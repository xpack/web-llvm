---

# DO NOT EDIT!
# Automatically generated via doxygen2docusaurus by Doxygen.

slug: /api/classes/llvm/orc/shared/spsserializationtraits-bc8864bc9177988c0f61b4692cfcd36c
custom_edit_url: null
toc_max_heading_level: 4
keywords:
  - doxygen
  - reference
  - class

---

<div class="doxyPage">

# `SPSSerializationTraits` Class Template

<p>SPS serialization for integral types, bool, and char. <a href="#details">More...</a></p>

## Declaration

<div class="doxyDeclaration">
template &lt;typename SPSTagT&gt;
class llvm::orc::shared::SPSSerializationTraits&lt;SPSTagT, SPSTagT, std::enable_if_t&lt; std::is_same&lt; SPSTagT, bool &gt;::value||std::is_same&lt; SPSTagT, char &gt;::value||std::is_same&lt; SPSTagT, int8_t &gt;::value||std::is_same&lt; SPSTagT, int16_t &gt;::value||std::is_same&lt; SPSTagT, int32_t &gt;::value||std::is_same&lt; SPSTagT, int64_t &gt;::value||std::is_same&lt; SPSTagT, uint8_t &gt;::value||std::is_same&lt; SPSTagT, uint16_t &gt;::value||std::is_same&lt; SPSTagT, uint32_t &gt;::value||std::is_same&lt; SPSTagT, uint64_t &gt;::value &gt;&gt; { ... }
</div>

## Included Headers

<div class="doxyIncludesList">#include "<a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/executionengine/include/llvm/executionengine/orc/include/llvm/executionengine/orc/shared/simplepackedserialization-h">llvm/ExecutionEngine/Orc/Shared/SimplePackedSerialization.h</a>"
</div>

## Public Static Functions Index

<table class="doxyMembersIndex">

<tr class="doxyMemberIndexTemplate">
<td class="doxyMemberIndexTemplate" colspan="2"><div>template &lt;typename SPSTagT&gt;</div></td>
</tr>
<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemTypeTemplate" align="left" valign="top">static size_t</td>
<td class="doxyMemberIndexItemNameTemplate" align="left" valign="top"><a href="#a0213e3507648b14cc7915ae0f0f08b20">size</a> (const SPSTagT &amp;Value)</td>
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
<td class="doxyMemberIndexTemplate" colspan="2"><div>template &lt;typename SPSTagT&gt;</div></td>
</tr>
<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemTypeTemplate" align="left" valign="top">static bool</td>
<td class="doxyMemberIndexItemNameTemplate" align="left" valign="top"><a href="#afe3ca4b56bc44bab916473dde49c6d4a">serialize</a> (SPSOutputBuffer &amp;OB, const SPSTagT &amp;Value)</td>
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
<td class="doxyMemberIndexTemplate" colspan="2"><div>template &lt;typename SPSTagT&gt;</div></td>
</tr>
<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemTypeTemplate" align="left" valign="top">static bool</td>
<td class="doxyMemberIndexItemNameTemplate" align="left" valign="top"><a href="#a010e8003e79960145f2f3f9aa0609a34">deserialize</a> (SPSInputBuffer &amp;IB, SPSTagT &amp;Value)</td>
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

<p>SPS serialization for integral types, bool, and char.</p>

<p>Definition at line 156 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/executionengine/include/llvm/executionengine/orc/include/llvm/executionengine/orc/shared/simplepackedserialization-h">SimplePackedSerialization.h</a>.</p>


<div class="doxySectionDef">

## Public Static Functions

### deserialize() {#a010e8003e79960145f2f3f9aa0609a34}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<div class="doxyMemberTemplate">template &lt;typename SPSTagT&gt;</div>
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool llvm::orc::shared::SPSSerializationTraits&lt; SPSTagT, SPSTagT, std::enable_if_t&lt; std::is_same&lt; SPSTagT, bool &gt;::value||std::is_same&lt; SPSTagT, char &gt;::value||std::is_same&lt; SPSTagT, int8_t &gt;::value||std::is_same&lt; SPSTagT, int16_t &gt;::value||std::is_same&lt; SPSTagT, int32_t &gt;::value||std::is_same&lt; SPSTagT, int64_t &gt;::value||std::is_same&lt; SPSTagT, uint8_t &gt;::value||std::is_same&lt; SPSTagT, uint16_t &gt;::value||std::is_same&lt; SPSTagT, uint32_t &gt;::value||std::is_same&lt; SPSTagT, uint64_t &gt;::value &gt; &gt;::deserialize (<a href="/web-llvm/docs/api/classes/llvm/orc/shared/spsinputbuffer">SPSInputBuffer</a> &amp; IB, SPSTagT &amp; Value)</td>
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



<p>Definition at line 178 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/executionengine/include/llvm/executionengine/orc/include/llvm/executionengine/orc/shared/simplepackedserialization-h">SimplePackedSerialization.h</a>.</p>


<p>References <a href="/web-llvm/docs/api/namespaces/llvm/sys/#ab9f705441a3a825d4b8a93ca4476d4e7">llvm::sys::IsBigEndianHost</a> and <a href="/web-llvm/docs/api/namespaces/llvm/sys/#ad0e418047a3e04c4fd1fb83325b571ae">llvm::sys::swapByteOrder</a>.</p>

</div>
</div>

### serialize() {#afe3ca4b56bc44bab916473dde49c6d4a}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<div class="doxyMemberTemplate">template &lt;typename SPSTagT&gt;</div>
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool llvm::orc::shared::SPSSerializationTraits&lt; SPSTagT, SPSTagT, std::enable_if_t&lt; std::is_same&lt; SPSTagT, bool &gt;::value||std::is_same&lt; SPSTagT, char &gt;::value||std::is_same&lt; SPSTagT, int8_t &gt;::value||std::is_same&lt; SPSTagT, int16_t &gt;::value||std::is_same&lt; SPSTagT, int32_t &gt;::value||std::is_same&lt; SPSTagT, int64_t &gt;::value||std::is_same&lt; SPSTagT, uint8_t &gt;::value||std::is_same&lt; SPSTagT, uint16_t &gt;::value||std::is_same&lt; SPSTagT, uint32_t &gt;::value||std::is_same&lt; SPSTagT, uint64_t &gt;::value &gt; &gt;::serialize (<a href="/web-llvm/docs/api/classes/llvm/orc/shared/spsoutputbuffer">SPSOutputBuffer</a> &amp; OB, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> SPSTagT &amp; Value)</td>
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



<p>Definition at line 171 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/executionengine/include/llvm/executionengine/orc/include/llvm/executionengine/orc/shared/simplepackedserialization-h">SimplePackedSerialization.h</a>.</p>


<p>References <a href="/web-llvm/docs/api/namespaces/llvm/sys/#ab9f705441a3a825d4b8a93ca4476d4e7">llvm::sys::IsBigEndianHost</a> and <a href="/web-llvm/docs/api/namespaces/llvm/sys/#ad0e418047a3e04c4fd1fb83325b571ae">llvm::sys::swapByteOrder</a>.</p>

</div>
</div>

### size() {#a0213e3507648b14cc7915ae0f0f08b20}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<div class="doxyMemberTemplate">template &lt;typename SPSTagT&gt;</div>
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">size_t llvm::orc::shared::SPSSerializationTraits&lt; SPSTagT, SPSTagT, std::enable_if_t&lt; std::is_same&lt; SPSTagT, bool &gt;::value||std::is_same&lt; SPSTagT, char &gt;::value||std::is_same&lt; SPSTagT, int8_t &gt;::value||std::is_same&lt; SPSTagT, int16_t &gt;::value||std::is_same&lt; SPSTagT, int32_t &gt;::value||std::is_same&lt; SPSTagT, int64_t &gt;::value||std::is_same&lt; SPSTagT, uint8_t &gt;::value||std::is_same&lt; SPSTagT, uint16_t &gt;::value||std::is_same&lt; SPSTagT, uint32_t &gt;::value||std::is_same&lt; SPSTagT, uint64_t &gt;::value &gt; &gt;::size (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> SPSTagT &amp; Value)</td>
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



<p>Definition at line 169 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/executionengine/include/llvm/executionengine/orc/include/llvm/executionengine/orc/shared/simplepackedserialization-h">SimplePackedSerialization.h</a>.</p>

</div>
</div>

</div>

<hr/>

The documentation for this class was generated from the following file:

<ul>
<li><a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/executionengine/include/llvm/executionengine/orc/include/llvm/executionengine/orc/shared/simplepackedserialization-h">SimplePackedSerialization.h</a></li>
</ul>

<hr/>

<p class="doxyGeneratedBy">Generated via <a href="https://github.com/xpack/doxygen2docusaurus">doxygen2docusaurus</a> by <a href="https://www.doxygen.nl">Doxygen</a> 1.15.0.</p>

</div>
