---

# DO NOT EDIT!
# Automatically generated via doxygen2docusaurus by Doxygen.

slug: /api/classes/anonymous-aarch64o0prelegalizercombiner-cpp-/aarch64o0prelegalizercombinerimpl
custom_edit_url: null
toc_max_heading_level: 4
keywords:
  - doxygen
  - reference
  - class

---

<div class="doxyPage">

# `AArch64O0PreLegalizerCombinerImpl` Class



## Declaration

<div class="doxyDeclaration">
class anonymous{AArch64O0PreLegalizerCombiner.cpp}::AArch64O0PreLegalizerCombinerImpl { ... }
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a7449c29ff83bc3145eac13a0e4fbe82a">AArch64O0PreLegalizerCombinerImpl</a> (MachineFunction &amp;MF, CombinerInfo &amp;CInfo, const TargetPassConfig *TPC, GISelKnownBits &amp;KB, GISelCSEInfo *CSEInfo, const AArch64O0PreLegalizerCombinerImplRuleConfig &amp;RuleConfig, const AArch64Subtarget &amp;STI)</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a564390b8abd3d9dcca6fe340ee72e706">tryCombineAll</a> (MachineInstr &amp;I) const override</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a1ebf6e41f44a7b48db9a0df522ea9e43">tryCombineAllImpl</a> (MachineInstr &amp;I) const</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#adc6aef7dedda5d7886111ea88c123cfd">Helper</a></td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> AArch64O0PreLegalizerCombinerImplRuleConfig &amp;</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ae656122360aadf0a3330b49c8f397035">RuleConfig</a></td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/aarch64subtarget">AArch64Subtarget</a> &amp;</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a87acf3ea6adb1e5b4b04b5455b3cb369">STI</a></td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a592762d0b01670d080566cc0c5d76e9c">getName</a> ()</td>
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


<p>Definition at line 42 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/lib/target/aarch64/gisel/aarch64o0prelegalizercombiner-cpp">AArch64O0PreLegalizerCombiner.cpp</a>.</p>


<div class="doxySectionDef">

## Public Constructors

### AArch64O0PreLegalizerCombinerImpl() {#a7449c29ff83bc3145eac13a0e4fbe82a}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">anonymous{AArch64O0PreLegalizerCombiner.cpp}::AArch64O0PreLegalizerCombinerImpl::AArch64O0PreLegalizerCombinerImpl (<a href="/web-llvm/docs/api/classes/llvm/machinefunction">MachineFunction</a> &amp; MF, <a href="/web-llvm/docs/api/structs/llvm/combinerinfo">CombinerInfo</a> &amp; CInfo, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/targetpassconfig">TargetPassConfig</a> * TPC, <a href="/web-llvm/docs/api/classes/llvm/giselknownbits">GISelKnownBits</a> &amp; KB, <a href="/web-llvm/docs/api/classes/llvm/giselcseinfo">GISelCSEInfo</a> * CSEInfo, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> AArch64O0PreLegalizerCombinerImplRuleConfig &amp; RuleConfig, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/aarch64subtarget">AArch64Subtarget</a> &amp; STI)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 49 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/lib/target/aarch64/gisel/aarch64o0prelegalizercombiner-cpp">AArch64O0PreLegalizerCombiner.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/classes/llvm/combiner/#ac6dfd441ea9e09d3fd537540a6f15d95">llvm::Combiner::CInfo</a>, <a href="/web-llvm/docs/api/classes/llvm/combiner/#a1505ab1c6b333e7cfdfb798e4a9cbca8">llvm::Combiner::CSEInfo</a>, <a href="/web-llvm/docs/api/classes/llvm/combiner/#aaea193b8fae97f73eed6eea3ed454385">llvm::Combiner::KB</a>, <a href="/web-llvm/docs/api/classes/llvm/combiner/#abc56e47138a95b66240fcfd9a5b5dc1f">llvm::Combiner::MF</a>, <a href="#ae656122360aadf0a3330b49c8f397035">RuleConfig</a>, <a href="#a87acf3ea6adb1e5b4b04b5455b3cb369">STI</a> and <a href="/web-llvm/docs/api/classes/llvm/combiner/#a8c559817eaf59cbae92ed5aa90af8741">llvm::Combiner::TPC</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Public Member Functions

### tryCombineAll() {#a564390b8abd3d9dcca6fe340ee72e706}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool anonymous{AArch64O0PreLegalizerCombiner.cpp}::AArch64O0PreLegalizerCombinerImpl::tryCombineAll (<a href="/web-llvm/docs/api/classes/llvm/machineinstr">MachineInstr</a> &amp; I)</td>
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



<p>Definition at line 57 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/lib/target/aarch64/gisel/aarch64o0prelegalizercombiner-cpp">AArch64O0PreLegalizerCombiner.cpp</a>.</p>


<p>Reference <a href="/web-llvm/docs/api/files/lib/lib/support/md5-cpp/#ac0eafdc9ee161b71e7af98af736952fd">I</a>.</p>

</div>
</div>

### tryCombineAllImpl() {#a1ebf6e41f44a7b48db9a0df522ea9e43}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool anonymous{AArch64O0PreLegalizerCombiner.cpp}::AArch64O0PreLegalizerCombinerImpl::tryCombineAllImpl (<a href="/web-llvm/docs/api/classes/llvm/machineinstr">MachineInstr</a> &amp; I)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 59 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/lib/target/aarch64/gisel/aarch64o0prelegalizercombiner-cpp">AArch64O0PreLegalizerCombiner.cpp</a>.</p>


<p>Reference <a href="/web-llvm/docs/api/files/lib/lib/support/md5-cpp/#ac0eafdc9ee161b71e7af98af736952fd">I</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Protected Member Attributes

### Helper {#adc6aef7dedda5d7886111ea88c123cfd}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">const CombinerHelper anonymous{AArch64O0PreLegalizerCombiner.cpp}::AArch64O0PreLegalizerCombinerImpl::Helper</td>
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



<p>Definition at line 44 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/lib/target/aarch64/gisel/aarch64o0prelegalizercombiner-cpp">AArch64O0PreLegalizerCombiner.cpp</a>.</p>

</div>
</div>

### RuleConfig {#ae656122360aadf0a3330b49c8f397035}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">const AArch64O0PreLegalizerCombinerImplRuleConfig&amp; anonymous{AArch64O0PreLegalizerCombiner.cpp}::AArch64O0PreLegalizerCombinerImpl::RuleConfig</td>
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



<p>Definition at line 45 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/lib/target/aarch64/gisel/aarch64o0prelegalizercombiner-cpp">AArch64O0PreLegalizerCombiner.cpp</a>.</p>


<p>Referenced by <a href="#a7449c29ff83bc3145eac13a0e4fbe82a">AArch64O0PreLegalizerCombinerImpl</a>.</p>

</div>
</div>

### STI {#a87acf3ea6adb1e5b4b04b5455b3cb369}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">const AArch64Subtarget&amp; anonymous{AArch64O0PreLegalizerCombiner.cpp}::AArch64O0PreLegalizerCombinerImpl::STI</td>
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



<p>Definition at line 46 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/lib/target/aarch64/gisel/aarch64o0prelegalizercombiner-cpp">AArch64O0PreLegalizerCombiner.cpp</a>.</p>


<p>Referenced by <a href="#a7449c29ff83bc3145eac13a0e4fbe82a">AArch64O0PreLegalizerCombinerImpl</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Public Static Functions

### getName() {#a592762d0b01670d080566cc0c5d76e9c}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">const char * anonymous{AArch64O0PreLegalizerCombiner.cpp}::AArch64O0PreLegalizerCombinerImpl::getName ()</td>
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



<p>Definition at line 55 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/lib/target/aarch64/gisel/aarch64o0prelegalizercombiner-cpp">AArch64O0PreLegalizerCombiner.cpp</a>.</p>

</div>
</div>

</div>

<hr/>

The documentation for this class was generated from the following file:

<ul>
<li><a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/lib/target/aarch64/gisel/aarch64o0prelegalizercombiner-cpp">AArch64O0PreLegalizerCombiner.cpp</a></li>
</ul>

<hr/>

<p class="doxyGeneratedBy">Generated via <a href="https://github.com/xpack/doxygen2docusaurus">doxygen2docusaurus</a> by <a href="https://www.doxygen.nl">Doxygen</a> 1.15.0.</p>

</div>
