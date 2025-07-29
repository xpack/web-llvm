---

# DO NOT EDIT!
# Automatically generated via doxygen2docusaurus by Doxygen.

slug: /api/structs/llvm/foldingsetbase/foldingsetinfo
custom_edit_url: null
toc_max_heading_level: 4
keywords:
  - doxygen
  - reference
  - struct

---

<div class="doxyPage">

# `FoldingSetInfo` Struct

<p>Functions provided by the derived class to compute folding properties. <a href="#details">More...</a></p>

## Declaration

<div class="doxyDeclaration">
struct llvm::FoldingSetBase::FoldingSetInfo { ... }
</div>

## Included Headers

<div class="doxyIncludesList">#include "<a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/adt/foldingset-h">llvm/ADT/FoldingSet.h</a>"
</div>

## Public Member Attributes Index

<table class="doxyMembersIndex">

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">void(*</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a96cd1afd2c8b95fe03acfe85d20fa990">GetNodeProfile</a>)(const FoldingSetBase *Self, Node *N, FoldingSetNodeID &ID)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>GetNodeProfile - Instantiations of the <a href="/web-llvm/docs/api/classes/llvm/foldingset">FoldingSet</a> template implement this function to gather data bits for the given node. <a href="#a96cd1afd2c8b95fe03acfe85d20fa990">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">bool(*</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a842b8d1fe91d868a5b5bd9fb9694d87f">NodeEquals</a>)(const FoldingSetBase *Self, Node *N, const FoldingSetNodeID &ID, unsigned IDHash, FoldingSetNodeID &TempID)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>NodeEquals - Instantiations of the <a href="/web-llvm/docs/api/classes/llvm/foldingset">FoldingSet</a> template implement this function to compare the given node with the given <a href="/web-llvm/docs/api/namespaces/llvm/callingconv/#abdf8cf606905c10634e831390981b0ed">ID</a>. <a href="#a842b8d1fe91d868a5b5bd9fb9694d87f">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">unsigned(*</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a5a25050bd86d0d67cfea0494ac005da1">ComputeNodeHash</a>)(const FoldingSetBase *Self, Node *N, FoldingSetNodeID &TempID)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>ComputeNodeHash - Instantiations of the <a href="/web-llvm/docs/api/classes/llvm/foldingset">FoldingSet</a> template implement this function to compute a hash value for the given node. <a href="#a5a25050bd86d0d67cfea0494ac005da1">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

</table>

## Description {#details}

<p>Functions provided by the derived class to compute folding properties.</p>


<p>This is effectively a vtable for <a href="/web-llvm/docs/api/classes/llvm/foldingsetbase">FoldingSetBase</a>, except that we don't actually store a pointer to it in the object.</p>


<p>Definition at line 172 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/adt/foldingset-h">FoldingSet.h</a>.</p>


<div class="doxySectionDef">

## Public Member Attributes

### ComputeNodeHash {#a5a25050bd86d0d67cfea0494ac005da1}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">unsigned(* llvm::FoldingSetBase::FoldingSetInfo::ComputeNodeHash) (const FoldingSetBase *Self, Node *N, FoldingSetNodeID &amp;TempID)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>ComputeNodeHash - Instantiations of the <a href="/web-llvm/docs/api/classes/llvm/foldingset">FoldingSet</a> template implement this function to compute a hash value for the given node.</p>

<p>Definition at line 186 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/adt/foldingset-h">FoldingSet.h</a>.</p>

</div>
</div>

### GetNodeProfile {#a96cd1afd2c8b95fe03acfe85d20fa990}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void(* llvm::FoldingSetBase::FoldingSetInfo::GetNodeProfile) (const FoldingSetBase *Self, Node *N, FoldingSetNodeID &amp;ID)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>GetNodeProfile - Instantiations of the <a href="/web-llvm/docs/api/classes/llvm/foldingset">FoldingSet</a> template implement this function to gather data bits for the given node.</p>

<p>Definition at line 175 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/adt/foldingset-h">FoldingSet.h</a>.</p>

</div>
</div>

### NodeEquals {#a842b8d1fe91d868a5b5bd9fb9694d87f}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool(* llvm::FoldingSetBase::FoldingSetInfo::NodeEquals) (const FoldingSetBase *Self, Node *N, const FoldingSetNodeID &amp;ID, unsigned IDHash, FoldingSetNodeID &amp;TempID)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>NodeEquals - Instantiations of the <a href="/web-llvm/docs/api/classes/llvm/foldingset">FoldingSet</a> template implement this function to compare the given node with the given <a href="/web-llvm/docs/api/namespaces/llvm/callingconv/#abdf8cf606905c10634e831390981b0ed">ID</a>.</p>

<p>Definition at line 180 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/adt/foldingset-h">FoldingSet.h</a>.</p>

</div>
</div>

</div>

<hr/>

The documentation for this struct was generated from the following file:

<ul>
<li><a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/adt/foldingset-h">FoldingSet.h</a></li>
</ul>

<hr/>

<p class="doxyGeneratedBy">Generated via <a href="https://github.com/xpack/doxygen2docusaurus">doxygen2docusaurus</a> by <a href="https://www.doxygen.nl">Doxygen</a> 1.15.0.</p>

</div>
