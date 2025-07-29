---

# DO NOT EDIT!
# Automatically generated via doxygen2docusaurus by Doxygen.

slug: /api/classes/llvm/liveintervalcalc
custom_edit_url: null
toc_max_heading_level: 4
keywords:
  - doxygen
  - reference
  - class

---

<div class="doxyPage">

# `LiveIntervalCalc` Class



## Declaration

<div class="doxyDeclaration">
class llvm::LiveIntervalCalc { ... }
</div>

## Included Headers

<div class="doxyIncludesList">#include "<a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/codegen/liveintervalcalc-h">llvm/CodeGen/LiveIntervalCalc.h</a>"
</div>

## Base class

<table class="doxyMembersIndex">

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">class</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/liverangecalc">LiveRangeCalc</a></td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a93435c79c80dceea8b29e6b47993a577">LiveIntervalCalc</a> ()=default</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a1c36b75f4a0dac1a833a459617f03c76">createDeadDefs</a> (LiveRange &amp;LR, Register Reg)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>createDeadDefs - Create a dead def in LI for every def operand of Reg. <a href="#a1c36b75f4a0dac1a833a459617f03c76">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">void</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ae3bff863d5f2c5df37ef42d76e457f74">extendToUses</a> (LiveRange &amp;LR, MCRegister PhysReg)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Extend the live range of <span class="doxyComputerOutput">LR</span> to reach all uses of Reg. <a href="#ae3bff863d5f2c5df37ef42d76e457f74">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">void</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ad67d6b7f9f91a2d5852b0f9aebfe542a">calculate</a> (LiveInterval &amp;LI, bool TrackSubRegs)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Calculates liveness for the register specified in live interval <span class="doxyComputerOutput">LI</span>. <a href="#ad67d6b7f9f91a2d5852b0f9aebfe542a">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">void</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#af5198110c0058e3d60524eecf500ee51">constructMainRangeFromSubranges</a> (LiveInterval &amp;LI)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>For live interval <span class="doxyComputerOutput">LI</span> with correct SubRanges construct matching information for the main live range. <a href="#af5198110c0058e3d60524eecf500ee51">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

</table>

## Private Member Functions Index

<table class="doxyMembersIndex">

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">void</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#abf0d796c3c3e4edc136150896749a589">extendToUses</a> (LiveRange &amp;LR, Register Reg, LaneBitmask LaneMask, LiveInterval *LI=nullptr)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Extend the live range of <span class="doxyComputerOutput">LR</span> to reach all uses of Reg. <a href="#abf0d796c3c3e4edc136150896749a589">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

</table>


<p>Definition at line 28 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/codegen/liveintervalcalc-h">LiveIntervalCalc.h</a>.</p>


<div class="doxySectionDef">

## Public Constructors

### LiveIntervalCalc() {#a93435c79c80dceea8b29e6b47993a577}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">llvm::LiveIntervalCalc::LiveIntervalCalc ()</td>
</tr>
</table>
</td>
<td class="doxyMemberLabelsRight">
<span class="doxyMemberLabels">
<span class="doxyMemberLabel default">default</span>
</span>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 43 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/codegen/liveintervalcalc-h">LiveIntervalCalc.h</a>.</p>


<p>Reference <a href="/web-llvm/docs/api/files/lib/lib/codegen/machinesink-cpp/#a359e1ff26f6d466d927a61aae45b05c3">Reg</a>.</p>


<p>Referenced by <a href="#ad67d6b7f9f91a2d5852b0f9aebfe542a">calculate</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Public Member Functions

### calculate() {#ad67d6b7f9f91a2d5852b0f9aebfe542a}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void LiveIntervalCalc::calculate (<a href="/web-llvm/docs/api/classes/llvm/liveinterval">LiveInterval</a> &amp; LI, bool TrackSubRegs)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Calculates liveness for the register specified in live interval <span class="doxyComputerOutput">LI</span>.</p>


<p>Creates subregister live ranges as needed if subreg liveness tracking is enabled.</p>


<p>Declaration at line 61 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/codegen/liveintervalcalc-h">LiveIntervalCalc.h</a>, definition at line 41 of file <a href="/web-llvm/docs/api/files/lib/lib/codegen/liveintervalcalc-cpp">LiveIntervalCalc.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/silowercontrolflow-cpp/#a4868c5d81c5ccc98c47aeab6244346a0">assert</a>, <a href="/web-llvm/docs/api/classes/llvm/liverange/#aa1555194b9f176612b04fbd38f49b40d">llvm::LiveRange::clear</a>, <a href="#af5198110c0058e3d60524eecf500ee51">constructMainRangeFromSubranges</a>, <a href="/web-llvm/docs/api/files/lib/lib/codegen/liveintervalcalc-cpp/#a70e2de8376b84c468e8a5762fda4c419">createDeadDef</a>, <a href="/web-llvm/docs/api/classes/llvm/liveinterval/#a8104005914e3dfed73608d0d8961b822">llvm::LiveInterval::createSubRangeFrom</a>, <a href="/web-llvm/docs/api/classes/llvm/liverange/#a66ff664a97cd3c30de7e873335a0c075">llvm::LiveRange::empty</a>, <a href="/web-llvm/docs/api/structs/llvm/lanebitmask/#a3714a639930eab71d7202da05ad82990">llvm::LaneBitmask::getAll</a>, <a href="/web-llvm/docs/api/classes/llvm/liverangecalc/#a3c8fd02f213ccc28812243ec1f36957c">llvm::LiveRangeCalc::getDomTree</a>, <a href="/web-llvm/docs/api/classes/llvm/liverangecalc/#a11a21f58b3a7b8b7c401958cd3f7304f">llvm::LiveRangeCalc::getIndexes</a>, <a href="/web-llvm/docs/api/classes/llvm/liverangecalc/#ab032314f07277bf920fd315187ab9605">llvm::LiveRangeCalc::getMachineFunction</a>, <a href="/web-llvm/docs/api/classes/llvm/liverangecalc/#ad09d2d2f0c1d47c7bc6eb04e33b5e51d">llvm::LiveRangeCalc::getRegInfo</a>, <a href="/web-llvm/docs/api/classes/llvm/liverangecalc/#a60d4123651abf23e886661980d951ffc">llvm::LiveRangeCalc::getVNAlloc</a>, <a href="/web-llvm/docs/api/classes/llvm/liveinterval/#a1c198291d6ee66150b76633cda8a1749">llvm::LiveInterval::hasSubRanges</a>, <a href="#a93435c79c80dceea8b29e6b47993a577">LiveIntervalCalc</a>, <a href="/web-llvm/docs/api/classes/llvm/liveinterval/#a967540f5e5799b56c6fbcee378d110eb">llvm::LiveInterval::refineSubRanges</a>, <a href="/web-llvm/docs/api/classes/llvm/liveinterval/#a14d46e70db7e417c8ed5bc66fb295185">llvm::LiveInterval::reg</a>, <a href="/web-llvm/docs/api/classes/llvm/liveinterval/#a0aac3ef1eadaa206a70b767730ef3c5b">llvm::LiveInterval::removeEmptySubRanges</a>, <a href="/web-llvm/docs/api/classes/llvm/liverangecalc/#a65f0beed94a7dbdf8c8d7e2b46a0afa0">llvm::LiveRangeCalc::reset</a>, <a href="/web-llvm/docs/api/classes/llvm/liverangecalc/#a56cefbb66ed770ce1e6df7cbd1fa90d1">llvm::LiveRangeCalc::resetLiveOutMap</a>, <a href="/web-llvm/docs/api/classes/llvm/liveinterval/#a9545a896d571165e9f43cf4b29a6d072">llvm::LiveInterval::subranges</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64advsimdscalarpass-cpp/#a92a6b0a9b7228d190b0a7d8ae3ef03c7">SubReg</a> and <a href="/web-llvm/docs/api/files/lib/lib/codegen/machinesink-cpp/#a0f36ed1bc17fc1aa97fe291c439a0698">TRI</a>.</p>

</div>
</div>

### constructMainRangeFromSubranges() {#af5198110c0058e3d60524eecf500ee51}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void LiveIntervalCalc::constructMainRangeFromSubranges (<a href="/web-llvm/docs/api/classes/llvm/liveinterval">LiveInterval</a> &amp; LI)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>For live interval <span class="doxyComputerOutput">LI</span> with correct SubRanges construct matching information for the main live range.</p>


<p>Expects the main live range to not have any segments or value numbers.</p>


<p>Declaration at line 66 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/codegen/liveintervalcalc-h">LiveIntervalCalc.h</a>, definition at line 105 of file <a href="/web-llvm/docs/api/files/lib/lib/codegen/liveintervalcalc-cpp">LiveIntervalCalc.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/silowercontrolflow-cpp/#a4868c5d81c5ccc98c47aeab6244346a0">assert</a>, <a href="/web-llvm/docs/api/classes/llvm/liverange/#a4258d794235c7a408b3f52e5e4ef7159">llvm::LiveRange::createDeadDef</a>, <a href="/web-llvm/docs/api/classes/llvm/vninfo/#ae623a0f1ab59da851f2ebf1674d1fddb">llvm::VNInfo::def</a>, <a href="/web-llvm/docs/api/classes/llvm/smallvectortemplatecommon/#ad9a3c7bc26b130377bbafc170b5f88a2">llvm::SmallVectorTemplateCommon&lt; T, typename &gt;::empty</a>, <a href="/web-llvm/docs/api/structs/llvm/lanebitmask/#a3714a639930eab71d7202da05ad82990">llvm::LaneBitmask::getAll</a>, <a href="/web-llvm/docs/api/classes/llvm/liverangecalc/#a60d4123651abf23e886661980d951ffc">llvm::LiveRangeCalc::getVNAlloc</a>, <a href="/web-llvm/docs/api/classes/llvm/vninfo/#ae72fbcf51be7574c84817cde814df07e">llvm::VNInfo::isPHIDef</a>, <a href="/web-llvm/docs/api/classes/llvm/vninfo/#ab72366fd538f240cbb53dac39368cdfc">llvm::VNInfo::isUnused</a>, <a href="/web-llvm/docs/api/classes/llvm/liveinterval/#a14d46e70db7e417c8ed5bc66fb295185">llvm::LiveInterval::reg</a>, <a href="/web-llvm/docs/api/classes/llvm/liverangecalc/#a56cefbb66ed770ce1e6df7cbd1fa90d1">llvm::LiveRangeCalc::resetLiveOutMap</a>, <a href="/web-llvm/docs/api/classes/llvm/liverange/#a9c628b400be67b6adb4fa07e84a96a82">llvm::LiveRange::segments</a>, <a href="/web-llvm/docs/api/classes/llvm/liveinterval/#a9545a896d571165e9f43cf4b29a6d072">llvm::LiveInterval::subranges</a> and <a href="/web-llvm/docs/api/classes/llvm/liverange/#a9eb4aa155c41e60dff42f4e741a0dcf0">llvm::LiveRange::valnos</a>.</p>


<p>Referenced by <a href="#ad67d6b7f9f91a2d5852b0f9aebfe542a">calculate</a>.</p>

</div>
</div>

### createDeadDefs() {#a1c36b75f4a0dac1a833a459617f03c76}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void LiveIntervalCalc::createDeadDefs (<a href="/web-llvm/docs/api/classes/llvm/liverange">LiveRange</a> &amp; LR, <a href="/web-llvm/docs/api/classes/llvm/register">Register</a> Reg)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>createDeadDefs - Create a dead def in LI for every def operand of Reg.</p>


<p>Each instruction defining Reg gets a new <a href="/web-llvm/docs/api/classes/llvm/vninfo">VNInfo</a> with a corresponding minimal live range.</p>


<p>Declaration at line 48 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/codegen/liveintervalcalc-h">LiveIntervalCalc.h</a>, definition at line 122 of file <a href="/web-llvm/docs/api/files/lib/lib/codegen/liveintervalcalc-cpp">LiveIntervalCalc.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/silowercontrolflow-cpp/#a4868c5d81c5ccc98c47aeab6244346a0">assert</a>, <a href="/web-llvm/docs/api/files/lib/lib/codegen/liveintervalcalc-cpp/#a70e2de8376b84c468e8a5762fda4c419">createDeadDef</a>, <a href="/web-llvm/docs/api/classes/llvm/liverangecalc/#a11a21f58b3a7b8b7c401958cd3f7304f">llvm::LiveRangeCalc::getIndexes</a>, <a href="/web-llvm/docs/api/classes/llvm/liverangecalc/#ad09d2d2f0c1d47c7bc6eb04e33b5e51d">llvm::LiveRangeCalc::getRegInfo</a> and <a href="/web-llvm/docs/api/classes/llvm/liverangecalc/#a60d4123651abf23e886661980d951ffc">llvm::LiveRangeCalc::getVNAlloc</a>.</p>

</div>
</div>

### extendToUses() {#ae3bff863d5f2c5df37ef42d76e457f74}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void llvm::LiveIntervalCalc::extendToUses (<a href="/web-llvm/docs/api/classes/llvm/liverange">LiveRange</a> &amp; LR, <a href="/web-llvm/docs/api/classes/llvm/mcregister">MCRegister</a> PhysReg)</td>
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

<p>Extend the live range of <span class="doxyComputerOutput">LR</span> to reach all uses of Reg.</p>


<p>All uses must be jointly dominated by existing liveness. PHI-defs are inserted as needed to preserve SSA form.</p>


<p>Definition at line 54 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/codegen/liveintervalcalc-h">LiveIntervalCalc.h</a>.</p>


<p>Reference <a href="/web-llvm/docs/api/structs/llvm/lanebitmask/#a3714a639930eab71d7202da05ad82990">llvm::LaneBitmask::getAll</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Private Member Functions

### extendToUses() {#abf0d796c3c3e4edc136150896749a589}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void LiveIntervalCalc::extendToUses (<a href="/web-llvm/docs/api/classes/llvm/liverange">LiveRange</a> &amp; LR, <a href="/web-llvm/docs/api/classes/llvm/register">Register</a> Reg, <a href="/web-llvm/docs/api/structs/llvm/lanebitmask">LaneBitmask</a> LaneMask, <a href="/web-llvm/docs/api/classes/llvm/liveinterval">LiveInterval</a> * LI=nullptr)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Extend the live range of <span class="doxyComputerOutput">LR</span> to reach all uses of Reg.</p>


<p>If <span class="doxyComputerOutput">LR</span> is a main range, or if <span class="doxyComputerOutput">LI</span> is null, then all uses must be jointly dominated by the definitions from <span class="doxyComputerOutput">LR</span>. If <span class="doxyComputerOutput">LR</span> is a subrange of the live interval <span class="doxyComputerOutput">LI</span>, corresponding to lane mask <span class="doxyComputerOutput">LaneMask</span>, all uses must be jointly dominated by the definitions from <span class="doxyComputerOutput">LR</span> together with definitions of other lanes where <span class="doxyComputerOutput">LR</span> becomes undefined (via &lt;def,read-undef&gt; operands). If <span class="doxyComputerOutput">LR</span> is a main range, the <span class="doxyComputerOutput">LaneMask</span> should be set to ~0, i.e. <a href="/web-llvm/docs/api/structs/llvm/lanebitmask/#a3714a639930eab71d7202da05ad82990">LaneBitmask::getAll()</a>.</p>


<p>Declaration at line 39 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/codegen/liveintervalcalc-h">LiveIntervalCalc.h</a>, definition at line 134 of file <a href="/web-llvm/docs/api/files/lib/lib/codegen/liveintervalcalc-cpp">LiveIntervalCalc.cpp</a>.</p>

</div>
</div>

</div>

<hr/>

The documentation for this class was generated from the following files:

<ul>
<li><a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/codegen/liveintervalcalc-h">LiveIntervalCalc.h</a></li>
<li><a href="/web-llvm/docs/api/files/lib/lib/codegen/liveintervalcalc-cpp">LiveIntervalCalc.cpp</a></li>
</ul>

<hr/>

<p class="doxyGeneratedBy">Generated via <a href="https://github.com/xpack/doxygen2docusaurus">doxygen2docusaurus</a> by <a href="https://www.doxygen.nl">Doxygen</a> 1.15.0.</p>

</div>
