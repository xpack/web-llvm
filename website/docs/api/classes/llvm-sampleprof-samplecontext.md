---

# DO NOT EDIT!
# Automatically generated via doxygen2docusaurus by Doxygen.

slug: /api/classes/llvm/sampleprof/samplecontext
custom_edit_url: null
toc_max_heading_level: 4
keywords:
  - doxygen
  - reference
  - class

---

<div class="doxyPage">

# `SampleContext` Class



## Declaration

<div class="doxyDeclaration">
class llvm::sampleprof::SampleContext { ... }
</div>

## Included Headers

<div class="doxyIncludesList">#include "<a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/profiledata/sampleprof-h">llvm/ProfileData/SampleProf.h</a>"
</div>

## Public Constructors Index

<table class="doxyMembersIndex">

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ab8ff16dff4a4304435e512fa6bd1066b">SampleContext</a> ()</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#af72a0c462f5d90d3d6c48e6ceaff38a3">SampleContext</a> (StringRef Name)</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a6cec6667c5b4468d44bbedcff1f29e8c">SampleContext</a> (FunctionId Func)</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a1623f5e961234d9e5953084f28892a1c">SampleContext</a> (SampleContextFrames Context, ContextStateMask CState=RawContext)</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a3093181fe818bf3fe03f72887de8943f">SampleContext</a> (StringRef ContextStr, std::list&lt; SampleContextFrameVector &gt; &amp;CSNameTable, ContextStateMask CState=RawContext)</td>
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

## Public Operators Index

<table class="doxyMembersIndex">

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ab5924f265dd624f920db021b65ddfba4">operator SampleContextFrames</a> () const</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a0aa116c8c84f49cc5770fcafc4057c7a">operator==</a> (const SampleContext &amp;That) const</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a95bab793c63f62320667fbf0a17c288a">operator!=</a> (const SampleContext &amp;That) const</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a2f34643744ac2bf92d700a8461d9aeb0">operator&lt;</a> (const SampleContext &amp;That) const</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#acddf84ace68d71cc96ecfdf7da44da58">hasAttribute</a> (ContextAttributeMask A)</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ac1a2adf3cf418221c93db5b17a760a5d">setAttribute</a> (ContextAttributeMask A)</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">uint32_t</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ac14fcf43c57c449e8398370de8d9a2dc">getAllAttributes</a> ()</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#aa7894022c49174ef967469c3ddd81857">setAllAttributes</a> (uint32_t A)</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a3f30fb3b02e2a17d75e3caf5af38eaed">hasState</a> (ContextStateMask S)</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#aa41059d227a82a3a80090c944aa80c5b">setState</a> (ContextStateMask S)</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a4edc88a1dca4a856f34e190c2626f3fc">clearState</a> (ContextStateMask S)</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a3f47a41fc180017373f06a00976d7c5c">hasContext</a> () const</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a742d15f1afc6f1accfa9694e3668ebac">isBaseContext</a> () const</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/sampleprof/functionid">FunctionId</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#aaec6c587638c9dedc9041f186e598196">getFunction</a> () const</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/namespaces/llvm/sampleprof/#a737d65abec7fd88fdb10cfcd209391c2">SampleContextFrames</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a5f6cf6770a2b1c836c02387c1c1b1258">getContextFrames</a> () const</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">std::string</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ade2e9346cc9a993d02dab4742aff2bdf">toString</a> () const</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">uint64_t</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#aa974f8c265b1f6334ffd5df3507371f3">getHashCode</a> () const</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a0fa76143f44e4ba94a2d71a2b97d609d">setFunction</a> (FunctionId NewFunctionID)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Set the name of the function and clear the current context. <a href="#a0fa76143f44e4ba94a2d71a2b97d609d">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">void</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#aacaac7c100a5edfd70457b34b5f25da9">setContext</a> (SampleContextFrames Context, ContextStateMask CState=RawContext)</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#afe13f78db01d9c3d12b2cf017bd9fbeb">isPrefixOf</a> (const SampleContext &amp;That) const</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/sampleprof/functionid">FunctionId</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a0c1e27d6337471ec3055b8ab2585e9e3">Func</a></td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/namespaces/llvm/sampleprof/#a737d65abec7fd88fdb10cfcd209391c2">SampleContextFrames</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a75bd4ad742863fb4896856e15c7014a1">FullContext</a></td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">uint32_t</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#aab93e729a26ea1adc6faac9a2a7b7062">State</a></td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">uint32_t</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ad46076356ba127a620aba358eccb7924">Attributes</a></td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">static void</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a03a9d7487e3a99b134abd6aa5bf2a101">createCtxVectorFromStr</a> (StringRef ContextStr, SampleContextFrameVector &amp;Context)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Create a context vector from a given context string and save it in <span class="doxyComputerOutput">Context</span>. <a href="#a03a9d7487e3a99b134abd6aa5bf2a101">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">static void</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a8405818cd197f55e233406e23f59c76e">decodeContextString</a> (StringRef ContextStr, FunctionId &amp;Func, LineLocation &amp;LineLoc)</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">static std::string</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a9103cd6ba6a3cc429e059e53ac9212b8">getContextString</a> (SampleContextFrames Context, bool IncludeLeafLineLocation=false)</td>
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


<p>Definition at line 523 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/profiledata/sampleprof-h">SampleProf.h</a>.</p>


<div class="doxySectionDef">

## Public Constructors

### SampleContext() {#ab8ff16dff4a4304435e512fa6bd1066b}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">llvm::sampleprof::SampleContext::SampleContext ()</td>
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



<p>Definition at line 525 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/profiledata/sampleprof-h">SampleProf.h</a>.</p>


<p>References <a href="/web-llvm/docs/api/namespaces/llvm/sampleprof/#a9c9cec0dc85381494fb418ae0e88a40fa228db178ac635da0209a2dd10cc8cf2e">llvm::sampleprof::ContextNone</a> and <a href="/web-llvm/docs/api/namespaces/llvm/sampleprof/#a6cff5a57b476680e6b28e4dbfd2da8aca39453cb1787cb996f3d47545939ef478">llvm::sampleprof::UnknownContext</a>.</p>


<p>Referenced by <a href="#afe13f78db01d9c3d12b2cf017bd9fbeb">isPrefixOf</a>, <a href="#a95bab793c63f62320667fbf0a17c288a">operator!=</a>, <a href="/web-llvm/docs/api/structs/llvm/sampleprof/samplecontext/hash/#a09f9002b9498a9daf39d24257e8a4a02">llvm::sampleprof::SampleContext::Hash::operator()</a>, <a href="#a2f34643744ac2bf92d700a8461d9aeb0">operator&lt;</a> and <a href="#a0aa116c8c84f49cc5770fcafc4057c7a">operator==</a>.</p>

</div>
</div>

### SampleContext() {#af72a0c462f5d90d3d6c48e6ceaff38a3}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">llvm::sampleprof::SampleContext::SampleContext (<a href="/web-llvm/docs/api/classes/llvm/stringref">StringRef</a> Name)</td>
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



<p>Definition at line 527 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/profiledata/sampleprof-h">SampleProf.h</a>.</p>


<p>References <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/silowercontrolflow-cpp/#a4868c5d81c5ccc98c47aeab6244346a0">assert</a>, <a href="/web-llvm/docs/api/namespaces/llvm/sampleprof/#a9c9cec0dc85381494fb418ae0e88a40fa228db178ac635da0209a2dd10cc8cf2e">llvm::sampleprof::ContextNone</a> and <a href="/web-llvm/docs/api/namespaces/llvm/sampleprof/#a6cff5a57b476680e6b28e4dbfd2da8aca39453cb1787cb996f3d47545939ef478">llvm::sampleprof::UnknownContext</a>.</p>

</div>
</div>

### SampleContext() {#a6cec6667c5b4468d44bbedcff1f29e8c}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">llvm::sampleprof::SampleContext::SampleContext (<a href="/web-llvm/docs/api/classes/llvm/sampleprof/functionid">FunctionId</a> Func)</td>
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



<p>Definition at line 532 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/profiledata/sampleprof-h">SampleProf.h</a>.</p>


<p>References <a href="/web-llvm/docs/api/namespaces/llvm/sampleprof/#a9c9cec0dc85381494fb418ae0e88a40fa228db178ac635da0209a2dd10cc8cf2e">llvm::sampleprof::ContextNone</a> and <a href="/web-llvm/docs/api/namespaces/llvm/sampleprof/#a6cff5a57b476680e6b28e4dbfd2da8aca39453cb1787cb996f3d47545939ef478">llvm::sampleprof::UnknownContext</a>.</p>

</div>
</div>

### SampleContext() {#a1623f5e961234d9e5953084f28892a1c}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">llvm::sampleprof::SampleContext::SampleContext (<a href="/web-llvm/docs/api/namespaces/llvm/sampleprof/#a737d65abec7fd88fdb10cfcd209391c2">SampleContextFrames</a> Context, <a href="/web-llvm/docs/api/namespaces/llvm/sampleprof/#a6cff5a57b476680e6b28e4dbfd2da8ac">ContextStateMask</a> CState=<a href="/web-llvm/docs/api/namespaces/llvm/sampleprof/#a6cff5a57b476680e6b28e4dbfd2da8aca33510720a1514b03ccfd70b909722ec6">RawContext</a>)</td>
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



<p>Definition at line 535 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/profiledata/sampleprof-h">SampleProf.h</a>.</p>


<p>References <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/silowercontrolflow-cpp/#a4868c5d81c5ccc98c47aeab6244346a0">assert</a>, <a href="/web-llvm/docs/api/namespaces/llvm/sampleprof/#a9c9cec0dc85381494fb418ae0e88a40fa228db178ac635da0209a2dd10cc8cf2e">llvm::sampleprof::ContextNone</a>, <a href="/web-llvm/docs/api/namespaces/llvm/sampleprof/#a6cff5a57b476680e6b28e4dbfd2da8aca33510720a1514b03ccfd70b909722ec6">llvm::sampleprof::RawContext</a> and <a href="#aacaac7c100a5edfd70457b34b5f25da9">setContext</a>.</p>

</div>
</div>

### SampleContext() {#a3093181fe818bf3fe03f72887de8943f}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">llvm::sampleprof::SampleContext::SampleContext (<a href="/web-llvm/docs/api/classes/llvm/stringref">StringRef</a> ContextStr, std::list&lt; <a href="/web-llvm/docs/api/namespaces/llvm/sampleprof/#abc45b32c93302a515b730f86807dd80c">SampleContextFrameVector</a> &gt; &amp; CSNameTable, <a href="/web-llvm/docs/api/namespaces/llvm/sampleprof/#a6cff5a57b476680e6b28e4dbfd2da8ac">ContextStateMask</a> CState=<a href="/web-llvm/docs/api/namespaces/llvm/sampleprof/#a6cff5a57b476680e6b28e4dbfd2da8aca33510720a1514b03ccfd70b909722ec6">RawContext</a>)</td>
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



<p>Definition at line 545 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/profiledata/sampleprof-h">SampleProf.h</a>.</p>


<p>References <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/silowercontrolflow-cpp/#a4868c5d81c5ccc98c47aeab6244346a0">assert</a>, <a href="/web-llvm/docs/api/namespaces/llvm/sampleprof/#a9c9cec0dc85381494fb418ae0e88a40fa228db178ac635da0209a2dd10cc8cf2e">llvm::sampleprof::ContextNone</a>, <a href="#a03a9d7487e3a99b134abd6aa5bf2a101">createCtxVectorFromStr</a>, <a href="/web-llvm/docs/api/classes/llvm/stringref/#a2dc80c585ad5882da8cae7b5968f7e74">llvm::StringRef::empty</a>, <a href="/web-llvm/docs/api/namespaces/llvm/sampleprof/#a6cff5a57b476680e6b28e4dbfd2da8aca33510720a1514b03ccfd70b909722ec6">llvm::sampleprof::RawContext</a>, <a href="#aacaac7c100a5edfd70457b34b5f25da9">setContext</a>, <a href="/web-llvm/docs/api/classes/llvm/stringref/#a2cd8968ff703aaeb395dcd63f6805ff1">llvm::StringRef::starts_with</a> and <a href="/web-llvm/docs/api/namespaces/llvm/sampleprof/#a6cff5a57b476680e6b28e4dbfd2da8aca39453cb1787cb996f3d47545939ef478">llvm::sampleprof::UnknownContext</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Public Operators

### operator SampleContextFrames() {#ab5924f265dd624f920db021b65ddfba4}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">llvm::sampleprof::SampleContext::operator SampleContextFrames ()</td>
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



<p>Definition at line 607 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/profiledata/sampleprof-h">SampleProf.h</a>.</p>

</div>
</div>

### operator!=() {#a95bab793c63f62320667fbf0a17c288a}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool llvm::sampleprof::SampleContext::operator!= (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/sampleprof/samplecontext">SampleContext</a> &amp; That)</td>
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



<p>Definition at line 665 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/profiledata/sampleprof-h">SampleProf.h</a>.</p>


<p>Reference <a href="#ab8ff16dff4a4304435e512fa6bd1066b">SampleContext</a>.</p>

</div>
</div>

### operator&lt;() {#a2f34643744ac2bf92d700a8461d9aeb0}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool llvm::sampleprof::SampleContext::operator&lt; (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/sampleprof/samplecontext">SampleContext</a> &amp; That)</td>
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



<p>Definition at line 667 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/profiledata/sampleprof-h">SampleProf.h</a>.</p>


<p>References <a href="#a3f47a41fc180017373f06a00976d7c5c">hasContext</a>, <a href="/web-llvm/docs/api/files/lib/lib/support/md5-cpp/#ac0eafdc9ee161b71e7af98af736952fd">I</a>, <a href="#ab8ff16dff4a4304435e512fa6bd1066b">SampleContext</a> and <a href="/web-llvm/docs/api/classes/llvm/arrayref/#a85ffb6531d4cda988ea81f18d4e56fb7">llvm::ArrayRef&lt; T &gt;::size</a>.</p>

</div>
</div>

### operator==() {#a0aa116c8c84f49cc5770fcafc4057c7a}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool llvm::sampleprof::SampleContext::operator== (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/sampleprof/samplecontext">SampleContext</a> &amp; That)</td>
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



<p>Definition at line 660 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/profiledata/sampleprof-h">SampleProf.h</a>.</p>


<p>Reference <a href="#ab8ff16dff4a4304435e512fa6bd1066b">SampleContext</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Public Member Functions

### clearState() {#a4edc88a1dca4a856f34e190c2626f3fc}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void llvm::sampleprof::SampleContext::clearState (<a href="/web-llvm/docs/api/namespaces/llvm/sampleprof/#a6cff5a57b476680e6b28e4dbfd2da8ac">ContextStateMask</a> S)</td>
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



<p>Definition at line 614 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/profiledata/sampleprof-h">SampleProf.h</a>.</p>

</div>
</div>

### getAllAttributes() {#ac14fcf43c57c449e8398370de8d9a2dc}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">uint32_t llvm::sampleprof::SampleContext::getAllAttributes ()</td>
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



<p>Definition at line 610 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/profiledata/sampleprof-h">SampleProf.h</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/classes/llvm/sampleprof/sampleprofilewriterextbinarybase/#a96315b9b9bda521e4026e537c7d9f139">llvm::sampleprof::SampleProfileWriterExtBinaryBase::writeFuncMetadata</a> and <a href="/web-llvm/docs/api/classes/llvm/sampleprof/sampleprofilewritertext/#acdb8f85283e93399278cbe5363f944da">llvm::sampleprof::SampleProfileWriterText::writeSample</a>.</p>

</div>
</div>

### getContextFrames() {#a5f6cf6770a2b1c836c02387c1c1b1258}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">SampleContextFrames llvm::sampleprof::SampleContext::getContextFrames ()</td>
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



<p>Definition at line 618 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/profiledata/sampleprof-h">SampleProf.h</a>.</p>


<p>Referenced by <a href="#aa974f8c265b1f6334ffd5df3507371f3">getHashCode</a>.</p>

</div>
</div>

### getFunction() {#aaec6c587638c9dedc9041f186e598196}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">FunctionId llvm::sampleprof::SampleContext::getFunction ()</td>
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



<p>Definition at line 617 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/profiledata/sampleprof-h">SampleProf.h</a>.</p>


<p>Referenced by <a href="#aa974f8c265b1f6334ffd5df3507371f3">getHashCode</a> and <a href="/web-llvm/docs/api/classes/llvm/sampleprof/sampleprofilereaderextbinarybase/#a873e0df967c1a3a622ee9e25c1a6fa00">llvm::sampleprof::SampleProfileReaderExtBinaryBase::readFuncProfiles</a>.</p>

</div>
</div>

### getHashCode() {#aa974f8c265b1f6334ffd5df3507371f3}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">uint64_t llvm::sampleprof::SampleContext::getHashCode ()</td>
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



<p>Definition at line 639 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/profiledata/sampleprof-h">SampleProf.h</a>.</p>


<p>References <a href="#a5f6cf6770a2b1c836c02387c1c1b1258">getContextFrames</a>, <a href="#aaec6c587638c9dedc9041f186e598196">getFunction</a>, <a href="/web-llvm/docs/api/classes/llvm/sampleprof/functionid/#a5c097d6625bd9e8132f391309e787943">llvm::sampleprof::FunctionId::getHashCode</a>, <a href="#a3f47a41fc180017373f06a00976d7c5c">hasContext</a> and <a href="/web-llvm/docs/api/namespaces/llvm/sampleprof/#ae45c2dc36b1f12d52356dd557bcf02eb">llvm::sampleprof::hash_value</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/structs/llvm/densemapinfo-937e4af4dbf28ce627a819a588e9e3c4/#a4c3c08201ce621ec4c184866b8be938c">llvm::DenseMapInfo&lt; SampleContext &gt;::getHashValue</a> and <a href="/web-llvm/docs/api/classes/llvm/sampleprof/sampleprofilereaderextbinarybase/#a58cedb1356bab80647af0fa48bc1750a">llvm::sampleprof::SampleProfileReaderExtBinaryBase::readFuncMetadata</a>.</p>

</div>
</div>

### hasAttribute() {#acddf84ace68d71cc96ecfdf7da44da58}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool llvm::sampleprof::SampleContext::hasAttribute (<a href="/web-llvm/docs/api/namespaces/llvm/sampleprof/#a9c9cec0dc85381494fb418ae0e88a40f">ContextAttributeMask</a> A)</td>
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



<p>Definition at line 608 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/profiledata/sampleprof-h">SampleProf.h</a>.</p>


<p>Reference <a href="/web-llvm/docs/api/files/lib/lib/ir/builtingcs-cpp/#a2e38c85003a042421cde1647632d0b72">A</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/classes/anonymous-sampleprofile-cpp-/sampleprofileloader/#aa9137eda03e0c2cfd6eebaa55dfdd4cc">anonymous{SampleProfile.cpp}::SampleProfileLoader::findExternalInlineCandidate</a>.</p>

</div>
</div>

### hasContext() {#a3f47a41fc180017373f06a00976d7c5c}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool llvm::sampleprof::SampleContext::hasContext ()</td>
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



<p>Definition at line 615 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/profiledata/sampleprof-h">SampleProf.h</a>.</p>


<p>Reference <a href="/web-llvm/docs/api/namespaces/llvm/sampleprof/#a6cff5a57b476680e6b28e4dbfd2da8aca39453cb1787cb996f3d47545939ef478">llvm::sampleprof::UnknownContext</a>.</p>


<p>Referenced by <a href="#aa974f8c265b1f6334ffd5df3507371f3">getHashCode</a>, <a href="#a2f34643744ac2bf92d700a8461d9aeb0">operator&lt;</a>, <a href="/web-llvm/docs/api/classes/llvm/sampleprof/sampleprofilereadertext/#aa8f17958c50ff564f5817c64850da276">llvm::sampleprof::SampleProfileReaderText::readImpl</a> and <a href="#ade2e9346cc9a993d02dab4742aff2bdf">toString</a>.</p>

</div>
</div>

### hasState() {#a3f30fb3b02e2a17d75e3caf5af38eaed}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool llvm::sampleprof::SampleContext::hasState (<a href="/web-llvm/docs/api/namespaces/llvm/sampleprof/#a6cff5a57b476680e6b28e4dbfd2da8ac">ContextStateMask</a> S)</td>
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



<p>Definition at line 612 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/profiledata/sampleprof-h">SampleProf.h</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/classes/llvm/samplecontexttracker/#a03cbc7841d2552fcd7639666975fa13c">llvm::SampleContextTracker::promoteMergeContextSamplesTree</a>.</p>

</div>
</div>

### isBaseContext() {#a742d15f1afc6f1accfa9694e3668ebac}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool llvm::sampleprof::SampleContext::isBaseContext ()</td>
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



<p>Definition at line 616 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/profiledata/sampleprof-h">SampleProf.h</a>.</p>

</div>
</div>

### isPrefixOf() {#afe13f78db01d9c3d12b2cf017bd9fbeb}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool llvm::sampleprof::SampleContext::isPrefixOf (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/sampleprof/samplecontext">SampleContext</a> &amp; That)</td>
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



<p>Definition at line 696 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/profiledata/sampleprof-h">SampleProf.h</a>.</p>


<p>References <a href="/web-llvm/docs/api/classes/llvm/arrayref/#aa713e2599e000adc01ced998c05502a7">llvm::ArrayRef&lt; T &gt;::drop_back</a>, <a href="#ab8ff16dff4a4304435e512fa6bd1066b">SampleContext</a> and <a href="/web-llvm/docs/api/classes/llvm/arrayref/#a33da2ddf6f447892591c86d9d3771b9c">llvm::ArrayRef&lt; T &gt;::take_front</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/classes/llvm/sampleprof/sampleprofilereaderextbinarybase/#a873e0df967c1a3a622ee9e25c1a6fa00">llvm::sampleprof::SampleProfileReaderExtBinaryBase::readFuncProfiles</a>.</p>

</div>
</div>

### setAllAttributes() {#aa7894022c49174ef967469c3ddd81857}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void llvm::sampleprof::SampleContext::setAllAttributes (uint32_t A)</td>
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



<p>Definition at line 611 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/profiledata/sampleprof-h">SampleProf.h</a>.</p>


<p>Reference <a href="/web-llvm/docs/api/files/lib/lib/ir/builtingcs-cpp/#a2e38c85003a042421cde1647632d0b72">A</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/classes/llvm/sampleprof/sampleprofilereaderextbinarybase/#a9b9e845ee3096f8360407bfa4f0f3d1a">llvm::sampleprof::SampleProfileReaderExtBinaryBase::readFuncMetadata</a> and <a href="/web-llvm/docs/api/classes/llvm/sampleprof/sampleprofilereadertext/#aa8f17958c50ff564f5817c64850da276">llvm::sampleprof::SampleProfileReaderText::readImpl</a>.</p>

</div>
</div>

### setAttribute() {#ac1a2adf3cf418221c93db5b17a760a5d}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void llvm::sampleprof::SampleContext::setAttribute (<a href="/web-llvm/docs/api/namespaces/llvm/sampleprof/#a9c9cec0dc85381494fb418ae0e88a40f">ContextAttributeMask</a> A)</td>
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



<p>Definition at line 609 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/profiledata/sampleprof-h">SampleProf.h</a>.</p>


<p>Reference <a href="/web-llvm/docs/api/files/lib/lib/ir/builtingcs-cpp/#a2e38c85003a042421cde1647632d0b72">A</a>.</p>

</div>
</div>

### setContext() {#aacaac7c100a5edfd70457b34b5f25da9}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void llvm::sampleprof::SampleContext::setContext (<a href="/web-llvm/docs/api/namespaces/llvm/sampleprof/#a737d65abec7fd88fdb10cfcd209391c2">SampleContextFrames</a> Context, <a href="/web-llvm/docs/api/namespaces/llvm/sampleprof/#a6cff5a57b476680e6b28e4dbfd2da8ac">ContextStateMask</a> CState=<a href="/web-llvm/docs/api/namespaces/llvm/sampleprof/#a6cff5a57b476680e6b28e4dbfd2da8aca33510720a1514b03ccfd70b909722ec6">RawContext</a>)</td>
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



<p>Definition at line 652 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/profiledata/sampleprof-h">SampleProf.h</a>.</p>


<p>References <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/silowercontrolflow-cpp/#a4868c5d81c5ccc98c47aeab6244346a0">assert</a>, <a href="/web-llvm/docs/api/namespaces/llvm/sampleprof/#a6cff5a57b476680e6b28e4dbfd2da8aca33510720a1514b03ccfd70b909722ec6">llvm::sampleprof::RawContext</a> and <a href="/web-llvm/docs/api/namespaces/llvm/sampleprof/#a6cff5a57b476680e6b28e4dbfd2da8aca39453cb1787cb996f3d47545939ef478">llvm::sampleprof::UnknownContext</a>.</p>


<p>Referenced by <a href="#a1623f5e961234d9e5953084f28892a1c">SampleContext</a> and <a href="#a3093181fe818bf3fe03f72887de8943f">SampleContext</a>.</p>

</div>
</div>

### setFunction() {#a0fa76143f44e4ba94a2d71a2b97d609d}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void llvm::sampleprof::SampleContext::setFunction (<a href="/web-llvm/docs/api/classes/llvm/sampleprof/functionid">FunctionId</a> NewFunctionID)</td>
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

<p>Set the name of the function and clear the current context.</p>

<p>Definition at line 646 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/profiledata/sampleprof-h">SampleProf.h</a>.</p>


<p>Reference <a href="/web-llvm/docs/api/namespaces/llvm/sampleprof/#a6cff5a57b476680e6b28e4dbfd2da8aca39453cb1787cb996f3d47545939ef478">llvm::sampleprof::UnknownContext</a>.</p>

</div>
</div>

### setState() {#aa41059d227a82a3a80090c944aa80c5b}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void llvm::sampleprof::SampleContext::setState (<a href="/web-llvm/docs/api/namespaces/llvm/sampleprof/#a6cff5a57b476680e6b28e4dbfd2da8ac">ContextStateMask</a> S)</td>
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



<p>Definition at line 613 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/profiledata/sampleprof-h">SampleProf.h</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/classes/llvm/samplecontexttracker/#a75bd919afb45ef334b6e8fa723d4beb5">llvm::SampleContextTracker::getContextSamplesFor</a>, <a href="/web-llvm/docs/api/classes/llvm/samplecontexttracker/#aa144b495aee60da309a023d554952ac9">llvm::SampleContextTracker::markContextSamplesInlined</a> and <a href="/web-llvm/docs/api/classes/llvm/samplecontexttracker/#a3f0ac0cd0b840c490d896fd333c79c51">llvm::SampleContextTracker::populateFuncToCtxtMap</a>.</p>

</div>
</div>

### toString() {#ade2e9346cc9a993d02dab4742aff2bdf}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">std::string llvm::sampleprof::SampleContext::toString ()</td>
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



<p>Definition at line 633 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/profiledata/sampleprof-h">SampleProf.h</a>.</p>


<p>References <a href="#a9103cd6ba6a3cc429e059e53ac9212b8">getContextString</a> and <a href="#a3f47a41fc180017373f06a00976d7c5c">hasContext</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/classes/llvm/sampleprof/sampleprofilewritertext/#acdb8f85283e93399278cbe5363f944da">llvm::sampleprof::SampleProfileWriterText::writeSample</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Private Member Attributes

### Attributes {#ad46076356ba127a620aba358eccb7924}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">uint32_t llvm::sampleprof::SampleContext::Attributes</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 718 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/profiledata/sampleprof-h">SampleProf.h</a>.</p>

</div>
</div>

### FullContext {#a75bd4ad742863fb4896856e15c7014a1}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">SampleContextFrames llvm::sampleprof::SampleContext::FullContext</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 714 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/profiledata/sampleprof-h">SampleProf.h</a>.</p>

</div>
</div>

### Func {#a0c1e27d6337471ec3055b8ab2585e9e3}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">FunctionId llvm::sampleprof::SampleContext::Func</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 712 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/profiledata/sampleprof-h">SampleProf.h</a>.</p>

</div>
</div>

### State {#aab93e729a26ea1adc6faac9a2a7b7062}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">uint32_t llvm::sampleprof::SampleContext::State</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 716 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/profiledata/sampleprof-h">SampleProf.h</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Public Static Functions

### createCtxVectorFromStr() {#a03a9d7487e3a99b134abd6aa5bf2a101}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void llvm::sampleprof::SampleContext::createCtxVectorFromStr (<a href="/web-llvm/docs/api/classes/llvm/stringref">StringRef</a> ContextStr, <a href="/web-llvm/docs/api/namespaces/llvm/sampleprof/#abc45b32c93302a515b730f86807dd80c">SampleContextFrameVector</a> &amp; Context)</td>
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

<p>Create a context vector from a given context string and save it in <span class="doxyComputerOutput">Context</span>.</p>

<p>Definition at line 566 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/profiledata/sampleprof-h">SampleProf.h</a>.</p>


<p>References <a href="#a8405818cd197f55e233406e23f59c76e">decodeContextString</a>, <a href="/web-llvm/docs/api/classes/llvm/stringref/#a2dc80c585ad5882da8cae7b5968f7e74">llvm::StringRef::empty</a>, <a href="/web-llvm/docs/api/classes/llvm/stringref/#a5db9240c74644c67759dd0f901fc3c7d">llvm::StringRef::size</a>, <a href="/web-llvm/docs/api/classes/llvm/stringref/#a0320b2a5a6d440bf4479a02e78cf5ca7">llvm::StringRef::split</a> and <a href="/web-llvm/docs/api/classes/llvm/stringref/#a25f1fd81f2132805676c82ab8ae0c109">llvm::StringRef::substr</a>.</p>


<p>Referenced by <a href="#a3093181fe818bf3fe03f72887de8943f">SampleContext</a>.</p>

</div>
</div>

### decodeContextString() {#a8405818cd197f55e233406e23f59c76e}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void llvm::sampleprof::SampleContext::decodeContextString (<a href="/web-llvm/docs/api/classes/llvm/stringref">StringRef</a> ContextStr, <a href="/web-llvm/docs/api/classes/llvm/sampleprof/functionid">FunctionId</a> &amp; Func, <a href="/web-llvm/docs/api/structs/llvm/sampleprof/linelocation">LineLocation</a> &amp; LineLoc)</td>
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



<p>Definition at line 585 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/profiledata/sampleprof-h">SampleProf.h</a>.</p>


<p>References <a href="/web-llvm/docs/api/structs/llvm/sampleprof/linelocation/#ac8129e173d0cdcdd59271bf89f32544c">llvm::sampleprof::LineLocation::Discriminator</a>, <a href="/web-llvm/docs/api/structs/llvm/sampleprof/linelocation/#ac38b029469edc31486c5ce8adf89e5f3">llvm::sampleprof::LineLocation::LineOffset</a> and <a href="/web-llvm/docs/api/classes/llvm/stringref/#a0320b2a5a6d440bf4479a02e78cf5ca7">llvm::StringRef::split</a>.</p>


<p>Referenced by <a href="#a03a9d7487e3a99b134abd6aa5bf2a101">createCtxVectorFromStr</a>.</p>

</div>
</div>

### getContextString() {#a9103cd6ba6a3cc429e059e53ac9212b8}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">std::string llvm::sampleprof::SampleContext::getContextString (<a href="/web-llvm/docs/api/namespaces/llvm/sampleprof/#a737d65abec7fd88fdb10cfcd209391c2">SampleContextFrames</a> Context, bool IncludeLeafLineLocation=false)</td>
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



<p>Definition at line 620 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/profiledata/sampleprof-h">SampleProf.h</a>.</p>


<p>Reference <a href="/web-llvm/docs/api/files/lib/lib/support/md5-cpp/#ac0eafdc9ee161b71e7af98af736952fd">I</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/classes/llvm/samplecontexttracker/#aa12ce67d21274bae7db762b1e5728bf6">llvm::SampleContextTracker::getContextString</a> and <a href="#ade2e9346cc9a993d02dab4742aff2bdf">toString</a>.</p>

</div>
</div>

</div>

<hr/>

The documentation for this class was generated from the following file:

<ul>
<li><a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/profiledata/sampleprof-h">SampleProf.h</a></li>
</ul>

<hr/>

<p class="doxyGeneratedBy">Generated via <a href="https://github.com/xpack/doxygen2docusaurus">doxygen2docusaurus</a> by <a href="https://www.doxygen.nl">Doxygen</a> 1.15.0.</p>

</div>
