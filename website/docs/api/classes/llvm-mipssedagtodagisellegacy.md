---

# DO NOT EDIT!
# Automatically generated via doxygen2docusaurus by Doxygen.

slug: /api/classes/llvm/mipssedagtodagisellegacy
custom_edit_url: null
toc_max_heading_level: 4
keywords:
  - doxygen
  - reference
  - class

---

<div class="doxyPage">

# The `MipsSEDAGToDAGISelLegacy` Class Reference



## Declaration

<div class="doxyDeclaration">
class llvm::MipsSEDAGToDAGISelLegacy { ... }
</div>

## Included Headers

<div class="doxyIncludesList">#include "<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/mips/mipsseiseldagtodag-h">Target/Mips/MipsSEISelDAGToDAG.h</a>"
</div>

## Base class

<table class="doxyMembersIndex">

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">class</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/mipsdagtodagisellegacy">MipsDAGToDAGISelLegacy</a></td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a96a86ac60344c6329ef1d2a7543cd40c">MipsSEDAGToDAGISelLegacy</a> (MipsTargetMachine &amp;TM, CodeGenOptLevel OL)</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a227e431ba575d1ef75fd46c006a11b09">getAnalysisUsage</a> (AnalysisUsage &amp;AU) const override</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>getAnalysisUsage - Subclasses that override getAnalysisUsage must call this. <a href="#a227e431ba575d1ef75fd46c006a11b09">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

</table>


<p>Definition at line 127 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/mips/mipsseiseldagtodag-h">MipsSEISelDAGToDAG.h</a>.</p>


<div class="doxySectionDef">

## Public Constructors

### MipsSEDAGToDAGISelLegacy() {#a96a86ac60344c6329ef1d2a7543cd40c}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">MipsSEDAGToDAGISelLegacy::MipsSEDAGToDAGISelLegacy (<a href="/web-llvm/docs/api/classes/llvm/mipstargetmachine">MipsTargetMachine</a> &amp; TM, <a href="/web-llvm/docs/api/namespaces/llvm/#a8ec1bf8d7b792ca9fac56f8514db18d2">CodeGenOptLevel</a> OL)</td>
</tr>
</table>
</td>
<td class="doxyMemberLabelsRight">
<span class="doxyMemberLabels">
<span class="doxyMemberLabel explicit">explicit</span>
</span>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Declaration at line 129 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/mips/mipsseiseldagtodag-h">MipsSEISelDAGToDAG.h</a>, definition at line 1399 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/mips/mipsseiseldagtodag-cpp">MipsSEISelDAGToDAG.cpp</a>.</p>


<p>Reference <a href="/web-llvm/docs/api/classes/llvm/mipsdagtodagisellegacy/#ad39746393cdb736ea345de27c819a719">llvm::MipsDAGToDAGISelLegacy::MipsDAGToDAGISelLegacy</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Public Member Functions

### getAnalysisUsage() {#a227e431ba575d1ef75fd46c006a11b09}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void MipsSEDAGToDAGISelLegacy::getAnalysisUsage (<a href="/web-llvm/docs/api/classes/llvm/analysisusage">AnalysisUsage</a> &amp; AU)</td>
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

<p>getAnalysisUsage - Subclasses that override getAnalysisUsage must call this.</p>


<p>For MachineFunctionPasses, calling AU.preservesCFG() indicates that the pass does not modify the <a href="/web-llvm/docs/api/classes/llvm/machinebasicblock">MachineBasicBlock</a> CFG.</p>


<p>Declaration at line 130 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/mips/mipsseiseldagtodag-h">MipsSEISelDAGToDAG.h</a>, definition at line 42 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/mips/mipsseiseldagtodag-cpp">MipsSEISelDAGToDAG.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/classes/llvm/analysisusage/#ae0adcccca08fb686c9ce00f9397b660c">llvm::AnalysisUsage::addRequired</a> and <a href="/web-llvm/docs/api/classes/llvm/selectiondagisellegacy/#a77e4cdd5d33f676fb695a8204f7b70ff">llvm::SelectionDAGISelLegacy::getAnalysisUsage</a>.</p>

</div>
</div>

</div>

<hr/>

The documentation for this class was generated from the following files:

<ul>
<li><a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/mips/mipsseiseldagtodag-cpp">MipsSEISelDAGToDAG.cpp</a></li>
<li><a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/mips/mipsseiseldagtodag-h">MipsSEISelDAGToDAG.h</a></li>
</ul>

<hr/>

<p class="doxyGeneratedBy">Generated via <a href="https://github.com/xpack/doxygen2docusaurus">doxygen2docusaurus</a> by <a href="https://www.doxygen.nl">Doxygen</a> 1.15.0.</p>

</div>
