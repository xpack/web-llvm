---

# DO NOT EDIT!
# Automatically generated via doxygen2docusaurus by Doxygen.

slug: /api/structs/llvm/dxcontaineryaml/psvinfo
custom_edit_url: null
toc_max_heading_level: 4
keywords:
  - doxygen
  - reference
  - struct

---

<div class="doxyPage">

# `PSVInfo` Struct



## Declaration

<div class="doxyDeclaration">
struct llvm::DXContainerYAML::PSVInfo { ... }
</div>

## Included Headers

<div class="doxyIncludesList">#include "<a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/objectyaml/dxcontaineryaml-h">llvm/ObjectYAML/DXContainerYAML.h</a>"
</div>

## Public Member Typedefs Index

<table class="doxyMembersIndex">

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">using</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#aed5956c024c3ddad3c20f802821563b3">MaskVector</a> = <a href="/web-llvm/docs/api/classes/llvm/smallvector">SmallVector</a>&lt; llvm::yaml::Hex32 &gt;</td>
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

## Public Constructors Index

<table class="doxyMembersIndex">

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a1b90da6546433d7d23cd840f04bf07c7">PSVInfo</a> ()</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a06695730ea4784857966d6149010b697">PSVInfo</a> (const dxbc::PSV::v0::RuntimeInfo *P, uint16_t Stage)</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#aaef5807a887ccbf45d0a43790b7f06a2">PSVInfo</a> (const dxbc::PSV::v1::RuntimeInfo *P)</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#aa4bf7682cdfd87a9c6d850428d7a7c8b">PSVInfo</a> (const dxbc::PSV::v2::RuntimeInfo *P)</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a594d619b949d38aa5d402e81a23ca13a">PSVInfo</a> (const dxbc::PSV::v3::RuntimeInfo *P, StringRef StringTable)</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#aef40b4410af614b5a4771ef2dfc5df47">mapInfoForVersion</a> (yaml::IO &amp;IO)</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">uint32_t</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a324c4bf6a0fd537c2738464a8ed2e0d1">Version</a></td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#af0a15b7e97f396db8d6fa3ed8774d3b3">Info</a></td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">uint32_t</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ae8d643e482694699c73d917ae25d6efc">ResourceStride</a></td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/smallvector">SmallVector</a>&lt; <a href="/web-llvm/docs/api/namespaces/llvm/dxcontaineryaml/#ac30535c881142b6321377959bd222fa9">ResourceBindInfo</a> &gt;</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a9ca0d2b25c023e503b15a3d56480b6a8">Resources</a></td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/smallvector">SmallVector</a>&lt; <a href="/web-llvm/docs/api/structs/llvm/dxcontaineryaml/signatureelement">SignatureElement</a> &gt;</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ade850344574d5f24343d9b8f7cac2a59">SigInputElements</a></td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/smallvector">SmallVector</a>&lt; <a href="/web-llvm/docs/api/structs/llvm/dxcontaineryaml/signatureelement">SignatureElement</a> &gt;</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a7f2b1d45c6da697cd4f7d29eb273f6b8">SigOutputElements</a></td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/smallvector">SmallVector</a>&lt; <a href="/web-llvm/docs/api/structs/llvm/dxcontaineryaml/signatureelement">SignatureElement</a> &gt;</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a8ce8a80cc6b5b21dc6b8961af4f033fe">SigPatchOrPrimElements</a></td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">std::array&lt; <a href="#aed5956c024c3ddad3c20f802821563b3">MaskVector</a>, 4 &gt;</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#af221e5ae1e7ead206496874a6d161098">OutputVectorMasks</a></td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="#aed5956c024c3ddad3c20f802821563b3">MaskVector</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a8c0982570296d296606f49dfb0d229c2">PatchOrPrimMasks</a></td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">std::array&lt; <a href="#aed5956c024c3ddad3c20f802821563b3">MaskVector</a>, 4 &gt;</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a0c3bdcfa633042b5864d44c45a99ee23">InputOutputMap</a></td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="#aed5956c024c3ddad3c20f802821563b3">MaskVector</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#af4e1583db6a1b5de4b8f41b09ca7f48f">InputPatchMap</a></td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="#aed5956c024c3ddad3c20f802821563b3">MaskVector</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a21fe1d431c473d674350c2f216f197b0">PatchOutputMap</a></td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/stringref">StringRef</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a26c5ab65a2cd81e3a273a737472cfbf5">EntryName</a></td>
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


<p>Definition at line 105 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/objectyaml/dxcontaineryaml-h">DXContainerYAML.h</a>.</p>


<div class="doxySectionDef">

## Public Member Typedefs

### MaskVector {#aed5956c024c3ddad3c20f802821563b3}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">using llvm::DXContainerYAML::PSVInfo::MaskVector =  SmallVector&lt;llvm::yaml::Hex32&gt;</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 118 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/objectyaml/dxcontaineryaml-h">DXContainerYAML.h</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Public Constructors

### PSVInfo() {#a1b90da6546433d7d23cd840f04bf07c7}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">llvm::DXContainerYAML::PSVInfo::PSVInfo ()</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Declaration at line 129 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/objectyaml/dxcontaineryaml-h">DXContainerYAML.h</a>, definition at line 48 of file <a href="/web-llvm/docs/api/files/lib/lib/objectyaml/dxcontaineryaml-cpp">DXContainerYAML.cpp</a>.</p>


<p>References <a href="#af0a15b7e97f396db8d6fa3ed8774d3b3">Info</a> and <a href="#a324c4bf6a0fd537c2738464a8ed2e0d1">Version</a>.</p>

</div>
</div>

### PSVInfo() {#a06695730ea4784857966d6149010b697}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">llvm::DXContainerYAML::PSVInfo::PSVInfo (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/structs/llvm/dxbc/psv/v0/runtimeinfo">dxbc::PSV::v0::RuntimeInfo</a> * P, uint16_t Stage)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Declaration at line 130 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/objectyaml/dxcontaineryaml-h">DXContainerYAML.h</a>, definition at line 52 of file <a href="/web-llvm/docs/api/files/lib/lib/objectyaml/dxcontaineryaml-cpp">DXContainerYAML.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/silowercontrolflow-cpp/#a4868c5d81c5ccc98c47aeab6244346a0">assert</a>, <a href="#af0a15b7e97f396db8d6fa3ed8774d3b3">Info</a>, <a href="/web-llvm/docs/api/files/lib/lib/option/option-cpp/#a04665169063c8ca1f2ea96c27fc7c2b2">P</a> and <a href="#a324c4bf6a0fd537c2738464a8ed2e0d1">Version</a>.</p>

</div>
</div>

### PSVInfo() {#aaef5807a887ccbf45d0a43790b7f06a2}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">llvm::DXContainerYAML::PSVInfo::PSVInfo (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/structs/llvm/dxbc/psv/v1/runtimeinfo">dxbc::PSV::v1::RuntimeInfo</a> * P)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Declaration at line 131 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/objectyaml/dxcontaineryaml-h">DXContainerYAML.h</a>, definition at line 65 of file <a href="/web-llvm/docs/api/files/lib/lib/objectyaml/dxcontaineryaml-cpp">DXContainerYAML.cpp</a>.</p>


<p>References <a href="#af0a15b7e97f396db8d6fa3ed8774d3b3">Info</a>, <a href="/web-llvm/docs/api/files/lib/lib/option/option-cpp/#a04665169063c8ca1f2ea96c27fc7c2b2">P</a> and <a href="#a324c4bf6a0fd537c2738464a8ed2e0d1">Version</a>.</p>

</div>
</div>

### PSVInfo() {#aa4bf7682cdfd87a9c6d850428d7a7c8b}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">llvm::DXContainerYAML::PSVInfo::PSVInfo (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/structs/llvm/dxbc/psv/v2/runtimeinfo">dxbc::PSV::v2::RuntimeInfo</a> * P)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Declaration at line 132 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/objectyaml/dxcontaineryaml-h">DXContainerYAML.h</a>, definition at line 71 of file <a href="/web-llvm/docs/api/files/lib/lib/objectyaml/dxcontaineryaml-cpp">DXContainerYAML.cpp</a>.</p>


<p>References <a href="#af0a15b7e97f396db8d6fa3ed8774d3b3">Info</a>, <a href="/web-llvm/docs/api/files/lib/lib/option/option-cpp/#a04665169063c8ca1f2ea96c27fc7c2b2">P</a> and <a href="#a324c4bf6a0fd537c2738464a8ed2e0d1">Version</a>.</p>

</div>
</div>

### PSVInfo() {#a594d619b949d38aa5d402e81a23ca13a}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">llvm::DXContainerYAML::PSVInfo::PSVInfo (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/structs/llvm/dxbc/psv/v3/runtimeinfo">dxbc::PSV::v3::RuntimeInfo</a> * P, <a href="/web-llvm/docs/api/classes/llvm/stringref">StringRef</a> StringTable)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Declaration at line 133 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/objectyaml/dxcontaineryaml-h">DXContainerYAML.h</a>, definition at line 77 of file <a href="/web-llvm/docs/api/files/lib/lib/objectyaml/dxcontaineryaml-cpp">DXContainerYAML.cpp</a>.</p>


<p>References <a href="#a26c5ab65a2cd81e3a273a737472cfbf5">EntryName</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a086e9fbdb06276db7753101a08a63adf">llvm::find</a>, <a href="#af0a15b7e97f396db8d6fa3ed8774d3b3">Info</a>, <a href="/web-llvm/docs/api/files/lib/lib/option/option-cpp/#a04665169063c8ca1f2ea96c27fc7c2b2">P</a>, <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/utils/simplifylibcalls-cpp/#ab845621311caa169682acb9c65516ae1">substr</a> and <a href="#a324c4bf6a0fd537c2738464a8ed2e0d1">Version</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Public Member Functions

### mapInfoForVersion() {#aef40b4410af614b5a4771ef2dfc5df47}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void llvm::DXContainerYAML::PSVInfo::mapInfoForVersion (<a href="/web-llvm/docs/api/classes/llvm/yaml/io">yaml::IO</a> &amp; IO)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Declaration at line 127 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/objectyaml/dxcontaineryaml-h">DXContainerYAML.h</a>, definition at line 295 of file <a href="/web-llvm/docs/api/files/lib/lib/objectyaml/dxcontaineryaml-cpp">DXContainerYAML.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/classes/llvm/triple/#a1778f5c464f88710033f7e11e84a9324ab926bec66aeb0288525973f203bcb94a">llvm::Triple::Amplification</a>, <a href="/web-llvm/docs/api/unions/llvm/dxbc/pipelinepsvinfo/#a92336bbde852654055d21fb2fd059189">llvm::dxbc::PipelinePSVInfo::AS</a>, <a href="/web-llvm/docs/api/structs/llvm/dxbc/pixelpsvinfo/#aa18630f893a1c466f205a6c0fab852a9">llvm::dxbc::PixelPSVInfo::DepthOutput</a>, <a href="/web-llvm/docs/api/classes/llvm/triple/#a1778f5c464f88710033f7e11e84a9324a9250a1f506b7407b838bf0b494f9cd33">llvm::Triple::Domain</a>, <a href="/web-llvm/docs/api/unions/llvm/dxbc/pipelinepsvinfo/#aeb9c8da0ce6c50c91242a3736013d465">llvm::dxbc::PipelinePSVInfo::DS</a>, <a href="#a26c5ab65a2cd81e3a273a737472cfbf5">EntryName</a>, <a href="/web-llvm/docs/api/classes/llvm/triple/#a1778f5c464f88710033f7e11e84a9324ade3aad57a34a47654ebeee1a2d4ab960">llvm::Triple::Geometry</a>, <a href="/web-llvm/docs/api/namespaces/llvm/dxbc/#a5d85020f593c54f3045af36f2175aa24">llvm::dxbc::getShaderStage</a>, <a href="/web-llvm/docs/api/structs/llvm/dxbc/meshpsvinfo/#a8062aadbcf3e54dcb6ae21e9d0f6c009">llvm::dxbc::MeshPSVInfo::GroupSharedBytesDependentOnViewID</a>, <a href="/web-llvm/docs/api/structs/llvm/dxbc/meshpsvinfo/#ac2a0ad0f49a291f38b185dfdccf0973e">llvm::dxbc::MeshPSVInfo::GroupSharedBytesUsed</a>, <a href="/web-llvm/docs/api/unions/llvm/dxbc/pipelinepsvinfo/#ab88e11b1bb3f2f3dea16ff83cbb592e8">llvm::dxbc::PipelinePSVInfo::GS</a>, <a href="/web-llvm/docs/api/unions/llvm/dxbc/pipelinepsvinfo/#ac1f286f64db945ee615260349fb28805">llvm::dxbc::PipelinePSVInfo::HS</a>, <a href="/web-llvm/docs/api/classes/llvm/triple/#a1778f5c464f88710033f7e11e84a9324ac8bc9b9934c75b722dcdde3b705c0a51">llvm::Triple::Hull</a>, <a href="#af0a15b7e97f396db8d6fa3ed8774d3b3">Info</a>, <a href="/web-llvm/docs/api/structs/llvm/dxbc/domainpsvinfo/#a42a543a9e16226a8bca2d95ffccf1de0">llvm::dxbc::DomainPSVInfo::InputControlPointCount</a>, <a href="/web-llvm/docs/api/structs/llvm/dxbc/hullpsvinfo/#af984dc292371e17cdef6b41720983872">llvm::dxbc::HullPSVInfo::InputControlPointCount</a>, <a href="/web-llvm/docs/api/structs/llvm/dxbc/geometrypsvinfo/#a536e2a915a738e83c752b687ea7f5d6c">llvm::dxbc::GeometryPSVInfo::InputPrimitive</a>, <a href="/web-llvm/docs/api/classes/llvm/yaml/io/#a76b59883a4b23c1cb5c5f55eac119f0d">llvm::yaml::IO::mapRequired</a>, <a href="/web-llvm/docs/api/structs/llvm/dxbc/meshpsvinfo/#a5feb190e8853f8cbc2611ff824f29903">llvm::dxbc::MeshPSVInfo::MaxOutputPrimitives</a>, <a href="/web-llvm/docs/api/structs/llvm/dxbc/meshpsvinfo/#a5cb93155aadb278c5fb3290a7c6ffa06">llvm::dxbc::MeshPSVInfo::MaxOutputVertices</a>, <a href="/web-llvm/docs/api/classes/llvm/triple/#a1778f5c464f88710033f7e11e84a9324aa1a97c079fbb80fcd9ab0f5fa24f3025">llvm::Triple::Mesh</a>, <a href="/web-llvm/docs/api/unions/llvm/dxbc/pipelinepsvinfo/#a1009151769c44b01b28de5428a0d7b4d">llvm::dxbc::PipelinePSVInfo::MS</a>, <a href="/web-llvm/docs/api/structs/llvm/dxbc/hullpsvinfo/#a98602553bb248b228689a255134c59ce">llvm::dxbc::HullPSVInfo::OutputControlPointCount</a>, <a href="/web-llvm/docs/api/structs/llvm/dxbc/domainpsvinfo/#a9e419095dadb7ea0e3d067fe62068323">llvm::dxbc::DomainPSVInfo::OutputPositionPresent</a>, <a href="/web-llvm/docs/api/structs/llvm/dxbc/geometrypsvinfo/#a8225e1c723e70629adb40c537eac1a7f">llvm::dxbc::GeometryPSVInfo::OutputPositionPresent</a>, <a href="/web-llvm/docs/api/structs/llvm/dxbc/vertexpsvinfo/#a5b016e2391e7c369c002e210b69c9d96">llvm::dxbc::VertexPSVInfo::OutputPositionPresent</a>, <a href="/web-llvm/docs/api/structs/llvm/dxbc/geometrypsvinfo/#ab0be274ab4868424a684e8fd4db549bc">llvm::dxbc::GeometryPSVInfo::OutputStreamMask</a>, <a href="/web-llvm/docs/api/structs/llvm/dxbc/geometrypsvinfo/#a62e6eec93acc63e0efd089364eb9bc0a">llvm::dxbc::GeometryPSVInfo::OutputTopology</a>, <a href="/web-llvm/docs/api/structs/llvm/dxbc/amplificationpsvinfo/#a971024042852ab7422aafaae910bb337">llvm::dxbc::AmplificationPSVInfo::PayloadSizeInBytes</a>, <a href="/web-llvm/docs/api/structs/llvm/dxbc/meshpsvinfo/#a322e5d5327920e4583c6a384626d9030">llvm::dxbc::MeshPSVInfo::PayloadSizeInBytes</a>, <a href="/web-llvm/docs/api/classes/llvm/triple/#a1778f5c464f88710033f7e11e84a9324a4bd403d91c4535171833f92e0ce36137">llvm::Triple::Pixel</a>, <a href="/web-llvm/docs/api/unions/llvm/dxbc/pipelinepsvinfo/#ae5924bee9872a00cf7d876c9604b9581">llvm::dxbc::PipelinePSVInfo::PS</a>, <a href="/web-llvm/docs/api/structs/llvm/dxbc/pixelpsvinfo/#a96180b28723758b850e31f21bc981f10">llvm::dxbc::PixelPSVInfo::SampleFrequency</a>, <a href="/web-llvm/docs/api/structs/llvm/dxbc/domainpsvinfo/#a915596ee8175c668d0a972c91555dbca">llvm::dxbc::DomainPSVInfo::TessellatorDomain</a>, <a href="/web-llvm/docs/api/structs/llvm/dxbc/hullpsvinfo/#afd8b809e555302b775b636809a9fe683">llvm::dxbc::HullPSVInfo::TessellatorDomain</a>, <a href="/web-llvm/docs/api/structs/llvm/dxbc/hullpsvinfo/#a13393193076b82684fa8179dc1d50381">llvm::dxbc::HullPSVInfo::TessellatorOutputPrimitive</a>, <a href="#a324c4bf6a0fd537c2738464a8ed2e0d1">Version</a>, <a href="/web-llvm/docs/api/classes/llvm/triple/#a1778f5c464f88710033f7e11e84a9324a71b983b2a1bf8a46c5ac7d21de26fb4a">llvm::Triple::Vertex</a> and <a href="/web-llvm/docs/api/unions/llvm/dxbc/pipelinepsvinfo/#a4628b8cca428f656f153f8e89bf7d455">llvm::dxbc::PipelinePSVInfo::VS</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/structs/llvm/yaml/mappingtraits-24dae25eef0cf89bd251b2ce9cf3fa24/#a6808d9de67d634c84c6549cc53e365bb">llvm::yaml::MappingTraits&lt; DXContainerYAML::PSVInfo &gt;::mapping</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Public Member Attributes

### EntryName {#a26c5ab65a2cd81e3a273a737472cfbf5}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">StringRef llvm::DXContainerYAML::PSVInfo::EntryName</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 125 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/objectyaml/dxcontaineryaml-h">DXContainerYAML.h</a>.</p>


<p>Referenced by <a href="#aef40b4410af614b5a4771ef2dfc5df47">mapInfoForVersion</a> and <a href="#a594d619b949d38aa5d402e81a23ca13a">PSVInfo</a>.</p>

</div>
</div>

### Info {#af0a15b7e97f396db8d6fa3ed8774d3b3}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">dxbc::PSV::v3::RuntimeInfo llvm::DXContainerYAML::PSVInfo::Info</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 111 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/objectyaml/dxcontaineryaml-h">DXContainerYAML.h</a>.</p>


<p>Referenced by <a href="#aef40b4410af614b5a4771ef2dfc5df47">mapInfoForVersion</a>, <a href="/web-llvm/docs/api/structs/llvm/yaml/mappingtraits-24dae25eef0cf89bd251b2ce9cf3fa24/#a6808d9de67d634c84c6549cc53e365bb">llvm::yaml::MappingTraits&lt; DXContainerYAML::PSVInfo &gt;::mapping</a>, <a href="#a1b90da6546433d7d23cd840f04bf07c7">PSVInfo</a>, <a href="#a06695730ea4784857966d6149010b697">PSVInfo</a>, <a href="#aaef5807a887ccbf45d0a43790b7f06a2">PSVInfo</a>, <a href="#aa4bf7682cdfd87a9c6d850428d7a7c8b">PSVInfo</a> and <a href="#a594d619b949d38aa5d402e81a23ca13a">PSVInfo</a>.</p>

</div>
</div>

### InputOutputMap {#a0c3bdcfa633042b5864d44c45a99ee23}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">std::array&lt;MaskVector, 4&gt; llvm::DXContainerYAML::PSVInfo::InputOutputMap</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 121 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/objectyaml/dxcontaineryaml-h">DXContainerYAML.h</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/structs/llvm/yaml/mappingtraits-24dae25eef0cf89bd251b2ce9cf3fa24/#a6808d9de67d634c84c6549cc53e365bb">llvm::yaml::MappingTraits&lt; DXContainerYAML::PSVInfo &gt;::mapping</a>.</p>

</div>
</div>

### InputPatchMap {#af4e1583db6a1b5de4b8f41b09ca7f48f}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">MaskVector llvm::DXContainerYAML::PSVInfo::InputPatchMap</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 122 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/objectyaml/dxcontaineryaml-h">DXContainerYAML.h</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/structs/llvm/yaml/mappingtraits-24dae25eef0cf89bd251b2ce9cf3fa24/#a6808d9de67d634c84c6549cc53e365bb">llvm::yaml::MappingTraits&lt; DXContainerYAML::PSVInfo &gt;::mapping</a>.</p>

</div>
</div>

### OutputVectorMasks {#af221e5ae1e7ead206496874a6d161098}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">std::array&lt;MaskVector, 4&gt; llvm::DXContainerYAML::PSVInfo::OutputVectorMasks</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 119 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/objectyaml/dxcontaineryaml-h">DXContainerYAML.h</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/structs/llvm/yaml/mappingtraits-24dae25eef0cf89bd251b2ce9cf3fa24/#a6808d9de67d634c84c6549cc53e365bb">llvm::yaml::MappingTraits&lt; DXContainerYAML::PSVInfo &gt;::mapping</a>.</p>

</div>
</div>

### PatchOrPrimMasks {#a8c0982570296d296606f49dfb0d229c2}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">MaskVector llvm::DXContainerYAML::PSVInfo::PatchOrPrimMasks</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 120 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/objectyaml/dxcontaineryaml-h">DXContainerYAML.h</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/structs/llvm/yaml/mappingtraits-24dae25eef0cf89bd251b2ce9cf3fa24/#a6808d9de67d634c84c6549cc53e365bb">llvm::yaml::MappingTraits&lt; DXContainerYAML::PSVInfo &gt;::mapping</a>.</p>

</div>
</div>

### PatchOutputMap {#a21fe1d431c473d674350c2f216f197b0}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">MaskVector llvm::DXContainerYAML::PSVInfo::PatchOutputMap</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 123 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/objectyaml/dxcontaineryaml-h">DXContainerYAML.h</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/structs/llvm/yaml/mappingtraits-24dae25eef0cf89bd251b2ce9cf3fa24/#a6808d9de67d634c84c6549cc53e365bb">llvm::yaml::MappingTraits&lt; DXContainerYAML::PSVInfo &gt;::mapping</a>.</p>

</div>
</div>

### Resources {#a9ca0d2b25c023e503b15a3d56480b6a8}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">SmallVector&lt;ResourceBindInfo&gt; llvm::DXContainerYAML::PSVInfo::Resources</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 113 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/objectyaml/dxcontaineryaml-h">DXContainerYAML.h</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/structs/llvm/yaml/mappingtraits-24dae25eef0cf89bd251b2ce9cf3fa24/#a6808d9de67d634c84c6549cc53e365bb">llvm::yaml::MappingTraits&lt; DXContainerYAML::PSVInfo &gt;::mapping</a>.</p>

</div>
</div>

### ResourceStride {#ae8d643e482694699c73d917ae25d6efc}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">uint32_t llvm::DXContainerYAML::PSVInfo::ResourceStride</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 112 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/objectyaml/dxcontaineryaml-h">DXContainerYAML.h</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/structs/llvm/yaml/mappingtraits-24dae25eef0cf89bd251b2ce9cf3fa24/#a6808d9de67d634c84c6549cc53e365bb">llvm::yaml::MappingTraits&lt; DXContainerYAML::PSVInfo &gt;::mapping</a>.</p>

</div>
</div>

### SigInputElements {#ade850344574d5f24343d9b8f7cac2a59}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">SmallVector&lt;SignatureElement&gt; llvm::DXContainerYAML::PSVInfo::SigInputElements</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 114 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/objectyaml/dxcontaineryaml-h">DXContainerYAML.h</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/structs/llvm/yaml/mappingtraits-24dae25eef0cf89bd251b2ce9cf3fa24/#a6808d9de67d634c84c6549cc53e365bb">llvm::yaml::MappingTraits&lt; DXContainerYAML::PSVInfo &gt;::mapping</a>.</p>

</div>
</div>

### SigOutputElements {#a7f2b1d45c6da697cd4f7d29eb273f6b8}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">SmallVector&lt;SignatureElement&gt; llvm::DXContainerYAML::PSVInfo::SigOutputElements</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 115 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/objectyaml/dxcontaineryaml-h">DXContainerYAML.h</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/structs/llvm/yaml/mappingtraits-24dae25eef0cf89bd251b2ce9cf3fa24/#a6808d9de67d634c84c6549cc53e365bb">llvm::yaml::MappingTraits&lt; DXContainerYAML::PSVInfo &gt;::mapping</a>.</p>

</div>
</div>

### SigPatchOrPrimElements {#a8ce8a80cc6b5b21dc6b8961af4f033fe}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">SmallVector&lt;SignatureElement&gt; llvm::DXContainerYAML::PSVInfo::SigPatchOrPrimElements</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 116 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/objectyaml/dxcontaineryaml-h">DXContainerYAML.h</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/structs/llvm/yaml/mappingtraits-24dae25eef0cf89bd251b2ce9cf3fa24/#a6808d9de67d634c84c6549cc53e365bb">llvm::yaml::MappingTraits&lt; DXContainerYAML::PSVInfo &gt;::mapping</a>.</p>

</div>
</div>

### Version {#a324c4bf6a0fd537c2738464a8ed2e0d1}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">uint32_t llvm::DXContainerYAML::PSVInfo::Version</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 109 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/objectyaml/dxcontaineryaml-h">DXContainerYAML.h</a>.</p>


<p>Referenced by <a href="#aef40b4410af614b5a4771ef2dfc5df47">mapInfoForVersion</a>, <a href="/web-llvm/docs/api/structs/llvm/yaml/mappingtraits-24dae25eef0cf89bd251b2ce9cf3fa24/#a6808d9de67d634c84c6549cc53e365bb">llvm::yaml::MappingTraits&lt; DXContainerYAML::PSVInfo &gt;::mapping</a>, <a href="#a1b90da6546433d7d23cd840f04bf07c7">PSVInfo</a>, <a href="#a06695730ea4784857966d6149010b697">PSVInfo</a>, <a href="#aaef5807a887ccbf45d0a43790b7f06a2">PSVInfo</a>, <a href="#aa4bf7682cdfd87a9c6d850428d7a7c8b">PSVInfo</a> and <a href="#a594d619b949d38aa5d402e81a23ca13a">PSVInfo</a>.</p>

</div>
</div>

</div>

<hr/>

The documentation for this struct was generated from the following files:

<ul>
<li><a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/objectyaml/dxcontaineryaml-h">DXContainerYAML.h</a></li>
<li><a href="/web-llvm/docs/api/files/lib/lib/objectyaml/dxcontaineryaml-cpp">DXContainerYAML.cpp</a></li>
</ul>

<hr/>

<p class="doxyGeneratedBy">Generated via <a href="https://github.com/xpack/doxygen2docusaurus">doxygen2docusaurus</a> by <a href="https://www.doxygen.nl">Doxygen</a> 1.15.0.</p>

</div>
