---

# DO NOT EDIT!
# Automatically generated via doxygen2docusaurus by Doxygen.

slug: /api/classes/anonymous-dagdeltaalgorithm-cpp-/deltaactivesethelper
custom_edit_url: null
toc_max_heading_level: 4
keywords:
  - doxygen
  - reference
  - class

---

<div class="doxyPage">

# The `DeltaActiveSetHelper` Class Reference

<p>Helper object for minimizing an active set of changes. <a href="#details">More...</a></p>

## Declaration

<div class="doxyDeclaration">
class anonymous{DAGDeltaAlgorithm.cpp}::DeltaActiveSetHelper { ... }
</div>

## Base class

<table class="doxyMembersIndex">

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">class</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/deltaalgorithm">DeltaAlgorithm</a></td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p><a href="/web-llvm/docs/api/classes/llvm/deltaalgorithm">DeltaAlgorithm</a> - Implements the delta debugging algorithm (A. <a href="/web-llvm/docs/api/classes/llvm/deltaalgorithm/#details">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

</table>

## Public Constructors Index

<table class="doxyMembersIndex">

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ae5f06e6b313a8f35f2e86a73a590ccc1">DeltaActiveSetHelper</a> (DAGDeltaAlgorithmImpl &amp;DDAI, const changeset_ty &amp;Required)</td>
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

## Protected Member Functions Index

<table class="doxyMembersIndex">

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">void</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a9c104d077ab4dd2faa0dbc0ddf16fd9d">UpdatedSearchState</a> (const changeset_ty &amp;Changes, const changesetlist_ty &amp;Sets) override</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>UpdatedSearchState - Callback used when the search state changes. <a href="#a9c104d077ab4dd2faa0dbc0ddf16fd9d">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">bool</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a1712c60b6ddf57740d97eec56cb004e1">ExecuteOneTest</a> (const changeset_ty &amp;S) override</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>ExecuteOneTest - Execute a single test predicate on the change set <span class="doxyComputerOutput">S</span>. <a href="#a1712c60b6ddf57740d97eec56cb004e1">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

</table>

## Private Member Attributes Index

<table class="doxyMembersIndex">

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/anonymous-dagdeltaalgorithm-cpp-/dagdeltaalgorithmimpl">DAGDeltaAlgorithmImpl</a> &amp;</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a24f70f68918a3430a41dff48a66c51d0">DDAI</a></td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/deltaalgorithm/#adbeb2e02b90b33dba5a8b124fbda75d9">changeset_ty</a> &amp;</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a082454404f8d1cbdb769cc06e55b007e">Required</a></td>
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

<p>Helper object for minimizing an active set of changes.</p>

<p>Definition at line 153 of file <a href="/web-llvm/docs/api/files/lib/lib/support/dagdeltaalgorithm-cpp">DAGDeltaAlgorithm.cpp</a>.</p>


<div class="doxySectionDef">

## Public Constructors

### DeltaActiveSetHelper() {#ae5f06e6b313a8f35f2e86a73a590ccc1}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">anonymous{DAGDeltaAlgorithm.cpp}::DeltaActiveSetHelper::DeltaActiveSetHelper (<a href="/web-llvm/docs/api/classes/anonymous-dagdeltaalgorithm-cpp-/dagdeltaalgorithmimpl">DAGDeltaAlgorithmImpl</a> &amp; DDAI, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/deltaalgorithm/#adbeb2e02b90b33dba5a8b124fbda75d9">changeset_ty</a> &amp; Required)</td>
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



<p>Definition at line 170 of file <a href="/web-llvm/docs/api/files/lib/lib/support/dagdeltaalgorithm-cpp">DAGDeltaAlgorithm.cpp</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Protected Member Functions

### ExecuteOneTest() {#a1712c60b6ddf57740d97eec56cb004e1}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool anonymous{DAGDeltaAlgorithm.cpp}::DeltaActiveSetHelper::ExecuteOneTest (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/deltaalgorithm/#adbeb2e02b90b33dba5a8b124fbda75d9">changeset_ty</a> &amp; S)</td>
</tr>
</table>
</td>
<td class="doxyMemberLabelsRight">
<span class="doxyMemberLabels">
<span class="doxyMemberLabel inline">inline</span>
<span class="doxyMemberLabel protected">protected</span>
<span class="doxyMemberLabel virtual">virtual</span>
</span>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>ExecuteOneTest - Execute a single test predicate on the change set <span class="doxyComputerOutput">S</span>.</p>

<p>Definition at line 165 of file <a href="/web-llvm/docs/api/files/lib/lib/support/dagdeltaalgorithm-cpp">DAGDeltaAlgorithm.cpp</a>.</p>

</div>
</div>

### UpdatedSearchState() {#a9c104d077ab4dd2faa0dbc0ddf16fd9d}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void anonymous{DAGDeltaAlgorithm.cpp}::DeltaActiveSetHelper::UpdatedSearchState (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/deltaalgorithm/#adbeb2e02b90b33dba5a8b124fbda75d9">changeset_ty</a> &amp; Changes, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/deltaalgorithm/#aeada9341c197ace7a6f1a43e4b26a146">changesetlist_ty</a> &amp; Sets)</td>
</tr>
</table>
</td>
<td class="doxyMemberLabelsRight">
<span class="doxyMemberLabels">
<span class="doxyMemberLabel inline">inline</span>
<span class="doxyMemberLabel protected">protected</span>
<span class="doxyMemberLabel virtual">virtual</span>
</span>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>UpdatedSearchState - Callback used when the search state changes.</p>

<p>Definition at line 160 of file <a href="/web-llvm/docs/api/files/lib/lib/support/dagdeltaalgorithm-cpp">DAGDeltaAlgorithm.cpp</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Private Member Attributes

### DDAI {#a24f70f68918a3430a41dff48a66c51d0}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">DAGDeltaAlgorithmImpl&amp; anonymous{DAGDeltaAlgorithm.cpp}::DeltaActiveSetHelper::DDAI</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 154 of file <a href="/web-llvm/docs/api/files/lib/lib/support/dagdeltaalgorithm-cpp">DAGDeltaAlgorithm.cpp</a>.</p>

</div>
</div>

### Required {#a082454404f8d1cbdb769cc06e55b007e}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">const changeset_ty&amp; anonymous{DAGDeltaAlgorithm.cpp}::DeltaActiveSetHelper::Required</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 156 of file <a href="/web-llvm/docs/api/files/lib/lib/support/dagdeltaalgorithm-cpp">DAGDeltaAlgorithm.cpp</a>.</p>

</div>
</div>

</div>

<hr/>

The documentation for this class was generated from the following file:

<ul>
<li><a href="/web-llvm/docs/api/files/lib/lib/support/dagdeltaalgorithm-cpp">DAGDeltaAlgorithm.cpp</a></li>
</ul>

<hr/>

<p class="doxyGeneratedBy">Generated via <a href="https://github.com/xpack/doxygen2docusaurus">doxygen2docusaurus</a> by <a href="https://www.doxygen.nl">Doxygen</a> 1.15.0.</p>

</div>
