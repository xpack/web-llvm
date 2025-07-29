---

# DO NOT EDIT!
# Automatically generated via doxygen2docusaurus by Doxygen.

slug: /api/classes/anonymous-optimizephis-cpp-/optimizephis
custom_edit_url: null
toc_max_heading_level: 4
keywords:
  - doxygen
  - reference
  - class

---

<div class="doxyPage">

# `OptimizePHIs` Class



## Declaration

<div class="doxyDeclaration">
class anonymous{OptimizePHIs.cpp}::OptimizePHIs { ... }
</div>

## Private Member Typedefs Index

<table class="doxyMembersIndex">

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">using</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a99f7aeda4e05770066d07fa3228dbecf">InstrSet</a> = <a href="/web-llvm/docs/api/classes/llvm/smallptrset">SmallPtrSet</a>&lt; <a href="/web-llvm/docs/api/classes/llvm/machineinstr">MachineInstr</a> *, 16 &gt;</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">using</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a93561b3f931d43cecbf171df80234b14">InstrSetIterator</a> = <a href="/web-llvm/docs/api/classes/llvm/smallptrsetiterator">SmallPtrSetIterator</a>&lt; <a href="/web-llvm/docs/api/classes/llvm/machineinstr">MachineInstr</a> * &gt;</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a84f1822dce1d5363a4cbc32c0401e52e">run</a> (MachineFunction &amp;Fn)</td>
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

## Private Member Functions Index

<table class="doxyMembersIndex">

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">bool</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a6437ddf1189c6ab703579fc870292b5f">IsSingleValuePHICycle</a> (MachineInstr *MI, unsigned &amp;SingleValReg, InstrSet &amp;PHIsInCycle)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>IsSingleValuePHICycle - Check if MI is a PHI where all the source operands are copies of SingleValReg, possibly via copies through other PHIs. <a href="#a6437ddf1189c6ab703579fc870292b5f">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">bool</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a29f58332966d84283cc07f0a27a5a868">IsDeadPHICycle</a> (MachineInstr *MI, InstrSet &amp;PHIsInCycle)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>IsDeadPHICycle - Check if the register defined by a PHI is only used by other PHIs in a cycle. <a href="#a29f58332966d84283cc07f0a27a5a868">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">bool</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a5ff4c3ea103a6adec90964a97be1bbcb">OptimizeBB</a> (MachineBasicBlock &amp;MBB)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>OptimizeBB - Remove dead PHI cycles and PHI cycles that can be replaced by a single value. <a href="#a5ff4c3ea103a6adec90964a97be1bbcb">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

</table>

## Private Member Attributes Index

<table class="doxyMembersIndex">

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/machineregisterinfo">MachineRegisterInfo</a> *</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a6ea5b8a896473cca4658921b530fcb61">MRI</a> = nullptr</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/targetinstrinfo">TargetInstrInfo</a> *</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#aa8dac0bbe50fd6366a3746235051fb95">TII</a> = nullptr</td>
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


<p>Definition at line 36 of file <a href="/web-llvm/docs/api/files/lib/lib/codegen/optimizephis-cpp">OptimizePHIs.cpp</a>.</p>


<div class="doxySectionDef">

## Private Member Typedefs

### InstrSet {#a99f7aeda4e05770066d07fa3228dbecf}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">using anonymous{OptimizePHIs.cpp}::OptimizePHIs::InstrSet =  SmallPtrSet&lt;MachineInstr *, 16&gt;</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 44 of file <a href="/web-llvm/docs/api/files/lib/lib/codegen/optimizephis-cpp">OptimizePHIs.cpp</a>.</p>

</div>
</div>

### InstrSetIterator {#a93561b3f931d43cecbf171df80234b14}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">using anonymous{OptimizePHIs.cpp}::OptimizePHIs::InstrSetIterator =  SmallPtrSetIterator&lt;MachineInstr *&gt;</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 45 of file <a href="/web-llvm/docs/api/files/lib/lib/codegen/optimizephis-cpp">OptimizePHIs.cpp</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Public Member Functions

### run() {#a84f1822dce1d5363a4cbc32c0401e52e}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool OptimizePHIs::run (<a href="/web-llvm/docs/api/classes/llvm/machinefunction">MachineFunction</a> &amp; Fn)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 41 of file <a href="/web-llvm/docs/api/files/lib/lib/codegen/optimizephis-cpp">OptimizePHIs.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/classes/llvm/targetsubtargetinfo/#acd858ed72f11db9444617740c3622608">llvm::TargetSubtargetInfo::getInstrInfo</a>, <a href="/web-llvm/docs/api/classes/llvm/machinefunction/#a810234b6b3d223b7c74a4253fcc5ea5e">llvm::MachineFunction::getRegInfo</a>, <a href="/web-llvm/docs/api/classes/llvm/machinefunction/#a3825368aca2bc1550d173660df4da6a6">llvm::MachineFunction::getSubtarget</a> and <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/arm/armslshardening-cpp/#a5958512eae2979bd2eb383977996a600">MBB</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Private Member Functions

### IsDeadPHICycle() {#a29f58332966d84283cc07f0a27a5a868}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool OptimizePHIs::IsDeadPHICycle (<a href="/web-llvm/docs/api/classes/llvm/machineinstr">MachineInstr</a> * MI, <a href="/web-llvm/docs/api/classes/llvm/smallptrset">InstrSet</a> &amp; PHIsInCycle)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>IsDeadPHICycle - Check if the register defined by a PHI is only used by other PHIs in a cycle.</p>

<p>Definition at line 49 of file <a href="/web-llvm/docs/api/files/lib/lib/codegen/optimizephis-cpp">OptimizePHIs.cpp</a>.</p>

</div>
</div>

### IsSingleValuePHICycle() {#a6437ddf1189c6ab703579fc870292b5f}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool OptimizePHIs::IsSingleValuePHICycle (<a href="/web-llvm/docs/api/classes/llvm/machineinstr">MachineInstr</a> * MI, unsigned &amp; SingleValReg, <a href="/web-llvm/docs/api/classes/llvm/smallptrset">InstrSet</a> &amp; PHIsInCycle)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>IsSingleValuePHICycle - Check if MI is a PHI where all the source operands are copies of SingleValReg, possibly via copies through other PHIs.</p>


<p>If SingleValReg is zero on entry, it is set to the register with the single non-copy value. PHIsInCycle is a set used to keep track of the PHIs that have been scanned. PHIs may be grouped by cycle, several cycles or chains.</p>


<p>Definition at line 47 of file <a href="/web-llvm/docs/api/files/lib/lib/codegen/optimizephis-cpp">OptimizePHIs.cpp</a>.</p>

</div>
</div>

### OptimizeBB() {#a5ff4c3ea103a6adec90964a97be1bbcb}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool OptimizePHIs::OptimizeBB (<a href="/web-llvm/docs/api/classes/llvm/machinebasicblock">MachineBasicBlock</a> &amp; MBB)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>OptimizeBB - Remove dead PHI cycles and PHI cycles that can be replaced by a single value.</p>

<p>Definition at line 50 of file <a href="/web-llvm/docs/api/files/lib/lib/codegen/optimizephis-cpp">OptimizePHIs.cpp</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Private Member Attributes

### MRI {#a6ea5b8a896473cca4658921b530fcb61}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">MachineRegisterInfo* anonymous{OptimizePHIs.cpp}::OptimizePHIs::MRI = nullptr</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 37 of file <a href="/web-llvm/docs/api/files/lib/lib/codegen/optimizephis-cpp">OptimizePHIs.cpp</a>.</p>

</div>
</div>

### TII {#aa8dac0bbe50fd6366a3746235051fb95}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">const TargetInstrInfo* anonymous{OptimizePHIs.cpp}::OptimizePHIs::TII = nullptr</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 38 of file <a href="/web-llvm/docs/api/files/lib/lib/codegen/optimizephis-cpp">OptimizePHIs.cpp</a>.</p>

</div>
</div>

</div>

<hr/>

The documentation for this class was generated from the following file:

<ul>
<li><a href="/web-llvm/docs/api/files/lib/lib/codegen/optimizephis-cpp">OptimizePHIs.cpp</a></li>
</ul>

<hr/>

<p class="doxyGeneratedBy">Generated via <a href="https://github.com/xpack/doxygen2docusaurus">doxygen2docusaurus</a> by <a href="https://www.doxygen.nl">Doxygen</a> 1.15.0.</p>

</div>
