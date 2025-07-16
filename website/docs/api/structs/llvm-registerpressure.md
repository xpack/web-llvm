---

# DO NOT EDIT!
# Automatically generated via doxygen2docusaurus by Doxygen.

slug: /api/structs/llvm/registerpressure
custom_edit_url: null
toc_max_heading_level: 4
keywords:
  - doxygen
  - reference
  - struct

---

<div class="doxyPage">

# The `RegisterPressure` Struct Reference

<p>Base class for register pressure results. <a href="#details">More...</a></p>

## Declaration

<div class="doxyDeclaration">
struct llvm::RegisterPressure { ... }
</div>

## Included Headers

<div class="doxyIncludesList">#include "<a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/codegen/registerpressure-h">llvm/CodeGen/RegisterPressure.h</a>"
</div>

## Derived Structs

<table class="doxyMembersIndex">

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">struct</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="/web-llvm/docs/api/structs/llvm/intervalpressure">IntervalPressure</a></td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p><a href="/web-llvm/docs/api/structs/llvm/registerpressure">RegisterPressure</a> computed within a region of instructions delimited by TopIdx and BottomIdx. <a href="/web-llvm/docs/api/structs/llvm/intervalpressure/#details">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">struct</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="/web-llvm/docs/api/structs/llvm/regionpressure">RegionPressure</a></td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p><a href="/web-llvm/docs/api/structs/llvm/registerpressure">RegisterPressure</a> computed within a region of instructions delimited by TopPos and BottomPos. <a href="/web-llvm/docs/api/structs/llvm/regionpressure/#details">More...</a></p>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#aed5b5c7fd078ad82cea332031dd5099d">dump</a> (const TargetRegisterInfo *TRI) const</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">std::vector&lt; unsigned &gt;</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#af444f3c79d12bb654d6477d629cbe7c0">MaxSetPressure</a></td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Map of max reg pressure indexed by pressure set <a href="/web-llvm/docs/api/namespaces/llvm/callingconv/#abdf8cf606905c10634e831390981b0ed">ID</a>, not class <a href="/web-llvm/docs/api/namespaces/llvm/callingconv/#abdf8cf606905c10634e831390981b0ed">ID</a>. <a href="#af444f3c79d12bb654d6477d629cbe7c0">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/smallvector">SmallVector</a>&lt; <a href="/web-llvm/docs/api/structs/llvm/vregmaskorunit">VRegMaskOrUnit</a>, 8 &gt;</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#aaf4867227a975bcae4b285003d7a8554">LiveInRegs</a></td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>List of live in virtual registers or physical register units. <a href="#aaf4867227a975bcae4b285003d7a8554">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/smallvector">SmallVector</a>&lt; <a href="/web-llvm/docs/api/structs/llvm/vregmaskorunit">VRegMaskOrUnit</a>, 8 &gt;</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a8e0d374fff11a3139a343cb42338b989">LiveOutRegs</a></td>
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

<p>Base class for register pressure results.</p>

<p>Definition at line 47 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/codegen/registerpressure-h">RegisterPressure.h</a>.</p>


<div class="doxySectionDef">

## Public Member Functions

### dump() {#aed5b5c7fd078ad82cea332031dd5099d}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">LLVM_DUMP_METHOD void RegisterPressure::dump (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/targetregisterinfo">TargetRegisterInfo</a> * TRI)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Declaration at line 55 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/codegen/registerpressure-h">RegisterPressure.h</a>, definition at line 94 of file <a href="/web-llvm/docs/api/files/lib/lib/codegen/registerpressure-cpp">RegisterPressure.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/namespaces/llvm/#a7c46c742c31be54870e2038048e6b391">llvm::dbgs</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#adb6fca77863850136760be488d6ea345">llvm::dumpRegSetPressure</a>, <a href="#aaf4867227a975bcae4b285003d7a8554">LiveInRegs</a>, <a href="#a8e0d374fff11a3139a343cb42338b989">LiveOutRegs</a>, <a href="#af444f3c79d12bb654d6477d629cbe7c0">MaxSetPressure</a>, <a href="/web-llvm/docs/api/files/lib/lib/option/option-cpp/#a04665169063c8ca1f2ea96c27fc7c2b2">P</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a3e30e18d6f7ebd943eaf8ebc3a2b2930">llvm::PrintLaneMask</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a788c5905de970028eb0efa2266bd10bf">llvm::printVRegOrUnit</a> and <a href="/web-llvm/docs/api/files/lib/lib/codegen/machinesink-cpp/#a0f36ed1bc17fc1aa97fe291c439a0698">TRI</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Public Member Attributes

### LiveInRegs {#aaf4867227a975bcae4b285003d7a8554}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">SmallVector&lt;VRegMaskOrUnit, 8&gt; llvm::RegisterPressure::LiveInRegs</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>List of live in virtual registers or physical register units.</p>

<p>Definition at line 52 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/codegen/registerpressure-h">RegisterPressure.h</a>.</p>


<p>Referenced by <a href="#aed5b5c7fd078ad82cea332031dd5099d">dump</a>, <a href="/web-llvm/docs/api/structs/llvm/intervalpressure/#a0fb4cf12022684a5149e2fba6b65a522">llvm::IntervalPressure::openBottom</a>, <a href="/web-llvm/docs/api/structs/llvm/regionpressure/#ad620503b286436fe7252602b9451dfca">llvm::RegionPressure::openBottom</a>, <a href="/web-llvm/docs/api/structs/llvm/intervalpressure/#ad388da0eac059da0c6cf642204a6308a">llvm::IntervalPressure::openTop</a>, <a href="/web-llvm/docs/api/structs/llvm/regionpressure/#a9f41ba24a7e6d9e5a68764096c2e763c">llvm::RegionPressure::openTop</a>, <a href="/web-llvm/docs/api/structs/llvm/intervalpressure/#a08225fe2adf56bf962e71483729fd99c">llvm::IntervalPressure::reset</a> and <a href="/web-llvm/docs/api/structs/llvm/regionpressure/#aa7faa2156e15c1085990ef11a6d19ac5">llvm::RegionPressure::reset</a>.</p>

</div>
</div>

### LiveOutRegs {#a8e0d374fff11a3139a343cb42338b989}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">SmallVector&lt;VRegMaskOrUnit, 8&gt; llvm::RegisterPressure::LiveOutRegs</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 53 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/codegen/registerpressure-h">RegisterPressure.h</a>.</p>


<p>Referenced by <a href="#aed5b5c7fd078ad82cea332031dd5099d">dump</a>, <a href="/web-llvm/docs/api/structs/llvm/intervalpressure/#a08225fe2adf56bf962e71483729fd99c">llvm::IntervalPressure::reset</a> and <a href="/web-llvm/docs/api/structs/llvm/regionpressure/#aa7faa2156e15c1085990ef11a6d19ac5">llvm::RegionPressure::reset</a>.</p>

</div>
</div>

### MaxSetPressure {#af444f3c79d12bb654d6477d629cbe7c0}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">std::vector&lt;unsigned&gt; llvm::RegisterPressure::MaxSetPressure</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Map of max reg pressure indexed by pressure set <a href="/web-llvm/docs/api/namespaces/llvm/callingconv/#abdf8cf606905c10634e831390981b0ed">ID</a>, not class <a href="/web-llvm/docs/api/namespaces/llvm/callingconv/#abdf8cf606905c10634e831390981b0ed">ID</a>.</p>

<p>Definition at line 49 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/codegen/registerpressure-h">RegisterPressure.h</a>.</p>


<p>Referenced by <a href="#aed5b5c7fd078ad82cea332031dd5099d">dump</a>, <a href="/web-llvm/docs/api/structs/llvm/intervalpressure/#a08225fe2adf56bf962e71483729fd99c">llvm::IntervalPressure::reset</a>, <a href="/web-llvm/docs/api/structs/llvm/regionpressure/#aa7faa2156e15c1085990ef11a6d19ac5">llvm::RegionPressure::reset</a> and <a href="/web-llvm/docs/api/classes/llvm/ppcinstrinfo/#acba682e84de176f762ddc4d774819cae">llvm::PPCInstrInfo::shouldReduceRegisterPressure</a>.</p>

</div>
</div>

</div>

<hr/>

The documentation for this struct was generated from the following files:

<ul>
<li><a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/codegen/registerpressure-h">RegisterPressure.h</a></li>
<li><a href="/web-llvm/docs/api/files/lib/lib/codegen/registerpressure-cpp">RegisterPressure.cpp</a></li>
</ul>

<hr/>

<p class="doxyGeneratedBy">Generated via <a href="https://github.com/xpack/doxygen2docusaurus">doxygen2docusaurus</a> by <a href="https://www.doxygen.nl">Doxygen</a> 1.15.0.</p>

</div>
