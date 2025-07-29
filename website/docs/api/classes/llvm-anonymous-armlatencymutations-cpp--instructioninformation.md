---

# DO NOT EDIT!
# Automatically generated via doxygen2docusaurus by Doxygen.

slug: /api/classes/llvm/anonymous-armlatencymutations-cpp-/instructioninformation
custom_edit_url: null
toc_max_heading_level: 4
keywords:
  - doxygen
  - reference
  - class

---

<div class="doxyPage">

# `InstructionInformation` Class



## Declaration

<div class="doxyDeclaration">
class llvm::anonymous{ARMLatencyMutations.cpp}::InstructionInformation { ... }
</div>

## Derived Classes

<table class="doxyMembersIndex">

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">class</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/anonymous-armlatencymutations-cpp-/cortexm7instructioninformation">CortexM7InstructionInformation</a></td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">class</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/anonymous-armlatencymutations-cpp-/m85instructioninformation">M85InstructionInformation</a></td>
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

## Protected Member Typedefs Index

<table class="doxyMembersIndex">

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">typedef</td>
<td class="doxyMemberIndexItemName" align="left" valign="top">std::array&lt; <a href="/web-llvm/docs/api/structs/llvm/anonymous-armlatencymutations-cpp-/instructioninformation/iinfo">IInfo</a>, ARM::INSTRUCTION_LIST_END &gt; <a href="#a4e9c530965cf2f3beb2eb2d8a4a797bd">IInfoArray</a></td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a6b97b7ecbffbfda703ccfe7e14d4d0c3">InstructionInformation</a> (const ARMBaseInstrInfo *TII)</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">unsigned</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ae6707fb7fa6749699b9a40e9d3905bf3">getAddressOpMask</a> (unsigned Op)</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#abe4201460e65df46409234c118c9eaea">hasBRegAddr</a> (unsigned Op)</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a0f43473b52fec0d5f4cf73fc2610bf98">hasBRegAddrShift</a> (unsigned Op)</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a343d7a2c17e9c267f959c9a8823a4562">isDivide</a> (unsigned Op)</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ae8d12f100306e91693f23e85fe68f9c1">isInlineShiftALU</a> (unsigned Op)</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ae505b61d426473e612025a69b6e4df98">isMultiply</a> (unsigned Op)</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a1a1c1f53c0750dc5358e4bf517f7bc38">isMVEIntMAC</a> (unsigned Op)</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a7eb1211d7a652e4eb8c34fb71462ea13">isNonSubwordLoad</a> (unsigned Op)</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#add24c360d68aacf5232a2d2c022c5e14">isRev</a> (unsigned Op)</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a99697ec14717fa82f166eb5c29d629b6">isShift</a> (unsigned Op)</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a9da481d0286a1e9b51e58b416b56c8a7">producesQP</a> (unsigned Op)</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a4f5b1a946daf32a4ca0d1b68085d75b4">producesDP</a> (unsigned Op)</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a3be53dc564f6ee9ac058309039ff44f0">producesSP</a> (unsigned Op)</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ab26173b46bacc05b8a192c000185cc31">consumesQP</a> (unsigned Op)</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#acf455f7d3d3fbf4250b5d75841310ee7">consumesDP</a> (unsigned Op)</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#abf5d3f8e03cfab5337089883699bb1cd">consumesSP</a> (unsigned Op)</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a07313818808353508e929c31891062d0">isMVEIntMACMatched</a> (unsigned SrcOp, unsigned DstOp)</td>
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

## Protected Member Functions Index

<table class="doxyMembersIndex">

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">void</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#acd87bac3058ade9f773fd2c79abdde8d">markDPProducersConsumers</a> (const ARMBaseInstrInfo *TII)</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="#a4e9c530965cf2f3beb2eb2d8a4a797bd">IInfoArray</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#af0b8b25642dc5c5a358a8f51ca04ba88">Info</a></td>
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


<p>Definition at line 32 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/arm/armlatencymutations-cpp">ARMLatencyMutations.cpp</a>.</p>


<div class="doxySectionDef">

## Protected Member Typedefs

### IInfoArray {#a4e9c530965cf2f3beb2eb2d8a4a797bd}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">typedef std::array&lt;IInfo, ARM::INSTRUCTION_LIST_END&gt; llvm::anonymous{ARMLatencyMutations.cpp}::InstructionInformation::IInfoArray</td>
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



<p>Definition at line 60 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/arm/armlatencymutations-cpp">ARMLatencyMutations.cpp</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Public Constructors

### InstructionInformation() {#a6b97b7ecbffbfda703ccfe7e14d4d0c3}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">llvm::anonymous{ARMLatencyMutations.cpp}::InstructionInformation::InstructionInformation (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/armbaseinstrinfo">ARMBaseInstrInfo</a> * TII)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 88 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/arm/armlatencymutations-cpp">ARMLatencyMutations.cpp</a>.</p>


<p>References <a href="#af0b8b25642dc5c5a358a8f51ca04ba88">Info</a>, <a href="#a6b97b7ecbffbfda703ccfe7e14d4d0c3">InstructionInformation</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/hexagon/hexagonbittracker-cpp/#a0ee73ba17c3a2cb54752905e99d77357">op</a> and <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/hexagon/hexagoncopytocombine-cpp/#a1d40004718218dbdf06b496766299101">TII</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/classes/llvm/anonymous-armlatencymutations-cpp-/cortexm7instructioninformation/#ae034fc5caea3f57c89bb7f74929a8aea">llvm::anonymous{ARMLatencyMutations.cpp}::CortexM7InstructionInformation::CortexM7InstructionInformation</a>, <a href="#a6b97b7ecbffbfda703ccfe7e14d4d0c3">InstructionInformation</a> and <a href="/web-llvm/docs/api/classes/llvm/anonymous-armlatencymutations-cpp-/m85instructioninformation/#a9490502b2a3a7904b5312f9b2bdc51f4">llvm::anonymous{ARMLatencyMutations.cpp}::M85InstructionInformation::M85InstructionInformation</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Public Member Functions

### consumesDP() {#acf455f7d3d3fbf4250b5d75841310ee7}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool llvm::anonymous{ARMLatencyMutations.cpp}::InstructionInformation::consumesDP (unsigned Op)</td>
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



<p>Definition at line 81 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/arm/armlatencymutations-cpp">ARMLatencyMutations.cpp</a>.</p>


<p>Reference <a href="#af0b8b25642dc5c5a358a8f51ca04ba88">Info</a>.</p>

</div>
</div>

### consumesQP() {#ab26173b46bacc05b8a192c000185cc31}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool llvm::anonymous{ARMLatencyMutations.cpp}::InstructionInformation::consumesQP (unsigned Op)</td>
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



<p>Definition at line 80 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/arm/armlatencymutations-cpp">ARMLatencyMutations.cpp</a>.</p>


<p>Reference <a href="#af0b8b25642dc5c5a358a8f51ca04ba88">Info</a>.</p>

</div>
</div>

### consumesSP() {#abf5d3f8e03cfab5337089883699bb1cd}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool llvm::anonymous{ARMLatencyMutations.cpp}::InstructionInformation::consumesSP (unsigned Op)</td>
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



<p>Definition at line 82 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/arm/armlatencymutations-cpp">ARMLatencyMutations.cpp</a>.</p>


<p>Reference <a href="#af0b8b25642dc5c5a358a8f51ca04ba88">Info</a>.</p>

</div>
</div>

### getAddressOpMask() {#ae6707fb7fa6749699b9a40e9d3905bf3}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">unsigned llvm::anonymous{ARMLatencyMutations.cpp}::InstructionInformation::getAddressOpMask (unsigned Op)</td>
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



<p>Definition at line 65 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/arm/armlatencymutations-cpp">ARMLatencyMutations.cpp</a>.</p>


<p>Reference <a href="#af0b8b25642dc5c5a358a8f51ca04ba88">Info</a>.</p>

</div>
</div>

### hasBRegAddr() {#abe4201460e65df46409234c118c9eaea}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool llvm::anonymous{ARMLatencyMutations.cpp}::InstructionInformation::hasBRegAddr (unsigned Op)</td>
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



<p>Definition at line 66 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/arm/armlatencymutations-cpp">ARMLatencyMutations.cpp</a>.</p>


<p>Reference <a href="#af0b8b25642dc5c5a358a8f51ca04ba88">Info</a>.</p>

</div>
</div>

### hasBRegAddrShift() {#a0f43473b52fec0d5f4cf73fc2610bf98}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool llvm::anonymous{ARMLatencyMutations.cpp}::InstructionInformation::hasBRegAddrShift (unsigned Op)</td>
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



<p>Definition at line 67 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/arm/armlatencymutations-cpp">ARMLatencyMutations.cpp</a>.</p>


<p>Reference <a href="#af0b8b25642dc5c5a358a8f51ca04ba88">Info</a>.</p>

</div>
</div>

### isDivide() {#a343d7a2c17e9c267f959c9a8823a4562}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool llvm::anonymous{ARMLatencyMutations.cpp}::InstructionInformation::isDivide (unsigned Op)</td>
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



<p>Definition at line 68 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/arm/armlatencymutations-cpp">ARMLatencyMutations.cpp</a>.</p>


<p>Reference <a href="#af0b8b25642dc5c5a358a8f51ca04ba88">Info</a>.</p>

</div>
</div>

### isInlineShiftALU() {#ae8d12f100306e91693f23e85fe68f9c1}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool llvm::anonymous{ARMLatencyMutations.cpp}::InstructionInformation::isInlineShiftALU (unsigned Op)</td>
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



<p>Definition at line 69 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/arm/armlatencymutations-cpp">ARMLatencyMutations.cpp</a>.</p>


<p>Reference <a href="#af0b8b25642dc5c5a358a8f51ca04ba88">Info</a>.</p>

</div>
</div>

### isMultiply() {#ae505b61d426473e612025a69b6e4df98}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool llvm::anonymous{ARMLatencyMutations.cpp}::InstructionInformation::isMultiply (unsigned Op)</td>
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



<p>Definition at line 70 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/arm/armlatencymutations-cpp">ARMLatencyMutations.cpp</a>.</p>


<p>Reference <a href="#af0b8b25642dc5c5a358a8f51ca04ba88">Info</a>.</p>

</div>
</div>

### isMVEIntMAC() {#a1a1c1f53c0750dc5358e4bf517f7bc38}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool llvm::anonymous{ARMLatencyMutations.cpp}::InstructionInformation::isMVEIntMAC (unsigned Op)</td>
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



<p>Definition at line 71 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/arm/armlatencymutations-cpp">ARMLatencyMutations.cpp</a>.</p>


<p>Reference <a href="#af0b8b25642dc5c5a358a8f51ca04ba88">Info</a>.</p>

</div>
</div>

### isMVEIntMACMatched() {#a07313818808353508e929c31891062d0}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool llvm::anonymous{ARMLatencyMutations.cpp}::InstructionInformation::isMVEIntMACMatched (unsigned SrcOp, unsigned DstOp)</td>
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



<p>Definition at line 84 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/arm/armlatencymutations-cpp">ARMLatencyMutations.cpp</a>.</p>


<p>Reference <a href="#af0b8b25642dc5c5a358a8f51ca04ba88">Info</a>.</p>

</div>
</div>

### isNonSubwordLoad() {#a7eb1211d7a652e4eb8c34fb71462ea13}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool llvm::anonymous{ARMLatencyMutations.cpp}::InstructionInformation::isNonSubwordLoad (unsigned Op)</td>
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



<p>Definition at line 72 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/arm/armlatencymutations-cpp">ARMLatencyMutations.cpp</a>.</p>


<p>Reference <a href="#af0b8b25642dc5c5a358a8f51ca04ba88">Info</a>.</p>

</div>
</div>

### isRev() {#add24c360d68aacf5232a2d2c022c5e14}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool llvm::anonymous{ARMLatencyMutations.cpp}::InstructionInformation::isRev (unsigned Op)</td>
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



<p>Definition at line 73 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/arm/armlatencymutations-cpp">ARMLatencyMutations.cpp</a>.</p>


<p>Reference <a href="#af0b8b25642dc5c5a358a8f51ca04ba88">Info</a>.</p>

</div>
</div>

### isShift() {#a99697ec14717fa82f166eb5c29d629b6}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool llvm::anonymous{ARMLatencyMutations.cpp}::InstructionInformation::isShift (unsigned Op)</td>
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



<p>Definition at line 74 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/arm/armlatencymutations-cpp">ARMLatencyMutations.cpp</a>.</p>


<p>Reference <a href="#af0b8b25642dc5c5a358a8f51ca04ba88">Info</a>.</p>

</div>
</div>

### producesDP() {#a4f5b1a946daf32a4ca0d1b68085d75b4}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool llvm::anonymous{ARMLatencyMutations.cpp}::InstructionInformation::producesDP (unsigned Op)</td>
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



<p>Definition at line 78 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/arm/armlatencymutations-cpp">ARMLatencyMutations.cpp</a>.</p>


<p>Reference <a href="#af0b8b25642dc5c5a358a8f51ca04ba88">Info</a>.</p>

</div>
</div>

### producesQP() {#a9da481d0286a1e9b51e58b416b56c8a7}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool llvm::anonymous{ARMLatencyMutations.cpp}::InstructionInformation::producesQP (unsigned Op)</td>
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



<p>Definition at line 77 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/arm/armlatencymutations-cpp">ARMLatencyMutations.cpp</a>.</p>


<p>Reference <a href="#af0b8b25642dc5c5a358a8f51ca04ba88">Info</a>.</p>

</div>
</div>

### producesSP() {#a3be53dc564f6ee9ac058309039ff44f0}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool llvm::anonymous{ARMLatencyMutations.cpp}::InstructionInformation::producesSP (unsigned Op)</td>
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



<p>Definition at line 79 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/arm/armlatencymutations-cpp">ARMLatencyMutations.cpp</a>.</p>


<p>Reference <a href="#af0b8b25642dc5c5a358a8f51ca04ba88">Info</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Protected Member Functions

### markDPProducersConsumers() {#acd87bac3058ade9f773fd2c79abdde8d}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void llvm::anonymous{ARMLatencyMutations.cpp}::InstructionInformation::markDPProducersConsumers (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/armbaseinstrinfo">ARMBaseInstrInfo</a> * TII)</td>
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



<p>Definition at line 91 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/arm/armlatencymutations-cpp">ARMLatencyMutations.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/classes/llvm/mcinstrdesc/#a3496944fcc473dfe584e6615503a7a76">llvm::MCInstrDesc::getNumDefs</a>, <a href="/web-llvm/docs/api/classes/llvm/mcinstrdesc/#a0ca904e64ee29c8812ed34e632d3c947">llvm::MCInstrDesc::getNumOperands</a>, <a href="#af0b8b25642dc5c5a358a8f51ca04ba88">Info</a>, <a href="#acd87bac3058ade9f773fd2c79abdde8d">markDPProducersConsumers</a>, <a href="/web-llvm/docs/api/files/lib/lib/codegen/lib/codegen/globalisel/irtranslator-cpp/#abe44dfdea65b4f7e11e0a608ab708b76">MI</a>, <a href="/web-llvm/docs/api/files/lib/lib/codegen/mirnamerpass-cpp/#a05e4be4ec3e2c3587dda0e376bb6822c">Operands</a>, <a href="/web-llvm/docs/api/classes/llvm/mcinstrdesc/#a0f4e09a761d45bf0914f26d4c149ddeb">llvm::MCInstrDesc::operands</a> and <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/hexagon/hexagoncopytocombine-cpp/#a1d40004718218dbdf06b496766299101">TII</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/classes/llvm/anonymous-armlatencymutations-cpp-/m85instructioninformation/#a9490502b2a3a7904b5312f9b2bdc51f4">llvm::anonymous{ARMLatencyMutations.cpp}::M85InstructionInformation::M85InstructionInformation</a> and <a href="#acd87bac3058ade9f773fd2c79abdde8d">markDPProducersConsumers</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Protected Member Attributes

### Info {#af0b8b25642dc5c5a358a8f51ca04ba88}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">IInfoArray llvm::anonymous{ARMLatencyMutations.cpp}::InstructionInformation::Info</td>
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



<p>Definition at line 61 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/arm/armlatencymutations-cpp">ARMLatencyMutations.cpp</a>.</p>


<p>Referenced by <a href="#acf455f7d3d3fbf4250b5d75841310ee7">consumesDP</a>, <a href="#ab26173b46bacc05b8a192c000185cc31">consumesQP</a>, <a href="#abf5d3f8e03cfab5337089883699bb1cd">consumesSP</a>, <a href="#ae6707fb7fa6749699b9a40e9d3905bf3">getAddressOpMask</a>, <a href="#abe4201460e65df46409234c118c9eaea">hasBRegAddr</a>, <a href="#a0f43473b52fec0d5f4cf73fc2610bf98">hasBRegAddrShift</a>, <a href="#a6b97b7ecbffbfda703ccfe7e14d4d0c3">InstructionInformation</a>, <a href="#a343d7a2c17e9c267f959c9a8823a4562">isDivide</a>, <a href="#ae8d12f100306e91693f23e85fe68f9c1">isInlineShiftALU</a>, <a href="#ae505b61d426473e612025a69b6e4df98">isMultiply</a>, <a href="#a1a1c1f53c0750dc5358e4bf517f7bc38">isMVEIntMAC</a>, <a href="#a07313818808353508e929c31891062d0">isMVEIntMACMatched</a>, <a href="#a7eb1211d7a652e4eb8c34fb71462ea13">isNonSubwordLoad</a>, <a href="#add24c360d68aacf5232a2d2c022c5e14">isRev</a>, <a href="#a99697ec14717fa82f166eb5c29d629b6">isShift</a>, <a href="#acd87bac3058ade9f773fd2c79abdde8d">markDPProducersConsumers</a>, <a href="#a4f5b1a946daf32a4ca0d1b68085d75b4">producesDP</a>, <a href="#a9da481d0286a1e9b51e58b416b56c8a7">producesQP</a> and <a href="#a3be53dc564f6ee9ac058309039ff44f0">producesSP</a>.</p>

</div>
</div>

</div>

<hr/>

The documentation for this class was generated from the following file:

<ul>
<li><a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/arm/armlatencymutations-cpp">ARMLatencyMutations.cpp</a></li>
</ul>

<hr/>

<p class="doxyGeneratedBy">Generated via <a href="https://github.com/xpack/doxygen2docusaurus">doxygen2docusaurus</a> by <a href="https://www.doxygen.nl">Doxygen</a> 1.15.0.</p>

</div>
