---

# DO NOT EDIT!
# Automatically generated via doxygen2docusaurus by Doxygen.

slug: /api/structs/anonymous-machoplatform-cpp-/objcimageinfoflags
custom_edit_url: null
toc_max_heading_level: 4
keywords:
  - doxygen
  - reference
  - struct

---

<div class="doxyPage">

# `ObjCImageInfoFlags` Struct



## Declaration

<div class="doxyDeclaration">
struct anonymous{MachOPlatform.cpp}::ObjCImageInfoFlags { ... }
</div>

## Public Constructors Index

<table class="doxyMembersIndex">

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a00cd2c3a93a0191a78b9623a4fedb4c1">ObjCImageInfoFlags</a> (uint32_t RawFlags)</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">uint32_t</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a0301263ca0e34778ef6c3c249b7f2177">rawFlags</a> () const</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">uint16_t</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a720b83ab13a5d39630fefdee7339a2bf">SwiftABIVersion</a></td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">uint16_t</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#af6f923ac9776bf4cfdbce0c788e7c7bd">SwiftVersion</a></td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a270679b4d853257a011d98c02f4c0791">HasCategoryClassProperties</a></td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a131e77af6181ce525adab8427271c9c2">HasSignedObjCClassROs</a></td>
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

## Public Static Attributes Index

<table class="doxyMembersIndex">

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">static constexpr uint32_t</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a92acb6428b268412646b3fe29f62bc2a">SIGNED_CLASS_RO</a> = (1 &lt;&lt; 4)</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">static constexpr uint32_t</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a5a51d3dcb25a690b5e49c1c12898a1b4">HAS_CATEGORY_CLASS_PROPERTIES</a> = (1 &lt;&lt; 6)</td>
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


<p>Definition at line 214 of file <a href="/web-llvm/docs/api/files/lib/lib/executionengine/lib/executionengine/orc/machoplatform-cpp">MachOPlatform.cpp</a>.</p>


<div class="doxySectionDef">

## Public Constructors

### ObjCImageInfoFlags() {#a00cd2c3a93a0191a78b9623a4fedb4c1}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">anonymous{MachOPlatform.cpp}::ObjCImageInfoFlags::ObjCImageInfoFlags (uint32_t RawFlags)</td>
</tr>
</table>
</td>
<td class="doxyMemberLabelsRight">
<span class="doxyMemberLabels">
<span class="doxyMemberLabel inline">inline</span>
<span class="doxyMemberLabel explicit">explicit</span>
</span>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 223 of file <a href="/web-llvm/docs/api/files/lib/lib/executionengine/lib/executionengine/orc/machoplatform-cpp">MachOPlatform.cpp</a>.</p>


<p>References <a href="#a5a51d3dcb25a690b5e49c1c12898a1b4">HAS_CATEGORY_CLASS_PROPERTIES</a>, <a href="#a270679b4d853257a011d98c02f4c0791">HasCategoryClassProperties</a>, <a href="#a131e77af6181ce525adab8427271c9c2">HasSignedObjCClassROs</a>, <a href="#a92acb6428b268412646b3fe29f62bc2a">SIGNED_CLASS_RO</a>, <a href="#a720b83ab13a5d39630fefdee7339a2bf">SwiftABIVersion</a> and <a href="#af6f923ac9776bf4cfdbce0c788e7c7bd">SwiftVersion</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Public Member Functions

### rawFlags() {#a0301263ca0e34778ef6c3c249b7f2177}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">uint32_t anonymous{MachOPlatform.cpp}::ObjCImageInfoFlags::rawFlags ()</td>
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



<p>Definition at line 230 of file <a href="/web-llvm/docs/api/files/lib/lib/executionengine/lib/executionengine/orc/machoplatform-cpp">MachOPlatform.cpp</a>.</p>


<p>References <a href="#a5a51d3dcb25a690b5e49c1c12898a1b4">HAS_CATEGORY_CLASS_PROPERTIES</a>, <a href="#a270679b4d853257a011d98c02f4c0791">HasCategoryClassProperties</a>, <a href="#a131e77af6181ce525adab8427271c9c2">HasSignedObjCClassROs</a>, <a href="/web-llvm/docs/api/namespaces/llvm/orc/#a1448b52253eb43f8f07b7f5d94336a47a8eea62084ca7e541d918e823422bd82e">llvm::orc::Result</a>, <a href="#a92acb6428b268412646b3fe29f62bc2a">SIGNED_CLASS_RO</a>, <a href="#a720b83ab13a5d39630fefdee7339a2bf">SwiftABIVersion</a> and <a href="#af6f923ac9776bf4cfdbce0c788e7c7bd">SwiftVersion</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Public Member Attributes

### HasCategoryClassProperties {#a270679b4d853257a011d98c02f4c0791}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool anonymous{MachOPlatform.cpp}::ObjCImageInfoFlags::HasCategoryClassProperties</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 217 of file <a href="/web-llvm/docs/api/files/lib/lib/executionengine/lib/executionengine/orc/machoplatform-cpp">MachOPlatform.cpp</a>.</p>


<p>Referenced by <a href="#a00cd2c3a93a0191a78b9623a4fedb4c1">ObjCImageInfoFlags</a> and <a href="#a0301263ca0e34778ef6c3c249b7f2177">rawFlags</a>.</p>

</div>
</div>

### HasSignedObjCClassROs {#a131e77af6181ce525adab8427271c9c2}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool anonymous{MachOPlatform.cpp}::ObjCImageInfoFlags::HasSignedObjCClassROs</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 218 of file <a href="/web-llvm/docs/api/files/lib/lib/executionengine/lib/executionengine/orc/machoplatform-cpp">MachOPlatform.cpp</a>.</p>


<p>Referenced by <a href="#a00cd2c3a93a0191a78b9623a4fedb4c1">ObjCImageInfoFlags</a> and <a href="#a0301263ca0e34778ef6c3c249b7f2177">rawFlags</a>.</p>

</div>
</div>

### SwiftABIVersion {#a720b83ab13a5d39630fefdee7339a2bf}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">uint16_t anonymous{MachOPlatform.cpp}::ObjCImageInfoFlags::SwiftABIVersion</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 215 of file <a href="/web-llvm/docs/api/files/lib/lib/executionengine/lib/executionengine/orc/machoplatform-cpp">MachOPlatform.cpp</a>.</p>


<p>Referenced by <a href="#a00cd2c3a93a0191a78b9623a4fedb4c1">ObjCImageInfoFlags</a> and <a href="#a0301263ca0e34778ef6c3c249b7f2177">rawFlags</a>.</p>

</div>
</div>

### SwiftVersion {#af6f923ac9776bf4cfdbce0c788e7c7bd}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">uint16_t anonymous{MachOPlatform.cpp}::ObjCImageInfoFlags::SwiftVersion</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 216 of file <a href="/web-llvm/docs/api/files/lib/lib/executionengine/lib/executionengine/orc/machoplatform-cpp">MachOPlatform.cpp</a>.</p>


<p>Referenced by <a href="#a00cd2c3a93a0191a78b9623a4fedb4c1">ObjCImageInfoFlags</a> and <a href="#a0301263ca0e34778ef6c3c249b7f2177">rawFlags</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Public Static Attributes

### HAS\_CATEGORY\_CLASS\_PROPERTIES {#a5a51d3dcb25a690b5e49c1c12898a1b4}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">uint32_t anonymous{MachOPlatform.cpp}::ObjCImageInfoFlags::HAS_CATEGORY_CLASS_PROPERTIES = (1 &lt;&lt; 6)</td>
</tr>
</table>
</td>
<td class="doxyMemberLabelsRight">
<span class="doxyMemberLabels">
<span class="doxyMemberLabel constexpr">constexpr</span>
<span class="doxyMemberLabel static">static</span>
</span>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 221 of file <a href="/web-llvm/docs/api/files/lib/lib/executionengine/lib/executionengine/orc/machoplatform-cpp">MachOPlatform.cpp</a>.</p>


<p>Referenced by <a href="#a00cd2c3a93a0191a78b9623a4fedb4c1">ObjCImageInfoFlags</a> and <a href="#a0301263ca0e34778ef6c3c249b7f2177">rawFlags</a>.</p>

</div>
</div>

### SIGNED\_CLASS\_RO {#a92acb6428b268412646b3fe29f62bc2a}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">uint32_t anonymous{MachOPlatform.cpp}::ObjCImageInfoFlags::SIGNED_CLASS_RO = (1 &lt;&lt; 4)</td>
</tr>
</table>
</td>
<td class="doxyMemberLabelsRight">
<span class="doxyMemberLabels">
<span class="doxyMemberLabel constexpr">constexpr</span>
<span class="doxyMemberLabel static">static</span>
</span>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 220 of file <a href="/web-llvm/docs/api/files/lib/lib/executionengine/lib/executionengine/orc/machoplatform-cpp">MachOPlatform.cpp</a>.</p>


<p>Referenced by <a href="#a00cd2c3a93a0191a78b9623a4fedb4c1">ObjCImageInfoFlags</a> and <a href="#a0301263ca0e34778ef6c3c249b7f2177">rawFlags</a>.</p>

</div>
</div>

</div>

<hr/>

The documentation for this struct was generated from the following file:

<ul>
<li><a href="/web-llvm/docs/api/files/lib/lib/executionengine/lib/executionengine/orc/machoplatform-cpp">MachOPlatform.cpp</a></li>
</ul>

<hr/>

<p class="doxyGeneratedBy">Generated via <a href="https://xpack.github.io/doxygen2docusaurus">doxygen2docusaurus</a> 2.0.0 by <a href="https://www.doxygen.nl">Doxygen</a> 1.15.0.</p>

</div>
