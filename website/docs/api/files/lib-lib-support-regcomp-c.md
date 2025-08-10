---

# DO NOT EDIT!
# Automatically generated via doxygen2docusaurus by Doxygen.

slug: /api/files/lib/lib/support/regcomp-c
custom_edit_url: null
toc_max_heading_level: 4
keywords:
  - doxygen
  - reference
  - file

---

<div class="doxyPage">

# `regcomp.c` File



## Included Headers

<div class="doxyIncludesList">#include &lt;sys/types.h&gt;
#include &lt;stdint.h&gt;
#include &lt;stdio.h&gt;
#include &lt;string.h&gt;
#include &lt;ctype.h&gt;
#include &lt;limits.h&gt;
#include &lt;stdlib.h&gt;
#include "<a href="/web-llvm/docs/api/files/lib/lib/support/regex-impl-h">regex_impl.h</a>"
#include "<a href="/web-llvm/docs/api/files/lib/lib/support/regutils-h">regutils.h</a>"
#include "<a href="/web-llvm/docs/api/files/lib/lib/support/regex2-h">regex2.h</a>"
#include "llvm/Config/config.h"
#include "<a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/support/compiler-h">llvm/Support/Compiler.h</a>"
</div>

## Classes Index

<table class="doxyMembersIndex">

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">struct</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="/web-llvm/docs/api/structs/cclass">cclass</a></td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">struct</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="/web-llvm/docs/api/structs/cname">cname</a></td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">struct</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="/web-llvm/docs/api/structs/parse">parse</a></td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">static void</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ab9fb47c0c5ae241b5de757a26393c11d">p_ere</a> (struct parse *, int)</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">static void</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a37b2c71be1bd09705bd8e3fa728c6b57">p_ere_exp</a> (struct parse *)</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">static void</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a86427d4d576dd8585a539946c3d662b0">p_str</a> (struct parse *)</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">static void</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#aa881669949ccbba0bc595287ea522c31">p_bre</a> (struct parse *, int, int)</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">static int</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#aee283f9c02a8848c8782c35713aad80c">p_simp_re</a> (struct parse *, int)</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">static int</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ae3ba3fa6df61a284fc4b4f9267f2c9b0">p_count</a> (struct parse *)</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">static void</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#adf84e1164f7b1e4d7711f5d6131491b0">p_bracket</a> (struct parse *)</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">static void</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a979bf5dd2e011f08e36f469df553441b">p_b_term</a> (struct parse *, cset *)</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">static void</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a41c76f49aa45896e78b801c95970f43b">p_b_cclass</a> (struct parse *, cset *)</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">static void</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a5782473066b8c574e25e16bd8a9ed067">p_b_eclass</a> (struct parse *, cset *)</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">static char</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ac24cfdb8cf256d8fc31d63ae5931db44">p_b_symbol</a> (struct parse *)</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">static char</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a21e3f305c59ef8746b818db2f47b3dc4">p_b_coll_elem</a> (struct parse *, int)</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">static char</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a3dbd966fbfc12e58cc293191e863bb6d">othercase</a> (int)</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">static void</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a8c380a95a0890b550f221e2184f6cada">bothcases</a> (struct parse *, int)</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">static void</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a72709d6823c4bd388ed9113242119a9b">ordinary</a> (struct parse *, int)</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">static void</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a517f964af5d3605b0d782dc24a574c8d">nonnewline</a> (struct parse *)</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">static void</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a919284efeea9e5256497a0778b7fdd75">repeat</a> (struct parse *, sopno, int, int)</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">static int</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#af6d02bc5e86c8d1b90cf67aaa719b127">seterr</a> (struct parse *, int)</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">static <a href="/web-llvm/docs/api/structs/cset">cset</a> *</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ada80fc7b6139b088f956ab9200bd15dd">allocset</a> (struct parse *)</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">static void</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#af1b35f4d10e296aa74c965da8031ed26">freeset</a> (struct parse *, cset *)</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">static int</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a5933b7beb88db01c7671918d5e75a53c">freezeset</a> (struct parse *, cset *)</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">static int</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#afc1d8df71f0b5f0795df5212acfd57c9">firstch</a> (struct parse *, cset *)</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">static int</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ab04fc18d5a9bd2a4fc001ec92cc28a93">nch</a> (struct parse *, cset *)</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">static void</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a1f409b976df7f4fa192aa05f9e5c673e">mcadd</a> (struct parse *, cset *, const char *)</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">static void</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#af538731f90644c7cc9c9f24ae52f3134">mcinvert</a> (struct parse *, cset *)</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">static void</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a019bfa725dfcb873bdd2276a7d0ff305">mccase</a> (struct parse *, cset *)</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">static int</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a988069e7f476c7dd06254b88d0a67d5a">isinsets</a> (struct re_guts *, int)</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">static int</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a0a11d04bd61f8c45fc80d7630133cf40">samesets</a> (struct re_guts *, int, int)</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">static void</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a7f555d714dea35fa2b3e00c2e727d0af">categorize</a> (struct parse *, struct re_guts *)</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">static <a href="/web-llvm/docs/api/files/lib/lib/support/regex2-h/#a1934207945a1bf71e1355e13cebc601a">sopno</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a388e2f31ac612ec148884cd3143db78c">dupl</a> (struct parse *, sopno, sopno)</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">static void</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a42f8fec9a1fa9d471abf77a8eead0da1">doemit</a> (struct parse *, sop, size_t)</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">static void</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ab437a1156833e5395a0102102cf93c6f">doinsert</a> (struct parse *, sop, size_t, sopno)</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">static void</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ae26e3e26f2a397a734f6b8fac059b356">dofwd</a> (struct parse *, sopno, sop)</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">static void</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ae5898edb3343d9868fcc1234e0e66fb7">enlarge</a> (struct parse *, sopno)</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">static void</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a0b3b7588a93de41b3dd6640e62787e2e">stripsnug</a> (struct parse *, struct re_guts *)</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">static void</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#acf3f78aff4143b42112848d8f0dd4d7a">findmust</a> (struct parse *, struct re_guts *)</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">static <a href="/web-llvm/docs/api/files/lib/lib/support/regex2-h/#a1934207945a1bf71e1355e13cebc601a">sopno</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ab868fc2a09cae3dc9ae25baea08db7a4">pluscount</a> (struct parse *, struct re_guts *)</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">int</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a94efd6ce730ab2988bfd211af4319873">llvm_regcomp</a> (llvm_regex_t *preg, const char *pattern, int cflags)</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a6dbc3d533054da9187c049907f5dd9c4">cclasses</a>[] = ...</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">struct { ... }</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a6dda07b235599739319ccc11dadeca0d">cnames</a>[]</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">static char</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a8eb1ab58fe7e084dbbdcb71c0ecf4c9c">nuls</a>[10]</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a4d75c71d09855c3c47f35622b289316f">NPAREN</a>&nbsp;&nbsp;&nbsp;10	/* we need to remember () 1-9 <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64expandpseudoinsts-cpp/#a4cfc8b177e8521a4b496ae2edff6244f">for</a> back refs */</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#aa25dac8b80db8b8f03732eeb9ca23934">PEEK</a>()&nbsp;&nbsp;&nbsp;(*p-&gt;next)</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a7eb3d11386334057b36a2a29564502ca">PEEK2</a>()&nbsp;&nbsp;&nbsp;(*(p-&gt;next+1))</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ace441594c4bd8da94fd64b1c612ca948">MORE</a>()&nbsp;&nbsp;&nbsp;(p-&gt;end - p-&gt;next &gt; 0)</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ae8a7b434a5c7a7f1cc2ba29e93870758">MORE2</a>()&nbsp;&nbsp;&nbsp;(p-&gt;end - p-&gt;next &gt; 1)</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#aa27d4f57d0739004f70aba0719150b57">SEE</a>(c)&nbsp;&nbsp;&nbsp;(<a href="#ace441594c4bd8da94fd64b1c612ca948">MORE</a>() &amp;&amp; <a href="#aa25dac8b80db8b8f03732eeb9ca23934">PEEK</a>() == (c))</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a2a2a6d570798c3d54c3ba019b07bff5b">SEETWO</a>(a, b)&nbsp;&nbsp;&nbsp;(<a href="#ae8a7b434a5c7a7f1cc2ba29e93870758">MORE2</a>() &amp;&amp; <a href="#aa25dac8b80db8b8f03732eeb9ca23934">PEEK</a>() == (a) &amp;&amp; <a href="#a7eb3d11386334057b36a2a29564502ca">PEEK2</a>() == (b))</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#aec4cb663b8ad7a53a03298cddd7ed0ed">EAT</a>(c)&nbsp;&nbsp;&nbsp;((<a href="#aa27d4f57d0739004f70aba0719150b57">SEE</a>(c)) ? (<a href="#afa19e2eadb751f3599e443d073862a2f">NEXT</a>(), 1) : 0)</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#afabd6ecec8f255325e095428354449e0">EATTWO</a>(a, b)&nbsp;&nbsp;&nbsp;((<a href="#a2a2a6d570798c3d54c3ba019b07bff5b">SEETWO</a>(a, b)) ? (<a href="#a0c4c28b39436d006b6efc2d8e796d784">NEXT2</a>(), 1) : 0)</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#afa19e2eadb751f3599e443d073862a2f">NEXT</a>()&nbsp;&nbsp;&nbsp;(p-&gt;next++)</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a0c4c28b39436d006b6efc2d8e796d784">NEXT2</a>()&nbsp;&nbsp;&nbsp;(p-&gt;next += 2)</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a9f50fecef89d9528dab4f03e00cc3a83">NEXTn</a>(n)&nbsp;&nbsp;&nbsp;(p-&gt;next += (n))</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a378c35ea281e1ad0d8e175cf565e7eb7">GETNEXT</a>()&nbsp;&nbsp;&nbsp;(*p-&gt;next++)</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a7dab3e6a7c837ba9fd0209963b8d6d76">SETERROR</a>(e)&nbsp;&nbsp;&nbsp;<a href="#af6d02bc5e86c8d1b90cf67aaa719b127">seterr</a>(p, (e))</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#aeb49e5164a8e40811cc769c1fd331d66">REQUIRE</a>(co, e)&nbsp;&nbsp;&nbsp;(void)((co) || <a href="#a7dab3e6a7c837ba9fd0209963b8d6d76">SETERROR</a>(e))</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a0b21bf0345d6bc495eb91b8ca338f66c">MUSTSEE</a>(c, e)&nbsp;&nbsp;&nbsp;(<a href="#aeb49e5164a8e40811cc769c1fd331d66">REQUIRE</a>(<a href="#ace441594c4bd8da94fd64b1c612ca948">MORE</a>() &amp;&amp; <a href="#aa25dac8b80db8b8f03732eeb9ca23934">PEEK</a>() == (c), e))</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a72f2f2b28c8abc20f687eb02b7af4bcf">MUSTEAT</a>(c, e)&nbsp;&nbsp;&nbsp;(<a href="#aeb49e5164a8e40811cc769c1fd331d66">REQUIRE</a>(<a href="#ace441594c4bd8da94fd64b1c612ca948">MORE</a>() &amp;&amp; <a href="#a378c35ea281e1ad0d8e175cf565e7eb7">GETNEXT</a>() == (c), e))</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a9daf6c2c089e7dcee7335b7e8e7a9a27">MUSTNOTSEE</a>(c, e)&nbsp;&nbsp;&nbsp;(<a href="#aeb49e5164a8e40811cc769c1fd331d66">REQUIRE</a>(!<a href="#ace441594c4bd8da94fd64b1c612ca948">MORE</a>() || <a href="#aa25dac8b80db8b8f03732eeb9ca23934">PEEK</a>() != (c), e))</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#aed59dfea56910669e8ad0dcef8a2ea8d">EMIT</a>(op, sopnd)&nbsp;&nbsp;&nbsp;<a href="#a42f8fec9a1fa9d471abf77a8eead0da1">doemit</a>(p, (<a href="/web-llvm/docs/api/files/lib/lib/support/regex2-h/#a06b705baf08297be667616dcfd9b63a6">sop</a>)(<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/hexagon/hexagonbittracker-cpp/#a0ee73ba17c3a2cb54752905e99d77357">op</a>), (size_t)(sopnd))</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a8e44b28c2ebff8b5b41eedff8a4988a3">INSERT</a>(op, pos)&nbsp;&nbsp;&nbsp;<a href="#ab437a1156833e5395a0102102cf93c6f">doinsert</a>(p, (<a href="/web-llvm/docs/api/files/lib/lib/support/regex2-h/#a06b705baf08297be667616dcfd9b63a6">sop</a>)(<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/hexagon/hexagonbittracker-cpp/#a0ee73ba17c3a2cb54752905e99d77357">op</a>), <a href="#a114e866679b13eadadd097635f4fb10d">HERE</a>()-(pos)+1, pos)</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a69e9716ecbad0514d4755e83f2435cce">AHEAD</a>(pos)&nbsp;&nbsp;&nbsp;<a href="#ae26e3e26f2a397a734f6b8fac059b356">dofwd</a>(p, pos, <a href="#a114e866679b13eadadd097635f4fb10d">HERE</a>()-(pos))</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a66a0070eca9aa4130dec4b380318741a">ASTERN</a>(sop, pos)&nbsp;&nbsp;&nbsp;<a href="#aed59dfea56910669e8ad0dcef8a2ea8d">EMIT</a>(<a href="/web-llvm/docs/api/files/lib/lib/support/regex2-h/#a06b705baf08297be667616dcfd9b63a6">sop</a>, <a href="#a114e866679b13eadadd097635f4fb10d">HERE</a>()-pos)</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a114e866679b13eadadd097635f4fb10d">HERE</a>()&nbsp;&nbsp;&nbsp;(p-&gt;slen)</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#aabbda40c6f9ead8cf0580b32f03afc59">THERE</a>()&nbsp;&nbsp;&nbsp;(p-&gt;slen - 1)</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#aeda59df8383196f8a403d52abb973470">THERETHERE</a>()&nbsp;&nbsp;&nbsp;(p-&gt;slen - 2)</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a3994d6de1952ba0c53e9121b0db9042c">DROP</a>(n)&nbsp;&nbsp;&nbsp;(p-&gt;slen -= (n))</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a86dc91d509b741fbaa09d2797137250f">DUPMAX</a>&nbsp;&nbsp;&nbsp;255</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ae6abca5a6c63e69b609228f027a1e7ac">REGINFINITY</a>&nbsp;&nbsp;&nbsp;(<a href="#a86dc91d509b741fbaa09d2797137250f">DUPMAX</a> + 1)</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a3a32062110fa975b1721c449fa7863dc">never</a>&nbsp;&nbsp;&nbsp;0		/* some &lt;assert.h&gt;s have bugs too */</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a8bd4863aae206f6f9c8b949fbec56885">GOODFLAGS</a>(f)&nbsp;&nbsp;&nbsp;((f)&amp;~<a href="/web-llvm/docs/api/files/lib/lib/support/regex-impl-h/#a0f4eb1f7553209185de343c875ca5142">REG_DUMP</a>)</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a5fea9c0bb049b263b4b609b72ef5322c">BACKSL</a>&nbsp;&nbsp;&nbsp;(1&lt;&lt;CHAR_BIT)</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a0240ac851181b84ac374872dc5434ee4">N</a>&nbsp;&nbsp;&nbsp;2</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a12c2040f25d8e3a7b9e1c2024c618cb6">INF</a>&nbsp;&nbsp;&nbsp;3</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#acf94cdcef32661117a14bbb806832437">REP</a>(f, t)&nbsp;&nbsp;&nbsp;((f)*8 + (t))</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a01bd739644e8d3cbbb80f37f6ddb8b0e">MAP</a>(n)&nbsp;&nbsp;&nbsp;(((n) &lt;= 1) ? (n) : ((n) == <a href="#ae6abca5a6c63e69b609228f027a1e7ac">REGINFINITY</a>) ? <a href="#a12c2040f25d8e3a7b9e1c2024c618cb6">INF</a> : <a href="#a0240ac851181b84ac374872dc5434ee4">N</a>)</td>
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

### allocset() {#ada80fc7b6139b088f956ab9200bd15dd}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">cset * allocset (struct <a href="/web-llvm/docs/api/structs/parse">parse</a> * p)</td>
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



<p>Definition at line 1192 of file <a href="/web-llvm/docs/api/files/lib/lib/support/regcomp-c">regcomp.c</a>.</p>


<p>References <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/silowercontrolflow-cpp/#a4868c5d81c5ccc98c47aeab6244346a0">assert</a>, <a href="/web-llvm/docs/api/structs/cset/#ab568e443829ddd27010ba41245914ddf">cset::hash</a>, <a href="/web-llvm/docs/api/structs/cset/#ae2d5b22558d4919936141dc777b1e64a">cset::mask</a>, <a href="/web-llvm/docs/api/structs/cset/#add245b653778186aa1cf33e2e5168a40">cset::multis</a>, <a href="/web-llvm/docs/api/structs/cset/#aeea60f2f5b02738e14c8c5a5830bfc1e">cset::ptr</a>, <a href="/web-llvm/docs/api/files/lib/lib/support/regex-impl-h/#ae0ee85477e8756f1cf2d7fab21e56235">REG_ESPACE</a>, <a href="#a7dab3e6a7c837ba9fd0209963b8d6d76">SETERROR</a> and <a href="/web-llvm/docs/api/structs/cset/#aefe920e2372b20caeddda7954fe8a638">cset::smultis</a>.</p>


<p>Referenced by <a href="#adf84e1164f7b1e4d7711f5d6131491b0">p_bracket</a>.</p>

</div>
</div>

### bothcases() {#a8c380a95a0890b550f221e2184f6cada}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void bothcases (struct <a href="/web-llvm/docs/api/structs/parse">parse</a> * p, int ch)</td>
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



<p>Definition at line 1049 of file <a href="/web-llvm/docs/api/files/lib/lib/support/regcomp-c">regcomp.c</a>.</p>


<p>References <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/silowercontrolflow-cpp/#a4868c5d81c5ccc98c47aeab6244346a0">assert</a>, <a href="#a3dbd966fbfc12e58cc293191e863bb6d">othercase</a> and <a href="#adf84e1164f7b1e4d7711f5d6131491b0">p_bracket</a>.</p>


<p>Referenced by <a href="#a72709d6823c4bd388ed9113242119a9b">ordinary</a>.</p>

</div>
</div>

### categorize() {#a7f555d714dea35fa2b3e00c2e727d0af}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void categorize (struct <a href="/web-llvm/docs/api/structs/parse">parse</a> * p, struct <a href="/web-llvm/docs/api/structs/re-guts">re_guts</a> * g)</td>
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



<p>Definition at line 1422 of file <a href="/web-llvm/docs/api/files/lib/lib/support/regcomp-c">regcomp.c</a>.</p>


<p>References <a href="/web-llvm/docs/api/files/lib/lib/support/lib/support/blake3/blake3-portable-c/#ab5958fad499ed692422c66bb20000a39">g</a>, <a href="#a988069e7f476c7dd06254b88d0a67d5a">isinsets</a> and <a href="#a0a11d04bd61f8c45fc80d7630133cf40">samesets</a>.</p>


<p>Referenced by <a href="#a94efd6ce730ab2988bfd211af4319873">llvm_regcomp</a>.</p>

</div>
</div>

### doemit() {#a42f8fec9a1fa9d471abf77a8eead0da1}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void doemit (struct <a href="/web-llvm/docs/api/structs/parse">parse</a> * p, <a href="/web-llvm/docs/api/files/lib/lib/support/regex2-h/#a06b705baf08297be667616dcfd9b63a6">sop</a> op, size_t opnd)</td>
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



<p>Definition at line 1473 of file <a href="/web-llvm/docs/api/files/lib/lib/support/regcomp-c">regcomp.c</a>.</p>


<p>References <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/silowercontrolflow-cpp/#a4868c5d81c5ccc98c47aeab6244346a0">assert</a>, <a href="#ae5898edb3343d9868fcc1234e0e66fb7">enlarge</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/hexagon/hexagonbittracker-cpp/#a0ee73ba17c3a2cb54752905e99d77357">op</a>, <a href="/web-llvm/docs/api/files/lib/lib/support/regex2-h/#ac5d1cd884391f17c78fcc188b73fe4ef">OPSHIFT</a> and <a href="/web-llvm/docs/api/files/lib/lib/support/regex2-h/#aba860196419d979bad27253aeadb088d">SOP</a>.</p>

</div>
</div>

### dofwd() {#ae26e3e26f2a397a734f6b8fac059b356}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void dofwd (struct <a href="/web-llvm/docs/api/structs/parse">parse</a> * p, <a href="/web-llvm/docs/api/files/lib/lib/support/regex2-h/#a1934207945a1bf71e1355e13cebc601a">sopno</a> pos, <a href="/web-llvm/docs/api/files/lib/lib/support/regex2-h/#a06b705baf08297be667616dcfd9b63a6">sop</a> value)</td>
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



<p>Definition at line 1530 of file <a href="/web-llvm/docs/api/files/lib/lib/support/regcomp-c">regcomp.c</a>.</p>


<p>References <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/silowercontrolflow-cpp/#a4868c5d81c5ccc98c47aeab6244346a0">assert</a>, <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/sandboxir/instruction-h/#a0b0cd724f4b7f8589a602b17d6caa1fb">OP</a> and <a href="/web-llvm/docs/api/files/lib/lib/support/regex2-h/#ac5d1cd884391f17c78fcc188b73fe4ef">OPSHIFT</a>.</p>

</div>
</div>

### doinsert() {#ab437a1156833e5395a0102102cf93c6f}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void doinsert (struct <a href="/web-llvm/docs/api/structs/parse">parse</a> * p, <a href="/web-llvm/docs/api/files/lib/lib/support/regex2-h/#a06b705baf08297be667616dcfd9b63a6">sop</a> op, size_t opnd, <a href="/web-llvm/docs/api/files/lib/lib/support/regex2-h/#a1934207945a1bf71e1355e13cebc601a">sopno</a> pos)</td>
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



<p>Definition at line 1495 of file <a href="/web-llvm/docs/api/files/lib/lib/support/regcomp-c">regcomp.c</a>.</p>


<p>References <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/silowercontrolflow-cpp/#a4868c5d81c5ccc98c47aeab6244346a0">assert</a>, <a href="#aed59dfea56910669e8ad0dcef8a2ea8d">EMIT</a>, <a href="#a114e866679b13eadadd097635f4fb10d">HERE</a>, <a href="#a4d75c71d09855c3c47f35622b289316f">NPAREN</a> and <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/hexagon/hexagonbittracker-cpp/#a0ee73ba17c3a2cb54752905e99d77357">op</a>.</p>

</div>
</div>

### dupl() {#a388e2f31ac612ec148884cd3143db78c}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">sopno dupl (struct <a href="/web-llvm/docs/api/structs/parse">parse</a> * p, <a href="/web-llvm/docs/api/files/lib/lib/support/regex2-h/#a1934207945a1bf71e1355e13cebc601a">sopno</a> start, <a href="/web-llvm/docs/api/files/lib/lib/support/regex2-h/#a1934207945a1bf71e1355e13cebc601a">sopno</a> finish)</td>
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



<p>Definition at line 1447 of file <a href="/web-llvm/docs/api/files/lib/lib/support/regcomp-c">regcomp.c</a>.</p>


<p>References <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/silowercontrolflow-cpp/#a4868c5d81c5ccc98c47aeab6244346a0">assert</a>, <a href="#ae5898edb3343d9868fcc1234e0e66fb7">enlarge</a> and <a href="#a114e866679b13eadadd097635f4fb10d">HERE</a>.</p>


<p>Referenced by <a href="#a37b2c71be1bd09705bd8e3fa728c6b57">p_ere_exp</a>, <a href="#aee283f9c02a8848c8782c35713aad80c">p_simp_re</a> and <a href="#a919284efeea9e5256497a0778b7fdd75">repeat</a>.</p>

</div>
</div>

### enlarge() {#ae5898edb3343d9868fcc1234e0e66fb7}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void enlarge (struct <a href="/web-llvm/docs/api/structs/parse">parse</a> * p, <a href="/web-llvm/docs/api/files/lib/lib/support/regex2-h/#a1934207945a1bf71e1355e13cebc601a">sopno</a> size)</td>
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



<p>Definition at line 1544 of file <a href="/web-llvm/docs/api/files/lib/lib/support/regcomp-c">regcomp.c</a>.</p>


<p>References <a href="/web-llvm/docs/api/files/lib/lib/support/regex-impl-h/#ae0ee85477e8756f1cf2d7fab21e56235">REG_ESPACE</a>, <a href="#a7dab3e6a7c837ba9fd0209963b8d6d76">SETERROR</a> and <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/nvptx/nvvmreflect-cpp/#ac934769d93af95250952646a3829df4c">size</a>.</p>


<p>Referenced by <a href="#a42f8fec9a1fa9d471abf77a8eead0da1">doemit</a> and <a href="#a388e2f31ac612ec148884cd3143db78c">dupl</a>.</p>

</div>
</div>

### findmust() {#acf3f78aff4143b42112848d8f0dd4d7a}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void findmust (struct <a href="/web-llvm/docs/api/structs/parse">parse</a> * p, struct <a href="/web-llvm/docs/api/structs/re-guts">re_guts</a> * g)</td>
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



<p>Definition at line 1595 of file <a href="/web-llvm/docs/api/files/lib/lib/support/regcomp-c">regcomp.c</a>.</p>


<p>References <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/silowercontrolflow-cpp/#a4868c5d81c5ccc98c47aeab6244346a0">assert</a>, <a href="/web-llvm/docs/api/files/lib/lib/support/lib/support/blake3/blake3-portable-c/#ab5958fad499ed692422c66bb20000a39">g</a>, <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/support/compiler-h/#a9579881de06b1560d242d15171ca1b86">LLVM_FALLTHROUGH</a>, <a href="/web-llvm/docs/api/files/lib/lib/support/regex2-h/#a1c30d83b5b72b81505f486ec816f7f50">O_CH</a>, <a href="/web-llvm/docs/api/files/lib/lib/support/regex2-h/#a909bd2030d6527ad02f8bf552deec559">O_QUEST</a>, <a href="/web-llvm/docs/api/files/lib/lib/support/regex2-h/#a3540bd5c66f3147b883585e722d658bf">OCH_</a>, <a href="/web-llvm/docs/api/files/lib/lib/support/regex2-h/#a54d1c317420932112aa9e171d754811f">OCHAR</a>, <a href="/web-llvm/docs/api/files/lib/lib/support/regex2-h/#a434ef202369d0ddf2def41bfeaad210e">OEND</a>, <a href="/web-llvm/docs/api/files/lib/lib/support/regex2-h/#a68656a8c7cdec0a5e6112976802801fd">OLPAREN</a>, <a href="/web-llvm/docs/api/files/lib/lib/support/regex2-h/#a3af4f4635fa6eb5d9030afce3f795b0f">OOR2</a>, <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/sandboxir/instruction-h/#a0b0cd724f4b7f8589a602b17d6caa1fb">OP</a>, <a href="/web-llvm/docs/api/files/lib/lib/support/regex2-h/#a704503a3445b5e1cfc2ba2032f3fefc7">OPLUS_</a>, <a href="/web-llvm/docs/api/files/lib/lib/support/regex2-h/#a0eaed4c74d1e8101dbe98aa9bb336697">OPND</a>, <a href="/web-llvm/docs/api/files/lib/lib/support/regex2-h/#a5fa9106fa97c3f33abc44db4f2a4f04a">OQUEST_</a>, <a href="/web-llvm/docs/api/files/lib/lib/support/regex2-h/#ad105523f8dbc7a2b1a0f6e98bff80ca4">ORPAREN</a> and <a href="/web-llvm/docs/api/files/lib/lib/support/regex2-h/#acd206907b0132fc600321a23e82aee78">REGEX_BAD</a>.</p>


<p>Referenced by <a href="#a94efd6ce730ab2988bfd211af4319873">llvm_regcomp</a>.</p>

</div>
</div>

### firstch() {#afc1d8df71f0b5f0795df5212acfd57c9}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">int firstch (struct <a href="/web-llvm/docs/api/structs/parse">parse</a> * p, <a href="/web-llvm/docs/api/structs/cset">cset</a> * cs)</td>
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



<p>Definition at line 1306 of file <a href="/web-llvm/docs/api/files/lib/lib/support/regcomp-c">regcomp.c</a>.</p>


<p>References <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/silowercontrolflow-cpp/#a4868c5d81c5ccc98c47aeab6244346a0">assert</a>, <a href="/web-llvm/docs/api/files/lib/lib/support/regex2-h/#aa1db32adfba101e49e40979db85943b3">CHIN</a> and <a href="#a3a32062110fa975b1721c449fa7863dc">never</a>.</p>


<p>Referenced by <a href="#adf84e1164f7b1e4d7711f5d6131491b0">p_bracket</a>.</p>

</div>
</div>

### freeset() {#af1b35f4d10e296aa74c965da8031ed26}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void freeset (struct <a href="/web-llvm/docs/api/structs/parse">parse</a> * p, <a href="/web-llvm/docs/api/structs/cset">cset</a> * cs)</td>
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



<p>Definition at line 1253 of file <a href="/web-llvm/docs/api/files/lib/lib/support/regcomp-c">regcomp.c</a>.</p>


<p>Reference <a href="/web-llvm/docs/api/files/lib/lib/support/regex2-h/#a0e39f78dc00de8dad42ae166aab07c05">CHsub</a>.</p>


<p>Referenced by <a href="#a5933b7beb88db01c7671918d5e75a53c">freezeset</a> and <a href="#adf84e1164f7b1e4d7711f5d6131491b0">p_bracket</a>.</p>

</div>
</div>

### freezeset() {#a5933b7beb88db01c7671918d5e75a53c}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">int freezeset (struct <a href="/web-llvm/docs/api/structs/parse">parse</a> * p, <a href="/web-llvm/docs/api/structs/cset">cset</a> * cs)</td>
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



<p>Definition at line 1275 of file <a href="/web-llvm/docs/api/files/lib/lib/support/regcomp-c">regcomp.c</a>.</p>


<p>References <a href="/web-llvm/docs/api/files/lib/lib/support/regex2-h/#aa1db32adfba101e49e40979db85943b3">CHIN</a>, <a href="#af1b35f4d10e296aa74c965da8031ed26">freeset</a> and <a href="/web-llvm/docs/api/structs/cset/#ab568e443829ddd27010ba41245914ddf">cset::hash</a>.</p>


<p>Referenced by <a href="#adf84e1164f7b1e4d7711f5d6131491b0">p_bracket</a>.</p>

</div>
</div>

### isinsets() {#a988069e7f476c7dd06254b88d0a67d5a}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">int isinsets (struct <a href="/web-llvm/docs/api/structs/re-guts">re_guts</a> * g, int c)</td>
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



<p>Definition at line 1387 of file <a href="/web-llvm/docs/api/files/lib/lib/support/regcomp-c">regcomp.c</a>.</p>


<p>Reference <a href="/web-llvm/docs/api/files/lib/lib/support/lib/support/blake3/blake3-portable-c/#ab5958fad499ed692422c66bb20000a39">g</a>.</p>


<p>Referenced by <a href="#a7f555d714dea35fa2b3e00c2e727d0af">categorize</a>.</p>

</div>
</div>

### llvm\_regcomp() {#a94efd6ce730ab2988bfd211af4319873}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">int llvm_regcomp (<a href="/web-llvm/docs/api/files/lib/lib/support/regex-impl-h/#a14d8a63433f444e7352b4e931cf33335">llvm_regex_t</a> * preg, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> char * pattern, int cflags)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 293 of file <a href="/web-llvm/docs/api/files/lib/lib/support/regcomp-c">regcomp.c</a>.</p>


<p>References <a href="#a7f555d714dea35fa2b3e00c2e727d0af">categorize</a>, <a href="/web-llvm/docs/api/structs/re-guts/#a120902614290b8531ce62482aa5e43d0">re_guts::cflags</a>, <a href="#aed59dfea56910669e8ad0dcef8a2ea8d">EMIT</a>, <a href="#acf3f78aff4143b42112848d8f0dd4d7a">findmust</a>, <a href="/web-llvm/docs/api/files/lib/lib/support/lib/support/blake3/blake3-portable-c/#ab5958fad499ed692422c66bb20000a39">g</a>, <a href="#a8bd4863aae206f6f9c8b949fbec56885">GOODFLAGS</a>, <a href="/web-llvm/docs/api/files/lib/lib/support/regex-impl-h/#a5b067957e932003b295ff3a8bbffe882">llvm_regfree</a>, <a href="/web-llvm/docs/api/files/lib/lib/support/regex2-h/#ac77db84cf42ba546550a69ac744c14ff">MAGIC1</a>, <a href="/web-llvm/docs/api/files/lib/lib/support/regex2-h/#ade86ed2c7955ab1d3b4b4d84f7df8524">MAGIC2</a>, <a href="/web-llvm/docs/api/files/lib/lib/support/regutils-h/#a1fa2460e32327ade49189c95740bc1b5">NC</a>, <a href="#a4d75c71d09855c3c47f35622b289316f">NPAREN</a>, <a href="/web-llvm/docs/api/files/lib/lib/support/regex2-h/#a434ef202369d0ddf2def41bfeaad210e">OEND</a>, <a href="/web-llvm/docs/api/files/lib/lib/support/regex2-h/#aec78e7a9e90a406a56f859ee456e8eae">OUT</a>, <a href="#aa881669949ccbba0bc595287ea522c31">p_bre</a>, <a href="#ab9fb47c0c5ae241b5de757a26393c11d">p_ere</a>, <a href="#a86427d4d576dd8585a539946c3d662b0">p_str</a>, <a href="#ab868fc2a09cae3dc9ae25baea08db7a4">pluscount</a>, <a href="/web-llvm/docs/api/structs/llvm-regex/#af5da3516ebe39b7fe40315175d49b55a">llvm_regex::re_endp</a>, <a href="/web-llvm/docs/api/structs/llvm-regex/#a21d425d48e65f2408ccadde7ec358bf7">llvm_regex::re_g</a>, <a href="/web-llvm/docs/api/structs/llvm-regex/#a1a96d03c57ddbbacd6bd4f5e587ce558">llvm_regex::re_magic</a>, <a href="/web-llvm/docs/api/structs/llvm-regex/#ab7b9279f0acdb26e438298369f121641">llvm_regex::re_nsub</a>, <a href="/web-llvm/docs/api/files/lib/lib/support/regex-impl-h/#a284ab151886dcb8b211f21a8a0d36d78">REG_ASSERT</a>, <a href="/web-llvm/docs/api/files/lib/lib/support/regex-impl-h/#ae0ee85477e8756f1cf2d7fab21e56235">REG_ESPACE</a>, <a href="/web-llvm/docs/api/files/lib/lib/support/regex-impl-h/#a5fc31e6da9b77e09ea62b4544ac4767f">REG_EXTENDED</a>, <a href="/web-llvm/docs/api/files/lib/lib/support/regex-impl-h/#a5dba69255d33bbff71dc102cd9d5477e">REG_INVARG</a>, <a href="/web-llvm/docs/api/files/lib/lib/support/regex-impl-h/#a6330cb5b93bbe64df6c63d57bbd866b5">REG_NOSPEC</a>, <a href="/web-llvm/docs/api/files/lib/lib/support/regex-impl-h/#a95142205890c3ac8dc12e5850cb0e946">REG_PEND</a>, <a href="/web-llvm/docs/api/files/lib/lib/support/regex2-h/#acd206907b0132fc600321a23e82aee78">REGEX_BAD</a>, <a href="#a7dab3e6a7c837ba9fd0209963b8d6d76">SETERROR</a>, <a href="#a0b3b7588a93de41b3dd6640e62787e2e">stripsnug</a> and <a href="#aabbda40c6f9ead8cf0580b32f03afc59">THERE</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/classes/llvm/regex/#a80318325208303662f9f20af3a28b1d7">llvm::Regex::Regex</a>.</p>

</div>
</div>

### mcadd() {#a1f409b976df7f4fa192aa05f9e5c673e}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void mcadd (struct <a href="/web-llvm/docs/api/structs/parse">parse</a> * p, <a href="/web-llvm/docs/api/structs/cset">cset</a> * cs, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> char * cp)</td>
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



<p>Definition at line 1338 of file <a href="/web-llvm/docs/api/files/lib/lib/support/regcomp-c">regcomp.c</a>.</p>


<p>References <a href="/web-llvm/docs/api/files/lib/lib/support/regex-impl-h/#a0665f8b90af5f30c518451a34a94e0aa">llvm_strlcpy</a>, <a href="/web-llvm/docs/api/structs/cset/#add245b653778186aa1cf33e2e5168a40">cset::multis</a>, <a href="/web-llvm/docs/api/files/lib/lib/support/regex-impl-h/#ae0ee85477e8756f1cf2d7fab21e56235">REG_ESPACE</a>, <a href="#a7dab3e6a7c837ba9fd0209963b8d6d76">SETERROR</a> and <a href="/web-llvm/docs/api/structs/cset/#aefe920e2372b20caeddda7954fe8a638">cset::smultis</a>.</p>

</div>
</div>

### mccase() {#a019bfa725dfcb873bdd2276a7d0ff305}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void mccase (struct <a href="/web-llvm/docs/api/structs/parse">parse</a> * p, <a href="/web-llvm/docs/api/structs/cset">cset</a> * cs)</td>
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



<p>Definition at line 1378 of file <a href="/web-llvm/docs/api/files/lib/lib/support/regcomp-c">regcomp.c</a>.</p>


<p>References <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/silowercontrolflow-cpp/#a4868c5d81c5ccc98c47aeab6244346a0">assert</a> and <a href="/web-llvm/docs/api/structs/cset/#add245b653778186aa1cf33e2e5168a40">cset::multis</a>.</p>


<p>Referenced by <a href="#adf84e1164f7b1e4d7711f5d6131491b0">p_bracket</a>.</p>

</div>
</div>

### mcinvert() {#af538731f90644c7cc9c9f24ae52f3134}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void mcinvert (struct <a href="/web-llvm/docs/api/structs/parse">parse</a> * p, <a href="/web-llvm/docs/api/structs/cset">cset</a> * cs)</td>
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



<p>Definition at line 1365 of file <a href="/web-llvm/docs/api/files/lib/lib/support/regcomp-c">regcomp.c</a>.</p>


<p>References <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/silowercontrolflow-cpp/#a4868c5d81c5ccc98c47aeab6244346a0">assert</a> and <a href="/web-llvm/docs/api/structs/cset/#add245b653778186aa1cf33e2e5168a40">cset::multis</a>.</p>


<p>Referenced by <a href="#adf84e1164f7b1e4d7711f5d6131491b0">p_bracket</a>.</p>

</div>
</div>

### nch() {#ab04fc18d5a9bd2a4fc001ec92cc28a93}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">int nch (struct <a href="/web-llvm/docs/api/structs/parse">parse</a> * p, <a href="/web-llvm/docs/api/structs/cset">cset</a> * cs)</td>
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



<p>Definition at line 1322 of file <a href="/web-llvm/docs/api/files/lib/lib/support/regcomp-c">regcomp.c</a>.</p>


<p>Reference <a href="/web-llvm/docs/api/files/lib/lib/support/regex2-h/#aa1db32adfba101e49e40979db85943b3">CHIN</a>.</p>


<p>Referenced by <a href="#adf84e1164f7b1e4d7711f5d6131491b0">p_bracket</a>.</p>

</div>
</div>

### nonnewline() {#a517f964af5d3605b0d782dc24a574c8d}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void nonnewline (struct <a href="/web-llvm/docs/api/structs/parse">parse</a> * p)</td>
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



<p>Definition at line 1091 of file <a href="/web-llvm/docs/api/files/lib/lib/support/regcomp-c">regcomp.c</a>.</p>


<p>References <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/silowercontrolflow-cpp/#a4868c5d81c5ccc98c47aeab6244346a0">assert</a> and <a href="#adf84e1164f7b1e4d7711f5d6131491b0">p_bracket</a>.</p>


<p>Referenced by <a href="#a37b2c71be1bd09705bd8e3fa728c6b57">p_ere_exp</a> and <a href="#aee283f9c02a8848c8782c35713aad80c">p_simp_re</a>.</p>

</div>
</div>

### ordinary() {#a72709d6823c4bd388ed9113242119a9b}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void ordinary (struct <a href="/web-llvm/docs/api/structs/parse">parse</a> * p, int ch)</td>
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



<p>Definition at line 1072 of file <a href="/web-llvm/docs/api/files/lib/lib/support/regcomp-c">regcomp.c</a>.</p>


<p>References <a href="#a8c380a95a0890b550f221e2184f6cada">bothcases</a>, <a href="#aed59dfea56910669e8ad0dcef8a2ea8d">EMIT</a>, <a href="/web-llvm/docs/api/files/lib/lib/support/regex2-h/#a54d1c317420932112aa9e171d754811f">OCHAR</a>, <a href="#a3dbd966fbfc12e58cc293191e863bb6d">othercase</a> and <a href="/web-llvm/docs/api/files/lib/lib/support/regex-impl-h/#a0c3e7b1d5bc9c2d278a544fe9b61b67a">REG_ICASE</a>.</p>


<p>Referenced by <a href="#adf84e1164f7b1e4d7711f5d6131491b0">p_bracket</a>, <a href="#a37b2c71be1bd09705bd8e3fa728c6b57">p_ere_exp</a>, <a href="#aee283f9c02a8848c8782c35713aad80c">p_simp_re</a> and <a href="#a86427d4d576dd8585a539946c3d662b0">p_str</a>.</p>

</div>
</div>

### othercase() {#a3dbd966fbfc12e58cc293191e863bb6d}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">char othercase (int ch)</td>
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



<p>Definition at line 1031 of file <a href="/web-llvm/docs/api/files/lib/lib/support/regcomp-c">regcomp.c</a>.</p>


<p>Reference <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/silowercontrolflow-cpp/#a4868c5d81c5ccc98c47aeab6244346a0">assert</a>.</p>


<p>Referenced by <a href="#a8c380a95a0890b550f221e2184f6cada">bothcases</a>, <a href="#a72709d6823c4bd388ed9113242119a9b">ordinary</a> and <a href="#adf84e1164f7b1e4d7711f5d6131491b0">p_bracket</a>.</p>

</div>
</div>

### p\_b\_cclass() {#a41c76f49aa45896e78b801c95970f43b}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void p_b_cclass (struct <a href="/web-llvm/docs/api/structs/parse">parse</a> * p, <a href="/web-llvm/docs/api/structs/cset">cset</a> * cs)</td>
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



<p>Definition at line 941 of file <a href="/web-llvm/docs/api/files/lib/lib/support/regcomp-c">regcomp.c</a>.</p>


<p>References <a href="#a6dbc3d533054da9187c049907f5dd9c4">cclasses</a>, <a href="/web-llvm/docs/api/files/lib/lib/support/regex2-h/#a6d21b10d07ea5a414f35de71fb5891d5">CHadd</a>, <a href="/web-llvm/docs/api/structs/cclass/#a60d1583b1313ba92412c607da497b96b">cclass::chars</a>, <a href="/web-llvm/docs/api/files/lib/lib/support/regex2-h/#abf6583f0e5d8fd98cce75e9b5902f04a">MCadd</a>, <a href="#ace441594c4bd8da94fd64b1c612ca948">MORE</a>, <a href="/web-llvm/docs/api/structs/cclass/#a0ddeaf5cc352118e2a48f0695296066e">cclass::multis</a>, <a href="/web-llvm/docs/api/structs/cclass/#aaad13453dadff228045e29a5affd3200">cclass::name</a>, <a href="#afa19e2eadb751f3599e443d073862a2f">NEXT</a>, <a href="#aa25dac8b80db8b8f03732eeb9ca23934">PEEK</a>, <a href="/web-llvm/docs/api/files/lib/lib/support/regex-impl-h/#a16d4f054978e6b70c2672145435a7917">REG_ECTYPE</a> and <a href="#a7dab3e6a7c837ba9fd0209963b8d6d76">SETERROR</a>.</p>


<p>Referenced by <a href="#a979bf5dd2e011f08e36f469df553441b">p_b_term</a>.</p>

</div>
</div>

### p\_b\_coll\_elem() {#a21e3f305c59ef8746b818db2f47b3dc4}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">char p_b_coll_elem (struct <a href="/web-llvm/docs/api/structs/parse">parse</a> * p, int endc)</td>
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



<p>Definition at line 1004 of file <a href="/web-llvm/docs/api/files/lib/lib/support/regcomp-c">regcomp.c</a>.</p>


<p>References <a href="#a6dda07b235599739319ccc11dadeca0d">cnames</a>, <a href="/web-llvm/docs/api/structs/cname/#a2a77bc035a862217178ac6247ba8fbf8">cname::code</a>, <a href="#ace441594c4bd8da94fd64b1c612ca948">MORE</a>, <a href="/web-llvm/docs/api/structs/cname/#a41c8ee241e24a7a44c79f18eb414128f">cname::name</a>, <a href="#afa19e2eadb751f3599e443d073862a2f">NEXT</a>, <a href="/web-llvm/docs/api/files/lib/lib/support/regex-impl-h/#a1e0ef4e0e9d4b184f1b21285cee16c81">REG_EBRACK</a>, <a href="/web-llvm/docs/api/files/lib/lib/support/regex-impl-h/#ac8233bd7398fdb236c8dadf7abebb8a3">REG_ECOLLATE</a>, <a href="#a2a2a6d570798c3d54c3ba019b07bff5b">SEETWO</a> and <a href="#a7dab3e6a7c837ba9fd0209963b8d6d76">SETERROR</a>.</p>


<p>Referenced by <a href="#a5782473066b8c574e25e16bd8a9ed067">p_b_eclass</a> and <a href="#ac24cfdb8cf256d8fc31d63ae5931db44">p_b_symbol</a>.</p>

</div>
</div>

### p\_b\_eclass() {#a5782473066b8c574e25e16bd8a9ed067}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void p_b_eclass (struct <a href="/web-llvm/docs/api/structs/parse">parse</a> * p, <a href="/web-llvm/docs/api/structs/cset">cset</a> * cs)</td>
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



<p>Definition at line 974 of file <a href="/web-llvm/docs/api/files/lib/lib/support/regcomp-c">regcomp.c</a>.</p>


<p>References <a href="/web-llvm/docs/api/files/lib/lib/support/regex2-h/#a6d21b10d07ea5a414f35de71fb5891d5">CHadd</a> and <a href="#a21e3f305c59ef8746b818db2f47b3dc4">p_b_coll_elem</a>.</p>


<p>Referenced by <a href="#a979bf5dd2e011f08e36f469df553441b">p_b_term</a>.</p>

</div>
</div>

### p\_b\_symbol() {#ac24cfdb8cf256d8fc31d63ae5931db44}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">char p_b_symbol (struct <a href="/web-llvm/docs/api/structs/parse">parse</a> * p)</td>
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



<p>Definition at line 986 of file <a href="/web-llvm/docs/api/files/lib/lib/support/regcomp-c">regcomp.c</a>.</p>


<p>References <a href="#afabd6ecec8f255325e095428354449e0">EATTWO</a>, <a href="#a378c35ea281e1ad0d8e175cf565e7eb7">GETNEXT</a>, <a href="#ace441594c4bd8da94fd64b1c612ca948">MORE</a>, <a href="#a21e3f305c59ef8746b818db2f47b3dc4">p_b_coll_elem</a>, <a href="/web-llvm/docs/api/files/lib/lib/support/regex-impl-h/#a1e0ef4e0e9d4b184f1b21285cee16c81">REG_EBRACK</a>, <a href="/web-llvm/docs/api/files/lib/lib/support/regex-impl-h/#ac8233bd7398fdb236c8dadf7abebb8a3">REG_ECOLLATE</a> and <a href="#aeb49e5164a8e40811cc769c1fd331d66">REQUIRE</a>.</p>


<p>Referenced by <a href="#a979bf5dd2e011f08e36f469df553441b">p_b_term</a>.</p>

</div>
</div>

### p\_b\_term() {#a979bf5dd2e011f08e36f469df553441b}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void p_b_term (struct <a href="/web-llvm/docs/api/structs/parse">parse</a> * p, <a href="/web-llvm/docs/api/structs/cset">cset</a> * cs)</td>
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



<p>Definition at line 878 of file <a href="/web-llvm/docs/api/files/lib/lib/support/regcomp-c">regcomp.c</a>.</p>


<p>References <a href="/web-llvm/docs/api/files/lib/lib/support/regex2-h/#a6d21b10d07ea5a414f35de71fb5891d5">CHadd</a>, <a href="#aec4cb663b8ad7a53a03298cddd7ed0ed">EAT</a>, <a href="#afabd6ecec8f255325e095428354449e0">EATTWO</a>, <a href="#ace441594c4bd8da94fd64b1c612ca948">MORE</a>, <a href="#ae8a7b434a5c7a7f1cc2ba29e93870758">MORE2</a>, <a href="#afa19e2eadb751f3599e443d073862a2f">NEXT</a>, <a href="#a0c4c28b39436d006b6efc2d8e796d784">NEXT2</a>, <a href="#a41c76f49aa45896e78b801c95970f43b">p_b_cclass</a>, <a href="#a5782473066b8c574e25e16bd8a9ed067">p_b_eclass</a>, <a href="#ac24cfdb8cf256d8fc31d63ae5931db44">p_b_symbol</a>, <a href="#aa25dac8b80db8b8f03732eeb9ca23934">PEEK</a>, <a href="#a7eb3d11386334057b36a2a29564502ca">PEEK2</a>, <a href="/web-llvm/docs/api/files/lib/lib/support/regex-impl-h/#a1e0ef4e0e9d4b184f1b21285cee16c81">REG_EBRACK</a>, <a href="/web-llvm/docs/api/files/lib/lib/support/regex-impl-h/#ac8233bd7398fdb236c8dadf7abebb8a3">REG_ECOLLATE</a>, <a href="/web-llvm/docs/api/files/lib/lib/support/regex-impl-h/#a16d4f054978e6b70c2672145435a7917">REG_ECTYPE</a>, <a href="/web-llvm/docs/api/files/lib/lib/support/regex-impl-h/#a92147e11843057bc3c9a5b2a2f682b14">REG_ERANGE</a>, <a href="#aeb49e5164a8e40811cc769c1fd331d66">REQUIRE</a>, <a href="#aa27d4f57d0739004f70aba0719150b57">SEE</a> and <a href="#a7dab3e6a7c837ba9fd0209963b8d6d76">SETERROR</a>.</p>


<p>Referenced by <a href="#adf84e1164f7b1e4d7711f5d6131491b0">p_bracket</a>.</p>

</div>
</div>

### p\_bracket() {#adf84e1164f7b1e4d7711f5d6131491b0}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void p_bracket (struct <a href="/web-llvm/docs/api/structs/parse">parse</a> * p)</td>
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



<p>Definition at line 797 of file <a href="/web-llvm/docs/api/files/lib/lib/support/regcomp-c">regcomp.c</a>.</p>


<p>References <a href="#ada80fc7b6139b088f956ab9200bd15dd">allocset</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/silowercontrolflow-cpp/#a4868c5d81c5ccc98c47aeab6244346a0">assert</a>, <a href="/web-llvm/docs/api/files/lib/lib/support/regex2-h/#a6d21b10d07ea5a414f35de71fb5891d5">CHadd</a>, <a href="/web-llvm/docs/api/files/lib/lib/support/regex2-h/#aa1db32adfba101e49e40979db85943b3">CHIN</a>, <a href="/web-llvm/docs/api/files/lib/lib/support/regex2-h/#a0e39f78dc00de8dad42ae166aab07c05">CHsub</a>, <a href="#aec4cb663b8ad7a53a03298cddd7ed0ed">EAT</a>, <a href="#aed59dfea56910669e8ad0dcef8a2ea8d">EMIT</a>, <a href="#afc1d8df71f0b5f0795df5212acfd57c9">firstch</a>, <a href="#af1b35f4d10e296aa74c965da8031ed26">freeset</a>, <a href="#a5933b7beb88db01c7671918d5e75a53c">freezeset</a>, <a href="#a019bfa725dfcb873bdd2276a7d0ff305">mccase</a>, <a href="#af538731f90644c7cc9c9f24ae52f3134">mcinvert</a>, <a href="#ace441594c4bd8da94fd64b1c612ca948">MORE</a>, <a href="/web-llvm/docs/api/structs/cset/#add245b653778186aa1cf33e2e5168a40">cset::multis</a>, <a href="#a72f2f2b28c8abc20f687eb02b7af4bcf">MUSTEAT</a>, <a href="#ab04fc18d5a9bd2a4fc001ec92cc28a93">nch</a>, <a href="#a9f50fecef89d9528dab4f03e00cc3a83">NEXTn</a>, <a href="/web-llvm/docs/api/files/lib/lib/support/regex2-h/#aac639b74f02e71b7e9b4e6179afc8b6f">OANYOF</a>, <a href="/web-llvm/docs/api/files/lib/lib/support/regex2-h/#a6b67f8af6085cd377b776d876fbf08f5">OBOW</a>, <a href="/web-llvm/docs/api/files/lib/lib/support/regex2-h/#ac736e994358a7ca5c854cec2e689de2d">OEOW</a>, <a href="#a72709d6823c4bd388ed9113242119a9b">ordinary</a>, <a href="#a3dbd966fbfc12e58cc293191e863bb6d">othercase</a>, <a href="#a979bf5dd2e011f08e36f469df553441b">p_b_term</a>, <a href="#aa25dac8b80db8b8f03732eeb9ca23934">PEEK</a>, <a href="/web-llvm/docs/api/files/lib/lib/support/regex-impl-h/#a1e0ef4e0e9d4b184f1b21285cee16c81">REG_EBRACK</a>, <a href="/web-llvm/docs/api/files/lib/lib/support/regex-impl-h/#a0c3e7b1d5bc9c2d278a544fe9b61b67a">REG_ICASE</a>, <a href="/web-llvm/docs/api/files/lib/lib/support/regex-impl-h/#ab678ef3b27bf7de2fb82c79cb2cd9d8a">REG_NEWLINE</a> and <a href="#a2a2a6d570798c3d54c3ba019b07bff5b">SEETWO</a>.</p>


<p>Referenced by <a href="#a8c380a95a0890b550f221e2184f6cada">bothcases</a>, <a href="#a517f964af5d3605b0d782dc24a574c8d">nonnewline</a>, <a href="#a37b2c71be1bd09705bd8e3fa728c6b57">p_ere_exp</a> and <a href="#aee283f9c02a8848c8782c35713aad80c">p_simp_re</a>.</p>

</div>
</div>

### p\_bre() {#aa881669949ccbba0bc595287ea522c31}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void p_bre (struct <a href="/web-llvm/docs/api/structs/parse">parse</a> * p, int end1, int end2)</td>
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



<p>Definition at line 629 of file <a href="/web-llvm/docs/api/files/lib/lib/support/regcomp-c">regcomp.c</a>.</p>


<p>References <a href="#a3994d6de1952ba0c53e9121b0db9042c">DROP</a>, <a href="#aec4cb663b8ad7a53a03298cddd7ed0ed">EAT</a>, <a href="#aed59dfea56910669e8ad0dcef8a2ea8d">EMIT</a>, <a href="#a114e866679b13eadadd097635f4fb10d">HERE</a>, <a href="#ace441594c4bd8da94fd64b1c612ca948">MORE</a>, <a href="/web-llvm/docs/api/files/lib/lib/support/regex2-h/#a2228fd86a118c059a40aa7906b7b9f75">OBOL</a>, <a href="/web-llvm/docs/api/files/lib/lib/support/regex2-h/#a64088e1d592688e933aaf055bada3212">OEOL</a>, <a href="#aee283f9c02a8848c8782c35713aad80c">p_simp_re</a>, <a href="/web-llvm/docs/api/files/lib/lib/support/regex-impl-h/#ab974b0d779831c3f7ba76a70748d7e71">REG_EMPTY</a>, <a href="#aeb49e5164a8e40811cc769c1fd331d66">REQUIRE</a>, <a href="#a2a2a6d570798c3d54c3ba019b07bff5b">SEETWO</a>, <a href="/web-llvm/docs/api/files/lib/lib/support/regex2-h/#a87eb741ccad21cee1dc3830ca3f06a90">USEBOL</a> and <a href="/web-llvm/docs/api/files/lib/lib/support/regex2-h/#a79f50dd10938b851f6d38b7131e2ddd5">USEEOL</a>.</p>


<p>Referenced by <a href="#a94efd6ce730ab2988bfd211af4319873">llvm_regcomp</a> and <a href="#aee283f9c02a8848c8782c35713aad80c">p_simp_re</a>.</p>

</div>
</div>

### p\_count() {#ae3ba3fa6df61a284fc4b4f9267f2c9b0}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">int p_count (struct <a href="/web-llvm/docs/api/structs/parse">parse</a> * p)</td>
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



<p>Definition at line 776 of file <a href="/web-llvm/docs/api/files/lib/lib/support/regcomp-c">regcomp.c</a>.</p>


<p>References <a href="#a86dc91d509b741fbaa09d2797137250f">DUPMAX</a>, <a href="#a378c35ea281e1ad0d8e175cf565e7eb7">GETNEXT</a>, <a href="#ace441594c4bd8da94fd64b1c612ca948">MORE</a>, <a href="#aa25dac8b80db8b8f03732eeb9ca23934">PEEK</a>, <a href="/web-llvm/docs/api/files/lib/lib/support/regex-impl-h/#aa4693ad3584b57edf162fa492f85c16f">REG_BADBR</a> and <a href="#aeb49e5164a8e40811cc769c1fd331d66">REQUIRE</a>.</p>


<p>Referenced by <a href="#a37b2c71be1bd09705bd8e3fa728c6b57">p_ere_exp</a> and <a href="#aee283f9c02a8848c8782c35713aad80c">p_simp_re</a>.</p>

</div>
</div>

### p\_ere() {#ab9fb47c0c5ae241b5de757a26393c11d}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void p_ere (struct <a href="/web-llvm/docs/api/structs/parse">parse</a> * p, int stop)</td>
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



<p>Definition at line 393 of file <a href="/web-llvm/docs/api/files/lib/lib/support/regcomp-c">regcomp.c</a>.</p>


<p>References <a href="#a69e9716ecbad0514d4755e83f2435cce">AHEAD</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/silowercontrolflow-cpp/#a4868c5d81c5ccc98c47aeab6244346a0">assert</a>, <a href="#a66a0070eca9aa4130dec4b380318741a">ASTERN</a>, <a href="#aec4cb663b8ad7a53a03298cddd7ed0ed">EAT</a>, <a href="#aed59dfea56910669e8ad0dcef8a2ea8d">EMIT</a>, <a href="#a114e866679b13eadadd097635f4fb10d">HERE</a>, <a href="#a8e44b28c2ebff8b5b41eedff8a4988a3">INSERT</a>, <a href="#ace441594c4bd8da94fd64b1c612ca948">MORE</a>, <a href="/web-llvm/docs/api/files/lib/lib/support/regex2-h/#a1c30d83b5b72b81505f486ec816f7f50">O_CH</a>, <a href="/web-llvm/docs/api/files/lib/lib/support/regex2-h/#a3540bd5c66f3147b883585e722d658bf">OCH_</a>, <a href="/web-llvm/docs/api/files/lib/lib/support/regex2-h/#af85671ff22b1810567138bbcba708004">OOR1</a>, <a href="/web-llvm/docs/api/files/lib/lib/support/regex2-h/#a3af4f4635fa6eb5d9030afce3f795b0f">OOR2</a>, <a href="#a37b2c71be1bd09705bd8e3fa728c6b57">p_ere_exp</a>, <a href="#aa25dac8b80db8b8f03732eeb9ca23934">PEEK</a>, <a href="/web-llvm/docs/api/files/lib/lib/support/regex-impl-h/#ab974b0d779831c3f7ba76a70748d7e71">REG_EMPTY</a>, <a href="#aeb49e5164a8e40811cc769c1fd331d66">REQUIRE</a>, <a href="#aa27d4f57d0739004f70aba0719150b57">SEE</a> and <a href="#aabbda40c6f9ead8cf0580b32f03afc59">THERE</a>.</p>


<p>Referenced by <a href="#a94efd6ce730ab2988bfd211af4319873">llvm_regcomp</a> and <a href="#a37b2c71be1bd09705bd8e3fa728c6b57">p_ere_exp</a>.</p>

</div>
</div>

### p\_ere\_exp() {#a37b2c71be1bd09705bd8e3fa728c6b57}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void p_ere_exp (struct <a href="/web-llvm/docs/api/structs/parse">parse</a> * p)</td>
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



<p>Definition at line 436 of file <a href="/web-llvm/docs/api/files/lib/lib/support/regcomp-c">regcomp.c</a>.</p>


<p>References <a href="#a69e9716ecbad0514d4755e83f2435cce">AHEAD</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/silowercontrolflow-cpp/#a4868c5d81c5ccc98c47aeab6244346a0">assert</a>, <a href="#a66a0070eca9aa4130dec4b380318741a">ASTERN</a>, <a href="#a388e2f31ac612ec148884cd3143db78c">dupl</a>, <a href="#aec4cb663b8ad7a53a03298cddd7ed0ed">EAT</a>, <a href="#aed59dfea56910669e8ad0dcef8a2ea8d">EMIT</a>, <a href="/web-llvm/docs/api/files/lib/lib/support/lib/support/blake3/blake3-portable-c/#ab5958fad499ed692422c66bb20000a39">g</a>, <a href="#a378c35ea281e1ad0d8e175cf565e7eb7">GETNEXT</a>, <a href="#a114e866679b13eadadd097635f4fb10d">HERE</a>, <a href="#a8e44b28c2ebff8b5b41eedff8a4988a3">INSERT</a>, <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/support/compiler-h/#a9579881de06b1560d242d15171ca1b86">LLVM_FALLTHROUGH</a>, <a href="#ace441594c4bd8da94fd64b1c612ca948">MORE</a>, <a href="#ae8a7b434a5c7a7f1cc2ba29e93870758">MORE2</a>, <a href="#a72f2f2b28c8abc20f687eb02b7af4bcf">MUSTEAT</a>, <a href="#afa19e2eadb751f3599e443d073862a2f">NEXT</a>, <a href="#a517f964af5d3605b0d782dc24a574c8d">nonnewline</a>, <a href="#a4d75c71d09855c3c47f35622b289316f">NPAREN</a>, <a href="/web-llvm/docs/api/files/lib/lib/support/regex2-h/#abe00fc485ef6e08c459df2f283fa5d9f">O_BACK</a>, <a href="/web-llvm/docs/api/files/lib/lib/support/regex2-h/#a1c30d83b5b72b81505f486ec816f7f50">O_CH</a>, <a href="/web-llvm/docs/api/files/lib/lib/support/regex2-h/#ab259df0d57bb496a9d9614b9a6eacc8e">O_PLUS</a>, <a href="/web-llvm/docs/api/files/lib/lib/support/regex2-h/#a909bd2030d6527ad02f8bf552deec559">O_QUEST</a>, <a href="/web-llvm/docs/api/files/lib/lib/support/regex2-h/#af88ba7651db72b3ffcae8c995e2e908e">OANY</a>, <a href="/web-llvm/docs/api/files/lib/lib/support/regex2-h/#ac13f928297b563a52fe41e5fb1cc29a5">OBACK_</a>, <a href="/web-llvm/docs/api/files/lib/lib/support/regex2-h/#a2228fd86a118c059a40aa7906b7b9f75">OBOL</a>, <a href="/web-llvm/docs/api/files/lib/lib/support/regex2-h/#a3540bd5c66f3147b883585e722d658bf">OCH_</a>, <a href="/web-llvm/docs/api/files/lib/lib/support/regex2-h/#a64088e1d592688e933aaf055bada3212">OEOL</a>, <a href="/web-llvm/docs/api/files/lib/lib/support/regex2-h/#a68656a8c7cdec0a5e6112976802801fd">OLPAREN</a>, <a href="/web-llvm/docs/api/files/lib/lib/support/regex2-h/#af85671ff22b1810567138bbcba708004">OOR1</a>, <a href="/web-llvm/docs/api/files/lib/lib/support/regex2-h/#a3af4f4635fa6eb5d9030afce3f795b0f">OOR2</a>, <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/sandboxir/instruction-h/#a0b0cd724f4b7f8589a602b17d6caa1fb">OP</a>, <a href="/web-llvm/docs/api/files/lib/lib/support/regex2-h/#a704503a3445b5e1cfc2ba2032f3fefc7">OPLUS_</a>, <a href="/web-llvm/docs/api/files/lib/lib/support/regex2-h/#a5fa9106fa97c3f33abc44db4f2a4f04a">OQUEST_</a>, <a href="#a72709d6823c4bd388ed9113242119a9b">ordinary</a>, <a href="/web-llvm/docs/api/files/lib/lib/support/regex2-h/#ad105523f8dbc7a2b1a0f6e98bff80ca4">ORPAREN</a>, <a href="#adf84e1164f7b1e4d7711f5d6131491b0">p_bracket</a>, <a href="#ae3ba3fa6df61a284fc4b4f9267f2c9b0">p_count</a>, <a href="#ab9fb47c0c5ae241b5de757a26393c11d">p_ere</a>, <a href="#aa25dac8b80db8b8f03732eeb9ca23934">PEEK</a>, <a href="#a7eb3d11386334057b36a2a29564502ca">PEEK2</a>, <a href="/web-llvm/docs/api/files/lib/lib/support/regex-impl-h/#aa4693ad3584b57edf162fa492f85c16f">REG_BADBR</a>, <a href="/web-llvm/docs/api/files/lib/lib/support/regex-impl-h/#a377356d91031028d3c2d6960b6fb3ac0">REG_BADRPT</a>, <a href="/web-llvm/docs/api/files/lib/lib/support/regex-impl-h/#ad0065762ae9d5301a00eddb6242f104b">REG_EBRACE</a>, <a href="/web-llvm/docs/api/files/lib/lib/support/regex-impl-h/#a3c04bdcb329fb937154b2b47b2c0c2e0">REG_EESCAPE</a>, <a href="/web-llvm/docs/api/files/lib/lib/support/regex-impl-h/#ab974b0d779831c3f7ba76a70748d7e71">REG_EMPTY</a>, <a href="/web-llvm/docs/api/files/lib/lib/support/regex-impl-h/#ad059816a7c4eb7e2193aadc66627a976">REG_EPAREN</a>, <a href="/web-llvm/docs/api/files/lib/lib/support/regex-impl-h/#a93635e62856bab30bab8d0bc400ff07d">REG_ESUBREG</a>, <a href="/web-llvm/docs/api/files/lib/lib/support/regex-impl-h/#ab678ef3b27bf7de2fb82c79cb2cd9d8a">REG_NEWLINE</a>, <a href="#ae6abca5a6c63e69b609228f027a1e7ac">REGINFINITY</a>, <a href="#a919284efeea9e5256497a0778b7fdd75">repeat</a>, <a href="#aeb49e5164a8e40811cc769c1fd331d66">REQUIRE</a>, <a href="#aa27d4f57d0739004f70aba0719150b57">SEE</a>, <a href="#a7dab3e6a7c837ba9fd0209963b8d6d76">SETERROR</a>, <a href="#aabbda40c6f9ead8cf0580b32f03afc59">THERE</a>, <a href="#aeda59df8383196f8a403d52abb973470">THERETHERE</a>, <a href="/web-llvm/docs/api/files/lib/lib/support/regex2-h/#a87eb741ccad21cee1dc3830ca3f06a90">USEBOL</a> and <a href="/web-llvm/docs/api/files/lib/lib/support/regex2-h/#a79f50dd10938b851f6d38b7131e2ddd5">USEEOL</a>.</p>


<p>Referenced by <a href="#ab9fb47c0c5ae241b5de757a26393c11d">p_ere</a>.</p>

</div>
</div>

### p\_simp\_re() {#aee283f9c02a8848c8782c35713aad80c}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">int p_simp_re (struct <a href="/web-llvm/docs/api/structs/parse">parse</a> * p, int starordinary)</td>
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



<p>Definition at line 660 of file <a href="/web-llvm/docs/api/files/lib/lib/support/regcomp-c">regcomp.c</a>.</p>


<p>References <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/silowercontrolflow-cpp/#a4868c5d81c5ccc98c47aeab6244346a0">assert</a>, <a href="#a66a0070eca9aa4130dec4b380318741a">ASTERN</a>, <a href="#a5fea9c0bb049b263b4b609b72ef5322c">BACKSL</a>, <a href="#a388e2f31ac612ec148884cd3143db78c">dupl</a>, <a href="#aec4cb663b8ad7a53a03298cddd7ed0ed">EAT</a>, <a href="#afabd6ecec8f255325e095428354449e0">EATTWO</a>, <a href="#aed59dfea56910669e8ad0dcef8a2ea8d">EMIT</a>, <a href="/web-llvm/docs/api/files/lib/lib/support/lib/support/blake3/blake3-portable-c/#ab5958fad499ed692422c66bb20000a39">g</a>, <a href="#a378c35ea281e1ad0d8e175cf565e7eb7">GETNEXT</a>, <a href="#a114e866679b13eadadd097635f4fb10d">HERE</a>, <a href="#a8e44b28c2ebff8b5b41eedff8a4988a3">INSERT</a>, <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/support/compiler-h/#a9579881de06b1560d242d15171ca1b86">LLVM_FALLTHROUGH</a>, <a href="#ace441594c4bd8da94fd64b1c612ca948">MORE</a>, <a href="#afa19e2eadb751f3599e443d073862a2f">NEXT</a>, <a href="#a517f964af5d3605b0d782dc24a574c8d">nonnewline</a>, <a href="#a4d75c71d09855c3c47f35622b289316f">NPAREN</a>, <a href="/web-llvm/docs/api/files/lib/lib/support/regex2-h/#abe00fc485ef6e08c459df2f283fa5d9f">O_BACK</a>, <a href="/web-llvm/docs/api/files/lib/lib/support/regex2-h/#ab259df0d57bb496a9d9614b9a6eacc8e">O_PLUS</a>, <a href="/web-llvm/docs/api/files/lib/lib/support/regex2-h/#a909bd2030d6527ad02f8bf552deec559">O_QUEST</a>, <a href="/web-llvm/docs/api/files/lib/lib/support/regex2-h/#af88ba7651db72b3ffcae8c995e2e908e">OANY</a>, <a href="/web-llvm/docs/api/files/lib/lib/support/regex2-h/#ac13f928297b563a52fe41e5fb1cc29a5">OBACK_</a>, <a href="/web-llvm/docs/api/files/lib/lib/support/regex2-h/#a68656a8c7cdec0a5e6112976802801fd">OLPAREN</a>, <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/sandboxir/instruction-h/#a0b0cd724f4b7f8589a602b17d6caa1fb">OP</a>, <a href="/web-llvm/docs/api/files/lib/lib/support/regex2-h/#a704503a3445b5e1cfc2ba2032f3fefc7">OPLUS_</a>, <a href="/web-llvm/docs/api/files/lib/lib/support/regex2-h/#a5fa9106fa97c3f33abc44db4f2a4f04a">OQUEST_</a>, <a href="#a72709d6823c4bd388ed9113242119a9b">ordinary</a>, <a href="/web-llvm/docs/api/files/lib/lib/support/regex2-h/#ad105523f8dbc7a2b1a0f6e98bff80ca4">ORPAREN</a>, <a href="#adf84e1164f7b1e4d7711f5d6131491b0">p_bracket</a>, <a href="#aa881669949ccbba0bc595287ea522c31">p_bre</a>, <a href="#ae3ba3fa6df61a284fc4b4f9267f2c9b0">p_count</a>, <a href="#aa25dac8b80db8b8f03732eeb9ca23934">PEEK</a>, <a href="/web-llvm/docs/api/files/lib/lib/support/regex-impl-h/#aa4693ad3584b57edf162fa492f85c16f">REG_BADBR</a>, <a href="/web-llvm/docs/api/files/lib/lib/support/regex-impl-h/#a377356d91031028d3c2d6960b6fb3ac0">REG_BADRPT</a>, <a href="/web-llvm/docs/api/files/lib/lib/support/regex-impl-h/#ad0065762ae9d5301a00eddb6242f104b">REG_EBRACE</a>, <a href="/web-llvm/docs/api/files/lib/lib/support/regex-impl-h/#a3c04bdcb329fb937154b2b47b2c0c2e0">REG_EESCAPE</a>, <a href="/web-llvm/docs/api/files/lib/lib/support/regex-impl-h/#ad059816a7c4eb7e2193aadc66627a976">REG_EPAREN</a>, <a href="/web-llvm/docs/api/files/lib/lib/support/regex-impl-h/#a93635e62856bab30bab8d0bc400ff07d">REG_ESUBREG</a>, <a href="/web-llvm/docs/api/files/lib/lib/support/regex-impl-h/#ab678ef3b27bf7de2fb82c79cb2cd9d8a">REG_NEWLINE</a>, <a href="#ae6abca5a6c63e69b609228f027a1e7ac">REGINFINITY</a>, <a href="#a919284efeea9e5256497a0778b7fdd75">repeat</a>, <a href="#aeb49e5164a8e40811cc769c1fd331d66">REQUIRE</a>, <a href="#a2a2a6d570798c3d54c3ba019b07bff5b">SEETWO</a> and <a href="#a7dab3e6a7c837ba9fd0209963b8d6d76">SETERROR</a>.</p>


<p>Referenced by <a href="#aa881669949ccbba0bc595287ea522c31">p_bre</a>.</p>

</div>
</div>

### p\_str() {#a86427d4d576dd8585a539946c3d662b0}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void p_str (struct <a href="/web-llvm/docs/api/structs/parse">parse</a> * p)</td>
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



<p>Definition at line 611 of file <a href="/web-llvm/docs/api/files/lib/lib/support/regcomp-c">regcomp.c</a>.</p>


<p>References <a href="#a378c35ea281e1ad0d8e175cf565e7eb7">GETNEXT</a>, <a href="#ace441594c4bd8da94fd64b1c612ca948">MORE</a>, <a href="#a72709d6823c4bd388ed9113242119a9b">ordinary</a>, <a href="/web-llvm/docs/api/files/lib/lib/support/regex-impl-h/#ab974b0d779831c3f7ba76a70748d7e71">REG_EMPTY</a> and <a href="#aeb49e5164a8e40811cc769c1fd331d66">REQUIRE</a>.</p>


<p>Referenced by <a href="#a94efd6ce730ab2988bfd211af4319873">llvm_regcomp</a>.</p>

</div>
</div>

### pluscount() {#ab868fc2a09cae3dc9ae25baea08db7a4}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">sopno pluscount (struct <a href="/web-llvm/docs/api/structs/parse">parse</a> * p, struct <a href="/web-llvm/docs/api/structs/re-guts">re_guts</a> * g)</td>
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



<p>Definition at line 1673 of file <a href="/web-llvm/docs/api/files/lib/lib/support/regcomp-c">regcomp.c</a>.</p>


<p>References <a href="/web-llvm/docs/api/files/lib/lib/support/lib/support/blake3/blake3-portable-c/#ab5958fad499ed692422c66bb20000a39">g</a>, <a href="/web-llvm/docs/api/files/lib/lib/support/regex2-h/#ab259df0d57bb496a9d9614b9a6eacc8e">O_PLUS</a>, <a href="/web-llvm/docs/api/files/lib/lib/support/regex2-h/#a434ef202369d0ddf2def41bfeaad210e">OEND</a>, <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/sandboxir/instruction-h/#a0b0cd724f4b7f8589a602b17d6caa1fb">OP</a>, <a href="/web-llvm/docs/api/files/lib/lib/support/regex2-h/#a704503a3445b5e1cfc2ba2032f3fefc7">OPLUS_</a> and <a href="/web-llvm/docs/api/files/lib/lib/support/regex2-h/#acd206907b0132fc600321a23e82aee78">REGEX_BAD</a>.</p>


<p>Referenced by <a href="#a94efd6ce730ab2988bfd211af4319873">llvm_regcomp</a>.</p>

</div>
</div>

### repeat() {#a919284efeea9e5256497a0778b7fdd75}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void repeat (struct <a href="/web-llvm/docs/api/structs/parse">parse</a> * p, <a href="/web-llvm/docs/api/files/lib/lib/support/regex2-h/#a1934207945a1bf71e1355e13cebc601a">sopno</a> start, int from, int to)</td>
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



<p>Definition at line 1109 of file <a href="/web-llvm/docs/api/files/lib/lib/support/regcomp-c">regcomp.c</a>.</p>


<p>References <a href="#a69e9716ecbad0514d4755e83f2435cce">AHEAD</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/silowercontrolflow-cpp/#a4868c5d81c5ccc98c47aeab6244346a0">assert</a>, <a href="#a66a0070eca9aa4130dec4b380318741a">ASTERN</a>, <a href="#a3994d6de1952ba0c53e9121b0db9042c">DROP</a>, <a href="#a388e2f31ac612ec148884cd3143db78c">dupl</a>, <a href="#aed59dfea56910669e8ad0dcef8a2ea8d">EMIT</a>, <a href="#a114e866679b13eadadd097635f4fb10d">HERE</a>, <a href="#a12c2040f25d8e3a7b9e1c2024c618cb6">INF</a>, <a href="#a8e44b28c2ebff8b5b41eedff8a4988a3">INSERT</a>, <a href="#a01bd739644e8d3cbbb80f37f6ddb8b0e">MAP</a>, <a href="#a0240ac851181b84ac374872dc5434ee4">N</a>, <a href="/web-llvm/docs/api/files/lib/lib/support/regex2-h/#a1c30d83b5b72b81505f486ec816f7f50">O_CH</a>, <a href="/web-llvm/docs/api/files/lib/lib/support/regex2-h/#ab259df0d57bb496a9d9614b9a6eacc8e">O_PLUS</a>, <a href="/web-llvm/docs/api/files/lib/lib/support/regex2-h/#a3540bd5c66f3147b883585e722d658bf">OCH_</a>, <a href="/web-llvm/docs/api/files/lib/lib/support/regex2-h/#af85671ff22b1810567138bbcba708004">OOR1</a>, <a href="/web-llvm/docs/api/files/lib/lib/support/regex2-h/#a3af4f4635fa6eb5d9030afce3f795b0f">OOR2</a>, <a href="/web-llvm/docs/api/files/lib/lib/support/regex2-h/#a704503a3445b5e1cfc2ba2032f3fefc7">OPLUS_</a>, <a href="/web-llvm/docs/api/files/lib/lib/support/regex-impl-h/#a284ab151886dcb8b211f21a8a0d36d78">REG_ASSERT</a>, <a href="#acf94cdcef32661117a14bbb806832437">REP</a>, <a href="#a919284efeea9e5256497a0778b7fdd75">repeat</a>, <a href="#a7dab3e6a7c837ba9fd0209963b8d6d76">SETERROR</a>, <a href="#aabbda40c6f9ead8cf0580b32f03afc59">THERE</a> and <a href="#aeda59df8383196f8a403d52abb973470">THERETHERE</a>.</p>


<p>Referenced by <a href="#a37b2c71be1bd09705bd8e3fa728c6b57">p_ere_exp</a>, <a href="#aee283f9c02a8848c8782c35713aad80c">p_simp_re</a> and <a href="#a919284efeea9e5256497a0778b7fdd75">repeat</a>.</p>

</div>
</div>

### samesets() {#a0a11d04bd61f8c45fc80d7630133cf40}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">int samesets (struct <a href="/web-llvm/docs/api/structs/re-guts">re_guts</a> * g, int c1, int c2)</td>
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



<p>Definition at line 1404 of file <a href="/web-llvm/docs/api/files/lib/lib/support/regcomp-c">regcomp.c</a>.</p>


<p>Reference <a href="/web-llvm/docs/api/files/lib/lib/support/lib/support/blake3/blake3-portable-c/#ab5958fad499ed692422c66bb20000a39">g</a>.</p>


<p>Referenced by <a href="#a7f555d714dea35fa2b3e00c2e727d0af">categorize</a>.</p>

</div>
</div>

### seterr() {#af6d02bc5e86c8d1b90cf67aaa719b127}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">int seterr (struct <a href="/web-llvm/docs/api/structs/parse">parse</a> * p, int e)</td>
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



<p>Definition at line 1179 of file <a href="/web-llvm/docs/api/files/lib/lib/support/regcomp-c">regcomp.c</a>.</p>


<p>Reference <a href="#a8eb1ab58fe7e084dbbdcb71c0ecf4c9c">nuls</a>.</p>

</div>
</div>

### stripsnug() {#a0b3b7588a93de41b3dd6640e62787e2e}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void stripsnug (struct <a href="/web-llvm/docs/api/structs/parse">parse</a> * p, struct <a href="/web-llvm/docs/api/structs/re-guts">re_guts</a> * g)</td>
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



<p>Definition at line 1569 of file <a href="/web-llvm/docs/api/files/lib/lib/support/regcomp-c">regcomp.c</a>.</p>


<p>References <a href="/web-llvm/docs/api/files/lib/lib/support/lib/support/blake3/blake3-portable-c/#ab5958fad499ed692422c66bb20000a39">g</a>, <a href="/web-llvm/docs/api/files/lib/lib/support/regex-impl-h/#ae0ee85477e8756f1cf2d7fab21e56235">REG_ESPACE</a> and <a href="#a7dab3e6a7c837ba9fd0209963b8d6d76">SETERROR</a>.</p>


<p>Referenced by <a href="#a94efd6ce730ab2988bfd211af4319873">llvm_regcomp</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Variables

### cclasses {#a6dbc3d533054da9187c049907f5dd9c4}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">struct cclass cclasses[]</td>
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
	{ "alnum",	"ABCDEFGHIJKLMNOPQRSTUVWXYZabcdefghijklmnopqrstuvwxyz\
0123456789",				""} ,
	{ "alpha",	"ABCDEFGHIJKLMNOPQRSTUVWXYZabcdefghijklmnopqrstuvwxyz",
					""} ,
	{ "blank",	" \t",		""} ,
	{ "cntrl",	"\007\b\t\n\v\f\r\1\2\3\4\5\6\16\17\20\21\22\23\24\
\25\26\27\30\31\32\33\34\35\36\37\177",	""} ,
	{ "digit",	"0123456789",	""} ,
	{ "graph",	"ABCDEFGHIJKLMNOPQRSTUVWXYZabcdefghijklmnopqrstuvwxyz\
0123456789!\"#$%&amp;'()*+,-./:;&lt;=&gt;?@[\\]^<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/hexagon/lib/target/hexagon/mctargetdesc/hexagonmccodeemitter-cpp/#ae4dfd7b0d66121016d6466d2ff10e8ba">_</a>`{|}~",
					""} ,
	{ "lower",	"abcdefghijklmnopqrstuvwxyz",
					""} ,
	{ "print",	"ABCDEFGHIJKLMNOPQRSTUVWXYZabcdefghijklmnopqrstuvwxyz\
0123456789!\"#$%&amp;'()*+,-./:;&lt;=&gt;?@[\\]^<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/hexagon/lib/target/hexagon/mctargetdesc/hexagonmccodeemitter-cpp/#ae4dfd7b0d66121016d6466d2ff10e8ba">_</a>`{|}~ ",
					""} ,
	{ "punct",	"!\"#$%&amp;'()*+,-./:;&lt;=&gt;?@[\\]^_`{|}~",
					""} ,
	{ "space",	"\t\n\v\f\r ",	""} ,
	{ "upper",	"ABCDEFGHIJKLMNOPQRSTUVWXYZ",
					""} ,
	{ "xdigit",	"0123456789ABCDEFabcdef",
					""} ,
	{ NULL,		0,		"" }
}
</div>
</dd>
</dl>

<p>Definition at line 83 of file <a href="/web-llvm/docs/api/files/lib/lib/support/regcomp-c">regcomp.c</a>.</p>


<p>Referenced by <a href="#a41c76f49aa45896e78b801c95970f43b">p_b_cclass</a>.</p>

</div>
</div>

### cnames {#a6dda07b235599739319ccc11dadeca0d}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">struct cname cnames[]</td>
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



<p>Definition at line 186 of file <a href="/web-llvm/docs/api/files/lib/lib/support/regcomp-c">regcomp.c</a>.</p>


<p>Referenced by <a href="#a21e3f305c59ef8746b818db2f47b3dc4">p_b_coll_elem</a>.</p>

</div>
</div>

### nuls {#a8eb1ab58fe7e084dbbdcb71c0ecf4c9c}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">char nuls[10]</td>
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



<p>Definition at line 244 of file <a href="/web-llvm/docs/api/files/lib/lib/support/regcomp-c">regcomp.c</a>.</p>


<p>Referenced by <a href="#af6d02bc5e86c8d1b90cf67aaa719b127">seterr</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Macro Definitions

### AHEAD {#a69e9716ecbad0514d4755e83f2435cce}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">#define AHEAD(pos)&nbsp;&nbsp;&nbsp;<a href="#ae26e3e26f2a397a734f6b8fac059b356">dofwd</a>(p, pos, <a href="#a114e866679b13eadadd097635f4fb10d">HERE</a>()-(pos))</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 269 of file <a href="/web-llvm/docs/api/files/lib/lib/support/regcomp-c">regcomp.c</a>.</p>


<p>Referenced by <a href="#ab9fb47c0c5ae241b5de757a26393c11d">p_ere</a>, <a href="#a37b2c71be1bd09705bd8e3fa728c6b57">p_ere_exp</a> and <a href="#a919284efeea9e5256497a0778b7fdd75">repeat</a>.</p>

</div>
</div>

### ASTERN {#a66a0070eca9aa4130dec4b380318741a}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">#define ASTERN(sop, pos)&nbsp;&nbsp;&nbsp;<a href="#aed59dfea56910669e8ad0dcef8a2ea8d">EMIT</a>(<a href="/web-llvm/docs/api/files/lib/lib/support/regex2-h/#a06b705baf08297be667616dcfd9b63a6">sop</a>, <a href="#a114e866679b13eadadd097635f4fb10d">HERE</a>()-pos)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 270 of file <a href="/web-llvm/docs/api/files/lib/lib/support/regcomp-c">regcomp.c</a>.</p>


<p>Referenced by <a href="#ab9fb47c0c5ae241b5de757a26393c11d">p_ere</a>, <a href="#a37b2c71be1bd09705bd8e3fa728c6b57">p_ere_exp</a>, <a href="#aee283f9c02a8848c8782c35713aad80c">p_simp_re</a> and <a href="#a919284efeea9e5256497a0778b7fdd75">repeat</a>.</p>

</div>
</div>

### BACKSL {#a5fea9c0bb049b263b4b609b72ef5322c}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">#define BACKSL&nbsp;&nbsp;&nbsp;(1&lt;&lt;CHAR_BIT)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 669 of file <a href="/web-llvm/docs/api/files/lib/lib/support/regcomp-c">regcomp.c</a>.</p>


<p>Referenced by <a href="#aee283f9c02a8848c8782c35713aad80c">p_simp_re</a>.</p>

</div>
</div>

### DROP {#a3994d6de1952ba0c53e9121b0db9042c}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">#define DROP(n)&nbsp;&nbsp;&nbsp;(p-&gt;slen -= (n))</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 274 of file <a href="/web-llvm/docs/api/files/lib/lib/support/regcomp-c">regcomp.c</a>.</p>


<p>Referenced by <a href="#aa881669949ccbba0bc595287ea522c31">p_bre</a> and <a href="#a919284efeea9e5256497a0778b7fdd75">repeat</a>.</p>

</div>
</div>

### DUPMAX {#a86dc91d509b741fbaa09d2797137250f}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">#define DUPMAX&nbsp;&nbsp;&nbsp;255</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 279 of file <a href="/web-llvm/docs/api/files/lib/lib/support/regcomp-c">regcomp.c</a>.</p>


<p>Referenced by <a href="#ae3ba3fa6df61a284fc4b4f9267f2c9b0">p_count</a>.</p>

</div>
</div>

### EAT {#aec4cb663b8ad7a53a03298cddd7ed0ed}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">#define EAT(c)&nbsp;&nbsp;&nbsp;((<a href="#aa27d4f57d0739004f70aba0719150b57">SEE</a>(c)) ? (<a href="#afa19e2eadb751f3599e443d073862a2f">NEXT</a>(), 1) : 0)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 256 of file <a href="/web-llvm/docs/api/files/lib/lib/support/regcomp-c">regcomp.c</a>.</p>


<p>Referenced by <a href="#a979bf5dd2e011f08e36f469df553441b">p_b_term</a>, <a href="#adf84e1164f7b1e4d7711f5d6131491b0">p_bracket</a>, <a href="#aa881669949ccbba0bc595287ea522c31">p_bre</a>, <a href="#ab9fb47c0c5ae241b5de757a26393c11d">p_ere</a>, <a href="#a37b2c71be1bd09705bd8e3fa728c6b57">p_ere_exp</a> and <a href="#aee283f9c02a8848c8782c35713aad80c">p_simp_re</a>.</p>

</div>
</div>

### EATTWO {#afabd6ecec8f255325e095428354449e0}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">#define EATTWO(a, b)&nbsp;&nbsp;&nbsp;((<a href="#a2a2a6d570798c3d54c3ba019b07bff5b">SEETWO</a>(a, b)) ? (<a href="#a0c4c28b39436d006b6efc2d8e796d784">NEXT2</a>(), 1) : 0)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 257 of file <a href="/web-llvm/docs/api/files/lib/lib/support/regcomp-c">regcomp.c</a>.</p>


<p>Referenced by <a href="#ac24cfdb8cf256d8fc31d63ae5931db44">p_b_symbol</a>, <a href="#a979bf5dd2e011f08e36f469df553441b">p_b_term</a> and <a href="#aee283f9c02a8848c8782c35713aad80c">p_simp_re</a>.</p>

</div>
</div>

### EMIT {#aed59dfea56910669e8ad0dcef8a2ea8d}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">#define EMIT(op, sopnd)&nbsp;&nbsp;&nbsp;<a href="#a42f8fec9a1fa9d471abf77a8eead0da1">doemit</a>(p, (<a href="/web-llvm/docs/api/files/lib/lib/support/regex2-h/#a06b705baf08297be667616dcfd9b63a6">sop</a>)(<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/hexagon/hexagonbittracker-cpp/#a0ee73ba17c3a2cb54752905e99d77357">op</a>), (size_t)(sopnd))</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 267 of file <a href="/web-llvm/docs/api/files/lib/lib/support/regcomp-c">regcomp.c</a>.</p>


<p>Referenced by <a href="#ab437a1156833e5395a0102102cf93c6f">doinsert</a>, <a href="#a94efd6ce730ab2988bfd211af4319873">llvm_regcomp</a>, <a href="#a72709d6823c4bd388ed9113242119a9b">ordinary</a>, <a href="#adf84e1164f7b1e4d7711f5d6131491b0">p_bracket</a>, <a href="#aa881669949ccbba0bc595287ea522c31">p_bre</a>, <a href="#ab9fb47c0c5ae241b5de757a26393c11d">p_ere</a>, <a href="#a37b2c71be1bd09705bd8e3fa728c6b57">p_ere_exp</a>, <a href="#aee283f9c02a8848c8782c35713aad80c">p_simp_re</a> and <a href="#a919284efeea9e5256497a0778b7fdd75">repeat</a>.</p>

</div>
</div>

### GETNEXT {#a378c35ea281e1ad0d8e175cf565e7eb7}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">#define GETNEXT()&nbsp;&nbsp;&nbsp;(*p-&gt;next++)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 261 of file <a href="/web-llvm/docs/api/files/lib/lib/support/regcomp-c">regcomp.c</a>.</p>


<p>Referenced by <a href="#ac24cfdb8cf256d8fc31d63ae5931db44">p_b_symbol</a>, <a href="#ae3ba3fa6df61a284fc4b4f9267f2c9b0">p_count</a>, <a href="#a37b2c71be1bd09705bd8e3fa728c6b57">p_ere_exp</a>, <a href="#aee283f9c02a8848c8782c35713aad80c">p_simp_re</a> and <a href="#a86427d4d576dd8585a539946c3d662b0">p_str</a>.</p>

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
<td class="doxyMemberName">#define GOODFLAGS(f)&nbsp;&nbsp;&nbsp;((f)&amp;~<a href="/web-llvm/docs/api/files/lib/lib/support/regex-impl-h/#a0f4eb1f7553209185de343c875ca5142">REG_DUMP</a>)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 303 of file <a href="/web-llvm/docs/api/files/lib/lib/support/regcomp-c">regcomp.c</a>.</p>


<p>Referenced by <a href="#a94efd6ce730ab2988bfd211af4319873">llvm_regcomp</a>.</p>

</div>
</div>

### HERE {#a114e866679b13eadadd097635f4fb10d}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">#define HERE()&nbsp;&nbsp;&nbsp;(p-&gt;slen)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 271 of file <a href="/web-llvm/docs/api/files/lib/lib/support/regcomp-c">regcomp.c</a>.</p>


<p>Referenced by <a href="#ab437a1156833e5395a0102102cf93c6f">doinsert</a>, <a href="#a388e2f31ac612ec148884cd3143db78c">dupl</a>, <a href="#aa881669949ccbba0bc595287ea522c31">p_bre</a>, <a href="#ab9fb47c0c5ae241b5de757a26393c11d">p_ere</a>, <a href="#a37b2c71be1bd09705bd8e3fa728c6b57">p_ere_exp</a>, <a href="#aee283f9c02a8848c8782c35713aad80c">p_simp_re</a> and <a href="#a919284efeea9e5256497a0778b7fdd75">repeat</a>.</p>

</div>
</div>

### INF {#a12c2040f25d8e3a7b9e1c2024c618cb6}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">#define INF&nbsp;&nbsp;&nbsp;3</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 1116 of file <a href="/web-llvm/docs/api/files/lib/lib/support/regcomp-c">regcomp.c</a>.</p>


<p>Referenced by <a href="#a919284efeea9e5256497a0778b7fdd75">repeat</a>.</p>

</div>
</div>

### INSERT {#a8e44b28c2ebff8b5b41eedff8a4988a3}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">#define INSERT(op, pos)&nbsp;&nbsp;&nbsp;<a href="#ab437a1156833e5395a0102102cf93c6f">doinsert</a>(p, (<a href="/web-llvm/docs/api/files/lib/lib/support/regex2-h/#a06b705baf08297be667616dcfd9b63a6">sop</a>)(<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/hexagon/hexagonbittracker-cpp/#a0ee73ba17c3a2cb54752905e99d77357">op</a>), <a href="#a114e866679b13eadadd097635f4fb10d">HERE</a>()-(pos)+1, pos)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 268 of file <a href="/web-llvm/docs/api/files/lib/lib/support/regcomp-c">regcomp.c</a>.</p>


<p>Referenced by <a href="#ab9fb47c0c5ae241b5de757a26393c11d">p_ere</a>, <a href="#a37b2c71be1bd09705bd8e3fa728c6b57">p_ere_exp</a>, <a href="#aee283f9c02a8848c8782c35713aad80c">p_simp_re</a> and <a href="#a919284efeea9e5256497a0778b7fdd75">repeat</a>.</p>

</div>
</div>

### MAP {#a01bd739644e8d3cbbb80f37f6ddb8b0e}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">#define MAP(n)&nbsp;&nbsp;&nbsp;(((n) &lt;= 1) ? (n) : ((n) == <a href="#ae6abca5a6c63e69b609228f027a1e7ac">REGINFINITY</a>) ? <a href="#a12c2040f25d8e3a7b9e1c2024c618cb6">INF</a> : <a href="#a0240ac851181b84ac374872dc5434ee4">N</a>)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 1118 of file <a href="/web-llvm/docs/api/files/lib/lib/support/regcomp-c">regcomp.c</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/files/lib/lib/analysis/memoryssa-cpp/#a930e3a524f031bdb14fe281e4eff4219">checkClobberSanity</a> and <a href="#a919284efeea9e5256497a0778b7fdd75">repeat</a>.</p>

</div>
</div>

### MORE {#ace441594c4bd8da94fd64b1c612ca948}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">#define MORE()&nbsp;&nbsp;&nbsp;(p-&gt;end - p-&gt;next &gt; 0)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 252 of file <a href="/web-llvm/docs/api/files/lib/lib/support/regcomp-c">regcomp.c</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/classes/llvm/combiner/#a4a3a16e02e0d2cbe78acd2dcab7dd388">llvm::Combiner::combineMachineInstrs</a>, <a href="/web-llvm/docs/api/structs/anonymous-machineoutliner-cpp-/machineoutliner/#a474b6a5a9e0e575d9d21d20e8b810ee7">anonymous{MachineOutliner.cpp}::MachineOutliner::emitInstrCountChangedRemark</a>, <a href="/web-llvm/docs/api/structs/anonymous-machineoutliner-cpp-/machineoutliner/#a9f5104a534795f587fc2e9ec2e6a0c03">anonymous{MachineOutliner.cpp}::MachineOutliner::emitOutlinedFunctionRemark</a>, <a href="/web-llvm/docs/api/files/lib/lib/codegen/machineoutliner-cpp/#ab72f6c46cf154205814197e0e93b69f7">INITIALIZE_PASS</a>, <a href="#a41c76f49aa45896e78b801c95970f43b">p_b_cclass</a>, <a href="#a21e3f305c59ef8746b818db2f47b3dc4">p_b_coll_elem</a>, <a href="#ac24cfdb8cf256d8fc31d63ae5931db44">p_b_symbol</a>, <a href="#a979bf5dd2e011f08e36f469df553441b">p_b_term</a>, <a href="#adf84e1164f7b1e4d7711f5d6131491b0">p_bracket</a>, <a href="#aa881669949ccbba0bc595287ea522c31">p_bre</a>, <a href="#ae3ba3fa6df61a284fc4b4f9267f2c9b0">p_count</a>, <a href="#ab9fb47c0c5ae241b5de757a26393c11d">p_ere</a>, <a href="#a37b2c71be1bd09705bd8e3fa728c6b57">p_ere_exp</a>, <a href="#aee283f9c02a8848c8782c35713aad80c">p_simp_re</a>, <a href="#a86427d4d576dd8585a539946c3d662b0">p_str</a>, <a href="/web-llvm/docs/api/files/lib/lib/codegen/lib/codegen/globalisel/utils-cpp/#a7e0c11d01ca1556ffc05daf859073e51">reportGISelDiagnostic</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a0e2b71d462b14e085a6a1d4b0a1d5e82">llvm::reportGISelFailure</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a7b804856a2e313abeef6f32c3c6f61eb">llvm::reportGISelFailure</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#aff9971cf6e5729588fe9a1ee94bb4fce">llvm::reportGISelWarning</a>, <a href="/web-llvm/docs/api/classes/llvm/legalizer/#a356f9de405c2904f7ad73659a2f378a0">llvm::Legalizer::runOnMachineFunction</a>, <a href="/web-llvm/docs/api/classes/llvm/instructionselect/#a07f4133008c7c11a0154735071ffcc19">llvm::InstructionSelect::selectMachineFunction</a> and <a href="/web-llvm/docs/api/classes/llvm/mirprofileloader/#ada46e031da560591716a22f4ef0d3a74">llvm::MIRProfileLoader::setInitVals</a>.</p>

</div>
</div>

### MORE2 {#ae8a7b434a5c7a7f1cc2ba29e93870758}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">#define MORE2()&nbsp;&nbsp;&nbsp;(p-&gt;end - p-&gt;next &gt; 1)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 253 of file <a href="/web-llvm/docs/api/files/lib/lib/support/regcomp-c">regcomp.c</a>.</p>


<p>Referenced by <a href="#a979bf5dd2e011f08e36f469df553441b">p_b_term</a> and <a href="#a37b2c71be1bd09705bd8e3fa728c6b57">p_ere_exp</a>.</p>

</div>
</div>

### MUSTEAT {#a72f2f2b28c8abc20f687eb02b7af4bcf}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">#define MUSTEAT(c, e)&nbsp;&nbsp;&nbsp;(<a href="#aeb49e5164a8e40811cc769c1fd331d66">REQUIRE</a>(<a href="#ace441594c4bd8da94fd64b1c612ca948">MORE</a>() &amp;&amp; <a href="#a378c35ea281e1ad0d8e175cf565e7eb7">GETNEXT</a>() == (c), e))</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 265 of file <a href="/web-llvm/docs/api/files/lib/lib/support/regcomp-c">regcomp.c</a>.</p>


<p>Referenced by <a href="#adf84e1164f7b1e4d7711f5d6131491b0">p_bracket</a> and <a href="#a37b2c71be1bd09705bd8e3fa728c6b57">p_ere_exp</a>.</p>

</div>
</div>

### MUSTNOTSEE {#a9daf6c2c089e7dcee7335b7e8e7a9a27}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">#define MUSTNOTSEE(c, e)&nbsp;&nbsp;&nbsp;(<a href="#aeb49e5164a8e40811cc769c1fd331d66">REQUIRE</a>(!<a href="#ace441594c4bd8da94fd64b1c612ca948">MORE</a>() || <a href="#aa25dac8b80db8b8f03732eeb9ca23934">PEEK</a>() != (c), e))</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 266 of file <a href="/web-llvm/docs/api/files/lib/lib/support/regcomp-c">regcomp.c</a>.</p>

</div>
</div>

### MUSTSEE {#a0b21bf0345d6bc495eb91b8ca338f66c}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">#define MUSTSEE(c, e)&nbsp;&nbsp;&nbsp;(<a href="#aeb49e5164a8e40811cc769c1fd331d66">REQUIRE</a>(<a href="#ace441594c4bd8da94fd64b1c612ca948">MORE</a>() &amp;&amp; <a href="#aa25dac8b80db8b8f03732eeb9ca23934">PEEK</a>() == (c), e))</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 264 of file <a href="/web-llvm/docs/api/files/lib/lib/support/regcomp-c">regcomp.c</a>.</p>

</div>
</div>

### N {#a0240ac851181b84ac374872dc5434ee4}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">#define N&nbsp;&nbsp;&nbsp;2</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 1115 of file <a href="/web-llvm/docs/api/files/lib/lib/support/regcomp-c">regcomp.c</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/structs/llvm/aamdnodes/#a8daf5329dec4f1f687b9ed9bcaf9f113">llvm::AAMDNodes::AAMDNodes</a>, <a href="/web-llvm/docs/api/classes/llvm/orc/objectlinkinglayer/#a972e1603fbdf3e039431a4bf34df6e03">llvm::orc::ObjectLinkingLayer::add</a>, <a href="/web-llvm/docs/api/classes/llvm/registry/#af1684cbe4fb121267dd3ae2f222f5086">llvm::Registry&lt; GCMetadataPrinter &gt;::add_node</a>, <a href="/web-llvm/docs/api/structs/llvm/x86operand/#a3fb809c95f07fa9985fef7e95cf551c8">llvm::X86Operand::addAbsMemOperands</a>, <a href="/web-llvm/docs/api/classes/anonymous-mipsasmparser-cpp-/mipsoperand/#a1c9da2c1517144cce67c080d549f24fb">anonymous{MipsAsmParser.cpp}::MipsOperand::addACC64DSPAsmRegOperands</a>, <a href="/web-llvm/docs/api/classes/anonymous-armasmparser-cpp-/armoperand/#aff551f6c57e2bda70f7c58294b662d04">anonymous{ARMAsmParser.cpp}::ARMOperand::addAddrMode2Operands</a>, <a href="/web-llvm/docs/api/classes/anonymous-armasmparser-cpp-/armoperand/#a29b2705aeee49d31d232c5ab440f7877">anonymous{ARMAsmParser.cpp}::ARMOperand::addAddrMode3Operands</a>, <a href="/web-llvm/docs/api/classes/anonymous-armasmparser-cpp-/armoperand/#aeca538a61ece736dfa6ca68bfcebb401">anonymous{ARMAsmParser.cpp}::ARMOperand::addAddrMode5FP16Operands</a>, <a href="/web-llvm/docs/api/classes/anonymous-armasmparser-cpp-/armoperand/#a6b2100e3595ebc052f71501e05bf9ef4">anonymous{ARMAsmParser.cpp}::ARMOperand::addAddrMode5Operands</a>, <a href="/web-llvm/docs/api/classes/anonymous-m68kasmparser-cpp-/m68koperand/#a6237dab111d9b5ff6d9d9df8f71807ea">anonymous{M68kAsmParser.cpp}::M68kOperand::addAddrOperands</a>, <a href="/web-llvm/docs/api/classes/anonymous-aarch64asmparser-cpp-/aarch64operand/#a575b6ba91338eaa06fd666dad94bc35c">anonymous{AArch64AsmParser.cpp}::AArch64Operand::addAdrLabelOperands</a>, <a href="/web-llvm/docs/api/classes/anonymous-armasmparser-cpp-/armoperand/#af6a434a23522485bf0d986faf12ee9f8">anonymous{ARMAsmParser.cpp}::ARMOperand::addAdrLabelOperands</a>, <a href="/web-llvm/docs/api/classes/anonymous-aarch64asmparser-cpp-/aarch64operand/#ab44f4b2113b7a3876bd7e61758319c6f">anonymous{AArch64AsmParser.cpp}::AArch64Operand::addAdrpLabelOperands</a>, <a href="/web-llvm/docs/api/classes/anonymous-mipsasmparser-cpp-/mipsoperand/#a97ec632b3a5e002b1d3d99b8b79c7883">anonymous{MipsAsmParser.cpp}::MipsOperand::addAFGR64AsmRegOperands</a>, <a href="/web-llvm/docs/api/classes/anonymous-armasmparser-cpp-/armoperand/#abaa71e0b8fa6231f0723d2cc4fd35496">anonymous{ARMAsmParser.cpp}::ARMOperand::addAlignedMemory16Operands</a>, <a href="/web-llvm/docs/api/classes/anonymous-armasmparser-cpp-/armoperand/#a7299cf9813b81c006ab4b7931d387ed6">anonymous{ARMAsmParser.cpp}::ARMOperand::addAlignedMemory32Operands</a>, <a href="/web-llvm/docs/api/classes/anonymous-armasmparser-cpp-/armoperand/#aac1011ef63122cc3bb552d260cfa5c65">anonymous{ARMAsmParser.cpp}::ARMOperand::addAlignedMemory64Operands</a>, <a href="/web-llvm/docs/api/classes/anonymous-armasmparser-cpp-/armoperand/#a7593b3ca6bb839efb503cb9cf7ebaab6">anonymous{ARMAsmParser.cpp}::ARMOperand::addAlignedMemory64or128Operands</a>, <a href="/web-llvm/docs/api/classes/anonymous-armasmparser-cpp-/armoperand/#a6f0e634d4d9455ffde9266a5619b0d21">anonymous{ARMAsmParser.cpp}::ARMOperand::addAlignedMemory64or128or256Operands</a>, <a href="/web-llvm/docs/api/classes/anonymous-armasmparser-cpp-/armoperand/#ae3d3cadf9e0b4a15f550c916bcaf9c45">anonymous{ARMAsmParser.cpp}::ARMOperand::addAlignedMemoryNoneOperands</a>, <a href="/web-llvm/docs/api/classes/anonymous-armasmparser-cpp-/armoperand/#a548a79ef6ddd55b914e259d2f957c632">anonymous{ARMAsmParser.cpp}::ARMOperand::addAlignedMemoryOperands</a>, <a href="/web-llvm/docs/api/classes/anonymous-armasmparser-cpp-/armoperand/#ab5034e33be4df547034085fd56f5ef7a">anonymous{ARMAsmParser.cpp}::ARMOperand::addAM2OffsetImmOperands</a>, <a href="/web-llvm/docs/api/classes/anonymous-armasmparser-cpp-/armoperand/#a9e51c04c7eea24160648528b9e2867c7">anonymous{ARMAsmParser.cpp}::ARMOperand::addAM3OffsetOperands</a>, <a href="/web-llvm/docs/api/classes/llvm/instruction/#a9a7c63edb94ce4fab2a5bb34dbf6079a">llvm::Instruction::addAnnotationMetadata</a>, <a href="/web-llvm/docs/api/classes/llvm/instruction/#a6762e9e611c29b13a5c94bf8488fe798">llvm::Instruction::addAnnotationMetadata</a>, <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/ipo/functionattrs-cpp/#a5c54a34ab3372d252d9e9341bdff3dd3">addArgumentAttrs</a>, <a href="/web-llvm/docs/api/classes/anonymous-m68kasmparser-cpp-/m68koperand/#a0e5767e266948d2da6a968bed7c234af">anonymous{M68kAsmParser.cpp}::M68kOperand::addARIDOperands</a>, <a href="/web-llvm/docs/api/classes/anonymous-m68kasmparser-cpp-/m68koperand/#a8b36bcd58d06ed763e3ff606ef787d61">anonymous{M68kAsmParser.cpp}::M68kOperand::addARIIOperands</a>, <a href="/web-llvm/docs/api/classes/anonymous-m68kasmparser-cpp-/m68koperand/#aef9678d5d40dc29d922920d97fe2e108">anonymous{M68kAsmParser.cpp}::M68kOperand::addARIOperands</a>, <a href="/web-llvm/docs/api/classes/anonymous-m68kasmparser-cpp-/m68koperand/#aa408301e2671cf7040584011da1ca4ee">anonymous{M68kAsmParser.cpp}::M68kOperand::addARIPDOperands</a>, <a href="/web-llvm/docs/api/classes/anonymous-m68kasmparser-cpp-/m68koperand/#a2a6d1110d5731551b614fc041a5e100e">anonymous{M68kAsmParser.cpp}::M68kOperand::addARIPIOperands</a>, <a href="/web-llvm/docs/api/classes/anonymous-armasmparser-cpp-/armoperand/#a7982bf777e9fb571e0e0c71199915572">anonymous{ARMAsmParser.cpp}::ARMOperand::addARMBranchTargetOperands</a>, <a href="/web-llvm/docs/api/classes/anonymous-sparcasmparser-cpp-/sparcoperand/#a139c989aebeb47528c3f50d9c97f55e4">anonymous{SparcAsmParser.cpp}::SparcOperand::addASITagOperands</a>, <a href="/web-llvm/docs/api/structs/llvm/x86operand/#a0f7ff37427c7091f644b497d94f4fcff">llvm::X86Operand::addAVX512RCOperands</a>, <a href="/web-llvm/docs/api/classes/anonymous-armasmparser-cpp-/armoperand/#a10e5ca2afe28615ccce1a071f17d25c1">anonymous{ARMAsmParser.cpp}::ARMOperand::addBankedRegOperands</a>, <a href="/web-llvm/docs/api/classes/anonymous-aarch64asmparser-cpp-/aarch64operand/#a48edf5070960702e2bdb4809a21e342e">anonymous{AArch64AsmParser.cpp}::AArch64Operand::addBarriernXSOperands</a>, <a href="/web-llvm/docs/api/classes/anonymous-aarch64asmparser-cpp-/aarch64operand/#a591114c0fea921bbe5364d31fbef1b64">anonymous{AArch64AsmParser.cpp}::AArch64Operand::addBarrierOperands</a>, <a href="/web-llvm/docs/api/classes/anonymous-systemzasmparser-cpp-/systemzoperand/#a9b9382a69efae30312157561c9935e47">anonymous{SystemZAsmParser.cpp}::SystemZOperand::addBDAddrOperands</a>, <a href="/web-llvm/docs/api/classes/anonymous-systemzasmparser-cpp-/systemzoperand/#ac0c2fe3c329a0af3333996cd5f459941">anonymous{SystemZAsmParser.cpp}::SystemZOperand::addBDLAddrOperands</a>, <a href="/web-llvm/docs/api/classes/anonymous-systemzasmparser-cpp-/systemzoperand/#a94365cb7b08e65f8c3939b8c6403137c">anonymous{SystemZAsmParser.cpp}::SystemZOperand::addBDRAddrOperands</a>, <a href="/web-llvm/docs/api/classes/anonymous-systemzasmparser-cpp-/systemzoperand/#af776389f8f4e4c37da30a66ff260f9f6">anonymous{SystemZAsmParser.cpp}::SystemZOperand::addBDVAddrOperands</a>, <a href="/web-llvm/docs/api/classes/anonymous-systemzasmparser-cpp-/systemzoperand/#abf2793ad54a2663ea0dedbaaa2b29cd8">anonymous{SystemZAsmParser.cpp}::SystemZOperand::addBDXAddrOperands</a>, <a href="/web-llvm/docs/api/classes/anonymous-armasmparser-cpp-/armoperand/#aecad58f6dbb6b10e480e511a6880d3a8">anonymous{ARMAsmParser.cpp}::ARMOperand::addBitfieldOperands</a>, <a href="/web-llvm/docs/api/classes/anonymous-aarch64asmparser-cpp-/aarch64operand/#aab7d7b59c23bda548073770ccaaa1f54">anonymous{AArch64AsmParser.cpp}::AArch64Operand::addBranchTarget14Operands</a>, <a href="/web-llvm/docs/api/classes/anonymous-aarch64asmparser-cpp-/aarch64operand/#aa1448a1c0dc861047a4abeab5dfa3d57">anonymous{AArch64AsmParser.cpp}::AArch64Operand::addBranchTarget26Operands</a>, <a href="/web-llvm/docs/api/structs/anonymous-ppcasmparser-cpp-/ppcoperand/#ae4e11d80124a79d601e7d34d463ff119">anonymous{PPCAsmParser.cpp}::PPCOperand::addBranchTargetOperands</a>, <a href="/web-llvm/docs/api/structs/anonymous-webassemblyasmparser-cpp-/webassemblyoperand/#a8896b0d3d3c22e3b36197de128dd7fd6">anonymous{WebAssemblyAsmParser.cpp}::WebAssemblyOperand::addBrListOperands</a>, <a href="/web-llvm/docs/api/structs/anonymous-lanaiasmparser-cpp-/lanaioperand/#a6242a454fd07471f8abb0de8c96948d1">anonymous{LanaiAsmParser.cpp}::LanaiOperand::addBrTargetOperands</a>, <a href="/web-llvm/docs/api/classes/anonymous-aarch64asmparser-cpp-/aarch64operand/#a8745b3f6e84510f5123c608560d067c3">anonymous{AArch64AsmParser.cpp}::AArch64Operand::addBTIHintOperands</a>, <a href="/web-llvm/docs/api/files/lib/lib/codegen/liveregunits-cpp/#a09c3edd4c226f6af4965320fa45f574d">addCalleeSavedRegs</a>, <a href="/web-llvm/docs/api/structs/anonymous-lanaiasmparser-cpp-/lanaioperand/#a2d1c4938e33ca93febed1f664840cbe0">anonymous{LanaiAsmParser.cpp}::LanaiOperand::addCallTargetOperands</a>, <a href="/web-llvm/docs/api/classes/anonymous-sparcasmparser-cpp-/sparcoperand/#a9075c3f4cc269a603e8f3f1d88ea2fb4">anonymous{SparcAsmParser.cpp}::SparcOperand::addCallTargetOperands</a>, <a href="/web-llvm/docs/api/structs/anonymous-webassemblyasmparser-cpp-/webassemblyoperand/#a20abe1ede172e9ba62511e7892a43051">anonymous{WebAssemblyAsmParser.cpp}::WebAssemblyOperand::addCatchListOperands</a>, <a href="/web-llvm/docs/api/classes/anonymous-veasmparser-cpp-/veoperand/#aecf9ef1555e75bad67a11aabe6d914c5">anonymous{VEAsmParser.cpp}::VEOperand::addCCOpOperands</a>, <a href="/web-llvm/docs/api/classes/anonymous-armasmparser-cpp-/armoperand/#aa03e2c6253e6c5b0f0b7b6013e18407f">anonymous{ARMAsmParser.cpp}::ARMOperand::addCCOutOperands</a>, <a href="/web-llvm/docs/api/classes/anonymous-mipsasmparser-cpp-/mipsoperand/#a9e8be9fe66ed8d207fc58839c24ce8ae">anonymous{MipsAsmParser.cpp}::MipsOperand::addCCRAsmRegOperands</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/arm/armisellowering-cpp/#a6a0699db88ea20879fd3e9c07cd36b0d">AddCombineBUILD_VECTORToVPADDL</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/arm/armisellowering-cpp/#a37754d31c33565bdfd4903ab5e905a6a">AddCombineToVPADD</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/arm/armisellowering-cpp/#a5e2ad1fd4e6db82aeeb143564ecca7fd">AddCombineVUZPToVPADDL</a>, <a href="/web-llvm/docs/api/classes/anonymous-aarch64asmparser-cpp-/aarch64operand/#acd4ed46a8bba14b6e611e0e34a5e02cc">anonymous{AArch64AsmParser.cpp}::AArch64Operand::addComplexRotationEvenOperands</a>, <a href="/web-llvm/docs/api/classes/anonymous-armasmparser-cpp-/armoperand/#afd957e14a6704fe97baef0356550ee54">anonymous{ARMAsmParser.cpp}::ARMOperand::addComplexRotationEvenOperands</a>, <a href="/web-llvm/docs/api/classes/anonymous-aarch64asmparser-cpp-/aarch64operand/#a0e16e22e5918c7110f0f7658b61f53e8">anonymous{AArch64AsmParser.cpp}::AArch64Operand::addComplexRotationOddOperands</a>, <a href="/web-llvm/docs/api/classes/anonymous-armasmparser-cpp-/armoperand/#a14c8b64e8fda48fef5220dfb9018fc08">anonymous{ARMAsmParser.cpp}::ARMOperand::addComplexRotationOddOperands</a>, <a href="/web-llvm/docs/api/classes/anonymous-aarch64asmparser-cpp-/aarch64operand/#a5120ff8db5e8098a3f9551e139d8aeaf">anonymous{AArch64AsmParser.cpp}::AArch64Operand::addCondCodeOperands</a>, <a href="/web-llvm/docs/api/classes/anonymous-armasmparser-cpp-/armoperand/#a03e3b195e9ccc3d8c840e87f0cba6dbc">anonymous{ARMAsmParser.cpp}::ARMOperand::addCondCodeOperands</a>, <a href="/web-llvm/docs/api/structs/anonymous-lanaiasmparser-cpp-/lanaioperand/#abeba174de27ec49a4b93d205a6cec2f2">anonymous{LanaiAsmParser.cpp}::LanaiOperand::addCondCodeOperands</a>, <a href="/web-llvm/docs/api/classes/anonymous-mipsasmparser-cpp-/mipsoperand/#ac6fc6636f3e516e99df40178e7e06215">anonymous{MipsAsmParser.cpp}::MipsOperand::addConstantSImmOperands</a>, <a href="/web-llvm/docs/api/classes/anonymous-mipsasmparser-cpp-/mipsoperand/#a7df0924976dc5e03315428d6d30ace75">anonymous{MipsAsmParser.cpp}::MipsOperand::addConstantUImmOperands</a>, <a href="/web-llvm/docs/api/classes/anonymous-armasmparser-cpp-/armoperand/#a11f0f3e61fbf198f6b64b6863b7dfffb">anonymous{ARMAsmParser.cpp}::ARMOperand::addConstPoolAsmImmOperands</a>, <a href="/web-llvm/docs/api/structs/anonymous-cskyasmparser-cpp-/cskyoperand/#a4945c8a4072ad73e71889ff2d278625a">anonymous{CSKYAsmParser.cpp}::CSKYOperand::addConstpoolOperands</a>, <a href="/web-llvm/docs/api/classes/anonymous-mipsasmparser-cpp-/mipsoperand/#a5a5052251d14c5c2dcaba9c28c37da47">anonymous{MipsAsmParser.cpp}::MipsOperand::addCOP0AsmRegOperands</a>, <a href="/web-llvm/docs/api/classes/anonymous-mipsasmparser-cpp-/mipsoperand/#af5da2d886c9733e83e02b50abeecc30e">anonymous{MipsAsmParser.cpp}::MipsOperand::addCOP2AsmRegOperands</a>, <a href="/web-llvm/docs/api/classes/anonymous-mipsasmparser-cpp-/mipsoperand/#a8d0cb9abd93678d9c6bc6a3a25eec412">anonymous{MipsAsmParser.cpp}::MipsOperand::addCOP3AsmRegOperands</a>, <a href="/web-llvm/docs/api/classes/anonymous-armasmparser-cpp-/armoperand/#a768efe40ca84546861891d6c31a1fb0b">anonymous{ARMAsmParser.cpp}::ARMOperand::addCoprocNumOperands</a>, <a href="/web-llvm/docs/api/classes/anonymous-armasmparser-cpp-/armoperand/#a10de3d0676a377654d69cb821f9d9d34">anonymous{ARMAsmParser.cpp}::ARMOperand::addCoprocOptionOperands</a>, <a href="/web-llvm/docs/api/classes/anonymous-armasmparser-cpp-/armoperand/#ad4ba28c8a06374cb1fe25facd4d8081b">anonymous{ARMAsmParser.cpp}::ARMOperand::addCoprocRegOperands</a>, <a href="/web-llvm/docs/api/structs/anonymous-ppcasmparser-cpp-/ppcoperand/#a5416ccbb01a0d1a87c306aa8f9229cc7">anonymous{PPCAsmParser.cpp}::PPCOperand::addCRBitMaskOperands</a>, <a href="/web-llvm/docs/api/structs/anonymous-riscvasmparser-cpp-/riscvoperand/#afd5cd5faa882cb075d2cd166a3cd3222">anonymous{RISCVAsmParser.cpp}::RISCVOperand::addCSRSystemRegisterOperands</a>, <a href="/web-llvm/docs/api/classes/anonymous-armasmparser-cpp-/armoperand/#ad6429ae0b96fbe89735f32009cc117e3">anonymous{ARMAsmParser.cpp}::ARMOperand::addDPRRegListOperands</a>, <a href="/web-llvm/docs/api/structs/llvm/x86operand/#aa957005d508608716aace06b32aedff5">llvm::X86Operand::addDstIdxOperands</a>, <a href="/web-llvm/docs/api/classes/anonymous-armasmparser-cpp-/armoperand/#ab544838a0a94ec236eef9b5ddfef1331">anonymous{ARMAsmParser.cpp}::ARMOperand::addDupAlignedMemory16Operands</a>, <a href="/web-llvm/docs/api/classes/anonymous-armasmparser-cpp-/armoperand/#ae470cd25c3073ee69eaf8f6b2796fcc3">anonymous{ARMAsmParser.cpp}::ARMOperand::addDupAlignedMemory32Operands</a>, <a href="/web-llvm/docs/api/classes/anonymous-armasmparser-cpp-/armoperand/#a833852ac5b010f3e43c6d03e8827bfa0">anonymous{ARMAsmParser.cpp}::ARMOperand::addDupAlignedMemory64Operands</a>, <a href="/web-llvm/docs/api/classes/anonymous-armasmparser-cpp-/armoperand/#aaafd5cf3c2c665491132fefbb8a35deb">anonymous{ARMAsmParser.cpp}::ARMOperand::addDupAlignedMemory64or128Operands</a>, <a href="/web-llvm/docs/api/classes/anonymous-armasmparser-cpp-/armoperand/#a05a3259dccee044fdadc9d5765ceb9cd">anonymous{ARMAsmParser.cpp}::ARMOperand::addDupAlignedMemoryNoneOperands</a>, <a href="/web-llvm/docs/api/files/lib/lib/analysis/lazycallgraph-cpp/#aec802e48dd5ef69029e285eddfc4158d">addEdge</a>, <a href="/web-llvm/docs/api/classes/llvm/itaniummanglingcanonicalizer/#ad45212f80f0a702ccdf863f2b03227b9">llvm::ItaniumManglingCanonicalizer::addEquivalence</a>, <a href="/web-llvm/docs/api/classes/anonymous-aarch64asmparser-cpp-/aarch64operand/#a9644f19a682324b158710b3222d190eb">anonymous{AArch64AsmParser.cpp}::AArch64Operand::addExactFPImmOperands</a>, <a href="/web-llvm/docs/api/classes/anonymous-aarch64asmparser-cpp-/aarch64operand/#a12ebb7021420c49a1338058e4db7f435">anonymous{AArch64AsmParser.cpp}::AArch64Operand::addExtend64Operands</a>, <a href="/web-llvm/docs/api/classes/anonymous-aarch64asmparser-cpp-/aarch64operand/#a8a2b0c34d3cfaf2fa1561bfaf6182700">anonymous{AArch64AsmParser.cpp}::AArch64Operand::addExtendOperands</a>, <a href="/web-llvm/docs/api/classes/anonymous-armasmparser-cpp-/armoperand/#a4b1be0b8c60dcebb134703a9676484e8">anonymous{ARMAsmParser.cpp}::ARMOperand::addFBits16Operands</a>, <a href="/web-llvm/docs/api/classes/anonymous-armasmparser-cpp-/armoperand/#a2c571f76a5913408475fa986a60ed6f1">anonymous{ARMAsmParser.cpp}::ARMOperand::addFBits32Operands</a>, <a href="/web-llvm/docs/api/classes/anonymous-mipsasmparser-cpp-/mipsoperand/#a0ef7cd5c70764da83c69359a22b1d8fc">anonymous{MipsAsmParser.cpp}::MipsOperand::addFCCAsmRegOperands</a>, <a href="/web-llvm/docs/api/structs/anonymous-riscvasmparser-cpp-/riscvoperand/#aaab805d2778c683124cc4241c4ae522e">anonymous{RISCVAsmParser.cpp}::RISCVOperand::addFenceArgOperands</a>, <a href="/web-llvm/docs/api/classes/anonymous-mipsasmparser-cpp-/mipsoperand/#a19837d0a63e7e5a0688d838fc824c16e">anonymous{MipsAsmParser.cpp}::MipsOperand::addFGR32AsmRegOperands</a>, <a href="/web-llvm/docs/api/classes/anonymous-mipsasmparser-cpp-/mipsoperand/#a45e61c46f7d86680d3816b090113bc7c">anonymous{MipsAsmParser.cpp}::MipsOperand::addFGR64AsmRegOperands</a>, <a href="/web-llvm/docs/api/classes/anonymous-armasmparser-cpp-/armoperand/#aa2eac2546f1093e8938ee0ae4d5562fd">anonymous{ARMAsmParser.cpp}::ARMOperand::addFPDRegListWithVPROperands</a>, <a href="/web-llvm/docs/api/structs/anonymous-webassemblyasmparser-cpp-/webassemblyoperand/#a897c9e930c31d4b65408c09c73d6a417">anonymous{WebAssemblyAsmParser.cpp}::WebAssemblyOperand::addFPImmf32Operands</a>, <a href="/web-llvm/docs/api/structs/anonymous-webassemblyasmparser-cpp-/webassemblyoperand/#a3bcb95d1f0d9f65bf8d7fb3e60601c57">anonymous{WebAssemblyAsmParser.cpp}::WebAssemblyOperand::addFPImmf64Operands</a>, <a href="/web-llvm/docs/api/classes/anonymous-aarch64asmparser-cpp-/aarch64operand/#aadc0596f177340a6d088aa4b9084263d">anonymous{AArch64AsmParser.cpp}::AArch64Operand::addFPImmOperands</a>, <a href="/web-llvm/docs/api/classes/anonymous-armasmparser-cpp-/armoperand/#abe2cc7744f5671009687f38923ffd49b">anonymous{ARMAsmParser.cpp}::ARMOperand::addFPImmOperands</a>, <a href="/web-llvm/docs/api/structs/anonymous-riscvasmparser-cpp-/riscvoperand/#a72b37da283ebf9ecc9ef3b8468b9569d">anonymous{RISCVAsmParser.cpp}::RISCVOperand::addFPImmOperands</a>, <a href="/web-llvm/docs/api/classes/anonymous-aarch64asmparser-cpp-/aarch64operand/#a693bc5d80a94144221ae8311989c4652">anonymous{AArch64AsmParser.cpp}::AArch64Operand::addFPRasZPRRegOperands</a>, <a href="/web-llvm/docs/api/classes/anonymous-armasmparser-cpp-/armoperand/#aaada46a5fed912a2fe0d8cce83b200e5">anonymous{ARMAsmParser.cpp}::ARMOperand::addFPSRegListWithVPROperands</a>, <a href="/web-llvm/docs/api/structs/anonymous-riscvasmparser-cpp-/riscvoperand/#a852817cd2a9f95112d0f01374ddc156f">anonymous{RISCVAsmParser.cpp}::RISCVOperand::addFRMArgOperands</a>, <a href="/web-llvm/docs/api/files/lib/lib/codegen/lib/codegen/selectiondag/scheduledagsdnodes-cpp/#a35a2c1218102d97a3eae54fac5386699">AddGlue</a>, <a href="/web-llvm/docs/api/classes/anonymous-aarch64asmparser-cpp-/aarch64operand/#ac4f56500894c6c3ca92c54b569cc42a7">anonymous{AArch64AsmParser.cpp}::AArch64Operand::addGPR32as64Operands</a>, <a href="/web-llvm/docs/api/classes/anonymous-mipsasmparser-cpp-/mipsoperand/#abd3fc4a45ddc96177fb36555202c66ae">anonymous{MipsAsmParser.cpp}::MipsOperand::addGPR32AsmRegOperands</a>, <a href="/web-llvm/docs/api/classes/anonymous-mipsasmparser-cpp-/mipsoperand/#a816b9264393cb64140de265f504fce83">anonymous{MipsAsmParser.cpp}::MipsOperand::addGPR32NonZeroAsmRegOperands</a>, <a href="/web-llvm/docs/api/classes/anonymous-mipsasmparser-cpp-/mipsoperand/#a83d460a6677f2f149ca35ea1a921a180">anonymous{MipsAsmParser.cpp}::MipsOperand::addGPR32ZeroAsmRegOperands</a>, <a href="/web-llvm/docs/api/classes/anonymous-aarch64asmparser-cpp-/aarch64operand/#ac45d96b1d1611280239c5f5ec90e1d22">anonymous{AArch64AsmParser.cpp}::AArch64Operand::addGPR64as32Operands</a>, <a href="/web-llvm/docs/api/classes/anonymous-mipsasmparser-cpp-/mipsoperand/#a51bf0a531510cc8e16e3226e82f10bcf">anonymous{MipsAsmParser.cpp}::MipsOperand::addGPR64AsmRegOperands</a>, <a href="/web-llvm/docs/api/classes/anonymous-mipsasmparser-cpp-/mipsoperand/#a3527031d5d4e3cb6824564e3a2ac1e76">anonymous{MipsAsmParser.cpp}::MipsOperand::addGPRMM16AsmRegMovePOperands</a>, <a href="/web-llvm/docs/api/classes/anonymous-mipsasmparser-cpp-/mipsoperand/#ae58ddc1271c5f3654e0ea31436ff5e0b">anonymous{MipsAsmParser.cpp}::MipsOperand::addGPRMM16AsmRegMovePPairFirstOperands</a>, <a href="/web-llvm/docs/api/classes/anonymous-mipsasmparser-cpp-/mipsoperand/#ab2c6ec24d31e5181054f9f6d9469ae79">anonymous{MipsAsmParser.cpp}::MipsOperand::addGPRMM16AsmRegMovePPairSecondOperands</a>, <a href="/web-llvm/docs/api/classes/anonymous-mipsasmparser-cpp-/mipsoperand/#aa46096946509f9d61cc4753c3ce9a69a">anonymous{MipsAsmParser.cpp}::MipsOperand::addGPRMM16AsmRegOperands</a>, <a href="/web-llvm/docs/api/classes/anonymous-mipsasmparser-cpp-/mipsoperand/#a3a16376a94d441185b8a8b41c7174b79">anonymous{MipsAsmParser.cpp}::MipsOperand::addGPRMM16AsmRegZeroOperands</a>, <a href="/web-llvm/docs/api/structs/llvm/x86operand/#a25127edbfd500680786a7964074d8629">llvm::X86Operand::addGR16orGR32orGR64Operands</a>, <a href="/web-llvm/docs/api/structs/llvm/x86operand/#a86467b8eb24fee4d7a713a537685d783">llvm::X86Operand::addGR32orGR64Operands</a>, <a href="/web-llvm/docs/api/classes/anonymous-mipsasmparser-cpp-/mipsoperand/#a1a0c253d3acd5440394239432c9fd5a1">anonymous{MipsAsmParser.cpp}::MipsOperand::addHI32DSPAsmRegOperands</a>, <a href="/web-llvm/docs/api/structs/anonymous-lanaiasmparser-cpp-/lanaioperand/#a1d7b8b2f33404bae5609243536427d9b">anonymous{LanaiAsmParser.cpp}::LanaiOperand::addHiImm16AndOperands</a>, <a href="/web-llvm/docs/api/structs/anonymous-lanaiasmparser-cpp-/lanaioperand/#a1df049e5840d649a327cba55d9ad3f8d">anonymous{LanaiAsmParser.cpp}::LanaiOperand::addHiImm16Operands</a>, <a href="/web-llvm/docs/api/classes/anonymous-mipsasmparser-cpp-/mipsoperand/#a221fdbf10781b3153f4dbc016a6bb059">anonymous{MipsAsmParser.cpp}::MipsOperand::addHWRegsAsmRegOperands</a>, <a href="/web-llvm/docs/api/classes/anonymous-armasmparser-cpp-/armoperand/#aa32c68b18eb08b2d2ccd98d101c9b46f">anonymous{ARMAsmParser.cpp}::ARMOperand::addImm0_1020s4Operands</a>, <a href="/web-llvm/docs/api/classes/anonymous-armasmparser-cpp-/armoperand/#a9a414428a9327e625a2299744ff564fe">anonymous{ARMAsmParser.cpp}::ARMOperand::addImm0_4095NegOperands</a>, <a href="/web-llvm/docs/api/classes/anonymous-armasmparser-cpp-/armoperand/#ab4026544d255ebabc8012238640dab5e">anonymous{ARMAsmParser.cpp}::ARMOperand::addImm0_508s4NegOperands</a>, <a href="/web-llvm/docs/api/classes/anonymous-armasmparser-cpp-/armoperand/#adfd7a84e908bb0a8dfca3ea459d652db">anonymous{ARMAsmParser.cpp}::ARMOperand::addImm0_508s4Operands</a>, <a href="/web-llvm/docs/api/structs/anonymous-lanaiasmparser-cpp-/lanaioperand/#ab82890c84cee6bcbdb0175c3d99032dd">anonymous{LanaiAsmParser.cpp}::LanaiOperand::addImm10Operands</a>, <a href="/web-llvm/docs/api/classes/anonymous-armasmparser-cpp-/armoperand/#aa7de9805408dca5ee30579319047181b">anonymous{ARMAsmParser.cpp}::ARMOperand::addImm1_16Operands</a>, <a href="/web-llvm/docs/api/classes/anonymous-armasmparser-cpp-/armoperand/#ac442880c4ca40e62e9f8398797ca5ec3">anonymous{ARMAsmParser.cpp}::ARMOperand::addImm1_32Operands</a>, <a href="/web-llvm/docs/api/classes/anonymous-armasmparser-cpp-/armoperand/#a361541dc318a3d464e368db2a352e56b">anonymous{ARMAsmParser.cpp}::ARMOperand::addImm7Operands</a>, <a href="/web-llvm/docs/api/classes/anonymous-armasmparser-cpp-/armoperand/#acdafd01d7875d4bf736bae1cc72a36fc">anonymous{ARMAsmParser.cpp}::ARMOperand::addImm7s4Operands</a>, <a href="/web-llvm/docs/api/classes/anonymous-armasmparser-cpp-/armoperand/#af91b5c447e1b5d8cb35d0000b4f48052">anonymous{ARMAsmParser.cpp}::ARMOperand::addImm7Shift0Operands</a>, <a href="/web-llvm/docs/api/classes/anonymous-armasmparser-cpp-/armoperand/#afd8f1642115c7fc6d487ffce63218a32">anonymous{ARMAsmParser.cpp}::ARMOperand::addImm7Shift1Operands</a>, <a href="/web-llvm/docs/api/classes/anonymous-armasmparser-cpp-/armoperand/#a81d4ac723e053777bb1b1796dc982098">anonymous{ARMAsmParser.cpp}::ARMOperand::addImm7Shift2Operands</a>, <a href="/web-llvm/docs/api/classes/anonymous-armasmparser-cpp-/armoperand/#a78914a4833ee6ecedeace11e730b5cd2">anonymous{ARMAsmParser.cpp}::ARMOperand::addImm8s4Operands</a>, <a href="/web-llvm/docs/api/classes/anonymous-avrasmparser-cpp-/avroperand/#aeb9cfed53c597477080d2f8d03cb4442">anonymous{AVRAsmParser.cpp}::AVROperand::addImmCom8Operands</a>, <a href="/web-llvm/docs/api/classes/anonymous-aarch64asmparser-cpp-/aarch64operand/#ab1e3f86f5e35a49ad9969616da8ee130">anonymous{AArch64AsmParser.cpp}::AArch64Operand::addImmNegWithOptionalShiftOperands</a>, <a href="/web-llvm/docs/api/classes/anonymous-aarch64asmparser-cpp-/aarch64operand/#af1209139ff48f61a284639b683997350">anonymous{AArch64AsmParser.cpp}::AArch64Operand::addImmOperands</a>, <a href="/web-llvm/docs/api/classes/anonymous-amdgpuasmparser-cpp-/amdgpuoperand/#aecc4bcb6c40064c4c0544f55facbb18a">anonymous{AMDGPUAsmParser.cpp}::AMDGPUOperand::addImmOperands</a>, <a href="/web-llvm/docs/api/classes/anonymous-armasmparser-cpp-/armoperand/#a402de26349e2f5a3ba022f4d6ae81378">anonymous{ARMAsmParser.cpp}::ARMOperand::addImmOperands</a>, <a href="/web-llvm/docs/api/classes/anonymous-avrasmparser-cpp-/avroperand/#a2e02da9d958ddc016197f203883a81e6">anonymous{AVRAsmParser.cpp}::AVROperand::addImmOperands</a>, <a href="/web-llvm/docs/api/structs/anonymous-bpfasmparser-cpp-/bpfoperand/#a06b01c100359674e93ee5ba45aacd0bc">anonymous{BPFAsmParser.cpp}::BPFOperand::addImmOperands</a>, <a href="/web-llvm/docs/api/structs/anonymous-cskyasmparser-cpp-/cskyoperand/#ae5ea637c5c5977fe147cf7a93f076879">anonymous{CSKYAsmParser.cpp}::CSKYOperand::addImmOperands</a>, <a href="/web-llvm/docs/api/structs/anonymous-hexagonasmparser-cpp-/hexagonoperand/#a12db185eb8785ef79c995954f5a15bf3">anonymous{HexagonAsmParser.cpp}::HexagonOperand::addImmOperands</a>, <a href="/web-llvm/docs/api/structs/anonymous-lanaiasmparser-cpp-/lanaioperand/#a21a556559c7e8454cf761a7c221be5f9">anonymous{LanaiAsmParser.cpp}::LanaiOperand::addImmOperands</a>, <a href="/web-llvm/docs/api/classes/anonymous-loongarchasmparser-cpp-/loongarchoperand/#a70a680203d02fe1028bb553895c4c017">anonymous{LoongArchAsmParser.cpp}::LoongArchOperand::addImmOperands</a>, <a href="/web-llvm/docs/api/classes/anonymous-m68kasmparser-cpp-/m68koperand/#a3467f0da9b2fdeb58a8078f5fb66e1c9">anonymous{M68kAsmParser.cpp}::M68kOperand::addImmOperands</a>, <a href="/web-llvm/docs/api/classes/anonymous-mipsasmparser-cpp-/mipsoperand/#aeb8d6ca03d166a0c534c48009f76e8a4">anonymous{MipsAsmParser.cpp}::MipsOperand::addImmOperands</a>, <a href="/web-llvm/docs/api/classes/anonymous-msp430asmparser-cpp-/msp430operand/#ad795b1ef17d0c2d436c386a9190c3710">anonymous{MSP430AsmParser.cpp}::MSP430Operand::addImmOperands</a>, <a href="/web-llvm/docs/api/structs/anonymous-ppcasmparser-cpp-/ppcoperand/#a713d7daafa349daa3ed89e1cf32844ba">anonymous{PPCAsmParser.cpp}::PPCOperand::addImmOperands</a>, <a href="/web-llvm/docs/api/structs/anonymous-riscvasmparser-cpp-/riscvoperand/#a433c5deedfe24ee94256da5a3021aa19">anonymous{RISCVAsmParser.cpp}::RISCVOperand::addImmOperands</a>, <a href="/web-llvm/docs/api/classes/anonymous-sparcasmparser-cpp-/sparcoperand/#affe77fc6db805412cce31d273aade153">anonymous{SparcAsmParser.cpp}::SparcOperand::addImmOperands</a>, <a href="/web-llvm/docs/api/classes/anonymous-systemzasmparser-cpp-/systemzoperand/#ad4b72b68c6fc2ddcfa070f61861e620d">anonymous{SystemZAsmParser.cpp}::SystemZOperand::addImmOperands</a>, <a href="/web-llvm/docs/api/classes/anonymous-veasmparser-cpp-/veoperand/#a89672826935dbe6bfcdf5e7fee75c7fb">anonymous{VEAsmParser.cpp}::VEOperand::addImmOperands</a>, <a href="/web-llvm/docs/api/structs/anonymous-webassemblyasmparser-cpp-/webassemblyoperand/#a1843f39a0d50d963f92c5f1fe30b633e">anonymous{WebAssemblyAsmParser.cpp}::WebAssemblyOperand::addImmOperands</a>, <a href="/web-llvm/docs/api/structs/llvm/x86operand/#a41c70f2eca46ec1276f2519a99ffae11">llvm::X86Operand::addImmOperands</a>, <a href="/web-llvm/docs/api/structs/xtensaoperand/#a394e7743dd2809662732f2a1e3ef6fa3">XtensaOperand::addImmOperands</a>, <a href="/web-llvm/docs/api/classes/anonymous-aarch64asmparser-cpp-/aarch64operand/#ad09ecb52e79c8bef77dea3fa313c9a31">anonymous{AArch64AsmParser.cpp}::AArch64Operand::addImmScaledOperands</a>, <a href="/web-llvm/docs/api/classes/anonymous-aarch64asmparser-cpp-/aarch64operand/#a3dfb11dc7e2fe62f40ada900f6e9e176">anonymous{AArch64AsmParser.cpp}::AArch64Operand::addImmScaledRangeOperands</a>, <a href="/web-llvm/docs/api/structs/anonymous-lanaiasmparser-cpp-/lanaioperand/#a2a6d4d0389eb037b2ca67206191384ee">anonymous{LanaiAsmParser.cpp}::LanaiOperand::addImmShiftOperands</a>, <a href="/web-llvm/docs/api/classes/anonymous-armasmparser-cpp-/armoperand/#a94e86034d35c6b76f9910bf56f7b793f">anonymous{ARMAsmParser.cpp}::ARMOperand::addImmThumbSROperands</a>, <a href="/web-llvm/docs/api/classes/anonymous-systemzasmparser-cpp-/systemzoperand/#a3c05e49d03c9042135ec827804a0a9e4">anonymous{SystemZAsmParser.cpp}::SystemZOperand::addImmTLSOperands</a>, <a href="/web-llvm/docs/api/classes/anonymous-aarch64asmparser-cpp-/aarch64operand/#ab6d217a1a1a9c4c03289d555a4404aed">anonymous{AArch64AsmParser.cpp}::AArch64Operand::addImmWithOptionalShiftOperands</a>, <a href="/web-llvm/docs/api/classes/anonymous-armasmparser-cpp-/armoperand/#aa1e630839626b7ae31f6abc1d87209e9">anonymous{ARMAsmParser.cpp}::ARMOperand::addInstSyncBarrierOptOperands</a>, <a href="/web-llvm/docs/api/classes/anonymous-armasmparser-cpp-/armoperand/#ad43d0a6a64bad5f305bb9ad845bd2096">anonymous{ARMAsmParser.cpp}::ARMOperand::addITCondCodeInvOperands</a>, <a href="/web-llvm/docs/api/classes/anonymous-armasmparser-cpp-/armoperand/#ac5e2c8aff96996ab20507dab30f9299b">anonymous{ARMAsmParser.cpp}::ARMOperand::addITCondCodeOperands</a>, <a href="/web-llvm/docs/api/classes/anonymous-armasmparser-cpp-/armoperand/#a9680608c6a2d4bde00a5b8b5ebb92bfe">anonymous{ARMAsmParser.cpp}::ARMOperand::addITMaskOperands</a>, <a href="/web-llvm/docs/api/classes/llvm/liveintervals/#a6e3886e9084257e74b5db4a8951d36e0">llvm::LiveIntervals::addKillFlags</a>, <a href="/web-llvm/docs/api/classes/llvm/gcovblock/#a0bc80e6944ef8d4caf1f83ea3b933e36">llvm::GCOVBlock::addLine</a>, <a href="/web-llvm/docs/api/classes/anonymous-mipsasmparser-cpp-/mipsoperand/#a5d3694893cd2e7880c2b77c3230c2865">anonymous{MipsAsmParser.cpp}::MipsOperand::addLO32DSPAsmRegOperands</a>, <a href="/web-llvm/docs/api/classes/anonymous-aarch64asmparser-cpp-/aarch64operand/#a9056346261cb779a567f627676c37068">anonymous{AArch64AsmParser.cpp}::AArch64Operand::addLogicalImmNotOperands</a>, <a href="/web-llvm/docs/api/classes/anonymous-aarch64asmparser-cpp-/aarch64operand/#ae997d5e3fd8015241b318c4b0da0c194">anonymous{AArch64AsmParser.cpp}::AArch64Operand::addLogicalImmOperands</a>, <a href="/web-llvm/docs/api/structs/anonymous-lanaiasmparser-cpp-/lanaioperand/#a9773bf588f5b30ff88274f1ee52e9c9b">anonymous{LanaiAsmParser.cpp}::LanaiOperand::addLoImm16AndOperands</a>, <a href="/web-llvm/docs/api/structs/anonymous-lanaiasmparser-cpp-/lanaioperand/#a0e06c5e6471e93005516ed8a140c72cb">anonymous{LanaiAsmParser.cpp}::LanaiOperand::addLoImm16Operands</a>, <a href="/web-llvm/docs/api/structs/anonymous-lanaiasmparser-cpp-/lanaioperand/#a5b3ab698b20fe1832388bb62f71c213e">anonymous{LanaiAsmParser.cpp}::LanaiOperand::addLoImm21Operands</a>, <a href="/web-llvm/docs/api/classes/anonymous-aarch64asmparser-cpp-/aarch64operand/#aa032e057f6912df64dddaffa3eaadf91">anonymous{AArch64AsmParser.cpp}::AArch64Operand::addLSLImm3ShifterOperands</a>, <a href="/web-llvm/docs/api/classes/anonymous-systemzasmparser-cpp-/systemzoperand/#a5adb948f0e1acffb765fb3d36b58635f">anonymous{SystemZAsmParser.cpp}::SystemZOperand::addLXAAddrOperands</a>, <a href="/web-llvm/docs/api/classes/llvm/dwarfexpression/#a8337bafd341ca7fa36509bf0ad142c57">llvm::DwarfExpression::addMachineRegExpression</a>, <a href="/web-llvm/docs/api/structs/llvm/x86operand/#a1411797182fa22f898f4baf0e3eb7298">llvm::X86Operand::addMaskPairOperands</a>, <a href="/web-llvm/docs/api/classes/anonymous-aarch64asmparser-cpp-/aarch64operand/#a52a9b33a2e0d8bab36c2c5cb7b36d610">anonymous{AArch64AsmParser.cpp}::AArch64Operand::addMatrixOperands</a>, <a href="/web-llvm/docs/api/classes/anonymous-aarch64asmparser-cpp-/aarch64operand/#a705e1e39d5002641f1a1a2730612b728">anonymous{AArch64AsmParser.cpp}::AArch64Operand::addMatrixTileListOperands</a>, <a href="/web-llvm/docs/api/classes/anonymous-armasmparser-cpp-/armoperand/#ab997fbc3057584e8c726b4d11c18746d">anonymous{ARMAsmParser.cpp}::ARMOperand::addMemBarrierOptOperands</a>, <a href="/web-llvm/docs/api/classes/anonymous-sparcasmparser-cpp-/sparcoperand/#ab77fda774011c250780f64adee95e3da">anonymous{SparcAsmParser.cpp}::SparcOperand::addMembarTagOperands</a>, <a href="/web-llvm/docs/api/classes/anonymous-aarch64asmparser-cpp-/aarch64operand/#ac9f0eb14b728a80df813a4da2e6ea7a7">anonymous{AArch64AsmParser.cpp}::AArch64Operand::addMemExtend8Operands</a>, <a href="/web-llvm/docs/api/classes/anonymous-aarch64asmparser-cpp-/aarch64operand/#a4c2a8c70306e9fdd7c8450d043f183e2">anonymous{AArch64AsmParser.cpp}::AArch64Operand::addMemExtendOperands</a>, <a href="/web-llvm/docs/api/classes/anonymous-armasmparser-cpp-/armoperand/#abe5b4923e46ab980bfb612b7a54cde90">anonymous{ARMAsmParser.cpp}::ARMOperand::addMemImm0_1020s4OffsetOperands</a>, <a href="/web-llvm/docs/api/classes/anonymous-armasmparser-cpp-/armoperand/#a6dff62db50ccdfe98aff9cb203745a66">anonymous{ARMAsmParser.cpp}::ARMOperand::addMemImm12OffsetOperands</a>, <a href="/web-llvm/docs/api/classes/anonymous-armasmparser-cpp-/armoperand/#a9fb937acd028a5bf796c672a0d6c5f75">anonymous{ARMAsmParser.cpp}::ARMOperand::addMemImm7s4OffsetOperands</a>, <a href="/web-llvm/docs/api/classes/anonymous-armasmparser-cpp-/armoperand/#a4301f3a2bb78f6f20862ba128f6f52f5">anonymous{ARMAsmParser.cpp}::ARMOperand::addMemImm8s4OffsetOperands</a>, <a href="/web-llvm/docs/api/classes/anonymous-armasmparser-cpp-/armoperand/#a80bc470aec6db28b9d04cf11684eb9da">anonymous{ARMAsmParser.cpp}::ARMOperand::addMemImmOffsetOperands</a>, <a href="/web-llvm/docs/api/structs/anonymous-lanaiasmparser-cpp-/lanaioperand/#a1cbefada336978d949d3aa114dbee948">anonymous{LanaiAsmParser.cpp}::LanaiOperand::addMemImmOperands</a>, <a href="/web-llvm/docs/api/classes/anonymous-armasmparser-cpp-/armoperand/#a2f54ecd20a9f31051c94fae0b156b249">anonymous{ARMAsmParser.cpp}::ARMOperand::addMemNoOffsetOperands</a>, <a href="/web-llvm/docs/api/classes/anonymous-armasmparser-cpp-/armoperand/#a1970df12effbecce45e177c7121cea0d">anonymous{ARMAsmParser.cpp}::ARMOperand::addMemNoOffsetT2NoSpOperands</a>, <a href="/web-llvm/docs/api/classes/anonymous-armasmparser-cpp-/armoperand/#a24f1bef4c5ea237c5519ac8ea4b0a69e">anonymous{ARMAsmParser.cpp}::ARMOperand::addMemNoOffsetT2Operands</a>, <a href="/web-llvm/docs/api/classes/anonymous-armasmparser-cpp-/armoperand/#a0f4b00007fc60d4881752835aa78235f">anonymous{ARMAsmParser.cpp}::ARMOperand::addMemNoOffsetTOperands</a>, <a href="/web-llvm/docs/api/structs/llvm/x86operand/#a46908e32f1979cb4f57d7d26df02bbf7">llvm::X86Operand::addMemOffsOperands</a>, <a href="/web-llvm/docs/api/classes/anonymous-mipsasmparser-cpp-/mipsoperand/#aaf1abd090a089523ab1f4fa4158734aa">anonymous{MipsAsmParser.cpp}::MipsOperand::addMemOperands</a>, <a href="/web-llvm/docs/api/classes/anonymous-msp430asmparser-cpp-/msp430operand/#af6f292c019d2b087fc36a88099ea71a4">anonymous{MSP430AsmParser.cpp}::MSP430Operand::addMemOperands</a>, <a href="/web-llvm/docs/api/structs/llvm/x86operand/#aa68185209b553ccd5de6d4cd21aae0b7">llvm::X86Operand::addMemOperands</a>, <a href="/web-llvm/docs/api/classes/anonymous-armasmparser-cpp-/armoperand/#a3e8d637955189e14866f744f29ee8ea5">anonymous{ARMAsmParser.cpp}::ARMOperand::addMemPCRelImm12Operands</a>, <a href="/web-llvm/docs/api/structs/anonymous-lanaiasmparser-cpp-/lanaioperand/#acacea0c596433796a7a9674ef7d6df1c">anonymous{LanaiAsmParser.cpp}::LanaiOperand::addMemRegImmOperands</a>, <a href="/web-llvm/docs/api/classes/anonymous-armasmparser-cpp-/armoperand/#a97437a291cf5a4acb1a9459466af8637">anonymous{ARMAsmParser.cpp}::ARMOperand::addMemRegOffsetOperands</a>, <a href="/web-llvm/docs/api/structs/anonymous-lanaiasmparser-cpp-/lanaioperand/#a3bc907003ab69e65230cb39a00390735">anonymous{LanaiAsmParser.cpp}::LanaiOperand::addMemRegRegOperands</a>, <a href="/web-llvm/docs/api/classes/anonymous-armasmparser-cpp-/armoperand/#ab0e32805a18bd96de1be7ab2112092dd">anonymous{ARMAsmParser.cpp}::ARMOperand::addMemRegRQOffsetOperands</a>, <a href="/web-llvm/docs/api/classes/anonymous-veasmparser-cpp-/veoperand/#ac78a8f54f4da2b028a4c513e9646c92a">anonymous{VEAsmParser.cpp}::VEOperand::addMEMriiOperands</a>, <a href="/web-llvm/docs/api/classes/anonymous-sparcasmparser-cpp-/sparcoperand/#ac20dd2f0350bf18d6fd97ba7ad0a2994">anonymous{SparcAsmParser.cpp}::SparcOperand::addMEMriOperands</a>, <a href="/web-llvm/docs/api/classes/anonymous-veasmparser-cpp-/veoperand/#a4fad1c08c01d149c6d24ae557bcee7d8">anonymous{VEAsmParser.cpp}::VEOperand::addMEMriOperands</a>, <a href="/web-llvm/docs/api/classes/anonymous-avrasmparser-cpp-/avroperand/#adf651d75c9923608fead490becd08b33">anonymous{AVRAsmParser.cpp}::AVROperand::addMemriOperands</a>, <a href="/web-llvm/docs/api/classes/anonymous-veasmparser-cpp-/veoperand/#a6c548174c36ceb90c1f77a6c163e80b1">anonymous{VEAsmParser.cpp}::VEOperand::addMEMrriOperands</a>, <a href="/web-llvm/docs/api/classes/anonymous-sparcasmparser-cpp-/sparcoperand/#aa7bb9d19afdd909845c9e565b833ef93">anonymous{SparcAsmParser.cpp}::SparcOperand::addMEMrrOperands</a>, <a href="/web-llvm/docs/api/structs/anonymous-lanaiasmparser-cpp-/lanaioperand/#adb2d3ecd3f23934a5c6194502f9d758e">anonymous{LanaiAsmParser.cpp}::LanaiOperand::addMemSplsOperands</a>, <a href="/web-llvm/docs/api/classes/anonymous-armasmparser-cpp-/armoperand/#a40b064476649a0a56ce95f93aa65c89b">anonymous{ARMAsmParser.cpp}::ARMOperand::addMemTBBOperands</a>, <a href="/web-llvm/docs/api/classes/anonymous-armasmparser-cpp-/armoperand/#a98d14559bea78406707287429d722ffe">anonymous{ARMAsmParser.cpp}::ARMOperand::addMemTBHOperands</a>, <a href="/web-llvm/docs/api/classes/anonymous-armasmparser-cpp-/armoperand/#a38c9a43be0fe27ac8944c0c8a89bb6b1">anonymous{ARMAsmParser.cpp}::ARMOperand::addMemThumbRIs1Operands</a>, <a href="/web-llvm/docs/api/classes/anonymous-armasmparser-cpp-/armoperand/#ad3b02f1b47b3ba6fd451237a1630aab4">anonymous{ARMAsmParser.cpp}::ARMOperand::addMemThumbRIs2Operands</a>, <a href="/web-llvm/docs/api/classes/anonymous-armasmparser-cpp-/armoperand/#a8e7c2c39ca9a33a289abd869b71142f7">anonymous{ARMAsmParser.cpp}::ARMOperand::addMemThumbRIs4Operands</a>, <a href="/web-llvm/docs/api/classes/anonymous-armasmparser-cpp-/armoperand/#a61729ed00e2b9ac641d162d059f24946">anonymous{ARMAsmParser.cpp}::ARMOperand::addMemThumbRROperands</a>, <a href="/web-llvm/docs/api/classes/anonymous-armasmparser-cpp-/armoperand/#a2b7bc4182080d75de1cb54ed7b5a90f8">anonymous{ARMAsmParser.cpp}::ARMOperand::addMemThumbSPIOperands</a>, <a href="/web-llvm/docs/api/classes/anonymous-armasmparser-cpp-/armoperand/#a9f7334fe4a405366c2e73604c925921f">anonymous{ARMAsmParser.cpp}::ARMOperand::addMemUImm12OffsetOperands</a>, <a href="/web-llvm/docs/api/classes/anonymous-veasmparser-cpp-/veoperand/#a9fd8cdace145c937068216b5623d0e22">anonymous{VEAsmParser.cpp}::VEOperand::addMEMziiOperands</a>, <a href="/web-llvm/docs/api/classes/anonymous-veasmparser-cpp-/veoperand/#aa6fbe9cbd311a2636146bafdc021c76c">anonymous{VEAsmParser.cpp}::VEOperand::addMEMziOperands</a>, <a href="/web-llvm/docs/api/classes/anonymous-veasmparser-cpp-/veoperand/#a72fe72f0ed13e4b97e1285d946efe7ec">anonymous{VEAsmParser.cpp}::VEOperand::addMEMzriOperands</a>, <a href="/web-llvm/docs/api/classes/anonymous-mipsasmparser-cpp-/mipsoperand/#a0d290306e7f76b115cfe75025d92be37">anonymous{MipsAsmParser.cpp}::MipsOperand::addMicroMipsMemOperands</a>, <a href="/web-llvm/docs/api/classes/anonymous-veasmparser-cpp-/veoperand/#a512f8716f6ee88fcef3b08264b744047">anonymous{VEAsmParser.cpp}::VEOperand::addMImmOperands</a>, <a href="/web-llvm/docs/api/classes/anonymous-armasmparser-cpp-/armoperand/#a00f276d60b4213d06f10e1c6965e6982">anonymous{ARMAsmParser.cpp}::ARMOperand::addModImmNegOperands</a>, <a href="/web-llvm/docs/api/classes/anonymous-armasmparser-cpp-/armoperand/#a25c3c5882ff6060ea26a9a2c6c96e4d9">anonymous{ARMAsmParser.cpp}::ARMOperand::addModImmNotOperands</a>, <a href="/web-llvm/docs/api/classes/anonymous-armasmparser-cpp-/armoperand/#a540ca19122e726ab4ca0c7a2f8a38ca8">anonymous{ARMAsmParser.cpp}::ARMOperand::addModImmOperands</a>, <a href="/web-llvm/docs/api/structs/anonymous-irsymtab-cpp-/builder/#a9e5d9d56a410f0bd58fa931731c9e644">anonymous{IRSymtab.cpp}::Builder::addModule</a>, <a href="/web-llvm/docs/api/classes/anonymous-m68kasmparser-cpp-/m68koperand/#a9cd23b62012f429a2e2edb2cb30c21b7">anonymous{M68kAsmParser.cpp}::M68kOperand::addMoveMaskOperands</a>, <a href="/web-llvm/docs/api/classes/anonymous-aarch64asmparser-cpp-/aarch64operand/#a937ca41eef356bc1388ad88f951238b7">anonymous{AArch64AsmParser.cpp}::AArch64Operand::addMOVNMovAliasOperands</a>, <a href="/web-llvm/docs/api/classes/anonymous-aarch64asmparser-cpp-/aarch64operand/#a4e23ebca490a6a436d047976a01e7d2f">anonymous{AArch64AsmParser.cpp}::AArch64Operand::addMOVZMovAliasOperands</a>, <a href="/web-llvm/docs/api/classes/anonymous-aarch64asmparser-cpp-/aarch64operand/#a4beaf9b78d7eb225552cd94b0149b024">anonymous{AArch64AsmParser.cpp}::AArch64Operand::addMRSSystemRegisterOperands</a>, <a href="/web-llvm/docs/api/classes/anonymous-mipsasmparser-cpp-/mipsoperand/#a30e5904a36614ccc09d784c12b981554">anonymous{MipsAsmParser.cpp}::MipsOperand::addMSA128AsmRegOperands</a>, <a href="/web-llvm/docs/api/classes/anonymous-mipsasmparser-cpp-/mipsoperand/#a32627220d84219d7cd27750d9664f16a">anonymous{MipsAsmParser.cpp}::MipsOperand::addMSACtrlAsmRegOperands</a>, <a href="/web-llvm/docs/api/classes/anonymous-armasmparser-cpp-/armoperand/#ad4a17494019897f01769f746ad7293d6">anonymous{ARMAsmParser.cpp}::ARMOperand::addMSRMaskOperands</a>, <a href="/web-llvm/docs/api/classes/anonymous-aarch64asmparser-cpp-/aarch64operand/#a1c8b498e080d62622a43e79e74556aa3">anonymous{AArch64AsmParser.cpp}::AArch64Operand::addMSRSystemRegisterOperands</a>, <a href="/web-llvm/docs/api/classes/anonymous-armasmparser-cpp-/armoperand/#a572dc8085b30704f8e30e28dccf68e42">anonymous{ARMAsmParser.cpp}::ARMOperand::addMVEPairVectorIndexOperands</a>, <a href="/web-llvm/docs/api/classes/anonymous-armasmparser-cpp-/armoperand/#a9cc6b74af0c84b124eb91623d1b97d53">anonymous{ARMAsmParser.cpp}::ARMOperand::addMveSaturateOperands</a>, <a href="/web-llvm/docs/api/classes/anonymous-armasmparser-cpp-/armoperand/#a7673cc7bf77bfe4773e263692b64c792">anonymous{ARMAsmParser.cpp}::ARMOperand::addMVEVecListOperands</a>, <a href="/web-llvm/docs/api/classes/anonymous-armasmparser-cpp-/armoperand/#a661225f249347ef6b1be3ad7751bedbb">anonymous{ARMAsmParser.cpp}::ARMOperand::addMVEVectorIndexOperands</a>, <a href="/web-llvm/docs/api/structs/anonymous-hexagonasmparser-cpp-/hexagonoperand/#a54a174b2f96dce8bd66155bf25d9f3d1">anonymous{HexagonAsmParser.cpp}::HexagonOperand::addn1ConstOperands</a>, <a href="/web-llvm/docs/api/classes/anonymous-armasmparser-cpp-/armoperand/#a8d92ff1355dcb13d00196990471f9139">anonymous{ARMAsmParser.cpp}::ARMOperand::addNEONi16splatNotOperands</a>, <a href="/web-llvm/docs/api/classes/anonymous-armasmparser-cpp-/armoperand/#a0940a9f22c8bd87b7fa0a45e012d0516">anonymous{ARMAsmParser.cpp}::ARMOperand::addNEONi16splatOperands</a>, <a href="/web-llvm/docs/api/classes/anonymous-armasmparser-cpp-/armoperand/#a4262ad98cb319bdaf2b640bdb0fbd6ff">anonymous{ARMAsmParser.cpp}::ARMOperand::addNEONi32splatNotOperands</a>, <a href="/web-llvm/docs/api/classes/anonymous-armasmparser-cpp-/armoperand/#a36daafec1fff81a5867269e34313dc3d">anonymous{ARMAsmParser.cpp}::ARMOperand::addNEONi32splatOperands</a>, <a href="/web-llvm/docs/api/classes/anonymous-armasmparser-cpp-/armoperand/#aad748df99e69a972f2c9e52b8cc39d00">anonymous{ARMAsmParser.cpp}::ARMOperand::addNEONi32vmovNegOperands</a>, <a href="/web-llvm/docs/api/classes/anonymous-armasmparser-cpp-/armoperand/#ac0bf4b69732f350137e1d6ae29cb5c92">anonymous{ARMAsmParser.cpp}::ARMOperand::addNEONi32vmovOperands</a>, <a href="/web-llvm/docs/api/classes/anonymous-armasmparser-cpp-/armoperand/#af385793af30b498ff6359717174370f3">anonymous{ARMAsmParser.cpp}::ARMOperand::addNEONi64splatOperands</a>, <a href="/web-llvm/docs/api/classes/anonymous-armasmparser-cpp-/armoperand/#a14b3322ac32c8b0b4eefae2bb49eda10">anonymous{ARMAsmParser.cpp}::ARMOperand::addNEONi8splatOperands</a>, <a href="/web-llvm/docs/api/classes/anonymous-armasmparser-cpp-/armoperand/#aa852cf5dade6f5ee5ca524a799465e1f">anonymous{ARMAsmParser.cpp}::ARMOperand::addNEONinvi8ReplicateOperands</a>, <a href="/web-llvm/docs/api/classes/anonymous-armasmparser-cpp-/armoperand/#accc1e804755bf43243950da346e4f635">anonymous{ARMAsmParser.cpp}::ARMOperand::addNEONvmovi16ReplicateOperands</a>, <a href="/web-llvm/docs/api/classes/anonymous-armasmparser-cpp-/armoperand/#ae9be674e0179e785d1e553d87229da10">anonymous{ARMAsmParser.cpp}::ARMOperand::addNEONvmovi32ReplicateOperands</a>, <a href="/web-llvm/docs/api/classes/anonymous-armasmparser-cpp-/armoperand/#ad610b0521f3a7c6abf5a87a9a71558e9">anonymous{ARMAsmParser.cpp}::ARMOperand::addNEONvmovi8ReplicateOperands</a>, <a href="/web-llvm/docs/api/structs/anonymous-materializationutils-cpp-/rematgraph/#a27ed97327f4a82098c5bcce303e704cb">anonymous{MaterializationUtils.cpp}::RematGraph::addNode</a>, <a href="/web-llvm/docs/api/classes/llvm/datadependencegraph/#a4de3ad80573d416c2450ae66a41729d8">llvm::DataDependenceGraph::addNode</a>, <a href="/web-llvm/docs/api/classes/llvm/directedgraph/#aee99ddb71edafb342c13876e76e583b6">llvm::DirectedGraph&lt; DDGNode, DDGEdge &gt;::addNode</a>, <a href="/web-llvm/docs/api/files/lib/lib/codegen/lib/codegen/selectiondag/selectiondag-cpp/#abd574741643b21b2db236255e18656db">AddNodeIDCustom</a>, <a href="/web-llvm/docs/api/files/lib/lib/codegen/lib/codegen/selectiondag/selectiondag-cpp/#a4b96877e65f76d1f6b8adc0d429b4fcc">AddNodeIDNode</a>, <a href="/web-llvm/docs/api/structs/llvm/bfi-detail/irreduciblegraph/#add4c9ca63093a8270248e72b08c5302e">llvm::bfi_detail::IrreducibleGraph::addNodesInLoop</a>, <a href="/web-llvm/docs/api/structs/llvm/ilist-callback-traits-6a00974026f1163ef87516ae73fba13d/#aa3592c6a473996778f4a411d2706292b">llvm::ilist_callback_traits&lt; MachineBasicBlock &gt;::addNodeToList</a>, <a href="/web-llvm/docs/api/structs/llvm/ilist-traits-58bb2936e8a6e4674ffe4f47907d64dc/#aa022f8a30a02c004bf6d39332cf7643d">llvm::ilist_traits&lt; MachineInstr &gt;::addNodeToList</a>, <a href="/web-llvm/docs/api/classes/anonymous-aarch64asmparser-cpp-/aarch64operand/#a94b3cbab03d77b6119bf4ffb8dc5b21d">anonymous{AArch64AsmParser.cpp}::AArch64Operand::addPAuthPCRelLabel16Operands</a>, <a href="/web-llvm/docs/api/classes/anonymous-m68kasmparser-cpp-/m68koperand/#a81edd91f1a089308e078a5c86ca07ae4">anonymous{M68kAsmParser.cpp}::M68kOperand::addPCDOperands</a>, <a href="/web-llvm/docs/api/classes/anonymous-m68kasmparser-cpp-/m68koperand/#afc5faf5d7c3df5946555e8a6b9e76c33">anonymous{M68kAsmParser.cpp}::M68kOperand::addPCIOperands</a>, <a href="/web-llvm/docs/api/classes/anonymous-aarch64asmparser-cpp-/aarch64operand/#a418048be5c0be53d70dec5000e5d4a7b">anonymous{AArch64AsmParser.cpp}::AArch64Operand::addPCRelLabel19Operands</a>, <a href="/web-llvm/docs/api/classes/anonymous-aarch64asmparser-cpp-/aarch64operand/#acbecf14320c5f3c8b0156ccc7a9ee39b">anonymous{AArch64AsmParser.cpp}::AArch64Operand::addPCRelLabel9Operands</a>, <a href="/web-llvm/docs/api/classes/anonymous-aarch64asmparser-cpp-/aarch64operand/#ab862de3d6c862e4a282cd88b928b9de4">anonymous{AArch64AsmParser.cpp}::AArch64Operand::addPHintOperands</a>, <a href="/web-llvm/docs/api/classes/anonymous-armasmparser-cpp-/armoperand/#adfe7013951c0588b8fc9bfe4f635aba5">anonymous{ARMAsmParser.cpp}::ARMOperand::addPKHASRImmOperands</a>, <a href="/web-llvm/docs/api/classes/anonymous-aarch64asmparser-cpp-/aarch64operand/#a6c9931ba36928eed8dcf2595c04ba489">anonymous{AArch64AsmParser.cpp}::AArch64Operand::addPNRasPPRRegOperands</a>, <a href="/web-llvm/docs/api/classes/anonymous-armasmparser-cpp-/armoperand/#afbe110673f6f1952a6e4e072d2cdd8de">anonymous{ARMAsmParser.cpp}::ARMOperand::addPostIdxImm8Operands</a>, <a href="/web-llvm/docs/api/classes/anonymous-armasmparser-cpp-/armoperand/#ad908815e815a5855ae31b84ba9a2720d">anonymous{ARMAsmParser.cpp}::ARMOperand::addPostIdxImm8s4Operands</a>, <a href="/web-llvm/docs/api/classes/anonymous-armasmparser-cpp-/armoperand/#aa7d60fa11f086b1e99ef10ce32ce5159">anonymous{ARMAsmParser.cpp}::ARMOperand::addPostIdxRegOperands</a>, <a href="/web-llvm/docs/api/classes/anonymous-armasmparser-cpp-/armoperand/#ac6ffe44b8dc8406f9792b89635c955b1">anonymous{ARMAsmParser.cpp}::ARMOperand::addPostIdxRegShiftedOperands</a>, <a href="/web-llvm/docs/api/classes/anonymous-armasmparser-cpp-/armoperand/#a874c0f5a1884183760a4e951c10874d4">anonymous{ARMAsmParser.cpp}::ARMOperand::addPowerTwoOperands</a>, <a href="/web-llvm/docs/api/classes/anonymous-aarch64asmparser-cpp-/aarch64operand/#a5f2b9dd674ec50e06b69b98a88e00317">anonymous{AArch64AsmParser.cpp}::AArch64Operand::addPPRorPNRRegOperands</a>, <a href="/web-llvm/docs/api/classes/llvm/sunit/#af92bf49ed4846e026e68c380d74d7b15">llvm::SUnit::addPred</a>, <a href="/web-llvm/docs/api/classes/anonymous-aarch64asmparser-cpp-/aarch64operand/#aba6f3578ca5c81d7b4fdfb0abd1dbfd6">anonymous{AArch64AsmParser.cpp}::AArch64Operand::addPrefetchOperands</a>, <a href="/web-llvm/docs/api/classes/anonymous-sparcasmparser-cpp-/sparcoperand/#ab8bccadeb3e2ad7db97aaef06ad23f70">anonymous{SparcAsmParser.cpp}::SparcOperand::addPrefetchTagOperands</a>, <a href="/web-llvm/docs/api/classes/anonymous-armasmparser-cpp-/armoperand/#a5c9ebbec74b03775cfb34daaac7c2075">anonymous{ARMAsmParser.cpp}::ARMOperand::addProcIFlagsOperands</a>, <a href="/web-llvm/docs/api/classes/anonymous-aarch64asmparser-cpp-/aarch64operand/#abff9fa54c3161ee17b37acc2b5546ea8">anonymous{AArch64AsmParser.cpp}::AArch64Operand::addPSBHintOperands</a>, <a href="/web-llvm/docs/api/structs/llvm/rdf/dataflowgraph/#aff0e0649aacc0cb7884acdb2caf3888c">llvm::rdf::DataFlowGraph::addr</a>, <a href="/web-llvm/docs/api/classes/anonymous-veasmparser-cpp-/veoperand/#ad9f45cd35c477b521daca23573ec3fcd">anonymous{VEAsmParser.cpp}::VEOperand::addRDOpOperands</a>, <a href="/web-llvm/docs/api/structs/anonymous-ppcasmparser-cpp-/ppcoperand/#a12210c238d328df79afbb1bf5b8d330f">anonymous{PPCAsmParser.cpp}::PPCOperand::addRegACCRCOperands</a>, <a href="/web-llvm/docs/api/structs/anonymous-ppcasmparser-cpp-/ppcoperand/#ac9f272922c818ce3d068c8da3b088e51">anonymous{PPCAsmParser.cpp}::PPCOperand::addRegCRBITRCOperands</a>, <a href="/web-llvm/docs/api/structs/anonymous-ppcasmparser-cpp-/ppcoperand/#a261bc82cf89578d4cad2017373d2000d">anonymous{PPCAsmParser.cpp}::PPCOperand::addRegCRRCOperands</a>, <a href="/web-llvm/docs/api/structs/anonymous-ppcasmparser-cpp-/ppcoperand/#a179ed03cc48e9a5569d66a7f44576942">anonymous{PPCAsmParser.cpp}::PPCOperand::addRegDMRpRCOperands</a>, <a href="/web-llvm/docs/api/structs/anonymous-ppcasmparser-cpp-/ppcoperand/#af033d8ccbf4172c8b4e289ddc6b645f7">anonymous{PPCAsmParser.cpp}::PPCOperand::addRegDMRRCOperands</a>, <a href="/web-llvm/docs/api/structs/anonymous-ppcasmparser-cpp-/ppcoperand/#ad5ff3b4938bbefa984a374310ba12b8e">anonymous{PPCAsmParser.cpp}::PPCOperand::addRegDMRROWpRCOperands</a>, <a href="/web-llvm/docs/api/structs/anonymous-ppcasmparser-cpp-/ppcoperand/#a6b9fc1453025fe740abd2314b1edce41">anonymous{PPCAsmParser.cpp}::PPCOperand::addRegDMRROWRCOperands</a>, <a href="/web-llvm/docs/api/structs/anonymous-ppcasmparser-cpp-/ppcoperand/#ae660622f18164d2564fc611c31e5dfe6">anonymous{PPCAsmParser.cpp}::PPCOperand::addRegF4RCOperands</a>, <a href="/web-llvm/docs/api/structs/anonymous-ppcasmparser-cpp-/ppcoperand/#a46e8f65e73a8c1ec486feacbd11b8598">anonymous{PPCAsmParser.cpp}::PPCOperand::addRegF8RCOperands</a>, <a href="/web-llvm/docs/api/structs/anonymous-ppcasmparser-cpp-/ppcoperand/#adfbd9f9bd8886de9cc1ce69aa19cecce">anonymous{PPCAsmParser.cpp}::PPCOperand::addRegFpRCOperands</a>, <a href="/web-llvm/docs/api/structs/anonymous-ppcasmparser-cpp-/ppcoperand/#a4f7c8642744e66352d3f0484f6b9f291">anonymous{PPCAsmParser.cpp}::PPCOperand::addRegG8pRCOperands</a>, <a href="/web-llvm/docs/api/structs/anonymous-ppcasmparser-cpp-/ppcoperand/#a6a926e9234ebdc634051a8cc4a884dab">anonymous{PPCAsmParser.cpp}::PPCOperand::addRegG8RCNoX0Operands</a>, <a href="/web-llvm/docs/api/structs/anonymous-ppcasmparser-cpp-/ppcoperand/#ad8399dd3de3aaf78884b2133c214ec5d">anonymous{PPCAsmParser.cpp}::PPCOperand::addRegG8RCOperands</a>, <a href="/web-llvm/docs/api/structs/anonymous-ppcasmparser-cpp-/ppcoperand/#a9fcff4b5ab16b5126b53e6221f72e4fe">anonymous{PPCAsmParser.cpp}::PPCOperand::addRegGPRCNoR0Operands</a>, <a href="/web-llvm/docs/api/structs/anonymous-ppcasmparser-cpp-/ppcoperand/#ab6d7068f5331beed20c505ac25bf75e6">anonymous{PPCAsmParser.cpp}::PPCOperand::addRegGPRCOperands</a>, <a href="/web-llvm/docs/api/structs/anonymous-ppcasmparser-cpp-/ppcoperand/#a2fb6dfb246e08cada6c1ee959fa370b5">anonymous{PPCAsmParser.cpp}::PPCOperand::addRegGxRCNoR0Operands</a>, <a href="/web-llvm/docs/api/structs/anonymous-ppcasmparser-cpp-/ppcoperand/#a520869629199796c869900cd4531fb96">anonymous{PPCAsmParser.cpp}::PPCOperand::addRegGxRCOperands</a>, <a href="/web-llvm/docs/api/classes/anonymous-armasmparser-cpp-/armoperand/#af5b3d3386caf9a9425af9379bae1f13f">anonymous{ARMAsmParser.cpp}::ARMOperand::addRegListOperands</a>, <a href="/web-llvm/docs/api/structs/anonymous-cskyasmparser-cpp-/cskyoperand/#a87ea4b3846e4d8daf60afad674bb0fb0">anonymous{CSKYAsmParser.cpp}::CSKYOperand::addRegListOperands</a>, <a href="/web-llvm/docs/api/classes/anonymous-mipsasmparser-cpp-/mipsoperand/#a321bb283c53099e773b935a368f7f738">anonymous{MipsAsmParser.cpp}::MipsOperand::addRegListOperands</a>, <a href="/web-llvm/docs/api/classes/anonymous-armasmparser-cpp-/armoperand/#a49e5f673f43aedf3325832c920843cc7">anonymous{ARMAsmParser.cpp}::ARMOperand::addRegListWithAPSROperands</a>, <a href="/web-llvm/docs/api/classes/anonymous-aarch64asmparser-cpp-/aarch64operand/#a834f5cf804b7eb070f1fb2cd8498f7eb">anonymous{AArch64AsmParser.cpp}::AArch64Operand::addRegOperands</a>, <a href="/web-llvm/docs/api/classes/anonymous-amdgpuasmparser-cpp-/amdgpuoperand/#aa66df54e14d6219d63e025455bfe52ae">anonymous{AMDGPUAsmParser.cpp}::AMDGPUOperand::addRegOperands</a>, <a href="/web-llvm/docs/api/classes/anonymous-armasmparser-cpp-/armoperand/#a645d5ef26292f8217b0a8822a8f104b4">anonymous{ARMAsmParser.cpp}::ARMOperand::addRegOperands</a>, <a href="/web-llvm/docs/api/classes/anonymous-avrasmparser-cpp-/avroperand/#a090fbb87261517d19ba5d7dfea66f50e">anonymous{AVRAsmParser.cpp}::AVROperand::addRegOperands</a>, <a href="/web-llvm/docs/api/structs/anonymous-bpfasmparser-cpp-/bpfoperand/#ade951bfec69d3a224c97705ba13e1739">anonymous{BPFAsmParser.cpp}::BPFOperand::addRegOperands</a>, <a href="/web-llvm/docs/api/structs/anonymous-cskyasmparser-cpp-/cskyoperand/#a326ed8ed376ee7d1fcd009912f1baadf">anonymous{CSKYAsmParser.cpp}::CSKYOperand::addRegOperands</a>, <a href="/web-llvm/docs/api/structs/anonymous-hexagonasmparser-cpp-/hexagonoperand/#a852b3c58b2b3267848e257b36ec634a7">anonymous{HexagonAsmParser.cpp}::HexagonOperand::addRegOperands</a>, <a href="/web-llvm/docs/api/structs/anonymous-lanaiasmparser-cpp-/lanaioperand/#a938a6ff26f09f87928908d016aa961d8">anonymous{LanaiAsmParser.cpp}::LanaiOperand::addRegOperands</a>, <a href="/web-llvm/docs/api/classes/anonymous-loongarchasmparser-cpp-/loongarchoperand/#a987343bc203c352faf89653f4e162c8e">anonymous{LoongArchAsmParser.cpp}::LoongArchOperand::addRegOperands</a>, <a href="/web-llvm/docs/api/classes/anonymous-m68kasmparser-cpp-/m68koperand/#a0e9b31563dafd04ae8a3f4c1114e8f75">anonymous{M68kAsmParser.cpp}::M68kOperand::addRegOperands</a>, <a href="/web-llvm/docs/api/classes/anonymous-mipsasmparser-cpp-/mipsoperand/#a5e039d5a4289fb56c8c46531bfc24097">anonymous{MipsAsmParser.cpp}::MipsOperand::addRegOperands</a>, <a href="/web-llvm/docs/api/classes/anonymous-msp430asmparser-cpp-/msp430operand/#a52c6549504302b3b1bd7ef56e56b1379">anonymous{MSP430AsmParser.cpp}::MSP430Operand::addRegOperands</a>, <a href="/web-llvm/docs/api/structs/anonymous-ppcasmparser-cpp-/ppcoperand/#a7bf3bf9bfc5c81b76395bcce75480146">anonymous{PPCAsmParser.cpp}::PPCOperand::addRegOperands</a>, <a href="/web-llvm/docs/api/structs/anonymous-riscvasmparser-cpp-/riscvoperand/#ab2a8ec62f78c00b33f2cfe5c531366f9">anonymous{RISCVAsmParser.cpp}::RISCVOperand::addRegOperands</a>, <a href="/web-llvm/docs/api/classes/anonymous-sparcasmparser-cpp-/sparcoperand/#a500c52eee2f18bf9ea0c6fd73b20a8d1">anonymous{SparcAsmParser.cpp}::SparcOperand::addRegOperands</a>, <a href="/web-llvm/docs/api/classes/anonymous-systemzasmparser-cpp-/systemzoperand/#ac5e94fab8baba89e96b19929550f2a21">anonymous{SystemZAsmParser.cpp}::SystemZOperand::addRegOperands</a>, <a href="/web-llvm/docs/api/classes/anonymous-veasmparser-cpp-/veoperand/#a6beb2a0c70d355c39054bb56daaf14dd">anonymous{VEAsmParser.cpp}::VEOperand::addRegOperands</a>, <a href="/web-llvm/docs/api/structs/llvm/x86operand/#aa8b46050f49c0070718cb24eaf4b44b0">llvm::X86Operand::addRegOperands</a>, <a href="/web-llvm/docs/api/structs/xtensaoperand/#a2d75e0733155cb6186ceb2829b3361dc">XtensaOperand::addRegOperands</a>, <a href="/web-llvm/docs/api/classes/anonymous-amdgpuasmparser-cpp-/amdgpuoperand/#a26bad8e09401457e56c428aa16473a53">anonymous{AMDGPUAsmParser.cpp}::AMDGPUOperand::addRegOrImmOperands</a>, <a href="/web-llvm/docs/api/classes/anonymous-amdgpuasmparser-cpp-/amdgpuoperand/#a12cbac6ccf1479b95d5f037a4e0721ce">anonymous{AMDGPUAsmParser.cpp}::AMDGPUOperand::addRegOrImmWithFPInputModsOperands</a>, <a href="/web-llvm/docs/api/classes/anonymous-amdgpuasmparser-cpp-/amdgpuoperand/#a625e5c93b568541975f28a4ad8746c4c">anonymous{AMDGPUAsmParser.cpp}::AMDGPUOperand::addRegOrImmWithInputModsOperands</a>, <a href="/web-llvm/docs/api/classes/anonymous-amdgpuasmparser-cpp-/amdgpuoperand/#a9fd65dfd459b859d9234fac35f3513f6">anonymous{AMDGPUAsmParser.cpp}::AMDGPUOperand::addRegOrImmWithIntInputModsOperands</a>, <a href="/web-llvm/docs/api/structs/anonymous-riscvasmparser-cpp-/riscvoperand/#a1c7c494c84693e0715097e5d9bc23c31">anonymous{RISCVAsmParser.cpp}::RISCVOperand::addRegRegOperands</a>, <a href="/web-llvm/docs/api/structs/anonymous-cskyasmparser-cpp-/cskyoperand/#af6301f276f11cc6a65a0fa29296aef93">anonymous{CSKYAsmParser.cpp}::CSKYOperand::addRegSeqOperands</a>, <a href="/web-llvm/docs/api/classes/anonymous-armasmparser-cpp-/armoperand/#a5c3ccc7ccc252771afe2c5992496a232">anonymous{ARMAsmParser.cpp}::ARMOperand::addRegShiftedImmOperands</a>, <a href="/web-llvm/docs/api/classes/anonymous-armasmparser-cpp-/armoperand/#acec3b6c59168a1ad077d5aeb5e00a83d">anonymous{ARMAsmParser.cpp}::ARMOperand::addRegShiftedRegOperands</a>, <a href="/web-llvm/docs/api/structs/anonymous-ppcasmparser-cpp-/ppcoperand/#ae8a5f120ec6a5723f1f2cfea052f096e">anonymous{PPCAsmParser.cpp}::PPCOperand::addRegSPE4RCOperands</a>, <a href="/web-llvm/docs/api/structs/anonymous-ppcasmparser-cpp-/ppcoperand/#a7ed33a86160f649e381a5e36d2ac0025">anonymous{PPCAsmParser.cpp}::PPCOperand::addRegSPERCOperands</a>, <a href="/web-llvm/docs/api/structs/anonymous-ppcasmparser-cpp-/ppcoperand/#a0746159c32e7ac0c99ed85d5ee328103">anonymous{PPCAsmParser.cpp}::PPCOperand::addRegVFRCOperands</a>, <a href="/web-llvm/docs/api/structs/anonymous-ppcasmparser-cpp-/ppcoperand/#ad06b4630ea0969c8091479fa22a5a5bc">anonymous{PPCAsmParser.cpp}::PPCOperand::addRegVRRCOperands</a>, <a href="/web-llvm/docs/api/structs/anonymous-ppcasmparser-cpp-/ppcoperand/#ae671f24372f1086564183e87fa417d64">anonymous{PPCAsmParser.cpp}::PPCOperand::addRegVSFRCOperands</a>, <a href="/web-llvm/docs/api/structs/anonymous-ppcasmparser-cpp-/ppcoperand/#ae738609c642f9c748c350ac993771f5a">anonymous{PPCAsmParser.cpp}::PPCOperand::addRegVSRCOperands</a>, <a href="/web-llvm/docs/api/structs/anonymous-ppcasmparser-cpp-/ppcoperand/#a148f711934b9ce4ad92cedcc83542771">anonymous{PPCAsmParser.cpp}::PPCOperand::addRegVSRpEvenRCOperands</a>, <a href="/web-llvm/docs/api/structs/anonymous-ppcasmparser-cpp-/ppcoperand/#a994642f0fa42d7b1ec9557c989e816e5">anonymous{PPCAsmParser.cpp}::PPCOperand::addRegVSRpRCOperands</a>, <a href="/web-llvm/docs/api/structs/anonymous-ppcasmparser-cpp-/ppcoperand/#a084aa0e18d26956a3e8c10627318e6d6">anonymous{PPCAsmParser.cpp}::PPCOperand::addRegVSSRCOperands</a>, <a href="/web-llvm/docs/api/structs/anonymous-ppcasmparser-cpp-/ppcoperand/#a95631286ee78d31fa6a320bdd65adf1a">anonymous{PPCAsmParser.cpp}::PPCOperand::addRegWACC_HIRCOperands</a>, <a href="/web-llvm/docs/api/structs/anonymous-ppcasmparser-cpp-/ppcoperand/#ad1fb4b2250fe4553fafb1966344239be">anonymous{PPCAsmParser.cpp}::PPCOperand::addRegWACCRCOperands</a>, <a href="/web-llvm/docs/api/classes/anonymous-amdgpuasmparser-cpp-/amdgpuoperand/#a33dbb12eab27e5ccb053b79af2fc9686">anonymous{AMDGPUAsmParser.cpp}::AMDGPUOperand::addRegWithFPInputModsOperands</a>, <a href="/web-llvm/docs/api/classes/anonymous-amdgpuasmparser-cpp-/amdgpuoperand/#a31034030d9e1080963a9033b29df4df8">anonymous{AMDGPUAsmParser.cpp}::AMDGPUOperand::addRegWithInputModsOperands</a>, <a href="/web-llvm/docs/api/classes/anonymous-amdgpuasmparser-cpp-/amdgpuoperand/#ab0bd16ede66efa2c0ef9f34924fbc39d">anonymous{AMDGPUAsmParser.cpp}::AMDGPUOperand::addRegWithIntInputModsOperands</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/arm/armisellowering-cpp/#a0aa60141f3fc64eccae5554fa3eb6426">AddRequiredExtensionForVMULL</a>, <a href="/web-llvm/docs/api/structs/anonymous-riscvasmparser-cpp-/riscvoperand/#af18328b40cba50468c5a380fb0d86eeb">anonymous{RISCVAsmParser.cpp}::RISCVOperand::addRlistOperands</a>, <a href="/web-llvm/docs/api/classes/anonymous-armasmparser-cpp-/armoperand/#a4b06a7f3f9931e6b418f61f97b49ba69">anonymous{ARMAsmParser.cpp}::ARMOperand::addRotImmOperands</a>, <a href="/web-llvm/docs/api/structs/anonymous-hexagonloopidiomrecognition-cpp-/simplifier/#ad9e4684b3e21c0fd381d86da8bcc9aa7">anonymous{HexagonLoopIdiomRecognition.cpp}::Simplifier::addRule</a>, <a href="/web-llvm/docs/api/structs/anonymous-ppcasmparser-cpp-/ppcoperand/#abc4166605fc07257d0de56a87f4b3f0d">anonymous{PPCAsmParser.cpp}::PPCOperand::addS16ImmOperands</a>, <a href="/web-llvm/docs/api/structs/anonymous-hexagonasmparser-cpp-/hexagonoperand/#a9766df7b4d9e7ceb0b822eab1e4bbf74">anonymous{HexagonAsmParser.cpp}::HexagonOperand::addsgp10ConstOperands</a>, <a href="/web-llvm/docs/api/classes/anonymous-sparcasmparser-cpp-/sparcoperand/#ab0e888cfad203facb901a854abbd55bd">anonymous{SparcAsmParser.cpp}::SparcOperand::addShiftAmtImm5Operands</a>, <a href="/web-llvm/docs/api/classes/anonymous-sparcasmparser-cpp-/sparcoperand/#ad6b9b488e9a3e2497904fa75954877cc">anonymous{SparcAsmParser.cpp}::SparcOperand::addShiftAmtImm6Operands</a>, <a href="/web-llvm/docs/api/classes/anonymous-armasmparser-cpp-/armoperand/#a9ff8a6126ecd827e2cfd20a38d93575d">anonymous{ARMAsmParser.cpp}::ARMOperand::addShifterImmOperands</a>, <a href="/web-llvm/docs/api/classes/anonymous-aarch64asmparser-cpp-/aarch64operand/#ad007797dfd6b5c922a9818fd215aebd0">anonymous{AArch64AsmParser.cpp}::AArch64Operand::addShifterOperands</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/powerpc/ppcisellowering-cpp/#a1a0cd3e4178d08fadb03d4e4e9404dcd">addShuffleForVecExtend</a>, <a href="/web-llvm/docs/api/structs/anonymous-hexagonasmparser-cpp-/hexagonoperand/#a4664c509547eec1f1063959c2159a6b3">anonymous{HexagonAsmParser.cpp}::HexagonOperand::addSignedImmOperands</a>, <a href="/web-llvm/docs/api/classes/anonymous-aarch64asmparser-cpp-/aarch64operand/#a275d93f01f3c0461c602869aa89a1fad">anonymous{AArch64AsmParser.cpp}::AArch64Operand::addSIMDImmType10Operands</a>, <a href="/web-llvm/docs/api/classes/anonymous-veasmparser-cpp-/veoperand/#aad77ccb880c157422ef649abf1f91536">anonymous{VEAsmParser.cpp}::VEOperand::addSImm7Operands</a>, <a href="/web-llvm/docs/api/classes/anonymous-mipsasmparser-cpp-/mipsoperand/#a3be9193f261a65d4f60d619cd6caec18">anonymous{MipsAsmParser.cpp}::MipsOperand::addSImmOperands</a>, <a href="/web-llvm/docs/api/structs/anonymous-riscvasmparser-cpp-/riscvoperand/#a2cd3aa898829c8a5af0f9f8b6c0b369f">anonymous{RISCVAsmParser.cpp}::RISCVOperand::addSpimmOperands</a>, <a href="/web-llvm/docs/api/classes/anonymous-armasmparser-cpp-/armoperand/#a80cb2a08ed99555a2f97f32d6939e9ff">anonymous{ARMAsmParser.cpp}::ARMOperand::addSPRRegListOperands</a>, <a href="/web-llvm/docs/api/structs/llvm/x86operand/#a49468934edef8e57cda0f8aad36c57e9">llvm::X86Operand::addSrcIdxOperands</a>, <a href="/web-llvm/docs/api/classes/anonymous-mipsasmparser-cpp-/mipsoperand/#a6daf6a91dc04b3ec1d1c68ea065f8970">anonymous{MipsAsmParser.cpp}::MipsOperand::addStrictlyAFGR64AsmRegOperands</a>, <a href="/web-llvm/docs/api/classes/anonymous-mipsasmparser-cpp-/mipsoperand/#a8dc5d7e426b9a1e3d3d56db70401bde6">anonymous{MipsAsmParser.cpp}::MipsOperand::addStrictlyFGR32AsmRegOperands</a>, <a href="/web-llvm/docs/api/classes/anonymous-mipsasmparser-cpp-/mipsoperand/#aab29a0e4b7912dd0fd49c5d2fcab3747">anonymous{MipsAsmParser.cpp}::MipsOperand::addStrictlyFGR64AsmRegOperands</a>, <a href="/web-llvm/docs/api/classes/anonymous-aarch64asmparser-cpp-/aarch64operand/#adbe61948d3299303dc25faf037775ae3">anonymous{AArch64AsmParser.cpp}::AArch64Operand::addStridedVectorListOperands</a>, <a href="/web-llvm/docs/api/classes/anonymous-aarch64asmparser-cpp-/aarch64operand/#aec0f3af336e424eb47c2d849c53a9c99">anonymous{AArch64AsmParser.cpp}::AArch64Operand::addSVCROperands</a>, <a href="/web-llvm/docs/api/classes/anonymous-aarch64asmparser-cpp-/aarch64operand/#a32f086ffb95e53ca2321121772ddc00a">anonymous{AArch64AsmParser.cpp}::AArch64Operand::addSysCROperands</a>, <a href="/web-llvm/docs/api/classes/anonymous-aarch64asmparser-cpp-/aarch64operand/#a536cdad3a9f844e78b6003550707b214">anonymous{AArch64AsmParser.cpp}::AArch64Operand::addSyspXzrPairOperand</a>, <a href="/web-llvm/docs/api/classes/anonymous-aarch64asmparser-cpp-/aarch64operand/#a58b5e0864f1dbb517a90f7e7a92946f5">anonymous{AArch64AsmParser.cpp}::AArch64Operand::addSystemPStateFieldWithImm0_15Operands</a>, <a href="/web-llvm/docs/api/classes/anonymous-aarch64asmparser-cpp-/aarch64operand/#a941d8c4c599c4ae4ed4da18d83b17b72">anonymous{AArch64AsmParser.cpp}::AArch64Operand::addSystemPStateFieldWithImm0_1Operands</a>, <a href="/web-llvm/docs/api/classes/anonymous-armasmparser-cpp-/armoperand/#a9564fa88cecc4b7080be2865e0332713">anonymous{ARMAsmParser.cpp}::ARMOperand::addT2MemRegOffsetOperands</a>, <a href="/web-llvm/docs/api/classes/anonymous-armasmparser-cpp-/armoperand/#a10da3880ea18d94668327a3a49d65e25">anonymous{ARMAsmParser.cpp}::ARMOperand::addT2SOImmNegOperands</a>, <a href="/web-llvm/docs/api/classes/anonymous-armasmparser-cpp-/armoperand/#a09aef2e9fa1cc6c6f71dc624d1a0158e">anonymous{ARMAsmParser.cpp}::ARMOperand::addT2SOImmNotOperands</a>, <a href="/web-llvm/docs/api/classes/anonymous-sparcasmparser-cpp-/sparcoperand/#ad01d695c2a1059da620343016ad5fff4">anonymous{SparcAsmParser.cpp}::SparcOperand::addTailRelocSymOperands</a>, <a href="/web-llvm/docs/api/classes/anonymous-armasmparser-cpp-/armoperand/#ac9f4924954e02e8c08e6ad3607bc8916">anonymous{ARMAsmParser.cpp}::ARMOperand::addThumbBranchTargetOperands</a>, <a href="/web-llvm/docs/api/classes/anonymous-armasmparser-cpp-/armoperand/#a31a9eafb0a15b40afecf4445f06dc73e">anonymous{ARMAsmParser.cpp}::ARMOperand::addThumbMemPCOperands</a>, <a href="/web-llvm/docs/api/classes/anonymous-armasmparser-cpp-/armoperand/#ac7b319451b0950021d0225105ce5f61e">anonymous{ARMAsmParser.cpp}::ARMOperand::addThumbModImmNeg1_7Operands</a>, <a href="/web-llvm/docs/api/classes/anonymous-armasmparser-cpp-/armoperand/#a7b235456f07b4a6c7a67a7a21914ae43">anonymous{ARMAsmParser.cpp}::ARMOperand::addThumbModImmNeg8_255Operands</a>, <a href="/web-llvm/docs/api/structs/llvm/x86operand/#a3d9f319c365afc3c199b8d1f179003bd">llvm::X86Operand::addTILEPairOperands</a>, <a href="/web-llvm/docs/api/structs/anonymous-ppcasmparser-cpp-/ppcoperand/#ab4ff241ea58ce22b2fb48a3fbb7f1085">anonymous{PPCAsmParser.cpp}::PPCOperand::addTLSRegOperands</a>, <a href="/web-llvm/docs/api/classes/anonymous-dagcombiner-cpp-/dagcombiner/#a3a47a8f2663afb2702e9c810eaf41e40">anonymous{DAGCombiner.cpp}::DAGCombiner::AddToWorklist</a>, <a href="/web-llvm/docs/api/structs/llvm/targetlowering/dagcombinerinfo/#a9e3e1453357b1b1cd870a4ac3528f918">llvm::TargetLowering::DAGCombinerInfo::AddToWorklist</a>, <a href="/web-llvm/docs/api/classes/anonymous-armasmparser-cpp-/armoperand/#acd2d8840bec9db8dc8d26c01be00f78b">anonymous{ARMAsmParser.cpp}::ARMOperand::addTraceSyncBarrierOptOperands</a>, <a href="/web-llvm/docs/api/structs/anonymous-ppcasmparser-cpp-/ppcoperand/#a25f8f8640a87306d856954ff636e3c54">anonymous{PPCAsmParser.cpp}::PPCOperand::addU16ImmOperands</a>, <a href="/web-llvm/docs/api/classes/anonymous-veasmparser-cpp-/veoperand/#a2dcf33b8ffe4183951334e3c0e088725">anonymous{VEAsmParser.cpp}::VEOperand::addUImm0to2Operands</a>, <a href="/web-llvm/docs/api/classes/anonymous-aarch64asmparser-cpp-/aarch64operand/#aade413b77f569da1d358d025182ced99">anonymous{AArch64AsmParser.cpp}::AArch64Operand::addUImm12OffsetOperands</a>, <a href="/web-llvm/docs/api/classes/anonymous-veasmparser-cpp-/veoperand/#a09beb3b79e92789df7fb4108392c9caf">anonymous{VEAsmParser.cpp}::VEOperand::addUImm1Operands</a>, <a href="/web-llvm/docs/api/classes/anonymous-veasmparser-cpp-/veoperand/#a13e7751617a73e903af65c7ee5724ec8">anonymous{VEAsmParser.cpp}::VEOperand::addUImm2Operands</a>, <a href="/web-llvm/docs/api/classes/anonymous-veasmparser-cpp-/veoperand/#a81c2287df17f1ff3170f7b4a756658d4">anonymous{VEAsmParser.cpp}::VEOperand::addUImm3Operands</a>, <a href="/web-llvm/docs/api/classes/anonymous-veasmparser-cpp-/veoperand/#a6a52170d893459cc4ecbb372cfc1de13">anonymous{VEAsmParser.cpp}::VEOperand::addUImm4Operands</a>, <a href="/web-llvm/docs/api/classes/anonymous-aarch64asmparser-cpp-/aarch64operand/#a3cc87770d7b78bdaebb4b74db9dfd78f">anonymous{AArch64AsmParser.cpp}::AArch64Operand::addUImm6Operands</a>, <a href="/web-llvm/docs/api/classes/anonymous-veasmparser-cpp-/veoperand/#ab9ed77a4dde06ce34afe3d812b7e1690">anonymous{VEAsmParser.cpp}::VEOperand::addUImm6Operands</a>, <a href="/web-llvm/docs/api/classes/anonymous-veasmparser-cpp-/veoperand/#a40723159a1f5e6f2348325a64175b67a">anonymous{VEAsmParser.cpp}::VEOperand::addUImm7Operands</a>, <a href="/web-llvm/docs/api/classes/anonymous-mipsasmparser-cpp-/mipsoperand/#afc44730a9c17cc064aba9a4c2212f9da">anonymous{MipsAsmParser.cpp}::MipsOperand::addUImmOperands</a>, <a href="/web-llvm/docs/api/classes/anonymous-armasmparser-cpp-/armoperand/#a2deb61ee90371c3718447dbe32d0d10a">anonymous{ARMAsmParser.cpp}::ARMOperand::addUnsignedOffset_b8s2Operands</a>, <a href="/web-llvm/docs/api/classes/anonymous-armasmparser-cpp-/armoperand/#a2287edccafae1d399ac9338429d056e9">anonymous{ARMAsmParser.cpp}::ARMOperand::addVecListIndexedOperands</a>, <a href="/web-llvm/docs/api/classes/anonymous-armasmparser-cpp-/armoperand/#ae6f6ab0591c1d91254dbb0cadecfca8f">anonymous{ARMAsmParser.cpp}::ARMOperand::addVecListOperands</a>, <a href="/web-llvm/docs/api/classes/anonymous-armasmparser-cpp-/armoperand/#a66aeb0ab4c553d5333da28689323bdaa">anonymous{ARMAsmParser.cpp}::ARMOperand::addVectorIndex16Operands</a>, <a href="/web-llvm/docs/api/classes/anonymous-armasmparser-cpp-/armoperand/#a3108dfa9b9ff61f1e1558e251947d377">anonymous{ARMAsmParser.cpp}::ARMOperand::addVectorIndex32Operands</a>, <a href="/web-llvm/docs/api/classes/anonymous-armasmparser-cpp-/armoperand/#a5c3fd94476330f0ba7c87ef6789de4c1">anonymous{ARMAsmParser.cpp}::ARMOperand::addVectorIndex64Operands</a>, <a href="/web-llvm/docs/api/classes/anonymous-armasmparser-cpp-/armoperand/#a199259455583be350d9673ed7275bdae">anonymous{ARMAsmParser.cpp}::ARMOperand::addVectorIndex8Operands</a>, <a href="/web-llvm/docs/api/classes/anonymous-aarch64asmparser-cpp-/aarch64operand/#a7d1858fef112dddb614e924ca0c714b4">anonymous{AArch64AsmParser.cpp}::AArch64Operand::addVectorIndexOperands</a>, <a href="/web-llvm/docs/api/classes/anonymous-aarch64asmparser-cpp-/aarch64operand/#a4ec1a2d3550a48035bda06364865c408">anonymous{AArch64AsmParser.cpp}::AArch64Operand::addVectorListOperands</a>, <a href="/web-llvm/docs/api/classes/anonymous-aarch64asmparser-cpp-/aarch64operand/#ac6a4ccdc548344f69822f6914bb40e35">anonymous{AArch64AsmParser.cpp}::AArch64Operand::addVectorReg0to7Operands</a>, <a href="/web-llvm/docs/api/classes/anonymous-aarch64asmparser-cpp-/aarch64operand/#a69eda91bc353715ea7d51bc6d0d2e849">anonymous{AArch64AsmParser.cpp}::AArch64Operand::addVectorReg128Operands</a>, <a href="/web-llvm/docs/api/classes/anonymous-aarch64asmparser-cpp-/aarch64operand/#a1b12b775c6f9e800fb7fd722fd6a5e90">anonymous{AArch64AsmParser.cpp}::AArch64Operand::addVectorReg64Operands</a>, <a href="/web-llvm/docs/api/classes/anonymous-aarch64asmparser-cpp-/aarch64operand/#aac4e8905e8ea71e68562f82797840d6d">anonymous{AArch64AsmParser.cpp}::AArch64Operand::addVectorRegLoOperands</a>, <a href="/web-llvm/docs/api/classes/anonymous-armasmparser-cpp-/armoperand/#ae02dcfe544c083fe2a3949c50b389718">anonymous{ARMAsmParser.cpp}::ARMOperand::addVPTPredNOperands</a>, <a href="/web-llvm/docs/api/classes/anonymous-armasmparser-cpp-/armoperand/#a45c157d6c567f135196ef6a2c1571409">anonymous{ARMAsmParser.cpp}::ARMOperand::addVPTPredROperands</a>, <a href="/web-llvm/docs/api/structs/anonymous-riscvasmparser-cpp-/riscvoperand/#a5515c4f1f3e9f0e04e83a787020af209">anonymous{RISCVAsmParser.cpp}::RISCVOperand::addVTypeIOperands</a>, <a href="/web-llvm/docs/api/classes/anonymous-veasmparser-cpp-/veoperand/#a5d0b28e5bd35f80a1e8b021e62a19cae">anonymous{VEAsmParser.cpp}::VEOperand::addZeroOperands</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/systemz/systemzisellowering-cpp/#a4f999e29e1c7e89f1f87f7ff3f3fa379">adjustForFNeg</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/systemz/systemzisellowering-cpp/#a0ea933cf7c687d2caba4d0fd66d7ed47">adjustForLTGFR</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/systemz/systemzisellowering-cpp/#a6d8c34094b346eb0009cabb44bf3eaf7">adjustForSubtraction</a>, <a href="/web-llvm/docs/api/classes/llvm/intervalmapimpl/nodebase/#a70a77b0f022fde493ace11aab5d70101">llvm::IntervalMapImpl::NodeBase&lt; std::pair&lt; KeyT, KeyT &gt;, ValT, LeafSize &gt;::adjustFromLeftSib</a>, <a href="/web-llvm/docs/api/namespaces/llvm/detail/anonymous-apfloat-cpp-/#af9b4f3c32f38913159a0ab75cb4bf133">llvm::detail::anonymous{APFloat.cpp}::AdjustToPrecision</a>, <a href="/web-llvm/docs/api/classes/llvm/aliasscopenode/#a62aa701200db44d524078279fc44a5cc">llvm::AliasScopeNode::AliasScopeNode</a>, <a href="/web-llvm/docs/api/classes/llvm/threadsafeallocator/#a3675bca5885ec5fdfbc222e625bbd473">llvm::ThreadSafeAllocator&lt; AllocatorType &gt;::Allocate</a>, <a href="/web-llvm/docs/api/classes/anonymous-itaniumdemangle-cpp-/bumppointerallocator/#a27cdc926feeb3d0ead106c604c68518f">anonymous{ItaniumDemangle.cpp}::BumpPointerAllocator::allocate</a>, <a href="/web-llvm/docs/api/classes/llvm/memoryphi/#a0238c3903f55dd3155d2a791e5a0ea2c">llvm::MemoryPhi::allocHungoffUses</a>, <a href="/web-llvm/docs/api/classes/llvm/phinode/#a2d9bdd089124b3dfea76eb13c60ecac8">llvm::PHINode::allocHungoffUses</a>, <a href="/web-llvm/docs/api/namespaces/llvm/isd/#a933d79e63e855d7c90bf161355c008ec">llvm::ISD::allOperandsUndef</a>, <a href="/web-llvm/docs/api/classes/llvm/amdgputargetlowering/#aca708dccf3303e8529183ba47e14642b">llvm::AMDGPUTargetLowering::allUsesHaveSourceMods</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/powerpc/ppciseldagtodag-cpp/#a5843fbc0765c997fa4bf9b6d876891b6">allUsesTruncate</a>, <a href="/web-llvm/docs/api/classes/llvm/amdgpudagtodagisel/#a902b69968026e292a115616b07ae111d">llvm::AMDGPUDAGToDAGISel::AMDGPUDAGToDAGISel</a>, <a href="/web-llvm/docs/api/classes/llvm/spirv/convergenceregionanalyzer/#aad660d1ec071e1945c2b96bfe4c3704b">llvm::SPIRV::ConvergenceRegionAnalyzer::analyze</a>, <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/instrumentation/pgoinstrumentation-cpp/#a1765b2301f26e0db70d0ba12b3a0e15a">annotateFunctionWithHashMismatch</a>, <a href="/web-llvm/docs/api/structs/llvm/dwarftypeprinter/#abcb3596d8a38517290a40f2fa529876a">llvm::DWARFTypePrinter&lt; DieType &gt;::appendConstVolatileQualifierAfter</a>, <a href="/web-llvm/docs/api/structs/llvm/dwarftypeprinter/#a6b109c547db47dc708d9585c485237ee">llvm::DWARFTypePrinter&lt; DieType &gt;::appendConstVolatileQualifierBefore</a>, <a href="/web-llvm/docs/api/files/lib/lib/support/scalednumber-cpp/#af9cfb5453e82e2e1cef9a73c6b239d96">appendNumber</a>, <a href="/web-llvm/docs/api/structs/anonymous-settheory-cpp-/decimateop/#a8f070ca2228c4942d2e51187cd9fe1d2">anonymous{SetTheory.cpp}::DecimateOp::apply2</a>, <a href="/web-llvm/docs/api/structs/anonymous-settheory-cpp-/rotop/#a3bdddb1972b8e6ad5a64c921e38f6794">anonymous{SetTheory.cpp}::RotOp::apply2</a>, <a href="/web-llvm/docs/api/structs/anonymous-settheory-cpp-/setintbinop/#ab705d6d3f3438f5cb077cd2632a204ee">anonymous{SetTheory.cpp}::SetIntBinOp::apply2</a>, <a href="/web-llvm/docs/api/structs/anonymous-settheory-cpp-/shlop/#aae3550d12fea16af5b89c43371e66844">anonymous{SetTheory.cpp}::ShlOp::apply2</a>, <a href="/web-llvm/docs/api/structs/anonymous-settheory-cpp-/truncop/#ac8dd7130676944aa7c321ac3a447c910">anonymous{SetTheory.cpp}::TruncOp::apply2</a>, <a href="/web-llvm/docs/api/namespaces/anonymous-machinedebugify-cpp-/#aa828309ad55f30355cd07c12017a2263">anonymous{MachineDebugify.cpp}::applyDebugifyMetadataToMachineFunction</a>, <a href="/web-llvm/docs/api/classes/llvm/amdgpuregisterbankinfo/#a66655fdd73a951d10ad6fb804f0fac98">llvm::AMDGPURegisterBankInfo::applyMappingImpl</a>, <a href="/web-llvm/docs/api/classes/llvm/sdnode/#a921a083162ebeec8f46240c1a48fef7b">llvm::SDNode::areOnlyUsersOf</a>, <a href="/web-llvm/docs/api/structs/llvm/diagnosticinfooptimizationbase/argument/#aa869fae0f884df7e9ac24873bf903c99">llvm::DiagnosticInfoOptimizationBase::Argument::Argument</a>, <a href="/web-llvm/docs/api/structs/llvm/diagnosticinfooptimizationbase/argument/#ae6a66141b38930cd57f8494b9231d09b">llvm::DiagnosticInfoOptimizationBase::Argument::Argument</a>, <a href="/web-llvm/docs/api/structs/llvm/diagnosticinfooptimizationbase/argument/#a9ddce73e55a7e02e3b859601817ccede">llvm::DiagnosticInfoOptimizationBase::Argument::Argument</a>, <a href="/web-llvm/docs/api/structs/llvm/diagnosticinfooptimizationbase/argument/#a072ba5eeec04acb5bb4549fb3968da0c">llvm::DiagnosticInfoOptimizationBase::Argument::Argument</a>, <a href="/web-llvm/docs/api/structs/llvm/diagnosticinfooptimizationbase/argument/#a9d07aa6f42e18144bd41ee7283d7e12e">llvm::DiagnosticInfoOptimizationBase::Argument::Argument</a>, <a href="/web-llvm/docs/api/structs/llvm/diagnosticinfooptimizationbase/argument/#a42cda9362ef6e1e04eadf091f82a45a2">llvm::DiagnosticInfoOptimizationBase::Argument::Argument</a>, <a href="/web-llvm/docs/api/structs/llvm/diagnosticinfooptimizationbase/argument/#ad05735ac41f09473d0fadebf7f123161">llvm::DiagnosticInfoOptimizationBase::Argument::Argument</a>, <a href="/web-llvm/docs/api/classes/llvm/msgpack/arraydocnode/#a321c0ea44e257246ee630eb346be23fa">llvm::msgpack::ArrayDocNode::ArrayDocNode</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a77e01dbeb9a5c12c3ac69ee1717d338a">llvm::ArrayRef</a>, <a href="/web-llvm/docs/api/classes/llvm/arrayref/#acbeaf6660fa6a272706c71336f0a77b7">llvm::ArrayRef&lt; llvm::cfg::Update&lt; MachineBasicBlock * &gt; &gt;::ArrayRef</a>, <a href="/web-llvm/docs/api/classes/llvm/arrayref/#abce7d9de986edb50fb9673e5015917b0">llvm::ArrayRef&lt; llvm::cfg::Update&lt; MachineBasicBlock * &gt; &gt;::ArrayRef</a>, <a href="/web-llvm/docs/api/classes/llvm/smallvectortemplatecommon/#ae0e4f4c34cddd8f514efe4f9e0accf09">llvm::SmallVectorTemplateCommon&lt; T, typename &gt;::assertSafeToAdd</a>, <a href="/web-llvm/docs/api/classes/llvm/selectiondag/#abb8c86cb032981edbbf6bf507ba2aa32">llvm::SelectionDAG::AssignTopologicalOrder</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/avr/avriseldagtodag-cpp/#ae5156eb20a86dab517fe5b8e19fac322">AVRDAGToDAGISel::select&lt; AVRISD::CALL &gt;</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/avr/avriseldagtodag-cpp/#ae23f9c249fde8d223579843fb4e03682">AVRDAGToDAGISel::select&lt; ISD::BRIND &gt;</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/avr/avriseldagtodag-cpp/#ad8797a2f3292ccfcfbdd7deee7e25945">AVRDAGToDAGISel::select&lt; ISD::FrameIndex &gt;</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/avr/avriseldagtodag-cpp/#a566a922274e3694fe81033c9abce79a2">AVRDAGToDAGISel::select&lt; ISD::LOAD &gt;</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/avr/avriseldagtodag-cpp/#ae711b36c828904fa303e8b920c057f41">AVRDAGToDAGISel::select&lt; ISD::STORE &gt;</a>, <a href="/web-llvm/docs/api/classes/llvm/avrtargetlowering/#ac14830797eaee15361f1585a2126def2">llvm::AVRTargetLowering::AVRTargetLowering</a>, <a href="/web-llvm/docs/api/classes/llvm/sdnodeiterator/#af14c003d9f4913dbc8b7daed0807183d">llvm::SDNodeIterator::begin</a>, <a href="/web-llvm/docs/api/classes/llvm/sunititerator/#a7fafbbefc8dae7eb2b3d348e0a6e4aa6">llvm::SUnitIterator::begin</a>, <a href="/web-llvm/docs/api/files/lib/lib/codegen/lib/codegen/globalisel/legalizerhelper-cpp/#a497ca5acebfbe31e76e7c05991519336">broadcastSrcOp</a>, <a href="/web-llvm/docs/api/files/lib/lib/codegen/lib/codegen/selectiondag/targetlowering-cpp/#af1364d76011b791bbac39ca8470dd2bf">BuildExactSDIV</a>, <a href="/web-llvm/docs/api/files/lib/lib/codegen/lib/codegen/selectiondag/targetlowering-cpp/#a1ca08074fa512b26eb7e8e88833892d9">BuildExactUDIV</a>, <a href="/web-llvm/docs/api/classes/llvm/anonymous-amdgpusplitmodule-cpp-/splitgraph/#a85511f1d0a02c18e6c6dd590344664a4">llvm::anonymous{AMDGPUSplitModule.cpp}::SplitGraph::buildGraph</a>, <a href="/web-llvm/docs/api/classes/llvm/lazycallgraph/#a72787ab6acfbe504a11ca1d927513356">llvm::LazyCallGraph::buildRefSCCs</a>, <a href="/web-llvm/docs/api/classes/anonymous-amdgpulowermoduleldspass-cpp-/amdgpulowermodulelds/#ad6c0f52a75bef49176db797774e8dc2c">anonymous{AMDGPULowerModuleLDSPass.cpp}::AMDGPULowerModuleLDS::buildRepresentativeDynamicLDSInstance</a>, <a href="/web-llvm/docs/api/classes/llvm/targetlowering/#a36c8f3817aaf6184163227ef33e08032">llvm::TargetLowering::BuildSDIV</a>, <a href="/web-llvm/docs/api/classes/llvm/ppctargetlowering/#a5583b4d2c0c7813f44df3fe6d42d20e1">llvm::PPCTargetLowering::BuildSDIVPow2</a>, <a href="/web-llvm/docs/api/classes/llvm/targetlowering/#a10e676263a198d8cd480918492893dcb">llvm::TargetLowering::BuildSDIVPow2</a>, <a href="/web-llvm/docs/api/classes/llvm/targetlowering/#ac059b1ca86f2540e9fcfbee0a0da1c7c">llvm::TargetLowering::buildSDIVPow2WithCMov</a>, <a href="/web-llvm/docs/api/classes/llvm/targetlowering/#abe774a33e51c905a23e19b7b9803e8eb">llvm::TargetLowering::BuildSREMPow2</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a4d05aa2854cf8b7927d9f162180d1a37">llvm::buildTopDownFuncOrder</a>, <a href="/web-llvm/docs/api/classes/llvm/targetlowering/#a634e703cb950d5425ce8594ea59ef3bd">llvm::TargetLowering::BuildUDIV</a>, <a href="/web-llvm/docs/api/classes/llvm/apint/#ace0bd40e4bee1851ebebb276178d65fc">llvm::APInt::byteSwap</a>, <a href="/web-llvm/docs/api/classes/llvm/selectiondag/#a397c1e0c14beb925e684033aa23ad8c5">llvm::SelectionDAG::calculateDivergence</a>, <a href="/web-llvm/docs/api/structs/llvm/mdnodekeyimpl-790d8f2739f010df55f45d6a1d49d352/#a292d747f08f9f3205408e48de409547c">llvm::MDNodeKeyImpl&lt; GenericDINode &gt;::calculateHash</a>, <a href="/web-llvm/docs/api/structs/llvm/mdnodekeyimpl-4af0d7051d6a9d6ec61ff79a979bea68/#adabb7a070201960968475b768df70c28">llvm::MDNodeKeyImpl&lt; MDTuple &gt;::calculateHash</a>, <a href="/web-llvm/docs/api/classes/llvm/mdnodeopskey/#aea1b184b8290b9c4bed5a42aaa6f1bb1">llvm::MDNodeOpsKey::calculateHash</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/arm/armisellowering-cpp/#aeff434dbdf596ee7867c4b817c57909f">canChangeToInt</a>, <a href="/web-llvm/docs/api/files/lib/lib/codegen/lib/codegen/selectiondag/scheduledagrrlist-cpp/#a6a91ff524836d3fca6cabe37c8fb7dc5">canClobberPhysRegDefs</a>, <a href="/web-llvm/docs/api/files/lib/lib/codegen/lib/codegen/selectiondag/dagcombiner-cpp/#a04cb51bd51ce0d3d114071ed4c38183b">CanCombineFCOPYSIGN_EXTEND_ROUND</a>, <a href="/web-llvm/docs/api/classes/llvm/targetinstrinfo/#a7b8003a932104a6adf3ddbf4435a49f0">llvm::TargetInstrInfo::canCopyGluedNodeDuringSchedule</a>, <a href="/web-llvm/docs/api/classes/llvm/thumb1instrinfo/#abf4cc4a5813e990f6bbdac57138e6638">llvm::Thumb1InstrInfo::canCopyGluedNodeDuringSchedule</a>, <a href="/web-llvm/docs/api/files/lib/lib/codegen/lib/codegen/selectiondag/dagcombiner-cpp/#a631357f1796c922cce73dae4bff6018f">canFoldInAddressingMode</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/arm/armisellowering-cpp/#a36dd5a226839c6599dc871cafd02f716">CanInvertMVEVCMP</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/x86/x86isellowering-cpp/#a682d6bb4daa2daec606a5510e963066a">canLowerByDroppingElements</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/nvptx/nvptxiseldagtodag-cpp/#afd0157878175238e15a984de366313af">canLowerToLDG</a>, <a href="/web-llvm/docs/api/classes/llvm/slpvectorizer/boupslp/#aac9cfeffe904936120849defcaa5afbc">llvm::slpvectorizer::BoUpSLP::canMapToVector</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/x86/x86isellowering-cpp/#ab0e42c8902538c259f008a6e8c2709de">canonicalizeBitSelect</a>, <a href="/web-llvm/docs/api/files/lib/lib/ir/metadata-cpp/#a20a678afa540694502fca3ed77617af8">canonicalizeMetadataForValue</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/x86/x86isellowering-cpp/#ad300ebbb9f1787468bee5209194857ef">canonicalizeShuffleWithOp</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/x86/x86isellowering-cpp/#a63b3ac6067f94151d39d197391477436">canReduceVMulWidth</a>, <a href="/web-llvm/docs/api/classes/llvm/dominatortreebase/#a2881c226e1c102190d54c3b664330aba">llvm::DominatorTreeBase&lt; BlockT, false &gt;::changeImmediateDominator</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/arm/mvegatherscatterlowering-cpp/#a7393bb18a6b67be8b26127bd4aab0cd4">CheckAndCreateOffsetAdd</a>, <a href="/web-llvm/docs/api/files/lib/lib/codegen/lib/codegen/selectiondag/selectiondagisel-cpp/#a617864a293ee07b291bef2224ea10567">CheckAndImm</a>, <a href="/web-llvm/docs/api/files/lib/lib/codegen/lib/codegen/selectiondag/selectiondagisel-cpp/#ab685ee3ee52df310a0f900c4d5084a5b">CheckChild2CondCode</a>, <a href="/web-llvm/docs/api/files/lib/lib/codegen/lib/codegen/selectiondag/selectiondagisel-cpp/#ae6550b720c223cefb6cf9dafefddca5c">CheckChildInteger</a>, <a href="/web-llvm/docs/api/files/lib/lib/codegen/lib/codegen/selectiondag/selectiondagisel-cpp/#a14c617a274bb807748be86583cf743f4">CheckChildSame</a>, <a href="/web-llvm/docs/api/files/lib/lib/codegen/lib/codegen/selectiondag/selectiondagisel-cpp/#a7849fd2c763a1dd266198c0dd4bf96bc">CheckChildType</a>, <a href="/web-llvm/docs/api/classes/llvm/selectiondagisel/#a3b843300218cb16620b8958ac4883fc1">llvm::SelectionDAGISel::CheckComplexPattern</a>, <a href="/web-llvm/docs/api/classes/llvm/amdgpupalmetadata/#a4cbe07926d164ca5df909bd51b351da8">llvm::AMDGPUPALMetadata::checkComputeRegisters</a>, <a href="/web-llvm/docs/api/classes/llvm/amdgpupalmetadata/#ad9cb93d8e26870ae612fc9d8c0a2e1cd">llvm::AMDGPUPALMetadata::checkComputeRegisters</a>, <a href="/web-llvm/docs/api/files/lib/lib/codegen/lib/codegen/selectiondag/selectiondagisel-cpp/#aaab015bad5b65423fd9921361c3c4e57">CheckCondCode</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64iseldagtodag-cpp/#a69c84bdc36fee945e94d62b77e1558f1">checkCVTFixedPointOperandWithFBits</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/siisellowering-cpp/#aac8364da8771a03bcc990c3c0d6ccfb6">checkDot4MulSignedness</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#ab9dac7f805d69b449e960f088af2dd7b">llvm::checkForCycles</a>, <a href="/web-llvm/docs/api/files/lib/lib/codegen/lib/codegen/selectiondag/selectiondag-cpp/#acee00c9f4491296332296054dddfb5d7">checkForCyclesHelper</a>, <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/hipstdpar/hipstdpar-cpp/#ad696038e18d6965dc078902075026d9b">checkIfSupported</a>, <a href="/web-llvm/docs/api/files/lib/lib/codegen/lib/codegen/selectiondag/selectiondagisel-cpp/#a55ddd986b32899ac868a18ee9d1182a1">CheckInteger</a>, <a href="/web-llvm/docs/api/files/lib/lib/codegen/lib/codegen/selectiondag/selectiondagisel-cpp/#ac991de895b0ff223cea1a86df733d619">CheckNodePredicate</a>, <a href="/web-llvm/docs/api/classes/llvm/selectiondagisel/#a246bbdcb892a7c3ff35f94d404ead49e">llvm::SelectionDAGISel::CheckNodePredicate</a>, <a href="/web-llvm/docs/api/classes/llvm/selectiondagisel/#a59165f42726267ed79287fd85ae682c9">llvm::SelectionDAGISel::CheckNodePredicateWithOperands</a>, <a href="/web-llvm/docs/api/classes/anonymous-complexdeinterleavingpass-cpp-/complexdeinterleavinggraph/#a7e6c4318cd8d3ae5bbe88df3d4a58490">anonymous{ComplexDeinterleavingPass.cpp}::ComplexDeinterleavingGraph::checkNodes</a>, <a href="/web-llvm/docs/api/files/lib/lib/codegen/lib/codegen/selectiondag/selectiondagisel-cpp/#ae27ccd25e008885da31b6af396bbb0cf">CheckOpcode</a>, <a href="/web-llvm/docs/api/files/lib/lib/codegen/lib/codegen/selectiondag/selectiondagisel-cpp/#a6699dbb00a8f802ae5f1db4599f93121">CheckOrImm</a>, <a href="/web-llvm/docs/api/files/lib/lib/object/machoobjectfile-cpp/#ad8413e5e66b80672de909764764faf7f">checkOverlappingElement</a>, <a href="/web-llvm/docs/api/files/lib/lib/codegen/lib/codegen/selectiondag/selectiondagisel-cpp/#a79923c0bb7ad7ead32b876800220d6b3">CheckSame</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/mips/mipslegalizerinfo-cpp/#a3a0fb4a3768823cf9aaeff9fa81ec04e">CheckTyN</a>, <a href="/web-llvm/docs/api/files/lib/lib/codegen/lib/codegen/selectiondag/selectiondagisel-cpp/#aa34708a5452c563dc4e8e3630abf6c24">CheckType</a>, <a href="/web-llvm/docs/api/files/lib/lib/codegen/lib/codegen/selectiondag/selectiondagisel-cpp/#a0bc7dc5a84a4f652c92ca80cd2afedc9">CheckValueType</a>, <a href="/web-llvm/docs/api/structs/anonymous-structurizecfg-cpp-/subgraphtraits/#a2a57cd464713ac766df43d7ee1a13b2b">anonymous{StructurizeCFG.cpp}::SubGraphTraits::child_begin</a>, <a href="/web-llvm/docs/api/structs/graphtraits-d346cb7ec23912bbca82c15ec6af2116/#abc8435b94d0327ea1d4cf4b85c5eaa61">GraphTraits&lt; const CallsiteContextGraph&lt; DerivedCCG, FuncTy, CallTy &gt; * &gt;::child_begin</a>, <a href="/web-llvm/docs/api/structs/llvm/domtreegraphtraitsbase/#a97e1d55168048bac513db36c91eba894">llvm::DomTreeGraphTraitsBase&lt; Node, ChildIterator &gt;::child_begin</a>, <a href="/web-llvm/docs/api/structs/llvm/graphtraits-a8d72c603246819e5ff8fe2b8d743d3d/#a74a373f8861255d60e43e9fea0e08208">llvm::GraphTraits&lt; AADepGraphNode * &gt;::child_begin</a>, <a href="/web-llvm/docs/api/structs/llvm/graphtraits-eb8e2dbb744d1632db22c7ccc59afa73/#a231e88b22018a730290bf7e828c787b2">llvm::GraphTraits&lt; ArgumentGraphNode * &gt;::child_begin</a>, <a href="/web-llvm/docs/api/structs/llvm/graphtraits-2bc92823035f996577648daa23ed11c7/#a7567329257991d1152c81dc1d6b54902">llvm::GraphTraits&lt; BasicBlock * &gt;::child_begin</a>, <a href="/web-llvm/docs/api/structs/llvm/graphtraits-41d1cb9c371ec31b99ac20773a2bc6fb/#a165c9f9a001d8a7fa2ce83142dc8445c">llvm::GraphTraits&lt; BlockFrequencyInfo * &gt;::child_begin</a>, <a href="/web-llvm/docs/api/structs/llvm/graphtraits-860e5f7a11c435b145d274344a0415db/#a20073b3e631a14c7639284690a2a3d63">llvm::GraphTraits&lt; BoUpSLP * &gt;::child_begin</a>, <a href="/web-llvm/docs/api/structs/llvm/graphtraits-8397ab5b42ef67d55d2802f6984af943/#af0d79a91210cd2f0f469cf1e0cea0d8c">llvm::GraphTraits&lt; CallGraphNode * &gt;::child_begin</a>, <a href="/web-llvm/docs/api/structs/llvm/graphtraits-9656629af6fba4d53ea66c8963d0c72b/#a4cbd1f332308931f53d78757939ec817">llvm::GraphTraits&lt; const BasicBlock * &gt;::child_begin</a>, <a href="/web-llvm/docs/api/structs/llvm/graphtraits-f12c7d9f96b7809048420bffd7bcf91c/#a0c9556a5db4ea466e14fd4568d2c5562">llvm::GraphTraits&lt; const CallGraphNode * &gt;::child_begin</a>, <a href="/web-llvm/docs/api/structs/llvm/graphtraits-c4751382d4709c00c1c1d640bb60c43b/#af63146c43e815c5dee9e90b2c00c3d8c">llvm::GraphTraits&lt; const DDGNode * &gt;::child_begin</a>, <a href="/web-llvm/docs/api/structs/llvm/graphtraits-f49901f175172e7cfbe6b56041ffd8d7/#a08011cf6ea8afbb269bc872899346654">llvm::GraphTraits&lt; const Loop * &gt;::child_begin</a>, <a href="/web-llvm/docs/api/structs/llvm/graphtraits-5d21b8f453fe72c9ef888c2858a7ce72/#a4a4dee80603bc9cc8ef388665ba71473">llvm::GraphTraits&lt; const MachineBasicBlock * &gt;::child_begin</a>, <a href="/web-llvm/docs/api/structs/llvm/graphtraits-c3a45f7f0dd450384d0784bafc98dec0/#a2570852c57a1c8f69983a68c8a661e22">llvm::GraphTraits&lt; const MachineLoop * &gt;::child_begin</a>, <a href="/web-llvm/docs/api/structs/llvm/graphtraits-34ad45e92d8eecd133e6e79591f93716/#ad84d1a884590165640546c18f0a8fb4f">llvm::GraphTraits&lt; const VPBlockBase * &gt;::child_begin</a>, <a href="/web-llvm/docs/api/structs/llvm/graphtraits-60fe2955c1f6971c9465484c526709fc/#ac9b253ebb1158a4bfa90091fc18f071d">llvm::GraphTraits&lt; DDGNode * &gt;::child_begin</a>, <a href="/web-llvm/docs/api/structs/llvm/graphtraits-5e1f4c1478a77e56af95f6a94081e313/#a628d797391ec416bf22db80fb4836030">llvm::GraphTraits&lt; DotCfgDiffDisplayGraph * &gt;::child_begin</a>, <a href="/web-llvm/docs/api/structs/llvm/graphtraits-973e7b08b5b5818a1d5c6c69da1fa05b/#a134d16a1375ced3b21ef1a0ffabfeaa8">llvm::GraphTraits&lt; Inverse&lt; BasicBlock * &gt; &gt;::child_begin</a>, <a href="/web-llvm/docs/api/structs/llvm/graphtraits-d27a12f208359493deb55564e5902b74/#a727dc9232800b6191663631dbce015f4">llvm::GraphTraits&lt; Inverse&lt; const BasicBlock * &gt; &gt;::child_begin</a>, <a href="/web-llvm/docs/api/structs/llvm/graphtraits-8dab79ad0cf15ea502cd9eb4bb116b20/#ae4b5cdc9acd5163f3cb9c94554b62994">llvm::GraphTraits&lt; Inverse&lt; const MachineBasicBlock * &gt; &gt;::child_begin</a>, <a href="/web-llvm/docs/api/structs/llvm/graphtraits-343d0630a0e99b15bc453d3b888245d8/#affb7a7a3d1a0e6bc8950ef8791c742d3">llvm::GraphTraits&lt; Inverse&lt; MachineBasicBlock * &gt; &gt;::child_begin</a>, <a href="/web-llvm/docs/api/structs/llvm/graphtraits-4eb58d9bcb360b0c1dcb042151ab7b36/#a0a49e10e15326b390485148974790d0b">llvm::GraphTraits&lt; Inverse&lt; MemoryAccess * &gt; &gt;::child_begin</a>, <a href="/web-llvm/docs/api/structs/llvm/graphtraits-6777a894e2bc907768e146187125b22e/#ae908aa836094e9755268e5c35bc7373e">llvm::GraphTraits&lt; Inverse&lt; VPBlockBase * &gt; &gt;::child_begin</a>, <a href="/web-llvm/docs/api/structs/llvm/graphtraits-a12c42fe191dcee87ec2a59ab1fee5fd/#a3c870bfd91132e05f68bd134407e2da4">llvm::GraphTraits&lt; IrreducibleGraph &gt;::child_begin</a>, <a href="/web-llvm/docs/api/structs/llvm/graphtraits-a2008b5f8b21ce1ff8289baaf7093f8a/#a1b756a6719f43bf1b868a0df8072e90e">llvm::GraphTraits&lt; LazyCallGraph * &gt;::child_begin</a>, <a href="/web-llvm/docs/api/structs/llvm/graphtraits-0ea52d7b93b4cfe134cbdc75e8ba07b0/#afa1a6a1d6514f489f7d50329a8092563">llvm::GraphTraits&lt; LazyCallGraph::Node * &gt;::child_begin</a>, <a href="/web-llvm/docs/api/structs/llvm/graphtraits-fcd0a659899357154ff141dcb39152d5/#a6bcb30a724ece212aca6850322a1d249">llvm::GraphTraits&lt; Loop * &gt;::child_begin</a>, <a href="/web-llvm/docs/api/structs/llvm/graphtraits-b9c75e93407b82228c2e4202f39262f5/#ad2117358cc853179e26dea3bbd4b25d3">llvm::GraphTraits&lt; MachineBasicBlock * &gt;::child_begin</a>, <a href="/web-llvm/docs/api/structs/llvm/graphtraits-98588480f432ad6b5e85a9f166846cbf/#a272c42253e24f382127ff6a2c57c75d2">llvm::GraphTraits&lt; MachineBlockFrequencyInfo * &gt;::child_begin</a>, <a href="/web-llvm/docs/api/structs/llvm/graphtraits-cd2f029841e7ddfea4b3dd7735cfc064/#ad9fca950ecd82c66816373210244b538">llvm::GraphTraits&lt; MachineLoop * &gt;::child_begin</a>, <a href="/web-llvm/docs/api/structs/llvm/graphtraits-0dc1828882f98769279a0fe7f513a40d/#a59842d9215dad924f110b2c0a1bdb7f8">llvm::GraphTraits&lt; MemoryAccess * &gt;::child_begin</a>, <a href="/web-llvm/docs/api/structs/llvm/graphtraits-0546ad5ef67fa8ce6d07eef123a5b8c9/#a34adae8e8e487d86a0dc804c351d50d7">llvm::GraphTraits&lt; PGOUseFunc * &gt;::child_begin</a>, <a href="/web-llvm/docs/api/structs/llvm/graphtraits-3415cdfe2a550135494395498d7d0793/#ae940ad2bdc9bc4f32b14425022457970">llvm::GraphTraits&lt; ProfiledCallGraphNode * &gt;::child_begin</a>, <a href="/web-llvm/docs/api/structs/llvm/graphtraits-1eef46228acd7bc9828d384fc7349578/#af18e552cfee5828616b328e7a438e13d">llvm::GraphTraits&lt; RematGraph * &gt;::child_begin</a>, <a href="/web-llvm/docs/api/structs/llvm/graphtraits-404b5b8ef0c47cc568060468de8cfca6/#a1631a81b96c667265c8e56391bf56f6d">llvm::GraphTraits&lt; SDNode * &gt;::child_begin</a>, <a href="/web-llvm/docs/api/structs/llvm/graphtraits-8cbcf8b9166a6c46f5d7e91ca6470b24/#a5e84ac952ffaaf2dbc9bed01fc8339fb">llvm::GraphTraits&lt; SUnit * &gt;::child_begin</a>, <a href="/web-llvm/docs/api/structs/llvm/graphtraits-54af6749b69c1b355796c199a231acf9/#a1df0ebff95cce54041e22832b0d84fb7">llvm::GraphTraits&lt; ValueInfo &gt;::child_begin</a>, <a href="/web-llvm/docs/api/structs/llvm/graphtraits-ac66d4b8671a287a0a0e312ee17ee28d/#adad4a9e180137ac74a35002ff1e36151">llvm::GraphTraits&lt; VPBlockBase * &gt;::child_begin</a>, <a href="/web-llvm/docs/api/structs/llvm/graphtraits-d394e565666085640be20f1e64fdd72b/#a9a567016affd7316a7c59b8f9b0fa4eb">llvm::GraphTraits&lt; VPBlockDeepTraversalWrapper&lt; const VPBlockBase * &gt; &gt;::child_begin</a>, <a href="/web-llvm/docs/api/structs/llvm/graphtraits-9ac678cba1b93dbde91361363a8c8a8e/#aa23188a92e58f4d24281cf91d49bf6d4">llvm::GraphTraits&lt; VPBlockDeepTraversalWrapper&lt; VPBlockBase * &gt; &gt;::child_begin</a>, <a href="/web-llvm/docs/api/structs/llvm/graphtraits-363fa89642305612e9e0e66792192abb/#a2f950c92d2cf85a46b9f8a3509455d5a">llvm::GraphTraits&lt; VPBlockShallowTraversalWrapper&lt; const VPBlockBase * &gt; &gt;::child_begin</a>, <a href="/web-llvm/docs/api/structs/llvm/graphtraits-0bf1ef93d28481823f2981c5bb514c9c/#a3ccb552b826784ccdb49991092c951af">llvm::GraphTraits&lt; VPBlockShallowTraversalWrapper&lt; VPBlockBase * &gt; &gt;::child_begin</a>, <a href="/web-llvm/docs/api/structs/llvm/machinedomtreegraphtraitsbase/#ad301f3cc266947caff26e4f03f043f12">llvm::MachineDomTreeGraphTraitsBase&lt; Node, ChildIterator &gt;::child_begin</a>, <a href="/web-llvm/docs/api/structs/llvm/graphtraits-f12c7d9f96b7809048420bffd7bcf91c/#a29e7af04c7df8aa931112caf0a4a8238">llvm::GraphTraits&lt; const CallGraphNode * &gt;::child_edge_begin</a>, <a href="/web-llvm/docs/api/structs/llvm/graphtraits-c4751382d4709c00c1c1d640bb60c43b/#a969f85bf97d87421292caf76b5379108">llvm::GraphTraits&lt; const DDGNode * &gt;::child_edge_begin</a>, <a href="/web-llvm/docs/api/structs/llvm/graphtraits-60fe2955c1f6971c9465484c526709fc/#a549790b274aec09c51449efe8ba4d17d">llvm::GraphTraits&lt; DDGNode * &gt;::child_edge_begin</a>, <a href="/web-llvm/docs/api/structs/llvm/graphtraits-5e1f4c1478a77e56af95f6a94081e313/#acc70929ec72a6d270a75db79504e9499">llvm::GraphTraits&lt; DotCfgDiffDisplayGraph * &gt;::child_edge_begin</a>, <a href="/web-llvm/docs/api/structs/llvm/graphtraits-54af6749b69c1b355796c199a231acf9/#a22c7599518f8b72893228c323340046e">llvm::GraphTraits&lt; ValueInfo &gt;::child_edge_begin</a>, <a href="/web-llvm/docs/api/structs/llvm/graphtraits-f12c7d9f96b7809048420bffd7bcf91c/#aa1e0b7f23c500778803e664b7dbfe954">llvm::GraphTraits&lt; const CallGraphNode * &gt;::child_edge_end</a>, <a href="/web-llvm/docs/api/structs/llvm/graphtraits-c4751382d4709c00c1c1d640bb60c43b/#a5af5f65a605fd66d21b9911879333ee6">llvm::GraphTraits&lt; const DDGNode * &gt;::child_edge_end</a>, <a href="/web-llvm/docs/api/structs/llvm/graphtraits-60fe2955c1f6971c9465484c526709fc/#a6914c2cf1184d37556786b4300cda926">llvm::GraphTraits&lt; DDGNode * &gt;::child_edge_end</a>, <a href="/web-llvm/docs/api/structs/llvm/graphtraits-5e1f4c1478a77e56af95f6a94081e313/#a0fa1f7a0e32ab56887c5c36ee467177d">llvm::GraphTraits&lt; DotCfgDiffDisplayGraph * &gt;::child_edge_end</a>, <a href="/web-llvm/docs/api/structs/llvm/graphtraits-54af6749b69c1b355796c199a231acf9/#af67d95f0a474235b2b276bac8a569b32">llvm::GraphTraits&lt; ValueInfo &gt;::child_edge_end</a>, <a href="/web-llvm/docs/api/structs/anonymous-structurizecfg-cpp-/subgraphtraits/#acdcafb537a0536ad04b4787c14116248">anonymous{StructurizeCFG.cpp}::SubGraphTraits::child_end</a>, <a href="/web-llvm/docs/api/structs/graphtraits-d346cb7ec23912bbca82c15ec6af2116/#a71242001d791ff4ed791b9f3fb3fcaf6">GraphTraits&lt; const CallsiteContextGraph&lt; DerivedCCG, FuncTy, CallTy &gt; * &gt;::child_end</a>, <a href="/web-llvm/docs/api/structs/llvm/domtreegraphtraitsbase/#a13dd3b6bf591b039a0bce53cc59cb2da">llvm::DomTreeGraphTraitsBase&lt; Node, ChildIterator &gt;::child_end</a>, <a href="/web-llvm/docs/api/structs/llvm/graphtraits-a8d72c603246819e5ff8fe2b8d743d3d/#a25b87d7d450879e0b43d491c48351b46">llvm::GraphTraits&lt; AADepGraphNode * &gt;::child_end</a>, <a href="/web-llvm/docs/api/structs/llvm/graphtraits-eb8e2dbb744d1632db22c7ccc59afa73/#aa4f5d191d29a1a6652aac89920cfef6f">llvm::GraphTraits&lt; ArgumentGraphNode * &gt;::child_end</a>, <a href="/web-llvm/docs/api/structs/llvm/graphtraits-2bc92823035f996577648daa23ed11c7/#a9d3d9cf68f46cb55dc4058dc193bbf54">llvm::GraphTraits&lt; BasicBlock * &gt;::child_end</a>, <a href="/web-llvm/docs/api/structs/llvm/graphtraits-41d1cb9c371ec31b99ac20773a2bc6fb/#a560f909d27eec3a830b25f633cf5a5dd">llvm::GraphTraits&lt; BlockFrequencyInfo * &gt;::child_end</a>, <a href="/web-llvm/docs/api/structs/llvm/graphtraits-860e5f7a11c435b145d274344a0415db/#a0471d402d5bb1c256eeefc915d2bc00b">llvm::GraphTraits&lt; BoUpSLP * &gt;::child_end</a>, <a href="/web-llvm/docs/api/structs/llvm/graphtraits-8397ab5b42ef67d55d2802f6984af943/#a5278399e6c0484924cbe2e4397e62dab">llvm::GraphTraits&lt; CallGraphNode * &gt;::child_end</a>, <a href="/web-llvm/docs/api/structs/llvm/graphtraits-9656629af6fba4d53ea66c8963d0c72b/#af2b11f894073723879a420fae62c94df">llvm::GraphTraits&lt; const BasicBlock * &gt;::child_end</a>, <a href="/web-llvm/docs/api/structs/llvm/graphtraits-f12c7d9f96b7809048420bffd7bcf91c/#a95422a2ee2adad0e624787d408eee365">llvm::GraphTraits&lt; const CallGraphNode * &gt;::child_end</a>, <a href="/web-llvm/docs/api/structs/llvm/graphtraits-c4751382d4709c00c1c1d640bb60c43b/#a0be045cfab048c078ea32d0fca42603b">llvm::GraphTraits&lt; const DDGNode * &gt;::child_end</a>, <a href="/web-llvm/docs/api/structs/llvm/graphtraits-f49901f175172e7cfbe6b56041ffd8d7/#a5ab8888f20c15345384d628542f79763">llvm::GraphTraits&lt; const Loop * &gt;::child_end</a>, <a href="/web-llvm/docs/api/structs/llvm/graphtraits-5d21b8f453fe72c9ef888c2858a7ce72/#ab71a68fe652279719768af0cc4465fcd">llvm::GraphTraits&lt; const MachineBasicBlock * &gt;::child_end</a>, <a href="/web-llvm/docs/api/structs/llvm/graphtraits-c3a45f7f0dd450384d0784bafc98dec0/#aeb2f02d57ad2cf8b547351a6b8fac495">llvm::GraphTraits&lt; const MachineLoop * &gt;::child_end</a>, <a href="/web-llvm/docs/api/structs/llvm/graphtraits-34ad45e92d8eecd133e6e79591f93716/#aacf630005242b99b208d399930993bb2">llvm::GraphTraits&lt; const VPBlockBase * &gt;::child_end</a>, <a href="/web-llvm/docs/api/structs/llvm/graphtraits-60fe2955c1f6971c9465484c526709fc/#a3f745f2b127d7340a005b74ef7758a46">llvm::GraphTraits&lt; DDGNode * &gt;::child_end</a>, <a href="/web-llvm/docs/api/structs/llvm/graphtraits-5e1f4c1478a77e56af95f6a94081e313/#a8eac96784271d5e005e3e52969f6e487">llvm::GraphTraits&lt; DotCfgDiffDisplayGraph * &gt;::child_end</a>, <a href="/web-llvm/docs/api/structs/llvm/graphtraits-973e7b08b5b5818a1d5c6c69da1fa05b/#a8d260368b043ac2dc415b03dc2c818f6">llvm::GraphTraits&lt; Inverse&lt; BasicBlock * &gt; &gt;::child_end</a>, <a href="/web-llvm/docs/api/structs/llvm/graphtraits-d27a12f208359493deb55564e5902b74/#a1d6d5c299666a449312c039640f55604">llvm::GraphTraits&lt; Inverse&lt; const BasicBlock * &gt; &gt;::child_end</a>, <a href="/web-llvm/docs/api/structs/llvm/graphtraits-8dab79ad0cf15ea502cd9eb4bb116b20/#a16c5ca7f61e3102bc5439e82776be024">llvm::GraphTraits&lt; Inverse&lt; const MachineBasicBlock * &gt; &gt;::child_end</a>, <a href="/web-llvm/docs/api/structs/llvm/graphtraits-343d0630a0e99b15bc453d3b888245d8/#a14320796c64b7bdf3ac474b7410952e9">llvm::GraphTraits&lt; Inverse&lt; MachineBasicBlock * &gt; &gt;::child_end</a>, <a href="/web-llvm/docs/api/structs/llvm/graphtraits-4eb58d9bcb360b0c1dcb042151ab7b36/#ad87c5dc70ecea2183dfaf2d23f54a953">llvm::GraphTraits&lt; Inverse&lt; MemoryAccess * &gt; &gt;::child_end</a>, <a href="/web-llvm/docs/api/structs/llvm/graphtraits-6777a894e2bc907768e146187125b22e/#ab88a8eadc16cffb44b2ae12321c90204">llvm::GraphTraits&lt; Inverse&lt; VPBlockBase * &gt; &gt;::child_end</a>, <a href="/web-llvm/docs/api/structs/llvm/graphtraits-a12c42fe191dcee87ec2a59ab1fee5fd/#a67447e0967f5758a26746ce1b653c967">llvm::GraphTraits&lt; IrreducibleGraph &gt;::child_end</a>, <a href="/web-llvm/docs/api/structs/llvm/graphtraits-a2008b5f8b21ce1ff8289baaf7093f8a/#a6be1efc99c4348623dd0c2aad997af37">llvm::GraphTraits&lt; LazyCallGraph * &gt;::child_end</a>, <a href="/web-llvm/docs/api/structs/llvm/graphtraits-0ea52d7b93b4cfe134cbdc75e8ba07b0/#a14dd61fc3aaa80af0dba2fab733fed68">llvm::GraphTraits&lt; LazyCallGraph::Node * &gt;::child_end</a>, <a href="/web-llvm/docs/api/structs/llvm/graphtraits-fcd0a659899357154ff141dcb39152d5/#a779bea7d0378a9f9d4d74671b3bf0acf">llvm::GraphTraits&lt; Loop * &gt;::child_end</a>, <a href="/web-llvm/docs/api/structs/llvm/graphtraits-b9c75e93407b82228c2e4202f39262f5/#acd5fcb79721311a1f0223584cd3e2d6d">llvm::GraphTraits&lt; MachineBasicBlock * &gt;::child_end</a>, <a href="/web-llvm/docs/api/structs/llvm/graphtraits-98588480f432ad6b5e85a9f166846cbf/#a41410fd62368663ef6e2d40b19f3762b">llvm::GraphTraits&lt; MachineBlockFrequencyInfo * &gt;::child_end</a>, <a href="/web-llvm/docs/api/structs/llvm/graphtraits-cd2f029841e7ddfea4b3dd7735cfc064/#aa83966096a9fc8ef9379976f852aa206">llvm::GraphTraits&lt; MachineLoop * &gt;::child_end</a>, <a href="/web-llvm/docs/api/structs/llvm/graphtraits-0dc1828882f98769279a0fe7f513a40d/#a76c15dd4625df32e24d30e6998703326">llvm::GraphTraits&lt; MemoryAccess * &gt;::child_end</a>, <a href="/web-llvm/docs/api/structs/llvm/graphtraits-0546ad5ef67fa8ce6d07eef123a5b8c9/#a118bfffc5d39b2c022855b2dc48b598d">llvm::GraphTraits&lt; PGOUseFunc * &gt;::child_end</a>, <a href="/web-llvm/docs/api/structs/llvm/graphtraits-3415cdfe2a550135494395498d7d0793/#a7ebe73ad4245eca8c49b3d2eb741ebc4">llvm::GraphTraits&lt; ProfiledCallGraphNode * &gt;::child_end</a>, <a href="/web-llvm/docs/api/structs/llvm/graphtraits-1eef46228acd7bc9828d384fc7349578/#a1f9cb0685800b508261501ca6019f772">llvm::GraphTraits&lt; RematGraph * &gt;::child_end</a>, <a href="/web-llvm/docs/api/structs/llvm/graphtraits-404b5b8ef0c47cc568060468de8cfca6/#a33dfada6e09d4cc7a536c11cc4b4c2db">llvm::GraphTraits&lt; SDNode * &gt;::child_end</a>, <a href="/web-llvm/docs/api/structs/llvm/graphtraits-8cbcf8b9166a6c46f5d7e91ca6470b24/#ae43e896e89edc202bd794ad3e94d0503">llvm::GraphTraits&lt; SUnit * &gt;::child_end</a>, <a href="/web-llvm/docs/api/structs/llvm/graphtraits-54af6749b69c1b355796c199a231acf9/#ae51a23343f5b03579c6f891232cd3f29">llvm::GraphTraits&lt; ValueInfo &gt;::child_end</a>, <a href="/web-llvm/docs/api/structs/llvm/graphtraits-ac66d4b8671a287a0a0e312ee17ee28d/#adadc7e1a031c159939798f47864a0737">llvm::GraphTraits&lt; VPBlockBase * &gt;::child_end</a>, <a href="/web-llvm/docs/api/structs/llvm/graphtraits-d394e565666085640be20f1e64fdd72b/#a8d321be6a1d3cab2bde236251e3a45cd">llvm::GraphTraits&lt; VPBlockDeepTraversalWrapper&lt; const VPBlockBase * &gt; &gt;::child_end</a>, <a href="/web-llvm/docs/api/structs/llvm/graphtraits-9ac678cba1b93dbde91361363a8c8a8e/#a674a487e693cc9d8974189f99e1791b3">llvm::GraphTraits&lt; VPBlockDeepTraversalWrapper&lt; VPBlockBase * &gt; &gt;::child_end</a>, <a href="/web-llvm/docs/api/structs/llvm/graphtraits-363fa89642305612e9e0e66792192abb/#a2a5e31c59a98d40c3bdae69b61f93cf0">llvm::GraphTraits&lt; VPBlockShallowTraversalWrapper&lt; const VPBlockBase * &gt; &gt;::child_end</a>, <a href="/web-llvm/docs/api/structs/llvm/graphtraits-0bf1ef93d28481823f2981c5bb514c9c/#a4d4293316d8186cd3e702f717345a024">llvm::GraphTraits&lt; VPBlockShallowTraversalWrapper&lt; VPBlockBase * &gt; &gt;::child_end</a>, <a href="/web-llvm/docs/api/structs/llvm/machinedomtreegraphtraitsbase/#a1b0bfca7c7f664c34bffedd2ccc45052">llvm::MachineDomTreeGraphTraitsBase&lt; Node, ChildIterator &gt;::child_end</a>, <a href="/web-llvm/docs/api/structs/anonymous-structurizecfg-cpp-/subgraphtraits/#ab79fd37f041d978a7007cbd751eb9665">anonymous{StructurizeCFG.cpp}::SubGraphTraits::children</a>, <a href="/web-llvm/docs/api/structs/anonymous-xcoffobjectwriter-cpp-/cinfosymsectionentry/#ae0d3f85342813ea8fa3b77f57f63477b">anonymous{XCOFFObjectWriter.cpp}::CInfoSymSectionEntry::CInfoSymSectionEntry</a>, <a href="/web-llvm/docs/api/classes/anonymous-deltatree-cpp-/deltatreeinteriornode/#a749735f86ee752ef7a27de0196c434ae">anonymous{DeltaTree.cpp}::DeltaTreeInteriorNode::classof</a>, <a href="/web-llvm/docs/api/classes/anonymous-rewriterope-cpp-/ropepiecebtreeinterior/#a499900d391955de65b1453c41b8e81c2">anonymous{RewriteRope.cpp}::RopePieceBTreeInterior::classof</a>, <a href="/web-llvm/docs/api/classes/anonymous-rewriterope-cpp-/ropepiecebtreeleaf/#a32f112cc839a156174e9aece8b339e68">anonymous{RewriteRope.cpp}::RopePieceBTreeLeaf::classof</a>, <a href="/web-llvm/docs/api/classes/llvm/addrspacecastsdnode/#ab417937f7065fb8f2fd6509a2279a3f7">llvm::AddrSpaceCastSDNode::classof</a>, <a href="/web-llvm/docs/api/classes/llvm/assertalignsdnode/#ad5625bdeff1e616c6921272ee0428d66">llvm::AssertAlignSDNode::classof</a>, <a href="/web-llvm/docs/api/classes/llvm/atomicsdnode/#a711691a8c7793f6e5737daeaa2a8815a">llvm::AtomicSDNode::classof</a>, <a href="/web-llvm/docs/api/classes/llvm/basicblocksdnode/#ad2c1d1d7e25eacb722ed594cbde6fd25">llvm::BasicBlockSDNode::classof</a>, <a href="/web-llvm/docs/api/classes/llvm/blockaddresssdnode/#a7e1a594943e424bdf5808be7065c4901">llvm::BlockAddressSDNode::classof</a>, <a href="/web-llvm/docs/api/classes/llvm/buildvectorsdnode/#ad44d0f0f1fddc11c4cf8b7566fdd33fd">llvm::BuildVectorSDNode::classof</a>, <a href="/web-llvm/docs/api/classes/llvm/condcodesdnode/#aa023aa408a7fb45b90f2a834b6cc6d03">llvm::CondCodeSDNode::classof</a>, <a href="/web-llvm/docs/api/classes/llvm/constantfpsdnode/#ac850cec521b9efe4f9ba07140dc27aa7">llvm::ConstantFPSDNode::classof</a>, <a href="/web-llvm/docs/api/classes/llvm/constantpoolsdnode/#a3bb40b90b6a488d35fc9989d17997ad3">llvm::ConstantPoolSDNode::classof</a>, <a href="/web-llvm/docs/api/classes/llvm/constantsdnode/#a8a38bf53cfdddb11ff0013d1cd03d7a0">llvm::ConstantSDNode::classof</a>, <a href="/web-llvm/docs/api/classes/llvm/dbgentity/#a788eb62d7ac86929d640d17dcdf98f9f">llvm::DbgEntity::classof</a>, <a href="/web-llvm/docs/api/classes/llvm/dbglabel/#a809c4308063b991a67ca3ab433a99b2c">llvm::DbgLabel::classof</a>, <a href="/web-llvm/docs/api/classes/llvm/dbgvariable/#aac479bcdf110bdc37a781338cb1e206b">llvm::DbgVariable::classof</a>, <a href="/web-llvm/docs/api/classes/llvm/externalsymbolsdnode/#aa2dff47aa3ff2713b537f82f5facf032">llvm::ExternalSymbolSDNode::classof</a>, <a href="/web-llvm/docs/api/classes/llvm/fpstateaccesssdnode/#a924a304883bf49f015d39424877a3d63">llvm::FPStateAccessSDNode::classof</a>, <a href="/web-llvm/docs/api/classes/llvm/frameindexsdnode/#a2595b3f94e347d81a2f1340a70e94476">llvm::FrameIndexSDNode::classof</a>, <a href="/web-llvm/docs/api/classes/llvm/globaladdresssdnode/#aaa61d0186a5eb8eb0bbcc5d1dd84faf5">llvm::GlobalAddressSDNode::classof</a>, <a href="/web-llvm/docs/api/classes/llvm/jumptablesdnode/#a50f6f04e01fd573979edd2b80f963157">llvm::JumpTableSDNode::classof</a>, <a href="/web-llvm/docs/api/classes/llvm/labelsdnode/#aee4e77e817660e229aef189c7744345e">llvm::LabelSDNode::classof</a>, <a href="/web-llvm/docs/api/classes/llvm/lifetimesdnode/#a378685595d8e8e30c7a229380f891413">llvm::LifetimeSDNode::classof</a>, <a href="/web-llvm/docs/api/classes/llvm/loadsdnode/#ae15fae32303e714d9009b970bf02a46d">llvm::LoadSDNode::classof</a>, <a href="/web-llvm/docs/api/classes/llvm/lsbasesdnode/#ac9baa7ecd81706188d103d90568de292">llvm::LSBaseSDNode::classof</a>, <a href="/web-llvm/docs/api/classes/llvm/machinesdnode/#a82bc51b7e0e7b18ed0eeb4deb352d0d2">llvm::MachineSDNode::classof</a>, <a href="/web-llvm/docs/api/classes/llvm/maskedgatherscattersdnode/#a59c019b73774ab8fb05f462713e531ab">llvm::MaskedGatherScatterSDNode::classof</a>, <a href="/web-llvm/docs/api/classes/llvm/maskedgathersdnode/#a2b2f567db188457b6ee4aa1d718e12ea">llvm::MaskedGatherSDNode::classof</a>, <a href="/web-llvm/docs/api/classes/llvm/maskedhistogramsdnode/#a662d621555ea6ac0b05d3e01646424e4">llvm::MaskedHistogramSDNode::classof</a>, <a href="/web-llvm/docs/api/classes/llvm/maskedloadsdnode/#a7ba665362da7a8210f8087e2ba62adda">llvm::MaskedLoadSDNode::classof</a>, <a href="/web-llvm/docs/api/classes/llvm/maskedloadstoresdnode/#aae38148981c9f79e75dda9f972b62384">llvm::MaskedLoadStoreSDNode::classof</a>, <a href="/web-llvm/docs/api/classes/llvm/maskedscattersdnode/#a39c0a507a2a4f696c34154c9e8adc00c">llvm::MaskedScatterSDNode::classof</a>, <a href="/web-llvm/docs/api/classes/llvm/maskedstoresdnode/#ad5d77ad6938ac0ae867e57cf0f558f6b">llvm::MaskedStoreSDNode::classof</a>, <a href="/web-llvm/docs/api/classes/llvm/mcsymbolsdnode/#ad372994148634ada144d3e6f5141da00">llvm::MCSymbolSDNode::classof</a>, <a href="/web-llvm/docs/api/classes/llvm/mdnodesdnode/#a07e30c80d76b5be01f224385c1cecacc">llvm::MDNodeSDNode::classof</a>, <a href="/web-llvm/docs/api/classes/llvm/memintrinsicsdnode/#a8bd9539a37f09dee380cd4cefbe9fd06">llvm::MemIntrinsicSDNode::classof</a>, <a href="/web-llvm/docs/api/classes/llvm/memsdnode/#ad55691554da9be384e9393e8b42a431a">llvm::MemSDNode::classof</a>, <a href="/web-llvm/docs/api/classes/llvm/piblockddgnode/#ab150d005f95305f5a7a9b8e4dafba5c1">llvm::PiBlockDDGNode::classof</a>, <a href="/web-llvm/docs/api/classes/llvm/pseudoprobesdnode/#a2232b705cb5b1647c8f02882ded6c240">llvm::PseudoProbeSDNode::classof</a>, <a href="/web-llvm/docs/api/classes/llvm/registermasksdnode/#adb0df75116db86aa5f41990e9961c4fc">llvm::RegisterMaskSDNode::classof</a>, <a href="/web-llvm/docs/api/classes/llvm/registersdnode/#a2b7677e3fe371ebe62c2aed17862f5c6">llvm::RegisterSDNode::classof</a>, <a href="/web-llvm/docs/api/classes/llvm/rootddgnode/#a57ed505e0c156e8381481d8b87354a14">llvm::RootDDGNode::classof</a>, <a href="/web-llvm/docs/api/classes/llvm/rootddgnode/#ac6ed9f2c3ea9afe1160aabbc6c2ff692">llvm::RootDDGNode::classof</a>, <a href="/web-llvm/docs/api/classes/llvm/shufflevectorsdnode/#ae7c77fc01f65af9d9ce0e35a266a2da5">llvm::ShuffleVectorSDNode::classof</a>, <a href="/web-llvm/docs/api/classes/llvm/simpleddgnode/#a4e7421b58370c9e1d947644fff1c54c2">llvm::SimpleDDGNode::classof</a>, <a href="/web-llvm/docs/api/classes/llvm/simpleddgnode/#a6b5faa13321479d114b145f7eba15420">llvm::SimpleDDGNode::classof</a>, <a href="/web-llvm/docs/api/classes/llvm/srcvaluesdnode/#a32b59c9133361163a2d1c4203d9bdf32">llvm::SrcValueSDNode::classof</a>, <a href="/web-llvm/docs/api/classes/llvm/storesdnode/#af13416343f5811f7842dec95b17c1a14">llvm::StoreSDNode::classof</a>, <a href="/web-llvm/docs/api/structs/llvm/suffixtreeinternalnode/#a945ed42e87aca83910a3f79960d00eb7">llvm::SuffixTreeInternalNode::classof</a>, <a href="/web-llvm/docs/api/structs/llvm/suffixtreeleafnode/#aad2e2f2432231920dd40153553db08fd">llvm::SuffixTreeLeafNode::classof</a>, <a href="/web-llvm/docs/api/classes/llvm/targetindexsdnode/#acc1bf32d5c273c2477089b2b7df3a24e">llvm::TargetIndexSDNode::classof</a>, <a href="/web-llvm/docs/api/classes/llvm/vfs/detail/anonymous-virtualfilesystem-cpp-/inmemoryhardlink/#aad125d3741d419bd479000e56998653c">llvm::vfs::detail::anonymous{VirtualFileSystem.cpp}::InMemoryHardLink::classof</a>, <a href="/web-llvm/docs/api/classes/llvm/vfs/detail/anonymous-virtualfilesystem-cpp-/inmemorysymboliclink/#a50f473dcc7e5def476076fe7fe5fb688">llvm::vfs::detail::anonymous{VirtualFileSystem.cpp}::InMemorySymbolicLink::classof</a>, <a href="/web-llvm/docs/api/classes/llvm/vfs/detail/inmemorydirectory/#a7437c0371863a9e1dc57c1ae51de51c4">llvm::vfs::detail::InMemoryDirectory::classof</a>, <a href="/web-llvm/docs/api/classes/llvm/vfs/detail/inmemoryfile/#aa8d36f36b3b68d5a51117802c5930169">llvm::vfs::detail::InMemoryFile::classof</a>, <a href="/web-llvm/docs/api/classes/llvm/vpbaseloadstoresdnode/#a5465b3431f43428d883682a455f2ada5">llvm::VPBaseLoadStoreSDNode::classof</a>, <a href="/web-llvm/docs/api/classes/llvm/vpgatherscattersdnode/#aedbd4efa9015a656563c4eeebf8efe4d">llvm::VPGatherScatterSDNode::classof</a>, <a href="/web-llvm/docs/api/classes/llvm/vpgathersdnode/#a83c4d0c5df57ccbcd6aa76b140e3d532">llvm::VPGatherSDNode::classof</a>, <a href="/web-llvm/docs/api/classes/llvm/vploadsdnode/#ad85cc977ad62aac937d06e919f00bbf8">llvm::VPLoadSDNode::classof</a>, <a href="/web-llvm/docs/api/classes/llvm/vpscattersdnode/#abb2f99909f1baf7d482d90a61bb99edc">llvm::VPScatterSDNode::classof</a>, <a href="/web-llvm/docs/api/classes/llvm/vpstoresdnode/#a4636d37ace103b08f36bba9f149f610d">llvm::VPStoreSDNode::classof</a>, <a href="/web-llvm/docs/api/classes/llvm/vpstridedloadsdnode/#ac4cc966f98ec01b567159e00bd24bcf4">llvm::VPStridedLoadSDNode::classof</a>, <a href="/web-llvm/docs/api/classes/llvm/vpstridedstoresdnode/#ad177f1b08449694744aefd1f1afcd081">llvm::VPStridedStoreSDNode::classof</a>, <a href="/web-llvm/docs/api/classes/llvm/vtsdnode/#ae82a2be488a727c9f52c2122ba47159f">llvm::VTSDNode::classof</a>, <a href="/web-llvm/docs/api/classes/llvm/x86maskedgatherscattersdnode/#a7daf9f3812c996181c43010a320e7977">llvm::X86MaskedGatherScatterSDNode::classof</a>, <a href="/web-llvm/docs/api/classes/llvm/x86maskedgathersdnode/#ad73daeec770128341744f249be5a7a39">llvm::X86MaskedGatherSDNode::classof</a>, <a href="/web-llvm/docs/api/classes/llvm/x86maskedscattersdnode/#a60f149c0e80fffba2e513f12a6184150">llvm::X86MaskedScatterSDNode::classof</a>, <a href="/web-llvm/docs/api/classes/llvm/yaml/aliasnode/#a5b055094faab8675a84ded1d0d849210">llvm::yaml::AliasNode::classof</a>, <a href="/web-llvm/docs/api/classes/llvm/yaml/blockscalarnode/#a0fe29b12ada09490790221d7f10e3cb9">llvm::yaml::BlockScalarNode::classof</a>, <a href="/web-llvm/docs/api/classes/llvm/yaml/keyvaluenode/#a9d6da181da9601218ececfbdd4361d49">llvm::yaml::KeyValueNode::classof</a>, <a href="/web-llvm/docs/api/classes/llvm/yaml/mappingnode/#a6a785765ed95dacd5f3a407b6c929de6">llvm::yaml::MappingNode::classof</a>, <a href="/web-llvm/docs/api/classes/llvm/yaml/nullnode/#ae80aaff6db8dccc59337adc2a7047bb3">llvm::yaml::NullNode::classof</a>, <a href="/web-llvm/docs/api/classes/llvm/yaml/scalarnode/#a6d236b13f37ba588208cb56039c1ed36">llvm::yaml::ScalarNode::classof</a>, <a href="/web-llvm/docs/api/classes/llvm/yaml/sequencenode/#a204c5bcb113d98ac54c0b5e721149911">llvm::yaml::SequenceNode::classof</a>, <a href="/web-llvm/docs/api/files/lib/lib/ir/printpasses-cpp/#aea57e0fed9b4f4177386bf11ebb66299">cleanUpTempFilesImpl</a>, <a href="/web-llvm/docs/api/structs/llvm/rdf/dataflowgraph/defstack/#a2304009ed0708ae40c76614597c8ce08">llvm::rdf::DataFlowGraph::DefStack::clear_block</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#ab371d6b308eb9772bdec63cf7a041407">llvm::CloneModule</a>, <a href="/web-llvm/docs/api/files/lib/lib/codegen/lib/codegen/selectiondag/scheduledagsdnodes-cpp/#afc8468deb9527c231335fb0bc9ea1109">CloneNodeWithValues</a>, <a href="/web-llvm/docs/api/classes/llvm/sandboxir/schedbundle/#af592edb1be21d93d852c97cb1db2dea5">llvm::sandboxir::SchedBundle::cluster</a>, <a href="/web-llvm/docs/api/structs/llvm/rdf/deadcodeelimination/#a4c7ab56ddc8e8b9a4f7903e9268c10e9">llvm::rdf::DeadCodeElimination::collect</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a544a0723e20148ceb9a3bb3210f45270">llvm::collectChildrenInLoop</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/x86/x86isellowering-cpp/#a9e8360ec6c03540a7ad4753613cfc66f">collectConcatOps</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64isellowering-cpp/#a8f8e13b821b9ba9b453c82ac0a356b82">combineAcrossLanesIntrinsic</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/x86/x86isellowering-cpp/#a2ef9bba3be5001d1d80c474dd335dff7">combineADC</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/x86/x86isellowering-cpp/#a4585b76cee25b89a8706715217a1c743">combineAdd</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/riscv/riscvisellowering-cpp/#aaab5068203f7eda4cf8a53182aae5cdd">combineAddOfBooleanXor</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/x86/x86isellowering-cpp/#a06ffb5dfa0c98a5796c4eca6684aded6">combineAddOrSubToADCOrSBB</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/powerpc/ppcisellowering-cpp/#a1cb8184c9c7806da491d6facc22a7fba">combineADDToADDZE</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/powerpc/ppcisellowering-cpp/#a2fc82b70727afff2c18b36c0a6c280cd">combineADDToMAT_PCREL_ADDR</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/m68k/m68kisellowering-cpp/#a15a58cff8c68e29d244fa674a612519c">combineADDX</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/x86/x86isellowering-cpp/#a61e686ca7b81dbf342b3af2d4e23149e">combineAnd</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/x86/x86isellowering-cpp/#aaa27af54b7ba8fa7ee30cc6d7f729207">combineAndMaskToShift</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/x86/x86isellowering-cpp/#afa581f136104dab3ed3a4c0ad153a67c">combineAndNotIntoANDNP</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/x86/x86isellowering-cpp/#aaef2e5e31eb4626f87592c24deeecfa3">combineAndNotOrIntoAndNotAnd</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/x86/x86isellowering-cpp/#a0285b9eb9c4a75abb42c7cf0ef0154f1">combineAndnp</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/x86/x86isellowering-cpp/#add97272311c92ae6e05533bf8718447f">combineAndOrForCcmpCtest</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/arm/armisellowering-cpp/#ad1b9f6a1979dddff5b170976bfd53c52">CombineANDShift</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/x86/x86isellowering-cpp/#a4149392e82922475c1b566db35e3c8b8">combineAndShuffleNot</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/x86/x86isellowering-cpp/#af59e4da255e65a90b6c4710be399b9e6">combineAVG</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/arm/armisellowering-cpp/#aa4c17cc7964441daaea8b4bee6c18f93">CombineBaseUpdate</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/x86/x86isellowering-cpp/#af0e0d5fc4a01d9f412064a5448052330">combineBEXTR</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/riscv/riscvisellowering-cpp/#aedc985b3a3cebc7be1d14b89265c3bce">combineBinOpOfExtractToReduceTree</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/riscv/riscvisellowering-cpp/#a9bdfd68546796977511fb45113e98deb">combineBinOpOfZExt</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/riscv/riscvisellowering-cpp/#abaf220e37dfcbfd9339df9b9ac2dff42">combineBinOpToReduce</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/x86/x86isellowering-cpp/#a1bca5f0c0254fc2b2707fe8b6e5677d3">combineBitcast</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/x86/x86isellowering-cpp/#acb27133587f777e5b89572d1c62aeac9">combineBITREVERSE</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/x86/x86isellowering-cpp/#a1d33df2c00851a783858052d263c2546">combineBMILogicOp</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/x86/x86isellowering-cpp/#afd512b724e2c19c51591ff52531f8659">combineBrCond</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/x86/x86isellowering-cpp/#aba1b64f17c84bc615a735f48746a0740">combineBROADCAST_LOAD</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/x86/x86isellowering-cpp/#afab7e380356e4b22d23f87fa2f45daf9">combineBT</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/powerpc/ppcisellowering-cpp/#af8092b588e16c93a54d21da99af4814c">combineBVOfConsecutiveLoads</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/powerpc/ppcisellowering-cpp/#af31a972f3279158ab9801b78f1f92e1f">combineBVOfVecSExt</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/powerpc/ppcisellowering-cpp/#ad6651de6f4b40c5d58ecbf97fad85374">combineBVZEXTLOAD</a>, <a href="/web-llvm/docs/api/files/lib/lib/codegen/lib/codegen/selectiondag/dagcombiner-cpp/#a3fe8c06097a055b8ab0114f2678ed2d6">combineCarryDiamond</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/x86/x86isellowering-cpp/#a1bd495ab23d43ebbe7e2d167103d8991">combineCastedMaskArithmetic</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/x86/x86isellowering-cpp/#af0fb4a30e359345f1f6c967488cd37ab">combineCMov</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/x86/x86isellowering-cpp/#aba289468402d03624610fd1f5fb042d0">combineCMP</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/x86/x86isellowering-cpp/#a454834aa3770b553c5365fa2460a7687">combineCommutableSHUFP</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/x86/x86isellowering-cpp/#a672f8f5fb89a9c2758df02f8e2d1e263">combineCompareEqual</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/x86/x86isellowering-cpp/#ae2e4d6043b5ce023daf9d1d905eb2110">combineCONCAT_VECTORS</a>, <a href="/web-llvm/docs/api/files/lib/lib/codegen/lib/codegen/selectiondag/dagcombiner-cpp/#ad45a536ce828d7fe0a889a1666437654">combineConcatVectorOfCasts</a>, <a href="/web-llvm/docs/api/files/lib/lib/codegen/lib/codegen/selectiondag/dagcombiner-cpp/#ae212b33ea9fc9947ff01a147fd5e8606">combineConcatVectorOfConcatVectors</a>, <a href="/web-llvm/docs/api/files/lib/lib/codegen/lib/codegen/selectiondag/dagcombiner-cpp/#a670c95cba653503ce21f4abeea37cd2f">combineConcatVectorOfExtracts</a>, <a href="/web-llvm/docs/api/files/lib/lib/codegen/lib/codegen/selectiondag/dagcombiner-cpp/#ade36263ef53851ce871d715dbbc10066">combineConcatVectorOfScalars</a>, <a href="/web-llvm/docs/api/files/lib/lib/codegen/lib/codegen/selectiondag/dagcombiner-cpp/#aa9000b7e9cff2ce4bcb6b5ae17761a3a">combineConcatVectorOfShuffleAndItsOperands</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/x86/x86isellowering-cpp/#ac20988096ab221d67983ac1c48ad4ebb">combineConstantPoolLoads</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/x86/x86isellowering-cpp/#a69c29dade9c2c83e9928f92e0e6452f0">combineCVTP2I_CVTTP2I</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/x86/x86isellowering-cpp/#a4a24cdc31f225e6b17b30c139085b064">combineCVTPH2PS</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/riscv/riscvisellowering-cpp/#a5a87447416046730b266c20001561df4">combineDeMorganOfBoolean</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/x86/x86isellowering-cpp/#acfa813720f554bb68a6e8c5fdb870f4e">combineEXTEND_VECTOR_INREG</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/x86/x86isellowering-cpp/#a7930c9d63dfbaa761bf5c317865e8a43">combineEXTRACT_SUBVECTOR</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/x86/x86isellowering-cpp/#aa9fca969da56000134dc248f8d676e3a">combineExtractFromVectorLoad</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/x86/x86isellowering-cpp/#a767fefc1593899bc23f0b03007b0bd76">combineExtractVectorElt</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/x86/x86isellowering-cpp/#a03737b8120e2ceffc57089d0510107c0">combineExtractWithShuffle</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/x86/x86isellowering-cpp/#ad2800cb88996291ed1676f5899997ebe">combineExtSetcc</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/x86/x86isellowering-cpp/#ae222abd7ba47c29a86fc6be7f3dd02fb">combineFaddCFmul</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/x86/x86isellowering-cpp/#ae7dca9dde4468bf201a9020ffb66e8b7">combineFaddFsub</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/x86/x86isellowering-cpp/#ae1ff7bc42bf5767e31a54339e89ce713">combineFAnd</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/x86/x86isellowering-cpp/#a24d54706296d70148335f0f4ff621028">combineFAndFNotToFAndn</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/x86/x86isellowering-cpp/#a6fea2dc458fb3a17821239b8383d26ad">combineFAndn</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/x86/x86isellowering-cpp/#a8dae5a29dc37de048a59e5bab5e30af2">combineFMA</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/x86/x86isellowering-cpp/#af0f13d1cf96cb32fba6d7ed4bd50ba5f">combineFMADDSUB</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/x86/x86isellowering-cpp/#a81efb38c390b38633dbdb3e877a15a84">combineFMinFMax</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/x86/x86isellowering-cpp/#aba1e500fbed9b5849bfd76724ccf3825">combineFMinNumFMaxNum</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/x86/x86isellowering-cpp/#a63a699ff4d2df76812431793394bf85a">combineFMulcFCMulc</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/x86/x86isellowering-cpp/#a7a388b8e71542c8223c73a0d99691c71">combineFneg</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/x86/x86isellowering-cpp/#a7e81e46aed86f26e5183c666e5dd1b06">combineFOr</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/x86/x86isellowering-cpp/#a1d28003b370fb2c0860ad25f3ef57c5f">combineFP16_TO_FP</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/x86/x86isellowering-cpp/#a2b9e3b2b4b0c1d77472815e6d770a4fb">combineFP_EXTEND</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/x86/x86isellowering-cpp/#a4106aa1194d1a3ddfe03bbbc600913cf">combineFP_ROUND</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/x86/x86isellowering-cpp/#aaa9fb1f6b90b41c70933803cefa8661a">combineFP_TO_xINT_SAT</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/x86/x86isellowering-cpp/#a250b1e0899d6d01c60cb7af31cd2a2fd">combineGatherScatter</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/x86/x86isellowering-cpp/#af366ca9511826f13c9d2e4494be70cd9">combineHorizOpWithShuffle</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/x86/x86isellowering-cpp/#ace3516d005e59a05c7b3ff975d063f23">combineINSERT_SUBVECTOR</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/x86/x86isellowering-cpp/#a7ed3d44a545e6f543e76cf58245d1f19">combineINTRINSIC_VOID</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/x86/x86isellowering-cpp/#ac13cf93d084e804ad88b2b1dbef0c618">combineINTRINSIC_W_CHAIN</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/x86/x86isellowering-cpp/#a84473a3a9dca82077491c2b25bc82837">combineINTRINSIC_WO_CHAIN</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/x86/x86isellowering-cpp/#a886d3292e22e113b2f04c1c35811bd0c">combineKSHIFT</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/x86/x86isellowering-cpp/#a7ae2bbddcc95cdf14669ea9eb8a2026e">combineLoad</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/x86/x86isellowering-cpp/#ada799c570dd41ead38f73ba71244c2b2">combineLogicBlendIntoConditionalNegate</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/x86/x86isellowering-cpp/#a04f34c6d2aa331eb6fe9c1f1e52f2f9d">combineLogicBlendIntoPBLENDV</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/x86/x86isellowering-cpp/#ab723e84f5e5bacce2d3e9a9bacf2c707">combineLRINT_LLRINT</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/m68k/m68kisellowering-cpp/#a4e69fe6435da5591de2b037c0e06ed95">combineM68kBrCond</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/m68k/m68kisellowering-cpp/#a6d0657564be2faf3fb451f237be1c818">combineM68kSetCC</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/x86/x86isellowering-cpp/#a4a6a2af7640ee8f9e66287e024d0f6b8">combineMaskedLoad</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/x86/x86isellowering-cpp/#a44f727169247a0359f485216a83265ac">combineMaskedStore</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/x86/x86isellowering-cpp/#a4d6ae8095a6353874359d5f5e886410c">combineMOVDQ2Q</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/x86/x86isellowering-cpp/#ab6a2c45af55afc1bf183cbafc577fd03">combineMOVMSK</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/x86/x86isellowering-cpp/#adc36484c228b0ce9652f549d04ae4e6e">combineMul</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/x86/x86isellowering-cpp/#ac5d1a07dd050cf248b97dd2600317e75">combineMulSpecial</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/x86/x86isellowering-cpp/#a25809cd7dd1487d02672b4b834bf2ee2">combineMulToPMADDWD</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/x86/x86isellowering-cpp/#aaef2336d9f0305e57b22c5be16c73caa">combineMulToPMULDQ</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/riscv/riscvisellowering-cpp/#a3ff4156c9862c64e6d354f5413c3da5e">combineOp_VLToVWOp_VL</a>, <a href="/web-llvm/docs/api/structs/anonymous-dataflowsanitizer-cpp-/dfsanfunction/#ad7d79bd0b027705195d79619a1d0450a">anonymous{DataFlowSanitizer.cpp}::DFSanFunction::combineOperandShadows</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/x86/x86isellowering-cpp/#a81ff8e0a240cf80ff42fcb1a6c796b33">combineOr</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/x86/x86isellowering-cpp/#a027102ec674270eecc2a1a6ec8588e44">combineOrCmpEqZeroToCtlzSrl</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/riscv/riscvisellowering-cpp/#a42b1445a28e47f29d193a59eccb0e19c">combineOrOfCZERO</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/x86/x86isellowering-cpp/#ad27c58fe609558af3d02f6eb59c0d075">combinePDEP</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/x86/x86isellowering-cpp/#a92cb7f91737deedc3c70fb0ec0b70807">combinePMULDQ</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/x86/x86isellowering-cpp/#a4bfc9dfb6bf7ab5af8b76e28d94162c2">combineRedundantDWordShuffle</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/x86/x86isellowering-cpp/#aa13d4cd47426dbe430d65df73fbab44b">combineSBB</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/x86/x86isellowering-cpp/#a2d9fefea85a815cc1227bbd3eee1fab3">combineSCALAR_TO_VECTOR</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/x86/x86isellowering-cpp/#aa701b28d5848c3250994e2e03a2dab97">combineScalarAndWithMaskSetcc</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/riscv/riscvisellowering-cpp/#a6d9136998f9ff100ad8449a69477ab94">combineScalarCTPOPToVCPOP</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/x86/x86isellowering-cpp/#a1f89a7382459e34a2d36ad281210e6c3">combineSelect</a>, <a href="/web-llvm/docs/api/classes/llvm/vetargetlowering/#a42586d078a0c852f7571d5d4fb0daa04">llvm::VETargetLowering::combineSelect</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/riscv/riscvisellowering-cpp/#ac1953eca2805574de12debdab3116430">combineSelectAndUse</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/lanai/lanaiisellowering-cpp/#a25b57e6a9269a29cbf98949ef2154842">combineSelectAndUse</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/arm/armisellowering-cpp/#ac23333bf0c5078b2f08c8e6e8509f0aa">combineSelectAndUse</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/arm/armisellowering-cpp/#a42665647b96c498ee34474d061608fb7">combineSelectAndUseCommutative</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/riscv/riscvisellowering-cpp/#aff09c08ab6404633d2ff44fa8185fc11">combineSelectAndUseCommutative</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/lanai/lanaiisellowering-cpp/#a7b7fd03bd2909ea37140e7a7c0467b7b">combineSelectAndUseCommutative</a>, <a href="/web-llvm/docs/api/classes/llvm/vetargetlowering/#a7094504ff72e8db0894faac2216aa00a">llvm::VETargetLowering::combineSelectCC</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/x86/x86isellowering-cpp/#a7e46711e88afd58c383ff1f504a173f5">combineSelectOfTwoConstants</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/riscv/riscvisellowering-cpp/#a72f1d6515236af504f465f5b35249e2b">combineSelectToBinOp</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/x86/x86isellowering-cpp/#a67003b5b5e4881cd871c87e65a58e3aa">combineSetCC</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/x86/x86isellowering-cpp/#ad7c52d56e60df127f4f9a429a5455590">combineSext</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/x86/x86isellowering-cpp/#a79a68c559c415f60c321106514817aa4">combineSextInRegCmov</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/x86/x86isellowering-cpp/#a7324b1333eec1b04ee358d58c42834ef">combineShiftLeft</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/x86/x86isellowering-cpp/#a925ab60e01665e8956b384fb79d7491c">combineShiftRightArithmetic</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/x86/x86isellowering-cpp/#a0b92776e41d73c3b5d4f1c5712f212c7">combineShiftRightLogical</a>, <a href="/web-llvm/docs/api/files/lib/lib/codegen/lib/codegen/selectiondag/dagcombiner-cpp/#ab5a426cb5c2105ca954c4ab9f12ef76f">combineShiftToMULH</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/x86/x86isellowering-cpp/#ab73df8541f091c30ed34fd2c89c57746">combineShiftToPMULH</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/x86/x86isellowering-cpp/#ae9b4450314b8e4acb9f937389b349fce">combineShuffle</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/x86/x86isellowering-cpp/#a364872c4ff0debf2cd93e9694b261b07">combineShuffleOfConcatUndef</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/x86/x86isellowering-cpp/#a6c8b4f7efd21d65ad87ca546e9696115">combineShuffleToAddSubOrFMAddSub</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/x86/x86isellowering-cpp/#aede614d152e5f383de8400fdbe75adf0">combineShuffleToFMAddSub</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/x86/x86isellowering-cpp/#a0cccf679aa7f34055f858474bf8bdcdf">combineSignExtendInReg</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/x86/x86isellowering-cpp/#aa2022f78361af7995aebd0a398e0a67e">combineSIntToFP</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/x86/x86isellowering-cpp/#af261a4d5db2bd80f9ef23aaf7a6caef7">combineStore</a>, <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/instcombine/instcombineloadstorealloca-cpp/#a00d35e1397cf2210fd30e1993c1eaab9">combineStoreToNewValue</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/x86/x86isellowering-cpp/#a0a830cdb7a7691a1d390be839ff5859f">combineSub</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/riscv/riscvisellowering-cpp/#ad0f859410a5e693f74b9c87a59cb9b85">combineSubOfBoolean</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/x86/x86isellowering-cpp/#a0bce091105ff422dbffc7677d698e455">combineSubSetcc</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/riscv/riscvisellowering-cpp/#a5efc2b9d3d3b40b85f5f7366bc145837">combineSubShiftToOrcB</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/m68k/m68kisellowering-cpp/#af412999bfa2d47d688955820572440ab">combineSUBX</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64isellowering-cpp/#a823e4af88c760486aecf7639ab3dc46e">combineSVEPrefetchVecBaseImmOff</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64isellowering-cpp/#a8762f1b4293f84b4f55ba7e2ee15924a">combineSVEReductionFP</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64isellowering-cpp/#ade199a6ca80a92917720916398f22963">combineSVEReductionInt</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64isellowering-cpp/#a769d7f599c512004a3f5d71e0ef7a8ed">combineSVEReductionOrderedFP</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/x86/x86isellowering-cpp/#a8af6dae0cb4e67d7004c888ed265f82a">combineTargetShuffle</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/x86/x86isellowering-cpp/#a619d32c3e94bf8ee0348f9611590dd90">combineTESTP</a>, <a href="/web-llvm/docs/api/classes/anonymous-dagcombiner-cpp-/dagcombiner/#a8018dafd83274830a0be46656f73d2f7">anonymous{DAGCombiner.cpp}::DAGCombiner::CombineTo</a>, <a href="/web-llvm/docs/api/classes/anonymous-dagcombiner-cpp-/dagcombiner/#ab61769601a4a8c94fdca4a4e1d205e11">anonymous{DAGCombiner.cpp}::DAGCombiner::CombineTo</a>, <a href="/web-llvm/docs/api/classes/anonymous-dagcombiner-cpp-/dagcombiner/#a88b0896fb4838342f46707f4d43c7b7e">anonymous{DAGCombiner.cpp}::DAGCombiner::CombineTo</a>, <a href="/web-llvm/docs/api/structs/llvm/targetlowering/dagcombinerinfo/#adff1fcbcf8e82995a72f1efd2d62ec11">llvm::TargetLowering::DAGCombinerInfo::CombineTo</a>, <a href="/web-llvm/docs/api/structs/llvm/targetlowering/dagcombinerinfo/#a7cf6bcad9fbd93aa99faf16377831feb">llvm::TargetLowering::DAGCombinerInfo::CombineTo</a>, <a href="/web-llvm/docs/api/structs/llvm/targetlowering/dagcombinerinfo/#a9ed65892d0b297e512746d6ef74debb7">llvm::TargetLowering::DAGCombinerInfo::CombineTo</a>, <a href="/web-llvm/docs/api/structs/llvm/targetlowering/targetloweringopt/#a75c3b728d0f9ba68b58c71a4940aedab">llvm::TargetLowering::TargetLoweringOpt::CombineTo</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/x86/x86isellowering-cpp/#aa2cc720ee13ee570307048e7940784be">combineToFPTruncExtElt</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/x86/x86isellowering-cpp/#a7af5f6d50f3be3168a1d91d056c78c8c">combineToHorizontalAddSub</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/riscv/riscvisellowering-cpp/#af55b26411e1b7ab6a05ac6292368daf6">combineToVWMACC</a>, <a href="/web-llvm/docs/api/classes/llvm/vetargetlowering/#acbbd968d4e7364fbdbc6af715f0768e6">llvm::VETargetLowering::combineTRUNCATE</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/x86/x86isellowering-cpp/#ae1e707b863a71852badbab7870597d8f">combineTruncate</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/x86/x86isellowering-cpp/#a68b7af58bc3486a7e1a872337cee003f">combineTruncatedArithmetic</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/riscv/riscvisellowering-cpp/#aac1c6dbf15b6867cf3e1d11b7a02c289">combineTruncOfSraSext</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/riscv/riscvisellowering-cpp/#accd2edb7bf3dca29f9a0f5e233134d09">combineTruncSelectToSMaxUSat</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/riscv/riscvisellowering-cpp/#a143e143f8ee315e712138f13f3343cd5">combineTruncToVnclip</a>, <a href="/web-llvm/docs/api/files/lib/lib/codegen/lib/codegen/selectiondag/dagcombiner-cpp/#a77515f2a50929db00636724e30ef3190">combineUADDO_CARRYDiamond</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/x86/x86isellowering-cpp/#a2e17548b90a1c18c6199a8f99c544dfc">combineUIntToFP</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/x86/x86isellowering-cpp/#aca03795fe4ea383d28dcf4433f994485">combineVectorCompare</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/x86/x86isellowering-cpp/#a54b7a43507d8f339f806b8d1c9f12f29">combineVectorCompareAndMaskUnaryOp</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/x86/x86isellowering-cpp/#ae65b165a9908b7b67d1bb6d3b93e8fd4">combineVectorHADDSUB</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/x86/x86isellowering-cpp/#a611e5eca9f470030689ec3f7d71c8e20">combineVectorInsert</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/riscv/riscvisellowering-cpp/#a6b655bb8a3717c0d0114c94f731ca01a">combineVectorMulToSraBitcast</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/x86/x86isellowering-cpp/#a533da4363391fd2771229d01ac431230">combineVectorPack</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/x86/x86isellowering-cpp/#afb154334e7a7daa07012c210ddd77bc4">combineVectorShiftImm</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/x86/x86isellowering-cpp/#a66295c004fc51403028ea1933b66642a">combineVectorShiftVar</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/x86/x86isellowering-cpp/#a9ac1db32c7172ebb71d45a6ece209b53">combineVEXTRACT_STORE</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/riscv/riscvisellowering-cpp/#a40a4232012f854c98d77eb5fe49a3aed">combineVFMADD_VLWithVFNEG_VL</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/arm/armisellowering-cpp/#a2a80150263a981dc99c6b12775ee495f">CombineVLDDUP</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/x86/x86isellowering-cpp/#a5c6a560bbaa7931f6375fd838fcfbaa8">combineVPMADD</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/x86/x86isellowering-cpp/#a54771fa408498557a71b99ded55f13bf">combineVSelectToBLENDV</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/x86/x86isellowering-cpp/#ab64510f686ff5f453f55707cfd19b07d">combineVSelectWithAllOnesOrZeros</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/x86/x86isellowering-cpp/#a45f59ac6b0a55fb1b92f4b3bfd5ce327">combineVTRUNC</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/riscv/riscvisellowering-cpp/#a491cbf5a685bf7c4455335bc9606ac49">combineVWADDSUBWSelect</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/x86/x86isellowering-cpp/#abb2988152a6f0b53e8da73bd75915365">combineX86AddSub</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/x86/x86isellowering-cpp/#a6038cc86e3b86730ea40b4ee63200f40">combineX86CloadCstore</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/x86/x86isellowering-cpp/#ae6535f37686895d8ab294ce06ffe2f15">combineX86GatherScatter</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/x86/x86isellowering-cpp/#ae0185d63d243a248f5bc69dfc943c88a">combineX86INT_TO_FP</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/x86/x86isellowering-cpp/#af29aa650f73d0ffdd74d33e6d4fef173">combineX86SetCC</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/x86/x86isellowering-cpp/#a4f4cf2e3dcecef6763caca7fd8949d76">combineX86SubCmpForFlags</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/x86/x86isellowering-cpp/#a321df2422ee45cfd96e738928fb178f7">combineXor</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/x86/x86isellowering-cpp/#a7b2e3484fbd87c4d093b88743b84af02">combineXorSubCTLZ</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/x86/x86isellowering-cpp/#a108b26123f976ad2ab078287e4be83ef">combineZext</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/x86/x86isellowering-cpp/#a2126441a7eae0e240bca04767ea42e51">commuteSelect</a>, <a href="/web-llvm/docs/api/classes/llvm/domtreenodebase/#a9d0c80d71ba83d90c53591bfbbdadf44">llvm::DomTreeNodeBase&lt; BlockT &gt;::compare</a>, <a href="/web-llvm/docs/api/namespaces/llvm/sys/unicode/#acb0122730c8d41728ac1213b0bef71c1">llvm::sys::unicode::compareNode</a>, <a href="/web-llvm/docs/api/classes/llvm/scalednumber/#afc6c374e75ac5c2dcf66e8499d6b0fa9">llvm::ScaledNumber&lt; uint64_t &gt;::compareTo</a>, <a href="/web-llvm/docs/api/classes/llvm/scalednumber/#ad0993b94a7bf7bd7d1f23f6a0361210f">llvm::ScaledNumber&lt; uint64_t &gt;::compareTo</a>, <a href="/web-llvm/docs/api/classes/llvm/btftypefuncproto/#acf454103dcd8875ce340e9a8dc028db9">llvm::BTFTypeFuncProto::completeType</a>, <a href="/web-llvm/docs/api/classes/llvm/wasmexception/#a8db890ae03cb072b7198ebcc5d52028b">llvm::WasmException::computeCallSiteTable</a>, <a href="/web-llvm/docs/api/classes/llvm/profilesummarybuilder/#a0cf99f7dc09e330137cb10a3a42c12b3">llvm::ProfileSummaryBuilder::computeDetailedSummary</a>, <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/scalar/simpleloopunswitch-cpp/#a78a15f5bff768264b9e435e319db18f3">computeDomSubtreeCost</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/powerpc/ppcisellowering-cpp/#adcd35cd6dd267ca162a87fac0acb4925">computeFlagsForAddressComputation</a>, <a href="/web-llvm/docs/api/classes/llvm/scheduledagsdnodes/#a6ab45d1027ab01be9c371634c49d077b">llvm::ScheduleDAGSDNodes::computeLatency</a>, <a href="/web-llvm/docs/api/classes/llvm/ehstreamer/#a1f1ea57bc156f9e309b4049bc1d10e17">llvm::EHStreamer::computePadMap</a>, <a href="/web-llvm/docs/api/classes/anonymous-loopdistribute-cpp-/instpartitioncontainer/#a223e50a7d4a7c2c8290b0697da780758">anonymous{LoopDistribute.cpp}::InstPartitionContainer::computePartitionSetForPointers</a>, <a href="/web-llvm/docs/api/classes/llvm/machinebasicblock/#a7ebfe0cc2f78ae5f27e1944412606973">llvm::MachineBasicBlock::computeRegisterLiveness</a>, <a href="/web-llvm/docs/api/namespaces/anonymous-lowermatrixintrinsics-cpp-/#abb6c70c6f3c205d6a0b73be4534c0de5">anonymous{LowerMatrixIntrinsics.cpp}::computeShapeInfoForInst</a>, <a href="/web-llvm/docs/api/namespaces/llvm/object/#acf228956812ef6e7722e8c114fe3b923">llvm::object::computeSymbolSizes</a>, <a href="/web-llvm/docs/api/classes/anonymous-dagcombiner-cpp-/dagcombiner/#a20abe073da0e4cc56c17114804f87b5a">anonymous{DAGCombiner.cpp}::DAGCombiner::ConsiderForPruning</a>, <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/utils/simplifycfg-cpp/#a40bb6295bf75ebb0f636376637ed518f">constantFold</a>, <a href="/web-llvm/docs/api/classes/llvm/dwarfunit/#abaab22fc54a4612ec58459997f58c6cc">llvm::DwarfUnit::constructSubprogramArguments</a>, <a href="/web-llvm/docs/api/namespaces/llvm/codeview/#a810901bf1e6c5f3228de79e7a61ef36b">llvm::codeview::consume</a>, <a href="/web-llvm/docs/api/classes/llvm/diexpressioncursor/#a83bd5b46867c5a738a0ad4ac51fc2187">llvm::DIExpressionCursor::consume</a>, <a href="/web-llvm/docs/api/namespaces/llvm/codeview/#a0d46104eb6ba85dbd9788ff11e64aaa6">llvm::codeview::consume_numeric</a>, <a href="/web-llvm/docs/api/classes/llvm/immutablegraph/nodeset/#a424bd2667f7e3c957b5e340bb0a7284e">llvm::ImmutableGraph&lt; NodeValueT, EdgeValueT &gt;::NodeSet::contains</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a89bc5d532d800b9af260bf5543415366">llvm::ConvertCostTableLookup</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64isellowering-cpp/#a55b5f0acbccdfe1f3e0688fa60b8d5e9">convertMergedOpToPredOp</a>, <a href="/web-llvm/docs/api/files/lib/lib/codegen/lib/codegen/selectiondag/dagcombiner-cpp/#a0d7b181917dd3066841199e4299d8b91">ConvertSelectToConcatVector</a>, <a href="/web-llvm/docs/api/classes/llvm/intervalmapimpl/nodebase/#a28ff2f41afe22a42b271b12b4fb8d809">llvm::IntervalMapImpl::NodeBase&lt; std::pair&lt; KeyT, KeyT &gt;, ValT, LeafSize &gt;::copy</a>, <a href="/web-llvm/docs/api/classes/llvm/selectiondag/#a7ccbc2b7c2fc5cf4c9dbb648570bcf01">llvm::SelectionDAG::copyExtraInfo</a>, <a href="/web-llvm/docs/api/files/lib/lib/codegen/atomicexpandpass-cpp/#ae9315c94e4cd695aceef039966a2beba">copyMetadataForAtomic</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a2f8e44f52bb2b2c5d2273eccec70faae">llvm::copyMetadataForLoad</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#ab057ca6ed74ccfa73d1a0d2cf15b2300">llvm::copyNonnullMetadata</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#aadb1772c1026a517d15c771ceb6a91ca">llvm::copyRangeMetadata</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a25f22870cc19ca22bc418936b4e28e08">llvm::CostTableLookup</a>, <a href="/web-llvm/docs/api/classes/llvm/stringref/#a797db79c8d98dcd992d5fe9a71ffe68c">llvm::StringRef::count</a>, <a href="/web-llvm/docs/api/classes/llvm/scalednumberbase/#a5e272c55d29857f950d2f777c5f2a3a4">llvm::ScaledNumberBase::countLeadingZeros32</a>, <a href="/web-llvm/docs/api/classes/llvm/scalednumberbase/#a1b5e7c1354f6907638d72d82e6f70af9">llvm::ScaledNumberBase::countLeadingZeros64</a>, <a href="/web-llvm/docs/api/files/lib/lib/codegen/lib/codegen/selectiondag/instremitter-cpp/#ad63c17e29f648fc3ed1985977c520ae7">countOperands</a>, <a href="/web-llvm/docs/api/classes/llvm/instremitter/#a6a91d391f3b91e549c1514468966f4e6">llvm::InstrEmitter::CountResults</a>, <a href="/web-llvm/docs/api/classes/llvm/function/#a7321f6163cd0a3ed2c1e87c63c6c4263">llvm::Function::Create</a>, <a href="/web-llvm/docs/api/classes/llvm/function/#a05d7aedbbdc0fd24e8bc27edfe9c603f">llvm::Function::Create</a>, <a href="/web-llvm/docs/api/classes/llvm/pointersumtype/#a822f3a6433ac1dbaaead6a3143675fd0">llvm::PointerSumType&lt; TagT, MemberTs... &gt;::create</a>, <a href="/web-llvm/docs/api/classes/llvm/irbuilderbase/#a7f4eefe9cb1d01508cce70c0aa9a9595">llvm::IRBuilderBase::CreateAggregateRet</a>, <a href="/web-llvm/docs/api/classes/llvm/dwarfunit/#ac4053999da10fee3e053346031495319">llvm::DwarfUnit::createAndAddDIE</a>, <a href="/web-llvm/docs/api/classes/llvm/abstractdependencegraphbuilder/#ac76acbd497d18c7306f8120c6f11fb51">llvm::AbstractDependenceGraphBuilder&lt; GraphType &gt;::createDefUseEdges</a>, <a href="/web-llvm/docs/api/classes/llvm/abstractdependencegraphbuilder/#ac76acbd497d18c7306f8120c6f11fb51">llvm::AbstractDependenceGraphBuilder&lt; DataDependenceGraph &gt;::createDefUseEdges</a>, <a href="/web-llvm/docs/api/classes/llvm/dibuilder/#a9cb4bcf5ce38d7b765c6f915f66f4bcf">llvm::DIBuilder::createGlobalVariableExpression</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a987f18f3591a74415a00f67b0fafe2ef">llvm::createGraphFilename</a>, <a href="/web-llvm/docs/api/files/lib/lib/analysis/blockfrequencyinfoimpl-cpp/#ada202dbe971b41ac9748f92c80464573">createIrreducibleLoop</a>, <a href="/web-llvm/docs/api/classes/llvm/abstractdependencegraphbuilder/#a9c4196edca24d644ff96e55945abd207">llvm::AbstractDependenceGraphBuilder&lt; DataDependenceGraph &gt;::createMemoryDependencyEdges</a>, <a href="/web-llvm/docs/api/classes/llvm/slottracker/#aa7699ddb98cde7601ae34ea616c08ac9">llvm::SlotTracker::createMetadataSlot</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a21576774815efd6bd8374d3ac55c65f6">llvm::createPGONameMetadata</a>, <a href="/web-llvm/docs/api/namespaces/llvm/sys/unicode/#a67818bf1586984762d35986330c4129b">llvm::sys::unicode::createRoot</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64slshardening-cpp/#a2daa71efe924e3772ea89ce14dc55f83">createThunkName</a>, <a href="/web-llvm/docs/api/classes/anonymous-aarch64iseldagtodag-cpp-/aarch64dagtodagisel/#a097c2cf1ff74009e3254960e61688c17">anonymous{AArch64ISelDAGToDAG.cpp}::AArch64DAGToDAGISel::createTuple</a>, <a href="/web-llvm/docs/api/structs/anonymous-xcoffobjectwriter-cpp-/csectsectionentry/#acbc7352200a105080886a8652f3b77da">anonymous{XCOFFObjectWriter.cpp}::CsectSectionEntry::CsectSectionEntry</a>, <a href="/web-llvm/docs/api/classes/llvm/targetlowering/#ae4ab2e1ac81721435d73f03617e59fc7">llvm::TargetLowering::CTTZTableLookup</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/loongarch/loongarchisellowering-cpp/#ab42ac60e33f89fbdaac10587d7b8f045">customLegalizeToWOp</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/riscv/riscvisellowering-cpp/#a748aa70e33fa7ee2dc2de7d91ca0741b">customLegalizeToWOp</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/loongarch/loongarchisellowering-cpp/#a765b869533ec8cb0d992e1199f71eb40">customLegalizeToWOpWithSExt</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/riscv/riscvisellowering-cpp/#a765b869533ec8cb0d992e1199f71eb40">customLegalizeToWOpWithSExt</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64isellowering-cpp/#a01509c23581fb688a399381319f6b1a3">CustomNonLegalBITCASTResults</a>, <a href="/web-llvm/docs/api/classes/llvm/selectiondag/#ae465b76a465f0d698764e660f1be55d0">llvm::SelectionDAG::DAGUpdateListener</a>, <a href="/web-llvm/docs/api/classes/llvm/dbgentity/#adea6ec515624a1a104a8cebee572d416">llvm::DbgEntity::DbgEntity</a>, <a href="/web-llvm/docs/api/classes/llvm/ddgedge/#aaa4fd5484dce2d2197eda38bc1a1690b">llvm::DDGEdge::DDGEdge</a>, <a href="/web-llvm/docs/api/classes/llvm/ddgedge/#a84cd95a42ccffec71f475ba7a3060552">llvm::DDGEdge::DDGEdge</a>, <a href="/web-llvm/docs/api/classes/llvm/ddgnode/#a4e38729bad92e0a8ee0ee5d216f79dc3">llvm::DDGNode::DDGNode</a>, <a href="/web-llvm/docs/api/classes/llvm/ddgnode/#a50418bd65b9095d0414334bafaef3f6d">llvm::DDGNode::DDGNode</a>, <a href="/web-llvm/docs/api/classes/llvm/debugloc/#a37616eb7c1e47f6df05f3fdbdc09552a">llvm::DebugLoc::DebugLoc</a>, <a href="/web-llvm/docs/api/namespaces/llvm/aarch64-am/#a1affd6d7e8a280fa6a0b642a6e0734b8">llvm::AArch64_AM::decodeLogicalImmediate</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/systemz/lib/target/systemz/disassembler/systemzdisassembler-cpp/#a75f4ac701a183d154f7798bf5db43311">decodePCDBLOperand</a>, <a href="/web-llvm/docs/api/files/lib/lib/demangle/rustdemangle-cpp/#ad70908652bd5b04580fa8bd87c85f701">decodePunycode</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/powerpc/lib/target/powerpc/disassembler/ppcdisassembler-cpp/#a084584c6167990eece3ec663f759829e">decodeRegisterClass</a>, <a href="/web-llvm/docs/api/structs/llvm/dwarftypeprinter/#a3ffc1f6f44d6f01f289108370a0fbf21">llvm::DWARFTypePrinter&lt; DieType &gt;::decomposeConstVolatile</a>, <a href="/web-llvm/docs/api/classes/anonymous-dagcombiner-cpp-/dagcombiner/#aa764f81559131c9afac18641c36a806d">anonymous{DAGCombiner.cpp}::DAGCombiner::deleteAndRecombine</a>, <a href="/web-llvm/docs/api/classes/llvm/selectiondag/#a5f57dcbedc16dced31c61f7bbbb06ded">llvm::SelectionDAG::DeleteNode</a>, <a href="/web-llvm/docs/api/classes/llvm/intrusivebacklist/#a22e759cf779b05bb76d8c180ec446b2c">llvm::IntrusiveBackList&lt; Node &gt;::deleteNode</a>, <a href="/web-llvm/docs/api/structs/anonymous-hexagoniseldagtodaghvx-cpp-/deleter/#ad591c05d8287727befde385e14a9d513">anonymous{HexagonISelDAGToDAGHVX.cpp}::Deleter::Deleter</a>, <a href="/web-llvm/docs/api/classes/llvm/mdnode/#a35e99dcd42831a0c100d6eed535eae23">llvm::MDNode::deleteTemporary</a>, <a href="/web-llvm/docs/api/structs/llvm/domtreebuilder/semincainfo/#ac0c56f97d07cfa7188e654e794e5032e">llvm::DomTreeBuilder::SemiNCAInfo&lt; DomTreeT &gt;::DeleteUnreachable</a>, <a href="/web-llvm/docs/api/classes/llvm/sdvalue/#a4eeed080d528d04900345a80b433c4cf">llvm::SDValue::DenseMapInfo&lt; SDValue &gt;</a>, <a href="/web-llvm/docs/api/classes/llvm/dependencegraphinfo/#a6377266976bdd637c555d2fb020306d7">llvm::DependenceGraphInfo&lt; DDGNode &gt;::DependenceGraphInfo</a>, <a href="/web-llvm/docs/api/classes/llvm/outlinedhashtree/#a4f9dd40bc3145351ebf12cfb4191a0eb">llvm::OutlinedHashTree::depth</a>, <a href="/web-llvm/docs/api/classes/llvm/abstractdependencegraphbuilder/#ab95e08bc6b6b4d0e95caada63521ad6d">llvm::AbstractDependenceGraphBuilder&lt; GraphType &gt;::destroyNode</a>, <a href="/web-llvm/docs/api/classes/llvm/hexagondagtodagisel/#a96da5708e20bbbc59324f0985bd9df30">llvm::HexagonDAGToDAGISel::DetectUseSxtw</a>, <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/vectorize/loopvectorize-cpp/#a0b91e092434338369b2e1995b87f0c5b">determineVPlanVF</a>, <a href="/web-llvm/docs/api/classes/llvm/dfcalculateworkobject/#a1132cf43c02abb0420eab44af77251f1">llvm::DFCalculateWorkObject&lt; BlockT &gt;::DFCalculateWorkObject</a>, <a href="/web-llvm/docs/api/classes/llvm/dgedge/#a12f5e07ec69a17be74aef6795313a059">llvm::DGEdge&lt; DDGNode, DDGEdge &gt;::DGEdge</a>, <a href="/web-llvm/docs/api/classes/llvm/dgnode/#aedb1a6d120ba9e76408591a1e6f83cb9">llvm::DGNode&lt; DDGNode, DDGEdge &gt;::DGNode</a>, <a href="/web-llvm/docs/api/classes/llvm/dgnode/#a4c9011dc0a51452d86714af40f2c340a">llvm::DGNode&lt; DDGNode, DDGEdge &gt;::DGNode</a>, <a href="/web-llvm/docs/api/structs/llvm/diarglistkeyinfo/#a84faa0018dbdf67ceec08a51743bdfc0">llvm::DIArgListKeyInfo::DIArgListKeyInfo</a>, <a href="/web-llvm/docs/api/structs/llvm/dictscope/#a8b646b491982742f60b2d0ba5db5db1a">llvm::DictScope::DictScope</a>, <a href="/web-llvm/docs/api/classes/llvm/directedgraph/#af366bb2bb3a0b9a3d598a7ef58a05cd9">llvm::DirectedGraph&lt; DDGNode, DDGEdge &gt;::DirectedGraph</a>, <a href="/web-llvm/docs/api/files/lib/lib/codegen/lib/codegen/selectiondag/selectiondag-cpp/#a78d002ff9015553f590990ec28181d63">doNotCSE</a>, <a href="/web-llvm/docs/api/classes/llvm/arrayref/#aa713e2599e000adc01ced998c05502a7">llvm::ArrayRef&lt; llvm::cfg::Update&lt; MachineBasicBlock * &gt; &gt;::drop_back</a>, <a href="/web-llvm/docs/api/classes/llvm/binarystreamrefbase/#a25aa9ecfd327d418a3030cc648d751af">llvm::BinaryStreamRefBase&lt; RefType, StreamType &gt;::drop_back</a>, <a href="/web-llvm/docs/api/classes/llvm/mutablearrayref/#ad1acfeed5712da9a4ffafda05fac15ac">llvm::MutableArrayRef&lt; uint8_t &gt;::drop_back</a>, <a href="/web-llvm/docs/api/classes/llvm/stringref/#ae2705fd641fb3d1eefa2691b5117cf22">llvm::StringRef::drop_back</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a02981de53fb6ffd384d39addc4d25f37">llvm::drop_begin</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a9b64313b5c1907066b7bab1c60a2ea08">llvm::drop_end</a>, <a href="/web-llvm/docs/api/classes/llvm/arrayref/#a55089293ebaccd683a82d97170041376">llvm::ArrayRef&lt; llvm::cfg::Update&lt; MachineBasicBlock * &gt; &gt;::drop_front</a>, <a href="/web-llvm/docs/api/classes/llvm/binarystreamrefbase/#a4232f2228987b39430e8d7a6b48d8188">llvm::BinaryStreamRefBase&lt; RefType, StreamType &gt;::drop_front</a>, <a href="/web-llvm/docs/api/structs/llvm/binarysubstreamref/#aee6463dc56686cedc45c6ffbdf982854">llvm::BinarySubstreamRef::drop_front</a>, <a href="/web-llvm/docs/api/classes/llvm/mutablearrayref/#a23489fd833f61022bf08dbe3ba9f1973">llvm::MutableArrayRef&lt; uint8_t &gt;::drop_front</a>, <a href="/web-llvm/docs/api/classes/llvm/stringref/#a3fb2867a1e9fa36e135d9ee4dffb0167">llvm::StringRef::drop_front</a>, <a href="/web-llvm/docs/api/classes/llvm/binarystreamrefbase/#a7f5b31b1a08588e0e76cc35f6eb280cf">llvm::BinaryStreamRefBase&lt; RefType, StreamType &gt;::drop_symmetric</a>, <a href="/web-llvm/docs/api/structs/anonymous-hexagoniseldagtodaghvx-cpp-/coloring/#a257e315d0507937d8463c1428da67284">anonymous{HexagonISelDAGToDAGHVX.cpp}::Coloring::dump</a>, <a href="/web-llvm/docs/api/classes/llvm/lexicalscope/#aa6c3d87456bbee468f6fd51bf8163dfe">llvm::LexicalScope::dump</a>, <a href="/web-llvm/docs/api/classes/llvm/sandboxir/schedbundle/#a51321cc6f05a9ae7b5f26b63d1932f30">llvm::sandboxir::SchedBundle::dump</a>, <a href="/web-llvm/docs/api/classes/llvm/selectiondag/#a8e7eabcdc79b470fd13a397b4464bfe2">llvm::SelectionDAG::dump</a>, <a href="/web-llvm/docs/api/classes/llvm/scheduledagsdnodes/#ab34667f1d218ea0b6566dd8f861dfe93">llvm::ScheduleDAGSDNodes::dumpNode</a>, <a href="/web-llvm/docs/api/files/lib/lib/codegen/lib/codegen/selectiondag/selectiondagdumper-cpp/#ad9526a1ce54457f4cef4a593ad1e99ea">DumpNodes</a>, <a href="/web-llvm/docs/api/files/lib/lib/codegen/lib/codegen/selectiondag/selectiondagdumper-cpp/#a8b40b63522fe1b491ba458feec392ea6">DumpNodesr</a>, <a href="/web-llvm/docs/api/structs/anonymous-xcoffobjectwriter-cpp-/dwarfsectionentry/#ae6cfee84ea7b7e4ff3b5ec82038da80b">anonymous{XCOFFObjectWriter.cpp}::DwarfSectionEntry::DwarfSectionEntry</a>, <a href="/web-llvm/docs/api/files/lib/lib/codegen/lib/codegen/selectiondag/legalizeintegertypes-cpp/#a296983d97d1ba11410248b9965b244e8">earlyExpandDIVFIX</a>, <a href="/web-llvm/docs/api/namespaces/anonymous-amdgpulibfunc-cpp-/#a848a2d90f798473878904dcbddfba506">anonymous{AMDGPULibFunc.cpp}::eatTerm</a>, <a href="/web-llvm/docs/api/classes/llvm/lazycallgraph/edge/#a97e3e2913f67539740641df7f922826d">llvm::LazyCallGraph::Edge::Edge</a>, <a href="/web-llvm/docs/api/classes/llvm/lazycallgraph/edge/#adc9a76e35304dc25cc0d3006d6f2939c">llvm::LazyCallGraph::Edge::Edge</a>, <a href="/web-llvm/docs/api/structs/llvm/sdpatternmatch/effectiveoperands/#a0c5e6b6524b2a56ddeba10b0c5c4b7c1">llvm::SDPatternMatch::EffectiveOperands&lt; ExcludeChain &gt;::EffectiveOperands</a>, <a href="/web-llvm/docs/api/structs/llvm/sdpatternmatch/effectiveoperands-b0fedc964c748238de2c085ed61f691c/#a3af8fd2e929225e1accb0d5e38af5452">llvm::SDPatternMatch::EffectiveOperands&lt; false &gt;::EffectiveOperands</a>, <a href="/web-llvm/docs/api/classes/anonymous-simplifyindvar-cpp-/simplifyindvar/#a664aaf46532d6ebeed0dfeb704308d33">anonymous{SimplifyIndVar.cpp}::SimplifyIndvar::eliminateSDiv</a>, <a href="/web-llvm/docs/api/classes/llvm/ondiskchainedhashtablegenerator/#a9c8d5a30bca2110b979dbe64063ee93d">llvm::OnDiskChainedHashTableGenerator&lt; Info &gt;::Emit</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/loongarch/loongarchisellowering-cpp/#a36eb02ea70b6f7df1795c2df0b297f16">emitErrorAndReplaceIntrinsicResults</a>, <a href="/web-llvm/docs/api/classes/llvm/systemzasmprinter/#a5a25bb817d51790574c718d2a39bfafc">llvm::SystemZAsmPrinter::emitFunctionEntryLabel</a>, <a href="/web-llvm/docs/api/classes/llvm/instrprofrecordwritertrait/#ad6f07481b72e3568320b1a68fe1d320d">llvm::InstrProfRecordWriterTrait::EmitKey</a>, <a href="/web-llvm/docs/api/classes/llvm/instrprofrecordwritertrait/#a063fe524f591af6fc154088fe2feb92f">llvm::InstrProfRecordWriterTrait::EmitKeyDataLength</a>, <a href="/web-llvm/docs/api/classes/llvm/memprof/callstackwritertrait/#a7bbd7db899237eba003035351c08afa3">llvm::memprof::CallStackWriterTrait::EmitKeyDataLength</a>, <a href="/web-llvm/docs/api/classes/llvm/memprof/framewritertrait/#aed67f77a3d6074d4466f9d5b75f6084d">llvm::memprof::FrameWriterTrait::EmitKeyDataLength</a>, <a href="/web-llvm/docs/api/classes/llvm/memprof/recordwritertrait/#a83b1030d5d1deae5ec5deee03beb31a2">llvm::memprof::RecordWriterTrait::EmitKeyDataLength</a>, <a href="/web-llvm/docs/api/classes/anonymous-ppcasmprinter-cpp-/ppcaixasmprinter/#a3275b7a3457510661d5af13a82bb48ca">anonymous{PPCAsmPrinter.cpp}::PPCAIXAsmPrinter::emitModuleCommandLines</a>, <a href="/web-llvm/docs/api/classes/llvm/asmprinter/#a11dc1e48c7d0e0da77a6d6d377fd391b">llvm::AsmPrinter::emitNops</a>, <a href="/web-llvm/docs/api/classes/anonymous-scheduledagfast-cpp-/scheduledaglinearize/#a16c498db76eb73d37731b36c18879ee4">anonymous{ScheduleDAGFast.cpp}::ScheduleDAGLinearize::EmitSchedule</a>, <a href="/web-llvm/docs/api/classes/llvm/scheduledagsdnodes/#a6f60ed03227dbeb711a3ae9b1f0238e9">llvm::ScheduleDAGSDNodes::EmitSchedule</a>, <a href="/web-llvm/docs/api/structs/anonymous-stackframelayoutanalysispass-cpp-/stackframelayoutanalysispass/#a80b987bb6e1318d2954ead530a285066">anonymous{StackFrameLayoutAnalysisPass.cpp}::StackFrameLayoutAnalysisPass::emitSourceLocRemark</a>, <a href="/web-llvm/docs/api/structs/anonymous-stackframelayoutanalysispass-cpp-/stackframelayoutanalysispass/#a69dafe1f45af554b1b82bcde2503a3c4">anonymous{StackFrameLayoutAnalysisPass.cpp}::StackFrameLayoutAnalysisPass::emitStackFrameLayoutRemarks</a>, <a href="/web-llvm/docs/api/classes/llvm/mipsmccodeemitter/#ada77d1fd6603eff06b4da3c2381b84be">llvm::MipsMCCodeEmitter::encodeInstruction</a>, <a href="/web-llvm/docs/api/classes/llvm/sdnodeiterator/#a3607d62a16488ad561958ccaf04dd511">llvm::SDNodeIterator::end</a>, <a href="/web-llvm/docs/api/classes/llvm/sunititerator/#a19cadb1ba98e4562c01f1b7df0999fe5">llvm::SUnitIterator::end</a>, <a href="/web-llvm/docs/api/classes/llvm/selectiondagisel/#a6d548a27495e0e978c1ef0cc0f185744">llvm::SelectionDAGISel::EnforceNodeIdInvariant</a>, <a href="/web-llvm/docs/api/structs/llvm/enumentry/#a232bc12eb67ba354545cf0e879d119d9">llvm::EnumEntry&lt; T &gt;::EnumEntry</a>, <a href="/web-llvm/docs/api/structs/llvm/enumentry/#ae48bba61b34214a2e5187f580640a02f">llvm::EnumEntry&lt; T &gt;::EnumEntry</a>, <a href="/web-llvm/docs/api/structs/anonymous-hexagonconstextenders-cpp-/rangetree/#aa7faf5116f8fe82cceccd026ac809bf7">anonymous{HexagonConstExtenders.cpp}::RangeTree::erase</a>, <a href="/web-llvm/docs/api/structs/anonymous-hexagoniseldagtodaghvx-cpp-/nullifyingvector/#ac24d77d1514f4152c2155ec32d3dbb06">anonymous{HexagonISelDAGToDAGHVX.cpp}::NullifyingVector&lt; T &gt;::erase</a>, <a href="/web-llvm/docs/api/classes/llvm/smallvectorimpl/#a563ffc2ff61c499b3be2e00100cb72fa">llvm::const_iterator&lt; MemoryLocation &gt;::erase</a>, <a href="/web-llvm/docs/api/classes/llvm/smallvectorimpl/#aa3787c69a41c14127758c359911180aa">llvm::const_iterator&lt; MemoryLocation &gt;::erase</a>, <a href="/web-llvm/docs/api/classes/llvm/immutablegraph/nodeset/#ac00b486bbae9e53cf57d33d02de8b588">llvm::ImmutableGraph&lt; NodeValueT, EdgeValueT &gt;::NodeSet::erase</a>, <a href="/web-llvm/docs/api/classes/llvm/escapeenumerator/#acf98a71c5c63f4ceedb8db2359e6e6d0">llvm::EscapeEnumerator::EscapeEnumerator</a>, <a href="/web-llvm/docs/api/structs/llvm/hexagonevaluator/#a49b4d08c8b0024b97c7e090a0b3e50f6">llvm::HexagonEvaluator::evaluate</a>, <a href="/web-llvm/docs/api/structs/anonymous-basicaliasanalysis-cpp-/castedvalue/#ad6216e095ec50beb58f5fa0306f057f5">anonymous{BasicAliasAnalysis.cpp}::CastedValue::evaluateWith</a>, <a href="/web-llvm/docs/api/structs/anonymous-basicaliasanalysis-cpp-/castedvalue/#af5333260b4104fef104ea3459553cae1">anonymous{BasicAliasAnalysis.cpp}::CastedValue::evaluateWith</a>, <a href="/web-llvm/docs/api/structs/anonymous-xcoffobjectwriter-cpp-/exceptionsectionentry/#a5025bde0980a70bcfa30bbbf8b3d7b37">anonymous{XCOFFObjectWriter.cpp}::ExceptionSectionEntry::ExceptionSectionEntry</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/arm/armisellowering-cpp/#af06754acf6dbda0709a6cda0b11cdab5">Expand64BitShift</a>, <a href="/web-llvm/docs/api/classes/llvm/targetlowering/#a010da65f0320c4a35d573ae07071b786">llvm::TargetLowering::expandABD</a>, <a href="/web-llvm/docs/api/classes/llvm/targetlowering/#a52e90a14f4d03b8959c096086b1bca73">llvm::TargetLowering::expandABS</a>, <a href="/web-llvm/docs/api/classes/llvm/targetlowering/#a39e0c74abf7ed800cb60f1bf840efe42">llvm::TargetLowering::expandAVG</a>, <a href="/web-llvm/docs/api/classes/llvm/targetlowering/#ad103ae2c1e3a3e2451ea8ab5febf7075">llvm::TargetLowering::expandBITREVERSE</a>, <a href="/web-llvm/docs/api/classes/llvm/targetlowering/#afdc2ae0ea51276d42cf58621158bb7b6">llvm::TargetLowering::expandBSWAP</a>, <a href="/web-llvm/docs/api/classes/llvm/targetlowering/#aa7fb5a0db40a7dbc4a0ac57bda71b893">llvm::TargetLowering::expandCTLZ</a>, <a href="/web-llvm/docs/api/classes/llvm/targetlowering/#a4fc0254299bd69d2edbd4bf7949292dc">llvm::TargetLowering::expandCTPOP</a>, <a href="/web-llvm/docs/api/classes/llvm/targetlowering/#a3060b73c758e36617520472f85e8a66d">llvm::TargetLowering::expandCTTZ</a>, <a href="/web-llvm/docs/api/classes/llvm/targetlowering/#abddef937939ecbe4cff930c60b055176">llvm::TargetLowering::expandDIVREMByConstant</a>, <a href="/web-llvm/docs/api/classes/llvm/targetlowering/#a942902db44f41703d4055454e2b39332">llvm::TargetLowering::expandFMINIMUM_FMAXIMUM</a>, <a href="/web-llvm/docs/api/classes/llvm/targetlowering/#ab4b58e5ebed5507d40b5e4c0e5e5d19a">llvm::TargetLowering::expandFMINIMUMNUM_FMAXIMUMNUM</a>, <a href="/web-llvm/docs/api/classes/llvm/targetlowering/#a2615b4208115a17e0cc88dc5e7142ee9">llvm::TargetLowering::expandFMINNUM_FMAXNUM</a>, <a href="/web-llvm/docs/api/classes/llvm/targetlowering/#a606e204a6a530a50176f469e79f23832">llvm::TargetLowering::expandFP_TO_INT_SAT</a>, <a href="/web-llvm/docs/api/classes/llvm/targetlowering/#ae88a98f9b6ef7661ed256aaaaea7455c">llvm::TargetLowering::expandFP_TO_SINT</a>, <a href="/web-llvm/docs/api/classes/llvm/targetlowering/#ac3bdbef1c14de11ac53ef2736000e900">llvm::TargetLowering::expandFP_TO_UINT</a>, <a href="/web-llvm/docs/api/classes/llvm/targetlowering/#a6277730d715a362deb5bd89ed0e17f53">llvm::TargetLowering::expandFunnelShift</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/x86/x86isellowering-cpp/#a53402f6e918f527e92ecdc700d88c472">expandIntrinsicWChainHelper</a>, <a href="/web-llvm/docs/api/classes/llvm/targetlowering/#ab707d083b764fa474237a76bc4b05694">llvm::TargetLowering::expandMUL</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/riscv/riscvisellowering-cpp/#a38a4767fc581ef400cbef34ac25d9f6c">expandMul</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/arm/armisellowering-cpp/#a399ea332dd7c5c88085dd03e09152545">ExpandREAD_REGISTER</a>, <a href="/web-llvm/docs/api/classes/llvm/targetlowering/#afdf8e533128a4e28f6720f70ab726376">llvm::TargetLowering::expandROT</a>, <a href="/web-llvm/docs/api/classes/llvm/targetlowering/#ad7c6044f8250efb3a9da26bcb6b1db62">llvm::TargetLowering::expandShiftParts</a>, <a href="/web-llvm/docs/api/classes/llvm/targetlowering/#a1d9e993d1512edc0f76c3545a7730444">llvm::TargetLowering::expandUINT_TO_FP</a>, <a href="/web-llvm/docs/api/classes/llvm/targetlowering/#a5dfdb0c505a77dd707e9e9d4a439d656">llvm::TargetLowering::expandVectorFindLastActive</a>, <a href="/web-llvm/docs/api/classes/llvm/targetlowering/#afa6a46c05752cd363e5c254403d30965">llvm::TargetLowering::expandVPBITREVERSE</a>, <a href="/web-llvm/docs/api/classes/llvm/targetlowering/#a249598a307c825ac80d22a45d863d3e4">llvm::TargetLowering::expandVPBSWAP</a>, <a href="/web-llvm/docs/api/classes/llvm/targetlowering/#a3d7ed5e11454a58e268bc32c6794a26f">llvm::TargetLowering::expandVPCTLZ</a>, <a href="/web-llvm/docs/api/classes/llvm/targetlowering/#a63399fefaac1b73b4c1a56c0c941004d">llvm::TargetLowering::expandVPCTPOP</a>, <a href="/web-llvm/docs/api/classes/llvm/targetlowering/#ab7abea2a5b5251eb10473c9c610d6490">llvm::TargetLowering::expandVPCTTZ</a>, <a href="/web-llvm/docs/api/classes/llvm/targetlowering/#a6f29c194ef5edad7c896b8b1ea1b3637">llvm::TargetLowering::expandVPCTTZElements</a>, <a href="/web-llvm/docs/api/classes/llvm/ppctargetlowering/#a414d9dfa6f85f8ad371a510821713e61">llvm::PPCTargetLowering::expandVSXLoadForLE</a>, <a href="/web-llvm/docs/api/classes/llvm/ppctargetlowering/#abf2cd323dcdc4b2b0a4741c62b30d0ba">llvm::PPCTargetLowering::expandVSXStoreForLE</a>, <a href="/web-llvm/docs/api/files/lib/lib/codegen/lib/codegen/selectiondag/dagcombiner-cpp/#a021f42abfec39ba02f6b719a449b21db">ExtendUsesToFormExtLoad</a>, <a href="/web-llvm/docs/api/files/lib/lib/ir/core-cpp/#a39c9d039f5cbab6c4155e907c466ab25">extractMDNode</a>, <a href="/web-llvm/docs/api/classes/llvm/hexagondagtodagisel/#ac9fa3f2ca7381a3d97d2d24ce885e83e">llvm::HexagonDAGToDAGISel::FastFDiv</a>, <a href="/web-llvm/docs/api/classes/llvm/hexagondagtodagisel/#aab413ab449c8d67dc4f4badc638f57b8">llvm::HexagonDAGToDAGISel::FDiv</a>, <a href="/web-llvm/docs/api/structs/anonymous-structurizecfg-cpp-/subgraphtraits/#a12d23468b7199813de9814c909ace4fd">anonymous{StructurizeCFG.cpp}::SubGraphTraits::filterAll</a>, <a href="/web-llvm/docs/api/structs/anonymous-structurizecfg-cpp-/subgraphtraits/#aac54e97dc0b60db5b332df29b11d56a8">anonymous{StructurizeCFG.cpp}::SubGraphTraits::filterSet</a>, <a href="/web-llvm/docs/api/classes/llvm/callgraphupdater/#adecede763aee9d37e00fee2c2328ac7e">llvm::CallGraphUpdater::finalize</a>, <a href="/web-llvm/docs/api/classes/llvm/dibuilder/#a138b93205c71960aa94763a1081c50e9">llvm::DIBuilder::finalize</a>, <a href="/web-llvm/docs/api/classes/llvm/giselworklist/#a8dfa66087776883d9901276039da5f31">llvm::GISelWorkList&lt; 512 &gt;::finalize</a>, <a href="/web-llvm/docs/api/classes/llvm/stringref/#a82369bea2700347f68e1f43e30d2d47b">llvm::StringRef::find</a>, <a href="/web-llvm/docs/api/classes/llvm/lexicalscopes/#a97c91dd63cc11f0c4fd4b537b079e8bd">llvm::LexicalScopes::findAbstractScope</a>, <a href="/web-llvm/docs/api/classes/anonymous-aarch64iseldagtodag-cpp-/aarch64dagtodagisel/#a9d6ab2ea6bde7a1c20063d6b9240e396">anonymous{AArch64ISelDAGToDAG.cpp}::AArch64DAGToDAGISel::findAddrModeSVELoadStore</a>, <a href="/web-llvm/docs/api/classes/llvm/pmtoplevelmanager/#aa2b6f31b009d485e411860e7547055c4">llvm::PMTopLevelManager::findAnalysisUsage</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/arm/armisellowering-cpp/#a64dad98cd7f82adb3de73d6f2c83e0f5">FindBFIToCombineWith</a>, <a href="/web-llvm/docs/api/classes/llvm/switchcg/switchlowering/#ab5de88dc9568b784876478e316042ba6">llvm::SwitchCG::SwitchLowering::findBitTestClusters</a>, <a href="/web-llvm/docs/api/files/lib/lib/codegen/lib/codegen/selectiondag/scheduledagrrlist-cpp/#aa10776cccd7d800d6a2357c5bd4129ba">FindCallSeqStart</a>, <a href="/web-llvm/docs/api/classes/llvm/dgnode/#a8560da4ee52510bb0b6bec7c71cf2855">llvm::DGNode&lt; DDGNode, DDGEdge &gt;::findEdgesTo</a>, <a href="/web-llvm/docs/api/classes/llvm/dgnode/#af1122d7e9c3003452415ccff7939c6d5">llvm::DGNode&lt; DDGNode, DDGEdge &gt;::findEdgeTo</a>, <a href="/web-llvm/docs/api/classes/llvm/intervalmapimpl/branchnode/#aa380d81762b0652a60d0db3e1592ced2">llvm::IntervalMapImpl::BranchNode&lt; KeyT, ValT, Sizer::BranchSize, Traits &gt;::findFrom</a>, <a href="/web-llvm/docs/api/classes/llvm/intervalmapimpl/leafnode/#afd4d5cb4ca79c050b69ef16dbbc64aae">llvm::IntervalMapImpl::LeafNode&lt; KeyT, ValT, Sizer::LeafSize, Traits &gt;::findFrom</a>, <a href="/web-llvm/docs/api/files/lib/lib/codegen/lib/codegen/selectiondag/scheduledagfast-cpp/#ac50565f46bf17e6c180062066ad3842d">findGluedUser</a>, <a href="/web-llvm/docs/api/classes/llvm/directedgraph/#a803c71157136a4df79e5422f83ae2c92">llvm::DirectedGraph&lt; DDGNode, DDGEdge &gt;::findIncomingEdgesToNode</a>, <a href="/web-llvm/docs/api/classes/llvm/lexicalscopes/#a975b93f1b5bdac0a6ffcaf130570d4d8">llvm::LexicalScopes::findInlinedScope</a>, <a href="/web-llvm/docs/api/classes/llvm/switchcg/switchlowering/#a41add37692675e7e74358acc1483f168">llvm::SwitchCG::SwitchLowering::findJumpTables</a>, <a href="/web-llvm/docs/api/classes/llvm/lexicalscopes/#aba236eb440fe88eb1906b3e8f00bd037">llvm::LexicalScopes::findLexicalScope</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/amdgpuiseldagtodag-cpp/#ab3e9e05d43f3d0d03eb8b698cbab4808">findMemSDNode</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64isellowering-cpp/#a64348c468485ac9fa8aaf382307061fb">findMoreOptimalIndexType</a>, <a href="/web-llvm/docs/api/classes/llvm/directedgraph/#af8701256ecdf4d3b262d725798e38426">llvm::DirectedGraph&lt; DDGNode, DDGEdge &gt;::findNode</a>, <a href="/web-llvm/docs/api/classes/llvm/directedgraph/#afd2c323f0a073d8d2f7d1fe0d622967e">llvm::DirectedGraph&lt; DDGNode, DDGEdge &gt;::findNode</a>, <a href="/web-llvm/docs/api/files/lib/lib/codegen/lib/codegen/selectiondag/selectiondagisel-cpp/#a7e5a9b5c5f87a0f7d2227881e84be8a2">findNonImmUse</a>, <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/utils/splitmodule-cpp/#a972e26a6789667f85f40893033116590">findPartitions</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/arm/armisellowering-cpp/#a34e84895bebe01ea797c47e6a2499d01">findPointerConstIncrement</a>, <a href="/web-llvm/docs/api/structs/llvm/domtreebuilder/semincainfo/#a2867e9240af1e5a7d2a7aabb385a661d">llvm::DomTreeBuilder::SemiNCAInfo&lt; DomTreeT &gt;::FindRoots</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/riscv/riscviseldagtodag-cpp/#ae0bac4d8677c9b1ee6a8626a4eca85d0">findVSplat</a>, <a href="/web-llvm/docs/api/structs/llvm/itaniumpartialdemangler/#a735b9eda5aeca00a01465c6fddd48c72">llvm::ItaniumPartialDemangler::finishDemangle</a>, <a href="/web-llvm/docs/api/structs/anonymous-minidumpyaml-cpp-/fixedsizehex/#af3af37b9bea8a378855a3a6fb97ab825">anonymous{MinidumpYAML.cpp}::FixedSizeHex&lt; N &gt;::FixedSizeHex</a>, <a href="/web-llvm/docs/api/structs/anonymous-minidumpyaml-cpp-/fixedsizestring/#ad657282b43fd1aa70b95916cebd4e9f8">anonymous{MinidumpYAML.cpp}::FixedSizeString&lt; N &gt;::FixedSizeString</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/x86/x86isellowering-cpp/#a58bbff4d7e32f5dd0824bc62f221d7a6">FixupMMXIntrinsicTypes</a>, <a href="/web-llvm/docs/api/classes/llvm/selectiondag/flaginserter/#aacad7387e8ea850a46bec5dd8a52f7e2">llvm::SelectionDAG::FlagInserter::FlagInserter</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/amdgpuisellowering-cpp/#a8111b84f0dcd25b744149232b17d8216">fnegFoldsIntoOp</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64isellowering-cpp/#ab43491efca0a534410c1dcece99f2949">foldADCToCINC</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/powerpc/ppciseldagtodag-cpp/#a2a73ac8be22cfe2a7d10fd13e70d57e1">foldADDIForFasterLocalAccesses</a>, <a href="/web-llvm/docs/api/files/lib/lib/codegen/lib/codegen/selectiondag/dagcombiner-cpp/#ae200e029e03b0fdac2427ee3811e24c5">foldAddSubBoolOfMaskedVal</a>, <a href="/web-llvm/docs/api/files/lib/lib/codegen/lib/codegen/selectiondag/dagcombiner-cpp/#a6ff9876b9195d71118f24729147be47a">foldAddSubOfSignBit</a>, <a href="/web-llvm/docs/api/files/lib/lib/codegen/lib/codegen/selectiondag/dagcombiner-cpp/#a5f0becba6abfe541dd2df2475c52268f">foldAndToUsubsat</a>, <a href="/web-llvm/docs/api/files/lib/lib/codegen/lib/codegen/selectiondag/dagcombiner-cpp/#a14b615dc096b20886abef65f8491e1ed">foldBitOrderCrossLogicOp</a>, <a href="/web-llvm/docs/api/files/lib/lib/codegen/lib/codegen/selectiondag/dagcombiner-cpp/#afd003bf0bf59d030e193b0772500ef66">foldBoolSelectToLogic</a>, <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/utils/simplifycfg-cpp/#ac0fb2da7eaa616e8ef8a8f52b981334b">foldCondBranchOnValueKnownInPredecessorImpl</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64isellowering-cpp/#a05c0c5cfbf4e57361a98212ee977ee01">foldCSELofCTTZ</a>, <a href="/web-llvm/docs/api/files/lib/lib/codegen/lib/codegen/selectiondag/dagcombiner-cpp/#ad191ffcc7522367aaecb263b8d149717">foldExtendedSignBitTest</a>, <a href="/web-llvm/docs/api/files/lib/lib/codegen/lib/codegen/selectiondag/dagcombiner-cpp/#a41d90ad30eef03eda7c41e46c1839ded">foldExtendVectorInregToExtendOfSubvector</a>, <a href="/web-llvm/docs/api/files/lib/lib/codegen/lib/codegen/selectiondag/dagcombiner-cpp/#a65dff372171f9d4e3e07a272214fb94d">foldExtractSubvectorFromShuffleVector</a>, <a href="/web-llvm/docs/api/files/lib/lib/codegen/lib/codegen/selectiondag/dagcombiner-cpp/#a904fa902f773c900d99c77af2da331c1">foldFPToIntToFP</a>, <a href="/web-llvm/docs/api/classes/llvm/amdgputargetlowering/#a98d5db97af4726044d334c4a21cc9bd2">llvm::AMDGPUTargetLowering::foldFreeOpFromSelect</a>, <a href="/web-llvm/docs/api/classes/llvm/scev/#ae29da85cd2dc185164c105e98fb7ec58">llvm::SCEV::FoldingSetTrait&lt; SCEV &gt;</a>, <a href="/web-llvm/docs/api/files/lib/lib/codegen/lib/codegen/selectiondag/dagcombiner-cpp/#a9940526e89938ffd29ad3135da3e2f7d">FoldIntToFPToInt</a>, <a href="/web-llvm/docs/api/files/lib/lib/codegen/lib/codegen/selectiondag/dagcombiner-cpp/#af911317e022ca63b9987c011c8e9a21b">foldLogicOfShifts</a>, <a href="/web-llvm/docs/api/files/lib/lib/codegen/lib/codegen/selectiondag/dagcombiner-cpp/#a4641b5e45848c460382fd60729bb5fe5">foldLogicTreeOfShifts</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/x86/x86iseldagtodag-cpp/#a09f3458b3e8eb96daed7a85d0635ac5d">foldMaskAndShiftToExtract</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/x86/x86iseldagtodag-cpp/#a06857829ce5f8610c6c44e45545212f4">foldMaskAndShiftToScale</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/x86/x86iseldagtodag-cpp/#a39d45c56475783e16bb465d63ff69a4c">foldMaskedShiftToBEXTR</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/x86/x86iseldagtodag-cpp/#abd6222456e5e712ccfdebd0c9182efb6">foldMaskedShiftToScaledMask</a>, <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/aggressiveinstcombine/aggressiveinstcombine-cpp/#a4e1612deb487473177dba9b03302386c">foldMemChr</a>, <a href="/web-llvm/docs/api/files/lib/lib/codegen/lib/codegen/selectiondag/dagcombiner-cpp/#aebf90edce984948502ad1606b3013417">foldSelectOfConstantsUsingSra</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/riscv/riscvisellowering-cpp/#a6aa5a20ccba4eafeded8c21562b71918">foldSelectOfCTTZOrCTLZ</a>, <a href="/web-llvm/docs/api/files/lib/lib/codegen/lib/codegen/selectiondag/dagcombiner-cpp/#a5471819ce50cdde6d7ebc70977179250">foldSelectWithIdentityConstant</a>, <a href="/web-llvm/docs/api/files/lib/lib/codegen/lib/codegen/selectiondag/dagcombiner-cpp/#a99e3727e5ff5a1c45d0ee6dfb697308a">foldSubCtlzNot</a>, <a href="/web-llvm/docs/api/files/lib/lib/codegen/lib/codegen/selectiondag/dagcombiner-cpp/#a98bf352a29693de3c4292f15ee698d79">foldToSaturated</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64isellowering-cpp/#af28deaf5887a7f186a2012df2bf82752">foldTruncStoreOfExt</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64isellowering-cpp/#aa8e7d7856b86905a5ce055fb23d0c9b2">foldVectorXorShiftIntoCmp</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/x86/x86isellowering-cpp/#a4f80d4b8b70f58b247193379a39d5541">foldVectorXorShiftIntoCmp</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/sifixsgprcopies-cpp/#a561542857883d396fc0c5dc9a1de342f">foldVGPRCopyIntoRegSequence</a>, <a href="/web-llvm/docs/api/files/lib/lib/codegen/lib/codegen/selectiondag/dagcombiner-cpp/#ae0975a935b1b17c1591b86a7bbf8e692">foldVSelectToSignBitSplatMask</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/x86/x86isellowering-cpp/#adb73c9adac12d432923cc883aa607798">foldXor1SetCC</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/x86/x86isellowering-cpp/#a974687eecfd14705774360c10e1c731a">foldXorTruncShiftIntoCmp</a>, <a href="/web-llvm/docs/api/classes/llvm/codeview/typecollection/#a93c8fc98bf04894bafc99e7869fa35e8">llvm::codeview::TypeCollection::ForEachRecord</a>, <a href="/web-llvm/docs/api/structs/llvm/format-provider-ecaa20ba3297bf1600b082fe1fca61e7/#a1e190076f44d99f68be134785ae5ad3b">llvm::format_provider&lt; T, std::enable_if_t&lt; support::detail::use_string_formatter&lt; T &gt;::value &gt; &gt;::format</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a0891783364de54e1128f37fdbc01e8b1">llvm::format_decimal</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a90c017a4d672e046b7e98f67edf082ec">llvm::format_hex</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a90c1e29256284cbb6ab1c31bfcdf7770">llvm::format_hex_no_prefix</a>, <a href="/web-llvm/docs/api/files/lib/lib/support/nativeformatting-cpp/#a30359c490796c080d15ae73cac5189ff">format_to_buffer</a>, <a href="/web-llvm/docs/api/classes/llvm/irsimilarity/irsimilaritycandidate/#ae9c1194a6f6117d8fb7c77e42b70f048">llvm::IRSimilarity::IRSimilarityCandidate::fromCanonicalNum</a>, <a href="/web-llvm/docs/api/structs/llvm/sys/unicode/node/#a49c7c7cf7d7086c3469e4d7ee2486f32">llvm::sys::unicode::Node::fullName</a>, <a href="/web-llvm/docs/api/structs/llvm/gsym/functioninfo/#adcf53d0ab35bb53a0ca5d71fb6c79b71">llvm::gsym::FunctionInfo::FunctionInfo</a>, <a href="/web-llvm/docs/api/classes/llvm/gcovblock/#a3a9468c2de2a4800fccd2a556a380996">llvm::GCOVBlock::GCOVBlock</a>, <a href="/web-llvm/docs/api/structs/llvm/gcroot/#a03ee8bfa8da13b01fb3a2b0d76bdbafe">llvm::GCRoot::GCRoot</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/powerpc/ppcisellowering-cpp/#a1f3670e08c57a95d0a5d9e442d9f322f">generateEquivalentSub</a>, <a href="/web-llvm/docs/api/namespaces/llvm/loongarchmatint/#a1e8bf674882ab22f3fa510916fab18fe">llvm::LoongArchMatInt::generateInstSeq</a>, <a href="/web-llvm/docs/api/structs/false/gepnode/#a72f317f6475e2e596a1e7881c0db322b">false::GepNode::GepNode</a>, <a href="/web-llvm/docs/api/classes/llvm/arrayrecycler/capacity/#ab52c84454e451fabe417985306501afb">llvm::ArrayRecycler&lt; T, Align &gt;::Capacity::get</a>, <a href="/web-llvm/docs/api/structs/llvm/idfcalculatordetail/childrengetterty/#a5f1b15474259d49fb4668ce85d797ab8">llvm::IDFCalculatorDetail::ChildrenGetterTy&lt; NodeTy, IsPostDom &gt;::get</a>, <a href="/web-llvm/docs/api/structs/llvm/idfcalculatordetail/childrengetterty-48c513751fec59f894901b1a7a36caad/#a22d6c86bce34c03d338ad002bba82885">llvm::IDFCalculatorDetail::ChildrenGetterTy&lt; BasicBlock, IsPostDom &gt;::get</a>, <a href="/web-llvm/docs/api/classes/llvm/lazycallgraph/#ad03c103c6345a262195c485df88d2a21">llvm::LazyCallGraph::get</a>, <a href="/web-llvm/docs/api/classes/llvm/scalednumber/#a643e49ec18ba075b047b4bbc026f4774">llvm::ScaledNumber&lt; uint64_t &gt;::get</a>, <a href="/web-llvm/docs/api/namespaces/llvm/ppc/#a1a14301103c8d97e52ed0ca117ea6b65">llvm::PPC::get_VSPLTI_elt</a>, <a href="/web-llvm/docs/api/classes/llvm/mipstargetlowering/#a3f5a81ea3f95a4119d6c0a5b5b2f5c49">llvm::MipsTargetLowering::getAddrGlobal</a>, <a href="/web-llvm/docs/api/classes/llvm/mipstargetlowering/#a5ccaa648716b2c4c8e0687f36e6c9fa2">llvm::MipsTargetLowering::getAddrGlobalLargeGOT</a>, <a href="/web-llvm/docs/api/classes/llvm/mipstargetlowering/#a1c44aab19fd4cd86f04d2dcc45062b25">llvm::MipsTargetLowering::getAddrGPRel</a>, <a href="/web-llvm/docs/api/classes/llvm/mipstargetlowering/#aa5e1d1788ef2fee23b0f9542eda5c1b6">llvm::MipsTargetLowering::getAddrLocal</a>, <a href="/web-llvm/docs/api/classes/llvm/mipstargetlowering/#a80d7b6f8225e03c0e2b80249cca5bd85">llvm::MipsTargetLowering::getAddrNonPIC</a>, <a href="/web-llvm/docs/api/classes/llvm/mipstargetlowering/#a272d1bf276d97a177b681f465129fe56">llvm::MipsTargetLowering::getAddrNonPICSym64</a>, <a href="/web-llvm/docs/api/classes/llvm/selectiondag/#a0ebd1bad63f0443b8329ac6a0c2a0ea6">llvm::SelectionDAG::getAddrSpaceCast</a>, <a href="/web-llvm/docs/api/structs/llvm/rdf/liveness/#a0c3a1721c534dbc63fdc081a9365fd9c">llvm::rdf::Liveness::getAllReachingDefs</a>, <a href="/web-llvm/docs/api/namespaces/llvm/offloading/amdgpu/#a658b1211d163ef9492d062d29de98201">llvm::offloading::amdgpu::getAMDGPUMetaDataFromImage</a>, <a href="/web-llvm/docs/api/files/lib/lib/object/machoobjectfile-cpp/#a8e5744e3da3116ce5eaf50660b88d6aa">getArray</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/spirv/spirvinstructionselector-cpp/#af999ef1c23f3644af392a2b4633fa8f7">getArrayComponentCount</a>, <a href="/web-llvm/docs/api/classes/llvm/msgpack/document/#a6e361fdc7f6a0c9dd44e46c0f020b46e">llvm::msgpack::Document::getArrayNode</a>, <a href="/web-llvm/docs/api/structs/llvm/yaml/polymorphictraits-19e5dd52fbbf83432f2ef10bff306b26/#aa519732ff23e8520549fee84f37604b3">llvm::yaml::PolymorphicTraits&lt; DocNode &gt;::getAsMap</a>, <a href="/web-llvm/docs/api/files/lib/lib/codegen/lib/codegen/selectiondag/dagcombiner-cpp/#ab5b54d45299d6e1868bfa6ef6b9b389f">getAsNonOpaqueConstant</a>, <a href="/web-llvm/docs/api/structs/llvm/yaml/polymorphictraits-19e5dd52fbbf83432f2ef10bff306b26/#aae064906988fb422c4c635cc83838c58">llvm::yaml::PolymorphicTraits&lt; DocNode &gt;::getAsScalar</a>, <a href="/web-llvm/docs/api/structs/llvm/yaml/polymorphictraits-19e5dd52fbbf83432f2ef10bff306b26/#a7d3fc2ef4c1c0c0117dea3acb6e5f117">llvm::yaml::PolymorphicTraits&lt; DocNode &gt;::getAsSequence</a>, <a href="/web-llvm/docs/api/classes/llvm/selectiondag/#a3b1a609daab06e074288990116f07dc0">llvm::SelectionDAG::getAssertAlign</a>, <a href="/web-llvm/docs/api/classes/llvm/json/value/#a301212abff5fea007dc2f1ba139ad63b">llvm::json::Value::getAsUINT64</a>, <a href="/web-llvm/docs/api/classes/llvm/selectiondag/#a1a1f2f01c1eb849390f448f90643c6ff">llvm::SelectionDAG::getAtomic</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/siisellowering-cpp/#ac6474b668c69198fbe7757e43f1e9bc7">getBasePtrIndex</a>, <a href="/web-llvm/docs/api/classes/llvm/selectiondag/#a9bcd28463c35c990c4bc354b0ec70fb8">llvm::SelectionDAG::getBasicBlock</a>, <a href="/web-llvm/docs/api/classes/llvm/selectiondag/#ab11ccb1e74242d4ba6e43373e3c4800c">llvm::SelectionDAG::getBlockAddress</a>, <a href="/web-llvm/docs/api/classes/llvm/machinefunction/#a81e8ccd82f750cdfb7488a3197401f7e">llvm::MachineFunction::getBlockNumbered</a>, <a href="/web-llvm/docs/api/classes/llvm/sandboxir/schedbundle/#a0dda45551d702439204dbc2ef32eade7">llvm::sandboxir::SchedBundle::getBot</a>, <a href="/web-llvm/docs/api/namespaces/anonymous-buildid-cpp-/#a10d49947a1b089d5ee06458bf8252a37">anonymous{BuildID.cpp}::getBuildID</a>, <a href="/web-llvm/docs/api/files/lib/lib/codegen/lib/codegen/selectiondag/dagcombiner-cpp/#a0ec0f119c981933406115e98aee243af">getBuildPairElt</a>, <a href="/web-llvm/docs/api/classes/llvm/edgebundles/#a82ab46612904a1a2bbacf62facbfc306">llvm::EdgeBundles::getBundle</a>, <a href="/web-llvm/docs/api/classes/llvm/irsimilarity/irsimilaritycandidate/#ae6b404a6e77e0349378afa8ae7ce0e4a">llvm::IRSimilarity::IRSimilarityCandidate::getCanonicalNum</a>, <a href="/web-llvm/docs/api/classes/llvm/x86ttiimpl/#a8728267f1d12f3c91b61da0187e4be7d">llvm::X86TTIImpl::getCastInstrCost</a>, <a href="/web-llvm/docs/api/classes/llvm/object/machoobjectfile/#a766c3350d64dde8af24ef7b600b11185">llvm::object::MachOObjectFile::getChainedFixupsSegments</a>, <a href="/web-llvm/docs/api/classes/llvm/pdb/nativeenumglobals/#ab9c9c1cc0ce67bb7e180cd6e3578021a">llvm::pdb::NativeEnumGlobals::getChildAtIndex</a>, <a href="/web-llvm/docs/api/classes/llvm/pdb/nativeenuminjectedsources/#a752b4bca0c8cc4f4cd97b592c1c44cb5">llvm::pdb::NativeEnumInjectedSources::getChildAtIndex</a>, <a href="/web-llvm/docs/api/classes/llvm/pdb/nativeenumlinenumbers/#a789f565ba934856e31431595664be79b">llvm::pdb::NativeEnumLineNumbers::getChildAtIndex</a>, <a href="/web-llvm/docs/api/classes/llvm/pdb/nativeenummodules/#af12000237b9f7f771a29a7c2d14c43ac">llvm::pdb::NativeEnumModules::getChildAtIndex</a>, <a href="/web-llvm/docs/api/classes/llvm/pdb/nativeenumsymbols/#aa23c53785d14b528f0fd4c8aba3c72c8">llvm::pdb::NativeEnumSymbols::getChildAtIndex</a>, <a href="/web-llvm/docs/api/classes/llvm/pdb/nativeenumtypes/#a3ccd20a2047d49e0c81fd7e42276211b">llvm::pdb::NativeEnumTypes::getChildAtIndex</a>, <a href="/web-llvm/docs/api/structs/llvm/domtreebuilder/semincainfo/#a0451f2d011f81c6f8ca840004a66c3fd">llvm::DomTreeBuilder::SemiNCAInfo&lt; DomTreeT &gt;::getChildren</a>, <a href="/web-llvm/docs/api/structs/llvm/domtreebuilder/semincainfo/#a3314013831ea1df71a5408ee6ac032e1">llvm::DomTreeBuilder::SemiNCAInfo&lt; DomTreeT &gt;::getChildren</a>, <a href="/web-llvm/docs/api/classes/llvm/graphdiff/#a7c6bfaa2b8d3dbf6f4c9f4dfec66c77d">llvm::GraphDiff&lt; MachineBasicBlock *, false &gt;::getChildren</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/nvptx/nvptxiseldagtodag-cpp/#a0ab9f5d7a4da7c32c7047da3d08c0f22">getCodeAddrSpace</a>, <a href="/web-llvm/docs/api/files/lib/lib/codegen/lib/codegen/selectiondag/dagcombiner-cpp/#a1a1520cd1b820feaac1e8b14b1ef360d">getCombineLoadStoreParts</a>, <a href="/web-llvm/docs/api/classes/llvm/selectiondag/#ad3db19b21e25af9ac5a1e514443b3d60">llvm::SelectionDAG::getCondCode</a>, <a href="/web-llvm/docs/api/classes/llvm/selectiondag/#a5fda84b4862d7e084fa4fa2cede8e37f">llvm::SelectionDAG::getConstant</a>, <a href="/web-llvm/docs/api/classes/llvm/selectiondag/#ad1ed10076dcd144800421886c7caea42">llvm::SelectionDAG::getConstantFP</a>, <a href="/web-llvm/docs/api/classes/llvm/selectiondag/#a22c327ddfcb98f911f3197180981f41e">llvm::SelectionDAG::getConstantPool</a>, <a href="/web-llvm/docs/api/classes/llvm/selectiondag/#a0c98ec1a456fb81eed1d51d987b156d1">llvm::SelectionDAG::getConstantPool</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a7d0bd64cc62d5027ed1040472fbb5fe6">llvm::getConstantValue</a>, <a href="/web-llvm/docs/api/classes/llvm/legacy/functionpassmanagerimpl/#a257ad4665a2a3c1c521dbbdc5f9c5882">llvm::legacy::FunctionPassManagerImpl::getContainedManager</a>, <a href="/web-llvm/docs/api/classes/llvm/legacy/passmanagerimpl/#aa361fb3ab0c9da9975f3df18f57e2d5a">llvm::legacy::PassManagerImpl::getContainedManager</a>, <a href="/web-llvm/docs/api/classes/anonymous-callgraphsccpass-cpp-/cgpassmanager/#a4b1bfae8468f5272b17dbfa99b21d8cf">anonymous{CallGraphSCCPass.cpp}::CGPassManager::getContainedPass</a>, <a href="/web-llvm/docs/api/classes/anonymous-legacypassmanager-cpp-/mppassmanager/#a304af141af26777cf00f13742ebb8bd8">anonymous{LegacyPassManager.cpp}::MPPassManager::getContainedPass</a>, <a href="/web-llvm/docs/api/classes/llvm/fppassmanager/#a76beb9efcf5d12a8fbe116ee2b8f56f0">llvm::FPPassManager::getContainedPass</a>, <a href="/web-llvm/docs/api/classes/llvm/lppassmanager/#aec82063d9514c697c7a721f257740646">llvm::LPPassManager::getContainedPass</a>, <a href="/web-llvm/docs/api/classes/llvm/rgpassmanager/#a41d8be8eb594fafcec7d5f06630783e5">llvm::RGPassManager::getContainedPass</a>, <a href="/web-llvm/docs/api/classes/llvm/selectiondag/#a155ffe05aa8e1991b486a7f96ff2e828">llvm::SelectionDAG::getCopyToReg</a>, <a href="/web-llvm/docs/api/classes/llvm/selectiondag/#a7c3f57225b086beb519a28087b4c2d3f">llvm::SelectionDAG::getCopyToReg</a>, <a href="/web-llvm/docs/api/classes/llvm/selectiondag/#a7244306a62d6e9858ef3b1be958f9740">llvm::SelectionDAG::getCopyToReg</a>, <a href="/web-llvm/docs/api/classes/llvm/scheduledagsdnodes/#a0923f09dc063b0d957449c45c562ca08">llvm::ScheduleDAGSDNodes::getCustomGraphFeatures</a>, <a href="/web-llvm/docs/api/classes/llvm/selectiondag/#af1b7de0f063606a3701944a0db6dab1e">llvm::SelectionDAG::getDbgValue</a>, <a href="/web-llvm/docs/api/classes/llvm/anonymous-amdgpusplitmodule-cpp-/splitgraph/node/#a853692dee5306a0d1c6ddafc53e954dd">llvm::anonymous{AMDGPUSplitModule.cpp}::SplitGraph::Node::getDependencies</a>, <a href="/web-llvm/docs/api/classes/llvm/dominatortreebase/#a406e4a6b7277aab7efd423ae30a9fb12">llvm::DominatorTreeBase&lt; BlockT, false &gt;::getDescendants</a>, <a href="/web-llvm/docs/api/classes/llvm/cl/generic-parser-base/#a0a13f1c3a1e86dedae65b2753b765798">llvm::cl::generic_parser_base::getDescription</a>, <a href="/web-llvm/docs/api/classes/llvm/cl/parser/#a97f353f2806e7db43cfb966150b99a1c">llvm::cl::parser&lt; DataType &gt;::getDescription</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/arm/armisellowering-cpp/#a8fb36df786ff6728049d25647092c350">getDivRemArgList</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/arm/armisellowering-cpp/#a5c6c520681b64fb03687d290b17f6e83">getDivRemLibcall</a>, <a href="/web-llvm/docs/api/classes/llvm/mipstargetlowering/#a77a87423f2a96adea15f67141ced40bc">llvm::MipsTargetLowering::getDllimportSymbol</a>, <a href="/web-llvm/docs/api/classes/llvm/mipstargetlowering/#a5f41eccd0b382684fdb89443c0c54a99">llvm::MipsTargetLowering::getDllimportVariable</a>, <a href="/web-llvm/docs/api/structs/llvm/bfidotgraphtraitsbase/#ac3fd4c945029b6ece24a347676056f86">llvm::BFIDOTGraphTraitsBase&lt; BlockFrequencyInfo, BranchProbabilityInfo &gt;::getEdgeAttributes</a>, <a href="/web-llvm/docs/api/structs/llvm/dotgraphtraits-8931387ba2ad73814dea2f707c6d1e07/#a133b818a82415809a3aff114db56f4af">llvm::DOTGraphTraits&lt; SplitGraph &gt;::getEdgeAttributes</a>, <a href="/web-llvm/docs/api/classes/llvm/structtype/#aee3c78d73273cb8449cd10cc15edcb83">llvm::StructType::getElementType</a>, <a href="/web-llvm/docs/api/classes/llvm/msgpack/document/#a58d0878f182d83be836a4081448a16b1">llvm::msgpack::Document::getEmptyNode</a>, <a href="/web-llvm/docs/api/files/lib/lib/debuginfo/lib/debuginfo/codeview/typeindexdiscovery-cpp/#a8fa7e42c07f77ffbc093d9f6b80a36af">getEncodedIntegerLength</a>, <a href="/web-llvm/docs/api/namespaces/llvm/amdgpu/#a2ee72f856a2116efe64cf999f14f277d">llvm::AMDGPU::getEncodingFromOperandTable</a>, <a href="/web-llvm/docs/api/structs/anonymous-structurizecfg-cpp-/subgraphtraits/#ad3649381b603017749af04afd7e762f7">anonymous{StructurizeCFG.cpp}::SubGraphTraits::getEntryNode</a>, <a href="/web-llvm/docs/api/structs/llvm/domtreegraphtraitsbase/#a23602a8d9a56747cb6f0a75903ba762e">llvm::DomTreeGraphTraitsBase&lt; Node, ChildIterator &gt;::getEntryNode</a>, <a href="/web-llvm/docs/api/structs/llvm/graphtraits-c4751382d4709c00c1c1d640bb60c43b/#ae32580f5a131b9b7f57c341ec8849d3d">llvm::GraphTraits&lt; const DDGNode * &gt;::getEntryNode</a>, <a href="/web-llvm/docs/api/structs/llvm/graphtraits-34ad45e92d8eecd133e6e79591f93716/#af5dc12892045b07f84160a1b9d6c63be">llvm::GraphTraits&lt; const VPBlockBase * &gt;::getEntryNode</a>, <a href="/web-llvm/docs/api/structs/llvm/graphtraits-60fe2955c1f6971c9465484c526709fc/#af649fd1d5c912431283409f2f85fe601">llvm::GraphTraits&lt; DDGNode * &gt;::getEntryNode</a>, <a href="/web-llvm/docs/api/structs/llvm/graphtraits-4eb58d9bcb360b0c1dcb042151ab7b36/#ae749ba26fb7d63fa14bec6353c265e80">llvm::GraphTraits&lt; Inverse&lt; MemoryAccess * &gt; &gt;::getEntryNode</a>, <a href="/web-llvm/docs/api/structs/llvm/graphtraits-a2008b5f8b21ce1ff8289baaf7093f8a/#afe5a164a07f9f8736dee0f9e90415d0b">llvm::GraphTraits&lt; LazyCallGraph * &gt;::getEntryNode</a>, <a href="/web-llvm/docs/api/structs/llvm/graphtraits-0ea52d7b93b4cfe134cbdc75e8ba07b0/#a0ba8b6a10a63e39150430506eae496b2">llvm::GraphTraits&lt; LazyCallGraph::Node * &gt;::getEntryNode</a>, <a href="/web-llvm/docs/api/structs/llvm/graphtraits-0dc1828882f98769279a0fe7f513a40d/#ab16708d338f23228b1fc3a863cb971b6">llvm::GraphTraits&lt; MemoryAccess * &gt;::getEntryNode</a>, <a href="/web-llvm/docs/api/structs/llvm/graphtraits-404b5b8ef0c47cc568060468de8cfca6/#a609e29697e2a8090c32dd8f931e58f26">llvm::GraphTraits&lt; SDNode * &gt;::getEntryNode</a>, <a href="/web-llvm/docs/api/structs/llvm/graphtraits-8931387ba2ad73814dea2f707c6d1e07/#a10425aae522a7705b9a03316dc9c3c1b">llvm::GraphTraits&lt; SplitGraph &gt;::getEntryNode</a>, <a href="/web-llvm/docs/api/structs/llvm/graphtraits-8cbcf8b9166a6c46f5d7e91ca6470b24/#ae3935878ba40a9b866d5ab0acc132db4">llvm::GraphTraits&lt; SUnit * &gt;::getEntryNode</a>, <a href="/web-llvm/docs/api/structs/llvm/graphtraits-ac66d4b8671a287a0a0e312ee17ee28d/#a5bceaaf742342c46b91e8fff03fe4786">llvm::GraphTraits&lt; VPBlockBase * &gt;::getEntryNode</a>, <a href="/web-llvm/docs/api/structs/llvm/graphtraits-d394e565666085640be20f1e64fdd72b/#af2ac1cd90c04788fc5e356c7ef89c9c0">llvm::GraphTraits&lt; VPBlockDeepTraversalWrapper&lt; const VPBlockBase * &gt; &gt;::getEntryNode</a>, <a href="/web-llvm/docs/api/structs/llvm/graphtraits-9ac678cba1b93dbde91361363a8c8a8e/#a3f92cc63126efa4835b782d4dcedf1e2">llvm::GraphTraits&lt; VPBlockDeepTraversalWrapper&lt; VPBlockBase * &gt; &gt;::getEntryNode</a>, <a href="/web-llvm/docs/api/structs/llvm/graphtraits-363fa89642305612e9e0e66792192abb/#ade13f748b737f3f9069b3f13ed5defe5">llvm::GraphTraits&lt; VPBlockShallowTraversalWrapper&lt; const VPBlockBase * &gt; &gt;::getEntryNode</a>, <a href="/web-llvm/docs/api/structs/llvm/graphtraits-0bf1ef93d28481823f2981c5bb514c9c/#a02fcd3e7d887c5e2917ca421e0839f89">llvm::GraphTraits&lt; VPBlockShallowTraversalWrapper&lt; VPBlockBase * &gt; &gt;::getEntryNode</a>, <a href="/web-llvm/docs/api/structs/llvm/graphtraits-d1ba9f3b34b3379086b936f68d22486f/#a86b09b531afcb39718629d845110241d">llvm::GraphTraits&lt; VPlan * &gt;::getEntryNode</a>, <a href="/web-llvm/docs/api/structs/llvm/machinedomtreegraphtraitsbase/#a9e0f96c892da58c3badac54c20ac8506">llvm::MachineDomTreeGraphTraitsBase&lt; Node, ChildIterator &gt;::getEntryNode</a>, <a href="/web-llvm/docs/api/classes/llvm/basicttiimplbase/#a57c818fa46b39f5b70d629087c58b38c">llvm::BasicTTIImplBase&lt; BasicTTIImpl &gt;::getEstimatedNumberOfCaseClusters</a>, <a href="/web-llvm/docs/api/files/lib/lib/codegen/lib/codegen/selectiondag/legalizeintegertypes-cpp/#a9a211c813c62230abc28ef3db4e34dc4">getExtendForIntVecReduction</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64iseldagtodag-cpp/#ae579b3dcf2613ef548aa1c6bfe50cdc9">getExtendTypeForNode</a>, <a href="/web-llvm/docs/api/classes/llvm/selectiondag/#aa8f1c26a4e070ead6c67b4e9a5d93124">llvm::SelectionDAG::getExternalSymbol</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/x86/x86isellowering-cpp/#a1749d6a76a90f1117d344826f3e1e428">getExtractedDemandedElts</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/x86/x86isellowering-cpp/#a4fc43ca790e9a82ad51249f2e93d2e17">getFauxShuffleMask</a>, <a href="/web-llvm/docs/api/files/lib/lib/object/archive-cpp/#a896c0342b10ed46345456bd263e5a7ae">getFieldRawString</a>, <a href="/web-llvm/docs/api/classes/llvm/baserecord/#abf942435da1f972e2439a84be56a04de">llvm::BaseRecord::getFormattedName</a>, <a href="/web-llvm/docs/api/classes/llvm/clause/#adb3d803ae6c5db871313c6154409c8cd">llvm::Clause::getFormattedParserClassName</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a02499e257a12ac8ac5619925e036a928">llvm::getFpImmVal</a>, <a href="/web-llvm/docs/api/classes/llvm/scalednumber/#aa9197fa9f1d099911fdc5e355f51a7d2">llvm::ScaledNumber&lt; uint64_t &gt;::getFraction</a>, <a href="/web-llvm/docs/api/classes/llvm/selectiondag/#acb59cbd8f4a8c1cf820b2b540aebdac1">llvm::SelectionDAG::getFrameIndex</a>, <a href="/web-llvm/docs/api/structs/llvm/itaniumpartialdemangler/#a2effd15853bfffbeec4d08451f1fa81c">llvm::ItaniumPartialDemangler::getFunctionBaseName</a>, <a href="/web-llvm/docs/api/classes/llvm/indexedinstrprofreader/#a2d771e664c8cbfcf4ed1e5a51d052b29">llvm::IndexedInstrProfReader::getFunctionBitmap</a>, <a href="/web-llvm/docs/api/structs/llvm/itaniumpartialdemangler/#aea51879b3b2822d1c0f74c71cff9bc2e">llvm::ItaniumPartialDemangler::getFunctionDeclContextName</a>, <a href="/web-llvm/docs/api/structs/llvm/itaniumpartialdemangler/#a483d97b0a650319638b62209a03b1dea">llvm::ItaniumPartialDemangler::getFunctionName</a>, <a href="/web-llvm/docs/api/structs/llvm/itaniumpartialdemangler/#a06d6bd09c85fc634502b4914843860a2">llvm::ItaniumPartialDemangler::getFunctionParameters</a>, <a href="/web-llvm/docs/api/structs/llvm/itaniumpartialdemangler/#abb17886e8b7123e706c1a207402c179f">llvm::ItaniumPartialDemangler::getFunctionReturnType</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#acfed5678d22df4ce259fa0f83075a410">llvm::getGatherScatterIndex</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a1f3aeccd734488eddcb632f9bb706f0a">llvm::getGatherScatterScale</a>, <a href="/web-llvm/docs/api/classes/llvm/selectiondag/#a5bd5e426c197fd66ec0ac6f088d51185">llvm::SelectionDAG::getGatherVP</a>, <a href="/web-llvm/docs/api/classes/llvm/statepointopers/#a670096de4a32a058514ddba685ececfe">llvm::StatepointOpers::getGCPointerMap</a>, <a href="/web-llvm/docs/api/classes/llvm/selectiondag/#a3af6334751e0a4eaf2b2a253f545a861">llvm::SelectionDAG::getGetFPEnv</a>, <a href="/web-llvm/docs/api/classes/llvm/selectiondag/#a7ee632093c5fc25ca22faa353105aa74">llvm::SelectionDAG::getGlobalAddress</a>, <a href="/web-llvm/docs/api/classes/llvm/selectiondag/#aa2a05997ac6221b9ed571bedb4d5ef52">llvm::SelectionDAG::getGraphAttrs</a>, <a href="/web-llvm/docs/api/classes/llvm/scheduledagsdnodes/#a8cbdb500ba4abd11fd23de4e7a020a2d">llvm::ScheduleDAGSDNodes::getGraphNodeLabel</a>, <a href="/web-llvm/docs/api/files/lib/lib/support/scalednumber-cpp/#a96a8305eca90ffb97ef1ad6cbfa5c2c6">getHalf</a>, <a href="/web-llvm/docs/api/classes/llvm/scalednumberbase/#afa2af28321f8882ed9f3636b25ebe3e9">llvm::ScaledNumberBase::getHalf</a>, <a href="/web-llvm/docs/api/structs/llvm/diarglistinfo/#a73560112a95361ff58c8b9d6f5ce35b4">llvm::DIArgListInfo::getHashValue</a>, <a href="/web-llvm/docs/api/structs/llvm/mdnodeinfo/#a7e719c3488bdfc541805df6d154fadee">llvm::MDNodeInfo&lt; NodeTy &gt;::getHashValue</a>, <a href="/web-llvm/docs/api/files/lib/lib/analysis/blockfrequencyinfoimpl-cpp/#a7c993766c71555883cf7cf7a2d98dd51">getHexDigit</a>, <a href="/web-llvm/docs/api/classes/anonymous-loongarchmccodeemitter-cpp-/loongarchmccodeemitter/#af641c8f0bf20235b08fc10826724dc8a">anonymous{LoongArchMCCodeEmitter.cpp}::LoongArchMCCodeEmitter::getImmOpValueAsr</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a395742e71a25e79d294071a3d5eefc54">llvm::getImmVal</a>, <a href="/web-llvm/docs/api/classes/llvm/selectiondag/#aa4f17f756eb1cb25b572523363d9ddce">llvm::SelectionDAG::getIndexedStore</a>, <a href="/web-llvm/docs/api/classes/llvm/selectiondag/#aa34a22977f06d68f99eabea788b8d4fa">llvm::SelectionDAG::getIndexedStoreVP</a>, <a href="/web-llvm/docs/api/files/lib/lib/codegen/lib/codegen/selectiondag/dagcombiner-cpp/#a4fb41e4d2abb178c37b2a3615e36d877">getInputChainForNode</a>, <a href="/web-llvm/docs/api/classes/llvm/targetinstrinfo/#a86ea143f1ea40632ba851badcf377101">llvm::TargetInstrInfo::getInstrLatency</a>, <a href="/web-llvm/docs/api/classes/llvm/amdgpuregisterbankinfo/#abb21f77ed3dc15eb330b93b3efaa94ba">llvm::AMDGPURegisterBankInfo::getInstrMapping</a>, <a href="/web-llvm/docs/api/files/lib/lib/profiledata/instrprofcorrelator-cpp/#a7d13f4f140cc4980cb2e6fe4d404b7cd">getInstrProfSection</a>, <a href="/web-llvm/docs/api/classes/llvm/irbuilderbase/#a95df4f20c933779306b9a936b88b99a5">llvm::IRBuilderBase::getIntN</a>, <a href="/web-llvm/docs/api/classes/llvm/irbuilderbase/#a31e2db8d1b315202d2c19e711b5365fd">llvm::IRBuilderBase::getIntNTy</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64isellowering-cpp/#a62766c75f88612ffa652342472e755f6">getIntrinsicID</a>, <a href="/web-llvm/docs/api/classes/llvm/scalednumber/#adb991a4c5135143ac0df0563911af3c8">llvm::ScaledNumber&lt; uint64_t &gt;::getInverse</a>, <a href="/web-llvm/docs/api/classes/llvm/selectiondag/#ac4bd7bc0fe71acaa3df19a18384ac2d4">llvm::SelectionDAG::getJumpTable</a>, <a href="/web-llvm/docs/api/structs/llvm/yaml/polymorphictraits-19e5dd52fbbf83432f2ef10bff306b26/#a7333c7e58813461cdd1579bfc1dd3337">llvm::yaml::PolymorphicTraits&lt; DocNode &gt;::getKind</a>, <a href="/web-llvm/docs/api/classes/llvm/selectiondag/#a099ce58f978968532bb5de54ed2a4a8b">llvm::SelectionDAG::getLabelNode</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/riscv/riscvisellowering-cpp/#a93143c7c98a98f3712301e2d749e8205">getLargeExternalSymbol</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/riscv/riscvisellowering-cpp/#ae1b012e1db529fbfbeee6e863dfef7cc">getLargeGlobalAddress</a>, <a href="/web-llvm/docs/api/classes/llvm/selectiondag/#ad4283d9a650f42aafcff8b6cefc332a2">llvm::SelectionDAG::getLifetimeNode</a>, <a href="/web-llvm/docs/api/classes/llvm/selectiondag/#ab280576b46181ebb3a3716370169c287">llvm::SelectionDAG::getLoad</a>, <a href="/web-llvm/docs/api/classes/llvm/selectiondag/#ab517db4292565daf5cea12e127f9db87">llvm::SelectionDAG::getLoadVP</a>, <a href="/web-llvm/docs/api/classes/llvm/selectiondag/#a8b513ea04feca0cb2a87cfc8f543396c">llvm::SelectionDAG::getMachineNode</a>, <a href="/web-llvm/docs/api/classes/llvm/msgpack/document/#a47c7647f08d2672561d925ce3c291dd3">llvm::msgpack::Document::getMapNode</a>, <a href="/web-llvm/docs/api/classes/llvm/selectiondag/#a0bc0f0450beae61b3c7c3f110d3b7c5c">llvm::SelectionDAG::getMaskedGather</a>, <a href="/web-llvm/docs/api/classes/llvm/selectiondag/#a77eef56a45fec10f706e25be688f3beb">llvm::SelectionDAG::getMaskedHistogram</a>, <a href="/web-llvm/docs/api/classes/llvm/selectiondag/#af2a48350a921ca25a0939a82228555f4">llvm::SelectionDAG::getMaskedLoad</a>, <a href="/web-llvm/docs/api/classes/llvm/selectiondag/#aff2202a13bbfad20f9b5156fd930cf01">llvm::SelectionDAG::getMaskedScatter</a>, <a href="/web-llvm/docs/api/classes/llvm/selectiondag/#aa83e0455dcd3f0feb08e08ebb0a18db0">llvm::SelectionDAG::getMaskedStore</a>, <a href="/web-llvm/docs/api/namespaces/llvm/amdgpu/isainfo/#a2d0c61cd3e4d53626ffdb34031766f08">llvm::AMDGPU::IsaInfo::getMaxWorkGroupsPerCU</a>, <a href="/web-llvm/docs/api/classes/llvm/selectiondag/#ae78ec4c2d770f86bacd6b337e1bd80e5">llvm::SelectionDAG::getMCSymbol</a>, <a href="/web-llvm/docs/api/classes/llvm/selectiondag/#a82e2e151e4db313b8832505c9955b689">llvm::SelectionDAG::getMDNode</a>, <a href="/web-llvm/docs/api/files/lib/lib/ir/core-cpp/#aa4b48d750cec06b65003055986a16b40">getMDNodeOperandImpl</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#ac5da18dc4025a639cd5ecc7a288f9d31">llvm::getMDOperandAsType</a>, <a href="/web-llvm/docs/api/classes/llvm/selectiondag/#a6fc57a7458164a2086dfee32a82530db">llvm::SelectionDAG::getMemIntrinsicNode</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/x86/x86optimizeleas-cpp/#adec2d3df3feb3a9a4507803dc1da37db">getMemOpKey</a>, <a href="/web-llvm/docs/api/classes/anonymous-metadataloader-cpp-/bitcodereadermetadatalist/#a9d29998e353ecb9f57c17b956670e2ae">anonymous{MetadataLoader.cpp}::BitcodeReaderMetadataList::getMetadataIfResolved</a>, <a href="/web-llvm/docs/api/classes/llvm/slottracker/#a1544617174694910a83110368004236b">llvm::SlotTracker::getMetadataSlot</a>, <a href="/web-llvm/docs/api/files/lib/lib/bitcode/lib/bitcode/writer/valueenumerator-cpp/#a13f66ae95444da9ef82b094963dd2599">getMetadataTypeOrder</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/directx/lib/target/directx/dxilwriter/dxilvalueenumerator-cpp/#a13f66ae95444da9ef82b094963dd2599">getMetadataTypeOrder</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#aa860d116fc20fde892f7485b706f9139">llvm::getN1Bits</a>, <a href="/web-llvm/docs/api/classes/llvm/aliasscopenode/#aeaa6875f30bc562b0fd24805a5014c3b">llvm::AliasScopeNode::getName</a>, <a href="/web-llvm/docs/api/namespaces/llvm/amdgpu/#a89e90b3784550781a7cb87657a8b417f">llvm::AMDGPU::getNameFromOperandTable</a>, <a href="/web-llvm/docs/api/structs/llvm/rdf/liveness/#a186be9b537ac3f4112ac6ea3d610ddf3">llvm::rdf::Liveness::getNearestAliasedRef</a>, <a href="/web-llvm/docs/api/structs/llvm/ilist-detail/nodeaccess/#a857271e8093bd2a99308671822db3704">llvm::ilist_detail::NodeAccess::getNext</a>, <a href="/web-llvm/docs/api/structs/llvm/ilist-detail/nodeaccess/#a8e29f2bc27babeccb2efe89d478f2920">llvm::ilist_detail::NodeAccess::getNext</a>, <a href="/web-llvm/docs/api/classes/llvm/iplist-impl/#a6f54fd35f7c9d358c932ffc7ecf0ee3c">llvm::iplist_impl&lt; IntrusiveListT, TraitsT &gt;::getNextNode</a>, <a href="/web-llvm/docs/api/classes/llvm/iplist-impl/#a6894769acc2863b818d55193fc05e9fc">llvm::iplist_impl&lt; IntrusiveListT, TraitsT &gt;::getNextNode</a>, <a href="/web-llvm/docs/api/classes/anonymous-standardinstrumentations-cpp-/dotcfgdiff/#ab43ae9469499b43439fe55742a7c9749">anonymous{StandardInstrumentations.cpp}::DotCfgDiff::getNode</a>, <a href="/web-llvm/docs/api/classes/anonymous-standardinstrumentations-cpp-/dotcfgdiffdisplaygraph/#aae785e172383d1db142d127c139969e9">anonymous{StandardInstrumentations.cpp}::DotCfgDiffDisplayGraph::getNode</a>, <a href="/web-llvm/docs/api/classes/llvm/msgpack/document/#a6d5fb2463b89c95b17ffffcef9cf7f4e">llvm::msgpack::Document::getNode</a>, <a href="/web-llvm/docs/api/classes/llvm/msgpack/document/#a852305a31c763efece584325cb814441">llvm::msgpack::Document::getNode</a>, <a href="/web-llvm/docs/api/classes/llvm/msgpack/document/#a3bd41a83d5d273091ac8b9f5fd633197">llvm::msgpack::Document::getNode</a>, <a href="/web-llvm/docs/api/classes/llvm/msgpack/document/#aae058e5223d395e89d7f8a63a22f65f3">llvm::msgpack::Document::getNode</a>, <a href="/web-llvm/docs/api/classes/llvm/msgpack/document/#a7b94a260cad744fb7871a0ff6e15838f">llvm::msgpack::Document::getNode</a>, <a href="/web-llvm/docs/api/classes/llvm/msgpack/document/#af8e2909cdbfc27ac0ec2c2710b633300">llvm::msgpack::Document::getNode</a>, <a href="/web-llvm/docs/api/classes/llvm/msgpack/document/#a337d91aa41dbe0ed407a0cd267c3a208">llvm::msgpack::Document::getNode</a>, <a href="/web-llvm/docs/api/classes/llvm/msgpack/document/#a622493610a44dfcbba874f9fe7a5583b">llvm::msgpack::Document::getNode</a>, <a href="/web-llvm/docs/api/classes/llvm/msgpack/document/#a0ebb06f24a82047ec691bd8b1ccac4f3">llvm::msgpack::Document::getNode</a>, <a href="/web-llvm/docs/api/classes/llvm/selectiondag/#ab621643f2804cd6719d4703a21c98bb6">llvm::SelectionDAG::getNode</a>, <a href="/web-llvm/docs/api/classes/llvm/selectiondag/#a0d2d9c6df58f2916c90d15bc635d871f">llvm::SelectionDAG::getNode</a>, <a href="/web-llvm/docs/api/classes/llvm/selectiondag/#adeb0d426ab4200eab1a410d030706b29">llvm::SelectionDAG::getNode</a>, <a href="/web-llvm/docs/api/classes/llvm/selectiondag/#ae53e791e2762b79bf164fb1802e3292b">llvm::SelectionDAG::getNode</a>, <a href="/web-llvm/docs/api/classes/llvm/selectiondag/#af0507ced82bf0518fbfc3087f3417395">llvm::SelectionDAG::getNode</a>, <a href="/web-llvm/docs/api/classes/llvm/selectiondag/#a9bb4cbe0f2af3f9ba06c999baeb7736d">llvm::SelectionDAG::getNode</a>, <a href="/web-llvm/docs/api/classes/llvm/vecustomdag/#a24f2724c3180118c51af9b3fe77328f2">llvm::VECustomDAG::getNode</a>, <a href="/web-llvm/docs/api/classes/llvm/vecustomdag/#afd07a519f6f716dfb3649c99c3bf8fc2">llvm::VECustomDAG::getNode</a>, <a href="/web-llvm/docs/api/classes/llvm/vecustomdag/#a6bc77ff0f140f382784b468fb1b8f65e">llvm::VECustomDAG::getNode</a>, <a href="/web-llvm/docs/api/structs/llvm/bfidotgraphtraitsbase/#a1c78d4d6544b97f0fb4219ec8a99c54b">llvm::BFIDOTGraphTraitsBase&lt; BlockFrequencyInfo, BranchProbabilityInfo &gt;::getNodeAttributes</a>, <a href="/web-llvm/docs/api/structs/llvm/dotgraphtraits-8724e5f1194a63950ec2dad06d9bdf62/#a0af913c67e3a0ba5f5756489230c823c">llvm::DOTGraphTraits&lt; ScheduleDAG * &gt;::getNodeAttributes</a>, <a href="/web-llvm/docs/api/structs/llvm/dotgraphtraits-3e4d2beef0711eb028dcc7799677e405/#aeec5b7bbdeddc6e81486c44f34c5975a">llvm::DOTGraphTraits&lt; ScheduleDAGMI * &gt;::getNodeAttributes</a>, <a href="/web-llvm/docs/api/structs/llvm/dotgraphtraits-d331e4256d82fb2920257d4c75d8b96c/#aaf5fc67e7c5452f9b299c0bb1f0ca42b">llvm::DOTGraphTraits&lt; SelectionDAG * &gt;::getNodeAttributes</a>, <a href="/web-llvm/docs/api/structs/llvm/dotgraphtraits-8931387ba2ad73814dea2f707c6d1e07/#ac6e2e75e511fe00375f2fb76dbad96a8">llvm::DOTGraphTraits&lt; SplitGraph &gt;::getNodeAttributes</a>, <a href="/web-llvm/docs/api/structs/llvm/dotgraphtraits-8931387ba2ad73814dea2f707c6d1e07/#ac75b991ae8e00835c85133d3053fd581">llvm::DOTGraphTraits&lt; SplitGraph &gt;::getNodeDescription</a>, <a href="/web-llvm/docs/api/classes/llvm/immutablegraph/#a41c7e9ffbcfe3525fa5e59747d7ea6cd">llvm::ImmutableGraph&lt; MachineInstr *, int &gt;::getNodeIndex</a>, <a href="/web-llvm/docs/api/structs/llvm/dotgraphtraits-8931387ba2ad73814dea2f707c6d1e07/#ae037d99834a00c3729ea65eaf211f1e1">llvm::DOTGraphTraits&lt; SplitGraph &gt;::getNodeLabel</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a99ae9f9b511cb5dc402e9fcee10be7d8">llvm::getNodePassthru</a>, <a href="/web-llvm/docs/api/structs/llvm/ilist-detail/nodeaccess/#ab506fe3cbc7657c8a0542eca37f5b963">llvm::ilist_detail::NodeAccess::getNodePtr</a>, <a href="/web-llvm/docs/api/structs/llvm/ilist-detail/nodeaccess/#aa63b74819f4121b464578da5dc4513f5">llvm::ilist_detail::NodeAccess::getNodePtr</a>, <a href="/web-llvm/docs/api/structs/llvm/ilist-detail/specificnodeaccess/#a68e81a4edf8b66f5fee065da8485573e">llvm::ilist_detail::SpecificNodeAccess&lt; OptionsT &gt;::getNodePtr</a>, <a href="/web-llvm/docs/api/structs/llvm/ilist-detail/specificnodeaccess/#a947c7a10dde23fc41eb95013313dcb3f">llvm::ilist_detail::SpecificNodeAccess&lt; OptionsT &gt;::getNodePtr</a>, <a href="/web-llvm/docs/api/files/lib/lib/codegen/lib/codegen/selectiondag/scheduledagrrlist-cpp/#ad2c25d325740e477ec4a81b0c9dbfaa0">getNodeRegMask</a>, <a href="/web-llvm/docs/api/classes/llvm/abstractdependencegraphbuilder/#a05e33cd36780875465c50c22d1a85ddd">llvm::AbstractDependenceGraphBuilder&lt; GraphType &gt;::getNodesInPiBlock</a>, <a href="/web-llvm/docs/api/classes/llvm/ddgbuilder/#a9e4484d16aab57829b9d4b17d08ae959">llvm::DDGBuilder::getNodesInPiBlock</a>, <a href="/web-llvm/docs/api/files/lib/lib/ir/dibuilder-cpp/#a5db83448daa843198df6b3ee1cea066c">getNonCompileUnitScope</a>, <a href="/web-llvm/docs/api/classes/llvm/selectiondagbuilder/#a4ad02593716678add54090c344959750">llvm::SelectionDAGBuilder::getNonRegisterValue</a>, <a href="/web-llvm/docs/api/classes/llvm/emptymatchcontext/#a67dc70f91a2b8798e031073b8124cbe9">llvm::EmptyMatchContext::getNumOperands</a>, <a href="/web-llvm/docs/api/classes/llvm/sdpatternmatch/basicmatchcontext/#ae8780ee81e1a7c4c8246103747203214">llvm::SDPatternMatch::BasicMatchContext::getNumOperands</a>, <a href="/web-llvm/docs/api/classes/llvm/vpmatchcontext/#aefbf3140b6d37b3c71d839bd5a694bc8">llvm::VPMatchContext::getNumOperands</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/siinstrinfo-cpp/#ae6e6e83717666f42581170b4599cd238">getNumOperandsNoGlue</a>, <a href="/web-llvm/docs/api/classes/anonymous-lowermatrixintrinsics-cpp-/lowermatrixintrinsics/#a0a0644b7c29287b0ea96ec3524e092e4">anonymous{LowerMatrixIntrinsics.cpp}::LowerMatrixIntrinsics::getNumOps</a>, <a href="/web-llvm/docs/api/structs/llvm/instrprofrecord/#a5417f0221bfe56145cf78606995c5ec5">llvm::InstrProfRecord::getNumValueData</a>, <a href="/web-llvm/docs/api/namespaces/llvm/aarch64cc/#affed553a12fdb2f42041ea371820e01f">llvm::AArch64CC::getNZCVToSatisfyCondCode</a>, <a href="/web-llvm/docs/api/classes/llvm/gvnexpression/basicexpression/#add58d1e477664fe4b3d578e2b0dae405">llvm::GVNExpression::BasicExpression::getOperand</a>, <a href="/web-llvm/docs/api/classes/llvm/namedmdnode/#aa24b566603d206b0e74bf63daf521078">llvm::NamedMDNode::getOperand</a>, <a href="/web-llvm/docs/api/classes/llvm/vpuser/#a6e1b252a9bbdc1a440fb57a6257b97f4">llvm::VPUser::getOperand</a>, <a href="/web-llvm/docs/api/classes/llvm/bitcodeabbrev/#a99bd594ca88426eba9b6581d9f292766">llvm::BitCodeAbbrev::getOperandInfo</a>, <a href="/web-llvm/docs/api/namespaces/anonymous-nvptxiseldagtodag-cpp-/#a4b394d4c4aa365db793d44aa627bec7a">anonymous{NVPTXISelDAGToDAG.cpp}::getOperationOrderings</a>, <a href="/web-llvm/docs/api/classes/llvm/cl/generic-parser-base/#a385a22b9974e70c20f13c987d900957c">llvm::cl::generic_parser_base::getOption</a>, <a href="/web-llvm/docs/api/classes/llvm/cl/parser/#ad2188e344f0fa1595ff65422b173716d">llvm::cl::parser&lt; DataType &gt;::getOption</a>, <a href="/web-llvm/docs/api/classes/llvm/cl/generic-parser-base/#a2927c0ec3cabfb7f3524f4531cec21fb">llvm::cl::generic_parser_base::getOptionValue</a>, <a href="/web-llvm/docs/api/classes/llvm/cl/parser/#aab83e7ec2802c9a2c764dd5a6e531dd4">llvm::cl::parser&lt; DataType &gt;::getOptionValue</a>, <a href="/web-llvm/docs/api/classes/llvm/machinefunction/#a762c7607d5b10f01c0e06ba4ca7ca463">llvm::MachineFunction::getOrCreateLandingPadInfo</a>, <a href="/web-llvm/docs/api/files/lib/lib/support/sourcemgr-cpp/#aeedad20be775a7811deb410cb58936a0">GetOrCreateOffsetCache</a>, <a href="/web-llvm/docs/api/classes/llvm/abstractdependencegraphbuilder/#ac987bb4640feeb3e68c416f1bba3d8e3">llvm::AbstractDependenceGraphBuilder&lt; GraphType &gt;::getOrdinal</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/spirv/spirvcalllowering-cpp/#a3d3f9a7f2fef13c8261fa2d3175a4cca">getOriginalFunctionType</a>, <a href="/web-llvm/docs/api/classes/llvm/foldingsetbase/#a98ba3e7ad8978f484e80055f31ddc27f">llvm::FoldingSetBase::GetOrInsertNode</a>, <a href="/web-llvm/docs/api/classes/llvm/foldingsetimpl/#adda67d07328a47b679a6b2853129a411">llvm::FoldingSetImpl&lt; FoldingSet, T &gt;::GetOrInsertNode</a>, <a href="/web-llvm/docs/api/classes/llvm/foldingsetvector/#a1af63f402c97ccdf0d2d3709c3c86f1c">llvm::FoldingSetVector&lt; T, VectorT &gt;::GetOrInsertNode</a>, <a href="/web-llvm/docs/api/files/lib/lib/ir/metadata-cpp/#ac03fb37174ccf690b0e7e675b47fcb19">getOrSelfReference</a>, <a href="/web-llvm/docs/api/files/lib/lib/codegen/lib/codegen/selectiondag/scheduledagfast-cpp/#a28587903fe646efc2cdcbab03d1dae6f">getPhysicalRegisterVT</a>, <a href="/web-llvm/docs/api/files/lib/lib/codegen/lib/codegen/selectiondag/scheduledagrrlist-cpp/#a28587903fe646efc2cdcbab03d1dae6f">getPhysicalRegisterVT</a>, <a href="/web-llvm/docs/api/classes/llvm/datadependencegraph/#a1a1d1453dbff4d66cdd16b7d60b208b2">llvm::DataDependenceGraph::getPiBlock</a>, <a href="/web-llvm/docs/api/classes/llvm/armtargetlowering/#af4269b2cd295687cb69f61729f91de3b">llvm::ARMTargetLowering::getPostIndexedAddressParts</a>, <a href="/web-llvm/docs/api/classes/llvm/avrtargetlowering/#af736164122434ca6fc3a5ac01ef739fd">llvm::AVRTargetLowering::getPostIndexedAddressParts</a>, <a href="/web-llvm/docs/api/classes/llvm/hexagontargetlowering/#a391ef092ff421faccdfef4cb88424742">llvm::HexagonTargetLowering::getPostIndexedAddressParts</a>, <a href="/web-llvm/docs/api/classes/llvm/riscvtargetlowering/#ae6b240b84dcd1e1b72cf122899fa93b6">llvm::RISCVTargetLowering::getPostIndexedAddressParts</a>, <a href="/web-llvm/docs/api/files/lib/lib/codegen/lib/codegen/selectiondag/dagcombiner-cpp/#a9d391021d805c83de0c322c3cb0fb355">getPostIndexedLoadStoreOp</a>, <a href="/web-llvm/docs/api/classes/llvm/armtargetlowering/#a22338caf16030dc171ee6dfb5580d308">llvm::ARMTargetLowering::getPreIndexedAddressParts</a>, <a href="/web-llvm/docs/api/classes/llvm/avrtargetlowering/#a2639a31c0222a806fa852121053d535c">llvm::AVRTargetLowering::getPreIndexedAddressParts</a>, <a href="/web-llvm/docs/api/classes/llvm/ppctargetlowering/#a7e08a461c58c82e0564d2cd25c6d9990">llvm::PPCTargetLowering::getPreIndexedAddressParts</a>, <a href="/web-llvm/docs/api/classes/llvm/riscvtargetlowering/#ae82f1f57b5f1ea36a774e28f54afb435">llvm::RISCVTargetLowering::getPreIndexedAddressParts</a>, <a href="/web-llvm/docs/api/structs/llvm/ilist-detail/nodeaccess/#aa62bfd2b254f6d2f01ff5bbadea8148d">llvm::ilist_detail::NodeAccess::getPrev</a>, <a href="/web-llvm/docs/api/structs/llvm/ilist-detail/nodeaccess/#a38c544d663ce52a8774da9e89af6d49b">llvm::ilist_detail::NodeAccess::getPrev</a>, <a href="/web-llvm/docs/api/classes/llvm/iplist-impl/#af61ba750ef7ac5df2c3231de040b128f">llvm::iplist_impl&lt; IntrusiveListT, TraitsT &gt;::getPrevNode</a>, <a href="/web-llvm/docs/api/classes/llvm/iplist-impl/#a5228dfd6bcfc437238285960a2bf1607">llvm::iplist_impl&lt; IntrusiveListT, TraitsT &gt;::getPrevNode</a>, <a href="/web-llvm/docs/api/namespaces/llvm/avr/#aaa04c08d1a30024d2dc3de761ff3167d">llvm::AVR::getProgramMemoryBank</a>, <a href="/web-llvm/docs/api/classes/llvm/selectiondag/#a1e99e576dd285dc69aa7ae6de70c05b1">llvm::SelectionDAG::getPseudoProbeNode</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/x86/x86isellowering-cpp/#aed7f179be3c007d1be442c9864380289">getPSHUFShuffleMask</a>, <a href="/web-llvm/docs/api/files/lib/lib/analysis/scalarevolution-cpp/#a99c9ef8776106c1e7b35c77a32e750e1">GetQuadraticEquation</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/x86/x86isellowering-cpp/#ae020054e3ff6b34b048afacab677d69b">getReadTimeStampCounter</a>, <a href="/web-llvm/docs/api/classes/llvm/amdgpupalmetadata/#a547583d1108b1d2cf5c0cab7d18745a2">llvm::AMDGPUPALMetadata::getRegister</a>, <a href="/web-llvm/docs/api/classes/llvm/selectiondag/#a3963ce0b1b988776399447f21df86b15">llvm::SelectionDAG::getRegister</a>, <a href="/web-llvm/docs/api/classes/llvm/selectiondag/#acfe1250a2214797a59c6457dd2180df9">llvm::SelectionDAG::getRegisterMask</a>, <a href="/web-llvm/docs/api/files/lib/lib/codegen/lib/codegen/asmprinter/dwarfdebug-cpp/#ac285fd5fed8c9963ff45f4aa56c2dc41">getRetainedNodeScope</a>, <a href="/web-llvm/docs/api/classes/llvm/selectiondag/#ab8b2b591dc9b054d04368b7d069fb76c">llvm::SelectionDAG::getScatterVP</a>, <a href="/web-llvm/docs/api/classes/llvm/armtargetlowering/#aa16505b46d66798daa417510b68ee4ac">llvm::ARMTargetLowering::getSchedulingPreference</a>, <a href="/web-llvm/docs/api/classes/llvm/ppctargetlowering/#afdf7d53d8e2b25e7b5c7981da1f11bcf">llvm::PPCTargetLowering::getSchedulingPreference</a>, <a href="/web-llvm/docs/api/files/lib/lib/codegen/lib/codegen/selectiondag/legalizevectortypes-cpp/#a3828b7af8b26d13f77232acd994157d1">getSETCCOperandType</a>, <a href="/web-llvm/docs/api/classes/llvm/selectiondag/#aa7cfce69eeecdf585f55b39efbdff6ba">llvm::SelectionDAG::getSetFPEnv</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64iseldagtodag-cpp/#a6d531ddcb8443d0ac92dc9cb288cc2ed">getShiftTypeForNode</a>, <a href="/web-llvm/docs/api/classes/llvm/aarch64ttiimpl/#ac16a7b224b20beeecf5f1665b4bcc65f">llvm::AArch64TTIImpl::getShuffleCost</a>, <a href="/web-llvm/docs/api/namespaces/llvm/ppc/#a93d85169d871f169e06ab00673048741">llvm::PPC::getSplatIdxForPPCMnemonics</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/ve/veisellowering-cpp/#a07226cd9aa78324951d9be41f6083c3e">getSplatValue</a>, <a href="/web-llvm/docs/api/classes/llvm/selectiondag/#a8a8b6ac1e6f0f684df4c64e8ae8835e7">llvm::SelectionDAG::getSrcValue</a>, <a href="/web-llvm/docs/api/classes/llvm/selectiondag/#a211f6d3863ce35b5a5893032fe0449cc">llvm::SelectionDAG::getStore</a>, <a href="/web-llvm/docs/api/classes/llvm/selectiondag/#a7bebd21fcb08b6b7288fee3de1246c52">llvm::SelectionDAG::getStoreVP</a>, <a href="/web-llvm/docs/api/classes/llvm/selectiondag/#a2319cb3270540dfd23ffd53d5a9bd8aa">llvm::SelectionDAG::getStridedLoadVP</a>, <a href="/web-llvm/docs/api/classes/llvm/selectiondag/#a4eeee43813ecf8dee2c4ccb837ec33b5">llvm::SelectionDAG::getStridedStoreVP</a>, <a href="/web-llvm/docs/api/classes/llvm/pdb/pdbfile/#ae335ef8883662c8098907e284abfc085">llvm::pdb::PDBFile::getStringTable</a>, <a href="/web-llvm/docs/api/classes/llvm/type/#a15d34f8dc07013df378e0fb3d0134c08">llvm::Type::getStructElementType</a>, <a href="/web-llvm/docs/api/classes/llvm/r600targetlowering/#a45f53ca8960cf7c5bf2f1ed24f18f717">llvm::R600TargetLowering::getSubtarget</a>, <a href="/web-llvm/docs/api/classes/llvm/selectiondag/#ae6f9eed3ec877628ac2b052733cee4d4">llvm::SelectionDAG::getTargetExternalSymbol</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/riscv/riscvisellowering-cpp/#a7f9ca31cb6a069b4594120b871fe91a1">getTargetNode</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/loongarch/loongarchisellowering-cpp/#a88d2aaedf925f7f192287a26fc75018f">getTargetNode</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/bpf/bpfisellowering-cpp/#a438c44a26a1f406a36ae3dea8efaeb2e">getTargetNode</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/riscv/riscvisellowering-cpp/#a438c44a26a1f406a36ae3dea8efaeb2e">getTargetNode</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/loongarch/loongarchisellowering-cpp/#a46b57d2ef07375726714d5c2288f0300">getTargetNode</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/bpf/bpfisellowering-cpp/#a0f989f77f3be8d54ef9a019ebf91dc30">getTargetNode</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/riscv/riscvisellowering-cpp/#a0f989f77f3be8d54ef9a019ebf91dc30">getTargetNode</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/loongarch/loongarchisellowering-cpp/#a7b3dbb86863a5e1a6ba5db5a3e0890bd">getTargetNode</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/riscv/riscvisellowering-cpp/#ae13074a3432c3e29f4e1e4ac342a49cf">getTargetNode</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/loongarch/loongarchisellowering-cpp/#a5507f28808770a0e4ed4f88e09b47455">getTargetNode</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/x86/x86isellowering-cpp/#af71303967827d0c63f1caa626e59aa38">getTargetShuffleAndZeroables</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/x86/x86isellowering-cpp/#ab554d4fce0127f51272190ffde07740c">getTargetShuffleMask</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/x86/x86isellowering-cpp/#a0b31f77b61967dd90fbcc8174ea66e93">getTargetShuffleMask</a>, <a href="/web-llvm/docs/api/classes/anonymous-metadataloader-cpp-/anonymous-metadataloader-cpp-/placeholderqueue/#ab99ee806589a55f539ce9b5b42a07fd6">anonymous{MetadataLoader.cpp}::anonymous{MetadataLoader.cpp}::PlaceholderQueue::getTemporaries</a>, <a href="/web-llvm/docs/api/classes/llvm/sandboxir/schedbundle/#a2de3d46c20d973de8710506ad587749c">llvm::sandboxir::SchedBundle::getTop</a>, <a href="/web-llvm/docs/api/classes/llvm/selectiondag/#a8c2603648fb228b097b421cfd6c577e2">llvm::SelectionDAG::getTruncStore</a>, <a href="/web-llvm/docs/api/classes/llvm/selectiondag/#a2b70646a1a7d39196c9e405e6e765b98">llvm::SelectionDAG::getTruncStoreVP</a>, <a href="/web-llvm/docs/api/classes/llvm/selectiondag/#ace48e423cac6b59de28c739fbe31c34d">llvm::SelectionDAG::getTruncStridedStoreVP</a>, <a href="/web-llvm/docs/api/classes/llvm/structtype/#aa4a68dda48893ebd98fe7d4878ba0830">llvm::StructType::getTypeAtIndex</a>, <a href="/web-llvm/docs/api/classes/llvm/machinefunction/#a59699d911356a8cb81ed8e2d2d0be4c5">llvm::MachineFunction::getTypeIDFor</a>, <a href="/web-llvm/docs/api/classes/llvm/scalarevolution/#a0daed958320635f1a9d440819f5bd487">llvm::ScalarEvolution::getUDivCeilSCEV</a>, <a href="/web-llvm/docs/api/files/lib/lib/codegen/lib/codegen/selectiondag/selectiondagbuilder-cpp/#a7f9cdc800dea62835ecb6014346a0bcd">getUnderlyingArgRegs</a>, <a href="/web-llvm/docs/api/classes/llvm/selectiondagisel/#a483127dd84f9da223f9fe5d20a0367a8">llvm::SelectionDAGISel::getUninvalidatedNodeId</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/ve/veisellowering-cpp/#ade8d16a7df546490fdabf0e2b36e3917">getUniqueInsertion</a>, <a href="/web-llvm/docs/api/classes/llvm/opt/arg/#ac268590692356db84db78050196b4940">llvm::opt::Arg::getValue</a>, <a href="/web-llvm/docs/api/classes/llvm/pdb/nativesymbolenumerator/#a92ce81a47b33b491fd017d85aabf2822">llvm::pdb::NativeSymbolEnumerator::getValue</a>, <a href="/web-llvm/docs/api/classes/llvm/selectiondagbuilder/#a025adb087cac36e2cd504a33e8cb749d">llvm::SelectionDAGBuilder::getValue</a>, <a href="/web-llvm/docs/api/structs/llvm/ilist-detail/nodeaccess/#ae288c2541623a938ff8b156852911597">llvm::ilist_detail::NodeAccess::getValuePtr</a>, <a href="/web-llvm/docs/api/structs/llvm/ilist-detail/nodeaccess/#ac7700a6a7b6c1faac8b6a5547b09df75">llvm::ilist_detail::NodeAccess::getValuePtr</a>, <a href="/web-llvm/docs/api/structs/llvm/ilist-detail/specificnodeaccess/#a5b870991624a137cca72e1b32a9e70c8">llvm::ilist_detail::SpecificNodeAccess&lt; OptionsT &gt;::getValuePtr</a>, <a href="/web-llvm/docs/api/structs/llvm/ilist-detail/specificnodeaccess/#a1174beada47865b43be33b53b17f2f09">llvm::ilist_detail::SpecificNodeAccess&lt; OptionsT &gt;::getValuePtr</a>, <a href="/web-llvm/docs/api/classes/llvm/selectiondag/#ab8ba6b05ad4fa7517f2e23b26f84ae1b">llvm::SelectionDAG::getValueType</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/arm/armisellowering-cpp/#a93361b1deb973c1d37e7f7ec635ec2af">getVCMPCondCode</a>, <a href="/web-llvm/docs/api/classes/llvm/selectiondag/#afa7e233051b9ed8ebc0191f42698cb14">llvm::SelectionDAG::getVectorShuffle</a>, <a href="/web-llvm/docs/api/structs/anonymous-msgpackdocumentyaml-cpp-/scalardocnode/#a3eeed73cd2b23e69e57d250ffece67d1">anonymous{MsgPackDocumentYAML.cpp}::ScalarDocNode::getYAMLTag</a>, <a href="/web-llvm/docs/api/classes/llvm/scalarevolution/#a26ffa319e1953452b1d1df84923f2108">llvm::ScalarEvolution::getZeroExtendExprImpl</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/hexagon/hexagonsubtarget-cpp/#abdd044c0a8482db135c0470df8d1920b">getZeroLatency</a>, <a href="/web-llvm/docs/api/classes/llvm/giselworklist/#a50c5a776b3621c57e5e904a33ca2c564">llvm::GISelWorkList&lt; 512 &gt;::GISelWorkList</a>, <a href="/web-llvm/docs/api/classes/llvm/inteqclasses/#ae3fe12ef47c5acce81d60daf8155c52d">llvm::IntEqClasses::grow</a>, <a href="/web-llvm/docs/api/classes/llvm/selectiondagbuilder/#a6571e1b07bfb1d4c5b1e832fdac355a1">llvm::SelectionDAGBuilder::handleDebugDeclare</a>, <a href="/web-llvm/docs/api/classes/llvm/selectiondagbuilder/#ae9748fb2e4d41aaa8ac80d00b2becc52">llvm::SelectionDAGBuilder::handleDebugValue</a>, <a href="/web-llvm/docs/api/files/lib/lib/codegen/lib/codegen/selectiondag/selectiondagisel-cpp/#aeb0bc3fb3008d1f61c5a1adb0b901c82">HandleMergeInputChains</a>, <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/utils/dxilupgrade-cpp/#a55a5c0652f51a63dc1ad0f386fe011f2">handleValVerMetadata</a>, <a href="/web-llvm/docs/api/classes/llvm/diexpression/#a55331359f9d74f5969a5b1ac700cbccd">llvm::DIExpression::hasAllLocationOps</a>, <a href="/web-llvm/docs/api/classes/llvm/scc-iterator/#abbd6357648d228d6a6e32e00aa2a5794">llvm::scc_iterator&lt; GraphT, GT &gt;::hasCycle</a>, <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/ipo/mergefunctions-cpp/#a95f2972efd3301ed0417b5fe74ecd9fb">hasDistinctMetadataIntrinsic</a>, <a href="/web-llvm/docs/api/classes/llvm/dgnode/#acae2ec43dd8e6715a9706107fabb63b3">llvm::DGNode&lt; DDGNode, DDGEdge &gt;::hasEdgeTo</a>, <a href="/web-llvm/docs/api/structs/llvm/domtreebuilder/semincainfo/#aa26a0ee0a9f0cd627c9a6dc712ae53cb">llvm::DomTreeBuilder::SemiNCAInfo&lt; DomTreeT &gt;::HasForwardSuccessors</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a9758dcba3499ba13d2756537ffe9474b">llvm::hasInstrProfHashMismatch</a>, <a href="/web-llvm/docs/api/classes/llvm/sandboxir/memdgnode/#a29735a2d6ea6cc680b8553d1013e040d">llvm::sandboxir::MemDGNode::hasMemPred</a>, <a href="/web-llvm/docs/api/classes/llvm/sitargetlowering/#a8f7c0e181f6da8ad09295aaaa2445880">llvm::SITargetLowering::hasMemSDNodeUser</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#aa23468ef9810b74fa5b8d4a8f319d715">llvm::hasNItems</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a7a396bf53b927c8f4c2191a0d115c7e1">llvm::hasNItems</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a38328ea32bc035b0156dfb05ff54400a">llvm::hasNItemsOrLess</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a3b24ebd69d40090a23b6a2717a896625">llvm::hasNItemsOrLess</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#ae7cc12beecee8ad26a54d3d81c6361af">llvm::hasNItemsOrMore</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a59eea4fd874ad0e0fad609e750c88976">llvm::hasNItemsOrMore</a>, <a href="/web-llvm/docs/api/files/lib/lib/codegen/lib/codegen/selectiondag/dagcombiner-cpp/#a67a9597d213ec55980bfeae907088d12">hasNoInfs</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/arm/armisellowering-cpp/#a573ab177e3dc7d27d8b2c6cb33544ab2">hasNormalLoadOperand</a>, <a href="/web-llvm/docs/api/classes/anonymous-armiseldagtodag-cpp-/armdagtodagisel/#ac699970e87055703b65c2efc1609689c">anonymous{ARMISelDAGToDAG.cpp}::ARMDAGToDAGISel::hasNoVMLxHazardUse</a>, <a href="/web-llvm/docs/api/classes/llvm/sdnode/#ab250276b651715d29b3ed20467d5f0a0">llvm::SDNode::hasPredecessor</a>, <a href="/web-llvm/docs/api/classes/llvm/sdnode/#a7c6beebf86835d6582b0550cd7731ee9">llvm::SDNode::hasPredecessorHelper</a>, <a href="/web-llvm/docs/api/files/lib/lib/ir/metadata-cpp/#a49da541b1e4cbb56f6ffaf92a684a697">hasSelfReference</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/amdgpuisellowering-cpp/#ac94d59ca34337f9b86479633636c9aeb">hasSourceMods</a>, <a href="/web-llvm/docs/api/namespaces/llvm/logicalview/#a0b853e87e0efcb31ad9f0381e7db7673">llvm::logicalview::hexValue</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a5efa2c3e00054566f1baaebc766461a4">llvm::hoistRegion</a>, <a href="/web-llvm/docs/api/classes/llvm/ilist-iterator/#abff2792faee68be0b8f65b99e8dab25b">llvm::ilist_iterator&lt; OptionsT, false, IsConst &gt;::ilist_iterator</a>, <a href="/web-llvm/docs/api/classes/llvm/ilist-iterator-w-bits/#a456ff55f796b007c0b243361a339c938">llvm::ilist_iterator_w_bits&lt; OptionsT, false, IsConst &gt;::ilist_iterator_w_bits</a>, <a href="/web-llvm/docs/api/classes/anonymous-xcoreiseldagtodag-cpp-/xcoredagtodagisel/#a130dd8b3a7be78a6fc6a72c513d00ef6">anonymous{XCoreISelDAGToDAG.cpp}::XCoreDAGToDAGISel::immMskBitp</a>, <a href="/web-llvm/docs/api/classes/anonymous-aarch64iseldagtodag-cpp-/aarch64dagtodagisel/#aebb4fd817f8233e59740b2c09a186f79">anonymous{AArch64ISelDAGToDAG.cpp}::AArch64DAGToDAGISel::ImmToReg</a>, <a href="/web-llvm/docs/api/classes/llvm/scevcomparepredicate/#ae05048aed25e1bf5010cc082e945f3f5">llvm::SCEVComparePredicate::implies</a>, <a href="/web-llvm/docs/api/classes/llvm/scevpredicate/#a917cb28715479ee3f2bc44d4149e13ef">llvm::SCEVPredicate::implies</a>, <a href="/web-llvm/docs/api/classes/llvm/scevunionpredicate/#a8e7ccfbb8166c920e677827e9a972aac">llvm::SCEVUnionPredicate::implies</a>, <a href="/web-llvm/docs/api/classes/llvm/scevwrappredicate/#a1bb4ca5c2810fc70f58fcf2581fa5bca">llvm::SCEVWrapPredicate::implies</a>, <a href="/web-llvm/docs/api/files/lib/lib/analysis/cgsccpassmanager-cpp/#aa64f6bcd5ace031369edc14aa406d745">incorporateNewSCCRange</a>, <a href="/web-llvm/docs/api/structs/anonymous-lowermatrixintrinsics-cpp-/lowermatrixintrinsics/exprlinearizer/#a4399031f3a5c96f0558df1ed7b828135">anonymous{LowerMatrixIntrinsics.cpp}::LowerMatrixIntrinsics::ExprLinearizer::indent</a>, <a href="/web-llvm/docs/api/structs/llvm/rdf/indexedset/#a3d9a103e8ef8f1d4fac156b23c178f85">llvm::rdf::IndexedSet&lt; T, N &gt;::IndexedSet</a>, <a href="/web-llvm/docs/api/classes/llvm/pressurediffs/#adc55f26c1bfbbe17074ded7275f3961c">llvm::PressureDiffs::init</a>, <a href="/web-llvm/docs/api/structs/llvm/bfi-detail/irreduciblegraph/#abe3bf5fccbd988d1daf97da30f0b0456">llvm::bfi_detail::IrreducibleGraph::initialize</a>, <a href="/web-llvm/docs/api/classes/llvm/resourcepriorityqueue/#ae40b5614303ad840c02bf2923d5f4305">llvm::ResourcePriorityQueue::initNumRegDefsLeft</a>, <a href="/web-llvm/docs/api/structs/inprogressentry/#a9d5b05a6b4de77767af37085bb3599ac">InProgressEntry::InProgressEntry</a>, <a href="/web-llvm/docs/api/structs/inprogressentry/#a2a8cb48dd55136330da7bfb42a2c1638">InProgressEntry::InProgressEntry</a>, <a href="/web-llvm/docs/api/structs/llvm/yaml/scalartraits-0eeacf48dfe007adc51330f03710cc90/#a6199f2256f4f065b51336b9327b18343">llvm::yaml::ScalarTraits&lt; Align &gt;::input</a>, <a href="/web-llvm/docs/api/structs/llvm/yaml/scalartraits-9d99cee30155623a4c4295fc3384ef15/#a845b3d5882fd989ac76b445ada27c7ed">llvm::yaml::ScalarTraits&lt; FixedSizeHex&lt; N &gt; &gt;::input</a>, <a href="/web-llvm/docs/api/structs/llvm/yaml/scalartraits-96f7362ea1da512c0a2732407c64df72/#a75bb8750d14640536f5b8127fa36620d">llvm::yaml::ScalarTraits&lt; FixedSizeString&lt; N &gt; &gt;::input</a>, <a href="/web-llvm/docs/api/structs/anonymous-hexagoncommongep-cpp-/nodeordering/#afc35bb8e3add1f694e6eaa470140c4a1">anonymous{HexagonCommonGEP.cpp}::NodeOrdering::insert</a>, <a href="/web-llvm/docs/api/structs/llvm/df-iterator-default-set/#afd3dcab23b7d24dbc2775ce3e132b1d5">llvm::df_iterator_default_set&lt; NodeRef, SmallSize &gt;::insert</a>, <a href="/web-llvm/docs/api/classes/llvm/immutablegraph/nodeset/#a4b1559c2b8242a4e33e636d551a5ea15">llvm::ImmutableGraph&lt; NodeValueT, EdgeValueT &gt;::NodeSet::insert</a>, <a href="/web-llvm/docs/api/classes/llvm/intervalmapimpl/branchnode/#af8deb6d8a06cd57e8268aef054879101">llvm::IntervalMapImpl::BranchNode&lt; KeyT, ValT, Sizer::BranchSize, Traits &gt;::insert</a>, <a href="/web-llvm/docs/api/classes/llvm/sandboxir/readylistcontainer/#ab2adde662d63350b0903bd45a96bc1af">llvm::sandboxir::ReadyListContainer::insert</a>, <a href="/web-llvm/docs/api/classes/llvm/setvector/#af34eb71cc483e84d2eca80575cb9ccde">llvm::SetVector&lt; EdgeType * &gt;::insert</a>, <a href="/web-llvm/docs/api/classes/outputbuffer/#ae8f0bd74643fb4035d3992af214b44a3">OutputBuffer::insert</a>, <a href="/web-llvm/docs/api/classes/llvm/ilist-base/#a6249803574fbf238e8fd351266899aea">llvm::ilist_base&lt; enable_sentinel_tracking, parent_ty &gt;::insertBefore</a>, <a href="/web-llvm/docs/api/classes/llvm/ilist-base/#a85aca1fb71993a8a1110e0138e8b1616">llvm::ilist_base&lt; enable_sentinel_tracking, parent_ty &gt;::insertBeforeImpl</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/x86/x86iseldagtodag-cpp/#a7c404b9b284d7d53f3aec00e776cd5b7">insertDAGNode</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/systemz/systemziseldagtodag-cpp/#ae61c505ef5dc38733d7b12b91e545a44">insertDAGNode</a>, <a href="/web-llvm/docs/api/classes/llvm/intervalmapimpl/leafnode/#ab0bd3e9464208516b824137ed7c70644">llvm::IntervalMapImpl::LeafNode&lt; KeyT, ValT, N, Traits &gt;::insertFrom</a>, <a href="/web-llvm/docs/api/classes/llvm/lazycallgraph/refscc/#a01b1581633bb40f86d6dc62a1c1a7f72">llvm::LazyCallGraph::RefSCC::insertIncomingRefEdge</a>, <a href="/web-llvm/docs/api/classes/llvm/foldingsetbase/#abad18f0235458f866663a2a78062c855">llvm::FoldingSetBase::InsertNode</a>, <a href="/web-llvm/docs/api/classes/llvm/foldingsetimpl/#a91cbae714e29bed29b5db8107b20fe10">llvm::FoldingSetImpl&lt; FoldingSet, T &gt;::InsertNode</a>, <a href="/web-llvm/docs/api/classes/llvm/foldingsetimpl/#aa7baa770e668fe8bb1d34ed9010a0bb0">llvm::FoldingSetImpl&lt; FoldingSet, T &gt;::InsertNode</a>, <a href="/web-llvm/docs/api/classes/llvm/foldingsetvector/#a7c5a4127393e04cb5eb5c17fe83a3a0b">llvm::FoldingSetVector&lt; T, VectorT &gt;::InsertNode</a>, <a href="/web-llvm/docs/api/classes/llvm/foldingsetvector/#af4ea13f6943a665055f541c7abda81b9">llvm::FoldingSetVector&lt; T, VectorT &gt;::InsertNode</a>, <a href="/web-llvm/docs/api/classes/llvm/inteqclasses/#a4b2302054a7bd53a46f7923854f45385">llvm::IntEqClasses::IntEqClasses</a>, <a href="/web-llvm/docs/api/classes/llvm/xray/profile/#a12fc96db03e9487cdd871074d13d0f64">llvm::xray::Profile::internPath</a>, <a href="/web-llvm/docs/api/classes/llvm/functionanalysismanagercgsccproxy/result/#a1d080c4ca8dd19e09237ac942b78acc7">llvm::FunctionAnalysisManagerCGSCCProxy::Result::invalidate</a>, <a href="/web-llvm/docs/api/classes/llvm/selectiondagisel/#af26c0de7ef8200c67d515229ac1f5453">llvm::SelectionDAGISel::InvalidateNodeId</a>, <a href="/web-llvm/docs/api/classes/llvm/phivalues/#a1f338cd311db969863e0560bed619bf5">llvm::PhiValues::invalidateValue</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/hexagon/hexagoncommongep-cpp/#a670b2ca76a46e31c94528f34ebf849c8">invert_find_roots</a>, <a href="/web-llvm/docs/api/classes/llvm/pointersumtype/#ae551a2bdd6f1404ca525b69c51af7251">llvm::PointerSumType&lt; TagT, MemberTs... &gt;::is</a>, <a href="/web-llvm/docs/api/namespaces/anonymous-hexagoncommongep-cpp-/#a5ce697a9c6ce3a134269d49db430b86a">anonymous{HexagonCommonGEP.cpp}::is_constant</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/m68k/m68kiseldagtodag-cpp/#ab6b7aacaba026852a7ef7ae8af0cb7c8">isAddressBase</a>, <a href="/web-llvm/docs/api/classes/anonymous-armiseldagtodag-cpp-/armdagtodagisel/#a97fccf6d0a26eb7a492eeecb241a93d0">anonymous{ARMISelDAGToDAG.cpp}::ARMDAGToDAGISel::IsAddressingMode5</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/x86/x86isellowering-cpp/#abcc89aad99c6a03adb5443eb5fa9f93c">isAddSubOrSubAdd</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/arm/armisellowering-cpp/#a7b88feeb3710cc54997cad1540860f08">isAddSubSExt</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64isellowering-cpp/#a02ba38ae733ae47a36eb03d9661fff6d">isAddSubSExt</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/arm/armisellowering-cpp/#a792e04e2a436db3281f42173654da414">isAddSubZExt</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64isellowering-cpp/#ad17c5939bd075abb87efb7268115f49b">isAddSubZExt</a>, <a href="/web-llvm/docs/api/namespaces/llvm/jitlink/#aa82aae3a001c5ed1fc950e97d85001a2">llvm::jitlink::isAlignmentCorrect</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64isellowering-cpp/#a33354bc388aab299f6dca5b75bbe2238">isAllActivePredicate</a>, <a href="/web-llvm/docs/api/classes/llvm/aarch64targetlowering/#ae7774721462886f7e79d72a94a121721">llvm::AArch64TargetLowering::isAllActivePredicate</a>, <a href="/web-llvm/docs/api/files/lib/lib/ir/debuginfo-cpp/#adc4df7597bb478e068d19916b187ef65">isAllDILocation</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64isellowering-cpp/#af615c2897e116be598ef60e4bbdbdd52">isAllInactivePredicate</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a8bc22108991ddb3f5bf2411c7b1f2149">llvm::isAllOnesOrAllOnesSplat</a>, <a href="/web-llvm/docs/api/classes/llvm/lazycallgraph/refscc/#a35a8d25c6df3f1d3bc5faba32de1dd55">llvm::LazyCallGraph::RefSCC::isAncestorOf</a>, <a href="/web-llvm/docs/api/classes/llvm/lazycallgraph/scc/#a024bad6935b15f7080b08b5dfec4eade">llvm::LazyCallGraph::SCC::isAncestorOf</a>, <a href="/web-llvm/docs/api/structs/anonymous-riscvasmparser-cpp-/riscvoperand/#a0f7cfaa1c472b36c995d6f95d9321e0a">anonymous{RISCVAsmParser.cpp}::RISCVOperand::isBareSimmNLsb0</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64iseldagtodag-cpp/#a53571dac5a290c5dd35e39486fe7e0ff">isBitfieldExtractOp</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64iseldagtodag-cpp/#a4b1f6c2a4e7b3aed4f56643d545f305b">isBitfieldExtractOpFromAnd</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64iseldagtodag-cpp/#a04d8bec5e4e1e6af669b1a018363b8b4">isBitfieldExtractOpFromSExtInReg</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64iseldagtodag-cpp/#aaf4b732e582e80caaceee1ed402180b8">isBitfieldExtractOpFromShr</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/mips/mipsseisellowering-cpp/#a38cd8a461664087e5c41c02aa3b660a7">isBitwiseInverse</a>, <a href="/web-llvm/docs/api/classes/llvm/selectiondag/#aedad36f1b0e2bd04f435ca9d1a595f9e">llvm::SelectionDAG::isBoolConstant</a>, <a href="/web-llvm/docs/api/classes/anonymous-aarch64asmparser-cpp-/aarch64operand/#a6502fd15601fbefa6de9a3c3f2a15a0d">anonymous{AArch64AsmParser.cpp}::AArch64Operand::isBranchTarget</a>, <a href="/web-llvm/docs/api/files/lib/lib/codegen/lib/codegen/selectiondag/dagcombiner-cpp/#afb2a4a1cf74122cbd8c4874f36961266">isBSwapHWordElement</a>, <a href="/web-llvm/docs/api/files/lib/lib/codegen/lib/codegen/selectiondag/dagcombiner-cpp/#a8f7262d114885a06bcab599252258208">isBSwapHWordPair</a>, <a href="/web-llvm/docs/api/namespaces/llvm/isd/#ac78d4df51ca05e4fb1630a01e07de434">llvm::ISD::isBuildVectorAllOnes</a>, <a href="/web-llvm/docs/api/namespaces/llvm/isd/#aaac3e239cbdfe15a8e9bad4f8e1e3a95">llvm::ISD::isBuildVectorAllZeros</a>, <a href="/web-llvm/docs/api/namespaces/llvm/isd/#abf3a86e6cdc4fe3dbd4e618c2f7a64c2">llvm::ISD::isBuildVectorOfConstantFPSDNodes</a>, <a href="/web-llvm/docs/api/namespaces/llvm/isd/#a2f37af786c5ba90887c1b4ec137a066c">llvm::ISD::isBuildVectorOfConstantSDNodes</a>, <a href="/web-llvm/docs/api/files/lib/lib/codegen/lib/codegen/selectiondag/scheduledagrrlist-cpp/#a1bf4053dbca77629ac65f4039a774fae">IsChainDependent</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64isellowering-cpp/#a3633803da2c1e9246eae907b238a0beb">isCheapToExtend</a>, <a href="/web-llvm/docs/api/structs/anonymous-riscvisellowering-cpp-/nodeextensionhelper/#a608b96d77b2ddf406d79e2716eb1ac47">anonymous{RISCVISelLowering.cpp}::NodeExtensionHelper::isCommutative</a>, <a href="/web-llvm/docs/api/files/lib/lib/codegen/lib/codegen/selectiondag/dagcombiner-cpp/#a44ca491dd218c0a233cd802680f27ad5">isCompatibleLoad</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/arm/armisellowering-cpp/#a98baa5c6ddd157ab0823fc3c308b94da">isConditionalZeroOrAllOnes</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/lanai/lanaiisellowering-cpp/#a98baa5c6ddd157ab0823fc3c308b94da">isConditionalZeroOrAllOnes</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/powerpc/ppcisellowering-cpp/#a915e43885fb2c475d2618dd41c58ed5d">isConsecutiveLS</a>, <a href="/web-llvm/docs/api/classes/llvm/amdgputargetlowering/#a544a02a070f8a473a2d747c3505e253b">llvm::AMDGPUTargetLowering::isConstantCheaperToNegate</a>, <a href="/web-llvm/docs/api/classes/llvm/amdgputargetlowering/#a6a7d63730380e17cc7355495627454d5">llvm::AMDGPUTargetLowering::isConstantCostlierToNegate</a>, <a href="/web-llvm/docs/api/classes/llvm/selectiondag/#a6b1d42b296c7c720ed353ebe0cb22f38">llvm::SelectionDAG::isConstantFPBuildVectorOrConstantFP</a>, <a href="/web-llvm/docs/api/classes/llvm/selectiondag/#a25f268d098eb2425d10532c2184ee8b6">llvm::SelectionDAG::isConstantIntBuildVectorOrConstantInt</a>, <a href="/web-llvm/docs/api/files/lib/lib/codegen/lib/codegen/selectiondag/dagcombiner-cpp/#a0b0c2cfc38bd4a4451d4dfdeac54d94c">isConstantOrConstantVector</a>, <a href="/web-llvm/docs/api/namespaces/llvm/isd/#aafb64237a88493be2c913b0a51630a0f">llvm::ISD::isConstantSplatVector</a>, <a href="/web-llvm/docs/api/namespaces/llvm/isd/#a08b1839785665aed1d6e91dd72764713">llvm::ISD::isConstantSplatVectorAllOnes</a>, <a href="/web-llvm/docs/api/namespaces/llvm/isd/#a531723c97a9c44056fc4996bde57229e">llvm::ISD::isConstantSplatVectorAllZeros</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64isellowering-cpp/#aec601d177f33c89713cff3857f97aa77">isConstantSplatVectorMaskForType</a>, <a href="/web-llvm/docs/api/files/lib/lib/codegen/lib/codegen/selectiondag/dagcombiner-cpp/#a607229211531af1259b2603df68033f0">isConstantSplatVectorMaskForType</a>, <a href="/web-llvm/docs/api/classes/llvm/selectiondag/#a95ee49cdb9f51fdf15552e5ab6af8152">llvm::SelectionDAG::isConstantValueOfAnyType</a>, <a href="/web-llvm/docs/api/classes/llvm/targetlowering/#a485c321d878ce722bb8d19a4b9d81657">llvm::TargetLowering::isConstFalseVal</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#abb4484ddcdad2576d97870230db05ed8">llvm::isConstOrConstSplat</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a8ceb04284d179d66b26dede64956d9c7">llvm::isConstOrConstSplat</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a516614c2855a763aa9eef67c6da888e0">llvm::isConstOrConstSplatFP</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#aedef5fbc8b36ae2d384e6a2d2dbae6ca">llvm::isConstOrConstSplatFP</a>, <a href="/web-llvm/docs/api/classes/llvm/targetlowering/#a49086baced6151325ba4b88ecdd5383f">llvm::TargetLowering::isConstTrueVal</a>, <a href="/web-llvm/docs/api/files/lib/lib/codegen/lib/codegen/selectiondag/dagcombiner-cpp/#a888abd560b0cd9a11630e3fab1e63c51">isContractableFMUL</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/siisellowering-cpp/#ac9e967824f3d95d21e222854a046743d">isCopyFromRegOfInlineAsm</a>, <a href="/web-llvm/docs/api/structs/llvm/itaniumpartialdemangler/#adc2764e156977abc23c40ce1344427ed">llvm::ItaniumPartialDemangler::isCtorOrDtor</a>, <a href="/web-llvm/docs/api/classes/llvm/aarch64targetlowering/#aecbd41e7754d9ca4d664dfa0d9df8510">llvm::AArch64TargetLowering::isDesirableToCommuteWithShift</a>, <a href="/web-llvm/docs/api/classes/llvm/amdgputargetlowering/#a4332a6c6b7e415a85911602414542140">llvm::AMDGPUTargetLowering::isDesirableToCommuteWithShift</a>, <a href="/web-llvm/docs/api/classes/llvm/armtargetlowering/#a0e3aa05aca949e6905dcb30c81c679e3">llvm::ARMTargetLowering::isDesirableToCommuteWithShift</a>, <a href="/web-llvm/docs/api/classes/llvm/riscvtargetlowering/#a52376a753c8ddea8a93cc03bdecc4fcd">llvm::RISCVTargetLowering::isDesirableToCommuteWithShift</a>, <a href="/web-llvm/docs/api/classes/llvm/targetlowering/#acadf633df07f9e11330ae99edf3e1bb7">llvm::TargetLowering::isDesirableToCommuteWithShift</a>, <a href="/web-llvm/docs/api/classes/llvm/aarch64targetlowering/#aec5f3889dfe7e8587557d1addb3a367c">llvm::AArch64TargetLowering::isDesirableToCommuteXorWithShift</a>, <a href="/web-llvm/docs/api/classes/llvm/armtargetlowering/#a49bbf30468c8d202d88466ff4bfd46dd">llvm::ARMTargetLowering::isDesirableToCommuteXorWithShift</a>, <a href="/web-llvm/docs/api/classes/llvm/targetlowering/#aaa536ba062854f0951a19b7457665c96">llvm::TargetLowering::isDesirableToCommuteXorWithShift</a>, <a href="/web-llvm/docs/api/files/lib/lib/ir/debuginfo-cpp/#af9ce3a67baafe11cb1484e0a1fc2b451">isDILocationReachable</a>, <a href="/web-llvm/docs/api/classes/llvm/dgnode/#aa16043c4ce9fe32590dd9a1cf9494b2d">llvm::DGNode&lt; DDGNode, DDGEdge &gt;::isEqualTo</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64isellowering-cpp/#ae7427237c74674e338a5baf351956f98">isEssentiallyExtractHighSubvector</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/arm/armisellowering-cpp/#a6c49319d93381e455f0138e221896629">isExtendedBUILD_VECTOR</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64isellowering-cpp/#a1b7427c6c75d193f9899b8a2849ed8aa">isExtendedBUILD_VECTOR</a>, <a href="/web-llvm/docs/api/classes/llvm/targetlowering/#a2dc906a01997a28f62fd05f6470d7dd7">llvm::TargetLowering::isExtendedTrueVal</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64isellowering-cpp/#a41c7c45737725bfde12e18e00feae15a">isExtendOrShiftOperand</a>, <a href="/web-llvm/docs/api/namespaces/llvm/isd/#a910795e8d77c1545da0683c0e1cb81ee">llvm::ISD::isEXTLoad</a>, <a href="/web-llvm/docs/api/classes/llvm/sitargetlowering/#a107b140628d17693305f07c5a1590a14">llvm::SITargetLowering::isFMADLegal</a>, <a href="/web-llvm/docs/api/classes/llvm/targetloweringbase/#a1077912d87ec3c85548fb8ab20a22caa">llvm::TargetLoweringBase::isFMADLegal</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/x86/x86isellowering-cpp/#a37f06b796addd745c44af4546b84fe76">isFNEG</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/x86/x86isellowering-cpp/#a2740fb8073dd44c958e5ee272444fde8">isFoldableUseOfShuffle</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/x86/x86isellowering-cpp/#a83537c0760f3fe6e50ed6205bb999a59">isFreeToSplitVector</a>, <a href="/web-llvm/docs/api/namespaces/llvm/isd/#a938294d45605337641e10c207def0988">llvm::ISD::isFreezeUndef</a>, <a href="/web-llvm/docs/api/classes/llvm/targetlowering/#abe66a168970ddd74cce6fbc9a40589c7">llvm::TargetLowering::isGAPlusOffset</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64isellowering-cpp/#adfaf056ced72346fabb19629cb51ead0">isHalvingTruncateAndConcatOfLegalIntScalableType</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/x86/x86isellowering-cpp/#a0bf38c29e86627800a241dc0f1005d5c">isHorizontalBinOpPart</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/ve/veisellowering-cpp/#aa4af5de1f29bd00a557083800ec079b3">isI32Insn</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/ve/veisellowering-cpp/#a56bc54b1cdc353a04db9ffa06e20d33c">isI32InsnAllUses</a>, <a href="/web-llvm/docs/api/classes/anonymous-armasmparser-cpp-/armoperand/#a31dc6d11a8c07395e1d0c38201df46a6">anonymous{ARMAsmParser.cpp}::ARMOperand::isImmediate</a>, <a href="/web-llvm/docs/api/classes/anonymous-armasmparser-cpp-/armoperand/#af43a6853b57a2e7207df485bafbb58a1">anonymous{ARMAsmParser.cpp}::ARMOperand::isImmediateS2</a>, <a href="/web-llvm/docs/api/classes/anonymous-armasmparser-cpp-/armoperand/#a0f65a3de546118692e8a061eadf55c25">anonymous{ARMAsmParser.cpp}::ARMOperand::isImmediateS4</a>, <a href="/web-llvm/docs/api/classes/anonymous-aarch64asmparser-cpp-/aarch64operand/#a0f6c1755e5ae566a87d87508d3cee9dc">anonymous{AArch64AsmParser.cpp}::AArch64Operand::isImmInRange</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/xcore/xcoreinstrinfo-cpp/#a96c5793f290e33933b89aff07e204852">isImmMskBitp</a>, <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/utils/splitmodule-cpp/#a80f6063dd5f9d9d06818808cbb646f75">isInPartition</a>, <a href="/web-llvm/docs/api/namespaces/llvm/jitlink/#ad47a0ff75d04d948cd596d3bd3b8fa2e">llvm::jitlink::isInRangeForImm</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a1a1e51a5952c3afa00875df90e7ae6f8">llvm::isInt</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/arm/armiseldagtodag-cpp/#a7c97deb23c9a669470b42d2bd2e99f19">isInt32Immediate</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/powerpc/ppciseldagtodag-cpp/#a7c97deb23c9a669470b42d2bd2e99f19">isInt32Immediate</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/arm/armiseldagtodag-cpp/#ace33718e35b67e1af759c3ec4c8f8443">isInt32Immediate</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/powerpc/ppciseldagtodag-cpp/#ace33718e35b67e1af759c3ec4c8f8443">isInt32Immediate</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/powerpc/ppciseldagtodag-cpp/#a7312dc1e31cba7889c13ff9ada91ff15">isInt64Immediate</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/powerpc/ppciseldagtodag-cpp/#a7dae3a17b5f66753b01606d48d50cd1d">isInt64Immediate</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64iseldagtodag-cpp/#aed37527b97744cc3570d09ed4d53fa51">isIntImmediate</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64isellowering-cpp/#aed37527b97744cc3570d09ed4d53fa51">isIntImmediate</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64iseldagtodag-cpp/#ac21f94c1c3947470e1b70a7238e172dd">isIntImmediate</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64iseldagtodag-cpp/#ae06fff53263e566c62b3798af5ea781f">isIntImmediateEq</a>, <a href="/web-llvm/docs/api/classes/llvm/apint/#ae00c35cb040107c05f3fe00c15bb3da0">llvm::APInt::isIntN</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#aad80b46c754cc7216244a866ec9b1cb0">llvm::isIntN</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a267dbd8fce711ee4a1adc8ee2b42fa0a">llvm::isIntS16Immediate</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a9ee9da8b28b365034ec4d2be17184ba7">llvm::isIntS34Immediate</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/powerpc/ppciseldagtodag-cpp/#a553dedf86a7805668290b813795b59d2">isLaneInsensitive</a>, <a href="/web-llvm/docs/api/classes/llvm/siinstrinfo/#ab97de5c81e48922426466768a69b38bf">llvm::SIInstrInfo::isLegalFLATOffset</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/x86/x86iseldagtodag-cpp/#a026121a7546e6370b59fc4b70af584d7">isLegalMaskCompare</a>, <a href="/web-llvm/docs/api/classes/llvm/selectiondagisel/#a98c172c9b66de1264ee2123e4f1a3df2">llvm::SelectionDAGISel::IsLegalToFold</a>, <a href="/web-llvm/docs/api/classes/llvm/sitargetlowering/#a934e0e0b94737441bea75fc4babf0021">llvm::SITargetLowering::isMemOpHasNoClobberedMemOperand</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64iseldagtodag-cpp/#abc725a1da8895568464ac487a30cbb1d">isMemOpOrPrefetch</a>, <a href="/web-llvm/docs/api/classes/anonymous-itaniummanglingcanonicalizer-cpp-/canonicalizerallocator/#a86e784e2c83a663b5e09b3deddbf250c">anonymous{ItaniumManglingCanonicalizer.cpp}::CanonicalizerAllocator::isMostRecentlyCreated</a>, <a href="/web-llvm/docs/api/classes/llvm/amdgputargetlowering/#ae14323a03c6bd118c28baa4bf381e532">llvm::AMDGPUTargetLowering::isNarrowingProfitable</a>, <a href="/web-llvm/docs/api/classes/llvm/targetloweringbase/#aafb5c7d833aa31d38df4f426bde5c3e7">llvm::TargetLoweringBase::isNarrowingProfitable</a>, <a href="/web-llvm/docs/api/classes/llvm/x86targetlowering/#a83185148c0d5d8353cc716271c560e66">llvm::X86TargetLowering::isNarrowingProfitable</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/powerpc/ppcisellowering-cpp/#af7dd03e8ef59be43553b3168e2293f33">isNByteElemShuffleMask</a>, <a href="/web-llvm/docs/api/namespaces/anonymous-typebasedaliasanalysis-cpp-/#a6082c6c4759ae677ec5e32ef0a5eff0f">anonymous{TypeBasedAliasAnalysis.cpp}::isNewFormatTypeNode</a>, <a href="/web-llvm/docs/api/namespaces/llvm/isd/#a15623094a1ed0cd7163dc786e44c87c9">llvm::ISD::isNON_EXTLoad</a>, <a href="/web-llvm/docs/api/namespaces/llvm/isd/#afaaeadcd82b42fc0d385a6247bf7bb52">llvm::ISD::isNormalLoad</a>, <a href="/web-llvm/docs/api/namespaces/llvm/isd/#a308088c2d65f8f3955f5fb0f6aca7ccc">llvm::ISD::isNormalStore</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a9b91a92b74c3013078d7cd339fe7dfd4">llvm::isNullOrNullSplat</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a9a194bbc0c2fac222eeb34d5c3ca97d6">llvm::isOneOrOneSplat</a>, <a href="/web-llvm/docs/api/classes/llvm/sdnode/#a2998329e16665f7101fac0ae9faee5c7">llvm::SDNode::isOnlyUserOf</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/hexagon/hexagoniseldagtodag-cpp/#aef5780c081044f78cc93135f94d56d6a">isOpcodeHandled</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64iseldagtodag-cpp/#a371ed2aa38ea07b42bb79e4414f78f39">isOpcWithIntImmediate</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64isellowering-cpp/#a371ed2aa38ea07b42bb79e4414f78f39">isOpcWithIntImmediate</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/arm/armiseldagtodag-cpp/#a5fa1cb1a1d96ce454ea9056f487d718e">isOpcWithIntImmediate</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/powerpc/ppciseldagtodag-cpp/#a5fa1cb1a1d96ce454ea9056f487d718e">isOpcWithIntImmediate</a>, <a href="/web-llvm/docs/api/files/lib/lib/codegen/lib/codegen/selectiondag/scheduledagrrlist-cpp/#aa405be8f26bc0ffcd089589d15327400">isOperandOf</a>, <a href="/web-llvm/docs/api/classes/llvm/sdnode/#a94aa946198a3279b30a6d3a943dede42">llvm::SDNode::isOperandOf</a>, <a href="/web-llvm/docs/api/classes/llvm/sdvalue/#a359dc06bf5ef65d00a6b3f4de3092909">llvm::SDValue::isOperandOf</a>, <a href="/web-llvm/docs/api/files/lib/lib/ir/metadata-cpp/#a30dd6d0a8bb26b2562332856caa54203">isOperandUnresolved</a>, <a href="/web-llvm/docs/api/classes/llvm/selectiondagisel/#a3b4c369d3a5ee9fcd1b68218728b5951">llvm::SelectionDAGISel::isOrEquivalentToAdd</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64isellowering-cpp/#a82b9ffb69b33609760bdf1a56390b7a8">isOrXorChain</a>, <a href="/web-llvm/docs/api/classes/llvm/lazycallgraph/refscc/#af952e1ffaf5cd4bd83b63cf7fb4cb068">llvm::LazyCallGraph::RefSCC::isParentOf</a>, <a href="/web-llvm/docs/api/classes/llvm/lazycallgraph/scc/#a542a7d70121296c36071303e26b68b7a">llvm::LazyCallGraph::SCC::isParentOf</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/powerpc/ppcisellowering-cpp/#a4bbe57bdaf29b707d8015c6268016aaa">isPCRelNode</a>, <a href="/web-llvm/docs/api/structs/llvm/domtreebuilder/semincainfo/#a883785e34f877df86f4408a3aa7f25aa">llvm::DomTreeBuilder::SemiNCAInfo&lt; DomTreeT &gt;::isPermutation</a>, <a href="/web-llvm/docs/api/classes/llvm/sunit/#a6fe37a9ed7e3ddc88a91b16aa3f83d14">llvm::SUnit::isPred</a>, <a href="/web-llvm/docs/api/classes/llvm/sdnode/#aaf99b3ee1d9577ac86d3bf072c7bc789">llvm::SDNode::isPredecessorOf</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64isellowering-cpp/#a24c02372c3ca3dfe2fed1bb12f00bae2">isPredicateCCSettingOp</a>, <a href="/web-llvm/docs/api/files/lib/lib/codegen/lib/codegen/selectiondag/selectiondagisel-cpp/#a41976e1f6ca65fb7830e1f348d751000">IsPredicateKnownToFail</a>, <a href="/web-llvm/docs/api/classes/anonymous-m68kiseldagtodag-cpp-/m68kdagtodagisel/#a6d0983364ce56bbe4d50d55274587c73">anonymous{M68kISelDAGToDAG.cpp}::M68kDAGToDAGISel::IsProfitableToFold</a>, <a href="/web-llvm/docs/api/classes/anonymous-systemziseldagtodag-cpp-/systemzdagtodagisel/#a5c013753f05b14d6d638ffe65860c6f1">anonymous{SystemZISelDAGToDAG.cpp}::SystemZDAGToDAGISel::IsProfitableToFold</a>, <a href="/web-llvm/docs/api/classes/anonymous-x86iseldagtodag-cpp-/x86dagtodagisel/#a6d5b4f84c3dda985bea36681d13bc55b">anonymous{X86ISelDAGToDAG.cpp}::X86DAGToDAGISel::IsProfitableToFold</a>, <a href="/web-llvm/docs/api/classes/llvm/selectiondagisel/#a877a33bf451c611191b8f8dcbbaed4ca">llvm::SelectionDAGISel::IsProfitableToFold</a>, <a href="/web-llvm/docs/api/namespaces/llvm/avr/#a2c128ac074d92126c8983e21aadbd9e4">llvm::AVR::isProgramMemoryAccess</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/arm/armisellowering-cpp/#ac0c5c5dd788201c5df3f6fc9d615a6f8">IsQRMVEInstruction</a>, <a href="/web-llvm/docs/api/classes/anonymous-ppciseldagtodag-cpp-/ppcdagtodagisel/#a678f88e041ed213103cc705ea75323a7">anonymous{PPCISelDAGToDAG.cpp}::PPCDAGToDAGISel::isRotateAndMask</a>, <a href="/web-llvm/docs/api/classes/llvm/selectiondag/#acb0a2de53bba0753825a66fa9d31b390">llvm::SelectionDAG::isSafeToSpeculativelyExecuteNode</a>, <a href="/web-llvm/docs/api/classes/llvm/amdgputargetlowering/#a430354699c0f912f4078f57fcc607319">llvm::AMDGPUTargetLowering::isSDNodeAlwaysUniform</a>, <a href="/web-llvm/docs/api/classes/llvm/targetlowering/#aa67e0a840aaf40e6406d7be705f44af5">llvm::TargetLowering::isSDNodeAlwaysUniform</a>, <a href="/web-llvm/docs/api/classes/llvm/sitargetlowering/#a9226f8a6386f03bffa9a98d07b2ed582">llvm::SITargetLowering::isSDNodeSourceOfDivergence</a>, <a href="/web-llvm/docs/api/classes/llvm/targetlowering/#aa17502133164c96bd0943f2241171ead">llvm::TargetLowering::isSDNodeSourceOfDivergence</a>, <a href="/web-llvm/docs/api/files/lib/lib/codegen/lib/codegen/selectiondag/legalizevectortypes-cpp/#a7e6d0c1c367f6604bb0634e62131cbed">isSETCCorConvertedSETCC</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64iseldagtodag-cpp/#a701a4a459b4a06759797ccf08030067c">isSeveralBitsExtractOpFromShr</a>, <a href="/web-llvm/docs/api/namespaces/llvm/isd/#ac174dc465cbe0e04a0f5e41c0a422124">llvm::ISD::isSEXTLoad</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#abcb678e42ef8094f2b744592ec378feb">llvm::isShiftedInt</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#af0d6fc340d84e22e165e7d069b74f3c5">llvm::isShiftedUInt</a>, <a href="/web-llvm/docs/api/classes/llvm/apint/#a87d50d10274efe9688166584391ae489">llvm::APInt::isSignedIntN</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/arm/armisellowering-cpp/#ad5ca6ec71f3b7fbe0cdf298de7dea6f3">isSignExtended</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64isellowering-cpp/#aae89411ebc82571d39a33d35726f9604">isSignExtended</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/systemz/systemzisellowering-cpp/#a21006f1229b36e0b4780121b74c5b242">isSimpleShift</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/arm/armisellowering-cpp/#ac026c42d33e80060e878a29358f2ed6a">IsSingleInstrConstant</a>, <a href="/web-llvm/docs/api/namespaces/llvm/ppc/#adf912033ee385662cb4e40bd06206b67">llvm::PPC::isSplatShuffleMask</a>, <a href="/web-llvm/docs/api/classes/llvm/sunit/#a65e96694f0d2eef93a9653beba7d12dc">llvm::SUnit::isSucc</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/powerpc/ppciseldagtodag-cpp/#af19deaa02afb7eb6f600c973c6aeebb2">isSWTestOp</a>, <a href="/web-llvm/docs/api/classes/llvm/hexagoninstrinfo/#ad4475ef8d36797ed68e422e259b7b4cf">llvm::HexagonInstrInfo::isToBeScheduledASAP</a>, <a href="/web-llvm/docs/api/files/lib/lib/codegen/lib/codegen/selectiondag/dagcombiner-cpp/#aa142b4be3c3ce29d1c12c39b88ec687d">isTruncateOf</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a87e65296f2a6d9570117a852af342764">llvm::isUInt</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a1a995470163b6d76695cba5bc8dfb529">llvm::isUIntN</a>, <a href="/web-llvm/docs/api/namespaces/llvm/isd/#a7da84980dd2ee06405d74303cfb90485">llvm::ISD::isUNINDEXEDLoad</a>, <a href="/web-llvm/docs/api/namespaces/llvm/isd/#ab5c74add1b228292dae9d97d63b6f27b">llvm::ISD::isUNINDEXEDStore</a>, <a href="/web-llvm/docs/api/classes/llvm/loongarchtargetlowering/#a0cb17d64ed4f7499fba8ffcf1dfca7db">llvm::LoongArchTargetLowering::isUsedByReturnOnly</a>, <a href="/web-llvm/docs/api/classes/llvm/riscvtargetlowering/#a97b1a7342d551c7997c4c2f4f0d44d6d">llvm::RISCVTargetLowering::isUsedByReturnOnly</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/arm/armisellowering-cpp/#abeb31ccfc9e083463bbeee472a765160">isValidBaseUpdate</a>, <a href="/web-llvm/docs/api/namespaces/llvm/aarch64-am/#a0a33ab78776cbb20a7b285e6f165888c">llvm::AArch64_AM::isValidDecodeLogicalImmediate</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/powerpc/ppcisellowering-cpp/#afa8da6f68560141aad9b3bb3e333a2c3">isValidPCRelNode</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/mips/mipsseisellowering-cpp/#a6027bd69e80c1591deaf7dff0257fc5d">isVectorAllOnes</a>, <a href="/web-llvm/docs/api/namespaces/llvm/isd/#a570c0c51d118ee761eb55fc0d2d910f4">llvm::ISD::isVectorShrinkable</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/riscv/riscviseldagtodag-cpp/#afd31764bfbff74f9e25afb3878a1901b">IsVMerge</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/powerpc/ppcisellowering-cpp/#a7a8b9d3036f888a5dfcc7ded26353005">isVMerge</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/powerpc/ppcisellowering-cpp/#a941eb33c376cb0192d0d7e52e21c0c11">isVMerge</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/arm/armisellowering-cpp/#aa47d7aa438a94dc4bdc96008c058d675">isVMOVNMask</a>, <a href="/web-llvm/docs/api/namespaces/llvm/ppc/#a5abe83e8c9d9553cfc708a024c204807">llvm::PPC::isVMRGEOShuffleMask</a>, <a href="/web-llvm/docs/api/namespaces/llvm/ppc/#a3f48ceee4d4e7b13efb21c415b8fc330">llvm::PPC::isVMRGHShuffleMask</a>, <a href="/web-llvm/docs/api/namespaces/llvm/ppc/#ab27448838ea5635fa836a68c3aa97b29">llvm::PPC::isVMRGLShuffleMask</a>, <a href="/web-llvm/docs/api/namespaces/llvm/ppc/#a43b885afb337e155a5f9e5257081de8b">llvm::PPC::isVPKUDUMShuffleMask</a>, <a href="/web-llvm/docs/api/namespaces/llvm/ppc/#aee91c58b3a130d49788e05c85b12dce4">llvm::PPC::isVPKUHUMShuffleMask</a>, <a href="/web-llvm/docs/api/namespaces/llvm/ppc/#ae9f806005e684e4cbd25d76849ee1775">llvm::PPC::isVPKUWUMShuffleMask</a>, <a href="/web-llvm/docs/api/namespaces/llvm/ppc/#aa45ea0323da7012ed4e0f58aef3619bb">llvm::PPC::isVSLDOIShuffleMask</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/mips/mipsseisellowering-cpp/#a2eed8ec2bd648a726180cb04439abf06">isVSplat</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/powerpc/ppciseldagtodag-cpp/#afdac4819808646ff7f3e8f126ee8efc3">isVSXSwap</a>, <a href="/web-llvm/docs/api/structs/anonymous-riscvasmparser-cpp-/riscvoperand/#a6e51b20075aca7e72c747ebe4ce625b9">anonymous{RISCVAsmParser.cpp}::RISCVOperand::isVTypeImm</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/arm/armisellowering-cpp/#af031a4198a6f04d819d799420383bcf1">IsVUZPShuffleNode</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64iseldagtodag-cpp/#a6cce87f0c847986049b5f7194f87416c">isWorthFoldingADDlow</a>, <a href="/web-llvm/docs/api/namespaces/llvm/ppc/#a2a25cc9341eead72b29eb9646e631244">llvm::PPC::isXXBRDShuffleMask</a>, <a href="/web-llvm/docs/api/namespaces/llvm/ppc/#a8bc23d2b734425aad94289c4dc5df21f">llvm::PPC::isXXBRHShuffleMask</a>, <a href="/web-llvm/docs/api/namespaces/llvm/ppc/#a6e40fdad18c650272628e91ecadce173">llvm::PPC::isXXBRQShuffleMask</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/powerpc/ppcisellowering-cpp/#af15ce5608e9ea5ba89ae7deb2e8895c7">isXXBRShuffleMaskHelper</a>, <a href="/web-llvm/docs/api/namespaces/llvm/ppc/#a88c93b88a2a89e226d5312299a4e1790">llvm::PPC::isXXBRWShuffleMask</a>, <a href="/web-llvm/docs/api/namespaces/llvm/ppc/#acb2d86096213925077b7a8b248745e34">llvm::PPC::isXXINSERTWMask</a>, <a href="/web-llvm/docs/api/namespaces/llvm/ppc/#a8bbd98a4e85245f40c2ef2ea6f14e7c6">llvm::PPC::isXXPERMDIShuffleMask</a>, <a href="/web-llvm/docs/api/namespaces/llvm/ppc/#a96447619c3b90a88e75aed44d332114c">llvm::PPC::isXXSLDWIShuffleMask</a>, <a href="/web-llvm/docs/api/files/lib/lib/analysis/lint-cpp/#a45005634b54e2126cb3e6ec0dbc9ade4">isZero</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/arm/armisellowering-cpp/#ad72a699a06faa16c6e8dc15ed5ea2250">isZeroExtended</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64isellowering-cpp/#a3470c7d8e9b267fb5818c968b808e787">isZeroExtended</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/arm/armisellowering-cpp/#a0cfad667c937a3bb6922389aea511897">isZeroOrAllOnes</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/lanai/lanaiisellowering-cpp/#a0cfad667c937a3bb6922389aea511897">isZeroOrAllOnes</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64isellowering-cpp/#a1ed5232dabde8c9cc04bfc41f179213a">isZerosVector</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/arm/armisellowering-cpp/#a9bcc716556b2a8d9c3f06c0a46c243f6">isZeroVector</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/systemz/systemzisellowering-cpp/#a9bcc716556b2a8d9c3f06c0a46c243f6">isZeroVector</a>, <a href="/web-llvm/docs/api/namespaces/llvm/isd/#a35edacef22fcaed7a8681fa573476131">llvm::ISD::isZEXTLoad</a>, <a href="/web-llvm/docs/api/structs/llvm/rdf/dataflowgraph/defstack/#a8378215c88c684d360158d869e3f0c49">llvm::rdf::DataFlowGraph::DefStack::Iterator</a>, <a href="/web-llvm/docs/api/classes/llvm/registry/iterator/#a7976112942726ac39e40f2b92e43504a">llvm::Registry&lt; T &gt;::iterator::iterator</a>, <a href="/web-llvm/docs/api/classes/llvm/binarystreamrefbase/#aad877535f4e84769dc04ae7115c79bb1">llvm::BinaryStreamRefBase&lt; RefType, StreamType &gt;::keep_back</a>, <a href="/web-llvm/docs/api/classes/llvm/binarystreamrefbase/#ae8bb4476ed76bffa9f15addd0f98a34a">llvm::BinaryStreamRefBase&lt; RefType, StreamType &gt;::keep_front</a>, <a href="/web-llvm/docs/api/structs/llvm/binarysubstreamref/#a92e872383f7bcc3fa4147128e58faa9d">llvm::BinarySubstreamRef::keep_front</a>, <a href="/web-llvm/docs/api/structs/llvm/targetexttypekeyinfo/keyty/#a4863b159139209bbd891fb57c533aa7b">llvm::TargetExtTypeKeyInfo::KeyTy::KeyTy</a>, <a href="/web-llvm/docs/api/classes/anonymous-hexagonconstpropagation-cpp-/latticecell/#a3d88d41f41ecd8c95d6ebf4013d08e80">anonymous{HexagonConstPropagation.cpp}::LatticeCell::LatticeCell</a>, <a href="/web-llvm/docs/api/classes/llvm/selectiondag/#a6f1e49f6f347835aa6b5a7423dd364d1">llvm::SelectionDAG::Legalize</a>, <a href="/web-llvm/docs/api/classes/llvm/amdgpulegalizerinfo/#a89e5277b1b90b54ea21a51120f9a4206">llvm::AMDGPULegalizerInfo::legalizeBufferLoad</a>, <a href="/web-llvm/docs/api/classes/llvm/selectiondag/#a74ce53f838a5372200a8e8ec9b135316">llvm::SelectionDAG::LegalizeOp</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64isellowering-cpp/#a77650539aaaa54572ee61d0cf97a3575">legalizeSVEGatherPrefetchOffsVec</a>, <a href="/web-llvm/docs/api/structs/llvm/letrecord/#a9c06c358ed747f6cae25377c01a3dbac">llvm::LetRecord::LetRecord</a>, <a href="/web-llvm/docs/api/structs/llvm/listscope/#af6e380e7a4bb1b79b86ca9485d7ad811">llvm::ListScope::ListScope</a>, <a href="/web-llvm/docs/api/groups/llvmccorevalueconstantexpressions/#gaa025b4042992fcb4ee0a8495cebb32ba">LLVM_ATTRIBUTE_C_DEPRECATED</a>, <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/objectyaml/elfyaml-h/#a44c4cd3d82aeee314a3048b5e7d8b28f">LLVM_YAML_IS_SEQUENCE_VECTOR</a>, <a href="/web-llvm/docs/api/groups/llvmccoremodule/#gaf1ac13437ad369836a46ed7eca8a39bc">LLVMAddNamedMetadataOperand</a>, <a href="/web-llvm/docs/api/groups/llvmccoreinstructionbuilder/#ga4e88ec706fa7c8cc0638d5d01694b0bb">LLVMBuildAggregateRet</a>, <a href="/web-llvm/docs/api/groups/llvmccorevalueconstantscalar/#ga06540cbed28286f40b0f625bf05d0233">LLVMConstInt</a>, <a href="/web-llvm/docs/api/groups/llvmccorevalueconstantscalar/#gadef5d5bf755485cad711fbc7b71a2f46">LLVMConstIntOfStringAndSize</a>, <a href="/web-llvm/docs/api/groups/llvmccorevalueconstantscalar/#gaff70032ea5d57ea05794aa42e83ccd44">LLVMConstReal</a>, <a href="/web-llvm/docs/api/groups/llvmcexecutionengine/#gabdeddb888028f5efec64d710a5c70e83">LLVMCreateGenericValueOfFloat</a>, <a href="/web-llvm/docs/api/groups/llvmcexecutionengine/#ga49e6ddbb4ef1d059831f3dc1e82141d9">LLVMCreateGenericValueOfInt</a>, <a href="/web-llvm/docs/api/groups/llvmccorevaluemetadata/#gae42c7759c81bdd4fce63ac78d0fd42ed">LLVMGetMDNodeOperands</a>, <a href="/web-llvm/docs/api/groups/llvmccoremodule/#ga9c5c38aced0f4851f11036f4fd358114">LLVMGetNamedMetadataNumOperands</a>, <a href="/web-llvm/docs/api/groups/llvmccoremodule/#gae134c00653fcc70b850fb03af410be9c">LLVMGetNamedMetadataOperands</a>, <a href="/web-llvm/docs/api/groups/llvmccorevaluemetadata/#ga49cfd8b93f67c2a9feeb4b86323bd7ed">LLVMReplaceMDNodeOperandWith</a>, <a href="/web-llvm/docs/api/groups/llvmccorevalueinstruction/#gae18d18420591748ed4ced12d7e125fa1">LLVMSetMetadata</a>, <a href="/web-llvm/docs/api/classes/llvm/xcoreinstrinfo/#a3ca4c3ddc5d302c21716484fa8de528d">llvm::XCoreInstrInfo::loadImmediate</a>, <a href="/web-llvm/docs/api/files/lib/lib/profiledata/lib/profiledata/coverage/coveragemappingreader-cpp/#a7851b0072b1b5a3330cda84355b476d3">loadTestingFormat</a>, <a href="/web-llvm/docs/api/classes/llvm/object/elffile/#aeb221ffeffa3ec7eaaa8eecf37b0146d">llvm::object::ELFFile&lt; ELFT &gt;::loadVersionMap</a>, <a href="/web-llvm/docs/api/classes/llvm/lazycallgraph/edgesequence/#af575c6f13e2a60386becb2929bec1940">llvm::LazyCallGraph::EdgeSequence::lookup</a>, <a href="/web-llvm/docs/api/classes/llvm/lazycallgraph/#a2b50db13f4a942ed11f2eaaa6e1709f3">llvm::LazyCallGraph::lookupRefSCC</a>, <a href="/web-llvm/docs/api/classes/llvm/lazycallgraph/#ad234c24f90aaa0fa3f30ac9c750883b6">llvm::LazyCallGraph::lookupSCC</a>, <a href="/web-llvm/docs/api/files/lib/lib/profiledata/lib/profiledata/coverage/coveragemappingreader-cpp/#a7d0e6c07b7e07a14b8006f915ceb6e6d">lookupSections</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/x86/x86isellowering-cpp/#a8d3d665855cae4e412e40108809ea91d">LowerADDRSPACECAST</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/systemz/systemzisellowering-cpp/#a1ad939c6fbe2dc02e6b027a079cc2c22">lowerAddrSpaceCast</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/x86/x86isellowering-cpp/#a72ab512faa829e90b3bac50641315497">LowerADDSUBO_CARRY</a>, <a href="/web-llvm/docs/api/classes/llvm/vetargetlowering/#ae213591aa7e87eacf101620bb4581287">llvm::VETargetLowering::lowerATOMIC_SWAP</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/x86/x86isellowering-cpp/#a3b7d14ce641064b70c1b921dd97afd3e">lowerAtomicArith</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/x86/x86isellowering-cpp/#a5271931ee931884bd81330b82a17f9f9">lowerAtomicArithWithLOCK</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/siisellowering-cpp/#ae213cc887b37c1743d66d2d9542a55c8">lowerBALLOTIntrinsic</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/arm/armisellowering-cpp/#a9a90bcacc0044e2fb442d934fba4f062">LowerBUILD_VECTORToVIDUP</a>, <a href="/web-llvm/docs/api/classes/llvm/systemztargetlowering/#aac7b8dff5ac02a4754d7e10dec681511">llvm::SystemZTargetLowering::LowerCall</a>, <a href="/web-llvm/docs/api/classes/llvm/lanaitargetlowering/#a01fb99881498447f36c9568903275b63">llvm::LanaiTargetLowering::LowerConstantPool</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/arm/armisellowering-cpp/#a7701507d5a5024692d7dfe93a90df8c6">LowerCTPOP</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/x86/x86isellowering-cpp/#aff70f9196e6aa57ec4aeedad1b845056">LowerCTPOP</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/arm/armisellowering-cpp/#a6fd620f229a9cde3e60fc77ab234cd1e">LowerCTTZ</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/riscv/riscvisellowering-cpp/#a948a1ca16b9bc0cfc5c513197f92b4a7">lowerCttzElts</a>, <a href="/web-llvm/docs/api/classes/anonymous-lowermatrixintrinsics-cpp-/lowermatrixintrinsics/#ab3118e33ed28deca370645b8b909fa5a">anonymous{LowerMatrixIntrinsics.cpp}::LowerMatrixIntrinsics::lowerDotProduct</a>, <a href="/web-llvm/docs/api/classes/anonymous-amdgpulowermoduleldspass-cpp-/amdgpulowermodulelds/#a8f69a29bf679c53a8703f5497bba92b2">anonymous{AMDGPULowerModuleLDSPass.cpp}::AMDGPULowerModuleLDS::lowerDynamicLDSVariables</a>, <a href="/web-llvm/docs/api/classes/llvm/hexagontargetlowering/#a3e5b6ff75680bf00cdbdfdf9624baca5">llvm::HexagonTargetLowering::LowerEH_LABEL</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/x86/x86isellowering-cpp/#a785699ec362428cc2e9f5ec9993a8d3f">LowerFCanonicalize</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/siisellowering-cpp/#ad02dfd40a37e1c0fc6365a700c4263dc">lowerFCMPIntrinsic</a>, <a href="/web-llvm/docs/api/classes/llvm/amdgputargetlowering/#a50d6cc7f6a30055914ca1598d668f7bc">llvm::AMDGPUTargetLowering::LowerFP_TO_FP16</a>, <a href="/web-llvm/docs/api/classes/llvm/legalizerhelper/#a04ee040b3b0253a0832ddb7915d55ae1">llvm::LegalizerHelper::lowerFPTRUNC_F64_TO_F16</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/riscv/riscvisellowering-cpp/#a897f4bf6b373f935cca5183ce7d4fd78">lowerGetVectorLength</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/siisellowering-cpp/#a6ffcf0878851c4e84a8c11a68b07e9e7">lowerICMPIntrinsic</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/siisellowering-cpp/#a3dbdbf556532f2d39ea38114cb7a5a23">lowerLaneOp</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/x86/x86isellowering-cpp/#a8245c7a15b6042f1346d528db83476a9">LowerMGATHER</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/x86/x86isellowering-cpp/#af682dbf33bab9c483fe52d9edd85422c">LowerMLOAD</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/arm/armisellowering-cpp/#ab8bc9452845ce93765def17a42addaed">LowerMLOAD</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/x86/x86isellowering-cpp/#a42f26c84bb612e3bd4acb003a3cdbdc7">LowerMSCATTER</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/x86/x86isellowering-cpp/#a8cbf01443deb8406807eaf5afe109f56">LowerMSTORE</a>, <a href="/web-llvm/docs/api/classes/llvm/hexagontargetlowering/#ab6b1675dcd59de9c26f2e5c51b6a9ee3">llvm::HexagonTargetLowering::LowerOperationWrapper</a>, <a href="/web-llvm/docs/api/classes/llvm/systemztargetlowering/#aaa6982f8a2f398fab0881b8806c3ce3f">llvm::SystemZTargetLowering::LowerOperationWrapper</a>, <a href="/web-llvm/docs/api/classes/llvm/targetlowering/#a12431703c17466d24d4bf388ce467ea3">llvm::TargetLowering::LowerOperationWrapper</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/m68k/m68kisellowering-cpp/#a059bb12c2d804e8382b1c8279fbd0dd5">lowerOverflowArithmetic</a>, <a href="/web-llvm/docs/api/classes/llvm/hexagontargetlowering/#a8a3f7047284d9a1811eb22bd8b86c898">llvm::HexagonTargetLowering::LowerSETCC</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/arm/armisellowering-cpp/#a07bef52d3581440af08be07591f29990">LowerShift</a>, <a href="/web-llvm/docs/api/classes/llvm/msp430targetlowering/#a7af439ae3c3279d4bd7d8a7d2a6337f2">llvm::MSP430TargetLowering::LowerShifts</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/riscv/riscvisellowering-cpp/#a602b901d40f2b6bc5bf489a131309eef">lowerShuffleViaVRegSplitting</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64isellowering-cpp/#a563b6bec6866ba0c415468c6eea997dc">LowerSMELdrStr</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/arm/armisellowering-cpp/#adb9776e3c9f8cf35e243fe5585cdafd3">LowerSTORE</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64isellowering-cpp/#a5fa6fc960b3aa12be602d53c619db3fe">LowerSVEIntrinsicDUP</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64isellowering-cpp/#a4eaae576935c3d68f63d9207bd5da494">LowerSVEIntrinsicEXT</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64isellowering-cpp/#a5293602509a91b24af2a2d56204ff5e1">LowerSVEIntrinsicIndex</a>, <a href="/web-llvm/docs/api/classes/anonymous-x86loweramxintrinsics-cpp-/x86loweramxintrinsics/#a79f47e97963f500c113eb9bfee2e5b47">anonymous{X86LowerAMXIntrinsics.cpp}::X86LowerAMXIntrinsics::lowerTileDP</a>, <a href="/web-llvm/docs/api/classes/anonymous-x86loweramxintrinsics-cpp-/x86loweramxintrinsics/#aabc37fb487455e5268d389333bc5c890">anonymous{X86LowerAMXIntrinsics.cpp}::X86LowerAMXIntrinsics::lowerTileLoadStore</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/arm/armisellowering-cpp/#ade7f9db31555260ac7d00622f0ddfff0">LowerTruncate</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/arm/armisellowering-cpp/#a5c40c1942742353e114ba38e5328c91d">LowerTruncatei1</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/arm/armisellowering-cpp/#a000f926363dd7bf704f07931ba721320">LowerUADDSUBO_CARRY</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a0947c6f5b0bdcd54aa4a8447602f8283">llvm::lowerUnaryVectorIntrinsicAsLoop</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/arm/armisellowering-cpp/#ab18e3739ef247af415be89a6d40fc20c">LowerVectorExtend</a>, <a href="/web-llvm/docs/api/classes/anonymous-sifixsgprcopies-cpp-/sifixsgprcopies/#a97298a7350df5e0302d0678065f5a1e2">anonymous{SIFixSGPRCopies.cpp}::SIFixSGPRCopies::lowerVGPR2SGPRCopies</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/x86/x86isellowering-cpp/#aa65c843e4780db206567b16085cb229a">lowerX86FPLogicOp</a>, <a href="/web-llvm/docs/api/namespaces/llvm/sdpatternmatch/#aea6c92b98e36f3faf9e661361a232979">llvm::SDPatternMatch::m_False</a>, <a href="/web-llvm/docs/api/namespaces/llvm/sdpatternmatch/#ad7f6c34d54bdcf3e0341b346bdbe1f30">llvm::SDPatternMatch::m_LegalOp</a>, <a href="/web-llvm/docs/api/namespaces/llvm/sdpatternmatch/#a5d2c4b2e144b3e34036d4b768c82cc6f">llvm::SDPatternMatch::m_LegalType</a>, <a href="/web-llvm/docs/api/namespaces/llvm/sdpatternmatch/#a779f9889de81cdbe82c3d14bcfa1035c">llvm::SDPatternMatch::m_Specific</a>, <a href="/web-llvm/docs/api/namespaces/llvm/sdpatternmatch/#ada593279bd9a12fd24d2a6df68acb356">llvm::SDPatternMatch::m_True</a>, <a href="/web-llvm/docs/api/namespaces/llvm/sdpatternmatch/#ac5c11446a7558ff6cd3f2a1291dde478">llvm::SDPatternMatch::m_Value</a>, <a href="/web-llvm/docs/api/classes/llvm/machinepassregistrynode/#a8587f6cac52094711e570462f5fc659d">llvm::MachinePassRegistryNode&lt; PassCtorTy &gt;::MachinePassRegistryNode</a>, <a href="/web-llvm/docs/api/classes/llvm/machineschedregistry/#a72ce1c7e2337672002f8330681bbdf40">llvm::MachineSchedRegistry::MachineSchedRegistry</a>, <a href="/web-llvm/docs/api/namespaces/llvm/jitlink/#a59286966d629be2e299edc33bb04fdb8">llvm::jitlink::makeAlignmentError</a>, <a href="/web-llvm/docs/api/structs/llvm/knownbits/#a2ed221e7e8b34742e248f6f81ef15f90">llvm::KnownBits::makeGE</a>, <a href="/web-llvm/docs/api/classes/anonymous-valuemapper-cpp-/mdnodemapper/#a19e14dd6bf8fd49e43925ade95aab06d">anonymous{ValueMapper.cpp}::MDNodeMapper::map</a>, <a href="/web-llvm/docs/api/classes/llvm/msgpack/mapdocnode/#a42a79d432d9684765f8d3bcd3ed6a5e7">llvm::msgpack::MapDocNode::MapDocNode</a>, <a href="/web-llvm/docs/api/classes/llvm/codeview/codeviewrecordio/#ad866e9f32981e8b9748dc09079ec83ba">llvm::codeview::CodeViewRecordIO::mapEncodedInteger</a>, <a href="/web-llvm/docs/api/classes/llvm/codeview/codeviewrecordio/#afc358a57ed79d1e05a866b061027e61b">llvm::codeview::CodeViewRecordIO::mapEncodedInteger</a>, <a href="/web-llvm/docs/api/classes/llvm/valuemapper/#a33edb8d7bd7bce78ba42492330cc233a">llvm::ValueMapper::mapMDNode</a>, <a href="/web-llvm/docs/api/files/lib/lib/debuginfo/lib/debuginfo/codeview/typerecordmapping-cpp/#aee6196bb67ae710bbbd44101ea42fc62">mapNameAndUniqueName</a>, <a href="/web-llvm/docs/api/classes/anonymous-debuginfo-cpp-/debugtypeinforemoval/#a121d20c7173eb47c19fae1b58a018a61">anonymous{DebugInfo.cpp}::DebugTypeInfoRemoval::mapNode</a>, <a href="/web-llvm/docs/api/classes/llvm/lazycallgraph/#a85788a67cbcd567d28600d43453e342d">llvm::LazyCallGraph::markDeadFunction</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a80c3b8536d5beae5bcbde7d9b0c58e02">llvm::markRegisterParameterAttributes</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#ac3d063b3cfffeac6b26118598d1f8413">llvm::maskLeadingOnes</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a67de670bede039c1740e54038c8a8986">llvm::maskLeadingZeros</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a79dff91526e31b1a05f59eed6c189eb4">llvm::maskTrailingOnes</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a7a32d8533843aab2ce0254e2e2389c9c">llvm::maskTrailingZeros</a>, <a href="/web-llvm/docs/api/classes/llvm/baseindexoffset/#a7e024fd5176d0d009350eea658ee5f5f">llvm::BaseIndexOffset::match</a>, <a href="/web-llvm/docs/api/structs/llvm/sdpatternmatch/allones-match/#ad021a89634c97d32e2dc592389ceb2a9">llvm::SDPatternMatch::AllOnes_match::match</a>, <a href="/web-llvm/docs/api/structs/llvm/sdpatternmatch/and/#aac592ecddf6eb56f3cbfb0c06db997f0">llvm::SDPatternMatch::And&lt; Preds &gt;::match</a>, <a href="/web-llvm/docs/api/structs/llvm/sdpatternmatch/and-72455f44e09362705844c51a365e177c/#a5c64ed29dce1ef008860fb313b38add7">llvm::SDPatternMatch::And&lt; Pred, Preds... &gt;::match</a>, <a href="/web-llvm/docs/api/classes/llvm/sdpatternmatch/basicmatchcontext/#ad029e96fdf65c93b92b53b034957a619">llvm::SDPatternMatch::BasicMatchContext::match</a>, <a href="/web-llvm/docs/api/structs/llvm/sdpatternmatch/binaryopc-match/#a1a5a03d05823f04a24f6f7b509f55882">llvm::SDPatternMatch::BinaryOpc_match&lt; LHS_P, RHS_P, Commutable, ExcludeChain &gt;::match</a>, <a href="/web-llvm/docs/api/structs/llvm/sdpatternmatch/condcode-match/#a6f5363a097969250ef9f5f9994853951">llvm::SDPatternMatch::CondCode_match::match</a>, <a href="/web-llvm/docs/api/structs/llvm/sdpatternmatch/constantint-match/#a5e7b0daf212c901784d8705f2cc506f8">llvm::SDPatternMatch::ConstantInt_match::match</a>, <a href="/web-llvm/docs/api/structs/llvm/sdpatternmatch/deferredvalue-match/#a0ecf1ae733b711d2dc3a81b03c0a74cc">llvm::SDPatternMatch::DeferredValue_match::match</a>, <a href="/web-llvm/docs/api/structs/llvm/sdpatternmatch/maxmin-match/#afe20fb3ab3d91632fb61aee9810d28c5">llvm::SDPatternMatch::MaxMin_match&lt; LHS_P, RHS_P, Pred_t, Commutable, ExcludeChain &gt;::match</a>, <a href="/web-llvm/docs/api/structs/llvm/sdpatternmatch/not/#ab906653592afe1e3eefcf9957a36e36f">llvm::SDPatternMatch::Not&lt; Pred &gt;::match</a>, <a href="/web-llvm/docs/api/structs/llvm/sdpatternmatch/nuses-match/#a1f04ab89bf200a1f4249b099f2f0bdca">llvm::SDPatternMatch::NUses_match&lt; NumUses, Pattern &gt;::match</a>, <a href="/web-llvm/docs/api/structs/llvm/sdpatternmatch/opcode-match/#a3fd0ecd14a99dfe978b4a3e6503dedf3">llvm::SDPatternMatch::Opcode_match::match</a>, <a href="/web-llvm/docs/api/structs/llvm/sdpatternmatch/operands-match/#a5ea913176a3c958f194dc8d027a778e0">llvm::SDPatternMatch::Operands_match&lt; OpIdx, OpndPreds &gt;::match</a>, <a href="/web-llvm/docs/api/structs/llvm/sdpatternmatch/operands-match-80768645620b5dc10c8aeb520eb8888c/#acbb751b957ad1720795ba5c80cd3582c">llvm::SDPatternMatch::Operands_match&lt; OpIdx, OpndPred, OpndPreds... &gt;::match</a>, <a href="/web-llvm/docs/api/structs/llvm/sdpatternmatch/or/#a5d7c2111fad4e32f68fb17a9a1e4a4ff">llvm::SDPatternMatch::Or&lt; Preds &gt;::match</a>, <a href="/web-llvm/docs/api/structs/llvm/sdpatternmatch/or-72455f44e09362705844c51a365e177c/#ab18966bfeef402ee2af1a5e86f0922a5">llvm::SDPatternMatch::Or&lt; Pred, Preds... &gt;::match</a>, <a href="/web-llvm/docs/api/structs/llvm/sdpatternmatch/sdshuffle-match/#a0c782514e9d367139bab231071a38196">llvm::SDPatternMatch::SDShuffle_match&lt; T0, T1, T2 &gt;::match</a>, <a href="/web-llvm/docs/api/structs/llvm/sdpatternmatch/specificint-match/#a6719b5d3d4004c67653f752f25920436">llvm::SDPatternMatch::SpecificInt_match::match</a>, <a href="/web-llvm/docs/api/structs/llvm/sdpatternmatch/switchcontext/#add6c67bd91e3b57463153096015a65d7">llvm::SDPatternMatch::SwitchContext&lt; NewMatchContext, Pattern &gt;::match</a>, <a href="/web-llvm/docs/api/structs/llvm/sdpatternmatch/ternaryopc-match/#a74f6fd4ceea41f9ff9d6baaa9c6a2e5d">llvm::SDPatternMatch::TernaryOpc_match&lt; T0_P, T1_P, T2_P, Commutable, ExcludeChain &gt;::match</a>, <a href="/web-llvm/docs/api/structs/llvm/sdpatternmatch/tli-pred-match/#a372a4d2c2f6c82ea3fccc38b2a92f619">llvm::SDPatternMatch::TLI_pred_match&lt; Pattern, PredFuncT &gt;::match</a>, <a href="/web-llvm/docs/api/structs/llvm/sdpatternmatch/unaryopc-match/#aa82cb4ad7ffa228901bd32582599254b">llvm::SDPatternMatch::UnaryOpc_match&lt; Opnd_P, ExcludeChain &gt;::match</a>, <a href="/web-llvm/docs/api/structs/llvm/sdpatternmatch/value-bind/#a82f85505db3da1bed5aef0fe3ee620a7">llvm::SDPatternMatch::Value_bind::match</a>, <a href="/web-llvm/docs/api/structs/llvm/sdpatternmatch/value-match/#a0cbfcaa8bfd00d07f68359a1a8716fac">llvm::SDPatternMatch::Value_match::match</a>, <a href="/web-llvm/docs/api/structs/llvm/sdpatternmatch/valuetype-bind/#a6080774c6f80a686b2ddd81dbe84b067">llvm::SDPatternMatch::ValueType_bind::match</a>, <a href="/web-llvm/docs/api/structs/llvm/sdpatternmatch/valuetype-match/#ac489f5d275d3fbaf1cdff546cf564b8f">llvm::SDPatternMatch::ValueType_match&lt; Pattern, PredFuncT &gt;::match</a>, <a href="/web-llvm/docs/api/files/lib/lib/codegen/lib/codegen/selectiondag/dagcombiner-cpp/#ae2e5854cbbb56cb58c6b641d105998db">matchBSwapHWordOrAndAnd</a>, <a href="/web-llvm/docs/api/classes/llvm/amdgpudagtodagisel/#afdcf01d7d3527e56cd6cc217975aac68">llvm::AMDGPUDAGToDAGISel::matchLoadD16FromBuildVector</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/x86/x86isellowering-cpp/#a01f930a0afc6b50e6351d21d012b724d">matchLogicBlend</a>, <a href="/web-llvm/docs/api/files/lib/lib/codegen/lib/codegen/selectiondag/selectiondagaddressanalysis-cpp/#a54243aacf632aa264d595914deb5ad08">matchLSNode</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/siisellowering-cpp/#aa435f2b01aca963d926bd31cd95e7f03">matchPERM</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/x86/x86isellowering-cpp/#a1f5195509d89464589e673074691103a">matchPMADDWD</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/x86/x86isellowering-cpp/#ad36ff51e2d7df1ab19e1f5a0bfe07e98">matchPMADDWD_2</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a08b6d5c69d7933ac65aae84e1b50fa62">llvm::maxIntN</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#af80bd4ec8a9b2f8e7d9d75ab708a55c2">llvm::maxUIntN</a>, <a href="/web-llvm/docs/api/classes/llvm/selectiondagisel/#abfec92a647d46864521a5f9bbc9e2138">llvm::SelectionDAGISel::mayRaiseFPException</a>, <a href="/web-llvm/docs/api/classes/anonymous-scheduledagrrlist-cpp-/regreductionpqbase/#aaae720d8a55a2ddf5a3b795d2a82805a">anonymous{ScheduleDAGRRList.cpp}::RegReductionPQBase::MayReduceRegPressure</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/powerpc/ppciseldagtodag-cpp/#aa5760d31de51afcdd6a97ee28d7d403b">mayUseP9Setb</a>, <a href="/web-llvm/docs/api/classes/anonymous-mipsoptimizepiccall-cpp-/mbbinfo/#a0737b6b75022fcab0f15a8d0bd3f9a54">anonymous{MipsOptimizePICCall.cpp}::MBBInfo::MBBInfo</a>, <a href="/web-llvm/docs/api/structs/llvm/mbbsectionid/#a58443b01d4b9a1c9ee57275d95fc22aa">llvm::MBBSectionID::MBBSectionID</a>, <a href="/web-llvm/docs/api/structs/llvm/mcasmmacro/#a91ca62fe521f4e37babadcf7a5d385ff">llvm::MCAsmMacro::MCAsmMacro</a>, <a href="/web-llvm/docs/api/structs/llvm/mcasmmacro/#a256357eef7cf2db13d6c79b531dac59f">llvm::MCAsmMacro::MCAsmMacro</a>, <a href="/web-llvm/docs/api/structs/llvm/mdnodekeyimpl-a632dbe89953e38d9916f1f9c85a00c6/#aa3b1d4a500150aacea4fb0d1ec75efdf">llvm::MDNodeKeyImpl&lt; DIBasicType &gt;::MDNodeKeyImpl</a>, <a href="/web-llvm/docs/api/structs/llvm/mdnodekeyimpl-19cbd634311fc7c21846f45212f8e51d/#ae1044d74d3e5b3af84598d88017a0b20">llvm::MDNodeKeyImpl&lt; DICommonBlock &gt;::MDNodeKeyImpl</a>, <a href="/web-llvm/docs/api/structs/llvm/mdnodekeyimpl-da9e4b682a4b3039a31f92ca230d6551/#a92dc296b7b60e0848408156781b20ec4">llvm::MDNodeKeyImpl&lt; DICompositeType &gt;::MDNodeKeyImpl</a>, <a href="/web-llvm/docs/api/structs/llvm/mdnodekeyimpl-8118c3d86fcf9b25c96acf40409650f8/#adcf6bf0f98ad306cb64ce7ffec144e09">llvm::MDNodeKeyImpl&lt; DIEnumerator &gt;::MDNodeKeyImpl</a>, <a href="/web-llvm/docs/api/structs/llvm/mdnodekeyimpl-d57e9afcec96ef547af4b59a07c94704/#aa534b4aa66e4209d9c5a6d8d93b8a8db">llvm::MDNodeKeyImpl&lt; DIExpression &gt;::MDNodeKeyImpl</a>, <a href="/web-llvm/docs/api/structs/llvm/mdnodekeyimpl-48409aaf85ebe18e5504af9294f699f7/#a9c007ee764d8142632d2935e598108b2">llvm::MDNodeKeyImpl&lt; DIFile &gt;::MDNodeKeyImpl</a>, <a href="/web-llvm/docs/api/structs/llvm/mdnodekeyimpl-0f7b524265fedd94c532c65a070f3685/#a4af0e089dba18e16b87e85e86e61ac75">llvm::MDNodeKeyImpl&lt; DIGenericSubrange &gt;::MDNodeKeyImpl</a>, <a href="/web-llvm/docs/api/structs/llvm/mdnodekeyimpl-633cc5d3b8e0834f084fa6ef9da68de8/#ab332f9d2f6fb953b3090477a0a5d30d1">llvm::MDNodeKeyImpl&lt; DIGlobalVariable &gt;::MDNodeKeyImpl</a>, <a href="/web-llvm/docs/api/structs/llvm/mdnodekeyimpl-0b55a2b041180b066c6c661c2f699b12/#ad627c06a34ddcbceb00e67b2d23f6ea6">llvm::MDNodeKeyImpl&lt; DIGlobalVariableExpression &gt;::MDNodeKeyImpl</a>, <a href="/web-llvm/docs/api/structs/llvm/mdnodekeyimpl-062269348a83b06524d54dea11c02dab/#aa899300dba2314b04ccffe6b7cb55b1b">llvm::MDNodeKeyImpl&lt; DIImportedEntity &gt;::MDNodeKeyImpl</a>, <a href="/web-llvm/docs/api/structs/llvm/mdnodekeyimpl-be0af8050581057172c949d730a3ccee/#a59433f60f5f45db6fb209146af926335">llvm::MDNodeKeyImpl&lt; DILabel &gt;::MDNodeKeyImpl</a>, <a href="/web-llvm/docs/api/structs/llvm/mdnodekeyimpl-5b54c2b60fded15b1c6d0672bc4152d6/#a7ddc8bbe2e8d61c71b82e011f7a4862f">llvm::MDNodeKeyImpl&lt; DILexicalBlock &gt;::MDNodeKeyImpl</a>, <a href="/web-llvm/docs/api/structs/llvm/mdnodekeyimpl-b63466a543ec5728bc32afd4ff983519/#a72a818d358be112cd337d44068cb951c">llvm::MDNodeKeyImpl&lt; DILexicalBlockFile &gt;::MDNodeKeyImpl</a>, <a href="/web-llvm/docs/api/structs/llvm/mdnodekeyimpl-2b01e7dc5fb21182294e60ed35cddf36/#ab24b963a11ddc0efebe8a87a99bf5709">llvm::MDNodeKeyImpl&lt; DILocalVariable &gt;::MDNodeKeyImpl</a>, <a href="/web-llvm/docs/api/structs/llvm/mdnodekeyimpl-c3f2e4e69b3e4e93737608e5e2acbbb3/#a4efa1994151ff19b20968f61a1ad1994">llvm::MDNodeKeyImpl&lt; DIMacro &gt;::MDNodeKeyImpl</a>, <a href="/web-llvm/docs/api/structs/llvm/mdnodekeyimpl-7a3e4c0afdb8cd9342de18889375273c/#a05946e0d02f157137eee37114953c361">llvm::MDNodeKeyImpl&lt; DIMacroFile &gt;::MDNodeKeyImpl</a>, <a href="/web-llvm/docs/api/structs/llvm/mdnodekeyimpl-943f94e144c5cf1d95fadf3852375c1e/#a066942edba04acb35ffd532f4134fd16">llvm::MDNodeKeyImpl&lt; DIModule &gt;::MDNodeKeyImpl</a>, <a href="/web-llvm/docs/api/structs/llvm/mdnodekeyimpl-7f77e64470d9cbfbea96ebf6fef8bbaa/#a2e81e189c9dcc42509408abc830fdd6e">llvm::MDNodeKeyImpl&lt; DINamespace &gt;::MDNodeKeyImpl</a>, <a href="/web-llvm/docs/api/structs/llvm/mdnodekeyimpl-c92fdcf4d517dcf85367b4d35c9c7c32/#a2791f954759af8da1eab54aa83063f1c">llvm::MDNodeKeyImpl&lt; DIObjCProperty &gt;::MDNodeKeyImpl</a>, <a href="/web-llvm/docs/api/structs/llvm/mdnodekeyimpl-e4185de404eff24c55141228a18450b0/#a7773090aff21c5087a36f883d73f5285">llvm::MDNodeKeyImpl&lt; DIStringType &gt;::MDNodeKeyImpl</a>, <a href="/web-llvm/docs/api/structs/llvm/mdnodekeyimpl-84210282e313a489b0d86e5b4c554c98/#ae5941dda5b53aa344d2ad93646d4f573">llvm::MDNodeKeyImpl&lt; DISubrange &gt;::MDNodeKeyImpl</a>, <a href="/web-llvm/docs/api/structs/llvm/mdnodekeyimpl-faa368e9a849f1379853705e8fc6ebb3/#adeb53eac2ad31e8fd72358d55ff79b77">llvm::MDNodeKeyImpl&lt; DISubroutineType &gt;::MDNodeKeyImpl</a>, <a href="/web-llvm/docs/api/structs/llvm/mdnodekeyimpl-3af434ed0e1c02da5f79ef1cec91fb78/#a2a28f6cbb1601898eddba1ba284ca340">llvm::MDNodeKeyImpl&lt; DITemplateTypeParameter &gt;::MDNodeKeyImpl</a>, <a href="/web-llvm/docs/api/structs/llvm/mdnodekeyimpl-1631382e92c1339e4ac300dbc528d6a2/#a29f0ccf2251bd58a58c48b0de7b1535d">llvm::MDNodeKeyImpl&lt; DITemplateValueParameter &gt;::MDNodeKeyImpl</a>, <a href="/web-llvm/docs/api/structs/llvm/mdnodekeyimpl-790d8f2739f010df55f45d6a1d49d352/#a5e9b70774f382997c37be2028a8c26fe">llvm::MDNodeKeyImpl&lt; GenericDINode &gt;::MDNodeKeyImpl</a>, <a href="/web-llvm/docs/api/structs/llvm/mdnodekeyimpl-4af0d7051d6a9d6ec61ff79a979bea68/#a7d41b466a5e45cb1f341dbdb2a645b21">llvm::MDNodeKeyImpl&lt; MDTuple &gt;::MDNodeKeyImpl</a>, <a href="/web-llvm/docs/api/classes/llvm/mdnodeopskey/#aa628cfe65b6dc4ae7f48348eef171ba8">llvm::MDNodeOpsKey::MDNodeOpsKey</a>, <a href="/web-llvm/docs/api/classes/llvm/equivalenceclasses/member-iterator/#a9d009ab1fb031d8e854808dd4cc33333">llvm::EquivalenceClasses&lt; ElemTy, Compare &gt;::member_iterator::member_iterator</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#ab9a9168454d9535e1d4ef88fb4a3592d">llvm::minIntN</a>, <a href="/web-llvm/docs/api/classes/llvm/selectiondag/#a5877bd47049087f890aed4f0f501ec3f">llvm::SelectionDAG::MorphNodeTo</a>, <a href="/web-llvm/docs/api/classes/llvm/balancedpartitioning/#a238d245e46593cc4a4f912a2bc53984f">llvm::BalancedPartitioning::moveGain</a>, <a href="/web-llvm/docs/api/classes/llvm/intervalmapimpl/nodebase/#ac39f13dd6ea8d7bed1ca4fdeeb409a39">llvm::IntervalMapImpl::NodeBase&lt; std::pair&lt; KeyT, KeyT &gt;, ValT, LeafSize &gt;::moveRight</a>, <a href="/web-llvm/docs/api/classes/llvm/riscvinstrinfo/#a1b4c9c49e603e4b80b3d052b54945426">llvm::RISCVInstrInfo::mulImm</a>, <a href="/web-llvm/docs/api/structs/llvm/cl/multi-val/#abb377721935d50ebf00d43c632ee2579">llvm::cl::multi_val::multi_val</a>, <a href="/web-llvm/docs/api/namespaces/llvm/scalednumbers/#a22a8258f778d9c8d3069d89a611e0abd">llvm::ScaledNumbers::multiply64</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#abd9e8e8a29985fdc362ece3dd0ff5441">llvm::MutableArrayRef</a>, <a href="/web-llvm/docs/api/classes/llvm/mutablearrayref/#acca5e74fa7d80fec49d0f74f1e70c40f">llvm::MutableArrayRef&lt; uint8_t &gt;::MutableArrayRef</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64iseldagtodag-cpp/#a1ae5a309dfa6daaa91e06970ea90aee6">narrowIfNeeded</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/riscv/riscvisellowering-cpp/#a1b85ec97e54e97c227762366bc69c962">narrowIndex</a>, <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/instcombine/instcombinemuldivrem-cpp/#a1d14a70b8f7a753dacc88586d6954900">narrowUDivURem</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/x86/x86isellowering-cpp/#a309d56d62904382ce197ab216f4ec43f">narrowVectorSelect</a>, <a href="/web-llvm/docs/api/namespaces/llvm/sys/unicode/#a4e10ba09dea9d13b485ec2a68efb4f98">llvm::sys::unicode::nearestMatchesForCodepointName</a>, <a href="/web-llvm/docs/api/classes/llvm/runtimepointerchecking/#a6134973479f9ed6eb1920d0fe69b6bc9">llvm::RuntimePointerChecking::needsChecking</a>, <a href="/web-llvm/docs/api/classes/llvm/negator/#a2abe5e7f029b63c7b1bd29ac231ef7fa">llvm::Negator::Negate</a>, <a href="/web-llvm/docs/api/classes/llvm/scheduledagsdnodes/#a15c0200b4b6e12b97d270fbea215443e">llvm::ScheduleDAGSDNodes::newSUnit</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/webassembly/lib/target/webassembly/disassembler/webassemblydisassembler-cpp/#a65e13c057217c221d060184d88638f07">nextLEB</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/hexagon/hexagoncommongep-cpp/#a21cbbab6a6991f925afed97ead5bbf49">node_class</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/hexagon/hexagoncommongep-cpp/#a024b67de8e1a0251f785d326118fc7fb">node_hash</a>, <a href="/web-llvm/docs/api/classes/anonymous-dagcombiner-cpp-/worklistremover/#a4589176f902565cb951c754dca72ca7c">anonymous{DAGCombiner.cpp}::WorklistRemover::NodeDeleted</a>, <a href="/web-llvm/docs/api/classes/anonymous-legalizetypes-cpp-/nodeupdatelistener/#aa976778bc4ac96d362ff62058d8586a7">anonymous{LegalizeTypes.cpp}::NodeUpdateListener::NodeDeleted</a>, <a href="/web-llvm/docs/api/classes/anonymous-selectiondagisel-cpp-/iselupdater/#a0d91928b625f40119d161ceb68726315">anonymous{SelectionDAGISel.cpp}::ISelUpdater::NodeDeleted</a>, <a href="/web-llvm/docs/api/classes/anonymous-selectiondagisel-cpp-/matchstateupdater/#af5c41dc0b4ca074230c9c4fbd4af6407">anonymous{SelectionDAGISel.cpp}::MatchStateUpdater::NodeDeleted</a>, <a href="/web-llvm/docs/api/structs/llvm/selectiondag/dagnodedeletedlistener/#a435a1ddcfc3dfd937580618585b997c0">llvm::SelectionDAG::DAGNodeDeletedListener::NodeDeleted</a>, <a href="/web-llvm/docs/api/classes/anonymous-dagcombiner-cpp-/worklistinserter/#af1c2352b4a44938719e7e8d23025cebc">anonymous{DAGCombiner.cpp}::WorklistInserter::NodeInserted</a>, <a href="/web-llvm/docs/api/classes/anonymous-selectiondagisel-cpp-/iselupdater/#a44d0f836c752cf8d1a28b71aec4ba564">anonymous{SelectionDAGISel.cpp}::ISelUpdater::NodeInserted</a>, <a href="/web-llvm/docs/api/structs/llvm/selectiondag/dagnodeinsertedlistener/#a8c380d22527ccfcb8d778258514328d0">llvm::SelectionDAG::DAGNodeInsertedListener::NodeInserted</a>, <a href="/web-llvm/docs/api/files/lib/lib/demangle/microsoftdemangle-cpp/#aa68e4ee3a5ef683a4cab2799aad55e04">nodeListToNodeArray</a>, <a href="/web-llvm/docs/api/structs/llvm/domtreegraphtraitsbase/#a76c1fdd394a63a9a288b4ec86f3c1349">llvm::DomTreeGraphTraitsBase&lt; Node, ChildIterator &gt;::nodes_begin</a>, <a href="/web-llvm/docs/api/structs/llvm/graphtraits-f31979df437dc9ea1e2269fa80c9ec5c/#ab68f5563491357b55d6f4565d403c246">llvm::GraphTraits&lt; DominatorTree * &gt;::nodes_begin</a>, <a href="/web-llvm/docs/api/structs/llvm/graphtraits-17b04332f83e992c6c30c4bb779c89c8/#ac67fea2843af436dbbbb8f6b229cadd9">llvm::GraphTraits&lt; PostDominatorTree * &gt;::nodes_begin</a>, <a href="/web-llvm/docs/api/structs/llvm/graphtraits-d1ba9f3b34b3379086b936f68d22486f/#afe9019b72c850ca4295ca0de6310d417">llvm::GraphTraits&lt; VPlan * &gt;::nodes_begin</a>, <a href="/web-llvm/docs/api/structs/llvm/domtreegraphtraitsbase/#a77ad0f9d4e66a1aea4d59b35adb2ed62">llvm::DomTreeGraphTraitsBase&lt; Node, ChildIterator &gt;::nodes_end</a>, <a href="/web-llvm/docs/api/structs/llvm/graphtraits-f31979df437dc9ea1e2269fa80c9ec5c/#a1636c2b3156ed2e0843dafe15e3b8ab2">llvm::GraphTraits&lt; DominatorTree * &gt;::nodes_end</a>, <a href="/web-llvm/docs/api/structs/llvm/graphtraits-17b04332f83e992c6c30c4bb779c89c8/#a64792efd5f823a148650b87a788f6708">llvm::GraphTraits&lt; PostDominatorTree * &gt;::nodes_end</a>, <a href="/web-llvm/docs/api/structs/llvm/graphtraits-d1ba9f3b34b3379086b936f68d22486f/#a72eb1bd80d4c3901fd8fff3eaff38d6a">llvm::GraphTraits&lt; VPlan * &gt;::nodes_end</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/hexagon/hexagoncommongep-cpp/#ad675cfabbe3548ea7f9b06c3518c0656">nodes_for_root</a>, <a href="/web-llvm/docs/api/classes/anonymous-legalizetypes-cpp-/nodeupdatelistener/#acf34249f3e61610c017c54e3445dda14">anonymous{LegalizeTypes.cpp}::NodeUpdateListener::NodeUpdated</a>, <a href="/web-llvm/docs/api/classes/llvm/machinepassregistrylistener/#ae1682ead618694c47edd3eeeed34d568">llvm::MachinePassRegistryListener&lt; PassCtorTy &gt;::NotifyAdd</a>, <a href="/web-llvm/docs/api/classes/llvm/registerpassparser/#ad7d78a3306ad32831dd941f12be8d80d">llvm::RegisterPassParser&lt; RegistryClass &gt;::NotifyAdd</a>, <a href="/web-llvm/docs/api/classes/llvm/machinepassregistrylistener/#ad6fa44abecf62f7dd090f50eb4342001">llvm::MachinePassRegistryListener&lt; PassCtorTy &gt;::NotifyRemove</a>, <a href="/web-llvm/docs/api/classes/llvm/registerpassparser/#a43ebe67ad48876c782ee0d206c1498ec">llvm::RegisterPassParser&lt; RegistryClass &gt;::NotifyRemove</a>, <a href="/web-llvm/docs/api/structs/anonymous-hexagoniseldagtodaghvx-cpp-/nullifyingvector/#a63e41c956009cbba44ccdf0cb90c6f8c">anonymous{HexagonISelDAGToDAGHVX.cpp}::NullifyingVector&lt; T &gt;::NullifyingVector</a>, <a href="/web-llvm/docs/api/namespaces/llvm/pdb/#a5ba9d5e5ed1d1ed47cfab7f4eddb45de">llvm::pdb::NumDigits</a>, <a href="/web-llvm/docs/api/files/lib/lib/support/suffixtree-cpp/#aecc364f695b930b0527ab2caafd99d4f">numElementsInSubstring</a>, <a href="/web-llvm/docs/api/classes/llvm/mlinlineadvisor/#aaaec1d89794dccf1f6d02c0e46258796">llvm::MLInlineAdvisor::onPassEntry</a>, <a href="/web-llvm/docs/api/classes/llvm/mlinlineadvisor/#a42079a872d9a000c124cef0d38723741">llvm::MLInlineAdvisor::onPassExit</a>, <a href="/web-llvm/docs/api/classes/llvm/mdnode/#a0796ce4aa726251e0930239aeacd02b4">llvm::MDNode::operator delete</a>, <a href="/web-llvm/docs/api/classes/llvm/mdnode/#abb937630d20f83ee3016e07746e19c0b">llvm::MDNode::operator new</a>, <a href="/web-llvm/docs/api/files/lib/lib/support/memorybuffer-cpp/#a21a44946d964a5e69dfa745bb1e9eabd">operator new</a>, <a href="/web-llvm/docs/api/classes/llvm/dgnode/#aef8e8aba1c6a3c420f115fdd778523c1">llvm::DGNode&lt; DDGNode, DDGEdge &gt;::operator!=</a>, <a href="/web-llvm/docs/api/classes/llvm/lazycallgraph/node/#a990f347b1a7291ed845028292f17b2c1">llvm::LazyCallGraph::Node::operator!=</a>, <a href="/web-llvm/docs/api/structs/anonymous-itaniummanglingcanonicalizer-cpp-/foldingsetnodeidbuilder/#a21bd9c6a098db6f747cbea4fb6eedcc3">anonymous{ItaniumManglingCanonicalizer.cpp}::FoldingSetNodeIDBuilder::operator()</a>, <a href="/web-llvm/docs/api/structs/anonymous-itaniummanglingcanonicalizer-cpp-/profilenode/#a15c78a45e6fbac658bc405e2c8a68996">anonymous{ItaniumManglingCanonicalizer.cpp}::ProfileNode::operator()</a>, <a href="/web-llvm/docs/api/structs/anonymous-itaniummanglingcanonicalizer-cpp-/profilenode/#a86dd41bb27d6fd401a1211713c5f6861">anonymous{ItaniumManglingCanonicalizer.cpp}::ProfileNode::operator()</a>, <a href="/web-llvm/docs/api/structs/false/in-set/#ac0b3199fb9031136ce7c5a568f453dca">false::in_set::operator()</a>, <a href="/web-llvm/docs/api/structs/llvm/loopbodytraits/loopbodyfilter/#a56c3c0bd29b785bdb7ebf85c25f156f3">llvm::LoopBodyTraits::LoopBodyFilter::operator()</a>, <a href="/web-llvm/docs/api/classes/llvm/codeview/typeindex/#a8d7ed478383a42c3b1d82a5400511626">llvm::codeview::TypeIndex::operator+</a>, <a href="/web-llvm/docs/api/structs/llvm/indent/#a8f70a0d062e1a21f4dcbfabe9a6cb90c">llvm::indent::operator+</a>, <a href="/web-llvm/docs/api/classes/llvm/codeview/typeindex/#abf91177328e8668926737a107eacb2cb">llvm::codeview::TypeIndex::operator+=</a>, <a href="/web-llvm/docs/api/structs/llvm/detail/index-iterator/#acf3bf17ba97a4c0b6779f0a00dc58c5e">llvm::detail::index_iterator::operator+=</a>, <a href="/web-llvm/docs/api/classes/llvm/fixedstreamarrayiterator/#a60a24ea3e82f781689317c4f3c5752fc">llvm::FixedStreamArrayIterator&lt; T &gt;::operator+=</a>, <a href="/web-llvm/docs/api/structs/llvm/indent/#a18c7967c3a28ed03ddc613b00bf25524">llvm::indent::operator+=</a>, <a href="/web-llvm/docs/api/classes/llvm/pdb/dbimodulesourcefilesiterator/#a8eec2556cef60d94aa806b96a8939afa">llvm::pdb::DbiModuleSourceFilesIterator::operator+=</a>, <a href="/web-llvm/docs/api/classes/llvm/switchinst/caseiteratorimpl/#a90548c05bbb51941d8b1abdb3346229a">llvm::SwitchInst::CaseIteratorImpl&lt; CaseHandle &gt;::operator+=</a>, <a href="/web-llvm/docs/api/classes/llvm/varstreamarrayiterator/#ac8edc6ce34e19e73f0f687dd6784424e">llvm::VarStreamArrayIterator&lt; ValueType, Extractor &gt;::operator+=</a>, <a href="/web-llvm/docs/api/classes/llvm/codeview/typeindex/#af833f2c6ea5ded09aba6b596c613a4e8">llvm::codeview::TypeIndex::operator-</a>, <a href="/web-llvm/docs/api/structs/llvm/indent/#ab0ae6a923863f212c4cb153a74d78cbc">llvm::indent::operator-</a>, <a href="/web-llvm/docs/api/classes/llvm/codeview/typeindex/#a3bc4190267d90cc30cad732ee3584787">llvm::codeview::TypeIndex::operator-=</a>, <a href="/web-llvm/docs/api/structs/llvm/detail/index-iterator/#abb15694aaf3c0616fa54c192c2444157">llvm::detail::index_iterator::operator-=</a>, <a href="/web-llvm/docs/api/classes/llvm/fixedstreamarrayiterator/#aca8fe7cdf5e5db72eac27adbf7ad90b5">llvm::FixedStreamArrayIterator&lt; T &gt;::operator-=</a>, <a href="/web-llvm/docs/api/structs/llvm/indent/#a466814cea20fb73feff13a035cce98b6">llvm::indent::operator-=</a>, <a href="/web-llvm/docs/api/classes/llvm/pdb/dbimodulesourcefilesiterator/#a2df94d4255a82e7157098c36da17c5df">llvm::pdb::DbiModuleSourceFilesIterator::operator-=</a>, <a href="/web-llvm/docs/api/classes/llvm/switchinst/caseiteratorimpl/#a4c737d915e7f11cc91c8304a5a3e81c0">llvm::SwitchInst::CaseIteratorImpl&lt; CaseHandle &gt;::operator-=</a>, <a href="/web-llvm/docs/api/classes/llvm/diagnosticprinter/#a22100edf15f23db0fbef2269e3b5cad5">llvm::DiagnosticPrinter::operator&lt;&lt;</a>, <a href="/web-llvm/docs/api/classes/llvm/diagnosticprinter/#a8705a248dd3e69a17453f1645de3b6d3">llvm::DiagnosticPrinter::operator&lt;&lt;</a>, <a href="/web-llvm/docs/api/classes/llvm/diagnosticprinter/#a4ec20040f229c3142ab75cc6108032d4">llvm::DiagnosticPrinter::operator&lt;&lt;</a>, <a href="/web-llvm/docs/api/classes/llvm/diagnosticprinter/#a0d2d0755f409439b83d652b7f692a05a">llvm::DiagnosticPrinter::operator&lt;&lt;</a>, <a href="/web-llvm/docs/api/classes/llvm/diagnosticprinter/#a42f885498899b5a6cf22a04de7be6b41">llvm::DiagnosticPrinter::operator&lt;&lt;</a>, <a href="/web-llvm/docs/api/classes/llvm/diagnosticprinter/#a98d727b10663ab46b62b09851bd2759a">llvm::DiagnosticPrinter::operator&lt;&lt;</a>, <a href="/web-llvm/docs/api/classes/llvm/diagnosticprinter/#ab6e2bd99358f9a65c478d8f07af296a9">llvm::DiagnosticPrinter::operator&lt;&lt;</a>, <a href="/web-llvm/docs/api/classes/llvm/diagnosticprinterrawostream/#a0585e0ff2dc9527bfb9277244fe601dc">llvm::DiagnosticPrinterRawOStream::operator&lt;&lt;</a>, <a href="/web-llvm/docs/api/classes/llvm/diagnosticprinterrawostream/#a91291a1f108c1c0407d17ac6fb97b00d">llvm::DiagnosticPrinterRawOStream::operator&lt;&lt;</a>, <a href="/web-llvm/docs/api/classes/llvm/diagnosticprinterrawostream/#abb4ec5ccd7a7287652e6d06239675671">llvm::DiagnosticPrinterRawOStream::operator&lt;&lt;</a>, <a href="/web-llvm/docs/api/classes/llvm/diagnosticprinterrawostream/#a6a1d97574c04155e03997dc6c65146c3">llvm::DiagnosticPrinterRawOStream::operator&lt;&lt;</a>, <a href="/web-llvm/docs/api/classes/llvm/diagnosticprinterrawostream/#aa74f5d97354a7edcf07820103fd46ee1">llvm::DiagnosticPrinterRawOStream::operator&lt;&lt;</a>, <a href="/web-llvm/docs/api/classes/llvm/diagnosticprinterrawostream/#ab7e8b3cb11b62632bc129e58c057b177">llvm::DiagnosticPrinterRawOStream::operator&lt;&lt;</a>, <a href="/web-llvm/docs/api/classes/llvm/diagnosticprinterrawostream/#a873fb5786e952dd8b999e7a3eaadaff3">llvm::DiagnosticPrinterRawOStream::operator&lt;&lt;</a>, <a href="/web-llvm/docs/api/classes/llvm/lazycallgraph/node/#aa6ddc9b5d662f44fe1796351ca5390f5">llvm::LazyCallGraph::Node::operator&lt;&lt;</a>, <a href="/web-llvm/docs/api/classes/llvm/lazycallgraph/scc/#a9caadc9c841ba10afbd2200bec580b18">llvm::LazyCallGraph::SCC::operator&lt;&lt;</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a198dd514b6fcada5bd79b308d0124fbe">llvm::operator&lt;&lt;</a>, <a href="/web-llvm/docs/api/classes/llvm/raw-ostream/#a0901ea2124ad30e3766766e20ed3a73e">llvm::raw_ostream::operator&lt;&lt;</a>, <a href="/web-llvm/docs/api/classes/llvm/raw-ostream/#abcf9b50e849ae41a25c3ac13ab1f1028">llvm::raw_ostream::operator&lt;&lt;</a>, <a href="/web-llvm/docs/api/classes/llvm/raw-ostream/#acabcb5001c45027cf69ca516a38f9e77">llvm::raw_ostream::operator&lt;&lt;</a>, <a href="/web-llvm/docs/api/classes/llvm/raw-ostream/#ae9d57be5c0397ea87d9f634929629c25">llvm::raw_ostream::operator&lt;&lt;</a>, <a href="/web-llvm/docs/api/classes/llvm/raw-ostream/#ae161a943836d575a59a8c84534ed6dcf">llvm::raw_ostream::operator&lt;&lt;</a>, <a href="/web-llvm/docs/api/classes/llvm/raw-ostream/#a45acd041c106c28341db5ef6c38d8125">llvm::raw_ostream::operator&lt;&lt;</a>, <a href="/web-llvm/docs/api/classes/llvm/raw-ostream/#aa0e27cd90adc0b6beb89033845f9823d">llvm::raw_ostream::operator&lt;&lt;</a>, <a href="/web-llvm/docs/api/namespaces/llvm/rdf/anonymous-rdfgraph-cpp-/#a741f459fead991a2b3c794c7dbed370f">llvm::rdf::anonymous{RDFGraph.cpp}::operator&lt;&lt;</a>, <a href="/web-llvm/docs/api/namespaces/llvm/rdf/#aefd178f993c25ba2221f325e426e973d">llvm::rdf::operator&lt;&lt;</a>, <a href="/web-llvm/docs/api/namespaces/llvm/rdf/#a9392b67c13199d71ef8b0f68fcaa8406">llvm::rdf::operator&lt;&lt;</a>, <a href="/web-llvm/docs/api/namespaces/llvm/rdf/#ab96cb4dd553834abae3ea18d0bece32a">llvm::rdf::operator&lt;&lt;</a>, <a href="/web-llvm/docs/api/namespaces/llvm/rdf/#a0273d9393551db6c302a610dfcd0e540">llvm::rdf::operator&lt;&lt;</a>, <a href="/web-llvm/docs/api/namespaces/llvm/rdf/#acfc468883ad1a17a1a04cb067ced93bb">llvm::rdf::operator&lt;&lt;</a>, <a href="/web-llvm/docs/api/namespaces/llvm/rdf/#a2962b57e0dfeef036e53411fecd7f850">llvm::rdf::operator&lt;&lt;</a>, <a href="/web-llvm/docs/api/classes/llvm/sandboxir/dgnode/#aed0ea23a6bea9a8d9432bd79b53c7219">llvm::sandboxir::DGNode::operator&lt;&lt;</a>, <a href="/web-llvm/docs/api/classes/outputbuffer/#ab191048312ffbc7fed536f7544d5910a">OutputBuffer::operator&lt;&lt;</a>, <a href="/web-llvm/docs/api/classes/outputbuffer/#abf3d890bf687463ffbaa9bf31a84be1d">OutputBuffer::operator&lt;&lt;</a>, <a href="/web-llvm/docs/api/classes/outputbuffer/#aafe02c290e94eb230d7d73dbcb694213">OutputBuffer::operator&lt;&lt;</a>, <a href="/web-llvm/docs/api/classes/outputbuffer/#af126aca0530071798774af05adfd87d5">OutputBuffer::operator&lt;&lt;</a>, <a href="/web-llvm/docs/api/classes/outputbuffer/#a02ac79c12cb7d0f5eb135a578e018961">OutputBuffer::operator&lt;&lt;</a>, <a href="/web-llvm/docs/api/classes/outputbuffer/#aed34311c0c80fafb227222866bd75a44">OutputBuffer::operator&lt;&lt;</a>, <a href="/web-llvm/docs/api/classes/llvm/bitvector/#a571c3958ecb1aa9ee1e3178b3544b9ca">llvm::BitVector::operator&lt;&lt;=</a>, <a href="/web-llvm/docs/api/classes/llvm/smallbitvector/#a8118e1a41c440dc86b37014d2d77bff2">llvm::SmallBitVector::operator&lt;&lt;=</a>, <a href="/web-llvm/docs/api/classes/anonymous-hexagonconstpropagation-cpp-/latticecell/#a929b9126db9f78e78e7e2cf35cb0f2b0">anonymous{HexagonConstPropagation.cpp}::LatticeCell::operator=</a>, <a href="/web-llvm/docs/api/classes/llvm/ddgnode/#accdf63db7987e2c51befc218dbf23c13">llvm::DDGNode::operator=</a>, <a href="/web-llvm/docs/api/classes/llvm/ddgnode/#a294539478d1eb721ea18ba41f97653fb">llvm::DDGNode::operator=</a>, <a href="/web-llvm/docs/api/classes/llvm/dgnode/#afd378959efb1aed1a27eb2d01be1e0e7">llvm::DGNode&lt; DDGNode, DDGEdge &gt;::operator=</a>, <a href="/web-llvm/docs/api/classes/llvm/dgnode/#a16f8c40b391815643da5e7ac016241a2">llvm::DGNode&lt; DDGNode, DDGEdge &gt;::operator=</a>, <a href="/web-llvm/docs/api/structs/llvm/indent/#af4d2bc5712d02a6708b42426cb4b8a2f">llvm::indent::operator=</a>, <a href="/web-llvm/docs/api/classes/llvm/piblockddgnode/#acb73a3b9c62727e383e93d0bac6df38b">llvm::PiBlockDDGNode::operator=</a>, <a href="/web-llvm/docs/api/classes/llvm/piblockddgnode/#a1866bf2b3eb3ee1bf9958a0d25346080">llvm::PiBlockDDGNode::operator=</a>, <a href="/web-llvm/docs/api/classes/llvm/simpleddgnode/#a3ce2d77e3c0a6f29f3b82b12e363d1e1">llvm::SimpleDDGNode::operator=</a>, <a href="/web-llvm/docs/api/classes/llvm/simpleddgnode/#a48e9864977966d2bef1d8e2d5217452f">llvm::SimpleDDGNode::operator=</a>, <a href="/web-llvm/docs/api/classes/llvm/smallvector/#acd1bf4a3cc2b247cdeac15790a9e6a1e">llvm::SmallVector&lt; BitWord &gt;::operator=</a>, <a href="/web-llvm/docs/api/classes/llvm/valuemapper/#a4e6ce25d919abcceeeefa6773954847b">llvm::ValueMapper::operator=</a>, <a href="/web-llvm/docs/api/classes/llvm/dgnode/#a239fdd5dd097091dfdc5525304722afb">llvm::DGNode&lt; DDGNode, DDGEdge &gt;::operator==</a>, <a href="/web-llvm/docs/api/classes/llvm/lazycallgraph/node/#aa308f33c44766d2ff81d7ff7928a1791">llvm::LazyCallGraph::Node::operator==</a>, <a href="/web-llvm/docs/api/classes/llvm/bitvector/#a09395da97c764bcd5804c40f1f0bff35">llvm::BitVector::operator&gt;&gt;=</a>, <a href="/web-llvm/docs/api/classes/llvm/smallbitvector/#a936c1e476683479d1f2595bb8e2d9cc3">llvm::SmallBitVector::operator&gt;&gt;=</a>, <a href="/web-llvm/docs/api/classes/llvm/lazycallgraph/edgesequence/#a9eb3f34f8579b89b29f4668378d7cab1">llvm::LazyCallGraph::EdgeSequence::operator[]</a>, <a href="/web-llvm/docs/api/classes/llvm/msgpack/mapdocnode/#aeda90977a3a2d3a4ebf597cbd7b29694">llvm::msgpack::MapDocNode::operator[]</a>, <a href="/web-llvm/docs/api/structs/llvm/object/dataregion/#a632a35d75049631b36806af87bbae818">llvm::object::DataRegion&lt; T &gt;::operator[]</a>, <a href="/web-llvm/docs/api/structs/abstractmanglingparser/operatorinfo/#a457eef7dd9ed96f5be3310083f08a0ac">AbstractManglingParser&lt; Derived, Alloc &gt;::OperatorInfo::OperatorInfo</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/amdgpuisellowering-cpp/#a9ac70ef2ea987d0c021f0c7910e79270">opMustUseVOP3Encoding</a>, <a href="/web-llvm/docs/api/structs/llvm/cl/applicator-04bff82bbcda0b477245670d6314e296/#a86b5907ff88370312e98993236389746">llvm::cl::applicator&lt; NumOccurrencesFlag &gt;::opt</a>, <a href="/web-llvm/docs/api/classes/llvm/targetloweringbase/#a54c9c9791d892ac8cdf9a11c850158d9">llvm::TargetLoweringBase::optimizeFMulOrFDivAsShiftAddBitcast</a>, <a href="/web-llvm/docs/api/classes/llvm/slpvectorizer/boupslp/#afd07d19c7174c06cd7c7415f63596839">llvm::slpvectorizer::BoUpSLP::optimizeGatherSequence</a>, <a href="/web-llvm/docs/api/classes/anonymous-aggressiveinstcombine-cpp-/strncmpinliner/#ac9d71bcb73b24374e675d3ac3b8f5e8b">anonymous{AggressiveInstCombine.cpp}::StrNCmpInliner::optimizeStrNCmp</a>, <a href="/web-llvm/docs/api/structs/llvm/gcov/options/#a8ee1fe2f1a12dba580a5fd0786f6678e">llvm::GCOV::Options::Options</a>, <a href="/web-llvm/docs/api/structs/llvm/yaml/scalartraits-96f7362ea1da512c0a2732407c64df72/#ab8319929b35ca07c4ca53f54d194542a">llvm::yaml::ScalarTraits&lt; FixedSizeString&lt; N &gt; &gt;::output</a>, <a href="/web-llvm/docs/api/structs/llvm/ms-demangle/arraytypenode/#a3f16f23c319db7ddd9fb89380e009870">llvm::ms_demangle::ArrayTypeNode::outputOneDimension</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a94b1e36afbaf95cc035249a6267f9472">llvm::packConstantV2I16</a>, <a href="/web-llvm/docs/api/structs/llvm/inlineasm/constraintinfo/#aa7d317c3dcdf1f805c995e9b3f2cba5f">llvm::InlineAsm::ConstraintInfo::Parse</a>, <a href="/web-llvm/docs/api/structs/abstractmanglingparser/#ac07d70593ff94177a2b659dfd61140fc">AbstractManglingParser&lt; Derived, Alloc &gt;::parseAbiTags</a>, <a href="/web-llvm/docs/api/structs/abstractmanglingparser/#ac07d70593ff94177a2b659dfd61140fc">AbstractManglingParser&lt; ManglingParser&lt; Alloc &gt;, Alloc &gt;::parseAbiTags</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/arm/armisellowering-cpp/#a2ab3403403aae0dd2e28fd96af0e4c39">ParseBFI</a>, <a href="/web-llvm/docs/api/structs/abstractmanglingparser/#ab438097f6264945733cb782df179497a">AbstractManglingParser&lt; Derived, Alloc &gt;::parseExprPrimary</a>, <a href="/web-llvm/docs/api/structs/abstractmanglingparser/#a1854a21eaab3d2bc78f248dea1549288">AbstractManglingParser&lt; Derived, Alloc &gt;::parseFloatingLiteral</a>, <a href="/web-llvm/docs/api/classes/anonymous-aarch64asmparser-cpp-/aarch64asmparser/#adc0358b42d36242d132980b3fe8260de">anonymous{AArch64AsmParser.cpp}::AArch64AsmParser::parseInstruction</a>, <a href="/web-llvm/docs/api/classes/anonymous-x86asmparser-cpp-/x86asmparser/#abf6230cdb8093ea54524821d036b2203">anonymous{X86AsmParser.cpp}::X86AsmParser::parseInstruction</a>, <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/scalar/jumptabletoswitch-cpp/#ad7593156486a0b9a2c48cfd1ab7b29a5">parseJumpTable</a>, <a href="/web-llvm/docs/api/structs/abstractmanglingparser/#aa0d666ea75f1150667fa90343823c5f4">AbstractManglingParser&lt; Derived, Alloc &gt;::parseLocalName</a>, <a href="/web-llvm/docs/api/files/lib/lib/profiledata/itaniummanglingcanonicalizer-cpp/#af6e9ec4d94b9ce3ac8849a43fc579aaf">parseMaybeMangledName</a>, <a href="/web-llvm/docs/api/files/lib/lib/mc/mcwin64eh-cpp/#a7274589f20fb34bb658dbffebb1426c4">parseRegMask</a>, <a href="/web-llvm/docs/api/structs/abstractmanglingparser/#a42f63ed33efd48464560c7a2808c2110">AbstractManglingParser&lt; Derived, Alloc &gt;::parseTemplateParamDecl</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64slshardening-cpp/#a407041f5d2ea26309c1f9071a724314e">parseThunkName</a>, <a href="/web-llvm/docs/api/files/lib/lib/codegen/lib/codegen/asmprinter/codeviewdebug-cpp/#a3c6777bde57e6936246482332f9b6d22">parseVersion</a>, <a href="/web-llvm/docs/api/structs/llvm/dxcontaineryaml/part/#ad65ba1949e181c3fda08d416774b39eb">llvm::DXContainerYAML::Part::Part</a>, <a href="/web-llvm/docs/api/files/lib/lib/codegen/lib/codegen/selectiondag/dagcombiner-cpp/#a466591fe7edc07ef1ffac406020984bd">partitionShuffleOfConcats</a>, <a href="/web-llvm/docs/api/classes/llvm/diexpressioncursor/#a5936f4188ab3407a34414892d9305324">llvm::DIExpressionCursor::peekNextN</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/nvptx/nvptxisellowering-cpp/#a05b3fae8db805d575354f7d359d11c5e">PerformADDCombine</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/arm/armisellowering-cpp/#a7ca64b74f25fc6b568b6446883e80379">PerformADDCombine</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/mips/mipsisellowering-cpp/#a830e51b63befaa067f822c088dd8833b">performADDCombine</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/riscv/riscvisellowering-cpp/#a683c927bf72b145ee57c5c91be458df5">performADDCombine</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64isellowering-cpp/#aca75d170f0dbf6e6473db3ef6148e1d5">performAddCombineForShiftedOperands</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64isellowering-cpp/#afb42a02647e8a6e78e252dd235388ac8">performAddCombineSubShift</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/nvptx/nvptxisellowering-cpp/#af12579ae662d4b706778ef90b989d4fc">PerformADDCombineWithOperands</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/arm/armisellowering-cpp/#a5fd0659783f0d5916ce7af83b808d90a">PerformADDCombineWithOperands</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64isellowering-cpp/#ae2006316fe1239e3e559f680aa00e365">performAddCSelIntoCSinc</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/arm/armisellowering-cpp/#a8e48c97fe5cefbf70aa4e9fa0138c99d">PerformAddcSubcCombine</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64isellowering-cpp/#aef1d70c3a535976917e68bf1626e75c4">performAddDotCombine</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/arm/armisellowering-cpp/#ad951ca5aa57e9482c9d5edfcf7cd1e46">PerformADDECombine</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/arm/armisellowering-cpp/#a9dbbe6acb79ab1e69a57634d58edcf4f">PerformAddeSubeCombine</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64isellowering-cpp/#afc2fb5809753e750c4245a785d06a754">performAddSubCombine</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64isellowering-cpp/#a9444d6cbd4dd097ce374b82c57e189c6">performAddSubIntoVectorOp</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64isellowering-cpp/#aa5a81f781f5f8796139dc49c03a44f02">performAddSubLongCombine</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64isellowering-cpp/#a635ad8d6dba2689cc34e3bb3fb12c2a6">performAddUADDVCombine</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/arm/armisellowering-cpp/#aed7db4aa3ec7143f38592865c2c0455d">PerformADDVecReduce</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/nvptx/nvptxisellowering-cpp/#a6c02410f9bb19b5b6eb61c9711ae4156">PerformANDCombine</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/arm/armisellowering-cpp/#aec3ab4d2802494bdb8b2c3c5343f8254">PerformANDCombine</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/loongarch/loongarchisellowering-cpp/#a14e0400deb65254122edb9e66d7bfcf7">performANDCombine</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/mips/mipsisellowering-cpp/#aa20249b0c2be4c3930493f53d8d4a5e5">performANDCombine</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/mips/mipsseisellowering-cpp/#aa20249b0c2be4c3930493f53d8d4a5e5">performANDCombine</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64isellowering-cpp/#a64b9ecc144bf0b95267b353d6ddf5b9b">performANDCombine</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/riscv/riscvisellowering-cpp/#a0c93589d74f9163f56f3f1200bcf9ad6">performANDCombine</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64isellowering-cpp/#a4764dd7a5c84db5880e9d37d5c1ce949">performANDORCSELCombine</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64isellowering-cpp/#afc0543ffe712dea27f610e198260fc8b">performANDSETCCCombine</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/arm/armisellowering-cpp/#a407b2b727a4e59f73315d53b9836daf6">PerformARMBUILD_VECTORCombine</a>, <a href="/web-llvm/docs/api/classes/llvm/amdgputargetlowering/#a2c8bc97059759cb53b363069723311ef">llvm::AMDGPUTargetLowering::performAssertSZExtCombine</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/arm/armisellowering-cpp/#ab6bb88ba60ff98b8e2c142d472f53717">PerformBFICombine</a>, <a href="/web-llvm/docs/api/classes/llvm/sparctargetlowering/#a9f32b61ceb023325bed9e826ade5d6e4">llvm::SparcTargetLowering::PerformBITCASTCombine</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/arm/armisellowering-cpp/#a51359c8ddfa214a514dbaab1b2ad2d29">PerformBITCASTCombine</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/webassembly/webassemblyisellowering-cpp/#aeeb9c744f747cad16a3508441ea4722f">performBitcastCombine</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/loongarch/loongarchisellowering-cpp/#ada069dd931c50ac8a36e7da178768eeb">performBITREV_WCombine</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/riscv/riscvisellowering-cpp/#ace90a1ae5966f6c7a0830a440698d4c5">performBITREVERSECombine</a>, <a href="/web-llvm/docs/api/classes/llvm/armtargetlowering/#ab051a4c12430b297d1465afcb7cf8485">llvm::ARMTargetLowering::PerformBRCONDCombine</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64isellowering-cpp/#a2a5ac33b69bb7d7687d12dc0dffe9f08">performBRCONDCombine</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64isellowering-cpp/#ab22a8cab92ee5978be7e541e30667c55">performBSPExpandForSVE</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/nvptx/nvptxisellowering-cpp/#a700b0db686d16d5c35f6dcf63659fefb">PerformBUILD_VECTORCombine</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/arm/armisellowering-cpp/#afd8034cb60968e67a0b01c4ae93ada12">PerformBUILD_VECTORCombine</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/riscv/riscvisellowering-cpp/#af84a0dc03b9bdd1ccfd5f88dae1a4aab">performBUILD_VECTORCombine</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64isellowering-cpp/#ad6bb7ee72f79badd15b563bf112de6e5">performBuildVectorCombine</a>, <a href="/web-llvm/docs/api/classes/llvm/armtargetlowering/#a4ba6b9afcc5b700d4c09664b5fa009d9">llvm::ARMTargetLowering::PerformCMOVCombine</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/mips/mipsisellowering-cpp/#adf702ecb841f96bb48f48607543fe438">performCMovFPCombine</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/arm/armisellowering-cpp/#a572a3d6dc485316839e59442fb7dae19">PerformCMPZCombine</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/riscv/riscvisellowering-cpp/#a0048548b4f1cc9455cf3af293d2b52bf">performCONCAT_VECTORSCombine</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64isellowering-cpp/#a8d4e8ce89b104f162a8900ab94461e95">performConcatVectorsCombine</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64isellowering-cpp/#a05ea7c29a0fde5a9a808c50aefd2e0fa">performCONDCombine</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64isellowering-cpp/#a4b8e4441770569e02f67db99773afff0">performCSELCombine</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/arm/armisellowering-cpp/#aae8b403580f3136879e238457f94d7ba">PerformCSETCombine</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64isellowering-cpp/#ae26a970eb40a07c455b1bf8697cb9409">performCTLZCombine</a>, <a href="/web-llvm/docs/api/classes/llvm/aarch64targetlowering/#a960012b61a9977dc7c2d3af3943da953">llvm::AArch64TargetLowering::PerformDAGCombine</a>, <a href="/web-llvm/docs/api/classes/llvm/amdgputargetlowering/#ae8ade4269715b02714b67bdf1a0b9ba5">llvm::AMDGPUTargetLowering::PerformDAGCombine</a>, <a href="/web-llvm/docs/api/classes/llvm/armtargetlowering/#a8e96878324f2ca0f847e369f839cfd23">llvm::ARMTargetLowering::PerformDAGCombine</a>, <a href="/web-llvm/docs/api/classes/llvm/hexagontargetlowering/#a35eced9d40135070fe0e267898a9be26">llvm::HexagonTargetLowering::PerformDAGCombine</a>, <a href="/web-llvm/docs/api/classes/llvm/lanaitargetlowering/#aea68fdcf73cd5da149ce8baf8bb3f3b5">llvm::LanaiTargetLowering::PerformDAGCombine</a>, <a href="/web-llvm/docs/api/classes/llvm/loongarchtargetlowering/#a114238b6f08e91873cbd29bae3f069c3">llvm::LoongArchTargetLowering::PerformDAGCombine</a>, <a href="/web-llvm/docs/api/classes/llvm/mipssetargetlowering/#a23c69653370af251e721680e01303967">llvm::MipsSETargetLowering::PerformDAGCombine</a>, <a href="/web-llvm/docs/api/classes/llvm/mipstargetlowering/#a6b3ae019ac2faf4a810a9b8fa80b747d">llvm::MipsTargetLowering::PerformDAGCombine</a>, <a href="/web-llvm/docs/api/classes/llvm/ppctargetlowering/#ab4ccdcee4c7a2e0892715d0a8094b86e">llvm::PPCTargetLowering::PerformDAGCombine</a>, <a href="/web-llvm/docs/api/classes/llvm/r600targetlowering/#a0101ddec6987012c164530ddbdcc307c">llvm::R600TargetLowering::PerformDAGCombine</a>, <a href="/web-llvm/docs/api/classes/llvm/riscvtargetlowering/#a2d89f95e0a2a13c2a42e9ef5805e6e11">llvm::RISCVTargetLowering::PerformDAGCombine</a>, <a href="/web-llvm/docs/api/classes/llvm/sitargetlowering/#a9930ac25c4e4a7ff566e6301bade01e7">llvm::SITargetLowering::PerformDAGCombine</a>, <a href="/web-llvm/docs/api/classes/llvm/sparctargetlowering/#a975d8653451eccbb54e12c11b39f1990">llvm::SparcTargetLowering::PerformDAGCombine</a>, <a href="/web-llvm/docs/api/classes/llvm/systemztargetlowering/#aaabd76316f928d47453720192a3b39a0">llvm::SystemZTargetLowering::PerformDAGCombine</a>, <a href="/web-llvm/docs/api/classes/llvm/targetlowering/#a041dc0924ebd52a3eda7e1a22c00310b">llvm::TargetLowering::PerformDAGCombine</a>, <a href="/web-llvm/docs/api/classes/llvm/vetargetlowering/#a671d25ff295d4c1ec9b55fbfc984af32">llvm::VETargetLowering::PerformDAGCombine</a>, <a href="/web-llvm/docs/api/classes/llvm/x86targetlowering/#a0a91c61d0657477fe6583b566dca7fb7">llvm::X86TargetLowering::PerformDAGCombine</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/mips/mipsisellowering-cpp/#a4855642780c43259ecd18ea1bce3f0d3">performDivRemCombine</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/mips/mipsseisellowering-cpp/#a1cb3d0ba0717491c0c28dcc2e4b3d152">performDSPShiftCombine</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64isellowering-cpp/#a08e1234497dd7fb39211e46523f02459">performDUPCombine</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64isellowering-cpp/#a88130de22a0c1eefe0ff49acda2ca4fd">performDupLane128Combine</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64isellowering-cpp/#a6408862dee3fedb95b41b72c9b8edeb6">performExtBinopLoadFold</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/arm/armisellowering-cpp/#ac2452330035d212f79a73e61ce9b923f">PerformExtendCombine</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64isellowering-cpp/#ad4765786a8a3de00320df895defc3250">performExtendCombine</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/nvptx/nvptxisellowering-cpp/#a0b81257e203b649db1e3ea511e5f3a3d">PerformEXTRACTCombine</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/arm/armisellowering-cpp/#a172a1f5983db0d10ae90c0d3f5beccdb">PerformExtractEltCombine</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/arm/armisellowering-cpp/#a00afc372e6cccfa7fd2904fde074a757">PerformExtractEltToVMOVRRD</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64isellowering-cpp/#aab253557e698e63e5f05d8d9dd1d91f5">performExtractSubvectorCombine</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64isellowering-cpp/#aefd957dcc1874b25b5b758324370d20d">performExtractVectorEltCombine</a>, <a href="/web-llvm/docs/api/classes/llvm/amdgputargetlowering/#ae0d935eaffbef9423e07ac82afb5eeb3">llvm::AMDGPUTargetLowering::performFAbsCombine</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/arm/armisellowering-cpp/#ae5e5f93737f5c911440a221ddedf8a64">PerformFADDCombine</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/nvptx/nvptxisellowering-cpp/#a2ce1fcf4e82d82ce6c46cb189b1100a3">PerformFADDCombine</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64isellowering-cpp/#a2f6ed7bfd084f49c2369eec4c74495a3">performFADDCombine</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/nvptx/nvptxisellowering-cpp/#a5d3cc5ce2199f840a6a9273c2285746e">PerformFADDCombineWithOperands</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/arm/armisellowering-cpp/#a3baa54d2ae1c98e5d8ae5af8acdf82c8">PerformFADDVCMLACombine</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/arm/armisellowering-cpp/#a116d9b245fc4dd2793e97045b292ffa6">PerformFAddVSelectCombine</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64isellowering-cpp/#a77e5d35ccfe68c41092edc168cfb393e">performFirstTrueTestVectorCombine</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64isellowering-cpp/#a4a73ebacb24d087b199805b801f61507">performFlagSettingCombine</a>, <a href="/web-llvm/docs/api/classes/llvm/amdgputargetlowering/#a6913e341612419ecb5b860b6759b929c">llvm::AMDGPUTargetLowering::performFNegCombine</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/riscv/riscvisellowering-cpp/#a7fca4dc2eee895ba0f0cc33cd3ca6c4d">performFP_TO_INT_SATCombine</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/riscv/riscvisellowering-cpp/#aed0a6ba299e2e585945210e2c39ac2ef">performFP_TO_INTCombine</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/arm/armisellowering-cpp/#a8d527926779350200f34b7c3fc12a95c">PerformFPExtendCombine</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64isellowering-cpp/#a8b803a5cecda412b4f4984ad8db7201e">performFPExtendCombine</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64isellowering-cpp/#aa7054eb07a4962c7516115555800c017">performFpToIntCombine</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64isellowering-cpp/#a856202032515a6113c3de53d575f2d33">performGatherLoadCombine</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64isellowering-cpp/#a20421c306f02a92c47eef00c2a1f02f8">performGLD1Combine</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64isellowering-cpp/#a40c243011cdda005e97448378d575096">performGlobalAddressCombine</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/arm/armisellowering-cpp/#ade8c7b6c75d72baebf1ac6d244b9fca5">PerformHWLoopCombine</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/riscv/riscvisellowering-cpp/#a4c4ced6d8064c639d791e53119774fcf">performINSERT_VECTOR_ELTCombine</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/arm/armisellowering-cpp/#a57984ebd9271c38d02eb92b050f5bcee">PerformInsertEltCombine</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/arm/armisellowering-cpp/#aaece9d12c539bbab91aff76ea7e95096">PerformInsertSubvectorCombine</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64isellowering-cpp/#afa4334801ad99c95a1b5fd0f417e16af">performInsertSubvectorCombine</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64isellowering-cpp/#aecebd3286d7e5e48086b22673717d22c">performInsertVectorEltCombine</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/loongarch/loongarchisellowering-cpp/#a001a6e7473d9f11917ec04f38e3cb498">performINTRINSIC_WO_CHAINCombine</a>, <a href="/web-llvm/docs/api/classes/llvm/armtargetlowering/#a42aa092f2811f72cad69b42cc2e4bb64">llvm::ARMTargetLowering::PerformIntrinsicCombine</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64isellowering-cpp/#af95a8dd3a4e9b403d57b68b5cbda46e6">performIntrinsicCombine</a>, <a href="/web-llvm/docs/api/classes/llvm/amdgputargetlowering/#ae4ec834dd7b4ce858321ecad900e9363">llvm::AMDGPUTargetLowering::performIntrinsicWOChainCombine</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64isellowering-cpp/#a03b14e6aca1277bdee37639aec700ba7">performIntToFpCombine</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64isellowering-cpp/#a076775accdfd3a4707279b9636a4986b">performLastTrueTestVectorCombine</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64isellowering-cpp/#a7b49e80a5c71aff0a4a6d6a637cafe3f">performLD1Combine</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64isellowering-cpp/#aae814004d3aa90fb312b7ac62cedb284">performLD1ReplicateCombine</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64isellowering-cpp/#aed80d9ad70fe74f3136dd25a2eee1c47">performLDNT1Combine</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/arm/armisellowering-cpp/#a4118089abb4cbadaf4b698cbbe05154f">PerformLOADCombine</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64isellowering-cpp/#ae60f4de0d1e0dac32141edcacb8d20c3">performLOADCombine</a>, <a href="/web-llvm/docs/api/classes/llvm/amdgputargetlowering/#a13463f9ee8babeef33857cbbc8ea4af1">llvm::AMDGPUTargetLowering::performLoadCombine</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/arm/armisellowering-cpp/#a375638c9ba231abce7be8b8130079499">PerformLongShiftCombine</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64isellowering-cpp/#ad50cb0376d697cd4ca4f6469bd6bd25c">performMaskedGatherScatterCombine</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/riscv/riscvisellowering-cpp/#a5991e29bae68e989e978dc600f93b48e">performMemPairCombine</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/arm/armisellowering-cpp/#afe3fc9a96e843f0a30a80d4af77c1b26">PerformMinMaxCombine</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64isellowering-cpp/#ac1e566876b6ec934e149faae1a9b6f74">performMSTORECombine</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/nvptx/nvptxisellowering-cpp/#a358247b6568a582423b4184574e950bc">PerformMULCombine</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/arm/armisellowering-cpp/#ae57c77c91d8ca534534565c26afee2da">PerformMULCombine</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/mips/mipsseisellowering-cpp/#a11579efb56ca3f28a43e11ddf6011a1d">performMULCombine</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/riscv/riscvisellowering-cpp/#aa26e9cc2dafb4d8b4af1d6e8f252ef09">performMULCombine</a>, <a href="/web-llvm/docs/api/classes/llvm/amdgputargetlowering/#ab049ba889709df922c683e1961c32ae9">llvm::AMDGPUTargetLowering::performMulCombine</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64isellowering-cpp/#a08ab6672869d33da27a1fb4f09602dd7">performMulCombine</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/nvptx/nvptxisellowering-cpp/#a85cbf79249f0c5054e0ff0ab3f351090">PerformMULCombineWithOperands</a>, <a href="/web-llvm/docs/api/classes/llvm/amdgputargetlowering/#a3e110576778e9ccf929885efddeea4aa">llvm::AMDGPUTargetLowering::performMulhsCombine</a>, <a href="/web-llvm/docs/api/classes/llvm/amdgputargetlowering/#a09d46d8519c83130e03376d0d2e0008a">llvm::AMDGPUTargetLowering::performMulhuCombine</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64isellowering-cpp/#aed1948f48d09629d7b5f3883119336b7">performMULLCombine</a>, <a href="/web-llvm/docs/api/classes/llvm/amdgputargetlowering/#ae60d2a6d5da1fa05bb8e59e09fb72612">llvm::AMDGPUTargetLowering::performMulLoHiCombine</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64isellowering-cpp/#a147c639e2ca29ad3a47362caa10562e8">performMulVectorCmpZeroCombine</a>, <a href="/web-llvm/docs/api/classes/llvm/armtargetlowering/#a589928ae94c1e14b50e374c6a1146c60">llvm::ARMTargetLowering::PerformMVEExtCombine</a>, <a href="/web-llvm/docs/api/classes/llvm/armtargetlowering/#a35a55a457bfc044d33bdeb4811532531">llvm::ARMTargetLowering::PerformMVETruncCombine</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/arm/armisellowering-cpp/#a77f2232fb1d07b3f88edaef89e94e673">PerformMVEVLDCombine</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/arm/armisellowering-cpp/#a4d6307dece29d3f347afff0ba4f2c2cd">PerformMVEVMULLCombine</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64isellowering-cpp/#a6bf8361890dacf0c32272b056acff135">performNegCSelCombine</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64isellowering-cpp/#a2fbb20906245b5a07551c13da1409712">performNEONPostLDSTCombine</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64isellowering-cpp/#a208e565c7a2bbd5703fcf565c790934e">performNVCASTCombine</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/arm/armisellowering-cpp/#ab81a857a51f1d25a352fc51569f079a0">PerformORCombine</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/loongarch/loongarchisellowering-cpp/#a3cb4731330867b7a71460d3f4daa752e">performORCombine</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/mips/mipsisellowering-cpp/#abcb6ebd6de53d9ed63cd065dd4128261">performORCombine</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/mips/mipsseisellowering-cpp/#abcb6ebd6de53d9ed63cd065dd4128261">performORCombine</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64isellowering-cpp/#a33f99c1c02a48f20e7ec9d30d11d093c">performORCombine</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/riscv/riscvisellowering-cpp/#a4798b448246e74d657035d49de0e648d">performORCombine</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/arm/armisellowering-cpp/#af6cad5c1ed13af84b4034a144841a48a">PerformORCombine_i1</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/arm/armisellowering-cpp/#a963a08f31bbf8cb9396ff5214bc7ae26">PerformORCombineToBFI</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64isellowering-cpp/#ac58bff1dbe11572c7b2150fc2ffda1b1">performOrXorChainCombine</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64isellowering-cpp/#abdbf7e16d7027d0bbbc9d4e8bf100840">performPostLD1Combine</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/arm/armisellowering-cpp/#a1d0f22bfc290fd2cb53c9486286359df">PerformPREDICATE_CASTCombine</a>, <a href="/web-llvm/docs/api/classes/llvm/amdgputargetlowering/#ad9d34da62b4146ef6290977107ea7ead">llvm::AMDGPUTargetLowering::performRcpCombine</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/arm/armisellowering-cpp/#ada94cd83b8b150c87b337c156f027c3c">PerformReduceShuffleCombine</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64isellowering-cpp/#af121f09f2d04bed8fb532a82bceaa576">performReinterpretCastCombine</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/nvptx/nvptxisellowering-cpp/#a7bd1aee507cb5d38c758c9d8620fb629">PerformREMCombine</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64isellowering-cpp/#a596ebebe073bb9a8568f898a4c2a06f6">performScalarToVectorCombine</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64isellowering-cpp/#ad9d322dc7ec082cd00e94e7888b78a43">performScatterStoreCombine</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/arm/armisellowering-cpp/#a2d87a7cc93a308acb6482288fea2bd7c">PerformSELECTCombine</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/riscv/riscvisellowering-cpp/#ac82e376bb0f509a7df81b213df951293">performSELECTCombine</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/mips/mipsisellowering-cpp/#add39487738bda59bdf85c85cb21b7e9a">performSELECTCombine</a>, <a href="/web-llvm/docs/api/classes/llvm/amdgputargetlowering/#a66904f0583c44a66125515e02e4905b1">llvm::AMDGPUTargetLowering::performSelectCombine</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64isellowering-cpp/#a3580959284fc1395f017d102336eb695">performSelectCombine</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/nvptx/nvptxisellowering-cpp/#ae2780d9409416f3a9ba64201fd887888">PerformSETCCCombine</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/mips/mipsseisellowering-cpp/#ad2e1f2a7410e4a84e5ef34bf5d9db5e5">performSETCCCombine</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/riscv/riscvisellowering-cpp/#a2caf0087e5ae1170754a8a4503df9a98">performSETCCCombine</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/loongarch/loongarchisellowering-cpp/#a2dec0cffd4ecd689da9a7901b8b90124">performSETCCCombine</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/webassembly/webassemblyisellowering-cpp/#a7d7ccddfc054f29d7bac995d70adb6e8">performSETCCCombine</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64isellowering-cpp/#aa26d28bee621b8087f1521482dc3b825">performSETCCCombine</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64isellowering-cpp/#abcaf1212adde88b8addaf1060c459819">performSetccMergeZeroCombine</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64isellowering-cpp/#aa7b5373efa0bde041422551595378b61">performSetCCPunpkCombine</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/arm/armisellowering-cpp/#a391272ef81598a4a25763b2f35809615">PerformShiftCombine</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/nvptx/nvptxisellowering-cpp/#afc4e1d1bb4f52d736313de3c06170381">PerformSHLCombine</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/mips/mipsisellowering-cpp/#a6d21a959b41eb8c9bf28105d72fdbd43">performSHLCombine</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/mips/mipsseisellowering-cpp/#a6d21a959b41eb8c9bf28105d72fdbd43">performSHLCombine</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64isellowering-cpp/#a24edd3104fd2ecba03dd7ca79104295d">performSHLCombine</a>, <a href="/web-llvm/docs/api/classes/llvm/amdgputargetlowering/#a4a2c60919236f6bec42a5a1cd2e0fadb">llvm::AMDGPUTargetLowering::performShlCombine</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/arm/armisellowering-cpp/#ad8eb465f75fcd8db9f348cbbb24194c1">PerformSHLSimplify</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/arm/armisellowering-cpp/#a8339ecd5fb85de6da0eb6bf6c38a4eb0">PerformShuffleVMOVNCombine</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/riscv/riscvisellowering-cpp/#a9843d498d81fb04dfb533d4702589ae8">performSIGN_EXTEND_INREGCombine</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/arm/armisellowering-cpp/#a82745b7ba6baed8c8e0af284dadb90a5">PerformSignExtendInregCombine</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64isellowering-cpp/#a72895c7f66e26be35e106221a2ab26ae">performSignExtendInRegCombine</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64isellowering-cpp/#a60f3ecc52d65b8827909808283319dfa">performSignExtendSetCCCombine</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64isellowering-cpp/#a4b5bb7ddabde61f69fdb9785410078ac">performSpliceCombine</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/arm/armisellowering-cpp/#af99f8aa9b9d9dddc47ec39b12a1eb02d">PerformSplittingMVEEXTToWideningLoad</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/arm/armisellowering-cpp/#afbc0dc4ba278fb4634893dc0c64b0676">PerformSplittingToWideningLoad</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/riscv/riscvisellowering-cpp/#ada4201742fab8916f9da75acd2b58fc1">performSRACombine</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/mips/mipsseisellowering-cpp/#a56ba18b7bb062d32ea351c6349a415c6">performSRACombine</a>, <a href="/web-llvm/docs/api/classes/llvm/amdgputargetlowering/#a801abfb2be28ad60d1a5f79828e99a41">llvm::AMDGPUTargetLowering::performSraCombine</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/loongarch/loongarchisellowering-cpp/#a5885643f7123cbe2d37a298d2551c9e1">performSRLCombine</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/mips/mipsseisellowering-cpp/#ab2fc845ce9d296eb2a7532f49d236b0c">performSRLCombine</a>, <a href="/web-llvm/docs/api/classes/llvm/amdgputargetlowering/#a89077a6acaf53615241018f1013dc349">llvm::AMDGPUTargetLowering::performSrlCombine</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64isellowering-cpp/#a6d287a92051d679a9eb264a553c64ffd">performST1Combine</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64isellowering-cpp/#a13534e47159f35c97e261aac72664214">performSTNT1Combine</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/arm/armisellowering-cpp/#a1ea4fa7098d682c8f0c1d00e09a2b40c">PerformSTORECombine</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64isellowering-cpp/#ad19eb01bd287efda27e7bc5ba67cd144">performSTORECombine</a>, <a href="/web-llvm/docs/api/classes/llvm/amdgputargetlowering/#ad85146c9cfc75b8fe84203e7b920b9e2">llvm::AMDGPUTargetLowering::performStoreCombine</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/nvptx/nvptxisellowering-cpp/#aa47f5523ced3ce0315f8d8ae63c22b18">PerformStoreCombineHelper</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/nvptx/nvptxisellowering-cpp/#a16b3daa8441d682b96ba0986fb162ed4">PerformStoreParamCombine</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/nvptx/nvptxisellowering-cpp/#a87b4ada1bfe6459bbaf173402d879bfe">PerformStoreRetvalCombine</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64isellowering-cpp/#a7b0f2aa7553db086084d3af12309181c">performSubAddMULCombine</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/lanai/lanaiisellowering-cpp/#acaa7667e3eb47c2528ee28df06d25ee1">PerformSUBCombine</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/arm/armisellowering-cpp/#a111643e86a00d697a134123e45817e14">PerformSUBCombine</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/riscv/riscvisellowering-cpp/#a6e70fa211896e5350b5a3ad81273a047">performSUBCombine</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/mips/mipsisellowering-cpp/#a9a5205b95660638f4c7d889f588251e7">performSUBCombine</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/arm/armisellowering-cpp/#aa83ed6897660185d0da121257baef9c4">PerformSubCSINCCombine</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64isellowering-cpp/#afe728440df980a14ddaa125c441496cc">performSubsToAndsCombine</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64isellowering-cpp/#ab5aa3058a584e6bc0e5b94db121422eb">performSunpkloCombine</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64isellowering-cpp/#a267cdbd87c30830568cb74844b0e489c">performSVEAndCombine</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64isellowering-cpp/#a8d8e109ce3c796c31524f5a06dd745ac">performSVEMulAddSubCombine</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64isellowering-cpp/#af246e1e2988325698821d504157ed804">performTBZCombine</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/riscv/riscvisellowering-cpp/#aef2ca69d18797d6709fade0d00b0a286">performTRUNCATECombine</a>, <a href="/web-llvm/docs/api/classes/llvm/amdgputargetlowering/#aa90790617dff98c702c09eb5e62e7430">llvm::AMDGPUTargetLowering::performTruncateCombine</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64isellowering-cpp/#a48a325f68cd666c7ee8808c5e224192c">performTruncateCombine</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/webassembly/webassemblyisellowering-cpp/#aafe4b0329b540edc331b00b6f669a636">performTruncateCombine</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64isellowering-cpp/#ad657d5a1d3a2813dbd073c235119c7e8">performUADDVCombine</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/arm/armisellowering-cpp/#adac55a5ab0773a88dd987c4610e2ed59">PerformUMLALCombine</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64isellowering-cpp/#a47e64a2f9eb3ade81edd0d1e20034ec1">performUnpackCombine</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64isellowering-cpp/#a8bdc70b2f7ce13fccad6913d54322dcf">performUzpCombine</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/arm/armisellowering-cpp/#a4d29144f0f49ccc2a115d389beaef36e">PerformVCMPCombine</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/arm/armisellowering-cpp/#a179a8cd2adc83f28bc70fed3ee8fde0b">PerformVCVTCombine</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/arm/armisellowering-cpp/#a153df73802d794646f81fb17c8dc5d17">PerformVDUPCombine</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/arm/armisellowering-cpp/#a57a099df9c79ef37ef7f89374247ac0e">PerformVDUPLANECombine</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/arm/armisellowering-cpp/#a90bba043b3ae7c24c251d61798920475">PerformVECREDUCE_ADDCombine</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64isellowering-cpp/#a6d8fbde7afd8f90c51d6001d0144b1c8">performVecReduceAddCombine</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64isellowering-cpp/#a436aed4536d617f9ac1a208273150ac0">performVecReduceAddCombineWithUADDLP</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64isellowering-cpp/#a49ed4ed152a2f6e8533ccac1deb10ca0">performVecReduceBitwiseCombine</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/arm/armisellowering-cpp/#a309ad0236599847afc64e0ab08fca23f">PerformVECTOR_REG_CASTCombine</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/arm/armisellowering-cpp/#a8544593225835a30146f86a3187740e7">PerformVECTOR_SHUFFLECombine</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/riscv/riscvisellowering-cpp/#a90089c4b79f869ee82ea85c2a737921a">performVECTOR_SHUFFLECombine</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/webassembly/webassemblyisellowering-cpp/#a86a5f246076a9ff2cba6a1b9ff58c4bf">performVECTOR_SHUFFLECombine</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64isellowering-cpp/#a5c12d92b2d9e291ad311d1468da07410">performVectorCompareAndMaskUnaryOpCombine</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64isellowering-cpp/#a31cdc023846d0798543e1fd10937005a">performVectorExtCombine</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/webassembly/webassemblyisellowering-cpp/#a45e1707fbf027e87ccca3b9d17cd8c6b">performVectorExtendCombine</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/webassembly/webassemblyisellowering-cpp/#ac2921375cd7404c088320b75e5df53c6">performVectorExtendToFPCombine</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64isellowering-cpp/#a7e495837f173dea1e6919b589d315f67">performVectorShiftCombine</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/webassembly/webassemblyisellowering-cpp/#a8a9e8cccbe98907e9c282728ab9ea7c0">performVectorTruncZeroCombine</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/riscv/riscvisellowering-cpp/#aba2bb778924793120e1a03fb10f0682a">performVFMADD_VLCombine</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/arm/armisellowering-cpp/#a7010007dcac40b070c67842b07a3845b">PerformVLDCombine</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/arm/armisellowering-cpp/#ace623ded66eb6a65f791b3ab555337fc">PerformVMOVDRRCombine</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/arm/armisellowering-cpp/#a19d36e331487399aaac4f18bac0c7956">PerformVMOVhrCombine</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/arm/armisellowering-cpp/#aaec24048b5502da3e426b474be7e6b4d">PerformVMOVNCombine</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/arm/armisellowering-cpp/#a40eb7d32bd58dfbdde6c632446a56828">PerformVMOVrhCombine</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/arm/armisellowering-cpp/#aa98ade29969ff63557a3a9594f95891a">PerformVMOVRRDCombine</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/arm/armisellowering-cpp/#ab245ac37eac3c3ba9c6e8cfa310f4a46">PerformVMULCombine</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/arm/armisellowering-cpp/#a30dc6de174502314903dfcbf8d176cea">PerformVMulVCTPCombine</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/riscv/riscvisellowering-cpp/#a84a7819a9f36f529085ab85492b5a4d7">performVP_REVERSECombine</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/riscv/riscvisellowering-cpp/#a90e158dcd9e3da205b3703145ed4cfcb">performVP_STORECombine</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/arm/armisellowering-cpp/#a040e9492b947241650ac7f528bd75c25">PerformVQDMULHCombine</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/arm/armisellowering-cpp/#aab5f933f6c91550090ecb2288acc64fd">PerformVQDMULHCombine</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/arm/armisellowering-cpp/#a87f35b3974b7d383ff5cd70bdfa090ab">PerformVQMOVNCombine</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/nvptx/nvptxisellowering-cpp/#a3a9b8c53e20027bce86d1f1364150e7c">PerformVSELECTCombine</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/arm/armisellowering-cpp/#a8ee8d90c02a1da62f94c6322a8f004cb">PerformVSELECTCombine</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/mips/mipsseisellowering-cpp/#a2a798c6b07c3e9e5e0ec518b0c3ef154">performVSELECTCombine</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/riscv/riscvisellowering-cpp/#a2a798c6b07c3e9e5e0ec518b0c3ef154">performVSELECTCombine</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64isellowering-cpp/#abc2faab09dd74a706e426de046a3f4a0">performVSelectCombine</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/arm/armisellowering-cpp/#a99f918c3264972ed6aea09c675404952">PerformVSetCCToVCTPCombine</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/riscv/riscvisellowering-cpp/#a3afeac5861ab518f4a52bb9d464a5da5">performVWADDSUBW_VLCombine</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/arm/armisellowering-cpp/#ac1399030f41bb48286cffbbfddb29a3f">PerformXORCombine</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/mips/mipsseisellowering-cpp/#a14fe6050fa67f0e7b01314d5c7586b8e">performXORCombine</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/riscv/riscvisellowering-cpp/#a6659c72985a2b34b2b0714641762ef21">performXORCombine</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64isellowering-cpp/#ac52bce44713165c831945178e1d5f696">performXorCombine</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64isellowering-cpp/#a036a964199eef5a0aab70732233b5e8d">performZExtDeinterleaveShuffleCombine</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64isellowering-cpp/#a7da18013c41f68948709a964437238bf">performZExtUZPCombine</a>, <a href="/web-llvm/docs/api/classes/llvm/piblockddgnode/#a495ca4b0fce6fb1dedbdbe171f74ce7c">llvm::PiBlockDDGNode::PiBlockDDGNode</a>, <a href="/web-llvm/docs/api/classes/llvm/piblockddgnode/#addeddd9f90516c98c3cd9dc945d46377">llvm::PiBlockDDGNode::PiBlockDDGNode</a>, <a href="/web-llvm/docs/api/classes/llvm/piblockddgnode/#adce32ebae1d8ec671b813c8ed69c7e95">llvm::PiBlockDDGNode::PiBlockDDGNode</a>, <a href="/web-llvm/docs/api/classes/podsmallvector/#af6aff2fdeac653f75f974143e610f858">PODSmallVector&lt; Node *, 8 &gt;::PODSmallVector</a>, <a href="/web-llvm/docs/api/classes/anonymous-constraintelimination-cpp-/constraintinfo/#a42ec44c7e64a75d533da53f76bf60ac5">anonymous{ConstraintElimination.cpp}::ConstraintInfo::popLastNVariables</a>, <a href="/web-llvm/docs/api/classes/llvm/constraintsystem/#aa6bdcd92da3382da904f006eb5aeb33c">llvm::ConstraintSystem::popLastNVariables</a>, <a href="/web-llvm/docs/api/classes/llvm/amdgputargetlowering/#a4713251cc0d94764b3bafeff64a26c79">llvm::AMDGPUTargetLowering::PostISelFolding</a>, <a href="/web-llvm/docs/api/classes/anonymous-x86iseldagtodag-cpp-/x86dagtodagisel/#aa5cb58b25423e45192ae938233ae4eae">anonymous{X86ISelDAGToDAG.cpp}::X86DAGToDAGISel::PostprocessISelDAG</a>, <a href="/web-llvm/docs/api/classes/llvm/riscvdagtodagisel/#a838f903d98be09e801b17c933b89fe27">llvm::RISCVDAGToDAGISel::PostprocessISelDAG</a>, <a href="/web-llvm/docs/api/namespaces/llvm/apintops/#a883e1be546d0c36c707bc175acedd262">llvm::APIntOps::pow</a>, <a href="/web-llvm/docs/api/namespaces/llvm/hexagonmcinstrinfo/#aa930f49234de4fd7a469613a1989daf1">llvm::HexagonMCInstrInfo::predicateInfo</a>, <a href="/web-llvm/docs/api/classes/llvm/sandboxir/memdgnode/#af065143585f17219e1066f582fd55021">llvm::sandboxir::MemDGNode::PredIterator</a>, <a href="/web-llvm/docs/api/classes/llvm/aarch64targetlowering/#a6667df004a39c249e82595e8c06841ca">llvm::AArch64TargetLowering::preferredShiftLegalizationStrategy</a>, <a href="/web-llvm/docs/api/classes/llvm/armtargetlowering/#af2c8b0d2dd39354fff7d4bb1ab3fa2f3">llvm::ARMTargetLowering::preferredShiftLegalizationStrategy</a>, <a href="/web-llvm/docs/api/classes/llvm/avrtargetlowering/#a555990ddecb21ee55c0813bc93aecb02">llvm::AVRTargetLowering::preferredShiftLegalizationStrategy</a>, <a href="/web-llvm/docs/api/classes/llvm/riscvtargetlowering/#a2d4b243bcdfea88060ffa51fa30683fb">llvm::RISCVTargetLowering::preferredShiftLegalizationStrategy</a>, <a href="/web-llvm/docs/api/classes/llvm/targetloweringbase/#aa88eb4ddf2a7c4d5d5482c9fc0b9090a">llvm::TargetLoweringBase::preferredShiftLegalizationStrategy</a>, <a href="/web-llvm/docs/api/classes/llvm/x86targetlowering/#a3bcf75579cf117a1b83a27dbe4d775d6">llvm::X86TargetLowering::preferredShiftLegalizationStrategy</a>, <a href="/web-llvm/docs/api/classes/llvm/riscvtargetlowering/#a301b8a0795699f142ce98bf05385c69b">llvm::RISCVTargetLowering::preferScalarizeSplat</a>, <a href="/web-llvm/docs/api/classes/llvm/targetloweringbase/#a6095ebdbbb4b8652c57fd99987e67927">llvm::TargetLoweringBase::preferScalarizeSplat</a>, <a href="/web-llvm/docs/api/classes/llvm/x86targetlowering/#a79733c103f8a91ce6006567de49a6f40">llvm::X86TargetLowering::preferScalarizeSplat</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/ve/veisellowering-cpp/#a3dbfd11d0e219a5ccf7b2a3bee4e55b3">prepareTS1AM</a>, <a href="/web-llvm/docs/api/classes/anonymous-armiseldagtodag-cpp-/armdagtodagisel/#aef3ca350fa266bbc7d421597cae9f11d">anonymous{ARMISelDAGToDAG.cpp}::ARMDAGToDAGISel::PreprocessISelDAG</a>, <a href="/web-llvm/docs/api/classes/anonymous-ppciseldagtodag-cpp-/ppcdagtodagisel/#a734032526577f3bd7808bcc857f35537">anonymous{PPCISelDAGToDAG.cpp}::PPCDAGToDAGISel::PreprocessISelDAG</a>, <a href="/web-llvm/docs/api/classes/anonymous-systemziseldagtodag-cpp-/systemzdagtodagisel/#aae5d1e82046f7e049df2177e29a9d6f7">anonymous{SystemZISelDAGToDAG.cpp}::SystemZDAGToDAGISel::PreprocessISelDAG</a>, <a href="/web-llvm/docs/api/classes/anonymous-webassemblyiseldagtodag-cpp-/webassemblydagtodagisel/#aa5fa9366605849c974443a41c63accb5">anonymous{WebAssemblyISelDAGToDAG.cpp}::WebAssemblyDAGToDAGISel::PreprocessISelDAG</a>, <a href="/web-llvm/docs/api/classes/anonymous-x86iseldagtodag-cpp-/x86dagtodagisel/#a621eb8645a9f80882b80ac3c6d4e0091">anonymous{X86ISelDAGToDAG.cpp}::X86DAGToDAGISel::PreprocessISelDAG</a>, <a href="/web-llvm/docs/api/classes/llvm/amdgpudagtodagisel/#a8a5d4f323744a3d4f3356493836cc59b">llvm::AMDGPUDAGToDAGISel::PreprocessISelDAG</a>, <a href="/web-llvm/docs/api/classes/llvm/hexagondagtodagisel/#ad83627951b8c14a59773abf836d4e91a">llvm::HexagonDAGToDAGISel::PreprocessISelDAG</a>, <a href="/web-llvm/docs/api/classes/llvm/riscvdagtodagisel/#a6aa2c4df9fd69696ef41afd841661bb7">llvm::RISCVDAGToDAGISel::PreprocessISelDAG</a>, <a href="/web-llvm/docs/api/classes/anonymous-scheduledagrrlist-cpp-/regreductionpqbase/#a6df9e18cc58cb146ccfa7c7d47b6b9ca">anonymous{ScheduleDAGRRList.cpp}::RegReductionPQBase::PrescheduleNodesWithMultipleUses</a>, <a href="/web-llvm/docs/api/structs/anonymous-hexagonloopidiomrecognition-cpp-/simplifier/context/#a014e2fa165b2f63dac3c79d8e1c73346">anonymous{HexagonLoopIdiomRecognition.cpp}::Simplifier::Context::print</a>, <a href="/web-llvm/docs/api/structs/anonymous-itaniumdemangle-cpp-/dumpvisitor/#a82c5934505b75b1d9c6c4f123898d47a">anonymous{ItaniumDemangle.cpp}::DumpVisitor::print</a>, <a href="/web-llvm/docs/api/structs/anonymous-itaniumdemangle-cpp-/dumpvisitor/#ad493cd30055fca3c8953054af0bbac6c">anonymous{ItaniumDemangle.cpp}::DumpVisitor::print</a>, <a href="/web-llvm/docs/api/structs/anonymous-itaniumdemangle-cpp-/dumpvisitor/#a71e5603c77c723604579181fe73a2071">anonymous{ItaniumDemangle.cpp}::DumpVisitor::print</a>, <a href="/web-llvm/docs/api/classes/llvm/format-object-base/#a5b6aaf8cbdc3d3660bef42e1556908f1">llvm::format_object_base::print</a>, <a href="/web-llvm/docs/api/classes/llvm/gcovblock/#ab29bbd9db53708e8289378ef09ce5c0e">llvm::GCOVBlock::print</a>, <a href="/web-llvm/docs/api/structs/llvm/knownbits/#a4d0179756dcc99d6a927d88dd0f0014b">llvm::KnownBits::print</a>, <a href="/web-llvm/docs/api/structs/llvm/memprof/memprofrecord/#aa5a539ee058b256071c731b50c18c2ca">llvm::memprof::MemProfRecord::print</a>, <a href="/web-llvm/docs/api/classes/llvm/opt/option/#afd58fdbc2f1005c2c368a24fd8af0c7a">llvm::opt::Option::print</a>, <a href="/web-llvm/docs/api/classes/llvm/phivalues/#adea7214b948710e46784edabd9c9dd79">llvm::PhiValues::print</a>, <a href="/web-llvm/docs/api/classes/llvm/sandboxir/dependencygraph/#aa8602ab3d40d78dfbf826e154ac3fb8d">llvm::sandboxir::DependencyGraph::print</a>, <a href="/web-llvm/docs/api/classes/llvm/symbolize/jsonprinter/#a808d66d93b73e4fdd1e409c9ba48671b">llvm::symbolize::JSONPrinter::print</a>, <a href="/web-llvm/docs/api/classes/llvm/sdnode/#ac351340ed4428a1b6d69d303bcba86d9">llvm::SDNode::print_details</a>, <a href="/web-llvm/docs/api/classes/llvm/runtimepointerchecking/#a3e60690517dfc1dd58b48cbbc1e0657f">llvm::RuntimePointerChecking::printChecks</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/x86/x86mcinstlower-cpp/#ade5b1fe412812c4f0d9bb11e2cf2f4d3">printConstant</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a0e7eca3929463309c716a4812fde06fe">llvm::PrintDomTree</a>, <a href="/web-llvm/docs/api/classes/llvm/yaml/stream/#ab14d4901b18c31b9707f2ea52d0f82f0">llvm::yaml::Stream::printError</a>, <a href="/web-llvm/docs/api/namespaces/anonymous-standardinstrumentations-cpp-/#a16cf3c3c02a9781f1cbe27968506f81b">anonymous{StandardInstrumentations.cpp}::printIR</a>, <a href="/web-llvm/docs/api/classes/floatliteralimpl/#a35a50b2e5042043182ad404b8073d197">FloatLiteralImpl&lt; float &gt;::printLeft</a>, <a href="/web-llvm/docs/api/structs/anonymous-asmwriter-cpp-/mdfieldprinter/#a2137ea7428ed1982a2ae6d0a2f8a2c35">anonymous{AsmWriter.cpp}::MDFieldPrinter::printMacinfoType</a>, <a href="/web-llvm/docs/api/files/lib/lib/ir/asmwriter-cpp/#a2c3485cc2e63a9ea902dccf6dc02a555">printMetadataImpl</a>, <a href="/web-llvm/docs/api/files/lib/lib/ir/asmwriter-cpp/#a98078ed9da1a2d013cd401e491649bf8">printMetadataImplRec</a>, <a href="/web-llvm/docs/api/files/lib/lib/demangle/itaniumdemangle-cpp/#a97d00adf19488f40b3eacb166bfa4d2b">printNode</a>, <a href="/web-llvm/docs/api/files/lib/lib/analysis/lazycallgraph-cpp/#a43bfa5ae5bc262dd53cb668fa64764dc">printNode</a>, <a href="/web-llvm/docs/api/files/lib/lib/analysis/lazycallgraph-cpp/#aa23cb08728e5bb13e2bf43eb614c3efa">printNodeDOT</a>, <a href="/web-llvm/docs/api/namespaces/llvm/anonymous-amdgpusplitmodule-cpp-/#ab6e8eb04697a9174b65bf56d1a480310">llvm::anonymous{AMDGPUSplitModule.cpp}::printPartitionSummary</a>, <a href="/web-llvm/docs/api/files/lib/lib/codegen/lib/codegen/selectiondag/selectiondagdumper-cpp/#adfc37ceb937f230dbfdbda000e383090">printrWithDepthHelper</a>, <a href="/web-llvm/docs/api/files/lib/lib/analysis/lazycallgraph-cpp/#ae48a57dbe703b0863fc96285ac60a9d6">printSCC</a>, <a href="/web-llvm/docs/api/structs/anonymous-asmwriter-cpp-/mdfieldprinter/#a9b204d399cf691b892395a9804639e58">anonymous{AsmWriter.cpp}::MDFieldPrinter::printTag</a>, <a href="/web-llvm/docs/api/namespaces/llvm/aarch64-am/#a2cd3e23b97b495a98c0b723ab18e4d96">llvm::AArch64_AM::processLogicalImmediate</a>, <a href="/web-llvm/docs/api/classes/anonymous-sifixsgprcopies-cpp-/sifixsgprcopies/#aadcf47d2bfa2abd153d66b001715198c">anonymous{SIFixSGPRCopies.cpp}::SIFixSGPRCopies::processPHINode</a>, <a href="/web-llvm/docs/api/files/lib/lib/codegen/lib/codegen/selectiondag/scheduledagsdnodes-cpp/#aab3e2639c5eed5d618705678090fa23f">ProcessSDDbgValues</a>, <a href="/web-llvm/docs/api/files/lib/lib/codegen/lib/codegen/selectiondag/scheduledagsdnodes-cpp/#a10d5495926e5659dbcefde78541b29a8">ProcessSourceNode</a>, <a href="/web-llvm/docs/api/namespaces/anonymous-lowerswitch-cpp-/#a5770d604e68e48d1b8f1e7aa4c89a034">anonymous{LowerSwitch.cpp}::ProcessSwitchInst</a>, <a href="/web-llvm/docs/api/namespaces/anonymous-itaniummanglingcanonicalizer-cpp-/#a70ae8683aab30e05587419cabd7d06aa">anonymous{ItaniumManglingCanonicalizer.cpp}::profileNode</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/nvptx/nvptxisellowering-cpp/#ade6927c3ebfbd00cbede63e5a1d1426d">PromoteBinOpToF32</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/x86/x86isellowering-cpp/#a79a78596a7d54cb3e906428f79199e93">PromoteMaskArithmetic</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/x86/x86isellowering-cpp/#a5ca0a8558bfafc5249f833982956d4cc">PromoteMaskArithmetic</a>, <a href="/web-llvm/docs/api/classes/anonymous-lowermatrixintrinsics-cpp-/lowermatrixintrinsics/#a611115d09f3dd3ef310f70c87a8ba402">anonymous{LowerMatrixIntrinsics.cpp}::LowerMatrixIntrinsics::propagateShapeBackward</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/powerpc/ppcisellowering-cpp/#a3c48cdb4fcbd71e51a4ec4c1d5c6a99a">provablyDisjointOr</a>, <a href="/web-llvm/docs/api/structs/llvm/rdf/dataflowgraph/#a9ee71e8d993c1deb028f6299d055340f">llvm::rdf::DataFlowGraph::ptr</a>, <a href="/web-llvm/docs/api/structs/llvm/rdf/nodeallocator/#a213d8f7f24fe29a3f8eec498398930cf">llvm::rdf::NodeAllocator::ptr</a>, <a href="/web-llvm/docs/api/classes/llvm/intrusivebacklist/#a9eac5dd87ac4464d5cd49645d6fafabf">llvm::IntrusiveBackList&lt; Node &gt;::push_back</a>, <a href="/web-llvm/docs/api/structs/llvm/intrusivebacklistbase/#a494ece99b2a33de9985a29c5bf49d7e7">llvm::IntrusiveBackListBase::push_back</a>, <a href="/web-llvm/docs/api/classes/llvm/msgpack/arraydocnode/#a969a25cab20bacfc1d698c1980a6b858">llvm::msgpack::ArrayDocNode::push_back</a>, <a href="/web-llvm/docs/api/classes/llvm/intrusivebacklist/#a6ac1a17a8d60411b771c0af6e99c670b">llvm::IntrusiveBackList&lt; Node &gt;::push_front</a>, <a href="/web-llvm/docs/api/structs/llvm/intrusivebacklistbase/#aea67d773bb7ff0e04a545837cc5613a8">llvm::IntrusiveBackListBase::push_front</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/x86/x86isellowering-cpp/#af99172dc0d0e9814f6b7138987c3b0f6">pushAddIntoCmovOfConsts</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#ad73613c8e8495c4d7e3aaf2da575f2e2">llvm::readAndDecodeStrings</a>, <a href="/web-llvm/docs/api/classes/llvm/instrproflookuptrait/#ab68d7f02ae82dffc7ab698204d1e7d57">llvm::InstrProfLookupTrait::ReadData</a>, <a href="/web-llvm/docs/api/classes/llvm/binarystreamreader/#a6a4349bd091677944d67764f80b6fbe0">llvm::BinaryStreamReader::readEnum</a>, <a href="/web-llvm/docs/api/classes/llvm/instrproflookuptrait/#a84dbd8771ff05ebd263bdc77a1553e86">llvm::InstrProfLookupTrait::ReadKey</a>, <a href="/web-llvm/docs/api/namespaces/llvm/sys/unicode/#a1595de063cd60f1beb94ab845204e496">llvm::sys::unicode::readNode</a>, <a href="/web-llvm/docs/api/classes/llvm/coverage/rawcoveragereader/#aca96acd10163f3b8e78eea75ba200fd1">llvm::coverage::RawCoverageReader::readULEB128</a>, <a href="/web-llvm/docs/api/classes/llvm/callgraphupdater/#a7bf8126709349339746d58096776d4f3">llvm::CallGraphUpdater::reanalyzeFunction</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64isellowering-cpp/#a0a920d221f6e65925d8b683836cebd03">reassociateCSELOperandsForCSE</a>, <a href="/web-llvm/docs/api/structs/llvm/domtreebuilder/semincainfo/#a6ab30bb387a6e7086235e9ff7ad01941">llvm::DomTreeBuilder::SemiNCAInfo&lt; DomTreeT &gt;::reattachExistingSubtree</a>, <a href="/web-llvm/docs/api/classes/llvm/record/#a98b09e526bfdb38ffb4a256f8cb6629a">llvm::Record::Record</a>, <a href="/web-llvm/docs/api/classes/llvm/record/#a9667e38415a2885b9cc555f6e41e1eab">llvm::Record::Record</a>, <a href="/web-llvm/docs/api/classes/llvm/recordval/#a9fb77205ef9270fad57e45ea4132d4ce">llvm::RecordVal::RecordVal</a>, <a href="/web-llvm/docs/api/classes/llvm/recordval/#af4359363f341a79bd6f65548c8bc49d2">llvm::RecordVal::RecordVal</a>, <a href="/web-llvm/docs/api/classes/llvm/imutavlfactory/#ade6cf254863ac87b2447630781be56a9">llvm::ImutAVLFactory&lt; ImutInfo &gt;::recoverNodes</a>, <a href="/web-llvm/docs/api/classes/anonymous-dagcombiner-cpp-/dagcombiner/#a1fb03492a579f75d8e28babe08499162">anonymous{DAGCombiner.cpp}::DAGCombiner::recursivelyDeleteUnusedNodes</a>, <a href="/web-llvm/docs/api/structs/llvm/targetlowering/dagcombinerinfo/#abf156bc8dfc3e92cd63aee7192c3dea8">llvm::TargetLowering::DAGCombinerInfo::recursivelyDeleteUnusedNodes</a>, <a href="/web-llvm/docs/api/classes/llvm/scheduledaginstrs/#a2e28b826aaa73d2dacf89ba8f8c775d1">llvm::ScheduleDAGInstrs::reduceHugeMemNodeMaps</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/x86/x86isellowering-cpp/#ab81263b19a504166d5c027a21cc15740">reduceVMULWidth</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/powerpc/ppciseldagtodag-cpp/#a5f0c9d4042514e981169ab91031fb08b">reduceVSXSwap</a>, <a href="/web-llvm/docs/api/structs/anonymous-hexagongeninsert-cpp-/registercellbitcomparesel/#a60bd6ecd292967fa5301f7e79fadd233">anonymous{HexagonGenInsert.cpp}::RegisterCellBitCompareSel::RegisterCellBitCompareSel</a>, <a href="/web-llvm/docs/api/classes/llvm/registerregalloc/#a71bd5c303d986f735e3b783266c79792">llvm::RegisterRegAlloc::RegisterRegAlloc</a>, <a href="/web-llvm/docs/api/classes/llvm/registerregallocbase/#ac90e8d65fa65253a4f819c03fb734f38">llvm::RegisterRegAllocBase&lt; SubClass &gt;::RegisterRegAllocBase</a>, <a href="/web-llvm/docs/api/classes/llvm/registerscheduler/#aa896a0f8a4e3c9084fd9bd98577ef34b">llvm::RegisterScheduler::RegisterScheduler</a>, <a href="/web-llvm/docs/api/classes/llvm/targetregisterinfo/#a4d07b23213b2426cc796329c00f8930d">llvm::TargetRegisterInfo::regmaskSubsetEqual</a>, <a href="/web-llvm/docs/api/classes/anonymous-scheduledagrrlist-cpp-/regreductionpqbase/#a1b480aa4515358bac44d9281c7f74471">anonymous{ScheduleDAGRRList.cpp}::RegReductionPQBase::RegPressureDiff</a>, <a href="/web-llvm/docs/api/classes/anonymous-valuemapper-cpp-/mdnodemapper/#a7c38ca83c916472e5580992d97616ba9">anonymous{ValueMapper.cpp}::MDNodeMapper::remapOperands</a>, <a href="/web-llvm/docs/api/structs/anonymous-materializationutils-cpp-/rematgraph/#af174860218eac10104c5be83375d5ec7">anonymous{MaterializationUtils.cpp}::RematGraph::RematGraph</a>, <a href="/web-llvm/docs/api/classes/llvm/ilist-base/#ab0e773629519dab96a519c567524ba65">llvm::ilist_base&lt; enable_sentinel_tracking, parent_ty &gt;::remove</a>, <a href="/web-llvm/docs/api/classes/llvm/simple-ilist/#af373b4ab7e8cd5a179d3c86ee3404912">llvm::simple_ilist&lt; Node &gt;::remove</a>, <a href="/web-llvm/docs/api/classes/llvm/simple-ilist/#afb5871f1692d8db06f33611f9bdddb85">llvm::simple_ilist&lt; Node &gt;::removeAndDispose</a>, <a href="/web-llvm/docs/api/classes/llvm/lazycallgraph/#a97b7a3d43f4f6eb3ab16554f56bd0cc4">llvm::LazyCallGraph::removeDeadFunctions</a>, <a href="/web-llvm/docs/api/classes/llvm/selectiondag/#a935ace76cef67c6da10cf0633371efe1">llvm::SelectionDAG::RemoveDeadNode</a>, <a href="/web-llvm/docs/api/classes/llvm/selectiondag/#afa91c37999052160d434c5bf803257c9">llvm::SelectionDAG::RemoveDeadNodes</a>, <a href="/web-llvm/docs/api/classes/llvm/machinefunction/#a2702e813ffe6b916af6be0924aa744fb">llvm::MachineFunction::removeFromMBBNumbering</a>, <a href="/web-llvm/docs/api/classes/anonymous-dagcombiner-cpp-/dagcombiner/#a86d34559ce6afe8a233d22ef656ac13b">anonymous{DAGCombiner.cpp}::DAGCombiner::removeFromWorklist</a>, <a href="/web-llvm/docs/api/classes/llvm/ilist-base/#ad192ebc3fb2e80bae6d62b0f80446ae5">llvm::ilist_base&lt; enable_sentinel_tracking, parent_ty &gt;::removeImpl</a>, <a href="/web-llvm/docs/api/classes/llvm/lazycallgraph/refscc/#a87dd1a69c8d8492e78b32708ceacb2c6">llvm::LazyCallGraph::RefSCC::removeInternalRefEdges</a>, <a href="/web-llvm/docs/api/classes/llvm/cl/parser/#a5ad1b91cd29cc60251f10f3fd4c6e563">llvm::cl::parser&lt; DataType &gt;::removeLiteralOption</a>, <a href="/web-llvm/docs/api/classes/llvm/foldingsetbase/#a50648616eadb2b7b9dcf36c9bd685ccc">llvm::FoldingSetBase::RemoveNode</a>, <a href="/web-llvm/docs/api/classes/llvm/foldingsetimpl/#a275874e6c3ea4829f9de7bd74304c5cc">llvm::FoldingSetImpl&lt; FoldingSet, T &gt;::RemoveNode</a>, <a href="/web-llvm/docs/api/classes/llvm/directedgraph/#af3d77f0eb55733fc66d9a8df01deeffb">llvm::DirectedGraph&lt; DDGNode, DDGEdge &gt;::removeNode</a>, <a href="/web-llvm/docs/api/classes/llvm/pbqp/graph/#a2e5eaf57399d0311f0c20896a43283ef">llvm::PBQP::Graph&lt; RegAllocSolverImpl &gt;::removeNode</a>, <a href="/web-llvm/docs/api/structs/llvm/ilist-callback-traits-6a00974026f1163ef87516ae73fba13d/#a75a61319c8ef57e447a07a0244e904b0">llvm::ilist_callback_traits&lt; MachineBasicBlock &gt;::removeNodeFromList</a>, <a href="/web-llvm/docs/api/structs/llvm/ilist-traits-58bb2936e8a6e4674ffe4f47907d64dc/#aba9869e6b806b747cdf16aefd230cfc5">llvm::ilist_traits&lt; MachineInstr &gt;::removeNodeFromList</a>, <a href="/web-llvm/docs/api/structs/anonymous-hexagonrdfopt-cpp-/hexagondce/#af147b385bf71cd50563c0d23b0f9baf7">anonymous{HexagonRDFOpt.cpp}::HexagonDCE::removeOperand</a>, <a href="/web-llvm/docs/api/classes/llvm/machineinstr/#ac3b161ec90385105cb46a08b52139e60">llvm::MachineInstr::removeOperand</a>, <a href="/web-llvm/docs/api/classes/llvm/scheduledagtopologicalsort/#a10a769ee13a9d9298d2c2b887dfae250">llvm::ScheduleDAGTopologicalSort::RemovePred</a>, <a href="/web-llvm/docs/api/classes/llvm/sunit/#a6d3233165db1e6be5c44060cd4a95461">llvm::SUnit::removePred</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64isellowering-cpp/#a72e2201d5e251af1abbfb6fde00df1cb">removeRedundantInsertVectorElt</a>, <a href="/web-llvm/docs/api/structs/llvm/domtreebuilder/semincainfo/#a851b359886bf561fb0fde504c228ecea">llvm::DomTreeBuilder::SemiNCAInfo&lt; DomTreeT &gt;::RemoveRedundantRoots</a>, <a href="/web-llvm/docs/api/files/lib/lib/codegen/lib/codegen/selectiondag/scheduledagsdnodes-cpp/#a57615f1098413358af4bdab4f2f493fe">RemoveUnusedGlue</a>, <a href="#a919284efeea9e5256497a0778b7fdd75">repeat</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64isellowering-cpp/#ab7f8d142b901597abdf51e5e51a5605f">ReplaceAddWithADDP</a>, <a href="/web-llvm/docs/api/classes/llvm/dibuilder/#afee05194feacd4f95209e840e7242332">llvm::DIBuilder::replaceArrays</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64isellowering-cpp/#ae416c990e5945aed7ccfb70d4c7a5802">ReplaceATOMIC_LOAD_128Results</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64isellowering-cpp/#a9d18c51ca04dfa5c2b56ad650ab0d7d9">replaceBoolVectorBitcast</a>, <a href="/web-llvm/docs/api/classes/llvm/callgraphnode/#a61a20bdec19cf182df0c3b23bb1895b7">llvm::CallGraphNode::replaceCallEdge</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64isellowering-cpp/#a32739f322e03782811f33bc367f9bc3b">ReplaceCMP_SWAP_128Results</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/arm/armisellowering-cpp/#a9edb7bbdf708d2f51e1cab727a105fdc">ReplaceCMP_SWAP_64Results</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/loongarch/loongarchisellowering-cpp/#ad7a2ce0778f9b0a95ac96bd8e3f9de78">replaceCMP_XCHG_128Results</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/nvptx/nvptxisellowering-cpp/#a3107ed4a76b88b6513e9009057b7ad9f">ReplaceCopyFromReg_128</a>, <a href="/web-llvm/docs/api/classes/anonymous-legalizedag-cpp-/selectiondaglegalize/#aab9274d5e16740f94ead5a55f197b514">anonymous{LegalizeDAG.cpp}::SelectionDAGLegalize::ReplacedNode</a>, <a href="/web-llvm/docs/api/classes/llvm/dicompileunit/#a4e9c2f038b1a61e566893b05cb19187d">llvm::DICompileUnit::replaceEnumTypes</a>, <a href="/web-llvm/docs/api/classes/llvm/dicompileunit/#a7c78bd25d89294be0cc8fa519c8cf2a1">llvm::DICompileUnit::replaceGlobalVariables</a>, <a href="/web-llvm/docs/api/classes/llvm/dicompileunit/#abe6add89069d0c88b795155b8de8bce1">llvm::DICompileUnit::replaceImportedEntities</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/nvptx/nvptxisellowering-cpp/#a43333bc4548cbb52de14105bc979c0e0">ReplaceINTRINSIC_W_CHAIN</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/loongarch/loongarchisellowering-cpp/#ae9668c83a73c0b3d546522e1d9860cba">replaceINTRINSIC_WO_CHAINResults</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/nvptx/nvptxisellowering-cpp/#a1d84356309e55a4722a2739dd3c655e4">ReplaceLoadVector</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/arm/armisellowering-cpp/#a663a00cee8894f834358261a64ea7c7e">ReplaceLongIntrinsic</a>, <a href="/web-llvm/docs/api/classes/llvm/dicompileunit/#a7d16da4f9fe3a9a316c3d34791745283">llvm::DICompileUnit::replaceMacros</a>, <a href="/web-llvm/docs/api/classes/llvm/lazycallgraph/refscc/#a70f7f0574edbfc0f75424499133d4ba3">llvm::LazyCallGraph::RefSCC::replaceNodeFunction</a>, <a href="/web-llvm/docs/api/classes/llvm/amdgputargetlowering/#ad968ecdcaf64b24df6515220e36bdb5d">llvm::AMDGPUTargetLowering::ReplaceNodeResults</a>, <a href="/web-llvm/docs/api/classes/llvm/armtargetlowering/#a28af47b21a8953afd3568b40acf3424d">llvm::ARMTargetLowering::ReplaceNodeResults</a>, <a href="/web-llvm/docs/api/classes/llvm/avrtargetlowering/#a088c31366c990e0e055fbe65766e8d2e">llvm::AVRTargetLowering::ReplaceNodeResults</a>, <a href="/web-llvm/docs/api/classes/llvm/hexagontargetlowering/#a9db6eb2b9e8f4c06455eb169c64e79b3">llvm::HexagonTargetLowering::ReplaceNodeResults</a>, <a href="/web-llvm/docs/api/classes/llvm/loongarchtargetlowering/#ac83ceb8e67e1ee6ca693e3ff1ffbac0f">llvm::LoongArchTargetLowering::ReplaceNodeResults</a>, <a href="/web-llvm/docs/api/classes/llvm/mipstargetlowering/#a73afb942bbe9f13347f351f28ac2fe2c">llvm::MipsTargetLowering::ReplaceNodeResults</a>, <a href="/web-llvm/docs/api/classes/llvm/ppctargetlowering/#a49eedef79b249eb098470debb9601eb7">llvm::PPCTargetLowering::ReplaceNodeResults</a>, <a href="/web-llvm/docs/api/classes/llvm/r600targetlowering/#aa52bac1dc0a8f251721e5702c4f81a50">llvm::R600TargetLowering::ReplaceNodeResults</a>, <a href="/web-llvm/docs/api/classes/llvm/riscvtargetlowering/#abb4ac2d585a18a9b8db4ac7ffa41fc06">llvm::RISCVTargetLowering::ReplaceNodeResults</a>, <a href="/web-llvm/docs/api/classes/llvm/sitargetlowering/#a697277613cca131c099969ca5d421041">llvm::SITargetLowering::ReplaceNodeResults</a>, <a href="/web-llvm/docs/api/classes/llvm/sparctargetlowering/#a16e6c862a36871c4f388c826ad65b07c">llvm::SparcTargetLowering::ReplaceNodeResults</a>, <a href="/web-llvm/docs/api/classes/llvm/systemztargetlowering/#ac8d6a0440d5c72783599e258a3db9e58">llvm::SystemZTargetLowering::ReplaceNodeResults</a>, <a href="/web-llvm/docs/api/classes/llvm/vetargetlowering/#ac37905796bf7d5a2582ea8f41e98c3f0">llvm::VETargetLowering::ReplaceNodeResults</a>, <a href="/web-llvm/docs/api/classes/llvm/x86targetlowering/#af77fd362607d101a7080481254ee2fe3">llvm::X86TargetLowering::ReplaceNodeResults</a>, <a href="/web-llvm/docs/api/classes/llvm/xcoretargetlowering/#a89e28b97fe160f32871560a32a350499">llvm::XCoreTargetLowering::ReplaceNodeResults</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/arm/armisellowering-cpp/#a953988fc960bc5ff29afff3ded965e9d">ReplaceREADCYCLECOUNTER</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64isellowering-cpp/#a4be0086aa7ffce797f40ad2eefd2ec1a">ReplaceReductionResults</a>, <a href="/web-llvm/docs/api/classes/anonymous-simplifyindvar-cpp-/simplifyindvar/#a645f6e970e94d7ca51922b3932338f51">anonymous{SimplifyIndVar.cpp}::SimplifyIndvar::replaceRemWithNumeratorOrZero</a>, <a href="/web-llvm/docs/api/classes/anonymous-dxiloplowering-cpp-/oplowerer/#a583a2a6c920de4695807c6ad35c5e35d">anonymous{DXILOpLowering.cpp}::OpLowerer::replaceResRetUses</a>, <a href="/web-llvm/docs/api/classes/llvm/dicompileunit/#a7672beda79b3ce26a92e6b27a024ef85">llvm::DICompileUnit::replaceRetainedTypes</a>, <a href="/web-llvm/docs/api/classes/anonymous-simplifyindvar-cpp-/simplifyindvar/#a8a96c9b1143670a73852464de9950e8e">anonymous{SimplifyIndVar.cpp}::SimplifyIndvar::replaceSRemWithURem</a>, <a href="/web-llvm/docs/api/classes/llvm/dibuilder/#a0cfa048f7096ffb7b085d2d5d1a399ba">llvm::DIBuilder::replaceTemporary</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/loongarch/loongarchisellowering-cpp/#ab60a9c518b2a79a37b4cf83ec7fdeee8">replaceVecCondBranchResults</a>, <a href="/web-llvm/docs/api/classes/llvm/dibuilder/#a736aced5bb739ef4976f57e0bc58ae22">llvm::DIBuilder::replaceVTableHolder</a>, <a href="/web-llvm/docs/api/classes/llvm/mdnode/#a7f0bcc228d194e9ec76797f689511951">llvm::MDNode::replaceWithDistinct</a>, <a href="/web-llvm/docs/api/classes/llvm/mdnode/#aede5ab4b2f3306b9f1ac4e69fdfd476b">llvm::MDNode::replaceWithPermanent</a>, <a href="/web-llvm/docs/api/classes/llvm/mdnode/#af8e7c85da0c37b1a8a5099d7a01f03a8">llvm::MDNode::replaceWithUniqued</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/loongarch/lib/target/loongarch/mctargetdesc/loongarchasmbackend-cpp/#ad360de3efee00759db4618c8f2bf738c">reportOutOfRangeError</a>, <a href="/web-llvm/docs/api/classes/llvm/selectiondag/#aed6667e93ace54abed8e4432b7b88927">llvm::SelectionDAG::RepositionNode</a>, <a href="/web-llvm/docs/api/structs/anonymous-hexagoniseldagtodaghvx-cpp-/opref/#a8ababd0d43313d3b6a1efb76cb0b74fd">anonymous{HexagonISelDAGToDAGHVX.cpp}::OpRef::res</a>, <a href="/web-llvm/docs/api/classes/llvm/bitvector/#a6940ad301a9c7053fdcb2acfbda169e5">llvm::BitVector::reserve</a>, <a href="/web-llvm/docs/api/classes/llvm/smallvectorimpl/#a499ea32ca1b8d16cedfe01d1e5b08f29">llvm::const_iterator&lt; MemoryLocation &gt;::reserve</a>, <a href="/web-llvm/docs/api/classes/llvm/packedvector/#af2779b3b1858a954e442e4219d1707d5">llvm::PackedVector&lt; T, BitNum, BitVectorTy &gt;::reserve</a>, <a href="/web-llvm/docs/api/classes/llvm/smallbitvector/#a36e2a6d15c30784c94effc174d573c2b">llvm::SmallBitVector::reserve</a>, <a href="/web-llvm/docs/api/classes/llvm/smallvectortemplatebase/#aeab77382e7ca9b451524424e268ff264">llvm::SmallVectorTemplateBase&lt; T, bool &gt;::reserveForParamAndGetAddress</a>, <a href="/web-llvm/docs/api/classes/llvm/smallvectortemplatebase/#a89ccedcf373b03d6e115d8b5e56ccebd">llvm::SmallVectorTemplateBase&lt; T, bool &gt;::reserveForParamAndGetAddress</a>, <a href="/web-llvm/docs/api/classes/llvm/smallvectortemplatebase-d7d249fb8bb1e1b13d21e8212052041a/#a31714b59605e59bf0543a765b3229096">llvm::SmallVectorTemplateBase&lt; T, true &gt;::reserveForParamAndGetAddress</a>, <a href="/web-llvm/docs/api/classes/llvm/smallvectortemplatebase-d7d249fb8bb1e1b13d21e8212052041a/#a8ada7545d53f82f040ad72cd9b137f00">llvm::SmallVectorTemplateBase&lt; T, true &gt;::reserveForParamAndGetAddress</a>, <a href="/web-llvm/docs/api/classes/llvm/smallvectortemplatecommon/#a4ff60fb0f0d249b4623327ef5976867b">llvm::SmallVectorTemplateCommon&lt; T, typename &gt;::reserveForParamAndGetAddressImpl</a>, <a href="/web-llvm/docs/api/classes/anonymous-metadataloader-cpp-/bitcodereadermetadatalist/#a61f3398b755fb2a680120c0d546b738a">anonymous{MetadataLoader.cpp}::BitcodeReaderMetadataList::resize</a>, <a href="/web-llvm/docs/api/classes/llvm/bitcodereadervaluelist/#a4a6b947102b7ca6325cdc32aa028505e">llvm::BitcodeReaderValueList::resize</a>, <a href="/web-llvm/docs/api/classes/llvm/bitvector/#a32859a24aa7a3be269855b989d92a4b4">llvm::BitVector::resize</a>, <a href="/web-llvm/docs/api/classes/llvm/smallvectorimpl/#ad0b3d8447f88377b62d9c019f3c4e118">llvm::const_iterator&lt; MemoryLocation &gt;::resize</a>, <a href="/web-llvm/docs/api/classes/llvm/smallvectorimpl/#a93f4e8afe33c15857b55c643ef09efce">llvm::const_iterator&lt; MemoryLocation &gt;::resize</a>, <a href="/web-llvm/docs/api/classes/llvm/packedvector/#a0856c7e0322e026ec7b88979656506a5">llvm::PackedVector&lt; T, BitNum, BitVectorTy &gt;::resize</a>, <a href="/web-llvm/docs/api/classes/llvm/pagedvector/#a84c9c19fca5d62dc0c891cdc7153ae15">llvm::PagedVector&lt; T, PageSize &gt;::resize</a>, <a href="/web-llvm/docs/api/classes/llvm/smallbitvector/#aa79d9a55d612eb330a0e25dc4170470d">llvm::SmallBitVector::resize</a>, <a href="/web-llvm/docs/api/classes/llvm/smallvectorimpl/#a061dce43d38a8693a30aa71027b7eaad">llvm::const_iterator&lt; MemoryLocation &gt;::resize_for_overwrite</a>, <a href="/web-llvm/docs/api/classes/llvm/mdnode/#a1e374f158a4fbdac4f74797096ced49a">llvm::MDNode::resolveCycles</a>, <a href="/web-llvm/docs/api/classes/llvm/stringref/#a56e7e0bebc570bc6814cdefd1f2ecda3">llvm::StringRef::rfind_insensitive</a>, <a href="/web-llvm/docs/api/classes/llvm/rootddgnode/#a64337eb0c9dad4529acc430a671e2082">llvm::RootDDGNode::RootDDGNode</a>, <a href="/web-llvm/docs/api/classes/llvm/rootddgnode/#ae091c0615ac8b3a516724b5c46d83fd5">llvm::RootDDGNode::RootDDGNode</a>, <a href="/web-llvm/docs/api/classes/llvm/ropepiecebtreeiterator/#a99a2ebd12c9a292e0381d3a94f2f6ee0">llvm::RopePieceBTreeIterator::RopePieceBTreeIterator</a>, <a href="/web-llvm/docs/api/classes/llvm/ropepiecebtreeiterator/#a55a2ecf8e4070a3b18e48b780cdd6f51">llvm::RopePieceBTreeIterator::RopePieceBTreeIterator</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#aef2599d8a5a682c348b25f74051cdb2d">llvm::rotl</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a06620855572cf0307aea15a25099df47">llvm::rotr</a>, <a href="/web-llvm/docs/api/structs/anonymous-hexagonloopidiomrecognition-cpp-/simplifier/rule/#a3ee1ad7963e2910532ceab8f03e2a067">anonymous{HexagonLoopIdiomRecognition.cpp}::Simplifier::Rule::Rule</a>, <a href="/web-llvm/docs/api/classes/anonymous-dagcombiner-cpp-/dagcombiner/#ac8513ff0e5a1f54815ec2807648fe0f6">anonymous{DAGCombiner.cpp}::DAGCombiner::Run</a>, <a href="/web-llvm/docs/api/classes/anonymous-gvnsink-cpp-/gvnsink/#a900ef156c51ab7bbcff3a4d45856a670">anonymous{GVNSink.cpp}::GVNSink::run</a>, <a href="/web-llvm/docs/api/structs/anonymous-hexagonrdfopt-cpp-/hexagondce/#a2fdc22ba5c1d80ca60c2adcd35b3cd41">anonymous{HexagonRDFOpt.cpp}::HexagonDCE::run</a>, <a href="/web-llvm/docs/api/classes/anonymous-machinelicm-cpp-/machinelicmimpl/#a91e4daed2453931a75ea961f1dce12ad">anonymous{MachineLICM.cpp}::MachineLICMImpl::run</a>, <a href="/web-llvm/docs/api/classes/llvm/argumentpromotionpass/#afe0f49f9daec2532b14ded30ed46ff28">llvm::ArgumentPromotionPass::run</a>, <a href="/web-llvm/docs/api/structs/llvm/attributorcgsccpass/#a305cbdd90350f05f5ee772811d596ded">llvm::AttributorCGSCCPass::run</a>, <a href="/web-llvm/docs/api/structs/llvm/attributorlightcgsccpass/#a1725467ef5883a44e7777d681c6a4d32">llvm::AttributorLightCGSCCPass::run</a>, <a href="/web-llvm/docs/api/structs/llvm/breakcriticaledgespass/#a5f8ef6ce9ef2eb4568d48e3530b5652d">llvm::BreakCriticalEdgesPass::run</a>, <a href="/web-llvm/docs/api/classes/llvm/cgscctofunctionpassadaptor/#a44a083f826f2f2a189d3979eb43dd5ed">llvm::CGSCCToFunctionPassAdaptor::run</a>, <a href="/web-llvm/docs/api/structs/llvm/coroannotationelidepass/#a411202dc502ac666302ba81c40e94b10">llvm::CoroAnnotationElidePass::run</a>, <a href="/web-llvm/docs/api/structs/llvm/corosplitpass/#a47f6589634ad33a13369ace133b9f4b2">llvm::CoroSplitPass::run</a>, <a href="/web-llvm/docs/api/classes/llvm/dagtypelegalizer/#a39cafb39798d9b0f3b611b9ee0fff149">llvm::DAGTypeLegalizer::run</a>, <a href="/web-llvm/docs/api/classes/llvm/devirtsccrepeatedpass/#a11597e1847c3156c4866aa0a43a1b71b">llvm::DevirtSCCRepeatedPass::run</a>, <a href="/web-llvm/docs/api/classes/llvm/functionspecializer/#a27893e2167969de71fd88771382a93ad">llvm::FunctionSpecializer::run</a>, <a href="/web-llvm/docs/api/classes/llvm/hipstdparacceleratorcodeselectionpass/#a3c59b50e60a44b5fa3871d0449aa4744">llvm::HipStdParAcceleratorCodeSelectionPass::run</a>, <a href="/web-llvm/docs/api/classes/llvm/inlinerpass/#a78e09cea341cfdf58869920175c52d82">llvm::InlinerPass::run</a>, <a href="/web-llvm/docs/api/classes/llvm/openmpoptcgsccpass/#a9d4366d9c2f6de53d6f2edce548577ab">llvm::OpenMPOptCGSCCPass::run</a>, <a href="/web-llvm/docs/api/structs/llvm/postorderfunctionattrspass/#a8312d250d0f7b4407b4bad97293e5865">llvm::PostOrderFunctionAttrsPass::run</a>, <a href="/web-llvm/docs/api/structs/llvm/rdf/copypropagation/#ab5cc393f3a921f0a6fe0505561a80e23">llvm::rdf::CopyPropagation::run</a>, <a href="/web-llvm/docs/api/classes/llvm/regtomempass/#a0a8fbb23329369eafe88acc194f6336d">llvm::RegToMemPass::run</a>, <a href="/web-llvm/docs/api/classes/anonymous-dataflowsanitizer-cpp-/dataflowsanitizer/#ab4d94a2774e8420abe5e331d94334cec">anonymous{DataFlowSanitizer.cpp}::DataFlowSanitizer::runImpl</a>, <a href="/web-llvm/docs/api/files/lib/lib/codegen/jmcinstrumenter-cpp/#a8fe56fea0dcbc78bba2366b7e2918a41">runImpl</a>, <a href="/web-llvm/docs/api/structs/anonymous-breakcriticaledges-cpp-/breakcriticaledges/#a1c9d2281808f2cebaf85dc0206fd4409">anonymous{BreakCriticalEdges.cpp}::BreakCriticalEdges::runOnFunction</a>, <a href="/web-llvm/docs/api/classes/llvm/regtomemwrapperpass/#aed9a7685d9b8b8775099d95d27898b74">llvm::RegToMemWrapperPass::runOnFunction</a>, <a href="/web-llvm/docs/api/structs/llvm/domtreebuilder/semincainfo/#a6b01145051cf194d0efb2b7ae241f24c">llvm::DomTreeBuilder::SemiNCAInfo&lt; DomTreeT &gt;::runSemiNCA</a>, <a href="/web-llvm/docs/api/classes/anonymous-riscvtargetmachine-cpp-/rvvregisterregalloc/#a8f45b46a8dddb92f59e625e2e0765bd9">anonymous{RISCVTargetMachine.cpp}::RVVRegisterRegAlloc::RVVRegisterRegAlloc</a>, <a href="/web-llvm/docs/api/structs/anonymous-systemziseldagtodag-cpp-/rxsbgoperands/#a4b2d6d1e99db7d3b107024307650bc0d">anonymous{SystemZISelDAGToDAG.cpp}::RxSBGOperands::RxSBGOperands</a>, <a href="/web-llvm/docs/api/classes/llvm/intervalmapimpl/branchnode/#a82c9083e2fef87017cef1611b1380a18">llvm::IntervalMapImpl::BranchNode&lt; KeyT, ValT, Sizer::BranchSize, Traits &gt;::safeFind</a>, <a href="/web-llvm/docs/api/classes/llvm/intervalmapimpl/leafnode/#a00c255e0d7969726d82306a392298061">llvm::IntervalMapImpl::LeafNode&lt; KeyT, ValT, Sizer::LeafSize, Traits &gt;::safeFind</a>, <a href="/web-llvm/docs/api/classes/llvm/selectiondag/#a582354e8d5806847614742270d2ece1d">llvm::SelectionDAG::salvageDebugInfo</a>, <a href="/web-llvm/docs/api/structs/anonymous-msgpackdocumentyaml-cpp-/scalardocnode/#a2e240b31940358d89a17fe15ae402220">anonymous{MsgPackDocumentYAML.cpp}::ScalarDocNode::ScalarDocNode</a>, <a href="/web-llvm/docs/api/classes/llvm/scevaddexpr/#a15a0237aaba54972c69acad43448c093">llvm::SCEVAddExpr::ScalarEvolution</a>, <a href="/web-llvm/docs/api/classes/llvm/scevaddrecexpr/#a15a0237aaba54972c69acad43448c093">llvm::SCEVAddRecExpr::ScalarEvolution</a>, <a href="/web-llvm/docs/api/classes/llvm/scevmulexpr/#a15a0237aaba54972c69acad43448c093">llvm::SCEVMulExpr::ScalarEvolution</a>, <a href="/web-llvm/docs/api/classes/llvm/scevsequentialuminexpr/#a15a0237aaba54972c69acad43448c093">llvm::SCEVSequentialUMinExpr::ScalarEvolution</a>, <a href="/web-llvm/docs/api/classes/llvm/scevsmaxexpr/#a15a0237aaba54972c69acad43448c093">llvm::SCEVSMaxExpr::ScalarEvolution</a>, <a href="/web-llvm/docs/api/classes/llvm/scevsminexpr/#a15a0237aaba54972c69acad43448c093">llvm::SCEVSMinExpr::ScalarEvolution</a>, <a href="/web-llvm/docs/api/classes/llvm/scevumaxexpr/#a15a0237aaba54972c69acad43448c093">llvm::SCEVUMaxExpr::ScalarEvolution</a>, <a href="/web-llvm/docs/api/classes/llvm/scevuminexpr/#a15a0237aaba54972c69acad43448c093">llvm::SCEVUMinExpr::ScalarEvolution</a>, <a href="/web-llvm/docs/api/files/lib/lib/codegen/lib/codegen/selectiondag/dagcombiner-cpp/#ae002ed884c63140cccb45d854b6bd013">scalarizeBinOpOfSplats</a>, <a href="/web-llvm/docs/api/structs/llvm/instrprofrecord/#afd434b7b22d9c00ba33a833940c91601">llvm::InstrProfRecord::scale</a>, <a href="/web-llvm/docs/api/structs/llvm/instrprofvaluesiterecord/#afd0859657dd371b027ded06a77e2e75e">llvm::InstrProfValueSiteRecord::scale</a>, <a href="/web-llvm/docs/api/classes/llvm/scalednumber/#a92df8a4251e18ddbe27e55c5d23899c0">llvm::ScaledNumber&lt; DigitsT &gt;::scale</a>, <a href="/web-llvm/docs/api/classes/llvm/scalednumber/#af9c95ee1e042eab1ec9f028be9f5cf8c">llvm::ScaledNumber&lt; uint64_t &gt;::scale</a>, <a href="/web-llvm/docs/api/classes/llvm/scalednumber/#a92df8a4251e18ddbe27e55c5d23899c0">llvm::ScaledNumber&lt; uint64_t &gt;::scale</a>, <a href="/web-llvm/docs/api/files/lib/lib/support/branchprobability-cpp/#aa8c7ae7da7990d5320b67c57f6fc3b59">scale</a>, <a href="/web-llvm/docs/api/classes/llvm/scalednumber/#aac4d59e63e8bb2995912168ea3b3d8e1">llvm::ScaledNumber&lt; uint64_t &gt;::scaleByInverse</a>, <a href="/web-llvm/docs/api/classes/llvm/scalednumber/#abb08f96a13cf1975ca8f7636cca13e65">llvm::ScaledNumber&lt; uint64_t &gt;::scaleByInverse</a>, <a href="/web-llvm/docs/api/files/lib/lib/codegen/registerscavenging-cpp/#a9029683bf2a81e8247c168501e85a8b4">scavengeFrameVirtualRegsInBlock</a>, <a href="/web-llvm/docs/api/namespaces/anonymous-standardinstrumentations-cpp-/#a39511cefb89ce99c011d1d0d1cfce663">anonymous{StandardInstrumentations.cpp}::sccContainsFilterPrintFunc</a>, <a href="/web-llvm/docs/api/classes/llvm/scevcommutativeexpr/#a6786459f166c925afb763d543d57daaa">llvm::SCEVCommutativeExpr::SCEVCommutativeExpr</a>, <a href="/web-llvm/docs/api/classes/llvm/scevminmaxexpr/#aa3394585e4782cd066626d4df6a341de">llvm::SCEVMinMaxExpr::SCEVMinMaxExpr</a>, <a href="/web-llvm/docs/api/classes/llvm/scevnaryexpr/#a76d2af00b10cda0b511a84a742d13f00">llvm::SCEVNAryExpr::SCEVNAryExpr</a>, <a href="/web-llvm/docs/api/classes/llvm/scevsequentialminmaxexpr/#a2569193b6e3198b19ca3a210e8f450bd">llvm::SCEVSequentialMinMaxExpr::SCEVSequentialMinMaxExpr</a>, <a href="/web-llvm/docs/api/classes/llvm/sandboxir/schedbundle/#a163f51beccbf4c13d8ce92cd8083ce02">llvm::sandboxir::SchedBundle::SchedBundle</a>, <a href="/web-llvm/docs/api/structs/anonymous-machinescheduler-cpp-/schedregion/#a4393cd1869923adcedef312efbea07be">anonymous{MachineScheduler.cpp}::SchedRegion::SchedRegion</a>, <a href="/web-llvm/docs/api/classes/anonymous-scheduledagfast-cpp-/scheduledaglinearize/#ac5dfad52f2ec0adbc920cf686c615e00">anonymous{ScheduleDAGFast.cpp}::ScheduleDAGLinearize::Schedule</a>, <a href="/web-llvm/docs/api/namespaces/llvm/sdpatternmatch/#aae860ccc89c4e15dc5c7aeffc6c70d08">llvm::SDPatternMatch::sd_context_match</a>, <a href="/web-llvm/docs/api/namespaces/llvm/sdpatternmatch/#af8425e06dcc0a862a898887c9baca083">llvm::SDPatternMatch::sd_context_match</a>, <a href="/web-llvm/docs/api/namespaces/llvm/sdpatternmatch/#ac35245ebc6cb2872fc37ba3cb8919b8e">llvm::SDPatternMatch::sd_match</a>, <a href="/web-llvm/docs/api/namespaces/llvm/sdpatternmatch/#a22e69d98d1e6e8f2308ede1c5809d0ac">llvm::SDPatternMatch::sd_match</a>, <a href="/web-llvm/docs/api/namespaces/llvm/sdpatternmatch/#a79d92d025e8221b41f34695cefdc5cd2">llvm::SDPatternMatch::sd_match</a>, <a href="/web-llvm/docs/api/namespaces/llvm/sdpatternmatch/#ac5a99fed92f12ccb41d56d1039b132c4">llvm::SDPatternMatch::sd_match</a>, <a href="/web-llvm/docs/api/classes/llvm/sdloc/#ab547baa9b958a27de005b90f74c5ffda">llvm::SDLoc::SDLoc</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/arm/armisellowering-cpp/#aedbdd7f517337906e23fbfc8ca72bfe2">SearchLoopIntrinsic</a>, <a href="/web-llvm/docs/api/structs/anonymous-xcoffobjectwriter-cpp-/sectionentry/#a6b7a3c345f4636c39dc88bff87582e91">anonymous{XCOFFObjectWriter.cpp}::SectionEntry::SectionEntry</a>, <a href="/web-llvm/docs/api/classes/anonymous-arciseldagtodag-cpp-/arcdagtodagisel/#a0a5b85d65e1849dee238ae2564d57953">anonymous{ARCISelDAGToDAG.cpp}::ARCDAGToDAGISel::Select</a>, <a href="/web-llvm/docs/api/classes/anonymous-armiseldagtodag-cpp-/armdagtodagisel/#a11372c88b31dcfd60fd4ef5d1bee8283">anonymous{ARMISelDAGToDAG.cpp}::ARMDAGToDAGISel::Select</a>, <a href="/web-llvm/docs/api/classes/anonymous-cskyiseldagtodag-cpp-/cskydagtodagisel/#a0a02f0891dd438323dc928dcef5081af">anonymous{CSKYISelDAGToDAG.cpp}::CSKYDAGToDAGISel::Select</a>, <a href="/web-llvm/docs/api/classes/anonymous-ppciseldagtodag-cpp-/bitpermutationselector/#a7084f717d525cea75708471b0acda302">anonymous{PPCISelDAGToDAG.cpp}::BitPermutationSelector::Select</a>, <a href="/web-llvm/docs/api/classes/anonymous-ppciseldagtodag-cpp-/integercompareeliminator/#a09fe3134a2922596d0704bf13f38560d">anonymous{PPCISelDAGToDAG.cpp}::IntegerCompareEliminator::Select</a>, <a href="/web-llvm/docs/api/classes/anonymous-ppciseldagtodag-cpp-/ppcdagtodagisel/#a77bc2aad31cb4ad41441222b28c8080c">anonymous{PPCISelDAGToDAG.cpp}::PPCDAGToDAGISel::Select</a>, <a href="/web-llvm/docs/api/classes/anonymous-r600iseldagtodag-cpp-/r600dagtodagisel/#a526fd2710d7457e09c2b4715b2367638">anonymous{R600ISelDAGToDAG.cpp}::R600DAGToDAGISel::Select</a>, <a href="/web-llvm/docs/api/classes/anonymous-sparciseldagtodag-cpp-/sparcdagtodagisel/#a4836a2e7db7d52a6bad08583011c60ff">anonymous{SparcISelDAGToDAG.cpp}::SparcDAGToDAGISel::Select</a>, <a href="/web-llvm/docs/api/classes/anonymous-veiseldagtodag-cpp-/vedagtodagisel/#a3a78b32f7bfd763634c0dd8f40737197">anonymous{VEISelDAGToDAG.cpp}::VEDAGToDAGISel::Select</a>, <a href="/web-llvm/docs/api/classes/anonymous-xcoreiseldagtodag-cpp-/xcoredagtodagisel/#a4b1c5b30230a9be2aa310c91d8dccf20">anonymous{XCoreISelDAGToDAG.cpp}::XCoreDAGToDAGISel::Select</a>, <a href="/web-llvm/docs/api/classes/llvm/amdgpudagtodagisel/#a4e1374fde17218f949e94ee57e18dc2c">llvm::AMDGPUDAGToDAGISel::Select</a>, <a href="/web-llvm/docs/api/classes/llvm/hexagondagtodagisel/#a41ef1b51e44cf199895c183cdc0a5b4c">llvm::HexagonDAGToDAGISel::Select</a>, <a href="/web-llvm/docs/api/classes/llvm/loongarchdagtodagisel/#aa5cd8d52437d1cc21d1dd127ada97559">llvm::LoongArchDAGToDAGISel::Select</a>, <a href="/web-llvm/docs/api/classes/llvm/riscvdagtodagisel/#a7d60a41c0d5e450f770042d3427928d0">llvm::RISCVDAGToDAGISel::Select</a>, <a href="/web-llvm/docs/api/classes/llvm/selectiondagisel/#a627055cc49ee176892512534877d1af6">llvm::SelectionDAGISel::Select</a>, <a href="/web-llvm/docs/api/classes/anonymous-cskyiseldagtodag-cpp-/cskydagtodagisel/#a75b8d8ea2b3a98a9bae9ec623007b6a0">anonymous{CSKYISelDAGToDAG.cpp}::CSKYDAGToDAGISel::selectAddCarry</a>, <a href="/web-llvm/docs/api/classes/anonymous-armiseldagtodag-cpp-/armdagtodagisel/#af829baf84aa61aab9b55f9196427759a">anonymous{ARMISelDAGToDAG.cpp}::ARMDAGToDAGISel::SelectAddLikeOr</a>, <a href="/web-llvm/docs/api/classes/anonymous-avriseldagtodag-cpp-/avrdagtodagisel/#a042feb8b79c4f631fd4b6d7452f48395">anonymous{AVRISelDAGToDAG.cpp}::AVRDAGToDAGISel::SelectAddr</a>, <a href="/web-llvm/docs/api/classes/anonymous-ppciseldagtodag-cpp-/ppcdagtodagisel/#a6931f19f358494cec46015be8d440500">anonymous{PPCISelDAGToDAG.cpp}::PPCDAGToDAGISel::SelectAddr</a>, <a href="/web-llvm/docs/api/classes/llvm/ppctargetlowering/#aec3b0201c5cd00acf45cc4eb33708687">llvm::PPCTargetLowering::SelectAddressEVXRegReg</a>, <a href="/web-llvm/docs/api/classes/llvm/ppctargetlowering/#ae882b4864ba6e86e417710e0b990b6d6">llvm::PPCTargetLowering::SelectAddressPCRel</a>, <a href="/web-llvm/docs/api/classes/llvm/ppctargetlowering/#a312de8232fec3e0e128f4a34b7ddc55d">llvm::PPCTargetLowering::SelectAddressRegImm</a>, <a href="/web-llvm/docs/api/classes/llvm/ppctargetlowering/#adaf95509430b29d867f49362e176027d">llvm::PPCTargetLowering::SelectAddressRegImm34</a>, <a href="/web-llvm/docs/api/classes/llvm/ppctargetlowering/#a521dc9b8649af234d8bf514085b9a640">llvm::PPCTargetLowering::SelectAddressRegReg</a>, <a href="/web-llvm/docs/api/classes/llvm/ppctargetlowering/#a5dc501f0601464ff8459b49b60b29140">llvm::PPCTargetLowering::SelectAddressRegRegOnly</a>, <a href="/web-llvm/docs/api/classes/llvm/hexagondagtodagisel/#aa5ffc8ad80e12c7f12a3ce994c083691">llvm::HexagonDAGToDAGISel::SelectAddrFI</a>, <a href="/web-llvm/docs/api/classes/llvm/hexagondagtodagisel/#ad82490861a604d6457d0303de8a6dd71">llvm::HexagonDAGToDAGISel::SelectAddrGA</a>, <a href="/web-llvm/docs/api/classes/llvm/hexagondagtodagisel/#abfabded517d3209aa4c255d960084594">llvm::HexagonDAGToDAGISel::SelectAddrGP</a>, <a href="/web-llvm/docs/api/classes/anonymous-ppciseldagtodag-cpp-/ppcdagtodagisel/#a9d8186c7c451237496285289e500d767">anonymous{PPCISelDAGToDAG.cpp}::PPCDAGToDAGISel::SelectAddrIdx</a>, <a href="/web-llvm/docs/api/classes/anonymous-ppciseldagtodag-cpp-/ppcdagtodagisel/#a4ee86bfe2f1ee82d58ea774a002f39ee">anonymous{PPCISelDAGToDAG.cpp}::PPCDAGToDAGISel::SelectAddrIdxOnly</a>, <a href="/web-llvm/docs/api/classes/anonymous-ppciseldagtodag-cpp-/ppcdagtodagisel/#ac5b50976d9722bf4747e8bfca4999eba">anonymous{PPCISelDAGToDAG.cpp}::PPCDAGToDAGISel::SelectAddrIdxX16</a>, <a href="/web-llvm/docs/api/classes/anonymous-ppciseldagtodag-cpp-/ppcdagtodagisel/#ab64aad15e6ca6e1d636c8dba77158137">anonymous{PPCISelDAGToDAG.cpp}::PPCDAGToDAGISel::SelectAddrIdxX4</a>, <a href="/web-llvm/docs/api/classes/anonymous-ppciseldagtodag-cpp-/ppcdagtodagisel/#a0c0a50338d1fb9d7177958ad0cbad701">anonymous{PPCISelDAGToDAG.cpp}::PPCDAGToDAGISel::SelectAddrImm</a>, <a href="/web-llvm/docs/api/classes/anonymous-ppciseldagtodag-cpp-/ppcdagtodagisel/#aba6e8fc4ecfe9de885837c27e9102491">anonymous{PPCISelDAGToDAG.cpp}::PPCDAGToDAGISel::SelectAddrImmOffs</a>, <a href="/web-llvm/docs/api/classes/anonymous-ppciseldagtodag-cpp-/ppcdagtodagisel/#aca4d74dc26c2823424663e2bc5454540">anonymous{PPCISelDAGToDAG.cpp}::PPCDAGToDAGISel::SelectAddrImmX16</a>, <a href="/web-llvm/docs/api/classes/anonymous-ppciseldagtodag-cpp-/ppcdagtodagisel/#a6c5846b80e7e757ab3abc5bf545f3668">anonymous{PPCISelDAGToDAG.cpp}::PPCDAGToDAGISel::SelectAddrImmX34</a>, <a href="/web-llvm/docs/api/classes/anonymous-ppciseldagtodag-cpp-/ppcdagtodagisel/#a3eff5989d155f6a5dfb3d14351826cc4">anonymous{PPCISelDAGToDAG.cpp}::PPCDAGToDAGISel::SelectAddrImmX4</a>, <a href="/web-llvm/docs/api/classes/anonymous-armiseldagtodag-cpp-/armdagtodagisel/#ac2a883d3da363288434a1110d9c275f0">anonymous{ARMISelDAGToDAG.cpp}::ARMDAGToDAGISel::SelectAddrMode2OffsetImm</a>, <a href="/web-llvm/docs/api/classes/anonymous-armiseldagtodag-cpp-/armdagtodagisel/#a60b48230d0fc952979f69fd95557ab3c">anonymous{ARMISelDAGToDAG.cpp}::ARMDAGToDAGISel::SelectAddrMode2OffsetImmPre</a>, <a href="/web-llvm/docs/api/classes/anonymous-armiseldagtodag-cpp-/armdagtodagisel/#a54dfd9d8e05d4813fa85c9877c0e270a">anonymous{ARMISelDAGToDAG.cpp}::ARMDAGToDAGISel::SelectAddrMode2OffsetReg</a>, <a href="/web-llvm/docs/api/classes/anonymous-armiseldagtodag-cpp-/armdagtodagisel/#abb5c2f66d44327ca2fceb3bf57801150">anonymous{ARMISelDAGToDAG.cpp}::ARMDAGToDAGISel::SelectAddrMode3</a>, <a href="/web-llvm/docs/api/classes/anonymous-armiseldagtodag-cpp-/armdagtodagisel/#a2831c4e1d62a6a8ebe8754d541736f1b">anonymous{ARMISelDAGToDAG.cpp}::ARMDAGToDAGISel::SelectAddrMode3Offset</a>, <a href="/web-llvm/docs/api/classes/anonymous-armiseldagtodag-cpp-/armdagtodagisel/#a35d7f28a8b4caff6a99ed653331205ff">anonymous{ARMISelDAGToDAG.cpp}::ARMDAGToDAGISel::SelectAddrMode5</a>, <a href="/web-llvm/docs/api/classes/anonymous-armiseldagtodag-cpp-/armdagtodagisel/#aa00a4706052572feea4548563d36f878">anonymous{ARMISelDAGToDAG.cpp}::ARMDAGToDAGISel::SelectAddrMode5FP16</a>, <a href="/web-llvm/docs/api/classes/anonymous-armiseldagtodag-cpp-/armdagtodagisel/#ae29a60720e41fdf677935d16ad9d3b5b">anonymous{ARMISelDAGToDAG.cpp}::ARMDAGToDAGISel::SelectAddrMode6</a>, <a href="/web-llvm/docs/api/classes/anonymous-armiseldagtodag-cpp-/armdagtodagisel/#abe588c29e26c909dcffe4c763aacaffe">anonymous{ARMISelDAGToDAG.cpp}::ARMDAGToDAGISel::SelectAddrMode6Offset</a>, <a href="/web-llvm/docs/api/classes/anonymous-aarch64iseldagtodag-cpp-/aarch64dagtodagisel/#a7d38c986b9dd1432432299136a1f05bd">anonymous{AArch64ISelDAGToDAG.cpp}::AArch64DAGToDAGISel::SelectAddrModeFrameIndexSVE</a>, <a href="/web-llvm/docs/api/classes/anonymous-armiseldagtodag-cpp-/armdagtodagisel/#a561582d24bb367fbf303e5a349906800">anonymous{ARMISelDAGToDAG.cpp}::ARMDAGToDAGISel::SelectAddrModeImm12</a>, <a href="/web-llvm/docs/api/classes/anonymous-aarch64iseldagtodag-cpp-/aarch64dagtodagisel/#aef900ac84eac7551b0060cbbab92e692">anonymous{AArch64ISelDAGToDAG.cpp}::AArch64DAGToDAGISel::SelectAddrModeIndexed128</a>, <a href="/web-llvm/docs/api/classes/anonymous-aarch64iseldagtodag-cpp-/aarch64dagtodagisel/#a2144be3ae774e6136afa598cbe70ceff">anonymous{AArch64ISelDAGToDAG.cpp}::AArch64DAGToDAGISel::SelectAddrModeIndexed16</a>, <a href="/web-llvm/docs/api/classes/anonymous-aarch64iseldagtodag-cpp-/aarch64dagtodagisel/#a0901fd709662ad4f7225576625bef842">anonymous{AArch64ISelDAGToDAG.cpp}::AArch64DAGToDAGISel::SelectAddrModeIndexed32</a>, <a href="/web-llvm/docs/api/classes/anonymous-aarch64iseldagtodag-cpp-/aarch64dagtodagisel/#a5c619f02ebbecf66d23f0903565d7107">anonymous{AArch64ISelDAGToDAG.cpp}::AArch64DAGToDAGISel::SelectAddrModeIndexed64</a>, <a href="/web-llvm/docs/api/classes/anonymous-aarch64iseldagtodag-cpp-/aarch64dagtodagisel/#a45eabc1ca0fa1f3a618dee04527bb890">anonymous{AArch64ISelDAGToDAG.cpp}::AArch64DAGToDAGISel::SelectAddrModeIndexed7S128</a>, <a href="/web-llvm/docs/api/classes/anonymous-aarch64iseldagtodag-cpp-/aarch64dagtodagisel/#adb40774135cbb73afb66666bd56c2653">anonymous{AArch64ISelDAGToDAG.cpp}::AArch64DAGToDAGISel::SelectAddrModeIndexed7S16</a>, <a href="/web-llvm/docs/api/classes/anonymous-aarch64iseldagtodag-cpp-/aarch64dagtodagisel/#a42429a0f8343058d13f546c1b49a9fc0">anonymous{AArch64ISelDAGToDAG.cpp}::AArch64DAGToDAGISel::SelectAddrModeIndexed7S32</a>, <a href="/web-llvm/docs/api/classes/anonymous-aarch64iseldagtodag-cpp-/aarch64dagtodagisel/#a2d06713e8cb3fc3a9a560997a1188c75">anonymous{AArch64ISelDAGToDAG.cpp}::AArch64DAGToDAGISel::SelectAddrModeIndexed7S64</a>, <a href="/web-llvm/docs/api/classes/anonymous-aarch64iseldagtodag-cpp-/aarch64dagtodagisel/#a2fb2adc1f9dbc6a7f0314f72b6568c76">anonymous{AArch64ISelDAGToDAG.cpp}::AArch64DAGToDAGISel::SelectAddrModeIndexed7S8</a>, <a href="/web-llvm/docs/api/classes/anonymous-aarch64iseldagtodag-cpp-/aarch64dagtodagisel/#aefea7466b30a05b8b4e49c57b1ec96e0">anonymous{AArch64ISelDAGToDAG.cpp}::AArch64DAGToDAGISel::SelectAddrModeIndexed8</a>, <a href="/web-llvm/docs/api/classes/anonymous-aarch64iseldagtodag-cpp-/aarch64dagtodagisel/#ab5f68324b3650d88de88da549a46e8bb">anonymous{AArch64ISelDAGToDAG.cpp}::AArch64DAGToDAGISel::SelectAddrModeIndexedS9S128</a>, <a href="/web-llvm/docs/api/classes/anonymous-aarch64iseldagtodag-cpp-/aarch64dagtodagisel/#a0e48eed8c71f1e31ececec593aa98908">anonymous{AArch64ISelDAGToDAG.cpp}::AArch64DAGToDAGISel::SelectAddrModeIndexedSVE</a>, <a href="/web-llvm/docs/api/classes/anonymous-aarch64iseldagtodag-cpp-/aarch64dagtodagisel/#a2723fc438110273d619f6bfd9123c73a">anonymous{AArch64ISelDAGToDAG.cpp}::AArch64DAGToDAGISel::SelectAddrModeIndexedU6S128</a>, <a href="/web-llvm/docs/api/classes/anonymous-aarch64iseldagtodag-cpp-/aarch64dagtodagisel/#a629888d33a1acde5199a06756427ff90">anonymous{AArch64ISelDAGToDAG.cpp}::AArch64DAGToDAGISel::SelectAddrModeIndexedUImm</a>, <a href="/web-llvm/docs/api/classes/anonymous-armiseldagtodag-cpp-/armdagtodagisel/#a075b3dafc91e9c39ed0f94ba7d604505">anonymous{ARMISelDAGToDAG.cpp}::ARMDAGToDAGISel::SelectAddrModePC</a>, <a href="/web-llvm/docs/api/classes/anonymous-aarch64iseldagtodag-cpp-/aarch64dagtodagisel/#a621d597fb8016b101a40bbc69974401c">anonymous{AArch64ISelDAGToDAG.cpp}::AArch64DAGToDAGISel::SelectAddrModeUnscaled128</a>, <a href="/web-llvm/docs/api/classes/anonymous-aarch64iseldagtodag-cpp-/aarch64dagtodagisel/#a909fba1f01e2fd0d72f92442d3bfbde0">anonymous{AArch64ISelDAGToDAG.cpp}::AArch64DAGToDAGISel::SelectAddrModeUnscaled16</a>, <a href="/web-llvm/docs/api/classes/anonymous-aarch64iseldagtodag-cpp-/aarch64dagtodagisel/#aec0835f1e409d8586b4bf63b0895a6ae">anonymous{AArch64ISelDAGToDAG.cpp}::AArch64DAGToDAGISel::SelectAddrModeUnscaled32</a>, <a href="/web-llvm/docs/api/classes/anonymous-aarch64iseldagtodag-cpp-/aarch64dagtodagisel/#a7706f7555772e51b20b71f51e850024f">anonymous{AArch64ISelDAGToDAG.cpp}::AArch64DAGToDAGISel::SelectAddrModeUnscaled64</a>, <a href="/web-llvm/docs/api/classes/anonymous-aarch64iseldagtodag-cpp-/aarch64dagtodagisel/#a95a0d358b5271c63f1c1632f95a4ceef">anonymous{AArch64ISelDAGToDAG.cpp}::AArch64DAGToDAGISel::SelectAddrModeUnscaled8</a>, <a href="/web-llvm/docs/api/classes/anonymous-aarch64iseldagtodag-cpp-/aarch64dagtodagisel/#aae04fb557e2c3c1c818894853af5b8e9">anonymous{AArch64ISelDAGToDAG.cpp}::AArch64DAGToDAGISel::SelectAddrModeWRO</a>, <a href="/web-llvm/docs/api/classes/anonymous-aarch64iseldagtodag-cpp-/aarch64dagtodagisel/#ab94aeed35e5445cadd4d56a34d3e05ea">anonymous{AArch64ISelDAGToDAG.cpp}::AArch64DAGToDAGISel::SelectAddrModeXRO</a>, <a href="/web-llvm/docs/api/classes/anonymous-armiseldagtodag-cpp-/armdagtodagisel/#ad07286568f7af8cc03f4d3e7afc0b695">anonymous{ARMISelDAGToDAG.cpp}::ARMDAGToDAGISel::SelectAddrOffsetNone</a>, <a href="/web-llvm/docs/api/classes/anonymous-ppciseldagtodag-cpp-/ppcdagtodagisel/#abcbf48892d45d9045a4b43189fab8edc">anonymous{PPCISelDAGToDAG.cpp}::PPCDAGToDAGISel::SelectAddrPCRel</a>, <a href="/web-llvm/docs/api/classes/llvm/riscvdagtodagisel/#afae779832c7d1fe14084a195e6826071">llvm::RISCVDAGToDAGISel::SelectAddrRegRegScale</a>, <a href="/web-llvm/docs/api/classes/llvm/hexagondagtodagisel/#a1b5b05e33321ac5119b7af3d5326ab28">llvm::HexagonDAGToDAGISel::SelectAddSubCarry</a>, <a href="/web-llvm/docs/api/classes/llvm/hexagondagtodagisel/#a7527b24d85c4aa35171099953fcabfa2">llvm::HexagonDAGToDAGISel::SelectAnyImm</a>, <a href="/web-llvm/docs/api/classes/llvm/hexagondagtodagisel/#a78c6d356aa69c648efe388813d47c60a">llvm::HexagonDAGToDAGISel::SelectAnyImm0</a>, <a href="/web-llvm/docs/api/classes/llvm/hexagondagtodagisel/#a889f711e0bade47ea06c2d5ee5c8bd8e">llvm::HexagonDAGToDAGISel::SelectAnyImm1</a>, <a href="/web-llvm/docs/api/classes/llvm/hexagondagtodagisel/#a72fcfc71c65503d007cb61ea3d73f93a">llvm::HexagonDAGToDAGISel::SelectAnyImm2</a>, <a href="/web-llvm/docs/api/classes/llvm/hexagondagtodagisel/#ac83bd6f6dd6acad0bbf4a5acae1efbf8">llvm::HexagonDAGToDAGISel::SelectAnyImm3</a>, <a href="/web-llvm/docs/api/classes/llvm/hexagondagtodagisel/#ac0b6934aa9318a8cb77d28f412a17879">llvm::HexagonDAGToDAGISel::SelectAnyImmediate</a>, <a href="/web-llvm/docs/api/classes/llvm/hexagondagtodagisel/#ad73feabd95918a5b10656d50bc253abf">llvm::HexagonDAGToDAGISel::SelectAnyInt</a>, <a href="/web-llvm/docs/api/classes/anonymous-aarch64iseldagtodag-cpp-/aarch64dagtodagisel/#ae88467b8c4fa79a40c1f748741344144">anonymous{AArch64ISelDAGToDAG.cpp}::AArch64DAGToDAGISel::SelectArithExtendedRegister</a>, <a href="/web-llvm/docs/api/classes/anonymous-aarch64iseldagtodag-cpp-/aarch64dagtodagisel/#ac2847ce431c05147e95ed196fd1c0658">anonymous{AArch64ISelDAGToDAG.cpp}::AArch64DAGToDAGISel::SelectArithImmed</a>, <a href="/web-llvm/docs/api/classes/anonymous-aarch64iseldagtodag-cpp-/aarch64dagtodagisel/#adc577fa08b1834d86b76d06438d3a6f9">anonymous{AArch64ISelDAGToDAG.cpp}::AArch64DAGToDAGISel::SelectArithShiftedRegister</a>, <a href="/web-llvm/docs/api/classes/anonymous-aarch64iseldagtodag-cpp-/aarch64dagtodagisel/#ab394dff6232fa926e01a45b114152990">anonymous{AArch64ISelDAGToDAG.cpp}::AArch64DAGToDAGISel::SelectArithUXTXRegister</a>, <a href="/web-llvm/docs/api/classes/anonymous-cskyiseldagtodag-cpp-/cskydagtodagisel/#a5bfa88a11c5200afad352e7881d20c6d">anonymous{CSKYISelDAGToDAG.cpp}::CSKYDAGToDAGISel::selectBITCAST_TO_LOHI</a>, <a href="/web-llvm/docs/api/classes/llvm/amdgpudagtodagisel/#a278bc9f5720547f5e171d0a62290d69f">llvm::AMDGPUDAGToDAGISel::SelectBuildVector</a>, <a href="/web-llvm/docs/api/classes/anonymous-aarch64iseldagtodag-cpp-/aarch64dagtodagisel/#a8f19f8c172189a8ba1daa86e7ea1f3a1">anonymous{AArch64ISelDAGToDAG.cpp}::AArch64DAGToDAGISel::SelectClamp</a>, <a href="/web-llvm/docs/api/classes/anonymous-aarch64iseldagtodag-cpp-/aarch64dagtodagisel/#a5102e7b846bb6abd12e621bcee16aa89">anonymous{AArch64ISelDAGToDAG.cpp}::AArch64DAGToDAGISel::SelectCntImm</a>, <a href="/web-llvm/docs/api/classes/llvm/selectiondagisel/#a624f21782a600e972eacbae3e4818fcc">llvm::SelectionDAGISel::SelectCodeCommon</a>, <a href="/web-llvm/docs/api/classes/llvm/hexagondagtodagisel/#a29c057f9f4e7f38857e3ee7f4d25aa97">llvm::HexagonDAGToDAGISel::SelectConstant</a>, <a href="/web-llvm/docs/api/classes/llvm/hexagondagtodagisel/#a8ecfcd1c9f4e07cd69b90aa52aecfccf">llvm::HexagonDAGToDAGISel::SelectConstantFP</a>, <a href="/web-llvm/docs/api/classes/anonymous-aarch64iseldagtodag-cpp-/aarch64dagtodagisel/#a214a3fbd6ca8b38f0fecfd66e2bbfbe1">anonymous{AArch64ISelDAGToDAG.cpp}::AArch64DAGToDAGISel::SelectContiguousMultiVectorLoad</a>, <a href="/web-llvm/docs/api/classes/anonymous-aarch64iseldagtodag-cpp-/aarch64dagtodagisel/#a341d0d63048c4a82f1ca9da8a290928e">anonymous{AArch64ISelDAGToDAG.cpp}::AArch64DAGToDAGISel::SelectCVTIntrinsic</a>, <a href="/web-llvm/docs/api/classes/anonymous-aarch64iseldagtodag-cpp-/aarch64dagtodagisel/#a38bba2501c9933dc2c85c367da23c81f">anonymous{AArch64ISelDAGToDAG.cpp}::AArch64DAGToDAGISel::SelectCVTIntrinsicFP8</a>, <a href="/web-llvm/docs/api/classes/llvm/hexagondagtodagisel/#adb08218875d99573a4daa508630e7732">llvm::HexagonDAGToDAGISel::SelectD2P</a>, <a href="/web-llvm/docs/api/classes/anonymous-aarch64iseldagtodag-cpp-/aarch64dagtodagisel/#aa3a08182b76b413a2809b0228659b498">anonymous{AArch64ISelDAGToDAG.cpp}::AArch64DAGToDAGISel::SelectDestructiveMultiIntrinsic</a>, <a href="/web-llvm/docs/api/classes/anonymous-ppciseldagtodag-cpp-/ppcdagtodagisel/#a28bd480d3b9f6836a2b99766b418f0ef">anonymous{PPCISelDAGToDAG.cpp}::PPCDAGToDAGISel::SelectDForm</a>, <a href="/web-llvm/docs/api/classes/anonymous-ppciseldagtodag-cpp-/ppcdagtodagisel/#acf6d1f527b6d4e5f0bbfcff1e5576971">anonymous{PPCISelDAGToDAG.cpp}::PPCDAGToDAGISel::SelectDQForm</a>, <a href="/web-llvm/docs/api/classes/anonymous-ppciseldagtodag-cpp-/ppcdagtodagisel/#a149a407f65b1895f0dd4a3e27cadd289">anonymous{PPCISelDAGToDAG.cpp}::PPCDAGToDAGISel::SelectDSForm</a>, <a href="/web-llvm/docs/api/classes/anonymous-aarch64iseldagtodag-cpp-/aarch64dagtodagisel/#acb8e4b35251de463c577e1bde4eb7a3c">anonymous{AArch64ISelDAGToDAG.cpp}::AArch64DAGToDAGISel::SelectDupZero</a>, <a href="/web-llvm/docs/api/classes/anonymous-aarch64iseldagtodag-cpp-/aarch64dagtodagisel/#a92eb9951b52d520b6d4c5f0f21b744e5">anonymous{AArch64ISelDAGToDAG.cpp}::AArch64DAGToDAGISel::SelectDupZeroOrUndef</a>, <a href="/web-llvm/docs/api/classes/anonymous-aarch64iseldagtodag-cpp-/aarch64dagtodagisel/#ad53b8fb7bd3b7446cbf63e3af96068fc">anonymous{AArch64ISelDAGToDAG.cpp}::AArch64DAGToDAGISel::SelectEXTImm</a>, <a href="/web-llvm/docs/api/classes/anonymous-aarch64iseldagtodag-cpp-/aarch64dagtodagisel/#a829a79c8cbee3cc9c372d70ab9df47d6">anonymous{AArch64ISelDAGToDAG.cpp}::AArch64DAGToDAGISel::SelectExtractHigh</a>, <a href="/web-llvm/docs/api/classes/llvm/hexagondagtodagisel/#a6420a6b27b9be369ca91fcdf54051ad0">llvm::HexagonDAGToDAGISel::SelectExtractSubvector</a>, <a href="/web-llvm/docs/api/structs/llvm/hvxselector/#ab4355a6f0290136cbba4b0b1a0617914">llvm::HvxSelector::selectExtractSubvector</a>, <a href="/web-llvm/docs/api/classes/llvm/hexagondagtodagisel/#ace602ea17c5ab82470ec20649ac88ce8">llvm::HexagonDAGToDAGISel::SelectFDiv</a>, <a href="/web-llvm/docs/api/classes/anonymous-ppciseldagtodag-cpp-/ppcdagtodagisel/#ad355575328b6adde4d94a15146966f19">anonymous{PPCISelDAGToDAG.cpp}::PPCDAGToDAGISel::SelectForceXForm</a>, <a href="/web-llvm/docs/api/classes/llvm/ppctargetlowering/#a19ee5344b14a547e1ede7370b62402ce">llvm::PPCTargetLowering::SelectForceXFormMode</a>, <a href="/web-llvm/docs/api/classes/llvm/hexagondagtodagisel/#ac57730efce0c1f82628bcdeb5ae42ce9">llvm::HexagonDAGToDAGISel::SelectFrameIndex</a>, <a href="/web-llvm/docs/api/classes/anonymous-ppciseldagtodag-cpp-/ppcdagtodagisel/#aeaa88de6884da5fde45eafb9b11fcb3e">anonymous{PPCISelDAGToDAG.cpp}::PPCDAGToDAGISel::selectFrameIndex</a>, <a href="/web-llvm/docs/api/classes/anonymous-aarch64iseldagtodag-cpp-/aarch64dagtodagisel/#ad1b8a48f44c14ccc0677bf6a3040de9b">anonymous{AArch64ISelDAGToDAG.cpp}::AArch64DAGToDAGISel::SelectFrintFromVT</a>, <a href="/web-llvm/docs/api/classes/llvm/fastisel/#a09eed569d7f0359be47433ca90532f81">llvm::FastISel::selectGetElementPtr</a>, <a href="/web-llvm/docs/api/classes/llvm/hexagondagtodagisel/#ac2657ca8507a7d9b4b8f0e426dd48605">llvm::HexagonDAGToDAGISel::SelectGlobalAddress</a>, <a href="/web-llvm/docs/api/classes/llvm/hexagondagtodagisel/#af89c6506a3b812e8c9126666e1567cde">llvm::HexagonDAGToDAGISel::SelectHVXDualOutput</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/powerpc/ppciseldagtodag-cpp/#a08de6cbf10b840cb8b8a96358ebc90da">selectI64Imm</a>, <a href="/web-llvm/docs/api/classes/anonymous-armiseldagtodag-cpp-/armdagtodagisel/#a19417d4f56c31835cfe0cd676435301a">anonymous{ARMISelDAGToDAG.cpp}::ARMDAGToDAGISel::SelectImmediateInRange</a>, <a href="/web-llvm/docs/api/classes/anonymous-armiseldagtodag-cpp-/armdagtodagisel/#a32d2decc2fbd86ebc9e635bc3aaf56d9">anonymous{ARMISelDAGToDAG.cpp}::ARMDAGToDAGISel::SelectImmShifterOperand</a>, <a href="/web-llvm/docs/api/classes/llvm/hexagondagtodagisel/#a5ed109e1cb014423460d747d1bad657c">llvm::HexagonDAGToDAGISel::SelectIndexedLoad</a>, <a href="/web-llvm/docs/api/classes/anonymous-avriseldagtodag-cpp-/avrdagtodagisel/#a59ecb2f55ede3625b6eec694caa3229f">anonymous{AVRISelDAGToDAG.cpp}::AVRDAGToDAGISel::selectIndexedLoad</a>, <a href="/web-llvm/docs/api/classes/anonymous-cskyiseldagtodag-cpp-/cskydagtodagisel/#aa0b3de3815c7ba67bd6b19ef08ac9f1c">anonymous{CSKYISelDAGToDAG.cpp}::CSKYDAGToDAGISel::selectInlineAsm</a>, <a href="/web-llvm/docs/api/classes/llvm/hexagondagtodagisel/#a805185e4d0df1acb7b434915aaefb5d4">llvm::HexagonDAGToDAGISel::SelectIntrinsicWChain</a>, <a href="/web-llvm/docs/api/classes/llvm/hexagondagtodagisel/#a3201782e33fb12bc813b511152d18ea5">llvm::HexagonDAGToDAGISel::SelectIntrinsicWOChain</a>, <a href="/web-llvm/docs/api/classes/llvm/riscvdagtodagisel/#a6ed9eee21fb8cd7cc428eeafae6b28bc">llvm::RISCVDAGToDAGISel::selectInvLogicImm</a>, <a href="/web-llvm/docs/api/classes/anonymous-armiseldagtodag-cpp-/armdagtodagisel/#a8485253be2e78195ae26f28df0dd41d4">anonymous{ARMISelDAGToDAG.cpp}::ARMDAGToDAGISel::SelectLdStSOReg</a>, <a href="/web-llvm/docs/api/classes/anonymous-aarch64iseldagtodag-cpp-/aarch64dagtodagisel/#a972db3e1a9977766d73a3afa790a18f0">anonymous{AArch64ISelDAGToDAG.cpp}::AArch64DAGToDAGISel::SelectLoad</a>, <a href="/web-llvm/docs/api/classes/llvm/hexagondagtodagisel/#ad375e79751436bc412d0c4e8ccfad806">llvm::HexagonDAGToDAGISel::SelectLoad</a>, <a href="/web-llvm/docs/api/classes/anonymous-aarch64iseldagtodag-cpp-/aarch64dagtodagisel/#a9208ba235fd513181d17277332f9bde2">anonymous{AArch64ISelDAGToDAG.cpp}::AArch64DAGToDAGISel::SelectLoadLane</a>, <a href="/web-llvm/docs/api/classes/anonymous-aarch64iseldagtodag-cpp-/aarch64dagtodagisel/#a640759be1e1562caeb7120109cbcd40e">anonymous{AArch64ISelDAGToDAG.cpp}::AArch64DAGToDAGISel::SelectLogicalShiftedRegister</a>, <a href="/web-llvm/docs/api/classes/llvm/riscvdagtodagisel/#a59b8897a5959dc1ad5ff6311eae5e9b2">llvm::RISCVDAGToDAGISel::selectLow8BitsVSplat</a>, <a href="/web-llvm/docs/api/classes/anonymous-aarch64iseldagtodag-cpp-/aarch64dagtodagisel/#abd77544198274490ba294f1db1cd047c">anonymous{AArch64ISelDAGToDAG.cpp}::AArch64DAGToDAGISel::SelectMultiVectorMove</a>, <a href="/web-llvm/docs/api/classes/anonymous-aarch64iseldagtodag-cpp-/aarch64dagtodagisel/#a49e31bdd17ffc99a430029bcde5480fd">anonymous{AArch64ISelDAGToDAG.cpp}::AArch64DAGToDAGISel::SelectMultiVectorMoveZ</a>, <a href="/web-llvm/docs/api/classes/anonymous-aarch64iseldagtodag-cpp-/aarch64dagtodagisel/#a10910de44009fd6010d6e09fa462a095">anonymous{AArch64ISelDAGToDAG.cpp}::AArch64DAGToDAGISel::SelectNegArithImmed</a>, <a href="/web-llvm/docs/api/classes/llvm/selectiondag/#a1eba17da85627807b4dab5ddc14d2c8e">llvm::SelectionDAG::SelectNodeTo</a>, <a href="/web-llvm/docs/api/classes/llvm/selectiondag/#abe63a79579b736d619338cc3cf570142">llvm::SelectionDAG::SelectNodeTo</a>, <a href="/web-llvm/docs/api/classes/llvm/selectiondag/#a96aac4c6bc44e654b8a0247851a5efb3">llvm::SelectionDAG::SelectNodeTo</a>, <a href="/web-llvm/docs/api/classes/llvm/selectiondag/#a675b86ff961a6fa31d278a5c9534ce77">llvm::SelectionDAG::SelectNodeTo</a>, <a href="/web-llvm/docs/api/classes/llvm/selectiondag/#a9717b632c48af5131b5fd75ee7fa5c5a">llvm::SelectionDAG::SelectNodeTo</a>, <a href="/web-llvm/docs/api/classes/llvm/selectiondag/#a14526009baf716f01b8907172efc2715">llvm::SelectionDAG::SelectNodeTo</a>, <a href="/web-llvm/docs/api/classes/llvm/selectiondag/#a87fc6eefa894bc885026b9b84a9affde">llvm::SelectionDAG::SelectNodeTo</a>, <a href="/web-llvm/docs/api/classes/llvm/selectiondag/#a9da92dd4ccdafc4a45a3db32136d71a3">llvm::SelectionDAG::SelectNodeTo</a>, <a href="/web-llvm/docs/api/classes/llvm/selectiondag/#af5081295124df43ca56ec3a663c69185">llvm::SelectionDAG::SelectNodeTo</a>, <a href="/web-llvm/docs/api/classes/llvm/selectiondag/#a0c7e962513cbe3c85da1e495ea9e610a">llvm::SelectionDAG::SelectNodeTo</a>, <a href="/web-llvm/docs/api/classes/llvm/ppctargetlowering/#ae058898e63ec72af7e4ed9b50ac8fbec">llvm::PPCTargetLowering::SelectOptimalAddrMode</a>, <a href="/web-llvm/docs/api/classes/llvm/hexagondagtodagisel/#ae31f69dd315950739471739473ebbbe8">llvm::HexagonDAGToDAGISel::SelectP2D</a>, <a href="/web-llvm/docs/api/classes/anonymous-ppciseldagtodag-cpp-/ppcdagtodagisel/#a694d03791f9cc383c2fedd9137107bfa">anonymous{PPCISelDAGToDAG.cpp}::PPCDAGToDAGISel::SelectPCRelForm</a>, <a href="/web-llvm/docs/api/classes/anonymous-ppciseldagtodag-cpp-/ppcdagtodagisel/#aa6fe251b071b9f3290732b4970df81e4">anonymous{PPCISelDAGToDAG.cpp}::PPCDAGToDAGISel::SelectPDForm</a>, <a href="/web-llvm/docs/api/classes/anonymous-aarch64iseldagtodag-cpp-/aarch64dagtodagisel/#a7076f4bbd65a6427f11dd14cce281ed4">anonymous{AArch64ISelDAGToDAG.cpp}::AArch64DAGToDAGISel::SelectPExtPair</a>, <a href="/web-llvm/docs/api/classes/anonymous-aarch64iseldagtodag-cpp-/aarch64dagtodagisel/#ac1346d28c3d5d259661f14ed8dc02423">anonymous{AArch64ISelDAGToDAG.cpp}::AArch64DAGToDAGISel::SelectPostLoad</a>, <a href="/web-llvm/docs/api/classes/anonymous-aarch64iseldagtodag-cpp-/aarch64dagtodagisel/#a87024e3cd8e787fed3e17063882847aa">anonymous{AArch64ISelDAGToDAG.cpp}::AArch64DAGToDAGISel::SelectPostLoadLane</a>, <a href="/web-llvm/docs/api/classes/anonymous-aarch64iseldagtodag-cpp-/aarch64dagtodagisel/#a7e3d9cf3f95460906ecb45fd30a3c6e5">anonymous{AArch64ISelDAGToDAG.cpp}::AArch64DAGToDAGISel::SelectPostStore</a>, <a href="/web-llvm/docs/api/classes/anonymous-aarch64iseldagtodag-cpp-/aarch64dagtodagisel/#af52e44fa59b89ae4c520c10a6de3eb4d">anonymous{AArch64ISelDAGToDAG.cpp}::AArch64DAGToDAGISel::SelectPostStoreLane</a>, <a href="/web-llvm/docs/api/classes/anonymous-aarch64iseldagtodag-cpp-/aarch64dagtodagisel/#a8f7ec1495df6db57a92060359b1ac27e">anonymous{AArch64ISelDAGToDAG.cpp}::AArch64DAGToDAGISel::SelectPredicatedLoad</a>, <a href="/web-llvm/docs/api/classes/anonymous-aarch64iseldagtodag-cpp-/aarch64dagtodagisel/#ac2acf10ff0cdf23bd749c57365aa12ab">anonymous{AArch64ISelDAGToDAG.cpp}::AArch64DAGToDAGISel::SelectPredicatedStore</a>, <a href="/web-llvm/docs/api/classes/anonymous-aarch64iseldagtodag-cpp-/aarch64dagtodagisel/#a2288bd65a234d48b37fa885946415134">anonymous{AArch64ISelDAGToDAG.cpp}::AArch64DAGToDAGISel::SelectPtrauthAuth</a>, <a href="/web-llvm/docs/api/classes/anonymous-aarch64iseldagtodag-cpp-/aarch64dagtodagisel/#a896c5ed9b541fda1cb6aeb021421d257">anonymous{AArch64ISelDAGToDAG.cpp}::AArch64DAGToDAGISel::SelectPtrauthResign</a>, <a href="/web-llvm/docs/api/classes/llvm/hexagondagtodagisel/#afdaa48e10d29db9073106c82c384184c">llvm::HexagonDAGToDAGISel::SelectQ2V</a>, <a href="/web-llvm/docs/api/classes/anonymous-aarch64iseldagtodag-cpp-/aarch64dagtodagisel/#a9709f09da4fb8d7326b23917d5c81922">anonymous{AArch64ISelDAGToDAG.cpp}::AArch64DAGToDAGISel::SelectRDVLImm</a>, <a href="/web-llvm/docs/api/classes/anonymous-armiseldagtodag-cpp-/armdagtodagisel/#ab301fda1e7e3cd7b76586ed7233df73a">anonymous{ARMISelDAGToDAG.cpp}::ARMDAGToDAGISel::SelectRegShifterOperand</a>, <a href="/web-llvm/docs/api/structs/llvm/hvxselector/#ab95e95f041d8724d5d33efc78a1f25cc">llvm::HvxSelector::selectRor</a>, <a href="/web-llvm/docs/api/classes/anonymous-aarch64iseldagtodag-cpp-/aarch64dagtodagisel/#a3156528a5f67da8543e7ef32f9218a79">anonymous{AArch64ISelDAGToDAG.cpp}::AArch64DAGToDAGISel::SelectRoundingVLShr</a>, <a href="/web-llvm/docs/api/classes/llvm/riscvdagtodagisel/#ab56dfbd0e6d276051f48a8aaca6162b5">llvm::RISCVDAGToDAGISel::selectRVVSimm5</a>, <a href="/web-llvm/docs/api/classes/llvm/riscvdagtodagisel/#a656b650a40d5acec00fc5a95ed5c71af">llvm::RISCVDAGToDAGISel::selectRVVSimm5</a>, <a href="/web-llvm/docs/api/classes/llvm/riscvdagtodagisel/#a8414362458bfc0acef16b0440665faa1">llvm::RISCVDAGToDAGISel::selectScalarFPAsInt</a>, <a href="/web-llvm/docs/api/classes/llvm/riscvdagtodagisel/#a007b16805afc4c07d06f494804c588a0">llvm::RISCVDAGToDAGISel::selectSETCC</a>, <a href="/web-llvm/docs/api/classes/llvm/riscvdagtodagisel/#a335dea545b19d321b4ef1e77fc1f77e7">llvm::RISCVDAGToDAGISel::selectSETEQ</a>, <a href="/web-llvm/docs/api/classes/llvm/riscvdagtodagisel/#a9399b0bae995e0f6e829909d253b252f">llvm::RISCVDAGToDAGISel::selectSETNE</a>, <a href="/web-llvm/docs/api/classes/llvm/riscvdagtodagisel/#a79ac751b1d22b0f304884dfabe120e05">llvm::RISCVDAGToDAGISel::selectSExtBits</a>, <a href="/web-llvm/docs/api/classes/llvm/riscvdagtodagisel/#a015f92412cbdc26fe3f1f398afb3575b">llvm::RISCVDAGToDAGISel::selectSExtBits</a>, <a href="/web-llvm/docs/api/classes/llvm/loongarchdagtodagisel/#a127155623f8b875235795782468030b1">llvm::LoongArchDAGToDAGISel::selectSExti32</a>, <a href="/web-llvm/docs/api/classes/anonymous-armiseldagtodag-cpp-/armdagtodagisel/#a3ce00bd4b67f193a67f5689b160e53a6">anonymous{ARMISelDAGToDAG.cpp}::ARMDAGToDAGISel::SelectShiftImmShifterOperand</a>, <a href="/web-llvm/docs/api/classes/anonymous-armiseldagtodag-cpp-/armdagtodagisel/#aa4fc3800778357b225faa099832a88a5">anonymous{ARMISelDAGToDAG.cpp}::ARMDAGToDAGISel::SelectShiftImmShifterOperandOneUse</a>, <a href="/web-llvm/docs/api/classes/llvm/loongarchdagtodagisel/#a36d1b77a885effd5cefdd787a7935226">llvm::LoongArchDAGToDAGISel::selectShiftMask</a>, <a href="/web-llvm/docs/api/classes/llvm/riscvdagtodagisel/#af619c526b5e90968d76fbd4fe4c861cb">llvm::RISCVDAGToDAGISel::selectShiftMask</a>, <a href="/web-llvm/docs/api/classes/llvm/loongarchdagtodagisel/#a0153badcd0031806e662355518d23af2">llvm::LoongArchDAGToDAGISel::selectShiftMask32</a>, <a href="/web-llvm/docs/api/classes/llvm/riscvdagtodagisel/#a9a218b6638506d322e84bf0e7a4fabff">llvm::RISCVDAGToDAGISel::selectShiftMask32</a>, <a href="/web-llvm/docs/api/classes/llvm/loongarchdagtodagisel/#a29f03ce7dcb2e8ffe60fa52b5be58dce">llvm::LoongArchDAGToDAGISel::selectShiftMaskGRLen</a>, <a href="/web-llvm/docs/api/classes/llvm/riscvdagtodagisel/#a1e9216876c10fd17e43217bab282a4d8">llvm::RISCVDAGToDAGISel::selectShiftMaskXLen</a>, <a href="/web-llvm/docs/api/classes/anonymous-armiseldagtodag-cpp-/armdagtodagisel/#ad004df90c18c0f44a698c8b8a0c3b14e">anonymous{ARMISelDAGToDAG.cpp}::ARMDAGToDAGISel::SelectShiftRegShifterOperand</a>, <a href="/web-llvm/docs/api/classes/llvm/hexagondagtodagisel/#a7cd9aa3bf030f7964c739b25a7b7965f">llvm::HexagonDAGToDAGISel::SelectSHL</a>, <a href="/web-llvm/docs/api/structs/llvm/hvxselector/#ae4d7d58593a9d0b5337f8089ee1946f6">llvm::HvxSelector::selectShuffle</a>, <a href="/web-llvm/docs/api/classes/llvm/riscvdagtodagisel/#a03a1b1ee1fea2b1c4911d4e5e6bb7a2a">llvm::RISCVDAGToDAGISel::selectSHXADD_UWOp</a>, <a href="/web-llvm/docs/api/classes/llvm/riscvdagtodagisel/#a06a0bdd0c07878ba4d61fa3b1b0453b1">llvm::RISCVDAGToDAGISel::selectSHXADD_UWOp</a>, <a href="/web-llvm/docs/api/classes/llvm/riscvdagtodagisel/#ae9ab615e80a0eef48a4c044b66d9c04f">llvm::RISCVDAGToDAGISel::selectSHXADDOp</a>, <a href="/web-llvm/docs/api/classes/llvm/riscvdagtodagisel/#af9a2bb077674a4de01b665b694b7f77f">llvm::RISCVDAGToDAGISel::selectSHXADDOp</a>, <a href="/web-llvm/docs/api/classes/llvm/riscvdagtodagisel/#a48c6bde78599716905a0196844dc5c9c">llvm::RISCVDAGToDAGISel::selectSimm5Shl2</a>, <a href="/web-llvm/docs/api/classes/anonymous-aarch64iseldagtodag-cpp-/aarch64dagtodagisel/#a243a149dc96c8921964eb0b85c84b2b2">anonymous{AArch64ISelDAGToDAG.cpp}::AArch64DAGToDAGISel::SelectSMETileSlice</a>, <a href="/web-llvm/docs/api/classes/anonymous-aarch64iseldagtodag-cpp-/aarch64dagtodagisel/#af03e0b9fbf705b2a8ecf9b5b44597ff9">anonymous{AArch64ISelDAGToDAG.cpp}::AArch64DAGToDAGISel::SelectStore</a>, <a href="/web-llvm/docs/api/classes/llvm/hexagondagtodagisel/#ad14724ea374cf56cc982c55eee97c03e">llvm::HexagonDAGToDAGISel::SelectStore</a>, <a href="/web-llvm/docs/api/classes/anonymous-aarch64iseldagtodag-cpp-/aarch64dagtodagisel/#a5984d3a5a8969d8d3238c4eaea8e4835">anonymous{AArch64ISelDAGToDAG.cpp}::AArch64DAGToDAGISel::SelectStoreLane</a>, <a href="/web-llvm/docs/api/classes/anonymous-cskyiseldagtodag-cpp-/cskydagtodagisel/#adc422f6987f0ad82fa646f7f9535fb0b">anonymous{CSKYISelDAGToDAG.cpp}::CSKYDAGToDAGISel::selectSubCarry</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/amdgpuisellowering-cpp/#a610f27b5e2b2ae6cd371310affe9c7ee">selectSupportsSourceMods</a>, <a href="/web-llvm/docs/api/classes/anonymous-aarch64iseldagtodag-cpp-/aarch64dagtodagisel/#a9b4ba75c51efd02dab989a4fedb73ea7">anonymous{AArch64ISelDAGToDAG.cpp}::AArch64DAGToDAGISel::SelectSVEAddSubImm</a>, <a href="/web-llvm/docs/api/classes/anonymous-aarch64iseldagtodag-cpp-/aarch64dagtodagisel/#abb640059b2c5052379eb16fbe0aae065">anonymous{AArch64ISelDAGToDAG.cpp}::AArch64DAGToDAGISel::SelectSVEAddSubSSatImm</a>, <a href="/web-llvm/docs/api/classes/anonymous-aarch64iseldagtodag-cpp-/aarch64dagtodagisel/#ace57b08063fdc70affb2a4989eb570e4">anonymous{AArch64ISelDAGToDAG.cpp}::AArch64DAGToDAGISel::SelectSVEArithImm</a>, <a href="/web-llvm/docs/api/classes/anonymous-aarch64iseldagtodag-cpp-/aarch64dagtodagisel/#a471c8c4cc2421f59c48dba47d82fade3">anonymous{AArch64ISelDAGToDAG.cpp}::AArch64DAGToDAGISel::SelectSVECpyDupImm</a>, <a href="/web-llvm/docs/api/classes/anonymous-aarch64iseldagtodag-cpp-/aarch64dagtodagisel/#a5d4e06054384d0c5ce3d87a3a9387136">anonymous{AArch64ISelDAGToDAG.cpp}::AArch64DAGToDAGISel::SelectSVELogicalImm</a>, <a href="/web-llvm/docs/api/classes/anonymous-aarch64iseldagtodag-cpp-/aarch64dagtodagisel/#af3f0eeb4d48eda09cd1566d2dfa46c19">anonymous{AArch64ISelDAGToDAG.cpp}::AArch64DAGToDAGISel::SelectSVERegRegAddrMode</a>, <a href="/web-llvm/docs/api/classes/anonymous-aarch64iseldagtodag-cpp-/aarch64dagtodagisel/#a2f591f8aab19cca49b1885c410abda8a">anonymous{AArch64ISelDAGToDAG.cpp}::AArch64DAGToDAGISel::SelectSVEShiftImm</a>, <a href="/web-llvm/docs/api/classes/anonymous-aarch64iseldagtodag-cpp-/aarch64dagtodagisel/#ab0ca85a9323ae8a5965a7c4d9e96a097">anonymous{AArch64ISelDAGToDAG.cpp}::AArch64DAGToDAGISel::SelectSVEShiftSplatImmR</a>, <a href="/web-llvm/docs/api/classes/anonymous-armiseldagtodag-cpp-/armdagtodagisel/#ad8af30e8308663f140b6e9c6f91bb063">anonymous{ARMISelDAGToDAG.cpp}::ARMDAGToDAGISel::SelectT2AddrModeExclusive</a>, <a href="/web-llvm/docs/api/classes/anonymous-armiseldagtodag-cpp-/armdagtodagisel/#a65e22140b3d39a410fa91e454513eb7e">anonymous{ARMISelDAGToDAG.cpp}::ARMDAGToDAGISel::SelectT2AddrModeImm12</a>, <a href="/web-llvm/docs/api/classes/anonymous-armiseldagtodag-cpp-/armdagtodagisel/#a4940db05905a9e557815bb2d99a5738f">anonymous{ARMISelDAGToDAG.cpp}::ARMDAGToDAGISel::SelectT2AddrModeImm7</a>, <a href="/web-llvm/docs/api/classes/anonymous-armiseldagtodag-cpp-/armdagtodagisel/#a3d5bdce97e969d809d962857d6f5af05">anonymous{ARMISelDAGToDAG.cpp}::ARMDAGToDAGISel::SelectT2AddrModeImm7Offset</a>, <a href="/web-llvm/docs/api/classes/anonymous-armiseldagtodag-cpp-/armdagtodagisel/#a9b71ec795bacb8b14faaed9a9e4ac5c3">anonymous{ARMISelDAGToDAG.cpp}::ARMDAGToDAGISel::SelectT2AddrModeImm7Offset</a>, <a href="/web-llvm/docs/api/classes/anonymous-armiseldagtodag-cpp-/armdagtodagisel/#a8262e2c96f6ed0ff7a0a907eb5663354">anonymous{ARMISelDAGToDAG.cpp}::ARMDAGToDAGISel::SelectT2AddrModeImm8</a>, <a href="/web-llvm/docs/api/classes/anonymous-armiseldagtodag-cpp-/armdagtodagisel/#a5d23fd57cf4c733f4a9d76ae11f00b4a">anonymous{ARMISelDAGToDAG.cpp}::ARMDAGToDAGISel::SelectT2AddrModeImm8Offset</a>, <a href="/web-llvm/docs/api/classes/anonymous-armiseldagtodag-cpp-/armdagtodagisel/#a727eda518f4ada7109bb391d66f576e9">anonymous{ARMISelDAGToDAG.cpp}::ARMDAGToDAGISel::SelectT2AddrModeSoReg</a>, <a href="/web-llvm/docs/api/classes/anonymous-aarch64iseldagtodag-cpp-/aarch64dagtodagisel/#a58e8e2324cf97c781f18868fba7a940f">anonymous{AArch64ISelDAGToDAG.cpp}::AArch64DAGToDAGISel::SelectTable</a>, <a href="/web-llvm/docs/api/classes/anonymous-armiseldagtodag-cpp-/armdagtodagisel/#adf95459d72259dcba7c222a194d09439">anonymous{ARMISelDAGToDAG.cpp}::ARMDAGToDAGISel::SelectTAddrModeImm7</a>, <a href="/web-llvm/docs/api/classes/anonymous-aarch64iseldagtodag-cpp-/aarch64dagtodagisel/#a0f95e2648f97b6e2446862a53d682888">anonymous{AArch64ISelDAGToDAG.cpp}::AArch64DAGToDAGISel::SelectTagP</a>, <a href="/web-llvm/docs/api/classes/anonymous-armiseldagtodag-cpp-/armdagtodagisel/#a67de03b6453d6cb0302cb42a21351422">anonymous{ARMISelDAGToDAG.cpp}::ARMDAGToDAGISel::SelectThumbAddrModeImm5S</a>, <a href="/web-llvm/docs/api/classes/anonymous-armiseldagtodag-cpp-/armdagtodagisel/#ae3e7c96a69728e825dce3cd81491edc0">anonymous{ARMISelDAGToDAG.cpp}::ARMDAGToDAGISel::SelectThumbAddrModeImm5S1</a>, <a href="/web-llvm/docs/api/classes/anonymous-armiseldagtodag-cpp-/armdagtodagisel/#a0d9cae290c29ebccc059dcf258454028">anonymous{ARMISelDAGToDAG.cpp}::ARMDAGToDAGISel::SelectThumbAddrModeImm5S2</a>, <a href="/web-llvm/docs/api/classes/anonymous-armiseldagtodag-cpp-/armdagtodagisel/#acb1cf0f839f283d5ac763183b0bd8a0a">anonymous{ARMISelDAGToDAG.cpp}::ARMDAGToDAGISel::SelectThumbAddrModeImm5S4</a>, <a href="/web-llvm/docs/api/classes/anonymous-armiseldagtodag-cpp-/armdagtodagisel/#a9a153a18768a8b602fbac7c74461fdce">anonymous{ARMISelDAGToDAG.cpp}::ARMDAGToDAGISel::SelectThumbAddrModeRR</a>, <a href="/web-llvm/docs/api/classes/anonymous-armiseldagtodag-cpp-/armdagtodagisel/#a72e1b557f03f315627084e2ab508adaa">anonymous{ARMISelDAGToDAG.cpp}::ARMDAGToDAGISel::SelectThumbAddrModeRRSext</a>, <a href="/web-llvm/docs/api/classes/anonymous-armiseldagtodag-cpp-/armdagtodagisel/#a01be2a14188ac612c910c9043ae037e1">anonymous{ARMISelDAGToDAG.cpp}::ARMDAGToDAGISel::SelectThumbAddrModeSP</a>, <a href="/web-llvm/docs/api/classes/llvm/hexagondagtodagisel/#ad8e39a32bed97c7dbaa8c3492eaf8079">llvm::HexagonDAGToDAGISel::SelectTypecast</a>, <a href="/web-llvm/docs/api/classes/anonymous-aarch64iseldagtodag-cpp-/aarch64dagtodagisel/#ad7efe7a9bae3f98d2d02310b6251bff0">anonymous{AArch64ISelDAGToDAG.cpp}::AArch64DAGToDAGISel::SelectUnaryMultiIntrinsic</a>, <a href="/web-llvm/docs/api/classes/llvm/hexagondagtodagisel/#a85a62a90a2a164b47c5b0612e13c22b8">llvm::HexagonDAGToDAGISel::SelectV2Q</a>, <a href="/web-llvm/docs/api/classes/llvm/hexagondagtodagisel/#ae6465931a42c451cc8fddc3fe53f9cc8">llvm::HexagonDAGToDAGISel::SelectV65Gather</a>, <a href="/web-llvm/docs/api/classes/llvm/hexagondagtodagisel/#a78560af0126401264a657db5634eec1f">llvm::HexagonDAGToDAGISel::SelectV65GatherPred</a>, <a href="/web-llvm/docs/api/classes/llvm/hexagondagtodagisel/#a6ca89fb4224ec252152730e1e57082e7">llvm::HexagonDAGToDAGISel::SelectVAlign</a>, <a href="/web-llvm/docs/api/structs/llvm/hvxselector/#aac090ca034780a9ec924da0729508a2c">llvm::HvxSelector::selectVAlign</a>, <a href="/web-llvm/docs/api/classes/llvm/hexagondagtodagisel/#adf57ec2211ca1bdc56dce8afdaa4b226">llvm::HexagonDAGToDAGISel::SelectVAlignAddr</a>, <a href="/web-llvm/docs/api/classes/llvm/amdgpudagtodagisel/#a7003b5e44eb73177e8c26b4a91247e57">llvm::AMDGPUDAGToDAGISel::SelectVectorShuffle</a>, <a href="/web-llvm/docs/api/classes/llvm/riscvdagtodagisel/#a9dd913520cec32052ff63c8735efad5c">llvm::RISCVDAGToDAGISel::selectVLOp</a>, <a href="/web-llvm/docs/api/classes/llvm/loongarchdagtodagisel/#a7dc08a83d2a2915b58f68316275fead0">llvm::LoongArchDAGToDAGISel::selectVSplat</a>, <a href="/web-llvm/docs/api/classes/llvm/riscvdagtodagisel/#a81db6a638b456bb26ffa634a27e52798">llvm::RISCVDAGToDAGISel::selectVSplat</a>, <a href="/web-llvm/docs/api/classes/llvm/loongarchdagtodagisel/#a90b0a83c31e7aff7acf50c716ef3e28e">llvm::LoongArchDAGToDAGISel::selectVSplatImm</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/riscv/riscviseldagtodag-cpp/#ae4864665b5082511864fa8b4ad9ea5f9">selectVSplatImmHelper</a>, <a href="/web-llvm/docs/api/classes/llvm/riscvdagtodagisel/#a60c150f4b46cf5dc8dd1af9653ddde43">llvm::RISCVDAGToDAGISel::selectVSplatSimm5</a>, <a href="/web-llvm/docs/api/classes/llvm/riscvdagtodagisel/#ab1135c7a8ff766bc0ec72c55e1049d87">llvm::RISCVDAGToDAGISel::selectVSplatSimm5Plus1</a>, <a href="/web-llvm/docs/api/classes/llvm/riscvdagtodagisel/#abfe913dce113bf8f5d20f5e1fe1966b2">llvm::RISCVDAGToDAGISel::selectVSplatSimm5Plus1NonZero</a>, <a href="/web-llvm/docs/api/classes/llvm/riscvdagtodagisel/#aff942d6f8939b769939917efd741bde5">llvm::RISCVDAGToDAGISel::selectVSplatUimm</a>, <a href="/web-llvm/docs/api/classes/llvm/riscvdagtodagisel/#a0fe3090ddbfdb18ba09417cd06334349">llvm::RISCVDAGToDAGISel::selectVSplatUimmBits</a>, <a href="/web-llvm/docs/api/classes/llvm/loongarchdagtodagisel/#ac8a9940ba807ee771ad949f2ab9e8bea">llvm::LoongArchDAGToDAGISel::selectVSplatUimmInvPow2</a>, <a href="/web-llvm/docs/api/classes/llvm/loongarchdagtodagisel/#a1a4e02c3247bc8b4134b91e707d6c146">llvm::LoongArchDAGToDAGISel::selectVSplatUimmPow2</a>, <a href="/web-llvm/docs/api/classes/anonymous-aarch64iseldagtodag-cpp-/aarch64dagtodagisel/#ac46ff75f3965f515cfddd8256d090fb8">anonymous{AArch64ISelDAGToDAG.cpp}::AArch64DAGToDAGISel::SelectWhilePair</a>, <a href="/web-llvm/docs/api/classes/anonymous-ppciseldagtodag-cpp-/ppcdagtodagisel/#a6fba61fdfae4868d150378d9f41020bc">anonymous{PPCISelDAGToDAG.cpp}::PPCDAGToDAGISel::SelectXForm</a>, <a href="/web-llvm/docs/api/classes/llvm/riscvdagtodagisel/#af01870e7e19b1220afa10a19f526c533">llvm::RISCVDAGToDAGISel::selectZExtBits</a>, <a href="/web-llvm/docs/api/classes/llvm/riscvdagtodagisel/#a05b5cba8cfdcec8f2d1dafb06fb63ab5">llvm::RISCVDAGToDAGISel::selectZExtBits</a>, <a href="/web-llvm/docs/api/classes/llvm/loongarchdagtodagisel/#a42ae88f3d9dbf2cd35c379cba4ef976f">llvm::LoongArchDAGToDAGISel::selectZExti32</a>, <a href="/web-llvm/docs/api/namespaces/llvm/memprof/#ad9f19a23fe474c0f4c53ac30f57b65d6">llvm::memprof::serializedSizeV2</a>, <a href="/web-llvm/docs/api/namespaces/llvm/memprof/#a82e6f658f2a17b60f5b9cdeca4904618">llvm::memprof::serializedSizeV3</a>, <a href="/web-llvm/docs/api/namespaces/llvm/memprof/#abf906f72a8e8c44574d1cfcfd020701f">llvm::memprof::serializeV2</a>, <a href="/web-llvm/docs/api/namespaces/llvm/memprof/#a2e8afc6631c5a017ffef151a9d1fe7f6">llvm::memprof::serializeV3</a>, <a href="/web-llvm/docs/api/classes/llvm/pointersumtype/#afcdc4cc69c3a0786b2f1ec76cecab61d">llvm::PointerSumType&lt; TagT, MemberTs... &gt;::set</a>, <a href="/web-llvm/docs/api/classes/llvm/smallvectorbase/#a435b1238f81c19cd3bd557fe9af58ed9">llvm::SmallVectorBase&lt; SmallVectorSizeType&lt; T &gt; &gt;::set_allocation_range</a>, <a href="/web-llvm/docs/api/classes/llvm/smallvectorbase/#acf1bb6ad9c13f32082c4e3b1272522fd">llvm::SmallVectorBase&lt; SmallVectorSizeType&lt; T &gt; &gt;::set_size</a>, <a href="/web-llvm/docs/api/classes/llvm/instruction/#a4dd9b6c5bb93e01393c47dbe60f8b23f">llvm::Instruction::setAAMetadata</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/powerpc/ppcisellowering-cpp/#a310a2b4f7197b620ecb3babef5637cc2">setAlignFlagsForFI</a>, <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/utils/simplifycfg-cpp/#a939fe4165e88bc40fb5831d3d7a42976">setBranchWeights</a>, <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/utils/simplifycfg-cpp/#a4c6e9504894d5f9468c5f151bdc75de2">setBranchWeights</a>, <a href="/web-llvm/docs/api/classes/llvm/mcencodedfragment/#a74ca9081add78d66b5c6ebfe0f3d2b28">llvm::MCEncodedFragment::setBundlePadding</a>, <a href="/web-llvm/docs/api/classes/llvm/machinebasicblock/#a4472755d36621c5e2d056eec5056202e">llvm::MachineBasicBlock::setCallFrameSize</a>, <a href="/web-llvm/docs/api/structs/anonymous-memprofcontextdisambiguation-cpp-/callsitecontextgraph/callinfo/#a2804f29c7c74811f26da7326fc142fc6">anonymous{MemProfContextDisambiguation.cpp}::CallsiteContextGraph&lt; DerivedCCG, FuncTy, CallTy &gt;::CallInfo::setCloneNo</a>, <a href="/web-llvm/docs/api/classes/llvm/yaml/input/#ab0fe8d0bc6e86529501a7ff2867fa1a7">llvm::yaml::Input::setCurrentDocument</a>, <a href="/web-llvm/docs/api/classes/anonymous-standardinstrumentations-cpp-/dotcfgdiffdisplaygraph/#a59db9f0a5bbc2cf0d4187f5f50d97b7f">anonymous{StandardInstrumentations.cpp}::DotCfgDiffDisplayGraph::setEntryNode</a>, <a href="/web-llvm/docs/api/classes/llvm/selectiondag/#a719417d1fdf9f37a0a59f62bf41e4730">llvm::SelectionDAG::setGraphAttrs</a>, <a href="/web-llvm/docs/api/classes/llvm/selectiondag/#a7e797c893fc956bc08a62c825e3fd728">llvm::SelectionDAG::setGraphColor</a>, <a href="/web-llvm/docs/api/classes/llvm/amdgpulibfunc/#a80ac8e418033d6c4c44e67625c073740">llvm::AMDGPULibFunc::setName</a>, <a href="/web-llvm/docs/api/classes/llvm/amdgpulibfuncimpl/#ad783e6edf33f340d74a7b8ecde825ee6">llvm::AMDGPULibFuncImpl::setName</a>, <a href="/web-llvm/docs/api/classes/llvm/machinepassregistrynode/#a6ae0fbb1c2f2da1b38ebde04acee8a7a">llvm::MachinePassRegistryNode&lt; PassCtorTy &gt;::setNext</a>, <a href="/web-llvm/docs/api/structs/llvm/rdf/nodebase/#a893d5a6711a796416c81214a3508ccd4">llvm::rdf::NodeBase::setNext</a>, <a href="/web-llvm/docs/api/classes/llvm/foldingsetbase/node/#a5e89537cd2bf241c821568a8790cba6a">llvm::FoldingSetBase::Node::SetNextInBucket</a>, <a href="/web-llvm/docs/api/classes/llvm/sdvalue/#ad575e4867727668f7d50952bc9e1a1cd">llvm::SDValue::setNode</a>, <a href="/web-llvm/docs/api/classes/llvm/sunit/#a1e76b6a72bd49c97aaf9fe170fb829bd">llvm::SUnit::setNode</a>, <a href="/web-llvm/docs/api/classes/llvm/selectiondag/#a66ebc3ec1c8816b16a5f239a8631c780">llvm::SelectionDAG::setNodeMemRefs</a>, <a href="/web-llvm/docs/api/classes/llvm/dieabbrev/#ac8ed225191cf81190ec6ffd5325594b5">llvm::DIEAbbrev::setNumber</a>, <a href="/web-llvm/docs/api/classes/llvm/machinebasicblock/#a87d6a6ddceb28f49cb7c34727c989c0a">llvm::MachineBasicBlock::setNumber</a>, <a href="/web-llvm/docs/api/classes/llvm/valuelatticeelement/#a64a82dcbacd27ff1996040ad31c9f36e">llvm::ValueLatticeElement::setNumRangeExtensions</a>, <a href="/web-llvm/docs/api/classes/llvm/mdnode/#a9db501ee1cf923b2031b1b924802fe55">llvm::MDNode::setNumUnresolved</a>, <a href="/web-llvm/docs/api/classes/llvm/gvnexpression/basicexpression/#a9fb5d54567277c2e3092a9c137b7bceb">llvm::GVNExpression::BasicExpression::setOperand</a>, <a href="/web-llvm/docs/api/classes/llvm/amdgpupalmetadata/#a44fe092bd112e2eb16c1cba213922aca">llvm::AMDGPUPALMetadata::setRegister</a>, <a href="/web-llvm/docs/api/classes/llvm/amdgpupalmetadata/#a97fc9eaaed21f58ee95b42903afabb90">llvm::AMDGPUPALMetadata::setRegister</a>, <a href="/web-llvm/docs/api/classes/llvm/selectiondag/#ae0fc3f54d06d2230bf93a19d45f51706">llvm::SelectionDAG::setRoot</a>, <a href="/web-llvm/docs/api/classes/llvm/selectiondag/#af1cb2dd492ddb445e5640e20d6815f58">llvm::SelectionDAG::setSubgraphColor</a>, <a href="/web-llvm/docs/api/classes/llvm/dgedge/#adcd9ba052310baee6e5b510bbadd5d74">llvm::DGEdge&lt; DDGNode, DDGEdge &gt;::setTargetNode</a>, <a href="/web-llvm/docs/api/files/lib/lib/codegen/machinefunction-cpp/#adfbf235872b70098310f84ace07f312a">setUnsafeStackSize</a>, <a href="/web-llvm/docs/api/classes/llvm/selectiondagbuilder/#a6b0040c5b706355fa56842358cf0cbe7">llvm::SelectionDAGBuilder::setUnusedArgValue</a>, <a href="/web-llvm/docs/api/classes/llvm/selectiondagbuilder/#ad8368fe85feec440623e9558e100f357">llvm::SelectionDAGBuilder::setValue</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/powerpc/ppcisellowering-cpp/#a853a1693caf74a6f250655800e136595">setXFormForUnalignedFI</a>, <a href="/web-llvm/docs/api/classes/anonymous-amdgputargetmachine-cpp-/sgprregisterregalloc/#a07e656a35435620beb11890a6c061e6d">anonymous{AMDGPUTargetMachine.cpp}::SGPRRegisterRegAlloc::SGPRRegisterRegAlloc</a>, <a href="/web-llvm/docs/api/files/lib/lib/analysis/blockfrequencyinfoimpl-cpp/#af7b0ebc6a85830e67121d86801e54d8f">shiftRightAndRound</a>, <a href="/web-llvm/docs/api/files/lib/lib/codegen/lib/codegen/selectiondag/dagcombiner-cpp/#ac6c9b791cef5925e123539fb2934316b">shouldCombineToPostInc</a>, <a href="/web-llvm/docs/api/classes/llvm/sitargetlowering/#a8272c4da36b8d295addf73f56c548155">llvm::SITargetLowering::shouldExpandVectorDynExt</a>, <a href="/web-llvm/docs/api/classes/llvm/aarch64targetlowering/#acefcea723a8cd3136dae2d39a8dd7ca9">llvm::AArch64TargetLowering::shouldFoldConstantShiftPairToMask</a>, <a href="/web-llvm/docs/api/classes/llvm/armtargetlowering/#a58c6bec36cfce34f95d92841b1d5ef9f">llvm::ARMTargetLowering::shouldFoldConstantShiftPairToMask</a>, <a href="/web-llvm/docs/api/classes/llvm/mipstargetlowering/#aa3cf604f0da074af7ca64f80e5d753ea">llvm::MipsTargetLowering::shouldFoldConstantShiftPairToMask</a>, <a href="/web-llvm/docs/api/classes/llvm/targetloweringbase/#a6ea263078f271d4d5e25764ef77d2878">llvm::TargetLoweringBase::shouldFoldConstantShiftPairToMask</a>, <a href="/web-llvm/docs/api/classes/llvm/x86targetlowering/#a85fb0d7e000c96b972014b0405aa9c88">llvm::X86TargetLowering::shouldFoldConstantShiftPairToMask</a>, <a href="/web-llvm/docs/api/classes/llvm/amdgputargetlowering/#ae13cfbd2de579359b370b4b7971e3ca1">llvm::AMDGPUTargetLowering::shouldFoldFNegIntoSrc</a>, <a href="/web-llvm/docs/api/classes/llvm/amdgputargetlowering/#a9131ae18383241b54e466cf623a7312b">llvm::AMDGPUTargetLowering::shouldReduceLoadWidth</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/arm/armiseldagtodag-cpp/#ae8e4f1811ba84f2b03bd44a549868127">shouldUseZeroOffsetLdSt</a>, <a href="/web-llvm/docs/api/classes/anonymous-metadataloader-cpp-/bitcodereadermetadatalist/#acc739dbfdc649bee0330488d1e42a3f5">anonymous{MetadataLoader.cpp}::BitcodeReaderMetadataList::shrinkTo</a>, <a href="/web-llvm/docs/api/classes/llvm/bitcodereadervaluelist/#ac5467d51cfd26f6bfc693125affb3ee1">llvm::BitcodeReaderValueList::shrinkTo</a>, <a href="/web-llvm/docs/api/classes/metadataloader/metadataloaderimpl/#a3ae39a61410ac4b8fa5f7714c9e1c102">llvm::MetadataLoader::MetadataLoaderImpl::shrinkTo</a>, <a href="/web-llvm/docs/api/classes/llvm/metadataloader/#a88ddd0875b67b0b3af1dd5da677d3ae4">llvm::MetadataLoader::shrinkTo</a>, <a href="/web-llvm/docs/api/classes/llvm/simpleddgnode/#a7cfe9acbc61e3fb6ed06efaf77ab02f5">llvm::SimpleDDGNode::SimpleDDGNode</a>, <a href="/web-llvm/docs/api/classes/llvm/simpleddgnode/#a6d07b91e9c9cf1265790ca3d94682f9f">llvm::SimpleDDGNode::SimpleDDGNode</a>, <a href="/web-llvm/docs/api/classes/llvm/simpleddgnode/#a14413e4111fa6738de29e2a7e1d8111b">llvm::SimpleDDGNode::SimpleDDGNode</a>, <a href="/web-llvm/docs/api/classes/llvm/simpleregistryentry/#a25f610c8dca629b40948f9c13adea575">llvm::SimpleRegistryEntry&lt; T &gt;::SimpleRegistryEntry</a>, <a href="/web-llvm/docs/api/classes/llvm/abstractdependencegraphbuilder/#aa58986a6df89ded5c86fc981ad2bf53c">llvm::AbstractDependenceGraphBuilder&lt; GraphType &gt;::simplify</a>, <a href="/web-llvm/docs/api/files/lib/lib/codegen/lib/codegen/selectiondag/dagcombiner-cpp/#a0cd03e62d1193e7b7e6562270356fdbb">simplifyDivRem</a>, <a href="/web-llvm/docs/api/classes/anonymous-simplifyindvar-cpp-/simplifyindvar/#a9a4e22418fd040f349bdecefdc303c2e">anonymous{SimplifyIndVar.cpp}::SimplifyIndvar::simplifyIVRemainder</a>, <a href="/web-llvm/docs/api/files/lib/lib/analysis/instructionsimplify-cpp/#a845e93029e92776841aaf5e0ec4c812f">simplifyOrInst</a>, <a href="/web-llvm/docs/api/classes/llvm/instcombinerimpl/#ad36c0bc30660bad4f2b79be90608ea60">llvm::InstCombinerImpl::SimplifySelectsFeedingBinaryOp</a>, <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/coroutines/corosplit-cpp/#a76d02f8354cb0d3c8b30eb7812ae01b2">simplifySuspendPoints</a>, <a href="/web-llvm/docs/api/classes/anonymous-simplifyindvar-cpp-/simplifyindvar/#a1ba99155749ea6a41858f9bc4449f543">anonymous{SimplifyIndVar.cpp}::SimplifyIndvar::simplifyUsers</a>, <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/scalar/loopsink-cpp/#a89374dd34ed723e45309afa9ac10eb83">sinkInstruction</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#ad30fb60072e2996200ea591628e33c5a">llvm::sinkRegion</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#af1236d17bc9dd1041e95f1724eb9cfa6">llvm::sinkRegionForLoopNest</a>, <a href="/web-llvm/docs/api/classes/llvm/outlinedhashtree/#abfea475152d214caa9b72bad101d75a0">llvm::OutlinedHashTree::size</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64isellowering-cpp/#ac5670c01bc722932c40b06aaab52a0df">skipExtensionForVectorMULL</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/arm/armisellowering-cpp/#a8556cfd59caa7077d224c55f2b1d9767">SkipExtensionForVMULL</a>, <a href="/web-llvm/docs/api/classes/llvm/arrayref/#a5c498de3bb758473707e9198311eb15f">llvm::ArrayRef&lt; llvm::cfg::Update&lt; MachineBasicBlock * &gt; &gt;::slice</a>, <a href="/web-llvm/docs/api/classes/llvm/arrayref/#aebf6ca7590d4f766b894044015a0fa31">llvm::ArrayRef&lt; llvm::cfg::Update&lt; MachineBasicBlock * &gt; &gt;::slice</a>, <a href="/web-llvm/docs/api/classes/llvm/mutablearrayref/#a526a7f286fa3dbf805ff61fbb35d84f7">llvm::MutableArrayRef&lt; uint8_t &gt;::slice</a>, <a href="/web-llvm/docs/api/classes/llvm/mutablearrayref/#ae671f7b11f895cb673f6ee9a3c694359">llvm::MutableArrayRef&lt; uint8_t &gt;::slice</a>, <a href="/web-llvm/docs/api/classes/llvm/smallvector/#a3c60758d71502ce394548f12077937ea">llvm::SmallVector&lt; BitWord &gt;::SmallVector</a>, <a href="/web-llvm/docs/api/classes/llvm/smallvector/#a2990838a54ecba14e6fc14281cca74d4">llvm::SmallVector&lt; BitWord &gt;::SmallVector</a>, <a href="/web-llvm/docs/api/classes/llvm/smallvector/#a6e4373e43164f1022d8b63a149f5ae5a">llvm::SmallVector&lt; BitWord &gt;::SmallVector</a>, <a href="/web-llvm/docs/api/classes/llvm/smallvector/#ad6efd90352524e7e107660f603748541">llvm::SmallVector&lt; BitWord &gt;::SmallVector</a>, <a href="/web-llvm/docs/api/classes/llvm/smallvector/#a860e6818f39bad2f5c26789cbe082daf">llvm::SmallVector&lt; BitWord &gt;::SmallVector</a>, <a href="/web-llvm/docs/api/classes/llvm/smallvector/#a1fb4cd0888232f1bfa93a543f9d8debd">llvm::SmallVector&lt; BitWord &gt;::SmallVector</a>, <a href="/web-llvm/docs/api/classes/llvm/smallvector/#a5826a010dbe5f46d2b134280d70ba406">llvm::SmallVector&lt; BitWord &gt;::SmallVector</a>, <a href="/web-llvm/docs/api/classes/llvm/smallvector/#aae7c6a5e0e3285061bfffa2e62584cab">llvm::SmallVector&lt; BitWord &gt;::SmallVector</a>, <a href="/web-llvm/docs/api/classes/llvm/smallvector/#a1e8fd80f33dcbb05f607aacbeb971d3b">llvm::SmallVector&lt; BitWord &gt;::SmallVector</a>, <a href="/web-llvm/docs/api/classes/llvm/smallvector/#a12defc013235be8903e1c22c9885a2ce">llvm::SmallVector&lt; BitWord &gt;::SmallVector</a>, <a href="/web-llvm/docs/api/classes/llvm/smallvectorimpl/#abd001dbc8a624eecaa020c6d4e3a6b06">llvm::const_iterator&lt; MemoryLocation &gt;::SmallVectorImpl</a>, <a href="/web-llvm/docs/api/namespaces/llvm/switchcg/#a770339f0c1b1f2c1328c48f1f4291dfa">llvm::SwitchCG::sortAndRangeify</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/webassembly/webassemblycfgsort-cpp/#ab52c873c8169af2a8b1256ace3fe7a7c">sortBlocks</a>, <a href="/web-llvm/docs/api/classes/llvm/abstractdependencegraphbuilder/#a2ca7af382aa1a34576aee355f364447c">llvm::AbstractDependenceGraphBuilder&lt; GraphType &gt;::sortNodesTopologically</a>, <a href="/web-llvm/docs/api/classes/llvm/iplist-impl/#aaccd9ef4bc06e4cc097ddb02e271798c">llvm::iplist_impl&lt; IntrusiveListT, TraitsT &gt;::splice</a>, <a href="/web-llvm/docs/api/classes/llvm/iplist-impl/#a1ce5b7538f71b9afbe41c85ef10cf36b">llvm::iplist_impl&lt; IntrusiveListT, TraitsT &gt;::splice</a>, <a href="/web-llvm/docs/api/namespaces/llvm/anonymous-amdgpusplitmodule-cpp-/#a0706966ac4f391854346bebfcda816fa">llvm::anonymous{AMDGPUSplitModule.cpp}::splitAMDGPUModule</a>, <a href="/web-llvm/docs/api/classes/llvm/selectiondag/#aac3337c401bb0145fbecced8d947cebf">llvm::SelectionDAG::SplitEVL</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a61553b705fc9be3d8d0a18a8af1bc152">llvm::SplitModule</a>, <a href="/web-llvm/docs/api/classes/llvm/selectiondag/#af587fdddecfd87186f09f4b1e9b4bc0a">llvm::SelectionDAG::SplitScalar</a>, <a href="/web-llvm/docs/api/classes/llvm/scalednumberbase/#afe42176d3878695a8d7991af3439783f">llvm::ScaledNumberBase::splitSigned</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64isellowering-cpp/#a0bbdb7f279f14b5f7ff6d7d9a2a97765">splitStores</a>, <a href="/web-llvm/docs/api/classes/llvm/selectiondag/#a7bf00c0cb45566170582cde2ecfe8809">llvm::SelectionDAG::SplitVector</a>, <a href="/web-llvm/docs/api/classes/llvm/selectiondag/#a8695950995820e5f6c0407c68f91f44f">llvm::SelectionDAG::SplitVector</a>, <a href="/web-llvm/docs/api/classes/llvm/amdgputargetlowering/#a95e6431ff6ad6b548c061a19df107850">llvm::AMDGPUTargetLowering::splitVector</a>, <a href="/web-llvm/docs/api/classes/llvm/selectiondag/#a483aff639a45188ff0f10ae1ae79da16">llvm::SelectionDAG::SplitVectorOperand</a>, <a href="/web-llvm/docs/api/classes/llvm/sampleprof/sampleprofilewriterbinary/#a3a9843c8238bc35707b209597d873d9b">llvm::sampleprof::SampleProfileWriterBinary::stablizeNameTable</a>, <a href="/web-llvm/docs/api/classes/stacknode/#ab9f6783b46a354a0dae1dd48f5da8f57">StackNode::StackNode</a>, <a href="/web-llvm/docs/api/structs/llvm/rdf/dataflowgraph/defstack/#a4dcc82a602fb346bfffbca9196d6ec40">llvm::rdf::DataFlowGraph::DefStack::start_block</a>, <a href="/web-llvm/docs/api/files/lib/lib/binaryformat/magic-cpp/#a3c4dfe70f4dcd8100bfb9a037b95a664">startswith</a>, <a href="/web-llvm/docs/api/classes/llvm/callgraphnode/#a8b15d9387cea0c9f55fdc8a0f864f28d">llvm::CallGraphNode::stealCalledFunctionsFrom</a>, <a href="/web-llvm/docs/api/classes/llvm/mdnode/#a20d3b0b5da786f4ad0747424704116bb">llvm::MDNode::storeImpl</a>, <a href="/web-llvm/docs/api/classes/llvm/mdnode/#ad0c6e5f8501b6685c39f35bd56cf0fd2">llvm::MDNode::storeImpl</a>, <a href="/web-llvm/docs/api/classes/llvm/stringliteral/#ac2c1c99d5682bb22faf4d85ce7b5f4bb">llvm::StringLiteral::StringLiteral</a>, <a href="/web-llvm/docs/api/classes/llvm/stringtable/#ae5ab7503eda2c197884a390d06969dc7">llvm::StringTable::StringTable</a>, <a href="/web-llvm/docs/api/files/lib/lib/ir/debuginfo-cpp/#a417bd37b1f7e5061fd57036f3160b288">stripDebugLocFromLoopID</a>, <a href="/web-llvm/docs/api/files/lib/lib/ir/debuginfo-cpp/#a1a063e0f7f97a2cf494f8fff2e566bde">stripLoopMDLoc</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/powerpc/ppcisellowering-cpp/#a6f0cac8b7a7acd364d34649335444ceb">stripModuloOnShift</a>, <a href="/web-llvm/docs/api/classes/llvm/smallstring/#abab69c8e9372f6a5283db4a059b8d5a0">llvm::SmallString&lt; 0 &gt;::substr</a>, <a href="/web-llvm/docs/api/classes/llvm/stringref/#a25f1fd81f2132805676c82ab8ae0c109">llvm::StringRef::substr</a>, <a href="/web-llvm/docs/api/classes/llvm/resourcepriorityqueue/#ae3f9d679010b93efcba0721c8714d029">llvm::ResourcePriorityQueue::SUSchedulingCost</a>, <a href="/web-llvm/docs/api/classes/llvm/suspendcrossinginfo/#a602f4157bb9c3e355a0a9377f828a56f">llvm::SuspendCrossingInfo::SuspendCrossingInfo</a>, <a href="/web-llvm/docs/api/files/lib/lib/codegen/lib/codegen/globalisel/legalizerhelper-cpp/#a7d7927ce19d14acc525d683585b8c58d">SwapN</a>, <a href="/web-llvm/docs/api/classes/llvm/lazycallgraph/refscc/#a2957918db7f91f405b11d92c1ebf3b0f">llvm::LazyCallGraph::RefSCC::switchInternalEdgeToCall</a>, <a href="/web-llvm/docs/api/classes/llvm/lazycallgraph/refscc/#a96fe0cb15ded58bd1824fa4e3daec680">llvm::LazyCallGraph::RefSCC::switchInternalEdgeToRef</a>, <a href="/web-llvm/docs/api/structs/llvm/sysalias/#a3699e92eee32aa54d064eb06b4ff631b">llvm::SysAlias::SysAlias</a>, <a href="/web-llvm/docs/api/structs/llvm/sysalias/#abd4a9400444e33762ce714ab21f762ef">llvm::SysAlias::SysAlias</a>, <a href="/web-llvm/docs/api/structs/llvm/sysaliasimm/#a93c175f97bc50811a075325079d396fd">llvm::SysAliasImm::SysAliasImm</a>, <a href="/web-llvm/docs/api/structs/llvm/sysaliasimm/#ab5bbd19123d6cb56b0fff53830fb524e">llvm::SysAliasImm::SysAliasImm</a>, <a href="/web-llvm/docs/api/structs/llvm/sysaliasreg/#a748fe9190a92c17f21936bdeb298980e">llvm::SysAliasReg::SysAliasReg</a>, <a href="/web-llvm/docs/api/structs/llvm/sysaliasreg/#a322ef362df05d163b9d4cc83f14db885">llvm::SysAliasReg::SysAliasReg</a>, <a href="/web-llvm/docs/api/classes/llvm/arrayref/#ac1f72f67a93986bb68c8b7f8a2dba4ba">llvm::ArrayRef&lt; llvm::cfg::Update&lt; MachineBasicBlock * &gt; &gt;::take_back</a>, <a href="/web-llvm/docs/api/classes/llvm/mutablearrayref/#a2efcc9f83bc3a5da3fbfc9feb047a7a0">llvm::MutableArrayRef&lt; uint8_t &gt;::take_back</a>, <a href="/web-llvm/docs/api/classes/llvm/stringref/#a9fe565cb0cc832480a9a9ed312dc2962">llvm::StringRef::take_back</a>, <a href="/web-llvm/docs/api/classes/llvm/arrayref/#a33da2ddf6f447892591c86d9d3771b9c">llvm::ArrayRef&lt; llvm::cfg::Update&lt; MachineBasicBlock * &gt; &gt;::take_front</a>, <a href="/web-llvm/docs/api/classes/llvm/mutablearrayref/#af7f90a0fd93435c0e075d55928d4320d">llvm::MutableArrayRef&lt; uint8_t &gt;::take_front</a>, <a href="/web-llvm/docs/api/classes/llvm/stringref/#aa28286a33491b5d9a936fb6ae853baee">llvm::StringRef::take_front</a>, <a href="/web-llvm/docs/api/classes/anonymous-typebasedaliasanalysis-cpp-/tbaanodeimpl/#ad027cb3b15346a1326eb4757456109fb">anonymous{TypeBasedAliasAnalysis.cpp}::TBAANodeImpl&lt; const MDNode &gt;::TBAANodeImpl</a>, <a href="/web-llvm/docs/api/classes/anonymous-typebasedaliasanalysis-cpp-/tbaastructtagnodeimpl/#a4aa0f92fa5df956ebd73ddafe0493e3d">anonymous{TypeBasedAliasAnalysis.cpp}::TBAAStructTagNodeImpl&lt; const MDNode &gt;::TBAAStructTagNodeImpl</a>, <a href="/web-llvm/docs/api/classes/anonymous-typebasedaliasanalysis-cpp-/tbaastructtypenode/#aa41708c0a83517ff2a334ee57ce26548">anonymous{TypeBasedAliasAnalysis.cpp}::TBAAStructTypeNode::TBAAStructTypeNode</a>, <a href="/web-llvm/docs/api/classes/llvm/coverage/mcdcrecord/testvector/#aaef697dad18728965b52f653af843e94">llvm::coverage::MCDCRecord::TestVector::TestVector</a>, <a href="/web-llvm/docs/api/structs/llvm/timetraceprofilerentry/#a1cac605ae10bf41e0287bf9092d5b737">llvm::TimeTraceProfilerEntry::TimeTraceProfilerEntry</a>, <a href="/web-llvm/docs/api/structs/llvm/timetraceprofilerentry/#a6edb393ad901a281393d41f46d6c9524">llvm::TimeTraceProfilerEntry::TimeTraceProfilerEntry</a>, <a href="/web-llvm/docs/api/classes/llvm/scalednumber/#aea1e398259be5674d18693b4892ae175">llvm::ScaledNumber&lt; DigitsT &gt;::toInt</a>, <a href="/web-llvm/docs/api/classes/llvm/intrusivebacklist/#aa9fb33f20236d43d3cf22244cc308e26">llvm::IntrusiveBackList&lt; Node &gt;::toIterator</a>, <a href="/web-llvm/docs/api/classes/llvm/intrusivebacklist/#addd2ed310d97112e926e9ec53feeb50d">llvm::IntrusiveBackList&lt; Node &gt;::toIterator</a>, <a href="/web-llvm/docs/api/classes/llvm/apint/#aff8bfdb27a0027b84b0c3580c0d9f530">llvm::APInt::toString</a>, <a href="/web-llvm/docs/api/classes/anonymous-itaniummanglingcanonicalizer-cpp-/canonicalizerallocator/#a0482fac5586994fcaf14eababdff45db">anonymous{ItaniumManglingCanonicalizer.cpp}::CanonicalizerAllocator::trackUsesOf</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/riscv/riscvisellowering-cpp/#acedf14c0b42fdeea7ed01a8a6e051299">transformAddImmMulImm</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/riscv/riscvisellowering-cpp/#ab64eb471c9d5a9db3c882d6bed499ddd">transformAddShlImm</a>, <a href="/web-llvm/docs/api/classes/anonymous-debuginfo-cpp-/debugtypeinforemoval/#ae05a2c490e9c5e36b78c0280c5592a1a">anonymous{DebugInfo.cpp}::DebugTypeInfoRemoval::traverseAndRemap</a>, <a href="/web-llvm/docs/api/classes/llvm/immutablegraphbuilder/#accc2000f874d9bb1c2edf814283e9222">llvm::ImmutableGraphBuilder&lt; MachineGadgetGraph &gt;::trim</a>, <a href="/web-llvm/docs/api/classes/llvm/smallvectorimpl/#aae26f659b722d1d053b93b5f1735f52f">llvm::const_iterator&lt; MemoryLocation &gt;::truncate</a>, <a href="/web-llvm/docs/api/classes/anonymous-aarch64iseldagtodag-cpp-/aarch64dagtodagisel/#a82b877d253e5f301ad84549956c9cfee">anonymous{AArch64ISelDAGToDAG.cpp}::AArch64DAGToDAGISel::tryBitfieldExtractOp</a>, <a href="/web-llvm/docs/api/classes/anonymous-aarch64iseldagtodag-cpp-/aarch64dagtodagisel/#ab9e3068f5d58302b996d7e3be3babd3f">anonymous{AArch64ISelDAGToDAG.cpp}::AArch64DAGToDAGISel::tryBitfieldExtractOpFromSExt</a>, <a href="/web-llvm/docs/api/classes/anonymous-ppciseldagtodag-cpp-/ppcdagtodagisel/#a377cd94b272a4c49477b765611e4a434">anonymous{PPCISelDAGToDAG.cpp}::PPCDAGToDAGISel::tryBitfieldInsert</a>, <a href="/web-llvm/docs/api/classes/anonymous-aarch64iseldagtodag-cpp-/aarch64dagtodagisel/#ad20f6dc8f2338b85fb4092df26df1b1e">anonymous{AArch64ISelDAGToDAG.cpp}::AArch64DAGToDAGISel::tryBitfieldInsertInZeroOp</a>, <a href="/web-llvm/docs/api/classes/anonymous-aarch64iseldagtodag-cpp-/aarch64dagtodagisel/#a67825100ea453502d0a670213260f08f">anonymous{AArch64ISelDAGToDAG.cpp}::AArch64DAGToDAGISel::tryBitfieldInsertOp</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64iseldagtodag-cpp/#acb09f4729b96af486916310eaf0e16f3">tryBitfieldInsertOpFromOr</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64iseldagtodag-cpp/#a380449a9ad9e4e2d3b6b3fdfa75a64d9">tryBitfieldInsertOpFromOrAndImm</a>, <a href="/web-llvm/docs/api/classes/anonymous-ppciseldagtodag-cpp-/ppcdagtodagisel/#aa8db0d17fd3b822273f71549f1f9e70a">anonymous{PPCISelDAGToDAG.cpp}::PPCDAGToDAGISel::tryBitPermutation</a>, <a href="/web-llvm/docs/api/classes/anonymous-xcoreiseldagtodag-cpp-/xcoredagtodagisel/#af3ca2da669fcab80222c31e39e32287d">anonymous{XCoreISelDAGToDAG.cpp}::XCoreDAGToDAGISel::tryBRIND</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/arm/armisellowering-cpp/#acbb9ce3311488486de6d14930b30c5ed">TryCombineBaseUpdate</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64isellowering-cpp/#aaae856ed3494d62692bb06a4d96dc33f">tryCombineCRC32</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64isellowering-cpp/#af5c638629eac280064519ac4dd103c06">tryCombineExtendRShTrunc</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64isellowering-cpp/#aa1aec95090eff4dcf6f51e0991ecc60e">tryCombineFixedPointConvert</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64isellowering-cpp/#adc515df450408045fd43835105d0c6ed">tryCombineLongOpWithDup</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64isellowering-cpp/#a1a7f46d2de90f91e6bf8103dd5f52afe">tryCombineMULLWithUZP1</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64isellowering-cpp/#aad0fb69928bec544ec83f90f26393521">tryCombineShiftImm</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64isellowering-cpp/#adb90031fb3d067969f3951a7a65c3db9">tryCombineToBSL</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64isellowering-cpp/#ad4340bab6e118d0614449e74a779b30c">tryCombineWhileLo</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64isellowering-cpp/#a05f57690dd5d9df763d5b75d14bc47fd">tryConvertSVEWideCompare</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/arm/armisellowering-cpp/#abe50b03585622dd5b4b3c76d44ea7a8e">TryDistrubutionADDVecReduce</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64isellowering-cpp/#ac2caac341848f2601e62da4fed020063">tryExtendDUPToExtractHigh</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/riscv/riscvisellowering-cpp/#ab6ff0707de4c45e3574f85baf38f1b1f">tryFoldSelectIntoOp</a>, <a href="/web-llvm/docs/api/classes/anonymous-aarch64iseldagtodag-cpp-/aarch64dagtodagisel/#a01d5b65fa577bc031d0774c32a047e31">anonymous{AArch64ISelDAGToDAG.cpp}::AArch64DAGToDAGISel::tryIndexedLoad</a>, <a href="/web-llvm/docs/api/classes/anonymous-ppciseldagtodag-cpp-/ppcdagtodagisel/#aa5129e150e18937b6123e93990c1c903">anonymous{PPCISelDAGToDAG.cpp}::PPCDAGToDAGISel::tryIntCompareInGPR</a>, <a href="/web-llvm/docs/api/classes/llvm/hexagondagtodagisel/#a5ca4c7ea43e08e07577cb9024b1f769f">llvm::HexagonDAGToDAGISel::tryLoadOfLoadIntrinsic</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64isellowering-cpp/#af27372c25a294d5d3b8ba864de3419b7">tryLowerPartialReductionToDot</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64isellowering-cpp/#a11ecac3a9729434713c118b4e1a6f52f">tryLowerPartialReductionToWideAdd</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64isellowering-cpp/#a254b0db030fe653dbe78f9336bf97c39">tryLowerToSLI</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/nvptx/nvptxisellowering-cpp/#aa8d333c2eb8d0346da6128f38cf941b5">TryMULWIDECombine</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64iseldagtodag-cpp/#aafaaafa83aac0fe8abe7498d59ceae37">tryOrrWithShift</a>, <a href="/web-llvm/docs/api/classes/anonymous-aarch64asmparser-cpp-/aarch64asmparser/#a3836dbcbb0e7b8207e5b1f40a85269af">anonymous{AArch64AsmParser.cpp}::AArch64AsmParser::tryParsePrefetch</a>, <a href="/web-llvm/docs/api/classes/anonymous-aarch64iseldagtodag-cpp-/aarch64dagtodagisel/#a31e2cb8d967c9a22d6f6fa22bb46acf6">anonymous{AArch64ISelDAGToDAG.cpp}::AArch64DAGToDAGISel::tryReadRegister</a>, <a href="/web-llvm/docs/api/classes/llvm/sandboxir/scheduler/#a9c67d906d22a6018e3ff649bafed6a1a">llvm::sandboxir::Scheduler::trySchedule</a>, <a href="/web-llvm/docs/api/classes/anonymous-aarch64iseldagtodag-cpp-/aarch64dagtodagisel/#af415da4daf8365b80a0f0dba2ee8490e">anonymous{AArch64ISelDAGToDAG.cpp}::AArch64DAGToDAGISel::trySelectCastFixedLengthToScalableVector</a>, <a href="/web-llvm/docs/api/classes/anonymous-aarch64iseldagtodag-cpp-/aarch64dagtodagisel/#ac490424228331c1beb5025ef6d45d2a6">anonymous{AArch64ISelDAGToDAG.cpp}::AArch64DAGToDAGISel::trySelectCastScalableToFixedLengthVector</a>, <a href="/web-llvm/docs/api/classes/anonymous-aarch64iseldagtodag-cpp-/aarch64dagtodagisel/#afe51519b53f2da04c9a224a1da7bd2bc">anonymous{AArch64ISelDAGToDAG.cpp}::AArch64DAGToDAGISel::trySelectStackSlotTagP</a>, <a href="/web-llvm/docs/api/classes/anonymous-aarch64iseldagtodag-cpp-/aarch64dagtodagisel/#a1671cc3411876afb45d27eac3a048d4a">anonymous{AArch64ISelDAGToDAG.cpp}::AArch64DAGToDAGISel::trySelectXAR</a>, <a href="/web-llvm/docs/api/classes/anonymous-aarch64iseldagtodag-cpp-/aarch64dagtodagisel/#a92aeb185d8fa73b0d6b44f62e13af912">anonymous{AArch64ISelDAGToDAG.cpp}::AArch64DAGToDAGISel::tryShiftAmountMod</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64isellowering-cpp/#a19494f628ff5bd818b43081b5615420e">trySwapVSelectOperands</a>, <a href="/web-llvm/docs/api/files/lib/lib/codegen/lib/codegen/selectiondag/dagcombiner-cpp/#a1500f3720744fec61e14c6b3c3b5477f">tryToFoldExtendOfConstant</a>, <a href="/web-llvm/docs/api/files/lib/lib/codegen/lib/codegen/selectiondag/dagcombiner-cpp/#ae362c61a21181f35e570b2d94cdd2056">tryToFoldExtendSelectLoad</a>, <a href="/web-llvm/docs/api/files/lib/lib/codegen/lib/codegen/selectiondag/dagcombiner-cpp/#a5d176b4adbcf9fd77cae6c4d43f13fb2">tryToFoldExtOfExtload</a>, <a href="/web-llvm/docs/api/files/lib/lib/codegen/lib/codegen/selectiondag/dagcombiner-cpp/#a07529501831cc322901e5a24586b7720">tryToFoldExtOfLoad</a>, <a href="/web-llvm/docs/api/files/lib/lib/codegen/lib/codegen/selectiondag/dagcombiner-cpp/#aa267be29b6ab02eda3ff34dd9c608b0c">tryToFoldExtOfMaskedLoad</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64isellowering-cpp/#aaca8ed79bbc4fe36c9285bea57d72906">tryToReplaceScalarFPConversionWithSVE</a>, <a href="/web-llvm/docs/api/classes/anonymous-metadataloader-cpp-/bitcodereadermetadatalist/#a0c13d9bd8e412766d16297a360ca60de">anonymous{MetadataLoader.cpp}::BitcodeReaderMetadataList::tryToResolveCycles</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64isellowering-cpp/#a07229844dfee2ef29637eec9717bede7">tryToWidenSetCCOperands</a>, <a href="/web-llvm/docs/api/classes/anonymous-aarch64iseldagtodag-cpp-/aarch64dagtodagisel/#afdc2c44d1804d4fc9cb46857104b3fe9">anonymous{AArch64ISelDAGToDAG.cpp}::AArch64DAGToDAGISel::tryWriteRegister</a>, <a href="/web-llvm/docs/api/classes/llvm/coverage/mcdc/tvidxbuilder/#a85f4860524d04ca3d92dae7f5b1a9fba">llvm::coverage::mcdc::TVIdxBuilder::TVIdxBuilder</a>, <a href="/web-llvm/docs/api/classes/llvm/targetinstrinfo/#af7a82bf89bd98729150cebde60be9dfd">llvm::TargetInstrInfo::unfoldMemoryOperand</a>, <a href="/web-llvm/docs/api/classes/llvm/x86instrinfo/#a768c85ec7c5044117192b9fc18395231">llvm::X86InstrInfo::unfoldMemoryOperand</a>, <a href="/web-llvm/docs/api/files/lib/lib/ir/metadata-cpp/#aa008b56a854aaad64812331d11db62d1">uniquifyImpl</a>, <a href="/web-llvm/docs/api/classes/llvm/selectiondag/#a305a3a4874c597243cd5ba04af01339e">llvm::SelectionDAG::UnrollVectorOp</a>, <a href="/web-llvm/docs/api/classes/llvm/selectiondag/#a5a8d860cc5c733afd761c1e292b5a0aa">llvm::SelectionDAG::UnrollVectorOverflowOp</a>, <a href="/web-llvm/docs/api/classes/anonymous-scheduledagrrlist-cpp-/regreductionpqbase/#a94317da8cf8f9c0cfd21c1af6c9ed449">anonymous{ScheduleDAGRRList.cpp}::RegReductionPQBase::unscheduledNode</a>, <a href="/web-llvm/docs/api/classes/llvm/targetlowering/#a5fb3dd542dde309c8e94f2a54f041814">llvm::TargetLowering::unwrapAddress</a>, <a href="/web-llvm/docs/api/classes/llvm/x86targetlowering/#ae6da32121a396476129bc7577db0aad2">llvm::X86TargetLowering::unwrapAddress</a>, <a href="/web-llvm/docs/api/files/lib/lib/analysis/blockfrequencyinfoimpl-cpp/#a4a494d2e2688c4f4ec901183685c215b">unwrapLoop</a>, <a href="/web-llvm/docs/api/namespaces/anonymous-standardinstrumentations-cpp-/#a88c780934618af67e6d51ba7f5e339f4">anonymous{StandardInstrumentations.cpp}::unwrapModule</a>, <a href="/web-llvm/docs/api/files/lib/lib/objcopy/lib/objcopy/macho/machoobjcopy-cpp/#af77b232892df5c7e1321f2885b0c49ef">updateAndRemoveSymbols</a>, <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/coroutines/corosplit-cpp/#a1d6bceebc19a80123ae26670c7645d1a">updateCallGraphAfterCoroutineSplit</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a2e739fb4907159062aacbbafea669592">llvm::updateCGAndAnalysisManagerForCGSCCPass</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a2a035e8c90cdcf756260ddd5ed0e9a26">llvm::updateCGAndAnalysisManagerForFunctionPass</a>, <a href="/web-llvm/docs/api/files/lib/lib/analysis/cgsccpassmanager-cpp/#a490117b63072462d035a6933fdb94c1f">updateCGAndAnalysisManagerForPass</a>, <a href="/web-llvm/docs/api/classes/llvm/selectiondag/#a1a9bc340dcef73647e894b19458ec9a9">llvm::SelectionDAG::updateDivergence</a>, <a href="/web-llvm/docs/api/files/lib/lib/analysis/cgsccpassmanager-cpp/#ab31c9b14b5bd6245b789fb6ed28a7aeb">updateNewSCCFunctionAnalyses</a>, <a href="/web-llvm/docs/api/classes/llvm/selectiondag/#a7bbb97e3e36105eb34df42371801e262">llvm::SelectionDAG::UpdateNodeOperands</a>, <a href="/web-llvm/docs/api/classes/llvm/selectiondag/#ae8c041f67463ea67d6c43867729b82cb">llvm::SelectionDAG::UpdateNodeOperands</a>, <a href="/web-llvm/docs/api/classes/llvm/selectiondag/#aebbe3664adc51bb118301d1b3f409333">llvm::SelectionDAG::UpdateNodeOperands</a>, <a href="/web-llvm/docs/api/classes/llvm/selectiondag/#a997fc24f538a73150c7058ef7aee7ec3">llvm::SelectionDAG::UpdateNodeOperands</a>, <a href="/web-llvm/docs/api/classes/llvm/selectiondag/#ade30480768cbb8de2f428d81be38fb3f">llvm::SelectionDAG::UpdateNodeOperands</a>, <a href="/web-llvm/docs/api/classes/llvm/selectiondag/#a0b525a306dd91028db958268a2aebe55">llvm::SelectionDAG::UpdateNodeOperands</a>, <a href="/web-llvm/docs/api/structs/llvm/domtreebuilder/semincainfo/#a7f940701e11629de07234b0d717f1e39">llvm::DomTreeBuilder::SemiNCAInfo&lt; DomTreeT &gt;::UpdateRootsAfterUpdate</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a95b7e7311ec52352ada27699c3c9c470">llvm::UpgradeGlobalVariable</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a331b2acd066a224f2e98163aee07bf96">llvm::upgradeInstructionLoopAttachment</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a085e92ed481e12744fdf1740b4751327">llvm::UpgradeIntrinsicCall</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/riscv/riscvisellowering-cpp/#a463fad626413d686ec86863553e1a559">useInversedSetcc</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/powerpc/ppcisellowering-cpp/#a9b97177f4c89df3fd0a2f05deec3378f">usePartialVectorLoads</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/riscv/riscviseldagtodag-cpp/#a31ec69d2a56ad55ca97695260fd53ad7">usesAllOnesMask</a>, <a href="/web-llvm/docs/api/files/lib/lib/fuzzmutate/operations-cpp/#acd02b84e30b7fa3fa475f938e522eb88">validExtractValueIndex</a>, <a href="/web-llvm/docs/api/structs/llvm/sdpatternmatch/value-bind/#a2d537b8dd2303f9e997c594723bcff16">llvm::SDPatternMatch::Value_bind::Value_bind</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64isellowering-cpp/#a1fad5ec2eef05d1c11eec0ee147eabab">vectorToScalarBitmask</a>, <a href="/web-llvm/docs/api/classes/llvm/anonymous-amdgpusplitmodule-cpp-/splitgraph/#a3f77e2cab72167554d1d13c44fc9877d">llvm::anonymous{AMDGPUSplitModule.cpp}::SplitGraph::verifyGraph</a>, <a href="/web-llvm/docs/api/structs/llvm/domtreebuilder/semincainfo/#a4bed97020476a2d93eb433776597d3de">llvm::DomTreeBuilder::SemiNCAInfo&lt; DomTreeT &gt;::verifyReachability</a>, <a href="/web-llvm/docs/api/structs/llvm/domtreebuilder/semincainfo/#aeff699bd020f8620eb57bc0ffd9ce847">llvm::DomTreeBuilder::SemiNCAInfo&lt; DomTreeT &gt;::verifyRoots</a>, <a href="/web-llvm/docs/api/files/lib/lib/codegen/lib/codegen/selectiondag/selectiondag-cpp/#acd50ad0e12fc082d49c38ea80985c612">VerifySDNode</a>, <a href="/web-llvm/docs/api/structs/llvm/domtreebuilder/semincainfo/#a647a59b37db18cd302d604f723ba2ec4">llvm::DomTreeBuilder::SemiNCAInfo&lt; DomTreeT &gt;::verifySiblingProperty</a>, <a href="/web-llvm/docs/api/classes/llvm/aarch64targetlowering/#ab30bbf3bcf699a32f7113173b5cee991">llvm::AArch64TargetLowering::verifyTargetSDNode</a>, <a href="/web-llvm/docs/api/classes/llvm/targetlowering/#a5a4ecad8579717395c05ad1218d440b9">llvm::TargetLowering::verifyTargetSDNode</a>, <a href="/web-llvm/docs/api/classes/anonymous-amdgputargetmachine-cpp-/vgprregisterregalloc/#ac98a714446d08aa3a277f0b6508f5a77">anonymous{AMDGPUTargetMachine.cpp}::VGPRRegisterRegAlloc::VGPRRegisterRegAlloc</a>, <a href="/web-llvm/docs/api/classes/anonymous-amdgpucodegenprepare-cpp-/amdgpucodegenprepareimpl/#a1cbb1fa4211e94aed86925b13569004a">anonymous{AMDGPUCodeGenPrepare.cpp}::AMDGPUCodeGenPrepareImpl::visitBinaryOperator</a>, <a href="/web-llvm/docs/api/classes/anonymous-dataflowsanitizer-cpp-/dfsanvisitor/#a403e1aa9c70e24ee0798d163ce9e0229">anonymous{DataFlowSanitizer.cpp}::DFSanVisitor::visitCallBase</a>, <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/scalar/simpleloopunswitch-cpp/#a18b0f192065386f9e0bc793a08bbf3ff">visitDomSubTree</a>, <a href="/web-llvm/docs/api/classes/anonymous-dagcombiner-cpp-/dagcombiner/#a3ded6112ba385818b252376e0dafa70a">anonymous{DAGCombiner.cpp}::DAGCombiner::visitFADDForFMACombine</a>, <a href="/web-llvm/docs/api/classes/anonymous-dagcombiner-cpp-/dagcombiner/#a15a49815d26dc575a89fcd5df34f18c6">anonymous{DAGCombiner.cpp}::DAGCombiner::visitFMA</a>, <a href="/web-llvm/docs/api/classes/anonymous-dagcombiner-cpp-/dagcombiner/#a10977176a9063297e4ed5e4c23422b29">anonymous{DAGCombiner.cpp}::DAGCombiner::visitFSUBForFMACombine</a>, <a href="/web-llvm/docs/api/classes/llvm/logicalview/lvlogicalvisitor/#a0f7b86f4b3c852f56ca5abb71840a4d6">llvm::logicalview::LVLogicalVisitor::visitKnownRecord</a>, <a href="/web-llvm/docs/api/classes/anonymous-dagcombiner-cpp-/dagcombiner/#a4a242b407971d123820ede5a7147ad62">anonymous{DAGCombiner.cpp}::DAGCombiner::visitMUL</a>, <a href="/web-llvm/docs/api/classes/llvm/instcombinerimpl/#a01ed915fb2acf9fd660ca752edeec0db">llvm::InstCombinerImpl::visitMul</a>, <a href="/web-llvm/docs/api/structs/anonymous-aarch64cleanuplocaldynamictlspass-cpp-/ldtlscleanup/#a047e1c70e1f34092b00f1c8b2d969778">anonymous{AArch64CleanupLocalDynamicTLSPass.cpp}::LDTLSCleanup::VisitNode</a>, <a href="/web-llvm/docs/api/files/lib/lib/codegen/lib/codegen/selectiondag/dagcombiner-cpp/#ac3077960f12b940e1085e66a3eca06b4">visitORCommutative</a>, <a href="/web-llvm/docs/api/classes/llvm/vpblockbase/#ad435a0e2dd67fef67f3169c288480063">llvm::VPBlockBase::VPBlockBase</a>, <a href="/web-llvm/docs/api/classes/llvm/xray/wallclockrecord/#adf294d1f3b834a572ed71a68212827cd">llvm::xray::WallclockRecord::WallclockRecord</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64iseldagtodag-cpp/#a0325404e4ca9868f3b8893516b45c3d2">Widen</a>, <a href="/web-llvm/docs/api/classes/llvm/selectiondag/#ab255633ec6629254aeb996969bc7a212">llvm::SelectionDAG::WidenVector</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/riscv/riscvisellowering-cpp/#abe0c2621dfb4c1e6bcfbaddc38fdf572">widenVectorOpsToi8</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/arm/armisellowering-cpp/#ab1b6f5321d57080da22b0cb6f6a394e7">WinDBZCheckDenominator</a>, <a href="/web-llvm/docs/api/classes/llvm/stringliteral/#ae104622e587c684e9aec229a00b395ae">llvm::StringLiteral::withInnerNUL</a>, <a href="/web-llvm/docs/api/classes/llvm/coverage/testingformatwriter/#af47bcd2c269bb9099d476b455b4dc5ed">llvm::coverage::TestingFormatWriter::write</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#abadfa6a189135012fde92b57982b2ce2">llvm::write_double</a>, <a href="/web-llvm/docs/api/classes/llvm/raw-ostream/#a37b5dd8a8b82f2818e0f4ea9699d8ae5">llvm::raw_ostream::write_hex</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#ab1aedb7c876c118bfb3b40eb756db6f9">llvm::write_hex</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a30e50e9e12c0456609b1c25a38f37572">llvm::write_integer</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#ab302296f87e15940f547f19eb441a12a">llvm::write_integer</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#aeb9032478b4cb6c8242ec014163c32d5">llvm::write_integer</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a5bf1d985e33127a9930a309cfdfdb093">llvm::write_integer</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#ae49c6be8ed5128f73f3c624ca3b87827">llvm::write_integer</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a326ca2731cebac8006185afd1bc96060">llvm::write_integer</a>, <a href="/web-llvm/docs/api/files/lib/lib/support/nativeformatting-cpp/#a486b03efff60127ea29c9ae5bb1b03f7">write_signed</a>, <a href="/web-llvm/docs/api/files/lib/lib/support/nativeformatting-cpp/#a18f13e903a98d38abc2b97b0840b04a8">write_unsigned</a>, <a href="/web-llvm/docs/api/files/lib/lib/support/nativeformatting-cpp/#a8462d4d5c5381616faaacedd724215f4">write_unsigned_impl</a>, <a href="/web-llvm/docs/api/classes/anonymous-elfemitter-cpp-/contiguousblobaccumulator/#aee3c2fffc5bc19465ef3941c6c034ab0">anonymous{ELFEmitter.cpp}::ContiguousBlobAccumulator::writeAsBinary</a>, <a href="/web-llvm/docs/api/classes/llvm/yaml/binaryref/#afc171c69b8c4ca66beae66513b4b1ab4">llvm::yaml::BinaryRef::writeAsBinary</a>, <a href="/web-llvm/docs/api/files/lib/lib/ir/asmwriter-cpp/#a3b2195c3b9d667a9857b9bce7eb8e267">WriteAsOperandInternal</a>, <a href="/web-llvm/docs/api/files/lib/lib/ir/asmwriter-cpp/#aa58433c5fc6be661639b52de0822d890">WriteConstantInternal</a>, <a href="/web-llvm/docs/api/files/lib/lib/ir/asmwriter-cpp/#af7fa07d6c1b002682729091f44ed713f">writeDIArgList</a>, <a href="/web-llvm/docs/api/files/lib/lib/ir/asmwriter-cpp/#ab007fb7393c2c55689a30b5c9f9b54e7">writeDIBasicType</a>, <a href="/web-llvm/docs/api/files/lib/lib/ir/asmwriter-cpp/#aa4ab58811d85ab06ba2589190e42c409">writeDICommonBlock</a>, <a href="/web-llvm/docs/api/files/lib/lib/ir/asmwriter-cpp/#abf928d48c46a6de39967c53eecfb6320">writeDICompileUnit</a>, <a href="/web-llvm/docs/api/files/lib/lib/ir/asmwriter-cpp/#a187176da17ddab193a07b2cde86c2297">writeDICompositeType</a>, <a href="/web-llvm/docs/api/files/lib/lib/ir/asmwriter-cpp/#a6f6d9d4bb9a4379614584f1dc6ec07cc">writeDIDerivedType</a>, <a href="/web-llvm/docs/api/files/lib/lib/ir/asmwriter-cpp/#ad48e4b73f1c3fda1be498800e79bb2d1">writeDIEnumerator</a>, <a href="/web-llvm/docs/api/files/lib/lib/ir/asmwriter-cpp/#ae17ea3efcdbb81ab64b4b54031176d88">writeDIExpression</a>, <a href="/web-llvm/docs/api/files/lib/lib/ir/asmwriter-cpp/#a593a29eb296078e4adc21c4735cbf089">writeDIFile</a>, <a href="/web-llvm/docs/api/files/lib/lib/ir/asmwriter-cpp/#ac7cbec4f02d601d51217c096e1462805">writeDIGenericSubrange</a>, <a href="/web-llvm/docs/api/files/lib/lib/ir/asmwriter-cpp/#a3a754075676cf28fe91f2d0bb1b5fc44">writeDIGlobalVariable</a>, <a href="/web-llvm/docs/api/files/lib/lib/ir/asmwriter-cpp/#a0f3f4b6a41a95ba9e3750a121736c90e">writeDIGlobalVariableExpression</a>, <a href="/web-llvm/docs/api/files/lib/lib/ir/asmwriter-cpp/#a7b805938ab35a8870fff225c689a3019">writeDIImportedEntity</a>, <a href="/web-llvm/docs/api/files/lib/lib/ir/asmwriter-cpp/#a6d889ad151bdaf0e37c410381812c17e">writeDILabel</a>, <a href="/web-llvm/docs/api/files/lib/lib/ir/asmwriter-cpp/#ae839d5f52524ed2102d25ae1ffe92deb">writeDILexicalBlock</a>, <a href="/web-llvm/docs/api/files/lib/lib/ir/asmwriter-cpp/#accd701498a663907e97c9dcedfa7a54a">writeDILexicalBlockFile</a>, <a href="/web-llvm/docs/api/files/lib/lib/ir/asmwriter-cpp/#ab6bcc5e28f19737a3b0ec69ff062c0f9">writeDILocalVariable</a>, <a href="/web-llvm/docs/api/files/lib/lib/ir/asmwriter-cpp/#a01d062dbede1f91bf1c960a57fd349dc">writeDIMacro</a>, <a href="/web-llvm/docs/api/files/lib/lib/ir/asmwriter-cpp/#afd6c1602b1a0ffbb1aad2c7cc9bac1d6">writeDIMacroFile</a>, <a href="/web-llvm/docs/api/files/lib/lib/ir/asmwriter-cpp/#a5584c0a21c6481a943ab39406bd62098">writeDIModule</a>, <a href="/web-llvm/docs/api/files/lib/lib/ir/asmwriter-cpp/#a9d3673e478e66c19b06dcbfb588686c2">writeDINamespace</a>, <a href="/web-llvm/docs/api/files/lib/lib/ir/asmwriter-cpp/#a8197c96b5ae5517644ec4c331c648782">writeDIObjCProperty</a>, <a href="/web-llvm/docs/api/files/lib/lib/ir/asmwriter-cpp/#a3480bb9edd827c6105a2a28652142d9c">writeDIStringType</a>, <a href="/web-llvm/docs/api/files/lib/lib/ir/asmwriter-cpp/#a82755caf4693707060eaa24ed59ebd2a">writeDISubprogram</a>, <a href="/web-llvm/docs/api/files/lib/lib/ir/asmwriter-cpp/#ac7e7ff419d64524657abe5c1389f34dc">writeDISubrange</a>, <a href="/web-llvm/docs/api/files/lib/lib/ir/asmwriter-cpp/#a5fbddbd7054d4a95232371b2c436ab7b">writeDISubroutineType</a>, <a href="/web-llvm/docs/api/files/lib/lib/ir/asmwriter-cpp/#ab9f46d7b60f100ca64722051bf8401b1">writeDITemplateTypeParameter</a>, <a href="/web-llvm/docs/api/files/lib/lib/ir/asmwriter-cpp/#af836f3f665f5c5c4ba40edc1db6ab530">writeDITemplateValueParameter</a>, <a href="/web-llvm/docs/api/files/lib/lib/ir/asmwriter-cpp/#ab51487913b1d80a22af63de2ff1dcb89">writeGenericDINode</a>, <a href="/web-llvm/docs/api/classes/llvm/sampleprof/sampleprofilewriterbinary/#a61e7926d242ffc3cac8fc92591b4178d">llvm::sampleprof::SampleProfileWriterBinary::writeNameTable</a>, <a href="/web-llvm/docs/api/classes/llvm/sampleprof/sampleprofilewriterextbinarybase/#a8da3b86e5070140af1716c64925a0495">llvm::sampleprof::SampleProfileWriterExtBinaryBase::writeNameTable</a>, <a href="/web-llvm/docs/api/classes/anonymous-amdgputargetmachine-cpp-/wwmregisterregalloc/#a6c9e5e71b5a3ea1913fc98782bc293e7">anonymous{AMDGPUTargetMachine.cpp}::WWMRegisterRegAlloc::WWMRegisterRegAlloc</a>, <a href="/web-llvm/docs/api/classes/anonymous-aarch64slshardening-cpp-/thunksset/#ab71b039b6a508980dee2fd8084d9453b">anonymous{AArch64SLSHardening.cpp}::ThunksSet::xRegByIndex</a>, <a href="/web-llvm/docs/api/classes/llvm/datadependencegraph/#ad870278b70634899bc71e1d39be324ae">llvm::DataDependenceGraph::~DataDependenceGraph</a>, <a href="/web-llvm/docs/api/structs/anonymous-hexagonconstextenders-cpp-/rangetree/#a303d486642dc7a77faa396d45f045216">anonymous{HexagonConstExtenders.cpp}::RangeTree::~RangeTree</a> and <a href="/web-llvm/docs/api/classes/llvm/sandboxir/schedbundle/#a61420e352aecd14a2604b3df5cc3d362">llvm::sandboxir::SchedBundle::~SchedBundle</a>.</p>

</div>
</div>

### never {#a3a32062110fa975b1721c449fa7863dc}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">#define never&nbsp;&nbsp;&nbsp;0		/* some &lt;assert.h&gt;s have bugs too */</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 286 of file <a href="/web-llvm/docs/api/files/lib/lib/support/regcomp-c">regcomp.c</a>.</p>


<p>Referenced by <a href="#afc1d8df71f0b5f0795df5212acfd57c9">firstch</a>.</p>

</div>
</div>

### NEXT {#afa19e2eadb751f3599e443d073862a2f}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">#define NEXT()&nbsp;&nbsp;&nbsp;(p-&gt;next++)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 258 of file <a href="/web-llvm/docs/api/files/lib/lib/support/regcomp-c">regcomp.c</a>.</p>


<p>Referenced by <a href="#a41c76f49aa45896e78b801c95970f43b">p_b_cclass</a>, <a href="#a21e3f305c59ef8746b818db2f47b3dc4">p_b_coll_elem</a>, <a href="#a979bf5dd2e011f08e36f469df553441b">p_b_term</a>, <a href="#a37b2c71be1bd09705bd8e3fa728c6b57">p_ere_exp</a> and <a href="#aee283f9c02a8848c8782c35713aad80c">p_simp_re</a>.</p>

</div>
</div>

### NEXT2 {#a0c4c28b39436d006b6efc2d8e796d784}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">#define NEXT2()&nbsp;&nbsp;&nbsp;(p-&gt;next += 2)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 259 of file <a href="/web-llvm/docs/api/files/lib/lib/support/regcomp-c">regcomp.c</a>.</p>


<p>Referenced by <a href="#a979bf5dd2e011f08e36f469df553441b">p_b_term</a>.</p>

</div>
</div>

### NEXTn {#a9f50fecef89d9528dab4f03e00cc3a83}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">#define NEXTn(n)&nbsp;&nbsp;&nbsp;(p-&gt;next += (n))</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 260 of file <a href="/web-llvm/docs/api/files/lib/lib/support/regcomp-c">regcomp.c</a>.</p>


<p>Referenced by <a href="#adf84e1164f7b1e4d7711f5d6131491b0">p_bracket</a>.</p>

</div>
</div>

### NPAREN {#a4d75c71d09855c3c47f35622b289316f}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">#define NPAREN&nbsp;&nbsp;&nbsp;10	/* we need to remember () 1-9 <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64expandpseudoinsts-cpp/#a4cfc8b177e8521a4b496ae2edff6244f">for</a> back refs */</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 201 of file <a href="/web-llvm/docs/api/files/lib/lib/support/regcomp-c">regcomp.c</a>.</p>


<p>Referenced by <a href="#ab437a1156833e5395a0102102cf93c6f">doinsert</a>, <a href="#a94efd6ce730ab2988bfd211af4319873">llvm_regcomp</a>, <a href="#a37b2c71be1bd09705bd8e3fa728c6b57">p_ere_exp</a> and <a href="#aee283f9c02a8848c8782c35713aad80c">p_simp_re</a>.</p>

</div>
</div>

### PEEK {#aa25dac8b80db8b8f03732eeb9ca23934}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">#define PEEK()&nbsp;&nbsp;&nbsp;(*p-&gt;next)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 250 of file <a href="/web-llvm/docs/api/files/lib/lib/support/regcomp-c">regcomp.c</a>.</p>


<p>Referenced by <a href="#a41c76f49aa45896e78b801c95970f43b">p_b_cclass</a>, <a href="#a979bf5dd2e011f08e36f469df553441b">p_b_term</a>, <a href="#adf84e1164f7b1e4d7711f5d6131491b0">p_bracket</a>, <a href="#ae3ba3fa6df61a284fc4b4f9267f2c9b0">p_count</a>, <a href="#ab9fb47c0c5ae241b5de757a26393c11d">p_ere</a>, <a href="#a37b2c71be1bd09705bd8e3fa728c6b57">p_ere_exp</a> and <a href="#aee283f9c02a8848c8782c35713aad80c">p_simp_re</a>.</p>

</div>
</div>

### PEEK2 {#a7eb3d11386334057b36a2a29564502ca}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">#define PEEK2()&nbsp;&nbsp;&nbsp;(*(p-&gt;next+1))</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 251 of file <a href="/web-llvm/docs/api/files/lib/lib/support/regcomp-c">regcomp.c</a>.</p>


<p>Referenced by <a href="#a979bf5dd2e011f08e36f469df553441b">p_b_term</a> and <a href="#a37b2c71be1bd09705bd8e3fa728c6b57">p_ere_exp</a>.</p>

</div>
</div>

### REGINFINITY {#ae6abca5a6c63e69b609228f027a1e7ac}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">#define REGINFINITY&nbsp;&nbsp;&nbsp;(<a href="#a86dc91d509b741fbaa09d2797137250f">DUPMAX</a> + 1)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 281 of file <a href="/web-llvm/docs/api/files/lib/lib/support/regcomp-c">regcomp.c</a>.</p>


<p>Referenced by <a href="#a37b2c71be1bd09705bd8e3fa728c6b57">p_ere_exp</a> and <a href="#aee283f9c02a8848c8782c35713aad80c">p_simp_re</a>.</p>

</div>
</div>

### REP {#acf94cdcef32661117a14bbb806832437}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">#define REP(f, t)&nbsp;&nbsp;&nbsp;((f)*8 + (t))</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 1117 of file <a href="/web-llvm/docs/api/files/lib/lib/support/regcomp-c">regcomp.c</a>.</p>


<p>Referenced by <a href="#a919284efeea9e5256497a0778b7fdd75">repeat</a>.</p>

</div>
</div>

### REQUIRE {#aeb49e5164a8e40811cc769c1fd331d66}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">#define REQUIRE(co, e)&nbsp;&nbsp;&nbsp;(void)((co) || <a href="#a7dab3e6a7c837ba9fd0209963b8d6d76">SETERROR</a>(e))</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 263 of file <a href="/web-llvm/docs/api/files/lib/lib/support/regcomp-c">regcomp.c</a>.</p>


<p>Referenced by <a href="#ac24cfdb8cf256d8fc31d63ae5931db44">p_b_symbol</a>, <a href="#a979bf5dd2e011f08e36f469df553441b">p_b_term</a>, <a href="#aa881669949ccbba0bc595287ea522c31">p_bre</a>, <a href="#ae3ba3fa6df61a284fc4b4f9267f2c9b0">p_count</a>, <a href="#ab9fb47c0c5ae241b5de757a26393c11d">p_ere</a>, <a href="#a37b2c71be1bd09705bd8e3fa728c6b57">p_ere_exp</a>, <a href="#aee283f9c02a8848c8782c35713aad80c">p_simp_re</a> and <a href="#a86427d4d576dd8585a539946c3d662b0">p_str</a>.</p>

</div>
</div>

### SEE {#aa27d4f57d0739004f70aba0719150b57}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">#define SEE(c)&nbsp;&nbsp;&nbsp;(<a href="#ace441594c4bd8da94fd64b1c612ca948">MORE</a>() &amp;&amp; <a href="#aa25dac8b80db8b8f03732eeb9ca23934">PEEK</a>() == (c))</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 254 of file <a href="/web-llvm/docs/api/files/lib/lib/support/regcomp-c">regcomp.c</a>.</p>


<p>Referenced by <a href="#a979bf5dd2e011f08e36f469df553441b">p_b_term</a>, <a href="#ab9fb47c0c5ae241b5de757a26393c11d">p_ere</a>, <a href="#a37b2c71be1bd09705bd8e3fa728c6b57">p_ere_exp</a>, <a href="/web-llvm/docs/api/classes/anonymous-looploadelimination-cpp-/loadeliminationforloop/#a1b795b0cd98521a7cf4ab769d9207258">anonymous{LoopLoadElimination.cpp}::LoadEliminationForLoop::processLoop</a> and <a href="/web-llvm/docs/api/classes/anonymous-looploadelimination-cpp-/loadeliminationforloop/#acc9ee85c11fa2173c85a1ba82797d9fb">anonymous{LoopLoadElimination.cpp}::LoadEliminationForLoop::propagateStoredValueToLoadUsers</a>.</p>

</div>
</div>

### SEETWO {#a2a2a6d570798c3d54c3ba019b07bff5b}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">#define SEETWO(a, b)&nbsp;&nbsp;&nbsp;(<a href="#ae8a7b434a5c7a7f1cc2ba29e93870758">MORE2</a>() &amp;&amp; <a href="#aa25dac8b80db8b8f03732eeb9ca23934">PEEK</a>() == (a) &amp;&amp; <a href="#a7eb3d11386334057b36a2a29564502ca">PEEK2</a>() == (b))</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 255 of file <a href="/web-llvm/docs/api/files/lib/lib/support/regcomp-c">regcomp.c</a>.</p>


<p>Referenced by <a href="#a21e3f305c59ef8746b818db2f47b3dc4">p_b_coll_elem</a>, <a href="#adf84e1164f7b1e4d7711f5d6131491b0">p_bracket</a>, <a href="#aa881669949ccbba0bc595287ea522c31">p_bre</a> and <a href="#aee283f9c02a8848c8782c35713aad80c">p_simp_re</a>.</p>

</div>
</div>

### SETERROR {#a7dab3e6a7c837ba9fd0209963b8d6d76}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">#define SETERROR(e)&nbsp;&nbsp;&nbsp;<a href="#af6d02bc5e86c8d1b90cf67aaa719b127">seterr</a>(p, (e))</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 262 of file <a href="/web-llvm/docs/api/files/lib/lib/support/regcomp-c">regcomp.c</a>.</p>


<p>Referenced by <a href="#ada80fc7b6139b088f956ab9200bd15dd">allocset</a>, <a href="#ae5898edb3343d9868fcc1234e0e66fb7">enlarge</a>, <a href="#a94efd6ce730ab2988bfd211af4319873">llvm_regcomp</a>, <a href="#a1f409b976df7f4fa192aa05f9e5c673e">mcadd</a>, <a href="#a41c76f49aa45896e78b801c95970f43b">p_b_cclass</a>, <a href="#a21e3f305c59ef8746b818db2f47b3dc4">p_b_coll_elem</a>, <a href="#a979bf5dd2e011f08e36f469df553441b">p_b_term</a>, <a href="#a37b2c71be1bd09705bd8e3fa728c6b57">p_ere_exp</a>, <a href="#aee283f9c02a8848c8782c35713aad80c">p_simp_re</a>, <a href="#a919284efeea9e5256497a0778b7fdd75">repeat</a> and <a href="#a0b3b7588a93de41b3dd6640e62787e2e">stripsnug</a>.</p>

</div>
</div>

### THERE {#aabbda40c6f9ead8cf0580b32f03afc59}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">#define THERE()&nbsp;&nbsp;&nbsp;(p-&gt;slen - 1)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 272 of file <a href="/web-llvm/docs/api/files/lib/lib/support/regcomp-c">regcomp.c</a>.</p>


<p>Referenced by <a href="#a94efd6ce730ab2988bfd211af4319873">llvm_regcomp</a>, <a href="#ab9fb47c0c5ae241b5de757a26393c11d">p_ere</a>, <a href="#a37b2c71be1bd09705bd8e3fa728c6b57">p_ere_exp</a> and <a href="#a919284efeea9e5256497a0778b7fdd75">repeat</a>.</p>

</div>
</div>

### THERETHERE {#aeda59df8383196f8a403d52abb973470}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">#define THERETHERE()&nbsp;&nbsp;&nbsp;(p-&gt;slen - 2)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 273 of file <a href="/web-llvm/docs/api/files/lib/lib/support/regcomp-c">regcomp.c</a>.</p>


<p>Referenced by <a href="#a37b2c71be1bd09705bd8e3fa728c6b57">p_ere_exp</a> and <a href="#a919284efeea9e5256497a0778b7fdd75">repeat</a>.</p>

</div>
</div>

</div>

<hr/>

<p class="doxyGeneratedBy">Generated via <a href="https://xpack.github.io/doxygen2docusaurus">doxygen2docusaurus</a> 2.0.0 by <a href="https://www.doxygen.nl">Doxygen</a> 1.15.0.</p>

</div>
