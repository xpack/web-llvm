---

# DO NOT EDIT!
# Automatically generated via doxygen2docusaurus by Doxygen.

slug: /api/classes/llvm/po-iterator-storage-3fc582f4b807835050bb72d4ed1f0e76
custom_edit_url: null
toc_max_heading_level: 4
keywords:
  - doxygen
  - reference
  - class

---

<div class="doxyPage">

# The `po_iterator_storage` Class Template Reference



## Declaration

<div class="doxyDeclaration">
class llvm::po_iterator_storage&lt;LoopBounds, true&gt; { ... }
</div>

## Public Constructors Index

<table class="doxyMembersIndex">

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ac357f99e36b35bf15cdf9c8f25af720a">po_iterator_storage</a> (LoopBounds &amp;lb)</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a3b2e0991ef19713f3f93145bfc572bde">finishPostorder</a> (const MachineBasicBlock *)</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a12289268ab155993fbbeef5ef8a2ffa4">insertEdge</a> (std::optional&lt; const MachineBasicBlock * &gt; From, const MachineBasicBlock *To)</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">LoopBounds &amp;</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ac833f92e49a959898b1757e32ae33002">LB</a></td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">LoopBounds</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/po-iterator-storage/#a21a846c4c88e0caf187c495898fbf339">Visited</a></td>
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


<p>Definition at line 491 of file <a href="/web-llvm/docs/api/files/lib/lib/codegen/machinetracemetrics-cpp">MachineTraceMetrics.cpp</a>.</p>


<div class="doxySectionDef">

## Public Constructors

### po\_iterator\_storage() {#ac357f99e36b35bf15cdf9c8f25af720a}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">llvm::po_iterator_storage&lt; LoopBounds, true &gt;::po_iterator_storage (LoopBounds &amp; lb)</td>
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



<p>Definition at line 495 of file <a href="/web-llvm/docs/api/files/lib/lib/codegen/machinetracemetrics-cpp">MachineTraceMetrics.cpp</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Public Member Functions

### finishPostorder() {#a3b2e0991ef19713f3f93145bfc572bde}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void llvm::po_iterator_storage&lt; LoopBounds, true &gt;::finishPostorder (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/machinebasicblock">MachineBasicBlock</a> *)</td>
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



<p>Definition at line 497 of file <a href="/web-llvm/docs/api/files/lib/lib/codegen/machinetracemetrics-cpp">MachineTraceMetrics.cpp</a>.</p>

</div>
</div>

### insertEdge() {#a12289268ab155993fbbeef5ef8a2ffa4}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool llvm::po_iterator_storage&lt; LoopBounds, true &gt;::insertEdge (std::optional&lt; <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/machinebasicblock">MachineBasicBlock</a> * &gt; From, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/machinebasicblock">MachineBasicBlock</a> * To)</td>
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



<p>Definition at line 499 of file <a href="/web-llvm/docs/api/files/lib/lib/codegen/machinetracemetrics-cpp">MachineTraceMetrics.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/classes/llvm/machinebasicblock/#a3aa22d521bd6a7e6b9f35545dc7b0f1e">llvm::MachineBasicBlock::getNumber</a>, <a href="/web-llvm/docs/api/structs/llvm/machinetracemetrics/traceblockinfo/#a8e39c65ba3a21fb041f682ab7b2be929">llvm::MachineTraceMetrics::TraceBlockInfo::hasValidDepth</a>, <a href="/web-llvm/docs/api/structs/llvm/machinetracemetrics/traceblockinfo/#ad636cb57c36fe3c776bb458c552435ac">llvm::MachineTraceMetrics::TraceBlockInfo::hasValidHeight</a> and <a href="/web-llvm/docs/api/files/lib/lib/codegen/machinetracemetrics-cpp/#a845058902483d2afbab93214dcce8684">isExitingLoop</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Private Member Attributes

### LB {#ac833f92e49a959898b1757e32ae33002}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">LoopBounds&amp; llvm::po_iterator_storage&lt; LoopBounds, true &gt;::LB</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 492 of file <a href="/web-llvm/docs/api/files/lib/lib/codegen/machinetracemetrics-cpp">MachineTraceMetrics.cpp</a>.</p>

</div>
</div>

### Visited {#a21a846c4c88e0caf187c495898fbf339}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">LoopBounds llvm::po_iterator_storage&lt; LoopBounds, External &gt;::Visited</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 60 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/adt/postorderiterator-h">PostOrderIterator.h</a>.</p>

</div>
</div>

</div>

<hr/>

The documentation for this class was generated from the following files:

<ul>
<li><a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/adt/postorderiterator-h">PostOrderIterator.h</a></li>
<li><a href="/web-llvm/docs/api/files/lib/lib/codegen/machinetracemetrics-cpp">MachineTraceMetrics.cpp</a></li>
</ul>

<hr/>

<p class="doxyGeneratedBy">Generated via <a href="https://github.com/xpack/doxygen2docusaurus">doxygen2docusaurus</a> by <a href="https://www.doxygen.nl">Doxygen</a> 1.15.0.</p>

</div>
