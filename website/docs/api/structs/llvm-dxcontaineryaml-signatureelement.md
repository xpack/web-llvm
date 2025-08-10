---

# DO NOT EDIT!
# Automatically generated via doxygen2docusaurus by Doxygen.

slug: /api/structs/llvm/dxcontaineryaml/signatureelement
custom_edit_url: null
toc_max_heading_level: 4
keywords:
  - doxygen
  - reference
  - struct

---

<div class="doxyPage">

# `SignatureElement` Struct



## Declaration

<div class="doxyDeclaration">
struct llvm::DXContainerYAML::SignatureElement { ... }
</div>

## Included Headers

<div class="doxyIncludesList">#include "<a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/objectyaml/dxcontaineryaml-h">llvm/ObjectYAML/DXContainerYAML.h</a>"
</div>

## Public Constructors Index

<table class="doxyMembersIndex">

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#af81871cd74bb7e359b3312a129673ca1">SignatureElement</a> ()=default</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a2d451930ceb53ca2af1b18101cffd06a">SignatureElement</a> (dxbc::PSV::v0::SignatureElement El, StringRef StringTable, ArrayRef&lt; uint32_t &gt; IdxTable)</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/stringref">StringRef</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a0de7d967111d174e1563aaedd8cbfec9">Name</a></td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#aab5d23890b2caac17f9ce5a87cf2d54d">Indices</a></td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">uint8_t</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a5337badac8ebaa2fc485a3f4c63848d7">StartRow</a></td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">uint8_t</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ad26405454d7b92f2337344f80fe4e4ba">Cols</a></td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">uint8_t</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a98063aa2c9df6649cfe115a3a8491473">StartCol</a></td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">bool</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a8c54bf11b10edaafd8abc0aef79efa96">Allocated</a></td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/namespaces/llvm/dxbc/psv/#a46bbed77958063a38334f15d2fb08e37">dxbc::PSV::SemanticKind</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a6f250f6b11333fc12f57478f4bcc198b">Kind</a></td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/namespaces/llvm/dxbc/psv/#ade495cbb91531342f36210abc17526d9">dxbc::PSV::ComponentType</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a3284364ae66434228d843a0194958585">Type</a></td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/namespaces/llvm/dxbc/psv/#a920feca1650f1696430f077e1a3e8df3">dxbc::PSV::InterpolationMode</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a493a5f1203d62e0d02b479ef1144c2ae">Mode</a></td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">llvm::yaml::Hex8</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a4dd77effaa70c6437654d3352fce5aa1">DynamicMask</a></td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">uint8_t</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#aad343cbdf78c14cac97e3ef993e66868">Stream</a></td>
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


<p>Definition at line 78 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/objectyaml/dxcontaineryaml-h">DXContainerYAML.h</a>.</p>


<div class="doxySectionDef">

## Public Constructors

### SignatureElement() {#af81871cd74bb7e359b3312a129673ca1}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">llvm::DXContainerYAML::SignatureElement::SignatureElement ()</td>
</tr>
</table>
</td>
<td class="doxyMemberLabelsRight">
<span class="doxyMemberLabels">
<span class="doxyMemberLabel default">default</span>
</span>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 79 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/objectyaml/dxcontaineryaml-h">DXContainerYAML.h</a>.</p>

</div>
</div>

### SignatureElement() {#a2d451930ceb53ca2af1b18101cffd06a}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">llvm::DXContainerYAML::SignatureElement::SignatureElement (<a href="/web-llvm/docs/api/structs/llvm/dxbc/psv/v0/signatureelement">dxbc::PSV::v0::SignatureElement</a> El, <a href="/web-llvm/docs/api/classes/llvm/stringref">StringRef</a> StringTable, <a href="/web-llvm/docs/api/classes/llvm/arrayref">ArrayRef</a>&lt; uint32_t &gt; IdxTable)</td>
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



<p>Definition at line 81 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/objectyaml/dxcontaineryaml-h">DXContainerYAML.h</a>.</p>


<p>References <a href="#a8c54bf11b10edaafd8abc0aef79efa96">Allocated</a>, <a href="#ad26405454d7b92f2337344f80fe4e4ba">Cols</a>, <a href="#a4dd77effaa70c6437654d3352fce5aa1">DynamicMask</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a086e9fbdb06276db7753101a08a63adf">llvm::find</a>, <a href="#aab5d23890b2caac17f9ce5a87cf2d54d">Indices</a>, <a href="#a6f250f6b11333fc12f57478f4bcc198b">Kind</a>, <a href="#a493a5f1203d62e0d02b479ef1144c2ae">Mode</a>, <a href="#a0de7d967111d174e1563aaedd8cbfec9">Name</a>, <a href="#a98063aa2c9df6649cfe115a3a8491473">StartCol</a>, <a href="#a5337badac8ebaa2fc485a3f4c63848d7">StartRow</a>, <a href="#aad343cbdf78c14cac97e3ef993e66868">Stream</a>, <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/utils/simplifylibcalls-cpp/#ab845621311caa169682acb9c65516ae1">substr</a> and <a href="#a3284364ae66434228d843a0194958585">Type</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Public Member Attributes

### Allocated {#a8c54bf11b10edaafd8abc0aef79efa96}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool llvm::DXContainerYAML::SignatureElement::Allocated</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 96 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/objectyaml/dxcontaineryaml-h">DXContainerYAML.h</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/structs/llvm/yaml/mappingtraits-5846170c20e5db658888cb79e6c9ffc2/#a1b133a0cc7119db93698f71fd2a576d9">llvm::yaml::MappingTraits&lt; DXContainerYAML::SignatureElement &gt;::mapping</a> and <a href="#a2d451930ceb53ca2af1b18101cffd06a">SignatureElement</a>.</p>

</div>
</div>

### Cols {#ad26405454d7b92f2337344f80fe4e4ba}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">uint8_t llvm::DXContainerYAML::SignatureElement::Cols</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 94 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/objectyaml/dxcontaineryaml-h">DXContainerYAML.h</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/structs/llvm/yaml/mappingtraits-5846170c20e5db658888cb79e6c9ffc2/#a1b133a0cc7119db93698f71fd2a576d9">llvm::yaml::MappingTraits&lt; DXContainerYAML::SignatureElement &gt;::mapping</a> and <a href="#a2d451930ceb53ca2af1b18101cffd06a">SignatureElement</a>.</p>

</div>
</div>

### DynamicMask {#a4dd77effaa70c6437654d3352fce5aa1}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">llvm::yaml::Hex8 llvm::DXContainerYAML::SignatureElement::DynamicMask</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 101 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/objectyaml/dxcontaineryaml-h">DXContainerYAML.h</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/structs/llvm/yaml/mappingtraits-5846170c20e5db658888cb79e6c9ffc2/#a1b133a0cc7119db93698f71fd2a576d9">llvm::yaml::MappingTraits&lt; DXContainerYAML::SignatureElement &gt;::mapping</a> and <a href="#a2d451930ceb53ca2af1b18101cffd06a">SignatureElement</a>.</p>

</div>
</div>

### Indices {#aab5d23890b2caac17f9ce5a87cf2d54d}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">SmallVector&lt;uint32_t&gt; llvm::DXContainerYAML::SignatureElement::Indices</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 91 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/objectyaml/dxcontaineryaml-h">DXContainerYAML.h</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/structs/llvm/yaml/mappingtraits-5846170c20e5db658888cb79e6c9ffc2/#a1b133a0cc7119db93698f71fd2a576d9">llvm::yaml::MappingTraits&lt; DXContainerYAML::SignatureElement &gt;::mapping</a> and <a href="#a2d451930ceb53ca2af1b18101cffd06a">SignatureElement</a>.</p>

</div>
</div>

### Kind {#a6f250f6b11333fc12f57478f4bcc198b}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">dxbc::PSV::SemanticKind llvm::DXContainerYAML::SignatureElement::Kind</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 97 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/objectyaml/dxcontaineryaml-h">DXContainerYAML.h</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/structs/llvm/yaml/mappingtraits-5846170c20e5db658888cb79e6c9ffc2/#a1b133a0cc7119db93698f71fd2a576d9">llvm::yaml::MappingTraits&lt; DXContainerYAML::SignatureElement &gt;::mapping</a> and <a href="#a2d451930ceb53ca2af1b18101cffd06a">SignatureElement</a>.</p>

</div>
</div>

### Mode {#a493a5f1203d62e0d02b479ef1144c2ae}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">dxbc::PSV::InterpolationMode llvm::DXContainerYAML::SignatureElement::Mode</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 100 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/objectyaml/dxcontaineryaml-h">DXContainerYAML.h</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/structs/llvm/yaml/mappingtraits-5846170c20e5db658888cb79e6c9ffc2/#a1b133a0cc7119db93698f71fd2a576d9">llvm::yaml::MappingTraits&lt; DXContainerYAML::SignatureElement &gt;::mapping</a> and <a href="#a2d451930ceb53ca2af1b18101cffd06a">SignatureElement</a>.</p>

</div>
</div>

### Name {#a0de7d967111d174e1563aaedd8cbfec9}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">StringRef llvm::DXContainerYAML::SignatureElement::Name</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 90 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/objectyaml/dxcontaineryaml-h">DXContainerYAML.h</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/structs/llvm/yaml/mappingtraits-5846170c20e5db658888cb79e6c9ffc2/#a1b133a0cc7119db93698f71fd2a576d9">llvm::yaml::MappingTraits&lt; DXContainerYAML::SignatureElement &gt;::mapping</a> and <a href="#a2d451930ceb53ca2af1b18101cffd06a">SignatureElement</a>.</p>

</div>
</div>

### StartCol {#a98063aa2c9df6649cfe115a3a8491473}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">uint8_t llvm::DXContainerYAML::SignatureElement::StartCol</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 95 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/objectyaml/dxcontaineryaml-h">DXContainerYAML.h</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/structs/llvm/yaml/mappingtraits-5846170c20e5db658888cb79e6c9ffc2/#a1b133a0cc7119db93698f71fd2a576d9">llvm::yaml::MappingTraits&lt; DXContainerYAML::SignatureElement &gt;::mapping</a> and <a href="#a2d451930ceb53ca2af1b18101cffd06a">SignatureElement</a>.</p>

</div>
</div>

### StartRow {#a5337badac8ebaa2fc485a3f4c63848d7}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">uint8_t llvm::DXContainerYAML::SignatureElement::StartRow</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 93 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/objectyaml/dxcontaineryaml-h">DXContainerYAML.h</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/structs/llvm/yaml/mappingtraits-5846170c20e5db658888cb79e6c9ffc2/#a1b133a0cc7119db93698f71fd2a576d9">llvm::yaml::MappingTraits&lt; DXContainerYAML::SignatureElement &gt;::mapping</a> and <a href="#a2d451930ceb53ca2af1b18101cffd06a">SignatureElement</a>.</p>

</div>
</div>

### Stream {#aad343cbdf78c14cac97e3ef993e66868}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">uint8_t llvm::DXContainerYAML::SignatureElement::Stream</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 102 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/objectyaml/dxcontaineryaml-h">DXContainerYAML.h</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/structs/llvm/yaml/mappingtraits-5846170c20e5db658888cb79e6c9ffc2/#a1b133a0cc7119db93698f71fd2a576d9">llvm::yaml::MappingTraits&lt; DXContainerYAML::SignatureElement &gt;::mapping</a> and <a href="#a2d451930ceb53ca2af1b18101cffd06a">SignatureElement</a>.</p>

</div>
</div>

### Type {#a3284364ae66434228d843a0194958585}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">dxbc::PSV::ComponentType llvm::DXContainerYAML::SignatureElement::Type</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 99 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/objectyaml/dxcontaineryaml-h">DXContainerYAML.h</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/structs/llvm/yaml/mappingtraits-5846170c20e5db658888cb79e6c9ffc2/#a1b133a0cc7119db93698f71fd2a576d9">llvm::yaml::MappingTraits&lt; DXContainerYAML::SignatureElement &gt;::mapping</a> and <a href="#a2d451930ceb53ca2af1b18101cffd06a">SignatureElement</a>.</p>

</div>
</div>

</div>

<hr/>

The documentation for this struct was generated from the following file:

<ul>
<li><a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/objectyaml/dxcontaineryaml-h">DXContainerYAML.h</a></li>
</ul>

<hr/>

<p class="doxyGeneratedBy">Generated via <a href="https://xpack.github.io/doxygen2docusaurus">doxygen2docusaurus</a> 2.0.0 by <a href="https://www.doxygen.nl">Doxygen</a> 1.15.0.</p>

</div>
