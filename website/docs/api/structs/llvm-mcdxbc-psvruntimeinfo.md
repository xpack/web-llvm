---

# DO NOT EDIT!
# Automatically generated via doxygen2docusaurus by Doxygen.

slug: /api/structs/llvm/mcdxbc/psvruntimeinfo
custom_edit_url: null
toc_max_heading_level: 4
keywords:
  - doxygen
  - reference
  - struct

---

<div class="doxyPage">

# The `PSVRuntimeInfo` Struct Reference



## Declaration

<div class="doxyDeclaration">
struct llvm::mcdxbc::PSVRuntimeInfo { ... }
</div>

## Included Headers

<div class="doxyIncludesList">#include "<a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/mc/dxcontainerpsvinfo-h">llvm/MC/DXContainerPSVInfo.h</a>"
</div>

## Public Constructors Index

<table class="doxyMembersIndex">

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#adf5feeb5a45265902d25bf594073dbc8">PSVRuntimeInfo</a> ()</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">void</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a8ce05943db5cfcb56bbff62909a08e9c">write</a> (raw_ostream &amp;OS, uint32_t Version=std::numeric_limits&lt; uint32_t &gt;::max()) const</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a3afcf265b28cf1aae8dab4af4c89201c">finalize</a> (Triple::EnvironmentType Stage)</td>
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

## Public Member Attributes Index

<table class="doxyMembersIndex">

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">bool</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a5490623d9b43cc6ffe8281b7371e6a74">IsFinalized</a> = false</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/structs/llvm/dxbc/psv/v3/runtimeinfo">dxbc::PSV::v3::RuntimeInfo</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a09e379cfaaaa0b34ef750f75ea34c1f8">BaseData</a></td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/smallvector">SmallVector</a>&lt; <a href="/web-llvm/docs/api/structs/llvm/dxbc/psv/v2/resourcebindinfo">dxbc::PSV::v2::ResourceBindInfo</a> &gt;</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a3a9d9cf1ccca83f03102ae0774632632">Resources</a></td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/smallvector">SmallVector</a>&lt; <a href="/web-llvm/docs/api/structs/llvm/mcdxbc/psvsignatureelement">PSVSignatureElement</a> &gt;</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a3c8ade6d02bf04b437d29581f5ff4988">InputElements</a></td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/smallvector">SmallVector</a>&lt; <a href="/web-llvm/docs/api/structs/llvm/mcdxbc/psvsignatureelement">PSVSignatureElement</a> &gt;</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a7ee6638d1d25baadda882672ad2503fa">OutputElements</a></td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/smallvector">SmallVector</a>&lt; <a href="/web-llvm/docs/api/structs/llvm/mcdxbc/psvsignatureelement">PSVSignatureElement</a> &gt;</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a8278c95e752f65773bd8cfe97d883b26">PatchOrPrimElements</a></td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">std::array&lt; <a href="/web-llvm/docs/api/classes/llvm/smallvector">SmallVector</a>&lt; uint32_t &gt;, 4 &gt;</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ac017cec633bc354cbd920a98a5964d16">OutputVectorMasks</a></td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/smallvector">SmallVector</a>&lt; uint32_t &gt;</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a1ba1347b905c22e0c9e7c449c293cd76">PatchOrPrimMasks</a></td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">std::array&lt; <a href="/web-llvm/docs/api/classes/llvm/smallvector">SmallVector</a>&lt; uint32_t &gt;, 4 &gt;</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ad7517b46a0377e474b1696c096f00c84">InputOutputMap</a></td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/smallvector">SmallVector</a>&lt; uint32_t &gt;</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a57112dd0d88767da2954345fe632cc38">InputPatchMap</a></td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/smallvector">SmallVector</a>&lt; uint32_t &gt;</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a213212a265b45977a906b2519dc0bebd">PatchOutputMap</a></td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/stringref">llvm::StringRef</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a1af3eadc5b0b59892963b569a9bd7e33">EntryName</a></td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/smallvector">SmallVector</a>&lt; uint32_t, 64 &gt;</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a2096a32619784bfb9a43835883513189">IndexBuffer</a></td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/smallvector">SmallVector</a>&lt; <a href="/web-llvm/docs/api/structs/llvm/dxbc/psv/v0/signatureelement">llvm::dxbc::PSV::v0::SignatureElement</a>, 32 &gt;</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a32e4c379b84ecebb7e507a3caba021f5">SignatureElements</a></td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/stringtablebuilder">StringTableBuilder</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a9ab37149017fd236c992c6c27d3668ca">DXConStrTabBuilder</a></td>
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


<p>Definition at line 49 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/mc/dxcontainerpsvinfo-h">DXContainerPSVInfo.h</a>.</p>


<div class="doxySectionDef">

## Public Constructors

### PSVRuntimeInfo() {#adf5feeb5a45265902d25bf594073dbc8}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">llvm::mcdxbc::PSVRuntimeInfo::PSVRuntimeInfo ()</td>
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



<p>Definition at line 50 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/mc/dxcontainerpsvinfo-h">DXContainerPSVInfo.h</a>.</p>


<p>Reference <a href="#a09e379cfaaaa0b34ef750f75ea34c1f8">BaseData</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Public Member Functions

### finalize() {#a3afcf265b28cf1aae8dab4af4c89201c}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void PSVRuntimeInfo::finalize (<a href="/web-llvm/docs/api/classes/llvm/triple/#a1778f5c464f88710033f7e11e84a9324">Triple::EnvironmentType</a> Stage)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Declaration at line 80 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/mc/dxcontainerpsvinfo-h">DXContainerPSVInfo.h</a>, definition at line 150 of file <a href="/web-llvm/docs/api/files/lib/lib/mc/dxcontainerpsvinfo-cpp">DXContainerPSVInfo.cpp</a>.</p>


<p>References <a href="#a09e379cfaaaa0b34ef750f75ea34c1f8">BaseData</a>, <a href="#a1af3eadc5b0b59892963b569a9bd7e33">EntryName</a>, <a href="#a3c8ade6d02bf04b437d29581f5ff4988">InputElements</a>, <a href="/web-llvm/docs/api/namespaces/llvm/sys/#ab9f705441a3a825d4b8a93ca4476d4e7">llvm::sys::IsBigEndianHost</a>, <a href="#a5490623d9b43cc6ffe8281b7371e6a74">IsFinalized</a>, <a href="/web-llvm/docs/api/structs/llvm/dxbc/psv/v0/signatureelement/#aebac9f9125c2e5f269773c7bbb47dfb8">llvm::dxbc::PSV::v0::SignatureElement::NameOffset</a>, <a href="#a7ee6638d1d25baadda882672ad2503fa">OutputElements</a>, <a href="#a8278c95e752f65773bd8cfe97d883b26">PatchOrPrimElements</a>, <a href="/web-llvm/docs/api/files/lib/lib/mc/dxcontainerpsvinfo-cpp/#ad6c7bb71f11814fe88bf73f5c589a9e0">ProcessElementList</a>, <a href="#a3a9d9cf1ccca83f03102ae0774632632">Resources</a>, <a href="/web-llvm/docs/api/structs/llvm/dxbc/psv/v0/signatureelement/#a958ddaed23b06c2af79165e71ecdbca3">llvm::dxbc::PSV::v0::SignatureElement::swapBytes</a> and <a href="/web-llvm/docs/api/namespaces/llvm/#a06041e3bf4b0a9e8984809413ddd9506">llvm::zip</a>.</p>

</div>
</div>

### write() {#a8ce05943db5cfcb56bbff62909a08e9c}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void PSVRuntimeInfo::write (<a href="/web-llvm/docs/api/classes/llvm/raw-ostream">raw_ostream</a> &amp; OS, uint32_t Version=std::numeric_limits&lt; uint32_t &gt;<a href="/web-llvm/docs/api/namespaces/llvm/#a003389e30c9b0ec678f95bad1f3dbc4a">::max</a>())</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Declaration at line 77 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/mc/dxcontainerpsvinfo-h">DXContainerPSVInfo.h</a>, definition at line 69 of file <a href="/web-llvm/docs/api/files/lib/lib/mc/dxcontainerpsvinfo-cpp">DXContainerPSVInfo.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/silowercontrolflow-cpp/#a4868c5d81c5ccc98c47aeab6244346a0">assert</a>, <a href="#a09e379cfaaaa0b34ef750f75ea34c1f8">BaseData</a>, <a href="/web-llvm/docs/api/files/lib/lib/support/md5-cpp/#ac0eafdc9ee161b71e7af98af736952fd">I</a>, <a href="#ad7517b46a0377e474b1696c096f00c84">InputOutputMap</a>, <a href="#a57112dd0d88767da2954345fe632cc38">InputPatchMap</a>, <a href="#a5490623d9b43cc6ffe8281b7371e6a74">IsFinalized</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#ae1e26e57357947b25e392fd18ab000dbaaae6635e044ac56046b2893a529b5114">llvm::little</a>, <a href="#ac017cec633bc354cbd920a98a5964d16">OutputVectorMasks</a>, <a href="#a1ba1347b905c22e0c9e7c449c293cd76">PatchOrPrimMasks</a>, <a href="#a213212a265b45977a906b2519dc0bebd">PatchOutputMap</a>, <a href="#a3a9d9cf1ccca83f03102ae0774632632">Resources</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a689a023f54d38d41f6d952cac41ee538">llvm::Version</a>, <a href="/web-llvm/docs/api/classes/llvm/raw-ostream/#a6e0cbc5c8568d8446c284c8538b2c9f1">llvm::raw_ostream::write</a>, <a href="/web-llvm/docs/api/namespaces/llvm/support/endian/#add1f2d1d972957d22186f4ec92f985f6">llvm::support::endian::write</a> and <a href="/web-llvm/docs/api/namespaces/llvm/support/endian/#a0d40b2f1e459508b598037aca1a32cfc">llvm::support::endian::write_array</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Public Member Attributes

### BaseData {#a09e379cfaaaa0b34ef750f75ea34c1f8}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">dxbc::PSV::v3::RuntimeInfo llvm::mcdxbc::PSVRuntimeInfo::BaseData</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 54 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/mc/dxcontainerpsvinfo-h">DXContainerPSVInfo.h</a>.</p>


<p>Referenced by <a href="#a3afcf265b28cf1aae8dab4af4c89201c">finalize</a>, <a href="#adf5feeb5a45265902d25bf594073dbc8">PSVRuntimeInfo</a> and <a href="#a8ce05943db5cfcb56bbff62909a08e9c">write</a>.</p>

</div>
</div>

### EntryName {#a1af3eadc5b0b59892963b569a9bd7e33}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">llvm::StringRef llvm::mcdxbc::PSVRuntimeInfo::EntryName</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 72 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/mc/dxcontainerpsvinfo-h">DXContainerPSVInfo.h</a>.</p>


<p>Referenced by <a href="#a3afcf265b28cf1aae8dab4af4c89201c">finalize</a>.</p>

</div>
</div>

### InputElements {#a3c8ade6d02bf04b437d29581f5ff4988}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">SmallVector&lt;PSVSignatureElement&gt; llvm::mcdxbc::PSVRuntimeInfo::InputElements</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 56 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/mc/dxcontainerpsvinfo-h">DXContainerPSVInfo.h</a>.</p>


<p>Referenced by <a href="#a3afcf265b28cf1aae8dab4af4c89201c">finalize</a>.</p>

</div>
</div>

### InputOutputMap {#ad7517b46a0377e474b1696c096f00c84}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">std::array&lt;SmallVector&lt;uint32_t&gt;, 4&gt; llvm::mcdxbc::PSVRuntimeInfo::InputOutputMap</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 69 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/mc/dxcontainerpsvinfo-h">DXContainerPSVInfo.h</a>.</p>


<p>Referenced by <a href="#a8ce05943db5cfcb56bbff62909a08e9c">write</a>.</p>

</div>
</div>

### InputPatchMap {#a57112dd0d88767da2954345fe632cc38}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">SmallVector&lt;uint32_t&gt; llvm::mcdxbc::PSVRuntimeInfo::InputPatchMap</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 70 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/mc/dxcontainerpsvinfo-h">DXContainerPSVInfo.h</a>.</p>


<p>Referenced by <a href="#a8ce05943db5cfcb56bbff62909a08e9c">write</a>.</p>

</div>
</div>

### IsFinalized {#a5490623d9b43cc6ffe8281b7371e6a74}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool llvm::mcdxbc::PSVRuntimeInfo::IsFinalized = false</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 53 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/mc/dxcontainerpsvinfo-h">DXContainerPSVInfo.h</a>.</p>


<p>Referenced by <a href="#a3afcf265b28cf1aae8dab4af4c89201c">finalize</a> and <a href="#a8ce05943db5cfcb56bbff62909a08e9c">write</a>.</p>

</div>
</div>

### OutputElements {#a7ee6638d1d25baadda882672ad2503fa}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">SmallVector&lt;PSVSignatureElement&gt; llvm::mcdxbc::PSVRuntimeInfo::OutputElements</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 57 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/mc/dxcontainerpsvinfo-h">DXContainerPSVInfo.h</a>.</p>


<p>Referenced by <a href="#a3afcf265b28cf1aae8dab4af4c89201c">finalize</a>.</p>

</div>
</div>

### OutputVectorMasks {#ac017cec633bc354cbd920a98a5964d16}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">std::array&lt;SmallVector&lt;uint32_t&gt;, 4&gt; llvm::mcdxbc::PSVRuntimeInfo::OutputVectorMasks</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 67 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/mc/dxcontainerpsvinfo-h">DXContainerPSVInfo.h</a>.</p>


<p>Referenced by <a href="#a8ce05943db5cfcb56bbff62909a08e9c">write</a>.</p>

</div>
</div>

### PatchOrPrimElements {#a8278c95e752f65773bd8cfe97d883b26}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">SmallVector&lt;PSVSignatureElement&gt; llvm::mcdxbc::PSVRuntimeInfo::PatchOrPrimElements</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 58 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/mc/dxcontainerpsvinfo-h">DXContainerPSVInfo.h</a>.</p>


<p>Referenced by <a href="#a3afcf265b28cf1aae8dab4af4c89201c">finalize</a>.</p>

</div>
</div>

### PatchOrPrimMasks {#a1ba1347b905c22e0c9e7c449c293cd76}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">SmallVector&lt;uint32_t&gt; llvm::mcdxbc::PSVRuntimeInfo::PatchOrPrimMasks</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 68 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/mc/dxcontainerpsvinfo-h">DXContainerPSVInfo.h</a>.</p>


<p>Referenced by <a href="#a8ce05943db5cfcb56bbff62909a08e9c">write</a>.</p>

</div>
</div>

### PatchOutputMap {#a213212a265b45977a906b2519dc0bebd}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">SmallVector&lt;uint32_t&gt; llvm::mcdxbc::PSVRuntimeInfo::PatchOutputMap</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 71 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/mc/dxcontainerpsvinfo-h">DXContainerPSVInfo.h</a>.</p>


<p>Referenced by <a href="#a8ce05943db5cfcb56bbff62909a08e9c">write</a>.</p>

</div>
</div>

### Resources {#a3a9d9cf1ccca83f03102ae0774632632}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">SmallVector&lt;dxbc::PSV::v2::ResourceBindInfo&gt; llvm::mcdxbc::PSVRuntimeInfo::Resources</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 55 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/mc/dxcontainerpsvinfo-h">DXContainerPSVInfo.h</a>.</p>


<p>Referenced by <a href="#a3afcf265b28cf1aae8dab4af4c89201c">finalize</a> and <a href="#a8ce05943db5cfcb56bbff62909a08e9c">write</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Private Member Attributes

### DXConStrTabBuilder {#a9ab37149017fd236c992c6c27d3668ca}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">StringTableBuilder llvm::mcdxbc::PSVRuntimeInfo::DXConStrTabBuilder</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 85 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/mc/dxcontainerpsvinfo-h">DXContainerPSVInfo.h</a>.</p>

</div>
</div>

### IndexBuffer {#a2096a32619784bfb9a43835883513189}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">SmallVector&lt;uint32_t, 64&gt; llvm::mcdxbc::PSVRuntimeInfo::IndexBuffer</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 83 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/mc/dxcontainerpsvinfo-h">DXContainerPSVInfo.h</a>.</p>

</div>
</div>

### SignatureElements {#a32e4c379b84ecebb7e507a3caba021f5}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">SmallVector&lt;llvm::dxbc::PSV::v0::SignatureElement, 32&gt; llvm::mcdxbc::PSVRuntimeInfo::SignatureElements</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 84 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/mc/dxcontainerpsvinfo-h">DXContainerPSVInfo.h</a>.</p>

</div>
</div>

</div>

<hr/>

The documentation for this struct was generated from the following files:

<ul>
<li><a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/mc/dxcontainerpsvinfo-h">DXContainerPSVInfo.h</a></li>
<li><a href="/web-llvm/docs/api/files/lib/lib/mc/dxcontainerpsvinfo-cpp">DXContainerPSVInfo.cpp</a></li>
</ul>

<hr/>

<p class="doxyGeneratedBy">Generated via <a href="https://github.com/xpack/doxygen2docusaurus">doxygen2docusaurus</a> by <a href="https://www.doxygen.nl">Doxygen</a> 1.14.0.</p>

</div>
