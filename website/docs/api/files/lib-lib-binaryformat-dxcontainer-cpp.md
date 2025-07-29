---

# DO NOT EDIT!
# Automatically generated via doxygen2docusaurus by Doxygen.

slug: /api/files/lib/lib/binaryformat/dxcontainer-cpp
custom_edit_url: null
toc_max_heading_level: 4
keywords:
  - doxygen
  - reference
  - file

---

<div class="doxyPage">

# `DXContainer.cpp` File



## Included Headers

<div class="doxyIncludesList">#include "<a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/binaryformat/dxcontainer-h">llvm/BinaryFormat/DXContainer.h</a>"
#include "<a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/adt/stringswitch-h">llvm/ADT/StringSwitch.h</a>"
#include "<a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/support/scopedprinter-h">llvm/Support/ScopedPrinter.h</a>"
#include "llvm/BinaryFormat/DXContainerConstants.def"
</div>

## Variables Index

<table class="doxyMembersIndex">

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">static <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/structs/llvm/enumentry">EnumEntry</a>&lt; <a href="/web-llvm/docs/api/namespaces/llvm/dxbc/#a5ad6c5b17ba8ae365308ec3b0dfa6cc6">SigMinPrecision</a> &gt;</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a6eea59ac6d5b031ca12af9b5d346a07d">SigMinPrecisionNames</a>[] = ...</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">static <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/structs/llvm/enumentry">EnumEntry</a>&lt; <a href="/web-llvm/docs/api/namespaces/llvm/dxbc/#a10c892417ddf709bb72ac6c19c3146d1">D3DSystemValue</a> &gt;</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a43eec6a999aa62e234feb887739e5dc6">D3DSystemValueNames</a>[] = ...</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">static <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/structs/llvm/enumentry">EnumEntry</a>&lt; <a href="/web-llvm/docs/api/namespaces/llvm/dxbc/#a02c3a495a56bc9a255d05d912afe0173">SigComponentType</a> &gt;</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ae0ea533f0be31026649dc2fa2dcd95f8">SigComponentTypes</a>[] = ...</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">static <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/structs/llvm/enumentry">EnumEntry</a>&lt; <a href="/web-llvm/docs/api/namespaces/llvm/dxbc/psv/#a46bbed77958063a38334f15d2fb08e37">PSV::SemanticKind</a> &gt;</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#aae66a83732ec49891f49ee97f082864a">SemanticKindNames</a>[] = ...</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">static <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/structs/llvm/enumentry">EnumEntry</a>&lt; <a href="/web-llvm/docs/api/namespaces/llvm/dxbc/psv/#ade495cbb91531342f36210abc17526d9">PSV::ComponentType</a> &gt;</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#aecb7aa902d6268612163e25265be3a0b">ComponentTypeNames</a>[] = ...</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">static <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/structs/llvm/enumentry">EnumEntry</a>&lt; <a href="/web-llvm/docs/api/namespaces/llvm/dxbc/psv/#a920feca1650f1696430f077e1a3e8df3">PSV::InterpolationMode</a> &gt;</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a616f9b6ecf7ae71d2664f248ba1c2788">InterpolationModeNames</a>[] = ...</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">static <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/structs/llvm/enumentry">EnumEntry</a>&lt; <a href="/web-llvm/docs/api/namespaces/llvm/dxbc/psv/#a77b9940b9167ea2e78639b1e12892e3b">PSV::ResourceType</a> &gt;</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#aaf3de5b1fca4b86ad01fe5c879599f05">ResourceTypeNames</a>[] = ...</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">static <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/structs/llvm/enumentry">EnumEntry</a>&lt; <a href="/web-llvm/docs/api/namespaces/llvm/dxbc/psv/#ad06bfb30e934bd6584fa26c6bf71e428">PSV::ResourceKind</a> &gt;</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ad6d8bbaa7d94c565b9a7df9a6544c549">ResourceKindNames</a>[] = ...</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ac3741256cafc41c80f76e8483efbf42c">CONTAINER_PART</a>(PartName)&nbsp;&nbsp;&nbsp;.Case(#PartName, PartType::PartName)</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">#define</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a1472d640e3663f504eb0dd1942c75e96">COMPONENT_PRECISION</a>(Val, Enum)&nbsp;&nbsp;&nbsp;{#Enum, SigMinPrecision::Enum},</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">#define</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ab02b8cc53e6dae866c8dc53cec3eb842">D3D_SYSTEM_VALUE</a>(Val, Enum)&nbsp;&nbsp;&nbsp;{#Enum, D3DSystemValue::Enum},</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">#define</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a2926fcee379203750b39f717ea44c6ab">COMPONENT_TYPE</a>(Val, Enum)&nbsp;&nbsp;&nbsp;{#Enum, SigComponentType::Enum},</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">#define</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a07c8c454526f3b4e2eefe831c697dfb5">SEMANTIC_KIND</a>(Val, Enum)&nbsp;&nbsp;&nbsp;{#Enum, PSV::SemanticKind::Enum},</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">#define</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a6083d191fc8c280989006c281f745056">COMPONENT_TYPE</a>(Val, Enum)&nbsp;&nbsp;&nbsp;{#Enum, PSV::ComponentType::Enum},</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">#define</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a63c266040837365d7aa5ad7ab33c19bf">INTERPOLATION_MODE</a>(Val, Enum)&nbsp;&nbsp;&nbsp;{#Enum, PSV::InterpolationMode::Enum},</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">#define</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a68a33f3fe257763f50e0bf3620cf541e">RESOURCE_TYPE</a>(Val, Enum)&nbsp;&nbsp;&nbsp;{#Enum, PSV::ResourceType::Enum},</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">#define</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#aad5889b1a17ddd38509b06619b1a08d1">RESOURCE_KIND</a>(Val, Enum)&nbsp;&nbsp;&nbsp;{#Enum, PSV::ResourceKind::Enum},</td>
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

## Variables

### ComponentTypeNames {#aecb7aa902d6268612163e25265be3a0b}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">const EnumEntry&lt;PSV::ComponentType&gt; ComponentTypeNames[]</td>
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



<dl class="doxySectionUser">
<dt>Initialiser</dt>
<dd>
<div class="doxyVerbatim">= {
}
</div>
</dd>
</dl>

<p>Definition at line 75 of file <a href="/web-llvm/docs/api/files/lib/lib/binaryformat/dxcontainer-cpp">DXContainer.cpp</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/namespaces/llvm/dxbc/psv/#a9b14f3b10dc225a85db5ccff438c2825">llvm::dxbc::PSV::getComponentTypes</a>.</p>

</div>
</div>

### D3DSystemValueNames {#a43eec6a999aa62e234feb887739e5dc6}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">const EnumEntry&lt;D3DSystemValue&gt; D3DSystemValueNames[]</td>
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



<dl class="doxySectionUser">
<dt>Initialiser</dt>
<dd>
<div class="doxyVerbatim">= {
}
</div>
</dd>
</dl>

<p>Definition at line 45 of file <a href="/web-llvm/docs/api/files/lib/lib/binaryformat/dxcontainer-cpp">DXContainer.cpp</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/namespaces/llvm/dxbc/#ab2fa6db18397dbe15c5a9c5889ff9d2b">llvm::dxbc::getD3DSystemValues</a>.</p>

</div>
</div>

### InterpolationModeNames {#a616f9b6ecf7ae71d2664f248ba1c2788}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">const EnumEntry&lt;PSV::InterpolationMode&gt; InterpolationModeNames[]</td>
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



<dl class="doxySectionUser">
<dt>Initialiser</dt>
<dd>
<div class="doxyVerbatim">= {
}
</div>
</dd>
</dl>

<p>Definition at line 85 of file <a href="/web-llvm/docs/api/files/lib/lib/binaryformat/dxcontainer-cpp">DXContainer.cpp</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/namespaces/llvm/dxbc/psv/#afafac52d6273d1a8046928c43a2df1fa">llvm::dxbc::PSV::getInterpolationModes</a>.</p>

</div>
</div>

### ResourceKindNames {#ad6d8bbaa7d94c565b9a7df9a6544c549}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">const EnumEntry&lt;PSV::ResourceKind&gt; ResourceKindNames[]</td>
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



<dl class="doxySectionUser">
<dt>Initialiser</dt>
<dd>
<div class="doxyVerbatim">= {
}
</div>
</dd>
</dl>

<p>Definition at line 105 of file <a href="/web-llvm/docs/api/files/lib/lib/binaryformat/dxcontainer-cpp">DXContainer.cpp</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/namespaces/llvm/dxbc/psv/#a978c6a9fc7ef52fbb28b0d7084d31ee6">llvm::dxbc::PSV::getResourceKinds</a>.</p>

</div>
</div>

### ResourceTypeNames {#aaf3de5b1fca4b86ad01fe5c879599f05}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">const EnumEntry&lt;PSV::ResourceType&gt; ResourceTypeNames[]</td>
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



<dl class="doxySectionUser">
<dt>Initialiser</dt>
<dd>
<div class="doxyVerbatim">= {
}
</div>
</dd>
</dl>

<p>Definition at line 95 of file <a href="/web-llvm/docs/api/files/lib/lib/binaryformat/dxcontainer-cpp">DXContainer.cpp</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/namespaces/llvm/dxbc/psv/#ab139ec676c2a3cf64055286c14a5ac1f">llvm::dxbc::PSV::getResourceTypes</a>.</p>

</div>
</div>

### SemanticKindNames {#aae66a83732ec49891f49ee97f082864a}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">const EnumEntry&lt;PSV::SemanticKind&gt; SemanticKindNames[]</td>
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



<dl class="doxySectionUser">
<dt>Initialiser</dt>
<dd>
<div class="doxyVerbatim">= {
}
</div>
</dd>
</dl>

<p>Definition at line 65 of file <a href="/web-llvm/docs/api/files/lib/lib/binaryformat/dxcontainer-cpp">DXContainer.cpp</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/namespaces/llvm/dxbc/psv/#ad686566cee38b90498b8a61737a5870b">llvm::dxbc::PSV::getSemanticKinds</a>.</p>

</div>
</div>

### SigComponentTypes {#ae0ea533f0be31026649dc2fa2dcd95f8}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">const EnumEntry&lt;SigComponentType&gt; SigComponentTypes[]</td>
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



<dl class="doxySectionUser">
<dt>Initialiser</dt>
<dd>
<div class="doxyVerbatim">= {
}
</div>
</dd>
</dl>

<p>Definition at line 55 of file <a href="/web-llvm/docs/api/files/lib/lib/binaryformat/dxcontainer-cpp">DXContainer.cpp</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/namespaces/llvm/dxbc/#a5e15aa5ca2a33a12af0563a4c079decd">llvm::dxbc::getSigComponentTypes</a>.</p>

</div>
</div>

### SigMinPrecisionNames {#a6eea59ac6d5b031ca12af9b5d346a07d}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">const EnumEntry&lt;SigMinPrecision&gt; SigMinPrecisionNames[]</td>
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



<dl class="doxySectionUser">
<dt>Initialiser</dt>
<dd>
<div class="doxyVerbatim">= {
}
</div>
</dd>
</dl>

<p>Definition at line 35 of file <a href="/web-llvm/docs/api/files/lib/lib/binaryformat/dxcontainer-cpp">DXContainer.cpp</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/namespaces/llvm/dxbc/#a6c597b2e98df86b2917b964fdc5f09fe">llvm::dxbc::getSigMinPrecisions</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Macro Definitions

### COMPONENT\_PRECISION {#a1472d640e3663f504eb0dd1942c75e96}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">#define COMPONENT_PRECISION(Val, Enum)&nbsp;&nbsp;&nbsp;{#Enum, SigMinPrecision::Enum},</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 33 of file <a href="/web-llvm/docs/api/files/lib/lib/binaryformat/dxcontainer-cpp">DXContainer.cpp</a>.</p>

</div>
</div>

### COMPONENT\_TYPE {#a2926fcee379203750b39f717ea44c6ab}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">#define COMPONENT_TYPE(Val, Enum)&nbsp;&nbsp;&nbsp;{#Enum, SigComponentType::Enum},</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 53 of file <a href="/web-llvm/docs/api/files/lib/lib/binaryformat/dxcontainer-cpp">DXContainer.cpp</a>.</p>

</div>
</div>

### COMPONENT\_TYPE {#a6083d191fc8c280989006c281f745056}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">#define COMPONENT_TYPE(Val, Enum)&nbsp;&nbsp;&nbsp;{#Enum, PSV::ComponentType::Enum},</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 73 of file <a href="/web-llvm/docs/api/files/lib/lib/binaryformat/dxcontainer-cpp">DXContainer.cpp</a>.</p>

</div>
</div>

### CONTAINER\_PART {#ac3741256cafc41c80f76e8483efbf42c}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">#define CONTAINER_PART(PartName)&nbsp;&nbsp;&nbsp;.Case(#PartName, PartType::PartName)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 22 of file <a href="/web-llvm/docs/api/files/lib/lib/binaryformat/dxcontainer-cpp">DXContainer.cpp</a>.</p>

</div>
</div>

### D3D\_SYSTEM\_VALUE {#ab02b8cc53e6dae866c8dc53cec3eb842}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">#define D3D_SYSTEM_VALUE(Val, Enum)&nbsp;&nbsp;&nbsp;{#Enum, D3DSystemValue::Enum},</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 43 of file <a href="/web-llvm/docs/api/files/lib/lib/binaryformat/dxcontainer-cpp">DXContainer.cpp</a>.</p>

</div>
</div>

### INTERPOLATION\_MODE {#a63c266040837365d7aa5ad7ab33c19bf}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">#define INTERPOLATION_MODE(Val, Enum)&nbsp;&nbsp;&nbsp;{#Enum, PSV::InterpolationMode::Enum},</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 83 of file <a href="/web-llvm/docs/api/files/lib/lib/binaryformat/dxcontainer-cpp">DXContainer.cpp</a>.</p>

</div>
</div>

### RESOURCE\_KIND {#aad5889b1a17ddd38509b06619b1a08d1}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">#define RESOURCE_KIND(Val, Enum)&nbsp;&nbsp;&nbsp;{#Enum, PSV::ResourceKind::Enum},</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 103 of file <a href="/web-llvm/docs/api/files/lib/lib/binaryformat/dxcontainer-cpp">DXContainer.cpp</a>.</p>

</div>
</div>

### RESOURCE\_TYPE {#a68a33f3fe257763f50e0bf3620cf541e}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">#define RESOURCE_TYPE(Val, Enum)&nbsp;&nbsp;&nbsp;{#Enum, PSV::ResourceType::Enum},</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 93 of file <a href="/web-llvm/docs/api/files/lib/lib/binaryformat/dxcontainer-cpp">DXContainer.cpp</a>.</p>

</div>
</div>

### SEMANTIC\_KIND {#a07c8c454526f3b4e2eefe831c697dfb5}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">#define SEMANTIC_KIND(Val, Enum)&nbsp;&nbsp;&nbsp;{#Enum, PSV::SemanticKind::Enum},</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 63 of file <a href="/web-llvm/docs/api/files/lib/lib/binaryformat/dxcontainer-cpp">DXContainer.cpp</a>.</p>

</div>
</div>

</div>

<hr/>

<p class="doxyGeneratedBy">Generated via <a href="https://github.com/xpack/doxygen2docusaurus">doxygen2docusaurus</a> by <a href="https://www.doxygen.nl">Doxygen</a> 1.15.0.</p>

</div>
