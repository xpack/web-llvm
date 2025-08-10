---

# DO NOT EDIT!
# Automatically generated via doxygen2docusaurus by Doxygen.

slug: /api/files/lib/lib/analysis/lazycallgraph-cpp
custom_edit_url: null
toc_max_heading_level: 4
keywords:
  - doxygen
  - reference
  - file

---

<div class="doxyPage">

# `LazyCallGraph.cpp` File



## Included Headers

<div class="doxyIncludesList">#include "<a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/analysis/lazycallgraph-h">llvm/Analysis/LazyCallGraph.h</a>"
#include "<a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/adt/arrayref-h">llvm/ADT/ArrayRef.h</a>"
#include "<a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/adt/stlextras-h">llvm/ADT/STLExtras.h</a>"
#include "<a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/adt/sequence-h">llvm/ADT/Sequence.h</a>"
#include "<a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/adt/smallptrset-h">llvm/ADT/SmallPtrSet.h</a>"
#include "<a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/adt/smallvector-h">llvm/ADT/SmallVector.h</a>"
#include "<a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/adt/iterator-range-h">llvm/ADT/iterator_range.h</a>"
#include "<a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/analysis/targetlibraryinfo-h">llvm/Analysis/TargetLibraryInfo.h</a>"
#include "<a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/ir/constants-h">llvm/IR/Constants.h</a>"
#include "<a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/ir/function-h">llvm/IR/Function.h</a>"
#include "<a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/ir/globalvariable-h">llvm/IR/GlobalVariable.h</a>"
#include "<a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/ir/institerator-h">llvm/IR/InstIterator.h</a>"
#include "<a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/ir/instruction-h">llvm/IR/Instruction.h</a>"
#include "<a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/ir/module-h">llvm/IR/Module.h</a>"
#include "<a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/ir/passmanager-h">llvm/IR/PassManager.h</a>"
#include "<a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/support/casting-h">llvm/Support/Casting.h</a>"
#include "<a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/support/compiler-h">llvm/Support/Compiler.h</a>"
#include "<a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/support/debug-h">llvm/Support/Debug.h</a>"
#include "<a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/support/graphwriter-h">llvm/Support/GraphWriter.h</a>"
#include "<a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/support/raw-ostream-h">llvm/Support/raw_ostream.h</a>"
#include &lt;algorithm&gt;
</div>

## Functions Index

<table class="doxyMembersIndex">

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">static void</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#aec802e48dd5ef69029e285eddfc4158d">addEdge</a> (SmallVectorImpl&lt; LazyCallGraph::Edge &gt; &amp;Edges, DenseMap&lt; LazyCallGraph::Node *, int &gt; &amp;EdgeIndexMap, LazyCallGraph::Node &amp;N, LazyCallGraph::Edge::Kind EK)</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#af481ee3f81ad12db32ea0df13ec4b0d0">isKnownLibFunction</a> (Function &amp;F, TargetLibraryInfo &amp;TLI)</td>
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
<td class="doxyMemberIndexTemplate" colspan="2"><div>template &lt; ... &gt;</div></td>
</tr>
<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemTypeTemplate" align="left" valign="top">static auto </td>
<td class="doxyMemberIndexItemNameTemplate" align="left" valign="top"><a href="#a88f678a123e3721551a1b867ed4b021c">updatePostorderSequenceForEdgeInsertion</a> (SCCT &amp;SourceSCC, SCCT &amp;TargetSCC, PostorderSequenceT &amp;SCCs, SCCIndexMapT &amp;SCCIndices, ComputeSourceConnectedSetCallableT ComputeSourceConnectedSet, ComputeTargetConnectedSetCallableT ComputeTargetConnectedSet) -&gt; <a href="/web-llvm/docs/api/classes/llvm/iterator-range">iterator_range</a>&lt; typename PostorderSequenceT::iterator &gt;</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Generic helper that updates a postorder sequence of SCCs for a potentially cycle-introducing edge insertion. <a href="#a88f678a123e3721551a1b867ed4b021c">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">static <a href="/web-llvm/docs/api/classes/llvm/lazycallgraph/edge/#a8a5508e6c049172373b05c47c1b6fe13">LazyCallGraph::Edge::Kind</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ad7483d245bba8b6658b4dbd429f14313">getEdgeKind</a> (Function &amp;OriginalFunction, Function &amp;NewFunction)</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a43bfa5ae5bc262dd53cb668fa64764dc">printNode</a> (raw_ostream &amp;OS, LazyCallGraph::Node &amp;N)</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ae48a57dbe703b0863fc96285ac60a9d6">printSCC</a> (raw_ostream &amp;OS, LazyCallGraph::SCC &amp;C)</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a5f3deff80749a0e7a3e4020593dc448f">printRefSCC</a> (raw_ostream &amp;OS, LazyCallGraph::RefSCC &amp;C)</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#aa23cb08728e5bb13e2bf43eb614c3efa">printNodeDOT</a> (raw_ostream &amp;OS, LazyCallGraph::Node &amp;N)</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ad78e062f62e0d6e453941fb4ca843e4d">DEBUG_TYPE</a>&nbsp;&nbsp;&nbsp;"lcg"</td>
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

### addEdge() {#aec802e48dd5ef69029e285eddfc4158d}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void addEdge (<a href="/web-llvm/docs/api/classes/llvm/smallvectorimpl">SmallVectorImpl</a>&lt; <a href="/web-llvm/docs/api/classes/llvm/lazycallgraph/edge">LazyCallGraph::Edge</a> &gt; &amp; Edges, <a href="/web-llvm/docs/api/classes/llvm/densemap">DenseMap</a>&lt; <a href="/web-llvm/docs/api/classes/llvm/lazycallgraph/node">LazyCallGraph::Node</a> *, int &gt; &amp; EdgeIndexMap, <a href="/web-llvm/docs/api/classes/llvm/lazycallgraph/node">LazyCallGraph::Node</a> &amp; N, <a href="/web-llvm/docs/api/classes/llvm/lazycallgraph/edge/#a8a5508e6c049172373b05c47c1b6fe13">LazyCallGraph::Edge::Kind</a> EK)</td>
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



<p>Definition at line 62 of file <a href="/web-llvm/docs/api/files/lib/lib/analysis/lazycallgraph-cpp">LazyCallGraph.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/namespaces/llvm/#a7c46c742c31be54870e2038048e6b391">llvm::dbgs</a>, <a href="/web-llvm/docs/api/classes/llvm/smallvectorimpl/#a396fcfee6914c76974b73c3d203da6a5">llvm::SmallVectorImpl&lt; T &gt;::emplace_back</a>, <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/support/debug-h/#a196897517069dda1bdb549e24468f7d7">LLVM_DEBUG</a>, <a href="/web-llvm/docs/api/files/lib/lib/support/regcomp-c/#a0240ac851181b84ac374872dc5434ee4">N</a>, <a href="/web-llvm/docs/api/classes/llvm/smallvectortemplatecommon/#a1c479a8c434377c2b8cb056bdfdfc201">llvm::SmallVectorTemplateCommon&lt; T, typename &gt;::size</a> and <a href="/web-llvm/docs/api/classes/llvm/densemapbase/#a1a245b31aced1374f28f45d2b297f402">llvm::DenseMapBase&lt; DerivedT, KeyT, ValueT, KeyInfoT, BucketT &gt;::try_emplace</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/classes/anonymous-sampleprofileinference-cpp-/mincostmaxflow/#af5911bffb6d89dea9124aec1644932c4">anonymous{SampleProfileInference.cpp}::MinCostMaxFlow::addEdge</a> and <a href="/web-llvm/docs/api/classes/llvm/lazycallgraph/#a58d534b072f7d0fa5f54ff569bb745ec">llvm::LazyCallGraph::LazyCallGraph</a>.</p>

</div>
</div>

### getEdgeKind() {#ad7483d245bba8b6658b4dbd429f14313}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">LazyCallGraph::Edge::Kind getEdgeKind (<a href="/web-llvm/docs/api/classes/llvm/function">Function</a> &amp; OriginalFunction, <a href="/web-llvm/docs/api/classes/llvm/function">Function</a> &amp; NewFunction)</td>
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



<p>Definition at line 1582 of file <a href="/web-llvm/docs/api/files/lib/lib/analysis/lazycallgraph-cpp">LazyCallGraph.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/silowercontrolflow-cpp/#a4868c5d81c5ccc98c47aeab6244346a0">assert</a>, <a href="/web-llvm/docs/api/namespaces/llvm/callingconv/#ac6aa1387c4375260e2468eb5a77fdb4cafd841a49aec1539bc88abc8ff9e170fb">llvm::CallingConv::C</a>, <a href="/web-llvm/docs/api/classes/llvm/lazycallgraph/edge/#a8a5508e6c049172373b05c47c1b6fe13a13b74fdca959e0c5da734f789b298cf6">llvm::LazyCallGraph::Edge::Call</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a22eeee01734061ac1b31ccd994c49eef">llvm::dyn_cast</a>, <a href="/web-llvm/docs/api/files/lib/lib/support/md5-cpp/#a96d73bbd7af15cb1fc38c3f4a3bd82e9">F</a>, <a href="/web-llvm/docs/api/files/lib/lib/support/md5-cpp/#ac0eafdc9ee161b71e7af98af736952fd">I</a>, <a href="/web-llvm/docs/api/classes/llvm/smallptrsetimpl/#a9d834ae3da8c62c2b668dada51335eb0">llvm::SmallPtrSetImpl&lt; PtrType &gt;::insert</a>, <a href="/web-llvm/docs/api/files/lib/lib/codegen/atomicexpandpass-cpp/#a1bcc06b1cb86bd0ea08f33323190bdaa">instructions</a>, <a href="/web-llvm/docs/api/classes/llvm/smallvectortemplatebase/#af42bfbc067df27c19ee2fc859df58799">llvm::SmallVectorTemplateBase&lt; T, bool &gt;::push_back</a>, <a href="/web-llvm/docs/api/classes/llvm/lazycallgraph/edge/#a8a5508e6c049172373b05c47c1b6fe13a81845d1d6d0f58deb757fad1e739c32c">llvm::LazyCallGraph::Edge::Ref</a> and <a href="/web-llvm/docs/api/classes/llvm/lazycallgraph/#a778d0494c2f8dec95d60160b1ce89a07">llvm::LazyCallGraph::visitReferences</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/classes/llvm/lazycallgraph/#a8d76834516af3608993c2add103b3a6f">llvm::LazyCallGraph::addSplitFunction</a> and <a href="/web-llvm/docs/api/classes/llvm/lazycallgraph/#a952c8adfe8553406e169b98200072a69">llvm::LazyCallGraph::addSplitRefRecursiveFunctions</a>.</p>

</div>
</div>

### isKnownLibFunction() {#af481ee3f81ad12db32ea0df13ec4b0d0}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool isKnownLibFunction (<a href="/web-llvm/docs/api/classes/llvm/function">Function</a> &amp; F, <a href="/web-llvm/docs/api/classes/llvm/targetlibraryinfo">TargetLibraryInfo</a> &amp; TLI)</td>
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



<p>Definition at line 146 of file <a href="/web-llvm/docs/api/files/lib/lib/analysis/lazycallgraph-cpp">LazyCallGraph.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/files/lib/lib/support/md5-cpp/#a96d73bbd7af15cb1fc38c3f4a3bd82e9">F</a>, <a href="/web-llvm/docs/api/classes/llvm/targetlibraryinfo/#a97cfbbed8869e3582142012a071a9052">llvm::TargetLibraryInfo::getLibFunc</a> and <a href="/web-llvm/docs/api/classes/llvm/targetlibraryinfo/#a509a54a541f436c80708c727d0b4d1b3">llvm::TargetLibraryInfo::isKnownVectorFunctionInLibrary</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/classes/llvm/lazycallgraph/#a58d534b072f7d0fa5f54ff569bb745ec">llvm::LazyCallGraph::LazyCallGraph</a> and <a href="/web-llvm/docs/api/classes/llvm/moduleinlinerpass/#ab7155781c9a6aafef322de28d9bc4c86">llvm::ModuleInlinerPass::run</a>.</p>

</div>
</div>

### printNode() {#a43bfa5ae5bc262dd53cb668fa64764dc}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void printNode (<a href="/web-llvm/docs/api/classes/llvm/raw-ostream">raw_ostream</a> &amp; OS, <a href="/web-llvm/docs/api/classes/llvm/lazycallgraph/node">LazyCallGraph::Node</a> &amp; N)</td>
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



<p>Definition at line 2000 of file <a href="/web-llvm/docs/api/files/lib/lib/analysis/lazycallgraph-cpp">LazyCallGraph.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/files/lib/lib/ir/builtingcs-cpp/#abb2b3a60ccc38a28239e19a1646e0c8a">E</a> and <a href="/web-llvm/docs/api/files/lib/lib/support/regcomp-c/#a0240ac851181b84ac374872dc5434ee4">N</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/structs/llvm/itaniumpartialdemangler/#a735b9eda5aeca00a01465c6fddd48c72">llvm::ItaniumPartialDemangler::finishDemangle</a>, <a href="/web-llvm/docs/api/structs/llvm/itaniumpartialdemangler/#a2effd15853bfffbeec4d08451f1fa81c">llvm::ItaniumPartialDemangler::getFunctionBaseName</a>, <a href="/web-llvm/docs/api/structs/llvm/itaniumpartialdemangler/#a483d97b0a650319638b62209a03b1dea">llvm::ItaniumPartialDemangler::getFunctionName</a> and <a href="/web-llvm/docs/api/classes/llvm/lazycallgraphprinterpass/#a2860c75599e4f96204b58e3c3be96dfe">llvm::LazyCallGraphPrinterPass::run</a>.</p>

</div>
</div>

### printNodeDOT() {#aa23cb08728e5bb13e2bf43eb614c3efa}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void printNodeDOT (<a href="/web-llvm/docs/api/classes/llvm/raw-ostream">raw_ostream</a> &amp; OS, <a href="/web-llvm/docs/api/classes/llvm/lazycallgraph/node">LazyCallGraph::Node</a> &amp; N)</td>
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



<p>Definition at line 2045 of file <a href="/web-llvm/docs/api/files/lib/lib/analysis/lazycallgraph-cpp">LazyCallGraph.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/files/lib/lib/ir/builtingcs-cpp/#abb2b3a60ccc38a28239e19a1646e0c8a">E</a>, <a href="/web-llvm/docs/api/namespaces/llvm/dot/#a4cab6453a8243573f35f162cd94f33ba">llvm::DOT::EscapeString</a> and <a href="/web-llvm/docs/api/files/lib/lib/support/regcomp-c/#a0240ac851181b84ac374872dc5434ee4">N</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/classes/llvm/lazycallgraphdotprinterpass/#a172985546be95f992c665ac5d82e4a08">llvm::LazyCallGraphDOTPrinterPass::run</a>.</p>

</div>
</div>

### printRefSCC() {#a5f3deff80749a0e7a3e4020593dc448f}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void printRefSCC (<a href="/web-llvm/docs/api/classes/llvm/raw-ostream">raw_ostream</a> &amp; OS, <a href="/web-llvm/docs/api/classes/llvm/lazycallgraph/refscc">LazyCallGraph::RefSCC</a> &amp; C)</td>
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



<p>Definition at line 2016 of file <a href="/web-llvm/docs/api/files/lib/lib/analysis/lazycallgraph-cpp">LazyCallGraph.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/namespaces/llvm/callingconv/#ac6aa1387c4375260e2468eb5a77fdb4cafd841a49aec1539bc88abc8ff9e170fb">llvm::CallingConv::C</a> and <a href="#ae48a57dbe703b0863fc96285ac60a9d6">printSCC</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/classes/llvm/lazycallgraphprinterpass/#a2860c75599e4f96204b58e3c3be96dfe">llvm::LazyCallGraphPrinterPass::run</a>.</p>

</div>
</div>

### printSCC() {#ae48a57dbe703b0863fc96285ac60a9d6}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void printSCC (<a href="/web-llvm/docs/api/classes/llvm/raw-ostream">raw_ostream</a> &amp; OS, <a href="/web-llvm/docs/api/classes/llvm/lazycallgraph/scc">LazyCallGraph::SCC</a> &amp; C)</td>
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



<p>Definition at line 2009 of file <a href="/web-llvm/docs/api/files/lib/lib/analysis/lazycallgraph-cpp">LazyCallGraph.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/namespaces/llvm/callingconv/#ac6aa1387c4375260e2468eb5a77fdb4cafd841a49aec1539bc88abc8ff9e170fb">llvm::CallingConv::C</a> and <a href="/web-llvm/docs/api/files/lib/lib/support/regcomp-c/#a0240ac851181b84ac374872dc5434ee4">N</a>.</p>


<p>Referenced by <a href="#a5f3deff80749a0e7a3e4020593dc448f">printRefSCC</a>.</p>

</div>
</div>

### updatePostorderSequenceForEdgeInsertion() {#a88f678a123e3721551a1b867ed4b021c}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<div class="doxyMemberTemplate">template &lt;typename SCCT, typename PostorderSequenceT, typename SCCIndexMapT, typename ComputeSourceConnectedSetCallableT, typename ComputeTargetConnectedSetCallableT&gt;</div>
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">iterator_range&lt; typename PostorderSequenceT::iterator &gt; updatePostorderSequenceForEdgeInsertion (SCCT &amp; SourceSCC, SCCT &amp; TargetSCC, PostorderSequenceT &amp; SCCs, SCCIndexMapT &amp; SCCIndices, ComputeSourceConnectedSetCallableT ComputeSourceConnectedSet, ComputeTargetConnectedSetCallableT ComputeTargetConnectedSet)</td>
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

<p>Generic helper that updates a postorder sequence of SCCs for a potentially cycle-introducing edge insertion.</p>


<p>A postorder sequence of SCCs of a directed graph has one fundamental property: all deges in the DAG of SCCs point "up" the sequence. That is, all edges in the SCC DAG point to prior SCCs in the sequence.</p>


<p>This routine both updates a postorder sequence and uses that sequence to compute the set of SCCs connected into a cycle. It should only be called to insert a "downward" edge which will require changing the sequence to restore it to a postorder.</p>


<p>When inserting an edge from an earlier SCC to a later SCC in some postorder sequence, all of the SCCs which may be impacted are in the closed range of those two within the postorder sequence. The algorithm used here to restore the state is as follows:</p>


<p>1) Starting from the source SCC, construct a set of SCCs which reach the source SCC consisting of just the source SCC. Then scan toward the target SCC in postorder and for each SCC, if it has an edge to an SCC in the set, add it to the set. Otherwise, the source SCC is not a successor, move it in the postorder sequence to immediately before the source SCC, shifting the source SCC and all SCCs in the set one position toward the target SCC. Stop scanning after processing the target SCC. 2) If the source SCC is now past the target SCC in the postorder sequence, and thus the new edge will flow toward the start, we are done. 3) Otherwise, starting from the target SCC, walk all edges which reach an SCC between the source and the target, and add them to the set of connected SCCs, then recurse through them. Once a complete set of the SCCs the target connects to is known, hoist the remaining SCCs between the source and the target to be above the target. Note that there is no need to process the source SCC, it is already known to connect. 4) At this point, all of the SCCs in the closed range between the source SCC and the target SCC in the postorder sequence are connected, including the target SCC and the source SCC. Inserting the edge from the source SCC to the target SCC will form a cycle out of precisely these SCCs. Thus we can merge all of the SCCs in this closed range into a single SCC.</p>


<p>This process has various important properties:</p>


<ul class="doxyList ">
<li>Only mutates the SCCs when adding the edge actually changes the SCC structure.</li>
<li>Never mutates SCCs which are unaffected by the change.</li>
<li>Updates the postorder sequence to correctly satisfy the postorder constraint after the edge is inserted.</li>
<li>Only reorders SCCs in the closed postorder sequence from the source to the target, so easy to bound how much has changed even in the ordering.</li>
<li>Big-O is the number of edges in the closed postorder range of SCCs from source to target.</li>
</ul>

<p>This helper routine, in addition to updating the postorder sequence itself will also update a map from SCCs to indices within that sequence.</p>


<p>The sequence and the map must operate on pointers to the SCC type.</p>


<p>Two callbacks must be provided. The first computes the subset of SCCs in the postorder closed range from the source to the target which connect to the source SCC via some (transitive) set of edges. The second computes the subset of the same range which the target SCC connects to via some (transitive) set of edges. Both callbacks should populate the set argument provided.</p>


<p>Definition at line 518 of file <a href="/web-llvm/docs/api/files/lib/lib/analysis/lazycallgraph-cpp">LazyCallGraph.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/silowercontrolflow-cpp/#a4868c5d81c5ccc98c47aeab6244346a0">assert</a>, <a href="/web-llvm/docs/api/namespaces/llvm/callingconv/#ac6aa1387c4375260e2468eb5a77fdb4cafd841a49aec1539bc88abc8ff9e170fb">llvm::CallingConv::C</a>, <a href="/web-llvm/docs/api/classes/llvm/smallptrsetimplbase/#a16413f1a88d8baca228d0a1b4cc0bfc6">llvm::SmallPtrSetImplBase::clear</a>, <a href="/web-llvm/docs/api/classes/llvm/smallptrsetimpl/#a1f475b0df44ebd7169e720fa1bf9169e">llvm::SmallPtrSetImpl&lt; PtrType &gt;::count</a>, <a href="/web-llvm/docs/api/files/lib/lib/ir/builtingcs-cpp/#abb2b3a60ccc38a28239e19a1646e0c8a">E</a>, <a href="/web-llvm/docs/api/files/lib/lib/support/md5-cpp/#ac0eafdc9ee161b71e7af98af736952fd">I</a> and <a href="/web-llvm/docs/api/namespaces/llvm/#a341215803e83773a3e97860dc291f121">llvm::make_range</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/classes/llvm/lazycallgraph/refscc/#a01b1581633bb40f86d6dc62a1c1a7f72">llvm::LazyCallGraph::RefSCC::insertIncomingRefEdge</a> and <a href="/web-llvm/docs/api/classes/llvm/lazycallgraph/refscc/#a2957918db7f91f405b11d92c1ebf3b0f">llvm::LazyCallGraph::RefSCC::switchInternalEdgeToCall</a>.</p>

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
<td class="doxyMemberName">#define DEBUG_TYPE&nbsp;&nbsp;&nbsp;"lcg"</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 38 of file <a href="/web-llvm/docs/api/files/lib/lib/analysis/lazycallgraph-cpp">LazyCallGraph.cpp</a>.</p>

</div>
</div>

</div>

<hr/>

<p class="doxyGeneratedBy">Generated via <a href="https://xpack.github.io/doxygen2docusaurus">doxygen2docusaurus</a> 2.0.0 by <a href="https://www.doxygen.nl">Doxygen</a> 1.15.0.</p>

</div>
