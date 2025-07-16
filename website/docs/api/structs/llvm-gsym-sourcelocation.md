---

# DO NOT EDIT!
# Automatically generated via doxygen2docusaurus by Doxygen.

slug: /api/structs/llvm/gsym/sourcelocation
custom_edit_url: null
toc_max_heading_level: 4
keywords:
  - doxygen
  - reference
  - struct

---

<div class="doxyPage">

# The `SourceLocation` Struct Reference



## Declaration

<div class="doxyDeclaration">
struct llvm::gsym::SourceLocation { ... }
</div>

## Included Headers

<div class="doxyIncludesList">#include "<a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/debuginfo/include/llvm/debuginfo/gsym/lookupresult-h">llvm/DebugInfo/GSYM/LookupResult.h</a>"
</div>

## Public Member Attributes Index

<table class="doxyMembersIndex">

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/stringref">StringRef</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#acc0de9bcc407c170aff5069c335bb961">Name</a></td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p><a href="/web-llvm/docs/api/classes/llvm/function">Function</a> or symbol name. <a href="#acc0de9bcc407c170aff5069c335bb961">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/stringref">StringRef</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a9c40347d10af7c2cefe3d77e8487f4b7">Dir</a></td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Line entry source file directory path. <a href="#a9c40347d10af7c2cefe3d77e8487f4b7">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/stringref">StringRef</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a05bfc8d6292b7916993f0f2a32307c88">Base</a></td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Line entry source file basename. <a href="#a05bfc8d6292b7916993f0f2a32307c88">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">uint32_t</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a158cfb1f977ca6fa5202d0925b97197b">Line</a> = 0</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Source file line number. <a href="#a158cfb1f977ca6fa5202d0925b97197b">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">uint32_t</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a5ac9d3eb9c18ab3a8da5b084d034c158">Offset</a> = 0</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Byte size offset within the named function. <a href="#a5ac9d3eb9c18ab3a8da5b084d034c158">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

</table>


<p>Definition at line 21 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/debuginfo/include/llvm/debuginfo/gsym/lookupresult-h">LookupResult.h</a>.</p>


<div class="doxySectionDef">

## Public Member Attributes

### Base {#a05bfc8d6292b7916993f0f2a32307c88}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">StringRef llvm::gsym::SourceLocation::Base</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Line entry source file basename.</p>

<p>Definition at line 24 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/debuginfo/include/llvm/debuginfo/gsym/lookupresult-h">LookupResult.h</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/structs/llvm/gsym/functioninfo/#a5d896568c18192e090d13f4831e4abb1">llvm::gsym::FunctionInfo::lookup</a>, <a href="/web-llvm/docs/api/files/lib/lib/debuginfo/lib/debuginfo/gsym/inlineinfo-cpp/#a5db99f4b7f8744e0b1c8b50dba8ec5a2">lookup</a> and <a href="/web-llvm/docs/api/namespaces/llvm/gsym/#a0db487cbf8c154e299a79baa79fde1ca">llvm::gsym::operator&lt;&lt;</a>.</p>

</div>
</div>

### Dir {#a9c40347d10af7c2cefe3d77e8487f4b7}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">StringRef llvm::gsym::SourceLocation::Dir</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Line entry source file directory path.</p>

<p>Definition at line 23 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/debuginfo/include/llvm/debuginfo/gsym/lookupresult-h">LookupResult.h</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/structs/llvm/gsym/functioninfo/#a5d896568c18192e090d13f4831e4abb1">llvm::gsym::FunctionInfo::lookup</a>, <a href="/web-llvm/docs/api/files/lib/lib/debuginfo/lib/debuginfo/gsym/inlineinfo-cpp/#a5db99f4b7f8744e0b1c8b50dba8ec5a2">lookup</a> and <a href="/web-llvm/docs/api/namespaces/llvm/gsym/#a0db487cbf8c154e299a79baa79fde1ca">llvm::gsym::operator&lt;&lt;</a>.</p>

</div>
</div>

### Line {#a158cfb1f977ca6fa5202d0925b97197b}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">uint32_t llvm::gsym::SourceLocation::Line = 0</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Source file line number.</p>

<p>Definition at line 25 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/debuginfo/include/llvm/debuginfo/gsym/lookupresult-h">LookupResult.h</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/structs/llvm/gsym/functioninfo/#a5d896568c18192e090d13f4831e4abb1">llvm::gsym::FunctionInfo::lookup</a>, <a href="/web-llvm/docs/api/files/lib/lib/debuginfo/lib/debuginfo/gsym/inlineinfo-cpp/#a5db99f4b7f8744e0b1c8b50dba8ec5a2">lookup</a> and <a href="/web-llvm/docs/api/namespaces/llvm/gsym/#a0db487cbf8c154e299a79baa79fde1ca">llvm::gsym::operator&lt;&lt;</a>.</p>

</div>
</div>

### Name {#acc0de9bcc407c170aff5069c335bb961}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">StringRef llvm::gsym::SourceLocation::Name</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p><a href="/web-llvm/docs/api/classes/llvm/function">Function</a> or symbol name.</p>

<p>Definition at line 22 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/debuginfo/include/llvm/debuginfo/gsym/lookupresult-h">LookupResult.h</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/structs/llvm/gsym/functioninfo/#a5d896568c18192e090d13f4831e4abb1">llvm::gsym::FunctionInfo::lookup</a>, <a href="/web-llvm/docs/api/files/lib/lib/debuginfo/lib/debuginfo/gsym/inlineinfo-cpp/#a5db99f4b7f8744e0b1c8b50dba8ec5a2">lookup</a> and <a href="/web-llvm/docs/api/namespaces/llvm/gsym/#a0db487cbf8c154e299a79baa79fde1ca">llvm::gsym::operator&lt;&lt;</a>.</p>

</div>
</div>

### Offset {#a5ac9d3eb9c18ab3a8da5b084d034c158}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">uint32_t llvm::gsym::SourceLocation::Offset = 0</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Byte size offset within the named function.</p>

<p>Definition at line 26 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/debuginfo/include/llvm/debuginfo/gsym/lookupresult-h">LookupResult.h</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/structs/llvm/gsym/functioninfo/#a5d896568c18192e090d13f4831e4abb1">llvm::gsym::FunctionInfo::lookup</a>, <a href="/web-llvm/docs/api/files/lib/lib/debuginfo/lib/debuginfo/gsym/inlineinfo-cpp/#a5db99f4b7f8744e0b1c8b50dba8ec5a2">lookup</a> and <a href="/web-llvm/docs/api/namespaces/llvm/gsym/#a0db487cbf8c154e299a79baa79fde1ca">llvm::gsym::operator&lt;&lt;</a>.</p>

</div>
</div>

</div>

<hr/>

The documentation for this struct was generated from the following file:

<ul>
<li><a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/debuginfo/include/llvm/debuginfo/gsym/lookupresult-h">LookupResult.h</a></li>
</ul>

<hr/>

<p class="doxyGeneratedBy">Generated via <a href="https://github.com/xpack/doxygen2docusaurus">doxygen2docusaurus</a> by <a href="https://www.doxygen.nl">Doxygen</a> 1.15.0.</p>

</div>
