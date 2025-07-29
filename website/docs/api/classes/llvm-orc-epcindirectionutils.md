---

# DO NOT EDIT!
# Automatically generated via doxygen2docusaurus by Doxygen.

slug: /api/classes/llvm/orc/epcindirectionutils
custom_edit_url: null
toc_max_heading_level: 4
keywords:
  - doxygen
  - reference
  - class

---

<div class="doxyPage">

# `EPCIndirectionUtils` Class

<p>Provides <a href="/web-llvm/docs/api/classes/llvm/orc/executorprocesscontrol">ExecutorProcessControl</a> based indirect stubs, trampoline pool and lazy call through manager. <a href="#details">More...</a></p>

## Declaration

<div class="doxyDeclaration">
class llvm::orc::EPCIndirectionUtils { ... }
</div>

## Included Headers

<div class="doxyIncludesList">#include "<a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/executionengine/include/llvm/executionengine/orc/epcindirectionutils-h">llvm/ExecutionEngine/Orc/EPCIndirectionUtils.h</a>"
</div>

## Private Member Typedefs Index

<table class="doxyMembersIndex">

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">using</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a8fd18c91b4930801c6715d7ccd0926fa">FinalizedAlloc</a> = <a href="/web-llvm/docs/api/classes/llvm/jitlink/jitlinkmemorymanager/finalizedalloc">jitlink::JITLinkMemoryManager::FinalizedAlloc</a></td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">using</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a1402ed65906e05a2c627754fadcf1214">IndirectStubInfoVector</a> = std::vector&lt; IndirectStubInfo &gt;</td>
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

## Friends Index

<table class="doxyMembersIndex">

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">class</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#af21342dd5bd9ad4edb6cece95bc5b83e">EPCIndirectionUtilsAccess</a></td>
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

## Private Constructors Index

<table class="doxyMembersIndex">

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#aba3e6ad9de2599cf2de495f8326855d6">EPCIndirectionUtils</a> (ExecutorProcessControl &amp;EPC, std::unique_ptr&lt; ABISupport &gt; ABI)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Create an <a href="/web-llvm/docs/api/classes/llvm/orc/epcindirectionutils">EPCIndirectionUtils</a> instance. <a href="#aba3e6ad9de2599cf2de495f8326855d6">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

</table>

## Public Member Functions Index

<table class="doxyMembersIndex">

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/orc/executorprocesscontrol">ExecutorProcessControl</a> &amp;</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a8890a3e6bb712df11b8cfcd9508fae8b">getExecutorProcessControl</a> () const</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Return a reference to the <a href="/web-llvm/docs/api/classes/llvm/orc/executorprocesscontrol">ExecutorProcessControl</a> object. <a href="#a8890a3e6bb712df11b8cfcd9508fae8b">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/orc/epcindirectionutils/abisupport">ABISupport</a> &amp;</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#af3e8d441173c1c1316665a7de1391a85">getABISupport</a> () const</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Return a reference to the <a href="/web-llvm/docs/api/classes/llvm/orc/epcindirectionutils/abisupport">ABISupport</a> object for this instance. <a href="#af3e8d441173c1c1316665a7de1391a85">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/error">Error</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ad028c15d9d57c008dc6bad42e35110e5">cleanup</a> ()</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Release memory for resources held by this instance. <a href="#ad028c15d9d57c008dc6bad42e35110e5">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/expected">Expected</a>&lt; <a href="/web-llvm/docs/api/classes/llvm/orc/executoraddr">ExecutorAddr</a> &gt;</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a317664253790f09d0e0f53c7cfbbea16">writeResolverBlock</a> (ExecutorAddr ReentryFnAddr, ExecutorAddr ReentryCtxAddr)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Write resolver code to the executor process and return its address. <a href="#a317664253790f09d0e0f53c7cfbbea16">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/orc/executoraddr">ExecutorAddr</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#affa9b5484486ff45ae096fe18ee64b61">getResolverBlockAddress</a> () const</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Returns the address of the <a href="/web-llvm/docs/api/classes/llvm/resolver">Resolver</a> block. <a href="#affa9b5484486ff45ae096fe18ee64b61">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">std::unique_ptr&lt; <a href="/web-llvm/docs/api/classes/llvm/orc/indirectstubsmanager">IndirectStubsManager</a> &gt;</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a065673061f0571c524d168d53b6da30e">createIndirectStubsManager</a> ()</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Create an <a href="/web-llvm/docs/api/classes/llvm/orc/indirectstubsmanager">IndirectStubsManager</a> for the executor process. <a href="#a065673061f0571c524d168d53b6da30e">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/orc/trampolinepool">TrampolinePool</a> &amp;</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#aea5d38db0f25b5d558713ee7e95b54b1">getTrampolinePool</a> ()</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Create a <a href="/web-llvm/docs/api/classes/llvm/orc/trampolinepool">TrampolinePool</a> for the executor process. <a href="#aea5d38db0f25b5d558713ee7e95b54b1">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/orc/lazycallthroughmanager">LazyCallThroughManager</a> &amp;</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#acee4c6d802b59a49a6d81e448a8674fb">createLazyCallThroughManager</a> (ExecutionSession &amp;ES, ExecutorAddr ErrorHandlerAddr)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Create a <a href="/web-llvm/docs/api/classes/llvm/orc/lazycallthroughmanager">LazyCallThroughManager</a>. <a href="#acee4c6d802b59a49a6d81e448a8674fb">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/orc/lazycallthroughmanager">LazyCallThroughManager</a> &amp;</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a5ec24aada6fb79fc32ae32e753c828a3">getLazyCallThroughManager</a> ()</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Create a <a href="/web-llvm/docs/api/classes/llvm/orc/lazycallthroughmanager">LazyCallThroughManager</a> for the executor process. <a href="#a5ec24aada6fb79fc32ae32e753c828a3">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

</table>

## Private Member Functions Index

<table class="doxyMembersIndex">

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/expected">Expected</a>&lt; IndirectStubInfoVector &gt;</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a9d71dbbcb578c1635fcef09530de3b94">getIndirectStubs</a> (unsigned NumStubs)</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a92a43585dcf79ae0105198c65b99d85a">EPCUIMutex</a></td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/orc/executorprocesscontrol">ExecutorProcessControl</a> &amp;</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a3f6f661a5d6523cade4b9e4c7eca3b3a">EPC</a></td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">std::unique_ptr&lt; <a href="/web-llvm/docs/api/classes/llvm/orc/epcindirectionutils/abisupport">ABISupport</a> &gt;</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a958e6ca066ebf535057cb16b7f22c4e9">ABI</a></td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/orc/executoraddr">ExecutorAddr</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ab77557af84e481a3353ea29257efc9f1">ResolverBlockAddr</a></td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/jitlink/jitlinkmemorymanager/finalizedalloc">FinalizedAlloc</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#afab39824070bee25ac8b6642ddb56ce9">ResolverBlock</a></td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">std::unique_ptr&lt; <a href="/web-llvm/docs/api/classes/llvm/orc/trampolinepool">TrampolinePool</a> &gt;</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#aad6a71d28a5a2601a83c046affd8c25b">TP</a></td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">std::unique_ptr&lt; <a href="/web-llvm/docs/api/classes/llvm/orc/lazycallthroughmanager">LazyCallThroughManager</a> &gt;</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#aacd755719a77412e313776ed919b5728">LCTM</a></td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">std::vector&lt; IndirectStubInfo &gt;</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a641d2d4d3bf5bebf024c81aa0eab35eb">AvailableIndirectStubs</a></td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">std::vector&lt; <a href="/web-llvm/docs/api/classes/llvm/jitlink/jitlinkmemorymanager/finalizedalloc">FinalizedAlloc</a> &gt;</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ae8eb3a7917e846701d0c0d71b83f614f">IndirectStubAllocs</a></td>
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

<tr class="doxyMemberIndexTemplate">
<td class="doxyMemberIndexTemplate" colspan="2"><div>template &lt;typename ORCABI&gt;</div></td>
</tr>
<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemTypeTemplate" align="left" valign="top">static auto </td>
<td class="doxyMemberIndexItemNameTemplate" align="left" valign="top"><a href="#a82f3f02e592ad6d352e788e7282449c3">CreateWithABI</a> (ExecutorProcessControl &amp;EPC) -&gt; std::unique_ptr&lt; <a href="/web-llvm/docs/api/classes/llvm/orc/epcindirectionutils">EPCIndirectionUtils</a> &gt;</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Create using the given ABI class. <a href="#a82f3f02e592ad6d352e788e7282449c3">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">static <a href="/web-llvm/docs/api/classes/llvm/expected">Expected</a>&lt; std::unique_ptr&lt; <a href="/web-llvm/docs/api/classes/llvm/orc/epcindirectionutils">EPCIndirectionUtils</a> &gt; &gt;</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#af27142d4d30e48ac9857889e37500483">Create</a> (ExecutorProcessControl &amp;EPC)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Create based on the <a href="/web-llvm/docs/api/classes/llvm/orc/executorprocesscontrol">ExecutorProcessControl</a> triple. <a href="#af27142d4d30e48ac9857889e37500483">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">static <a href="/web-llvm/docs/api/classes/llvm/expected">Expected</a>&lt; std::unique_ptr&lt; <a href="/web-llvm/docs/api/classes/llvm/orc/epcindirectionutils">EPCIndirectionUtils</a> &gt; &gt;</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a2d4d7f7525cb9afe6a7f1c767e5f2599">Create</a> (ExecutionSession &amp;ES)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Create based on the <a href="/web-llvm/docs/api/classes/llvm/orc/executorprocesscontrol">ExecutorProcessControl</a> triple. <a href="#a2d4d7f7525cb9afe6a7f1c767e5f2599">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

</table>

## Description {#details}

<p>Provides <a href="/web-llvm/docs/api/classes/llvm/orc/executorprocesscontrol">ExecutorProcessControl</a> based indirect stubs, trampoline pool and lazy call through manager.</p>

<p>Definition at line 30 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/executionengine/include/llvm/executionengine/orc/epcindirectionutils-h">EPCIndirectionUtils.h</a>.</p>


<div class="doxySectionDef">

## Private Member Typedefs

### FinalizedAlloc {#a8fd18c91b4930801c6715d7ccd0926fa}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">using llvm::orc::EPCIndirectionUtils::FinalizedAlloc =  jitlink::JITLinkMemoryManager::FinalizedAlloc</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 132 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/executionengine/include/llvm/executionengine/orc/epcindirectionutils-h">EPCIndirectionUtils.h</a>.</p>

</div>
</div>

### IndirectStubInfoVector {#a1402ed65906e05a2c627754fadcf1214}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">using llvm::orc::EPCIndirectionUtils::IndirectStubInfoVector =  std::vector&lt;IndirectStubInfo&gt;</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 142 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/executionengine/include/llvm/executionengine/orc/epcindirectionutils-h">EPCIndirectionUtils.h</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Friends

### EPCIndirectionUtilsAccess {#af21342dd5bd9ad4edb6cece95bc5b83e}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">friend class <a href="/web-llvm/docs/api/classes/llvm/orc/epcindirectionutilsaccess">EPCIndirectionUtilsAccess</a></td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">


<p>Definition at line 31 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/executionengine/include/llvm/executionengine/orc/epcindirectionutils-h">EPCIndirectionUtils.h</a>.</p>


<p>Reference <a href="#af21342dd5bd9ad4edb6cece95bc5b83e">EPCIndirectionUtilsAccess</a>.</p>


<p>Referenced by <a href="#af21342dd5bd9ad4edb6cece95bc5b83e">EPCIndirectionUtilsAccess</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Private Constructors

### EPCIndirectionUtils() {#aba3e6ad9de2599cf2de495f8326855d6}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">llvm::orc::EPCIndirectionUtils::EPCIndirectionUtils (<a href="/web-llvm/docs/api/classes/llvm/orc/executorprocesscontrol">ExecutorProcessControl</a> &amp; EPC, std::unique_ptr&lt; <a href="/web-llvm/docs/api/classes/llvm/orc/epcindirectionutils/abisupport">ABISupport</a> &gt; ABI)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Create an <a href="/web-llvm/docs/api/classes/llvm/orc/epcindirectionutils">EPCIndirectionUtils</a> instance.</p>

<p>Declaration at line 145 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/executionengine/include/llvm/executionengine/orc/epcindirectionutils-h">EPCIndirectionUtils.h</a>, definition at line 339 of file <a href="/web-llvm/docs/api/files/lib/lib/executionengine/lib/executionengine/orc/epcindirectionutils-cpp">EPCIndirectionUtils.cpp</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Public Member Functions

### cleanup() {#ad028c15d9d57c008dc6bad42e35110e5}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">Error llvm::orc::EPCIndirectionUtils::cleanup ()</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Release memory for resources held by this instance.</p>


<p>This <em>must</em> be called prior to destruction of the class.</p>


<p>Declaration at line 101 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/executionengine/include/llvm/executionengine/orc/epcindirectionutils-h">EPCIndirectionUtils.h</a>, definition at line 273 of file <a href="/web-llvm/docs/api/files/lib/lib/executionengine/lib/executionengine/orc/epcindirectionutils-cpp">EPCIndirectionUtils.cpp</a>.</p>


<p>Reference <a href="/web-llvm/docs/api/namespaces/llvm/#a71210b99d2ef87236d8505c1771a7ab1">llvm::joinErrors</a>.</p>

</div>
</div>

### createIndirectStubsManager() {#a065673061f0571c524d168d53b6da30e}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">std::unique_ptr&lt; IndirectStubsManager &gt; llvm::orc::EPCIndirectionUtils::createIndirectStubsManager ()</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Create an <a href="/web-llvm/docs/api/classes/llvm/orc/indirectstubsmanager">IndirectStubsManager</a> for the executor process.</p>

<p>Declaration at line 114 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/executionengine/include/llvm/executionengine/orc/epcindirectionutils-h">EPCIndirectionUtils.h</a>, definition at line 320 of file <a href="/web-llvm/docs/api/files/lib/lib/executionengine/lib/executionengine/orc/epcindirectionutils-cpp">EPCIndirectionUtils.cpp</a>.</p>

</div>
</div>

### createLazyCallThroughManager() {#acee4c6d802b59a49a6d81e448a8674fb}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">LazyCallThroughManager &amp; llvm::orc::EPCIndirectionUtils::createLazyCallThroughManager (<a href="/web-llvm/docs/api/classes/llvm/orc/executionsession">ExecutionSession</a> &amp; ES, <a href="/web-llvm/docs/api/classes/llvm/orc/executoraddr">ExecutorAddr</a> ErrorHandlerAddr)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Create a <a href="/web-llvm/docs/api/classes/llvm/orc/lazycallthroughmanager">LazyCallThroughManager</a>.</p>


<p>This function should only be called once.</p>


<p>Declaration at line 122 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/executionengine/include/llvm/executionengine/orc/epcindirectionutils-h">EPCIndirectionUtils.h</a>, definition at line 330 of file <a href="/web-llvm/docs/api/files/lib/lib/executionengine/lib/executionengine/orc/epcindirectionutils-cpp">EPCIndirectionUtils.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/silowercontrolflow-cpp/#a4868c5d81c5ccc98c47aeab6244346a0">assert</a> and <a href="#aea5d38db0f25b5d558713ee7e95b54b1">getTrampolinePool</a>.</p>

</div>
</div>

### getABISupport() {#af3e8d441173c1c1316665a7de1391a85}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">ABISupport &amp; llvm::orc::EPCIndirectionUtils::getABISupport ()</td>
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

<p>Return a reference to the <a href="/web-llvm/docs/api/classes/llvm/orc/epcindirectionutils/abisupport">ABISupport</a> object for this instance.</p>

<p>Definition at line 97 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/executionengine/include/llvm/executionengine/orc/epcindirectionutils-h">EPCIndirectionUtils.h</a>.</p>

</div>
</div>

### getExecutorProcessControl() {#a8890a3e6bb712df11b8cfcd9508fae8b}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">ExecutorProcessControl &amp; llvm::orc::EPCIndirectionUtils::getExecutorProcessControl ()</td>
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

<p>Return a reference to the <a href="/web-llvm/docs/api/classes/llvm/orc/executorprocesscontrol">ExecutorProcessControl</a> object.</p>

<p>Definition at line 94 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/executionengine/include/llvm/executionengine/orc/epcindirectionutils-h">EPCIndirectionUtils.h</a>.</p>

</div>
</div>

### getLazyCallThroughManager() {#a5ec24aada6fb79fc32ae32e753c828a3}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">LazyCallThroughManager &amp; llvm::orc::EPCIndirectionUtils::getLazyCallThroughManager ()</td>
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

<p>Create a <a href="/web-llvm/docs/api/classes/llvm/orc/lazycallthroughmanager">LazyCallThroughManager</a> for the executor process.</p>

<p>Definition at line 126 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/executionengine/include/llvm/executionengine/orc/epcindirectionutils-h">EPCIndirectionUtils.h</a>.</p>


<p>Reference <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/silowercontrolflow-cpp/#a4868c5d81c5ccc98c47aeab6244346a0">assert</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/namespaces/llvm/orc/#ad5f773f31c1e2529e6dca4686a3b968e">llvm::orc::setUpInProcessLCTMReentryViaEPCIU</a>.</p>

</div>
</div>

### getResolverBlockAddress() {#affa9b5484486ff45ae096fe18ee64b61}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">ExecutorAddr llvm::orc::EPCIndirectionUtils::getResolverBlockAddress ()</td>
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

<p>Returns the address of the <a href="/web-llvm/docs/api/classes/llvm/resolver">Resolver</a> block.</p>


<p>Returns zero if the writeResolverBlock method has not previously been called.</p>


<p>Definition at line 111 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/executionengine/include/llvm/executionengine/orc/epcindirectionutils-h">EPCIndirectionUtils.h</a>.</p>

</div>
</div>

### getTrampolinePool() {#aea5d38db0f25b5d558713ee7e95b54b1}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">TrampolinePool &amp; llvm::orc::EPCIndirectionUtils::getTrampolinePool ()</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Create a <a href="/web-llvm/docs/api/classes/llvm/orc/trampolinepool">TrampolinePool</a> for the executor process.</p>

<p>Declaration at line 117 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/executionengine/include/llvm/executionengine/orc/epcindirectionutils-h">EPCIndirectionUtils.h</a>, definition at line 324 of file <a href="/web-llvm/docs/api/files/lib/lib/executionengine/lib/executionengine/orc/epcindirectionutils-cpp">EPCIndirectionUtils.cpp</a>.</p>


<p>Referenced by <a href="#acee4c6d802b59a49a6d81e448a8674fb">createLazyCallThroughManager</a>.</p>

</div>
</div>

### writeResolverBlock() {#a317664253790f09d0e0f53c7cfbbea16}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">Expected&lt; ExecutorAddr &gt; llvm::orc::EPCIndirectionUtils::writeResolverBlock (<a href="/web-llvm/docs/api/classes/llvm/orc/executoraddr">ExecutorAddr</a> ReentryFnAddr, <a href="/web-llvm/docs/api/classes/llvm/orc/executoraddr">ExecutorAddr</a> ReentryCtxAddr)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Write resolver code to the executor process and return its address.</p>


<p>This must be called before any call to createTrampolinePool or createLazyCallThroughManager.</p>


<p>Declaration at line 106 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/executionengine/include/llvm/executionengine/orc/epcindirectionutils-h">EPCIndirectionUtils.h</a>, definition at line 290 of file <a href="/web-llvm/docs/api/files/lib/lib/executionengine/lib/executionengine/orc/epcindirectionutils-cpp">EPCIndirectionUtils.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/namespaces/llvm/#a264176188c0aadccd3ca5b6929b5a2e1aea571dc00aef155a16d4e7e1861e1682">llvm::Alloc</a> and <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/silowercontrolflow-cpp/#a4868c5d81c5ccc98c47aeab6244346a0">assert</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/namespaces/llvm/orc/#ad5f773f31c1e2529e6dca4686a3b968e">llvm::orc::setUpInProcessLCTMReentryViaEPCIU</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Private Member Functions

### getIndirectStubs() {#a9d71dbbcb578c1635fcef09530de3b94}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">Expected&lt; EPCIndirectionUtils::IndirectStubInfoVector &gt; llvm::orc::EPCIndirectionUtils::getIndirectStubs (unsigned NumStubs)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Declaration at line 148 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/executionengine/include/llvm/executionengine/orc/epcindirectionutils-h">EPCIndirectionUtils.h</a>, definition at line 349 of file <a href="/web-llvm/docs/api/files/lib/lib/executionengine/lib/executionengine/orc/epcindirectionutils-cpp">EPCIndirectionUtils.cpp</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Private Member Attributes

### ABI {#a958e6ca066ebf535057cb16b7f22c4e9}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">std::unique_ptr&lt;ABISupport&gt; llvm::orc::EPCIndirectionUtils::ABI</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 152 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/executionengine/include/llvm/executionengine/orc/epcindirectionutils-h">EPCIndirectionUtils.h</a>.</p>

</div>
</div>

### AvailableIndirectStubs {#a641d2d4d3bf5bebf024c81aa0eab35eb}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">std::vector&lt;IndirectStubInfo&gt; llvm::orc::EPCIndirectionUtils::AvailableIndirectStubs</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 158 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/executionengine/include/llvm/executionengine/orc/epcindirectionutils-h">EPCIndirectionUtils.h</a>.</p>

</div>
</div>

### EPC {#a3f6f661a5d6523cade4b9e4c7eca3b3a}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">ExecutorProcessControl&amp; llvm::orc::EPCIndirectionUtils::EPC</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 151 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/executionengine/include/llvm/executionengine/orc/epcindirectionutils-h">EPCIndirectionUtils.h</a>.</p>

</div>
</div>

### EPCUIMutex {#a92a43585dcf79ae0105198c65b99d85a}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">std::mutex llvm::orc::EPCIndirectionUtils::EPCUIMutex</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 150 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/executionengine/include/llvm/executionengine/orc/epcindirectionutils-h">EPCIndirectionUtils.h</a>.</p>

</div>
</div>

### IndirectStubAllocs {#ae8eb3a7917e846701d0c0d71b83f614f}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">std::vector&lt;FinalizedAlloc&gt; llvm::orc::EPCIndirectionUtils::IndirectStubAllocs</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 159 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/executionengine/include/llvm/executionengine/orc/epcindirectionutils-h">EPCIndirectionUtils.h</a>.</p>

</div>
</div>

### LCTM {#aacd755719a77412e313776ed919b5728}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">std::unique_ptr&lt;LazyCallThroughManager&gt; llvm::orc::EPCIndirectionUtils::LCTM</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 156 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/executionengine/include/llvm/executionengine/orc/epcindirectionutils-h">EPCIndirectionUtils.h</a>.</p>

</div>
</div>

### ResolverBlock {#afab39824070bee25ac8b6642ddb56ce9}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">FinalizedAlloc llvm::orc::EPCIndirectionUtils::ResolverBlock</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 154 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/executionengine/include/llvm/executionengine/orc/epcindirectionutils-h">EPCIndirectionUtils.h</a>.</p>

</div>
</div>

### ResolverBlockAddr {#ab77557af84e481a3353ea29257efc9f1}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">ExecutorAddr llvm::orc::EPCIndirectionUtils::ResolverBlockAddr</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 153 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/executionengine/include/llvm/executionengine/orc/epcindirectionutils-h">EPCIndirectionUtils.h</a>.</p>

</div>
</div>

### TP {#aad6a71d28a5a2601a83c046affd8c25b}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">std::unique_ptr&lt;TrampolinePool&gt; llvm::orc::EPCIndirectionUtils::TP</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 155 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/executionengine/include/llvm/executionengine/orc/epcindirectionutils-h">EPCIndirectionUtils.h</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Public Static Functions

### Create() {#af27142d4d30e48ac9857889e37500483}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">Expected&lt; std::unique_ptr&lt; EPCIndirectionUtils &gt; &gt; llvm::orc::EPCIndirectionUtils::Create (<a href="/web-llvm/docs/api/classes/llvm/orc/executorprocesscontrol">ExecutorProcessControl</a> &amp; EPC)</td>
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

<p>Create based on the <a href="/web-llvm/docs/api/classes/llvm/orc/executorprocesscontrol">ExecutorProcessControl</a> triple.</p>

<p>Declaration at line 85 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/executionengine/include/llvm/executionengine/orc/epcindirectionutils-h">EPCIndirectionUtils.h</a>, definition at line 235 of file <a href="/web-llvm/docs/api/files/lib/lib/executionengine/lib/executionengine/orc/epcindirectionutils-cpp">EPCIndirectionUtils.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/classes/llvm/triple/#a547abd13f7a3c063aa72c8192a868154aee7bfdb86a0614afb9b44615e3e652d3">llvm::Triple::aarch64</a>, <a href="/web-llvm/docs/api/classes/llvm/triple/#a547abd13f7a3c063aa72c8192a868154af26b2aa05e5a49b91b981143e0e49a34">llvm::Triple::aarch64_32</a>, <a href="#a82f3f02e592ad6d352e788e7282449c3">CreateWithABI</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a2b43c21951d0948b34bcf7019949032d">llvm::inconvertibleErrorCode</a>, <a href="/web-llvm/docs/api/classes/llvm/triple/#a547abd13f7a3c063aa72c8192a868154a7e69e3edde4260406241be26e08fbd7c">llvm::Triple::loongarch64</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a9999bd897fc8a1648bd69b36fee2d357">llvm::make_error</a>, <a href="/web-llvm/docs/api/classes/llvm/triple/#a547abd13f7a3c063aa72c8192a868154a867c596b0454c5bbeeb1ff490b9d70bc">llvm::Triple::mips</a>, <a href="/web-llvm/docs/api/classes/llvm/triple/#a547abd13f7a3c063aa72c8192a868154a9ff8c8868a9f1892ce3f896e7f0fe1e5">llvm::Triple::mips64</a>, <a href="/web-llvm/docs/api/classes/llvm/triple/#a547abd13f7a3c063aa72c8192a868154ae60fc4f421b40b84a536b24fc2a1919f">llvm::Triple::mips64el</a>, <a href="/web-llvm/docs/api/classes/llvm/triple/#a547abd13f7a3c063aa72c8192a868154a5fb4823bc5bbdad4684399b118ccace8">llvm::Triple::mipsel</a>, <a href="/web-llvm/docs/api/classes/llvm/triple/#a547abd13f7a3c063aa72c8192a868154ae4763cb7c05a2a59ce27d51040bf4b08">llvm::Triple::riscv64</a>, <a href="/web-llvm/docs/api/classes/llvm/triple/#a3cfefc755ab656000934f91193afb1cdafd0c0a465dca43ad44f79806a226a1ae">llvm::Triple::Win32</a>, <a href="/web-llvm/docs/api/classes/llvm/triple/#a547abd13f7a3c063aa72c8192a868154a0eefa3e53db25b90828e42c64b138648">llvm::Triple::x86</a> and <a href="/web-llvm/docs/api/classes/llvm/triple/#a547abd13f7a3c063aa72c8192a868154a13d8ce5e71051718a537277c6a594062">llvm::Triple::x86_64</a>.</p>


<p>Referenced by <a href="#a2d4d7f7525cb9afe6a7f1c767e5f2599">Create</a>.</p>

</div>
</div>

### Create() {#a2d4d7f7525cb9afe6a7f1c767e5f2599}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">Expected&lt; std::unique_ptr&lt; EPCIndirectionUtils &gt; &gt; llvm::orc::EPCIndirectionUtils::Create (<a href="/web-llvm/docs/api/classes/llvm/orc/executionsession">ExecutionSession</a> &amp; ES)</td>
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

<p>Create based on the <a href="/web-llvm/docs/api/classes/llvm/orc/executorprocesscontrol">ExecutorProcessControl</a> triple.</p>

<p>Definition at line 89 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/executionengine/include/llvm/executionengine/orc/epcindirectionutils-h">EPCIndirectionUtils.h</a>.</p>


<p>References <a href="#af27142d4d30e48ac9857889e37500483">Create</a> and <a href="/web-llvm/docs/api/classes/llvm/orc/executionsession/#a128c42c13c6cee5b388a8748e6a0a797">llvm::orc::ExecutionSession::getExecutorProcessControl</a>.</p>

</div>
</div>

### CreateWithABI() {#a82f3f02e592ad6d352e788e7282449c3}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<div class="doxyMemberTemplate">template &lt;typename ORCABI&gt;</div>
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">std::unique_ptr&lt; EPCIndirectionUtils &gt; llvm::orc::EPCIndirectionUtils::CreateWithABI (<a href="/web-llvm/docs/api/classes/llvm/orc/executorprocesscontrol">ExecutorProcessControl</a> &amp; EPC)</td>
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

<p>Create using the given ABI class.</p>

<p>Definition at line 81 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/executionengine/include/llvm/executionengine/orc/epcindirectionutils-h">EPCIndirectionUtils.h</a>.</p>


<p>Referenced by <a href="#af27142d4d30e48ac9857889e37500483">Create</a>.</p>

</div>
</div>

</div>

<hr/>

The documentation for this class was generated from the following files:

<ul>
<li><a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/executionengine/include/llvm/executionengine/orc/epcindirectionutils-h">EPCIndirectionUtils.h</a></li>
<li><a href="/web-llvm/docs/api/files/lib/lib/executionengine/lib/executionengine/orc/epcindirectionutils-cpp">EPCIndirectionUtils.cpp</a></li>
</ul>

<hr/>

<p class="doxyGeneratedBy">Generated via <a href="https://github.com/xpack/doxygen2docusaurus">doxygen2docusaurus</a> by <a href="https://www.doxygen.nl">Doxygen</a> 1.15.0.</p>

</div>
