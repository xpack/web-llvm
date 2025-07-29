---

# DO NOT EDIT!
# Automatically generated via doxygen2docusaurus by Doxygen.

slug: /api/files/lib/lib/debuginfo/lib/debuginfo/codeview/typeindexdiscovery-cpp
custom_edit_url: null
toc_max_heading_level: 4
keywords:
  - doxygen
  - reference
  - file

---

<div class="doxyPage">

# `TypeIndexDiscovery.cpp` File



## Included Headers

<div class="doxyIncludesList">#include "<a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/debuginfo/include/llvm/debuginfo/codeview/typeindexdiscovery-h">llvm/DebugInfo/CodeView/TypeIndexDiscovery.h</a>"
#include "<a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/debuginfo/include/llvm/debuginfo/codeview/typerecord-h">llvm/DebugInfo/CodeView/TypeRecord.h</a>"
#include "<a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/adt/arrayref-h">llvm/ADT/ArrayRef.h</a>"
#include "<a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/support/endian-h">llvm/Support/Endian.h</a>"
</div>

## Functions Index

<table class="doxyMembersIndex">

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">static <a href="/web-llvm/docs/api/namespaces/llvm/codeview/#a168a6021abac4aa4ac613129e7fc38c7">MethodKind</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ae0c27fda221da0261489c8534a5e93c8">getMethodKind</a> (uint16_t Attrs)</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ae644f68d24ac5b34de160fc910f2f3ec">isIntroVirtual</a> (uint16_t Attrs)</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">static <a href="/web-llvm/docs/api/namespaces/llvm/codeview/#a0bfa8e65ecd85f3151f84bb53ad4bcbc">PointerMode</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#adf4718363dcb690ce2b5560c4f5c0689">getPointerMode</a> (uint32_t Attrs)</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a4ff4587317327e576c1edb8aa61234fc">isMemberPointer</a> (uint32_t Attrs)</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">static uint32_t</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a8fa7e42c07f77ffbc093d9f6b80a36af">getEncodedIntegerLength</a> (ArrayRef&lt; uint8_t &gt; Data)</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">static uint32_t</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a03de03d741e52bd468fdcb9398d1d8db">getCStringLength</a> (ArrayRef&lt; uint8_t &gt; Data)</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">static void</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#abbb20c80e0c1ab59446de978f898fc1e">handleMethodOverloadList</a> (ArrayRef&lt; uint8_t &gt; Content, SmallVectorImpl&lt; TiReference &gt; &amp;Refs)</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">static uint32_t</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#aaff349708bd2e38bf04c7995bc40db8c">handleBaseClass</a> (ArrayRef&lt; uint8_t &gt; Data, uint32_t Offset, SmallVectorImpl&lt; TiReference &gt; &amp;Refs)</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">static uint32_t</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a4f2a73c2eeab970bde7323cae38e6dd3">handleEnumerator</a> (ArrayRef&lt; uint8_t &gt; Data, uint32_t Offset, SmallVectorImpl&lt; TiReference &gt; &amp;Refs)</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">static uint32_t</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a11cc5001079df0a0c9f4e0f16fb2e4a5">handleDataMember</a> (ArrayRef&lt; uint8_t &gt; Data, uint32_t Offset, SmallVectorImpl&lt; TiReference &gt; &amp;Refs)</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">static uint32_t</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ae10e279e0a75605e7429e6e3176a7ca2">handleOverloadedMethod</a> (ArrayRef&lt; uint8_t &gt; Data, uint32_t Offset, SmallVectorImpl&lt; TiReference &gt; &amp;Refs)</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">static uint32_t</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a96ae8a0897a355d1c0a04a7eae3f2466">handleOneMethod</a> (ArrayRef&lt; uint8_t &gt; Data, uint32_t Offset, SmallVectorImpl&lt; TiReference &gt; &amp;Refs)</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">static uint32_t</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a57e9d47198c1315b209ae12d935a60d9">handleNestedType</a> (ArrayRef&lt; uint8_t &gt; Data, uint32_t Offset, SmallVectorImpl&lt; TiReference &gt; &amp;Refs)</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">static uint32_t</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#afa937cb598845b69e37a81f67ffd4c7b">handleStaticDataMember</a> (ArrayRef&lt; uint8_t &gt; Data, uint32_t Offset, SmallVectorImpl&lt; TiReference &gt; &amp;Refs)</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">static uint32_t</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ad79c1724545f758ab3046506669b993d">handleVirtualBaseClass</a> (ArrayRef&lt; uint8_t &gt; Data, uint32_t Offset, bool IsIndirect, SmallVectorImpl&lt; TiReference &gt; &amp;Refs)</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">static uint32_t</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a93e8eec2fad7a5df11a2d003d095a6df">handleVFPtr</a> (ArrayRef&lt; uint8_t &gt; Data, uint32_t Offset, SmallVectorImpl&lt; TiReference &gt; &amp;Refs)</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">static uint32_t</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a1ab055a13a095bb1fa676e2df11b9024">handleListContinuation</a> (ArrayRef&lt; uint8_t &gt; Data, uint32_t Offset, SmallVectorImpl&lt; TiReference &gt; &amp;Refs)</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">static void</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#aa9a744b2382a97226e765258f365a15c">handleFieldList</a> (ArrayRef&lt; uint8_t &gt; Content, SmallVectorImpl&lt; TiReference &gt; &amp;Refs)</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">static void</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ab36e33dbf8516f7892bd335ff40545e9">handlePointer</a> (ArrayRef&lt; uint8_t &gt; Content, SmallVectorImpl&lt; TiReference &gt; &amp;Refs)</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">static void</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a25991c233686a63c58cc75b2fc0d9a5f">discoverTypeIndices</a> (ArrayRef&lt; uint8_t &gt; Content, TypeLeafKind Kind, SmallVectorImpl&lt; TiReference &gt; &amp;Refs)</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a6c25c8fa1e18bfa4689e9982991c9791">discoverTypeIndices</a> (ArrayRef&lt; uint8_t &gt; Content, SymbolKind Kind, SmallVectorImpl&lt; TiReference &gt; &amp;Refs)</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">static void</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a350ae3fe286b68175d7eee301904506c">resolveTypeIndexReferences</a> (ArrayRef&lt; uint8_t &gt; RecordData, ArrayRef&lt; TiReference &gt; Refs, SmallVectorImpl&lt; TypeIndex &gt; &amp;Indices)</td>
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

### discoverTypeIndices() {#a25991c233686a63c58cc75b2fc0d9a5f}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void discoverTypeIndices (<a href="/web-llvm/docs/api/classes/llvm/arrayref">ArrayRef</a>&lt; uint8_t &gt; Content, <a href="/web-llvm/docs/api/namespaces/llvm/codeview/#a945d5dcbe78d400d17656726e2f6089b">TypeLeafKind</a> Kind, <a href="/web-llvm/docs/api/classes/llvm/smallvectorimpl">SmallVectorImpl</a>&lt; <a href="/web-llvm/docs/api/structs/llvm/codeview/tireference">TiReference</a> &gt; &amp; Refs)</td>
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



<p>Definition at line 274 of file <a href="/web-llvm/docs/api/files/lib/lib/debuginfo/lib/debuginfo/codeview/typeindexdiscovery-cpp">TypeIndexDiscovery.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/namespaces/llvm/#a845e08be4b0320d66901a66b0c0e9509">llvm::Count</a>, <a href="/web-llvm/docs/api/classes/llvm/arrayref/#adb9cab4abca6bf2855c882dcf79fb1cb">llvm::ArrayRef&lt; T &gt;::data</a>, <a href="#aa9a744b2382a97226e765258f365a15c">handleFieldList</a>, <a href="#abbb20c80e0c1ab59446de978f898fc1e">handleMethodOverloadList</a>, <a href="#ab36e33dbf8516f7892bd335ff40545e9">handlePointer</a>, <a href="/web-llvm/docs/api/namespaces/llvm/codeview/#a15b96719effacbb3d6e211f4ef768d98ae4b32150368e5a8a701eb52dc75c769f">llvm::codeview::IndexRef</a>, <a href="/web-llvm/docs/api/classes/llvm/smallvectortemplatebase/#af42bfbc067df27c19ee2fc859df58799">llvm::SmallVectorTemplateBase&lt; T, bool &gt;::push_back</a>, <a href="/web-llvm/docs/api/namespaces/llvm/support/endian/#a17a3ace88f2bb1abf73bf887cdc88e5f">llvm::support::endian::read16le</a>, <a href="/web-llvm/docs/api/namespaces/llvm/support/endian/#ae865d5defb8785b365f342375822beaa">llvm::support::endian::read32le</a> and <a href="/web-llvm/docs/api/namespaces/llvm/codeview/#a15b96719effacbb3d6e211f4ef768d98a5a2393a91d8bbd23f8fd97b38d660498">llvm::codeview::TypeRef</a>.</p>

</div>
</div>

### discoverTypeIndices() {#a6c25c8fa1e18bfa4689e9982991c9791}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool discoverTypeIndices (<a href="/web-llvm/docs/api/classes/llvm/arrayref">ArrayRef</a>&lt; uint8_t &gt; Content, <a href="/web-llvm/docs/api/namespaces/llvm/codeview/#ac3fd578f133e7ee0210c835b393bca59">SymbolKind</a> Kind, <a href="/web-llvm/docs/api/classes/llvm/smallvectorimpl">SmallVectorImpl</a>&lt; <a href="/web-llvm/docs/api/structs/llvm/codeview/tireference">TiReference</a> &gt; &amp; Refs)</td>
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



<p>Definition at line 360 of file <a href="/web-llvm/docs/api/files/lib/lib/debuginfo/lib/debuginfo/codeview/typeindexdiscovery-cpp">TypeIndexDiscovery.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/namespaces/llvm/#a845e08be4b0320d66901a66b0c0e9509">llvm::Count</a>, <a href="/web-llvm/docs/api/classes/llvm/arrayref/#adb9cab4abca6bf2855c882dcf79fb1cb">llvm::ArrayRef&lt; T &gt;::data</a>, <a href="/web-llvm/docs/api/namespaces/llvm/codeview/#a15b96719effacbb3d6e211f4ef768d98ae4b32150368e5a8a701eb52dc75c769f">llvm::codeview::IndexRef</a>, <a href="/web-llvm/docs/api/classes/llvm/smallvectortemplatebase/#af42bfbc067df27c19ee2fc859df58799">llvm::SmallVectorTemplateBase&lt; T, bool &gt;::push_back</a> and <a href="/web-llvm/docs/api/namespaces/llvm/codeview/#a15b96719effacbb3d6e211f4ef768d98a5a2393a91d8bbd23f8fd97b38d660498">llvm::codeview::TypeRef</a>.</p>

</div>
</div>

### getCStringLength() {#a03de03d741e52bd468fdcb9398d1d8db}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">uint32_t getCStringLength (<a href="/web-llvm/docs/api/classes/llvm/arrayref">ArrayRef</a>&lt; uint8_t &gt; Data)</td>
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



<p>Definition at line 64 of file <a href="/web-llvm/docs/api/files/lib/lib/debuginfo/lib/debuginfo/codeview/typeindexdiscovery-cpp">TypeIndexDiscovery.cpp</a>.</p>


<p>Reference <a href="/web-llvm/docs/api/namespaces/llvm/#aa20539e89704d20b98b97e9c3feac934">llvm::Data</a>.</p>


<p>Referenced by <a href="#a11cc5001079df0a0c9f4e0f16fb2e4a5">handleDataMember</a>, <a href="#a4f2a73c2eeab970bde7323cae38e6dd3">handleEnumerator</a>, <a href="#a57e9d47198c1315b209ae12d935a60d9">handleNestedType</a>, <a href="#a96ae8a0897a355d1c0a04a7eae3f2466">handleOneMethod</a>, <a href="#ae10e279e0a75605e7429e6e3176a7ca2">handleOverloadedMethod</a> and <a href="#afa937cb598845b69e37a81f67ffd4c7b">handleStaticDataMember</a>.</p>

</div>
</div>

### getEncodedIntegerLength() {#a8fa7e42c07f77ffbc093d9f6b80a36af}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">uint32_t getEncodedIntegerLength (<a href="/web-llvm/docs/api/classes/llvm/arrayref">ArrayRef</a>&lt; uint8_t &gt; Data)</td>
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



<p>Definition at line 40 of file <a href="/web-llvm/docs/api/files/lib/lib/debuginfo/lib/debuginfo/codeview/typeindexdiscovery-cpp">TypeIndexDiscovery.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/silowercontrolflow-cpp/#a4868c5d81c5ccc98c47aeab6244346a0">assert</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#aa20539e89704d20b98b97e9c3feac934">llvm::Data</a>, <a href="/web-llvm/docs/api/files/lib/lib/support/regcomp-c/#a0240ac851181b84ac374872dc5434ee4">N</a> and <a href="/web-llvm/docs/api/namespaces/llvm/support/endian/#a17a3ace88f2bb1abf73bf887cdc88e5f">llvm::support::endian::read16le</a>.</p>


<p>Referenced by <a href="#aaff349708bd2e38bf04c7995bc40db8c">handleBaseClass</a>, <a href="#a11cc5001079df0a0c9f4e0f16fb2e4a5">handleDataMember</a>, <a href="#a4f2a73c2eeab970bde7323cae38e6dd3">handleEnumerator</a> and <a href="#ad79c1724545f758ab3046506669b993d">handleVirtualBaseClass</a>.</p>

</div>
</div>

### getMethodKind() {#ae0c27fda221da0261489c8534a5e93c8}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">MethodKind getMethodKind (uint16_t Attrs)</td>
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



<p>Definition at line 17 of file <a href="/web-llvm/docs/api/files/lib/lib/debuginfo/lib/debuginfo/codeview/typeindexdiscovery-cpp">TypeIndexDiscovery.cpp</a>.</p>


<p>Reference <a href="/web-llvm/docs/api/namespaces/llvm/codeview/#a728fe3ed02de6938b9ae302f54d8626fa7462d50a1f48859ae5ae2d6009a07ee9">llvm::codeview::MethodKindMask</a>.</p>


<p>Referenced by <a href="#ae644f68d24ac5b34de160fc910f2f3ec">isIntroVirtual</a>.</p>

</div>
</div>

### getPointerMode() {#adf4718363dcb690ce2b5560c4f5c0689}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">PointerMode getPointerMode (uint32_t Attrs)</td>
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



<p>Definition at line 29 of file <a href="/web-llvm/docs/api/files/lib/lib/debuginfo/lib/debuginfo/codeview/typeindexdiscovery-cpp">TypeIndexDiscovery.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/classes/llvm/codeview/pointerrecord/#af3b49353d30ac40865a3f8cd304dc767">llvm::codeview::PointerRecord::PointerModeMask</a> and <a href="/web-llvm/docs/api/classes/llvm/codeview/pointerrecord/#a0d0ff1e428401914c3faacfb68648a55">llvm::codeview::PointerRecord::PointerModeShift</a>.</p>


<p>Referenced by <a href="#a4ff4587317327e576c1edb8aa61234fc">isMemberPointer</a>.</p>

</div>
</div>

### handleBaseClass() {#aaff349708bd2e38bf04c7995bc40db8c}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">uint32_t handleBaseClass (<a href="/web-llvm/docs/api/classes/llvm/arrayref">ArrayRef</a>&lt; uint8_t &gt; Data, uint32_t Offset, <a href="/web-llvm/docs/api/classes/llvm/smallvectorimpl">SmallVectorImpl</a>&lt; <a href="/web-llvm/docs/api/structs/llvm/codeview/tireference">TiReference</a> &gt; &amp; Refs)</td>
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



<p>Definition at line 95 of file <a href="/web-llvm/docs/api/files/lib/lib/debuginfo/lib/debuginfo/codeview/typeindexdiscovery-cpp">TypeIndexDiscovery.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/namespaces/llvm/#aa20539e89704d20b98b97e9c3feac934">llvm::Data</a>, <a href="#a8fa7e42c07f77ffbc093d9f6b80a36af">getEncodedIntegerLength</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a05f5b9a11bdcc5feba62899f95dcf878a3134224cba2545bc57954d3b072aebb4">llvm::Offset</a>, <a href="/web-llvm/docs/api/classes/llvm/smallvectortemplatebase/#af42bfbc067df27c19ee2fc859df58799">llvm::SmallVectorTemplateBase&lt; T, bool &gt;::push_back</a> and <a href="/web-llvm/docs/api/namespaces/llvm/codeview/#a15b96719effacbb3d6e211f4ef768d98a5a2393a91d8bbd23f8fd97b38d660498">llvm::codeview::TypeRef</a>.</p>


<p>Referenced by <a href="#aa9a744b2382a97226e765258f365a15c">handleFieldList</a>.</p>

</div>
</div>

### handleDataMember() {#a11cc5001079df0a0c9f4e0f16fb2e4a5}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">uint32_t handleDataMember (<a href="/web-llvm/docs/api/classes/llvm/arrayref">ArrayRef</a>&lt; uint8_t &gt; Data, uint32_t Offset, <a href="/web-llvm/docs/api/classes/llvm/smallvectorimpl">SmallVectorImpl</a>&lt; <a href="/web-llvm/docs/api/structs/llvm/codeview/tireference">TiReference</a> &gt; &amp; Refs)</td>
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



<p>Definition at line 115 of file <a href="/web-llvm/docs/api/files/lib/lib/debuginfo/lib/debuginfo/codeview/typeindexdiscovery-cpp">TypeIndexDiscovery.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/namespaces/llvm/#aa20539e89704d20b98b97e9c3feac934">llvm::Data</a>, <a href="#a03de03d741e52bd468fdcb9398d1d8db">getCStringLength</a>, <a href="#a8fa7e42c07f77ffbc093d9f6b80a36af">getEncodedIntegerLength</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a05f5b9a11bdcc5feba62899f95dcf878a3134224cba2545bc57954d3b072aebb4">llvm::Offset</a>, <a href="/web-llvm/docs/api/classes/llvm/smallvectortemplatebase/#af42bfbc067df27c19ee2fc859df58799">llvm::SmallVectorTemplateBase&lt; T, bool &gt;::push_back</a>, <a href="/web-llvm/docs/api/files/lib/lib/analysis/inlineorder-cpp/#a7ee6f0cb51c3b9056199e9a0001fe8c3a6f6cb72d544962fa333e2e34ce64f719">Size</a> and <a href="/web-llvm/docs/api/namespaces/llvm/codeview/#a15b96719effacbb3d6e211f4ef768d98a5a2393a91d8bbd23f8fd97b38d660498">llvm::codeview::TypeRef</a>.</p>


<p>Referenced by <a href="#aa9a744b2382a97226e765258f365a15c">handleFieldList</a>.</p>

</div>
</div>

### handleEnumerator() {#a4f2a73c2eeab970bde7323cae38e6dd3}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">uint32_t handleEnumerator (<a href="/web-llvm/docs/api/classes/llvm/arrayref">ArrayRef</a>&lt; uint8_t &gt; Data, uint32_t Offset, <a href="/web-llvm/docs/api/classes/llvm/smallvectorimpl">SmallVectorImpl</a>&lt; <a href="/web-llvm/docs/api/structs/llvm/codeview/tireference">TiReference</a> &gt; &amp; Refs)</td>
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



<p>Definition at line 105 of file <a href="/web-llvm/docs/api/files/lib/lib/debuginfo/lib/debuginfo/codeview/typeindexdiscovery-cpp">TypeIndexDiscovery.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/namespaces/llvm/#aa20539e89704d20b98b97e9c3feac934">llvm::Data</a>, <a href="#a03de03d741e52bd468fdcb9398d1d8db">getCStringLength</a>, <a href="#a8fa7e42c07f77ffbc093d9f6b80a36af">getEncodedIntegerLength</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a05f5b9a11bdcc5feba62899f95dcf878a3134224cba2545bc57954d3b072aebb4">llvm::Offset</a> and <a href="/web-llvm/docs/api/files/lib/lib/analysis/inlineorder-cpp/#a7ee6f0cb51c3b9056199e9a0001fe8c3a6f6cb72d544962fa333e2e34ce64f719">Size</a>.</p>


<p>Referenced by <a href="#aa9a744b2382a97226e765258f365a15c">handleFieldList</a>.</p>

</div>
</div>

### handleFieldList() {#aa9a744b2382a97226e765258f365a15c}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void handleFieldList (<a href="/web-llvm/docs/api/classes/llvm/arrayref">ArrayRef</a>&lt; uint8_t &gt; Content, <a href="/web-llvm/docs/api/classes/llvm/smallvectorimpl">SmallVectorImpl</a>&lt; <a href="/web-llvm/docs/api/structs/llvm/codeview/tireference">TiReference</a> &gt; &amp; Refs)</td>
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



<p>Definition at line 209 of file <a href="/web-llvm/docs/api/files/lib/lib/debuginfo/lib/debuginfo/codeview/typeindexdiscovery-cpp">TypeIndexDiscovery.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/classes/llvm/arrayref/#adb9cab4abca6bf2855c882dcf79fb1cb">llvm::ArrayRef&lt; T &gt;::data</a>, <a href="/web-llvm/docs/api/classes/llvm/arrayref/#a55089293ebaccd683a82d97170041376">llvm::ArrayRef&lt; T &gt;::drop_front</a>, <a href="/web-llvm/docs/api/classes/llvm/arrayref/#ac835b8735b1b2faec0efdca236e37d94">llvm::ArrayRef&lt; T &gt;::empty</a>, <a href="/web-llvm/docs/api/classes/llvm/arrayref/#a721fc555cb3d8dc2a1a680dcc2ce69b2">llvm::ArrayRef&lt; T &gt;::front</a>, <a href="#aaff349708bd2e38bf04c7995bc40db8c">handleBaseClass</a>, <a href="#a11cc5001079df0a0c9f4e0f16fb2e4a5">handleDataMember</a>, <a href="#a4f2a73c2eeab970bde7323cae38e6dd3">handleEnumerator</a>, <a href="#a1ab055a13a095bb1fa676e2df11b9024">handleListContinuation</a>, <a href="#a57e9d47198c1315b209ae12d935a60d9">handleNestedType</a>, <a href="#a96ae8a0897a355d1c0a04a7eae3f2466">handleOneMethod</a>, <a href="#ae10e279e0a75605e7429e6e3176a7ca2">handleOverloadedMethod</a>, <a href="#afa937cb598845b69e37a81f67ffd4c7b">handleStaticDataMember</a>, <a href="#a93e8eec2fad7a5df11a2d003d095a6df">handleVFPtr</a>, <a href="#ad79c1724545f758ab3046506669b993d">handleVirtualBaseClass</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a05f5b9a11bdcc5feba62899f95dcf878a3134224cba2545bc57954d3b072aebb4">llvm::Offset</a> and <a href="/web-llvm/docs/api/namespaces/llvm/support/endian/#a17a3ace88f2bb1abf73bf887cdc88e5f">llvm::support::endian::read16le</a>.</p>


<p>Referenced by <a href="#a25991c233686a63c58cc75b2fc0d9a5f">discoverTypeIndices</a>.</p>

</div>
</div>

### handleListContinuation() {#a1ab055a13a095bb1fa676e2df11b9024}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">uint32_t handleListContinuation (<a href="/web-llvm/docs/api/classes/llvm/arrayref">ArrayRef</a>&lt; uint8_t &gt; Data, uint32_t Offset, <a href="/web-llvm/docs/api/classes/llvm/smallvectorimpl">SmallVectorImpl</a>&lt; <a href="/web-llvm/docs/api/structs/llvm/codeview/tireference">TiReference</a> &gt; &amp; Refs)</td>
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



<p>Definition at line 200 of file <a href="/web-llvm/docs/api/files/lib/lib/debuginfo/lib/debuginfo/codeview/typeindexdiscovery-cpp">TypeIndexDiscovery.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/namespaces/llvm/#aa20539e89704d20b98b97e9c3feac934">llvm::Data</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a05f5b9a11bdcc5feba62899f95dcf878a3134224cba2545bc57954d3b072aebb4">llvm::Offset</a>, <a href="/web-llvm/docs/api/classes/llvm/smallvectortemplatebase/#af42bfbc067df27c19ee2fc859df58799">llvm::SmallVectorTemplateBase&lt; T, bool &gt;::push_back</a> and <a href="/web-llvm/docs/api/namespaces/llvm/codeview/#a15b96719effacbb3d6e211f4ef768d98a5a2393a91d8bbd23f8fd97b38d660498">llvm::codeview::TypeRef</a>.</p>


<p>Referenced by <a href="#aa9a744b2382a97226e765258f365a15c">handleFieldList</a>.</p>

</div>
</div>

### handleMethodOverloadList() {#abbb20c80e0c1ab59446de978f898fc1e}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void handleMethodOverloadList (<a href="/web-llvm/docs/api/classes/llvm/arrayref">ArrayRef</a>&lt; uint8_t &gt; Content, <a href="/web-llvm/docs/api/classes/llvm/smallvectorimpl">SmallVectorImpl</a>&lt; <a href="/web-llvm/docs/api/structs/llvm/codeview/tireference">TiReference</a> &gt; &amp; Refs)</td>
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



<p>Definition at line 69 of file <a href="/web-llvm/docs/api/files/lib/lib/debuginfo/lib/debuginfo/codeview/typeindexdiscovery-cpp">TypeIndexDiscovery.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/classes/llvm/arrayref/#adb9cab4abca6bf2855c882dcf79fb1cb">llvm::ArrayRef&lt; T &gt;::data</a>, <a href="/web-llvm/docs/api/classes/llvm/arrayref/#a55089293ebaccd683a82d97170041376">llvm::ArrayRef&lt; T &gt;::drop_front</a>, <a href="/web-llvm/docs/api/classes/llvm/arrayref/#ac835b8735b1b2faec0efdca236e37d94">llvm::ArrayRef&lt; T &gt;::empty</a>, <a href="#ae644f68d24ac5b34de160fc910f2f3ec">isIntroVirtual</a>, <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/support/compiler-h/#a104cae72182bec0ab951e3faea6ce509">LLVM_UNLIKELY</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a05f5b9a11bdcc5feba62899f95dcf878a3134224cba2545bc57954d3b072aebb4">llvm::Offset</a>, <a href="/web-llvm/docs/api/classes/llvm/smallvectortemplatebase/#af42bfbc067df27c19ee2fc859df58799">llvm::SmallVectorTemplateBase&lt; T, bool &gt;::push_back</a>, <a href="/web-llvm/docs/api/namespaces/llvm/support/endian/#a17a3ace88f2bb1abf73bf887cdc88e5f">llvm::support::endian::read16le</a> and <a href="/web-llvm/docs/api/namespaces/llvm/codeview/#a15b96719effacbb3d6e211f4ef768d98a5a2393a91d8bbd23f8fd97b38d660498">llvm::codeview::TypeRef</a>.</p>


<p>Referenced by <a href="#a25991c233686a63c58cc75b2fc0d9a5f">discoverTypeIndices</a>.</p>

</div>
</div>

### handleNestedType() {#a57e9d47198c1315b209ae12d935a60d9}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">uint32_t handleNestedType (<a href="/web-llvm/docs/api/classes/llvm/arrayref">ArrayRef</a>&lt; uint8_t &gt; Data, uint32_t Offset, <a href="/web-llvm/docs/api/classes/llvm/smallvectorimpl">SmallVectorImpl</a>&lt; <a href="/web-llvm/docs/api/structs/llvm/codeview/tireference">TiReference</a> &gt; &amp; Refs)</td>
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



<p>Definition at line 155 of file <a href="/web-llvm/docs/api/files/lib/lib/debuginfo/lib/debuginfo/codeview/typeindexdiscovery-cpp">TypeIndexDiscovery.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/namespaces/llvm/#aa20539e89704d20b98b97e9c3feac934">llvm::Data</a>, <a href="#a03de03d741e52bd468fdcb9398d1d8db">getCStringLength</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a05f5b9a11bdcc5feba62899f95dcf878a3134224cba2545bc57954d3b072aebb4">llvm::Offset</a>, <a href="/web-llvm/docs/api/classes/llvm/smallvectortemplatebase/#af42bfbc067df27c19ee2fc859df58799">llvm::SmallVectorTemplateBase&lt; T, bool &gt;::push_back</a> and <a href="/web-llvm/docs/api/namespaces/llvm/codeview/#a15b96719effacbb3d6e211f4ef768d98a5a2393a91d8bbd23f8fd97b38d660498">llvm::codeview::TypeRef</a>.</p>


<p>Referenced by <a href="#aa9a744b2382a97226e765258f365a15c">handleFieldList</a>.</p>

</div>
</div>

### handleOneMethod() {#a96ae8a0897a355d1c0a04a7eae3f2466}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">uint32_t handleOneMethod (<a href="/web-llvm/docs/api/classes/llvm/arrayref">ArrayRef</a>&lt; uint8_t &gt; Data, uint32_t Offset, <a href="/web-llvm/docs/api/classes/llvm/smallvectorimpl">SmallVectorImpl</a>&lt; <a href="/web-llvm/docs/api/structs/llvm/codeview/tireference">TiReference</a> &gt; &amp; Refs)</td>
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



<p>Definition at line 137 of file <a href="/web-llvm/docs/api/files/lib/lib/debuginfo/lib/debuginfo/codeview/typeindexdiscovery-cpp">TypeIndexDiscovery.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/namespaces/llvm/#aa20539e89704d20b98b97e9c3feac934">llvm::Data</a>, <a href="#a03de03d741e52bd468fdcb9398d1d8db">getCStringLength</a>, <a href="#ae644f68d24ac5b34de160fc910f2f3ec">isIntroVirtual</a>, <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/support/compiler-h/#a104cae72182bec0ab951e3faea6ce509">LLVM_UNLIKELY</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a05f5b9a11bdcc5feba62899f95dcf878a3134224cba2545bc57954d3b072aebb4">llvm::Offset</a>, <a href="/web-llvm/docs/api/classes/llvm/smallvectortemplatebase/#af42bfbc067df27c19ee2fc859df58799">llvm::SmallVectorTemplateBase&lt; T, bool &gt;::push_back</a>, <a href="/web-llvm/docs/api/namespaces/llvm/support/endian/#a17a3ace88f2bb1abf73bf887cdc88e5f">llvm::support::endian::read16le</a>, <a href="/web-llvm/docs/api/files/lib/lib/analysis/inlineorder-cpp/#a7ee6f0cb51c3b9056199e9a0001fe8c3a6f6cb72d544962fa333e2e34ce64f719">Size</a> and <a href="/web-llvm/docs/api/namespaces/llvm/codeview/#a15b96719effacbb3d6e211f4ef768d98a5a2393a91d8bbd23f8fd97b38d660498">llvm::codeview::TypeRef</a>.</p>


<p>Referenced by <a href="#aa9a744b2382a97226e765258f365a15c">handleFieldList</a>.</p>

</div>
</div>

### handleOverloadedMethod() {#ae10e279e0a75605e7429e6e3176a7ca2}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">uint32_t handleOverloadedMethod (<a href="/web-llvm/docs/api/classes/llvm/arrayref">ArrayRef</a>&lt; uint8_t &gt; Data, uint32_t Offset, <a href="/web-llvm/docs/api/classes/llvm/smallvectorimpl">SmallVectorImpl</a>&lt; <a href="/web-llvm/docs/api/structs/llvm/codeview/tireference">TiReference</a> &gt; &amp; Refs)</td>
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



<p>Definition at line 127 of file <a href="/web-llvm/docs/api/files/lib/lib/debuginfo/lib/debuginfo/codeview/typeindexdiscovery-cpp">TypeIndexDiscovery.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/namespaces/llvm/#aa20539e89704d20b98b97e9c3feac934">llvm::Data</a>, <a href="#a03de03d741e52bd468fdcb9398d1d8db">getCStringLength</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a05f5b9a11bdcc5feba62899f95dcf878a3134224cba2545bc57954d3b072aebb4">llvm::Offset</a>, <a href="/web-llvm/docs/api/classes/llvm/smallvectortemplatebase/#af42bfbc067df27c19ee2fc859df58799">llvm::SmallVectorTemplateBase&lt; T, bool &gt;::push_back</a> and <a href="/web-llvm/docs/api/namespaces/llvm/codeview/#a15b96719effacbb3d6e211f4ef768d98a5a2393a91d8bbd23f8fd97b38d660498">llvm::codeview::TypeRef</a>.</p>


<p>Referenced by <a href="#aa9a744b2382a97226e765258f365a15c">handleFieldList</a>.</p>

</div>
</div>

### handlePointer() {#ab36e33dbf8516f7892bd335ff40545e9}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void handlePointer (<a href="/web-llvm/docs/api/classes/llvm/arrayref">ArrayRef</a>&lt; uint8_t &gt; Content, <a href="/web-llvm/docs/api/classes/llvm/smallvectorimpl">SmallVectorImpl</a>&lt; <a href="/web-llvm/docs/api/structs/llvm/codeview/tireference">TiReference</a> &gt; &amp; Refs)</td>
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



<p>Definition at line 265 of file <a href="/web-llvm/docs/api/files/lib/lib/debuginfo/lib/debuginfo/codeview/typeindexdiscovery-cpp">TypeIndexDiscovery.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/classes/llvm/arrayref/#a55089293ebaccd683a82d97170041376">llvm::ArrayRef&lt; T &gt;::drop_front</a>, <a href="#a4ff4587317327e576c1edb8aa61234fc">isMemberPointer</a>, <a href="/web-llvm/docs/api/classes/llvm/smallvectortemplatebase/#af42bfbc067df27c19ee2fc859df58799">llvm::SmallVectorTemplateBase&lt; T, bool &gt;::push_back</a>, <a href="/web-llvm/docs/api/namespaces/llvm/support/endian/#ae865d5defb8785b365f342375822beaa">llvm::support::endian::read32le</a> and <a href="/web-llvm/docs/api/namespaces/llvm/codeview/#a15b96719effacbb3d6e211f4ef768d98a5a2393a91d8bbd23f8fd97b38d660498">llvm::codeview::TypeRef</a>.</p>


<p>Referenced by <a href="#a25991c233686a63c58cc75b2fc0d9a5f">discoverTypeIndices</a>.</p>

</div>
</div>

### handleStaticDataMember() {#afa937cb598845b69e37a81f67ffd4c7b}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">uint32_t handleStaticDataMember (<a href="/web-llvm/docs/api/classes/llvm/arrayref">ArrayRef</a>&lt; uint8_t &gt; Data, uint32_t Offset, <a href="/web-llvm/docs/api/classes/llvm/smallvectorimpl">SmallVectorImpl</a>&lt; <a href="/web-llvm/docs/api/structs/llvm/codeview/tireference">TiReference</a> &gt; &amp; Refs)</td>
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



<p>Definition at line 165 of file <a href="/web-llvm/docs/api/files/lib/lib/debuginfo/lib/debuginfo/codeview/typeindexdiscovery-cpp">TypeIndexDiscovery.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/namespaces/llvm/#aa20539e89704d20b98b97e9c3feac934">llvm::Data</a>, <a href="#a03de03d741e52bd468fdcb9398d1d8db">getCStringLength</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a05f5b9a11bdcc5feba62899f95dcf878a3134224cba2545bc57954d3b072aebb4">llvm::Offset</a>, <a href="/web-llvm/docs/api/classes/llvm/smallvectortemplatebase/#af42bfbc067df27c19ee2fc859df58799">llvm::SmallVectorTemplateBase&lt; T, bool &gt;::push_back</a> and <a href="/web-llvm/docs/api/namespaces/llvm/codeview/#a15b96719effacbb3d6e211f4ef768d98a5a2393a91d8bbd23f8fd97b38d660498">llvm::codeview::TypeRef</a>.</p>


<p>Referenced by <a href="#aa9a744b2382a97226e765258f365a15c">handleFieldList</a>.</p>

</div>
</div>

### handleVFPtr() {#a93e8eec2fad7a5df11a2d003d095a6df}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">uint32_t handleVFPtr (<a href="/web-llvm/docs/api/classes/llvm/arrayref">ArrayRef</a>&lt; uint8_t &gt; Data, uint32_t Offset, <a href="/web-llvm/docs/api/classes/llvm/smallvectorimpl">SmallVectorImpl</a>&lt; <a href="/web-llvm/docs/api/structs/llvm/codeview/tireference">TiReference</a> &gt; &amp; Refs)</td>
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



<p>Definition at line 191 of file <a href="/web-llvm/docs/api/files/lib/lib/debuginfo/lib/debuginfo/codeview/typeindexdiscovery-cpp">TypeIndexDiscovery.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/namespaces/llvm/#aa20539e89704d20b98b97e9c3feac934">llvm::Data</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a05f5b9a11bdcc5feba62899f95dcf878a3134224cba2545bc57954d3b072aebb4">llvm::Offset</a>, <a href="/web-llvm/docs/api/classes/llvm/smallvectortemplatebase/#af42bfbc067df27c19ee2fc859df58799">llvm::SmallVectorTemplateBase&lt; T, bool &gt;::push_back</a> and <a href="/web-llvm/docs/api/namespaces/llvm/codeview/#a15b96719effacbb3d6e211f4ef768d98a5a2393a91d8bbd23f8fd97b38d660498">llvm::codeview::TypeRef</a>.</p>


<p>Referenced by <a href="#aa9a744b2382a97226e765258f365a15c">handleFieldList</a>.</p>

</div>
</div>

### handleVirtualBaseClass() {#ad79c1724545f758ab3046506669b993d}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">uint32_t handleVirtualBaseClass (<a href="/web-llvm/docs/api/classes/llvm/arrayref">ArrayRef</a>&lt; uint8_t &gt; Data, uint32_t Offset, bool IsIndirect, <a href="/web-llvm/docs/api/classes/llvm/smallvectorimpl">SmallVectorImpl</a>&lt; <a href="/web-llvm/docs/api/structs/llvm/codeview/tireference">TiReference</a> &gt; &amp; Refs)</td>
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



<p>Definition at line 175 of file <a href="/web-llvm/docs/api/files/lib/lib/debuginfo/lib/debuginfo/codeview/typeindexdiscovery-cpp">TypeIndexDiscovery.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/namespaces/llvm/#aa20539e89704d20b98b97e9c3feac934">llvm::Data</a>, <a href="#a8fa7e42c07f77ffbc093d9f6b80a36af">getEncodedIntegerLength</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a05f5b9a11bdcc5feba62899f95dcf878a3134224cba2545bc57954d3b072aebb4">llvm::Offset</a>, <a href="/web-llvm/docs/api/classes/llvm/smallvectortemplatebase/#af42bfbc067df27c19ee2fc859df58799">llvm::SmallVectorTemplateBase&lt; T, bool &gt;::push_back</a>, <a href="/web-llvm/docs/api/files/lib/lib/analysis/inlineorder-cpp/#a7ee6f0cb51c3b9056199e9a0001fe8c3a6f6cb72d544962fa333e2e34ce64f719">Size</a> and <a href="/web-llvm/docs/api/namespaces/llvm/codeview/#a15b96719effacbb3d6e211f4ef768d98a5a2393a91d8bbd23f8fd97b38d660498">llvm::codeview::TypeRef</a>.</p>


<p>Referenced by <a href="#aa9a744b2382a97226e765258f365a15c">handleFieldList</a>.</p>

</div>
</div>

### isIntroVirtual() {#ae644f68d24ac5b34de160fc910f2f3ec}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool isIntroVirtual (uint16_t Attrs)</td>
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



<p>Definition at line 23 of file <a href="/web-llvm/docs/api/files/lib/lib/debuginfo/lib/debuginfo/codeview/typeindexdiscovery-cpp">TypeIndexDiscovery.cpp</a>.</p>


<p>References <a href="#ae0c27fda221da0261489c8534a5e93c8">getMethodKind</a>, <a href="/web-llvm/docs/api/namespaces/llvm/codeview/#a168a6021abac4aa4ac613129e7fc38c7ab195ef30e97fd79fc09350e5528d0ede">llvm::codeview::IntroducingVirtual</a> and <a href="/web-llvm/docs/api/namespaces/llvm/codeview/#a168a6021abac4aa4ac613129e7fc38c7af60013c9b6ecfec449aeace857155e4c">llvm::codeview::PureIntroducingVirtual</a>.</p>


<p>Referenced by <a href="#abbb20c80e0c1ab59446de978f898fc1e">handleMethodOverloadList</a> and <a href="#a96ae8a0897a355d1c0a04a7eae3f2466">handleOneMethod</a>.</p>

</div>
</div>

### isMemberPointer() {#a4ff4587317327e576c1edb8aa61234fc}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool isMemberPointer (uint32_t Attrs)</td>
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



<p>Definition at line 34 of file <a href="/web-llvm/docs/api/files/lib/lib/debuginfo/lib/debuginfo/codeview/typeindexdiscovery-cpp">TypeIndexDiscovery.cpp</a>.</p>


<p>References <a href="#adf4718363dcb690ce2b5560c4f5c0689">getPointerMode</a>, <a href="/web-llvm/docs/api/files/lib/lib/codegen/regallocevictionadvisor-cpp/#aef71c4b21823f236e70cc6d62375adcd">Mode</a>, <a href="/web-llvm/docs/api/namespaces/llvm/codeview/#a0bfa8e65ecd85f3151f84bb53ad4bcbcaadf8be6fd2059290188a2c4b791edcd1">llvm::codeview::PointerToDataMember</a> and <a href="/web-llvm/docs/api/namespaces/llvm/codeview/#a0bfa8e65ecd85f3151f84bb53ad4bcbcada5a6fc5693ed8a5e467c414ca2589d3">llvm::codeview::PointerToMemberFunction</a>.</p>


<p>Referenced by <a href="#ab36e33dbf8516f7892bd335ff40545e9">handlePointer</a>.</p>

</div>
</div>

### resolveTypeIndexReferences() {#a350ae3fe286b68175d7eee301904506c}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void resolveTypeIndexReferences (<a href="/web-llvm/docs/api/classes/llvm/arrayref">ArrayRef</a>&lt; uint8_t &gt; RecordData, <a href="/web-llvm/docs/api/classes/llvm/arrayref">ArrayRef</a>&lt; <a href="/web-llvm/docs/api/structs/llvm/codeview/tireference">TiReference</a> &gt; Refs, <a href="/web-llvm/docs/api/classes/llvm/smallvectorimpl">SmallVectorImpl</a>&lt; <a href="/web-llvm/docs/api/classes/llvm/codeview/typeindex">TypeIndex</a> &gt; &amp; Indices)</td>
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



<p>Definition at line 463 of file <a href="/web-llvm/docs/api/files/lib/lib/debuginfo/lib/debuginfo/codeview/typeindexdiscovery-cpp">TypeIndexDiscovery.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/classes/llvm/smallvectorimpl/#a7efd1f0c1206d95e4fe01a9b49a57b82">llvm::SmallVectorImpl&lt; T &gt;::append</a>, <a href="/web-llvm/docs/api/classes/llvm/fixedstreamarray/#a2bd9a772b38ee46f2959576f4dcc77df">llvm::FixedStreamArray&lt; T &gt;::begin</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#aa1e1474f15df639f0d874b21f15666f7">llvm::cantFail</a>, <a href="/web-llvm/docs/api/classes/llvm/smallvectorimpl/#aac0ea55010b7b1a301e65a0baea057aa">llvm::SmallVectorImpl&lt; T &gt;::clear</a>, <a href="/web-llvm/docs/api/classes/llvm/arrayref/#a55089293ebaccd683a82d97170041376">llvm::ArrayRef&lt; T &gt;::drop_front</a>, <a href="/web-llvm/docs/api/classes/llvm/arrayref/#ac835b8735b1b2faec0efdca236e37d94">llvm::ArrayRef&lt; T &gt;::empty</a>, <a href="/web-llvm/docs/api/classes/llvm/fixedstreamarray/#a6dce16256d5fcd49185c72727b9eb908">llvm::FixedStreamArray&lt; T &gt;::end</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#ae1e26e57357947b25e392fd18ab000dbaaae6635e044ac56046b2893a529b5114">llvm::little</a>, <a href="/web-llvm/docs/api/classes/llvm/binarystreamreader/#ab88a8b3835c1028f8fd6c2b23f396d30">llvm::BinaryStreamReader::readArray</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a9db8c44b250b90e3ab7e4d144e7c9c2ea60baadb22e80b147e4885ad16760e569">llvm::Ref</a> and <a href="/web-llvm/docs/api/classes/llvm/binarystreamreader/#ab56b001a0bd245c9e73972be0ac5d593">llvm::BinaryStreamReader::setOffset</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/namespaces/llvm/codeview/#a231e60c4d5cb7cb0095c9a8995692046">llvm::codeview::discoverTypeIndices</a> and <a href="/web-llvm/docs/api/namespaces/llvm/codeview/#a26158f45e8fad6b48cac4bf7c2d9a98a">llvm::codeview::discoverTypeIndicesInSymbol</a>.</p>

</div>
</div>

</div>

<hr/>

<p class="doxyGeneratedBy">Generated via <a href="https://github.com/xpack/doxygen2docusaurus">doxygen2docusaurus</a> by <a href="https://www.doxygen.nl">Doxygen</a> 1.15.0.</p>

</div>
