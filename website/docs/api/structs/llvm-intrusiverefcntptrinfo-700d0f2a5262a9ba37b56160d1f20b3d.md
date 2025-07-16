---

# DO NOT EDIT!
# Automatically generated via doxygen2docusaurus by Doxygen.

slug: /api/structs/llvm/intrusiverefcntptrinfo-700d0f2a5262a9ba37b56160d1f20b3d
custom_edit_url: null
toc_max_heading_level: 4
keywords:
  - doxygen
  - reference
  - struct

---

<div class="doxyPage">

# The `IntrusiveRefCntPtrInfo` Struct Template Reference



## Declaration

<div class="doxyDeclaration">
template &lt;typename ImutInfo&gt;
struct llvm::IntrusiveRefCntPtrInfo&lt;ImutAVLTree&lt; ImutInfo &gt;&gt; { ... }
</div>

## Included Headers

<div class="doxyIncludesList">#include "<a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/adt/immutableset-h">llvm/ADT/ImmutableSet.h</a>"
</div>

## Public Static Functions Index

<table class="doxyMembersIndex">

<tr class="doxyMemberIndexTemplate">
<td class="doxyMemberIndexTemplate" colspan="2"><div>template &lt;typename ImutInfo&gt;</div></td>
</tr>
<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemTypeTemplate" align="left" valign="top">static void</td>
<td class="doxyMemberIndexItemNameTemplate" align="left" valign="top"><a href="#abd0517458c589f8c1551eac54d093bbf">retain</a> (ImutAVLTree&lt; ImutInfo &gt; *Tree)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexTemplate">
<td class="doxyMemberIndexTemplate" colspan="2"><div>template &lt;typename ImutInfo&gt;</div></td>
</tr>
<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemTypeTemplate" align="left" valign="top">static void</td>
<td class="doxyMemberIndexItemNameTemplate" align="left" valign="top"><a href="#af75ea76ee1cf62c981ef43d5e7c1d086">release</a> (ImutAVLTree&lt; ImutInfo &gt; *Tree)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexTemplate">
<td class="doxyMemberIndexTemplate" colspan="2"><div>template &lt;typename ImutInfo&gt;</div></td>
</tr>
<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemTypeTemplate" align="left" valign="top">static unsigned</td>
<td class="doxyMemberIndexItemNameTemplate" align="left" valign="top"><a href="/web-llvm/docs/api/structs/llvm/intrusiverefcntptrinfo/#a164f355991617c24c14e4d61cf2787da">useCount</a> (const ImutAVLTree&lt; ImutInfo &gt; *obj)</td>
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


<p>Definition at line 349 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/adt/immutableset-h">ImmutableSet.h</a>.</p>


<div class="doxySectionDef">

## Public Static Functions

### release() {#af75ea76ee1cf62c981ef43d5e7c1d086}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<div class="doxyMemberTemplate">template &lt;typename ImutInfo&gt;</div>
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void llvm::IntrusiveRefCntPtrInfo&lt; ImutAVLTree&lt; ImutInfo &gt; &gt;::release (<a href="/web-llvm/docs/api/classes/llvm/imutavltree">ImutAVLTree</a>&lt; ImutInfo &gt; * Tree)</td>
</tr>
</table>
</td>
<td class="doxyMemberLabelsRight">
<span class="doxyMemberLabels">
<span class="doxyMemberLabel inline">inline</span>
<span class="doxyMemberLabel static">static</span>
</span>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 351 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/adt/immutableset-h">ImmutableSet.h</a>.</p>

</div>
</div>

### retain() {#abd0517458c589f8c1551eac54d093bbf}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<div class="doxyMemberTemplate">template &lt;typename ImutInfo&gt;</div>
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void llvm::IntrusiveRefCntPtrInfo&lt; ImutAVLTree&lt; ImutInfo &gt; &gt;::retain (<a href="/web-llvm/docs/api/classes/llvm/imutavltree">ImutAVLTree</a>&lt; ImutInfo &gt; * Tree)</td>
</tr>
</table>
</td>
<td class="doxyMemberLabelsRight">
<span class="doxyMemberLabels">
<span class="doxyMemberLabel inline">inline</span>
<span class="doxyMemberLabel static">static</span>
</span>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 350 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/adt/immutableset-h">ImmutableSet.h</a>.</p>


<p>Reference <a href="/web-llvm/docs/api/classes/llvm/imutavltree/#a6c0478e059ed72cca5a056192088e662">llvm::ImutAVLTree&lt; ImutInfo &gt;::retain</a>.</p>

</div>
</div>

### useCount() {#a164f355991617c24c14e4d61cf2787da}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<div class="doxyMemberTemplate">template &lt;typename ImutInfo&gt;</div>
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">unsigned llvm::IntrusiveRefCntPtrInfo&lt; ImutAVLTree&lt; ImutInfo &gt; &gt;::useCount (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/imutavltree">ImutAVLTree</a>&lt; ImutInfo &gt; * obj)</td>
</tr>
</table>
</td>
<td class="doxyMemberLabelsRight">
<span class="doxyMemberLabels">
<span class="doxyMemberLabel inline">inline</span>
<span class="doxyMemberLabel static">static</span>
</span>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 162 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/adt/intrusiverefcntptr-h">IntrusiveRefCntPtr.h</a>.</p>

</div>
</div>

</div>

<hr/>

The documentation for this struct was generated from the following files:

<ul>
<li><a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/adt/immutableset-h">ImmutableSet.h</a></li>
<li><a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/adt/intrusiverefcntptr-h">IntrusiveRefCntPtr.h</a></li>
</ul>

<hr/>

<p class="doxyGeneratedBy">Generated via <a href="https://github.com/xpack/doxygen2docusaurus">doxygen2docusaurus</a> by <a href="https://www.doxygen.nl">Doxygen</a> 1.15.0.</p>

</div>
