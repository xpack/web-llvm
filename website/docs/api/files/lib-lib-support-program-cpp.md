---

# DO NOT EDIT!
# Automatically generated via doxygen2docusaurus by Doxygen.

slug: /api/files/lib/lib/support/program-cpp
custom_edit_url: null
toc_max_heading_level: 4
keywords:
  - doxygen
  - reference
  - file

---

<div class="doxyPage">

# The `Program.cpp` File Reference



## Included Headers

<div class="doxyIncludesList">#include "<a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/support/program-h">llvm/Support/Program.h</a>"
#include "<a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/adt/stringref-h">llvm/ADT/StringRef.h</a>"
#include "llvm/Config/llvm-config.h"
#include "<a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/support/raw-ostream-h">llvm/Support/raw_ostream.h</a>"
#include "Unix/Program.inc"
</div>

## Functions Index

<table class="doxyMembersIndex">

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">static bool</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a3cc4767a85e498eea6b41bfbbdb4d2e9">Execute</a> (ProcessInfo &amp;PI, StringRef Program, ArrayRef&lt; StringRef &gt; Args, std::optional&lt; ArrayRef&lt; StringRef &gt; &gt; Env, ArrayRef&lt; std::optional&lt; StringRef &gt; &gt; Redirects, unsigned MemoryLimit, std::string *ErrMsg, BitVector *AffinityMask, bool DetachProcess)</td>
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

### Execute() {#a3cc4767a85e498eea6b41bfbbdb4d2e9}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool Execute (<a href="/web-llvm/docs/api/structs/llvm/sys/processinfo">ProcessInfo</a> &amp; PI, <a href="/web-llvm/docs/api/classes/llvm/stringref">StringRef</a> Program, <a href="/web-llvm/docs/api/classes/llvm/arrayref">ArrayRef</a>&lt; <a href="/web-llvm/docs/api/classes/llvm/stringref">StringRef</a> &gt; Args, std::optional&lt; <a href="/web-llvm/docs/api/classes/llvm/arrayref">ArrayRef</a>&lt; <a href="/web-llvm/docs/api/classes/llvm/stringref">StringRef</a> &gt; &gt; Env, <a href="/web-llvm/docs/api/classes/llvm/arrayref">ArrayRef</a>&lt; std::optional&lt; <a href="/web-llvm/docs/api/classes/llvm/stringref">StringRef</a> &gt; &gt; Redirects, unsigned MemoryLimit, <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/demangle/itaniumdemangle-h/#ae2b0d0345572d6718e219aa76d1d54edab45cffe084dd3d20d928bee85e7b0f21">std::string</a> * ErrMsg, <a href="/web-llvm/docs/api/classes/llvm/bitvector">BitVector</a> * AffinityMask, bool DetachProcess)</td>
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



<p>Definition at line 25 of file <a href="/web-llvm/docs/api/files/lib/lib/support/program-cpp">Program.cpp</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/classes/llvm/logicalview/lvoptions/#a556875654ed3dfbb90a82a57c242d59b">llvm::logicalview::LVOptions::BOOL_FUNCTION</a>, <a href="/web-llvm/docs/api/classes/llvm/logicalview/lvoptions/#afdd8c40716080674601c24a8febca1d1">llvm::logicalview::LVOptions::BOOL_FUNCTION</a>, <a href="/web-llvm/docs/api/classes/llvm/logicalview/lvoptions/#a974130b725649fbbfafc84ddeef25e9d">llvm::logicalview::LVOptions::BOOL_FUNCTION</a>, <a href="/web-llvm/docs/api/classes/llvm/logicalview/lvoptions/#a231878b3485b57af5ee9ac2374b8e2f6">llvm::logicalview::LVOptions::BOOL_FUNCTION</a>, <a href="/web-llvm/docs/api/classes/llvm/mca/context/#ae59a559d2474039c4dfb540996e84d42">llvm::mca::Context::createDefaultPipeline</a>, <a href="/web-llvm/docs/api/namespaces/llvm/sys/#abb13fbc7f52c659966b05092b19e6e19">llvm::sys::ExecuteAndWait</a> and <a href="/web-llvm/docs/api/namespaces/llvm/sys/#a76fe26a8f1401a60839398dedb2f170c">llvm::sys::ExecuteNoWait</a>.</p>

</div>
</div>

</div>

<hr/>

<p class="doxyGeneratedBy">Generated via <a href="https://github.com/xpack/doxygen2docusaurus">doxygen2docusaurus</a> by <a href="https://www.doxygen.nl">Doxygen</a> 1.15.0.</p>

</div>
