---

# DO NOT EDIT!
# Automatically generated via doxygen2docusaurus by Doxygen.

slug: /api/files/lib/lib/support/regfree-c
custom_edit_url: null
toc_max_heading_level: 4
keywords:
  - doxygen
  - reference
  - file

---

<div class="doxyPage">

# The `regfree.c` File Reference



## Included Headers

<div class="doxyIncludesList">#include &lt;sys/types.h&gt;
#include &lt;stdio.h&gt;
#include &lt;stdlib.h&gt;
#include "<a href="/web-llvm/docs/api/files/lib/lib/support/regex-impl-h">regex_impl.h</a>"
#include "<a href="/web-llvm/docs/api/files/lib/lib/support/regutils-h">regutils.h</a>"
#include "<a href="/web-llvm/docs/api/files/lib/lib/support/regex2-h">regex2.h</a>"
</div>

## Functions Index

<table class="doxyMembersIndex">

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">void</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ad2dfee836b7a3af7b31d061df0c90b8b">llvm_regfree</a> (llvm_regex_t *preg)</td>
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

### llvm\_regfree() {#ad2dfee836b7a3af7b31d061df0c90b8b}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void llvm_regfree (<a href="/web-llvm/docs/api/files/lib/lib/support/regex-impl-h/#a14d8a63433f444e7352b4e931cf33335">llvm_regex_t</a> * preg)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 50 of file <a href="/web-llvm/docs/api/files/lib/lib/support/regfree-c">regfree.c</a>.</p>


<p>References <a href="/web-llvm/docs/api/files/lib/lib/support/lib/support/blake3/blake3-portable-c/#ab5958fad499ed692422c66bb20000a39">g</a>, <a href="/web-llvm/docs/api/files/lib/lib/support/regex2-h/#ac77db84cf42ba546550a69ac744c14ff">MAGIC1</a>, <a href="/web-llvm/docs/api/files/lib/lib/support/regex2-h/#ade86ed2c7955ab1d3b4b4d84f7df8524">MAGIC2</a>, <a href="/web-llvm/docs/api/structs/llvm-regex/#a21d425d48e65f2408ccadde7ec358bf7">llvm_regex::re_g</a> and <a href="/web-llvm/docs/api/structs/llvm-regex/#a1a96d03c57ddbbacd6bd4f5e587ce558">llvm_regex::re_magic</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/files/lib/lib/support/regcomp-c/#a94efd6ce730ab2988bfd211af4319873">llvm_regcomp</a> and <a href="/web-llvm/docs/api/classes/llvm/regex/#a4b32acda8c0843ee5a68ebccba4ad993">llvm::Regex::~Regex</a>.</p>

</div>
</div>

</div>

<hr/>

<p class="doxyGeneratedBy">Generated via <a href="https://github.com/xpack/doxygen2docusaurus">doxygen2docusaurus</a> by <a href="https://www.doxygen.nl">Doxygen</a> 1.15.0.</p>

</div>
