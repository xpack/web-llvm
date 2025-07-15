---

# DO NOT EDIT!
# Automatically generated via doxygen2docusaurus by Doxygen.

slug: /api/namespaces/llvm/orc/shared
custom_edit_url: null
toc_max_heading_level: 4
keywords:
  - doxygen
  - reference
  - namespace

---

<div class="doxyPage">

# The `shared` Namespace Reference



## Definition

<div class="doxyDefinition">
namespace llvm::orc::shared { ... }
</div>

## Namespaces Index

<table class="doxyMembersIndex">

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">namespace</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="/web-llvm/docs/api/namespaces/llvm/orc/shared/detail">detail</a></td>
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

## Classes Index

<table class="doxyMembersIndex">

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">struct</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="/web-llvm/docs/api/structs/llvm/orc/shared/allocactioncallpair">AllocActionCallPair</a></td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>A pair of WrapperFunctionCalls, one to be run at finalization time, one to be run at deallocation time. <a href="/web-llvm/docs/api/structs/llvm/orc/shared/allocactioncallpair/#details">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">struct</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="/web-llvm/docs/api/structs/llvm/orc/shared/cwrapperfunctionresult">CWrapperFunctionResult</a></td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">union</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="/web-llvm/docs/api/unions/llvm/orc/shared/cwrapperfunctionresultdataunion">CWrapperFunctionResultDataUnion</a></td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/orc/shared/methodwrapperhandler">MethodWrapperHandler&lt;RetT, ClassT, ArgTs&gt;</a></td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>A function object that takes an <a href="/web-llvm/docs/api/classes/llvm/orc/executoraddr">ExecutorAddr</a> as its first argument, casts that address to a ClassT*, then calls the given method on that pointer passing in the remaining function arguments. <a href="/web-llvm/docs/api/classes/llvm/orc/shared/methodwrapperhandler/#details">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">class</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/orc/shared/spsarglist">SPSArgList&lt;ArgTs&gt;</a></td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>A utility class for serializing to a blob from a variadic list. <a href="/web-llvm/docs/api/classes/llvm/orc/shared/spsarglist/#details">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">class</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/orc/shared/spsarglist-ade063f27d7f7f49fb540da6dccad5db">SPSArgList&lt;SPSTagT, SPSTagTs...&gt;</a></td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/orc/shared/spsarglist-38559c871fba28d992ead51549367f83">SPSArgList&lt;&gt;</a></td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/orc/shared/spsempty">SPSEmpty</a></td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/orc/shared/spsexecutoraddr">SPSExecutorAddr</a></td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/orc/shared/spsexpected">SPSExpected&lt;SPSTagT&gt;</a></td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>SPS tag type for expecteds, which are either a T or a string representing an error. <a href="/web-llvm/docs/api/classes/llvm/orc/shared/spsexpected/#details">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">class</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/orc/shared/spsinputbuffer">SPSInputBuffer</a></td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p><a href="/web-llvm/docs/api/classes/input">Input</a> char buffer with underflow check. <a href="/web-llvm/docs/api/classes/llvm/orc/shared/spsinputbuffer/#details">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">class</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/orc/shared/spsoptional">SPSOptional&lt;SPSTagT&gt;</a></td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>SPS tag type for optionals. <a href="/web-llvm/docs/api/classes/llvm/orc/shared/spsoptional/#details">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">class</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/orc/shared/spsoutputbuffer">SPSOutputBuffer</a></td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Output char buffer with overflow check. <a href="/web-llvm/docs/api/classes/llvm/orc/shared/spsoutputbuffer/#details">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">class</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/orc/shared/spssequence">SPSSequence&lt;SPSElementTagT&gt;</a></td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>SPS tag type for sequences. <a href="/web-llvm/docs/api/classes/llvm/orc/shared/spssequence/#details">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">class</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/orc/shared/spsserializationtraits">SPSSerializationTraits&lt;SPSTagT, ConcreteT, _&gt;</a></td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Specialize to describe how to serialize/deserialize to/from the given concrete type. <a href="/web-llvm/docs/api/classes/llvm/orc/shared/spsserializationtraits/#details">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">class</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/orc/shared/spsserializationtraits-7dec749f93c51446f39c26c3bd42b2d1">SPSSerializationTraits&lt;SPSAllocActionCallPair, AllocActionCallPair&gt;</a></td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/orc/shared/spsserializationtraits-4a4349e84cb76fa6e4b87af0bdf8dcce">SPSSerializationTraits&lt;SPSELFPerObjectSectionsToRegister, ELFPerObjectSectionsToRegister&gt;</a></td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/orc/shared/spsserializationtraits-73102b3c945f4ce3037e4a3b7cc9f4a3">SPSSerializationTraits&lt;SPSEmpty, SPSEmpty&gt;</a></td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Serialization for <a href="/web-llvm/docs/api/classes/llvm/orc/shared/spsempty">SPSEmpty</a> type. <a href="/web-llvm/docs/api/classes/llvm/orc/shared/spsserializationtraits-73102b3c945f4ce3037e4a3b7cc9f4a3/#details">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">class</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/orc/shared/spsserializationtraits-cd852d5f6a36d9b68f841465fc6ad92c">SPSSerializationTraits&lt;SPSError, detail::SPSSerializableError&gt;</a></td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Serialize to a SPSError from a <a href="/web-llvm/docs/api/structs/llvm/orc/shared/detail/spsserializableerror">detail::SPSSerializableError</a>. <a href="/web-llvm/docs/api/classes/llvm/orc/shared/spsserializationtraits-cd852d5f6a36d9b68f841465fc6ad92c/#details">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">class</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/orc/shared/spsserializationtraits-7c663d3ebf566f53b426b05f6555c600">SPSSerializationTraits&lt;SPSExecutorAddr, ExecutorAddr&gt;</a></td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>SPS serializatior for <a href="/web-llvm/docs/api/classes/llvm/orc/executoraddr">ExecutorAddr</a>. <a href="/web-llvm/docs/api/classes/llvm/orc/shared/spsserializationtraits-7c663d3ebf566f53b426b05f6555c600/#details">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">class</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/orc/shared/spsserializationtraits-e47496333f3a7195e94b23690cdd7152">SPSSerializationTraits&lt;SPSExecutorAddr, jitlink::JITLinkMemoryManager::FinalizedAlloc&gt;</a></td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>FIXME: This specialization should be moved into <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/executionengine/include/llvm/executionengine/orc/include/llvm/executionengine/orc/shared/targetprocesscontroltypes-h">TargetProcessControlTypes.h</a> (or wherever those types get merged to) once ORC depends on JITLink. <a href="/web-llvm/docs/api/classes/llvm/orc/shared/spsserializationtraits-e47496333f3a7195e94b23690cdd7152/#details">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">class</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/orc/shared/spsserializationtraits-31e3dd6c5fee9a97ecd2d80646929061">SPSSerializationTraits&lt;SPSExecutorAddrRange, ExecutorAddrRange&gt;</a></td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Serialization traits for address ranges. <a href="/web-llvm/docs/api/classes/llvm/orc/shared/spsserializationtraits-31e3dd6c5fee9a97ecd2d80646929061/#details">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">class</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/orc/shared/spsserializationtraits-e321987a18985455c442c402cefd370c">SPSSerializationTraits&lt;SPSExecutorSymbolDef, ExecutorSymbolDef&gt;</a></td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>SPS serializatior for <a href="/web-llvm/docs/api/classes/llvm/orc/executorsymboldef">ExecutorSymbolDef</a>. <a href="/web-llvm/docs/api/classes/llvm/orc/shared/spsserializationtraits-e321987a18985455c442c402cefd370c/#details">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">class</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/orc/shared/spsserializationtraits-37cbb09f9b4be473884ff41b97f4a7e3">SPSSerializationTraits&lt;SPSExpected&lt; SPSTagT &gt;, detail::SPSSerializableError&gt;</a></td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Serialize to a <a href="/web-llvm/docs/api/classes/llvm/orc/shared/spsexpected">SPSExpected&lt;SPSTagT&gt;</a> from a <a href="/web-llvm/docs/api/structs/llvm/orc/shared/detail/spsserializableerror">detail::SPSSerializableError</a>. <a href="/web-llvm/docs/api/classes/llvm/orc/shared/spsserializationtraits-37cbb09f9b4be473884ff41b97f4a7e3/#details">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">class</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/orc/shared/spsserializationtraits-6eb1037f48906ccf4a6754355361971f">SPSSerializationTraits&lt;SPSExpected&lt; SPSTagT &gt;, detail::SPSSerializableExpected&lt; T &gt;&gt;</a></td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Serialize to a <a href="/web-llvm/docs/api/classes/llvm/orc/shared/spsexpected">SPSExpected&lt;SPSTagT&gt;</a> from a <a href="/web-llvm/docs/api/structs/llvm/orc/shared/detail/spsserializableexpected">detail::SPSSerializableExpected&lt;T&gt;</a>. <a href="/web-llvm/docs/api/classes/llvm/orc/shared/spsserializationtraits-6eb1037f48906ccf4a6754355361971f/#details">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">class</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/orc/shared/spsserializationtraits-fc4016c8d8c4495f46b412168ce23a39">SPSSerializationTraits&lt;SPSExpected&lt; SPSTagT &gt;, T&gt;</a></td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Serialize to a <a href="/web-llvm/docs/api/classes/llvm/orc/shared/spsexpected">SPSExpected&lt;SPSTagT&gt;</a> from a T. <a href="/web-llvm/docs/api/classes/llvm/orc/shared/spsserializationtraits-fc4016c8d8c4495f46b412168ce23a39/#details">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">class</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/orc/shared/spsserializationtraits-8d961f7519b494fe7911b7456b62b5bc">SPSSerializationTraits&lt;SPSFinalizeRequest, tpctypes::FinalizeRequest&gt;</a></td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/orc/shared/spsserializationtraits-0da1f70d1d92c2b66afc8dda54004bbc">SPSSerializationTraits&lt;SPSJITSymbolFlags, JITSymbolFlags&gt;</a></td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>SPS serializatior for <a href="/web-llvm/docs/api/classes/llvm/jitsymbolflags">JITSymbolFlags</a>. <a href="/web-llvm/docs/api/classes/llvm/orc/shared/spsserializationtraits-0da1f70d1d92c2b66afc8dda54004bbc/#details">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">class</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/orc/shared/spsserializationtraits-14905d9a94849ef22778e38054ef6b35">SPSSerializationTraits&lt;SPSMachOExecutorSymbolFlags, MachOPlatform::MachOExecutorSymbolFlags&gt;</a></td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/orc/shared/spsserializationtraits-c6d176ad220170898e4bb610fa876dea">SPSSerializationTraits&lt;SPSMachOJITDylibDepInfo, MachOPlatform::MachOJITDylibDepInfo&gt;</a></td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/orc/shared/spsserializationtraits-71687e8a474d10567aa469b563addeee">SPSSerializationTraits&lt;SPSMemoryAccessBufferWrite, tpctypes::BufferWrite&gt;</a></td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/orc/shared/spsserializationtraits-e7f248266248024b510ebd5ea3836f79">SPSSerializationTraits&lt;SPSMemoryAccessPointerWrite, tpctypes::PointerWrite&gt;</a></td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/orc/shared/spsserializationtraits-ae65730cc6de186b086a4e60fc396e11">SPSSerializationTraits&lt;SPSMemoryAccessUIntWrite&lt; T &gt;, tpctypes::UIntWrite&lt; T &gt;&gt;</a></td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/orc/shared/spsserializationtraits-75f93f7f70cbe45c06a0f848750912ee">SPSSerializationTraits&lt;SPSOptional&lt; SPSTagT &gt;, std::optional&lt; T &gt;&gt;</a></td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p><a href="/web-llvm/docs/api/classes/llvm/orc/shared/spsoptional">SPSOptional</a> serialization for std::optional. <a href="/web-llvm/docs/api/classes/llvm/orc/shared/spsserializationtraits-75f93f7f70cbe45c06a0f848750912ee/#details">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">class</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/orc/shared/spsserializationtraits-20c3e8fe0b43675dcae9552f5a6e6381">SPSSerializationTraits&lt;SPSPerfJITCodeLoadRecord, PerfJITCodeLoadRecord&gt;</a></td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/orc/shared/spsserializationtraits-53f5c500ef1915486eadd6d8e0a449ba">SPSSerializationTraits&lt;SPSPerfJITCodeUnwindingInfoRecord, PerfJITCodeUnwindingInfoRecord&gt;</a></td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/orc/shared/spsserializationtraits-bf8924ae7d79c09d623eda7a9bca91c9">SPSSerializationTraits&lt;SPSPerfJITDebugEntry, PerfJITDebugEntry&gt;</a></td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/orc/shared/spsserializationtraits-f42140d4aead7dc95bdc42c5e21e5ae9">SPSSerializationTraits&lt;SPSPerfJITDebugInfoRecord, PerfJITDebugInfoRecord&gt;</a></td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/orc/shared/spsserializationtraits-46145372e1312ab0db588d8e712df78b">SPSSerializationTraits&lt;SPSPerfJITRecordBatch, PerfJITRecordBatch&gt;</a></td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/orc/shared/spsserializationtraits-b23e5a852f3aefd3a94c5f626e3e85e7">SPSSerializationTraits&lt;SPSPerfJITRecordPrefix, PerfJITRecordPrefix&gt;</a></td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/orc/shared/spsserializationtraits-aeebb0825631f820a39ab3fb25c6ed72">SPSSerializationTraits&lt;SPSRemoteAllocGroup, tpctypes::RemoteAllocGroup&gt;</a></td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/orc/shared/spsserializationtraits-00c54102394820e4e4a0c6d885ac3542">SPSSerializationTraits&lt;SPSRemoteSymbolLookup, DylibManager::LookupRequest&gt;</a></td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/orc/shared/spsserializationtraits-e6f3407606c96b1e4e04d36265010f97">SPSSerializationTraits&lt;SPSRemoteSymbolLookup, RemoteSymbolLookup&gt;</a></td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/orc/shared/spsserializationtraits-8bb0c38405e731770fcc164a0efbfc82">SPSSerializationTraits&lt;SPSRemoteSymbolLookupSetElement, RemoteSymbolLookupSetElement&gt;</a></td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/orc/shared/spsserializationtraits-0521b96d452ef45bf186843e7f4aa9f7">SPSSerializationTraits&lt;SPSRemoteSymbolLookupSetElement, SymbolLookupSet::value_type&gt;</a></td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/orc/shared/spsserializationtraits-784a1bef17190e6ab41c561ff2b7a7b9">SPSSerializationTraits&lt;SPSSegFinalizeRequest, tpctypes::SegFinalizeRequest&gt;</a></td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/orc/shared/spsserializationtraits-f019840641ef1438dc73ca66a5e8c819">SPSSerializationTraits&lt;SPSSequence&lt; char &gt;, ArrayRef&lt; char &gt;&gt;</a></td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Specialized <a href="/web-llvm/docs/api/classes/llvm/orc/shared/spssequence">SPSSequence&lt;char&gt;</a> -&gt; <a href="/web-llvm/docs/api/classes/llvm/arrayref">ArrayRef&lt;char&gt;</a> serialization. <a href="/web-llvm/docs/api/classes/llvm/orc/shared/spsserializationtraits-f019840641ef1438dc73ca66a5e8c819/#details">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">class</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/orc/shared/spsserializationtraits-b4773a76f675f907803c035578129f5e">SPSSerializationTraits&lt;SPSSequence&lt; SPSElementTagT &gt;, SequenceT, std::enable_if_t&lt; TrivialSPSSequenceSerialization&lt; SPSElementTagT, SequenceT &gt;::available &gt;&gt;</a></td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>'Trivial' sequence serialization: Sequence is serialized as a uint64_t size followed by a for-earch loop over the elements of the sequence to serialize each of them. <a href="/web-llvm/docs/api/classes/llvm/orc/shared/spsserializationtraits-b4773a76f675f907803c035578129f5e/#details">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">class</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/orc/shared/spsserializationtraits-ad3c6a75d874eeba0dc8345a233b4dcc">SPSSerializationTraits&lt;SPSSequence&lt; SPSTuple&lt; SPSString, SPSValueT &gt; &gt;, StringMap&lt; ValueT &gt;&gt;</a></td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Serialization for <a href="/web-llvm/docs/api/classes/llvm/stringmap">StringMap&lt;ValueT&gt;</a>s. <a href="/web-llvm/docs/api/classes/llvm/orc/shared/spsserializationtraits-ad3c6a75d874eeba0dc8345a233b4dcc/#details">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">class</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/orc/shared/spsserializationtraits-93eecca8a87e5b74adad0ef6c46c4f97">SPSSerializationTraits&lt;SPSSharedMemoryFinalizeRequest, tpctypes::SharedMemoryFinalizeRequest&gt;</a></td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/orc/shared/spsserializationtraits-c4c9d06010351644bf0ec9c5d491d476">SPSSerializationTraits&lt;SPSSharedMemorySegFinalizeRequest, tpctypes::SharedMemorySegFinalizeRequest&gt;</a></td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/orc/shared/spsserializationtraits-ea18de0a5e2ee726f163169765325d87">SPSSerializationTraits&lt;SPSSimpleRemoteEPCExecutorInfo, SimpleRemoteEPCExecutorInfo&gt;</a></td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/orc/shared/spsserializationtraits-df914a78aa74437406828e15b40ba1b2">SPSSerializationTraits&lt;SPSString, StringRef&gt;</a></td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Serialization for StringRefs. <a href="/web-llvm/docs/api/classes/llvm/orc/shared/spsserializationtraits-df914a78aa74437406828e15b40ba1b2/#details">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">class</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/orc/shared/spsserializationtraits-bc8864bc9177988c0f61b4692cfcd36c">SPSSerializationTraits&lt;SPSTagT, SPSTagT, std::enable_if_t&lt; std::is_same&lt; SPSTagT, bool &gt;::value||std::is_same&lt; SPSTagT, char &gt;::value||std::is_same&lt; SPSTagT, int8_t &gt;::value||std::is_same&lt; SPSTagT, int16_t &gt;::value||std::is_same&lt; SPSTagT, int32_t &gt;::value||std::is_same&lt; SPSTagT, int64_t &gt;::value||std::is_same&lt; SPSTagT, uint8_t &gt;::value||std::is_same&lt; SPSTagT, uint16_t &gt;::value||std::is_same&lt; SPSTagT, uint32_t &gt;::value||std::is_same&lt; SPSTagT, uint64_t &gt;::value &gt;&gt;</a></td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>SPS serialization for integral types, bool, and char. <a href="/web-llvm/docs/api/classes/llvm/orc/shared/spsserializationtraits-bc8864bc9177988c0f61b4692cfcd36c/#details">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">class</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/orc/shared/spsserializationtraits-f01540c9a4b553bdf4fa0df9a2b9cf36">SPSSerializationTraits&lt;SPSTuple&lt; SPSTagT1, SPSTagT2 &gt;, std::pair&lt; T1, T2 &gt;&gt;</a></td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p><a href="/web-llvm/docs/api/classes/llvm/orc/shared/spstuple">SPSTuple</a> serialization for std::pair. <a href="/web-llvm/docs/api/classes/llvm/orc/shared/spsserializationtraits-f01540c9a4b553bdf4fa0df9a2b9cf36/#details">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">class</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/orc/shared/spsserializationtraits-278ceb76ae7482b6d9279b9275c5dc4a">SPSSerializationTraits&lt;SPSTuple&lt; SPSTagTs... &gt;, std::tuple&lt; Ts... &gt;&gt;</a></td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p><a href="/web-llvm/docs/api/classes/llvm/orc/shared/spstuple">SPSTuple</a> serialization for std::tuple. <a href="/web-llvm/docs/api/classes/llvm/orc/shared/spsserializationtraits-278ceb76ae7482b6d9279b9275c5dc4a/#details">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">class</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/orc/shared/spsserializationtraits-9c3017e558e10a785f4f9859d2b0ac2e">SPSSerializationTraits&lt;SPSVTuneMethodBatch, VTuneMethodBatch&gt;</a></td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/orc/shared/spsserializationtraits-0febf1ed687686d6570ddae389b2a20f">SPSSerializationTraits&lt;SPSVTuneMethodInfo, VTuneMethodInfo&gt;</a></td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/orc/shared/spsserializationtraits-6f403f5489d3025cbee03c70dd5dff03">SPSSerializationTraits&lt;SPSWrapperFunctionCall, WrapperFunctionCall&gt;</a></td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/orc/shared/spstuple">SPSTuple&lt;SPSTagTs&gt;</a></td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>SPS tag type for tuples. <a href="/web-llvm/docs/api/classes/llvm/orc/shared/spstuple/#details">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">class</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/orc/shared/trivialspssequencedeserialization">TrivialSPSSequenceDeserialization&lt;SPSElementTagT, ConcreteSequenceT&gt;</a></td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Specialize this to implement 'trivial' sequence deserialization for a concrete sequence type. <a href="/web-llvm/docs/api/classes/llvm/orc/shared/trivialspssequencedeserialization/#details">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">class</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/orc/shared/trivialspssequencedeserialization-6551f236402cb4450ad318ef3746f88b">TrivialSPSSequenceDeserialization&lt;char, std::string&gt;</a></td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Trivial <a href="/web-llvm/docs/api/classes/llvm/orc/shared/spssequence">SPSSequence&lt;char&gt;</a> -&gt; std::string deserialization. <a href="/web-llvm/docs/api/classes/llvm/orc/shared/trivialspssequencedeserialization-6551f236402cb4450ad318ef3746f88b/#details">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">class</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/orc/shared/trivialspssequencedeserialization-f85231e1e53bc289879e23cdc9c8d11b">TrivialSPSSequenceDeserialization&lt;SPSElementTagT, SmallVector&lt; T, N &gt;&gt;</a></td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Trivial <a href="/web-llvm/docs/api/classes/llvm/orc/shared/spssequence">SPSSequence&lt;SPSElementTagT&gt;</a> -&gt; <a href="/web-llvm/docs/api/classes/llvm/smallvectorimpl">SmallVectorImpl&lt;T&gt;</a> deserialization. <a href="/web-llvm/docs/api/classes/llvm/orc/shared/trivialspssequencedeserialization-f85231e1e53bc289879e23cdc9c8d11b/#details">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">class</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/orc/shared/trivialspssequencedeserialization-50e0d7f1c41e4df8199f0418331b4143">TrivialSPSSequenceDeserialization&lt;SPSElementTagT, SmallVectorImpl&lt; T &gt;&gt;</a></td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Trivial <a href="/web-llvm/docs/api/classes/llvm/orc/shared/spssequence">SPSSequence&lt;SPSElementTagT&gt;</a> -&gt; <a href="/web-llvm/docs/api/classes/llvm/smallvectorimpl">SmallVectorImpl&lt;T&gt;</a> deserialization. <a href="/web-llvm/docs/api/classes/llvm/orc/shared/trivialspssequencedeserialization-50e0d7f1c41e4df8199f0418331b4143/#details">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">class</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/orc/shared/trivialspssequencedeserialization-b2f13945b68f255caec04fc7bacaccc5">TrivialSPSSequenceDeserialization&lt;SPSElementTagT, std::vector&lt; T &gt;&gt;</a></td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Trivial <a href="/web-llvm/docs/api/classes/llvm/orc/shared/spssequence">SPSSequence&lt;SPSElementTagT&gt;</a> -&gt; std::vector&lt;T&gt; deserialization. <a href="/web-llvm/docs/api/classes/llvm/orc/shared/trivialspssequencedeserialization-b2f13945b68f255caec04fc7bacaccc5/#details">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">class</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/orc/shared/trivialspssequenceserialization">TrivialSPSSequenceSerialization&lt;SPSElementTagT, ConcreteSequenceT&gt;</a></td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Specialize this to implement 'trivial' sequence serialization for a concrete sequence type. <a href="/web-llvm/docs/api/classes/llvm/orc/shared/trivialspssequenceserialization/#details">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">class</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/orc/shared/trivialspssequenceserialization-6551f236402cb4450ad318ef3746f88b">TrivialSPSSequenceSerialization&lt;char, std::string&gt;</a></td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Trivial std::string -&gt; <a href="/web-llvm/docs/api/classes/llvm/orc/shared/spssequence">SPSSequence&lt;char&gt;</a> serialization. <a href="/web-llvm/docs/api/classes/llvm/orc/shared/trivialspssequenceserialization-6551f236402cb4450ad318ef3746f88b/#details">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">class</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/orc/shared/trivialspssequenceserialization-259352f25699e374ee62b5725f593f1c">TrivialSPSSequenceSerialization&lt;SPSElementTagT, ArrayRef&lt; T &gt;&gt;</a></td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Trivial <a href="/web-llvm/docs/api/classes/llvm/arrayref">ArrayRef&lt;T&gt;</a> -&gt; <a href="/web-llvm/docs/api/classes/llvm/orc/shared/spssequence">SPSSequence&lt;SPSElementTagT&gt;</a> serialization. <a href="/web-llvm/docs/api/classes/llvm/orc/shared/trivialspssequenceserialization-259352f25699e374ee62b5725f593f1c/#details">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">class</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/orc/shared/trivialspssequenceserialization-f85231e1e53bc289879e23cdc9c8d11b">TrivialSPSSequenceSerialization&lt;SPSElementTagT, SmallVector&lt; T, N &gt;&gt;</a></td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Trivial <a href="/web-llvm/docs/api/classes/llvm/smallvectorimpl">SmallVectorImpl&lt;T&gt;</a> -&gt; <a href="/web-llvm/docs/api/classes/llvm/orc/shared/spssequence">SPSSequence&lt;char&gt;</a> serialization. <a href="/web-llvm/docs/api/classes/llvm/orc/shared/trivialspssequenceserialization-f85231e1e53bc289879e23cdc9c8d11b/#details">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">class</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/orc/shared/trivialspssequenceserialization-50e0d7f1c41e4df8199f0418331b4143">TrivialSPSSequenceSerialization&lt;SPSElementTagT, SmallVectorImpl&lt; T &gt;&gt;</a></td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Trivial <a href="/web-llvm/docs/api/classes/llvm/smallvectorimpl">SmallVectorImpl&lt;T&gt;</a> -&gt; <a href="/web-llvm/docs/api/classes/llvm/orc/shared/spssequence">SPSSequence&lt;char&gt;</a> serialization. <a href="/web-llvm/docs/api/classes/llvm/orc/shared/trivialspssequenceserialization-50e0d7f1c41e4df8199f0418331b4143/#details">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">class</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/orc/shared/trivialspssequenceserialization-b2f13945b68f255caec04fc7bacaccc5">TrivialSPSSequenceSerialization&lt;SPSElementTagT, std::vector&lt; T &gt;&gt;</a></td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Trivial std::vector&lt;T&gt; -&gt; <a href="/web-llvm/docs/api/classes/llvm/orc/shared/spssequence">SPSSequence&lt;SPSElementTagT&gt;</a> serialization. <a href="/web-llvm/docs/api/classes/llvm/orc/shared/trivialspssequenceserialization-b2f13945b68f255caec04fc7bacaccc5/#details">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">class</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/orc/shared/trivialspssequenceserialization-efda56c1d7ea865b9efb0454f9c681e8">TrivialSPSSequenceSerialization&lt;SPSRemoteSymbolLookupSetElement, SymbolLookupSet&gt;</a></td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/orc/shared/wrapperfunction">WrapperFunction&lt;SPSSignature&gt;</a></td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/orc/shared/wrapperfunction-cc5f507a6376a88c1d33fbec441bda7d">WrapperFunction&lt;SPSRetTagT(SPSTagTs...)&gt;</a></td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/orc/shared/wrapperfunction-57c216e8d05a1a3276d5aed69aadeffc">WrapperFunction&lt;void(SPSTagTs...)&gt;</a></td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/orc/shared/wrapperfunctioncall">WrapperFunctionCall</a></td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Represents a serialized wrapper function call. <a href="/web-llvm/docs/api/classes/llvm/orc/shared/wrapperfunctioncall/#details">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">class</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/orc/shared/wrapperfunctionresult">WrapperFunctionResult</a></td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>C++ wrapper function result: Same as <a href="/web-llvm/docs/api/structs/llvm/orc/shared/cwrapperfunctionresult">CWrapperFunctionResult</a> but auto-releases memory. <a href="/web-llvm/docs/api/classes/llvm/orc/shared/wrapperfunctionresult/#details">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

</table>

## Typedefs Index

<table class="doxyMembersIndex">

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">using</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a1c4c7365247c5364b0183da327176a04">SPSELFPerObjectSectionsToRegister</a> = <a href="/web-llvm/docs/api/classes/llvm/orc/shared/spstuple">SPSTuple</a>&lt; <a href="#aa48e4738482db923f95f0667a440aea4">SPSExecutorAddrRange</a>, <a href="#aa48e4738482db923f95f0667a440aea4">SPSExecutorAddrRange</a> &gt;</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a7c37debf020343319cd5515b321a05b6">SPSELFNixJITDylibDepInfoMap</a> = <a href="/web-llvm/docs/api/classes/llvm/orc/shared/spssequence">SPSSequence</a>&lt; <a href="/web-llvm/docs/api/classes/llvm/orc/shared/spstuple">SPSTuple</a>&lt; <a href="/web-llvm/docs/api/classes/llvm/orc/shared/spsexecutoraddr">SPSExecutorAddr</a>, <a href="/web-llvm/docs/api/classes/llvm/orc/shared/spssequence">SPSSequence</a>&lt; <a href="/web-llvm/docs/api/classes/llvm/orc/shared/spsexecutoraddr">SPSExecutorAddr</a> &gt; &gt; &gt;</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a6da0b5cb8e68a6cc791a183d9d38aae0">AllocActions</a> = std::vector&lt; <a href="/web-llvm/docs/api/structs/llvm/orc/shared/allocactioncallpair">AllocActionCallPair</a> &gt;</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>A vector of allocation actions to be run for this allocation. <a href="#a6da0b5cb8e68a6cc791a183d9d38aae0">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">using</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#aaf20479822b924307d388261f4bb1159">SPSAllocActionCallPair</a> = <a href="/web-llvm/docs/api/classes/llvm/orc/shared/spstuple">SPSTuple</a>&lt; <a href="#a99ed71ed35a3aed5a6a7ca164c750dad">SPSWrapperFunctionCall</a>, <a href="#a99ed71ed35a3aed5a6a7ca164c750dad">SPSWrapperFunctionCall</a> &gt;</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#aa48e4738482db923f95f0667a440aea4">SPSExecutorAddrRange</a> = <a href="/web-llvm/docs/api/classes/llvm/orc/shared/spstuple">SPSTuple</a>&lt; <a href="/web-llvm/docs/api/classes/llvm/orc/shared/spsexecutoraddr">SPSExecutorAddr</a>, <a href="/web-llvm/docs/api/classes/llvm/orc/shared/spsexecutoraddr">SPSExecutorAddr</a> &gt;</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a1b3495ab143f17c8ab3ffbf1e167dfed">SPSExecutorAddrRangeSequence</a> = <a href="/web-llvm/docs/api/classes/llvm/orc/shared/spssequence">SPSSequence</a>&lt; <a href="#aa48e4738482db923f95f0667a440aea4">SPSExecutorAddrRange</a> &gt;</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a0295b4b8235c6c45e3d630f59a879547">SPSJITSymbolFlags</a> = <a href="/web-llvm/docs/api/classes/llvm/orc/shared/spstuple">SPSTuple</a>&lt; <a href="/web-llvm/docs/api/classes/llvm/jitsymbolflags/#ae8a3d8ffa06d35ed1b432fd4ba578ad4">JITSymbolFlags::UnderlyingType</a>, <a href="/web-llvm/docs/api/classes/llvm/jitsymbolflags/#a52b2cde16c7a36e0ac89c4a9462f2226">JITSymbolFlags::TargetFlagsType</a> &gt;</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a2e25123fcbb940292ea9a1f907924952">SPSExecutorSymbolDef</a> = <a href="/web-llvm/docs/api/classes/llvm/orc/shared/spstuple">SPSTuple</a>&lt; <a href="/web-llvm/docs/api/classes/llvm/orc/shared/spsexecutoraddr">SPSExecutorAddr</a>, <a href="#a0295b4b8235c6c45e3d630f59a879547">SPSJITSymbolFlags</a> &gt;</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a18a3a6ce95408493d152bbe2def15947">SPSPerfJITRecordPrefix</a> = <a href="/web-llvm/docs/api/classes/llvm/orc/shared/spstuple">SPSTuple</a>&lt; uint32_t, uint32_t &gt;</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a229d8f55458fe47f2d874ec647efefc9">SPSPerfJITCodeLoadRecord</a> = <a href="/web-llvm/docs/api/classes/llvm/orc/shared/spstuple">SPSTuple</a>&lt; <a href="#a18a3a6ce95408493d152bbe2def15947">SPSPerfJITRecordPrefix</a>, uint32_t, uint32_t, uint64_t, uint64_t, uint64_t, uint64_t, <a href="#a3b101487ee72cf9033225840204e68bb">SPSString</a> &gt;</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ae405e3e3dbf8ee11685677d3c6df3451">SPSPerfJITDebugEntry</a> = <a href="/web-llvm/docs/api/classes/llvm/orc/shared/spstuple">SPSTuple</a>&lt; uint64_t, uint32_t, uint32_t, <a href="#a3b101487ee72cf9033225840204e68bb">SPSString</a> &gt;</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a90b01e023242207373817d7ffc8d3402">SPSPerfJITDebugInfoRecord</a> = <a href="/web-llvm/docs/api/classes/llvm/orc/shared/spstuple">SPSTuple</a>&lt; <a href="#a18a3a6ce95408493d152bbe2def15947">SPSPerfJITRecordPrefix</a>, uint64_t, <a href="/web-llvm/docs/api/classes/llvm/orc/shared/spssequence">SPSSequence</a>&lt; <a href="#ae405e3e3dbf8ee11685677d3c6df3451">SPSPerfJITDebugEntry</a> &gt; &gt;</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a0578094f53cbed5cabb13da9cb5f664a">SPSPerfJITCodeUnwindingInfoRecord</a> = <a href="/web-llvm/docs/api/classes/llvm/orc/shared/spstuple">SPSTuple</a>&lt; <a href="#a18a3a6ce95408493d152bbe2def15947">SPSPerfJITRecordPrefix</a>, uint64_t, uint64_t, uint64_t, uint64_t, <a href="#a3b101487ee72cf9033225840204e68bb">SPSString</a>, uint64_t &gt;</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a5154edf9dc098d48b5d3972eb81ad5c3">SPSPerfJITRecordBatch</a> = <a href="/web-llvm/docs/api/classes/llvm/orc/shared/spstuple">SPSTuple</a>&lt; <a href="/web-llvm/docs/api/classes/llvm/orc/shared/spssequence">SPSSequence</a>&lt; <a href="#a229d8f55458fe47f2d874ec647efefc9">SPSPerfJITCodeLoadRecord</a> &gt;, <a href="/web-llvm/docs/api/classes/llvm/orc/shared/spssequence">SPSSequence</a>&lt; <a href="#a90b01e023242207373817d7ffc8d3402">SPSPerfJITDebugInfoRecord</a> &gt;, <a href="#a0578094f53cbed5cabb13da9cb5f664a">SPSPerfJITCodeUnwindingInfoRecord</a> &gt;</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a3b101487ee72cf9033225840204e68bb">SPSString</a> = <a href="/web-llvm/docs/api/classes/llvm/orc/shared/spssequence">SPSSequence</a>&lt; char &gt;</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>SPS tag type for strings, which are equivalent to sequences of chars. <a href="#a3b101487ee72cf9033225840204e68bb">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexTemplate">
<td class="doxyMemberIndexTemplate" colspan="2"><div>template &lt;typename SPSTagT1, typename SPSTagT2&gt;</div></td>
</tr>
<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemTypeTemplate" align="left" valign="top">using</td>
<td class="doxyMemberIndexItemNameTemplate" align="left" valign="top"><a href="#a24d34cffd0fe2ca8a39d38b4a1d18474">SPSMap</a> = <a href="/web-llvm/docs/api/classes/llvm/orc/shared/spssequence">SPSSequence</a>&lt; <a href="/web-llvm/docs/api/classes/llvm/orc/shared/spstuple">SPSTuple</a>&lt; SPSTagT1, SPSTagT2 &gt; &gt;</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>SPS tag type for maps. <a href="#a24d34cffd0fe2ca8a39d38b4a1d18474">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">using</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a61d90db1bc867d756c6431a7aac12b2b">SPSRemoteSymbolLookupSetElement</a> = <a href="/web-llvm/docs/api/classes/llvm/orc/shared/spstuple">SPSTuple</a>&lt; <a href="#a3b101487ee72cf9033225840204e68bb">SPSString</a>, bool &gt;</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#aa4683bc096f3b0cd8be3e2bcfa5924fa">SPSRemoteSymbolLookupSet</a> = <a href="/web-llvm/docs/api/classes/llvm/orc/shared/spssequence">SPSSequence</a>&lt; <a href="#a61d90db1bc867d756c6431a7aac12b2b">SPSRemoteSymbolLookupSetElement</a> &gt;</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#aa3c3ea30847f43c1075fb13d02fc457a">SPSRemoteSymbolLookup</a> = <a href="/web-llvm/docs/api/classes/llvm/orc/shared/spstuple">SPSTuple</a>&lt; uint64_t, <a href="#aa4683bc096f3b0cd8be3e2bcfa5924fa">SPSRemoteSymbolLookupSet</a> &gt;</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a59137420a08264e9deb791025a69564a">SPSSimpleRemoteEPCExecutorInfo</a> = <a href="/web-llvm/docs/api/classes/llvm/orc/shared/spstuple">SPSTuple</a>&lt; <a href="#a3b101487ee72cf9033225840204e68bb">SPSString</a>, uint64_t, <a href="/web-llvm/docs/api/classes/llvm/orc/shared/spssequence">SPSSequence</a>&lt; <a href="/web-llvm/docs/api/classes/llvm/orc/shared/spstuple">SPSTuple</a>&lt; <a href="#a3b101487ee72cf9033225840204e68bb">SPSString</a>, <a href="/web-llvm/docs/api/classes/llvm/orc/shared/spssequence">SPSSequence</a>&lt; char &gt; &gt; &gt;, <a href="/web-llvm/docs/api/classes/llvm/orc/shared/spssequence">SPSSequence</a>&lt; <a href="/web-llvm/docs/api/classes/llvm/orc/shared/spstuple">SPSTuple</a>&lt; <a href="#a3b101487ee72cf9033225840204e68bb">SPSString</a>, <a href="/web-llvm/docs/api/classes/llvm/orc/shared/spsexecutoraddr">SPSExecutorAddr</a> &gt; &gt; &gt;</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Tuple containing target triple, page size, and bootstrap symbols. <a href="#a59137420a08264e9deb791025a69564a">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">using</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ae1e526f8e244d506e1183003a3f9c190">SPSLoadDylibSignature</a> = <a href="/web-llvm/docs/api/classes/llvm/orc/shared/spsexpected">SPSExpected</a>&lt; <a href="/web-llvm/docs/api/classes/llvm/orc/shared/spsexecutoraddr">SPSExecutorAddr</a> &gt;(<a href="/web-llvm/docs/api/classes/llvm/orc/shared/spsexecutoraddr">SPSExecutorAddr</a>, <a href="#a3b101487ee72cf9033225840204e68bb">SPSString</a>, uint64_t)</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a2e1f5547fff97a7b98e45c1eb859d85c">SPSLookupSymbolsSignature</a> = <a href="/web-llvm/docs/api/classes/llvm/orc/shared/spsexpected">SPSExpected</a>&lt; <a href="/web-llvm/docs/api/classes/llvm/orc/shared/spssequence">SPSSequence</a>&lt; <a href="/web-llvm/docs/api/classes/llvm/orc/shared/spssequence">SPSSequence</a>&lt; <a href="/web-llvm/docs/api/classes/llvm/orc/shared/spsexecutoraddr">SPSExecutorAddr</a> &gt; &gt; &gt;( <a href="/web-llvm/docs/api/classes/llvm/orc/shared/spsexecutoraddr">SPSExecutorAddr</a>, <a href="/web-llvm/docs/api/classes/llvm/orc/shared/spssequence">SPSSequence</a>&lt; <a href="#aa3c3ea30847f43c1075fb13d02fc457a">SPSRemoteSymbolLookup</a> &gt;)</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#af22bbbfb9701abad2eb1f6688bb7ac24">SPSSegFinalizeRequest</a> = <a href="/web-llvm/docs/api/classes/llvm/orc/shared/spstuple">SPSTuple</a>&lt; SPSRemoteAllocGroup, <a href="/web-llvm/docs/api/classes/llvm/orc/shared/spsexecutoraddr">SPSExecutorAddr</a>, uint64_t, <a href="/web-llvm/docs/api/classes/llvm/orc/shared/spssequence">SPSSequence</a>&lt; char &gt; &gt;</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a35b277daedca31091f550803ef8834c0">SPSFinalizeRequest</a> = <a href="/web-llvm/docs/api/classes/llvm/orc/shared/spstuple">SPSTuple</a>&lt; <a href="/web-llvm/docs/api/classes/llvm/orc/shared/spssequence">SPSSequence</a>&lt; <a href="#af22bbbfb9701abad2eb1f6688bb7ac24">SPSSegFinalizeRequest</a> &gt;, <a href="/web-llvm/docs/api/classes/llvm/orc/shared/spssequence">SPSSequence</a>&lt; <a href="#aaf20479822b924307d388261f4bb1159">SPSAllocActionCallPair</a> &gt; &gt;</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ac44c043807d31d44e93725a2d3ccf237">SPSSharedMemorySegFinalizeRequest</a> = <a href="/web-llvm/docs/api/classes/llvm/orc/shared/spstuple">SPSTuple</a>&lt; SPSRemoteAllocGroup, <a href="/web-llvm/docs/api/classes/llvm/orc/shared/spsexecutoraddr">SPSExecutorAddr</a>, uint64_t &gt;</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#aa747eff51a403ae9b4d7a429b63cbfc7">SPSSharedMemoryFinalizeRequest</a> = <a href="/web-llvm/docs/api/classes/llvm/orc/shared/spstuple">SPSTuple</a>&lt; <a href="/web-llvm/docs/api/classes/llvm/orc/shared/spssequence">SPSSequence</a>&lt; <a href="#ac44c043807d31d44e93725a2d3ccf237">SPSSharedMemorySegFinalizeRequest</a> &gt;, <a href="/web-llvm/docs/api/classes/llvm/orc/shared/spssequence">SPSSequence</a>&lt; <a href="#aaf20479822b924307d388261f4bb1159">SPSAllocActionCallPair</a> &gt; &gt;</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexTemplate">
<td class="doxyMemberIndexTemplate" colspan="2"><div>template &lt;typename T&gt;</div></td>
</tr>
<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemTypeTemplate" align="left" valign="top">using</td>
<td class="doxyMemberIndexItemNameTemplate" align="left" valign="top"><a href="#a21a2a0fe8646c6c1644a53b958052140">SPSMemoryAccessUIntWrite</a> = <a href="/web-llvm/docs/api/classes/llvm/orc/shared/spstuple">SPSTuple</a>&lt; <a href="/web-llvm/docs/api/classes/llvm/orc/shared/spsexecutoraddr">SPSExecutorAddr</a>, T &gt;</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a366a1c17ed2f1bfa82440bec79562539">SPSMemoryAccessUInt8Write</a> = <a href="#a21a2a0fe8646c6c1644a53b958052140">SPSMemoryAccessUIntWrite</a>&lt; uint8_t &gt;</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a473c1f44e358211e2e2884b5c18c8739">SPSMemoryAccessUInt16Write</a> = <a href="#a21a2a0fe8646c6c1644a53b958052140">SPSMemoryAccessUIntWrite</a>&lt; uint16_t &gt;</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ada94a49624061fcb74ac5f345ebf9b47">SPSMemoryAccessUInt32Write</a> = <a href="#a21a2a0fe8646c6c1644a53b958052140">SPSMemoryAccessUIntWrite</a>&lt; uint32_t &gt;</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#abb49291ab901453b8022fe8c209e2816">SPSMemoryAccessUInt64Write</a> = <a href="#a21a2a0fe8646c6c1644a53b958052140">SPSMemoryAccessUIntWrite</a>&lt; uint64_t &gt;</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a1f35b361296e6a966c9b234555663e83">SPSMemoryAccessBufferWrite</a> = <a href="/web-llvm/docs/api/classes/llvm/orc/shared/spstuple">SPSTuple</a>&lt; <a href="/web-llvm/docs/api/classes/llvm/orc/shared/spsexecutoraddr">SPSExecutorAddr</a>, <a href="/web-llvm/docs/api/classes/llvm/orc/shared/spssequence">SPSSequence</a>&lt; char &gt; &gt;</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a038ec884d4dfa8c4e139dab99cce3867">SPSMemoryAccessPointerWrite</a> = <a href="/web-llvm/docs/api/classes/llvm/orc/shared/spstuple">SPSTuple</a>&lt; <a href="/web-llvm/docs/api/classes/llvm/orc/shared/spsexecutoraddr">SPSExecutorAddr</a>, <a href="/web-llvm/docs/api/classes/llvm/orc/shared/spsexecutoraddr">SPSExecutorAddr</a> &gt;</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ad9a23c25caf1236edf28c57bf0a99f50">SPSVTuneLineTable</a> = <a href="/web-llvm/docs/api/classes/llvm/orc/shared/spssequence">SPSSequence</a>&lt; <a href="/web-llvm/docs/api/classes/llvm/orc/shared/spstuple">SPSTuple</a>&lt; uint32_t, uint32_t &gt; &gt;</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a0826d6988ed0701fab900be1955bd5c4">SPSVTuneMethodInfo</a> = <a href="/web-llvm/docs/api/classes/llvm/orc/shared/spstuple">SPSTuple</a>&lt; <a href="#ad9a23c25caf1236edf28c57bf0a99f50">SPSVTuneLineTable</a>, <a href="/web-llvm/docs/api/classes/llvm/orc/shared/spsexecutoraddr">SPSExecutorAddr</a>, uint64_t, uint64_t, uint32_t, uint32_t, uint32_t, uint32_t &gt;</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#afd9a4ba9a92bb5cb3e21f2888c49c9ce">SPSVTuneMethodTable</a> = <a href="/web-llvm/docs/api/classes/llvm/orc/shared/spssequence">SPSSequence</a>&lt; <a href="#a0826d6988ed0701fab900be1955bd5c4">SPSVTuneMethodInfo</a> &gt;</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#aa11ac17eb36e30714745eca2cc24be41">SPSVTuneStringTable</a> = <a href="/web-llvm/docs/api/classes/llvm/orc/shared/spssequence">SPSSequence</a>&lt; <a href="#a3b101487ee72cf9033225840204e68bb">SPSString</a> &gt;</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a9983826caf04ffd668754806d230725c">SPSVTuneMethodBatch</a> = <a href="/web-llvm/docs/api/classes/llvm/orc/shared/spstuple">SPSTuple</a>&lt; <a href="#afd9a4ba9a92bb5cb3e21f2888c49c9ce">SPSVTuneMethodTable</a>, <a href="#aa11ac17eb36e30714745eca2cc24be41">SPSVTuneStringTable</a> &gt;</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#acb5ae9c28716651ce56207d60a55db52">SPSVTuneUnloadedMethodIDs</a> = <a href="/web-llvm/docs/api/classes/llvm/orc/shared/spssequence">SPSSequence</a>&lt; <a href="/web-llvm/docs/api/classes/llvm/orc/shared/spstuple">SPSTuple</a>&lt; uint64_t, uint64_t &gt; &gt;</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a99ed71ed35a3aed5a6a7ca164c750dad">SPSWrapperFunctionCall</a> = <a href="/web-llvm/docs/api/classes/llvm/orc/shared/spstuple">SPSTuple</a>&lt; <a href="/web-llvm/docs/api/classes/llvm/orc/shared/spsexecutoraddr">SPSExecutorAddr</a>, <a href="/web-llvm/docs/api/classes/llvm/orc/shared/spssequence">SPSSequence</a>&lt; char &gt; &gt;</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a1560488a576630ed0353640a48590f71">SPSCOFFJITDylibDepInfo</a> = <a href="/web-llvm/docs/api/classes/llvm/orc/shared/spssequence">SPSSequence</a>&lt; <a href="/web-llvm/docs/api/classes/llvm/orc/shared/spsexecutoraddr">SPSExecutorAddr</a> &gt;</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a909ddd6e036ef92df6744a617002430c">SPSCOFFJITDylibDepInfoMap</a> = <a href="/web-llvm/docs/api/classes/llvm/orc/shared/spssequence">SPSSequence</a>&lt; <a href="/web-llvm/docs/api/classes/llvm/orc/shared/spstuple">SPSTuple</a>&lt; <a href="/web-llvm/docs/api/classes/llvm/orc/shared/spsexecutoraddr">SPSExecutorAddr</a>, <a href="#a1560488a576630ed0353640a48590f71">SPSCOFFJITDylibDepInfo</a> &gt; &gt;</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a427372506e092aa98324f5621e89083c">SPSCOFFObjectSectionsMap</a> = <a href="/web-llvm/docs/api/classes/llvm/orc/shared/spssequence">SPSSequence</a>&lt; <a href="/web-llvm/docs/api/classes/llvm/orc/shared/spstuple">SPSTuple</a>&lt; <a href="#a3b101487ee72cf9033225840204e68bb">SPSString</a>, <a href="#aa48e4738482db923f95f0667a440aea4">SPSExecutorAddrRange</a> &gt; &gt;</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a3db5ab78de8866241cd1c20698ace321">SPSCOFFRegisterObjectSectionsArgs</a> = <a href="/web-llvm/docs/api/classes/llvm/orc/shared/spsarglist">SPSArgList</a>&lt; <a href="/web-llvm/docs/api/classes/llvm/orc/shared/spsexecutoraddr">SPSExecutorAddr</a>, <a href="#a427372506e092aa98324f5621e89083c">SPSCOFFObjectSectionsMap</a>, bool &gt;</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ae936157092ce93bdbd3fe43cb265f5e9">SPSCOFFDeregisterObjectSectionsArgs</a> = <a href="/web-llvm/docs/api/classes/llvm/orc/shared/spsarglist">SPSArgList</a>&lt; <a href="/web-llvm/docs/api/classes/llvm/orc/shared/spsexecutoraddr">SPSExecutorAddr</a>, <a href="#a427372506e092aa98324f5621e89083c">SPSCOFFObjectSectionsMap</a> &gt;</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a6cc85dca9bd6dbcafb664f4413bdd828">SPSMachOJITDylibDepInfo</a> = <a href="/web-llvm/docs/api/classes/llvm/orc/shared/spstuple">SPSTuple</a>&lt; bool, <a href="/web-llvm/docs/api/classes/llvm/orc/shared/spssequence">SPSSequence</a>&lt; <a href="/web-llvm/docs/api/classes/llvm/orc/shared/spsexecutoraddr">SPSExecutorAddr</a> &gt; &gt;</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a71ed2e9de678a6504c9cfbd6fddc55b9">SPSMachOJITDylibDepInfoMap</a> = <a href="/web-llvm/docs/api/classes/llvm/orc/shared/spssequence">SPSSequence</a>&lt; <a href="/web-llvm/docs/api/classes/llvm/orc/shared/spstuple">SPSTuple</a>&lt; <a href="/web-llvm/docs/api/classes/llvm/orc/shared/spsexecutoraddr">SPSExecutorAddr</a>, <a href="#a6cc85dca9bd6dbcafb664f4413bdd828">SPSMachOJITDylibDepInfo</a> &gt; &gt;</td>
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

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">size_t</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a803f10b1184f06380dadea58c07912f4">numDeallocActions</a> (const AllocActions &amp;AAs)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Returns the number of deallocaton actions in the given <a href="#a6da0b5cb8e68a6cc791a183d9d38aae0">AllocActions</a> array. <a href="#a803f10b1184f06380dadea58c07912f4">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/expected">Expected</a>&lt; std::vector&lt; <a href="/web-llvm/docs/api/classes/llvm/orc/shared/wrapperfunctioncall">WrapperFunctionCall</a> &gt; &gt;</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#aa02467cf9213727cd36bce6f59653e5b">runFinalizeActions</a> (AllocActions &amp;AAs)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Run finalize actions. <a href="#aa02467cf9213727cd36bce6f59653e5b">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/error">Error</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a8263d385de2b406acf8dbef9b0993cc9">runDeallocActions</a> (ArrayRef&lt; WrapperFunctionCall &gt; DAs)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Run deallocation actions. <a href="#a8263d385de2b406acf8dbef9b0993cc9">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexTemplate">
<td class="doxyMemberIndexTemplate" colspan="2"><div>template &lt;typename RetT, typename ClassT, typename... ArgTs&gt;</div></td>
</tr>
<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemTypeTemplate" align="left" valign="top">auto </td>
<td class="doxyMemberIndexItemNameTemplate" align="left" valign="top"><a href="#a22daede26acd2cbd316d09f0c21e12dd">makeMethodWrapperHandler</a> (RetT(ClassT::*Method)(ArgTs...)) -&gt; <a href="/web-llvm/docs/api/classes/llvm/orc/shared/methodwrapperhandler">MethodWrapperHandler</a>&lt; RetT, ClassT, ArgTs... &gt;</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Create a <a href="/web-llvm/docs/api/classes/llvm/orc/shared/methodwrapperhandler">MethodWrapperHandler</a> object from the given method pointer. <a href="#a22daede26acd2cbd316d09f0c21e12dd">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

</table>


<div class="doxySectionDef">

## Typedefs

### AllocActions {#a6da0b5cb8e68a6cc791a183d9d38aae0}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">using llvm::orc::shared::AllocActions =  std::vector&lt;AllocActionCallPair&gt;</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>A vector of allocation actions to be run for this allocation.</p>


<p>Finalize allocations will be run in order at finalize time. Dealloc actions will be run in reverse order at deallocation time.</p>


<p>Definition at line 44 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/executionengine/include/llvm/executionengine/orc/include/llvm/executionengine/orc/shared/allocationactions-h">AllocationActions.h</a>.</p>

</div>
</div>

### SPSAllocActionCallPair {#aaf20479822b924307d388261f4bb1159}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">using llvm::orc::shared::SPSAllocActionCallPair = 
    SPSTuple&lt;SPSWrapperFunctionCall, SPSWrapperFunctionCall&gt;</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 73 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/executionengine/include/llvm/executionengine/orc/include/llvm/executionengine/orc/shared/allocationactions-h">AllocationActions.h</a>.</p>

</div>
</div>

### SPSCOFFDeregisterObjectSectionsArgs {#ae936157092ce93bdbd3fe43cb265f5e9}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">using llvm::orc::shared::SPSCOFFDeregisterObjectSectionsArgs = 
    SPSArgList&lt;SPSExecutorAddr, SPSCOFFObjectSectionsMap&gt;</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 39 of file <a href="/web-llvm/docs/api/files/lib/lib/executionengine/lib/executionengine/orc/coffplatform-cpp">COFFPlatform.cpp</a>.</p>

</div>
</div>

### SPSCOFFJITDylibDepInfo {#a1560488a576630ed0353640a48590f71}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">using llvm::orc::shared::SPSCOFFJITDylibDepInfo =  SPSSequence&lt;SPSExecutorAddr&gt;</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 32 of file <a href="/web-llvm/docs/api/files/lib/lib/executionengine/lib/executionengine/orc/coffplatform-cpp">COFFPlatform.cpp</a>.</p>

</div>
</div>

### SPSCOFFJITDylibDepInfoMap {#a909ddd6e036ef92df6744a617002430c}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">using llvm::orc::shared::SPSCOFFJITDylibDepInfoMap = 
    SPSSequence&lt;SPSTuple&lt;SPSExecutorAddr, SPSCOFFJITDylibDepInfo&gt;&gt;</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 33 of file <a href="/web-llvm/docs/api/files/lib/lib/executionengine/lib/executionengine/orc/coffplatform-cpp">COFFPlatform.cpp</a>.</p>

</div>
</div>

### SPSCOFFObjectSectionsMap {#a427372506e092aa98324f5621e89083c}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">using llvm::orc::shared::SPSCOFFObjectSectionsMap = 
    SPSSequence&lt;SPSTuple&lt;SPSString, SPSExecutorAddrRange&gt;&gt;</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 35 of file <a href="/web-llvm/docs/api/files/lib/lib/executionengine/lib/executionengine/orc/coffplatform-cpp">COFFPlatform.cpp</a>.</p>

</div>
</div>

### SPSCOFFRegisterObjectSectionsArgs {#a3db5ab78de8866241cd1c20698ace321}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">using llvm::orc::shared::SPSCOFFRegisterObjectSectionsArgs = 
    SPSArgList&lt;SPSExecutorAddr, SPSCOFFObjectSectionsMap, bool&gt;</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 37 of file <a href="/web-llvm/docs/api/files/lib/lib/executionengine/lib/executionengine/orc/coffplatform-cpp">COFFPlatform.cpp</a>.</p>

</div>
</div>

### SPSELFNixJITDylibDepInfoMap {#a7c37debf020343319cd5515b321a05b6}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">using llvm::orc::shared::SPSELFNixJITDylibDepInfoMap = 
    SPSSequence&lt;SPSTuple&lt;SPSExecutorAddr, SPSSequence&lt;SPSExecutorAddr&gt;&gt;&gt;</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 309 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/executionengine/include/llvm/executionengine/orc/elfnixplatform-h">ELFNixPlatform.h</a>.</p>

</div>
</div>

### SPSELFPerObjectSectionsToRegister {#a1c4c7365247c5364b0183da327176a04}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">using llvm::orc::shared::SPSELFPerObjectSectionsToRegister = 
    SPSTuple&lt;SPSExecutorAddrRange, SPSExecutorAddrRange&gt;</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 283 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/executionengine/include/llvm/executionengine/orc/elfnixplatform-h">ELFNixPlatform.h</a>.</p>

</div>
</div>

### SPSExecutorAddrRange {#aa48e4738482db923f95f0667a440aea4}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">using llvm::orc::shared::SPSExecutorAddrRange =  SPSTuple&lt;SPSExecutorAddr, SPSExecutorAddr&gt;</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 302 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/executionengine/include/llvm/executionengine/orc/include/llvm/executionengine/orc/shared/executoraddress-h">ExecutorAddress.h</a>.</p>

</div>
</div>

### SPSExecutorAddrRangeSequence {#a1b3495ab143f17c8ab3ffbf1e167dfed}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">using llvm::orc::shared::SPSExecutorAddrRangeSequence =  SPSSequence&lt;SPSExecutorAddrRange&gt;</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 324 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/executionengine/include/llvm/executionengine/orc/include/llvm/executionengine/orc/shared/executoraddress-h">ExecutorAddress.h</a>.</p>

</div>
</div>

### SPSExecutorSymbolDef {#a2e25123fcbb940292ea9a1f907924952}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">using llvm::orc::shared::SPSExecutorSymbolDef =  SPSTuple&lt;SPSExecutorAddr, SPSJITSymbolFlags&gt;</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 113 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/executionengine/include/llvm/executionengine/orc/include/llvm/executionengine/orc/shared/executorsymboldef-h">ExecutorSymbolDef.h</a>.</p>

</div>
</div>

### SPSFinalizeRequest {#a35b277daedca31091f550803ef8834c0}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">using llvm::orc::shared::SPSFinalizeRequest =  SPSTuple&lt;SPSSequence&lt;SPSSegFinalizeRequest&gt;,
                                    SPSSequence&lt;SPSAllocActionCallPair&gt;&gt;</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 128 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/executionengine/include/llvm/executionengine/orc/include/llvm/executionengine/orc/shared/targetprocesscontroltypes-h">TargetProcessControlTypes.h</a>.</p>

</div>
</div>

### SPSJITSymbolFlags {#a0295b4b8235c6c45e3d630f59a879547}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">using llvm::orc::shared::SPSJITSymbolFlags = 
    SPSTuple&lt;JITSymbolFlags::UnderlyingType, JITSymbolFlags::TargetFlagsType&gt;</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 85 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/executionengine/include/llvm/executionengine/orc/include/llvm/executionengine/orc/shared/executorsymboldef-h">ExecutorSymbolDef.h</a>.</p>

</div>
</div>

### SPSLoadDylibSignature {#ae1e526f8e244d506e1183003a3f9c190}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">using llvm::orc::shared::SPSLoadDylibSignature =  SPSExpected&lt;SPSExecutorAddr&gt;(SPSExecutorAddr,
                                                           SPSString, uint64_t)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 226 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/executionengine/include/llvm/executionengine/orc/include/llvm/executionengine/orc/shared/simpleremoteepcutils-h">SimpleRemoteEPCUtils.h</a>.</p>

</div>
</div>

### SPSLookupSymbolsSignature {#a2e1f5547fff97a7b98e45c1eb859d85c}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">using llvm::orc::shared::SPSLookupSymbolsSignature = 
    SPSExpected&lt;SPSSequence&lt;SPSSequence&lt;SPSExecutorAddr&gt;&gt;&gt;(
        SPSExecutorAddr, SPSSequence&lt;SPSRemoteSymbolLookup&gt;)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 229 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/executionengine/include/llvm/executionengine/orc/include/llvm/executionengine/orc/shared/simpleremoteepcutils-h">SimpleRemoteEPCUtils.h</a>.</p>

</div>
</div>

### SPSMachOJITDylibDepInfo {#a6cc85dca9bd6dbcafb664f4413bdd828}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">using llvm::orc::shared::SPSMachOJITDylibDepInfo =  SPSTuple&lt;bool, SPSSequence&lt;SPSExecutorAddr&gt;&gt;</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 32 of file <a href="/web-llvm/docs/api/files/lib/lib/executionengine/lib/executionengine/orc/machoplatform-cpp">MachOPlatform.cpp</a>.</p>

</div>
</div>

### SPSMachOJITDylibDepInfoMap {#a71ed2e9de678a6504c9cfbd6fddc55b9}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">using llvm::orc::shared::SPSMachOJITDylibDepInfoMap = 
    SPSSequence&lt;SPSTuple&lt;SPSExecutorAddr, SPSMachOJITDylibDepInfo&gt;&gt;</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 33 of file <a href="/web-llvm/docs/api/files/lib/lib/executionengine/lib/executionengine/orc/machoplatform-cpp">MachOPlatform.cpp</a>.</p>

</div>
</div>

### SPSMap {#a24d34cffd0fe2ca8a39d38b4a1d18474}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<div class="doxyMemberTemplate">template &lt;typename SPSTagT1, typename SPSTagT2&gt;</div>
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">using llvm::orc::shared::SPSMap =  SPSSequence&lt;SPSTuple&lt;SPSTagT1, SPSTagT2&gt;&gt;</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>SPS tag type for maps.</p>


<p>SPS maps are just sequences of (Key, <a href="/web-llvm/docs/api/classes/llvm/value">Value</a>) tuples.</p>


<p>Definition at line 223 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/executionengine/include/llvm/executionengine/orc/include/llvm/executionengine/orc/shared/simplepackedserialization-h">SimplePackedSerialization.h</a>.</p>

</div>
</div>

### SPSMemoryAccessBufferWrite {#a1f35b361296e6a966c9b234555663e83}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">using llvm::orc::shared::SPSMemoryAccessBufferWrite =  SPSTuple&lt;SPSExecutorAddr, SPSSequence&lt;char&gt;&gt;</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 146 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/executionengine/include/llvm/executionengine/orc/include/llvm/executionengine/orc/shared/targetprocesscontroltypes-h">TargetProcessControlTypes.h</a>.</p>

</div>
</div>

### SPSMemoryAccessPointerWrite {#a038ec884d4dfa8c4e139dab99cce3867}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">using llvm::orc::shared::SPSMemoryAccessPointerWrite =  SPSTuple&lt;SPSExecutorAddr, SPSExecutorAddr&gt;</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 147 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/executionengine/include/llvm/executionengine/orc/include/llvm/executionengine/orc/shared/targetprocesscontroltypes-h">TargetProcessControlTypes.h</a>.</p>

</div>
</div>

### SPSMemoryAccessUInt16Write {#a473c1f44e358211e2e2884b5c18c8739}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">using llvm::orc::shared::SPSMemoryAccessUInt16Write =  SPSMemoryAccessUIntWrite&lt;uint16_t&gt;</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 142 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/executionengine/include/llvm/executionengine/orc/include/llvm/executionengine/orc/shared/targetprocesscontroltypes-h">TargetProcessControlTypes.h</a>.</p>

</div>
</div>

### SPSMemoryAccessUInt32Write {#ada94a49624061fcb74ac5f345ebf9b47}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">using llvm::orc::shared::SPSMemoryAccessUInt32Write =  SPSMemoryAccessUIntWrite&lt;uint32_t&gt;</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 143 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/executionengine/include/llvm/executionengine/orc/include/llvm/executionengine/orc/shared/targetprocesscontroltypes-h">TargetProcessControlTypes.h</a>.</p>

</div>
</div>

### SPSMemoryAccessUInt64Write {#abb49291ab901453b8022fe8c209e2816}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">using llvm::orc::shared::SPSMemoryAccessUInt64Write =  SPSMemoryAccessUIntWrite&lt;uint64_t&gt;</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 144 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/executionengine/include/llvm/executionengine/orc/include/llvm/executionengine/orc/shared/targetprocesscontroltypes-h">TargetProcessControlTypes.h</a>.</p>

</div>
</div>

### SPSMemoryAccessUInt8Write {#a366a1c17ed2f1bfa82440bec79562539}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">using llvm::orc::shared::SPSMemoryAccessUInt8Write =  SPSMemoryAccessUIntWrite&lt;uint8_t&gt;</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 141 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/executionengine/include/llvm/executionengine/orc/include/llvm/executionengine/orc/shared/targetprocesscontroltypes-h">TargetProcessControlTypes.h</a>.</p>

</div>
</div>

### SPSMemoryAccessUIntWrite {#a21a2a0fe8646c6c1644a53b958052140}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<div class="doxyMemberTemplate">template &lt;typename T&gt;</div>
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">using llvm::orc::shared::SPSMemoryAccessUIntWrite =  SPSTuple&lt;SPSExecutorAddr, T&gt;</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 139 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/executionengine/include/llvm/executionengine/orc/include/llvm/executionengine/orc/shared/targetprocesscontroltypes-h">TargetProcessControlTypes.h</a>.</p>

</div>
</div>

### SPSPerfJITCodeLoadRecord {#a229d8f55458fe47f2d874ec647efefc9}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">using llvm::orc::shared::SPSPerfJITCodeLoadRecord = 
    SPSTuple&lt;SPSPerfJITRecordPrefix, uint32_t, uint32_t, uint64_t, uint64_t,
             uint64_t, uint64_t, SPSString&gt;</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 112 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/executionengine/include/llvm/executionengine/orc/include/llvm/executionengine/orc/shared/perfsharedstructs-h">PerfSharedStructs.h</a>.</p>

</div>
</div>

### SPSPerfJITCodeUnwindingInfoRecord {#a0578094f53cbed5cabb13da9cb5f664a}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">using llvm::orc::shared::SPSPerfJITCodeUnwindingInfoRecord = 
    SPSTuple&lt;SPSPerfJITRecordPrefix, uint64_t, uint64_t, uint64_t, uint64_t,
             SPSString, uint64_t&gt;</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 181 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/executionengine/include/llvm/executionengine/orc/include/llvm/executionengine/orc/shared/perfsharedstructs-h">PerfSharedStructs.h</a>.</p>

</div>
</div>

### SPSPerfJITDebugEntry {#ae405e3e3dbf8ee11685677d3c6df3451}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">using llvm::orc::shared::SPSPerfJITDebugEntry =  SPSTuple&lt;uint64_t, uint32_t, uint32_t, SPSString&gt;</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 138 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/executionengine/include/llvm/executionengine/orc/include/llvm/executionengine/orc/shared/perfsharedstructs-h">PerfSharedStructs.h</a>.</p>

</div>
</div>

### SPSPerfJITDebugInfoRecord {#a90b01e023242207373817d7ffc8d3402}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">using llvm::orc::shared::SPSPerfJITDebugInfoRecord =  SPSTuple&lt;SPSPerfJITRecordPrefix, uint64_t,
                                           SPSSequence&lt;SPSPerfJITDebugEntry&gt;&gt;</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 159 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/executionengine/include/llvm/executionengine/orc/include/llvm/executionengine/orc/shared/perfsharedstructs-h">PerfSharedStructs.h</a>.</p>

</div>
</div>

### SPSPerfJITRecordBatch {#a5154edf9dc098d48b5d3972eb81ad5c3}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">using llvm::orc::shared::SPSPerfJITRecordBatch =  SPSTuple&lt;SPSSequence&lt;SPSPerfJITCodeLoadRecord&gt;,
                                       SPSSequence&lt;SPSPerfJITDebugInfoRecord&gt;,
                                       SPSPerfJITCodeUnwindingInfoRecord&gt;</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 207 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/executionengine/include/llvm/executionengine/orc/include/llvm/executionengine/orc/shared/perfsharedstructs-h">PerfSharedStructs.h</a>.</p>

</div>
</div>

### SPSPerfJITRecordPrefix {#a18a3a6ce95408493d152bbe2def15947}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">using llvm::orc::shared::SPSPerfJITRecordPrefix =  SPSTuple&lt;uint32_t, uint32_t&gt;</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 90 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/executionengine/include/llvm/executionengine/orc/include/llvm/executionengine/orc/shared/perfsharedstructs-h">PerfSharedStructs.h</a>.</p>

</div>
</div>

### SPSRemoteSymbolLookup {#aa3c3ea30847f43c1075fb13d02fc457a}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">using llvm::orc::shared::SPSRemoteSymbolLookup =  SPSTuple&lt;uint64_t, SPSRemoteSymbolLookupSet&gt;</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 160 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/executionengine/include/llvm/executionengine/orc/include/llvm/executionengine/orc/shared/simpleremoteepcutils-h">SimpleRemoteEPCUtils.h</a>.</p>

</div>
</div>

### SPSRemoteSymbolLookupSet {#aa4683bc096f3b0cd8be3e2bcfa5924fa}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">using llvm::orc::shared::SPSRemoteSymbolLookupSet =  SPSSequence&lt;SPSRemoteSymbolLookupSetElement&gt;</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 158 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/executionengine/include/llvm/executionengine/orc/include/llvm/executionengine/orc/shared/simpleremoteepcutils-h">SimpleRemoteEPCUtils.h</a>.</p>

</div>
</div>

### SPSRemoteSymbolLookupSetElement {#a61d90db1bc867d756c6431a7aac12b2b}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">using llvm::orc::shared::SPSRemoteSymbolLookupSetElement =  SPSTuple&lt;SPSString, bool&gt;</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 156 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/executionengine/include/llvm/executionengine/orc/include/llvm/executionengine/orc/shared/simpleremoteepcutils-h">SimpleRemoteEPCUtils.h</a>.</p>

</div>
</div>

### SPSSegFinalizeRequest {#af22bbbfb9701abad2eb1f6688bb7ac24}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">using llvm::orc::shared::SPSSegFinalizeRequest = 
    SPSTuple&lt;SPSRemoteAllocGroup, SPSExecutorAddr, uint64_t, SPSSequence&lt;char&gt;&gt;</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 125 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/executionengine/include/llvm/executionengine/orc/include/llvm/executionengine/orc/shared/targetprocesscontroltypes-h">TargetProcessControlTypes.h</a>.</p>

</div>
</div>

### SPSSharedMemoryFinalizeRequest {#aa747eff51a403ae9b4d7a429b63cbfc7}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">using llvm::orc::shared::SPSSharedMemoryFinalizeRequest = 
    SPSTuple&lt;SPSSequence&lt;SPSSharedMemorySegFinalizeRequest&gt;,
             SPSSequence&lt;SPSAllocActionCallPair&gt;&gt;</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 134 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/executionengine/include/llvm/executionengine/orc/include/llvm/executionengine/orc/shared/targetprocesscontroltypes-h">TargetProcessControlTypes.h</a>.</p>

</div>
</div>

### SPSSharedMemorySegFinalizeRequest {#ac44c043807d31d44e93725a2d3ccf237}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">using llvm::orc::shared::SPSSharedMemorySegFinalizeRequest = 
    SPSTuple&lt;SPSRemoteAllocGroup, SPSExecutorAddr, uint64_t&gt;</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 131 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/executionengine/include/llvm/executionengine/orc/include/llvm/executionengine/orc/shared/targetprocesscontroltypes-h">TargetProcessControlTypes.h</a>.</p>

</div>
</div>

### SPSSimpleRemoteEPCExecutorInfo {#a59137420a08264e9deb791025a69564a}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">using llvm::orc::shared::SPSSimpleRemoteEPCExecutorInfo = 
    SPSTuple&lt;SPSString, uint64_t,
             SPSSequence&lt;SPSTuple&lt;SPSString, SPSSequence&lt;char&gt;&gt;&gt;,
             SPSSequence&lt;SPSTuple&lt;SPSString, SPSExecutorAddr&gt;&gt;&gt;</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Tuple containing target triple, page size, and bootstrap symbols.</p>

<p>Definition at line 163 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/executionengine/include/llvm/executionengine/orc/include/llvm/executionengine/orc/shared/simpleremoteepcutils-h">SimpleRemoteEPCUtils.h</a>.</p>

</div>
</div>

### SPSString {#a3b101487ee72cf9033225840204e68bb}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">using llvm::orc::shared::SPSString =  SPSSequence&lt;char&gt;</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>SPS tag type for strings, which are equivalent to sequences of chars.</p>

<p>Definition at line 217 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/executionengine/include/llvm/executionengine/orc/include/llvm/executionengine/orc/shared/simplepackedserialization-h">SimplePackedSerialization.h</a>.</p>

</div>
</div>

### SPSVTuneLineTable {#ad9a23c25caf1236edf28c57bf0a99f50}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">using llvm::orc::shared::SPSVTuneLineTable =  SPSSequence&lt;SPSTuple&lt;uint32_t, uint32_t&gt;&gt;</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 54 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/executionengine/include/llvm/executionengine/orc/include/llvm/executionengine/orc/shared/vtunesharedstructs-h">VTuneSharedStructs.h</a>.</p>

</div>
</div>

### SPSVTuneMethodBatch {#a9983826caf04ffd668754806d230725c}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">using llvm::orc::shared::SPSVTuneMethodBatch =  SPSTuple&lt;SPSVTuneMethodTable, SPSVTuneStringTable&gt;</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 60 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/executionengine/include/llvm/executionengine/orc/include/llvm/executionengine/orc/shared/vtunesharedstructs-h">VTuneSharedStructs.h</a>.</p>

</div>
</div>

### SPSVTuneMethodInfo {#a0826d6988ed0701fab900be1955bd5c4}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">using llvm::orc::shared::SPSVTuneMethodInfo = 
    SPSTuple&lt;SPSVTuneLineTable, SPSExecutorAddr, uint64_t, uint64_t, uint32_t,
             uint32_t, uint32_t, uint32_t&gt;</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 55 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/executionengine/include/llvm/executionengine/orc/include/llvm/executionengine/orc/shared/vtunesharedstructs-h">VTuneSharedStructs.h</a>.</p>

</div>
</div>

### SPSVTuneMethodTable {#afd9a4ba9a92bb5cb3e21f2888c49c9ce}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">using llvm::orc::shared::SPSVTuneMethodTable =  SPSSequence&lt;SPSVTuneMethodInfo&gt;</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 58 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/executionengine/include/llvm/executionengine/orc/include/llvm/executionengine/orc/shared/vtunesharedstructs-h">VTuneSharedStructs.h</a>.</p>

</div>
</div>

### SPSVTuneStringTable {#aa11ac17eb36e30714745eca2cc24be41}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">using llvm::orc::shared::SPSVTuneStringTable =  SPSSequence&lt;SPSString&gt;</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 59 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/executionengine/include/llvm/executionengine/orc/include/llvm/executionengine/orc/shared/vtunesharedstructs-h">VTuneSharedStructs.h</a>.</p>

</div>
</div>

### SPSVTuneUnloadedMethodIDs {#acb5ae9c28716651ce56207d60a55db52}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">using llvm::orc::shared::SPSVTuneUnloadedMethodIDs =  SPSSequence&lt;SPSTuple&lt;uint64_t, uint64_t&gt;&gt;</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 61 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/executionengine/include/llvm/executionengine/orc/include/llvm/executionengine/orc/shared/vtunesharedstructs-h">VTuneSharedStructs.h</a>.</p>

</div>
</div>

### SPSWrapperFunctionCall {#a99ed71ed35a3aed5a6a7ca164c750dad}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">using llvm::orc::shared::SPSWrapperFunctionCall =  SPSTuple&lt;SPSExecutorAddr, SPSSequence&lt;char&gt;&gt;</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 710 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/executionengine/include/llvm/executionengine/orc/include/llvm/executionengine/orc/shared/wrapperfunctionutils-h">WrapperFunctionUtils.h</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Functions

### makeMethodWrapperHandler() {#a22daede26acd2cbd316d09f0c21e12dd}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<div class="doxyMemberTemplate">template &lt;typename RetT, typename ClassT, typename... ArgTs&gt;</div>
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">MethodWrapperHandler&lt; RetT, ClassT, ArgTs... &gt; llvm::orc::shared::makeMethodWrapperHandler (RetT(ClassT::*)(ArgTs...) Method)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Create a <a href="/web-llvm/docs/api/classes/llvm/orc/shared/methodwrapperhandler">MethodWrapperHandler</a> object from the given method pointer.</p>

<p>Definition at line 619 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/executionengine/include/llvm/executionengine/orc/include/llvm/executionengine/orc/shared/wrapperfunctionutils-h">WrapperFunctionUtils.h</a>.</p>

</div>
</div>

### numDeallocActions() {#a803f10b1184f06380dadea58c07912f4}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">size_t llvm::orc::shared::numDeallocActions (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="#a6da0b5cb8e68a6cc791a183d9d38aae0">AllocActions</a> &amp; AAs)</td>
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

<p>Returns the number of deallocaton actions in the given <a href="#a6da0b5cb8e68a6cc791a183d9d38aae0">AllocActions</a> array.</p>


<p>This can be useful if clients want to pre-allocate room for deallocation actions with the rest of their memory.</p>


<p>Definition at line 50 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/executionengine/include/llvm/executionengine/orc/include/llvm/executionengine/orc/shared/allocationactions-h">AllocationActions.h</a>.</p>


<p>References <a href="/web-llvm/docs/api/namespaces/llvm/#ac214df91cdc242f4710ea5a93939c678">llvm::count_if</a> and <a href="/web-llvm/docs/api/files/lib/lib/option/option-cpp/#a04665169063c8ca1f2ea96c27fc7c2b2">P</a>.</p>


<p>Referenced by <a href="#aa02467cf9213727cd36bce6f59653e5b">runFinalizeActions</a>.</p>

</div>
</div>

### runDeallocActions() {#a8263d385de2b406acf8dbef9b0993cc9}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">Error llvm::orc::shared::runDeallocActions (<a href="/web-llvm/docs/api/classes/llvm/arrayref">ArrayRef</a>&lt; <a href="/web-llvm/docs/api/classes/llvm/orc/shared/wrapperfunctioncall">WrapperFunctionCall</a> &gt; DAs)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Run deallocation actions.</p>


<p>Dealloc actions will be run in reverse order (from last element of DAs to first).</p>


<p>Definition at line 33 of file <a href="/web-llvm/docs/api/files/lib/lib/executionengine/lib/executionengine/orc/lib/executionengine/orc/shared/allocationactions-cpp">AllocationActions.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/classes/llvm/arrayref/#a291ac49156942529f159a9ec003cc25f">llvm::ArrayRef&lt; T &gt;::back</a>, <a href="/web-llvm/docs/api/classes/llvm/arrayref/#aa713e2599e000adc01ced998c05502a7">llvm::ArrayRef&lt; T &gt;::drop_back</a>, <a href="/web-llvm/docs/api/classes/llvm/arrayref/#ac835b8735b1b2faec0efdca236e37d94">llvm::ArrayRef&lt; T &gt;::empty</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a71210b99d2ef87236d8505c1771a7ab1">llvm::joinErrors</a> and <a href="/web-llvm/docs/api/classes/llvm/error/#a4dfd0813c3d0e0a30439b5a3e9196b59">llvm::Error::success</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/classes/llvm/orc/inprocessmemorymapper/#ac501a4fc8b8826d6451a9ae117ca3e0b">llvm::orc::InProcessMemoryMapper::deinitialize</a>, <a href="/web-llvm/docs/api/classes/llvm/orc/rt-bootstrap/executorsharedmemorymapperservice/#a860b91123cbc492ac289fa52811dc84e">llvm::orc::rt_bootstrap::ExecutorSharedMemoryMapperService::deinitialize</a> and <a href="#aa02467cf9213727cd36bce6f59653e5b">runFinalizeActions</a>.</p>

</div>
</div>

### runFinalizeActions() {#aa02467cf9213727cd36bce6f59653e5b}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">Expected&lt; std::vector&lt; WrapperFunctionCall &gt; &gt; llvm::orc::shared::runFinalizeActions (<a href="#a6da0b5cb8e68a6cc791a183d9d38aae0">AllocActions</a> &amp; AAs)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Run finalize actions.</p>


<p>If any finalize action fails then the corresponding dealloc actions will be run in reverse order (not including the deallocation action for the failed finalize action), and the error for the failing action will be returned.</p>


<p>If all finalize actions succeed then a vector of deallocation actions will be returned. The dealloc actions should be run by calling runDeallocationActions. If this function succeeds then the <a href="/web-llvm/docs/api/namespaces/llvm/aa">AA</a> argument will be cleared before the function returns.</p>


<p>Definition at line 16 of file <a href="/web-llvm/docs/api/files/lib/lib/executionengine/lib/executionengine/orc/lib/executionengine/orc/shared/allocationactions-cpp">AllocationActions.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/namespaces/llvm/#a71210b99d2ef87236d8505c1771a7ab1">llvm::joinErrors</a>, <a href="#a803f10b1184f06380dadea58c07912f4">numDeallocActions</a> and <a href="#a8263d385de2b406acf8dbef9b0993cc9">runDeallocActions</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/classes/llvm/orc/inprocessmemorymapper/#a492e4d6b2bf660e7c499e22f85b72440">llvm::orc::InProcessMemoryMapper::initialize</a> and <a href="/web-llvm/docs/api/classes/llvm/orc/rt-bootstrap/executorsharedmemorymapperservice/#af7f72f04af2ffe1b66adfecb7f881b02">llvm::orc::rt_bootstrap::ExecutorSharedMemoryMapperService::initialize</a>.</p>

</div>
</div>

</div>

<hr/>

The documentation for this namespace was generated from the following files:

<ul>
<li><a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/executionengine/include/llvm/executionengine/orc/elfnixplatform-h">ELFNixPlatform.h</a></li>
<li><a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/executionengine/include/llvm/executionengine/orc/include/llvm/executionengine/orc/shared/allocationactions-h">AllocationActions.h</a></li>
<li><a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/executionengine/include/llvm/executionengine/orc/include/llvm/executionengine/orc/shared/executoraddress-h">ExecutorAddress.h</a></li>
<li><a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/executionengine/include/llvm/executionengine/orc/include/llvm/executionengine/orc/shared/executorsymboldef-h">ExecutorSymbolDef.h</a></li>
<li><a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/executionengine/include/llvm/executionengine/orc/include/llvm/executionengine/orc/shared/perfsharedstructs-h">PerfSharedStructs.h</a></li>
<li><a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/executionengine/include/llvm/executionengine/orc/include/llvm/executionengine/orc/shared/simplepackedserialization-h">SimplePackedSerialization.h</a></li>
<li><a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/executionengine/include/llvm/executionengine/orc/include/llvm/executionengine/orc/shared/simpleremoteepcutils-h">SimpleRemoteEPCUtils.h</a></li>
<li><a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/executionengine/include/llvm/executionengine/orc/include/llvm/executionengine/orc/shared/targetprocesscontroltypes-h">TargetProcessControlTypes.h</a></li>
<li><a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/executionengine/include/llvm/executionengine/orc/include/llvm/executionengine/orc/shared/vtunesharedstructs-h">VTuneSharedStructs.h</a></li>
<li><a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/executionengine/include/llvm/executionengine/orc/include/llvm/executionengine/orc/shared/wrapperfunctionutils-h">WrapperFunctionUtils.h</a></li>
<li><a href="/web-llvm/docs/api/files/lib/lib/executionengine/lib/executionengine/orc/coffplatform-cpp">COFFPlatform.cpp</a></li>
<li><a href="/web-llvm/docs/api/files/lib/lib/executionengine/lib/executionengine/orc/machoplatform-cpp">MachOPlatform.cpp</a></li>
<li><a href="/web-llvm/docs/api/files/lib/lib/executionengine/lib/executionengine/orc/lib/executionengine/orc/shared/allocationactions-cpp">AllocationActions.cpp</a></li>
</ul>

<hr/>

<p class="doxyGeneratedBy">Generated via <a href="https://github.com/xpack/doxygen2docusaurus">doxygen2docusaurus</a> by <a href="https://www.doxygen.nl">Doxygen</a> 1.14.0.</p>

</div>
