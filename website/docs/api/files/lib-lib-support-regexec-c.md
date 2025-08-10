---

# DO NOT EDIT!
# Automatically generated via doxygen2docusaurus by Doxygen.

slug: /api/files/lib/lib/support/regexec-c
custom_edit_url: null
toc_max_heading_level: 4
keywords:
  - doxygen
  - reference
  - file

---

<div class="doxyPage">

# `regexec.c` File



## Included Headers

<div class="doxyIncludesList">#include &lt;sys/types.h&gt;
#include &lt;stdio.h&gt;
#include &lt;stdlib.h&gt;
#include &lt;string.h&gt;
#include &lt;limits.h&gt;
#include &lt;ctype.h&gt;
#include "<a href="/web-llvm/docs/api/files/lib/lib/support/regex-impl-h">regex_impl.h</a>"
#include "<a href="/web-llvm/docs/api/files/lib/lib/support/regutils-h">regutils.h</a>"
#include "<a href="/web-llvm/docs/api/files/lib/lib/support/regex2-h">regex2.h</a>"
#include "regengine.inc"
</div>

## Functions Index

<table class="doxyMembersIndex">

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">int</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a0a32880e03bd670f9ce258f691350c0b">llvm_regexec</a> (const llvm_regex_t *preg, const char *string, size_t nmatch, llvm_regmatch_t pmatch[], int eflags)</td>
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

## Macro Definitions Index

<table class="doxyMembersIndex">

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">#define</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a602d88f3fdc69402056326f5b0215216">states1</a>&nbsp;&nbsp;&nbsp;long		/* <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64expandpseudoinsts-cpp/#a4cfc8b177e8521a4b496ae2edff6244f">for</a> later <a href="/web-llvm/docs/api/files/lib/lib/codegen/lib/codegen/globalisel/localizer-cpp/#a428090a453f41a199ef67fc3f2179fbc">use</a> in <a href="/web-llvm/docs/api/files/lib/lib/support/regex-impl-h/#a91460c195c399d42fa14fbb37d0465a3">llvm_regexec</a>() decision */</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">#define</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#aed6ba9caf2dd761b586d2a4556b18a46">states</a>&nbsp;&nbsp;&nbsp;<a href="#a602d88f3fdc69402056326f5b0215216">states1</a></td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">#define</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a37ead5efaf13316dc2b72c35a310fccf">CLEAR</a>(v)&nbsp;&nbsp;&nbsp;((v) = 0)</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">#define</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#acdacc044d43a471b7e99219445f838c1">SET0</a>(v, n)&nbsp;&nbsp;&nbsp;((v) &amp;= ~((unsigned long)1 &lt;&lt; (n)))</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">#define</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a78b8419959220045f4f26f813506ef84">SET1</a>(v, n)&nbsp;&nbsp;&nbsp;((v) |= (unsigned long)1 &lt;&lt; (n))</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">#define</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#afd0ec3820b3e40560b07fc954082b93f">ISSET</a>(v, n)&nbsp;&nbsp;&nbsp;(((v) &amp; ((unsigned long)1 &lt;&lt; (n))) != 0)</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">#define</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a08cbbed4826d8ea1e614454dfebda354">ASSIGN</a>(d, s)&nbsp;&nbsp;&nbsp;((d) = (s))</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">#define</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ac07acfbb082b04f5bea72998c8976b3c">EQ</a>(a, b)&nbsp;&nbsp;&nbsp;((a) == (b))</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">#define</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ab817eef95b34c417b50a0ab99eb669d8">STATEVARS</a>&nbsp;&nbsp;&nbsp;long dummy	/* dummy version */</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">#define</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a5db6ba9e1c9a83da53632a66469f4d13">STATESETUP</a>(m, n)&nbsp;&nbsp;&nbsp;/* nothing */</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">#define</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#aea3d1f3e02f26f7104a27b3111df5caf">STATETEARDOWN</a>(m)&nbsp;&nbsp;&nbsp;/* nothing */</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">#define</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a4b5f5ae43eead0baeb0751bd0efa8003">SETUP</a>(v)&nbsp;&nbsp;&nbsp;((v) = 0)</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">#define</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a27e2b05318b406a5662fb3078a338d3a">onestate</a>&nbsp;&nbsp;&nbsp;long</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">#define</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#af319751162595d897c085e511c7e7d4a">INIT</a>(o, n)&nbsp;&nbsp;&nbsp;((o) = (unsigned long)1 &lt;&lt; (n))</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">#define</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a68c0da74d68cdce62e77fd6ae2684729">INC</a>(o)&nbsp;&nbsp;&nbsp;((o) = (unsigned long)(o) &lt;&lt; 1)</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">#define</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a44fd2e8ff7759e602fb9c691fd3ed2e7">ISSTATEIN</a>(v, o)&nbsp;&nbsp;&nbsp;(((v) &amp; (o)) != 0)</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">#define</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a6858ab421e69248b9222432dbac4f18a">FWD</a>(dst, src, n)&nbsp;&nbsp;&nbsp;((dst) |= ((unsigned long)(src)&amp;(here)) &lt;&lt; (n))</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">#define</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a53668b16673a2c2e25c9bcb7ffd9903a">BACK</a>(dst, src, n)&nbsp;&nbsp;&nbsp;((dst) |= ((unsigned long)(src)&amp;(here)) &gt;&gt; (n))</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">#define</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a82ac2430962b07ea93c0d0080839d7b4">ISSETBACK</a>(v, n)&nbsp;&nbsp;&nbsp;(((v) &amp; ((unsigned long)here &gt;&gt; (n))) != 0)</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">#define</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a4cbdc62bbcfb34e2333b698565d11d5a">SNAMES</a>&nbsp;&nbsp;&nbsp;/* engine.inc looks after details */</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">#define</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#abbd8038db44ed17d974e4f03c8b707bb">states</a>&nbsp;&nbsp;&nbsp;char *</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">#define</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ae414c630a3eaa48e694eed2dfd97752f">CLEAR</a>(v)&nbsp;&nbsp;&nbsp;memset(v, 0, m-&gt;<a href="/web-llvm/docs/api/files/lib/lib/support/lib/support/blake3/blake3-portable-c/#ab5958fad499ed692422c66bb20000a39">g</a>-&gt;nstates)</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">#define</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ad2d2ed21b6496c6cd8d78e8f9645c980">SET0</a>(v, n)&nbsp;&nbsp;&nbsp;((v)[n] = 0)</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">#define</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#abface7468f749a56ed17db1dc9335e90">SET1</a>(v, n)&nbsp;&nbsp;&nbsp;((v)[n] = 1)</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">#define</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a8e48de72ceb69dda38fc7e48d823b455">ISSET</a>(v, n)&nbsp;&nbsp;&nbsp;((v)[n])</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">#define</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#af1d71202b6760544daa654f069339950">ASSIGN</a>(d, s)&nbsp;&nbsp;&nbsp;memmove(d, s, m-&gt;<a href="/web-llvm/docs/api/files/lib/lib/support/lib/support/blake3/blake3-portable-c/#ab5958fad499ed692422c66bb20000a39">g</a>-&gt;nstates)</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">#define</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#acb972a27c6f1598c41506d53d1320846">EQ</a>(a, b)&nbsp;&nbsp;&nbsp;(<a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/scalar/mergeicmps-cpp/#affd23ab4a2fbb796128b383986b7286f">memcmp</a>(a, b, m-&gt;<a href="/web-llvm/docs/api/files/lib/lib/support/lib/support/blake3/blake3-portable-c/#ab5958fad499ed692422c66bb20000a39">g</a>-&gt;nstates) == 0)</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">#define</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a80a7c6fc38e2bf78a9af06827e76b20b">STATEVARS</a>&nbsp;&nbsp;&nbsp;long vn; char *space</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">#define</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a392330873a59da7b0d1c5fd29e291ec6">STATESETUP</a>(m, nv)&nbsp;&nbsp;&nbsp;...</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">#define</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ad2af78efbffed26c544dd31897af4bcd">STATETEARDOWN</a>(m)&nbsp;&nbsp;&nbsp;{ free((m)-&gt;space); }</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">#define</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a9a82cc4b015eda1ca07ee2496977ebe6">SETUP</a>(v)&nbsp;&nbsp;&nbsp;((v) = &amp;m-&gt;space[m-&gt;vn++ * m-&gt;<a href="/web-llvm/docs/api/files/lib/lib/support/lib/support/blake3/blake3-portable-c/#ab5958fad499ed692422c66bb20000a39">g</a>-&gt;nstates])</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">#define</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ac4a3825cbd942967bed8e6a373f05831">onestate</a>&nbsp;&nbsp;&nbsp;long</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">#define</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a772e5498d8f21a5b83268cae73512098">INIT</a>(o, n)&nbsp;&nbsp;&nbsp;((o) = (n))</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">#define</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ad44e8050e347b2baca42d9d9deaa71c1">INC</a>(o)&nbsp;&nbsp;&nbsp;((o)++)</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">#define</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#af3413d5f57f76b906336ff751dda43eb">ISSTATEIN</a>(v, o)&nbsp;&nbsp;&nbsp;((v)[o])</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">#define</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a7b2f3853ae0712ff71b983a9f5ad6ecb">FWD</a>(dst, src, n)&nbsp;&nbsp;&nbsp;((dst)[here+(n)] |= (src)[here])</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">#define</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#af7d4e2c5223d6cfe536d91e8155abdc6">BACK</a>(dst, src, n)&nbsp;&nbsp;&nbsp;((dst)[here-(n)] |= (src)[here])</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">#define</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a3fb7c1a218ae4dcf4c0fb4808dfc5732">ISSETBACK</a>(v, n)&nbsp;&nbsp;&nbsp;((v)[here - (n)])</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">#define</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a7cc56a3f312b3893f4e9d0018c79757e">LNAMES</a>&nbsp;&nbsp;&nbsp;/* flag */</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">#define</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a8bd4863aae206f6f9c8b949fbec56885">GOODFLAGS</a>(f)&nbsp;&nbsp;&nbsp;((f)&amp;(<a href="/web-llvm/docs/api/files/lib/lib/support/regex-impl-h/#aa0ca15a79530976f6d4ef90326c46858">REG_NOTBOL</a>|<a href="/web-llvm/docs/api/files/lib/lib/support/regex-impl-h/#a9d97d85ef86123060a845723d28a92cb">REG_NOTEOL</a>|<a href="/web-llvm/docs/api/files/lib/lib/support/regex-impl-h/#a343ef97b721e94f5cb1a8d2e742132b1">REG_STARTEND</a>))</td>
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

### llvm\_regexec() {#a0a32880e03bd670f9ce258f691350c0b}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">int llvm_regexec (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/files/lib/lib/support/regex-impl-h/#a14d8a63433f444e7352b4e931cf33335">llvm_regex_t</a> * preg, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> char * string, size_t nmatch, <a href="/web-llvm/docs/api/structs/llvm-regmatch-t">llvm_regmatch_t</a> pmatch=[], int eflags)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 141 of file <a href="/web-llvm/docs/api/files/lib/lib/support/regexec-c">regexec.c</a>.</p>


<p>References <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/silowercontrolflow-cpp/#a4868c5d81c5ccc98c47aeab6244346a0">assert</a>, <a href="/web-llvm/docs/api/files/lib/lib/support/lib/support/blake3/blake3-portable-c/#ab5958fad499ed692422c66bb20000a39">g</a>, <a href="#a8bd4863aae206f6f9c8b949fbec56885">GOODFLAGS</a>, <a href="/web-llvm/docs/api/files/lib/lib/support/regex2-h/#ac77db84cf42ba546550a69ac744c14ff">MAGIC1</a>, <a href="/web-llvm/docs/api/files/lib/lib/support/regex2-h/#ade86ed2c7955ab1d3b4b4d84f7df8524">MAGIC2</a>, <a href="/web-llvm/docs/api/structs/llvm-regex/#a21d425d48e65f2408ccadde7ec358bf7">llvm_regex::re_g</a>, <a href="/web-llvm/docs/api/structs/llvm-regex/#a1a96d03c57ddbbacd6bd4f5e587ce558">llvm_regex::re_magic</a>, <a href="/web-llvm/docs/api/files/lib/lib/support/regex-impl-h/#ad7e13616a54be821d6b686d8b2587401">REG_BADPAT</a>, <a href="/web-llvm/docs/api/files/lib/lib/support/regex-impl-h/#a16c9402d70d5e7b84901663934bbe901">REG_LARGE</a>, <a href="/web-llvm/docs/api/files/lib/lib/support/regex2-h/#acd206907b0132fc600321a23e82aee78">REGEX_BAD</a> and <a href="#a602d88f3fdc69402056326f5b0215216">states1</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/classes/llvm/regex/#ae787b71e8d775a2b662d04e913489d8d">llvm::Regex::match</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Macro Definitions

### ASSIGN {#a08cbbed4826d8ea1e614454dfebda354}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">#define ASSIGN(d, s)&nbsp;&nbsp;&nbsp;((d) = (s))</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 64 of file <a href="/web-llvm/docs/api/files/lib/lib/support/regexec-c">regexec.c</a>.</p>

</div>
</div>

### ASSIGN {#af1d71202b6760544daa654f069339950}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">#define ASSIGN(d, s)&nbsp;&nbsp;&nbsp;memmove(d, s, m-&gt;<a href="/web-llvm/docs/api/files/lib/lib/support/lib/support/blake3/blake3-portable-c/#ab5958fad499ed692422c66bb20000a39">g</a>-&gt;nstates)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 111 of file <a href="/web-llvm/docs/api/files/lib/lib/support/regexec-c">regexec.c</a>.</p>

</div>
</div>

### BACK {#a53668b16673a2c2e25c9bcb7ffd9903a}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">#define BACK(dst, src, n)&nbsp;&nbsp;&nbsp;((dst) |= ((unsigned long)(src)&amp;(here)) &gt;&gt; (n))</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 77 of file <a href="/web-llvm/docs/api/files/lib/lib/support/regexec-c">regexec.c</a>.</p>

</div>
</div>

### BACK {#af7d4e2c5223d6cfe536d91e8155abdc6}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">#define BACK(dst, src, n)&nbsp;&nbsp;&nbsp;((dst)[here-(n)] |= (src)[here])</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 126 of file <a href="/web-llvm/docs/api/files/lib/lib/support/regexec-c">regexec.c</a>.</p>

</div>
</div>

### CLEAR {#a37ead5efaf13316dc2b72c35a310fccf}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">#define CLEAR(v)&nbsp;&nbsp;&nbsp;((v) = 0)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 60 of file <a href="/web-llvm/docs/api/files/lib/lib/support/regexec-c">regexec.c</a>.</p>

</div>
</div>

### CLEAR {#ae414c630a3eaa48e694eed2dfd97752f}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">#define CLEAR(v)&nbsp;&nbsp;&nbsp;memset(v, 0, m-&gt;<a href="/web-llvm/docs/api/files/lib/lib/support/lib/support/blake3/blake3-portable-c/#ab5958fad499ed692422c66bb20000a39">g</a>-&gt;nstates)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 107 of file <a href="/web-llvm/docs/api/files/lib/lib/support/regexec-c">regexec.c</a>.</p>

</div>
</div>

### EQ {#ac07acfbb082b04f5bea72998c8976b3c}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">#define EQ(a, b)&nbsp;&nbsp;&nbsp;((a) == (b))</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 65 of file <a href="/web-llvm/docs/api/files/lib/lib/support/regexec-c">regexec.c</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/systemz/systemzisellowering-cpp/#a4407efa7c48f4c4931c04855996069c3">CCMaskForCondCode</a>, <a href="/web-llvm/docs/api/structs/tomp/type/definedoperatort/#ad583f1fe80f85a5c8af3b609214c5b1a">tomp::type::DefinedOperatorT&lt; I, E &gt;::ENUM</a> and <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/x86/x86isellowering-cpp/#abd57a066d3b3d5ca417117df41ca120c">LowerVSETCC</a>.</p>

</div>
</div>

### EQ {#acb972a27c6f1598c41506d53d1320846}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">#define EQ(a, b)&nbsp;&nbsp;&nbsp;(<a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/scalar/mergeicmps-cpp/#affd23ab4a2fbb796128b383986b7286f">memcmp</a>(a, b, m-&gt;<a href="/web-llvm/docs/api/files/lib/lib/support/lib/support/blake3/blake3-portable-c/#ab5958fad499ed692422c66bb20000a39">g</a>-&gt;nstates) == 0)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 112 of file <a href="/web-llvm/docs/api/files/lib/lib/support/regexec-c">regexec.c</a>.</p>

</div>
</div>

### FWD {#a6858ab421e69248b9222432dbac4f18a}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">#define FWD(dst, src, n)&nbsp;&nbsp;&nbsp;((dst) |= ((unsigned long)(src)&amp;(here)) &lt;&lt; (n))</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 76 of file <a href="/web-llvm/docs/api/files/lib/lib/support/regexec-c">regexec.c</a>.</p>

</div>
</div>

### FWD {#a7b2f3853ae0712ff71b983a9f5ad6ecb}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">#define FWD(dst, src, n)&nbsp;&nbsp;&nbsp;((dst)[here+(n)] |= (src)[here])</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 125 of file <a href="/web-llvm/docs/api/files/lib/lib/support/regexec-c">regexec.c</a>.</p>

</div>
</div>

### GOODFLAGS {#a8bd4863aae206f6f9c8b949fbec56885}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">#define GOODFLAGS(f)&nbsp;&nbsp;&nbsp;((f)&amp;(<a href="/web-llvm/docs/api/files/lib/lib/support/regex-impl-h/#aa0ca15a79530976f6d4ef90326c46858">REG_NOTBOL</a>|<a href="/web-llvm/docs/api/files/lib/lib/support/regex-impl-h/#a9d97d85ef86123060a845723d28a92cb">REG_NOTEOL</a>|<a href="/web-llvm/docs/api/files/lib/lib/support/regex-impl-h/#a343ef97b721e94f5cb1a8d2e742132b1">REG_STARTEND</a>))</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 148 of file <a href="/web-llvm/docs/api/files/lib/lib/support/regexec-c">regexec.c</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/files/lib/lib/support/regex-impl-h/#a91460c195c399d42fa14fbb37d0465a3">llvm_regexec</a>.</p>

</div>
</div>

### INC {#a68c0da74d68cdce62e77fd6ae2684729}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">#define INC(o)&nbsp;&nbsp;&nbsp;((o) = (unsigned long)(o) &lt;&lt; 1)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 72 of file <a href="/web-llvm/docs/api/files/lib/lib/support/regexec-c">regexec.c</a>.</p>

</div>
</div>

### INC {#ad44e8050e347b2baca42d9d9deaa71c1}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">#define INC(o)&nbsp;&nbsp;&nbsp;((o)++)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 121 of file <a href="/web-llvm/docs/api/files/lib/lib/support/regexec-c">regexec.c</a>.</p>

</div>
</div>

### INIT {#af319751162595d897c085e511c7e7d4a}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">#define INIT(o, n)&nbsp;&nbsp;&nbsp;((o) = (unsigned long)1 &lt;&lt; (n))</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 71 of file <a href="/web-llvm/docs/api/files/lib/lib/support/regexec-c">regexec.c</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/files/lib/lib/support/commandline-cpp/#aaa5adc2409ac3c78b33d4813ff31ae6e">tokenizeWindowsCommandLineImpl</a>.</p>

</div>
</div>

### INIT {#a772e5498d8f21a5b83268cae73512098}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">#define INIT(o, n)&nbsp;&nbsp;&nbsp;((o) = (n))</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 120 of file <a href="/web-llvm/docs/api/files/lib/lib/support/regexec-c">regexec.c</a>.</p>

</div>
</div>

### ISSET {#afd0ec3820b3e40560b07fc954082b93f}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">#define ISSET(v, n)&nbsp;&nbsp;&nbsp;(((v) &amp; ((unsigned long)1 &lt;&lt; (n))) != 0)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 63 of file <a href="/web-llvm/docs/api/files/lib/lib/support/regexec-c">regexec.c</a>.</p>

</div>
</div>

### ISSET {#a8e48de72ceb69dda38fc7e48d823b455}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">#define ISSET(v, n)&nbsp;&nbsp;&nbsp;((v)[n])</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 110 of file <a href="/web-llvm/docs/api/files/lib/lib/support/regexec-c">regexec.c</a>.</p>

</div>
</div>

### ISSETBACK {#a82ac2430962b07ea93c0d0080839d7b4}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">#define ISSETBACK(v, n)&nbsp;&nbsp;&nbsp;(((v) &amp; ((unsigned long)here &gt;&gt; (n))) != 0)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 78 of file <a href="/web-llvm/docs/api/files/lib/lib/support/regexec-c">regexec.c</a>.</p>

</div>
</div>

### ISSETBACK {#a3fb7c1a218ae4dcf4c0fb4808dfc5732}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">#define ISSETBACK(v, n)&nbsp;&nbsp;&nbsp;((v)[here - (n)])</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 127 of file <a href="/web-llvm/docs/api/files/lib/lib/support/regexec-c">regexec.c</a>.</p>

</div>
</div>

### ISSTATEIN {#a44fd2e8ff7759e602fb9c691fd3ed2e7}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">#define ISSTATEIN(v, o)&nbsp;&nbsp;&nbsp;(((v) &amp; (o)) != 0)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 73 of file <a href="/web-llvm/docs/api/files/lib/lib/support/regexec-c">regexec.c</a>.</p>

</div>
</div>

### ISSTATEIN {#af3413d5f57f76b906336ff751dda43eb}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">#define ISSTATEIN(v, o)&nbsp;&nbsp;&nbsp;((v)[o])</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 122 of file <a href="/web-llvm/docs/api/files/lib/lib/support/regexec-c">regexec.c</a>.</p>

</div>
</div>

### LNAMES {#a7cc56a3f312b3893f4e9d0018c79757e}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">#define LNAMES&nbsp;&nbsp;&nbsp;/* flag */</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 129 of file <a href="/web-llvm/docs/api/files/lib/lib/support/regexec-c">regexec.c</a>.</p>

</div>
</div>

### onestate {#a27e2b05318b406a5662fb3078a338d3a}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">#define onestate&nbsp;&nbsp;&nbsp;long</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 70 of file <a href="/web-llvm/docs/api/files/lib/lib/support/regexec-c">regexec.c</a>.</p>

</div>
</div>

### onestate {#ac4a3825cbd942967bed8e6a373f05831}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">#define onestate&nbsp;&nbsp;&nbsp;long</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 119 of file <a href="/web-llvm/docs/api/files/lib/lib/support/regexec-c">regexec.c</a>.</p>

</div>
</div>

### SET0 {#acdacc044d43a471b7e99219445f838c1}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">#define SET0(v, n)&nbsp;&nbsp;&nbsp;((v) &amp;= ~((unsigned long)1 &lt;&lt; (n)))</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 61 of file <a href="/web-llvm/docs/api/files/lib/lib/support/regexec-c">regexec.c</a>.</p>

</div>
</div>

### SET0 {#ad2d2ed21b6496c6cd8d78e8f9645c980}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">#define SET0(v, n)&nbsp;&nbsp;&nbsp;((v)[n] = 0)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 108 of file <a href="/web-llvm/docs/api/files/lib/lib/support/regexec-c">regexec.c</a>.</p>

</div>
</div>

### SET1 {#a78b8419959220045f4f26f813506ef84}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">#define SET1(v, n)&nbsp;&nbsp;&nbsp;((v) |= (unsigned long)1 &lt;&lt; (n))</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 62 of file <a href="/web-llvm/docs/api/files/lib/lib/support/regexec-c">regexec.c</a>.</p>

</div>
</div>

### SET1 {#abface7468f749a56ed17db1dc9335e90}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">#define SET1(v, n)&nbsp;&nbsp;&nbsp;((v)[n] = 1)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 109 of file <a href="/web-llvm/docs/api/files/lib/lib/support/regexec-c">regexec.c</a>.</p>

</div>
</div>

### SETUP {#a4b5f5ae43eead0baeb0751bd0efa8003}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">#define SETUP(v)&nbsp;&nbsp;&nbsp;((v) = 0)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 69 of file <a href="/web-llvm/docs/api/files/lib/lib/support/regexec-c">regexec.c</a>.</p>

</div>
</div>

### SETUP {#a9a82cc4b015eda1ca07ee2496977ebe6}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">#define SETUP(v)&nbsp;&nbsp;&nbsp;((v) = &amp;m-&gt;space[m-&gt;vn++ * m-&gt;<a href="/web-llvm/docs/api/files/lib/lib/support/lib/support/blake3/blake3-portable-c/#ab5958fad499ed692422c66bb20000a39">g</a>-&gt;nstates])</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 118 of file <a href="/web-llvm/docs/api/files/lib/lib/support/regexec-c">regexec.c</a>.</p>

</div>
</div>

### SNAMES {#a4cbdc62bbcfb34e2333b698565d11d5a}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">#define SNAMES&nbsp;&nbsp;&nbsp;/* engine.inc looks after details */</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 80 of file <a href="/web-llvm/docs/api/files/lib/lib/support/regexec-c">regexec.c</a>.</p>

</div>
</div>

### states {#aed6ba9caf2dd761b586d2a4556b18a46}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">#define states&nbsp;&nbsp;&nbsp;<a href="#a602d88f3fdc69402056326f5b0215216">states1</a></td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 59 of file <a href="/web-llvm/docs/api/files/lib/lib/support/regexec-c">regexec.c</a>.</p>

</div>
</div>

### states {#abbd8038db44ed17d974e4f03c8b707bb}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">#define states&nbsp;&nbsp;&nbsp;char *</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 106 of file <a href="/web-llvm/docs/api/files/lib/lib/support/regexec-c">regexec.c</a>.</p>

</div>
</div>

### states1 {#a602d88f3fdc69402056326f5b0215216}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">#define states1&nbsp;&nbsp;&nbsp;long		/* <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64expandpseudoinsts-cpp/#a4cfc8b177e8521a4b496ae2edff6244f">for</a> later <a href="/web-llvm/docs/api/files/lib/lib/codegen/lib/codegen/globalisel/localizer-cpp/#a428090a453f41a199ef67fc3f2179fbc">use</a> in <a href="/web-llvm/docs/api/files/lib/lib/support/regex-impl-h/#a91460c195c399d42fa14fbb37d0465a3">llvm_regexec</a>() decision */</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 58 of file <a href="/web-llvm/docs/api/files/lib/lib/support/regexec-c">regexec.c</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/files/lib/lib/support/regex-impl-h/#a91460c195c399d42fa14fbb37d0465a3">llvm_regexec</a>.</p>

</div>
</div>

### STATESETUP {#a5db6ba9e1c9a83da53632a66469f4d13}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">#define STATESETUP(m, n)&nbsp;&nbsp;&nbsp;/* nothing */</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 67 of file <a href="/web-llvm/docs/api/files/lib/lib/support/regexec-c">regexec.c</a>.</p>

</div>
</div>

### STATESETUP {#a392330873a59da7b0d1c5fd29e291ec6}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">#define STATESETUP(m, nv)&nbsp;&nbsp;&nbsp;...</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<dl class="doxySectionUser">
<dt>Value</dt>
<dd>
<div class="doxyVerbatim">				{ (m)-&gt;space = malloc((nv)*(m)-&gt;<a href="/web-llvm/docs/api/files/lib/lib/support/lib/support/blake3/blake3-portable-c/#ab5958fad499ed692422c66bb20000a39">g</a>-&gt;nstates); \
				<a href="/web-llvm/docs/api/files/lib/lib/passes/passbuilderbindings-cpp/#acdfbcf188e2d4a80837e89de2ccdffab">if</a> ((m)-&gt;space == NULL) return(<a href="/web-llvm/docs/api/files/lib/lib/support/regex-impl-h/#ae0ee85477e8756f1cf2d7fab21e56235">REG_ESPACE</a>); \
				(m)-&gt;vn = 0; }
</div>
</dd>
</dl>

<p>Definition at line 114 of file <a href="/web-llvm/docs/api/files/lib/lib/support/regexec-c">regexec.c</a>.</p>

</div>
</div>

### STATETEARDOWN {#aea3d1f3e02f26f7104a27b3111df5caf}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">#define STATETEARDOWN(m)&nbsp;&nbsp;&nbsp;/* nothing */</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 68 of file <a href="/web-llvm/docs/api/files/lib/lib/support/regexec-c">regexec.c</a>.</p>

</div>
</div>

### STATETEARDOWN {#ad2af78efbffed26c544dd31897af4bcd}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">#define STATETEARDOWN(m)&nbsp;&nbsp;&nbsp;{ free((m)-&gt;space); }</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 117 of file <a href="/web-llvm/docs/api/files/lib/lib/support/regexec-c">regexec.c</a>.</p>

</div>
</div>

### STATEVARS {#ab817eef95b34c417b50a0ab99eb669d8}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">#define STATEVARS&nbsp;&nbsp;&nbsp;long dummy	/* dummy version */</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 66 of file <a href="/web-llvm/docs/api/files/lib/lib/support/regexec-c">regexec.c</a>.</p>

</div>
</div>

### STATEVARS {#a80a7c6fc38e2bf78a9af06827e76b20b}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">#define STATEVARS&nbsp;&nbsp;&nbsp;long vn; char *space</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 113 of file <a href="/web-llvm/docs/api/files/lib/lib/support/regexec-c">regexec.c</a>.</p>

</div>
</div>

</div>

<hr/>

<p class="doxyGeneratedBy">Generated via <a href="https://xpack.github.io/doxygen2docusaurus">doxygen2docusaurus</a> 2.0.0 by <a href="https://www.doxygen.nl">Doxygen</a> 1.15.0.</p>

</div>
