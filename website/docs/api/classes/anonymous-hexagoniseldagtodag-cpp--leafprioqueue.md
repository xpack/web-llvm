---

# DO NOT EDIT!
# Automatically generated via doxygen2docusaurus by Doxygen.

slug: /api/classes/anonymous-hexagoniseldagtodag-cpp-/leafprioqueue
custom_edit_url: null
toc_max_heading_level: 4
keywords:
  - doxygen
  - reference
  - class

---

<div class="doxyPage">

# The `LeafPrioQueue` Class Reference

<p>A specialized priority queue for WeigthedLeaves. <a href="#details">More...</a></p>

## Declaration

<div class="doxyDeclaration">
class anonymous{HexagonISelDAGToDAG.cpp}::LeafPrioQueue { ... }
</div>

## Public Constructors Index

<table class="doxyMembersIndex">

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a96e835c06ac0e045b9190f0923ccc7e6">LeafPrioQueue</a> (unsigned Opcode)</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a13e54870db702aaa5e44af2499d93ce1">empty</a> ()</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">size_t</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a13c4ba9286873d170718c6f84aac342f">size</a> ()</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#adbc64f3d500f04cdbdc3c02054c7948f">hasConst</a> ()</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/structs/anonymous-hexagoniseldagtodag-cpp-/weightedleaf">WeightedLeaf</a> &amp;</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a6fbcab2b677179388416db123e855790">top</a> ()</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/structs/anonymous-hexagoniseldagtodag-cpp-/weightedleaf">WeightedLeaf</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ad9efae3be66f56549ab63032e4b8dab1">pop</a> ()</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a798e25620446157a9daab52c3436a0ea">push</a> (WeightedLeaf L, bool SeparateConst=true)</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a7518fb8ba61e4fb42ac28952d0aa1396">pushToBottom</a> (WeightedLeaf L)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Push L to the bottom of the queue regardless of its weight. <a href="#a7518fb8ba61e4fb42ac28952d0aa1396">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/structs/anonymous-hexagoniseldagtodag-cpp-/weightedleaf">WeightedLeaf</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a6b72d8d09e9a7d6ebc8c4e9fbcf403ee">findSHL</a> (uint64_t MaxAmount)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Search for a SHL(x, [&lt;=MaxAmount]) subtree in the queue, return the one of lowest weight and remove it from the queue. <a href="#a6b72d8d09e9a7d6ebc8c4e9fbcf403ee">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/structs/anonymous-hexagoniseldagtodag-cpp-/weightedleaf">WeightedLeaf</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ac85ed3a65527ca452b614d54c9d8b401">findMULbyConst</a> ()</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/smallvector">SmallVector</a>&lt; <a href="/web-llvm/docs/api/structs/anonymous-hexagoniseldagtodag-cpp-/weightedleaf">WeightedLeaf</a>, 8 &gt;</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a83937be4bf20919005b953a1a9bf80e3">Q</a></td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a1028972987029163988f0f82e3ce1fcf">HaveConst</a></td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/structs/anonymous-hexagoniseldagtodag-cpp-/weightedleaf">WeightedLeaf</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a8e6ecc79cccb575ed829f6b9a7174b92">ConstElt</a></td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">unsigned</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ae01273efba3419824179b4cbae13f2da">Opcode</a></td>
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

<p>A specialized priority queue for WeigthedLeaves.</p>


<p>It automatically folds constants and allows removal of non-top elements while maintaining the priority order.</p>


<p>Definition at line 1824 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/hexagon/hexagoniseldagtodag-cpp">HexagonISelDAGToDAG.cpp</a>.</p>


<div class="doxySectionDef">

## Public Constructors

### LeafPrioQueue() {#a96e835c06ac0e045b9190f0923ccc7e6}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">anonymous{HexagonISelDAGToDAG.cpp}::LeafPrioQueue::LeafPrioQueue (unsigned Opcode)</td>
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



<p>Definition at line 1888 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/hexagon/hexagoniseldagtodag-cpp">HexagonISelDAGToDAG.cpp</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Public Member Functions

### empty() {#a13e54870db702aaa5e44af2499d93ce1}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool anonymous{HexagonISelDAGToDAG.cpp}::LeafPrioQueue::empty ()</td>
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



<p>Definition at line 1831 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/hexagon/hexagoniseldagtodag-cpp">HexagonISelDAGToDAG.cpp</a>.</p>

</div>
</div>

### findMULbyConst() {#ac85ed3a65527ca452b614d54c9d8b401}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">WeightedLeaf LeafPrioQueue::findMULbyConst ()</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 1886 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/hexagon/hexagoniseldagtodag-cpp">HexagonISelDAGToDAG.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/structs/anonymous-hexagoniseldagtodag-cpp-/weightedleaf/#a20ee1cbb44f65ad3a567b9af1489047f">anonymous{HexagonISelDAGToDAG.cpp}::WeightedLeaf::Compare</a>, <a href="/web-llvm/docs/api/classes/llvm/sdvalue/#ac969b6c833cfa44c1b4fcd5790268340">llvm::SDValue::getConstantOperandVal</a>, <a href="/web-llvm/docs/api/classes/llvm/sdvalue/#ae779a9d142e6318d8fb0e4f0da32af0f">llvm::SDValue::getOpcode</a>, <a href="/web-llvm/docs/api/classes/llvm/sdvalue/#a977e54da724d62e7b08e2ad69723731e">llvm::SDValue::getOperand</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a92ca992e52dddc420f4b069cae06dfbe">llvm::isa</a> and <a href="/web-llvm/docs/api/namespaces/llvm/isd/#a22ea9cec080dd5f4f47ba234c2f59110ad8aec9273962cf78d087090c11a1dd1c">llvm::ISD::MUL</a>.</p>

</div>
</div>

### findSHL() {#a6b72d8d09e9a7d6ebc8c4e9fbcf403ee}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">WeightedLeaf LeafPrioQueue::findSHL (uint64_t MaxAmount)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Search for a SHL(x, [&lt;=MaxAmount]) subtree in the queue, return the one of lowest weight and remove it from the queue.</p>

<p>Definition at line 1884 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/hexagon/hexagoniseldagtodag-cpp">HexagonISelDAGToDAG.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/structs/anonymous-hexagoniseldagtodag-cpp-/weightedleaf/#a20ee1cbb44f65ad3a567b9af1489047f">anonymous{HexagonISelDAGToDAG.cpp}::WeightedLeaf::Compare</a>, <a href="/web-llvm/docs/api/classes/llvm/sdvalue/#ac969b6c833cfa44c1b4fcd5790268340">llvm::SDValue::getConstantOperandVal</a>, <a href="/web-llvm/docs/api/classes/llvm/sdvalue/#ae779a9d142e6318d8fb0e4f0da32af0f">llvm::SDValue::getOpcode</a>, <a href="/web-llvm/docs/api/classes/llvm/sdvalue/#a977e54da724d62e7b08e2ad69723731e">llvm::SDValue::getOperand</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a92ca992e52dddc420f4b069cae06dfbe">llvm::isa</a> and <a href="/web-llvm/docs/api/namespaces/llvm/isd/#a22ea9cec080dd5f4f47ba234c2f59110a8cc94e03dea594863073a02f5bb94997">llvm::ISD::SHL</a>.</p>

</div>
</div>

### hasConst() {#adbc64f3d500f04cdbdc3c02054c7948f}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool anonymous{HexagonISelDAGToDAG.cpp}::LeafPrioQueue::hasConst ()</td>
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



<p>Definition at line 1839 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/hexagon/hexagoniseldagtodag-cpp">HexagonISelDAGToDAG.cpp</a>.</p>

</div>
</div>

### pop() {#ad9efae3be66f56549ab63032e4b8dab1}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">WeightedLeaf anonymous{HexagonISelDAGToDAG.cpp}::LeafPrioQueue::pop ()</td>
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



<p>Definition at line 1849 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/hexagon/hexagoniseldagtodag-cpp">HexagonISelDAGToDAG.cpp</a>.</p>


<p>Reference <a href="/web-llvm/docs/api/structs/anonymous-hexagoniseldagtodag-cpp-/weightedleaf/#a20ee1cbb44f65ad3a567b9af1489047f">anonymous{HexagonISelDAGToDAG.cpp}::WeightedLeaf::Compare</a>.</p>

</div>
</div>

### push() {#a798e25620446157a9daab52c3436a0ea}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void anonymous{HexagonISelDAGToDAG.cpp}::LeafPrioQueue::push (<a href="/web-llvm/docs/api/structs/anonymous-hexagoniseldagtodag-cpp-/weightedleaf">WeightedLeaf</a> L, bool SeparateConst=<a href="/web-llvm/docs/api/files/lib/lib/analysis/basicaliasanalysis-cpp/#af6d5cafbdfc5313e65d990120021a3ec">true</a>)</td>
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



<p>Definition at line 1858 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/hexagon/hexagoniseldagtodag-cpp">HexagonISelDAGToDAG.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/namespaces/llvm/isd/#a22ea9cec080dd5f4f47ba234c2f59110a269996b43a1f3e1d1f84a70fd4387535">llvm::ISD::ADD</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#ac4fc845f5ed92de63cd4474f128f5fc5">llvm::cast</a>, <a href="/web-llvm/docs/api/structs/anonymous-hexagoniseldagtodag-cpp-/weightedleaf/#a20ee1cbb44f65ad3a567b9af1489047f">anonymous{HexagonISelDAGToDAG.cpp}::WeightedLeaf::Compare</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a92ca992e52dddc420f4b069cae06dfbe">llvm::isa</a> and <a href="/web-llvm/docs/api/namespaces/llvm/isd/#a22ea9cec080dd5f4f47ba234c2f59110ad8aec9273962cf78d087090c11a1dd1c">llvm::ISD::MUL</a>.</p>

</div>
</div>

### pushToBottom() {#a7518fb8ba61e4fb42ac28952d0aa1396}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void anonymous{HexagonISelDAGToDAG.cpp}::LeafPrioQueue::pushToBottom (<a href="/web-llvm/docs/api/structs/anonymous-hexagoniseldagtodag-cpp-/weightedleaf">WeightedLeaf</a> L)</td>
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

<p>Push L to the bottom of the queue regardless of its weight.</p>


<p>If L is constant, it will not be folded with other constants in the queue.</p>


<p>Definition at line 1877 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/hexagon/hexagoniseldagtodag-cpp">HexagonISelDAGToDAG.cpp</a>.</p>


<p>Reference <a href="/web-llvm/docs/api/files/lib/lib/remarks/bitstreamremarkserializer-cpp/#a720622fc32fd2435f7726d832d851ea6">push</a>.</p>

</div>
</div>

### size() {#a13c4ba9286873d170718c6f84aac342f}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">size_t anonymous{HexagonISelDAGToDAG.cpp}::LeafPrioQueue::size ()</td>
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



<p>Definition at line 1835 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/hexagon/hexagoniseldagtodag-cpp">HexagonISelDAGToDAG.cpp</a>.</p>

</div>
</div>

### top() {#a6fbcab2b677179388416db123e855790}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">const WeightedLeaf &amp; anonymous{HexagonISelDAGToDAG.cpp}::LeafPrioQueue::top ()</td>
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



<p>Definition at line 1843 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/hexagon/hexagoniseldagtodag-cpp">HexagonISelDAGToDAG.cpp</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Private Member Attributes

### ConstElt {#a8e6ecc79cccb575ed829f6b9a7174b92}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">WeightedLeaf anonymous{HexagonISelDAGToDAG.cpp}::LeafPrioQueue::ConstElt</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 1827 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/hexagon/hexagoniseldagtodag-cpp">HexagonISelDAGToDAG.cpp</a>.</p>

</div>
</div>

### HaveConst {#a1028972987029163988f0f82e3ce1fcf}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool anonymous{HexagonISelDAGToDAG.cpp}::LeafPrioQueue::HaveConst</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 1826 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/hexagon/hexagoniseldagtodag-cpp">HexagonISelDAGToDAG.cpp</a>.</p>

</div>
</div>

### Opcode {#ae01273efba3419824179b4cbae13f2da}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">unsigned anonymous{HexagonISelDAGToDAG.cpp}::LeafPrioQueue::Opcode</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 1828 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/hexagon/hexagoniseldagtodag-cpp">HexagonISelDAGToDAG.cpp</a>.</p>

</div>
</div>

### Q {#a83937be4bf20919005b953a1a9bf80e3}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">SmallVector&lt;WeightedLeaf, 8&gt; anonymous{HexagonISelDAGToDAG.cpp}::LeafPrioQueue::Q</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 1825 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/hexagon/hexagoniseldagtodag-cpp">HexagonISelDAGToDAG.cpp</a>.</p>

</div>
</div>

</div>

<hr/>

The documentation for this class was generated from the following file:

<ul>
<li><a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/hexagon/hexagoniseldagtodag-cpp">HexagonISelDAGToDAG.cpp</a></li>
</ul>

<hr/>

<p class="doxyGeneratedBy">Generated via <a href="https://github.com/xpack/doxygen2docusaurus">doxygen2docusaurus</a> by <a href="https://www.doxygen.nl">Doxygen</a> 1.14.0.</p>

</div>
