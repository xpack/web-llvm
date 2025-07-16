---

# DO NOT EDIT!
# Automatically generated via doxygen2docusaurus by Doxygen.

slug: /api/files/lib/lib/support/graphwriter-cpp
custom_edit_url: null
toc_max_heading_level: 4
keywords:
  - doxygen
  - reference
  - file

---

<div class="doxyPage">

# The `GraphWriter.cpp` File Reference



## Included Headers

<div class="doxyIncludesList">#include "<a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/support/graphwriter-h">llvm/Support/GraphWriter.h</a>"
#include "<a href="/web-llvm/docs/api/files/lib/lib/support/debugoptions-h">DebugOptions.h</a>"
#include "<a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/adt/smallstring-h">llvm/ADT/SmallString.h</a>"
#include "<a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/adt/smallvector-h">llvm/ADT/SmallVector.h</a>"
#include "<a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/adt/stringref-h">llvm/ADT/StringRef.h</a>"
#include "llvm/Config/config.h"
#include "<a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/support/compiler-h">llvm/Support/Compiler.h</a>"
#include "<a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/support/errorhandling-h">llvm/Support/ErrorHandling.h</a>"
#include "<a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/support/erroror-h">llvm/Support/ErrorOr.h</a>"
#include "<a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/support/filesystem-h">llvm/Support/FileSystem.h</a>"
#include "<a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/support/path-h">llvm/Support/Path.h</a>"
#include "<a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/support/program-h">llvm/Support/Program.h</a>"
#include "<a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/support/raw-ostream-h">llvm/Support/raw_ostream.h</a>"
#include &lt;string&gt;
#include &lt;system_error&gt;
#include &lt;vector&gt;
</div>

## Namespaces Index

<table class="doxyMembersIndex">

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">namespace</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="/web-llvm/docs/api/namespaces/anonymous-graphwriter-cpp-">anonymous{GraphWriter.cpp}</a></td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="/web-llvm/docs/api/structs/anonymous-graphwriter-cpp-/graphsession">GraphSession</a></td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">static <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/demangle/itaniumdemangle-h/#ae2b0d0345572d6718e219aa76d1d54edab45cffe084dd3d20d928bee85e7b0f21">std::string</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a5459e2bb88199b215a3b8f2007464cf2">replaceIllegalFilenameChars</a> (std::string Filename, const char ReplacementChar)</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">static bool</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a757cbab3b98663245aad227dc16be58b">ExecGraphViewer</a> (StringRef ExecPath, std::vector&lt; StringRef &gt; &amp;args, StringRef Filename, bool wait, std::string &amp;ErrMsg)</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">static <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> char *</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a9951c360627b9478493739a9b96a4b20">getProgramName</a> (GraphProgram::Name program)</td>
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

## Functions

### ExecGraphViewer() {#a757cbab3b98663245aad227dc16be58b}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool ExecGraphViewer (<a href="/web-llvm/docs/api/classes/llvm/stringref">StringRef</a> ExecPath, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/amdgpupromotealloca-cpp/#ac760e37eba1d852d0a28011a1a0ce05f">std::vector</a>&lt; <a href="/web-llvm/docs/api/classes/llvm/stringref">StringRef</a> &gt; &amp; args, <a href="/web-llvm/docs/api/classes/llvm/stringref">StringRef</a> Filename, bool wait, <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/demangle/itaniumdemangle-h/#ae2b0d0345572d6718e219aa76d1d54edab45cffe084dd3d20d928bee85e7b0f21">std::string</a> &amp; ErrMsg)</td>
</tr>
</table>
</td>
<td class="doxyMemberLabelsRight">
<span class="doxyMemberLabels">
<span class="doxyMemberLabel static">static</span>
</span>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 137 of file <a href="/web-llvm/docs/api/files/lib/lib/support/graphwriter-cpp">GraphWriter.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/nvptx/nvptxlowerargs-cpp/#a4d6da696b3c753c5e5fbcc4d21d4cb71">args</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a9a7b5c68c90f85baaedaa854cc5002cc">llvm::errs</a>, <a href="/web-llvm/docs/api/namespaces/llvm/sys/#abb13fbc7f52c659966b05092b19e6e19">llvm::sys::ExecuteAndWait</a>, <a href="/web-llvm/docs/api/namespaces/llvm/sys/#a76fe26a8f1401a60839398dedb2f170c">llvm::sys::ExecuteNoWait</a> and <a href="/web-llvm/docs/api/namespaces/llvm/sys/fs/#a921e0b01f22f9a37012450f9b5f0ccb7">llvm::sys::fs::remove</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/namespaces/llvm/#a2ac93a817bcb1ef2549c8e737866b7a3">llvm::DisplayGraph</a>.</p>

</div>
</div>

### getProgramName() {#a9951c360627b9478493739a9b96a4b20}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">const char * getProgramName (<a href="/web-llvm/docs/api/namespaces/llvm/graphprogram/#a0ad4685976f8c4d4a697a53fbe05d10b">GraphProgram::Name</a> program)</td>
</tr>
</table>
</td>
<td class="doxyMemberLabelsRight">
<span class="doxyMemberLabels">
<span class="doxyMemberLabel static">static</span>
</span>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 176 of file <a href="/web-llvm/docs/api/files/lib/lib/support/graphwriter-cpp">GraphWriter.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/namespaces/llvm/graphprogram/#a0ad4685976f8c4d4a697a53fbe05d10bab89542c270041afd91cb19369af6dc31">llvm::GraphProgram::CIRCO</a>, <a href="/web-llvm/docs/api/namespaces/llvm/graphprogram/#a0ad4685976f8c4d4a697a53fbe05d10baa979410a6f3129644e1be86fb488e455">llvm::GraphProgram::DOT</a>, <a href="/web-llvm/docs/api/namespaces/llvm/graphprogram/#a0ad4685976f8c4d4a697a53fbe05d10ba369c1aafe1a79637a098d1ac61c3c940">llvm::GraphProgram::FDP</a>, <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/support/errorhandling-h/#ace243f5c25697a1107cce46626b3dc94">llvm_unreachable</a>, <a href="/web-llvm/docs/api/namespaces/llvm/graphprogram/#a0ad4685976f8c4d4a697a53fbe05d10ba5f97d56ae6699c2775313a0b5cd6badb">llvm::GraphProgram::NEATO</a> and <a href="/web-llvm/docs/api/namespaces/llvm/graphprogram/#a0ad4685976f8c4d4a697a53fbe05d10ba3af922b814bd0960a3c12abbe6b87a0d">llvm::GraphProgram::TWOPI</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/namespaces/llvm/#a2ac93a817bcb1ef2549c8e737866b7a3">llvm::DisplayGraph</a>.</p>

</div>
</div>

### replaceIllegalFilenameChars() {#a5459e2bb88199b215a3b8f2007464cf2}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">std::string replaceIllegalFilenameChars (<a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/demangle/itaniumdemangle-h/#ae2b0d0345572d6718e219aa76d1d54edab45cffe084dd3d20d928bee85e7b0f21">std::string</a> Filename, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> char ReplacementChar)</td>
</tr>
</table>
</td>
<td class="doxyMemberLabelsRight">
<span class="doxyMemberLabels">
<span class="doxyMemberLabel static">static</span>
</span>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 100 of file <a href="/web-llvm/docs/api/files/lib/lib/support/graphwriter-cpp">GraphWriter.cpp</a>.</p>


<p>Reference <a href="/web-llvm/docs/api/namespaces/llvm/sys/path/#a58cfd8a47c0ef96db27b451c2d6ec49fa8e5f3adee38c8fccc13c1f3be0143796">llvm::sys::path::native</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/namespaces/llvm/#a987f18f3591a74415a00f67b0fafe2ef">llvm::createGraphFilename</a>.</p>

</div>
</div>

</div>

<hr/>

<p class="doxyGeneratedBy">Generated via <a href="https://github.com/xpack/doxygen2docusaurus">doxygen2docusaurus</a> by <a href="https://www.doxygen.nl">Doxygen</a> 1.15.0.</p>

</div>
