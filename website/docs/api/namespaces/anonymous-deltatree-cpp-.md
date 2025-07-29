---

# DO NOT EDIT!
# Automatically generated via doxygen2docusaurus by Doxygen.

slug: /api/namespaces/anonymous-deltatree-cpp-
custom_edit_url: null
toc_max_heading_level: 4
keywords:
  - doxygen
  - reference
  - namespace

---

<div class="doxyPage">

# `anonymous{DeltaTree.cpp}` Namespace

<p>The <a href="/web-llvm/docs/api/classes/llvm/deltatree">DeltaTree</a> class is a multiway search tree (BTree) structure with some fancy features. <a href="#details">More...</a></p>

## Definition

<div class="doxyDefinition">
namespace anonymous{DeltaTree.cpp} { ... }
</div>

## Classes Index

<table class="doxyMembersIndex">

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">struct</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="/web-llvm/docs/api/structs/anonymous-deltatree-cpp-/sourcedelta">SourceDelta</a></td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p><a href="/web-llvm/docs/api/structs/anonymous-deltatree-cpp-/sourcedelta">SourceDelta</a> - As code in the original input buffer is added and deleted, <a href="/web-llvm/docs/api/structs/anonymous-deltatree-cpp-/sourcedelta">SourceDelta</a> records are used to keep track of how the input SourceLocation object is mapped into the output buffer. <a href="/web-llvm/docs/api/structs/anonymous-deltatree-cpp-/sourcedelta/#details">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">class</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="/web-llvm/docs/api/classes/anonymous-deltatree-cpp-/deltatreenode">DeltaTreeNode</a></td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p><a href="/web-llvm/docs/api/classes/anonymous-deltatree-cpp-/deltatreenode">DeltaTreeNode</a> - The common part of all nodes. <a href="/web-llvm/docs/api/classes/anonymous-deltatree-cpp-/deltatreenode/#details">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">class</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="/web-llvm/docs/api/classes/anonymous-deltatree-cpp-/deltatreeinteriornode">DeltaTreeInteriorNode</a></td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p><a href="/web-llvm/docs/api/classes/anonymous-deltatree-cpp-/deltatreeinteriornode">DeltaTreeInteriorNode</a> - When isLeaf = false, a node has child pointers. <a href="/web-llvm/docs/api/classes/anonymous-deltatree-cpp-/deltatreeinteriornode/#details">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

</table>

## Description {#details}

<p>The <a href="/web-llvm/docs/api/classes/llvm/deltatree">DeltaTree</a> class is a multiway search tree (BTree) structure with some fancy features.</p>


<p>B-Trees are generally more memory and cache efficient than binary trees, because they store multiple keys/values in each node.</p>


<p><a href="/web-llvm/docs/api/classes/llvm/deltatree">DeltaTree</a> implements a key/value mapping from FileIndex to Delta, allowing fast lookup by FileIndex. However, an added (important) bonus is that it can also efficiently tell us the full accumulated delta for a specific file offset as well, without traversing the whole tree.</p>


<p>The nodes of the tree are made up of instances of two classes: <a href="/web-llvm/docs/api/classes/anonymous-deltatree-cpp-/deltatreenode">DeltaTreeNode</a> and <a href="/web-llvm/docs/api/classes/anonymous-deltatree-cpp-/deltatreeinteriornode">DeltaTreeInteriorNode</a>. The later subclasses the former and adds children pointers. Each node knows the full delta of all entries (recursively) contained inside of it, which allows us to get the full delta implied by a whole subtree in constant time.</p>


<hr/>

<p class="doxyGeneratedBy">Generated via <a href="https://github.com/xpack/doxygen2docusaurus">doxygen2docusaurus</a> by <a href="https://www.doxygen.nl">Doxygen</a> 1.15.0.</p>

</div>
