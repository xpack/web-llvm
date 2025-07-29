---

# DO NOT EDIT!
# Automatically generated via doxygen2docusaurus by Doxygen.

slug: /api/classes/llvm/orc/coffplatform
custom_edit_url: null
toc_max_heading_level: 4
keywords:
  - doxygen
  - reference
  - class

---

<div class="doxyPage">

# `COFFPlatform` Class

<p>Mediates between <a href="/web-llvm/docs/api/namespaces/llvm/coff">COFF</a> initialization and <a href="/web-llvm/docs/api/classes/llvm/orc/executionsession">ExecutionSession</a> state. <a href="#details">More...</a></p>

## Declaration

<div class="doxyDeclaration">
class llvm::orc::COFFPlatform { ... }
</div>

## Included Headers

<div class="doxyIncludesList">#include "<a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/executionengine/include/llvm/executionengine/orc/coffplatform-h">llvm/ExecutionEngine/Orc/COFFPlatform.h</a>"
</div>

## Base class

<table class="doxyMembersIndex">

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">class</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/orc/platform">Platform</a></td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Platforms set up standard symbols and mediate interactions between dynamic initializers (e.g. <a href="/web-llvm/docs/api/classes/llvm/orc/platform/#details">More...</a></p>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a12da434b55a741dcb040e17d487bdf39">LoadDynamicLibrary</a> = <a href="/web-llvm/docs/api/classes/llvm/unique-function">unique_function</a>&lt; <a href="/web-llvm/docs/api/classes/llvm/error">Error</a>(<a href="/web-llvm/docs/api/classes/llvm/orc/jitdylib">JITDylib</a> &amp;JD, <a href="/web-llvm/docs/api/classes/llvm/stringref">StringRef</a> DLLFileName)&gt;</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>A function that will be called with the name of dll file that must be loaded. <a href="#a12da434b55a741dcb040e17d487bdf39">More...</a></p>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a769773f069e99a3e132676e003836fcf">COFFJITDylibDepInfo</a> = std::vector&lt; <a href="/web-llvm/docs/api/classes/llvm/orc/executoraddr">ExecutorAddr</a> &gt;</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a73f0f8d09158e4cd7a9e9487ebd5b627">COFFJITDylibDepInfoMap</a> = std::vector&lt; std::pair&lt; <a href="/web-llvm/docs/api/classes/llvm/orc/executoraddr">ExecutorAddr</a>, COFFJITDylibDepInfo &gt; &gt;</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a96dc06160ce7b2622f193378e38f37ba">COFFObjectSectionsMap</a> = <a href="/web-llvm/docs/api/classes/llvm/smallvector">SmallVector</a>&lt; std::pair&lt; std::string, <a href="/web-llvm/docs/api/structs/llvm/orc/executoraddrrange">ExecutorAddrRange</a> &gt; &gt;</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a66fc265c8cca531b589aa7daaad87d2a">PushInitializersSendResultFn</a> = <a href="/web-llvm/docs/api/classes/llvm/unique-function">unique_function</a>&lt; void(<a href="/web-llvm/docs/api/classes/llvm/expected">Expected</a>&lt; COFFJITDylibDepInfoMap &gt;)&gt;</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#aa5ba42befb40bed5291995b897e1a01e">SendSymbolAddressFn</a> = <a href="/web-llvm/docs/api/classes/llvm/unique-function">unique_function</a>&lt; void(<a href="/web-llvm/docs/api/classes/llvm/expected">Expected</a>&lt; <a href="/web-llvm/docs/api/classes/llvm/orc/executoraddr">ExecutorAddr</a> &gt;)&gt;</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#af75024abd739e62b9fefac901fe9ce9b">JITDylibDepMap</a> = <a href="/web-llvm/docs/api/classes/llvm/densemap">DenseMap</a>&lt; <a href="/web-llvm/docs/api/classes/llvm/orc/jitdylib">JITDylib</a> *, <a href="/web-llvm/docs/api/classes/llvm/smallvector">SmallVector</a>&lt; <a href="/web-llvm/docs/api/classes/llvm/orc/jitdylib">JITDylib</a> * &gt; &gt;</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a739d08c4e28997315ad0902f855138bd">COFFPlatform</a> (ObjectLinkingLayer &amp;ObjLinkingLayer, JITDylib &amp;PlatformJD, std::unique_ptr&lt; StaticLibraryDefinitionGenerator &gt; OrcRuntimeGenerator, std::unique_ptr&lt; MemoryBuffer &gt; OrcRuntimeArchiveBuffer, std::unique_ptr&lt; object::Archive &gt; OrcRuntimeArchive, LoadDynamicLibrary LoadDynLibrary, bool StaticVCRuntime, const char *VCRuntimePath, Error &amp;Err)</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/orc/executionsession">ExecutionSession</a> &amp;</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a939275744a267d0b0612f172a395ca69">getExecutionSession</a> () const</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/orc/objectlinkinglayer">ObjectLinkingLayer</a> &amp;</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a3ef249d0da17f1dab6f8a7c53957b4e9">getObjectLinkingLayer</a> () const</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a0cd59afcda8972c7ffd9254da83b7d70">setupJITDylib</a> (JITDylib &amp;JD) override</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>This method will be called outside the session lock each time a <a href="/web-llvm/docs/api/classes/llvm/orc/jitdylib">JITDylib</a> is created (unless it is created with EmptyJITDylib set) to allow the <a href="/web-llvm/docs/api/classes/llvm/orc/platform">Platform</a> to install any <a href="/web-llvm/docs/api/classes/llvm/orc/jitdylib">JITDylib</a> specific standard symbols (e.g __dso_handle). <a href="#a0cd59afcda8972c7ffd9254da83b7d70">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/error">Error</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a1a257687b19260c45eb247fdf4e83af7">teardownJITDylib</a> (JITDylib &amp;JD) override</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>This method will be called outside the session lock each time a <a href="/web-llvm/docs/api/classes/llvm/orc/jitdylib">JITDylib</a> is removed to allow the <a href="/web-llvm/docs/api/classes/llvm/orc/platform">Platform</a> to remove any JITDylib-specific data. <a href="#a1a257687b19260c45eb247fdf4e83af7">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/error">Error</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a6ceb8793145f063bcb5e204c1251649e">notifyAdding</a> (ResourceTracker &amp;RT, const MaterializationUnit &amp;MU) override</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>This method will be called under the <a href="/web-llvm/docs/api/classes/llvm/orc/executionsession">ExecutionSession</a> lock each time a <a href="/web-llvm/docs/api/classes/llvm/orc/materializationunit">MaterializationUnit</a> is added to a <a href="/web-llvm/docs/api/classes/llvm/orc/jitdylib">JITDylib</a>. <a href="#a6ceb8793145f063bcb5e204c1251649e">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/error">Error</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ae9761095caf64ffbd3c599774a4dff4b">notifyRemoving</a> (ResourceTracker &amp;RT) override</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>This method will be called under the <a href="/web-llvm/docs/api/classes/llvm/orc/executionsession">ExecutionSession</a> lock when a <a href="/web-llvm/docs/api/classes/llvm/orc/resourcetracker">ResourceTracker</a> is removed. <a href="#ae9761095caf64ffbd3c599774a4dff4b">More...</a></p>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ab33677c8adf9149cc0a6a03d7de301c3">associateRuntimeSupportFunctions</a> (JITDylib &amp;PlatformJD)</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a33419364943405307276ae8768e8e959">bootstrapCOFFRuntime</a> (JITDylib &amp;PlatformJD)</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a440c4484aeec945aa93e0cd312d73a81">runSymbolIfExists</a> (JITDylib &amp;PlatformJD, StringRef SymbolName)</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#acbf7639a33dfdf03271bdffe816938bf">runBootstrapInitializers</a> (JDBootstrapState &amp;BState)</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a526745454f3eb70d09c34bc6f2f5c879">runBootstrapSubsectionInitializers</a> (JDBootstrapState &amp;BState, StringRef Start, StringRef End)</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/expected">Expected</a>&lt; <a href="/web-llvm/docs/api/classes/llvm/densemap">JITDylibDepMap</a> &gt;</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a747a7e1862342419045866aeb1d78ee2">buildJDDepMap</a> (JITDylib &amp;JD)</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/expected">Expected</a>&lt; <a href="/web-llvm/docs/api/classes/llvm/memorybufferref">MemoryBufferRef</a> &gt;</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a775ecb0c769c0def7333729c8553e68d">getPerJDObjectFile</a> ()</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a57a08c86e6cea605831b27ea4b94bbd3">pushInitializersLoop</a> (PushInitializersSendResultFn SendResult, JITDylibSP JD, JITDylibDepMap &amp;JDDepMap)</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a0c0d40c096e1a2642ec9abd738ce01b8">rt_pushInitializers</a> (PushInitializersSendResultFn SendResult, ExecutorAddr JDHeaderAddr)</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a2f7fa97cd61d30ddb82a2355317c084f">rt_lookupSymbol</a> (SendSymbolAddressFn SendResult, ExecutorAddr Handle, StringRef SymbolName)</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/orc/executionsession">ExecutionSession</a> &amp;</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a8c90f6ac4fdcef58ba62f300623c4965">ES</a></td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/orc/objectlinkinglayer">ObjectLinkingLayer</a> &amp;</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a2e43c1df5a54b7439f8e1ac20c21cb89">ObjLinkingLayer</a></td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="#a12da434b55a741dcb040e17d487bdf39">LoadDynamicLibrary</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a9ed1841e88fdeed4ac4c1a9e8804cd47">LoadDynLibrary</a></td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">std::unique_ptr&lt; <a href="/web-llvm/docs/api/classes/llvm/orc/coffvcruntimebootstrapper">COFFVCRuntimeBootstrapper</a> &gt;</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a22d0cc8c4fad6f874da6dc970ef96093">VCRuntimeBootstrap</a></td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">std::unique_ptr&lt; <a href="/web-llvm/docs/api/classes/llvm/memorybuffer">MemoryBuffer</a> &gt;</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a1c044115512bde6ad4b83ea5ac9afe9e">OrcRuntimeArchiveBuffer</a></td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">std::unique_ptr&lt; <a href="/web-llvm/docs/api/classes/llvm/object/archive">object::Archive</a> &gt;</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a58d43b8daea9a1167e26dbb71b604496">OrcRuntimeArchive</a></td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#adb3d7d6c25b3a54dd784cb02c1d31438">StaticVCRuntime</a></td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/orc/symbolstringptr">SymbolStringPtr</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a057557e17e83ae5e1b91a10b78182405">COFFHeaderStartSymbol</a></td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">std::map&lt; <a href="/web-llvm/docs/api/classes/llvm/orc/jitdylib">JITDylib</a> *, JDBootstrapState &gt;</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a231085975b152ae86716eb62b70c16d2">JDBootstrapStates</a></td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">std::atomic&lt; bool &gt;</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a28b7358c14fd9d99b0074ccb3e67e019">Bootstrapping</a></td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a3a5000929702fd4314bdfa0be9dbddf4">orc_rt_coff_platform_bootstrap</a></td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a3d1e218441d505e2e6f0e3e5a271dd66">orc_rt_coff_platform_shutdown</a></td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a3b6560535e4842884d7159beac68d692">orc_rt_coff_register_object_sections</a></td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a345a905bb996df8aa2d37f917321d2cd">orc_rt_coff_deregister_object_sections</a></td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#aff34c21a33089f0144b90ad1444360de">orc_rt_coff_register_jitdylib</a></td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a16f87774aee0bbf4275a9eb30f2d9cef">orc_rt_coff_deregister_jitdylib</a></td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/densemap">DenseMap</a>&lt; <a href="/web-llvm/docs/api/classes/llvm/orc/jitdylib">JITDylib</a> *, <a href="/web-llvm/docs/api/classes/llvm/orc/executoraddr">ExecutorAddr</a> &gt;</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a3f9ff60adff7f5dc919046af6928c2b8">JITDylibToHeaderAddr</a></td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/densemap">DenseMap</a>&lt; <a href="/web-llvm/docs/api/classes/llvm/orc/executoraddr">ExecutorAddr</a>, <a href="/web-llvm/docs/api/classes/llvm/orc/jitdylib">JITDylib</a> * &gt;</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a486e4d67f57cf69bc736c35950eb595e">HeaderAddrToJITDylib</a></td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/densemap">DenseMap</a>&lt; <a href="/web-llvm/docs/api/classes/llvm/orc/jitdylib">JITDylib</a> *, <a href="/web-llvm/docs/api/classes/llvm/orc/symbollookupset">SymbolLookupSet</a> &gt;</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#aec55b13893610c89843b9478948b8f03">RegisteredInitSymbols</a></td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">std::set&lt; std::string &gt;</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#abcda8ae14ed5587ca145d07bb445f6cc">DylibsToPreload</a></td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">std::mutex</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a81f207065861800d6b332a31410ae7ca">PlatformMutex</a></td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">static <a href="/web-llvm/docs/api/classes/llvm/expected">Expected</a>&lt; std::unique_ptr&lt; <a href="/web-llvm/docs/api/classes/llvm/orc/coffplatform">COFFPlatform</a> &gt; &gt;</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a0ff140ec3eee8b9a860f3626b5640c04">Create</a> (ObjectLinkingLayer &amp;ObjLinkingLayer, JITDylib &amp;PlatformJD, std::unique_ptr&lt; MemoryBuffer &gt; OrcRuntimeArchiveBuffer, LoadDynamicLibrary LoadDynLibrary, bool StaticVCRuntime=false, const char *VCRuntimePath=nullptr, std::optional&lt; SymbolAliasMap &gt; RuntimeAliases=std::nullopt)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Try to create a <a href="/web-llvm/docs/api/classes/llvm/orc/coffplatform">COFFPlatform</a> instance, adding the ORC runtime to the given <a href="/web-llvm/docs/api/classes/llvm/orc/jitdylib">JITDylib</a>. <a href="#a0ff140ec3eee8b9a860f3626b5640c04">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">static <a href="/web-llvm/docs/api/classes/llvm/expected">Expected</a>&lt; std::unique_ptr&lt; <a href="/web-llvm/docs/api/classes/llvm/orc/coffplatform">COFFPlatform</a> &gt; &gt;</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#aace1e8dbb3956766bdd52e5cac572da2">Create</a> (ObjectLinkingLayer &amp;ObjLinkingLayer, JITDylib &amp;PlatformJD, const char *OrcRuntimePath, LoadDynamicLibrary LoadDynLibrary, bool StaticVCRuntime=false, const char *VCRuntimePath=nullptr, std::optional&lt; SymbolAliasMap &gt; RuntimeAliases=std::nullopt)</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">static <a href="/web-llvm/docs/api/namespaces/llvm/orc/#adfa7bcc2544e48c4531ebfe74ae622b2">SymbolAliasMap</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a5d4cd708e7ef7878583300a0a5a3b0da">standardPlatformAliases</a> (ExecutionSession &amp;ES)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Returns an AliasMap containing the default aliases for the <a href="/web-llvm/docs/api/classes/llvm/orc/coffplatform">COFFPlatform</a>. <a href="#a5d4cd708e7ef7878583300a0a5a3b0da">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">static <a href="/web-llvm/docs/api/classes/llvm/arrayref">ArrayRef</a>&lt; std::pair&lt; <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> char *, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> char * &gt; &gt;</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a8dfa1ab7b14c67b662c7fe88fb2777c6">requiredCXXAliases</a> ()</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Returns the array of required CXX aliases. <a href="#a8dfa1ab7b14c67b662c7fe88fb2777c6">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">static <a href="/web-llvm/docs/api/classes/llvm/arrayref">ArrayRef</a>&lt; std::pair&lt; <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> char *, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> char * &gt; &gt;</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a1476ba35d3f457e40a40863d139bf614">standardRuntimeUtilityAliases</a> ()</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Returns the array of standard runtime utility aliases for <a href="/web-llvm/docs/api/namespaces/llvm/coff">COFF</a>. <a href="#a1476ba35d3f457e40a40863d139bf614">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">static <a href="/web-llvm/docs/api/classes/llvm/stringref">StringRef</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a38f3464b16783a25413f7c9b9a604a4e">getSEHFrameSectionName</a> ()</td>
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

## Private Static Functions Index

<table class="doxyMembersIndex">

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">static bool</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#aab13abb650bc0afdc3442d5020534a24">supportedTarget</a> (const Triple &amp;TT)</td>
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

<p>Mediates between <a href="/web-llvm/docs/api/namespaces/llvm/coff">COFF</a> initialization and <a href="/web-llvm/docs/api/classes/llvm/orc/executionsession">ExecutionSession</a> state.</p>

<p>Definition at line 34 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/executionengine/include/llvm/executionengine/orc/coffplatform-h">COFFPlatform.h</a>.</p>


<div class="doxySectionDef">

## Public Member Typedefs

### LoadDynamicLibrary {#a12da434b55a741dcb040e17d487bdf39}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">using llvm::orc::COFFPlatform::LoadDynamicLibrary = 
      unique_function&lt;Error(JITDylib &amp;JD, StringRef DLLFileName)&gt;</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>A function that will be called with the name of dll file that must be loaded.</p>

<p>Definition at line 38 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/executionengine/include/llvm/executionengine/orc/coffplatform-h">COFFPlatform.h</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Private Member Typedefs

### COFFJITDylibDepInfo {#a769773f069e99a3e132676e003836fcf}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">using llvm::orc::COFFPlatform::COFFJITDylibDepInfo =  std::vector&lt;ExecutorAddr&gt;</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 80 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/executionengine/include/llvm/executionengine/orc/coffplatform-h">COFFPlatform.h</a>.</p>

</div>
</div>

### COFFJITDylibDepInfoMap {#a73f0f8d09158e4cd7a9e9487ebd5b627}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">using llvm::orc::COFFPlatform::COFFJITDylibDepInfoMap = 
      std::vector&lt;std::pair&lt;ExecutorAddr, COFFJITDylibDepInfo&gt;&gt;</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 81 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/executionengine/include/llvm/executionengine/orc/coffplatform-h">COFFPlatform.h</a>.</p>

</div>
</div>

### COFFObjectSectionsMap {#a96dc06160ce7b2622f193378e38f37ba}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">using llvm::orc::COFFPlatform::COFFObjectSectionsMap = 
      SmallVector&lt;std::pair&lt;std::string, ExecutorAddrRange&gt;&gt;</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 83 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/executionengine/include/llvm/executionengine/orc/coffplatform-h">COFFPlatform.h</a>.</p>

</div>
</div>

### JITDylibDepMap {#af75024abd739e62b9fefac901fe9ce9b}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">using llvm::orc::COFFPlatform::JITDylibDepMap =  DenseMap&lt;JITDylib *, SmallVector&lt;JITDylib *&gt;&gt;</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 88 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/executionengine/include/llvm/executionengine/orc/coffplatform-h">COFFPlatform.h</a>.</p>

</div>
</div>

### PushInitializersSendResultFn {#a66fc265c8cca531b589aa7daaad87d2a}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">using llvm::orc::COFFPlatform::PushInitializersSendResultFn = 
      unique_function&lt;void(Expected&lt;COFFJITDylibDepInfoMap&gt;)&gt;</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 85 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/executionengine/include/llvm/executionengine/orc/coffplatform-h">COFFPlatform.h</a>.</p>

</div>
</div>

### SendSymbolAddressFn {#aa5ba42befb40bed5291995b897e1a01e}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">using llvm::orc::COFFPlatform::SendSymbolAddressFn =  unique_function&lt;void(Expected&lt;ExecutorAddr&gt;)&gt;</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 87 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/executionengine/include/llvm/executionengine/orc/coffplatform-h">COFFPlatform.h</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Private Constructors

### COFFPlatform() {#a739d08c4e28997315ad0902f855138bd}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">llvm::orc::COFFPlatform::COFFPlatform (<a href="/web-llvm/docs/api/classes/llvm/orc/objectlinkinglayer">ObjectLinkingLayer</a> &amp; ObjLinkingLayer, <a href="/web-llvm/docs/api/classes/llvm/orc/jitdylib">JITDylib</a> &amp; PlatformJD, std::unique_ptr&lt; <a href="/web-llvm/docs/api/classes/llvm/orc/staticlibrarydefinitiongenerator">StaticLibraryDefinitionGenerator</a> &gt; OrcRuntimeGenerator, std::unique_ptr&lt; <a href="/web-llvm/docs/api/classes/llvm/memorybuffer">MemoryBuffer</a> &gt; OrcRuntimeArchiveBuffer, std::unique_ptr&lt; <a href="/web-llvm/docs/api/classes/llvm/object/archive">object::Archive</a> &gt; OrcRuntimeArchive, <a href="#a12da434b55a741dcb040e17d487bdf39">LoadDynamicLibrary</a> LoadDynLibrary, bool StaticVCRuntime, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> char * VCRuntimePath, <a href="/web-llvm/docs/api/classes/llvm/error">Error</a> &amp; Err)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Declaration at line 139 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/executionengine/include/llvm/executionengine/orc/coffplatform-h">COFFPlatform.h</a>, definition at line 376 of file <a href="/web-llvm/docs/api/files/lib/lib/executionengine/lib/executionengine/orc/coffplatform-cpp">COFFPlatform.cpp</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Public Member Functions

### getExecutionSession() {#a939275744a267d0b0612f172a395ca69}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">ExecutionSession &amp; llvm::orc::COFFPlatform::getExecutionSession ()</td>
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



<p>Definition at line 56 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/executionengine/include/llvm/executionengine/orc/coffplatform-h">COFFPlatform.h</a>.</p>

</div>
</div>

### getObjectLinkingLayer() {#a3ef249d0da17f1dab6f8a7c53957b4e9}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">ObjectLinkingLayer &amp; llvm::orc::COFFPlatform::getObjectLinkingLayer ()</td>
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



<p>Definition at line 57 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/executionengine/include/llvm/executionengine/orc/coffplatform-h">COFFPlatform.h</a>.</p>

</div>
</div>

### notifyAdding() {#a6ceb8793145f063bcb5e204c1251649e}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">Error llvm::orc::COFFPlatform::notifyAdding (<a href="/web-llvm/docs/api/classes/llvm/orc/resourcetracker">ResourceTracker</a> &amp; RT, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/orc/materializationunit">MaterializationUnit</a> &amp; MU)</td>
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

<p>This method will be called under the <a href="/web-llvm/docs/api/classes/llvm/orc/executionsession">ExecutionSession</a> lock each time a <a href="/web-llvm/docs/api/classes/llvm/orc/materializationunit">MaterializationUnit</a> is added to a <a href="/web-llvm/docs/api/classes/llvm/orc/jitdylib">JITDylib</a>.</p>

<p>Declaration at line 61 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/executionengine/include/llvm/executionengine/orc/coffplatform-h">COFFPlatform.h</a>, definition at line 315 of file <a href="/web-llvm/docs/api/files/lib/lib/executionengine/lib/executionengine/orc/coffplatform-cpp">COFFPlatform.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/namespaces/llvm/#a7c46c742c31be54870e2038048e6b391">llvm::dbgs</a>, <a href="/web-llvm/docs/api/classes/llvm/orc/materializationunit/#a99d1933cb59ec5527b4c025ae7027216">llvm::orc::MaterializationUnit::getInitializerSymbol</a>, <a href="/web-llvm/docs/api/classes/llvm/orc/resourcetracker/#a19b2c478815e45a7c78615959f5450a2">llvm::orc::ResourceTracker::getJITDylib</a>, <a href="/web-llvm/docs/api/classes/llvm/orc/materializationunit/#a1c2e2986d77d9e3cc3d1c64e6e8f35ad">llvm::orc::MaterializationUnit::getName</a>, <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/support/debug-h/#a196897517069dda1bdb549e24468f7d7">LLVM_DEBUG</a>, <a href="/web-llvm/docs/api/classes/llvm/error/#a4dfd0813c3d0e0a30439b5a3e9196b59">llvm::Error::success</a> and <a href="/web-llvm/docs/api/namespaces/llvm/orc/#a69e9511c04540297d2cff38f4645a9aba26a03cdefe35519715a4b6d564c9c9c7">llvm::orc::WeaklyReferencedSymbol</a>.</p>

</div>
</div>

### notifyRemoving() {#ae9761095caf64ffbd3c599774a4dff4b}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">Error llvm::orc::COFFPlatform::notifyRemoving (<a href="/web-llvm/docs/api/classes/llvm/orc/resourcetracker">ResourceTracker</a> &amp; RT)</td>
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

<p>This method will be called under the <a href="/web-llvm/docs/api/classes/llvm/orc/executionsession">ExecutionSession</a> lock when a <a href="/web-llvm/docs/api/classes/llvm/orc/resourcetracker">ResourceTracker</a> is removed.</p>

<p>Declaration at line 63 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/executionengine/include/llvm/executionengine/orc/coffplatform-h">COFFPlatform.h</a>, definition at line 332 of file <a href="/web-llvm/docs/api/files/lib/lib/executionengine/lib/executionengine/orc/coffplatform-cpp">COFFPlatform.cpp</a>.</p>


<p>Reference <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/support/errorhandling-h/#ace243f5c25697a1107cce46626b3dc94">llvm_unreachable</a>.</p>

</div>
</div>

### setupJITDylib() {#a0cd59afcda8972c7ffd9254da83b7d70}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">Error llvm::orc::COFFPlatform::setupJITDylib (<a href="/web-llvm/docs/api/classes/llvm/orc/jitdylib">JITDylib</a> &amp; JD)</td>
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

<p>This method will be called outside the session lock each time a <a href="/web-llvm/docs/api/classes/llvm/orc/jitdylib">JITDylib</a> is created (unless it is created with EmptyJITDylib set) to allow the <a href="/web-llvm/docs/api/classes/llvm/orc/platform">Platform</a> to install any <a href="/web-llvm/docs/api/classes/llvm/orc/jitdylib">JITDylib</a> specific standard symbols (e.g __dso_handle).</p>

<p>Declaration at line 59 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/executionengine/include/llvm/executionengine/orc/coffplatform-h">COFFPlatform.h</a>, definition at line 259 of file <a href="/web-llvm/docs/api/files/lib/lib/executionengine/lib/executionengine/orc/coffplatform-cpp">COFFPlatform.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/namespaces/llvm/orc/#a82f74a53afe9225468960223f8d96c46">llvm::orc::addAliases</a>, <a href="/web-llvm/docs/api/classes/llvm/orc/jitdylib/#ae89dfebe97fc65907c1b9194aafe1ade">llvm::orc::JITDylib::addGenerator</a>, <a href="/web-llvm/docs/api/classes/llvm/orc/dllimportdefinitiongenerator/#a0a18ceb873894a966ded295537737261">llvm::orc::DLLImportDefinitionGenerator::Create</a>, <a href="/web-llvm/docs/api/classes/llvm/orc/jitdylib/#a5ec8631eb0c37168d6f85c4ecad77747">llvm::orc::JITDylib::define</a>, <a href="/web-llvm/docs/api/classes/llvm/memorybuffer/#a0f68098734d6d3b451aacf5b38a67131">llvm::MemoryBuffer::getMemBuffer</a>, <a href="/web-llvm/docs/api/namespaces/llvm/orc/#a94a67b1b1afd0088aecc47ddcc329096">llvm::orc::getObjectFileInterface</a>, <a href="/web-llvm/docs/api/files/lib/lib/support/md5-cpp/#ac0eafdc9ee161b71e7af98af736952fd">I</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a372f87e2cac1c83389c98554dc44806da043d23e54edc5360a7785ae212d1b806">llvm::Lib</a>, <a href="#a8dfa1ab7b14c67b662c7fe88fb2777c6">requiredCXXAliases</a>, <a href="/web-llvm/docs/api/classes/llvm/error/#a4dfd0813c3d0e0a30439b5a3e9196b59">llvm::Error::success</a> and <a href="/web-llvm/docs/api/namespaces/llvm/orc/#a2c212cdbe134087fcaa385aad1bc8a9e">llvm::orc::symbolAliases</a>.</p>

</div>
</div>

### teardownJITDylib() {#a1a257687b19260c45eb247fdf4e83af7}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">Error llvm::orc::COFFPlatform::teardownJITDylib (<a href="/web-llvm/docs/api/classes/llvm/orc/jitdylib">JITDylib</a> &amp; JD)</td>
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

<p>This method will be called outside the session lock each time a <a href="/web-llvm/docs/api/classes/llvm/orc/jitdylib">JITDylib</a> is removed to allow the <a href="/web-llvm/docs/api/classes/llvm/orc/platform">Platform</a> to remove any JITDylib-specific data.</p>

<p>Declaration at line 60 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/executionengine/include/llvm/executionengine/orc/coffplatform-h">COFFPlatform.h</a>, definition at line 303 of file <a href="/web-llvm/docs/api/files/lib/lib/executionengine/lib/executionengine/orc/coffplatform-cpp">COFFPlatform.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/silowercontrolflow-cpp/#a4868c5d81c5ccc98c47aeab6244346a0">assert</a>, <a href="/web-llvm/docs/api/files/lib/lib/support/md5-cpp/#ac0eafdc9ee161b71e7af98af736952fd">I</a> and <a href="/web-llvm/docs/api/classes/llvm/error/#a4dfd0813c3d0e0a30439b5a3e9196b59">llvm::Error::success</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Private Member Functions

### associateRuntimeSupportFunctions() {#ab33677c8adf9149cc0a6a03d7de301c3}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">Error llvm::orc::COFFPlatform::associateRuntimeSupportFunctions (<a href="/web-llvm/docs/api/classes/llvm/orc/jitdylib">JITDylib</a> &amp; PlatformJD)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Declaration at line 148 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/executionengine/include/llvm/executionengine/orc/coffplatform-h">COFFPlatform.h</a>, definition at line 632 of file <a href="/web-llvm/docs/api/files/lib/lib/executionengine/lib/executionengine/orc/coffplatform-cpp">COFFPlatform.cpp</a>.</p>

</div>
</div>

### bootstrapCOFFRuntime() {#a33419364943405307276ae8768e8e959}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">Error llvm::orc::COFFPlatform::bootstrapCOFFRuntime (<a href="/web-llvm/docs/api/classes/llvm/orc/jitdylib">JITDylib</a> &amp; PlatformJD)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Declaration at line 151 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/executionengine/include/llvm/executionengine/orc/coffplatform-h">COFFPlatform.h</a>, definition at line 678 of file <a href="/web-llvm/docs/api/files/lib/lib/executionengine/lib/executionengine/orc/coffplatform-cpp">COFFPlatform.cpp</a>.</p>

</div>
</div>

### buildJDDepMap() {#a747a7e1862342419045866aeb1d78ee2}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">Expected&lt; COFFPlatform::JITDylibDepMap &gt; llvm::orc::COFFPlatform::buildJDDepMap (<a href="/web-llvm/docs/api/classes/llvm/orc/jitdylib">JITDylib</a> &amp; JD)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Declaration at line 162 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/executionengine/include/llvm/executionengine/orc/coffplatform-h">COFFPlatform.h</a>, definition at line 458 of file <a href="/web-llvm/docs/api/files/lib/lib/executionengine/lib/executionengine/orc/coffplatform-cpp">COFFPlatform.cpp</a>.</p>

</div>
</div>

### getPerJDObjectFile() {#a775ecb0c769c0def7333729c8553e68d}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">Expected&lt; MemoryBufferRef &gt; llvm::orc::COFFPlatform::getPerJDObjectFile ()</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Declaration at line 164 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/executionengine/include/llvm/executionengine/orc/coffplatform-h">COFFPlatform.h</a>, definition at line 233 of file <a href="/web-llvm/docs/api/files/lib/lib/executionengine/lib/executionengine/orc/coffplatform-cpp">COFFPlatform.cpp</a>.</p>

</div>
</div>

### pushInitializersLoop() {#a57a08c86e6cea605831b27ea4b94bbd3}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void llvm::orc::COFFPlatform::pushInitializersLoop (<a href="/web-llvm/docs/api/classes/llvm/unique-function">PushInitializersSendResultFn</a> SendResult, <a href="/web-llvm/docs/api/namespaces/llvm/orc/#a1baadbec01aced37be13a1b86c76397e">JITDylibSP</a> JD, <a href="/web-llvm/docs/api/classes/llvm/densemap">JITDylibDepMap</a> &amp; JDDepMap)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Declaration at line 169 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/executionengine/include/llvm/executionengine/orc/coffplatform-h">COFFPlatform.h</a>, definition at line 498 of file <a href="/web-llvm/docs/api/files/lib/lib/executionengine/lib/executionengine/orc/coffplatform-cpp">COFFPlatform.cpp</a>.</p>

</div>
</div>

### rt\_lookupSymbol() {#a2f7fa97cd61d30ddb82a2355317c084f}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void llvm::orc::COFFPlatform::rt_lookupSymbol (<a href="/web-llvm/docs/api/classes/llvm/unique-function">SendSymbolAddressFn</a> SendResult, <a href="/web-llvm/docs/api/classes/llvm/orc/executoraddr">ExecutorAddr</a> Handle, <a href="/web-llvm/docs/api/classes/llvm/stringref">StringRef</a> SymbolName)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Declaration at line 175 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/executionengine/include/llvm/executionengine/orc/coffplatform-h">COFFPlatform.h</a>, definition at line 587 of file <a href="/web-llvm/docs/api/files/lib/lib/executionengine/lib/executionengine/orc/coffplatform-cpp">COFFPlatform.cpp</a>.</p>

</div>
</div>

### rt\_pushInitializers() {#a0c0d40c096e1a2642ec9abd738ce01b8}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void llvm::orc::COFFPlatform::rt_pushInitializers (<a href="/web-llvm/docs/api/classes/llvm/unique-function">PushInitializersSendResultFn</a> SendResult, <a href="/web-llvm/docs/api/classes/llvm/orc/executoraddr">ExecutorAddr</a> JDHeaderAddr)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Declaration at line 172 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/executionengine/include/llvm/executionengine/orc/coffplatform-h">COFFPlatform.h</a>, definition at line 553 of file <a href="/web-llvm/docs/api/files/lib/lib/executionengine/lib/executionengine/orc/coffplatform-cpp">COFFPlatform.cpp</a>.</p>

</div>
</div>

### runBootstrapInitializers() {#acbf7639a33dfdf03271bdffe816938bf}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">Error llvm::orc::COFFPlatform::runBootstrapInitializers (JDBootstrapState &amp; BState)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Declaration at line 157 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/executionengine/include/llvm/executionengine/orc/coffplatform-h">COFFPlatform.h</a>, definition at line 649 of file <a href="/web-llvm/docs/api/files/lib/lib/executionengine/lib/executionengine/orc/coffplatform-cpp">COFFPlatform.cpp</a>.</p>

</div>
</div>

### runBootstrapSubsectionInitializers() {#a526745454f3eb70d09c34bc6f2f5c879}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">Error llvm::orc::COFFPlatform::runBootstrapSubsectionInitializers (JDBootstrapState &amp; BState, <a href="/web-llvm/docs/api/classes/llvm/stringref">StringRef</a> Start, <a href="/web-llvm/docs/api/classes/llvm/stringref">StringRef</a> End)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Declaration at line 158 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/executionengine/include/llvm/executionengine/orc/coffplatform-h">COFFPlatform.h</a>, definition at line 664 of file <a href="/web-llvm/docs/api/files/lib/lib/executionengine/lib/executionengine/orc/coffplatform-cpp">COFFPlatform.cpp</a>.</p>

</div>
</div>

### runSymbolIfExists() {#a440c4484aeec945aa93e0cd312d73a81}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">Error llvm::orc::COFFPlatform::runSymbolIfExists (<a href="/web-llvm/docs/api/classes/llvm/orc/jitdylib">JITDylib</a> &amp; PlatformJD, <a href="/web-llvm/docs/api/classes/llvm/stringref">StringRef</a> SymbolName)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Declaration at line 154 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/executionengine/include/llvm/executionengine/orc/coffplatform-h">COFFPlatform.h</a>, definition at line 730 of file <a href="/web-llvm/docs/api/files/lib/lib/executionengine/lib/executionengine/orc/coffplatform-cpp">COFFPlatform.cpp</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Private Member Attributes

### Bootstrapping {#a28b7358c14fd9d99b0074ccb3e67e019}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">std::atomic&lt;bool&gt; llvm::orc::COFFPlatform::Bootstrapping</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 191 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/executionengine/include/llvm/executionengine/orc/coffplatform-h">COFFPlatform.h</a>.</p>

</div>
</div>

### COFFHeaderStartSymbol {#a057557e17e83ae5e1b91a10b78182405}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">SymbolStringPtr llvm::orc::COFFPlatform::COFFHeaderStartSymbol</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 187 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/executionengine/include/llvm/executionengine/orc/coffplatform-h">COFFPlatform.h</a>.</p>

</div>
</div>

### DylibsToPreload {#abcda8ae14ed5587ca145d07bb445f6cc}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">std::set&lt;std::string&gt; llvm::orc::COFFPlatform::DylibsToPreload</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 205 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/executionengine/include/llvm/executionengine/orc/coffplatform-h">COFFPlatform.h</a>.</p>

</div>
</div>

### ES {#a8c90f6ac4fdcef58ba62f300623c4965}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">ExecutionSession&amp; llvm::orc::COFFPlatform::ES</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 178 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/executionengine/include/llvm/executionengine/orc/coffplatform-h">COFFPlatform.h</a>.</p>

</div>
</div>

### HeaderAddrToJITDylib {#a486e4d67f57cf69bc736c35950eb595e}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">DenseMap&lt;ExecutorAddr, JITDylib *&gt; llvm::orc::COFFPlatform::HeaderAddrToJITDylib</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 201 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/executionengine/include/llvm/executionengine/orc/coffplatform-h">COFFPlatform.h</a>.</p>

</div>
</div>

### JDBootstrapStates {#a231085975b152ae86716eb62b70c16d2}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">std::map&lt;JITDylib *, JDBootstrapState&gt; llvm::orc::COFFPlatform::JDBootstrapStates</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 190 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/executionengine/include/llvm/executionengine/orc/coffplatform-h">COFFPlatform.h</a>.</p>

</div>
</div>

### JITDylibToHeaderAddr {#a3f9ff60adff7f5dc919046af6928c2b8}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">DenseMap&lt;JITDylib *, ExecutorAddr&gt; llvm::orc::COFFPlatform::JITDylibToHeaderAddr</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 200 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/executionengine/include/llvm/executionengine/orc/coffplatform-h">COFFPlatform.h</a>.</p>

</div>
</div>

### LoadDynLibrary {#a9ed1841e88fdeed4ac4c1a9e8804cd47}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">LoadDynamicLibrary llvm::orc::COFFPlatform::LoadDynLibrary</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 181 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/executionengine/include/llvm/executionengine/orc/coffplatform-h">COFFPlatform.h</a>.</p>

</div>
</div>

### ObjLinkingLayer {#a2e43c1df5a54b7439f8e1ac20c21cb89}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">ObjectLinkingLayer&amp; llvm::orc::COFFPlatform::ObjLinkingLayer</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 179 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/executionengine/include/llvm/executionengine/orc/coffplatform-h">COFFPlatform.h</a>.</p>

</div>
</div>

### orc\_rt\_coff\_deregister\_jitdylib {#a16f87774aee0bbf4275a9eb30f2d9cef}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">ExecutorAddr llvm::orc::COFFPlatform::orc_rt_coff_deregister_jitdylib</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 198 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/executionengine/include/llvm/executionengine/orc/coffplatform-h">COFFPlatform.h</a>.</p>

</div>
</div>

### orc\_rt\_coff\_deregister\_object\_sections {#a345a905bb996df8aa2d37f917321d2cd}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">ExecutorAddr llvm::orc::COFFPlatform::orc_rt_coff_deregister_object_sections</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 196 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/executionengine/include/llvm/executionengine/orc/coffplatform-h">COFFPlatform.h</a>.</p>

</div>
</div>

### orc\_rt\_coff\_platform\_bootstrap {#a3a5000929702fd4314bdfa0be9dbddf4}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">ExecutorAddr llvm::orc::COFFPlatform::orc_rt_coff_platform_bootstrap</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 193 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/executionengine/include/llvm/executionengine/orc/coffplatform-h">COFFPlatform.h</a>.</p>

</div>
</div>

### orc\_rt\_coff\_platform\_shutdown {#a3d1e218441d505e2e6f0e3e5a271dd66}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">ExecutorAddr llvm::orc::COFFPlatform::orc_rt_coff_platform_shutdown</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 194 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/executionengine/include/llvm/executionengine/orc/coffplatform-h">COFFPlatform.h</a>.</p>

</div>
</div>

### orc\_rt\_coff\_register\_jitdylib {#aff34c21a33089f0144b90ad1444360de}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">ExecutorAddr llvm::orc::COFFPlatform::orc_rt_coff_register_jitdylib</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 197 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/executionengine/include/llvm/executionengine/orc/coffplatform-h">COFFPlatform.h</a>.</p>

</div>
</div>

### orc\_rt\_coff\_register\_object\_sections {#a3b6560535e4842884d7159beac68d692}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">ExecutorAddr llvm::orc::COFFPlatform::orc_rt_coff_register_object_sections</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 195 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/executionengine/include/llvm/executionengine/orc/coffplatform-h">COFFPlatform.h</a>.</p>

</div>
</div>

### OrcRuntimeArchive {#a58d43b8daea9a1167e26dbb71b604496}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">std::unique_ptr&lt;object::Archive&gt; llvm::orc::COFFPlatform::OrcRuntimeArchive</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 184 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/executionengine/include/llvm/executionengine/orc/coffplatform-h">COFFPlatform.h</a>.</p>

</div>
</div>

### OrcRuntimeArchiveBuffer {#a1c044115512bde6ad4b83ea5ac9afe9e}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">std::unique_ptr&lt;MemoryBuffer&gt; llvm::orc::COFFPlatform::OrcRuntimeArchiveBuffer</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 183 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/executionengine/include/llvm/executionengine/orc/coffplatform-h">COFFPlatform.h</a>.</p>

</div>
</div>

### PlatformMutex {#a81f207065861800d6b332a31410ae7ca}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">std::mutex llvm::orc::COFFPlatform::PlatformMutex</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 207 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/executionengine/include/llvm/executionengine/orc/coffplatform-h">COFFPlatform.h</a>.</p>

</div>
</div>

### RegisteredInitSymbols {#aec55b13893610c89843b9478948b8f03}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">DenseMap&lt;JITDylib *, SymbolLookupSet&gt; llvm::orc::COFFPlatform::RegisteredInitSymbols</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 203 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/executionengine/include/llvm/executionengine/orc/coffplatform-h">COFFPlatform.h</a>.</p>

</div>
</div>

### StaticVCRuntime {#adb3d7d6c25b3a54dd784cb02c1d31438}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool llvm::orc::COFFPlatform::StaticVCRuntime</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 185 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/executionengine/include/llvm/executionengine/orc/coffplatform-h">COFFPlatform.h</a>.</p>

</div>
</div>

### VCRuntimeBootstrap {#a22d0cc8c4fad6f874da6dc970ef96093}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">std::unique_ptr&lt;COFFVCRuntimeBootstrapper&gt; llvm::orc::COFFPlatform::VCRuntimeBootstrap</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 182 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/executionengine/include/llvm/executionengine/orc/coffplatform-h">COFFPlatform.h</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Public Static Functions

### Create() {#a0ff140ec3eee8b9a860f3626b5640c04}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">Expected&lt; std::unique_ptr&lt; COFFPlatform &gt; &gt; llvm::orc::COFFPlatform::Create (<a href="/web-llvm/docs/api/classes/llvm/orc/objectlinkinglayer">ObjectLinkingLayer</a> &amp; ObjLinkingLayer, <a href="/web-llvm/docs/api/classes/llvm/orc/jitdylib">JITDylib</a> &amp; PlatformJD, std::unique_ptr&lt; <a href="/web-llvm/docs/api/classes/llvm/memorybuffer">MemoryBuffer</a> &gt; OrcRuntimeArchiveBuffer, <a href="#a12da434b55a741dcb040e17d487bdf39">LoadDynamicLibrary</a> LoadDynLibrary, bool StaticVCRuntime=false, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> char * VCRuntimePath=nullptr, std::optional&lt; <a href="/web-llvm/docs/api/namespaces/llvm/orc/#adfa7bcc2544e48c4531ebfe74ae622b2">SymbolAliasMap</a> &gt; RuntimeAliases=std::nullopt)</td>
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

<p>Try to create a <a href="/web-llvm/docs/api/classes/llvm/orc/coffplatform">COFFPlatform</a> instance, adding the ORC runtime to the given <a href="/web-llvm/docs/api/classes/llvm/orc/jitdylib">JITDylib</a>.</p>

<p>Declaration at line 44 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/executionengine/include/llvm/executionengine/orc/coffplatform-h">COFFPlatform.h</a>, definition at line 152 of file <a href="/web-llvm/docs/api/files/lib/lib/executionengine/lib/executionengine/orc/coffplatform-cpp">COFFPlatform.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/namespaces/llvm/orc/#a3a6ca0ed8ac3267e0579452013a2e82d">llvm::orc::absoluteSymbols</a>, <a href="/web-llvm/docs/api/classes/llvm/orc/jitdylib/#a6dfad3bd64c32a0f80f488fee7f637de">llvm::orc::JITDylib::addToLinkOrder</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#aa1e1474f15df639f0d874b21f15666f7">llvm::cantFail</a>, <a href="/web-llvm/docs/api/classes/llvm/orc/staticlibrarydefinitiongenerator/#a6e910497d88200a16108f6849b074ab8">llvm::orc::StaticLibraryDefinitionGenerator::Create</a>, <a href="/web-llvm/docs/api/classes/llvm/object/archive/#afff545dbbc7e3d85c4e6d914200747db">llvm::object::Archive::create</a>, <a href="/web-llvm/docs/api/classes/llvm/orc/jitdylib/#a5ec8631eb0c37168d6f85c4ecad77747">llvm::orc::JITDylib::define</a>, <a href="/web-llvm/docs/api/classes/llvm/jitsymbolflags/#ad509c6d010720c4f71aeac1fba93f8cbaeb59403a31ee3f63734a411e9e42ddd8">llvm::JITSymbolFlags::Exported</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a2b43c21951d0948b34bcf7019949032d">llvm::inconvertibleErrorCode</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a9999bd897fc8a1648bd69b36fee2d357">llvm::make_error</a>, <a href="/web-llvm/docs/api/files/lib/lib/option/option-cpp/#a04665169063c8ca1f2ea96c27fc7c2b2">P</a>, <a href="#a5d4cd708e7ef7878583300a0a5a3b0da">standardPlatformAliases</a>, <a href="/web-llvm/docs/api/classes/llvm/error/#a4dfd0813c3d0e0a30439b5a3e9196b59">llvm::Error::success</a> and <a href="/web-llvm/docs/api/namespaces/llvm/orc/#a2c212cdbe134087fcaa385aad1bc8a9e">llvm::orc::symbolAliases</a>.</p>


<p>Referenced by <a href="#aace1e8dbb3956766bdd52e5cac572da2">Create</a> and <a href="/web-llvm/docs/api/classes/llvm/orc/executornativeplatform/#aa1bd92add845031ceeaab24c2c25c275">llvm::orc::ExecutorNativePlatform::operator()</a>.</p>

</div>
</div>

### Create() {#aace1e8dbb3956766bdd52e5cac572da2}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">Expected&lt; std::unique_ptr&lt; COFFPlatform &gt; &gt; llvm::orc::COFFPlatform::Create (<a href="/web-llvm/docs/api/classes/llvm/orc/objectlinkinglayer">ObjectLinkingLayer</a> &amp; ObjLinkingLayer, <a href="/web-llvm/docs/api/classes/llvm/orc/jitdylib">JITDylib</a> &amp; PlatformJD, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> char * OrcRuntimePath, <a href="#a12da434b55a741dcb040e17d487bdf39">LoadDynamicLibrary</a> LoadDynLibrary, bool StaticVCRuntime=false, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> char * VCRuntimePath=nullptr, std::optional&lt; <a href="/web-llvm/docs/api/namespaces/llvm/orc/#adfa7bcc2544e48c4531ebfe74ae622b2">SymbolAliasMap</a> &gt; RuntimeAliases=std::nullopt)</td>
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



<p>Declaration at line 51 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/executionengine/include/llvm/executionengine/orc/coffplatform-h">COFFPlatform.h</a>, definition at line 218 of file <a href="/web-llvm/docs/api/files/lib/lib/executionengine/lib/executionengine/orc/coffplatform-cpp">COFFPlatform.cpp</a>.</p>


<p>References <a href="#a0ff140ec3eee8b9a860f3626b5640c04">Create</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a0f4ffaa2f15fc8f612a233e3b45510c0">llvm::createFileError</a> and <a href="/web-llvm/docs/api/classes/llvm/memorybuffer/#aa98611beefe78f907beeee7305cc8174">llvm::MemoryBuffer::getFile</a>.</p>

</div>
</div>

### getSEHFrameSectionName() {#a38f3464b16783a25413f7c9b9a604a4e}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">StringRef llvm::orc::COFFPlatform::getSEHFrameSectionName ()</td>
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



<p>Definition at line 77 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/executionengine/include/llvm/executionengine/orc/coffplatform-h">COFFPlatform.h</a>.</p>

</div>
</div>

### requiredCXXAliases() {#a8dfa1ab7b14c67b662c7fe88fb2777c6}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">ArrayRef&lt; std::pair&lt; const char *, const char * &gt; &gt; llvm::orc::COFFPlatform::requiredCXXAliases ()</td>
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

<p>Returns the array of required CXX aliases.</p>

<p>Declaration at line 71 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/executionengine/include/llvm/executionengine/orc/coffplatform-h">COFFPlatform.h</a>, definition at line 343 of file <a href="/web-llvm/docs/api/files/lib/lib/executionengine/lib/executionengine/orc/coffplatform-cpp">COFFPlatform.cpp</a>.</p>


<p>Referenced by <a href="#a0cd59afcda8972c7ffd9254da83b7d70">setupJITDylib</a>.</p>

</div>
</div>

### standardPlatformAliases() {#a5d4cd708e7ef7878583300a0a5a3b0da}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">SymbolAliasMap llvm::orc::COFFPlatform::standardPlatformAliases (<a href="/web-llvm/docs/api/classes/llvm/orc/executionsession">ExecutionSession</a> &amp; ES)</td>
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

<p>Returns an AliasMap containing the default aliases for the <a href="/web-llvm/docs/api/classes/llvm/orc/coffplatform">COFFPlatform</a>.</p>


<p>This can be modified by clients when constructing the platform to add or remove aliases.</p>


<p>Declaration at line 68 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/executionengine/include/llvm/executionengine/orc/coffplatform-h">COFFPlatform.h</a>, definition at line 336 of file <a href="/web-llvm/docs/api/files/lib/lib/executionengine/lib/executionengine/orc/coffplatform-cpp">COFFPlatform.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/namespaces/llvm/orc/#a82f74a53afe9225468960223f8d96c46">llvm::orc::addAliases</a> and <a href="#a1476ba35d3f457e40a40863d139bf614">standardRuntimeUtilityAliases</a>.</p>


<p>Referenced by <a href="#a0ff140ec3eee8b9a860f3626b5640c04">Create</a>.</p>

</div>
</div>

### standardRuntimeUtilityAliases() {#a1476ba35d3f457e40a40863d139bf614}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">ArrayRef&lt; std::pair&lt; const char *, const char * &gt; &gt; llvm::orc::COFFPlatform::standardRuntimeUtilityAliases ()</td>
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

<p>Returns the array of standard runtime utility aliases for <a href="/web-llvm/docs/api/namespaces/llvm/coff">COFF</a>.</p>

<p>Declaration at line 75 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/executionengine/include/llvm/executionengine/orc/coffplatform-h">COFFPlatform.h</a>, definition at line 353 of file <a href="/web-llvm/docs/api/files/lib/lib/executionengine/lib/executionengine/orc/coffplatform-cpp">COFFPlatform.cpp</a>.</p>


<p>Referenced by <a href="#a5d4cd708e7ef7878583300a0a5a3b0da">standardPlatformAliases</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Private Static Functions

### supportedTarget() {#aab13abb650bc0afdc3442d5020534a24}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool llvm::orc::COFFPlatform::supportedTarget (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/triple">Triple</a> &amp; TT)</td>
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



<p>Declaration at line 137 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/executionengine/include/llvm/executionengine/orc/coffplatform-h">COFFPlatform.h</a>, definition at line 367 of file <a href="/web-llvm/docs/api/files/lib/lib/executionengine/lib/executionengine/orc/coffplatform-cpp">COFFPlatform.cpp</a>.</p>

</div>
</div>

</div>

<hr/>

The documentation for this class was generated from the following files:

<ul>
<li><a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/executionengine/include/llvm/executionengine/orc/coffplatform-h">COFFPlatform.h</a></li>
<li><a href="/web-llvm/docs/api/files/lib/lib/executionengine/lib/executionengine/orc/coffplatform-cpp">COFFPlatform.cpp</a></li>
</ul>

<hr/>

<p class="doxyGeneratedBy">Generated via <a href="https://github.com/xpack/doxygen2docusaurus">doxygen2docusaurus</a> by <a href="https://www.doxygen.nl">Doxygen</a> 1.15.0.</p>

</div>
