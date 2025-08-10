---

# DO NOT EDIT!
# Automatically generated via doxygen2docusaurus by Doxygen.

slug: /api/classes/llvm/orc/shared/spsserializationtraits-6eb1037f48906ccf4a6754355361971f
custom_edit_url: null
toc_max_heading_level: 4
keywords:
  - doxygen
  - reference
  - class

---

<div class="doxyPage">

# `SPSSerializationTraits` Class Template

<p>Serialize to a <a href="/web-llvm/docs/api/classes/llvm/orc/shared/spsexpected">SPSExpected&lt;SPSTagT&gt;</a> from a <a href="/web-llvm/docs/api/structs/llvm/orc/shared/detail/spsserializableexpected">detail::SPSSerializableExpected&lt;T&gt;</a>. <a href="#details">More...</a></p>

## Declaration

<div class="doxyDeclaration">
template &lt;typename SPSTagT, typename T&gt;
class llvm::orc::shared::SPSSerializationTraits&lt;SPSExpected&lt; SPSTagT &gt;, detail::SPSSerializableExpected&lt; T &gt;&gt; { ... }
</div>

## Included Headers

<div class="doxyIncludesList">#include "<a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/executionengine/include/llvm/executionengine/orc/include/llvm/executionengine/orc/shared/simplepackedserialization-h">llvm/ExecutionEngine/Orc/Shared/SimplePackedSerialization.h</a>"
</div>

## Public Static Functions Index

<table class="doxyMembersIndex">

<tr class="doxyMemberIndexTemplate">
<td class="doxyMemberIndexTemplate" colspan="2"><div>template &lt;typename SPSTagT, typename T&gt;</div></td>
</tr>
<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemTypeTemplate" align="left" valign="top">static size_t</td>
<td class="doxyMemberIndexItemNameTemplate" align="left" valign="top"><a href="#afd9a4384263aeabbbaedbb688f1d445c">size</a> (const detail::SPSSerializableExpected&lt; T &gt; &amp;BSE)</td>
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
<td class="doxyMemberIndexTemplate" colspan="2"><div>template &lt;typename SPSTagT, typename T&gt;</div></td>
</tr>
<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemTypeTemplate" align="left" valign="top">static bool</td>
<td class="doxyMemberIndexItemNameTemplate" align="left" valign="top"><a href="#a8f3b834ea070f40c1fa51a1d8c0f2d4f">serialize</a> (SPSOutputBuffer &amp;OB, const detail::SPSSerializableExpected&lt; T &gt; &amp;BSE)</td>
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
<td class="doxyMemberIndexTemplate" colspan="2"><div>template &lt;typename SPSTagT, typename T&gt;</div></td>
</tr>
<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemTypeTemplate" align="left" valign="top">static bool</td>
<td class="doxyMemberIndexItemNameTemplate" align="left" valign="top"><a href="#a1381c86054cf4e7c377382c8f98933b7">deserialize</a> (SPSInputBuffer &amp;IB, detail::SPSSerializableExpected&lt; T &gt; &amp;BSE)</td>
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

<p>Serialize to a <a href="/web-llvm/docs/api/classes/llvm/orc/shared/spsexpected">SPSExpected&lt;SPSTagT&gt;</a> from a <a href="/web-llvm/docs/api/structs/llvm/orc/shared/detail/spsserializableexpected">detail::SPSSerializableExpected&lt;T&gt;</a>.</p>

<p>Definition at line 684 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/executionengine/include/llvm/executionengine/orc/include/llvm/executionengine/orc/shared/simplepackedserialization-h">SimplePackedSerialization.h</a>.</p>


<div class="doxySectionDef">

## Public Static Functions

### deserialize() {#a1381c86054cf4e7c377382c8f98933b7}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<div class="doxyMemberTemplate">template &lt;typename SPSTagT, typename T&gt;</div>
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool llvm::orc::shared::SPSSerializationTraits&lt; SPSExpected&lt; SPSTagT &gt;, detail::SPSSerializableExpected&lt; T &gt; &gt;::deserialize (<a href="/web-llvm/docs/api/classes/llvm/orc/shared/spsinputbuffer">SPSInputBuffer</a> &amp; IB, <a href="/web-llvm/docs/api/structs/llvm/orc/shared/detail/spsserializableexpected">detail::SPSSerializableExpected</a>&lt; T &gt; &amp; BSE)</td>
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



<p>Definition at line 707 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/executionengine/include/llvm/executionengine/orc/include/llvm/executionengine/orc/shared/simplepackedserialization-h">SimplePackedSerialization.h</a>.</p>


<p>References <a href="/web-llvm/docs/api/structs/llvm/orc/shared/detail/spsserializableexpected/#a7199d44b72f5b3732d640f94cf0aaf19">llvm::orc::shared::detail::SPSSerializableExpected&lt; T &gt;::ErrMsg</a>, <a href="/web-llvm/docs/api/structs/llvm/orc/shared/detail/spsserializableexpected/#a899a04357b2eb9ad12ff66f43d933e0c">llvm::orc::shared::detail::SPSSerializableExpected&lt; T &gt;::HasValue</a> and <a href="/web-llvm/docs/api/structs/llvm/orc/shared/detail/spsserializableexpected/#a447d25e34c5c5f26ed4106cc4294585e">llvm::orc::shared::detail::SPSSerializableExpected&lt; T &gt;::Value</a>.</p>

</div>
</div>

### serialize() {#a8f3b834ea070f40c1fa51a1d8c0f2d4f}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<div class="doxyMemberTemplate">template &lt;typename SPSTagT, typename T&gt;</div>
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool llvm::orc::shared::SPSSerializationTraits&lt; SPSExpected&lt; SPSTagT &gt;, detail::SPSSerializableExpected&lt; T &gt; &gt;::serialize (<a href="/web-llvm/docs/api/classes/llvm/orc/shared/spsoutputbuffer">SPSOutputBuffer</a> &amp; OB, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/structs/llvm/orc/shared/detail/spsserializableexpected">detail::SPSSerializableExpected</a>&lt; T &gt; &amp; BSE)</td>
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



<p>Definition at line 696 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/executionengine/include/llvm/executionengine/orc/include/llvm/executionengine/orc/shared/simplepackedserialization-h">SimplePackedSerialization.h</a>.</p>


<p>References <a href="/web-llvm/docs/api/structs/llvm/orc/shared/detail/spsserializableexpected/#a7199d44b72f5b3732d640f94cf0aaf19">llvm::orc::shared::detail::SPSSerializableExpected&lt; T &gt;::ErrMsg</a>, <a href="/web-llvm/docs/api/structs/llvm/orc/shared/detail/spsserializableexpected/#a899a04357b2eb9ad12ff66f43d933e0c">llvm::orc::shared::detail::SPSSerializableExpected&lt; T &gt;::HasValue</a> and <a href="/web-llvm/docs/api/structs/llvm/orc/shared/detail/spsserializableexpected/#a447d25e34c5c5f26ed4106cc4294585e">llvm::orc::shared::detail::SPSSerializableExpected&lt; T &gt;::Value</a>.</p>

</div>
</div>

### size() {#afd9a4384263aeabbbaedbb688f1d445c}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<div class="doxyMemberTemplate">template &lt;typename SPSTagT, typename T&gt;</div>
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">size_t llvm::orc::shared::SPSSerializationTraits&lt; SPSExpected&lt; SPSTagT &gt;, detail::SPSSerializableExpected&lt; T &gt; &gt;::size (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/structs/llvm/orc/shared/detail/spsserializableexpected">detail::SPSSerializableExpected</a>&lt; T &gt; &amp; BSE)</td>
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



<p>Definition at line 687 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/executionengine/include/llvm/executionengine/orc/include/llvm/executionengine/orc/shared/simplepackedserialization-h">SimplePackedSerialization.h</a>.</p>


<p>References <a href="/web-llvm/docs/api/structs/llvm/orc/shared/detail/spsserializableexpected/#a7199d44b72f5b3732d640f94cf0aaf19">llvm::orc::shared::detail::SPSSerializableExpected&lt; T &gt;::ErrMsg</a>, <a href="/web-llvm/docs/api/structs/llvm/orc/shared/detail/spsserializableexpected/#a899a04357b2eb9ad12ff66f43d933e0c">llvm::orc::shared::detail::SPSSerializableExpected&lt; T &gt;::HasValue</a>, <a href="/web-llvm/docs/api/files/lib/lib/analysis/inlineorder-cpp/#a7ee6f0cb51c3b9056199e9a0001fe8c3a6f6cb72d544962fa333e2e34ce64f719">Size</a> and <a href="/web-llvm/docs/api/structs/llvm/orc/shared/detail/spsserializableexpected/#a447d25e34c5c5f26ed4106cc4294585e">llvm::orc::shared::detail::SPSSerializableExpected&lt; T &gt;::Value</a>.</p>

</div>
</div>

</div>

<hr/>

The documentation for this class was generated from the following file:

<ul>
<li><a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/executionengine/include/llvm/executionengine/orc/include/llvm/executionengine/orc/shared/simplepackedserialization-h">SimplePackedSerialization.h</a></li>
</ul>

<hr/>

<p class="doxyGeneratedBy">Generated via <a href="https://xpack.github.io/doxygen2docusaurus">doxygen2docusaurus</a> 2.0.0 by <a href="https://www.doxygen.nl">Doxygen</a> 1.15.0.</p>

</div>
