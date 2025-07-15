---

# DO NOT EDIT!
# Automatically generated via doxygen2docusaurus by Doxygen.

slug: /api/groups/llvmcbitwriter
custom_edit_url: null
toc_max_heading_level: 4
keywords:
  - doxygen
  - reference
  - group

---

<div class="doxyPage">

# The Bit Writer Reference



## Functions Index

<table class="doxyMembersIndex">

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">int</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ga10b86ad44bcad46fcf80cc525949703d">LLVMWriteBitcodeToFile</a> (LLVMModuleRef M, const char *Path)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Writes a module to the specified path. <a href="#ga10b86ad44bcad46fcf80cc525949703d">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">int</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ga75ab6d85381957cd9c487b4bd1069bce">LLVMWriteBitcodeToFD</a> (LLVMModuleRef M, int FD, int ShouldClose, int Unbuffered)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Writes a module to an open file descriptor. <a href="#ga75ab6d85381957cd9c487b4bd1069bce">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">int</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ga265dfc97cc8af15a31cf876a107fb7d0">LLVMWriteBitcodeToFileHandle</a> (LLVMModuleRef M, int Handle)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Deprecated for LLVMWriteBitcodeToFD. <a href="#ga265dfc97cc8af15a31cf876a107fb7d0">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/groups/llvmcsupporttypes/#ga9867eaa7b17ba17405cdf2539bedb108">LLVMMemoryBufferRef</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ga43cccd6ab4fe5c042fc59d972430c97f">LLVMWriteBitcodeToMemoryBuffer</a> (LLVMModuleRef M)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Writes a module to a new memory buffer and returns it. <a href="#ga43cccd6ab4fe5c042fc59d972430c97f">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

</table>


<div class="doxySectionDef">

## Functions

### LLVMWriteBitcodeToFD() {#ga75ab6d85381957cd9c487b4bd1069bce}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">int LLVMWriteBitcodeToFD (<a href="/web-llvm/docs/api/groups/llvmcsupporttypes/#gad1d1bb5f901c903a0cf09c5a053c9c56">LLVMModuleRef</a> M, int FD, int ShouldClose, int Unbuffered)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Writes a module to an open file descriptor.</p>


<p>Returns 0 on success.</p>


<p>Declaration at line 40 of file <a href="/web-llvm/docs/api/files/include/include/llvm-c/bitwriter-h">BitWriter.h</a>, definition at line 31 of file <a href="/web-llvm/docs/api/files/lib/lib/bitcode/lib/bitcode/writer/bitwriter-cpp">BitWriter.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/namespaces/llvm/#aa3d613e3ad429bdb5b1a7d22796028e9">llvm::unwrap</a> and <a href="/web-llvm/docs/api/namespaces/llvm/#a199eb3a521b35ac20b20b7460bf2dabb">llvm::WriteBitcodeToFile</a>.</p>


<p>Referenced by <a href="#ga265dfc97cc8af15a31cf876a107fb7d0">LLVMWriteBitcodeToFileHandle</a>.</p>

</div>
</div>

### LLVMWriteBitcodeToFile() {#ga10b86ad44bcad46fcf80cc525949703d}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">int LLVMWriteBitcodeToFile (<a href="/web-llvm/docs/api/groups/llvmcsupporttypes/#gad1d1bb5f901c903a0cf09c5a053c9c56">LLVMModuleRef</a> M, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> char * Path)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Writes a module to the specified path.</p>


<p>Returns 0 on success.</p>


<p>Declaration at line 37 of file <a href="/web-llvm/docs/api/files/include/include/llvm-c/bitwriter-h">BitWriter.h</a>, definition at line 20 of file <a href="/web-llvm/docs/api/files/lib/lib/bitcode/lib/bitcode/writer/bitwriter-cpp">BitWriter.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/namespaces/llvm/sys/fs/#a662978c0cdf81de0d448032f142a3695a8ae6a0a158ab49e5bbe92cbc2cabcbcd">llvm::sys::fs::OF_None</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#aa3d613e3ad429bdb5b1a7d22796028e9">llvm::unwrap</a> and <a href="/web-llvm/docs/api/namespaces/llvm/#a199eb3a521b35ac20b20b7460bf2dabb">llvm::WriteBitcodeToFile</a>.</p>

</div>
</div>

### LLVMWriteBitcodeToFileHandle() {#ga265dfc97cc8af15a31cf876a107fb7d0}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">int LLVMWriteBitcodeToFileHandle (<a href="/web-llvm/docs/api/groups/llvmcsupporttypes/#gad1d1bb5f901c903a0cf09c5a053c9c56">LLVMModuleRef</a> M, int Handle)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Deprecated for LLVMWriteBitcodeToFD.</p>


<p>Writes a module to an open file descriptor. Returns 0 on success. Closes the Handle.</p>


<p>Declaration at line 45 of file <a href="/web-llvm/docs/api/files/include/include/llvm-c/bitwriter-h">BitWriter.h</a>, definition at line 39 of file <a href="/web-llvm/docs/api/files/lib/lib/bitcode/lib/bitcode/writer/bitwriter-cpp">BitWriter.cpp</a>.</p>


<p>Reference <a href="#ga75ab6d85381957cd9c487b4bd1069bce">LLVMWriteBitcodeToFD</a>.</p>

</div>
</div>

### LLVMWriteBitcodeToMemoryBuffer() {#ga43cccd6ab4fe5c042fc59d972430c97f}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">LLVMMemoryBufferRef LLVMWriteBitcodeToMemoryBuffer (<a href="/web-llvm/docs/api/groups/llvmcsupporttypes/#gad1d1bb5f901c903a0cf09c5a053c9c56">LLVMModuleRef</a> M)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Writes a module to a new memory buffer and returns it.</p>

<p>Declaration at line 48 of file <a href="/web-llvm/docs/api/files/include/include/llvm-c/bitwriter-h">BitWriter.h</a>, definition at line 43 of file <a href="/web-llvm/docs/api/files/lib/lib/bitcode/lib/bitcode/writer/bitwriter-cpp">BitWriter.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/namespaces/llvm/#aa20539e89704d20b98b97e9c3feac934">llvm::Data</a>, <a href="/web-llvm/docs/api/classes/llvm/memorybuffer/#a32d2c9ba9019e6e41605c60acd06bd09">llvm::MemoryBuffer::getMemBufferCopy</a>, <a href="/web-llvm/docs/api/classes/llvm/raw-string-ostream/#a6732e8d3ff8100a662ce73634840b990">llvm::raw_string_ostream::str</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#aa3d613e3ad429bdb5b1a7d22796028e9">llvm::unwrap</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#ac9a23c88949ad27ad62f0ee03254ee3a">llvm::wrap</a> and <a href="/web-llvm/docs/api/namespaces/llvm/#a199eb3a521b35ac20b20b7460bf2dabb">llvm::WriteBitcodeToFile</a>.</p>

</div>
</div>

</div>

<hr/>

<p class="doxyGeneratedBy">Generated via <a href="https://github.com/xpack/doxygen2docusaurus">doxygen2docusaurus</a> by <a href="https://www.doxygen.nl">Doxygen</a> 1.14.0.</p>

</div>
