---

# DO NOT EDIT!
# Automatically generated via doxygen2docusaurus by Doxygen.

slug: /api/structs/llvm/detail/ptrusevisitorbase/usetovisit
custom_edit_url: null
toc_max_heading_level: 4
keywords:
  - doxygen
  - reference
  - struct

---

<div class="doxyPage">

# The `UseToVisit` Struct Reference

<p>A struct of the data needed to visit a particular use. <a href="#details">More...</a></p>

## Declaration

<div class="doxyDeclaration">
struct llvm::detail::PtrUseVisitorBase::UseToVisit { ... }
</div>

## Included Headers

<div class="doxyIncludesList">#include "<a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/analysis/ptrusevisitor-h">llvm/Analysis/PtrUseVisitor.h</a>"
</div>

## Public Member Typedefs Index

<table class="doxyMembersIndex">

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">using</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a87b66e7600e3ba5d44d7c79fbdf7c969">UseAndIsOffsetKnownPair</a> = <a href="/web-llvm/docs/api/classes/llvm/pointerintpair">PointerIntPair</a>&lt; <a href="/web-llvm/docs/api/classes/llvm/use">Use</a> *, 1, bool &gt;</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="#a87b66e7600e3ba5d44d7c79fbdf7c969">UseAndIsOffsetKnownPair</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a28f946ac353f6118bb637201ff1d5658">UseAndIsOffsetKnown</a></td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/apint">APInt</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a896685128ccfe72a1fe8053ba05b52b7">Offset</a></td>
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

## Description {#details}

<p>A struct of the data needed to visit a particular use.</p>


<p>This is used to maintain a worklist fo to-visit uses. This is used to make the visit be iterative rather than recursive.</p>


<p>Definition at line 132 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/analysis/ptrusevisitor-h">PtrUseVisitor.h</a>.</p>


<div class="doxySectionDef">

## Public Member Typedefs

### UseAndIsOffsetKnownPair {#a87b66e7600e3ba5d44d7c79fbdf7c969}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">using llvm::detail::PtrUseVisitorBase::UseToVisit::UseAndIsOffsetKnownPair =  PointerIntPair&lt;Use *, 1, bool&gt;</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 133 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/analysis/ptrusevisitor-h">PtrUseVisitor.h</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Public Member Attributes

### Offset {#a896685128ccfe72a1fe8053ba05b52b7}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">APInt llvm::detail::PtrUseVisitorBase::UseToVisit::Offset</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 136 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/analysis/ptrusevisitor-h">PtrUseVisitor.h</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/classes/llvm/ptrusevisitor/#a764cd98e9a2d1c1fdfb40aa63ef17385">llvm::PtrUseVisitor&lt; ArgUseChecker &gt;::visitPtr</a>.</p>

</div>
</div>

### UseAndIsOffsetKnown {#a28f946ac353f6118bb637201ff1d5658}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">UseAndIsOffsetKnownPair llvm::detail::PtrUseVisitorBase::UseToVisit::UseAndIsOffsetKnown</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 135 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/analysis/ptrusevisitor-h">PtrUseVisitor.h</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/structs/anonymous-nvptxlowerargs-cpp-/argusechecker/#a6d53db8820f5704f0678827ac5314fcb">anonymous{NVPTXLowerArgs.cpp}::ArgUseChecker::visitArgPtr</a> and <a href="/web-llvm/docs/api/classes/llvm/ptrusevisitor/#a764cd98e9a2d1c1fdfb40aa63ef17385">llvm::PtrUseVisitor&lt; ArgUseChecker &gt;::visitPtr</a>.</p>

</div>
</div>

</div>

<hr/>

The documentation for this struct was generated from the following file:

<ul>
<li><a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/analysis/ptrusevisitor-h">PtrUseVisitor.h</a></li>
</ul>

<hr/>

<p class="doxyGeneratedBy">Generated via <a href="https://github.com/xpack/doxygen2docusaurus">doxygen2docusaurus</a> by <a href="https://www.doxygen.nl">Doxygen</a> 1.15.0.</p>

</div>
