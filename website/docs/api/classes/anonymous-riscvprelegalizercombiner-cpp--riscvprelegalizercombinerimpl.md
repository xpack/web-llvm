---

# DO NOT EDIT!
# Automatically generated via doxygen2docusaurus by Doxygen.

slug: /api/classes/anonymous-riscvprelegalizercombiner-cpp-/riscvprelegalizercombinerimpl
custom_edit_url: null
toc_max_heading_level: 4
keywords:
  - doxygen
  - reference
  - class

---

<div class="doxyPage">

# `RISCVPreLegalizerCombinerImpl` Class



## Declaration

<div class="doxyDeclaration">
class anonymous{RISCVPreLegalizerCombiner.cpp}::RISCVPreLegalizerCombinerImpl { ... }
</div>

## Base class

<table class="doxyMembersIndex">

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">class</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/combiner">Combiner</a></td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p><a href="/web-llvm/docs/api/classes/llvm/combiner">Combiner</a> implementation. <a href="/web-llvm/docs/api/classes/llvm/combiner/#details">More...</a></p>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a4c4427370e056d9fcbddfcfd3b1ee1c5">RISCVPreLegalizerCombinerImpl</a> (MachineFunction &amp;MF, CombinerInfo &amp;CInfo, const TargetPassConfig *TPC, GISelKnownBits &amp;KB, GISelCSEInfo *CSEInfo, const RISCVPreLegalizerCombinerImplRuleConfig &amp;RuleConfig, const RISCVSubtarget &amp;STI, MachineDominatorTree *MDT, const LegalizerInfo *LI)</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a16230737bfeb74d39086d138d684d2c2">tryCombineAll</a> (MachineInstr &amp;I) const override</td>
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

## Protected Member Attributes Index

<table class="doxyMembersIndex">

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/combinerhelper">CombinerHelper</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ab0bf30146d5e5e01048d98ee887b8187">Helper</a></td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> RISCVPreLegalizerCombinerImplRuleConfig &amp;</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a601c01a3af88a3257660acb401053ae0">RuleConfig</a></td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/riscvsubtarget">RISCVSubtarget</a> &amp;</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a8ebf217f489780aeabc5d1e38658f723">STI</a></td>
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

## Public Static Functions Index

<table class="doxyMembersIndex">

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">static <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> char *</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ae5aba05707dd394184698ac39cd94726">getName</a> ()</td>
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


<p>Definition at line 41 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/riscv/lib/target/riscv/gisel/riscvprelegalizercombiner-cpp">RISCVPreLegalizerCombiner.cpp</a>.</p>


<div class="doxySectionDef">

## Public Constructors

### RISCVPreLegalizerCombinerImpl() {#a4c4427370e056d9fcbddfcfd3b1ee1c5}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">anonymous{RISCVPreLegalizerCombiner.cpp}::RISCVPreLegalizerCombinerImpl::RISCVPreLegalizerCombinerImpl (<a href="/web-llvm/docs/api/classes/llvm/machinefunction">MachineFunction</a> &amp; MF, <a href="/web-llvm/docs/api/structs/llvm/combinerinfo">CombinerInfo</a> &amp; CInfo, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/targetpassconfig">TargetPassConfig</a> * TPC, <a href="/web-llvm/docs/api/classes/llvm/giselknownbits">GISelKnownBits</a> &amp; KB, <a href="/web-llvm/docs/api/classes/llvm/giselcseinfo">GISelCSEInfo</a> * CSEInfo, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> RISCVPreLegalizerCombinerImplRuleConfig &amp; RuleConfig, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/riscvsubtarget">RISCVSubtarget</a> &amp; STI, <a href="/web-llvm/docs/api/classes/llvm/machinedominatortree">MachineDominatorTree</a> * MDT, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/legalizerinfo">LegalizerInfo</a> * LI)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 48 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/riscv/lib/target/riscv/gisel/riscvprelegalizercombiner-cpp">RISCVPreLegalizerCombiner.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/classes/llvm/combiner/#ac6dfd441ea9e09d3fd537540a6f15d95">llvm::Combiner::CInfo</a>, <a href="/web-llvm/docs/api/classes/llvm/combiner/#a1505ab1c6b333e7cfdfb798e4a9cbca8">llvm::Combiner::CSEInfo</a>, <a href="/web-llvm/docs/api/classes/llvm/combiner/#aaea193b8fae97f73eed6eea3ed454385">llvm::Combiner::KB</a>, <a href="/web-llvm/docs/api/classes/llvm/combiner/#abc56e47138a95b66240fcfd9a5b5dc1f">llvm::Combiner::MF</a>, <a href="#a601c01a3af88a3257660acb401053ae0">RuleConfig</a>, <a href="#a8ebf217f489780aeabc5d1e38658f723">STI</a> and <a href="/web-llvm/docs/api/classes/llvm/combiner/#a8c559817eaf59cbae92ed5aa90af8741">llvm::Combiner::TPC</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Public Member Functions

### tryCombineAll() {#a16230737bfeb74d39086d138d684d2c2}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool anonymous{RISCVPreLegalizerCombiner.cpp}::RISCVPreLegalizerCombinerImpl::tryCombineAll (<a href="/web-llvm/docs/api/classes/llvm/machineinstr">MachineInstr</a> &amp; I)</td>
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



<p>Definition at line 57 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/riscv/lib/target/riscv/gisel/riscvprelegalizercombiner-cpp">RISCVPreLegalizerCombiner.cpp</a>.</p>


<p>Reference <a href="/web-llvm/docs/api/files/lib/lib/support/md5-cpp/#ac0eafdc9ee161b71e7af98af736952fd">I</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Protected Member Attributes

### Helper {#ab0bf30146d5e5e01048d98ee887b8187}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">const CombinerHelper anonymous{RISCVPreLegalizerCombiner.cpp}::RISCVPreLegalizerCombinerImpl::Helper</td>
</tr>
</table>
</td>
<td class="doxyMemberLabelsRight">
<span class="doxyMemberLabels">
<span class="doxyMemberLabel protected">protected</span>
</span>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 43 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/riscv/lib/target/riscv/gisel/riscvprelegalizercombiner-cpp">RISCVPreLegalizerCombiner.cpp</a>.</p>

</div>
</div>

### RuleConfig {#a601c01a3af88a3257660acb401053ae0}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">const RISCVPreLegalizerCombinerImplRuleConfig&amp; anonymous{RISCVPreLegalizerCombiner.cpp}::RISCVPreLegalizerCombinerImpl::RuleConfig</td>
</tr>
</table>
</td>
<td class="doxyMemberLabelsRight">
<span class="doxyMemberLabels">
<span class="doxyMemberLabel protected">protected</span>
</span>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 44 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/riscv/lib/target/riscv/gisel/riscvprelegalizercombiner-cpp">RISCVPreLegalizerCombiner.cpp</a>.</p>


<p>Referenced by <a href="#a4c4427370e056d9fcbddfcfd3b1ee1c5">RISCVPreLegalizerCombinerImpl</a>.</p>

</div>
</div>

### STI {#a8ebf217f489780aeabc5d1e38658f723}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">const RISCVSubtarget&amp; anonymous{RISCVPreLegalizerCombiner.cpp}::RISCVPreLegalizerCombinerImpl::STI</td>
</tr>
</table>
</td>
<td class="doxyMemberLabelsRight">
<span class="doxyMemberLabels">
<span class="doxyMemberLabel protected">protected</span>
</span>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 45 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/riscv/lib/target/riscv/gisel/riscvprelegalizercombiner-cpp">RISCVPreLegalizerCombiner.cpp</a>.</p>


<p>Referenced by <a href="#a4c4427370e056d9fcbddfcfd3b1ee1c5">RISCVPreLegalizerCombinerImpl</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Public Static Functions

### getName() {#ae5aba05707dd394184698ac39cd94726}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">const char * anonymous{RISCVPreLegalizerCombiner.cpp}::RISCVPreLegalizerCombinerImpl::getName ()</td>
</tr>
</table>
</td>
<td class="doxyMemberLabelsRight">
<span class="doxyMemberLabels">
<span class="doxyMemberLabel inline">inline</span>
<span class="doxyMemberLabel static">static</span>
</span>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 55 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/riscv/lib/target/riscv/gisel/riscvprelegalizercombiner-cpp">RISCVPreLegalizerCombiner.cpp</a>.</p>

</div>
</div>

</div>

<hr/>

The documentation for this class was generated from the following file:

<ul>
<li><a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/riscv/lib/target/riscv/gisel/riscvprelegalizercombiner-cpp">RISCVPreLegalizerCombiner.cpp</a></li>
</ul>

<hr/>

<p class="doxyGeneratedBy">Generated via <a href="https://github.com/xpack/doxygen2docusaurus">doxygen2docusaurus</a> by <a href="https://www.doxygen.nl">Doxygen</a> 1.15.0.</p>

</div>
