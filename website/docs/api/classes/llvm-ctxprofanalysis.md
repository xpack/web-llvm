---

# DO NOT EDIT!
# Automatically generated via doxygen2docusaurus by Doxygen.

slug: /api/classes/llvm/ctxprofanalysis
custom_edit_url: null
toc_max_heading_level: 4
keywords:
  - doxygen
  - reference
  - class

---

<div class="doxyPage">

# `CtxProfAnalysis` Class



## Declaration

<div class="doxyDeclaration">
class llvm::CtxProfAnalysis { ... }
</div>

## Included Headers

<div class="doxyIncludesList">#include "<a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/analysis/ctxprofanalysis-h">llvm/Analysis/CtxProfAnalysis.h</a>"
</div>

## Base class

<table class="doxyMembersIndex">

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">struct</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="/web-llvm/docs/api/structs/llvm/analysisinfomixin">AnalysisInfoMixin&lt;DerivedT&gt;</a></td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>A CRTP mix-in that provides informational APIs needed for analysis passes. <a href="/web-llvm/docs/api/structs/llvm/analysisinfomixin/#details">More...</a></p>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ad194602e219bc748c795ee7fbbac6abb">Result</a> = <a href="/web-llvm/docs/api/classes/llvm/pgocontextualprofile">PGOContextualProfile</a></td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#aeb0c1de723319e0dde2c8e263eb4c2ac">CtxProfAnalysis</a> (std::optional&lt; StringRef &gt; Profile=std::nullopt)</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/pgocontextualprofile">PGOContextualProfile</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a0cbc02f8988e793203b0a4f7e75587c0">run</a> (Module &amp;M, ModuleAnalysisManager &amp;MAM)</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> std::optional&lt; <a href="/web-llvm/docs/api/classes/llvm/stringref">StringRef</a> &gt;</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#adf31ea09a633a9225eb099a5bb7b5464">Profile</a></td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">static <a href="/web-llvm/docs/api/classes/llvm/instrprofcallsite">InstrProfCallsite</a> *</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#aa20d83f600303548f2e24aa2fc98e377">getCallsiteInstrumentation</a> (CallBase &amp;CB)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Get the instruction instrumenting a callsite, or nullptr if that cannot be found. <a href="#aa20d83f600303548f2e24aa2fc98e377">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">static <a href="/web-llvm/docs/api/classes/llvm/instrprofincrementinst">InstrProfIncrementInst</a> *</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a3a31a6be1881280b30e349edabc9ca43">getBBInstrumentation</a> (BasicBlock &amp;BB)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Get the instruction instrumenting a BB, or nullptr if not present. <a href="#a3a31a6be1881280b30e349edabc9ca43">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">static <a href="/web-llvm/docs/api/classes/llvm/instrprofincrementinststep">InstrProfIncrementInstStep</a> *</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a411b52f3710d28d5927341e36853f03b">getSelectInstrumentation</a> (SelectInst &amp;SI)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Get the step instrumentation associated with a <span class="doxyComputerOutput">select</span> <a href="#a411b52f3710d28d5927341e36853f03b">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">static void</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a4dd66bb1f3a24ebaf94d2f204a700e4a">collectIndirectCallPromotionList</a> (CallBase &amp;IC, Result &amp;Profile, SetVector&lt; std::pair&lt; CallBase *, Function * &gt; &gt; &amp;Candidates)</td>
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

## Public Static Attributes Index

<table class="doxyMembersIndex">

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">static <a href="/web-llvm/docs/api/structs/llvm/analysiskey">AnalysisKey</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#aa59b19b76f7d4522d1abbeda36f844d6">Key</a></td>
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


<p>Definition at line 113 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/analysis/ctxprofanalysis-h">CtxProfAnalysis.h</a>.</p>


<div class="doxySectionDef">

## Public Member Typedefs

### Result {#ad194602e219bc748c795ee7fbbac6abb}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">using llvm::CtxProfAnalysis::Result =  PGOContextualProfile</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 120 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/analysis/ctxprofanalysis-h">CtxProfAnalysis.h</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Public Constructors

### CtxProfAnalysis() {#aeb0c1de723319e0dde2c8e263eb4c2ac}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">CtxProfAnalysis::CtxProfAnalysis (std::optional&lt; <a href="/web-llvm/docs/api/classes/llvm/stringref">StringRef</a> &gt; Profile=std::nullopt)</td>
</tr>
</table>
</td>
<td class="doxyMemberLabelsRight">
<span class="doxyMemberLabels">
<span class="doxyMemberLabel explicit">explicit</span>
</span>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Declaration at line 118 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/analysis/ctxprofanalysis-h">CtxProfAnalysis.h</a>, definition at line 71 of file <a href="/web-llvm/docs/api/files/lib/lib/analysis/ctxprofanalysis-cpp">CtxProfAnalysis.cpp</a>.</p>


<p>Reference <a href="/web-llvm/docs/api/files/lib/lib/analysis/ctxprofanalysis-cpp/#ae2b2c87a52448d91bf5be603cc14acc5">UseCtxProfile</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Public Member Functions

### run() {#a0cbc02f8988e793203b0a4f7e75587c0}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">PGOContextualProfile CtxProfAnalysis::run (<a href="/web-llvm/docs/api/classes/llvm/module">Module</a> &amp; M, <a href="/web-llvm/docs/api/namespaces/llvm/#af9c9208365fd9ce11392b4d79485e259">ModuleAnalysisManager</a> &amp; MAM)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Declaration at line 122 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/analysis/ctxprofanalysis-h">CtxProfAnalysis.h</a>, definition at line 80 of file <a href="/web-llvm/docs/api/files/lib/lib/analysis/ctxprofanalysis-cpp">CtxProfAnalysis.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/hexagon/lib/target/hexagon/mctargetdesc/hexagonmccodeemitter-cpp/#ae4dfd7b0d66121016d6466d2ff10e8ba">_</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/silowercontrolflow-cpp/#a4868c5d81c5ccc98c47aeab6244346a0">assert</a>, <a href="/web-llvm/docs/api/namespaces/llvm/callingconv/#ac6aa1387c4375260e2468eb5a77fdb4cafd841a49aec1539bc88abc8ff9e170fb">llvm::CallingConv::C</a>, <a href="/web-llvm/docs/api/classes/llvm/detail/densesetimpl/#ad409c2de8502b94c8a0b1193307c63b6">llvm::detail::DenseSetImpl&lt; ValueT, MapTy, ValueInfoT &gt;::contains</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a22eeee01734061ac1b31ccd994c49eef">llvm::dyn_cast</a>, <a href="/web-llvm/docs/api/files/lib/lib/support/md5-cpp/#a96d73bbd7af15cb1fc38c3f4a3bd82e9">F</a>, <a href="/web-llvm/docs/api/classes/llvm/memorybuffer/#aa98611beefe78f907beeee7305cc8174">llvm::MemoryBuffer::getFile</a>, <a href="/web-llvm/docs/api/classes/llvm/assignguidpass/#a00cd72af35cb6bdeae06467500b531ae">llvm::AssignGUIDPass::getGUID</a>, <a href="/web-llvm/docs/api/files/lib/lib/support/md5-cpp/#ac0eafdc9ee161b71e7af98af736952fd">I</a>, <a href="/web-llvm/docs/api/classes/llvm/detail/densesetimpl/#a1b0f3ebdced8fce4b22c6a63b25d9525">llvm::detail::DenseSetImpl&lt; ValueT, MapTy, ValueInfoT &gt;::insert</a>, <a href="/web-llvm/docs/api/classes/llvm/pgoctxprofilereader/#a77404104d3023855650e4348186034e9">llvm::PGOCtxProfileReader::loadContexts</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a3d2cdc4a0db233678e7141c9d6ea3419">llvm::make_early_inc_range</a>, <a href="/web-llvm/docs/api/files/lib/lib/passes/passbuilderbindings-cpp/#a85bddafa659a93a7a67c9094648259be">MAM</a> and <a href="/web-llvm/docs/api/namespaces/llvm/#ad06d74e24faba91639ef782ef7291c3d">llvm::toString</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Private Member Attributes

### Profile {#adf31ea09a633a9225eb099a5bb7b5464}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">const std::optional&lt;StringRef&gt; llvm::CtxProfAnalysis::Profile</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 114 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/analysis/ctxprofanalysis-h">CtxProfAnalysis.h</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Public Static Functions

### collectIndirectCallPromotionList() {#a4dd66bb1f3a24ebaf94d2f204a700e4a}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void CtxProfAnalysis::collectIndirectCallPromotionList (<a href="/web-llvm/docs/api/classes/llvm/callbase">CallBase</a> &amp; IC, <a href="#ad194602e219bc748c795ee7fbbac6abb">Result</a> &amp; Profile, <a href="/web-llvm/docs/api/classes/llvm/setvector">SetVector</a>&lt; std::pair&lt; <a href="/web-llvm/docs/api/classes/llvm/callbase">CallBase</a> *, <a href="/web-llvm/docs/api/classes/llvm/function">Function</a> * &gt; &gt; &amp; Candidates)</td>
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



<p>Declaration at line 135 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/analysis/ctxprofanalysis-h">CtxProfAnalysis.h</a>, definition at line 301 of file <a href="/web-llvm/docs/api/files/lib/lib/analysis/ctxprofanalysis-cpp">CtxProfAnalysis.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/hexagon/lib/target/hexagon/mctargetdesc/hexagonmccodeemitter-cpp/#ae4dfd7b0d66121016d6466d2ff10e8ba">_</a>, <a href="/web-llvm/docs/api/classes/llvm/callbase/#afac5b39bcbb90d660f83d9b4bd8c6d95">llvm::CallBase::getCaller</a>, <a href="#aa20d83f600303548f2e24aa2fc98e377">getCallsiteInstrumentation</a>, <a href="/web-llvm/docs/api/classes/llvm/ilist-detail/node-parent-access/#a7e19e7508415378ad9523e0339b23e22">llvm::ilist_detail::node_parent_access&lt; NodeTy, ParentTy &gt;::getParent</a> and <a href="/web-llvm/docs/api/namespaces/llvm/#af59335be18fa802d111a646be658b7d0acb957607a78494ea70db887d1463437c">llvm::Guid</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/classes/llvm/moduleinlinerpass/#ab7155781c9a6aafef322de28d9bc4c86">llvm::ModuleInlinerPass::run</a>.</p>

</div>
</div>

### getBBInstrumentation() {#a3a31a6be1881280b30e349edabc9ca43}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">InstrProfIncrementInst * CtxProfAnalysis::getBBInstrumentation (<a href="/web-llvm/docs/api/classes/llvm/basicblock">BasicBlock</a> &amp; BB)</td>
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

<p>Get the instruction instrumenting a BB, or nullptr if not present.</p>

<p>Declaration at line 129 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/analysis/ctxprofanalysis-h">CtxProfAnalysis.h</a>, definition at line 211 of file <a href="/web-llvm/docs/api/files/lib/lib/analysis/ctxprofanalysis-cpp">CtxProfAnalysis.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/namespaces/llvm/#a22eeee01734061ac1b31ccd994c49eef">llvm::dyn_cast</a>, <a href="/web-llvm/docs/api/files/lib/lib/support/md5-cpp/#ac0eafdc9ee161b71e7af98af736952fd">I</a> and <a href="/web-llvm/docs/api/namespaces/llvm/#a92ca992e52dddc420f4b069cae06dfbe">llvm::isa</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/classes/anonymous-pgoctxprofflattening-cpp-/profileannotator/#a9a58a5d6b3af1afec70ac9b8c1b2c902">anonymous{PGOCtxProfFlattening.cpp}::ProfileAnnotator::ProfileAnnotator</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a9469fd548994812c12e4c10d42ec82a3">llvm::promoteCallWithIfThenElse</a> and <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/utils/inlinefunction-cpp/#aa46864b5ba9d7d71163e2f00ab1cddf5">remapIndices</a>.</p>

</div>
</div>

### getCallsiteInstrumentation() {#aa20d83f600303548f2e24aa2fc98e377}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">InstrProfCallsite * CtxProfAnalysis::getCallsiteInstrumentation (<a href="/web-llvm/docs/api/classes/llvm/callbase">CallBase</a> &amp; CB)</td>
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

<p>Get the instruction instrumenting a callsite, or nullptr if that cannot be found.</p>

<p>Declaration at line 126 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/analysis/ctxprofanalysis-h">CtxProfAnalysis.h</a>, definition at line 198 of file <a href="/web-llvm/docs/api/files/lib/lib/analysis/ctxprofanalysis-cpp">CtxProfAnalysis.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/silowercontrolflow-cpp/#a4868c5d81c5ccc98c47aeab6244346a0">assert</a>, <a href="/web-llvm/docs/api/classes/llvm/instrprofcallsite/#ad13669e41527f0cb36a0f5c93cff4a21">llvm::InstrProfCallsite::canInstrumentCallsite</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a22eeee01734061ac1b31ccd994c49eef">llvm::dyn_cast</a>, <a href="/web-llvm/docs/api/classes/llvm/ilist-node-with-parent/#a1dfdcf6998ec28bfd2f8d2cdebc984a9">llvm::ilist_node_with_parent&lt; NodeTy, ParentTy, Options &gt;::getPrevNode</a> and <a href="/web-llvm/docs/api/namespaces/llvm/#a92ca992e52dddc420f4b069cae06dfbe">llvm::isa</a>.</p>


<p>Referenced by <a href="#a4dd66bb1f3a24ebaf94d2f204a700e4a">collectIndirectCallPromotionList</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a9031658af970d96ad739450ec380d86a">llvm::InlineFunction</a> and <a href="/web-llvm/docs/api/namespaces/llvm/#a9469fd548994812c12e4c10d42ec82a3">llvm::promoteCallWithIfThenElse</a>.</p>

</div>
</div>

### getSelectInstrumentation() {#a411b52f3710d28d5927341e36853f03b}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">InstrProfIncrementInstStep * CtxProfAnalysis::getSelectInstrumentation (<a href="/web-llvm/docs/api/classes/llvm/selectinst">SelectInst</a> &amp; SI)</td>
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

<p>Get the step instrumentation associated with a <span class="doxyComputerOutput">select</span></p>

<p>Declaration at line 132 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/analysis/ctxprofanalysis-h">CtxProfAnalysis.h</a>, definition at line 220 of file <a href="/web-llvm/docs/api/files/lib/lib/analysis/ctxprofanalysis-cpp">CtxProfAnalysis.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/namespaces/llvm/#a22eeee01734061ac1b31ccd994c49eef">llvm::dyn_cast</a> and <a href="/web-llvm/docs/api/classes/llvm/ilist-node-with-parent/#a1dfdcf6998ec28bfd2f8d2cdebc984a9">llvm::ilist_node_with_parent&lt; NodeTy, ParentTy, Options &gt;::getPrevNode</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/classes/anonymous-pgoctxprofflattening-cpp-/profileannotator/#aced541bffb79f022b3251cde733f77e8">anonymous{PGOCtxProfFlattening.cpp}::ProfileAnnotator::setProfileForSelectInstructions</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Public Static Attributes

### Key {#aa59b19b76f7d4522d1abbeda36f844d6}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">AnalysisKey CtxProfAnalysis::Key</td>
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



<p>Definition at line 117 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/analysis/ctxprofanalysis-h">CtxProfAnalysis.h</a>.</p>

</div>
</div>

</div>

<hr/>

The documentation for this class was generated from the following files:

<ul>
<li><a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/analysis/ctxprofanalysis-h">CtxProfAnalysis.h</a></li>
<li><a href="/web-llvm/docs/api/files/lib/lib/analysis/ctxprofanalysis-cpp">CtxProfAnalysis.cpp</a></li>
</ul>

<hr/>

<p class="doxyGeneratedBy">Generated via <a href="https://github.com/xpack/doxygen2docusaurus">doxygen2docusaurus</a> by <a href="https://www.doxygen.nl">Doxygen</a> 1.15.0.</p>

</div>
