---

# DO NOT EDIT!
# Automatically generated via doxygen2docusaurus by Doxygen.

slug: /api/structs/llvm/ilist-detail/is-valid-option
custom_edit_url: null
toc_max_heading_level: 4
keywords:
  - doxygen
  - reference
  - struct

---

<div class="doxyPage">

# `is_valid_option` Struct Template

<p><a href="/web-llvm/docs/api/namespaces/llvm/check">Check</a> whether an option is valid. <a href="#details">More...</a></p>

## Declaration

<div class="doxyDeclaration">
template &lt;class Option&gt;
struct llvm::ilist_detail::is_valid_option&lt;Option&gt; { ... }
</div>

## Included Headers

<div class="doxyIncludesList">#include "<a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/adt/ilist-node-options-h">llvm/ADT/ilist_node_options.h</a>"
</div>

## Base struct

<table class="doxyMembersIndex">

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">struct</td>
<td class="doxyMemberIndexItemName" align="left" valign="top">std::false_type</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

</table>

## Description {#details}

<p><a href="/web-llvm/docs/api/namespaces/llvm/check">Check</a> whether an option is valid.</p>


<p>The steps for adding and enabling a new ilist option include:</p>


<ul class="doxyList ">
<li>define the option, ilist_foo&lt;Bar&gt;, above;</li>
<li>add new parameters for Bar to <em><a href="/web-llvm/docs/api/structs/llvm/ilist-detail/node-options">ilist_detail::node_options</a></em>;</li>
<li>add an extraction meta-function, ilist_detail::extract_foo;</li>
<li>call extract_foo from <em><a href="/web-llvm/docs/api/structs/llvm/ilist-detail/compute-node-options">ilist_detail::compute_node_options</a></em> and pass it into <em><a href="/web-llvm/docs/api/structs/llvm/ilist-detail/node-options">ilist_detail::node_options</a></em>; and</li>
<li>specialize <span class="doxyComputerOutput"><a href="/web-llvm/docs/api/structs/llvm/ilist-detail/is-valid-option">is_valid_option&lt;ilist_foo&lt;Bar&gt;&gt;</a></span> to inherit from <span class="doxyComputerOutput">std::true_type</span> to get static assertions passing in <em><a href="/web-llvm/docs/api/classes/llvm/simple-ilist">simple_ilist</a></em> and <em><a href="/web-llvm/docs/api/classes/llvm/ilist-node">ilist_node</a></em>.</li>
</ul>

<p>Definition at line 75 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/adt/ilist-node-options-h">ilist_node_options.h</a>.</p>


<hr/>

<p class="doxyGeneratedBy">Generated via <a href="https://xpack.github.io/doxygen2docusaurus">doxygen2docusaurus</a> 2.0.0 by <a href="https://www.doxygen.nl">Doxygen</a> 1.15.0.</p>

</div>
