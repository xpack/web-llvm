---

# DO NOT EDIT!
# Automatically generated via doxygen2docusaurus by Doxygen.

slug: /api/classes/llvm/opt/arglist
custom_edit_url: null
toc_max_heading_level: 4
keywords:
  - doxygen
  - reference
  - class

---

<div class="doxyPage">

# `ArgList` Class

<p><a href="/web-llvm/docs/api/classes/llvm/opt/arglist">ArgList</a> - Ordered collection of driver arguments. <a href="#details">More...</a></p>

## Declaration

<div class="doxyDeclaration">
class llvm::opt::ArgList { ... }
</div>

## Included Headers

<div class="doxyIncludesList">#include "<a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/option/arglist-h">llvm/Option/ArgList.h</a>"
</div>

## Derived Classes

<table class="doxyMembersIndex">

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">class</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/opt/derivedarglist">DerivedArgList</a></td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p><a href="/web-llvm/docs/api/classes/llvm/opt/derivedarglist">DerivedArgList</a> - An ordered collection of driver arguments, whose storage may be in another argument list. <a href="/web-llvm/docs/api/classes/llvm/opt/derivedarglist/#details">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">class</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/opt/inputarglist">InputArgList</a></td>
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

## Public Member Typedefs Index

<table class="doxyMembersIndex">

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">using</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#affc380c02ba7b4abe2cea6db269ed28a">arglist_type</a> = <a href="/web-llvm/docs/api/classes/llvm/smallvector">SmallVector</a>&lt; <a href="/web-llvm/docs/api/classes/llvm/opt/arg">Arg</a> *, 16 &gt;</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">using</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ad5ab77aa3a8722f53010130cb15e4ad3">iterator</a> = <a href="/web-llvm/docs/api/classes/llvm/opt/arg-iterator">arg_iterator</a>&lt; <a href="/web-llvm/docs/api/classes/llvm/smallvectortemplatecommon/#a9eae7ba1448d9866beca95a042de2e11">arglist_type::iterator</a> &gt;</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">using</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a5c8d76179703eb68330dffcf5d2f9cec">const_iterator</a> = <a href="/web-llvm/docs/api/classes/llvm/opt/arg-iterator">arg_iterator</a>&lt; <a href="/web-llvm/docs/api/classes/llvm/smallvectortemplatecommon/#aa11b903431c1931920939bac6b5293a2">arglist_type::const_iterator</a> &gt;</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">using</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ac502e306b860474bf8a6bf7f12fafd75">reverse_iterator</a> = <a href="/web-llvm/docs/api/classes/llvm/opt/arg-iterator">arg_iterator</a>&lt; <a href="/web-llvm/docs/api/classes/llvm/smallvectortemplatecommon/#af6a3df9bf4da2b9af52a9ad973e6f30c">arglist_type::reverse_iterator</a> &gt;</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">using</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a84c30c0179d86c3cd82f0a05c21dbf2d">const_reverse_iterator</a> = <a href="/web-llvm/docs/api/classes/llvm/opt/arg-iterator">arg_iterator</a>&lt; <a href="/web-llvm/docs/api/classes/llvm/smallvectortemplatecommon/#a739c383b97286396ce969b521da2f642">arglist_type::const_reverse_iterator</a> &gt;</td>
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
<td class="doxyMemberIndexTemplate" colspan="2"><div>template &lt;unsigned N&gt;</div></td>
</tr>
<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemTypeTemplate" align="left" valign="top">using</td>
<td class="doxyMemberIndexItemNameTemplate" align="left" valign="top"><a href="#a6332b7ab4b3af2eb746f4f0b4ec9b228">filtered_iterator</a> = <a href="/web-llvm/docs/api/classes/llvm/opt/arg-iterator">arg_iterator</a>&lt; <a href="/web-llvm/docs/api/classes/llvm/smallvectortemplatecommon/#aa11b903431c1931920939bac6b5293a2">arglist_type::const_iterator</a>, <a href="/web-llvm/docs/api/files/lib/lib/support/regcomp-c/#a0240ac851181b84ac374872dc5434ee4">N</a> &gt;</td>
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
<td class="doxyMemberIndexTemplate" colspan="2"><div>template &lt;unsigned N&gt;</div></td>
</tr>
<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemTypeTemplate" align="left" valign="top">using</td>
<td class="doxyMemberIndexItemNameTemplate" align="left" valign="top"><a href="#a22d9aa30cd5a897f8080e561ad0cd98b">filtered_reverse_iterator</a> = <a href="/web-llvm/docs/api/classes/llvm/opt/arg-iterator">arg_iterator</a>&lt; <a href="/web-llvm/docs/api/classes/llvm/smallvectortemplatecommon/#a739c383b97286396ce969b521da2f642">arglist_type::const_reverse_iterator</a>, <a href="/web-llvm/docs/api/files/lib/lib/support/regcomp-c/#a0240ac851181b84ac374872dc5434ee4">N</a> &gt;</td>
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

## Private Member Typedefs Index

<table class="doxyMembersIndex">

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">using</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a2a107a1407746b2d0523d2fe6d564531">OptRange</a> = std::pair&lt; unsigned, unsigned &gt;</td>
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

## Protected Constructors Index

<table class="doxyMembersIndex">

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a65954e42e1dd42746f957601cf6216ce">ArgList</a> ()=default</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#aeee4cc311a0bc487121e23eade53d181">ArgList</a> (ArgList &amp;&amp;RHS)</td>
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

## Protected Destructor Index

<table class="doxyMembersIndex">

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a9de9a8cffc90295f9faf95cf311b04a5">~ArgList</a> ()=default</td>
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

## Protected Operators Index

<table class="doxyMembersIndex">

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/opt/arglist">ArgList</a> &amp;</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#aed839d60eca856865ca21558724a049a">operator=</a> (ArgList &amp;&amp;RHS)</td>
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

## Private Member Functions Index

<table class="doxyMembersIndex">

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">OptRange</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ae1cfe50b29accbb5d637efaeedaa59d0">getRange</a> (std::initializer_list&lt; OptSpecifier &gt; Ids) const</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Get the range of indexes in which options with the specified IDs might reside, or (0, 0) if there are no such options. <a href="#ae1cfe50b29accbb5d637efaeedaa59d0">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

</table>

## Private Member Attributes Index

<table class="doxyMembersIndex">

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="#affc380c02ba7b4abe2cea6db269ed28a">arglist_type</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a70aa569fc72f042e1729ddfa3202c074">Args</a></td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>The internal list of arguments. <a href="#a70aa569fc72f042e1729ddfa3202c074">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/densemap">DenseMap</a>&lt; unsigned, OptRange &gt;</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a2d4ba15c22c2d13f82110d1bbd40afec">OptRanges</a></td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>The first and last index of each different <a href="/web-llvm/docs/api/classes/llvm/opt/optspecifier">OptSpecifier</a> <a href="/web-llvm/docs/api/namespaces/llvm/callingconv/#abdf8cf606905c10634e831390981b0ed">ID</a>. <a href="#a2d4ba15c22c2d13f82110d1bbd40afec">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

</table>

## Protected Static Functions Index

<table class="doxyMembersIndex">

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">static <a href="/web-llvm/docs/api/classes/llvm/opt/optspecifier">OptSpecifier</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a593b9ff9bea9354163be70de429075ec">toOptSpecifier</a> (OptSpecifier S)</td>
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

## Private Static Functions Index

<table class="doxyMembersIndex">

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">static OptRange</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#aaf8eb75d9a8201cdd2984d2d07c65586">emptyRange</a> ()</td>
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

## Arg Access Index

<table class="doxyMembersIndex">

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">void</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a862d6016ee6bbfb979acf4739b4fcfac">append</a> (Arg *A)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>append - Append <span class="doxyComputerOutput">A</span> to the arg list. <a href="#a862d6016ee6bbfb979acf4739b4fcfac">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="#affc380c02ba7b4abe2cea6db269ed28a">arglist_type</a> &amp;</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a88c8665b3056d0730186572e8494f365">getArgs</a> () const</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">unsigned</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a5466418a7db1f20f39ad71346f22bdf7">size</a> () const</td>
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
<td class="doxyMemberIndexTemplate" colspan="2"><div>template &lt;typename ... OptSpecifiers&gt;</div></td>
</tr>
<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemTypeTemplate" align="left" valign="top">bool</td>
<td class="doxyMemberIndexItemNameTemplate" align="left" valign="top"><a href="#a73c250aad85229fe689e98dc66c6fb44">hasArgNoClaim</a> (OptSpecifiers ...Ids) const</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>hasArg - Does the arg list contain any option matching <span class="doxyComputerOutput">Id</span>. <a href="#a73c250aad85229fe689e98dc66c6fb44">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexTemplate">
<td class="doxyMemberIndexTemplate" colspan="2"><div>template &lt;typename ... OptSpecifiers&gt;</div></td>
</tr>
<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemTypeTemplate" align="left" valign="top">bool</td>
<td class="doxyMemberIndexItemNameTemplate" align="left" valign="top"><a href="#adacbd83ff3d0127e8862bdf6a0051572">hasArg</a> (OptSpecifiers ...Ids) const</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">bool</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a61b0d09d8e01eae52ed4e4ff3bb966d8">hasMultipleArgs</a> (OptSpecifier Id) const</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Return true if the arg list contains multiple arguments matching <span class="doxyComputerOutput">Id</span>. <a href="#a61b0d09d8e01eae52ed4e4ff3bb966d8">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexTemplate">
<td class="doxyMemberIndexTemplate" colspan="2"><div>template &lt;typename ... OptSpecifiers&gt;</div></td>
</tr>
<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemTypeTemplate" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/opt/arg">Arg</a> *</td>
<td class="doxyMemberIndexItemNameTemplate" align="left" valign="top"><a href="#aa7b3f568748cb5a0cab744337ae3eb52">getLastArg</a> (OptSpecifiers ...Ids) const</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Return the last argument matching <span class="doxyComputerOutput">Id</span>, or null. <a href="#aa7b3f568748cb5a0cab744337ae3eb52">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexTemplate">
<td class="doxyMemberIndexTemplate" colspan="2"><div>template &lt;typename ... OptSpecifiers&gt;</div></td>
</tr>
<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemTypeTemplate" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/opt/arg">Arg</a> *</td>
<td class="doxyMemberIndexItemNameTemplate" align="left" valign="top"><a href="#a3102b968dbf681bb7353e02eba411a11">getLastArgNoClaim</a> (OptSpecifiers ...Ids) const</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Return the last argument matching <span class="doxyComputerOutput">Id</span>, or null. <a href="#a3102b968dbf681bb7353e02eba411a11">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> char *</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a238654e81bd5a66aa111a4cbf898c165">getArgString</a> (unsigned Index) const =0</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>getArgString - Return the input argument string at <span class="doxyComputerOutput">Index</span>. <a href="#a238654e81bd5a66aa111a4cbf898c165">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">unsigned</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a2d204f9d95d54ae0427f37f73dab16db">getNumInputArgStrings</a> () const =0</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>getNumInputArgStrings - Return the number of original argument strings, which are guaranteed to be the first strings in the argument string list. <a href="#a2d204f9d95d54ae0427f37f73dab16db">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

</table>

## Arg Iteration Index

<table class="doxyMembersIndex">

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="#ad5ab77aa3a8722f53010130cb15e4ad3">iterator</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a820dba330c8ce4cf86cd2bae4d1ef509">begin</a> ()</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="#ad5ab77aa3a8722f53010130cb15e4ad3">iterator</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ae1d7be319add714458290b0251602b4a">end</a> ()</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="#ac502e306b860474bf8a6bf7f12fafd75">reverse_iterator</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#aa367fe2f66ef3f505946b6bf9beec0c3">rbegin</a> ()</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="#ac502e306b860474bf8a6bf7f12fafd75">reverse_iterator</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ab7464b01e58453e55bbb26521e50dd65">rend</a> ()</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="#a5c8d76179703eb68330dffcf5d2f9cec">const_iterator</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a97ff5248de01159460962ee3db81ee37">begin</a> () const</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="#a5c8d76179703eb68330dffcf5d2f9cec">const_iterator</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a5b1c259d095ece5b305b73226bad0bf6">end</a> () const</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="#a84c30c0179d86c3cd82f0a05c21dbf2d">const_reverse_iterator</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a9a3314fc0453555bb2cc3aea75b02ea6">rbegin</a> () const</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="#a84c30c0179d86c3cd82f0a05c21dbf2d">const_reverse_iterator</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a7210cd8ea9a9e820e62cdefe20981524">rend</a> () const</td>
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
<td class="doxyMemberIndexTemplate" colspan="2"><div>template &lt;typename ... OptSpecifiers&gt;</div></td>
</tr>
<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemTypeTemplate" align="left" valign="top">auto </td>
<td class="doxyMemberIndexItemNameTemplate" align="left" valign="top"><a href="#ae6005f6bafe8396d40dc173831c6bdba">filtered</a> (OptSpecifiers ...Ids) const -&gt; <a href="/web-llvm/docs/api/classes/llvm/iterator-range">iterator_range</a>&lt; <a href="#a6332b7ab4b3af2eb746f4f0b4ec9b228">filtered_iterator</a>&lt; sizeof...(OptSpecifiers)&gt; &gt;</td>
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
<td class="doxyMemberIndexTemplate" colspan="2"><div>template &lt;typename ... OptSpecifiers&gt;</div></td>
</tr>
<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemTypeTemplate" align="left" valign="top">auto </td>
<td class="doxyMemberIndexItemNameTemplate" align="left" valign="top"><a href="#a5f5ba4a58ba957ffc2e173ea9cfb4834">filtered_reverse</a> (OptSpecifiers ...Ids) const -&gt; <a href="/web-llvm/docs/api/classes/llvm/iterator-range">iterator_range</a>&lt; <a href="#a22d9aa30cd5a897f8080e561ad0cd98b">filtered_reverse_iterator</a>&lt; sizeof...(OptSpecifiers)&gt; &gt;</td>
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

## Arg Removal Index

<table class="doxyMembersIndex">

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">void</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a156189fac43bbb6cb89af54b0a72ebca">eraseArg</a> (OptSpecifier Id)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>eraseArg - Remove any option matching <span class="doxyComputerOutput">Id</span>. <a href="#a156189fac43bbb6cb89af54b0a72ebca">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

</table>

## Argument Lookup Utilities Index

<table class="doxyMembersIndex">

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/stringref">StringRef</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#adc31a5f33c24a36189f865c605247c68">getLastArgValue</a> (OptSpecifier Id, StringRef Default="") const</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>getLastArgValue - Return the value of the last argument, or a default. <a href="#adc31a5f33c24a36189f865c605247c68">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">std::vector&lt; std::string &gt;</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ace2ec29a8f2231556c7f8a20929cc138">getAllArgValues</a> (OptSpecifier Id) const</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>getAllArgValues - Get the values of all instances of the given argument as strings. <a href="#ace2ec29a8f2231556c7f8a20929cc138">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

</table>

## Translation Utilities Index

<table class="doxyMembersIndex">

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">bool</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#af4ede33e90efaf90c6534f43b3cfbffc">hasFlag</a> (OptSpecifier Pos, OptSpecifier Neg, bool Default) const</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>hasFlag - Given an option <span class="doxyComputerOutput">Pos</span> and its negative form <span class="doxyComputerOutput">Neg</span>, return true if the option is present, false if the negation is present, and <span class="doxyComputerOutput">Default</span> if neither option is given. <a href="#af4ede33e90efaf90c6534f43b3cfbffc">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">bool</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a4a6d454c010b5cdcae7d8990ae44d0a5">hasFlagNoClaim</a> (OptSpecifier Pos, OptSpecifier Neg, bool Default) const</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">bool</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#af5d90967a9f37775b3b18b46b846316b">hasFlag</a> (OptSpecifier Pos, OptSpecifier PosAlias, OptSpecifier Neg, bool Default) const</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>hasFlag - Given an option <span class="doxyComputerOutput">Pos</span>, an alias <span class="doxyComputerOutput">PosAlias</span> and its negative form <span class="doxyComputerOutput">Neg</span>, return true if the option or its alias is present, false if the negation is present, and <span class="doxyComputerOutput">Default</span> if none of the options are given. <a href="#af5d90967a9f37775b3b18b46b846316b">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">void</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a342aaf3c2d86a3defc7baf1549143997">addOptInFlag</a> (ArgStringList &amp;Output, OptSpecifier Pos, OptSpecifier Neg) const</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Given an option Pos and its negative form Neg, render the option if Pos is present. <a href="#a342aaf3c2d86a3defc7baf1549143997">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">void</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ad270693324724209b55d264ede75f640">addOptOutFlag</a> (ArgStringList &amp;Output, OptSpecifier Pos, OptSpecifier Neg) const</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Render the option if Neg is present. <a href="#ad270693324724209b55d264ede75f640">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexTemplate">
<td class="doxyMemberIndexTemplate" colspan="2"><div>template &lt;typename... OptSpecifiers&gt;</div></td>
</tr>
<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemTypeTemplate" align="left" valign="top">void</td>
<td class="doxyMemberIndexItemNameTemplate" align="left" valign="top"><a href="#a872650762e7195e1e9e7d10cf670c894">addLastArg</a> (ArgStringList &amp;Output, OptSpecifiers... Ids) const</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Render only the last argument match <span class="doxyComputerOutput">Id0</span>, if present. <a href="#a872650762e7195e1e9e7d10cf670c894">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexTemplate">
<td class="doxyMemberIndexTemplate" colspan="2"><div>template &lt;typename... OptSpecifiers&gt;</div></td>
</tr>
<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemTypeTemplate" align="left" valign="top">void</td>
<td class="doxyMemberIndexItemNameTemplate" align="left" valign="top"><a href="#a7a0ac31f20ed170cac107e0d4c8c6f24">AddLastArg</a> (ArgStringList &amp;Output, OptSpecifiers... Ids) const</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">void</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ab7ef568579e2fc175c4d3d68921a1a9b">AddAllArgsExcept</a> (ArgStringList &amp;Output, ArrayRef&lt; OptSpecifier &gt; Ids, ArrayRef&lt; OptSpecifier &gt; ExcludeIds) const</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>AddAllArgsExcept - Render all arguments matching any of the given ids and not matching any of the excluded ids. <a href="#ab7ef568579e2fc175c4d3d68921a1a9b">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">void</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a8a832028dff8abb97e1b9fec4987b13a">addAllArgs</a> (ArgStringList &amp;Output, ArrayRef&lt; OptSpecifier &gt; Ids) const</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Render all arguments matching any of the given ids. <a href="#a8a832028dff8abb97e1b9fec4987b13a">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">void</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a623040a06f67b95ab24c5e78e41c8bc8">AddAllArgs</a> (ArgStringList &amp;Output, OptSpecifier Id0) const</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>AddAllArgs - Render all arguments matching the given ids. <a href="#a623040a06f67b95ab24c5e78e41c8bc8">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">void</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a279c6ca725e36eff09469d98e6ee1988">AddAllArgValues</a> (ArgStringList &amp;Output, OptSpecifier Id0, OptSpecifier Id1=0U, OptSpecifier Id2=0U) const</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>AddAllArgValues - Render the argument values of all arguments matching the given ids. <a href="#a279c6ca725e36eff09469d98e6ee1988">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">void</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a58ecc4f607c39abaf338915a04a29922">AddAllArgsTranslated</a> (ArgStringList &amp;Output, OptSpecifier Id0, const char *Translation, bool Joined=false) const</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>AddAllArgsTranslated - Render all the arguments matching the given ids, but forced to separate args and using the provided name instead of the first option value. <a href="#a58ecc4f607c39abaf338915a04a29922">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">void</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a2598c7f3e2c4d6571d84bbcd8fdaf4a9">ClaimAllArgs</a> (OptSpecifier Id0) const</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>ClaimAllArgs - Claim all arguments which match the given option id. <a href="#a2598c7f3e2c4d6571d84bbcd8fdaf4a9">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexTemplate">
<td class="doxyMemberIndexTemplate" colspan="2"><div>template &lt;typename... OptSpecifiers&gt;</div></td>
</tr>
<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemTypeTemplate" align="left" valign="top">void</td>
<td class="doxyMemberIndexItemNameTemplate" align="left" valign="top"><a href="#ab2e8451c25cb69c040675e00ca747319">claimAllArgs</a> (OptSpecifiers... Ids) const</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">void</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a974b1537dd2bfc45684a63390f5a0c8a">ClaimAllArgs</a> () const</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>ClaimAllArgs - Claim all arguments. <a href="#a974b1537dd2bfc45684a63390f5a0c8a">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

</table>

## Arg Synthesis Index

<table class="doxyMembersIndex">

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> char *</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ae249e8d33e950ad1d388556c89a359a6">MakeArgStringRef</a> (StringRef Str) const =0</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Construct a constant string pointer whose lifetime will match that of the <a href="/web-llvm/docs/api/classes/llvm/opt/arglist">ArgList</a>. <a href="#ae249e8d33e950ad1d388556c89a359a6">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> char *</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a678763a7949f037831ab90dcea55a817">MakeArgString</a> (const Twine &amp;Str) const</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> char *</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a33efdfc01aaf654147da9f8c05f7706d">GetOrMakeJoinedArgString</a> (unsigned Index, StringRef LHS, StringRef RHS) const</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Create an arg string for (<span class="doxyComputerOutput">LHS</span> + <span class="doxyComputerOutput">RHS</span>), reusing the string at <span class="doxyComputerOutput">Index</span> if possible. <a href="#a33efdfc01aaf654147da9f8c05f7706d">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">void</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a3347586cae383098ab26e84292881ebf">print</a> (raw_ostream &amp;O) const</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">void</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ab5735777324ec9864032e2673b01d58c">dump</a> () const</td>
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

## Description {#details}

<p><a href="/web-llvm/docs/api/classes/llvm/opt/arglist">ArgList</a> - Ordered collection of driver arguments.</p>


<p>The <a href="/web-llvm/docs/api/classes/llvm/opt/arglist">ArgList</a> class manages a list of <a href="/web-llvm/docs/api/classes/llvm/opt/arg">Arg</a> instances as well as auxiliary data and convenience methods to allow Tools to quickly check for the presence of <a href="/web-llvm/docs/api/classes/llvm/opt/arg">Arg</a> instances for a particular <a href="/web-llvm/docs/api/classes/llvm/opt/option">Option</a> and to iterate over groups of arguments.</p>


<p>Definition at line 116 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/option/arglist-h">ArgList.h</a>.</p>


<div class="doxySectionDef">

## Public Member Typedefs

### arglist\_type {#affc380c02ba7b4abe2cea6db269ed28a}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">using llvm::opt::ArgList::arglist_type =  SmallVector&lt;Arg *, 16&gt;</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 118 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/option/arglist-h">ArgList.h</a>.</p>

</div>
</div>

### const\_iterator {#a5c8d76179703eb68330dffcf5d2f9cec}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">using llvm::opt::ArgList::const_iterator =  arg_iterator&lt;arglist_type::const_iterator&gt;</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 120 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/option/arglist-h">ArgList.h</a>.</p>

</div>
</div>

### const\_reverse\_iterator {#a84c30c0179d86c3cd82f0a05c21dbf2d}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">using llvm::opt::ArgList::const_reverse_iterator = 
      arg_iterator&lt;arglist_type::const_reverse_iterator&gt;</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 122 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/option/arglist-h">ArgList.h</a>.</p>

</div>
</div>

### filtered\_iterator {#a6332b7ab4b3af2eb746f4f0b4ec9b228}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<div class="doxyMemberTemplate">template &lt;unsigned N&gt;</div>
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">using llvm::opt::ArgList::filtered_iterator = 
      arg_iterator&lt;arglist_type::const_iterator, N&gt;</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 125 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/option/arglist-h">ArgList.h</a>.</p>

</div>
</div>

### filtered\_reverse\_iterator {#a22d9aa30cd5a897f8080e561ad0cd98b}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<div class="doxyMemberTemplate">template &lt;unsigned N&gt;</div>
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">using llvm::opt::ArgList::filtered_reverse_iterator = 
      arg_iterator&lt;arglist_type::const_reverse_iterator, N&gt;</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 127 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/option/arglist-h">ArgList.h</a>.</p>

</div>
</div>

### iterator {#ad5ab77aa3a8722f53010130cb15e4ad3}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">using llvm::opt::ArgList::iterator =  arg_iterator&lt;arglist_type::iterator&gt;</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 119 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/option/arglist-h">ArgList.h</a>.</p>

</div>
</div>

### reverse\_iterator {#ac502e306b860474bf8a6bf7f12fafd75}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">using llvm::opt::ArgList::reverse_iterator =  arg_iterator&lt;arglist_type::reverse_iterator&gt;</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 121 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/option/arglist-h">ArgList.h</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Private Member Typedefs

### OptRange {#a2a107a1407746b2d0523d2fe6d564531}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">using llvm::opt::ArgList::OptRange =  std::pair&lt;unsigned, unsigned&gt;</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 134 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/option/arglist-h">ArgList.h</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Protected Constructors

### ArgList() {#a65954e42e1dd42746f957601cf6216ce}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">llvm::opt::ArgList::ArgList ()</td>
</tr>
</table>
</td>
<td class="doxyMemberLabelsRight">
<span class="doxyMemberLabels">
<span class="doxyMemberLabel protected">protected</span>
<span class="doxyMemberLabel default">default</span>
</span>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 148 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/option/arglist-h">ArgList.h</a>.</p>


<p>Referenced by <a href="#aeee4cc311a0bc487121e23eade53d181">ArgList</a>, <a href="/web-llvm/docs/api/classes/llvm/opt/inputarglist/#a11aa9df74cf3bbbba5a80c7d1c41772f">llvm::opt::InputArgList::InputArgList</a> and <a href="#aed839d60eca856865ca21558724a049a">operator=</a>.</p>

</div>
</div>

### ArgList() {#aeee4cc311a0bc487121e23eade53d181}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">llvm::opt::ArgList::ArgList (<a href="/web-llvm/docs/api/classes/llvm/opt/arglist">ArgList</a> &amp;&amp; RHS)</td>
</tr>
</table>
</td>
<td class="doxyMemberLabelsRight">
<span class="doxyMemberLabels">
<span class="doxyMemberLabel inline">inline</span>
<span class="doxyMemberLabel protected">protected</span>
</span>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 155 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/option/arglist-h">ArgList.h</a>.</p>


<p>References <a href="#a65954e42e1dd42746f957601cf6216ce">ArgList</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#abfc9c7ecf70f66901e439f7c04ef3dbb">llvm::move</a> and <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/x86/x86partialreduction-cpp/#a87b8bfbbe9d8f7146d7f20a5fb42efd0">RHS</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Protected Destructor

### \~ArgList() {#a9de9a8cffc90295f9faf95cf311b04a5}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">llvm::opt::ArgList::~ArgList ()</td>
</tr>
</table>
</td>
<td class="doxyMemberLabelsRight">
<span class="doxyMemberLabels">
<span class="doxyMemberLabel protected">protected</span>
<span class="doxyMemberLabel default">default</span>
</span>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 170 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/option/arglist-h">ArgList.h</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Protected Operators

### operator=() {#aed839d60eca856865ca21558724a049a}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">ArgList &amp; llvm::opt::ArgList::operator= (<a href="/web-llvm/docs/api/classes/llvm/opt/arglist">ArgList</a> &amp;&amp; RHS)</td>
</tr>
</table>
</td>
<td class="doxyMemberLabelsRight">
<span class="doxyMemberLabels">
<span class="doxyMemberLabel inline">inline</span>
<span class="doxyMemberLabel protected">protected</span>
</span>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 161 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/option/arglist-h">ArgList.h</a>.</p>


<p>References <a href="#a65954e42e1dd42746f957601cf6216ce">ArgList</a> and <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/x86/x86partialreduction-cpp/#a87b8bfbbe9d8f7146d7f20a5fb42efd0">RHS</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/classes/llvm/opt/inputarglist/#a4c39639d3f62e4d9641f63346064b61e">llvm::opt::InputArgList::operator=</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Private Member Functions

### getRange() {#ae1cfe50b29accbb5d637efaeedaa59d0}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">ArgList::OptRange ArgList::getRange (std::initializer_list&lt; <a href="/web-llvm/docs/api/classes/llvm/opt/optspecifier">OptSpecifier</a> &gt; Ids)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Get the range of indexes in which options with the specified IDs might reside, or (0, 0) if there are no such options.</p>

<p>Declaration at line 142 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/option/arglist-h">ArgList.h</a>, definition at line 57 of file <a href="/web-llvm/docs/api/files/lib/lib/option/arglist-cpp">ArgList.cpp</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Private Member Attributes

### Args {#a70aa569fc72f042e1729ddfa3202c074}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">arglist_type llvm::opt::ArgList::Args</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>The internal list of arguments.</p>

<p>Definition at line 132 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/option/arglist-h">ArgList.h</a>.</p>

</div>
</div>

### OptRanges {#a2d4ba15c22c2d13f82110d1bbd40afec}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">DenseMap&lt;unsigned, OptRange&gt; llvm::opt::ArgList::OptRanges</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>The first and last index of each different <a href="/web-llvm/docs/api/classes/llvm/opt/optspecifier">OptSpecifier</a> <a href="/web-llvm/docs/api/namespaces/llvm/callingconv/#abdf8cf606905c10634e831390981b0ed">ID</a>.</p>

<p>Definition at line 138 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/option/arglist-h">ArgList.h</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Protected Static Functions

### toOptSpecifier() {#a593b9ff9bea9354163be70de429075ec}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">OptSpecifier llvm::opt::ArgList::toOptSpecifier (<a href="/web-llvm/docs/api/classes/llvm/opt/optspecifier">OptSpecifier</a> S)</td>
</tr>
</table>
</td>
<td class="doxyMemberLabelsRight">
<span class="doxyMemberLabels">
<span class="doxyMemberLabel inline">inline</span>
<span class="doxyMemberLabel protected">protected</span>
<span class="doxyMemberLabel static">static</span>
</span>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 174 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/option/arglist-h">ArgList.h</a>.</p>


<p>Referenced by <a href="#ae6005f6bafe8396d40dc173831c6bdba">filtered</a> and <a href="#a5f5ba4a58ba957ffc2e173ea9cfb4834">filtered_reverse</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Private Static Functions

### emptyRange() {#aaf8eb75d9a8201cdd2984d2d07c65586}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">OptRange llvm::opt::ArgList::emptyRange ()</td>
</tr>
</table>
</td>
<td class="doxyMemberLabelsRight">
<span class="doxyMemberLabels">
<span class="doxyMemberLabel inline">inline</span>
<span class="doxyMemberLabel static">static</span>
</span>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 135 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/option/arglist-h">ArgList.h</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Arg Access

### append {#a862d6016ee6bbfb979acf4739b4fcfac}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void ArgList::append (<a href="/web-llvm/docs/api/classes/llvm/opt/arg">Arg</a> * A)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>append - Append <span class="doxyComputerOutput">A</span> to the arg list.</p>

<p>Declaration at line 181 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/option/arglist-h">ArgList.h</a>, definition at line 32 of file <a href="/web-llvm/docs/api/files/lib/lib/option/arglist-cpp">ArgList.cpp</a>.</p>


<p>Reference <a href="/web-llvm/docs/api/files/lib/lib/ir/builtingcs-cpp/#a2e38c85003a042421cde1647632d0b72">A</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/classes/llvm/opt/derivedarglist/#a3a30886094ab508b4a00828729da9d55">llvm::opt::DerivedArgList::AddFlagArg</a>, <a href="/web-llvm/docs/api/classes/llvm/opt/derivedarglist/#a07d2e877f7b7ac9f51686c52df637170">llvm::opt::DerivedArgList::AddJoinedArg</a>, <a href="/web-llvm/docs/api/classes/llvm/opt/derivedarglist/#a913fc3de04c49ef64ed77e50f0d5f7d9">llvm::opt::DerivedArgList::AddPositionalArg</a> and <a href="/web-llvm/docs/api/classes/llvm/opt/derivedarglist/#aca09243bbb137b7edf07ad9b20181bf4">llvm::opt::DerivedArgList::AddSeparateArg</a>.</p>

</div>
</div>

### getArgs {#a88c8665b3056d0730186572e8494f365}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">const arglist_type &amp; llvm::opt::ArgList::getArgs ()</td>
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



<p>Definition at line 183 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/option/arglist-h">ArgList.h</a>.</p>

</div>
</div>

### getArgString {#a238654e81bd5a66aa111a4cbf898c165}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">virtual const char * llvm::opt::ArgList::getArgString (unsigned Index)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>getArgString - Return the input argument string at <span class="doxyComputerOutput">Index</span>.</p>

<p>Definition at line 275 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/option/arglist-h">ArgList.h</a>.</p>


<p>Referenced by <a href="#a33efdfc01aaf654147da9f8c05f7706d">GetOrMakeJoinedArgString</a>.</p>

</div>
</div>

### getLastArg {#aa7b3f568748cb5a0cab744337ae3eb52}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<div class="doxyMemberTemplate">template &lt;typename ... OptSpecifiers&gt;</div>
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">Arg * llvm::opt::ArgList::getLastArg (OptSpecifiers ... Ids)</td>
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

<p>Return the last argument matching <span class="doxyComputerOutput">Id</span>, or null.</p>

<p>Definition at line 256 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/option/arglist-h">ArgList.h</a>.</p>


<p>References <a href="/web-llvm/docs/api/files/lib/lib/ir/builtingcs-cpp/#a2e38c85003a042421cde1647632d0b72">A</a>, <a href="/web-llvm/docs/api/classes/llvm/opt/arg/#acb283e68273392bc0169fe79b4e8e134">llvm::opt::Arg::claim</a> and <a href="#ae6005f6bafe8396d40dc173831c6bdba">filtered</a>.</p>


<p>Referenced by <a href="#a872650762e7195e1e9e7d10cf670c894">addLastArg</a>, <a href="#a342aaf3c2d86a3defc7baf1549143997">addOptInFlag</a>, <a href="#adc31a5f33c24a36189f865c605247c68">getLastArgValue</a>, <a href="#adacbd83ff3d0127e8862bdf6a0051572">hasArg</a>, <a href="#af4ede33e90efaf90c6534f43b3cfbffc">hasFlag</a> and <a href="#af5d90967a9f37775b3b18b46b846316b">hasFlag</a>.</p>

</div>
</div>

### getLastArgNoClaim {#a3102b968dbf681bb7353e02eba411a11}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<div class="doxyMemberTemplate">template &lt;typename ... OptSpecifiers&gt;</div>
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">Arg * llvm::opt::ArgList::getLastArgNoClaim (OptSpecifiers ... Ids)</td>
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

<p>Return the last argument matching <span class="doxyComputerOutput">Id</span>, or null.</p>


<p>Do not "claim" the option (don't mark it as having been used).</p>


<p>Definition at line 268 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/option/arglist-h">ArgList.h</a>.</p>


<p>References <a href="/web-llvm/docs/api/files/lib/lib/ir/builtingcs-cpp/#a2e38c85003a042421cde1647632d0b72">A</a> and <a href="#a5f5ba4a58ba957ffc2e173ea9cfb4834">filtered_reverse</a>.</p>


<p>Referenced by <a href="#a73c250aad85229fe689e98dc66c6fb44">hasArgNoClaim</a> and <a href="#a4a6d454c010b5cdcae7d8990ae44d0a5">hasFlagNoClaim</a>.</p>

</div>
</div>

### getNumInputArgStrings {#a2d204f9d95d54ae0427f37f73dab16db}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">virtual unsigned llvm::opt::ArgList::getNumInputArgStrings ()</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>getNumInputArgStrings - Return the number of original argument strings, which are guaranteed to be the first strings in the argument string list.</p>

<p>Definition at line 280 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/option/arglist-h">ArgList.h</a>.</p>


<p>Reference <a href="/web-llvm/docs/api/namespaces/llvm/#ae58c751054b01f206f9b9e34e461d25fa7a1920d61156abc05a60135aefe8bc67">llvm::Default</a>.</p>

</div>
</div>

### hasArg {#adacbd83ff3d0127e8862bdf6a0051572}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<div class="doxyMemberTemplate">template &lt;typename ... OptSpecifiers&gt;</div>
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool llvm::opt::ArgList::hasArg (OptSpecifiers ... Ids)</td>
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



<p>Definition at line 244 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/option/arglist-h">ArgList.h</a>.</p>


<p>Reference <a href="#aa7b3f568748cb5a0cab744337ae3eb52">getLastArg</a>.</p>

</div>
</div>

### hasArgNoClaim {#a73c250aad85229fe689e98dc66c6fb44}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<div class="doxyMemberTemplate">template &lt;typename ... OptSpecifiers&gt;</div>
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool llvm::opt::ArgList::hasArgNoClaim (OptSpecifiers ... Ids)</td>
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

<p>hasArg - Does the arg list contain any option matching <span class="doxyComputerOutput">Id</span>.</p>


<p><span class="doxyComputerOutput">Claim</span> Whether the argument should be claimed, if it exists.</p>


<p>Definition at line 240 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/option/arglist-h">ArgList.h</a>.</p>


<p>Reference <a href="#a3102b968dbf681bb7353e02eba411a11">getLastArgNoClaim</a>.</p>

</div>
</div>

### hasMultipleArgs {#a61b0d09d8e01eae52ed4e4ff3bb966d8}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool llvm::opt::ArgList::hasMultipleArgs (<a href="/web-llvm/docs/api/classes/llvm/opt/optspecifier">OptSpecifier</a> Id)</td>
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

<p>Return true if the arg list contains multiple arguments matching <span class="doxyComputerOutput">Id</span>.</p>

<p>Definition at line 249 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/option/arglist-h">ArgList.h</a>.</p>


<p>Reference <a href="#ae6005f6bafe8396d40dc173831c6bdba">filtered</a>.</p>

</div>
</div>

### size {#a5466418a7db1f20f39ad71346f22bdf7}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">unsigned llvm::opt::ArgList::size ()</td>
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



<p>Definition at line 185 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/option/arglist-h">ArgList.h</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Arg Iteration

### begin {#a820dba330c8ce4cf86cd2bae4d1ef509}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">iterator llvm::opt::ArgList::begin ()</td>
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



<p>Definition at line 191 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/option/arglist-h">ArgList.h</a>.</p>

</div>
</div>

### begin {#a97ff5248de01159460962ee3db81ee37}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">const_iterator llvm::opt::ArgList::begin ()</td>
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



<p>Definition at line 197 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/option/arglist-h">ArgList.h</a>.</p>

</div>
</div>

### end {#ae1d7be319add714458290b0251602b4a}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">iterator llvm::opt::ArgList::end ()</td>
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



<p>Definition at line 192 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/option/arglist-h">ArgList.h</a>.</p>

</div>
</div>

### end {#a5b1c259d095ece5b305b73226bad0bf6}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">const_iterator llvm::opt::ArgList::end ()</td>
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



<p>Definition at line 198 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/option/arglist-h">ArgList.h</a>.</p>

</div>
</div>

### filtered {#ae6005f6bafe8396d40dc173831c6bdba}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<div class="doxyMemberTemplate">template &lt;typename ... OptSpecifiers&gt;</div>
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">iterator_range&lt; filtered_iterator&lt; sizeof...(OptSpecifiers)&gt; &gt; llvm::opt::ArgList::filtered (OptSpecifiers ... Ids)</td>
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



<p>Definition at line 205 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/option/arglist-h">ArgList.h</a>.</p>


<p>References <a href="/web-llvm/docs/api/files/lib/lib/ir/builtingcs-cpp/#ae76959fe811ba090de4cba69ac00f1da">B</a>, <a href="/web-llvm/docs/api/files/lib/lib/ir/builtingcs-cpp/#abb2b3a60ccc38a28239e19a1646e0c8a">E</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a341215803e83773a3e97860dc291f121">llvm::make_range</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/nvptx/nvvmintrrange-cpp/#a34bd74317e3f04bfc4318c2d1a470877">Range</a> and <a href="#a593b9ff9bea9354163be70de429075ec">toOptSpecifier</a>.</p>


<p>Referenced by <a href="#a623040a06f67b95ab24c5e78e41c8bc8">AddAllArgs</a>, <a href="#a58ecc4f607c39abaf338915a04a29922">AddAllArgsTranslated</a>, <a href="#a279c6ca725e36eff09469d98e6ee1988">AddAllArgValues</a>, <a href="#a2598c7f3e2c4d6571d84bbcd8fdaf4a9">ClaimAllArgs</a>, <a href="#ab2e8451c25cb69c040675e00ca747319">claimAllArgs</a>, <a href="#a156189fac43bbb6cb89af54b0a72ebca">eraseArg</a>, <a href="#aa7b3f568748cb5a0cab744337ae3eb52">getLastArg</a> and <a href="#a61b0d09d8e01eae52ed4e4ff3bb966d8">hasMultipleArgs</a>.</p>

</div>
</div>

### filtered\_reverse {#a5f5ba4a58ba957ffc2e173ea9cfb4834}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<div class="doxyMemberTemplate">template &lt;typename ... OptSpecifiers&gt;</div>
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">iterator_range&lt; filtered_reverse_iterator&lt; sizeof...(OptSpecifiers)&gt; &gt; llvm::opt::ArgList::filtered_reverse (OptSpecifiers ... Ids)</td>
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



<p>Definition at line 216 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/option/arglist-h">ArgList.h</a>.</p>


<p>References <a href="/web-llvm/docs/api/files/lib/lib/ir/builtingcs-cpp/#ae76959fe811ba090de4cba69ac00f1da">B</a>, <a href="/web-llvm/docs/api/files/lib/lib/ir/builtingcs-cpp/#abb2b3a60ccc38a28239e19a1646e0c8a">E</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a341215803e83773a3e97860dc291f121">llvm::make_range</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/nvptx/nvvmintrrange-cpp/#a34bd74317e3f04bfc4318c2d1a470877">Range</a> and <a href="#a593b9ff9bea9354163be70de429075ec">toOptSpecifier</a>.</p>


<p>Referenced by <a href="#a3102b968dbf681bb7353e02eba411a11">getLastArgNoClaim</a>.</p>

</div>
</div>

### rbegin {#aa367fe2f66ef3f505946b6bf9beec0c3}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">reverse_iterator llvm::opt::ArgList::rbegin ()</td>
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



<p>Definition at line 194 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/option/arglist-h">ArgList.h</a>.</p>

</div>
</div>

### rbegin {#a9a3314fc0453555bb2cc3aea75b02ea6}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">const_reverse_iterator llvm::opt::ArgList::rbegin ()</td>
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



<p>Definition at line 200 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/option/arglist-h">ArgList.h</a>.</p>

</div>
</div>

### rend {#ab7464b01e58453e55bbb26521e50dd65}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">reverse_iterator llvm::opt::ArgList::rend ()</td>
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



<p>Definition at line 195 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/option/arglist-h">ArgList.h</a>.</p>

</div>
</div>

### rend {#a7210cd8ea9a9e820e62cdefe20981524}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">const_reverse_iterator llvm::opt::ArgList::rend ()</td>
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



<p>Definition at line 201 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/option/arglist-h">ArgList.h</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Arg Removal

### eraseArg {#a156189fac43bbb6cb89af54b0a72ebca}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void ArgList::eraseArg (<a href="/web-llvm/docs/api/classes/llvm/opt/optspecifier">OptSpecifier</a> Id)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>eraseArg - Remove any option matching <span class="doxyComputerOutput">Id</span>.</p>

<p>Declaration at line 230 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/option/arglist-h">ArgList.h</a>, definition at line 45 of file <a href="/web-llvm/docs/api/files/lib/lib/option/arglist-cpp">ArgList.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/files/lib/lib/ir/builtingcs-cpp/#a2e38c85003a042421cde1647632d0b72">A</a> and <a href="#ae6005f6bafe8396d40dc173831c6bdba">filtered</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Argument Lookup Utilities

### getAllArgValues {#ace2ec29a8f2231556c7f8a20929cc138}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">std::vector&lt; std::string &gt; ArgList::getAllArgValues (<a href="/web-llvm/docs/api/classes/llvm/opt/optspecifier">OptSpecifier</a> Id)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>getAllArgValues - Get the values of all instances of the given argument as strings.</p>

<p>Declaration at line 291 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/option/arglist-h">ArgList.h</a>, definition at line 98 of file <a href="/web-llvm/docs/api/files/lib/lib/option/arglist-cpp">ArgList.cpp</a>.</p>


<p>References <a href="#a279c6ca725e36eff09469d98e6ee1988">AddAllArgValues</a>, <a href="/web-llvm/docs/api/classes/llvm/smallvectortemplatecommon/#a8a045d250952c0867382a9840ee18fdf">llvm::SmallVectorTemplateCommon&lt; T, typename &gt;::begin</a> and <a href="/web-llvm/docs/api/classes/llvm/smallvectortemplatecommon/#a075e34e98605d0e7c289763a104869ac">llvm::SmallVectorTemplateCommon&lt; T, typename &gt;::end</a>.</p>

</div>
</div>

### getLastArgValue {#adc31a5f33c24a36189f865c605247c68}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">StringRef ArgList::getLastArgValue (<a href="/web-llvm/docs/api/classes/llvm/opt/optspecifier">OptSpecifier</a> Id, <a href="/web-llvm/docs/api/classes/llvm/stringref">StringRef</a> Default="")</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>getLastArgValue - Return the value of the last argument, or a default.</p>

<p>Declaration at line 287 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/option/arglist-h">ArgList.h</a>, definition at line 92 of file <a href="/web-llvm/docs/api/files/lib/lib/option/arglist-cpp">ArgList.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/files/lib/lib/ir/builtingcs-cpp/#a2e38c85003a042421cde1647632d0b72">A</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#ae58c751054b01f206f9b9e34e461d25fa7a1920d61156abc05a60135aefe8bc67">llvm::Default</a> and <a href="#aa7b3f568748cb5a0cab744337ae3eb52">getLastArg</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Translation Utilities

### addAllArgs {#a8a832028dff8abb97e1b9fec4987b13a}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void ArgList::addAllArgs (<a href="/web-llvm/docs/api/namespaces/llvm/opt/#a2ceb2416aeccdb4b087e29abc8c6b52f">ArgStringList</a> &amp; Output, <a href="/web-llvm/docs/api/classes/llvm/arrayref">ArrayRef</a>&lt; <a href="/web-llvm/docs/api/classes/llvm/opt/optspecifier">OptSpecifier</a> &gt; Ids)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Render all arguments matching any of the given ids.</p>


<p>This is a nicer interface when you don't have a list of Ids to exclude.</p>


<p>Declaration at line 337 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/option/arglist-h">ArgList.h</a>, definition at line 135 of file <a href="/web-llvm/docs/api/files/lib/lib/option/arglist-cpp">ArgList.cpp</a>.</p>


<p>Reference <a href="#ab7ef568579e2fc175c4d3d68921a1a9b">AddAllArgsExcept</a>.</p>

</div>
</div>

### AddAllArgs {#a623040a06f67b95ab24c5e78e41c8bc8}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void ArgList::AddAllArgs (<a href="/web-llvm/docs/api/namespaces/llvm/opt/#a2ceb2416aeccdb4b087e29abc8c6b52f">ArgStringList</a> &amp; Output, <a href="/web-llvm/docs/api/classes/llvm/opt/optspecifier">OptSpecifier</a> Id0)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>AddAllArgs - Render all arguments matching the given ids.</p>

<p>Declaration at line 340 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/option/arglist-h">ArgList.h</a>, definition at line 141 of file <a href="/web-llvm/docs/api/files/lib/lib/option/arglist-cpp">ArgList.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/classes/llvm/opt/arg/#acb283e68273392bc0169fe79b4e8e134">llvm::opt::Arg::claim</a>, <a href="#ae6005f6bafe8396d40dc173831c6bdba">filtered</a> and <a href="/web-llvm/docs/api/classes/llvm/opt/arg/#a05377ec092a5d076c82dd3285317e6fa">llvm::opt::Arg::render</a>.</p>

</div>
</div>

### AddAllArgsExcept {#ab7ef568579e2fc175c4d3d68921a1a9b}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void ArgList::AddAllArgsExcept (<a href="/web-llvm/docs/api/namespaces/llvm/opt/#a2ceb2416aeccdb4b087e29abc8c6b52f">ArgStringList</a> &amp; Output, <a href="/web-llvm/docs/api/classes/llvm/arrayref">ArrayRef</a>&lt; <a href="/web-llvm/docs/api/classes/llvm/opt/optspecifier">OptSpecifier</a> &gt; Ids, <a href="/web-llvm/docs/api/classes/llvm/arrayref">ArrayRef</a>&lt; <a href="/web-llvm/docs/api/classes/llvm/opt/optspecifier">OptSpecifier</a> &gt; ExcludeIds)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>AddAllArgsExcept - Render all arguments matching any of the given ids and not matching any of the excluded ids.</p>

<p>Declaration at line 334 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/option/arglist-h">ArgList.h</a>, definition at line 111 of file <a href="/web-llvm/docs/api/files/lib/lib/option/arglist-cpp">ArgList.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/classes/llvm/opt/arg/#acb283e68273392bc0169fe79b4e8e134">llvm::opt::Arg::claim</a>, <a href="/web-llvm/docs/api/classes/llvm/opt/arg/#a666ec80cc708a588992a87278c4e1f74">llvm::opt::Arg::getOption</a>, <a href="/web-llvm/docs/api/classes/llvm/opt/option/#a34443bb51a0b61e6c113e721533d3235">llvm::opt::Option::matches</a> and <a href="/web-llvm/docs/api/classes/llvm/opt/arg/#a05377ec092a5d076c82dd3285317e6fa">llvm::opt::Arg::render</a>.</p>


<p>Referenced by <a href="#a8a832028dff8abb97e1b9fec4987b13a">addAllArgs</a>.</p>

</div>
</div>

### AddAllArgsTranslated {#a58ecc4f607c39abaf338915a04a29922}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void ArgList::AddAllArgsTranslated (<a href="/web-llvm/docs/api/namespaces/llvm/opt/#a2ceb2416aeccdb4b087e29abc8c6b52f">ArgStringList</a> &amp; Output, <a href="/web-llvm/docs/api/classes/llvm/opt/optspecifier">OptSpecifier</a> Id0, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> char * Translation, bool Joined=false)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>AddAllArgsTranslated - Render all the arguments matching the given ids, but forced to separate args and using the provided name instead of the first option value.</p>


<dl class="doxyParamsList">
<dt class="doxyParamsTableTitle">Parameters</dt>
<dd>
<table class="doxyParamsTable">
<tr class="doxyParamItem">
<td class="doxyParamItemName">Joined</td>
<td class="doxyParamItemDescription"><p>- If true, render the argument as joined with the option specifier.</p></td>
</tr>
</table>
</dd>
</dl>

<p>Declaration at line 353 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/option/arglist-h">ArgList.h</a>, definition at line 157 of file <a href="/web-llvm/docs/api/files/lib/lib/option/arglist-cpp">ArgList.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/classes/llvm/opt/arg/#acb283e68273392bc0169fe79b4e8e134">llvm::opt::Arg::claim</a>, <a href="#ae6005f6bafe8396d40dc173831c6bdba">filtered</a>, <a href="/web-llvm/docs/api/classes/llvm/opt/arg/#ac268590692356db84db78050196b4940">llvm::opt::Arg::getValue</a>, <a href="#a678763a7949f037831ab90dcea55a817">MakeArgString</a> and <a href="/web-llvm/docs/api/classes/llvm/smallvectortemplatebase/#af42bfbc067df27c19ee2fc859df58799">llvm::SmallVectorTemplateBase&lt; T, bool &gt;::push_back</a>.</p>

</div>
</div>

### AddAllArgValues {#a279c6ca725e36eff09469d98e6ee1988}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void ArgList::AddAllArgValues (<a href="/web-llvm/docs/api/namespaces/llvm/opt/#a2ceb2416aeccdb4b087e29abc8c6b52f">ArgStringList</a> &amp; Output, <a href="/web-llvm/docs/api/classes/llvm/opt/optspecifier">OptSpecifier</a> Id0, <a href="/web-llvm/docs/api/classes/llvm/opt/optspecifier">OptSpecifier</a> Id1=0U, <a href="/web-llvm/docs/api/classes/llvm/opt/optspecifier">OptSpecifier</a> Id2=0U)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>AddAllArgValues - Render the argument values of all arguments matching the given ids.</p>

<p>Declaration at line 344 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/option/arglist-h">ArgList.h</a>, definition at line 148 of file <a href="/web-llvm/docs/api/files/lib/lib/option/arglist-cpp">ArgList.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/classes/llvm/smallvectorimpl/#a7efd1f0c1206d95e4fe01a9b49a57b82">llvm::SmallVectorImpl&lt; T &gt;::append</a>, <a href="/web-llvm/docs/api/classes/llvm/opt/arg/#acb283e68273392bc0169fe79b4e8e134">llvm::opt::Arg::claim</a>, <a href="#ae6005f6bafe8396d40dc173831c6bdba">filtered</a> and <a href="/web-llvm/docs/api/classes/llvm/opt/arg/#a5fae2e9403c3f2b91455abe787c41add">llvm::opt::Arg::getValues</a>.</p>


<p>Referenced by <a href="#ace2ec29a8f2231556c7f8a20929cc138">getAllArgValues</a>.</p>

</div>
</div>

### addLastArg {#a872650762e7195e1e9e7d10cf670c894}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<div class="doxyMemberTemplate">template &lt;typename... OptSpecifiers&gt;</div>
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void llvm::opt::ArgList::addLastArg (<a href="/web-llvm/docs/api/namespaces/llvm/opt/#a2ceb2416aeccdb4b087e29abc8c6b52f">ArgStringList</a> &amp; Output, OptSpecifiers... Ids)</td>
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

<p>Render only the last argument match <span class="doxyComputerOutput">Id0</span>, if present.</p>

<p>Definition at line 323 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/option/arglist-h">ArgList.h</a>.</p>


<p>References <a href="/web-llvm/docs/api/files/lib/lib/ir/builtingcs-cpp/#a2e38c85003a042421cde1647632d0b72">A</a> and <a href="#aa7b3f568748cb5a0cab744337ae3eb52">getLastArg</a>.</p>


<p>Referenced by <a href="#a7a0ac31f20ed170cac107e0d4c8c6f24">AddLastArg</a>.</p>

</div>
</div>

### AddLastArg {#a7a0ac31f20ed170cac107e0d4c8c6f24}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<div class="doxyMemberTemplate">template &lt;typename... OptSpecifiers&gt;</div>
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void llvm::opt::ArgList::AddLastArg (<a href="/web-llvm/docs/api/namespaces/llvm/opt/#a2ceb2416aeccdb4b087e29abc8c6b52f">ArgStringList</a> &amp; Output, OptSpecifiers... Ids)</td>
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



<p>Definition at line 328 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/option/arglist-h">ArgList.h</a>.</p>


<p>Reference <a href="#a872650762e7195e1e9e7d10cf670c894">addLastArg</a>.</p>

</div>
</div>

### addOptInFlag {#a342aaf3c2d86a3defc7baf1549143997}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void ArgList::addOptInFlag (<a href="/web-llvm/docs/api/namespaces/llvm/opt/#a2ceb2416aeccdb4b087e29abc8c6b52f">ArgStringList</a> &amp; Output, <a href="/web-llvm/docs/api/classes/llvm/opt/optspecifier">OptSpecifier</a> Pos, <a href="/web-llvm/docs/api/classes/llvm/opt/optspecifier">OptSpecifier</a> Neg)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Given an option Pos and its negative form Neg, render the option if Pos is present.</p>

<p>Declaration at line 313 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/option/arglist-h">ArgList.h</a>, definition at line 104 of file <a href="/web-llvm/docs/api/files/lib/lib/option/arglist-cpp">ArgList.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/files/lib/lib/ir/builtingcs-cpp/#a2e38c85003a042421cde1647632d0b72">A</a> and <a href="#aa7b3f568748cb5a0cab744337ae3eb52">getLastArg</a>.</p>


<p>Referenced by <a href="#ad270693324724209b55d264ede75f640">addOptOutFlag</a>.</p>

</div>
</div>

### addOptOutFlag {#ad270693324724209b55d264ede75f640}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void llvm::opt::ArgList::addOptOutFlag (<a href="/web-llvm/docs/api/namespaces/llvm/opt/#a2ceb2416aeccdb4b087e29abc8c6b52f">ArgStringList</a> &amp; Output, <a href="/web-llvm/docs/api/classes/llvm/opt/optspecifier">OptSpecifier</a> Pos, <a href="/web-llvm/docs/api/classes/llvm/opt/optspecifier">OptSpecifier</a> Neg)</td>
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

<p>Render the option if Neg is present.</p>

<p>Definition at line 316 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/option/arglist-h">ArgList.h</a>.</p>


<p>Reference <a href="#a342aaf3c2d86a3defc7baf1549143997">addOptInFlag</a>.</p>

</div>
</div>

### claimAllArgs {#ab2e8451c25cb69c040675e00ca747319}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<div class="doxyMemberTemplate">template &lt;typename... OptSpecifiers&gt;</div>
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void llvm::opt::ArgList::claimAllArgs (OptSpecifiers... Ids)</td>
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



<p>Definition at line 362 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/option/arglist-h">ArgList.h</a>.</p>


<p>References <a href="/web-llvm/docs/api/files/lib/lib/ir/builtingcs-cpp/#a2e38c85003a042421cde1647632d0b72">A</a> and <a href="#ae6005f6bafe8396d40dc173831c6bdba">filtered</a>.</p>

</div>
</div>

### ClaimAllArgs {#a2598c7f3e2c4d6571d84bbcd8fdaf4a9}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void ArgList::ClaimAllArgs (<a href="/web-llvm/docs/api/classes/llvm/opt/optspecifier">OptSpecifier</a> Id0)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>ClaimAllArgs - Claim all arguments which match the given option id.</p>

<p>Declaration at line 359 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/option/arglist-h">ArgList.h</a>, definition at line 173 of file <a href="/web-llvm/docs/api/files/lib/lib/option/arglist-cpp">ArgList.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/classes/llvm/opt/arg/#acb283e68273392bc0169fe79b4e8e134">llvm::opt::Arg::claim</a> and <a href="#ae6005f6bafe8396d40dc173831c6bdba">filtered</a>.</p>

</div>
</div>

### ClaimAllArgs {#a974b1537dd2bfc45684a63390f5a0c8a}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void ArgList::ClaimAllArgs ()</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>ClaimAllArgs - Claim all arguments.</p>

<p>Declaration at line 369 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/option/arglist-h">ArgList.h</a>, definition at line 178 of file <a href="/web-llvm/docs/api/files/lib/lib/option/arglist-cpp">ArgList.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/classes/llvm/opt/arg/#acb283e68273392bc0169fe79b4e8e134">llvm::opt::Arg::claim</a> and <a href="/web-llvm/docs/api/classes/llvm/opt/arg/#a78b7b00f492ac682e070f08e6a263d33">llvm::opt::Arg::isClaimed</a>.</p>

</div>
</div>

### hasFlag {#af4ede33e90efaf90c6534f43b3cfbffc}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool ArgList::hasFlag (<a href="/web-llvm/docs/api/classes/llvm/opt/optspecifier">OptSpecifier</a> Pos, <a href="/web-llvm/docs/api/classes/llvm/opt/optspecifier">OptSpecifier</a> Neg, bool Default)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>hasFlag - Given an option <span class="doxyComputerOutput">Pos</span> and its negative form <span class="doxyComputerOutput">Neg</span>, return true if the option is present, false if the negation is present, and <span class="doxyComputerOutput">Default</span> if neither option is given.</p>


<p>If both the option and its negation are present, the last one wins.</p>


<p>Declaration at line 301 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/option/arglist-h">ArgList.h</a>, definition at line 72 of file <a href="/web-llvm/docs/api/files/lib/lib/option/arglist-cpp">ArgList.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/files/lib/lib/ir/builtingcs-cpp/#a2e38c85003a042421cde1647632d0b72">A</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#ae58c751054b01f206f9b9e34e461d25fa7a1920d61156abc05a60135aefe8bc67">llvm::Default</a> and <a href="#aa7b3f568748cb5a0cab744337ae3eb52">getLastArg</a>.</p>

</div>
</div>

### hasFlag {#af5d90967a9f37775b3b18b46b846316b}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool ArgList::hasFlag (<a href="/web-llvm/docs/api/classes/llvm/opt/optspecifier">OptSpecifier</a> Pos, <a href="/web-llvm/docs/api/classes/llvm/opt/optspecifier">OptSpecifier</a> PosAlias, <a href="/web-llvm/docs/api/classes/llvm/opt/optspecifier">OptSpecifier</a> Neg, bool Default)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>hasFlag - Given an option <span class="doxyComputerOutput">Pos</span>, an alias <span class="doxyComputerOutput">PosAlias</span> and its negative form <span class="doxyComputerOutput">Neg</span>, return true if the option or its alias is present, false if the negation is present, and <span class="doxyComputerOutput">Default</span> if none of the options are given.</p>


<p>If multiple options are present, the last one wins.</p>


<p>Declaration at line 308 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/option/arglist-h">ArgList.h</a>, definition at line 85 of file <a href="/web-llvm/docs/api/files/lib/lib/option/arglist-cpp">ArgList.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/files/lib/lib/ir/builtingcs-cpp/#a2e38c85003a042421cde1647632d0b72">A</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#ae58c751054b01f206f9b9e34e461d25fa7a1920d61156abc05a60135aefe8bc67">llvm::Default</a> and <a href="#aa7b3f568748cb5a0cab744337ae3eb52">getLastArg</a>.</p>

</div>
</div>

### hasFlagNoClaim {#a4a6d454c010b5cdcae7d8990ae44d0a5}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool ArgList::hasFlagNoClaim (<a href="/web-llvm/docs/api/classes/llvm/opt/optspecifier">OptSpecifier</a> Pos, <a href="/web-llvm/docs/api/classes/llvm/opt/optspecifier">OptSpecifier</a> Neg, bool Default)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Declaration at line 302 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/option/arglist-h">ArgList.h</a>, definition at line 78 of file <a href="/web-llvm/docs/api/files/lib/lib/option/arglist-cpp">ArgList.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/files/lib/lib/ir/builtingcs-cpp/#a2e38c85003a042421cde1647632d0b72">A</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#ae58c751054b01f206f9b9e34e461d25fa7a1920d61156abc05a60135aefe8bc67">llvm::Default</a> and <a href="#a3102b968dbf681bb7353e02eba411a11">getLastArgNoClaim</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Arg Synthesis

### dump {#ab5735777324ec9864032e2673b01d58c}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">LLVM_DUMP_METHOD void ArgList::dump ()</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Declaration at line 388 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/option/arglist-h">ArgList.h</a>, definition at line 203 of file <a href="/web-llvm/docs/api/files/lib/lib/option/arglist-cpp">ArgList.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/namespaces/llvm/#a7c46c742c31be54870e2038048e6b391">llvm::dbgs</a>, <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/support/compiler-h/#aa863693eef567397d9c292da5bf22d34">LLVM_DUMP_METHOD</a> and <a href="#a3347586cae383098ab26e84292881ebf">print</a>.</p>

</div>
</div>

### GetOrMakeJoinedArgString {#a33efdfc01aaf654147da9f8c05f7706d}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">const char * ArgList::GetOrMakeJoinedArgString (unsigned Index, <a href="/web-llvm/docs/api/classes/llvm/stringref">StringRef</a> LHS, <a href="/web-llvm/docs/api/classes/llvm/stringref">StringRef</a> RHS)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Create an arg string for (<span class="doxyComputerOutput">LHS</span> + <span class="doxyComputerOutput">RHS</span>), reusing the string at <span class="doxyComputerOutput">Index</span> if possible.</p>

<p>Declaration at line 384 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/option/arglist-h">ArgList.h</a>, definition at line 184 of file <a href="/web-llvm/docs/api/files/lib/lib/option/arglist-cpp">ArgList.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/classes/llvm/stringref/#a7b0fa1a82461032cdf16b7f6c59f0a6a">llvm::StringRef::data</a>, <a href="/web-llvm/docs/api/classes/llvm/stringref/#aca439bf65258d9d8d057812938b617c5">llvm::StringRef::ends_with</a>, <a href="#a238654e81bd5a66aa111a4cbf898c165">getArgString</a>, <a href="#a678763a7949f037831ab90dcea55a817">MakeArgString</a>, <a href="/web-llvm/docs/api/classes/llvm/stringref/#a5db9240c74644c67759dd0f901fc3c7d">llvm::StringRef::size</a> and <a href="/web-llvm/docs/api/classes/llvm/stringref/#a2cd8968ff703aaeb395dcd63f6805ff1">llvm::StringRef::starts_with</a>.</p>

</div>
</div>

### MakeArgString {#a678763a7949f037831ab90dcea55a817}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">const char * llvm::opt::ArgList::MakeArgString (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/twine">Twine</a> &amp; Str)</td>
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



<p>Definition at line 377 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/option/arglist-h">ArgList.h</a>.</p>


<p>Reference <a href="#ae249e8d33e950ad1d388556c89a359a6">MakeArgStringRef</a>.</p>


<p>Referenced by <a href="#a58ecc4f607c39abaf338915a04a29922">AddAllArgsTranslated</a> and <a href="#a33efdfc01aaf654147da9f8c05f7706d">GetOrMakeJoinedArgString</a>.</p>

</div>
</div>

### MakeArgStringRef {#ae249e8d33e950ad1d388556c89a359a6}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">virtual const char * llvm::opt::ArgList::MakeArgStringRef (<a href="/web-llvm/docs/api/classes/llvm/stringref">StringRef</a> Str)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Construct a constant string pointer whose lifetime will match that of the <a href="/web-llvm/docs/api/classes/llvm/opt/arglist">ArgList</a>.</p>

<p>Definition at line 376 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/option/arglist-h">ArgList.h</a>.</p>


<p>Referenced by <a href="#a678763a7949f037831ab90dcea55a817">MakeArgString</a>.</p>

</div>
</div>

### print {#a3347586cae383098ab26e84292881ebf}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void ArgList::print (<a href="/web-llvm/docs/api/classes/llvm/raw-ostream">raw_ostream</a> &amp; O)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Declaration at line 387 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/option/arglist-h">ArgList.h</a>, definition at line 195 of file <a href="/web-llvm/docs/api/files/lib/lib/option/arglist-cpp">ArgList.cpp</a>.</p>


<p>Reference <a href="/web-llvm/docs/api/files/lib/lib/ir/builtingcs-cpp/#a2e38c85003a042421cde1647632d0b72">A</a>.</p>


<p>Referenced by <a href="#ab5735777324ec9864032e2673b01d58c">dump</a>.</p>

</div>
</div>

</div>

<hr/>

The documentation for this class was generated from the following files:

<ul>
<li><a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/option/arglist-h">ArgList.h</a></li>
<li><a href="/web-llvm/docs/api/files/lib/lib/option/arglist-cpp">ArgList.cpp</a></li>
</ul>

<hr/>

<p class="doxyGeneratedBy">Generated via <a href="https://github.com/xpack/doxygen2docusaurus">doxygen2docusaurus</a> by <a href="https://www.doxygen.nl">Doxygen</a> 1.15.0.</p>

</div>
