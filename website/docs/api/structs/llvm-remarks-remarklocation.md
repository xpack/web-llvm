---

# DO NOT EDIT!
# Automatically generated via doxygen2docusaurus by Doxygen.

slug: /api/structs/llvm/remarks/remarklocation
custom_edit_url: null
toc_max_heading_level: 4
keywords:
  - doxygen
  - reference
  - struct

---

<div class="doxyPage">

# The `RemarkLocation` Struct Reference

<p>The debug location used to track a remark back to the source file. <a href="#details">More...</a></p>

## Declaration

<div class="doxyDeclaration">
struct llvm::remarks::RemarkLocation { ... }
</div>

## Included Headers

<div class="doxyIncludesList">#include "<a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/remarks/remark-h">llvm/Remarks/Remark.h</a>"
</div>

## Public Member Functions Index

<table class="doxyMembersIndex">

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">void</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a2c5be9f89a9dbd6c4049c480037b73ad">print</a> (raw_ostream &amp;OS) const</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Implement operator&lt;&lt; on <a href="/web-llvm/docs/api/structs/llvm/remarks/remarklocation">RemarkLocation</a>. <a href="#a2c5be9f89a9dbd6c4049c480037b73ad">More...</a></p>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a82090d22eac34da799b82a80c87de556">SourceFilePath</a></td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Absolute path of the source file corresponding to this remark. <a href="#a82090d22eac34da799b82a80c87de556">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">unsigned</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#aaa163f0ef608440c669200d510c91835">SourceLine</a> = 0</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">unsigned</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a6345368f6dd5385fc38fefb2da62b043">SourceColumn</a> = 0</td>
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

## Description {#details}

<p>The debug location used to track a remark back to the source file.</p>

<p>Definition at line 31 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/remarks/remark-h">Remark.h</a>.</p>


<div class="doxySectionDef">

## Public Member Functions

### print() {#a2c5be9f89a9dbd6c4049c480037b73ad}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void RemarkLocation::print (<a href="/web-llvm/docs/api/classes/llvm/raw-ostream">raw_ostream</a> &amp; OS)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Implement operator&lt;&lt; on <a href="/web-llvm/docs/api/structs/llvm/remarks/remarklocation">RemarkLocation</a>.</p>

<p>Declaration at line 38 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/remarks/remark-h">Remark.h</a>, definition at line 39 of file <a href="/web-llvm/docs/api/files/lib/lib/remarks/remark-cpp">Remark.cpp</a>.</p>


<p>References <a href="#a6345368f6dd5385fc38fefb2da62b043">SourceColumn</a>, <a href="#a82090d22eac34da799b82a80c87de556">SourceFilePath</a> and <a href="#aaa163f0ef608440c669200d510c91835">SourceLine</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/namespaces/llvm/remarks/#a12cdc4c9444eeac178784c5de3b006d7">llvm::remarks::operator&lt;&lt;</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Public Member Attributes

### SourceColumn {#a6345368f6dd5385fc38fefb2da62b043}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">unsigned llvm::remarks::RemarkLocation::SourceColumn = 0</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 35 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/remarks/remark-h">Remark.h</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/structs/llvm/yaml/mappingtraits-e04ef8402fe6e5256544f3aa0cee17c3/#a92a38bb7828b1553781c36e6a8b2bda2">llvm::yaml::MappingTraits&lt; RemarkLocation &gt;::mapping</a> and <a href="#a2c5be9f89a9dbd6c4049c480037b73ad">print</a>.</p>

</div>
</div>

### SourceFilePath {#a82090d22eac34da799b82a80c87de556}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">StringRef llvm::remarks::RemarkLocation::SourceFilePath</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Absolute path of the source file corresponding to this remark.</p>

<p>Definition at line 33 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/remarks/remark-h">Remark.h</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/structs/llvm/yaml/mappingtraits-e04ef8402fe6e5256544f3aa0cee17c3/#a92a38bb7828b1553781c36e6a8b2bda2">llvm::yaml::MappingTraits&lt; RemarkLocation &gt;::mapping</a> and <a href="#a2c5be9f89a9dbd6c4049c480037b73ad">print</a>.</p>

</div>
</div>

### SourceLine {#aaa163f0ef608440c669200d510c91835}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">unsigned llvm::remarks::RemarkLocation::SourceLine = 0</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 34 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/remarks/remark-h">Remark.h</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/structs/llvm/yaml/mappingtraits-e04ef8402fe6e5256544f3aa0cee17c3/#a92a38bb7828b1553781c36e6a8b2bda2">llvm::yaml::MappingTraits&lt; RemarkLocation &gt;::mapping</a> and <a href="#a2c5be9f89a9dbd6c4049c480037b73ad">print</a>.</p>

</div>
</div>

</div>

<hr/>

The documentation for this struct was generated from the following files:

<ul>
<li><a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/remarks/remark-h">Remark.h</a></li>
<li><a href="/web-llvm/docs/api/files/lib/lib/remarks/remark-cpp">Remark.cpp</a></li>
</ul>

<hr/>

<p class="doxyGeneratedBy">Generated via <a href="https://github.com/xpack/doxygen2docusaurus">doxygen2docusaurus</a> by <a href="https://www.doxygen.nl">Doxygen</a> 1.15.0.</p>

</div>
