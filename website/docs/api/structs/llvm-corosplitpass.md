---

# DO NOT EDIT!
# Automatically generated via doxygen2docusaurus by Doxygen.

slug: /api/structs/llvm/corosplitpass
custom_edit_url: null
toc_max_heading_level: 4
keywords:
  - doxygen
  - reference
  - struct

---

<div class="doxyPage">

# The `CoroSplitPass` Struct Reference



## Declaration

<div class="doxyDeclaration">
struct llvm::CoroSplitPass { ... }
</div>

## Included Headers

<div class="doxyIncludesList">#include "<a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/transforms/include/llvm/transforms/coroutines/corosplit-h">llvm/Transforms/Coroutines/CoroSplit.h</a>"
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

## Public Member Typedefs Index

<table class="doxyMembersIndex">

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">using</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#abaf5427dbf33b7bab2de92c89385a547">BaseABITy</a> = std::function&lt; std::unique_ptr&lt; <a href="/web-llvm/docs/api/classes/llvm/coro/baseabi">coro::BaseABI</a> &gt;(<a href="/web-llvm/docs/api/classes/llvm/function">Function</a> &amp;, <a href="/web-llvm/docs/api/structs/llvm/coro/shape">coro::Shape</a> &amp;)&gt;</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a5f0bac32eb02663f4b3c2cc0adc0b41f">CoroSplitPass</a> (bool OptimizeFrame=false)</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#afa5e75aeef01520a39012a69184b317d">CoroSplitPass</a> (SmallVector&lt; BaseABITy &gt; GenCustomABIs, bool OptimizeFrame=false)</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a076c212743064432c11c29e2ab0d3564">CoroSplitPass</a> (std::function&lt; bool(Instruction &amp;)&gt; MaterializableCallback, bool OptimizeFrame=false)</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a2b8dc4c3114b5872109bd5499f965f00">CoroSplitPass</a> (std::function&lt; bool(Instruction &amp;)&gt; MaterializableCallback, SmallVector&lt; BaseABITy &gt; GenCustomABIs, bool OptimizeFrame=false)</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a47f6589634ad33a13369ace133b9f4b2">run</a> (LazyCallGraph::SCC &amp;C, CGSCCAnalysisManager &amp;AM, LazyCallGraph &amp;CG, CGSCCUpdateResult &amp;UR)</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="#abaf5427dbf33b7bab2de92c89385a547">BaseABITy</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a60948454dbcc254d144bfe52dc320595">CreateAndInitABI</a></td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#acad6a8cfcddc1bd59394c0f2944f306e">OptimizeFrame</a></td>
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

## Public Static Functions Index

<table class="doxyMembersIndex">

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">static bool</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a7c323f9346064eeaf0038d10f32fddec">isRequired</a> ()</td>
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


<p>Definition at line 30 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/transforms/include/llvm/transforms/coroutines/corosplit-h">CoroSplit.h</a>.</p>


<div class="doxySectionDef">

## Public Member Typedefs

### BaseABITy {#abaf5427dbf33b7bab2de92c89385a547}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">using llvm::CoroSplitPass::BaseABITy = 
      std::function&lt;std::unique_ptr&lt;coro::BaseABI&gt;(Function &amp;, coro::Shape &amp;)&gt;</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 31 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/transforms/include/llvm/transforms/coroutines/corosplit-h">CoroSplit.h</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Public Constructors

### CoroSplitPass() {#a5f0bac32eb02663f4b3c2cc0adc0b41f}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">CoroSplitPass::CoroSplitPass (bool OptimizeFrame=false)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Declaration at line 34 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/transforms/include/llvm/transforms/coroutines/corosplit-h">CoroSplit.h</a>, definition at line 2175 of file <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/coroutines/corosplit-cpp">CoroSplit.cpp</a>.</p>


<p>References <a href="#a60948454dbcc254d144bfe52dc320595">CreateAndInitABI</a>, <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/coroutines/corosplit-cpp/#a88fd8d22fd3856c5ed785a7d9f2a736e">CreateNewABI</a>, <a href="/web-llvm/docs/api/files/lib/lib/support/md5-cpp/#a96d73bbd7af15cb1fc38c3f4a3bd82e9">F</a>, <a href="/web-llvm/docs/api/namespaces/llvm/coro/#ad2ae5b6314d4de7db633c2181e707132">llvm::coro::isTriviallyMaterializable</a> and <a href="#acad6a8cfcddc1bd59394c0f2944f306e">OptimizeFrame</a>.</p>

</div>
</div>

### CoroSplitPass() {#afa5e75aeef01520a39012a69184b317d}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">CoroSplitPass::CoroSplitPass (<a href="/web-llvm/docs/api/classes/llvm/smallvector">SmallVector</a>&lt; <a href="#abaf5427dbf33b7bab2de92c89385a547">BaseABITy</a> &gt; GenCustomABIs, bool OptimizeFrame=false)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Declaration at line 36 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/transforms/include/llvm/transforms/coroutines/corosplit-h">CoroSplit.h</a>, definition at line 2184 of file <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/coroutines/corosplit-cpp">CoroSplit.cpp</a>.</p>


<p>References <a href="#a60948454dbcc254d144bfe52dc320595">CreateAndInitABI</a>, <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/coroutines/corosplit-cpp/#a88fd8d22fd3856c5ed785a7d9f2a736e">CreateNewABI</a>, <a href="/web-llvm/docs/api/files/lib/lib/support/md5-cpp/#a96d73bbd7af15cb1fc38c3f4a3bd82e9">F</a>, <a href="/web-llvm/docs/api/namespaces/llvm/coro/#ad2ae5b6314d4de7db633c2181e707132">llvm::coro::isTriviallyMaterializable</a> and <a href="#acad6a8cfcddc1bd59394c0f2944f306e">OptimizeFrame</a>.</p>

</div>
</div>

### CoroSplitPass() {#a076c212743064432c11c29e2ab0d3564}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">CoroSplitPass::CoroSplitPass (std::function&lt; bool(<a href="/web-llvm/docs/api/classes/llvm/instruction">Instruction</a> &amp;)&gt; MaterializableCallback, bool OptimizeFrame=false)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Declaration at line 39 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/transforms/include/llvm/transforms/coroutines/corosplit-h">CoroSplit.h</a>, definition at line 2196 of file <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/coroutines/corosplit-cpp">CoroSplit.cpp</a>.</p>


<p>References <a href="#a60948454dbcc254d144bfe52dc320595">CreateAndInitABI</a>, <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/coroutines/corosplit-cpp/#a88fd8d22fd3856c5ed785a7d9f2a736e">CreateNewABI</a>, <a href="/web-llvm/docs/api/files/lib/lib/support/md5-cpp/#a96d73bbd7af15cb1fc38c3f4a3bd82e9">F</a> and <a href="#acad6a8cfcddc1bd59394c0f2944f306e">OptimizeFrame</a>.</p>

</div>
</div>

### CoroSplitPass() {#a2b8dc4c3114b5872109bd5499f965f00}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">CoroSplitPass::CoroSplitPass (std::function&lt; bool(<a href="/web-llvm/docs/api/classes/llvm/instruction">Instruction</a> &amp;)&gt; MaterializableCallback, <a href="/web-llvm/docs/api/classes/llvm/smallvector">SmallVector</a>&lt; <a href="#abaf5427dbf33b7bab2de92c89385a547">BaseABITy</a> &gt; GenCustomABIs, bool OptimizeFrame=false)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Declaration at line 42 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/transforms/include/llvm/transforms/coroutines/corosplit-h">CoroSplit.h</a>, definition at line 2208 of file <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/coroutines/corosplit-cpp">CoroSplit.cpp</a>.</p>


<p>References <a href="#a60948454dbcc254d144bfe52dc320595">CreateAndInitABI</a>, <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/coroutines/corosplit-cpp/#a88fd8d22fd3856c5ed785a7d9f2a736e">CreateNewABI</a>, <a href="/web-llvm/docs/api/files/lib/lib/support/md5-cpp/#a96d73bbd7af15cb1fc38c3f4a3bd82e9">F</a> and <a href="#acad6a8cfcddc1bd59394c0f2944f306e">OptimizeFrame</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Public Member Functions

### run() {#a47f6589634ad33a13369ace133b9f4b2}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">PreservedAnalyses CoroSplitPass::run (<a href="/web-llvm/docs/api/classes/llvm/lazycallgraph/scc">LazyCallGraph::SCC</a> &amp; C, <a href="/web-llvm/docs/api/namespaces/llvm/#a571b2bbf074b46c75300bd8f14c5ab72">CGSCCAnalysisManager</a> &amp; AM, <a href="/web-llvm/docs/api/classes/llvm/lazycallgraph">LazyCallGraph</a> &amp; CG, <a href="/web-llvm/docs/api/structs/llvm/cgsccupdateresult">CGSCCUpdateResult</a> &amp; UR)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Declaration at line 46 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/transforms/include/llvm/transforms/coroutines/corosplit-h">CoroSplit.h</a>, definition at line 2219 of file <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/coroutines/corosplit-cpp">CoroSplit.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/coroutines/corosplit-cpp/#a68cd8d24134223f2dfaf5f482a56f1fd">addPrepareFunction</a>, <a href="/web-llvm/docs/api/namespaces/llvm/callingconv/#ac6aa1387c4375260e2468eb5a77fdb4cafd841a49aec1539bc88abc8ff9e170fb">llvm::CallingConv::C</a>, <a href="/web-llvm/docs/api/structs/llvm/coro/shape/#abfb56acef5d60fefb2edc417f0bfbda0">llvm::coro::Shape::CoroBegin</a>, <a href="/web-llvm/docs/api/structs/llvm/coro/shape/#a5fd0aa934908c837c6d78097a2fd667b">llvm::coro::Shape::CoroSuspends</a>, <a href="#a60948454dbcc254d144bfe52dc320595">CreateAndInitABI</a>, <a href="/web-llvm/docs/api/structs/llvm/cgsccupdateresult/#a277c9d45b3b20308e166249fd56598ed">llvm::CGSCCUpdateResult::CWorklist</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a7c46c742c31be54870e2038048e6b391">llvm::dbgs</a>, <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/adt/genericcycleimpl-h/#ad78e062f62e0d6e453941fb4ca843e4d">DEBUG_TYPE</a>, <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/coroutines/corosplit-cpp/#a8bf580168c7138b15f7bfdd080416bec">doSplitCoroutine</a>, <a href="/web-llvm/docs/api/classes/llvm/smallvectortemplatecommon/#ad9a3c7bc26b130377bbafc170b5f88a2">llvm::SmallVectorTemplateCommon&lt; T, typename &gt;::empty</a>, <a href="/web-llvm/docs/api/files/lib/lib/support/md5-cpp/#a96d73bbd7af15cb1fc38c3f4a3bd82e9">F</a>, <a href="/web-llvm/docs/api/files/lib/lib/passes/passbuilderbindings-cpp/#a83c7e5ca51099e4efa895791a02fb0ed">FAM</a>, <a href="/web-llvm/docs/api/structs/llvm/coro/shape/#a0a1a8e48ba1e5d845e979d5da8de597d">llvm::coro::Shape::FrameAlign</a>, <a href="/web-llvm/docs/api/structs/llvm/coro/shape/#a742806b2e667a87817ae171e1ec59826">llvm::coro::Shape::FrameSize</a>, <a href="/web-llvm/docs/api/classes/llvm/lazycallgraph/#ad03c103c6345a262195c485df88d2a21">llvm::LazyCallGraph::get</a>, <a href="/web-llvm/docs/api/classes/llvm/analysismanager/#aaab1fad63e4f3b8679469720a873fedd">llvm::AnalysisManager&lt; IRUnitT, ExtraArgTs &gt;::getResult</a>, <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/support/debug-h/#a196897517069dda1bdb549e24468f7d7">LLVM_DEBUG</a>, <a href="/web-llvm/docs/api/classes/llvm/lazycallgraph/#ad234c24f90aaa0fa3f30ac9c750883b6">llvm::LazyCallGraph::lookupSCC</a>, <a href="/web-llvm/docs/api/files/lib/lib/support/regcomp-c/#a0240ac851181b84ac374872dc5434ee4">N</a>, <a href="#acad6a8cfcddc1bd59394c0f2944f306e">OptimizeFrame</a>, <a href="/web-llvm/docs/api/classes/llvm/smallvectortemplatebase/#af42bfbc067df27c19ee2fc859df58799">llvm::SmallVectorTemplateBase&lt; T, bool &gt;::push_back</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#aec88b7682025edff7984c3b6c8da8ac9">llvm::removeUnreachableBlocks</a>, <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/coroutines/corosplit-cpp/#a83664bf5c186d5e2d65853f2cce4ec3a">replaceAllPrepares</a>, <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/coroutines/corosplit-cpp/#a1d6bceebc19a80123ae26670c7645d1a">updateCallGraphAfterCoroutineSplit</a> and <a href="/web-llvm/docs/api/structs/llvm/align/#a80735739b49cf97a491922c8f9af2cc1">llvm::Align::value</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Public Member Attributes

### CreateAndInitABI {#a60948454dbcc254d144bfe52dc320595}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">BaseABITy llvm::CoroSplitPass::CreateAndInitABI</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 52 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/transforms/include/llvm/transforms/coroutines/corosplit-h">CoroSplit.h</a>.</p>


<p>Referenced by <a href="#a5f0bac32eb02663f4b3c2cc0adc0b41f">CoroSplitPass</a>, <a href="#afa5e75aeef01520a39012a69184b317d">CoroSplitPass</a>, <a href="#a076c212743064432c11c29e2ab0d3564">CoroSplitPass</a>, <a href="#a2b8dc4c3114b5872109bd5499f965f00">CoroSplitPass</a> and <a href="#a47f6589634ad33a13369ace133b9f4b2">run</a>.</p>

</div>
</div>

### OptimizeFrame {#acad6a8cfcddc1bd59394c0f2944f306e}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool llvm::CoroSplitPass::OptimizeFrame</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 55 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/transforms/include/llvm/transforms/coroutines/corosplit-h">CoroSplit.h</a>.</p>


<p>Referenced by <a href="#a5f0bac32eb02663f4b3c2cc0adc0b41f">CoroSplitPass</a>, <a href="#afa5e75aeef01520a39012a69184b317d">CoroSplitPass</a>, <a href="#a076c212743064432c11c29e2ab0d3564">CoroSplitPass</a>, <a href="#a2b8dc4c3114b5872109bd5499f965f00">CoroSplitPass</a> and <a href="#a47f6589634ad33a13369ace133b9f4b2">run</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Public Static Functions

### isRequired() {#a7c323f9346064eeaf0038d10f32fddec}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool llvm::CoroSplitPass::isRequired ()</td>
</tr>
</table>
</td>
<td class="doxyMemberLabelsRight">
<span class="doxyMemberLabels">
<span class="doxyMemberLabel inline">inline</span>
<span class="doxyMemberLabel static">static</span>
</span>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 49 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/transforms/include/llvm/transforms/coroutines/corosplit-h">CoroSplit.h</a>.</p>

</div>
</div>

</div>

<hr/>

The documentation for this struct was generated from the following files:

<ul>
<li><a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/transforms/include/llvm/transforms/coroutines/corosplit-h">CoroSplit.h</a></li>
<li><a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/coroutines/corosplit-cpp">CoroSplit.cpp</a></li>
</ul>

<hr/>

<p class="doxyGeneratedBy">Generated via <a href="https://github.com/xpack/doxygen2docusaurus">doxygen2docusaurus</a> by <a href="https://www.doxygen.nl">Doxygen</a> 1.15.0.</p>

</div>
