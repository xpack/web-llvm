---

# DO NOT EDIT!
# Automatically generated via doxygen2docusaurus by Doxygen.

slug: /api/classes/llvm/valuemapper
custom_edit_url: null
toc_max_heading_level: 4
keywords:
  - doxygen
  - reference
  - class

---

<div class="doxyPage">

# The `ValueMapper` Class Reference

<p>Context for (re-)mapping values (and metadata). <a href="#details">More...</a></p>

## Declaration

<div class="doxyDeclaration">
class llvm::ValueMapper { ... }
</div>

## Included Headers

<div class="doxyIncludesList">#include "<a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/transforms/include/llvm/transforms/utils/valuemapper-h">llvm/Transforms/Utils/ValueMapper.h</a>"
</div>

## Public Constructors Index

<table class="doxyMembersIndex">

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ad0c8b397f8b38de86898f8ad1a2f7ca5">ValueMapper</a> (ValueToValueMapTy &amp;VM, RemapFlags Flags=RF_None, ValueMapTypeRemapper *TypeMapper=nullptr, ValueMaterializer *Materializer=nullptr, const MetadataSetTy *IdentityMD=nullptr)</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a5426f4a7848eb0f1d32cde68b6a1e859">ValueMapper</a> (ValueMapper &amp;&amp;)=delete</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ab5b058f81f944fe9f6511cba20f05a16">ValueMapper</a> (const ValueMapper &amp;)=delete</td>
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

## Public Destructor Index

<table class="doxyMembersIndex">

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a069d03c6a59e7842f4989ad2cbdf784b">~ValueMapper</a> ()</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/valuemapper">ValueMapper</a> &amp;</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#abe4e609531e4bfd5beb3a32fe65a0718">operator=</a> (ValueMapper &amp;&amp;)=delete</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/valuemapper">ValueMapper</a> &amp;</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a4e6ce25d919abcceeeefa6773954847b">operator=</a> (const ValueMapper &amp;)=delete</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">unsigned</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a995e15c9fb470ea7ad0ad64a2107cb2d">registerAlternateMappingContext</a> (ValueToValueMapTy &amp;VM, ValueMaterializer *Materializer=nullptr)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p><a href="/web-llvm/docs/api/classes/llvm/register">Register</a> an alternate mapping context. <a href="#a995e15c9fb470ea7ad0ad64a2107cb2d">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">void</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#afe293888b7729d9e4561b842029a81d2">addFlags</a> (RemapFlags Flags)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Add to the current <em><a href="/web-llvm/docs/api/namespaces/llvm/#a77724415203930efd07d7098cb1e437d">RemapFlags</a></em>. <a href="#afe293888b7729d9e4561b842029a81d2">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/metadata">Metadata</a> *</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a34e95c851d620226f791fcbe877762cf">mapMetadata</a> (const Metadata &amp;MD)</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/mdnode">MDNode</a> *</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a33edb8d7bd7bce78ba42492330cc233a">mapMDNode</a> (const MDNode &amp;N)</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/value">Value</a> *</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ae5adbfde952beb3b67c171e6b6429764">mapValue</a> (const Value &amp;V)</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/constant">Constant</a> *</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#abe2b1256305179d082979053910d0f8d">mapConstant</a> (const Constant &amp;C)</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a52c3da2ac81996e272ec9eadbd224517">remapInstruction</a> (Instruction &amp;I)</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a06197e7841d4afc1dac5d5e812818fbf">remapDbgRecord</a> (Module *M, DbgRecord &amp;V)</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a17575c108f15c37d5475da79089be35b">remapDbgRecordRange</a> (Module *M, iterator_range&lt; DbgRecordIterator &gt; Range)</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#abc0a2be8d6101a9ed7f565409fbe4151">remapFunction</a> (Function &amp;F)</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ae3e49b91eb8536c50030213a24dea440">remapGlobalObjectMetadata</a> (GlobalObject &amp;GO)</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a7c73fec2158f89a9339a366f5827df4b">scheduleMapGlobalInitializer</a> (GlobalVariable &amp;GV, Constant &amp;Init, unsigned MappingContextID=0)</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ad87dbabd93d50b016817bf54b0345340">scheduleMapAppendingVariable</a> (GlobalVariable &amp;GV, Constant *InitPrefix, bool IsOldCtorDtor, ArrayRef&lt; Constant * &gt; NewMembers, unsigned MappingContextID=0)</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#adc967f437f5d05f0921816addf1ed9c7">scheduleMapGlobalAlias</a> (GlobalAlias &amp;GA, Constant &amp;Aliasee, unsigned MappingContextID=0)</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a8e20a241c1637ffe908adac8a5011f43">scheduleMapGlobalIFunc</a> (GlobalIFunc &amp;GI, Constant &amp;Resolver, unsigned MappingContextID=0)</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a84b3f8c68eba85bccc6d26e69679b5fe">scheduleRemapFunction</a> (Function &amp;F, unsigned MappingContextID=0)</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">void *</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#aeb9808ac3c62b8854015f6674100dc79">pImpl</a></td>
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

<p>Context for (re-)mapping values (and metadata).</p>


<p>A shared context used for mapping and remapping of <a href="/web-llvm/docs/api/classes/llvm/value">Value</a> and <a href="/web-llvm/docs/api/classes/llvm/metadata">Metadata</a> instances using <em><a href="/web-llvm/docs/api/namespaces/llvm/#abf0f52ae29f87b5e0f2b95ff961cdae1">ValueToValueMapTy</a></em>, <em><a href="/web-llvm/docs/api/namespaces/llvm/#a77724415203930efd07d7098cb1e437d">RemapFlags</a></em>, <em><a href="/web-llvm/docs/api/classes/llvm/valuemaptyperemapper">ValueMapTypeRemapper</a></em>, <em><a href="/web-llvm/docs/api/classes/llvm/valuematerializer">ValueMaterializer</a></em>, and <em>IdentityMD</em>.</p>


<p>There are a number of top-level entry points:</p>


<ul class="doxyList ">
<li><em><a href="#ae5adbfde952beb3b67c171e6b6429764">mapValue()</a></em> (and <em><a href="#abe2b1256305179d082979053910d0f8d">mapConstant()</a></em>);</li>
<li><em><a href="#a34e95c851d620226f791fcbe877762cf">mapMetadata()</a></em> (and <em><a href="#a33edb8d7bd7bce78ba42492330cc233a">mapMDNode()</a></em>);</li>
<li><em><a href="#a52c3da2ac81996e272ec9eadbd224517">remapInstruction()</a></em>;</li>
<li><em><a href="#abc0a2be8d6101a9ed7f565409fbe4151">remapFunction()</a></em>; and</li>
<li><em><a href="#ae3e49b91eb8536c50030213a24dea440">remapGlobalObjectMetadata()</a></em>.</li>
</ul>

<p>The <em><a href="/web-llvm/docs/api/classes/llvm/valuematerializer">ValueMaterializer</a></em> can be used as a callback, but cannot invoke any of these top-level functions recursively. Instead, callbacks should use one of the following to schedule work lazily in the <em><a href="/web-llvm/docs/api/classes/llvm/valuemapper">ValueMapper</a></em> instance:</p>


<ul class="doxyList ">
<li><em><a href="#a7c73fec2158f89a9339a366f5827df4b">scheduleMapGlobalInitializer()</a></em></li>
<li><em><a href="#ad87dbabd93d50b016817bf54b0345340">scheduleMapAppendingVariable()</a></em></li>
<li><em><a href="#adc967f437f5d05f0921816addf1ed9c7">scheduleMapGlobalAlias()</a></em></li>
<li><em><a href="#a8e20a241c1637ffe908adac8a5011f43">scheduleMapGlobalIFunc()</a></em></li>
<li><em><a href="#a84b3f8c68eba85bccc6d26e69679b5fe">scheduleRemapFunction()</a></em></li>
</ul>

<p>Sometimes a callback needs a different mapping context. Such a context can be registered using <em><a href="#a995e15c9fb470ea7ad0ad64a2107cb2d">registerAlternateMappingContext()</a></em>, which takes an alternate <em><a href="/web-llvm/docs/api/namespaces/llvm/#abf0f52ae29f87b5e0f2b95ff961cdae1">ValueToValueMapTy</a></em> and <em><a href="/web-llvm/docs/api/classes/llvm/valuematerializer">ValueMaterializer</a></em> and returns a <a href="/web-llvm/docs/api/namespaces/llvm/callingconv/#abdf8cf606905c10634e831390981b0ed">ID</a> to pass into the schedule*() functions.</p>


<p>If an <em>IdentityMD</em> set is optionally provided, <em><a href="/web-llvm/docs/api/classes/llvm/metadata">Metadata</a></em> inside this set will be mapped onto itself in <em>VM</em> on first use.</p>


<p>TODO: lib/Linker really doesn't need the <em>ValueHandle</em> in the <em><a href="/web-llvm/docs/api/namespaces/llvm/#abf0f52ae29f87b5e0f2b95ff961cdae1">ValueToValueMapTy</a></em>. We should template <em><a href="/web-llvm/docs/api/classes/llvm/valuemapper">ValueMapper</a></em> (and its implementation classes), and explicitly instantiate on two concrete instances of <em><a href="/web-llvm/docs/api/classes/llvm/valuemap">ValueMap</a></em> (one as <em><a href="/web-llvm/docs/api/namespaces/llvm/#afab3631a764c3f3a60ca9b1c0d7d5967">ValueToValueMap</a></em>, and one with raw <em><a href="/web-llvm/docs/api/classes/llvm/value">Value</a></em> pointers). It may be viable to do away with <em><a href="/web-llvm/docs/api/classes/llvm/trackingmdref">TrackingMDRef</a></em> in the <em><a href="/web-llvm/docs/api/classes/llvm/metadata">Metadata</a></em> side map for the lib/Linker case as well, in which case we'll need a new template parameter on <em><a href="/web-llvm/docs/api/classes/llvm/valuemap">ValueMap</a></em>.</p>


<p>TODO: Update callers of <em><a href="/web-llvm/docs/api/namespaces/llvm/#a7da684e1cead3524bdd9b0d171aad161">RemapInstruction()</a></em> and <em><a href="/web-llvm/docs/api/namespaces/llvm/#a7d7375d2149eafc730d09e8e48089021">MapValue()</a></em> (etc.) to use <em><a href="/web-llvm/docs/api/classes/llvm/valuemapper">ValueMapper</a></em> directly.</p>


<p>Definition at line 154 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/transforms/include/llvm/transforms/utils/valuemapper-h">ValueMapper.h</a>.</p>


<div class="doxySectionDef">

## Public Constructors

### ValueMapper() {#ad0c8b397f8b38de86898f8ad1a2f7ca5}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">ValueMapper::ValueMapper (<a href="/web-llvm/docs/api/namespaces/llvm/#abf0f52ae29f87b5e0f2b95ff961cdae1">ValueToValueMapTy</a> &amp; VM, <a href="/web-llvm/docs/api/namespaces/llvm/#a77724415203930efd07d7098cb1e437d">RemapFlags</a> Flags=<a href="/web-llvm/docs/api/namespaces/llvm/#a77724415203930efd07d7098cb1e437da89b60f3b4ad8c1e0ddb9a31b57cb13f9">RF_None</a>, <a href="/web-llvm/docs/api/classes/llvm/valuemaptyperemapper">ValueMapTypeRemapper</a> * TypeMapper=nullptr, <a href="/web-llvm/docs/api/classes/llvm/valuematerializer">ValueMaterializer</a> * Materializer=nullptr, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/namespaces/llvm/#a91897d2d0da113b016f14ae110586ab1">MetadataSetTy</a> * IdentityMD=nullptr)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Declaration at line 158 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/transforms/include/llvm/transforms/utils/valuemapper-h">ValueMapper.h</a>, definition at line 1208 of file <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/utils/valuemapper-cpp">ValueMapper.cpp</a>.</p>


<p>Referenced by <a href="#a4e6ce25d919abcceeeefa6773954847b">operator=</a>, <a href="#abe4e609531e4bfd5beb3a32fe65a0718">operator=</a>, <a href="#ab5b058f81f944fe9f6511cba20f05a16">ValueMapper</a> and <a href="#a5426f4a7848eb0f1d32cde68b6a1e859">ValueMapper</a>.</p>

</div>
</div>

### ValueMapper() {#a5426f4a7848eb0f1d32cde68b6a1e859}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">llvm::ValueMapper::ValueMapper (<a href="/web-llvm/docs/api/classes/llvm/valuemapper">ValueMapper</a> &amp;&amp;)</td>
</tr>
</table>
</td>
<td class="doxyMemberLabelsRight">
<span class="doxyMemberLabels">
<span class="doxyMemberLabel delete">delete</span>
</span>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 162 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/transforms/include/llvm/transforms/utils/valuemapper-h">ValueMapper.h</a>.</p>


<p>Reference <a href="#ad0c8b397f8b38de86898f8ad1a2f7ca5">ValueMapper</a>.</p>

</div>
</div>

### ValueMapper() {#ab5b058f81f944fe9f6511cba20f05a16}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">llvm::ValueMapper::ValueMapper (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/valuemapper">ValueMapper</a> &amp;)</td>
</tr>
</table>
</td>
<td class="doxyMemberLabelsRight">
<span class="doxyMemberLabels">
<span class="doxyMemberLabel delete">delete</span>
</span>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 163 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/transforms/include/llvm/transforms/utils/valuemapper-h">ValueMapper.h</a>.</p>


<p>Reference <a href="#ad0c8b397f8b38de86898f8ad1a2f7ca5">ValueMapper</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Public Destructor

### \~ValueMapper() {#a069d03c6a59e7842f4989ad2cbdf784b}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">ValueMapper::~ValueMapper ()</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Declaration at line 166 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/transforms/include/llvm/transforms/utils/valuemapper-h">ValueMapper.h</a>, definition at line 1214 of file <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/utils/valuemapper-cpp">ValueMapper.cpp</a>.</p>


<p>Reference <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/utils/valuemapper-cpp/#a6a27385e1d060ed2f46eef63ae302509">getAsMapper</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Public Operators

### operator=() {#abe4e609531e4bfd5beb3a32fe65a0718}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">ValueMapper &amp; llvm::ValueMapper::operator= (<a href="/web-llvm/docs/api/classes/llvm/valuemapper">ValueMapper</a> &amp;&amp;)</td>
</tr>
</table>
</td>
<td class="doxyMemberLabelsRight">
<span class="doxyMemberLabels">
<span class="doxyMemberLabel delete">delete</span>
</span>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 164 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/transforms/include/llvm/transforms/utils/valuemapper-h">ValueMapper.h</a>.</p>


<p>Reference <a href="#ad0c8b397f8b38de86898f8ad1a2f7ca5">ValueMapper</a>.</p>

</div>
</div>

### operator=() {#a4e6ce25d919abcceeeefa6773954847b}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">ValueMapper &amp; llvm::ValueMapper::operator= (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/valuemapper">ValueMapper</a> &amp;)</td>
</tr>
</table>
</td>
<td class="doxyMemberLabelsRight">
<span class="doxyMemberLabels">
<span class="doxyMemberLabel delete">delete</span>
</span>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 165 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/transforms/include/llvm/transforms/utils/valuemapper-h">ValueMapper.h</a>.</p>


<p>References <a href="/web-llvm/docs/api/namespaces/llvm/callingconv/#ac6aa1387c4375260e2468eb5a77fdb4cafd841a49aec1539bc88abc8ff9e170fb">llvm::CallingConv::C</a>, <a href="/web-llvm/docs/api/files/lib/lib/support/md5-cpp/#a96d73bbd7af15cb1fc38c3f4a3bd82e9">F</a>, <a href="/web-llvm/docs/api/files/lib/lib/support/md5-cpp/#ac0eafdc9ee161b71e7af98af736952fd">I</a>, <a href="/web-llvm/docs/api/files/lib/lib/support/regcomp-c/#a0240ac851181b84ac374872dc5434ee4">N</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/nvptx/nvvmintrrange-cpp/#a34bd74317e3f04bfc4318c2d1a470877">Range</a> and <a href="#ad0c8b397f8b38de86898f8ad1a2f7ca5">ValueMapper</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Public Member Functions

### addFlags() {#afe293888b7729d9e4561b842029a81d2}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void ValueMapper::addFlags (<a href="/web-llvm/docs/api/namespaces/llvm/#a77724415203930efd07d7098cb1e437d">RemapFlags</a> Flags)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Add to the current <em><a href="/web-llvm/docs/api/namespaces/llvm/#a77724415203930efd07d7098cb1e437d">RemapFlags</a></em>.</p>



:::info
<p>Like the top-level mapping functions, <em><a href="#afe293888b7729d9e4561b842029a81d2">addFlags()</a></em> must be called at the top level, not during a callback in a <em><a href="/web-llvm/docs/api/classes/llvm/valuematerializer">ValueMaterializer</a></em>.</p>
:::


<p>Declaration at line 180 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/transforms/include/llvm/transforms/utils/valuemapper-h">ValueMapper.h</a>, definition at line 1222 of file <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/utils/valuemapper-cpp">ValueMapper.cpp</a>.</p>

</div>
</div>

### mapConstant() {#abe2b1256305179d082979053910d0f8d}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">Constant * ValueMapper::mapConstant (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/constant">Constant</a> &amp; C)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Declaration at line 186 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/transforms/include/llvm/transforms/utils/valuemapper-h">ValueMapper.h</a>, definition at line 1230 of file <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/utils/valuemapper-cpp">ValueMapper.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/namespaces/llvm/callingconv/#ac6aa1387c4375260e2468eb5a77fdb4cafd841a49aec1539bc88abc8ff9e170fb">llvm::CallingConv::C</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a3e627c32543ca70720c4270a8b11da3f">llvm::cast_or_null</a> and <a href="#ae5adbfde952beb3b67c171e6b6429764">mapValue</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/namespaces/llvm/#a14ee556d11594fb4a3b9ec4372ba519a">llvm::MapValue</a>.</p>

</div>
</div>

### mapMDNode() {#a33edb8d7bd7bce78ba42492330cc233a}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">MDNode * ValueMapper::mapMDNode (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/mdnode">MDNode</a> &amp; N)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Declaration at line 183 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/transforms/include/llvm/transforms/utils/valuemapper-h">ValueMapper.h</a>, definition at line 1238 of file <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/utils/valuemapper-cpp">ValueMapper.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/namespaces/llvm/#a3e627c32543ca70720c4270a8b11da3f">llvm::cast_or_null</a>, <a href="#a34e95c851d620226f791fcbe877762cf">mapMetadata</a> and <a href="/web-llvm/docs/api/files/lib/lib/support/regcomp-c/#a0240ac851181b84ac374872dc5434ee4">N</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/namespaces/llvm/#ad8c7d2d5a6bee5e7fd70861da745011d">llvm::MapMetadata</a>.</p>

</div>
</div>

### mapMetadata() {#a34e95c851d620226f791fcbe877762cf}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">Metadata * ValueMapper::mapMetadata (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/metadata">Metadata</a> &amp; MD)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Declaration at line 182 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/transforms/include/llvm/transforms/utils/valuemapper-h">ValueMapper.h</a>, definition at line 1234 of file <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/utils/valuemapper-cpp">ValueMapper.cpp</a>.</p>


<p>Referenced by <a href="#a33edb8d7bd7bce78ba42492330cc233a">mapMDNode</a> and <a href="/web-llvm/docs/api/namespaces/llvm/#a2e1cbfa3b8663c65505fcd7e5119638f">llvm::MapMetadata</a>.</p>

</div>
</div>

### mapValue() {#ae5adbfde952beb3b67c171e6b6429764}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">Value * ValueMapper::mapValue (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/value">Value</a> &amp; V)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Declaration at line 185 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/transforms/include/llvm/transforms/utils/valuemapper-h">ValueMapper.h</a>, definition at line 1226 of file <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/utils/valuemapper-cpp">ValueMapper.cpp</a>.</p>


<p>Referenced by <a href="#abe2b1256305179d082979053910d0f8d">mapConstant</a> and <a href="/web-llvm/docs/api/namespaces/llvm/#a7d7375d2149eafc730d09e8e48089021">llvm::MapValue</a>.</p>

</div>
</div>

### registerAlternateMappingContext() {#a995e15c9fb470ea7ad0ad64a2107cb2d}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">unsigned ValueMapper::registerAlternateMappingContext (<a href="/web-llvm/docs/api/namespaces/llvm/#abf0f52ae29f87b5e0f2b95ff961cdae1">ValueToValueMapTy</a> &amp; VM, <a href="/web-llvm/docs/api/classes/llvm/valuematerializer">ValueMaterializer</a> * Materializer=nullptr)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p><a href="/web-llvm/docs/api/classes/llvm/register">Register</a> an alternate mapping context.</p>


<p>Returns a MappingContextID that can be used with the various schedule*() API to switch in a different value map on-the-fly.</p>


<p>Declaration at line 173 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/transforms/include/llvm/transforms/utils/valuemapper-h">ValueMapper.h</a>, definition at line 1217 of file <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/utils/valuemapper-cpp">ValueMapper.cpp</a>.</p>


<p>Reference <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/utils/valuemapper-cpp/#a6a27385e1d060ed2f46eef63ae302509">getAsMapper</a>.</p>

</div>
</div>

### remapDbgRecord() {#a06197e7841d4afc1dac5d5e812818fbf}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void ValueMapper::remapDbgRecord (<a href="/web-llvm/docs/api/classes/llvm/module">Module</a> * M, <a href="/web-llvm/docs/api/classes/llvm/dbgrecord">DbgRecord</a> &amp; V)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Declaration at line 189 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/transforms/include/llvm/transforms/utils/valuemapper-h">ValueMapper.h</a>, definition at line 1246 of file <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/utils/valuemapper-cpp">ValueMapper.cpp</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/namespaces/llvm/#a7f9da6836e29ef23fa74d3af96dad639">llvm::RemapDbgRecord</a> and <a href="#a17575c108f15c37d5475da79089be35b">remapDbgRecordRange</a>.</p>

</div>
</div>

### remapDbgRecordRange() {#a17575c108f15c37d5475da79089be35b}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void ValueMapper::remapDbgRecordRange (<a href="/web-llvm/docs/api/classes/llvm/module">Module</a> * M, <a href="/web-llvm/docs/api/classes/llvm/iterator-range">iterator_range</a>&lt; <a href="/web-llvm/docs/api/namespaces/llvm/#ac98637d8ed0a7a261db0a78e590edf0f">DbgRecordIterator</a> &gt; Range)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Declaration at line 190 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/transforms/include/llvm/transforms/utils/valuemapper-h">ValueMapper.h</a>, definition at line 1250 of file <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/utils/valuemapper-cpp">ValueMapper.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/nvptx/nvvmintrrange-cpp/#a34bd74317e3f04bfc4318c2d1a470877">Range</a> and <a href="#a06197e7841d4afc1dac5d5e812818fbf">remapDbgRecord</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/namespaces/llvm/#a3c6de822ccc920e435932d6cb73ac146">llvm::RemapDbgRecordRange</a>.</p>

</div>
</div>

### remapFunction() {#abc0a2be8d6101a9ed7f565409fbe4151}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void ValueMapper::remapFunction (<a href="/web-llvm/docs/api/classes/llvm/function">Function</a> &amp; F)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Declaration at line 191 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/transforms/include/llvm/transforms/utils/valuemapper-h">ValueMapper.h</a>, definition at line 1257 of file <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/utils/valuemapper-cpp">ValueMapper.cpp</a>.</p>


<p>Reference <a href="/web-llvm/docs/api/files/lib/lib/support/md5-cpp/#a96d73bbd7af15cb1fc38c3f4a3bd82e9">F</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/namespaces/llvm/#a142494cd83b3db792419910822ccc8d6">llvm::RemapFunction</a> and <a href="/web-llvm/docs/api/classes/anonymous-amdgpulowerbufferfatpointers-cpp-/amdgpulowerbufferfatpointers/#a00d87849a4eb6524d910ab07f0fd968f">anonymous{AMDGPULowerBufferFatPointers.cpp}::AMDGPULowerBufferFatPointers::run</a>.</p>

</div>
</div>

### remapGlobalObjectMetadata() {#ae3e49b91eb8536c50030213a24dea440}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void ValueMapper::remapGlobalObjectMetadata (<a href="/web-llvm/docs/api/classes/llvm/globalobject">GlobalObject</a> &amp; GO)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Declaration at line 192 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/transforms/include/llvm/transforms/utils/valuemapper-h">ValueMapper.h</a>, definition at line 1261 of file <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/utils/valuemapper-cpp">ValueMapper.cpp</a>.</p>

</div>
</div>

### remapInstruction() {#a52c3da2ac81996e272ec9eadbd224517}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void ValueMapper::remapInstruction (<a href="/web-llvm/docs/api/classes/llvm/instruction">Instruction</a> &amp; I)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Declaration at line 188 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/transforms/include/llvm/transforms/utils/valuemapper-h">ValueMapper.h</a>, definition at line 1242 of file <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/utils/valuemapper-cpp">ValueMapper.cpp</a>.</p>


<p>Reference <a href="/web-llvm/docs/api/files/lib/lib/support/md5-cpp/#ac0eafdc9ee161b71e7af98af736952fd">I</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/namespaces/llvm/#a7da684e1cead3524bdd9b0d171aad161">llvm::RemapInstruction</a>.</p>

</div>
</div>

### scheduleMapAppendingVariable() {#ad87dbabd93d50b016817bf54b0345340}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void ValueMapper::scheduleMapAppendingVariable (<a href="/web-llvm/docs/api/classes/llvm/globalvariable">GlobalVariable</a> &amp; GV, <a href="/web-llvm/docs/api/classes/llvm/constant">Constant</a> * InitPrefix, bool IsOldCtorDtor, <a href="/web-llvm/docs/api/classes/llvm/arrayref">ArrayRef</a>&lt; <a href="/web-llvm/docs/api/classes/llvm/constant">Constant</a> * &gt; NewMembers, unsigned MappingContextID=0)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Declaration at line 196 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/transforms/include/llvm/transforms/utils/valuemapper-h">ValueMapper.h</a>, definition at line 1271 of file <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/utils/valuemapper-cpp">ValueMapper.cpp</a>.</p>


<p>Reference <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/utils/valuemapper-cpp/#a6a27385e1d060ed2f46eef63ae302509">getAsMapper</a>.</p>

</div>
</div>

### scheduleMapGlobalAlias() {#adc967f437f5d05f0921816addf1ed9c7}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void ValueMapper::scheduleMapGlobalAlias (<a href="/web-llvm/docs/api/classes/llvm/globalalias">GlobalAlias</a> &amp; GA, <a href="/web-llvm/docs/api/classes/llvm/constant">Constant</a> &amp; Aliasee, unsigned MappingContextID=0)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Declaration at line 200 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/transforms/include/llvm/transforms/utils/valuemapper-h">ValueMapper.h</a>, definition at line 1280 of file <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/utils/valuemapper-cpp">ValueMapper.cpp</a>.</p>


<p>Reference <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/utils/valuemapper-cpp/#a6a27385e1d060ed2f46eef63ae302509">getAsMapper</a>.</p>

</div>
</div>

### scheduleMapGlobalIFunc() {#a8e20a241c1637ffe908adac8a5011f43}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void ValueMapper::scheduleMapGlobalIFunc (<a href="/web-llvm/docs/api/classes/llvm/globalifunc">GlobalIFunc</a> &amp; GI, <a href="/web-llvm/docs/api/classes/llvm/constant">Constant</a> &amp; Resolver, unsigned MappingContextID=0)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Declaration at line 202 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/transforms/include/llvm/transforms/utils/valuemapper-h">ValueMapper.h</a>, definition at line 1285 of file <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/utils/valuemapper-cpp">ValueMapper.cpp</a>.</p>


<p>Reference <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/utils/valuemapper-cpp/#a6a27385e1d060ed2f46eef63ae302509">getAsMapper</a>.</p>

</div>
</div>

### scheduleMapGlobalInitializer() {#a7c73fec2158f89a9339a366f5827df4b}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void ValueMapper::scheduleMapGlobalInitializer (<a href="/web-llvm/docs/api/classes/llvm/globalvariable">GlobalVariable</a> &amp; GV, <a href="/web-llvm/docs/api/classes/llvm/constant">Constant</a> &amp; Init, unsigned MappingContextID=0)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Declaration at line 194 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/transforms/include/llvm/transforms/utils/valuemapper-h">ValueMapper.h</a>, definition at line 1265 of file <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/utils/valuemapper-cpp">ValueMapper.cpp</a>.</p>


<p>Reference <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/utils/valuemapper-cpp/#a6a27385e1d060ed2f46eef63ae302509">getAsMapper</a>.</p>

</div>
</div>

### scheduleRemapFunction() {#a84b3f8c68eba85bccc6d26e69679b5fe}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void ValueMapper::scheduleRemapFunction (<a href="/web-llvm/docs/api/classes/llvm/function">Function</a> &amp; F, unsigned MappingContextID=0)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Declaration at line 204 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/transforms/include/llvm/transforms/utils/valuemapper-h">ValueMapper.h</a>, definition at line 1290 of file <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/utils/valuemapper-cpp">ValueMapper.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/files/lib/lib/support/md5-cpp/#a96d73bbd7af15cb1fc38c3f4a3bd82e9">F</a> and <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/utils/valuemapper-cpp/#a6a27385e1d060ed2f46eef63ae302509">getAsMapper</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Private Member Attributes

### pImpl {#aeb9808ac3c62b8854015f6674100dc79}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void* llvm::ValueMapper::pImpl</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 155 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/transforms/include/llvm/transforms/utils/valuemapper-h">ValueMapper.h</a>.</p>

</div>
</div>

</div>

<hr/>

The documentation for this class was generated from the following files:

<ul>
<li><a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/transforms/include/llvm/transforms/utils/valuemapper-h">ValueMapper.h</a></li>
<li><a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/utils/valuemapper-cpp">ValueMapper.cpp</a></li>
</ul>

<hr/>

<p class="doxyGeneratedBy">Generated via <a href="https://github.com/xpack/doxygen2docusaurus">doxygen2docusaurus</a> by <a href="https://www.doxygen.nl">Doxygen</a> 1.15.0.</p>

</div>
