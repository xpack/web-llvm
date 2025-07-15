---

# DO NOT EDIT!
# Automatically generated via doxygen2docusaurus by Doxygen.

slug: /api/structs/llvm/detail/uniquefunctionbase/nontrivialcallbacks
custom_edit_url: null
toc_max_heading_level: 4
keywords:
  - doxygen
  - reference
  - struct

---

<div class="doxyPage">

# The `NonTrivialCallbacks` Struct Reference

<p>A struct we use to aggregate three callbacks when we need full set of operations. <a href="#details">More...</a></p>

## Declaration

<div class="doxyDeclaration">
struct llvm::detail::UniqueFunctionBase::NonTrivialCallbacks { ... }
</div>

## Included Headers

<div class="doxyIncludesList">#include "<a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/adt/functionextras-h">llvm/ADT/FunctionExtras.h</a>"
</div>

## Public Member Attributes Index

<table class="doxyMembersIndex">

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/detail/uniquefunctionbase/#ad288286dc47ebc0627a959b0b73b4f07">CallPtrT</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ad79629877ef746a4834280327dd54a5f">CallPtr</a></td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/detail/uniquefunctionbase/#a1301d4dd2580808c59e79c5ee0582139">MovePtrT</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a610e945b8a0cced95a06904273be7a08">MovePtr</a></td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/detail/uniquefunctionbase/#ad1d1a8b2b0bb45c115e6df518cfb1d6d">DestroyPtrT</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a06981c10535d2568955138877e54a07a">DestroyPtr</a></td>
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

<p>A struct we use to aggregate three callbacks when we need full set of operations.</p>

<p>Definition at line 135 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/adt/functionextras-h">FunctionExtras.h</a>.</p>


<div class="doxySectionDef">

## Public Member Attributes

### CallPtr {#ad79629877ef746a4834280327dd54a5f}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">CallPtrT llvm::detail::UniqueFunctionBase&lt; ReturnT, ParamTs &gt;::NonTrivialCallbacks::CallPtr</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 136 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/adt/functionextras-h">FunctionExtras.h</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/classes/llvm/detail/uniquefunctionbase/#a0166f36c59bf23f7a969796f3b160120">llvm::detail::UniqueFunctionBase&lt; R, P... &gt;::getCallPtr</a>.</p>

</div>
</div>

### DestroyPtr {#a06981c10535d2568955138877e54a07a}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">DestroyPtrT llvm::detail::UniqueFunctionBase&lt; ReturnT, ParamTs &gt;::NonTrivialCallbacks::DestroyPtr</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 138 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/adt/functionextras-h">FunctionExtras.h</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/classes/llvm/detail/uniquefunctionbase/#ad6d450e33cf5fff1101a1e8daabcd2b3">llvm::detail::UniqueFunctionBase&lt; R, P... &gt;::UniqueFunctionBase</a> and <a href="/web-llvm/docs/api/classes/llvm/detail/uniquefunctionbase/#a288074261a390b844e1bb895827aae96">llvm::detail::UniqueFunctionBase&lt; R, P... &gt;::~UniqueFunctionBase</a>.</p>

</div>
</div>

### MovePtr {#a610e945b8a0cced95a06904273be7a08}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">MovePtrT llvm::detail::UniqueFunctionBase&lt; ReturnT, ParamTs &gt;::NonTrivialCallbacks::MovePtr</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 137 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/adt/functionextras-h">FunctionExtras.h</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/classes/llvm/detail/uniquefunctionbase/#ad6d450e33cf5fff1101a1e8daabcd2b3">llvm::detail::UniqueFunctionBase&lt; R, P... &gt;::UniqueFunctionBase</a>.</p>

</div>
</div>

</div>

<hr/>

The documentation for this struct was generated from the following file:

<ul>
<li><a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/adt/functionextras-h">FunctionExtras.h</a></li>
</ul>

<hr/>

<p class="doxyGeneratedBy">Generated via <a href="https://github.com/xpack/doxygen2docusaurus">doxygen2docusaurus</a> by <a href="https://www.doxygen.nl">Doxygen</a> 1.14.0.</p>

</div>
