---

# DO NOT EDIT!
# Automatically generated via doxygen2docusaurus by Doxygen.

slug: /api/structs/llvm/detail/errorholder
custom_edit_url: null
toc_max_heading_level: 4
keywords:
  - doxygen
  - reference
  - struct

---

<div class="doxyPage">

# `ErrorHolder` Struct



## Declaration

<div class="doxyDeclaration">
struct llvm::detail::ErrorHolder { ... }
</div>

## Included Headers

<div class="doxyIncludesList">#include "<a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/testing/include/llvm/testing/support/supporthelpers-h">llvm/Testing/Support/SupportHelpers.h</a>"
</div>

## Derived Structs

<table class="doxyMembersIndex">

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">struct</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="/web-llvm/docs/api/structs/llvm/detail/expectedholder">ExpectedHolder&lt;T&gt;</a></td>
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

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">bool</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a41e8ff6f9bf94de6e7201bd13dcf190f">Success</a> () const</td>
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

## Public Member Attributes Index

<table class="doxyMembersIndex">

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">std::vector&lt; std::shared_ptr&lt; <a href="/web-llvm/docs/api/classes/llvm/errorinfobase">ErrorInfoBase</a> &gt; &gt;</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a3f39ac70f66ad250c9f1ec90c4970fae">Infos</a></td>
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


<p>Definition at line 25 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/testing/include/llvm/testing/support/supporthelpers-h">SupportHelpers.h</a>.</p>


<div class="doxySectionDef">

## Public Member Functions

### Success() {#a41e8ff6f9bf94de6e7201bd13dcf190f}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool llvm::detail::ErrorHolder::Success ()</td>
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



<p>Definition at line 28 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/testing/include/llvm/testing/support/supporthelpers-h">SupportHelpers.h</a>.</p>


<p>Reference <a href="#a3f39ac70f66ad250c9f1ec90c4970fae">Infos</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/classes/llvm/detail/errormatchesmono/#ab5ca366d69aa6962d4142ab273fa72b1">llvm::detail::ErrorMatchesMono&lt; InfoT &gt;::MatchAndExplain</a>, <a href="/web-llvm/docs/api/classes/llvm/detail/valuematchesmono/#a55e4701767b53c688bffa2d8793c27be">llvm::detail::ValueMatchesMono&lt; T &gt;::MatchAndExplain</a>, <a href="/web-llvm/docs/api/namespaces/llvm/detail/#a8e42ee77c6f653926adf1253af32dea0">llvm::detail::PrintTo</a> and <a href="/web-llvm/docs/api/namespaces/llvm/detail/#ae3cee347bb08dc5c49a0c79a02ad120c">llvm::detail::PrintTo</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Public Member Attributes

### Infos {#a3f39ac70f66ad250c9f1ec90c4970fae}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">std::vector&lt;std::shared_ptr&lt;ErrorInfoBase&gt; &gt; llvm::detail::ErrorHolder::Infos</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 26 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/testing/include/llvm/testing/support/supporthelpers-h">SupportHelpers.h</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/classes/llvm/detail/errormatchesmono/#ab5ca366d69aa6962d4142ab273fa72b1">llvm::detail::ErrorMatchesMono&lt; InfoT &gt;::MatchAndExplain</a>, <a href="/web-llvm/docs/api/classes/llvm/detail/errormessagematches/#ac6fe268bac0c05dbccf3c63bbb54b356">llvm::detail::ErrorMessageMatches::MatchAndExplain</a>, <a href="/web-llvm/docs/api/namespaces/llvm/detail/#a8e42ee77c6f653926adf1253af32dea0">llvm::detail::PrintTo</a> and <a href="#a41e8ff6f9bf94de6e7201bd13dcf190f">Success</a>.</p>

</div>
</div>

</div>

<hr/>

The documentation for this struct was generated from the following file:

<ul>
<li><a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/testing/include/llvm/testing/support/supporthelpers-h">SupportHelpers.h</a></li>
</ul>

<hr/>

<p class="doxyGeneratedBy">Generated via <a href="https://xpack.github.io/doxygen2docusaurus">doxygen2docusaurus</a> 2.0.0 by <a href="https://www.doxygen.nl">Doxygen</a> 1.15.0.</p>

</div>
