---

# DO NOT EDIT!
# Automatically generated via doxygen2docusaurus by Doxygen.

slug: /api/structs/llvm/detail/zip-enumerator
custom_edit_url: null
toc_max_heading_level: 4
keywords:
  - doxygen
  - reference
  - struct

---

<div class="doxyPage">

# `zip_enumerator` Struct Template

<p>Zippy iterator that uses the second iterator for comparisons. <a href="#details">More...</a></p>

## Declaration

<div class="doxyDeclaration">
template &lt;typename... Iters&gt;
struct llvm::detail::zip_enumerator&lt;Iters&gt; { ... }
</div>

## Included Headers

<div class="doxyIncludesList">#include "<a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/adt/stlextras-h">llvm/ADT/STLExtras.h</a>"
</div>

## Base struct

<table class="doxyMembersIndex">

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">struct</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="/web-llvm/docs/api/structs/llvm/detail/zip-common">zip_common&lt;ZipType, ReferenceTupleType, Iters&gt;</a></td>
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
<td class="doxyMemberIndexTemplate" colspan="2"><div>template &lt;typename... Iters&gt;</div></td>
</tr>
<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemTypeTemplate" align="left" valign="top">bool</td>
<td class="doxyMemberIndexItemNameTemplate" align="left" valign="top"><a href="#aed8e35a6544f711b7ac7382d6364f077">operator==</a> (const zip_enumerator &amp;Other) const</td>
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

<p>Zippy iterator that uses the second iterator for comparisons.</p>


<p>For the increment to be safe, the second range has to be the shortest. Returns <span class="doxyComputerOutput"><a href="/web-llvm/docs/api/structs/llvm/detail/enumerator-result">enumerator_result</a></span> on dereference to provide <span class="doxyComputerOutput">.index()</span> and <span class="doxyComputerOutput">.<a href="/web-llvm/docs/api/namespaces/llvm/detail/#a3fe429695b1d6a60635b1e490092037e">value()</a></span> member functions. Note: Because the dereference operator returns <span class="doxyComputerOutput"><a href="/web-llvm/docs/api/structs/llvm/detail/enumerator-result">enumerator_result</a></span> as a value instead of a reference and does not strictly conform to the C++17's definition of forward iterator. However, it satisfies all the forward_iterator requirements that the <span class="doxyComputerOutput"><a href="/web-llvm/docs/api/structs/llvm/detail/zip-common">zip_common</a></span> and <span class="doxyComputerOutput">zippy</span> depend on and fully conforms to the C++20 definition of forward iterator. This is similar to <span class="doxyComputerOutput">std::vector&lt;bool&gt;::iterator</span> that returns bit reference wrappers on dereference.</p>


<p>Definition at line 2269 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/adt/stlextras-h">STLExtras.h</a>.</p>


<div class="doxySectionDef">

## Public Operators

### operator==() {#aed8e35a6544f711b7ac7382d6364f077}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<div class="doxyMemberTemplate">template &lt;typename... Iters&gt;</div>
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool llvm::detail::zip_enumerator&lt; Iters &gt;::operator== (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/structs/llvm/detail/zip-enumerator">zip_enumerator</a> &amp; Other)</td>
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



<p>Definition at line 2275 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/adt/stlextras-h">STLExtras.h</a>.</p>


<p>References <a href="/web-llvm/docs/api/structs/llvm/detail/zip-common/#a6fc64436ed7f0c3434c241b4228ff16a">llvm::detail::zip_common&lt; zip_enumerator&lt; Iters... &gt;, EnumeratorTupleType&lt; Iters... &gt;, Iters... &gt;::iterators</a> and <a href="/web-llvm/docs/api/namespaces/llvm/#a9eb4f5b98b70ee4fab9614ed58282c1fa6311ae17c1ee52b36e68aaf4ad066387">llvm::Other</a>.</p>

</div>
</div>

</div>

<hr/>

The documentation for this struct was generated from the following file:

<ul>
<li><a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/adt/stlextras-h">STLExtras.h</a></li>
</ul>

<hr/>

<p class="doxyGeneratedBy">Generated via <a href="https://xpack.github.io/doxygen2docusaurus">doxygen2docusaurus</a> 2.0.0 by <a href="https://www.doxygen.nl">Doxygen</a> 1.15.0.</p>

</div>
