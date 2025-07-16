---

# DO NOT EDIT!
# Automatically generated via doxygen2docusaurus by Doxygen.

slug: /api/classes/llvm/codegenpassbuilder
custom_edit_url: null
toc_max_heading_level: 4
keywords:
  - doxygen
  - reference
  - class

---

<div class="doxyPage">

# The `CodeGenPassBuilder` Class Template Reference

<p>This class provides access to building LLVM's passes. <a href="#details">More...</a></p>

## Declaration

<div class="doxyDeclaration">
template &lt;typename DerivedT, typename TargetMachineT&gt;
class llvm::CodeGenPassBuilder&lt;DerivedT, TargetMachineT&gt; { ... }
</div>

## Included Headers

<div class="doxyIncludesList">#include "<a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/passes/codegenpassbuilder-h">llvm/Passes/CodeGenPassBuilder.h</a>"
</div>

## Protected Member Typedefs Index

<table class="doxyMembersIndex">

<tr class="doxyMemberIndexTemplate">
<td class="doxyMemberIndexTemplate" colspan="2"><div>template &lt;typename PassT&gt;</div></td>
</tr>
<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemTypeTemplate" align="left" valign="top">using</td>
<td class="doxyMemberIndexItemNameTemplate" align="left" valign="top"><a href="#a40c20bd892cf1a4f1586b891cd7d8bb3">has_required_t</a> = decltype(std::declval&lt; PassT &amp; &gt;().isRequired())</td>
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
<td class="doxyMemberIndexItemTypeTemplate" align="left" valign="top">using</td>
<td class="doxyMemberIndexItemNameTemplate" align="left" valign="top"><a href="#ae703149d62fc6b3c3891d5d17fa870d9">is_module_pass_t</a> = decltype(std::declval&lt; PassT &amp; &gt;().run( std::declval&lt; <a href="/web-llvm/docs/api/classes/llvm/module">Module</a> &amp; &gt;(), std::declval&lt; <a href="/web-llvm/docs/api/namespaces/llvm/#af9c9208365fd9ce11392b4d79485e259">ModuleAnalysisManager</a> &amp; &gt;()))</td>
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
<td class="doxyMemberIndexItemTypeTemplate" align="left" valign="top">using</td>
<td class="doxyMemberIndexItemNameTemplate" align="left" valign="top"><a href="#a22b2211b9b667c6f850cc78f48a9954b">is_function_pass_t</a> = decltype(std::declval&lt; PassT &amp; &gt;().run( std::declval&lt; <a href="/web-llvm/docs/api/classes/llvm/function">Function</a> &amp; &gt;(), std::declval&lt; <a href="/web-llvm/docs/api/namespaces/llvm/#adce09a5a0de0e3177eb00e932734af2f">FunctionAnalysisManager</a> &amp; &gt;()))</td>
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
<td class="doxyMemberIndexItemTypeTemplate" align="left" valign="top">using</td>
<td class="doxyMemberIndexItemNameTemplate" align="left" valign="top"><a href="#a83e5009676402fa2e2f4df5cecbe66bf">is_machine_function_pass_t</a> = decltype(std::declval&lt; PassT &amp; &gt;().run( std::declval&lt; <a href="/web-llvm/docs/api/classes/llvm/machinefunction">MachineFunction</a> &amp; &gt;(), std::declval&lt; <a href="/web-llvm/docs/api/namespaces/llvm/#a064825a8817522ca733ac413a7122d36">MachineFunctionAnalysisManager</a> &amp; &gt;()))</td>
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
<td class="doxyMemberIndexTemplate" colspan="2"><div>template &lt;typename DerivedT, typename TargetMachineT&gt;</div></td>
</tr>
<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemTypeTemplate" align="left" valign="top">using</td>
<td class="doxyMemberIndexItemNameTemplate" align="left" valign="top"><a href="#a738a8c97344f7d78bfb36623251608ad">CreateMCStreamer</a> = std::function&lt; <a href="/web-llvm/docs/api/classes/llvm/expected">Expected</a>&lt; std::unique_ptr&lt; <a href="/web-llvm/docs/api/classes/llvm/mcstreamer">MCStreamer</a> &gt; &gt;(<a href="/web-llvm/docs/api/classes/llvm/mccontext">MCContext</a> &amp;)&gt;</td>
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

<tr class="doxyMemberIndexTemplate">
<td class="doxyMemberIndexTemplate" colspan="2"><div>template &lt;typename DerivedT, typename TargetMachineT&gt;</div></td>
</tr>
<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemNoTypeNameTemplate" colspan="2" align="left" valign="top"><a href="#a94d7ce2e38cb6acae735d6edb74c8fa7">CodeGenPassBuilder</a> (TargetMachineT &amp;TM, const CGPassBuilderOption &amp;Opts, PassInstrumentationCallbacks *PIC)</td>
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

<tr class="doxyMemberIndexTemplate">
<td class="doxyMemberIndexTemplate" colspan="2"><div>template &lt;typename DerivedT, typename TargetMachineT&gt;</div></td>
</tr>
<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemTypeTemplate" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/error">Error</a></td>
<td class="doxyMemberIndexItemNameTemplate" align="left" valign="top"><a href="#a6476029eb211f7d7bc0bf419d58ac6c6">buildPipeline</a> (ModulePassManager &amp;MPM, raw_pwrite_stream &amp;Out, raw_pwrite_stream *DwoOut, CodeGenFileType FileType) const</td>
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
<td class="doxyMemberIndexTemplate" colspan="2"><div>template &lt;typename DerivedT, typename TargetMachineT&gt;</div></td>
</tr>
<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemTypeTemplate" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/passinstrumentationcallbacks">PassInstrumentationCallbacks</a> *</td>
<td class="doxyMemberIndexItemNameTemplate" align="left" valign="top"><a href="#af6b2e10f840b080fc006189f27eaf641">getPassInstrumentationCallbacks</a> () const</td>
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

## Protected Member Functions Index

<table class="doxyMembersIndex">

<tr class="doxyMemberIndexTemplate">
<td class="doxyMemberIndexTemplate" colspan="2"><div>template &lt;typename TMC&gt;</div></td>
</tr>
<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemTypeTemplate" align="left" valign="top">TMC &amp;</td>
<td class="doxyMemberIndexItemNameTemplate" align="left" valign="top"><a href="#a74d04e121942d5e2fb2b8d1772d41a71">getTM</a> () const</td>
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
<td class="doxyMemberIndexTemplate" colspan="2"><div>template &lt;typename DerivedT, typename TargetMachineT&gt;</div></td>
</tr>
<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemTypeTemplate" align="left" valign="top"><a href="/web-llvm/docs/api/namespaces/llvm/#a8ec1bf8d7b792ca9fac56f8514db18d2">CodeGenOptLevel</a></td>
<td class="doxyMemberIndexItemNameTemplate" align="left" valign="top"><a href="#af027a2e3b2cd80c416d04bc509dd9b43">getOptLevel</a> () const</td>
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
<td class="doxyMemberIndexTemplate" colspan="2"><div>template &lt;typename DerivedT, typename TargetMachineT&gt;</div></td>
</tr>
<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemTypeTemplate" align="left" valign="top">bool</td>
<td class="doxyMemberIndexItemNameTemplate" align="left" valign="top"><a href="#a454c24dde3f14412c63b3ae23f048274">isGlobalISelAbortEnabled</a> () const</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p><a href="/web-llvm/docs/api/namespaces/llvm/check">Check</a> whether or not GlobalISel should abort on error. <a href="#a454c24dde3f14412c63b3ae23f048274">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexTemplate">
<td class="doxyMemberIndexTemplate" colspan="2"><div>template &lt;typename DerivedT, typename TargetMachineT&gt;</div></td>
</tr>
<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemTypeTemplate" align="left" valign="top">bool</td>
<td class="doxyMemberIndexItemNameTemplate" align="left" valign="top"><a href="#af6db0af78f5cdf3125396c8572f37417">reportDiagnosticWhenGlobalISelFallback</a> () const</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p><a href="/web-llvm/docs/api/namespaces/llvm/check">Check</a> whether or not a diagnostic should be emitted when GlobalISel uses the fallback path. <a href="#af6db0af78f5cdf3125396c8572f37417">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexTemplate">
<td class="doxyMemberIndexTemplate" colspan="2"><div>template &lt;typename DerivedT, typename TargetMachineT&gt;</div></td>
</tr>
<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemTypeTemplate" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/error">Error</a></td>
<td class="doxyMemberIndexItemNameTemplate" align="left" valign="top"><a href="#ac965e696cbe925c9d2b54537b69b3ded">addInstSelector</a> (AddMachinePass &amp;) const</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>addInstSelector - This method should install an instruction selector pass, which converts from LLVM code to machine instructions. <a href="#ac965e696cbe925c9d2b54537b69b3ded">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexTemplate">
<td class="doxyMemberIndexTemplate" colspan="2"><div>template &lt;typename DerivedT, typename TargetMachineT&gt;</div></td>
</tr>
<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemTypeTemplate" align="left" valign="top">void</td>
<td class="doxyMemberIndexItemNameTemplate" align="left" valign="top"><a href="#a675ee875dcfb92cfea3edf6acc947285">addGlobalMergePass</a> (AddIRPass &amp;) const</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p><a href="/web-llvm/docs/api/classes/llvm/target">Target</a> can override this to add <a href="/web-llvm/docs/api/classes/llvm/globalmergepass">GlobalMergePass</a> before all IR passes. <a href="#a675ee875dcfb92cfea3edf6acc947285">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexTemplate">
<td class="doxyMemberIndexTemplate" colspan="2"><div>template &lt;typename DerivedT, typename TargetMachineT&gt;</div></td>
</tr>
<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemTypeTemplate" align="left" valign="top">void</td>
<td class="doxyMemberIndexItemNameTemplate" align="left" valign="top"><a href="#a2d618dbbb3180d74c19249f3419cb54f">addILPOpts</a> (AddMachinePass &amp;) const</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Add passes that optimize instruction level parallelism for out-of-order targets. <a href="#a2d618dbbb3180d74c19249f3419cb54f">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexTemplate">
<td class="doxyMemberIndexTemplate" colspan="2"><div>template &lt;typename DerivedT, typename TargetMachineT&gt;</div></td>
</tr>
<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemTypeTemplate" align="left" valign="top">void</td>
<td class="doxyMemberIndexItemNameTemplate" align="left" valign="top"><a href="#a551342b9f2f56afd7dd999ac2da202a2">addPreRegAlloc</a> (AddMachinePass &amp;) const</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>This method may be implemented by targets that want to run passes immediately before register allocation. <a href="#a551342b9f2f56afd7dd999ac2da202a2">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexTemplate">
<td class="doxyMemberIndexTemplate" colspan="2"><div>template &lt;typename DerivedT, typename TargetMachineT&gt;</div></td>
</tr>
<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemTypeTemplate" align="left" valign="top">void</td>
<td class="doxyMemberIndexItemNameTemplate" align="left" valign="top"><a href="#a01e72190d04d4448265cf8f5a367a614">addPreRewrite</a> (AddMachinePass &amp;) const</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>addPreRewrite - Add passes to the optimized register allocation pipeline after register allocation is complete, but before virtual registers are rewritten to physical registers. <a href="#a01e72190d04d4448265cf8f5a367a614">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexTemplate">
<td class="doxyMemberIndexTemplate" colspan="2"><div>template &lt;typename DerivedT, typename TargetMachineT&gt;</div></td>
</tr>
<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemTypeTemplate" align="left" valign="top">void</td>
<td class="doxyMemberIndexItemNameTemplate" align="left" valign="top"><a href="#acd6b0eade594096f793ab6d550d33ff6">addPostRewrite</a> (AddMachinePass &amp;) const</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Add passes to be run immediately after virtual registers are rewritten to physical registers. <a href="#acd6b0eade594096f793ab6d550d33ff6">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexTemplate">
<td class="doxyMemberIndexTemplate" colspan="2"><div>template &lt;typename DerivedT, typename TargetMachineT&gt;</div></td>
</tr>
<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemTypeTemplate" align="left" valign="top">void</td>
<td class="doxyMemberIndexItemNameTemplate" align="left" valign="top"><a href="#a049e7f55b396434a1455d53aba79c259">addPostRegAlloc</a> (AddMachinePass &amp;) const</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>This method may be implemented by targets that want to run passes after register allocation pass pipeline but before prolog-epilog insertion. <a href="#a049e7f55b396434a1455d53aba79c259">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexTemplate">
<td class="doxyMemberIndexTemplate" colspan="2"><div>template &lt;typename DerivedT, typename TargetMachineT&gt;</div></td>
</tr>
<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemTypeTemplate" align="left" valign="top">void</td>
<td class="doxyMemberIndexItemNameTemplate" align="left" valign="top"><a href="#a399ba5ae9a5e17572286d4466a68a6ed">addPreSched2</a> (AddMachinePass &amp;) const</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>This method may be implemented by targets that want to run passes after prolog-epilog insertion and before the second instruction scheduling pass. <a href="#a399ba5ae9a5e17572286d4466a68a6ed">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexTemplate">
<td class="doxyMemberIndexTemplate" colspan="2"><div>template &lt;typename DerivedT, typename TargetMachineT&gt;</div></td>
</tr>
<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemTypeTemplate" align="left" valign="top">void</td>
<td class="doxyMemberIndexItemNameTemplate" align="left" valign="top"><a href="#ad16b79ac352d540374ff9f433fd72748">addPreEmitPass</a> (AddMachinePass &amp;) const</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>This pass may be implemented by targets that want to run passes immediately before machine code is emitted. <a href="#ad16b79ac352d540374ff9f433fd72748">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexTemplate">
<td class="doxyMemberIndexTemplate" colspan="2"><div>template &lt;typename DerivedT, typename TargetMachineT&gt;</div></td>
</tr>
<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemTypeTemplate" align="left" valign="top">void</td>
<td class="doxyMemberIndexItemNameTemplate" align="left" valign="top"><a href="#acbee0ccdec0f7e6003a5905a236f03f0">addPreEmitPass2</a> (AddMachinePass &amp;) const</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Targets may add passes immediately before machine code is emitted in this callback. <a href="#acbee0ccdec0f7e6003a5905a236f03f0">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexTemplate">
<td class="doxyMemberIndexTemplate" colspan="2"><div>template &lt;typename DerivedT, typename TargetMachineT&gt;</div></td>
</tr>
<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemTypeTemplate" align="left" valign="top">void</td>
<td class="doxyMemberIndexItemNameTemplate" align="left" valign="top"><a href="#afc6649ff4d117ac2dd598bdbeca9cce7">addPreISel</a> (AddIRPass &amp;) const</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>{{@ For GlobalISel <a href="#afc6649ff4d117ac2dd598bdbeca9cce7">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexTemplate">
<td class="doxyMemberIndexTemplate" colspan="2"><div>template &lt;typename DerivedT, typename TargetMachineT&gt;</div></td>
</tr>
<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemTypeTemplate" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/error">Error</a></td>
<td class="doxyMemberIndexItemNameTemplate" align="left" valign="top"><a href="#a2743a643b7637310e134e947248a57fd">addIRTranslator</a> (AddMachinePass &amp;) const</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>This method should install an IR translator pass, which converts from LLVM code to machine instructions with possibly generic opcodes. <a href="#a2743a643b7637310e134e947248a57fd">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexTemplate">
<td class="doxyMemberIndexTemplate" colspan="2"><div>template &lt;typename DerivedT, typename TargetMachineT&gt;</div></td>
</tr>
<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemTypeTemplate" align="left" valign="top">void</td>
<td class="doxyMemberIndexItemNameTemplate" align="left" valign="top"><a href="#aed9d1553e76d562bcad39c4dd6922f17">addPreLegalizeMachineIR</a> (AddMachinePass &amp;) const</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>This method may be implemented by targets that want to run passes immediately before legalization. <a href="#aed9d1553e76d562bcad39c4dd6922f17">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexTemplate">
<td class="doxyMemberIndexTemplate" colspan="2"><div>template &lt;typename DerivedT, typename TargetMachineT&gt;</div></td>
</tr>
<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemTypeTemplate" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/error">Error</a></td>
<td class="doxyMemberIndexItemNameTemplate" align="left" valign="top"><a href="#a68b5c4a9bf312eb721c6ac407af2a7eb">addLegalizeMachineIR</a> (AddMachinePass &amp;) const</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>This method should install a legalize pass, which converts the instruction sequence into one that can be selected by the target. <a href="#a68b5c4a9bf312eb721c6ac407af2a7eb">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexTemplate">
<td class="doxyMemberIndexTemplate" colspan="2"><div>template &lt;typename DerivedT, typename TargetMachineT&gt;</div></td>
</tr>
<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemTypeTemplate" align="left" valign="top">void</td>
<td class="doxyMemberIndexItemNameTemplate" align="left" valign="top"><a href="#ad0f79ace134c31b4e445707078072766">addPreRegBankSelect</a> (AddMachinePass &amp;) const</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>This method may be implemented by targets that want to run passes immediately before the register bank selection. <a href="#ad0f79ace134c31b4e445707078072766">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexTemplate">
<td class="doxyMemberIndexTemplate" colspan="2"><div>template &lt;typename DerivedT, typename TargetMachineT&gt;</div></td>
</tr>
<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemTypeTemplate" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/error">Error</a></td>
<td class="doxyMemberIndexItemNameTemplate" align="left" valign="top"><a href="#a3e88c5ab231653e3fccd5ac4c32f00c0">addRegBankSelect</a> (AddMachinePass &amp;) const</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>This method should install a register bank selector pass, which assigns register banks to virtual registers without a register class or register banks. <a href="#a3e88c5ab231653e3fccd5ac4c32f00c0">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexTemplate">
<td class="doxyMemberIndexTemplate" colspan="2"><div>template &lt;typename DerivedT, typename TargetMachineT&gt;</div></td>
</tr>
<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemTypeTemplate" align="left" valign="top">void</td>
<td class="doxyMemberIndexItemNameTemplate" align="left" valign="top"><a href="#a1e436c30d1765ee112af32831e8d5d19">addPreGlobalInstructionSelect</a> (AddMachinePass &amp;) const</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>This method may be implemented by targets that want to run passes immediately before the (global) instruction selection. <a href="#a1e436c30d1765ee112af32831e8d5d19">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexTemplate">
<td class="doxyMemberIndexTemplate" colspan="2"><div>template &lt;typename DerivedT, typename TargetMachineT&gt;</div></td>
</tr>
<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemTypeTemplate" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/error">Error</a></td>
<td class="doxyMemberIndexItemNameTemplate" align="left" valign="top"><a href="#ad55685e6ba5ef46183f43431a8a6a45f">addGlobalInstructionSelect</a> (AddMachinePass &amp;) const</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>This method should install a (global) instruction selector pass, which converts possibly generic instructions to fully target-specific instructions, thereby constraining all generic virtual registers to register classes. <a href="#ad55685e6ba5ef46183f43431a8a6a45f">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexTemplate">
<td class="doxyMemberIndexTemplate" colspan="2"><div>template &lt;typename DerivedT, typename TargetMachineT&gt;</div></td>
</tr>
<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemTypeTemplate" align="left" valign="top">void</td>
<td class="doxyMemberIndexItemNameTemplate" align="left" valign="top"><a href="#a7b58e0c440a2d9ee99b03789cbd10253">addISelPasses</a> (AddIRPass &amp;) const</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>High level function that adds all passes necessary to go from llvm IR representation to the MI representation. <a href="#a7b58e0c440a2d9ee99b03789cbd10253">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexTemplate">
<td class="doxyMemberIndexTemplate" colspan="2"><div>template &lt;typename DerivedT, typename TargetMachineT&gt;</div></td>
</tr>
<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemTypeTemplate" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/error">Error</a></td>
<td class="doxyMemberIndexItemNameTemplate" align="left" valign="top"><a href="#a6def3ee2976adc8630894b508c7c7402">addCoreISelPasses</a> (AddMachinePass &amp;) const</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Add the actual instruction selection passes. <a href="#a6def3ee2976adc8630894b508c7c7402">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexTemplate">
<td class="doxyMemberIndexTemplate" colspan="2"><div>template &lt;typename DerivedT, typename TargetMachineT&gt;</div></td>
</tr>
<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemTypeTemplate" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/error">Error</a></td>
<td class="doxyMemberIndexItemNameTemplate" align="left" valign="top"><a href="#aa3cda6e4a4f17e5759b544a4c7ec494c">addMachinePasses</a> (AddMachinePass &amp;) const</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Add the complete, standard set of LLVM CodeGen passes. <a href="#aa3cda6e4a4f17e5759b544a4c7ec494c">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexTemplate">
<td class="doxyMemberIndexTemplate" colspan="2"><div>template &lt;typename DerivedT, typename TargetMachineT&gt;</div></td>
</tr>
<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemTypeTemplate" align="left" valign="top">void</td>
<td class="doxyMemberIndexItemNameTemplate" align="left" valign="top"><a href="#af1e8527d2d52590304877f95c649aa71">addPassesToHandleExceptions</a> (AddIRPass &amp;) const</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Add passes to lower exception handling for the code generator. <a href="#af1e8527d2d52590304877f95c649aa71">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexTemplate">
<td class="doxyMemberIndexTemplate" colspan="2"><div>template &lt;typename DerivedT, typename TargetMachineT&gt;</div></td>
</tr>
<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemTypeTemplate" align="left" valign="top">void</td>
<td class="doxyMemberIndexItemNameTemplate" align="left" valign="top"><a href="#ad6d8ab9f89af9e5c0329a300b3dfd7ab">addIRPasses</a> (AddIRPass &amp;) const</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Add common target configurable passes that perform LLVM IR to IR transforms following machine independent optimization. <a href="#ad6d8ab9f89af9e5c0329a300b3dfd7ab">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexTemplate">
<td class="doxyMemberIndexTemplate" colspan="2"><div>template &lt;typename DerivedT, typename TargetMachineT&gt;</div></td>
</tr>
<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemTypeTemplate" align="left" valign="top">void</td>
<td class="doxyMemberIndexItemNameTemplate" align="left" valign="top"><a href="#a9e1385ad22d85a41207f9c1e158788ea">addCodeGenPrepare</a> (AddIRPass &amp;) const</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Add pass to prepare the LLVM IR for code generation. <a href="#a9e1385ad22d85a41207f9c1e158788ea">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexTemplate">
<td class="doxyMemberIndexTemplate" colspan="2"><div>template &lt;typename DerivedT, typename TargetMachineT&gt;</div></td>
</tr>
<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemTypeTemplate" align="left" valign="top">void</td>
<td class="doxyMemberIndexItemNameTemplate" align="left" valign="top"><a href="#ab7f25cc708c60ca391b68da2b83935d9">addISelPrepare</a> (AddIRPass &amp;) const</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Add common passes that perform LLVM IR to IR transforms in preparation for instruction selection. <a href="#ab7f25cc708c60ca391b68da2b83935d9">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexTemplate">
<td class="doxyMemberIndexTemplate" colspan="2"><div>template &lt;typename DerivedT, typename TargetMachineT&gt;</div></td>
</tr>
<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemTypeTemplate" align="left" valign="top">void</td>
<td class="doxyMemberIndexItemNameTemplate" align="left" valign="top"><a href="#a920cca6ac99ee512714d624a25a90d34">addMachineSSAOptimization</a> (AddMachinePass &amp;) const</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Methods with trivial inline returns are convenient points in the common codegen pass pipeline where targets may insert passes. <a href="#a920cca6ac99ee512714d624a25a90d34">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexTemplate">
<td class="doxyMemberIndexTemplate" colspan="2"><div>template &lt;typename DerivedT, typename TargetMachineT&gt;</div></td>
</tr>
<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemTypeTemplate" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/error">Error</a></td>
<td class="doxyMemberIndexItemNameTemplate" align="left" valign="top"><a href="#a22fe41485e53804d696235cc418139d3">addFastRegAlloc</a> (AddMachinePass &amp;) const</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>addFastRegAlloc - Add the minimum set of target-independent passes that are required for fast register allocation. <a href="#a22fe41485e53804d696235cc418139d3">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexTemplate">
<td class="doxyMemberIndexTemplate" colspan="2"><div>template &lt;typename DerivedT, typename TargetMachineT&gt;</div></td>
</tr>
<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemTypeTemplate" align="left" valign="top">void</td>
<td class="doxyMemberIndexItemNameTemplate" align="left" valign="top"><a href="#a73a36580247da797a62c3609afe8e1e9">addOptimizedRegAlloc</a> (AddMachinePass &amp;) const</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>addOptimizedRegAlloc - Add passes related to register allocation. <a href="#a73a36580247da797a62c3609afe8e1e9">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexTemplate">
<td class="doxyMemberIndexTemplate" colspan="2"><div>template &lt;typename DerivedT, typename TargetMachineT&gt;</div></td>
</tr>
<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemTypeTemplate" align="left" valign="top">void</td>
<td class="doxyMemberIndexItemNameTemplate" align="left" valign="top"><a href="#ad632c4c783e5170dd972a8d18836c0e9">addMachineLateOptimization</a> (AddMachinePass &amp;) const</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Add passes that optimize machine instructions after register allocation. <a href="#ad632c4c783e5170dd972a8d18836c0e9">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexTemplate">
<td class="doxyMemberIndexTemplate" colspan="2"><div>template &lt;typename DerivedT, typename TargetMachineT&gt;</div></td>
</tr>
<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemTypeTemplate" align="left" valign="top">void</td>
<td class="doxyMemberIndexItemNameTemplate" align="left" valign="top"><a href="#a5e87aaa9c803ce580d904db968b8f6a1">addGCPasses</a> (AddMachinePass &amp;) const</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>addGCPasses - Add late codegen passes that analyze code for garbage collection. <a href="#a5e87aaa9c803ce580d904db968b8f6a1">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexTemplate">
<td class="doxyMemberIndexTemplate" colspan="2"><div>template &lt;typename DerivedT, typename TargetMachineT&gt;</div></td>
</tr>
<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemTypeTemplate" align="left" valign="top">void</td>
<td class="doxyMemberIndexItemNameTemplate" align="left" valign="top"><a href="#ac7afb20962e71fd338b570303da8c45f">addBlockPlacement</a> (AddMachinePass &amp;) const</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Add standard basic block placement passes. <a href="#ac7afb20962e71fd338b570303da8c45f">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexTemplate">
<td class="doxyMemberIndexTemplate" colspan="2"><div>template &lt;typename DerivedT, typename TargetMachineT&gt;</div></td>
</tr>
<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemTypeTemplate" align="left" valign="top">void</td>
<td class="doxyMemberIndexItemNameTemplate" align="left" valign="top"><a href="#affececa2f7ed0b546881202e4af6565a">addAsmPrinter</a> (AddMachinePass &amp;, CreateMCStreamer) const</td>
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
<td class="doxyMemberIndexTemplate" colspan="2"><div>template &lt;typename DerivedT, typename TargetMachineT&gt;</div></td>
</tr>
<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemTypeTemplate" align="left" valign="top">void</td>
<td class="doxyMemberIndexItemNameTemplate" align="left" valign="top"><a href="#ac9d8fa0c86b7b514e80a528d85b4330a">addTargetRegisterAllocator</a> (AddMachinePass &amp;, bool Optimized) const</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Utilities for targets to add passes to the pass manager. <a href="#ac9d8fa0c86b7b514e80a528d85b4330a">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexTemplate">
<td class="doxyMemberIndexTemplate" colspan="2"><div>template &lt;typename DerivedT, typename TargetMachineT&gt;</div></td>
</tr>
<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemTypeTemplate" align="left" valign="top">void</td>
<td class="doxyMemberIndexItemNameTemplate" align="left" valign="top"><a href="#a329811e8a7ffa3b23fecec167f9fc31f">addRegAllocPass</a> (AddMachinePass &amp;, bool Optimized) const</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>addMachinePasses helper to create the target-selected or overriden regalloc pass. <a href="#a329811e8a7ffa3b23fecec167f9fc31f">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexTemplate">
<td class="doxyMemberIndexTemplate" colspan="2"><div>template &lt;typename DerivedT, typename TargetMachineT&gt;</div></td>
</tr>
<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemTypeTemplate" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/error">Error</a></td>
<td class="doxyMemberIndexItemNameTemplate" align="left" valign="top"><a href="#a1e77277704de3f76249f730ee55dc7b9">addRegAssignmentFast</a> (AddMachinePass &amp;) const</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Add core register alloator passes which do the actual register assignment and rewriting. <a href="#a1e77277704de3f76249f730ee55dc7b9">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexTemplate">
<td class="doxyMemberIndexTemplate" colspan="2"><div>template &lt;typename DerivedT, typename TargetMachineT&gt;</div></td>
</tr>
<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemTypeTemplate" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/error">Error</a></td>
<td class="doxyMemberIndexItemNameTemplate" align="left" valign="top"><a href="#a9b736691b65c34ed04d495d4e1166a39">addRegAssignmentOptimized</a> (AddMachinePass &amp;) const</td>
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
<td class="doxyMemberIndexTemplate" colspan="2"><div>template &lt;typename... PassTs&gt;</div></td>
</tr>
<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemTypeTemplate" align="left" valign="top">void</td>
<td class="doxyMemberIndexItemNameTemplate" align="left" valign="top"><a href="#abf8928310db68013b2d547df352d9345">disablePass</a> ()</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Allow the target to disable a specific pass by default. <a href="#abf8928310db68013b2d547df352d9345">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexTemplate">
<td class="doxyMemberIndexTemplate" colspan="2"><div>template &lt;typename TargetPassT, typename InsertedPassT&gt;</div></td>
</tr>
<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemTypeTemplate" align="left" valign="top">void</td>
<td class="doxyMemberIndexItemNameTemplate" align="left" valign="top"><a href="#a16b9126d671cbce7e45e877cc583d405">insertPass</a> (InsertedPassT &amp;&amp;Pass)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Insert InsertedPass pass after TargetPass pass. <a href="#a16b9126d671cbce7e45e877cc583d405">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

</table>

## Private Member Functions Index

<table class="doxyMembersIndex">

<tr class="doxyMemberIndexTemplate">
<td class="doxyMemberIndexTemplate" colspan="2"><div>template &lt;typename DerivedT, typename TargetMachineT&gt;</div></td>
</tr>
<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemTypeTemplate" align="left" valign="top">DerivedT &amp;</td>
<td class="doxyMemberIndexItemNameTemplate" align="left" valign="top"><a href="#a254906540e0cfbcc692799d044ee60e4">derived</a> ()</td>
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
<td class="doxyMemberIndexTemplate" colspan="2"><div>template &lt;typename DerivedT, typename TargetMachineT&gt;</div></td>
</tr>
<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemTypeTemplate" align="left" valign="top"><a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> DerivedT &amp;</td>
<td class="doxyMemberIndexItemNameTemplate" align="left" valign="top"><a href="#a0e64497c02ad69345f515516685c9af5">derived</a> () const</td>
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
<td class="doxyMemberIndexTemplate" colspan="2"><div>template &lt;typename DerivedT, typename TargetMachineT&gt;</div></td>
</tr>
<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemTypeTemplate" align="left" valign="top">bool</td>
<td class="doxyMemberIndexItemNameTemplate" align="left" valign="top"><a href="#ac129e4826b19e5a844fa51debfdf23fc">runBeforeAdding</a> (StringRef Name) const</td>
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
<td class="doxyMemberIndexTemplate" colspan="2"><div>template &lt;typename DerivedT, typename TargetMachineT&gt;</div></td>
</tr>
<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemTypeTemplate" align="left" valign="top">void</td>
<td class="doxyMemberIndexItemNameTemplate" align="left" valign="top"><a href="#a5402ebed2a6335b3a482b20c540c7232">setStartStopPasses</a> (const TargetPassConfig::StartStopInfo &amp;Info) const</td>
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
<td class="doxyMemberIndexTemplate" colspan="2"><div>template &lt;typename DerivedT, typename TargetMachineT&gt;</div></td>
</tr>
<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemTypeTemplate" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/error">Error</a></td>
<td class="doxyMemberIndexItemNameTemplate" align="left" valign="top"><a href="#af0d1d92762fab6e66573c3ebb9b6caaf">verifyStartStop</a> (const TargetPassConfig::StartStopInfo &amp;Info) const</td>
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

## Protected Member Attributes Index

<table class="doxyMembersIndex">

<tr class="doxyMemberIndexTemplate">
<td class="doxyMemberIndexTemplate" colspan="2"><div>template &lt;typename DerivedT, typename TargetMachineT&gt;</div></td>
</tr>
<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemTypeTemplate" align="left" valign="top">TargetMachineT &amp;</td>
<td class="doxyMemberIndexItemNameTemplate" align="left" valign="top"><a href="#a534105ec90dac84f7e87451abf4b528d">TM</a></td>
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
<td class="doxyMemberIndexTemplate" colspan="2"><div>template &lt;typename DerivedT, typename TargetMachineT&gt;</div></td>
</tr>
<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemTypeTemplate" align="left" valign="top"><a href="/web-llvm/docs/api/structs/llvm/cgpassbuilderoption">CGPassBuilderOption</a></td>
<td class="doxyMemberIndexItemNameTemplate" align="left" valign="top"><a href="#a9a8ef18a6785a2e0c11995308ccfba2b">Opt</a></td>
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
<td class="doxyMemberIndexTemplate" colspan="2"><div>template &lt;typename DerivedT, typename TargetMachineT&gt;</div></td>
</tr>
<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemTypeTemplate" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/passinstrumentationcallbacks">PassInstrumentationCallbacks</a> *</td>
<td class="doxyMemberIndexItemNameTemplate" align="left" valign="top"><a href="#a8b37f13bb1431bc3965bbdfc110a5fb1">PIC</a></td>
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

<tr class="doxyMemberIndexTemplate">
<td class="doxyMemberIndexTemplate" colspan="2"><div>template &lt;typename DerivedT, typename TargetMachineT&gt;</div></td>
</tr>
<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemTypeTemplate" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/smallvector">SmallVector</a>&lt; <a href="/web-llvm/docs/api/classes/llvm/unique-function">llvm::unique_function</a>&lt; bool(<a href="/web-llvm/docs/api/classes/llvm/stringref">StringRef</a>)&gt;, 4 &gt;</td>
<td class="doxyMemberIndexItemNameTemplate" align="left" valign="top"><a href="#a626f11e8362faef40d41ba537ccf66f6">BeforeCallbacks</a></td>
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
<td class="doxyMemberIndexTemplate" colspan="2"><div>template &lt;typename DerivedT, typename TargetMachineT&gt;</div></td>
</tr>
<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemTypeTemplate" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/smallvector">SmallVector</a>&lt; <a href="/web-llvm/docs/api/classes/llvm/unique-function">llvm::unique_function</a>&lt; void(<a href="/web-llvm/docs/api/classes/llvm/stringref">StringRef</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#ac4d6ff2181c8f2a8d4dabd70e55f2ba2">MachineFunctionPassManager</a> &amp;)&gt;, 4 &gt;</td>
<td class="doxyMemberIndexItemNameTemplate" align="left" valign="top"><a href="#acd9826fb30491a5d69a89545c84d44f2">AfterCallbacks</a></td>
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
<td class="doxyMemberIndexTemplate" colspan="2"><div>template &lt;typename DerivedT, typename TargetMachineT&gt;</div></td>
</tr>
<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemTypeTemplate" align="left" valign="top">bool</td>
<td class="doxyMemberIndexItemNameTemplate" align="left" valign="top"><a href="#afdfc097647580db5a9ca9a06cb5dd06e">Started</a> = <a href="/web-llvm/docs/api/files/lib/lib/analysis/basicaliasanalysis-cpp/#af6d5cafbdfc5313e65d990120021a3ec">true</a></td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Helper variable for <span class="doxyComputerOutput">-start-before/-start-after/-stop-before/-stop-after</span> <a href="#afdfc097647580db5a9ca9a06cb5dd06e">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexTemplate">
<td class="doxyMemberIndexTemplate" colspan="2"><div>template &lt;typename DerivedT, typename TargetMachineT&gt;</div></td>
</tr>
<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemTypeTemplate" align="left" valign="top">bool</td>
<td class="doxyMemberIndexItemNameTemplate" align="left" valign="top"><a href="#af749c6158295a5f9b47712e5a5c4cc35">Stopped</a> = <a href="/web-llvm/docs/api/files/lib/lib/analysis/basicaliasanalysis-cpp/#af6d5cafbdfc5313e65d990120021a3ec">true</a></td>
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

<p>This class provides access to building LLVM's passes.</p>


<p>Its members provide the baseline state available to passes during their construction. The <span class="doxyComputerOutput">MachinePassRegistry.def</span> file specifies how to construct all of the built-in passes, and those may reference these members during construction.</p>


<p>Definition at line 133 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/passes/codegenpassbuilder-h">CodeGenPassBuilder.h</a>.</p>


<div class="doxySectionDef">

## Protected Member Typedefs

### CreateMCStreamer {#a738a8c97344f7d78bfb36623251608ad}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<div class="doxyMemberTemplate">template &lt;typename DerivedT, typename TargetMachineT&gt;</div>
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">using llvm::CodeGenPassBuilder&lt; DerivedT, TargetMachineT &gt;::CreateMCStreamer = 
      std::function&lt;Expected&lt;std::unique_ptr&lt;MCStreamer&gt;&gt;(MCContext &amp;)&gt;</td>
</tr>
</table>
</td>
<td class="doxyMemberLabelsRight">
<span class="doxyMemberLabels">
<span class="doxyMemberLabel protected">protected</span>
</span>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 465 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/passes/codegenpassbuilder-h">CodeGenPassBuilder.h</a>.</p>

</div>
</div>

### has\_required\_t {#a40c20bd892cf1a4f1586b891cd7d8bb3}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<div class="doxyMemberTemplate">template &lt;typename PassT&gt;</div>
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">using llvm::CodeGenPassBuilder&lt; DerivedT, TargetMachineT &gt;::has_required_t =  decltype(std::declval&lt;PassT &amp;&gt;().isRequired())</td>
</tr>
</table>
</td>
<td class="doxyMemberLabelsRight">
<span class="doxyMemberLabels">
<span class="doxyMemberLabel protected">protected</span>
</span>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 164 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/passes/codegenpassbuilder-h">CodeGenPassBuilder.h</a>.</p>

</div>
</div>

### is\_function\_pass\_t {#a22b2211b9b667c6f850cc78f48a9954b}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<div class="doxyMemberTemplate">template &lt;typename PassT&gt;</div>
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">using llvm::CodeGenPassBuilder&lt; DerivedT, TargetMachineT &gt;::is_function_pass_t =  decltype(std::declval&lt;PassT &amp;&gt;().run(
      std::declval&lt;Function &amp;&gt;(), std::declval&lt;FunctionAnalysisManager &amp;&gt;()))</td>
</tr>
</table>
</td>
<td class="doxyMemberLabelsRight">
<span class="doxyMemberLabels">
<span class="doxyMemberLabel protected">protected</span>
</span>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 171 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/passes/codegenpassbuilder-h">CodeGenPassBuilder.h</a>.</p>

</div>
</div>

### is\_machine\_function\_pass\_t {#a83e5009676402fa2e2f4df5cecbe66bf}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<div class="doxyMemberTemplate">template &lt;typename PassT&gt;</div>
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">using llvm::CodeGenPassBuilder&lt; DerivedT, TargetMachineT &gt;::is_machine_function_pass_t =  decltype(std::declval&lt;PassT &amp;&gt;().run(
      std::declval&lt;MachineFunction &amp;&gt;(),
      std::declval&lt;MachineFunctionAnalysisManager &amp;&gt;()))</td>
</tr>
</table>
</td>
<td class="doxyMemberLabelsRight">
<span class="doxyMemberLabels">
<span class="doxyMemberLabel protected">protected</span>
</span>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 175 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/passes/codegenpassbuilder-h">CodeGenPassBuilder.h</a>.</p>

</div>
</div>

### is\_module\_pass\_t {#ae703149d62fc6b3c3891d5d17fa870d9}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<div class="doxyMemberTemplate">template &lt;typename PassT&gt;</div>
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">using llvm::CodeGenPassBuilder&lt; DerivedT, TargetMachineT &gt;::is_module_pass_t =  decltype(std::declval&lt;PassT &amp;&gt;().run(
      std::declval&lt;Module &amp;&gt;(), std::declval&lt;ModuleAnalysisManager &amp;&gt;()))</td>
</tr>
</table>
</td>
<td class="doxyMemberLabelsRight">
<span class="doxyMemberLabels">
<span class="doxyMemberLabel protected">protected</span>
</span>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 167 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/passes/codegenpassbuilder-h">CodeGenPassBuilder.h</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Public Constructors

### CodeGenPassBuilder() {#a94d7ce2e38cb6acae735d6edb74c8fa7}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<div class="doxyMemberTemplate">template &lt;typename DerivedT, typename TargetMachineT&gt;</div>
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">llvm::CodeGenPassBuilder&lt; DerivedT, TargetMachineT &gt;::CodeGenPassBuilder (TargetMachineT &amp; TM, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/structs/llvm/cgpassbuilderoption">CGPassBuilderOption</a> &amp; Opts, <a href="/web-llvm/docs/api/classes/llvm/passinstrumentationcallbacks">PassInstrumentationCallbacks</a> * PIC)</td>
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



<p>Definition at line 135 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/passes/codegenpassbuilder-h">CodeGenPassBuilder.h</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Public Member Functions

### buildPipeline() {#a6476029eb211f7d7bc0bf419d58ac6c6}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<div class="doxyMemberTemplate">template &lt;typename DerivedT, typename TargetMachineT&gt;</div>
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">Error llvm::CodeGenPassBuilder&lt; Derived, TargetMachineT &gt;::buildPipeline (<a href="/web-llvm/docs/api/namespaces/llvm/#a79ab9199d2ba6a1c9cac2b79efc194a3">ModulePassManager</a> &amp; MPM, <a href="/web-llvm/docs/api/classes/llvm/raw-pwrite-stream">raw_pwrite_stream</a> &amp; Out, <a href="/web-llvm/docs/api/classes/llvm/raw-pwrite-stream">raw_pwrite_stream</a> * DwoOut, <a href="/web-llvm/docs/api/namespaces/llvm/#a73b761f8d40500a5a28889569526b260">CodeGenFileType</a> FileType)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 154 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/passes/codegenpassbuilder-h">CodeGenPassBuilder.h</a>.</p>


<p>References <a href="#a6def3ee2976adc8630894b508c7c7402">llvm::CodeGenPassBuilder&lt; DerivedT, TargetMachineT &gt;::addCoreISelPasses</a>, <a href="#a7b58e0c440a2d9ee99b03789cbd10253">llvm::CodeGenPassBuilder&lt; DerivedT, TargetMachineT &gt;::addISelPasses</a>, <a href="#aa3cda6e4a4f17e5759b544a4c7ec494c">llvm::CodeGenPassBuilder&lt; DerivedT, TargetMachineT &gt;::addMachinePasses</a>, <a href="/web-llvm/docs/api/classes/llvm/targetpassconfig/#a2adec695334610982e70d013e958a4fd">llvm::TargetPassConfig::getStartStopInfo</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a73b761f8d40500a5a28889569526b260abbb93ef26e3c101ff11cdd21cab08a94">llvm::Null</a>, <a href="#a9a8ef18a6785a2e0c11995308ccfba2b">llvm::CodeGenPassBuilder&lt; DerivedT, TargetMachineT &gt;::Opt</a>, <a href="#a8b37f13bb1431bc3965bbdfc110a5fb1">llvm::CodeGenPassBuilder&lt; DerivedT, TargetMachineT &gt;::PIC</a> and <a href="/web-llvm/docs/api/classes/llvm/targetpassconfig/#ad0db8596710a5666b67e513da0d9b415">llvm::TargetPassConfig::willCompleteCodeGenPipeline</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/classes/llvm/gcntargetmachine/#a6b558554de041312d8c8cd3f1609c90c">llvm::GCNTargetMachine::buildCodeGenPipeline</a> and <a href="/web-llvm/docs/api/classes/llvm/r600targetmachine/#a00b4afd351da5d7ef32495bb1b790447">llvm::R600TargetMachine::buildCodeGenPipeline</a>.</p>

</div>
</div>

### getPassInstrumentationCallbacks() {#af6b2e10f840b080fc006189f27eaf641}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<div class="doxyMemberTemplate">template &lt;typename DerivedT, typename TargetMachineT&gt;</div>
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">PassInstrumentationCallbacks * llvm::CodeGenPassBuilder&lt; DerivedT, TargetMachineT &gt;::getPassInstrumentationCallbacks ()</td>
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



<p>Definition at line 158 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/passes/codegenpassbuilder-h">CodeGenPassBuilder.h</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Protected Member Functions

### addAsmPrinter() {#affececa2f7ed0b546881202e4af6565a}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<div class="doxyMemberTemplate">template &lt;typename DerivedT, typename TargetMachineT&gt;</div>
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void llvm::CodeGenPassBuilder&lt; DerivedT, TargetMachineT &gt;::addAsmPrinter (<a href="/web-llvm/docs/api/classes/llvm/codegenpassbuilder/addmachinepass">AddMachinePass</a> &amp;, <a href="#a738a8c97344f7d78bfb36623251608ad">CreateMCStreamer</a>)</td>
</tr>
</table>
</td>
<td class="doxyMemberLabelsRight">
<span class="doxyMemberLabels">
<span class="doxyMemberLabel inline">inline</span>
<span class="doxyMemberLabel protected">protected</span>
</span>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 467 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/passes/codegenpassbuilder-h">CodeGenPassBuilder.h</a>.</p>

</div>
</div>

### addBlockPlacement() {#ac7afb20962e71fd338b570303da8c45f}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<div class="doxyMemberTemplate">template &lt;typename DerivedT, typename TargetMachineT&gt;</div>
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void llvm::CodeGenPassBuilder&lt; Derived, TargetMachineT &gt;::addBlockPlacement (<a href="/web-llvm/docs/api/classes/llvm/codegenpassbuilder/addmachinepass">AddMachinePass</a> &amp; addPass)</td>
</tr>
</table>
</td>
<td class="doxyMemberLabelsRight">
<span class="doxyMemberLabels">
<span class="doxyMemberLabel protected">protected</span>
</span>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Add standard basic block placement passes.</p>

<p>Definition at line 463 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/passes/codegenpassbuilder-h">CodeGenPassBuilder.h</a>.</p>


<p>References <a href="#ac7afb20962e71fd338b570303da8c45f">llvm::CodeGenPassBuilder&lt; DerivedT, TargetMachineT &gt;::addBlockPlacement</a> and <a href="#a9a8ef18a6785a2e0c11995308ccfba2b">llvm::CodeGenPassBuilder&lt; DerivedT, TargetMachineT &gt;::Opt</a>.</p>


<p>Referenced by <a href="#ac7afb20962e71fd338b570303da8c45f">llvm::CodeGenPassBuilder&lt; DerivedT, TargetMachineT &gt;::addBlockPlacement</a>.</p>

</div>
</div>

### addCodeGenPrepare() {#a9e1385ad22d85a41207f9c1e158788ea}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<div class="doxyMemberTemplate">template &lt;typename DerivedT, typename TargetMachineT&gt;</div>
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void llvm::CodeGenPassBuilder&lt; Derived, TargetMachineT &gt;::addCodeGenPrepare (<a href="/web-llvm/docs/api/classes/llvm/codegenpassbuilder/addirpass">AddIRPass</a> &amp; addPass)</td>
</tr>
</table>
</td>
<td class="doxyMemberLabelsRight">
<span class="doxyMemberLabels">
<span class="doxyMemberLabel protected">protected</span>
</span>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Add pass to prepare the LLVM IR for code generation.</p>


<p>This should be done before exception handling preparation passes.</p>


<p>Definition at line 428 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/passes/codegenpassbuilder-h">CodeGenPassBuilder.h</a>.</p>


<p>References <a href="#a9e1385ad22d85a41207f9c1e158788ea">llvm::CodeGenPassBuilder&lt; DerivedT, TargetMachineT &gt;::addCodeGenPrepare</a>, <a href="#af027a2e3b2cd80c416d04bc509dd9b43">llvm::CodeGenPassBuilder&lt; DerivedT, TargetMachineT &gt;::getOptLevel</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a8ec1bf8d7b792ca9fac56f8514db18d2a6adf97f83acf6453d4a6a4b1070f3754">llvm::None</a>, <a href="#a9a8ef18a6785a2e0c11995308ccfba2b">llvm::CodeGenPassBuilder&lt; DerivedT, TargetMachineT &gt;::Opt</a> and <a href="#a534105ec90dac84f7e87451abf4b528d">llvm::CodeGenPassBuilder&lt; DerivedT, TargetMachineT &gt;::TM</a>.</p>


<p>Referenced by <a href="#a9e1385ad22d85a41207f9c1e158788ea">llvm::CodeGenPassBuilder&lt; DerivedT, TargetMachineT &gt;::addCodeGenPrepare</a>.</p>

</div>
</div>

### addCoreISelPasses() {#a6def3ee2976adc8630894b508c7c7402}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<div class="doxyMemberTemplate">template &lt;typename DerivedT, typename TargetMachineT&gt;</div>
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">Error llvm::CodeGenPassBuilder&lt; Derived, TargetMachineT &gt;::addCoreISelPasses (<a href="/web-llvm/docs/api/classes/llvm/codegenpassbuilder/addmachinepass">AddMachinePass</a> &amp; addPass)</td>
</tr>
</table>
</td>
<td class="doxyMemberLabelsRight">
<span class="doxyMemberLabels">
<span class="doxyMemberLabel protected">protected</span>
</span>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Add the actual instruction selection passes.</p>


<p>This does not include preparation passes on IR.</p>


<p>Definition at line 413 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/passes/codegenpassbuilder-h">CodeGenPassBuilder.h</a>.</p>


<p>References <a href="#a6def3ee2976adc8630894b508c7c7402">llvm::CodeGenPassBuilder&lt; DerivedT, TargetMachineT &gt;::addCoreISelPasses</a>, <a href="#ad55685e6ba5ef46183f43431a8a6a45f">llvm::CodeGenPassBuilder&lt; DerivedT, TargetMachineT &gt;::addGlobalInstructionSelect</a>, <a href="#ac965e696cbe925c9d2b54537b69b3ded">llvm::CodeGenPassBuilder&lt; DerivedT, TargetMachineT &gt;::addInstSelector</a>, <a href="#a2743a643b7637310e134e947248a57fd">llvm::CodeGenPassBuilder&lt; DerivedT, TargetMachineT &gt;::addIRTranslator</a>, <a href="#a68b5c4a9bf312eb721c6ac407af2a7eb">llvm::CodeGenPassBuilder&lt; DerivedT, TargetMachineT &gt;::addLegalizeMachineIR</a>, <a href="#a3e88c5ab231653e3fccd5ac4c32f00c0">llvm::CodeGenPassBuilder&lt; DerivedT, TargetMachineT &gt;::addRegBankSelect</a>, <a href="#a454c24dde3f14412c63b3ae23f048274">llvm::CodeGenPassBuilder&lt; DerivedT, TargetMachineT &gt;::isGlobalISelAbortEnabled</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a8ec1bf8d7b792ca9fac56f8514db18d2a6adf97f83acf6453d4a6a4b1070f3754">llvm::None</a>, <a href="#a9a8ef18a6785a2e0c11995308ccfba2b">llvm::CodeGenPassBuilder&lt; DerivedT, TargetMachineT &gt;::Opt</a>, <a href="#af6db0af78f5cdf3125396c8572f37417">llvm::CodeGenPassBuilder&lt; DerivedT, TargetMachineT &gt;::reportDiagnosticWhenGlobalISelFallback</a>, <a href="/web-llvm/docs/api/classes/llvm/error/#a4dfd0813c3d0e0a30439b5a3e9196b59">llvm::Error::success</a> and <a href="#a534105ec90dac84f7e87451abf4b528d">llvm::CodeGenPassBuilder&lt; DerivedT, TargetMachineT &gt;::TM</a>.</p>


<p>Referenced by <a href="#a6def3ee2976adc8630894b508c7c7402">llvm::CodeGenPassBuilder&lt; DerivedT, TargetMachineT &gt;::addCoreISelPasses</a> and <a href="#a6476029eb211f7d7bc0bf419d58ac6c6">llvm::CodeGenPassBuilder&lt; DerivedT, TargetMachineT &gt;::buildPipeline</a>.</p>

</div>
</div>

### addFastRegAlloc() {#a22fe41485e53804d696235cc418139d3}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<div class="doxyMemberTemplate">template &lt;typename DerivedT, typename TargetMachineT&gt;</div>
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">Error llvm::CodeGenPassBuilder&lt; Derived, TargetMachineT &gt;::addFastRegAlloc (<a href="/web-llvm/docs/api/classes/llvm/codegenpassbuilder/addmachinepass">AddMachinePass</a> &amp; addPass)</td>
</tr>
</table>
</td>
<td class="doxyMemberLabelsRight">
<span class="doxyMemberLabels">
<span class="doxyMemberLabel protected">protected</span>
</span>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>addFastRegAlloc - Add the minimum set of target-independent passes that are required for fast register allocation.</p>


<p>Add the minimum set of target-independent passes that are required for register allocation.</p>


<p>No coalescing or scheduling.</p>


<p>Definition at line 447 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/passes/codegenpassbuilder-h">CodeGenPassBuilder.h</a>.</p>


<p>Reference <a href="#a22fe41485e53804d696235cc418139d3">llvm::CodeGenPassBuilder&lt; DerivedT, TargetMachineT &gt;::addFastRegAlloc</a>.</p>


<p>Referenced by <a href="#a22fe41485e53804d696235cc418139d3">llvm::CodeGenPassBuilder&lt; DerivedT, TargetMachineT &gt;::addFastRegAlloc</a> and <a href="#aa3cda6e4a4f17e5759b544a4c7ec494c">llvm::CodeGenPassBuilder&lt; DerivedT, TargetMachineT &gt;::addMachinePasses</a>.</p>

</div>
</div>

### addGCPasses() {#a5e87aaa9c803ce580d904db968b8f6a1}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<div class="doxyMemberTemplate">template &lt;typename DerivedT, typename TargetMachineT&gt;</div>
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void llvm::CodeGenPassBuilder&lt; DerivedT, TargetMachineT &gt;::addGCPasses (<a href="/web-llvm/docs/api/classes/llvm/codegenpassbuilder/addmachinepass">AddMachinePass</a> &amp;)</td>
</tr>
</table>
</td>
<td class="doxyMemberLabelsRight">
<span class="doxyMemberLabels">
<span class="doxyMemberLabel inline">inline</span>
<span class="doxyMemberLabel protected">protected</span>
</span>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>addGCPasses - Add late codegen passes that analyze code for garbage collection.</p>


<p>This should return true if GC info should be printed after these passes.</p>


<p>Definition at line 460 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/passes/codegenpassbuilder-h">CodeGenPassBuilder.h</a>.</p>

</div>
</div>

### addGlobalInstructionSelect() {#ad55685e6ba5ef46183f43431a8a6a45f}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<div class="doxyMemberTemplate">template &lt;typename DerivedT, typename TargetMachineT&gt;</div>
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">Error llvm::CodeGenPassBuilder&lt; DerivedT, TargetMachineT &gt;::addGlobalInstructionSelect (<a href="/web-llvm/docs/api/classes/llvm/codegenpassbuilder/addmachinepass">AddMachinePass</a> &amp;)</td>
</tr>
</table>
</td>
<td class="doxyMemberLabelsRight">
<span class="doxyMemberLabels">
<span class="doxyMemberLabel inline">inline</span>
<span class="doxyMemberLabel protected">protected</span>
</span>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>This method should install a (global) instruction selector pass, which converts possibly generic instructions to fully target-specific instructions, thereby constraining all generic virtual registers to register classes.</p>

<p>Definition at line 398 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/passes/codegenpassbuilder-h">CodeGenPassBuilder.h</a>.</p>


<p>Referenced by <a href="#a6def3ee2976adc8630894b508c7c7402">llvm::CodeGenPassBuilder&lt; DerivedT, TargetMachineT &gt;::addCoreISelPasses</a>.</p>

</div>
</div>

### addGlobalMergePass() {#a675ee875dcfb92cfea3edf6acc947285}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<div class="doxyMemberTemplate">template &lt;typename DerivedT, typename TargetMachineT&gt;</div>
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void llvm::CodeGenPassBuilder&lt; DerivedT, TargetMachineT &gt;::addGlobalMergePass (<a href="/web-llvm/docs/api/classes/llvm/codegenpassbuilder/addirpass">AddIRPass</a> &amp;)</td>
</tr>
</table>
</td>
<td class="doxyMemberLabelsRight">
<span class="doxyMemberLabels">
<span class="doxyMemberLabel inline">inline</span>
<span class="doxyMemberLabel protected">protected</span>
</span>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p><a href="/web-llvm/docs/api/classes/llvm/target">Target</a> can override this to add <a href="/web-llvm/docs/api/classes/llvm/globalmergepass">GlobalMergePass</a> before all IR passes.</p>

<p>Definition at line 300 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/passes/codegenpassbuilder-h">CodeGenPassBuilder.h</a>.</p>

</div>
</div>

### addILPOpts() {#a2d618dbbb3180d74c19249f3419cb54f}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<div class="doxyMemberTemplate">template &lt;typename DerivedT, typename TargetMachineT&gt;</div>
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void llvm::CodeGenPassBuilder&lt; DerivedT, TargetMachineT &gt;::addILPOpts (<a href="/web-llvm/docs/api/classes/llvm/codegenpassbuilder/addmachinepass">AddMachinePass</a> &amp;)</td>
</tr>
</table>
</td>
<td class="doxyMemberLabelsRight">
<span class="doxyMemberLabels">
<span class="doxyMemberLabel inline">inline</span>
<span class="doxyMemberLabel protected">protected</span>
</span>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Add passes that optimize instruction level parallelism for out-of-order targets.</p>


<p>These passes are run while the machine code is still in SSA form, so they can use <a href="/web-llvm/docs/api/classes/llvm/machinetracemetrics">MachineTraceMetrics</a> to control their heuristics.</p>


<p>All passes added here should preserve the <a href="/web-llvm/docs/api/classes/llvm/machinedominatortree">MachineDominatorTree</a>, <a href="/web-llvm/docs/api/classes/llvm/machineloopinfo">MachineLoopInfo</a>, and <a href="/web-llvm/docs/api/classes/llvm/machinetracemetrics">MachineTraceMetrics</a> analyses.</p>


<p>Definition at line 308 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/passes/codegenpassbuilder-h">CodeGenPassBuilder.h</a>.</p>

</div>
</div>

### addInstSelector() {#ac965e696cbe925c9d2b54537b69b3ded}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<div class="doxyMemberTemplate">template &lt;typename DerivedT, typename TargetMachineT&gt;</div>
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">Error llvm::CodeGenPassBuilder&lt; DerivedT, TargetMachineT &gt;::addInstSelector (<a href="/web-llvm/docs/api/classes/llvm/codegenpassbuilder/addmachinepass">AddMachinePass</a> &amp;)</td>
</tr>
</table>
</td>
<td class="doxyMemberLabelsRight">
<span class="doxyMemberLabels">
<span class="doxyMemberLabel inline">inline</span>
<span class="doxyMemberLabel protected">protected</span>
</span>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>addInstSelector - This method should install an instruction selector pass, which converts from LLVM code to machine instructions.</p>

<p>Definition at line 294 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/passes/codegenpassbuilder-h">CodeGenPassBuilder.h</a>.</p>


<p>Referenced by <a href="#a6def3ee2976adc8630894b508c7c7402">llvm::CodeGenPassBuilder&lt; DerivedT, TargetMachineT &gt;::addCoreISelPasses</a>.</p>

</div>
</div>

### addIRPasses() {#ad6d8ab9f89af9e5c0329a300b3dfd7ab}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<div class="doxyMemberTemplate">template &lt;typename DerivedT, typename TargetMachineT&gt;</div>
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void llvm::CodeGenPassBuilder&lt; Derived, TargetMachineT &gt;::addIRPasses (<a href="/web-llvm/docs/api/classes/llvm/codegenpassbuilder/addirpass">AddIRPass</a> &amp; addPass)</td>
</tr>
</table>
</td>
<td class="doxyMemberLabelsRight">
<span class="doxyMemberLabels">
<span class="doxyMemberLabel protected">protected</span>
</span>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Add common target configurable passes that perform LLVM IR to IR transforms following machine independent optimization.</p>

<p>Definition at line 424 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/passes/codegenpassbuilder-h">CodeGenPassBuilder.h</a>.</p>


<p>References <a href="#ad6d8ab9f89af9e5c0329a300b3dfd7ab">llvm::CodeGenPassBuilder&lt; DerivedT, TargetMachineT &gt;::addIRPasses</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#adc70c26b79aeaaca89ad7e74474c3cca">llvm::createFunctionToLoopPassAdaptor</a>, <a href="#af027a2e3b2cd80c416d04bc509dd9b43">llvm::CodeGenPassBuilder&lt; DerivedT, TargetMachineT &gt;::getOptLevel</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a8ec1bf8d7b792ca9fac56f8514db18d2a6adf97f83acf6453d4a6a4b1070f3754">llvm::None</a>, <a href="#a9a8ef18a6785a2e0c11995308ccfba2b">llvm::CodeGenPassBuilder&lt; DerivedT, TargetMachineT &gt;::Opt</a> and <a href="#a534105ec90dac84f7e87451abf4b528d">llvm::CodeGenPassBuilder&lt; DerivedT, TargetMachineT &gt;::TM</a>.</p>


<p>Referenced by <a href="#ad6d8ab9f89af9e5c0329a300b3dfd7ab">llvm::CodeGenPassBuilder&lt; DerivedT, TargetMachineT &gt;::addIRPasses</a>.</p>

</div>
</div>

### addIRTranslator() {#a2743a643b7637310e134e947248a57fd}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<div class="doxyMemberTemplate">template &lt;typename DerivedT, typename TargetMachineT&gt;</div>
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">Error llvm::CodeGenPassBuilder&lt; DerivedT, TargetMachineT &gt;::addIRTranslator (<a href="/web-llvm/docs/api/classes/llvm/codegenpassbuilder/addmachinepass">AddMachinePass</a> &amp;)</td>
</tr>
</table>
</td>
<td class="doxyMemberLabelsRight">
<span class="doxyMemberLabels">
<span class="doxyMemberLabel inline">inline</span>
<span class="doxyMemberLabel protected">protected</span>
</span>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>This method should install an IR translator pass, which converts from LLVM code to machine instructions with possibly generic opcodes.</p>

<p>Definition at line 362 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/passes/codegenpassbuilder-h">CodeGenPassBuilder.h</a>.</p>


<p>Referenced by <a href="#a6def3ee2976adc8630894b508c7c7402">llvm::CodeGenPassBuilder&lt; DerivedT, TargetMachineT &gt;::addCoreISelPasses</a>.</p>

</div>
</div>

### addISelPasses() {#a7b58e0c440a2d9ee99b03789cbd10253}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<div class="doxyMemberTemplate">template &lt;typename DerivedT, typename TargetMachineT&gt;</div>
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void llvm::CodeGenPassBuilder&lt; Derived, TargetMachineT &gt;::addISelPasses (<a href="/web-llvm/docs/api/classes/llvm/codegenpassbuilder/addirpass">AddIRPass</a> &amp; addPass)</td>
</tr>
</table>
</td>
<td class="doxyMemberLabelsRight">
<span class="doxyMemberLabels">
<span class="doxyMemberLabel protected">protected</span>
</span>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>High level function that adds all passes necessary to go from llvm IR representation to the MI representation.</p>


<p>Adds IR based lowering and target specific optimization passes and finally the core instruction selection passes.</p>


<p>Definition at line 409 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/passes/codegenpassbuilder-h">CodeGenPassBuilder.h</a>.</p>


<p>References <a href="#a7b58e0c440a2d9ee99b03789cbd10253">llvm::CodeGenPassBuilder&lt; DerivedT, TargetMachineT &gt;::addISelPasses</a>, <a href="#af1e8527d2d52590304877f95c649aa71">llvm::CodeGenPassBuilder&lt; DerivedT, TargetMachineT &gt;::addPassesToHandleExceptions</a> and <a href="#a534105ec90dac84f7e87451abf4b528d">llvm::CodeGenPassBuilder&lt; DerivedT, TargetMachineT &gt;::TM</a>.</p>


<p>Referenced by <a href="#a7b58e0c440a2d9ee99b03789cbd10253">llvm::CodeGenPassBuilder&lt; DerivedT, TargetMachineT &gt;::addISelPasses</a> and <a href="#a6476029eb211f7d7bc0bf419d58ac6c6">llvm::CodeGenPassBuilder&lt; DerivedT, TargetMachineT &gt;::buildPipeline</a>.</p>

</div>
</div>

### addISelPrepare() {#ab7f25cc708c60ca391b68da2b83935d9}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<div class="doxyMemberTemplate">template &lt;typename DerivedT, typename TargetMachineT&gt;</div>
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void llvm::CodeGenPassBuilder&lt; Derived, TargetMachineT &gt;::addISelPrepare (<a href="/web-llvm/docs/api/classes/llvm/codegenpassbuilder/addirpass">AddIRPass</a> &amp; addPass)</td>
</tr>
</table>
</td>
<td class="doxyMemberLabelsRight">
<span class="doxyMemberLabels">
<span class="doxyMemberLabel protected">protected</span>
</span>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Add common passes that perform LLVM IR to IR transforms in preparation for instruction selection.</p>

<p>Definition at line 432 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/passes/codegenpassbuilder-h">CodeGenPassBuilder.h</a>.</p>


<p>References <a href="#ab7f25cc708c60ca391b68da2b83935d9">llvm::CodeGenPassBuilder&lt; DerivedT, TargetMachineT &gt;::addISelPrepare</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a7c46c742c31be54870e2038048e6b391">llvm::dbgs</a>, <a href="#a9a8ef18a6785a2e0c11995308ccfba2b">llvm::CodeGenPassBuilder&lt; DerivedT, TargetMachineT &gt;::Opt</a> and <a href="#a534105ec90dac84f7e87451abf4b528d">llvm::CodeGenPassBuilder&lt; DerivedT, TargetMachineT &gt;::TM</a>.</p>


<p>Referenced by <a href="#ab7f25cc708c60ca391b68da2b83935d9">llvm::CodeGenPassBuilder&lt; DerivedT, TargetMachineT &gt;::addISelPrepare</a>.</p>

</div>
</div>

### addLegalizeMachineIR() {#a68b5c4a9bf312eb721c6ac407af2a7eb}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<div class="doxyMemberTemplate">template &lt;typename DerivedT, typename TargetMachineT&gt;</div>
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">Error llvm::CodeGenPassBuilder&lt; DerivedT, TargetMachineT &gt;::addLegalizeMachineIR (<a href="/web-llvm/docs/api/classes/llvm/codegenpassbuilder/addmachinepass">AddMachinePass</a> &amp;)</td>
</tr>
</table>
</td>
<td class="doxyMemberLabelsRight">
<span class="doxyMemberLabels">
<span class="doxyMemberLabel inline">inline</span>
<span class="doxyMemberLabel protected">protected</span>
</span>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>This method should install a legalize pass, which converts the instruction sequence into one that can be selected by the target.</p>

<p>Definition at line 373 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/passes/codegenpassbuilder-h">CodeGenPassBuilder.h</a>.</p>


<p>Referenced by <a href="#a6def3ee2976adc8630894b508c7c7402">llvm::CodeGenPassBuilder&lt; DerivedT, TargetMachineT &gt;::addCoreISelPasses</a>.</p>

</div>
</div>

### addMachineLateOptimization() {#ad632c4c783e5170dd972a8d18836c0e9}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<div class="doxyMemberTemplate">template &lt;typename DerivedT, typename TargetMachineT&gt;</div>
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void llvm::CodeGenPassBuilder&lt; Derived, TargetMachineT &gt;::addMachineLateOptimization (<a href="/web-llvm/docs/api/classes/llvm/codegenpassbuilder/addmachinepass">AddMachinePass</a> &amp; addPass)</td>
</tr>
</table>
</td>
<td class="doxyMemberLabelsRight">
<span class="doxyMemberLabels">
<span class="doxyMemberLabel protected">protected</span>
</span>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Add passes that optimize machine instructions after register allocation.</p>


<p>Post RegAlloc <a href="/web-llvm/docs/api/classes/llvm/pass">Pass</a> Configuration.</p>


<p>Add passes that optimize machine instructions after register allocation.</p>


<p>Definition at line 455 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/passes/codegenpassbuilder-h">CodeGenPassBuilder.h</a>.</p>


<p>References <a href="#ad632c4c783e5170dd972a8d18836c0e9">llvm::CodeGenPassBuilder&lt; DerivedT, TargetMachineT &gt;::addMachineLateOptimization</a> and <a href="#a534105ec90dac84f7e87451abf4b528d">llvm::CodeGenPassBuilder&lt; DerivedT, TargetMachineT &gt;::TM</a>.</p>


<p>Referenced by <a href="#ad632c4c783e5170dd972a8d18836c0e9">llvm::CodeGenPassBuilder&lt; DerivedT, TargetMachineT &gt;::addMachineLateOptimization</a>.</p>

</div>
</div>

### addMachinePasses() {#aa3cda6e4a4f17e5759b544a4c7ec494c}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<div class="doxyMemberTemplate">template &lt;typename DerivedT, typename TargetMachineT&gt;</div>
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">Error llvm::CodeGenPassBuilder&lt; Derived, TargetMachineT &gt;::addMachinePasses (<a href="/web-llvm/docs/api/classes/llvm/codegenpassbuilder/addmachinepass">AddMachinePass</a> &amp; addPass)</td>
</tr>
</table>
</td>
<td class="doxyMemberLabelsRight">
<span class="doxyMemberLabels">
<span class="doxyMemberLabel protected">protected</span>
</span>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Add the complete, standard set of LLVM CodeGen passes.</p>


<p>Add the complete set of target-independent postISel code generator passes.</p>


<p>Fully developed targets will not generally override this.</p>


<p>This can be read as the standard order of major LLVM CodeGen stages. Stages with nontrivial configuration or multiple passes are broken out below in addStage routines.</p>


<p><a href="/web-llvm/docs/api/classes/llvm/any">Any</a> CodeGenPassBuilder&lt;Derived, TargetMachine&gt;::addXX routine may be overriden by the <a href="/web-llvm/docs/api/classes/llvm/target">Target</a>. The addPre/Post methods with empty header implementations allow injecting target-specific fixups just before or after major stages. Additionally, targets have the flexibility to change pass order within a stage by overriding default implementation of addStage routines below. Each technique has maintainability tradeoffs because alternate pass orders are not well supported. addPre/Post works better if the target pass is easily tied to a common pass. But if it has subtle dependencies on multiple passes, the target should override the stage instead.</p>


<p>Definition at line 417 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/passes/codegenpassbuilder-h">CodeGenPassBuilder.h</a>.</p>


<p>References <a href="#a22fe41485e53804d696235cc418139d3">llvm::CodeGenPassBuilder&lt; DerivedT, TargetMachineT &gt;::addFastRegAlloc</a>, <a href="#aa3cda6e4a4f17e5759b544a4c7ec494c">llvm::CodeGenPassBuilder&lt; DerivedT, TargetMachineT &gt;::addMachinePasses</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#ad16d2d781480402236239b1a788d96c2ad974e9d034ddb6f17c04a7464bee7f1f">llvm::AlwaysOutline</a>, <a href="#af027a2e3b2cd80c416d04bc509dd9b43">llvm::CodeGenPassBuilder&lt; DerivedT, TargetMachineT &gt;::getOptLevel</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#ad16d2d781480402236239b1a788d96c2a195096192885c0c4a0ee1a4d8d0712bc">llvm::NeverOutline</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a8ec1bf8d7b792ca9fac56f8514db18d2a6adf97f83acf6453d4a6a4b1070f3754">llvm::None</a>, <a href="#a9a8ef18a6785a2e0c11995308ccfba2b">llvm::CodeGenPassBuilder&lt; DerivedT, TargetMachineT &gt;::Opt</a>, <a href="/web-llvm/docs/api/classes/llvm/error/#a4dfd0813c3d0e0a30439b5a3e9196b59">llvm::Error::success</a> and <a href="#a534105ec90dac84f7e87451abf4b528d">llvm::CodeGenPassBuilder&lt; DerivedT, TargetMachineT &gt;::TM</a>.</p>


<p>Referenced by <a href="#aa3cda6e4a4f17e5759b544a4c7ec494c">llvm::CodeGenPassBuilder&lt; DerivedT, TargetMachineT &gt;::addMachinePasses</a> and <a href="#a6476029eb211f7d7bc0bf419d58ac6c6">llvm::CodeGenPassBuilder&lt; DerivedT, TargetMachineT &gt;::buildPipeline</a>.</p>

</div>
</div>

### addMachineSSAOptimization() {#a920cca6ac99ee512714d624a25a90d34}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<div class="doxyMemberTemplate">template &lt;typename DerivedT, typename TargetMachineT&gt;</div>
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void llvm::CodeGenPassBuilder&lt; Derived, TargetMachineT &gt;::addMachineSSAOptimization (<a href="/web-llvm/docs/api/classes/llvm/codegenpassbuilder/addmachinepass">AddMachinePass</a> &amp; addPass)</td>
</tr>
</table>
</td>
<td class="doxyMemberLabelsRight">
<span class="doxyMemberLabels">
<span class="doxyMemberLabel protected">protected</span>
</span>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Methods with trivial inline returns are convenient points in the common codegen pass pipeline where targets may insert passes.</p>


<p>Add passes that optimize machine instructions in SSA form.</p>


<p>Methods with out-of-line standard implementations are major CodeGen stages called by addMachinePasses. Some targets may override major stages when inserting passes is insufficient, but maintaining overriden stages is more work. addMachineSSAOptimization - Add standard passes that optimize machine instructions in SSA form.</p>


<p>Definition at line 443 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/passes/codegenpassbuilder-h">CodeGenPassBuilder.h</a>.</p>


<p>Reference <a href="#a920cca6ac99ee512714d624a25a90d34">llvm::CodeGenPassBuilder&lt; DerivedT, TargetMachineT &gt;::addMachineSSAOptimization</a>.</p>


<p>Referenced by <a href="#a920cca6ac99ee512714d624a25a90d34">llvm::CodeGenPassBuilder&lt; DerivedT, TargetMachineT &gt;::addMachineSSAOptimization</a>.</p>

</div>
</div>

### addOptimizedRegAlloc() {#a73a36580247da797a62c3609afe8e1e9}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<div class="doxyMemberTemplate">template &lt;typename DerivedT, typename TargetMachineT&gt;</div>
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void llvm::CodeGenPassBuilder&lt; Derived, TargetMachineT &gt;::addOptimizedRegAlloc (<a href="/web-llvm/docs/api/classes/llvm/codegenpassbuilder/addmachinepass">AddMachinePass</a> &amp; addPass)</td>
</tr>
</table>
</td>
<td class="doxyMemberLabelsRight">
<span class="doxyMemberLabels">
<span class="doxyMemberLabel protected">protected</span>
</span>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>addOptimizedRegAlloc - Add passes related to register allocation.</p>


<p>Add standard target-independent passes that are tightly coupled with optimized register allocation, including coalescing, machine instruction scheduling, and register allocation itself.</p>


<p><a href="/web-llvm/docs/api/classes/llvm/codegentargetmachineimpl">CodeGenTargetMachineImpl</a> provides standard regalloc passes for most targets.</p>


<p>Definition at line 452 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/passes/codegenpassbuilder-h">CodeGenPassBuilder.h</a>.</p>


<p>References <a href="#a73a36580247da797a62c3609afe8e1e9">llvm::CodeGenPassBuilder&lt; DerivedT, TargetMachineT &gt;::addOptimizedRegAlloc</a>, <a href="#a9b736691b65c34ed04d495d4e1166a39">llvm::CodeGenPassBuilder&lt; DerivedT, TargetMachineT &gt;::addRegAssignmentOptimized</a> and <a href="#a9a8ef18a6785a2e0c11995308ccfba2b">llvm::CodeGenPassBuilder&lt; DerivedT, TargetMachineT &gt;::Opt</a>.</p>


<p>Referenced by <a href="#a73a36580247da797a62c3609afe8e1e9">llvm::CodeGenPassBuilder&lt; DerivedT, TargetMachineT &gt;::addOptimizedRegAlloc</a>.</p>

</div>
</div>

### addPassesToHandleExceptions() {#af1e8527d2d52590304877f95c649aa71}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<div class="doxyMemberTemplate">template &lt;typename DerivedT, typename TargetMachineT&gt;</div>
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void llvm::CodeGenPassBuilder&lt; Derived, TargetMachineT &gt;::addPassesToHandleExceptions (<a href="/web-llvm/docs/api/classes/llvm/codegenpassbuilder/addirpass">AddIRPass</a> &amp; addPass)</td>
</tr>
</table>
</td>
<td class="doxyMemberLabelsRight">
<span class="doxyMemberLabels">
<span class="doxyMemberLabel protected">protected</span>
</span>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Add passes to lower exception handling for the code generator.</p>


<p>Turn exception handling constructs into something the code generators can handle.</p>


<p>Definition at line 420 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/passes/codegenpassbuilder-h">CodeGenPassBuilder.h</a>.</p>


<p>References <a href="#af1e8527d2d52590304877f95c649aa71">llvm::CodeGenPassBuilder&lt; DerivedT, TargetMachineT &gt;::addPassesToHandleExceptions</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a2ca3855108426698ff21517a7c884c84a7e6bb0931a72759d39514aa924b420bc">llvm::AIX</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a2ca3855108426698ff21517a7c884c84a47f45e65244c17ec9fa8771a5c6d60e1">llvm::ARM</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/silowercontrolflow-cpp/#a4868c5d81c5ccc98c47aeab6244346a0">assert</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a2ca3855108426698ff21517a7c884c84ab4fe87e4046ecd1f9f3d96bbf63822b3">llvm::DwarfCFI</a>, <a href="/web-llvm/docs/api/classes/llvm/mcasminfo/#af2741cb32381997a1e0f074f63d977ae">llvm::MCAsmInfo::getExceptionHandlingType</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a2ca3855108426698ff21517a7c884c84a6adf97f83acf6453d4a6a4b1070f3754">llvm::None</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a2ca3855108426698ff21517a7c884c84a0f60fd9b862dff366e18e32c6d98d96b">llvm::SjLj</a>, <a href="#a534105ec90dac84f7e87451abf4b528d">llvm::CodeGenPassBuilder&lt; DerivedT, TargetMachineT &gt;::TM</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a2ca3855108426698ff21517a7c884c84af93da81fd23e2eeaf8de29b04bb2399f">llvm::Wasm</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a2ca3855108426698ff21517a7c884c84ae06fc7407f764e5ccf2e67ccbe17accd">llvm::WinEH</a> and <a href="/web-llvm/docs/api/namespaces/llvm/#a2ca3855108426698ff21517a7c884c84a1e96588966115565402c00e156423f65">llvm::ZOS</a>.</p>


<p>Referenced by <a href="#a7b58e0c440a2d9ee99b03789cbd10253">llvm::CodeGenPassBuilder&lt; DerivedT, TargetMachineT &gt;::addISelPasses</a> and <a href="#af1e8527d2d52590304877f95c649aa71">llvm::CodeGenPassBuilder&lt; DerivedT, TargetMachineT &gt;::addPassesToHandleExceptions</a>.</p>

</div>
</div>

### addPostRegAlloc() {#a049e7f55b396434a1455d53aba79c259}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<div class="doxyMemberTemplate">template &lt;typename DerivedT, typename TargetMachineT&gt;</div>
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void llvm::CodeGenPassBuilder&lt; DerivedT, TargetMachineT &gt;::addPostRegAlloc (<a href="/web-llvm/docs/api/classes/llvm/codegenpassbuilder/addmachinepass">AddMachinePass</a> &amp;)</td>
</tr>
</table>
</td>
<td class="doxyMemberLabelsRight">
<span class="doxyMemberLabels">
<span class="doxyMemberLabel inline">inline</span>
<span class="doxyMemberLabel protected">protected</span>
</span>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>This method may be implemented by targets that want to run passes after register allocation pass pipeline but before prolog-epilog insertion.</p>

<p>Definition at line 334 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/passes/codegenpassbuilder-h">CodeGenPassBuilder.h</a>.</p>

</div>
</div>

### addPostRewrite() {#acd6b0eade594096f793ab6d550d33ff6}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<div class="doxyMemberTemplate">template &lt;typename DerivedT, typename TargetMachineT&gt;</div>
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void llvm::CodeGenPassBuilder&lt; DerivedT, TargetMachineT &gt;::addPostRewrite (<a href="/web-llvm/docs/api/classes/llvm/codegenpassbuilder/addmachinepass">AddMachinePass</a> &amp;)</td>
</tr>
</table>
</td>
<td class="doxyMemberLabelsRight">
<span class="doxyMemberLabels">
<span class="doxyMemberLabel inline">inline</span>
<span class="doxyMemberLabel protected">protected</span>
</span>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Add passes to be run immediately after virtual registers are rewritten to physical registers.</p>

<p>Definition at line 330 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/passes/codegenpassbuilder-h">CodeGenPassBuilder.h</a>.</p>

</div>
</div>

### addPreEmitPass() {#ad16b79ac352d540374ff9f433fd72748}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<div class="doxyMemberTemplate">template &lt;typename DerivedT, typename TargetMachineT&gt;</div>
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void llvm::CodeGenPassBuilder&lt; DerivedT, TargetMachineT &gt;::addPreEmitPass (<a href="/web-llvm/docs/api/classes/llvm/codegenpassbuilder/addmachinepass">AddMachinePass</a> &amp;)</td>
</tr>
</table>
</td>
<td class="doxyMemberLabelsRight">
<span class="doxyMemberLabels">
<span class="doxyMemberLabel inline">inline</span>
<span class="doxyMemberLabel protected">protected</span>
</span>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>This pass may be implemented by targets that want to run passes immediately before machine code is emitted.</p>

<p>Definition at line 342 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/passes/codegenpassbuilder-h">CodeGenPassBuilder.h</a>.</p>

</div>
</div>

### addPreEmitPass2() {#acbee0ccdec0f7e6003a5905a236f03f0}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<div class="doxyMemberTemplate">template &lt;typename DerivedT, typename TargetMachineT&gt;</div>
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void llvm::CodeGenPassBuilder&lt; DerivedT, TargetMachineT &gt;::addPreEmitPass2 (<a href="/web-llvm/docs/api/classes/llvm/codegenpassbuilder/addmachinepass">AddMachinePass</a> &amp;)</td>
</tr>
</table>
</td>
<td class="doxyMemberLabelsRight">
<span class="doxyMemberLabels">
<span class="doxyMemberLabel inline">inline</span>
<span class="doxyMemberLabel protected">protected</span>
</span>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Targets may add passes immediately before machine code is emitted in this callback.</p>


<p>This is called even later than <span class="doxyComputerOutput">addPreEmitPass</span>.</p>


<p>Definition at line 349 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/passes/codegenpassbuilder-h">CodeGenPassBuilder.h</a>.</p>

</div>
</div>

### addPreGlobalInstructionSelect() {#a1e436c30d1765ee112af32831e8d5d19}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<div class="doxyMemberTemplate">template &lt;typename DerivedT, typename TargetMachineT&gt;</div>
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void llvm::CodeGenPassBuilder&lt; DerivedT, TargetMachineT &gt;::addPreGlobalInstructionSelect (<a href="/web-llvm/docs/api/classes/llvm/codegenpassbuilder/addmachinepass">AddMachinePass</a> &amp;)</td>
</tr>
</table>
</td>
<td class="doxyMemberLabelsRight">
<span class="doxyMemberLabels">
<span class="doxyMemberLabel inline">inline</span>
<span class="doxyMemberLabel protected">protected</span>
</span>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>This method may be implemented by targets that want to run passes immediately before the (global) instruction selection.</p>

<p>Definition at line 392 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/passes/codegenpassbuilder-h">CodeGenPassBuilder.h</a>.</p>

</div>
</div>

### addPreISel() {#afc6649ff4d117ac2dd598bdbeca9cce7}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<div class="doxyMemberTemplate">template &lt;typename DerivedT, typename TargetMachineT&gt;</div>
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void llvm::CodeGenPassBuilder&lt; DerivedT, TargetMachineT &gt;::addPreISel (<a href="/web-llvm/docs/api/classes/llvm/codegenpassbuilder/addirpass">AddIRPass</a> &amp;)</td>
</tr>
</table>
</td>
<td class="doxyMemberLabelsRight">
<span class="doxyMemberLabels">
<span class="doxyMemberLabel inline">inline</span>
<span class="doxyMemberLabel protected">protected</span>
</span>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>{{@ For GlobalISel</p>


<p>addPreISel - This method should add any "last minute" LLVM-&gt;LLVM passes (which are run just before instruction selector).</p>


<p>Definition at line 356 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/passes/codegenpassbuilder-h">CodeGenPassBuilder.h</a>.</p>

</div>
</div>

### addPreLegalizeMachineIR() {#aed9d1553e76d562bcad39c4dd6922f17}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<div class="doxyMemberTemplate">template &lt;typename DerivedT, typename TargetMachineT&gt;</div>
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void llvm::CodeGenPassBuilder&lt; DerivedT, TargetMachineT &gt;::addPreLegalizeMachineIR (<a href="/web-llvm/docs/api/classes/llvm/codegenpassbuilder/addmachinepass">AddMachinePass</a> &amp;)</td>
</tr>
</table>
</td>
<td class="doxyMemberLabelsRight">
<span class="doxyMemberLabels">
<span class="doxyMemberLabel inline">inline</span>
<span class="doxyMemberLabel protected">protected</span>
</span>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>This method may be implemented by targets that want to run passes immediately before legalization.</p>

<p>Definition at line 369 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/passes/codegenpassbuilder-h">CodeGenPassBuilder.h</a>.</p>

</div>
</div>

### addPreRegAlloc() {#a551342b9f2f56afd7dd999ac2da202a2}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<div class="doxyMemberTemplate">template &lt;typename DerivedT, typename TargetMachineT&gt;</div>
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void llvm::CodeGenPassBuilder&lt; DerivedT, TargetMachineT &gt;::addPreRegAlloc (<a href="/web-llvm/docs/api/classes/llvm/codegenpassbuilder/addmachinepass">AddMachinePass</a> &amp;)</td>
</tr>
</table>
</td>
<td class="doxyMemberLabelsRight">
<span class="doxyMemberLabels">
<span class="doxyMemberLabel inline">inline</span>
<span class="doxyMemberLabel protected">protected</span>
</span>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>This method may be implemented by targets that want to run passes immediately before register allocation.</p>

<p>Definition at line 312 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/passes/codegenpassbuilder-h">CodeGenPassBuilder.h</a>.</p>

</div>
</div>

### addPreRegBankSelect() {#ad0f79ace134c31b4e445707078072766}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<div class="doxyMemberTemplate">template &lt;typename DerivedT, typename TargetMachineT&gt;</div>
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void llvm::CodeGenPassBuilder&lt; DerivedT, TargetMachineT &gt;::addPreRegBankSelect (<a href="/web-llvm/docs/api/classes/llvm/codegenpassbuilder/addmachinepass">AddMachinePass</a> &amp;)</td>
</tr>
</table>
</td>
<td class="doxyMemberLabelsRight">
<span class="doxyMemberLabels">
<span class="doxyMemberLabel inline">inline</span>
<span class="doxyMemberLabel protected">protected</span>
</span>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>This method may be implemented by targets that want to run passes immediately before the register bank selection.</p>

<p>Definition at line 380 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/passes/codegenpassbuilder-h">CodeGenPassBuilder.h</a>.</p>

</div>
</div>

### addPreRewrite() {#a01e72190d04d4448265cf8f5a367a614}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<div class="doxyMemberTemplate">template &lt;typename DerivedT, typename TargetMachineT&gt;</div>
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void llvm::CodeGenPassBuilder&lt; DerivedT, TargetMachineT &gt;::addPreRewrite (<a href="/web-llvm/docs/api/classes/llvm/codegenpassbuilder/addmachinepass">AddMachinePass</a> &amp;)</td>
</tr>
</table>
</td>
<td class="doxyMemberLabelsRight">
<span class="doxyMemberLabels">
<span class="doxyMemberLabel inline">inline</span>
<span class="doxyMemberLabel protected">protected</span>
</span>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>addPreRewrite - Add passes to the optimized register allocation pipeline after register allocation is complete, but before virtual registers are rewritten to physical registers.</p>


<p>These passes must preserve <a href="/web-llvm/docs/api/classes/llvm/virtregmap">VirtRegMap</a> and <a href="/web-llvm/docs/api/classes/llvm/liveintervals">LiveIntervals</a>, and when running after RABasic or <a href="/web-llvm/docs/api/classes/llvm/ragreedy">RAGreedy</a>, they should take advantage of <a href="/web-llvm/docs/api/classes/llvm/liveregmatrix">LiveRegMatrix</a>. When these passes run, <a href="/web-llvm/docs/api/classes/llvm/virtregmap">VirtRegMap</a> contains legal physreg assignments for all virtual registers.</p>


<p>Note if the target overloads addRegAssignAndRewriteOptimized, this may not be honored. This is also not generally used for the fast variant, where the allocation and rewriting are done in one pass.</p>


<p>Definition at line 326 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/passes/codegenpassbuilder-h">CodeGenPassBuilder.h</a>.</p>

</div>
</div>

### addPreSched2() {#a399ba5ae9a5e17572286d4466a68a6ed}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<div class="doxyMemberTemplate">template &lt;typename DerivedT, typename TargetMachineT&gt;</div>
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void llvm::CodeGenPassBuilder&lt; DerivedT, TargetMachineT &gt;::addPreSched2 (<a href="/web-llvm/docs/api/classes/llvm/codegenpassbuilder/addmachinepass">AddMachinePass</a> &amp;)</td>
</tr>
</table>
</td>
<td class="doxyMemberLabelsRight">
<span class="doxyMemberLabels">
<span class="doxyMemberLabel inline">inline</span>
<span class="doxyMemberLabel protected">protected</span>
</span>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>This method may be implemented by targets that want to run passes after prolog-epilog insertion and before the second instruction scheduling pass.</p>

<p>Definition at line 338 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/passes/codegenpassbuilder-h">CodeGenPassBuilder.h</a>.</p>

</div>
</div>

### addRegAllocPass() {#a329811e8a7ffa3b23fecec167f9fc31f}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<div class="doxyMemberTemplate">template &lt;typename DerivedT, typename TargetMachineT&gt;</div>
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void llvm::CodeGenPassBuilder&lt; Derived, TargetMachineT &gt;::addRegAllocPass (<a href="/web-llvm/docs/api/classes/llvm/codegenpassbuilder/addmachinepass">AddMachinePass</a> &amp; addPass, bool Optimized)</td>
</tr>
</table>
</td>
<td class="doxyMemberLabelsRight">
<span class="doxyMemberLabels">
<span class="doxyMemberLabel protected">protected</span>
</span>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>addMachinePasses helper to create the target-selected or overriden regalloc pass.</p>


<p>Find and instantiate the register allocation pass requested by this target at the current optimization level.</p>


<p>Different register allocators are defined as separate passes because they may require different analysis.</p>


<p>Definition at line 480 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/passes/codegenpassbuilder-h">CodeGenPassBuilder.h</a>.</p>


<p>Reference <a href="#a329811e8a7ffa3b23fecec167f9fc31f">llvm::CodeGenPassBuilder&lt; DerivedT, TargetMachineT &gt;::addRegAllocPass</a>.</p>


<p>Referenced by <a href="#a329811e8a7ffa3b23fecec167f9fc31f">llvm::CodeGenPassBuilder&lt; DerivedT, TargetMachineT &gt;::addRegAllocPass</a>, <a href="#a1e77277704de3f76249f730ee55dc7b9">llvm::CodeGenPassBuilder&lt; DerivedT, TargetMachineT &gt;::addRegAssignmentFast</a> and <a href="#a9b736691b65c34ed04d495d4e1166a39">llvm::CodeGenPassBuilder&lt; DerivedT, TargetMachineT &gt;::addRegAssignmentOptimized</a>.</p>

</div>
</div>

### addRegAssignmentFast() {#a1e77277704de3f76249f730ee55dc7b9}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<div class="doxyMemberTemplate">template &lt;typename DerivedT, typename TargetMachineT&gt;</div>
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">Error llvm::CodeGenPassBuilder&lt; Derived, TargetMachineT &gt;::addRegAssignmentFast (<a href="/web-llvm/docs/api/classes/llvm/codegenpassbuilder/addmachinepass">AddMachinePass</a> &amp; addPass)</td>
</tr>
</table>
</td>
<td class="doxyMemberLabelsRight">
<span class="doxyMemberLabels">
<span class="doxyMemberLabel protected">protected</span>
</span>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Add core register alloator passes which do the actual register assignment and rewriting.</p>


<dl class="doxySectionUser">
<dt>Returns</dt>
<dd><p>true if any passes were added.</p></dd>
</dl>


<p>Definition at line 484 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/passes/codegenpassbuilder-h">CodeGenPassBuilder.h</a>.</p>


<p>References <a href="#a329811e8a7ffa3b23fecec167f9fc31f">llvm::CodeGenPassBuilder&lt; DerivedT, TargetMachineT &gt;::addRegAllocPass</a>, <a href="#a1e77277704de3f76249f730ee55dc7b9">llvm::CodeGenPassBuilder&lt; DerivedT, TargetMachineT &gt;::addRegAssignmentFast</a> and <a href="/web-llvm/docs/api/classes/llvm/error/#a4dfd0813c3d0e0a30439b5a3e9196b59">llvm::Error::success</a>.</p>


<p>Referenced by <a href="#a1e77277704de3f76249f730ee55dc7b9">llvm::CodeGenPassBuilder&lt; DerivedT, TargetMachineT &gt;::addRegAssignmentFast</a>.</p>

</div>
</div>

### addRegAssignmentOptimized() {#a9b736691b65c34ed04d495d4e1166a39}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<div class="doxyMemberTemplate">template &lt;typename DerivedT, typename TargetMachineT&gt;</div>
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">Error llvm::CodeGenPassBuilder&lt; Derived, TargetMachineT &gt;::addRegAssignmentOptimized (<a href="/web-llvm/docs/api/classes/llvm/codegenpassbuilder/addmachinepass">AddMachinePass</a> &amp; addPass)</td>
</tr>
</table>
</td>
<td class="doxyMemberLabelsRight">
<span class="doxyMemberLabels">
<span class="doxyMemberLabel protected">protected</span>
</span>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 485 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/passes/codegenpassbuilder-h">CodeGenPassBuilder.h</a>.</p>


<p>References <a href="#a329811e8a7ffa3b23fecec167f9fc31f">llvm::CodeGenPassBuilder&lt; DerivedT, TargetMachineT &gt;::addRegAllocPass</a>, <a href="#a9b736691b65c34ed04d495d4e1166a39">llvm::CodeGenPassBuilder&lt; DerivedT, TargetMachineT &gt;::addRegAssignmentOptimized</a> and <a href="/web-llvm/docs/api/classes/llvm/error/#a4dfd0813c3d0e0a30439b5a3e9196b59">llvm::Error::success</a>.</p>


<p>Referenced by <a href="#a73a36580247da797a62c3609afe8e1e9">llvm::CodeGenPassBuilder&lt; DerivedT, TargetMachineT &gt;::addOptimizedRegAlloc</a> and <a href="#a9b736691b65c34ed04d495d4e1166a39">llvm::CodeGenPassBuilder&lt; DerivedT, TargetMachineT &gt;::addRegAssignmentOptimized</a>.</p>

</div>
</div>

### addRegBankSelect() {#a3e88c5ab231653e3fccd5ac4c32f00c0}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<div class="doxyMemberTemplate">template &lt;typename DerivedT, typename TargetMachineT&gt;</div>
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">Error llvm::CodeGenPassBuilder&lt; DerivedT, TargetMachineT &gt;::addRegBankSelect (<a href="/web-llvm/docs/api/classes/llvm/codegenpassbuilder/addmachinepass">AddMachinePass</a> &amp;)</td>
</tr>
</table>
</td>
<td class="doxyMemberLabelsRight">
<span class="doxyMemberLabels">
<span class="doxyMemberLabel inline">inline</span>
<span class="doxyMemberLabel protected">protected</span>
</span>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>This method should install a register bank selector pass, which assigns register banks to virtual registers without a register class or register banks.</p>

<p>Definition at line 385 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/passes/codegenpassbuilder-h">CodeGenPassBuilder.h</a>.</p>


<p>Referenced by <a href="#a6def3ee2976adc8630894b508c7c7402">llvm::CodeGenPassBuilder&lt; DerivedT, TargetMachineT &gt;::addCoreISelPasses</a>.</p>

</div>
</div>

### addTargetRegisterAllocator() {#ac9d8fa0c86b7b514e80a528d85b4330a}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<div class="doxyMemberTemplate">template &lt;typename DerivedT, typename TargetMachineT&gt;</div>
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void llvm::CodeGenPassBuilder&lt; Derived, TargetMachineT &gt;::addTargetRegisterAllocator (<a href="/web-llvm/docs/api/classes/llvm/codegenpassbuilder/addmachinepass">AddMachinePass</a> &amp; addPass, bool Optimized)</td>
</tr>
</table>
</td>
<td class="doxyMemberLabelsRight">
<span class="doxyMemberLabels">
<span class="doxyMemberLabel protected">protected</span>
</span>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Utilities for targets to add passes to the pass manager.</p>


<p><a href="/web-llvm/docs/api/classes/llvm/register">Register</a> Allocation <a href="/web-llvm/docs/api/classes/llvm/pass">Pass</a> Configuration.</p>


<p>createTargetRegisterAllocator - Create the register allocator pass for this target at the current optimization level.</p>


<p>Instantiate the default register allocator pass for this target for either the optimized or unoptimized allocation path. This will be added to the pass manager by addFastRegAlloc in the unoptimized case or addOptimizedRegAlloc in the optimized case.</p>


<p>A target that uses the standard regalloc pass order for fast or optimized allocation may still override this for per-target regalloc selection. But -regalloc=... always takes precedence.</p>


<p>Definition at line 476 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/passes/codegenpassbuilder-h">CodeGenPassBuilder.h</a>.</p>


<p>Reference <a href="#ac9d8fa0c86b7b514e80a528d85b4330a">llvm::CodeGenPassBuilder&lt; DerivedT, TargetMachineT &gt;::addTargetRegisterAllocator</a>.</p>


<p>Referenced by <a href="#ac9d8fa0c86b7b514e80a528d85b4330a">llvm::CodeGenPassBuilder&lt; DerivedT, TargetMachineT &gt;::addTargetRegisterAllocator</a>.</p>

</div>
</div>

### disablePass() {#abf8928310db68013b2d547df352d9345}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<div class="doxyMemberTemplate">template &lt;typename... PassTs&gt;</div>
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void llvm::CodeGenPassBuilder&lt; DerivedT, TargetMachineT &gt;::disablePass ()</td>
</tr>
</table>
</td>
<td class="doxyMemberLabelsRight">
<span class="doxyMemberLabels">
<span class="doxyMemberLabel inline">inline</span>
<span class="doxyMemberLabel protected">protected</span>
</span>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Allow the target to disable a specific pass by default.</p>


<p>Backend can declare unwanted passes in constructor.</p>


<p>Definition at line 489 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/passes/codegenpassbuilder-h">CodeGenPassBuilder.h</a>.</p>

</div>
</div>

### getOptLevel() {#af027a2e3b2cd80c416d04bc509dd9b43}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<div class="doxyMemberTemplate">template &lt;typename DerivedT, typename TargetMachineT&gt;</div>
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">CodeGenOptLevel llvm::CodeGenPassBuilder&lt; DerivedT, TargetMachineT &gt;::getOptLevel ()</td>
</tr>
</table>
</td>
<td class="doxyMemberLabelsRight">
<span class="doxyMemberLabels">
<span class="doxyMemberLabel inline">inline</span>
<span class="doxyMemberLabel protected">protected</span>
</span>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 276 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/passes/codegenpassbuilder-h">CodeGenPassBuilder.h</a>.</p>


<p>Referenced by <a href="#a9e1385ad22d85a41207f9c1e158788ea">llvm::CodeGenPassBuilder&lt; DerivedT, TargetMachineT &gt;::addCodeGenPrepare</a>, <a href="#ad6d8ab9f89af9e5c0329a300b3dfd7ab">llvm::CodeGenPassBuilder&lt; DerivedT, TargetMachineT &gt;::addIRPasses</a> and <a href="#aa3cda6e4a4f17e5759b544a4c7ec494c">llvm::CodeGenPassBuilder&lt; DerivedT, TargetMachineT &gt;::addMachinePasses</a>.</p>

</div>
</div>

### getTM() {#a74d04e121942d5e2fb2b8d1772d41a71}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<div class="doxyMemberTemplate">template &lt;typename TMC&gt;</div>
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">TMC &amp; llvm::CodeGenPassBuilder&lt; DerivedT, TargetMachineT &gt;::getTM ()</td>
</tr>
</table>
</td>
<td class="doxyMemberLabelsRight">
<span class="doxyMemberLabels">
<span class="doxyMemberLabel inline">inline</span>
<span class="doxyMemberLabel protected">protected</span>
</span>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 275 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/passes/codegenpassbuilder-h">CodeGenPassBuilder.h</a>.</p>

</div>
</div>

### insertPass() {#a16b9126d671cbce7e45e877cc583d405}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<div class="doxyMemberTemplate">template &lt;typename TargetPassT, typename InsertedPassT&gt;</div>
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void llvm::CodeGenPassBuilder&lt; DerivedT, TargetMachineT &gt;::insertPass (InsertedPassT &amp;&amp; Pass)</td>
</tr>
</table>
</td>
<td class="doxyMemberLabelsRight">
<span class="doxyMemberLabels">
<span class="doxyMemberLabel inline">inline</span>
<span class="doxyMemberLabel protected">protected</span>
</span>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Insert InsertedPass pass after TargetPass pass.</p>


<p>Only machine function passes are supported.</p>


<p>Definition at line 497 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/passes/codegenpassbuilder-h">CodeGenPassBuilder.h</a>.</p>

</div>
</div>

### isGlobalISelAbortEnabled() {#a454c24dde3f14412c63b3ae23f048274}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<div class="doxyMemberTemplate">template &lt;typename DerivedT, typename TargetMachineT&gt;</div>
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool llvm::CodeGenPassBuilder&lt; DerivedT, TargetMachineT &gt;::isGlobalISelAbortEnabled ()</td>
</tr>
</table>
</td>
<td class="doxyMemberLabelsRight">
<span class="doxyMemberLabels">
<span class="doxyMemberLabel inline">inline</span>
<span class="doxyMemberLabel protected">protected</span>
</span>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p><a href="/web-llvm/docs/api/namespaces/llvm/check">Check</a> whether or not GlobalISel should abort on error.</p>


<p>When this is disabled, GlobalISel will fall back on SDISel instead of erroring out.</p>


<p>Definition at line 281 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/passes/codegenpassbuilder-h">CodeGenPassBuilder.h</a>.</p>


<p>Referenced by <a href="#a6def3ee2976adc8630894b508c7c7402">llvm::CodeGenPassBuilder&lt; DerivedT, TargetMachineT &gt;::addCoreISelPasses</a>.</p>

</div>
</div>

### reportDiagnosticWhenGlobalISelFallback() {#af6db0af78f5cdf3125396c8572f37417}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<div class="doxyMemberTemplate">template &lt;typename DerivedT, typename TargetMachineT&gt;</div>
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool llvm::CodeGenPassBuilder&lt; DerivedT, TargetMachineT &gt;::reportDiagnosticWhenGlobalISelFallback ()</td>
</tr>
</table>
</td>
<td class="doxyMemberLabelsRight">
<span class="doxyMemberLabels">
<span class="doxyMemberLabel inline">inline</span>
<span class="doxyMemberLabel protected">protected</span>
</span>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p><a href="/web-llvm/docs/api/namespaces/llvm/check">Check</a> whether or not a diagnostic should be emitted when GlobalISel uses the fallback path.</p>


<p>In other words, it will emit a diagnostic when GlobalISel failed and isGlobalISelAbortEnabled is false.</p>


<p>Definition at line 288 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/passes/codegenpassbuilder-h">CodeGenPassBuilder.h</a>.</p>


<p>Referenced by <a href="#a6def3ee2976adc8630894b508c7c7402">llvm::CodeGenPassBuilder&lt; DerivedT, TargetMachineT &gt;::addCoreISelPasses</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Private Member Functions

### derived() {#a254906540e0cfbcc692799d044ee60e4}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<div class="doxyMemberTemplate">template &lt;typename DerivedT, typename TargetMachineT&gt;</div>
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">DerivedT &amp; llvm::CodeGenPassBuilder&lt; DerivedT, TargetMachineT &gt;::derived ()</td>
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



<p>Definition at line 506 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/passes/codegenpassbuilder-h">CodeGenPassBuilder.h</a>.</p>

</div>
</div>

### derived() {#a0e64497c02ad69345f515516685c9af5}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<div class="doxyMemberTemplate">template &lt;typename DerivedT, typename TargetMachineT&gt;</div>
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">const DerivedT &amp; llvm::CodeGenPassBuilder&lt; DerivedT, TargetMachineT &gt;::derived ()</td>
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



<p>Definition at line 507 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/passes/codegenpassbuilder-h">CodeGenPassBuilder.h</a>.</p>

</div>
</div>

### runBeforeAdding() {#ac129e4826b19e5a844fa51debfdf23fc}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<div class="doxyMemberTemplate">template &lt;typename DerivedT, typename TargetMachineT&gt;</div>
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool llvm::CodeGenPassBuilder&lt; DerivedT, TargetMachineT &gt;::runBeforeAdding (<a href="/web-llvm/docs/api/classes/llvm/stringref">StringRef</a> Name)</td>
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



<p>Definition at line 511 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/passes/codegenpassbuilder-h">CodeGenPassBuilder.h</a>.</p>

</div>
</div>

### setStartStopPasses() {#a5402ebed2a6335b3a482b20c540c7232}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<div class="doxyMemberTemplate">template &lt;typename DerivedT, typename TargetMachineT&gt;</div>
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void llvm::CodeGenPassBuilder&lt; Derived, TargetMachineT &gt;::setStartStopPasses (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/structs/llvm/targetpassconfig/startstopinfo">TargetPassConfig::StartStopInfo</a> &amp; Info)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 518 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/passes/codegenpassbuilder-h">CodeGenPassBuilder.h</a>.</p>

</div>
</div>

### verifyStartStop() {#af0d1d92762fab6e66573c3ebb9b6caaf}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<div class="doxyMemberTemplate">template &lt;typename DerivedT, typename TargetMachineT&gt;</div>
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">Error llvm::CodeGenPassBuilder&lt; Derived, TargetMachineT &gt;::verifyStartStop (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/structs/llvm/targetpassconfig/startstopinfo">TargetPassConfig::StartStopInfo</a> &amp; Info)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 520 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/passes/codegenpassbuilder-h">CodeGenPassBuilder.h</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Protected Member Attributes

### Opt {#a9a8ef18a6785a2e0c11995308ccfba2b}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<div class="doxyMemberTemplate">template &lt;typename DerivedT, typename TargetMachineT&gt;</div>
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">CGPassBuilderOption llvm::CodeGenPassBuilder&lt; DerivedT, TargetMachineT &gt;::Opt</td>
</tr>
</table>
</td>
<td class="doxyMemberLabelsRight">
<span class="doxyMemberLabels">
<span class="doxyMemberLabel protected">protected</span>
</span>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 272 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/passes/codegenpassbuilder-h">CodeGenPassBuilder.h</a>.</p>


<p>Referenced by <a href="#ac7afb20962e71fd338b570303da8c45f">llvm::CodeGenPassBuilder&lt; DerivedT, TargetMachineT &gt;::addBlockPlacement</a>, <a href="#a9e1385ad22d85a41207f9c1e158788ea">llvm::CodeGenPassBuilder&lt; DerivedT, TargetMachineT &gt;::addCodeGenPrepare</a>, <a href="#a6def3ee2976adc8630894b508c7c7402">llvm::CodeGenPassBuilder&lt; DerivedT, TargetMachineT &gt;::addCoreISelPasses</a>, <a href="#ad6d8ab9f89af9e5c0329a300b3dfd7ab">llvm::CodeGenPassBuilder&lt; DerivedT, TargetMachineT &gt;::addIRPasses</a>, <a href="#ab7f25cc708c60ca391b68da2b83935d9">llvm::CodeGenPassBuilder&lt; DerivedT, TargetMachineT &gt;::addISelPrepare</a>, <a href="#aa3cda6e4a4f17e5759b544a4c7ec494c">llvm::CodeGenPassBuilder&lt; DerivedT, TargetMachineT &gt;::addMachinePasses</a>, <a href="#a73a36580247da797a62c3609afe8e1e9">llvm::CodeGenPassBuilder&lt; DerivedT, TargetMachineT &gt;::addOptimizedRegAlloc</a> and <a href="#a6476029eb211f7d7bc0bf419d58ac6c6">llvm::CodeGenPassBuilder&lt; DerivedT, TargetMachineT &gt;::buildPipeline</a>.</p>

</div>
</div>

### PIC {#a8b37f13bb1431bc3965bbdfc110a5fb1}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<div class="doxyMemberTemplate">template &lt;typename DerivedT, typename TargetMachineT&gt;</div>
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">PassInstrumentationCallbacks* llvm::CodeGenPassBuilder&lt; DerivedT, TargetMachineT &gt;::PIC</td>
</tr>
</table>
</td>
<td class="doxyMemberLabelsRight">
<span class="doxyMemberLabels">
<span class="doxyMemberLabel protected">protected</span>
</span>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 273 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/passes/codegenpassbuilder-h">CodeGenPassBuilder.h</a>.</p>


<p>Referenced by <a href="#a6476029eb211f7d7bc0bf419d58ac6c6">llvm::CodeGenPassBuilder&lt; DerivedT, TargetMachineT &gt;::buildPipeline</a>.</p>

</div>
</div>

### TM {#a534105ec90dac84f7e87451abf4b528d}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<div class="doxyMemberTemplate">template &lt;typename DerivedT, typename TargetMachineT&gt;</div>
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">TargetMachineT&amp; llvm::CodeGenPassBuilder&lt; DerivedT, TargetMachineT &gt;::TM</td>
</tr>
</table>
</td>
<td class="doxyMemberLabelsRight">
<span class="doxyMemberLabels">
<span class="doxyMemberLabel protected">protected</span>
</span>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 271 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/passes/codegenpassbuilder-h">CodeGenPassBuilder.h</a>.</p>


<p>Referenced by <a href="#a9e1385ad22d85a41207f9c1e158788ea">llvm::CodeGenPassBuilder&lt; DerivedT, TargetMachineT &gt;::addCodeGenPrepare</a>, <a href="#a6def3ee2976adc8630894b508c7c7402">llvm::CodeGenPassBuilder&lt; DerivedT, TargetMachineT &gt;::addCoreISelPasses</a>, <a href="#ad6d8ab9f89af9e5c0329a300b3dfd7ab">llvm::CodeGenPassBuilder&lt; DerivedT, TargetMachineT &gt;::addIRPasses</a>, <a href="#a7b58e0c440a2d9ee99b03789cbd10253">llvm::CodeGenPassBuilder&lt; DerivedT, TargetMachineT &gt;::addISelPasses</a>, <a href="#ab7f25cc708c60ca391b68da2b83935d9">llvm::CodeGenPassBuilder&lt; DerivedT, TargetMachineT &gt;::addISelPrepare</a>, <a href="#ad632c4c783e5170dd972a8d18836c0e9">llvm::CodeGenPassBuilder&lt; DerivedT, TargetMachineT &gt;::addMachineLateOptimization</a>, <a href="#aa3cda6e4a4f17e5759b544a4c7ec494c">llvm::CodeGenPassBuilder&lt; DerivedT, TargetMachineT &gt;::addMachinePasses</a> and <a href="#af1e8527d2d52590304877f95c649aa71">llvm::CodeGenPassBuilder&lt; DerivedT, TargetMachineT &gt;::addPassesToHandleExceptions</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Private Member Attributes

### AfterCallbacks {#acd9826fb30491a5d69a89545c84d44f2}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<div class="doxyMemberTemplate">template &lt;typename DerivedT, typename TargetMachineT&gt;</div>
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">SmallVector&lt; llvm::unique_function&lt;void(StringRef, MachineFunctionPassManager &amp;)&gt;, 4&gt; llvm::CodeGenPassBuilder&lt; DerivedT, TargetMachineT &gt;::AfterCallbacks</td>
</tr>
</table>
</td>
<td class="doxyMemberLabelsRight">
<span class="doxyMemberLabels">
<span class="doxyMemberLabel mutable">mutable</span>
</span>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 526 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/passes/codegenpassbuilder-h">CodeGenPassBuilder.h</a>.</p>

</div>
</div>

### BeforeCallbacks {#a626f11e8362faef40d41ba537ccf66f6}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<div class="doxyMemberTemplate">template &lt;typename DerivedT, typename TargetMachineT&gt;</div>
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">SmallVector&lt;llvm::unique_function&lt;bool(StringRef)&gt;, 4&gt; llvm::CodeGenPassBuilder&lt; DerivedT, TargetMachineT &gt;::BeforeCallbacks</td>
</tr>
</table>
</td>
<td class="doxyMemberLabelsRight">
<span class="doxyMemberLabels">
<span class="doxyMemberLabel mutable">mutable</span>
</span>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 523 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/passes/codegenpassbuilder-h">CodeGenPassBuilder.h</a>.</p>

</div>
</div>

### Started {#afdfc097647580db5a9ca9a06cb5dd06e}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<div class="doxyMemberTemplate">template &lt;typename DerivedT, typename TargetMachineT&gt;</div>
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool llvm::CodeGenPassBuilder&lt; DerivedT, TargetMachineT &gt;::Started = <a href="/web-llvm/docs/api/files/lib/lib/analysis/basicaliasanalysis-cpp/#af6d5cafbdfc5313e65d990120021a3ec">true</a></td>
</tr>
</table>
</td>
<td class="doxyMemberLabelsRight">
<span class="doxyMemberLabels">
<span class="doxyMemberLabel mutable">mutable</span>
</span>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Helper variable for <span class="doxyComputerOutput">-start-before/-start-after/-stop-before/-stop-after</span></p>

<p>Definition at line 529 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/passes/codegenpassbuilder-h">CodeGenPassBuilder.h</a>.</p>

</div>
</div>

### Stopped {#af749c6158295a5f9b47712e5a5c4cc35}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<div class="doxyMemberTemplate">template &lt;typename DerivedT, typename TargetMachineT&gt;</div>
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool llvm::CodeGenPassBuilder&lt; DerivedT, TargetMachineT &gt;::Stopped = <a href="/web-llvm/docs/api/files/lib/lib/analysis/basicaliasanalysis-cpp/#af6d5cafbdfc5313e65d990120021a3ec">true</a></td>
</tr>
</table>
</td>
<td class="doxyMemberLabelsRight">
<span class="doxyMemberLabels">
<span class="doxyMemberLabel mutable">mutable</span>
</span>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 530 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/passes/codegenpassbuilder-h">CodeGenPassBuilder.h</a>.</p>

</div>
</div>

</div>

<hr/>

The documentation for this class was generated from the following file:

<ul>
<li><a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/passes/codegenpassbuilder-h">CodeGenPassBuilder.h</a></li>
</ul>

<hr/>

<p class="doxyGeneratedBy">Generated via <a href="https://github.com/xpack/doxygen2docusaurus">doxygen2docusaurus</a> by <a href="https://www.doxygen.nl">Doxygen</a> 1.15.0.</p>

</div>
