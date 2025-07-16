---

# DO NOT EDIT!
# Automatically generated via doxygen2docusaurus by Doxygen.

slug: /api/classes/llvm/loopunrollpass
custom_edit_url: null
toc_max_heading_level: 4
keywords:
  - doxygen
  - reference
  - class

---

<div class="doxyPage">

# The `LoopUnrollPass` Class Reference

<p><a href="/web-llvm/docs/api/classes/llvm/loop">Loop</a> unroll pass that will support both full and partial unrolling. <a href="#details">More...</a></p>

## Declaration

<div class="doxyDeclaration">
class llvm::LoopUnrollPass { ... }
</div>

## Included Headers

<div class="doxyIncludesList">#include "<a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/transforms/include/llvm/transforms/scalar/loopunrollpass-h">llvm/Transforms/Scalar/LoopUnrollPass.h</a>"
</div>

## Base class

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

## Public Constructors Index

<table class="doxyMembersIndex">

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a2e1907c5ba529e1a6778611df03fa07b">LoopUnrollPass</a> (LoopUnrollOptions UnrollOpts={})</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>This uses the target information (or flags) to control the thresholds for different unrolling stategies but supports all of them. <a href="#a2e1907c5ba529e1a6778611df03fa07b">More...</a></p>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a62ed17cf8aa893362e6c3c1f6d8a0898">run</a> (Function &amp;F, FunctionAnalysisManager &amp;AM)</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ac318cdc3433689772c5cce5abdb39472">printPipeline</a> (raw_ostream &amp;OS, function_ref&lt; StringRef(StringRef)&gt; MapClassName2PassName)</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/structs/llvm/loopunrolloptions">LoopUnrollOptions</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a20522d67f8715073f224272bc9475635">UnrollOpts</a></td>
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

<p><a href="/web-llvm/docs/api/classes/llvm/loop">Loop</a> unroll pass that will support both full and partial unrolling.</p>


<p>It is a function pass to have access to function and module analyses. It will also put loops into canonical form (simplified and LCSSA).</p>


<p>Definition at line 133 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/transforms/include/llvm/transforms/scalar/loopunrollpass-h">LoopUnrollPass.h</a>.</p>


<div class="doxySectionDef">

## Public Constructors

### LoopUnrollPass() {#a2e1907c5ba529e1a6778611df03fa07b}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">llvm::LoopUnrollPass::LoopUnrollPass (<a href="/web-llvm/docs/api/structs/llvm/loopunrolloptions">LoopUnrollOptions</a> UnrollOpts={})</td>
</tr>
</table>
</td>
<td class="doxyMemberLabelsRight">
<span class="doxyMemberLabels">
<span class="doxyMemberLabel inline">inline</span>
<span class="doxyMemberLabel explicit">explicit</span>
</span>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>This uses the target information (or flags) to control the thresholds for different unrolling stategies but supports all of them.</p>

<p>Definition at line 139 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/transforms/include/llvm/transforms/scalar/loopunrollpass-h">LoopUnrollPass.h</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Public Member Functions

### printPipeline() {#ac318cdc3433689772c5cce5abdb39472}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void LoopUnrollPass::printPipeline (<a href="/web-llvm/docs/api/classes/llvm/raw-ostream">raw_ostream</a> &amp; OS, <a href="/web-llvm/docs/api/classes/llvm/function-ref">function_ref</a>&lt; <a href="/web-llvm/docs/api/classes/llvm/stringref">StringRef</a>(<a href="/web-llvm/docs/api/classes/llvm/stringref">StringRef</a>)&gt; MapClassName2PassName)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Declaration at line 143 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/transforms/include/llvm/transforms/scalar/loopunrollpass-h">LoopUnrollPass.h</a>, definition at line 1682 of file <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/scalar/loopunrollpass-cpp">LoopUnrollPass.cpp</a>.</p>


<p>Reference <a href="#ac318cdc3433689772c5cce5abdb39472">printPipeline</a>.</p>


<p>Referenced by <a href="#ac318cdc3433689772c5cce5abdb39472">printPipeline</a>.</p>

</div>
</div>

### run() {#a62ed17cf8aa893362e6c3c1f6d8a0898}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">PreservedAnalyses LoopUnrollPass::run (<a href="/web-llvm/docs/api/classes/llvm/function">Function</a> &amp; F, <a href="/web-llvm/docs/api/namespaces/llvm/#adce09a5a0de0e3177eb00e932734af2f">FunctionAnalysisManager</a> &amp; AM)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Declaration at line 142 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/transforms/include/llvm/transforms/scalar/loopunrollpass-h">LoopUnrollPass.h</a>, definition at line 1593 of file <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/scalar/loopunrollpass-cpp">LoopUnrollPass.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/namespaces/llvm/#ab7a106c600cf32852298d9041e8c8044">llvm::appendLoopsToWorklist</a>, <a href="/web-llvm/docs/api/classes/llvm/priorityworklist/#adc2ef5f0964becc28dfa58a7abc2f1e7">llvm::PriorityWorklist&lt; T, VectorT, MapT &gt;::empty</a>, <a href="/web-llvm/docs/api/files/lib/lib/support/md5-cpp/#a96d73bbd7af15cb1fc38c3f4a3bd82e9">F</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a30e47ae014eb35bea24e45097c2bd731">llvm::formLCSSARecursively</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a8c861ddf753ab3690437dceaadf5c7e1add722bdf19fff3e686f559790c6124d8">llvm::FullyUnrolled</a>, <a href="/web-llvm/docs/api/classes/llvm/analysismanager/#a828ff8185f881fca9e3d534781244041">llvm::AnalysisManager&lt; IRUnitT, ExtraArgTs &gt;::getCachedResult</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#ac7294ba4e105807674fe3a394437fcc1">llvm::getLoopPassPreservedAnalyses</a>, <a href="/web-llvm/docs/api/classes/llvm/analysismanager/#aaab1fad63e4f3b8679469720a873fedd">llvm::AnalysisManager&lt; IRUnitT, ExtraArgTs &gt;::getResult</a>, <a href="/web-llvm/docs/api/files/lib/lib/passes/passbuilderbindings-cpp/#a7cfe61417446ebb812e81293bde22a29">LAM</a>, <a href="/web-llvm/docs/api/classes/llvm/priorityworklist/#ab89ceb7695256590499de818b5360c54">llvm::PriorityWorklist&lt; T, VectorT, MapT &gt;::pop_back_val</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a0083a69883e0f97e111dbff064c60f42">llvm::simplifyLoop</a>, <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/scalar/loopunrollpass-cpp/#ab6df82212b20d28e61ff9417744420ff">tryToUnrollLoop</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a8c861ddf753ab3690437dceaadf5c7e1aac5e6ff0bb9cd22f9f55570e7b318c84">llvm::Unmodified</a> and <a href="/web-llvm/docs/api/classes/llvm/loopbase/#a2896fd505fc6356f4ad5b53bb5001a39">llvm::LoopBase&lt; BlockT, LoopT &gt;::verifyLoop</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Private Member Attributes

### UnrollOpts {#a20522d67f8715073f224272bc9475635}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">LoopUnrollOptions llvm::LoopUnrollPass::UnrollOpts</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 134 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/transforms/include/llvm/transforms/scalar/loopunrollpass-h">LoopUnrollPass.h</a>.</p>

</div>
</div>

</div>

<hr/>

The documentation for this class was generated from the following files:

<ul>
<li><a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/transforms/include/llvm/transforms/scalar/loopunrollpass-h">LoopUnrollPass.h</a></li>
<li><a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/scalar/loopunrollpass-cpp">LoopUnrollPass.cpp</a></li>
</ul>

<hr/>

<p class="doxyGeneratedBy">Generated via <a href="https://github.com/xpack/doxygen2docusaurus">doxygen2docusaurus</a> by <a href="https://www.doxygen.nl">Doxygen</a> 1.15.0.</p>

</div>
