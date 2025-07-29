---

# DO NOT EDIT!
# Automatically generated via doxygen2docusaurus by Doxygen.

slug: /api/files/lib/lib/analysis/modulesummaryanalysis-cpp
custom_edit_url: null
toc_max_heading_level: 4
keywords:
  - doxygen
  - reference
  - file

---

<div class="doxyPage">

# `ModuleSummaryAnalysis.cpp` File



## Included Headers

<div class="doxyIncludesList">#include "<a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/analysis/modulesummaryanalysis-h">llvm/Analysis/ModuleSummaryAnalysis.h</a>"
#include "<a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/adt/arrayref-h">llvm/ADT/ArrayRef.h</a>"
#include "<a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/adt/denseset-h">llvm/ADT/DenseSet.h</a>"
#include "<a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/adt/mapvector-h">llvm/ADT/MapVector.h</a>"
#include "<a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/adt/stlextras-h">llvm/ADT/STLExtras.h</a>"
#include "<a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/adt/setvector-h">llvm/ADT/SetVector.h</a>"
#include "<a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/adt/smallptrset-h">llvm/ADT/SmallPtrSet.h</a>"
#include "<a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/adt/smallvector-h">llvm/ADT/SmallVector.h</a>"
#include "<a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/adt/stringref-h">llvm/ADT/StringRef.h</a>"
#include "<a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/analysis/blockfrequencyinfo-h">llvm/Analysis/BlockFrequencyInfo.h</a>"
#include "<a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/analysis/branchprobabilityinfo-h">llvm/Analysis/BranchProbabilityInfo.h</a>"
#include "<a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/analysis/constantfolding-h">llvm/Analysis/ConstantFolding.h</a>"
#include "<a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/analysis/indirectcallpromotionanalysis-h">llvm/Analysis/IndirectCallPromotionAnalysis.h</a>"
#include "<a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/analysis/loopinfo-h">llvm/Analysis/LoopInfo.h</a>"
#include "<a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/analysis/memoryprofileinfo-h">llvm/Analysis/MemoryProfileInfo.h</a>"
#include "<a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/analysis/profilesummaryinfo-h">llvm/Analysis/ProfileSummaryInfo.h</a>"
#include "<a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/analysis/stacksafetyanalysis-h">llvm/Analysis/StackSafetyAnalysis.h</a>"
#include "<a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/analysis/typemetadatautils-h">llvm/Analysis/TypeMetadataUtils.h</a>"
#include "<a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/ir/attributes-h">llvm/IR/Attributes.h</a>"
#include "<a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/ir/basicblock-h">llvm/IR/BasicBlock.h</a>"
#include "<a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/ir/constant-h">llvm/IR/Constant.h</a>"
#include "<a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/ir/constants-h">llvm/IR/Constants.h</a>"
#include "<a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/ir/dominators-h">llvm/IR/Dominators.h</a>"
#include "<a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/ir/function-h">llvm/IR/Function.h</a>"
#include "<a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/ir/globalalias-h">llvm/IR/GlobalAlias.h</a>"
#include "<a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/ir/globalvalue-h">llvm/IR/GlobalValue.h</a>"
#include "<a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/ir/globalvariable-h">llvm/IR/GlobalVariable.h</a>"
#include "<a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/ir/instructions-h">llvm/IR/Instructions.h</a>"
#include "<a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/ir/intrinsicinst-h">llvm/IR/IntrinsicInst.h</a>"
#include "<a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/ir/metadata-h">llvm/IR/Metadata.h</a>"
#include "<a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/ir/module-h">llvm/IR/Module.h</a>"
#include "<a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/ir/modulesummaryindex-h">llvm/IR/ModuleSummaryIndex.h</a>"
#include "<a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/ir/use-h">llvm/IR/Use.h</a>"
#include "<a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/ir/user-h">llvm/IR/User.h</a>"
#include "<a href="/web-llvm/docs/api/files/include/include/llvm/initializepasses-h">llvm/InitializePasses.h</a>"
#include "<a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/object/modulesymboltable-h">llvm/Object/ModuleSymbolTable.h</a>"
#include "<a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/object/symbolicfile-h">llvm/Object/SymbolicFile.h</a>"
#include "<a href="/web-llvm/docs/api/files/include/include/llvm/pass-h">llvm/Pass.h</a>"
#include "<a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/support/casting-h">llvm/Support/Casting.h</a>"
#include "<a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/support/commandline-h">llvm/Support/CommandLine.h</a>"
#include "<a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/support/filesystem-h">llvm/Support/FileSystem.h</a>"
#include &lt;cassert&gt;
#include &lt;cstdint&gt;
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

</table>

## Functions Index

<table class="doxyMembersIndex">

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">static bool</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ad63451798277c4bce34d6446c9cb75ac">findRefEdges</a> (ModuleSummaryIndex &amp;Index, const User *CurUser, SetVector&lt; ValueInfo, SmallVector&lt; ValueInfo, 0 &gt; &gt; &amp;RefEdges, SmallPtrSet&lt; const User *, 8 &gt; &amp;Visited, bool &amp;RefLocalLinkageIFunc)</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">static <a href="/web-llvm/docs/api/structs/llvm/calleeinfo/#a2413e35985411a461b9ab03c17c01caa">CalleeInfo::HotnessType</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a38dd3609a23a5d917457d18d88fceff3">getHotness</a> (uint64_t ProfileCount, ProfileSummaryInfo *PSI)</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a7fcfddcf483c0b43f2614b2b292f0393">isNonRenamableLocal</a> (const GlobalValue &amp;GV)</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">static void</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a0e78e3b2bdc628be0f3e61c2b0aba32e">addVCallToSet</a> (DevirtCallSite Call, GlobalValue::GUID Guid, SetVector&lt; FunctionSummary::VFuncId, std::vector&lt; FunctionSummary::VFuncId &gt; &gt; &amp;VCalls, SetVector&lt; FunctionSummary::ConstVCall, std::vector&lt; FunctionSummary::ConstVCall &gt; &gt; &amp;ConstVCalls)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Determine whether this call has all constant integer arguments (excluding "this") and summarize it to VCalls or ConstVCalls as appropriate. <a href="#a0e78e3b2bdc628be0f3e61c2b0aba32e">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">static void</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ae52dc32e051ded6356e4065b75d19935">addIntrinsicToSummary</a> (const CallInst *CI, SetVector&lt; GlobalValue::GUID, std::vector&lt; GlobalValue::GUID &gt; &gt; &amp;TypeTests, SetVector&lt; FunctionSummary::VFuncId, std::vector&lt; FunctionSummary::VFuncId &gt; &gt; &amp;TypeTestAssumeVCalls, SetVector&lt; FunctionSummary::VFuncId, std::vector&lt; FunctionSummary::VFuncId &gt; &gt; &amp;TypeCheckedLoadVCalls, SetVector&lt; FunctionSummary::ConstVCall, std::vector&lt; FunctionSummary::ConstVCall &gt; &gt; &amp;TypeTestAssumeConstVCalls, SetVector&lt; FunctionSummary::ConstVCall, std::vector&lt; FunctionSummary::ConstVCall &gt; &gt; &amp;TypeCheckedLoadConstVCalls, DominatorTree &amp;DT)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>If this intrinsic call requires that we add information to the function summary, do so via the non-constant reference arguments. <a href="#ae52dc32e051ded6356e4065b75d19935">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">static bool</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a5f1b165d0efdc05ba21b9ca51cec0cf4">isNonVolatileLoad</a> (const Instruction *I)</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ab50b4ce10ba21d6a8f864e219c70b1b4">isNonVolatileStore</a> (const Instruction *I)</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#aaeceda7c9243e01a0888f44e2f3e7ba3">mustBeUnreachableFunction</a> (const Function &amp;F)</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">static void</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a9b06152b51259f884261bba3099e4fc6">computeFunctionSummary</a> (ModuleSummaryIndex &amp;Index, const Module &amp;M, const Function &amp;F, BlockFrequencyInfo *BFI, ProfileSummaryInfo *PSI, DominatorTree &amp;DT, bool HasLocalsInUsedOrAsm, DenseSet&lt; GlobalValue::GUID &gt; &amp;CantBePromoted, bool IsThinLTO, std::function&lt; const StackSafetyInfo *(const Function &amp;F)&gt; GetSSICallback)</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">static void</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a221bfefa2a7606c89cb5a8635375f891">findFuncPointers</a> (const Constant *I, uint64_t StartingOffset, const Module &amp;M, ModuleSummaryIndex &amp;Index, VTableFuncList &amp;VTableFuncs, const GlobalVariable &amp;OrigGV)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Find function pointers referenced within the given vtable initializer (or subset of an initializer) <span class="doxyComputerOutput">I</span>. <a href="#a221bfefa2a7606c89cb5a8635375f891">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">static void</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a1d170ee13fa2607c646195d82b5f9899">computeVTableFuncs</a> (ModuleSummaryIndex &amp;Index, const GlobalVariable &amp;V, const Module &amp;M, VTableFuncList &amp;VTableFuncs)</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">static void</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#af9fba4efc601bd7c469537ae25d76cdb">recordTypeIdCompatibleVtableReferences</a> (ModuleSummaryIndex &amp;Index, const GlobalVariable &amp;V, SmallVectorImpl&lt; MDNode * &gt; &amp;Types)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p><a href="/web-llvm/docs/api/classes/llvm/record">Record</a> vtable definition <span class="doxyComputerOutput">V</span> for each type metadata it references. <a href="#af9fba4efc601bd7c469537ae25d76cdb">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">static void</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a33a077de9929c7516aed06f18563f450">computeVariableSummary</a> (ModuleSummaryIndex &amp;Index, const GlobalVariable &amp;V, DenseSet&lt; GlobalValue::GUID &gt; &amp;CantBePromoted, const Module &amp;M, SmallVectorImpl&lt; MDNode * &gt; &amp;Types)</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">static void</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a1e1c4a4bdaaa3af5a3c988554783bd48">computeAliasSummary</a> (ModuleSummaryIndex &amp;Index, const GlobalAlias &amp;A, DenseSet&lt; GlobalValue::GUID &gt; &amp;CantBePromoted)</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">static void</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a37994a2b7672d14f55587c8d6311adcf">setLiveRoot</a> (ModuleSummaryIndex &amp;Index, StringRef Name)</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#af072630d86644c22c7d47b0008668581">INITIALIZE_PASS_BEGIN</a> (ModuleSummaryIndexWrapperPass, "module-summary-analysis", "Module Summary Analysis", false, true) INITIALIZE_PASS_END(ModuleSummaryIndexWrapperPass</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a0c644c1ec65bfe3ab19a7ac9d5e0aeab">INITIALIZE_PASS</a> (ImmutableModuleSummaryIndexWrapperPass, "module-summary-info", "Module summary info", false, true) bool llvm</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">static <a href="/web-llvm/docs/api/classes/llvm/cl/opt">cl::opt</a>&lt; <a href="/web-llvm/docs/api/classes/llvm/functionsummary/#ad8775375a74c04489e82ba5e39a2cf33">FunctionSummary::ForceSummaryHotnessType</a>, <a href="/web-llvm/docs/api/files/lib/lib/analysis/basicaliasanalysis-cpp/#af6d5cafbdfc5313e65d990120021a3ec">true</a> &gt;</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#aadb892aa087cdabd7ecc542b8d54b4c3">FSEC</a>("force-summary-edges-cold", cl::Hidden, cl::location(ForceSummaryEdgesCold), cl::desc("Force all edges in the function summary to cold"), cl::values(clEnumValN(FunctionSummary::FSHT_None, "none", "None."), clEnumValN(FunctionSummary::FSHT_AllNonCritical, "all-non-critical", "All non-critical edges."), clEnumValN(FunctionSummary::FSHT_All, "all", "All edges.")))</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ac6f2d6c702d85380dd8d2f5e59f37f57">ModuleSummaryDotFile</a>("module-summary-dot-file", cl::Hidden, cl::value_desc("filename"), cl::desc("File to emit dot graph of new summary into"))</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a5b43a87e5f7e1b46d4824c06ebc9837d">EnableMemProfIndirectCallSupport</a>("enable-memprof-indirect-call-support", cl::init(false), cl::Hidden, cl::desc("Enable MemProf support for summarizing and cloning indirect calls"))</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/arm/armloadstoreoptimizer-cpp/#ab3bfc7321acfbc3619170d5bed907cb3">cl::opt</a>&lt; bool &gt;</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a779f5a0d11c10db9cac376d263b8e9fe">ScalePartialSampleProfileWorkingSetSize</a></td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/arm/armloadstoreoptimizer-cpp/#ab3bfc7321acfbc3619170d5bed907cb3">cl::opt</a>&lt; unsigned &gt;</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a1b743fac529f89163351c3db7fe68a13">MaxNumVTableAnnotations</a></td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/arm/armloadstoreoptimizer-cpp/#ab3bfc7321acfbc3619170d5bed907cb3">cl::opt</a>&lt; bool &gt;</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a7af832ec142a036af0c6439583d7785d">MemProfReportHintedSizes</a></td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">module summary</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#abfa9bcfe6f0180f576c1a8c503ba2a03">analysis</a></td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">module summary <a href="/web-llvm/docs/api/classes/llvm/module">Module</a> Summary</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a380fed491f598d1230cde8972f3e5418">Analysis</a></td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">module summary <a href="/web-llvm/docs/api/classes/llvm/module">Module</a> Summary</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a929abbf0f66a4052924aa363a61b223e">false</a></td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ad78e062f62e0d6e453941fb4ca843e4d">DEBUG_TYPE</a>&nbsp;&nbsp;&nbsp;"module-summary-analysis"</td>
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

### addIntrinsicToSummary() {#ae52dc32e051ded6356e4065b75d19935}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void addIntrinsicToSummary (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/callinst">CallInst</a> * CI, <a href="/web-llvm/docs/api/classes/llvm/setvector">SetVector</a>&lt; <a href="/web-llvm/docs/api/classes/llvm/globalvalue/#a3af0428ec6e48cb2f05c199b7b9f7e07">GlobalValue::GUID</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/amdgpupromotealloca-cpp/#ac760e37eba1d852d0a28011a1a0ce05f">std::vector</a>&lt; <a href="/web-llvm/docs/api/classes/llvm/globalvalue/#a3af0428ec6e48cb2f05c199b7b9f7e07">GlobalValue::GUID</a> &gt; &gt; &amp; TypeTests, <a href="/web-llvm/docs/api/classes/llvm/setvector">SetVector</a>&lt; <a href="/web-llvm/docs/api/structs/llvm/functionsummary/vfuncid">FunctionSummary::VFuncId</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/amdgpupromotealloca-cpp/#ac760e37eba1d852d0a28011a1a0ce05f">std::vector</a>&lt; <a href="/web-llvm/docs/api/structs/llvm/functionsummary/vfuncid">FunctionSummary::VFuncId</a> &gt; &gt; &amp; TypeTestAssumeVCalls, <a href="/web-llvm/docs/api/classes/llvm/setvector">SetVector</a>&lt; <a href="/web-llvm/docs/api/structs/llvm/functionsummary/vfuncid">FunctionSummary::VFuncId</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/amdgpupromotealloca-cpp/#ac760e37eba1d852d0a28011a1a0ce05f">std::vector</a>&lt; <a href="/web-llvm/docs/api/structs/llvm/functionsummary/vfuncid">FunctionSummary::VFuncId</a> &gt; &gt; &amp; TypeCheckedLoadVCalls, <a href="/web-llvm/docs/api/classes/llvm/setvector">SetVector</a>&lt; <a href="/web-llvm/docs/api/structs/llvm/functionsummary/constvcall">FunctionSummary::ConstVCall</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/amdgpupromotealloca-cpp/#ac760e37eba1d852d0a28011a1a0ce05f">std::vector</a>&lt; <a href="/web-llvm/docs/api/structs/llvm/functionsummary/constvcall">FunctionSummary::ConstVCall</a> &gt; &gt; &amp; TypeTestAssumeConstVCalls, <a href="/web-llvm/docs/api/classes/llvm/setvector">SetVector</a>&lt; <a href="/web-llvm/docs/api/structs/llvm/functionsummary/constvcall">FunctionSummary::ConstVCall</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/amdgpupromotealloca-cpp/#ac760e37eba1d852d0a28011a1a0ce05f">std::vector</a>&lt; <a href="/web-llvm/docs/api/structs/llvm/functionsummary/constvcall">FunctionSummary::ConstVCall</a> &gt; &gt; &amp; TypeCheckedLoadConstVCalls, <a href="/web-llvm/docs/api/classes/llvm/dominatortree">DominatorTree</a> &amp; DT)</td>
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

<p>If this intrinsic call requires that we add information to the function summary, do so via the non-constant reference arguments.</p>

<p>Definition at line 204 of file <a href="/web-llvm/docs/api/files/lib/lib/analysis/modulesummaryanalysis-cpp">ModuleSummaryAnalysis.cpp</a>.</p>


<p>References <a href="#a0e78e3b2bdc628be0f3e61c2b0aba32e">addVCallToSet</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a61d13d6824ec46c31260a4fd0997eda0">llvm::any_of</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#ac4fc845f5ed92de63cd4474f128f5fc5">llvm::cast</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a22eeee01734061ac1b31ccd994c49eef">llvm::dyn_cast</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a8148654fcf3528ef06d7a0e28b57b952">llvm::findDevirtualizableCallsForTypeCheckedLoad</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#af88f364cd09c715e8853a1027c7180ef">llvm::findDevirtualizableCallsForTypeTest</a>, <a href="/web-llvm/docs/api/classes/llvm/callbase/#aabd76e6a8a23a5af1ce4d3c310d88bcd">llvm::CallBase::getArgOperand</a>, <a href="/web-llvm/docs/api/classes/llvm/callbase/#a2b1ae7cf1bafdd43d1fee4c6ad0a2913">llvm::CallBase::getCalledFunction</a>, <a href="/web-llvm/docs/api/classes/llvm/globalvalue/#a71ee7e63264e4997a3340a781d44832e">llvm::GlobalValue::getGUID</a>, <a href="/web-llvm/docs/api/classes/llvm/function/#a4d0a7baab8d078065b2de10e3460892a">llvm::Function::getIntrinsicID</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#af59335be18fa802d111a646be658b7d0acb957607a78494ea70db887d1463437c">llvm::Guid</a> and <a href="/web-llvm/docs/api/classes/llvm/value/#abf855b7cd63a0cd7f73759e396f280c9">llvm::Value::uses</a>.</p>


<p>Referenced by <a href="#a9b06152b51259f884261bba3099e4fc6">computeFunctionSummary</a>.</p>

</div>
</div>

### addVCallToSet() {#a0e78e3b2bdc628be0f3e61c2b0aba32e}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void addVCallToSet (<a href="/web-llvm/docs/api/structs/llvm/devirtcallsite">DevirtCallSite</a> Call, <a href="/web-llvm/docs/api/classes/llvm/globalvalue/#a3af0428ec6e48cb2f05c199b7b9f7e07">GlobalValue::GUID</a> Guid, <a href="/web-llvm/docs/api/classes/llvm/setvector">SetVector</a>&lt; <a href="/web-llvm/docs/api/structs/llvm/functionsummary/vfuncid">FunctionSummary::VFuncId</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/amdgpupromotealloca-cpp/#ac760e37eba1d852d0a28011a1a0ce05f">std::vector</a>&lt; <a href="/web-llvm/docs/api/structs/llvm/functionsummary/vfuncid">FunctionSummary::VFuncId</a> &gt; &gt; &amp; VCalls, <a href="/web-llvm/docs/api/classes/llvm/setvector">SetVector</a>&lt; <a href="/web-llvm/docs/api/structs/llvm/functionsummary/constvcall">FunctionSummary::ConstVCall</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/amdgpupromotealloca-cpp/#ac760e37eba1d852d0a28011a1a0ce05f">std::vector</a>&lt; <a href="/web-llvm/docs/api/structs/llvm/functionsummary/constvcall">FunctionSummary::ConstVCall</a> &gt; &gt; &amp; ConstVCalls)</td>
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

<p>Determine whether this call has all constant integer arguments (excluding "this") and summarize it to VCalls or ConstVCalls as appropriate.</p>

<p>Definition at line 183 of file <a href="/web-llvm/docs/api/files/lib/lib/analysis/modulesummaryanalysis-cpp">ModuleSummaryAnalysis.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/namespaces/llvm/#a02981de53fb6ffd384d39addc4d25f37">llvm::drop_begin</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a22eeee01734061ac1b31ccd994c49eef">llvm::dyn_cast</a> and <a href="/web-llvm/docs/api/namespaces/llvm/#af59335be18fa802d111a646be658b7d0acb957607a78494ea70db887d1463437c">llvm::Guid</a>.</p>


<p>Referenced by <a href="#ae52dc32e051ded6356e4065b75d19935">addIntrinsicToSummary</a>.</p>

</div>
</div>

### computeAliasSummary() {#a1e1c4a4bdaaa3af5a3c988554783bd48}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void computeAliasSummary (<a href="/web-llvm/docs/api/classes/llvm/modulesummaryindex">ModuleSummaryIndex</a> &amp; Index, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/globalalias">GlobalAlias</a> &amp; A, <a href="/web-llvm/docs/api/classes/llvm/denseset">DenseSet</a>&lt; <a href="/web-llvm/docs/api/classes/llvm/globalvalue/#a3af0428ec6e48cb2f05c199b7b9f7e07">GlobalValue::GUID</a> &gt; &amp; CantBePromoted)</td>
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



<p>Definition at line 884 of file <a href="/web-llvm/docs/api/files/lib/lib/analysis/modulesummaryanalysis-cpp">ModuleSummaryAnalysis.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/files/lib/lib/ir/builtingcs-cpp/#a2e38c85003a042421cde1647632d0b72">A</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/silowercontrolflow-cpp/#a4868c5d81c5ccc98c47aeab6244346a0">assert</a>, <a href="/web-llvm/docs/api/classes/llvm/globalvaluesummary/#a04e3abfb7aee7a96d3d56a99c9f0b737acb646dd0be0c28c71a939dc87ab59340">llvm::GlobalValueSummary::Definition</a>, <a href="/web-llvm/docs/api/classes/llvm/globalvalue/#a6811428caf500217f319c74e80900c14">llvm::GlobalValue::getGUID</a>, <a href="/web-llvm/docs/api/classes/llvm/detail/densesetimpl/#a1b0f3ebdced8fce4b22c6a63b25d9525">llvm::detail::DenseSetImpl&lt; ValueT, MapTy, ValueInfoT &gt;::insert</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a92ca992e52dddc420f4b069cae06dfbe">llvm::isa</a> and <a href="#a7fcfddcf483c0b43f2614b2b292f0393">isNonRenamableLocal</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/namespaces/llvm/#a49170e37072dd286a1fcf76f2efec373">llvm::buildModuleSummaryIndex</a>.</p>

</div>
</div>

### computeFunctionSummary() {#a9b06152b51259f884261bba3099e4fc6}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void computeFunctionSummary (<a href="/web-llvm/docs/api/classes/llvm/modulesummaryindex">ModuleSummaryIndex</a> &amp; Index, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/module">Module</a> &amp; M, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/function">Function</a> &amp; F, <a href="/web-llvm/docs/api/classes/llvm/blockfrequencyinfo">BlockFrequencyInfo</a> * BFI, <a href="/web-llvm/docs/api/classes/llvm/profilesummaryinfo">ProfileSummaryInfo</a> * PSI, <a href="/web-llvm/docs/api/classes/llvm/dominatortree">DominatorTree</a> &amp; DT, bool HasLocalsInUsedOrAsm, <a href="/web-llvm/docs/api/classes/llvm/denseset">DenseSet</a>&lt; <a href="/web-llvm/docs/api/classes/llvm/globalvalue/#a3af0428ec6e48cb2f05c199b7b9f7e07">GlobalValue::GUID</a> &gt; &amp; CantBePromoted, bool IsThinLTO, <a href="/web-llvm/docs/api/files/lib/lib/analysis/regionprinter-cpp/#aa37fbbce2360106772fd97ed06455d55">std::function</a>&lt; <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/stacksafetyinfo">StackSafetyInfo</a> *(<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/function">Function</a> &amp;<a href="/web-llvm/docs/api/files/lib/lib/support/md5-cpp/#a96d73bbd7af15cb1fc38c3f4a3bd82e9">F</a>)&gt; GetSSICallback)</td>
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



<p>Definition at line 302 of file <a href="/web-llvm/docs/api/files/lib/lib/analysis/modulesummaryanalysis-cpp">ModuleSummaryAnalysis.cpp</a>.</p>


<p>References <a href="#ae52dc32e051ded6356e4065b75d19935">addIntrinsicToSummary</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/silowercontrolflow-cpp/#a4868c5d81c5ccc98c47aeab6244346a0">assert</a>, <a href="/web-llvm/docs/api/classes/llvm/smallvectortemplatecommon/#acd9e771a3296c6b24146955754620557">llvm::SmallVectorTemplateCommon&lt; T, typename &gt;::back</a>, <a href="/web-llvm/docs/api/files/lib/lib/codegen/lib/codegen/asmprinter/asmprinter-cpp/#a9541bbf765f7db0b078a45d6f43c34b4a8cb28931840da67702e5bd9068512905">BBFreq</a>, <a href="/web-llvm/docs/api/classes/llvm/memprof/callstack/#a874c43eac4b723c9e3d0070342a8f0f3">llvm::memprof::CallStack&lt; NodeT, IteratorT &gt;::beginAfterSharedPrefix</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#ac4fc845f5ed92de63cd4474f128f5fc5">llvm::cast</a>, <a href="/web-llvm/docs/api/structs/llvm/calleeinfo/#a2413e35985411a461b9ab03c17c01caaa1a3c2e99e572ec71d3820d0363d90742">llvm::CalleeInfo::Cold</a>, <a href="/web-llvm/docs/api/classes/llvm/detail/densesetimpl/#afe504aa31a6a354cec13f5b32d0b1d9d">llvm::detail::DenseSetImpl&lt; ValueT, MapTy, ValueInfoT &gt;::count</a>, <a href="/web-llvm/docs/api/structs/llvm/calleeinfo/#a2413e35985411a461b9ab03c17c01caaa278d01e5af56273bae1bb99a98b370cd">llvm::CalleeInfo::Critical</a>, <a href="/web-llvm/docs/api/classes/llvm/globalvaluesummary/#a04e3abfb7aee7a96d3d56a99c9f0b737acb646dd0be0c28c71a939dc87ab59340">llvm::GlobalValueSummary::Definition</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a22eeee01734061ac1b31ccd994c49eef">llvm::dyn_cast</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a3377eac88526e806d9d887c4a0ba2a73">llvm::dyn_cast_if_present</a>, <a href="/web-llvm/docs/api/namespaces/llvm/mdconst/#ad7ca5290dc5789cbeae763690e6edccf">llvm::mdconst::dyn_extract</a>, <a href="/web-llvm/docs/api/classes/llvm/memprof/callstack/#aa9e2045926d6c3f8367573526b1af0f8">llvm::memprof::CallStack&lt; NodeT, IteratorT &gt;::empty</a>, <a href="/web-llvm/docs/api/classes/llvm/smallvectortemplatecommon/#ad9a3c7bc26b130377bbafc170b5f88a2">llvm::SmallVectorTemplateCommon&lt; T, typename &gt;::empty</a>, <a href="#a5b43a87e5f7e1b46d4824c06ebc9837d">EnableMemProfIndirectCallSupport</a>, <a href="/web-llvm/docs/api/classes/llvm/memprof/callstack/#a503a5a9aa96aa060c44756c03b5e5ef3">llvm::memprof::CallStack&lt; NodeT, IteratorT &gt;::end</a>, <a href="/web-llvm/docs/api/namespaces/llvm/mdconst/#a86397deb1d9d25f7a17ce22c4d66482f">llvm::mdconst::extract_or_null</a>, <a href="/web-llvm/docs/api/files/lib/lib/support/md5-cpp/#a96d73bbd7af15cb1fc38c3f4a3bd82e9">F</a>, <a href="#ad63451798277c4bce34d6446c9cb75ac">findRefEdges</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a388c42d2c8faae1dc055cec2db9c84f0">llvm::ForceSummaryEdgesCold</a>, <a href="/web-llvm/docs/api/classes/llvm/functionsummary/#ad8775375a74c04489e82ba5e39a2cf33ab2c06e29582ab10b05b65ae878009a63">llvm::FunctionSummary::FSHT_All</a>, <a href="/web-llvm/docs/api/classes/llvm/functionsummary/#ad8775375a74c04489e82ba5e39a2cf33a91e19b0aa8dcda73fcff4dfbe4f98b8c">llvm::FunctionSummary::FSHT_None</a>, <a href="/web-llvm/docs/api/classes/llvm/blockaddress/#af6e2f535824d8f9b4bf1b1a75e5ab57c">llvm::BlockAddress::get</a>, <a href="#a38dd3609a23a5d917457d18d88fceff3">getHotness</a>, <a href="/web-llvm/docs/api/namespaces/llvm/memprof/#a6adf5ed44d664399d019ab3727dc5bd9">llvm::memprof::getMIBAllocType</a>, <a href="/web-llvm/docs/api/namespaces/llvm/memprof/#ab5636c9dedf3853480a075cefc7cc1fa">llvm::memprof::getMIBStackNode</a>, <a href="/web-llvm/docs/api/classes/llvm/mdnode/#aa4068e37ec583962685e3567dc102ae5">llvm::MDNode::getNumOperands</a>, <a href="/web-llvm/docs/api/classes/llvm/mdnode/#a42409838a49255a3770da1469872f20b">llvm::MDNode::getOperand</a>, <a href="/web-llvm/docs/api/classes/llvm/profilesummaryinfo/#a37e70e7a7b5e8ebe792ecaec8639d16e">llvm::ProfileSummaryInfo::getProfileCount</a>, <a href="/web-llvm/docs/api/classes/llvm/icallpromotionanalysis/#ad7143519efbd492ef7ced88c6198e1ca">llvm::ICallPromotionAnalysis::getPromotionCandidatesForInstruction</a>, <a href="/web-llvm/docs/api/classes/llvm/profilesummaryinfo/#a9610274171a85158779e7ee6031d2376">llvm::ProfileSummaryInfo::hasPartialSampleProfile</a>, <a href="/web-llvm/docs/api/files/lib/lib/support/md5-cpp/#ac0eafdc9ee161b71e7af98af736952fd">I</a>, <a href="/web-llvm/docs/api/classes/llvm/detail/densesetimpl/#a1b0f3ebdced8fce4b22c6a63b25d9525">llvm::detail::DenseSetImpl&lt; ValueT, MapTy, ValueInfoT &gt;::insert</a>, <a href="/web-llvm/docs/api/classes/llvm/setvector/#af34eb71cc483e84d2eca80575cb9ccde">llvm::SetVector&lt; T, Vector, Set, N &gt;::insert</a>, <a href="/web-llvm/docs/api/classes/llvm/smallptrsetimpl/#a9d834ae3da8c62c2b668dada51335eb0">llvm::SmallPtrSetImpl&lt; PtrType &gt;::insert</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a92ca992e52dddc420f4b069cae06dfbe">llvm::isa</a>, <a href="#a7fcfddcf483c0b43f2614b2b292f0393">isNonRenamableLocal</a>, <a href="#a5f1b165d0efdc05ba21b9ca51cec0cf4">isNonVolatileLoad</a>, <a href="#ab50b4ce10ba21d6a8f864e219c70b1b4">isNonVolatileStore</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#af619a00e1ea9b169197b2d7ce9798aa6">llvm::mayHaveMemprofSummary</a>, <a href="/web-llvm/docs/api/files/lib/lib/analysis/memoryprofileinfo-cpp/#a696467f077d0e94dc6b3f171acc6be25">MemProfReportHintedSizes</a>, <a href="#aaeceda7c9243e01a0888f44e2f3e7ba3">mustBeUnreachableFunction</a>, <a href="/web-llvm/docs/api/classes/llvm/smallvectortemplatebase/#af42bfbc067df27c19ee2fc859df58799">llvm::SmallVectorTemplateBase&lt; T, bool &gt;::push_back</a>, <a href="/web-llvm/docs/api/classes/llvm/setvector/#a0ddd27a8bb9aa02671ef487de0c6f5ca">llvm::SetVector&lt; T, Vector, Set, N &gt;::remove</a>, <a href="#a779f5a0d11c10db9cac376d263b8e9fe">ScalePartialSampleProfileWorkingSetSize</a>, <a href="/web-llvm/docs/api/classes/llvm/setvector/#a1a42c1ba878bd637f374197d05f0a97f">llvm::SetVector&lt; T, Vector, Set, N &gt;::size</a>, <a href="/web-llvm/docs/api/classes/llvm/smallvectortemplatecommon/#a1c479a8c434377c2b8cb056bdfdfc201">llvm::SmallVectorTemplateCommon&lt; T, typename &gt;::size</a>, <a href="/web-llvm/docs/api/classes/llvm/mapvector/#a48284a35966b520c1da3a34a112726f5">llvm::MapVector&lt; KeyT, ValueT, MapType, VectorType &gt;::takeVector</a>, <a href="/web-llvm/docs/api/classes/llvm/setvector/#a7c36580f905b274ca0a1ade46ba06ae0">llvm::SetVector&lt; T, Vector, Set, N &gt;::takeVector</a>, <a href="/web-llvm/docs/api/structs/llvm/calleeinfo/#a2413e35985411a461b9ab03c17c01caaa88183b946cc5f0e8c96b2e66e1c74a7e">llvm::CalleeInfo::Unknown</a> and <a href="/web-llvm/docs/api/files/lib/lib/analysis/ivusers-cpp/#ac2f338c3f467b3d09613e190d73044a5">users</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/namespaces/llvm/#a49170e37072dd286a1fcf76f2efec373">llvm::buildModuleSummaryIndex</a>.</p>

</div>
</div>

### computeVariableSummary() {#a33a077de9929c7516aed06f18563f450}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void computeVariableSummary (<a href="/web-llvm/docs/api/classes/llvm/modulesummaryindex">ModuleSummaryIndex</a> &amp; Index, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/globalvariable">GlobalVariable</a> &amp; V, <a href="/web-llvm/docs/api/classes/llvm/denseset">DenseSet</a>&lt; <a href="/web-llvm/docs/api/classes/llvm/globalvalue/#a3af0428ec6e48cb2f05c199b7b9f7e07">GlobalValue::GUID</a> &gt; &amp; CantBePromoted, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/module">Module</a> &amp; M, <a href="/web-llvm/docs/api/classes/llvm/smallvectorimpl">SmallVectorImpl</a>&lt; <a href="/web-llvm/docs/api/classes/llvm/mdnode">MDNode</a> * &gt; &amp; Types)</td>
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



<p>Definition at line 833 of file <a href="/web-llvm/docs/api/files/lib/lib/analysis/modulesummaryanalysis-cpp">ModuleSummaryAnalysis.cpp</a>.</p>


<p>References <a href="#a1d170ee13fa2607c646195d82b5f9899">computeVTableFuncs</a>, <a href="/web-llvm/docs/api/classes/llvm/globalvaluesummary/#a04e3abfb7aee7a96d3d56a99c9f0b737acb646dd0be0c28c71a939dc87ab59340">llvm::GlobalValueSummary::Definition</a>, <a href="#ad63451798277c4bce34d6446c9cb75ac">findRefEdges</a>, <a href="/web-llvm/docs/api/classes/llvm/detail/densesetimpl/#a1b0f3ebdced8fce4b22c6a63b25d9525">llvm::detail::DenseSetImpl&lt; ValueT, MapTy, ValueInfoT &gt;::insert</a>, <a href="#a7fcfddcf483c0b43f2614b2b292f0393">isNonRenamableLocal</a>, <a href="#af9fba4efc601bd7c469537ae25d76cdb">recordTypeIdCompatibleVtableReferences</a> and <a href="/web-llvm/docs/api/classes/llvm/setvector/#a7c36580f905b274ca0a1ade46ba06ae0">llvm::SetVector&lt; T, Vector, Set, N &gt;::takeVector</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/namespaces/llvm/#a49170e37072dd286a1fcf76f2efec373">llvm::buildModuleSummaryIndex</a>.</p>

</div>
</div>

### computeVTableFuncs() {#a1d170ee13fa2607c646195d82b5f9899}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void computeVTableFuncs (<a href="/web-llvm/docs/api/classes/llvm/modulesummaryindex">ModuleSummaryIndex</a> &amp; Index, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/globalvariable">GlobalVariable</a> &amp; V, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/module">Module</a> &amp; M, <a href="/web-llvm/docs/api/namespaces/llvm/#a0cba6e4101e6b20a4b71aa098d1b6c2c">VTableFuncList</a> &amp; VTableFuncs)</td>
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



<p>Definition at line 792 of file <a href="/web-llvm/docs/api/files/lib/lib/analysis/modulesummaryanalysis-cpp">ModuleSummaryAnalysis.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/silowercontrolflow-cpp/#a4868c5d81c5ccc98c47aeab6244346a0">assert</a>, <a href="#a221bfefa2a7606c89cb5a8635375f891">findFuncPointers</a> and <a href="/web-llvm/docs/api/files/lib/lib/option/option-cpp/#a04665169063c8ca1f2ea96c27fc7c2b2">P</a>.</p>


<p>Referenced by <a href="#a33a077de9929c7516aed06f18563f450">computeVariableSummary</a>.</p>

</div>
</div>

### findFuncPointers() {#a221bfefa2a7606c89cb5a8635375f891}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void findFuncPointers (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/constant">Constant</a> * I, uint64_t StartingOffset, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/module">Module</a> &amp; M, <a href="/web-llvm/docs/api/classes/llvm/modulesummaryindex">ModuleSummaryIndex</a> &amp; Index, <a href="/web-llvm/docs/api/namespaces/llvm/#a0cba6e4101e6b20a4b71aa098d1b6c2c">VTableFuncList</a> &amp; VTableFuncs, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/globalvariable">GlobalVariable</a> &amp; OrigGV)</td>
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

<p>Find function pointers referenced within the given vtable initializer (or subset of an initializer) <span class="doxyComputerOutput">I</span>.</p>


<p>The starting offset of <span class="doxyComputerOutput">I</span> within the vtable initializer is <span class="doxyComputerOutput">StartingOffset</span>. <a href="/web-llvm/docs/api/classes/llvm/any">Any</a> discovered function pointers are added to <span class="doxyComputerOutput">VTableFuncs</span> along with their cumulative offset within the initializer.</p>


<p>Definition at line 720 of file <a href="/web-llvm/docs/api/files/lib/lib/analysis/modulesummaryanalysis-cpp">ModuleSummaryAnalysis.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/files/lib/lib/ir/builtingcs-cpp/#a2e38c85003a042421cde1647632d0b72">A</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/silowercontrolflow-cpp/#a4868c5d81c5ccc98c47aeab6244346a0">assert</a>, <a href="/web-llvm/docs/api/namespaces/llvm/callingconv/#ac6aa1387c4375260e2468eb5a77fdb4cafd841a49aec1539bc88abc8ff9e170fb">llvm::CallingConv::C</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#ac4fc845f5ed92de63cd4474f128f5fc5">llvm::cast</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/arm/armslshardening-cpp/#ad467c4ab9119043f9b7750ab986be61a">DL</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a22eeee01734061ac1b31ccd994c49eef">llvm::dyn_cast</a>, <a href="/web-llvm/docs/api/classes/llvm/structtype/#a339ac1c5133ca49e7a5fb1e37ce0a308">llvm::StructType::elements</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a206e2134ddd2312c3488d0632d98f554">llvm::enumerate</a>, <a href="#a221bfefa2a7606c89cb5a8635375f891">findFuncPointers</a>, <a href="/web-llvm/docs/api/classes/llvm/structlayout/#a331caeb70809f50e71528de06fba7b66">llvm::StructLayout::getElementContainingOffset</a>, <a href="/web-llvm/docs/api/classes/llvm/structlayout/#a3932cc53acb297750961bfdaa86425bc">llvm::StructLayout::getElementOffset</a>, <a href="/web-llvm/docs/api/classes/llvm/globalvariable/#a0698d5bcabbfbca4f56a9d7a81cecb25">llvm::GlobalVariable::getInitializer</a>, <a href="/web-llvm/docs/api/classes/llvm/value/#a0344a49526443edf90cc0aef3abd3337">llvm::Value::getType</a>, <a href="/web-llvm/docs/api/files/lib/lib/support/md5-cpp/#ac0eafdc9ee161b71e7af98af736952fd">I</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a92ca992e52dddc420f4b069cae06dfbe">llvm::isa</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a2e3103683ccd8b97050f821110b98ad2">llvm::IsConstantOffsetFromGlobal</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/x86/x86partialreduction-cpp/#a9e1483f7215664a2315c53c3558d9a8d">LHS</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a05f5b9a11bdcc5feba62899f95dcf878a3134224cba2545bc57954d3b072aebb4">llvm::Offset</a> and <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/x86/x86partialreduction-cpp/#a87b8bfbbe9d8f7146d7f20a5fb42efd0">RHS</a>.</p>


<p>Referenced by <a href="#a1d170ee13fa2607c646195d82b5f9899">computeVTableFuncs</a> and <a href="#a221bfefa2a7606c89cb5a8635375f891">findFuncPointers</a>.</p>

</div>
</div>

### findRefEdges() {#ad63451798277c4bce34d6446c9cb75ac}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool findRefEdges (<a href="/web-llvm/docs/api/classes/llvm/modulesummaryindex">ModuleSummaryIndex</a> &amp; Index, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/user">User</a> * CurUser, <a href="/web-llvm/docs/api/classes/llvm/setvector">SetVector</a>&lt; <a href="/web-llvm/docs/api/structs/llvm/valueinfo">ValueInfo</a>, <a href="/web-llvm/docs/api/classes/llvm/smallvector">SmallVector</a>&lt; <a href="/web-llvm/docs/api/structs/llvm/valueinfo">ValueInfo</a>, 0 &gt; &gt; &amp; RefEdges, <a href="/web-llvm/docs/api/classes/llvm/smallptrset">SmallPtrSet</a>&lt; <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/user">User</a> *, 8 &gt; &amp; Visited, bool &amp; RefLocalLinkageIFunc)</td>
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



<p>Definition at line 107 of file <a href="/web-llvm/docs/api/files/lib/lib/analysis/modulesummaryanalysis-cpp">ModuleSummaryAnalysis.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/namespaces/llvm/#a22eeee01734061ac1b31ccd994c49eef">llvm::dyn_cast</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a3377eac88526e806d9d887c4a0ba2a73">llvm::dyn_cast_if_present</a>, <a href="/web-llvm/docs/api/classes/llvm/smallvectortemplatecommon/#ad9a3c7bc26b130377bbafc170b5f88a2">llvm::SmallVectorTemplateCommon&lt; T, typename &gt;::empty</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a8f6ad5c1831928ee2c6c5058d9580edf">llvm::getValueProfDataFromInst</a>, <a href="/web-llvm/docs/api/files/lib/lib/support/md5-cpp/#ac0eafdc9ee161b71e7af98af736952fd">I</a>, <a href="/web-llvm/docs/api/classes/llvm/smallptrsetimpl/#a9d834ae3da8c62c2b668dada51335eb0">llvm::SmallPtrSetImpl&lt; PtrType &gt;::insert</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a92ca992e52dddc420f4b069cae06dfbe">llvm::isa</a>, <a href="/web-llvm/docs/api/files/lib/lib/analysis/indirectcallpromotionanalysis-cpp/#ae3ba3ba92eb73f08da8f9a6eac523b33">MaxNumVTableAnnotations</a>, <a href="/web-llvm/docs/api/classes/llvm/smallvectorimpl/#a0c8ffe664a36e30d49c84d0aded2fe08">llvm::SmallVectorImpl&lt; T &gt;::pop_back_val</a> and <a href="/web-llvm/docs/api/classes/llvm/smallvectortemplatebase/#af42bfbc067df27c19ee2fc859df58799">llvm::SmallVectorTemplateBase&lt; T, bool &gt;::push_back</a>.</p>


<p>Referenced by <a href="#a9b06152b51259f884261bba3099e4fc6">computeFunctionSummary</a> and <a href="#a33a077de9929c7516aed06f18563f450">computeVariableSummary</a>.</p>

</div>
</div>

### getHotness() {#a38dd3609a23a5d917457d18d88fceff3}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">CalleeInfo::HotnessType getHotness (uint64_t ProfileCount, <a href="/web-llvm/docs/api/classes/llvm/profilesummaryinfo">ProfileSummaryInfo</a> * PSI)</td>
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



<p>Definition at line 166 of file <a href="/web-llvm/docs/api/files/lib/lib/analysis/modulesummaryanalysis-cpp">ModuleSummaryAnalysis.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/structs/llvm/calleeinfo/#a2413e35985411a461b9ab03c17c01caaa1a3c2e99e572ec71d3820d0363d90742">llvm::CalleeInfo::Cold</a>, <a href="/web-llvm/docs/api/structs/llvm/calleeinfo/#a2413e35985411a461b9ab03c17c01caaa4194726ee334e1085d93e002837b73f0">llvm::CalleeInfo::Hot</a>, <a href="/web-llvm/docs/api/classes/llvm/profilesummaryinfo/#a5f58eb949321536363605ac9920a95cb">llvm::ProfileSummaryInfo::isColdCount</a>, <a href="/web-llvm/docs/api/classes/llvm/profilesummaryinfo/#ac46d4d55dd867977ba88d57a170e31de">llvm::ProfileSummaryInfo::isHotCount</a>, <a href="/web-llvm/docs/api/structs/llvm/calleeinfo/#a2413e35985411a461b9ab03c17c01caaa6adf97f83acf6453d4a6a4b1070f3754">llvm::CalleeInfo::None</a> and <a href="/web-llvm/docs/api/structs/llvm/calleeinfo/#a2413e35985411a461b9ab03c17c01caaa88183b946cc5f0e8c96b2e66e1c74a7e">llvm::CalleeInfo::Unknown</a>.</p>


<p>Referenced by <a href="#a9b06152b51259f884261bba3099e4fc6">computeFunctionSummary</a>.</p>

</div>
</div>

### INITIALIZE\_PASS() {#a0c644c1ec65bfe3ab19a7ac9d5e0aeab}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">INITIALIZE_PASS (<a href="/web-llvm/docs/api/classes/llvm/immutablemodulesummaryindexwrapperpass">ImmutableModuleSummaryIndexWrapperPass</a>, "module-summary-info", "Module summary info", false, <a href="/web-llvm/docs/api/files/lib/lib/analysis/basicaliasanalysis-cpp/#af6d5cafbdfc5313e65d990120021a3ec">true</a>)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 1216 of file <a href="/web-llvm/docs/api/files/lib/lib/analysis/modulesummaryanalysis-cpp">ModuleSummaryAnalysis.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/silowercontrolflow-cpp/#a4868c5d81c5ccc98c47aeab6244346a0">assert</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a22eeee01734061ac1b31ccd994c49eef">llvm::dyn_cast</a>, <a href="#a5b43a87e5f7e1b46d4824c06ebc9837d">EnableMemProfIndirectCallSupport</a>, <a href="/web-llvm/docs/api/files/lib/lib/passes/passbuilderbindings-cpp/#acdfbcf188e2d4a80837e89de2ccdffab">if</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a92ca992e52dddc420f4b069cae06dfbe">llvm::isa</a> and <a href="/web-llvm/docs/api/namespaces/llvm/#af619a00e1ea9b169197b2d7ce9798aa6">llvm::mayHaveMemprofSummary</a>.</p>

</div>
</div>

### INITIALIZE\_PASS\_BEGIN() {#af072630d86644c22c7d47b0008668581}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">INITIALIZE_PASS_BEGIN (<a href="/web-llvm/docs/api/classes/llvm/modulesummaryindexwrapperpass">ModuleSummaryIndexWrapperPass</a>, "module-summary-analysis", "Module Summary Analysis", false, <a href="/web-llvm/docs/api/files/lib/lib/analysis/basicaliasanalysis-cpp/#af6d5cafbdfc5313e65d990120021a3ec">true</a>)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 1148 of file <a href="/web-llvm/docs/api/files/lib/lib/analysis/modulesummaryanalysis-cpp">ModuleSummaryAnalysis.cpp</a>.</p>


<p>Reference <a href="/web-llvm/docs/api/files/include/include/llvm/passsupport-h/#a14724f1ccf528e73bb29bc9230737967">INITIALIZE_PASS_DEPENDENCY</a>.</p>

</div>
</div>

### isNonRenamableLocal() {#a7fcfddcf483c0b43f2614b2b292f0393}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool isNonRenamableLocal (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/globalvalue">GlobalValue</a> &amp; GV)</td>
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



<p>Definition at line 177 of file <a href="/web-llvm/docs/api/files/lib/lib/analysis/modulesummaryanalysis-cpp">ModuleSummaryAnalysis.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/classes/llvm/globalvalue/#a3ba1af4b9d9faa4a33729bbbecee83d1">llvm::GlobalValue::hasLocalLinkage</a> and <a href="/web-llvm/docs/api/classes/llvm/globalvalue/#a9f52d196211845d0d605733e2f699055">llvm::GlobalValue::hasSection</a>.</p>


<p>Referenced by <a href="#a1e1c4a4bdaaa3af5a3c988554783bd48">computeAliasSummary</a>, <a href="#a9b06152b51259f884261bba3099e4fc6">computeFunctionSummary</a> and <a href="#a33a077de9929c7516aed06f18563f450">computeVariableSummary</a>.</p>

</div>
</div>

### isNonVolatileLoad() {#a5f1b165d0efdc05ba21b9ca51cec0cf4}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool isNonVolatileLoad (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/instruction">Instruction</a> * I)</td>
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



<p>Definition at line 276 of file <a href="/web-llvm/docs/api/files/lib/lib/analysis/modulesummaryanalysis-cpp">ModuleSummaryAnalysis.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/namespaces/llvm/#a22eeee01734061ac1b31ccd994c49eef">llvm::dyn_cast</a> and <a href="/web-llvm/docs/api/files/lib/lib/support/md5-cpp/#ac0eafdc9ee161b71e7af98af736952fd">I</a>.</p>


<p>Referenced by <a href="#a9b06152b51259f884261bba3099e4fc6">computeFunctionSummary</a>.</p>

</div>
</div>

### isNonVolatileStore() {#ab50b4ce10ba21d6a8f864e219c70b1b4}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool isNonVolatileStore (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/instruction">Instruction</a> * I)</td>
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



<p>Definition at line 283 of file <a href="/web-llvm/docs/api/files/lib/lib/analysis/modulesummaryanalysis-cpp">ModuleSummaryAnalysis.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/namespaces/llvm/#a22eeee01734061ac1b31ccd994c49eef">llvm::dyn_cast</a> and <a href="/web-llvm/docs/api/files/lib/lib/support/md5-cpp/#ac0eafdc9ee161b71e7af98af736952fd">I</a>.</p>


<p>Referenced by <a href="#a9b06152b51259f884261bba3099e4fc6">computeFunctionSummary</a>.</p>

</div>
</div>

### mustBeUnreachableFunction() {#aaeceda7c9243e01a0888f44e2f3e7ba3}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool mustBeUnreachableFunction (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/function">Function</a> &amp; F)</td>
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



<p>Definition at line 295 of file <a href="/web-llvm/docs/api/files/lib/lib/analysis/modulesummaryanalysis-cpp">ModuleSummaryAnalysis.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/silowercontrolflow-cpp/#a4868c5d81c5ccc98c47aeab6244346a0">assert</a>, <a href="/web-llvm/docs/api/files/lib/lib/support/md5-cpp/#a96d73bbd7af15cb1fc38c3f4a3bd82e9">F</a> and <a href="/web-llvm/docs/api/namespaces/llvm/#a92ca992e52dddc420f4b069cae06dfbe">llvm::isa</a>.</p>


<p>Referenced by <a href="#a9b06152b51259f884261bba3099e4fc6">computeFunctionSummary</a>, <a href="/web-llvm/docs/api/structs/anonymous-wholeprogramdevirt-cpp-/devirtmodule/#a91cdd27c8deb2678870c535c9205fcc4">anonymous{WholeProgramDevirt.cpp}::DevirtModule::mustBeUnreachableFunction</a>, <a href="/web-llvm/docs/api/structs/anonymous-wholeprogramdevirt-cpp-/devirtindex/#abcd9be7acff38f150936f7bbfe72ac14">anonymous{WholeProgramDevirt.cpp}::DevirtIndex::tryFindVirtualCallTargets</a> and <a href="/web-llvm/docs/api/structs/anonymous-wholeprogramdevirt-cpp-/devirtmodule/#abfe26739ec5c54c0e4039d8e5d2d4a01">anonymous{WholeProgramDevirt.cpp}::DevirtModule::tryFindVirtualCallTargets</a>.</p>

</div>
</div>

### recordTypeIdCompatibleVtableReferences() {#af9fba4efc601bd7c469537ae25d76cdb}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void recordTypeIdCompatibleVtableReferences (<a href="/web-llvm/docs/api/classes/llvm/modulesummaryindex">ModuleSummaryIndex</a> &amp; Index, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/globalvariable">GlobalVariable</a> &amp; V, <a href="/web-llvm/docs/api/classes/llvm/smallvectorimpl">SmallVectorImpl</a>&lt; <a href="/web-llvm/docs/api/classes/llvm/mdnode">MDNode</a> * &gt; &amp; Types)</td>
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

<p><a href="/web-llvm/docs/api/classes/llvm/record">Record</a> vtable definition <span class="doxyComputerOutput">V</span> for each type metadata it references.</p>

<p>Definition at line 816 of file <a href="/web-llvm/docs/api/files/lib/lib/analysis/modulesummaryanalysis-cpp">ModuleSummaryAnalysis.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/namespaces/llvm/#ac4fc845f5ed92de63cd4474f128f5fc5">llvm::cast</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a22eeee01734061ac1b31ccd994c49eef">llvm::dyn_cast</a> and <a href="/web-llvm/docs/api/namespaces/llvm/#a05f5b9a11bdcc5feba62899f95dcf878a3134224cba2545bc57954d3b072aebb4">llvm::Offset</a>.</p>


<p>Referenced by <a href="#a33a077de9929c7516aed06f18563f450">computeVariableSummary</a>.</p>

</div>
</div>

### setLiveRoot() {#a37994a2b7672d14f55587c8d6311adcf}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void setLiveRoot (<a href="/web-llvm/docs/api/classes/llvm/modulesummaryindex">ModuleSummaryIndex</a> &amp; Index, <a href="/web-llvm/docs/api/classes/llvm/stringref">StringRef</a> Name)</td>
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



<p>Definition at line 908 of file <a href="/web-llvm/docs/api/files/lib/lib/analysis/modulesummaryanalysis-cpp">ModuleSummaryAnalysis.cpp</a>.</p>


<p>Reference <a href="/web-llvm/docs/api/classes/llvm/globalvalue/#a6811428caf500217f319c74e80900c14">llvm::GlobalValue::getGUID</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/namespaces/llvm/#a49170e37072dd286a1fcf76f2efec373">llvm::buildModuleSummaryIndex</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Variables

### analysis {#abfa9bcfe6f0180f576c1a8c503ba2a03}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">module summary analysis</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 1153 of file <a href="/web-llvm/docs/api/files/lib/lib/analysis/modulesummaryanalysis-cpp">ModuleSummaryAnalysis.cpp</a>.</p>

</div>
</div>

### Analysis {#a380fed491f598d1230cde8972f3e5418}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">module summary Module Summary Analysis</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 1154 of file <a href="/web-llvm/docs/api/files/lib/lib/analysis/modulesummaryanalysis-cpp">ModuleSummaryAnalysis.cpp</a>.</p>

</div>
</div>

### EnableMemProfIndirectCallSupport {#a5b43a87e5f7e1b46d4824c06ebc9837d}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">cl::opt&lt; bool &gt; EnableMemProfIndirectCallSupport("enable-memprof-indirect-call-support", cl::init(false), cl::Hidden, cl::desc( "Enable MemProf support for summarizing and cloning indirect calls"))</td>
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



<p>Definition at line 83 of file <a href="/web-llvm/docs/api/files/lib/lib/analysis/modulesummaryanalysis-cpp">ModuleSummaryAnalysis.cpp</a>.</p>


<p>Referenced by <a href="#a9b06152b51259f884261bba3099e4fc6">computeFunctionSummary</a> and <a href="#a0c644c1ec65bfe3ab19a7ac9d5e0aeab">INITIALIZE_PASS</a>.</p>

</div>
</div>

### false {#a929abbf0f66a4052924aa363a61b223e}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">module summary Module Summary false</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 1154 of file <a href="/web-llvm/docs/api/files/lib/lib/analysis/modulesummaryanalysis-cpp">ModuleSummaryAnalysis.cpp</a>.</p>

</div>
</div>

### FSEC {#aadb892aa087cdabd7ecc542b8d54b4c3}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">cl::opt&lt; FunctionSummary::ForceSummaryHotnessType, true &gt; FSEC("force-summary-edges-cold", cl::Hidden, cl::location(ForceSummaryEdgesCold), cl::desc("Force all edges in the function summary to cold"), cl::values(clEnumValN(FunctionSummary::FSHT_None, "none", "None."), clEnumValN(FunctionSummary::FSHT_AllNonCritical, "all-non-critical", "All non-critical edges."), clEnumValN(FunctionSummary::FSHT_All, "all", "All edges.")))</td>
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



<p>Definition at line 71 of file <a href="/web-llvm/docs/api/files/lib/lib/analysis/modulesummaryanalysis-cpp">ModuleSummaryAnalysis.cpp</a>.</p>

</div>
</div>

### MaxNumVTableAnnotations {#a1b743fac529f89163351c3db7fe68a13}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">cl::opt&lt;unsigned&gt; MaxNumVTableAnnotations</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 90 of file <a href="/web-llvm/docs/api/files/lib/lib/analysis/modulesummaryanalysis-cpp">ModuleSummaryAnalysis.cpp</a>.</p>

</div>
</div>

### MemProfReportHintedSizes {#a7af832ec142a036af0c6439583d7785d}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">cl::opt&lt;bool&gt; MemProfReportHintedSizes</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 92 of file <a href="/web-llvm/docs/api/files/lib/lib/analysis/modulesummaryanalysis-cpp">ModuleSummaryAnalysis.cpp</a>.</p>

</div>
</div>

### ModuleSummaryDotFile {#ac6f2d6c702d85380dd8d2f5e59f37f57}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">cl::opt&lt; std::string &gt; ModuleSummaryDotFile("module-summary-dot-file", cl::Hidden, cl::value_desc("filename"), cl::desc("File to emit dot graph of new summary into"))</td>
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



<p>Definition at line 79 of file <a href="/web-llvm/docs/api/files/lib/lib/analysis/modulesummaryanalysis-cpp">ModuleSummaryAnalysis.cpp</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/namespaces/llvm/#a49170e37072dd286a1fcf76f2efec373">llvm::buildModuleSummaryIndex</a>.</p>

</div>
</div>

### ScalePartialSampleProfileWorkingSetSize {#a779f5a0d11c10db9cac376d263b8e9fe}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">cl::opt&lt;bool&gt; ScalePartialSampleProfileWorkingSetSize</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 88 of file <a href="/web-llvm/docs/api/files/lib/lib/analysis/modulesummaryanalysis-cpp">ModuleSummaryAnalysis.cpp</a>.</p>


<p>Referenced by <a href="#a9b06152b51259f884261bba3099e4fc6">computeFunctionSummary</a>.</p>

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
<td class="doxyMemberName">#define DEBUG_TYPE&nbsp;&nbsp;&nbsp;"module-summary-analysis"</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 62 of file <a href="/web-llvm/docs/api/files/lib/lib/analysis/modulesummaryanalysis-cpp">ModuleSummaryAnalysis.cpp</a>.</p>

</div>
</div>

</div>

<hr/>

<p class="doxyGeneratedBy">Generated via <a href="https://github.com/xpack/doxygen2docusaurus">doxygen2docusaurus</a> by <a href="https://www.doxygen.nl">Doxygen</a> 1.15.0.</p>

</div>
