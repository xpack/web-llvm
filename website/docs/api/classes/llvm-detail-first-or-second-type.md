---

# DO NOT EDIT!
# Automatically generated via doxygen2docusaurus by Doxygen.

slug: /api/classes/llvm/detail/first-or-second-type
custom_edit_url: null
toc_max_heading_level: 4
keywords:
  - doxygen
  - reference
  - class

---

<div class="doxyPage">

# The `first_or_second_type` Class Template Reference

<p>Return a reference to the first or second member of a reference. <a href="#details">More...</a></p>

## Declaration

<div class="doxyDeclaration">
template &lt;typename EltTy, typename FirstTy&gt;
class llvm::detail::first_or_second_type&lt;EltTy, FirstTy&gt; { ... }
</div>

## Included Headers

<div class="doxyIncludesList">#include "<a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/adt/stlextras-h">llvm/ADT/STLExtras.h</a>"
</div>

## Public Member Typedefs Index

<table class="doxyMembersIndex">

<tr class="doxyMemberIndexTemplate">
<td class="doxyMemberIndexTemplate" colspan="2"><div>template &lt;typename EltTy, typename FirstTy&gt;</div></td>
</tr>
<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemTypeTemplate" align="left" valign="top">using</td>
<td class="doxyMemberIndexItemNameTemplate" align="left" valign="top"><a href="#ada3c4ec351e39616de6e0256ef0a000b">type</a> = std::conditional_t&lt; std::is_reference&lt; EltTy &gt;<a href="/web-llvm/docs/api/namespaces/llvm/detail/#a3fe429695b1d6a60635b1e490092037e">::value</a>, FirstTy, std::remove_reference_t&lt; FirstTy &gt; &gt;</td>
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

<p>Return a reference to the first or second member of a reference.</p>


<p>Otherwise, return a copy of the member of a temporary.</p>


<p>When passing a range whose iterators return values instead of references, the reference must be dropped from <span class="doxyComputerOutput">decltype((elt.first))</span>, which will always be a reference, to avoid returning a reference to a temporary.</p>


<p>Definition at line 1431 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/adt/stlextras-h">STLExtras.h</a>.</p>


<div class="doxySectionDef">

## Public Member Typedefs

### type {#ada3c4ec351e39616de6e0256ef0a000b}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<div class="doxyMemberTemplate">template &lt;typename EltTy, typename FirstTy&gt;</div>
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">using llvm::detail::first_or_second_type&lt; EltTy, FirstTy &gt;::type =  std::conditional_t&lt;std::is_reference&lt;EltTy&gt;::value, FirstTy,
                                  std::remove_reference_t&lt;FirstTy&gt;&gt;</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 1433 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/adt/stlextras-h">STLExtras.h</a>.</p>

</div>
</div>

</div>

<hr/>

The documentation for this class was generated from the following file:

<ul>
<li><a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/adt/stlextras-h">STLExtras.h</a></li>
</ul>

<hr/>

<p class="doxyGeneratedBy">Generated via <a href="https://github.com/xpack/doxygen2docusaurus">doxygen2docusaurus</a> by <a href="https://www.doxygen.nl">Doxygen</a> 1.14.0.</p>

</div>
