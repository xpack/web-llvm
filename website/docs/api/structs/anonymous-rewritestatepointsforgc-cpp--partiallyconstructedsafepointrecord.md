---

# DO NOT EDIT!
# Automatically generated via doxygen2docusaurus by Doxygen.

slug: /api/structs/anonymous-rewritestatepointsforgc-cpp-/partiallyconstructedsafepointrecord
custom_edit_url: null
toc_max_heading_level: 4
keywords:
  - doxygen
  - reference
  - struct

---

<div class="doxyPage">

# `PartiallyConstructedSafepointRecord` Struct



## Declaration

<div class="doxyDeclaration">
struct anonymous{RewriteStatepointsForGC.cpp}::PartiallyConstructedSafepointRecord { ... }
</div>

## Public Member Attributes Index

<table class="doxyMembersIndex">

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/namespaces/anonymous-rewritestatepointsforgc-cpp-/#a44ffc2aed23d32f992437bbf2a87699b">StatepointLiveSetTy</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a6390af6dff7b6f4a5a6935e790b17e7d">LiveSet</a></td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>The set of values known to be live across this safepoint. <a href="#a6390af6dff7b6f4a5a6935e790b17e7d">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/gcstatepointinst">GCStatepointInst</a> *</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a6c837647056b274bfef25285c578e2e6">StatepointToken</a></td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>The <em>new</em> gc.statepoint instruction itself. <a href="#a6c837647056b274bfef25285c578e2e6">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/instruction">Instruction</a> *</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a96701e3b5f7fbede4562924f12d60855">UnwindToken</a></td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p><a href="/web-llvm/docs/api/classes/llvm/instruction">Instruction</a> to which exceptional gc relocates are attached Makes it easier to iterate through them during relocationViaAlloca. <a href="#a96701e3b5f7fbede4562924f12d60855">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/namespaces/anonymous-rewritestatepointsforgc-cpp-/#a1c48ec4ca71e3529980deb7922f3e7ea">RematerializedValueMapTy</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a2636132e9fa0f32d56b1713358998633">RematerializedValues</a></td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p><a href="/web-llvm/docs/api/classes/llvm/record">Record</a> live values we are rematerialized instead of relocating. <a href="#a2636132e9fa0f32d56b1713358998633">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

</table>


<p>Definition at line 201 of file <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/scalar/rewritestatepointsforgc-cpp">RewriteStatepointsForGC.cpp</a>.</p>


<div class="doxySectionDef">

## Public Member Attributes

### LiveSet {#a6390af6dff7b6f4a5a6935e790b17e7d}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">StatepointLiveSetTy anonymous{RewriteStatepointsForGC.cpp}::PartiallyConstructedSafepointRecord::LiveSet</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>The set of values known to be live across this safepoint.</p>

<p>Definition at line 203 of file <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/scalar/rewritestatepointsforgc-cpp">RewriteStatepointsForGC.cpp</a>.</p>

</div>
</div>

### RematerializedValues {#a2636132e9fa0f32d56b1713358998633}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">RematerializedValueMapTy anonymous{RewriteStatepointsForGC.cpp}::PartiallyConstructedSafepointRecord::RematerializedValues</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p><a href="/web-llvm/docs/api/classes/llvm/record">Record</a> live values we are rematerialized instead of relocating.</p>


<p>They are not included into 'LiveSet' field. Maps rematerialized copy to it's original value.</p>


<p>Definition at line 216 of file <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/scalar/rewritestatepointsforgc-cpp">RewriteStatepointsForGC.cpp</a>.</p>

</div>
</div>

### StatepointToken {#a6c837647056b274bfef25285c578e2e6}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">GCStatepointInst* anonymous{RewriteStatepointsForGC.cpp}::PartiallyConstructedSafepointRecord::StatepointToken</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>The <em>new</em> gc.statepoint instruction itself.</p>


<p>This produces the token that normal path gc.relocates and the gc.result are tied to.</p>


<p>Definition at line 207 of file <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/scalar/rewritestatepointsforgc-cpp">RewriteStatepointsForGC.cpp</a>.</p>

</div>
</div>

### UnwindToken {#a96701e3b5f7fbede4562924f12d60855}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">Instruction* anonymous{RewriteStatepointsForGC.cpp}::PartiallyConstructedSafepointRecord::UnwindToken</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p><a href="/web-llvm/docs/api/classes/llvm/instruction">Instruction</a> to which exceptional gc relocates are attached Makes it easier to iterate through them during relocationViaAlloca.</p>

<p>Definition at line 211 of file <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/scalar/rewritestatepointsforgc-cpp">RewriteStatepointsForGC.cpp</a>.</p>

</div>
</div>

</div>

<hr/>

The documentation for this struct was generated from the following file:

<ul>
<li><a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/scalar/rewritestatepointsforgc-cpp">RewriteStatepointsForGC.cpp</a></li>
</ul>

<hr/>

<p class="doxyGeneratedBy">Generated via <a href="https://xpack.github.io/doxygen2docusaurus">doxygen2docusaurus</a> 2.0.0 by <a href="https://www.doxygen.nl">Doxygen</a> 1.15.0.</p>

</div>
