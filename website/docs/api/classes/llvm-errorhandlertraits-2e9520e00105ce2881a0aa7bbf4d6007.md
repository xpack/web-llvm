---

# DO NOT EDIT!
# Automatically generated via doxygen2docusaurus by Doxygen.

slug: /api/classes/llvm/errorhandlertraits-2e9520e00105ce2881a0aa7bbf4d6007
custom_edit_url: null
toc_max_heading_level: 4
keywords:
  - doxygen
  - reference
  - class

---

<div class="doxyPage">

# `ErrorHandlerTraits` Class Template

<p>Specialization for member functions of the form 'RetT (std::unique_ptr&lt;ErrT&gt;)'. <a href="#details">More...</a></p>

## Declaration

<div class="doxyDeclaration">
template &lt;typename C, typename RetT, typename ErrT&gt;
class llvm::ErrorHandlerTraits&lt;RetT(C::*)(std::unique_ptr&lt; ErrT &gt;)&gt; { ... }
</div>

## Included Headers

<div class="doxyIncludesList">#include "<a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/support/error-h">llvm/Support/Error.h</a>"
</div>

## Base class

<table class="doxyMembersIndex">

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">class</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/errorhandlertraits">ErrorHandlerTraits&lt;HandlerT&gt;</a></td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Helper for testing applicability of, and applying, handlers for <a href="/web-llvm/docs/api/classes/llvm/errorinfo">ErrorInfo</a> types. <a href="/web-llvm/docs/api/classes/llvm/errorhandlertraits/#details">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

</table>

## Description {#details}

<p>Specialization for member functions of the form 'RetT (std::unique_ptr&lt;ErrT&gt;)'.</p>

<p>Definition at line 924 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/support/error-h">Error.h</a>.</p>


<hr/>

<p class="doxyGeneratedBy">Generated via <a href="https://github.com/xpack/doxygen2docusaurus">doxygen2docusaurus</a> by <a href="https://www.doxygen.nl">Doxygen</a> 1.15.0.</p>

</div>
