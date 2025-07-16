---

# DO NOT EDIT!
# Automatically generated via doxygen2docusaurus by Doxygen.

slug: /api/files/lib/lib/transforms/lib/transforms/ipo/sampleprofile-cpp
custom_edit_url: null
toc_max_heading_level: 4
keywords:
  - doxygen
  - reference
  - file

---

<div class="doxyPage">

# The `SampleProfile.cpp` File Reference



## Included Headers

<div class="doxyIncludesList">#include "<a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/transforms/include/llvm/transforms/ipo/sampleprofile-h">llvm/Transforms/IPO/SampleProfile.h</a>"
#include "<a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/adt/arrayref-h">llvm/ADT/ArrayRef.h</a>"
#include "<a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/adt/densemap-h">llvm/ADT/DenseMap.h</a>"
#include "<a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/adt/denseset-h">llvm/ADT/DenseSet.h</a>"
#include "<a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/adt/mapvector-h">llvm/ADT/MapVector.h</a>"
#include "<a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/adt/priorityqueue-h">llvm/ADT/PriorityQueue.h</a>"
#include "<a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/adt/scciterator-h">llvm/ADT/SCCIterator.h</a>"
#include "<a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/adt/smallvector-h">llvm/ADT/SmallVector.h</a>"
#include "<a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/adt/statistic-h">llvm/ADT/Statistic.h</a>"
#include "<a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/adt/stringref-h">llvm/ADT/StringRef.h</a>"
#include "<a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/adt/twine-h">llvm/ADT/Twine.h</a>"
#include "<a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/analysis/assumptioncache-h">llvm/Analysis/AssumptionCache.h</a>"
#include "<a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/analysis/blockfrequencyinfoimpl-h">llvm/Analysis/BlockFrequencyInfoImpl.h</a>"
#include "<a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/analysis/inlineadvisor-h">llvm/Analysis/InlineAdvisor.h</a>"
#include "<a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/analysis/inlinecost-h">llvm/Analysis/InlineCost.h</a>"
#include "<a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/analysis/lazycallgraph-h">llvm/Analysis/LazyCallGraph.h</a>"
#include "<a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/analysis/optimizationremarkemitter-h">llvm/Analysis/OptimizationRemarkEmitter.h</a>"
#include "<a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/analysis/profilesummaryinfo-h">llvm/Analysis/ProfileSummaryInfo.h</a>"
#include "<a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/analysis/replayinlineadvisor-h">llvm/Analysis/ReplayInlineAdvisor.h</a>"
#include "<a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/analysis/targetlibraryinfo-h">llvm/Analysis/TargetLibraryInfo.h</a>"
#include "<a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/analysis/targettransforminfo-h">llvm/Analysis/TargetTransformInfo.h</a>"
#include "<a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/ir/basicblock-h">llvm/IR/BasicBlock.h</a>"
#include "<a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/ir/debugloc-h">llvm/IR/DebugLoc.h</a>"
#include "<a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/ir/diagnosticinfo-h">llvm/IR/DiagnosticInfo.h</a>"
#include "<a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/ir/function-h">llvm/IR/Function.h</a>"
#include "<a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/ir/globalvalue-h">llvm/IR/GlobalValue.h</a>"
#include "<a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/ir/instrtypes-h">llvm/IR/InstrTypes.h</a>"
#include "<a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/ir/instruction-h">llvm/IR/Instruction.h</a>"
#include "<a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/ir/instructions-h">llvm/IR/Instructions.h</a>"
#include "<a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/ir/intrinsicinst-h">llvm/IR/IntrinsicInst.h</a>"
#include "<a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/ir/llvmcontext-h">llvm/IR/LLVMContext.h</a>"
#include "<a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/ir/mdbuilder-h">llvm/IR/MDBuilder.h</a>"
#include "<a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/ir/module-h">llvm/IR/Module.h</a>"
#include "<a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/ir/passmanager-h">llvm/IR/PassManager.h</a>"
#include "<a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/ir/profdatautils-h">llvm/IR/ProfDataUtils.h</a>"
#include "<a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/ir/pseudoprobe-h">llvm/IR/PseudoProbe.h</a>"
#include "<a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/ir/valuesymboltable-h">llvm/IR/ValueSymbolTable.h</a>"
#include "<a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/profiledata/instrprof-h">llvm/ProfileData/InstrProf.h</a>"
#include "<a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/profiledata/sampleprof-h">llvm/ProfileData/SampleProf.h</a>"
#include "<a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/profiledata/sampleprofreader-h">llvm/ProfileData/SampleProfReader.h</a>"
#include "<a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/support/casting-h">llvm/Support/Casting.h</a>"
#include "<a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/support/commandline-h">llvm/Support/CommandLine.h</a>"
#include "<a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/support/debug-h">llvm/Support/Debug.h</a>"
#include "<a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/support/erroror-h">llvm/Support/ErrorOr.h</a>"
#include "<a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/support/virtualfilesystem-h">llvm/Support/VirtualFileSystem.h</a>"
#include "<a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/support/raw-ostream-h">llvm/Support/raw_ostream.h</a>"
#include "<a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/transforms/ipo-h">llvm/Transforms/IPO.h</a>"
#include "<a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/transforms/include/llvm/transforms/ipo/profiledcallgraph-h">llvm/Transforms/IPO/ProfiledCallGraph.h</a>"
#include "<a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/transforms/include/llvm/transforms/ipo/samplecontexttracker-h">llvm/Transforms/IPO/SampleContextTracker.h</a>"
#include "<a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/transforms/include/llvm/transforms/ipo/sampleprofilematcher-h">llvm/Transforms/IPO/SampleProfileMatcher.h</a>"
#include "<a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/transforms/include/llvm/transforms/ipo/sampleprofileprobe-h">llvm/Transforms/IPO/SampleProfileProbe.h</a>"
#include "<a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/transforms/include/llvm/transforms/utils/callpromotionutils-h">llvm/Transforms/Utils/CallPromotionUtils.h</a>"
#include "<a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/transforms/include/llvm/transforms/utils/cloning-h">llvm/Transforms/Utils/Cloning.h</a>"
#include "<a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/transforms/include/llvm/transforms/utils/instrumentation-h">llvm/Transforms/Utils/Instrumentation.h</a>"
#include "<a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/transforms/include/llvm/transforms/utils/misexpect-h">llvm/Transforms/Utils/MisExpect.h</a>"
#include "<a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/transforms/include/llvm/transforms/utils/sampleprofileloaderbaseimpl-h">llvm/Transforms/Utils/SampleProfileLoaderBaseImpl.h</a>"
#include "<a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/transforms/include/llvm/transforms/utils/sampleprofileloaderbaseutil-h">llvm/Transforms/Utils/SampleProfileLoaderBaseUtil.h</a>"
#include &lt;algorithm&gt;
#include &lt;cassert&gt;
#include &lt;cstdint&gt;
#include &lt;functional&gt;
#include &lt;limits&gt;
#include &lt;map&gt;
#include &lt;memory&gt;
#include &lt;queue&gt;
#include &lt;string&gt;
#include &lt;system_error&gt;
#include &lt;utility&gt;
#include &lt;vector&gt;
</div>

## Namespaces Index

<table class="doxyMembersIndex">

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">namespace</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="/web-llvm/docs/api/namespaces/llvm">llvm</a></td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>This is an optimization pass for GlobalISel generic memory operations. <a href="/web-llvm/docs/api/namespaces/llvm/#details">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">namespace</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="/web-llvm/docs/api/namespaces/anonymous-sampleprofile-cpp-">anonymous{SampleProfile.cpp}</a></td>
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

## Classes Index

<table class="doxyMembersIndex">

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">class</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="/web-llvm/docs/api/classes/anonymous-sampleprofile-cpp-/guidtofuncnamemapper">GUIDToFuncNameMapper</a></td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="/web-llvm/docs/api/structs/anonymous-sampleprofile-cpp-/inlinecandidate">InlineCandidate</a></td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="/web-llvm/docs/api/structs/anonymous-sampleprofile-cpp-/candidatecomparer">CandidateComparer</a></td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">class</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="/web-llvm/docs/api/classes/anonymous-sampleprofile-cpp-/sampleprofileloader">SampleProfileLoader</a></td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Sample profile pass. <a href="/web-llvm/docs/api/classes/anonymous-sampleprofile-cpp-/sampleprofileloader/#details">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">struct</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="/web-llvm/docs/api/structs/anonymous-sampleprofile-cpp-/sampleprofileloader/notinlinedprofileinfo">NotInlinedProfileInfo</a></td>
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

## Functions Index

<table class="doxyMembersIndex">

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a043ee38f41b13487f8e0ef4f74cc600d">STATISTIC</a> (NumCSInlined, "Number of functions inlined with context sensitive profile")</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a645f77fa2f8d80cd7269b393eab19f76">STATISTIC</a> (NumCSNotInlined, "Number of functions not inlined with context sensitive profile")</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a46c2637d19fc97fa8af274512b3d6fe9">STATISTIC</a> (NumMismatchedProfile, "Number of functions with CFG mismatched profile")</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ada628920f6270698bc899d52ce29f681">STATISTIC</a> (NumMatchedProfile, "Number of functions with CFG matched profile")</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a185d42a572de583b7604376b4ea3660c">STATISTIC</a> (NumDuplicatedInlinesite, "Number of inlined callsites with a partial distribution factor")</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a9c8fc785df9ca40ae647d7bd297edf4d">STATISTIC</a> (NumCSInlinedHitMinLimit, "Number of functions with FDO inline stopped due to min size limit")</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a4df177ce3a429f975041e866a6cf0453">STATISTIC</a> (NumCSInlinedHitMaxLimit, "Number of functions with FDO inline stopped due to max size limit")</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#acee6f38eb8e4ddba9973ec3c31d83b44">STATISTIC</a> (NumCSInlinedHitGrowthLimit, "Number of functions with FDO inline stopped due to growth size limit")</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">static bool</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#aa2ce415bf980facbbfb4eb13a1e9ce54">doesHistoryAllowICP</a> (const Instruction &amp;Inst, StringRef Candidate)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p><a href="/web-llvm/docs/api/namespaces/llvm/check">Check</a> whether the indirect call promotion history of <span class="doxyComputerOutput">Inst</span> allows the promotion for <span class="doxyComputerOutput">Candidate</span>. <a href="#aa2ce415bf980facbbfb4eb13a1e9ce54">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">static void</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a5c3b919b227c332257bcc77ec8c9df00">updateIDTMetaData</a> (Instruction &amp;Inst, const SmallVectorImpl&lt; InstrProfValueData &gt; &amp;CallTargets, uint64_t Sum)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Update indirect call target profile metadata for <span class="doxyComputerOutput">Inst</span>. <a href="#a5c3b919b227c332257bcc77ec8c9df00">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">static <a href="/web-llvm/docs/api/classes/llvm/smallvector">SmallVector</a>&lt; InstrProfValueData, 2 &gt;</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#aaf55fbc9b8550957ceb81da6a13f54e4">GetSortedValueDataFromCallTargets</a> (const SampleRecord::CallTargetMap &amp;M)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Returns the sorted CallTargetMap <span class="doxyComputerOutput">M</span> by count in descending order. <a href="#aaf55fbc9b8550957ceb81da6a13f54e4">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

</table>

## Variables Index

<table class="doxyMembersIndex">

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">static <a href="/web-llvm/docs/api/classes/llvm/cl/opt">cl::opt</a>&lt; <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/demangle/itaniumdemangle-h/#ae2b0d0345572d6718e219aa76d1d54edab45cffe084dd3d20d928bee85e7b0f21">std::string</a> &gt;</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a055c6b7054a94b338830b3da8ecc4023">SampleProfileFile</a>("sample-profile-file", cl::init(""), cl::value_desc("filename"), cl::desc("Profile file loaded by -sample-profile"), cl::Hidden)</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">static <a href="/web-llvm/docs/api/classes/llvm/cl/opt">cl::opt</a>&lt; <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/demangle/itaniumdemangle-h/#ae2b0d0345572d6718e219aa76d1d54edab45cffe084dd3d20d928bee85e7b0f21">std::string</a> &gt;</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#af8d3791537a44c00b699d28c4d978d82">SampleProfileRemappingFile</a>("sample-profile-remapping-file", cl::init(""), cl::value_desc("filename"), cl::desc("Profile remapping file loaded by -sample-profile"), cl::Hidden)</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/cl/opt">cl::opt</a>&lt; bool &gt;</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#addfc98fccc9f0617cf933d80dc634f2c">SalvageStaleProfile</a>("salvage-stale-profile", cl::Hidden, cl::init(false), cl::desc("Salvage stale profile by fuzzy matching and use the remapped " "location for sample profile query."))</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/cl/opt">cl::opt</a>&lt; bool &gt;</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a176dcdd54b914f2847535fc7c8f1f77b">SalvageUnusedProfile</a>("salvage-unused-profile", cl::Hidden, cl::init(false), cl::desc("Salvage unused profile by matching with new " "functions on call graph."))</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/cl/opt">cl::opt</a>&lt; bool &gt;</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#accaf075320be45eaba2a9cbf611368a9">ReportProfileStaleness</a>("report-profile-staleness", cl::Hidden, cl::init(false), cl::desc("Compute and report stale profile statistical metrics."))</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/cl/opt">cl::opt</a>&lt; bool &gt;</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a997d20da5b25193880115dc8a0b5e4ee">PersistProfileStaleness</a>("persist-profile-staleness", cl::Hidden, cl::init(false), cl::desc("Compute stale profile statistical metrics and write it into the " "native object file(.llvm_stats section)."))</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#af00e1c8a074b97aedd1a2db33dea6753">ProfileSampleAccurate</a>("profile-sample-accurate", cl::Hidden, cl::init(false), cl::desc("If the sample profile is accurate, we will mark all un-sampled " "callsite and function as having 0 samples. Otherwise, treat " "un-sampled callsites and functions conservatively as unknown. "))</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a2612d121382d9498fc6fc0acd70a0cf4">ProfileSampleBlockAccurate</a>("profile-sample-block-accurate", cl::Hidden, cl::init(false), cl::desc("If the sample profile is accurate, we will mark all un-sampled " "branches and calls as having 0 samples. Otherwise, treat " "them conservatively as unknown. "))</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a88e2b32b6c2ab29b0b4470f5a1a32364">ProfileAccurateForSymsInList</a>("profile-accurate-for-symsinlist", cl::Hidden, cl::init(true), cl::desc("For symbols in profile symbol list, regard their profiles to " "be accurate. It may be overridden by profile-sample-accurate. "))</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a8b16dbb3ebefd05908afe3a7874d6353">ProfileMergeInlinee</a>("sample-profile-merge-inlinee", cl::Hidden, cl::init(true), cl::desc("Merge past inlinee's profile to outline version if sample " "profile loader decided not to inline a call site. It will " "only be enabled when top-down order of profile loading is " "enabled. "))</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#aeeed05c14d5103af2df4ef16b3d12674">ProfileTopDownLoad</a>("sample-profile-top-down-load", cl::Hidden, cl::init(true), cl::desc("Do profile annotation and inlining for functions in top-down " "order of call graph during sample profile loading. It only " "works for new pass manager. "))</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ab5c0de16382c784463afd1d0749521b2">UseProfiledCallGraph</a>("use-profiled-call-graph", cl::init(true), cl::Hidden, cl::desc("Process functions in a top-down order " "defined by the profiled call graph when " "-sample-profile-top-down-load is on."))</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ada8f2c564085d598909fb28464614812">ProfileSizeInline</a>("sample-profile-inline-size", cl::Hidden, cl::init(false), cl::desc("Inline cold call sites in profile loader if it's beneficial " "for code size."))</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a3ea40d9c4ddb417257d8c7c5f8bfe981">DisableSampleLoaderInlining</a>("disable-sample-loader-inlining", cl::Hidden, cl::init(false), cl::desc("If true, artificially skip inline transformation in sample-loader " "pass, and merge (or scale) profiles (as configured by " "--sample-profile-merge-inlinee)."))</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">static <a href="/web-llvm/docs/api/classes/llvm/cl/opt">cl::opt</a>&lt; unsigned &gt;</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#abe3f89debe4f7888460625789de78083">ProfileICPRelativeHotness</a>("sample-profile-icp-relative-hotness", cl::Hidden, cl::init(25), cl::desc("Relative hotness percentage threshold for indirect " "call promotion in proirity-based sample profile loader inlining."))</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">static <a href="/web-llvm/docs/api/classes/llvm/cl/opt">cl::opt</a>&lt; unsigned &gt;</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ac689c456b39941e3af203d3e1750b8b5">ProfileICPRelativeHotnessSkip</a>("sample-profile-icp-relative-hotness-skip", cl::Hidden, cl::init(1), cl::desc("Skip relative hotness check for ICP up to given number of targets."))</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">static <a href="/web-llvm/docs/api/classes/llvm/cl/opt">cl::opt</a>&lt; unsigned &gt;</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#af9dc2d6d5404e7d42198490fa3be4e73">HotFuncCutoffForStalenessError</a>("hot-func-cutoff-for-staleness-error", cl::Hidden, cl::init(800000), cl::desc("A function is considered hot for staleness error check if its " "total sample count is above the specified percentile"))</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">static <a href="/web-llvm/docs/api/classes/llvm/cl/opt">cl::opt</a>&lt; unsigned &gt;</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a0839b336a4cfa394f0a6df99af24c122">MinfuncsForStalenessError</a>("min-functions-for-staleness-error", cl::Hidden, cl::init(50), cl::desc("Skip the check if the number of hot functions is smaller than " "the specified number."))</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">static <a href="/web-llvm/docs/api/classes/llvm/cl/opt">cl::opt</a>&lt; unsigned &gt;</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a31561104790d3759baa688de077367ce">PrecentMismatchForStalenessError</a>("precent-mismatch-for-staleness-error", cl::Hidden, cl::init(80), cl::desc("Reject the profile if the mismatch percent is higher than the " "given number."))</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a9eaaeedd35128b9508715b2c16dd58f5">CallsitePrioritizedInline</a>("sample-profile-prioritized-inline", cl::Hidden, cl::desc("Use call site prioritized inlining for sample profile loader. " "Currently only CSSPGO is supported."))</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ad07d06e65e4610fb8ac7b13e868ec1c9">UsePreInlinerDecision</a>("sample-profile-use-preinliner", cl::Hidden, cl::desc("Use the preinliner decisions stored in profile context."))</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#af5f668624e8264858b5efb9127b3be47">AllowRecursiveInline</a>("sample-profile-recursive-inline", cl::Hidden, cl::desc("Allow sample loader inliner to inline recursive calls."))</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a43f756cf4ee4b9d99c35677a3aa852af">RemoveProbeAfterProfileAnnotation</a>("sample-profile-remove-probe", cl::Hidden, cl::init(false), cl::desc("Remove pseudo-probe after sample profile annotation."))</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">static <a href="/web-llvm/docs/api/classes/llvm/cl/opt">cl::opt</a>&lt; <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/demangle/itaniumdemangle-h/#ae2b0d0345572d6718e219aa76d1d54edab45cffe084dd3d20d928bee85e7b0f21">std::string</a> &gt;</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a732d61bd469914910adee6ed8c8c4a38">ProfileInlineReplayFile</a>("sample-profile-inline-replay", cl::init(""), cl::value_desc("filename"), cl::desc("Optimization remarks file containing inline remarks to be replayed " "by inlining from sample profile loader."), cl::Hidden)</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">static <a href="/web-llvm/docs/api/classes/llvm/cl/opt">cl::opt</a>&lt; <a href="/web-llvm/docs/api/structs/llvm/replayinlinersettings/#a692270e0daa8cc3ffb3d83238afcd4b5">ReplayInlinerSettings::Scope</a> &gt;</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ab75eb24423b8e8d730f81eec23e93f43">ProfileInlineReplayScope</a>("sample-profile-inline-replay-scope", cl::init(ReplayInlinerSettings::Scope::Function), cl::values(clEnumValN(ReplayInlinerSettings::Scope::Function, "Function", "Replay on functions that have remarks associated " "with them (default)"), clEnumValN(ReplayInlinerSettings::Scope::Module, "Module", "Replay on the entire module")), cl::desc("Whether inline replay should be applied to the entire " "Module or just the Functions (default) that are present as " "callers in remarks during sample profile inlining."), cl::Hidden)</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">static <a href="/web-llvm/docs/api/classes/llvm/cl/opt">cl::opt</a>&lt; <a href="/web-llvm/docs/api/structs/llvm/replayinlinersettings/#a49a0d94e62049ec7cf29edc327856d0d">ReplayInlinerSettings::Fallback</a> &gt;</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a477f441a65d57a1d0bff97e993e0f5d3">ProfileInlineReplayFallback</a>("sample-profile-inline-replay-fallback", cl::init(ReplayInlinerSettings::Fallback::Original), cl::values(clEnumValN(ReplayInlinerSettings::Fallback::Original, "Original", "All decisions not in replay send to original advisor (default)"), clEnumValN(ReplayInlinerSettings::Fallback::AlwaysInline, "AlwaysInline", "All decisions not in replay are inlined"), clEnumValN(ReplayInlinerSettings::Fallback::NeverInline, "NeverInline", "All decisions not in replay are not inlined")), cl::desc("How sample profile inline replay treats sites that don't come " "from the replay. Original: defers to original advisor, " "AlwaysInline: inline all sites not in replay, NeverInline: " "inline no sites not in replay"), cl::Hidden)</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">static <a href="/web-llvm/docs/api/classes/llvm/cl/opt">cl::opt</a>&lt; <a href="/web-llvm/docs/api/structs/llvm/callsiteformat/#afd04e6f91cb72fa5dd456253fd595689">CallSiteFormat::Format</a> &gt;</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#af61ae5b7d50b9b36cc3a2350ded45f82">ProfileInlineReplayFormat</a>("sample-profile-inline-replay-format", cl::init(CallSiteFormat::Format::LineColumnDiscriminator), cl::values(clEnumValN(CallSiteFormat::Format::Line, "Line", "<Line Number>"), clEnumValN(CallSiteFormat::Format::LineColumn, "LineColumn", "<Line Number>:<Column Number>"), clEnumValN(CallSiteFormat::Format::LineDiscriminator, "LineDiscriminator", "<Line Number>.<Discriminator>"), clEnumValN(CallSiteFormat::Format::LineColumnDiscriminator, "LineColumnDiscriminator", "<Line Number>:<Column Number>.<Discriminator> (default)")), cl::desc("How sample profile inline replay file is formatted"), cl::Hidden)</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">static <a href="/web-llvm/docs/api/classes/llvm/cl/opt">cl::opt</a>&lt; unsigned &gt;</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a46f9ffda019c1ffa7dd85cf1a22435a3">MaxNumPromotions</a>("sample-profile-icp-max-prom", cl::init(3), cl::Hidden, cl::desc("Max number of promotions for a single indirect " "call callsite in sample profile loader"))</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a4880524206cd6bd2551dda5c915be189">OverwriteExistingWeights</a>("overwrite-existing-weights", cl::Hidden, cl::init(false), cl::desc("Ignore existing branch weights on IR and always overwrite."))</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a6249b41b02fca2bc7c121511ad72062b">AnnotateSampleProfileInlinePhase</a>("annotate-sample-profile-inline-phase", cl::Hidden, cl::init(false), cl::desc("Annotate LTO phase (prelink / postlink), or main (no LTO) for " "sample-profile inline pass name."))</td>
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

## Macro Definitions Index

<table class="doxyMembersIndex">

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">#define</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ad78e062f62e0d6e453941fb4ca843e4d">DEBUG_TYPE</a>&nbsp;&nbsp;&nbsp;"sample-profile"</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">#define</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ab4932d7673e6e1138d8a2671f16865d1">CSINLINE_DEBUG</a>&nbsp;&nbsp;&nbsp;<a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/adt/genericcycleimpl-h/#ad78e062f62e0d6e453941fb4ca843e4d">DEBUG_TYPE</a> "-inline"</td>
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


<div class="doxySectionDef">

## Functions

### doesHistoryAllowICP() {#aa2ce415bf980facbbfb4eb13a1e9ce54}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool doesHistoryAllowICP (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/instruction">Instruction</a> &amp; Inst, <a href="/web-llvm/docs/api/classes/llvm/stringref">StringRef</a> Candidate)</td>
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

<p><a href="/web-llvm/docs/api/namespaces/llvm/check">Check</a> whether the indirect call promotion history of <span class="doxyComputerOutput">Inst</span> allows the promotion for <span class="doxyComputerOutput">Candidate</span>.</p>


<p>If the profile count for the promotion candidate <span class="doxyComputerOutput">Candidate</span> is NOMORE_ICP_MAGICNUM, it means <span class="doxyComputerOutput">Candidate</span> has already been promoted for <span class="doxyComputerOutput">Inst</span>. If we already have at least MaxNumPromotions NOMORE_ICP_MAGICNUM count values in the value profile of <span class="doxyComputerOutput">Inst</span>, we cannot promote for <span class="doxyComputerOutput">Inst</span> anymore.</p>


<p>Definition at line 811 of file <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/ipo/sampleprofile-cpp">SampleProfile.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/classes/llvm/globalvalue/#a6811428caf500217f319c74e80900c14">llvm::GlobalValue::getGUID</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a8f6ad5c1831928ee2c6c5058d9580edf">llvm::getValueProfDataFromInst</a>, <a href="/web-llvm/docs/api/files/lib/lib/analysis/indirectcallpromotionanalysis-cpp/#a8d1c61a222911b42ad7dc30bc6519d81">MaxNumPromotions</a> and <a href="/web-llvm/docs/api/namespaces/llvm/#aee20e86d3817849199a21d19bcc273c5">llvm::NOMORE_ICP_MAGICNUM</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/classes/anonymous-sampleprofile-cpp-/sampleprofileloader/#ad5c772a0b61cb29106af3a4f9ae43d59">anonymous{SampleProfile.cpp}::SampleProfileLoader::tryPromoteAndInlineCandidate</a>.</p>

</div>
</div>

### GetSortedValueDataFromCallTargets() {#aaf55fbc9b8550957ceb81da6a13f54e4}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">SmallVector&lt; InstrProfValueData, 2 &gt; GetSortedValueDataFromCallTargets (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/sampleprof/samplerecord/#a25d27170e0de5f9f6d999f8efa3cc32d">SampleRecord::CallTargetMap</a> &amp; M)</td>
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

<p>Returns the sorted CallTargetMap <span class="doxyComputerOutput">M</span> by count in descending order.</p>

<p>Definition at line 1608 of file <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/ipo/sampleprofile-cpp">SampleProfile.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/files/lib/lib/support/md5-cpp/#ac0eafdc9ee161b71e7af98af736952fd">I</a> and <a href="/web-llvm/docs/api/classes/llvm/sampleprof/samplerecord/#a63324042ea47580bcee3675b4351b704">llvm::sampleprof::SampleRecord::sortCallTargets</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/classes/anonymous-sampleprofile-cpp-/sampleprofileloader/#acf512f516130aaabdd835c48140c9e5c">anonymous{SampleProfile.cpp}::SampleProfileLoader::generateMDProfMetadata</a>.</p>

</div>
</div>

### STATISTIC() {#a043ee38f41b13487f8e0ef4f74cc600d}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">STATISTIC (NumCSInlined, "Number of <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/amdgpulowermoduleldspass-cpp/#a8818b45f8c07ddce635268ec684dc61a">functions</a> inlined with context sensitive profile")</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 101 of file <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/ipo/sampleprofile-cpp">SampleProfile.cpp</a>.</p>

</div>
</div>

### STATISTIC() {#a645f77fa2f8d80cd7269b393eab19f76}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">STATISTIC (NumCSNotInlined, "Number of <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/amdgpulowermoduleldspass-cpp/#a8818b45f8c07ddce635268ec684dc61a">functions</a> not inlined with context sensitive profile")</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 103 of file <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/ipo/sampleprofile-cpp">SampleProfile.cpp</a>.</p>

</div>
</div>

### STATISTIC() {#a46c2637d19fc97fa8af274512b3d6fe9}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">STATISTIC (NumMismatchedProfile, "Number of <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/amdgpulowermoduleldspass-cpp/#a8818b45f8c07ddce635268ec684dc61a">functions</a> with <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/scalar/flattencfgpass-cpp/#a78c5fc25b7e349ae0e4a32100404a4b4">CFG</a> mismatched profile")</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 105 of file <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/ipo/sampleprofile-cpp">SampleProfile.cpp</a>.</p>

</div>
</div>

### STATISTIC() {#ada628920f6270698bc899d52ce29f681}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">STATISTIC (NumMatchedProfile, "Number of <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/amdgpulowermoduleldspass-cpp/#a8818b45f8c07ddce635268ec684dc61a">functions</a> with <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/scalar/flattencfgpass-cpp/#a78c5fc25b7e349ae0e4a32100404a4b4">CFG</a> matched profile")</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 107 of file <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/ipo/sampleprofile-cpp">SampleProfile.cpp</a>.</p>

</div>
</div>

### STATISTIC() {#a185d42a572de583b7604376b4ea3660c}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">STATISTIC (NumDuplicatedInlinesite, "Number of inlined callsites with a partial distribution factor")</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 108 of file <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/ipo/sampleprofile-cpp">SampleProfile.cpp</a>.</p>

</div>
</div>

### STATISTIC() {#a9c8fc785df9ca40ae647d7bd297edf4d}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">STATISTIC (NumCSInlinedHitMinLimit, "Number of <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/amdgpulowermoduleldspass-cpp/#a8818b45f8c07ddce635268ec684dc61a">functions</a> with FDO <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/ipo/alwaysinliner-cpp/#a46ccdc20c42bb5ae5b9d313e12a68421">inline</a> stopped due to min <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/nvptx/nvvmreflect-cpp/#ac934769d93af95250952646a3829df4c">size</a> limit")</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 111 of file <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/ipo/sampleprofile-cpp">SampleProfile.cpp</a>.</p>

</div>
</div>

### STATISTIC() {#a4df177ce3a429f975041e866a6cf0453}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">STATISTIC (NumCSInlinedHitMaxLimit, "Number of <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/amdgpulowermoduleldspass-cpp/#a8818b45f8c07ddce635268ec684dc61a">functions</a> with FDO <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/ipo/alwaysinliner-cpp/#a46ccdc20c42bb5ae5b9d313e12a68421">inline</a> stopped due to max <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/nvptx/nvvmreflect-cpp/#ac934769d93af95250952646a3829df4c">size</a> limit")</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 113 of file <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/ipo/sampleprofile-cpp">SampleProfile.cpp</a>.</p>

</div>
</div>

### STATISTIC() {#acee6f38eb8e4ddba9973ec3c31d83b44}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">STATISTIC (NumCSInlinedHitGrowthLimit, "Number of <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/amdgpulowermoduleldspass-cpp/#a8818b45f8c07ddce635268ec684dc61a">functions</a> with FDO <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/ipo/alwaysinliner-cpp/#a46ccdc20c42bb5ae5b9d313e12a68421">inline</a> stopped due to growth <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/nvptx/nvvmreflect-cpp/#ac934769d93af95250952646a3829df4c">size</a> limit")</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 115 of file <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/ipo/sampleprofile-cpp">SampleProfile.cpp</a>.</p>

</div>
</div>

### updateIDTMetaData() {#a5c3b919b227c332257bcc77ec8c9df00}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void updateIDTMetaData (<a href="/web-llvm/docs/api/classes/llvm/instruction">Instruction</a> &amp; Inst, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/smallvectorimpl">SmallVectorImpl</a>&lt; InstrProfValueData &gt; &amp; CallTargets, uint64_t Sum)</td>
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

<p>Update indirect call target profile metadata for <span class="doxyComputerOutput">Inst</span>.</p>


<p>Usually <span class="doxyComputerOutput">Sum</span> is the sum of counts of all the targets for <span class="doxyComputerOutput">Inst</span>. If it is 0, it means updateIDTMetaData is used to mark a certain target to be promoted already. If it is not zero, we expect to use it to update the total count in the value profile.</p>


<p>Definition at line 844 of file <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/ipo/sampleprofile-cpp">SampleProfile.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/namespaces/llvm/#a68ee9c22fcc77e40d4ae44e5b37c7998">llvm::annotateValueSite</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/silowercontrolflow-cpp/#a4868c5d81c5ccc98c47aeab6244346a0">assert</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a845e08be4b0320d66901a66b0c0e9509">llvm::Count</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#aa20539e89704d20b98b97e9c3feac934">llvm::Data</a>, <a href="/web-llvm/docs/api/classes/llvm/smallvectorimpl/#a396fcfee6914c76974b73c3d203da6a5">llvm::SmallVectorImpl&lt; T &gt;::emplace_back</a>, <a href="/web-llvm/docs/api/classes/llvm/ilist-detail/node-parent-access/#a7e19e7508415378ad9523e0339b23e22">llvm::ilist_detail::node_parent_access&lt; NodeTy, ParentTy &gt;::getParent</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a8f6ad5c1831928ee2c6c5058d9580edf">llvm::getValueProfDataFromInst</a>, <a href="/web-llvm/docs/api/files/lib/lib/analysis/indirectcallpromotionanalysis-cpp/#a8d1c61a222911b42ad7dc30bc6519d81">MaxNumPromotions</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#aee20e86d3817849199a21d19bcc273c5">llvm::NOMORE_ICP_MAGICNUM</a>, <a href="/web-llvm/docs/api/classes/llvm/smallvectortemplatecommon/#a1c479a8c434377c2b8cb056bdfdfc201">llvm::SmallVectorTemplateCommon&lt; T, typename &gt;::size</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a74cdbd1e4f731e7d7cd83461b8b1de0b">llvm::sort</a> and <a href="/web-llvm/docs/api/classes/llvm/densemapbase/#a1a245b31aced1374f28f45d2b297f402">llvm::DenseMapBase&lt; DerivedT, KeyT, ValueT, KeyInfoT, BucketT &gt;::try_emplace</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/classes/anonymous-sampleprofile-cpp-/sampleprofileloader/#acf512f516130aaabdd835c48140c9e5c">anonymous{SampleProfile.cpp}::SampleProfileLoader::generateMDProfMetadata</a> and <a href="/web-llvm/docs/api/classes/anonymous-sampleprofile-cpp-/sampleprofileloader/#ad5c772a0b61cb29106af3a4f9ae43d59">anonymous{SampleProfile.cpp}::SampleProfileLoader::tryPromoteAndInlineCandidate</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Variables

### AllowRecursiveInline {#af5f668624e8264858b5efb9127b3be47}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">cl::opt&lt; bool &gt; AllowRecursiveInline("sample-profile-recursive-inline", cl::Hidden, cl::desc("Allow sample loader inliner to inline recursive calls."))</td>
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



<p>Definition at line 266 of file <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/ipo/sampleprofile-cpp">SampleProfile.cpp</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/classes/anonymous-sampleprofile-cpp-/sampleprofileloader/#a7e1da8085095c6d808713b280edb143b">anonymous{SampleProfile.cpp}::SampleProfileLoader::doInitialization</a> and <a href="/web-llvm/docs/api/classes/anonymous-sampleprofile-cpp-/sampleprofileloader/#a518b0cf18edfb9fb05aaa530550af870">anonymous{SampleProfile.cpp}::SampleProfileLoader::shouldInlineCandidate</a>.</p>

</div>
</div>

### AnnotateSampleProfileInlinePhase {#a6249b41b02fca2bc7c121511ad72062b}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">cl::opt&lt; bool &gt; AnnotateSampleProfileInlinePhase("annotate-sample-profile-inline-phase", cl::Hidden, cl::init(false), cl::desc("Annotate LTO phase (prelink / postlink), or main (no LTO) for " "sample-profile inline pass name."))</td>
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



<p>Definition at line 334 of file <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/ipo/sampleprofile-cpp">SampleProfile.cpp</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/classes/anonymous-sampleprofile-cpp-/sampleprofileloader/#a5133b642b31dcbfad681874ba97d5914">anonymous{SampleProfile.cpp}::SampleProfileLoader::SampleProfileLoader</a>.</p>

</div>
</div>

### CallsitePrioritizedInline {#a9eaaeedd35128b9508715b2c16dd58f5}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">cl::opt&lt; bool &gt; CallsitePrioritizedInline("sample-profile-prioritized-inline", cl::Hidden, cl::desc("Use call site prioritized inlining for sample profile loader. " "Currently only CSSPGO is supported."))</td>
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



<p>Definition at line 257 of file <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/ipo/sampleprofile-cpp">SampleProfile.cpp</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/classes/anonymous-sampleprofile-cpp-/sampleprofileloader/#a7e1da8085095c6d808713b280edb143b">anonymous{SampleProfile.cpp}::SampleProfileLoader::doInitialization</a>, <a href="/web-llvm/docs/api/classes/anonymous-sampleprofile-cpp-/sampleprofileloader/#a6f70814abe4749ddb1e8356c3584b2ac">anonymous{SampleProfile.cpp}::SampleProfileLoader::emitAnnotations</a> and <a href="/web-llvm/docs/api/classes/anonymous-sampleprofile-cpp-/sampleprofileloader/#a518b0cf18edfb9fb05aaa530550af870">anonymous{SampleProfile.cpp}::SampleProfileLoader::shouldInlineCandidate</a>.</p>

</div>
</div>

### DisableSampleLoaderInlining {#a3ea40d9c4ddb417257d8c7c5f8bfe981}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">cl::opt&lt; bool &gt; DisableSampleLoaderInlining("disable-sample-loader-inlining", cl::Hidden, cl::init(false), cl::desc( "If true, artificially skip inline transformation in sample-loader " "pass, and merge (or scale) profiles (as configured by " "--sample-profile-merge-inlinee)."))</td>
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



<p>Definition at line 194 of file <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/ipo/sampleprofile-cpp">SampleProfile.cpp</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/classes/anonymous-sampleprofile-cpp-/sampleprofileloader/#a7e1da8085095c6d808713b280edb143b">anonymous{SampleProfile.cpp}::SampleProfileLoader::doInitialization</a>.</p>

</div>
</div>

### HotFuncCutoffForStalenessError {#af9dc2d6d5404e7d42198490fa3be4e73}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">cl::opt&lt; unsigned &gt; HotFuncCutoffForStalenessError("hot-func-cutoff-for-staleness-error", cl::Hidden, cl::init(800000), cl::desc("A function is considered hot for staleness error check if its " "total sample count is above the specified percentile"))</td>
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



<p>Definition at line 242 of file <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/ipo/sampleprofile-cpp">SampleProfile.cpp</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/classes/anonymous-sampleprofile-cpp-/sampleprofileloader/#abf1045cfa542c9bf01c10bcf99262a2c">anonymous{SampleProfile.cpp}::SampleProfileLoader::rejectHighStalenessProfile</a>.</p>

</div>
</div>

### MaxNumPromotions {#a46f9ffda019c1ffa7dd85cf1a22435a3}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">cl::opt&lt; unsigned &gt; MaxNumPromotions("sample-profile-icp-max-prom", cl::init(3), cl::Hidden, cl::desc("Max number of promotions for a single indirect " "call callsite in sample profile loader"))</td>
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



<p>Definition at line 326 of file <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/ipo/sampleprofile-cpp">SampleProfile.cpp</a>.</p>

</div>
</div>

### MinfuncsForStalenessError {#a0839b336a4cfa394f0a6df99af24c122}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">cl::opt&lt; unsigned &gt; MinfuncsForStalenessError("min-functions-for-staleness-error", cl::Hidden, cl::init(50), cl::desc("Skip the check if the number of hot functions is smaller than " "the specified number."))</td>
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



<p>Definition at line 247 of file <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/ipo/sampleprofile-cpp">SampleProfile.cpp</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/classes/anonymous-sampleprofile-cpp-/sampleprofileloader/#abf1045cfa542c9bf01c10bcf99262a2c">anonymous{SampleProfile.cpp}::SampleProfileLoader::rejectHighStalenessProfile</a>.</p>

</div>
</div>

### OverwriteExistingWeights {#a4880524206cd6bd2551dda5c915be189}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">cl::opt&lt; bool &gt; OverwriteExistingWeights("overwrite-existing-weights", cl::Hidden, cl::init(false), cl::desc("Ignore existing branch weights on IR and always overwrite."))</td>
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



<p>Definition at line 330 of file <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/ipo/sampleprofile-cpp">SampleProfile.cpp</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/classes/anonymous-sampleprofile-cpp-/sampleprofileloader/#acf512f516130aaabdd835c48140c9e5c">anonymous{SampleProfile.cpp}::SampleProfileLoader::generateMDProfMetadata</a>.</p>

</div>
</div>

### PersistProfileStaleness {#a997d20da5b25193880115dc8a0b5e4ee}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">cl::opt&lt; bool &gt; PersistProfileStaleness("persist-profile-staleness", cl::Hidden, cl::init(false), cl::desc("Compute stale profile statistical metrics and write it into the " "native object file(.llvm_stats section)."))</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 145 of file <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/ipo/sampleprofile-cpp">SampleProfile.cpp</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/classes/anonymous-sampleprofile-cpp-/sampleprofileloader/#a7e1da8085095c6d808713b280edb143b">anonymous{SampleProfile.cpp}::SampleProfileLoader::doInitialization</a> and <a href="/web-llvm/docs/api/classes/anonymous-sampleprofile-cpp-/sampleprofileloader/#a25da45ec2b5b7dacb22e831cb7aef0c5">anonymous{SampleProfile.cpp}::SampleProfileLoader::runOnModule</a>.</p>

</div>
</div>

### PrecentMismatchForStalenessError {#a31561104790d3759baa688de077367ce}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">cl::opt&lt; unsigned &gt; PrecentMismatchForStalenessError("precent-mismatch-for-staleness-error", cl::Hidden, cl::init(80), cl::desc("Reject the profile if the mismatch percent is higher than the " "given number."))</td>
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



<p>Definition at line 252 of file <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/ipo/sampleprofile-cpp">SampleProfile.cpp</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/classes/anonymous-sampleprofile-cpp-/sampleprofileloader/#abf1045cfa542c9bf01c10bcf99262a2c">anonymous{SampleProfile.cpp}::SampleProfileLoader::rejectHighStalenessProfile</a>.</p>

</div>
</div>

### ProfileAccurateForSymsInList {#a88e2b32b6c2ab29b0b4470f5a1a32364}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">cl::opt&lt; bool &gt; ProfileAccurateForSymsInList("profile-accurate-for-symsinlist", cl::Hidden, cl::init(true), cl::desc("For symbols in profile symbol list, regard their profiles to " "be accurate. It may be overridden by profile-sample-accurate. "))</td>
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



<p>Definition at line 162 of file <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/ipo/sampleprofile-cpp">SampleProfile.cpp</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/classes/anonymous-sampleprofile-cpp-/sampleprofileloader/#a7e1da8085095c6d808713b280edb143b">anonymous{SampleProfile.cpp}::SampleProfileLoader::doInitialization</a> and <a href="/web-llvm/docs/api/classes/anonymous-sampleprofile-cpp-/sampleprofileloader/#a358b28b8ab641a2a22ed8849a2dff2cf">anonymous{SampleProfile.cpp}::SampleProfileLoader::runOnFunction</a>.</p>

</div>
</div>

### ProfileICPRelativeHotness {#abe3f89debe4f7888460625789de78083}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">cl::opt&lt; unsigned &gt; ProfileICPRelativeHotness("sample-profile-icp-relative-hotness", cl::Hidden, cl::init(25), cl::desc( "Relative hotness percentage threshold for indirect " "call promotion in proirity-based sample profile loader inlining."))</td>
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



<p>Definition at line 231 of file <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/ipo/sampleprofile-cpp">SampleProfile.cpp</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/classes/anonymous-sampleprofile-cpp-/sampleprofileloader/#ae0bf03df2431c543590180658ce4709d">anonymous{SampleProfile.cpp}::SampleProfileLoader::inlineHotFunctionsWithPriority</a>.</p>

</div>
</div>

### ProfileICPRelativeHotnessSkip {#ac689c456b39941e3af203d3e1750b8b5}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">cl::opt&lt; unsigned &gt; ProfileICPRelativeHotnessSkip("sample-profile-icp-relative-hotness-skip", cl::Hidden, cl::init(1), cl::desc( "Skip relative hotness check for ICP up to given number of targets."))</td>
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



<p>Definition at line 237 of file <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/ipo/sampleprofile-cpp">SampleProfile.cpp</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/classes/anonymous-sampleprofile-cpp-/sampleprofileloader/#ae0bf03df2431c543590180658ce4709d">anonymous{SampleProfile.cpp}::SampleProfileLoader::inlineHotFunctionsWithPriority</a>.</p>

</div>
</div>

### ProfileInlineReplayFallback {#a477f441a65d57a1d0bff97e993e0f5d3}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">cl::opt&lt; ReplayInlinerSettings::Fallback &gt; ProfileInlineReplayFallback("sample-profile-inline-replay-fallback", cl::init(ReplayInlinerSettings::Fallback::Original), cl::values( clEnumValN( ReplayInlinerSettings::Fallback::Original, "Original", "All decisions not in replay send to original advisor (default)"), clEnumValN(ReplayInlinerSettings::Fallback::AlwaysInline, "AlwaysInline", "All decisions not in replay are inlined"), clEnumValN(ReplayInlinerSettings::Fallback::NeverInline, "NeverInline", "All decisions not in replay are not inlined")), cl::desc("How sample profile inline replay treats sites that don't come " "from the replay. Original: defers to original advisor, " "AlwaysInline: inline all sites not in replay, NeverInline: " "inline no sites not in replay"), cl::Hidden)</td>
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



<p>Definition at line 294 of file <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/ipo/sampleprofile-cpp">SampleProfile.cpp</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/classes/anonymous-sampleprofile-cpp-/sampleprofileloader/#a7e1da8085095c6d808713b280edb143b">anonymous{SampleProfile.cpp}::SampleProfileLoader::doInitialization</a>.</p>

</div>
</div>

### ProfileInlineReplayFile {#a732d61bd469914910adee6ed8c8c4a38}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">cl::opt&lt; std::string &gt; ProfileInlineReplayFile("sample-profile-inline-replay", cl::init(""), cl::value_desc("filename"), cl::desc( "Optimization remarks file containing inline remarks to be replayed " "by inlining from sample profile loader."), cl::Hidden)</td>
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



<p>Definition at line 274 of file <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/ipo/sampleprofile-cpp">SampleProfile.cpp</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/classes/anonymous-sampleprofile-cpp-/sampleprofileloader/#a7e1da8085095c6d808713b280edb143b">anonymous{SampleProfile.cpp}::SampleProfileLoader::doInitialization</a>.</p>

</div>
</div>

### ProfileInlineReplayFormat {#af61ae5b7d50b9b36cc3a2350ded45f82}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">cl::opt&lt; CallSiteFormat::Format &gt; ProfileInlineReplayFormat("sample-profile-inline-replay-format", cl::init(CallSiteFormat::Format::LineColumnDiscriminator), cl::values( clEnumValN(CallSiteFormat::Format::Line, "Line", "&lt;Line Number&gt;"), clEnumValN(CallSiteFormat::Format::LineColumn, "LineColumn", "&lt;Line Number&gt;:&lt;Column Number&gt;"), clEnumValN(CallSiteFormat::Format::LineDiscriminator, "LineDiscriminator", "&lt;Line Number&gt;.&lt;Discriminator&gt;"), clEnumValN(CallSiteFormat::Format::LineColumnDiscriminator, "LineColumnDiscriminator", "&lt;Line Number&gt;:&lt;Column Number&gt;.&lt;Discriminator&gt; (default)")), cl::desc("How sample profile inline replay file is formatted"), cl::Hidden)</td>
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



<p>Definition at line 311 of file <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/ipo/sampleprofile-cpp">SampleProfile.cpp</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/classes/anonymous-sampleprofile-cpp-/sampleprofileloader/#a7e1da8085095c6d808713b280edb143b">anonymous{SampleProfile.cpp}::SampleProfileLoader::doInitialization</a>.</p>

</div>
</div>

### ProfileInlineReplayScope {#ab75eb24423b8e8d730f81eec23e93f43}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">cl::opt&lt; ReplayInlinerSettings::Scope &gt; ProfileInlineReplayScope("sample-profile-inline-replay-scope", cl::init(ReplayInlinerSettings::Scope::Function), cl::values(clEnumValN(ReplayInlinerSettings::Scope::Function, "Function", "Replay on functions that have remarks associated " "with them (default)"), clEnumValN(ReplayInlinerSettings::Scope::Module, "Module", "Replay on the entire module")), cl::desc("Whether inline replay should be applied to the entire " "Module or just the Functions (default) that are present as " "callers in remarks during sample profile inlining."), cl::Hidden)</td>
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



<p>Definition at line 281 of file <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/ipo/sampleprofile-cpp">SampleProfile.cpp</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/classes/anonymous-sampleprofile-cpp-/sampleprofileloader/#a7e1da8085095c6d808713b280edb143b">anonymous{SampleProfile.cpp}::SampleProfileLoader::doInitialization</a>.</p>

</div>
</div>

### ProfileMergeInlinee {#a8b16dbb3ebefd05908afe3a7874d6353}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">cl::opt&lt; bool &gt; ProfileMergeInlinee("sample-profile-merge-inlinee", cl::Hidden, cl::init(true), cl::desc("Merge past inlinee's profile to outline version if sample " "profile loader decided not to inline a call site. It will " "only be enabled when top-down order of profile loading is " "enabled. "))</td>
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



<p>Definition at line 167 of file <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/ipo/sampleprofile-cpp">SampleProfile.cpp</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/classes/anonymous-sampleprofile-cpp-/sampleprofileloader/#a0f9647d7bd1eb0c38198f05b3d34d4f3">anonymous{SampleProfile.cpp}::SampleProfileLoader::buildFunctionOrder</a> and <a href="/web-llvm/docs/api/classes/anonymous-sampleprofile-cpp-/sampleprofileloader/#a16e99ef185f55c3e45caf11c880998ff">anonymous{SampleProfile.cpp}::SampleProfileLoader::promoteMergeNotInlinedContextSamples</a>.</p>

</div>
</div>

### ProfileSampleAccurate {#af00e1c8a074b97aedd1a2db33dea6753}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">cl::opt&lt; bool &gt; ProfileSampleAccurate("profile-sample-accurate", cl::Hidden, cl::init(false), cl::desc("If the sample profile is accurate, we will mark all un-sampled " "callsite and function as having 0 samples. Otherwise, treat " "un-sampled callsites and functions conservatively as unknown. "))</td>
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



<p>Definition at line 150 of file <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/ipo/sampleprofile-cpp">SampleProfile.cpp</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/classes/anonymous-sampleprofile-cpp-/sampleprofileloader/#a7e1da8085095c6d808713b280edb143b">anonymous{SampleProfile.cpp}::SampleProfileLoader::doInitialization</a>, <a href="/web-llvm/docs/api/classes/anonymous-sampleprofile-cpp-/sampleprofileloader/#aa730b58924baf8f35394c2e5a0bb3714">anonymous{SampleProfile.cpp}::SampleProfileLoader::inlineHotFunctions</a>, <a href="/web-llvm/docs/api/classes/anonymous-sampleprofile-cpp-/sampleprofileloader/#ae0bf03df2431c543590180658ce4709d">anonymous{SampleProfile.cpp}::SampleProfileLoader::inlineHotFunctionsWithPriority</a> and <a href="/web-llvm/docs/api/classes/anonymous-sampleprofile-cpp-/sampleprofileloader/#a358b28b8ab641a2a22ed8849a2dff2cf">anonymous{SampleProfile.cpp}::SampleProfileLoader::runOnFunction</a>.</p>

</div>
</div>

### ProfileSampleBlockAccurate {#a2612d121382d9498fc6fc0acd70a0cf4}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">cl::opt&lt; bool &gt; ProfileSampleBlockAccurate("profile-sample-block-accurate", cl::Hidden, cl::init(false), cl::desc("If the sample profile is accurate, we will mark all un-sampled " "branches and calls as having 0 samples. Otherwise, treat " "them conservatively as unknown. "))</td>
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



<p>Definition at line 156 of file <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/ipo/sampleprofile-cpp">SampleProfile.cpp</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/classes/anonymous-sampleprofile-cpp-/sampleprofileloader/#acf512f516130aaabdd835c48140c9e5c">anonymous{SampleProfile.cpp}::SampleProfileLoader::generateMDProfMetadata</a>.</p>

</div>
</div>

### ProfileSizeInline {#ada8f2c564085d598909fb28464614812}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">cl::opt&lt; bool &gt; ProfileSizeInline("sample-profile-inline-size", cl::Hidden, cl::init(false), cl::desc("Inline cold call sites in profile loader if it's beneficial " "for code size."))</td>
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



<p>Definition at line 186 of file <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/ipo/sampleprofile-cpp">SampleProfile.cpp</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/classes/anonymous-sampleprofile-cpp-/sampleprofileloader/#a7e1da8085095c6d808713b280edb143b">anonymous{SampleProfile.cpp}::SampleProfileLoader::doInitialization</a>, <a href="/web-llvm/docs/api/classes/anonymous-sampleprofile-cpp-/sampleprofileloader/#a518b0cf18edfb9fb05aaa530550af870">anonymous{SampleProfile.cpp}::SampleProfileLoader::shouldInlineCandidate</a> and <a href="/web-llvm/docs/api/classes/anonymous-sampleprofile-cpp-/sampleprofileloader/#a902b6197889c703bbe3c087f8bcf0789">anonymous{SampleProfile.cpp}::SampleProfileLoader::shouldInlineColdCallee</a>.</p>

</div>
</div>

### ProfileTopDownLoad {#aeeed05c14d5103af2df4ef16b3d12674}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">cl::opt&lt; bool &gt; ProfileTopDownLoad("sample-profile-top-down-load", cl::Hidden, cl::init(true), cl::desc("Do profile annotation and inlining for functions in top-down " "order of call graph during sample profile loading. It only " "works for new pass manager. "))</td>
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



<p>Definition at line 174 of file <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/ipo/sampleprofile-cpp">SampleProfile.cpp</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/classes/anonymous-sampleprofile-cpp-/sampleprofileloader/#a0f9647d7bd1eb0c38198f05b3d34d4f3">anonymous{SampleProfile.cpp}::SampleProfileLoader::buildFunctionOrder</a>.</p>

</div>
</div>

### RemoveProbeAfterProfileAnnotation {#a43f756cf4ee4b9d99c35677a3aa852af}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">cl::opt&lt; bool &gt; RemoveProbeAfterProfileAnnotation("sample-profile-remove-probe", cl::Hidden, cl::init(false), cl::desc("Remove pseudo-probe after sample profile annotation."))</td>
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



<p>Definition at line 270 of file <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/ipo/sampleprofile-cpp">SampleProfile.cpp</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/classes/anonymous-sampleprofile-cpp-/sampleprofileloader/#a25da45ec2b5b7dacb22e831cb7aef0c5">anonymous{SampleProfile.cpp}::SampleProfileLoader::runOnModule</a>.</p>

</div>
</div>

### ReportProfileStaleness {#accaf075320be45eaba2a9cbf611368a9}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">cl::opt&lt; bool &gt; ReportProfileStaleness("report-profile-staleness", cl::Hidden, cl::init(false), cl::desc("Compute and report stale profile statistical metrics."))</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 141 of file <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/ipo/sampleprofile-cpp">SampleProfile.cpp</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/classes/anonymous-sampleprofile-cpp-/sampleprofileloader/#a7e1da8085095c6d808713b280edb143b">anonymous{SampleProfile.cpp}::SampleProfileLoader::doInitialization</a> and <a href="/web-llvm/docs/api/classes/anonymous-sampleprofile-cpp-/sampleprofileloader/#a25da45ec2b5b7dacb22e831cb7aef0c5">anonymous{SampleProfile.cpp}::SampleProfileLoader::runOnModule</a>.</p>

</div>
</div>

### SalvageStaleProfile {#addfc98fccc9f0617cf933d80dc634f2c}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">cl::opt&lt; bool &gt; SalvageStaleProfile("salvage-stale-profile", cl::Hidden, cl::init(false), cl::desc("Salvage stale profile by fuzzy matching and use the remapped " "location for sample profile query."))</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 132 of file <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/ipo/sampleprofile-cpp">SampleProfile.cpp</a>.</p>

</div>
</div>

### SalvageUnusedProfile {#a176dcdd54b914f2847535fc7c8f1f77b}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">cl::opt&lt; bool &gt; SalvageUnusedProfile("salvage-unused-profile", cl::Hidden, cl::init(false), cl::desc("Salvage unused profile by matching with new " "functions on call graph."))</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 137 of file <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/ipo/sampleprofile-cpp">SampleProfile.cpp</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/classes/anonymous-sampleprofile-cpp-/sampleprofileloader/#a25da45ec2b5b7dacb22e831cb7aef0c5">anonymous{SampleProfile.cpp}::SampleProfileLoader::runOnModule</a> and <a href="/web-llvm/docs/api/classes/llvm/sampleprofilematcher/#a5031837ecbfce3c5c2811da239ba777e">llvm::SampleProfileMatcher::runOnModule</a>.</p>

</div>
</div>

### SampleProfileFile {#a055c6b7054a94b338830b3da8ecc4023}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">cl::opt&lt; std::string &gt; SampleProfileFile("sample-profile-file", cl::init(""), cl::value_desc("filename"), cl::desc("Profile file loaded by -sample-profile"), cl::Hidden)</td>
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



<p>Definition at line 121 of file <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/ipo/sampleprofile-cpp">SampleProfile.cpp</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/classes/llvm/sampleprofileloaderpass/#a324d3696b255beea7cfd1e8b901b2363">llvm::SampleProfileLoaderPass::run</a>.</p>

</div>
</div>

### SampleProfileRemappingFile {#af8d3791537a44c00b699d28c4d978d82}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">cl::opt&lt; std::string &gt; SampleProfileRemappingFile("sample-profile-remapping-file", cl::init(""), cl::value_desc("filename"), cl::desc("Profile remapping file loaded by -sample-profile"), cl::Hidden)</td>
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



<p>Definition at line 128 of file <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/ipo/sampleprofile-cpp">SampleProfile.cpp</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/classes/llvm/sampleprofileloaderpass/#a324d3696b255beea7cfd1e8b901b2363">llvm::SampleProfileLoaderPass::run</a>.</p>

</div>
</div>

### UsePreInlinerDecision {#ad07d06e65e4610fb8ac7b13e868ec1c9}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">cl::opt&lt; bool &gt; UsePreInlinerDecision("sample-profile-use-preinliner", cl::Hidden, cl::desc("Use the preinliner decisions stored in profile context."))</td>
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



<p>Definition at line 262 of file <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/ipo/sampleprofile-cpp">SampleProfile.cpp</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/classes/anonymous-sampleprofile-cpp-/sampleprofileloader/#a7e1da8085095c6d808713b280edb143b">anonymous{SampleProfile.cpp}::SampleProfileLoader::doInitialization</a>, <a href="/web-llvm/docs/api/classes/anonymous-sampleprofile-cpp-/sampleprofileloader/#aa9137eda03e0c2cfd6eebaa55dfdd4cc">anonymous{SampleProfile.cpp}::SampleProfileLoader::findExternalInlineCandidate</a> and <a href="/web-llvm/docs/api/classes/anonymous-sampleprofile-cpp-/sampleprofileloader/#a518b0cf18edfb9fb05aaa530550af870">anonymous{SampleProfile.cpp}::SampleProfileLoader::shouldInlineCandidate</a>.</p>

</div>
</div>

### UseProfiledCallGraph {#ab5c0de16382c784463afd1d0749521b2}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">cl::opt&lt; bool &gt; UseProfiledCallGraph("use-profiled-call-graph", cl::init(true), cl::Hidden, cl::desc("Process functions in a top-down order " "defined by the profiled call graph when " "-sample-profile-top-down-load is on."))</td>
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



<p>Definition at line 181 of file <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/ipo/sampleprofile-cpp">SampleProfile.cpp</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/classes/anonymous-sampleprofile-cpp-/sampleprofileloader/#a0f9647d7bd1eb0c38198f05b3d34d4f3">anonymous{SampleProfile.cpp}::SampleProfileLoader::buildFunctionOrder</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Macro Definitions

### CSINLINE\_DEBUG {#ab4932d7673e6e1138d8a2671f16865d1}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">#define CSINLINE_DEBUG&nbsp;&nbsp;&nbsp;<a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/adt/genericcycleimpl-h/#ad78e062f62e0d6e453941fb4ca843e4d">DEBUG_TYPE</a> "-inline"</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 99 of file <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/ipo/sampleprofile-cpp">SampleProfile.cpp</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/classes/anonymous-sampleprofile-cpp-/sampleprofileloader/#a5133b642b31dcbfad681874ba97d5914">anonymous{SampleProfile.cpp}::SampleProfileLoader::SampleProfileLoader</a>.</p>

</div>
</div>

### DEBUG\_TYPE {#ad78e062f62e0d6e453941fb4ca843e4d}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">#define DEBUG_TYPE&nbsp;&nbsp;&nbsp;"sample-profile"</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 98 of file <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/ipo/sampleprofile-cpp">SampleProfile.cpp</a>.</p>

</div>
</div>

</div>

<hr/>

<p class="doxyGeneratedBy">Generated via <a href="https://github.com/xpack/doxygen2docusaurus">doxygen2docusaurus</a> by <a href="https://www.doxygen.nl">Doxygen</a> 1.15.0.</p>

</div>
