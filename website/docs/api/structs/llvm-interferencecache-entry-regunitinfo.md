---

# DO NOT EDIT!
# Automatically generated via doxygen2docusaurus by Doxygen.

slug: /api/structs/llvm/interferencecache/entry/regunitinfo
custom_edit_url: null
toc_max_heading_level: 4
keywords:
  - doxygen
  - reference
  - struct

---

<div class="doxyPage">

# The `RegUnitInfo` Struct Reference

<p>RegUnitInfo - Information tracked about each RegUnit in PhysReg. <a href="#details">More...</a></p>

## Declaration

<div class="doxyDeclaration">
struct llvm::InterferenceCache::Entry::RegUnitInfo { ... }
</div>

## Public Constructors Index

<table class="doxyMembersIndex">

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ae148fb98f79d1b6595ee7b153b1ee31f">RegUnitInfo</a> (LiveIntervalUnion &amp;LIU)</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/liveintervalunion/#a955fe64963e97f1356746fbce9baeb84">LiveIntervalUnion::SegmentIter</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#af3957ede721d0ffbc9db29a30596aa8e">VirtI</a></td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Iterator pointing into the <a href="/web-llvm/docs/api/classes/llvm/liveintervalunion">LiveIntervalUnion</a> containing virtual register interference. <a href="#af3957ede721d0ffbc9db29a30596aa8e">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">unsigned</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a0e0b2fa91887f0162231d3f69f84f9f5">VirtTag</a></td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Tag of the LIU last time we looked. <a href="#a0e0b2fa91887f0162231d3f69f84f9f5">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/liverange">LiveRange</a> *</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a4ead9ae54b07ab56298760dfd19644f6">Fixed</a> = nullptr</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Fixed interference in RegUnit. <a href="#a4ead9ae54b07ab56298760dfd19644f6">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/liverange/#a143c1fcb6066cb301f828ec4c18d79f4">LiveInterval::iterator</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a629d05c0412bbb4edfa36cd39fba7b7c">FixedI</a></td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Iterator pointing into the fixed RegUnit interference. <a href="#a629d05c0412bbb4edfa36cd39fba7b7c">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

</table>

## Description {#details}

<p>RegUnitInfo - Information tracked about each RegUnit in PhysReg.</p>


<p>When PrevPos is set, the iterators are valid as if advanceTo(PrevPos) had just been called.</p>


<p>Definition at line 71 of file <a href="/web-llvm/docs/api/files/lib/lib/codegen/interferencecache-h">InterferenceCache.h</a>.</p>


<div class="doxySectionDef">

## Public Constructors

### RegUnitInfo() {#ae148fb98f79d1b6595ee7b153b1ee31f}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">llvm::InterferenceCache::Entry::RegUnitInfo::RegUnitInfo (<a href="/web-llvm/docs/api/classes/llvm/liveintervalunion">LiveIntervalUnion</a> &amp; LIU)</td>
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



<p>Definition at line 85 of file <a href="/web-llvm/docs/api/files/lib/lib/codegen/interferencecache-h">InterferenceCache.h</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Public Member Attributes

### Fixed {#a4ead9ae54b07ab56298760dfd19644f6}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">LiveRange* llvm::InterferenceCache::Entry::RegUnitInfo::Fixed = nullptr</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Fixed interference in RegUnit.</p>

<p>Definition at line 80 of file <a href="/web-llvm/docs/api/files/lib/lib/codegen/interferencecache-h">InterferenceCache.h</a>.</p>

</div>
</div>

### FixedI {#a629d05c0412bbb4edfa36cd39fba7b7c}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">LiveInterval::iterator llvm::InterferenceCache::Entry::RegUnitInfo::FixedI</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Iterator pointing into the fixed RegUnit interference.</p>

<p>Definition at line 83 of file <a href="/web-llvm/docs/api/files/lib/lib/codegen/interferencecache-h">InterferenceCache.h</a>.</p>

</div>
</div>

### VirtI {#af3957ede721d0ffbc9db29a30596aa8e}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">LiveIntervalUnion::SegmentIter llvm::InterferenceCache::Entry::RegUnitInfo::VirtI</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Iterator pointing into the <a href="/web-llvm/docs/api/classes/llvm/liveintervalunion">LiveIntervalUnion</a> containing virtual register interference.</p>

<p>Definition at line 74 of file <a href="/web-llvm/docs/api/files/lib/lib/codegen/interferencecache-h">InterferenceCache.h</a>.</p>

</div>
</div>

### VirtTag {#a0e0b2fa91887f0162231d3f69f84f9f5}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">unsigned llvm::InterferenceCache::Entry::RegUnitInfo::VirtTag</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Tag of the LIU last time we looked.</p>

<p>Definition at line 77 of file <a href="/web-llvm/docs/api/files/lib/lib/codegen/interferencecache-h">InterferenceCache.h</a>.</p>

</div>
</div>

</div>

<hr/>

The documentation for this struct was generated from the following file:

<ul>
<li><a href="/web-llvm/docs/api/files/lib/lib/codegen/interferencecache-h">InterferenceCache.h</a></li>
</ul>

<hr/>

<p class="doxyGeneratedBy">Generated via <a href="https://github.com/xpack/doxygen2docusaurus">doxygen2docusaurus</a> by <a href="https://www.doxygen.nl">Doxygen</a> 1.14.0.</p>

</div>
