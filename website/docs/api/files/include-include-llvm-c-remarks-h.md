---

# DO NOT EDIT!
# Automatically generated via doxygen2docusaurus by Doxygen.

slug: /api/files/include/include/llvm-c/remarks-h
custom_edit_url: null
toc_max_heading_level: 4
keywords:
  - doxygen
  - reference
  - file

---

<div class="doxyPage">

# The `Remarks.h` File Reference



## Included Headers

<div class="doxyIncludesList">#include "<a href="/web-llvm/docs/api/files/include/include/llvm-c/externc-h">llvm-c/ExternC.h</a>"
#include "<a href="/web-llvm/docs/api/files/include/include/llvm-c/types-h">llvm-c/Types.h</a>"
#include &lt;stddef.h&gt;
</div>

## Typedefs Index

<table class="doxyMembersIndex">

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">typedef</td>
<td class="doxyMemberIndexItemName" align="left" valign="top">struct LLVMRemarkOpaqueString * <a href="/web-llvm/docs/api/groups/llvmcremarks/#ga4029ca629a9c507071bc942d42192ad3">LLVMRemarkStringRef</a></td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>String containing a buffer and a length. <a href="/web-llvm/docs/api/groups/llvmcremarks/#ga4029ca629a9c507071bc942d42192ad3">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">typedef</td>
<td class="doxyMemberIndexItemName" align="left" valign="top">struct LLVMRemarkOpaqueDebugLoc * <a href="/web-llvm/docs/api/groups/llvmcremarks/#gaba2caafe2c1665c6326e01e0dcd0574f">LLVMRemarkDebugLocRef</a></td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>DebugLoc containing File, Line and Column. <a href="/web-llvm/docs/api/groups/llvmcremarks/#gaba2caafe2c1665c6326e01e0dcd0574f">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">typedef</td>
<td class="doxyMemberIndexItemName" align="left" valign="top">struct LLVMRemarkOpaqueArg * <a href="/web-llvm/docs/api/groups/llvmcremarks/#ga5af94d02e0cfc296f48e4c6026c3a505">LLVMRemarkArgRef</a></td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Element of the "Args" list. <a href="/web-llvm/docs/api/groups/llvmcremarks/#ga5af94d02e0cfc296f48e4c6026c3a505">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">typedef</td>
<td class="doxyMemberIndexItemName" align="left" valign="top">struct LLVMRemarkOpaqueEntry * <a href="/web-llvm/docs/api/groups/llvmcremarks/#ga124978db2f97610eed656328fe801d64">LLVMRemarkEntryRef</a></td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>A remark emitted by the compiler. <a href="/web-llvm/docs/api/groups/llvmcremarks/#ga124978db2f97610eed656328fe801d64">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">typedef</td>
<td class="doxyMemberIndexItemName" align="left" valign="top">struct LLVMRemarkOpaqueParser * <a href="/web-llvm/docs/api/groups/llvmcremarks/#ga8065752effe66fd6b55586f04028cccd">LLVMRemarkParserRef</a></td>
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

## Enumerations Index

<table class="doxyMembersIndex">

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">enum</td>
<td class="doxyMemberIndexItemName" align="left" valign="top">LLVMRemarkType { <a href="/web-llvm/docs/api/groups/llvmcremarks/#ga3227d6d7b0c2e64770d011f38c144b1f">...</a> }</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>The type of the emitted remark. <a href="/web-llvm/docs/api/groups/llvmcremarks/#ga3227d6d7b0c2e64770d011f38c144b1f">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

</table>

## Functions Index

<table class="doxyMembersIndex">

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> char *</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="/web-llvm/docs/api/groups/llvmcremarks/#ga0486d7fbdef367b47c2f6c2edbfaac16">LLVMRemarkStringGetData</a> (LLVMRemarkStringRef String)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Returns the buffer holding the string. <a href="/web-llvm/docs/api/groups/llvmcremarks/#ga0486d7fbdef367b47c2f6c2edbfaac16">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">uint32_t</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="/web-llvm/docs/api/groups/llvmcremarks/#ga0f362b5544af2faeb2e8f501502a49bc">LLVMRemarkStringGetLen</a> (LLVMRemarkStringRef String)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Returns the size of the string. <a href="/web-llvm/docs/api/groups/llvmcremarks/#ga0f362b5544af2faeb2e8f501502a49bc">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/groups/llvmcremarks/#ga4029ca629a9c507071bc942d42192ad3">LLVMRemarkStringRef</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="/web-llvm/docs/api/groups/llvmcremarks/#ga8966352852f5e09e811cbef754bdb2d3">LLVMRemarkDebugLocGetSourceFilePath</a> (LLVMRemarkDebugLocRef DL)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Return the path to the source file for a debug location. <a href="/web-llvm/docs/api/groups/llvmcremarks/#ga8966352852f5e09e811cbef754bdb2d3">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">uint32_t</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="/web-llvm/docs/api/groups/llvmcremarks/#ga5e797d19877e5755237084b8a70ba2ce">LLVMRemarkDebugLocGetSourceLine</a> (LLVMRemarkDebugLocRef DL)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Return the line in the source file for a debug location. <a href="/web-llvm/docs/api/groups/llvmcremarks/#ga5e797d19877e5755237084b8a70ba2ce">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">uint32_t</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="/web-llvm/docs/api/groups/llvmcremarks/#gab996bcaa6f19f9477eb99e157e2a079f">LLVMRemarkDebugLocGetSourceColumn</a> (LLVMRemarkDebugLocRef DL)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Return the column in the source file for a debug location. <a href="/web-llvm/docs/api/groups/llvmcremarks/#gab996bcaa6f19f9477eb99e157e2a079f">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/groups/llvmcremarks/#ga4029ca629a9c507071bc942d42192ad3">LLVMRemarkStringRef</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="/web-llvm/docs/api/groups/llvmcremarks/#ga04799d41da890b231715aea5bf8dbe4d">LLVMRemarkArgGetKey</a> (LLVMRemarkArgRef Arg)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Returns the key of an argument. <a href="/web-llvm/docs/api/groups/llvmcremarks/#ga04799d41da890b231715aea5bf8dbe4d">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/groups/llvmcremarks/#ga4029ca629a9c507071bc942d42192ad3">LLVMRemarkStringRef</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="/web-llvm/docs/api/groups/llvmcremarks/#gab6c23a919f81db525433e8feb6bb58a8">LLVMRemarkArgGetValue</a> (LLVMRemarkArgRef Arg)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Returns the value of an argument. <a href="/web-llvm/docs/api/groups/llvmcremarks/#gab6c23a919f81db525433e8feb6bb58a8">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/groups/llvmcremarks/#gaba2caafe2c1665c6326e01e0dcd0574f">LLVMRemarkDebugLocRef</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="/web-llvm/docs/api/groups/llvmcremarks/#gac957fc4c2494542def206b494cec3304">LLVMRemarkArgGetDebugLoc</a> (LLVMRemarkArgRef Arg)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Returns the debug location that is attached to the value of this argument. <a href="/web-llvm/docs/api/groups/llvmcremarks/#gac957fc4c2494542def206b494cec3304">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">void</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="/web-llvm/docs/api/groups/llvmcremarks/#ga4c5e73440d732e43d91a04128fe689de">LLVMRemarkEntryDispose</a> (LLVMRemarkEntryRef Remark)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Free the resources used by the remark entry. <a href="/web-llvm/docs/api/groups/llvmcremarks/#ga4c5e73440d732e43d91a04128fe689de">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">enum <a href="/web-llvm/docs/api/groups/llvmcremarks/#ga3227d6d7b0c2e64770d011f38c144b1f">LLVMRemarkType</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="/web-llvm/docs/api/groups/llvmcremarks/#ga6e8cb8cc35fd788a58ec7c6fc30823e1">LLVMRemarkEntryGetType</a> (LLVMRemarkEntryRef Remark)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>The type of the remark. <a href="/web-llvm/docs/api/groups/llvmcremarks/#ga6e8cb8cc35fd788a58ec7c6fc30823e1">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/groups/llvmcremarks/#ga4029ca629a9c507071bc942d42192ad3">LLVMRemarkStringRef</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="/web-llvm/docs/api/groups/llvmcremarks/#ga03d12c9d1603fb8ceafb3957e1fefd70">LLVMRemarkEntryGetPassName</a> (LLVMRemarkEntryRef Remark)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Get the name of the pass that emitted this remark. <a href="/web-llvm/docs/api/groups/llvmcremarks/#ga03d12c9d1603fb8ceafb3957e1fefd70">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/groups/llvmcremarks/#ga4029ca629a9c507071bc942d42192ad3">LLVMRemarkStringRef</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="/web-llvm/docs/api/groups/llvmcremarks/#gaab67540868f9d9dc5822df8a7cc88bd4">LLVMRemarkEntryGetRemarkName</a> (LLVMRemarkEntryRef Remark)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Get an identifier of the remark. <a href="/web-llvm/docs/api/groups/llvmcremarks/#gaab67540868f9d9dc5822df8a7cc88bd4">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/groups/llvmcremarks/#ga4029ca629a9c507071bc942d42192ad3">LLVMRemarkStringRef</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="/web-llvm/docs/api/groups/llvmcremarks/#gae820dadab3f932f16a27a9e3776da1de">LLVMRemarkEntryGetFunctionName</a> (LLVMRemarkEntryRef Remark)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Get the name of the function being processed when the remark was emitted. <a href="/web-llvm/docs/api/groups/llvmcremarks/#gae820dadab3f932f16a27a9e3776da1de">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/groups/llvmcremarks/#gaba2caafe2c1665c6326e01e0dcd0574f">LLVMRemarkDebugLocRef</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="/web-llvm/docs/api/groups/llvmcremarks/#ga8e83a933adba7960d4221f9e9e199c8f">LLVMRemarkEntryGetDebugLoc</a> (LLVMRemarkEntryRef Remark)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Returns the debug location that is attached to this remark. <a href="/web-llvm/docs/api/groups/llvmcremarks/#ga8e83a933adba7960d4221f9e9e199c8f">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">uint64_t</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="/web-llvm/docs/api/groups/llvmcremarks/#gaf92df00fcd4aad0b639c1b886da31bee">LLVMRemarkEntryGetHotness</a> (LLVMRemarkEntryRef Remark)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Return the hotness of the remark. <a href="/web-llvm/docs/api/groups/llvmcremarks/#gaf92df00fcd4aad0b639c1b886da31bee">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">uint32_t</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="/web-llvm/docs/api/groups/llvmcremarks/#ga9bd84c8c922a02ee6c9f93be92d58b48">LLVMRemarkEntryGetNumArgs</a> (LLVMRemarkEntryRef Remark)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>The number of arguments the remark holds. <a href="/web-llvm/docs/api/groups/llvmcremarks/#ga9bd84c8c922a02ee6c9f93be92d58b48">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/groups/llvmcremarks/#ga5af94d02e0cfc296f48e4c6026c3a505">LLVMRemarkArgRef</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="/web-llvm/docs/api/groups/llvmcremarks/#ga85761e9b8c26fd7989dfd64fe8b796c8">LLVMRemarkEntryGetFirstArg</a> (LLVMRemarkEntryRef Remark)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Get a new iterator to iterate over a remark's argument. <a href="/web-llvm/docs/api/groups/llvmcremarks/#ga85761e9b8c26fd7989dfd64fe8b796c8">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/groups/llvmcremarks/#ga5af94d02e0cfc296f48e4c6026c3a505">LLVMRemarkArgRef</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="/web-llvm/docs/api/groups/llvmcremarks/#ga8801c13719544eb5fc0373ba63b88731">LLVMRemarkEntryGetNextArg</a> (LLVMRemarkArgRef It, LLVMRemarkEntryRef Remark)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Get the next argument in <span class="doxyComputerOutput">Remark</span> from the position of <span class="doxyComputerOutput">It</span>. <a href="/web-llvm/docs/api/groups/llvmcremarks/#ga8801c13719544eb5fc0373ba63b88731">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

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

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">uint32_t</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="/web-llvm/docs/api/groups/llvmcremarks/#ga0369399b76ee94ed8e63cbccf07d08d6">LLVMRemarkVersion</a> (void)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Returns the version of the remarks library. <a href="/web-llvm/docs/api/groups/llvmcremarks/#ga0369399b76ee94ed8e63cbccf07d08d6">More...</a></p>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="/web-llvm/docs/api/groups/llvmcremarks/#gac93670c4f16d0779764ce0776b240c1c">REMARKS_API_VERSION</a>&nbsp;&nbsp;&nbsp;1</td>
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


<hr/>

<p class="doxyGeneratedBy">Generated via <a href="https://github.com/xpack/doxygen2docusaurus">doxygen2docusaurus</a> by <a href="https://www.doxygen.nl">Doxygen</a> 1.15.0.</p>

</div>
