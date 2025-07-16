---

# DO NOT EDIT!
# Automatically generated via doxygen2docusaurus by Doxygen.

slug: /api/classes/anonymous-loopunrollpass-cpp-/loopunroll
custom_edit_url: null
toc_max_heading_level: 4
keywords:
  - doxygen
  - reference
  - class

---

<div class="doxyPage">

# The `LoopUnroll` Class Reference



## Declaration

<div class="doxyDeclaration">
class anonymous{LoopUnrollPass.cpp}::LoopUnroll { ... }
</div>

## Base class

<table class="doxyMembersIndex">

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">class</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/looppass">LoopPass</a></td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a75e222e94c61c768491fb808096d1953">LoopUnroll</a> (int OptLevel=2, bool OnlyWhenForced=false, bool ForgetAllSCEV=false, std::optional&lt; unsigned &gt; Threshold=std::nullopt, std::optional&lt; unsigned &gt; Count=std::nullopt, std::optional&lt; bool &gt; AllowPartial=std::nullopt, std::optional&lt; bool &gt; Runtime=std::nullopt, std::optional&lt; bool &gt; UpperBound=std::nullopt, std::optional&lt; bool &gt; AllowPeeling=std::nullopt, std::optional&lt; bool &gt; AllowProfileBasedPeeling=std::nullopt, std::optional&lt; unsigned &gt; ProvidedFullUnrollMaxCount=std::nullopt)</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">bool</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a176b0f7a9dc90d996cae2767b3aea0ca">runOnLoop</a> (Loop *L, LPPassManager &amp;LPM) override</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a300d24aab1f2cf36089d0daa640d5b8f">getAnalysisUsage</a> (AnalysisUsage &amp;AU) const override</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>This transformation requires natural loop information &amp; requires that loop preheaders be inserted into the CFG... <a href="#a300d24aab1f2cf36089d0daa640d5b8f">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

</table>

## Public Member Attributes Index

<table class="doxyMembersIndex">

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">int</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a527cd7bd83369d2f31e9b8c933e57150">OptLevel</a></td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a9b38d6cf75cc948e981de87f0dfee2bd">OnlyWhenForced</a></td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>If false, use a cost model to determine whether unrolling of a loop is profitable. <a href="#a9b38d6cf75cc948e981de87f0dfee2bd">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">bool</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a06e9230dbb1e24f5398518447f5aa568">ForgetAllSCEV</a></td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>If false, when <a href="/web-llvm/docs/api/classes/llvm/scev">SCEV</a> is invalidated, only forget everything in the top-most loop (call forgetTopMostLoop), of the loop being processed. <a href="#a06e9230dbb1e24f5398518447f5aa568">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">std::optional&lt; unsigned &gt;</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#afc02f6df322b6e474d7cae00c32d5359">ProvidedCount</a></td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">std::optional&lt; unsigned &gt;</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a4b07daef177cac672f67877257bb7e42">ProvidedThreshold</a></td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">std::optional&lt; bool &gt;</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a88ffa785f507ea0164cbf8826a69e721">ProvidedAllowPartial</a></td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">std::optional&lt; bool &gt;</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ae3f69a119b1d6e64f4b47b71184d76ff">ProvidedRuntime</a></td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">std::optional&lt; bool &gt;</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#abcbc7bee3077936a0a570f166e149343">ProvidedUpperBound</a></td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">std::optional&lt; bool &gt;</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a69042fae1c005289be92b3465cc6d9fd">ProvidedAllowPeeling</a></td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">std::optional&lt; bool &gt;</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#aa5adcb078180828109b2e9044d97a317">ProvidedAllowProfileBasedPeeling</a></td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">std::optional&lt; unsigned &gt;</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a0e7d1ba1fcb1697c23806f7a2cecb79a">ProvidedFullUnrollMaxCount</a></td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">static char</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ad04341bfb03fbed7713ee9ff65c154e8">ID</a> = 0</td>
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


<p>Definition at line 1393 of file <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/scalar/loopunrollpass-cpp">LoopUnrollPass.cpp</a>.</p>


<div class="doxySectionDef">

## Public Constructors

### LoopUnroll() {#a75e222e94c61c768491fb808096d1953}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">anonymous{LoopUnrollPass.cpp}::LoopUnroll::LoopUnroll (int OptLevel=2, bool OnlyWhenForced=false, bool ForgetAllSCEV=false, std::optional&lt; unsigned &gt; Threshold=std::nullopt, std::optional&lt; unsigned &gt; Count=std::nullopt, std::optional&lt; bool &gt; AllowPartial=std::nullopt, std::optional&lt; bool &gt; Runtime=std::nullopt, std::optional&lt; bool &gt; UpperBound=std::nullopt, std::optional&lt; bool &gt; AllowPeeling=std::nullopt, std::optional&lt; bool &gt; AllowProfileBasedPeeling=std::nullopt, std::optional&lt; unsigned &gt; ProvidedFullUnrollMaxCount=std::nullopt)</td>
</tr>
</table>
</td>
<td class="doxyMemberLabelsRight">
<span class="doxyMemberLabels">
<span class="doxyMemberLabel inline">inline</span>
</span>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 1418 of file <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/scalar/loopunrollpass-cpp">LoopUnrollPass.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/namespaces/llvm/#a845e08be4b0320d66901a66b0c0e9509">llvm::Count</a>, <a href="#a06e9230dbb1e24f5398518447f5aa568">ForgetAllSCEV</a>, <a href="/web-llvm/docs/api/classes/llvm/passregistry/#a05a729900b76c89e808c6c3094921b2f">llvm::PassRegistry::getPassRegistry</a>, <a href="#ad04341bfb03fbed7713ee9ff65c154e8">ID</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a1ae4cc6b0e03c93538ef094518fabd35">llvm::initializeLoopUnrollPass</a>, <a href="/web-llvm/docs/api/classes/llvm/looppass/#a4d5799624e630ba03cb9133168951e8a">llvm::LoopPass::LoopPass</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#abfc9c7ecf70f66901e439f7c04ef3dbb">llvm::move</a>, <a href="#a9b38d6cf75cc948e981de87f0dfee2bd">OnlyWhenForced</a>, <a href="#a527cd7bd83369d2f31e9b8c933e57150">OptLevel</a>, <a href="#a88ffa785f507ea0164cbf8826a69e721">ProvidedAllowPartial</a>, <a href="#a69042fae1c005289be92b3465cc6d9fd">ProvidedAllowPeeling</a>, <a href="#aa5adcb078180828109b2e9044d97a317">ProvidedAllowProfileBasedPeeling</a>, <a href="#afc02f6df322b6e474d7cae00c32d5359">ProvidedCount</a>, <a href="#a0e7d1ba1fcb1697c23806f7a2cecb79a">ProvidedFullUnrollMaxCount</a>, <a href="#ae3f69a119b1d6e64f4b47b71184d76ff">ProvidedRuntime</a>, <a href="#a4b07daef177cac672f67877257bb7e42">ProvidedThreshold</a>, <a href="#abcbc7bee3077936a0a570f166e149343">ProvidedUpperBound</a> and <a href="/web-llvm/docs/api/namespaces/llvm/#a273ffd11c1ebf40fc70e3b22009adabdabc366f2d0ba3d681e7a3899917c5d3de">llvm::Runtime</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Public Member Functions

### getAnalysisUsage() {#a300d24aab1f2cf36089d0daa640d5b8f}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void anonymous{LoopUnrollPass.cpp}::LoopUnroll::getAnalysisUsage (<a href="/web-llvm/docs/api/classes/llvm/analysisusage">AnalysisUsage</a> &amp; AU)</td>
</tr>
</table>
</td>
<td class="doxyMemberLabelsRight">
<span class="doxyMemberLabels">
<span class="doxyMemberLabel inline">inline</span>
<span class="doxyMemberLabel virtual">virtual</span>
</span>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>This transformation requires natural loop information &amp; requires that loop preheaders be inserted into the CFG...</p>

<p>Definition at line 1471 of file <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/scalar/loopunrollpass-cpp">LoopUnrollPass.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/classes/llvm/analysisusage/#ae0adcccca08fb686c9ce00f9397b660c">llvm::AnalysisUsage::addRequired</a> and <a href="/web-llvm/docs/api/namespaces/llvm/#a92caae34bfacc63bda0f23d5d005a89e">llvm::getLoopAnalysisUsage</a>.</p>

</div>
</div>

### runOnLoop() {#a176b0f7a9dc90d996cae2767b3aea0ca}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool anonymous{LoopUnrollPass.cpp}::LoopUnroll::runOnLoop (<a href="/web-llvm/docs/api/classes/llvm/loop">Loop</a> * L, <a href="/web-llvm/docs/api/classes/llvm/lppassmanager">LPPassManager</a> &amp; LPM)</td>
</tr>
</table>
</td>
<td class="doxyMemberLabelsRight">
<span class="doxyMemberLabels">
<span class="doxyMemberLabel inline">inline</span>
<span class="doxyMemberLabel virtual">virtual</span>
</span>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 1438 of file <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/scalar/loopunrollpass-cpp">LoopUnrollPass.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/files/lib/lib/support/md5-cpp/#a96d73bbd7af15cb1fc38c3f4a3bd82e9">F</a>, <a href="#a06e9230dbb1e24f5398518447f5aa568">ForgetAllSCEV</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a8c861ddf753ab3690437dceaadf5c7e1add722bdf19fff3e686f559790c6124d8">llvm::FullyUnrolled</a>, <a href="/web-llvm/docs/api/classes/llvm/pass/#a4863e5e463fb79955269fbf7fbf52b80">llvm::Pass::getAnalysis</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a3e3d3c6d4e33a4f5ca579ee7939f0349">llvm::LCSSAID</a>, <a href="/web-llvm/docs/api/classes/llvm/lppassmanager/#a8ef47cc6f59b91bf5a1392975366e758">llvm::LPPassManager::markLoopAsDeleted</a>, <a href="/web-llvm/docs/api/classes/llvm/pass/#a0b4a511579939b07831db90c3fc98996">llvm::Pass::mustPreserveAnalysisID</a>, <a href="#a9b38d6cf75cc948e981de87f0dfee2bd">OnlyWhenForced</a>, <a href="#a527cd7bd83369d2f31e9b8c933e57150">OptLevel</a>, <a href="#a88ffa785f507ea0164cbf8826a69e721">ProvidedAllowPartial</a>, <a href="#a69042fae1c005289be92b3465cc6d9fd">ProvidedAllowPeeling</a>, <a href="#aa5adcb078180828109b2e9044d97a317">ProvidedAllowProfileBasedPeeling</a>, <a href="#afc02f6df322b6e474d7cae00c32d5359">ProvidedCount</a>, <a href="#a0e7d1ba1fcb1697c23806f7a2cecb79a">ProvidedFullUnrollMaxCount</a>, <a href="#ae3f69a119b1d6e64f4b47b71184d76ff">ProvidedRuntime</a>, <a href="#a4b07daef177cac672f67877257bb7e42">ProvidedThreshold</a>, <a href="#abcbc7bee3077936a0a570f166e149343">ProvidedUpperBound</a>, <a href="/web-llvm/docs/api/classes/llvm/looppass/#ac97db8f0e4f4a0946dddf617f45f6c8b">llvm::LoopPass::skipLoop</a>, <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/scalar/loopunrollpass-cpp/#ab6df82212b20d28e61ff9417744420ff">tryToUnrollLoop</a> and <a href="/web-llvm/docs/api/namespaces/llvm/#a8c861ddf753ab3690437dceaadf5c7e1aac5e6ff0bb9cd22f9f55570e7b318c84">llvm::Unmodified</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Public Member Attributes

### ForgetAllSCEV {#a06e9230dbb1e24f5398518447f5aa568}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool anonymous{LoopUnrollPass.cpp}::LoopUnroll::ForgetAllSCEV</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>If false, when <a href="/web-llvm/docs/api/classes/llvm/scev">SCEV</a> is invalidated, only forget everything in the top-most loop (call forgetTopMostLoop), of the loop being processed.</p>


<p>Otherwise, forgetAllLoops and rebuild when needed next.</p>


<p>Definition at line 1407 of file <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/scalar/loopunrollpass-cpp">LoopUnrollPass.cpp</a>.</p>


<p>Referenced by <a href="#a75e222e94c61c768491fb808096d1953">LoopUnroll</a> and <a href="#a176b0f7a9dc90d996cae2767b3aea0ca">runOnLoop</a>.</p>

</div>
</div>

### OnlyWhenForced {#a9b38d6cf75cc948e981de87f0dfee2bd}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool anonymous{LoopUnrollPass.cpp}::LoopUnroll::OnlyWhenForced</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>If false, use a cost model to determine whether unrolling of a loop is profitable.</p>


<p>If true, only loops that explicitly request unrolling via metadata are considered. All other loops are skipped.</p>


<p>Definition at line 1402 of file <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/scalar/loopunrollpass-cpp">LoopUnrollPass.cpp</a>.</p>


<p>Referenced by <a href="#a75e222e94c61c768491fb808096d1953">LoopUnroll</a> and <a href="#a176b0f7a9dc90d996cae2767b3aea0ca">runOnLoop</a>.</p>

</div>
</div>

### OptLevel {#a527cd7bd83369d2f31e9b8c933e57150}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">int anonymous{LoopUnrollPass.cpp}::LoopUnroll::OptLevel</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 1397 of file <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/scalar/loopunrollpass-cpp">LoopUnrollPass.cpp</a>.</p>


<p>Referenced by <a href="#a75e222e94c61c768491fb808096d1953">LoopUnroll</a> and <a href="#a176b0f7a9dc90d996cae2767b3aea0ca">runOnLoop</a>.</p>

</div>
</div>

### ProvidedAllowPartial {#a88ffa785f507ea0164cbf8826a69e721}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">std::optional&lt;bool&gt; anonymous{LoopUnrollPass.cpp}::LoopUnroll::ProvidedAllowPartial</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 1411 of file <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/scalar/loopunrollpass-cpp">LoopUnrollPass.cpp</a>.</p>


<p>Referenced by <a href="#a75e222e94c61c768491fb808096d1953">LoopUnroll</a> and <a href="#a176b0f7a9dc90d996cae2767b3aea0ca">runOnLoop</a>.</p>

</div>
</div>

### ProvidedAllowPeeling {#a69042fae1c005289be92b3465cc6d9fd}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">std::optional&lt;bool&gt; anonymous{LoopUnrollPass.cpp}::LoopUnroll::ProvidedAllowPeeling</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 1414 of file <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/scalar/loopunrollpass-cpp">LoopUnrollPass.cpp</a>.</p>


<p>Referenced by <a href="#a75e222e94c61c768491fb808096d1953">LoopUnroll</a> and <a href="#a176b0f7a9dc90d996cae2767b3aea0ca">runOnLoop</a>.</p>

</div>
</div>

### ProvidedAllowProfileBasedPeeling {#aa5adcb078180828109b2e9044d97a317}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">std::optional&lt;bool&gt; anonymous{LoopUnrollPass.cpp}::LoopUnroll::ProvidedAllowProfileBasedPeeling</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 1415 of file <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/scalar/loopunrollpass-cpp">LoopUnrollPass.cpp</a>.</p>


<p>Referenced by <a href="#a75e222e94c61c768491fb808096d1953">LoopUnroll</a> and <a href="#a176b0f7a9dc90d996cae2767b3aea0ca">runOnLoop</a>.</p>

</div>
</div>

### ProvidedCount {#afc02f6df322b6e474d7cae00c32d5359}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">std::optional&lt;unsigned&gt; anonymous{LoopUnrollPass.cpp}::LoopUnroll::ProvidedCount</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 1409 of file <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/scalar/loopunrollpass-cpp">LoopUnrollPass.cpp</a>.</p>


<p>Referenced by <a href="#a75e222e94c61c768491fb808096d1953">LoopUnroll</a> and <a href="#a176b0f7a9dc90d996cae2767b3aea0ca">runOnLoop</a>.</p>

</div>
</div>

### ProvidedFullUnrollMaxCount {#a0e7d1ba1fcb1697c23806f7a2cecb79a}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">std::optional&lt;unsigned&gt; anonymous{LoopUnrollPass.cpp}::LoopUnroll::ProvidedFullUnrollMaxCount</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 1416 of file <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/scalar/loopunrollpass-cpp">LoopUnrollPass.cpp</a>.</p>


<p>Referenced by <a href="#a75e222e94c61c768491fb808096d1953">LoopUnroll</a> and <a href="#a176b0f7a9dc90d996cae2767b3aea0ca">runOnLoop</a>.</p>

</div>
</div>

### ProvidedRuntime {#ae3f69a119b1d6e64f4b47b71184d76ff}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">std::optional&lt;bool&gt; anonymous{LoopUnrollPass.cpp}::LoopUnroll::ProvidedRuntime</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 1412 of file <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/scalar/loopunrollpass-cpp">LoopUnrollPass.cpp</a>.</p>


<p>Referenced by <a href="#a75e222e94c61c768491fb808096d1953">LoopUnroll</a> and <a href="#a176b0f7a9dc90d996cae2767b3aea0ca">runOnLoop</a>.</p>

</div>
</div>

### ProvidedThreshold {#a4b07daef177cac672f67877257bb7e42}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">std::optional&lt;unsigned&gt; anonymous{LoopUnrollPass.cpp}::LoopUnroll::ProvidedThreshold</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 1410 of file <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/scalar/loopunrollpass-cpp">LoopUnrollPass.cpp</a>.</p>


<p>Referenced by <a href="#a75e222e94c61c768491fb808096d1953">LoopUnroll</a> and <a href="#a176b0f7a9dc90d996cae2767b3aea0ca">runOnLoop</a>.</p>

</div>
</div>

### ProvidedUpperBound {#abcbc7bee3077936a0a570f166e149343}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">std::optional&lt;bool&gt; anonymous{LoopUnrollPass.cpp}::LoopUnroll::ProvidedUpperBound</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 1413 of file <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/scalar/loopunrollpass-cpp">LoopUnrollPass.cpp</a>.</p>


<p>Referenced by <a href="#a75e222e94c61c768491fb808096d1953">LoopUnroll</a> and <a href="#a176b0f7a9dc90d996cae2767b3aea0ca">runOnLoop</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Public Static Attributes

### ID {#ad04341bfb03fbed7713ee9ff65c154e8}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">char LoopUnroll::ID = 0</td>
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



<p>Definition at line 1395 of file <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/scalar/loopunrollpass-cpp">LoopUnrollPass.cpp</a>.</p>


<p>Referenced by <a href="#a75e222e94c61c768491fb808096d1953">LoopUnroll</a>.</p>

</div>
</div>

</div>

<hr/>

The documentation for this class was generated from the following file:

<ul>
<li><a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/scalar/loopunrollpass-cpp">LoopUnrollPass.cpp</a></li>
</ul>

<hr/>

<p class="doxyGeneratedBy">Generated via <a href="https://github.com/xpack/doxygen2docusaurus">doxygen2docusaurus</a> by <a href="https://www.doxygen.nl">Doxygen</a> 1.15.0.</p>

</div>
