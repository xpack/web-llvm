---

# DO NOT EDIT!
# Automatically generated via doxygen2docusaurus by Doxygen.

slug: /api/structs/llvm/ilist-iterator-bits
custom_edit_url: null
toc_max_heading_level: 4
keywords:
  - doxygen
  - reference
  - struct

---

<div class="doxyPage">

# The `ilist_iterator_bits` Struct Template Reference

<p>Option to add extra bits to the <a href="/web-llvm/docs/api/classes/llvm/ilist-iterator">ilist_iterator</a>. <a href="#details">More...</a></p>

## Declaration

<div class="doxyDeclaration">
template &lt;bool ExtraIteratorBits&gt;
struct llvm::ilist_iterator_bits&lt;ExtraIteratorBits&gt; { ... }
</div>

## Included Headers

<div class="doxyIncludesList">#include "<a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/adt/ilist-node-options-h">llvm/ADT/ilist_node_options.h</a>"
</div>

## Description {#details}

<p>Option to add extra bits to the <a href="/web-llvm/docs/api/classes/llvm/ilist-iterator">ilist_iterator</a>.</p>


<p>Some use-cases (debug-info) need to know whether a position is intended to be half-open or fully open, i.e. whether to include any immediately adjacent debug-info in an operation. This option adds two bits to the iterator class to store that information.</p>


<p>Definition at line 40 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/adt/ilist-node-options-h">ilist_node_options.h</a>.</p>


<hr/>

<p class="doxyGeneratedBy">Generated via <a href="https://github.com/xpack/doxygen2docusaurus">doxygen2docusaurus</a> by <a href="https://www.doxygen.nl">Doxygen</a> 1.14.0.</p>

</div>
