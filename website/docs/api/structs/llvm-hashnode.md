---

# DO NOT EDIT!
# Automatically generated via doxygen2docusaurus by Doxygen.

slug: /api/structs/llvm/hashnode
custom_edit_url: null
toc_max_heading_level: 4
keywords:
  - doxygen
  - reference
  - struct

---

<div class="doxyPage">

# The `HashNode` Struct Reference

<p>A <a href="/web-llvm/docs/api/structs/llvm/hashnode">HashNode</a> is an entry in an <a href="/web-llvm/docs/api/classes/llvm/outlinedhashtree">OutlinedHashTree</a>, holding a hash value and a collection of Successors (other HashNodes). <a href="#details">More...</a></p>

## Declaration

<div class="doxyDeclaration">
struct llvm::HashNode { ... }
</div>

## Included Headers

<div class="doxyIncludesList">#include "<a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/cgdata/outlinedhashtree-h">llvm/CGData/OutlinedHashTree.h</a>"
</div>

## Public Member Attributes Index

<table class="doxyMembersIndex">

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/namespaces/llvm/#a3f07bd5ee30b6a57ddc214f64d5fd941">stable_hash</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#adf900abae6895805cd64c155430807fe">Hash</a> = 0</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>The hash value of the node. <a href="#adf900abae6895805cd64c155430807fe">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">std::optional&lt; unsigned &gt;</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a66632316e3bbfd1f40384f637f68e625">Terminals</a></td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>The number of terminals in the sequence ending at this node. <a href="#a66632316e3bbfd1f40384f637f68e625">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">std::unordered_map&lt; <a href="/web-llvm/docs/api/namespaces/llvm/#a3f07bd5ee30b6a57ddc214f64d5fd941">stable_hash</a>, std::unique_ptr&lt; <a href="/web-llvm/docs/api/structs/llvm/hashnode">HashNode</a> &gt; &gt;</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a1a31b051ee904b573a699443959ce8b6">Successors</a></td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>The successors of this node. <a href="#a1a31b051ee904b573a699443959ce8b6">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

</table>

## Description {#details}

<p>A <a href="/web-llvm/docs/api/structs/llvm/hashnode">HashNode</a> is an entry in an <a href="/web-llvm/docs/api/classes/llvm/outlinedhashtree">OutlinedHashTree</a>, holding a hash value and a collection of Successors (other HashNodes).</p>


<p>If a <a href="/web-llvm/docs/api/structs/llvm/hashnode">HashNode</a> has a positive terminal value (Terminals &gt; 0), it signifies the end of a hash sequence with that occurrence count.</p>


<p>Definition at line 32 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/cgdata/outlinedhashtree-h">OutlinedHashTree.h</a>.</p>


<div class="doxySectionDef">

## Public Member Attributes

### Hash {#adf900abae6895805cd64c155430807fe}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">stable_hash llvm::HashNode::Hash = 0</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>The hash value of the node.</p>

<p>Definition at line 34 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/cgdata/outlinedhashtree-h">OutlinedHashTree.h</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/classes/llvm/outlinedhashtree/#abc2686042d37b5df938df13eef50cd6e">llvm::OutlinedHashTree::insert</a> and <a href="/web-llvm/docs/api/classes/llvm/outlinedhashtree/#a9d8f153a3d47acbb643fde3d1f215bcc">llvm::OutlinedHashTree::merge</a>.</p>

</div>
</div>

### Successors {#a1a31b051ee904b573a699443959ce8b6}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">std::unordered_map&lt;stable_hash, std::unique_ptr&lt;HashNode&gt; &gt; llvm::HashNode::Successors</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>The successors of this node.</p>


<p>We don't use <a href="/web-llvm/docs/api/classes/llvm/densemap">DenseMap</a> as a <a href="/web-llvm/docs/api/namespaces/llvm/#a3f07bd5ee30b6a57ddc214f64d5fd941">stable_hash</a> value can be tombstone.</p>


<p>Definition at line 39 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/cgdata/outlinedhashtree-h">OutlinedHashTree.h</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/classes/llvm/outlinedhashtree/#a1d79a1e68b8960755f9f0bf4aceb1ae1">llvm::OutlinedHashTree::clear</a>, <a href="/web-llvm/docs/api/classes/llvm/outlinedhashtree/#a6c408d99704ccf35333069847a091eeb">llvm::OutlinedHashTree::find</a> and <a href="/web-llvm/docs/api/classes/llvm/outlinedhashtree/#abc2686042d37b5df938df13eef50cd6e">llvm::OutlinedHashTree::insert</a>.</p>

</div>
</div>

### Terminals {#a66632316e3bbfd1f40384f637f68e625}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">std::optional&lt;unsigned&gt; llvm::HashNode::Terminals</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>The number of terminals in the sequence ending at this node.</p>

<p>Definition at line 36 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/cgdata/outlinedhashtree-h">OutlinedHashTree.h</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/classes/llvm/outlinedhashtree/#a6c408d99704ccf35333069847a091eeb">llvm::OutlinedHashTree::find</a>, <a href="/web-llvm/docs/api/files/lib/lib/codegen/machineoutliner-cpp/#af08090d2b358f57cbf6b3448a5ff2676">getMatchedEntries</a> and <a href="/web-llvm/docs/api/classes/llvm/outlinedhashtree/#abc2686042d37b5df938df13eef50cd6e">llvm::OutlinedHashTree::insert</a>.</p>

</div>
</div>

</div>

<hr/>

The documentation for this struct was generated from the following file:

<ul>
<li><a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/cgdata/outlinedhashtree-h">OutlinedHashTree.h</a></li>
</ul>

<hr/>

<p class="doxyGeneratedBy">Generated via <a href="https://github.com/xpack/doxygen2docusaurus">doxygen2docusaurus</a> by <a href="https://www.doxygen.nl">Doxygen</a> 1.15.0.</p>

</div>
