---

# DO NOT EDIT!
# Automatically generated via doxygen2docusaurus by Doxygen.

slug: /api/structs/anonymous-capturetracking-cpp-/earliestcaptures
custom_edit_url: null
toc_max_heading_level: 4
keywords:
  - doxygen
  - reference
  - struct

---

<div class="doxyPage">

# `EarliestCaptures` Struct

<p>Find the 'earliest' instruction before which the pointer is known not to be captured. <a href="#details">More...</a></p>

## Declaration

<div class="doxyDeclaration">
struct anonymous{CaptureTracking.cpp}::EarliestCaptures { ... }
</div>

## Base struct

<table class="doxyMembersIndex">

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">struct</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="/web-llvm/docs/api/structs/llvm/capturetracker">CaptureTracker</a></td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>This callback is used in conjunction with PointerMayBeCaptured. <a href="/web-llvm/docs/api/structs/llvm/capturetracker/#details">More...</a></p>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a2173e1b9b7c907c560fa9326b2a2352c">EarliestCaptures</a> (bool ReturnCaptures, Function &amp;F, const DominatorTree &amp;DT)</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a9bee3cf935e17c24637319fc402e1667">tooManyUses</a> () override</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>tooManyUses - The depth of traversal has breached a limit. <a href="#a9bee3cf935e17c24637319fc402e1667">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">bool</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#acc3304c7668514d15b7e9d6d61676ce5">captured</a> (const Use *U) override</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>captured - Information about the pointer was captured by the user of use U. <a href="#acc3304c7668514d15b7e9d6d61676ce5">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

</table>

## Public Member Attributes Index

<table class="doxyMembersIndex">

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/instruction">Instruction</a> *</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ae7243c11d421637329949fe0b62cf7c4">EarliestCapture</a> = nullptr</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/dominatortree">DominatorTree</a> &amp;</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a477a5360363112d7ed2c9ba8834e36bc">DT</a></td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">bool</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ac2d8451c44f0a5715233dc0b677c45d0">ReturnCaptures</a></td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">bool</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a42f878c57f21dceaf1c87cd7f15742bd">Captured</a> = false</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/function">Function</a> &amp;</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a265d5d74cfb20f6cf9146d52efe7bbfb">F</a></td>
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

<p>Find the 'earliest' instruction before which the pointer is known not to be captured.</p>


<p>Here an instruction A is considered earlier than instruction B, if A dominates B. If 2 escapes do not dominate each other, the terminator of the common dominator is chosen. If not all uses cannot be analyzed, the earliest escape is set to the first instruction in the function entry block.</p>


<p>Definition at line 159 of file <a href="/web-llvm/docs/api/files/lib/lib/analysis/capturetracking-cpp">CaptureTracking.cpp</a>.</p>


<div class="doxySectionDef">

## Public Constructors

### EarliestCaptures() {#a2173e1b9b7c907c560fa9326b2a2352c}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">anonymous{CaptureTracking.cpp}::EarliestCaptures::EarliestCaptures (bool ReturnCaptures, <a href="/web-llvm/docs/api/classes/llvm/function">Function</a> &amp; F, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/dominatortree">DominatorTree</a> &amp; DT)</td>
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



<p>Definition at line 161 of file <a href="/web-llvm/docs/api/files/lib/lib/analysis/capturetracking-cpp">CaptureTracking.cpp</a>.</p>


<p>References <a href="#a477a5360363112d7ed2c9ba8834e36bc">DT</a>, <a href="#a265d5d74cfb20f6cf9146d52efe7bbfb">F</a> and <a href="#ac2d8451c44f0a5715233dc0b677c45d0">ReturnCaptures</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Public Member Functions

### captured() {#acc3304c7668514d15b7e9d6d61676ce5}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool anonymous{CaptureTracking.cpp}::EarliestCaptures::captured (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/use">Use</a> * U)</td>
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

<p>captured - Information about the pointer was captured by the user of use U.</p>


<p>Return true to stop the traversal or false to continue looking for more capturing instructions.</p>


<p>Definition at line 169 of file <a href="/web-llvm/docs/api/files/lib/lib/analysis/capturetracking-cpp">CaptureTracking.cpp</a>.</p>


<p>References <a href="#a42f878c57f21dceaf1c87cd7f15742bd">Captured</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#ac4fc845f5ed92de63cd4474f128f5fc5">llvm::cast</a>, <a href="#a477a5360363112d7ed2c9ba8834e36bc">DT</a>, <a href="#ae7243c11d421637329949fe0b62cf7c4">EarliestCapture</a>, <a href="/web-llvm/docs/api/files/lib/lib/support/md5-cpp/#ac0eafdc9ee161b71e7af98af736952fd">I</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a92ca992e52dddc420f4b069cae06dfbe">llvm::isa</a> and <a href="#ac2d8451c44f0a5715233dc0b677c45d0">ReturnCaptures</a>.</p>

</div>
</div>

### tooManyUses() {#a9bee3cf935e17c24637319fc402e1667}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void anonymous{CaptureTracking.cpp}::EarliestCaptures::tooManyUses ()</td>
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

<p>tooManyUses - The depth of traversal has breached a limit.</p>


<p>There may be capturing instructions that will not be passed into <a href="#acc3304c7668514d15b7e9d6d61676ce5">captured()</a>.</p>


<p>Definition at line 164 of file <a href="/web-llvm/docs/api/files/lib/lib/analysis/capturetracking-cpp">CaptureTracking.cpp</a>.</p>


<p>References <a href="#a42f878c57f21dceaf1c87cd7f15742bd">Captured</a>, <a href="#ae7243c11d421637329949fe0b62cf7c4">EarliestCapture</a> and <a href="#a265d5d74cfb20f6cf9146d52efe7bbfb">F</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Public Member Attributes

### Captured {#a42f878c57f21dceaf1c87cd7f15742bd}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool anonymous{CaptureTracking.cpp}::EarliestCaptures::Captured = false</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 191 of file <a href="/web-llvm/docs/api/files/lib/lib/analysis/capturetracking-cpp">CaptureTracking.cpp</a>.</p>


<p>Referenced by <a href="#acc3304c7668514d15b7e9d6d61676ce5">captured</a> and <a href="#a9bee3cf935e17c24637319fc402e1667">tooManyUses</a>.</p>

</div>
</div>

### DT {#a477a5360363112d7ed2c9ba8834e36bc}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">const DominatorTree&amp; anonymous{CaptureTracking.cpp}::EarliestCaptures::DT</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 187 of file <a href="/web-llvm/docs/api/files/lib/lib/analysis/capturetracking-cpp">CaptureTracking.cpp</a>.</p>


<p>Referenced by <a href="#acc3304c7668514d15b7e9d6d61676ce5">captured</a> and <a href="#a2173e1b9b7c907c560fa9326b2a2352c">EarliestCaptures</a>.</p>

</div>
</div>

### EarliestCapture {#ae7243c11d421637329949fe0b62cf7c4}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">Instruction* anonymous{CaptureTracking.cpp}::EarliestCaptures::EarliestCapture = nullptr</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 185 of file <a href="/web-llvm/docs/api/files/lib/lib/analysis/capturetracking-cpp">CaptureTracking.cpp</a>.</p>


<p>Referenced by <a href="#acc3304c7668514d15b7e9d6d61676ce5">captured</a> and <a href="#a9bee3cf935e17c24637319fc402e1667">tooManyUses</a>.</p>

</div>
</div>

### F {#a265d5d74cfb20f6cf9146d52efe7bbfb}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">Function&amp; anonymous{CaptureTracking.cpp}::EarliestCaptures::F</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 193 of file <a href="/web-llvm/docs/api/files/lib/lib/analysis/capturetracking-cpp">CaptureTracking.cpp</a>.</p>


<p>Referenced by <a href="#a2173e1b9b7c907c560fa9326b2a2352c">EarliestCaptures</a> and <a href="#a9bee3cf935e17c24637319fc402e1667">tooManyUses</a>.</p>

</div>
</div>

### ReturnCaptures {#ac2d8451c44f0a5715233dc0b677c45d0}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool anonymous{CaptureTracking.cpp}::EarliestCaptures::ReturnCaptures</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 189 of file <a href="/web-llvm/docs/api/files/lib/lib/analysis/capturetracking-cpp">CaptureTracking.cpp</a>.</p>


<p>Referenced by <a href="#acc3304c7668514d15b7e9d6d61676ce5">captured</a> and <a href="#a2173e1b9b7c907c560fa9326b2a2352c">EarliestCaptures</a>.</p>

</div>
</div>

</div>

<hr/>

The documentation for this struct was generated from the following file:

<ul>
<li><a href="/web-llvm/docs/api/files/lib/lib/analysis/capturetracking-cpp">CaptureTracking.cpp</a></li>
</ul>

<hr/>

<p class="doxyGeneratedBy">Generated via <a href="https://github.com/xpack/doxygen2docusaurus">doxygen2docusaurus</a> by <a href="https://www.doxygen.nl">Doxygen</a> 1.15.0.</p>

</div>
