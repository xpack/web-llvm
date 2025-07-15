---

# DO NOT EDIT!
# Automatically generated via doxygen2docusaurus by Doxygen.

slug: /api/structs/llvm/spillplacement/blockconstraint
custom_edit_url: null
toc_max_heading_level: 4
keywords:
  - doxygen
  - reference
  - struct

---

<div class="doxyPage">

# The `BlockConstraint` Struct Reference

<p><a href="/web-llvm/docs/api/structs/llvm/spillplacement/blockconstraint">BlockConstraint</a> - Entry and exit constraints for a basic block. <a href="#details">More...</a></p>

## Declaration

<div class="doxyDeclaration">
struct llvm::SpillPlacement::BlockConstraint { ... }
</div>

## Included Headers

<div class="doxyIncludesList">#include "<a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/codegen/spillplacement-h">llvm/CodeGen/SpillPlacement.h</a>"
</div>

## Public Member Functions Index

<table class="doxyMembersIndex">

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">void</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a5c51fb97e1e2f08e23feafb387c5d4e1">print</a> (raw_ostream &amp;OS) const</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">void</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a3441def385335310144f7a6d27b885d7">dump</a> () const</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">unsigned</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#addcae7ef74d3f00004c6dfcc5775c1e3">Number</a></td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Basic block number (from MBB::getNumber()). <a href="#addcae7ef74d3f00004c6dfcc5775c1e3">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/spillplacement/#ab09623fee8a653165a7cc624b8eaaa8c">BorderConstraint</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#aab2805f3c0c929660eb309b0fe9e9ee3">Entry</a></td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Constraint on block entry. <a href="#aab2805f3c0c929660eb309b0fe9e9ee3">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/spillplacement/#ab09623fee8a653165a7cc624b8eaaa8c">BorderConstraint</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a1e36bf5c748d62c8fa43ff7827f94684">Exit</a></td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Constraint on block exit. <a href="#a1e36bf5c748d62c8fa43ff7827f94684">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">bool</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#aa94bff6fdd53de69a5ca85f8ff69a37c">ChangesValue</a></td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>True when this block changes the value of the live range. <a href="#aa94bff6fdd53de69a5ca85f8ff69a37c">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

</table>

## Description {#details}

<p><a href="/web-llvm/docs/api/structs/llvm/spillplacement/blockconstraint">BlockConstraint</a> - Entry and exit constraints for a basic block.</p>

<p>Definition at line 90 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/codegen/spillplacement-h">SpillPlacement.h</a>.</p>


<div class="doxySectionDef">

## Public Member Functions

### dump() {#a3441def385335310144f7a6d27b885d7}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void SpillPlacement::BlockConstraint::dump ()</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Declaration at line 101 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/codegen/spillplacement-h">SpillPlacement.h</a>, definition at line 427 of file <a href="/web-llvm/docs/api/files/lib/lib/codegen/spillplacement-cpp">SpillPlacement.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/namespaces/llvm/#a7c46c742c31be54870e2038048e6b391">llvm::dbgs</a> and <a href="/web-llvm/docs/api/namespaces/llvm/#a50bf746ca1858c0e272e3a802fc27942">llvm::print</a>.</p>

</div>
</div>

### print() {#a5c51fb97e1e2f08e23feafb387c5d4e1}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void SpillPlacement::BlockConstraint::print (<a href="/web-llvm/docs/api/classes/llvm/raw-ostream">raw_ostream</a> &amp; OS)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Declaration at line 100 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/codegen/spillplacement-h">SpillPlacement.h</a>, definition at line 409 of file <a href="/web-llvm/docs/api/files/lib/lib/codegen/spillplacement-cpp">SpillPlacement.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/namespaces/llvm/callingconv/#ac6aa1387c4375260e2468eb5a77fdb4cafd841a49aec1539bc88abc8ff9e170fb">llvm::CallingConv::C</a>, <a href="#aa94bff6fdd53de69a5ca85f8ff69a37c">ChangesValue</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a7c46c742c31be54870e2038048e6b391">llvm::dbgs</a>, <a href="/web-llvm/docs/api/classes/llvm/spillplacement/#ab09623fee8a653165a7cc624b8eaaa8ca49b6f21cf41c5b608cb5645bc70d36b8">llvm::SpillPlacement::DontCare</a>, <a href="#aab2805f3c0c929660eb309b0fe9e9ee3">Entry</a>, <a href="#a1e36bf5c748d62c8fa43ff7827f94684">Exit</a>, <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/support/errorhandling-h/#ace243f5c25697a1107cce46626b3dc94">llvm_unreachable</a>, <a href="/web-llvm/docs/api/classes/llvm/spillplacement/#ab09623fee8a653165a7cc624b8eaaa8ca043a091e52f465df92623f5f17477837">llvm::SpillPlacement::MustSpill</a>, <a href="#addcae7ef74d3f00004c6dfcc5775c1e3">Number</a>, <a href="/web-llvm/docs/api/classes/llvm/spillplacement/#ab09623fee8a653165a7cc624b8eaaa8ca821efd84662975133aa7c60d1a84fa42">llvm::SpillPlacement::PrefBoth</a>, <a href="/web-llvm/docs/api/classes/llvm/spillplacement/#ab09623fee8a653165a7cc624b8eaaa8caca6da2dad218232636b80854d81a6e1c">llvm::SpillPlacement::PrefReg</a>, <a href="/web-llvm/docs/api/classes/llvm/spillplacement/#ab09623fee8a653165a7cc624b8eaaa8caf5efe10871d66719c8668d09d768e740">llvm::SpillPlacement::PrefSpill</a> and <a href="/web-llvm/docs/api/namespaces/llvm/#aba83a013c55b19255697393a10d9165e">llvm::toString</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Public Member Attributes

### ChangesValue {#aa94bff6fdd53de69a5ca85f8ff69a37c}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool llvm::SpillPlacement::BlockConstraint::ChangesValue</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>True when this block changes the value of the live range.</p>


<p>This means the block has a non-PHI def. When this is false, a live-in value on the stack can be live-out on the stack without inserting a spill.</p>


<p>Definition at line 98 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/codegen/spillplacement-h">SpillPlacement.h</a>.</p>


<p>Referenced by <a href="#a5c51fb97e1e2f08e23feafb387c5d4e1">print</a>.</p>

</div>
</div>

### Entry {#aab2805f3c0c929660eb309b0fe9e9ee3}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">BorderConstraint llvm::SpillPlacement::BlockConstraint::Entry</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Constraint on block entry.</p>

<p>Definition at line 92 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/codegen/spillplacement-h">SpillPlacement.h</a>.</p>


<p>Referenced by <a href="#a5c51fb97e1e2f08e23feafb387c5d4e1">print</a>.</p>

</div>
</div>

### Exit {#a1e36bf5c748d62c8fa43ff7827f94684}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">BorderConstraint llvm::SpillPlacement::BlockConstraint::Exit</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Constraint on block exit.</p>

<p>Definition at line 93 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/codegen/spillplacement-h">SpillPlacement.h</a>.</p>


<p>Referenced by <a href="#a5c51fb97e1e2f08e23feafb387c5d4e1">print</a>.</p>

</div>
</div>

### Number {#addcae7ef74d3f00004c6dfcc5775c1e3}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">unsigned llvm::SpillPlacement::BlockConstraint::Number</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Basic block number (from MBB::getNumber()).</p>

<p>Definition at line 91 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/codegen/spillplacement-h">SpillPlacement.h</a>.</p>


<p>Referenced by <a href="#a5c51fb97e1e2f08e23feafb387c5d4e1">print</a>.</p>

</div>
</div>

</div>

<hr/>

The documentation for this struct was generated from the following files:

<ul>
<li><a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/codegen/spillplacement-h">SpillPlacement.h</a></li>
<li><a href="/web-llvm/docs/api/files/lib/lib/codegen/spillplacement-cpp">SpillPlacement.cpp</a></li>
</ul>

<hr/>

<p class="doxyGeneratedBy">Generated via <a href="https://github.com/xpack/doxygen2docusaurus">doxygen2docusaurus</a> by <a href="https://www.doxygen.nl">Doxygen</a> 1.14.0.</p>

</div>
