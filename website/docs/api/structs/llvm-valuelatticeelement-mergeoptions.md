---

# DO NOT EDIT!
# Automatically generated via doxygen2docusaurus by Doxygen.

slug: /api/structs/llvm/valuelatticeelement/mergeoptions
custom_edit_url: null
toc_max_heading_level: 4
keywords:
  - doxygen
  - reference
  - struct

---

<div class="doxyPage">

# `MergeOptions` Struct

<p>Struct to control some aspects related to merging constant ranges. <a href="#details">More...</a></p>

## Declaration

<div class="doxyDeclaration">
struct llvm::ValueLatticeElement::MergeOptions { ... }
</div>

## Included Headers

<div class="doxyIncludesList">#include "<a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/analysis/valuelattice-h">llvm/Analysis/ValueLattice.h</a>"
</div>

## Public Constructors Index

<table class="doxyMembersIndex">

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a225f048a5b5b01db03baa36b62f52b89">MergeOptions</a> ()</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ad8e7891f7dafb6899d68d2339ce23248">MergeOptions</a> (bool MayIncludeUndef, bool CheckWiden, unsigned MaxWidenSteps=1)</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/structs/llvm/valuelatticeelement/mergeoptions">MergeOptions</a> &amp;</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a18e7ce787d45c157813217897f1ce8bd">setMayIncludeUndef</a> (bool V=true)</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/structs/llvm/valuelatticeelement/mergeoptions">MergeOptions</a> &amp;</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ad7db0377a26ebf05073ffeae8ef48919">setCheckWiden</a> (bool V=true)</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/structs/llvm/valuelatticeelement/mergeoptions">MergeOptions</a> &amp;</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ace3a38e819bd42eb384b64778dd326c5">setMaxWidenSteps</a> (unsigned Steps=1)</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">bool</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a09f877a7f7b1ab6be9fe1528f42d5047">MayIncludeUndef</a></td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>The merge value may include undef. <a href="#a09f877a7f7b1ab6be9fe1528f42d5047">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">bool</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a2956df58979d496475e6b3a470b2ec51">CheckWiden</a></td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Handle repeatedly extending a range by going to overdefined after a number of steps. <a href="#a2956df58979d496475e6b3a470b2ec51">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">unsigned</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ae95a4617b39adf70a6fd81a4090ec066">MaxWidenSteps</a></td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>The number of allowed widening steps (including setting the range initially). <a href="#ae95a4617b39adf70a6fd81a4090ec066">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

</table>

## Description {#details}

<p>Struct to control some aspects related to merging constant ranges.</p>

<p>Definition at line 108 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/analysis/valuelattice-h">ValueLattice.h</a>.</p>


<div class="doxySectionDef">

## Public Constructors

### MergeOptions() {#a225f048a5b5b01db03baa36b62f52b89}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">llvm::ValueLatticeElement::MergeOptions::MergeOptions ()</td>
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



<p>Definition at line 120 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/analysis/valuelattice-h">ValueLattice.h</a>.</p>


<p>Reference <a href="#a225f048a5b5b01db03baa36b62f52b89">MergeOptions</a>.</p>


<p>Referenced by <a href="#a225f048a5b5b01db03baa36b62f52b89">MergeOptions</a>, <a href="#ad7db0377a26ebf05073ffeae8ef48919">setCheckWiden</a>, <a href="#ace3a38e819bd42eb384b64778dd326c5">setMaxWidenSteps</a> and <a href="#a18e7ce787d45c157813217897f1ce8bd">setMayIncludeUndef</a>.</p>

</div>
</div>

### MergeOptions() {#ad8e7891f7dafb6899d68d2339ce23248}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">llvm::ValueLatticeElement::MergeOptions::MergeOptions (bool MayIncludeUndef, bool CheckWiden, unsigned MaxWidenSteps=1)</td>
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



<p>Definition at line 122 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/analysis/valuelattice-h">ValueLattice.h</a>.</p>


<p>References <a href="#a2956df58979d496475e6b3a470b2ec51">CheckWiden</a>, <a href="#ae95a4617b39adf70a6fd81a4090ec066">MaxWidenSteps</a> and <a href="#a09f877a7f7b1ab6be9fe1528f42d5047">MayIncludeUndef</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Public Member Functions

### setCheckWiden() {#ad7db0377a26ebf05073ffeae8ef48919}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">MergeOptions &amp; llvm::ValueLatticeElement::MergeOptions::setCheckWiden (bool V=<a href="/web-llvm/docs/api/files/lib/lib/analysis/basicaliasanalysis-cpp/#af6d5cafbdfc5313e65d990120021a3ec">true</a>)</td>
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



<p>Definition at line 132 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/analysis/valuelattice-h">ValueLattice.h</a>.</p>


<p>References <a href="#a2956df58979d496475e6b3a470b2ec51">CheckWiden</a> and <a href="#a225f048a5b5b01db03baa36b62f52b89">MergeOptions</a>.</p>

</div>
</div>

### setMaxWidenSteps() {#ace3a38e819bd42eb384b64778dd326c5}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">MergeOptions &amp; llvm::ValueLatticeElement::MergeOptions::setMaxWidenSteps (unsigned Steps=1)</td>
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



<p>Definition at line 137 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/analysis/valuelattice-h">ValueLattice.h</a>.</p>


<p>References <a href="#a2956df58979d496475e6b3a470b2ec51">CheckWiden</a>, <a href="#ae95a4617b39adf70a6fd81a4090ec066">MaxWidenSteps</a> and <a href="#a225f048a5b5b01db03baa36b62f52b89">MergeOptions</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/utils/sccpsolver-cpp/#a080450f5d7071db2a77886da534ac3ab">getMaxWidenStepsOpts</a>.</p>

</div>
</div>

### setMayIncludeUndef() {#a18e7ce787d45c157813217897f1ce8bd}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">MergeOptions &amp; llvm::ValueLatticeElement::MergeOptions::setMayIncludeUndef (bool V=<a href="/web-llvm/docs/api/files/lib/lib/analysis/basicaliasanalysis-cpp/#af6d5cafbdfc5313e65d990120021a3ec">true</a>)</td>
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



<p>Definition at line 127 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/analysis/valuelattice-h">ValueLattice.h</a>.</p>


<p>References <a href="#a09f877a7f7b1ab6be9fe1528f42d5047">MayIncludeUndef</a> and <a href="#a225f048a5b5b01db03baa36b62f52b89">MergeOptions</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Public Member Attributes

### CheckWiden {#a2956df58979d496475e6b3a470b2ec51}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool llvm::ValueLatticeElement::MergeOptions::CheckWiden</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Handle repeatedly extending a range by going to overdefined after a number of steps.</p>

<p>Definition at line 114 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/analysis/valuelattice-h">ValueLattice.h</a>.</p>


<p>Referenced by <a href="#ad8e7891f7dafb6899d68d2339ce23248">MergeOptions</a>, <a href="#ad7db0377a26ebf05073ffeae8ef48919">setCheckWiden</a> and <a href="#ace3a38e819bd42eb384b64778dd326c5">setMaxWidenSteps</a>.</p>

</div>
</div>

### MaxWidenSteps {#ae95a4617b39adf70a6fd81a4090ec066}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">unsigned llvm::ValueLatticeElement::MergeOptions::MaxWidenSteps</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>The number of allowed widening steps (including setting the range initially).</p>

<p>Definition at line 118 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/analysis/valuelattice-h">ValueLattice.h</a>.</p>


<p>Referenced by <a href="#ad8e7891f7dafb6899d68d2339ce23248">MergeOptions</a> and <a href="#ace3a38e819bd42eb384b64778dd326c5">setMaxWidenSteps</a>.</p>

</div>
</div>

### MayIncludeUndef {#a09f877a7f7b1ab6be9fe1528f42d5047}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool llvm::ValueLatticeElement::MergeOptions::MayIncludeUndef</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>The merge value may include undef.</p>

<p>Definition at line 110 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/analysis/valuelattice-h">ValueLattice.h</a>.</p>


<p>Referenced by <a href="#ad8e7891f7dafb6899d68d2339ce23248">MergeOptions</a> and <a href="#a18e7ce787d45c157813217897f1ce8bd">setMayIncludeUndef</a>.</p>

</div>
</div>

</div>

<hr/>

The documentation for this struct was generated from the following file:

<ul>
<li><a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/analysis/valuelattice-h">ValueLattice.h</a></li>
</ul>

<hr/>

<p class="doxyGeneratedBy">Generated via <a href="https://xpack.github.io/doxygen2docusaurus">doxygen2docusaurus</a> 2.0.0 by <a href="https://www.doxygen.nl">Doxygen</a> 1.15.0.</p>

</div>
