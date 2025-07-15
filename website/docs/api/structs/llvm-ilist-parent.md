---

# DO NOT EDIT!
# Automatically generated via doxygen2docusaurus by Doxygen.

slug: /api/structs/llvm/ilist-parent
custom_edit_url: null
toc_max_heading_level: 4
keywords:
  - doxygen
  - reference
  - struct

---

<div class="doxyPage">

# The `ilist_parent` Struct Template Reference

<p>Option to add a pointer to this list's owner in every node. <a href="#details">More...</a></p>

## Declaration

<div class="doxyDeclaration">
template &lt;class ParentTy&gt;
struct llvm::ilist_parent&lt;ParentTy&gt; { ... }
</div>

## Included Headers

<div class="doxyIncludesList">#include "<a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/adt/ilist-node-options-h">llvm/ADT/ilist_node_options.h</a>"
</div>

## Description {#details}

<p>Option to add a pointer to this list's owner in every node.</p>


<p>This option causes the <em>ilist_base_node</em> for this list to contain a pointer ParentTy *Parent, returned by <em>ilist_base_node::getNodeBaseParent()</em> and set by <em>ilist_base_node::setNodeBaseParent(ParentTy *Parent)</em>. The parent value is not set automatically; the ilist owner should set itself as the parent of the list sentinel, and the parent should be set on each node inserted into the list. This value is also not used by <em>ilist_node_with_parent::getNodeParent()</em>, but is used by <em>ilist_iterator::getNodeParent()</em>, which allows the parent to be fetched from any valid (non-null) iterator to this list, including the sentinel.</p>


<p>Definition at line 53 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/adt/ilist-node-options-h">ilist_node_options.h</a>.</p>


<hr/>

<p class="doxyGeneratedBy">Generated via <a href="https://github.com/xpack/doxygen2docusaurus">doxygen2docusaurus</a> by <a href="https://www.doxygen.nl">Doxygen</a> 1.14.0.</p>

</div>
