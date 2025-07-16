---

# DO NOT EDIT!
# Automatically generated via doxygen2docusaurus by Doxygen.

slug: /api/structs/anonymous-valuemapper-cpp-/potworklistentry
custom_edit_url: null
toc_max_heading_level: 4
keywords:
  - doxygen
  - reference
  - struct

---

<div class="doxyPage">

# The `POTWorklistEntry` Struct Reference

<p>An entry in the worklist for the post-order traversal. <a href="#details">More...</a></p>

## Declaration

<div class="doxyDeclaration">
struct anonymous{ValueMapper.cpp}::POTWorklistEntry { ... }
</div>

## Public Constructors Index

<table class="doxyMembersIndex">

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ab71f922cf776ebcd2e97b854edc2952e">POTWorklistEntry</a> (MDNode &amp;N)</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/mdnode">MDNode</a> *</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a0de68b449d6133f347e3dc092ad5145f">N</a></td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Current node. <a href="#a0de68b449d6133f347e3dc092ad5145f">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/mdnode/#af4fe559b6ceafad40f7144063ef2afd2">MDNode::op_iterator</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a629b10e7e173be59cd5f1d320c011f65">Op</a></td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Current operand of <span class="doxyComputerOutput">N</span>. <a href="#a629b10e7e173be59cd5f1d320c011f65">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">bool</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a078f37b66e307f6cfec550dc3ad593f8">HasChanged</a> = false</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Keep a flag of whether operands have changed in the worklist to avoid hitting the map in <em>UniquedGraph</em>. <a href="#a078f37b66e307f6cfec550dc3ad593f8">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

</table>

## Description {#details}

<p>An entry in the worklist for the post-order traversal.</p>

<p>Definition at line 713 of file <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/utils/valuemapper-cpp">ValueMapper.cpp</a>.</p>


<div class="doxySectionDef">

## Public Constructors

### POTWorklistEntry() {#ab71f922cf776ebcd2e97b854edc2952e}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">anonymous{ValueMapper.cpp}::POTWorklistEntry::POTWorklistEntry (<a href="/web-llvm/docs/api/classes/llvm/mdnode">MDNode</a> &amp; N)</td>
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



<p>Definition at line 721 of file <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/utils/valuemapper-cpp">ValueMapper.cpp</a>.</p>


<p>References <a href="#a0de68b449d6133f347e3dc092ad5145f">N</a> and <a href="#a629b10e7e173be59cd5f1d320c011f65">Op</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Public Member Attributes

### HasChanged {#a078f37b66e307f6cfec550dc3ad593f8}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool anonymous{ValueMapper.cpp}::POTWorklistEntry::HasChanged = false</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Keep a flag of whether operands have changed in the worklist to avoid hitting the map in <em>UniquedGraph</em>.</p>

<p>Definition at line 719 of file <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/utils/valuemapper-cpp">ValueMapper.cpp</a>.</p>

</div>
</div>

### N {#a0de68b449d6133f347e3dc092ad5145f}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">MDNode* anonymous{ValueMapper.cpp}::POTWorklistEntry::N</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Current node.</p>

<p>Definition at line 714 of file <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/utils/valuemapper-cpp">ValueMapper.cpp</a>.</p>


<p>Referenced by <a href="#ab71f922cf776ebcd2e97b854edc2952e">POTWorklistEntry</a>.</p>

</div>
</div>

### Op {#a629b10e7e173be59cd5f1d320c011f65}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">MDNode::op_iterator anonymous{ValueMapper.cpp}::POTWorklistEntry::Op</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Current operand of <span class="doxyComputerOutput">N</span>.</p>

<p>Definition at line 715 of file <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/utils/valuemapper-cpp">ValueMapper.cpp</a>.</p>


<p>Referenced by <a href="#ab71f922cf776ebcd2e97b854edc2952e">POTWorklistEntry</a>.</p>

</div>
</div>

</div>

<hr/>

The documentation for this struct was generated from the following file:

<ul>
<li><a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/utils/valuemapper-cpp">ValueMapper.cpp</a></li>
</ul>

<hr/>

<p class="doxyGeneratedBy">Generated via <a href="https://github.com/xpack/doxygen2docusaurus">doxygen2docusaurus</a> by <a href="https://www.doxygen.nl">Doxygen</a> 1.15.0.</p>

</div>
