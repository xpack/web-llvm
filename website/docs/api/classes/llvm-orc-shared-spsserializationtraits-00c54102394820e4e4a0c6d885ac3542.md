---

# DO NOT EDIT!
# Automatically generated via doxygen2docusaurus by Doxygen.

slug: /api/classes/llvm/orc/shared/spsserializationtraits-00c54102394820e4e4a0c6d885ac3542
custom_edit_url: null
toc_max_heading_level: 4
keywords:
  - doxygen
  - reference
  - class

---

<div class="doxyPage">

# `SPSSerializationTraits` Class Template



## Declaration

<div class="doxyDeclaration">
class llvm::orc::shared::SPSSerializationTraits&lt;SPSRemoteSymbolLookup, DylibManager::LookupRequest&gt; { ... }
</div>

## Private Member Typedefs Index

<table class="doxyMembersIndex">

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">using</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a32380a65a858ad671a6874cd2c212cef">MemberSerialization</a> = <a href="/web-llvm/docs/api/classes/llvm/orc/shared/spsarglist">SPSArgList</a>&lt; <a href="/web-llvm/docs/api/classes/llvm/orc/shared/spsexecutoraddr">SPSExecutorAddr</a>, <a href="/web-llvm/docs/api/namespaces/llvm/orc/shared/#aa4683bc096f3b0cd8be3e2bcfa5924fa">SPSRemoteSymbolLookupSet</a> &gt;</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">static size_t</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a743263a214c1e61b0b0f7204edc31ab0">size</a> (const DylibManager::LookupRequest &amp;LR)</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">static bool</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ac3ec625f50b1316875a6cff25997925b">serialize</a> (SPSOutputBuffer &amp;OB, const DylibManager::LookupRequest &amp;LR)</td>
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


<p>Definition at line 43 of file <a href="/web-llvm/docs/api/files/lib/lib/executionengine/lib/executionengine/orc/epcgenericdylibmanager-cpp">EPCGenericDylibManager.cpp</a>.</p>


<div class="doxySectionDef">

## Private Member Typedefs

### MemberSerialization {#a32380a65a858ad671a6874cd2c212cef}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">using llvm::orc::shared::SPSSerializationTraits&lt; SPSRemoteSymbolLookup, DylibManager::LookupRequest &gt;::MemberSerialization = 
      SPSArgList&lt;SPSExecutorAddr, SPSRemoteSymbolLookupSet&gt;</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 45 of file <a href="/web-llvm/docs/api/files/lib/lib/executionengine/lib/executionengine/orc/epcgenericdylibmanager-cpp">EPCGenericDylibManager.cpp</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Public Static Functions

### serialize() {#ac3ec625f50b1316875a6cff25997925b}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool llvm::orc::shared::SPSSerializationTraits&lt; SPSRemoteSymbolLookup, DylibManager::LookupRequest &gt;::serialize (<a href="/web-llvm/docs/api/classes/llvm/orc/shared/spsoutputbuffer">SPSOutputBuffer</a> &amp; OB, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/structs/llvm/orc/dylibmanager/lookuprequest">DylibManager::LookupRequest</a> &amp; LR)</td>
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



<p>Definition at line 53 of file <a href="/web-llvm/docs/api/files/lib/lib/executionengine/lib/executionengine/orc/epcgenericdylibmanager-cpp">EPCGenericDylibManager.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/structs/llvm/orc/dylibmanager/lookuprequest/#a0ad6e98070f8308cb8699c98a9f903d0">llvm::orc::DylibManager::LookupRequest::Handle</a> and <a href="/web-llvm/docs/api/structs/llvm/orc/dylibmanager/lookuprequest/#a4c3a9af49af3d697ca48dae256ac250c">llvm::orc::DylibManager::LookupRequest::Symbols</a>.</p>

</div>
</div>

### size() {#a743263a214c1e61b0b0f7204edc31ab0}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">size_t llvm::orc::shared::SPSSerializationTraits&lt; SPSRemoteSymbolLookup, DylibManager::LookupRequest &gt;::size (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/structs/llvm/orc/dylibmanager/lookuprequest">DylibManager::LookupRequest</a> &amp; LR)</td>
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



<p>Definition at line 49 of file <a href="/web-llvm/docs/api/files/lib/lib/executionengine/lib/executionengine/orc/epcgenericdylibmanager-cpp">EPCGenericDylibManager.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/structs/llvm/orc/dylibmanager/lookuprequest/#a0ad6e98070f8308cb8699c98a9f903d0">llvm::orc::DylibManager::LookupRequest::Handle</a> and <a href="/web-llvm/docs/api/structs/llvm/orc/dylibmanager/lookuprequest/#a4c3a9af49af3d697ca48dae256ac250c">llvm::orc::DylibManager::LookupRequest::Symbols</a>.</p>

</div>
</div>

</div>

<hr/>

The documentation for this class was generated from the following file:

<ul>
<li><a href="/web-llvm/docs/api/files/lib/lib/executionengine/lib/executionengine/orc/epcgenericdylibmanager-cpp">EPCGenericDylibManager.cpp</a></li>
</ul>

<hr/>

<p class="doxyGeneratedBy">Generated via <a href="https://github.com/xpack/doxygen2docusaurus">doxygen2docusaurus</a> by <a href="https://www.doxygen.nl">Doxygen</a> 1.15.0.</p>

</div>
