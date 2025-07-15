---

# DO NOT EDIT!
# Automatically generated via doxygen2docusaurus by Doxygen.

slug: /api/structs/llvm/ilist-sentinel-tracking
custom_edit_url: null
toc_max_heading_level: 4
keywords:
  - doxygen
  - reference
  - struct

---

<div class="doxyPage">

# The `ilist_sentinel_tracking` Struct Template Reference

<p>Option to choose whether to track sentinels. <a href="#details">More...</a></p>

## Declaration

<div class="doxyDeclaration">
template &lt;bool EnableSentinelTracking&gt;
struct llvm::ilist_sentinel_tracking&lt;EnableSentinelTracking&gt; { ... }
</div>

## Included Headers

<div class="doxyIncludesList">#include "<a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/adt/ilist-node-options-h">llvm/ADT/ilist_node_options.h</a>"
</div>

## Description {#details}

<p>Option to choose whether to track sentinels.</p>


<p>This option affects the ABI for the nodes. When not specified explicitly, the ABI depends on LLVM_ENABLE_ABI_BREAKING_CHECKS. Specify explicitly to enable <em><a href="/web-llvm/docs/api/classes/llvm/ilist-node-impl/#a0570092282570244c4d7af86003f0aa9">ilist_node::isSentinel()</a></em>.</p>


<p>Definition at line 26 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/adt/ilist-node-options-h">ilist_node_options.h</a>.</p>


<hr/>

<p class="doxyGeneratedBy">Generated via <a href="https://github.com/xpack/doxygen2docusaurus">doxygen2docusaurus</a> by <a href="https://www.doxygen.nl">Doxygen</a> 1.14.0.</p>

</div>
