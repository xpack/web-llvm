---

# DO NOT EDIT!
# Automatically generated via doxygen2docusaurus by Doxygen.

slug: /api/classes/llvm/orc/machoplatform
custom_edit_url: null
toc_max_heading_level: 4
keywords:
  - doxygen
  - reference
  - class

---

<div class="doxyPage">

# The `MachOPlatform` Class Reference

<p>Mediates between <a href="/web-llvm/docs/api/namespaces/llvm/macho">MachO</a> initialization and <a href="/web-llvm/docs/api/classes/llvm/orc/executionsession">ExecutionSession</a> state. <a href="#details">More...</a></p>

## Declaration

<div class="doxyDeclaration">
class llvm::orc::MachOPlatform { ... }
</div>

## Included Headers

<div class="doxyIncludesList">#include "<a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/executionengine/include/llvm/executionengine/orc/machoplatform-h">llvm/ExecutionEngine/Orc/MachOPlatform.h</a>"
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a770d73acb401c9ed0ed6b16272aa4050">MachOJITDylibDepInfoMap</a> = std::vector&lt; std::pair&lt; <a href="/web-llvm/docs/api/classes/llvm/orc/executoraddr">ExecutorAddr</a>, <a href="/web-llvm/docs/api/structs/llvm/orc/machoplatform/machojitdylibdepinfo">MachOJITDylibDepInfo</a> &gt; &gt;</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a93b754ab1a755ecf25e98f2bea459d8d">MachOHeaderMUBuilder</a> = <a href="/web-llvm/docs/api/classes/llvm/unique-function">unique_function</a>&lt; std::unique_ptr&lt; <a href="/web-llvm/docs/api/classes/llvm/orc/materializationunit">MaterializationUnit</a> &gt;(<a href="/web-llvm/docs/api/classes/llvm/orc/machoplatform">MachOPlatform</a> &amp;MOP, <a href="/web-llvm/docs/api/structs/llvm/orc/machoplatform/headeroptions">HeaderOptions</a> Opts)&gt;</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Used by setupJITDylib to create <a href="/web-llvm/docs/api/namespaces/llvm/macho">MachO</a> header MaterializationUnits for JITDylibs. <a href="#a93b754ab1a755ecf25e98f2bea459d8d">More...</a></p>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a6f940849fa868c06ae19d660ddc29f00">SymbolTableVector</a> = <a href="/web-llvm/docs/api/classes/llvm/smallvector">SmallVector</a>&lt; std::tuple&lt; <a href="/web-llvm/docs/api/classes/llvm/orc/executoraddr">ExecutorAddr</a>, <a href="/web-llvm/docs/api/classes/llvm/orc/executoraddr">ExecutorAddr</a>, <a href="#a0fd90f53b4f2a866cffe1bbd54be93ba">MachOExecutorSymbolFlags</a> &gt; &gt;</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a031eb0731dbdc11f0819c99ca5a224ed">GetJITDylibHeaderSendResultFn</a> = <a href="/web-llvm/docs/api/classes/llvm/unique-function">unique_function</a>&lt; void(<a href="/web-llvm/docs/api/classes/llvm/expected">Expected</a>&lt; <a href="/web-llvm/docs/api/classes/llvm/orc/executoraddr">ExecutorAddr</a> &gt;)&gt;</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#acb4e0fede6431746ef387cce55174e4b">GetJITDylibNameSendResultFn</a> = <a href="/web-llvm/docs/api/classes/llvm/unique-function">unique_function</a>&lt; void(<a href="/web-llvm/docs/api/classes/llvm/expected">Expected</a>&lt; <a href="/web-llvm/docs/api/classes/llvm/stringref">StringRef</a> &gt;)&gt;</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a049d88db8b8c6139a2b6e22b25a446a5">PushInitializersSendResultFn</a> = <a href="/web-llvm/docs/api/classes/llvm/unique-function">unique_function</a>&lt; void(<a href="/web-llvm/docs/api/classes/llvm/expected">Expected</a>&lt; <a href="#a770d73acb401c9ed0ed6b16272aa4050">MachOJITDylibDepInfoMap</a> &gt;)&gt;</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a3827ef14f27e73ba0230b0070aa155fb">SendSymbolAddressFn</a> = <a href="/web-llvm/docs/api/classes/llvm/unique-function">unique_function</a>&lt; void(<a href="/web-llvm/docs/api/classes/llvm/expected">Expected</a>&lt; <a href="/web-llvm/docs/api/classes/llvm/orc/executoraddr">ExecutorAddr</a> &gt;)&gt;</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ac8694415b66355a2fff841e6a3399c1d">PushSymbolsInSendResultFn</a> = <a href="/web-llvm/docs/api/classes/llvm/unique-function">unique_function</a>&lt; void(<a href="/web-llvm/docs/api/classes/llvm/error">Error</a>)&gt;</td>
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

## Enumerations Index

<table class="doxyMembersIndex">

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">enum class</td>
<td class="doxyMemberIndexItemName" align="left" valign="top">MachOExecutorSymbolFlags : uint8_t { <a href="#a0fd90f53b4f2a866cffe1bbd54be93ba">...</a> }</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a4297b32d58300729e5b0b21de250e415">MachOPlatform</a> (ObjectLinkingLayer &amp;ObjLinkingLayer, JITDylib &amp;PlatformJD, std::unique_ptr&lt; DefinitionGenerator &gt; OrcRuntimeGenerator, HeaderOptions PlatformJDOpts, MachOHeaderMUBuilder BuildMachOHeaderMU, Error &amp;Err)</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ab2d022e73bf8373d324c1b989c57074f">getExecutionSession</a> () const</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a0b6c5f7bc389c9247771b1642410352e">getObjectLinkingLayer</a> () const</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/orc/nonowningsymbolstringptr">NonOwningSymbolStringPtr</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a1e54bdbfb200dbbd195008fa638d154a">getMachOHeaderStartSymbol</a> () const</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a45fd41e11f6881253372745d7927cd52">setupJITDylib</a> (JITDylib &amp;JD) override</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>This method will be called outside the session lock each time a <a href="/web-llvm/docs/api/classes/llvm/orc/jitdylib">JITDylib</a> is created (unless it is created with EmptyJITDylib set) to allow the <a href="/web-llvm/docs/api/classes/llvm/orc/platform">Platform</a> to install any <a href="/web-llvm/docs/api/classes/llvm/orc/jitdylib">JITDylib</a> specific standard symbols (e.g __dso_handle). <a href="#a45fd41e11f6881253372745d7927cd52">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/error">Error</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a8be40bff13ac5d492bc1e7179ce12046">setupJITDylib</a> (JITDylib &amp;JD, HeaderOptions Opts)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Install any platform-specific symbols (e.g. <a href="#a8be40bff13ac5d492bc1e7179ce12046">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/error">Error</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a2410f51d9f312b025f9a3307f63c7f6e">teardownJITDylib</a> (JITDylib &amp;JD) override</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>This method will be called outside the session lock each time a <a href="/web-llvm/docs/api/classes/llvm/orc/jitdylib">JITDylib</a> is removed to allow the <a href="/web-llvm/docs/api/classes/llvm/orc/platform">Platform</a> to remove any JITDylib-specific data. <a href="#a2410f51d9f312b025f9a3307f63c7f6e">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/error">Error</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a9933be5a0082912958e7328de0ca90e1">notifyAdding</a> (ResourceTracker &amp;RT, const MaterializationUnit &amp;MU) override</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>This method will be called under the <a href="/web-llvm/docs/api/classes/llvm/orc/executionsession">ExecutionSession</a> lock each time a <a href="/web-llvm/docs/api/classes/llvm/orc/materializationunit">MaterializationUnit</a> is added to a <a href="/web-llvm/docs/api/classes/llvm/orc/jitdylib">JITDylib</a>. <a href="#a9933be5a0082912958e7328de0ca90e1">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/error">Error</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ab3516e13e87d0b4a374fad5b5ff22b05">notifyRemoving</a> (ResourceTracker &amp;RT) override</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>This method will be called under the <a href="/web-llvm/docs/api/classes/llvm/orc/executionsession">ExecutionSession</a> lock when a <a href="/web-llvm/docs/api/classes/llvm/orc/resourcetracker">ResourceTracker</a> is removed. <a href="#ab3516e13e87d0b4a374fad5b5ff22b05">More...</a></p>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a18de895712b320493315a686ee523cdc">associateRuntimeSupportFunctions</a> ()</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#aaef0a534624b9da460a9c5f5e3e33bc0">pushInitializersLoop</a> (PushInitializersSendResultFn SendResult, JITDylibSP JD)</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ab13c0cccbb9a329f1ff11caffae1faef">rt_pushInitializers</a> (PushInitializersSendResultFn SendResult, ExecutorAddr JDHeaderAddr)</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#acc7532ba128265dc45bdfdf3e51ee613">rt_pushSymbols</a> (PushSymbolsInSendResultFn SendResult, ExecutorAddr Handle, const std::vector&lt; std::pair&lt; StringRef, bool &gt; &gt; &amp;Symbols)</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/expected">Expected</a>&lt; uint64_t &gt;</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a5b1f2a231d4623bfd2d51f182d42dfb9">createPThreadKey</a> ()</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ab39a0edd4fcacc2ebcfd36ba0edd753b">ES</a></td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/orc/jitdylib">JITDylib</a> &amp;</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a48694a6b455662fdecac8bd1b6137826">PlatformJD</a></td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a917039f581ceb3c620ac061caf670439">ObjLinkingLayer</a></td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="#a93b754ab1a755ecf25e98f2bea459d8d">MachOHeaderMUBuilder</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a8039d4b520fbf64f6e46ff35a9257151">BuildMachOHeaderMU</a></td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a72b7e37fa5425894e9922653a6197689">MachOHeaderStartSymbol</a> = ES.intern("___dso_handle")</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">RuntimeFunction</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#aafedf866d8c9272604ee8efb1c21e808">PlatformBootstrap</a> = ...</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">RuntimeFunction</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a5c1711fa7d5a92381f88d3a2e78fcff3">PlatformShutdown</a> = ...</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">RuntimeFunction</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ac5c7627613e80f4d73ef1b30a3096f45">RegisterEHFrameSection</a> = ...</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">RuntimeFunction</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a4c9c00d88289a6245270d5b6c787d79d">DeregisterEHFrameSection</a> = ...</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">RuntimeFunction</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#afe45e15a78759534c64d693e2d3e1dfc">RegisterJITDylib</a> = ...</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">RuntimeFunction</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a414795804483258cb2c6fac97dd7325c">DeregisterJITDylib</a> = ...</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">RuntimeFunction</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#aa22203c97eb1b4b5963b119c17f80f01">RegisterObjectSymbolTable</a> = ...</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">RuntimeFunction</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a444581fce3271fab8f2f79994f222c9b">DeregisterObjectSymbolTable</a> = ...</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">RuntimeFunction</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a3bdb5572b0ba558c8b8e58056130188d">RegisterObjectPlatformSections</a> = ...</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">RuntimeFunction</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a9a9bdf7ca13bd87781a302c09b3aec37">DeregisterObjectPlatformSections</a> = ...</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">RuntimeFunction</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a83542a9b15f4858faf09fb212b92e5f6">CreatePThreadKey</a> = ...</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">RuntimeFunction</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a9b7383aad0063bb463ed9c287b33259d">RegisterObjCRuntimeObject</a> = ...</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">RuntimeFunction</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a94f567a49e0f8c1ab2c48d4941c19722">DeregisterObjCRuntimeObject</a> = ...</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ad19d903a51c897944c3b7be83ac434b0">RegisteredInitSymbols</a></td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ac1cbe24b81a9791070732dfd9d2c87ea">PlatformMutex</a></td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a40d506be0d455e57f1f895fc1eb28ce2">ForceEHFrames</a> = false</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">BootstrapInfo *</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a48e9d9194bc57222fa6b9960973e084a">Bootstrap</a> = nullptr</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#aba8b1e73aceb71252adac1510f61fa41">JITDylibToHeaderAddr</a></td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#abd44c5d6cecb38ecc95ad4d70f39b157">HeaderAddrToJITDylib</a></td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/densemap">DenseMap</a>&lt; <a href="/web-llvm/docs/api/classes/llvm/orc/jitdylib">JITDylib</a> *, uint64_t &gt;</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a2e16344024bad553941930ee5ef5bda3">JITDylibToPThreadKey</a></td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">static std::unique_ptr&lt; <a href="/web-llvm/docs/api/classes/llvm/orc/materializationunit">MaterializationUnit</a> &gt;</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a49136cf1b05dde0d5cea41910deb238e">buildSimpleMachOHeaderMU</a> (MachOPlatform &amp;MOP, HeaderOptions Opts)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Simple <a href="/web-llvm/docs/api/namespaces/llvm/macho">MachO</a> header graph builder. <a href="#a49136cf1b05dde0d5cea41910deb238e">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">static <a href="/web-llvm/docs/api/classes/llvm/expected">Expected</a>&lt; std::unique_ptr&lt; <a href="/web-llvm/docs/api/classes/llvm/orc/machoplatform">MachOPlatform</a> &gt; &gt;</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ad166f5736231229286c93cd8c6aa8b6d">Create</a> (ObjectLinkingLayer &amp;ObjLinkingLayer, JITDylib &amp;PlatformJD, std::unique_ptr&lt; DefinitionGenerator &gt; OrcRuntime, HeaderOptions PlatformJDOpts={}, MachOHeaderMUBuilder BuildMachOHeaderMU=buildSimpleMachOHeaderMU, std::optional&lt; SymbolAliasMap &gt; RuntimeAliases=std::nullopt)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Try to create a <a href="/web-llvm/docs/api/classes/llvm/orc/machoplatform">MachOPlatform</a> instance, adding the ORC runtime to the given <a href="/web-llvm/docs/api/classes/llvm/orc/jitdylib">JITDylib</a>. <a href="#ad166f5736231229286c93cd8c6aa8b6d">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">static <a href="/web-llvm/docs/api/classes/llvm/expected">Expected</a>&lt; std::unique_ptr&lt; <a href="/web-llvm/docs/api/classes/llvm/orc/machoplatform">MachOPlatform</a> &gt; &gt;</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a1d471ce68684309b46d6afa43f8ec0a9">Create</a> (ObjectLinkingLayer &amp;ObjLinkingLayer, JITDylib &amp;PlatformJD, const char *OrcRuntimePath, HeaderOptions PlatformJDOpts={}, MachOHeaderMUBuilder BuildMachOHeaderMU=buildSimpleMachOHeaderMU, std::optional&lt; SymbolAliasMap &gt; RuntimeAliases=std::nullopt)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Construct using a path to the ORC runtime. <a href="#a1d471ce68684309b46d6afa43f8ec0a9">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">static <a href="/web-llvm/docs/api/namespaces/llvm/orc/#adfa7bcc2544e48c4531ebfe74ae622b2">SymbolAliasMap</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ab2b75dd698cda0452b5e84199248ca8a">standardPlatformAliases</a> (ExecutionSession &amp;ES)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Returns an AliasMap containing the default aliases for the <a href="/web-llvm/docs/api/classes/llvm/orc/machoplatform">MachOPlatform</a>. <a href="#ab2b75dd698cda0452b5e84199248ca8a">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">static <a href="/web-llvm/docs/api/classes/llvm/arrayref">ArrayRef</a>&lt; std::pair&lt; <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> char *, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> char * &gt; &gt;</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#afa832afa22d43b07518adfe5bae7c816">requiredCXXAliases</a> ()</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Returns the array of required CXX aliases. <a href="#afa832afa22d43b07518adfe5bae7c816">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">static <a href="/web-llvm/docs/api/classes/llvm/arrayref">ArrayRef</a>&lt; std::pair&lt; <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> char *, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> char * &gt; &gt;</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a5033eefe5c3bcf123e9d3070884f38f5">standardRuntimeUtilityAliases</a> ()</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Returns the array of standard runtime utility aliases for <a href="/web-llvm/docs/api/namespaces/llvm/macho">MachO</a>. <a href="#a5033eefe5c3bcf123e9d3070884f38f5">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">static <a href="/web-llvm/docs/api/classes/llvm/arrayref">ArrayRef</a>&lt; std::pair&lt; <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> char *, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> char * &gt; &gt;</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a25ec836178bfbac963e0945c6e0cdb75">standardLazyCompilationAliases</a> ()</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Returns a list of aliases required to enable lazy compilation via the ORC runtime. <a href="#a25ec836178bfbac963e0945c6e0cdb75">More...</a></p>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#afc346fc9cb8bf6dd068a52409381ff46">supportedTarget</a> (const Triple &amp;TT)</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">static <a href="/web-llvm/docs/api/classes/llvm/jitlink/edge/#af18145da213e6c4033b368d657e80baa">jitlink::Edge::Kind</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a2de04c95b174adde918039416aab6716">getPointerEdgeKind</a> (jitlink::LinkGraph &amp;G)</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">static <a href="#a0fd90f53b4f2a866cffe1bbd54be93ba">MachOExecutorSymbolFlags</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ace8d0e493303fca2cbb2548b6add121d">flagsForSymbol</a> (jitlink::Symbol &amp;Sym)</td>
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

<p>Mediates between <a href="/web-llvm/docs/api/namespaces/llvm/macho">MachO</a> initialization and <a href="/web-llvm/docs/api/classes/llvm/orc/executionsession">ExecutionSession</a> state.</p>

<p>Definition at line 30 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/executionengine/include/llvm/executionengine/orc/machoplatform-h">MachOPlatform.h</a>.</p>


<div class="doxySectionDef">

## Public Member Typedefs

### MachOHeaderMUBuilder {#a93b754ab1a755ecf25e98f2bea459d8d}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">using llvm::orc::MachOPlatform::MachOHeaderMUBuilder = 
      unique_function&lt;std::unique_ptr&lt;MaterializationUnit&gt;(MachOPlatform &amp;MOP,
                                                           HeaderOptions Opts)&gt;</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Used by setupJITDylib to create <a href="/web-llvm/docs/api/namespaces/llvm/macho">MachO</a> header MaterializationUnits for JITDylibs.</p>

<p>Definition at line 89 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/executionengine/include/llvm/executionengine/orc/machoplatform-h">MachOPlatform.h</a>.</p>

</div>
</div>

### MachOJITDylibDepInfoMap {#a770d73acb401c9ed0ed6b16272aa4050}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">using llvm::orc::MachOPlatform::MachOJITDylibDepInfoMap = 
      std::vector&lt;std::pair&lt;ExecutorAddr, MachOJITDylibDepInfo&gt;&gt;</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 39 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/executionengine/include/llvm/executionengine/orc/machoplatform-h">MachOPlatform.h</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Private Member Typedefs

### GetJITDylibHeaderSendResultFn {#a031eb0731dbdc11f0819c99ca5a224ed}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">using llvm::orc::MachOPlatform::GetJITDylibHeaderSendResultFn = 
      unique_function&lt;void(Expected&lt;ExecutorAddr&gt;)&gt;</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 285 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/executionengine/include/llvm/executionengine/orc/machoplatform-h">MachOPlatform.h</a>.</p>

</div>
</div>

### GetJITDylibNameSendResultFn {#acb4e0fede6431746ef387cce55174e4b}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">using llvm::orc::MachOPlatform::GetJITDylibNameSendResultFn = 
      unique_function&lt;void(Expected&lt;StringRef&gt;)&gt;</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 287 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/executionengine/include/llvm/executionengine/orc/machoplatform-h">MachOPlatform.h</a>.</p>

</div>
</div>

### PushInitializersSendResultFn {#a049d88db8b8c6139a2b6e22b25a446a5}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">using llvm::orc::MachOPlatform::PushInitializersSendResultFn = 
      unique_function&lt;void(Expected&lt;MachOJITDylibDepInfoMap&gt;)&gt;</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 289 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/executionengine/include/llvm/executionengine/orc/machoplatform-h">MachOPlatform.h</a>.</p>

</div>
</div>

### PushSymbolsInSendResultFn {#ac8694415b66355a2fff841e6a3399c1d}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">using llvm::orc::MachOPlatform::PushSymbolsInSendResultFn =  unique_function&lt;void(Error)&gt;</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 292 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/executionengine/include/llvm/executionengine/orc/machoplatform-h">MachOPlatform.h</a>.</p>

</div>
</div>

### SendSymbolAddressFn {#a3827ef14f27e73ba0230b0070aa155fb}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">using llvm::orc::MachOPlatform::SendSymbolAddressFn =  unique_function&lt;void(Expected&lt;ExecutorAddr&gt;)&gt;</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 291 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/executionengine/include/llvm/executionengine/orc/machoplatform-h">MachOPlatform.h</a>.</p>

</div>
</div>

### SymbolTableVector {#a6f940849fa868c06ae19d660ddc29f00}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">using llvm::orc::MachOPlatform::SymbolTableVector =  SmallVector&lt;
      std::tuple&lt;ExecutorAddr, ExecutorAddr, MachOExecutorSymbolFlags&gt;&gt;</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 185 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/executionengine/include/llvm/executionengine/orc/machoplatform-h">MachOPlatform.h</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Enumerations

### MachOExecutorSymbolFlags {#a0fd90f53b4f2a866cffe1bbd54be93ba}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">enum class llvm::orc::MachOPlatform::MachOExecutorSymbolFlags : uint8_t</td>
</tr>
</table>
</td>
<td class="doxyMemberLabelsRight">
<span class="doxyMemberLabels">
<span class="doxyMemberLabel strong">strong</span>
</span>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">


<dl class="doxyEnumList">
<dt class="doxyEnumTableTitle">Enumeration values</dt>
<dd>
<table class="doxyEnumTable">

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">None<a id="a0fd90f53b4f2a866cffe1bbd54be93baa6adf97f83acf6453d4a6a4b1070f3754"></a></td>
<td class="doxyEnumItemDescription"> (= 0)</td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">Weak<a id="a0fd90f53b4f2a866cffe1bbd54be93baa7324e3727807d95037eb19d304fd91ec"></a></td>
<td class="doxyEnumItemDescription"> (= 1U &lt;&lt; 0)</td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">Callable<a id="a0fd90f53b4f2a866cffe1bbd54be93baa79ace5b2a7206c5d0aa286a5b33385f8"></a></td>
<td class="doxyEnumItemDescription"> (= 1U &lt;&lt; 1)</td>
</tr>

</table>
</dd>
</dl>

<p>Definition at line 43 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/executionengine/include/llvm/executionengine/orc/machoplatform-h">MachOPlatform.h</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Private Constructors

### MachOPlatform() {#a4297b32d58300729e5b0b21de250e415}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">llvm::orc::MachOPlatform::MachOPlatform (<a href="/web-llvm/docs/api/classes/llvm/orc/objectlinkinglayer">ObjectLinkingLayer</a> &amp; ObjLinkingLayer, <a href="/web-llvm/docs/api/classes/llvm/orc/jitdylib">JITDylib</a> &amp; PlatformJD, std::unique_ptr&lt; <a href="/web-llvm/docs/api/classes/llvm/orc/definitiongenerator">DefinitionGenerator</a> &gt; OrcRuntimeGenerator, <a href="/web-llvm/docs/api/structs/llvm/orc/machoplatform/headeroptions">HeaderOptions</a> PlatformJDOpts, <a href="#a93b754ab1a755ecf25e98f2bea459d8d">MachOHeaderMUBuilder</a> BuildMachOHeaderMU, <a href="/web-llvm/docs/api/classes/llvm/error">Error</a> &amp; Err)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Declaration at line 300 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/executionengine/include/llvm/executionengine/orc/machoplatform-h">MachOPlatform.h</a>, definition at line 472 of file <a href="/web-llvm/docs/api/files/lib/lib/executionengine/lib/executionengine/orc/machoplatform-cpp">MachOPlatform.cpp</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Public Member Functions

### getExecutionSession() {#ab2d022e73bf8373d324c1b989c57074f}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">ExecutionSession &amp; llvm::orc::MachOPlatform::getExecutionSession ()</td>
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



<p>Definition at line 149 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/executionengine/include/llvm/executionengine/orc/machoplatform-h">MachOPlatform.h</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/namespaces/llvm/orc/#ab3b175f40b07ac581cc42fc835420d25">llvm::orc::createHeaderBlock</a> and <a href="/web-llvm/docs/api/namespaces/anonymous-machoplatform-cpp-/#aef4e166e503c258a5488943077a4239c">anonymous{MachOPlatform.cpp}::createPlatformGraph</a>.</p>

</div>
</div>

### getMachOHeaderStartSymbol() {#a1e54bdbfb200dbbd195008fa638d154a}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">NonOwningSymbolStringPtr llvm::orc::MachOPlatform::getMachOHeaderStartSymbol ()</td>
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



<p>Definition at line 152 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/executionengine/include/llvm/executionengine/orc/machoplatform-h">MachOPlatform.h</a>.</p>

</div>
</div>

### getObjectLinkingLayer() {#a0b6c5f7bc389c9247771b1642410352e}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">ObjectLinkingLayer &amp; llvm::orc::MachOPlatform::getObjectLinkingLayer ()</td>
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



<p>Definition at line 150 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/executionengine/include/llvm/executionengine/orc/machoplatform-h">MachOPlatform.h</a>.</p>

</div>
</div>

### notifyAdding() {#a9933be5a0082912958e7328de0ca90e1}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">Error llvm::orc::MachOPlatform::notifyAdding (<a href="/web-llvm/docs/api/classes/llvm/orc/resourcetracker">ResourceTracker</a> &amp; RT, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/orc/materializationunit">MaterializationUnit</a> &amp; MU)</td>
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

<p>Declaration at line 163 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/executionengine/include/llvm/executionengine/orc/machoplatform-h">MachOPlatform.h</a>, definition at line 366 of file <a href="/web-llvm/docs/api/files/lib/lib/executionengine/lib/executionengine/orc/machoplatform-cpp">MachOPlatform.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/namespaces/llvm/#a7c46c742c31be54870e2038048e6b391">llvm::dbgs</a>, <a href="/web-llvm/docs/api/classes/llvm/orc/materializationunit/#a99d1933cb59ec5527b4c025ae7027216">llvm::orc::MaterializationUnit::getInitializerSymbol</a>, <a href="/web-llvm/docs/api/classes/llvm/orc/resourcetracker/#a19b2c478815e45a7c78615959f5450a2">llvm::orc::ResourceTracker::getJITDylib</a>, <a href="/web-llvm/docs/api/classes/llvm/orc/materializationunit/#a1c2e2986d77d9e3cc3d1c64e6e8f35ad">llvm::orc::MaterializationUnit::getName</a>, <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/support/debug-h/#a196897517069dda1bdb549e24468f7d7">LLVM_DEBUG</a>, <a href="/web-llvm/docs/api/classes/llvm/error/#a4dfd0813c3d0e0a30439b5a3e9196b59">llvm::Error::success</a> and <a href="/web-llvm/docs/api/namespaces/llvm/orc/#a69e9511c04540297d2cff38f4645a9aba26a03cdefe35519715a4b6d564c9c9c7">llvm::orc::WeaklyReferencedSymbol</a>.</p>

</div>
</div>

### notifyRemoving() {#ab3516e13e87d0b4a374fad5b5ff22b05}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">Error llvm::orc::MachOPlatform::notifyRemoving (<a href="/web-llvm/docs/api/classes/llvm/orc/resourcetracker">ResourceTracker</a> &amp; RT)</td>
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

<p>Declaration at line 165 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/executionengine/include/llvm/executionengine/orc/machoplatform-h">MachOPlatform.h</a>, definition at line 382 of file <a href="/web-llvm/docs/api/files/lib/lib/executionengine/lib/executionengine/orc/machoplatform-cpp">MachOPlatform.cpp</a>.</p>


<p>Reference <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/support/errorhandling-h/#ace243f5c25697a1107cce46626b3dc94">llvm_unreachable</a>.</p>

</div>
</div>

### setupJITDylib() {#a45fd41e11f6881253372745d7927cd52}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">Error llvm::orc::MachOPlatform::setupJITDylib (<a href="/web-llvm/docs/api/classes/llvm/orc/jitdylib">JITDylib</a> &amp; JD)</td>
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

<p>Declaration at line 156 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/executionengine/include/llvm/executionengine/orc/machoplatform-h">MachOPlatform.h</a>, definition at line 342 of file <a href="/web-llvm/docs/api/files/lib/lib/executionengine/lib/executionengine/orc/machoplatform-cpp">MachOPlatform.cpp</a>.</p>


<p>Reference <a href="#a45fd41e11f6881253372745d7927cd52">setupJITDylib</a>.</p>


<p>Referenced by <a href="#a45fd41e11f6881253372745d7927cd52">setupJITDylib</a>.</p>

</div>
</div>

### setupJITDylib() {#a8be40bff13ac5d492bc1e7179ce12046}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">Error llvm::orc::MachOPlatform::setupJITDylib (<a href="/web-llvm/docs/api/classes/llvm/orc/jitdylib">JITDylib</a> &amp; JD, <a href="/web-llvm/docs/api/structs/llvm/orc/machoplatform/headeroptions">HeaderOptions</a> Opts)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Install any platform-specific symbols (e.g.</p>


<p><span class="doxyComputerOutput">__dso_handle</span>) and create a mach-o header based on the given options.</p>


<p>Declaration at line 160 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/executionengine/include/llvm/executionengine/orc/machoplatform-h">MachOPlatform.h</a>, definition at line 346 of file <a href="/web-llvm/docs/api/files/lib/lib/executionengine/lib/executionengine/orc/machoplatform-cpp">MachOPlatform.cpp</a>.</p>


<p>Reference <a href="/web-llvm/docs/api/classes/llvm/orc/jitdylib/#a5ec8631eb0c37168d6f85c4ecad77747">llvm::orc::JITDylib::define</a>.</p>

</div>
</div>

### teardownJITDylib() {#a2410f51d9f312b025f9a3307f63c7f6e}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">Error llvm::orc::MachOPlatform::teardownJITDylib (<a href="/web-llvm/docs/api/classes/llvm/orc/jitdylib">JITDylib</a> &amp; JD)</td>
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

<p>Declaration at line 162 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/executionengine/include/llvm/executionengine/orc/machoplatform-h">MachOPlatform.h</a>, definition at line 353 of file <a href="/web-llvm/docs/api/files/lib/lib/executionengine/lib/executionengine/orc/machoplatform-cpp">MachOPlatform.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/silowercontrolflow-cpp/#a4868c5d81c5ccc98c47aeab6244346a0">assert</a>, <a href="/web-llvm/docs/api/files/lib/lib/support/md5-cpp/#ac0eafdc9ee161b71e7af98af736952fd">I</a> and <a href="/web-llvm/docs/api/classes/llvm/error/#a4dfd0813c3d0e0a30439b5a3e9196b59">llvm::Error::success</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Private Member Functions

### associateRuntimeSupportFunctions() {#a18de895712b320493315a686ee523cdc}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">Error llvm::orc::MachOPlatform::associateRuntimeSupportFunctions ()</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Declaration at line 306 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/executionengine/include/llvm/executionengine/orc/machoplatform-h">MachOPlatform.h</a>, definition at line 606 of file <a href="/web-llvm/docs/api/files/lib/lib/executionengine/lib/executionengine/orc/machoplatform-cpp">MachOPlatform.cpp</a>.</p>

</div>
</div>

### createPThreadKey() {#a5b1f2a231d4623bfd2d51f182d42dfb9}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">Expected&lt; uint64_t &gt; llvm::orc::MachOPlatform::createPThreadKey ()</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Declaration at line 326 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/executionengine/include/llvm/executionengine/orc/machoplatform-h">MachOPlatform.h</a>, definition at line 785 of file <a href="/web-llvm/docs/api/files/lib/lib/executionengine/lib/executionengine/orc/machoplatform-cpp">MachOPlatform.cpp</a>.</p>

</div>
</div>

### pushInitializersLoop() {#aaef0a534624b9da460a9c5f5e3e33bc0}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void llvm::orc::MachOPlatform::pushInitializersLoop (<a href="/web-llvm/docs/api/classes/llvm/unique-function">PushInitializersSendResultFn</a> SendResult, <a href="/web-llvm/docs/api/namespaces/llvm/orc/#a1baadbec01aced37be13a1b86c76397e">JITDylibSP</a> JD)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Declaration at line 311 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/executionengine/include/llvm/executionengine/orc/machoplatform-h">MachOPlatform.h</a>, definition at line 624 of file <a href="/web-llvm/docs/api/files/lib/lib/executionengine/lib/executionengine/orc/machoplatform-cpp">MachOPlatform.cpp</a>.</p>

</div>
</div>

### rt\_pushInitializers() {#ab13c0cccbb9a329f1ff11caffae1faef}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void llvm::orc::MachOPlatform::rt_pushInitializers (<a href="/web-llvm/docs/api/classes/llvm/unique-function">PushInitializersSendResultFn</a> SendResult, <a href="/web-llvm/docs/api/classes/llvm/orc/executoraddr">ExecutorAddr</a> JDHeaderAddr)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Declaration at line 315 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/executionengine/include/llvm/executionengine/orc/machoplatform-h">MachOPlatform.h</a>, definition at line 712 of file <a href="/web-llvm/docs/api/files/lib/lib/executionengine/lib/executionengine/orc/machoplatform-cpp">MachOPlatform.cpp</a>.</p>

</div>
</div>

### rt\_pushSymbols() {#acc7532ba128265dc45bdfdf3e51ee613}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void llvm::orc::MachOPlatform::rt_pushSymbols (<a href="/web-llvm/docs/api/classes/llvm/unique-function">PushSymbolsInSendResultFn</a> SendResult, <a href="/web-llvm/docs/api/classes/llvm/orc/executoraddr">ExecutorAddr</a> Handle, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> std::vector&lt; std::pair&lt; <a href="/web-llvm/docs/api/classes/llvm/stringref">StringRef</a>, bool &gt; &gt; &amp; Symbols)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Declaration at line 322 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/executionengine/include/llvm/executionengine/orc/machoplatform-h">MachOPlatform.h</a>, definition at line 740 of file <a href="/web-llvm/docs/api/files/lib/lib/executionengine/lib/executionengine/orc/machoplatform-cpp">MachOPlatform.cpp</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Private Member Attributes

### Bootstrap {#a48e9d9194bc57222fa6b9960973e084a}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">BootstrapInfo* llvm::orc::MachOPlatform::Bootstrap = nullptr</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 372 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/executionengine/include/llvm/executionengine/orc/machoplatform-h">MachOPlatform.h</a>.</p>

</div>
</div>

### BuildMachOHeaderMU {#a8039d4b520fbf64f6e46ff35a9257151}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">MachOHeaderMUBuilder llvm::orc::MachOPlatform::BuildMachOHeaderMU</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 331 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/executionengine/include/llvm/executionengine/orc/machoplatform-h">MachOPlatform.h</a>.</p>

</div>
</div>

### CreatePThreadKey {#a83542a9b15f4858faf09fb212b92e5f6}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">RuntimeFunction llvm::orc::MachOPlatform::CreatePThreadKey</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<dl class="doxySectionUser">
<dt>Initialiser</dt>
<dd>
<div class="doxyVerbatim">{
      ES.intern("___orc_rt_macho_create_pthread_key")}
</div>
</dd>
</dl>

<p>Definition at line 361 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/executionengine/include/llvm/executionengine/orc/machoplatform-h">MachOPlatform.h</a>.</p>

</div>
</div>

### DeregisterEHFrameSection {#a4c9c00d88289a6245270d5b6c787d79d}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">RuntimeFunction llvm::orc::MachOPlatform::DeregisterEHFrameSection</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<dl class="doxySectionUser">
<dt>Initialiser</dt>
<dd>
<div class="doxyVerbatim">{
      ES.intern("___orc_rt_macho_deregister_ehframe_section")}
</div>
</dd>
</dl>

<p>Definition at line 347 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/executionengine/include/llvm/executionengine/orc/machoplatform-h">MachOPlatform.h</a>.</p>

</div>
</div>

### DeregisterJITDylib {#a414795804483258cb2c6fac97dd7325c}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">RuntimeFunction llvm::orc::MachOPlatform::DeregisterJITDylib</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<dl class="doxySectionUser">
<dt>Initialiser</dt>
<dd>
<div class="doxyVerbatim">{
      ES.intern("___orc_rt_macho_deregister_jitdylib")}
</div>
</dd>
</dl>

<p>Definition at line 351 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/executionengine/include/llvm/executionengine/orc/machoplatform-h">MachOPlatform.h</a>.</p>

</div>
</div>

### DeregisterObjCRuntimeObject {#a94f567a49e0f8c1ab2c48d4941c19722}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">RuntimeFunction llvm::orc::MachOPlatform::DeregisterObjCRuntimeObject</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<dl class="doxySectionUser">
<dt>Initialiser</dt>
<dd>
<div class="doxyVerbatim">{
      ES.intern("___orc_rt_macho_deregister_objc_runtime_object")}
</div>
</dd>
</dl>

<p>Definition at line 365 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/executionengine/include/llvm/executionengine/orc/machoplatform-h">MachOPlatform.h</a>.</p>

</div>
</div>

### DeregisterObjectPlatformSections {#a9a9bdf7ca13bd87781a302c09b3aec37}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">RuntimeFunction llvm::orc::MachOPlatform::DeregisterObjectPlatformSections</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<dl class="doxySectionUser">
<dt>Initialiser</dt>
<dd>
<div class="doxyVerbatim">{
      ES.intern("___orc_rt_macho_deregister_object_platform_sections")}
</div>
</dd>
</dl>

<p>Definition at line 359 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/executionengine/include/llvm/executionengine/orc/machoplatform-h">MachOPlatform.h</a>.</p>

</div>
</div>

### DeregisterObjectSymbolTable {#a444581fce3271fab8f2f79994f222c9b}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">RuntimeFunction llvm::orc::MachOPlatform::DeregisterObjectSymbolTable</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<dl class="doxySectionUser">
<dt>Initialiser</dt>
<dd>
<div class="doxyVerbatim">{
      ES.intern("___orc_rt_macho_deregister_object_symbol_table")}
</div>
</dd>
</dl>

<p>Definition at line 355 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/executionengine/include/llvm/executionengine/orc/machoplatform-h">MachOPlatform.h</a>.</p>

</div>
</div>

### ES {#ab39a0edd4fcacc2ebcfd36ba0edd753b}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">ExecutionSession&amp; llvm::orc::MachOPlatform::ES</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 328 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/executionengine/include/llvm/executionengine/orc/machoplatform-h">MachOPlatform.h</a>.</p>

</div>
</div>

### ForceEHFrames {#a40d506be0d455e57f1f895fc1eb28ce2}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool llvm::orc::MachOPlatform::ForceEHFrames = false</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 371 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/executionengine/include/llvm/executionengine/orc/machoplatform-h">MachOPlatform.h</a>.</p>

</div>
</div>

### HeaderAddrToJITDylib {#abd44c5d6cecb38ecc95ad4d70f39b157}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">DenseMap&lt;ExecutorAddr, JITDylib *&gt; llvm::orc::MachOPlatform::HeaderAddrToJITDylib</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 374 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/executionengine/include/llvm/executionengine/orc/machoplatform-h">MachOPlatform.h</a>.</p>

</div>
</div>

### JITDylibToHeaderAddr {#aba8b1e73aceb71252adac1510f61fa41}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">DenseMap&lt;JITDylib *, ExecutorAddr&gt; llvm::orc::MachOPlatform::JITDylibToHeaderAddr</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 373 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/executionengine/include/llvm/executionengine/orc/machoplatform-h">MachOPlatform.h</a>.</p>

</div>
</div>

### JITDylibToPThreadKey {#a2e16344024bad553941930ee5ef5bda3}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">DenseMap&lt;JITDylib *, uint64_t&gt; llvm::orc::MachOPlatform::JITDylibToPThreadKey</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 375 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/executionengine/include/llvm/executionengine/orc/machoplatform-h">MachOPlatform.h</a>.</p>

</div>
</div>

### MachOHeaderStartSymbol {#a72b7e37fa5425894e9922653a6197689}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">SymbolStringPtr llvm::orc::MachOPlatform::MachOHeaderStartSymbol = ES.intern("___dso_handle")</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 333 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/executionengine/include/llvm/executionengine/orc/machoplatform-h">MachOPlatform.h</a>.</p>

</div>
</div>

### ObjLinkingLayer {#a917039f581ceb3c620ac061caf670439}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">ObjectLinkingLayer&amp; llvm::orc::MachOPlatform::ObjLinkingLayer</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 330 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/executionengine/include/llvm/executionengine/orc/machoplatform-h">MachOPlatform.h</a>.</p>

</div>
</div>

### PlatformBootstrap {#aafedf866d8c9272604ee8efb1c21e808}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">RuntimeFunction llvm::orc::MachOPlatform::PlatformBootstrap</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<dl class="doxySectionUser">
<dt>Initialiser</dt>
<dd>
<div class="doxyVerbatim">{
      ES.intern("___orc_rt_macho_platform_bootstrap")}
</div>
</dd>
</dl>

<p>Definition at line 341 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/executionengine/include/llvm/executionengine/orc/machoplatform-h">MachOPlatform.h</a>.</p>

</div>
</div>

### PlatformJD {#a48694a6b455662fdecac8bd1b6137826}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">JITDylib&amp; llvm::orc::MachOPlatform::PlatformJD</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 329 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/executionengine/include/llvm/executionengine/orc/machoplatform-h">MachOPlatform.h</a>.</p>

</div>
</div>

### PlatformMutex {#ac1cbe24b81a9791070732dfd9d2c87ea}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">std::mutex llvm::orc::MachOPlatform::PlatformMutex</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 370 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/executionengine/include/llvm/executionengine/orc/machoplatform-h">MachOPlatform.h</a>.</p>

</div>
</div>

### PlatformShutdown {#a5c1711fa7d5a92381f88d3a2e78fcff3}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">RuntimeFunction llvm::orc::MachOPlatform::PlatformShutdown</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<dl class="doxySectionUser">
<dt>Initialiser</dt>
<dd>
<div class="doxyVerbatim">{
      ES.intern("___orc_rt_macho_platform_shutdown")}
</div>
</dd>
</dl>

<p>Definition at line 343 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/executionengine/include/llvm/executionengine/orc/machoplatform-h">MachOPlatform.h</a>.</p>

</div>
</div>

### RegisteredInitSymbols {#ad19d903a51c897944c3b7be83ac434b0}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">DenseMap&lt;JITDylib *, SymbolLookupSet&gt; llvm::orc::MachOPlatform::RegisteredInitSymbols</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 368 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/executionengine/include/llvm/executionengine/orc/machoplatform-h">MachOPlatform.h</a>.</p>

</div>
</div>

### RegisterEHFrameSection {#ac5c7627613e80f4d73ef1b30a3096f45}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">RuntimeFunction llvm::orc::MachOPlatform::RegisterEHFrameSection</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<dl class="doxySectionUser">
<dt>Initialiser</dt>
<dd>
<div class="doxyVerbatim">{
      ES.intern("___orc_rt_macho_register_ehframe_section")}
</div>
</dd>
</dl>

<p>Definition at line 345 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/executionengine/include/llvm/executionengine/orc/machoplatform-h">MachOPlatform.h</a>.</p>

</div>
</div>

### RegisterJITDylib {#afe45e15a78759534c64d693e2d3e1dfc}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">RuntimeFunction llvm::orc::MachOPlatform::RegisterJITDylib</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<dl class="doxySectionUser">
<dt>Initialiser</dt>
<dd>
<div class="doxyVerbatim">{
      ES.intern("___orc_rt_macho_register_jitdylib")}
</div>
</dd>
</dl>

<p>Definition at line 349 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/executionengine/include/llvm/executionengine/orc/machoplatform-h">MachOPlatform.h</a>.</p>

</div>
</div>

### RegisterObjCRuntimeObject {#a9b7383aad0063bb463ed9c287b33259d}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">RuntimeFunction llvm::orc::MachOPlatform::RegisterObjCRuntimeObject</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<dl class="doxySectionUser">
<dt>Initialiser</dt>
<dd>
<div class="doxyVerbatim">{
      ES.intern("___orc_rt_macho_register_objc_runtime_object")}
</div>
</dd>
</dl>

<p>Definition at line 363 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/executionengine/include/llvm/executionengine/orc/machoplatform-h">MachOPlatform.h</a>.</p>

</div>
</div>

### RegisterObjectPlatformSections {#a3bdb5572b0ba558c8b8e58056130188d}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">RuntimeFunction llvm::orc::MachOPlatform::RegisterObjectPlatformSections</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<dl class="doxySectionUser">
<dt>Initialiser</dt>
<dd>
<div class="doxyVerbatim">{
      ES.intern("___orc_rt_macho_register_object_platform_sections")}
</div>
</dd>
</dl>

<p>Definition at line 357 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/executionengine/include/llvm/executionengine/orc/machoplatform-h">MachOPlatform.h</a>.</p>

</div>
</div>

### RegisterObjectSymbolTable {#aa22203c97eb1b4b5963b119c17f80f01}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">RuntimeFunction llvm::orc::MachOPlatform::RegisterObjectSymbolTable</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<dl class="doxySectionUser">
<dt>Initialiser</dt>
<dd>
<div class="doxyVerbatim">{
      ES.intern("___orc_rt_macho_register_object_symbol_table")}
</div>
</dd>
</dl>

<p>Definition at line 353 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/executionengine/include/llvm/executionengine/orc/machoplatform-h">MachOPlatform.h</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Public Static Functions

### buildSimpleMachOHeaderMU() {#a49136cf1b05dde0d5cea41910deb238e}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">std::unique_ptr&lt; MaterializationUnit &gt; llvm::orc::MachOPlatform::buildSimpleMachOHeaderMU (<a href="/web-llvm/docs/api/classes/llvm/orc/machoplatform">MachOPlatform</a> &amp; MOP, <a href="/web-llvm/docs/api/structs/llvm/orc/machoplatform/headeroptions">HeaderOptions</a> Opts)</td>
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

<p>Simple <a href="/web-llvm/docs/api/namespaces/llvm/macho">MachO</a> header graph builder.</p>

<p>Definition at line 95 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/executionengine/include/llvm/executionengine/orc/machoplatform-h">MachOPlatform.h</a>.</p>

</div>
</div>

### Create() {#ad166f5736231229286c93cd8c6aa8b6d}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">Expected&lt; std::unique_ptr&lt; MachOPlatform &gt; &gt; llvm::orc::MachOPlatform::Create (<a href="/web-llvm/docs/api/classes/llvm/orc/objectlinkinglayer">ObjectLinkingLayer</a> &amp; ObjLinkingLayer, <a href="/web-llvm/docs/api/classes/llvm/orc/jitdylib">JITDylib</a> &amp; PlatformJD, std::unique_ptr&lt; <a href="/web-llvm/docs/api/classes/llvm/orc/definitiongenerator">DefinitionGenerator</a> &gt; OrcRuntime, <a href="/web-llvm/docs/api/structs/llvm/orc/machoplatform/headeroptions">HeaderOptions</a> PlatformJDOpts={}, <a href="#a93b754ab1a755ecf25e98f2bea459d8d">MachOHeaderMUBuilder</a> BuildMachOHeaderMU=<a href="#a49136cf1b05dde0d5cea41910deb238e">buildSimpleMachOHeaderMU</a>, std::optional&lt; <a href="/web-llvm/docs/api/namespaces/llvm/orc/#adfa7bcc2544e48c4531ebfe74ae622b2">SymbolAliasMap</a> &gt; RuntimeAliases=std::nullopt)</td>
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

<p>Try to create a <a href="/web-llvm/docs/api/classes/llvm/orc/machoplatform">MachOPlatform</a> instance, adding the ORC runtime to the given <a href="/web-llvm/docs/api/classes/llvm/orc/jitdylib">JITDylib</a>.</p>


<p>The ORC runtime requires access to a number of symbols in libc++, and requires access to symbols in libobjc, and libswiftCore to support Objective-C and Swift code. It is up to the caller to ensure that the required symbols can be referenced by code added to PlatformJD. The standard way to achieve this is to first attach dynamic library search generators for either the given process, or for the specific required libraries, to PlatformJD, then to create the platform instance:</p>


<div class="doxyProgramListing">

<div class="doxyCodeLine"><span class="doxyNoLineNumber">&nbsp;</span><span class="doxyLineContent"><span class="doxyHighlightKeyword">auto</span><span class="doxyHighlight"> &amp;PlatformJD = ES.createBareJITDylib(</span><span class="doxyHighlightStringLiteral">"stdlib"</span><span class="doxyHighlight">);</span></span></div>
<div class="doxyCodeLine"><span class="doxyNoLineNumber">&nbsp;</span><span class="doxyLineContent"><span class="doxyHighlight">PlatformJD.addGenerator(</span></span></div>
<div class="doxyCodeLine"><span class="doxyNoLineNumber">&nbsp;</span><span class="doxyLineContent"><span class="doxyHighlight">  ExitOnErr(EPCDynamicLibrarySearchGenerator</span></span></div>
<div class="doxyCodeLine"><span class="doxyNoLineNumber">&nbsp;</span><span class="doxyLineContent"><span class="doxyHighlight">              ::GetForTargetProcess(EPC)));</span></span></div>
<div class="doxyCodeLine"><span class="doxyNoLineNumber">&nbsp;</span><span class="doxyLineContent"><span class="doxyHighlight">ES.setPlatform(</span></span></div>
<div class="doxyCodeLine"><span class="doxyNoLineNumber">&nbsp;</span><span class="doxyLineContent"><span class="doxyHighlight">  ExitOnErr(<a href="#ad166f5736231229286c93cd8c6aa8b6d">MachOPlatform::Create</a>(ES, ObjLayer, EPC, PlatformJD,</span></span></div>
<div class="doxyCodeLine"><span class="doxyNoLineNumber">&nbsp;</span><span class="doxyLineContent"><span class="doxyHighlight">                                  </span><span class="doxyHighlightStringLiteral">"/path/to/orc/runtime"</span><span class="doxyHighlight">)));</span></span></div>

</div>


<p>Alternatively, these symbols could be added to another <a href="/web-llvm/docs/api/classes/llvm/orc/jitdylib">JITDylib</a> that PlatformJD links against.</p>


<p>Clients are also responsible for ensuring that any JIT'd code that depends on runtime functions (including any code using TLV or static destructors) can reference the runtime symbols. This is usually achieved by linking any JITDylibs containing regular code against PlatformJD.</p>


<p>By default, <a href="/web-llvm/docs/api/classes/llvm/orc/machoplatform">MachOPlatform</a> will add the set of aliases returned by the standardPlatformAliases function. This includes both required aliases (e.g. __cxa_atexit -&gt; __orc_rt_macho_cxa_atexit for static destructor support), and optional aliases that provide JIT versions of common functions (e.g. dlopen -&gt; __orc_rt_macho_jit_dlopen). Clients can override these defaults by passing a non-None value for the RuntimeAliases function, in which case the client is responsible for setting up all aliases (including the required ones).</p>


<p>Declaration at line 136 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/executionengine/include/llvm/executionengine/orc/machoplatform-h">MachOPlatform.h</a>, definition at line 280 of file <a href="/web-llvm/docs/api/files/lib/lib/executionengine/lib/executionengine/orc/machoplatform-cpp">MachOPlatform.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/namespaces/llvm/orc/#a3a6ca0ed8ac3267e0579452013a2e82d">llvm::orc::absoluteSymbols</a>, <a href="/web-llvm/docs/api/classes/llvm/jitsymbolflags/#ad509c6d010720c4f71aeac1fba93f8cbaeb59403a31ee3f63734a411e9e42ddd8">llvm::JITSymbolFlags::Exported</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a2b43c21951d0948b34bcf7019949032d">llvm::inconvertibleErrorCode</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a9999bd897fc8a1648bd69b36fee2d357">llvm::make_error</a>, <a href="/web-llvm/docs/api/files/lib/lib/option/option-cpp/#a04665169063c8ca1f2ea96c27fc7c2b2">P</a>, <a href="#ab2b75dd698cda0452b5e84199248ca8a">standardPlatformAliases</a>, <a href="/web-llvm/docs/api/classes/llvm/error/#a4dfd0813c3d0e0a30439b5a3e9196b59">llvm::Error::success</a> and <a href="/web-llvm/docs/api/namespaces/llvm/orc/#a2c212cdbe134087fcaa385aad1bc8a9e">llvm::orc::symbolAliases</a>.</p>


<p>Referenced by <a href="#a1d471ce68684309b46d6afa43f8ec0a9">Create</a> and <a href="/web-llvm/docs/api/classes/llvm/orc/executornativeplatform/#aa1bd92add845031ceeaab24c2c25c275">llvm::orc::ExecutorNativePlatform::operator()</a>.</p>

</div>
</div>

### Create() {#a1d471ce68684309b46d6afa43f8ec0a9}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">Expected&lt; std::unique_ptr&lt; MachOPlatform &gt; &gt; llvm::orc::MachOPlatform::Create (<a href="/web-llvm/docs/api/classes/llvm/orc/objectlinkinglayer">ObjectLinkingLayer</a> &amp; ObjLinkingLayer, <a href="/web-llvm/docs/api/classes/llvm/orc/jitdylib">JITDylib</a> &amp; PlatformJD, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> char * OrcRuntimePath, <a href="/web-llvm/docs/api/structs/llvm/orc/machoplatform/headeroptions">HeaderOptions</a> PlatformJDOpts={}, <a href="#a93b754ab1a755ecf25e98f2bea459d8d">MachOHeaderMUBuilder</a> BuildMachOHeaderMU=<a href="#a49136cf1b05dde0d5cea41910deb238e">buildSimpleMachOHeaderMU</a>, std::optional&lt; <a href="/web-llvm/docs/api/namespaces/llvm/orc/#adfa7bcc2544e48c4531ebfe74ae622b2">SymbolAliasMap</a> &gt; RuntimeAliases=std::nullopt)</td>
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

<p>Construct using a path to the ORC runtime.</p>

<p>Declaration at line 144 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/executionengine/include/llvm/executionengine/orc/machoplatform-h">MachOPlatform.h</a>, definition at line 325 of file <a href="/web-llvm/docs/api/files/lib/lib/executionengine/lib/executionengine/orc/machoplatform-cpp">MachOPlatform.cpp</a>.</p>


<p>References <a href="#ad166f5736231229286c93cd8c6aa8b6d">Create</a> and <a href="/web-llvm/docs/api/classes/llvm/orc/staticlibrarydefinitiongenerator/#a703cd8845907b2859b4ebdd00c206bc1">llvm::orc::StaticLibraryDefinitionGenerator::Load</a>.</p>

</div>
</div>

### requiredCXXAliases() {#afa832afa22d43b07518adfe5bae7c816}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">ArrayRef&lt; std::pair&lt; const char *, const char * &gt; &gt; llvm::orc::MachOPlatform::requiredCXXAliases ()</td>
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

<p>Declaration at line 173 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/executionengine/include/llvm/executionengine/orc/machoplatform-h">MachOPlatform.h</a>, definition at line 405 of file <a href="/web-llvm/docs/api/files/lib/lib/executionengine/lib/executionengine/orc/machoplatform-cpp">MachOPlatform.cpp</a>.</p>


<p>Referenced by <a href="#ab2b75dd698cda0452b5e84199248ca8a">standardPlatformAliases</a>.</p>

</div>
</div>

### standardLazyCompilationAliases() {#a25ec836178bfbac963e0945c6e0cdb75}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">ArrayRef&lt; std::pair&lt; const char *, const char * &gt; &gt; llvm::orc::MachOPlatform::standardLazyCompilationAliases ()</td>
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

<p>Returns a list of aliases required to enable lazy compilation via the ORC runtime.</p>

<p>Declaration at line 182 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/executionengine/include/llvm/executionengine/orc/machoplatform-h">MachOPlatform.h</a>, definition at line 429 of file <a href="/web-llvm/docs/api/files/lib/lib/executionengine/lib/executionengine/orc/machoplatform-cpp">MachOPlatform.cpp</a>.</p>


<p>Referenced by <a href="#ab2b75dd698cda0452b5e84199248ca8a">standardPlatformAliases</a>.</p>

</div>
</div>

### standardPlatformAliases() {#ab2b75dd698cda0452b5e84199248ca8a}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">SymbolAliasMap llvm::orc::MachOPlatform::standardPlatformAliases (<a href="/web-llvm/docs/api/classes/llvm/orc/executionsession">ExecutionSession</a> &amp; ES)</td>
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

<p>Returns an AliasMap containing the default aliases for the <a href="/web-llvm/docs/api/classes/llvm/orc/machoplatform">MachOPlatform</a>.</p>


<p>This can be modified by clients when constructing the platform to add or remove aliases.</p>


<p>Declaration at line 170 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/executionengine/include/llvm/executionengine/orc/machoplatform-h">MachOPlatform.h</a>, definition at line 396 of file <a href="/web-llvm/docs/api/files/lib/lib/executionengine/lib/executionengine/orc/machoplatform-cpp">MachOPlatform.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/namespaces/llvm/orc/#a82f74a53afe9225468960223f8d96c46">llvm::orc::addAliases</a>, <a href="#afa832afa22d43b07518adfe5bae7c816">requiredCXXAliases</a>, <a href="#a25ec836178bfbac963e0945c6e0cdb75">standardLazyCompilationAliases</a> and <a href="#a5033eefe5c3bcf123e9d3070884f38f5">standardRuntimeUtilityAliases</a>.</p>


<p>Referenced by <a href="#ad166f5736231229286c93cd8c6aa8b6d">Create</a>.</p>

</div>
</div>

### standardRuntimeUtilityAliases() {#a5033eefe5c3bcf123e9d3070884f38f5}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">ArrayRef&lt; std::pair&lt; const char *, const char * &gt; &gt; llvm::orc::MachOPlatform::standardRuntimeUtilityAliases ()</td>
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

<p>Returns the array of standard runtime utility aliases for <a href="/web-llvm/docs/api/namespaces/llvm/macho">MachO</a>.</p>

<p>Declaration at line 177 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/executionengine/include/llvm/executionengine/orc/machoplatform-h">MachOPlatform.h</a>, definition at line 413 of file <a href="/web-llvm/docs/api/files/lib/lib/executionengine/lib/executionengine/orc/machoplatform-cpp">MachOPlatform.cpp</a>.</p>


<p>Referenced by <a href="#ab2b75dd698cda0452b5e84199248ca8a">standardPlatformAliases</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Private Static Functions

### flagsForSymbol() {#ace8d0e493303fca2cbb2548b6add121d}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">MachOPlatform::MachOExecutorSymbolFlags llvm::orc::MachOPlatform::flagsForSymbol (<a href="/web-llvm/docs/api/classes/llvm/jitlink/symbol">jitlink::Symbol</a> &amp; Sym)</td>
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



<p>Declaration at line 298 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/executionengine/include/llvm/executionengine/orc/machoplatform-h">MachOPlatform.h</a>, definition at line 461 of file <a href="/web-llvm/docs/api/files/lib/lib/executionengine/lib/executionengine/orc/machoplatform-cpp">MachOPlatform.cpp</a>.</p>

</div>
</div>

### getPointerEdgeKind() {#a2de04c95b174adde918039416aab6716}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">jitlink::Edge::Kind llvm::orc::MachOPlatform::getPointerEdgeKind (<a href="/web-llvm/docs/api/classes/llvm/jitlink/linkgraph">jitlink::LinkGraph</a> &amp; G)</td>
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



<p>Declaration at line 296 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/executionengine/include/llvm/executionengine/orc/machoplatform-h">MachOPlatform.h</a>, definition at line 449 of file <a href="/web-llvm/docs/api/files/lib/lib/executionengine/lib/executionengine/orc/machoplatform-cpp">MachOPlatform.cpp</a>.</p>

</div>
</div>

### supportedTarget() {#afc346fc9cb8bf6dd068a52409381ff46}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool llvm::orc::MachOPlatform::supportedTarget (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/triple">Triple</a> &amp; TT)</td>
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



<p>Declaration at line 294 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/executionengine/include/llvm/executionengine/orc/machoplatform-h">MachOPlatform.h</a>, definition at line 439 of file <a href="/web-llvm/docs/api/files/lib/lib/executionengine/lib/executionengine/orc/machoplatform-cpp">MachOPlatform.cpp</a>.</p>

</div>
</div>

</div>

<hr/>

The documentation for this class was generated from the following files:

<ul>
<li><a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/executionengine/include/llvm/executionengine/orc/machoplatform-h">MachOPlatform.h</a></li>
<li><a href="/web-llvm/docs/api/files/lib/lib/executionengine/lib/executionengine/orc/machoplatform-cpp">MachOPlatform.cpp</a></li>
</ul>

<hr/>

<p class="doxyGeneratedBy">Generated via <a href="https://github.com/xpack/doxygen2docusaurus">doxygen2docusaurus</a> by <a href="https://www.doxygen.nl">Doxygen</a> 1.14.0.</p>

</div>
