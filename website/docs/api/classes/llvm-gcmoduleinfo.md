---

# DO NOT EDIT!
# Automatically generated via doxygen2docusaurus by Doxygen.

slug: /api/classes/llvm/gcmoduleinfo
custom_edit_url: null
toc_max_heading_level: 4
keywords:
  - doxygen
  - reference
  - class

---

<div class="doxyPage">

# The `GCModuleInfo` Class Reference

<p>An analysis pass which caches information about the entire <a href="/web-llvm/docs/api/classes/llvm/module">Module</a>. <a href="#details">More...</a></p>

## Declaration

<div class="doxyDeclaration">
class llvm::GCModuleInfo { ... }
</div>

## Included Headers

<div class="doxyIncludesList">#include "<a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/codegen/gcmetadata-h">llvm/CodeGen/GCMetadata.h</a>"
</div>

## Base class

<table class="doxyMembersIndex">

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">class</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/immutablepass">ImmutablePass</a></td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p><a href="/web-llvm/docs/api/classes/llvm/immutablepass">ImmutablePass</a> class - This class is used to provide information that does not need to be run. <a href="/web-llvm/docs/api/classes/llvm/immutablepass/#details">More...</a></p>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a20eb7a9dc2fc52ecb5977580f2217e71">FuncInfoVec</a> = std::vector&lt; std::unique_ptr&lt; <a href="/web-llvm/docs/api/classes/llvm/gcfunctioninfo">GCFunctionInfo</a> &gt; &gt;</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>List of per function info objects. <a href="#a20eb7a9dc2fc52ecb5977580f2217e71">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">using</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a3fd8184a3ebda29e3ea2a05f899bf0f6">iterator</a> = <a href="/web-llvm/docs/api/classes/llvm/smallvector">SmallVector</a>&lt; std::unique_ptr&lt; <a href="/web-llvm/docs/api/classes/llvm/gcstrategy">GCStrategy</a> &gt;, 1 &gt;::const_iterator</td>
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

## Private Member Typedefs Index

<table class="doxyMembersIndex">

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">using</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#adcbe4fe1685e3d26e2509cf75c0a959f">finfo_map_type</a> = <a href="/web-llvm/docs/api/classes/llvm/densemap">DenseMap</a>&lt; <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/function">Function</a> *, <a href="/web-llvm/docs/api/classes/llvm/gcfunctioninfo">GCFunctionInfo</a> * &gt;</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Non-owning map to bypass linear search when finding the <a href="/web-llvm/docs/api/classes/llvm/gcfunctioninfo">GCFunctionInfo</a> associated with a particular <a href="/web-llvm/docs/api/classes/llvm/function">Function</a>. <a href="#adcbe4fe1685e3d26e2509cf75c0a959f">More...</a></p>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#aef9a20d9d1ca159dbb4419dc2b964e0d">GCModuleInfo</a> ()</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/gcstrategy">GCStrategy</a> *</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#abcc9f954d1d685f041f63c4abb1cf574">getGCStrategy</a> (const StringRef Name)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Lookup the <a href="/web-llvm/docs/api/classes/llvm/gcstrategy">GCStrategy</a> object associated with the given gc name. <a href="#abcc9f954d1d685f041f63c4abb1cf574">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">FuncInfoVec::iterator</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a2f0d3ee6539bb5dc9f1f78c6ba9fadd8">funcinfo_begin</a> ()</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">FuncInfoVec::iterator</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a2ee5e052ace1f6c85cdbcc970a705323">funcinfo_end</a> ()</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a9f011533f40036b03346c18dab170d7e">clear</a> ()</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>clear - Resets the pass. <a href="#a9f011533f40036b03346c18dab170d7e">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="#a3fd8184a3ebda29e3ea2a05f899bf0f6">iterator</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a511214c4efcdc90e46ea95d5e93ed030">begin</a> () const</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>begin/end - Iterators for used strategies. <a href="#a511214c4efcdc90e46ea95d5e93ed030">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="#a3fd8184a3ebda29e3ea2a05f899bf0f6">iterator</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a5b9417560fc962a44b73ebabce07ceaf">end</a> () const</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/gcfunctioninfo">GCFunctionInfo</a> &amp;</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a358e88db4412de1a07bf6714c545ce06">getFunctionInfo</a> (const Function &amp;F)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>get - Look up function metadata. <a href="#a358e88db4412de1a07bf6714c545ce06">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

</table>

## Private Member Attributes Index

<table class="doxyMembersIndex">

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/smallvector">SmallVector</a>&lt; std::unique_ptr&lt; <a href="/web-llvm/docs/api/classes/llvm/gcstrategy">GCStrategy</a> &gt;, 1 &gt;</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a70dfb3621a05ab86152bfee5ea76b859">GCStrategyList</a></td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>An owning list of all GCStrategies which have been created. <a href="#a70dfb3621a05ab86152bfee5ea76b859">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/stringmap">StringMap</a>&lt; <a href="/web-llvm/docs/api/classes/llvm/gcstrategy">GCStrategy</a> * &gt;</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ad605beeb53e37c754afaed2e6cce3378">GCStrategyMap</a></td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>A helper map to speedup lookups into the above list. <a href="#ad605beeb53e37c754afaed2e6cce3378">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="#a20eb7a9dc2fc52ecb5977580f2217e71">FuncInfoVec</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a6014814de73e8bb32641740a5a71ef87">Functions</a></td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Owning list of all GCFunctionInfos associated with this <a href="/web-llvm/docs/api/classes/llvm/module">Module</a>. <a href="#a6014814de73e8bb32641740a5a71ef87">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/densemap">finfo_map_type</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a08b190e179a6ad4ea7d26d7f20e64ec1">FInfoMap</a></td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a7ede183e80b15de0ddc61e80892fd0ca">ID</a> = 0</td>
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

<p>An analysis pass which caches information about the entire <a href="/web-llvm/docs/api/classes/llvm/module">Module</a>.</p>


<p>Records both the function level information used by GCRoots and a cache of the 'active' gc strategy objects for the current <a href="/web-llvm/docs/api/classes/llvm/module">Module</a>.</p>


<p>Definition at line 203 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/codegen/gcmetadata-h">GCMetadata.h</a>.</p>


<div class="doxySectionDef">

## Public Member Typedefs

### FuncInfoVec {#a20eb7a9dc2fc52ecb5977580f2217e71}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">using llvm::GCModuleInfo::FuncInfoVec =  std::vector&lt;std::unique_ptr&lt;GCFunctionInfo&gt;&gt;</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>List of per function info objects.</p>


<p>In theory, Each of these may be associated with a different GC.</p>


<p>Definition at line 217 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/codegen/gcmetadata-h">GCMetadata.h</a>.</p>

</div>
</div>

### iterator {#a3fd8184a3ebda29e3ea2a05f899bf0f6}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">using llvm::GCModuleInfo::iterator =  SmallVector&lt;std::unique_ptr&lt;GCStrategy&gt;, 1&gt;::const_iterator</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 232 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/codegen/gcmetadata-h">GCMetadata.h</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Private Member Typedefs

### finfo\_map\_type {#adcbe4fe1685e3d26e2509cf75c0a959f}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">using llvm::GCModuleInfo::finfo_map_type =  DenseMap&lt;const Function *, GCFunctionInfo *&gt;</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Non-owning map to bypass linear search when finding the <a href="/web-llvm/docs/api/classes/llvm/gcfunctioninfo">GCFunctionInfo</a> associated with a particular <a href="/web-llvm/docs/api/classes/llvm/function">Function</a>.</p>

<p>Definition at line 228 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/codegen/gcmetadata-h">GCMetadata.h</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Public Constructors

### GCModuleInfo() {#aef9a20d9d1ca159dbb4419dc2b964e0d}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">GCModuleInfo::GCModuleInfo ()</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Declaration at line 236 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/codegen/gcmetadata-h">GCMetadata.h</a>, definition at line 88 of file <a href="/web-llvm/docs/api/files/lib/lib/codegen/gcmetadata-cpp">GCMetadata.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/classes/llvm/passregistry/#a05a729900b76c89e808c6c3094921b2f">llvm::PassRegistry::getPassRegistry</a>, <a href="#a7ede183e80b15de0ddc61e80892fd0ca">ID</a>, <a href="/web-llvm/docs/api/classes/llvm/immutablepass/#a4d664099280bb09275254d64c329d25d">llvm::ImmutablePass::ImmutablePass</a> and <a href="/web-llvm/docs/api/namespaces/llvm/#a7c3c64daeddcc57785e85d30f13b1e55">llvm::initializeGCModuleInfoPass</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Public Member Functions

### begin() {#a511214c4efcdc90e46ea95d5e93ed030}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">iterator llvm::GCModuleInfo::begin ()</td>
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

<p>begin/end - Iterators for used strategies.</p>

<p>Definition at line 245 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/codegen/gcmetadata-h">GCMetadata.h</a>.</p>

</div>
</div>

### clear() {#a9f011533f40036b03346c18dab170d7e}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void GCModuleInfo::clear ()</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>clear - Resets the pass.</p>


<p><a href="/web-llvm/docs/api/classes/llvm/any">Any</a> pass, which uses <a href="/web-llvm/docs/api/classes/llvm/gcmoduleinfo">GCModuleInfo</a>, should call it in <a href="/web-llvm/docs/api/classes/llvm/pass/#ac7811985250c75d7e2a244292d615fff">doFinalization()</a>.</p>


<p>Declaration at line 241 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/codegen/gcmetadata-h">GCMetadata.h</a>, definition at line 107 of file <a href="/web-llvm/docs/api/files/lib/lib/codegen/gcmetadata-cpp">GCMetadata.cpp</a>.</p>

</div>
</div>

### end() {#a5b9417560fc962a44b73ebabce07ceaf}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">iterator llvm::GCModuleInfo::end ()</td>
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



<p>Definition at line 246 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/codegen/gcmetadata-h">GCMetadata.h</a>.</p>

</div>
</div>

### funcinfo\_begin() {#a2f0d3ee6539bb5dc9f1f78c6ba9fadd8}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">FuncInfoVec::iterator llvm::GCModuleInfo::funcinfo_begin ()</td>
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



<p>Definition at line 219 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/codegen/gcmetadata-h">GCMetadata.h</a>.</p>

</div>
</div>

### funcinfo\_end() {#a2ee5e052ace1f6c85cdbcc970a705323}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">FuncInfoVec::iterator llvm::GCModuleInfo::funcinfo_end ()</td>
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



<p>Definition at line 220 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/codegen/gcmetadata-h">GCMetadata.h</a>.</p>

</div>
</div>

### getFunctionInfo() {#a358e88db4412de1a07bf6714c545ce06}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">GCFunctionInfo &amp; GCModuleInfo::getFunctionInfo (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/function">Function</a> &amp; F)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>get - Look up function metadata.</p>


<p>This is currently assumed have the side effect of initializing the associated <a href="/web-llvm/docs/api/classes/llvm/gcstrategy">GCStrategy</a>. That will soon change.</p>


<p>Declaration at line 251 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/codegen/gcmetadata-h">GCMetadata.h</a>, definition at line 92 of file <a href="/web-llvm/docs/api/files/lib/lib/codegen/gcmetadata-cpp">GCMetadata.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/silowercontrolflow-cpp/#a4868c5d81c5ccc98c47aeab6244346a0">assert</a>, <a href="/web-llvm/docs/api/files/lib/lib/support/md5-cpp/#a96d73bbd7af15cb1fc38c3f4a3bd82e9">F</a>, <a href="#abcc9f954d1d685f041f63c4abb1cf574">getGCStrategy</a> and <a href="/web-llvm/docs/api/files/lib/lib/support/md5-cpp/#ac0eafdc9ee161b71e7af98af736952fd">I</a>.</p>

</div>
</div>

### getGCStrategy() {#abcc9f954d1d685f041f63c4abb1cf574}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">GCStrategy * GCModuleInfo::getGCStrategy (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/stringref">StringRef</a> Name)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Lookup the <a href="/web-llvm/docs/api/classes/llvm/gcstrategy">GCStrategy</a> object associated with the given gc name.</p>


<p>Objects are owned internally; No caller should attempt to delete the returned objects.</p>


<p>Declaration at line 213 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/codegen/gcmetadata-h">GCMetadata.h</a>, definition at line 115 of file <a href="/web-llvm/docs/api/files/lib/lib/codegen/gcmetadata-cpp">GCMetadata.cpp</a>.</p>


<p>Reference <a href="/web-llvm/docs/api/namespaces/llvm/#ac94cf747f5fb3d8bef69ba5168873f55">llvm::getGCStrategy</a>.</p>


<p>Referenced by <a href="#a358e88db4412de1a07bf6714c545ce06">getFunctionInfo</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Private Member Attributes

### FInfoMap {#a08b190e179a6ad4ea7d26d7f20e64ec1}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">finfo_map_type llvm::GCModuleInfo::FInfoMap</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 229 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/codegen/gcmetadata-h">GCMetadata.h</a>.</p>

</div>
</div>

### Functions {#a6014814de73e8bb32641740a5a71ef87}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">FuncInfoVec llvm::GCModuleInfo::Functions</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Owning list of all GCFunctionInfos associated with this <a href="/web-llvm/docs/api/classes/llvm/module">Module</a>.</p>

<p>Definition at line 224 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/codegen/gcmetadata-h">GCMetadata.h</a>.</p>

</div>
</div>

### GCStrategyList {#a70dfb3621a05ab86152bfee5ea76b859}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">SmallVector&lt;std::unique_ptr&lt;GCStrategy&gt;, 1&gt; llvm::GCModuleInfo::GCStrategyList</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>An owning list of all GCStrategies which have been created.</p>

<p>Definition at line 205 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/codegen/gcmetadata-h">GCMetadata.h</a>.</p>

</div>
</div>

### GCStrategyMap {#ad605beeb53e37c754afaed2e6cce3378}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">StringMap&lt;GCStrategy*&gt; llvm::GCModuleInfo::GCStrategyMap</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>A helper map to speedup lookups into the above list.</p>

<p>Definition at line 207 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/codegen/gcmetadata-h">GCMetadata.h</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Public Static Attributes

### ID {#a7ede183e80b15de0ddc61e80892fd0ca}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">char GCModuleInfo::ID = 0</td>
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



<p>Definition at line 234 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/codegen/gcmetadata-h">GCMetadata.h</a>.</p>


<p>Referenced by <a href="#aef9a20d9d1ca159dbb4419dc2b964e0d">GCModuleInfo</a>.</p>

</div>
</div>

</div>

<hr/>

The documentation for this class was generated from the following files:

<ul>
<li><a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/codegen/gcmetadata-h">GCMetadata.h</a></li>
<li><a href="/web-llvm/docs/api/files/lib/lib/codegen/gcmetadata-cpp">GCMetadata.cpp</a></li>
</ul>

<hr/>

<p class="doxyGeneratedBy">Generated via <a href="https://github.com/xpack/doxygen2docusaurus">doxygen2docusaurus</a> by <a href="https://www.doxygen.nl">Doxygen</a> 1.15.0.</p>

</div>
