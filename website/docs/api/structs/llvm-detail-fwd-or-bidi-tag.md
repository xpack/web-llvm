---

# DO NOT EDIT!
# Automatically generated via doxygen2docusaurus by Doxygen.

slug: /api/structs/llvm/detail/fwd-or-bidi-tag
custom_edit_url: null
toc_max_heading_level: 4
keywords:
  - doxygen
  - reference
  - struct

---

<div class="doxyPage">

# `fwd_or_bidi_tag` Struct Template

<p>Helper which sets its type member to forward_iterator_tag if the category of <span class="doxyComputerOutput">IterT</span> does not derive from bidirectional_iterator_tag, and to bidirectional_iterator_tag otherwise. <a href="#details">More...</a></p>

## Declaration

<div class="doxyDeclaration">
template &lt;typename IterT&gt;
struct llvm::detail::fwd_or_bidi_tag&lt;IterT&gt; { ... }
</div>

## Included Headers

<div class="doxyIncludesList">#include "<a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/adt/stlextras-h">llvm/ADT/STLExtras.h</a>"
</div>

## Public Member Typedefs Index

<table class="doxyMembersIndex">

<tr class="doxyMemberIndexTemplate">
<td class="doxyMemberIndexTemplate" colspan="2"><div>template &lt;typename IterT&gt;</div></td>
</tr>
<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemTypeTemplate" align="left" valign="top">using</td>
<td class="doxyMemberIndexItemNameTemplate" align="left" valign="top"><a href="#a2e36701a503a8f20e834f872f181fb34">type</a> = typename <a href="/web-llvm/docs/api/structs/llvm/detail/fwd-or-bidi-tag-impl">fwd_or_bidi_tag_impl</a>&lt; std::is_base_of&lt; std::bidirectional_iterator_tag, typename std::iterator_traits&lt; IterT &gt;::iterator_category &gt;<a href="/web-llvm/docs/api/namespaces/llvm/detail/#a3fe429695b1d6a60635b1e490092037e">::value</a> &gt;::type</td>
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

<p>Helper which sets its type member to forward_iterator_tag if the category of <span class="doxyComputerOutput">IterT</span> does not derive from bidirectional_iterator_tag, and to bidirectional_iterator_tag otherwise.</p>

<p>Definition at line 549 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/adt/stlextras-h">STLExtras.h</a>.</p>


<div class="doxySectionDef">

## Public Member Typedefs

### type {#a2e36701a503a8f20e834f872f181fb34}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<div class="doxyMemberTemplate">template &lt;typename IterT&gt;</div>
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">using llvm::detail::fwd_or_bidi_tag&lt; IterT &gt;::type =  typename fwd_or_bidi_tag_impl&lt;std::is_base_of&lt;
      std::bidirectional_iterator_tag,
      typename std::iterator_traits&lt;IterT&gt;::iterator_category&gt;::value&gt;::type</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 550 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/adt/stlextras-h">STLExtras.h</a>.</p>

</div>
</div>

</div>

<hr/>

The documentation for this struct was generated from the following file:

<ul>
<li><a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/adt/stlextras-h">STLExtras.h</a></li>
</ul>

<hr/>

<p class="doxyGeneratedBy">Generated via <a href="https://github.com/xpack/doxygen2docusaurus">doxygen2docusaurus</a> by <a href="https://www.doxygen.nl">Doxygen</a> 1.15.0.</p>

</div>
