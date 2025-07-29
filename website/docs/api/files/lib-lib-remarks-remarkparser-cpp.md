---

# DO NOT EDIT!
# Automatically generated via doxygen2docusaurus by Doxygen.

slug: /api/files/lib/lib/remarks/remarkparser-cpp
custom_edit_url: null
toc_max_heading_level: 4
keywords:
  - doxygen
  - reference
  - file

---

<div class="doxyPage">

# `RemarkParser.cpp` File



## Included Headers

<div class="doxyIncludesList">#include "<a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/remarks/remarkparser-h">llvm/Remarks/RemarkParser.h</a>"
#include "BitstreamRemarkParser.h"
#include "<a href="/web-llvm/docs/api/files/lib/lib/remarks/yamlremarkparser-h">YAMLRemarkParser.h</a>"
#include "<a href="/web-llvm/docs/api/files/include/include/llvm-c/remarks-h">llvm-c/Remarks.h</a>"
#include "<a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/support/cbindingwrapping-h">llvm/Support/CBindingWrapping.h</a>"
#include &lt;optional&gt;
</div>

## Namespaces Index

<table class="doxyMembersIndex">

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">namespace</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="/web-llvm/docs/api/namespaces/anonymous-remarkparser-cpp-">anonymous{RemarkParser.cpp}</a></td>
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

## Classes Index

<table class="doxyMembersIndex">

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">struct</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="/web-llvm/docs/api/structs/anonymous-remarkparser-cpp-/cparser">CParser</a></td>
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

## Functions Index

<table class="doxyMembersIndex">

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/groups/llvmcremarks/#ga8065752effe66fd6b55586f04028cccd">LLVMRemarkParserRef</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="/web-llvm/docs/api/groups/llvmcremarks/#ga67a4d14fa2dd7a2908b0888dc1ffbd8d">LLVMRemarkParserCreateYAML</a> (const void *Buf, uint64_t Size)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Creates a remark parser that can be used to parse the buffer located in <span class="doxyComputerOutput">Buf</span> of size <span class="doxyComputerOutput">Size</span> bytes. <a href="/web-llvm/docs/api/groups/llvmcremarks/#ga67a4d14fa2dd7a2908b0888dc1ffbd8d">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/groups/llvmcremarks/#ga8065752effe66fd6b55586f04028cccd">LLVMRemarkParserRef</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="/web-llvm/docs/api/groups/llvmcremarks/#ga3876e400217122e91a34c002981bc82d">LLVMRemarkParserCreateBitstream</a> (const void *Buf, uint64_t Size)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Creates a remark parser that can be used to parse the buffer located in <span class="doxyComputerOutput">Buf</span> of size <span class="doxyComputerOutput">Size</span> bytes. <a href="/web-llvm/docs/api/groups/llvmcremarks/#ga3876e400217122e91a34c002981bc82d">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/groups/llvmcremarks/#ga124978db2f97610eed656328fe801d64">LLVMRemarkEntryRef</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="/web-llvm/docs/api/groups/llvmcremarks/#gada1d7ab2d57b735d67fa095bc099cc7f">LLVMRemarkParserGetNext</a> (LLVMRemarkParserRef Parser)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Returns the next remark in the file. <a href="/web-llvm/docs/api/groups/llvmcremarks/#gada1d7ab2d57b735d67fa095bc099cc7f">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/groups/llvmcsupporttypes/#ga209de0bceb13179a973c6a45211617bd">LLVMBool</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="/web-llvm/docs/api/groups/llvmcremarks/#ga88083b5d141c27d1dd14dc4d2f0f81a2">LLVMRemarkParserHasError</a> (LLVMRemarkParserRef Parser)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Returns <span class="doxyComputerOutput">1</span> if the parser encountered an error while parsing the buffer. <a href="/web-llvm/docs/api/groups/llvmcremarks/#ga88083b5d141c27d1dd14dc4d2f0f81a2">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> char *</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="/web-llvm/docs/api/groups/llvmcremarks/#gab870147e749d296c569783d7539b6656">LLVMRemarkParserGetErrorMessage</a> (LLVMRemarkParserRef Parser)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Returns a null-terminated string containing an error message. <a href="/web-llvm/docs/api/groups/llvmcremarks/#gab870147e749d296c569783d7539b6656">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">void</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="/web-llvm/docs/api/groups/llvmcremarks/#gad7ebecfc91d543900784cb97c6302d47">LLVMRemarkParserDispose</a> (LLVMRemarkParserRef Parser)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Releases all the resources used by <span class="doxyComputerOutput">Parser</span>. <a href="/web-llvm/docs/api/groups/llvmcremarks/#gad7ebecfc91d543900784cb97c6302d47">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

</table>


<hr/>

<p class="doxyGeneratedBy">Generated via <a href="https://github.com/xpack/doxygen2docusaurus">doxygen2docusaurus</a> by <a href="https://www.doxygen.nl">Doxygen</a> 1.15.0.</p>

</div>
