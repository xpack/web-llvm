---

# DO NOT EDIT!
# Automatically generated via doxygen2docusaurus by Doxygen.

slug: /api/classes/anonymous-aarch64postlegalizerlowering-cpp-/aarch64postlegalizerloweringimpl
custom_edit_url: null
toc_max_heading_level: 4
keywords:
  - doxygen
  - reference
  - class

---

<div class="doxyPage">

# `AArch64PostLegalizerLoweringImpl` Class



## Declaration

<div class="doxyDeclaration">
class anonymous{AArch64PostLegalizerLowering.cpp}::AArch64PostLegalizerLoweringImpl { ... }
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ae075ffce03710b4fe2bbadd12c03a2c2">AArch64PostLegalizerLoweringImpl</a> (MachineFunction &amp;MF, CombinerInfo &amp;CInfo, const TargetPassConfig *TPC, GISelCSEInfo *CSEInfo, const AArch64PostLegalizerLoweringImplRuleConfig &amp;RuleConfig, const AArch64Subtarget &amp;STI)</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a827ec53f8981cee697cfc461d43e26c9">tryCombineAll</a> (MachineInstr &amp;I) const override</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a9310eb42a146f1dc53a0cd50637ccacb">Helper</a></td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> AArch64PostLegalizerLoweringImplRuleConfig &amp;</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a94a3dd53acc6dd17b0b7847459f244bc">RuleConfig</a></td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#aec05843db77292e75bd22230c6ecf570">STI</a></td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a2ce478b9de64cd65add25ce983a8e5d3">getName</a> ()</td>
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


<p>Definition at line 1257 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/lib/target/aarch64/gisel/aarch64postlegalizerlowering-cpp">AArch64PostLegalizerLowering.cpp</a>.</p>


<div class="doxySectionDef">

## Public Constructors

### AArch64PostLegalizerLoweringImpl() {#ae075ffce03710b4fe2bbadd12c03a2c2}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">anonymous{AArch64PostLegalizerLowering.cpp}::AArch64PostLegalizerLoweringImpl::AArch64PostLegalizerLoweringImpl (<a href="/web-llvm/docs/api/classes/llvm/machinefunction">MachineFunction</a> &amp; MF, <a href="/web-llvm/docs/api/structs/llvm/combinerinfo">CombinerInfo</a> &amp; CInfo, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/targetpassconfig">TargetPassConfig</a> * TPC, <a href="/web-llvm/docs/api/classes/llvm/giselcseinfo">GISelCSEInfo</a> * CSEInfo, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> AArch64PostLegalizerLoweringImplRuleConfig &amp; RuleConfig, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/aarch64subtarget">AArch64Subtarget</a> &amp; STI)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 1264 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/lib/target/aarch64/gisel/aarch64postlegalizerlowering-cpp">AArch64PostLegalizerLowering.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/classes/llvm/combiner/#ac6dfd441ea9e09d3fd537540a6f15d95">llvm::Combiner::CInfo</a>, <a href="/web-llvm/docs/api/classes/llvm/combiner/#a1505ab1c6b333e7cfdfb798e4a9cbca8">llvm::Combiner::CSEInfo</a>, <a href="/web-llvm/docs/api/classes/llvm/combiner/#abc56e47138a95b66240fcfd9a5b5dc1f">llvm::Combiner::MF</a>, <a href="#a94a3dd53acc6dd17b0b7847459f244bc">RuleConfig</a>, <a href="#aec05843db77292e75bd22230c6ecf570">STI</a> and <a href="/web-llvm/docs/api/classes/llvm/combiner/#a8c559817eaf59cbae92ed5aa90af8741">llvm::Combiner::TPC</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Public Member Functions

### tryCombineAll() {#a827ec53f8981cee697cfc461d43e26c9}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool anonymous{AArch64PostLegalizerLowering.cpp}::AArch64PostLegalizerLoweringImpl::tryCombineAll (<a href="/web-llvm/docs/api/classes/llvm/machineinstr">MachineInstr</a> &amp; I)</td>
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



<p>Definition at line 1272 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/lib/target/aarch64/gisel/aarch64postlegalizerlowering-cpp">AArch64PostLegalizerLowering.cpp</a>.</p>


<p>Reference <a href="/web-llvm/docs/api/files/lib/lib/support/md5-cpp/#ac0eafdc9ee161b71e7af98af736952fd">I</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Protected Member Attributes

### Helper {#a9310eb42a146f1dc53a0cd50637ccacb}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">const CombinerHelper anonymous{AArch64PostLegalizerLowering.cpp}::AArch64PostLegalizerLoweringImpl::Helper</td>
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



<p>Definition at line 1259 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/lib/target/aarch64/gisel/aarch64postlegalizerlowering-cpp">AArch64PostLegalizerLowering.cpp</a>.</p>

</div>
</div>

### RuleConfig {#a94a3dd53acc6dd17b0b7847459f244bc}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">const AArch64PostLegalizerLoweringImplRuleConfig&amp; anonymous{AArch64PostLegalizerLowering.cpp}::AArch64PostLegalizerLoweringImpl::RuleConfig</td>
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



<p>Definition at line 1260 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/lib/target/aarch64/gisel/aarch64postlegalizerlowering-cpp">AArch64PostLegalizerLowering.cpp</a>.</p>


<p>Referenced by <a href="#ae075ffce03710b4fe2bbadd12c03a2c2">AArch64PostLegalizerLoweringImpl</a>.</p>

</div>
</div>

### STI {#aec05843db77292e75bd22230c6ecf570}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">const AArch64Subtarget&amp; anonymous{AArch64PostLegalizerLowering.cpp}::AArch64PostLegalizerLoweringImpl::STI</td>
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



<p>Definition at line 1261 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/lib/target/aarch64/gisel/aarch64postlegalizerlowering-cpp">AArch64PostLegalizerLowering.cpp</a>.</p>


<p>Referenced by <a href="#ae075ffce03710b4fe2bbadd12c03a2c2">AArch64PostLegalizerLoweringImpl</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Public Static Functions

### getName() {#a2ce478b9de64cd65add25ce983a8e5d3}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">const char * anonymous{AArch64PostLegalizerLowering.cpp}::AArch64PostLegalizerLoweringImpl::getName ()</td>
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



<p>Definition at line 1270 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/lib/target/aarch64/gisel/aarch64postlegalizerlowering-cpp">AArch64PostLegalizerLowering.cpp</a>.</p>

</div>
</div>

</div>

<hr/>

The documentation for this class was generated from the following file:

<ul>
<li><a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/lib/target/aarch64/gisel/aarch64postlegalizerlowering-cpp">AArch64PostLegalizerLowering.cpp</a></li>
</ul>

<hr/>

<p class="doxyGeneratedBy">Generated via <a href="https://github.com/xpack/doxygen2docusaurus">doxygen2docusaurus</a> by <a href="https://www.doxygen.nl">Doxygen</a> 1.15.0.</p>

</div>
