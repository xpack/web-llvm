---

# DO NOT EDIT!
# Automatically generated via doxygen2docusaurus by Doxygen.

slug: /api/structs/anonymous-capturetracking-cpp-/simplecapturetracker
custom_edit_url: null
toc_max_heading_level: 4
keywords:
  - doxygen
  - reference
  - struct

---

<div class="doxyPage">

# The `SimpleCaptureTracker` Struct Reference



## Declaration

<div class="doxyDeclaration">
struct anonymous{CaptureTracking.cpp}::SimpleCaptureTracker { ... }
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a30577ab8ddbd645b8ef89eb6763551b3">SimpleCaptureTracker</a> (bool ReturnCaptures)</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ad5a1c4d387d926c0b09402e1e1e0c9e0">tooManyUses</a> () override</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>tooManyUses - The depth of traversal has breached a limit. <a href="#ad5a1c4d387d926c0b09402e1e1e0c9e0">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">bool</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a6134360027974f69765c931b0c22074e">captured</a> (const Use *U) override</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>captured - Information about the pointer was captured by the user of use U. <a href="#a6134360027974f69765c931b0c22074e">More...</a></p>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a68abfe2c0d9bc25b8487cee1d821edf5">ReturnCaptures</a></td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#afc3749d345a3f6efe7ed5c866e403b2a">Captured</a> = false</td>
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


<p>Definition at line 75 of file <a href="/web-llvm/docs/api/files/lib/lib/analysis/capturetracking-cpp">CaptureTracking.cpp</a>.</p>


<div class="doxySectionDef">

## Public Constructors

### SimpleCaptureTracker() {#a30577ab8ddbd645b8ef89eb6763551b3}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">anonymous{CaptureTracking.cpp}::SimpleCaptureTracker::SimpleCaptureTracker (bool ReturnCaptures)</td>
</tr>
</table>
</td>
<td class="doxyMemberLabelsRight">
<span class="doxyMemberLabels">
<span class="doxyMemberLabel inline">inline</span>
<span class="doxyMemberLabel explicit">explicit</span>
</span>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 76 of file <a href="/web-llvm/docs/api/files/lib/lib/analysis/capturetracking-cpp">CaptureTracking.cpp</a>.</p>


<p>Reference <a href="#a68abfe2c0d9bc25b8487cee1d821edf5">ReturnCaptures</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Public Member Functions

### captured() {#a6134360027974f69765c931b0c22074e}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool anonymous{CaptureTracking.cpp}::SimpleCaptureTracker::captured (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/use">Use</a> * U)</td>
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


<p>Definition at line 84 of file <a href="/web-llvm/docs/api/files/lib/lib/analysis/capturetracking-cpp">CaptureTracking.cpp</a>.</p>


<p>References <a href="#afc3749d345a3f6efe7ed5c866e403b2a">Captured</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a7c46c742c31be54870e2038048e6b391">llvm::dbgs</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a92ca992e52dddc420f4b069cae06dfbe">llvm::isa</a>, <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/support/debug-h/#a196897517069dda1bdb549e24468f7d7">LLVM_DEBUG</a> and <a href="#a68abfe2c0d9bc25b8487cee1d821edf5">ReturnCaptures</a>.</p>

</div>
</div>

### tooManyUses() {#ad5a1c4d387d926c0b09402e1e1e0c9e0}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void anonymous{CaptureTracking.cpp}::SimpleCaptureTracker::tooManyUses ()</td>
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


<p>There may be capturing instructions that will not be passed into <a href="#a6134360027974f69765c931b0c22074e">captured()</a>.</p>


<p>Definition at line 79 of file <a href="/web-llvm/docs/api/files/lib/lib/analysis/capturetracking-cpp">CaptureTracking.cpp</a>.</p>


<p>References <a href="#afc3749d345a3f6efe7ed5c866e403b2a">Captured</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a7c46c742c31be54870e2038048e6b391">llvm::dbgs</a> and <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/support/debug-h/#a196897517069dda1bdb549e24468f7d7">LLVM_DEBUG</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Public Member Attributes

### Captured {#afc3749d345a3f6efe7ed5c866e403b2a}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool anonymous{CaptureTracking.cpp}::SimpleCaptureTracker::Captured = false</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 96 of file <a href="/web-llvm/docs/api/files/lib/lib/analysis/capturetracking-cpp">CaptureTracking.cpp</a>.</p>


<p>Referenced by <a href="#a6134360027974f69765c931b0c22074e">captured</a> and <a href="#ad5a1c4d387d926c0b09402e1e1e0c9e0">tooManyUses</a>.</p>

</div>
</div>

### ReturnCaptures {#a68abfe2c0d9bc25b8487cee1d821edf5}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool anonymous{CaptureTracking.cpp}::SimpleCaptureTracker::ReturnCaptures</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 94 of file <a href="/web-llvm/docs/api/files/lib/lib/analysis/capturetracking-cpp">CaptureTracking.cpp</a>.</p>


<p>Referenced by <a href="#a6134360027974f69765c931b0c22074e">captured</a> and <a href="#a30577ab8ddbd645b8ef89eb6763551b3">SimpleCaptureTracker</a>.</p>

</div>
</div>

</div>

<hr/>

The documentation for this struct was generated from the following file:

<ul>
<li><a href="/web-llvm/docs/api/files/lib/lib/analysis/capturetracking-cpp">CaptureTracking.cpp</a></li>
</ul>

<hr/>

<p class="doxyGeneratedBy">Generated via <a href="https://github.com/xpack/doxygen2docusaurus">doxygen2docusaurus</a> by <a href="https://www.doxygen.nl">Doxygen</a> 1.14.0.</p>

</div>
