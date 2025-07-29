---

# DO NOT EDIT!
# Automatically generated via doxygen2docusaurus by Doxygen.

slug: /api/files/lib/lib/debuginfo/lib/debuginfo/gsym/functioninfo-cpp
custom_edit_url: null
toc_max_heading_level: 4
keywords:
  - doxygen
  - reference
  - file

---

<div class="doxyPage">

# `FunctionInfo.cpp` File



## Included Headers

<div class="doxyIncludesList">#include "<a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/debuginfo/include/llvm/debuginfo/gsym/functioninfo-h">llvm/DebugInfo/GSYM/FunctionInfo.h</a>"
#include "<a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/debuginfo/include/llvm/debuginfo/gsym/filewriter-h">llvm/DebugInfo/GSYM/FileWriter.h</a>"
#include "<a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/debuginfo/include/llvm/debuginfo/gsym/gsymreader-h">llvm/DebugInfo/GSYM/GsymReader.h</a>"
#include "<a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/debuginfo/include/llvm/debuginfo/gsym/linetable-h">llvm/DebugInfo/GSYM/LineTable.h</a>"
#include "<a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/debuginfo/include/llvm/debuginfo/gsym/inlineinfo-h">llvm/DebugInfo/GSYM/InlineInfo.h</a>"
#include "<a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/support/dataextractor-h">llvm/Support/DataExtractor.h</a>"
#include &lt;optional&gt;
</div>

## Enumerations Index

<table class="doxyMembersIndex">

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">enum</td>
<td class="doxyMemberIndexItemName" align="left" valign="top">InfoType : uint32_t { <a href="#a3e1eb307ada3e1ef3a115f4c734aa5ee">...</a> }</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p><a href="/web-llvm/docs/api/structs/llvm/gsym/functioninfo">FunctionInfo</a> information type that is used to encode the optional data that is associated with a <a href="/web-llvm/docs/api/structs/llvm/gsym/functioninfo">FunctionInfo</a> object. <a href="#a3e1eb307ada3e1ef3a115f4c734aa5ee">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

</table>


<div class="doxySectionDef">

## Enumerations

### InfoType {#a3e1eb307ada3e1ef3a115f4c734aa5ee}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">enum InfoType : uint32_t</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p><a href="/web-llvm/docs/api/structs/llvm/gsym/functioninfo">FunctionInfo</a> information type that is used to encode the optional data that is associated with a <a href="/web-llvm/docs/api/structs/llvm/gsym/functioninfo">FunctionInfo</a> object.</p>

<dl class="doxyEnumList">
<dt class="doxyEnumTableTitle">Enumeration values</dt>
<dd>
<table class="doxyEnumTable">

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">EndOfList<a id="a3e1eb307ada3e1ef3a115f4c734aa5eea3d516faa526d601aa8b16c176189f1a6"></a></td>
<td class="doxyEnumItemDescription"> (= 0u)</td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">LineTableInfo<a id="a3e1eb307ada3e1ef3a115f4c734aa5eeadfcbc49fc99e4c3832ed815adc425447"></a></td>
<td class="doxyEnumItemDescription"> (= 1u)</td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">InlineInfo<a id="a3e1eb307ada3e1ef3a115f4c734aa5eeac1775aaace95748849e1216a09f028fc"></a></td>
<td class="doxyEnumItemDescription"> (= 2u)</td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">MergedFunctionsInfo<a id="a3e1eb307ada3e1ef3a115f4c734aa5eea13e6f453fc178a85f4f96cef6fbfe02c"></a></td>
<td class="doxyEnumItemDescription"> (= 3u)</td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">CallSiteInfo<a id="a3e1eb307ada3e1ef3a115f4c734aa5eeaa494eb85f92e884f7e730d15a4dec9c7"></a></td>
<td class="doxyEnumItemDescription"> (= 4u)</td>
</tr>

</table>
</dd>
</dl>

<p>Definition at line 22 of file <a href="/web-llvm/docs/api/files/lib/lib/debuginfo/lib/debuginfo/gsym/functioninfo-cpp">FunctionInfo.cpp</a>.</p>

</div>
</div>

</div>

<hr/>

<p class="doxyGeneratedBy">Generated via <a href="https://github.com/xpack/doxygen2docusaurus">doxygen2docusaurus</a> by <a href="https://www.doxygen.nl">Doxygen</a> 1.15.0.</p>

</div>
