---

# DO NOT EDIT!
# Automatically generated via doxygen2docusaurus by Doxygen.

slug: /api/classes/anonymous-sampleprofile-cpp-/sampleprofileloader
custom_edit_url: null
toc_max_heading_level: 4
keywords:
  - doxygen
  - reference
  - class

---

<div class="doxyPage">

# The `SampleProfileLoader` Class Reference

<p>Sample profile pass. <a href="#details">More...</a></p>

## Declaration

<div class="doxyDeclaration">
class anonymous{SampleProfile.cpp}::SampleProfileLoader { ... }
</div>

## Base class

<table class="doxyMembersIndex">

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">class</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/sampleprofileloaderbaseimpl">SampleProfileLoaderBaseImpl&lt;FT&gt;</a></td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a5133b642b31dcbfad681874ba97d5914">SampleProfileLoader</a> (StringRef Name, StringRef RemapName, ThinOrFullLTOPhase LTOPhase, IntrusiveRefCntPtr&lt; vfs::FileSystem &gt; FS, std::function&lt; AssumptionCache &amp;(Function &amp;)&gt; GetAssumptionCache, std::function&lt; TargetTransformInfo &amp;(Function &amp;)&gt; GetTargetTransformInfo, std::function&lt; const TargetLibraryInfo &amp;(Function &amp;)&gt; GetTLI, LazyCallGraph &amp;CG, bool DisableSampleProfileInlining, bool UseFlattenedProfile)</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a7e1da8085095c6d808713b280edb143b">doInitialization</a> (Module &amp;M, FunctionAnalysisManager *FAM=nullptr)</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a25da45ec2b5b7dacb22e831cb7aef0c5">runOnModule</a> (Module &amp;M, ModuleAnalysisManager *AM, ProfileSummaryInfo *_PSI)</td>
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

## Protected Member Functions Index

<table class="doxyMembersIndex">

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">bool</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a358b28b8ab641a2a22ed8849a2dff2cf">runOnFunction</a> (Function &amp;F, ModuleAnalysisManager *AM)</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a6f70814abe4749ddb1e8356c3584b2ac">emitAnnotations</a> (Function &amp;F)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Once all the branch weights are computed, we emit the MD_prof metadata on BB using the computed values for each of its branches. <a href="#a6f70814abe4749ddb1e8356c3584b2ac">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/erroror">ErrorOr</a>&lt; uint64_t &gt;</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#aa583009e488330c099a4ab23e2536d2f">getInstWeight</a> (const Instruction &amp;I) override</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/sampleprof/functionsamples">FunctionSamples</a> *</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a219e9fac05a219d48a97e03304f84613">findCalleeFunctionSamples</a> (const CallBase &amp;I) const</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Get the <a href="/web-llvm/docs/api/classes/llvm/sampleprof/functionsamples">FunctionSamples</a> for a call instruction. <a href="#a219e9fac05a219d48a97e03304f84613">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/sampleprof/functionsamples">FunctionSamples</a> *</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a2c88d6b3f033c87b7304db47133a930e">findFunctionSamples</a> (const Instruction &amp;I) const override</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">std::vector&lt; <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/sampleprof/functionsamples">FunctionSamples</a> * &gt;</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#abf8457f6ea82a821ee3fb08dae6246d9">findIndirectCallFunctionSamples</a> (const Instruction &amp;I, uint64_t &amp;Sum) const</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Returns a vector of <a href="/web-llvm/docs/api/classes/llvm/sampleprof/functionsamples">FunctionSamples</a> that are the indirect call targets of <span class="doxyComputerOutput">Inst</span>. <a href="#abf8457f6ea82a821ee3fb08dae6246d9">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">void</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#aa9137eda03e0c2cfd6eebaa55dfdd4cc">findExternalInlineCandidate</a> (CallBase *CB, const FunctionSamples *Samples, DenseSet&lt; GlobalValue::GUID &gt; &amp;InlinedGUIDs, uint64_t Threshold)</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ad5c772a0b61cb29106af3a4f9ae43d59">tryPromoteAndInlineCandidate</a> (Function &amp;F, InlineCandidate &amp;Candidate, uint64_t SumOrigin, uint64_t &amp;Sum, SmallVector&lt; CallBase *, 8 &gt; *InlinedCallSites=nullptr)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Attempt to promote indirect call and also inline the promoted call. <a href="#ad5c772a0b61cb29106af3a4f9ae43d59">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">bool</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#aa730b58924baf8f35394c2e5a0bb3714">inlineHotFunctions</a> (Function &amp;F, DenseSet&lt; GlobalValue::GUID &gt; &amp;InlinedGUIDs)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Iteratively inline hot callsites of a function. <a href="#aa730b58924baf8f35394c2e5a0bb3714">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">std::optional&lt; <a href="/web-llvm/docs/api/classes/llvm/inlinecost">InlineCost</a> &gt;</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ab8641bf75d896ad3caffd68a441c4a7e">getExternalInlineAdvisorCost</a> (CallBase &amp;CB)</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a1504c594e55b1808ae9f992f9783c8b0">getExternalInlineAdvisorShouldInline</a> (CallBase &amp;CB)</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/inlinecost">InlineCost</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a518b0cf18edfb9fb05aaa530550af870">shouldInlineCandidate</a> (InlineCandidate &amp;Candidate)</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a284bbebbcad19f7e38253a1a8df134b5">getInlineCandidate</a> (InlineCandidate *NewCandidate, CallBase *CB)</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#adb1dafd461988f3d8e687eabb99e108d">tryInlineCandidate</a> (InlineCandidate &amp;Candidate, SmallVector&lt; CallBase *, 8 &gt; *InlinedCallSites=nullptr)</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ae0bf03df2431c543590180658ce4709d">inlineHotFunctionsWithPriority</a> (Function &amp;F, DenseSet&lt; GlobalValue::GUID &gt; &amp;InlinedGUIDs)</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a902b6197889c703bbe3c087f8bcf0789">shouldInlineColdCallee</a> (CallBase &amp;CallInst)</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a64ec6ec160cdb088c22ec00f8e314822">emitOptimizationRemarksForInlineCandidates</a> (const SmallVectorImpl&lt; CallBase * &gt; &amp;Candidates, const Function &amp;F, bool Hot)</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a16e99ef185f55c3e45caf11c880998ff">promoteMergeNotInlinedContextSamples</a> (MapVector&lt; CallBase *, const FunctionSamples * &gt; NonInlinedCallSites, const Function &amp;F)</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">std::vector&lt; <a href="/web-llvm/docs/api/classes/llvm/function">Function</a> * &gt;</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a0f9647d7bd1eb0c38198f05b3d34d4f3">buildFunctionOrder</a> (Module &amp;M, LazyCallGraph &amp;CG)</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">std::unique_ptr&lt; <a href="/web-llvm/docs/api/classes/llvm/sampleprof/profiledcallgraph">ProfiledCallGraph</a> &gt;</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#af64b545a1de5a343850725733d522546">buildProfiledCallGraph</a> (Module &amp;M)</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#acf512f516130aaabdd835c48140c9e5c">generateMDProfMetadata</a> (Function &amp;F)</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#abf1045cfa542c9bf01c10bcf99262a2c">rejectHighStalenessProfile</a> (Module &amp;M, ProfileSummaryInfo *PSI, const SampleProfileMap &amp;Profiles)</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a35bb2baa976d7716a9752ad544e8134f">removePseudoProbeInstsDiscriminator</a> (Module &amp;M)</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> char *</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a7fa0621e771540b700bb1d6273ccb082">getAnnotatedRemarkPassName</a> () const</td>
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

## Protected Member Attributes Index

<table class="doxyMembersIndex">

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/sampleprof/hashkeymap">HashKeyMap</a>&lt; std::unordered_map, <a href="/web-llvm/docs/api/classes/llvm/sampleprof/functionid">FunctionId</a>, <a href="/web-llvm/docs/api/classes/llvm/function">Function</a> * &gt;</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a36a42d67af221fe58af6d4e4fa30ce96">SymbolMap</a></td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Map from function name to <a href="/web-llvm/docs/api/classes/llvm/function">Function</a> *. <a href="#a36a42d67af221fe58af6d4e4fa30ce96">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/sampleprof/hashkeymap">HashKeyMap</a>&lt; std::unordered_map, <a href="/web-llvm/docs/api/classes/llvm/sampleprof/functionid">FunctionId</a>, <a href="/web-llvm/docs/api/classes/llvm/sampleprof/functionid">FunctionId</a> &gt;</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ade23e6b6f4c8e772b888612e156b5344">FuncNameToProfNameMap</a></td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Map from function name to profile name generated by call-graph based profile fuzzy matching(–salvage-unused-profile). <a href="#ade23e6b6f4c8e772b888612e156b5344">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">std::function&lt; <a href="/web-llvm/docs/api/classes/llvm/assumptioncache">AssumptionCache</a> &amp;(<a href="/web-llvm/docs/api/classes/llvm/function">Function</a> &amp;)&gt;</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#aaa4377cfbfd513fba3113fa91210a0c4">GetAC</a></td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">std::function&lt; <a href="/web-llvm/docs/api/classes/llvm/targettransforminfo">TargetTransformInfo</a> &amp;(<a href="/web-llvm/docs/api/classes/llvm/function">Function</a> &amp;)&gt;</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#aa6421c02e92eda93cce39ae1adc23f45">GetTTI</a></td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">std::function&lt; <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/targetlibraryinfo">TargetLibraryInfo</a> &amp;(<a href="/web-llvm/docs/api/classes/llvm/function">Function</a> &amp;)&gt;</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ad152203aa6393f06c0b955e3f70b94dd">GetTLI</a></td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/lazycallgraph">LazyCallGraph</a> &amp;</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a79367a297c27b50b1a88acabf00f1070">CG</a></td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">std::unique_ptr&lt; <a href="/web-llvm/docs/api/classes/llvm/samplecontexttracker">SampleContextTracker</a> &gt;</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a61e8260e50a3374fc9cd3540068f856a">ContextTracker</a></td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Profile tracker for different context. <a href="#a61e8260e50a3374fc9cd3540068f856a">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/namespaces/llvm/#a5d737fb4258bb27586a1bffd557fbb49">ThinOrFullLTOPhase</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a16100da114bdba0571c38edc371835d8">LTOPhase</a></td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Flag indicating which LTO/ThinLTO phase the pass is invoked in. <a href="#a16100da114bdba0571c38edc371835d8">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> std::string</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ab7d55132a633847b63ce0cdadca0af02">AnnotatedPassName</a></td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">std::shared_ptr&lt; <a href="/web-llvm/docs/api/classes/llvm/sampleprof/profilesymbollist">ProfileSymbolList</a> &gt;</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a3329c2209e8b3bc0cd93bd6172ef16ca">PSL</a></td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Profle Symbol list tells whether a function name appears in the binary used to generate the current profile. <a href="#a3329c2209e8b3bc0cd93bd6172ef16ca">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">uint64_t</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a03dd9387104275f69afacd119f353c10">TotalCollectedSamples</a> = 0</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Total number of samples collected in this profile. <a href="#a03dd9387104275f69afacd119f353c10">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/densemap">DenseMap</a>&lt; <a href="/web-llvm/docs/api/classes/llvm/function">Function</a> *, <a href="/web-llvm/docs/api/structs/anonymous-sampleprofile-cpp-/sampleprofileloader/notinlinedprofileinfo">NotInlinedProfileInfo</a> &gt;</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a09c53287a76f1544e782601e437149be">notInlinedCallInfo</a></td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/densemap">DenseMap</a>&lt; uint64_t, <a href="/web-llvm/docs/api/classes/llvm/stringref">StringRef</a> &gt;</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a86674e88fdb911aab10f14aa01863d88">GUIDToFuncNameMap</a></td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/stringset">StringSet</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a13d326ade07b8cc14d4e307253b2797b">NamesInProfile</a></td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/denseset">llvm::DenseSet</a>&lt; uint64_t &gt;</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a99625599858fb55fe0892163548436b3">GUIDsInProfile</a></td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a08e4315133d1d023573bd96e627d0dc0">ProfAccForSymsInList</a></td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#aac6219556110a8ac4a20f7c6a49dc0c9">DisableSampleProfileInlining</a></td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a641b8ee0f58b045f31b9376e927a0b49">UseFlattenedProfile</a></td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">std::unique_ptr&lt; <a href="/web-llvm/docs/api/classes/llvm/inlineadvisor">InlineAdvisor</a> &gt;</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a7d8fb7d2b619a9afafc3add8e9c11eb9">ExternalInlineAdvisor</a></td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">std::unique_ptr&lt; <a href="/web-llvm/docs/api/classes/llvm/sampleprofilematcher">SampleProfileMatcher</a> &gt;</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a7bac1f5f852f643b10b9e02862e2b3ab">MatchingManager</a></td>
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

<p>Sample profile pass.</p>


<p>This pass reads profile data from the file specified by -sample-profile-file and annotates every affected function with the profile information found in that file.</p>


<p>Definition at line 465 of file <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/ipo/sampleprofile-cpp">SampleProfile.cpp</a>.</p>


<div class="doxySectionDef">

## Public Constructors

### SampleProfileLoader() {#a5133b642b31dcbfad681874ba97d5914}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">anonymous{SampleProfile.cpp}::SampleProfileLoader::SampleProfileLoader (<a href="/web-llvm/docs/api/classes/llvm/stringref">StringRef</a> Name, <a href="/web-llvm/docs/api/classes/llvm/stringref">StringRef</a> RemapName, <a href="/web-llvm/docs/api/namespaces/llvm/#a5d737fb4258bb27586a1bffd557fbb49">ThinOrFullLTOPhase</a> LTOPhase, <a href="/web-llvm/docs/api/classes/llvm/intrusiverefcntptr">IntrusiveRefCntPtr</a>&lt; <a href="/web-llvm/docs/api/classes/llvm/vfs/filesystem">vfs::FileSystem</a> &gt; FS, std::function&lt; <a href="/web-llvm/docs/api/classes/llvm/assumptioncache">AssumptionCache</a> &amp;(<a href="/web-llvm/docs/api/classes/llvm/function">Function</a> &amp;)&gt; GetAssumptionCache, std::function&lt; <a href="/web-llvm/docs/api/classes/llvm/targettransforminfo">TargetTransformInfo</a> &amp;(<a href="/web-llvm/docs/api/classes/llvm/function">Function</a> &amp;)&gt; GetTargetTransformInfo, std::function&lt; <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/targetlibraryinfo">TargetLibraryInfo</a> &amp;(<a href="/web-llvm/docs/api/classes/llvm/function">Function</a> &amp;)&gt; GetTLI, <a href="/web-llvm/docs/api/classes/llvm/lazycallgraph">LazyCallGraph</a> &amp; CG, bool DisableSampleProfileInlining, bool UseFlattenedProfile)</td>
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



<p>Definition at line 467 of file <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/ipo/sampleprofile-cpp">SampleProfile.cpp</a>.</p>


<p>References <a href="#ab7d55132a633847b63ce0cdadca0af02">AnnotatedPassName</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a5c2a5dcf016849f14d98c8bf8e01e659">llvm::AnnotateInlinePassName</a>, <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/ipo/sampleprofile-cpp/#a6249b41b02fca2bc7c121511ad72062b">AnnotateSampleProfileInlinePhase</a>, <a href="#a79367a297c27b50b1a88acabf00f1070">CG</a>, <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/ipo/sampleprofile-cpp/#ab4932d7673e6e1138d8a2671f16865d1">CSINLINE_DEBUG</a>, <a href="#aac6219556110a8ac4a20f7c6a49dc0c9">DisableSampleProfileInlining</a>, <a href="/web-llvm/docs/api/classes/llvm/sampleprofileloaderbaseimpl/#a12022aa707c271f81eae8ec0eebfae29">llvm::SampleProfileLoaderBaseImpl&lt; Function &gt;::FS</a>, <a href="#aaa4377cfbfd513fba3113fa91210a0c4">GetAC</a>, <a href="#ad152203aa6393f06c0b955e3f70b94dd">GetTLI</a>, <a href="#aa6421c02e92eda93cce39ae1adc23f45">GetTTI</a>, <a href="#a16100da114bdba0571c38edc371835d8">LTOPhase</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#abfc9c7ecf70f66901e439f7c04ef3dbb">llvm::move</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a051cd0cc5f9d159ee0960b13051e5939a5d1c7c4bd0b5e11993c6c4f8bb09c8a0">llvm::SampleProfileInliner</a>, <a href="/web-llvm/docs/api/classes/llvm/sampleprofileloaderbaseimpl/#a8914bae43b683a78d971e5954d781331">llvm::SampleProfileLoaderBaseImpl&lt; Function &gt;::SampleProfileLoaderBaseImpl</a> and <a href="#a641b8ee0f58b045f31b9376e927a0b49">UseFlattenedProfile</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Public Member Functions

### doInitialization() {#a7e1da8085095c6d808713b280edb143b}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool SampleProfileLoader::doInitialization (<a href="/web-llvm/docs/api/classes/llvm/module">Module</a> &amp; M, <a href="/web-llvm/docs/api/namespaces/llvm/#adce09a5a0de0e3177eb00e932734af2f">FunctionAnalysisManager</a> * FAM=nullptr)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 487 of file <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/ipo/sampleprofile-cpp">SampleProfile.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/ipo/sampleprofile-cpp/#af5f668624e8264858b5efb9127b3be47">AllowRecursiveInline</a>, <a href="/web-llvm/docs/api/namespaces/llvm/sampleprof/#a702f69807459cc25db5754a5f179d3fcaf6fbeb8fa9f451468611536b00878d41">llvm::sampleprof::Base</a>, <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/ipo/sampleprofile-cpp/#a9eaaeedd35128b9508715b2c16dd58f5">CallsitePrioritizedInline</a>, <a href="#a79367a297c27b50b1a88acabf00f1070">CG</a>, <a href="#a61e8260e50a3374fc9cd3540068f856a">ContextTracker</a>, <a href="/web-llvm/docs/api/classes/llvm/sampleprofileloaderbaseimpl/#a52673282884569984ceee1e4f7119a50">llvm::SampleProfileLoaderBaseImpl&lt; Function &gt;::CoverageTracker</a>, <a href="/web-llvm/docs/api/classes/llvm/sampleprof/sampleprofilereader/#a1f2d1c30eab01a2f5ae485d3c3cbf5b4">llvm::sampleprof::SampleProfileReader::create</a>, <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/ipo/sampleprofile-cpp/#a3ea40d9c4ddb417257d8c7c5f8bfe981">DisableSampleLoaderInlining</a>, <a href="#aac6219556110a8ac4a20f7c6a49dc0c9">DisableSampleProfileInlining</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#abfcab32516704f11d146c757f402ad5ca1cde8c8828756cdaf2a93260e247ae31">llvm::DS_Warning</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#ae4599fe5d1385154f1bfbc41a10495c5">llvm::EnableExtTspBlockPlacement</a>, <a href="#a7d8fb7d2b619a9afafc3add8e9c11eb9">ExternalInlineAdvisor</a>, <a href="/web-llvm/docs/api/files/lib/lib/passes/passbuilderbindings-cpp/#a83c7e5ca51099e4efa895791a02fb0ed">FAM</a>, <a href="/web-llvm/docs/api/classes/llvm/sampleprofileloaderbaseimpl/#aa25c9c0884c2fc1dc621c881c00485f8">llvm::SampleProfileLoaderBaseImpl&lt; Function &gt;::Filename</a>, <a href="/web-llvm/docs/api/classes/llvm/sampleprof/profileconverter/#aa3ffda78d2adde5ff1916294f9fe3488">llvm::sampleprof::ProfileConverter::flattenProfile</a>, <a href="/web-llvm/docs/api/classes/llvm/sampleprofileloaderbaseimpl/#a12022aa707c271f81eae8ec0eebfae29">llvm::SampleProfileLoaderBaseImpl&lt; Function &gt;::FS</a>, <a href="#ade23e6b6f4c8e772b888612e156b5344">FuncNameToProfNameMap</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a903adbd42316e51df3cda640d664aa65">llvm::getReplayInlineAdvisor</a>, <a href="#a99625599858fb55fe0892163548436b3">GUIDsInProfile</a>, <a href="#a86674e88fdb911aab10f14aa01863d88">GUIDToFuncNameMap</a>, <a href="#a16100da114bdba0571c38edc371835d8">LTOPhase</a>, <a href="#a7bac1f5f852f643b10b9e02862e2b3ab">MatchingManager</a>, <a href="#a13d326ade07b8cc14d4e307253b2797b">NamesInProfile</a>, <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/ipo/sampleprofile-cpp/#a997d20da5b25193880115dc8a0b5e4ee">PersistProfileStaleness</a>, <a href="/web-llvm/docs/api/classes/llvm/sampleprofileloaderbaseimpl/#a8a061b4f421152b76653f15e18bec185">llvm::SampleProfileLoaderBaseImpl&lt; Function &gt;::ProbeManager</a>, <a href="#a08e4315133d1d023573bd96e627d0dc0">ProfAccForSymsInList</a>, <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/ipo/sampleprofile-cpp/#a88e2b32b6c2ab29b0b4470f5a1a32364">ProfileAccurateForSymsInList</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#ad68079dd1eac0685dbf374e088d79b64">llvm::ProfileInlineLimitMax</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a1118e6eca7dab8dfcd484ccb179533b0">llvm::ProfileInlineLimitMin</a>, <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/ipo/sampleprofile-cpp/#a477f441a65d57a1d0bff97e993e0f5d3">ProfileInlineReplayFallback</a>, <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/ipo/sampleprofile-cpp/#a732d61bd469914910adee6ed8c8c4a38">ProfileInlineReplayFile</a>, <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/ipo/sampleprofile-cpp/#af61ae5b7d50b9b36cc3a2350ded45f82">ProfileInlineReplayFormat</a>, <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/ipo/sampleprofile-cpp/#ab75eb24423b8e8d730f81eec23e93f43">ProfileInlineReplayScope</a>, <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/ipo/sampleprofile-cpp/#af00e1c8a074b97aedd1a2db33dea6753">ProfileSampleAccurate</a>, <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/ipo/sampleprofile-cpp/#ada8f2c564085d598909fb28464614812">ProfileSizeInline</a>, <a href="#a3329c2209e8b3bc0cd93bd6172ef16ca">PSL</a>, <a href="/web-llvm/docs/api/classes/llvm/sampleprofileloaderbaseimpl/#a6cda1f8872cce456c1ec260c8ef7aa24">llvm::SampleProfileLoaderBaseImpl&lt; Function &gt;::Reader</a>, <a href="/web-llvm/docs/api/classes/llvm/sampleprofileloaderbaseimpl/#ad0b57e56868a6c60929c62f1494628af">llvm::SampleProfileLoaderBaseImpl&lt; Function &gt;::RemappingFilename</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a051cd0cc5f9d159ee0960b13051e5939ab507b35664283545eb19ab0fba3c8247">llvm::ReplaySampleProfileInliner</a>, <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/ipo/sampleprofile-cpp/#accaf075320be45eaba2a9cbf611368a9">ReportProfileStaleness</a>, <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/instrumentation/memprofiler-cpp/#a8fcac4cee0537749800b9b24859dc7dd">SalvageStaleProfile</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a6074db8acc6aa7a2f810d5918a793e87">llvm::SampleProfileUseProfi</a>, <a href="#a36a42d67af221fe58af6d4e4fa30ce96">SymbolMap</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a5d737fb4258bb27586a1bffd557fbb49a5c0973ae3fdda34daff394f30f81f19b">llvm::ThinLTOPostLink</a>, <a href="#a641b8ee0f58b045f31b9376e927a0b49">UseFlattenedProfile</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a7ae09d3a026a47bf0a9332fe3ef5ad88">llvm::UseIterativeBFIInference</a>, <a href="/web-llvm/docs/api/classes/llvm/sampleprof/functionsamples/#afddaa81316d56f125de69793e0ddb33c">llvm::sampleprof::FunctionSamples::UseMD5</a> and <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/ipo/sampleprofile-cpp/#ad07d06e65e4610fb8ac7b13e868ec1c9">UsePreInlinerDecision</a>.</p>

</div>
</div>

### runOnModule() {#a25da45ec2b5b7dacb22e831cb7aef0c5}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool SampleProfileLoader::runOnModule (<a href="/web-llvm/docs/api/classes/llvm/module">Module</a> &amp; M, <a href="/web-llvm/docs/api/namespaces/llvm/#af9c9208365fd9ce11392b4d79485e259">ModuleAnalysisManager</a> * AM, <a href="/web-llvm/docs/api/classes/llvm/profilesummaryinfo">ProfileSummaryInfo</a> * _PSI)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 488 of file <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/ipo/sampleprofile-cpp">SampleProfile.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/silowercontrolflow-cpp/#a4868c5d81c5ccc98c47aeab6244346a0">assert</a>, <a href="#a0f9647d7bd1eb0c38198f05b3d34d4f3">buildFunctionOrder</a>, <a href="#a79367a297c27b50b1a88acabf00f1070">CG</a>, <a href="/web-llvm/docs/api/classes/llvm/sampleprofileloaderbaseimpl/#ae9bae46af4ef474d7f244e4f9b67e188">llvm::SampleProfileLoaderBaseImpl&lt; Function &gt;::clearFunctionData</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a22eeee01734061ac1b31ccd994c49eef">llvm::dyn_cast</a>, <a href="/web-llvm/docs/api/classes/llvm/stringref/#a2dc80c585ad5882da8cae7b5968f7e74">llvm::StringRef::empty</a>, <a href="/web-llvm/docs/api/files/lib/lib/support/md5-cpp/#a96d73bbd7af15cb1fc38c3f4a3bd82e9">F</a>, <a href="#ade23e6b6f4c8e772b888612e156b5344">FuncNameToProfNameMap</a>, <a href="/web-llvm/docs/api/classes/llvm/sampleprof/functionsamples/#aa7122a07ea48e47fc71083e68b829003">llvm::sampleprof::FunctionSamples::getCanonicalFnName</a>, <a href="#a86674e88fdb911aab10f14aa01863d88">GUIDToFuncNameMap</a>, <a href="/web-llvm/docs/api/files/lib/lib/support/md5-cpp/#ac0eafdc9ee161b71e7af98af736952fd">I</a>, <a href="#a7bac1f5f852f643b10b9e02862e2b3ab">MatchingManager</a>, <a href="#a09c53287a76f1544e782601e437149be">notInlinedCallInfo</a>, <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/ipo/sampleprofile-cpp/#a997d20da5b25193880115dc8a0b5e4ee">PersistProfileStaleness</a>, <a href="/web-llvm/docs/api/classes/llvm/sampleprof/functionsamples/#a67e19eb484a5eaa31b22894398e258c0">llvm::sampleprof::FunctionSamples::ProfileIsCS</a>, <a href="/web-llvm/docs/api/classes/llvm/sampleprof/functionsamples/#aa37fe7429ffcf70c306c27a55d714d31">llvm::sampleprof::FunctionSamples::ProfileIsProbeBased</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#afe8cddc1b878bbfc7598e672f96cfbf1">llvm::PseudoProbeDescMetadataName</a>, <a href="/web-llvm/docs/api/classes/llvm/sampleprofileloaderbaseimpl/#ae49ac2191e91a12f7ed0b92b2b72ebbe">llvm::SampleProfileLoaderBaseImpl&lt; Function &gt;::PSI</a>, <a href="/web-llvm/docs/api/classes/llvm/profilesummary/#aa5aa682b3904e88749fa973b3da370c2a0c86eaeebf5b6120b601ecc93a1c2e3a">llvm::ProfileSummary::PSK_Sample</a>, <a href="/web-llvm/docs/api/classes/llvm/sampleprofileloaderbaseimpl/#a6cda1f8872cce456c1ec260c8ef7aa24">llvm::SampleProfileLoaderBaseImpl&lt; Function &gt;::Reader</a>, <a href="#abf1045cfa542c9bf01c10bcf99262a2c">rejectHighStalenessProfile</a>, <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/ipo/sampleprofile-cpp/#a43f756cf4ee4b9d99c35677a3aa852af">RemoveProbeAfterProfileAnnotation</a>, <a href="#a35bb2baa976d7716a9752ad544e8134f">removePseudoProbeInstsDiscriminator</a>, <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/ipo/sampleprofile-cpp/#accaf075320be45eaba2a9cbf611368a9">ReportProfileStaleness</a>, <a href="#a358b28b8ab641a2a22ed8849a2dff2cf">runOnFunction</a>, <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/instrumentation/memprofiler-cpp/#a8fcac4cee0537749800b9b24859dc7dd">SalvageStaleProfile</a>, <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/ipo/sampleprofile-cpp/#a176dcdd54b914f2847535fc7c8f1f77b">SalvageUnusedProfile</a>, <a href="#a36a42d67af221fe58af6d4e4fa30ce96">SymbolMap</a>, <a href="#a03dd9387104275f69afacd119f353c10">TotalCollectedSamples</a> and <a href="/web-llvm/docs/api/namespaces/llvm/#aa7cd2cc36098475563ad0fd3371df2a6">llvm::updateProfileCallee</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Protected Member Functions

### buildFunctionOrder() {#a0f9647d7bd1eb0c38198f05b3d34d4f3}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">std::vector&lt; Function * &gt; SampleProfileLoader::buildFunctionOrder (<a href="/web-llvm/docs/api/classes/llvm/module">Module</a> &amp; M, <a href="/web-llvm/docs/api/classes/llvm/lazycallgraph">LazyCallGraph</a> &amp; CG)</td>
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



<p>Definition at line 528 of file <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/ipo/sampleprofile-cpp">SampleProfile.cpp</a>.</p>


<p>References <a href="#af64b545a1de5a343850725733d522546">buildProfiledCallGraph</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a4d05aa2854cf8b7927d9f162180d1a37">llvm::buildTopDownFuncOrder</a>, <a href="#a79367a297c27b50b1a88acabf00f1070">CG</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a7c46c742c31be54870e2038048e6b391">llvm::dbgs</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a9a7b5c68c90f85baaedaa854cc5002cc">llvm::errs</a>, <a href="/web-llvm/docs/api/files/lib/lib/support/md5-cpp/#a96d73bbd7af15cb1fc38c3f4a3bd82e9">F</a>, <a href="/web-llvm/docs/api/classes/llvm/scc-iterator/#a7d6ec03718a5e48f3ec7ce22fefcb91d">llvm::scc_iterator&lt; GraphT, GT &gt;::isAtEnd</a>, <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/support/debug-h/#a196897517069dda1bdb549e24468f7d7">LLVM_DEBUG</a>, <a href="/web-llvm/docs/api/classes/llvm/sampleprof/functionsamples/#a67e19eb484a5eaa31b22894398e258c0">llvm::sampleprof::FunctionSamples::ProfileIsCS</a>, <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/ipo/sampleprofile-cpp/#a8b16dbb3ebefd05908afe3a7874d6353">ProfileMergeInlinee</a>, <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/ipo/sampleprofile-cpp/#aeeed05c14d5103af2df4ef16b3d12674">ProfileTopDownLoad</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/nvptx/nvvmintrrange-cpp/#a34bd74317e3f04bfc4318c2d1a470877">Range</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a3c1a67796e24a843db8a6766baa54c21">llvm::scc_begin</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#ac5e4f143be554153513191443c4709f6">llvm::skipProfileForFunction</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#ac626ee70ac28610543aa590dab04e81b">llvm::SortProfiledSCC</a>, <a href="#a36a42d67af221fe58af6d4e4fa30ce96">SymbolMap</a> and <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/ipo/sampleprofile-cpp/#ab5c0de16382c784463afd1d0749521b2">UseProfiledCallGraph</a>.</p>


<p>Referenced by <a href="#a25da45ec2b5b7dacb22e831cb7aef0c5">runOnModule</a>.</p>

</div>
</div>

### buildProfiledCallGraph() {#af64b545a1de5a343850725733d522546}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">std::unique_ptr&lt; ProfiledCallGraph &gt; SampleProfileLoader::buildProfiledCallGraph (<a href="/web-llvm/docs/api/classes/llvm/module">Module</a> &amp; M)</td>
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



<p>Definition at line 529 of file <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/ipo/sampleprofile-cpp">SampleProfile.cpp</a>.</p>


<p>References <a href="#a61e8260e50a3374fc9cd3540068f856a">ContextTracker</a>, <a href="/web-llvm/docs/api/files/lib/lib/support/md5-cpp/#a96d73bbd7af15cb1fc38c3f4a3bd82e9">F</a>, <a href="/web-llvm/docs/api/classes/llvm/sampleprof/functionsamples/#aa7122a07ea48e47fc71083e68b829003">llvm::sampleprof::FunctionSamples::getCanonicalFnName</a>, <a href="/web-llvm/docs/api/namespaces/llvm/sampleprof/#a012731cbc58856aff956543ab824eb8d">llvm::sampleprof::getRepInFormat</a>, <a href="/web-llvm/docs/api/classes/llvm/sampleprof/functionsamples/#a67e19eb484a5eaa31b22894398e258c0">llvm::sampleprof::FunctionSamples::ProfileIsCS</a>, <a href="/web-llvm/docs/api/classes/llvm/sampleprofileloaderbaseimpl/#a6cda1f8872cce456c1ec260c8ef7aa24">llvm::SampleProfileLoaderBaseImpl&lt; Function &gt;::Reader</a> and <a href="/web-llvm/docs/api/namespaces/llvm/#ac5e4f143be554153513191443c4709f6">llvm::skipProfileForFunction</a>.</p>


<p>Referenced by <a href="#a0f9647d7bd1eb0c38198f05b3d34d4f3">buildFunctionOrder</a>.</p>

</div>
</div>

### emitAnnotations() {#a6f70814abe4749ddb1e8356c3584b2ac}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool SampleProfileLoader::emitAnnotations (<a href="/web-llvm/docs/api/classes/llvm/function">Function</a> &amp; F)</td>
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

<p>Once all the branch weights are computed, we emit the MD_prof metadata on BB using the computed values for each of its branches.</p>


<dl class="doxyParamsList">
<dt class="doxyParamsTableTitle">Parameters</dt>
<dd>
<table class="doxyParamsTable">
<tr class="doxyParamItem">
<td class="doxyParamItemName">F</td>
<td class="doxyParamItemDescription"><p>The function to query.</p></td>
</tr>
</table>
</dd>
</dl>

<dl class="doxySectionUser">
<dt>Returns</dt>
<dd><p>true if <span class="doxyComputerOutput">F</span> was modified. Returns false, otherwise.</p></dd>
</dl>


<p>Definition at line 493 of file <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/ipo/sampleprofile-cpp">SampleProfile.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/ipo/sampleprofile-cpp/#a9eaaeedd35128b9508715b2c16dd58f5">CallsitePrioritizedInline</a>, <a href="/web-llvm/docs/api/classes/llvm/sampleprofileloaderbaseimpl/#a040b98a945772423eab83d2ce02f984a">llvm::SampleProfileLoaderBaseImpl&lt; Function &gt;::computeAndPropagateWeights</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a7c46c742c31be54870e2038048e6b391">llvm::dbgs</a>, <a href="/web-llvm/docs/api/classes/llvm/sampleprofileloaderbaseimpl/#a9da04aa71aaa9243bb7efe549f1dd758">llvm::SampleProfileLoaderBaseImpl&lt; Function &gt;::emitCoverageRemarks</a>, <a href="/web-llvm/docs/api/files/lib/lib/support/md5-cpp/#a96d73bbd7af15cb1fc38c3f4a3bd82e9">F</a>, <a href="#acf512f516130aaabdd835c48140c9e5c">generateMDProfMetadata</a>, <a href="/web-llvm/docs/api/classes/llvm/sampleprofileloaderbaseimpl/#a3bb6939c9a307a2d7a2bc20363b5433c">llvm::SampleProfileLoaderBaseImpl&lt; Function &gt;::getFunctionLoc</a>, <a href="#aa730b58924baf8f35394c2e5a0bb3714">inlineHotFunctions</a>, <a href="#ae0bf03df2431c543590180658ce4709d">inlineHotFunctionsWithPriority</a>, <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/support/debug-h/#a196897517069dda1bdb549e24468f7d7">LLVM_DEBUG</a>, <a href="/web-llvm/docs/api/classes/llvm/sampleprofileloaderbaseimpl/#a8a061b4f421152b76653f15e18bec185">llvm::SampleProfileLoaderBaseImpl&lt; Function &gt;::ProbeManager</a>, <a href="/web-llvm/docs/api/classes/llvm/sampleprof/functionsamples/#aa37fe7429ffcf70c306c27a55d714d31">llvm::sampleprof::FunctionSamples::ProfileIsProbeBased</a>, <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/instrumentation/memprofiler-cpp/#a8fcac4cee0537749800b9b24859dc7dd">SalvageStaleProfile</a> and <a href="/web-llvm/docs/api/classes/llvm/sampleprofileloaderbaseimpl/#ad9ec5be72117476a75c7dd1cc59d03f1">llvm::SampleProfileLoaderBaseImpl&lt; Function &gt;::Samples</a>.</p>


<p>Referenced by <a href="#a358b28b8ab641a2a22ed8849a2dff2cf">runOnFunction</a>.</p>

</div>
</div>

### emitOptimizationRemarksForInlineCandidates() {#a64ec6ec160cdb088c22ec00f8e314822}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void SampleProfileLoader::emitOptimizationRemarksForInlineCandidates (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/smallvectorimpl">SmallVectorImpl</a>&lt; <a href="/web-llvm/docs/api/classes/llvm/callbase">CallBase</a> * &gt; &amp; Candidates, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/function">Function</a> &amp; F, bool Hot)</td>
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



<p>Definition at line 522 of file <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/ipo/sampleprofile-cpp">SampleProfile.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/files/lib/lib/support/md5-cpp/#a96d73bbd7af15cb1fc38c3f4a3bd82e9">F</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a59c007354dfad2f618a37e6efaf7cd9ba4194726ee334e1085d93e002837b73f0">llvm::Hot</a>, <a href="/web-llvm/docs/api/files/lib/lib/support/md5-cpp/#ac0eafdc9ee161b71e7af98af736952fd">I</a> and <a href="/web-llvm/docs/api/classes/llvm/sampleprofileloaderbaseimpl/#a293c85647f9dcb78f29ad5ab31e5a7f9">llvm::SampleProfileLoaderBaseImpl&lt; Function &gt;::ORE</a>.</p>


<p>Referenced by <a href="#aa730b58924baf8f35394c2e5a0bb3714">inlineHotFunctions</a>.</p>

</div>
</div>

### findCalleeFunctionSamples() {#a219e9fac05a219d48a97e03304f84613}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">const FunctionSamples * SampleProfileLoader::findCalleeFunctionSamples (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/callbase">CallBase</a> &amp; Inst)</td>
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

<p>Get the <a href="/web-llvm/docs/api/classes/llvm/sampleprof/functionsamples">FunctionSamples</a> for a call instruction.</p>


<p>The <a href="/web-llvm/docs/api/classes/llvm/sampleprof/functionsamples">FunctionSamples</a> of a call/invoke instruction <span class="doxyComputerOutput">Inst</span> is the inlined instance in which that call instruction is calling to. It contains all samples that resides in the inlined instance. We first find the inlined instance in which the call instruction is from, then we traverse its children to find the callsite with the matching location.</p>


<dl class="doxyParamsList">
<dt class="doxyParamsTableTitle">Parameters</dt>
<dd>
<table class="doxyParamsTable">
<tr class="doxyParamItem">
<td class="doxyParamItemName">Inst</td>
<td class="doxyParamItemDescription"><p>Call/Invoke instruction to query.</p></td>
</tr>
</table>
</dd>
</dl>

<dl class="doxySectionUser">
<dt>Returns</dt>
<dd><p>The <a href="/web-llvm/docs/api/classes/llvm/sampleprof/functionsamples">FunctionSamples</a> pointer to the inlined instance.</p></dd>
</dl>


<p>Definition at line 495 of file <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/ipo/sampleprofile-cpp">SampleProfile.cpp</a>.</p>


<p>References <a href="#a61e8260e50a3374fc9cd3540068f856a">ContextTracker</a>, <a href="#a2c88d6b3f033c87b7304db47133a930e">findFunctionSamples</a>, <a href="/web-llvm/docs/api/classes/llvm/sampleprofileloaderbaseimpl/#a12022aa707c271f81eae8ec0eebfae29">llvm::SampleProfileLoaderBaseImpl&lt; Function &gt;::FS</a>, <a href="#ade23e6b6f4c8e772b888612e156b5344">FuncNameToProfNameMap</a>, <a href="/web-llvm/docs/api/classes/llvm/callbase/#a2b1ae7cf1bafdd43d1fee4c6ad0a2913">llvm::CallBase::getCalledFunction</a>, <a href="/web-llvm/docs/api/classes/llvm/sampleprof/functionsamples/#aeea4c49a1040f9305f6a09d7d7815544">llvm::sampleprof::FunctionSamples::getCallSiteIdentifier</a>, <a href="/web-llvm/docs/api/classes/llvm/instruction/#a4b8faae4ff9e7434a1d226d03d15dcd2">llvm::Instruction::getDebugLoc</a>, <a href="/web-llvm/docs/api/classes/llvm/sampleprof/functionsamples/#a67e19eb484a5eaa31b22894398e258c0">llvm::sampleprof::FunctionSamples::ProfileIsCS</a> and <a href="/web-llvm/docs/api/classes/llvm/sampleprofileloaderbaseimpl/#a6cda1f8872cce456c1ec260c8ef7aa24">llvm::SampleProfileLoaderBaseImpl&lt; Function &gt;::Reader</a>.</p>


<p>Referenced by <a href="#a284bbebbcad19f7e38253a1a8df134b5">getInlineCandidate</a>, <a href="#aa583009e488330c099a4ab23e2536d2f">getInstWeight</a>, <a href="#aa730b58924baf8f35394c2e5a0bb3714">inlineHotFunctions</a> and <a href="#ae0bf03df2431c543590180658ce4709d">inlineHotFunctionsWithPriority</a>.</p>

</div>
</div>

### findExternalInlineCandidate() {#aa9137eda03e0c2cfd6eebaa55dfdd4cc}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void SampleProfileLoader::findExternalInlineCandidate (<a href="/web-llvm/docs/api/classes/llvm/callbase">CallBase</a> * CB, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/sampleprof/functionsamples">FunctionSamples</a> * Samples, <a href="/web-llvm/docs/api/classes/llvm/denseset">DenseSet</a>&lt; <a href="/web-llvm/docs/api/classes/llvm/globalvalue/#a3af0428ec6e48cb2f05c199b7b9f7e07">GlobalValue::GUID</a> &gt; &amp; InlinedGUIDs, uint64_t Threshold)</td>
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



<p>Definition at line 500 of file <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/ipo/sampleprofile-cpp">SampleProfile.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/namespaces/llvm/sampleprof/#a9c9cec0dc85381494fb418ae0e88a40fa9a35039dfc5e52a8ee9289957a726bee">llvm::sampleprof::ContextShouldBeInlined</a>, <a href="#a61e8260e50a3374fc9cd3540068f856a">ContextTracker</a>, <a href="/web-llvm/docs/api/classes/llvm/sampleprof/functionsamples/#afd62779d71a74d2db69f4fde48b37893">llvm::sampleprof::FunctionSamples::getBodySamples</a>, <a href="/web-llvm/docs/api/classes/llvm/callbase/#a2b1ae7cf1bafdd43d1fee4c6ad0a2913">llvm::CallBase::getCalledFunction</a>, <a href="/web-llvm/docs/api/classes/llvm/sampleprof/functionsamples/#ad117577730085f895045fc7ff90d8fc2">llvm::sampleprof::FunctionSamples::getContext</a>, <a href="#a1504c594e55b1808ae9f992f9783c8b0">getExternalInlineAdvisorShouldInline</a>, <a href="/web-llvm/docs/api/classes/llvm/sampleprof/functionsamples/#a7ff8c2d016ae9169f35cdd1d1aaa1564">llvm::sampleprof::FunctionSamples::getFunction</a>, <a href="/web-llvm/docs/api/classes/llvm/globalvalue/#a6811428caf500217f319c74e80900c14">llvm::GlobalValue::getGUID</a>, <a href="/web-llvm/docs/api/classes/llvm/sampleprof/functionsamples/#afb077bf8dc20e4016e83042d3f784d32">llvm::sampleprof::FunctionSamples::getGUID</a>, <a href="/web-llvm/docs/api/classes/llvm/sampleprof/functionsamples/#af757985efc97179779ea3fc9e84f4735">llvm::sampleprof::FunctionSamples::getHeadSamplesEstimate</a>, <a href="/web-llvm/docs/api/classes/llvm/value/#adb5c319f5905c1d3ca9eb5df546388c5">llvm::Value::getName</a>, <a href="/web-llvm/docs/api/classes/llvm/sampleprof/samplecontext/#acddf84ace68d71cc96ecfdf7da44da58">llvm::sampleprof::SampleContext::hasAttribute</a>, <a href="/web-llvm/docs/api/classes/llvm/detail/densesetimpl/#a1b0f3ebdced8fce4b22c6a63b25d9525">llvm::detail::DenseSetImpl&lt; ValueT, MapTy, ValueInfoT &gt;::insert</a>, <a href="/web-llvm/docs/api/classes/llvm/sampleprof/functionsamples/#a67e19eb484a5eaa31b22894398e258c0">llvm::sampleprof::FunctionSamples::ProfileIsCS</a>, <a href="/web-llvm/docs/api/classes/llvm/sampleprofileloaderbaseimpl/#ad9ec5be72117476a75c7dd1cc59d03f1">llvm::SampleProfileLoaderBaseImpl&lt; Function &gt;::Samples</a>, <a href="#a36a42d67af221fe58af6d4e4fa30ce96">SymbolMap</a> and <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/ipo/sampleprofile-cpp/#ad07d06e65e4610fb8ac7b13e868ec1c9">UsePreInlinerDecision</a>.</p>


<p>Referenced by <a href="#aa730b58924baf8f35394c2e5a0bb3714">inlineHotFunctions</a> and <a href="#ae0bf03df2431c543590180658ce4709d">inlineHotFunctionsWithPriority</a>.</p>

</div>
</div>

### findFunctionSamples() {#a2c88d6b3f033c87b7304db47133a930e}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">const FunctionSamples * SampleProfileLoader::findFunctionSamples (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/instruction">Instruction</a> &amp; I)</td>
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



<p>Definition at line 497 of file <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/ipo/sampleprofile-cpp">SampleProfile.cpp</a>.</p>


<p>References <a href="#a61e8260e50a3374fc9cd3540068f856a">ContextTracker</a>, <a href="/web-llvm/docs/api/classes/llvm/sampleprofileloaderbaseimpl/#aeacafab53cd915d0ff8922dcb398fbe1">llvm::SampleProfileLoaderBaseImpl&lt; Function &gt;::DILocation2SampleMap</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a7b3e8a01dfede6141c79e012a44ec9e4">llvm::extractProbe</a>, <a href="#ade23e6b6f4c8e772b888612e156b5344">FuncNameToProfNameMap</a>, <a href="/web-llvm/docs/api/classes/llvm/instruction/#a4b8faae4ff9e7434a1d226d03d15dcd2">llvm::Instruction::getDebugLoc</a>, <a href="/web-llvm/docs/api/classes/llvm/sampleprof/functionsamples/#a67e19eb484a5eaa31b22894398e258c0">llvm::sampleprof::FunctionSamples::ProfileIsCS</a>, <a href="/web-llvm/docs/api/classes/llvm/sampleprof/functionsamples/#aa37fe7429ffcf70c306c27a55d714d31">llvm::sampleprof::FunctionSamples::ProfileIsProbeBased</a>, <a href="/web-llvm/docs/api/classes/llvm/sampleprofileloaderbaseimpl/#a6cda1f8872cce456c1ec260c8ef7aa24">llvm::SampleProfileLoaderBaseImpl&lt; Function &gt;::Reader</a> and <a href="/web-llvm/docs/api/classes/llvm/sampleprofileloaderbaseimpl/#ad9ec5be72117476a75c7dd1cc59d03f1">llvm::SampleProfileLoaderBaseImpl&lt; Function &gt;::Samples</a>.</p>


<p>Referenced by <a href="#a219e9fac05a219d48a97e03304f84613">findCalleeFunctionSamples</a>, <a href="#abf8457f6ea82a821ee3fb08dae6246d9">findIndirectCallFunctionSamples</a> and <a href="#acf512f516130aaabdd835c48140c9e5c">generateMDProfMetadata</a>.</p>

</div>
</div>

### findIndirectCallFunctionSamples() {#abf8457f6ea82a821ee3fb08dae6246d9}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">std::vector&lt; const FunctionSamples * &gt; SampleProfileLoader::findIndirectCallFunctionSamples (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/instruction">Instruction</a> &amp; Inst, uint64_t &amp; Sum)</td>
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

<p>Returns a vector of <a href="/web-llvm/docs/api/classes/llvm/sampleprof/functionsamples">FunctionSamples</a> that are the indirect call targets of <span class="doxyComputerOutput">Inst</span>.</p>


<p>The vector is sorted by the total number of samples. Stores the total call count of the indirect call in <span class="doxyComputerOutput">Sum</span>.</p>


<p>Definition at line 499 of file <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/ipo/sampleprofile-cpp">SampleProfile.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/silowercontrolflow-cpp/#a4868c5d81c5ccc98c47aeab6244346a0">assert</a>, <a href="#a61e8260e50a3374fc9cd3540068f856a">ContextTracker</a>, <a href="#a2c88d6b3f033c87b7304db47133a930e">findFunctionSamples</a>, <a href="/web-llvm/docs/api/classes/llvm/sampleprofileloaderbaseimpl/#a12022aa707c271f81eae8ec0eebfae29">llvm::SampleProfileLoaderBaseImpl&lt; Function &gt;::FS</a>, <a href="/web-llvm/docs/api/classes/llvm/sampleprof/functionsamples/#aeea4c49a1040f9305f6a09d7d7815544">llvm::sampleprof::FunctionSamples::getCallSiteIdentifier</a>, <a href="/web-llvm/docs/api/classes/llvm/instruction/#a4b8faae4ff9e7434a1d226d03d15dcd2">llvm::Instruction::getDebugLoc</a>, <a href="/web-llvm/docs/api/classes/llvm/sampleprof/functionsamples/#a67e19eb484a5eaa31b22894398e258c0">llvm::sampleprof::FunctionSamples::ProfileIsCS</a> and <a href="/web-llvm/docs/api/namespaces/llvm/#a74cdbd1e4f731e7d7cd83461b8b1de0b">llvm::sort</a>.</p>


<p>Referenced by <a href="#aa730b58924baf8f35394c2e5a0bb3714">inlineHotFunctions</a> and <a href="#ae0bf03df2431c543590180658ce4709d">inlineHotFunctionsWithPriority</a>.</p>

</div>
</div>

### generateMDProfMetadata() {#acf512f516130aaabdd835c48140c9e5c}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void SampleProfileLoader::generateMDProfMetadata (<a href="/web-llvm/docs/api/classes/llvm/function">Function</a> &amp; F)</td>
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



<p>Definition at line 530 of file <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/ipo/sampleprofile-cpp">SampleProfile.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/classes/llvm/sampleprof/samplerecord/#abfed1f1dfd251457d62aa20c4c4e95eb">llvm::sampleprof::SampleRecord::adjustCallTargets</a>, <a href="/web-llvm/docs/api/classes/llvm/sampleprofileloaderbaseimpl/#afd962f6862c0fa756bc3d8e2e751a955">llvm::SampleProfileLoaderBaseImpl&lt; Function &gt;::BlockWeights</a>, <a href="/web-llvm/docs/api/namespaces/llvm/callingconv/#ac6aa1387c4375260e2468eb5a77fdb4cafd841a49aec1539bc88abc8ff9e170fb">llvm::CallingConv::C</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#ac4fc845f5ed92de63cd4474f128f5fc5">llvm::cast</a>, <a href="/web-llvm/docs/api/namespaces/llvm/misexpect/#a4c52059f91406714507309d168ff95b8">llvm::misexpect::checkExpectAnnotations</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a7c46c742c31be54870e2038048e6b391">llvm::dbgs</a>, <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/adt/genericcycleimpl-h/#ad78e062f62e0d6e453941fb4ca843e4d">DEBUG_TYPE</a>, <a href="/web-llvm/docs/api/classes/llvm/sampleprofileloaderbaseimpl/#a25b4d69386a27e339e802ac43d47fe33">llvm::SampleProfileLoaderBaseImpl&lt; Function &gt;::EdgeWeights</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a7b3e8a01dfede6141c79e012a44ec9e4">llvm::extractProbe</a>, <a href="/web-llvm/docs/api/classes/llvm/instruction/#a51d5735829e1f043630dd403f01d4219">llvm::Instruction::extractProfTotalWeight</a>, <a href="/web-llvm/docs/api/files/lib/lib/support/md5-cpp/#a96d73bbd7af15cb1fc38c3f4a3bd82e9">F</a>, <a href="#a2c88d6b3f033c87b7304db47133a930e">findFunctionSamples</a>, <a href="/web-llvm/docs/api/classes/llvm/sampleprofileloaderbaseimpl/#a12022aa707c271f81eae8ec0eebfae29">llvm::SampleProfileLoaderBaseImpl&lt; Function &gt;::FS</a>, <a href="/web-llvm/docs/api/files/lib/lib/analysis/memorybuiltins-cpp/#aa04dbee2593fa5fbeb0552fcb8a00ee4">getCalledFunction</a>, <a href="/web-llvm/docs/api/classes/llvm/sampleprof/functionsamples/#aeea4c49a1040f9305f6a09d7d7815544">llvm::sampleprof::FunctionSamples::getCallSiteIdentifier</a>, <a href="/web-llvm/docs/api/classes/llvm/instruction/#a4b8faae4ff9e7434a1d226d03d15dcd2">llvm::Instruction::getDebugLoc</a>, <a href="/web-llvm/docs/api/classes/llvm/basicblock/#ac24cd8d28904d8a4eac2dc3d7545355e">llvm::BasicBlock::getFirstNonPHIOrDbgOrLifetime</a>, <a href="/web-llvm/docs/api/classes/llvm/debugloc/#a427c256af834975c7869ad28fac00563">llvm::DebugLoc::getLine</a>, <a href="/web-llvm/docs/api/classes/llvm/instruction/#a3287172f2d13af086e6d66364e8c6de3">llvm::Instruction::getNumSuccessors</a>, <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/ipo/sampleprofile-cpp/#aaf55fbc9b8550957ceb81da6a13f54e4">GetSortedValueDataFromCallTargets</a>, <a href="/web-llvm/docs/api/classes/llvm/instruction/#a6e5d2e18c81baaeec7dadc81a0dea993">llvm::Instruction::getSuccessor</a>, <a href="/web-llvm/docs/api/classes/llvm/basicblock/#acf3c3aa4880eb60d00963ba93082c298">llvm::BasicBlock::getTerminator</a>, <a href="/web-llvm/docs/api/files/lib/lib/support/md5-cpp/#ac0eafdc9ee161b71e7af98af736952fd">I</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a92ca992e52dddc420f4b069cae06dfbe">llvm::isa</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a070cea0b95536a427b3ebbcedba2a630">llvm::isIndirectCall</a>, <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/support/debug-h/#a196897517069dda1bdb549e24468f7d7">LLVM_DEBUG</a>, <a href="/web-llvm/docs/api/classes/llvm/sampleprofileloaderbaseimpl/#a293c85647f9dcb78f29ad5ab31e5a7f9">llvm::SampleProfileLoaderBaseImpl&lt; Function &gt;::ORE</a>, <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/ipo/sampleprofile-cpp/#a4880524206cd6bd2551dda5c915be189">OverwriteExistingWeights</a>, <a href="/web-llvm/docs/api/classes/llvm/sampleprofileloaderbaseimpl/#af80c8905cce458376f69ac1282a07bc3">llvm::SampleProfileLoaderBaseImpl&lt; Function &gt;::printEdgeWeight</a>, <a href="/web-llvm/docs/api/classes/llvm/sampleprof/functionsamples/#a67e19eb484a5eaa31b22894398e258c0">llvm::sampleprof::FunctionSamples::ProfileIsCS</a>, <a href="/web-llvm/docs/api/classes/llvm/sampleprof/functionsamples/#aa37fe7429ffcf70c306c27a55d714d31">llvm::sampleprof::FunctionSamples::ProfileIsProbeBased</a>, <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/ipo/sampleprofile-cpp/#a2612d121382d9498fc6fc0acd70a0cf4">ProfileSampleBlockAccurate</a>, <a href="/web-llvm/docs/api/classes/llvm/smallvectortemplatebase/#af42bfbc067df27c19ee2fc859df58799">llvm::SmallVectorTemplateBase&lt; T, bool &gt;::push_back</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a6074db8acc6aa7a2f810d5918a793e87">llvm::SampleProfileUseProfi</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a6cf82c052d63a1b464be8e48ff38c48e">llvm::setBranchWeights</a>, <a href="/web-llvm/docs/api/classes/llvm/instruction/#a9247a212ea89acc9573fa7e7f557eaba">llvm::Instruction::setMetadata</a> and <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/ipo/sampleprofile-cpp/#a5c3b919b227c332257bcc77ec8c9df00">updateIDTMetaData</a>.</p>


<p>Referenced by <a href="#a6f70814abe4749ddb1e8356c3584b2ac">emitAnnotations</a>.</p>

</div>
</div>

### getExternalInlineAdvisorCost() {#ab8641bf75d896ad3caffd68a441c4a7e}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">std::optional&lt; InlineCost &gt; SampleProfileLoader::getExternalInlineAdvisorCost (<a href="/web-llvm/docs/api/classes/llvm/callbase">CallBase</a> &amp; CB)</td>
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



<p>Definition at line 510 of file <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/ipo/sampleprofile-cpp">SampleProfile.cpp</a>.</p>


<p>References <a href="#a7d8fb7d2b619a9afafc3add8e9c11eb9">ExternalInlineAdvisor</a>, <a href="/web-llvm/docs/api/classes/llvm/inlinecost/#aa71268864238db3f41e3d6582103e4e2">llvm::InlineCost::getAlways</a> and <a href="/web-llvm/docs/api/classes/llvm/inlinecost/#aa1e6376794d0c3da5a2820a2943634eb">llvm::InlineCost::getNever</a>.</p>


<p>Referenced by <a href="#a1504c594e55b1808ae9f992f9783c8b0">getExternalInlineAdvisorShouldInline</a> and <a href="#a518b0cf18edfb9fb05aaa530550af870">shouldInlineCandidate</a>.</p>

</div>
</div>

### getExternalInlineAdvisorShouldInline() {#a1504c594e55b1808ae9f992f9783c8b0}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool SampleProfileLoader::getExternalInlineAdvisorShouldInline (<a href="/web-llvm/docs/api/classes/llvm/callbase">CallBase</a> &amp; CB)</td>
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



<p>Definition at line 511 of file <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/ipo/sampleprofile-cpp">SampleProfile.cpp</a>.</p>


<p>Reference <a href="#ab8641bf75d896ad3caffd68a441c4a7e">getExternalInlineAdvisorCost</a>.</p>


<p>Referenced by <a href="#aa9137eda03e0c2cfd6eebaa55dfdd4cc">findExternalInlineCandidate</a>, <a href="#a284bbebbcad19f7e38253a1a8df134b5">getInlineCandidate</a> and <a href="#aa730b58924baf8f35394c2e5a0bb3714">inlineHotFunctions</a>.</p>

</div>
</div>

### getInlineCandidate() {#a284bbebbcad19f7e38253a1a8df134b5}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool SampleProfileLoader::getInlineCandidate (<a href="/web-llvm/docs/api/structs/anonymous-sampleprofile-cpp-/inlinecandidate">InlineCandidate</a> * NewCandidate, <a href="/web-llvm/docs/api/classes/llvm/callbase">CallBase</a> * CB)</td>
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



<p>Definition at line 513 of file <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/ipo/sampleprofile-cpp">SampleProfile.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/silowercontrolflow-cpp/#a4868c5d81c5ccc98c47aeab6244346a0">assert</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a7b3e8a01dfede6141c79e012a44ec9e4">llvm::extractProbe</a>, <a href="#a219e9fac05a219d48a97e03304f84613">findCalleeFunctionSamples</a>, <a href="#a1504c594e55b1808ae9f992f9783c8b0">getExternalInlineAdvisorShouldInline</a>, <a href="/web-llvm/docs/api/classes/llvm/sampleprof/functionsamples/#af757985efc97179779ea3fc9e84f4735">llvm::sampleprof::FunctionSamples::getHeadSamplesEstimate</a> and <a href="/web-llvm/docs/api/namespaces/llvm/#a92ca992e52dddc420f4b069cae06dfbe">llvm::isa</a>.</p>


<p>Referenced by <a href="#ae0bf03df2431c543590180658ce4709d">inlineHotFunctionsWithPriority</a>.</p>

</div>
</div>

### getInstWeight() {#aa583009e488330c099a4ab23e2536d2f}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">ErrorOr&lt; uint64_t &gt; SampleProfileLoader::getInstWeight (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/instruction">Instruction</a> &amp; I)</td>
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



<p>Definition at line 494 of file <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/ipo/sampleprofile-cpp">SampleProfile.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/namespaces/llvm/#a22eeee01734061ac1b31ccd994c49eef">llvm::dyn_cast</a>, <a href="#a219e9fac05a219d48a97e03304f84613">findCalleeFunctionSamples</a>, <a href="/web-llvm/docs/api/classes/llvm/instruction/#a4b8faae4ff9e7434a1d226d03d15dcd2">llvm::Instruction::getDebugLoc</a>, <a href="/web-llvm/docs/api/classes/llvm/sampleprofileloaderbaseimpl/#a3fd239026aba79e9aaf5b81578f4198c">llvm::SampleProfileLoaderBaseImpl&lt; Function &gt;::getInstWeightImpl</a>, <a href="/web-llvm/docs/api/classes/llvm/sampleprofileloaderbaseimpl/#acdcff307bede233f8221f618d262b6df">llvm::SampleProfileLoaderBaseImpl&lt; Function &gt;::getProbeWeight</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a92ca992e52dddc420f4b069cae06dfbe">llvm::isa</a>, <a href="/web-llvm/docs/api/classes/llvm/sampleprof/functionsamples/#a67e19eb484a5eaa31b22894398e258c0">llvm::sampleprof::FunctionSamples::ProfileIsCS</a> and <a href="/web-llvm/docs/api/classes/llvm/sampleprof/functionsamples/#aa37fe7429ffcf70c306c27a55d714d31">llvm::sampleprof::FunctionSamples::ProfileIsProbeBased</a>.</p>

</div>
</div>

### inlineHotFunctions() {#aa730b58924baf8f35394c2e5a0bb3714}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool SampleProfileLoader::inlineHotFunctions (<a href="/web-llvm/docs/api/classes/llvm/function">Function</a> &amp; F, <a href="/web-llvm/docs/api/classes/llvm/denseset">DenseSet</a>&lt; <a href="/web-llvm/docs/api/classes/llvm/globalvalue/#a3af0428ec6e48cb2f05c199b7b9f7e07">GlobalValue::GUID</a> &gt; &amp; InlinedGUIDs)</td>
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

<p>Iteratively inline hot callsites of a function.</p>


<p>Iteratively traverse all callsites of the function <span class="doxyComputerOutput">F</span>, so as to find out callsites with corresponding inline instances.</p>


<p>For such callsites,</p>


<ul class="doxyList ">
<li>If it is hot enough, inline the callsites and adds callsites of the callee into the caller. If the call is an indirect call, first promote it to direct call. Each indirect call is limited with a single target.</li>
<li>If a callsite is not inlined, merge the its profile to the outline version (if –sample-profile-merge-inlinee is true), or scale the counters of standalone function based on the profile of inlined instances (if –sample-profile-merge-inlinee is false).

Later passes may consume the updated profiles.</li>
</ul>

<dl class="doxyParamsList">
<dt class="doxyParamsTableTitle">Parameters</dt>
<dd>
<table class="doxyParamsTable">
<tr class="doxyParamItem">
<td class="doxyParamItemName">F</td>
<td class="doxyParamItemDescription"><p>function to perform iterative inlining.</p></td>
</tr>
<tr class="doxyParamItem">
<td class="doxyParamItemName">InlinedGUIDs</td>
<td class="doxyParamItemDescription"><p>a set to be updated to include all GUIDs that are inlined in the profiled binary.</p></td>
</tr>
</table>
</dd>
</dl>

<dl class="doxySectionUser">
<dt>Returns</dt>
<dd><p>True if there is any inline happened.</p></dd>
</dl>


<p>Definition at line 508 of file <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/ipo/sampleprofile-cpp">SampleProfile.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/silowercontrolflow-cpp/#a4868c5d81c5ccc98c47aeab6244346a0">assert</a>, <a href="/web-llvm/docs/api/classes/llvm/smallvectortemplatecommon/#a8a045d250952c0867382a9840ee18fdf">llvm::SmallVectorTemplateCommon&lt; T, typename &gt;::begin</a>, <a href="/web-llvm/docs/api/namespaces/llvm/sampleprofutil/#ab6789a9522443425d339fa34c25f89d5">llvm::sampleprofutil::callsiteIsHot</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a22eeee01734061ac1b31ccd994c49eef">llvm::dyn_cast</a>, <a href="#a64ec6ec160cdb088c22ec00f8e314822">emitOptimizationRemarksForInlineCandidates</a>, <a href="/web-llvm/docs/api/classes/llvm/smallvectortemplatecommon/#a075e34e98605d0e7c289763a104869ac">llvm::SmallVectorTemplateCommon&lt; T, typename &gt;::end</a>, <a href="/web-llvm/docs/api/classes/llvm/mapvector/#a3a8171298a7d19a309d599de01906703">llvm::MapVector&lt; KeyT, ValueT, MapType, VectorType &gt;::erase</a>, <a href="#a7d8fb7d2b619a9afafc3add8e9c11eb9">ExternalInlineAdvisor</a>, <a href="/web-llvm/docs/api/files/lib/lib/support/md5-cpp/#a96d73bbd7af15cb1fc38c3f4a3bd82e9">F</a>, <a href="#a219e9fac05a219d48a97e03304f84613">findCalleeFunctionSamples</a>, <a href="#aa9137eda03e0c2cfd6eebaa55dfdd4cc">findExternalInlineCandidate</a>, <a href="#abf8457f6ea82a821ee3fb08dae6246d9">findIndirectCallFunctionSamples</a>, <a href="/web-llvm/docs/api/classes/llvm/sampleprofileloaderbaseimpl/#a12022aa707c271f81eae8ec0eebfae29">llvm::SampleProfileLoaderBaseImpl&lt; Function &gt;::FS</a>, <a href="#a1504c594e55b1808ae9f992f9783c8b0">getExternalInlineAdvisorShouldInline</a>, <a href="/web-llvm/docs/api/classes/llvm/function/#a4d834f9897d15e3a6349063b5d637cd8">llvm::Function::getSubprogram</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a59c007354dfad2f618a37e6efaf7cd9ba4194726ee334e1085d93e002837b73f0">llvm::Hot</a>, <a href="/web-llvm/docs/api/files/lib/lib/support/md5-cpp/#ac0eafdc9ee161b71e7af98af736952fd">I</a>, <a href="/web-llvm/docs/api/classes/llvm/mapvector/#abb6ea6cbdf19ab64bf0c8f65b2e6e8ce">llvm::MapVector&lt; KeyT, ValueT, MapType, VectorType &gt;::insert</a>, <a href="/web-llvm/docs/api/classes/llvm/smallvectorimpl/#a94d23373106467003722f7d6c17b1528">llvm::SmallVectorImpl&lt; T &gt;::insert</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a92ca992e52dddc420f4b069cae06dfbe">llvm::isa</a>, <a href="/web-llvm/docs/api/classes/llvm/globalvalue/#a32e606ac4c88f71f14212e42b808e7f4">llvm::GlobalValue::isDeclaration</a>, <a href="/web-llvm/docs/api/classes/llvm/mapvector/#abca23bddf517f69d28c6d30c58a7b6f9">llvm::MapVector&lt; KeyT, ValueT, MapType, VectorType &gt;::lookup</a>, <a href="#a16100da114bdba0571c38edc371835d8">LTOPhase</a>, <a href="#a08e4315133d1d023573bd96e627d0dc0">ProfAccForSymsInList</a>, <a href="/web-llvm/docs/api/classes/llvm/sampleprof/functionsamples/#a67e19eb484a5eaa31b22894398e258c0">llvm::sampleprof::FunctionSamples::ProfileIsCS</a>, <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/ipo/sampleprofile-cpp/#af00e1c8a074b97aedd1a2db33dea6753">ProfileSampleAccurate</a>, <a href="#a16e99ef185f55c3e45caf11c880998ff">promoteMergeNotInlinedContextSamples</a>, <a href="/web-llvm/docs/api/classes/llvm/sampleprofileloaderbaseimpl/#ae49ac2191e91a12f7ed0b92b2b72ebbe">llvm::SampleProfileLoaderBaseImpl&lt; Function &gt;::PSI</a>, <a href="/web-llvm/docs/api/classes/llvm/smallvectortemplatebase/#af42bfbc067df27c19ee2fc859df58799">llvm::SmallVectorTemplateBase&lt; T, bool &gt;::push_back</a>, <a href="#a902b6197889c703bbe3c087f8bcf0789">shouldInlineColdCallee</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a5d737fb4258bb27586a1bffd557fbb49ad94cc56b0a9155d607f2609b0f5c39d3">llvm::ThinLTOPreLink</a>, <a href="#adb1dafd461988f3d8e687eabb99e108d">tryInlineCandidate</a>, <a href="#ad5c772a0b61cb29106af3a4f9ae43d59">tryPromoteAndInlineCandidate</a> and <a href="/web-llvm/docs/api/classes/llvm/sampleprof/functionsamples/#afddaa81316d56f125de69793e0ddb33c">llvm::sampleprof::FunctionSamples::UseMD5</a>.</p>


<p>Referenced by <a href="#a6f70814abe4749ddb1e8356c3584b2ac">emitAnnotations</a>.</p>

</div>
</div>

### inlineHotFunctionsWithPriority() {#ae0bf03df2431c543590180658ce4709d}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool SampleProfileLoader::inlineHotFunctionsWithPriority (<a href="/web-llvm/docs/api/classes/llvm/function">Function</a> &amp; F, <a href="/web-llvm/docs/api/classes/llvm/denseset">DenseSet</a>&lt; <a href="/web-llvm/docs/api/classes/llvm/globalvalue/#a3af0428ec6e48cb2f05c199b7b9f7e07">GlobalValue::GUID</a> &gt; &amp; InlinedGUIDs)</td>
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



<p>Definition at line 518 of file <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/ipo/sampleprofile-cpp">SampleProfile.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/silowercontrolflow-cpp/#a4868c5d81c5ccc98c47aeab6244346a0">assert</a>, <a href="/web-llvm/docs/api/structs/anonymous-sampleprofile-cpp-/inlinecandidate/#a9d11db7a624e3a52fafdae744a90b4e3">anonymous{SampleProfile.cpp}::InlineCandidate::CalleeSamples</a>, <a href="/web-llvm/docs/api/structs/anonymous-sampleprofile-cpp-/inlinecandidate/#aee9c3595a3d7818a194632b2b7700afe">anonymous{SampleProfile.cpp}::InlineCandidate::CallInstr</a>, <a href="/web-llvm/docs/api/structs/anonymous-sampleprofile-cpp-/inlinecandidate/#ab46eb71ad8b2e407e902b2c6e06f1b27">anonymous{SampleProfile.cpp}::InlineCandidate::CallsiteDistribution</a>, <a href="#a61e8260e50a3374fc9cd3540068f856a">ContextTracker</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a22eeee01734061ac1b31ccd994c49eef">llvm::dyn_cast</a>, <a href="#a7d8fb7d2b619a9afafc3add8e9c11eb9">ExternalInlineAdvisor</a>, <a href="/web-llvm/docs/api/files/lib/lib/support/md5-cpp/#a96d73bbd7af15cb1fc38c3f4a3bd82e9">F</a>, <a href="#a219e9fac05a219d48a97e03304f84613">findCalleeFunctionSamples</a>, <a href="#aa9137eda03e0c2cfd6eebaa55dfdd4cc">findExternalInlineCandidate</a>, <a href="#abf8457f6ea82a821ee3fb08dae6246d9">findIndirectCallFunctionSamples</a>, <a href="/web-llvm/docs/api/classes/llvm/sampleprofileloaderbaseimpl/#a12022aa707c271f81eae8ec0eebfae29">llvm::SampleProfileLoaderBaseImpl&lt; Function &gt;::FS</a>, <a href="#a284bbebbcad19f7e38253a1a8df134b5">getInlineCandidate</a>, <a href="/web-llvm/docs/api/classes/llvm/function/#a4d834f9897d15e3a6349063b5d637cd8">llvm::Function::getSubprogram</a>, <a href="/web-llvm/docs/api/files/lib/lib/support/md5-cpp/#ac0eafdc9ee161b71e7af98af736952fd">I</a>, <a href="/web-llvm/docs/api/classes/llvm/mapvector/#abb6ea6cbdf19ab64bf0c8f65b2e6e8ce">llvm::MapVector&lt; KeyT, ValueT, MapType, VectorType &gt;::insert</a>, <a href="/web-llvm/docs/api/classes/llvm/globalvalue/#a32e606ac4c88f71f14212e42b808e7f4">llvm::GlobalValue::isDeclaration</a>, <a href="#a16100da114bdba0571c38edc371835d8">LTOPhase</a>, <a href="#a08e4315133d1d023573bd96e627d0dc0">ProfAccForSymsInList</a>, <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/ipo/sampleprofile-cpp/#abe3f89debe4f7888460625789de78083">ProfileICPRelativeHotness</a>, <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/ipo/sampleprofile-cpp/#ac689c456b39941e3af203d3e1750b8b5">ProfileICPRelativeHotnessSkip</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#af000efe78adef3c5fc3cbedbc215556b">llvm::ProfileInlineGrowthLimit</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#ad68079dd1eac0685dbf374e088d79b64">llvm::ProfileInlineLimitMax</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a1118e6eca7dab8dfcd484ccb179533b0">llvm::ProfileInlineLimitMin</a>, <a href="/web-llvm/docs/api/classes/llvm/sampleprof/functionsamples/#a67e19eb484a5eaa31b22894398e258c0">llvm::sampleprof::FunctionSamples::ProfileIsCS</a>, <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/ipo/sampleprofile-cpp/#af00e1c8a074b97aedd1a2db33dea6753">ProfileSampleAccurate</a>, <a href="#a16e99ef185f55c3e45caf11c880998ff">promoteMergeNotInlinedContextSamples</a>, <a href="/web-llvm/docs/api/classes/llvm/sampleprofileloaderbaseimpl/#ae49ac2191e91a12f7ed0b92b2b72ebbe">llvm::SampleProfileLoaderBaseImpl&lt; Function &gt;::PSI</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/hexagon/hexagonearlyifconv-cpp/#a69e1845bcbb3948c6e36bbbfb71e8024">SizeLimit</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a5d737fb4258bb27586a1bffd557fbb49ad94cc56b0a9155d607f2609b0f5c39d3">llvm::ThinLTOPreLink</a>, <a href="#adb1dafd461988f3d8e687eabb99e108d">tryInlineCandidate</a> and <a href="#ad5c772a0b61cb29106af3a4f9ae43d59">tryPromoteAndInlineCandidate</a>.</p>


<p>Referenced by <a href="#a6f70814abe4749ddb1e8356c3584b2ac">emitAnnotations</a>.</p>

</div>
</div>

### promoteMergeNotInlinedContextSamples() {#a16e99ef185f55c3e45caf11c880998ff}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void SampleProfileLoader::promoteMergeNotInlinedContextSamples (<a href="/web-llvm/docs/api/classes/llvm/mapvector">MapVector</a>&lt; <a href="/web-llvm/docs/api/classes/llvm/callbase">CallBase</a> *, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/sampleprof/functionsamples">FunctionSamples</a> * &gt; NonInlinedCallSites, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/function">Function</a> &amp; F)</td>
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



<p>Definition at line 525 of file <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/ipo/sampleprofile-cpp">SampleProfile.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/namespaces/llvm/sampleprof/#a9c9cec0dc85381494fb418ae0e88a40fa2ccdadcef66b2fc9b3f0fe60045c32c8">llvm::sampleprof::ContextDuplicatedIntoBase</a>, <a href="/web-llvm/docs/api/files/lib/lib/support/md5-cpp/#a96d73bbd7af15cb1fc38c3f4a3bd82e9">F</a>, <a href="/web-llvm/docs/api/classes/llvm/sampleprofileloaderbaseimpl/#a12022aa707c271f81eae8ec0eebfae29">llvm::SampleProfileLoaderBaseImpl&lt; Function &gt;::FS</a>, <a href="/web-llvm/docs/api/classes/llvm/sampleprof/functionsamples/#aa7122a07ea48e47fc71083e68b829003">llvm::sampleprof::FunctionSamples::getCanonicalFnName</a>, <a href="/web-llvm/docs/api/files/lib/lib/support/md5-cpp/#ac0eafdc9ee161b71e7af98af736952fd">I</a>, <a href="/web-llvm/docs/api/classes/llvm/sampleprof/functionsamples/#adfcf1b41d1251eac2f16312eec52b45a">llvm::sampleprof::FunctionSamples::merge</a>, <a href="#a09c53287a76f1544e782601e437149be">notInlinedCallInfo</a>, <a href="/web-llvm/docs/api/classes/llvm/sampleprofileloaderbaseimpl/#a293c85647f9dcb78f29ad5ab31e5a7f9">llvm::SampleProfileLoaderBaseImpl&lt; Function &gt;::ORE</a>, <a href="/web-llvm/docs/api/classes/llvm/sampleprofileloaderbaseimpl/#a28a1e350b54691c575efa482bfc72140">llvm::SampleProfileLoaderBaseImpl&lt; Function &gt;::OutlineFunctionSamples</a>, <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/ipo/sampleprofile-cpp/#a8b16dbb3ebefd05908afe3a7874d6353">ProfileMergeInlinee</a>, <a href="/web-llvm/docs/api/classes/llvm/sampleprofileloaderbaseimpl/#a6cda1f8872cce456c1ec260c8ef7aa24">llvm::SampleProfileLoaderBaseImpl&lt; Function &gt;::Reader</a> and <a href="/web-llvm/docs/api/classes/llvm/sampleprof/functionsamples/#abfe0ee51b3061c6dde4984d786065ac8">llvm::sampleprof::FunctionSamples::setContextSynthetic</a>.</p>


<p>Referenced by <a href="#aa730b58924baf8f35394c2e5a0bb3714">inlineHotFunctions</a> and <a href="#ae0bf03df2431c543590180658ce4709d">inlineHotFunctionsWithPriority</a>.</p>

</div>
</div>

### rejectHighStalenessProfile() {#abf1045cfa542c9bf01c10bcf99262a2c}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool SampleProfileLoader::rejectHighStalenessProfile (<a href="/web-llvm/docs/api/classes/llvm/module">Module</a> &amp; M, <a href="/web-llvm/docs/api/classes/llvm/profilesummaryinfo">ProfileSummaryInfo</a> * PSI, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/sampleprof/sampleprofilemap">SampleProfileMap</a> &amp; Profiles)</td>
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



<p>Definition at line 531 of file <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/ipo/sampleprofile-cpp">SampleProfile.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/silowercontrolflow-cpp/#a4868c5d81c5ccc98c47aeab6244346a0">assert</a>, <a href="/web-llvm/docs/api/classes/llvm/sampleprofileloaderbaseimpl/#a12022aa707c271f81eae8ec0eebfae29">llvm::SampleProfileLoaderBaseImpl&lt; Function &gt;::FS</a>, <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/ipo/sampleprofile-cpp/#af9dc2d6d5404e7d42198490fa3be4e73">HotFuncCutoffForStalenessError</a>, <a href="/web-llvm/docs/api/files/lib/lib/support/md5-cpp/#ac0eafdc9ee161b71e7af98af736952fd">I</a>, <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/ipo/sampleprofile-cpp/#a0839b336a4cfa394f0a6df99af24c122">MinfuncsForStalenessError</a>, <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/ipo/sampleprofile-cpp/#a31561104790d3759baa688de077367ce">PrecentMismatchForStalenessError</a>, <a href="/web-llvm/docs/api/classes/llvm/sampleprofileloaderbaseimpl/#a8a061b4f421152b76653f15e18bec185">llvm::SampleProfileLoaderBaseImpl&lt; Function &gt;::ProbeManager</a>, <a href="/web-llvm/docs/api/classes/llvm/sampleprof/functionsamples/#aa37fe7429ffcf70c306c27a55d714d31">llvm::sampleprof::FunctionSamples::ProfileIsProbeBased</a> and <a href="/web-llvm/docs/api/classes/llvm/sampleprofileloaderbaseimpl/#ae49ac2191e91a12f7ed0b92b2b72ebbe">llvm::SampleProfileLoaderBaseImpl&lt; Function &gt;::PSI</a>.</p>


<p>Referenced by <a href="#a25da45ec2b5b7dacb22e831cb7aef0c5">runOnModule</a>.</p>

</div>
</div>

### removePseudoProbeInstsDiscriminator() {#a35bb2baa976d7716a9752ad544e8134f}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void SampleProfileLoader::removePseudoProbeInstsDiscriminator (<a href="/web-llvm/docs/api/classes/llvm/module">Module</a> &amp; M)</td>
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



<p>Definition at line 533 of file <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/ipo/sampleprofile-cpp">SampleProfile.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/structs/llvm/pseudoprobedwarfdiscriminator/#ad0c37806bfdb6415dbe3866307f6716c">llvm::PseudoProbeDwarfDiscriminator::extractDwarfBaseDiscriminator</a>, <a href="/web-llvm/docs/api/files/lib/lib/support/md5-cpp/#a96d73bbd7af15cb1fc38c3f4a3bd82e9">F</a>, <a href="/web-llvm/docs/api/files/lib/lib/support/md5-cpp/#ac0eafdc9ee161b71e7af98af736952fd">I</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a92ca992e52dddc420f4b069cae06dfbe">llvm::isa</a> and <a href="/web-llvm/docs/api/classes/llvm/dilocation/#a1d5bbfbe6fc9f92e22bf16cb1c2dc110">llvm::DILocation::isPseudoProbeDiscriminator</a>.</p>


<p>Referenced by <a href="#a25da45ec2b5b7dacb22e831cb7aef0c5">runOnModule</a>.</p>

</div>
</div>

### runOnFunction() {#a358b28b8ab641a2a22ed8849a2dff2cf}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool SampleProfileLoader::runOnFunction (<a href="/web-llvm/docs/api/classes/llvm/function">Function</a> &amp; F, <a href="/web-llvm/docs/api/namespaces/llvm/#af9c9208365fd9ce11392b4d79485e259">ModuleAnalysisManager</a> * AM)</td>
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



<p>Definition at line 492 of file <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/ipo/sampleprofile-cpp">SampleProfile.cpp</a>.</p>


<p>References <a href="#a61e8260e50a3374fc9cd3540068f856a">ContextTracker</a>, <a href="/web-llvm/docs/api/classes/llvm/sampleprofileloaderbaseimpl/#a52673282884569984ceee1e4f7119a50">llvm::SampleProfileLoaderBaseImpl&lt; Function &gt;::CoverageTracker</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a7c46c742c31be54870e2038048e6b391">llvm::dbgs</a>, <a href="/web-llvm/docs/api/classes/llvm/sampleprofileloaderbaseimpl/#aeacafab53cd915d0ff8922dcb398fbe1">llvm::SampleProfileLoaderBaseImpl&lt; Function &gt;::DILocation2SampleMap</a>, <a href="#a6f70814abe4749ddb1e8356c3584b2ac">emitAnnotations</a>, <a href="/web-llvm/docs/api/files/lib/lib/support/md5-cpp/#a96d73bbd7af15cb1fc38c3f4a3bd82e9">F</a>, <a href="/web-llvm/docs/api/files/lib/lib/passes/passbuilderbindings-cpp/#a83c7e5ca51099e4efa895791a02fb0ed">FAM</a>, <a href="/web-llvm/docs/api/classes/llvm/sampleprof/functionsamples/#aa7122a07ea48e47fc71083e68b829003">llvm::sampleprof::FunctionSamples::getCanonicalFnName</a>, <a href="/web-llvm/docs/api/classes/llvm/globalvalue/#a6811428caf500217f319c74e80900c14">llvm::GlobalValue::getGUID</a>, <a href="/web-llvm/docs/api/classes/llvm/analysismanager/#aaab1fad63e4f3b8679469720a873fedd">llvm::AnalysisManager&lt; IRUnitT, ExtraArgTs &gt;::getResult</a>, <a href="#a99625599858fb55fe0892163548436b3">GUIDsInProfile</a>, <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/support/debug-h/#a196897517069dda1bdb549e24468f7d7">LLVM_DEBUG</a>, <a href="#a13d326ade07b8cc14d4e307253b2797b">NamesInProfile</a>, <a href="/web-llvm/docs/api/classes/llvm/sampleprofileloaderbaseimpl/#a293c85647f9dcb78f29ad5ab31e5a7f9">llvm::SampleProfileLoaderBaseImpl&lt; Function &gt;::ORE</a>, <a href="/web-llvm/docs/api/classes/llvm/sampleprofileloaderbaseimpl/#a28a1e350b54691c575efa482bfc72140">llvm::SampleProfileLoaderBaseImpl&lt; Function &gt;::OutlineFunctionSamples</a>, <a href="/web-llvm/docs/api/classes/llvm/function/#a438d2f246b76817114ade2a005a6bcabac7dbc704eba08842e6acdde9cf6379ba">llvm::Function::PCT_Real</a>, <a href="#a08e4315133d1d023573bd96e627d0dc0">ProfAccForSymsInList</a>, <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/ipo/sampleprofile-cpp/#a88e2b32b6c2ab29b0b4470f5a1a32364">ProfileAccurateForSymsInList</a>, <a href="/web-llvm/docs/api/classes/llvm/sampleprof/functionsamples/#a67e19eb484a5eaa31b22894398e258c0">llvm::sampleprof::FunctionSamples::ProfileIsCS</a>, <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/ipo/sampleprofile-cpp/#af00e1c8a074b97aedd1a2db33dea6753">ProfileSampleAccurate</a>, <a href="#a3329c2209e8b3bc0cd93bd6172ef16ca">PSL</a>, <a href="/web-llvm/docs/api/classes/llvm/sampleprofileloaderbaseimpl/#a6cda1f8872cce456c1ec260c8ef7aa24">llvm::SampleProfileLoaderBaseImpl&lt; Function &gt;::Reader</a>, <a href="/web-llvm/docs/api/classes/llvm/sampleprofileloaderbaseimpl/#ad9ec5be72117476a75c7dd1cc59d03f1">llvm::SampleProfileLoaderBaseImpl&lt; Function &gt;::Samples</a> and <a href="/web-llvm/docs/api/classes/llvm/sampleprof/functionsamples/#afddaa81316d56f125de69793e0ddb33c">llvm::sampleprof::FunctionSamples::UseMD5</a>.</p>


<p>Referenced by <a href="#a25da45ec2b5b7dacb22e831cb7aef0c5">runOnModule</a>.</p>

</div>
</div>

### shouldInlineCandidate() {#a518b0cf18edfb9fb05aaa530550af870}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">InlineCost SampleProfileLoader::shouldInlineCandidate (<a href="/web-llvm/docs/api/structs/anonymous-sampleprofile-cpp-/inlinecandidate">InlineCandidate</a> &amp; Candidate)</td>
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



<p>Definition at line 512 of file <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/ipo/sampleprofile-cpp">SampleProfile.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/structs/llvm/inlineparams/#a9d17fae32cf8dbe9afa4043766b5592a">llvm::InlineParams::AllowRecursiveCall</a>, <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/ipo/sampleprofile-cpp/#af5f668624e8264858b5efb9127b3be47">AllowRecursiveInline</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/silowercontrolflow-cpp/#a4868c5d81c5ccc98c47aeab6244346a0">assert</a>, <a href="/web-llvm/docs/api/structs/anonymous-sampleprofile-cpp-/inlinecandidate/#a9d11db7a624e3a52fafdae744a90b4e3">anonymous{SampleProfile.cpp}::InlineCandidate::CalleeSamples</a>, <a href="/web-llvm/docs/api/structs/anonymous-sampleprofile-cpp-/inlinecandidate/#aee9c3595a3d7818a194632b2b7700afe">anonymous{SampleProfile.cpp}::InlineCandidate::CallInstr</a>, <a href="/web-llvm/docs/api/structs/anonymous-sampleprofile-cpp-/inlinecandidate/#ab322916149d8aa186f76dcf9aaf7f5c1">anonymous{SampleProfile.cpp}::InlineCandidate::CallsiteCount</a>, <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/ipo/sampleprofile-cpp/#a9eaaeedd35128b9508715b2c16dd58f5">CallsitePrioritizedInline</a>, <a href="/web-llvm/docs/api/structs/llvm/inlineparams/#ad0224a24a49c3ff90f10dc6970f6b89f">llvm::InlineParams::ComputeFullInlineCost</a>, <a href="/web-llvm/docs/api/namespaces/llvm/sampleprof/#a9c9cec0dc85381494fb418ae0e88a40fa9a35039dfc5e52a8ee9289957a726bee">llvm::sampleprof::ContextShouldBeInlined</a>, <a href="/web-llvm/docs/api/classes/llvm/inlinecost/#ac1dbd59a648c96031c8d91238017e6c2">llvm::InlineCost::get</a>, <a href="#aaa4377cfbfd513fba3113fa91210a0c4">GetAC</a>, <a href="/web-llvm/docs/api/classes/llvm/inlinecost/#aa71268864238db3f41e3d6582103e4e2">llvm::InlineCost::getAlways</a>, <a href="/web-llvm/docs/api/classes/llvm/callbase/#a2b1ae7cf1bafdd43d1fee4c6ad0a2913">llvm::CallBase::getCalledFunction</a>, <a href="/web-llvm/docs/api/classes/llvm/sampleprof/functionsamples/#ad117577730085f895045fc7ff90d8fc2">llvm::sampleprof::FunctionSamples::getContext</a>, <a href="#ab8641bf75d896ad3caffd68a441c4a7e">getExternalInlineAdvisorCost</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a5f5f248d08aa55c63e5bc7a8304a7319">llvm::getInlineCost</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#aba7063dea024346c7b70099c63703f50">llvm::getInlineParams</a>, <a href="/web-llvm/docs/api/classes/llvm/inlinecost/#aa1e6376794d0c3da5a2820a2943634eb">llvm::InlineCost::getNever</a>, <a href="#ad152203aa6393f06c0b955e3f70b94dd">GetTLI</a>, <a href="#aa6421c02e92eda93cce39ae1adc23f45">GetTTI</a>, <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/ipo/sampleprofile-cpp/#ada8f2c564085d598909fb28464614812">ProfileSizeInline</a>, <a href="/web-llvm/docs/api/classes/llvm/sampleprofileloaderbaseimpl/#ae49ac2191e91a12f7ed0b92b2b72ebbe">llvm::SampleProfileLoaderBaseImpl&lt; Function &gt;::PSI</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#ab2e474df1ef4ceee0cf5ed5785caf31c">llvm::SampleColdCallSiteThreshold</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a96398453e844d01e6c978df781ba96ac">llvm::SampleHotCallSiteThreshold</a>, <a href="/web-llvm/docs/api/namespaces/llvm/sampleprof/#a6cff5a57b476680e6b28e4dbfd2da8acab2e6b6d8b22672f40e617c7dfedd302a">llvm::sampleprof::SyntheticContext</a> and <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/ipo/sampleprofile-cpp/#ad07d06e65e4610fb8ac7b13e868ec1c9">UsePreInlinerDecision</a>.</p>


<p>Referenced by <a href="#adb1dafd461988f3d8e687eabb99e108d">tryInlineCandidate</a>.</p>

</div>
</div>

### shouldInlineColdCallee() {#a902b6197889c703bbe3c087f8bcf0789}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool SampleProfileLoader::shouldInlineColdCallee (<a href="/web-llvm/docs/api/classes/llvm/callbase">CallBase</a> &amp; CallInst)</td>
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



<p>Definition at line 521 of file <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/ipo/sampleprofile-cpp">SampleProfile.cpp</a>.</p>


<p>References <a href="#aaa4377cfbfd513fba3113fa91210a0c4">GetAC</a>, <a href="/web-llvm/docs/api/classes/llvm/callbase/#a2b1ae7cf1bafdd43d1fee4c6ad0a2913">llvm::CallBase::getCalledFunction</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a5f5f248d08aa55c63e5bc7a8304a7319">llvm::getInlineCost</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#aba7063dea024346c7b70099c63703f50">llvm::getInlineParams</a>, <a href="#ad152203aa6393f06c0b955e3f70b94dd">GetTLI</a>, <a href="#aa6421c02e92eda93cce39ae1adc23f45">GetTTI</a>, <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/ipo/sampleprofile-cpp/#ada8f2c564085d598909fb28464614812">ProfileSizeInline</a> and <a href="/web-llvm/docs/api/namespaces/llvm/#ab2e474df1ef4ceee0cf5ed5785caf31c">llvm::SampleColdCallSiteThreshold</a>.</p>


<p>Referenced by <a href="#aa730b58924baf8f35394c2e5a0bb3714">inlineHotFunctions</a>.</p>

</div>
</div>

### tryInlineCandidate() {#adb1dafd461988f3d8e687eabb99e108d}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool SampleProfileLoader::tryInlineCandidate (<a href="/web-llvm/docs/api/structs/anonymous-sampleprofile-cpp-/inlinecandidate">InlineCandidate</a> &amp; Candidate, <a href="/web-llvm/docs/api/classes/llvm/smallvector">SmallVector</a>&lt; <a href="/web-llvm/docs/api/classes/llvm/callbase">CallBase</a> *, 8 &gt; * InlinedCallSites=nullptr)</td>
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



<p>Definition at line 515 of file <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/ipo/sampleprofile-cpp">SampleProfile.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/silowercontrolflow-cpp/#a4868c5d81c5ccc98c47aeab6244346a0">assert</a>, <a href="/web-llvm/docs/api/structs/anonymous-sampleprofile-cpp-/inlinecandidate/#a9d11db7a624e3a52fafdae744a90b4e3">anonymous{SampleProfile.cpp}::InlineCandidate::CalleeSamples</a>, <a href="/web-llvm/docs/api/structs/anonymous-sampleprofile-cpp-/inlinecandidate/#aee9c3595a3d7818a194632b2b7700afe">anonymous{SampleProfile.cpp}::InlineCandidate::CallInstr</a>, <a href="/web-llvm/docs/api/structs/anonymous-sampleprofile-cpp-/inlinecandidate/#ab46eb71ad8b2e407e902b2c6e06f1b27">anonymous{SampleProfile.cpp}::InlineCandidate::CallsiteDistribution</a>, <a href="/web-llvm/docs/api/classes/llvm/smallvectorimpl/#aac0ea55010b7b1a301e65a0baea057aa">llvm::SmallVectorImpl&lt; T &gt;::clear</a>, <a href="#a61e8260e50a3374fc9cd3540068f856a">ContextTracker</a>, <a href="#aac6219556110a8ac4a20f7c6a49dc0c9">DisableSampleProfileInlining</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a83035d5c2bb6a64f3c35b716a994b586">llvm::emitInlinedIntoBasedOnCost</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a7b3e8a01dfede6141c79e012a44ec9e4">llvm::extractProbe</a>, <a href="#aaa4377cfbfd513fba3113fa91210a0c4">GetAC</a>, <a href="/web-llvm/docs/api/classes/llvm/callbase/#a2b1ae7cf1bafdd43d1fee4c6ad0a2913">llvm::CallBase::getCalledFunction</a>, <a href="/web-llvm/docs/api/classes/llvm/instruction/#a4b8faae4ff9e7434a1d226d03d15dcd2">llvm::Instruction::getDebugLoc</a>, <a href="/web-llvm/docs/api/classes/llvm/basicblock/#a80069e261aca5e34cffcc2ef67cfa29b">llvm::BasicBlock::getParent</a>, <a href="/web-llvm/docs/api/classes/llvm/ilist-detail/node-parent-access/#a7e19e7508415378ad9523e0339b23e22">llvm::ilist_detail::node_parent_access&lt; NodeTy, ParentTy &gt;::getParent</a>, <a href="/web-llvm/docs/api/files/lib/lib/support/md5-cpp/#ac0eafdc9ee161b71e7af98af736952fd">I</a>, <a href="/web-llvm/docs/api/classes/llvm/inlinefunctioninfo/#afee77c39305987451e9495b749863d07">llvm::InlineFunctionInfo::InlinedCallSites</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#ab5a3ac0a249da0743dac1bd816d8e5d5">llvm::InlineFunction</a>, <a href="/web-llvm/docs/api/files/lib/lib/codegen/lib/codegen/globalisel/legalizer-cpp/#a05ab4853f7153e537774d02580e761ec">IR</a>, <a href="/web-llvm/docs/api/classes/llvm/sampleprofileloaderbaseimpl/#a293c85647f9dcb78f29ad5ab31e5a7f9">llvm::SampleProfileLoaderBaseImpl&lt; Function &gt;::ORE</a>, <a href="/web-llvm/docs/api/classes/llvm/sampleprof/functionsamples/#a67e19eb484a5eaa31b22894398e258c0">llvm::sampleprof::FunctionSamples::ProfileIsCS</a>, <a href="/web-llvm/docs/api/classes/llvm/smallvectortemplatebase/#af42bfbc067df27c19ee2fc859df58799">llvm::SmallVectorTemplateBase&lt; T, bool &gt;::push_back</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a4fb32c986b105bb7a53700e5988aab6e">llvm::setProbeDistributionFactor</a>, <a href="#a518b0cf18edfb9fb05aaa530550af870">shouldInlineCandidate</a> and <a href="/web-llvm/docs/api/classes/llvm/inlinefunctioninfo/#a2479f3ea47eee2627b24bddfa6333415">llvm::InlineFunctionInfo::UpdateProfile</a>.</p>


<p>Referenced by <a href="#aa730b58924baf8f35394c2e5a0bb3714">inlineHotFunctions</a>, <a href="#ae0bf03df2431c543590180658ce4709d">inlineHotFunctionsWithPriority</a> and <a href="#ad5c772a0b61cb29106af3a4f9ae43d59">tryPromoteAndInlineCandidate</a>.</p>

</div>
</div>

### tryPromoteAndInlineCandidate() {#ad5c772a0b61cb29106af3a4f9ae43d59}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool SampleProfileLoader::tryPromoteAndInlineCandidate (<a href="/web-llvm/docs/api/classes/llvm/function">Function</a> &amp; F, <a href="/web-llvm/docs/api/structs/anonymous-sampleprofile-cpp-/inlinecandidate">InlineCandidate</a> &amp; Candidate, uint64_t SumOrigin, uint64_t &amp; Sum, <a href="/web-llvm/docs/api/classes/llvm/smallvector">SmallVector</a>&lt; <a href="/web-llvm/docs/api/classes/llvm/callbase">CallBase</a> *, 8 &gt; * InlinedCallSite=nullptr)</td>
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

<p>Attempt to promote indirect call and also inline the promoted call.</p>


<dl class="doxyParamsList">
<dt class="doxyParamsTableTitle">Parameters</dt>
<dd>
<table class="doxyParamsTable">
<tr class="doxyParamItem">
<td class="doxyParamItemName">F</td>
<td class="doxyParamItemDescription"><p>Caller function.</p></td>
</tr>
<tr class="doxyParamItem">
<td class="doxyParamItemName">Candidate</td>
<td class="doxyParamItemDescription"><p>ICP and inline candidate.</p></td>
</tr>
<tr class="doxyParamItem">
<td class="doxyParamItemName">SumOrigin</td>
<td class="doxyParamItemDescription"><p>Original sum of target counts for indirect call before promoting given candidate.</p></td>
</tr>
<tr class="doxyParamItem">
<td class="doxyParamItemName">Sum</td>
<td class="doxyParamItemDescription"><p>Prorated sum of remaining target counts for indirect call after promoting given candidate.</p></td>
</tr>
<tr class="doxyParamItem">
<td class="doxyParamItemName">InlinedCallSite</td>
<td class="doxyParamItemDescription"><p>Output vector for new call sites exposed after inlining.</p></td>
</tr>
</table>
</dd>
</dl>

<p>Definition at line 504 of file <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/ipo/sampleprofile-cpp">SampleProfile.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/structs/anonymous-sampleprofile-cpp-/inlinecandidate/#a9d11db7a624e3a52fafdae744a90b4e3">anonymous{SampleProfile.cpp}::InlineCandidate::CalleeSamples</a>, <a href="/web-llvm/docs/api/structs/anonymous-sampleprofile-cpp-/inlinecandidate/#aee9c3595a3d7818a194632b2b7700afe">anonymous{SampleProfile.cpp}::InlineCandidate::CallInstr</a>, <a href="/web-llvm/docs/api/structs/anonymous-sampleprofile-cpp-/inlinecandidate/#ab322916149d8aa186f76dcf9aaf7f5c1">anonymous{SampleProfile.cpp}::InlineCandidate::CallsiteCount</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a7c46c742c31be54870e2038048e6b391">llvm::dbgs</a>, <a href="#aac6219556110a8ac4a20f7c6a49dc0c9">DisableSampleProfileInlining</a>, <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/ipo/sampleprofile-cpp/#aa2ce415bf980facbbfb4eb13a1e9ce54">doesHistoryAllowICP</a>, <a href="/web-llvm/docs/api/files/lib/lib/support/md5-cpp/#a96d73bbd7af15cb1fc38c3f4a3bd82e9">F</a>, <a href="/web-llvm/docs/api/classes/llvm/sampleprof/functionsamples/#aa7122a07ea48e47fc71083e68b829003">llvm::sampleprof::FunctionSamples::getCanonicalFnName</a>, <a href="/web-llvm/docs/api/classes/llvm/sampleprof/functionsamples/#a7ff8c2d016ae9169f35cdd1d1aaa1564">llvm::sampleprof::FunctionSamples::getFunction</a>, <a href="/web-llvm/docs/api/classes/llvm/globalvalue/#a6811428caf500217f319c74e80900c14">llvm::GlobalValue::getGUID</a>, <a href="/web-llvm/docs/api/classes/llvm/value/#adb5c319f5905c1d3ca9eb5df546388c5">llvm::Value::getName</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a92ca992e52dddc420f4b069cae06dfbe">llvm::isa</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a0e5b9e42ea84622605acea0b0d721fda">llvm::isLegalToPromote</a>, <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/support/debug-h/#a196897517069dda1bdb549e24468f7d7">LLVM_DEBUG</a>, <a href="/web-llvm/docs/api/files/lib/lib/analysis/indirectcallpromotionanalysis-cpp/#a8d1c61a222911b42ad7dc30bc6519d81">MaxNumPromotions</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#aee20e86d3817849199a21d19bcc273c5">llvm::NOMORE_ICP_MAGICNUM</a>, <a href="/web-llvm/docs/api/classes/llvm/sampleprofileloaderbaseimpl/#a293c85647f9dcb78f29ad5ab31e5a7f9">llvm::SampleProfileLoaderBaseImpl&lt; Function &gt;::ORE</a>, <a href="/web-llvm/docs/api/namespaces/llvm/pgo/#ac3ab1f99a5d99ba23fcfec6044ebc805">llvm::pgo::promoteIndirectCall</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a4fb32c986b105bb7a53700e5988aab6e">llvm::setProbeDistributionFactor</a>, <a href="#a36a42d67af221fe58af6d4e4fa30ce96">SymbolMap</a>, <a href="#adb1dafd461988f3d8e687eabb99e108d">tryInlineCandidate</a> and <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/ipo/sampleprofile-cpp/#a5c3b919b227c332257bcc77ec8c9df00">updateIDTMetaData</a>.</p>


<p>Referenced by <a href="#aa730b58924baf8f35394c2e5a0bb3714">inlineHotFunctions</a> and <a href="#ae0bf03df2431c543590180658ce4709d">inlineHotFunctionsWithPriority</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Private Member Functions

### getAnnotatedRemarkPassName() {#a7fa0621e771540b700bb1d6273ccb082}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">const char * anonymous{SampleProfile.cpp}::SampleProfileLoader::getAnnotatedRemarkPassName ()</td>
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



<p>Definition at line 610 of file <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/ipo/sampleprofile-cpp">SampleProfile.cpp</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Protected Member Attributes

### AnnotatedPassName {#ab7d55132a633847b63ce0cdadca0af02}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">const std::string anonymous{SampleProfile.cpp}::SampleProfileLoader::AnnotatedPassName</td>
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



<p>Definition at line 559 of file <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/ipo/sampleprofile-cpp">SampleProfile.cpp</a>.</p>


<p>Referenced by <a href="#a5133b642b31dcbfad681874ba97d5914">SampleProfileLoader</a>.</p>

</div>
</div>

### CG {#a79367a297c27b50b1a88acabf00f1070}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">LazyCallGraph&amp; anonymous{SampleProfile.cpp}::SampleProfileLoader::CG</td>
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



<p>Definition at line 548 of file <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/ipo/sampleprofile-cpp">SampleProfile.cpp</a>.</p>


<p>Referenced by <a href="#a0f9647d7bd1eb0c38198f05b3d34d4f3">buildFunctionOrder</a>, <a href="#a7e1da8085095c6d808713b280edb143b">doInitialization</a>, <a href="#a25da45ec2b5b7dacb22e831cb7aef0c5">runOnModule</a> and <a href="#a5133b642b31dcbfad681874ba97d5914">SampleProfileLoader</a>.</p>

</div>
</div>

### ContextTracker {#a61e8260e50a3374fc9cd3540068f856a}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">std::unique_ptr&lt;SampleContextTracker&gt; anonymous{SampleProfile.cpp}::SampleProfileLoader::ContextTracker</td>
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

<p>Profile tracker for different context.</p>

<p>Definition at line 551 of file <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/ipo/sampleprofile-cpp">SampleProfile.cpp</a>.</p>


<p>Referenced by <a href="#af64b545a1de5a343850725733d522546">buildProfiledCallGraph</a>, <a href="#a7e1da8085095c6d808713b280edb143b">doInitialization</a>, <a href="#a219e9fac05a219d48a97e03304f84613">findCalleeFunctionSamples</a>, <a href="#aa9137eda03e0c2cfd6eebaa55dfdd4cc">findExternalInlineCandidate</a>, <a href="#a2c88d6b3f033c87b7304db47133a930e">findFunctionSamples</a>, <a href="#abf8457f6ea82a821ee3fb08dae6246d9">findIndirectCallFunctionSamples</a>, <a href="#ae0bf03df2431c543590180658ce4709d">inlineHotFunctionsWithPriority</a>, <a href="#a358b28b8ab641a2a22ed8849a2dff2cf">runOnFunction</a> and <a href="#adb1dafd461988f3d8e687eabb99e108d">tryInlineCandidate</a>.</p>

</div>
</div>

### DisableSampleProfileInlining {#aac6219556110a8ac4a20f7c6a49dc0c9}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool anonymous{SampleProfile.cpp}::SampleProfileLoader::DisableSampleProfileInlining</td>
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



<p>Definition at line 599 of file <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/ipo/sampleprofile-cpp">SampleProfile.cpp</a>.</p>


<p>Referenced by <a href="#a7e1da8085095c6d808713b280edb143b">doInitialization</a>, <a href="#a5133b642b31dcbfad681874ba97d5914">SampleProfileLoader</a>, <a href="#adb1dafd461988f3d8e687eabb99e108d">tryInlineCandidate</a> and <a href="#ad5c772a0b61cb29106af3a4f9ae43d59">tryPromoteAndInlineCandidate</a>.</p>

</div>
</div>

### ExternalInlineAdvisor {#a7d8fb7d2b619a9afafc3add8e9c11eb9}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">std::unique_ptr&lt;InlineAdvisor&gt; anonymous{SampleProfile.cpp}::SampleProfileLoader::ExternalInlineAdvisor</td>
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



<p>Definition at line 604 of file <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/ipo/sampleprofile-cpp">SampleProfile.cpp</a>.</p>


<p>Referenced by <a href="#a7e1da8085095c6d808713b280edb143b">doInitialization</a>, <a href="#ab8641bf75d896ad3caffd68a441c4a7e">getExternalInlineAdvisorCost</a>, <a href="#aa730b58924baf8f35394c2e5a0bb3714">inlineHotFunctions</a> and <a href="#ae0bf03df2431c543590180658ce4709d">inlineHotFunctionsWithPriority</a>.</p>

</div>
</div>

### FuncNameToProfNameMap {#ade23e6b6f4c8e772b888612e156b5344}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">HashKeyMap&lt;std::unordered_map, FunctionId, FunctionId&gt; anonymous{SampleProfile.cpp}::SampleProfileLoader::FuncNameToProfNameMap</td>
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

<p>Map from function name to profile name generated by call-graph based profile fuzzy matching(–salvage-unused-profile).</p>

<p>Definition at line 543 of file <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/ipo/sampleprofile-cpp">SampleProfile.cpp</a>.</p>


<p>Referenced by <a href="#a7e1da8085095c6d808713b280edb143b">doInitialization</a>, <a href="#a219e9fac05a219d48a97e03304f84613">findCalleeFunctionSamples</a>, <a href="#a2c88d6b3f033c87b7304db47133a930e">findFunctionSamples</a> and <a href="#a25da45ec2b5b7dacb22e831cb7aef0c5">runOnModule</a>.</p>

</div>
</div>

### GetAC {#aaa4377cfbfd513fba3113fa91210a0c4}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">std::function&lt;AssumptionCache &amp;(Function &amp;)&gt; anonymous{SampleProfile.cpp}::SampleProfileLoader::GetAC</td>
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



<p>Definition at line 545 of file <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/ipo/sampleprofile-cpp">SampleProfile.cpp</a>.</p>


<p>Referenced by <a href="#a5133b642b31dcbfad681874ba97d5914">SampleProfileLoader</a>, <a href="#a518b0cf18edfb9fb05aaa530550af870">shouldInlineCandidate</a>, <a href="#a902b6197889c703bbe3c087f8bcf0789">shouldInlineColdCallee</a> and <a href="#adb1dafd461988f3d8e687eabb99e108d">tryInlineCandidate</a>.</p>

</div>
</div>

### GetTLI {#ad152203aa6393f06c0b955e3f70b94dd}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">std::function&lt;const TargetLibraryInfo &amp;(Function &amp;)&gt; anonymous{SampleProfile.cpp}::SampleProfileLoader::GetTLI</td>
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



<p>Definition at line 547 of file <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/ipo/sampleprofile-cpp">SampleProfile.cpp</a>.</p>


<p>Referenced by <a href="#a5133b642b31dcbfad681874ba97d5914">SampleProfileLoader</a>, <a href="#a518b0cf18edfb9fb05aaa530550af870">shouldInlineCandidate</a> and <a href="#a902b6197889c703bbe3c087f8bcf0789">shouldInlineColdCallee</a>.</p>

</div>
</div>

### GetTTI {#aa6421c02e92eda93cce39ae1adc23f45}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">std::function&lt;TargetTransformInfo &amp;(Function &amp;)&gt; anonymous{SampleProfile.cpp}::SampleProfileLoader::GetTTI</td>
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



<p>Definition at line 546 of file <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/ipo/sampleprofile-cpp">SampleProfile.cpp</a>.</p>


<p>Referenced by <a href="#a5133b642b31dcbfad681874ba97d5914">SampleProfileLoader</a>, <a href="#a518b0cf18edfb9fb05aaa530550af870">shouldInlineCandidate</a> and <a href="#a902b6197889c703bbe3c087f8bcf0789">shouldInlineColdCallee</a>.</p>

</div>
</div>

### GUIDsInProfile {#a99625599858fb55fe0892163548436b3}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">llvm::DenseSet&lt;uint64_t&gt; anonymous{SampleProfile.cpp}::SampleProfileLoader::GUIDsInProfile</td>
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



<p>Definition at line 590 of file <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/ipo/sampleprofile-cpp">SampleProfile.cpp</a>.</p>


<p>Referenced by <a href="#a7e1da8085095c6d808713b280edb143b">doInitialization</a> and <a href="#a358b28b8ab641a2a22ed8849a2dff2cf">runOnFunction</a>.</p>

</div>
</div>

### GUIDToFuncNameMap {#a86674e88fdb911aab10f14aa01863d88}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">DenseMap&lt;uint64_t, StringRef&gt; anonymous{SampleProfile.cpp}::SampleProfileLoader::GUIDToFuncNameMap</td>
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



<p>Definition at line 581 of file <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/ipo/sampleprofile-cpp">SampleProfile.cpp</a>.</p>


<p>Referenced by <a href="#a7e1da8085095c6d808713b280edb143b">doInitialization</a> and <a href="#a25da45ec2b5b7dacb22e831cb7aef0c5">runOnModule</a>.</p>

</div>
</div>

### LTOPhase {#a16100da114bdba0571c38edc371835d8}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">const ThinOrFullLTOPhase anonymous{SampleProfile.cpp}::SampleProfileLoader::LTOPhase</td>
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

<p>Flag indicating which LTO/ThinLTO phase the pass is invoked in.</p>


<p>We need to know the LTO phase because for example in ThinLTOPrelink phase, in annotation, we should not promote indirect calls. Instead, we will mark GUIDs that needs to be annotated to the function.</p>


<p>Definition at line 558 of file <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/ipo/sampleprofile-cpp">SampleProfile.cpp</a>.</p>


<p>Referenced by <a href="#a7e1da8085095c6d808713b280edb143b">doInitialization</a>, <a href="#aa730b58924baf8f35394c2e5a0bb3714">inlineHotFunctions</a>, <a href="#ae0bf03df2431c543590180658ce4709d">inlineHotFunctionsWithPriority</a> and <a href="#a5133b642b31dcbfad681874ba97d5914">SampleProfileLoader</a>.</p>

</div>
</div>

### MatchingManager {#a7bac1f5f852f643b10b9e02862e2b3ab}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">std::unique_ptr&lt;SampleProfileMatcher&gt; anonymous{SampleProfile.cpp}::SampleProfileLoader::MatchingManager</td>
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



<p>Definition at line 607 of file <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/ipo/sampleprofile-cpp">SampleProfile.cpp</a>.</p>


<p>Referenced by <a href="#a7e1da8085095c6d808713b280edb143b">doInitialization</a> and <a href="#a25da45ec2b5b7dacb22e831cb7aef0c5">runOnModule</a>.</p>

</div>
</div>

### NamesInProfile {#a13d326ade07b8cc14d4e307253b2797b}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">StringSet anonymous{SampleProfile.cpp}::SampleProfileLoader::NamesInProfile</td>
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



<p>Definition at line 585 of file <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/ipo/sampleprofile-cpp">SampleProfile.cpp</a>.</p>


<p>Referenced by <a href="#a7e1da8085095c6d808713b280edb143b">doInitialization</a> and <a href="#a358b28b8ab641a2a22ed8849a2dff2cf">runOnFunction</a>.</p>

</div>
</div>

### notInlinedCallInfo {#a09c53287a76f1544e782601e437149be}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">DenseMap&lt;Function *, NotInlinedProfileInfo&gt; anonymous{SampleProfile.cpp}::SampleProfileLoader::notInlinedCallInfo</td>
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



<p>Definition at line 577 of file <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/ipo/sampleprofile-cpp">SampleProfile.cpp</a>.</p>


<p>Referenced by <a href="#a16e99ef185f55c3e45caf11c880998ff">promoteMergeNotInlinedContextSamples</a> and <a href="#a25da45ec2b5b7dacb22e831cb7aef0c5">runOnModule</a>.</p>

</div>
</div>

### ProfAccForSymsInList {#a08e4315133d1d023573bd96e627d0dc0}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool anonymous{SampleProfile.cpp}::SampleProfileLoader::ProfAccForSymsInList</td>
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



<p>Definition at line 597 of file <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/ipo/sampleprofile-cpp">SampleProfile.cpp</a>.</p>


<p>Referenced by <a href="#a7e1da8085095c6d808713b280edb143b">doInitialization</a>, <a href="#aa730b58924baf8f35394c2e5a0bb3714">inlineHotFunctions</a>, <a href="#ae0bf03df2431c543590180658ce4709d">inlineHotFunctionsWithPriority</a> and <a href="#a358b28b8ab641a2a22ed8849a2dff2cf">runOnFunction</a>.</p>

</div>
</div>

### PSL {#a3329c2209e8b3bc0cd93bd6172ef16ca}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">std::shared_ptr&lt;ProfileSymbolList&gt; anonymous{SampleProfile.cpp}::SampleProfileLoader::PSL</td>
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

<p>Profle Symbol list tells whether a function name appears in the binary used to generate the current profile.</p>

<p>Definition at line 563 of file <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/ipo/sampleprofile-cpp">SampleProfile.cpp</a>.</p>


<p>Referenced by <a href="#a7e1da8085095c6d808713b280edb143b">doInitialization</a> and <a href="#a358b28b8ab641a2a22ed8849a2dff2cf">runOnFunction</a>.</p>

</div>
</div>

### SymbolMap {#a36a42d67af221fe58af6d4e4fa30ce96}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">HashKeyMap&lt;std::unordered_map, FunctionId, Function *&gt; anonymous{SampleProfile.cpp}::SampleProfileLoader::SymbolMap</td>
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

<p>Map from function name to <a href="/web-llvm/docs/api/classes/llvm/function">Function</a> *.</p>


<p>Used to find the function from the function name. If the function name contains suffix, additional entry is added to map from the stripped name to the function if there is one-to-one mapping.</p>


<p>Definition at line 539 of file <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/ipo/sampleprofile-cpp">SampleProfile.cpp</a>.</p>


<p>Referenced by <a href="#a0f9647d7bd1eb0c38198f05b3d34d4f3">buildFunctionOrder</a>, <a href="#a7e1da8085095c6d808713b280edb143b">doInitialization</a>, <a href="#aa9137eda03e0c2cfd6eebaa55dfdd4cc">findExternalInlineCandidate</a>, <a href="#a25da45ec2b5b7dacb22e831cb7aef0c5">runOnModule</a> and <a href="#ad5c772a0b61cb29106af3a4f9ae43d59">tryPromoteAndInlineCandidate</a>.</p>

</div>
</div>

### TotalCollectedSamples {#a03dd9387104275f69afacd119f353c10}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">uint64_t anonymous{SampleProfile.cpp}::SampleProfileLoader::TotalCollectedSamples = 0</td>
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

<p>Total number of samples collected in this profile.</p>


<p>This is the sum of all the samples collected in all the functions executed at runtime.</p>


<p>Definition at line 569 of file <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/ipo/sampleprofile-cpp">SampleProfile.cpp</a>.</p>


<p>Referenced by <a href="#a25da45ec2b5b7dacb22e831cb7aef0c5">runOnModule</a>.</p>

</div>
</div>

### UseFlattenedProfile {#a641b8ee0f58b045f31b9376e927a0b49}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool anonymous{SampleProfile.cpp}::SampleProfileLoader::UseFlattenedProfile</td>
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



<p>Definition at line 601 of file <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/ipo/sampleprofile-cpp">SampleProfile.cpp</a>.</p>


<p>Referenced by <a href="#a7e1da8085095c6d808713b280edb143b">doInitialization</a> and <a href="#a5133b642b31dcbfad681874ba97d5914">SampleProfileLoader</a>.</p>

</div>
</div>

</div>

<hr/>

The documentation for this class was generated from the following file:

<ul>
<li><a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/ipo/sampleprofile-cpp">SampleProfile.cpp</a></li>
</ul>

<hr/>

<p class="doxyGeneratedBy">Generated via <a href="https://github.com/xpack/doxygen2docusaurus">doxygen2docusaurus</a> by <a href="https://www.doxygen.nl">Doxygen</a> 1.15.0.</p>

</div>
