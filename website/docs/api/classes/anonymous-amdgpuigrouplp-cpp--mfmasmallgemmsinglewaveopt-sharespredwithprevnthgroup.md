---

# DO NOT EDIT!
# Automatically generated via doxygen2docusaurus by Doxygen.

slug: /api/classes/anonymous-amdgpuigrouplp-cpp-/mfmasmallgemmsinglewaveopt/sharespredwithprevnthgroup
custom_edit_url: null
toc_max_heading_level: 4
keywords:
  - doxygen
  - reference
  - class

---

<div class="doxyPage">

# `SharesPredWithPrevNthGroup` Class

<p>Whether the SU shares a V_PERM predecessor with any SU in the <a href="/web-llvm/docs/api/classes/anonymous-amdgpuigrouplp-cpp-/schedgroup">SchedGroup</a> that is <span class="doxyComputerOutput">Distance</span> steps away. <a href="#details">More...</a></p>

## Declaration

<div class="doxyDeclaration">
class anonymous{AMDGPUIGroupLP.cpp}::MFMASmallGemmSingleWaveOpt::SharesPredWithPrevNthGroup { ... }
</div>

## Base class

<table class="doxyMembersIndex">

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">class</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="/web-llvm/docs/api/classes/anonymous-amdgpuigrouplp-cpp-/instructionrule">InstructionRule</a></td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ad7d8870c69356999a54ff9dcc907a4c3">SharesPredWithPrevNthGroup</a> (unsigned Distance, const SIInstrInfo *TII, unsigned SGID, bool NeedsCache=false)</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a72dba7906771e3ef6d24dba45bee300d">apply</a> (const SUnit *SU, const ArrayRef&lt; SUnit * &gt; Collection, SmallVectorImpl&lt; SchedGroup &gt; &amp;SyncPipe) override</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">unsigned</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a02436fd92f67009ff0cfc07de9eace6d">Distance</a> = 1</td>
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

<p>Whether the SU shares a V_PERM predecessor with any SU in the <a href="/web-llvm/docs/api/classes/anonymous-amdgpuigrouplp-cpp-/schedgroup">SchedGroup</a> that is <span class="doxyComputerOutput">Distance</span> steps away.</p>

<p>Definition at line 2013 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/amdgpuigrouplp-cpp">AMDGPUIGroupLP.cpp</a>.</p>


<div class="doxySectionDef">

## Public Constructors

### SharesPredWithPrevNthGroup() {#ad7d8870c69356999a54ff9dcc907a4c3}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">anonymous{AMDGPUIGroupLP.cpp}::MFMASmallGemmSingleWaveOpt::SharesPredWithPrevNthGroup::SharesPredWithPrevNthGroup (unsigned Distance, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/siinstrinfo">SIInstrInfo</a> * TII, unsigned SGID, bool NeedsCache=false)</td>
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



<p>Definition at line 2057 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/amdgpuigrouplp-cpp">AMDGPUIGroupLP.cpp</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Public Member Functions

### apply() {#a72dba7906771e3ef6d24dba45bee300d}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool anonymous{AMDGPUIGroupLP.cpp}::MFMASmallGemmSingleWaveOpt::SharesPredWithPrevNthGroup::apply (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/sunit">SUnit</a> * SU, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/arrayref">ArrayRef</a>&lt; <a href="/web-llvm/docs/api/classes/llvm/sunit">SUnit</a> * &gt; Collection, <a href="/web-llvm/docs/api/classes/llvm/smallvectorimpl">SmallVectorImpl</a>&lt; <a href="/web-llvm/docs/api/classes/anonymous-amdgpuigrouplp-cpp-/schedgroup">SchedGroup</a> &gt; &amp; SyncPipe)</td>
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



<p>Definition at line 2018 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/amdgpuigrouplp-cpp">AMDGPUIGroupLP.cpp</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Private Member Attributes

### Distance {#a02436fd92f67009ff0cfc07de9eace6d}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">unsigned anonymous{AMDGPUIGroupLP.cpp}::MFMASmallGemmSingleWaveOpt::SharesPredWithPrevNthGroup::Distance = 1</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 2015 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/amdgpuigrouplp-cpp">AMDGPUIGroupLP.cpp</a>.</p>

</div>
</div>

</div>

<hr/>

The documentation for this class was generated from the following file:

<ul>
<li><a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/amdgpuigrouplp-cpp">AMDGPUIGroupLP.cpp</a></li>
</ul>

<hr/>

<p class="doxyGeneratedBy">Generated via <a href="https://github.com/xpack/doxygen2docusaurus">doxygen2docusaurus</a> by <a href="https://www.doxygen.nl">Doxygen</a> 1.15.0.</p>

</div>
