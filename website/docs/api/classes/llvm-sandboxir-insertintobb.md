---

# DO NOT EDIT!
# Automatically generated via doxygen2docusaurus by Doxygen.

slug: /api/classes/llvm/sandboxir/insertintobb
custom_edit_url: null
toc_max_heading_level: 4
keywords:
  - doxygen
  - reference
  - class

---

<div class="doxyPage">

# `InsertIntoBB` Class



## Declaration

<div class="doxyDeclaration">
class llvm::sandboxir::InsertIntoBB { ... }
</div>

## Included Headers

<div class="doxyIncludesList">#include "<a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/sandboxir/tracker-h">llvm/SandboxIR/Tracker.h</a>"
</div>

## Base class

<table class="doxyMembersIndex">

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">class</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/sandboxir/irchangebase">IRChangeBase</a></td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>The base class for IR Change classes. <a href="/web-llvm/docs/api/classes/llvm/sandboxir/irchangebase/#details">More...</a></p>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#af84628621aa77de4c2c3673b528765fb">InsertIntoBB</a> (Instruction *InsertedI)</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#affd575f572c8878aaaf43b87106dde71">revert</a> (Tracker &amp;Tracker) final</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>This runs when changes get reverted. <a href="#affd575f572c8878aaaf43b87106dde71">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">void</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ae843498174d96efdbb69508a093461b6">accept</a> () final</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>This runs when changes get accepted. <a href="#ae843498174d96efdbb69508a093461b6">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">void</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a412f2ad0a99452437d6ef8b932e36f91">dump</a> (raw_ostream &amp;OS) const final</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/support/compiler-h/#aa863693eef567397d9c292da5bf22d34">LLVM_DUMP_METHOD</a> void</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ac8ec42571eec61db5478d26f23a6f8e6">dump</a> () const final</td>
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

## Private Member Attributes Index

<table class="doxyMembersIndex">

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/sandboxir/instruction">Instruction</a> *</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#afe3b2d3a075f7741bf5ae2b024608adf">InsertedI</a> = nullptr</td>
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


<p>Definition at line 398 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/sandboxir/tracker-h">Tracker.h</a>.</p>


<div class="doxySectionDef">

## Public Constructors

### InsertIntoBB() {#af84628621aa77de4c2c3673b528765fb}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">InsertIntoBB::InsertIntoBB (<a href="/web-llvm/docs/api/classes/llvm/sandboxir/instruction">Instruction</a> * InsertedI)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Declaration at line 402 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/sandboxir/tracker-h">Tracker.h</a>, definition at line 299 of file <a href="/web-llvm/docs/api/files/lib/lib/sandboxir/tracker-cpp">Tracker.cpp</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Public Member Functions

### accept() {#ae843498174d96efdbb69508a093461b6}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void llvm::sandboxir::InsertIntoBB::accept ()</td>
</tr>
</table>
</td>
<td class="doxyMemberLabelsRight">
<span class="doxyMemberLabels">
<span class="doxyMemberLabel inline">inline</span>
<span class="doxyMemberLabel virtual">virtual</span>
</span>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>This runs when changes get accepted.</p>

<p>Definition at line 404 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/sandboxir/tracker-h">Tracker.h</a>.</p>

</div>
</div>

### dump() {#a412f2ad0a99452437d6ef8b932e36f91}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void llvm::sandboxir::InsertIntoBB::dump (<a href="/web-llvm/docs/api/classes/llvm/raw-ostream">raw_ostream</a> &amp; OS)</td>
</tr>
</table>
</td>
<td class="doxyMemberLabelsRight">
<span class="doxyMemberLabels">
<span class="doxyMemberLabel inline">inline</span>
<span class="doxyMemberLabel virtual">virtual</span>
</span>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 406 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/sandboxir/tracker-h">Tracker.h</a>.</p>

</div>
</div>

### dump() {#ac8ec42571eec61db5478d26f23a6f8e6}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void InsertIntoBB::dump ()</td>
</tr>
</table>
</td>
<td class="doxyMemberLabelsRight">
<span class="doxyMemberLabels">
<span class="doxyMemberLabel virtual">virtual</span>
</span>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Declaration at line 407 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/sandboxir/tracker-h">Tracker.h</a>, definition at line 302 of file <a href="/web-llvm/docs/api/files/lib/lib/sandboxir/tracker-cpp">Tracker.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/namespaces/llvm/#a7c46c742c31be54870e2038048e6b391">llvm::dbgs</a> and <a href="#ac8ec42571eec61db5478d26f23a6f8e6">dump</a>.</p>


<p>Referenced by <a href="#ac8ec42571eec61db5478d26f23a6f8e6">dump</a>.</p>

</div>
</div>

### revert() {#affd575f572c8878aaaf43b87106dde71}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void InsertIntoBB::revert (<a href="/web-llvm/docs/api/classes/llvm/sandboxir/tracker">Tracker</a> &amp; Tracker)</td>
</tr>
</table>
</td>
<td class="doxyMemberLabelsRight">
<span class="doxyMemberLabels">
<span class="doxyMemberLabel virtual">virtual</span>
</span>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>This runs when changes get reverted.</p>

<p>Declaration at line 403 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/sandboxir/tracker-h">Tracker.h</a>, definition at line 297 of file <a href="/web-llvm/docs/api/files/lib/lib/sandboxir/tracker-cpp">Tracker.cpp</a>.</p>


<p>Reference <a href="/web-llvm/docs/api/classes/llvm/sandboxir/irchangebase/#a178a085e66872f6cbe6c33f101debdf5">llvm::sandboxir::IRChangeBase::Tracker</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Private Member Attributes

### InsertedI {#afe3b2d3a075f7741bf5ae2b024608adf}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">Instruction* llvm::sandboxir::InsertIntoBB::InsertedI = nullptr</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 399 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/sandboxir/tracker-h">Tracker.h</a>.</p>

</div>
</div>

</div>

<hr/>

The documentation for this class was generated from the following files:

<ul>
<li><a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/sandboxir/tracker-h">Tracker.h</a></li>
<li><a href="/web-llvm/docs/api/files/lib/lib/sandboxir/tracker-cpp">Tracker.cpp</a></li>
</ul>

<hr/>

<p class="doxyGeneratedBy">Generated via <a href="https://github.com/xpack/doxygen2docusaurus">doxygen2docusaurus</a> by <a href="https://www.doxygen.nl">Doxygen</a> 1.15.0.</p>

</div>
