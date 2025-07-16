---

# DO NOT EDIT!
# Automatically generated via doxygen2docusaurus by Doxygen.

slug: /api/classes/llvm/passinstrumentation
custom_edit_url: null
toc_max_heading_level: 4
keywords:
  - doxygen
  - reference
  - class

---

<div class="doxyPage">

# The `PassInstrumentation` Class Reference

<p>This class provides instrumentation entry points for the <a href="/web-llvm/docs/api/classes/llvm/pass">Pass</a> Manager, doing calls to callbacks registered in <a href="/web-llvm/docs/api/classes/llvm/passinstrumentationcallbacks">PassInstrumentationCallbacks</a>. <a href="#details">More...</a></p>

## Declaration

<div class="doxyDeclaration">
class llvm::PassInstrumentation { ... }
</div>

## Included Headers

<div class="doxyIncludesList">#include "<a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/ir/passinstrumentation-h">llvm/IR/PassInstrumentation.h</a>"
</div>

## Private Member Typedefs Index

<table class="doxyMembersIndex">

<tr class="doxyMemberIndexTemplate">
<td class="doxyMemberIndexTemplate" colspan="2"><div>template &lt;typename PassT&gt;</div></td>
</tr>
<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemTypeTemplate" align="left" valign="top">using</td>
<td class="doxyMemberIndexItemNameTemplate" align="left" valign="top"><a href="#a932d2ac7d58bdfa6e7088b84563f94db">has_required_t</a> = decltype(std::declval&lt; PassT &amp; &gt;().isRequired())</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a405394a2ffc8cc85cd6e6be0e64d1408">PassInstrumentation</a> (PassInstrumentationCallbacks *CB=nullptr)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Callbacks object is not owned by <a href="/web-llvm/docs/api/classes/llvm/passinstrumentation">PassInstrumentation</a>, its life-time should at least match the life-time of corresponding <a href="/web-llvm/docs/api/classes/llvm/passinstrumentationanalysis">PassInstrumentationAnalysis</a> (which usually is till the end of current compilation). <a href="#a405394a2ffc8cc85cd6e6be0e64d1408">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

</table>

## Public Member Functions Index

<table class="doxyMembersIndex">

<tr class="doxyMemberIndexTemplate">
<td class="doxyMemberIndexTemplate" colspan="2"><div>template &lt;typename IRUnitT, typename PassT&gt;</div></td>
</tr>
<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemTypeTemplate" align="left" valign="top">bool</td>
<td class="doxyMemberIndexItemNameTemplate" align="left" valign="top"><a href="#aead32b9af4b66a742d37585c6d6b4cbc">runBeforePass</a> (const PassT &amp;Pass, const IRUnitT &amp;IR) const</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>BeforePass instrumentation point - takes <span class="doxyComputerOutput"><a href="/web-llvm/docs/api/classes/llvm/pass">Pass</a></span> instance to be executed and constant reference to IR it operates on. <a href="#aead32b9af4b66a742d37585c6d6b4cbc">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexTemplate">
<td class="doxyMemberIndexTemplate" colspan="2"><div>template &lt;typename IRUnitT, typename PassT&gt;</div></td>
</tr>
<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemTypeTemplate" align="left" valign="top">void</td>
<td class="doxyMemberIndexItemNameTemplate" align="left" valign="top"><a href="#acec038dce9072b64301f6e5226c5579a">runAfterPass</a> (const PassT &amp;Pass, const IRUnitT &amp;IR, const PreservedAnalyses &amp;PA) const</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>AfterPass instrumentation point - takes <span class="doxyComputerOutput"><a href="/web-llvm/docs/api/classes/llvm/pass">Pass</a></span> instance that has just been executed and constant reference to <span class="doxyComputerOutput">IR</span> it operates on. <a href="#acec038dce9072b64301f6e5226c5579a">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexTemplate">
<td class="doxyMemberIndexTemplate" colspan="2"><div>template &lt;typename IRUnitT, typename PassT&gt;</div></td>
</tr>
<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemTypeTemplate" align="left" valign="top">void</td>
<td class="doxyMemberIndexItemNameTemplate" align="left" valign="top"><a href="#a055d7d34f26a121bd6cd03073cda6529">runAfterPassInvalidated</a> (const PassT &amp;Pass, const PreservedAnalyses &amp;PA) const</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>AfterPassInvalidated instrumentation point - takes <span class="doxyComputerOutput"><a href="/web-llvm/docs/api/classes/llvm/pass">Pass</a></span> instance that has just been executed. <a href="#a055d7d34f26a121bd6cd03073cda6529">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexTemplate">
<td class="doxyMemberIndexTemplate" colspan="2"><div>template &lt;typename IRUnitT, typename PassT&gt;</div></td>
</tr>
<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemTypeTemplate" align="left" valign="top">void</td>
<td class="doxyMemberIndexItemNameTemplate" align="left" valign="top"><a href="#a5a2cc6fe0017dd7067b103118a7bc914">runBeforeAnalysis</a> (const PassT &amp;Analysis, const IRUnitT &amp;IR) const</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>BeforeAnalysis instrumentation point - takes <span class="doxyComputerOutput">Analysis</span> instance to be executed and constant reference to IR it operates on. <a href="#a5a2cc6fe0017dd7067b103118a7bc914">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexTemplate">
<td class="doxyMemberIndexTemplate" colspan="2"><div>template &lt;typename IRUnitT, typename PassT&gt;</div></td>
</tr>
<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemTypeTemplate" align="left" valign="top">void</td>
<td class="doxyMemberIndexItemNameTemplate" align="left" valign="top"><a href="#adda8476ef0007c61013ba8e5c46c6693">runAfterAnalysis</a> (const PassT &amp;Analysis, const IRUnitT &amp;IR) const</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>AfterAnalysis instrumentation point - takes <span class="doxyComputerOutput">Analysis</span> instance that has just been executed and constant reference to IR it operated on. <a href="#adda8476ef0007c61013ba8e5c46c6693">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexTemplate">
<td class="doxyMemberIndexTemplate" colspan="2"><div>template &lt;typename IRUnitT, typename PassT&gt;</div></td>
</tr>
<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemTypeTemplate" align="left" valign="top">void</td>
<td class="doxyMemberIndexItemNameTemplate" align="left" valign="top"><a href="#a698253acb40299131fecdb9489f88fcd">runAnalysisInvalidated</a> (const PassT &amp;Analysis, const IRUnitT &amp;IR) const</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>AnalysisInvalidated instrumentation point - takes <span class="doxyComputerOutput">Analysis</span> instance that has just been invalidated and constant reference to IR it operated on. <a href="#a698253acb40299131fecdb9489f88fcd">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">void</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a79746b86dd505966e089c0b90e810053">runAnalysesCleared</a> (StringRef Name) const</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>AnalysesCleared instrumentation point - takes name of IR that analyses operated on. <a href="#a79746b86dd505966e089c0b90e810053">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexTemplate">
<td class="doxyMemberIndexTemplate" colspan="2"><div>template &lt;typename IRUnitT, typename... ExtraArgsT&gt;</div></td>
</tr>
<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemTypeTemplate" align="left" valign="top">bool</td>
<td class="doxyMemberIndexItemNameTemplate" align="left" valign="top"><a href="#a58242b7112ed65072c3a1e77568d1a6a">invalidate</a> (IRUnitT &amp;, const class llvm::PreservedAnalyses &amp;, ExtraArgsT...)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Handle invalidation from the pass manager when <a href="/web-llvm/docs/api/classes/llvm/passinstrumentation">PassInstrumentation</a> is used as the result of <a href="/web-llvm/docs/api/classes/llvm/passinstrumentationanalysis">PassInstrumentationAnalysis</a>. <a href="#a58242b7112ed65072c3a1e77568d1a6a">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexTemplate">
<td class="doxyMemberIndexTemplate" colspan="2"><div>template &lt;typename CallableT&gt;</div></td>
</tr>
<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemTypeTemplate" align="left" valign="top">void</td>
<td class="doxyMemberIndexItemNameTemplate" align="left" valign="top"><a href="#a3e9514787a065c96294f645b1967f450">pushBeforeNonSkippedPassCallback</a> (CallableT C)</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ab20a8985d0c6fff641ddf9b933b2a886">popBeforeNonSkippedPassCallback</a> ()</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/stringref">StringRef</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a79b8b2488fca01c969f40f133c416e99">getPassNameForClassName</a> (StringRef ClassName) const</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Get the pass name for a given pass class name. <a href="#a79b8b2488fca01c969f40f133c416e99">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

</table>

## Private Member Attributes Index

<table class="doxyMembersIndex">

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/passinstrumentationcallbacks">PassInstrumentationCallbacks</a> *</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#aa36c9efbd63670be8da8a1e26336fe16">Callbacks</a></td>
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

## Private Static Functions Index

<table class="doxyMembersIndex">

<tr class="doxyMemberIndexTemplate">
<td class="doxyMemberIndexTemplate" colspan="2"><div>template &lt;typename PassT&gt;</div></td>
</tr>
<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemTypeTemplate" align="left" valign="top">static auto </td>
<td class="doxyMemberIndexItemNameTemplate" align="left" valign="top"><a href="#a13d4175f125b5c6a43696bd187fd9f2d">isRequired</a> (const PassT &amp;Pass) -&gt; std::enable_if_t&lt; <a href="/web-llvm/docs/api/namespaces/llvm/#abf1ad174f29a434886594433ce8a787f">is_detected</a>&lt; has_required_t, PassT &gt;::value, bool &gt;</td>
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
<td class="doxyMemberIndexTemplate" colspan="2"><div>template &lt;typename PassT&gt;</div></td>
</tr>
<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemTypeTemplate" align="left" valign="top">static auto </td>
<td class="doxyMemberIndexItemNameTemplate" align="left" valign="top"><a href="#a3bce34071dc79eb763c69816b78980f5">isRequired</a> (const PassT &amp;Pass) -&gt; std::enable_if_t&lt;!<a href="/web-llvm/docs/api/namespaces/llvm/#abf1ad174f29a434886594433ce8a787f">is_detected</a>&lt; has_required_t, PassT &gt;::value, bool &gt;</td>
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

<p>This class provides instrumentation entry points for the <a href="/web-llvm/docs/api/classes/llvm/pass">Pass</a> Manager, doing calls to callbacks registered in <a href="/web-llvm/docs/api/classes/llvm/passinstrumentationcallbacks">PassInstrumentationCallbacks</a>.</p>

<p>Definition at line 207 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/ir/passinstrumentation-h">PassInstrumentation.h</a>.</p>


<div class="doxySectionDef">

## Private Member Typedefs

### has\_required\_t {#a932d2ac7d58bdfa6e7088b84563f94db}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<div class="doxyMemberTemplate">template &lt;typename PassT&gt;</div>
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">using llvm::PassInstrumentation::has_required_t =  decltype(std::declval&lt;PassT &amp;&gt;().isRequired())</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 217 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/ir/passinstrumentation-h">PassInstrumentation.h</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Public Constructors

### PassInstrumentation() {#a405394a2ffc8cc85cd6e6be0e64d1408}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">llvm::PassInstrumentation::PassInstrumentation (<a href="/web-llvm/docs/api/classes/llvm/passinstrumentationcallbacks">PassInstrumentationCallbacks</a> * CB=nullptr)</td>
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

<p>Callbacks object is not owned by <a href="/web-llvm/docs/api/classes/llvm/passinstrumentation">PassInstrumentation</a>, its life-time should at least match the life-time of corresponding <a href="/web-llvm/docs/api/classes/llvm/passinstrumentationanalysis">PassInstrumentationAnalysis</a> (which usually is till the end of current compilation).</p>

<p>Definition at line 235 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/ir/passinstrumentation-h">PassInstrumentation.h</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Public Member Functions

### getPassNameForClassName() {#a79b8b2488fca01c969f40f133c416e99}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">StringRef llvm::PassInstrumentation::getPassNameForClassName (<a href="/web-llvm/docs/api/classes/llvm/stringref">StringRef</a> ClassName)</td>
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

<p>Get the pass name for a given pass class name.</p>

<p>Definition at line 345 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/ir/passinstrumentation-h">PassInstrumentation.h</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/classes/llvm/passmanager/#aef5d9142acafceffd14c76b8ddd0fd4e">llvm::PassManager&lt; IRUnitT, AnalysisManagerT, ExtraArgTs &gt;::run</a>.</p>

</div>
</div>

### invalidate() {#a58242b7112ed65072c3a1e77568d1a6a}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<div class="doxyMemberTemplate">template &lt;typename IRUnitT, typename... ExtraArgsT&gt;</div>
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool llvm::PassInstrumentation::invalidate (IRUnitT &amp;, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> class llvm::PreservedAnalyses &amp;, ExtraArgsT...)</td>
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

<p>Handle invalidation from the pass manager when <a href="/web-llvm/docs/api/classes/llvm/passinstrumentation">PassInstrumentation</a> is used as the result of <a href="/web-llvm/docs/api/classes/llvm/passinstrumentationanalysis">PassInstrumentationAnalysis</a>.</p>


<p>On attempt to invalidate just return false. There is nothing to become invalid here.</p>


<p>Definition at line 329 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/ir/passinstrumentation-h">PassInstrumentation.h</a>.</p>

</div>
</div>

### popBeforeNonSkippedPassCallback() {#ab20a8985d0c6fff641ddf9b933b2a886}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void llvm::PassInstrumentation::popBeforeNonSkippedPassCallback ()</td>
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



<p>Definition at line 339 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/ir/passinstrumentation-h">PassInstrumentation.h</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/classes/llvm/functiontolooppassadaptor/#aee681bfb37f62d30a1d0a1f47d73b4f1">llvm::FunctionToLoopPassAdaptor::run</a>.</p>

</div>
</div>

### pushBeforeNonSkippedPassCallback() {#a3e9514787a065c96294f645b1967f450}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<div class="doxyMemberTemplate">template &lt;typename CallableT&gt;</div>
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void llvm::PassInstrumentation::pushBeforeNonSkippedPassCallback (CallableT C)</td>
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



<p>Definition at line 335 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/ir/passinstrumentation-h">PassInstrumentation.h</a>.</p>


<p>Reference <a href="/web-llvm/docs/api/namespaces/llvm/callingconv/#ac6aa1387c4375260e2468eb5a77fdb4cafd841a49aec1539bc88abc8ff9e170fb">llvm::CallingConv::C</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/classes/llvm/functiontolooppassadaptor/#aee681bfb37f62d30a1d0a1f47d73b4f1">llvm::FunctionToLoopPassAdaptor::run</a>.</p>

</div>
</div>

### runAfterAnalysis() {#adda8476ef0007c61013ba8e5c46c6693}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<div class="doxyMemberTemplate">template &lt;typename IRUnitT, typename PassT&gt;</div>
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void llvm::PassInstrumentation::runAfterAnalysis (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> PassT &amp; Analysis, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> IRUnitT &amp; IR)</td>
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

<p>AfterAnalysis instrumentation point - takes <span class="doxyComputerOutput">Analysis</span> instance that has just been executed and constant reference to IR it operated on.</p>

<p>Definition at line 299 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/ir/passinstrumentation-h">PassInstrumentation.h</a>.</p>


<p>References <a href="/web-llvm/docs/api/files/lib/lib/analysis/blockfrequencyinfo-cpp/#a882e33145fd2a17174b47d3f964a6b2d">Analysis</a>, <a href="/web-llvm/docs/api/namespaces/llvm/callingconv/#ac6aa1387c4375260e2468eb5a77fdb4cafd841a49aec1539bc88abc8ff9e170fb">llvm::CallingConv::C</a> and <a href="/web-llvm/docs/api/files/lib/lib/codegen/lib/codegen/globalisel/legalizer-cpp/#a05ab4853f7153e537774d02580e761ec">IR</a>.</p>

</div>
</div>

### runAfterPass() {#acec038dce9072b64301f6e5226c5579a}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<div class="doxyMemberTemplate">template &lt;typename IRUnitT, typename PassT&gt;</div>
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void llvm::PassInstrumentation::runAfterPass (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> PassT &amp; Pass, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> IRUnitT &amp; IR, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> PreservedAnalyses &amp; PA)</td>
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

<p>AfterPass instrumentation point - takes <span class="doxyComputerOutput"><a href="/web-llvm/docs/api/classes/llvm/pass">Pass</a></span> instance that has just been executed and constant reference to <span class="doxyComputerOutput">IR</span> it operates on.</p>


<p><span class="doxyComputerOutput">IR</span> is guaranteed to be valid at this point.</p>


<p>Definition at line 269 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/ir/passinstrumentation-h">PassInstrumentation.h</a>.</p>


<p>References <a href="/web-llvm/docs/api/namespaces/llvm/callingconv/#ac6aa1387c4375260e2468eb5a77fdb4cafd841a49aec1539bc88abc8ff9e170fb">llvm::CallingConv::C</a> and <a href="/web-llvm/docs/api/files/lib/lib/codegen/lib/codegen/globalisel/legalizer-cpp/#a05ab4853f7153e537774d02580e761ec">IR</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/classes/llvm/cgscctofunctionpassadaptor/#a44a083f826f2f2a189d3979eb43dd5ed">llvm::CGSCCToFunctionPassAdaptor::run</a>, <a href="/web-llvm/docs/api/classes/llvm/devirtsccrepeatedpass/#a11597e1847c3156c4866aa0a43a1b71b">llvm::DevirtSCCRepeatedPass::run</a>, <a href="/web-llvm/docs/api/classes/llvm/functiontolooppassadaptor/#aee681bfb37f62d30a1d0a1f47d73b4f1">llvm::FunctionToLoopPassAdaptor::run</a>, <a href="/web-llvm/docs/api/classes/llvm/functiontomachinefunctionpassadaptor/#a1c8aea757190a42fd931c0d95a4f2721">llvm::FunctionToMachineFunctionPassAdaptor::run</a>, <a href="/web-llvm/docs/api/classes/llvm/moduletopostordercgsccpassadaptor/#a0ff99def687659818bdb4a25afd82c94">llvm::ModuleToPostOrderCGSCCPassAdaptor::run</a>, <a href="/web-llvm/docs/api/classes/llvm/passmanager/#aef5d9142acafceffd14c76b8ddd0fd4e">llvm::PassManager&lt; IRUnitT, AnalysisManagerT, ExtraArgTs &gt;::run</a> and <a href="/web-llvm/docs/api/classes/llvm/passmanager/#a6d74effaad77f6ecb91e1806993cda8f">llvm::PassManager&lt; LazyCallGraph::SCC, CGSCCAnalysisManager, LazyCallGraph &amp;, CGSCCUpdateResult &amp; &gt;::run</a>.</p>

</div>
</div>

### runAfterPassInvalidated() {#a055d7d34f26a121bd6cd03073cda6529}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<div class="doxyMemberTemplate">template &lt;typename IRUnitT, typename PassT&gt;</div>
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void llvm::PassInstrumentation::runAfterPassInvalidated (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> PassT &amp; Pass, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> PreservedAnalyses &amp; PA)</td>
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

<p>AfterPassInvalidated instrumentation point - takes <span class="doxyComputerOutput"><a href="/web-llvm/docs/api/classes/llvm/pass">Pass</a></span> instance that has just been executed.</p>


<p>For use when IR has been invalidated by <span class="doxyComputerOutput"><a href="/web-llvm/docs/api/classes/llvm/pass">Pass</a></span> execution.</p>


<p>Definition at line 280 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/ir/passinstrumentation-h">PassInstrumentation.h</a>.</p>


<p>Reference <a href="/web-llvm/docs/api/namespaces/llvm/callingconv/#ac6aa1387c4375260e2468eb5a77fdb4cafd841a49aec1539bc88abc8ff9e170fb">llvm::CallingConv::C</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/classes/llvm/devirtsccrepeatedpass/#a11597e1847c3156c4866aa0a43a1b71b">llvm::DevirtSCCRepeatedPass::run</a>, <a href="/web-llvm/docs/api/classes/llvm/functiontolooppassadaptor/#aee681bfb37f62d30a1d0a1f47d73b4f1">llvm::FunctionToLoopPassAdaptor::run</a>, <a href="/web-llvm/docs/api/classes/llvm/moduletopostordercgsccpassadaptor/#a0ff99def687659818bdb4a25afd82c94">llvm::ModuleToPostOrderCGSCCPassAdaptor::run</a> and <a href="/web-llvm/docs/api/classes/llvm/passmanager/#a6d74effaad77f6ecb91e1806993cda8f">llvm::PassManager&lt; LazyCallGraph::SCC, CGSCCAnalysisManager, LazyCallGraph &amp;, CGSCCUpdateResult &amp; &gt;::run</a>.</p>

</div>
</div>

### runAnalysesCleared() {#a79746b86dd505966e089c0b90e810053}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void llvm::PassInstrumentation::runAnalysesCleared (<a href="/web-llvm/docs/api/classes/llvm/stringref">StringRef</a> Name)</td>
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

<p>AnalysesCleared instrumentation point - takes name of IR that analyses operated on.</p>

<p>Definition at line 317 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/ir/passinstrumentation-h">PassInstrumentation.h</a>.</p>


<p>Reference <a href="/web-llvm/docs/api/namespaces/llvm/callingconv/#ac6aa1387c4375260e2468eb5a77fdb4cafd841a49aec1539bc88abc8ff9e170fb">llvm::CallingConv::C</a>.</p>

</div>
</div>

### runAnalysisInvalidated() {#a698253acb40299131fecdb9489f88fcd}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<div class="doxyMemberTemplate">template &lt;typename IRUnitT, typename PassT&gt;</div>
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void llvm::PassInstrumentation::runAnalysisInvalidated (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> PassT &amp; Analysis, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> IRUnitT &amp; IR)</td>
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

<p>AnalysisInvalidated instrumentation point - takes <span class="doxyComputerOutput">Analysis</span> instance that has just been invalidated and constant reference to IR it operated on.</p>

<p>Definition at line 309 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/ir/passinstrumentation-h">PassInstrumentation.h</a>.</p>


<p>References <a href="/web-llvm/docs/api/files/lib/lib/analysis/blockfrequencyinfo-cpp/#a882e33145fd2a17174b47d3f964a6b2d">Analysis</a>, <a href="/web-llvm/docs/api/namespaces/llvm/callingconv/#ac6aa1387c4375260e2468eb5a77fdb4cafd841a49aec1539bc88abc8ff9e170fb">llvm::CallingConv::C</a> and <a href="/web-llvm/docs/api/files/lib/lib/codegen/lib/codegen/globalisel/legalizer-cpp/#a05ab4853f7153e537774d02580e761ec">IR</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/classes/llvm/analysismanager/#a64b2a209a16bcd41375b5cae12690eaa">llvm::AnalysisManager&lt; IRUnitT, ExtraArgTs &gt;::invalidate</a>.</p>

</div>
</div>

### runBeforeAnalysis() {#a5a2cc6fe0017dd7067b103118a7bc914}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<div class="doxyMemberTemplate">template &lt;typename IRUnitT, typename PassT&gt;</div>
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void llvm::PassInstrumentation::runBeforeAnalysis (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> PassT &amp; Analysis, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> IRUnitT &amp; IR)</td>
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

<p>BeforeAnalysis instrumentation point - takes <span class="doxyComputerOutput">Analysis</span> instance to be executed and constant reference to IR it operates on.</p>

<p>Definition at line 290 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/ir/passinstrumentation-h">PassInstrumentation.h</a>.</p>


<p>References <a href="/web-llvm/docs/api/files/lib/lib/analysis/blockfrequencyinfo-cpp/#a882e33145fd2a17174b47d3f964a6b2d">Analysis</a>, <a href="/web-llvm/docs/api/namespaces/llvm/callingconv/#ac6aa1387c4375260e2468eb5a77fdb4cafd841a49aec1539bc88abc8ff9e170fb">llvm::CallingConv::C</a> and <a href="/web-llvm/docs/api/files/lib/lib/codegen/lib/codegen/globalisel/legalizer-cpp/#a05ab4853f7153e537774d02580e761ec">IR</a>.</p>

</div>
</div>

### runBeforePass() {#aead32b9af4b66a742d37585c6d6b4cbc}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<div class="doxyMemberTemplate">template &lt;typename IRUnitT, typename PassT&gt;</div>
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool llvm::PassInstrumentation::runBeforePass (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> PassT &amp; Pass, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> IRUnitT &amp; IR)</td>
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

<p>BeforePass instrumentation point - takes <span class="doxyComputerOutput"><a href="/web-llvm/docs/api/classes/llvm/pass">Pass</a></span> instance to be executed and constant reference to IR it operates on.</p>


<p>\Returns true if pass is allowed to be executed. These are only run on optional pass since required passes must always be run. This allows these callbacks to print info when they want to skip a pass.</p>


<p>Definition at line 244 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/ir/passinstrumentation-h">PassInstrumentation.h</a>.</p>


<p>References <a href="/web-llvm/docs/api/namespaces/llvm/callingconv/#ac6aa1387c4375260e2468eb5a77fdb4cafd841a49aec1539bc88abc8ff9e170fb">llvm::CallingConv::C</a> and <a href="/web-llvm/docs/api/files/lib/lib/codegen/lib/codegen/globalisel/legalizer-cpp/#a05ab4853f7153e537774d02580e761ec">IR</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/classes/llvm/cgscctofunctionpassadaptor/#a44a083f826f2f2a189d3979eb43dd5ed">llvm::CGSCCToFunctionPassAdaptor::run</a>, <a href="/web-llvm/docs/api/classes/llvm/devirtsccrepeatedpass/#a11597e1847c3156c4866aa0a43a1b71b">llvm::DevirtSCCRepeatedPass::run</a>, <a href="/web-llvm/docs/api/classes/llvm/functiontolooppassadaptor/#aee681bfb37f62d30a1d0a1f47d73b4f1">llvm::FunctionToLoopPassAdaptor::run</a>, <a href="/web-llvm/docs/api/classes/llvm/functiontomachinefunctionpassadaptor/#a1c8aea757190a42fd931c0d95a4f2721">llvm::FunctionToMachineFunctionPassAdaptor::run</a>, <a href="/web-llvm/docs/api/classes/llvm/moduletopostordercgsccpassadaptor/#a0ff99def687659818bdb4a25afd82c94">llvm::ModuleToPostOrderCGSCCPassAdaptor::run</a>, <a href="/web-llvm/docs/api/classes/llvm/passmanager/#aef5d9142acafceffd14c76b8ddd0fd4e">llvm::PassManager&lt; IRUnitT, AnalysisManagerT, ExtraArgTs &gt;::run</a> and <a href="/web-llvm/docs/api/classes/llvm/passmanager/#a6d74effaad77f6ecb91e1806993cda8f">llvm::PassManager&lt; LazyCallGraph::SCC, CGSCCAnalysisManager, LazyCallGraph &amp;, CGSCCUpdateResult &amp; &gt;::run</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Private Member Attributes

### Callbacks {#aa36c9efbd63670be8da8a1e26336fe16}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">PassInstrumentationCallbacks* llvm::PassInstrumentation::Callbacks</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 208 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/ir/passinstrumentation-h">PassInstrumentation.h</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Private Static Functions

### isRequired() {#a13d4175f125b5c6a43696bd187fd9f2d}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<div class="doxyMemberTemplate">template &lt;typename PassT&gt;</div>
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">std::enable_if_t&lt; is_detected&lt; has_required_t, PassT &gt;::value, bool &gt; llvm::PassInstrumentation::isRequired (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> PassT &amp; Pass)</td>
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



<p>Definition at line 221 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/ir/passinstrumentation-h">PassInstrumentation.h</a>.</p>

</div>
</div>

### isRequired() {#a3bce34071dc79eb763c69816b78980f5}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<div class="doxyMemberTemplate">template &lt;typename PassT&gt;</div>
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">std::enable_if_t&lt;!is_detected&lt; has_required_t, PassT &gt;::value, bool &gt; llvm::PassInstrumentation::isRequired (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> PassT &amp; Pass)</td>
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



<p>Definition at line 226 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/ir/passinstrumentation-h">PassInstrumentation.h</a>.</p>

</div>
</div>

</div>

<hr/>

The documentation for this class was generated from the following file:

<ul>
<li><a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/ir/passinstrumentation-h">PassInstrumentation.h</a></li>
</ul>

<hr/>

<p class="doxyGeneratedBy">Generated via <a href="https://github.com/xpack/doxygen2docusaurus">doxygen2docusaurus</a> by <a href="https://www.doxygen.nl">Doxygen</a> 1.15.0.</p>

</div>
