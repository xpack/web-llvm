---

# DO NOT EDIT!
# Automatically generated via doxygen2docusaurus by Doxygen.

slug: /api/files/lib/lib/transforms/lib/transforms/ipo/inliner-cpp
custom_edit_url: null
toc_max_heading_level: 4
keywords:
  - doxygen
  - reference
  - file

---

<div class="doxyPage">

# The `Inliner.cpp` File Reference



## Included Headers

<div class="doxyIncludesList">#include "<a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/transforms/include/llvm/transforms/ipo/inliner-h">llvm/Transforms/IPO/Inliner.h</a>"
#include "<a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/adt/priorityworklist-h">llvm/ADT/PriorityWorklist.h</a>"
#include "<a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/adt/stlextras-h">llvm/ADT/STLExtras.h</a>"
#include "<a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/adt/scopeexit-h">llvm/ADT/ScopeExit.h</a>"
#include "<a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/adt/setvector-h">llvm/ADT/SetVector.h</a>"
#include "<a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/adt/smallptrset-h">llvm/ADT/SmallPtrSet.h</a>"
#include "<a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/adt/smallvector-h">llvm/ADT/SmallVector.h</a>"
#include "<a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/adt/statistic-h">llvm/ADT/Statistic.h</a>"
#include "<a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/adt/stringextras-h">llvm/ADT/StringExtras.h</a>"
#include "<a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/adt/stringref-h">llvm/ADT/StringRef.h</a>"
#include "<a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/analysis/assumptioncache-h">llvm/Analysis/AssumptionCache.h</a>"
#include "<a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/analysis/basicaliasanalysis-h">llvm/Analysis/BasicAliasAnalysis.h</a>"
#include "<a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/analysis/blockfrequencyinfo-h">llvm/Analysis/BlockFrequencyInfo.h</a>"
#include "<a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/analysis/cgsccpassmanager-h">llvm/Analysis/CGSCCPassManager.h</a>"
#include "<a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/analysis/inlineadvisor-h">llvm/Analysis/InlineAdvisor.h</a>"
#include "<a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/analysis/inlinecost-h">llvm/Analysis/InlineCost.h</a>"
#include "<a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/analysis/lazycallgraph-h">llvm/Analysis/LazyCallGraph.h</a>"
#include "<a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/analysis/optimizationremarkemitter-h">llvm/Analysis/OptimizationRemarkEmitter.h</a>"
#include "<a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/analysis/profilesummaryinfo-h">llvm/Analysis/ProfileSummaryInfo.h</a>"
#include "<a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/analysis/replayinlineadvisor-h">llvm/Analysis/ReplayInlineAdvisor.h</a>"
#include "<a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/analysis/include/llvm/analysis/utils/importedfunctionsinliningstatistics-h">llvm/Analysis/Utils/ImportedFunctionsInliningStatistics.h</a>"
#include "<a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/ir/attributes-h">llvm/IR/Attributes.h</a>"
#include "<a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/ir/basicblock-h">llvm/IR/BasicBlock.h</a>"
#include "<a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/ir/debugloc-h">llvm/IR/DebugLoc.h</a>"
#include "<a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/ir/derivedtypes-h">llvm/IR/DerivedTypes.h</a>"
#include "<a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/ir/diagnosticinfo-h">llvm/IR/DiagnosticInfo.h</a>"
#include "<a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/ir/function-h">llvm/IR/Function.h</a>"
#include "<a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/ir/institerator-h">llvm/IR/InstIterator.h</a>"
#include "<a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/ir/instruction-h">llvm/IR/Instruction.h</a>"
#include "<a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/ir/instructions-h">llvm/IR/Instructions.h</a>"
#include "<a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/ir/intrinsicinst-h">llvm/IR/IntrinsicInst.h</a>"
#include "<a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/ir/metadata-h">llvm/IR/Metadata.h</a>"
#include "<a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/ir/module-h">llvm/IR/Module.h</a>"
#include "<a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/ir/passmanager-h">llvm/IR/PassManager.h</a>"
#include "<a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/ir/value-h">llvm/IR/Value.h</a>"
#include "<a href="/web-llvm/docs/api/files/include/include/llvm/pass-h">llvm/Pass.h</a>"
#include "<a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/support/casting-h">llvm/Support/Casting.h</a>"
#include "<a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/support/commandline-h">llvm/Support/CommandLine.h</a>"
#include "<a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/support/debug-h">llvm/Support/Debug.h</a>"
#include "<a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/support/raw-ostream-h">llvm/Support/raw_ostream.h</a>"
#include "<a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/transforms/include/llvm/transforms/utils/callpromotionutils-h">llvm/Transforms/Utils/CallPromotionUtils.h</a>"
#include "<a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/transforms/include/llvm/transforms/utils/cloning-h">llvm/Transforms/Utils/Cloning.h</a>"
#include "<a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/transforms/include/llvm/transforms/utils/local-h">llvm/Transforms/Utils/Local.h</a>"
#include "<a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/transforms/include/llvm/transforms/utils/moduleutils-h">llvm/Transforms/Utils/ModuleUtils.h</a>"
#include &lt;algorithm&gt;
#include &lt;cassert&gt;
#include &lt;utility&gt;
</div>

## Functions Index

<table class="doxyMembersIndex">

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a2cf0e6f0f7276ef3e449c577776a8d79">STATISTIC</a> (NumInlined, "Number of functions inlined")</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a43a412412dba52a42755ef315b5a1d10">STATISTIC</a> (NumDeleted, "Number of functions deleted because all callers found")</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a12a3c37c6bd2a94f388aafe4e68462f1">inlineHistoryIncludes</a> (Function *F, int InlineHistoryID, const SmallVectorImpl&lt; std::pair&lt; Function *, int &gt; &gt; &amp;InlineHistory)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Return true if the specified inline history <a href="/web-llvm/docs/api/namespaces/llvm/callingconv/#abdf8cf606905c10634e831390981b0ed">ID</a> indicates an inline history that includes the specified function. <a href="#a12a3c37c6bd2a94f388aafe4e68462f1">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">void</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ad4950adb47ff6ab441d457a67d66ebec">makeFunctionBodyUnreachable</a> (Function &amp;F)</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">static <a href="/web-llvm/docs/api/classes/llvm/cl/opt">cl::opt</a>&lt; int &gt;</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#aa7c9c54b4238110fb367b94fab00b853">IntraSCCCostMultiplier</a>("intra-scc-cost-multiplier", cl::init(2), cl::Hidden, cl::desc("Cost multiplier to multiply onto inlined call sites where the " "new call was previously an intra-SCC call (not relevant when the " "original call was already intra-SCC). This can accumulate over " "multiple inlinings (e.g. if a call site already had a cost " "multiplier and one of its inlined calls was also subject to " "this, the inlined call would have the original multiplier " "multiplied by intra-scc-cost-multiplier). This is to prevent tons of " "inlining through a child SCC which can cause terrible compile times"))</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a292d536b3d32e1daa73ecf947bdfc3e0">KeepAdvisorForPrinting</a>("keep-inline-advisor-for-printing", cl::init(false), cl::Hidden)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>A flag for test, so we can print the content of the advisor when running it as part of the default (e.g. <a href="#a292d536b3d32e1daa73ecf947bdfc3e0">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">static <a href="/web-llvm/docs/api/classes/llvm/cl/opt">cl::opt</a>&lt; bool &gt;</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a52008b14ac463a4009ec7debf64144d2">EnablePostSCCAdvisorPrinting</a>("enable-scc-inline-advisor-printing", cl::init(false), cl::Hidden)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Allows printing the contents of the advisor after each SCC inliner pass. <a href="#a52008b14ac463a4009ec7debf64144d2">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">static <a href="/web-llvm/docs/api/classes/llvm/cl/opt">cl::opt</a>&lt; <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/demangle/itaniumdemangle-h/#ae2b0d0345572d6718e219aa76d1d54edab45cffe084dd3d20d928bee85e7b0f21">std::string</a> &gt;</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a41211670f7f4ca37e0d867e6064768e5">CGSCCInlineReplayFile</a>("cgscc-inline-replay", cl::init(""), cl::value_desc("filename"), cl::desc("Optimization remarks file containing inline remarks to be replayed " "by cgscc inlining."), cl::Hidden)</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a28f0ec448d7749e1a5d97e70b52bebc8">CGSCCInlineReplayScope</a>("cgscc-inline-replay-scope", cl::init(ReplayInlinerSettings::Scope::Function), cl::values(clEnumValN(ReplayInlinerSettings::Scope::Function, "Function", "Replay on functions that have remarks associated " "with them (default)"), clEnumValN(ReplayInlinerSettings::Scope::Module, "Module", "Replay on the entire module")), cl::desc("Whether inline replay should be applied to the entire " "Module or just the Functions (default) that are present as " "callers in remarks during cgscc inlining."), cl::Hidden)</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ad4d7ff47530e67f077a4c3e0eaccd810">CGSCCInlineReplayFallback</a>("cgscc-inline-replay-fallback", cl::init(ReplayInlinerSettings::Fallback::Original), cl::values(clEnumValN(ReplayInlinerSettings::Fallback::Original, "Original", "All decisions not in replay send to original advisor (default)"), clEnumValN(ReplayInlinerSettings::Fallback::AlwaysInline, "AlwaysInline", "All decisions not in replay are inlined"), clEnumValN(ReplayInlinerSettings::Fallback::NeverInline, "NeverInline", "All decisions not in replay are not inlined")), cl::desc("How cgscc inline replay treats sites that don't come from the replay. " "Original: defers to original advisor, AlwaysInline: inline all sites " "not in replay, NeverInline: inline no sites not in replay"), cl::Hidden)</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ad13a4ff402ad74abfbb87485924b8293">CGSCCInlineReplayFormat</a>("cgscc-inline-replay-format", cl::init(CallSiteFormat::Format::LineColumnDiscriminator), cl::values(clEnumValN(CallSiteFormat::Format::Line, "Line", "<Line Number>"), clEnumValN(CallSiteFormat::Format::LineColumn, "LineColumn", "<Line Number>:<Column Number>"), clEnumValN(CallSiteFormat::Format::LineDiscriminator, "LineDiscriminator", "<Line Number>.<Discriminator>"), clEnumValN(CallSiteFormat::Format::LineColumnDiscriminator, "LineColumnDiscriminator", "<Line Number>:<Column Number>.<Discriminator> (default)")), cl::desc("How cgscc inline replay file is formatted"), cl::Hidden)</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ad78e062f62e0d6e453941fb4ca843e4d">DEBUG_TYPE</a>&nbsp;&nbsp;&nbsp;"inline"</td>
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

### inlineHistoryIncludes() {#a12a3c37c6bd2a94f388aafe4e68462f1}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool inlineHistoryIncludes (<a href="/web-llvm/docs/api/classes/llvm/function">Function</a> * F, int InlineHistoryID, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/smallvectorimpl">SmallVectorImpl</a>&lt; std::pair&lt; <a href="/web-llvm/docs/api/classes/llvm/function">Function</a> *, int &gt; &gt; &amp; InlineHistory)</td>
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

<p>Return true if the specified inline history <a href="/web-llvm/docs/api/namespaces/llvm/callingconv/#abdf8cf606905c10634e831390981b0ed">ID</a> indicates an inline history that includes the specified function.</p>

<p>Definition at line 146 of file <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/ipo/inliner-cpp">Inliner.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/silowercontrolflow-cpp/#a4868c5d81c5ccc98c47aeab6244346a0">assert</a> and <a href="/web-llvm/docs/api/files/lib/lib/support/md5-cpp/#a96d73bbd7af15cb1fc38c3f4a3bd82e9">F</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/classes/llvm/inlinerpass/#a78e09cea341cfdf58869920175c52d82">llvm::InlinerPass::run</a> and <a href="/web-llvm/docs/api/classes/llvm/moduleinlinerpass/#ab7155781c9a6aafef322de28d9bc4c86">llvm::ModuleInlinerPass::run</a>.</p>

</div>
</div>

### makeFunctionBodyUnreachable() {#ad4950adb47ff6ab441d457a67d66ebec}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void makeFunctionBodyUnreachable (<a href="/web-llvm/docs/api/classes/llvm/function">Function</a> &amp; F)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 197 of file <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/ipo/inliner-cpp">Inliner.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/classes/llvm/basicblock/#a4a5b798214be930cf8e133c032ba0129">llvm::BasicBlock::Create</a>, <a href="/web-llvm/docs/api/files/lib/lib/support/md5-cpp/#a96d73bbd7af15cb1fc38c3f4a3bd82e9">F</a> and <a href="/web-llvm/docs/api/namespaces/llvm/#a3d2cdc4a0db233678e7141c9d6ea3419">llvm::make_early_inc_range</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/classes/llvm/inlinerpass/#a78e09cea341cfdf58869920175c52d82">llvm::InlinerPass::run</a>.</p>

</div>
</div>

### STATISTIC() {#a2cf0e6f0f7276ef3e449c577776a8d79}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">STATISTIC (NumInlined, "Number of <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/amdgpulowermoduleldspass-cpp/#a8818b45f8c07ddce635268ec684dc61a">functions</a> inlined")</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 67 of file <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/ipo/inliner-cpp">Inliner.cpp</a>.</p>

</div>
</div>

### STATISTIC() {#a43a412412dba52a42755ef315b5a1d10}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">STATISTIC (NumDeleted, "Number of <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/amdgpulowermoduleldspass-cpp/#a8818b45f8c07ddce635268ec684dc61a">functions</a> deleted because all callers found")</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 68 of file <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/ipo/inliner-cpp">Inliner.cpp</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Variables

### CGSCCInlineReplayFallback {#ad4d7ff47530e67f077a4c3e0eaccd810}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">cl::opt&lt; ReplayInlinerSettings::Fallback &gt; CGSCCInlineReplayFallback("cgscc-inline-replay-fallback", cl::init(ReplayInlinerSettings::Fallback::Original), cl::values( clEnumValN( ReplayInlinerSettings::Fallback::Original, "Original", "All decisions not in replay send to original advisor (default)"), clEnumValN(ReplayInlinerSettings::Fallback::AlwaysInline, "AlwaysInline", "All decisions not in replay are inlined"), clEnumValN(ReplayInlinerSettings::Fallback::NeverInline, "NeverInline", "All decisions not in replay are not inlined")), cl::desc( "How cgscc inline replay treats sites that don't come from the replay. " "Original: defers to original advisor, AlwaysInline: inline all sites " "not in replay, NeverInline: inline no sites not in replay"), cl::Hidden)</td>
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



<p>Definition at line 113 of file <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/ipo/inliner-cpp">Inliner.cpp</a>.</p>

</div>
</div>

### CGSCCInlineReplayFile {#a41211670f7f4ca37e0d867e6064768e5}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">cl::opt&lt; std::string &gt; CGSCCInlineReplayFile("cgscc-inline-replay", cl::init(""), cl::value_desc("filename"), cl::desc( "Optimization remarks file containing inline remarks to be replayed " "by cgscc inlining."), cl::Hidden)</td>
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



<p>Definition at line 93 of file <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/ipo/inliner-cpp">Inliner.cpp</a>.</p>

</div>
</div>

### CGSCCInlineReplayFormat {#ad13a4ff402ad74abfbb87485924b8293}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">cl::opt&lt; CallSiteFormat::Format &gt; CGSCCInlineReplayFormat("cgscc-inline-replay-format", cl::init(CallSiteFormat::Format::LineColumnDiscriminator), cl::values( clEnumValN(CallSiteFormat::Format::Line, "Line", "&lt;Line Number&gt;"), clEnumValN(CallSiteFormat::Format::LineColumn, "LineColumn", "&lt;Line Number&gt;:&lt;Column Number&gt;"), clEnumValN(CallSiteFormat::Format::LineDiscriminator, "LineDiscriminator", "&lt;Line Number&gt;.&lt;Discriminator&gt;"), clEnumValN(CallSiteFormat::Format::LineColumnDiscriminator, "LineColumnDiscriminator", "&lt;Line Number&gt;:&lt;Column Number&gt;.&lt;Discriminator&gt; (default)")), cl::desc("How cgscc inline replay file is formatted"), cl::Hidden)</td>
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



<p>Definition at line 130 of file <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/ipo/inliner-cpp">Inliner.cpp</a>.</p>

</div>
</div>

### CGSCCInlineReplayScope {#a28f0ec448d7749e1a5d97e70b52bebc8}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">cl::opt&lt; ReplayInlinerSettings::Scope &gt; CGSCCInlineReplayScope("cgscc-inline-replay-scope", cl::init(ReplayInlinerSettings::Scope::Function), cl::values(clEnumValN(ReplayInlinerSettings::Scope::Function, "Function", "Replay on functions that have remarks associated " "with them (default)"), clEnumValN(ReplayInlinerSettings::Scope::Module, "Module", "Replay on the entire module")), cl::desc("Whether inline replay should be applied to the entire " "Module or just the Functions (default) that are present as " "callers in remarks during cgscc inlining."), cl::Hidden)</td>
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



<p>Definition at line 100 of file <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/ipo/inliner-cpp">Inliner.cpp</a>.</p>

</div>
</div>

### EnablePostSCCAdvisorPrinting {#a52008b14ac463a4009ec7debf64144d2}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">cl::opt&lt; bool &gt; EnablePostSCCAdvisorPrinting("enable-scc-inline-advisor-printing", cl::init(false), cl::Hidden)</td>
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

<p>Allows printing the contents of the advisor after each SCC inliner pass.</p>

<p>Definition at line 89 of file <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/ipo/inliner-cpp">Inliner.cpp</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/classes/llvm/moduleinlinerwrapperpass/#aff89291a71c595f474b9fc7c99860170">llvm::ModuleInlinerWrapperPass::ModuleInlinerWrapperPass</a>.</p>

</div>
</div>

### IntraSCCCostMultiplier {#aa7c9c54b4238110fb367b94fab00b853}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">cl::opt&lt; int &gt; IntraSCCCostMultiplier("intra-scc-cost-multiplier", cl::init(2), cl::Hidden, cl::desc( "Cost multiplier to multiply onto inlined call sites where the " "new call was previously an intra-SCC call (not relevant when the " "original call was already intra-SCC). This can accumulate over " "multiple inlinings (e.g. if a call site already had a cost " "multiplier and one of its inlined calls was also subject to " "this, the inlined call would have the original multiplier " "multiplied by intra-scc-cost-multiplier). This is to prevent tons of " "inlining through a child SCC which can cause terrible compile times"))</td>
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



<p>Definition at line 70 of file <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/ipo/inliner-cpp">Inliner.cpp</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/classes/llvm/inlinerpass/#a78e09cea341cfdf58869920175c52d82">llvm::InlinerPass::run</a>.</p>

</div>
</div>

### KeepAdvisorForPrinting {#a292d536b3d32e1daa73ecf947bdfc3e0}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">cl::opt&lt; bool &gt; KeepAdvisorForPrinting("keep-inline-advisor-for-printing", cl::init(false), cl::Hidden)</td>
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

<p>A flag for test, so we can print the content of the advisor when running it as part of the default (e.g.</p>


<p>-O3) pipeline.</p>


<p>Definition at line 84 of file <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/ipo/inliner-cpp">Inliner.cpp</a>.</p>

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
<td class="doxyMemberName">#define DEBUG_TYPE&nbsp;&nbsp;&nbsp;"inline"</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 65 of file <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/ipo/inliner-cpp">Inliner.cpp</a>.</p>

</div>
</div>

</div>

<hr/>

<p class="doxyGeneratedBy">Generated via <a href="https://github.com/xpack/doxygen2docusaurus">doxygen2docusaurus</a> by <a href="https://www.doxygen.nl">Doxygen</a> 1.14.0.</p>

</div>
