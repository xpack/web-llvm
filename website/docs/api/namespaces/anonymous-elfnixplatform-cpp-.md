---

# DO NOT EDIT!
# Automatically generated via doxygen2docusaurus by Doxygen.

slug: /api/namespaces/anonymous-elfnixplatform-cpp-
custom_edit_url: null
toc_max_heading_level: 4
keywords:
  - doxygen
  - reference
  - namespace

---

<div class="doxyPage">

# The `anonymous{ELFNixPlatform.cpp}` Namespace Reference



## Definition

<div class="doxyDefinition">
namespace anonymous{ELFNixPlatform.cpp} { ... }
</div>

## Classes Index

<table class="doxyMembersIndex">

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">class</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="/web-llvm/docs/api/classes/anonymous-elfnixplatform-cpp-/elfnixplatformcompletebootstrapmaterializationunit">ELFNixPlatformCompleteBootstrapMaterializationUnit</a></td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">class</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="/web-llvm/docs/api/classes/anonymous-elfnixplatform-cpp-/dsohandlematerializationunit">DSOHandleMaterializationUnit</a></td>
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
<td class="doxyMemberIndexTemplate" colspan="2"><div>template &lt;typename SPSSerializer, typename... ArgTs&gt;</div></td>
</tr>
<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemTypeTemplate" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/orc/shared/wrapperfunctioncall/#aa437c8c5cbb354584f2b0720610cbe62">shared::WrapperFunctionCall::ArgDataBufferType</a></td>
<td class="doxyMemberIndexItemNameTemplate" align="left" valign="top"><a href="#ae8fb1e7d144d58bebdc065615673d9f4">getArgDataBufferType</a> (const ArgTs &amp;...Args)</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">std::unique_ptr&lt; <a href="/web-llvm/docs/api/classes/llvm/jitlink/linkgraph">jitlink::LinkGraph</a> &gt;</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a4edaac18b04b42252a7c922e21fcc222">createPlatformGraph</a> (ELFNixPlatform &amp;MOP, std::string Name)</td>
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


<div class="doxySectionDef">

## Functions

### createPlatformGraph() {#a4edaac18b04b42252a7c922e21fcc222}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">std::unique_ptr&lt; jitlink::LinkGraph &gt; anonymous{ELFNixPlatform.cpp}::createPlatformGraph (<a href="/web-llvm/docs/api/classes/llvm/orc/elfnixplatform">ELFNixPlatform</a> &amp; MOP, std::string Name)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 41 of file <a href="/web-llvm/docs/api/files/lib/lib/executionengine/lib/executionengine/orc/elfnixplatform-cpp">ELFNixPlatform.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/classes/llvm/orc/elfnixplatform/#a7523fe80220e295e2b16bd82472481ee">llvm::orc::ELFNixPlatform::getExecutionSession</a> and <a href="/web-llvm/docs/api/namespaces/llvm/jitlink/#a06eee57acde48953ffd29ae8d337202e">llvm::jitlink::getGenericEdgeKindName</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/classes/anonymous-elfnixplatform-cpp-/elfnixplatformcompletebootstrapmaterializationunit/#aa18b5e663aa3f2116768bde792d2df6f">anonymous{ELFNixPlatform.cpp}::ELFNixPlatformCompleteBootstrapMaterializationUnit::materialize</a>.</p>

</div>
</div>

### getArgDataBufferType() {#ae8fb1e7d144d58bebdc065615673d9f4}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<div class="doxyMemberTemplate">template &lt;typename SPSSerializer, typename... ArgTs&gt;</div>
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">shared::WrapperFunctionCall::ArgDataBufferType anonymous{ELFNixPlatform.cpp}::getArgDataBufferType (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> ArgTs &amp;... Args)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 31 of file <a href="/web-llvm/docs/api/files/lib/lib/executionengine/lib/executionengine/orc/elfnixplatform-cpp">ELFNixPlatform.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/classes/llvm/smallvectortemplatecommon/#a7b68be12c974b6b70bc86062f221a344">llvm::SmallVectorTemplateCommon&lt; T, typename &gt;::data</a>, <a href="/web-llvm/docs/api/classes/llvm/smallvectortemplatecommon/#ad9a3c7bc26b130377bbafc170b5f88a2">llvm::SmallVectorTemplateCommon&lt; T, typename &gt;::empty</a>, <a href="/web-llvm/docs/api/classes/llvm/smallvectorimpl/#ad0b3d8447f88377b62d9c019f3c4e118">llvm::SmallVectorImpl&lt; T &gt;::resize</a> and <a href="/web-llvm/docs/api/classes/llvm/smallvectortemplatecommon/#a1c479a8c434377c2b8cb056bdfdfc201">llvm::SmallVectorTemplateCommon&lt; T, typename &gt;::size</a>.</p>

</div>
</div>

</div>

<hr/>

The documentation for this namespace was generated from the following file:

<ul>
<li><a href="/web-llvm/docs/api/files/lib/lib/executionengine/lib/executionengine/orc/elfnixplatform-cpp">ELFNixPlatform.cpp</a></li>
</ul>

<hr/>

<p class="doxyGeneratedBy">Generated via <a href="https://github.com/xpack/doxygen2docusaurus">doxygen2docusaurus</a> by <a href="https://www.doxygen.nl">Doxygen</a> 1.15.0.</p>

</div>
