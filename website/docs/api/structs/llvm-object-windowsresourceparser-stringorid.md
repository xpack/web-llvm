---

# DO NOT EDIT!
# Automatically generated via doxygen2docusaurus by Doxygen.

slug: /api/structs/llvm/object/windowsresourceparser/stringorid
custom_edit_url: null
toc_max_heading_level: 4
keywords:
  - doxygen
  - reference
  - struct

---

<div class="doxyPage">

# The `StringOrID` Struct Reference



## Declaration

<div class="doxyDeclaration">
struct llvm::object::WindowsResourceParser::StringOrID { ... }
</div>

## Included Headers

<div class="doxyIncludesList">#include "<a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/object/windowsresource-h">llvm/Object/WindowsResource.h</a>"
</div>

## Public Constructors Index

<table class="doxyMembersIndex">

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a24b0f0f84cf03ba44d5e11fb27e03c5a">StringOrID</a> (uint32_t ID)</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a5362183134493622cb2454a8b6d571d7">StringOrID</a> (ArrayRef&lt; UTF16 &gt; String)</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#af0d9970f3b2c6cc0b76c35d7f11aa69c">IsString</a></td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/arrayref">ArrayRef</a>&lt; <a href="/web-llvm/docs/api/namespaces/llvm/#a17701f48ffa18ce5f16797db84617db2">UTF16</a> &gt;</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ab20601f90323e3e2ad4a7bf40f2703c5">String</a></td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a3d2ea681e920074a997a6a44438cf32b">ID</a> = ~0u</td>
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


<p>Definition at line 234 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/object/windowsresource-h">WindowsResource.h</a>.</p>


<div class="doxySectionDef">

## Public Constructors

### StringOrID() {#a24b0f0f84cf03ba44d5e11fb27e03c5a}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">llvm::object::WindowsResourceParser::StringOrID::StringOrID (uint32_t ID)</td>
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



<p>Definition at line 239 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/object/windowsresource-h">WindowsResource.h</a>.</p>


<p>References <a href="#a3d2ea681e920074a997a6a44438cf32b">ID</a> and <a href="#af0d9970f3b2c6cc0b76c35d7f11aa69c">IsString</a>.</p>

</div>
</div>

### StringOrID() {#a5362183134493622cb2454a8b6d571d7}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">llvm::object::WindowsResourceParser::StringOrID::StringOrID (<a href="/web-llvm/docs/api/classes/llvm/arrayref">ArrayRef</a>&lt; <a href="/web-llvm/docs/api/namespaces/llvm/#a17701f48ffa18ce5f16797db84617db2">UTF16</a> &gt; String)</td>
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



<p>Definition at line 240 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/object/windowsresource-h">WindowsResource.h</a>.</p>


<p>References <a href="#af0d9970f3b2c6cc0b76c35d7f11aa69c">IsString</a>, <a href="#ab20601f90323e3e2ad4a7bf40f2703c5">String</a> and <a href="/web-llvm/docs/api/files/lib/lib/analysis/basicaliasanalysis-cpp/#af6d5cafbdfc5313e65d990120021a3ec">true</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Public Member Attributes

### ID {#a3d2ea681e920074a997a6a44438cf32b}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">uint32_t llvm::object::WindowsResourceParser::StringOrID::ID = ~0u</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 237 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/object/windowsresource-h">WindowsResource.h</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/namespaces/llvm/object/#a178b31645db53ed6a6c3da689960c16e">llvm::object::printStringOrID</a> and <a href="#a24b0f0f84cf03ba44d5e11fb27e03c5a">StringOrID</a>.</p>

</div>
</div>

### IsString {#af0d9970f3b2c6cc0b76c35d7f11aa69c}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool llvm::object::WindowsResourceParser::StringOrID::IsString</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 235 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/object/windowsresource-h">WindowsResource.h</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/namespaces/llvm/object/#a178b31645db53ed6a6c3da689960c16e">llvm::object::printStringOrID</a>, <a href="#a5362183134493622cb2454a8b6d571d7">StringOrID</a> and <a href="#a24b0f0f84cf03ba44d5e11fb27e03c5a">StringOrID</a>.</p>

</div>
</div>

### String {#ab20601f90323e3e2ad4a7bf40f2703c5}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">ArrayRef&lt;UTF16&gt; llvm::object::WindowsResourceParser::StringOrID::String</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 236 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/object/windowsresource-h">WindowsResource.h</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/namespaces/llvm/object/#a178b31645db53ed6a6c3da689960c16e">llvm::object::printStringOrID</a> and <a href="#a5362183134493622cb2454a8b6d571d7">StringOrID</a>.</p>

</div>
</div>

</div>

<hr/>

The documentation for this struct was generated from the following file:

<ul>
<li><a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/object/windowsresource-h">WindowsResource.h</a></li>
</ul>

<hr/>

<p class="doxyGeneratedBy">Generated via <a href="https://github.com/xpack/doxygen2docusaurus">doxygen2docusaurus</a> by <a href="https://www.doxygen.nl">Doxygen</a> 1.15.0.</p>

</div>
