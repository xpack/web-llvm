---

# DO NOT EDIT!
# Automatically generated via doxygen2docusaurus by Doxygen.

slug: /api/structs/llvm/orc/shared/detail/spsserializableerror
custom_edit_url: null
toc_max_heading_level: 4
keywords:
  - doxygen
  - reference
  - struct

---

<div class="doxyPage">

# `SPSSerializableError` Struct

<p>Helper type for serializing Errors. <a href="#details">More...</a></p>

## Declaration

<div class="doxyDeclaration">
struct llvm::orc::shared::detail::SPSSerializableError { ... }
</div>

## Included Headers

<div class="doxyIncludesList">#include "<a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/executionengine/include/llvm/executionengine/orc/include/llvm/executionengine/orc/shared/simplepackedserialization-h">llvm/ExecutionEngine/Orc/Shared/SimplePackedSerialization.h</a>"
</div>

## Public Member Attributes Index

<table class="doxyMembersIndex">

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">bool</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#aa9c8ef19ab31e1d15348496557cdd772">HasError</a> = false</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">std::string</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a07afd4980ec97562be279c16015a07de">ErrMsg</a></td>
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

<p>Helper type for serializing Errors.</p>


<p>llvm::Errors are move-only, and not inspectable except by consuming them. This makes them unsuitable for direct serialization via <a href="/web-llvm/docs/api/classes/llvm/orc/shared/spsserializationtraits">SPSSerializationTraits</a>, which needs to inspect values twice (once to determine the amount of space to reserve, and then again to serialize).</p>


<p>The <a href="/web-llvm/docs/api/structs/llvm/orc/shared/detail/spsserializableerror">SPSSerializableError</a> type is a helper that can be constructed from an <a href="/web-llvm/docs/api/classes/llvm/error">llvm::Error</a>, but inspected more than once.</p>


<p>Definition at line 602 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/executionengine/include/llvm/executionengine/orc/include/llvm/executionengine/orc/shared/simplepackedserialization-h">SimplePackedSerialization.h</a>.</p>


<div class="doxySectionDef">

## Public Member Attributes

### ErrMsg {#a07afd4980ec97562be279c16015a07de}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">std::string llvm::orc::shared::detail::SPSSerializableError::ErrMsg</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 604 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/executionengine/include/llvm/executionengine/orc/include/llvm/executionengine/orc/shared/simplepackedserialization-h">SimplePackedSerialization.h</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/classes/llvm/orc/shared/spsserializationtraits-cd852d5f6a36d9b68f841465fc6ad92c/#a648ed3e50744e8e3623baefdc9505690">llvm::orc::shared::SPSSerializationTraits&lt; SPSError, detail::SPSSerializableError &gt;::deserialize</a>, <a href="/web-llvm/docs/api/namespaces/llvm/orc/shared/detail/#abba6e489c8732769239a8efbbf27364a">llvm::orc::shared::detail::fromSPSSerializable</a>, <a href="/web-llvm/docs/api/classes/llvm/orc/shared/spsserializationtraits-cd852d5f6a36d9b68f841465fc6ad92c/#a993eeee668aa76796889fcbcf40b5f27">llvm::orc::shared::SPSSerializationTraits&lt; SPSError, detail::SPSSerializableError &gt;::serialize</a>, <a href="/web-llvm/docs/api/classes/llvm/orc/shared/spsserializationtraits-37cbb09f9b4be473884ff41b97f4a7e3/#a87e586c978f00fe1c33caf922a30b9b8">llvm::orc::shared::SPSSerializationTraits&lt; SPSExpected&lt; SPSTagT &gt;, detail::SPSSerializableError &gt;::serialize</a>, <a href="/web-llvm/docs/api/classes/llvm/orc/shared/spsserializationtraits-cd852d5f6a36d9b68f841465fc6ad92c/#a5267153f5852e62487d16f3eda9cc68a">llvm::orc::shared::SPSSerializationTraits&lt; SPSError, detail::SPSSerializableError &gt;::size</a> and <a href="/web-llvm/docs/api/classes/llvm/orc/shared/spsserializationtraits-37cbb09f9b4be473884ff41b97f4a7e3/#a275bdc8d2ac3afdfcc1613c9431bdf00">llvm::orc::shared::SPSSerializationTraits&lt; SPSExpected&lt; SPSTagT &gt;, detail::SPSSerializableError &gt;::size</a>.</p>

</div>
</div>

### HasError {#aa9c8ef19ab31e1d15348496557cdd772}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool llvm::orc::shared::detail::SPSSerializableError::HasError = false</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 603 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/executionengine/include/llvm/executionengine/orc/include/llvm/executionengine/orc/shared/simplepackedserialization-h">SimplePackedSerialization.h</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/classes/llvm/orc/shared/spsserializationtraits-cd852d5f6a36d9b68f841465fc6ad92c/#a648ed3e50744e8e3623baefdc9505690">llvm::orc::shared::SPSSerializationTraits&lt; SPSError, detail::SPSSerializableError &gt;::deserialize</a>, <a href="/web-llvm/docs/api/namespaces/llvm/orc/shared/detail/#abba6e489c8732769239a8efbbf27364a">llvm::orc::shared::detail::fromSPSSerializable</a>, <a href="/web-llvm/docs/api/classes/llvm/orc/shared/spsserializationtraits-cd852d5f6a36d9b68f841465fc6ad92c/#a993eeee668aa76796889fcbcf40b5f27">llvm::orc::shared::SPSSerializationTraits&lt; SPSError, detail::SPSSerializableError &gt;::serialize</a>, <a href="/web-llvm/docs/api/classes/llvm/orc/shared/spsserializationtraits-37cbb09f9b4be473884ff41b97f4a7e3/#a87e586c978f00fe1c33caf922a30b9b8">llvm::orc::shared::SPSSerializationTraits&lt; SPSExpected&lt; SPSTagT &gt;, detail::SPSSerializableError &gt;::serialize</a>, <a href="/web-llvm/docs/api/classes/llvm/orc/shared/spsserializationtraits-cd852d5f6a36d9b68f841465fc6ad92c/#a5267153f5852e62487d16f3eda9cc68a">llvm::orc::shared::SPSSerializationTraits&lt; SPSError, detail::SPSSerializableError &gt;::size</a> and <a href="/web-llvm/docs/api/classes/llvm/orc/shared/spsserializationtraits-37cbb09f9b4be473884ff41b97f4a7e3/#a275bdc8d2ac3afdfcc1613c9431bdf00">llvm::orc::shared::SPSSerializationTraits&lt; SPSExpected&lt; SPSTagT &gt;, detail::SPSSerializableError &gt;::size</a>.</p>

</div>
</div>

</div>

<hr/>

The documentation for this struct was generated from the following file:

<ul>
<li><a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/executionengine/include/llvm/executionengine/orc/include/llvm/executionengine/orc/shared/simplepackedserialization-h">SimplePackedSerialization.h</a></li>
</ul>

<hr/>

<p class="doxyGeneratedBy">Generated via <a href="https://xpack.github.io/doxygen2docusaurus">doxygen2docusaurus</a> 2.0.0 by <a href="https://www.doxygen.nl">Doxygen</a> 1.15.0.</p>

</div>
