---

# DO NOT EDIT!
# Automatically generated via doxygen2docusaurus by Doxygen.

slug: /api/files/lib/lib/transforms/lib/transforms/ipo/attributor-cpp
custom_edit_url: null
toc_max_heading_level: 4
keywords:
  - doxygen
  - reference
  - file

---

<div class="doxyPage">

# The `Attributor.cpp` File Reference



## Included Headers

<div class="doxyIncludesList">#include "<a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/transforms/include/llvm/transforms/ipo/attributor-h">llvm/Transforms/IPO/Attributor.h</a>"
#include "<a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/adt/arrayref-h">llvm/ADT/ArrayRef.h</a>"
#include "<a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/adt/pointerintpair-h">llvm/ADT/PointerIntPair.h</a>"
#include "<a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/adt/stlextras-h">llvm/ADT/STLExtras.h</a>"
#include "<a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/adt/smallptrset-h">llvm/ADT/SmallPtrSet.h</a>"
#include "<a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/adt/statistic-h">llvm/ADT/Statistic.h</a>"
#include "<a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/analysis/aliasanalysis-h">llvm/Analysis/AliasAnalysis.h</a>"
#include "<a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/analysis/callgraph-h">llvm/Analysis/CallGraph.h</a>"
#include "<a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/analysis/inlinecost-h">llvm/Analysis/InlineCost.h</a>"
#include "<a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/analysis/memorybuiltins-h">llvm/Analysis/MemoryBuiltins.h</a>"
#include "<a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/analysis/mustexecute-h">llvm/Analysis/MustExecute.h</a>"
#include "<a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/ir/attributemask-h">llvm/IR/AttributeMask.h</a>"
#include "<a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/ir/attributes-h">llvm/IR/Attributes.h</a>"
#include "<a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/ir/constant-h">llvm/IR/Constant.h</a>"
#include "<a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/ir/constantfold-h">llvm/IR/ConstantFold.h</a>"
#include "<a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/ir/constants-h">llvm/IR/Constants.h</a>"
#include "<a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/ir/datalayout-h">llvm/IR/DataLayout.h</a>"
#include "<a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/ir/globalvalue-h">llvm/IR/GlobalValue.h</a>"
#include "<a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/ir/globalvariable-h">llvm/IR/GlobalVariable.h</a>"
#include "<a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/ir/instruction-h">llvm/IR/Instruction.h</a>"
#include "<a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/ir/instructions-h">llvm/IR/Instructions.h</a>"
#include "<a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/ir/intrinsicinst-h">llvm/IR/IntrinsicInst.h</a>"
#include "<a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/ir/llvmcontext-h">llvm/IR/LLVMContext.h</a>"
#include "<a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/ir/valuehandle-h">llvm/IR/ValueHandle.h</a>"
#include "<a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/support/casting-h">llvm/Support/Casting.h</a>"
#include "<a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/support/commandline-h">llvm/Support/CommandLine.h</a>"
#include "<a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/support/debug-h">llvm/Support/Debug.h</a>"
#include "<a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/support/debugcounter-h">llvm/Support/DebugCounter.h</a>"
#include "<a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/support/filesystem-h">llvm/Support/FileSystem.h</a>"
#include "<a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/support/graphwriter-h">llvm/Support/GraphWriter.h</a>"
#include "<a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/support/modref-h">llvm/Support/ModRef.h</a>"
#include "<a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/support/raw-ostream-h">llvm/Support/raw_ostream.h</a>"
#include "<a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/transforms/include/llvm/transforms/utils/basicblockutils-h">llvm/Transforms/Utils/BasicBlockUtils.h</a>"
#include "<a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/transforms/include/llvm/transforms/utils/cloning-h">llvm/Transforms/Utils/Cloning.h</a>"
#include "<a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/transforms/include/llvm/transforms/utils/local-h">llvm/Transforms/Utils/Local.h</a>"
#include &lt;cstdint&gt;
#include &lt;memory&gt;
#include &lt;cassert&gt;
#include &lt;optional&gt;
#include &lt;string&gt;
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

</table>

## Classes Index

<table class="doxyMembersIndex">

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">struct</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="/web-llvm/docs/api/structs/llvm/graphtraits-a8d72c603246819e5ff8fe2b8d743d3d">GraphTraits&lt;AADepGraphNode *&gt;</a></td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="/web-llvm/docs/api/structs/llvm/graphtraits-5ae0d92f2ba2f935f855d4f6b5815c67">GraphTraits&lt;AADepGraph *&gt;</a></td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="/web-llvm/docs/api/structs/llvm/dotgraphtraits-5ae0d92f2ba2f935f855d4f6b5815c67">DOTGraphTraits&lt;AADepGraph *&gt;</a></td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a820a30de9cd69a68b529a8508bd0c6bc">DEBUG_COUNTER</a> (ManifestDBGCounter, "attributor-manifest", "Determine what attributes are manifested in the IR")</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a01a7636f32e10e10863a196bb3924d1b">STATISTIC</a> (NumFnDeleted, "Number of function deleted")</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#aa778adddbb8911f43551a872f1cfa946">STATISTIC</a> (NumFnWithExactDefinition, "Number of functions with exact definitions")</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ab14e97acf8891b26541b86d158511137">STATISTIC</a> (NumFnWithoutExactDefinition, "Number of functions without exact definitions")</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a40b97597bbd0d5a4eddd6615200a1d4d">STATISTIC</a> (NumFnShallowWrappersCreated, "Number of shallow wrappers created")</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#af018678b819f781564539a13d039376c">STATISTIC</a> (NumAttributesTimedOut, "Number of abstract attributes timed out before fixpoint")</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#af1d7bb9a9827a512de4312992c592d59">STATISTIC</a> (NumAttributesValidFixpoint, "Number of abstract attributes in a valid fixpoint state")</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#aa4b6d17177f81f5c10b071f8c1bdf8a6">STATISTIC</a> (NumAttributesManifested, "Number of abstract attributes manifested in IR")</td>
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
<td class="doxyMemberIndexTemplate" colspan="2"><div>template &lt;bool IsLoad, typename Ty&gt;</div></td>
</tr>
<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemTypeTemplate" align="left" valign="top">static bool</td>
<td class="doxyMemberIndexItemNameTemplate" align="left" valign="top"><a href="#a605fed3c698bbafcf2d81aa2a1b191af">getPotentialCopiesOfMemoryValue</a> (Attributor &amp;A, Ty &amp;I, SmallSetVector&lt; Value *, 4 &gt; &amp;PotentialCopies, SmallSetVector&lt; Instruction *, 4 &gt; *PotentialValueOrigins, const AbstractAttribute &amp;QueryingAA, bool &amp;UsedAssumedInformation, bool OnlyExact)</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ac4e3c1743f6f71b7424a580571065530">isAssumedReadOnlyOrReadNone</a> (Attributor &amp;A, const IRPosition &amp;IRP, const AbstractAttribute &amp;QueryingAA, bool RequireReadNone, bool &amp;IsKnown)</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a365173e63bd73b3ee58033678429636e">isPotentiallyReachable</a> (Attributor &amp;A, const Instruction &amp;FromI, const Instruction *ToI, const Function &amp;ToFn, const AbstractAttribute &amp;QueryingAA, const AA::InstExclusionSetTy *ExclusionSet, std::function&lt; bool(const Function &amp;F)&gt; GoBackwardsCB)</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a9460e7e520ab945be65ecc565f727cf5">isEqualOrWorse</a> (const Attribute &amp;New, const Attribute &amp;Old)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Return true if <span class="doxyComputerOutput">New</span> is equal or worse than <span class="doxyComputerOutput">Old</span>. <a href="#a9460e7e520ab945be65ecc565f727cf5">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">static bool</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a819df2aa3d544e7dd0d23b7504d5cbe6">addIfNotExistent</a> (LLVMContext &amp;Ctx, const Attribute &amp;Attr, AttributeSet AttrSet, bool ForceReplace, AttrBuilder &amp;AB)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Return true if the information provided by <span class="doxyComputerOutput">Attr</span> was added to the attribute set <span class="doxyComputerOutput">AttrSet</span>. <a href="#a819df2aa3d544e7dd0d23b7504d5cbe6">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">bool</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a05271f93f8132d087bbcf61ed309b394">canMarkAsVisited</a> (const User *Usr)</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ab44571c39a32f937c4340ae3b578a58e">checkForAllInstructionsImpl</a> (Attributor *A, InformationCache::OpcodeInstMapTy &amp;OpcodeInstMap, function_ref&lt; bool(Instruction &amp;)&gt; Pred, const AbstractAttribute *QueryingAA, const AAIsDead *LivenessAA, ArrayRef&lt; unsigned &gt; Opcodes, bool &amp;UsedAssumedInformation, bool CheckBBLivenessOnly=false, bool CheckPotentiallyDead=false)</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a30e276f415c0b092317585c37160f9ce">runAttributorOnFunctions</a> (InformationCache &amp;InfoCache, SetVector&lt; Function * &gt; &amp;Functions, AnalysisGetter &amp;AG, CallGraphUpdater &amp;CGUpdater, bool DeleteFns, bool IsModulePass)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>} <a href="#a30e276f415c0b092317585c37160f9ce">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">static bool</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a6c7a8371c75641e29a5259c131fd8408">runAttributorLightOnFunctions</a> (InformationCache &amp;InfoCache, SetVector&lt; Function * &gt; &amp;Functions, AnalysisGetter &amp;AG, CallGraphUpdater &amp;CGUpdater, FunctionAnalysisManager &amp;FAM, bool IsModulePass)</td>
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

## Variables Index

<table class="doxyMembersIndex">

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">static <a href="/web-llvm/docs/api/classes/llvm/cl/opt">cl::opt</a>&lt; unsigned &gt;</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ae508a1e427389fe8dc7af78bcf47722b">SetFixpointIterations</a>("attributor-max-iterations", cl::Hidden, cl::desc("Maximal number of fixpoint iterations."), cl::init(32))</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a7455e308fb6c442b5878bfed73a4a5dc">MaxSpecializationPerCB</a>("attributor-max-specializations-per-call-base", cl::Hidden, cl::desc("Maximal number of callees specialized for " "a call base"), cl::init(UINT32_MAX))</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">static <a href="/web-llvm/docs/api/classes/llvm/cl/opt">cl::opt</a>&lt; unsigned, <a href="/web-llvm/docs/api/files/lib/lib/analysis/basicaliasanalysis-cpp/#af6d5cafbdfc5313e65d990120021a3ec">true</a> &gt;</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a6cd2478e78b7c61428b22055690bccbf">MaxInitializationChainLengthX</a>("attributor-max-initialization-chain-length", cl::Hidden, cl::desc("Maximal number of chained initializations (to avoid stack overflows)"), cl::location(MaxInitializationChainLength), cl::init(1024))</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ad7e545b9df9ab804eee74a77844d6392">AnnotateDeclarationCallSites</a>("attributor-annotate-decl-cs", cl::Hidden, cl::desc("Annotate call sites of function declarations."), cl::init(false))</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a1d2cc3f4c2b097da4d259a452d62d0a7">EnableHeapToStack</a>("enable-heap-to-stack-conversion", cl::init(true), cl::Hidden)</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a00425b450f84fcb086524ce93092057b">AllowShallowWrappers</a>("attributor-allow-shallow-wrappers", cl::Hidden, cl::desc("Allow the Attributor to create shallow " "wrappers for non-exact definitions."), cl::init(false))</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a98dfc5810f1fa947aee48d697f77a607">AllowDeepWrapper</a>("attributor-allow-deep-wrappers", cl::Hidden, cl::desc("Allow the Attributor to use IP information " "derived from non-exact functions via cloning"), cl::init(false))</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">static <a href="/web-llvm/docs/api/classes/llvm/cl/list">cl::list</a>&lt; <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/demangle/itaniumdemangle-h/#ae2b0d0345572d6718e219aa76d1d54edab45cffe084dd3d20d928bee85e7b0f21">std::string</a> &gt;</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a1ed855e5e975e8b5392f25c2f0270331">SeedAllowList</a>("attributor-seed-allow-list", cl::Hidden, cl::desc("Comma separated list of attribute names that are " "allowed to be seeded."), cl::CommaSeparated)</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">static <a href="/web-llvm/docs/api/classes/llvm/cl/list">cl::list</a>&lt; <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/demangle/itaniumdemangle-h/#ae2b0d0345572d6718e219aa76d1d54edab45cffe084dd3d20d928bee85e7b0f21">std::string</a> &gt;</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ae7f60ce38b4ecdcfd1821378c76f4c97">FunctionSeedAllowList</a>("attributor-function-seed-allow-list", cl::Hidden, cl::desc("Comma separated list of function names that are " "allowed to be seeded."), cl::CommaSeparated)</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a9cf7b7d08f97479cedc2892d6da115cf">DumpDepGraph</a>("attributor-dump-dep-graph", cl::Hidden, cl::desc("Dump the dependency graph to dot files."), cl::init(false))</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ac77746890efb50a7a6d319e3395a6995">DepGraphDotFileNamePrefix</a>("attributor-depgraph-dot-filename-prefix", cl::Hidden, cl::desc("The prefix used for the CallGraph dot file names."))</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a9384fde06002e04ab10293fd247ccdac">ViewDepGraph</a>("attributor-view-dep-graph", cl::Hidden, cl::desc("View the dependency graph."), cl::init(false))</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#abd7d04d3a8a8b49b6fd16831ee9f88f8">PrintDependencies</a>("attributor-print-dep", cl::Hidden, cl::desc("Print attribute dependencies"), cl::init(false))</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#aeeeca85026cee403a0ff736143361286">EnableCallSiteSpecific</a>("attributor-enable-call-site-specific-deduction", cl::Hidden, cl::desc("Allow the Attributor to do call site specific analysis"), cl::init(false))</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#aa6443d0786bdbd56af759becd0383608">PrintCallGraph</a>("attributor-print-call-graph", cl::Hidden, cl::desc("Print Attributor's internal call graph"), cl::init(false))</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a74b5d4fab3da546e8584abe7d4ded0f0">SimplifyAllLoads</a>("attributor-simplify-all-loads", cl::Hidden, cl::desc("Try to simplify all loads."), cl::init(true))</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#af432b045bbd6cf91a3fc9893c7b632e1">CloseWorldAssumption</a>("attributor-assume-closed-world", cl::Hidden, cl::desc("Should a closed world be assumed, or not. Default if not set."))</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ad78e062f62e0d6e453941fb4ca843e4d">DEBUG_TYPE</a>&nbsp;&nbsp;&nbsp;"attributor"</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a190bcd99b8eb9f8b9794ef07026d83fa">VERBOSE_DEBUG_TYPE</a>&nbsp;&nbsp;&nbsp;<a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/adt/genericcycleimpl-h/#ad78e062f62e0d6e453941fb4ca843e4d">DEBUG_TYPE</a> "-verbose"</td>
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

### addIfNotExistent() {#a819df2aa3d544e7dd0d23b7504d5cbe6}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool addIfNotExistent (<a href="/web-llvm/docs/api/classes/llvm/llvmcontext">LLVMContext</a> &amp; Ctx, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/attribute">Attribute</a> &amp; Attr, <a href="/web-llvm/docs/api/classes/llvm/attributeset">AttributeSet</a> AttrSet, bool ForceReplace, <a href="/web-llvm/docs/api/classes/llvm/attrbuilder">AttrBuilder</a> &amp; AB)</td>
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

<p>Return true if the information provided by <span class="doxyComputerOutput">Attr</span> was added to the attribute set <span class="doxyComputerOutput">AttrSet</span>.</p>


<p>This is only the case if it was not already present in <span class="doxyComputerOutput">AttrSet</span>.</p>


<p>Definition at line 955 of file <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/ipo/attributor-cpp">Attributor.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/classes/llvm/attributeset/#ab50af3bf5ee8727df07c79065d61c204">llvm::AttributeSet::getAttribute</a>, <a href="/web-llvm/docs/api/classes/llvm/attribute/#a6fea074fd9120ff82abd8f9e0036a12a">llvm::Attribute::getKindAsEnum</a>, <a href="/web-llvm/docs/api/classes/llvm/attribute/#a3ad8f83f8d6165314fe8f173645dd458">llvm::Attribute::getKindAsString</a>, <a href="/web-llvm/docs/api/classes/llvm/attribute/#a7c68b48aeb5f2440cf65d5e8b2e16040">llvm::Attribute::getMemoryEffects</a>, <a href="/web-llvm/docs/api/classes/llvm/attributeset/#a481ff076fc621dd7d69f160632b8f7df">llvm::AttributeSet::getMemoryEffects</a>, <a href="/web-llvm/docs/api/classes/llvm/attribute/#a968930aea9d9efa8d46dd890fce75643">llvm::Attribute::getValueAsString</a>, <a href="/web-llvm/docs/api/classes/llvm/attributeset/#a51fc96070af1597981c3000171e1a5ab">llvm::AttributeSet::hasAttribute</a>, <a href="/web-llvm/docs/api/classes/llvm/attribute/#a0f4d4e6a852d283cafe0b0413cfb6430">llvm::Attribute::isEnumAttribute</a>, <a href="#a9460e7e520ab945be65ecc565f727cf5">isEqualOrWorse</a>, <a href="/web-llvm/docs/api/classes/llvm/attribute/#a142250c7b671591390912db907532036">llvm::Attribute::isIntAttribute</a>, <a href="/web-llvm/docs/api/classes/llvm/attribute/#a0571df3e57128211e09cba4544aa9ca7">llvm::Attribute::isStringAttribute</a> and <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/support/errorhandling-h/#ace243f5c25697a1107cce46626b3dc94">llvm_unreachable</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/structs/llvm/attributor/#abc4265ad1d2a8b43fcf0e44d4b4f6274">llvm::Attributor::manifestAttrs</a>.</p>

</div>
</div>

### canMarkAsVisited() {#a05271f93f8132d087bbcf61ed309b394}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool canMarkAsVisited (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/user">User</a> * Usr)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 1751 of file <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/ipo/attributor-cpp">Attributor.cpp</a>.</p>


<p>Reference <a href="/web-llvm/docs/api/namespaces/llvm/#a92ca992e52dddc420f4b069cae06dfbe">llvm::isa</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/structs/llvm/attributor/#abbea65eed8b9b7cd07f0b8eef53df6f5">llvm::Attributor::checkForAllUses</a>.</p>

</div>
</div>

### checkForAllInstructionsImpl() {#ab44571c39a32f937c4340ae3b578a58e}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool checkForAllInstructionsImpl (<a href="/web-llvm/docs/api/structs/llvm/attributor">Attributor</a> * A, <a href="/web-llvm/docs/api/structs/llvm/informationcache/#acdbaebbb9ad6354d5d85d0d6480c9fde">InformationCache::OpcodeInstMapTy</a> &amp; OpcodeInstMap, <a href="/web-llvm/docs/api/classes/llvm/function-ref">function_ref</a>&lt; bool(<a href="/web-llvm/docs/api/classes/llvm/instruction">Instruction</a> &amp;)&gt; Pred, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/structs/llvm/abstractattribute">AbstractAttribute</a> * QueryingAA, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/structs/llvm/aaisdead">AAIsDead</a> * LivenessAA, <a href="/web-llvm/docs/api/classes/llvm/arrayref">ArrayRef</a>&lt; unsigned &gt; Opcodes, bool &amp; UsedAssumedInformation, bool CheckBBLivenessOnly=false, bool CheckPotentiallyDead=false)</td>
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



<p>Definition at line 2009 of file <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/ipo/attributor-cpp">Attributor.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/files/lib/lib/ir/builtingcs-cpp/#a2e38c85003a042421cde1647632d0b72">A</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a7c46c742c31be54870e2038048e6b391">llvm::dbgs</a>, <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/support/debug-h/#a3fcdc9f30e5e8b9ea4da99868a8ae4a9">DEBUG_WITH_TYPE</a>, <a href="/web-llvm/docs/api/files/lib/lib/support/md5-cpp/#ac0eafdc9ee161b71e7af98af736952fd">I</a>, <a href="/web-llvm/docs/api/structs/llvm/irposition/#a4a67bf6ab49ae2630d14e3159ef51cf4">llvm::IRPosition::inst</a>, <a href="/web-llvm/docs/api/classes/llvm/densemapbase/#a0b2ca98dc28c61793ff5c90d23e5f14e">llvm::DenseMapBase&lt; DerivedT, KeyT, ValueT, KeyInfoT, BucketT &gt;::lookup</a> and <a href="#a190bcd99b8eb9f8b9794ef07026d83fa">VERBOSE_DEBUG_TYPE</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/structs/llvm/attributor/#a440c7b43772713f767d18f81c9caadf2">llvm::Attributor::checkForAllInstructions</a>, <a href="/web-llvm/docs/api/structs/llvm/attributor/#adab9b2e1a33cfbe6f0fa6443046dcaf8">llvm::Attributor::identifyDefaultAbstractAttributes</a> and <a href="/web-llvm/docs/api/structs/llvm/attributor/#a273e9b97fc0dfec8df7cf4294d9b87fe">llvm::Attributor::isValidFunctionSignatureRewrite</a>.</p>

</div>
</div>

### DEBUG\_COUNTER() {#a820a30de9cd69a68b529a8508bd0c6bc}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">DEBUG_COUNTER (ManifestDBGCounter, "attributor-manifest", "Determine what attributes are manifested in the IR")</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 68 of file <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/ipo/attributor-cpp">Attributor.cpp</a>.</p>

</div>
</div>

### getPotentialCopiesOfMemoryValue() {#a605fed3c698bbafcf2d81aa2a1b191af}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<div class="doxyMemberTemplate">template &lt;bool IsLoad, typename Ty&gt;</div>
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool getPotentialCopiesOfMemoryValue (<a href="/web-llvm/docs/api/structs/llvm/attributor">Attributor</a> &amp; A, Ty &amp; I, <a href="/web-llvm/docs/api/classes/llvm/smallsetvector">SmallSetVector</a>&lt; <a href="/web-llvm/docs/api/classes/llvm/value">Value</a> *, 4 &gt; &amp; PotentialCopies, <a href="/web-llvm/docs/api/classes/llvm/smallsetvector">SmallSetVector</a>&lt; <a href="/web-llvm/docs/api/classes/llvm/instruction">Instruction</a> *, 4 &gt; * PotentialValueOrigins, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/structs/llvm/abstractattribute">AbstractAttribute</a> &amp; QueryingAA, bool &amp; UsedAssumedInformation, bool OnlyExact)</td>
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



<p>Definition at line 364 of file <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/ipo/attributor-cpp">Attributor.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/files/lib/lib/ir/builtingcs-cpp/#a2e38c85003a042421cde1647632d0b72">A</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/silowercontrolflow-cpp/#a4868c5d81c5ccc98c47aeab6244346a0">assert</a>, <a href="/web-llvm/docs/api/classes/llvm/setvector/#ad0bf95396cec46a41371341460d14a1c">llvm::SetVector&lt; T, Vector, Set, N &gt;::begin</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#ac4fc845f5ed92de63cd4474f128f5fc5">llvm::cast</a>, <a href="/web-llvm/docs/api/classes/llvm/setvector/#abb03e3b6c4fd937936a13afe4f60d291">llvm::SetVector&lt; T, Vector, Set, N &gt;::count</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a7c46c742c31be54870e2038048e6b391">llvm::dbgs</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/arm/armslshardening-cpp/#ad467c4ab9119043f9b7750ab986be61a">DL</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a22eeee01734061ac1b31ccd994c49eef">llvm::dyn_cast</a>, <a href="/web-llvm/docs/api/classes/llvm/setvector/#a889cc0df630d4b01e12d359517e26670">llvm::SetVector&lt; T, Vector, Set, N &gt;::end</a>, <a href="/web-llvm/docs/api/structs/llvm/aapointerinfo/access/#a5d15343639f36496bb20ec1d96b96c2c">llvm::AAPointerInfo::Access::getContent</a>, <a href="/web-llvm/docs/api/namespaces/llvm/aa/#abdc024165477822f664fda55551f8a66">llvm::AA::getInitialValueForObj</a>, <a href="/web-llvm/docs/api/structs/llvm/aapointerinfo/access/#ae6aa86dd515ac8bbc7071107bc171ffa">llvm::AAPointerInfo::Access::getRemoteInst</a>, <a href="/web-llvm/docs/api/namespaces/llvm/aa/#af967a81762eaaf67f292abee4a00180c">llvm::AA::getWithType</a>, <a href="/web-llvm/docs/api/structs/llvm/aapointerinfo/access/#a9965f099cf7df854178212cf5bd4462d">llvm::AAPointerInfo::Access::getWrittenValue</a>, <a href="/web-llvm/docs/api/files/lib/lib/support/md5-cpp/#ac0eafdc9ee161b71e7af98af736952fd">I</a>, <a href="/web-llvm/docs/api/classes/llvm/setvector/#af34eb71cc483e84d2eca80575cb9ccde">llvm::SetVector&lt; T, Vector, Set, N &gt;::insert</a>, <a href="/web-llvm/docs/api/namespaces/llvm/aa/#ac85851126814105f4a92b699293e4141ab563ef74be13fcdcf264798ed6af5666">llvm::AA::Interprocedural</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a92ca992e52dddc420f4b069cae06dfbe">llvm::isa</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a4956305191cdba7f9995569d011a5ab7">llvm::isa_and_nonnull</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#accaca14b419cbac91ca6170523084a04">llvm::isAllocationFn</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a433468826ef20b5ddb53704fc38363fc">llvm::isNoAliasCall</a>, <a href="/web-llvm/docs/api/structs/llvm/aapointerinfo/access/#a98ea1d651bed48c5b634d128476a4d9b">llvm::AAPointerInfo::Access::isRead</a>, <a href="/web-llvm/docs/api/structs/llvm/aapointerinfo/access/#a9718c2b67dd987b9cf987a7f18321a06">llvm::AAPointerInfo::Access::isWriteOrAssumption</a>, <a href="/web-llvm/docs/api/structs/llvm/aapointerinfo/access/#a04d1c8b495725833be009b9154b66895">llvm::AAPointerInfo::Access::isWrittenValueUnknown</a>, <a href="/web-llvm/docs/api/structs/llvm/aapointerinfo/access/#afe4d359249a556bf78eb97dd96055e6a">llvm::AAPointerInfo::Access::isWrittenValueYetUndetermined</a>, <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/support/debug-h/#a196897517069dda1bdb549e24468f7d7">LLVM_DEBUG</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#adadcb655edca867f08f7ea6068a7d8a1ab50339a10e1de285ac99d4c3990b8693">llvm::NONE</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a7b03ed78a8e299bde6d26a8793cd4e06">llvm::NullPointerIsDefined</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#adadcb655edca867f08f7ea6068a7d8a1a7951811e4b085cf68ed3dc3191f36405">llvm::OPTIONAL</a>, <a href="/web-llvm/docs/api/files/lib/lib/analysis/targetlibraryinfo-cpp/#aca185e6d0e9f423dbb24440206454872a11dbf501abf829b3ab7049c2d3a8a053">Ptr</a>, <a href="/web-llvm/docs/api/classes/llvm/smallvectortemplatebase/#af42bfbc067df27c19ee2fc859df58799">llvm::SmallVectorTemplateBase&lt; T, bool &gt;::push_back</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/nvptx/nvvmintrrange-cpp/#a34bd74317e3f04bfc4318c2d1a470877">Range</a> and <a href="/web-llvm/docs/api/structs/llvm/irposition/#a3bee165465962ee97307066da4f0fb13">llvm::IRPosition::value</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/namespaces/llvm/aa/#a5901858977a1ad4f47eb76f8491fadd8">llvm::AA::getPotentialCopiesOfStoredValue</a> and <a href="/web-llvm/docs/api/namespaces/llvm/aa/#af30179a08c576d56d2469f5373174c43">llvm::AA::getPotentiallyLoadedValues</a>.</p>

</div>
</div>

### isAssumedReadOnlyOrReadNone() {#ac4e3c1743f6f71b7424a580571065530}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool isAssumedReadOnlyOrReadNone (<a href="/web-llvm/docs/api/structs/llvm/attributor">Attributor</a> &amp; A, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/structs/llvm/irposition">IRPosition</a> &amp; IRP, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/structs/llvm/abstractattribute">AbstractAttribute</a> &amp; QueryingAA, bool RequireReadNone, bool &amp; IsKnown)</td>
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



<p>Definition at line 608 of file <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/ipo/attributor-cpp">Attributor.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/files/lib/lib/ir/builtingcs-cpp/#a2e38c85003a042421cde1647632d0b72">A</a>, <a href="/web-llvm/docs/api/structs/llvm/irposition/#aea16db681aa18f4eded0015e284fdfe5">llvm::IRPosition::getPositionKind</a>, <a href="/web-llvm/docs/api/namespaces/llvm/aa/#ae8abeaeed2f11072b2d064fe70510e9f">llvm::AA::hasAssumedIRAttr</a>, <a href="/web-llvm/docs/api/structs/llvm/irposition/#a53f576f97e0dfa8314afb16bd74a76d0a4b033e6b489e8f06fe2819955eb8011b">llvm::IRPosition::IRP_CALL_SITE</a>, <a href="/web-llvm/docs/api/structs/llvm/irposition/#a53f576f97e0dfa8314afb16bd74a76d0aa823f70d88660d88196943a3f09301da">llvm::IRPosition::IRP_FUNCTION</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#adadcb655edca867f08f7ea6068a7d8a1ab50339a10e1de285ac99d4c3990b8693">llvm::NONE</a> and <a href="/web-llvm/docs/api/namespaces/llvm/#adadcb655edca867f08f7ea6068a7d8a1a7951811e4b085cf68ed3dc3191f36405">llvm::OPTIONAL</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/namespaces/llvm/aa/#a1496d1d7b408ea24a3c4d3c6d9a2d08c">llvm::AA::isAssumedReadNone</a> and <a href="/web-llvm/docs/api/namespaces/llvm/aa/#a17d95a36815f9b2bb3441fd61ee328be">llvm::AA::isAssumedReadOnly</a>.</p>

</div>
</div>

### isEqualOrWorse() {#a9460e7e520ab945be65ecc565f727cf5}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool isEqualOrWorse (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/attribute">Attribute</a> &amp; New, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/attribute">Attribute</a> &amp; Old)</td>
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

<p>Return true if <span class="doxyComputerOutput">New</span> is equal or worse than <span class="doxyComputerOutput">Old</span>.</p>

<p>Definition at line 945 of file <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/ipo/attributor-cpp">Attributor.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/classes/llvm/attribute/#a1db9b109e0e28e38eb43086b679dc271">llvm::Attribute::getValueAsInt</a> and <a href="/web-llvm/docs/api/classes/llvm/attribute/#a142250c7b671591390912db907532036">llvm::Attribute::isIntAttribute</a>.</p>


<p>Referenced by <a href="#a819df2aa3d544e7dd0d23b7504d5cbe6">addIfNotExistent</a>.</p>

</div>
</div>

### isPotentiallyReachable() {#a365173e63bd73b3ee58033678429636e}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool isPotentiallyReachable (<a href="/web-llvm/docs/api/structs/llvm/attributor">Attributor</a> &amp; A, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/instruction">Instruction</a> &amp; FromI, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/instruction">Instruction</a> * ToI, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/function">Function</a> &amp; ToFn, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/structs/llvm/abstractattribute">AbstractAttribute</a> &amp; QueryingAA, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/namespaces/llvm/aa/#ab7dc88f593d600ddcfe97fcbd6f15e43">AA::InstExclusionSetTy</a> * ExclusionSet, <a href="/web-llvm/docs/api/files/lib/lib/analysis/regionprinter-cpp/#aa37fbbce2360106772fd97ed06455d55">std::function</a>&lt; bool(<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/function">Function</a> &amp;<a href="/web-llvm/docs/api/files/lib/lib/support/md5-cpp/#a96d73bbd7af15cb1fc38c3f4a3bd82e9">F</a>)&gt; GoBackwardsCB)</td>
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



<p>Definition at line 660 of file <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/ipo/attributor-cpp">Attributor.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/files/lib/lib/ir/builtingcs-cpp/#a2e38c85003a042421cde1647632d0b72">A</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a7c46c742c31be54870e2038048e6b391">llvm::dbgs</a>, <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/support/debug-h/#a3fcdc9f30e5e8b9ea4da99868a8ae4a9">DEBUG_WITH_TYPE</a>, <a href="/web-llvm/docs/api/classes/llvm/smallvectortemplatecommon/#ad9a3c7bc26b130377bbafc170b5f88a2">llvm::SmallVectorTemplateCommon&lt; T, typename &gt;::empty</a>, <a href="/web-llvm/docs/api/files/lib/lib/support/md5-cpp/#a96d73bbd7af15cb1fc38c3f4a3bd82e9">F</a>, <a href="/web-llvm/docs/api/classes/llvm/basicblock/#a4848d1a141ddc7cf0068460fba53ba37">llvm::BasicBlock::front</a>, <a href="/web-llvm/docs/api/structs/llvm/irposition/#a8936a7eb7c9151c46513b192053afb2e">llvm::IRPosition::function</a>, <a href="/web-llvm/docs/api/classes/llvm/function/#a169f0c26ef46161741fdd120a806f853">llvm::Function::getEntryBlock</a>, <a href="/web-llvm/docs/api/classes/llvm/instruction/#a6a66ebb3aa12757479a3c88de77d78f8">llvm::Instruction::getFunction</a>, <a href="/web-llvm/docs/api/classes/llvm/value/#adb5c319f5905c1d3ca9eb5df546388c5">llvm::Value::getName</a>, <a href="/web-llvm/docs/api/classes/llvm/instruction/#a91bd28adea418a08cec78b72413d9d45">llvm::Instruction::getNextNonDebugInstruction</a>, <a href="/web-llvm/docs/api/classes/llvm/smallptrsetimpl/#a9d834ae3da8c62c2b668dada51335eb0">llvm::SmallPtrSetImpl&lt; PtrType &gt;::insert</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a92ca992e52dddc420f4b069cae06dfbe">llvm::isa</a>, <a href="/web-llvm/docs/api/classes/llvm/globalvalue/#a32e606ac4c88f71f14212e42b808e7f4">llvm::GlobalValue::isDeclaration</a>, <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/support/debug-h/#a196897517069dda1bdb549e24468f7d7">LLVM_DEBUG</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#adadcb655edca867f08f7ea6068a7d8a1a7951811e4b085cf68ed3dc3191f36405">llvm::OPTIONAL</a>, <a href="/web-llvm/docs/api/classes/llvm/smallvectorimpl/#a0c8ffe664a36e30d49c84d0aded2fe08">llvm::SmallVectorImpl&lt; T &gt;::pop_back_val</a>, <a href="/web-llvm/docs/api/classes/llvm/smallvectortemplatebase/#af42bfbc067df27c19ee2fc859df58799">llvm::SmallVectorTemplateBase&lt; T, bool &gt;::push_back</a>, <a href="/web-llvm/docs/api/classes/llvm/smallptrsetimplbase/#a0e1c3175b0ac22fe3853651c28e1ecb8">llvm::SmallPtrSetImplBase::size</a>, <a href="/web-llvm/docs/api/classes/llvm/smallvectortemplatecommon/#a1c479a8c434377c2b8cb056bdfdfc201">llvm::SmallVectorTemplateCommon&lt; T, typename &gt;::size</a> and <a href="#a190bcd99b8eb9f8b9794ef07026d83fa">VERBOSE_DEBUG_TYPE</a>.</p>

</div>
</div>

### runAttributorLightOnFunctions() {#a6c7a8371c75641e29a5259c131fd8408}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool runAttributorLightOnFunctions (<a href="/web-llvm/docs/api/structs/llvm/informationcache">InformationCache</a> &amp; InfoCache, <a href="/web-llvm/docs/api/classes/llvm/setvector">SetVector</a>&lt; <a href="/web-llvm/docs/api/classes/llvm/function">Function</a> * &gt; &amp; Functions, <a href="/web-llvm/docs/api/structs/llvm/analysisgetter">AnalysisGetter</a> &amp; AG, <a href="/web-llvm/docs/api/classes/llvm/callgraphupdater">CallGraphUpdater</a> &amp; CGUpdater, <a href="/web-llvm/docs/api/namespaces/llvm/#adce09a5a0de0e3177eb00e932734af2f">FunctionAnalysisManager</a> &amp; FAM, bool IsModulePass)</td>
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



<p>Definition at line 3906 of file <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/ipo/attributor-cpp">Attributor.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/files/lib/lib/ir/builtingcs-cpp/#a2e38c85003a042421cde1647632d0b72">A</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a0d10fe510ced2849a8074fe81e5d04ce">llvm::all_of</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#acd850975ae5042cacb64a9d0ea4715f3ae6b94e58bfd13b21bc786578d9f8ba4a">llvm::CHANGED</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a7c46c742c31be54870e2038048e6b391">llvm::dbgs</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a22eeee01734061ac1b31ccd994c49eef">llvm::dyn_cast</a>, <a href="/web-llvm/docs/api/classes/llvm/setvector/#ac178f4fc4e4a0642610c374256b9fb27">llvm::SetVector&lt; T, Vector, Set, N &gt;::empty</a>, <a href="/web-llvm/docs/api/files/lib/lib/support/md5-cpp/#a96d73bbd7af15cb1fc38c3f4a3bd82e9">F</a>, <a href="/web-llvm/docs/api/files/lib/lib/passes/passbuilderbindings-cpp/#a83c7e5ca51099e4efa895791a02fb0ed">FAM</a>, <a href="/web-llvm/docs/api/classes/llvm/value/#adb5c319f5905c1d3ca9eb5df546388c5">llvm::Value::getName</a>, <a href="/web-llvm/docs/api/structs/llvm/aacalledges/#a65b8aefa6995e3dcfc33976d666b5519">llvm::AACallEdges::ID</a>, <a href="/web-llvm/docs/api/structs/llvm/aainterfnreachability/#a19232ae5fde34ad6c29d5b6504b1b4c3">llvm::AAInterFnReachability::ID</a>, <a href="/web-llvm/docs/api/structs/llvm/aaintrafnreachability/#a6f9ee7c30c14972518f9f36000ac989a">llvm::AAIntraFnReachability::ID</a>, <a href="/web-llvm/docs/api/structs/llvm/aamemorybehavior/#a5819afb332c2bf8d5e347df978c2fff5">llvm::AAMemoryBehavior::ID</a>, <a href="/web-llvm/docs/api/structs/llvm/aamemorylocation/#a57002bf60277fbf32d88bd544be41e0f">llvm::AAMemoryLocation::ID</a>, <a href="/web-llvm/docs/api/structs/llvm/aamustprogress/#aa5236aa24b3f45741cd815ea22f99a38">llvm::AAMustProgress::ID</a>, <a href="/web-llvm/docs/api/structs/llvm/aanocapture/#a8bb470ec04114d55381446066944b973">llvm::AANoCapture::ID</a>, <a href="/web-llvm/docs/api/structs/llvm/aanofpclass/#a9fb13cf84818a0f292ee27abe92e676d">llvm::AANoFPClass::ID</a>, <a href="/web-llvm/docs/api/structs/llvm/aanofree/#a47ec1ffd72c64b28ac7972ab646ea6ea">llvm::AANoFree::ID</a>, <a href="/web-llvm/docs/api/structs/llvm/aanonnull/#a59fb2ffb03c674dc2d353fcb0e3b25d0">llvm::AANonNull::ID</a>, <a href="/web-llvm/docs/api/structs/llvm/aanorecurse/#af9538009445a372373400e5b41f3f956">llvm::AANoRecurse::ID</a>, <a href="/web-llvm/docs/api/structs/llvm/aanoreturn/#a4f983c389abfbbadac5977381428805d">llvm::AANoReturn::ID</a>, <a href="/web-llvm/docs/api/structs/llvm/aanosync/#a7922e1455152216d7b6b4761f6e973c1">llvm::AANoSync::ID</a>, <a href="/web-llvm/docs/api/structs/llvm/aanounwind/#aae643fe4f801d23e5e8ecc23c3d14da8">llvm::AANoUnwind::ID</a>, <a href="/web-llvm/docs/api/structs/llvm/aaunderlyingobjects/#a637a2694991165b5b84b360a6d4aa2bd">llvm::AAUnderlyingObjects::ID</a>, <a href="/web-llvm/docs/api/structs/llvm/aawillreturn/#a7fa76312cedc99d5fd3bbefa92f3d6d2">llvm::AAWillReturn::ID</a>, <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/support/debug-h/#a196897517069dda1bdb549e24468f7d7">LLVM_DEBUG</a> and <a href="/web-llvm/docs/api/classes/llvm/setvector/#a1a42c1ba878bd637f374197d05f0a97f">llvm::SetVector&lt; T, Vector, Set, N &gt;::size</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/structs/llvm/attributorlightcgsccpass/#a1725467ef5883a44e7777d681c6a4d32">llvm::AttributorLightCGSCCPass::run</a> and <a href="/web-llvm/docs/api/structs/llvm/attributorlightpass/#af4dc3e41c843da6385d1252386d4c03e">llvm::AttributorLightPass::run</a>.</p>

</div>
</div>

### runAttributorOnFunctions() {#a30e276f415c0b092317585c37160f9ce}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool runAttributorOnFunctions (<a href="/web-llvm/docs/api/structs/llvm/informationcache">InformationCache</a> &amp; InfoCache, <a href="/web-llvm/docs/api/classes/llvm/setvector">SetVector</a>&lt; <a href="/web-llvm/docs/api/classes/llvm/function">Function</a> * &gt; &amp; Functions, <a href="/web-llvm/docs/api/structs/llvm/analysisgetter">AnalysisGetter</a> &amp; AG, <a href="/web-llvm/docs/api/classes/llvm/callgraphupdater">CallGraphUpdater</a> &amp; CGUpdater, bool DeleteFns, bool IsModulePass)</td>
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

<p>}</p>


<hr/>



### Pass (Manager) Boilerplate {#autotoc_md120}


<p>Definition at line 3803 of file <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/ipo/attributor-cpp">Attributor.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/files/lib/lib/ir/builtingcs-cpp/#a2e38c85003a042421cde1647632d0b72">A</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a0d10fe510ced2849a8074fe81e5d04ce">llvm::all_of</a>, <a href="#a98dfc5810f1fa947aee48d697f77a607">AllowDeepWrapper</a>, <a href="#a00425b450f84fcb086524ce93092057b">AllowShallowWrappers</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/silowercontrolflow-cpp/#a4868c5d81c5ccc98c47aeab6244346a0">assert</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#acd850975ae5042cacb64a9d0ea4715f3ae6b94e58bfd13b21bc786578d9f8ba4a">llvm::CHANGED</a>, <a href="/web-llvm/docs/api/structs/llvm/attributor/#a45f6cbf770c1d990014838ceb300e936">llvm::Attributor::createShallowWrapper</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a7c46c742c31be54870e2038048e6b391">llvm::dbgs</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a22eeee01734061ac1b31ccd994c49eef">llvm::dyn_cast</a>, <a href="/web-llvm/docs/api/classes/llvm/setvector/#ac178f4fc4e4a0642610c374256b9fb27">llvm::SetVector&lt; T, Vector, Set, N &gt;::empty</a>, <a href="/web-llvm/docs/api/files/lib/lib/support/md5-cpp/#a96d73bbd7af15cb1fc38c3f4a3bd82e9">F</a>, <a href="/web-llvm/docs/api/classes/llvm/value/#adb5c319f5905c1d3ca9eb5df546388c5">llvm::Value::getName</a>, <a href="/web-llvm/docs/api/classes/llvm/setvector/#af34eb71cc483e84d2eca80575cb9ccde">llvm::SetVector&lt; T, Vector, Set, N &gt;::insert</a>, <a href="/web-llvm/docs/api/structs/llvm/attributor/#a58a631dd1eec9e904e4618288bcc9442">llvm::Attributor::internalizeFunction</a>, <a href="/web-llvm/docs/api/classes/llvm/globalvalue/#aabf6932ed41fc64e17c0030c44eda44e">llvm::GlobalValue::isInterposableLinkage</a>, <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/support/debug-h/#a196897517069dda1bdb549e24468f7d7">LLVM_DEBUG</a>, <a href="#a7455e308fb6c442b5878bfed73a4a5dc">MaxSpecializationPerCB</a>, <a href="/web-llvm/docs/api/classes/llvm/callgraphupdater/#a7bf8126709349339746d58096776d4f3">llvm::CallGraphUpdater::reanalyzeFunction</a>, <a href="/web-llvm/docs/api/classes/llvm/callgraphupdater/#a3153d95e005c433416597836e80331d2">llvm::CallGraphUpdater::replaceFunctionWith</a>, <a href="/web-llvm/docs/api/classes/llvm/setvector/#a1a42c1ba878bd637f374197d05f0a97f">llvm::SetVector&lt; T, Vector, Set, N &gt;::size</a> and <a href="/web-llvm/docs/api/classes/llvm/value/#abf855b7cd63a0cd7f73759e396f280c9">llvm::Value::uses</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/structs/llvm/attributorcgsccpass/#a305cbdd90350f05f5ee772811d596ded">llvm::AttributorCGSCCPass::run</a> and <a href="/web-llvm/docs/api/structs/llvm/attributorpass/#aba65d47dce0a15a90eb4e519ffc4929c">llvm::AttributorPass::run</a>.</p>

</div>
</div>

### STATISTIC() {#a01a7636f32e10e10863a196bb3924d1b}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">STATISTIC (NumFnDeleted, "Number of <a href="/web-llvm/docs/api/files/lib/lib/analysis/regionprinter-cpp/#aa37fbbce2360106772fd97ed06455d55">function</a> deleted")</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 71 of file <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/ipo/attributor-cpp">Attributor.cpp</a>.</p>

</div>
</div>

### STATISTIC() {#aa778adddbb8911f43551a872f1cfa946}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">STATISTIC (NumFnWithExactDefinition, "Number of <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/amdgpulowermoduleldspass-cpp/#a8818b45f8c07ddce635268ec684dc61a">functions</a> with exact definitions")</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 72 of file <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/ipo/attributor-cpp">Attributor.cpp</a>.</p>

</div>
</div>

### STATISTIC() {#ab14e97acf8891b26541b86d158511137}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">STATISTIC (NumFnWithoutExactDefinition, "Number of <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/amdgpulowermoduleldspass-cpp/#a8818b45f8c07ddce635268ec684dc61a">functions</a> without exact definitions")</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 74 of file <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/ipo/attributor-cpp">Attributor.cpp</a>.</p>

</div>
</div>

### STATISTIC() {#a40b97597bbd0d5a4eddd6615200a1d4d}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">STATISTIC (NumFnShallowWrappersCreated, "Number of shallow wrappers created")</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 76 of file <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/ipo/attributor-cpp">Attributor.cpp</a>.</p>

</div>
</div>

### STATISTIC() {#af018678b819f781564539a13d039376c}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">STATISTIC (NumAttributesTimedOut, "Number of abstract attributes timed out before fixpoint")</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 77 of file <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/ipo/attributor-cpp">Attributor.cpp</a>.</p>

</div>
</div>

### STATISTIC() {#af1d7bb9a9827a512de4312992c592d59}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">STATISTIC (NumAttributesValidFixpoint, "Number of abstract attributes in a valid fixpoint state")</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 79 of file <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/ipo/attributor-cpp">Attributor.cpp</a>.</p>

</div>
</div>

### STATISTIC() {#aa4b6d17177f81f5c10b071f8c1bdf8a6}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">STATISTIC (NumAttributesManifested, "Number of abstract attributes manifested in IR")</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 81 of file <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/ipo/attributor-cpp">Attributor.cpp</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Variables

### AllowDeepWrapper {#a98dfc5810f1fa947aee48d697f77a607}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">cl::opt&lt; bool &gt; AllowDeepWrapper("attributor-allow-deep-wrappers", cl::Hidden, cl::desc("Allow the Attributor to use IP information " "derived from non-exact functions via cloning"), cl::init(false))</td>
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



<p>Definition at line 125 of file <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/ipo/attributor-cpp">Attributor.cpp</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/structs/llvm/attributor/#a58a631dd1eec9e904e4618288bcc9442">llvm::Attributor::internalizeFunction</a> and <a href="#a30e276f415c0b092317585c37160f9ce">runAttributorOnFunctions</a>.</p>

</div>
</div>

### AllowShallowWrappers {#a00425b450f84fcb086524ce93092057b}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">cl::opt&lt; bool &gt; AllowShallowWrappers("attributor-allow-shallow-wrappers", cl::Hidden, cl::desc("Allow the Attributor to create shallow " "wrappers for non-exact definitions."), cl::init(false))</td>
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



<p>Definition at line 119 of file <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/ipo/attributor-cpp">Attributor.cpp</a>.</p>


<p>Referenced by <a href="#a30e276f415c0b092317585c37160f9ce">runAttributorOnFunctions</a>.</p>

</div>
</div>

### AnnotateDeclarationCallSites {#ad7e545b9df9ab804eee74a77844d6392}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">cl::opt&lt; bool &gt; AnnotateDeclarationCallSites("attributor-annotate-decl-cs", cl::Hidden, cl::desc("Annotate call sites of function declarations."), cl::init(false))</td>
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



<p>Definition at line 111 of file <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/ipo/attributor-cpp">Attributor.cpp</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/structs/llvm/attributor/#adab9b2e1a33cfbe6f0fa6443046dcaf8">llvm::Attributor::identifyDefaultAbstractAttributes</a>.</p>

</div>
</div>

### CloseWorldAssumption {#af432b045bbd6cf91a3fc9893c7b632e1}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">cl::opt&lt; bool &gt; CloseWorldAssumption("attributor-assume-closed-world", cl::Hidden, cl::desc("Should a closed world be assumed, or not. Default if not set."))</td>
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



<p>Definition at line 177 of file <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/ipo/attributor-cpp">Attributor.cpp</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/structs/llvm/attributor/#a84e8ffa7958427b302f833f8d89ba06a">llvm::Attributor::isClosedWorldModule</a>.</p>

</div>
</div>

### DepGraphDotFileNamePrefix {#ac77746890efb50a7a6d319e3395a6995}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">cl::opt&lt; std::string &gt; DepGraphDotFileNamePrefix("attributor-depgraph-dot-filename-prefix", cl::Hidden, cl::desc("The prefix used for the CallGraph dot file names."))</td>
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



<p>Definition at line 150 of file <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/ipo/attributor-cpp">Attributor.cpp</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/structs/llvm/aadepgraph/#abd053aaf6945419c019c5f3e4e87826e">llvm::AADepGraph::dumpGraph</a>.</p>

</div>
</div>

### DumpDepGraph {#a9cf7b7d08f97479cedc2892d6da115cf}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">cl::opt&lt; bool &gt; DumpDepGraph("attributor-dump-dep-graph", cl::Hidden, cl::desc("Dump the dependency graph to dot files."), cl::init(false))</td>
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



<p>Definition at line 146 of file <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/ipo/attributor-cpp">Attributor.cpp</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/structs/llvm/attributor/#af7d3babc57be041df699846f65d231c8">llvm::Attributor::run</a>.</p>

</div>
</div>

### EnableCallSiteSpecific {#aeeeca85026cee403a0ff736143361286}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">cl::opt&lt; bool &gt; EnableCallSiteSpecific("attributor-enable-call-site-specific-deduction", cl::Hidden, cl::desc("Allow the Attributor to do call site specific analysis"), cl::init(false))</td>
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



<p>Definition at line 162 of file <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/ipo/attributor-cpp">Attributor.cpp</a>.</p>

</div>
</div>

### EnableHeapToStack {#a1d2cc3f4c2b097da4d259a452d62d0a7}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">cl::opt&lt; bool &gt; EnableHeapToStack("enable-heap-to-stack-conversion", cl::init(true), cl::Hidden)</td>
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



<p>Definition at line 115 of file <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/ipo/attributor-cpp">Attributor.cpp</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/structs/llvm/attributor/#adab9b2e1a33cfbe6f0fa6443046dcaf8">llvm::Attributor::identifyDefaultAbstractAttributes</a>.</p>

</div>
</div>

### FunctionSeedAllowList {#ae7f60ce38b4ecdcfd1821378c76f4c97}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">cl::list&lt; std::string &gt; FunctionSeedAllowList("attributor-function-seed-allow-list", cl::Hidden, cl::desc("Comma separated list of function names that are " "allowed to be seeded."), cl::CommaSeparated)</td>
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



<p>Definition at line 138 of file <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/ipo/attributor-cpp">Attributor.cpp</a>.</p>

</div>
</div>

### MaxInitializationChainLengthX {#a6cd2478e78b7c61428b22055690bccbf}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">cl::opt&lt; unsigned, true &gt; MaxInitializationChainLengthX("attributor-max-initialization-chain-length", cl::Hidden, cl::desc( "Maximal number of chained initializations (to avoid stack overflows)"), cl::location(MaxInitializationChainLength), cl::init(1024))</td>
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



<p>Definition at line 104 of file <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/ipo/attributor-cpp">Attributor.cpp</a>.</p>

</div>
</div>

### MaxSpecializationPerCB {#a7455e308fb6c442b5878bfed73a4a5dc}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">cl::opt&lt; unsigned &gt; MaxSpecializationPerCB("attributor-max-specializations-per-call-base", cl::Hidden, cl::desc("Maximal number of callees specialized for " "a call base"), cl::init(UINT32_MAX))</td>
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



<p>Definition at line 98 of file <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/ipo/attributor-cpp">Attributor.cpp</a>.</p>


<p>Referenced by <a href="#a30e276f415c0b092317585c37160f9ce">runAttributorOnFunctions</a>.</p>

</div>
</div>

### PrintCallGraph {#aa6443d0786bdbd56af759becd0383608}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">cl::opt&lt; bool &gt; PrintCallGraph("attributor-print-call-graph", cl::Hidden, cl::desc("Print Attributor's internal call graph"), cl::init(false))</td>
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



<p>Definition at line 168 of file <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/ipo/attributor-cpp">Attributor.cpp</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/structs/llvm/attributor/#af7d3babc57be041df699846f65d231c8">llvm::Attributor::run</a>.</p>

</div>
</div>

### PrintDependencies {#abd7d04d3a8a8b49b6fd16831ee9f88f8}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">cl::opt&lt; bool &gt; PrintDependencies("attributor-print-dep", cl::Hidden, cl::desc("Print attribute dependencies"), cl::init(false))</td>
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



<p>Definition at line 158 of file <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/ipo/attributor-cpp">Attributor.cpp</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/structs/llvm/attributor/#af7d3babc57be041df699846f65d231c8">llvm::Attributor::run</a>.</p>

</div>
</div>

### SeedAllowList {#a1ed855e5e975e8b5392f25c2f0270331}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">cl::list&lt; std::string &gt; SeedAllowList("attributor-seed-allow-list", cl::Hidden, cl::desc("Comma separated list of attribute names that are " "allowed to be seeded."), cl::CommaSeparated)</td>
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



<p>Definition at line 133 of file <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/ipo/attributor-cpp">Attributor.cpp</a>.</p>

</div>
</div>

### SetFixpointIterations {#ae508a1e427389fe8dc7af78bcf47722b}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">cl::opt&lt; unsigned &gt; SetFixpointIterations("attributor-max-iterations", cl::Hidden, cl::desc("Maximal number of fixpoint iterations."), cl::init(32))</td>
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



<p>Definition at line 93 of file <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/ipo/attributor-cpp">Attributor.cpp</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/classes/llvm/openmpoptcgsccpass/#a9d4366d9c2f6de53d6f2edce548577ab">llvm::OpenMPOptCGSCCPass::run</a> and <a href="/web-llvm/docs/api/classes/llvm/openmpoptpass/#ad0812a5ba88f8645505134a108f639b2">llvm::OpenMPOptPass::run</a>.</p>

</div>
</div>

### SimplifyAllLoads {#a74b5d4fab3da546e8584abe7d4ded0f0}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">cl::opt&lt; bool &gt; SimplifyAllLoads("attributor-simplify-all-loads", cl::Hidden, cl::desc("Try to simplify all loads."), cl::init(true))</td>
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



<p>Definition at line 172 of file <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/ipo/attributor-cpp">Attributor.cpp</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/structs/llvm/attributor/#adab9b2e1a33cfbe6f0fa6443046dcaf8">llvm::Attributor::identifyDefaultAbstractAttributes</a>.</p>

</div>
</div>

### ViewDepGraph {#a9384fde06002e04ab10293fd247ccdac}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">cl::opt&lt; bool &gt; ViewDepGraph("attributor-view-dep-graph", cl::Hidden, cl::desc("View the dependency graph."), cl::init(false))</td>
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



<p>Definition at line 154 of file <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/ipo/attributor-cpp">Attributor.cpp</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/structs/llvm/attributor/#af7d3babc57be041df699846f65d231c8">llvm::Attributor::run</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Macro Definitions

### DEBUG\_TYPE {#ad78e062f62e0d6e453941fb4ca843e4d}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">#define DEBUG_TYPE&nbsp;&nbsp;&nbsp;"attributor"</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 65 of file <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/ipo/attributor-cpp">Attributor.cpp</a>.</p>

</div>
</div>

### VERBOSE\_DEBUG\_TYPE {#a190bcd99b8eb9f8b9794ef07026d83fa}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">#define VERBOSE_DEBUG_TYPE&nbsp;&nbsp;&nbsp;<a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/adt/genericcycleimpl-h/#ad78e062f62e0d6e453941fb4ca843e4d">DEBUG_TYPE</a> "-verbose"</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 66 of file <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/ipo/attributor-cpp">Attributor.cpp</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/structs/llvm/attributor/#a8d0a2ebeeedeb0bd16a52affb7f6ed88">llvm::Attributor::checkForAllCallSites</a>, <a href="#ab44571c39a32f937c4340ae3b578a58e">checkForAllInstructionsImpl</a>, <a href="/web-llvm/docs/api/structs/llvm/attributor/#abbea65eed8b9b7cd07f0b8eef53df6f5">llvm::Attributor::checkForAllUses</a> and <a href="#a365173e63bd73b3ee58033678429636e">isPotentiallyReachable</a>.</p>

</div>
</div>

</div>

<hr/>

<p class="doxyGeneratedBy">Generated via <a href="https://github.com/xpack/doxygen2docusaurus">doxygen2docusaurus</a> by <a href="https://www.doxygen.nl">Doxygen</a> 1.15.0.</p>

</div>
