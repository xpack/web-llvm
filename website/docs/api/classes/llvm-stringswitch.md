---

# DO NOT EDIT!
# Automatically generated via doxygen2docusaurus by Doxygen.

slug: /api/classes/llvm/stringswitch
custom_edit_url: null
toc_max_heading_level: 4
keywords:
  - doxygen
  - reference
  - class

---

<div class="doxyPage">

# `StringSwitch` Class Template

<p>A switch()-like statement whose cases are string literals. <a href="#details">More...</a></p>

## Declaration

<div class="doxyDeclaration">
template &lt;typename T, typename R = T&gt;
class llvm::StringSwitch&lt;T, R&gt; { ... }
</div>

## Included Headers

<div class="doxyIncludesList">#include "<a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/adt/stringswitch-h">llvm/ADT/StringSwitch.h</a>"
</div>

## Public Constructors Index

<table class="doxyMembersIndex">

<tr class="doxyMemberIndexTemplate">
<td class="doxyMemberIndexTemplate" colspan="2"><div>template &lt;typename T, typename R = T&gt;</div></td>
</tr>
<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemNoTypeNameTemplate" colspan="2" align="left" valign="top"><a href="#acb567c28ed2b00f93894c700dab8faea">StringSwitch</a> (StringRef S)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexTemplate">
<td class="doxyMemberIndexTemplate" colspan="2"><div>template &lt;typename T, typename R = T&gt;</div></td>
</tr>
<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemNoTypeNameTemplate" colspan="2" align="left" valign="top"><a href="#aa1f692f65bb6d37f16536be4d33e5fd9">StringSwitch</a> (const StringSwitch &amp;)=delete</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexTemplate">
<td class="doxyMemberIndexTemplate" colspan="2"><div>template &lt;typename T, typename R = T&gt;</div></td>
</tr>
<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemNoTypeNameTemplate" colspan="2" align="left" valign="top"><a href="#aab282d4e6799b53447e0e749b2993ecf">StringSwitch</a> (StringSwitch &amp;&amp;other)</td>
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

## Public Destructor Index

<table class="doxyMembersIndex">

<tr class="doxyMemberIndexTemplate">
<td class="doxyMemberIndexTemplate" colspan="2"><div>template &lt;typename T, typename R = T&gt;</div></td>
</tr>
<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemNoTypeNameTemplate" colspan="2" align="left" valign="top"><a href="#af941d113404894ae9c27240ad4748c49">~StringSwitch</a> ()=default</td>
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

## Public Operators Index

<table class="doxyMembersIndex">

<tr class="doxyMemberIndexTemplate">
<td class="doxyMemberIndexTemplate" colspan="2"><div>template &lt;typename T, typename R = T&gt;</div></td>
</tr>
<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemTypeTemplate" align="left" valign="top">void</td>
<td class="doxyMemberIndexItemNameTemplate" align="left" valign="top"><a href="#a525554c22e5ea48df34fc3c413efa1ff">operator=</a> (const StringSwitch &amp;)=delete</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexTemplate">
<td class="doxyMemberIndexTemplate" colspan="2"><div>template &lt;typename T, typename R = T&gt;</div></td>
</tr>
<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemTypeTemplate" align="left" valign="top">void</td>
<td class="doxyMemberIndexItemNameTemplate" align="left" valign="top"><a href="#ab8d86ca41cdcda4c93aefb8e6a99f3eb">operator=</a> (StringSwitch &amp;&amp;other)=delete</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexTemplate">
<td class="doxyMemberIndexTemplate" colspan="2"><div>template &lt;typename T, typename R = T&gt;</div></td>
</tr>
<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemNoTypeNameTemplate" colspan="2" align="left" valign="top"><a href="#a4901c18875ca5c40c372512a833c1785">operator R</a> ()</td>
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

## Public Member Functions Index

<table class="doxyMembersIndex">

<tr class="doxyMemberIndexTemplate">
<td class="doxyMemberIndexTemplate" colspan="2"><div>template &lt;typename T, typename R = T&gt;</div></td>
</tr>
<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemTypeTemplate" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/stringswitch">StringSwitch</a> &amp;</td>
<td class="doxyMemberIndexItemNameTemplate" align="left" valign="top"><a href="#a3de12858bdbbd0b3da179d508ff2be75">Case</a> (StringLiteral S, T Value)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexTemplate">
<td class="doxyMemberIndexTemplate" colspan="2"><div>template &lt;typename T, typename R = T&gt;</div></td>
</tr>
<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemTypeTemplate" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/stringswitch">StringSwitch</a> &amp;</td>
<td class="doxyMemberIndexItemNameTemplate" align="left" valign="top"><a href="#aa50a7b1fb270f50ee5fe0db126b9f75f">EndsWith</a> (StringLiteral S, T Value)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexTemplate">
<td class="doxyMemberIndexTemplate" colspan="2"><div>template &lt;typename T, typename R = T&gt;</div></td>
</tr>
<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemTypeTemplate" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/stringswitch">StringSwitch</a> &amp;</td>
<td class="doxyMemberIndexItemNameTemplate" align="left" valign="top"><a href="#a88e653a89d15149cc7a68f88be360303">StartsWith</a> (StringLiteral S, T Value)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexTemplate">
<td class="doxyMemberIndexTemplate" colspan="2"><div>template &lt;typename T, typename R = T&gt;</div></td>
</tr>
<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemTypeTemplate" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/stringswitch">StringSwitch</a> &amp;</td>
<td class="doxyMemberIndexItemNameTemplate" align="left" valign="top"><a href="#aa13f802513b39e1e2a7650011e5651d7">Cases</a> (StringLiteral S0, StringLiteral S1, T Value)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexTemplate">
<td class="doxyMemberIndexTemplate" colspan="2"><div>template &lt;typename T, typename R = T&gt;</div></td>
</tr>
<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemTypeTemplate" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/stringswitch">StringSwitch</a> &amp;</td>
<td class="doxyMemberIndexItemNameTemplate" align="left" valign="top"><a href="#abdc24b10120247d56ec645cb6191fc9a">Cases</a> (StringLiteral S0, StringLiteral S1, StringLiteral S2, T Value)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexTemplate">
<td class="doxyMemberIndexTemplate" colspan="2"><div>template &lt;typename T, typename R = T&gt;</div></td>
</tr>
<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemTypeTemplate" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/stringswitch">StringSwitch</a> &amp;</td>
<td class="doxyMemberIndexItemNameTemplate" align="left" valign="top"><a href="#aa3f39f2122c9d75055c8b37401e375cf">Cases</a> (StringLiteral S0, StringLiteral S1, StringLiteral S2, StringLiteral S3, T Value)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexTemplate">
<td class="doxyMemberIndexTemplate" colspan="2"><div>template &lt;typename T, typename R = T&gt;</div></td>
</tr>
<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemTypeTemplate" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/stringswitch">StringSwitch</a> &amp;</td>
<td class="doxyMemberIndexItemNameTemplate" align="left" valign="top"><a href="#a491cb4cc33dcafc0c4ef8d15ed04c7f1">Cases</a> (StringLiteral S0, StringLiteral S1, StringLiteral S2, StringLiteral S3, StringLiteral S4, T Value)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexTemplate">
<td class="doxyMemberIndexTemplate" colspan="2"><div>template &lt;typename T, typename R = T&gt;</div></td>
</tr>
<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemTypeTemplate" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/stringswitch">StringSwitch</a> &amp;</td>
<td class="doxyMemberIndexItemNameTemplate" align="left" valign="top"><a href="#a1dd17df30c3b52d1e0f5317faaef4e4e">Cases</a> (StringLiteral S0, StringLiteral S1, StringLiteral S2, StringLiteral S3, StringLiteral S4, StringLiteral S5, T Value)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexTemplate">
<td class="doxyMemberIndexTemplate" colspan="2"><div>template &lt;typename T, typename R = T&gt;</div></td>
</tr>
<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemTypeTemplate" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/stringswitch">StringSwitch</a> &amp;</td>
<td class="doxyMemberIndexItemNameTemplate" align="left" valign="top"><a href="#abb7b572d55d25ad0b700231ff2399d98">Cases</a> (StringLiteral S0, StringLiteral S1, StringLiteral S2, StringLiteral S3, StringLiteral S4, StringLiteral S5, StringLiteral S6, T Value)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexTemplate">
<td class="doxyMemberIndexTemplate" colspan="2"><div>template &lt;typename T, typename R = T&gt;</div></td>
</tr>
<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemTypeTemplate" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/stringswitch">StringSwitch</a> &amp;</td>
<td class="doxyMemberIndexItemNameTemplate" align="left" valign="top"><a href="#aa8aef18351d47bdceacdb1da1f7af2c7">Cases</a> (StringLiteral S0, StringLiteral S1, StringLiteral S2, StringLiteral S3, StringLiteral S4, StringLiteral S5, StringLiteral S6, StringLiteral S7, T Value)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexTemplate">
<td class="doxyMemberIndexTemplate" colspan="2"><div>template &lt;typename T, typename R = T&gt;</div></td>
</tr>
<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemTypeTemplate" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/stringswitch">StringSwitch</a> &amp;</td>
<td class="doxyMemberIndexItemNameTemplate" align="left" valign="top"><a href="#a931ede9419864a545b6b679c025b5bb1">Cases</a> (StringLiteral S0, StringLiteral S1, StringLiteral S2, StringLiteral S3, StringLiteral S4, StringLiteral S5, StringLiteral S6, StringLiteral S7, StringLiteral S8, T Value)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexTemplate">
<td class="doxyMemberIndexTemplate" colspan="2"><div>template &lt;typename T, typename R = T&gt;</div></td>
</tr>
<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemTypeTemplate" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/stringswitch">StringSwitch</a> &amp;</td>
<td class="doxyMemberIndexItemNameTemplate" align="left" valign="top"><a href="#ae160b30f330ff80aca770eccbd622bb0">Cases</a> (StringLiteral S0, StringLiteral S1, StringLiteral S2, StringLiteral S3, StringLiteral S4, StringLiteral S5, StringLiteral S6, StringLiteral S7, StringLiteral S8, StringLiteral S9, T Value)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexTemplate">
<td class="doxyMemberIndexTemplate" colspan="2"><div>template &lt;typename T, typename R = T&gt;</div></td>
</tr>
<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemTypeTemplate" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/stringswitch">StringSwitch</a> &amp;</td>
<td class="doxyMemberIndexItemNameTemplate" align="left" valign="top"><a href="#a36af5d2d51b08d83d76264dc33746e8d">CaseLower</a> (StringLiteral S, T Value)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexTemplate">
<td class="doxyMemberIndexTemplate" colspan="2"><div>template &lt;typename T, typename R = T&gt;</div></td>
</tr>
<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemTypeTemplate" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/stringswitch">StringSwitch</a> &amp;</td>
<td class="doxyMemberIndexItemNameTemplate" align="left" valign="top"><a href="#a26f67aa26109e982724285750a39fdb9">EndsWithLower</a> (StringLiteral S, T Value)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexTemplate">
<td class="doxyMemberIndexTemplate" colspan="2"><div>template &lt;typename T, typename R = T&gt;</div></td>
</tr>
<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemTypeTemplate" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/stringswitch">StringSwitch</a> &amp;</td>
<td class="doxyMemberIndexItemNameTemplate" align="left" valign="top"><a href="#a2a3f855f53939cc944792516f0fc8205">StartsWithLower</a> (StringLiteral S, T Value)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexTemplate">
<td class="doxyMemberIndexTemplate" colspan="2"><div>template &lt;typename T, typename R = T&gt;</div></td>
</tr>
<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemTypeTemplate" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/stringswitch">StringSwitch</a> &amp;</td>
<td class="doxyMemberIndexItemNameTemplate" align="left" valign="top"><a href="#a4544df2c19074824906281761017ddfc">CasesLower</a> (StringLiteral S0, StringLiteral S1, T Value)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexTemplate">
<td class="doxyMemberIndexTemplate" colspan="2"><div>template &lt;typename T, typename R = T&gt;</div></td>
</tr>
<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemTypeTemplate" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/stringswitch">StringSwitch</a> &amp;</td>
<td class="doxyMemberIndexItemNameTemplate" align="left" valign="top"><a href="#aefa06ebc7b4fbf480129276bb50d6811">CasesLower</a> (StringLiteral S0, StringLiteral S1, StringLiteral S2, T Value)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexTemplate">
<td class="doxyMemberIndexTemplate" colspan="2"><div>template &lt;typename T, typename R = T&gt;</div></td>
</tr>
<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemTypeTemplate" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/stringswitch">StringSwitch</a> &amp;</td>
<td class="doxyMemberIndexItemNameTemplate" align="left" valign="top"><a href="#a58074239a30b92c33aeba30b27edb376">CasesLower</a> (StringLiteral S0, StringLiteral S1, StringLiteral S2, StringLiteral S3, T Value)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexTemplate">
<td class="doxyMemberIndexTemplate" colspan="2"><div>template &lt;typename T, typename R = T&gt;</div></td>
</tr>
<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemTypeTemplate" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/stringswitch">StringSwitch</a> &amp;</td>
<td class="doxyMemberIndexItemNameTemplate" align="left" valign="top"><a href="#a1a88c815228a7c3609d4ef20daaf8554">CasesLower</a> (StringLiteral S0, StringLiteral S1, StringLiteral S2, StringLiteral S3, StringLiteral S4, T Value)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexTemplate">
<td class="doxyMemberIndexTemplate" colspan="2"><div>template &lt;typename T, typename R = T&gt;</div></td>
</tr>
<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemTypeTemplate" align="left" valign="top">R</td>
<td class="doxyMemberIndexItemNameTemplate" align="left" valign="top"><a href="#a7f0e82e8a818ca43926fceb49be81661">Default</a> (T Value)</td>
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

## Private Member Attributes Index

<table class="doxyMembersIndex">

<tr class="doxyMemberIndexTemplate">
<td class="doxyMemberIndexTemplate" colspan="2"><div>template &lt;typename T, typename R = T&gt;</div></td>
</tr>
<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemTypeTemplate" align="left" valign="top"><a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/stringref">StringRef</a></td>
<td class="doxyMemberIndexItemNameTemplate" align="left" valign="top"><a href="#a408da1a7112ce48825d569248f451a93">Str</a></td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>The string we are matching. <a href="#a408da1a7112ce48825d569248f451a93">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexTemplate">
<td class="doxyMemberIndexTemplate" colspan="2"><div>template &lt;typename T, typename R = T&gt;</div></td>
</tr>
<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemTypeTemplate" align="left" valign="top">std::optional&lt; T &gt;</td>
<td class="doxyMemberIndexItemNameTemplate" align="left" valign="top"><a href="#a36c9f94454740495463dce83f3e476af">Result</a></td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>The pointer to the result of this switch statement, once known, null before that. <a href="#a36c9f94454740495463dce83f3e476af">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

</table>

## Description {#details}

<p>A switch()-like statement whose cases are string literals.</p>


<p>The <a href="/web-llvm/docs/api/classes/llvm/stringswitch">StringSwitch</a> class is a simple form of a switch() statement that determines whether the given string matches one of the given string literals. The template type parameter <span class="doxyComputerOutput">T</span> is the type of the value that will be returned from the string-switch expression. For example, the following code switches on the name of a color in <span class="doxyComputerOutput">argv</span>[i]:</p>


<div class="doxyProgramListing">

<div class="doxyCodeLine"><span class="doxyNoLineNumber">&nbsp;</span><span class="doxyLineContent"><span class="doxyHighlight"><a href="/web-llvm/docs/api/namespaces/anonymous-aarch64a57fploadbalancing-cpp-/#afcb9ac67c90816f55d217d4f629e1047">Color</a> color = <a href="#acb567c28ed2b00f93894c700dab8faea">StringSwitch&lt;Color&gt;</a>(argv[i])</span></span></div>
<div class="doxyCodeLine"><span class="doxyNoLineNumber">&nbsp;</span><span class="doxyLineContent"><span class="doxyHighlight">  .Case(</span><span class="doxyHighlightStringLiteral">"red"</span><span class="doxyHighlight">, Red)</span></span></div>
<div class="doxyCodeLine"><span class="doxyNoLineNumber">&nbsp;</span><span class="doxyLineContent"><span class="doxyHighlight">  .Case(</span><span class="doxyHighlightStringLiteral">"orange"</span><span class="doxyHighlight">, Orange)</span></span></div>
<div class="doxyCodeLine"><span class="doxyNoLineNumber">&nbsp;</span><span class="doxyLineContent"><span class="doxyHighlight">  .Case(</span><span class="doxyHighlightStringLiteral">"yellow"</span><span class="doxyHighlight">, Yellow)</span></span></div>
<div class="doxyCodeLine"><span class="doxyNoLineNumber">&nbsp;</span><span class="doxyLineContent"><span class="doxyHighlight">  .Case(</span><span class="doxyHighlightStringLiteral">"green"</span><span class="doxyHighlight">, Green)</span></span></div>
<div class="doxyCodeLine"><span class="doxyNoLineNumber">&nbsp;</span><span class="doxyLineContent"><span class="doxyHighlight">  .Case(</span><span class="doxyHighlightStringLiteral">"blue"</span><span class="doxyHighlight">, Blue)</span></span></div>
<div class="doxyCodeLine"><span class="doxyNoLineNumber">&nbsp;</span><span class="doxyLineContent"><span class="doxyHighlight">  .Case(</span><span class="doxyHighlightStringLiteral">"indigo"</span><span class="doxyHighlight">, Indigo)</span></span></div>
<div class="doxyCodeLine"><span class="doxyNoLineNumber">&nbsp;</span><span class="doxyLineContent"><span class="doxyHighlight">  .Cases(</span><span class="doxyHighlightStringLiteral">"violet"</span><span class="doxyHighlight">, </span><span class="doxyHighlightStringLiteral">"purple"</span><span class="doxyHighlight">, Violet)</span></span></div>
<div class="doxyCodeLine"><span class="doxyNoLineNumber">&nbsp;</span><span class="doxyLineContent"><span class="doxyHighlight">  .Default(UnknownColor);</span></span></div>

</div>


<p>Definition at line 44 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/adt/stringswitch-h">StringSwitch.h</a>.</p>


<div class="doxySectionDef">

## Public Constructors

### StringSwitch() {#acb567c28ed2b00f93894c700dab8faea}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<div class="doxyMemberTemplate">template &lt;typename T, typename R = T&gt;</div>
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">llvm::StringSwitch&lt; T, R &gt;::StringSwitch (<a href="/web-llvm/docs/api/classes/llvm/stringref">StringRef</a> S)</td>
</tr>
</table>
</td>
<td class="doxyMemberLabelsRight">
<span class="doxyMemberLabels">
<span class="doxyMemberLabel inline">inline</span>
<span class="doxyMemberLabel explicit">explicit</span>
</span>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 53 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/adt/stringswitch-h">StringSwitch.h</a>.</p>


<p>Referenced by <a href="#a3de12858bdbbd0b3da179d508ff2be75">llvm::StringSwitch&lt; T, R &gt;::Case</a>, <a href="#a36af5d2d51b08d83d76264dc33746e8d">llvm::StringSwitch&lt; T, R &gt;::CaseLower</a>, <a href="#ae160b30f330ff80aca770eccbd622bb0">llvm::StringSwitch&lt; T, R &gt;::Cases</a>, <a href="#a931ede9419864a545b6b679c025b5bb1">llvm::StringSwitch&lt; T, R &gt;::Cases</a>, <a href="#aa8aef18351d47bdceacdb1da1f7af2c7">llvm::StringSwitch&lt; T, R &gt;::Cases</a>, <a href="#abb7b572d55d25ad0b700231ff2399d98">llvm::StringSwitch&lt; T, R &gt;::Cases</a>, <a href="#a1dd17df30c3b52d1e0f5317faaef4e4e">llvm::StringSwitch&lt; T, R &gt;::Cases</a>, <a href="#a491cb4cc33dcafc0c4ef8d15ed04c7f1">llvm::StringSwitch&lt; T, R &gt;::Cases</a>, <a href="#aa3f39f2122c9d75055c8b37401e375cf">llvm::StringSwitch&lt; T, R &gt;::Cases</a>, <a href="#abdc24b10120247d56ec645cb6191fc9a">llvm::StringSwitch&lt; T, R &gt;::Cases</a>, <a href="#aa13f802513b39e1e2a7650011e5651d7">llvm::StringSwitch&lt; T, R &gt;::Cases</a>, <a href="#a1a88c815228a7c3609d4ef20daaf8554">llvm::StringSwitch&lt; T, R &gt;::CasesLower</a>, <a href="#a58074239a30b92c33aeba30b27edb376">llvm::StringSwitch&lt; T, R &gt;::CasesLower</a>, <a href="#aefa06ebc7b4fbf480129276bb50d6811">llvm::StringSwitch&lt; T, R &gt;::CasesLower</a>, <a href="#a4544df2c19074824906281761017ddfc">llvm::StringSwitch&lt; T, R &gt;::CasesLower</a>, <a href="#aa50a7b1fb270f50ee5fe0db126b9f75f">llvm::StringSwitch&lt; T, R &gt;::EndsWith</a>, <a href="#a26f67aa26109e982724285750a39fdb9">llvm::StringSwitch&lt; T, R &gt;::EndsWithLower</a>, <a href="#a525554c22e5ea48df34fc3c413efa1ff">llvm::StringSwitch&lt; T, R &gt;::operator=</a>, <a href="#ab8d86ca41cdcda4c93aefb8e6a99f3eb">llvm::StringSwitch&lt; T, R &gt;::operator=</a>, <a href="#a88e653a89d15149cc7a68f88be360303">llvm::StringSwitch&lt; T, R &gt;::StartsWith</a>, <a href="#a2a3f855f53939cc944792516f0fc8205">llvm::StringSwitch&lt; T, R &gt;::StartsWithLower</a>, <a href="#aa1f692f65bb6d37f16536be4d33e5fd9">llvm::StringSwitch&lt; T, R &gt;::StringSwitch</a> and <a href="#aab282d4e6799b53447e0e749b2993ecf">llvm::StringSwitch&lt; T, R &gt;::StringSwitch</a>.</p>

</div>
</div>

### StringSwitch() {#aa1f692f65bb6d37f16536be4d33e5fd9}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<div class="doxyMemberTemplate">template &lt;typename T, typename R = T&gt;</div>
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">llvm::StringSwitch&lt; T, R &gt;::StringSwitch (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/stringswitch">StringSwitch</a> &amp;)</td>
</tr>
</table>
</td>
<td class="doxyMemberLabelsRight">
<span class="doxyMemberLabels">
<span class="doxyMemberLabel delete">delete</span>
</span>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 57 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/adt/stringswitch-h">StringSwitch.h</a>.</p>


<p>Reference <a href="#acb567c28ed2b00f93894c700dab8faea">llvm::StringSwitch&lt; T, R &gt;::StringSwitch</a>.</p>

</div>
</div>

### StringSwitch() {#aab282d4e6799b53447e0e749b2993ecf}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<div class="doxyMemberTemplate">template &lt;typename T, typename R = T&gt;</div>
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">llvm::StringSwitch&lt; T, R &gt;::StringSwitch (<a href="/web-llvm/docs/api/classes/llvm/stringswitch">StringSwitch</a> &amp;&amp; other)</td>
</tr>
</table>
</td>
<td class="doxyMemberLabelsRight">
<span class="doxyMemberLabels">
<span class="doxyMemberLabel inline">inline</span>
</span>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 63 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/adt/stringswitch-h">StringSwitch.h</a>.</p>


<p>References <a href="/web-llvm/docs/api/namespaces/llvm/#abfc9c7ecf70f66901e439f7c04ef3dbb">llvm::move</a> and <a href="#acb567c28ed2b00f93894c700dab8faea">llvm::StringSwitch&lt; T, R &gt;::StringSwitch</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Public Destructor

### \~StringSwitch() {#af941d113404894ae9c27240ad4748c49}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<div class="doxyMemberTemplate">template &lt;typename T, typename R = T&gt;</div>
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">llvm::StringSwitch&lt; T, R &gt;::~StringSwitch ()</td>
</tr>
</table>
</td>
<td class="doxyMemberLabelsRight">
<span class="doxyMemberLabels">
<span class="doxyMemberLabel default">default</span>
</span>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 66 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/adt/stringswitch-h">StringSwitch.h</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Public Operators

### operator R() {#a4901c18875ca5c40c372512a833c1785}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<div class="doxyMemberTemplate">template &lt;typename T, typename R = T&gt;</div>
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">llvm::StringSwitch&lt; T, R &gt;::operator R ()</td>
</tr>
</table>
</td>
<td class="doxyMemberLabelsRight">
<span class="doxyMemberLabels">
<span class="doxyMemberLabel inline">inline</span>
<span class="doxyMemberLabel nodiscard">nodiscard</span>
</span>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 188 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/adt/stringswitch-h">StringSwitch.h</a>.</p>


<p>Reference <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/silowercontrolflow-cpp/#a4868c5d81c5ccc98c47aeab6244346a0">assert</a>.</p>

</div>
</div>

### operator=() {#a525554c22e5ea48df34fc3c413efa1ff}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<div class="doxyMemberTemplate">template &lt;typename T, typename R = T&gt;</div>
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void llvm::StringSwitch&lt; T, R &gt;::operator= (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/stringswitch">StringSwitch</a> &amp;)</td>
</tr>
</table>
</td>
<td class="doxyMemberLabelsRight">
<span class="doxyMemberLabels">
<span class="doxyMemberLabel delete">delete</span>
</span>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 60 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/adt/stringswitch-h">StringSwitch.h</a>.</p>


<p>Reference <a href="#acb567c28ed2b00f93894c700dab8faea">llvm::StringSwitch&lt; T, R &gt;::StringSwitch</a>.</p>

</div>
</div>

### operator=() {#ab8d86ca41cdcda4c93aefb8e6a99f3eb}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<div class="doxyMemberTemplate">template &lt;typename T, typename R = T&gt;</div>
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void llvm::StringSwitch&lt; T, R &gt;::operator= (<a href="/web-llvm/docs/api/classes/llvm/stringswitch">StringSwitch</a> &amp;&amp; other)</td>
</tr>
</table>
</td>
<td class="doxyMemberLabelsRight">
<span class="doxyMemberLabels">
<span class="doxyMemberLabel delete">delete</span>
</span>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 61 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/adt/stringswitch-h">StringSwitch.h</a>.</p>


<p>Reference <a href="#acb567c28ed2b00f93894c700dab8faea">llvm::StringSwitch&lt; T, R &gt;::StringSwitch</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Public Member Functions

### Case() {#a3de12858bdbbd0b3da179d508ff2be75}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<div class="doxyMemberTemplate">template &lt;typename T, typename R = T&gt;</div>
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">StringSwitch &amp; llvm::StringSwitch&lt; T, R &gt;::Case (<a href="/web-llvm/docs/api/classes/llvm/stringliteral">StringLiteral</a> S, T Value)</td>
</tr>
</table>
</td>
<td class="doxyMemberLabelsRight">
<span class="doxyMemberLabels">
<span class="doxyMemberLabel inline">inline</span>
</span>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 69 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/adt/stringswitch-h">StringSwitch.h</a>.</p>


<p>References <a href="#acb567c28ed2b00f93894c700dab8faea">llvm::StringSwitch&lt; T, R &gt;::StringSwitch</a> and <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/mips/mips16isellowering-cpp/#a0acb682b8260ab1c60b918599864e2e5">T</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/namespaces/llvm/#a1fb527457523d460b8cc9380c21e3487">llvm::AArch64StringToVectorLayout</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a30231bf39cddac434ba6ef3431f3631e">llvm::ARMCondCodeFromString</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#ad0d7cafd1635d7ff2c4a658618491fdc">llvm::ARMVectorCondCodeFromString</a>, <a href="#ae160b30f330ff80aca770eccbd622bb0">llvm::StringSwitch&lt; T, R &gt;::Cases</a>, <a href="#a931ede9419864a545b6b679c025b5bb1">llvm::StringSwitch&lt; T, R &gt;::Cases</a>, <a href="#aa8aef18351d47bdceacdb1da1f7af2c7">llvm::StringSwitch&lt; T, R &gt;::Cases</a>, <a href="#abb7b572d55d25ad0b700231ff2399d98">llvm::StringSwitch&lt; T, R &gt;::Cases</a>, <a href="#a1dd17df30c3b52d1e0f5317faaef4e4e">llvm::StringSwitch&lt; T, R &gt;::Cases</a>, <a href="#a491cb4cc33dcafc0c4ef8d15ed04c7f1">llvm::StringSwitch&lt; T, R &gt;::Cases</a>, <a href="#aa3f39f2122c9d75055c8b37401e375cf">llvm::StringSwitch&lt; T, R &gt;::Cases</a>, <a href="#abdc24b10120247d56ec645cb6191fc9a">llvm::StringSwitch&lt; T, R &gt;::Cases</a>, <a href="#aa13f802513b39e1e2a7650011e5651d7">llvm::StringSwitch&lt; T, R &gt;::Cases</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a8d508f23e2580095561902c39911fb9b">llvm::classifyEHPersonality</a>, <a href="/web-llvm/docs/api/namespaces/llvm/elf/#aa2bdca1224d6c61d9e395584a3c3eb4b">llvm::ELF::convertArchNameToEMachine</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#aab775fc8630b56ff01ffc4624fed3a87">llvm::convertStrToExceptionBehavior</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#ac8070537f4f31ef2b969d570ee70d6fa">llvm::convertStrToRoundingMode</a>, <a href="/web-llvm/docs/api/classes/llvm/targetoptions/#aa56ae8efa388a7840c07b61e6a03b33e">llvm::TargetOptions::FramePointerIsReserved</a>, <a href="/web-llvm/docs/api/classes/llvm/amdgpu/hsamd/metadatastreamermsgpackv4/#a14772fdd5684682678e840fcee863a55">llvm::AMDGPU::HSAMD::MetadataStreamerMsgPackV4::getAccessQualifier</a>, <a href="/web-llvm/docs/api/namespaces/llvm/arm/#a7eedaf9c3e17742875752a729cab56f7">llvm::ARM::getArchSynonym</a>, <a href="/web-llvm/docs/api/classes/llvm/triple/#a5d5efe3bb966ce825560b2e6dd46f8ec">llvm::Triple::getArchTypeForLLVMName</a>, <a href="/web-llvm/docs/api/classes/llvm/difile/#a7f69484f6a25f76fceea4fda06fee60d">llvm::DIFile::getChecksumKind</a>, <a href="/web-llvm/docs/api/classes/anonymous-amdgpuasmparser-cpp-/amdgpuasmparser/#ac905bca0319767a6f6590aa62145c2be">anonymous{AMDGPUAsmParser.cpp}::AMDGPUAsmParser::getCPolKind</a>, <a href="/web-llvm/docs/api/namespaces/llvm/hexagon/#afd5440e15db345bf9daf9a8961192663">llvm::Hexagon::getCpu</a>, <a href="/web-llvm/docs/api/namespaces/llvm/xcoff/#a2584f7d1fe1c5ab17f8aaba3dafaed66">llvm::XCOFF::getCpuID</a>, <a href="/web-llvm/docs/api/namespaces/llvm/dwarfyaml/#a9bde8a0a70fe79e96ac7232738deabff">llvm::DWARFYAML::getDWARFEmitterByName</a>, <a href="/web-llvm/docs/api/namespaces/llvm/hexagon-mc/#a14ab5a27df8fdb9f291f2545ffb610a3">llvm::Hexagon_MC::GetELFFlags</a>, <a href="/web-llvm/docs/api/classes/llvm/dicompileunit/#afeaa84c982a7493e02d1b547297e0e69">llvm::DICompileUnit::getEmissionKind</a>, <a href="/web-llvm/docs/api/namespaces/anonymous-dlltooldriver-cpp-/#a9a0afb32a6485a1b9239e7ba2e43b65c">anonymous{DlltoolDriver.cpp}::getEmulation</a>, <a href="/web-llvm/docs/api/namespaces/llvm/aarch64buildattrs/#a74a62fe438b3f361417141dd25db3199">llvm::AArch64BuildAttrs::getFeatureAndBitsTagsID</a>, <a href="/web-llvm/docs/api/classes/anonymous-aarch64asmbackend-cpp-/aarch64asmbackend/#aa431a4802cd07f5834ca37b0413952ec">anonymous{AArch64AsmBackend.cpp}::AArch64AsmBackend::getFixupKind</a>, <a href="/web-llvm/docs/api/classes/anonymous-amdgpuasmbackend-cpp-/amdgpuasmbackend/#a9c7a7066ba41ebc91a5e5e2c5c50d071">anonymous{AMDGPUAsmBackend.cpp}::AMDGPUAsmBackend::getFixupKind</a>, <a href="/web-llvm/docs/api/classes/anonymous-ppcasmbackend-cpp-/elfppcasmbackend/#afdc328af308a27f89cbb8b79252228de">anonymous{PPCAsmBackend.cpp}::ELFPPCAsmBackend::getFixupKind</a>, <a href="/web-llvm/docs/api/classes/anonymous-sparcasmbackend-cpp-/sparcasmbackend/#af17ba788554dd64c6fdd0ee98c969c2b">anonymous{SparcAsmBackend.cpp}::SparcAsmBackend::getFixupKind</a>, <a href="/web-llvm/docs/api/classes/anonymous-systemzmcasmbackend-cpp-/systemzmcasmbackend/#a0104530e4e778b15dea72e3933b55925">anonymous{SystemZMCAsmBackend.cpp}::SystemZMCAsmBackend::getFixupKind</a>, <a href="/web-llvm/docs/api/classes/anonymous-x86asmbackend-cpp-/windowsx86asmbackend/#abddb25d092c60036cb1dd8e03e5e23ce">anonymous{X86AsmBackend.cpp}::WindowsX86AsmBackend::getFixupKind</a>, <a href="/web-llvm/docs/api/classes/anonymous-x86asmbackend-cpp-/x86asmbackend/#a628c61cc739e4291331529759a81f2ce">anonymous{X86AsmBackend.cpp}::X86AsmBackend::getFixupKind</a>, <a href="/web-llvm/docs/api/classes/llvm/armasmbackendelf/#a61167dc3b30e5e746bf6dc33c07146fd">llvm::ARMAsmBackendELF::getFixupKind</a>, <a href="/web-llvm/docs/api/classes/llvm/avrasmbackend/#a86ec1c09eab7a6bd76bdbd5cd1fc922d">llvm::AVRAsmBackend::getFixupKind</a>, <a href="/web-llvm/docs/api/classes/llvm/loongarchasmbackend/#a3112533bd0846170e7b10c779d04f94b">llvm::LoongArchAsmBackend::getFixupKind</a>, <a href="/web-llvm/docs/api/classes/llvm/mipsasmbackend/#aae0c25f61de4486fee1e2cc6c09a4e1a">llvm::MipsAsmBackend::getFixupKind</a>, <a href="/web-llvm/docs/api/classes/llvm/riscvasmbackend/#af93cdb06931a3c3ccef44a634cb837c2">llvm::RISCVAsmBackend::getFixupKind</a>, <a href="/web-llvm/docs/api/namespaces/anonymous-textstubv5-cpp-/stubparser/#a736134f0d04876e181e093887c0a5edd">anonymous{TextStubV5.cpp}::StubParser::getFlags</a>, <a href="/web-llvm/docs/api/files/lib/lib/ir/intrinsicinst-cpp/#afef6fb615caba281c5f73108e71c468e">getFPPredicateFromMD</a>, <a href="/web-llvm/docs/api/namespaces/llvm/arm/#a04a82d5e283ca414252d3ebd466f0fad">llvm::ARM::getFPUSynonym</a>, <a href="/web-llvm/docs/api/namespaces/llvm/sys/detail/#a5cd7a516996539c18628e51d9f628e07">llvm::sys::detail::getHostCPUNameForARM</a>, <a href="/web-llvm/docs/api/namespaces/llvm/sys/detail/#a506b97a4c93510ccce514cef204be19d">llvm::sys::detail::getHostCPUNameForPowerPC</a>, <a href="/web-llvm/docs/api/namespaces/llvm/sys/detail/#a6c6d718154a7120db2e00cd7a1895aea">llvm::sys::detail::getHostCPUNameForRISCV</a>, <a href="/web-llvm/docs/api/files/lib/lib/targetparser/armtargetparser-cpp/#a51c5b47f454cbf71aed5ac9dbc0f566b">getHWDivSynonym</a>, <a href="/web-llvm/docs/api/files/lib/lib/codegen/lib/codegen/mirparser/milexer-cpp/#a343545c6308183cfae523bf627eb4373">getIdentifierKind</a>, <a href="/web-llvm/docs/api/namespaces/llvm/object/#a5fe32c8c9f04ad9a2301724bf7f601ab">llvm::object::getImageKind</a>, <a href="/web-llvm/docs/api/classes/llvm/m68ktargetlowering/#ac6c58901e3cf6a8800abd157924a0166">llvm::M68kTargetLowering::getInlineAsmMemConstraint</a>, <a href="/web-llvm/docs/api/files/lib/lib/ir/intrinsicinst-cpp/#a999e126bc1cc88c8f31fc84106c1b65f">getIntPredicateFromMD</a>, <a href="/web-llvm/docs/api/classes/llvm/mca/riscvlmulinstrument/#a5a931e7a3f5a08d5878c1cc9b2e4b9ad">llvm::mca::RISCVLMULInstrument::getLMUL</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a4b24b650f118105cc5fbc34c83f006cf">llvm::getMachineType</a>, <a href="/web-llvm/docs/api/groups/dwarfconstantsparsing/#gaedfb90cbf93ba3782def5165b3830452">llvm::dwarf::getMacinfo</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/arm/armiseldagtodag-cpp/#af76eaeb7e369fcb227ebc1d1854956b6">getMClassFlagsMask</a>, <a href="/web-llvm/docs/api/files/lib/lib/codegen/lib/codegen/mirparser/milexer-cpp/#a9d70692332178cbc52cf13297525771c">getMetadataKeywordKind</a>, <a href="/web-llvm/docs/api/classes/llvm/dicompileunit/#a659717c7e0fe157516a881f0de5e1dec">llvm::DICompileUnit::getNameTableKind</a>, <a href="/web-llvm/docs/api/namespaces/llvm/object/#aaf9aa3a9ba5ea1e75d724420a15d1125">llvm::object::getOffloadKind</a>, <a href="/web-llvm/docs/api/groups/dwarfconstantsparsing/#ga3282147626ca93f5875a224cf648aa94">llvm::dwarf::getOperationEncoding</a>, <a href="/web-llvm/docs/api/namespaces/llvm/aarch64buildattrs/#a1552d70a70e16a1b000424999a0ba957">llvm::AArch64BuildAttrs::getOptionalID</a>, <a href="/web-llvm/docs/api/namespaces/llvm/aarch64buildattrs/#aae26d0ec0ccb5ee8ea72e0f296ea75a3">llvm::AArch64BuildAttrs::getPauthABITagsID</a>, <a href="/web-llvm/docs/api/namespaces/llvm/macho/#ad675040b09078b7fd4203a1efbfc6765">llvm::MachO::getPlatformFromName</a>, <a href="/web-llvm/docs/api/classes/llvm/riscvtargetlowering/#a7ade77bdee8e8fe0f6694d0ef8fda0ad">llvm::RISCVTargetLowering::getRegForInlineAsmConstraint</a>, <a href="/web-llvm/docs/api/classes/llvm/avrtargetlowering/#abc10c981c4505185b1d517237acaf9c2">llvm::AVRTargetLowering::getRegisterByName</a>, <a href="/web-llvm/docs/api/classes/llvm/hexagontargetlowering/#ae7573ce36a4dba9654c530165584e450">llvm::HexagonTargetLowering::getRegisterByName</a>, <a href="/web-llvm/docs/api/classes/llvm/lanaitargetlowering/#a7180fced62e46cab7a499bb2b914057e">llvm::LanaiTargetLowering::getRegisterByName</a>, <a href="/web-llvm/docs/api/classes/llvm/mipstargetlowering/#a21a0e970e98d8f88cee991fe790e1fe9">llvm::MipsTargetLowering::getRegisterByName</a>, <a href="/web-llvm/docs/api/classes/llvm/sitargetlowering/#a697cb1debe6ad1be7e59990072185844">llvm::SITargetLowering::getRegisterByName</a>, <a href="/web-llvm/docs/api/classes/llvm/sparctargetlowering/#af4f13984fe50ba9df4f0345922c76639">llvm::SparcTargetLowering::getRegisterByName</a>, <a href="/web-llvm/docs/api/classes/llvm/systemztargetlowering/#ae6cfa37e3a1c1da565288af32dad3e9f">llvm::SystemZTargetLowering::getRegisterByName</a>, <a href="/web-llvm/docs/api/classes/llvm/vetargetlowering/#aefa52d054df295e06e758af765e7dbf4">llvm::VETargetLowering::getRegisterByName</a>, <a href="/web-llvm/docs/api/classes/llvm/x86targetlowering/#a42f7160579c4a68a75447d21da859821">llvm::X86TargetLowering::getRegisterByName</a>, <a href="/web-llvm/docs/api/classes/llvm/mca/riscvsewinstrument/#ac7705a408f195f75fbf074b92cb4bc74">llvm::mca::RISCVSEWInstrument::getSEW</a>, <a href="/web-llvm/docs/api/classes/llvm/pdb/pdbsymbolcompiland/#a10cadbc43e6950a1500f1308cb931c2d">llvm::pdb::PDBSymbolCompiland::getSourceFileFullPath</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/lib/target/amdgpu/asmparser/amdgpuasmparser-cpp/#accab5e4c51ff8b8d5f6e4f434d628f5a">getSpecialRegForName</a>, <a href="/web-llvm/docs/api/namespaces/llvm/loongarchabi/#af8217dcfbfb9f249429cf83c5b9dc107">llvm::LoongArchABI::getTargetABI</a>, <a href="/web-llvm/docs/api/namespaces/llvm/riscvabi/#a16d139f36eb6a2d61dd1c79a4503ecb0">llvm::RISCVABI::getTargetABI</a>, <a href="/web-llvm/docs/api/classes/llvm/amdgpu/hsamd/metadatastreamermsgpackv4/#adb7bfed2c40e61784a27f7a7ccb150a8">llvm::AMDGPU::HSAMD::MetadataStreamerMsgPackV4::getValueKind</a>, <a href="/web-llvm/docs/api/classes/anonymous-armasmparser-cpp-/armasmparser/#a5c6e4f72518fdb9a296586f53019678e">anonymous{ARMAsmParser.cpp}::ARMAsmParser::getVariantKindForName</a>, <a href="/web-llvm/docs/api/classes/llvm/loongarchmcexpr/#a66cc3e0b06526eb09333e4c407425c2a">llvm::LoongArchMCExpr::getVariantKindForName</a>, <a href="/web-llvm/docs/api/classes/llvm/mcsymbolrefexpr/#a433c1cd00305214e7d1d81d682c2346a">llvm::MCSymbolRefExpr::getVariantKindForName</a>, <a href="/web-llvm/docs/api/classes/llvm/riscvmcexpr/#af71a001d22873f5487311a525ee014d7">llvm::RISCVMCExpr::getVariantKindForName</a>, <a href="/web-llvm/docs/api/namespaces/llvm/aarch64buildattrs/#ad766d3db5e5dbd0ab264d5b85814fbf7">llvm::AArch64BuildAttrs::getVendorID</a>, <a href="/web-llvm/docs/api/namespaces/llvm/vfabi/#aaf19acac548dca3c8f263ceb6a860b57">llvm::VFABI::getVFParamKindFromString</a>, <a href="/web-llvm/docs/api/structs/llvm/yaml/scalartraits-21f54daa5a7f69d1f67ec087e8697447/#a8b674d28ee553a4d9594696d639f01d7">llvm::yaml::ScalarTraits&lt; IFSBitWidthType &gt;::input</a>, <a href="/web-llvm/docs/api/structs/llvm/yaml/scalartraits-f70fe88e9b24021c5964543ebadf403d/#a8ca72cfd56434ff061aa86cf6e92f138">llvm::yaml::ScalarTraits&lt; IFSEndiannessType &gt;::input</a>, <a href="/web-llvm/docs/api/structs/llvm/yaml/scalartraits-bfb7e3c2d6178155d508621f8f04dbb7/#ae693a7579ae0e3ce57aa73e31b03efff">llvm::yaml::ScalarTraits&lt; SwiftVersion &gt;::input</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64targettransforminfo-cpp/#accf402c1a02e48bf0826d239322b1f85">isSMEABIRoutineCall</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/powerpc/ppcasmprinter-cpp/#a37e41a7f6870d875dafe144485f2fb3f">isSpecialLLVMGlobalArrayToSkip</a>, <a href="/web-llvm/docs/api/structs/anonymous-bpfasmparser-cpp-/bpfoperand/#a7f7f5247db5bbeb28d50bd5e9bfac0a8">anonymous{BPFAsmParser.cpp}::BPFOperand::isValidIdAtStart</a>, <a href="/web-llvm/docs/api/structs/anonymous-bpfasmparser-cpp-/bpfoperand/#afbaeae8d201ffa2c8db34bb2d65b24d0">anonymous{BPFAsmParser.cpp}::BPFOperand::isValidIdInMiddle</a>, <a href="/web-llvm/docs/api/classes/llvm/object/lexer/#a0f4fa1946ef0ac461232bc74e92dd921">llvm::object::Lexer::lex</a>, <a href="/web-llvm/docs/api/classes/llvm/object/coffobjectfile/#aaf2d41bd06b5c504e4b62f9f8a3bad25">llvm::object::COFFObjectFile::mapDebugSectionName</a>, <a href="/web-llvm/docs/api/classes/llvm/object/machoobjectfile/#a9ebf76d221187db6bf7395a664923d80">llvm::object::MachOObjectFile::mapDebugSectionName</a>, <a href="/web-llvm/docs/api/classes/llvm/object/xcoffobjectfile/#abc07ce668f69931ef8f02942f71c8dca">llvm::object::XCOFFObjectFile::mapDebugSectionName</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/lib/target/aarch64/asmparser/aarch64asmparser-cpp/#a8192bb5558b707429e651b879cd2b433">matchMatrixRegName</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/lib/target/aarch64/asmparser/aarch64asmparser-cpp/#a87c349e8410de484860cfa6dc0f7bb11">matchMatrixTileListRegName</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/lib/target/aarch64/asmparser/aarch64asmparser-cpp/#a6653c5364f4763c10533006042f5f071">MatchNeonVectorRegName</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/lib/target/aarch64/asmparser/aarch64asmparser-cpp/#a26a262811f235c0aac0a514e3128b42c">matchSVEDataVectorRegName</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/lib/target/aarch64/asmparser/aarch64asmparser-cpp/#a43b14a60decc8f407a3d7889a3fb9b18">matchSVEPredicateAsCounterRegName</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/lib/target/aarch64/asmparser/aarch64asmparser-cpp/#ab1e2051a7076e015d29dae1ef73465d8">matchSVEPredicateVectorRegName</a>, <a href="/web-llvm/docs/api/files/lib/lib/mc/lib/mc/mcparser/elfasmparser-cpp/#aef3ca830f5fa48417d89efd24c5a8e98">MCAttrForString</a>, <a href="/web-llvm/docs/api/namespaces/llvm/ppc/#a9e3c196667a91fdc81783769feab2e89">llvm::PPC::normalizeCPUName</a>, <a href="/web-llvm/docs/api/namespaces/llvm/hexagonmcinstrinfo/#afbd5d7edb0e9b02e6072243fa310e97b">llvm::HexagonMCInstrInfo::packetSize</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/amdgputargetmachine-cpp/#a98361b28ee9d2d64026953887c1aff33">parseAMDGPUAtomicOptimizerStrategy</a>, <a href="/web-llvm/docs/api/files/lib/lib/targetparser/triple-cpp/#ad3a9a5aa955e9b62ec11e4d3566d4594">parseArch</a>, <a href="/web-llvm/docs/api/namespaces/llvm/webassembly/#a36696bf11093560ddae04b19b3e6857a">llvm::WebAssembly::parseBlockType</a>, <a href="/web-llvm/docs/api/classes/anonymous-webassemblyasmparser-cpp-/webassemblyasmparser/#a4009b2b10bf09c0de7daf3062a89d803">anonymous{WebAssemblyAsmParser.cpp}::WebAssemblyAsmParser::parseCatchList</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64isellowering-cpp/#a5d8593bb34f2d8b9e8b81d36a3a72e54">parseConstraintCode</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/x86/x86isellowering-cpp/#aa7916a0e32a89dd12645d0c3941b1485">parseConstraintCode</a>, <a href="/web-llvm/docs/api/namespaces/llvm/dwarf-linker/#a112b0124ddda89fd041dbdbc53016275">llvm::dwarf_linker::parseDebugTableName</a>, <a href="/web-llvm/docs/api/classes/anonymous-amdgpuasmparser-cpp-/amdgpuasmparser/#aac5924990c1b6a01f79b3dd8019f5f7b">anonymous{AMDGPUAsmParser.cpp}::AMDGPUAsmParser::parseDelay</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a078e5029b1000e28c9b5a21179491b11">llvm::parseDenormalFPAttributeComponent</a>, <a href="/web-llvm/docs/api/classes/anonymous-darwinasmparser-cpp-/darwinasmparser/#ae246971cdc93908b9f10e7e7a829314c">anonymous{DarwinAsmParser.cpp}::DarwinAsmParser::parseDirectiveDataRegion</a>, <a href="/web-llvm/docs/api/classes/anonymous-darwinasmparser-cpp-/darwinasmparser/#a757668838f5767cbf28d9a5b1201a646">anonymous{DarwinAsmParser.cpp}::DarwinAsmParser::parseDirectiveSection</a>, <a href="/web-llvm/docs/api/classes/anonymous-wasmasmparser-cpp-/wasmasmparser/#adca7252d5d5b7cb17458ac9e482e8bde">anonymous{WasmAsmParser.cpp}::WasmAsmParser::ParseDirectiveSymbolAttribute</a>, <a href="/web-llvm/docs/api/classes/anonymous-elfasmparser-cpp-/elfasmparser/#ace33fcaf2869f1932feb764d96a621fa">anonymous{ELFAsmParser.cpp}::ELFAsmParser::parseDirectiveSymbolAttribute</a>, <a href="/web-llvm/docs/api/classes/anonymous-amdgpuasmparser-cpp-/amdgpuasmparser/#a1ee2ba5e7987e0dc7330c99ad35cdf88">anonymous{AMDGPUAsmParser.cpp}::AMDGPUAsmParser::parseDPPCtrlSel</a>, <a href="/web-llvm/docs/api/classes/llvm/macho/textapiwriter/#a9afb9c049d0f17fe4036dbe6654d4ea2">llvm::MachO::TextAPIWriter::parseFileType</a>, <a href="/web-llvm/docs/api/namespaces/llvm/remarks/#a6c80295c5037fd265a600ae769440d39">llvm::remarks::parseFormat</a>, <a href="/web-llvm/docs/api/classes/anonymous-aarch64asmparser-cpp-/aarch64asmparser/#adc0358b42d36242d132980b3fe8260de">anonymous{AArch64AsmParser.cpp}::AArch64AsmParser::parseInstruction</a>, <a href="/web-llvm/docs/api/classes/anonymous-x86asmparser-cpp-/x86asmparser/#abf6230cdb8093ea54524821d036b2203">anonymous{X86AsmParser.cpp}::X86AsmParser::parseInstruction</a>, <a href="/web-llvm/docs/api/classes/anonymous-amdgpuasmparser-cpp-/amdgpuasmparser/#a5c3abd5a0df4ec19738884622846a92b">anonymous{AMDGPUAsmParser.cpp}::AMDGPUAsmParser::parseInterpAttr</a>, <a href="/web-llvm/docs/api/classes/anonymous-amdgpuasmparser-cpp-/amdgpuasmparser/#abc5a32fe7c02fdcfc1484e926e376ce0">anonymous{AMDGPUAsmParser.cpp}::AMDGPUAsmParser::parseInterpSlot</a>, <a href="/web-llvm/docs/api/structs/anonymous-amdgpulibfunc-cpp-/itaniumparamparser/#aa21569cfdba76deadeb40added273001">anonymous{AMDGPULibFunc.cpp}::ItaniumParamParser::parseItaniumParam</a>, <a href="/web-llvm/docs/api/namespaces/llvm/webassembly/#ad633bade17028bdef34a0637c012eeb2">llvm::WebAssembly::parseMVT</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/amdgpulibfunc-cpp/#a56ec8af379a8cf1ff76e2171f0bbbbb3">parseNamePrefix</a>, <a href="/web-llvm/docs/api/classes/anonymous-miparser-cpp-/miparser/#a7eb95d6aa8ae9f89008ea38203b6e894">anonymous{MIParser.cpp}::MIParser::parseOptionalAtomicOrdering</a>, <a href="/web-llvm/docs/api/files/lib/lib/passes/passbuilder-cpp/#a9e4f6112c778d883860155c39c4d3594">parseOptLevel</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64isellowering-cpp/#a0b1d72a2f4241daf5c6036547f4bbbf0">parsePredicateConstraint</a>, <a href="/web-llvm/docs/api/classes/anonymous-miparser-cpp-/miparser/#a4590f4e05f484028f3b4bf3387955427">anonymous{MIParser.cpp}::MIParser::parsePredicateOperand</a>, <a href="/web-llvm/docs/api/classes/anonymous-amdgpuasmparser-cpp-/amdgpuasmparser/#ab65e752ef8a4ee9e6df01039bfa00b0e">anonymous{AMDGPUAsmParser.cpp}::AMDGPUAsmParser::parsePrimaryExpr</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64isellowering-cpp/#aa07f7f9a7abdfccd15bb1e2c9be4edc7">parseReducedGprConstraint</a>, <a href="/web-llvm/docs/api/classes/anonymous-amdgpuasmparser-cpp-/amdgpuasmparser/#a3a4cad862e9d4dda82fe89b5a2557e97">anonymous{AMDGPUAsmParser.cpp}::AMDGPUAsmParser::parseTH</a>, <a href="/web-llvm/docs/api/namespaces/llvm/riscv/#af23b1af03352d87263aad79e5700fe79">llvm::RISCV::parseTuneCPU</a>, <a href="/web-llvm/docs/api/structs/llvm/remarks/yamlremarkparser/#afe5f8ff50f8bc8d22acbe211ed9e19df">llvm::remarks::YAMLRemarkParser::parseType</a>, <a href="/web-llvm/docs/api/namespaces/llvm/webassembly/#ae55eace303da656ab895760ed2f6da26">llvm::WebAssembly::parseType</a>, <a href="/web-llvm/docs/api/classes/llvm/sparcmcexpr/#a8f8493d80b8e10f21a7d4ea16ac003ea">llvm::SparcMCExpr::parseVariantKind</a>, <a href="/web-llvm/docs/api/classes/llvm/vemcexpr/#a34980fe75ddfddc6b82e729a114d63ee">llvm::VEMCExpr::parseVariantKind</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/lib/target/aarch64/asmparser/aarch64asmparser-cpp/#a6e6c0bab5a3be5e64ec9e03316c0c782">parseVectorKind</a>, <a href="/web-llvm/docs/api/files/lib/lib/targetparser/triple-cpp/#af928c309977e80665cdc60d0b9c46d89">parseVendor</a>, <a href="/web-llvm/docs/api/classes/llvm/symbolremappingreader/#a6b15e282ce11e66f93f7b1a22407547b">llvm::SymbolRemappingReader::read</a>, <a href="/web-llvm/docs/api/files/lib/lib/ir/autoupgrade-cpp/#a3cdb051e7b4490b330de172bbdecbf18">shouldUpgradeNVPTXBF16Intrinsic</a>, <a href="/web-llvm/docs/api/namespaces/llvm/lpac/#a82e423fdc73ec257d71d9881ca6744e8">llvm::LPAC::stringToLanaiAluCode</a>, <a href="/web-llvm/docs/api/namespaces/llvm/riscvfprndmode/#a572415830c007d4e57c1733fdc7007a8">llvm::RISCVFPRndMode::stringToRoundingMode</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a75573c9f0abf07d17e3cd1c8eaf3311b">llvm::stringToVEFCondCode</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#af535846bcbb6c6df0b0a3a81b51bcbf4">llvm::stringToVEICondCode</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#ae6f47e902e2365c054ea9388993ec497">llvm::stringToVERD</a>, <a href="/web-llvm/docs/api/namespaces/anonymous-vfabidemangler-cpp-/#a1e256b3e261a7e37851be3f91173e6c0">anonymous{VFABIDemangler.cpp}::tryParseISA</a>, <a href="/web-llvm/docs/api/files/lib/lib/ir/autoupgrade-cpp/#a4ce4b835cffc5fa4123fe82f5f39cf97">upgradeAArch64IntrinsicCall</a>, <a href="/web-llvm/docs/api/files/lib/lib/ir/autoupgrade-cpp/#aabed4dadfe0a32d2cc856553788212ba">upgradeArmOrAarch64IntrinsicFunction</a>, <a href="/web-llvm/docs/api/files/lib/lib/ir/autoupgrade-cpp/#a0e3d706240976157dfd3542311dc48cb">upgradeIntrinsicFunction1</a> and <a href="/web-llvm/docs/api/files/lib/lib/ir/autoupgrade-cpp/#a634253063317c2a283da15093157baae">upgradeX86IntrinsicFunction</a>.</p>

</div>
</div>

### CaseLower() {#a36af5d2d51b08d83d76264dc33746e8d}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<div class="doxyMemberTemplate">template &lt;typename T, typename R = T&gt;</div>
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">StringSwitch &amp; llvm::StringSwitch&lt; T, R &gt;::CaseLower (<a href="/web-llvm/docs/api/classes/llvm/stringliteral">StringLiteral</a> S, T Value)</td>
</tr>
</table>
</td>
<td class="doxyMemberLabelsRight">
<span class="doxyMemberLabels">
<span class="doxyMemberLabel inline">inline</span>
</span>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 142 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/adt/stringswitch-h">StringSwitch.h</a>.</p>


<p>References <a href="#acb567c28ed2b00f93894c700dab8faea">llvm::StringSwitch&lt; T, R &gt;::StringSwitch</a> and <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/mips/mips16isellowering-cpp/#a0acb682b8260ab1c60b918599864e2e5">T</a>.</p>


<p>Referenced by <a href="#a1a88c815228a7c3609d4ef20daaf8554">llvm::StringSwitch&lt; T, R &gt;::CasesLower</a>, <a href="#a58074239a30b92c33aeba30b27edb376">llvm::StringSwitch&lt; T, R &gt;::CasesLower</a>, <a href="#aefa06ebc7b4fbf480129276bb50d6811">llvm::StringSwitch&lt; T, R &gt;::CasesLower</a>, <a href="#a4544df2c19074824906281761017ddfc">llvm::StringSwitch&lt; T, R &gt;::CasesLower</a> and <a href="/web-llvm/docs/api/classes/anonymous-masmparser-cpp-/masmparser/#ae2e029f6e72e5147a329b0a221f38fbf">anonymous{MasmParser.cpp}::MasmParser::lookUpType</a>.</p>

</div>
</div>

### Cases() {#aa13f802513b39e1e2a7650011e5651d7}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<div class="doxyMemberTemplate">template &lt;typename T, typename R = T&gt;</div>
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">StringSwitch &amp; llvm::StringSwitch&lt; T, R &gt;::Cases (<a href="/web-llvm/docs/api/classes/llvm/stringliteral">StringLiteral</a> S0, <a href="/web-llvm/docs/api/classes/llvm/stringliteral">StringLiteral</a> S1, T Value)</td>
</tr>
</table>
</td>
<td class="doxyMemberLabelsRight">
<span class="doxyMemberLabels">
<span class="doxyMemberLabel inline">inline</span>
</span>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 90 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/adt/stringswitch-h">StringSwitch.h</a>.</p>


<p>References <a href="#a3de12858bdbbd0b3da179d508ff2be75">llvm::StringSwitch&lt; T, R &gt;::Case</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/amdgpulegalizerinfo-cpp/#a22eabd3566ae5f32cb6f594f4f343399">S1</a>, <a href="#acb567c28ed2b00f93894c700dab8faea">llvm::StringSwitch&lt; T, R &gt;::StringSwitch</a> and <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/mips/mips16isellowering-cpp/#a0acb682b8260ab1c60b918599864e2e5">T</a>.</p>


<p>Referenced by <a href="#ae160b30f330ff80aca770eccbd622bb0">llvm::StringSwitch&lt; T, R &gt;::Cases</a>, <a href="#a931ede9419864a545b6b679c025b5bb1">llvm::StringSwitch&lt; T, R &gt;::Cases</a>, <a href="#aa8aef18351d47bdceacdb1da1f7af2c7">llvm::StringSwitch&lt; T, R &gt;::Cases</a>, <a href="#abb7b572d55d25ad0b700231ff2399d98">llvm::StringSwitch&lt; T, R &gt;::Cases</a>, <a href="#a1dd17df30c3b52d1e0f5317faaef4e4e">llvm::StringSwitch&lt; T, R &gt;::Cases</a>, <a href="#a491cb4cc33dcafc0c4ef8d15ed04c7f1">llvm::StringSwitch&lt; T, R &gt;::Cases</a>, <a href="#aa3f39f2122c9d75055c8b37401e375cf">llvm::StringSwitch&lt; T, R &gt;::Cases</a>, <a href="#abdc24b10120247d56ec645cb6191fc9a">llvm::StringSwitch&lt; T, R &gt;::Cases</a>, <a href="/web-llvm/docs/api/classes/llvm/targetoptions/#aa56ae8efa388a7840c07b61e6a03b33e">llvm::TargetOptions::FramePointerIsReserved</a>, <a href="/web-llvm/docs/api/namespaces/llvm/arm/#a7eedaf9c3e17742875752a729cab56f7">llvm::ARM::getArchSynonym</a>, <a href="/web-llvm/docs/api/namespaces/llvm/xcoff/#a2584f7d1fe1c5ab17f8aaba3dafaed66">llvm::XCOFF::getCpuID</a>, <a href="/web-llvm/docs/api/namespaces/llvm/arm/#a04a82d5e283ca414252d3ebd466f0fad">llvm::ARM::getFPUSynonym</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a4b24b650f118105cc5fbc34c83f006cf">llvm::getMachineType</a>, <a href="/web-llvm/docs/api/classes/llvm/riscvtargetlowering/#a7ade77bdee8e8fe0f6694d0ef8fda0ad">llvm::RISCVTargetLowering::getRegForInlineAsmConstraint</a>, <a href="/web-llvm/docs/api/namespaces/llvm/aarch64buildattrs/#afec13a4bcd08acad2ef55c7c35fc4878">llvm::AArch64BuildAttrs::getTypeID</a>, <a href="/web-llvm/docs/api/classes/llvm/mca/riscvlmulinstrument/#a64b0f03818e2adfb7d040addcd629006">llvm::mca::RISCVLMULInstrument::isDataValid</a>, <a href="/web-llvm/docs/api/classes/llvm/mca/riscvsewinstrument/#a415d385fae49859d685eb3c0aaf4c049">llvm::mca::RISCVSEWInstrument::isDataValid</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/powerpc/ppcasmprinter-cpp/#a16ff47c73e3b36831f13b3ff0b1a3f33">isSpecialLLVMGlobalArrayForStaticInit</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/riscv/lib/target/riscv/asmparser/riscvasmparser-cpp/#a04addbe868f651a5ec7d0b799e1331d8">isValidInsnFormat</a>, <a href="/web-llvm/docs/api/files/lib/lib/mc/lib/mc/mcparser/elfasmparser-cpp/#aef3ca830f5fa48417d89efd24c5a8e98">MCAttrForString</a>, <a href="/web-llvm/docs/api/namespaces/llvm/ppc/#a9e3c196667a91fdc81783769feab2e89">llvm::PPC::normalizeCPUName</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/amdgputargetmachine-cpp/#a98361b28ee9d2d64026953887c1aff33">parseAMDGPUAtomicOptimizerStrategy</a>, <a href="/web-llvm/docs/api/files/lib/lib/targetparser/triple-cpp/#ad3a9a5aa955e9b62ec11e4d3566d4594">parseArch</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a078e5029b1000e28c9b5a21179491b11">llvm::parseDenormalFPAttributeComponent</a>, <a href="/web-llvm/docs/api/namespaces/llvm/remarks/#a6c80295c5037fd265a600ae769440d39">llvm::remarks::parseFormat</a>, <a href="/web-llvm/docs/api/classes/anonymous-x86asmparser-cpp-/x86asmparser/#abf6230cdb8093ea54524821d036b2203">anonymous{X86AsmParser.cpp}::X86AsmParser::parseInstruction</a>, <a href="/web-llvm/docs/api/namespaces/llvm/webassembly/#ae55eace303da656ab895760ed2f6da26">llvm::WebAssembly::parseType</a>, <a href="/web-llvm/docs/api/classes/llvm/triple/#a5795a74557bb339afa955660ecb76247">llvm::Triple::Triple</a>, <a href="/web-llvm/docs/api/files/lib/lib/ir/autoupgrade-cpp/#aabed4dadfe0a32d2cc856553788212ba">upgradeArmOrAarch64IntrinsicFunction</a> and <a href="/web-llvm/docs/api/files/lib/lib/ir/autoupgrade-cpp/#a0e3d706240976157dfd3542311dc48cb">upgradeIntrinsicFunction1</a>.</p>

</div>
</div>

### Cases() {#abdc24b10120247d56ec645cb6191fc9a}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<div class="doxyMemberTemplate">template &lt;typename T, typename R = T&gt;</div>
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">StringSwitch &amp; llvm::StringSwitch&lt; T, R &gt;::Cases (<a href="/web-llvm/docs/api/classes/llvm/stringliteral">StringLiteral</a> S0, <a href="/web-llvm/docs/api/classes/llvm/stringliteral">StringLiteral</a> S1, <a href="/web-llvm/docs/api/classes/llvm/stringliteral">StringLiteral</a> S2, T Value)</td>
</tr>
</table>
</td>
<td class="doxyMemberLabelsRight">
<span class="doxyMemberLabels">
<span class="doxyMemberLabel inline">inline</span>
</span>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 94 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/adt/stringswitch-h">StringSwitch.h</a>.</p>


<p>References <a href="#a3de12858bdbbd0b3da179d508ff2be75">llvm::StringSwitch&lt; T, R &gt;::Case</a>, <a href="#aa13f802513b39e1e2a7650011e5651d7">llvm::StringSwitch&lt; T, R &gt;::Cases</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/amdgpulegalizerinfo-cpp/#a22eabd3566ae5f32cb6f594f4f343399">S1</a>, <a href="#acb567c28ed2b00f93894c700dab8faea">llvm::StringSwitch&lt; T, R &gt;::StringSwitch</a> and <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/mips/mips16isellowering-cpp/#a0acb682b8260ab1c60b918599864e2e5">T</a>.</p>

</div>
</div>

### Cases() {#aa3f39f2122c9d75055c8b37401e375cf}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<div class="doxyMemberTemplate">template &lt;typename T, typename R = T&gt;</div>
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">StringSwitch &amp; llvm::StringSwitch&lt; T, R &gt;::Cases (<a href="/web-llvm/docs/api/classes/llvm/stringliteral">StringLiteral</a> S0, <a href="/web-llvm/docs/api/classes/llvm/stringliteral">StringLiteral</a> S1, <a href="/web-llvm/docs/api/classes/llvm/stringliteral">StringLiteral</a> S2, <a href="/web-llvm/docs/api/classes/llvm/stringliteral">StringLiteral</a> S3, T Value)</td>
</tr>
</table>
</td>
<td class="doxyMemberLabelsRight">
<span class="doxyMemberLabels">
<span class="doxyMemberLabel inline">inline</span>
</span>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 99 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/adt/stringswitch-h">StringSwitch.h</a>.</p>


<p>References <a href="#a3de12858bdbbd0b3da179d508ff2be75">llvm::StringSwitch&lt; T, R &gt;::Case</a>, <a href="#aa13f802513b39e1e2a7650011e5651d7">llvm::StringSwitch&lt; T, R &gt;::Cases</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/amdgpulegalizerinfo-cpp/#a22eabd3566ae5f32cb6f594f4f343399">S1</a>, <a href="#acb567c28ed2b00f93894c700dab8faea">llvm::StringSwitch&lt; T, R &gt;::StringSwitch</a> and <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/mips/mips16isellowering-cpp/#a0acb682b8260ab1c60b918599864e2e5">T</a>.</p>

</div>
</div>

### Cases() {#a491cb4cc33dcafc0c4ef8d15ed04c7f1}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<div class="doxyMemberTemplate">template &lt;typename T, typename R = T&gt;</div>
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">StringSwitch &amp; llvm::StringSwitch&lt; T, R &gt;::Cases (<a href="/web-llvm/docs/api/classes/llvm/stringliteral">StringLiteral</a> S0, <a href="/web-llvm/docs/api/classes/llvm/stringliteral">StringLiteral</a> S1, <a href="/web-llvm/docs/api/classes/llvm/stringliteral">StringLiteral</a> S2, <a href="/web-llvm/docs/api/classes/llvm/stringliteral">StringLiteral</a> S3, <a href="/web-llvm/docs/api/classes/llvm/stringliteral">StringLiteral</a> S4, T Value)</td>
</tr>
</table>
</td>
<td class="doxyMemberLabelsRight">
<span class="doxyMemberLabels">
<span class="doxyMemberLabel inline">inline</span>
</span>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 104 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/adt/stringswitch-h">StringSwitch.h</a>.</p>


<p>References <a href="#a3de12858bdbbd0b3da179d508ff2be75">llvm::StringSwitch&lt; T, R &gt;::Case</a>, <a href="#aa13f802513b39e1e2a7650011e5651d7">llvm::StringSwitch&lt; T, R &gt;::Cases</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/amdgpulegalizerinfo-cpp/#a22eabd3566ae5f32cb6f594f4f343399">S1</a>, <a href="#acb567c28ed2b00f93894c700dab8faea">llvm::StringSwitch&lt; T, R &gt;::StringSwitch</a> and <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/mips/mips16isellowering-cpp/#a0acb682b8260ab1c60b918599864e2e5">T</a>.</p>

</div>
</div>

### Cases() {#a1dd17df30c3b52d1e0f5317faaef4e4e}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<div class="doxyMemberTemplate">template &lt;typename T, typename R = T&gt;</div>
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">StringSwitch &amp; llvm::StringSwitch&lt; T, R &gt;::Cases (<a href="/web-llvm/docs/api/classes/llvm/stringliteral">StringLiteral</a> S0, <a href="/web-llvm/docs/api/classes/llvm/stringliteral">StringLiteral</a> S1, <a href="/web-llvm/docs/api/classes/llvm/stringliteral">StringLiteral</a> S2, <a href="/web-llvm/docs/api/classes/llvm/stringliteral">StringLiteral</a> S3, <a href="/web-llvm/docs/api/classes/llvm/stringliteral">StringLiteral</a> S4, <a href="/web-llvm/docs/api/classes/llvm/stringliteral">StringLiteral</a> S5, T Value)</td>
</tr>
</table>
</td>
<td class="doxyMemberLabelsRight">
<span class="doxyMemberLabels">
<span class="doxyMemberLabel inline">inline</span>
</span>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 109 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/adt/stringswitch-h">StringSwitch.h</a>.</p>


<p>References <a href="#a3de12858bdbbd0b3da179d508ff2be75">llvm::StringSwitch&lt; T, R &gt;::Case</a>, <a href="#aa13f802513b39e1e2a7650011e5651d7">llvm::StringSwitch&lt; T, R &gt;::Cases</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/amdgpulegalizerinfo-cpp/#a22eabd3566ae5f32cb6f594f4f343399">S1</a>, <a href="#acb567c28ed2b00f93894c700dab8faea">llvm::StringSwitch&lt; T, R &gt;::StringSwitch</a> and <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/mips/mips16isellowering-cpp/#a0acb682b8260ab1c60b918599864e2e5">T</a>.</p>

</div>
</div>

### Cases() {#abb7b572d55d25ad0b700231ff2399d98}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<div class="doxyMemberTemplate">template &lt;typename T, typename R = T&gt;</div>
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">StringSwitch &amp; llvm::StringSwitch&lt; T, R &gt;::Cases (<a href="/web-llvm/docs/api/classes/llvm/stringliteral">StringLiteral</a> S0, <a href="/web-llvm/docs/api/classes/llvm/stringliteral">StringLiteral</a> S1, <a href="/web-llvm/docs/api/classes/llvm/stringliteral">StringLiteral</a> S2, <a href="/web-llvm/docs/api/classes/llvm/stringliteral">StringLiteral</a> S3, <a href="/web-llvm/docs/api/classes/llvm/stringliteral">StringLiteral</a> S4, <a href="/web-llvm/docs/api/classes/llvm/stringliteral">StringLiteral</a> S5, <a href="/web-llvm/docs/api/classes/llvm/stringliteral">StringLiteral</a> S6, T Value)</td>
</tr>
</table>
</td>
<td class="doxyMemberLabelsRight">
<span class="doxyMemberLabels">
<span class="doxyMemberLabel inline">inline</span>
</span>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 115 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/adt/stringswitch-h">StringSwitch.h</a>.</p>


<p>References <a href="#a3de12858bdbbd0b3da179d508ff2be75">llvm::StringSwitch&lt; T, R &gt;::Case</a>, <a href="#aa13f802513b39e1e2a7650011e5651d7">llvm::StringSwitch&lt; T, R &gt;::Cases</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/amdgpulegalizerinfo-cpp/#a22eabd3566ae5f32cb6f594f4f343399">S1</a>, <a href="#acb567c28ed2b00f93894c700dab8faea">llvm::StringSwitch&lt; T, R &gt;::StringSwitch</a> and <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/mips/mips16isellowering-cpp/#a0acb682b8260ab1c60b918599864e2e5">T</a>.</p>

</div>
</div>

### Cases() {#aa8aef18351d47bdceacdb1da1f7af2c7}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<div class="doxyMemberTemplate">template &lt;typename T, typename R = T&gt;</div>
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">StringSwitch &amp; llvm::StringSwitch&lt; T, R &gt;::Cases (<a href="/web-llvm/docs/api/classes/llvm/stringliteral">StringLiteral</a> S0, <a href="/web-llvm/docs/api/classes/llvm/stringliteral">StringLiteral</a> S1, <a href="/web-llvm/docs/api/classes/llvm/stringliteral">StringLiteral</a> S2, <a href="/web-llvm/docs/api/classes/llvm/stringliteral">StringLiteral</a> S3, <a href="/web-llvm/docs/api/classes/llvm/stringliteral">StringLiteral</a> S4, <a href="/web-llvm/docs/api/classes/llvm/stringliteral">StringLiteral</a> S5, <a href="/web-llvm/docs/api/classes/llvm/stringliteral">StringLiteral</a> S6, <a href="/web-llvm/docs/api/classes/llvm/stringliteral">StringLiteral</a> S7, T Value)</td>
</tr>
</table>
</td>
<td class="doxyMemberLabelsRight">
<span class="doxyMemberLabels">
<span class="doxyMemberLabel inline">inline</span>
</span>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 121 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/adt/stringswitch-h">StringSwitch.h</a>.</p>


<p>References <a href="#a3de12858bdbbd0b3da179d508ff2be75">llvm::StringSwitch&lt; T, R &gt;::Case</a>, <a href="#aa13f802513b39e1e2a7650011e5651d7">llvm::StringSwitch&lt; T, R &gt;::Cases</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/amdgpulegalizerinfo-cpp/#a22eabd3566ae5f32cb6f594f4f343399">S1</a>, <a href="#acb567c28ed2b00f93894c700dab8faea">llvm::StringSwitch&lt; T, R &gt;::StringSwitch</a> and <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/mips/mips16isellowering-cpp/#a0acb682b8260ab1c60b918599864e2e5">T</a>.</p>

</div>
</div>

### Cases() {#a931ede9419864a545b6b679c025b5bb1}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<div class="doxyMemberTemplate">template &lt;typename T, typename R = T&gt;</div>
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">StringSwitch &amp; llvm::StringSwitch&lt; T, R &gt;::Cases (<a href="/web-llvm/docs/api/classes/llvm/stringliteral">StringLiteral</a> S0, <a href="/web-llvm/docs/api/classes/llvm/stringliteral">StringLiteral</a> S1, <a href="/web-llvm/docs/api/classes/llvm/stringliteral">StringLiteral</a> S2, <a href="/web-llvm/docs/api/classes/llvm/stringliteral">StringLiteral</a> S3, <a href="/web-llvm/docs/api/classes/llvm/stringliteral">StringLiteral</a> S4, <a href="/web-llvm/docs/api/classes/llvm/stringliteral">StringLiteral</a> S5, <a href="/web-llvm/docs/api/classes/llvm/stringliteral">StringLiteral</a> S6, <a href="/web-llvm/docs/api/classes/llvm/stringliteral">StringLiteral</a> S7, <a href="/web-llvm/docs/api/classes/llvm/stringliteral">StringLiteral</a> S8, T Value)</td>
</tr>
</table>
</td>
<td class="doxyMemberLabelsRight">
<span class="doxyMemberLabels">
<span class="doxyMemberLabel inline">inline</span>
</span>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 127 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/adt/stringswitch-h">StringSwitch.h</a>.</p>


<p>References <a href="#a3de12858bdbbd0b3da179d508ff2be75">llvm::StringSwitch&lt; T, R &gt;::Case</a>, <a href="#aa13f802513b39e1e2a7650011e5651d7">llvm::StringSwitch&lt; T, R &gt;::Cases</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/amdgpulegalizerinfo-cpp/#a22eabd3566ae5f32cb6f594f4f343399">S1</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/amdgpulegalizerinfo-cpp/#af00ba7c018760702ba16a5009cec810c">S8</a>, <a href="#acb567c28ed2b00f93894c700dab8faea">llvm::StringSwitch&lt; T, R &gt;::StringSwitch</a> and <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/mips/mips16isellowering-cpp/#a0acb682b8260ab1c60b918599864e2e5">T</a>.</p>

</div>
</div>

### Cases() {#ae160b30f330ff80aca770eccbd622bb0}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<div class="doxyMemberTemplate">template &lt;typename T, typename R = T&gt;</div>
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">StringSwitch &amp; llvm::StringSwitch&lt; T, R &gt;::Cases (<a href="/web-llvm/docs/api/classes/llvm/stringliteral">StringLiteral</a> S0, <a href="/web-llvm/docs/api/classes/llvm/stringliteral">StringLiteral</a> S1, <a href="/web-llvm/docs/api/classes/llvm/stringliteral">StringLiteral</a> S2, <a href="/web-llvm/docs/api/classes/llvm/stringliteral">StringLiteral</a> S3, <a href="/web-llvm/docs/api/classes/llvm/stringliteral">StringLiteral</a> S4, <a href="/web-llvm/docs/api/classes/llvm/stringliteral">StringLiteral</a> S5, <a href="/web-llvm/docs/api/classes/llvm/stringliteral">StringLiteral</a> S6, <a href="/web-llvm/docs/api/classes/llvm/stringliteral">StringLiteral</a> S7, <a href="/web-llvm/docs/api/classes/llvm/stringliteral">StringLiteral</a> S8, <a href="/web-llvm/docs/api/classes/llvm/stringliteral">StringLiteral</a> S9, T Value)</td>
</tr>
</table>
</td>
<td class="doxyMemberLabelsRight">
<span class="doxyMemberLabels">
<span class="doxyMemberLabel inline">inline</span>
</span>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 134 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/adt/stringswitch-h">StringSwitch.h</a>.</p>


<p>References <a href="#a3de12858bdbbd0b3da179d508ff2be75">llvm::StringSwitch&lt; T, R &gt;::Case</a>, <a href="#aa13f802513b39e1e2a7650011e5651d7">llvm::StringSwitch&lt; T, R &gt;::Cases</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/amdgpulegalizerinfo-cpp/#a22eabd3566ae5f32cb6f594f4f343399">S1</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/amdgpulegalizerinfo-cpp/#af00ba7c018760702ba16a5009cec810c">S8</a>, <a href="#acb567c28ed2b00f93894c700dab8faea">llvm::StringSwitch&lt; T, R &gt;::StringSwitch</a> and <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/mips/mips16isellowering-cpp/#a0acb682b8260ab1c60b918599864e2e5">T</a>.</p>

</div>
</div>

### CasesLower() {#a4544df2c19074824906281761017ddfc}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<div class="doxyMemberTemplate">template &lt;typename T, typename R = T&gt;</div>
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">StringSwitch &amp; llvm::StringSwitch&lt; T, R &gt;::CasesLower (<a href="/web-llvm/docs/api/classes/llvm/stringliteral">StringLiteral</a> S0, <a href="/web-llvm/docs/api/classes/llvm/stringliteral">StringLiteral</a> S1, T Value)</td>
</tr>
</table>
</td>
<td class="doxyMemberLabelsRight">
<span class="doxyMemberLabels">
<span class="doxyMemberLabel inline">inline</span>
</span>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 163 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/adt/stringswitch-h">StringSwitch.h</a>.</p>


<p>References <a href="#a36af5d2d51b08d83d76264dc33746e8d">llvm::StringSwitch&lt; T, R &gt;::CaseLower</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/amdgpulegalizerinfo-cpp/#a22eabd3566ae5f32cb6f594f4f343399">S1</a>, <a href="#acb567c28ed2b00f93894c700dab8faea">llvm::StringSwitch&lt; T, R &gt;::StringSwitch</a> and <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/mips/mips16isellowering-cpp/#a0acb682b8260ab1c60b918599864e2e5">T</a>.</p>


<p>Referenced by <a href="#a1a88c815228a7c3609d4ef20daaf8554">llvm::StringSwitch&lt; T, R &gt;::CasesLower</a>, <a href="#a58074239a30b92c33aeba30b27edb376">llvm::StringSwitch&lt; T, R &gt;::CasesLower</a>, <a href="#aefa06ebc7b4fbf480129276bb50d6811">llvm::StringSwitch&lt; T, R &gt;::CasesLower</a> and <a href="/web-llvm/docs/api/classes/anonymous-masmparser-cpp-/masmparser/#ae2e029f6e72e5147a329b0a221f38fbf">anonymous{MasmParser.cpp}::MasmParser::lookUpType</a>.</p>

</div>
</div>

### CasesLower() {#aefa06ebc7b4fbf480129276bb50d6811}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<div class="doxyMemberTemplate">template &lt;typename T, typename R = T&gt;</div>
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">StringSwitch &amp; llvm::StringSwitch&lt; T, R &gt;::CasesLower (<a href="/web-llvm/docs/api/classes/llvm/stringliteral">StringLiteral</a> S0, <a href="/web-llvm/docs/api/classes/llvm/stringliteral">StringLiteral</a> S1, <a href="/web-llvm/docs/api/classes/llvm/stringliteral">StringLiteral</a> S2, T Value)</td>
</tr>
</table>
</td>
<td class="doxyMemberLabelsRight">
<span class="doxyMemberLabels">
<span class="doxyMemberLabel inline">inline</span>
</span>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 167 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/adt/stringswitch-h">StringSwitch.h</a>.</p>


<p>References <a href="#a36af5d2d51b08d83d76264dc33746e8d">llvm::StringSwitch&lt; T, R &gt;::CaseLower</a>, <a href="#a4544df2c19074824906281761017ddfc">llvm::StringSwitch&lt; T, R &gt;::CasesLower</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/amdgpulegalizerinfo-cpp/#a22eabd3566ae5f32cb6f594f4f343399">S1</a>, <a href="#acb567c28ed2b00f93894c700dab8faea">llvm::StringSwitch&lt; T, R &gt;::StringSwitch</a> and <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/mips/mips16isellowering-cpp/#a0acb682b8260ab1c60b918599864e2e5">T</a>.</p>

</div>
</div>

### CasesLower() {#a58074239a30b92c33aeba30b27edb376}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<div class="doxyMemberTemplate">template &lt;typename T, typename R = T&gt;</div>
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">StringSwitch &amp; llvm::StringSwitch&lt; T, R &gt;::CasesLower (<a href="/web-llvm/docs/api/classes/llvm/stringliteral">StringLiteral</a> S0, <a href="/web-llvm/docs/api/classes/llvm/stringliteral">StringLiteral</a> S1, <a href="/web-llvm/docs/api/classes/llvm/stringliteral">StringLiteral</a> S2, <a href="/web-llvm/docs/api/classes/llvm/stringliteral">StringLiteral</a> S3, T Value)</td>
</tr>
</table>
</td>
<td class="doxyMemberLabelsRight">
<span class="doxyMemberLabels">
<span class="doxyMemberLabel inline">inline</span>
</span>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 172 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/adt/stringswitch-h">StringSwitch.h</a>.</p>


<p>References <a href="#a36af5d2d51b08d83d76264dc33746e8d">llvm::StringSwitch&lt; T, R &gt;::CaseLower</a>, <a href="#a4544df2c19074824906281761017ddfc">llvm::StringSwitch&lt; T, R &gt;::CasesLower</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/amdgpulegalizerinfo-cpp/#a22eabd3566ae5f32cb6f594f4f343399">S1</a>, <a href="#acb567c28ed2b00f93894c700dab8faea">llvm::StringSwitch&lt; T, R &gt;::StringSwitch</a> and <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/mips/mips16isellowering-cpp/#a0acb682b8260ab1c60b918599864e2e5">T</a>.</p>

</div>
</div>

### CasesLower() {#a1a88c815228a7c3609d4ef20daaf8554}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<div class="doxyMemberTemplate">template &lt;typename T, typename R = T&gt;</div>
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">StringSwitch &amp; llvm::StringSwitch&lt; T, R &gt;::CasesLower (<a href="/web-llvm/docs/api/classes/llvm/stringliteral">StringLiteral</a> S0, <a href="/web-llvm/docs/api/classes/llvm/stringliteral">StringLiteral</a> S1, <a href="/web-llvm/docs/api/classes/llvm/stringliteral">StringLiteral</a> S2, <a href="/web-llvm/docs/api/classes/llvm/stringliteral">StringLiteral</a> S3, <a href="/web-llvm/docs/api/classes/llvm/stringliteral">StringLiteral</a> S4, T Value)</td>
</tr>
</table>
</td>
<td class="doxyMemberLabelsRight">
<span class="doxyMemberLabels">
<span class="doxyMemberLabel inline">inline</span>
</span>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 177 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/adt/stringswitch-h">StringSwitch.h</a>.</p>


<p>References <a href="#a36af5d2d51b08d83d76264dc33746e8d">llvm::StringSwitch&lt; T, R &gt;::CaseLower</a>, <a href="#a4544df2c19074824906281761017ddfc">llvm::StringSwitch&lt; T, R &gt;::CasesLower</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/amdgpulegalizerinfo-cpp/#a22eabd3566ae5f32cb6f594f4f343399">S1</a>, <a href="#acb567c28ed2b00f93894c700dab8faea">llvm::StringSwitch&lt; T, R &gt;::StringSwitch</a> and <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/mips/mips16isellowering-cpp/#a0acb682b8260ab1c60b918599864e2e5">T</a>.</p>

</div>
</div>

### Default() {#a7f0e82e8a818ca43926fceb49be81661}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<div class="doxyMemberTemplate">template &lt;typename T, typename R = T&gt;</div>
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">R llvm::StringSwitch&lt; T, R &gt;::Default (T Value)</td>
</tr>
</table>
</td>
<td class="doxyMemberLabelsRight">
<span class="doxyMemberLabels">
<span class="doxyMemberLabel inline">inline</span>
<span class="doxyMemberLabel nodiscard">nodiscard</span>
</span>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 182 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/adt/stringswitch-h">StringSwitch.h</a>.</p>


<p>Reference <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/mips/mips16isellowering-cpp/#a0acb682b8260ab1c60b918599864e2e5">T</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/namespaces/llvm/#a1fb527457523d460b8cc9380c21e3487">llvm::AArch64StringToVectorLayout</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a30231bf39cddac434ba6ef3431f3631e">llvm::ARMCondCodeFromString</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#ad0d7cafd1635d7ff2c4a658618491fdc">llvm::ARMVectorCondCodeFromString</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a8d508f23e2580095561902c39911fb9b">llvm::classifyEHPersonality</a>, <a href="/web-llvm/docs/api/namespaces/llvm/elf/#aa2bdca1224d6c61d9e395584a3c3eb4b">llvm::ELF::convertArchNameToEMachine</a>, <a href="/web-llvm/docs/api/namespaces/llvm/elf/#af629e6836e2820856a0e811938ddf8af">llvm::ELF::convertNameToOSABI</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#aab775fc8630b56ff01ffc4624fed3a87">llvm::convertStrToExceptionBehavior</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#ac8070537f4f31ef2b969d570ee70d6fa">llvm::convertStrToRoundingMode</a>, <a href="/web-llvm/docs/api/classes/llvm/macho/target/#ac60f765fb1e3ea2626663548ace96890">llvm::MachO::Target::create</a>, <a href="/web-llvm/docs/api/classes/llvm/amdgpu/hsamd/metadatastreamermsgpackv4/#a14772fdd5684682678e840fcee863a55">llvm::AMDGPU::HSAMD::MetadataStreamerMsgPackV4::getAccessQualifier</a>, <a href="/web-llvm/docs/api/namespaces/llvm/macho/#a10005555774b1ad4d2a65a0904f3c573">llvm::MachO::getArchitectureFromName</a>, <a href="/web-llvm/docs/api/namespaces/llvm/arm/#a7eedaf9c3e17742875752a729cab56f7">llvm::ARM::getArchSynonym</a>, <a href="/web-llvm/docs/api/classes/llvm/triple/#a5d5efe3bb966ce825560b2e6dd46f8ec">llvm::Triple::getArchTypeForLLVMName</a>, <a href="/web-llvm/docs/api/groups/dwarfconstantsparsing/#ga42773bac5182a842f016704db8007e54">llvm::dwarf::getAttributeEncoding</a>, <a href="/web-llvm/docs/api/classes/llvm/attribute/#a0c53a4c5456480dc377772d5d2f4f832">llvm::Attribute::getAttrKindFromName</a>, <a href="/web-llvm/docs/api/groups/dwarfconstantsparsing/#ga70747367467013c5b906dd29773f16e0">llvm::dwarf::getCallingConvention</a>, <a href="/web-llvm/docs/api/classes/llvm/difile/#a7f69484f6a25f76fceea4fda06fee60d">llvm::DIFile::getChecksumKind</a>, <a href="/web-llvm/docs/api/classes/anonymous-amdgpuasmparser-cpp-/amdgpuasmparser/#ac905bca0319767a6f6590aa62145c2be">anonymous{AMDGPUAsmParser.cpp}::AMDGPUAsmParser::getCPolKind</a>, <a href="/web-llvm/docs/api/namespaces/llvm/hexagon/#afd5440e15db345bf9daf9a8961192663">llvm::Hexagon::getCpu</a>, <a href="/web-llvm/docs/api/namespaces/llvm/xcoff/#a2584f7d1fe1c5ab17f8aaba3dafaed66">llvm::XCOFF::getCpuID</a>, <a href="/web-llvm/docs/api/namespaces/llvm/arm/#ad9995d34f6e4078d008996e58c6d0b85">llvm::ARM::getDefaultExtensions</a>, <a href="/web-llvm/docs/api/namespaces/llvm/csky/#ae8c064152718a0cb588361b2a4e48f8f">llvm::CSKY::getDefaultExtensions</a>, <a href="/web-llvm/docs/api/namespaces/llvm/arm/#ae76c4d8b77249e5552ee21af4f069505">llvm::ARM::getDefaultFPU</a>, <a href="/web-llvm/docs/api/namespaces/llvm/dwarfyaml/#a9bde8a0a70fe79e96ac7232738deabff">llvm::DWARFYAML::getDWARFEmitterByName</a>, <a href="/web-llvm/docs/api/classes/llvm/dicompileunit/#afeaa84c982a7493e02d1b547297e0e69">llvm::DICompileUnit::getEmissionKind</a>, <a href="/web-llvm/docs/api/namespaces/anonymous-dlltooldriver-cpp-/#a9a0afb32a6485a1b9239e7ba2e43b65c">anonymous{DlltoolDriver.cpp}::getEmulation</a>, <a href="/web-llvm/docs/api/namespaces/llvm/aarch64buildattrs/#a74a62fe438b3f361417141dd25db3199">llvm::AArch64BuildAttrs::getFeatureAndBitsTagsID</a>, <a href="/web-llvm/docs/api/classes/anonymous-aarch64asmbackend-cpp-/aarch64asmbackend/#aa431a4802cd07f5834ca37b0413952ec">anonymous{AArch64AsmBackend.cpp}::AArch64AsmBackend::getFixupKind</a>, <a href="/web-llvm/docs/api/classes/anonymous-amdgpuasmbackend-cpp-/amdgpuasmbackend/#a9c7a7066ba41ebc91a5e5e2c5c50d071">anonymous{AMDGPUAsmBackend.cpp}::AMDGPUAsmBackend::getFixupKind</a>, <a href="/web-llvm/docs/api/classes/anonymous-ppcasmbackend-cpp-/elfppcasmbackend/#afdc328af308a27f89cbb8b79252228de">anonymous{PPCAsmBackend.cpp}::ELFPPCAsmBackend::getFixupKind</a>, <a href="/web-llvm/docs/api/classes/anonymous-ppcasmbackend-cpp-/xcoffppcasmbackend/#a5fb342562ad4c5754d23f53ee74931f4">anonymous{PPCAsmBackend.cpp}::XCOFFPPCAsmBackend::getFixupKind</a>, <a href="/web-llvm/docs/api/classes/anonymous-sparcasmbackend-cpp-/sparcasmbackend/#af17ba788554dd64c6fdd0ee98c969c2b">anonymous{SparcAsmBackend.cpp}::SparcAsmBackend::getFixupKind</a>, <a href="/web-llvm/docs/api/classes/anonymous-systemzmcasmbackend-cpp-/systemzmcasmbackend/#a0104530e4e778b15dea72e3933b55925">anonymous{SystemZMCAsmBackend.cpp}::SystemZMCAsmBackend::getFixupKind</a>, <a href="/web-llvm/docs/api/classes/anonymous-x86asmbackend-cpp-/windowsx86asmbackend/#abddb25d092c60036cb1dd8e03e5e23ce">anonymous{X86AsmBackend.cpp}::WindowsX86AsmBackend::getFixupKind</a>, <a href="/web-llvm/docs/api/classes/anonymous-x86asmbackend-cpp-/x86asmbackend/#a628c61cc739e4291331529759a81f2ce">anonymous{X86AsmBackend.cpp}::X86AsmBackend::getFixupKind</a>, <a href="/web-llvm/docs/api/classes/llvm/armasmbackendelf/#a61167dc3b30e5e746bf6dc33c07146fd">llvm::ARMAsmBackendELF::getFixupKind</a>, <a href="/web-llvm/docs/api/classes/llvm/avrasmbackend/#a86ec1c09eab7a6bd76bdbd5cd1fc922d">llvm::AVRAsmBackend::getFixupKind</a>, <a href="/web-llvm/docs/api/classes/llvm/loongarchasmbackend/#a3112533bd0846170e7b10c779d04f94b">llvm::LoongArchAsmBackend::getFixupKind</a>, <a href="/web-llvm/docs/api/classes/llvm/mipsasmbackend/#aae0c25f61de4486fee1e2cc6c09a4e1a">llvm::MipsAsmBackend::getFixupKind</a>, <a href="/web-llvm/docs/api/classes/llvm/riscvasmbackend/#af93cdb06931a3c3ccef44a634cb837c2">llvm::RISCVAsmBackend::getFixupKind</a>, <a href="/web-llvm/docs/api/classes/llvm/dinode/#a35d619dfbd94cfdf3aabaf66cdb6115c">llvm::DINode::getFlag</a>, <a href="/web-llvm/docs/api/classes/llvm/disubprogram/#ab048654bcb9a1b09231983bf1c71efb9">llvm::DISubprogram::getFlag</a>, <a href="/web-llvm/docs/api/namespaces/anonymous-textstubv5-cpp-/stubparser/#a736134f0d04876e181e093887c0a5edd">anonymous{TextStubV5.cpp}::StubParser::getFlags</a>, <a href="/web-llvm/docs/api/files/lib/lib/ir/intrinsicinst-cpp/#afef6fb615caba281c5f73108e71c468e">getFPPredicateFromMD</a>, <a href="/web-llvm/docs/api/namespaces/llvm/arm/#a04a82d5e283ca414252d3ebd466f0fad">llvm::ARM::getFPUSynonym</a>, <a href="/web-llvm/docs/api/namespaces/llvm/sys/detail/#a5cd7a516996539c18628e51d9f628e07">llvm::sys::detail::getHostCPUNameForARM</a>, <a href="/web-llvm/docs/api/namespaces/llvm/sys/detail/#a506b97a4c93510ccce514cef204be19d">llvm::sys::detail::getHostCPUNameForPowerPC</a>, <a href="/web-llvm/docs/api/namespaces/llvm/sys/detail/#a6c6d718154a7120db2e00cd7a1895aea">llvm::sys::detail::getHostCPUNameForRISCV</a>, <a href="/web-llvm/docs/api/files/lib/lib/targetparser/armtargetparser-cpp/#a51c5b47f454cbf71aed5ac9dbc0f566b">getHWDivSynonym</a>, <a href="/web-llvm/docs/api/files/lib/lib/codegen/lib/codegen/mirparser/milexer-cpp/#a343545c6308183cfae523bf627eb4373">getIdentifierKind</a>, <a href="/web-llvm/docs/api/namespaces/llvm/object/#a5fe32c8c9f04ad9a2301724bf7f601ab">llvm::object::getImageKind</a>, <a href="/web-llvm/docs/api/classes/llvm/m68ktargetlowering/#ac6c58901e3cf6a8800abd157924a0166">llvm::M68kTargetLowering::getInlineAsmMemConstraint</a>, <a href="/web-llvm/docs/api/files/lib/lib/ir/intrinsicinst-cpp/#a999e126bc1cc88c8f31fc84106c1b65f">getIntPredicateFromMD</a>, <a href="/web-llvm/docs/api/groups/dwarfconstantsparsing/#ga74b19c4e1fb8540a9975e774efc46fd9">llvm::dwarf::getLanguage</a>, <a href="/web-llvm/docs/api/files/lib/lib/binaryformat/dwarf-cpp/#a4343b39231fb6db37ae8b55d21245386">getLlvmUserOperationEncoding</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a4b24b650f118105cc5fbc34c83f006cf">llvm::getMachineType</a>, <a href="/web-llvm/docs/api/groups/dwarfconstantsparsing/#gaedfb90cbf93ba3782def5165b3830452">llvm::dwarf::getMacinfo</a>, <a href="/web-llvm/docs/api/groups/dwarfconstantsparsing/#gae0b335b23d55246b9c836013516d92d5">llvm::dwarf::getMacro</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/arm/armiseldagtodag-cpp/#af76eaeb7e369fcb227ebc1d1854956b6">getMClassFlagsMask</a>, <a href="/web-llvm/docs/api/files/lib/lib/codegen/lib/codegen/mirparser/milexer-cpp/#a9d70692332178cbc52cf13297525771c">getMetadataKeywordKind</a>, <a href="/web-llvm/docs/api/classes/llvm/dicompileunit/#a659717c7e0fe157516a881f0de5e1dec">llvm::DICompileUnit::getNameTableKind</a>, <a href="/web-llvm/docs/api/namespaces/llvm/object/#aaf9aa3a9ba5ea1e75d724420a15d1125">llvm::object::getOffloadKind</a>, <a href="/web-llvm/docs/api/namespaces/llvm/omp/#ac2fc3a53ac7c2cad1be2ce939074d2cc">llvm::omp::getOpenMPContextTraitPropertyForSelector</a>, <a href="/web-llvm/docs/api/namespaces/llvm/omp/#ab11968aae3de226efd5e696f3e301489">llvm::omp::getOpenMPContextTraitSelectorKind</a>, <a href="/web-llvm/docs/api/namespaces/llvm/omp/#adfc882779f1a9040b8127ccfbed46f71">llvm::omp::getOpenMPContextTraitSetKind</a>, <a href="/web-llvm/docs/api/groups/dwarfconstantsparsing/#ga3282147626ca93f5875a224cf648aa94">llvm::dwarf::getOperationEncoding</a>, <a href="/web-llvm/docs/api/namespaces/llvm/aarch64buildattrs/#a1552d70a70e16a1b000424999a0ba957">llvm::AArch64BuildAttrs::getOptionalID</a>, <a href="/web-llvm/docs/api/namespaces/llvm/aarch64buildattrs/#aae26d0ec0ccb5ee8ea72e0f296ea75a3">llvm::AArch64BuildAttrs::getPauthABITagsID</a>, <a href="/web-llvm/docs/api/namespaces/llvm/macho/#ad675040b09078b7fd4203a1efbfc6765">llvm::MachO::getPlatformFromName</a>, <a href="/web-llvm/docs/api/classes/llvm/riscvtargetlowering/#a7ade77bdee8e8fe0f6694d0ef8fda0ad">llvm::RISCVTargetLowering::getRegForInlineAsmConstraint</a>, <a href="/web-llvm/docs/api/classes/llvm/avrtargetlowering/#abc10c981c4505185b1d517237acaf9c2">llvm::AVRTargetLowering::getRegisterByName</a>, <a href="/web-llvm/docs/api/classes/llvm/hexagontargetlowering/#ae7573ce36a4dba9654c530165584e450">llvm::HexagonTargetLowering::getRegisterByName</a>, <a href="/web-llvm/docs/api/classes/llvm/lanaitargetlowering/#a7180fced62e46cab7a499bb2b914057e">llvm::LanaiTargetLowering::getRegisterByName</a>, <a href="/web-llvm/docs/api/classes/llvm/mipstargetlowering/#a21a0e970e98d8f88cee991fe790e1fe9">llvm::MipsTargetLowering::getRegisterByName</a>, <a href="/web-llvm/docs/api/classes/llvm/sitargetlowering/#a697cb1debe6ad1be7e59990072185844">llvm::SITargetLowering::getRegisterByName</a>, <a href="/web-llvm/docs/api/classes/llvm/sparctargetlowering/#af4f13984fe50ba9df4f0345922c76639">llvm::SparcTargetLowering::getRegisterByName</a>, <a href="/web-llvm/docs/api/classes/llvm/systemztargetlowering/#ae6cfa37e3a1c1da565288af32dad3e9f">llvm::SystemZTargetLowering::getRegisterByName</a>, <a href="/web-llvm/docs/api/classes/llvm/vetargetlowering/#aefa52d054df295e06e758af765e7dbf4">llvm::VETargetLowering::getRegisterByName</a>, <a href="/web-llvm/docs/api/classes/llvm/x86targetlowering/#a42f7160579c4a68a75447d21da859821">llvm::X86TargetLowering::getRegisterByName</a>, <a href="/web-llvm/docs/api/classes/llvm/pdb/pdbsymbolcompiland/#a10cadbc43e6950a1500f1308cb931c2d">llvm::pdb::PDBSymbolCompiland::getSourceFileFullPath</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/lib/target/amdgpu/asmparser/amdgpuasmparser-cpp/#accab5e4c51ff8b8d5f6e4f434d628f5a">getSpecialRegForName</a>, <a href="/web-llvm/docs/api/groups/dwarfconstantsparsing/#ga5e36554e194e99d7da32c35d16ba453a">llvm::dwarf::getTag</a>, <a href="/web-llvm/docs/api/namespaces/llvm/loongarchabi/#af8217dcfbfb9f249429cf83c5b9dc107">llvm::LoongArchABI::getTargetABI</a>, <a href="/web-llvm/docs/api/namespaces/llvm/riscvabi/#a16d139f36eb6a2d61dd1c79a4503ecb0">llvm::RISCVABI::getTargetABI</a>, <a href="/web-llvm/docs/api/namespaces/llvm/aarch64buildattrs/#afec13a4bcd08acad2ef55c7c35fc4878">llvm::AArch64BuildAttrs::getTypeID</a>, <a href="/web-llvm/docs/api/classes/llvm/amdgpu/hsamd/metadatastreamermsgpackv4/#adb7bfed2c40e61784a27f7a7ccb150a8">llvm::AMDGPU::HSAMD::MetadataStreamerMsgPackV4::getValueKind</a>, <a href="/web-llvm/docs/api/classes/anonymous-armasmparser-cpp-/armasmparser/#a5c6e4f72518fdb9a296586f53019678e">anonymous{ARMAsmParser.cpp}::ARMAsmParser::getVariantKindForName</a>, <a href="/web-llvm/docs/api/classes/llvm/loongarchmcexpr/#a66cc3e0b06526eb09333e4c407425c2a">llvm::LoongArchMCExpr::getVariantKindForName</a>, <a href="/web-llvm/docs/api/classes/llvm/mcsymbolrefexpr/#a433c1cd00305214e7d1d81d682c2346a">llvm::MCSymbolRefExpr::getVariantKindForName</a>, <a href="/web-llvm/docs/api/classes/llvm/riscvmcexpr/#af71a001d22873f5487311a525ee014d7">llvm::RISCVMCExpr::getVariantKindForName</a>, <a href="/web-llvm/docs/api/classes/llvm/xtensamcexpr/#a1f6ac568faece433f8a855bcb5397ff9">llvm::XtensaMCExpr::getVariantKindForName</a>, <a href="/web-llvm/docs/api/namespaces/llvm/aarch64buildattrs/#ad766d3db5e5dbd0ab264d5b85814fbf7">llvm::AArch64BuildAttrs::getVendorID</a>, <a href="/web-llvm/docs/api/namespaces/llvm/vfabi/#aaf19acac548dca3c8f263ceb6a860b57">llvm::VFABI::getVFParamKindFromString</a>, <a href="/web-llvm/docs/api/groups/dwarfconstantsparsing/#ga79029f75d17b7821fd61ec6b992d0f84">llvm::dwarf::getVirtuality</a>, <a href="/web-llvm/docs/api/structs/llvm/yaml/scalartraits-21f54daa5a7f69d1f67ec087e8697447/#a8b674d28ee553a4d9594696d639f01d7">llvm::yaml::ScalarTraits&lt; IFSBitWidthType &gt;::input</a>, <a href="/web-llvm/docs/api/structs/llvm/yaml/scalartraits-f70fe88e9b24021c5964543ebadf403d/#a8ca72cfd56434ff061aa86cf6e92f138">llvm::yaml::ScalarTraits&lt; IFSEndiannessType &gt;::input</a>, <a href="/web-llvm/docs/api/structs/llvm/yaml/scalartraits-bfb7e3c2d6178155d508621f8f04dbb7/#ae693a7579ae0e3ce57aa73e31b03efff">llvm::yaml::ScalarTraits&lt; SwiftVersion &gt;::input</a>, <a href="/web-llvm/docs/api/classes/llvm/mca/riscvlmulinstrument/#a64b0f03818e2adfb7d040addcd629006">llvm::mca::RISCVLMULInstrument::isDataValid</a>, <a href="/web-llvm/docs/api/classes/llvm/mca/riscvsewinstrument/#a415d385fae49859d685eb3c0aaf4c049">llvm::mca::RISCVSEWInstrument::isDataValid</a>, <a href="/web-llvm/docs/api/classes/llvm/attribute/#a9b0a1acb1f888349f2e47466c73f2d97">llvm::Attribute::isExistingAttribute</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64targettransforminfo-cpp/#accf402c1a02e48bf0826d239322b1f85">isSMEABIRoutineCall</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/powerpc/ppcasmprinter-cpp/#a16ff47c73e3b36831f13b3ff0b1a3f33">isSpecialLLVMGlobalArrayForStaticInit</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/powerpc/ppcasmprinter-cpp/#a37e41a7f6870d875dafe144485f2fb3f">isSpecialLLVMGlobalArrayToSkip</a>, <a href="/web-llvm/docs/api/structs/anonymous-bpfasmparser-cpp-/bpfoperand/#a7f7f5247db5bbeb28d50bd5e9bfac0a8">anonymous{BPFAsmParser.cpp}::BPFOperand::isValidIdAtStart</a>, <a href="/web-llvm/docs/api/structs/anonymous-bpfasmparser-cpp-/bpfoperand/#afbaeae8d201ffa2c8db34bb2d65b24d0">anonymous{BPFAsmParser.cpp}::BPFOperand::isValidIdInMiddle</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/riscv/lib/target/riscv/asmparser/riscvasmparser-cpp/#a04addbe868f651a5ec7d0b799e1331d8">isValidInsnFormat</a>, <a href="/web-llvm/docs/api/classes/llvm/object/lexer/#a0f4fa1946ef0ac461232bc74e92dd921">llvm::object::Lexer::lex</a>, <a href="/web-llvm/docs/api/classes/anonymous-masmparser-cpp-/masmparser/#ae2e029f6e72e5147a329b0a221f38fbf">anonymous{MasmParser.cpp}::MasmParser::lookUpType</a>, <a href="/web-llvm/docs/api/namespaces/llvm/remarks/#a33db5e22d2f3b0403b2fcd906f5a2377">llvm::remarks::magicToFormat</a>, <a href="/web-llvm/docs/api/classes/llvm/object/coffobjectfile/#aaf2d41bd06b5c504e4b62f9f8a3bad25">llvm::object::COFFObjectFile::mapDebugSectionName</a>, <a href="/web-llvm/docs/api/classes/llvm/object/machoobjectfile/#a9ebf76d221187db6bf7395a664923d80">llvm::object::MachOObjectFile::mapDebugSectionName</a>, <a href="/web-llvm/docs/api/classes/llvm/object/xcoffobjectfile/#abc07ce668f69931ef8f02942f71c8dca">llvm::object::XCOFFObjectFile::mapDebugSectionName</a>, <a href="/web-llvm/docs/api/classes/llvm/object/machoobjectfile/#ac5d1811aaaa04d131a3a65d89888aab1">llvm::object::MachOObjectFile::mapReflectionSectionNameToEnumValue</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/lib/target/aarch64/asmparser/aarch64asmparser-cpp/#a8192bb5558b707429e651b879cd2b433">matchMatrixRegName</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/lib/target/aarch64/asmparser/aarch64asmparser-cpp/#a87c349e8410de484860cfa6dc0f7bb11">matchMatrixTileListRegName</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/lib/target/aarch64/asmparser/aarch64asmparser-cpp/#a6653c5364f4763c10533006042f5f071">MatchNeonVectorRegName</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/lib/target/aarch64/asmparser/aarch64asmparser-cpp/#a26a262811f235c0aac0a514e3128b42c">matchSVEDataVectorRegName</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/lib/target/aarch64/asmparser/aarch64asmparser-cpp/#a43b14a60decc8f407a3d7889a3fb9b18">matchSVEPredicateAsCounterRegName</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/lib/target/aarch64/asmparser/aarch64asmparser-cpp/#ab1e2051a7076e015d29dae1ef73465d8">matchSVEPredicateVectorRegName</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/lanai/lib/target/lanai/asmparser/lanaiasmparser-cpp/#aa381725d28ae64fbe2941e262ad59353">MaybePredicatedInst</a>, <a href="/web-llvm/docs/api/files/lib/lib/mc/lib/mc/mcparser/elfasmparser-cpp/#aef3ca830f5fa48417d89efd24c5a8e98">MCAttrForString</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a0b5c038406239d93579b96463331ff2d">llvm::MCLOHNameToId</a>, <a href="/web-llvm/docs/api/namespaces/llvm/ppc/#a9e3c196667a91fdc81783769feab2e89">llvm::PPC::normalizeCPUName</a>, <a href="/web-llvm/docs/api/namespaces/llvm/hexagonmcinstrinfo/#afbd5d7edb0e9b02e6072243fa310e97b">llvm::HexagonMCInstrInfo::packetSize</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/amdgputargetmachine-cpp/#a98361b28ee9d2d64026953887c1aff33">parseAMDGPUAtomicOptimizerStrategy</a>, <a href="/web-llvm/docs/api/files/lib/lib/targetparser/triple-cpp/#ad3a9a5aa955e9b62ec11e4d3566d4594">parseArch</a>, <a href="/web-llvm/docs/api/namespaces/llvm/arm/#a1d5ed0bfc1c21767207fbd9c06aa68e9">llvm::ARM::parseArchISA</a>, <a href="/web-llvm/docs/api/namespaces/llvm/webassembly/#a36696bf11093560ddae04b19b3e6857a">llvm::WebAssembly::parseBlockType</a>, <a href="/web-llvm/docs/api/classes/anonymous-darwinasmparser-cpp-/darwinasmparser/#a1a972ee6fe54b3bdbfbcf505162a75ea">anonymous{DarwinAsmParser.cpp}::DarwinAsmParser::parseBuildVersion</a>, <a href="/web-llvm/docs/api/classes/anonymous-webassemblyasmparser-cpp-/webassemblyasmparser/#a4009b2b10bf09c0de7daf3062a89d803">anonymous{WebAssemblyAsmParser.cpp}::WebAssemblyAsmParser::parseCatchList</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64isellowering-cpp/#a5d8593bb34f2d8b9e8b81d36a3a72e54">parseConstraintCode</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/x86/x86isellowering-cpp/#aa7916a0e32a89dd12645d0c3941b1485">parseConstraintCode</a>, <a href="/web-llvm/docs/api/namespaces/llvm/dwarf-linker/#a112b0124ddda89fd041dbdbc53016275">llvm::dwarf_linker::parseDebugTableName</a>, <a href="/web-llvm/docs/api/classes/anonymous-amdgpuasmparser-cpp-/amdgpuasmparser/#aac5924990c1b6a01f79b3dd8019f5f7b">anonymous{AMDGPUAsmParser.cpp}::AMDGPUAsmParser::parseDelay</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a078e5029b1000e28c9b5a21179491b11">llvm::parseDenormalFPAttributeComponent</a>, <a href="/web-llvm/docs/api/classes/anonymous-darwinasmparser-cpp-/darwinasmparser/#ae246971cdc93908b9f10e7e7a829314c">anonymous{DarwinAsmParser.cpp}::DarwinAsmParser::parseDirectiveDataRegion</a>, <a href="/web-llvm/docs/api/classes/anonymous-darwinasmparser-cpp-/darwinasmparser/#a757668838f5767cbf28d9a5b1201a646">anonymous{DarwinAsmParser.cpp}::DarwinAsmParser::parseDirectiveSection</a>, <a href="/web-llvm/docs/api/classes/anonymous-wasmasmparser-cpp-/wasmasmparser/#adca7252d5d5b7cb17458ac9e482e8bde">anonymous{WasmAsmParser.cpp}::WasmAsmParser::ParseDirectiveSymbolAttribute</a>, <a href="/web-llvm/docs/api/classes/anonymous-elfasmparser-cpp-/elfasmparser/#ace33fcaf2869f1932feb764d96a621fa">anonymous{ELFAsmParser.cpp}::ELFAsmParser::parseDirectiveSymbolAttribute</a>, <a href="/web-llvm/docs/api/files/lib/lib/targetparser/triple-cpp/#a1d2990073fc241c3de22309696bf3314">parseEnvironment</a>, <a href="/web-llvm/docs/api/classes/llvm/macho/textapiwriter/#a9afb9c049d0f17fe4036dbe6654d4ea2">llvm::MachO::TextAPIWriter::parseFileType</a>, <a href="/web-llvm/docs/api/namespaces/llvm/remarks/#a6c80295c5037fd265a600ae769440d39">llvm::remarks::parseFormat</a>, <a href="/web-llvm/docs/api/files/lib/lib/targetparser/triple-cpp/#acd920d1fcd9dc528687e8ab0df027fdd">parseFormat</a>, <a href="/web-llvm/docs/api/classes/anonymous-aarch64asmparser-cpp-/aarch64asmparser/#adc0358b42d36242d132980b3fe8260de">anonymous{AArch64AsmParser.cpp}::AArch64AsmParser::parseInstruction</a>, <a href="/web-llvm/docs/api/classes/anonymous-x86asmparser-cpp-/x86asmparser/#abf6230cdb8093ea54524821d036b2203">anonymous{X86AsmParser.cpp}::X86AsmParser::parseInstruction</a>, <a href="/web-llvm/docs/api/classes/anonymous-amdgpuasmparser-cpp-/amdgpuasmparser/#a5c3abd5a0df4ec19738884622846a92b">anonymous{AMDGPUAsmParser.cpp}::AMDGPUAsmParser::parseInterpAttr</a>, <a href="/web-llvm/docs/api/classes/anonymous-amdgpuasmparser-cpp-/amdgpuasmparser/#abc5a32fe7c02fdcfc1484e926e376ce0">anonymous{AMDGPUAsmParser.cpp}::AMDGPUAsmParser::parseInterpSlot</a>, <a href="/web-llvm/docs/api/structs/anonymous-amdgpulibfunc-cpp-/itaniumparamparser/#aa21569cfdba76deadeb40added273001">anonymous{AMDGPULibFunc.cpp}::ItaniumParamParser::parseItaniumParam</a>, <a href="/web-llvm/docs/api/namespaces/llvm/webassembly/#ad633bade17028bdef34a0637c012eeb2">llvm::WebAssembly::parseMVT</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/amdgpulibfunc-cpp/#a56ec8af379a8cf1ff76e2171f0bbbbb3">parseNamePrefix</a>, <a href="/web-llvm/docs/api/classes/anonymous-miparser-cpp-/miparser/#a7eb95d6aa8ae9f89008ea38203b6e894">anonymous{MIParser.cpp}::MIParser::parseOptionalAtomicOrdering</a>, <a href="/web-llvm/docs/api/files/lib/lib/passes/passbuilder-cpp/#a9e4f6112c778d883860155c39c4d3594">parseOptLevel</a>, <a href="/web-llvm/docs/api/files/lib/lib/targetparser/triple-cpp/#a96f0a5c666b924f50da56dede8092ae7">parseOS</a>, <a href="/web-llvm/docs/api/namespaces/llvm/dxbc/#a22967e47fc32d184579dc8442b979a4b">llvm::dxbc::parsePartType</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64isellowering-cpp/#a0b1d72a2f4241daf5c6036547f4bbbf0">parsePredicateConstraint</a>, <a href="/web-llvm/docs/api/classes/anonymous-miparser-cpp-/miparser/#a4590f4e05f484028f3b4bf3387955427">anonymous{MIParser.cpp}::MIParser::parsePredicateOperand</a>, <a href="/web-llvm/docs/api/classes/anonymous-amdgpuasmparser-cpp-/amdgpuasmparser/#ab65e752ef8a4ee9e6df01039bfa00b0e">anonymous{AMDGPUAsmParser.cpp}::AMDGPUAsmParser::parsePrimaryExpr</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64isellowering-cpp/#aa07f7f9a7abdfccd15bb1e2c9be4edc7">parseReducedGprConstraint</a>, <a href="/web-llvm/docs/api/classes/anonymous-wasmasmparser-cpp-/wasmasmparser/#ae0649c94bd0699e12841f9abe89b3548">anonymous{WasmAsmParser.cpp}::WasmAsmParser::parseSectionDirective</a>, <a href="/web-llvm/docs/api/files/lib/lib/targetparser/triple-cpp/#ac784253baaaa3c7ac2760f3d9b71f1c1">parseSubArch</a>, <a href="/web-llvm/docs/api/classes/anonymous-amdgpuasmparser-cpp-/amdgpuasmparser/#a3a4cad862e9d4dda82fe89b5a2557e97">anonymous{AMDGPUAsmParser.cpp}::AMDGPUAsmParser::parseTH</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64slshardening-cpp/#a407041f5d2ea26309c1f9071a724314e">parseThunkName</a>, <a href="/web-llvm/docs/api/namespaces/llvm/riscv/#af23b1af03352d87263aad79e5700fe79">llvm::RISCV::parseTuneCPU</a>, <a href="/web-llvm/docs/api/structs/llvm/remarks/yamlremarkparser/#afe5f8ff50f8bc8d22acbe211ed9e19df">llvm::remarks::YAMLRemarkParser::parseType</a>, <a href="/web-llvm/docs/api/namespaces/llvm/webassembly/#ae55eace303da656ab895760ed2f6da26">llvm::WebAssembly::parseType</a>, <a href="/web-llvm/docs/api/classes/llvm/sparcmcexpr/#a8f8493d80b8e10f21a7d4ea16ac003ea">llvm::SparcMCExpr::parseVariantKind</a>, <a href="/web-llvm/docs/api/classes/llvm/vemcexpr/#a34980fe75ddfddc6b82e729a114d63ee">llvm::VEMCExpr::parseVariantKind</a>, <a href="/web-llvm/docs/api/files/lib/lib/targetparser/triple-cpp/#af928c309977e80665cdc60d0b9c46d89">parseVendor</a>, <a href="/web-llvm/docs/api/classes/llvm/symbolremappingreader/#a6b15e282ce11e66f93f7b1a22407547b">llvm::SymbolRemappingReader::read</a>, <a href="/web-llvm/docs/api/files/lib/lib/ir/autoupgrade-cpp/#a3cdb051e7b4490b330de172bbdecbf18">shouldUpgradeNVPTXBF16Intrinsic</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/lanai/lib/target/lanai/asmparser/lanaiasmparser-cpp/#a03d61e95bb079ccf1aad303ac9e6fb93">SizeForSuffix</a>, <a href="/web-llvm/docs/api/namespaces/llvm/lpac/#a82e423fdc73ec257d71d9881ca6744e8">llvm::LPAC::stringToLanaiAluCode</a>, <a href="/web-llvm/docs/api/namespaces/llvm/riscvfprndmode/#a572415830c007d4e57c1733fdc7007a8">llvm::RISCVFPRndMode::stringToRoundingMode</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a75573c9f0abf07d17e3cd1c8eaf3311b">llvm::stringToVEFCondCode</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#af535846bcbb6c6df0b0a3a81b51bcbf4">llvm::stringToVEICondCode</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#ae6f47e902e2365c054ea9388993ec497">llvm::stringToVERD</a>, <a href="/web-llvm/docs/api/namespaces/llvm/lpcc/#a444b7661fff6a2bcb99552d068bb3aca">llvm::LPCC::suffixToLanaiCondCode</a>, <a href="/web-llvm/docs/api/classes/llvm/triple/#a5795a74557bb339afa955660ecb76247">llvm::Triple::Triple</a>, <a href="/web-llvm/docs/api/namespaces/anonymous-vfabidemangler-cpp-/#a1e256b3e261a7e37851be3f91173e6c0">anonymous{VFABIDemangler.cpp}::tryParseISA</a>, <a href="/web-llvm/docs/api/files/lib/lib/ir/autoupgrade-cpp/#a4ce4b835cffc5fa4123fe82f5f39cf97">upgradeAArch64IntrinsicCall</a>, <a href="/web-llvm/docs/api/files/lib/lib/ir/autoupgrade-cpp/#aabed4dadfe0a32d2cc856553788212ba">upgradeArmOrAarch64IntrinsicFunction</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a085e92ed481e12744fdf1740b4751327">llvm::UpgradeIntrinsicCall</a>, <a href="/web-llvm/docs/api/files/lib/lib/ir/autoupgrade-cpp/#a0e3d706240976157dfd3542311dc48cb">upgradeIntrinsicFunction1</a> and <a href="/web-llvm/docs/api/files/lib/lib/ir/autoupgrade-cpp/#a634253063317c2a283da15093157baae">upgradeX86IntrinsicFunction</a>.</p>

</div>
</div>

### EndsWith() {#aa50a7b1fb270f50ee5fe0db126b9f75f}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<div class="doxyMemberTemplate">template &lt;typename T, typename R = T&gt;</div>
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">StringSwitch &amp; llvm::StringSwitch&lt; T, R &gt;::EndsWith (<a href="/web-llvm/docs/api/classes/llvm/stringliteral">StringLiteral</a> S, T Value)</td>
</tr>
</table>
</td>
<td class="doxyMemberLabelsRight">
<span class="doxyMemberLabels">
<span class="doxyMemberLabel inline">inline</span>
</span>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 76 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/adt/stringswitch-h">StringSwitch.h</a>.</p>


<p>References <a href="#acb567c28ed2b00f93894c700dab8faea">llvm::StringSwitch&lt; T, R &gt;::StringSwitch</a> and <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/mips/mips16isellowering-cpp/#a0acb682b8260ab1c60b918599864e2e5">T</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/namespaces/llvm/#a5c9c060a884e9461f06d7601681d2bcf">llvm::generateKernelClockInst</a>, <a href="/web-llvm/docs/api/files/lib/lib/targetparser/triple-cpp/#acd920d1fcd9dc528687e8ab0df027fdd">parseFormat</a>, <a href="/web-llvm/docs/api/files/lib/lib/targetparser/triple-cpp/#ac784253baaaa3c7ac2760f3d9b71f1c1">parseSubArch</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/lanai/lib/target/lanai/asmparser/lanaiasmparser-cpp/#a03d61e95bb079ccf1aad303ac9e6fb93">SizeForSuffix</a> and <a href="/web-llvm/docs/api/namespaces/llvm/lpcc/#a444b7661fff6a2bcb99552d068bb3aca">llvm::LPCC::suffixToLanaiCondCode</a>.</p>

</div>
</div>

### EndsWithLower() {#a26f67aa26109e982724285750a39fdb9}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<div class="doxyMemberTemplate">template &lt;typename T, typename R = T&gt;</div>
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">StringSwitch &amp; llvm::StringSwitch&lt; T, R &gt;::EndsWithLower (<a href="/web-llvm/docs/api/classes/llvm/stringliteral">StringLiteral</a> S, T Value)</td>
</tr>
</table>
</td>
<td class="doxyMemberLabelsRight">
<span class="doxyMemberLabels">
<span class="doxyMemberLabel inline">inline</span>
</span>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 149 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/adt/stringswitch-h">StringSwitch.h</a>.</p>


<p>References <a href="#acb567c28ed2b00f93894c700dab8faea">llvm::StringSwitch&lt; T, R &gt;::StringSwitch</a> and <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/mips/mips16isellowering-cpp/#a0acb682b8260ab1c60b918599864e2e5">T</a>.</p>

</div>
</div>

### StartsWith() {#a88e653a89d15149cc7a68f88be360303}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<div class="doxyMemberTemplate">template &lt;typename T, typename R = T&gt;</div>
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">StringSwitch &amp; llvm::StringSwitch&lt; T, R &gt;::StartsWith (<a href="/web-llvm/docs/api/classes/llvm/stringliteral">StringLiteral</a> S, T Value)</td>
</tr>
</table>
</td>
<td class="doxyMemberLabelsRight">
<span class="doxyMemberLabels">
<span class="doxyMemberLabel inline">inline</span>
</span>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 83 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/adt/stringswitch-h">StringSwitch.h</a>.</p>


<p>References <a href="#acb567c28ed2b00f93894c700dab8faea">llvm::StringSwitch&lt; T, R &gt;::StringSwitch</a> and <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/mips/mips16isellowering-cpp/#a0acb682b8260ab1c60b918599864e2e5">T</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/namespaces/llvm/elf/#af629e6836e2820856a0e811938ddf8af">llvm::ELF::convertNameToOSABI</a>, <a href="/web-llvm/docs/api/classes/llvm/triple/#a5d5efe3bb966ce825560b2e6dd46f8ec">llvm::Triple::getArchTypeForLLVMName</a>, <a href="/web-llvm/docs/api/namespaces/llvm/remarks/#a33db5e22d2f3b0403b2fcd906f5a2377">llvm::remarks::magicToFormat</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/lanai/lib/target/lanai/asmparser/lanaiasmparser-cpp/#aa381725d28ae64fbe2941e262ad59353">MaybePredicatedInst</a>, <a href="/web-llvm/docs/api/files/lib/lib/targetparser/triple-cpp/#ad3a9a5aa955e9b62ec11e4d3566d4594">parseArch</a>, <a href="/web-llvm/docs/api/namespaces/llvm/arm/#a1d5ed0bfc1c21767207fbd9c06aa68e9">llvm::ARM::parseArchISA</a>, <a href="/web-llvm/docs/api/files/lib/lib/targetparser/triple-cpp/#a1d2990073fc241c3de22309696bf3314">parseEnvironment</a>, <a href="/web-llvm/docs/api/structs/anonymous-amdgpulibfunc-cpp-/itaniumparamparser/#aa21569cfdba76deadeb40added273001">anonymous{AMDGPULibFunc.cpp}::ItaniumParamParser::parseItaniumParam</a>, <a href="/web-llvm/docs/api/files/lib/lib/targetparser/triple-cpp/#a96f0a5c666b924f50da56dede8092ae7">parseOS</a>, <a href="/web-llvm/docs/api/classes/anonymous-wasmasmparser-cpp-/wasmasmparser/#ae0649c94bd0699e12841f9abe89b3548">anonymous{WasmAsmParser.cpp}::WasmAsmParser::parseSectionDirective</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64slshardening-cpp/#a407041f5d2ea26309c1f9071a724314e">parseThunkName</a>, <a href="/web-llvm/docs/api/classes/llvm/triple/#a5795a74557bb339afa955660ecb76247">llvm::Triple::Triple</a>, <a href="/web-llvm/docs/api/files/lib/lib/ir/autoupgrade-cpp/#a9d9ad1173db1cee0c288f1b773baaf65">upgradeAMDGCNIntrinsicCall</a>, <a href="/web-llvm/docs/api/files/lib/lib/ir/autoupgrade-cpp/#aabed4dadfe0a32d2cc856553788212ba">upgradeArmOrAarch64IntrinsicFunction</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a085e92ed481e12744fdf1740b4751327">llvm::UpgradeIntrinsicCall</a> and <a href="/web-llvm/docs/api/files/lib/lib/ir/autoupgrade-cpp/#a0e3d706240976157dfd3542311dc48cb">upgradeIntrinsicFunction1</a>.</p>

</div>
</div>

### StartsWithLower() {#a2a3f855f53939cc944792516f0fc8205}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<div class="doxyMemberTemplate">template &lt;typename T, typename R = T&gt;</div>
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">StringSwitch &amp; llvm::StringSwitch&lt; T, R &gt;::StartsWithLower (<a href="/web-llvm/docs/api/classes/llvm/stringliteral">StringLiteral</a> S, T Value)</td>
</tr>
</table>
</td>
<td class="doxyMemberLabelsRight">
<span class="doxyMemberLabels">
<span class="doxyMemberLabel inline">inline</span>
</span>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 156 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/adt/stringswitch-h">StringSwitch.h</a>.</p>


<p>References <a href="#acb567c28ed2b00f93894c700dab8faea">llvm::StringSwitch&lt; T, R &gt;::StringSwitch</a> and <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/mips/mips16isellowering-cpp/#a0acb682b8260ab1c60b918599864e2e5">T</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Private Member Attributes

### Result {#a36c9f94454740495463dce83f3e476af}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<div class="doxyMemberTemplate">template &lt;typename T, typename R = T&gt;</div>
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">std::optional&lt;T&gt; llvm::StringSwitch&lt; T, R &gt;::Result</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>The pointer to the result of this switch statement, once known, null before that.</p>

<p>Definition at line 50 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/adt/stringswitch-h">StringSwitch.h</a>.</p>

</div>
</div>

### Str {#a408da1a7112ce48825d569248f451a93}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<div class="doxyMemberTemplate">template &lt;typename T, typename R = T&gt;</div>
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">const StringRef llvm::StringSwitch&lt; T, R &gt;::Str</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>The string we are matching.</p>

<p>Definition at line 46 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/adt/stringswitch-h">StringSwitch.h</a>.</p>

</div>
</div>

</div>

<hr/>

The documentation for this class was generated from the following file:

<ul>
<li><a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/adt/stringswitch-h">StringSwitch.h</a></li>
</ul>

<hr/>

<p class="doxyGeneratedBy">Generated via <a href="https://github.com/xpack/doxygen2docusaurus">doxygen2docusaurus</a> by <a href="https://www.doxygen.nl">Doxygen</a> 1.15.0.</p>

</div>
