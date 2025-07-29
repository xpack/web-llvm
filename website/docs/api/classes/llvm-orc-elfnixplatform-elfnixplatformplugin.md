---

# DO NOT EDIT!
# Automatically generated via doxygen2docusaurus by Doxygen.

slug: /api/classes/llvm/orc/elfnixplatform/elfnixplatformplugin
custom_edit_url: null
toc_max_heading_level: 4
keywords:
  - doxygen
  - reference
  - class

---

<div class="doxyPage">

# `ELFNixPlatformPlugin` Class



## Declaration

<div class="doxyDeclaration">
class llvm::orc::ELFNixPlatform::ELFNixPlatformPlugin { ... }
</div>

## Base class

<table class="doxyMembersIndex">

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">class</td>
<td class="doxyMemberIndexItemName" align="left" valign="top">ObjectLinkingLayer::Plugin</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

</table>

## Public Constructors Index

<table class="doxyMembersIndex">

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a012c91d994295c47bb7e70f3a18f63a2">ELFNixPlatformPlugin</a> (ELFNixPlatform &amp;MP)</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">void</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ae0f092738c232db9793e7065996ba5be">modifyPassConfig</a> (MaterializationResponsibility &amp;MR, jitlink::LinkGraph &amp;G, jitlink::PassConfiguration &amp;Config) override</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/error">Error</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a9f314a29a6d1729e8382e2bb464f3378">notifyFailed</a> (MaterializationResponsibility &amp;MR) override</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/error">Error</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a7a4e693639f616a9eaa84a546b363df7">notifyRemovingResources</a> (JITDylib &amp;JD, ResourceKey K) override</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a6eefc4140aa64b65bbd8154763d938b2">notifyTransferringResources</a> (JITDylib &amp;JD, ResourceKey DstKey, ResourceKey SrcKey) override</td>
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

## Private Member Functions Index

<table class="doxyMembersIndex">

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/error">Error</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ac3c806537127b4b25d34dca93aad4c52">bootstrapPipelineStart</a> (jitlink::LinkGraph &amp;G)</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/error">Error</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ac0b585627222e27d0b07d317de5ccaf1">bootstrapPipelineRecordRuntimeFunctions</a> (jitlink::LinkGraph &amp;G)</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/error">Error</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a31f9adccdcebf7a25a0fb59bef388356">bootstrapPipelineEnd</a> (jitlink::LinkGraph &amp;G)</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a69059ec9a5957a347daebc6b8b202f26">addDSOHandleSupportPasses</a> (MaterializationResponsibility &amp;MR, jitlink::PassConfiguration &amp;Config)</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a043e04fe3d7afc8439c032a5be2ab3c1">addEHAndTLVSupportPasses</a> (MaterializationResponsibility &amp;MR, jitlink::PassConfiguration &amp;Config, bool IsBootstrapping)</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/error">Error</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a9d3b95e373b19a536c7ad9c15a752f80">preserveInitSections</a> (jitlink::LinkGraph &amp;G, MaterializationResponsibility &amp;MR)</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/error">Error</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a8e9e4a78428ee825add156c12d872600">registerInitSections</a> (jitlink::LinkGraph &amp;G, JITDylib &amp;JD, bool IsBootstrapping)</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/error">Error</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#aa65ba816d95374a001e54f17ae369a01">fixTLVSectionsAndEdges</a> (jitlink::LinkGraph &amp;G, JITDylib &amp;JD)</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ac34528e98979b79ab7b40abd286f2eea">PluginMutex</a></td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/orc/elfnixplatform">ELFNixPlatform</a> &amp;</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a11cfc76c681b1831f618779636da572d">MP</a></td>
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


<p>Definition at line 168 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/executionengine/include/llvm/executionengine/orc/elfnixplatform-h">ELFNixPlatform.h</a>.</p>


<div class="doxySectionDef">

## Public Constructors

### ELFNixPlatformPlugin() {#a012c91d994295c47bb7e70f3a18f63a2}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">llvm::orc::ELFNixPlatform::ELFNixPlatformPlugin::ELFNixPlatformPlugin (<a href="/web-llvm/docs/api/classes/llvm/orc/elfnixplatform">ELFNixPlatform</a> &amp; MP)</td>
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



<p>Definition at line 170 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/executionengine/include/llvm/executionengine/orc/elfnixplatform-h">ELFNixPlatform.h</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Public Member Functions

### modifyPassConfig() {#ae0f092738c232db9793e7065996ba5be}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void llvm::orc::ELFNixPlatform::ELFNixPlatformPlugin::modifyPassConfig (<a href="/web-llvm/docs/api/classes/llvm/orc/materializationresponsibility">MaterializationResponsibility</a> &amp; MR, <a href="/web-llvm/docs/api/classes/llvm/jitlink/linkgraph">jitlink::LinkGraph</a> &amp; G, <a href="/web-llvm/docs/api/structs/llvm/jitlink/passconfiguration">jitlink::PassConfiguration</a> &amp; Config)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Declaration at line 172 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/executionengine/include/llvm/executionengine/orc/elfnixplatform-h">ELFNixPlatform.h</a>, definition at line 726 of file <a href="/web-llvm/docs/api/files/lib/lib/executionengine/lib/executionengine/orc/elfnixplatform-cpp">ELFNixPlatform.cpp</a>.</p>

</div>
</div>

### notifyFailed() {#a9f314a29a6d1729e8382e2bb464f3378}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">Error llvm::orc::ELFNixPlatform::ELFNixPlatformPlugin::notifyFailed (<a href="/web-llvm/docs/api/classes/llvm/orc/materializationresponsibility">MaterializationResponsibility</a> &amp; MR)</td>
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



<p>Definition at line 178 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/executionengine/include/llvm/executionengine/orc/elfnixplatform-h">ELFNixPlatform.h</a>.</p>

</div>
</div>

### notifyRemovingResources() {#a7a4e693639f616a9eaa84a546b363df7}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">Error llvm::orc::ELFNixPlatform::ELFNixPlatformPlugin::notifyRemovingResources (<a href="/web-llvm/docs/api/classes/llvm/orc/jitdylib">JITDylib</a> &amp; JD, <a href="/web-llvm/docs/api/namespaces/llvm/orc/#a48eb648e96394270c69273c29bfad24e">ResourceKey</a> K)</td>
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



<p>Definition at line 182 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/executionengine/include/llvm/executionengine/orc/elfnixplatform-h">ELFNixPlatform.h</a>.</p>

</div>
</div>

### notifyTransferringResources() {#a6eefc4140aa64b65bbd8154763d938b2}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void llvm::orc::ELFNixPlatform::ELFNixPlatformPlugin::notifyTransferringResources (<a href="/web-llvm/docs/api/classes/llvm/orc/jitdylib">JITDylib</a> &amp; JD, <a href="/web-llvm/docs/api/namespaces/llvm/orc/#a48eb648e96394270c69273c29bfad24e">ResourceKey</a> DstKey, <a href="/web-llvm/docs/api/namespaces/llvm/orc/#a48eb648e96394270c69273c29bfad24e">ResourceKey</a> SrcKey)</td>
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



<p>Definition at line 186 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/executionengine/include/llvm/executionengine/orc/elfnixplatform-h">ELFNixPlatform.h</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Private Member Functions

### addDSOHandleSupportPasses() {#a69059ec9a5957a347daebc6b8b202f26}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void llvm::orc::ELFNixPlatform::ELFNixPlatformPlugin::addDSOHandleSupportPasses (<a href="/web-llvm/docs/api/classes/llvm/orc/materializationresponsibility">MaterializationResponsibility</a> &amp; MR, <a href="/web-llvm/docs/api/structs/llvm/jitlink/passconfiguration">jitlink::PassConfiguration</a> &amp; Config)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Declaration at line 194 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/executionengine/include/llvm/executionengine/orc/elfnixplatform-h">ELFNixPlatform.h</a>, definition at line 778 of file <a href="/web-llvm/docs/api/files/lib/lib/executionengine/lib/executionengine/orc/elfnixplatform-cpp">ELFNixPlatform.cpp</a>.</p>

</div>
</div>

### addEHAndTLVSupportPasses() {#a043e04fe3d7afc8439c032a5be2ab3c1}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void llvm::orc::ELFNixPlatform::ELFNixPlatformPlugin::addEHAndTLVSupportPasses (<a href="/web-llvm/docs/api/classes/llvm/orc/materializationresponsibility">MaterializationResponsibility</a> &amp; MR, <a href="/web-llvm/docs/api/structs/llvm/jitlink/passconfiguration">jitlink::PassConfiguration</a> &amp; Config, bool IsBootstrapping)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Declaration at line 197 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/executionengine/include/llvm/executionengine/orc/elfnixplatform-h">ELFNixPlatform.h</a>, definition at line 804 of file <a href="/web-llvm/docs/api/files/lib/lib/executionengine/lib/executionengine/orc/elfnixplatform-cpp">ELFNixPlatform.cpp</a>.</p>

</div>
</div>

### bootstrapPipelineEnd() {#a31f9adccdcebf7a25a0fb59bef388356}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">Error llvm::orc::ELFNixPlatform::ELFNixPlatformPlugin::bootstrapPipelineEnd (<a href="/web-llvm/docs/api/classes/llvm/jitlink/linkgraph">jitlink::LinkGraph</a> &amp; G)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Declaration at line 192 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/executionengine/include/llvm/executionengine/orc/elfnixplatform-h">ELFNixPlatform.h</a>, definition at line 677 of file <a href="/web-llvm/docs/api/files/lib/lib/executionengine/lib/executionengine/orc/elfnixplatform-cpp">ELFNixPlatform.cpp</a>.</p>

</div>
</div>

### bootstrapPipelineRecordRuntimeFunctions() {#ac0b585627222e27d0b07d317de5ccaf1}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">Error llvm::orc::ELFNixPlatform::ELFNixPlatformPlugin::bootstrapPipelineRecordRuntimeFunctions (<a href="/web-llvm/docs/api/classes/llvm/jitlink/linkgraph">jitlink::LinkGraph</a> &amp; G)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Declaration at line 191 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/executionengine/include/llvm/executionengine/orc/elfnixplatform-h">ELFNixPlatform.h</a>, definition at line 631 of file <a href="/web-llvm/docs/api/files/lib/lib/executionengine/lib/executionengine/orc/elfnixplatform-cpp">ELFNixPlatform.cpp</a>.</p>

</div>
</div>

### bootstrapPipelineStart() {#ac3c806537127b4b25d34dca93aad4c52}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">Error llvm::orc::ELFNixPlatform::ELFNixPlatformPlugin::bootstrapPipelineStart (<a href="/web-llvm/docs/api/classes/llvm/jitlink/linkgraph">jitlink::LinkGraph</a> &amp; G)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Declaration at line 190 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/executionengine/include/llvm/executionengine/orc/elfnixplatform-h">ELFNixPlatform.h</a>, definition at line 622 of file <a href="/web-llvm/docs/api/files/lib/lib/executionengine/lib/executionengine/orc/elfnixplatform-cpp">ELFNixPlatform.cpp</a>.</p>

</div>
</div>

### fixTLVSectionsAndEdges() {#aa65ba816d95374a001e54f17ae369a01}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">Error llvm::orc::ELFNixPlatform::ELFNixPlatformPlugin::fixTLVSectionsAndEdges (<a href="/web-llvm/docs/api/classes/llvm/jitlink/linkgraph">jitlink::LinkGraph</a> &amp; G, <a href="/web-llvm/docs/api/classes/llvm/orc/jitdylib">JITDylib</a> &amp; JD)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Declaration at line 207 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/executionengine/include/llvm/executionengine/orc/elfnixplatform-h">ELFNixPlatform.h</a>, definition at line 981 of file <a href="/web-llvm/docs/api/files/lib/lib/executionengine/lib/executionengine/orc/elfnixplatform-cpp">ELFNixPlatform.cpp</a>.</p>

</div>
</div>

### preserveInitSections() {#a9d3b95e373b19a536c7ad9c15a752f80}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">Error llvm::orc::ELFNixPlatform::ELFNixPlatformPlugin::preserveInitSections (<a href="/web-llvm/docs/api/classes/llvm/jitlink/linkgraph">jitlink::LinkGraph</a> &amp; G, <a href="/web-llvm/docs/api/classes/llvm/orc/materializationresponsibility">MaterializationResponsibility</a> &amp; MR)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Declaration at line 201 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/executionengine/include/llvm/executionengine/orc/elfnixplatform-h">ELFNixPlatform.h</a>, definition at line 863 of file <a href="/web-llvm/docs/api/files/lib/lib/executionengine/lib/executionengine/orc/elfnixplatform-cpp">ELFNixPlatform.cpp</a>.</p>

</div>
</div>

### registerInitSections() {#a8e9e4a78428ee825add156c12d872600}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">Error llvm::orc::ELFNixPlatform::ELFNixPlatformPlugin::registerInitSections (<a href="/web-llvm/docs/api/classes/llvm/jitlink/linkgraph">jitlink::LinkGraph</a> &amp; G, <a href="/web-llvm/docs/api/classes/llvm/orc/jitdylib">JITDylib</a> &amp; JD, bool IsBootstrapping)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Declaration at line 204 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/executionengine/include/llvm/executionengine/orc/elfnixplatform-h">ELFNixPlatform.h</a>, definition at line 899 of file <a href="/web-llvm/docs/api/files/lib/lib/executionengine/lib/executionengine/orc/elfnixplatform-cpp">ELFNixPlatform.cpp</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Private Member Attributes

### MP {#a11cfc76c681b1831f618779636da572d}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">ELFNixPlatform&amp; llvm::orc::ELFNixPlatform::ELFNixPlatformPlugin::MP</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 210 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/executionengine/include/llvm/executionengine/orc/elfnixplatform-h">ELFNixPlatform.h</a>.</p>

</div>
</div>

### PluginMutex {#ac34528e98979b79ab7b40abd286f2eea}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">std::mutex llvm::orc::ELFNixPlatform::ELFNixPlatformPlugin::PluginMutex</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 209 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/executionengine/include/llvm/executionengine/orc/elfnixplatform-h">ELFNixPlatform.h</a>.</p>

</div>
</div>

</div>

<hr/>

The documentation for this class was generated from the following files:

<ul>
<li><a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/executionengine/include/llvm/executionengine/orc/elfnixplatform-h">ELFNixPlatform.h</a></li>
<li><a href="/web-llvm/docs/api/files/lib/lib/executionengine/lib/executionengine/orc/elfnixplatform-cpp">ELFNixPlatform.cpp</a></li>
</ul>

<hr/>

<p class="doxyGeneratedBy">Generated via <a href="https://github.com/xpack/doxygen2docusaurus">doxygen2docusaurus</a> by <a href="https://www.doxygen.nl">Doxygen</a> 1.15.0.</p>

</div>
