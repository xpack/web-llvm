---

# DO NOT EDIT!
# Automatically generated via doxygen2docusaurus by Doxygen.

slug: /api/structs/anonymous-armloadstoreoptimizer-cpp-/armloadstoreopt/mergecandidate
custom_edit_url: null
toc_max_heading_level: 4
keywords:
  - doxygen
  - reference
  - struct

---

<div class="doxyPage">

# The `MergeCandidate` Struct Reference

<p>A set of MachineInstrs that fulfill (nearly all) conditions to get merged into a LDM/STM. <a href="#details">More...</a></p>

## Declaration

<div class="doxyDeclaration">
struct anonymous{ARMLoadStoreOptimizer.cpp}::ARMLoadStoreOpt::MergeCandidate { ... }
</div>

## Public Member Attributes Index

<table class="doxyMembersIndex">

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/smallvector">SmallVector</a>&lt; <a href="/web-llvm/docs/api/classes/llvm/machineinstr">MachineInstr</a> *, 4 &gt;</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ab1794a09a795ebe434211ff7a44e8a63">Instrs</a></td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>List of instructions ordered by load/store offset. <a href="#ab1794a09a795ebe434211ff7a44e8a63">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">unsigned</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#aff004d407110a85c3c7a1da85145c2a1">LatestMIIdx</a></td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Index in Instrs of the instruction being latest in the schedule. <a href="#aff004d407110a85c3c7a1da85145c2a1">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">unsigned</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a4635bc1a656730b056a01bcc4adfd37b">EarliestMIIdx</a></td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Index in Instrs of the instruction being earliest in the schedule. <a href="#a4635bc1a656730b056a01bcc4adfd37b">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">unsigned</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a8e7b5a28e14aedf6be9a3c23d0863021">InsertPos</a></td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Index into the basic block where the merged instruction will be inserted. <a href="#a8e7b5a28e14aedf6be9a3c23d0863021">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">bool</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ac3df2fbe652532ef2b956b704f53baaa">CanMergeToLSMulti</a></td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Whether the instructions can be merged into a ldm/stm instruction. <a href="#ac3df2fbe652532ef2b956b704f53baaa">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">bool</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ae4add619756aa86a57fda6983de2e6d5">CanMergeToLSDouble</a></td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Whether the instructions can be merged into a ldrd/strd instruction. <a href="#ae4add619756aa86a57fda6983de2e6d5">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

</table>

## Description {#details}

<p>A set of MachineInstrs that fulfill (nearly all) conditions to get merged into a LDM/STM.</p>

<p>Definition at line 143 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/arm/armloadstoreoptimizer-cpp">ARMLoadStoreOptimizer.cpp</a>.</p>


<div class="doxySectionDef">

## Public Member Attributes

### CanMergeToLSDouble {#ae4add619756aa86a57fda6983de2e6d5}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool anonymous{ARMLoadStoreOptimizer.cpp}::ARMLoadStoreOpt::MergeCandidate::CanMergeToLSDouble</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Whether the instructions can be merged into a ldrd/strd instruction.</p>

<p>Definition at line 161 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/arm/armloadstoreoptimizer-cpp">ARMLoadStoreOptimizer.cpp</a>.</p>

</div>
</div>

### CanMergeToLSMulti {#ac3df2fbe652532ef2b956b704f53baaa}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool anonymous{ARMLoadStoreOptimizer.cpp}::ARMLoadStoreOpt::MergeCandidate::CanMergeToLSMulti</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Whether the instructions can be merged into a ldm/stm instruction.</p>

<p>Definition at line 158 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/arm/armloadstoreoptimizer-cpp">ARMLoadStoreOptimizer.cpp</a>.</p>

</div>
</div>

### EarliestMIIdx {#a4635bc1a656730b056a01bcc4adfd37b}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">unsigned anonymous{ARMLoadStoreOptimizer.cpp}::ARMLoadStoreOpt::MergeCandidate::EarliestMIIdx</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Index in Instrs of the instruction being earliest in the schedule.</p>

<p>Definition at line 151 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/arm/armloadstoreoptimizer-cpp">ARMLoadStoreOptimizer.cpp</a>.</p>

</div>
</div>

### InsertPos {#a8e7b5a28e14aedf6be9a3c23d0863021}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">unsigned anonymous{ARMLoadStoreOptimizer.cpp}::ARMLoadStoreOpt::MergeCandidate::InsertPos</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Index into the basic block where the merged instruction will be inserted.</p>


<p>(See MemOpQueueEntry.Position)</p>


<p>Definition at line 155 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/arm/armloadstoreoptimizer-cpp">ARMLoadStoreOptimizer.cpp</a>.</p>

</div>
</div>

### Instrs {#ab1794a09a795ebe434211ff7a44e8a63}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">SmallVector&lt;MachineInstr*, 4&gt; anonymous{ARMLoadStoreOptimizer.cpp}::ARMLoadStoreOpt::MergeCandidate::Instrs</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>List of instructions ordered by load/store offset.</p>

<p>Definition at line 145 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/arm/armloadstoreoptimizer-cpp">ARMLoadStoreOptimizer.cpp</a>.</p>

</div>
</div>

### LatestMIIdx {#aff004d407110a85c3c7a1da85145c2a1}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">unsigned anonymous{ARMLoadStoreOptimizer.cpp}::ARMLoadStoreOpt::MergeCandidate::LatestMIIdx</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Index in Instrs of the instruction being latest in the schedule.</p>

<p>Definition at line 148 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/arm/armloadstoreoptimizer-cpp">ARMLoadStoreOptimizer.cpp</a>.</p>

</div>
</div>

</div>

<hr/>

The documentation for this struct was generated from the following file:

<ul>
<li><a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/arm/armloadstoreoptimizer-cpp">ARMLoadStoreOptimizer.cpp</a></li>
</ul>

<hr/>

<p class="doxyGeneratedBy">Generated via <a href="https://github.com/xpack/doxygen2docusaurus">doxygen2docusaurus</a> by <a href="https://www.doxygen.nl">Doxygen</a> 1.15.0.</p>

</div>
