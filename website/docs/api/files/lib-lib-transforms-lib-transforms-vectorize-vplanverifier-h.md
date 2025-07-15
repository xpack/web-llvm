---

# DO NOT EDIT!
# Automatically generated via doxygen2docusaurus by Doxygen.

slug: /api/files/lib/lib/transforms/lib/transforms/vectorize/vplanverifier-h
custom_edit_url: null
toc_max_heading_level: 4
keywords:
  - doxygen
  - reference
  - file

---

<div class="doxyPage">

# The `VPlanVerifier.h` File Reference

<p>This file declares the class VPlanVerifier, which contains utility functions to check the consistency of a VPlan. <a href="#details">More...</a></p>

## Namespaces Index

<table class="doxyMembersIndex">

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">namespace</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="/web-llvm/docs/api/namespaces/llvm">llvm</a></td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>This is an optimization pass for GlobalISel generic memory operations. <a href="/web-llvm/docs/api/namespaces/llvm/#details">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

</table>

## Description {#details}

<p>This file declares the class VPlanVerifier, which contains utility functions to check the consistency of a VPlan.</p>


<p>This includes the following kinds of invariants:</p>


<ol class="doxyList" type="1">
<li>Region/Block invariants:

<ul class="doxyList ">
<li>Region's entry/exit block must have no predecessors/successors, respectively.</li>
<li>Block's parent must be the region immediately containing the block.</li>
<li>Linked blocks must have a bi-directional link (successor/predecessor).</li>
<li>All predecessors/successors of a block must belong to the same region.</li>
<li>Blocks must have no duplicated successor/predecessor.</li>
</ul></li>
</ol>

<hr/>

<p class="doxyGeneratedBy">Generated via <a href="https://github.com/xpack/doxygen2docusaurus">doxygen2docusaurus</a> by <a href="https://www.doxygen.nl">Doxygen</a> 1.14.0.</p>

</div>
