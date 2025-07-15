---

# DO NOT EDIT!
# Automatically generated via doxygen2docusaurus by Doxygen.

slug: /api/classes/llvm/orc/shared/spsserializationtraits-784a1bef17190e6ab41c561ff2b7a7b9
custom_edit_url: null
toc_max_heading_level: 4
keywords:
  - doxygen
  - reference
  - class

---

<div class="doxyPage">

# The `SPSSerializationTraits` Class Template Reference



## Declaration

<div class="doxyDeclaration">
class llvm::orc::shared::SPSSerializationTraits&lt;SPSSegFinalizeRequest, tpctypes::SegFinalizeRequest&gt; { ... }
</div>

## Included Headers

<div class="doxyIncludesList">#include "<a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/executionengine/include/llvm/executionengine/orc/include/llvm/executionengine/orc/shared/targetprocesscontroltypes-h">llvm/ExecutionEngine/Orc/Shared/TargetProcessControlTypes.h</a>"
</div>

## Private Member Typedefs Index

<table class="doxyMembersIndex">

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">using</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ae1b00807cc882c8a9bac88b667a88949">SFRAL</a> = <a href="/web-llvm/docs/api/classes/llvm/orc/shared/spstuple/#a4ac958780d60988306a818239d07657c">SPSSegFinalizeRequest::AsArgList</a></td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">static size_t</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a9114ae5be7ffa02b4566dc6e5109d44c">size</a> (const tpctypes::SegFinalizeRequest &amp;SFR)</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">static bool</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#aee5f3d5808154c2cd798394a195e5b73">serialize</a> (SPSOutputBuffer &amp;OB, const tpctypes::SegFinalizeRequest &amp;SFR)</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">static bool</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a9f26566a1c21b25aa74e802028257708">deserialize</a> (SPSInputBuffer &amp;IB, tpctypes::SegFinalizeRequest &amp;SFR)</td>
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


<p>Definition at line 196 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/executionengine/include/llvm/executionengine/orc/include/llvm/executionengine/orc/shared/targetprocesscontroltypes-h">TargetProcessControlTypes.h</a>.</p>


<div class="doxySectionDef">

## Private Member Typedefs

### SFRAL {#ae1b00807cc882c8a9bac88b667a88949}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">using llvm::orc::shared::SPSSerializationTraits&lt; SPSSegFinalizeRequest, tpctypes::SegFinalizeRequest &gt;::SFRAL =  SPSSegFinalizeRequest::AsArgList</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 198 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/executionengine/include/llvm/executionengine/orc/include/llvm/executionengine/orc/shared/targetprocesscontroltypes-h">TargetProcessControlTypes.h</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Public Static Functions

### deserialize() {#a9f26566a1c21b25aa74e802028257708}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool llvm::orc::shared::SPSSerializationTraits&lt; SPSSegFinalizeRequest, tpctypes::SegFinalizeRequest &gt;::deserialize (<a href="/web-llvm/docs/api/classes/llvm/orc/shared/spsinputbuffer">SPSInputBuffer</a> &amp; IB, <a href="/web-llvm/docs/api/structs/llvm/orc/tpctypes/segfinalizerequest">tpctypes::SegFinalizeRequest</a> &amp; SFR)</td>
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



<p>Definition at line 210 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/executionengine/include/llvm/executionengine/orc/include/llvm/executionengine/orc/shared/targetprocesscontroltypes-h">TargetProcessControlTypes.h</a>.</p>


<p>References <a href="/web-llvm/docs/api/structs/llvm/orc/tpctypes/segfinalizerequest/#a63a7ca147b982a7206f3ca9b18923b94">llvm::orc::tpctypes::SegFinalizeRequest::Addr</a>, <a href="/web-llvm/docs/api/structs/llvm/orc/tpctypes/segfinalizerequest/#a20543fdb30035570b044c28008d9c42e">llvm::orc::tpctypes::SegFinalizeRequest::Content</a>, <a href="/web-llvm/docs/api/structs/llvm/orc/tpctypes/segfinalizerequest/#abc86666c4219c9f050f3c30106f4a4e3">llvm::orc::tpctypes::SegFinalizeRequest::RAG</a> and <a href="/web-llvm/docs/api/structs/llvm/orc/tpctypes/segfinalizerequest/#a88bf55a6e833d2d04aca01c3e5e01615">llvm::orc::tpctypes::SegFinalizeRequest::Size</a>.</p>

</div>
</div>

### serialize() {#aee5f3d5808154c2cd798394a195e5b73}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool llvm::orc::shared::SPSSerializationTraits&lt; SPSSegFinalizeRequest, tpctypes::SegFinalizeRequest &gt;::serialize (<a href="/web-llvm/docs/api/classes/llvm/orc/shared/spsoutputbuffer">SPSOutputBuffer</a> &amp; OB, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/structs/llvm/orc/tpctypes/segfinalizerequest">tpctypes::SegFinalizeRequest</a> &amp; SFR)</td>
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



<p>Definition at line 205 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/executionengine/include/llvm/executionengine/orc/include/llvm/executionengine/orc/shared/targetprocesscontroltypes-h">TargetProcessControlTypes.h</a>.</p>


<p>References <a href="/web-llvm/docs/api/structs/llvm/orc/tpctypes/segfinalizerequest/#a63a7ca147b982a7206f3ca9b18923b94">llvm::orc::tpctypes::SegFinalizeRequest::Addr</a>, <a href="/web-llvm/docs/api/structs/llvm/orc/tpctypes/segfinalizerequest/#a20543fdb30035570b044c28008d9c42e">llvm::orc::tpctypes::SegFinalizeRequest::Content</a>, <a href="/web-llvm/docs/api/structs/llvm/orc/tpctypes/segfinalizerequest/#abc86666c4219c9f050f3c30106f4a4e3">llvm::orc::tpctypes::SegFinalizeRequest::RAG</a> and <a href="/web-llvm/docs/api/structs/llvm/orc/tpctypes/segfinalizerequest/#a88bf55a6e833d2d04aca01c3e5e01615">llvm::orc::tpctypes::SegFinalizeRequest::Size</a>.</p>

</div>
</div>

### size() {#a9114ae5be7ffa02b4566dc6e5109d44c}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">size_t llvm::orc::shared::SPSSerializationTraits&lt; SPSSegFinalizeRequest, tpctypes::SegFinalizeRequest &gt;::size (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/structs/llvm/orc/tpctypes/segfinalizerequest">tpctypes::SegFinalizeRequest</a> &amp; SFR)</td>
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



<p>Definition at line 201 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/executionengine/include/llvm/executionengine/orc/include/llvm/executionengine/orc/shared/targetprocesscontroltypes-h">TargetProcessControlTypes.h</a>.</p>


<p>References <a href="/web-llvm/docs/api/structs/llvm/orc/tpctypes/segfinalizerequest/#a63a7ca147b982a7206f3ca9b18923b94">llvm::orc::tpctypes::SegFinalizeRequest::Addr</a>, <a href="/web-llvm/docs/api/structs/llvm/orc/tpctypes/segfinalizerequest/#a20543fdb30035570b044c28008d9c42e">llvm::orc::tpctypes::SegFinalizeRequest::Content</a>, <a href="/web-llvm/docs/api/structs/llvm/orc/tpctypes/segfinalizerequest/#abc86666c4219c9f050f3c30106f4a4e3">llvm::orc::tpctypes::SegFinalizeRequest::RAG</a> and <a href="/web-llvm/docs/api/structs/llvm/orc/tpctypes/segfinalizerequest/#a88bf55a6e833d2d04aca01c3e5e01615">llvm::orc::tpctypes::SegFinalizeRequest::Size</a>.</p>

</div>
</div>

</div>

<hr/>

The documentation for this class was generated from the following file:

<ul>
<li><a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/executionengine/include/llvm/executionengine/orc/include/llvm/executionengine/orc/shared/targetprocesscontroltypes-h">TargetProcessControlTypes.h</a></li>
</ul>

<hr/>

<p class="doxyGeneratedBy">Generated via <a href="https://github.com/xpack/doxygen2docusaurus">doxygen2docusaurus</a> by <a href="https://www.doxygen.nl">Doxygen</a> 1.14.0.</p>

</div>
