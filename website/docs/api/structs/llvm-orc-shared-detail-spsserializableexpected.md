---

# DO NOT EDIT!
# Automatically generated via doxygen2docusaurus by Doxygen.

slug: /api/structs/llvm/orc/shared/detail/spsserializableexpected
custom_edit_url: null
toc_max_heading_level: 4
keywords:
  - doxygen
  - reference
  - struct

---

<div class="doxyPage">

# The `SPSSerializableExpected` Struct Template Reference

<p>Helper type for serializing <a href="/web-llvm/docs/api/classes/llvm/expected">Expected&lt;T&gt;</a>s. <a href="#details">More...</a></p>

## Declaration

<div class="doxyDeclaration">
template &lt;typename T&gt;
struct llvm::orc::shared::detail::SPSSerializableExpected&lt;T&gt; { ... }
</div>

## Included Headers

<div class="doxyIncludesList">#include "<a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/executionengine/include/llvm/executionengine/orc/include/llvm/executionengine/orc/shared/simplepackedserialization-h">llvm/ExecutionEngine/Orc/Shared/SimplePackedSerialization.h</a>"
</div>

## Public Member Attributes Index

<table class="doxyMembersIndex">

<tr class="doxyMemberIndexTemplate">
<td class="doxyMemberIndexTemplate" colspan="2"><div>template &lt;typename T&gt;</div></td>
</tr>
<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemTypeTemplate" align="left" valign="top">bool</td>
<td class="doxyMemberIndexItemNameTemplate" align="left" valign="top"><a href="#a899a04357b2eb9ad12ff66f43d933e0c">HasValue</a> = false</td>
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
<td class="doxyMemberIndexItemTypeTemplate" align="left" valign="top">T</td>
<td class="doxyMemberIndexItemNameTemplate" align="left" valign="top"><a href="#a447d25e34c5c5f26ed4106cc4294585e">Value</a> {}</td>
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
<td class="doxyMemberIndexItemTypeTemplate" align="left" valign="top">std::string</td>
<td class="doxyMemberIndexItemNameTemplate" align="left" valign="top"><a href="#a7199d44b72f5b3732d640f94cf0aaf19">ErrMsg</a></td>
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

<p>Helper type for serializing <a href="/web-llvm/docs/api/classes/llvm/expected">Expected&lt;T&gt;</a>s.</p>


<p>See <a href="/web-llvm/docs/api/structs/llvm/orc/shared/detail/spsserializableerror">SPSSerializableError</a> for more details.</p>


<p>Definition at line 612 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/executionengine/include/llvm/executionengine/orc/include/llvm/executionengine/orc/shared/simplepackedserialization-h">SimplePackedSerialization.h</a>.</p>


<div class="doxySectionDef">

## Public Member Attributes

### ErrMsg {#a7199d44b72f5b3732d640f94cf0aaf19}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<div class="doxyMemberTemplate">template &lt;typename T&gt;</div>
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">std::string llvm::orc::shared::detail::SPSSerializableExpected&lt; T &gt;::ErrMsg</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 615 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/executionengine/include/llvm/executionengine/orc/include/llvm/executionengine/orc/shared/simplepackedserialization-h">SimplePackedSerialization.h</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/classes/llvm/orc/shared/spsserializationtraits-6eb1037f48906ccf4a6754355361971f/#a1381c86054cf4e7c377382c8f98933b7">llvm::orc::shared::SPSSerializationTraits&lt; SPSExpected&lt; SPSTagT &gt;, detail::SPSSerializableExpected&lt; T &gt; &gt;::deserialize</a>, <a href="/web-llvm/docs/api/namespaces/llvm/orc/shared/detail/#a94a3b524d950e4e80287ef3f20268fb5">llvm::orc::shared::detail::fromSPSSerializable</a>, <a href="/web-llvm/docs/api/classes/llvm/orc/shared/spsserializationtraits-6eb1037f48906ccf4a6754355361971f/#a8f3b834ea070f40c1fa51a1d8c0f2d4f">llvm::orc::shared::SPSSerializationTraits&lt; SPSExpected&lt; SPSTagT &gt;, detail::SPSSerializableExpected&lt; T &gt; &gt;::serialize</a> and <a href="/web-llvm/docs/api/classes/llvm/orc/shared/spsserializationtraits-6eb1037f48906ccf4a6754355361971f/#afd9a4384263aeabbbaedbb688f1d445c">llvm::orc::shared::SPSSerializationTraits&lt; SPSExpected&lt; SPSTagT &gt;, detail::SPSSerializableExpected&lt; T &gt; &gt;::size</a>.</p>

</div>
</div>

### HasValue {#a899a04357b2eb9ad12ff66f43d933e0c}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<div class="doxyMemberTemplate">template &lt;typename T&gt;</div>
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool llvm::orc::shared::detail::SPSSerializableExpected&lt; T &gt;::HasValue = false</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 613 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/executionengine/include/llvm/executionengine/orc/include/llvm/executionengine/orc/shared/simplepackedserialization-h">SimplePackedSerialization.h</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/classes/llvm/orc/shared/spsserializationtraits-6eb1037f48906ccf4a6754355361971f/#a1381c86054cf4e7c377382c8f98933b7">llvm::orc::shared::SPSSerializationTraits&lt; SPSExpected&lt; SPSTagT &gt;, detail::SPSSerializableExpected&lt; T &gt; &gt;::deserialize</a>, <a href="/web-llvm/docs/api/namespaces/llvm/orc/shared/detail/#a94a3b524d950e4e80287ef3f20268fb5">llvm::orc::shared::detail::fromSPSSerializable</a>, <a href="/web-llvm/docs/api/classes/llvm/orc/shared/spsserializationtraits-6eb1037f48906ccf4a6754355361971f/#a8f3b834ea070f40c1fa51a1d8c0f2d4f">llvm::orc::shared::SPSSerializationTraits&lt; SPSExpected&lt; SPSTagT &gt;, detail::SPSSerializableExpected&lt; T &gt; &gt;::serialize</a> and <a href="/web-llvm/docs/api/classes/llvm/orc/shared/spsserializationtraits-6eb1037f48906ccf4a6754355361971f/#afd9a4384263aeabbbaedbb688f1d445c">llvm::orc::shared::SPSSerializationTraits&lt; SPSExpected&lt; SPSTagT &gt;, detail::SPSSerializableExpected&lt; T &gt; &gt;::size</a>.</p>

</div>
</div>

### Value {#a447d25e34c5c5f26ed4106cc4294585e}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<div class="doxyMemberTemplate">template &lt;typename T&gt;</div>
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">T llvm::orc::shared::detail::SPSSerializableExpected&lt; T &gt;::Value {}</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 614 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/executionengine/include/llvm/executionengine/orc/include/llvm/executionengine/orc/shared/simplepackedserialization-h">SimplePackedSerialization.h</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/classes/llvm/orc/shared/spsserializationtraits-6eb1037f48906ccf4a6754355361971f/#a1381c86054cf4e7c377382c8f98933b7">llvm::orc::shared::SPSSerializationTraits&lt; SPSExpected&lt; SPSTagT &gt;, detail::SPSSerializableExpected&lt; T &gt; &gt;::deserialize</a>, <a href="/web-llvm/docs/api/namespaces/llvm/orc/shared/detail/#a94a3b524d950e4e80287ef3f20268fb5">llvm::orc::shared::detail::fromSPSSerializable</a>, <a href="/web-llvm/docs/api/classes/llvm/orc/shared/spsserializationtraits-6eb1037f48906ccf4a6754355361971f/#a8f3b834ea070f40c1fa51a1d8c0f2d4f">llvm::orc::shared::SPSSerializationTraits&lt; SPSExpected&lt; SPSTagT &gt;, detail::SPSSerializableExpected&lt; T &gt; &gt;::serialize</a> and <a href="/web-llvm/docs/api/classes/llvm/orc/shared/spsserializationtraits-6eb1037f48906ccf4a6754355361971f/#afd9a4384263aeabbbaedbb688f1d445c">llvm::orc::shared::SPSSerializationTraits&lt; SPSExpected&lt; SPSTagT &gt;, detail::SPSSerializableExpected&lt; T &gt; &gt;::size</a>.</p>

</div>
</div>

</div>

<hr/>

The documentation for this struct was generated from the following file:

<ul>
<li><a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/executionengine/include/llvm/executionengine/orc/include/llvm/executionengine/orc/shared/simplepackedserialization-h">SimplePackedSerialization.h</a></li>
</ul>

<hr/>

<p class="doxyGeneratedBy">Generated via <a href="https://github.com/xpack/doxygen2docusaurus">doxygen2docusaurus</a> by <a href="https://www.doxygen.nl">Doxygen</a> 1.14.0.</p>

</div>
