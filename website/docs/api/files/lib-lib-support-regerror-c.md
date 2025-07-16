---

# DO NOT EDIT!
# Automatically generated via doxygen2docusaurus by Doxygen.

slug: /api/files/lib/lib/support/regerror-c
custom_edit_url: null
toc_max_heading_level: 4
keywords:
  - doxygen
  - reference
  - file

---

<div class="doxyPage">

# The `regerror.c` File Reference



## Included Headers

<div class="doxyIncludesList">#include &lt;sys/types.h&gt;
#include &lt;stdio.h&gt;
#include &lt;string.h&gt;
#include &lt;ctype.h&gt;
#include &lt;limits.h&gt;
#include &lt;stdlib.h&gt;
#include "<a href="/web-llvm/docs/api/files/lib/lib/support/regex-impl-h">regex_impl.h</a>"
#include "<a href="/web-llvm/docs/api/files/lib/lib/support/regutils-h">regutils.h</a>"
</div>

## Classes Index

<table class="doxyMembersIndex">

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">struct</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="/web-llvm/docs/api/structs/rerr">rerr</a></td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">static <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> char *</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#af481b7e4615b89b40883ff6f7f60bafd">regatoi</a> (const llvm_regex_t *, char *, int)</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">size_t</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a728104a5963c78e214c7b847b338ad55">llvm_regerror</a> (int errcode, const llvm_regex_t *preg, char *errbuf, size_t errbuf_size)</td>
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

## Variables Index

<table class="doxyMembersIndex">

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">struct { ... }</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a3163e0fa575d4c1b102ac71ea9454896">rerrs</a>[] = ...</td>
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

### llvm\_regerror() {#a728104a5963c78e214c7b847b338ad55}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">size_t llvm_regerror (int errcode, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/files/lib/lib/support/regex-impl-h/#a14d8a63433f444e7352b4e931cf33335">llvm_regex_t</a> * preg, char * errbuf, size_t errbuf_size)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 84 of file <a href="/web-llvm/docs/api/files/lib/lib/support/regerror-c">regerror.c</a>.</p>


<p>References <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/silowercontrolflow-cpp/#a4868c5d81c5ccc98c47aeab6244346a0">assert</a>, <a href="/web-llvm/docs/api/structs/rerr/#a0bbc574398805ac6226a74745d8a8215">rerr::code</a>, <a href="/web-llvm/docs/api/structs/rerr/#a00db6e0c7d6449af27fff2afdb4155ea">rerr::explain</a>, <a href="/web-llvm/docs/api/files/lib/lib/support/regex-impl-h/#a0665f8b90af5f30c518451a34a94e0aa">llvm_strlcpy</a>, <a href="/web-llvm/docs/api/structs/rerr/#a2f69e340c9f6404032c5f9d5ea84245b">rerr::name</a>, <a href="/web-llvm/docs/api/files/lib/lib/support/regex-impl-h/#a527188d8a22e439dd6dfa7d909815611">REG_ATOI</a>, <a href="/web-llvm/docs/api/files/lib/lib/support/regex-impl-h/#a2a2cc83a1e03c9821465885213d5af5b">REG_ITOA</a>, <a href="#af481b7e4615b89b40883ff6f7f60bafd">regatoi</a> and <a href="#a3163e0fa575d4c1b102ac71ea9454896">rerrs</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/namespaces/anonymous-regex-cpp-/#a2cf0de01ea6bd871ff2bc908265cb0f0">anonymous{Regex.cpp}::RegexErrorToString</a>.</p>

</div>
</div>

### regatoi() {#af481b7e4615b89b40883ff6f7f60bafd}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">const char * regatoi (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/files/lib/lib/support/regex-impl-h/#a14d8a63433f444e7352b4e931cf33335">llvm_regex_t</a> * preg, char * localbuf, int localbufsize)</td>
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



<p>Definition at line 123 of file <a href="/web-llvm/docs/api/files/lib/lib/support/regerror-c">regerror.c</a>.</p>


<p>References <a href="/web-llvm/docs/api/structs/rerr/#a0bbc574398805ac6226a74745d8a8215">rerr::code</a>, <a href="/web-llvm/docs/api/structs/rerr/#a2f69e340c9f6404032c5f9d5ea84245b">rerr::name</a>, <a href="/web-llvm/docs/api/structs/llvm-regex/#af5da3516ebe39b7fe40315175d49b55a">llvm_regex::re_endp</a> and <a href="#a3163e0fa575d4c1b102ac71ea9454896">rerrs</a>.</p>


<p>Referenced by <a href="#a728104a5963c78e214c7b847b338ad55">llvm_regerror</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Variables

### rerrs {#a3163e0fa575d4c1b102ac71ea9454896}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">struct rerr rerrs[]</td>
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



<dl class="doxySectionUser">
<dt>Initialiser</dt>
<dd>
<div class="doxyVerbatim">= {
	{ <a href="/web-llvm/docs/api/files/lib/lib/support/regex-impl-h/#a183aab34192b1bdc18a56e84759aa210">REG_NOMATCH</a>,	"REG_NOMATCH",	"llvm_regexec() failed to match" },
	{ <a href="/web-llvm/docs/api/files/lib/lib/support/regex-impl-h/#ad7e13616a54be821d6b686d8b2587401">REG_BADPAT</a>,	"REG_BADPAT",	"invalid regular expression" },
	{ <a href="/web-llvm/docs/api/files/lib/lib/support/regex-impl-h/#ac8233bd7398fdb236c8dadf7abebb8a3">REG_ECOLLATE</a>,	"REG_ECOLLATE",	"invalid collating element" },
	{ <a href="/web-llvm/docs/api/files/lib/lib/support/regex-impl-h/#a16d4f054978e6b70c2672145435a7917">REG_ECTYPE</a>,	"REG_ECTYPE",	"invalid character class" },
	{ <a href="/web-llvm/docs/api/files/lib/lib/support/regex-impl-h/#a3c04bdcb329fb937154b2b47b2c0c2e0">REG_EESCAPE</a>,	"REG_EESCAPE",	"trailing backslash (\\)" },
	{ REG_ESUBREG,	"REG_ESUBREG",	"invalid backreference number" },
	{ <a href="/web-llvm/docs/api/files/lib/lib/support/regex-impl-h/#a1e0ef4e0e9d4b184f1b21285cee16c81">REG_EBRACK</a>,	"REG_EBRACK",	"brackets ([ ]) not balanced" },
	{ <a href="/web-llvm/docs/api/files/lib/lib/support/regex-impl-h/#ad059816a7c4eb7e2193aadc66627a976">REG_EPAREN</a>,	"REG_EPAREN",	"parentheses not balanced" },
	{ <a href="/web-llvm/docs/api/files/lib/lib/support/regex-impl-h/#ad0065762ae9d5301a00eddb6242f104b">REG_EBRACE</a>,	"REG_EBRACE",	"braces not balanced" },
	{ <a href="/web-llvm/docs/api/files/lib/lib/support/regex-impl-h/#aa4693ad3584b57edf162fa492f85c16f">REG_BADBR</a>,	"REG_BADBR",	"invalid repetition count(s)" },
	{ REG_ERANGE,	"REG_ERANGE",	"invalid character range" },
	{ <a href="/web-llvm/docs/api/files/lib/lib/support/regex-impl-h/#ae0ee85477e8756f1cf2d7fab21e56235">REG_ESPACE</a>,	"REG_ESPACE",	"out of memory" },
	{ <a href="/web-llvm/docs/api/files/lib/lib/support/regex-impl-h/#a377356d91031028d3c2d6960b6fb3ac0">REG_BADRPT</a>,	"REG_BADRPT",	"repetition-operator operand invalid" },
	{ <a href="/web-llvm/docs/api/files/lib/lib/support/regex-impl-h/#ab974b0d779831c3f7ba76a70748d7e71">REG_EMPTY</a>,	"REG_EMPTY",	"empty (sub)expression" },
	{ <a href="/web-llvm/docs/api/files/lib/lib/support/regex-impl-h/#a284ab151886dcb8b211f21a8a0d36d78">REG_ASSERT</a>,	"REG_ASSERT",	"\"can't happen\" -- you found a bug" },
	{ <a href="/web-llvm/docs/api/files/lib/lib/support/regex-impl-h/#a5dba69255d33bbff71dc102cd9d5477e">REG_INVARG</a>,	"REG_INVARG",	"invalid argument to regex routine" },
	{ 0,		"",		"*** unknown regexp <a href="/web-llvm/docs/api/files/lib/lib/debuginfo/lib/debuginfo/codeview/symbolrecordmapping-cpp/#a9cdf893c7d17e47fa1ed8bebf92a5da4">error</a> code ***" }
}
</div>
</dd>
</dl>

<p>Definition at line 76 of file <a href="/web-llvm/docs/api/files/lib/lib/support/regerror-c">regerror.c</a>.</p>


<p>Referenced by <a href="#a728104a5963c78e214c7b847b338ad55">llvm_regerror</a> and <a href="#af481b7e4615b89b40883ff6f7f60bafd">regatoi</a>.</p>

</div>
</div>

</div>

<hr/>

<p class="doxyGeneratedBy">Generated via <a href="https://github.com/xpack/doxygen2docusaurus">doxygen2docusaurus</a> by <a href="https://www.doxygen.nl">Doxygen</a> 1.15.0.</p>

</div>
