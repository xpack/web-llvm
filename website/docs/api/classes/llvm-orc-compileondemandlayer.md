---

# DO NOT EDIT!
# Automatically generated via doxygen2docusaurus by Doxygen.

slug: /api/classes/llvm/orc/compileondemandlayer
custom_edit_url: null
toc_max_heading_level: 4
keywords:
  - doxygen
  - reference
  - class

---

<div class="doxyPage">

# The `CompileOnDemandLayer` Class Reference



## Declaration

<div class="doxyDeclaration">
class llvm::orc::CompileOnDemandLayer { ... }
</div>

## Included Headers

<div class="doxyIncludesList">#include "<a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/executionengine/include/llvm/executionengine/orc/compileondemandlayer-h">llvm/ExecutionEngine/Orc/CompileOnDemandLayer.h</a>"
</div>

## Base class

<table class="doxyMembersIndex">

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">class</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/orc/irlayer">IRLayer</a></td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Interface for layers that accept LLVM IR. <a href="/web-llvm/docs/api/classes/llvm/orc/irlayer/#details">More...</a></p>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a8bccd12782700db63367128dc4a3c89d">IndirectStubsManagerBuilder</a> = std::function&lt; std::unique_ptr&lt; <a href="/web-llvm/docs/api/classes/llvm/orc/indirectstubsmanager">IndirectStubsManager</a> &gt;()&gt;</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Builder for IndirectStubsManagers. <a href="#a8bccd12782700db63367128dc4a3c89d">More...</a></p>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a1c0f4e08fae802417c25853b6bf0d32e">PerDylibResourcesMap</a> = std::map&lt; <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/orc/jitdylib">JITDylib</a> *, PerDylibResources &gt;</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a60b3749f91b86e4e27270e69d82fb330">CompileOnDemandLayer</a> (ExecutionSession &amp;ES, IRLayer &amp;BaseLayer, LazyCallThroughManager &amp;LCTMgr, IndirectStubsManagerBuilder BuildIndirectStubsManager)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Construct a <a href="/web-llvm/docs/api/classes/llvm/orc/compileondemandlayer">CompileOnDemandLayer</a>. <a href="#a60b3749f91b86e4e27270e69d82fb330">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

</table>

## Public Member Functions Index

<table class="doxyMembersIndex">

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">void</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a7c507a2cc8f50d7dbf01908e8b3be329">setImplMap</a> (ImplSymbolMap *Imp)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Sets the <a href="/web-llvm/docs/api/classes/llvm/orc/implsymbolmap">ImplSymbolMap</a>. <a href="#a7c507a2cc8f50d7dbf01908e8b3be329">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">void</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a58cc5a656f5d4cc0a32d58494dcb860b">emit</a> (std::unique_ptr&lt; MaterializationResponsibility &gt; R, ThreadSafeModule TSM) override</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Emits the given module. <a href="#a58cc5a656f5d4cc0a32d58494dcb860b">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

</table>

## Private Member Functions Index

<table class="doxyMembersIndex">

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">PerDylibResources &amp;</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a77c00dafd3139f077a126440836bfec7">getPerDylibResources</a> (JITDylib &amp;TargetD)</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">std::mutex</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a9d66e414a61eff40f081b97b13900485">CODLayerMutex</a></td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/orc/irlayer">IRLayer</a> &amp;</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#aadc665f3e210437af16f0ce2e32c1b7f">BaseLayer</a></td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/orc/lazycallthroughmanager">LazyCallThroughManager</a> &amp;</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a135d3a71a90412e65c9dadcabfc86107">LCTMgr</a></td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="#a8bccd12782700db63367128dc4a3c89d">IndirectStubsManagerBuilder</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ad630f89b0b981167f422f5aa772aca29">BuildIndirectStubsManager</a></td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">PerDylibResourcesMap</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#aa2191fae7c4b84c78dd2fd4dce703a2d">DylibResources</a></td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/orc/implsymbolmap">ImplSymbolMap</a> *</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#acca14270156e38b136d14a13088e4fc9">AliaseeImpls</a> = nullptr</td>
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


<p>Definition at line 55 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/executionengine/include/llvm/executionengine/orc/compileondemandlayer-h">CompileOnDemandLayer.h</a>.</p>


<div class="doxySectionDef">

## Public Member Typedefs

### IndirectStubsManagerBuilder {#a8bccd12782700db63367128dc4a3c89d}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">using llvm::orc::CompileOnDemandLayer::IndirectStubsManagerBuilder = 
      std::function&lt;std::unique_ptr&lt;IndirectStubsManager&gt;()&gt;</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Builder for IndirectStubsManagers.</p>

<p>Definition at line 58 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/executionengine/include/llvm/executionengine/orc/compileondemandlayer-h">CompileOnDemandLayer.h</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Private Member Typedefs

### PerDylibResourcesMap {#a1c0f4e08fae802417c25853b6bf0d32e}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">using llvm::orc::CompileOnDemandLayer::PerDylibResourcesMap =  std::map&lt;const JITDylib *, PerDylibResources&gt;</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 87 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/executionengine/include/llvm/executionengine/orc/compileondemandlayer-h">CompileOnDemandLayer.h</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Public Constructors

### CompileOnDemandLayer() {#a60b3749f91b86e4e27270e69d82fb330}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">CompileOnDemandLayer::CompileOnDemandLayer (<a href="/web-llvm/docs/api/classes/llvm/orc/executionsession">ExecutionSession</a> &amp; ES, <a href="/web-llvm/docs/api/classes/llvm/orc/irlayer">IRLayer</a> &amp; BaseLayer, <a href="/web-llvm/docs/api/classes/llvm/orc/lazycallthroughmanager">LazyCallThroughManager</a> &amp; LCTMgr, <a href="#a8bccd12782700db63367128dc4a3c89d">IndirectStubsManagerBuilder</a> BuildIndirectStubsManager)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Construct a <a href="/web-llvm/docs/api/classes/llvm/orc/compileondemandlayer">CompileOnDemandLayer</a>.</p>

<p>Declaration at line 62 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/executionengine/include/llvm/executionengine/orc/compileondemandlayer-h">CompileOnDemandLayer.h</a>, definition at line 16 of file <a href="/web-llvm/docs/api/files/lib/lib/executionengine/lib/executionengine/orc/compileondemandlayer-cpp">CompileOnDemandLayer.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/classes/llvm/orc/irlayer/#ae3cfe72cdaca15dbe4c360d8bcdb5207">llvm::orc::IRLayer::getManglingOptions</a>, <a href="/web-llvm/docs/api/classes/llvm/orc/irlayer/#a1141609d9c7e4bdd205bc09698ff51b3">llvm::orc::IRLayer::IRLayer</a> and <a href="/web-llvm/docs/api/namespaces/llvm/#abfc9c7ecf70f66901e439f7c04ef3dbb">llvm::move</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Public Member Functions

### emit() {#a58cc5a656f5d4cc0a32d58494dcb860b}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void CompileOnDemandLayer::emit (std::unique_ptr&lt; <a href="/web-llvm/docs/api/classes/llvm/orc/materializationresponsibility">MaterializationResponsibility</a> &gt; R, <a href="/web-llvm/docs/api/classes/llvm/orc/threadsafemodule">ThreadSafeModule</a> TSM)</td>
</tr>
</table>
</td>
<td class="doxyMemberLabelsRight">
<span class="doxyMemberLabels">
<span class="doxyMemberLabel virtual">virtual</span>
</span>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Emits the given module.</p>


<p>This should not be called by clients: it will be called by the JIT when a definition added via the add method is requested.</p>


<p>Declaration at line 70 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/executionengine/include/llvm/executionengine/orc/compileondemandlayer-h">CompileOnDemandLayer.h</a>, definition at line 27 of file <a href="/web-llvm/docs/api/files/lib/lib/executionengine/lib/executionengine/orc/compileondemandlayer-cpp">CompileOnDemandLayer.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/silowercontrolflow-cpp/#a4868c5d81c5ccc98c47aeab6244346a0">assert</a>, <a href="/web-llvm/docs/api/classes/llvm/densemapbase/#a49c487a9395a6c384be8544cfb2cfccf">llvm::DenseMapBase&lt; DerivedT, KeyT, ValueT, KeyInfoT, BucketT &gt;::empty</a>, <a href="/web-llvm/docs/api/classes/llvm/orc/irlayer/#a88dfbca45a6353ce7c643414c0d945cf">llvm::orc::IRLayer::getExecutionSession</a>, <a href="/web-llvm/docs/api/classes/llvm/orc/irlayer/#ae3cfe72cdaca15dbe4c360d8bcdb5207">llvm::orc::IRLayer::getManglingOptions</a>, <a href="/web-llvm/docs/api/namespaces/llvm/orc/#aa74c9e8e6a57d19831cc120e9b2a37fd">llvm::orc::lazyReexports</a>, <a href="/web-llvm/docs/api/namespaces/llvm/orc/#a7cb1d8cb0ab2329f032d69d79498c81da5fa8627bea3ff4b720673b9a298caf2d">llvm::orc::MatchAllSymbols</a>, <a href="/web-llvm/docs/api/namespaces/llvm/orc/#a6b9e003e73655db7fad152ceddb3b45b">llvm::orc::reexports</a> and <a href="/web-llvm/docs/api/classes/llvm/orc/executionsession/#a1c47ed6ddfb6770f1a432af1c9acdc44">llvm::orc::ExecutionSession::reportError</a>.</p>

</div>
</div>

### setImplMap() {#a7c507a2cc8f50d7dbf01908e8b3be329}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void CompileOnDemandLayer::setImplMap (<a href="/web-llvm/docs/api/classes/llvm/orc/implsymbolmap">ImplSymbolMap</a> * Imp)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Sets the <a href="/web-llvm/docs/api/classes/llvm/orc/implsymbolmap">ImplSymbolMap</a>.</p>

<p>Declaration at line 66 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/executionengine/include/llvm/executionengine/orc/compileondemandlayer-h">CompileOnDemandLayer.h</a>, definition at line 23 of file <a href="/web-llvm/docs/api/files/lib/lib/executionengine/lib/executionengine/orc/compileondemandlayer-cpp">CompileOnDemandLayer.cpp</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Private Member Functions

### getPerDylibResources() {#a77c00dafd3139f077a126440836bfec7}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">CompileOnDemandLayer::PerDylibResources &amp; CompileOnDemandLayer::getPerDylibResources (<a href="/web-llvm/docs/api/classes/llvm/orc/jitdylib">JITDylib</a> &amp; TargetD)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Declaration at line 89 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/executionengine/include/llvm/executionengine/orc/compileondemandlayer-h">CompileOnDemandLayer.h</a>, definition at line 78 of file <a href="/web-llvm/docs/api/files/lib/lib/executionengine/lib/executionengine/orc/compileondemandlayer-cpp">CompileOnDemandLayer.cpp</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Private Member Attributes

### AliaseeImpls {#acca14270156e38b136d14a13088e4fc9}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">ImplSymbolMap* llvm::orc::CompileOnDemandLayer::AliaseeImpls = nullptr</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 97 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/executionengine/include/llvm/executionengine/orc/compileondemandlayer-h">CompileOnDemandLayer.h</a>.</p>

</div>
</div>

### BaseLayer {#aadc665f3e210437af16f0ce2e32c1b7f}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">IRLayer&amp; llvm::orc::CompileOnDemandLayer::BaseLayer</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 93 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/executionengine/include/llvm/executionengine/orc/compileondemandlayer-h">CompileOnDemandLayer.h</a>.</p>

</div>
</div>

### BuildIndirectStubsManager {#ad630f89b0b981167f422f5aa772aca29}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">IndirectStubsManagerBuilder llvm::orc::CompileOnDemandLayer::BuildIndirectStubsManager</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 95 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/executionengine/include/llvm/executionengine/orc/compileondemandlayer-h">CompileOnDemandLayer.h</a>.</p>

</div>
</div>

### CODLayerMutex {#a9d66e414a61eff40f081b97b13900485}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">std::mutex llvm::orc::CompileOnDemandLayer::CODLayerMutex</td>
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



<p>Definition at line 91 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/executionengine/include/llvm/executionengine/orc/compileondemandlayer-h">CompileOnDemandLayer.h</a>.</p>

</div>
</div>

### DylibResources {#aa2191fae7c4b84c78dd2fd4dce703a2d}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">PerDylibResourcesMap llvm::orc::CompileOnDemandLayer::DylibResources</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 96 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/executionengine/include/llvm/executionengine/orc/compileondemandlayer-h">CompileOnDemandLayer.h</a>.</p>

</div>
</div>

### LCTMgr {#a135d3a71a90412e65c9dadcabfc86107}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">LazyCallThroughManager&amp; llvm::orc::CompileOnDemandLayer::LCTMgr</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 94 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/executionengine/include/llvm/executionengine/orc/compileondemandlayer-h">CompileOnDemandLayer.h</a>.</p>

</div>
</div>

</div>

<hr/>

The documentation for this class was generated from the following files:

<ul>
<li><a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/executionengine/include/llvm/executionengine/orc/compileondemandlayer-h">CompileOnDemandLayer.h</a></li>
<li><a href="/web-llvm/docs/api/files/lib/lib/executionengine/lib/executionengine/orc/compileondemandlayer-cpp">CompileOnDemandLayer.cpp</a></li>
</ul>

<hr/>

<p class="doxyGeneratedBy">Generated via <a href="https://github.com/xpack/doxygen2docusaurus">doxygen2docusaurus</a> by <a href="https://www.doxygen.nl">Doxygen</a> 1.15.0.</p>

</div>
