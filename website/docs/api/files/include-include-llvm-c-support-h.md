---

# DO NOT EDIT!
# Automatically generated via doxygen2docusaurus by Doxygen.

slug: /api/files/include/include/llvm-c/support-h
custom_edit_url: null
toc_max_heading_level: 4
keywords:
  - doxygen
  - reference
  - file

---

<div class="doxyPage">

# The `Support.h` File Reference



## Included Headers

<div class="doxyIncludesList">#include "<a href="/web-llvm/docs/api/files/include/include/llvm-c/datatypes-h">llvm-c/DataTypes.h</a>"
#include "<a href="/web-llvm/docs/api/files/include/include/llvm-c/externc-h">llvm-c/ExternC.h</a>"
#include "<a href="/web-llvm/docs/api/files/include/include/llvm-c/types-h">llvm-c/Types.h</a>"
</div>

## Functions Index

<table class="doxyMembersIndex">

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/groups/llvmcsupporttypes/#ga209de0bceb13179a973c6a45211617bd">LLVMBool</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="/web-llvm/docs/api/groups/llvmccore/#ga6fc1331c1a6d2cc6f0fda94f4a4636f9">LLVMLoadLibraryPermanently</a> (const char *Filename)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>This function permanently loads the dynamic library at the given path. <a href="/web-llvm/docs/api/groups/llvmccore/#ga6fc1331c1a6d2cc6f0fda94f4a4636f9">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">void</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="/web-llvm/docs/api/groups/llvmccore/#ga81494b4c1a36f4eb0aae2c1225ede0e4">LLVMParseCommandLineOptions</a> (int argc, const char *const *argv, const char *Overview)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>This function parses the given arguments using the LLVM command line parser. <a href="/web-llvm/docs/api/groups/llvmccore/#ga81494b4c1a36f4eb0aae2c1225ede0e4">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">void *</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="/web-llvm/docs/api/groups/llvmccore/#ga9361c91b1806a646e7c019ee82f927f2">LLVMSearchForAddressOfSymbol</a> (const char *symbolName)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>This function will search through all previously loaded dynamic libraries for the symbol <span class="doxyComputerOutput">symbolName</span>. <a href="/web-llvm/docs/api/groups/llvmccore/#ga9361c91b1806a646e7c019ee82f927f2">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">void</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="/web-llvm/docs/api/groups/llvmccore/#ga8706a6e4aa81193f97cf40c1dd8c0d3a">LLVMAddSymbol</a> (const char *symbolName, void *symbolValue)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>This functions permanently adds the symbol <span class="doxyComputerOutput">symbolName</span> with the value <span class="doxyComputerOutput">symbolValue</span>. <a href="/web-llvm/docs/api/groups/llvmccore/#ga8706a6e4aa81193f97cf40c1dd8c0d3a">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

</table>


<hr/>

<p class="doxyGeneratedBy">Generated via <a href="https://github.com/xpack/doxygen2docusaurus">doxygen2docusaurus</a> by <a href="https://www.doxygen.nl">Doxygen</a> 1.15.0.</p>

</div>
