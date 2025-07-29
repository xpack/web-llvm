---

# DO NOT EDIT!
# Automatically generated via doxygen2docusaurus by Doxygen.

slug: /api/namespaces/anonymous-instrprofiling-cpp-
custom_edit_url: null
toc_max_heading_level: 4
keywords:
  - doxygen
  - reference
  - namespace

---

<div class="doxyPage">

# `anonymous{InstrProfiling.cpp}` Namespace



## Definition

<div class="doxyDefinition">
namespace anonymous{InstrProfiling.cpp} { ... }
</div>

## Classes Index

<table class="doxyMembersIndex">

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">struct</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="/web-llvm/docs/api/structs/anonymous-instrprofiling-cpp-/sampledinstrumentationconfig">SampledInstrumentationConfig</a></td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="/web-llvm/docs/api/classes/anonymous-instrprofiling-cpp-/instrlowerer">InstrLowerer</a></td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="/web-llvm/docs/api/classes/anonymous-instrprofiling-cpp-/pgocounterpromoterhelper">PGOCounterPromoterHelper</a></td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>A helper class to promote one counter RMW operation in the loop into register update. <a href="/web-llvm/docs/api/classes/anonymous-instrprofiling-cpp-/pgocounterpromoterhelper/#details">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">class</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="/web-llvm/docs/api/classes/anonymous-instrprofiling-cpp-/pgocounterpromoter">PGOCounterPromoter</a></td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>A helper class to do register promotion for all profile counter updates in a loop. <a href="/web-llvm/docs/api/classes/anonymous-instrprofiling-cpp-/pgocounterpromoter/#details">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

</table>

## Typedefs Index

<table class="doxyMembersIndex">

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">using</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a361b8ddbd271c831f936f4cca3bc7ec6">LoadStorePair</a> = std::pair&lt; <a href="/web-llvm/docs/api/classes/llvm/instruction">Instruction</a> *, <a href="/web-llvm/docs/api/classes/llvm/instruction">Instruction</a> * &gt;</td>
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

## Enumerations Index

<table class="doxyMembersIndex">

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">enum class</td>
<td class="doxyMemberIndexItemName" align="left" valign="top">ValueProfilingCallType { <a href="#ab90df0bea341a2cd835e25e236bac68b">...</a> }</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">static <a href="/web-llvm/docs/api/structs/anonymous-instrprofiling-cpp-/sampledinstrumentationconfig">SampledInstrumentationConfig</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a567d49d2063c521f212a391d13170a78">getSampledInstrumentationConfig</a> ()</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">static uint64_t</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#abaf4b4b336b3a93d025611fc42518a2b">getIntModuleFlagOrZero</a> (const Module &amp;M, StringRef Flag)</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a7309e5d4eda519b324d895ce7a75f862">enablesValueProfiling</a> (const Module &amp;M)</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#afb8afb94e818749e2f835faa7e974b5d">profDataReferencedByCode</a> (const Module &amp;M)</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/cl/opt">cl::opt</a>&lt; bool &gt;</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a8b989deaca06251ec85fd7c46384cffd">DoHashBasedCounterSplit</a>("hash-based-counter-split", cl::desc("Rename counter variable of a comdat function based on cfg hash"), cl::init(true))</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a6b3f6e320915349f0653d39442cd61e6">RuntimeCounterRelocation</a>("runtime-counter-relocation", cl::desc("Enable relocating counters at runtime."), cl::init(false))</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#afd8b1cecf4038e6ea20c5feec9353cfd">ValueProfileStaticAlloc</a>("vp-static-alloc", cl::desc("Do static counter allocation for value profiler"), cl::init(true))</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/cl/opt">cl::opt</a>&lt; double &gt;</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#acf233bbec8800c08be805896d73f6a09">NumCountersPerValueSite</a>("vp-counters-per-site", cl::desc("The average number of profile counters allocated " "per value profiling site."), cl::init(1.0))</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a5a9330e9eb0bceaa95c175878b07fd30">AtomicCounterUpdateAll</a>("instrprof-atomic-counter-update-all", cl::desc("Make all profile counter updates atomic (for testing only)"), cl::init(false))</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#aa96e53d0e78c4c541e906c99e5a03fbc">AtomicCounterUpdatePromoted</a>("atomic-counter-update-promoted", cl::desc("Do counter update using atomic fetch add " " for promoted counters only"), cl::init(false))</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#aa7677a1bbc2b30320c1178d3b72734c2">AtomicFirstCounter</a>("atomic-first-counter", cl::desc("Use atomic fetch add for first counter in a function (usually " "the entry counter)"), cl::init(false))</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ad0c1d4535b7972bca28a188cc136d128">ConditionalCounterUpdate</a>("conditional-counter-update", cl::desc("Do conditional counter updates in single byte counters mode)"), cl::init(false))</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a85ac84a02e1357f155129b907dabd263">DoCounterPromotion</a>("do-counter-promotion", cl::desc("Do counter register promotion"), cl::init(false))</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/cl/opt">cl::opt</a>&lt; unsigned &gt;</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a8e743c99eceeaeee15f380f474b5783e">MaxNumOfPromotionsPerLoop</a>("max-counter-promotions-per-loop", cl::init(20), cl::desc("Max number counter promotions per loop to avoid" " increasing register pressure too much"))</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/cl/opt">cl::opt</a>&lt; int &gt;</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a9a0c5035e575c6b2b6898567576ea54a">MaxNumOfPromotions</a>("max-counter-promotions", cl::init(-1), cl::desc("Max number of allowed counter promotions"))</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/cl/opt">cl::opt</a>&lt; unsigned &gt;</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a5b3e10c4011211ccbfebcf232115fee3">SpeculativeCounterPromotionMaxExiting</a>("speculative-counter-promotion-max-exiting", cl::init(3), cl::desc("The max number of exiting blocks of a loop to allow " " speculative counter promotion"))</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a33cfe9b13365aa727a6cbd3323938e20">SpeculativeCounterPromotionToLoop</a>("speculative-counter-promotion-to-loop", cl::desc("When the option is false, if the target block is in a loop, " "the promotion will be disallowed unless the promoted counter " " update can be further/iteratively promoted into an acyclic " " region."))</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#af98060255c39c5e6716d67994c79a1b3">IterativeCounterPromotion</a>("iterative-counter-promotion", cl::init(true), cl::desc("Allow counter promotion across the whole loop nest."))</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a0b50a4ffe69e0cb430be82ecb0585501">SkipRetExitBlock</a>("skip-ret-exit-block", cl::init(true), cl::desc("Suppress counter promotion if exit blocks contain ret."))</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a9009455575ed3956df4d3f2661fa35f9">SampledInstr</a>("sampled-instrumentation", cl::ZeroOrMore, cl::init(false), cl::desc("Do PGO instrumentation sampling"))</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a1aeb2630e9bc0d54b2b0a92634541aa0">SampledInstrPeriod</a>("sampled-instr-period", cl::desc("Set the profile instrumentation sample period. A sample period " "of 0 is invalid. For each sample period, a fixed number of " "consecutive samples will be recorded. The number is controlled " "by 'sampled-instr-burst-duration' flag. The default sample " "period of 65536 is optimized for generating efficient code that " "leverages unsigned short integer wrapping in overflow, but this " "is disabled under simple sampling (burst duration = 1)."), cl::init(USHRT_MAX+1))</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a4060600c2a9343ad1a973bf8201de98b">SampledInstrBurstDuration</a>("sampled-instr-burst-duration", cl::desc("Set the profile instrumentation burst duration, which can range " "from 1 to the value of 'sampled-instr-period' (0 is invalid). " "This number of samples will be recorded for each " "'sampled-instr-period' count update. Setting to 1 enables simple " "sampling, in which case it is recommended to set " "'sampled-instr-period' to a prime number."), cl::init(200))</td>
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

## Typedefs

### LoadStorePair {#a361b8ddbd271c831f936f4cca3bc7ec6}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">using anonymous{InstrProfiling.cpp}::LoadStorePair =  std::pair&lt;Instruction *, Instruction *&gt;</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 229 of file <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/instrumentation/instrprofiling-cpp">InstrProfiling.cpp</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Enumerations

### ValueProfilingCallType {#ab90df0bea341a2cd835e25e236bac68b}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">enum class anonymous{InstrProfiling.cpp}::ValueProfilingCallType </td>
</tr>
</table>
</td>
<td class="doxyMemberLabelsRight">
<span class="doxyMemberLabels">
<span class="doxyMemberLabel strong">strong</span>
</span>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">


<dl class="doxyEnumList">
<dt class="doxyEnumTableTitle">Enumeration values</dt>
<dd>
<table class="doxyEnumTable">

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">Default<a id="ab90df0bea341a2cd835e25e236bac68ba7a1920d61156abc05a60135aefe8bc67"></a></td>
<td class="doxyEnumItemDescription"></td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">MemOp<a id="ab90df0bea341a2cd835e25e236bac68ba33d2873b27c32fae6c504cf50d742381"></a></td>
<td class="doxyEnumItemDescription"></td>
</tr>

</table>
</dd>
</dl>

<p>Definition at line 663 of file <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/instrumentation/instrprofiling-cpp">InstrProfiling.cpp</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Functions

### enablesValueProfiling() {#a7309e5d4eda519b324d895ce7a75f862}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool anonymous{InstrProfiling.cpp}::enablesValueProfiling (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/module">Module</a> &amp; M)</td>
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



<p>Definition at line 241 of file <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/instrumentation/instrprofiling-cpp">InstrProfiling.cpp</a>.</p>


<p>References <a href="#abaf4b4b336b3a93d025611fc42518a2b">getIntModuleFlagOrZero</a> and <a href="/web-llvm/docs/api/namespaces/llvm/#aeb5dc4f19ccfe906a67745d10a39b4c6">llvm::isIRPGOFlagSet</a>.</p>


<p>Referenced by <a href="#afb8afb94e818749e2f835faa7e974b5d">profDataReferencedByCode</a>.</p>

</div>
</div>

### getIntModuleFlagOrZero() {#abaf4b4b336b3a93d025611fc42518a2b}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">uint64_t anonymous{InstrProfiling.cpp}::getIntModuleFlagOrZero (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/module">Module</a> &amp; M, <a href="/web-llvm/docs/api/classes/llvm/stringref">StringRef</a> Flag)</td>
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



<p>Definition at line 231 of file <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/instrumentation/instrprofiling-cpp">InstrProfiling.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/namespaces/llvm/#ac4fc845f5ed92de63cd4474f128f5fc5">llvm::cast</a> and <a href="/web-llvm/docs/api/namespaces/llvm/#a5f6182886dc2f96c204299e92c1565d5">llvm::dyn_cast_or_null</a>.</p>


<p>Referenced by <a href="#a7309e5d4eda519b324d895ce7a75f862">enablesValueProfiling</a>.</p>

</div>
</div>

### getSampledInstrumentationConfig() {#a567d49d2063c521f212a391d13170a78}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">SampledInstrumentationConfig anonymous{InstrProfiling.cpp}::getSampledInstrumentationConfig ()</td>
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



<p>Definition at line 210 of file <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/instrumentation/instrprofiling-cpp">InstrProfiling.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/structs/anonymous-instrprofiling-cpp-/sampledinstrumentationconfig/#a761c3263fcd2aae8509ba8a68759c2d0">anonymous{InstrProfiling.cpp}::SampledInstrumentationConfig::BurstDuration</a>, <a href="/web-llvm/docs/api/structs/anonymous-instrprofiling-cpp-/sampledinstrumentationconfig/#a2578bcbc57927aaca239ec007103f499">anonymous{InstrProfiling.cpp}::SampledInstrumentationConfig::IsFastSampling</a>, <a href="/web-llvm/docs/api/structs/anonymous-instrprofiling-cpp-/sampledinstrumentationconfig/#a3eb43f235c06e659ceb4602b7d81932b">anonymous{InstrProfiling.cpp}::SampledInstrumentationConfig::IsSimpleSampling</a>, <a href="/web-llvm/docs/api/structs/anonymous-instrprofiling-cpp-/sampledinstrumentationconfig/#acfc26039db374bd9ba631acb5dae5398">anonymous{InstrProfiling.cpp}::SampledInstrumentationConfig::Period</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a7f2a3d4dcfee70225988aec53ff1e173">llvm::report_fatal_error</a>, <a href="#a4060600c2a9343ad1a973bf8201de98b">SampledInstrBurstDuration</a>, <a href="#a1aeb2630e9bc0d54b2b0a92634541aa0">SampledInstrPeriod</a> and <a href="/web-llvm/docs/api/structs/anonymous-instrprofiling-cpp-/sampledinstrumentationconfig/#a457f0c61195e6e924e0ee634c657815a">anonymous{InstrProfiling.cpp}::SampledInstrumentationConfig::UseShort</a>.</p>

</div>
</div>

### profDataReferencedByCode() {#afb8afb94e818749e2f835faa7e974b5d}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool anonymous{InstrProfiling.cpp}::profDataReferencedByCode (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/module">Module</a> &amp; M)</td>
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



<p>Definition at line 247 of file <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/instrumentation/instrprofiling-cpp">InstrProfiling.cpp</a>.</p>


<p>Reference <a href="#a7309e5d4eda519b324d895ce7a75f862">enablesValueProfiling</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/classes/anonymous-instrprofiling-cpp-/instrlowerer/#a70e0b3b4e6c78926a887c81eba07c880">anonymous{InstrProfiling.cpp}::InstrLowerer::InstrLowerer</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Variables

### AtomicCounterUpdateAll {#a5a9330e9eb0bceaa95c175878b07fd30}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">cl::opt&lt; bool &gt; anonymous{InstrProfiling.cpp}::AtomicCounterUpdateAll("instrprof-atomic-counter-update-all", cl::desc("Make all profile counter updates atomic (for testing only)"), cl::init(false))</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 117 of file <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/instrumentation/instrprofiling-cpp">InstrProfiling.cpp</a>.</p>

</div>
</div>

### AtomicCounterUpdatePromoted {#aa96e53d0e78c4c541e906c99e5a03fbc}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">cl::opt&lt; bool &gt; anonymous{InstrProfiling.cpp}::AtomicCounterUpdatePromoted("atomic-counter-update-promoted", cl::desc("Do counter update using atomic fetch add " " for promoted counters only"), cl::init(false))</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 122 of file <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/instrumentation/instrprofiling-cpp">InstrProfiling.cpp</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/classes/anonymous-instrprofiling-cpp-/pgocounterpromoterhelper/#afb93c0389fa161c51b25541def502b89">anonymous{InstrProfiling.cpp}::PGOCounterPromoterHelper::doExtraRewritesBeforeFinalDeletion</a>.</p>

</div>
</div>

### AtomicFirstCounter {#aa7677a1bbc2b30320c1178d3b72734c2}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">cl::opt&lt; bool &gt; anonymous{InstrProfiling.cpp}::AtomicFirstCounter("atomic-first-counter", cl::desc("Use atomic fetch add for first counter in a function (usually " "the entry counter)"), cl::init(false))</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 128 of file <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/instrumentation/instrprofiling-cpp">InstrProfiling.cpp</a>.</p>

</div>
</div>

### ConditionalCounterUpdate {#ad0c1d4535b7972bca28a188cc136d128}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">cl::opt&lt; bool &gt; anonymous{InstrProfiling.cpp}::ConditionalCounterUpdate("conditional-counter-update", cl::desc("Do conditional counter updates in single byte counters mode)"), cl::init(false))</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 134 of file <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/instrumentation/instrprofiling-cpp">InstrProfiling.cpp</a>.</p>

</div>
</div>

### DoCounterPromotion {#a85ac84a02e1357f155129b907dabd263}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">cl::opt&lt; bool &gt; anonymous{InstrProfiling.cpp}::DoCounterPromotion("do-counter-promotion", cl::desc("Do counter register promotion"), cl::init(false))</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 144 of file <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/instrumentation/instrprofiling-cpp">InstrProfiling.cpp</a>.</p>

</div>
</div>

### DoHashBasedCounterSplit {#a8b989deaca06251ec85fd7c46384cffd}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">cl::opt&lt; bool &gt; anonymous{InstrProfiling.cpp}::DoHashBasedCounterSplit("hash-based-counter-split", cl::desc("Rename counter variable of a comdat function based on cfg hash"), cl::init(true))</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 92 of file <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/instrumentation/instrprofiling-cpp">InstrProfiling.cpp</a>.</p>

</div>
</div>

### IterativeCounterPromotion {#af98060255c39c5e6716d67994c79a1b3}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">cl::opt&lt; bool &gt; anonymous{InstrProfiling.cpp}::IterativeCounterPromotion("iterative-counter-promotion", cl::init(true), cl::desc("Allow counter promotion across the whole loop nest."))</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 169 of file <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/instrumentation/instrprofiling-cpp">InstrProfiling.cpp</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/classes/anonymous-instrprofiling-cpp-/pgocounterpromoterhelper/#afb93c0389fa161c51b25541def502b89">anonymous{InstrProfiling.cpp}::PGOCounterPromoterHelper::doExtraRewritesBeforeFinalDeletion</a>.</p>

</div>
</div>

### MaxNumOfPromotions {#a9a0c5035e575c6b2b6898567576ea54a}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">cl::opt&lt; int &gt; anonymous{InstrProfiling.cpp}::MaxNumOfPromotions("max-counter-promotions", cl::init(-1), cl::desc("Max number of allowed counter promotions"))</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 154 of file <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/instrumentation/instrprofiling-cpp">InstrProfiling.cpp</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/classes/anonymous-instrprofiling-cpp-/pgocounterpromoter/#aba67c0c1aba6c8fcf674792830b73704">anonymous{InstrProfiling.cpp}::PGOCounterPromoter::run</a>.</p>

</div>
</div>

### MaxNumOfPromotionsPerLoop {#a8e743c99eceeaeee15f380f474b5783e}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">cl::opt&lt; unsigned &gt; anonymous{InstrProfiling.cpp}::MaxNumOfPromotionsPerLoop("max-counter-promotions-per-loop", cl::init(20), cl::desc("Max number counter promotions per loop to avoid" " increasing register pressure too much"))</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 147 of file <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/instrumentation/instrprofiling-cpp">InstrProfiling.cpp</a>.</p>

</div>
</div>

### NumCountersPerValueSite {#acf233bbec8800c08be805896d73f6a09}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">cl::opt&lt; double &gt; anonymous{InstrProfiling.cpp}::NumCountersPerValueSite("vp-counters-per-site", cl::desc("The average number of profile counters allocated " "per value profiling site."), cl::init(1.0))</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 107 of file <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/instrumentation/instrprofiling-cpp">InstrProfiling.cpp</a>.</p>

</div>
</div>

### RuntimeCounterRelocation {#a6b3f6e320915349f0653d39442cd61e6}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">cl::opt&lt; bool &gt; anonymous{InstrProfiling.cpp}::RuntimeCounterRelocation("runtime-counter-relocation", cl::desc("Enable relocating counters at runtime."), cl::init(false))</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 98 of file <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/instrumentation/instrprofiling-cpp">InstrProfiling.cpp</a>.</p>

</div>
</div>

### SampledInstr {#a9009455575ed3956df4d3f2661fa35f9}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">cl::opt&lt; bool &gt; anonymous{InstrProfiling.cpp}::SampledInstr("sampled-instrumentation", cl::ZeroOrMore, cl::init(false), cl::desc("Do PGO instrumentation sampling"))</td>
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



<p>Definition at line 177 of file <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/instrumentation/instrprofiling-cpp">InstrProfiling.cpp</a>.</p>

</div>
</div>

### SampledInstrBurstDuration {#a4060600c2a9343ad1a973bf8201de98b}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">cl::opt&lt; unsigned &gt; anonymous{InstrProfiling.cpp}::SampledInstrBurstDuration("sampled-instr-burst-duration", cl::desc("Set the profile instrumentation burst duration, which can range " "from 1 to the value of 'sampled-instr-period' (0 is invalid). " "This number of samples will be recorded for each " "'sampled-instr-period' count update. Setting to 1 enables simple " "sampling, in which case it is recommended to set " "'sampled-instr-period' to a prime number."), cl::init(200))</td>
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



<p>Definition at line 192 of file <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/instrumentation/instrprofiling-cpp">InstrProfiling.cpp</a>.</p>


<p>Referenced by <a href="#a567d49d2063c521f212a391d13170a78">getSampledInstrumentationConfig</a>.</p>

</div>
</div>

### SampledInstrPeriod {#a1aeb2630e9bc0d54b2b0a92634541aa0}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">cl::opt&lt; unsigned &gt; anonymous{InstrProfiling.cpp}::SampledInstrPeriod("sampled-instr-period", cl::desc("Set the profile instrumentation sample period. A sample period " "of 0 is invalid. For each sample period, a fixed number of " "consecutive samples will be recorded. The number is controlled " "by 'sampled-instr-burst-duration' flag. The default sample " "period of 65536 is optimized for generating efficient code that " "leverages unsigned short integer wrapping in overflow, but this " "is disabled under simple sampling (burst duration = 1)."), cl::init(USHRT_MAX+1))</td>
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



<p>Definition at line 181 of file <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/instrumentation/instrprofiling-cpp">InstrProfiling.cpp</a>.</p>


<p>Referenced by <a href="#a567d49d2063c521f212a391d13170a78">getSampledInstrumentationConfig</a>.</p>

</div>
</div>

### SkipRetExitBlock {#a0b50a4ffe69e0cb430be82ecb0585501}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">cl::opt&lt; bool &gt; anonymous{InstrProfiling.cpp}::SkipRetExitBlock("skip-ret-exit-block", cl::init(true), cl::desc("Suppress counter promotion if exit blocks contain ret."))</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 173 of file <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/instrumentation/instrprofiling-cpp">InstrProfiling.cpp</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/classes/anonymous-instrprofiling-cpp-/pgocounterpromoter/#aba67c0c1aba6c8fcf674792830b73704">anonymous{InstrProfiling.cpp}::PGOCounterPromoter::run</a>.</p>

</div>
</div>

### SpeculativeCounterPromotionMaxExiting {#a5b3e10c4011211ccbfebcf232115fee3}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">cl::opt&lt; unsigned &gt; anonymous{InstrProfiling.cpp}::SpeculativeCounterPromotionMaxExiting("speculative-counter-promotion-max-exiting", cl::init(3), cl::desc("The max number of exiting blocks of a loop to allow " " speculative counter promotion"))</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 157 of file <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/instrumentation/instrprofiling-cpp">InstrProfiling.cpp</a>.</p>

</div>
</div>

### SpeculativeCounterPromotionToLoop {#a33cfe9b13365aa727a6cbd3323938e20}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">cl::opt&lt; bool &gt; anonymous{InstrProfiling.cpp}::SpeculativeCounterPromotionToLoop("speculative-counter-promotion-to-loop", cl::desc("When the option is false, if the target block is in a loop, " "the promotion will be disallowed unless the promoted counter " " update can be further/iteratively promoted into an acyclic " " region."))</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 162 of file <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/instrumentation/instrprofiling-cpp">InstrProfiling.cpp</a>.</p>

</div>
</div>

### ValueProfileStaticAlloc {#afd8b1cecf4038e6ea20c5feec9353cfd}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">cl::opt&lt; bool &gt; anonymous{InstrProfiling.cpp}::ValueProfileStaticAlloc("vp-static-alloc", cl::desc("Do static counter allocation for value profiler"), cl::init(true))</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 102 of file <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/instrumentation/instrprofiling-cpp">InstrProfiling.cpp</a>.</p>

</div>
</div>

</div>

<hr/>

The documentation for this namespace was generated from the following file:

<ul>
<li><a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/instrumentation/instrprofiling-cpp">InstrProfiling.cpp</a></li>
</ul>

<hr/>

<p class="doxyGeneratedBy">Generated via <a href="https://github.com/xpack/doxygen2docusaurus">doxygen2docusaurus</a> by <a href="https://www.doxygen.nl">Doxygen</a> 1.15.0.</p>

</div>
