---

# DO NOT EDIT!
# Automatically generated via doxygen2docusaurus by Doxygen.

slug: /api/groups/llvmccoreirreader
custom_edit_url: null
toc_max_heading_level: 4
keywords:
  - doxygen
  - reference
  - group

---

<div class="doxyPage">

# The IR Reader Reference



## Functions Index

<table class="doxyMembersIndex">

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/groups/llvmcsupporttypes/#ga209de0bceb13179a973c6a45211617bd">LLVMBool</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ga319e4562ffb47ec6eba2eb70ffdbaa37">LLVMParseIRInContext</a> (LLVMContextRef ContextRef, LLVMMemoryBufferRef MemBuf, LLVMModuleRef *OutM, char **OutMessage)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Read LLVM IR from a memory buffer and convert it into an in-memory Module object. <a href="#ga319e4562ffb47ec6eba2eb70ffdbaa37">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

</table>


<div class="doxySectionDef">

## Functions

### LLVMParseIRInContext() {#ga319e4562ffb47ec6eba2eb70ffdbaa37}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">LLVMBool LLVMParseIRInContext (<a href="/web-llvm/docs/api/groups/llvmcsupporttypes/#ga9c43e01525516ff6b4feab5166c5b1da">LLVMContextRef</a> ContextRef, <a href="/web-llvm/docs/api/groups/llvmcsupporttypes/#ga9867eaa7b17ba17405cdf2539bedb108">LLVMMemoryBufferRef</a> MemBuf, <a href="/web-llvm/docs/api/groups/llvmcsupporttypes/#gad1d1bb5f901c903a0cf09c5a053c9c56">LLVMModuleRef</a> * OutM, char ** OutMessage)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Read LLVM IR from a memory buffer and convert it into an in-memory Module object.</p>


<p>Returns 0 on success. Optionally returns a human-readable description of any errors that occurred during parsing IR. OutMessage must be disposed with LLVMDisposeMessage.</p>


<dl class="doxySectionUser">
<dt>See Also</dt>
<dd><p>llvm::ParseIR()</p></dd>
</dl>


<p>Declaration at line 38 of file <a href="/web-llvm/docs/api/files/include/include/llvm-c/irreader-h">IRReader.h</a>, definition at line 112 of file <a href="/web-llvm/docs/api/files/lib/lib/irreader/irreader-cpp">IRReader.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/namespaces/llvm/#a8b04365fc31f28e28e484d2f3cba05f1">llvm::parseIR</a>, <a href="/web-llvm/docs/api/classes/llvm/smdiagnostic/#a0653e9bbc6598528d50ec97cad565b74">llvm::SMDiagnostic::print</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a650dea4533083a886cec9f16d80356d9a123fead50246387983ee340507115ef4">llvm::release</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#aa3d613e3ad429bdb5b1a7d22796028e9">llvm::unwrap</a> and <a href="/web-llvm/docs/api/namespaces/llvm/#ac9a23c88949ad27ad62f0ee03254ee3a">llvm::wrap</a>.</p>

</div>
</div>

</div>

<hr/>

<p class="doxyGeneratedBy">Generated via <a href="https://github.com/xpack/doxygen2docusaurus">doxygen2docusaurus</a> by <a href="https://www.doxygen.nl">Doxygen</a> 1.14.0.</p>

</div>
