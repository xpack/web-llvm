---

# DO NOT EDIT!
# Automatically generated via doxygen2docusaurus by Doxygen.

slug: /api/structs/anonymous-memoryssa-cpp-/renamepassdata
custom_edit_url: null
toc_max_heading_level: 4
keywords:
  - doxygen
  - reference
  - struct

---

<div class="doxyPage">

# The `RenamePassData` Struct Reference



## Declaration

<div class="doxyDeclaration">
struct anonymous{MemorySSA.cpp}::RenamePassData { ... }
</div>

## Public Constructors Index

<table class="doxyMembersIndex">

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a2e45ec6a03b57985e4226642384e7a74">RenamePassData</a> (DomTreeNode *D, DomTreeNode::const_iterator It, MemoryAccess *M)</td>
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

## Public Member Functions Index

<table class="doxyMembersIndex">

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">void</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ad690a03dc06c2db9fc9ae0ba4750c313">swap</a> (RenamePassData &amp;RHS)</td>
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

## Public Member Attributes Index

<table class="doxyMembersIndex">

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/namespaces/llvm/#a58b9df85470fc4e2a8066ff6a62e5a34">DomTreeNode</a> *</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a30d2d5c7bd77707f811c2f2b99ec4669">DTN</a></td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/domtreenodebase/#ac7d6c8d6097d77418565f21650836d66">DomTreeNode::const_iterator</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a8cee6cbbf655538a4a7fbee3a9db8d81">ChildIt</a></td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/memoryaccess">MemoryAccess</a> *</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ad86a516fd404e8da7a1d7053031dbc80">IncomingVal</a></td>
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


<p>Definition at line 968 of file <a href="/web-llvm/docs/api/files/lib/lib/analysis/memoryssa-cpp">MemorySSA.cpp</a>.</p>


<div class="doxySectionDef">

## Public Constructors

### RenamePassData() {#a2e45ec6a03b57985e4226642384e7a74}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">anonymous{MemorySSA.cpp}::RenamePassData::RenamePassData (<a href="/web-llvm/docs/api/namespaces/llvm/#a58b9df85470fc4e2a8066ff6a62e5a34">DomTreeNode</a> * D, <a href="/web-llvm/docs/api/classes/llvm/domtreenodebase/#ac7d6c8d6097d77418565f21650836d66">DomTreeNode::const_iterator</a> It, <a href="/web-llvm/docs/api/classes/llvm/memoryaccess">MemoryAccess</a> * M)</td>
</tr>
</table>
</td>
<td class="doxyMemberLabelsRight">
<span class="doxyMemberLabels">
<span class="doxyMemberLabel inline">inline</span>
</span>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 973 of file <a href="/web-llvm/docs/api/files/lib/lib/analysis/memoryssa-cpp">MemorySSA.cpp</a>.</p>


<p>References <a href="#a8cee6cbbf655538a4a7fbee3a9db8d81">ChildIt</a>, <a href="/web-llvm/docs/api/files/lib/lib/ir/builtingcs-cpp/#a6a9f043784cf87001c84980afa76da82">D</a>, <a href="#a30d2d5c7bd77707f811c2f2b99ec4669">DTN</a> and <a href="#ad86a516fd404e8da7a1d7053031dbc80">IncomingVal</a>.</p>


<p>Referenced by <a href="#ad690a03dc06c2db9fc9ae0ba4750c313">swap</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Public Member Functions

### swap() {#ad690a03dc06c2db9fc9ae0ba4750c313}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void anonymous{MemorySSA.cpp}::RenamePassData::swap (<a href="/web-llvm/docs/api/structs/anonymous-memoryssa-cpp-/renamepassdata">RenamePassData</a> &amp; RHS)</td>
</tr>
</table>
</td>
<td class="doxyMemberLabelsRight">
<span class="doxyMemberLabels">
<span class="doxyMemberLabel inline">inline</span>
</span>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 977 of file <a href="/web-llvm/docs/api/files/lib/lib/analysis/memoryssa-cpp">MemorySSA.cpp</a>.</p>


<p>References <a href="#a8cee6cbbf655538a4a7fbee3a9db8d81">ChildIt</a>, <a href="#a30d2d5c7bd77707f811c2f2b99ec4669">DTN</a>, <a href="#ad86a516fd404e8da7a1d7053031dbc80">IncomingVal</a>, <a href="#a2e45ec6a03b57985e4226642384e7a74">RenamePassData</a> and <a href="/web-llvm/docs/api/namespaces/std/#ab8424022895aee3e366fb9a32f2883cb">std::swap</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Public Member Attributes

### ChildIt {#a8cee6cbbf655538a4a7fbee3a9db8d81}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">DomTreeNode::const_iterator anonymous{MemorySSA.cpp}::RenamePassData::ChildIt</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 970 of file <a href="/web-llvm/docs/api/files/lib/lib/analysis/memoryssa-cpp">MemorySSA.cpp</a>.</p>


<p>Referenced by <a href="#a2e45ec6a03b57985e4226642384e7a74">RenamePassData</a> and <a href="#ad690a03dc06c2db9fc9ae0ba4750c313">swap</a>.</p>

</div>
</div>

### DTN {#a30d2d5c7bd77707f811c2f2b99ec4669}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">DomTreeNode* anonymous{MemorySSA.cpp}::RenamePassData::DTN</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 969 of file <a href="/web-llvm/docs/api/files/lib/lib/analysis/memoryssa-cpp">MemorySSA.cpp</a>.</p>


<p>Referenced by <a href="#a2e45ec6a03b57985e4226642384e7a74">RenamePassData</a> and <a href="#ad690a03dc06c2db9fc9ae0ba4750c313">swap</a>.</p>

</div>
</div>

### IncomingVal {#ad86a516fd404e8da7a1d7053031dbc80}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">MemoryAccess* anonymous{MemorySSA.cpp}::RenamePassData::IncomingVal</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 971 of file <a href="/web-llvm/docs/api/files/lib/lib/analysis/memoryssa-cpp">MemorySSA.cpp</a>.</p>


<p>Referenced by <a href="#a2e45ec6a03b57985e4226642384e7a74">RenamePassData</a> and <a href="#ad690a03dc06c2db9fc9ae0ba4750c313">swap</a>.</p>

</div>
</div>

</div>

<hr/>

The documentation for this struct was generated from the following file:

<ul>
<li><a href="/web-llvm/docs/api/files/lib/lib/analysis/memoryssa-cpp">MemorySSA.cpp</a></li>
</ul>

<hr/>

<p class="doxyGeneratedBy">Generated via <a href="https://github.com/xpack/doxygen2docusaurus">doxygen2docusaurus</a> by <a href="https://www.doxygen.nl">Doxygen</a> 1.15.0.</p>

</div>
