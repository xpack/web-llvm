---

# DO NOT EDIT!
# Automatically generated via doxygen2docusaurus by Doxygen.

slug: /api/structs/llvm/hashing/detail/is-hashable-data-c5ff1c17472038b6f5efad36061925b9
custom_edit_url: null
toc_max_heading_level: 4
keywords:
  - doxygen
  - reference
  - struct

---

<div class="doxyPage">

# `is_hashable_data` Struct Template



## Declaration

<div class="doxyDeclaration">
template &lt;typename T, typename U&gt;
struct llvm::hashing::detail::is_hashable_data&lt;std::pair&lt; T, U &gt;&gt; { ... }
</div>

## Included Headers

<div class="doxyIncludesList">#include "<a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/adt/hashing-h">llvm/ADT/Hashing.h</a>"
</div>

## Base structs

<table class="doxyMembersIndex">

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">struct</td>
<td class="doxyMemberIndexItemName" align="left" valign="top">std::integral_constant&lt; bool,((is_integral_or_enum&lt; T &gt;::value||std::is_pointer&lt; T &gt;::value) &amp;&amp;64 % sizeof(T)==0)&gt;</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">struct</td>
<td class="doxyMemberIndexItemName" align="left" valign="top">std::integral_constant&lt; bool,(is_hashable_data&lt; T &gt;::value &amp;&amp;is_hashable_data&lt; U &gt;::value &amp;&amp;(sizeof(T)+sizeof(U))==sizeof(std::pair&lt; T, U &gt;))&gt;</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

</table>


<p>Definition at line 344 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/adt/hashing-h">Hashing.h</a>.</p>


<hr/>

<p class="doxyGeneratedBy">Generated via <a href="https://xpack.github.io/doxygen2docusaurus">doxygen2docusaurus</a> 2.0.0 by <a href="https://www.doxygen.nl">Doxygen</a> 1.15.0.</p>

</div>
