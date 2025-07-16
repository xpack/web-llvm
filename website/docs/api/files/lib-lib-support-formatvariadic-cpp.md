---

# DO NOT EDIT!
# Automatically generated via doxygen2docusaurus by Doxygen.

slug: /api/files/lib/lib/support/formatvariadic-cpp
custom_edit_url: null
toc_max_heading_level: 4
keywords:
  - doxygen
  - reference
  - file

---

<div class="doxyPage">

# The `FormatVariadic.cpp` File Reference



## Included Headers

<div class="doxyIncludesList">#include "<a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/support/formatvariadic-h">llvm/Support/FormatVariadic.h</a>"
#include &lt;cassert&gt;
#include &lt;optional&gt;
</div>

## Functions Index

<table class="doxyMembersIndex">

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">static std::optional&lt; <a href="/web-llvm/docs/api/namespaces/llvm/#a2554a96c67bdd7d0a62855a844ec55b0">AlignStyle</a> &gt;</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a9658070c5e21478178a5fc0d32b105ec">translateLocChar</a> (char C)</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a2d41bf697e339948086195506824ddf0">consumeFieldLayout</a> (StringRef &amp;Spec, AlignStyle &amp;Where, unsigned &amp;Align, char &amp;Pad)</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">static std::optional&lt; <a href="/web-llvm/docs/api/structs/llvm/replacementitem">ReplacementItem</a> &gt;</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a93e1f93d537243a559abd940ec1b6f53">parseReplacementItem</a> (StringRef Spec)</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">static std::pair&lt; std::optional&lt; <a href="/web-llvm/docs/api/structs/llvm/replacementitem">ReplacementItem</a> &gt;, <a href="/web-llvm/docs/api/classes/llvm/stringref">StringRef</a> &gt;</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a4424b1162f4c0837c494b0ae747e683a">splitLiteralAndReplacement</a> (StringRef Fmt)</td>
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

## Macro Definitions Index

<table class="doxyMembersIndex">

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">#define</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a8f17b62dd93730fe6e2cd6044912a740">ENABLE_VALIDATION</a>&nbsp;&nbsp;&nbsp;1</td>
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


<div class="doxySectionDef">

## Functions

### consumeFieldLayout() {#a2d41bf697e339948086195506824ddf0}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool consumeFieldLayout (<a href="/web-llvm/docs/api/classes/llvm/stringref">StringRef</a> &amp; Spec, <a href="/web-llvm/docs/api/namespaces/llvm/#a2554a96c67bdd7d0a62855a844ec55b0">AlignStyle</a> &amp; Where, unsigned &amp; Align, char &amp; Pad)</td>
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



<p>Definition at line 28 of file <a href="/web-llvm/docs/api/files/lib/lib/support/formatvariadic-cpp">FormatVariadic.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/namespaces/llvm/#a2cd7b2e49608a96ba42f59f642cf99ac">llvm::Failed</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a2554a96c67bdd7d0a62855a844ec55b0a92b09c7c48c520c3c55e497875da437c">llvm::Right</a> and <a href="#a9658070c5e21478178a5fc0d32b105ec">translateLocChar</a>.</p>


<p>Referenced by <a href="#a93e1f93d537243a559abd940ec1b6f53">parseReplacementItem</a>.</p>

</div>
</div>

### parseReplacementItem() {#a93e1f93d537243a559abd940ec1b6f53}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">std::optional&lt; ReplacementItem &gt; parseReplacementItem (<a href="/web-llvm/docs/api/classes/llvm/stringref">StringRef</a> Spec)</td>
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



<p>Definition at line 57 of file <a href="/web-llvm/docs/api/files/lib/lib/support/formatvariadic-cpp">FormatVariadic.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/silowercontrolflow-cpp/#a4868c5d81c5ccc98c47aeab6244346a0">assert</a>, <a href="/web-llvm/docs/api/classes/llvm/stringref/#a8a7fac667f8ae35285b8b53d9f2dd9dc">llvm::StringRef::consume_front</a>, <a href="#a2d41bf697e339948086195506824ddf0">consumeFieldLayout</a>, <a href="/web-llvm/docs/api/classes/llvm/stringref/#a1643e7698ddbfd40fbd374a85f015846">llvm::StringRef::consumeInteger</a>, <a href="/web-llvm/docs/api/classes/llvm/stringref/#a2dc80c585ad5882da8cae7b5968f7e74">llvm::StringRef::empty</a>, <a href="/web-llvm/docs/api/classes/llvm/stringref/#a8265efd805e4ce0c9d3c18e78194324c">llvm::StringRef::ltrim</a>, <a href="/web-llvm/docs/api/files/lib/lib/debuginfo/lib/debuginfo/logicalview/lib/debuginfo/logicalview/core/lvoptions-cpp/#ab4088b7a11f3cbc38ac16a6e9c72494e">Options</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a2554a96c67bdd7d0a62855a844ec55b0a92b09c7c48c520c3c55e497875da437c">llvm::Right</a> and <a href="/web-llvm/docs/api/classes/llvm/stringref/#ab9990397f97b40d5d8564e000d00174a">llvm::StringRef::trim</a>.</p>


<p>Referenced by <a href="#a4424b1162f4c0837c494b0ae747e683a">splitLiteralAndReplacement</a>.</p>

</div>
</div>

### splitLiteralAndReplacement() {#a4424b1162f4c0837c494b0ae747e683a}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">std::pair&lt; std::optional&lt; ReplacementItem &gt;, StringRef &gt; splitLiteralAndReplacement (<a href="/web-llvm/docs/api/classes/llvm/stringref">StringRef</a> Fmt)</td>
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



<p>Definition at line 93 of file <a href="/web-llvm/docs/api/files/lib/lib/support/formatvariadic-cpp">FormatVariadic.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/silowercontrolflow-cpp/#a4868c5d81c5ccc98c47aeab6244346a0">assert</a>, <a href="/web-llvm/docs/api/namespaces/llvm/callingconv/#ac6aa1387c4375260e2468eb5a77fdb4cafd841a49aec1539bc88abc8ff9e170fb">llvm::CallingConv::C</a>, <a href="/web-llvm/docs/api/classes/llvm/stringref/#a3fb2867a1e9fa36e135d9ee4dffb0167">llvm::StringRef::drop_front</a>, <a href="/web-llvm/docs/api/classes/llvm/stringref/#a2dc80c585ad5882da8cae7b5968f7e74">llvm::StringRef::empty</a>, <a href="/web-llvm/docs/api/classes/llvm/stringref/#a93b15a8c0022febbe39d17ab933737a8">llvm::StringRef::find_first_of</a>, <a href="/web-llvm/docs/api/classes/llvm/stringref/#a61364ca3a5ff90fb2aa0d5a371fd43f7">llvm::StringRef::front</a>, <a href="/web-llvm/docs/api/classes/anonymous-path-cpp-/stringref/#ad0f54a163ac500b144590640c6f1eb6b">anonymous{Path.cpp}::StringRef::npos</a>, <a href="#a93e1f93d537243a559abd940ec1b6f53">parseReplacementItem</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a2554a96c67bdd7d0a62855a844ec55b0a92b09c7c48c520c3c55e497875da437c">llvm::Right</a>, <a href="/web-llvm/docs/api/classes/llvm/stringref/#a5db9240c74644c67759dd0f901fc3c7d">llvm::StringRef::size</a>, <a href="/web-llvm/docs/api/classes/llvm/stringref/#a5d4c961b9b6f1da17df74b4496ecb30e">llvm::StringRef::slice</a>, <a href="/web-llvm/docs/api/classes/llvm/stringref/#a25f1fd81f2132805676c82ab8ae0c109">llvm::StringRef::substr</a>, <a href="/web-llvm/docs/api/classes/llvm/stringref/#aa28286a33491b5d9a936fb6ae853baee">llvm::StringRef::take_front</a> and <a href="/web-llvm/docs/api/classes/llvm/stringref/#a34a27457ad5d68f631c788807c4ff52c">llvm::StringRef::take_while</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/classes/llvm/formatv-object-base/#a3daaa42a47524368df5608cccd1f6b66">llvm::formatv_object_base::parseFormatString</a>.</p>

</div>
</div>

### translateLocChar() {#a9658070c5e21478178a5fc0d32b105ec}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">std::optional&lt; AlignStyle &gt; translateLocChar (char C)</td>
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



<p>Definition at line 14 of file <a href="/web-llvm/docs/api/files/lib/lib/support/formatvariadic-cpp">FormatVariadic.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/namespaces/llvm/callingconv/#ac6aa1387c4375260e2468eb5a77fdb4cafd841a49aec1539bc88abc8ff9e170fb">llvm::CallingConv::C</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a2554a96c67bdd7d0a62855a844ec55b0a4f1f6016fc9f3f2353c0cc7c67b292bd">llvm::Center</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a2554a96c67bdd7d0a62855a844ec55b0a945d5e233cf7d6240f6b783b36a374ff">llvm::Left</a> and <a href="/web-llvm/docs/api/namespaces/llvm/#a2554a96c67bdd7d0a62855a844ec55b0a92b09c7c48c520c3c55e497875da437c">llvm::Right</a>.</p>


<p>Referenced by <a href="#a2d41bf697e339948086195506824ddf0">consumeFieldLayout</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Macro Definitions

### ENABLE\_VALIDATION {#a8f17b62dd93730fe6e2cd6044912a740}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">#define ENABLE_VALIDATION&nbsp;&nbsp;&nbsp;1</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 136 of file <a href="/web-llvm/docs/api/files/lib/lib/support/formatvariadic-cpp">FormatVariadic.cpp</a>.</p>

</div>
</div>

</div>

<hr/>

<p class="doxyGeneratedBy">Generated via <a href="https://github.com/xpack/doxygen2docusaurus">doxygen2docusaurus</a> by <a href="https://www.doxygen.nl">Doxygen</a> 1.15.0.</p>

</div>
