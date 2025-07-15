---

# DO NOT EDIT!
# Automatically generated via doxygen2docusaurus by Doxygen.

slug: /api/files/include/include/llvm/include/llvm/executionengine/include/llvm/executionengine/orc/include/llvm/executionengine/orc/shared/simplepackedserialization-h
custom_edit_url: null
toc_max_heading_level: 4
keywords:
  - doxygen
  - reference
  - file

---

<div class="doxyPage">

# The `SimplePackedSerialization.h` File Reference



## Included Headers

<div class="doxyIncludesList">#include "<a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/adt/stlextras-h">llvm/ADT/STLExtras.h</a>"
#include "<a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/adt/smallvector-h">llvm/ADT/SmallVector.h</a>"
#include "<a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/adt/stringmap-h">llvm/ADT/StringMap.h</a>"
#include "<a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/adt/stringref-h">llvm/ADT/StringRef.h</a>"
#include "<a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/support/error-h">llvm/Support/Error.h</a>"
#include "<a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/support/swapbyteorder-h">llvm/Support/SwapByteOrder.h</a>"
#include &lt;limits&gt;
#include &lt;optional&gt;
#include &lt;string&gt;
#include &lt;tuple&gt;
#include &lt;type_traits&gt;
#include &lt;utility&gt;
#include &lt;vector&gt;
</div>

## Namespaces Index

<table class="doxyMembersIndex">

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">namespace</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="/web-llvm/docs/api/namespaces/llvm">llvm</a></td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>This is an optimization pass for GlobalISel generic memory operations. <a href="/web-llvm/docs/api/namespaces/llvm/#details">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">namespace</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="/web-llvm/docs/api/namespaces/llvm/orc">orc</a></td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">namespace</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="/web-llvm/docs/api/namespaces/llvm/orc/shared">shared</a></td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">struct</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="/web-llvm/docs/api/structs/llvm/orc/shared/detail/spsserializableerror">SPSSerializableError</a></td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Helper type for serializing Errors. <a href="/web-llvm/docs/api/structs/llvm/orc/shared/detail/spsserializableerror/#details">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">struct</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="/web-llvm/docs/api/structs/llvm/orc/shared/detail/spsserializableexpected">SPSSerializableExpected&lt;T&gt;</a></td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Helper type for serializing <a href="/web-llvm/docs/api/classes/llvm/expected">Expected&lt;T&gt;</a>s. <a href="/web-llvm/docs/api/structs/llvm/orc/shared/detail/spsserializableexpected/#details">More...</a></p>
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

</table>


<hr/>

<p class="doxyGeneratedBy">Generated via <a href="https://github.com/xpack/doxygen2docusaurus">doxygen2docusaurus</a> by <a href="https://www.doxygen.nl">Doxygen</a> 1.14.0.</p>

</div>
