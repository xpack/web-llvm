---

# DO NOT EDIT!
# Automatically generated via doxygen2docusaurus by Doxygen.

slug: /api/structs/anonymous-scheduledagrrlist-cpp-/ilp-ls-rr-sort
custom_edit_url: null
toc_max_heading_level: 4
keywords:
  - doxygen
  - reference
  - struct

---

<div class="doxyPage">

# The `ilp_ls_rr_sort` Struct Reference



## Declaration

<div class="doxyDeclaration">
struct anonymous{ScheduleDAGRRList.cpp}::ilp_ls_rr_sort { ... }
</div>

## Base struct

<table class="doxyMembersIndex">

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">struct</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="/web-llvm/docs/api/structs/anonymous-scheduledagrrlist-cpp-/queue-sort">queue_sort</a></td>
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

## Enumerations Index

<table class="doxyMembersIndex">

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">anonymous enum</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"> { <a href="#a79439b03adbe91c9ae9024a7b55e023f">...</a> }</td>
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

## Public Constructors Index

<table class="doxyMembersIndex">

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a6a37c62bf730aa995a87686d6497a41e">ilp_ls_rr_sort</a> (RegReductionPQBase *spq)</td>
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

## Public Operators Index

<table class="doxyMembersIndex">

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">bool</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a79b85bbc0a0fbf047dcef83891e4b9e4">operator()</a> (SUnit *left, SUnit *right) const</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">bool</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a6e62f12a56efd07685870a1acd81af4a">isReady</a> (SUnit *SU, unsigned CurCycle) const</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/anonymous-scheduledagrrlist-cpp-/regreductionpqbase">RegReductionPQBase</a> *</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a8bce7217da3a036fed44f703a3b448ee">SPQ</a></td>
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


<p>Definition at line 1717 of file <a href="/web-llvm/docs/api/files/lib/lib/codegen/lib/codegen/selectiondag/scheduledagrrlist-cpp">ScheduleDAGRRList.cpp</a>.</p>


<div class="doxySectionDef">

## Enumerations

### anonymous enum  {#a79439b03adbe91c9ae9024a7b55e023f}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">anonymous enum </td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">


<dl class="doxyEnumList">
<dt class="doxyEnumTableTitle">Enumeration values</dt>
<dd>
<table class="doxyEnumTable">

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">IsBottomUp<a id="a79439b03adbe91c9ae9024a7b55e023fa0882c495caa1bbc571d1bc3c3d3e09f3"></a></td>
<td class="doxyEnumItemDescription"> (= true)</td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">HasReadyFilter<a id="a79439b03adbe91c9ae9024a7b55e023fac356c5199a702a41ae9ac82191cc885f"></a></td>
<td class="doxyEnumItemDescription"> (= false)</td>
</tr>

</table>
</dd>
</dl>

<p>Definition at line 1718 of file <a href="/web-llvm/docs/api/files/lib/lib/codegen/lib/codegen/selectiondag/scheduledagrrlist-cpp">ScheduleDAGRRList.cpp</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Public Constructors

### ilp\_ls\_rr\_sort() {#a6a37c62bf730aa995a87686d6497a41e}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">anonymous{ScheduleDAGRRList.cpp}::ilp_ls_rr_sort::ilp_ls_rr_sort (<a href="/web-llvm/docs/api/classes/anonymous-scheduledagrrlist-cpp-/regreductionpqbase">RegReductionPQBase</a> * spq)</td>
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



<p>Definition at line 1725 of file <a href="/web-llvm/docs/api/files/lib/lib/codegen/lib/codegen/selectiondag/scheduledagrrlist-cpp">ScheduleDAGRRList.cpp</a>.</p>


<p>Reference <a href="#a8bce7217da3a036fed44f703a3b448ee">SPQ</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Public Operators

### operator()() {#a79b85bbc0a0fbf047dcef83891e4b9e4}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool ilp_ls_rr_sort::operator() (<a href="/web-llvm/docs/api/classes/llvm/sunit">SUnit</a> * left, <a href="/web-llvm/docs/api/classes/llvm/sunit">SUnit</a> * right)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 1729 of file <a href="/web-llvm/docs/api/files/lib/lib/codegen/lib/codegen/selectiondag/scheduledagrrlist-cpp">ScheduleDAGRRList.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/files/lib/lib/codegen/lib/codegen/selectiondag/scheduledagrrlist-cpp/#a8127bf55bc75e880ae5830edbebf065d">BUHasStall</a>, <a href="/web-llvm/docs/api/files/lib/lib/codegen/lib/codegen/selectiondag/scheduledagrrlist-cpp/#a7c9777fccc67ab82fb3d6067611ba1c2">BURRSort</a>, <a href="/web-llvm/docs/api/files/lib/lib/codegen/lib/codegen/selectiondag/scheduledagrrlist-cpp/#a07e9d7ff453553fd3e5e64c9d93d5d07">canEnableCoalescing</a>, <a href="/web-llvm/docs/api/files/lib/lib/codegen/lib/codegen/selectiondag/scheduledagrrlist-cpp/#ac49ea8879ebf41e521f4f48838e17b6c">checkSpecialNodes</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a7c46c742c31be54870e2038048e6b391">llvm::dbgs</a>, <a href="/web-llvm/docs/api/files/lib/lib/codegen/lib/codegen/selectiondag/scheduledagrrlist-cpp/#a2ec713ec5478dc3e598dc6319b2ae5de">DisableSchedCriticalPath</a>, <a href="/web-llvm/docs/api/files/lib/lib/codegen/lib/codegen/selectiondag/scheduledagrrlist-cpp/#aea38eae180cf9360c052a88b63220f39">DisableSchedHeight</a>, <a href="/web-llvm/docs/api/files/lib/lib/codegen/lib/codegen/selectiondag/scheduledagrrlist-cpp/#acf6cc8bdf2214ef23ef759883e9a134c">DisableSchedLiveUses</a>, <a href="/web-llvm/docs/api/files/lib/lib/codegen/lib/codegen/selectiondag/scheduledagrrlist-cpp/#a801e0a876ba324b5c8b67c2ed1a75717">DisableSchedRegPressure</a>, <a href="/web-llvm/docs/api/files/lib/lib/codegen/lib/codegen/selectiondag/scheduledagrrlist-cpp/#a158b6d9f8c5865052af711b8286a59a2">DisableSchedStalls</a>, <a href="/web-llvm/docs/api/classes/llvm/sunit/#a8926b25df7254ba2730fa5d7ec139862">llvm::SUnit::getDepth</a>, <a href="/web-llvm/docs/api/classes/llvm/sunit/#a582da862b28b876ef2235781392cffa6">llvm::SUnit::getHeight</a>, <a href="/web-llvm/docs/api/classes/llvm/sunit/#a0be1f84d53e90c247d75f2ed63636761">llvm::SUnit::isCall</a>, <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/support/debug-h/#a196897517069dda1bdb549e24468f7d7">LLVM_DEBUG</a>, <a href="/web-llvm/docs/api/files/lib/lib/codegen/lib/codegen/selectiondag/scheduledagrrlist-cpp/#a9ce6b6c1c63c0580011ddbd5105d6ccb">MaxReorderWindow</a>, <a href="/web-llvm/docs/api/classes/llvm/sunit/#a3f708b119627541f144d703a1d183202">llvm::SUnit::NodeNum</a> and <a href="#a8bce7217da3a036fed44f703a3b448ee">SPQ</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Public Member Functions

### isReady() {#a6e62f12a56efd07685870a1acd81af4a}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool ilp_ls_rr_sort::isReady (<a href="/web-llvm/docs/api/classes/llvm/sunit">SUnit</a> * SU, unsigned CurCycle)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 1727 of file <a href="/web-llvm/docs/api/files/lib/lib/codegen/lib/codegen/selectiondag/scheduledagrrlist-cpp">ScheduleDAGRRList.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/classes/llvm/sunit/#a582da862b28b876ef2235781392cffa6">llvm::SUnit::getHeight</a>, <a href="/web-llvm/docs/api/classes/llvm/schedulehazardrecognizer/#a9bec0e329b12bbc503d08db497d43267a4e42ac50bfd060349e49904842121cf1">llvm::ScheduleHazardRecognizer::NoHazard</a> and <a href="#a8bce7217da3a036fed44f703a3b448ee">SPQ</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Public Member Attributes

### SPQ {#a8bce7217da3a036fed44f703a3b448ee}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">RegReductionPQBase* anonymous{ScheduleDAGRRList.cpp}::ilp_ls_rr_sort::SPQ</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 1723 of file <a href="/web-llvm/docs/api/files/lib/lib/codegen/lib/codegen/selectiondag/scheduledagrrlist-cpp">ScheduleDAGRRList.cpp</a>.</p>


<p>Referenced by <a href="#a6a37c62bf730aa995a87686d6497a41e">ilp_ls_rr_sort</a>, <a href="#a6e62f12a56efd07685870a1acd81af4a">isReady</a> and <a href="#a79b85bbc0a0fbf047dcef83891e4b9e4">operator()</a>.</p>

</div>
</div>

</div>

<hr/>

The documentation for this struct was generated from the following file:

<ul>
<li><a href="/web-llvm/docs/api/files/lib/lib/codegen/lib/codegen/selectiondag/scheduledagrrlist-cpp">ScheduleDAGRRList.cpp</a></li>
</ul>

<hr/>

<p class="doxyGeneratedBy">Generated via <a href="https://github.com/xpack/doxygen2docusaurus">doxygen2docusaurus</a> by <a href="https://www.doxygen.nl">Doxygen</a> 1.14.0.</p>

</div>
