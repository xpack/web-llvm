---

# DO NOT EDIT!
# Automatically generated via doxygen2docusaurus by Doxygen.

slug: /api/groups/llvmcremarks
custom_edit_url: null
toc_max_heading_level: 4
keywords:
  - doxygen
  - reference
  - group

---

<div class="doxyPage">

# The Remarks Reference



## Typedefs Index

<table class="doxyMembersIndex">

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">typedef</td>
<td class="doxyMemberIndexItemName" align="left" valign="top">struct LLVMRemarkOpaqueString * <a href="#ga4029ca629a9c507071bc942d42192ad3">LLVMRemarkStringRef</a></td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>String containing a buffer and a length. <a href="#ga4029ca629a9c507071bc942d42192ad3">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">typedef</td>
<td class="doxyMemberIndexItemName" align="left" valign="top">struct LLVMRemarkOpaqueDebugLoc * <a href="#gaba2caafe2c1665c6326e01e0dcd0574f">LLVMRemarkDebugLocRef</a></td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>DebugLoc containing File, Line and Column. <a href="#gaba2caafe2c1665c6326e01e0dcd0574f">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">typedef</td>
<td class="doxyMemberIndexItemName" align="left" valign="top">struct LLVMRemarkOpaqueArg * <a href="#ga5af94d02e0cfc296f48e4c6026c3a505">LLVMRemarkArgRef</a></td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Element of the "Args" list. <a href="#ga5af94d02e0cfc296f48e4c6026c3a505">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">typedef</td>
<td class="doxyMemberIndexItemName" align="left" valign="top">struct LLVMRemarkOpaqueEntry * <a href="#ga124978db2f97610eed656328fe801d64">LLVMRemarkEntryRef</a></td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>A remark emitted by the compiler. <a href="#ga124978db2f97610eed656328fe801d64">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">typedef</td>
<td class="doxyMemberIndexItemName" align="left" valign="top">struct LLVMRemarkOpaqueParser * <a href="#ga8065752effe66fd6b55586f04028cccd">LLVMRemarkParserRef</a></td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top">LLVMRemarkType { <a href="#ga3227d6d7b0c2e64770d011f38c144b1f">...</a> }</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>The type of the emitted remark. <a href="#ga3227d6d7b0c2e64770d011f38c144b1f">More...</a></p>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ga0486d7fbdef367b47c2f6c2edbfaac16">LLVMRemarkStringGetData</a> (LLVMRemarkStringRef String)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Returns the buffer holding the string. <a href="#ga0486d7fbdef367b47c2f6c2edbfaac16">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">uint32_t</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ga0f362b5544af2faeb2e8f501502a49bc">LLVMRemarkStringGetLen</a> (LLVMRemarkStringRef String)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Returns the size of the string. <a href="#ga0f362b5544af2faeb2e8f501502a49bc">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="#ga4029ca629a9c507071bc942d42192ad3">LLVMRemarkStringRef</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ga8966352852f5e09e811cbef754bdb2d3">LLVMRemarkDebugLocGetSourceFilePath</a> (LLVMRemarkDebugLocRef DL)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Return the path to the source file for a debug location. <a href="#ga8966352852f5e09e811cbef754bdb2d3">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">uint32_t</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ga5e797d19877e5755237084b8a70ba2ce">LLVMRemarkDebugLocGetSourceLine</a> (LLVMRemarkDebugLocRef DL)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Return the line in the source file for a debug location. <a href="#ga5e797d19877e5755237084b8a70ba2ce">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">uint32_t</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#gab996bcaa6f19f9477eb99e157e2a079f">LLVMRemarkDebugLocGetSourceColumn</a> (LLVMRemarkDebugLocRef DL)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Return the column in the source file for a debug location. <a href="#gab996bcaa6f19f9477eb99e157e2a079f">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="#ga4029ca629a9c507071bc942d42192ad3">LLVMRemarkStringRef</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ga04799d41da890b231715aea5bf8dbe4d">LLVMRemarkArgGetKey</a> (LLVMRemarkArgRef Arg)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Returns the key of an argument. <a href="#ga04799d41da890b231715aea5bf8dbe4d">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="#ga4029ca629a9c507071bc942d42192ad3">LLVMRemarkStringRef</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#gab6c23a919f81db525433e8feb6bb58a8">LLVMRemarkArgGetValue</a> (LLVMRemarkArgRef Arg)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Returns the value of an argument. <a href="#gab6c23a919f81db525433e8feb6bb58a8">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="#gaba2caafe2c1665c6326e01e0dcd0574f">LLVMRemarkDebugLocRef</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#gac957fc4c2494542def206b494cec3304">LLVMRemarkArgGetDebugLoc</a> (LLVMRemarkArgRef Arg)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Returns the debug location that is attached to the value of this argument. <a href="#gac957fc4c2494542def206b494cec3304">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">void</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ga4c5e73440d732e43d91a04128fe689de">LLVMRemarkEntryDispose</a> (LLVMRemarkEntryRef Remark)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Free the resources used by the remark entry. <a href="#ga4c5e73440d732e43d91a04128fe689de">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">enum <a href="#ga3227d6d7b0c2e64770d011f38c144b1f">LLVMRemarkType</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ga6e8cb8cc35fd788a58ec7c6fc30823e1">LLVMRemarkEntryGetType</a> (LLVMRemarkEntryRef Remark)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>The type of the remark. <a href="#ga6e8cb8cc35fd788a58ec7c6fc30823e1">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="#ga4029ca629a9c507071bc942d42192ad3">LLVMRemarkStringRef</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ga03d12c9d1603fb8ceafb3957e1fefd70">LLVMRemarkEntryGetPassName</a> (LLVMRemarkEntryRef Remark)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Get the name of the pass that emitted this remark. <a href="#ga03d12c9d1603fb8ceafb3957e1fefd70">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="#ga4029ca629a9c507071bc942d42192ad3">LLVMRemarkStringRef</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#gaab67540868f9d9dc5822df8a7cc88bd4">LLVMRemarkEntryGetRemarkName</a> (LLVMRemarkEntryRef Remark)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Get an identifier of the remark. <a href="#gaab67540868f9d9dc5822df8a7cc88bd4">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="#ga4029ca629a9c507071bc942d42192ad3">LLVMRemarkStringRef</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#gae820dadab3f932f16a27a9e3776da1de">LLVMRemarkEntryGetFunctionName</a> (LLVMRemarkEntryRef Remark)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Get the name of the function being processed when the remark was emitted. <a href="#gae820dadab3f932f16a27a9e3776da1de">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="#gaba2caafe2c1665c6326e01e0dcd0574f">LLVMRemarkDebugLocRef</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ga8e83a933adba7960d4221f9e9e199c8f">LLVMRemarkEntryGetDebugLoc</a> (LLVMRemarkEntryRef Remark)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Returns the debug location that is attached to this remark. <a href="#ga8e83a933adba7960d4221f9e9e199c8f">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">uint64_t</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#gaf92df00fcd4aad0b639c1b886da31bee">LLVMRemarkEntryGetHotness</a> (LLVMRemarkEntryRef Remark)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Return the hotness of the remark. <a href="#gaf92df00fcd4aad0b639c1b886da31bee">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">uint32_t</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ga9bd84c8c922a02ee6c9f93be92d58b48">LLVMRemarkEntryGetNumArgs</a> (LLVMRemarkEntryRef Remark)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>The number of arguments the remark holds. <a href="#ga9bd84c8c922a02ee6c9f93be92d58b48">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="#ga5af94d02e0cfc296f48e4c6026c3a505">LLVMRemarkArgRef</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ga85761e9b8c26fd7989dfd64fe8b796c8">LLVMRemarkEntryGetFirstArg</a> (LLVMRemarkEntryRef Remark)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Get a new iterator to iterate over a remark's argument. <a href="#ga85761e9b8c26fd7989dfd64fe8b796c8">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="#ga5af94d02e0cfc296f48e4c6026c3a505">LLVMRemarkArgRef</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ga8801c13719544eb5fc0373ba63b88731">LLVMRemarkEntryGetNextArg</a> (LLVMRemarkArgRef It, LLVMRemarkEntryRef Remark)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Get the next argument in <span class="doxyComputerOutput">Remark</span> from the position of <span class="doxyComputerOutput">It</span>. <a href="#ga8801c13719544eb5fc0373ba63b88731">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="#ga8065752effe66fd6b55586f04028cccd">LLVMRemarkParserRef</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ga67a4d14fa2dd7a2908b0888dc1ffbd8d">LLVMRemarkParserCreateYAML</a> (const void *Buf, uint64_t Size)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Creates a remark parser that can be used to parse the buffer located in <span class="doxyComputerOutput">Buf</span> of size <span class="doxyComputerOutput">Size</span> bytes. <a href="#ga67a4d14fa2dd7a2908b0888dc1ffbd8d">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="#ga8065752effe66fd6b55586f04028cccd">LLVMRemarkParserRef</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ga3876e400217122e91a34c002981bc82d">LLVMRemarkParserCreateBitstream</a> (const void *Buf, uint64_t Size)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Creates a remark parser that can be used to parse the buffer located in <span class="doxyComputerOutput">Buf</span> of size <span class="doxyComputerOutput">Size</span> bytes. <a href="#ga3876e400217122e91a34c002981bc82d">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="#ga124978db2f97610eed656328fe801d64">LLVMRemarkEntryRef</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#gada1d7ab2d57b735d67fa095bc099cc7f">LLVMRemarkParserGetNext</a> (LLVMRemarkParserRef Parser)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Returns the next remark in the file. <a href="#gada1d7ab2d57b735d67fa095bc099cc7f">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/groups/llvmcsupporttypes/#ga209de0bceb13179a973c6a45211617bd">LLVMBool</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ga88083b5d141c27d1dd14dc4d2f0f81a2">LLVMRemarkParserHasError</a> (LLVMRemarkParserRef Parser)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Returns <span class="doxyComputerOutput">1</span> if the parser encountered an error while parsing the buffer. <a href="#ga88083b5d141c27d1dd14dc4d2f0f81a2">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> char *</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#gab870147e749d296c569783d7539b6656">LLVMRemarkParserGetErrorMessage</a> (LLVMRemarkParserRef Parser)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Returns a null-terminated string containing an error message. <a href="#gab870147e749d296c569783d7539b6656">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">void</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#gad7ebecfc91d543900784cb97c6302d47">LLVMRemarkParserDispose</a> (LLVMRemarkParserRef Parser)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Releases all the resources used by <span class="doxyComputerOutput">Parser</span>. <a href="#gad7ebecfc91d543900784cb97c6302d47">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">uint32_t</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ga0369399b76ee94ed8e63cbccf07d08d6">LLVMRemarkVersion</a> (void)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Returns the version of the remarks library. <a href="#ga0369399b76ee94ed8e63cbccf07d08d6">More...</a></p>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#gac93670c4f16d0779764ce0776b240c1c">REMARKS_API_VERSION</a>&nbsp;&nbsp;&nbsp;1</td>
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

## Typedefs

### LLVMRemarkArgRef {#ga5af94d02e0cfc296f48e4c6026c3a505}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">typedef struct LLVMRemarkOpaqueArg* LLVMRemarkArgRef</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Element of the "Args" list.</p>


<p>The key might give more information about what the semantics of the value are, e.g. "Callee" will tell you that the value is a symbol that names a function.</p>


<dl class="doxySectionUser">
<dt>Since</dt>
<dd><p>REMARKS_API_VERSION=0</p></dd>
</dl>


<p>Definition at line 109 of file <a href="/web-llvm/docs/api/files/include/include/llvm-c/remarks-h">Remarks.h</a>.</p>

</div>
</div>

### LLVMRemarkDebugLocRef {#gaba2caafe2c1665c6326e01e0dcd0574f}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">typedef struct LLVMRemarkOpaqueDebugLoc* LLVMRemarkDebugLocRef</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>DebugLoc containing File, Line and Column.</p>


<dl class="doxySectionUser">
<dt>Since</dt>
<dd><p>REMARKS_API_VERSION=0</p></dd>
</dl>


<p>Definition at line 78 of file <a href="/web-llvm/docs/api/files/include/include/llvm-c/remarks-h">Remarks.h</a>.</p>

</div>
</div>

### LLVMRemarkEntryRef {#ga124978db2f97610eed656328fe801d64}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">typedef struct LLVMRemarkOpaqueEntry* LLVMRemarkEntryRef</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>A remark emitted by the compiler.</p>


<dl class="doxySectionUser">
<dt>Since</dt>
<dd><p>REMARKS_API_VERSION=0</p></dd>
</dl>


<p>Definition at line 140 of file <a href="/web-llvm/docs/api/files/include/include/llvm-c/remarks-h">Remarks.h</a>.</p>

</div>
</div>

### LLVMRemarkParserRef {#ga8065752effe66fd6b55586f04028cccd}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">typedef struct LLVMRemarkOpaqueParser* LLVMRemarkParserRef</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 230 of file <a href="/web-llvm/docs/api/files/include/include/llvm-c/remarks-h">Remarks.h</a>.</p>

</div>
</div>

### LLVMRemarkStringRef {#ga4029ca629a9c507071bc942d42192ad3}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">typedef struct LLVMRemarkOpaqueString* LLVMRemarkStringRef</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>String containing a buffer and a length.</p>


<p>The buffer is not guaranteed to be zero-terminated.</p>


<dl class="doxySectionUser">
<dt>Since</dt>
<dd><p>REMARKS_API_VERSION=0</p></dd>
</dl>


<p>Definition at line 57 of file <a href="/web-llvm/docs/api/files/include/include/llvm-c/remarks-h">Remarks.h</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Enumerations

### LLVMRemarkType {#ga3227d6d7b0c2e64770d011f38c144b1f}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">enum LLVMRemarkType </td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>The type of the emitted remark.</p>

<dl class="doxyEnumList">
<dt class="doxyEnumTableTitle">Enumeration values</dt>
<dd>
<table class="doxyEnumTable">

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">LLVMRemarkTypeUnknown<a id="gga3227d6d7b0c2e64770d011f38c144b1fab1ab41d37803bef06e81525e78f3a9c8"></a></td>
<td class="doxyEnumItemDescription"></td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">LLVMRemarkTypePassed<a id="gga3227d6d7b0c2e64770d011f38c144b1fa6bae23855a302a123d506092295675b7"></a></td>
<td class="doxyEnumItemDescription"></td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">LLVMRemarkTypeMissed<a id="gga3227d6d7b0c2e64770d011f38c144b1fafeec6fa6d9485f2884770d4b33c18090"></a></td>
<td class="doxyEnumItemDescription"></td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">LLVMRemarkTypeAnalysis<a id="gga3227d6d7b0c2e64770d011f38c144b1fae72f71c71a1449417a0fd9864fb6b3b0"></a></td>
<td class="doxyEnumItemDescription"></td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">LLVMRemarkTypeAnalysisFPCommute<a id="gga3227d6d7b0c2e64770d011f38c144b1fa18832aa3767aac4727cdae8d79d3bcc2"></a></td>
<td class="doxyEnumItemDescription"></td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">LLVMRemarkTypeAnalysisAliasing<a id="gga3227d6d7b0c2e64770d011f38c144b1fa3ae3a690b7fdf2f692166e48112de0b7"></a></td>
<td class="doxyEnumItemDescription"></td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">LLVMRemarkTypeFailure<a id="gga3227d6d7b0c2e64770d011f38c144b1face40aea6ef6bce5db7c9ecd141725b22"></a></td>
<td class="doxyEnumItemDescription"></td>
</tr>

</table>
</dd>
</dl>

<p>Definition at line 41 of file <a href="/web-llvm/docs/api/files/include/include/llvm-c/remarks-h">Remarks.h</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Functions

### LLVMRemarkArgGetDebugLoc() {#gac957fc4c2494542def206b494cec3304}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">LLVMRemarkDebugLocRef LLVMRemarkArgGetDebugLoc (<a href="#ga5af94d02e0cfc296f48e4c6026c3a505">LLVMRemarkArgRef</a> Arg)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Returns the debug location that is attached to the value of this argument.</p>


<p>If there is no debug location, the return value will be <span class="doxyComputerOutput">NULL</span>.</p>


<dl class="doxySectionUser">
<dt>Since</dt>
<dd><p>REMARKS_API_VERSION=0</p></dd>
</dl>


<p>Declaration at line 133 of file <a href="/web-llvm/docs/api/files/include/include/llvm-c/remarks-h">Remarks.h</a>, definition at line 100 of file <a href="/web-llvm/docs/api/files/lib/lib/remarks/remark-cpp">Remark.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/namespaces/llvm/#aa3d613e3ad429bdb5b1a7d22796028e9">llvm::unwrap</a> and <a href="/web-llvm/docs/api/namespaces/llvm/#ac9a23c88949ad27ad62f0ee03254ee3a">llvm::wrap</a>.</p>

</div>
</div>

### LLVMRemarkArgGetKey() {#ga04799d41da890b231715aea5bf8dbe4d}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">LLVMRemarkStringRef LLVMRemarkArgGetKey (<a href="#ga5af94d02e0cfc296f48e4c6026c3a505">LLVMRemarkArgRef</a> Arg)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Returns the key of an argument.</p>


<p>The key defines what the value is, and the same key can appear multiple times in the list of arguments.</p>


<dl class="doxySectionUser">
<dt>Since</dt>
<dd><p>REMARKS_API_VERSION=0</p></dd>
</dl>


<p>Declaration at line 117 of file <a href="/web-llvm/docs/api/files/include/include/llvm-c/remarks-h">Remarks.h</a>, definition at line 91 of file <a href="/web-llvm/docs/api/files/lib/lib/remarks/remark-cpp">Remark.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/namespaces/llvm/#a98c6256d0644613c6b5b3e2ef06ef5ce">llvm::InnerAnalysisManagerProxy&lt; AnalysisManagerT, IRUnitT, ExtraArgTs... &gt;::Key</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#aa3d613e3ad429bdb5b1a7d22796028e9">llvm::unwrap</a> and <a href="/web-llvm/docs/api/namespaces/llvm/#ac9a23c88949ad27ad62f0ee03254ee3a">llvm::wrap</a>.</p>

</div>
</div>

### LLVMRemarkArgGetValue() {#gab6c23a919f81db525433e8feb6bb58a8}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">LLVMRemarkStringRef LLVMRemarkArgGetValue (<a href="#ga5af94d02e0cfc296f48e4c6026c3a505">LLVMRemarkArgRef</a> Arg)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Returns the value of an argument.</p>


<p>This is a string that can contain newlines.</p>


<dl class="doxySectionUser">
<dt>Since</dt>
<dd><p>REMARKS_API_VERSION=0</p></dd>
</dl>


<p>Declaration at line 124 of file <a href="/web-llvm/docs/api/files/include/include/llvm-c/remarks-h">Remarks.h</a>, definition at line 95 of file <a href="/web-llvm/docs/api/files/lib/lib/remarks/remark-cpp">Remark.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/namespaces/llvm/#aa3d613e3ad429bdb5b1a7d22796028e9">llvm::unwrap</a> and <a href="/web-llvm/docs/api/namespaces/llvm/#ac9a23c88949ad27ad62f0ee03254ee3a">llvm::wrap</a>.</p>

</div>
</div>

### LLVMRemarkDebugLocGetSourceColumn() {#gab996bcaa6f19f9477eb99e157e2a079f}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">uint32_t LLVMRemarkDebugLocGetSourceColumn (<a href="#gaba2caafe2c1665c6326e01e0dcd0574f">LLVMRemarkDebugLocRef</a> DL)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Return the column in the source file for a debug location.</p>


<dl class="doxySectionUser">
<dt>Since</dt>
<dd><p>REMARKS_API_VERSION=0</p></dd>
</dl>


<p>Declaration at line 100 of file <a href="/web-llvm/docs/api/files/include/include/llvm-c/remarks-h">Remarks.h</a>, definition at line 87 of file <a href="/web-llvm/docs/api/files/lib/lib/remarks/remark-cpp">Remark.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/arm/armslshardening-cpp/#ad467c4ab9119043f9b7750ab986be61a">DL</a> and <a href="/web-llvm/docs/api/namespaces/llvm/#aa3d613e3ad429bdb5b1a7d22796028e9">llvm::unwrap</a>.</p>

</div>
</div>

### LLVMRemarkDebugLocGetSourceFilePath() {#ga8966352852f5e09e811cbef754bdb2d3}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">LLVMRemarkStringRef LLVMRemarkDebugLocGetSourceFilePath (<a href="#gaba2caafe2c1665c6326e01e0dcd0574f">LLVMRemarkDebugLocRef</a> DL)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Return the path to the source file for a debug location.</p>


<dl class="doxySectionUser">
<dt>Since</dt>
<dd><p>REMARKS_API_VERSION=0</p></dd>
</dl>


<p>Declaration at line 86 of file <a href="/web-llvm/docs/api/files/include/include/llvm-c/remarks-h">Remarks.h</a>, definition at line 78 of file <a href="/web-llvm/docs/api/files/lib/lib/remarks/remark-cpp">Remark.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/arm/armslshardening-cpp/#ad467c4ab9119043f9b7750ab986be61a">DL</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#aa3d613e3ad429bdb5b1a7d22796028e9">llvm::unwrap</a> and <a href="/web-llvm/docs/api/namespaces/llvm/#ac9a23c88949ad27ad62f0ee03254ee3a">llvm::wrap</a>.</p>

</div>
</div>

### LLVMRemarkDebugLocGetSourceLine() {#ga5e797d19877e5755237084b8a70ba2ce}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">uint32_t LLVMRemarkDebugLocGetSourceLine (<a href="#gaba2caafe2c1665c6326e01e0dcd0574f">LLVMRemarkDebugLocRef</a> DL)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Return the line in the source file for a debug location.</p>


<dl class="doxySectionUser">
<dt>Since</dt>
<dd><p>REMARKS_API_VERSION=0</p></dd>
</dl>


<p>Declaration at line 93 of file <a href="/web-llvm/docs/api/files/include/include/llvm-c/remarks-h">Remarks.h</a>, definition at line 82 of file <a href="/web-llvm/docs/api/files/lib/lib/remarks/remark-cpp">Remark.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/arm/armslshardening-cpp/#ad467c4ab9119043f9b7750ab986be61a">DL</a> and <a href="/web-llvm/docs/api/namespaces/llvm/#aa3d613e3ad429bdb5b1a7d22796028e9">llvm::unwrap</a>.</p>

</div>
</div>

### LLVMRemarkEntryDispose() {#ga4c5e73440d732e43d91a04128fe689de}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void LLVMRemarkEntryDispose (<a href="#ga124978db2f97610eed656328fe801d64">LLVMRemarkEntryRef</a> Remark)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Free the resources used by the remark entry.</p>


<dl class="doxySectionUser">
<dt>Since</dt>
<dd><p>REMARKS_API_VERSION=0</p></dd>
</dl>


<p>Declaration at line 147 of file <a href="/web-llvm/docs/api/files/include/include/llvm-c/remarks-h">Remarks.h</a>, definition at line 106 of file <a href="/web-llvm/docs/api/files/lib/lib/remarks/remark-cpp">Remark.cpp</a>.</p>


<p>Reference <a href="/web-llvm/docs/api/namespaces/llvm/#aa3d613e3ad429bdb5b1a7d22796028e9">llvm::unwrap</a>.</p>

</div>
</div>

### LLVMRemarkEntryGetDebugLoc() {#ga8e83a933adba7960d4221f9e9e199c8f}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">LLVMRemarkDebugLocRef LLVMRemarkEntryGetDebugLoc (<a href="#ga124978db2f97610eed656328fe801d64">LLVMRemarkEntryRef</a> Remark)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Returns the debug location that is attached to this remark.</p>


<p>If there is no debug location, the return value will be <span class="doxyComputerOutput">NULL</span>.</p>


<dl class="doxySectionUser">
<dt>Since</dt>
<dd><p>REMARKS_API_VERSION=0</p></dd>
</dl>


<p>Declaration at line 189 of file <a href="/web-llvm/docs/api/files/include/include/llvm-c/remarks-h">Remarks.h</a>, definition at line 131 of file <a href="/web-llvm/docs/api/files/lib/lib/remarks/remark-cpp">Remark.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/namespaces/llvm/#aa3d613e3ad429bdb5b1a7d22796028e9">llvm::unwrap</a> and <a href="/web-llvm/docs/api/namespaces/llvm/#ac9a23c88949ad27ad62f0ee03254ee3a">llvm::wrap</a>.</p>

</div>
</div>

### LLVMRemarkEntryGetFirstArg() {#ga85761e9b8c26fd7989dfd64fe8b796c8}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">LLVMRemarkArgRef LLVMRemarkEntryGetFirstArg (<a href="#ga124978db2f97610eed656328fe801d64">LLVMRemarkEntryRef</a> Remark)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Get a new iterator to iterate over a remark's argument.</p>


<p>If there are no arguments in <span class="doxyComputerOutput">Remark</span>, the return value will be <span class="doxyComputerOutput">NULL</span>.</p>


<p>The lifetime of the returned value is bound to the lifetime of <span class="doxyComputerOutput">Remark</span>.</p>


<dl class="doxySectionUser">
<dt>Since</dt>
<dd><p>REMARKS_API_VERSION=0</p></dd>
</dl>


<p>Declaration at line 216 of file <a href="/web-llvm/docs/api/files/include/include/llvm-c/remarks-h">Remarks.h</a>, definition at line 148 of file <a href="/web-llvm/docs/api/files/lib/lib/remarks/remark-cpp">Remark.cpp</a>.</p>


<p>Reference <a href="/web-llvm/docs/api/namespaces/llvm/#aa3d613e3ad429bdb5b1a7d22796028e9">llvm::unwrap</a>.</p>

</div>
</div>

### LLVMRemarkEntryGetFunctionName() {#gae820dadab3f932f16a27a9e3776da1de}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">LLVMRemarkStringRef LLVMRemarkEntryGetFunctionName (<a href="#ga124978db2f97610eed656328fe801d64">LLVMRemarkEntryRef</a> Remark)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Get the name of the function being processed when the remark was emitted.</p>


<dl class="doxySectionUser">
<dt>Since</dt>
<dd><p>REMARKS_API_VERSION=0</p></dd>
</dl>


<p>Declaration at line 179 of file <a href="/web-llvm/docs/api/files/include/include/llvm-c/remarks-h">Remarks.h</a>, definition at line 126 of file <a href="/web-llvm/docs/api/files/lib/lib/remarks/remark-cpp">Remark.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/namespaces/llvm/#aa3d613e3ad429bdb5b1a7d22796028e9">llvm::unwrap</a> and <a href="/web-llvm/docs/api/namespaces/llvm/#ac9a23c88949ad27ad62f0ee03254ee3a">llvm::wrap</a>.</p>

</div>
</div>

### LLVMRemarkEntryGetHotness() {#gaf92df00fcd4aad0b639c1b886da31bee}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">uint64_t LLVMRemarkEntryGetHotness (<a href="#ga124978db2f97610eed656328fe801d64">LLVMRemarkEntryRef</a> Remark)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Return the hotness of the remark.</p>


<p>A hotness of <span class="doxyComputerOutput">0</span> means this value is not set.</p>


<dl class="doxySectionUser">
<dt>Since</dt>
<dd><p>REMARKS_API_VERSION=0</p></dd>
</dl>


<p>Declaration at line 198 of file <a href="/web-llvm/docs/api/files/include/include/llvm-c/remarks-h">Remarks.h</a>, definition at line 137 of file <a href="/web-llvm/docs/api/files/lib/lib/remarks/remark-cpp">Remark.cpp</a>.</p>


<p>Reference <a href="/web-llvm/docs/api/namespaces/llvm/#aa3d613e3ad429bdb5b1a7d22796028e9">llvm::unwrap</a>.</p>

</div>
</div>

### LLVMRemarkEntryGetNextArg() {#ga8801c13719544eb5fc0373ba63b88731}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">LLVMRemarkArgRef LLVMRemarkEntryGetNextArg (<a href="#ga5af94d02e0cfc296f48e4c6026c3a505">LLVMRemarkArgRef</a> It, <a href="#ga124978db2f97610eed656328fe801d64">LLVMRemarkEntryRef</a> Remark)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Get the next argument in <span class="doxyComputerOutput">Remark</span> from the position of <span class="doxyComputerOutput">It</span>.</p>


<p>Returns <span class="doxyComputerOutput">NULL</span> if there are no more arguments available.</p>


<p>The lifetime of the returned value is bound to the lifetime of <span class="doxyComputerOutput">Remark</span>.</p>


<dl class="doxySectionUser">
<dt>Since</dt>
<dd><p>REMARKS_API_VERSION=0</p></dd>
</dl>


<p>Declaration at line 227 of file <a href="/web-llvm/docs/api/files/include/include/llvm-c/remarks-h">Remarks.h</a>, definition at line 158 of file <a href="/web-llvm/docs/api/files/lib/lib/remarks/remark-cpp">Remark.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/namespaces/llvm/#ab13c360340346d082b959b8cd79f2c1a">llvm::Next</a> and <a href="/web-llvm/docs/api/namespaces/llvm/#aa3d613e3ad429bdb5b1a7d22796028e9">llvm::unwrap</a>.</p>

</div>
</div>

### LLVMRemarkEntryGetNumArgs() {#ga9bd84c8c922a02ee6c9f93be92d58b48}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">uint32_t LLVMRemarkEntryGetNumArgs (<a href="#ga124978db2f97610eed656328fe801d64">LLVMRemarkEntryRef</a> Remark)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>The number of arguments the remark holds.</p>


<dl class="doxySectionUser">
<dt>Since</dt>
<dd><p>REMARKS_API_VERSION=0</p></dd>
</dl>


<p>Declaration at line 205 of file <a href="/web-llvm/docs/api/files/include/include/llvm-c/remarks-h">Remarks.h</a>, definition at line 143 of file <a href="/web-llvm/docs/api/files/lib/lib/remarks/remark-cpp">Remark.cpp</a>.</p>


<p>Reference <a href="/web-llvm/docs/api/namespaces/llvm/#aa3d613e3ad429bdb5b1a7d22796028e9">llvm::unwrap</a>.</p>

</div>
</div>

### LLVMRemarkEntryGetPassName() {#ga03d12c9d1603fb8ceafb3957e1fefd70}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">LLVMRemarkStringRef LLVMRemarkEntryGetPassName (<a href="#ga124978db2f97610eed656328fe801d64">LLVMRemarkEntryRef</a> Remark)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Get the name of the pass that emitted this remark.</p>


<dl class="doxySectionUser">
<dt>Since</dt>
<dd><p>REMARKS_API_VERSION=0</p></dd>
</dl>


<p>Declaration at line 163 of file <a href="/web-llvm/docs/api/files/include/include/llvm-c/remarks-h">Remarks.h</a>, definition at line 116 of file <a href="/web-llvm/docs/api/files/lib/lib/remarks/remark-cpp">Remark.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/x86/x86loweramxintrinsics-cpp/#adb9257105a403ef9d0773b87693f7779">PassName</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#aa3d613e3ad429bdb5b1a7d22796028e9">llvm::unwrap</a> and <a href="/web-llvm/docs/api/namespaces/llvm/#ac9a23c88949ad27ad62f0ee03254ee3a">llvm::wrap</a>.</p>

</div>
</div>

### LLVMRemarkEntryGetRemarkName() {#gaab67540868f9d9dc5822df8a7cc88bd4}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">LLVMRemarkStringRef LLVMRemarkEntryGetRemarkName (<a href="#ga124978db2f97610eed656328fe801d64">LLVMRemarkEntryRef</a> Remark)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Get an identifier of the remark.</p>


<dl class="doxySectionUser">
<dt>Since</dt>
<dd><p>REMARKS_API_VERSION=0</p></dd>
</dl>


<p>Declaration at line 171 of file <a href="/web-llvm/docs/api/files/include/include/llvm-c/remarks-h">Remarks.h</a>, definition at line 121 of file <a href="/web-llvm/docs/api/files/lib/lib/remarks/remark-cpp">Remark.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/namespaces/llvm/#aa3d613e3ad429bdb5b1a7d22796028e9">llvm::unwrap</a> and <a href="/web-llvm/docs/api/namespaces/llvm/#ac9a23c88949ad27ad62f0ee03254ee3a">llvm::wrap</a>.</p>

</div>
</div>

### LLVMRemarkEntryGetType() {#ga6e8cb8cc35fd788a58ec7c6fc30823e1}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">enum LLVMRemarkType LLVMRemarkEntryGetType (<a href="#ga124978db2f97610eed656328fe801d64">LLVMRemarkEntryRef</a> Remark)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>The type of the remark.</p>


<p>For example, it can allow users to only keep the missed optimizations from the compiler.</p>


<dl class="doxySectionUser">
<dt>Since</dt>
<dd><p>REMARKS_API_VERSION=0</p></dd>
</dl>


<p>Declaration at line 155 of file <a href="/web-llvm/docs/api/files/include/include/llvm-c/remarks-h">Remarks.h</a>, definition at line 110 of file <a href="/web-llvm/docs/api/files/lib/lib/remarks/remark-cpp">Remark.cpp</a>.</p>


<p>Reference <a href="/web-llvm/docs/api/namespaces/llvm/#aa3d613e3ad429bdb5b1a7d22796028e9">llvm::unwrap</a>.</p>

</div>
</div>

### LLVMRemarkParserCreateBitstream() {#ga3876e400217122e91a34c002981bc82d}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">LLVMRemarkParserRef LLVMRemarkParserCreateBitstream (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> void * Buf, uint64_t Size)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Creates a remark parser that can be used to parse the buffer located in <span class="doxyComputerOutput">Buf</span> of size <span class="doxyComputerOutput">Size</span> bytes.</p>


<p><span class="doxyComputerOutput">Buf</span> cannot be <span class="doxyComputerOutput">NULL</span>.</p>


<p>This function should be paired with <a href="#gad7ebecfc91d543900784cb97c6302d47">LLVMRemarkParserDispose()</a> to avoid leaking resources.</p>


<dl class="doxySectionUser">
<dt>Since</dt>
<dd><p>REMARKS_API_VERSION=1</p></dd>
</dl>


<p>Declaration at line 257 of file <a href="/web-llvm/docs/api/files/include/include/llvm-c/remarks-h">Remarks.h</a>, definition at line 136 of file <a href="/web-llvm/docs/api/files/lib/lib/remarks/remarkparser-cpp">RemarkParser.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/namespaces/llvm/remarks/#a6e038f443b9029221c590524f08be0bea0b79eab5aacf81d139c4eaec818a549a">llvm::remarks::Bitstream</a>, <a href="/web-llvm/docs/api/files/lib/lib/analysis/inlineorder-cpp/#a7ee6f0cb51c3b9056199e9a0001fe8c3a6f6cb72d544962fa333e2e34ce64f719">Size</a> and <a href="/web-llvm/docs/api/namespaces/llvm/#ac9a23c88949ad27ad62f0ee03254ee3a">llvm::wrap</a>.</p>

</div>
</div>

### LLVMRemarkParserCreateYAML() {#ga67a4d14fa2dd7a2908b0888dc1ffbd8d}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">LLVMRemarkParserRef LLVMRemarkParserCreateYAML (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> void * Buf, uint64_t Size)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Creates a remark parser that can be used to parse the buffer located in <span class="doxyComputerOutput">Buf</span> of size <span class="doxyComputerOutput">Size</span> bytes.</p>


<p><span class="doxyComputerOutput">Buf</span> cannot be <span class="doxyComputerOutput">NULL</span>.</p>


<p>This function should be paired with <a href="#gad7ebecfc91d543900784cb97c6302d47">LLVMRemarkParserDispose()</a> to avoid leaking resources.</p>


<dl class="doxySectionUser">
<dt>Since</dt>
<dd><p>REMARKS_API_VERSION=0</p></dd>
</dl>


<p>Declaration at line 243 of file <a href="/web-llvm/docs/api/files/include/include/llvm-c/remarks-h">Remarks.h</a>, definition at line 130 of file <a href="/web-llvm/docs/api/files/lib/lib/remarks/remarkparser-cpp">RemarkParser.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a>, <a href="#ga67a4d14fa2dd7a2908b0888dc1ffbd8d">LLVMRemarkParserCreateYAML</a>, <a href="/web-llvm/docs/api/files/lib/lib/analysis/inlineorder-cpp/#a7ee6f0cb51c3b9056199e9a0001fe8c3a6f6cb72d544962fa333e2e34ce64f719">Size</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#ac9a23c88949ad27ad62f0ee03254ee3a">llvm::wrap</a> and <a href="/web-llvm/docs/api/namespaces/llvm/remarks/#a6e038f443b9029221c590524f08be0bea9463f87bbed1fcdacfb8d40e185ca2bc">llvm::remarks::YAML</a>.</p>


<p>Referenced by <a href="#ga67a4d14fa2dd7a2908b0888dc1ffbd8d">LLVMRemarkParserCreateYAML</a>.</p>

</div>
</div>

### LLVMRemarkParserDispose() {#gad7ebecfc91d543900784cb97c6302d47}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void LLVMRemarkParserDispose (<a href="#ga8065752effe66fd6b55586f04028cccd">LLVMRemarkParserRef</a> Parser)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Releases all the resources used by <span class="doxyComputerOutput">Parser</span>.</p>


<dl class="doxySectionUser">
<dt>Since</dt>
<dd><p>REMARKS_API_VERSION=0</p></dd>
</dl>


<p>Declaration at line 329 of file <a href="/web-llvm/docs/api/files/include/include/llvm-c/remarks-h">Remarks.h</a>, definition at line 173 of file <a href="/web-llvm/docs/api/files/lib/lib/remarks/remarkparser-cpp">RemarkParser.cpp</a>.</p>


<p>Reference <a href="/web-llvm/docs/api/namespaces/llvm/#aa3d613e3ad429bdb5b1a7d22796028e9">llvm::unwrap</a>.</p>

</div>
</div>

### LLVMRemarkParserGetErrorMessage() {#gab870147e749d296c569783d7539b6656}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">const char * LLVMRemarkParserGetErrorMessage (<a href="#ga8065752effe66fd6b55586f04028cccd">LLVMRemarkParserRef</a> Parser)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Returns a null-terminated string containing an error message.</p>


<p>In case of no error, the result is <span class="doxyComputerOutput">NULL</span>.</p>


<p>The memory of the string is bound to the lifetime of <span class="doxyComputerOutput">Parser</span>. If <a href="#gad7ebecfc91d543900784cb97c6302d47">LLVMRemarkParserDispose()</a> is called, the memory of the string will be released.</p>


<dl class="doxySectionUser">
<dt>Since</dt>
<dd><p>REMARKS_API_VERSION=0</p></dd>
</dl>


<p>Declaration at line 322 of file <a href="/web-llvm/docs/api/files/include/include/llvm-c/remarks-h">Remarks.h</a>, definition at line 169 of file <a href="/web-llvm/docs/api/files/lib/lib/remarks/remarkparser-cpp">RemarkParser.cpp</a>.</p>


<p>Reference <a href="/web-llvm/docs/api/namespaces/llvm/#aa3d613e3ad429bdb5b1a7d22796028e9">llvm::unwrap</a>.</p>

</div>
</div>

### LLVMRemarkParserGetNext() {#gada1d7ab2d57b735d67fa095bc099cc7f}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">LLVMRemarkEntryRef LLVMRemarkParserGetNext (<a href="#ga8065752effe66fd6b55586f04028cccd">LLVMRemarkParserRef</a> Parser)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Returns the next remark in the file.</p>


<p>The value pointed to by the return value needs to be disposed using a call to <a href="#ga4c5e73440d732e43d91a04128fe689de">LLVMRemarkEntryDispose()</a>.</p>


<p>All the entries in the returned value that are of <a href="#ga4029ca629a9c507071bc942d42192ad3">LLVMRemarkStringRef</a> type will become invalidated once a call to LLVMRemarkParserDispose is made.</p>


<p>If the parser reaches the end of the buffer, the return value will be <span class="doxyComputerOutput">NULL</span>.</p>


<p>In the case of an error, the return value will be <span class="doxyComputerOutput">NULL</span>, and:</p>


<p>1) <a href="#ga88083b5d141c27d1dd14dc4d2f0f81a2">LLVMRemarkParserHasError()</a> will return <span class="doxyComputerOutput">1</span>.</p>


<p>2) <a href="#gab870147e749d296c569783d7539b6656">LLVMRemarkParserGetErrorMessage()</a> will return a descriptive error message.</p>


<p>An error may occur if:</p>


<p>1) An argument is invalid.</p>


<p>2) There is a parsing error. This can occur on things like malformed YAML.</p>


<p>3) There is a Remark semantic error. This can occur on well-formed files with missing or extra fields.</p>


<p>Here is a quick example of the usage:</p>


<div class="doxyProgramListing">

<div class="doxyCodeLine"><span class="doxyNoLineNumber">&nbsp;</span><span class="doxyLineContent"><span class="doxyHighlight">LLVMRemarkParserRef Parser = LLVMRemarkParserCreateYAML(Buf, Size);</span></span></div>
<div class="doxyCodeLine"><span class="doxyNoLineNumber">&nbsp;</span><span class="doxyLineContent"><span class="doxyHighlight">LLVMRemarkEntryRef Remark = NULL;</span></span></div>
<div class="doxyCodeLine"><span class="doxyNoLineNumber">&nbsp;</span><span class="doxyLineContent"><span class="doxyHighlight">while ((Remark = LLVMRemarkParserGetNext(Parser))) {</span></span></div>
<div class="doxyCodeLine"><span class="doxyNoLineNumber">&nbsp;</span><span class="doxyLineContent"><span class="doxyHighlight">   // use Remark</span></span></div>
<div class="doxyCodeLine"><span class="doxyNoLineNumber">&nbsp;</span><span class="doxyLineContent"><span class="doxyHighlight">   LLVMRemarkEntryDispose(Remark); // Release memory.</span></span></div>
<div class="doxyCodeLine"><span class="doxyNoLineNumber">&nbsp;</span><span class="doxyLineContent"><span class="doxyHighlight">}</span></span></div>
<div class="doxyCodeLine"><span class="doxyNoLineNumber">&nbsp;</span><span class="doxyLineContent"><span class="doxyHighlight">bool HasError = LLVMRemarkParserHasError(Parser);</span></span></div>
<div class="doxyCodeLine"><span class="doxyNoLineNumber">&nbsp;</span><span class="doxyLineContent"><span class="doxyHighlight">LLVMRemarkParserDispose(Parser);</span></span></div>

</div>


<dl class="doxySectionUser">
<dt>Since</dt>
<dd><p>REMARKS_API_VERSION=0</p></dd>
</dl>


<p>Declaration at line 302 of file <a href="/web-llvm/docs/api/files/include/include/llvm-c/remarks-h">Remarks.h</a>, definition at line 143 of file <a href="/web-llvm/docs/api/files/lib/lib/remarks/remarkparser-cpp">RemarkParser.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/namespaces/llvm/#aee0e70be66536b9ef7b65ae2e5a45959">llvm::consumeError</a>, <a href="/web-llvm/docs/api/files/lib/lib/ir/builtingcs-cpp/#abb2b3a60ccc38a28239e19a1646e0c8a">E</a>, <a href="/web-llvm/docs/api/structs/llvm/remarks/remarkparser/#af41ce5d552a2f97ed547661bcee5c26e">llvm::remarks::RemarkParser::next</a>, <a href="/web-llvm/docs/api/classes/llvm/expected/#a94789df4ebd03dc008e8adebaa66ac1f">llvm::Expected&lt; T &gt;::takeError</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#aa3d613e3ad429bdb5b1a7d22796028e9">llvm::unwrap</a> and <a href="/web-llvm/docs/api/namespaces/llvm/#ac9a23c88949ad27ad62f0ee03254ee3a">llvm::wrap</a>.</p>

</div>
</div>

### LLVMRemarkParserHasError() {#ga88083b5d141c27d1dd14dc4d2f0f81a2}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">LLVMBool LLVMRemarkParserHasError (<a href="#ga8065752effe66fd6b55586f04028cccd">LLVMRemarkParserRef</a> Parser)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Returns <span class="doxyComputerOutput">1</span> if the parser encountered an error while parsing the buffer.</p>


<dl class="doxySectionUser">
<dt>Since</dt>
<dd><p>REMARKS_API_VERSION=0</p></dd>
</dl>


<p>Declaration at line 309 of file <a href="/web-llvm/docs/api/files/include/include/llvm-c/remarks-h">Remarks.h</a>, definition at line 164 of file <a href="/web-llvm/docs/api/files/lib/lib/remarks/remarkparser-cpp">RemarkParser.cpp</a>.</p>


<p>Reference <a href="/web-llvm/docs/api/namespaces/llvm/#aa3d613e3ad429bdb5b1a7d22796028e9">llvm::unwrap</a>.</p>

</div>
</div>

### LLVMRemarkStringGetData() {#ga0486d7fbdef367b47c2f6c2edbfaac16}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">const char * LLVMRemarkStringGetData (<a href="#ga4029ca629a9c507071bc942d42192ad3">LLVMRemarkStringRef</a> String)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Returns the buffer holding the string.</p>


<dl class="doxySectionUser">
<dt>Since</dt>
<dd><p>REMARKS_API_VERSION=0</p></dd>
</dl>


<p>Declaration at line 64 of file <a href="/web-llvm/docs/api/files/include/include/llvm-c/remarks-h">Remarks.h</a>, definition at line 69 of file <a href="/web-llvm/docs/api/files/lib/lib/remarks/remark-cpp">Remark.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a>, <a href="#ga0486d7fbdef367b47c2f6c2edbfaac16">LLVMRemarkStringGetData</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#ac226f3d2b9ca090171a8e0a8cb92c343a27118326006d3829667a400ad23d5d98">llvm::String</a> and <a href="/web-llvm/docs/api/namespaces/llvm/#aa3d613e3ad429bdb5b1a7d22796028e9">llvm::unwrap</a>.</p>


<p>Referenced by <a href="#ga0486d7fbdef367b47c2f6c2edbfaac16">LLVMRemarkStringGetData</a>.</p>

</div>
</div>

### LLVMRemarkStringGetLen() {#ga0f362b5544af2faeb2e8f501502a49bc}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">uint32_t LLVMRemarkStringGetLen (<a href="#ga4029ca629a9c507071bc942d42192ad3">LLVMRemarkStringRef</a> String)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Returns the size of the string.</p>


<dl class="doxySectionUser">
<dt>Since</dt>
<dd><p>REMARKS_API_VERSION=0</p></dd>
</dl>


<p>Declaration at line 71 of file <a href="/web-llvm/docs/api/files/include/include/llvm-c/remarks-h">Remarks.h</a>, definition at line 73 of file <a href="/web-llvm/docs/api/files/lib/lib/remarks/remark-cpp">Remark.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/namespaces/llvm/#ac226f3d2b9ca090171a8e0a8cb92c343a27118326006d3829667a400ad23d5d98">llvm::String</a> and <a href="/web-llvm/docs/api/namespaces/llvm/#aa3d613e3ad429bdb5b1a7d22796028e9">llvm::unwrap</a>.</p>

</div>
</div>

### LLVMRemarkVersion() {#ga0369399b76ee94ed8e63cbccf07d08d6}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">uint32_t LLVMRemarkVersion (void)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Returns the version of the remarks library.</p>


<dl class="doxySectionUser">
<dt>Since</dt>
<dd><p>REMARKS_API_VERSION=0</p></dd>
</dl>


<p>Definition at line 336 of file <a href="/web-llvm/docs/api/files/include/include/llvm-c/remarks-h">Remarks.h</a>.</p>


<p>Reference <a href="/web-llvm/docs/api/files/include/include/llvm-c/externc-h/#ae016a3733553fe3990c8dfcec10d9d3a">LLVM_C_EXTERN_C_END</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Macro Definitions

### REMARKS\_API\_VERSION {#gac93670c4f16d0779764ce0776b240c1c}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">#define REMARKS_API_VERSION&nbsp;&nbsp;&nbsp;1</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 36 of file <a href="/web-llvm/docs/api/files/include/include/llvm-c/remarks-h">Remarks.h</a>.</p>

</div>
</div>

</div>

<hr/>

<p class="doxyGeneratedBy">Generated via <a href="https://github.com/xpack/doxygen2docusaurus">doxygen2docusaurus</a> by <a href="https://www.doxygen.nl">Doxygen</a> 1.14.0.</p>

</div>
