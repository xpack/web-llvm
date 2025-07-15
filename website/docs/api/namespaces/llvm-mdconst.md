---

# DO NOT EDIT!
# Automatically generated via doxygen2docusaurus by Doxygen.

slug: /api/namespaces/llvm/mdconst
custom_edit_url: null
toc_max_heading_level: 4
keywords:
  - doxygen
  - reference
  - namespace

---

<div class="doxyPage">

# The `mdconst` Namespace Reference

<p>Transitional API for extracting constants from <a href="/web-llvm/docs/api/classes/llvm/metadata">Metadata</a>. <a href="#details">More...</a></p>

## Definition

<div class="doxyDefinition">
namespace llvm::mdconst { ... }
</div>

## Namespaces Index

<table class="doxyMembersIndex">

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">namespace</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="/web-llvm/docs/api/namespaces/llvm/mdconst/detail">detail</a></td>
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

<tr class="doxyMemberIndexTemplate">
<td class="doxyMemberIndexTemplate" colspan="2"><div>template &lt;class X, class Y&gt;</div></td>
</tr>
<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemTypeTemplate" align="left" valign="top">auto </td>
<td class="doxyMemberIndexItemNameTemplate" align="left" valign="top"><a href="#a7f12b8ac7462ea82d735ac7d56f6260b">hasa</a> (Y &amp;&amp;MD) -&gt; std::enable_if_t&lt; <a href="/web-llvm/docs/api/structs/llvm/mdconst/detail/isvalidpointer">detail::IsValidPointer</a>&lt; <a href="/web-llvm/docs/api/files/lib/lib/tablegen/tablegenbackendskeleton-cpp/#ab60f28d7a141ac46ccc200176a1bca8b">X</a>, <a href="/web-llvm/docs/api/files/lib/lib/tablegen/tablegenbackendskeleton-cpp/#a262774d3e5186511427e5b2414a85f7f">Y</a> &gt;::value, bool &gt;</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p><a href="/web-llvm/docs/api/namespaces/llvm/check">Check</a> whether <a href="/web-llvm/docs/api/classes/llvm/metadata">Metadata</a> has a <a href="/web-llvm/docs/api/classes/llvm/value">Value</a>. <a href="#a7f12b8ac7462ea82d735ac7d56f6260b">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexTemplate">
<td class="doxyMemberIndexTemplate" colspan="2"><div>template &lt;class X, class Y&gt;</div></td>
</tr>
<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemTypeTemplate" align="left" valign="top">auto </td>
<td class="doxyMemberIndexItemNameTemplate" align="left" valign="top"><a href="#ad793f1ffb5a639cc165da41fc0639b82">hasa</a> (Y &amp;MD) -&gt; std::enable_if_t&lt; <a href="/web-llvm/docs/api/structs/llvm/mdconst/detail/isvalidreference">detail::IsValidReference</a>&lt; <a href="/web-llvm/docs/api/files/lib/lib/tablegen/tablegenbackendskeleton-cpp/#ab60f28d7a141ac46ccc200176a1bca8b">X</a>, <a href="/web-llvm/docs/api/files/lib/lib/tablegen/tablegenbackendskeleton-cpp/#a262774d3e5186511427e5b2414a85f7f">Y</a> &amp; &gt;::value, bool &gt;</td>
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
<td class="doxyMemberIndexTemplate" colspan="2"><div>template &lt;class X, class Y&gt;</div></td>
</tr>
<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemTypeTemplate" align="left" valign="top">auto </td>
<td class="doxyMemberIndexItemNameTemplate" align="left" valign="top"><a href="#ad938857d6c6603847adf3a8cbe403d17">extract</a> (Y &amp;&amp;MD) -&gt; std::enable_if_t&lt; <a href="/web-llvm/docs/api/structs/llvm/mdconst/detail/isvalidpointer">detail::IsValidPointer</a>&lt; <a href="/web-llvm/docs/api/files/lib/lib/tablegen/tablegenbackendskeleton-cpp/#ab60f28d7a141ac46ccc200176a1bca8b">X</a>, <a href="/web-llvm/docs/api/files/lib/lib/tablegen/tablegenbackendskeleton-cpp/#a262774d3e5186511427e5b2414a85f7f">Y</a> &gt;::value, <a href="/web-llvm/docs/api/files/lib/lib/tablegen/tablegenbackendskeleton-cpp/#ab60f28d7a141ac46ccc200176a1bca8b">X</a> * &gt;</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Extract a <a href="/web-llvm/docs/api/classes/llvm/value">Value</a> from <a href="/web-llvm/docs/api/classes/llvm/metadata">Metadata</a>. <a href="#ad938857d6c6603847adf3a8cbe403d17">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexTemplate">
<td class="doxyMemberIndexTemplate" colspan="2"><div>template &lt;class X, class Y&gt;</div></td>
</tr>
<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemTypeTemplate" align="left" valign="top">auto </td>
<td class="doxyMemberIndexItemNameTemplate" align="left" valign="top"><a href="#a28b74e2f39993aedb95e57c013e451b6">extract</a> (Y &amp;MD) -&gt; std::enable_if_t&lt; <a href="/web-llvm/docs/api/structs/llvm/mdconst/detail/isvalidreference">detail::IsValidReference</a>&lt; <a href="/web-llvm/docs/api/files/lib/lib/tablegen/tablegenbackendskeleton-cpp/#ab60f28d7a141ac46ccc200176a1bca8b">X</a>, <a href="/web-llvm/docs/api/files/lib/lib/tablegen/tablegenbackendskeleton-cpp/#a262774d3e5186511427e5b2414a85f7f">Y</a> &amp; &gt;::value, <a href="/web-llvm/docs/api/files/lib/lib/tablegen/tablegenbackendskeleton-cpp/#ab60f28d7a141ac46ccc200176a1bca8b">X</a> * &gt;</td>
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
<td class="doxyMemberIndexTemplate" colspan="2"><div>template &lt;class X, class Y&gt;</div></td>
</tr>
<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemTypeTemplate" align="left" valign="top">auto </td>
<td class="doxyMemberIndexItemNameTemplate" align="left" valign="top"><a href="#a86397deb1d9d25f7a17ce22c4d66482f">extract_or_null</a> (Y &amp;&amp;MD) -&gt; std::enable_if_t&lt; <a href="/web-llvm/docs/api/structs/llvm/mdconst/detail/isvalidpointer">detail::IsValidPointer</a>&lt; <a href="/web-llvm/docs/api/files/lib/lib/tablegen/tablegenbackendskeleton-cpp/#ab60f28d7a141ac46ccc200176a1bca8b">X</a>, <a href="/web-llvm/docs/api/files/lib/lib/tablegen/tablegenbackendskeleton-cpp/#a262774d3e5186511427e5b2414a85f7f">Y</a> &gt;::value, <a href="/web-llvm/docs/api/files/lib/lib/tablegen/tablegenbackendskeleton-cpp/#ab60f28d7a141ac46ccc200176a1bca8b">X</a> * &gt;</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Extract a <a href="/web-llvm/docs/api/classes/llvm/value">Value</a> from <a href="/web-llvm/docs/api/classes/llvm/metadata">Metadata</a>, allowing null. <a href="#a86397deb1d9d25f7a17ce22c4d66482f">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexTemplate">
<td class="doxyMemberIndexTemplate" colspan="2"><div>template &lt;class X, class Y&gt;</div></td>
</tr>
<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemTypeTemplate" align="left" valign="top">auto </td>
<td class="doxyMemberIndexItemNameTemplate" align="left" valign="top"><a href="#ad7ca5290dc5789cbeae763690e6edccf">dyn_extract</a> (Y &amp;&amp;MD) -&gt; std::enable_if_t&lt; <a href="/web-llvm/docs/api/structs/llvm/mdconst/detail/isvalidpointer">detail::IsValidPointer</a>&lt; <a href="/web-llvm/docs/api/files/lib/lib/tablegen/tablegenbackendskeleton-cpp/#ab60f28d7a141ac46ccc200176a1bca8b">X</a>, <a href="/web-llvm/docs/api/files/lib/lib/tablegen/tablegenbackendskeleton-cpp/#a262774d3e5186511427e5b2414a85f7f">Y</a> &gt;::value, <a href="/web-llvm/docs/api/files/lib/lib/tablegen/tablegenbackendskeleton-cpp/#ab60f28d7a141ac46ccc200176a1bca8b">X</a> * &gt;</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Extract a <a href="/web-llvm/docs/api/classes/llvm/value">Value</a> from <a href="/web-llvm/docs/api/classes/llvm/metadata">Metadata</a>, if any. <a href="#ad7ca5290dc5789cbeae763690e6edccf">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexTemplate">
<td class="doxyMemberIndexTemplate" colspan="2"><div>template &lt;class X, class Y&gt;</div></td>
</tr>
<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemTypeTemplate" align="left" valign="top">auto </td>
<td class="doxyMemberIndexItemNameTemplate" align="left" valign="top"><a href="#a2d40c0621205b0cbd5f642d970cbb896">dyn_extract_or_null</a> (Y &amp;&amp;MD) -&gt; std::enable_if_t&lt; <a href="/web-llvm/docs/api/structs/llvm/mdconst/detail/isvalidpointer">detail::IsValidPointer</a>&lt; <a href="/web-llvm/docs/api/files/lib/lib/tablegen/tablegenbackendskeleton-cpp/#ab60f28d7a141ac46ccc200176a1bca8b">X</a>, <a href="/web-llvm/docs/api/files/lib/lib/tablegen/tablegenbackendskeleton-cpp/#a262774d3e5186511427e5b2414a85f7f">Y</a> &gt;::value, <a href="/web-llvm/docs/api/files/lib/lib/tablegen/tablegenbackendskeleton-cpp/#ab60f28d7a141ac46ccc200176a1bca8b">X</a> * &gt;</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Extract a <a href="/web-llvm/docs/api/classes/llvm/value">Value</a> from <a href="/web-llvm/docs/api/classes/llvm/metadata">Metadata</a>, if any, allowing null. <a href="#a2d40c0621205b0cbd5f642d970cbb896">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

</table>

## Description {#details}

<p>Transitional API for extracting constants from <a href="/web-llvm/docs/api/classes/llvm/metadata">Metadata</a>.</p>


<p>This namespace contains transitional functions for metadata that points to <em>Constants</em>.</p>


<p>In prehistory – when metadata was a subclass of <em><a href="/web-llvm/docs/api/classes/llvm/value">Value</a></em> – <em><a href="/web-llvm/docs/api/classes/llvm/mdnode">MDNode</a></em> operands could refer to any <em><a href="/web-llvm/docs/api/classes/llvm/value">Value</a></em>. There's was a lot of code like this:</p>


<div class="doxyProgramListing">

<div class="doxyCodeLine"><span class="doxyNoLineNumber">&nbsp;</span><span class="doxyLineContent"><span class="doxyHighlight"><a href="/web-llvm/docs/api/classes/llvm/mdnode">MDNode</a> *<a href="/web-llvm/docs/api/files/lib/lib/support/regcomp-c/#a0240ac851181b84ac374872dc5434ee4">N</a> = ...;</span></span></div>
<div class="doxyCodeLine"><span class="doxyNoLineNumber">&nbsp;</span><span class="doxyLineContent"><span class="doxyHighlightKeyword">auto</span><span class="doxyHighlight"> *CI = <a href="/web-llvm/docs/api/namespaces/llvm/#a22eeee01734061ac1b31ccd994c49eef">dyn_cast&lt;ConstantInt&gt;</a>(<a href="/web-llvm/docs/api/files/lib/lib/support/regcomp-c/#a0240ac851181b84ac374872dc5434ee4">N</a>-&gt;getOperand(2));</span></span></div>

</div>


<p>Now that <em><a href="/web-llvm/docs/api/classes/llvm/value">Value</a></em> and <em><a href="/web-llvm/docs/api/classes/llvm/metadata">Metadata</a></em> are in separate hierarchies, maintaining the semantics for <em><a href="/web-llvm/docs/api/namespaces/llvm/#a92ca992e52dddc420f4b069cae06dfbe">isa()</a></em>, <em><a href="/web-llvm/docs/api/namespaces/llvm/#ac4fc845f5ed92de63cd4474f128f5fc5">cast()</a></em>, <em><a href="/web-llvm/docs/api/namespaces/llvm/#a22eeee01734061ac1b31ccd994c49eef">dyn_cast()</a></em> (etc.) requires three steps: cast in the <em><a href="/web-llvm/docs/api/classes/llvm/metadata">Metadata</a></em> hierarchy, extraction of the <em><a href="/web-llvm/docs/api/classes/llvm/value">Value</a></em>, and cast in the <em><a href="/web-llvm/docs/api/classes/llvm/value">Value</a></em> hierarchy. Besides creating boiler-plate, this requires subtle control flow changes.</p>


<p>The end-goal is to create a new type of metadata, called (e.g.) <em>MDInt</em>, so that metadata can refer to numbers without traversing a bridge to the <em><a href="/web-llvm/docs/api/classes/llvm/value">Value</a></em> hierarchy. In this final state, the code above would look like this:</p>


<div class="doxyProgramListing">

<div class="doxyCodeLine"><span class="doxyNoLineNumber">&nbsp;</span><span class="doxyLineContent"><span class="doxyHighlight"><a href="/web-llvm/docs/api/classes/llvm/mdnode">MDNode</a> *<a href="/web-llvm/docs/api/files/lib/lib/support/regcomp-c/#a0240ac851181b84ac374872dc5434ee4">N</a> = ...;</span></span></div>
<div class="doxyCodeLine"><span class="doxyNoLineNumber">&nbsp;</span><span class="doxyLineContent"><span class="doxyHighlightKeyword">auto</span><span class="doxyHighlight"> *<a href="/web-llvm/docs/api/files/lib/lib/codegen/lib/codegen/globalisel/irtranslator-cpp/#abe44dfdea65b4f7e11e0a608ab708b76">MI</a> = <a href="/web-llvm/docs/api/namespaces/llvm/#a22eeee01734061ac1b31ccd994c49eef">dyn_cast&lt;MDInt&gt;</a>(<a href="/web-llvm/docs/api/files/lib/lib/support/regcomp-c/#a0240ac851181b84ac374872dc5434ee4">N</a>-&gt;getOperand(2));</span></span></div>

</div>


<p>The API in this namespace supports the transition. <em>MDInt</em> doesn't exist yet, and even once it does, changing each metadata schema to use it is its own mini-project. In the meantime this API prevents us from introducing complex and bug-prone control flow that will disappear in the end. In particular, the above code looks like this:</p>


<div class="doxyProgramListing">

<div class="doxyCodeLine"><span class="doxyNoLineNumber">&nbsp;</span><span class="doxyLineContent"><span class="doxyHighlight"><a href="/web-llvm/docs/api/classes/llvm/mdnode">MDNode</a> *<a href="/web-llvm/docs/api/files/lib/lib/support/regcomp-c/#a0240ac851181b84ac374872dc5434ee4">N</a> = ...;</span></span></div>
<div class="doxyCodeLine"><span class="doxyNoLineNumber">&nbsp;</span><span class="doxyLineContent"><span class="doxyHighlightKeyword">auto</span><span class="doxyHighlight"> *CI = <a href="#ad7ca5290dc5789cbeae763690e6edccf">mdconst::dyn_extract&lt;ConstantInt&gt;</a>(<a href="/web-llvm/docs/api/files/lib/lib/support/regcomp-c/#a0240ac851181b84ac374872dc5434ee4">N</a>-&gt;getOperand(2));</span></span></div>

</div>


<p>The full set of provided functions includes:</p>


<p><a href="#a7f12b8ac7462ea82d735ac7d56f6260b">mdconst::hasa</a> &lt;=&gt; isa <a href="#ad938857d6c6603847adf3a8cbe403d17">mdconst::extract</a> &lt;=&gt; cast <a href="#a86397deb1d9d25f7a17ce22c4d66482f">mdconst::extract_or_null</a> &lt;=&gt; cast_or_null <a href="#ad7ca5290dc5789cbeae763690e6edccf">mdconst::dyn_extract</a> &lt;=&gt; dyn_cast <a href="#a2d40c0621205b0cbd5f642d970cbb896">mdconst::dyn_extract_or_null</a> &lt;=&gt; dyn_cast_or_null</p>


<p>The target of the cast must be a subclass of <em><a href="/web-llvm/docs/api/classes/llvm/constant">Constant</a></em>.</p>


<div class="doxySectionDef">

## Functions

### dyn\_extract() {#ad7ca5290dc5789cbeae763690e6edccf}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<div class="doxyMemberTemplate">template &lt;class X, class Y&gt;</div>
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">std::enable_if_t&lt; detail::IsValidPointer&lt; X, Y &gt;::value, X * &gt; llvm::mdconst::dyn_extract (<a href="/web-llvm/docs/api/files/lib/lib/tablegen/tablegenbackendskeleton-cpp/#a262774d3e5186511427e5b2414a85f7f">Y</a> &amp;&amp; MD)</td>
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

<p>Extract a <a href="/web-llvm/docs/api/classes/llvm/value">Value</a> from <a href="/web-llvm/docs/api/classes/llvm/metadata">Metadata</a>, if any.</p>


<p>As an analogue to <em><a href="/web-llvm/docs/api/namespaces/llvm/#a5f6182886dc2f96c204299e92c1565d5">dyn_cast_or_null()</a></em>, extract the <em><a href="/web-llvm/docs/api/classes/llvm/value">Value</a></em> subclass <span class="doxyComputerOutput">X</span> from <span class="doxyComputerOutput">MD</span>, return null if <span class="doxyComputerOutput">MD</span> doesn't contain a <em><a href="/web-llvm/docs/api/classes/llvm/value">Value</a></em> or if the <em><a href="/web-llvm/docs/api/classes/llvm/value">Value</a></em> it does contain is of the wrong subclass.</p>


<p>Definition at line 698 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/ir/metadata-h">Metadata.h</a>.</p>


<p>References <a href="/web-llvm/docs/api/namespaces/llvm/#a22eeee01734061ac1b31ccd994c49eef">llvm::dyn_cast</a> and <a href="/web-llvm/docs/api/files/lib/lib/tablegen/tablegenbackendskeleton-cpp/#a262774d3e5186511427e5b2414a85f7f">Y</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/classes/llvm/memprof/callstacktrie/#a0a4dd5e0dc9edbcc395f80456856acb0">llvm::memprof::CallStackTrie::addCallStack</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#aec2c920f97cffa508fee51ee5e722056">llvm::buildOpSpirvDecorations</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a78b74816ecfd86997bf31b5bc2eb0cd1">llvm::cacheAnnotationFromMD</a>, <a href="/web-llvm/docs/api/files/lib/lib/analysis/modulesummaryanalysis-cpp/#a9b06152b51259f884261bba3099e4fc6">computeFunctionSummary</a>, <a href="/web-llvm/docs/api/classes/llvm/targetloweringobjectfileelf/#a3a90d46a868772348b417ed1a94b3a94">llvm::TargetLoweringObjectFileELF::emitModuleMetadata</a>, <a href="/web-llvm/docs/api/namespaces/anonymous-profdatautils-cpp-/#ab93f9a286fcf61c8d72594caa6aa7ddc">anonymous{ProfDataUtils.cpp}::extractFromBranchWeightMD</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a17c107232f5b1b3c9b7da7402b873562">llvm::extractProfTotalWeight</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a0f15483bad46a33489608d861c49b338">llvm::getAlign</a>, <a href="/web-llvm/docs/api/structs/llvm/dotgraphtraits-55c8cb82503f51812ad190e425a6fd3d/#a02f466eae018c75689a0189cb5f29524">llvm::DOTGraphTraits&lt; DOTFuncInfo * &gt;::getEdgeAttributes</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/r600openclimagetypeloweringpass-cpp/#a5bfeca5996966d19706f2a277e7c2341">GetFunctionFromMDNode</a>, <a href="/web-llvm/docs/api/files/lib/lib/codegen/machinemoduleinfo-cpp/#a84b611106739b9bc347338219f73be29">getLocCookie</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a8f6ad5c1831928ee2c6c5058d9580edf">llvm::getValueProfDataFromInst</a>, <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/utils/inlinefunction-cpp/#af7016ec74e60284d198d9b70ec8f1ab2">haveCommonPrefix</a>, <a href="/web-llvm/docs/api/files/lib/lib/ir/verifier-cpp/#a0a03ab42c7fa3946768768795b277c8e">IsScalarTBAANodeImpl</a>, <a href="/web-llvm/docs/api/classes/anonymous-typebasedaliasanalysis-cpp-/tbaanodeimpl/#a9bbbef7a85885dd5bd420999d6f6d86c">anonymous{TypeBasedAliasAnalysis.cpp}::TBAANodeImpl&lt; const MDNode &gt;::isTypeImmutable</a>, <a href="/web-llvm/docs/api/classes/anonymous-typebasedaliasanalysis-cpp-/tbaastructtagnodeimpl/#a39bda24e1c076b046f74704651743443">anonymous{TypeBasedAliasAnalysis.cpp}::TBAAStructTagNodeImpl&lt; const MDNode &gt;::isTypeImmutable</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a4d5216a94e3d3c5aced721cc4f25dc7e">llvm::mayHaveValueProfileOfKind</a>, <a href="/web-llvm/docs/api/classes/anonymous-memprofcontextdisambiguation-cpp-/modulecallsitecontextgraph/#aeefc570485efea4da856d33ef3d16f2a">anonymous{MemProfContextDisambiguation.cpp}::ModuleCallsiteContextGraph::ModuleCallsiteContextGraph</a>, <a href="/web-llvm/docs/api/classes/llvm/pseudoprobemanager/#ae7e567473787718c86fee7cfd653dbbf">llvm::PseudoProbeManager::PseudoProbeManager</a>, <a href="/web-llvm/docs/api/classes/llvm/amdgpupalmetadata/#a93d8a5bd0e7677224b9705f4bea047f9">llvm::AMDGPUPALMetadata::readFromIR</a> and <a href="/web-llvm/docs/api/namespaces/llvm/#af38c031cd1488ca8f80ada31b3df9eac">llvm::scaleProfData</a>.</p>

</div>
</div>

### dyn\_extract\_or\_null() {#a2d40c0621205b0cbd5f642d970cbb896}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<div class="doxyMemberTemplate">template &lt;class X, class Y&gt;</div>
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">std::enable_if_t&lt; detail::IsValidPointer&lt; X, Y &gt;::value, X * &gt; llvm::mdconst::dyn_extract_or_null (<a href="/web-llvm/docs/api/files/lib/lib/tablegen/tablegenbackendskeleton-cpp/#a262774d3e5186511427e5b2414a85f7f">Y</a> &amp;&amp; MD)</td>
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

<p>Extract a <a href="/web-llvm/docs/api/classes/llvm/value">Value</a> from <a href="/web-llvm/docs/api/classes/llvm/metadata">Metadata</a>, if any, allowing null.</p>


<p>As an analogue to <em><a href="/web-llvm/docs/api/namespaces/llvm/#a5f6182886dc2f96c204299e92c1565d5">dyn_cast_or_null()</a></em>, extract the <em><a href="/web-llvm/docs/api/classes/llvm/value">Value</a></em> subclass <span class="doxyComputerOutput">X</span> from <span class="doxyComputerOutput">MD</span>, return null if <span class="doxyComputerOutput">MD</span> doesn't contain a <em><a href="/web-llvm/docs/api/classes/llvm/value">Value</a></em> or if the <em><a href="/web-llvm/docs/api/classes/llvm/value">Value</a></em> it does contain is of the wrong subclass, allowing <span class="doxyComputerOutput">MD</span> to be null.</p>


<p>Definition at line 711 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/ir/metadata-h">Metadata.h</a>.</p>


<p>References <a href="/web-llvm/docs/api/namespaces/llvm/#a22eeee01734061ac1b31ccd994c49eef">llvm::dyn_cast</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a5f6182886dc2f96c204299e92c1565d5">llvm::dyn_cast_or_null</a> and <a href="/web-llvm/docs/api/files/lib/lib/tablegen/tablegenbackendskeleton-cpp/#a262774d3e5186511427e5b2414a85f7f">Y</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/namespaces/llvm/#a3a75955141a4289e3ff78d21aea406a6">llvm::cacheAnnotationFromMD</a>, <a href="/web-llvm/docs/api/namespaces/anonymous-offloadbinary-cpp-/#a0f076ea04eda5249d0527c704881cdf1">anonymous{OffloadBinary.cpp}::extractFromBitcode</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a96bf50345388bc1f2d3727ac83477b05">llvm::getDebugMetadataVersionFromModule</a>, <a href="/web-llvm/docs/api/namespaces/llvm/omp/#a7f2eade374bf61ed94ab98b04803a079">llvm::omp::getDeviceKernels</a>, <a href="/web-llvm/docs/api/structs/anonymous-attributorattributes-cpp-/aaindirectcallinfocallsite/#a30d8d29c9510e2f8b7f6244979fc9376">anonymous{AttributorAttributes.cpp}::AAIndirectCallInfoCallSite::initialize</a>, <a href="/web-llvm/docs/api/structs/anonymous-typesanitizer-cpp-/typesanitizer/#aa8094f0b4dd7316f56198f0e4760b9b4">anonymous{TypeSanitizer.cpp}::TypeSanitizer::instrumentGlobals</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#ad3c29183c5faa7f5a352807af8aca268">llvm::UpgradeDebugInfo</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a40c011ab750e2b4ea0d6b8076345cb0c">llvm::UpgradeModuleFlags</a> and <a href="/web-llvm/docs/api/classes/llvm/tbaaverifier/#a673dcb43872b8c1bd019eff06545c746">llvm::TBAAVerifier::visitTBAAMetadata</a>.</p>

</div>
</div>

### extract() {#ad938857d6c6603847adf3a8cbe403d17}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<div class="doxyMemberTemplate">template &lt;class X, class Y&gt;</div>
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">std::enable_if_t&lt; detail::IsValidPointer&lt; X, Y &gt;::value, X * &gt; llvm::mdconst::extract (<a href="/web-llvm/docs/api/files/lib/lib/tablegen/tablegenbackendskeleton-cpp/#a262774d3e5186511427e5b2414a85f7f">Y</a> &amp;&amp; MD)</td>
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

<p>Extract a <a href="/web-llvm/docs/api/classes/llvm/value">Value</a> from <a href="/web-llvm/docs/api/classes/llvm/metadata">Metadata</a>.</p>


<p>As an analogue to <em><a href="/web-llvm/docs/api/namespaces/llvm/#ac4fc845f5ed92de63cd4474f128f5fc5">cast()</a></em>, extract the <em><a href="/web-llvm/docs/api/classes/llvm/value">Value</a></em> subclass <span class="doxyComputerOutput">X</span> from <span class="doxyComputerOutput">MD</span>.</p>


<p>Definition at line 670 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/ir/metadata-h">Metadata.h</a>.</p>


<p>References <a href="/web-llvm/docs/api/namespaces/llvm/#ac4fc845f5ed92de63cd4474f128f5fc5">llvm::cast</a> and <a href="/web-llvm/docs/api/files/lib/lib/tablegen/tablegenbackendskeleton-cpp/#a262774d3e5186511427e5b2414a85f7f">Y</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/structs/llvm/aamdnodes/#a9c82bb8e10db405d4dd265c150fc52b9">llvm::AAMDNodes::adjustForAccess</a>, <a href="/web-llvm/docs/api/namespaces/anonymous-machinedebugify-cpp-/#aa828309ad55f30355cd07c12017a2263">anonymous{MachineDebugify.cpp}::applyDebugifyMetadataToMachineFunction</a>, <a href="/web-llvm/docs/api/namespaces/anonymous-debugify-cpp-/#aa39f65efac3a51f3001285439ea997be">anonymous{Debugify.cpp}::checkDebugifyMetadata</a>, <a href="/web-llvm/docs/api/files/lib/lib/analysis/dxilmetadataanalysis-cpp/#ab109200c3fd91dd6bf0176734ad64b1f">collectMetadataInfo</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#ae277e0144afb92a90c24163fb4898f02">llvm::computeKnownBitsFromRangeMetadata</a>, <a href="/web-llvm/docs/api/classes/llvm/mdbuilder/#ad1cfc11850432a4ab7d952d5f71ad94f">llvm::MDBuilder::createMutableTBAAAccessTag</a>, <a href="/web-llvm/docs/api/classes/llvm/spirvstructurizer/#a52c61b3548ffc6f5088b78dc45141354">llvm::SPIRVStructurizer::createOpSelectMerge</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a259334992127b809a034f025fc2bd13f">llvm::diagnoseDontCall</a>, <a href="/web-llvm/docs/api/classes/anonymous-globalmerge-cpp-/globalmerge/#abe9c261f5762d1873822f0635616e14e">anonymous{GlobalMerge.cpp}::GlobalMerge::doInitialization</a>, <a href="/web-llvm/docs/api/classes/llvm/machineinstr/#ad72245681f0ae02a2d4574d434bc813d">llvm::MachineInstr::emitInlineAsmError</a>, <a href="/web-llvm/docs/api/classes/llvm/asmprinter/#ab27b01af2db172cdd69c11c9b4888ecc">llvm::AsmPrinter::emitKCFITypeId</a>, <a href="/web-llvm/docs/api/classes/llvm/x86asmprinter/#a09f6957ce3faffb065b97517e5a5ff76">llvm::X86AsmPrinter::emitKCFITypeId</a>, <a href="/web-llvm/docs/api/classes/llvm/amdgpu/hsamd/metadatastreamermsgpackv4/#a2877b4f51a65483c451edd59a4704df6">llvm::AMDGPU::HSAMD::MetadataStreamerMsgPackV4::emitKernelAttrs</a>, <a href="/web-llvm/docs/api/classes/llvm/amdgpu/hsamd/metadatastreamermsgpackv4/#a161232fcda35d33312029e1d80015b77">llvm::AMDGPU::HSAMD::MetadataStreamerMsgPackV4::emitKernelLanguage</a>, <a href="/web-llvm/docs/api/structs/llvm/aamdnodes/#a53468ec93dc5de2584b89a719ab34627">llvm::AAMDNodes::extendToTBAA</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a17c107232f5b1b3c9b7da7402b873562">llvm::extractProfTotalWeight</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/siisellowering-cpp/#a143f6e9097d500daf23fa6ff6a38d774">flatInstrMayAccessPrivate</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a5193c3535375c450b9430e5671cbeb2d">llvm::getConstantRangeFromMetadata</a>, <a href="/web-llvm/docs/api/classes/anonymous-typebasedaliasanalysis-cpp-/tbaastructtypenode/#adf4acdd27d93ff0b0eec8cda6af26de3">anonymous{TypeBasedAliasAnalysis.cpp}::TBAAStructTypeNode::getField</a>, <a href="/web-llvm/docs/api/classes/llvm/fpmathoperator/#af50d863c0e5a39ec42b567a9ea58e351">llvm::FPMathOperator::getFPAccuracy</a>, <a href="/web-llvm/docs/api/classes/llvm/amdgpumachinefunction/#a13726c00b6a447734d47ecaae49ebbd0">llvm::AMDGPUMachineFunction::getLDSKernelIdMetadata</a>, <a href="/web-llvm/docs/api/classes/llvm/riscvelftargetobjectfile/#a64aceaab78ebf55cdbd3e08b2745a2ff">llvm::RISCVELFTargetObjectFile::getModuleMetadata</a>, <a href="/web-llvm/docs/api/classes/llvm/mdnode/#af9b9a04442e0f04f60751aca1783ff3b">llvm::MDNode::getMostGenericAlignmentOrDereferenceable</a>, <a href="/web-llvm/docs/api/classes/llvm/mdnode/#a9d9f2d817781a31c771406d1f0acc9fb">llvm::MDNode::getMostGenericFPMath</a>, <a href="/web-llvm/docs/api/classes/llvm/mdnode/#a45a64ff2883d51edeb926ee63a4f64ac">llvm::MDNode::getMostGenericNoaliasAddrspace</a>, <a href="/web-llvm/docs/api/classes/llvm/mdnode/#aac6e3a0dec40a6721857cbbd4330039f">llvm::MDNode::getMostGenericRange</a>, <a href="/web-llvm/docs/api/files/lib/lib/codegen/targetloweringobjectfileimpl-cpp/#a2cf0a64393382f9a3115486212dfddda">GetObjCImageInfo</a>, <a href="/web-llvm/docs/api/classes/anonymous-typebasedaliasanalysis-cpp-/tbaastructtagnodeimpl/#ac0ef6a49277ded57ff3f304cd9288863">anonymous{TypeBasedAliasAnalysis.cpp}::TBAAStructTagNodeImpl&lt; const MDNode &gt;::getOffset</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/amdgpusubtarget-cpp/#ae13c4e3a2e5393fa5bfd4c32d216e475">getReqdWorkGroupSize</a>, <a href="/web-llvm/docs/api/classes/anonymous-typebasedaliasanalysis-cpp-/tbaastructtagnodeimpl/#a17860fdaf03e300a82ca6974cb0769cc">anonymous{TypeBasedAliasAnalysis.cpp}::TBAAStructTagNodeImpl&lt; const MDNode &gt;::getSize</a>, <a href="/web-llvm/docs/api/classes/llvm/switchinstprofupdatewrapper/#ae6106a112dcb8e7f6b615d746d5bcfc2">llvm::SwitchInstProfUpdateWrapper::getSuccessorWeight</a>, <a href="/web-llvm/docs/api/classes/llvm/amdgpu/hsamd/metadatastreamermsgpackv4/#a0fa4b05292a7268cac4e8261332c3706">llvm::AMDGPU::HSAMD::MetadataStreamerMsgPackV4::getWorkGroupDimensions</a>, <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/utils/dxilupgrade-cpp/#a55a5c0652f51a63dc1ad0f386fe011f2">handleValVerMetadata</a>, <a href="/web-llvm/docs/api/structs/anonymous-attributorattributes-cpp-/aavalueconstantrangeimpl/#a745987cc07ad13e3d1b5e07ea6d8e78f">anonymous{AttributorAttributes.cpp}::AAValueConstantRangeImpl::isBetterRange</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/amdgpulowerkernelattributes-cpp/#aec05cafc12b1852dbd16670773d4f00d">processUse</a>, <a href="/web-llvm/docs/api/files/lib/lib/analysis/valuetracking-cpp/#a134a163243f828943859b5327c73604d">rangeMetadataExcludesValue</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a1b14864699b62834e6644a2692c3743e">llvm::readIntVecFromMDNode</a>, <a href="/web-llvm/docs/api/structs/anonymous-machinecheckdebugify-cpp-/checkdebugmachinemodule/#a326b0f33afafa16b37d37f736e52bf5e">anonymous{MachineCheckDebugify.cpp}::CheckDebugMachineModule::runOnModule</a>, <a href="/web-llvm/docs/api/files/lib/lib/codegen/machinefunction-cpp/#adfbf235872b70098310f84ace07f312a">setUnsafeStackSize</a>, <a href="/web-llvm/docs/api/structs/llvm/aamdnodes/#a25af03cf36c07d235f487e525e5dcd07">llvm::AAMDNodes::shiftTBAAStruct</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/directx/dxiltranslatemetadata-cpp/#ab10b653a914cecca232400be7a563633">translateBranchMetadata</a>, <a href="/web-llvm/docs/api/namespaces/anonymous-amdgpuunifymetadata-cpp-/#a42808949a508a2f6e635b6ae584adcd5">anonymous{AMDGPUUnifyMetadata.cpp}::unifyVersionMD</a>, <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/scalar/loopunrollandjampass-cpp/#aba61ac3543c189773a7afba5d9a6b333">unrollAndJamCountPragmaValue</a>, <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/scalar/loopunrollpass-cpp/#a4f441813911ba060dc9457d93d289527">unrollCountPragmaValue</a>, <a href="/web-llvm/docs/api/structs/anonymous-machineverifier-cpp-/machineverifier/#abdca91902881772e4b8e135a14ff1223">anonymous{MachineVerifier.cpp}::MachineVerifier::verifyPreISelGenericInstruction</a> and <a href="/web-llvm/docs/api/classes/anonymous-amdgpucodegenprepare-cpp-/amdgpucodegenprepareimpl/#a3542900427118365bd67a1d1f4336a50">anonymous{AMDGPUCodeGenPrepare.cpp}::AMDGPUCodeGenPrepareImpl::visitLoadInst</a>.</p>

</div>
</div>

### extract() {#a28b74e2f39993aedb95e57c013e451b6}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<div class="doxyMemberTemplate">template &lt;class X, class Y&gt;</div>
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">std::enable_if_t&lt; detail::IsValidReference&lt; X, Y &amp; &gt;::value, X * &gt; llvm::mdconst::extract (<a href="/web-llvm/docs/api/files/lib/lib/tablegen/tablegenbackendskeleton-cpp/#a262774d3e5186511427e5b2414a85f7f">Y</a> &amp; MD)</td>
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



<p>Definition at line 675 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/ir/metadata-h">Metadata.h</a>.</p>


<p>References <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/ipo/loopextractor-cpp/#a84dff14934298a71113ab11312c243f6">extract</a> and <a href="/web-llvm/docs/api/files/lib/lib/tablegen/tablegenbackendskeleton-cpp/#a262774d3e5186511427e5b2414a85f7f">Y</a>.</p>

</div>
</div>

### extract\_or\_null() {#a86397deb1d9d25f7a17ce22c4d66482f}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<div class="doxyMemberTemplate">template &lt;class X, class Y&gt;</div>
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">std::enable_if_t&lt; detail::IsValidPointer&lt; X, Y &gt;::value, X * &gt; llvm::mdconst::extract_or_null (<a href="/web-llvm/docs/api/files/lib/lib/tablegen/tablegenbackendskeleton-cpp/#a262774d3e5186511427e5b2414a85f7f">Y</a> &amp;&amp; MD)</td>
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

<p>Extract a <a href="/web-llvm/docs/api/classes/llvm/value">Value</a> from <a href="/web-llvm/docs/api/classes/llvm/metadata">Metadata</a>, allowing null.</p>


<p>As an analogue to <em><a href="/web-llvm/docs/api/namespaces/llvm/#a3e627c32543ca70720c4270a8b11da3f">cast_or_null()</a></em>, extract the <em><a href="/web-llvm/docs/api/classes/llvm/value">Value</a></em> subclass <span class="doxyComputerOutput">X</span> from <span class="doxyComputerOutput">MD</span>, allowing <span class="doxyComputerOutput">MD</span> to be null.</p>


<p>Definition at line 685 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/ir/metadata-h">Metadata.h</a>.</p>


<p>References <a href="/web-llvm/docs/api/namespaces/llvm/#ac4fc845f5ed92de63cd4474f128f5fc5">llvm::cast</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a3e627c32543ca70720c4270a8b11da3f">llvm::cast_or_null</a> and <a href="/web-llvm/docs/api/files/lib/lib/tablegen/tablegenbackendskeleton-cpp/#a262774d3e5186511427e5b2414a85f7f">Y</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/classes/llvm/aarch64functioninfo/#a9fd3cdd22c698232d4998d7b3ea7b21a">llvm::AArch64FunctionInfo::AArch64FunctionInfo</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a55c9054d63d1c6a39e9c09ba13a482fa">llvm::addStringMetadataToLoop</a>, <a href="/web-llvm/docs/api/classes/llvm/codeviewdebug/#a435833d0fa51b89ed044e840a28833a0">llvm::CodeViewDebug::beginModule</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a49170e37072dd286a1fcf76f2efec373">llvm::buildModuleSummaryIndex</a>, <a href="/web-llvm/docs/api/files/lib/lib/analysis/modulesummaryanalysis-cpp/#a9b06152b51259f884261bba3099e4fc6">computeFunctionSummary</a>, <a href="/web-llvm/docs/api/classes/anonymous-cfguard-cpp-/cfguardimpl/#a27b401b3a141c64a98a51bafa9c8efdc">anonymous{CFGuard.cpp}::CFGuardImpl::doInitialization</a>, <a href="/web-llvm/docs/api/classes/llvm/asmprinter/#a7cd6d58462a0ebf3fa2c3d1423b0e2c6">llvm::AsmPrinter::doInitialization</a>, <a href="/web-llvm/docs/api/classes/anonymous-aarch64asmprinter-cpp-/aarch64asmprinter/#adae657ab9991540e975726434ee1f053">anonymous{AArch64AsmPrinter.cpp}::AArch64AsmPrinter::emitStartOfAsmFile</a>, <a href="/web-llvm/docs/api/namespaces/anonymous-thinltobitcodewriter-cpp-/#a14e7e537714cbb346b1e6e0eae12fdf5">anonymous{ThinLTOBitcodeWriter.cpp}::enableSplitLTOUnit</a>, <a href="/web-llvm/docs/api/namespaces/anonymous-thinltobitcodewriter-cpp-/#a3c9fb1dd04a5625722582e1806f21fa6">anonymous{ThinLTOBitcodeWriter.cpp}::enableUnifiedLTO</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/nvptx/nvvmreflect-cpp/#ae25b1e577bcd72ebc8b84b83aca02662">for</a>, <a href="/web-llvm/docs/api/namespaces/llvm/amdgpu/#a5f9a0bcc6ecfeef7109258c6a8012978">llvm::AMDGPU::getAMDHSACodeObjectVersion</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a1ec7886622fff3c19833d6c516d4d461">llvm::getOptionalBoolLoopAttribute</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a9b3cfe2d1603665824476c30368b8eb1">llvm::getOptionalIntLoopAttribute</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/systemz/systemzasmprinter-cpp/#af90e8068e4cb52d95a5710879e6ab2bb">getProductPatch</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/systemz/systemzasmprinter-cpp/#aec5822942c1ed04983601ae2467fa6d3">getProductRelease</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/systemz/systemzasmprinter-cpp/#a90ad5d613d92eb50b159c315fbadc4b7">getProductVersion</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/systemz/systemzasmprinter-cpp/#ac6378fb3661a1cfeba49f326fbd0df88">getTranslationTime</a>, <a href="/web-llvm/docs/api/classes/llvm/amdgputtiimpl/#a99fc6c25163b324f8642658b54e77687">llvm::AMDGPUTTIImpl::getUnrollingPreferences</a>, <a href="/web-llvm/docs/api/namespaces/llvm/anonymous-amdgpusplitmodule-cpp-/#a4f04c6f908fc9d132e025f31d40fc976">llvm::anonymous{AMDGPUSplitModule.cpp}::handleCalleesMD</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64machinefunctioninfo-cpp/#a94b61556b849102cdcace07d0a404434">hasELFSignedGOTHelper</a>, <a href="/web-llvm/docs/api/namespaces/llvm/lowertypetests/#ab6535371eaec8620c84bbb0689535dbb">llvm::lowertypetests::isJumpTableCanonical</a>, <a href="/web-llvm/docs/api/classes/llvm/machinemoduleinfoelf/#a10fcc9cad3c4fe08af16f7ca8c14110d">llvm::MachineModuleInfoELF::MachineModuleInfoELF</a>, <a href="/web-llvm/docs/api/classes/llvm/riscvmachinefunctioninfo/#a7a4a4089f8f04bc4d76b68399bdb6099">llvm::RISCVMachineFunctionInfo::RISCVMachineFunctionInfo</a>, <a href="/web-llvm/docs/api/classes/anonymous-aarch64arm64eccalllowering-cpp-/aarch64arm64eccalllowering/#a7b0a136ac6a10743ef5d3cbc1ee0190e">anonymous{AArch64Arm64ECCallLowering.cpp}::AArch64Arm64ECCallLowering::runOnModule</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#ac3dadc94dc9df93690ba937226744797">llvm::setKCFIType</a> and <a href="/web-llvm/docs/api/classes/anonymous-bitcodewriter-cpp-/modulebitcodewriterbase/#ad8b12ebb23f57815dfdaa7a14562aa5f">anonymous{BitcodeWriter.cpp}::ModuleBitcodeWriterBase::writePerModuleGlobalValueSummary</a>.</p>

</div>
</div>

### hasa() {#a7f12b8ac7462ea82d735ac7d56f6260b}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<div class="doxyMemberTemplate">template &lt;class X, class Y&gt;</div>
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">std::enable_if_t&lt; detail::IsValidPointer&lt; X, Y &gt;::value, bool &gt; llvm::mdconst::hasa (<a href="/web-llvm/docs/api/files/lib/lib/tablegen/tablegenbackendskeleton-cpp/#a262774d3e5186511427e5b2414a85f7f">Y</a> &amp;&amp; MD)</td>
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

<p><a href="/web-llvm/docs/api/namespaces/llvm/check">Check</a> whether <a href="/web-llvm/docs/api/classes/llvm/metadata">Metadata</a> has a <a href="/web-llvm/docs/api/classes/llvm/value">Value</a>.</p>


<p>As an analogue to <em><a href="/web-llvm/docs/api/namespaces/llvm/#a92ca992e52dddc420f4b069cae06dfbe">isa()</a></em>, check whether <span class="doxyComputerOutput">MD</span> has an <em><a href="/web-llvm/docs/api/classes/llvm/value">Value</a></em> inside of type <span class="doxyComputerOutput">X</span>.</p>


<p>Definition at line 653 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/ir/metadata-h">Metadata.h</a>.</p>


<p>References <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/silowercontrolflow-cpp/#a4868c5d81c5ccc98c47aeab6244346a0">assert</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a22eeee01734061ac1b31ccd994c49eef">llvm::dyn_cast</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a92ca992e52dddc420f4b069cae06dfbe">llvm::isa</a> and <a href="/web-llvm/docs/api/files/lib/lib/tablegen/tablegenbackendskeleton-cpp/#a262774d3e5186511427e5b2414a85f7f">Y</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/structs/llvm/aamdnodes/#a9c82bb8e10db405d4dd265c150fc52b9">llvm::AAMDNodes::adjustForAccess</a>, <a href="/web-llvm/docs/api/classes/llvm/machineinstr/#aea65fa322ddcff0ca4cd6f83ccef77e0">llvm::MachineInstr::getLocCookieMD</a> and <a href="#ad793f1ffb5a639cc165da41fc0639b82">hasa</a>.</p>

</div>
</div>

### hasa() {#ad793f1ffb5a639cc165da41fc0639b82}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<div class="doxyMemberTemplate">template &lt;class X, class Y&gt;</div>
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">std::enable_if_t&lt; detail::IsValidReference&lt; X, Y &amp; &gt;::value, bool &gt; llvm::mdconst::hasa (<a href="/web-llvm/docs/api/files/lib/lib/tablegen/tablegenbackendskeleton-cpp/#a262774d3e5186511427e5b2414a85f7f">Y</a> &amp; MD)</td>
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



<p>Definition at line 661 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/ir/metadata-h">Metadata.h</a>.</p>


<p>References <a href="#a7f12b8ac7462ea82d735ac7d56f6260b">hasa</a> and <a href="/web-llvm/docs/api/files/lib/lib/tablegen/tablegenbackendskeleton-cpp/#a262774d3e5186511427e5b2414a85f7f">Y</a>.</p>

</div>
</div>

</div>

<hr/>

The documentation for this namespace was generated from the following file:

<ul>
<li><a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/ir/metadata-h">Metadata.h</a></li>
</ul>

<hr/>

<p class="doxyGeneratedBy">Generated via <a href="https://github.com/xpack/doxygen2docusaurus">doxygen2docusaurus</a> by <a href="https://www.doxygen.nl">Doxygen</a> 1.14.0.</p>

</div>
