---

# DO NOT EDIT!
# Automatically generated via doxygen2docusaurus by Doxygen.

slug: /api/structs/anonymous-partialinlining-cpp-/partialinlinerimpl/functioncloner
custom_edit_url: null
toc_max_heading_level: 4
keywords:
  - doxygen
  - reference
  - struct

---

<div class="doxyPage">

# `FunctionCloner` Struct



## Declaration

<div class="doxyDeclaration">
struct anonymous{PartialInlining.cpp}::PartialInlinerImpl::FunctionCloner { ... }
</div>

## Public Member Typedefs Index

<table class="doxyMembersIndex">

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">typedef</td>
<td class="doxyMemberIndexItemName" align="left" valign="top">std::pair&lt; <a href="/web-llvm/docs/api/classes/llvm/function">Function</a> *, <a href="/web-llvm/docs/api/classes/llvm/basicblock">BasicBlock</a> * &gt; <a href="#a9d220271d49d62a56a6d0467c403b9d5">FuncBodyCallerPair</a></td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a36fe9b66ac821eaf4492b176a50cdffb">FunctionCloner</a> (Function *F, FunctionOutliningInfo *OI, OptimizationRemarkEmitter &amp;ORE, function_ref&lt; AssumptionCache *(Function &amp;)&gt; LookupAC, function_ref&lt; TargetTransformInfo &amp;(Function &amp;)&gt; GetTTI)</td>
</tr>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a4586ab2c09e6ce15f6763c5ff4d5cc24">FunctionCloner</a> (Function *F, FunctionOutliningMultiRegionInfo *OMRI, OptimizationRemarkEmitter &amp;ORE, function_ref&lt; AssumptionCache *(Function &amp;)&gt; LookupAC, function_ref&lt; TargetTransformInfo &amp;(Function &amp;)&gt; GetTTI)</td>
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

## Public Destructor Index

<table class="doxyMembersIndex">

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a517123ae36af5e94fb7e11d66cbb0cf3">~FunctionCloner</a> ()</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a759daba99f9b665ac7274d0dfe70ce09">normalizeReturnBlock</a> () const</td>
</tr>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a61f3d93434dc9f576826799df553ed1b">doMultiRegionFunctionOutlining</a> ()</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/function">Function</a> *</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#aa06ef927da6dbc2b989bb4df7d1f5c6a">doSingleRegionFunctionOutlining</a> ()</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/function">Function</a> *</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a0a1f7bd23a972ea881f335dd9a3cc6ec">OrigFunc</a> = nullptr</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/function">Function</a> *</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a063af39d96ffd4ebc70974c8ed54bc3b">ClonedFunc</a> = nullptr</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/smallvector">SmallVector</a>&lt; <a href="#a9d220271d49d62a56a6d0467c403b9d5">FuncBodyCallerPair</a>, 4 &gt;</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ae47efd5952fcd1822fbf782b111af85b">OutlinedFunctions</a></td>
</tr>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a02aa72e8c0ebde84305b89d162bd1410">IsFunctionInlined</a> = false</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/instructioncost">InstructionCost</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a38e6074cc40daeea36bcb868a4341515">OutlinedRegionCost</a> = 0</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">std::unique_ptr&lt; <a href="/web-llvm/docs/api/structs/anonymous-partialinlining-cpp-/functionoutlininginfo">FunctionOutliningInfo</a> &gt;</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a2125a81ea634a2024c982d0764447f99">ClonedOI</a> = nullptr</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">std::unique_ptr&lt; <a href="/web-llvm/docs/api/structs/anonymous-partialinlining-cpp-/functionoutliningmultiregioninfo">FunctionOutliningMultiRegionInfo</a> &gt;</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#adf7512e1e5309362ebd878b33846ffe4">ClonedOMRI</a> = nullptr</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">std::unique_ptr&lt; <a href="/web-llvm/docs/api/classes/llvm/blockfrequencyinfo">BlockFrequencyInfo</a> &gt;</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a21ca37f2ec000756bb8655f67fafd85b">ClonedFuncBFI</a> = nullptr</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/optimizationremarkemitter">OptimizationRemarkEmitter</a> &amp;</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#af575f312776d952734df819e078d6c30">ORE</a></td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/function-ref">function_ref</a>&lt; <a href="/web-llvm/docs/api/classes/llvm/assumptioncache">AssumptionCache</a> *(<a href="/web-llvm/docs/api/classes/llvm/function">Function</a> &amp;)&gt;</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a062f15bc8c95455929db575f434cc1dc">LookupAC</a></td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/function-ref">function_ref</a>&lt; <a href="/web-llvm/docs/api/classes/llvm/targettransforminfo">TargetTransformInfo</a> &amp;(<a href="/web-llvm/docs/api/classes/llvm/function">Function</a> &amp;)&gt;</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a7ce80459da474ce252c1cf540ce7ecdb">GetTTI</a></td>
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


<p>Definition at line 212 of file <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/ipo/partialinlining-cpp">PartialInlining.cpp</a>.</p>


<div class="doxySectionDef">

## Public Member Typedefs

### FuncBodyCallerPair {#a9d220271d49d62a56a6d0467c403b9d5}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">typedef std::pair&lt;Function *, BasicBlock *&gt; anonymous{PartialInlining.cpp}::PartialInlinerImpl::FunctionCloner::FuncBodyCallerPair</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 244 of file <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/ipo/partialinlining-cpp">PartialInlining.cpp</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Public Constructors

### FunctionCloner() {#a36fe9b66ac821eaf4492b176a50cdffb}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">PartialInlinerImpl::FunctionCloner::FunctionCloner (<a href="/web-llvm/docs/api/classes/llvm/function">Function</a> * F, <a href="/web-llvm/docs/api/structs/anonymous-partialinlining-cpp-/functionoutlininginfo">FunctionOutliningInfo</a> * OI, <a href="/web-llvm/docs/api/classes/llvm/optimizationremarkemitter">OptimizationRemarkEmitter</a> &amp; ORE, <a href="/web-llvm/docs/api/classes/llvm/function-ref">function_ref</a>&lt; <a href="/web-llvm/docs/api/classes/llvm/assumptioncache">AssumptionCache</a> *(<a href="/web-llvm/docs/api/classes/llvm/function">Function</a> &amp;)&gt; LookupAC, <a href="/web-llvm/docs/api/classes/llvm/function-ref">function_ref</a>&lt; <a href="/web-llvm/docs/api/classes/llvm/targettransforminfo">TargetTransformInfo</a> &amp;(<a href="/web-llvm/docs/api/classes/llvm/function">Function</a> &amp;)&gt; GetTTI)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 215 of file <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/ipo/partialinlining-cpp">PartialInlining.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/namespaces/llvm/#ac4fc845f5ed92de63cd4474f128f5fc5">llvm::cast</a>, <a href="#a063af39d96ffd4ebc70974c8ed54bc3b">ClonedFunc</a>, <a href="#a2125a81ea634a2024c982d0764447f99">ClonedOI</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#aedeb89fa4ceb608d9d49bcd53ddcd2c1">llvm::CloneFunction</a>, <a href="/web-llvm/docs/api/structs/anonymous-partialinlining-cpp-/functionoutlininginfo/#a6a053ec8c25e8a04257b8a55ea52116e">anonymous{PartialInlining.cpp}::FunctionOutliningInfo::Entries</a>, <a href="/web-llvm/docs/api/files/lib/lib/support/md5-cpp/#a96d73bbd7af15cb1fc38c3f4a3bd82e9">F</a>, <a href="#a7ce80459da474ce252c1cf540ce7ecdb">GetTTI</a>, <a href="#a062f15bc8c95455929db575f434cc1dc">LookupAC</a>, <a href="/web-llvm/docs/api/structs/anonymous-partialinlining-cpp-/functionoutlininginfo/#a305456eb9eeef128076457cf801016d1">anonymous{PartialInlining.cpp}::FunctionOutliningInfo::NonReturnBlock</a>, <a href="#af575f312776d952734df819e078d6c30">ORE</a>, <a href="#a0a1f7bd23a972ea881f335dd9a3cc6ec">OrigFunc</a>, <a href="/web-llvm/docs/api/structs/anonymous-partialinlining-cpp-/functionoutlininginfo/#a6a5879becbc5af6475bd1cd3c1047eef">anonymous{PartialInlining.cpp}::FunctionOutliningInfo::ReturnBlock</a> and <a href="/web-llvm/docs/api/structs/anonymous-partialinlining-cpp-/functionoutlininginfo/#aa4b6b4d3f209fa1a9ef63ad7441cb1e9">anonymous{PartialInlining.cpp}::FunctionOutliningInfo::ReturnBlockPreds</a>.</p>

</div>
</div>

### FunctionCloner() {#a4586ab2c09e6ce15f6763c5ff4d5cc24}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">PartialInlinerImpl::FunctionCloner::FunctionCloner (<a href="/web-llvm/docs/api/classes/llvm/function">Function</a> * F, <a href="/web-llvm/docs/api/structs/anonymous-partialinlining-cpp-/functionoutliningmultiregioninfo">FunctionOutliningMultiRegionInfo</a> * OMRI, <a href="/web-llvm/docs/api/classes/llvm/optimizationremarkemitter">OptimizationRemarkEmitter</a> &amp; ORE, <a href="/web-llvm/docs/api/classes/llvm/function-ref">function_ref</a>&lt; <a href="/web-llvm/docs/api/classes/llvm/assumptioncache">AssumptionCache</a> *(<a href="/web-llvm/docs/api/classes/llvm/function">Function</a> &amp;)&gt; LookupAC, <a href="/web-llvm/docs/api/classes/llvm/function-ref">function_ref</a>&lt; <a href="/web-llvm/docs/api/classes/llvm/targettransforminfo">TargetTransformInfo</a> &amp;(<a href="/web-llvm/docs/api/classes/llvm/function">Function</a> &amp;)&gt; GetTTI)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 219 of file <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/ipo/partialinlining-cpp">PartialInlining.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/namespaces/llvm/#ac4fc845f5ed92de63cd4474f128f5fc5">llvm::cast</a>, <a href="#a063af39d96ffd4ebc70974c8ed54bc3b">ClonedFunc</a>, <a href="#adf7512e1e5309362ebd878b33846ffe4">ClonedOMRI</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#aedeb89fa4ceb608d9d49bcd53ddcd2c1">llvm::CloneFunction</a>, <a href="/web-llvm/docs/api/files/lib/lib/support/md5-cpp/#a96d73bbd7af15cb1fc38c3f4a3bd82e9">F</a>, <a href="#a7ce80459da474ce252c1cf540ce7ecdb">GetTTI</a>, <a href="#a062f15bc8c95455929db575f434cc1dc">LookupAC</a>, <a href="#af575f312776d952734df819e078d6c30">ORE</a>, <a href="/web-llvm/docs/api/structs/anonymous-partialinlining-cpp-/functionoutliningmultiregioninfo/#aff0046f26a3a57028c20e44f7f93fbab">anonymous{PartialInlining.cpp}::FunctionOutliningMultiRegionInfo::ORI</a> and <a href="#a0a1f7bd23a972ea881f335dd9a3cc6ec">OrigFunc</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Public Destructor

### \~FunctionCloner() {#a517123ae36af5e94fb7e11d66cbb0cf3}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">PartialInlinerImpl::FunctionCloner::~FunctionCloner ()</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 224 of file <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/ipo/partialinlining-cpp">PartialInlining.cpp</a>.</p>


<p>References <a href="#a063af39d96ffd4ebc70974c8ed54bc3b">ClonedFunc</a>, <a href="#a02aa72e8c0ebde84305b89d162bd1410">IsFunctionInlined</a>, <a href="#a0a1f7bd23a972ea881f335dd9a3cc6ec">OrigFunc</a> and <a href="#ae47efd5952fcd1822fbf782b111af85b">OutlinedFunctions</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Public Member Functions

### doMultiRegionFunctionOutlining() {#a61f3d93434dc9f576826799df553ed1b}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool PartialInlinerImpl::FunctionCloner::doMultiRegionFunctionOutlining ()</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 232 of file <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/ipo/partialinlining-cpp">PartialInlining.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/silowercontrolflow-cpp/#a4868c5d81c5ccc98c47aeab6244346a0">assert</a>, <a href="#a063af39d96ffd4ebc70974c8ed54bc3b">ClonedFunc</a>, <a href="#a21ca37f2ec000756bb8655f67fafd85b">ClonedFuncBFI</a>, <a href="#adf7512e1e5309362ebd878b33846ffe4">ClonedOMRI</a>, <a href="/web-llvm/docs/api/namespaces/llvm/callingconv/#ac6aa1387c4375260e2468eb5a77fdb4ca94ec9273479164e4aec1d5d91b71dc85">llvm::CallingConv::Cold</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a7c46c742c31be54870e2038048e6b391">llvm::dbgs</a>, <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/adt/genericcycleimpl-h/#ad78e062f62e0d6e453941fb4ca843e4d">DEBUG_TYPE</a>, <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/ipo/partialinlining-cpp/#aedd5bae59fecc6f8c340763d4bb226fd">ForceLiveExit</a>, <a href="/web-llvm/docs/api/classes/llvm/basicblock/#a80069e261aca5e34cffcc2ef67cfa29b">llvm::BasicBlock::getParent</a>, <a href="/web-llvm/docs/api/classes/llvm/ilist-detail/node-parent-access/#a7e19e7508415378ad9523e0339b23e22">llvm::ilist_detail::node_parent_access&lt; NodeTy, ParentTy &gt;::getParent</a>, <a href="#a7ce80459da474ce252c1cf540ce7ecdb">GetTTI</a>, <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/support/debug-h/#a196897517069dda1bdb549e24468f7d7">LLVM_DEBUG</a>, <a href="#a062f15bc8c95455929db575f434cc1dc">LookupAC</a>, <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/ipo/partialinlining-cpp/#a2885a9c4f28f179095493c5467797f97">MarkOutlinedColdCC</a>, <a href="#af575f312776d952734df819e078d6c30">ORE</a>, <a href="#ae47efd5952fcd1822fbf782b111af85b">OutlinedFunctions</a>, <a href="#a38e6074cc40daeea36bcb868a4341515">OutlinedRegionCost</a>, <a href="/web-llvm/docs/api/classes/llvm/dominatortreebase/#aa0641ae965656ff9988d67a35140e4d9">llvm::DominatorTreeBase&lt; NodeT, IsPostDom &gt;::recalculate</a>, <a href="/web-llvm/docs/api/classes/llvm/callbase/#a0851b4de29686e9c3918449b054cfada">llvm::CallBase::setCallingConv</a>, <a href="/web-llvm/docs/api/classes/llvm/function/#ae6db8746934e6feae3649a8709fce3cc">llvm::Function::setCallingConv</a> and <a href="/web-llvm/docs/api/classes/llvm/setvector/#a1a42c1ba878bd637f374197d05f0a97f">llvm::SetVector&lt; T, Vector, Set, N &gt;::size</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/structs/anonymous-partialinlining-cpp-/partialinlinerimpl/#a1fa6fb3707c37fd9468795bc04580f5d">anonymous{PartialInlining.cpp}::PartialInlinerImpl::unswitchFunction</a>.</p>

</div>
</div>

### doSingleRegionFunctionOutlining() {#aa06ef927da6dbc2b989bb4df7d1f5c6a}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">Function * PartialInlinerImpl::FunctionCloner::doSingleRegionFunctionOutlining ()</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 239 of file <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/ipo/partialinlining-cpp">PartialInlining.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/silowercontrolflow-cpp/#a4868c5d81c5ccc98c47aeab6244346a0">assert</a>, <a href="#a063af39d96ffd4ebc70974c8ed54bc3b">ClonedFunc</a>, <a href="#a21ca37f2ec000756bb8655f67fafd85b">ClonedFuncBFI</a>, <a href="#a2125a81ea634a2024c982d0764447f99">ClonedOI</a>, <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/adt/genericcycleimpl-h/#ad78e062f62e0d6e453941fb4ca843e4d">DEBUG_TYPE</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#ad6e19a09aeed4c56617c284e099c81de">llvm::depth_first</a>, <a href="/web-llvm/docs/api/classes/llvm/codeextractor/#a8561c48aa0b397c37f9e071dad7df392">llvm::CodeExtractor::extractCodeRegion</a>, <a href="/web-llvm/docs/api/classes/llvm/basicblock/#a80069e261aca5e34cffcc2ef67cfa29b">llvm::BasicBlock::getParent</a>, <a href="#a7ce80459da474ce252c1cf540ce7ecdb">GetTTI</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#acd1cd968cb420c82d70926920fcdc7d7">llvm::is_contained</a>, <a href="#a062f15bc8c95455929db575f434cc1dc">LookupAC</a>, <a href="#af575f312776d952734df819e078d6c30">ORE</a>, <a href="#ae47efd5952fcd1822fbf782b111af85b">OutlinedFunctions</a>, <a href="#a38e6074cc40daeea36bcb868a4341515">OutlinedRegionCost</a> and <a href="/web-llvm/docs/api/classes/llvm/dominatortreebase/#aa0641ae965656ff9988d67a35140e4d9">llvm::DominatorTreeBase&lt; NodeT, IsPostDom &gt;::recalculate</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/structs/anonymous-partialinlining-cpp-/partialinlinerimpl/#a1fa6fb3707c37fd9468795bc04580f5d">anonymous{PartialInlining.cpp}::PartialInlinerImpl::unswitchFunction</a>.</p>

</div>
</div>

### normalizeReturnBlock() {#a759daba99f9b665ac7274d0dfe70ce09}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void PartialInlinerImpl::FunctionCloner::normalizeReturnBlock ()</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 229 of file <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/ipo/partialinlining-cpp">PartialInlining.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/classes/llvm/phinode/#a089cccb6f231efee72abc76d0f9c695f">llvm::PHINode::addIncoming</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#ad78da75bd1f157e72100f97d1ecdc756">llvm::all_equal</a>, <a href="/web-llvm/docs/api/classes/llvm/basicblock/#a0ed5f3ab3c2e4196ee0cffffa080c062">llvm::BasicBlock::begin</a>, <a href="#a2125a81ea634a2024c982d0764447f99">ClonedOI</a>, <a href="/web-llvm/docs/api/classes/llvm/phinode/#af4aba918a76ca15bde1be3e14572e475">llvm::PHINode::Create</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a22eeee01734061ac1b31ccd994c49eef">llvm::dyn_cast</a>, <a href="/web-llvm/docs/api/classes/llvm/basicblock/#a0b4e7bee9b8575cc7db73329f1a561bd">llvm::BasicBlock::end</a>, <a href="/web-llvm/docs/api/classes/llvm/phinode/#ab2db7609ec72b1af2f91d47e40dc3722">llvm::PHINode::getIncomingValueForBlock</a>, <a href="/web-llvm/docs/api/classes/llvm/phinode/#aef51af4b490af6b3bf2dfbc8737a8f9f">llvm::PHINode::getNumIncomingValues</a>, <a href="/web-llvm/docs/api/classes/llvm/value/#a0344a49526443edf90cc0aef3abd3337">llvm::Value::getType</a>, <a href="/web-llvm/docs/api/files/lib/lib/support/md5-cpp/#ac0eafdc9ee161b71e7af98af736952fd">I</a>, <a href="/web-llvm/docs/api/classes/llvm/instruction/#a482498a1c760122fd33c7fc8190dd277">llvm::Instruction::insertBefore</a>, <a href="/web-llvm/docs/api/classes/llvm/smallvectortemplatebase/#af42bfbc067df27c19ee2fc859df58799">llvm::SmallVectorTemplateBase&lt; T, bool &gt;::push_back</a>, <a href="/web-llvm/docs/api/classes/llvm/phinode/#a6f01dbe965b38186b1a78378689d4105">llvm::PHINode::removeIncomingValue</a> and <a href="/web-llvm/docs/api/classes/llvm/value/#a3ab5fc45117b450e8bb04e564cb6e5f2">llvm::Value::replaceAllUsesWith</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/structs/anonymous-partialinlining-cpp-/partialinlinerimpl/#a1fa6fb3707c37fd9468795bc04580f5d">anonymous{PartialInlining.cpp}::PartialInlinerImpl::unswitchFunction</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Public Member Attributes

### ClonedFunc {#a063af39d96ffd4ebc70974c8ed54bc3b}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">Function* anonymous{PartialInlining.cpp}::PartialInlinerImpl::FunctionCloner::ClonedFunc = nullptr</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 242 of file <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/ipo/partialinlining-cpp">PartialInlining.cpp</a>.</p>


<p>Referenced by <a href="#a61f3d93434dc9f576826799df553ed1b">doMultiRegionFunctionOutlining</a>, <a href="#aa06ef927da6dbc2b989bb4df7d1f5c6a">doSingleRegionFunctionOutlining</a>, <a href="#a36fe9b66ac821eaf4492b176a50cdffb">FunctionCloner</a>, <a href="#a4586ab2c09e6ce15f6763c5ff4d5cc24">FunctionCloner</a>, <a href="/web-llvm/docs/api/structs/anonymous-partialinlining-cpp-/partialinlinerimpl/#a1fa6fb3707c37fd9468795bc04580f5d">anonymous{PartialInlining.cpp}::PartialInlinerImpl::unswitchFunction</a> and <a href="#a517123ae36af5e94fb7e11d66cbb0cf3">~FunctionCloner</a>.</p>

</div>
</div>

### ClonedFuncBFI {#a21ca37f2ec000756bb8655f67fafd85b}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">std::unique_ptr&lt;BlockFrequencyInfo&gt; anonymous{PartialInlining.cpp}::PartialInlinerImpl::FunctionCloner::ClonedFuncBFI = nullptr</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 257 of file <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/ipo/partialinlining-cpp">PartialInlining.cpp</a>.</p>


<p>Referenced by <a href="#a61f3d93434dc9f576826799df553ed1b">doMultiRegionFunctionOutlining</a> and <a href="#aa06ef927da6dbc2b989bb4df7d1f5c6a">doSingleRegionFunctionOutlining</a>.</p>

</div>
</div>

### ClonedOI {#a2125a81ea634a2024c982d0764447f99}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">std::unique_ptr&lt;FunctionOutliningInfo&gt; anonymous{PartialInlining.cpp}::PartialInlinerImpl::FunctionCloner::ClonedOI = nullptr</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 254 of file <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/ipo/partialinlining-cpp">PartialInlining.cpp</a>.</p>


<p>Referenced by <a href="#aa06ef927da6dbc2b989bb4df7d1f5c6a">doSingleRegionFunctionOutlining</a>, <a href="#a36fe9b66ac821eaf4492b176a50cdffb">FunctionCloner</a> and <a href="#a759daba99f9b665ac7274d0dfe70ce09">normalizeReturnBlock</a>.</p>

</div>
</div>

### ClonedOMRI {#adf7512e1e5309362ebd878b33846ffe4}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">std::unique_ptr&lt;FunctionOutliningMultiRegionInfo&gt; anonymous{PartialInlining.cpp}::PartialInlinerImpl::FunctionCloner::ClonedOMRI = nullptr</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 256 of file <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/ipo/partialinlining-cpp">PartialInlining.cpp</a>.</p>


<p>Referenced by <a href="#a61f3d93434dc9f576826799df553ed1b">doMultiRegionFunctionOutlining</a> and <a href="#a4586ab2c09e6ce15f6763c5ff4d5cc24">FunctionCloner</a>.</p>

</div>
</div>

### GetTTI {#a7ce80459da474ce252c1cf540ce7ecdb}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">function_ref&lt;TargetTransformInfo &amp;(Function &amp;)&gt; anonymous{PartialInlining.cpp}::PartialInlinerImpl::FunctionCloner::GetTTI</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 260 of file <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/ipo/partialinlining-cpp">PartialInlining.cpp</a>.</p>


<p>Referenced by <a href="#a61f3d93434dc9f576826799df553ed1b">doMultiRegionFunctionOutlining</a>, <a href="#aa06ef927da6dbc2b989bb4df7d1f5c6a">doSingleRegionFunctionOutlining</a>, <a href="#a36fe9b66ac821eaf4492b176a50cdffb">FunctionCloner</a> and <a href="#a4586ab2c09e6ce15f6763c5ff4d5cc24">FunctionCloner</a>.</p>

</div>
</div>

### IsFunctionInlined {#a02aa72e8c0ebde84305b89d162bd1410}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool anonymous{PartialInlining.cpp}::PartialInlinerImpl::FunctionCloner::IsFunctionInlined = false</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 250 of file <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/ipo/partialinlining-cpp">PartialInlining.cpp</a>.</p>


<p>Referenced by <a href="#a517123ae36af5e94fb7e11d66cbb0cf3">~FunctionCloner</a>.</p>

</div>
</div>

### LookupAC {#a062f15bc8c95455929db575f434cc1dc}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">function_ref&lt;AssumptionCache *(Function &amp;)&gt; anonymous{PartialInlining.cpp}::PartialInlinerImpl::FunctionCloner::LookupAC</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 259 of file <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/ipo/partialinlining-cpp">PartialInlining.cpp</a>.</p>


<p>Referenced by <a href="#a61f3d93434dc9f576826799df553ed1b">doMultiRegionFunctionOutlining</a>, <a href="#aa06ef927da6dbc2b989bb4df7d1f5c6a">doSingleRegionFunctionOutlining</a>, <a href="#a36fe9b66ac821eaf4492b176a50cdffb">FunctionCloner</a> and <a href="#a4586ab2c09e6ce15f6763c5ff4d5cc24">FunctionCloner</a>.</p>

</div>
</div>

### ORE {#af575f312776d952734df819e078d6c30}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">OptimizationRemarkEmitter&amp; anonymous{PartialInlining.cpp}::PartialInlinerImpl::FunctionCloner::ORE</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 258 of file <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/ipo/partialinlining-cpp">PartialInlining.cpp</a>.</p>


<p>Referenced by <a href="#a61f3d93434dc9f576826799df553ed1b">doMultiRegionFunctionOutlining</a>, <a href="#aa06ef927da6dbc2b989bb4df7d1f5c6a">doSingleRegionFunctionOutlining</a>, <a href="#a36fe9b66ac821eaf4492b176a50cdffb">FunctionCloner</a> and <a href="#a4586ab2c09e6ce15f6763c5ff4d5cc24">FunctionCloner</a>.</p>

</div>
</div>

### OrigFunc {#a0a1f7bd23a972ea881f335dd9a3cc6ec}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">Function* anonymous{PartialInlining.cpp}::PartialInlinerImpl::FunctionCloner::OrigFunc = nullptr</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 241 of file <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/ipo/partialinlining-cpp">PartialInlining.cpp</a>.</p>


<p>Referenced by <a href="#a36fe9b66ac821eaf4492b176a50cdffb">FunctionCloner</a>, <a href="#a4586ab2c09e6ce15f6763c5ff4d5cc24">FunctionCloner</a> and <a href="#a517123ae36af5e94fb7e11d66cbb0cf3">~FunctionCloner</a>.</p>

</div>
</div>

### OutlinedFunctions {#ae47efd5952fcd1822fbf782b111af85b}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">SmallVector&lt;FuncBodyCallerPair, 4&gt; anonymous{PartialInlining.cpp}::PartialInlinerImpl::FunctionCloner::OutlinedFunctions</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 246 of file <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/ipo/partialinlining-cpp">PartialInlining.cpp</a>.</p>


<p>Referenced by <a href="#a61f3d93434dc9f576826799df553ed1b">doMultiRegionFunctionOutlining</a>, <a href="#aa06ef927da6dbc2b989bb4df7d1f5c6a">doSingleRegionFunctionOutlining</a> and <a href="#a517123ae36af5e94fb7e11d66cbb0cf3">~FunctionCloner</a>.</p>

</div>
</div>

### OutlinedRegionCost {#a38e6074cc40daeea36bcb868a4341515}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">InstructionCost anonymous{PartialInlining.cpp}::PartialInlinerImpl::FunctionCloner::OutlinedRegionCost = 0</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 252 of file <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/ipo/partialinlining-cpp">PartialInlining.cpp</a>.</p>


<p>Referenced by <a href="#a61f3d93434dc9f576826799df553ed1b">doMultiRegionFunctionOutlining</a> and <a href="#aa06ef927da6dbc2b989bb4df7d1f5c6a">doSingleRegionFunctionOutlining</a>.</p>

</div>
</div>

</div>

<hr/>

The documentation for this struct was generated from the following file:

<ul>
<li><a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/ipo/partialinlining-cpp">PartialInlining.cpp</a></li>
</ul>

<hr/>

<p class="doxyGeneratedBy">Generated via <a href="https://github.com/xpack/doxygen2docusaurus">doxygen2docusaurus</a> by <a href="https://www.doxygen.nl">Doxygen</a> 1.15.0.</p>

</div>
