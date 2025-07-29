---

# DO NOT EDIT!
# Automatically generated via doxygen2docusaurus by Doxygen.

slug: /api/files/include/include/llvm/include/llvm/support/optimizedstructlayout-h
custom_edit_url: null
toc_max_heading_level: 4
keywords:
  - doxygen
  - reference
  - file

---

<div class="doxyPage">

# `OptimizedStructLayout.h` File

<p>This file provides an interface for laying out a sequence of fields as a struct in a way that attempts to minimizes the total space requirements of the struct while still satisfying the layout requirements of the individual fields. <a href="#details">More...</a></p>

## Included Headers

<div class="doxyIncludesList">#include "<a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/support/alignment-h">llvm/Support/Alignment.h</a>"
#include "<a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/adt/arrayref-h">llvm/ADT/ArrayRef.h</a>"
#include &lt;utility&gt;
</div>

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

## Classes Index

<table class="doxyMembersIndex">

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">struct</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="/web-llvm/docs/api/structs/llvm/optimizedstructlayoutfield">OptimizedStructLayoutField</a></td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>A field in a structure. <a href="/web-llvm/docs/api/structs/llvm/optimizedstructlayoutfield/#details">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

</table>

## Description {#details}

<p>This file provides an interface for laying out a sequence of fields as a struct in a way that attempts to minimizes the total space requirements of the struct while still satisfying the layout requirements of the individual fields.</p>


<p>The resulting layout may be substantially more compact than simply laying out the fields in their original order.</p>


<p>Fields may be pre-assigned fixed offsets. They may also be given sizes that are not multiples of their alignments. There is no currently no way to describe that a field has interior padding that other fields may be allocated into.</p>


<p>This algorithm does not claim to be "optimal" for several reasons:</p>


<ul class="doxyList ">
<li>First, it does not guarantee that the result is minimal in size. There is no known efficient algoorithm to achieve minimality for unrestricted inputs. Nonetheless, this algorithm</li>
<li>Second, there are other ways that a struct layout could be optimized besides space usage, such as locality. This layout may have a mixed impact on locality: less overall memory may be used, but adjacent fields in the original array may be moved further from one another.</li>
</ul>

<hr/>

<p class="doxyGeneratedBy">Generated via <a href="https://github.com/xpack/doxygen2docusaurus">doxygen2docusaurus</a> by <a href="https://www.doxygen.nl">Doxygen</a> 1.15.0.</p>

</div>
