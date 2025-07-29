---

# DO NOT EDIT!
# Automatically generated via doxygen2docusaurus by Doxygen.

slug: /api/structs/anonymous-implicitnullchecks-cpp-/implicitnullchecks/dependenceresult
custom_edit_url: null
toc_max_heading_level: 4
keywords:
  - doxygen
  - reference
  - struct

---

<div class="doxyPage">

# `DependenceResult` Struct

<p>A data type for representing the result computed by <span class="doxyComputerOutput">computeDependence</span>. <a href="#details">More...</a></p>

## Declaration

<div class="doxyDeclaration">
struct anonymous{ImplicitNullChecks.cpp}::ImplicitNullChecks::DependenceResult { ... }
</div>

## Public Constructors Index

<table class="doxyMembersIndex">

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ac4482b60fb9bbbcd12311f77a83d568c">DependenceResult</a> (bool CanReorder, std::optional&lt; ArrayRef&lt; MachineInstr * &gt;::iterator &gt; PotentialDependence)</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a698f6a30c09fe78e545a83100eccfca5">CanReorder</a></td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Can we actually re-order <span class="doxyComputerOutput">MI</span> with <span class="doxyComputerOutput">Insts</span> (see <span class="doxyComputerOutput">computeDependence</span>). <a href="#a698f6a30c09fe78e545a83100eccfca5">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">std::optional&lt; <a href="/web-llvm/docs/api/classes/llvm/arrayref">ArrayRef</a>&lt; <a href="/web-llvm/docs/api/classes/llvm/machineinstr">MachineInstr</a> * &gt;<a href="/web-llvm/docs/api/classes/llvm/iplist">::iterator</a> &gt;</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a50ad4632ea88746d7b4e164b399ad5bf">PotentialDependence</a></td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>If non-std::nullopt, then an instruction in <span class="doxyComputerOutput">Insts</span> that also must be hoisted. <a href="#a50ad4632ea88746d7b4e164b399ad5bf">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

</table>

## Description {#details}

<p>A data type for representing the result computed by <span class="doxyComputerOutput">computeDependence</span>.</p>


<p>States whether it is okay to reorder the instruction passed to <span class="doxyComputerOutput">computeDependence</span> with at most one dependency.</p>


<p>Definition at line 92 of file <a href="/web-llvm/docs/api/files/lib/lib/codegen/implicitnullchecks-cpp">ImplicitNullChecks.cpp</a>.</p>


<div class="doxySectionDef">

## Public Constructors

### DependenceResult() {#ac4482b60fb9bbbcd12311f77a83d568c}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">anonymous{ImplicitNullChecks.cpp}::ImplicitNullChecks::DependenceResult::DependenceResult (bool CanReorder, std::optional&lt; <a href="/web-llvm/docs/api/classes/llvm/arrayref">ArrayRef</a>&lt; <a href="/web-llvm/docs/api/classes/llvm/machineinstr">MachineInstr</a> * &gt;<a href="/web-llvm/docs/api/classes/llvm/iplist">::iterator</a> &gt; PotentialDependence)</td>
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



<p>Definition at line 101 of file <a href="/web-llvm/docs/api/files/lib/lib/codegen/implicitnullchecks-cpp">ImplicitNullChecks.cpp</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Public Member Attributes

### CanReorder {#a698f6a30c09fe78e545a83100eccfca5}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool anonymous{ImplicitNullChecks.cpp}::ImplicitNullChecks::DependenceResult::CanReorder</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Can we actually re-order <span class="doxyComputerOutput">MI</span> with <span class="doxyComputerOutput">Insts</span> (see <span class="doxyComputerOutput">computeDependence</span>).</p>

<p>Definition at line 95 of file <a href="/web-llvm/docs/api/files/lib/lib/codegen/implicitnullchecks-cpp">ImplicitNullChecks.cpp</a>.</p>

</div>
</div>

### PotentialDependence {#a50ad4632ea88746d7b4e164b399ad5bf}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">std::optional&lt;ArrayRef&lt;MachineInstr *&gt;::iterator&gt; anonymous{ImplicitNullChecks.cpp}::ImplicitNullChecks::DependenceResult::PotentialDependence</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>If non-std::nullopt, then an instruction in <span class="doxyComputerOutput">Insts</span> that also must be hoisted.</p>

<p>Definition at line 99 of file <a href="/web-llvm/docs/api/files/lib/lib/codegen/implicitnullchecks-cpp">ImplicitNullChecks.cpp</a>.</p>

</div>
</div>

</div>

<hr/>

The documentation for this struct was generated from the following file:

<ul>
<li><a href="/web-llvm/docs/api/files/lib/lib/codegen/implicitnullchecks-cpp">ImplicitNullChecks.cpp</a></li>
</ul>

<hr/>

<p class="doxyGeneratedBy">Generated via <a href="https://github.com/xpack/doxygen2docusaurus">doxygen2docusaurus</a> by <a href="https://www.doxygen.nl">Doxygen</a> 1.15.0.</p>

</div>
