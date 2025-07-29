---

# DO NOT EDIT!
# Automatically generated via doxygen2docusaurus by Doxygen.

slug: /api/structs/anonymous-selectoptimize-cpp-/selectoptimizeimpl/costinfo
custom_edit_url: null
toc_max_heading_level: 4
keywords:
  - doxygen
  - reference
  - struct

---

<div class="doxyPage">

# `CostInfo` Struct



## Declaration

<div class="doxyDeclaration">
struct anonymous{SelectOptimize.cpp}::SelectOptimizeImpl::CostInfo { ... }
</div>

## Public Member Attributes Index

<table class="doxyMembersIndex">

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/anonymous-selectoptimize-cpp-/selectoptimizeimpl/#a7e50b359af6e42ca84e7152e049da6e5">Scaled64</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a9b2869ffcbec4ca48f31c4c1c673f0a8">PredCost</a></td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Predicated cost (with selects as conditional moves). <a href="#a9b2869ffcbec4ca48f31c4c1c673f0a8">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/anonymous-selectoptimize-cpp-/selectoptimizeimpl/#a7e50b359af6e42ca84e7152e049da6e5">Scaled64</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a003b24fa51e57f72daee010cd11d9b75">NonPredCost</a></td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Non-predicated cost (with selects converted to branches). <a href="#a003b24fa51e57f72daee010cd11d9b75">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

</table>


<p>Definition at line 120 of file <a href="/web-llvm/docs/api/files/lib/lib/codegen/selectoptimize-cpp">SelectOptimize.cpp</a>.</p>


<div class="doxySectionDef">

## Public Member Attributes

### NonPredCost {#a003b24fa51e57f72daee010cd11d9b75}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">Scaled64 anonymous{SelectOptimize.cpp}::SelectOptimizeImpl::CostInfo::NonPredCost</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Non-predicated cost (with selects converted to branches).</p>

<p>Definition at line 124 of file <a href="/web-llvm/docs/api/files/lib/lib/codegen/selectoptimize-cpp">SelectOptimize.cpp</a>.</p>

</div>
</div>

### PredCost {#a9b2869ffcbec4ca48f31c4c1c673f0a8}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">Scaled64 anonymous{SelectOptimize.cpp}::SelectOptimizeImpl::CostInfo::PredCost</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Predicated cost (with selects as conditional moves).</p>

<p>Definition at line 122 of file <a href="/web-llvm/docs/api/files/lib/lib/codegen/selectoptimize-cpp">SelectOptimize.cpp</a>.</p>

</div>
</div>

</div>

<hr/>

The documentation for this struct was generated from the following file:

<ul>
<li><a href="/web-llvm/docs/api/files/lib/lib/codegen/selectoptimize-cpp">SelectOptimize.cpp</a></li>
</ul>

<hr/>

<p class="doxyGeneratedBy">Generated via <a href="https://github.com/xpack/doxygen2docusaurus">doxygen2docusaurus</a> by <a href="https://www.doxygen.nl">Doxygen</a> 1.15.0.</p>

</div>
