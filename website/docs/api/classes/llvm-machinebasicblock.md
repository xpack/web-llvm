---

# DO NOT EDIT!
# Automatically generated via doxygen2docusaurus by Doxygen.

slug: /api/classes/llvm/machinebasicblock
custom_edit_url: null
toc_max_heading_level: 4
keywords:
  - doxygen
  - reference
  - class

---

<div class="doxyPage">

# The `MachineBasicBlock` Class Reference



## Declaration

<div class="doxyDeclaration">
class llvm::MachineBasicBlock { ... }
</div>

## Included Headers

<div class="doxyIncludesList">#include "<a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/codegen/machinebasicblock-h">llvm/CodeGen/MachineBasicBlock.h</a>"
</div>

## Base class

<table class="doxyMembersIndex">

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">class</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/ilist-node-with-parent">ilist_node_with_parent&lt;NodeTy, ParentTy, Options&gt;</a></td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>An ilist node that can access its parent list. <a href="/web-llvm/docs/api/classes/llvm/ilist-node-with-parent/#details">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

</table>

## Public Member Typedefs Index

<table class="doxyMembersIndex">

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">using</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ab6395548cae73865213e279ae461db54">instr_iterator</a> = <a href="/web-llvm/docs/api/classes/llvm/iplist-impl/#a4563732eae31ee14694e7ce17a5a6749">Instructions::iterator</a></td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#acc786576edf1d6a2697426143314bcef">const_instr_iterator</a> = <a href="/web-llvm/docs/api/classes/llvm/iplist-impl/#a3a5c6f429b19022105ee49f587c7ed04">Instructions::const_iterator</a></td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#afde32735260c30997acd66990e80a320">reverse_instr_iterator</a> = <a href="/web-llvm/docs/api/classes/llvm/iplist-impl/#a3597c16fc1832e39109d9848a63cc55c">Instructions::reverse_iterator</a></td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a014d813afe056b3d260ef97687347e32">const_reverse_instr_iterator</a> = <a href="/web-llvm/docs/api/classes/llvm/iplist-impl/#a297861b8ff76496286b3bea882c2969a">Instructions::const_reverse_iterator</a></td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ae34c996b58df9b9ce6695a0c8b70c533">iterator</a> = <a href="/web-llvm/docs/api/classes/llvm/machineinstrbundleiterator">MachineInstrBundleIterator</a>&lt; <a href="/web-llvm/docs/api/classes/llvm/machineinstr">MachineInstr</a> &gt;</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a199a6e4bfdffc8f3379ef4f35004488f">const_iterator</a> = <a href="/web-llvm/docs/api/classes/llvm/machineinstrbundleiterator">MachineInstrBundleIterator</a>&lt; <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/machineinstr">MachineInstr</a> &gt;</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#abada92f8cd2854d2b747f14c4a7be0ed">reverse_iterator</a> = <a href="/web-llvm/docs/api/classes/llvm/machineinstrbundleiterator">MachineInstrBundleIterator</a>&lt; <a href="/web-llvm/docs/api/classes/llvm/machineinstr">MachineInstr</a>, <a href="/web-llvm/docs/api/files/lib/lib/analysis/basicaliasanalysis-cpp/#af6d5cafbdfc5313e65d990120021a3ec">true</a> &gt;</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#af09a6bd5bd27c029abbf5f0b7e5dc137">const_reverse_iterator</a> = <a href="/web-llvm/docs/api/classes/llvm/machineinstrbundleiterator">MachineInstrBundleIterator</a>&lt; <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/machineinstr">MachineInstr</a>, <a href="/web-llvm/docs/api/files/lib/lib/analysis/basicaliasanalysis-cpp/#af6d5cafbdfc5313e65d990120021a3ec">true</a> &gt;</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#af91eb0d508929a6b59d300bc7052390f">instr_range</a> = <a href="/web-llvm/docs/api/classes/llvm/iterator-range">iterator_range</a>&lt; <a href="#ab6395548cae73865213e279ae461db54">instr_iterator</a> &gt;</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a9140b0e73280574a820037cf0aa6adf3">const_instr_range</a> = <a href="/web-llvm/docs/api/classes/llvm/iterator-range">iterator_range</a>&lt; <a href="#acc786576edf1d6a2697426143314bcef">const_instr_iterator</a> &gt;</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#aa3e6549a5c552971ce60013e2e7c6154">pred_iterator</a> = <a href="/web-llvm/docs/api/classes/llvm/smallvectorimpl">SmallVectorImpl</a>&lt; <a href="/web-llvm/docs/api/classes/llvm/machinebasicblock">MachineBasicBlock</a> * &gt;<a href="#ae34c996b58df9b9ce6695a0c8b70c533">::iterator</a></td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#af23bb5122fa5f787c2e1ba23a5325331">const_pred_iterator</a> = <a href="/web-llvm/docs/api/classes/llvm/smallvectorimpl">SmallVectorImpl</a>&lt; <a href="/web-llvm/docs/api/classes/llvm/machinebasicblock">MachineBasicBlock</a> * &gt;::const_iterator</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a9936e11d7a6149f7cac8fa32a81dd488">succ_iterator</a> = <a href="/web-llvm/docs/api/classes/llvm/smallvectorimpl">SmallVectorImpl</a>&lt; <a href="/web-llvm/docs/api/classes/llvm/machinebasicblock">MachineBasicBlock</a> * &gt;<a href="#ae34c996b58df9b9ce6695a0c8b70c533">::iterator</a></td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a3f43e04d827b07cf1d5366554d03f748">const_succ_iterator</a> = <a href="/web-llvm/docs/api/classes/llvm/smallvectorimpl">SmallVectorImpl</a>&lt; <a href="/web-llvm/docs/api/classes/llvm/machinebasicblock">MachineBasicBlock</a> * &gt;::const_iterator</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#adc1b2a5ae459095d279b621a419e6ea0">pred_reverse_iterator</a> = <a href="/web-llvm/docs/api/classes/llvm/smallvectorimpl">SmallVectorImpl</a>&lt; <a href="/web-llvm/docs/api/classes/llvm/machinebasicblock">MachineBasicBlock</a> * &gt;<a href="#abada92f8cd2854d2b747f14c4a7be0ed">::reverse_iterator</a></td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a422a49a2a62f51ee4cadd8efd33dcfbe">const_pred_reverse_iterator</a> = <a href="/web-llvm/docs/api/classes/llvm/smallvectorimpl">SmallVectorImpl</a>&lt; <a href="/web-llvm/docs/api/classes/llvm/machinebasicblock">MachineBasicBlock</a> * &gt;<a href="#af09a6bd5bd27c029abbf5f0b7e5dc137">::const_reverse_iterator</a></td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a2e976bfbcbbea1b5ba70c6eb56bf108e">succ_reverse_iterator</a> = <a href="/web-llvm/docs/api/classes/llvm/smallvectorimpl">SmallVectorImpl</a>&lt; <a href="/web-llvm/docs/api/classes/llvm/machinebasicblock">MachineBasicBlock</a> * &gt;<a href="#abada92f8cd2854d2b747f14c4a7be0ed">::reverse_iterator</a></td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a94786cbd25915d1f798cca9a14ce0d34">const_succ_reverse_iterator</a> = <a href="/web-llvm/docs/api/classes/llvm/smallvectorimpl">SmallVectorImpl</a>&lt; <a href="/web-llvm/docs/api/classes/llvm/machinebasicblock">MachineBasicBlock</a> * &gt;<a href="#af09a6bd5bd27c029abbf5f0b7e5dc137">::const_reverse_iterator</a></td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a787c857539b04a8552aec72d561a3ca2">livein_iterator</a> = LiveInVector::const_iterator</td>
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

## Private Member Typedefs Index

<table class="doxyMembersIndex">

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">using</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ad3c3e5d2c4208c5032c7466a00cf9d1d">Instructions</a> = <a href="/web-llvm/docs/api/namespaces/llvm/#a62ea5abc9af8e7ee394912e2617cf30f">ilist</a>&lt; <a href="/web-llvm/docs/api/classes/llvm/machineinstr">MachineInstr</a>, <a href="/web-llvm/docs/api/structs/llvm/ilist-sentinel-tracking">ilist_sentinel_tracking</a>&lt; <a href="/web-llvm/docs/api/files/lib/lib/analysis/basicaliasanalysis-cpp/#af6d5cafbdfc5313e65d990120021a3ec">true</a> &gt; &gt;</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a86fb7beac625c137e20e708cd5f0ccf6">probability_iterator</a> = std::vector&lt; <a href="/web-llvm/docs/api/classes/llvm/branchprobability">BranchProbability</a> &gt;<a href="#ae34c996b58df9b9ce6695a0c8b70c533">::iterator</a></td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ab99f82bbbab32ed7281272176425ad4a">const_probability_iterator</a> = std::vector&lt; <a href="/web-llvm/docs/api/classes/llvm/branchprobability">BranchProbability</a> &gt;::const_iterator</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a2ed4997d258b757a53564f79a788b32e">LiveInVector</a> = std::vector&lt; <a href="/web-llvm/docs/api/structs/llvm/machinebasicblock/registermaskpair">RegisterMaskPair</a> &gt;</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Keep track of the physical registers that are livein of the basicblock. <a href="#a2ed4997d258b757a53564f79a788b32e">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

</table>

## Enumerations Index

<table class="doxyMembersIndex">

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">enum</td>
<td class="doxyMemberIndexItemName" align="left" valign="top">LivenessQueryResult { <a href="#af0288e181965a5ff9f0c7a75201fd142">...</a> }</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Possible outcome of a register liveness query to <a href="#a7ebfe0cc2f78ae5f27e1944412606973">computeRegisterLiveness()</a> <a href="#af0288e181965a5ff9f0c7a75201fd142">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">enum</td>
<td class="doxyMemberIndexItemName" align="left" valign="top">PrintNameFlag { <a href="#a55df99d8362d83a10b9fb35fd5b8cf7c">...</a> }</td>
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

## Friends Index

<table class="doxyMembersIndex">

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">class</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ac423fefe048ace18159808c5592ae74c">MachineFunction</a></td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ad75fd5d6b52a6efd7f2ae8448871c528">MachineBranchProbabilityInfo</a></td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#acdf9e09362a2acd47819187dabad184b">MIPrinter</a></td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">struct</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#acbd6646c0c037f87ce89191e20336d77">ilist_callback_traits&lt; MachineBasicBlock &gt;</a></td>
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

## Private Constructors Index

<table class="doxyMembersIndex">

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a76eab5c5c5201f40d87ee38e74b71702">MachineBasicBlock</a> ()=default</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#aefa0e690cc1479e4073dfc201785d082">MachineBasicBlock</a> (MachineFunction &amp;MF, const BasicBlock *BB)</td>
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

## Private Destructor Index

<table class="doxyMembersIndex">

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a7458b9e8596683781ad372a590b67041">~MachineBasicBlock</a> ()</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/basicblock">BasicBlock</a> *</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a4874816314c3308be0bf1e71de2078d8">getBasicBlock</a> () const</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Return the LLVM basic block that this instance corresponded to originally. <a href="#a4874816314c3308be0bf1e71de2078d8">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">void</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a6cc466c26334b3089541986b21b4aa02">clearBasicBlock</a> ()</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Remove the reference to the underlying IR <a href="/web-llvm/docs/api/classes/llvm/basicblock">BasicBlock</a>. <a href="#a6cc466c26334b3089541986b21b4aa02">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">bool</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a426db725707eef3025202e393420aa7f">hasName</a> () const</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p><a href="/web-llvm/docs/api/namespaces/llvm/check">Check</a> if there is a name of corresponding LLVM basic block. <a href="#a426db725707eef3025202e393420aa7f">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/stringref">StringRef</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#aedf6cb1135961f41f39dc58ca8576123">getName</a> () const</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Return the name of the corresponding LLVM basic block, or an empty string. <a href="#aedf6cb1135961f41f39dc58ca8576123">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">std::string</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ad2a8da74fd4e4c892018c56c977addee">getFullName</a> () const</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Return a formatted string to identify this block and its parent function. <a href="#ad2a8da74fd4e4c892018c56c977addee">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">bool</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a86ae593fc791eda3aae24bd9d6df2322">hasAddressTaken</a> () const</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Test whether this block is used as something other than the target of a terminator, exception-handling target, or jump table. <a href="#a86ae593fc791eda3aae24bd9d6df2322">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">bool</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ad934138cd088f6c08cbf0f373997fd17">isMachineBlockAddressTaken</a> () const</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Test whether this block is used as something other than the target of a terminator, exception-handling target, jump table, or IR blockaddress. <a href="#ad934138cd088f6c08cbf0f373997fd17">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">bool</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a753336faa16076c3931ae29c55f88f68">isIRBlockAddressTaken</a> () const</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Test whether this block is the target of an IR <a href="/web-llvm/docs/api/classes/llvm/blockaddress">BlockAddress</a>. <a href="#a753336faa16076c3931ae29c55f88f68">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/basicblock">BasicBlock</a> *</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a9e26767dd60f2ffd50a7a6c5ea3a0c32">getAddressTakenIRBlock</a> () const</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Retrieves the <a href="/web-llvm/docs/api/classes/llvm/basicblock">BasicBlock</a> which corresponds to this <a href="/web-llvm/docs/api/classes/llvm/machinebasicblock">MachineBasicBlock</a>. <a href="#a9e26767dd60f2ffd50a7a6c5ea3a0c32">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">void</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#af4236a9c3c028303d301f49c7ee9a868">setMachineBlockAddressTaken</a> ()</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Set this block to indicate that its address is used as something other than the target of a terminator, exception-handling target, jump table, or IR-level "blockaddress". <a href="#af4236a9c3c028303d301f49c7ee9a868">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">void</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a0e100b3a8a8794e966c37ac13b1ea891">setAddressTakenIRBlock</a> (BasicBlock *BB)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Set this block to reflect that it corresponds to an IR-level basic block with a <a href="/web-llvm/docs/api/classes/llvm/blockaddress">BlockAddress</a>. <a href="#a0e100b3a8a8794e966c37ac13b1ea891">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">bool</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a32eddb893169a26afe7e7372ecf943ef">hasLabelMustBeEmitted</a> () const</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Test whether this block must have its label emitted. <a href="#a32eddb893169a26afe7e7372ecf943ef">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">void</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a2861faef4c19963f6994aded803f7d20">setLabelMustBeEmitted</a> ()</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Set this block to reflect that, regardless how we flow to it, we need its label be emitted. <a href="#a2861faef4c19963f6994aded803f7d20">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/machinefunction">MachineFunction</a> *</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#acf6442108e21e7e5379feb8962de65b7">getParent</a> () const</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Return the <a href="/web-llvm/docs/api/classes/llvm/machinefunction">MachineFunction</a> containing this basic block. <a href="#acf6442108e21e7e5379feb8962de65b7">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/machinefunction">MachineFunction</a> *</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ac35a65b864412ca7fd4c25b8724144c9">getParent</a> ()</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a703ba58bd58d60cd76ad205dda1634eb">terminatorIsComputedGoto</a> () const</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Returns true if the original IR terminator is an <span class="doxyComputerOutput">indirectbr</span>. <a href="#a703ba58bd58d60cd76ad205dda1634eb">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">unsigned</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#adbff55f335d303816547f35eb6edb948">size</a> () const</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#af897d8e9556478c1442c739ce664bcb6">sizeWithoutDebugLargerThan</a> (unsigned Limit) const</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a095ce2d870dadf620a4c887ecc0efef8">empty</a> () const</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/machineinstr">MachineInstr</a> &amp;</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ae59809519f8d4797e1c8833cc85fda54">instr_front</a> ()</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/machineinstr">MachineInstr</a> &amp;</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a90c02828bcc7a77219045d7869b54304">instr_back</a> ()</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/machineinstr">MachineInstr</a> &amp;</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a00e3db961381c3ca1eca33de53227f6a">instr_front</a> () const</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/machineinstr">MachineInstr</a> &amp;</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a7510abf5520cdbffac84302d49b2ebc0">instr_back</a> () const</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/machineinstr">MachineInstr</a> &amp;</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#aeedc2554f9637d1e27befa7a85c70ec9">front</a> ()</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/machineinstr">MachineInstr</a> &amp;</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#acf35424231192c6b4a3e22d711f50b1e">back</a> ()</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/machineinstr">MachineInstr</a> &amp;</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a68cc6dfc001c6d7140cee1c7f3e37a48">front</a> () const</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/machineinstr">MachineInstr</a> &amp;</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a12b36a2272e92056473c7b59722afa14">back</a> () const</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="#ab6395548cae73865213e279ae461db54">instr_iterator</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a172e7bd9150eb0519ef04c796086f93d">instr_begin</a> ()</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="#acc786576edf1d6a2697426143314bcef">const_instr_iterator</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a51830f3957f907531febde4c3fbf25d1">instr_begin</a> () const</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="#ab6395548cae73865213e279ae461db54">instr_iterator</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#acae72f6ab1071b7ec87b741a8bef582b">instr_end</a> ()</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="#acc786576edf1d6a2697426143314bcef">const_instr_iterator</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#aa122564bb9dcd534ae31eea9a6dc6ebb">instr_end</a> () const</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="#afde32735260c30997acd66990e80a320">reverse_instr_iterator</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a3758eeb6d9f052f15217146b4ae4d5a1">instr_rbegin</a> ()</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="#a014d813afe056b3d260ef97687347e32">const_reverse_instr_iterator</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#aeb5e3dec197ec0f4bfb5ae384fb6175b">instr_rbegin</a> () const</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="#afde32735260c30997acd66990e80a320">reverse_instr_iterator</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ab42a834f1ab8e65b6f525a5cb23a4fe7">instr_rend</a> ()</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="#a014d813afe056b3d260ef97687347e32">const_reverse_instr_iterator</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a36234942b757e726441b9622bdcfd85b">instr_rend</a> () const</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="#af91eb0d508929a6b59d300bc7052390f">instr_range</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a40bf8f9579717d3f9be7640f1c6d678b">instrs</a> ()</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="#a9140b0e73280574a820037cf0aa6adf3">const_instr_range</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a6b367cbab4e273612adc65fddbce0e91">instrs</a> () const</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="#ae34c996b58df9b9ce6695a0c8b70c533">iterator</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ab2d91e7bec944efcbc39d8e30644f111">begin</a> ()</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="#a199a6e4bfdffc8f3379ef4f35004488f">const_iterator</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#aa86c88f644b3ccab5bac660ca5f45760">begin</a> () const</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="#ae34c996b58df9b9ce6695a0c8b70c533">iterator</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#acbc921830578e2741be6549db716c0ce">end</a> ()</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="#a199a6e4bfdffc8f3379ef4f35004488f">const_iterator</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#aec6d7041bedf7535f7565f3e9471a5bd">end</a> () const</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="#abada92f8cd2854d2b747f14c4a7be0ed">reverse_iterator</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ad8c9657cfb03ef2ebf6364ba9d68c127">rbegin</a> ()</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="#af09a6bd5bd27c029abbf5f0b7e5dc137">const_reverse_iterator</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a6c8e031b0c3396d32f8ed87dfda16a7d">rbegin</a> () const</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="#abada92f8cd2854d2b747f14c4a7be0ed">reverse_iterator</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a2a25c462b91ac5da41f4ab7edc32b650">rend</a> ()</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="#af09a6bd5bd27c029abbf5f0b7e5dc137">const_reverse_iterator</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ab4d33f4fc1545c32aa8bef180f5dbc19">rend</a> () const</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/iterator-range">iterator_range</a>&lt; <a href="#ae34c996b58df9b9ce6695a0c8b70c533">iterator</a> &gt;</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ad56ff27a502cd519f9aaf5cc028b4ea5">terminators</a> ()</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/iterator-range">iterator_range</a>&lt; <a href="#a199a6e4bfdffc8f3379ef4f35004488f">const_iterator</a> &gt;</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#aadfc2f6425b15faff5ce2421cc708205">terminators</a> () const</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/iterator-range">iterator_range</a>&lt; <a href="#ae34c996b58df9b9ce6695a0c8b70c533">iterator</a> &gt;</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a36b529ef331e4099007e14b48c75316a">phis</a> ()</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Returns a range that iterates over the phis in the basic block. <a href="#a36b529ef331e4099007e14b48c75316a">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/iterator-range">iterator_range</a>&lt; <a href="#a199a6e4bfdffc8f3379ef4f35004488f">const_iterator</a> &gt;</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#aa0cd1cb6694e9efa62191e936842b5c4">phis</a> () const</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="#aa3e6549a5c552971ce60013e2e7c6154">pred_iterator</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ab644fcf07a4c2708333cf66276282357">pred_begin</a> ()</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="#af23bb5122fa5f787c2e1ba23a5325331">const_pred_iterator</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ab2e39223357fe836c7c11bbe8bc3c6af">pred_begin</a> () const</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="#aa3e6549a5c552971ce60013e2e7c6154">pred_iterator</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a0359a738e0412c5a7ea55d61175e0661">pred_end</a> ()</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="#af23bb5122fa5f787c2e1ba23a5325331">const_pred_iterator</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a22d721563c09048a50761b9065b046c7">pred_end</a> () const</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="#adc1b2a5ae459095d279b621a419e6ea0">pred_reverse_iterator</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a3c1a265be404da0734c41c2f4b7373b3">pred_rbegin</a> ()</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="#a422a49a2a62f51ee4cadd8efd33dcfbe">const_pred_reverse_iterator</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a9b00167ef2323cf65dbd5a1fde0c882a">pred_rbegin</a> () const</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="#adc1b2a5ae459095d279b621a419e6ea0">pred_reverse_iterator</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a5429a41753b45803fce6e1bc33be84c4">pred_rend</a> ()</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="#a422a49a2a62f51ee4cadd8efd33dcfbe">const_pred_reverse_iterator</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a30f830271b49728f71960a2a76377939">pred_rend</a> () const</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">unsigned</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a03936a9b37da541420049422204ab206">pred_size</a> () const</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a877507fda31c207ec36a018784369708">pred_empty</a> () const</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="#a9936e11d7a6149f7cac8fa32a81dd488">succ_iterator</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a6321b189ea8fd5058663f8a87d6c23e9">succ_begin</a> ()</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="#a3f43e04d827b07cf1d5366554d03f748">const_succ_iterator</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a52fd67628cdf00fadc23e1953a20c2ca">succ_begin</a> () const</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="#a9936e11d7a6149f7cac8fa32a81dd488">succ_iterator</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a3ddd708642d60c1661992ff8ba1b215d">succ_end</a> ()</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="#a3f43e04d827b07cf1d5366554d03f748">const_succ_iterator</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#aa7702db38b77b6d8db4b414105a7b6b7">succ_end</a> () const</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="#a2e976bfbcbbea1b5ba70c6eb56bf108e">succ_reverse_iterator</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#abd32ea34faf1cde285a1b8daccd9c167">succ_rbegin</a> ()</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="#a94786cbd25915d1f798cca9a14ce0d34">const_succ_reverse_iterator</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a539c706b56554cf14a09b2a1124d7788">succ_rbegin</a> () const</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="#a2e976bfbcbbea1b5ba70c6eb56bf108e">succ_reverse_iterator</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#af3e547707a23a2e668d56a85f8482d70">succ_rend</a> ()</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="#a94786cbd25915d1f798cca9a14ce0d34">const_succ_reverse_iterator</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ace984d6e8836a03f99cf5bcb9dfa791d">succ_rend</a> () const</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">unsigned</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a81626de817a0cb021ff8e915cf1942ed">succ_size</a> () const</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#aa8d1d8d88835b75b05b14ab774785e8a">succ_empty</a> () const</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/iterator-range">iterator_range</a>&lt; <a href="#aa3e6549a5c552971ce60013e2e7c6154">pred_iterator</a> &gt;</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#addd80df79ba902914c7d8a52e3896b79">predecessors</a> ()</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/iterator-range">iterator_range</a>&lt; <a href="#af23bb5122fa5f787c2e1ba23a5325331">const_pred_iterator</a> &gt;</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a6faf2a0270e85a9cb7a3b871cfb3d9df">predecessors</a> () const</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/iterator-range">iterator_range</a>&lt; <a href="#a9936e11d7a6149f7cac8fa32a81dd488">succ_iterator</a> &gt;</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ad88ff1529541fb4e243cc8ed90b11131">successors</a> ()</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/iterator-range">iterator_range</a>&lt; <a href="#a3f43e04d827b07cf1d5366554d03f748">const_succ_iterator</a> &gt;</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#acce99554f41c0ba0f161102672722e4c">successors</a> () const</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">void</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#acce9c12cc977a88dc7bc51493ce7681c">addLiveIn</a> (MCRegister PhysReg, LaneBitmask LaneMask=LaneBitmask::getAll())</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Adds the specified register as a live in. <a href="#acce9c12cc977a88dc7bc51493ce7681c">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">void</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a9c42510477e83303466bdd92ff333eec">addLiveIn</a> (const RegisterMaskPair &amp;RegMaskPair)</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">void</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a9ff557f73ac8f2608369d70b3c73e525">sortUniqueLiveIns</a> ()</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Sorts and uniques the LiveIns vector. <a href="#a9ff557f73ac8f2608369d70b3c73e525">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">void</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a7c9de323398db302bf33de488a780467">clearLiveIns</a> ()</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Clear live in list. <a href="#a7c9de323398db302bf33de488a780467">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">void</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a02bae4956974c41a4bad6b95f5d7cc1a">clearLiveIns</a> (std::vector&lt; RegisterMaskPair &gt; &amp;OldLiveIns)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Clear the live in list, and return the removed live in's in <span class="doxyComputerOutput">OldLiveIns</span>. <a href="#a02bae4956974c41a4bad6b95f5d7cc1a">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/register">Register</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a9bd7c04e374ad15665430a243dd30d80">addLiveIn</a> (MCRegister PhysReg, const TargetRegisterClass *RC)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Add PhysReg as live in to this block, and ensure that there is a copy of PhysReg to a virtual register of class RC. <a href="#a9bd7c04e374ad15665430a243dd30d80">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">void</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a668e2f48294f63416c8f28072e531c33">removeLiveIn</a> (MCRegister Reg, LaneBitmask LaneMask=LaneBitmask::getAll())</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Remove the specified register from the live in set. <a href="#a668e2f48294f63416c8f28072e531c33">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">bool</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#af9745f59d6647bd43f9f7959ca1a9971">isLiveIn</a> (MCRegister Reg, LaneBitmask LaneMask=LaneBitmask::getAll()) const</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Return true if the specified register is in the live in set. <a href="#af9745f59d6647bd43f9f7959ca1a9971">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="#a787c857539b04a8552aec72d561a3ca2">livein_iterator</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ab01e076c631849cba69494483703600a">livein_begin_dbg</a> () const</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Unlike livein_begin, this method does not check that the liveness information is accurate. <a href="#ab01e076c631849cba69494483703600a">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/iterator-range">iterator_range</a>&lt; <a href="#a787c857539b04a8552aec72d561a3ca2">livein_iterator</a> &gt;</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a84496a274487670f481ebaaa787149f6">liveins_dbg</a> () const</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="#a787c857539b04a8552aec72d561a3ca2">livein_iterator</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a81335545907243d4dea1a276f01566c0">livein_begin</a> () const</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="#a787c857539b04a8552aec72d561a3ca2">livein_iterator</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a0e76d75564a8460bd9f2822f7ad49b1f">livein_end</a> () const</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a64e73d869f06f711fb3d5b2c07dfc7be">livein_empty</a> () const</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/iterator-range">iterator_range</a>&lt; <a href="#a787c857539b04a8552aec72d561a3ca2">livein_iterator</a> &gt;</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a364ed6e68f92f797c0cd9e53ce5ea2a5">liveins</a> () const</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="#a787c857539b04a8552aec72d561a3ca2">livein_iterator</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ac3c75602432ab98a011f0a469ebdc5c2">removeLiveIn</a> (livein_iterator I)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Remove entry from the livein set and return iterator to the next. <a href="#ac3c75602432ab98a011f0a469ebdc5c2">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> std::vector&lt; <a href="/web-llvm/docs/api/structs/llvm/machinebasicblock/registermaskpair">RegisterMaskPair</a> &gt; &amp;</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a8012fc1639ba1cd1f3966ccca165d2af">getLiveIns</a> () const</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/machinebasicblock/liveout-iterator">liveout_iterator</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#aa13f60350a3e19e1791fd628b694da36">liveout_begin</a> () const</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Iterator scanning successor basic blocks' liveins to determine the registers potentially live at the end of this block. <a href="#aa13f60350a3e19e1791fd628b694da36">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/machinebasicblock/liveout-iterator">liveout_iterator</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a4fcb7c9dcf957be63eb03d4a7b8b0cd9">liveout_end</a> () const</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/iterator-range">iterator_range</a>&lt; <a href="/web-llvm/docs/api/classes/llvm/machinebasicblock/liveout-iterator">liveout_iterator</a> &gt;</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a114e4a8fc84200c5f3d4d02ecb366dd5">liveouts</a> () const</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> uint32_t *</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a864dfd605ab4c40b895d035a165a873b">getBeginClobberMask</a> (const TargetRegisterInfo *TRI) const</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Get the clobber mask for the start of this basic block. <a href="#a864dfd605ab4c40b895d035a165a873b">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> uint32_t *</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#af80cc22ae7f226a8c819be6bf9e731d4">getEndClobberMask</a> (const TargetRegisterInfo *TRI) const</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Get the clobber mask for the end of the basic block. <a href="#af80cc22ae7f226a8c819be6bf9e731d4">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/structs/llvm/align">Align</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ae13575403de0e7d005f1b5905053f3ea">getAlignment</a> () const</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Return alignment of the basic block. <a href="#ae13575403de0e7d005f1b5905053f3ea">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">void</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a8cb665c210dc8e43f537cf4c9b84e2c7">setAlignment</a> (Align A)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Set alignment of the basic block. <a href="#a8cb665c210dc8e43f537cf4c9b84e2c7">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">void</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a36652c385717d0111378ed12b65dbb75">setAlignment</a> (Align A, unsigned MaxBytes)</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">unsigned</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a6e25c9cf835390ac9c23abb4cf70d4eb">getMaxBytesForAlignment</a> () const</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Return the maximum amount of padding allowed for aligning the basic block. <a href="#a6e25c9cf835390ac9c23abb4cf70d4eb">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">void</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a6e758ce47fe7d9b66e9accb1b8418e43">setMaxBytesForAlignment</a> (unsigned MaxBytes)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Set the maximum amount of padding allowed for aligning the basic block. <a href="#a6e758ce47fe7d9b66e9accb1b8418e43">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">bool</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a1100bfbadd996d464150c6a68fa8dc1d">isEHPad</a> () const</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Returns true if the block is a landing pad. <a href="#a1100bfbadd996d464150c6a68fa8dc1d">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">void</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#afcc0e4bdd74c918624da8eea761a0ef9">setIsEHPad</a> (bool V=true)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Indicates the block is a landing pad. <a href="#afcc0e4bdd74c918624da8eea761a0ef9">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">bool</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a07ccfc69389d4e9657d22698f4a7ef46">hasEHPadSuccessor</a> () const</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a9103c1c7b60d793b0efd41c741286508">isEntryBlock</a> () const</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Returns true if this is the entry block of the function. <a href="#a9103c1c7b60d793b0efd41c741286508">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">bool</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a8d7d10ec1863b6601b83523da37401e6">isEHScopeEntry</a> () const</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Returns true if this is the entry block of an EH scope, i.e., the block that used to have a catchpad or cleanuppad instruction in the LLVM IR. <a href="#a8d7d10ec1863b6601b83523da37401e6">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">void</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#af296bb7eb6fea94d49bfbc434cf3bf3c">setIsEHScopeEntry</a> (bool V=true)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Indicates if this is the entry block of an EH scope, i.e., the block that that used to have a catchpad or cleanuppad instruction in the LLVM IR. <a href="#af296bb7eb6fea94d49bfbc434cf3bf3c">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">bool</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a9f5f0a44387ca86786022bf55c3cb41e">isEHCatchretTarget</a> () const</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Returns true if this is a target block of a catchret. <a href="#a9f5f0a44387ca86786022bf55c3cb41e">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">void</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a148fa7c12ad7679341d884e0f8295d39">setIsEHCatchretTarget</a> (bool V=true)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Indicates if this is a target block of a catchret. <a href="#a148fa7c12ad7679341d884e0f8295d39">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">bool</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a7d2f8efd82042b4cf611ba10e9e79ed0">isEHFuncletEntry</a> () const</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Returns true if this is the entry block of an EH funclet. <a href="#a7d2f8efd82042b4cf611ba10e9e79ed0">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">void</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ad6a02ab1681cddfb6a5991ad2a5fff88">setIsEHFuncletEntry</a> (bool V=true)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Indicates if this is the entry block of an EH funclet. <a href="#ad6a02ab1681cddfb6a5991ad2a5fff88">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">bool</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#afe9ba3711c6b7625da1425cc0a7b3f10">isCleanupFuncletEntry</a> () const</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Returns true if this is the entry block of a cleanup funclet. <a href="#afe9ba3711c6b7625da1425cc0a7b3f10">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">void</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a1e199d04a33af3daf0b9c29c6b0d83f0">setIsCleanupFuncletEntry</a> (bool V=true)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Indicates if this is the entry block of a cleanup funclet. <a href="#a1e199d04a33af3daf0b9c29c6b0d83f0">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">bool</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ad4835355c1e5ca306abd15f5b90bd9b4">isBeginSection</a> () const</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Returns true if this block begins any section. <a href="#ad4835355c1e5ca306abd15f5b90bd9b4">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">bool</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ae0fd0a5397ceb88bd0d58ecb1708e1dc">isEndSection</a> () const</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Returns true if this block ends any section. <a href="#ae0fd0a5397ceb88bd0d58ecb1708e1dc">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">void</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#af8228a164de284cac5db790f0377031b">setIsBeginSection</a> (bool V=true)</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">void</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a17f6a7634e1ea3b0fbaf1de07e000818">setIsEndSection</a> (bool V=true)</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">std::optional&lt; <a href="/web-llvm/docs/api/structs/llvm/uniquebbid">UniqueBBID</a> &gt;</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a45a5042aa51fc28cccaba7a95ec9746c">getBBID</a> () const</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/structs/llvm/mbbsectionid">MBBSectionID</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a87ee39ccabd6fa5abe6302ebffd768c9">getSectionID</a> () const</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Returns the section <a href="/web-llvm/docs/api/namespaces/llvm/callingconv/#abdf8cf606905c10634e831390981b0ed">ID</a> of this basic block. <a href="#a87ee39ccabd6fa5abe6302ebffd768c9">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">void</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a088df0647ac6dd7fc843b2d2f7126327">setBBID</a> (const UniqueBBID &amp;V)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Sets the fixed BBID of this basic block. <a href="#a088df0647ac6dd7fc843b2d2f7126327">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">void</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#aac864a2ce4f4fcac4c21062b29986c5c">setSectionID</a> (MBBSectionID V)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Sets the section <a href="/web-llvm/docs/api/namespaces/llvm/callingconv/#abdf8cf606905c10634e831390981b0ed">ID</a> for this basic block. <a href="#aac864a2ce4f4fcac4c21062b29986c5c">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/mcsymbol">MCSymbol</a> *</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a78b12ba4209266f4d26fa513c576ee18">getEndSymbol</a> () const</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Returns the <a href="/web-llvm/docs/api/classes/llvm/mcsymbol">MCSymbol</a> marking the end of this basic block. <a href="#a78b12ba4209266f4d26fa513c576ee18">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">bool</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#aefb323794dab5bb00d738a3f32dd65e6">mayHaveInlineAsmBr</a> () const</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Returns true if this block may have an INLINEASM_BR (overestimate, by checking if any of the successors are indirect targets of any inlineasm_br in the function). <a href="#aefb323794dab5bb00d738a3f32dd65e6">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">bool</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a00e55a6b6b44b739e9da1d62f1d8a5b3">isInlineAsmBrIndirectTarget</a> () const</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Returns true if this is the indirect dest of an INLINEASM_BR. <a href="#a00e55a6b6b44b739e9da1d62f1d8a5b3">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">void</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ac9e8a1eeb039aaa25962721ca718de49">setIsInlineAsmBrIndirectTarget</a> (bool V=true)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Indicates if this is the indirect dest of an INLINEASM_BR. <a href="#ac9e8a1eeb039aaa25962721ca718de49">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">bool</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ae37b6ccdd5b2bdd9bc53dc0b634e3f7f">isLegalToHoistInto</a> () const</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Returns true if it is legal to hoist instructions into this block. <a href="#ae37b6ccdd5b2bdd9bc53dc0b634e3f7f">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">void</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a25c2a6ee39d0d97dac2184e8bd942300">moveBefore</a> (MachineBasicBlock *NewAfter)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Move 'this' block before or after the specified block. <a href="#a25c2a6ee39d0d97dac2184e8bd942300">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">void</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#af3c2dc75190645b72eee3c416cd14885">moveAfter</a> (MachineBasicBlock *NewBefore)</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a7feb92c592c0f5bd6cbe88c5fbaa91f4">sameSection</a> (const MachineBasicBlock *MBB) const</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Returns true if this and MBB belong to the same section. <a href="#a7feb92c592c0f5bd6cbe88c5fbaa91f4">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">void</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a5803a49facae20ca4b002dcba6f1d03e">updateTerminator</a> (MachineBasicBlock *PreviousLayoutSuccessor)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Update the terminator instructions in block to account for changes to block layout which may have been made. <a href="#a5803a49facae20ca4b002dcba6f1d03e">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">void</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a935e2a8884592189d8f261634a0b24c5">addSuccessor</a> (MachineBasicBlock *Succ, BranchProbability Prob=BranchProbability::getUnknown())</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Add Succ as a successor of this <a href="/web-llvm/docs/api/classes/llvm/machinebasicblock">MachineBasicBlock</a>. <a href="#a935e2a8884592189d8f261634a0b24c5">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">void</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a3f3061829632220504bb4a1cb819cfac">addSuccessorWithoutProb</a> (MachineBasicBlock *Succ)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Add Succ as a successor of this <a href="/web-llvm/docs/api/classes/llvm/machinebasicblock">MachineBasicBlock</a>. <a href="#a3f3061829632220504bb4a1cb819cfac">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">void</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a6171d209616c58347dea44a49d7675c0">setSuccProbability</a> (succ_iterator I, BranchProbability Prob)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Set successor probability of a given iterator. <a href="#a6171d209616c58347dea44a49d7675c0">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">void</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a0c54da24de983d197068425e718fb607">normalizeSuccProbs</a> ()</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Normalize probabilities of all successors so that the sum of them becomes one. <a href="#a0c54da24de983d197068425e718fb607">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">void</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a6f0fb45670739e2756c1e41ce22c457b">validateSuccProbs</a> () const</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Validate successors' probabilities and check if the sum of them is approximate one. <a href="#a6f0fb45670739e2756c1e41ce22c457b">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">void</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#aa7114bb360b922025e7a4fec442676db">removeSuccessor</a> (MachineBasicBlock *Succ, bool NormalizeSuccProbs=false)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Remove successor from the successors list of this <a href="/web-llvm/docs/api/classes/llvm/machinebasicblock">MachineBasicBlock</a>. <a href="#aa7114bb360b922025e7a4fec442676db">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="#a9936e11d7a6149f7cac8fa32a81dd488">succ_iterator</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a29a36aca5cf01600bc3f403aaa2f2467">removeSuccessor</a> (succ_iterator I, bool NormalizeSuccProbs=false)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Remove specified successor from the successors list of this <a href="/web-llvm/docs/api/classes/llvm/machinebasicblock">MachineBasicBlock</a>. <a href="#a29a36aca5cf01600bc3f403aaa2f2467">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">void</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a2d4703c258359175d1c7840735bd77b6">replaceSuccessor</a> (MachineBasicBlock *Old, MachineBasicBlock *New)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Replace successor OLD with NEW and update probability info. <a href="#a2d4703c258359175d1c7840735bd77b6">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">void</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a95933492048f0ea830f02f61b1329c12">copySuccessor</a> (const MachineBasicBlock *Orig, succ_iterator I)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Copy a successor (and any probability info) from original block to this block's. <a href="#a95933492048f0ea830f02f61b1329c12">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">void</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a4b43b969b3db9fc943b664738f62ca76">splitSuccessor</a> (MachineBasicBlock *Old, MachineBasicBlock *New, bool NormalizeSuccProbs=false)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Split the old successor into old plus new and updates the probability info. <a href="#a4b43b969b3db9fc943b664738f62ca76">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">void</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a31e57b158a17c459f0dc34b0e602ecc6">transferSuccessors</a> (MachineBasicBlock *FromMBB)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Transfers all the successors from MBB to this machine basic block (i.e., copies all the successors FromMBB and remove all the successors from FromMBB). <a href="#a31e57b158a17c459f0dc34b0e602ecc6">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">void</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a046a35e36c4c1206711ea82ee9cb6d72">transferSuccessorsAndUpdatePHIs</a> (MachineBasicBlock *FromMBB)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Transfers all the successors, as in transferSuccessors, and update PHI operands in the successor blocks which refer to FromMBB to refer to this. <a href="#a046a35e36c4c1206711ea82ee9cb6d72">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">bool</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#aabd086dcf9e2397dc4d228b6b7d8c40f">hasSuccessorProbabilities</a> () const</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Return true if any of the successors have probabilities attached to them. <a href="#aabd086dcf9e2397dc4d228b6b7d8c40f">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">bool</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#aaa71c733e5aa6113e60a3a806e01bb10">isPredecessor</a> (const MachineBasicBlock *MBB) const</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Return true if the specified MBB is a predecessor of this block. <a href="#aaa71c733e5aa6113e60a3a806e01bb10">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">bool</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#adc8f1be4a77ae671ac139d5f06b44deb">isSuccessor</a> (const MachineBasicBlock *MBB) const</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Return true if the specified MBB is a successor of this block. <a href="#adc8f1be4a77ae671ac139d5f06b44deb">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">bool</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#abd85c9d7c51eb515a550069e9ad9445e">isLayoutSuccessor</a> (const MachineBasicBlock *MBB) const</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Return true if the specified MBB will be emitted immediately after this block, such that if this block exits by falling through, control will transfer to the specified MBB. <a href="#abd85c9d7c51eb515a550069e9ad9445e">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/machinebasicblock">MachineBasicBlock</a> *</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#aa0a5ac19256656534bea2daabdfb947b">getSingleSuccessor</a> () const</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Return the successor of this block if it has a single successor. <a href="#aa0a5ac19256656534bea2daabdfb947b">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/machinebasicblock">MachineBasicBlock</a> *</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a9dd1a68709ac7641bf56ad6afaad6b4c">getSingleSuccessor</a> ()</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/machinebasicblock">MachineBasicBlock</a> *</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a5bfe9045e7f0a89622211264b32ff155">getSinglePredecessor</a> () const</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Return the predecessor of this block if it has a single predecessor. <a href="#a5bfe9045e7f0a89622211264b32ff155">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/machinebasicblock">MachineBasicBlock</a> *</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a4337bbedd6474d24a404573fd8880410">getSinglePredecessor</a> ()</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/machinebasicblock">MachineBasicBlock</a> *</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a31aa2680ec79198a4c94f35b3a1ad97e">getFallThrough</a> (bool JumpToFallThrough=true)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Return the fallthrough block if the block can implicitly transfer control to the block after it by falling off the end of it. <a href="#a31aa2680ec79198a4c94f35b3a1ad97e">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/machinebasicblock">MachineBasicBlock</a> *</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a1b9a057d53df3e20a0618572be3802f5">getLogicalFallThrough</a> ()</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Return the fallthrough block if the block can implicitly transfer control to it's successor, whether by a branch or a fallthrough. <a href="#a1b9a057d53df3e20a0618572be3802f5">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">bool</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a5ffb77c69d69a5beff906caaecfd7be4">canFallThrough</a> ()</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Return true if the block can implicitly transfer control to the block after it by falling off the end of it. <a href="#a5ffb77c69d69a5beff906caaecfd7be4">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="#ae34c996b58df9b9ce6695a0c8b70c533">iterator</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#aa7dc7faaab4856b8f0014b8283e26c7b">getFirstNonPHI</a> ()</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Returns a pointer to the first instruction in this block that is not a <a href="/web-llvm/docs/api/classes/llvm/phinode">PHINode</a> instruction. <a href="#aa7dc7faaab4856b8f0014b8283e26c7b">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="#a199a6e4bfdffc8f3379ef4f35004488f">const_iterator</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a9fc9c00548565617b77dc29112199269">getFirstNonPHI</a> () const</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="#ae34c996b58df9b9ce6695a0c8b70c533">iterator</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a3be7d94076d328797ab57ce09cefab33">SkipPHIsAndLabels</a> (iterator I)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Return the first instruction in MBB after I that is not a PHI or a label. <a href="#a3be7d94076d328797ab57ce09cefab33">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="#ae34c996b58df9b9ce6695a0c8b70c533">iterator</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a5d8a45757c9861d499cba1a0d54e2c1e">SkipPHIsLabelsAndDebug</a> (iterator I, Register Reg=Register(), bool SkipPseudoOp=true)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Return the first instruction in MBB after I that is not a PHI, label or debug. <a href="#a5d8a45757c9861d499cba1a0d54e2c1e">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="#ae34c996b58df9b9ce6695a0c8b70c533">iterator</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a7f0521fa2de44271fd4b909ea7351ef3">getFirstTerminator</a> ()</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Returns an iterator to the first terminator instruction of this basic block. <a href="#a7f0521fa2de44271fd4b909ea7351ef3">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="#a199a6e4bfdffc8f3379ef4f35004488f">const_iterator</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#acd8ed715d1519a082b42e4ecf0d22320">getFirstTerminator</a> () const</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="#ab6395548cae73865213e279ae461db54">instr_iterator</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ad8c65b86ef286331d408a7a74c7b0b2f">getFirstInstrTerminator</a> ()</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Same getFirstTerminator but it ignores bundles and return an <a href="#ab6395548cae73865213e279ae461db54">instr_iterator</a> instead. <a href="#ad8c65b86ef286331d408a7a74c7b0b2f">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="#ae34c996b58df9b9ce6695a0c8b70c533">iterator</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a0fab3e644b3457f90ed7f64876a037d2">getFirstTerminatorForward</a> ()</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Finds the first terminator in a block by scanning forward. <a href="#a0fab3e644b3457f90ed7f64876a037d2">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="#ae34c996b58df9b9ce6695a0c8b70c533">iterator</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a62b5d2211c09378c471307293453d780">getFirstNonDebugInstr</a> (bool SkipPseudoOp=true)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Returns an iterator to the first non-debug instruction in the basic block, or <a href="#acbc921830578e2741be6549db716c0ce">end()</a>. <a href="#a62b5d2211c09378c471307293453d780">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="#a199a6e4bfdffc8f3379ef4f35004488f">const_iterator</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a33633113f9128fa0c2b8543c6b1703f6">getFirstNonDebugInstr</a> (bool SkipPseudoOp=true) const</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="#ae34c996b58df9b9ce6695a0c8b70c533">iterator</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ab8d7b8ff6803133d567fd4240e6364ce">getLastNonDebugInstr</a> (bool SkipPseudoOp=true)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Returns an iterator to the last non-debug instruction in the basic block, or <a href="#acbc921830578e2741be6549db716c0ce">end()</a>. <a href="#ab8d7b8ff6803133d567fd4240e6364ce">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="#a199a6e4bfdffc8f3379ef4f35004488f">const_iterator</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a7e284f7329497d8ffc3bd7fab1402cac">getLastNonDebugInstr</a> (bool SkipPseudoOp=true) const</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a82f5d244972c88ff03ee56d6c090ac70">isReturnBlock</a> () const</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Convenience function that returns true if the block ends in a return instruction. <a href="#a82f5d244972c88ff03ee56d6c090ac70">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">bool</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#adf1c64c05c8afb975b979543f8f850df">isEHScopeReturnBlock</a> () const</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Convenience function that returns true if the bock ends in a EH scope return instruction. <a href="#adf1c64c05c8afb975b979543f8f850df">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/machinebasicblock">MachineBasicBlock</a> *</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ac0bfa894f538166cb476b439a2cb0aea">splitAt</a> (MachineInstr &amp;SplitInst, bool UpdateLiveIns=true, LiveIntervals *LIS=nullptr)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Split a basic block into 2 pieces at <span class="doxyComputerOutput">SplitPoint</span>. <a href="#ac0bfa894f538166cb476b439a2cb0aea">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/machinebasicblock">MachineBasicBlock</a> *</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a324e3327b26396f39229654c107601d8">SplitCriticalEdge</a> (MachineBasicBlock *Succ, Pass &amp;P, std::vector&lt; SparseBitVector&lt;&gt; &gt; *LiveInSets=nullptr, MachineDomTreeUpdater *MDTU=nullptr)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Split the critical edge from this block to the given successor block, and return the newly created block, or null if splitting is not possible. <a href="#a324e3327b26396f39229654c107601d8">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/machinebasicblock">MachineBasicBlock</a> *</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a9cf5c21c2ef38624a3ee3a12d21e76f0">SplitCriticalEdge</a> (MachineBasicBlock *Succ, MachineFunctionAnalysisManager &amp;MFAM, std::vector&lt; SparseBitVector&lt;&gt; &gt; *LiveInSets=nullptr, MachineDomTreeUpdater *MDTU=nullptr)</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/machinebasicblock">MachineBasicBlock</a> *</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#aa80aaa82844ab5560ece045eee7b34ac">SplitCriticalEdge</a> (MachineBasicBlock *Succ, Pass *P, MachineFunctionAnalysisManager *MFAM, std::vector&lt; SparseBitVector&lt;&gt; &gt; *LiveInSets, MachineDomTreeUpdater *MDTU)</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ae32dc74389a52cbb83e6a016274142f5">canSplitCriticalEdge</a> (const MachineBasicBlock *Succ) const</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p><a href="/web-llvm/docs/api/namespaces/llvm/check">Check</a> if the edge between this block and the given successor <span class="doxyComputerOutput">Succ</span>, can be split. <a href="#ae32dc74389a52cbb83e6a016274142f5">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">void</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#af9247e8f4d910743041faf53a5255ea6">pop_front</a> ()</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">void</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a1056a82d0f5c741ea09c49be8673156a">pop_back</a> ()</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">void</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a3b1dce1f3354a357fb9061bb7568a84e">push_back</a> (MachineInstr *MI)</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="#ab6395548cae73865213e279ae461db54">instr_iterator</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a3435a2381e60e842e915f85c931b7dde">insert</a> (instr_iterator I, MachineInstr *M)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Insert MI into the instruction list before I, possibly inside a bundle. <a href="#a3435a2381e60e842e915f85c931b7dde">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexTemplate">
<td class="doxyMemberIndexTemplate" colspan="2"><div>template &lt;typename IT&gt;</div></td>
</tr>
<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemTypeTemplate" align="left" valign="top">void</td>
<td class="doxyMemberIndexItemNameTemplate" align="left" valign="top"><a href="#afc15ef658764e1532ae80037d5d6ba6d">insert</a> (iterator I, IT S, IT E)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Insert a range of instructions into the instruction list before I. <a href="#afc15ef658764e1532ae80037d5d6ba6d">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="#ae34c996b58df9b9ce6695a0c8b70c533">iterator</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a80512774162f8a8d15bd6e3b6739cf9b">insert</a> (iterator I, MachineInstr *MI)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Insert MI into the instruction list before I. <a href="#a80512774162f8a8d15bd6e3b6739cf9b">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="#ae34c996b58df9b9ce6695a0c8b70c533">iterator</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#adbcec9820951b0e3872c94cbd4e57c80">insertAfter</a> (iterator I, MachineInstr *MI)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Insert MI into the instruction list after I. <a href="#adbcec9820951b0e3872c94cbd4e57c80">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="#ab6395548cae73865213e279ae461db54">instr_iterator</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#aec460b7ed48d97ed84ae2466b498763f">insertAfterBundle</a> (instr_iterator I, MachineInstr *MI)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>If I is bundled then insert MI into the instruction list after the end of the bundle, otherwise insert MI immediately after I. <a href="#aec460b7ed48d97ed84ae2466b498763f">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="#ab6395548cae73865213e279ae461db54">instr_iterator</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ad26bff839257f220557ce812b2159c72">erase</a> (instr_iterator I)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Remove an instruction from the instruction list and delete it. <a href="#ad26bff839257f220557ce812b2159c72">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="#ab6395548cae73865213e279ae461db54">instr_iterator</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a3a892dcf265c384644ffac47d97b7e53">erase_instr</a> (MachineInstr *I)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Remove an instruction from the instruction list and delete it. <a href="#a3a892dcf265c384644ffac47d97b7e53">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="#ae34c996b58df9b9ce6695a0c8b70c533">iterator</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a6707fe3d50909e1409802995d5829c72">erase</a> (iterator I, iterator E)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Remove a range of instructions from the instruction list and delete them. <a href="#a6707fe3d50909e1409802995d5829c72">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="#ae34c996b58df9b9ce6695a0c8b70c533">iterator</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#aeb9c4dcc4993b06ce44b8d5ae1c7702b">erase</a> (iterator I)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Remove an instruction or bundle from the instruction list and delete it. <a href="#aeb9c4dcc4993b06ce44b8d5ae1c7702b">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="#ae34c996b58df9b9ce6695a0c8b70c533">iterator</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a0c194a99e410c07d2e694d4c802de0ab">erase</a> (MachineInstr *I)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Remove an instruction from the instruction list and delete it. <a href="#a0c194a99e410c07d2e694d4c802de0ab">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/machineinstr">MachineInstr</a> *</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a6a77acab2477f9eaf0de232a1d94ff3d">remove</a> (MachineInstr *I)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Remove the unbundled instruction from the instruction list without deleting it. <a href="#a6a77acab2477f9eaf0de232a1d94ff3d">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/machineinstr">MachineInstr</a> *</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a1590a6d5d0f6d95dda90f2cf8954f3fb">remove_instr</a> (MachineInstr *I)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Remove the possibly bundled instruction from the instruction list without deleting it. <a href="#a1590a6d5d0f6d95dda90f2cf8954f3fb">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">void</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a2be0839c1c2ac22d7c65f8a175105959">clear</a> ()</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">void</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#adf0023bdc4f05a7849c35b1c859580d8">splice</a> (iterator Where, MachineBasicBlock *Other, iterator From)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Take an instruction from MBB 'Other' at the position From, and insert it into this MBB right before 'Where'. <a href="#adf0023bdc4f05a7849c35b1c859580d8">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">void</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a78fb611836599b6138ba072712dcc315">splice</a> (iterator Where, MachineBasicBlock *Other, iterator From, iterator To)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Take a block of instructions from MBB 'Other' in the range [From, To), and insert them into this MBB right before 'Where'. <a href="#a78fb611836599b6138ba072712dcc315">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/machinebasicblock">MachineBasicBlock</a> *</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#af99e842f9d7eeea463d1d8f0bd34a0d0">removeFromParent</a> ()</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>This method unlinks 'this' from the containing function, and returns it, but does not delete it. <a href="#af99e842f9d7eeea463d1d8f0bd34a0d0">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">void</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ac421fe6513e43aedbba712e4a981744e">eraseFromParent</a> ()</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>This method unlinks 'this' from the containing function and deletes it. <a href="#ac421fe6513e43aedbba712e4a981744e">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">void</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ab9a54fdc7456ee97cb54ff30d625b6b7">ReplaceUsesOfBlockWith</a> (MachineBasicBlock *Old, MachineBasicBlock *New)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Given a machine basic block that branched to 'Old', change the code and CFG so that it branches to 'New' instead. <a href="#ab9a54fdc7456ee97cb54ff30d625b6b7">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">void</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a134a21189d056b81b80d0cdf01ef8c46">replacePhiUsesWith</a> (MachineBasicBlock *Old, MachineBasicBlock *New)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Update all phi nodes in this basic block to refer to basic block <span class="doxyComputerOutput">New</span> instead of basic block <span class="doxyComputerOutput">Old</span>. <a href="#a134a21189d056b81b80d0cdf01ef8c46">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/debugloc">DebugLoc</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ab622d694b5fcb0edb99159f1ebdcdb6b">findDebugLoc</a> (instr_iterator MBBI)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Find the next valid <a href="/web-llvm/docs/api/classes/llvm/debugloc">DebugLoc</a> starting at MBBI, skipping any debug instructions. <a href="#ab622d694b5fcb0edb99159f1ebdcdb6b">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/debugloc">DebugLoc</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#aa2e30b8dd8b4aecfff7f7f5bfa90cff2">findDebugLoc</a> (iterator MBBI)</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/debugloc">DebugLoc</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ab2192a3dc7e43ace4706a00258bf5f47">rfindDebugLoc</a> (reverse_instr_iterator MBBI)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Has exact same behavior as <a href="#ab622d694b5fcb0edb99159f1ebdcdb6b">findDebugLoc</a> (it also searches towards the end of this MBB) except that this function takes a reverse iterator to identify the starting MI. <a href="#ab2192a3dc7e43ace4706a00258bf5f47">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/debugloc">DebugLoc</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a64a742bb4380d11a9b4c23c5c2794c79">rfindDebugLoc</a> (reverse_iterator MBBI)</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/debugloc">DebugLoc</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#abfe76200d04557c617e5f505717c3ad3">findPrevDebugLoc</a> (instr_iterator MBBI)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Find the previous valid <a href="/web-llvm/docs/api/classes/llvm/debugloc">DebugLoc</a> preceding MBBI, skipping any debug instructions. <a href="#abfe76200d04557c617e5f505717c3ad3">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/debugloc">DebugLoc</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ad4aa6f6ff5e863a2e26dc79531ff56d5">findPrevDebugLoc</a> (iterator MBBI)</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/debugloc">DebugLoc</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a01356cc615c2222dba3e1b2776800add">rfindPrevDebugLoc</a> (reverse_instr_iterator MBBI)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Has exact same behavior as <a href="#abfe76200d04557c617e5f505717c3ad3">findPrevDebugLoc</a> (it also searches towards the beginning of this MBB) except that this function takes reverse iterator to identify the starting MI. <a href="#a01356cc615c2222dba3e1b2776800add">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/debugloc">DebugLoc</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a20495533e294b68b1f9487ceee026459">rfindPrevDebugLoc</a> (reverse_iterator MBBI)</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/debugloc">DebugLoc</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ad81901d0d8b768b240e78bf357999f34">findBranchDebugLoc</a> ()</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Find and return the merged <a href="/web-llvm/docs/api/classes/llvm/debugloc">DebugLoc</a> of the branch instructions of the block. <a href="#ad81901d0d8b768b240e78bf357999f34">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="#af0288e181965a5ff9f0c7a75201fd142">LivenessQueryResult</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a7ebfe0cc2f78ae5f27e1944412606973">computeRegisterLiveness</a> (const TargetRegisterInfo *TRI, MCRegister Reg, const_iterator Before, unsigned Neighborhood=10) const</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Return whether (physical) register <span class="doxyComputerOutput">Reg</span> has been defined and not killed as of just before <span class="doxyComputerOutput">Before</span>. <a href="#a7ebfe0cc2f78ae5f27e1944412606973">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">void</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a8cec41e65c7ebf7da3e9d41f2317065e">dump</a> () const</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">void</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ab3b62258d9bd41595674de878f37f8d8">print</a> (raw_ostream &amp;OS, const SlotIndexes *=nullptr, bool IsStandalone=true) const</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">void</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a5a4302f4590a281bb84e08b30c80591c">print</a> (raw_ostream &amp;OS, ModuleSlotTracker &amp;MST, const SlotIndexes *=nullptr, bool IsStandalone=true) const</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">void</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#adad68dd11c1995cc4f63e51986f50ce0">printName</a> (raw_ostream &amp;os, unsigned printNameFlags=PrintNameIr, ModuleSlotTracker *moduleSlotTracker=nullptr) const</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Print the basic block's name as: <a href="#adad68dd11c1995cc4f63e51986f50ce0">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">void</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a691794b4391537d134a8b2afbd21f8cb">printAsOperand</a> (raw_ostream &amp;OS, bool PrintType=true) const</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">int</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a3aa22d521bd6a7e6b9f35545dc7b0f1e">getNumber</a> () const</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>MachineBasicBlocks are uniquely numbered at the function level, unless they're not in a <a href="/web-llvm/docs/api/classes/llvm/machinefunction">MachineFunction</a> yet, in which case this will return -1. <a href="#a3aa22d521bd6a7e6b9f35545dc7b0f1e">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">void</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a87d6a6ddceb28f49cb7c34727c989c0a">setNumber</a> (int N)</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">unsigned</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ad661835c7f2b51fb3c5d826e77eafb93">getCallFrameSize</a> () const</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Return the call frame size on entry to this basic block. <a href="#ad661835c7f2b51fb3c5d826e77eafb93">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">void</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a4472755d36621c5e2d056eec5056202e">setCallFrameSize</a> (unsigned N)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Set the call frame size on entry to this basic block. <a href="#a4472755d36621c5e2d056eec5056202e">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/mcsymbol">MCSymbol</a> *</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a1cc134bd22a318835dc929323da70ea4">getSymbol</a> () const</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Return the <a href="/web-llvm/docs/api/classes/llvm/mcsymbol">MCSymbol</a> for this basic block. <a href="#a1cc134bd22a318835dc929323da70ea4">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/mcsymbol">MCSymbol</a> *</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a210ccb5b83a717a8dce63cd7602a58b6">getEHCatchretSymbol</a> () const</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Return the EHCatchret Symbol for this basic block. <a href="#a210ccb5b83a717a8dce63cd7602a58b6">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">std::optional&lt; uint64_t &gt;</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#af45e6b009a9a5ec818e4ae303ab65cb1">getIrrLoopHeaderWeight</a> () const</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">void</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a19e7678bb3906783e58c80452147c3b5">setIrrLoopHeaderWeight</a> (uint64_t Weight)</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/branchprobability">BranchProbability</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a34b15764a81fb89e68d85d5aae76f20f">getSuccProbability</a> (const_succ_iterator Succ) const</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Return probability of the edge from this block to MBB. <a href="#a34b15764a81fb89e68d85d5aae76f20f">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

</table>

## Private Member Functions Index

<table class="doxyMembersIndex">

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">probability_iterator</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ae7e1d87fee532b477c249afd0735baa2">getProbabilityIterator</a> (succ_iterator I)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Return probability iterator corresponding to the I successor iterator. <a href="#ae7e1d87fee532b477c249afd0735baa2">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">const_probability_iterator</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a7f82f84156c54b819f8d571d039924f1">getProbabilityIterator</a> (const_succ_iterator I) const</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Return probability iterator corresonding to the I successor iterator. <a href="#a7f82f84156c54b819f8d571d039924f1">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">void</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ae604bff2bdb15779c0cf4fb842c05ac4">addPredecessor</a> (MachineBasicBlock *Pred)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Add Pred as a predecessor of this <a href="/web-llvm/docs/api/classes/llvm/machinebasicblock">MachineBasicBlock</a>. <a href="#ae604bff2bdb15779c0cf4fb842c05ac4">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">void</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a6cdb963bc7631186cc7272d8b5bd2e37">removePredecessor</a> (MachineBasicBlock *Pred)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Remove Pred as a predecessor of this <a href="/web-llvm/docs/api/classes/llvm/machinebasicblock">MachineBasicBlock</a>. <a href="#a6cdb963bc7631186cc7272d8b5bd2e37">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

</table>

## Private Member Attributes Index

<table class="doxyMembersIndex">

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/basicblock">BasicBlock</a> *</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a38abf622db4c408ea8676a8c847fce2f">BB</a></td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">int</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a6b4fada343ca9edcbc94cdf9a7b641c4">Number</a></td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">unsigned</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a9f521bdaf2449ac14f88acbd1b5f6696">CallFrameSize</a> = 0</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>The call frame size on entry to this basic block due to call frame setup instructions in a predecessor. <a href="#a9f521bdaf2449ac14f88acbd1b5f6696">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/machinefunction">MachineFunction</a> *</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a67d186c9f4dfdca3055fcc9c2c1b13d9">xParent</a></td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/iplist">Instructions</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a066f5919ac1fb05971aa19600004a5fc">Insts</a></td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/smallvector">SmallVector</a>&lt; <a href="/web-llvm/docs/api/classes/llvm/machinebasicblock">MachineBasicBlock</a> *, 4 &gt;</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a0693ebc2b695da6ee922ec058ad0e4ea">Predecessors</a></td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Keep track of the predecessor / successor basic blocks. <a href="#a0693ebc2b695da6ee922ec058ad0e4ea">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/smallvector">SmallVector</a>&lt; <a href="/web-llvm/docs/api/classes/llvm/machinebasicblock">MachineBasicBlock</a> *, 2 &gt;</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a5b671c7ad91bd7d5a938d0a19b577904">Successors</a></td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">std::vector&lt; <a href="/web-llvm/docs/api/classes/llvm/branchprobability">BranchProbability</a> &gt;</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a952a6ef8310d3ef92f6b38f03b5ea28d">Probs</a></td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Keep track of the probabilities to the successors. <a href="#a952a6ef8310d3ef92f6b38f03b5ea28d">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">std::optional&lt; uint64_t &gt;</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ac1fb1cb844d0383b98c0c0acbc45fe13">IrrLoopHeaderWeight</a></td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">LiveInVector</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a11a99edc69f45edc2edd2014a3dacc40">LiveIns</a></td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/structs/llvm/align">Align</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a290845d0eb80824612933eb53c1b3c3c">Alignment</a></td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Alignment of the basic block. <a href="#a290845d0eb80824612933eb53c1b3c3c">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">unsigned</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a9b4b1df0aa33a43360c65b84c4753224">MaxBytesForAlignment</a> = 0</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Maximum amount of bytes that can be added to align the basic block. <a href="#a9b4b1df0aa33a43360c65b84c4753224">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">bool</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a9e544bc758c33bf4c1854b1a2a1af8df">IsEHPad</a> = false</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Indicate that this basic block is entered via an exception handler. <a href="#a9e544bc758c33bf4c1854b1a2a1af8df">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">bool</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a45f2b95a6636e94c1a9a99c455a5108f">MachineBlockAddressTaken</a> = false</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Indicate that this <a href="/web-llvm/docs/api/classes/llvm/machinebasicblock">MachineBasicBlock</a> is referenced somewhere other than as predecessor/successor, a terminator <a href="/web-llvm/docs/api/classes/llvm/machineinstr">MachineInstr</a>, or a jump table. <a href="#a45f2b95a6636e94c1a9a99c455a5108f">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/basicblock">BasicBlock</a> *</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a03ebe9212604114c3f50a27cdc208f8c">AddressTakenIRBlock</a> = nullptr</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>If this <a href="/web-llvm/docs/api/classes/llvm/machinebasicblock">MachineBasicBlock</a> corresponds to an IR-level "blockaddress" constant, this contains a pointer to that block. <a href="#a03ebe9212604114c3f50a27cdc208f8c">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">bool</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ac69b1d61d78e01506e276aa056b651f6">LabelMustBeEmitted</a> = false</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Indicate that this basic block needs its symbol be emitted regardless of whether the flow just falls-through to it. <a href="#ac69b1d61d78e01506e276aa056b651f6">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">bool</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#adadcc59c46cf7fa94a597cad0a4e9728">IsEHScopeEntry</a> = false</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Indicate that this basic block is the entry block of an EH scope, i.e., the block that used to have a catchpad or cleanuppad instruction in the LLVM IR. <a href="#adadcc59c46cf7fa94a597cad0a4e9728">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">bool</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a1660c6738d59ac46b917fd08f267662a">IsEHCatchretTarget</a> = false</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Indicates if this is a target block of a catchret. <a href="#a1660c6738d59ac46b917fd08f267662a">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">bool</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ae670ff8a9ccbc216ddd27e77f83b232d">IsEHFuncletEntry</a> = false</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Indicate that this basic block is the entry block of an EH funclet. <a href="#ae670ff8a9ccbc216ddd27e77f83b232d">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">bool</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a43c07b5ce650da5578f76f478b38aa2f">IsCleanupFuncletEntry</a> = false</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Indicate that this basic block is the entry block of a cleanup funclet. <a href="#a43c07b5ce650da5578f76f478b38aa2f">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">std::optional&lt; <a href="/web-llvm/docs/api/structs/llvm/uniquebbid">UniqueBBID</a> &gt;</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#af4970272a3e0bfce6f0004e2bc4b310b">BBID</a></td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Fixed unique <a href="/web-llvm/docs/api/namespaces/llvm/callingconv/#abdf8cf606905c10634e831390981b0ed">ID</a> assigned to this basic block upon creation. <a href="#af4970272a3e0bfce6f0004e2bc4b310b">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/structs/llvm/mbbsectionid">MBBSectionID</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a7ee82e7f2ea8408bbe6a52d3bfb0127b">SectionID</a> {0}</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>With basic block sections, this stores the Section <a href="/web-llvm/docs/api/namespaces/llvm/callingconv/#abdf8cf606905c10634e831390981b0ed">ID</a> of the basic block. <a href="#a7ee82e7f2ea8408bbe6a52d3bfb0127b">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">bool</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a06e13a2a32e34a07d37c41bdc31c3bbb">IsBeginSection</a> = false</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a27d120ff36e83bd2f88281195d3e5910">IsEndSection</a> = false</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ad47740cf90b7431b29394c0c22cbbc44">IsInlineAsmBrIndirectTarget</a> = false</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Indicate that this basic block is the indirect dest of an INLINEASM_BR. <a href="#ad47740cf90b7431b29394c0c22cbbc44">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/mcsymbol">MCSymbol</a> *</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a3bc40e61dab48b8202763e53f5004c6b">CachedMCSymbol</a> = nullptr</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>since getSymbol is a relatively heavy-weight operation, the symbol is only computed once and is cached. <a href="#a3bc40e61dab48b8202763e53f5004c6b">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/mcsymbol">MCSymbol</a> *</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a4a66640a51268476b55b0db690e6bb61">CachedEHCatchretMCSymbol</a> = nullptr</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Cached <a href="/web-llvm/docs/api/classes/llvm/mcsymbol">MCSymbol</a> for this block (used if IsEHCatchRetTarget). <a href="#a4a66640a51268476b55b0db690e6bb61">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/mcsymbol">MCSymbol</a> *</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a63f70ef9e743dd96169889251791eda3">CachedEndMCSymbol</a> = nullptr</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Marks the end of the basic block. <a href="#a63f70ef9e743dd96169889251791eda3">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

</table>

## Public Static Functions Index

<table class="doxyMembersIndex">

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">static <a href="/web-llvm/docs/api/classes/llvm/iplist">Instructions</a> MachineBasicBlock::*</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#abf04d174151ccf42258903385338a984">getSublistAccess</a> (MachineInstr *)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Support for <a href="/web-llvm/docs/api/classes/llvm/ilist-node-with-parent/#a62ee7ece4986606d41363bc1f70d5ab2">MachineInstr::getNextNode()</a>. <a href="#abf04d174151ccf42258903385338a984">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

</table>


<p>Definition at line 124 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/codegen/machinebasicblock-h">MachineBasicBlock.h</a>.</p>


<div class="doxySectionDef">

## Public Member Typedefs

### const\_instr\_iterator {#acc786576edf1d6a2697426143314bcef}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">using llvm::MachineBasicBlock::const_instr_iterator =  Instructions::const_iterator</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 324 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/codegen/machinebasicblock-h">MachineBasicBlock.h</a>.</p>

</div>
</div>

### const\_instr\_range {#a9140b0e73280574a820037cf0aa6adf3}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">using llvm::MachineBasicBlock::const_instr_range =  iterator_range&lt;const_instr_iterator&gt;</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 358 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/codegen/machinebasicblock-h">MachineBasicBlock.h</a>.</p>

</div>
</div>

### const\_iterator {#a199a6e4bfdffc8f3379ef4f35004488f}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">using llvm::MachineBasicBlock::const_iterator =  MachineInstrBundleIterator&lt;const MachineInstr&gt;</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 329 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/codegen/machinebasicblock-h">MachineBasicBlock.h</a>.</p>

</div>
</div>

### const\_pred\_iterator {#af23bb5122fa5f787c2e1ba23a5325331}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">using llvm::MachineBasicBlock::const_pred_iterator = 
      SmallVectorImpl&lt;MachineBasicBlock *&gt;::const_iterator</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 401 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/codegen/machinebasicblock-h">MachineBasicBlock.h</a>.</p>

</div>
</div>

### const\_pred\_reverse\_iterator {#a422a49a2a62f51ee4cadd8efd33dcfbe}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">using llvm::MachineBasicBlock::const_pred_reverse_iterator = 
      SmallVectorImpl&lt;MachineBasicBlock *&gt;::const_reverse_iterator</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 408 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/codegen/machinebasicblock-h">MachineBasicBlock.h</a>.</p>

</div>
</div>

### const\_reverse\_instr\_iterator {#a014d813afe056b3d260ef97687347e32}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">using llvm::MachineBasicBlock::const_reverse_instr_iterator =  Instructions::const_reverse_iterator</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 326 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/codegen/machinebasicblock-h">MachineBasicBlock.h</a>.</p>

</div>
</div>

### const\_reverse\_iterator {#af09a6bd5bd27c029abbf5f0b7e5dc137}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">using llvm::MachineBasicBlock::const_reverse_iterator = 
      MachineInstrBundleIterator&lt;const MachineInstr, true&gt;</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 331 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/codegen/machinebasicblock-h">MachineBasicBlock.h</a>.</p>

</div>
</div>

### const\_succ\_iterator {#a3f43e04d827b07cf1d5366554d03f748}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">using llvm::MachineBasicBlock::const_succ_iterator = 
      SmallVectorImpl&lt;MachineBasicBlock *&gt;::const_iterator</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 404 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/codegen/machinebasicblock-h">MachineBasicBlock.h</a>.</p>

</div>
</div>

### const\_succ\_reverse\_iterator {#a94786cbd25915d1f798cca9a14ce0d34}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">using llvm::MachineBasicBlock::const_succ_reverse_iterator = 
      SmallVectorImpl&lt;MachineBasicBlock *&gt;::const_reverse_iterator</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 412 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/codegen/machinebasicblock-h">MachineBasicBlock.h</a>.</p>

</div>
</div>

### instr\_iterator {#ab6395548cae73865213e279ae461db54}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">using llvm::MachineBasicBlock::instr_iterator =  Instructions::iterator</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 323 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/codegen/machinebasicblock-h">MachineBasicBlock.h</a>.</p>

</div>
</div>

### instr\_range {#af91eb0d508929a6b59d300bc7052390f}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">using llvm::MachineBasicBlock::instr_range =  iterator_range&lt;instr_iterator&gt;</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 357 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/codegen/machinebasicblock-h">MachineBasicBlock.h</a>.</p>

</div>
</div>

### iterator {#ae34c996b58df9b9ce6695a0c8b70c533}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">using llvm::MachineBasicBlock::iterator =  MachineInstrBundleIterator&lt;MachineInstr&gt;</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 328 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/codegen/machinebasicblock-h">MachineBasicBlock.h</a>.</p>

</div>
</div>

### livein\_iterator {#a787c857539b04a8552aec72d561a3ca2}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">using llvm::MachineBasicBlock::livein_iterator =  LiveInVector::const_iterator</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 500 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/codegen/machinebasicblock-h">MachineBasicBlock.h</a>.</p>

</div>
</div>

### pred\_iterator {#aa3e6549a5c552971ce60013e2e7c6154}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">using llvm::MachineBasicBlock::pred_iterator =  SmallVectorImpl&lt;MachineBasicBlock *&gt;::iterator</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 400 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/codegen/machinebasicblock-h">MachineBasicBlock.h</a>.</p>

</div>
</div>

### pred\_reverse\_iterator {#adc1b2a5ae459095d279b621a419e6ea0}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">using llvm::MachineBasicBlock::pred_reverse_iterator = 
      SmallVectorImpl&lt;MachineBasicBlock *&gt;::reverse_iterator</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 406 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/codegen/machinebasicblock-h">MachineBasicBlock.h</a>.</p>

</div>
</div>

### reverse\_instr\_iterator {#afde32735260c30997acd66990e80a320}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">using llvm::MachineBasicBlock::reverse_instr_iterator =  Instructions::reverse_iterator</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 325 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/codegen/machinebasicblock-h">MachineBasicBlock.h</a>.</p>

</div>
</div>

### reverse\_iterator {#abada92f8cd2854d2b747f14c4a7be0ed}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">using llvm::MachineBasicBlock::reverse_iterator =  MachineInstrBundleIterator&lt;MachineInstr, true&gt;</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 330 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/codegen/machinebasicblock-h">MachineBasicBlock.h</a>.</p>

</div>
</div>

### succ\_iterator {#a9936e11d7a6149f7cac8fa32a81dd488}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">using llvm::MachineBasicBlock::succ_iterator =  SmallVectorImpl&lt;MachineBasicBlock *&gt;::iterator</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 403 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/codegen/machinebasicblock-h">MachineBasicBlock.h</a>.</p>

</div>
</div>

### succ\_reverse\_iterator {#a2e976bfbcbbea1b5ba70c6eb56bf108e}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">using llvm::MachineBasicBlock::succ_reverse_iterator = 
      SmallVectorImpl&lt;MachineBasicBlock *&gt;::reverse_iterator</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 410 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/codegen/machinebasicblock-h">MachineBasicBlock.h</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Private Member Typedefs

### const\_probability\_iterator {#ab99f82bbbab32ed7281272176425ad4a}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">using llvm::MachineBasicBlock::const_probability_iterator = 
      std::vector&lt;BranchProbability&gt;::const_iterator</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 169 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/codegen/machinebasicblock-h">MachineBasicBlock.h</a>.</p>

</div>
</div>

### Instructions {#ad3c3e5d2c4208c5032c7466a00cf9d1d}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">using llvm::MachineBasicBlock::Instructions =  ilist&lt;MachineInstr, ilist_sentinel_tracking&lt;true&gt;&gt;</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 144 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/codegen/machinebasicblock-h">MachineBasicBlock.h</a>.</p>

</div>
</div>

### LiveInVector {#a2ed4997d258b757a53564f79a788b32e}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">using llvm::MachineBasicBlock::LiveInVector =  std::vector&lt;RegisterMaskPair&gt;</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Keep track of the physical registers that are livein of the basicblock.</p>

<p>Definition at line 175 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/codegen/machinebasicblock-h">MachineBasicBlock.h</a>.</p>

</div>
</div>

### probability\_iterator {#a86fb7beac625c137e20e708cd5f0ccf6}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">using llvm::MachineBasicBlock::probability_iterator =  std::vector&lt;BranchProbability&gt;::iterator</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 168 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/codegen/machinebasicblock-h">MachineBasicBlock.h</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Enumerations

### LivenessQueryResult {#af0288e181965a5ff9f0c7a75201fd142}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">enum llvm::MachineBasicBlock::LivenessQueryResult </td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Possible outcome of a register liveness query to <a href="#a7ebfe0cc2f78ae5f27e1944412606973">computeRegisterLiveness()</a></p>

<dl class="doxyEnumList">
<dt class="doxyEnumTableTitle">Enumeration values</dt>
<dd>
<table class="doxyEnumTable">

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">LQR_Live<a id="af0288e181965a5ff9f0c7a75201fd142accc15fa5c7a27d461dc9a884cc9a2dc8"></a></td>
<td class="doxyEnumItemDescription"><a href="/web-llvm/docs/api/classes/llvm/register">Register</a> is known to be (at least partially) live</td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">LQR_Dead<a id="af0288e181965a5ff9f0c7a75201fd142a092531ae27becd74d96d4a6fae76f863"></a></td>
<td class="doxyEnumItemDescription"><a href="/web-llvm/docs/api/classes/llvm/register">Register</a> is known to be fully dead</td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">LQR_Unknown<a id="af0288e181965a5ff9f0c7a75201fd142af64367be349b6e7672de902ebecae068"></a></td>
<td class="doxyEnumItemDescription"><a href="/web-llvm/docs/api/classes/llvm/register">Register</a> liveness not decidable from local neighborhood</td>
</tr>

</table>
</dd>
</dl>

<p>Definition at line 1187 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/codegen/machinebasicblock-h">MachineBasicBlock.h</a>.</p>

</div>
</div>

### PrintNameFlag {#a55df99d8362d83a10b9fb35fd5b8cf7c}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">enum llvm::MachineBasicBlock::PrintNameFlag </td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">


<dl class="doxyEnumList">
<dt class="doxyEnumTableTitle">Enumeration values</dt>
<dd>
<table class="doxyEnumTable">

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">PrintNameIr<a id="a55df99d8362d83a10b9fb35fd5b8cf7cac13a649d6c2087dca8873a8edd4d3c8d"></a></td>
<td class="doxyEnumItemDescription">Add IR name where available (= (1 &lt;&lt; 0))</td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">PrintNameAttributes<a id="a55df99d8362d83a10b9fb35fd5b8cf7caf29bf9642eaca6e0619977346c03efd8"></a></td>
<td class="doxyEnumItemDescription">Print attributes (= (1 &lt;&lt; 1))</td>
</tr>

</table>
</dd>
</dl>

<p>Definition at line 1213 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/codegen/machinebasicblock-h">MachineBasicBlock.h</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Friends

### ilist\_callback\_traits&lt; MachineBasicBlock &gt; {#acbd6646c0c037f87ce89191e20336d77}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">friend struct <a href="/web-llvm/docs/api/structs/llvm/ilist-callback-traits">ilist_callback_traits</a>&lt; <a href="/web-llvm/docs/api/classes/llvm/machinebasicblock">MachineBasicBlock</a> &gt;</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">


<p>Definition at line 1260 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/codegen/machinebasicblock-h">MachineBasicBlock.h</a>.</p>


<p>Reference <a href="#acdf9e09362a2acd47819187dabad184b">MIPrinter</a>.</p>

</div>
</div>

### MachineBranchProbabilityInfo {#ad75fd5d6b52a6efd7f2ae8448871c528}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">friend class <a href="/web-llvm/docs/api/classes/llvm/machinebranchprobabilityinfo">MachineBranchProbabilityInfo</a></td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">


<p>Definition at line 1259 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/codegen/machinebasicblock-h">MachineBasicBlock.h</a>.</p>


<p>Reference <a href="#ad75fd5d6b52a6efd7f2ae8448871c528">MachineBranchProbabilityInfo</a>.</p>


<p>Referenced by <a href="#ad75fd5d6b52a6efd7f2ae8448871c528">MachineBranchProbabilityInfo</a>.</p>

</div>
</div>

### MachineFunction {#ac423fefe048ace18159808c5592ae74c}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">friend class <a href="/web-llvm/docs/api/classes/llvm/machinefunction">MachineFunction</a></td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">


<p>Definition at line 250 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/codegen/machinebasicblock-h">MachineBasicBlock.h</a>.</p>


<p>Reference <a href="#ac423fefe048ace18159808c5592ae74c">MachineFunction</a>.</p>


<p>Referenced by <a href="#ae32dc74389a52cbb83e6a016274142f5">canSplitCriticalEdge</a>, <a href="#a210ccb5b83a717a8dce63cd7602a58b6">getEHCatchretSymbol</a>, <a href="#a78b12ba4209266f4d26fa513c576ee18">getEndSymbol</a>, <a href="#ac35a65b864412ca7fd4c25b8724144c9">getParent</a>, <a href="#acf6442108e21e7e5379feb8962de65b7">getParent</a>, <a href="#a1cc134bd22a318835dc929323da70ea4">getSymbol</a>, <a href="#aa13f60350a3e19e1791fd628b694da36">liveout_begin</a>, <a href="#ac423fefe048ace18159808c5592ae74c">MachineFunction</a>, <a href="#ab3b62258d9bd41595674de878f37f8d8">print</a>, <a href="#a5a4302f4590a281bb84e08b30c80591c">print</a>, <a href="#ac0bfa894f538166cb476b439a2cb0aea">splitAt</a> and <a href="#aa80aaa82844ab5560ece045eee7b34ac">SplitCriticalEdge</a>.</p>

</div>
</div>

### MIPrinter {#acdf9e09362a2acd47819187dabad184b}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">friend class <a href="/web-llvm/docs/api/classes/llvm/miprinter">MIPrinter</a></td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">


<p>Definition at line 1260 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/codegen/machinebasicblock-h">MachineBasicBlock.h</a>.</p>


<p>Referenced by <a href="#acbd6646c0c037f87ce89191e20336d77">ilist_callback_traits&lt; MachineBasicBlock &gt;</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Private Constructors

### MachineBasicBlock() {#a76eab5c5c5201f40d87ee38e74b71702}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">llvm::MachineBasicBlock::MachineBasicBlock ()</td>
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



<p>Definition at line 243 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/codegen/machinebasicblock-h">MachineBasicBlock.h</a>.</p>

</div>
</div>

### MachineBasicBlock() {#aefa0e690cc1479e4073dfc201785d082}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">MachineBasicBlock::MachineBasicBlock (<a href="/web-llvm/docs/api/classes/llvm/machinefunction">MachineFunction</a> &amp; MF, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/basicblock">BasicBlock</a> * BB)</td>
</tr>
</table>
</td>
<td class="doxyMemberLabelsRight">
<span class="doxyMemberLabels">
<span class="doxyMemberLabel explicit">explicit</span>
</span>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Declaration at line 245 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/codegen/machinebasicblock-h">MachineBasicBlock.h</a>, definition at line 53 of file <a href="/web-llvm/docs/api/files/lib/lib/codegen/machinebasicblock-cpp">MachineBasicBlock.cpp</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Private Destructor

### \~MachineBasicBlock() {#a7458b9e8596683781ad372a590b67041}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">MachineBasicBlock::~MachineBasicBlock ()</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 247 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/codegen/machinebasicblock-h">MachineBasicBlock.h</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Public Member Functions

### addLiveIn() {#acce9c12cc977a88dc7bc51493ce7681c}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void llvm::MachineBasicBlock::addLiveIn (<a href="/web-llvm/docs/api/classes/llvm/mcregister">MCRegister</a> PhysReg, <a href="/web-llvm/docs/api/structs/llvm/lanebitmask">LaneBitmask</a> LaneMask=<a href="/web-llvm/docs/api/structs/llvm/lanebitmask/#a3714a639930eab71d7202da05ad82990">LaneBitmask::getAll</a>())</td>
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

<p>Adds the specified register as a live in.</p>


<p>Note that it is an error to add the same register to the same set more than once unless the intention is to call sortUniqueLiveIns after all registers are added.</p>


<p>Definition at line 465 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/codegen/machinebasicblock-h">MachineBasicBlock.h</a>.</p>


<p>Reference <a href="/web-llvm/docs/api/structs/llvm/lanebitmask/#a3714a639930eab71d7202da05ad82990">llvm::LaneBitmask::getAll</a>.</p>


<p>Referenced by <a href="#a9bd7c04e374ad15665430a243dd30d80">addLiveIn</a>, <a href="/web-llvm/docs/api/classes/llvm/x86framelowering/#afd992a2165073c9cea53128d5b6c4145">llvm::X86FrameLowering::adjustForHiPEPrologue</a>, <a href="/web-llvm/docs/api/classes/llvm/x86framelowering/#ac8faf9a625064bfefafb7ace646815ff">llvm::X86FrameLowering::adjustForSegmentedStacks</a>, <a href="/web-llvm/docs/api/namespaces/anonymous-basicblockpathcloning-cpp-/#a09842318dc1064ae48b19d91e2cb11aa">anonymous{BasicBlockPathCloning.cpp}::ApplyCloning</a>, <a href="/web-llvm/docs/api/classes/llvm/aarch64targetlowering/#ab6a60676cdf39d45ae2ec66a7ea4aada">llvm::AArch64TargetLowering::EmitF128CSEL</a>, <a href="/web-llvm/docs/api/classes/llvm/armtargetlowering/#a6820d09b4db5654cd1377d3ab63b3e01">llvm::ARMTargetLowering::EmitInstrWithCustomInserter</a>, <a href="/web-llvm/docs/api/classes/llvm/x86targetlowering/#a5fd231b7f6dc1db67a2bb2f48bf5f342">llvm::X86TargetLowering::EmitInstrWithCustomInserter</a>, <a href="/web-llvm/docs/api/classes/llvm/machineregisterinfo/#a44ddc08d3e0ee02a2a8fb36fb4c8ac18">llvm::MachineRegisterInfo::EmitLiveInCopies</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/x86/x86isellowering-cpp/#a13a9214d6e92afcb3e956a5891522bed">emitXBegin</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a02134e88cd18139c71d9274c7d287ac3">llvm::getFunctionLiveInPhysReg</a>, <a href="/web-llvm/docs/api/classes/llvm/mipscalllowering/#a3a0c76714485f4713fed0661f961b09a">llvm::MipsCallLowering::lowerFormalArguments</a>, <a href="/web-llvm/docs/api/structs/anonymous-x86indirectthunks-cpp-/lvithunkinserter/#abdfd94a7acd3b3d9694c88bc642d9269">anonymous{X86IndirectThunks.cpp}::LVIThunkInserter::populateThunk</a>, <a href="/web-llvm/docs/api/structs/anonymous-x86indirectthunks-cpp-/retpolinethunkinserter/#aceed22e00e1b77a1a8cab4ac045d6a21">anonymous{X86IndirectThunks.cpp}::RetpolineThunkInserter::populateThunk</a>, <a href="/web-llvm/docs/api/classes/anonymous-hexagoncfgoptimizer-cpp-/hexagoncfgoptimizer/#a44a6c0917383ba77dca7325a7b23c252">anonymous{HexagonCFGOptimizer.cpp}::HexagonCFGOptimizer::runOnMachineFunction</a>, <a href="/web-llvm/docs/api/classes/llvm/irtranslator/#a2fa3a523a1812aeda17891575f852ce9">llvm::IRTranslator::runOnMachineFunction</a>, <a href="/web-llvm/docs/api/classes/llvm/xtensaframelowering/#a757685f42fe19ad1375d53c7e5aa95b1">llvm::XtensaFrameLowering::spillCalleeSavedRegisters</a>, <a href="#aa80aaa82844ab5560ece045eee7b34ac">SplitCriticalEdge</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/x86/x86speculativeloadhardening-cpp/#a18b17899654dd5adb69b62c89ba95783">splitEdge</a>, <a href="/web-llvm/docs/api/files/lib/lib/codegen/shrinkwrap-cpp/#a1c1f48594a6218fef9639f313edbb2c5">tryToSplitRestore</a>, <a href="/web-llvm/docs/api/files/lib/lib/codegen/machinesink-cpp/#a6c1da13a967ff01e9076c55b0b6d158c">updateLiveIn</a> and <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/silowersgprspills-cpp/#a0a2dffaa4ca0137aa854675d5a7c578d">updateLiveness</a>.</p>

</div>
</div>

### addLiveIn() {#a9c42510477e83303466bdd92ff333eec}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void llvm::MachineBasicBlock::addLiveIn (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/structs/llvm/machinebasicblock/registermaskpair">RegisterMaskPair</a> &amp; RegMaskPair)</td>
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



<p>Definition at line 469 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/codegen/machinebasicblock-h">MachineBasicBlock.h</a>.</p>

</div>
</div>

### addLiveIn() {#a9bd7c04e374ad15665430a243dd30d80}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">Register MachineBasicBlock::addLiveIn (<a href="/web-llvm/docs/api/classes/llvm/mcregister">MCRegister</a> PhysReg, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/targetregisterclass">TargetRegisterClass</a> * RC)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Add PhysReg as live in to this block, and ensure that there is a copy of PhysReg to a virtual register of class RC.</p>


<p>Return the virtual register that is a copy of the live in PhysReg.</p>


<p>Declaration at line 488 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/codegen/machinebasicblock-h">MachineBasicBlock.h</a>, definition at line 645 of file <a href="/web-llvm/docs/api/files/lib/lib/codegen/machinebasicblock-cpp">MachineBasicBlock.cpp</a>.</p>


<p>References <a href="#acce9c12cc977a88dc7bc51493ce7681c">addLiveIn</a>, <a href="/web-llvm/docs/api/classes/llvm/machineinstrbuilder/#a927857fc69e4b4f0cde307f86f180df5">llvm::MachineInstrBuilder::addReg</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/silowercontrolflow-cpp/#a4868c5d81c5ccc98c47aeab6244346a0">assert</a>, <a href="#ab2d91e7bec944efcbc39d8e30644f111">begin</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a17e04afcf0c5efeb0eb6a9a45287b5e4">llvm::BuildMI</a>, <a href="/web-llvm/docs/api/namespaces/llvm/dwarf-linker/#a463a58e257d5f6fb2c39eb9a2474fc24ac2e06fc138163b7095fa483616a0a47a">llvm::dwarf_linker::DebugLoc</a>, <a href="#acbc921830578e2741be6549db716c0ce">end</a>, <a href="#aeedc2554f9637d1e27befa7a85c70ec9">front</a>, <a href="/web-llvm/docs/api/classes/llvm/targetsubtargetinfo/#acd858ed72f11db9444617740c3622608">llvm::TargetSubtargetInfo::getInstrInfo</a>, <a href="#acf6442108e21e7e5379feb8962de65b7">getParent</a>, <a href="/web-llvm/docs/api/classes/llvm/machinefunction/#a810234b6b3d223b7c74a4253fcc5ea5e">llvm::MachineFunction::getRegInfo</a>, <a href="/web-llvm/docs/api/classes/llvm/machinefunction/#a3825368aca2bc1550d173660df4da6a6">llvm::MachineFunction::getSubtarget</a>, <a href="/web-llvm/docs/api/files/lib/lib/support/md5-cpp/#ac0eafdc9ee161b71e7af98af736952fd">I</a>, <a href="#a1100bfbadd996d464150c6a68fa8dc1d">isEHPad</a>, <a href="#af9745f59d6647bd43f9f7959ca1a9971">isLiveIn</a>, <a href="/web-llvm/docs/api/classes/llvm/mcregister/#adab6a6e130a565c2cb11ef465fac90e7">llvm::MCRegister::isPhysical</a>, <a href="/web-llvm/docs/api/namespaces/llvm/regstate/#ade26fe5c9b3fe6948def36f7ca12dfc5a9ddde91ef09476d28a088fe57f8e2921">llvm::RegState::Kill</a>, <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/support/errorhandling-h/#ace243f5c25697a1107cce46626b3dc94">llvm_unreachable</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64advsimdscalarpass-cpp/#aacd2ab195054a3e6a74bfbb9d5d571c8">MRI</a>, <a href="#a3be7d94076d328797ab57ce09cefab33">SkipPHIsAndLabels</a> and <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/hexagon/hexagoncopytocombine-cpp/#a1d40004718218dbdf06b496766299101">TII</a>.</p>

</div>
</div>

### addSuccessor() {#a935e2a8884592189d8f261634a0b24c5}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void MachineBasicBlock::addSuccessor (<a href="/web-llvm/docs/api/classes/llvm/machinebasicblock">MachineBasicBlock</a> * Succ, <a href="/web-llvm/docs/api/classes/llvm/branchprobability">BranchProbability</a> Prob=<a href="/web-llvm/docs/api/classes/llvm/branchprobability/#a76e4454abb329dee28e8f525ddd1a210">BranchProbability::getUnknown</a>())</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Add Succ as a successor of this <a href="/web-llvm/docs/api/classes/llvm/machinebasicblock">MachineBasicBlock</a>.</p>


<p>The Predecessors list of Succ is automatically updated. PROB parameter is stored in Probabilities list. The default probability is set as unknown. Mixing known and unknown probabilities in successor list is not allowed. When all successors have unknown probabilities, 1 / N is returned as the probability for each successor, where N is the number of successors.</p>


<p>Note that duplicate Machine CFG edges are not allowed.</p>


<p>Declaration at line 756 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/codegen/machinebasicblock-h">MachineBasicBlock.h</a>, definition at line 798 of file <a href="/web-llvm/docs/api/files/lib/lib/codegen/machinebasicblock-cpp">MachineBasicBlock.cpp</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/classes/llvm/x86framelowering/#afd992a2165073c9cea53128d5b6c4145">llvm::X86FrameLowering::adjustForHiPEPrologue</a>, <a href="/web-llvm/docs/api/classes/llvm/armframelowering/#a62042f5fd3a2df1b4fab2bfc692b2390">llvm::ARMFrameLowering::adjustForSegmentedStacks</a>, <a href="/web-llvm/docs/api/classes/llvm/x86framelowering/#ac8faf9a625064bfefafb7ace646815ff">llvm::X86FrameLowering::adjustForSegmentedStacks</a>, <a href="/web-llvm/docs/api/classes/anonymous-r600machinecfgstructurizer-cpp-/r600machinecfgstructurizer/#a1e5698213d6d250e814ed909311751be">anonymous{R600MachineCFGStructurizer.cpp}::R600MachineCFGStructurizer::cloneSuccessorList</a>, <a href="#a95933492048f0ea830f02f61b1329c12">copySuccessor</a>, <a href="/web-llvm/docs/api/files/lib/lib/codegen/moduloschedule-cpp/#a087b8382e9e76fa52c0c473b14f7d37d">createDedicatedExit</a>, <a href="/web-llvm/docs/api/classes/llvm/peelingmoduloscheduleexpander/#ae5fdb7e682e1d04dab7282c473a3641b">llvm::PeelingModuloScheduleExpander::CreateLCSSAExitingBlock</a>, <a href="/web-llvm/docs/api/classes/llvm/ppctargetlowering/#a541b354a6386df6d03fcdc656d7d9db7">llvm::PPCTargetLowering::EmitAtomicBinary</a>, <a href="/web-llvm/docs/api/classes/llvm/riscvtargetlowering/#a7bafcec0aefe1c8144ce6cacdf80ff19">llvm::RISCVTargetLowering::emitDynamicProbedAlloc</a>, <a href="/web-llvm/docs/api/classes/llvm/ppctargetlowering/#a212384cdd746eaffedb7edc7a16a1cef">llvm::PPCTargetLowering::emitEHSjLjSetJmp</a>, <a href="/web-llvm/docs/api/classes/llvm/systemztargetlowering/#a2a8a6c3f5cf71d0e400566ee13c6e828">llvm::SystemZTargetLowering::emitEHSjLjSetJmp</a>, <a href="/web-llvm/docs/api/classes/llvm/vetargetlowering/#a9b01008eed371b3da0faa8604b91e828">llvm::VETargetLowering::emitEHSjLjSetJmp</a>, <a href="/web-llvm/docs/api/classes/llvm/aarch64targetlowering/#ab6a60676cdf39d45ae2ec66a7ea4aada">llvm::AArch64TargetLowering::EmitF128CSEL</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/riscv/riscvisellowering-cpp/#a90f911eb0622dc6ec5c1333369e495ac">emitFROUND</a>, <a href="/web-llvm/docs/api/classes/llvm/armtargetlowering/#a6820d09b4db5654cd1377d3ab63b3e01">llvm::ARMTargetLowering::EmitInstrWithCustomInserter</a>, <a href="/web-llvm/docs/api/classes/llvm/avrtargetlowering/#a336444d567b931e2ced0dd4f844148ab">llvm::AVRTargetLowering::EmitInstrWithCustomInserter</a>, <a href="/web-llvm/docs/api/classes/llvm/bpftargetlowering/#ac190f0cf5627568bd97cf1e5b24ce57d">llvm::BPFTargetLowering::EmitInstrWithCustomInserter</a>, <a href="/web-llvm/docs/api/classes/llvm/msp430targetlowering/#a948d164566e4b5aca48cf71cbf3a9ee3">llvm::MSP430TargetLowering::EmitInstrWithCustomInserter</a>, <a href="/web-llvm/docs/api/classes/llvm/ppctargetlowering/#a10d6f09e62a827099ec8b54efb4c035d">llvm::PPCTargetLowering::EmitInstrWithCustomInserter</a>, <a href="/web-llvm/docs/api/classes/llvm/sitargetlowering/#a92bd7eb8dcbdfa0341a4fe88a09941da">llvm::SITargetLowering::EmitInstrWithCustomInserter</a>, <a href="/web-llvm/docs/api/classes/llvm/xcoretargetlowering/#a13afdeda523046ab7176bead48d1c46f">llvm::XCoreTargetLowering::EmitInstrWithCustomInserter</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/riscv/riscvisellowering-cpp/#a4af8648d2e12301489dcc7b760f981ac">EmitLoweredCascadedSelect</a>, <a href="/web-llvm/docs/api/classes/llvm/ppctargetlowering/#a2e99e64e510ba34954d7fe85b1e30119">llvm::PPCTargetLowering::EmitPartwordAtomicBinary</a>, <a href="/web-llvm/docs/api/classes/llvm/ppctargetlowering/#a2cb46b1ded73af4c2924bd2d1d8db334">llvm::PPCTargetLowering::emitProbedAlloca</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/riscv/riscvisellowering-cpp/#ae20aef7ab8c13752bc5663fb0e6cbb1c">emitReadCounterWidePseudo</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/riscv/riscvisellowering-cpp/#a59f08a4b78badcbfff06545894a60e6e">emitSelectPseudo</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/csky/cskyisellowering-cpp/#a8e39c98d41d74a2147127a17c9800c7d">emitSelectPseudo</a>, <a href="/web-llvm/docs/api/classes/llvm/msp430targetlowering/#a33dd164bd4caf16d69db25a98f5d338f">llvm::MSP430TargetLowering::EmitShiftInstr</a>, <a href="/web-llvm/docs/api/classes/llvm/vetargetlowering/#a751f59893007a8fdcc892d81119abc82">llvm::VETargetLowering::emitSjLjDispatchBlock</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/riscv/riscvframelowering-cpp/#a30a608df0c31b4ad3814cce66364082c">emitStackProbeInline</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/loongarch/loongarchisellowering-cpp/#accb97b288f5b7b78cc16845a383fc13c">emitVecCondBranchPseudo</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/x86/x86isellowering-cpp/#a13a9214d6e92afcb3e956a5891522bed">emitXBegin</a>, <a href="/web-llvm/docs/api/classes/llvm/amdgpuregisterbankinfo/#a533cd1035e03cdca3da433e98e77e430">llvm::AMDGPURegisterBankInfo::executeInWaterfallLoop</a>, <a href="/web-llvm/docs/api/classes/llvm/veinstrinfo/#ad99d6c93063cbfe0bf0f995a0cf12552">llvm::VEInstrInfo::expandExtendStackPseudo</a>, <a href="/web-llvm/docs/api/classes/llvm/sparctargetlowering/#a216c0fdb0cdd991dcf320bd42ff4c39e">llvm::SparcTargetLowering::expandSelectCC</a>, <a href="/web-llvm/docs/api/classes/llvm/ppcframelowering/#af0a5a3bd252aaac7b161ad8c01cf0951">llvm::PPCFrameLowering::inlineStackProbe</a>, <a href="/web-llvm/docs/api/classes/llvm/systemzelfframelowering/#a61e80a52ee9eaf5dce1b7a90d1901d0e">llvm::SystemZELFFrameLowering::inlineStackProbe</a>, <a href="/web-llvm/docs/api/classes/llvm/systemzxplinkframelowering/#a35f79e8cb7551ca57450108d9816b2ba">llvm::SystemZXPLINKFrameLowering::inlineStackProbe</a>, <a href="/web-llvm/docs/api/classes/llvm/siinstrinfo/#a7dbf2885fa89980322c2f4b58f85ff18">llvm::SIInstrInfo::insertSimulatedTrap</a>, <a href="/web-llvm/docs/api/classes/llvm/amdgpulegalizerinfo/#aff7dfc9d1d4355acbd741d76ce27fca1">llvm::AMDGPULegalizerInfo::legalizeTrapEndpgm</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/siisellowering-cpp/#a696bdea6147585aeab4c74925c3587c3">loadM0FromVGPR</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/siinstrinfo-cpp/#af14ddf696e10f25864072cc0dc2e0161">loadMBUFScalarOperandsFromVGPR</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/webassembly/webassemblyisellowering-cpp/#a01bea37475bf9a1f853b90975dbf7605">LowerFPToInt</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/webassembly/webassemblyisellowering-cpp/#a1b22ed476a56f8583de43854dfe57830">LowerMemcpy</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/webassembly/webassemblyisellowering-cpp/#aa603afd757ff3057f96bf5c1ee83e8b2">LowerMemset</a>, <a href="/web-llvm/docs/api/classes/anonymous-miparser-cpp-/miparser/#a3904021432d1d4cf1620b9c09506e612">anonymous{MIParser.cpp}::MIParser::parseBasicBlocks</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a0fdc13bfd373951ae6163637d6576c39">llvm::PeelSingleBlockLoop</a>, <a href="/web-llvm/docs/api/structs/anonymous-x86indirectthunks-cpp-/retpolinethunkinserter/#aceed22e00e1b77a1a8cab4ac045d6a21">anonymous{X86IndirectThunks.cpp}::RetpolineThunkInserter::populateThunk</a>, <a href="/web-llvm/docs/api/classes/llvm/aarch64instrinfo/#ab9deb47df6ac29c81422ae6b4bfd924d">llvm::AArch64InstrInfo::probedStackAlloc</a>, <a href="/web-llvm/docs/api/classes/llvm/armblockplacement/#a977d1a0dea04c7f562cb1ca6063d81dd">llvm::ARMBlockPlacement::revertWhileToDoLoop</a>, <a href="#ac0bfa894f538166cb476b439a2cb0aea">splitAt</a>, <a href="/web-llvm/docs/api/classes/anonymous-cskyconstantislandpass-cpp-/cskyconstantislands/#ae708a0dc9c80038ba6d971c94eb9db5c">anonymous{CSKYConstantIslandPass.cpp}::CSKYConstantIslands::splitBlockBeforeInstr</a>, <a href="/web-llvm/docs/api/classes/anonymous-mipsconstantislandpass-cpp-/mipsconstantislands/#a747abf73a79323919b62fb98e61aeaf2">anonymous{MipsConstantIslandPass.cpp}::MipsConstantIslands::splitBlockBeforeInstr</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/siisellowering-cpp/#ac24b8552572d60a9f8943c27199fb8b2">splitBlockForLoop</a>, <a href="#aa80aaa82844ab5560ece045eee7b34ac">SplitCriticalEdge</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/x86/x86speculativeloadhardening-cpp/#a18b17899654dd5adb69b62c89ba95783">splitEdge</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/powerpc/ppcreducecrlogicals-cpp/#a6268a1294b61555b575fbd131789aaf3">splitMBB</a>, <a href="#a4b43b969b3db9fc943b664738f62ca76">splitSuccessor</a>, <a href="#a31e57b158a17c459f0dc34b0e602ecc6">transferSuccessors</a>, <a href="#a046a35e36c4c1206711ea82ee9cb6d72">transferSuccessorsAndUpdatePHIs</a> and <a href="/web-llvm/docs/api/files/lib/lib/codegen/shrinkwrap-cpp/#a1c1f48594a6218fef9639f313edbb2c5">tryToSplitRestore</a>.</p>

</div>
</div>

### addSuccessorWithoutProb() {#a3f3061829632220504bb4a1cb819cfac}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void MachineBasicBlock::addSuccessorWithoutProb (<a href="/web-llvm/docs/api/classes/llvm/machinebasicblock">MachineBasicBlock</a> * Succ)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Add Succ as a successor of this <a href="/web-llvm/docs/api/classes/llvm/machinebasicblock">MachineBasicBlock</a>.</p>


<p>The Predecessors list of Succ is automatically updated. The probability is not provided because BPI is not available (e.g. -O0 is used), in which case edge probabilities won't be used. Using this interface can save some space.</p>


<p>Declaration at line 763 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/codegen/machinebasicblock-h">MachineBasicBlock.h</a>, definition at line 808 of file <a href="/web-llvm/docs/api/files/lib/lib/codegen/machinebasicblock-cpp">MachineBasicBlock.cpp</a>.</p>


<p>Referenced by <a href="#a95933492048f0ea830f02f61b1329c12">copySuccessor</a>, <a href="#a31e57b158a17c459f0dc34b0e602ecc6">transferSuccessors</a> and <a href="#a046a35e36c4c1206711ea82ee9cb6d72">transferSuccessorsAndUpdatePHIs</a>.</p>

</div>
</div>

### back() {#acf35424231192c6b4a3e22d711f50b1e}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">MachineInstr &amp; llvm::MachineBasicBlock::back ()</td>
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



<p>Definition at line 344 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/codegen/machinebasicblock-h">MachineBasicBlock.h</a>.</p>


<p>Reference <a href="#acbc921830578e2741be6549db716c0ce">end</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/classes/llvm/machinefunction/#af56aaa8bfe07634547529beee6e99917">llvm::MachineFunction::back</a>, <a href="/web-llvm/docs/api/classes/llvm/machinefunction/#aa99535342c75b02dd086fd3a7633e747">llvm::MachineFunction::back</a>, <a href="/web-llvm/docs/api/classes/anonymous-cskyconstantislandpass-cpp-/cskyconstantislands/#aee171a94c094d78c3744e68795791b8d">anonymous{CSKYConstantIslandPass.cpp}::CSKYConstantIslands::createNewWater</a>, <a href="/web-llvm/docs/api/classes/anonymous-mipsconstantislandpass-cpp-/mipsconstantislands/#ac438bed7ae6afbb9ff9e0be02099ad0f">anonymous{MipsConstantIslandPass.cpp}::MipsConstantIslands::createNewWater</a>, <a href="#a31aa2680ec79198a4c94f35b3a1ad97e">getFallThrough</a>, <a href="/web-llvm/docs/api/classes/llvm/loongarchinstrinfo/#a7a51fbf2432530ad72f0a3996b993a7f">llvm::LoongArchInstrInfo::insertIndirectBranch</a>, <a href="/web-llvm/docs/api/classes/llvm/riscvinstrinfo/#a63b280c848f7c74e68e3a6f45ffb4a85">llvm::RISCVInstrInfo::insertIndirectBranch</a>, <a href="/web-llvm/docs/api/classes/llvm/xtensainstrinfo/#a593e32f55b5d5133887cf7feb7999792">llvm::XtensaInstrInfo::insertIndirectBranch</a>, <a href="#adf1c64c05c8afb975b979543f8f850df">isEHScopeReturnBlock</a>, <a href="#a82f5d244972c88ff03ee56d6c090ac70">isReturnBlock</a>, <a href="/web-llvm/docs/api/namespaces/anonymous-basicblockpathcloning-cpp-/#abbaff7e4a8cdaa59924d29ba6e305f4a">anonymous{BasicBlockPathCloning.cpp}::IsValidCloning</a>, <a href="/web-llvm/docs/api/structs/anonymous-x86indirectthunks-cpp-/retpolinethunkinserter/#aceed22e00e1b77a1a8cab4ac045d6a21">anonymous{X86IndirectThunks.cpp}::RetpolineThunkInserter::populateThunk</a>, <a href="/web-llvm/docs/api/files/lib/lib/codegen/branchfolding-cpp/#a905140abedaee343fc7ef33707052792">ProfitableToMerge</a>, <a href="/web-llvm/docs/api/classes/llvm/armblockplacement/#a977d1a0dea04c7f562cb1ca6063d81dd">llvm::ARMBlockPlacement::revertWhileToDoLoop</a>, <a href="/web-llvm/docs/api/classes/anonymous-hexagoncfgoptimizer-cpp-/hexagoncfgoptimizer/#a44a6c0917383ba77dca7325a7b23c252">anonymous{HexagonCFGOptimizer.cpp}::HexagonCFGOptimizer::runOnMachineFunction</a>, <a href="/web-llvm/docs/api/classes/llvm/tailduplicator/#aa7dba30d4d9162f00367404e06085391">llvm::TailDuplicator::shouldTailDuplicate</a> and <a href="#a703ba58bd58d60cd76ad205dda1634eb">terminatorIsComputedGoto</a>.</p>

</div>
</div>

### back() {#a12b36a2272e92056473c7b59722afa14}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">const MachineInstr &amp; llvm::MachineBasicBlock::back ()</td>
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



<p>Definition at line 346 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/codegen/machinebasicblock-h">MachineBasicBlock.h</a>.</p>


<p>Reference <a href="#acbc921830578e2741be6549db716c0ce">end</a>.</p>

</div>
</div>

### begin() {#ab2d91e7bec944efcbc39d8e30644f111}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">iterator llvm::MachineBasicBlock::begin ()</td>
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



<p>Definition at line 364 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/codegen/machinebasicblock-h">MachineBasicBlock.h</a>.</p>


<p>Reference <a href="#a172e7bd9150eb0519ef04c796086f93d">instr_begin</a>.</p>


<p>Referenced by <a href="#a9bd7c04e374ad15665430a243dd30d80">addLiveIn</a>, <a href="/web-llvm/docs/api/classes/llvm/livevariables/#afbcff91139fc89e3e8c0dda857e7b128">llvm::LiveVariables::addNewBlock</a>, <a href="/web-llvm/docs/api/classes/llvm/livevariables/#afc347ae9e7fcba69b04162d7b4a73635">llvm::LiveVariables::addNewBlock</a>, <a href="/web-llvm/docs/api/files/lib/lib/codegen/tailduplicator-cpp/#a8d60ca423c44106297940619d9411856">bothUsedInPHI</a>, <a href="/web-llvm/docs/api/classes/llvm/errataworkaround/#a9ca7d3c709feb89bb21527a0b439c6ad">llvm::ErrataWorkaround::checkSeqTN0010</a>, <a href="/web-llvm/docs/api/classes/llvm/errataworkaround/#a97e744d4954c2bbf1ebf01f00ff11b42">llvm::ErrataWorkaround::checkSeqTN0012</a>, <a href="/web-llvm/docs/api/files/lib/lib/codegen/cfifixup-cpp/#a6766bb9d415c3d929afaa24877e14fc6">cloneCfiPrologue</a>, <a href="#a7ebfe0cc2f78ae5f27e1944412606973">computeRegisterLiveness</a>, <a href="/web-llvm/docs/api/files/lib/lib/codegen/branchfolding-cpp/#aaaf533c4a29ff1fd44bfef2f8feb1c3c">copyDebugInfoToSuccessor</a>, <a href="/web-llvm/docs/api/classes/llvm/ssaupdatertraits-4e613f36227a2a352217431a8f1958cd/#a0db03d5e2c460331af4ee0afaaec953a">llvm::SSAUpdaterTraits&lt; MachineSSAUpdater &gt;::CreateEmptyPHI</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/x86/x86isellowering-cpp/#a22444fb95050a5bef1c689e5bc9b064e">createPHIsForCMOVsInSinkBB</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/systemz/systemzisellowering-cpp/#a3c4c42f79d79638f6b67532d3f81df58">createPHIsForSelects</a>, <a href="/web-llvm/docs/api/classes/llvm/machinedominatortree/#a0dbb37174d54679518ca9ed1a0e7016e">llvm::MachineDominatorTree::dominates</a>, <a href="/web-llvm/docs/api/classes/llvm/ppctargetlowering/#a541b354a6386df6d03fcdc656d7d9db7">llvm::PPCTargetLowering::EmitAtomicBinary</a>, <a href="/web-llvm/docs/api/classes/llvm/livedebugvariables/ldvimpl/#abe5a79d15b373804c482e1905df927ff">llvm::LiveDebugVariables::LDVImpl::emitDebugValues</a>, <a href="/web-llvm/docs/api/classes/llvm/riscvtargetlowering/#a7bafcec0aefe1c8144ce6cacdf80ff19">llvm::RISCVTargetLowering::emitDynamicProbedAlloc</a>, <a href="/web-llvm/docs/api/classes/llvm/ppctargetlowering/#a212384cdd746eaffedb7edc7a16a1cef">llvm::PPCTargetLowering::emitEHSjLjSetJmp</a>, <a href="/web-llvm/docs/api/classes/llvm/systemztargetlowering/#a2a8a6c3f5cf71d0e400566ee13c6e828">llvm::SystemZTargetLowering::emitEHSjLjSetJmp</a>, <a href="/web-llvm/docs/api/classes/llvm/vetargetlowering/#a9b01008eed371b3da0faa8604b91e828">llvm::VETargetLowering::emitEHSjLjSetJmp</a>, <a href="/web-llvm/docs/api/classes/llvm/aarch64targetlowering/#ab6a60676cdf39d45ae2ec66a7ea4aada">llvm::AArch64TargetLowering::EmitF128CSEL</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/riscv/riscvisellowering-cpp/#a90f911eb0622dc6ec5c1333369e495ac">emitFROUND</a>, <a href="/web-llvm/docs/api/classes/llvm/armtargetlowering/#a6820d09b4db5654cd1377d3ab63b3e01">llvm::ARMTargetLowering::EmitInstrWithCustomInserter</a>, <a href="/web-llvm/docs/api/classes/llvm/avrtargetlowering/#a336444d567b931e2ced0dd4f844148ab">llvm::AVRTargetLowering::EmitInstrWithCustomInserter</a>, <a href="/web-llvm/docs/api/classes/llvm/bpftargetlowering/#ac190f0cf5627568bd97cf1e5b24ce57d">llvm::BPFTargetLowering::EmitInstrWithCustomInserter</a>, <a href="/web-llvm/docs/api/classes/llvm/msp430targetlowering/#a948d164566e4b5aca48cf71cbf3a9ee3">llvm::MSP430TargetLowering::EmitInstrWithCustomInserter</a>, <a href="/web-llvm/docs/api/classes/llvm/ppctargetlowering/#a10d6f09e62a827099ec8b54efb4c035d">llvm::PPCTargetLowering::EmitInstrWithCustomInserter</a>, <a href="/web-llvm/docs/api/classes/llvm/xcoretargetlowering/#a13afdeda523046ab7176bead48d1c46f">llvm::XCoreTargetLowering::EmitInstrWithCustomInserter</a>, <a href="/web-llvm/docs/api/classes/llvm/machineregisterinfo/#a44ddc08d3e0ee02a2a8fb36fb4c8ac18">llvm::MachineRegisterInfo::EmitLiveInCopies</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/siisellowering-cpp/#a9d5a6023eff415532345b226faccc38b">emitLoadM0FromVGPRLoop</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/siinstrinfo-cpp/#a476adf24d3374520fb31b2785f331d58">emitLoadScalarOpsFromVGPRLoop</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/riscv/riscvisellowering-cpp/#a4af8648d2e12301489dcc7b760f981ac">EmitLoweredCascadedSelect</a>, <a href="/web-llvm/docs/api/classes/llvm/ppctargetlowering/#a2e99e64e510ba34954d7fe85b1e30119">llvm::PPCTargetLowering::EmitPartwordAtomicBinary</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/riscv/riscvisellowering-cpp/#ae20aef7ab8c13752bc5663fb0e6cbb1c">emitReadCounterWidePseudo</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/riscv/riscvisellowering-cpp/#a59f08a4b78badcbfff06545894a60e6e">emitSelectPseudo</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/csky/cskyisellowering-cpp/#a8e39c98d41d74a2147127a17c9800c7d">emitSelectPseudo</a>, <a href="/web-llvm/docs/api/classes/llvm/msp430targetlowering/#a33dd164bd4caf16d69db25a98f5d338f">llvm::MSP430TargetLowering::EmitShiftInstr</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/loongarch/loongarchisellowering-cpp/#accb97b288f5b7b78cc16845a383fc13c">emitVecCondBranchPseudo</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/x86/x86isellowering-cpp/#a13a9214d6e92afcb3e956a5891522bed">emitXBegin</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/gcnhazardrecognizer-cpp/#accecdb72ed09118005742bcd44b08440">ensureEntrySetPrio</a>, <a href="/web-llvm/docs/api/classes/llvm/amdgpuregisterbankinfo/#a533cd1035e03cdca3da433e98e77e430">llvm::AMDGPURegisterBankInfo::executeInWaterfallLoop</a>, <a href="/web-llvm/docs/api/classes/llvm/veinstrinfo/#ad99d6c93063cbfe0bf0f995a0cf12552">llvm::VEInstrInfo::expandExtendStackPseudo</a>, <a href="/web-llvm/docs/api/classes/llvm/sparctargetlowering/#a216c0fdb0cdd991dcf320bd42ff4c39e">llvm::SparcTargetLowering::expandSelectCC</a>, <a href="/web-llvm/docs/api/namespaces/llvm/webassembly/#a6cc6351696a872f05cdf540a663d584c">llvm::WebAssembly::findCatch</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a079add9cf3b7069c79b91a3d8c7c28a3">llvm::findCMPToFoldIntoCBZ</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a444e3b411610e3f4275e36386768ce8d">llvm::findSplitPointForStackProtector</a>, <a href="/web-llvm/docs/api/structs/llvm/rdf/liveness/#a0c3a1721c534dbc63fdc081a9365fd9c">llvm::rdf::Liveness::getAllReachingDefs</a>, <a href="#a62b5d2211c09378c471307293453d780">getFirstNonDebugInstr</a>, <a href="#a7f0521fa2de44271fd4b909ea7351ef3">getFirstTerminator</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a02134e88cd18139c71d9274c7d287ac3">llvm::getFunctionLiveInPhysReg</a>, <a href="/web-llvm/docs/api/classes/anonymous-ppciseldagtodag-cpp-/ppcdagtodagisel/#ac20ef8c91eac038ee0e6bcc32be560f5">anonymous{PPCISelDAGToDAG.cpp}::PPCDAGToDAGISel::getGlobalBaseReg</a>, <a href="/web-llvm/docs/api/classes/llvm/cskyinstrinfo/#a9fa574f4bc0ad6d1cd8335fdf7aba857">llvm::CSKYInstrInfo::getGlobalBaseReg</a>, <a href="/web-llvm/docs/api/classes/llvm/sparcinstrinfo/#a6e968bdff5d0f9e8b1f3492bd2460317">llvm::SparcInstrInfo::getGlobalBaseReg</a>, <a href="/web-llvm/docs/api/classes/llvm/veinstrinfo/#a7a03faa0eec2d5c0ded78156f276258c">llvm::VEInstrInfo::getGlobalBaseReg</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/mips/mipsbranchexpansion-cpp/#a4801e594c6226fb9020a07ca36641c5b">getNextMachineInstr</a>, <a href="/web-llvm/docs/api/classes/llvm/sitargetlowering/#a5b2c69041e8c83952d7cdd75cf7a36e8">llvm::SITargetLowering::getPrefLoopAlignment</a>, <a href="/web-llvm/docs/api/classes/llvm/machinessaupdater/#a670da7741129c7d591dc19951ecce6c3">llvm::MachineSSAUpdater::GetValueInMiddleOfBlock</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64redundantcopyelimination-cpp/#af884214031cdb18344d85b5d4c422fef">INITIALIZE_PASS</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/lanai/lanaimemalucombiner-cpp/#a3d8451ff05b58b604cb87a1623ef73b3">INITIALIZE_PASS</a>, <a href="/web-llvm/docs/api/classes/llvm/ppcframelowering/#af0a5a3bd252aaac7b161ad8c01cf0951">llvm::PPCFrameLowering::inlineStackProbe</a>, <a href="/web-llvm/docs/api/classes/llvm/systemzelfframelowering/#a61e80a52ee9eaf5dce1b7a90d1901d0e">llvm::SystemZELFFrameLowering::inlineStackProbe</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/silowersgprspills-cpp/#a3c627e9f404e8f9cf66e5a4a27860347">insertCSRRestores</a>, <a href="/web-llvm/docs/api/files/lib/lib/codegen/prologepiloginserter-cpp/#a04bc45ddbc56deb8b54dacaeea86df8f">insertCSRRestores</a>, <a href="/web-llvm/docs/api/files/lib/lib/codegen/prologepiloginserter-cpp/#a61e27cf21f938d341d13395bb4e17493">insertCSRSaves</a>, <a href="/web-llvm/docs/api/classes/anonymous-hexagoncopyhoisting-cpp-/hexagoncopyhoisting/#a2142c4566b7d15a35687f955d946a277">anonymous{HexagonCopyHoisting.cpp}::HexagonCopyHoisting::isSafetoMove</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/siisellowering-cpp/#a696bdea6147585aeab4c74925c3587c3">loadM0FromVGPR</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/siinstrinfo-cpp/#af14ddf696e10f25864072cc0dc2e0161">loadMBUFScalarOperandsFromVGPR</a>, <a href="/web-llvm/docs/api/files/lib/lib/codegen/machinessaupdater-cpp/#a43b22ba78d684fd69b551c4c04426e3d">LookForIdenticalPHI</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/webassembly/webassemblyisellowering-cpp/#a01bea37475bf9a1f853b90975dbf7605">LowerFPToInt</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/webassembly/webassemblyisellowering-cpp/#a1b22ed476a56f8583de43854dfe57830">LowerMemcpy</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/webassembly/webassemblyisellowering-cpp/#aa603afd757ff3057f96bf5c1ee83e8b2">LowerMemset</a>, <a href="/web-llvm/docs/api/classes/anonymous-r600machinecfgstructurizer-cpp-/r600machinecfgstructurizer/#aa76d1bb8a35c5fe0c9c22df9cc0dba10">anonymous{R600MachineCFGStructurizer.cpp}::R600MachineCFGStructurizer::mergeIfthenelseBlock</a>, <a href="/web-llvm/docs/api/classes/anonymous-r600machinecfgstructurizer-cpp-/r600machinecfgstructurizer/#a5fec9aab7a2ff820c3c372f3cda87c25">anonymous{R600MachineCFGStructurizer.cpp}::R600MachineCFGStructurizer::mergeSerialBlock</a>, <a href="/web-llvm/docs/api/classes/anonymous-r600machinecfgstructurizer-cpp-/r600machinecfgstructurizer/#a34b11aa12929fbf594b75074a35dc9c2">anonymous{R600MachineCFGStructurizer.cpp}::R600MachineCFGStructurizer::migrateInstruction</a>, <a href="/web-llvm/docs/api/classes/anonymous-ppcbranchcoalescing-cpp-/ppcbranchcoalescing/#a2a11298ee3a7cfcfa678f8b9a3df20db">anonymous{PPCBranchCoalescing.cpp}::PPCBranchCoalescing::moveAndUpdatePHIs</a>, <a href="/web-llvm/docs/api/classes/anonymous-aarch64redundantcopyelimination-cpp-/aarch64redundantcopyelimination/#a1ee0cfcd17ed3a5b4826b8a5f93e50e1">anonymous{AArch64RedundantCopyElimination.cpp}::AArch64RedundantCopyElimination::optimizeBlock</a>, <a href="/web-llvm/docs/api/classes/llvm/armbaseinstrinfo/#a12cb817575a9c4141e5a1268e6821503">llvm::ARMBaseInstrInfo::optimizeCompareInstr</a>, <a href="/web-llvm/docs/api/classes/llvm/lanaiinstrinfo/#ac3660ab4e1d66ed8457df619aa1bfec1">llvm::LanaiInstrInfo::optimizeCompareInstr</a>, <a href="/web-llvm/docs/api/classes/llvm/ppcinstrinfo/#a8118d9f62c345028220579c9d1ca4061">llvm::PPCInstrInfo::optimizeCompareInstr</a>, <a href="/web-llvm/docs/api/classes/llvm/peelingmoduloscheduleexpander/#a32e5399895869ed336d4d279c20b5f9c">llvm::PeelingModuloScheduleExpander::peelKernel</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a0fdc13bfd373951ae6163637d6576c39">llvm::PeelSingleBlockLoop</a>, <a href="#a36b529ef331e4099007e14b48c75316a">phis</a>, <a href="/web-llvm/docs/api/structs/anonymous-aarch64slshardening-cpp-/slshardeninginserter/#aa0294873aedbdc7244e1ca9aa115889e">anonymous{AArch64SLSHardening.cpp}::SLSHardeningInserter::populateThunk</a>, <a href="/web-llvm/docs/api/classes/llvm/aarch64instrinfo/#ab9deb47df6ac29c81422ae6b4bfd924d">llvm::AArch64InstrInfo::probedStackAlloc</a>, <a href="/web-llvm/docs/api/structs/anonymous-ppcearlyreturn-cpp-/ppcearlyreturn/#ae036500138a9ae1567af6b28547cf045">anonymous{PPCEarlyReturn.cpp}::PPCEarlyReturn::processBlock</a>, <a href="/web-llvm/docs/api/files/lib/lib/codegen/branchfolding-cpp/#a905140abedaee343fc7ef33707052792">ProfitableToMerge</a>, <a href="/web-llvm/docs/api/classes/anonymous-cskyconstantislandpass-cpp-/cskyconstantislands/#a260e4fa04b4392ed7de8a9202292a2ca">anonymous{CSKYConstantIslandPass.cpp}::CSKYConstantIslands::removeDeadCPEMI</a>, <a href="/web-llvm/docs/api/classes/anonymous-mipsconstantislandpass-cpp-/mipsconstantislands/#abbda87d0f5c41ed3eca00b354a53417d">anonymous{MipsConstantIslandPass.cpp}::MipsConstantIslands::removeDeadCPEMI</a>, <a href="/web-llvm/docs/api/files/lib/lib/codegen/shrinkwrap-cpp/#a5aa69466ef430dc4ba4de70307ae4415">rollbackRestoreSplit</a>, <a href="/web-llvm/docs/api/files/lib/lib/codegen/finalizeisel-cpp/#a6395b072c4fb781dca4789de8aba1f55">runImpl</a>, <a href="/web-llvm/docs/api/classes/anonymous-hexagoncfgoptimizer-cpp-/hexagoncfgoptimizer/#a44a6c0917383ba77dca7325a7b23c252">anonymous{HexagonCFGOptimizer.cpp}::HexagonCFGOptimizer::runOnMachineFunction</a>, <a href="/web-llvm/docs/api/structs/anonymous-m68kinstrinfo-cpp-/m68kglobalbasereg/#a04412e72586680e6bfb4ced5a69102c2">anonymous{M68kInstrInfo.cpp}::M68kGlobalBaseReg::runOnMachineFunction</a>, <a href="/web-llvm/docs/api/structs/anonymous-patchablefunction-cpp-/patchablefunction/#a11d99203cc91bbd49c59f32943541747">anonymous{PatchableFunction.cpp}::PatchableFunction::runOnMachineFunction</a>, <a href="/web-llvm/docs/api/classes/anonymous-siinsertwaitcnts-cpp-/siinsertwaitcnts/#aab6a5b3788b7384e1928f2ccd79f26b7">anonymous{SIInsertWaitcnts.cpp}::SIInsertWaitcnts::runOnMachineFunction</a>, <a href="/web-llvm/docs/api/classes/anonymous-x86flagscopylowering-cpp-/x86flagscopyloweringpass/#a30d90e84a3faa0cd7aa2c3b96d65c232">anonymous{X86FlagsCopyLowering.cpp}::X86FlagsCopyLoweringPass::runOnMachineFunction</a>, <a href="/web-llvm/docs/api/structs/anonymous-x86instrinfo-cpp-/cgbr/#ae7e54015b8e4160365d925c1bd46004f">anonymous{X86InstrInfo.cpp}::CGBR::runOnMachineFunction</a>, <a href="/web-llvm/docs/api/classes/llvm/cfifixup/#a7d1808859a4351ab820d5fa17a0e2685">llvm::CFIFixup::runOnMachineFunction</a>, <a href="/web-llvm/docs/api/classes/llvm/irtranslator/#a2fa3a523a1812aeda17891575f852ce9">llvm::IRTranslator::runOnMachineFunction</a>, <a href="/web-llvm/docs/api/classes/llvm/selectiondagisel/#af17ffaab7d809b7d56e212a46f26f1a2">llvm::SelectionDAGISel::runOnMachineFunction</a>, <a href="#af897d8e9556478c1442c739ce664bcb6">sizeWithoutDebugLargerThan</a>, <a href="#ac0bfa894f538166cb476b439a2cb0aea">splitAt</a>, <a href="/web-llvm/docs/api/namespaces/llvm/systemz/#a9f28b32cebb99746b65b07147c24d6cf">llvm::SystemZ::splitBlockAfter</a>, <a href="/web-llvm/docs/api/namespaces/llvm/systemz/#a175299250e6f7f5542fb5474ff0c9c6a">llvm::SystemZ::splitBlockBefore</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/siisellowering-cpp/#ac24b8552572d60a9f8943c27199fb8b2">splitBlockForLoop</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/webassembly/webassemblycfgstackify-cpp/#a3f8efd734c37d01f22580c2211a68483">splitEndLoopBB</a>, <a href="/web-llvm/docs/api/classes/llvm/peelingmoduloscheduleexpander/#ae67a99405a40814d2261e31f11fe7a38">llvm::PeelingModuloScheduleExpander::validateAgainstModuloScheduleExpander</a>, <a href="/web-llvm/docs/api/structs/anonymous-aarch64cleanuplocaldynamictlspass-cpp-/ldtlscleanup/#a047e1c70e1f34092b00f1c8b2d969778">anonymous{AArch64CleanupLocalDynamicTLSPass.cpp}::LDTLSCleanup::VisitNode</a> and <a href="/web-llvm/docs/api/structs/anonymous-x86instrinfo-cpp-/ldtlscleanup/#a96815d10911f05b2612864c5ee82f5d4">anonymous{X86InstrInfo.cpp}::LDTLSCleanup::VisitNode</a>.</p>

</div>
</div>

### begin() {#aa86c88f644b3ccab5bac660ca5f45760}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">const_iterator llvm::MachineBasicBlock::begin ()</td>
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



<p>Definition at line 365 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/codegen/machinebasicblock-h">MachineBasicBlock.h</a>.</p>


<p>Reference <a href="#a172e7bd9150eb0519ef04c796086f93d">instr_begin</a>.</p>

</div>
</div>

### canFallThrough() {#a5ffb77c69d69a5beff906caaecfd7be4}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool MachineBasicBlock::canFallThrough ()</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Return true if the block can implicitly transfer control to the block after it by falling off the end of it.</p>


<p>This should return false if it can reach the block after it, but it uses an explicit branch to do so (e.g., a table jump). True is a conservative answer.</p>


<p>Declaration at line 871 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/codegen/machinebasicblock-h">MachineBasicBlock.h</a>, definition at line 1021 of file <a href="/web-llvm/docs/api/files/lib/lib/codegen/machinebasicblock-cpp">MachineBasicBlock.cpp</a>.</p>


<p>Reference <a href="#a31aa2680ec79198a4c94f35b3a1ad97e">getFallThrough</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/classes/llvm/armtargetlowering/#a6820d09b4db5654cd1377d3ab63b3e01">llvm::ARMTargetLowering::EmitInstrWithCustomInserter</a>, <a href="/web-llvm/docs/api/structs/anonymous-ppcearlyreturn-cpp-/ppcearlyreturn/#ae036500138a9ae1567af6b28547cf045">anonymous{PPCEarlyReturn.cpp}::PPCEarlyReturn::processBlock</a> and <a href="/web-llvm/docs/api/classes/llvm/tailduplicator/#aa7dba30d4d9162f00367404e06085391">llvm::TailDuplicator::shouldTailDuplicate</a>.</p>

</div>
</div>

### canSplitCriticalEdge() {#ae32dc74389a52cbb83e6a016274142f5}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool MachineBasicBlock::canSplitCriticalEdge (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/machinebasicblock">MachineBasicBlock</a> * Succ)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p><a href="/web-llvm/docs/api/namespaces/llvm/check">Check</a> if the edge between this block and the given successor <span class="doxyComputerOutput">Succ</span>, can be split.</p>


<p>If this returns true a subsequent call to SplitCriticalEdge is guaranteed to return a valid basic block if no changes occurred in the meantime.</p>


<p>Declaration at line 1007 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/codegen/machinebasicblock-h">MachineBasicBlock.h</a>, definition at line 1384 of file <a href="/web-llvm/docs/api/files/lib/lib/codegen/machinebasicblock-cpp">MachineBasicBlock.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/riscv/riscvredundantcopyelimination-cpp/#a193847098793cdbab306803186676899">Cond</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a7c46c742c31be54870e2038048e6b391">llvm::dbgs</a>, <a href="/web-llvm/docs/api/files/lib/lib/codegen/machinebasicblock-cpp/#a8694d520d0ec389dfe12068c5039131c">findJumpTableIndex</a>, <a href="/web-llvm/docs/api/classes/llvm/targetsubtargetinfo/#acd858ed72f11db9444617740c3622608">llvm::TargetSubtargetInfo::getInstrInfo</a>, <a href="#acf6442108e21e7e5379feb8962de65b7">getParent</a>, <a href="/web-llvm/docs/api/classes/llvm/machinefunction/#a3825368aca2bc1550d173660df4da6a6">llvm::MachineFunction::getSubtarget</a>, <a href="/web-llvm/docs/api/classes/llvm/machinefunction/#af777ff93c9e07a6ff5ffe3226deb3e76">llvm::MachineFunction::getTarget</a>, <a href="#a1100bfbadd996d464150c6a68fa8dc1d">isEHPad</a>, <a href="#a00e55a6b6b44b739e9da1d62f1d8a5b3">isInlineAsmBrIndirectTarget</a>, <a href="/web-llvm/docs/api/files/lib/lib/codegen/machinebasicblock-cpp/#a466674860524a217292797476e9ce371">jumpTableHasOtherUses</a>, <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/support/debug-h/#a196897517069dda1bdb549e24468f7d7">LLVM_DEBUG</a>, <a href="#ac423fefe048ace18159808c5592ae74c">MachineFunction</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#af7881286e3ea4d7f1c4a63c87c132dac">llvm::printMBBReference</a>, <a href="/web-llvm/docs/api/classes/llvm/targetmachine/#aa276e49983e93afa359ec83ad71ccadc">llvm::TargetMachine::requiresStructuredCFG</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/riscv/riscvredundantcopyelimination-cpp/#a1441f79530bc7f3a89118bb8067eac69">TBB</a> and <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/hexagon/hexagoncopytocombine-cpp/#a1d40004718218dbdf06b496766299101">TII</a>.</p>


<p>Referenced by <a href="#aa80aaa82844ab5560ece045eee7b34ac">SplitCriticalEdge</a>.</p>

</div>
</div>

### clear() {#a2be0839c1c2ac22d7c65f8a175105959}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void llvm::MachineBasicBlock::clear ()</td>
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



<p>Definition at line 1110 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/codegen/machinebasicblock-h">MachineBasicBlock.h</a>.</p>

</div>
</div>

### clearBasicBlock() {#a6cc466c26334b3089541986b21b4aa02}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void llvm::MachineBasicBlock::clearBasicBlock ()</td>
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

<p>Remove the reference to the underlying IR <a href="/web-llvm/docs/api/classes/llvm/basicblock">BasicBlock</a>.</p>


<p>This is for reduction tools and should generally not be used.</p>


<p>Definition at line 260 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/codegen/machinebasicblock-h">MachineBasicBlock.h</a>.</p>

</div>
</div>

### clearLiveIns() {#a7c9de323398db302bf33de488a780467}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void MachineBasicBlock::clearLiveIns ()</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Clear live in list.</p>

<p>Declaration at line 479 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/codegen/machinebasicblock-h">MachineBasicBlock.h</a>, definition at line 1743 of file <a href="/web-llvm/docs/api/files/lib/lib/codegen/machinebasicblock-cpp">MachineBasicBlock.cpp</a>.</p>

</div>
</div>

### clearLiveIns() {#a02bae4956974c41a4bad6b95f5d7cc1a}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void MachineBasicBlock::clearLiveIns (std::vector&lt; <a href="/web-llvm/docs/api/structs/llvm/machinebasicblock/registermaskpair">RegisterMaskPair</a> &gt; &amp; OldLiveIns)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Clear the live in list, and return the removed live in's in <span class="doxyComputerOutput">OldLiveIns</span>.</p>


<p>Requires that the vector <span class="doxyComputerOutput">OldLiveIns</span> is empty.</p>


<p>Declaration at line 483 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/codegen/machinebasicblock-h">MachineBasicBlock.h</a>, definition at line 1747 of file <a href="/web-llvm/docs/api/files/lib/lib/codegen/machinebasicblock-cpp">MachineBasicBlock.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/silowercontrolflow-cpp/#a4868c5d81c5ccc98c47aeab6244346a0">assert</a> and <a href="/web-llvm/docs/api/namespaces/std/#ab8424022895aee3e366fb9a32f2883cb">std::swap</a>.</p>

</div>
</div>

### computeRegisterLiveness() {#a7ebfe0cc2f78ae5f27e1944412606973}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">MachineBasicBlock::LivenessQueryResult MachineBasicBlock::computeRegisterLiveness (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/targetregisterinfo">TargetRegisterInfo</a> * TRI, <a href="/web-llvm/docs/api/classes/llvm/mcregister">MCRegister</a> Reg, <a href="#a199a6e4bfdffc8f3379ef4f35004488f">const_iterator</a> Before, unsigned Neighborhood=10)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Return whether (physical) register <span class="doxyComputerOutput">Reg</span> has been defined and not killed as of just before <span class="doxyComputerOutput">Before</span>.</p>


<p>Return whether (physical) register "Reg" has been &lt;def&gt;ined and not &lt;kill&gt;ed as of just before "MI".</p>


<p>Search is localised to a neighborhood of <span class="doxyComputerOutput">Neighborhood</span> instructions before (searching for defs or kills) and <span class="doxyComputerOutput">Neighborhood</span> instructions after (searching just for defs) <span class="doxyComputerOutput">Before</span>.</p>


<p><span class="doxyComputerOutput">Reg</span> must be a physical register.</p>


<p>Search is localised to a neighborhood of Neighborhood instructions before (searching for defs or kills) and N instructions after (searching just for defs) MI.</p>


<p>Declaration at line 1201 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/codegen/machinebasicblock-h">MachineBasicBlock.h</a>, definition at line 1632 of file <a href="/web-llvm/docs/api/files/lib/lib/codegen/machinebasicblock-cpp">MachineBasicBlock.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/namespaces/llvm/#a34ace715436fcbc42e83e196957b9f16">llvm::AnalyzePhysRegInBundle</a>, <a href="/web-llvm/docs/api/files/lib/lib/passes/standardinstrumentations-cpp/#a6f1bbcae7288f05872dcfe811d0388baa9060587edeb01a63e3d3edc959678d1e">Before</a>, <a href="#ab2d91e7bec944efcbc39d8e30644f111">begin</a>, <a href="#acbc921830578e2741be6549db716c0ce">end</a>, <a href="/web-llvm/docs/api/files/lib/lib/support/md5-cpp/#ac0eafdc9ee161b71e7af98af736952fd">I</a>, <a href="#a364ed6e68f92f797c0cd9e53ce5ea2a5">liveins</a>, <a href="#af0288e181965a5ff9f0c7a75201fd142a092531ae27becd74d96d4a6fae76f863">LQR_Dead</a>, <a href="#af0288e181965a5ff9f0c7a75201fd142accc15fa5c7a27d461dc9a884cc9a2dc8">LQR_Live</a>, <a href="#af0288e181965a5ff9f0c7a75201fd142af64367be349b6e7672de902ebecae068">LQR_Unknown</a>, <a href="/web-llvm/docs/api/files/lib/lib/support/regcomp-c/#a0240ac851181b84ac374872dc5434ee4">N</a>, <a href="#ad88ff1529541fb4e243cc8ed90b11131">successors</a> and <a href="/web-llvm/docs/api/files/lib/lib/codegen/machinesink-cpp/#a0f36ed1bc17fc1aa97fe291c439a0698">TRI</a>.</p>

</div>
</div>

### copySuccessor() {#a95933492048f0ea830f02f61b1329c12}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void MachineBasicBlock::copySuccessor (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/machinebasicblock">MachineBasicBlock</a> * Orig, <a href="#a9936e11d7a6149f7cac8fa32a81dd488">succ_iterator</a> I)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Copy a successor (and any probability info) from original block to this block's.</p>


<p>Uses an iterator into the original blocks successors.</p>


<p>This is useful when doing a partial clone of successors. Afterward, the probabilities may need to be normalized.</p>


<p>Declaration at line 804 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/codegen/machinebasicblock-h">MachineBasicBlock.h</a>, definition at line 899 of file <a href="/web-llvm/docs/api/files/lib/lib/codegen/machinebasicblock-cpp">MachineBasicBlock.cpp</a>.</p>


<p>References <a href="#a935e2a8884592189d8f261634a0b24c5">addSuccessor</a>, <a href="#a3f3061829632220504bb4a1cb819cfac">addSuccessorWithoutProb</a>, <a href="#a34b15764a81fb89e68d85d5aae76f20f">getSuccProbability</a> and <a href="/web-llvm/docs/api/files/lib/lib/support/md5-cpp/#ac0eafdc9ee161b71e7af98af736952fd">I</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/namespaces/anonymous-basicblockpathcloning-cpp-/#a0150e86671c87ec3046e8ba46be9f151">anonymous{BasicBlockPathCloning.cpp}::CloneMachineBasicBlock</a>.</p>

</div>
</div>

### dump() {#a8cec41e65c7ebf7da3e9d41f2317065e}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">LLVM_DUMP_METHOD void MachineBasicBlock::dump ()</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Declaration at line 1207 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/codegen/machinebasicblock-h">MachineBasicBlock.h</a>, definition at line 301 of file <a href="/web-llvm/docs/api/files/lib/lib/codegen/machinebasicblock-cpp">MachineBasicBlock.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/namespaces/llvm/#a7c46c742c31be54870e2038048e6b391">llvm::dbgs</a>, <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/support/compiler-h/#aa863693eef567397d9c292da5bf22d34">LLVM_DUMP_METHOD</a> and <a href="#ab3b62258d9bd41595674de878f37f8d8">print</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/classes/anonymous-cskyconstantislandpass-cpp-/cskyconstantislands/#a6159cb24e3496f5b8bd5e830e052aba1">anonymous{CSKYConstantIslandPass.cpp}::CSKYConstantIslands::doInitialPlacement</a>, <a href="/web-llvm/docs/api/classes/anonymous-mipsconstantislandpass-cpp-/mipsconstantislands/#a3068d2fa3c2556694ca3db57b7c197dd">anonymous{MipsConstantIslandPass.cpp}::MipsConstantIslands::doInitialPlacement</a>, <a href="/web-llvm/docs/api/classes/anonymous-x86flagscopylowering-cpp-/x86flagscopyloweringpass/#a30d90e84a3faa0cd7aa2c3b96d65c232">anonymous{X86FlagsCopyLowering.cpp}::X86FlagsCopyLoweringPass::runOnMachineFunction</a> and <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/powerpc/ppcreducecrlogicals-cpp/#a6268a1294b61555b575fbd131789aaf3">splitMBB</a>.</p>

</div>
</div>

### empty() {#a095ce2d870dadf620a4c887ecc0efef8}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool llvm::MachineBasicBlock::empty ()</td>
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



<p>Definition at line 336 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/codegen/machinebasicblock-h">MachineBasicBlock.h</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/files/lib/lib/codegen/tailduplicator-cpp/#a8d60ca423c44106297940619d9411856">bothUsedInPHI</a>, <a href="/web-llvm/docs/api/classes/llvm/ssaupdatertraits-4e613f36227a2a352217431a8f1958cd/#a0db03d5e2c460331af4ee0afaaec953a">llvm::SSAUpdaterTraits&lt; MachineSSAUpdater &gt;::CreateEmptyPHI</a>, <a href="#a31aa2680ec79198a4c94f35b3a1ad97e">getFallThrough</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/mips/mipsbranchexpansion-cpp/#a4801e594c6226fb9020a07ca36641c5b">getNextMachineInstr</a>, <a href="/web-llvm/docs/api/classes/llvm/machinessaupdater/#a670da7741129c7d591dc19951ecce6c3">llvm::MachineSSAUpdater::GetValueInMiddleOfBlock</a>, <a href="/web-llvm/docs/api/classes/llvm/aarch64instrinfo/#a538e94fb7d7a71910f3cbb5cd97aae0c">llvm::AArch64InstrInfo::insertIndirectBranch</a>, <a href="/web-llvm/docs/api/classes/llvm/riscvinstrinfo/#a63b280c848f7c74e68e3a6f45ffb4a85">llvm::RISCVInstrInfo::insertIndirectBranch</a>, <a href="/web-llvm/docs/api/classes/llvm/siinstrinfo/#aff3eb40a3be5c2fb6f804f1e5649fd57">llvm::SIInstrInfo::insertIndirectBranch</a>, <a href="/web-llvm/docs/api/classes/llvm/slotindexes/#a55bd6e17074a39a9aad2ee8cd6f541fb">llvm::SlotIndexes::insertMBBInMaps</a>, <a href="#adf1c64c05c8afb975b979543f8f850df">isEHScopeReturnBlock</a>, <a href="#a82f5d244972c88ff03ee56d6c090ac70">isReturnBlock</a>, <a href="/web-llvm/docs/api/namespaces/anonymous-basicblockpathcloning-cpp-/#abbaff7e4a8cdaa59924d29ba6e305f4a">anonymous{BasicBlockPathCloning.cpp}::IsValidCloning</a>, <a href="/web-llvm/docs/api/files/lib/lib/codegen/machinessaupdater-cpp/#a43b22ba78d684fd69b551c4c04426e3d">LookForIdenticalPHI</a>, <a href="/web-llvm/docs/api/classes/anonymous-ppcbranchcoalescing-cpp-/ppcbranchcoalescing/#a072a336f973a3de4daa8fe16e5b4570f">anonymous{PPCBranchCoalescing.cpp}::PPCBranchCoalescing::mergeCandidates</a>, <a href="/web-llvm/docs/api/files/lib/lib/codegen/machinesink-cpp/#a1e64ed92fc7b343fa59c28105e16b794">performSink</a>, <a href="/web-llvm/docs/api/classes/anonymous-cskyconstantislandpass-cpp-/cskyconstantislands/#a260e4fa04b4392ed7de8a9202292a2ca">anonymous{CSKYConstantIslandPass.cpp}::CSKYConstantIslands::removeDeadCPEMI</a>, <a href="/web-llvm/docs/api/classes/anonymous-mipsconstantislandpass-cpp-/mipsconstantislands/#abbda87d0f5c41ed3eca00b354a53417d">anonymous{MipsConstantIslandPass.cpp}::MipsConstantIslands::removeDeadCPEMI</a>, <a href="/web-llvm/docs/api/classes/anonymous-hexagoncfgoptimizer-cpp-/hexagoncfgoptimizer/#a44a6c0917383ba77dca7325a7b23c252">anonymous{HexagonCFGOptimizer.cpp}::HexagonCFGOptimizer::runOnMachineFunction</a> and <a href="/web-llvm/docs/api/classes/llvm/tailduplicator/#aa7dba30d4d9162f00367404e06085391">llvm::TailDuplicator::shouldTailDuplicate</a>.</p>

</div>
</div>

### end() {#acbc921830578e2741be6549db716c0ce}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">iterator llvm::MachineBasicBlock::end ()</td>
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



<p>Definition at line 366 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/codegen/machinebasicblock-h">MachineBasicBlock.h</a>.</p>


<p>Reference <a href="#acae72f6ab1071b7ec87b741a8bef582b">instr_end</a>.</p>


<p>Referenced by <a href="#a9bd7c04e374ad15665430a243dd30d80">addLiveIn</a>, <a href="/web-llvm/docs/api/classes/llvm/livevariables/#afbcff91139fc89e3e8c0dda857e7b128">llvm::LiveVariables::addNewBlock</a>, <a href="/web-llvm/docs/api/classes/llvm/livevariables/#afc347ae9e7fcba69b04162d7b4a73635">llvm::LiveVariables::addNewBlock</a>, <a href="/web-llvm/docs/api/classes/llvm/armframelowering/#a62042f5fd3a2df1b4fab2bfc692b2390">llvm::ARMFrameLowering::adjustForSegmentedStacks</a>, <a href="/web-llvm/docs/api/classes/llvm/armbaseinstrinfo/#a637fe9208c860066ecf02233cd258f9b">llvm::ARMBaseInstrInfo::analyzeLoopForPipelining</a>, <a href="/web-llvm/docs/api/classes/llvm/hexagoninstrinfo/#a5e0e04407d3397fa1b002c7559a33860">llvm::HexagonInstrInfo::analyzeLoopForPipelining</a>, <a href="/web-llvm/docs/api/classes/llvm/ppcinstrinfo/#adc8a417082dae00c6f459b63a65e0ed8">llvm::PPCInstrInfo::analyzeLoopForPipelining</a>, <a href="/web-llvm/docs/api/classes/anonymous-sifixsgprcopies-cpp-/sifixsgprcopies/#af8967731195e767bf313308f20b640de">anonymous{SIFixSGPRCopies.cpp}::SIFixSGPRCopies::analyzeVGPRToSGPRCopy</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/webassembly/webassemblycfgstackify-cpp/#a4669a9ca77f8a7a1b4458c3b98cab697">appendEndToFunction</a>, <a href="/web-llvm/docs/api/classes/anonymous-siinsertwaitcnts-cpp-/waitcntgeneratorgfx12plus/#a30a7745f58a481ca6495b35e202e4cce">anonymous{SIInsertWaitcnts.cpp}::WaitcntGeneratorGFX12Plus::applyPreexistingWaitcnt</a>, <a href="/web-llvm/docs/api/classes/anonymous-siinsertwaitcnts-cpp-/waitcntgeneratorpregfx12/#a83153660927a017cef8d173e5917f3a4">anonymous{SIInsertWaitcnts.cpp}::WaitcntGeneratorPreGFX12::applyPreexistingWaitcnt</a>, <a href="#acf35424231192c6b4a3e22d711f50b1e">back</a>, <a href="#a12b36a2272e92056473c7b59722afa14">back</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a7d605028fb7136428e6ead66bfa32bdb">llvm::BuildMI</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a94b3bd0804b21915716072c021bf7407">llvm::BuildMI</a>, <a href="/web-llvm/docs/api/classes/anonymous-ppcbranchcoalescing-cpp-/ppcbranchcoalescing/#a481db3ca9a03829503a402a2318a27b1">anonymous{PPCBranchCoalescing.cpp}::PPCBranchCoalescing::canMerge</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/m68k/m68kisellowering-cpp/#aed8bb289e710a4687f5dbdc1b0b35fd3">checkAndUpdateCCRKill</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/arm/armisellowering-cpp/#a551cf4f2a46a96b347d222acc8df059c">checkAndUpdateCPSRKill</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/x86/x86cmovconversion-cpp/#a84a6f842d324111ba3e11e8b0e547801">checkEFLAGSLive</a>, <a href="/web-llvm/docs/api/classes/llvm/errataworkaround/#a9ca7d3c709feb89bb21527a0b439c6ad">llvm::ErrataWorkaround::checkSeqTN0010</a>, <a href="/web-llvm/docs/api/classes/llvm/errataworkaround/#a97e744d4954c2bbf1ebf01f00ff11b42">llvm::ErrataWorkaround::checkSeqTN0012</a>, <a href="/web-llvm/docs/api/files/lib/lib/codegen/machinesink-cpp/#a084d504a7f8b42657e1c910ba098ad94">clearKillFlags</a>, <a href="/web-llvm/docs/api/namespaces/anonymous-basicblockpathcloning-cpp-/#a0150e86671c87ec3046e8ba46be9f151">anonymous{BasicBlockPathCloning.cpp}::CloneMachineBasicBlock</a>, <a href="/web-llvm/docs/api/files/lib/lib/codegen/branchfolding-cpp/#a0ff8a27be1a6683026280a4611628562">ComputeCommonTailLength</a>, <a href="#a7ebfe0cc2f78ae5f27e1944412606973">computeRegisterLiveness</a>, <a href="/web-llvm/docs/api/classes/llvm/ssaupdatertraits-4e613f36227a2a352217431a8f1958cd/#a0db03d5e2c460331af4ee0afaaec953a">llvm::SSAUpdaterTraits&lt; MachineSSAUpdater &gt;::CreateEmptyPHI</a>, <a href="/web-llvm/docs/api/classes/anonymous-cskyconstantislandpass-cpp-/cskyconstantislands/#aee171a94c094d78c3744e68795791b8d">anonymous{CSKYConstantIslandPass.cpp}::CSKYConstantIslands::createNewWater</a>, <a href="/web-llvm/docs/api/classes/anonymous-mipsconstantislandpass-cpp-/mipsconstantislands/#ac438bed7ae6afbb9ff9e0be02099ad0f">anonymous{MipsConstantIslandPass.cpp}::MipsConstantIslands::createNewWater</a>, <a href="/web-llvm/docs/api/structs/anonymous-machineoutliner-cpp-/machineoutliner/#a272487247e40605fc8a0ee848d4dcf44">anonymous{MachineOutliner.cpp}::MachineOutliner::createOutlinedFunction</a>, <a href="/web-llvm/docs/api/classes/anonymous-cskyconstantislandpass-cpp-/cskyconstantislands/#a6159cb24e3496f5b8bd5e830e052aba1">anonymous{CSKYConstantIslandPass.cpp}::CSKYConstantIslands::doInitialPlacement</a>, <a href="/web-llvm/docs/api/classes/anonymous-mipsconstantislandpass-cpp-/mipsconstantislands/#a3068d2fa3c2556694ca3db57b7c197dd">anonymous{MipsConstantIslandPass.cpp}::MipsConstantIslands::doInitialPlacement</a>, <a href="/web-llvm/docs/api/classes/llvm/ppctargetlowering/#a541b354a6386df6d03fcdc656d7d9db7">llvm::PPCTargetLowering::EmitAtomicBinary</a>, <a href="/web-llvm/docs/api/classes/llvm/riscvtargetlowering/#a7bafcec0aefe1c8144ce6cacdf80ff19">llvm::RISCVTargetLowering::emitDynamicProbedAlloc</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/riscv/riscvisellowering-cpp/#a90f911eb0622dc6ec5c1333369e495ac">emitFROUND</a>, <a href="/web-llvm/docs/api/classes/llvm/armtargetlowering/#a6820d09b4db5654cd1377d3ab63b3e01">llvm::ARMTargetLowering::EmitInstrWithCustomInserter</a>, <a href="/web-llvm/docs/api/classes/llvm/bpftargetlowering/#ac190f0cf5627568bd97cf1e5b24ce57d">llvm::BPFTargetLowering::EmitInstrWithCustomInserter</a>, <a href="/web-llvm/docs/api/classes/llvm/msp430targetlowering/#a948d164566e4b5aca48cf71cbf3a9ee3">llvm::MSP430TargetLowering::EmitInstrWithCustomInserter</a>, <a href="/web-llvm/docs/api/classes/llvm/ppctargetlowering/#a10d6f09e62a827099ec8b54efb4c035d">llvm::PPCTargetLowering::EmitInstrWithCustomInserter</a>, <a href="/web-llvm/docs/api/classes/llvm/r600targetlowering/#a3098f3c7fe942574303f81224b526094">llvm::R600TargetLowering::EmitInstrWithCustomInserter</a>, <a href="/web-llvm/docs/api/classes/llvm/sitargetlowering/#a92bd7eb8dcbdfa0341a4fe88a09941da">llvm::SITargetLowering::EmitInstrWithCustomInserter</a>, <a href="/web-llvm/docs/api/classes/llvm/xcoretargetlowering/#a13afdeda523046ab7176bead48d1c46f">llvm::XCoreTargetLowering::EmitInstrWithCustomInserter</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/siinstrinfo-cpp/#a476adf24d3374520fb31b2785f331d58">emitLoadScalarOpsFromVGPRLoop</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/riscv/riscvisellowering-cpp/#a4af8648d2e12301489dcc7b760f981ac">EmitLoweredCascadedSelect</a>, <a href="/web-llvm/docs/api/classes/llvm/ppctargetlowering/#a2e99e64e510ba34954d7fe85b1e30119">llvm::PPCTargetLowering::EmitPartwordAtomicBinary</a>, <a href="/web-llvm/docs/api/classes/llvm/ppctargetlowering/#a2cb46b1ded73af4c2924bd2d1d8db334">llvm::PPCTargetLowering::emitProbedAlloca</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/riscv/riscvisellowering-cpp/#ae20aef7ab8c13752bc5663fb0e6cbb1c">emitReadCounterWidePseudo</a>, <a href="/web-llvm/docs/api/classes/llvm/scheduledagsdnodes/#a6f60ed03227dbeb711a3ae9b1f0238e9">llvm::ScheduleDAGSDNodes::EmitSchedule</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/riscv/riscvisellowering-cpp/#a59f08a4b78badcbfff06545894a60e6e">emitSelectPseudo</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/csky/cskyisellowering-cpp/#a8e39c98d41d74a2147127a17c9800c7d">emitSelectPseudo</a>, <a href="/web-llvm/docs/api/classes/llvm/msp430targetlowering/#a33dd164bd4caf16d69db25a98f5d338f">llvm::MSP430TargetLowering::EmitShiftInstr</a>, <a href="/web-llvm/docs/api/classes/llvm/vetargetlowering/#a751f59893007a8fdcc892d81119abc82">llvm::VETargetLowering::emitSjLjDispatchBlock</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/riscv/riscvframelowering-cpp/#a30a608df0c31b4ad3814cce66364082c">emitStackProbeInline</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/loongarch/loongarchisellowering-cpp/#accb97b288f5b7b78cc16845a383fc13c">emitVecCondBranchPseudo</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/gcnhazardrecognizer-cpp/#accecdb72ed09118005742bcd44b08440">ensureEntrySetPrio</a>, <a href="/web-llvm/docs/api/classes/llvm/scheduledagmilive/#a34481791fdd8f5d9131431cb0a1a0c01">llvm::ScheduleDAGMILive::enterRegion</a>, <a href="/web-llvm/docs/api/classes/llvm/amdgpuregisterbankinfo/#a533cd1035e03cdca3da433e98e77e430">llvm::AMDGPURegisterBankInfo::executeInWaterfallLoop</a>, <a href="/web-llvm/docs/api/classes/llvm/veinstrinfo/#ad99d6c93063cbfe0bf0f995a0cf12552">llvm::VEInstrInfo::expandExtendStackPseudo</a>, <a href="/web-llvm/docs/api/classes/llvm/sparctargetlowering/#a216c0fdb0cdd991dcf320bd42ff4c39e">llvm::SparcTargetLowering::expandSelectCC</a>, <a href="#ad81901d0d8b768b240e78bf357999f34">findBranchDebugLoc</a>, <a href="/web-llvm/docs/api/namespaces/llvm/webassembly/#a6cc6351696a872f05cdf540a663d584c">llvm::WebAssembly::findCatch</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/lib/target/aarch64/gisel/aarch64instructionselector-cpp/#aafb37937e5f21c12443bd5278264d08b">fixupPHIOpBanks</a>, <a href="/web-llvm/docs/api/structs/llvm/rdf/liveness/#a0c3a1721c534dbc63fdc081a9365fd9c">llvm::rdf::Liveness::getAllReachingDefs</a>, <a href="#a31aa2680ec79198a4c94f35b3a1ad97e">getFallThrough</a>, <a href="#a62b5d2211c09378c471307293453d780">getFirstNonDebugInstr</a>, <a href="#a7f0521fa2de44271fd4b909ea7351ef3">getFirstTerminator</a>, <a href="#ab8d7b8ff6803133d567fd4240e6364ce">getLastNonDebugInstr</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/mips/mipsbranchexpansion-cpp/#a4801e594c6226fb9020a07ca36641c5b">getNextMachineInstr</a>, <a href="/web-llvm/docs/api/classes/llvm/machinessaupdater/#a670da7741129c7d591dc19951ecce6c3">llvm::MachineSSAUpdater::GetValueInMiddleOfBlock</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64collectloh-cpp/#a897e4640c14c6556e0b1bc06eca81134">handleADRP</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/lanai/lanaimemalucombiner-cpp/#a3d8451ff05b58b604cb87a1623ef73b3">INITIALIZE_PASS</a>, <a href="/web-llvm/docs/api/classes/llvm/ppcframelowering/#af0a5a3bd252aaac7b161ad8c01cf0951">llvm::PPCFrameLowering::inlineStackProbe</a>, <a href="/web-llvm/docs/api/classes/llvm/x86framelowering/#a91705445bd9fc240a0092580cab1d092">llvm::X86FrameLowering::inlineStackProbe</a>, <a href="#afc15ef658764e1532ae80037d5d6ba6d">insert</a>, <a href="#a80512774162f8a8d15bd6e3b6739cf9b">insert</a>, <a href="#adbcec9820951b0e3872c94cbd4e57c80">insertAfter</a>, <a href="/web-llvm/docs/api/classes/llvm/aarch64instrinfo/#a538e94fb7d7a71910f3cbb5cd97aae0c">llvm::AArch64InstrInfo::insertIndirectBranch</a>, <a href="/web-llvm/docs/api/classes/llvm/loongarchinstrinfo/#a7a51fbf2432530ad72f0a3996b993a7f">llvm::LoongArchInstrInfo::insertIndirectBranch</a>, <a href="/web-llvm/docs/api/classes/llvm/riscvinstrinfo/#a63b280c848f7c74e68e3a6f45ffb4a85">llvm::RISCVInstrInfo::insertIndirectBranch</a>, <a href="/web-llvm/docs/api/classes/llvm/xtensainstrinfo/#a593e32f55b5d5133887cf7feb7999792">llvm::XtensaInstrInfo::insertIndirectBranch</a>, <a href="/web-llvm/docs/api/classes/llvm/siinstrinfo/#a7dbf2885fa89980322c2f4b58f85ff18">llvm::SIInstrInfo::insertSimulatedTrap</a>, <a href="/web-llvm/docs/api/files/lib/lib/codegen/branchfolding-cpp/#acda790896623fd894c71bf79f1bbcfea">IsBetterFallthrough</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/x86/x86isellowering-cpp/#af10cf44c8132db33091188f9530e9dee">isEFLAGSLiveAfter</a>, <a href="/web-llvm/docs/api/classes/llvm/reachingdefanalysis/#a09e2271431de53cc4cc5057148c18c93">llvm::ReachingDefAnalysis::isSafeToMoveForwards</a>, <a href="/web-llvm/docs/api/classes/llvm/tailduplicator/#a22b5f49c33bc7b11d150556b0ee1ca0a">llvm::TailDuplicator::isSimpleBB</a>, <a href="/web-llvm/docs/api/classes/llvm/amdgpulegalizerinfo/#aff7dfc9d1d4355acbd741d76ce27fca1">llvm::AMDGPULegalizerInfo::legalizeTrapEndpgm</a>, <a href="/web-llvm/docs/api/files/lib/lib/codegen/machinessaupdater-cpp/#a43b22ba78d684fd69b551c4c04426e3d">LookForIdenticalPHI</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/webassembly/webassemblyisellowering-cpp/#a01bea37475bf9a1f853b90975dbf7605">LowerFPToInt</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/webassembly/webassemblyisellowering-cpp/#a1b22ed476a56f8583de43854dfe57830">LowerMemcpy</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/webassembly/webassemblyisellowering-cpp/#aa603afd757ff3057f96bf5c1ee83e8b2">LowerMemset</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/siisellowering-cpp/#a7809852647bc7e8ceed1f287b2d03125">lowerWaveReduce</a>, <a href="/web-llvm/docs/api/classes/llvm/machineinstrspan/#a6d3c33032876211778d613690be1a5be">llvm::MachineInstrSpan::MachineInstrSpan</a>, <a href="/web-llvm/docs/api/classes/anonymous-r600machinecfgstructurizer-cpp-/r600machinecfgstructurizer/#aa76d1bb8a35c5fe0c9c22df9cc0dba10">anonymous{R600MachineCFGStructurizer.cpp}::R600MachineCFGStructurizer::mergeIfthenelseBlock</a>, <a href="/web-llvm/docs/api/classes/anonymous-r600machinecfgstructurizer-cpp-/r600machinecfgstructurizer/#a5fec9aab7a2ff820c3c372f3cda87c25">anonymous{R600MachineCFGStructurizer.cpp}::R600MachineCFGStructurizer::mergeSerialBlock</a>, <a href="/web-llvm/docs/api/classes/anonymous-r600machinecfgstructurizer-cpp-/r600machinecfgstructurizer/#a34b11aa12929fbf594b75074a35dc9c2">anonymous{R600MachineCFGStructurizer.cpp}::R600MachineCFGStructurizer::migrateInstruction</a>, <a href="/web-llvm/docs/api/classes/anonymous-hexagoncopyhoisting-cpp-/hexagoncopyhoisting/#a4fc59ce12e2dc07246561737f195c0c6">anonymous{HexagonCopyHoisting.cpp}::HexagonCopyHoisting::moveCopyInstr</a>, <a href="/web-llvm/docs/api/classes/llvm/peelingmoduloscheduleexpander/#afe809699537758032938bea41ea44bb7">llvm::PeelingModuloScheduleExpander::moveStageBetweenBlocks</a>, <a href="/web-llvm/docs/api/classes/anonymous-aarch64redundantcopyelimination-cpp-/aarch64redundantcopyelimination/#a1ee0cfcd17ed3a5b4826b8a5f93e50e1">anonymous{AArch64RedundantCopyElimination.cpp}::AArch64RedundantCopyElimination::optimizeBlock</a>, <a href="/web-llvm/docs/api/classes/llvm/armbaseinstrinfo/#a12cb817575a9c4141e5a1268e6821503">llvm::ARMBaseInstrInfo::optimizeCompareInstr</a>, <a href="/web-llvm/docs/api/classes/llvm/lanaiinstrinfo/#ac3660ab4e1d66ed8457df619aa1bfec1">llvm::LanaiInstrInfo::optimizeCompareInstr</a>, <a href="/web-llvm/docs/api/classes/llvm/ppcinstrinfo/#a8118d9f62c345028220579c9d1ca4061">llvm::PPCInstrInfo::optimizeCompareInstr</a>, <a href="/web-llvm/docs/api/classes/llvm/x86instrinfo/#a08a488100b4cc4464d879a987e490915">llvm::X86InstrInfo::optimizeCompareInstr</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a0fdc13bfd373951ae6163637d6576c39">llvm::PeelSingleBlockLoop</a>, <a href="/web-llvm/docs/api/files/lib/lib/codegen/machinesink-cpp/#a1e64ed92fc7b343fa59c28105e16b794">performSink</a>, <a href="/web-llvm/docs/api/classes/llvm/aarch64instrinfo/#ab9deb47df6ac29c81422ae6b4bfd924d">llvm::AArch64InstrInfo::probedStackAlloc</a>, <a href="/web-llvm/docs/api/structs/anonymous-ppcearlyreturn-cpp-/ppcearlyreturn/#ae036500138a9ae1567af6b28547cf045">anonymous{PPCEarlyReturn.cpp}::PPCEarlyReturn::processBlock</a>, <a href="/web-llvm/docs/api/files/lib/lib/codegen/branchfolding-cpp/#a905140abedaee343fc7ef33707052792">ProfitableToMerge</a>, <a href="/web-llvm/docs/api/classes/llvm/armblockplacement/#a977d1a0dea04c7f562cb1ca6063d81dd">llvm::ARMBlockPlacement::revertWhileToDoLoop</a>, <a href="/web-llvm/docs/api/files/lib/lib/codegen/shrinkwrap-cpp/#a5aa69466ef430dc4ba4de70307ae4415">rollbackRestoreSplit</a>, <a href="/web-llvm/docs/api/files/lib/lib/codegen/finalizeisel-cpp/#a6395b072c4fb781dca4789de8aba1f55">runImpl</a>, <a href="/web-llvm/docs/api/classes/anonymous-siinsertwaitcnts-cpp-/siinsertwaitcnts/#aab6a5b3788b7384e1928f2ccd79f26b7">anonymous{SIInsertWaitcnts.cpp}::SIInsertWaitcnts::runOnMachineFunction</a>, <a href="/web-llvm/docs/api/classes/anonymous-silatebranchlowering-cpp-/silatebranchlowering/#a2f96cc01100e6467c2b124371cf417c0">anonymous{SILateBranchLowering.cpp}::SILateBranchLowering::runOnMachineFunction</a>, <a href="/web-llvm/docs/api/classes/anonymous-webassemblyargumentmove-cpp-/webassemblyargumentmove/#aa44a7b836eacb5db2df92e3ae85693ef">anonymous{WebAssemblyArgumentMove.cpp}::WebAssemblyArgumentMove::runOnMachineFunction</a>, <a href="/web-llvm/docs/api/classes/anonymous-x86winfixupbuffersecuritycheck-cpp-/x86winfixupbuffersecuritycheckpass/#a72a62fe526ad0cd3c24cfe003d363df0">anonymous{X86WinFixupBufferSecurityCheck.cpp}::X86WinFixupBufferSecurityCheckPass::runOnMachineFunction</a>, <a href="#af897d8e9556478c1442c739ce664bcb6">sizeWithoutDebugLargerThan</a>, <a href="#a3be7d94076d328797ab57ce09cefab33">SkipPHIsAndLabels</a>, <a href="#a5d8a45757c9861d499cba1a0d54e2c1e">SkipPHIsLabelsAndDebug</a>, <a href="/web-llvm/docs/api/classes/llvm/siregisterinfo/#a3d4103d19eae05425cf7aee3ad915250">llvm::SIRegisterInfo::spillEmergencySGPR</a>, <a href="#ac0bfa894f538166cb476b439a2cb0aea">splitAt</a>, <a href="/web-llvm/docs/api/classes/anonymous-x86winfixupbuffersecuritycheck-cpp-/x86winfixupbuffersecuritycheckpass/#a4a9e94af76b18840bb6b75a873b41010">anonymous{X86WinFixupBufferSecurityCheck.cpp}::X86WinFixupBufferSecurityCheckPass::SplitBasicBlock</a>, <a href="/web-llvm/docs/api/classes/anonymous-cskyconstantislandpass-cpp-/cskyconstantislands/#ae708a0dc9c80038ba6d971c94eb9db5c">anonymous{CSKYConstantIslandPass.cpp}::CSKYConstantIslands::splitBlockBeforeInstr</a>, <a href="/web-llvm/docs/api/classes/anonymous-mipsconstantislandpass-cpp-/mipsconstantislands/#a747abf73a79323919b62fb98e61aeaf2">anonymous{MipsConstantIslandPass.cpp}::MipsConstantIslands::splitBlockBeforeInstr</a>, <a href="#aa80aaa82844ab5560ece045eee7b34ac">SplitCriticalEdge</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/powerpc/ppcreducecrlogicals-cpp/#a6268a1294b61555b575fbd131789aaf3">splitMBB</a>, <a href="#ad56ff27a502cd519f9aaf5cc028b4ea5">terminators</a>, <a href="#aadfc2f6425b15faff5ce2421cc708205">terminators</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/gcnhazardrecognizer-cpp/#a3dc1ad6a578f69fed203a6022699080f">updateGetPCBundle</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/amdgpulegalizerinfo-cpp/#a87e58e9d24983c7890c502fbe731f950">verifyCFIntrinsic</a>, <a href="/web-llvm/docs/api/structs/anonymous-aarch64cleanuplocaldynamictlspass-cpp-/ldtlscleanup/#a047e1c70e1f34092b00f1c8b2d969778">anonymous{AArch64CleanupLocalDynamicTLSPass.cpp}::LDTLSCleanup::VisitNode</a> and <a href="/web-llvm/docs/api/structs/anonymous-x86instrinfo-cpp-/ldtlscleanup/#a96815d10911f05b2612864c5ee82f5d4">anonymous{X86InstrInfo.cpp}::LDTLSCleanup::VisitNode</a>.</p>

</div>
</div>

### end() {#aec6d7041bedf7535f7565f3e9471a5bd}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">const_iterator llvm::MachineBasicBlock::end ()</td>
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



<p>Definition at line 367 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/codegen/machinebasicblock-h">MachineBasicBlock.h</a>.</p>


<p>Reference <a href="#acae72f6ab1071b7ec87b741a8bef582b">instr_end</a>.</p>

</div>
</div>

### erase() {#ad26bff839257f220557ce812b2159c72}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">MachineBasicBlock::instr_iterator MachineBasicBlock::erase (<a href="#ab6395548cae73865213e279ae461db54">instr_iterator</a> I)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Remove an instruction from the instruction list and delete it.</p>


<p>If the instruction is part of a bundle, the other instructions in the bundle will still be bundled after removing the single instruction.</p>


<p>Declaration at line 1063 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/codegen/machinebasicblock-h">MachineBasicBlock.h</a>, definition at line 1443 of file <a href="/web-llvm/docs/api/files/lib/lib/codegen/machinebasicblock-cpp">MachineBasicBlock.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/files/lib/lib/support/md5-cpp/#ac0eafdc9ee161b71e7af98af736952fd">I</a> and <a href="/web-llvm/docs/api/files/lib/lib/codegen/machinebasicblock-cpp/#a6373a450215747746eb3eeeccc3d45f1">unbundleSingleMI</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/classes/llvm/armtargetlowering/#a6820d09b4db5654cd1377d3ab63b3e01">llvm::ARMTargetLowering::EmitInstrWithCustomInserter</a>, <a href="#aeb9c4dcc4993b06ce44b8d5ae1c7702b">erase</a>, <a href="#a0c194a99e410c07d2e694d4c802de0ab">erase</a>, <a href="#a3a892dcf265c384644ffac47d97b7e53">erase_instr</a>, <a href="/web-llvm/docs/api/classes/llvm/machineinstr/#ac2421adbb9996e1b15f03a8abb6c70a8">llvm::MachineInstr::eraseFromParent</a>, <a href="/web-llvm/docs/api/classes/anonymous-cskyconstantislandpass-cpp-/cskyconstantislands/#a800f62f10fe1fafc076ae4002371ba45">anonymous{CSKYConstantIslandPass.cpp}::CSKYConstantIslands::handleConstantPoolUser</a>, <a href="/web-llvm/docs/api/classes/anonymous-mipsconstantislandpass-cpp-/mipsconstantislands/#a4d3a04a082a7dd5b285cddb7feef368c">anonymous{MipsConstantIslandPass.cpp}::MipsConstantIslands::handleConstantPoolUser</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/hexagon/hexagongenmemabsolute-cpp/#a88a18d17d81c22fad6a400689ff6192e">INITIALIZE_PASS</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/lanai/lanaimemalucombiner-cpp/#a3d8451ff05b58b604cb87a1623ef73b3">INITIALIZE_PASS</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/x86/x86expandpseudo-cpp/#ab768c8179d2c43f28c8082df2f42b026">INITIALIZE_PASS</a>, <a href="/web-llvm/docs/api/structs/anonymous-aarch64slshardening-cpp-/slshardeninginserter/#aa0294873aedbdc7244e1ca9aa115889e">anonymous{AArch64SLSHardening.cpp}::SLSHardeningInserter::populateThunk</a>, <a href="/web-llvm/docs/api/files/lib/lib/codegen/shrinkwrap-cpp/#a5aa69466ef430dc4ba4de70307ae4415">rollbackRestoreSplit</a>, <a href="/web-llvm/docs/api/classes/anonymous-hexagoncfgoptimizer-cpp-/hexagoncfgoptimizer/#a44a6c0917383ba77dca7325a7b23c252">anonymous{HexagonCFGOptimizer.cpp}::HexagonCFGOptimizer::runOnMachineFunction</a> and <a href="/web-llvm/docs/api/classes/anonymous-hexagonvextract-cpp-/hexagonvextract/#ae163c69bb53c3aa811348aa9547a4ebb">anonymous{HexagonVExtract.cpp}::HexagonVExtract::runOnMachineFunction</a>.</p>

</div>
</div>

### erase() {#a6707fe3d50909e1409802995d5829c72}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">iterator llvm::MachineBasicBlock::erase (<a href="#ae34c996b58df9b9ce6695a0c8b70c533">iterator</a> I, <a href="#ae34c996b58df9b9ce6695a0c8b70c533">iterator</a> E)</td>
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

<p>Remove a range of instructions from the instruction list and delete them.</p>

<p>Definition at line 1074 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/codegen/machinebasicblock-h">MachineBasicBlock.h</a>.</p>


<p>References <a href="/web-llvm/docs/api/files/lib/lib/ir/builtingcs-cpp/#abb2b3a60ccc38a28239e19a1646e0c8a">E</a> and <a href="/web-llvm/docs/api/files/lib/lib/support/md5-cpp/#ac0eafdc9ee161b71e7af98af736952fd">I</a>.</p>

</div>
</div>

### erase() {#aeb9c4dcc4993b06ce44b8d5ae1c7702b}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">iterator llvm::MachineBasicBlock::erase (<a href="#ae34c996b58df9b9ce6695a0c8b70c533">iterator</a> I)</td>
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

<p>Remove an instruction or bundle from the instruction list and delete it.</p>


<p>If I points to a bundle of instructions, they are all erased.</p>


<p>Definition at line 1081 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/codegen/machinebasicblock-h">MachineBasicBlock.h</a>.</p>


<p>References <a href="#ad26bff839257f220557ce812b2159c72">erase</a> and <a href="/web-llvm/docs/api/files/lib/lib/support/md5-cpp/#ac0eafdc9ee161b71e7af98af736952fd">I</a>.</p>

</div>
</div>

### erase() {#a0c194a99e410c07d2e694d4c802de0ab}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">iterator llvm::MachineBasicBlock::erase (<a href="/web-llvm/docs/api/classes/llvm/machineinstr">MachineInstr</a> * I)</td>
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

<p>Remove an instruction from the instruction list and delete it.</p>


<p>If I is the head of a bundle of instructions, the whole bundle will be erased.</p>


<p>Definition at line 1089 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/codegen/machinebasicblock-h">MachineBasicBlock.h</a>.</p>


<p>References <a href="#ad26bff839257f220557ce812b2159c72">erase</a> and <a href="/web-llvm/docs/api/files/lib/lib/support/md5-cpp/#ac0eafdc9ee161b71e7af98af736952fd">I</a>.</p>

</div>
</div>

### erase\_instr() {#a3a892dcf265c384644ffac47d97b7e53}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">instr_iterator llvm::MachineBasicBlock::erase_instr (<a href="/web-llvm/docs/api/classes/llvm/machineinstr">MachineInstr</a> * I)</td>
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

<p>Remove an instruction from the instruction list and delete it.</p>


<p>If the instruction is part of a bundle, the other instructions in the bundle will still be bundled after removing the single instruction.</p>


<p>Definition at line 1069 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/codegen/machinebasicblock-h">MachineBasicBlock.h</a>.</p>


<p>References <a href="#ad26bff839257f220557ce812b2159c72">erase</a> and <a href="/web-llvm/docs/api/files/lib/lib/support/md5-cpp/#ac0eafdc9ee161b71e7af98af736952fd">I</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/classes/llvm/machineinstr/#a9891e442de101ced8a1533a71511dbed">llvm::MachineInstr::eraseFromBundle</a>.</p>

</div>
</div>

### eraseFromParent() {#ac421fe6513e43aedbba712e4a981744e}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void MachineBasicBlock::eraseFromParent ()</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>This method unlinks 'this' from the containing function and deletes it.</p>


<p>This method unlinks 'this' from the containing function, and deletes it.</p>


<p>Declaration at line 1140 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/codegen/machinebasicblock-h">MachineBasicBlock.h</a>, definition at line 1476 of file <a href="/web-llvm/docs/api/files/lib/lib/codegen/machinebasicblock-cpp">MachineBasicBlock.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/silowercontrolflow-cpp/#a4868c5d81c5ccc98c47aeab6244346a0">assert</a>, <a href="/web-llvm/docs/api/classes/llvm/machinefunction/#ae986afe2285d3980b27aa9763f3203e9">llvm::MachineFunction::erase</a> and <a href="#acf6442108e21e7e5379feb8962de65b7">getParent</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/classes/llvm/machinedomtreeupdater/#a37347c3bcb72b1a6c2ab0b5dc28cb34b">llvm::MachineDomTreeUpdater::deleteBB</a>, <a href="/web-llvm/docs/api/classes/anonymous-ppcbranchcoalescing-cpp-/ppcbranchcoalescing/#a072a336f973a3de4daa8fe16e5b4570f">anonymous{PPCBranchCoalescing.cpp}::PPCBranchCoalescing::mergeCandidates</a>, <a href="/web-llvm/docs/api/structs/anonymous-ppcearlyreturn-cpp-/ppcearlyreturn/#ae036500138a9ae1567af6b28547cf045">anonymous{PPCEarlyReturn.cpp}::PPCEarlyReturn::processBlock</a> and <a href="/web-llvm/docs/api/files/lib/lib/codegen/shrinkwrap-cpp/#a5aa69466ef430dc4ba4de70307ae4415">rollbackRestoreSplit</a>.</p>

</div>
</div>

### findBranchDebugLoc() {#ad81901d0d8b768b240e78bf357999f34}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">DebugLoc MachineBasicBlock::findBranchDebugLoc ()</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Find and return the merged <a href="/web-llvm/docs/api/classes/llvm/debugloc">DebugLoc</a> of the branch instructions of the block.</p>


<p>Return UnknownLoc if there is none.</p>


<p>Declaration at line 1184 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/codegen/machinebasicblock-h">MachineBasicBlock.h</a>, definition at line 1559 of file <a href="/web-llvm/docs/api/files/lib/lib/codegen/machinebasicblock-cpp">MachineBasicBlock.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/arm/armslshardening-cpp/#ad467c4ab9119043f9b7750ab986be61a">DL</a>, <a href="#acbc921830578e2741be6549db716c0ce">end</a>, <a href="#a7f0521fa2de44271fd4b909ea7351ef3">getFirstTerminator</a> and <a href="/web-llvm/docs/api/classes/llvm/dilocation/#a78cc51c415c7e64b5efe2c8458fbd35a">llvm::DILocation::getMergedLocation</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/namespaces/anonymous-basicblockpathcloning-cpp-/#a09842318dc1064ae48b19d91e2cb11aa">anonymous{BasicBlockPathCloning.cpp}::ApplyCloning</a>, <a href="/web-llvm/docs/api/namespaces/anonymous-basicblockpathcloning-cpp-/#a0150e86671c87ec3046e8ba46be9f151">anonymous{BasicBlockPathCloning.cpp}::CloneMachineBasicBlock</a>, <a href="/web-llvm/docs/api/files/lib/lib/codegen/branchfolding-cpp/#abbe6276e99bb565156d18a843ae1ccb9">FixTail</a>, <a href="/web-llvm/docs/api/classes/llvm/mirprofileloader/#a31f2c5f323ca8742d0588171e0c33b49">llvm::MIRProfileLoader::setBranchProbs</a>, <a href="#aa80aaa82844ab5560ece045eee7b34ac">SplitCriticalEdge</a>, <a href="#a5803a49facae20ca4b002dcba6f1d03e">updateTerminator</a> and <a href="/web-llvm/docs/api/files/lib/lib/codegen/shrinkwrap-cpp/#a0d669f3a4d6e865cc9d89c43e230976f">updateTerminator</a>.</p>

</div>
</div>

### findDebugLoc() {#ab622d694b5fcb0edb99159f1ebdcdb6b}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">DebugLoc MachineBasicBlock::findDebugLoc (<a href="#ab6395548cae73865213e279ae461db54">instr_iterator</a> MBBI)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Find the next valid <a href="/web-llvm/docs/api/classes/llvm/debugloc">DebugLoc</a> starting at MBBI, skipping any debug instructions.</p>


<p>Return UnknownLoc if there is none.</p>


<p>Declaration at line 1152 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/codegen/machinebasicblock-h">MachineBasicBlock.h</a>, definition at line 1516 of file <a href="/web-llvm/docs/api/files/lib/lib/codegen/machinebasicblock-cpp">MachineBasicBlock.cpp</a>.</p>


<p>References <a href="#acae72f6ab1071b7ec87b741a8bef582b">instr_end</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/arm/armslshardening-cpp/#ad5f691fdc1a09aaf6df5fef958b35a3d">MBBI</a> and <a href="/web-llvm/docs/api/namespaces/llvm/#a5bacbbd03e9261f7b30dc174f26d680c">llvm::skipDebugInstructionsForward</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/classes/llvm/r600targetlowering/#a3098f3c7fe942574303f81224b526094">llvm::R600TargetLowering::EmitInstrWithCustomInserter</a>, <a href="#aa2e30b8dd8b4aecfff7f7f5bfa90cff2">findDebugLoc</a>, <a href="/web-llvm/docs/api/classes/llvm/ppcframelowering/#af0a5a3bd252aaac7b161ad8c01cf0951">llvm::PPCFrameLowering::inlineStackProbe</a>, <a href="/web-llvm/docs/api/classes/llvm/x86framelowering/#a91705445bd9fc240a0092580cab1d092">llvm::X86FrameLowering::inlineStackProbe</a>, <a href="#ab2192a3dc7e43ace4706a00258bf5f47">rfindDebugLoc</a>, <a href="/web-llvm/docs/api/structs/anonymous-m68kinstrinfo-cpp-/m68kglobalbasereg/#a04412e72586680e6bfb4ced5a69102c2">anonymous{M68kInstrInfo.cpp}::M68kGlobalBaseReg::runOnMachineFunction</a> and <a href="/web-llvm/docs/api/structs/anonymous-x86instrinfo-cpp-/cgbr/#ae7e54015b8e4160365d925c1bd46004f">anonymous{X86InstrInfo.cpp}::CGBR::runOnMachineFunction</a>.</p>

</div>
</div>

### findDebugLoc() {#aa2e30b8dd8b4aecfff7f7f5bfa90cff2}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">DebugLoc llvm::MachineBasicBlock::findDebugLoc (<a href="#ae34c996b58df9b9ce6695a0c8b70c533">iterator</a> MBBI)</td>
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



<p>Definition at line 1153 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/codegen/machinebasicblock-h">MachineBasicBlock.h</a>.</p>


<p>References <a href="#ab622d694b5fcb0edb99159f1ebdcdb6b">findDebugLoc</a> and <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/arm/armslshardening-cpp/#ad5f691fdc1a09aaf6df5fef958b35a3d">MBBI</a>.</p>

</div>
</div>

### findPrevDebugLoc() {#abfe76200d04557c617e5f505717c3ad3}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">DebugLoc MachineBasicBlock::findPrevDebugLoc (<a href="#ab6395548cae73865213e279ae461db54">instr_iterator</a> MBBI)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Find the previous valid <a href="/web-llvm/docs/api/classes/llvm/debugloc">DebugLoc</a> preceding MBBI, skipping any debug instructions.</p>


<p>It is possible to find the last <a href="/web-llvm/docs/api/classes/llvm/debugloc">DebugLoc</a> in the MBB using findPrevDebugLoc(instr_end()). Return UnknownLoc if there is none.</p>


<p>Return UnknownLoc if there is none.</p>


<p>Declaration at line 1168 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/codegen/machinebasicblock-h">MachineBasicBlock.h</a>, definition at line 1536 of file <a href="/web-llvm/docs/api/files/lib/lib/codegen/machinebasicblock-cpp">MachineBasicBlock.cpp</a>.</p>


<p>References <a href="#a172e7bd9150eb0519ef04c796086f93d">instr_begin</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/arm/armslshardening-cpp/#ad5f691fdc1a09aaf6df5fef958b35a3d">MBBI</a> and <a href="/web-llvm/docs/api/namespaces/llvm/#ae74dcdb801fe44b3840dd93e6c395066">llvm::prev_nodbg</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/webassembly/webassemblycfgstackify-cpp/#a4669a9ca77f8a7a1b4458c3b98cab697">appendEndToFunction</a> and <a href="#ad4aa6f6ff5e863a2e26dc79531ff56d5">findPrevDebugLoc</a>.</p>

</div>
</div>

### findPrevDebugLoc() {#ad4aa6f6ff5e863a2e26dc79531ff56d5}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">DebugLoc llvm::MachineBasicBlock::findPrevDebugLoc (<a href="#ae34c996b58df9b9ce6695a0c8b70c533">iterator</a> MBBI)</td>
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



<p>Definition at line 1169 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/codegen/machinebasicblock-h">MachineBasicBlock.h</a>.</p>


<p>References <a href="#abfe76200d04557c617e5f505717c3ad3">findPrevDebugLoc</a> and <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/arm/armslshardening-cpp/#ad5f691fdc1a09aaf6df5fef958b35a3d">MBBI</a>.</p>

</div>
</div>

### front() {#aeedc2554f9637d1e27befa7a85c70ec9}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">MachineInstr &amp; llvm::MachineBasicBlock::front ()</td>
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



<p>Definition at line 343 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/codegen/machinebasicblock-h">MachineBasicBlock.h</a>.</p>


<p>Referenced by <a href="#a9bd7c04e374ad15665430a243dd30d80">addLiveIn</a>, <a href="/web-llvm/docs/api/structs/anonymous-machineoutliner-cpp-/machineoutliner/#a272487247e40605fc8a0ee848d4dcf44">anonymous{MachineOutliner.cpp}::MachineOutliner::createOutlinedFunction</a>, <a href="/web-llvm/docs/api/classes/llvm/machinefunction/#afd05b72c03616b8b9a97f1a282a257f8">llvm::MachineFunction::front</a>, <a href="/web-llvm/docs/api/classes/llvm/machinefunction/#ac8ca28de0f4dcee651340e7ef0c45233">llvm::MachineFunction::front</a>, <a href="/web-llvm/docs/api/classes/llvm/slotindexes/#a55bd6e17074a39a9aad2ee8cd6f541fb">llvm::SlotIndexes::insertMBBInMaps</a>, <a href="/web-llvm/docs/api/structs/anonymous-aarch64slshardening-cpp-/slshardeninginserter/#aa0294873aedbdc7244e1ca9aa115889e">anonymous{AArch64SLSHardening.cpp}::SLSHardeningInserter::populateThunk</a> and <a href="/web-llvm/docs/api/classes/anonymous-hexagoncfgoptimizer-cpp-/hexagoncfgoptimizer/#a44a6c0917383ba77dca7325a7b23c252">anonymous{HexagonCFGOptimizer.cpp}::HexagonCFGOptimizer::runOnMachineFunction</a>.</p>

</div>
</div>

### front() {#a68cc6dfc001c6d7140cee1c7f3e37a48}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">const MachineInstr &amp; llvm::MachineBasicBlock::front ()</td>
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



<p>Definition at line 345 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/codegen/machinebasicblock-h">MachineBasicBlock.h</a>.</p>

</div>
</div>

### getAddressTakenIRBlock() {#a9e26767dd60f2ffd50a7a6c5ea3a0c32}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">BasicBlock * llvm::MachineBasicBlock::getAddressTakenIRBlock ()</td>
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

<p>Retrieves the <a href="/web-llvm/docs/api/classes/llvm/basicblock">BasicBlock</a> which corresponds to this <a href="/web-llvm/docs/api/classes/llvm/machinebasicblock">MachineBasicBlock</a>.</p>

<p>Definition at line 292 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/codegen/machinebasicblock-h">MachineBasicBlock.h</a>.</p>


<p>Referenced by <a href="#adad68dd11c1995cc4f63e51986f50ce0">printName</a>.</p>

</div>
</div>

### getAlignment() {#ae13575403de0e7d005f1b5905053f3ea}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">Align llvm::MachineBasicBlock::getAlignment ()</td>
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

<p>Return alignment of the basic block.</p>

<p>Definition at line 623 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/codegen/machinebasicblock-h">MachineBasicBlock.h</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/structs/anonymous-ppcbranchselector-cpp-/ppcbsel/#a4e820fafe9db53cc4c12257e709dccde">anonymous{PPCBranchSelector.cpp}::PPCBSel::computeBranchSize</a>, <a href="/web-llvm/docs/api/classes/anonymous-cskyconstantislandpass-cpp-/cskyconstantislands/#a6159cb24e3496f5b8bd5e830e052aba1">anonymous{CSKYConstantIslandPass.cpp}::CSKYConstantIslands::doInitialPlacement</a>, <a href="/web-llvm/docs/api/classes/anonymous-mipsconstantislandpass-cpp-/mipsconstantislands/#a3068d2fa3c2556694ca3db57b7c197dd">anonymous{MipsConstantIslandPass.cpp}::MipsConstantIslands::doInitialPlacement</a> and <a href="#adad68dd11c1995cc4f63e51986f50ce0">printName</a>.</p>

</div>
</div>

### getBasicBlock() {#a4874816314c3308be0bf1e71de2078d8}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">const BasicBlock * llvm::MachineBasicBlock::getBasicBlock ()</td>
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

<p>Return the LLVM basic block that this instance corresponded to originally.</p>


<p>Note that this may be NULL if this instance does not correspond directly to an LLVM basic block.</p>


<p>Definition at line 256 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/codegen/machinebasicblock-h">MachineBasicBlock.h</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/classes/llvm/machinefunction/#a84a89ee9844b6cffc3660100168d7bee">llvm::MachineFunction::addLandingPad</a>, <a href="/web-llvm/docs/api/namespaces/anonymous-basicblockpathcloning-cpp-/#a0150e86671c87ec3046e8ba46be9f151">anonymous{BasicBlockPathCloning.cpp}::CloneMachineBasicBlock</a>, <a href="/web-llvm/docs/api/classes/llvm/ppctargetlowering/#a541b354a6386df6d03fcdc656d7d9db7">llvm::PPCTargetLowering::EmitAtomicBinary</a>, <a href="/web-llvm/docs/api/classes/llvm/selectiondagbuilder/#a41a8f459a2dcfcfc624394df6b432689">llvm::SelectionDAGBuilder::EmitBranchForMergedCondition</a>, <a href="/web-llvm/docs/api/classes/llvm/armtargetlowering/#a6820d09b4db5654cd1377d3ab63b3e01">llvm::ARMTargetLowering::EmitInstrWithCustomInserter</a>, <a href="/web-llvm/docs/api/classes/llvm/bpftargetlowering/#ac190f0cf5627568bd97cf1e5b24ce57d">llvm::BPFTargetLowering::EmitInstrWithCustomInserter</a>, <a href="/web-llvm/docs/api/classes/llvm/msp430targetlowering/#a948d164566e4b5aca48cf71cbf3a9ee3">llvm::MSP430TargetLowering::EmitInstrWithCustomInserter</a>, <a href="/web-llvm/docs/api/classes/llvm/ppctargetlowering/#a10d6f09e62a827099ec8b54efb4c035d">llvm::PPCTargetLowering::EmitInstrWithCustomInserter</a>, <a href="/web-llvm/docs/api/classes/llvm/xcoretargetlowering/#a13afdeda523046ab7176bead48d1c46f">llvm::XCoreTargetLowering::EmitInstrWithCustomInserter</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/riscv/riscvisellowering-cpp/#a4af8648d2e12301489dcc7b760f981ac">EmitLoweredCascadedSelect</a>, <a href="/web-llvm/docs/api/classes/llvm/ppctargetlowering/#a2e99e64e510ba34954d7fe85b1e30119">llvm::PPCTargetLowering::EmitPartwordAtomicBinary</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/riscv/riscvisellowering-cpp/#ae20aef7ab8c13752bc5663fb0e6cbb1c">emitReadCounterWidePseudo</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/riscv/riscvisellowering-cpp/#a59f08a4b78badcbfff06545894a60e6e">emitSelectPseudo</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/csky/cskyisellowering-cpp/#a8e39c98d41d74a2147127a17c9800c7d">emitSelectPseudo</a>, <a href="/web-llvm/docs/api/classes/llvm/msp430targetlowering/#a33dd164bd4caf16d69db25a98f5d338f">llvm::MSP430TargetLowering::EmitShiftInstr</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/loongarch/loongarchisellowering-cpp/#accb97b288f5b7b78cc16845a383fc13c">emitVecCondBranchPseudo</a>, <a href="/web-llvm/docs/api/classes/llvm/veinstrinfo/#ad99d6c93063cbfe0bf0f995a0cf12552">llvm::VEInstrInfo::expandExtendStackPseudo</a>, <a href="/web-llvm/docs/api/classes/llvm/sparctargetlowering/#a216c0fdb0cdd991dcf320bd42ff4c39e">llvm::SparcTargetLowering::expandSelectCC</a>, <a href="/web-llvm/docs/api/classes/llvm/fastisel/#a1b8715812b9f4dd2bd46163dd1b51128">llvm::FastISel::fastEmitBranch</a>, <a href="/web-llvm/docs/api/classes/llvm/selectiondagbuilder/#ae17b24216f27d8266c87b9fa9a70f533">llvm::SelectionDAGBuilder::FindMergedConditions</a>, <a href="/web-llvm/docs/api/classes/llvm/fastisel/#aebb4626a91d27266548cba7efedc6fe6">llvm::FastISel::finishCondBranch</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/powerpc/ppciseldagtodag-cpp/#a9293c2849df988b06fecea7e1b021fee">getBranchHint</a>, <a href="#ad2a8da74fd4e4c892018c56c977addee">getFullName</a>, <a href="#aedf6cb1135961f41f39dc58ca8576123">getName</a>, <a href="#a426db725707eef3025202e393420aa7f">hasName</a>, <a href="/web-llvm/docs/api/classes/llvm/ppcframelowering/#af0a5a3bd252aaac7b161ad8c01cf0951">llvm::PPCFrameLowering::inlineStackProbe</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/webassembly/webassemblyisellowering-cpp/#a01bea37475bf9a1f853b90975dbf7605">LowerFPToInt</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/webassembly/webassemblyisellowering-cpp/#a1b22ed476a56f8583de43854dfe57830">LowerMemcpy</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/webassembly/webassemblyisellowering-cpp/#aa603afd757ff3057f96bf5c1ee83e8b2">LowerMemset</a>, <a href="#adad68dd11c1995cc4f63e51986f50ce0">printName</a>, <a href="/web-llvm/docs/api/classes/llvm/armblockplacement/#a977d1a0dea04c7f562cb1ca6063d81dd">llvm::ARMBlockPlacement::revertWhileToDoLoop</a>, <a href="#ac0bfa894f538166cb476b439a2cb0aea">splitAt</a>, <a href="/web-llvm/docs/api/classes/anonymous-cskyconstantislandpass-cpp-/cskyconstantislands/#ae708a0dc9c80038ba6d971c94eb9db5c">anonymous{CSKYConstantIslandPass.cpp}::CSKYConstantIslands::splitBlockBeforeInstr</a>, <a href="/web-llvm/docs/api/classes/anonymous-mipsconstantislandpass-cpp-/mipsconstantislands/#a747abf73a79323919b62fb98e61aeaf2">anonymous{MipsConstantIslandPass.cpp}::MipsConstantIslands::splitBlockBeforeInstr</a> and <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/powerpc/ppcreducecrlogicals-cpp/#a6268a1294b61555b575fbd131789aaf3">splitMBB</a>.</p>

</div>
</div>

### getBBID() {#a45a5042aa51fc28cccaba7a95ec9746c}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">std::optional&lt; UniqueBBID &gt; llvm::MachineBasicBlock::getBBID ()</td>
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



<p>Definition at line 690 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/codegen/machinebasicblock-h">MachineBasicBlock.h</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/namespaces/anonymous-basicblockpathcloning-cpp-/#abbaff7e4a8cdaa59924d29ba6e305f4a">anonymous{BasicBlockPathCloning.cpp}::IsValidCloning</a> and <a href="#adad68dd11c1995cc4f63e51986f50ce0">printName</a>.</p>

</div>
</div>

### getBeginClobberMask() {#a864dfd605ab4c40b895d035a165a873b}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">const uint32_t * MachineBasicBlock::getBeginClobberMask (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/targetregisterinfo">TargetRegisterInfo</a> * TRI)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Get the clobber mask for the start of this basic block.</p>


<p>Funclets use this to prevent register allocation across funclet transitions.</p>


<p>Declaration at line 616 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/codegen/machinebasicblock-h">MachineBasicBlock.h</a>, definition at line 1730 of file <a href="/web-llvm/docs/api/files/lib/lib/codegen/machinebasicblock-cpp">MachineBasicBlock.cpp</a>.</p>


<p>References <a href="#a7d2f8efd82042b4cf611ba10e9e79ed0">isEHFuncletEntry</a> and <a href="/web-llvm/docs/api/files/lib/lib/codegen/machinesink-cpp/#a0f36ed1bc17fc1aa97fe291c439a0698">TRI</a>.</p>

</div>
</div>

### getCallFrameSize() {#ad661835c7f2b51fb3c5d826e77eafb93}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">unsigned llvm::MachineBasicBlock::getCallFrameSize ()</td>
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

<p>Return the call frame size on entry to this basic block.</p>

<p>Definition at line 1230 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/codegen/machinebasicblock-h">MachineBasicBlock.h</a>.</p>


<p>Referenced by <a href="#aa80aaa82844ab5560ece045eee7b34ac">SplitCriticalEdge</a>.</p>

</div>
</div>

### getEHCatchretSymbol() {#a210ccb5b83a717a8dce63cd7602a58b6}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">MCSymbol * MachineBasicBlock::getEHCatchretSymbol ()</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Return the EHCatchret Symbol for this basic block.</p>

<p>Declaration at line 1238 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/codegen/machinebasicblock-h">MachineBasicBlock.h</a>, definition at line 95 of file <a href="/web-llvm/docs/api/files/lib/lib/codegen/machinebasicblock-cpp">MachineBasicBlock.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/classes/llvm/machinefunction/#a752546c51633c140d9ca4ab98b4781b6">llvm::MachineFunction::getContext</a>, <a href="/web-llvm/docs/api/classes/llvm/machinefunction/#a28a68f98b1944a3a50635a007c3c3907">llvm::MachineFunction::getFunctionNumber</a>, <a href="#a3aa22d521bd6a7e6b9f35545dc7b0f1e">getNumber</a>, <a href="/web-llvm/docs/api/classes/llvm/mccontext/#ac11eef690074972378846024abbe8722">llvm::MCContext::getOrCreateSymbol</a>, <a href="#acf6442108e21e7e5379feb8962de65b7">getParent</a> and <a href="#ac423fefe048ace18159808c5592ae74c">MachineFunction</a>.</p>

</div>
</div>

### getEndClobberMask() {#af80cc22ae7f226a8c819be6bf9e731d4}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">const uint32_t * MachineBasicBlock::getEndClobberMask (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/targetregisterinfo">TargetRegisterInfo</a> * TRI)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Get the clobber mask for the end of the basic block.</p>


<dl class="doxySectionUser">
<dt>See Also</dt>
<dd><p><a href="#a864dfd605ab4c40b895d035a165a873b">getBeginClobberMask()</a></p></dd>
</dl>


<p>Declaration at line 620 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/codegen/machinebasicblock-h">MachineBasicBlock.h</a>, definition at line 1736 of file <a href="/web-llvm/docs/api/files/lib/lib/codegen/machinebasicblock-cpp">MachineBasicBlock.cpp</a>.</p>


<p>References <a href="#a82f5d244972c88ff03ee56d6c090ac70">isReturnBlock</a>, <a href="#aa8d1d8d88835b75b05b14ab774785e8a">succ_empty</a> and <a href="/web-llvm/docs/api/files/lib/lib/codegen/machinesink-cpp/#a0f36ed1bc17fc1aa97fe291c439a0698">TRI</a>.</p>

</div>
</div>

### getEndSymbol() {#a78b12ba4209266f4d26fa513c576ee18}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">MCSymbol * MachineBasicBlock::getEndSymbol ()</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Returns the <a href="/web-llvm/docs/api/classes/llvm/mcsymbol">MCSymbol</a> marking the end of this basic block.</p>

<p>Declaration at line 705 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/codegen/machinebasicblock-h">MachineBasicBlock.h</a>, definition at line 106 of file <a href="/web-llvm/docs/api/files/lib/lib/codegen/machinebasicblock-cpp">MachineBasicBlock.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/classes/llvm/mccontext/#a03742cf8aa97edf5612a800e4f159876">llvm::MCContext::createBlockSymbol</a>, <a href="/web-llvm/docs/api/classes/llvm/machinefunction/#a752546c51633c140d9ca4ab98b4781b6">llvm::MachineFunction::getContext</a>, <a href="/web-llvm/docs/api/classes/llvm/machinefunction/#a28a68f98b1944a3a50635a007c3c3907">llvm::MachineFunction::getFunctionNumber</a>, <a href="#a3aa22d521bd6a7e6b9f35545dc7b0f1e">getNumber</a>, <a href="#acf6442108e21e7e5379feb8962de65b7">getParent</a> and <a href="#ac423fefe048ace18159808c5592ae74c">MachineFunction</a>.</p>

</div>
</div>

### getFallThrough() {#a31aa2680ec79198a4c94f35b3a1ad97e}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">MachineBasicBlock * MachineBasicBlock::getFallThrough (bool JumpToFallThrough=<a href="/web-llvm/docs/api/files/lib/lib/analysis/basicaliasanalysis-cpp/#af6d5cafbdfc5313e65d990120021a3ec">true</a>)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Return the fallthrough block if the block can implicitly transfer control to the block after it by falling off the end of it.</p>


<p>If an explicit branch to the fallthrough block is not allowed, set JumpToFallThrough to be false. Non-null return is a conservative answer.</p>


<p>Declaration at line 859 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/codegen/machinebasicblock-h">MachineBasicBlock.h</a>, definition at line 977 of file <a href="/web-llvm/docs/api/files/lib/lib/codegen/machinebasicblock-cpp">MachineBasicBlock.cpp</a>.</p>


<p>References <a href="#acf35424231192c6b4a3e22d711f50b1e">back</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/riscv/riscvredundantcopyelimination-cpp/#a193847098793cdbab306803186676899">Cond</a>, <a href="#a095ce2d870dadf620a4c887ecc0efef8">empty</a>, <a href="#acbc921830578e2741be6549db716c0ce">end</a>, <a href="/web-llvm/docs/api/classes/llvm/targetsubtargetinfo/#acd858ed72f11db9444617740c3622608">llvm::TargetSubtargetInfo::getInstrInfo</a>, <a href="/web-llvm/docs/api/classes/llvm/ilist-node-impl/#af719fc783be6589465137d997701a432">llvm::ilist_node_impl&lt; ilist_detail::compute_node_options&lt; MachineBasicBlock, Options... &gt;::type &gt;::getIterator</a>, <a href="#acf6442108e21e7e5379feb8962de65b7">getParent</a>, <a href="/web-llvm/docs/api/classes/llvm/machinefunction/#a3825368aca2bc1550d173660df4da6a6">llvm::MachineFunction::getSubtarget</a>, <a href="#adc8f1be4a77ae671ac139d5f06b44deb">isSuccessor</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/riscv/riscvredundantcopyelimination-cpp/#a1441f79530bc7f3a89118bb8067eac69">TBB</a> and <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/hexagon/hexagoncopytocombine-cpp/#a1d40004718218dbdf06b496766299101">TII</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/namespaces/anonymous-basicblockpathcloning-cpp-/#a09842318dc1064ae48b19d91e2cb11aa">anonymous{BasicBlockPathCloning.cpp}::ApplyCloning</a>, <a href="#a5ffb77c69d69a5beff906caaecfd7be4">canFallThrough</a>, <a href="/web-llvm/docs/api/classes/llvm/riscvframelowering/#a4c55a328d2daf9b5e2f457c8880e21c4">llvm::RISCVFrameLowering::canUseAsEpilogue</a>, <a href="/web-llvm/docs/api/namespaces/anonymous-basicblockpathcloning-cpp-/#a0150e86671c87ec3046e8ba46be9f151">anonymous{BasicBlockPathCloning.cpp}::CloneMachineBasicBlock</a>, <a href="/web-llvm/docs/api/classes/llvm/armtargetlowering/#a6820d09b4db5654cd1377d3ab63b3e01">llvm::ARMTargetLowering::EmitInstrWithCustomInserter</a> and <a href="#a1b9a057d53df3e20a0618572be3802f5">getLogicalFallThrough</a>.</p>

</div>
</div>

### getFirstInstrTerminator() {#ad8c65b86ef286331d408a7a74c7b0b2f}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">MachineBasicBlock::instr_iterator MachineBasicBlock::getFirstInstrTerminator ()</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Same getFirstTerminator but it ignores bundles and return an <a href="#ab6395548cae73865213e279ae461db54">instr_iterator</a> instead.</p>

<p>Declaration at line 904 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/codegen/machinebasicblock-h">MachineBasicBlock.h</a>, definition at line 253 of file <a href="/web-llvm/docs/api/files/lib/lib/codegen/machinebasicblock-cpp">MachineBasicBlock.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/files/lib/lib/ir/builtingcs-cpp/#ae76959fe811ba090de4cba69ac00f1da">B</a>, <a href="/web-llvm/docs/api/files/lib/lib/support/md5-cpp/#ac0eafdc9ee161b71e7af98af736952fd">I</a>, <a href="#a172e7bd9150eb0519ef04c796086f93d">instr_begin</a> and <a href="#acae72f6ab1071b7ec87b741a8bef582b">instr_end</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/classes/anonymous-sifixsgprcopies-cpp-/sifixsgprcopies/#ac937dffe1e0bab6bdb751371c1923928">anonymous{SIFixSGPRCopies.cpp}::SIFixSGPRCopies::run</a> and <a href="#aa80aaa82844ab5560ece045eee7b34ac">SplitCriticalEdge</a>.</p>

</div>
</div>

### getFirstNonDebugInstr() {#a62b5d2211c09378c471307293453d780}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">MachineBasicBlock::iterator MachineBasicBlock::getFirstNonDebugInstr (bool SkipPseudoOp=<a href="/web-llvm/docs/api/files/lib/lib/analysis/basicaliasanalysis-cpp/#af6d5cafbdfc5313e65d990120021a3ec">true</a>)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Returns an iterator to the first non-debug instruction in the basic block, or <a href="#acbc921830578e2741be6549db716c0ce">end()</a>.</p>


<p>Skip any pseudo probe operation if <span class="doxyComputerOutput">SkipPseudoOp</span> is true. Pseudo probes are like debug instructions which do not turn into real machine code. We try to use the function to skip both debug instructions and pseudo probe operations to avoid API proliferation. This should work most of the time when considering optimizing the rest of code in the block, except for certain cases where pseudo probes are designed to block the optimizations. For example, code merge like optimizations are supposed to be blocked by pseudo probes for better AutoFDO profile quality. Therefore, they should be considered as a valid instruction when this function is called in a context of such optimizations. On the other hand, <span class="doxyComputerOutput">SkipPseudoOp</span> should be true when it's used in optimizations that unlikely hurt profile quality, e.g., without block merging. The default value of <span class="doxyComputerOutput">SkipPseudoOp</span> is set to true to maximize code quality in general, with an explict false value passed in in a few places like branch folding and if-conversion to favor profile quality.</p>


<p>Declaration at line 927 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/codegen/machinebasicblock-h">MachineBasicBlock.h</a>, definition at line 267 of file <a href="/web-llvm/docs/api/files/lib/lib/codegen/machinebasicblock-cpp">MachineBasicBlock.cpp</a>.</p>


<p>References <a href="#ab2d91e7bec944efcbc39d8e30644f111">begin</a>, <a href="#acbc921830578e2741be6549db716c0ce">end</a> and <a href="/web-llvm/docs/api/namespaces/llvm/#a5bacbbd03e9261f7b30dc174f26d680c">llvm::skipDebugInstructionsForward</a>.</p>


<p>Referenced by <a href="#a33633113f9128fa0c2b8543c6b1703f6">getFirstNonDebugInstr</a> and <a href="/web-llvm/docs/api/classes/llvm/tailduplicator/#a22b5f49c33bc7b11d150556b0ee1ca0a">llvm::TailDuplicator::isSimpleBB</a>.</p>

</div>
</div>

### getFirstNonDebugInstr() {#a33633113f9128fa0c2b8543c6b1703f6}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">const_iterator llvm::MachineBasicBlock::getFirstNonDebugInstr (bool SkipPseudoOp=<a href="/web-llvm/docs/api/files/lib/lib/analysis/basicaliasanalysis-cpp/#af6d5cafbdfc5313e65d990120021a3ec">true</a>)</td>
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



<p>Definition at line 928 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/codegen/machinebasicblock-h">MachineBasicBlock.h</a>.</p>


<p>Reference <a href="#a62b5d2211c09378c471307293453d780">getFirstNonDebugInstr</a>.</p>

</div>
</div>

### getFirstNonPHI() {#aa7dc7faaab4856b8f0014b8283e26c7b}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">MachineBasicBlock::iterator MachineBasicBlock::getFirstNonPHI ()</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Returns a pointer to the first instruction in this block that is not a <a href="/web-llvm/docs/api/classes/llvm/phinode">PHINode</a> instruction.</p>


<p>When adding instructions to the beginning of the basic block, they should be added before the returned value, not before the first instruction, which might be PHI. Returns <a href="#acbc921830578e2741be6549db716c0ce">end()</a> is there's no non-PHI instruction.</p>


<p>Declaration at line 878 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/codegen/machinebasicblock-h">MachineBasicBlock.h</a>, definition at line 202 of file <a href="/web-llvm/docs/api/files/lib/lib/codegen/machinebasicblock-cpp">MachineBasicBlock.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/silowercontrolflow-cpp/#a4868c5d81c5ccc98c47aeab6244346a0">assert</a>, <a href="/web-llvm/docs/api/files/lib/lib/support/md5-cpp/#ac0eafdc9ee161b71e7af98af736952fd">I</a>, <a href="#a172e7bd9150eb0519ef04c796086f93d">instr_begin</a> and <a href="#acae72f6ab1071b7ec87b741a8bef582b">instr_end</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/classes/anonymous-ppcbranchcoalescing-cpp-/ppcbranchcoalescing/#a481db3ca9a03829503a402a2318a27b1">anonymous{PPCBranchCoalescing.cpp}::PPCBranchCoalescing::canMerge</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/lib/target/aarch64/gisel/aarch64instructionselector-cpp/#aafb37937e5f21c12443bd5278264d08b">fixupPHIOpBanks</a>, <a href="#a9fc9c00548565617b77dc29112199269">getFirstNonPHI</a>, <a href="/web-llvm/docs/api/classes/llvm/ssaupdatertraits-4e613f36227a2a352217431a8f1958cd/#a55bb47729cc153812bf4c00989460022">llvm::SSAUpdaterTraits&lt; MachineSSAUpdater &gt;::GetPoisonVal</a>, <a href="/web-llvm/docs/api/namespaces/anonymous-combinerhelper-cpp-/#abe36a8462243713bdada68a3fc16ee47">anonymous{CombinerHelper.cpp}::InsertInsnsWithoutSideEffectsBeforeUse</a>, <a href="/web-llvm/docs/api/classes/anonymous-ppcbranchcoalescing-cpp-/ppcbranchcoalescing/#a072a336f973a3de4daa8fe16e5b4570f">anonymous{PPCBranchCoalescing.cpp}::PPCBranchCoalescing::mergeCandidates</a>, <a href="/web-llvm/docs/api/classes/anonymous-ppcbranchcoalescing-cpp-/ppcbranchcoalescing/#a2a11298ee3a7cfcfa678f8b9a3df20db">anonymous{PPCBranchCoalescing.cpp}::PPCBranchCoalescing::moveAndUpdatePHIs</a>, <a href="/web-llvm/docs/api/classes/llvm/peelingmoduloscheduleexpander/#afe809699537758032938bea41ea44bb7">llvm::PeelingModuloScheduleExpander::moveStageBetweenBlocks</a>, <a href="/web-llvm/docs/api/classes/anonymous-sioptimizevgprliverange-cpp-/sioptimizevgprliverange/#aa35ddcfd60c7c4587ea25cb27e25968e">anonymous{SIOptimizeVGPRLiveRange.cpp}::SIOptimizeVGPRLiveRange::optimizeWaterfallLiveRange</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a0fdc13bfd373951ae6163637d6576c39">llvm::PeelSingleBlockLoop</a>, <a href="#a36b529ef331e4099007e14b48c75316a">phis</a>, <a href="/web-llvm/docs/api/classes/llvm/swifterrorvaluetracking/#afc960ff953a4a9d9fbf91baf590222d2">llvm::SwiftErrorValueTracking::propagateVRegs</a>, <a href="/web-llvm/docs/api/classes/llvm/machinessaupdater/#a71a08885f7838dc5a544816a357e2ec7">llvm::MachineSSAUpdater::RewriteUse</a> and <a href="/web-llvm/docs/api/classes/llvm/machinefunction/#aa3fa258f0e297563fcec4bb619d2a759">llvm::MachineFunction::salvageCopySSAImpl</a>.</p>

</div>
</div>

### getFirstNonPHI() {#a9fc9c00548565617b77dc29112199269}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">const_iterator llvm::MachineBasicBlock::getFirstNonPHI ()</td>
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



<p>Definition at line 879 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/codegen/machinebasicblock-h">MachineBasicBlock.h</a>.</p>


<p>Reference <a href="#aa7dc7faaab4856b8f0014b8283e26c7b">getFirstNonPHI</a>.</p>

</div>
</div>

### getFirstTerminator() {#a7f0521fa2de44271fd4b909ea7351ef3}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">MachineBasicBlock::iterator MachineBasicBlock::getFirstTerminator ()</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Returns an iterator to the first terminator instruction of this basic block.</p>


<p>If a terminator does not exist, it returns <a href="#acbc921830578e2741be6549db716c0ce">end()</a>.</p>


<p>Declaration at line 897 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/codegen/machinebasicblock-h">MachineBasicBlock.h</a>, definition at line 244 of file <a href="/web-llvm/docs/api/files/lib/lib/codegen/machinebasicblock-cpp">MachineBasicBlock.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/files/lib/lib/ir/builtingcs-cpp/#ae76959fe811ba090de4cba69ac00f1da">B</a>, <a href="#ab2d91e7bec944efcbc39d8e30644f111">begin</a>, <a href="#acbc921830578e2741be6549db716c0ce">end</a> and <a href="/web-llvm/docs/api/files/lib/lib/support/md5-cpp/#ac0eafdc9ee161b71e7af98af736952fd">I</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/classes/llvm/aarch64instrinfo/#ab359f8ff91954b23a1e8366666e59cbb">llvm::AArch64InstrInfo::analyzeLoopForPipelining</a>, <a href="/web-llvm/docs/api/classes/llvm/armbaseinstrinfo/#a637fe9208c860066ecf02233cd258f9b">llvm::ARMBaseInstrInfo::analyzeLoopForPipelining</a>, <a href="/web-llvm/docs/api/classes/llvm/hexagoninstrinfo/#a5e0e04407d3397fa1b002c7559a33860">llvm::HexagonInstrInfo::analyzeLoopForPipelining</a>, <a href="/web-llvm/docs/api/classes/llvm/ppcinstrinfo/#adc8a417082dae00c6f459b63a65e0ed8">llvm::PPCInstrInfo::analyzeLoopForPipelining</a>, <a href="/web-llvm/docs/api/classes/llvm/amdgpuregisterbankinfo/#a66655fdd73a951d10ad6fb804f0fac98">llvm::AMDGPURegisterBankInfo::applyMappingImpl</a>, <a href="/web-llvm/docs/api/files/lib/lib/codegen/branchfolding-cpp/#a287fa83baa277de19fb734bdda92f0c6">copyDebugInfoToPredecessor</a>, <a href="/web-llvm/docs/api/classes/llvm/scheduledagsdnodes/#a6f60ed03227dbeb711a3ae9b1f0238e9">llvm::ScheduleDAGSDNodes::EmitSchedule</a>, <a href="#ad81901d0d8b768b240e78bf357999f34">findBranchDebugLoc</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a444e3b411610e3f4275e36386768ce8d">llvm::findSplitPointForStackProtector</a>, <a href="#acd8ed715d1519a082b42e4ecf0d22320">getFirstTerminator</a>, <a href="/web-llvm/docs/api/classes/llvm/sitargetlowering/#a5b2c69041e8c83952d7cdd75cf7a36e8">llvm::SITargetLowering::getPrefLoopAlignment</a>, <a href="/web-llvm/docs/api/classes/llvm/machinessaupdater/#a670da7741129c7d591dc19951ecce6c3">llvm::MachineSSAUpdater::GetValueInMiddleOfBlock</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/silowersgprspills-cpp/#a3c627e9f404e8f9cf66e5a4a27860347">insertCSRRestores</a>, <a href="/web-llvm/docs/api/files/lib/lib/codegen/prologepiloginserter-cpp/#a04bc45ddbc56deb8b54dacaeea86df8f">insertCSRRestores</a>, <a href="/web-llvm/docs/api/classes/llvm/siinstrinfo/#a09787033a63326e79a0d1445d3e0de13">llvm::SIInstrInfo::legalizeOperands</a>, <a href="/web-llvm/docs/api/classes/anonymous-ppcbranchcoalescing-cpp-/ppcbranchcoalescing/#a072a336f973a3de4daa8fe16e5b4570f">anonymous{PPCBranchCoalescing.cpp}::PPCBranchCoalescing::mergeCandidates</a>, <a href="/web-llvm/docs/api/classes/llvm/legalizerhelper/#a98e3f12f0b3d7f35251e1e71336b480c">llvm::LegalizerHelper::moreElementsVectorPhi</a>, <a href="/web-llvm/docs/api/classes/anonymous-hexagoncopyhoisting-cpp-/hexagoncopyhoisting/#a4fc59ce12e2dc07246561737f195c0c6">anonymous{HexagonCopyHoisting.cpp}::HexagonCopyHoisting::moveCopyInstr</a>, <a href="/web-llvm/docs/api/classes/anonymous-x86flagscopylowering-cpp-/x86flagscopyloweringpass/#a30d90e84a3faa0cd7aa2c3b96d65c232">anonymous{X86FlagsCopyLowering.cpp}::X86FlagsCopyLoweringPass::runOnMachineFunction</a>, <a href="/web-llvm/docs/api/classes/anonymous-hexagoninstrinfo-cpp-/hexagonpipelinerloopinfo/#af7f7f0f37193bf67ea9e1c7538388773">anonymous{HexagonInstrInfo.cpp}::HexagonPipelinerLoopInfo::setPreheader</a>, <a href="#aa80aaa82844ab5560ece045eee7b34ac">SplitCriticalEdge</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/powerpc/ppcreducecrlogicals-cpp/#a6268a1294b61555b575fbd131789aaf3">splitMBB</a>, <a href="#ad56ff27a502cd519f9aaf5cc028b4ea5">terminators</a>, <a href="#aadfc2f6425b15faff5ce2421cc708205">terminators</a>, <a href="/web-llvm/docs/api/classes/anonymous-sifoldoperands-cpp-/sifoldoperandsimpl/#a17772fd1beeccd740ec6412abad098f9">anonymous{SIFoldOperands.cpp}::SIFoldOperandsImpl::tryFoldPhiAGPR</a> and <a href="/web-llvm/docs/api/classes/anonymous-silowersgprspills-cpp-/silowersgprspills/#a5d3b9b2ab425ee38c1571fb2cc9a5608">anonymous{SILowerSGPRSpills.cpp}::SILowerSGPRSpills::updateLaneVGPRDomInstr</a>.</p>

</div>
</div>

### getFirstTerminator() {#acd8ed715d1519a082b42e4ecf0d22320}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">const_iterator llvm::MachineBasicBlock::getFirstTerminator ()</td>
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



<p>Definition at line 898 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/codegen/machinebasicblock-h">MachineBasicBlock.h</a>.</p>


<p>Reference <a href="#a7f0521fa2de44271fd4b909ea7351ef3">getFirstTerminator</a>.</p>

</div>
</div>

### getFirstTerminatorForward() {#a0fab3e644b3457f90ed7f64876a037d2}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">MachineBasicBlock::iterator MachineBasicBlock::getFirstTerminatorForward ()</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Finds the first terminator in a block by scanning forward.</p>


<p>This can handle cases in GlobalISel where there may be non-terminator instructions between terminators, for which <a href="#a7f0521fa2de44271fd4b909ea7351ef3">getFirstTerminator()</a> will not work correctly.</p>


<p>Declaration at line 909 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/codegen/machinebasicblock-h">MachineBasicBlock.h</a>, definition at line 262 of file <a href="/web-llvm/docs/api/files/lib/lib/codegen/machinebasicblock-cpp">MachineBasicBlock.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/namespaces/llvm/#ac78c09ae232b2ce188ff590d51e3c268">llvm::find_if</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/nvptx/nvvmintrrange-cpp/#ac5804672fc0850438d63caec770647f8">II</a> and <a href="#a40bf8f9579717d3f9be7640f1c6d678b">instrs</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/classes/llvm/legalizerhelper/#a60e4161d46b020a55403acd13e31df9a">llvm::LegalizerHelper::fewerElementsVectorPhi</a>, <a href="/web-llvm/docs/api/classes/llvm/legalizerhelper/#a6701d040466d73f3dc51481d3186c294">llvm::LegalizerHelper::narrowScalar</a> and <a href="/web-llvm/docs/api/classes/llvm/legalizerhelper/#aacc36b9bbb74a3cdb987aa8f28b269e3">llvm::LegalizerHelper::widenScalar</a>.</p>

</div>
</div>

### getFullName() {#ad2a8da74fd4e4c892018c56c977addee}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">std::string MachineBasicBlock::getFullName ()</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Return a formatted string to identify this block and its parent function.</p>


<p>Return a hopefully unique identifier for this block.</p>


<p>Declaration at line 271 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/codegen/machinebasicblock-h">MachineBasicBlock.h</a>, definition at line 334 of file <a href="/web-llvm/docs/api/files/lib/lib/codegen/machinebasicblock-cpp">MachineBasicBlock.cpp</a>.</p>


<p>References <a href="#a4874816314c3308be0bf1e71de2078d8">getBasicBlock</a>, <a href="/web-llvm/docs/api/classes/llvm/machinefunction/#a3d142c9e7c066059e15232c56dec9e2e">llvm::MachineFunction::getName</a>, <a href="/web-llvm/docs/api/classes/llvm/value/#adb5c319f5905c1d3ca9eb5df546388c5">llvm::Value::getName</a>, <a href="#a3aa22d521bd6a7e6b9f35545dc7b0f1e">getNumber</a> and <a href="#acf6442108e21e7e5379feb8962de65b7">getParent</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/classes/llvm/armblockplacement/#ab273671903c0baabbbf098a0a4581101">llvm::ARMBlockPlacement::fixBackwardsWLS</a>.</p>

</div>
</div>

### getIrrLoopHeaderWeight() {#af45e6b009a9a5ec818e4ae303ab65cb1}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">std::optional&lt; uint64_t &gt; llvm::MachineBasicBlock::getIrrLoopHeaderWeight ()</td>
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



<p>Definition at line 1240 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/codegen/machinebasicblock-h">MachineBasicBlock.h</a>.</p>

</div>
</div>

### getLastNonDebugInstr() {#ab8d7b8ff6803133d567fd4240e6364ce}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">MachineBasicBlock::iterator MachineBasicBlock::getLastNonDebugInstr (bool SkipPseudoOp=<a href="/web-llvm/docs/api/files/lib/lib/analysis/basicaliasanalysis-cpp/#af6d5cafbdfc5313e65d990120021a3ec">true</a>)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Returns an iterator to the last non-debug instruction in the basic block, or <a href="#acbc921830578e2741be6549db716c0ce">end()</a>.</p>


<p>Skip any pseudo operation if <span class="doxyComputerOutput">SkipPseudoOp</span> is true. Pseudo probes are like debug instructions which do not turn into real machine code. We try to use the function to skip both debug instructions and pseudo probe operations to avoid API proliferation. This should work most of the time when considering optimizing the rest of code in the block, except for certain cases where pseudo probes are designed to block the optimizations. For example, code merge like optimizations are supposed to be blocked by pseudo probes for better AutoFDO profile quality. Therefore, they should be considered as a valid instruction when this function is called in a context of such optimizations. On the other hand, <span class="doxyComputerOutput">SkipPseudoOp</span> should be true when it's used in optimizations that unlikely hurt profile quality, e.g., without block merging. The default value of <span class="doxyComputerOutput">SkipPseudoOp</span> is set to true to maximize code quality in general, with an explict false value passed in in a few places like branch folding and if-conversion to favor profile quality.</p>


<p>Declaration at line 949 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/codegen/machinebasicblock-h">MachineBasicBlock.h</a>, definition at line 273 of file <a href="/web-llvm/docs/api/files/lib/lib/codegen/machinebasicblock-cpp">MachineBasicBlock.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/files/lib/lib/ir/builtingcs-cpp/#ae76959fe811ba090de4cba69ac00f1da">B</a>, <a href="#acbc921830578e2741be6549db716c0ce">end</a>, <a href="/web-llvm/docs/api/files/lib/lib/support/md5-cpp/#ac0eafdc9ee161b71e7af98af736952fd">I</a>, <a href="#a172e7bd9150eb0519ef04c796086f93d">instr_begin</a> and <a href="#acae72f6ab1071b7ec87b741a8bef582b">instr_end</a>.</p>


<p>Referenced by <a href="#a7e284f7329497d8ffc3bd7fab1402cac">getLastNonDebugInstr</a>, <a href="/web-llvm/docs/api/files/lib/lib/codegen/branchfolding-cpp/#acda790896623fd894c71bf79f1bbcfea">IsBetterFallthrough</a>, <a href="/web-llvm/docs/api/classes/anonymous-aarch64redundantcopyelimination-cpp-/aarch64redundantcopyelimination/#a1ee0cfcd17ed3a5b4826b8a5f93e50e1">anonymous{AArch64RedundantCopyElimination.cpp}::AArch64RedundantCopyElimination::optimizeBlock</a> and <a href="/web-llvm/docs/api/structs/anonymous-ppcearlyreturn-cpp-/ppcearlyreturn/#ae036500138a9ae1567af6b28547cf045">anonymous{PPCEarlyReturn.cpp}::PPCEarlyReturn::processBlock</a>.</p>

</div>
</div>

### getLastNonDebugInstr() {#a7e284f7329497d8ffc3bd7fab1402cac}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">const_iterator llvm::MachineBasicBlock::getLastNonDebugInstr (bool SkipPseudoOp=<a href="/web-llvm/docs/api/files/lib/lib/analysis/basicaliasanalysis-cpp/#af6d5cafbdfc5313e65d990120021a3ec">true</a>)</td>
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



<p>Definition at line 950 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/codegen/machinebasicblock-h">MachineBasicBlock.h</a>.</p>


<p>Reference <a href="#ab8d7b8ff6803133d567fd4240e6364ce">getLastNonDebugInstr</a>.</p>

</div>
</div>

### getLiveIns() {#a8012fc1639ba1cd1f3966ccca165d2af}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">const std::vector&lt; RegisterMaskPair &gt; &amp; llvm::MachineBasicBlock::getLiveIns ()</td>
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



<p>Definition at line 521 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/codegen/machinebasicblock-h">MachineBasicBlock.h</a>.</p>

</div>
</div>

### getLogicalFallThrough() {#a1b9a057d53df3e20a0618572be3802f5}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">MachineBasicBlock * llvm::MachineBasicBlock::getLogicalFallThrough ()</td>
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

<p>Return the fallthrough block if the block can implicitly transfer control to it's successor, whether by a branch or a fallthrough.</p>


<p>Non-null return is a conservative answer.</p>


<p>Definition at line 864 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/codegen/machinebasicblock-h">MachineBasicBlock.h</a>.</p>


<p>Reference <a href="#a31aa2680ec79198a4c94f35b3a1ad97e">getFallThrough</a>.</p>

</div>
</div>

### getMaxBytesForAlignment() {#a6e25c9cf835390ac9c23abb4cf70d4eb}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">unsigned llvm::MachineBasicBlock::getMaxBytesForAlignment ()</td>
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

<p>Return the maximum amount of padding allowed for aligning the basic block.</p>

<p>Definition at line 634 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/codegen/machinebasicblock-h">MachineBasicBlock.h</a>.</p>

</div>
</div>

### getName() {#aedf6cb1135961f41f39dc58ca8576123}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">StringRef MachineBasicBlock::getName ()</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Return the name of the corresponding LLVM basic block, or an empty string.</p>

<p>Declaration at line 268 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/codegen/machinebasicblock-h">MachineBasicBlock.h</a>, definition at line 326 of file <a href="/web-llvm/docs/api/files/lib/lib/codegen/machinebasicblock-cpp">MachineBasicBlock.cpp</a>.</p>


<p>Reference <a href="#a4874816314c3308be0bf1e71de2078d8">getBasicBlock</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/classes/llvm/armbasicblockutils/#a918dbb418e1069f7afe1d321cd5547c0">llvm::ARMBasicBlockUtils::adjustBBOffsetsAfter</a>, <a href="/web-llvm/docs/api/files/lib/lib/codegen/machineblockplacement-cpp/#a8f9ee7f9ffc036496a8663335da175fa">getBlockName</a>, <a href="/web-llvm/docs/api/files/lib/lib/codegen/mirfsdiscriminator-cpp/#a3dd14252abb2a835f8682b0ffd6b5cf3">getCallStackHashV0</a>, <a href="/web-llvm/docs/api/classes/llvm/armblockplacement/#aa13bb5e066b0419461ad1bbdd7bc9a1d">llvm::ARMBlockPlacement::moveBasicBlock</a>, <a href="/web-llvm/docs/api/classes/llvm/webassemblyexceptioninfo/#a6248704cecd958d5eeb84fa3536fc78c">llvm::WebAssemblyExceptionInfo::recalculate</a> and <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/x86/x86speculativeloadhardening-cpp/#a18b17899654dd5adb69b62c89ba95783">splitEdge</a>.</p>

</div>
</div>

### getNumber() {#a3aa22d521bd6a7e6b9f35545dc7b0f1e}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">int llvm::MachineBasicBlock::getNumber ()</td>
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

<p>MachineBasicBlocks are uniquely numbered at the function level, unless they're not in a <a href="/web-llvm/docs/api/classes/llvm/machinefunction">MachineFunction</a> yet, in which case this will return -1.</p>

<p>Definition at line 1226 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/codegen/machinebasicblock-h">MachineBasicBlock.h</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/classes/llvm/livevariables/#afbcff91139fc89e3e8c0dda857e7b128">llvm::LiveVariables::addNewBlock</a>, <a href="/web-llvm/docs/api/classes/llvm/livevariables/#afc347ae9e7fcba69b04162d7b4a73635">llvm::LiveVariables::addNewBlock</a>, <a href="/web-llvm/docs/api/classes/anonymous-cskyconstantislandpass-cpp-/cskyconstantislands/#a3384fc522b23fa07500bd151eee9fed5">anonymous{CSKYConstantIslandPass.cpp}::CSKYConstantIslands::adjustBBOffsetsAfter</a>, <a href="/web-llvm/docs/api/classes/anonymous-mipsconstantislandpass-cpp-/mipsconstantislands/#a94b3ade7f05777308f0695ef6eb5da19">anonymous{MipsConstantIslandPass.cpp}::MipsConstantIslands::adjustBBOffsetsAfter</a>, <a href="/web-llvm/docs/api/classes/llvm/armbasicblockutils/#a918dbb418e1069f7afe1d321cd5547c0">llvm::ARMBasicBlockUtils::adjustBBOffsetsAfter</a>, <a href="/web-llvm/docs/api/classes/anonymous-hexagoncopyhoisting-cpp-/hexagoncopyhoisting/#a11effd5d22384daab26c5045ecff2e5b">anonymous{HexagonCopyHoisting.cpp}::HexagonCopyHoisting::analyzeCopy</a>, <a href="/web-llvm/docs/api/classes/anonymous-ppcbranchcoalescing-cpp-/ppcbranchcoalescing/#aa8661c8ac8b1cb3810a45d201972e5d5">anonymous{PPCBranchCoalescing.cpp}::PPCBranchCoalescing::canMoveToBeginning</a>, <a href="/web-llvm/docs/api/classes/anonymous-ppcbranchcoalescing-cpp-/ppcbranchcoalescing/#afd833dc91598d5a3c3f327b47b98a4cf">anonymous{PPCBranchCoalescing.cpp}::PPCBranchCoalescing::canMoveToEnd</a>, <a href="/web-llvm/docs/api/structs/anonymous-ppcbranchselector-cpp-/ppcbsel/#a4e820fafe9db53cc4c12257e709dccde">anonymous{PPCBranchSelector.cpp}::PPCBSel::computeBranchSize</a>, <a href="/web-llvm/docs/api/classes/anonymous-cskyconstantislandpass-cpp-/cskyconstantislands/#aee171a94c094d78c3744e68795791b8d">anonymous{CSKYConstantIslandPass.cpp}::CSKYConstantIslands::createNewWater</a>, <a href="/web-llvm/docs/api/classes/anonymous-mipsconstantislandpass-cpp-/mipsconstantislands/#ac438bed7ae6afbb9ff9e0be02099ad0f">anonymous{MipsConstantIslandPass.cpp}::MipsConstantIslands::createNewWater</a>, <a href="/web-llvm/docs/api/classes/anonymous-cskyconstantislandpass-cpp-/cskyconstantislands/#a4a94570a6a2a0044a7e4e959f414b317">anonymous{CSKYConstantIslandPass.cpp}::CSKYConstantIslands::findAvailableWater</a>, <a href="/web-llvm/docs/api/classes/anonymous-mipsconstantislandpass-cpp-/mipsconstantislands/#a909a324ed32517aaca69fb2e87f41bca">anonymous{MipsConstantIslandPass.cpp}::MipsConstantIslands::findAvailableWater</a>, <a href="/web-llvm/docs/api/classes/llvm/webassembly/sortregioninfo/#a6ee3593d7995476eab40d83e2ba1fb35">llvm::WebAssembly::SortRegionInfo::getBottom</a>, <a href="/web-llvm/docs/api/classes/llvm/webassembly/sortregioninfo/#aaf85bffcbc40515b7511a958b7d82ee6">llvm::WebAssembly::SortRegionInfo::getBottom</a>, <a href="#a210ccb5b83a717a8dce63cd7602a58b6">getEHCatchretSymbol</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#afa141935f9c9a1ad9c785d7b6200b119">llvm::getEHScopeMembership</a>, <a href="#a78b12ba4209266f4d26fa513c576ee18">getEndSymbol</a>, <a href="#ad2a8da74fd4e4c892018c56c977addee">getFullName</a>, <a href="/web-llvm/docs/api/structs/llvm/graphtraits-5d21b8f453fe72c9ef888c2858a7ce72/#a850648bfd97449027f93cb18af249ee3">llvm::GraphTraits&lt; const MachineBasicBlock * &gt;::getNumber</a>, <a href="/web-llvm/docs/api/structs/llvm/graphtraits-8dab79ad0cf15ea502cd9eb4bb116b20/#a71f87966b4dabdb5942b4d3391f106d9">llvm::GraphTraits&lt; Inverse&lt; const MachineBasicBlock * &gt; &gt;::getNumber</a>, <a href="/web-llvm/docs/api/structs/llvm/graphtraits-343d0630a0e99b15bc453d3b888245d8/#ac644ccdb34373d9f54b182fcd5403820">llvm::GraphTraits&lt; Inverse&lt; MachineBasicBlock * &gt; &gt;::getNumber</a>, <a href="/web-llvm/docs/api/structs/llvm/graphtraits-b9c75e93407b82228c2e4202f39262f5/#a343466f5c3404b2339fdeb2c8253b12a">llvm::GraphTraits&lt; MachineBasicBlock * &gt;::getNumber</a>, <a href="#a1cc134bd22a318835dc929323da70ea4">getSymbol</a>, <a href="/web-llvm/docs/api/classes/anonymous-cskyconstantislandpass-cpp-/cskyconstantislands/#a800f62f10fe1fafc076ae4002371ba45">anonymous{CSKYConstantIslandPass.cpp}::CSKYConstantIslands::handleConstantPoolUser</a>, <a href="/web-llvm/docs/api/classes/anonymous-mipsconstantislandpass-cpp-/mipsconstantislands/#a4d3a04a082a7dd5b285cddb7feef368c">anonymous{MipsConstantIslandPass.cpp}::MipsConstantIslands::handleConstantPoolUser</a>, <a href="/web-llvm/docs/api/classes/anonymous-r600machinecfgstructurizer-cpp-/r600machinecfgstructurizer/#a3d20136077641cd8689ad93587230228">anonymous{R600MachineCFGStructurizer.cpp}::R600MachineCFGStructurizer::handleJumpintoIfImp</a>, <a href="/web-llvm/docs/api/classes/llvm/po-iterator-storage-3fc582f4b807835050bb72d4ed1f0e76/#a12289268ab155993fbbeef5ef8a2ffa4">llvm::po_iterator_storage&lt; LoopBounds, true &gt;::insertEdge</a>, <a href="/web-llvm/docs/api/classes/llvm/slotindexes/#a55bd6e17074a39a9aad2ee8cd6f541fb">llvm::SlotIndexes::insertMBBInMaps</a>, <a href="/web-llvm/docs/api/classes/llvm/machinetracemetrics/ensemble/#a063217bcbb8b81adfdc88feb1a52ddcb">llvm::MachineTraceMetrics::Ensemble::invalidate</a>, <a href="/web-llvm/docs/api/classes/anonymous-cskyconstantislandpass-cpp-/cskyconstantislands/#a32cee73e5a706eff3a8fc0b655f3ad93">anonymous{CSKYConstantIslandPass.cpp}::CSKYConstantIslands::isBBInRange</a>, <a href="/web-llvm/docs/api/classes/anonymous-mipsconstantislandpass-cpp-/mipsconstantislands/#ab686eff61461eaac81cf87ba84143a0a">anonymous{MipsConstantIslandPass.cpp}::MipsConstantIslands::isBBInRange</a>, <a href="/web-llvm/docs/api/classes/llvm/armbasicblockutils/#a1744b6aaacbb052e862e88903ded5956">llvm::ARMBasicBlockUtils::isBBInRange</a>, <a href="/web-llvm/docs/api/classes/anonymous-r600machinecfgstructurizer-cpp-/r600machinecfgstructurizer/#a34c501f2f094f555ee3dbe0a1970d300">anonymous{R600MachineCFGStructurizer.cpp}::R600MachineCFGStructurizer::isSameloopDetachedContbreak</a>, <a href="/web-llvm/docs/api/classes/anonymous-cskyconstantislandpass-cpp-/cskyconstantislands/#a31dc649eb968f53e71376a708b40333f">anonymous{CSKYConstantIslandPass.cpp}::CSKYConstantIslands::isWaterInRange</a>, <a href="/web-llvm/docs/api/classes/anonymous-mipsconstantislandpass-cpp-/mipsconstantislands/#a54ee101062ec8079d8d7fadafb29c511">anonymous{MipsConstantIslandPass.cpp}::MipsConstantIslands::isWaterInRange</a>, <a href="/web-llvm/docs/api/classes/anonymous-r600machinecfgstructurizer-cpp-/r600machinecfgstructurizer/#aa76d1bb8a35c5fe0c9c22df9cc0dba10">anonymous{R600MachineCFGStructurizer.cpp}::R600MachineCFGStructurizer::mergeIfthenelseBlock</a>, <a href="/web-llvm/docs/api/classes/anonymous-r600machinecfgstructurizer-cpp-/r600machinecfgstructurizer/#ac1a085b3eb182136b9d98a7d6916421f">anonymous{R600MachineCFGStructurizer.cpp}::R600MachineCFGStructurizer::mergeLoopbreakBlock</a>, <a href="/web-llvm/docs/api/classes/anonymous-r600machinecfgstructurizer-cpp-/r600machinecfgstructurizer/#ab38ab4f331b754f58147aaa7a86febb1">anonymous{R600MachineCFGStructurizer.cpp}::R600MachineCFGStructurizer::mergeLooplandBlock</a>, <a href="/web-llvm/docs/api/classes/anonymous-r600machinecfgstructurizer-cpp-/r600machinecfgstructurizer/#a5fec9aab7a2ff820c3c372f3cda87c25">anonymous{R600MachineCFGStructurizer.cpp}::R600MachineCFGStructurizer::mergeSerialBlock</a>, <a href="#adad68dd11c1995cc4f63e51986f50ce0">printName</a>, <a href="/web-llvm/docs/api/classes/llvm/swifterrorvaluetracking/#afc960ff953a4a9d9fbf91baf590222d2">llvm::SwiftErrorValueTracking::propagateVRegs</a>, <a href="/web-llvm/docs/api/classes/llvm/webassemblyexceptioninfo/#a6248704cecd958d5eeb84fa3536fc78c">llvm::WebAssemblyExceptionInfo::recalculate</a>, <a href="/web-llvm/docs/api/classes/llvm/livevariables/#a9e0695dc8fb597f66ca702309da941f7">llvm::LiveVariables::recomputeForSingleDefVirtReg</a>, <a href="/web-llvm/docs/api/classes/anonymous-cskyconstantislandpass-cpp-/cskyconstantislands/#a260e4fa04b4392ed7de8a9202292a2ca">anonymous{CSKYConstantIslandPass.cpp}::CSKYConstantIslands::removeDeadCPEMI</a>, <a href="/web-llvm/docs/api/classes/anonymous-mipsconstantislandpass-cpp-/mipsconstantislands/#abbda87d0f5c41ed3eca00b354a53417d">anonymous{MipsConstantIslandPass.cpp}::MipsConstantIslands::removeDeadCPEMI</a>, <a href="/web-llvm/docs/api/classes/anonymous-moduloschedule-cpp-/moduloscheduletest/#aff71500f971dc1f796d293a1450dc6b0">anonymous{ModuloSchedule.cpp}::ModuloScheduleTest::runOnLoop</a>, <a href="/web-llvm/docs/api/classes/anonymous-gcnpreralongbranchreg-cpp-/gcnpreralongbranchreg/#a8b5ef68b98f901c64096eb633984c661">anonymous{GCNPreRALongBranchReg.cpp}::GCNPreRALongBranchReg::runOnMachineFunction</a>, <a href="/web-llvm/docs/api/classes/anonymous-ifconversion-cpp-/ifconverter/#abff4179252123a7710b2fa134be3f9d6">anonymous{IfConversion.cpp}::IfConverter::runOnMachineFunction</a>, <a href="/web-llvm/docs/api/classes/llvm/cfifixup/#a7d1808859a4351ab820d5fa17a0e2685">llvm::CFIFixup::runOnMachineFunction</a>, <a href="/web-llvm/docs/api/classes/llvm/mirprofileloader/#a31f2c5f323ca8742d0588171e0c33b49">llvm::MIRProfileLoader::setBranchProbs</a>, <a href="/web-llvm/docs/api/classes/anonymous-r600machinecfgstructurizer-cpp-/r600machinecfgstructurizer/#a484a24399c195bf93535e18192b7cc94">anonymous{R600MachineCFGStructurizer.cpp}::R600MachineCFGStructurizer::settleLoopcontBlock</a>, <a href="/web-llvm/docs/api/classes/anonymous-r600machinecfgstructurizer-cpp-/r600machinecfgstructurizer/#ac471c55917cb9e3fdc7674e300260d9f">anonymous{R600MachineCFGStructurizer.cpp}::R600MachineCFGStructurizer::showImproveSimpleJumpintoIf</a>, <a href="/web-llvm/docs/api/classes/anonymous-cskyconstantislandpass-cpp-/cskyconstantislands/#ae708a0dc9c80038ba6d971c94eb9db5c">anonymous{CSKYConstantIslandPass.cpp}::CSKYConstantIslands::splitBlockBeforeInstr</a>, <a href="/web-llvm/docs/api/classes/anonymous-mipsconstantislandpass-cpp-/mipsconstantislands/#a747abf73a79323919b62fb98e61aeaf2">anonymous{MipsConstantIslandPass.cpp}::MipsConstantIslands::splitBlockBeforeInstr</a>, <a href="/web-llvm/docs/api/classes/anonymous-cskyconstantislandpass-cpp-/cskyconstantislands/#ab83a38fd680014ffab61e69579bb7c36">anonymous{CSKYConstantIslandPass.cpp}::CSKYConstantIslands::updateForInsertedWaterBlock</a>, <a href="/web-llvm/docs/api/classes/anonymous-mipsconstantislandpass-cpp-/mipsconstantislands/#a2810208a226ed8b333882063153be2e0">anonymous{MipsConstantIslandPass.cpp}::MipsConstantIslands::updateForInsertedWaterBlock</a>, <a href="/web-llvm/docs/api/classes/llvm/machinetracemetrics/ensemble/#a0a23768d13b961c25d4bb19c3f42824c">llvm::MachineTraceMetrics::Ensemble::verify</a>, <a href="/web-llvm/docs/api/files/lib/lib/codegen/tailduplicator-cpp/#a833919b7851dc025ff507a7f8652bb8e">VerifyPHIs</a> and <a href="/web-llvm/docs/api/structs/anonymous-machineverifier-cpp-/machineverifier/#a63ebe76813ff76375cf5705af12bdcd6">anonymous{MachineVerifier.cpp}::MachineVerifier::verifyStackFrame</a>.</p>

</div>
</div>

### getParent() {#acf6442108e21e7e5379feb8962de65b7}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">const MachineFunction * llvm::MachineBasicBlock::getParent ()</td>
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

<p>Return the <a href="/web-llvm/docs/api/classes/llvm/machinefunction">MachineFunction</a> containing this basic block.</p>

<p>Definition at line 311 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/codegen/machinebasicblock-h">MachineBasicBlock.h</a>.</p>


<p>Reference <a href="#ac423fefe048ace18159808c5592ae74c">MachineFunction</a>.</p>


<p>Referenced by <a href="#a9bd7c04e374ad15665430a243dd30d80">addLiveIn</a>, <a href="/web-llvm/docs/api/classes/llvm/armbasicblockutils/#a918dbb418e1069f7afe1d321cd5547c0">llvm::ARMBasicBlockUtils::adjustBBOffsetsAfter</a>, <a href="/web-llvm/docs/api/classes/llvm/armbaseinstrinfo/#a637fe9208c860066ecf02233cd258f9b">llvm::ARMBaseInstrInfo::analyzeLoopForPipelining</a>, <a href="/web-llvm/docs/api/classes/llvm/ppcinstrinfo/#adc8a417082dae00c6f459b63a65e0ed8">llvm::PPCInstrInfo::analyzeLoopForPipelining</a>, <a href="/web-llvm/docs/api/classes/llvm/riscvinstrinfo/#a2b7f96b6dd38c8bb8039a5018a8dc1e1">llvm::RISCVInstrInfo::analyzeLoopForPipelining</a>, <a href="/web-llvm/docs/api/classes/llvm/amdgpuregisterbankinfo/#a66655fdd73a951d10ad6fb804f0fac98">llvm::AMDGPURegisterBankInfo::applyMappingImpl</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a9a381a22976702d096a05acf1605c5bc">llvm::BuildMI</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#ac98e182e817bb53f2ff8135d29637dfb">llvm::BuildMI</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#ac441ac1e3b333caa1d41bee0d4fabbe8">llvm::BuildMI</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a2513bcbf688cb9218d16769edbba6a47">llvm::BuildMI</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#afa1fe17340600deeeb2a5647e56fc1a2">llvm::BuildMI</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a859007fbe974ffb4c1793877e4ada681">llvm::BuildMI</a>, <a href="/web-llvm/docs/api/classes/llvm/moduloscheduleexpandermve/#a8b570f6c1b94d49245ad3cee2887acf3">llvm::ModuloScheduleExpanderMVE::canApply</a>, <a href="#ae32dc74389a52cbb83e6a016274142f5">canSplitCriticalEdge</a>, <a href="/web-llvm/docs/api/files/lib/lib/codegen/cfifixup-cpp/#a6766bb9d415c3d929afaa24877e14fc6">cloneCfiPrologue</a>, <a href="/web-llvm/docs/api/namespaces/anonymous-basicblockpathcloning-cpp-/#a0150e86671c87ec3046e8ba46be9f151">anonymous{BasicBlockPathCloning.cpp}::CloneMachineBasicBlock</a>, <a href="/web-llvm/docs/api/classes/anonymous-sioptimizevgprliverange-cpp-/sioptimizevgprliverange/#a5290bdffbf68a26e47345d1bb2abb246">anonymous{SIOptimizeVGPRLiveRange.cpp}::SIOptimizeVGPRLiveRange::collectCandidateRegisters</a>, <a href="/web-llvm/docs/api/classes/anonymous-sioptimizevgprliverange-cpp-/sioptimizevgprliverange/#ab47a3d3cac0564876929e77389dbe569">anonymous{SIOptimizeVGPRLiveRange.cpp}::SIOptimizeVGPRLiveRange::collectWaterfallCandidateRegisters</a>, <a href="/web-llvm/docs/api/structs/llvm/hexagonblockranges/#a4271a72d1e29d700427b7cb039771a5f">llvm::HexagonBlockRanges::computeDeadMap</a>, <a href="/web-llvm/docs/api/classes/anonymous-x86winfixupbuffersecuritycheck-cpp-/x86winfixupbuffersecuritycheckpass/#a8d1d93bb20bf72c7782cf68446e5bf9f">anonymous{X86WinFixupBufferSecurityCheck.cpp}::X86WinFixupBufferSecurityCheckPass::CreateFailCheckSequence</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/x86/x86isellowering-cpp/#a22444fb95050a5bef1c689e5bc9b064e">createPHIsForCMOVsInSinkBB</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/systemz/systemzisellowering-cpp/#a3c4c42f79d79638f6b67532d3f81df58">createPHIsForSelects</a>, <a href="/web-llvm/docs/api/classes/llvm/aarch64targetlowering/#ab812d774aa563ffc2c67030a9ba1be39">llvm::AArch64TargetLowering::EmitAllocateSMESaveBuffer</a>, <a href="/web-llvm/docs/api/classes/llvm/aarch64targetlowering/#ab9a65a8c0739a72de196022849b4ee67">llvm::AArch64TargetLowering::EmitAllocateZABuffer</a>, <a href="/web-llvm/docs/api/classes/llvm/ppctargetlowering/#a541b354a6386df6d03fcdc656d7d9db7">llvm::PPCTargetLowering::EmitAtomicBinary</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/riscv/riscvisellowering-cpp/#a04f5dec5b43c7deebd3c243317240d95">emitBuildPairF64Pseudo</a>, <a href="/web-llvm/docs/api/classes/llvm/aarch64targetlowering/#acfee0aff6a62996ec1dbee56ef35ad88">llvm::AArch64TargetLowering::EmitGetSMESaveSize</a>, <a href="/web-llvm/docs/api/classes/llvm/sitargetlowering/#a82e453c9e7f441c185009164f0136fa8">llvm::SITargetLowering::emitGWSMemViolTestLoop</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/siisellowering-cpp/#ab69231adafff5e2e89dfae5a21ba246b">emitIndirectDst</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/siisellowering-cpp/#a071d8b84e530f1a6e725aea09fdc6407">emitIndirectSrc</a>, <a href="/web-llvm/docs/api/classes/llvm/aarch64targetlowering/#a2ed887f0677d391bc6f9d7e77b761695">llvm::AArch64TargetLowering::EmitInitTPIDR2Object</a>, <a href="/web-llvm/docs/api/classes/llvm/armtargetlowering/#a6820d09b4db5654cd1377d3ab63b3e01">llvm::ARMTargetLowering::EmitInstrWithCustomInserter</a>, <a href="/web-llvm/docs/api/classes/llvm/bpftargetlowering/#ac190f0cf5627568bd97cf1e5b24ce57d">llvm::BPFTargetLowering::EmitInstrWithCustomInserter</a>, <a href="/web-llvm/docs/api/classes/llvm/msp430targetlowering/#a948d164566e4b5aca48cf71cbf3a9ee3">llvm::MSP430TargetLowering::EmitInstrWithCustomInserter</a>, <a href="/web-llvm/docs/api/classes/llvm/ppctargetlowering/#a10d6f09e62a827099ec8b54efb4c035d">llvm::PPCTargetLowering::EmitInstrWithCustomInserter</a>, <a href="/web-llvm/docs/api/classes/llvm/r600targetlowering/#a3098f3c7fe942574303f81224b526094">llvm::R600TargetLowering::EmitInstrWithCustomInserter</a>, <a href="/web-llvm/docs/api/classes/llvm/sitargetlowering/#a92bd7eb8dcbdfa0341a4fe88a09941da">llvm::SITargetLowering::EmitInstrWithCustomInserter</a>, <a href="/web-llvm/docs/api/classes/llvm/x86targetlowering/#a5fd231b7f6dc1db67a2bb2f48bf5f342">llvm::X86TargetLowering::EmitInstrWithCustomInserter</a>, <a href="/web-llvm/docs/api/classes/llvm/xcoretargetlowering/#a13afdeda523046ab7176bead48d1c46f">llvm::XCoreTargetLowering::EmitInstrWithCustomInserter</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/siisellowering-cpp/#a9d5a6023eff415532345b226faccc38b">emitLoadM0FromVGPRLoop</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/siinstrinfo-cpp/#a476adf24d3374520fb31b2785f331d58">emitLoadScalarOpsFromVGPRLoop</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/riscv/riscvisellowering-cpp/#a4af8648d2e12301489dcc7b760f981ac">EmitLoweredCascadedSelect</a>, <a href="/web-llvm/docs/api/classes/llvm/aarch64targetlowering/#a87a3c3fc7fc8bc05db24005a6d38b5b2">llvm::AArch64TargetLowering::EmitLoweredCatchRet</a>, <a href="/web-llvm/docs/api/classes/llvm/ppctargetlowering/#a2e99e64e510ba34954d7fe85b1e30119">llvm::PPCTargetLowering::EmitPartwordAtomicBinary</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/loongarch/loongarchisellowering-cpp/#a94be4f19deb3ce06a8fcde89fb4b639b">emitPseudoCTPOP</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/loongarch/loongarchisellowering-cpp/#a9de3850aa5bea6fb60e5c61162bf22e9">emitPseudoXVINSGR2VR</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/riscv/riscvisellowering-cpp/#a055df59820235c32c403d7c78de5494b">emitQuietFCMP</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/riscv/riscvisellowering-cpp/#ae20aef7ab8c13752bc5663fb0e6cbb1c">emitReadCounterWidePseudo</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/riscv/riscvisellowering-cpp/#a59f08a4b78badcbfff06545894a60e6e">emitSelectPseudo</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/csky/cskyisellowering-cpp/#a8e39c98d41d74a2147127a17c9800c7d">emitSelectPseudo</a>, <a href="/web-llvm/docs/api/classes/llvm/msp430targetlowering/#a33dd164bd4caf16d69db25a98f5d338f">llvm::MSP430TargetLowering::EmitShiftInstr</a>, <a href="/web-llvm/docs/api/classes/llvm/vetargetlowering/#a751f59893007a8fdcc892d81119abc82">llvm::VETargetLowering::emitSjLjDispatchBlock</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/riscv/riscvisellowering-cpp/#aaf673a1e44074d7088008437112159fa">emitSplitF64Pseudo</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/loongarch/loongarchisellowering-cpp/#accb97b288f5b7b78cc16845a383fc13c">emitVecCondBranchPseudo</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/riscv/riscvisellowering-cpp/#ab0a615cb68b545ea3a9c88243a0ab4d9">emitVFROUND_NOEXCEPT_MASK</a>, <a href="/web-llvm/docs/api/classes/llvm/siinstrinfo/#ae0196eca3002f5fd8c339ea859ddd12f">llvm::SIInstrInfo::enforceOperandRCAlignment</a>, <a href="#ac421fe6513e43aedbba712e4a981744e">eraseFromParent</a>, <a href="/web-llvm/docs/api/classes/llvm/sparctargetlowering/#a216c0fdb0cdd991dcf320bd42ff4c39e">llvm::SparcTargetLowering::expandSelectCC</a>, <a href="/web-llvm/docs/api/classes/llvm/selectiondagbuilder/#ae17b24216f27d8266c87b9fa9a70f533">llvm::SelectionDAGBuilder::FindMergedConditions</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64loadstoreoptimizer-cpp/#a4a8c56807dfa1a49f37218084fb6c044">findRenameRegForSameLdStRegPair</a>, <a href="/web-llvm/docs/api/classes/anonymous-x86winfixupbuffersecuritycheck-cpp-/x86winfixupbuffersecuritycheckpass/#af3c6ee1ea1205bc11240ee3916b4411d">anonymous{X86WinFixupBufferSecurityCheck.cpp}::X86WinFixupBufferSecurityCheckPass::FinishFunction</a>, <a href="/web-llvm/docs/api/files/lib/lib/codegen/branchfolding-cpp/#abbe6276e99bb565156d18a843ae1ccb9">FixTail</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/lib/target/aarch64/gisel/aarch64instructionselector-cpp/#aafb37937e5f21c12443bd5278264d08b">fixupPHIOpBanks</a>, <a href="/web-llvm/docs/api/classes/llvm/machineloop/#aa5d6d2568abd0f3161ac255b4c6e1f4c">llvm::MachineLoop::getBottomBlock</a>, <a href="/web-llvm/docs/api/classes/llvm/machineinstr/#ad26a74fb0ad868f0867cce317269d721">llvm::MachineInstr::getDebugInstrNum</a>, <a href="#a210ccb5b83a717a8dce63cd7602a58b6">getEHCatchretSymbol</a>, <a href="#a78b12ba4209266f4d26fa513c576ee18">getEndSymbol</a>, <a href="#a31aa2680ec79198a4c94f35b3a1ad97e">getFallThrough</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/siinstrinfo-cpp/#a23c3c91648996442b88f0c53cf1415d8">getFoldableImm</a>, <a href="#ad2a8da74fd4e4c892018c56c977addee">getFullName</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64instrinfo-cpp/#a339e0ad5e938860dcbd0c510ce212c4b">getIndVarInfo</a>, <a href="/web-llvm/docs/api/files/lib/lib/codegen/machineblockplacement-cpp/#a3d135a8abf70dc93455708cc087cc0b0">getLayoutSuccessorProbThreshold</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/mips/mipsseregisterinfo-cpp/#ae4f8119e930e450734d4903391aca1fa">getLoadStoreOffsetSizeInBits</a>, <a href="/web-llvm/docs/api/classes/llvm/machineinstr/#ab05719438bdf4b46871e5ecd9730caeb">llvm::MachineInstr::getMF</a>, <a href="#a1cc134bd22a318835dc929323da70ea4">getSymbol</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/powerpc/ppcmcinstlower-cpp/#a8aa470cbd092a0baa198faf2e5174f94">GetSymbolRef</a>, <a href="/web-llvm/docs/api/classes/llvm/machineloop/#adfb3765b2827835823c1c55d12b33957">llvm::MachineLoop::getTopBlock</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/sifixsgprcopies-cpp/#a4e0750d12818ab0f8a301e4be935ea72">hoistAndMergeSGPRInits</a>, <a href="/web-llvm/docs/api/classes/anonymous-r600machinecfgstructurizer-cpp-/r600machinecfgstructurizer/#ae27fd47ee099b4aba7fe2bc84be97ff8">anonymous{R600MachineCFGStructurizer.cpp}::R600MachineCFGStructurizer::improveSimpleJumpintoIf</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64redundantcopyelimination-cpp/#af884214031cdb18344d85b5d4c422fef">INITIALIZE_PASS</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/hexagon/hexagonvextract-cpp/#a88486e318adbd7333b898816348c8e7c">INITIALIZE_PASS</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/silowersgprspills-cpp/#a3c627e9f404e8f9cf66e5a4a27860347">insertCSRRestores</a>, <a href="/web-llvm/docs/api/files/lib/lib/codegen/prologepiloginserter-cpp/#a04bc45ddbc56deb8b54dacaeea86df8f">insertCSRRestores</a>, <a href="/web-llvm/docs/api/files/lib/lib/codegen/prologepiloginserter-cpp/#a61e27cf21f938d341d13395bb4e17493">insertCSRSaves</a>, <a href="/web-llvm/docs/api/classes/llvm/slotindexes/#a55bd6e17074a39a9aad2ee8cd6f541fb">llvm::SlotIndexes::insertMBBInMaps</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#ad64501a368789645f6f80afbce82da90">llvm::insertMultibyteShift</a>, <a href="/web-llvm/docs/api/files/lib/lib/codegen/cfifixup-cpp/#a313dff6a75b3ae9c5c5d6802f3007a56">insertRememberRestorePair</a>, <a href="/web-llvm/docs/api/classes/llvm/instremitter/#add888de4c361e3791a2aba0cb578aa53">llvm::InstrEmitter::InstrEmitter</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64instrinfo-cpp/#a89fae3db628b477b713990d7a58732ea">isCombineInstrCandidateFP</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64instrinfo-cpp/#ad6838072f35cd662ae8704973ccfc407">isDefinedOutside</a>, <a href="/web-llvm/docs/api/classes/llvm/machineinstr/#a2626405eab33f6bae29077772fd63115">llvm::MachineInstr::isDereferenceableInvariantLoad</a>, <a href="#a9103c1c7b60d793b0efd41c741286508">isEntryBlock</a>, <a href="/web-llvm/docs/api/classes/llvm/siinstrinfo/#abecccbf97c3a9d0be384e6c639fcf2dc">llvm::SIInstrInfo::isLegalRegOperand</a>, <a href="/web-llvm/docs/api/classes/llvm/amdgpulegalizerinfo/#aff7dfc9d1d4355acbd741d76ce27fca1">llvm::AMDGPULegalizerInfo::legalizeTrapEndpgm</a>, <a href="#a81335545907243d4dea1a276f01566c0">livein_begin</a>, <a href="#aa13f60350a3e19e1791fd628b694da36">liveout_begin</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/webassembly/webassemblyisellowering-cpp/#a5e660e19acc0643f71469b40cc016c2f">LowerCallResults</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/webassembly/webassemblyisellowering-cpp/#a01bea37475bf9a1f853b90975dbf7605">LowerFPToInt</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/webassembly/webassemblyisellowering-cpp/#a1b22ed476a56f8583de43854dfe57830">LowerMemcpy</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/webassembly/webassemblyisellowering-cpp/#aa603afd757ff3057f96bf5c1ee83e8b2">LowerMemset</a>, <a href="/web-llvm/docs/api/classes/llvm/aarch64mcinstlower/#a8ad295bb319044a941bbc7cc9e598efa">llvm::AArch64MCInstLower::lowerSymbolOperandELF</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/siisellowering-cpp/#a7809852647bc7e8ceed1f287b2d03125">lowerWaveReduce</a>, <a href="#af3c2dc75190645b72eee3c416cd14885">moveAfter</a>, <a href="/web-llvm/docs/api/classes/llvm/armblockplacement/#aa13bb5e066b0419461ad1bbdd7bc9a1d">llvm::ARMBlockPlacement::moveBasicBlock</a>, <a href="#a25c2a6ee39d0d97dac2184e8bd942300">moveBefore</a>, <a href="/web-llvm/docs/api/classes/anonymous-r600machinecfgstructurizer-cpp-/r600machinecfgstructurizer/#a43d3fe2699745c950168939ee8f0d5cb">anonymous{R600MachineCFGStructurizer.cpp}::R600MachineCFGStructurizer::normalizeInfiniteLoopExit</a>, <a href="/web-llvm/docs/api/classes/llvm/ppcinstrinfo/#aeae69b1baee541f55a44aaf2804dc007">llvm::PPCInstrInfo::optimizeCmpPostRA</a>, <a href="#ab3b62258d9bd41595674de878f37f8d8">print</a>, <a href="#a5a4302f4590a281bb84e08b30c80591c">print</a>, <a href="/web-llvm/docs/api/structs/anonymous-ppcearlyreturn-cpp-/ppcearlyreturn/#ae036500138a9ae1567af6b28547cf045">anonymous{PPCEarlyReturn.cpp}::PPCEarlyReturn::processBlock</a>, <a href="/web-llvm/docs/api/classes/llvm/armbaseinstrinfo/#a5a480d1fb65446ff93ffc9f140e213ab">llvm::ARMBaseInstrInfo::produceSameValue</a>, <a href="#af99e842f9d7eeea463d1d8f0bd34a0d0">removeFromParent</a>, <a href="/web-llvm/docs/api/classes/llvm/armblockplacement/#a977d1a0dea04c7f562cb1ca6063d81dd">llvm::ARMBlockPlacement::revertWhileToDoLoop</a>, <a href="/web-llvm/docs/api/classes/anonymous-x86flagscopylowering-cpp-/x86flagscopyloweringpass/#a30d90e84a3faa0cd7aa2c3b96d65c232">anonymous{X86FlagsCopyLowering.cpp}::X86FlagsCopyLoweringPass::runOnMachineFunction</a>, <a href="/web-llvm/docs/api/classes/llvm/machinefunction/#aa3fa258f0e297563fcec4bb619d2a759">llvm::MachineFunction::salvageCopySSAImpl</a>, <a href="/web-llvm/docs/api/classes/llvm/aarch64instrinfo/#a802e14b5716a86fc1f69d39fd1e2a5a2">llvm::AArch64InstrInfo::shouldClusterMemOps</a>, <a href="/web-llvm/docs/api/classes/llvm/tailduplicator/#aa7dba30d4d9162f00367404e06085391">llvm::TailDuplicator::shouldTailDuplicate</a>, <a href="#a3be7d94076d328797ab57ce09cefab33">SkipPHIsAndLabels</a>, <a href="#a5d8a45757c9861d499cba1a0d54e2c1e">SkipPHIsLabelsAndDebug</a>, <a href="#ac0bfa894f538166cb476b439a2cb0aea">splitAt</a>, <a href="#aa80aaa82844ab5560ece045eee7b34ac">SplitCriticalEdge</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/webassembly/webassemblycfgstackify-cpp/#a3f8efd734c37d01f22580c2211a68483">splitEndLoopBB</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/powerpc/ppcreducecrlogicals-cpp/#a6268a1294b61555b575fbd131789aaf3">splitMBB</a>, <a href="/web-llvm/docs/api/classes/anonymous-cskyconstantislandpass-cpp-/cskyconstantislands/#ab83a38fd680014ffab61e69579bb7c36">anonymous{CSKYConstantIslandPass.cpp}::CSKYConstantIslands::updateForInsertedWaterBlock</a>, <a href="/web-llvm/docs/api/classes/anonymous-mipsconstantislandpass-cpp-/mipsconstantislands/#a2810208a226ed8b333882063153be2e0">anonymous{MipsConstantIslandPass.cpp}::MipsConstantIslands::updateForInsertedWaterBlock</a>, <a href="/web-llvm/docs/api/classes/anonymous-silowersgprspills-cpp-/silowersgprspills/#a5d3b9b2ab425ee38c1571fb2cc9a5608">anonymous{SILowerSGPRSpills.cpp}::SILowerSGPRSpills::updateLaneVGPRDomInstr</a>, <a href="/web-llvm/docs/api/files/lib/lib/codegen/machinesink-cpp/#a6c1da13a967ff01e9076c55b0b6d158c">updateLiveIn</a>, <a href="#a5803a49facae20ca4b002dcba6f1d03e">updateTerminator</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/spirv/spirvisellowering-cpp/#adc3ecee5ecd3f86b45e6779653ca10da">validateFunCall</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/spirv/spirvisellowering-cpp/#ad7fdf3fa9ec7e0c43067799e690529c1">validateFunCallMachineDef</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/spirv/spirvisellowering-cpp/#af60628c2329ed3a894bf3d9fc1c5ec51">validatePtrTypes</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/amdgpulegalizerinfo-cpp/#a87e58e9d24983c7890c502fbe731f950">verifyCFIntrinsic</a> and <a href="/web-llvm/docs/api/classes/llvm/selectiondagbuilder/#ae8662f747218aee8ddeb4cdfbd1435a7">llvm::SelectionDAGBuilder::visitSPDescriptorParent</a>.</p>

</div>
</div>

### getParent() {#ac35a65b864412ca7fd4c25b8724144c9}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">MachineFunction * llvm::MachineBasicBlock::getParent ()</td>
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



<p>Definition at line 312 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/codegen/machinebasicblock-h">MachineBasicBlock.h</a>.</p>


<p>Reference <a href="#ac423fefe048ace18159808c5592ae74c">MachineFunction</a>.</p>

</div>
</div>

### getSectionID() {#a87ee39ccabd6fa5abe6302ebffd768c9}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">MBBSectionID llvm::MachineBasicBlock::getSectionID ()</td>
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

<p>Returns the section <a href="/web-llvm/docs/api/namespaces/llvm/callingconv/#abdf8cf606905c10634e831390981b0ed">ID</a> of this basic block.</p>

<p>Definition at line 693 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/codegen/machinebasicblock-h">MachineBasicBlock.h</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/classes/llvm/machinefunction/#af588c66ab3fcfe66fd0c99bcd645ee36">llvm::MachineFunction::assignBeginEndSections</a>, <a href="#adad68dd11c1995cc4f63e51986f50ce0">printName</a>, <a href="/web-llvm/docs/api/classes/llvm/cfifixup/#a7d1808859a4351ab820d5fa17a0e2685">llvm::CFIFixup::runOnMachineFunction</a> and <a href="#a7feb92c592c0f5bd6cbe88c5fbaa91f4">sameSection</a>.</p>

</div>
</div>

### getSinglePredecessor() {#a5bfe9045e7f0a89622211264b32ff155}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">const MachineBasicBlock * MachineBasicBlock::getSinglePredecessor ()</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Return the predecessor of this block if it has a single predecessor.</p>


<p>Otherwise return a null pointer.</p>


<p>Declaration at line 848 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/codegen/machinebasicblock-h">MachineBasicBlock.h</a>, definition at line 973 of file <a href="/web-llvm/docs/api/files/lib/lib/codegen/machinebasicblock-cpp">MachineBasicBlock.cpp</a>.</p>


<p>Reference <a href="#adbff55f335d303816547f35eb6edb948">size</a>.</p>

</div>
</div>

### getSinglePredecessor() {#a4337bbedd6474d24a404573fd8880410}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">MachineBasicBlock * llvm::MachineBasicBlock::getSinglePredecessor ()</td>
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



<p>Definition at line 849 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/codegen/machinebasicblock-h">MachineBasicBlock.h</a>.</p>

</div>
</div>

### getSingleSuccessor() {#aa0a5ac19256656534bea2daabdfb947b}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">const MachineBasicBlock * MachineBasicBlock::getSingleSuccessor ()</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Return the successor of this block if it has a single successor.</p>


<p>Otherwise return a null pointer.</p>


<p>Declaration at line 839 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/codegen/machinebasicblock-h">MachineBasicBlock.h</a>, definition at line 969 of file <a href="/web-llvm/docs/api/files/lib/lib/codegen/machinebasicblock-cpp">MachineBasicBlock.cpp</a>.</p>


<p>Reference <a href="#adbff55f335d303816547f35eb6edb948">size</a>.</p>

</div>
</div>

### getSingleSuccessor() {#a9dd1a68709ac7641bf56ad6afaad6b4c}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">MachineBasicBlock * llvm::MachineBasicBlock::getSingleSuccessor ()</td>
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



<p>Definition at line 840 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/codegen/machinebasicblock-h">MachineBasicBlock.h</a>.</p>

</div>
</div>

### getSuccProbability() {#a34b15764a81fb89e68d85d5aae76f20f}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">BranchProbability MachineBasicBlock::getSuccProbability (<a href="#a3f43e04d827b07cf1d5366554d03f748">const_succ_iterator</a> Succ)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Return probability of the edge from this block to MBB.</p>


<p>This method should NOT be called directly, but by using getEdgeProbability method from <a href="/web-llvm/docs/api/classes/llvm/machinebranchprobabilityinfo">MachineBranchProbabilityInfo</a> class.</p>


<p>Declaration at line 1251 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/codegen/machinebasicblock-h">MachineBasicBlock.h</a>, definition at line 1576 of file <a href="/web-llvm/docs/api/files/lib/lib/codegen/machinebasicblock-cpp">MachineBasicBlock.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/classes/llvm/branchprobability/#afd00958cba7080048a84cccfcef55d71">llvm::BranchProbability::getZero</a>, <a href="/web-llvm/docs/api/files/lib/lib/option/option-cpp/#a04665169063c8ca1f2ea96c27fc7c2b2">P</a> and <a href="#a81626de817a0cb021ff8e915cf1942ed">succ_size</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/classes/anonymous-sipreemitpeephole-cpp-/branchweightcostmodel/#aa842d0e2dfc3a19e513d9098c7e4d00e">anonymous{SIPreEmitPeephole.cpp}::BranchWeightCostModel::BranchWeightCostModel</a>, <a href="#a95933492048f0ea830f02f61b1329c12">copySuccessor</a> and <a href="#a5a4302f4590a281bb84e08b30c80591c">print</a>.</p>

</div>
</div>

### getSymbol() {#a1cc134bd22a318835dc929323da70ea4}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">MCSymbol * MachineBasicBlock::getSymbol ()</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Return the <a href="/web-llvm/docs/api/classes/llvm/mcsymbol">MCSymbol</a> for this basic block.</p>

<p>Declaration at line 1235 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/codegen/machinebasicblock-h">MachineBasicBlock.h</a>, definition at line 63 of file <a href="/web-llvm/docs/api/files/lib/lib/codegen/machinebasicblock-cpp">MachineBasicBlock.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/structs/llvm/mbbsectionid/#a2cbbe04f568b5890eeb2b58c0cbf6d71">llvm::MBBSectionID::ColdSectionID</a>, <a href="/web-llvm/docs/api/structs/llvm/mbbsectionid/#a27940a53407c67036b8292fa9bf4721d">llvm::MBBSectionID::ExceptionSectionID</a>, <a href="/web-llvm/docs/api/classes/llvm/machinefunction/#a752546c51633c140d9ca4ab98b4781b6">llvm::MachineFunction::getContext</a>, <a href="/web-llvm/docs/api/classes/llvm/machinefunction/#a28a68f98b1944a3a50635a007c3c3907">llvm::MachineFunction::getFunctionNumber</a>, <a href="/web-llvm/docs/api/classes/llvm/machinefunction/#a3d142c9e7c066059e15232c56dec9e2e">llvm::MachineFunction::getName</a>, <a href="#a3aa22d521bd6a7e6b9f35545dc7b0f1e">getNumber</a>, <a href="#acf6442108e21e7e5379feb8962de65b7">getParent</a>, <a href="/web-llvm/docs/api/classes/llvm/machinefunction/#a74e97fc3012191edf10e8c51291da4a7">llvm::MachineFunction::hasBBSections</a>, <a href="#a32eddb893169a26afe7e7372ecf943ef">hasLabelMustBeEmitted</a>, <a href="#ad4835355c1e5ca306abd15f5b90bd9b4">isBeginSection</a> and <a href="#ac423fefe048ace18159808c5592ae74c">MachineFunction</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/classes/llvm/systemzmcinstlower/#ad312528de16c4c08c2615fff027208fe">llvm::SystemZMCInstLower::getExpr</a>, <a href="/web-llvm/docs/api/classes/anonymous-x86mcinstlower-cpp-/x86mcinstlower/#af74245f7fce2e423d6a6b11e6ec37847">anonymous{X86MCInstLower.cpp}::X86MCInstLower::GetSymbolFromOperand</a>, <a href="/web-llvm/docs/api/classes/llvm/m68kmcinstlower/#a094b53ae338bc1ed10ec35facf8e07b0">llvm::M68kMCInstLower::GetSymbolFromOperand</a>, <a href="/web-llvm/docs/api/classes/llvm/siinstrinfo/#aff3eb40a3be5c2fb6f804f1e5649fd57">llvm::SIInstrInfo::insertIndirectBranch</a>, <a href="/web-llvm/docs/api/classes/anonymous-aarch64asmprinter-cpp-/aarch64asmprinter/#a72864dd5479176074c3bbcc3b0e50c22">anonymous{AArch64AsmPrinter.cpp}::AArch64AsmPrinter::LowerFAULTING_OP</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a2e1cb40177ee7bfd4c57389946f5117f">llvm::lowerLoongArchMachineOperandToMCOperand</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/ve/vemcinstlower-cpp/#ad827b1817feb40466ad495b35f506d3d">LowerOperand</a>, <a href="/web-llvm/docs/api/classes/amdgpumcinstlower/#a40f485334c44043e5c4849b522dd9e74">AMDGPUMCInstLower::lowerOperand</a>, <a href="/web-llvm/docs/api/classes/anonymous-riscvasmprinter-cpp-/riscvasmprinter/#a0236fccfc21c4cd523f03edf2e494a94">anonymous{RISCVAsmPrinter.cpp}::RISCVAsmPrinter::lowerOperand</a>, <a href="/web-llvm/docs/api/classes/llvm/aarch64mcinstlower/#abb90ec56583c85eb4445f4970f394571">llvm::AArch64MCInstLower::lowerOperand</a>, <a href="/web-llvm/docs/api/classes/llvm/armasmprinter/#a452a31c9f24b147d72a14890d60d3894">llvm::ARMAsmPrinter::lowerOperand</a>, <a href="/web-llvm/docs/api/classes/llvm/cskymcinstlower/#a12f79817d45ce63618d0cd11d1f146b9">llvm::CSKYMCInstLower::lowerOperand</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a261510478c31d3a3f1537bddd746a421">llvm::LowerPPCMachineOperandToMCOperand</a>, <a href="/web-llvm/docs/api/classes/llvm/xtensaasmprinter/#a153a3f96b2710ef9d924d8168a93482b">llvm::XtensaAsmPrinter::LowerSymbolOperand</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/sparc/sparcmcinstlower-cpp/#a413bd96508214793c2f0dcc61f05f71e">LowerSymbolOperand</a>, <a href="/web-llvm/docs/api/classes/llvm/webassemblyasmprinter/#ab3b56dc8749765fe615f325594493167">llvm::WebAssemblyAsmPrinter::PrintAsmOperand</a>, <a href="/web-llvm/docs/api/classes/anonymous-bpfasmprinter-cpp-/bpfasmprinter/#a83c424197528aeade7d84bfc2be9b074">anonymous{BPFAsmPrinter.cpp}::BPFAsmPrinter::printOperand</a>, <a href="/web-llvm/docs/api/classes/anonymous-lanaiasmprinter-cpp-/lanaiasmprinter/#accb05d49b5f0228bba4b29a4a0806756">anonymous{LanaiAsmPrinter.cpp}::LanaiAsmPrinter::printOperand</a>, <a href="/web-llvm/docs/api/classes/anonymous-msp430asmprinter-cpp-/msp430asmprinter/#adc984afaf62b041cceff164e14cdb889">anonymous{MSP430AsmPrinter.cpp}::MSP430AsmPrinter::printOperand</a>, <a href="/web-llvm/docs/api/classes/anonymous-ppcasmprinter-cpp-/ppcasmprinter/#ad00203b7ccef5249a4dda62efbd1be07">anonymous{PPCAsmPrinter.cpp}::PPCAsmPrinter::printOperand</a>, <a href="/web-llvm/docs/api/classes/anonymous-sparcasmprinter-cpp-/sparcasmprinter/#ace4a165fe83a11188e7e9393c2e6cbed">anonymous{SparcAsmPrinter.cpp}::SparcAsmPrinter::printOperand</a>, <a href="/web-llvm/docs/api/classes/anonymous-spirvasmprinter-cpp-/spirvasmprinter/#a84913da63189f7b4166625f0f01a37e5">anonymous{SPIRVAsmPrinter.cpp}::SPIRVAsmPrinter::printOperand</a>, <a href="/web-llvm/docs/api/classes/anonymous-xcoreasmprinter-cpp-/xcoreasmprinter/#a4e9f35f7c792ae53843a921999988ccb">anonymous{XCoreAsmPrinter.cpp}::XCoreAsmPrinter::printOperand</a>, <a href="/web-llvm/docs/api/classes/llvm/armasmprinter/#a3178261c88c74264649ee4b881e19306">llvm::ARMAsmPrinter::printOperand</a>, <a href="/web-llvm/docs/api/classes/llvm/avrasmprinter/#a7ddd6d21450d4f2269de2ab98fc8db6b">llvm::AVRAsmPrinter::printOperand</a>, <a href="/web-llvm/docs/api/classes/llvm/hexagonasmprinter/#aec3f83e468ca215a70dda2742816745c">llvm::HexagonAsmPrinter::printOperand</a> and <a href="/web-llvm/docs/api/classes/llvm/mipsasmprinter/#ad7367f761921fa5792918525c5082bac">llvm::MipsAsmPrinter::printOperand</a>.</p>

</div>
</div>

### hasAddressTaken() {#a86ae593fc791eda3aae24bd9d6df2322}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool llvm::MachineBasicBlock::hasAddressTaken ()</td>
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

<p>Test whether this block is used as something other than the target of a terminator, exception-handling target, or jump table.</p>


<p>This is either the result of an IR-level "blockaddress", or some form of target-specific branch lowering.</p>


<p>Definition at line 277 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/codegen/machinebasicblock-h">MachineBasicBlock.h</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/classes/llvm/machineloopinfo/#a80b0e6e28849491c5b267be8ffc909b4">llvm::MachineLoopInfo::findLoopPreheader</a> and <a href="/web-llvm/docs/api/structs/anonymous-ppcearlyreturn-cpp-/ppcearlyreturn/#ae036500138a9ae1567af6b28547cf045">anonymous{PPCEarlyReturn.cpp}::PPCEarlyReturn::processBlock</a>.</p>

</div>
</div>

### hasEHPadSuccessor() {#a07ccfc69389d4e9657d22698f4a7ef46}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool MachineBasicBlock::hasEHPadSuccessor ()</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Declaration at line 649 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/codegen/machinebasicblock-h">MachineBasicBlock.h</a>, definition at line 289 of file <a href="/web-llvm/docs/api/files/lib/lib/codegen/machinebasicblock-cpp">MachineBasicBlock.cpp</a>.</p>


<p>Reference <a href="#ad88ff1529541fb4e243cc8ed90b11131">successors</a>.</p>


<p>Referenced by <a href="#ae37b6ccdd5b2bdd9bc53dc0b634e3f7f">isLegalToHoistInto</a>.</p>

</div>
</div>

### hasLabelMustBeEmitted() {#a32eddb893169a26afe7e7372ecf943ef}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool llvm::MachineBasicBlock::hasLabelMustBeEmitted ()</td>
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

<p>Test whether this block must have its label emitted.</p>

<p>Definition at line 304 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/codegen/machinebasicblock-h">MachineBasicBlock.h</a>.</p>


<p>Referenced by <a href="#a1cc134bd22a318835dc929323da70ea4">getSymbol</a>.</p>

</div>
</div>

### hasName() {#a426db725707eef3025202e393420aa7f}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool MachineBasicBlock::hasName ()</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p><a href="/web-llvm/docs/api/namespaces/llvm/check">Check</a> if there is a name of corresponding LLVM basic block.</p>

<p>Declaration at line 265 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/codegen/machinebasicblock-h">MachineBasicBlock.h</a>, definition at line 320 of file <a href="/web-llvm/docs/api/files/lib/lib/codegen/machinebasicblock-cpp">MachineBasicBlock.cpp</a>.</p>


<p>Reference <a href="#a4874816314c3308be0bf1e71de2078d8">getBasicBlock</a>.</p>

</div>
</div>

### hasSuccessorProbabilities() {#aabd086dcf9e2397dc4d228b6b7d8c40f}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool llvm::MachineBasicBlock::hasSuccessorProbabilities ()</td>
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

<p>Return true if any of the successors have probabilities attached to them.</p>

<p>Definition at line 821 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/codegen/machinebasicblock-h">MachineBasicBlock.h</a>.</p>

</div>
</div>

### insert() {#a3435a2381e60e842e915f85c931b7dde}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">MachineBasicBlock::instr_iterator MachineBasicBlock::insert (<a href="#ab6395548cae73865213e279ae461db54">instr_iterator</a> I, <a href="/web-llvm/docs/api/classes/llvm/machineinstr">MachineInstr</a> * M)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Insert MI into the instruction list before I, possibly inside a bundle.</p>


<p>If the insertion point is inside a bundle, MI will be added to the bundle, otherwise MI will not be added to any bundle. That means this function alone can't be used to prepend or append instructions to bundles. See <a href="/web-llvm/docs/api/classes/llvm/mibundlebuilder/#aa4a15221a192683c58b5998fa42756ea">MIBundleBuilder::insert()</a> for a more reliable way of doing that.</p>


<p>Declaration at line 1019 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/codegen/machinebasicblock-h">MachineBasicBlock.h</a>, definition at line 1456 of file <a href="/web-llvm/docs/api/files/lib/lib/codegen/machinebasicblock-cpp">MachineBasicBlock.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/silowercontrolflow-cpp/#a4868c5d81c5ccc98c47aeab6244346a0">assert</a>, <a href="/web-llvm/docs/api/classes/llvm/machineinstr/#aafacf84de1cb994a92dc045f4aa1d518a9a9e5ef20669b2c9666b2689808b48ee">llvm::MachineInstr::BundledPred</a>, <a href="/web-llvm/docs/api/classes/llvm/machineinstr/#aafacf84de1cb994a92dc045f4aa1d518ad00e31da3877ce738df8343edcff6ed8">llvm::MachineInstr::BundledSucc</a>, <a href="/web-llvm/docs/api/files/lib/lib/support/md5-cpp/#ac0eafdc9ee161b71e7af98af736952fd">I</a>, <a href="#acae72f6ab1071b7ec87b741a8bef582b">instr_end</a> and <a href="/web-llvm/docs/api/files/lib/lib/codegen/lib/codegen/globalisel/irtranslator-cpp/#abe44dfdea65b4f7e11e0a608ab708b76">MI</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/namespaces/llvm/#a9a381a22976702d096a05acf1605c5bc">llvm::BuildMI</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#ac98e182e817bb53f2ff8135d29637dfb">llvm::BuildMI</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#ac441ac1e3b333caa1d41bee0d4fabbe8">llvm::BuildMI</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a2513bcbf688cb9218d16769edbba6a47">llvm::BuildMI</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#afa1fe17340600deeeb2a5647e56fc1a2">llvm::BuildMI</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a859007fbe974ffb4c1793877e4ada681">llvm::BuildMI</a>, <a href="/web-llvm/docs/api/files/lib/lib/codegen/cfifixup-cpp/#a6766bb9d415c3d929afaa24877e14fc6">cloneCfiPrologue</a>, <a href="/web-llvm/docs/api/classes/anonymous-sipeepholesdwa-cpp-/sdwadstpreserveoperand/#a9899e618878cac6bb75eafe4d46810f4">anonymous{SIPeepholeSDWA.cpp}::SDWADstPreserveOperand::convertToSDWA</a>, <a href="/web-llvm/docs/api/classes/llvm/scheduledagsdnodes/#a6f60ed03227dbeb711a3ae9b1f0238e9">llvm::ScheduleDAGSDNodes::EmitSchedule</a>, <a href="/web-llvm/docs/api/classes/anonymous-cskyconstantislandpass-cpp-/cskyconstantislands/#a800f62f10fe1fafc076ae4002371ba45">anonymous{CSKYConstantIslandPass.cpp}::CSKYConstantIslands::handleConstantPoolUser</a>, <a href="/web-llvm/docs/api/classes/anonymous-mipsconstantislandpass-cpp-/mipsconstantislands/#a4d3a04a082a7dd5b285cddb7feef368c">anonymous{MipsConstantIslandPass.cpp}::MipsConstantIslands::handleConstantPoolUser</a>, <a href="/web-llvm/docs/api/classes/llvm/regbankselect/insertpoint/#ac54a5d84d40b30695f8229f023d7ee69">llvm::RegBankSelect::InsertPoint::insert</a>, <a href="/web-llvm/docs/api/structs/llvm/siinstrworklist/#aed7def507592d4f53c51d552144531c5">llvm::SIInstrWorklist::insert</a>, <a href="/web-llvm/docs/api/classes/llvm/machineirbuilder/#a06dc2f24e1f4dea357bf6c646f5b2607">llvm::MachineIRBuilder::insertInstr</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/webassembly/webassemblyisellowering-cpp/#a5e660e19acc0643f71469b40cc016c2f">LowerCallResults</a>, <a href="/web-llvm/docs/api/classes/llvm/peelingmoduloscheduleexpander/#afe809699537758032938bea41ea44bb7">llvm::PeelingModuloScheduleExpander::moveStageBetweenBlocks</a>, <a href="/web-llvm/docs/api/classes/llvm/armbaseinstrinfo/#a12cb817575a9c4141e5a1268e6821503">llvm::ARMBaseInstrInfo::optimizeCompareInstr</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a0fdc13bfd373951ae6163637d6576c39">llvm::PeelSingleBlockLoop</a>, <a href="/web-llvm/docs/api/files/lib/lib/codegen/machinesink-cpp/#a1e64ed92fc7b343fa59c28105e16b794">performSink</a>, <a href="/web-llvm/docs/api/files/lib/lib/codegen/lib/codegen/selectiondag/scheduledagsdnodes-cpp/#aab3e2639c5eed5d618705678090fa23f">ProcessSDDbgValues</a>, <a href="/web-llvm/docs/api/classes/llvm/armblockplacement/#a977d1a0dea04c7f562cb1ca6063d81dd">llvm::ARMBlockPlacement::revertWhileToDoLoop</a>, <a href="/web-llvm/docs/api/classes/anonymous-webassemblyargumentmove-cpp-/webassemblyargumentmove/#aa44a7b836eacb5db2df92e3ae85693ef">anonymous{WebAssemblyArgumentMove.cpp}::WebAssemblyArgumentMove::runOnMachineFunction</a>, <a href="/web-llvm/docs/api/classes/llvm/selectiondagisel/#af17ffaab7d809b7d56e212a46f26f1a2">llvm::SelectionDAGISel::runOnMachineFunction</a>, <a href="/web-llvm/docs/api/classes/anonymous-cskyconstantislandpass-cpp-/cskyconstantislands/#ae708a0dc9c80038ba6d971c94eb9db5c">anonymous{CSKYConstantIslandPass.cpp}::CSKYConstantIslands::splitBlockBeforeInstr</a> and <a href="/web-llvm/docs/api/classes/anonymous-mipsconstantislandpass-cpp-/mipsconstantislands/#a747abf73a79323919b62fb98e61aeaf2">anonymous{MipsConstantIslandPass.cpp}::MipsConstantIslands::splitBlockBeforeInstr</a>.</p>

</div>
</div>

### insert() {#afc15ef658764e1532ae80037d5d6ba6d}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<div class="doxyMemberTemplate">template &lt;typename IT&gt;</div>
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void llvm::MachineBasicBlock::insert (<a href="#ae34c996b58df9b9ce6695a0c8b70c533">iterator</a> I, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/arm/armsubtarget-cpp/#a6f57985fa144303082fa7517a52e6db9">IT</a> S, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/arm/armsubtarget-cpp/#a6f57985fa144303082fa7517a52e6db9">IT</a> E)</td>
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

<p>Insert a range of instructions into the instruction list before I.</p>

<p>Definition at line 1023 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/codegen/machinebasicblock-h">MachineBasicBlock.h</a>.</p>


<p>References <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/silowercontrolflow-cpp/#a4868c5d81c5ccc98c47aeab6244346a0">assert</a>, <a href="/web-llvm/docs/api/files/lib/lib/ir/builtingcs-cpp/#abb2b3a60ccc38a28239e19a1646e0c8a">E</a>, <a href="#acbc921830578e2741be6549db716c0ce">end</a>, <a href="/web-llvm/docs/api/files/lib/lib/support/md5-cpp/#ac0eafdc9ee161b71e7af98af736952fd">I</a> and <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/arm/armsubtarget-cpp/#a6f57985fa144303082fa7517a52e6db9">IT</a>.</p>

</div>
</div>

### insert() {#a80512774162f8a8d15bd6e3b6739cf9b}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">iterator llvm::MachineBasicBlock::insert (<a href="#ae34c996b58df9b9ce6695a0c8b70c533">iterator</a> I, <a href="/web-llvm/docs/api/classes/llvm/machineinstr">MachineInstr</a> * MI)</td>
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

<p>Insert MI into the instruction list before I.</p>

<p>Definition at line 1030 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/codegen/machinebasicblock-h">MachineBasicBlock.h</a>.</p>


<p>References <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/silowercontrolflow-cpp/#a4868c5d81c5ccc98c47aeab6244346a0">assert</a>, <a href="#acbc921830578e2741be6549db716c0ce">end</a>, <a href="/web-llvm/docs/api/files/lib/lib/support/md5-cpp/#ac0eafdc9ee161b71e7af98af736952fd">I</a> and <a href="/web-llvm/docs/api/files/lib/lib/codegen/lib/codegen/globalisel/irtranslator-cpp/#abe44dfdea65b4f7e11e0a608ab708b76">MI</a>.</p>

</div>
</div>

### insertAfter() {#adbcec9820951b0e3872c94cbd4e57c80}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">iterator llvm::MachineBasicBlock::insertAfter (<a href="#ae34c996b58df9b9ce6695a0c8b70c533">iterator</a> I, <a href="/web-llvm/docs/api/classes/llvm/machineinstr">MachineInstr</a> * MI)</td>
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

<p>Insert MI into the instruction list after I.</p>

<p>Definition at line 1039 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/codegen/machinebasicblock-h">MachineBasicBlock.h</a>.</p>


<p>References <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/silowercontrolflow-cpp/#a4868c5d81c5ccc98c47aeab6244346a0">assert</a>, <a href="#acbc921830578e2741be6549db716c0ce">end</a>, <a href="/web-llvm/docs/api/files/lib/lib/support/md5-cpp/#ac0eafdc9ee161b71e7af98af736952fd">I</a> and <a href="/web-llvm/docs/api/files/lib/lib/codegen/lib/codegen/globalisel/irtranslator-cpp/#abe44dfdea65b4f7e11e0a608ab708b76">MI</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/webassembly/webassemblyisellowering-cpp/#a5e660e19acc0643f71469b40cc016c2f">LowerCallResults</a> and <a href="/web-llvm/docs/api/classes/llvm/selectiondagisel/#af17ffaab7d809b7d56e212a46f26f1a2">llvm::SelectionDAGISel::runOnMachineFunction</a>.</p>

</div>
</div>

### insertAfterBundle() {#aec460b7ed48d97ed84ae2466b498763f}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">instr_iterator llvm::MachineBasicBlock::insertAfterBundle (<a href="#ab6395548cae73865213e279ae461db54">instr_iterator</a> I, <a href="/web-llvm/docs/api/classes/llvm/machineinstr">MachineInstr</a> * MI)</td>
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

<p>If I is bundled then insert MI into the instruction list after the end of the bundle, otherwise insert MI immediately after I.</p>

<p>Definition at line 1049 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/codegen/machinebasicblock-h">MachineBasicBlock.h</a>.</p>


<p>References <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/silowercontrolflow-cpp/#a4868c5d81c5ccc98c47aeab6244346a0">assert</a>, <a href="/web-llvm/docs/api/files/lib/lib/support/md5-cpp/#ac0eafdc9ee161b71e7af98af736952fd">I</a>, <a href="#acae72f6ab1071b7ec87b741a8bef582b">instr_end</a> and <a href="/web-llvm/docs/api/files/lib/lib/codegen/lib/codegen/globalisel/irtranslator-cpp/#abe44dfdea65b4f7e11e0a608ab708b76">MI</a>.</p>

</div>
</div>

### instr\_back() {#a90c02828bcc7a77219045d7869b54304}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">MachineInstr &amp; llvm::MachineBasicBlock::instr_back ()</td>
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



<p>Definition at line 339 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/codegen/machinebasicblock-h">MachineBasicBlock.h</a>.</p>

</div>
</div>

### instr\_back() {#a7510abf5520cdbffac84302d49b2ebc0}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">const MachineInstr &amp; llvm::MachineBasicBlock::instr_back ()</td>
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



<p>Definition at line 341 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/codegen/machinebasicblock-h">MachineBasicBlock.h</a>.</p>

</div>
</div>

### instr\_begin() {#a172e7bd9150eb0519ef04c796086f93d}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">instr_iterator llvm::MachineBasicBlock::instr_begin ()</td>
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



<p>Definition at line 348 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/codegen/machinebasicblock-h">MachineBasicBlock.h</a>.</p>


<p>Referenced by <a href="#ab2d91e7bec944efcbc39d8e30644f111">begin</a>, <a href="#aa86c88f644b3ccab5bac660ca5f45760">begin</a>, <a href="/web-llvm/docs/api/classes/anonymous-ppcbranchcoalescing-cpp-/ppcbranchcoalescing/#a481db3ca9a03829503a402a2318a27b1">anonymous{PPCBranchCoalescing.cpp}::PPCBranchCoalescing::canMerge</a>, <a href="/web-llvm/docs/api/namespaces/anonymous-machinelooputils-cpp-/#aff0a1cdc0a759d052259cb36a260ce10">anonymous{MachineLoopUtils.cpp}::findEquivalentInstruction</a>, <a href="#abfe76200d04557c617e5f505717c3ad3">findPrevDebugLoc</a>, <a href="#ad8c65b86ef286331d408a7a74c7b0b2f">getFirstInstrTerminator</a>, <a href="#aa7dc7faaab4856b8f0014b8283e26c7b">getFirstNonPHI</a>, <a href="#ab8d7b8ff6803133d567fd4240e6364ce">getLastNonDebugInstr</a>, <a href="#a40bf8f9579717d3f9be7640f1c6d678b">instrs</a>, <a href="#a6b367cbab4e273612adc65fddbce0e91">instrs</a>, <a href="/web-llvm/docs/api/classes/llvm/hexagoninstrinfo/#ad60287ef8b5a83a38ec5f29bce7bf43c">llvm::HexagonInstrInfo::nonDbgBBSize</a>, <a href="#ab9a54fdc7456ee97cb54ff30d625b6b7">ReplaceUsesOfBlockWith</a>, <a href="#ab2192a3dc7e43ace4706a00258bf5f47">rfindDebugLoc</a>, <a href="/web-llvm/docs/api/classes/anonymous-x86flagscopylowering-cpp-/x86flagscopyloweringpass/#a30d90e84a3faa0cd7aa2c3b96d65c232">anonymous{X86FlagsCopyLowering.cpp}::X86FlagsCopyLoweringPass::runOnMachineFunction</a>, <a href="/web-llvm/docs/api/classes/anonymous-hexagonloopalign-cpp-/hexagonloopalign/#a9147ecc832d6583c9c129bd4ddcb0488">anonymous{HexagonLoopAlign.cpp}::HexagonLoopAlign::shouldBalignLoop</a> and <a href="#aa80aaa82844ab5560ece045eee7b34ac">SplitCriticalEdge</a>.</p>

</div>
</div>

### instr\_begin() {#a51830f3957f907531febde4c3fbf25d1}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">const_instr_iterator llvm::MachineBasicBlock::instr_begin ()</td>
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



<p>Definition at line 349 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/codegen/machinebasicblock-h">MachineBasicBlock.h</a>.</p>

</div>
</div>

### instr\_end() {#acae72f6ab1071b7ec87b741a8bef582b}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">instr_iterator llvm::MachineBasicBlock::instr_end ()</td>
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



<p>Definition at line 350 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/codegen/machinebasicblock-h">MachineBasicBlock.h</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/classes/llvm/gcnsubtarget/#a38ff3df1feb7915dfda6303a34484534">llvm::GCNSubtarget::adjustSchedDependency</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/riscv/riscvisellowering-cpp/#a59f08a4b78badcbfff06545894a60e6e">emitSelectPseudo</a>, <a href="#acbc921830578e2741be6549db716c0ce">end</a>, <a href="#aec6d7041bedf7535f7565f3e9471a5bd">end</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a8d6c4616e2c2cc90d58377868eda6102">llvm::examineCFlagsUse</a>, <a href="#ab622d694b5fcb0edb99159f1ebdcdb6b">findDebugLoc</a>, <a href="#ad8c65b86ef286331d408a7a74c7b0b2f">getFirstInstrTerminator</a>, <a href="#aa7dc7faaab4856b8f0014b8283e26c7b">getFirstNonPHI</a>, <a href="#ab8d7b8ff6803133d567fd4240e6364ce">getLastNonDebugInstr</a>, <a href="#a3435a2381e60e842e915f85c931b7dde">insert</a>, <a href="#aec460b7ed48d97ed84ae2466b498763f">insertAfterBundle</a>, <a href="#a40bf8f9579717d3f9be7640f1c6d678b">instrs</a>, <a href="#a6b367cbab4e273612adc65fddbce0e91">instrs</a>, <a href="/web-llvm/docs/api/classes/llvm/hexagoninstrinfo/#ad60287ef8b5a83a38ec5f29bce7bf43c">llvm::HexagonInstrInfo::nonDbgBBSize</a>, <a href="#ab9a54fdc7456ee97cb54ff30d625b6b7">ReplaceUsesOfBlockWith</a>, <a href="/web-llvm/docs/api/classes/anonymous-x86flagscopylowering-cpp-/x86flagscopyloweringpass/#a30d90e84a3faa0cd7aa2c3b96d65c232">anonymous{X86FlagsCopyLowering.cpp}::X86FlagsCopyLoweringPass::runOnMachineFunction</a>, <a href="/web-llvm/docs/api/classes/anonymous-hexagonloopalign-cpp-/hexagonloopalign/#a9147ecc832d6583c9c129bd4ddcb0488">anonymous{HexagonLoopAlign.cpp}::HexagonLoopAlign::shouldBalignLoop</a> and <a href="#aa80aaa82844ab5560ece045eee7b34ac">SplitCriticalEdge</a>.</p>

</div>
</div>

### instr\_end() {#aa122564bb9dcd534ae31eea9a6dc6ebb}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">const_instr_iterator llvm::MachineBasicBlock::instr_end ()</td>
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



<p>Definition at line 351 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/codegen/machinebasicblock-h">MachineBasicBlock.h</a>.</p>

</div>
</div>

### instr\_front() {#ae59809519f8d4797e1c8833cc85fda54}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">MachineInstr &amp; llvm::MachineBasicBlock::instr_front ()</td>
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



<p>Definition at line 338 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/codegen/machinebasicblock-h">MachineBasicBlock.h</a>.</p>

</div>
</div>

### instr\_front() {#a00e3db961381c3ca1eca33de53227f6a}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">const MachineInstr &amp; llvm::MachineBasicBlock::instr_front ()</td>
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



<p>Definition at line 340 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/codegen/machinebasicblock-h">MachineBasicBlock.h</a>.</p>

</div>
</div>

### instr\_rbegin() {#a3758eeb6d9f052f15217146b4ae4d5a1}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">reverse_instr_iterator llvm::MachineBasicBlock::instr_rbegin ()</td>
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



<p>Definition at line 352 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/codegen/machinebasicblock-h">MachineBasicBlock.h</a>.</p>


<p>Referenced by <a href="#ad8c9657cfb03ef2ebf6364ba9d68c127">rbegin</a>, <a href="#a6c8e031b0c3396d32f8ed87dfda16a7d">rbegin</a> and <a href="#ab2192a3dc7e43ace4706a00258bf5f47">rfindDebugLoc</a>.</p>

</div>
</div>

### instr\_rbegin() {#aeb5e3dec197ec0f4bfb5ae384fb6175b}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">const_reverse_instr_iterator llvm::MachineBasicBlock::instr_rbegin ()</td>
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



<p>Definition at line 353 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/codegen/machinebasicblock-h">MachineBasicBlock.h</a>.</p>

</div>
</div>

### instr\_rend() {#ab42a834f1ab8e65b6f525a5cb23a4fe7}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">reverse_instr_iterator llvm::MachineBasicBlock::instr_rend ()</td>
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



<p>Definition at line 354 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/codegen/machinebasicblock-h">MachineBasicBlock.h</a>.</p>


<p>Referenced by <a href="#a2a25c462b91ac5da41f4ab7edc32b650">rend</a>, <a href="#ab4d33f4fc1545c32aa8bef180f5dbc19">rend</a>, <a href="#ab2192a3dc7e43ace4706a00258bf5f47">rfindDebugLoc</a> and <a href="#a01356cc615c2222dba3e1b2776800add">rfindPrevDebugLoc</a>.</p>

</div>
</div>

### instr\_rend() {#a36234942b757e726441b9622bdcfd85b}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">const_reverse_instr_iterator llvm::MachineBasicBlock::instr_rend ()</td>
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



<p>Definition at line 355 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/codegen/machinebasicblock-h">MachineBasicBlock.h</a>.</p>

</div>
</div>

### instrs() {#a40bf8f9579717d3f9be7640f1c6d678b}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">instr_range llvm::MachineBasicBlock::instrs ()</td>
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



<p>Definition at line 359 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/codegen/machinebasicblock-h">MachineBasicBlock.h</a>.</p>


<p>References <a href="#a172e7bd9150eb0519ef04c796086f93d">instr_begin</a> and <a href="#acae72f6ab1071b7ec87b741a8bef582b">instr_end</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/classes/llvm/armbaseinstrinfo/#a637fe9208c860066ecf02233cd258f9b">llvm::ARMBaseInstrInfo::analyzeLoopForPipelining</a>, <a href="/web-llvm/docs/api/namespaces/anonymous-basicblockpathcloning-cpp-/#a0150e86671c87ec3046e8ba46be9f151">anonymous{BasicBlockPathCloning.cpp}::CloneMachineBasicBlock</a>, <a href="/web-llvm/docs/api/classes/llvm/ppcinstrinfo/#a9f6bd20f6d3bb4bb60d84472550ab6e5">llvm::PPCInstrInfo::findLoopInstr</a>, <a href="#a0fab3e644b3457f90ed7f64876a037d2">getFirstTerminatorForward</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#acd2fa20a564d31aed52db5cb081bc4d9">llvm::instrs</a> and <a href="#a5a4302f4590a281bb84e08b30c80591c">print</a>.</p>

</div>
</div>

### instrs() {#a6b367cbab4e273612adc65fddbce0e91}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">const_instr_range llvm::MachineBasicBlock::instrs ()</td>
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



<p>Definition at line 360 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/codegen/machinebasicblock-h">MachineBasicBlock.h</a>.</p>


<p>References <a href="#a172e7bd9150eb0519ef04c796086f93d">instr_begin</a> and <a href="#acae72f6ab1071b7ec87b741a8bef582b">instr_end</a>.</p>

</div>
</div>

### isBeginSection() {#ad4835355c1e5ca306abd15f5b90bd9b4}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool llvm::MachineBasicBlock::isBeginSection ()</td>
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

<p>Returns true if this block begins any section.</p>

<p>Definition at line 681 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/codegen/machinebasicblock-h">MachineBasicBlock.h</a>.</p>


<p>Referenced by <a href="#a1cc134bd22a318835dc929323da70ea4">getSymbol</a>.</p>

</div>
</div>

### isCleanupFuncletEntry() {#afe9ba3711c6b7625da1425cc0a7b3f10}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool llvm::MachineBasicBlock::isCleanupFuncletEntry ()</td>
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

<p>Returns true if this is the entry block of a cleanup funclet.</p>

<p>Definition at line 675 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/codegen/machinebasicblock-h">MachineBasicBlock.h</a>.</p>

</div>
</div>

### isEHCatchretTarget() {#a9f5f0a44387ca86786022bf55c3cb41e}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool llvm::MachineBasicBlock::isEHCatchretTarget ()</td>
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

<p>Returns true if this is a target block of a catchret.</p>

<p>Definition at line 663 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/codegen/machinebasicblock-h">MachineBasicBlock.h</a>.</p>

</div>
</div>

### isEHFuncletEntry() {#a7d2f8efd82042b4cf611ba10e9e79ed0}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool llvm::MachineBasicBlock::isEHFuncletEntry ()</td>
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

<p>Returns true if this is the entry block of an EH funclet.</p>

<p>Definition at line 669 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/codegen/machinebasicblock-h">MachineBasicBlock.h</a>.</p>


<p>Referenced by <a href="#a864dfd605ab4c40b895d035a165a873b">getBeginClobberMask</a>, <a href="#adad68dd11c1995cc4f63e51986f50ce0">printName</a> and <a href="/web-llvm/docs/api/classes/anonymous-x86avoidtrailingcall-cpp-/x86avoidtrailingcallpass/#aecb6e2ec27a2aa4a52e980e61f0f742b">anonymous{X86AvoidTrailingCall.cpp}::X86AvoidTrailingCallPass::runOnMachineFunction</a>.</p>

</div>
</div>

### isEHPad() {#a1100bfbadd996d464150c6a68fa8dc1d}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool llvm::MachineBasicBlock::isEHPad ()</td>
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

<p>Returns true if the block is a landing pad.</p>


<p>That is this basic block is entered via an exception handler.</p>


<p>Definition at line 643 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/codegen/machinebasicblock-h">MachineBasicBlock.h</a>.</p>


<p>Referenced by <a href="#a9bd7c04e374ad15665430a243dd30d80">addLiveIn</a>, <a href="#ae32dc74389a52cbb83e6a016274142f5">canSplitCriticalEdge</a>, <a href="/web-llvm/docs/api/files/lib/lib/codegen/analysis-cpp/#a86959c09e02e571589af525c983cdf4e">collectEHScopeMembers</a>, <a href="/web-llvm/docs/api/namespaces/llvm/webassembly/#a6cc6351696a872f05cdf540a663d584c">llvm::WebAssembly::findCatch</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#ae5498526c74722ab28fc494f37de2ea8">llvm::findPHICopyInsertPoint</a>, <a href="#adad68dd11c1995cc4f63e51986f50ce0">printName</a>, <a href="/web-llvm/docs/api/classes/llvm/webassemblyexceptioninfo/#a6248704cecd958d5eeb84fa3536fc78c">llvm::WebAssemblyExceptionInfo::recalculate</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/x86/x86speculativeloadhardening-cpp/#a18b17899654dd5adb69b62c89ba95783">splitEdge</a> and <a href="#a5803a49facae20ca4b002dcba6f1d03e">updateTerminator</a>.</p>

</div>
</div>

### isEHScopeEntry() {#a8d7d10ec1863b6601b83523da37401e6}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool llvm::MachineBasicBlock::isEHScopeEntry ()</td>
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

<p>Returns true if this is the entry block of an EH scope, i.e., the block that used to have a catchpad or cleanuppad instruction in the LLVM IR.</p>

<p>Definition at line 656 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/codegen/machinebasicblock-h">MachineBasicBlock.h</a>.</p>

</div>
</div>

### isEHScopeReturnBlock() {#adf1c64c05c8afb975b979543f8f850df}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool llvm::MachineBasicBlock::isEHScopeReturnBlock ()</td>
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

<p>Convenience function that returns true if the bock ends in a EH scope return instruction.</p>

<p>Definition at line 963 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/codegen/machinebasicblock-h">MachineBasicBlock.h</a>.</p>


<p>References <a href="#acf35424231192c6b4a3e22d711f50b1e">back</a>, <a href="#a095ce2d870dadf620a4c887ecc0efef8">empty</a> and <a href="/web-llvm/docs/api/classes/llvm/machineinstr/#abefa2936f2beea06e735ee3887f5b6c4">llvm::MachineInstr::isEHScopeReturn</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/files/lib/lib/codegen/analysis-cpp/#a86959c09e02e571589af525c983cdf4e">collectEHScopeMembers</a>.</p>

</div>
</div>

### isEndSection() {#ae0fd0a5397ceb88bd0d58ecb1708e1dc}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool llvm::MachineBasicBlock::isEndSection ()</td>
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

<p>Returns true if this block ends any section.</p>

<p>Definition at line 684 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/codegen/machinebasicblock-h">MachineBasicBlock.h</a>.</p>

</div>
</div>

### isEntryBlock() {#a9103c1c7b60d793b0efd41c741286508}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool MachineBasicBlock::isEntryBlock ()</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Returns true if this is the entry block of the function.</p>

<p>Declaration at line 652 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/codegen/machinebasicblock-h">MachineBasicBlock.h</a>, definition at line 296 of file <a href="/web-llvm/docs/api/files/lib/lib/codegen/machinebasicblock-cpp">MachineBasicBlock.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/classes/llvm/machinefunction/#ab0789854909cf47f640a85fa2bac29c7">llvm::MachineFunction::begin</a>, <a href="/web-llvm/docs/api/classes/llvm/ilist-node-impl/#af719fc783be6589465137d997701a432">llvm::ilist_node_impl&lt; ilist_detail::compute_node_options&lt; MachineBasicBlock, Options... &gt;::type &gt;::getIterator</a> and <a href="#acf6442108e21e7e5379feb8962de65b7">getParent</a>.</p>

</div>
</div>

### isInlineAsmBrIndirectTarget() {#a00e55a6b6b44b739e9da1d62f1d8a5b3}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool llvm::MachineBasicBlock::isInlineAsmBrIndirectTarget ()</td>
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

<p>Returns true if this is the indirect dest of an INLINEASM_BR.</p>

<p>Definition at line 713 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/codegen/machinebasicblock-h">MachineBasicBlock.h</a>.</p>


<p>Referenced by <a href="#ae32dc74389a52cbb83e6a016274142f5">canSplitCriticalEdge</a>, <a href="/web-llvm/docs/api/classes/llvm/tailduplicator/#a8fffb36a3e1523ff3d26521f27c02df8">llvm::TailDuplicator::canTailDuplicate</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#ae5498526c74722ab28fc494f37de2ea8">llvm::findPHICopyInsertPoint</a> and <a href="#adad68dd11c1995cc4f63e51986f50ce0">printName</a>.</p>

</div>
</div>

### isIRBlockAddressTaken() {#a753336faa16076c3931ae29c55f88f68}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool llvm::MachineBasicBlock::isIRBlockAddressTaken ()</td>
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

<p>Test whether this block is the target of an IR <a href="/web-llvm/docs/api/classes/llvm/blockaddress">BlockAddress</a>.</p>


<p>(There can more than one MBB associated with an IR BB where the address is taken.)</p>


<p>Definition at line 289 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/codegen/machinebasicblock-h">MachineBasicBlock.h</a>.</p>


<p>Referenced by <a href="#adad68dd11c1995cc4f63e51986f50ce0">printName</a> and <a href="#a703ba58bd58d60cd76ad205dda1634eb">terminatorIsComputedGoto</a>.</p>

</div>
</div>

### isLayoutSuccessor() {#abd85c9d7c51eb515a550069e9ad9445e}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool MachineBasicBlock::isLayoutSuccessor (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/machinebasicblock">MachineBasicBlock</a> * MBB)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Return true if the specified MBB will be emitted immediately after this block, such that if this block exits by falling through, control will transfer to the specified MBB.</p>


<p>Note that MBB need not be a successor at all, for example if this block ends with an unconditional branch to some other block.</p>


<p>Declaration at line 834 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/codegen/machinebasicblock-h">MachineBasicBlock.h</a>, definition at line 964 of file <a href="/web-llvm/docs/api/files/lib/lib/codegen/machinebasicblock-cpp">MachineBasicBlock.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/files/lib/lib/support/md5-cpp/#ac0eafdc9ee161b71e7af98af736952fd">I</a> and <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/arm/armslshardening-cpp/#a5958512eae2979bd2eb383977996a600">MBB</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/structs/anonymous-ppcearlyreturn-cpp-/ppcearlyreturn/#ae036500138a9ae1567af6b28547cf045">anonymous{PPCEarlyReturn.cpp}::PPCEarlyReturn::processBlock</a>, <a href="/web-llvm/docs/api/files/lib/lib/codegen/branchfolding-cpp/#a905140abedaee343fc7ef33707052792">ProfitableToMerge</a>, <a href="/web-llvm/docs/api/classes/anonymous-hexagoncfgoptimizer-cpp-/hexagoncfgoptimizer/#a44a6c0917383ba77dca7325a7b23c252">anonymous{HexagonCFGOptimizer.cpp}::HexagonCFGOptimizer::runOnMachineFunction</a>, <a href="#aa80aaa82844ab5560ece045eee7b34ac">SplitCriticalEdge</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/x86/x86speculativeloadhardening-cpp/#a18b17899654dd5adb69b62c89ba95783">splitEdge</a>, <a href="#a5803a49facae20ca4b002dcba6f1d03e">updateTerminator</a> and <a href="/web-llvm/docs/api/files/lib/lib/codegen/shrinkwrap-cpp/#a0d669f3a4d6e865cc9d89c43e230976f">updateTerminator</a>.</p>

</div>
</div>

### isLegalToHoistInto() {#ae37b6ccdd5b2bdd9bc53dc0b634e3f7f}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool MachineBasicBlock::isLegalToHoistInto ()</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Returns true if it is legal to hoist instructions into this block.</p>

<p>Declaration at line 723 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/codegen/machinebasicblock-h">MachineBasicBlock.h</a>, definition at line 314 of file <a href="/web-llvm/docs/api/files/lib/lib/codegen/machinebasicblock-cpp">MachineBasicBlock.cpp</a>.</p>


<p>References <a href="#a07ccfc69389d4e9657d22698f4a7ef46">hasEHPadSuccessor</a>, <a href="#a82f5d244972c88ff03ee56d6c090ac70">isReturnBlock</a> and <a href="#aefb323794dab5bb00d738a3f32dd65e6">mayHaveInlineAsmBr</a>.</p>

</div>
</div>

### isLiveIn() {#af9745f59d6647bd43f9f7959ca1a9971}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool MachineBasicBlock::isLiveIn (<a href="/web-llvm/docs/api/classes/llvm/mcregister">MCRegister</a> Reg, <a href="/web-llvm/docs/api/structs/llvm/lanebitmask">LaneBitmask</a> LaneMask=<a href="/web-llvm/docs/api/structs/llvm/lanebitmask/#a3714a639930eab71d7202da05ad82990">LaneBitmask::getAll</a>())</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Return true if the specified register is in the live in set.</p>

<p>Declaration at line 495 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/codegen/machinebasicblock-h">MachineBasicBlock.h</a>, definition at line 618 of file <a href="/web-llvm/docs/api/files/lib/lib/codegen/machinebasicblock-cpp">MachineBasicBlock.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/namespaces/llvm/#ac78c09ae232b2ce188ff590d51e3c268">llvm::find_if</a>, <a href="/web-llvm/docs/api/files/lib/lib/support/md5-cpp/#ac0eafdc9ee161b71e7af98af736952fd">I</a>, <a href="#a0e76d75564a8460bd9f2822f7ad49b1f">livein_end</a> and <a href="/web-llvm/docs/api/structs/llvm/machinebasicblock/registermaskpair/#aec870716714bddabfc363a79a44a52ca">llvm::MachineBasicBlock::RegisterMaskPair::PhysReg</a>.</p>


<p>Referenced by <a href="#a9bd7c04e374ad15665430a243dd30d80">addLiveIn</a>, <a href="/web-llvm/docs/api/classes/llvm/x86targetlowering/#a5fd231b7f6dc1db67a2bb2f48bf5f342">llvm::X86TargetLowering::EmitInstrWithCustomInserter</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a02134e88cd18139c71d9274c7d287ac3">llvm::getFunctionLiveInPhysReg</a>, <a href="/web-llvm/docs/api/classes/llvm/systemzxplinkframelowering/#a35f79e8cb7551ca57450108d9816b2ba">llvm::SystemZXPLINKFrameLowering::inlineStackProbe</a>, <a href="/web-llvm/docs/api/classes/llvm/systemzelfframelowering/#ae45b5d3065cf62a7eac0053f27cb8103">llvm::SystemZELFFrameLowering::processFunctionBeforeFrameFinalized</a> and <a href="/web-llvm/docs/api/classes/anonymous-x86flagscopylowering-cpp-/x86flagscopyloweringpass/#a30d90e84a3faa0cd7aa2c3b96d65c232">anonymous{X86FlagsCopyLowering.cpp}::X86FlagsCopyLoweringPass::runOnMachineFunction</a>.</p>

</div>
</div>

### isMachineBlockAddressTaken() {#ad934138cd088f6c08cbf0f373997fd17}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool llvm::MachineBasicBlock::isMachineBlockAddressTaken ()</td>
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

<p>Test whether this block is used as something other than the target of a terminator, exception-handling target, jump table, or IR blockaddress.</p>


<p>For example, its address might be loaded into a register, or stored in some branch table that isn't part of <a href="/web-llvm/docs/api/classes/llvm/machinejumptableinfo">MachineJumpTableInfo</a>.</p>


<p>Definition at line 285 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/codegen/machinebasicblock-h">MachineBasicBlock.h</a>.</p>


<p>Referenced by <a href="#adad68dd11c1995cc4f63e51986f50ce0">printName</a>.</p>

</div>
</div>

### isPredecessor() {#aaa71c733e5aa6113e60a3a806e01bb10}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool MachineBasicBlock::isPredecessor (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/machinebasicblock">MachineBasicBlock</a> * MBB)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Return true if the specified MBB is a predecessor of this block.</p>

<p>Declaration at line 824 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/codegen/machinebasicblock-h">MachineBasicBlock.h</a>, definition at line 956 of file <a href="/web-llvm/docs/api/files/lib/lib/codegen/machinebasicblock-cpp">MachineBasicBlock.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/namespaces/llvm/#acd1cd968cb420c82d70926920fcdc7d7">llvm::is_contained</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/arm/armslshardening-cpp/#a5958512eae2979bd2eb383977996a600">MBB</a> and <a href="#addd80df79ba902914c7d8a52e3896b79">predecessors</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/classes/llvm/machinetracemetrics/ensemble/#a063217bcbb8b81adfdc88feb1a52ddcb">llvm::MachineTraceMetrics::Ensemble::invalidate</a> and <a href="/web-llvm/docs/api/structs/anonymous-machineverifier-cpp-/machineverifier/#a97c94504ca3d3dcb826cd34ec463f98e">anonymous{MachineVerifier.cpp}::MachineVerifier::verifyInlineAsm</a>.</p>

</div>
</div>

### isReturnBlock() {#a82f5d244972c88ff03ee56d6c090ac70}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool llvm::MachineBasicBlock::isReturnBlock ()</td>
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

<p>Convenience function that returns true if the block ends in a return instruction.</p>

<p>Definition at line 957 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/codegen/machinebasicblock-h">MachineBasicBlock.h</a>.</p>


<p>References <a href="#acf35424231192c6b4a3e22d711f50b1e">back</a>, <a href="#a095ce2d870dadf620a4c887ecc0efef8">empty</a> and <a href="/web-llvm/docs/api/classes/llvm/machineinstr/#a04af1d639a21e7ef4357facd283b42c4">llvm::MachineInstr::isReturn</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/classes/anonymous-silowersgprspills-cpp-/silowersgprspills/#a5647b98ce7f0b4ad6fedc71a993e9979">anonymous{SILowerSGPRSpills.cpp}::SILowerSGPRSpills::calculateSaveRestoreBlocks</a>, <a href="/web-llvm/docs/api/classes/llvm/riscvframelowering/#a4c55a328d2daf9b5e2f457c8880e21c4">llvm::RISCVFrameLowering::canUseAsEpilogue</a>, <a href="#af80cc22ae7f226a8c819be6bf9e731d4">getEndClobberMask</a>, <a href="#ae37b6ccdd5b2bdd9bc53dc0b634e3f7f">isLegalToHoistInto</a>, <a href="/web-llvm/docs/api/classes/llvm/aggressiveantidepbreaker/#abd095bb58a0243946704d20d3559d420">llvm::AggressiveAntiDepBreaker::StartBlock</a> and <a href="/web-llvm/docs/api/classes/llvm/criticalantidepbreaker/#adb4573a84f25279673e3906914132a39">llvm::CriticalAntiDepBreaker::StartBlock</a>.</p>

</div>
</div>

### isSuccessor() {#adc8f1be4a77ae671ac139d5f06b44deb}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool MachineBasicBlock::isSuccessor (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/machinebasicblock">MachineBasicBlock</a> * MBB)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Return true if the specified MBB is a successor of this block.</p>

<p>Declaration at line 827 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/codegen/machinebasicblock-h">MachineBasicBlock.h</a>, definition at line 960 of file <a href="/web-llvm/docs/api/files/lib/lib/codegen/machinebasicblock-cpp">MachineBasicBlock.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/namespaces/llvm/#acd1cd968cb420c82d70926920fcdc7d7">llvm::is_contained</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/arm/armslshardening-cpp/#a5958512eae2979bd2eb383977996a600">MBB</a> and <a href="#ad88ff1529541fb4e243cc8ed90b11131">successors</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/powerpc/ppcreducecrlogicals-cpp/#ac2fc7f2c8237332f8b99c6e88af1b678">addIncomingValuesToPHIs</a>, <a href="/web-llvm/docs/api/structs/anonymous-machineverifier-cpp-/machineverifier/#a1d5250336b7b5e6c5f3c8e88fb9a9041">anonymous{MachineVerifier.cpp}::MachineVerifier::checkPHIOps</a>, <a href="/web-llvm/docs/api/classes/anonymous-r600machinecfgstructurizer-cpp-/r600machinecfgstructurizer/#a8945ac962ff2d369b77ff9ab927529a4">anonymous{R600MachineCFGStructurizer.cpp}::R600MachineCFGStructurizer::cloneBlockForPredecessor</a>, <a href="/web-llvm/docs/api/classes/anonymous-r600machinecfgstructurizer-cpp-/r600machinecfgstructurizer/#ab90cb03c7501b031fa63735cc9391a5f">anonymous{R600MachineCFGStructurizer.cpp}::R600MachineCFGStructurizer::cloneOnSideEntryTo</a>, <a href="#a31aa2680ec79198a4c94f35b3a1ad97e">getFallThrough</a>, <a href="/web-llvm/docs/api/files/lib/lib/codegen/machineblockplacement-cpp/#a3d135a8abf70dc93455708cc087cc0b0">getLayoutSuccessorProbThreshold</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/mips/mipsbranchexpansion-cpp/#a4801e594c6226fb9020a07ca36641c5b">getNextMachineInstr</a>, <a href="/web-llvm/docs/api/classes/llvm/machinetracemetrics/ensemble/#a063217bcbb8b81adfdc88feb1a52ddcb">llvm::MachineTraceMetrics::Ensemble::invalidate</a>, <a href="/web-llvm/docs/api/files/lib/lib/codegen/branchfolding-cpp/#acda790896623fd894c71bf79f1bbcfea">IsBetterFallthrough</a>, <a href="/web-llvm/docs/api/namespaces/anonymous-basicblockpathcloning-cpp-/#abbaff7e4a8cdaa59924d29ba6e305f4a">anonymous{BasicBlockPathCloning.cpp}::IsValidCloning</a>, <a href="/web-llvm/docs/api/classes/llvm/armblockplacement/#aa13bb5e066b0419461ad1bbdd7bc9a1d">llvm::ARMBlockPlacement::moveBasicBlock</a>, <a href="/web-llvm/docs/api/classes/anonymous-miparser-cpp-/miparser/#a3904021432d1d4cf1620b9c09506e612">anonymous{MIParser.cpp}::MIParser::parseBasicBlocks</a>, <a href="/web-llvm/docs/api/classes/anonymous-hexagoncfgoptimizer-cpp-/hexagoncfgoptimizer/#a44a6c0917383ba77dca7325a7b23c252">anonymous{HexagonCFGOptimizer.cpp}::HexagonCFGOptimizer::runOnMachineFunction</a>, <a href="/web-llvm/docs/api/classes/llvm/tailduplicator/#aa7dba30d4d9162f00367404e06085391">llvm::TailDuplicator::shouldTailDuplicate</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/powerpc/ppcreducecrlogicals-cpp/#ac47046162deb21d43512581afc16fa7c">updatePHIs</a>, <a href="#a5803a49facae20ca4b002dcba6f1d03e">updateTerminator</a> and <a href="/web-llvm/docs/api/structs/anonymous-machineverifier-cpp-/machineverifier/#a16957e467c8bf1aa4c3c8614d7315709">anonymous{MachineVerifier.cpp}::MachineVerifier::visitMachineOperand</a>.</p>

</div>
</div>

### livein\_begin() {#a81335545907243d4dea1a276f01566c0}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">MachineBasicBlock::livein_iterator MachineBasicBlock::livein_begin ()</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Declaration at line 511 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/codegen/machinebasicblock-h">MachineBasicBlock.h</a>, definition at line 1753 of file <a href="/web-llvm/docs/api/files/lib/lib/codegen/machinebasicblock-cpp">MachineBasicBlock.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/silowercontrolflow-cpp/#a4868c5d81c5ccc98c47aeab6244346a0">assert</a>, <a href="#acf6442108e21e7e5379feb8962de65b7">getParent</a> and <a href="/web-llvm/docs/api/classes/llvm/machinefunctionproperties/#ad85237c6c667e4713efe8921e9c32ac1a0020348b08bb4cccecf3241eac999d8a">llvm::MachineFunctionProperties::TracksLiveness</a>.</p>


<p>Referenced by <a href="#a364ed6e68f92f797c0cd9e53ce5ea2a5">liveins</a> and <a href="/web-llvm/docs/api/classes/anonymous-hexagoncfgoptimizer-cpp-/hexagoncfgoptimizer/#a44a6c0917383ba77dca7325a7b23c252">anonymous{HexagonCFGOptimizer.cpp}::HexagonCFGOptimizer::runOnMachineFunction</a>.</p>

</div>
</div>

### livein\_begin\_dbg() {#ab01e076c631849cba69494483703600a}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">livein_iterator llvm::MachineBasicBlock::livein_begin_dbg ()</td>
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

<p>Unlike livein_begin, this method does not check that the liveness information is accurate.</p>


<p>Still for debug purposes it may be useful to have iterators that won't assert if the liveness information is not current.</p>


<p>Definition at line 506 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/codegen/machinebasicblock-h">MachineBasicBlock.h</a>.</p>


<p>Referenced by <a href="#a84496a274487670f481ebaaa787149f6">liveins_dbg</a>.</p>

</div>
</div>

### livein\_empty() {#a64e73d869f06f711fb3d5b2c07dfc7be}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool llvm::MachineBasicBlock::livein_empty ()</td>
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



<p>Definition at line 513 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/codegen/machinebasicblock-h">MachineBasicBlock.h</a>.</p>


<p>Referenced by <a href="#a5a4302f4590a281bb84e08b30c80591c">print</a>.</p>

</div>
</div>

### livein\_end() {#a0e76d75564a8460bd9f2822f7ad49b1f}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">livein_iterator llvm::MachineBasicBlock::livein_end ()</td>
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



<p>Definition at line 512 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/codegen/machinebasicblock-h">MachineBasicBlock.h</a>.</p>


<p>Referenced by <a href="#af9745f59d6647bd43f9f7959ca1a9971">isLiveIn</a>, <a href="#a364ed6e68f92f797c0cd9e53ce5ea2a5">liveins</a>, <a href="#a84496a274487670f481ebaaa787149f6">liveins_dbg</a> and <a href="/web-llvm/docs/api/classes/anonymous-hexagoncfgoptimizer-cpp-/hexagoncfgoptimizer/#a44a6c0917383ba77dca7325a7b23c252">anonymous{HexagonCFGOptimizer.cpp}::HexagonCFGOptimizer::runOnMachineFunction</a>.</p>

</div>
</div>

### liveins() {#a364ed6e68f92f797c0cd9e53ce5ea2a5}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">iterator_range&lt; livein_iterator &gt; llvm::MachineBasicBlock::liveins ()</td>
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



<p>Definition at line 514 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/codegen/machinebasicblock-h">MachineBasicBlock.h</a>.</p>


<p>References <a href="#a81335545907243d4dea1a276f01566c0">livein_begin</a>, <a href="#a0e76d75564a8460bd9f2822f7ad49b1f">livein_end</a> and <a href="/web-llvm/docs/api/namespaces/llvm/#a341215803e83773a3e97860dc291f121">llvm::make_range</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/classes/llvm/x86framelowering/#afd992a2165073c9cea53128d5b6c4145">llvm::X86FrameLowering::adjustForHiPEPrologue</a>, <a href="/web-llvm/docs/api/classes/llvm/armframelowering/#a62042f5fd3a2df1b4fab2bfc692b2390">llvm::ARMFrameLowering::adjustForSegmentedStacks</a>, <a href="/web-llvm/docs/api/classes/llvm/x86framelowering/#ac8faf9a625064bfefafb7ace646815ff">llvm::X86FrameLowering::adjustForSegmentedStacks</a>, <a href="/web-llvm/docs/api/namespaces/anonymous-basicblockpathcloning-cpp-/#a09842318dc1064ae48b19d91e2cb11aa">anonymous{BasicBlockPathCloning.cpp}::ApplyCloning</a>, <a href="/web-llvm/docs/api/structs/llvm/rdf/dataflowgraph/#a0b52d2ebf631ded594b7311d1f2829e3">llvm::rdf::DataFlowGraph::build</a>, <a href="#a7ebfe0cc2f78ae5f27e1944412606973">computeRegisterLiveness</a>, <a href="#a5a4302f4590a281bb84e08b30c80591c">print</a>, <a href="#aa80aaa82844ab5560ece045eee7b34ac">SplitCriticalEdge</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/x86/x86speculativeloadhardening-cpp/#a18b17899654dd5adb69b62c89ba95783">splitEdge</a> and <a href="/web-llvm/docs/api/structs/anonymous-armlowoverheadloops-cpp-/lowoverheadloop/#ad8272d1e2af6d68d30fbd619283a68c5">anonymous{ARMLowOverheadLoops.cpp}::LowOverheadLoop::ValidateLiveOuts</a>.</p>

</div>
</div>

### liveins\_dbg() {#a84496a274487670f481ebaaa787149f6}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">iterator_range&lt; livein_iterator &gt; llvm::MachineBasicBlock::liveins_dbg ()</td>
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



<p>Definition at line 507 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/codegen/machinebasicblock-h">MachineBasicBlock.h</a>.</p>


<p>References <a href="#ab01e076c631849cba69494483703600a">livein_begin_dbg</a>, <a href="#a0e76d75564a8460bd9f2822f7ad49b1f">livein_end</a> and <a href="/web-llvm/docs/api/namespaces/llvm/#a341215803e83773a3e97860dc291f121">llvm::make_range</a>.</p>

</div>
</div>

### liveout\_begin() {#aa13f60350a3e19e1791fd628b694da36}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">MachineBasicBlock::liveout_iterator MachineBasicBlock::liveout_begin ()</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Iterator scanning successor basic blocks' liveins to determine the registers potentially live at the end of this block.</p>


<p>There may be duplicates or overlapping registers in the list returned.</p>


<p>Declaration at line 606 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/codegen/machinebasicblock-h">MachineBasicBlock.h</a>, definition at line 1760 of file <a href="/web-llvm/docs/api/files/lib/lib/codegen/machinebasicblock-cpp">MachineBasicBlock.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/silowercontrolflow-cpp/#a4868c5d81c5ccc98c47aeab6244346a0">assert</a>, <a href="/web-llvm/docs/api/classes/llvm/targetloweringbase/#ade4c9edab20f271644c8678ae6764c69">llvm::TargetLoweringBase::getExceptionPointerRegister</a>, <a href="/web-llvm/docs/api/classes/llvm/targetloweringbase/#af00cd85bb1e2d2286212e74352c0a191">llvm::TargetLoweringBase::getExceptionSelectorRegister</a>, <a href="/web-llvm/docs/api/classes/llvm/machinefunction/#a977ddce262de45c645be23d951066351">llvm::MachineFunction::getFunction</a>, <a href="#acf6442108e21e7e5379feb8962de65b7">getParent</a>, <a href="/web-llvm/docs/api/classes/llvm/function/#a6f77e4e800ba4dffd63e8ddb330062aa">llvm::Function::getPersonalityFn</a>, <a href="/web-llvm/docs/api/classes/llvm/machinefunction/#ac1f888bba00f32cb4f9a0010c958f397">llvm::MachineFunction::getProperties</a>, <a href="/web-llvm/docs/api/classes/llvm/machinefunction/#a3825368aca2bc1550d173660df4da6a6">llvm::MachineFunction::getSubtarget</a>, <a href="/web-llvm/docs/api/classes/llvm/targetsubtargetinfo/#ade3f0d8b35d67c43df9425bb730a9a7c">llvm::TargetSubtargetInfo::getTargetLowering</a>, <a href="/web-llvm/docs/api/classes/llvm/function/#a6a0f6312963ee6fb0969243607174949">llvm::Function::hasPersonalityFn</a>, <a href="/web-llvm/docs/api/classes/llvm/machinefunctionproperties/#aacef05f16d3e71703f08bb4677e1d7a2">llvm::MachineFunctionProperties::hasProperty</a>, <a href="#ac423fefe048ace18159808c5592ae74c">MachineFunction</a> and <a href="/web-llvm/docs/api/classes/llvm/machinefunctionproperties/#ad85237c6c667e4713efe8921e9c32ac1a0020348b08bb4cccecf3241eac999d8a">llvm::MachineFunctionProperties::TracksLiveness</a>.</p>


<p>Referenced by <a href="#a114e4a8fc84200c5f3d4d02ecb366dd5">liveouts</a>.</p>

</div>
</div>

### liveout\_end() {#a4fcb7c9dcf957be63eb03d4a7b8b0cd9}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">liveout_iterator llvm::MachineBasicBlock::liveout_end ()</td>
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



<p>Definition at line 607 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/codegen/machinebasicblock-h">MachineBasicBlock.h</a>.</p>


<p>Referenced by <a href="#a114e4a8fc84200c5f3d4d02ecb366dd5">liveouts</a>.</p>

</div>
</div>

### liveouts() {#a114e4a8fc84200c5f3d4d02ecb366dd5}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">iterator_range&lt; liveout_iterator &gt; llvm::MachineBasicBlock::liveouts ()</td>
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



<p>Definition at line 610 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/codegen/machinebasicblock-h">MachineBasicBlock.h</a>.</p>


<p>References <a href="#aa13f60350a3e19e1791fd628b694da36">liveout_begin</a>, <a href="#a4fcb7c9dcf957be63eb03d4a7b8b0cd9">liveout_end</a> and <a href="/web-llvm/docs/api/namespaces/llvm/#a341215803e83773a3e97860dc291f121">llvm::make_range</a>.</p>

</div>
</div>

### mayHaveInlineAsmBr() {#aefb323794dab5bb00d738a3f32dd65e6}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool MachineBasicBlock::mayHaveInlineAsmBr ()</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Returns true if this block may have an INLINEASM_BR (overestimate, by checking if any of the successors are indirect targets of any inlineasm_br in the function).</p>

<p>Declaration at line 710 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/codegen/machinebasicblock-h">MachineBasicBlock.h</a>, definition at line 306 of file <a href="/web-llvm/docs/api/files/lib/lib/codegen/machinebasicblock-cpp">MachineBasicBlock.cpp</a>.</p>


<p>Reference <a href="#ad88ff1529541fb4e243cc8ed90b11131">successors</a>.</p>


<p>Referenced by <a href="#ae37b6ccdd5b2bdd9bc53dc0b634e3f7f">isLegalToHoistInto</a>.</p>

</div>
</div>

### moveAfter() {#af3c2dc75190645b72eee3c416cd14885}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void MachineBasicBlock::moveAfter (<a href="/web-llvm/docs/api/classes/llvm/machinebasicblock">MachineBasicBlock</a> * NewBefore)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Declaration at line 731 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/codegen/machinebasicblock-h">MachineBasicBlock.h</a>, definition at line 680 of file <a href="/web-llvm/docs/api/files/lib/lib/codegen/machinebasicblock-cpp">MachineBasicBlock.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/classes/llvm/ilist-node-impl/#af719fc783be6589465137d997701a432">llvm::ilist_node_impl&lt; OptionsT &gt;::getIterator</a>, <a href="/web-llvm/docs/api/classes/llvm/ilist-node-impl/#af719fc783be6589465137d997701a432">llvm::ilist_node_impl&lt; ilist_detail::compute_node_options&lt; MachineBasicBlock, Options... &gt;::type &gt;::getIterator</a>, <a href="#acf6442108e21e7e5379feb8962de65b7">getParent</a> and <a href="/web-llvm/docs/api/classes/llvm/machinefunction/#adf74e9faccaee21b521a0973568d4738">llvm::MachineFunction::splice</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/classes/llvm/armtargetlowering/#a6820d09b4db5654cd1377d3ab63b3e01">llvm::ARMTargetLowering::EmitInstrWithCustomInserter</a> and <a href="/web-llvm/docs/api/classes/anonymous-hexagoncfgoptimizer-cpp-/hexagoncfgoptimizer/#a44a6c0917383ba77dca7325a7b23c252">anonymous{HexagonCFGOptimizer.cpp}::HexagonCFGOptimizer::runOnMachineFunction</a>.</p>

</div>
</div>

### moveBefore() {#a25c2a6ee39d0d97dac2184e8bd942300}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void MachineBasicBlock::moveBefore (<a href="/web-llvm/docs/api/classes/llvm/machinebasicblock">MachineBasicBlock</a> * NewAfter)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Move 'this' block before or after the specified block.</p>


<p>This only moves the block, it does not modify the CFG or adjust potential fall-throughs at the end of the block.</p>


<p>Declaration at line 730 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/codegen/machinebasicblock-h">MachineBasicBlock.h</a>, definition at line 676 of file <a href="/web-llvm/docs/api/files/lib/lib/codegen/machinebasicblock-cpp">MachineBasicBlock.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/classes/llvm/ilist-node-impl/#af719fc783be6589465137d997701a432">llvm::ilist_node_impl&lt; OptionsT &gt;::getIterator</a>, <a href="/web-llvm/docs/api/classes/llvm/ilist-node-impl/#af719fc783be6589465137d997701a432">llvm::ilist_node_impl&lt; ilist_detail::compute_node_options&lt; MachineBasicBlock, Options... &gt;::type &gt;::getIterator</a>, <a href="#acf6442108e21e7e5379feb8962de65b7">getParent</a> and <a href="/web-llvm/docs/api/classes/llvm/machinefunction/#adf74e9faccaee21b521a0973568d4738">llvm::MachineFunction::splice</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/classes/llvm/armblockplacement/#aa13bb5e066b0419461ad1bbdd7bc9a1d">llvm::ARMBlockPlacement::moveBasicBlock</a>.</p>

</div>
</div>

### normalizeSuccProbs() {#a0c54da24de983d197068425e718fb607}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void llvm::MachineBasicBlock::normalizeSuccProbs ()</td>
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

<p>Normalize probabilities of all successors so that the sum of them becomes one.</p>


<p>This is usually done when the current update on this MBB is done, and the sum of its successors' probabilities is not guaranteed to be one. The user is responsible for the correct use of this function. MBB::removeSuccessor() has an option to do this automatically.</p>


<p>Definition at line 773 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/codegen/machinebasicblock-h">MachineBasicBlock.h</a>.</p>


<p>Reference <a href="/web-llvm/docs/api/classes/llvm/branchprobability/#afff2bab6bb7f206bbacad5dd589a6186">llvm::BranchProbability::normalizeProbabilities</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/classes/llvm/switchcg/switchlowering/#ae706b72bcadad3acf12a239b257aabc6">llvm::SwitchCG::SwitchLowering::buildJumpTable</a>, <a href="/web-llvm/docs/api/classes/anonymous-ppcbranchcoalescing-cpp-/ppcbranchcoalescing/#a072a336f973a3de4daa8fe16e5b4570f">anonymous{PPCBranchCoalescing.cpp}::PPCBranchCoalescing::mergeCandidates</a>, <a href="/web-llvm/docs/api/classes/anonymous-miparser-cpp-/miparser/#a3904021432d1d4cf1620b9c09506e612">anonymous{MIParser.cpp}::MIParser::parseBasicBlocks</a>, <a href="#a29a36aca5cf01600bc3f403aaa2f2467">removeSuccessor</a>, <a href="#a4b43b969b3db9fc943b664738f62ca76">splitSuccessor</a>, <a href="#a046a35e36c4c1206711ea82ee9cb6d72">transferSuccessorsAndUpdatePHIs</a>, <a href="/web-llvm/docs/api/classes/llvm/selectiondagbuilder/#a7a7b439d546506d56e2cdc61a1ac1d06">llvm::SelectionDAGBuilder::visitBitTestCase</a>, <a href="/web-llvm/docs/api/classes/llvm/selectiondagbuilder/#a31f9f0db1bb0b321286db70b58fb001e">llvm::SelectionDAGBuilder::visitBitTestHeader</a> and <a href="/web-llvm/docs/api/classes/llvm/selectiondagbuilder/#afe7d9f31d3030277242731ccf43478c0">llvm::SelectionDAGBuilder::visitSwitchCase</a>.</p>

</div>
</div>

### phis() {#a36b529ef331e4099007e14b48c75316a}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">iterator_range&lt; iterator &gt; llvm::MachineBasicBlock::phis ()</td>
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

<p>Returns a range that iterates over the phis in the basic block.</p>

<p>Definition at line 392 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/codegen/machinebasicblock-h">MachineBasicBlock.h</a>.</p>


<p>References <a href="#ab2d91e7bec944efcbc39d8e30644f111">begin</a>, <a href="#aa7dc7faaab4856b8f0014b8283e26c7b">getFirstNonPHI</a> and <a href="/web-llvm/docs/api/namespaces/llvm/#a341215803e83773a3e97860dc291f121">llvm::make_range</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/classes/llvm/moduloscheduleexpandermve/#a8b570f6c1b94d49245ad3cee2887acf3">llvm::ModuloScheduleExpanderMVE::canApply</a>, <a href="/web-llvm/docs/api/classes/llvm/peelingmoduloscheduleexpander/#ade77f3d7ddbf542604f38d867287876f">llvm::PeelingModuloScheduleExpander::fixupBranches</a>, <a href="/web-llvm/docs/api/classes/llvm/peelingmoduloscheduleexpander/#afe809699537758032938bea41ea44bb7">llvm::PeelingModuloScheduleExpander::moveStageBetweenBlocks</a>, <a href="#aa0cd1cb6694e9efa62191e936842b5c4">phis</a> and <a href="#a134a21189d056b81b80d0cdf01ef8c46">replacePhiUsesWith</a>.</p>

</div>
</div>

### phis() {#aa0cd1cb6694e9efa62191e936842b5c4}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">iterator_range&lt; const_iterator &gt; llvm::MachineBasicBlock::phis ()</td>
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



<p>Definition at line 395 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/codegen/machinebasicblock-h">MachineBasicBlock.h</a>.</p>


<p>Reference <a href="#a36b529ef331e4099007e14b48c75316a">phis</a>.</p>

</div>
</div>

### pop\_back() {#a1056a82d0f5c741ea09c49be8673156a}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void llvm::MachineBasicBlock::pop_back ()</td>
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



<p>Definition at line 1010 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/codegen/machinebasicblock-h">MachineBasicBlock.h</a>.</p>

</div>
</div>

### pop\_front() {#af9247e8f4d910743041faf53a5255ea6}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void llvm::MachineBasicBlock::pop_front ()</td>
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



<p>Definition at line 1009 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/codegen/machinebasicblock-h">MachineBasicBlock.h</a>.</p>

</div>
</div>

### pred\_begin() {#ab644fcf07a4c2708333cf66276282357}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">pred_iterator llvm::MachineBasicBlock::pred_begin ()</td>
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



<p>Definition at line 414 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/codegen/machinebasicblock-h">MachineBasicBlock.h</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/classes/llvm/armbaseinstrinfo/#a637fe9208c860066ecf02233cd258f9b">llvm::ARMBaseInstrInfo::analyzeLoopForPipelining</a>, <a href="/web-llvm/docs/api/classes/llvm/ppcinstrinfo/#adc8a417082dae00c6f459b63a65e0ed8">llvm::PPCInstrInfo::analyzeLoopForPipelining</a>, <a href="/web-llvm/docs/api/classes/llvm/spirvtargetlowering/#ab0b7a641c5208a3cd348ac5ea98e59b6">llvm::SPIRVTargetLowering::finalizeLowering</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/arm/armblockplacement-cpp/#ac80c82ab5623016f11bc128c6a943af6">findWLS</a>, <a href="/web-llvm/docs/api/files/lib/lib/codegen/shrinkwrap-cpp/#a7d76643dfe192e91b138cb1e156b92cf">isSaveReachableThroughClean</a>, <a href="/web-llvm/docs/api/classes/llvm/peelingmoduloscheduleexpander/#afe809699537758032938bea41ea44bb7">llvm::PeelingModuloScheduleExpander::moveStageBetweenBlocks</a>, <a href="/web-llvm/docs/api/classes/llvm/peelingmoduloscheduleexpander/#adc90ef1bf034dfb4446b910d3795d218">llvm::PeelingModuloScheduleExpander::peelPrologAndEpilogs</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#ac3e549d97549636a7f08779d5cd98540">llvm::pred_begin</a>, <a href="#addd80df79ba902914c7d8a52e3896b79">predecessors</a>, <a href="#a6faf2a0270e85a9cb7a3b871cfb3d9df">predecessors</a>, <a href="/web-llvm/docs/api/structs/anonymous-ppcearlyreturn-cpp-/ppcearlyreturn/#ae036500138a9ae1567af6b28547cf045">anonymous{PPCEarlyReturn.cpp}::PPCEarlyReturn::processBlock</a>, <a href="/web-llvm/docs/api/classes/llvm/livevariables/#a9e0695dc8fb597f66ca702309da941f7">llvm::LiveVariables::recomputeForSingleDefVirtReg</a> and <a href="/web-llvm/docs/api/classes/anonymous-x86flagscopylowering-cpp-/x86flagscopyloweringpass/#a30d90e84a3faa0cd7aa2c3b96d65c232">anonymous{X86FlagsCopyLowering.cpp}::X86FlagsCopyLoweringPass::runOnMachineFunction</a>.</p>

</div>
</div>

### pred\_begin() {#ab2e39223357fe836c7c11bbe8bc3c6af}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">const_pred_iterator llvm::MachineBasicBlock::pred_begin ()</td>
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



<p>Definition at line 415 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/codegen/machinebasicblock-h">MachineBasicBlock.h</a>.</p>

</div>
</div>

### pred\_empty() {#a877507fda31c207ec36a018784369708}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool llvm::MachineBasicBlock::pred_empty ()</td>
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



<p>Definition at line 429 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/codegen/machinebasicblock-h">MachineBasicBlock.h</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/structs/llvm/rdf/dataflowgraph/#a0b52d2ebf631ded594b7311d1f2829e3">llvm::rdf::DataFlowGraph::build</a>, <a href="/web-llvm/docs/api/classes/llvm/spirvtargetlowering/#ab0b7a641c5208a3cd348ac5ea98e59b6">llvm::SPIRVTargetLowering::finalizeLowering</a>, <a href="/web-llvm/docs/api/classes/llvm/machinessaupdater/#a670da7741129c7d591dc19951ecce6c3">llvm::MachineSSAUpdater::GetValueInMiddleOfBlock</a>, <a href="/web-llvm/docs/api/classes/llvm/tailduplicator/#a22b5f49c33bc7b11d150556b0ee1ca0a">llvm::TailDuplicator::isSimpleBB</a>, <a href="#a5a4302f4590a281bb84e08b30c80591c">print</a>, <a href="/web-llvm/docs/api/structs/anonymous-ppcearlyreturn-cpp-/ppcearlyreturn/#ae036500138a9ae1567af6b28547cf045">anonymous{PPCEarlyReturn.cpp}::PPCEarlyReturn::processBlock</a> and <a href="/web-llvm/docs/api/classes/anonymous-x86flagscopylowering-cpp-/x86flagscopyloweringpass/#a30d90e84a3faa0cd7aa2c3b96d65c232">anonymous{X86FlagsCopyLowering.cpp}::X86FlagsCopyLoweringPass::runOnMachineFunction</a>.</p>

</div>
</div>

### pred\_end() {#a0359a738e0412c5a7ea55d61175e0661}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">pred_iterator llvm::MachineBasicBlock::pred_end ()</td>
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



<p>Definition at line 416 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/codegen/machinebasicblock-h">MachineBasicBlock.h</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/files/lib/lib/codegen/shrinkwrap-cpp/#a7d76643dfe192e91b138cb1e156b92cf">isSaveReachableThroughClean</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a2103c335fa6ab933312c3871c82b0106">llvm::pred_end</a>, <a href="#addd80df79ba902914c7d8a52e3896b79">predecessors</a>, <a href="#a6faf2a0270e85a9cb7a3b871cfb3d9df">predecessors</a>, <a href="/web-llvm/docs/api/classes/llvm/livevariables/#a9e0695dc8fb597f66ca702309da941f7">llvm::LiveVariables::recomputeForSingleDefVirtReg</a> and <a href="/web-llvm/docs/api/classes/anonymous-x86flagscopylowering-cpp-/x86flagscopyloweringpass/#a30d90e84a3faa0cd7aa2c3b96d65c232">anonymous{X86FlagsCopyLowering.cpp}::X86FlagsCopyLoweringPass::runOnMachineFunction</a>.</p>

</div>
</div>

### pred\_end() {#a22d721563c09048a50761b9065b046c7}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">const_pred_iterator llvm::MachineBasicBlock::pred_end ()</td>
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



<p>Definition at line 417 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/codegen/machinebasicblock-h">MachineBasicBlock.h</a>.</p>

</div>
</div>

### pred\_rbegin() {#a3c1a265be404da0734c41c2f4b7373b3}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">pred_reverse_iterator llvm::MachineBasicBlock::pred_rbegin ()</td>
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



<p>Definition at line 418 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/codegen/machinebasicblock-h">MachineBasicBlock.h</a>.</p>

</div>
</div>

### pred\_rbegin() {#a9b00167ef2323cf65dbd5a1fde0c882a}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">const_pred_reverse_iterator llvm::MachineBasicBlock::pred_rbegin ()</td>
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



<p>Definition at line 420 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/codegen/machinebasicblock-h">MachineBasicBlock.h</a>.</p>

</div>
</div>

### pred\_rend() {#a5429a41753b45803fce6e1bc33be84c4}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">pred_reverse_iterator llvm::MachineBasicBlock::pred_rend ()</td>
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



<p>Definition at line 422 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/codegen/machinebasicblock-h">MachineBasicBlock.h</a>.</p>

</div>
</div>

### pred\_rend() {#a30f830271b49728f71960a2a76377939}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">const_pred_reverse_iterator llvm::MachineBasicBlock::pred_rend ()</td>
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



<p>Definition at line 424 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/codegen/machinebasicblock-h">MachineBasicBlock.h</a>.</p>

</div>
</div>

### pred\_size() {#a03936a9b37da541420049422204ab206}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">unsigned llvm::MachineBasicBlock::pred_size ()</td>
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



<p>Definition at line 426 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/codegen/machinebasicblock-h">MachineBasicBlock.h</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/classes/anonymous-aarch64conditionalcompares-cpp-/ssaccmpconv/#a545b0c16154dffb0ddba86968d798e2f">anonymous{AArch64ConditionalCompares.cpp}::SSACCmpConv::canConvert</a>, <a href="/web-llvm/docs/api/classes/anonymous-earlyifconversion-cpp-/ssaifconv/#ad73f79350d54fe535469c4a148943e3a">anonymous{EarlyIfConversion.cpp}::SSAIfConv::canConvertIf</a>, <a href="/web-llvm/docs/api/classes/anonymous-r600machinecfgstructurizer-cpp-/r600machinecfgstructurizer/#ab90cb03c7501b031fa63735cc9391a5f">anonymous{R600MachineCFGStructurizer.cpp}::R600MachineCFGStructurizer::cloneOnSideEntryTo</a>, <a href="/web-llvm/docs/api/classes/llvm/machineloopinfo/#a80b0e6e28849491c5b267be8ffc909b4">llvm::MachineLoopInfo::findLoopPreheader</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/arm/armblockplacement-cpp/#ac80c82ab5623016f11bc128c6a943af6">findWLS</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64instrinfo-cpp/#a339e0ad5e938860dcbd0c510ce212c4b">getIndVarInfo</a>, <a href="/web-llvm/docs/api/classes/llvm/liveintervals/#a1b6e5f6033c80dff3f9b4c6fb40499c2">llvm::LiveIntervals::hasPHIKill</a>, <a href="/web-llvm/docs/api/classes/anonymous-r600machinecfgstructurizer-cpp-/r600machinecfgstructurizer/#a55b3f01e91f974764d18a95d9e4b7ec5">anonymous{R600MachineCFGStructurizer.cpp}::R600MachineCFGStructurizer::ifPatternMatch</a>, <a href="/web-llvm/docs/api/classes/anonymous-r600machinecfgstructurizer-cpp-/r600machinecfgstructurizer/#ae27fd47ee099b4aba7fe2bc84be97ff8">anonymous{R600MachineCFGStructurizer.cpp}::R600MachineCFGStructurizer::improveSimpleJumpintoIf</a>, <a href="/web-llvm/docs/api/classes/llvm/armbaseinstrinfo/#a5b272a39b33a4e8ab2ac4acb2e64d583">llvm::ARMBaseInstrInfo::isProfitableToIfCvt</a>, <a href="/web-llvm/docs/api/files/lib/lib/codegen/shrinkwrap-cpp/#a7d76643dfe192e91b138cb1e156b92cf">isSaveReachableThroughClean</a>, <a href="/web-llvm/docs/api/namespaces/llvm/rdf/#aefd178f993c25ba2221f325e426e973d">llvm::rdf::operator&lt;&lt;</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a3f211484edf604716a6c80030b0a0375">llvm::pred_size</a>, <a href="/web-llvm/docs/api/structs/anonymous-ppcearlyreturn-cpp-/ppcearlyreturn/#ae036500138a9ae1567af6b28547cf045">anonymous{PPCEarlyReturn.cpp}::PPCEarlyReturn::processBlock</a>, <a href="/web-llvm/docs/api/classes/anonymous-hexagoncfgoptimizer-cpp-/hexagoncfgoptimizer/#a44a6c0917383ba77dca7325a7b23c252">anonymous{HexagonCFGOptimizer.cpp}::HexagonCFGOptimizer::runOnMachineFunction</a>, <a href="/web-llvm/docs/api/classes/llvm/irtranslator/#a2fa3a523a1812aeda17891575f852ce9">llvm::IRTranslator::runOnMachineFunction</a>, <a href="/web-llvm/docs/api/files/lib/lib/codegen/branchfolding-cpp/#a3fb0794be53f8c8e93e76861075a9a8a">salvageDebugInfoFromEmptyBlock</a>, <a href="/web-llvm/docs/api/classes/anonymous-r600machinecfgstructurizer-cpp-/r600machinecfgstructurizer/#a2252dc7a91adc7d24397a4dddc25d3a6">anonymous{R600MachineCFGStructurizer.cpp}::R600MachineCFGStructurizer::serialPatternMatch</a>, <a href="/web-llvm/docs/api/classes/llvm/tailduplicator/#aa7dba30d4d9162f00367404e06085391">llvm::TailDuplicator::shouldTailDuplicate</a>, <a href="/web-llvm/docs/api/classes/anonymous-r600machinecfgstructurizer-cpp-/r600machinecfgstructurizer/#ac471c55917cb9e3fdc7674e300260d9f">anonymous{R600MachineCFGStructurizer.cpp}::R600MachineCFGStructurizer::showImproveSimpleJumpintoIf</a> and <a href="/web-llvm/docs/api/classes/anonymous-r600machinecfgstructurizer-cpp-/r600machinecfgstructurizer/#ac393ff87a496a67dae4ba9430b816263">anonymous{R600MachineCFGStructurizer.cpp}::R600MachineCFGStructurizer::singlePathTo</a>.</p>

</div>
</div>

### predecessors() {#addd80df79ba902914c7d8a52e3896b79}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">iterator_range&lt; pred_iterator &gt; llvm::MachineBasicBlock::predecessors ()</td>
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



<p>Definition at line 447 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/codegen/machinebasicblock-h">MachineBasicBlock.h</a>.</p>


<p>References <a href="/web-llvm/docs/api/namespaces/llvm/#a341215803e83773a3e97860dc291f121">llvm::make_range</a>, <a href="#ab644fcf07a4c2708333cf66276282357">pred_begin</a> and <a href="#a0359a738e0412c5a7ea55d61175e0661">pred_end</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/classes/llvm/armframelowering/#a62042f5fd3a2df1b4fab2bfc692b2390">llvm::ARMFrameLowering::adjustForSegmentedStacks</a>, <a href="/web-llvm/docs/api/classes/llvm/hexagoninstrinfo/#a71bb0396fb78bb7298d96df79bbf2200">llvm::HexagonInstrInfo::findLoopInstr</a>, <a href="/web-llvm/docs/api/classes/llvm/machineloopinfo/#a80b0e6e28849491c5b267be8ffc909b4">llvm::MachineLoopInfo::findLoopPreheader</a>, <a href="/web-llvm/docs/api/classes/llvm/ssaupdatertraits-4e613f36227a2a352217431a8f1958cd/#a46f0b89ac3af7c7b99a001b5c8eadff4">llvm::SSAUpdaterTraits&lt; MachineSSAUpdater &gt;::FindPredecessorBlocks</a>, <a href="/web-llvm/docs/api/structs/llvm/afdo-detail/irtraits-6a00974026f1163ef87516ae73fba13d/#a1976c9bfaa3528e1a0697be60c1165ac">llvm::afdo_detail::IRTraits&lt; MachineBasicBlock &gt;::getPredecessors</a>, <a href="/web-llvm/docs/api/classes/llvm/reachingdefanalysis/#adf38674f9ee35a7d177066a78027aa56">llvm::ReachingDefAnalysis::getUniqueReachingMIDef</a>, <a href="/web-llvm/docs/api/classes/llvm/machinessaupdater/#a670da7741129c7d591dc19951ecce6c3">llvm::MachineSSAUpdater::GetValueInMiddleOfBlock</a>, <a href="/web-llvm/docs/api/classes/llvm/liveintervals/#a1b6e5f6033c80dff3f9b4c6fb40499c2">llvm::LiveIntervals::hasPHIKill</a>, <a href="/web-llvm/docs/api/classes/anonymous-r600machinecfgstructurizer-cpp-/r600machinecfgstructurizer/#ae27fd47ee099b4aba7fe2bc84be97ff8">anonymous{R600MachineCFGStructurizer.cpp}::R600MachineCFGStructurizer::improveSimpleJumpintoIf</a>, <a href="#aaa71c733e5aa6113e60a3a806e01bb10">isPredecessor</a>, <a href="/web-llvm/docs/api/namespaces/llvm/rdf/#aefd178f993c25ba2221f325e426e973d">llvm::rdf::operator&lt;&lt;</a>, <a href="/web-llvm/docs/api/classes/anonymous-sioptimizevgprliverange-cpp-/sioptimizevgprliverange/#aa35ddcfd60c7c4587ea25cb27e25968e">anonymous{SIOptimizeVGPRLiveRange.cpp}::SIOptimizeVGPRLiveRange::optimizeWaterfallLiveRange</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#acb22fb04083152eee862457e42e8dc31">llvm::predecessors</a>, <a href="#a5a4302f4590a281bb84e08b30c80591c">print</a>, <a href="/web-llvm/docs/api/structs/anonymous-ppcearlyreturn-cpp-/ppcearlyreturn/#ae036500138a9ae1567af6b28547cf045">anonymous{PPCEarlyReturn.cpp}::PPCEarlyReturn::processBlock</a> and <a href="/web-llvm/docs/api/structs/anonymous-machineverifier-cpp-/machineverifier/#abc440c9fad640641c26ddae8c08dce82">anonymous{MachineVerifier.cpp}::MachineVerifier::verifyLiveRangeSegment</a>.</p>

</div>
</div>

### predecessors() {#a6faf2a0270e85a9cb7a3b871cfb3d9df}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">iterator_range&lt; const_pred_iterator &gt; llvm::MachineBasicBlock::predecessors ()</td>
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



<p>Definition at line 450 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/codegen/machinebasicblock-h">MachineBasicBlock.h</a>.</p>


<p>References <a href="/web-llvm/docs/api/namespaces/llvm/#a341215803e83773a3e97860dc291f121">llvm::make_range</a>, <a href="#ab644fcf07a4c2708333cf66276282357">pred_begin</a> and <a href="#a0359a738e0412c5a7ea55d61175e0661">pred_end</a>.</p>

</div>
</div>

### print() {#ab3b62258d9bd41595674de878f37f8d8}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void MachineBasicBlock::print (<a href="/web-llvm/docs/api/classes/llvm/raw-ostream">raw_ostream</a> &amp; OS, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/slotindexes">SlotIndexes</a> * Indexes=nullptr, bool IsStandalone=<a href="/web-llvm/docs/api/files/lib/lib/analysis/basicaliasanalysis-cpp/#af6d5cafbdfc5313e65d990120021a3ec">true</a>)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Declaration at line 1208 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/codegen/machinebasicblock-h">MachineBasicBlock.h</a>, definition at line 345 of file <a href="/web-llvm/docs/api/files/lib/lib/codegen/machinebasicblock-cpp">MachineBasicBlock.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/files/lib/lib/support/md5-cpp/#a96d73bbd7af15cb1fc38c3f4a3bd82e9">F</a>, <a href="/web-llvm/docs/api/classes/llvm/machinefunction/#a977ddce262de45c645be23d951066351">llvm::MachineFunction::getFunction</a>, <a href="#acf6442108e21e7e5379feb8962de65b7">getParent</a>, <a href="/web-llvm/docs/api/classes/llvm/moduleslottracker/#ace93d877ff9298d25a15e2a32f765653">llvm::ModuleSlotTracker::incorporateFunction</a>, <a href="#ac423fefe048ace18159808c5592ae74c">MachineFunction</a> and <a href="#ab3b62258d9bd41595674de878f37f8d8">print</a>.</p>


<p>Referenced by <a href="#a8cec41e65c7ebf7da3e9d41f2317065e">dump</a>, <a href="#ab3b62258d9bd41595674de878f37f8d8">print</a>, <a href="/web-llvm/docs/api/classes/anonymous-r600machinecfgstructurizer-cpp-/r600machinecfgstructurizer/#ac471c55917cb9e3fdc7674e300260d9f">anonymous{R600MachineCFGStructurizer.cpp}::R600MachineCFGStructurizer::showImproveSimpleJumpintoIf</a> and <a href="/web-llvm/docs/api/classes/llvm/peelingmoduloscheduleexpander/#ae67a99405a40814d2261e31f11fe7a38">llvm::PeelingModuloScheduleExpander::validateAgainstModuloScheduleExpander</a>.</p>

</div>
</div>

### print() {#a5a4302f4590a281bb84e08b30c80591c}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void MachineBasicBlock::print (<a href="/web-llvm/docs/api/classes/llvm/raw-ostream">raw_ostream</a> &amp; OS, <a href="/web-llvm/docs/api/classes/llvm/moduleslottracker">ModuleSlotTracker</a> &amp; MST, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/slotindexes">SlotIndexes</a> * Indexes=nullptr, bool IsStandalone=<a href="/web-llvm/docs/api/files/lib/lib/analysis/basicaliasanalysis-cpp/#af6d5cafbdfc5313e65d990120021a3ec">true</a>)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Declaration at line 1210 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/codegen/machinebasicblock-h">MachineBasicBlock.h</a>, definition at line 360 of file <a href="/web-llvm/docs/api/files/lib/lib/codegen/machinebasicblock-cpp">MachineBasicBlock.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/classes/llvm/machineinstr/#aafacf84de1cb994a92dc045f4aa1d518ad00e31da3877ce738df8343edcff6ed8">llvm::MachineInstr::BundledSucc</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a939bc2108d47080767f0c06ba56caec7">llvm::format</a>, <a href="/web-llvm/docs/api/classes/llvm/branchprobability/#a19c752227e02f7cb26fb47fdb36dc349">llvm::BranchProbability::getDenominator</a>, <a href="/web-llvm/docs/api/classes/llvm/targetsubtargetinfo/#acd858ed72f11db9444617740c3622608">llvm::TargetSubtargetInfo::getInstrInfo</a>, <a href="/web-llvm/docs/api/classes/llvm/slotindexes/#aa429e211fd041cb42d26e49dd5d95d75">llvm::SlotIndexes::getInstructionIndex</a>, <a href="/web-llvm/docs/api/classes/llvm/slotindexes/#aaf0c07cc1cdb9c78c6dfdfdd5913420a">llvm::SlotIndexes::getMBBStartIdx</a>, <a href="/web-llvm/docs/api/classes/llvm/branchprobability/#a7be5759bf75c903d1695fa97eca6f139">llvm::BranchProbability::getNumerator</a>, <a href="#acf6442108e21e7e5379feb8962de65b7">getParent</a>, <a href="/web-llvm/docs/api/classes/llvm/machinefunction/#a810234b6b3d223b7c74a4253fcc5ea5e">llvm::MachineFunction::getRegInfo</a>, <a href="/web-llvm/docs/api/classes/llvm/targetsubtargetinfo/#a43c530c830206ecf5ad3359364634c75">llvm::TargetSubtargetInfo::getRegisterInfo</a>, <a href="/web-llvm/docs/api/classes/llvm/machinefunction/#a3825368aca2bc1550d173660df4da6a6">llvm::MachineFunction::getSubtarget</a>, <a href="#a34b15764a81fb89e68d85d5aae76f20f">getSuccProbability</a>, <a href="/web-llvm/docs/api/classes/llvm/slotindexes/#ad05ea5ba061f9397ac8d15d02d77c812">llvm::SlotIndexes::hasIndex</a>, <a href="/web-llvm/docs/api/files/lib/lib/support/md5-cpp/#ac0eafdc9ee161b71e7af98af736952fd">I</a>, <a href="/web-llvm/docs/api/classes/llvm/raw-ostream/#a8fdf5cdf041c8aded7e3308c1c3efacc">llvm::raw_ostream::indent</a>, <a href="#a40bf8f9579717d3f9be7640f1c6d678b">instrs</a>, <a href="#a64e73d869f06f711fb3d5b2c07dfc7be">livein_empty</a>, <a href="#a364ed6e68f92f797c0cd9e53ce5ea2a5">liveins</a>, <a href="#ac423fefe048ace18159808c5592ae74c">MachineFunction</a>, <a href="/web-llvm/docs/api/files/lib/lib/codegen/lib/codegen/globalisel/irtranslator-cpp/#abe44dfdea65b4f7e11e0a608ab708b76">MI</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64advsimdscalarpass-cpp/#aacd2ab195054a3e6a74bfbb9d5d571c8">MRI</a>, <a href="#a877507fda31c207ec36a018784369708">pred_empty</a>, <a href="#addd80df79ba902914c7d8a52e3896b79">predecessors</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a3e30e18d6f7ebd943eaf8ebc3a2b2930">llvm::PrintLaneMask</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#af7881286e3ea4d7f1c4a63c87c132dac">llvm::printMBBReference</a>, <a href="#adad68dd11c1995cc4f63e51986f50ce0">printName</a>, <a href="#a55df99d8362d83a10b9fb35fd5b8cf7caf29bf9642eaca6e0619977346c03efd8">PrintNameAttributes</a>, <a href="#a55df99d8362d83a10b9fb35fd5b8cf7cac13a649d6c2087dca8873a8edd4d3c8d">PrintNameIr</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#af085ea923a328b9fa6a1975f1a4ff987">llvm::printReg</a>, <a href="/web-llvm/docs/api/files/lib/lib/codegen/machinebasicblock-cpp/#afdb0f5c05148e990fe054340f9701683">PrintSlotIndexes</a>, <a href="#a6321b189ea8fd5058663f8a87d6c23e9">succ_begin</a>, <a href="#aa8d1d8d88835b75b05b14ab774785e8a">succ_empty</a>, <a href="#a3ddd708642d60c1661992ff8ba1b215d">succ_end</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/hexagon/hexagoncopytocombine-cpp/#a1d40004718218dbdf06b496766299101">TII</a> and <a href="/web-llvm/docs/api/files/lib/lib/codegen/machinesink-cpp/#a0f36ed1bc17fc1aa97fe291c439a0698">TRI</a>.</p>

</div>
</div>

### printAsOperand() {#a691794b4391537d134a8b2afbd21f8cb}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void MachineBasicBlock::printAsOperand (<a href="/web-llvm/docs/api/classes/llvm/raw-ostream">raw_ostream</a> &amp; OS, bool PrintType=<a href="/web-llvm/docs/api/files/lib/lib/analysis/basicaliasanalysis-cpp/#af6d5cafbdfc5313e65d990120021a3ec">true</a>)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Declaration at line 1222 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/codegen/machinebasicblock-h">MachineBasicBlock.h</a>, definition at line 594 of file <a href="/web-llvm/docs/api/files/lib/lib/codegen/machinebasicblock-cpp">MachineBasicBlock.cpp</a>.</p>


<p>Reference <a href="#adad68dd11c1995cc4f63e51986f50ce0">printName</a>.</p>

</div>
</div>

### printName() {#adad68dd11c1995cc4f63e51986f50ce0}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void MachineBasicBlock::printName (<a href="/web-llvm/docs/api/classes/llvm/raw-ostream">raw_ostream</a> &amp; os, unsigned printNameFlags=<a href="#a55df99d8362d83a10b9fb35fd5b8cf7cac13a649d6c2087dca8873a8edd4d3c8d">PrintNameIr</a>, <a href="/web-llvm/docs/api/classes/llvm/moduleslottracker">ModuleSlotTracker</a> * moduleSlotTracker=nullptr)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Print the basic block's name as:</p>


<p>bb.{number}[.{ir-name}] [(attributes...)]</p>


<p>The {ir-name} is only printed when the <a href="#a55df99d8362d83a10b9fb35fd5b8cf7cac13a649d6c2087dca8873a8edd4d3c8d">PrintNameIr</a> flag is passed (which is the default). If the IR block has no name, it is identified numerically using the attribute syntax as "(%ir-block.{ir-slot})".</p>


<p>When the <a href="#a55df99d8362d83a10b9fb35fd5b8cf7caf29bf9642eaca6e0619977346c03efd8">PrintNameAttributes</a> flag is passed, additional attributes of the block are printed when set.</p>


<dl class="doxyParamsList">
<dt class="doxyParamsTableTitle">Parameters</dt>
<dd>
<table class="doxyParamsTable">
<tr class="doxyParamItem">
<td class="doxyParamItemName">printNameFlags</td>
<td class="doxyParamItemDescription"><p>Combination of <a href="#a55df99d8362d83a10b9fb35fd5b8cf7c">PrintNameFlag</a> flags indicating the parts to print.</p></td>
</tr>
<tr class="doxyParamItem">
<td class="doxyParamItemName">moduleSlotTracker</td>
<td class="doxyParamItemDescription"><p>Optional <a href="/web-llvm/docs/api/classes/llvm/moduleslottracker">ModuleSlotTracker</a>. This method will incorporate its own tracker when necessary to determine the block's IR name.</p></td>
</tr>
</table>
</dd>
</dl>

<p>Declaration at line 1218 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/codegen/machinebasicblock-h">MachineBasicBlock.h</a>, definition at line 490 of file <a href="/web-llvm/docs/api/files/lib/lib/codegen/machinebasicblock-cpp">MachineBasicBlock.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/structs/llvm/mbbsectionid/#ab1720aee7515c00604560487e182f97ba27d391fde824c4f095edec26d0281786">llvm::MBBSectionID::Cold</a>, <a href="/web-llvm/docs/api/structs/llvm/mbbsectionid/#ab1720aee7515c00604560487e182f97ba71abf8d2560307db8a89078860fd599a">llvm::MBBSectionID::Exception</a>, <a href="#a9e26767dd60f2ffd50a7a6c5ea3a0c32">getAddressTakenIRBlock</a>, <a href="#ae13575403de0e7d005f1b5905053f3ea">getAlignment</a>, <a href="#a4874816314c3308be0bf1e71de2078d8">getBasicBlock</a>, <a href="#a45a5042aa51fc28cccaba7a95ec9746c">getBBID</a>, <a href="/web-llvm/docs/api/classes/llvm/moduleslottracker/#a6d82623735b3bd2208170d379913f2e1">llvm::ModuleSlotTracker::getLocalSlot</a>, <a href="#a3aa22d521bd6a7e6b9f35545dc7b0f1e">getNumber</a>, <a href="#a87ee39ccabd6fa5abe6302ebffd768c9">getSectionID</a>, <a href="/web-llvm/docs/api/classes/llvm/moduleslottracker/#ace93d877ff9298d25a15e2a32f765653">llvm::ModuleSlotTracker::incorporateFunction</a>, <a href="#a7d2f8efd82042b4cf611ba10e9e79ed0">isEHFuncletEntry</a>, <a href="#a1100bfbadd996d464150c6a68fa8dc1d">isEHPad</a>, <a href="#a00e55a6b6b44b739e9da1d62f1d8a5b3">isInlineAsmBrIndirectTarget</a>, <a href="#a753336faa16076c3931ae29c55f88f68">isIRBlockAddressTaken</a>, <a href="#ad934138cd088f6c08cbf0f373997fd17">isMachineBlockAddressTaken</a>, <a href="/web-llvm/docs/api/structs/llvm/mbbsectionid/#a2948b9ecb725f98db2afa43ce1d78b94">llvm::MBBSectionID::Number</a>, <a href="#a55df99d8362d83a10b9fb35fd5b8cf7caf29bf9642eaca6e0619977346c03efd8">PrintNameAttributes</a>, <a href="#a55df99d8362d83a10b9fb35fd5b8cf7cac13a649d6c2087dca8873a8edd4d3c8d">PrintNameIr</a> and <a href="/web-llvm/docs/api/structs/llvm/align/#a80735739b49cf97a491922c8f9af2cc1">llvm::Align::value</a>.</p>


<p>Referenced by <a href="#a5a4302f4590a281bb84e08b30c80591c">print</a> and <a href="#a691794b4391537d134a8b2afbd21f8cb">printAsOperand</a>.</p>

</div>
</div>

### push\_back() {#a3b1dce1f3354a357fb9061bb7568a84e}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void llvm::MachineBasicBlock::push_back (<a href="/web-llvm/docs/api/classes/llvm/machineinstr">MachineInstr</a> * MI)</td>
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



<p>Definition at line 1011 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/codegen/machinebasicblock-h">MachineBasicBlock.h</a>.</p>


<p>Reference <a href="/web-llvm/docs/api/files/lib/lib/codegen/lib/codegen/globalisel/irtranslator-cpp/#abe44dfdea65b4f7e11e0a608ab708b76">MI</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/classes/anonymous-r600machinecfgstructurizer-cpp-/r600machinecfgstructurizer/#a41dd7655c0a468a74784440f2a65bdb8">anonymous{R600MachineCFGStructurizer.cpp}::R600MachineCFGStructurizer::addDummyExitBlock</a>, <a href="/web-llvm/docs/api/classes/anonymous-siloweri1copies-cpp-/phiincominganalysis/#a223f44f36f65f70b6e7f23b59baffd15">anonymous{SILowerI1Copies.cpp}::PhiIncomingAnalysis::analyze</a>, <a href="/web-llvm/docs/api/classes/anonymous-silowersgprspills-cpp-/silowersgprspills/#a5647b98ce7f0b4ad6fedc71a993e9979">anonymous{SILowerSGPRSpills.cpp}::SILowerSGPRSpills::calculateSaveRestoreBlocks</a>, <a href="/web-llvm/docs/api/classes/anonymous-r600machinecfgstructurizer-cpp-/r600machinecfgstructurizer/#a3312930671bb8ba4a3e685149c8f4e43">anonymous{R600MachineCFGStructurizer.cpp}::R600MachineCFGStructurizer::clone</a>, <a href="/web-llvm/docs/api/namespaces/anonymous-basicblockpathcloning-cpp-/#a0150e86671c87ec3046e8ba46be9f151">anonymous{BasicBlockPathCloning.cpp}::CloneMachineBasicBlock</a>, <a href="/web-llvm/docs/api/classes/anonymous-cskyconstantislandpass-cpp-/cskyconstantislands/#a6159cb24e3496f5b8bd5e830e052aba1">anonymous{CSKYConstantIslandPass.cpp}::CSKYConstantIslands::doInitialPlacement</a>, <a href="/web-llvm/docs/api/classes/anonymous-mipsconstantislandpass-cpp-/mipsconstantislands/#a3068d2fa3c2556694ca3db57b7c197dd">anonymous{MipsConstantIslandPass.cpp}::MipsConstantIslands::doInitialPlacement</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/riscv/riscvisellowering-cpp/#a59f08a4b78badcbfff06545894a60e6e">emitSelectPseudo</a>, <a href="/web-llvm/docs/api/classes/anonymous-r600machinecfgstructurizer-cpp-/r600machinecfgstructurizer/#a43d3fe2699745c950168939ee8f0d5cb">anonymous{R600MachineCFGStructurizer.cpp}::R600MachineCFGStructurizer::normalizeInfiniteLoopExit</a> and <a href="/web-llvm/docs/api/classes/llvm/irtranslator/#a2fa3a523a1812aeda17891575f852ce9">llvm::IRTranslator::runOnMachineFunction</a>.</p>

</div>
</div>

### rbegin() {#ad8c9657cfb03ef2ebf6364ba9d68c127}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">reverse_iterator llvm::MachineBasicBlock::rbegin ()</td>
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



<p>Definition at line 368 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/codegen/machinebasicblock-h">MachineBasicBlock.h</a>.</p>


<p>References <a href="/web-llvm/docs/api/classes/llvm/machineinstrbundleiterator/#aabd8ceec6157d122511b36eb7bcbe75a">llvm::MachineInstrBundleIterator&lt; MachineInstr, true &gt;::getAtBundleBegin</a> and <a href="#a3758eeb6d9f052f15217146b4ae4d5a1">instr_rbegin</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/classes/anonymous-x86winfixupbuffersecuritycheck-cpp-/x86winfixupbuffersecuritycheckpass/#a6195b88d995439efe9e0cdb9288df85c">anonymous{X86WinFixupBufferSecurityCheck.cpp}::X86WinFixupBufferSecurityCheckPass::getGuardCheckSequence</a>, <a href="/web-llvm/docs/api/files/lib/lib/codegen/branchfolding-cpp/#ae7773e6945ecc33b1e3ab0d47f293665">mergeOperations</a>, <a href="/web-llvm/docs/api/classes/anonymous-r600machinecfgstructurizer-cpp-/r600machinecfgstructurizer/#a484a24399c195bf93535e18192b7cc94">anonymous{R600MachineCFGStructurizer.cpp}::R600MachineCFGStructurizer::settleLoopcontBlock</a>, <a href="#ac0bfa894f538166cb476b439a2cb0aea">splitAt</a> and <a href="/web-llvm/docs/api/files/lib/lib/codegen/ifconversion-cpp/#a63c3add430381e43de46a44151e1a892">verifySameBranchInstructions</a>.</p>

</div>
</div>

### rbegin() {#a6c8e031b0c3396d32f8ed87dfda16a7d}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">const_reverse_iterator llvm::MachineBasicBlock::rbegin ()</td>
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



<p>Definition at line 371 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/codegen/machinebasicblock-h">MachineBasicBlock.h</a>.</p>


<p>References <a href="/web-llvm/docs/api/classes/llvm/machineinstrbundleiterator/#aabd8ceec6157d122511b36eb7bcbe75a">llvm::MachineInstrBundleIterator&lt; const MachineInstr, true &gt;::getAtBundleBegin</a> and <a href="#a3758eeb6d9f052f15217146b4ae4d5a1">instr_rbegin</a>.</p>

</div>
</div>

### remove() {#a6a77acab2477f9eaf0de232a1d94ff3d}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">MachineInstr * llvm::MachineBasicBlock::remove (<a href="/web-llvm/docs/api/classes/llvm/machineinstr">MachineInstr</a> * I)</td>
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

<p>Remove the unbundled instruction from the instruction list without deleting it.</p>


<p>This function can not be used to remove bundled instructions, use remove_instr to remove individual instructions from a bundle.</p>


<p>Definition at line 1098 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/codegen/machinebasicblock-h">MachineBasicBlock.h</a>.</p>


<p>References <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/silowercontrolflow-cpp/#a4868c5d81c5ccc98c47aeab6244346a0">assert</a> and <a href="/web-llvm/docs/api/files/lib/lib/support/md5-cpp/#ac0eafdc9ee161b71e7af98af736952fd">I</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/classes/llvm/x86instrinfo/#a08a488100b4cc4464d879a987e490915">llvm::X86InstrInfo::optimizeCompareInstr</a> and <a href="/web-llvm/docs/api/classes/llvm/machineinstr/#a1bc2f14c5e0de3c7ba77ed8d892a4c5a">llvm::MachineInstr::removeFromParent</a>.</p>

</div>
</div>

### remove\_instr() {#a1590a6d5d0f6d95dda90f2cf8954f3fb}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">MachineInstr * MachineBasicBlock::remove_instr (<a href="/web-llvm/docs/api/classes/llvm/machineinstr">MachineInstr</a> * I)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Remove the possibly bundled instruction from the instruction list without deleting it.</p>


<p>If the instruction is part of a bundle, the other instructions in the bundle will still be bundled after removing the single instruction.</p>


<p>Declaration at line 1108 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/codegen/machinebasicblock-h">MachineBasicBlock.h</a>, definition at line 1448 of file <a href="/web-llvm/docs/api/files/lib/lib/codegen/machinebasicblock-cpp">MachineBasicBlock.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/classes/llvm/machineinstr/#aafacf84de1cb994a92dc045f4aa1d518a9a9e5ef20669b2c9666b2689808b48ee">llvm::MachineInstr::BundledPred</a>, <a href="/web-llvm/docs/api/classes/llvm/machineinstr/#aafacf84de1cb994a92dc045f4aa1d518ad00e31da3877ce738df8343edcff6ed8">llvm::MachineInstr::BundledSucc</a>, <a href="/web-llvm/docs/api/files/lib/lib/codegen/lib/codegen/globalisel/irtranslator-cpp/#abe44dfdea65b4f7e11e0a608ab708b76">MI</a> and <a href="/web-llvm/docs/api/files/lib/lib/codegen/machinebasicblock-cpp/#a6373a450215747746eb3eeeccc3d45f1">unbundleSingleMI</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/classes/llvm/aarch64targetlowering/#ab812d774aa563ffc2c67030a9ba1be39">llvm::AArch64TargetLowering::EmitAllocateSMESaveBuffer</a>, <a href="/web-llvm/docs/api/classes/llvm/aarch64targetlowering/#ab9a65a8c0739a72de196022849b4ee67">llvm::AArch64TargetLowering::EmitAllocateZABuffer</a>, <a href="/web-llvm/docs/api/classes/llvm/aarch64targetlowering/#acfee0aff6a62996ec1dbee56ef35ad88">llvm::AArch64TargetLowering::EmitGetSMESaveSize</a>, <a href="/web-llvm/docs/api/classes/llvm/aarch64targetlowering/#a2ed887f0677d391bc6f9d7e77b761695">llvm::AArch64TargetLowering::EmitInitTPIDR2Object</a>, <a href="/web-llvm/docs/api/classes/llvm/spirvtargetlowering/#ab0b7a641c5208a3cd348ac5ea98e59b6">llvm::SPIRVTargetLowering::finalizeLowering</a> and <a href="/web-llvm/docs/api/classes/llvm/machineinstr/#a471e524f23e926d8d76bcdaa6355d7eb">llvm::MachineInstr::removeFromBundle</a>.</p>

</div>
</div>

### removeFromParent() {#af99e842f9d7eeea463d1d8f0bd34a0d0}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">MachineBasicBlock * MachineBasicBlock::removeFromParent ()</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>This method unlinks 'this' from the containing function, and returns it, but does not delete it.</p>

<p>Declaration at line 1137 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/codegen/machinebasicblock-h">MachineBasicBlock.h</a>, definition at line 1469 of file <a href="/web-llvm/docs/api/files/lib/lib/codegen/machinebasicblock-cpp">MachineBasicBlock.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/silowercontrolflow-cpp/#a4868c5d81c5ccc98c47aeab6244346a0">assert</a>, <a href="#acf6442108e21e7e5379feb8962de65b7">getParent</a> and <a href="/web-llvm/docs/api/classes/llvm/machinefunction/#ab4a521be45d78861faab0ed3e7540f77">llvm::MachineFunction::remove</a>.</p>

</div>
</div>

### removeLiveIn() {#a668e2f48294f63416c8f28072e531c33}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void MachineBasicBlock::removeLiveIn (<a href="/web-llvm/docs/api/classes/llvm/mcregister">MCRegister</a> Reg, <a href="/web-llvm/docs/api/structs/llvm/lanebitmask">LaneBitmask</a> LaneMask=<a href="/web-llvm/docs/api/structs/llvm/lanebitmask/#a3714a639930eab71d7202da05ad82990">LaneBitmask::getAll</a>())</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Remove the specified register from the live in set.</p>

<p>Declaration at line 491 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/codegen/machinebasicblock-h">MachineBasicBlock.h</a>, definition at line 600 of file <a href="/web-llvm/docs/api/files/lib/lib/codegen/machinebasicblock-cpp">MachineBasicBlock.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/namespaces/llvm/#ac78c09ae232b2ce188ff590d51e3c268">llvm::find_if</a>, <a href="/web-llvm/docs/api/files/lib/lib/support/md5-cpp/#ac0eafdc9ee161b71e7af98af736952fd">I</a> and <a href="/web-llvm/docs/api/structs/llvm/machinebasicblock/registermaskpair/#aec870716714bddabfc363a79a44a52ca">llvm::MachineBasicBlock::RegisterMaskPair::PhysReg</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/classes/anonymous-hexagoncfgoptimizer-cpp-/hexagoncfgoptimizer/#a44a6c0917383ba77dca7325a7b23c252">anonymous{HexagonCFGOptimizer.cpp}::HexagonCFGOptimizer::runOnMachineFunction</a> and <a href="/web-llvm/docs/api/files/lib/lib/codegen/machinesink-cpp/#a6c1da13a967ff01e9076c55b0b6d158c">updateLiveIn</a>.</p>

</div>
</div>

### removeLiveIn() {#ac3c75602432ab98a011f0a469ebdc5c2}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">MachineBasicBlock::livein_iterator MachineBasicBlock::removeLiveIn (<a href="#a787c857539b04a8552aec72d561a3ca2">livein_iterator</a> I)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Remove entry from the livein set and return iterator to the next.</p>

<p>Declaration at line 519 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/codegen/machinebasicblock-h">MachineBasicBlock.h</a>, definition at line 612 of file <a href="/web-llvm/docs/api/files/lib/lib/codegen/machinebasicblock-cpp">MachineBasicBlock.cpp</a>.</p>


<p>Reference <a href="/web-llvm/docs/api/files/lib/lib/support/md5-cpp/#ac0eafdc9ee161b71e7af98af736952fd">I</a>.</p>

</div>
</div>

### removeSuccessor() {#aa7114bb360b922025e7a4fec442676db}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void MachineBasicBlock::removeSuccessor (<a href="/web-llvm/docs/api/classes/llvm/machinebasicblock">MachineBasicBlock</a> * Succ, bool NormalizeSuccProbs=false)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Remove successor from the successors list of this <a href="/web-llvm/docs/api/classes/llvm/machinebasicblock">MachineBasicBlock</a>.</p>


<p>The Predecessors list of Succ is automatically updated. If NormalizeSuccProbs is true, then normalize successors' probabilities after the successor is removed.</p>


<p>Declaration at line 785 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/codegen/machinebasicblock-h">MachineBasicBlock.h</a>, definition at line 836 of file <a href="/web-llvm/docs/api/files/lib/lib/codegen/machinebasicblock-cpp">MachineBasicBlock.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/namespaces/llvm/#a086e9fbdb06276db7753101a08a63adf">llvm::find</a>, <a href="/web-llvm/docs/api/files/lib/lib/support/md5-cpp/#ac0eafdc9ee161b71e7af98af736952fd">I</a> and <a href="#aa7114bb360b922025e7a4fec442676db">removeSuccessor</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/classes/anonymous-ppcbranchcoalescing-cpp-/ppcbranchcoalescing/#a072a336f973a3de4daa8fe16e5b4570f">anonymous{PPCBranchCoalescing.cpp}::PPCBranchCoalescing::mergeCandidates</a>, <a href="/web-llvm/docs/api/classes/anonymous-r600machinecfgstructurizer-cpp-/r600machinecfgstructurizer/#aa76d1bb8a35c5fe0c9c22df9cc0dba10">anonymous{R600MachineCFGStructurizer.cpp}::R600MachineCFGStructurizer::mergeIfthenelseBlock</a>, <a href="/web-llvm/docs/api/classes/anonymous-r600machinecfgstructurizer-cpp-/r600machinecfgstructurizer/#ac1a085b3eb182136b9d98a7d6916421f">anonymous{R600MachineCFGStructurizer.cpp}::R600MachineCFGStructurizer::mergeLoopbreakBlock</a>, <a href="/web-llvm/docs/api/classes/anonymous-r600machinecfgstructurizer-cpp-/r600machinecfgstructurizer/#a5fec9aab7a2ff820c3c372f3cda87c25">anonymous{R600MachineCFGStructurizer.cpp}::R600MachineCFGStructurizer::mergeSerialBlock</a>, <a href="/web-llvm/docs/api/structs/anonymous-ppcearlyreturn-cpp-/ppcearlyreturn/#ae036500138a9ae1567af6b28547cf045">anonymous{PPCEarlyReturn.cpp}::PPCEarlyReturn::processBlock</a>, <a href="#aa7114bb360b922025e7a4fec442676db">removeSuccessor</a>, <a href="#a2d4703c258359175d1c7840735bd77b6">replaceSuccessor</a>, <a href="/web-llvm/docs/api/files/lib/lib/codegen/shrinkwrap-cpp/#a5aa69466ef430dc4ba4de70307ae4415">rollbackRestoreSplit</a>, <a href="#a31e57b158a17c459f0dc34b0e602ecc6">transferSuccessors</a> and <a href="#a046a35e36c4c1206711ea82ee9cb6d72">transferSuccessorsAndUpdatePHIs</a>.</p>

</div>
</div>

### removeSuccessor() {#a29a36aca5cf01600bc3f403aaa2f2467}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">MachineBasicBlock::succ_iterator MachineBasicBlock::removeSuccessor (<a href="#a9936e11d7a6149f7cac8fa32a81dd488">succ_iterator</a> I, bool NormalizeSuccProbs=false)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Remove specified successor from the successors list of this <a href="/web-llvm/docs/api/classes/llvm/machinebasicblock">MachineBasicBlock</a>.</p>


<p>The Predecessors list of Succ is automatically updated. If NormalizeSuccProbs is true, then normalize successors' probabilities after the successor is removed. Return the iterator to the element after the one removed.</p>


<p>Declaration at line 793 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/codegen/machinebasicblock-h">MachineBasicBlock.h</a>, definition at line 843 of file <a href="/web-llvm/docs/api/files/lib/lib/codegen/machinebasicblock-cpp">MachineBasicBlock.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/silowercontrolflow-cpp/#a4868c5d81c5ccc98c47aeab6244346a0">assert</a>, <a href="/web-llvm/docs/api/files/lib/lib/support/md5-cpp/#ac0eafdc9ee161b71e7af98af736952fd">I</a> and <a href="#a0c54da24de983d197068425e718fb607">normalizeSuccProbs</a>.</p>

</div>
</div>

### rend() {#a2a25c462b91ac5da41f4ab7edc32b650}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">reverse_iterator llvm::MachineBasicBlock::rend ()</td>
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



<p>Definition at line 374 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/codegen/machinebasicblock-h">MachineBasicBlock.h</a>.</p>


<p>Reference <a href="#ab42a834f1ab8e65b6f525a5cb23a4fe7">instr_rend</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/classes/llvm/x86targetlowering/#a5fd231b7f6dc1db67a2bb2f48bf5f342">llvm::X86TargetLowering::EmitInstrWithCustomInserter</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64redundantcopyelimination-cpp/#af884214031cdb18344d85b5d4c422fef">INITIALIZE_PASS</a>, <a href="/web-llvm/docs/api/classes/llvm/reachingdefanalysis/#a7bc46cb4bc77e9715066c204bd98e309">llvm::ReachingDefAnalysis::isSafeToMoveBackwards</a>, <a href="/web-llvm/docs/api/files/lib/lib/codegen/branchfolding-cpp/#ae7773e6945ecc33b1e3ab0d47f293665">mergeOperations</a>, <a href="/web-llvm/docs/api/classes/llvm/x86instrinfo/#a08a488100b4cc4464d879a987e490915">llvm::X86InstrInfo::optimizeCompareInstr</a>, <a href="/web-llvm/docs/api/classes/anonymous-amdgpumarklastscratchload-cpp-/amdgpumarklastscratchload/#adb457e87e019538757ec91bec7a7e5f0">anonymous{AMDGPUMarkLastScratchLoad.cpp}::AMDGPUMarkLastScratchLoad::runOnMachineFunction</a> and <a href="/web-llvm/docs/api/files/lib/lib/codegen/ifconversion-cpp/#a63c3add430381e43de46a44151e1a892">verifySameBranchInstructions</a>.</p>

</div>
</div>

### rend() {#ab4d33f4fc1545c32aa8bef180f5dbc19}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">const_reverse_iterator llvm::MachineBasicBlock::rend ()</td>
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



<p>Definition at line 375 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/codegen/machinebasicblock-h">MachineBasicBlock.h</a>.</p>


<p>Reference <a href="#ab42a834f1ab8e65b6f525a5cb23a4fe7">instr_rend</a>.</p>

</div>
</div>

### replacePhiUsesWith() {#a134a21189d056b81b80d0cdf01ef8c46}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void MachineBasicBlock::replacePhiUsesWith (<a href="/web-llvm/docs/api/classes/llvm/machinebasicblock">MachineBasicBlock</a> * Old, <a href="/web-llvm/docs/api/classes/llvm/machinebasicblock">MachineBasicBlock</a> * New)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Update all phi nodes in this basic block to refer to basic block <span class="doxyComputerOutput">New</span> instead of basic block <span class="doxyComputerOutput">Old</span>.</p>

<p>Declaration at line 1148 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/codegen/machinebasicblock-h">MachineBasicBlock.h</a>, definition at line 1503 of file <a href="/web-llvm/docs/api/files/lib/lib/codegen/machinebasicblock-cpp">MachineBasicBlock.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/classes/llvm/machineoperand/#a57e64b633278df75c699e6b98ce15031">llvm::MachineOperand::getMBB</a>, <a href="/web-llvm/docs/api/files/lib/lib/codegen/lib/codegen/globalisel/irtranslator-cpp/#abe44dfdea65b4f7e11e0a608ab708b76">MI</a>, <a href="#a36b529ef331e4099007e14b48c75316a">phis</a> and <a href="/web-llvm/docs/api/classes/llvm/machineoperand/#a98e9c9e8ef7cbb6c4aa89a38f21decfa">llvm::MachineOperand::setMBB</a>.</p>


<p>Referenced by <a href="#aa80aaa82844ab5560ece045eee7b34ac">SplitCriticalEdge</a> and <a href="#a046a35e36c4c1206711ea82ee9cb6d72">transferSuccessorsAndUpdatePHIs</a>.</p>

</div>
</div>

### replaceSuccessor() {#a2d4703c258359175d1c7840735bd77b6}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void MachineBasicBlock::replaceSuccessor (<a href="/web-llvm/docs/api/classes/llvm/machinebasicblock">MachineBasicBlock</a> * Old, <a href="/web-llvm/docs/api/classes/llvm/machinebasicblock">MachineBasicBlock</a> * New)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Replace successor OLD with NEW and update probability info.</p>

<p>Declaration at line 797 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/codegen/machinebasicblock-h">MachineBasicBlock.h</a>, definition at line 859 of file <a href="/web-llvm/docs/api/files/lib/lib/codegen/machinebasicblock-cpp">MachineBasicBlock.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/silowercontrolflow-cpp/#a4868c5d81c5ccc98c47aeab6244346a0">assert</a>, <a href="/web-llvm/docs/api/files/lib/lib/support/md5-cpp/#ac0eafdc9ee161b71e7af98af736952fd">I</a>, <a href="#aa7114bb360b922025e7a4fec442676db">removeSuccessor</a>, <a href="#a6321b189ea8fd5058663f8a87d6c23e9">succ_begin</a> and <a href="#a3ddd708642d60c1661992ff8ba1b215d">succ_end</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/classes/anonymous-r600machinecfgstructurizer-cpp-/r600machinecfgstructurizer/#a8945ac962ff2d369b77ff9ab927529a4">anonymous{R600MachineCFGStructurizer.cpp}::R600MachineCFGStructurizer::cloneBlockForPredecessor</a>, <a href="/web-llvm/docs/api/classes/anonymous-r600machinecfgstructurizer-cpp-/r600machinecfgstructurizer/#ab38ab4f331b754f58147aaa7a86febb1">anonymous{R600MachineCFGStructurizer.cpp}::R600MachineCFGStructurizer::mergeLooplandBlock</a>, <a href="#ab9a54fdc7456ee97cb54ff30d625b6b7">ReplaceUsesOfBlockWith</a>, <a href="/web-llvm/docs/api/classes/llvm/armblockplacement/#a977d1a0dea04c7f562cb1ca6063d81dd">llvm::ARMBlockPlacement::revertWhileToDoLoop</a> and <a href="/web-llvm/docs/api/classes/anonymous-hexagoncfgoptimizer-cpp-/hexagoncfgoptimizer/#a44a6c0917383ba77dca7325a7b23c252">anonymous{HexagonCFGOptimizer.cpp}::HexagonCFGOptimizer::runOnMachineFunction</a>.</p>

</div>
</div>

### ReplaceUsesOfBlockWith() {#ab9a54fdc7456ee97cb54ff30d625b6b7}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void MachineBasicBlock::ReplaceUsesOfBlockWith (<a href="/web-llvm/docs/api/classes/llvm/machinebasicblock">MachineBasicBlock</a> * Old, <a href="/web-llvm/docs/api/classes/llvm/machinebasicblock">MachineBasicBlock</a> * New)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Given a machine basic block that branched to 'Old', change the code and CFG so that it branches to 'New' instead.</p>

<p>Declaration at line 1144 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/codegen/machinebasicblock-h">MachineBasicBlock.h</a>, definition at line 1483 of file <a href="/web-llvm/docs/api/files/lib/lib/codegen/machinebasicblock-cpp">MachineBasicBlock.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/silowercontrolflow-cpp/#a4868c5d81c5ccc98c47aeab6244346a0">assert</a>, <a href="/web-llvm/docs/api/files/lib/lib/support/md5-cpp/#ac0eafdc9ee161b71e7af98af736952fd">I</a>, <a href="#a172e7bd9150eb0519ef04c796086f93d">instr_begin</a>, <a href="#acae72f6ab1071b7ec87b741a8bef582b">instr_end</a> and <a href="#a2d4703c258359175d1c7840735bd77b6">replaceSuccessor</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/namespaces/anonymous-basicblockpathcloning-cpp-/#a09842318dc1064ae48b19d91e2cb11aa">anonymous{BasicBlockPathCloning.cpp}::ApplyCloning</a>, <a href="/web-llvm/docs/api/classes/anonymous-ppcbranchcoalescing-cpp-/ppcbranchcoalescing/#a072a336f973a3de4daa8fe16e5b4570f">anonymous{PPCBranchCoalescing.cpp}::PPCBranchCoalescing::mergeCandidates</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a0fdc13bfd373951ae6163637d6576c39">llvm::PeelSingleBlockLoop</a> and <a href="#aa80aaa82844ab5560ece045eee7b34ac">SplitCriticalEdge</a>.</p>

</div>
</div>

### rfindDebugLoc() {#ab2192a3dc7e43ace4706a00258bf5f47}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">DebugLoc MachineBasicBlock::rfindDebugLoc (<a href="#afde32735260c30997acd66990e80a320">reverse_instr_iterator</a> MBBI)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Has exact same behavior as <a href="#ab622d694b5fcb0edb99159f1ebdcdb6b">findDebugLoc</a> (it also searches towards the end of this MBB) except that this function takes a reverse iterator to identify the starting MI.</p>

<p>Declaration at line 1160 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/codegen/machinebasicblock-h">MachineBasicBlock.h</a>, definition at line 1524 of file <a href="/web-llvm/docs/api/files/lib/lib/codegen/machinebasicblock-cpp">MachineBasicBlock.cpp</a>.</p>


<p>References <a href="#ab622d694b5fcb0edb99159f1ebdcdb6b">findDebugLoc</a>, <a href="#a172e7bd9150eb0519ef04c796086f93d">instr_begin</a>, <a href="#a3758eeb6d9f052f15217146b4ae4d5a1">instr_rbegin</a>, <a href="#ab42a834f1ab8e65b6f525a5cb23a4fe7">instr_rend</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/arm/armslshardening-cpp/#ad5f691fdc1a09aaf6df5fef958b35a3d">MBBI</a> and <a href="/web-llvm/docs/api/namespaces/llvm/#a9256279285c60fce1b2eb1b928599461">llvm::skipDebugInstructionsBackward</a>.</p>


<p>Referenced by <a href="#a64a742bb4380d11a9b4c23c5c2794c79">rfindDebugLoc</a>.</p>

</div>
</div>

### rfindDebugLoc() {#a64a742bb4380d11a9b4c23c5c2794c79}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">DebugLoc llvm::MachineBasicBlock::rfindDebugLoc (<a href="#abada92f8cd2854d2b747f14c4a7be0ed">reverse_iterator</a> MBBI)</td>
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



<p>Definition at line 1161 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/codegen/machinebasicblock-h">MachineBasicBlock.h</a>.</p>


<p>References <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/arm/armslshardening-cpp/#ad5f691fdc1a09aaf6df5fef958b35a3d">MBBI</a> and <a href="#ab2192a3dc7e43ace4706a00258bf5f47">rfindDebugLoc</a>.</p>

</div>
</div>

### rfindPrevDebugLoc() {#a01356cc615c2222dba3e1b2776800add}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">DebugLoc MachineBasicBlock::rfindPrevDebugLoc (<a href="#afde32735260c30997acd66990e80a320">reverse_instr_iterator</a> MBBI)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Has exact same behavior as <a href="#abfe76200d04557c617e5f505717c3ad3">findPrevDebugLoc</a> (it also searches towards the beginning of this MBB) except that this function takes reverse iterator to identify the starting MI.</p>


<p>A minor difference compared to findPrevDebugLoc is that we can't start scanning at "instr_end".</p>


<p>Declaration at line 1177 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/codegen/machinebasicblock-h">MachineBasicBlock.h</a>, definition at line 1546 of file <a href="/web-llvm/docs/api/files/lib/lib/codegen/machinebasicblock-cpp">MachineBasicBlock.cpp</a>.</p>


<p>References <a href="#ab42a834f1ab8e65b6f525a5cb23a4fe7">instr_rend</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/arm/armslshardening-cpp/#ad5f691fdc1a09aaf6df5fef958b35a3d">MBBI</a> and <a href="/web-llvm/docs/api/namespaces/llvm/#a0270bdca4aeb43f39bf91c900a398057">llvm::next_nodbg</a>.</p>


<p>Referenced by <a href="#a20495533e294b68b1f9487ceee026459">rfindPrevDebugLoc</a>.</p>

</div>
</div>

### rfindPrevDebugLoc() {#a20495533e294b68b1f9487ceee026459}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">DebugLoc llvm::MachineBasicBlock::rfindPrevDebugLoc (<a href="#abada92f8cd2854d2b747f14c4a7be0ed">reverse_iterator</a> MBBI)</td>
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



<p>Definition at line 1178 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/codegen/machinebasicblock-h">MachineBasicBlock.h</a>.</p>


<p>References <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/arm/armslshardening-cpp/#ad5f691fdc1a09aaf6df5fef958b35a3d">MBBI</a> and <a href="#a01356cc615c2222dba3e1b2776800add">rfindPrevDebugLoc</a>.</p>

</div>
</div>

### sameSection() {#a7feb92c592c0f5bd6cbe88c5fbaa91f4}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool llvm::MachineBasicBlock::sameSection (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/machinebasicblock">MachineBasicBlock</a> * MBB)</td>
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

<p>Returns true if this and MBB belong to the same section.</p>

<p>Definition at line 734 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/codegen/machinebasicblock-h">MachineBasicBlock.h</a>.</p>


<p>References <a href="#a87ee39ccabd6fa5abe6302ebffd768c9">getSectionID</a> and <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/arm/armslshardening-cpp/#a5958512eae2979bd2eb383977996a600">MBB</a>.</p>

</div>
</div>

### setAddressTakenIRBlock() {#a0e100b3a8a8794e966c37ac13b1ea891}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void llvm::MachineBasicBlock::setAddressTakenIRBlock (<a href="/web-llvm/docs/api/classes/llvm/basicblock">BasicBlock</a> * BB)</td>
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

<p>Set this block to reflect that it corresponds to an IR-level basic block with a <a href="/web-llvm/docs/api/classes/llvm/blockaddress">BlockAddress</a>.</p>

<p>Definition at line 301 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/codegen/machinebasicblock-h">MachineBasicBlock.h</a>.</p>

</div>
</div>

### setAlignment() {#a8cb665c210dc8e43f537cf4c9b84e2c7}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void llvm::MachineBasicBlock::setAlignment (<a href="/web-llvm/docs/api/structs/llvm/align">Align</a> A)</td>
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

<p>Set alignment of the basic block.</p>

<p>Definition at line 626 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/codegen/machinebasicblock-h">MachineBasicBlock.h</a>.</p>


<p>Reference <a href="/web-llvm/docs/api/files/lib/lib/ir/builtingcs-cpp/#a2e38c85003a042421cde1647632d0b72">A</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/classes/anonymous-cskyconstantislandpass-cpp-/cskyconstantislands/#a6159cb24e3496f5b8bd5e830e052aba1">anonymous{CSKYConstantIslandPass.cpp}::CSKYConstantIslands::doInitialPlacement</a>, <a href="/web-llvm/docs/api/classes/anonymous-mipsconstantislandpass-cpp-/mipsconstantislands/#a3068d2fa3c2556694ca3db57b7c197dd">anonymous{MipsConstantIslandPass.cpp}::MipsConstantIslands::doInitialPlacement</a>, <a href="/web-llvm/docs/api/classes/anonymous-mipsconstantislandpass-cpp-/mipsconstantislands/#a7faaededab3b537edc011e168876a92b">anonymous{MipsConstantIslandPass.cpp}::MipsConstantIslands::fixupUnconditionalBr</a>, <a href="/web-llvm/docs/api/classes/anonymous-cskyconstantislandpass-cpp-/cskyconstantislands/#a800f62f10fe1fafc076ae4002371ba45">anonymous{CSKYConstantIslandPass.cpp}::CSKYConstantIslands::handleConstantPoolUser</a>, <a href="/web-llvm/docs/api/classes/anonymous-mipsconstantislandpass-cpp-/mipsconstantislands/#a4d3a04a082a7dd5b285cddb7feef368c">anonymous{MipsConstantIslandPass.cpp}::MipsConstantIslands::handleConstantPoolUser</a>, <a href="/web-llvm/docs/api/structs/anonymous-x86indirectthunks-cpp-/retpolinethunkinserter/#aceed22e00e1b77a1a8cab4ac045d6a21">anonymous{X86IndirectThunks.cpp}::RetpolineThunkInserter::populateThunk</a>, <a href="/web-llvm/docs/api/classes/anonymous-cskyconstantislandpass-cpp-/cskyconstantislands/#a260e4fa04b4392ed7de8a9202292a2ca">anonymous{CSKYConstantIslandPass.cpp}::CSKYConstantIslands::removeDeadCPEMI</a>, <a href="/web-llvm/docs/api/classes/anonymous-mipsconstantislandpass-cpp-/mipsconstantislands/#abbda87d0f5c41ed3eca00b354a53417d">anonymous{MipsConstantIslandPass.cpp}::MipsConstantIslands::removeDeadCPEMI</a> and <a href="#a36652c385717d0111378ed12b65dbb75">setAlignment</a>.</p>

</div>
</div>

### setAlignment() {#a36652c385717d0111378ed12b65dbb75}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void llvm::MachineBasicBlock::setAlignment (<a href="/web-llvm/docs/api/structs/llvm/align">Align</a> A, unsigned MaxBytes)</td>
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



<p>Definition at line 628 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/codegen/machinebasicblock-h">MachineBasicBlock.h</a>.</p>


<p>References <a href="/web-llvm/docs/api/files/lib/lib/ir/builtingcs-cpp/#a2e38c85003a042421cde1647632d0b72">A</a>, <a href="#a8cb665c210dc8e43f537cf4c9b84e2c7">setAlignment</a> and <a href="#a6e758ce47fe7d9b66e9accb1b8418e43">setMaxBytesForAlignment</a>.</p>

</div>
</div>

### setBBID() {#a088df0647ac6dd7fc843b2d2f7126327}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void llvm::MachineBasicBlock::setBBID (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/structs/llvm/uniquebbid">UniqueBBID</a> &amp; V)</td>
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

<p>Sets the fixed BBID of this basic block.</p>

<p>Definition at line 696 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/codegen/machinebasicblock-h">MachineBasicBlock.h</a>.</p>


<p>Reference <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/silowercontrolflow-cpp/#a4868c5d81c5ccc98c47aeab6244346a0">assert</a>.</p>

</div>
</div>

### setCallFrameSize() {#a4472755d36621c5e2d056eec5056202e}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void llvm::MachineBasicBlock::setCallFrameSize (unsigned N)</td>
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

<p>Set the call frame size on entry to this basic block.</p>

<p>Definition at line 1232 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/codegen/machinebasicblock-h">MachineBasicBlock.h</a>.</p>


<p>Reference <a href="/web-llvm/docs/api/files/lib/lib/support/regcomp-c/#a0240ac851181b84ac374872dc5434ee4">N</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/classes/llvm/armtargetlowering/#a6820d09b4db5654cd1377d3ab63b3e01">llvm::ARMTargetLowering::EmitInstrWithCustomInserter</a>, <a href="/web-llvm/docs/api/classes/llvm/avrtargetlowering/#a336444d567b931e2ced0dd4f844148ab">llvm::AVRTargetLowering::EmitInstrWithCustomInserter</a>, <a href="/web-llvm/docs/api/classes/llvm/ppctargetlowering/#a10d6f09e62a827099ec8b54efb4c035d">llvm::PPCTargetLowering::EmitInstrWithCustomInserter</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/riscv/riscvisellowering-cpp/#a59f08a4b78badcbfff06545894a60e6e">emitSelectPseudo</a> and <a href="#aa80aaa82844ab5560ece045eee7b34ac">SplitCriticalEdge</a>.</p>

</div>
</div>

### setIrrLoopHeaderWeight() {#a19e7678bb3906783e58c80452147c3b5}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void llvm::MachineBasicBlock::setIrrLoopHeaderWeight (uint64_t Weight)</td>
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



<p>Definition at line 1244 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/codegen/machinebasicblock-h">MachineBasicBlock.h</a>.</p>

</div>
</div>

### setIsBeginSection() {#af8228a164de284cac5db790f0377031b}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void llvm::MachineBasicBlock::setIsBeginSection (bool V=<a href="/web-llvm/docs/api/files/lib/lib/analysis/basicaliasanalysis-cpp/#af6d5cafbdfc5313e65d990120021a3ec">true</a>)</td>
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



<p>Definition at line 686 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/codegen/machinebasicblock-h">MachineBasicBlock.h</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/classes/llvm/machinefunction/#af588c66ab3fcfe66fd0c99bcd645ee36">llvm::MachineFunction::assignBeginEndSections</a>.</p>

</div>
</div>

### setIsCleanupFuncletEntry() {#a1e199d04a33af3daf0b9c29c6b0d83f0}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void llvm::MachineBasicBlock::setIsCleanupFuncletEntry (bool V=<a href="/web-llvm/docs/api/files/lib/lib/analysis/basicaliasanalysis-cpp/#af6d5cafbdfc5313e65d990120021a3ec">true</a>)</td>
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

<p>Indicates if this is the entry block of a cleanup funclet.</p>

<p>Definition at line 678 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/codegen/machinebasicblock-h">MachineBasicBlock.h</a>.</p>

</div>
</div>

### setIsEHCatchretTarget() {#a148fa7c12ad7679341d884e0f8295d39}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void llvm::MachineBasicBlock::setIsEHCatchretTarget (bool V=<a href="/web-llvm/docs/api/files/lib/lib/analysis/basicaliasanalysis-cpp/#af6d5cafbdfc5313e65d990120021a3ec">true</a>)</td>
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

<p>Indicates if this is a target block of a catchret.</p>

<p>Definition at line 666 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/codegen/machinebasicblock-h">MachineBasicBlock.h</a>.</p>

</div>
</div>

### setIsEHFuncletEntry() {#ad6a02ab1681cddfb6a5991ad2a5fff88}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void llvm::MachineBasicBlock::setIsEHFuncletEntry (bool V=<a href="/web-llvm/docs/api/files/lib/lib/analysis/basicaliasanalysis-cpp/#af6d5cafbdfc5313e65d990120021a3ec">true</a>)</td>
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

<p>Indicates if this is the entry block of an EH funclet.</p>

<p>Definition at line 672 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/codegen/machinebasicblock-h">MachineBasicBlock.h</a>.</p>

</div>
</div>

### setIsEHPad() {#afcc0e4bdd74c918624da8eea761a0ef9}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void llvm::MachineBasicBlock::setIsEHPad (bool V=<a href="/web-llvm/docs/api/files/lib/lib/analysis/basicaliasanalysis-cpp/#af6d5cafbdfc5313e65d990120021a3ec">true</a>)</td>
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

<p>Indicates the block is a landing pad.</p>


<p>That is this basic block is entered via an exception handler.</p>


<p>Definition at line 647 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/codegen/machinebasicblock-h">MachineBasicBlock.h</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/classes/llvm/vetargetlowering/#a751f59893007a8fdcc892d81119abc82">llvm::VETargetLowering::emitSjLjDispatchBlock</a>.</p>

</div>
</div>

### setIsEHScopeEntry() {#af296bb7eb6fea94d49bfbc434cf3bf3c}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void llvm::MachineBasicBlock::setIsEHScopeEntry (bool V=<a href="/web-llvm/docs/api/files/lib/lib/analysis/basicaliasanalysis-cpp/#af6d5cafbdfc5313e65d990120021a3ec">true</a>)</td>
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

<p>Indicates if this is the entry block of an EH scope, i.e., the block that that used to have a catchpad or cleanuppad instruction in the LLVM IR.</p>

<p>Definition at line 660 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/codegen/machinebasicblock-h">MachineBasicBlock.h</a>.</p>

</div>
</div>

### setIsEndSection() {#a17f6a7634e1ea3b0fbaf1de07e000818}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void llvm::MachineBasicBlock::setIsEndSection (bool V=<a href="/web-llvm/docs/api/files/lib/lib/analysis/basicaliasanalysis-cpp/#af6d5cafbdfc5313e65d990120021a3ec">true</a>)</td>
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



<p>Definition at line 688 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/codegen/machinebasicblock-h">MachineBasicBlock.h</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/classes/llvm/machinefunction/#af588c66ab3fcfe66fd0c99bcd645ee36">llvm::MachineFunction::assignBeginEndSections</a>.</p>

</div>
</div>

### setIsInlineAsmBrIndirectTarget() {#ac9e8a1eeb039aaa25962721ca718de49}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void llvm::MachineBasicBlock::setIsInlineAsmBrIndirectTarget (bool V=<a href="/web-llvm/docs/api/files/lib/lib/analysis/basicaliasanalysis-cpp/#af6d5cafbdfc5313e65d990120021a3ec">true</a>)</td>
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

<p>Indicates if this is the indirect dest of an INLINEASM_BR.</p>

<p>Definition at line 718 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/codegen/machinebasicblock-h">MachineBasicBlock.h</a>.</p>

</div>
</div>

### setLabelMustBeEmitted() {#a2861faef4c19963f6994aded803f7d20}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void llvm::MachineBasicBlock::setLabelMustBeEmitted ()</td>
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

<p>Set this block to reflect that, regardless how we flow to it, we need its label be emitted.</p>

<p>Definition at line 308 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/codegen/machinebasicblock-h">MachineBasicBlock.h</a>.</p>

</div>
</div>

### setMachineBlockAddressTaken() {#af4236a9c3c028303d301f49c7ee9a868}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void llvm::MachineBasicBlock::setMachineBlockAddressTaken ()</td>
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

<p>Set this block to indicate that its address is used as something other than the target of a terminator, exception-handling target, jump table, or IR-level "blockaddress".</p>

<p>Definition at line 297 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/codegen/machinebasicblock-h">MachineBasicBlock.h</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/classes/llvm/systemztargetlowering/#a2a8a6c3f5cf71d0e400566ee13c6e828">llvm::SystemZTargetLowering::emitEHSjLjSetJmp</a>, <a href="/web-llvm/docs/api/classes/llvm/vetargetlowering/#a9b01008eed371b3da0faa8604b91e828">llvm::VETargetLowering::emitEHSjLjSetJmp</a> and <a href="/web-llvm/docs/api/structs/anonymous-x86indirectthunks-cpp-/retpolinethunkinserter/#aceed22e00e1b77a1a8cab4ac045d6a21">anonymous{X86IndirectThunks.cpp}::RetpolineThunkInserter::populateThunk</a>.</p>

</div>
</div>

### setMaxBytesForAlignment() {#a6e758ce47fe7d9b66e9accb1b8418e43}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void llvm::MachineBasicBlock::setMaxBytesForAlignment (unsigned MaxBytes)</td>
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

<p>Set the maximum amount of padding allowed for aligning the basic block.</p>

<p>Definition at line 637 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/codegen/machinebasicblock-h">MachineBasicBlock.h</a>.</p>


<p>Referenced by <a href="#a36652c385717d0111378ed12b65dbb75">setAlignment</a>.</p>

</div>
</div>

### setNumber() {#a87d6a6ddceb28f49cb7c34727c989c0a}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void llvm::MachineBasicBlock::setNumber (int N)</td>
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



<p>Definition at line 1227 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/codegen/machinebasicblock-h">MachineBasicBlock.h</a>.</p>


<p>Reference <a href="/web-llvm/docs/api/files/lib/lib/support/regcomp-c/#a0240ac851181b84ac374872dc5434ee4">N</a>.</p>

</div>
</div>

### setSectionID() {#aac864a2ce4f4fcac4c21062b29986c5c}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void llvm::MachineBasicBlock::setSectionID (<a href="/web-llvm/docs/api/structs/llvm/mbbsectionid">MBBSectionID</a> V)</td>
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

<p>Sets the section <a href="/web-llvm/docs/api/namespaces/llvm/callingconv/#abdf8cf606905c10634e831390981b0ed">ID</a> for this basic block.</p>

<p>Definition at line 702 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/codegen/machinebasicblock-h">MachineBasicBlock.h</a>.</p>

</div>
</div>

### setSuccProbability() {#a6171d209616c58347dea44a49d7675c0}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void MachineBasicBlock::setSuccProbability (<a href="#a9936e11d7a6149f7cac8fa32a81dd488">succ_iterator</a> I, <a href="/web-llvm/docs/api/classes/llvm/branchprobability">BranchProbability</a> Prob)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Set successor probability of a given iterator.</p>

<p>Declaration at line 766 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/codegen/machinebasicblock-h">MachineBasicBlock.h</a>, definition at line 1598 of file <a href="/web-llvm/docs/api/files/lib/lib/codegen/machinebasicblock-cpp">MachineBasicBlock.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/silowercontrolflow-cpp/#a4868c5d81c5ccc98c47aeab6244346a0">assert</a>, <a href="/web-llvm/docs/api/files/lib/lib/support/md5-cpp/#ac0eafdc9ee161b71e7af98af736952fd">I</a> and <a href="/web-llvm/docs/api/classes/llvm/branchprobability/#a7f41716b68c197b7cd7582d7a66201a3">llvm::BranchProbability::isUnknown</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/classes/llvm/mirprofileloader/#a31f2c5f323ca8742d0588171e0c33b49">llvm::MIRProfileLoader::setBranchProbs</a> and <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/powerpc/ppcreducecrlogicals-cpp/#a6268a1294b61555b575fbd131789aaf3">splitMBB</a>.</p>

</div>
</div>

### size() {#adbff55f335d303816547f35eb6edb948}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">unsigned llvm::MachineBasicBlock::size ()</td>
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



<p>Definition at line 334 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/codegen/machinebasicblock-h">MachineBasicBlock.h</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/classes/llvm/aggressiveantidepstate/#a0c8e899a88a4162aeeaca5461012bb78">llvm::AggressiveAntiDepState::AggressiveAntiDepState</a>, <a href="/web-llvm/docs/api/classes/llvm/riscvframelowering/#a4c55a328d2daf9b5e2f457c8880e21c4">llvm::RISCVFrameLowering::canUseAsEpilogue</a>, <a href="#a5bfe9045e7f0a89622211264b32ff155">getSinglePredecessor</a>, <a href="#aa0a5ac19256656534bea2daabdfb947b">getSingleSuccessor</a>, <a href="/web-llvm/docs/api/classes/anonymous-r600machinecfgstructurizer-cpp-/r600machinecfgstructurizer/#a34b11aa12929fbf594b75074a35dc9c2">anonymous{R600MachineCFGStructurizer.cpp}::R600MachineCFGStructurizer::migrateInstruction</a>, <a href="/web-llvm/docs/api/structs/anonymous-aarch64slshardening-cpp-/slshardeninginserter/#aa0294873aedbdc7244e1ca9aa115889e">anonymous{AArch64SLSHardening.cpp}::SLSHardeningInserter::populateThunk</a>, <a href="/web-llvm/docs/api/classes/anonymous-hexagoncfgoptimizer-cpp-/hexagoncfgoptimizer/#a44a6c0917383ba77dca7325a7b23c252">anonymous{HexagonCFGOptimizer.cpp}::HexagonCFGOptimizer::runOnMachineFunction</a>, <a href="/web-llvm/docs/api/classes/anonymous-r600machinecfgstructurizer-cpp-/r600machinecfgstructurizer/#ac471c55917cb9e3fdc7674e300260d9f">anonymous{R600MachineCFGStructurizer.cpp}::R600MachineCFGStructurizer::showImproveSimpleJumpintoIf</a>, <a href="/web-llvm/docs/api/classes/llvm/aggressiveantidepbreaker/#abd095bb58a0243946704d20d3559d420">llvm::AggressiveAntiDepBreaker::StartBlock</a> and <a href="/web-llvm/docs/api/classes/llvm/criticalantidepbreaker/#adb4573a84f25279673e3906914132a39">llvm::CriticalAntiDepBreaker::StartBlock</a>.</p>

</div>
</div>

### sizeWithoutDebugLargerThan() {#af897d8e9556478c1442c739ce664bcb6}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool MachineBasicBlock::sizeWithoutDebugLargerThan (unsigned Limit)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Declaration at line 335 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/codegen/machinebasicblock-h">MachineBasicBlock.h</a>, definition at line 1777 of file <a href="/web-llvm/docs/api/files/lib/lib/codegen/machinebasicblock-cpp">MachineBasicBlock.cpp</a>.</p>


<p>References <a href="#ab2d91e7bec944efcbc39d8e30644f111">begin</a>, <a href="#acbc921830578e2741be6549db716c0ce">end</a>, <a href="/web-llvm/docs/api/files/lib/lib/support/md5-cpp/#ac0eafdc9ee161b71e7af98af736952fd">I</a> and <a href="/web-llvm/docs/api/namespaces/llvm/#a90f68a1fc5d44bb06164dc2188b8e486">llvm::instructionsWithoutDebug</a>.</p>

</div>
</div>

### SkipPHIsAndLabels() {#a3be7d94076d328797ab57ce09cefab33}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">MachineBasicBlock::iterator MachineBasicBlock::SkipPHIsAndLabels (<a href="#ae34c996b58df9b9ce6695a0c8b70c533">iterator</a> I)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Return the first instruction in MBB after I that is not a PHI or a label.</p>


<p>This is the correct point to insert lowered copies at the beginning of a basic block that must be before any debugging information.</p>


<p>Declaration at line 886 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/codegen/machinebasicblock-h">MachineBasicBlock.h</a>, definition at line 212 of file <a href="/web-llvm/docs/api/files/lib/lib/codegen/machinebasicblock-cpp">MachineBasicBlock.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/silowercontrolflow-cpp/#a4868c5d81c5ccc98c47aeab6244346a0">assert</a>, <a href="#acbc921830578e2741be6549db716c0ce">end</a>, <a href="/web-llvm/docs/api/classes/llvm/targetsubtargetinfo/#acd858ed72f11db9444617740c3622608">llvm::TargetSubtargetInfo::getInstrInfo</a>, <a href="#acf6442108e21e7e5379feb8962de65b7">getParent</a>, <a href="/web-llvm/docs/api/classes/llvm/machinefunction/#a3825368aca2bc1550d173660df4da6a6">llvm::MachineFunction::getSubtarget</a>, <a href="/web-llvm/docs/api/files/lib/lib/support/md5-cpp/#ac0eafdc9ee161b71e7af98af736952fd">I</a> and <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/hexagon/hexagoncopytocombine-cpp/#a1d40004718218dbdf06b496766299101">TII</a>.</p>


<p>Referenced by <a href="#a9bd7c04e374ad15665430a243dd30d80">addLiveIn</a>, <a href="/web-llvm/docs/api/classes/llvm/amdgpu/regbanklegalizehelper/#af375ca05eecaafa17b7a92ec352537d4">llvm::AMDGPU::RegBankLegalizeHelper::applyMappingPHI</a>, <a href="/web-llvm/docs/api/classes/regbankselecthelper/#ae56b2250d41c0820f12319e553d76084">RegBankSelectHelper::constrainRegBankUse</a> and <a href="/web-llvm/docs/api/files/lib/lib/codegen/branchfolding-cpp/#aaaf533c4a29ff1fd44bfef2f8feb1c3c">copyDebugInfoToSuccessor</a>.</p>

</div>
</div>

### SkipPHIsLabelsAndDebug() {#a5d8a45757c9861d499cba1a0d54e2c1e}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">MachineBasicBlock::iterator MachineBasicBlock::SkipPHIsLabelsAndDebug (<a href="#ae34c996b58df9b9ce6695a0c8b70c533">iterator</a> I, <a href="/web-llvm/docs/api/classes/llvm/register">Register</a> Reg=<a href="/web-llvm/docs/api/classes/llvm/register">Register</a>(), bool SkipPseudoOp=<a href="/web-llvm/docs/api/files/lib/lib/analysis/basicaliasanalysis-cpp/#af6d5cafbdfc5313e65d990120021a3ec">true</a>)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Return the first instruction in MBB after I that is not a PHI, label or debug.</p>


<p>This is the correct point to insert copies at the beginning of a basic block. <span class="doxyComputerOutput">Reg</span> is the register being used by a spill or defined for a restore/split during register allocation.</p>


<p>Declaration at line 892 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/codegen/machinebasicblock-h">MachineBasicBlock.h</a>, definition at line 227 of file <a href="/web-llvm/docs/api/files/lib/lib/codegen/machinebasicblock-cpp">MachineBasicBlock.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/silowercontrolflow-cpp/#a4868c5d81c5ccc98c47aeab6244346a0">assert</a>, <a href="#acbc921830578e2741be6549db716c0ce">end</a>, <a href="/web-llvm/docs/api/classes/llvm/targetsubtargetinfo/#acd858ed72f11db9444617740c3622608">llvm::TargetSubtargetInfo::getInstrInfo</a>, <a href="#acf6442108e21e7e5379feb8962de65b7">getParent</a>, <a href="/web-llvm/docs/api/classes/llvm/machinefunction/#a3825368aca2bc1550d173660df4da6a6">llvm::MachineFunction::getSubtarget</a>, <a href="/web-llvm/docs/api/files/lib/lib/support/md5-cpp/#ac0eafdc9ee161b71e7af98af736952fd">I</a> and <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/hexagon/hexagoncopytocombine-cpp/#a1d40004718218dbdf06b496766299101">TII</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/structs/anonymous-ppcearlyreturn-cpp-/ppcearlyreturn/#ae036500138a9ae1567af6b28547cf045">anonymous{PPCEarlyReturn.cpp}::PPCEarlyReturn::processBlock</a> and <a href="/web-llvm/docs/api/classes/anonymous-sifoldoperands-cpp-/sifoldoperandsimpl/#a17772fd1beeccd740ec6412abad098f9">anonymous{SIFoldOperands.cpp}::SIFoldOperandsImpl::tryFoldPhiAGPR</a>.</p>

</div>
</div>

### sortUniqueLiveIns() {#a9ff557f73ac8f2608369d70b3c73e525}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void MachineBasicBlock::sortUniqueLiveIns ()</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Sorts and uniques the LiveIns vector.</p>


<p>It can be significantly faster to do this than repeatedly calling isLiveIn before calling addLiveIn for every LiveIn insertion.</p>


<p>Declaration at line 476 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/codegen/machinebasicblock-h">MachineBasicBlock.h</a>, definition at line 624 of file <a href="/web-llvm/docs/api/files/lib/lib/codegen/machinebasicblock-cpp">MachineBasicBlock.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/files/lib/lib/support/md5-cpp/#ac0eafdc9ee161b71e7af98af736952fd">I</a>, <a href="/web-llvm/docs/api/structs/llvm/machinebasicblock/registermaskpair/#aec870716714bddabfc363a79a44a52ca">llvm::MachineBasicBlock::RegisterMaskPair::PhysReg</a> and <a href="/web-llvm/docs/api/namespaces/llvm/#a74cdbd1e4f731e7d7cd83461b8b1de0b">llvm::sort</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/classes/llvm/irtranslator/#a2fa3a523a1812aeda17891575f852ce9">llvm::IRTranslator::runOnMachineFunction</a>, <a href="/web-llvm/docs/api/files/lib/lib/codegen/machinesink-cpp/#a6c1da13a967ff01e9076c55b0b6d158c">updateLiveIn</a> and <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/silowersgprspills-cpp/#a0a2dffaa4ca0137aa854675d5a7c578d">updateLiveness</a>.</p>

</div>
</div>

### splice() {#adf0023bdc4f05a7849c35b1c859580d8}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void llvm::MachineBasicBlock::splice (<a href="#ae34c996b58df9b9ce6695a0c8b70c533">iterator</a> Where, <a href="/web-llvm/docs/api/classes/llvm/machinebasicblock">MachineBasicBlock</a> * Other, <a href="#ae34c996b58df9b9ce6695a0c8b70c533">iterator</a> From)</td>
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

<p>Take an instruction from MBB 'Other' at the position From, and insert it into this MBB right before 'Where'.</p>


<p>If From points to a bundle of instructions, the whole bundle is moved.</p>


<p>Definition at line 1118 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/codegen/machinebasicblock-h">MachineBasicBlock.h</a>.</p>


<p>References <a href="/web-llvm/docs/api/namespaces/llvm/#a9eb4f5b98b70ee4fab9614ed58282c1fa6311ae17c1ee52b36e68aaf4ad066387">llvm::Other</a> and <a href="#adf0023bdc4f05a7849c35b1c859580d8">splice</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/classes/llvm/ppctargetlowering/#a541b354a6386df6d03fcdc656d7d9db7">llvm::PPCTargetLowering::EmitAtomicBinary</a>, <a href="/web-llvm/docs/api/classes/llvm/riscvtargetlowering/#a7bafcec0aefe1c8144ce6cacdf80ff19">llvm::RISCVTargetLowering::emitDynamicProbedAlloc</a>, <a href="/web-llvm/docs/api/classes/llvm/ppctargetlowering/#a212384cdd746eaffedb7edc7a16a1cef">llvm::PPCTargetLowering::emitEHSjLjSetJmp</a>, <a href="/web-llvm/docs/api/classes/llvm/systemztargetlowering/#a2a8a6c3f5cf71d0e400566ee13c6e828">llvm::SystemZTargetLowering::emitEHSjLjSetJmp</a>, <a href="/web-llvm/docs/api/classes/llvm/vetargetlowering/#a9b01008eed371b3da0faa8604b91e828">llvm::VETargetLowering::emitEHSjLjSetJmp</a>, <a href="/web-llvm/docs/api/classes/llvm/aarch64targetlowering/#ab6a60676cdf39d45ae2ec66a7ea4aada">llvm::AArch64TargetLowering::EmitF128CSEL</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/riscv/riscvisellowering-cpp/#a90f911eb0622dc6ec5c1333369e495ac">emitFROUND</a>, <a href="/web-llvm/docs/api/classes/llvm/armtargetlowering/#a6820d09b4db5654cd1377d3ab63b3e01">llvm::ARMTargetLowering::EmitInstrWithCustomInserter</a>, <a href="/web-llvm/docs/api/classes/llvm/avrtargetlowering/#a336444d567b931e2ced0dd4f844148ab">llvm::AVRTargetLowering::EmitInstrWithCustomInserter</a>, <a href="/web-llvm/docs/api/classes/llvm/bpftargetlowering/#ac190f0cf5627568bd97cf1e5b24ce57d">llvm::BPFTargetLowering::EmitInstrWithCustomInserter</a>, <a href="/web-llvm/docs/api/classes/llvm/msp430targetlowering/#a948d164566e4b5aca48cf71cbf3a9ee3">llvm::MSP430TargetLowering::EmitInstrWithCustomInserter</a>, <a href="/web-llvm/docs/api/classes/llvm/ppctargetlowering/#a10d6f09e62a827099ec8b54efb4c035d">llvm::PPCTargetLowering::EmitInstrWithCustomInserter</a>, <a href="/web-llvm/docs/api/classes/llvm/xcoretargetlowering/#a13afdeda523046ab7176bead48d1c46f">llvm::XCoreTargetLowering::EmitInstrWithCustomInserter</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/riscv/riscvisellowering-cpp/#a4af8648d2e12301489dcc7b760f981ac">EmitLoweredCascadedSelect</a>, <a href="/web-llvm/docs/api/classes/llvm/ppctargetlowering/#a2e99e64e510ba34954d7fe85b1e30119">llvm::PPCTargetLowering::EmitPartwordAtomicBinary</a>, <a href="/web-llvm/docs/api/classes/llvm/ppctargetlowering/#a2cb46b1ded73af4c2924bd2d1d8db334">llvm::PPCTargetLowering::emitProbedAlloca</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/riscv/riscvisellowering-cpp/#ae20aef7ab8c13752bc5663fb0e6cbb1c">emitReadCounterWidePseudo</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/riscv/riscvisellowering-cpp/#a59f08a4b78badcbfff06545894a60e6e">emitSelectPseudo</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/csky/cskyisellowering-cpp/#a8e39c98d41d74a2147127a17c9800c7d">emitSelectPseudo</a>, <a href="/web-llvm/docs/api/classes/llvm/msp430targetlowering/#a33dd164bd4caf16d69db25a98f5d338f">llvm::MSP430TargetLowering::EmitShiftInstr</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/riscv/riscvframelowering-cpp/#a30a608df0c31b4ad3814cce66364082c">emitStackProbeInline</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/loongarch/loongarchisellowering-cpp/#accb97b288f5b7b78cc16845a383fc13c">emitVecCondBranchPseudo</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/x86/x86isellowering-cpp/#a13a9214d6e92afcb3e956a5891522bed">emitXBegin</a>, <a href="/web-llvm/docs/api/classes/llvm/amdgpuregisterbankinfo/#a533cd1035e03cdca3da433e98e77e430">llvm::AMDGPURegisterBankInfo::executeInWaterfallLoop</a>, <a href="/web-llvm/docs/api/classes/llvm/veinstrinfo/#ad99d6c93063cbfe0bf0f995a0cf12552">llvm::VEInstrInfo::expandExtendStackPseudo</a>, <a href="/web-llvm/docs/api/classes/llvm/sparctargetlowering/#a216c0fdb0cdd991dcf320bd42ff4c39e">llvm::SparcTargetLowering::expandSelectCC</a>, <a href="/web-llvm/docs/api/classes/llvm/ppcframelowering/#af0a5a3bd252aaac7b161ad8c01cf0951">llvm::PPCFrameLowering::inlineStackProbe</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/siinstrinfo-cpp/#af14ddf696e10f25864072cc0dc2e0161">loadMBUFScalarOperandsFromVGPR</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/webassembly/webassemblyisellowering-cpp/#a01bea37475bf9a1f853b90975dbf7605">LowerFPToInt</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/webassembly/webassemblyisellowering-cpp/#a1b22ed476a56f8583de43854dfe57830">LowerMemcpy</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/webassembly/webassemblyisellowering-cpp/#aa603afd757ff3057f96bf5c1ee83e8b2">LowerMemset</a>, <a href="/web-llvm/docs/api/classes/anonymous-r600machinecfgstructurizer-cpp-/r600machinecfgstructurizer/#a5fec9aab7a2ff820c3c372f3cda87c25">anonymous{R600MachineCFGStructurizer.cpp}::R600MachineCFGStructurizer::mergeSerialBlock</a>, <a href="/web-llvm/docs/api/classes/anonymous-r600machinecfgstructurizer-cpp-/r600machinecfgstructurizer/#a34b11aa12929fbf594b75074a35dc9c2">anonymous{R600MachineCFGStructurizer.cpp}::R600MachineCFGStructurizer::migrateInstruction</a>, <a href="/web-llvm/docs/api/classes/anonymous-ppcbranchcoalescing-cpp-/ppcbranchcoalescing/#a2a11298ee3a7cfcfa678f8b9a3df20db">anonymous{PPCBranchCoalescing.cpp}::PPCBranchCoalescing::moveAndUpdatePHIs</a>, <a href="/web-llvm/docs/api/classes/llvm/machineinstr/#afc00f43b2ea96bd57a1d9ceb316dccb7">llvm::MachineInstr::moveBefore</a>, <a href="/web-llvm/docs/api/classes/anonymous-hexagoncopyhoisting-cpp-/hexagoncopyhoisting/#a4fc59ce12e2dc07246561737f195c0c6">anonymous{HexagonCopyHoisting.cpp}::HexagonCopyHoisting::moveCopyInstr</a>, <a href="/web-llvm/docs/api/files/lib/lib/codegen/machinesink-cpp/#a1e64ed92fc7b343fa59c28105e16b794">performSink</a>, <a href="/web-llvm/docs/api/classes/llvm/aarch64instrinfo/#ab9deb47df6ac29c81422ae6b4bfd924d">llvm::AArch64InstrInfo::probedStackAlloc</a>, <a href="/web-llvm/docs/api/structs/anonymous-ppcearlyreturn-cpp-/ppcearlyreturn/#ae036500138a9ae1567af6b28547cf045">anonymous{PPCEarlyReturn.cpp}::PPCEarlyReturn::processBlock</a>, <a href="/web-llvm/docs/api/classes/anonymous-x86winfixupbuffersecuritycheck-cpp-/x86winfixupbuffersecuritycheckpass/#a72a62fe526ad0cd3c24cfe003d363df0">anonymous{X86WinFixupBufferSecurityCheck.cpp}::X86WinFixupBufferSecurityCheckPass::runOnMachineFunction</a>, <a href="/web-llvm/docs/api/classes/llvm/irtranslator/#a2fa3a523a1812aeda17891575f852ce9">llvm::IRTranslator::runOnMachineFunction</a>, <a href="/web-llvm/docs/api/classes/anonymous-hexagoninstrinfo-cpp-/hexagonpipelinerloopinfo/#af7f7f0f37193bf67ea9e1c7538388773">anonymous{HexagonInstrInfo.cpp}::HexagonPipelinerLoopInfo::setPreheader</a>, <a href="#adf0023bdc4f05a7849c35b1c859580d8">splice</a>, <a href="#ac0bfa894f538166cb476b439a2cb0aea">splitAt</a>, <a href="/web-llvm/docs/api/classes/anonymous-x86winfixupbuffersecuritycheck-cpp-/x86winfixupbuffersecuritycheckpass/#a4a9e94af76b18840bb6b75a873b41010">anonymous{X86WinFixupBufferSecurityCheck.cpp}::X86WinFixupBufferSecurityCheckPass::SplitBasicBlock</a>, <a href="/web-llvm/docs/api/namespaces/llvm/systemz/#a9f28b32cebb99746b65b07147c24d6cf">llvm::SystemZ::splitBlockAfter</a>, <a href="/web-llvm/docs/api/namespaces/llvm/systemz/#a175299250e6f7f5542fb5474ff0c9c6a">llvm::SystemZ::splitBlockBefore</a>, <a href="/web-llvm/docs/api/classes/anonymous-cskyconstantislandpass-cpp-/cskyconstantislands/#ae708a0dc9c80038ba6d971c94eb9db5c">anonymous{CSKYConstantIslandPass.cpp}::CSKYConstantIslands::splitBlockBeforeInstr</a>, <a href="/web-llvm/docs/api/classes/anonymous-mipsconstantislandpass-cpp-/mipsconstantislands/#a747abf73a79323919b62fb98e61aeaf2">anonymous{MipsConstantIslandPass.cpp}::MipsConstantIslands::splitBlockBeforeInstr</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/siisellowering-cpp/#ac24b8552572d60a9f8943c27199fb8b2">splitBlockForLoop</a> and <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/powerpc/ppcreducecrlogicals-cpp/#a6268a1294b61555b575fbd131789aaf3">splitMBB</a>.</p>

</div>
</div>

### splice() {#a78fb611836599b6138ba072712dcc315}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void llvm::MachineBasicBlock::splice (<a href="#ae34c996b58df9b9ce6695a0c8b70c533">iterator</a> Where, <a href="/web-llvm/docs/api/classes/llvm/machinebasicblock">MachineBasicBlock</a> * Other, <a href="#ae34c996b58df9b9ce6695a0c8b70c533">iterator</a> From, <a href="#ae34c996b58df9b9ce6695a0c8b70c533">iterator</a> To)</td>
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

<p>Take a block of instructions from MBB 'Other' in the range [From, To), and insert them into this MBB right before 'Where'.</p>


<p>The instruction at 'Where' must not be included in the range of instructions to move.</p>


<p>Definition at line 1129 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/codegen/machinebasicblock-h">MachineBasicBlock.h</a>.</p>


<p>References <a href="/web-llvm/docs/api/classes/llvm/machineinstrbundleiterator/#a897c4661275324674e38c41a52e7fc88">llvm::MachineInstrBundleIterator&lt; Ty, IsReverse &gt;::getInstrIterator</a> and <a href="/web-llvm/docs/api/namespaces/llvm/#a9eb4f5b98b70ee4fab9614ed58282c1fa6311ae17c1ee52b36e68aaf4ad066387">llvm::Other</a>.</p>

</div>
</div>

### splitAt() {#ac0bfa894f538166cb476b439a2cb0aea}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">MachineBasicBlock * MachineBasicBlock::splitAt (<a href="/web-llvm/docs/api/classes/llvm/machineinstr">MachineInstr</a> &amp; SplitInst, bool UpdateLiveIns=<a href="/web-llvm/docs/api/files/lib/lib/analysis/basicaliasanalysis-cpp/#af6d5cafbdfc5313e65d990120021a3ec">true</a>, <a href="/web-llvm/docs/api/classes/llvm/liveintervals">LiveIntervals</a> * LIS=nullptr)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Split a basic block into 2 pieces at <span class="doxyComputerOutput">SplitPoint</span>.</p>


<p>A new block will be inserted after this block, and all instructions after <span class="doxyComputerOutput">SplitInst</span> moved to it (<span class="doxyComputerOutput">SplitInst</span> will be in the original block). If <span class="doxyComputerOutput">LIS</span> is provided, <a href="/web-llvm/docs/api/classes/llvm/liveintervals">LiveIntervals</a> will be appropriately updated.</p>


<dl class="doxySectionUser">
<dt>Returns</dt>
<dd><p>the newly inserted block.</p></dd>
</dl>


<p>If <span class="doxyComputerOutput">UpdateLiveIns</span> is true, this will ensure the live ins list is accurate, including for physreg uses/defs in the original block.</p>


<p>Declaration at line 975 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/codegen/machinebasicblock-h">MachineBasicBlock.h</a>, definition at line 1025 of file <a href="/web-llvm/docs/api/files/lib/lib/codegen/machinebasicblock-cpp">MachineBasicBlock.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/namespaces/llvm/#af9a1ca470b2b9c8e97304f5be5448422">llvm::addLiveIns</a>, <a href="/web-llvm/docs/api/classes/llvm/livephysregs/#abb67d4b6f48395a5aca25fc32e042928">llvm::LivePhysRegs::addLiveOuts</a>, <a href="#a935e2a8884592189d8f261634a0b24c5">addSuccessor</a>, <a href="#ab2d91e7bec944efcbc39d8e30644f111">begin</a>, <a href="/web-llvm/docs/api/classes/llvm/machinefunction/#adfc62ee16549afaac5bde30156ddc989">llvm::MachineFunction::CreateMachineBasicBlock</a>, <a href="#acbc921830578e2741be6549db716c0ce">end</a>, <a href="#a4874816314c3308be0bf1e71de2078d8">getBasicBlock</a>, <a href="#acf6442108e21e7e5379feb8962de65b7">getParent</a>, <a href="/web-llvm/docs/api/classes/llvm/targetsubtargetinfo/#a43c530c830206ecf5ad3359364634c75">llvm::TargetSubtargetInfo::getRegisterInfo</a>, <a href="/web-llvm/docs/api/classes/llvm/machineinstrbundleiterator/#a13dd64c40d9f175e578ade3ef60ea351">llvm::MachineInstrBundleIterator&lt; Ty, IsReverse &gt;::getReverse</a>, <a href="/web-llvm/docs/api/classes/llvm/machinefunction/#a3825368aca2bc1550d173660df4da6a6">llvm::MachineFunction::getSubtarget</a>, <a href="/web-llvm/docs/api/files/lib/lib/support/md5-cpp/#ac0eafdc9ee161b71e7af98af736952fd">I</a>, <a href="/web-llvm/docs/api/classes/llvm/livephysregs/#a8b52495cd160fff98521b57a4479f2da">llvm::LivePhysRegs::init</a>, <a href="/web-llvm/docs/api/classes/llvm/machinefunction/#af4c0db6d503e0ba3b8e44067023ffbba">llvm::MachineFunction::insert</a>, <a href="/web-llvm/docs/api/classes/llvm/liveintervals/#a2b6f72816801c63516c4b25f3b6544b0">llvm::LiveIntervals::insertMBBInMaps</a>, <a href="#ac423fefe048ace18159808c5592ae74c">MachineFunction</a>, <a href="/web-llvm/docs/api/files/lib/lib/codegen/lib/codegen/globalisel/irtranslator-cpp/#abe44dfdea65b4f7e11e0a608ab708b76">MI</a>, <a href="#ad8c9657cfb03ef2ebf6364ba9d68c127">rbegin</a>, <a href="#adf0023bdc4f05a7849c35b1c859580d8">splice</a>, <a href="/web-llvm/docs/api/classes/llvm/livephysregs/#a683d33b7b0ca1cf29e61a3dc4614a046">llvm::LivePhysRegs::stepBackward</a> and <a href="#a046a35e36c4c1206711ea82ee9cb6d72">transferSuccessorsAndUpdatePHIs</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/classes/llvm/armtargetlowering/#a6820d09b4db5654cd1377d3ab63b3e01">llvm::ARMTargetLowering::EmitInstrWithCustomInserter</a>, <a href="/web-llvm/docs/api/classes/llvm/sitargetlowering/#a92bd7eb8dcbdfa0341a4fe88a09941da">llvm::SITargetLowering::EmitInstrWithCustomInserter</a>, <a href="/web-llvm/docs/api/classes/llvm/amdgpulegalizerinfo/#aff7dfc9d1d4355acbd741d76ce27fca1">llvm::AMDGPULegalizerInfo::legalizeTrapEndpgm</a> and <a href="/web-llvm/docs/api/classes/llvm/sitargetlowering/#a8b55d1aa92c4d9f17904aa2c9d7c79a3">llvm::SITargetLowering::splitKillBlock</a>.</p>

</div>
</div>

### SplitCriticalEdge() {#a324e3327b26396f39229654c107601d8}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">MachineBasicBlock * llvm::MachineBasicBlock::SplitCriticalEdge (<a href="/web-llvm/docs/api/classes/llvm/machinebasicblock">MachineBasicBlock</a> * Succ, <a href="/web-llvm/docs/api/classes/llvm/pass">Pass</a> &amp; P, std::vector&lt; <a href="/web-llvm/docs/api/classes/llvm/sparsebitvector">SparseBitVector</a>&lt;&gt; &gt; * LiveInSets=nullptr, <a href="/web-llvm/docs/api/classes/llvm/machinedomtreeupdater">MachineDomTreeUpdater</a> * MDTU=nullptr)</td>
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

<p>Split the critical edge from this block to the given successor block, and return the newly created block, or null if splitting is not possible.</p>


<p>This function updates <a href="/web-llvm/docs/api/classes/llvm/livevariables">LiveVariables</a>, <a href="/web-llvm/docs/api/classes/llvm/machinedominatortree">MachineDominatorTree</a>, and <a href="/web-llvm/docs/api/classes/llvm/machineloopinfo">MachineLoopInfo</a>, as applicable.</p>


<p>Definition at line 984 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/codegen/machinebasicblock-h">MachineBasicBlock.h</a>.</p>


<p>References <a href="/web-llvm/docs/api/files/lib/lib/option/option-cpp/#a04665169063c8ca1f2ea96c27fc7c2b2">P</a> and <a href="#a324e3327b26396f39229654c107601d8">SplitCriticalEdge</a>.</p>


<p>Referenced by <a href="#a9cf5c21c2ef38624a3ee3a12d21e76f0">SplitCriticalEdge</a> and <a href="#a324e3327b26396f39229654c107601d8">SplitCriticalEdge</a>.</p>

</div>
</div>

### SplitCriticalEdge() {#a9cf5c21c2ef38624a3ee3a12d21e76f0}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">MachineBasicBlock * llvm::MachineBasicBlock::SplitCriticalEdge (<a href="/web-llvm/docs/api/classes/llvm/machinebasicblock">MachineBasicBlock</a> * Succ, <a href="/web-llvm/docs/api/namespaces/llvm/#a064825a8817522ca733ac413a7122d36">MachineFunctionAnalysisManager</a> &amp; MFAM, std::vector&lt; <a href="/web-llvm/docs/api/classes/llvm/sparsebitvector">SparseBitVector</a>&lt;&gt; &gt; * LiveInSets=nullptr, <a href="/web-llvm/docs/api/classes/llvm/machinedomtreeupdater">MachineDomTreeUpdater</a> * MDTU=nullptr)</td>
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



<p>Definition at line 991 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/codegen/machinebasicblock-h">MachineBasicBlock.h</a>.</p>


<p>Reference <a href="#a324e3327b26396f39229654c107601d8">SplitCriticalEdge</a>.</p>

</div>
</div>

### SplitCriticalEdge() {#aa80aaa82844ab5560ece045eee7b34ac}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">MachineBasicBlock * MachineBasicBlock::SplitCriticalEdge (<a href="/web-llvm/docs/api/classes/llvm/machinebasicblock">MachineBasicBlock</a> * Succ, <a href="/web-llvm/docs/api/classes/llvm/pass">Pass</a> * P, <a href="/web-llvm/docs/api/namespaces/llvm/#a064825a8817522ca733ac413a7122d36">MachineFunctionAnalysisManager</a> * MFAM, std::vector&lt; <a href="/web-llvm/docs/api/classes/llvm/sparsebitvector">SparseBitVector</a>&lt;&gt; &gt; * LiveInSets, <a href="/web-llvm/docs/api/classes/llvm/machinedomtreeupdater">MachineDomTreeUpdater</a> * MDTU)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Declaration at line 999 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/codegen/machinebasicblock-h">MachineBasicBlock.h</a>, definition at line 1149 of file <a href="/web-llvm/docs/api/files/lib/lib/codegen/machinebasicblock-cpp">MachineBasicBlock.cpp</a>.</p>


<p>References <a href="#acce9c12cc977a88dc7bc51493ce7681c">addLiveIn</a>, <a href="/web-llvm/docs/api/classes/llvm/livevariables/#afbcff91139fc89e3e8c0dda857e7b128">llvm::LiveVariables::addNewBlock</a>, <a href="/web-llvm/docs/api/classes/llvm/liverange/#a0b73c8d5ae32ca13dd02ddde86ffd0a2">llvm::LiveRange::addSegment</a>, <a href="#a935e2a8884592189d8f261634a0b24c5">addSuccessor</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/silowercontrolflow-cpp/#a4868c5d81c5ccc98c47aeab6244346a0">assert</a>, <a href="#ae32dc74389a52cbb83e6a016274142f5">canSplitCriticalEdge</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/riscv/riscvredundantcopyelimination-cpp/#a193847098793cdbab306803186676899">Cond</a>, <a href="/web-llvm/docs/api/classes/llvm/smallset/#a2a98f19750ba941ce791b75ca6d77e48">llvm::SmallSet&lt; T, N, C &gt;::count</a>, <a href="/web-llvm/docs/api/classes/llvm/machinefunction/#adfc62ee16549afaac5bde30156ddc989">llvm::MachineFunction::CreateMachineBasicBlock</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a7c46c742c31be54870e2038048e6b391">llvm::dbgs</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/arm/armslshardening-cpp/#ad467c4ab9119043f9b7750ab986be61a">DL</a>, <a href="/web-llvm/docs/api/classes/llvm/smallvectortemplatecommon/#ad9a3c7bc26b130377bbafc170b5f88a2">llvm::SmallVectorTemplateCommon&lt; T, typename &gt;::empty</a>, <a href="#acbc921830578e2741be6549db716c0ce">end</a>, <a href="/web-llvm/docs/api/classes/llvm/machinefunction/#a9d017af749f76484cb9aec9ff6e4330c">llvm::MachineFunction::end</a>, <a href="#ad81901d0d8b768b240e78bf357999f34">findBranchDebugLoc</a>, <a href="/web-llvm/docs/api/files/lib/lib/codegen/machinebasicblock-cpp/#a8694d520d0ec389dfe12068c5039131c">findJumpTableIndex</a>, <a href="/web-llvm/docs/api/files/lib/lib/codegen/machinebasicblock-cpp/#a25976fc86125d38cce05518bf65c9792">GET_RESULT</a>, <a href="#ad661835c7f2b51fb3c5d826e77eafb93">getCallFrameSize</a>, <a href="/web-llvm/docs/api/classes/llvm/debugloc/#a98eca4d65070b40322af34cf08842d8c">llvm::DebugLoc::getCol</a>, <a href="#ad8c65b86ef286331d408a7a74c7b0b2f">getFirstInstrTerminator</a>, <a href="#a7f0521fa2de44271fd4b909ea7351ef3">getFirstTerminator</a>, <a href="/web-llvm/docs/api/classes/llvm/targetsubtargetinfo/#acd858ed72f11db9444617740c3622608">llvm::TargetSubtargetInfo::getInstrInfo</a>, <a href="/web-llvm/docs/api/classes/llvm/liveintervals/#a8208eacaf02c9742c8ed7f09ec0837f3">llvm::LiveIntervals::getInterval</a>, <a href="/web-llvm/docs/api/classes/llvm/machinefunction/#ad828deab7de3b5f4d03fac86e26adae9">llvm::MachineFunction::getJumpTableInfo</a>, <a href="/web-llvm/docs/api/classes/llvm/debugloc/#a427c256af834975c7869ad28fac00563">llvm::DebugLoc::getLine</a>, <a href="/web-llvm/docs/api/classes/llvm/slotindexes/#a662867d9274595cdac0092afa45888be">llvm::SlotIndexes::getMBBEndIdx</a>, <a href="/web-llvm/docs/api/classes/llvm/liveintervals/#a17bd0f1ec8263f735f29dd8840b7188f">llvm::LiveIntervals::getMBBStartIdx</a>, <a href="/web-llvm/docs/api/classes/llvm/ilist-node-with-parent/#a62ee7ece4986606d41363bc1f70d5ab2">llvm::ilist_node_with_parent&lt; MachineBasicBlock, MachineFunction &gt;::getNextNode</a>, <a href="#acf6442108e21e7e5379feb8962de65b7">getParent</a>, <a href="/web-llvm/docs/api/classes/llvm/slotindex/#ac832da130f4d71a4533a69d98315fb19">llvm::SlotIndex::getPrevSlot</a>, <a href="/web-llvm/docs/api/classes/llvm/machineoperand/#ac0035d7c1c860501c877c20e6e93297b">llvm::MachineOperand::getReg</a>, <a href="/web-llvm/docs/api/classes/llvm/machinefunction/#a810234b6b3d223b7c74a4253fcc5ea5e">llvm::MachineFunction::getRegInfo</a>, <a href="/web-llvm/docs/api/classes/llvm/targetsubtargetinfo/#a43c530c830206ecf5ad3359364634c75">llvm::TargetSubtargetInfo::getRegisterInfo</a>, <a href="/web-llvm/docs/api/classes/llvm/machinefunction/#a3825368aca2bc1550d173660df4da6a6">llvm::MachineFunction::getSubtarget</a>, <a href="/web-llvm/docs/api/classes/llvm/livevariables/#af73ca972d296b25a689a90fb5a0713f3">llvm::LiveVariables::getVarInfo</a>, <a href="/web-llvm/docs/api/classes/llvm/liverange/#afe7daa73e4cee4edb9f137a8008dfb73">llvm::LiveRange::getVNInfoAt</a>, <a href="/web-llvm/docs/api/classes/llvm/liveintervals/#a11cd70de340f310acc70781d57a00136">llvm::LiveIntervals::hasInterval</a>, <a href="/web-llvm/docs/api/files/lib/lib/support/md5-cpp/#ac0eafdc9ee161b71e7af98af736952fd">I</a>, <a href="/web-llvm/docs/api/classes/llvm/register/#a1979c563289f871907832e419889f979">llvm::Register::index2VirtReg</a>, <a href="/web-llvm/docs/api/classes/llvm/machinefunction/#af4c0db6d503e0ba3b8e44067023ffbba">llvm::MachineFunction::insert</a>, <a href="/web-llvm/docs/api/classes/llvm/smallset/#afcadfef2cf37c3e6dbdbc9cd7bea50a0">llvm::SmallSet&lt; T, N, C &gt;::insert</a>, <a href="/web-llvm/docs/api/classes/llvm/liveintervals/#a2b6f72816801c63516c4b25f3b6544b0">llvm::LiveIntervals::insertMBBInMaps</a>, <a href="/web-llvm/docs/api/classes/llvm/slotindexes/#a55bd6e17074a39a9aad2ee8cd6f541fb">llvm::SlotIndexes::insertMBBInMaps</a>, <a href="#a172e7bd9150eb0519ef04c796086f93d">instr_begin</a>, <a href="#acae72f6ab1071b7ec87b741a8bef582b">instr_end</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#acd1cd968cb420c82d70926920fcdc7d7">llvm::is_contained</a>, <a href="#abd85c9d7c51eb515a550069e9ad9445e">isLayoutSuccessor</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/sioptimizeexecmasking-cpp/#a9f2e59104ff29fd8ad0707fc4a1bac1f">isLiveOut</a>, <a href="/web-llvm/docs/api/classes/llvm/machineoperand/#a1255befbcd6e034394681b1bcd3529ff">llvm::MachineOperand::isUndef</a>, <a href="/web-llvm/docs/api/structs/llvm/livevariables/varinfo/#a65c816771eca7465f5e3e0bb6624ad88">llvm::LiveVariables::VarInfo::Kills</a>, <a href="/web-llvm/docs/api/classes/llvm/liverange/#a400c0b88110521ad1de258a7885d9038">llvm::LiveRange::liveAt</a>, <a href="#a364ed6e68f92f797c0cd9e53ce5ea2a5">liveins</a>, <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/support/debug-h/#a196897517069dda1bdb549e24468f7d7">LLVM_DEBUG</a>, <a href="#ac423fefe048ace18159808c5592ae74c">MachineFunction</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a341215803e83773a3e97860dc291f121">llvm::make_range</a>, <a href="/web-llvm/docs/api/files/lib/lib/codegen/lib/codegen/globalisel/irtranslator-cpp/#abe44dfdea65b4f7e11e0a608ab708b76">MI</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64advsimdscalarpass-cpp/#aacd2ab195054a3e6a74bfbb9d5d571c8">MRI</a>, <a href="/web-llvm/docs/api/files/lib/lib/option/option-cpp/#a04665169063c8ca1f2ea96c27fc7c2b2">P</a>, <a href="/web-llvm/docs/api/classes/llvm/smallvectorimpl/#a0c8ffe664a36e30d49c84d0aded2fe08">llvm::SmallVectorImpl&lt; T &gt;::pop_back_val</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#af7881286e3ea4d7f1c4a63c87c132dac">llvm::printMBBReference</a>, <a href="/web-llvm/docs/api/classes/llvm/smallvectortemplatebase/#af42bfbc067df27c19ee2fc859df58799">llvm::SmallVectorTemplateBase&lt; T, bool &gt;::push_back</a>, <a href="/web-llvm/docs/api/structs/llvm/livevariables/varinfo/#a1e808b535590177bb00545b77a324288">llvm::LiveVariables::VarInfo::removeKill</a>, <a href="/web-llvm/docs/api/classes/llvm/liverange/#ae8bd4b098d55a431c12cfba2a11c94bb">llvm::LiveRange::removeSegment</a>, <a href="/web-llvm/docs/api/classes/llvm/liveintervals/#a0d7e0d23a0453390a4c1e9a61afccdca">llvm::LiveIntervals::repairIntervalsInRange</a>, <a href="/web-llvm/docs/api/classes/llvm/machinejumptableinfo/#a729a069c6d2880c2c75148c61998c129">llvm::MachineJumpTableInfo::ReplaceMBBInJumpTable</a>, <a href="#a134a21189d056b81b80d0cdf01ef8c46">replacePhiUsesWith</a>, <a href="#ab9a54fdc7456ee97cb54ff30d625b6b7">ReplaceUsesOfBlockWith</a>, <a href="#a4472755d36621c5e2d056eec5056202e">setCallFrameSize</a>, <a href="/web-llvm/docs/api/classes/llvm/genericdomtreeupdater/#abb620d887e5e200028c5e0fb37f82592">llvm::GenericDomTreeUpdater&lt; DerivedT, DomTreeT, PostDomTreeT &gt;::splitCriticalEdge</a>, <a href="/web-llvm/docs/api/classes/llvm/liveinterval/#a9545a896d571165e9f43cf4b29a6d072">llvm::LiveInterval::subranges</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/hexagon/hexagoncopytocombine-cpp/#a1d40004718218dbdf06b496766299101">TII</a>, <a href="/web-llvm/docs/api/files/lib/lib/codegen/machinesink-cpp/#a0f36ed1bc17fc1aa97fe291c439a0698">TRI</a> and <a href="#a5803a49facae20ca4b002dcba6f1d03e">updateTerminator</a>.</p>

</div>
</div>

### splitSuccessor() {#a4b43b969b3db9fc943b664738f62ca76}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void MachineBasicBlock::splitSuccessor (<a href="/web-llvm/docs/api/classes/llvm/machinebasicblock">MachineBasicBlock</a> * Old, <a href="/web-llvm/docs/api/classes/llvm/machinebasicblock">MachineBasicBlock</a> * New, bool NormalizeSuccProbs=false)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Split the old successor into old plus new and updates the probability info.</p>

<p>Declaration at line 808 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/codegen/machinebasicblock-h">MachineBasicBlock.h</a>, definition at line 817 of file <a href="/web-llvm/docs/api/files/lib/lib/codegen/machinebasicblock-cpp">MachineBasicBlock.cpp</a>.</p>


<p>References <a href="#a935e2a8884592189d8f261634a0b24c5">addSuccessor</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/silowercontrolflow-cpp/#a4868c5d81c5ccc98c47aeab6244346a0">assert</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a086e9fbdb06276db7753101a08a63adf">llvm::find</a>, <a href="/web-llvm/docs/api/classes/llvm/branchprobability/#a76e4454abb329dee28e8f525ddd1a210">llvm::BranchProbability::getUnknown</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#acd1cd968cb420c82d70926920fcdc7d7">llvm::is_contained</a>, <a href="#a0c54da24de983d197068425e718fb607">normalizeSuccProbs</a>, <a href="#a3ddd708642d60c1661992ff8ba1b215d">succ_end</a> and <a href="#ad88ff1529541fb4e243cc8ed90b11131">successors</a>.</p>

</div>
</div>

### succ\_begin() {#a6321b189ea8fd5058663f8a87d6c23e9}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">succ_iterator llvm::MachineBasicBlock::succ_begin ()</td>
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



<p>Definition at line 430 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/codegen/machinebasicblock-h">MachineBasicBlock.h</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/classes/anonymous-hexagoncopyhoisting-cpp-/hexagoncopyhoisting/#a11effd5d22384daab26c5045ecff2e5b">anonymous{HexagonCopyHoisting.cpp}::HexagonCopyHoisting::analyzeCopy</a>, <a href="/web-llvm/docs/api/classes/llvm/ssaupdatertraits-4e613f36227a2a352217431a8f1958cd/#a74d9ee2bf0883c64efbd9ec44d267599">llvm::SSAUpdaterTraits&lt; MachineSSAUpdater &gt;::BlkSucc_begin</a>, <a href="/web-llvm/docs/api/classes/anonymous-earlyifconversion-cpp-/ssaifconv/#ad73f79350d54fe535469c4a148943e3a">anonymous{EarlyIfConversion.cpp}::SSAIfConv::canConvertIf</a>, <a href="/web-llvm/docs/api/namespaces/anonymous-basicblockpathcloning-cpp-/#a0150e86671c87ec3046e8ba46be9f151">anonymous{BasicBlockPathCloning.cpp}::CloneMachineBasicBlock</a>, <a href="/web-llvm/docs/api/classes/anonymous-r600machinecfgstructurizer-cpp-/r600machinecfgstructurizer/#ab90cb03c7501b031fa63735cc9391a5f">anonymous{R600MachineCFGStructurizer.cpp}::R600MachineCFGStructurizer::cloneOnSideEntryTo</a>, <a href="/web-llvm/docs/api/files/lib/lib/codegen/machineblockplacement-cpp/#a3d135a8abf70dc93455708cc087cc0b0">getLayoutSuccessorProbThreshold</a>, <a href="/web-llvm/docs/api/classes/anonymous-r600machinecfgstructurizer-cpp-/r600machinecfgstructurizer/#a3d20136077641cd8689ad93587230228">anonymous{R600MachineCFGStructurizer.cpp}::R600MachineCFGStructurizer::handleJumpintoIfImp</a>, <a href="/web-llvm/docs/api/classes/anonymous-r600machinecfgstructurizer-cpp-/r600machinecfgstructurizer/#a55b3f01e91f974764d18a95d9e4b7ec5">anonymous{R600MachineCFGStructurizer.cpp}::R600MachineCFGStructurizer::ifPatternMatch</a>, <a href="/web-llvm/docs/api/classes/llvm/machinebasicblock/liveout-iterator/#a22178f2b34888fe05c10d9ff241a5172">llvm::MachineBasicBlock::liveout_iterator::liveout_iterator</a>, <a href="/web-llvm/docs/api/files/lib/lib/codegen/shrinkwrap-cpp/#a0c3bc0926778b155544ae7c190921f4e">markAllReachable</a>, <a href="#a5a4302f4590a281bb84e08b30c80591c">print</a>, <a href="#a2d4703c258359175d1c7840735bd77b6">replaceSuccessor</a>, <a href="/web-llvm/docs/api/classes/llvm/irtranslator/#a2fa3a523a1812aeda17891575f852ce9">llvm::IRTranslator::runOnMachineFunction</a>, <a href="/web-llvm/docs/api/classes/llvm/mirprofileloader/#a31f2c5f323ca8742d0588171e0c33b49">llvm::MIRProfileLoader::setBranchProbs</a>, <a href="/web-llvm/docs/api/classes/anonymous-r600machinecfgstructurizer-cpp-/r600machinecfgstructurizer/#ac393ff87a496a67dae4ba9430b816263">anonymous{R600MachineCFGStructurizer.cpp}::R600MachineCFGStructurizer::singlePathTo</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/powerpc/ppcreducecrlogicals-cpp/#a6268a1294b61555b575fbd131789aaf3">splitMBB</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#ab7cceb7f324454419d509ed7ac651132">llvm::succ_begin</a>, <a href="#ad88ff1529541fb4e243cc8ed90b11131">successors</a>, <a href="#acce99554f41c0ba0f161102672722e4c">successors</a>, <a href="#a31e57b158a17c459f0dc34b0e602ecc6">transferSuccessors</a> and <a href="#a046a35e36c4c1206711ea82ee9cb6d72">transferSuccessorsAndUpdatePHIs</a>.</p>

</div>
</div>

### succ\_begin() {#a52fd67628cdf00fadc23e1953a20c2ca}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">const_succ_iterator llvm::MachineBasicBlock::succ_begin ()</td>
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



<p>Definition at line 431 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/codegen/machinebasicblock-h">MachineBasicBlock.h</a>.</p>

</div>
</div>

### succ\_empty() {#aa8d1d8d88835b75b05b14ab774785e8a}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool llvm::MachineBasicBlock::succ_empty ()</td>
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



<p>Definition at line 445 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/codegen/machinebasicblock-h">MachineBasicBlock.h</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/classes/anonymous-silowersgprspills-cpp-/silowersgprspills/#a5647b98ce7f0b4ad6fedc71a993e9979">anonymous{SILowerSGPRSpills.cpp}::SILowerSGPRSpills::calculateSaveRestoreBlocks</a>, <a href="/web-llvm/docs/api/classes/llvm/sitargetlowering/#a92bd7eb8dcbdfa0341a4fe88a09941da">llvm::SITargetLowering::EmitInstrWithCustomInserter</a>, <a href="#af80cc22ae7f226a8c819be6bf9e731d4">getEndClobberMask</a>, <a href="/web-llvm/docs/api/classes/anonymous-r600machinecfgstructurizer-cpp-/r600machinecfgstructurizer/#a55b3f01e91f974764d18a95d9e4b7ec5">anonymous{R600MachineCFGStructurizer.cpp}::R600MachineCFGStructurizer::ifPatternMatch</a>, <a href="/web-llvm/docs/api/classes/anonymous-r600machinecfgstructurizer-cpp-/r600machinecfgstructurizer/#a34c501f2f094f555ee3dbe0a1970d300">anonymous{R600MachineCFGStructurizer.cpp}::R600MachineCFGStructurizer::isSameloopDetachedContbreak</a>, <a href="/web-llvm/docs/api/classes/llvm/amdgpulegalizerinfo/#aff7dfc9d1d4355acbd741d76ce27fca1">llvm::AMDGPULegalizerInfo::legalizeTrapEndpgm</a>, <a href="/web-llvm/docs/api/classes/anonymous-r600machinecfgstructurizer-cpp-/r600machinecfgstructurizer/#aa76d1bb8a35c5fe0c9c22df9cc0dba10">anonymous{R600MachineCFGStructurizer.cpp}::R600MachineCFGStructurizer::mergeIfthenelseBlock</a>, <a href="#a5a4302f4590a281bb84e08b30c80591c">print</a>, <a href="/web-llvm/docs/api/classes/anonymous-r600machinecfgstructurizer-cpp-/r600machinecfgstructurizer/#a5e759f21490690f9162f74e250d73857">anonymous{R600MachineCFGStructurizer.cpp}::R600MachineCFGStructurizer::run</a>, <a href="#a31e57b158a17c459f0dc34b0e602ecc6">transferSuccessors</a>, <a href="#a046a35e36c4c1206711ea82ee9cb6d72">transferSuccessorsAndUpdatePHIs</a>, <a href="/web-llvm/docs/api/namespaces/anonymous-aarch64prelegalizercombiner-cpp-/#af6dea6ab7fff2717e5813f576518e4f2">anonymous{AArch64PreLegalizerCombiner.cpp}::tryToSimplifyUADDO</a> and <a href="#a5803a49facae20ca4b002dcba6f1d03e">updateTerminator</a>.</p>

</div>
</div>

### succ\_end() {#a3ddd708642d60c1661992ff8ba1b215d}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">succ_iterator llvm::MachineBasicBlock::succ_end ()</td>
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



<p>Definition at line 432 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/codegen/machinebasicblock-h">MachineBasicBlock.h</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/classes/llvm/ssaupdatertraits-4e613f36227a2a352217431a8f1958cd/#a784a8e97960198712e1da4efd0e05553">llvm::SSAUpdaterTraits&lt; MachineSSAUpdater &gt;::BlkSucc_end</a>, <a href="/web-llvm/docs/api/classes/anonymous-sipreemitpeephole-cpp-/branchweightcostmodel/#aa842d0e2dfc3a19e513d9098c7e4d00e">anonymous{SIPreEmitPeephole.cpp}::BranchWeightCostModel::BranchWeightCostModel</a>, <a href="/web-llvm/docs/api/namespaces/anonymous-basicblockpathcloning-cpp-/#a0150e86671c87ec3046e8ba46be9f151">anonymous{BasicBlockPathCloning.cpp}::CloneMachineBasicBlock</a>, <a href="/web-llvm/docs/api/classes/llvm/machinebasicblock/liveout-iterator/#a22178f2b34888fe05c10d9ff241a5172">llvm::MachineBasicBlock::liveout_iterator::liveout_iterator</a>, <a href="/web-llvm/docs/api/files/lib/lib/codegen/shrinkwrap-cpp/#a0c3bc0926778b155544ae7c190921f4e">markAllReachable</a>, <a href="#a5a4302f4590a281bb84e08b30c80591c">print</a>, <a href="#a2d4703c258359175d1c7840735bd77b6">replaceSuccessor</a>, <a href="/web-llvm/docs/api/classes/llvm/mirprofileloader/#a31f2c5f323ca8742d0588171e0c33b49">llvm::MIRProfileLoader::setBranchProbs</a>, <a href="#a4b43b969b3db9fc943b664738f62ca76">splitSuccessor</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#ab9de1bba228fdc8f9c7a68a132e458cf">llvm::succ_end</a>, <a href="#ad88ff1529541fb4e243cc8ed90b11131">successors</a> and <a href="#acce99554f41c0ba0f161102672722e4c">successors</a>.</p>

</div>
</div>

### succ\_end() {#aa7702db38b77b6d8db4b414105a7b6b7}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">const_succ_iterator llvm::MachineBasicBlock::succ_end ()</td>
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



<p>Definition at line 433 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/codegen/machinebasicblock-h">MachineBasicBlock.h</a>.</p>

</div>
</div>

### succ\_rbegin() {#abd32ea34faf1cde285a1b8daccd9c167}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">succ_reverse_iterator llvm::MachineBasicBlock::succ_rbegin ()</td>
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



<p>Definition at line 434 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/codegen/machinebasicblock-h">MachineBasicBlock.h</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/powerpc/ppcreducecrlogicals-cpp/#a6268a1294b61555b575fbd131789aaf3">splitMBB</a>.</p>

</div>
</div>

### succ\_rbegin() {#a539c706b56554cf14a09b2a1124d7788}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">const_succ_reverse_iterator llvm::MachineBasicBlock::succ_rbegin ()</td>
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



<p>Definition at line 436 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/codegen/machinebasicblock-h">MachineBasicBlock.h</a>.</p>

</div>
</div>

### succ\_rend() {#af3e547707a23a2e668d56a85f8482d70}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">succ_reverse_iterator llvm::MachineBasicBlock::succ_rend ()</td>
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



<p>Definition at line 438 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/codegen/machinebasicblock-h">MachineBasicBlock.h</a>.</p>

</div>
</div>

### succ\_rend() {#ace984d6e8836a03f99cf5bcb9dfa791d}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">const_succ_reverse_iterator llvm::MachineBasicBlock::succ_rend ()</td>
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



<p>Definition at line 440 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/codegen/machinebasicblock-h">MachineBasicBlock.h</a>.</p>

</div>
</div>

### succ\_size() {#a81626de817a0cb021ff8e915cf1942ed}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">unsigned llvm::MachineBasicBlock::succ_size ()</td>
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



<p>Definition at line 442 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/codegen/machinebasicblock-h">MachineBasicBlock.h</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/classes/anonymous-hexagoncopyhoisting-cpp-/hexagoncopyhoisting/#a11effd5d22384daab26c5045ecff2e5b">anonymous{HexagonCopyHoisting.cpp}::HexagonCopyHoisting::analyzeCopy</a>, <a href="/web-llvm/docs/api/classes/anonymous-aarch64conditionalcompares-cpp-/ssaccmpconv/#a545b0c16154dffb0ddba86968d798e2f">anonymous{AArch64ConditionalCompares.cpp}::SSACCmpConv::canConvert</a>, <a href="/web-llvm/docs/api/classes/anonymous-earlyifconversion-cpp-/ssaifconv/#ad73f79350d54fe535469c4a148943e3a">anonymous{EarlyIfConversion.cpp}::SSAIfConv::canConvertIf</a>, <a href="/web-llvm/docs/api/classes/llvm/tailduplicator/#a8fffb36a3e1523ff3d26521f27c02df8">llvm::TailDuplicator::canTailDuplicate</a>, <a href="/web-llvm/docs/api/classes/anonymous-r600machinecfgstructurizer-cpp-/r600machinecfgstructurizer/#ab90cb03c7501b031fa63735cc9391a5f">anonymous{R600MachineCFGStructurizer.cpp}::R600MachineCFGStructurizer::cloneOnSideEntryTo</a>, <a href="/web-llvm/docs/api/files/lib/lib/codegen/machineblockplacement-cpp/#a3d135a8abf70dc93455708cc087cc0b0">getLayoutSuccessorProbThreshold</a>, <a href="/web-llvm/docs/api/structs/llvm/regiontraits-c2500bb2a5b69b206350ed65636c42b7/#afd75993d466f0ac90b53ad1aff1d59bb">llvm::RegionTraits&lt; MachineFunction &gt;::getNumSuccessors</a>, <a href="#a34b15764a81fb89e68d85d5aae76f20f">getSuccProbability</a>, <a href="/web-llvm/docs/api/classes/anonymous-r600machinecfgstructurizer-cpp-/r600machinecfgstructurizer/#a3d20136077641cd8689ad93587230228">anonymous{R600MachineCFGStructurizer.cpp}::R600MachineCFGStructurizer::handleJumpintoIfImp</a>, <a href="/web-llvm/docs/api/files/lib/lib/codegen/machineblockplacement-cpp/#ab20068697df3d13ab12e09852d99b7f7">hasSameSuccessors</a>, <a href="/web-llvm/docs/api/classes/anonymous-r600machinecfgstructurizer-cpp-/r600machinecfgstructurizer/#a55b3f01e91f974764d18a95d9e4b7ec5">anonymous{R600MachineCFGStructurizer.cpp}::R600MachineCFGStructurizer::ifPatternMatch</a>, <a href="/web-llvm/docs/api/classes/anonymous-r600machinecfgstructurizer-cpp-/r600machinecfgstructurizer/#ae27fd47ee099b4aba7fe2bc84be97ff8">anonymous{R600MachineCFGStructurizer.cpp}::R600MachineCFGStructurizer::improveSimpleJumpintoIf</a>, <a href="/web-llvm/docs/api/classes/llvm/tailduplicator/#a22b5f49c33bc7b11d150556b0ee1ca0a">llvm::TailDuplicator::isSimpleBB</a>, <a href="/web-llvm/docs/api/classes/anonymous-r600machinecfgstructurizer-cpp-/r600machinecfgstructurizer/#aa76d1bb8a35c5fe0c9c22df9cc0dba10">anonymous{R600MachineCFGStructurizer.cpp}::R600MachineCFGStructurizer::mergeIfthenelseBlock</a>, <a href="/web-llvm/docs/api/namespaces/llvm/rdf/#aefd178f993c25ba2221f325e426e973d">llvm::rdf::operator&lt;&lt;</a>, <a href="/web-llvm/docs/api/classes/anonymous-aarch64redundantcopyelimination-cpp-/aarch64redundantcopyelimination/#a1ee0cfcd17ed3a5b4826b8a5f93e50e1">anonymous{AArch64RedundantCopyElimination.cpp}::AArch64RedundantCopyElimination::optimizeBlock</a>, <a href="/web-llvm/docs/api/files/lib/lib/codegen/branchfolding-cpp/#a905140abedaee343fc7ef33707052792">ProfitableToMerge</a>, <a href="/web-llvm/docs/api/classes/anonymous-hexagoncfgoptimizer-cpp-/hexagoncfgoptimizer/#a44a6c0917383ba77dca7325a7b23c252">anonymous{HexagonCFGOptimizer.cpp}::HexagonCFGOptimizer::runOnMachineFunction</a>, <a href="/web-llvm/docs/api/files/lib/lib/codegen/branchfolding-cpp/#a3fb0794be53f8c8e93e76861075a9a8a">salvageDebugInfoFromEmptyBlock</a>, <a href="/web-llvm/docs/api/classes/llvm/mirprofileloader/#a31f2c5f323ca8742d0588171e0c33b49">llvm::MIRProfileLoader::setBranchProbs</a>, <a href="/web-llvm/docs/api/classes/llvm/tailduplicator/#aa7dba30d4d9162f00367404e06085391">llvm::TailDuplicator::shouldTailDuplicate</a>, <a href="/web-llvm/docs/api/classes/anonymous-r600machinecfgstructurizer-cpp-/r600machinecfgstructurizer/#ac393ff87a496a67dae4ba9430b816263">anonymous{R600MachineCFGStructurizer.cpp}::R600MachineCFGStructurizer::singlePathTo</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/powerpc/ppcreducecrlogicals-cpp/#a6268a1294b61555b575fbd131789aaf3">splitMBB</a> and <a href="/web-llvm/docs/api/namespaces/llvm/#a85da2bdebeeed0bf7fdccfdfc5f1b92c">llvm::succ_size</a>.</p>

</div>
</div>

### successors() {#ad88ff1529541fb4e243cc8ed90b11131}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">iterator_range&lt; succ_iterator &gt; llvm::MachineBasicBlock::successors ()</td>
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



<p>Definition at line 453 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/codegen/machinebasicblock-h">MachineBasicBlock.h</a>.</p>


<p>References <a href="/web-llvm/docs/api/namespaces/llvm/#a341215803e83773a3e97860dc291f121">llvm::make_range</a>, <a href="#a6321b189ea8fd5058663f8a87d6c23e9">succ_begin</a> and <a href="#a3ddd708642d60c1661992ff8ba1b215d">succ_end</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/classes/anonymous-hexagoncopyhoisting-cpp-/hexagoncopyhoisting/#a11effd5d22384daab26c5045ecff2e5b">anonymous{HexagonCopyHoisting.cpp}::HexagonCopyHoisting::analyzeCopy</a>, <a href="/web-llvm/docs/api/classes/anonymous-sipreemitpeephole-cpp-/branchweightcostmodel/#aa842d0e2dfc3a19e513d9098c7e4d00e">anonymous{SIPreEmitPeephole.cpp}::BranchWeightCostModel::BranchWeightCostModel</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/amdgpusetwavepriority-cpp/#a78255db8421a0c6e709e8f8d42b1c648">CanLowerPriorityDirectlyInPredecessors</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/m68k/m68kisellowering-cpp/#aed8bb289e710a4687f5dbdc1b0b35fd3">checkAndUpdateCCRKill</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/arm/armisellowering-cpp/#a551cf4f2a46a96b347d222acc8df059c">checkAndUpdateCPSRKill</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/x86/x86cmovconversion-cpp/#a84a6f842d324111ba3e11e8b0e547801">checkEFLAGSLive</a>, <a href="/web-llvm/docs/api/classes/anonymous-r600machinecfgstructurizer-cpp-/r600machinecfgstructurizer/#a1e5698213d6d250e814ed909311751be">anonymous{R600MachineCFGStructurizer.cpp}::R600MachineCFGStructurizer::cloneSuccessorList</a>, <a href="/web-llvm/docs/api/files/lib/lib/codegen/analysis-cpp/#a86959c09e02e571589af525c983cdf4e">collectEHScopeMembers</a>, <a href="/web-llvm/docs/api/classes/anonymous-sioptimizevgprliverange-cpp-/sioptimizevgprliverange/#ab47a3d3cac0564876929e77389dbe569">anonymous{SIOptimizeVGPRLiveRange.cpp}::SIOptimizeVGPRLiveRange::collectWaterfallCandidateRegisters</a>, <a href="#a7ebfe0cc2f78ae5f27e1944412606973">computeRegisterLiveness</a>, <a href="/web-llvm/docs/api/files/lib/lib/codegen/branchfolding-cpp/#a22558d7c3b0ce9b0075ea086c1d3749d">findFalseBlock</a>, <a href="/web-llvm/docs/api/files/lib/lib/codegen/ifconversion-cpp/#a22558d7c3b0ce9b0075ea086c1d3749d">findFalseBlock</a>, <a href="/web-llvm/docs/api/classes/llvm/machineloopinfo/#a80b0e6e28849491c5b267be8ffc909b4">llvm::MachineLoopInfo::findLoopPreheader</a>, <a href="/web-llvm/docs/api/files/lib/lib/codegen/machinesink-cpp/#acf8fc7aec1c211309bcfdadf5471efc5">getSingleLiveInSuccBB</a>, <a href="/web-llvm/docs/api/structs/llvm/afdo-detail/irtraits-6a00974026f1163ef87516ae73fba13d/#a92f58feb24c5cecfc536df5db9e7f2c9">llvm::afdo_detail::IRTraits&lt; MachineBasicBlock &gt;::getSuccessors</a>, <a href="#a07ccfc69389d4e9657d22698f4a7ef46">hasEHPadSuccessor</a>, <a href="/web-llvm/docs/api/files/lib/lib/codegen/machineblockplacement-cpp/#ab20068697df3d13ab12e09852d99b7f7">hasSameSuccessors</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/x86/x86isellowering-cpp/#af10cf44c8132db33091188f9530e9dee">isEFLAGSLiveAfter</a>, <a href="#adc8f1be4a77ae671ac139d5f06b44deb">isSuccessor</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/siinstrinfo-cpp/#af14ddf696e10f25864072cc0dc2e0161">loadMBUFScalarOperandsFromVGPR</a>, <a href="#aefb323794dab5bb00d738a3f32dd65e6">mayHaveInlineAsmBr</a>, <a href="/web-llvm/docs/api/classes/anonymous-hexagoncopyhoisting-cpp-/hexagoncopyhoisting/#a4fc59ce12e2dc07246561737f195c0c6">anonymous{HexagonCopyHoisting.cpp}::HexagonCopyHoisting::moveCopyInstr</a>, <a href="/web-llvm/docs/api/namespaces/llvm/rdf/#aefd178f993c25ba2221f325e426e973d">llvm::rdf::operator&lt;&lt;</a>, <a href="/web-llvm/docs/api/classes/llvm/x86instrinfo/#a08a488100b4cc4464d879a987e490915">llvm::X86InstrInfo::optimizeCompareInstr</a>, <a href="/web-llvm/docs/api/classes/llvm/liveintervals/#a94cf1c59ca73ea330872deb639013cb9">llvm::LiveIntervals::pruneValue</a>, <a href="/web-llvm/docs/api/classes/anonymous-x86flagscopylowering-cpp-/x86flagscopyloweringpass/#a30d90e84a3faa0cd7aa2c3b96d65c232">anonymous{X86FlagsCopyLowering.cpp}::X86FlagsCopyLoweringPass::runOnMachineFunction</a>, <a href="/web-llvm/docs/api/classes/llvm/mirprofileloader/#a31f2c5f323ca8742d0588171e0c33b49">llvm::MIRProfileLoader::setBranchProbs</a>, <a href="/web-llvm/docs/api/classes/llvm/tailduplicator/#aa7dba30d4d9162f00367404e06085391">llvm::TailDuplicator::shouldTailDuplicate</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/silatebranchlowering-cpp/#a93b418512ed9bd239b221724374df852">splitBlock</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/powerpc/ppcreducecrlogicals-cpp/#a6268a1294b61555b575fbd131789aaf3">splitMBB</a>, <a href="#a4b43b969b3db9fc943b664738f62ca76">splitSuccessor</a>, <a href="/web-llvm/docs/api/classes/llvm/aggressiveantidepbreaker/#abd095bb58a0243946704d20d3559d420">llvm::AggressiveAntiDepBreaker::StartBlock</a>, <a href="/web-llvm/docs/api/classes/llvm/criticalantidepbreaker/#adb4573a84f25279673e3906914132a39">llvm::CriticalAntiDepBreaker::StartBlock</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a26e2a938b431eaa6eca2beaa96410c9d">llvm::successors</a>, <a href="#a703ba58bd58d60cd76ad205dda1634eb">terminatorIsComputedGoto</a>, <a href="/web-llvm/docs/api/classes/llvm/looptraversal/#a87cd9704fc800af5dddb87f26badfb3a">llvm::LoopTraversal::traverse</a>, <a href="/web-llvm/docs/api/files/lib/lib/codegen/prologepiloginserter-cpp/#ab462c5bbf745633740ccfb2920040000">updateLiveness</a> and <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/arm/armlowoverheadloops-cpp/#a5d85b8fd4787153b0ade229c616b7562">ValidateMVEStore</a>.</p>

</div>
</div>

### successors() {#acce99554f41c0ba0f161102672722e4c}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">iterator_range&lt; const_succ_iterator &gt; llvm::MachineBasicBlock::successors ()</td>
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



<p>Definition at line 456 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/codegen/machinebasicblock-h">MachineBasicBlock.h</a>.</p>


<p>References <a href="/web-llvm/docs/api/namespaces/llvm/#a341215803e83773a3e97860dc291f121">llvm::make_range</a>, <a href="#a6321b189ea8fd5058663f8a87d6c23e9">succ_begin</a> and <a href="#a3ddd708642d60c1661992ff8ba1b215d">succ_end</a>.</p>

</div>
</div>

### terminatorIsComputedGoto() {#a703ba58bd58d60cd76ad205dda1634eb}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool llvm::MachineBasicBlock::terminatorIsComputedGoto ()</td>
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

<p>Returns true if the original IR terminator is an <span class="doxyComputerOutput">indirectbr</span>.</p>


<p>This typically corresponds to a <span class="doxyComputerOutput">goto</span> in C, rather than jump tables.</p>


<p>Definition at line 316 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/codegen/machinebasicblock-h">MachineBasicBlock.h</a>.</p>


<p>References <a href="/web-llvm/docs/api/namespaces/llvm/#a0d10fe510ced2849a8074fe81e5d04ce">llvm::all_of</a>, <a href="#acf35424231192c6b4a3e22d711f50b1e">back</a>, <a href="/web-llvm/docs/api/classes/llvm/machineinstr/#a19ce3659ba05d62794e306f6d070a850">llvm::MachineInstr::isIndirectBranch</a>, <a href="#a753336faa16076c3931ae29c55f88f68">isIRBlockAddressTaken</a> and <a href="#ad88ff1529541fb4e243cc8ed90b11131">successors</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/classes/llvm/tailduplicator/#aa7dba30d4d9162f00367404e06085391">llvm::TailDuplicator::shouldTailDuplicate</a>.</p>

</div>
</div>

### terminators() {#ad56ff27a502cd519f9aaf5cc028b4ea5}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">iterator_range&lt; iterator &gt; llvm::MachineBasicBlock::terminators ()</td>
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



<p>Definition at line 384 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/codegen/machinebasicblock-h">MachineBasicBlock.h</a>.</p>


<p>References <a href="#acbc921830578e2741be6549db716c0ce">end</a>, <a href="#a7f0521fa2de44271fd4b909ea7351ef3">getFirstTerminator</a> and <a href="/web-llvm/docs/api/namespaces/llvm/#a341215803e83773a3e97860dc291f121">llvm::make_range</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/arm/mvetpandvptoptimisationspass-cpp/#a4aadfbe4795304e72a1a7be77ac88be7">findLoopComponents</a>, <a href="/web-llvm/docs/api/classes/anonymous-ppcbranchcoalescing-cpp-/ppcbranchcoalescing/#a072a336f973a3de4daa8fe16e5b4570f">anonymous{PPCBranchCoalescing.cpp}::PPCBranchCoalescing::mergeCandidates</a> and <a href="/web-llvm/docs/api/classes/llvm/armblockplacement/#aa13bb5e066b0419461ad1bbdd7bc9a1d">llvm::ARMBlockPlacement::moveBasicBlock</a>.</p>

</div>
</div>

### terminators() {#aadfc2f6425b15faff5ce2421cc708205}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">iterator_range&lt; const_iterator &gt; llvm::MachineBasicBlock::terminators ()</td>
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



<p>Definition at line 387 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/codegen/machinebasicblock-h">MachineBasicBlock.h</a>.</p>


<p>References <a href="#acbc921830578e2741be6549db716c0ce">end</a>, <a href="#a7f0521fa2de44271fd4b909ea7351ef3">getFirstTerminator</a> and <a href="/web-llvm/docs/api/namespaces/llvm/#a341215803e83773a3e97860dc291f121">llvm::make_range</a>.</p>

</div>
</div>

### transferSuccessors() {#a31e57b158a17c459f0dc34b0e602ecc6}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void MachineBasicBlock::transferSuccessors (<a href="/web-llvm/docs/api/classes/llvm/machinebasicblock">MachineBasicBlock</a> * FromMBB)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Transfers all the successors from MBB to this machine basic block (i.e., copies all the successors FromMBB and remove all the successors from FromMBB).</p>

<p>Declaration at line 814 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/codegen/machinebasicblock-h">MachineBasicBlock.h</a>, definition at line 917 of file <a href="/web-llvm/docs/api/files/lib/lib/codegen/machinebasicblock-cpp">MachineBasicBlock.cpp</a>.</p>


<p>References <a href="#a935e2a8884592189d8f261634a0b24c5">addSuccessor</a>, <a href="#a3f3061829632220504bb4a1cb819cfac">addSuccessorWithoutProb</a>, <a href="#aa7114bb360b922025e7a4fec442676db">removeSuccessor</a>, <a href="#a6321b189ea8fd5058663f8a87d6c23e9">succ_begin</a> and <a href="#aa8d1d8d88835b75b05b14ab774785e8a">succ_empty</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/classes/anonymous-cskyconstantislandpass-cpp-/cskyconstantislands/#ae708a0dc9c80038ba6d971c94eb9db5c">anonymous{CSKYConstantIslandPass.cpp}::CSKYConstantIslands::splitBlockBeforeInstr</a>, <a href="/web-llvm/docs/api/classes/anonymous-mipsconstantislandpass-cpp-/mipsconstantislands/#a747abf73a79323919b62fb98e61aeaf2">anonymous{MipsConstantIslandPass.cpp}::MipsConstantIslands::splitBlockBeforeInstr</a> and <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/powerpc/ppcreducecrlogicals-cpp/#a6268a1294b61555b575fbd131789aaf3">splitMBB</a>.</p>

</div>
</div>

### transferSuccessorsAndUpdatePHIs() {#a046a35e36c4c1206711ea82ee9cb6d72}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void MachineBasicBlock::transferSuccessorsAndUpdatePHIs (<a href="/web-llvm/docs/api/classes/llvm/machinebasicblock">MachineBasicBlock</a> * FromMBB)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Transfers all the successors, as in transferSuccessors, and update PHI operands in the successor blocks which refer to FromMBB to refer to this.</p>

<p>Declaration at line 818 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/codegen/machinebasicblock-h">MachineBasicBlock.h</a>, definition at line 937 of file <a href="/web-llvm/docs/api/files/lib/lib/codegen/machinebasicblock-cpp">MachineBasicBlock.cpp</a>.</p>


<p>References <a href="#a935e2a8884592189d8f261634a0b24c5">addSuccessor</a>, <a href="#a3f3061829632220504bb4a1cb819cfac">addSuccessorWithoutProb</a>, <a href="#a0c54da24de983d197068425e718fb607">normalizeSuccProbs</a>, <a href="#aa7114bb360b922025e7a4fec442676db">removeSuccessor</a>, <a href="#a134a21189d056b81b80d0cdf01ef8c46">replacePhiUsesWith</a>, <a href="#a6321b189ea8fd5058663f8a87d6c23e9">succ_begin</a> and <a href="#aa8d1d8d88835b75b05b14ab774785e8a">succ_empty</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/classes/llvm/ppctargetlowering/#a541b354a6386df6d03fcdc656d7d9db7">llvm::PPCTargetLowering::EmitAtomicBinary</a>, <a href="/web-llvm/docs/api/classes/llvm/riscvtargetlowering/#a7bafcec0aefe1c8144ce6cacdf80ff19">llvm::RISCVTargetLowering::emitDynamicProbedAlloc</a>, <a href="/web-llvm/docs/api/classes/llvm/ppctargetlowering/#a212384cdd746eaffedb7edc7a16a1cef">llvm::PPCTargetLowering::emitEHSjLjSetJmp</a>, <a href="/web-llvm/docs/api/classes/llvm/systemztargetlowering/#a2a8a6c3f5cf71d0e400566ee13c6e828">llvm::SystemZTargetLowering::emitEHSjLjSetJmp</a>, <a href="/web-llvm/docs/api/classes/llvm/vetargetlowering/#a9b01008eed371b3da0faa8604b91e828">llvm::VETargetLowering::emitEHSjLjSetJmp</a>, <a href="/web-llvm/docs/api/classes/llvm/aarch64targetlowering/#ab6a60676cdf39d45ae2ec66a7ea4aada">llvm::AArch64TargetLowering::EmitF128CSEL</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/riscv/riscvisellowering-cpp/#a90f911eb0622dc6ec5c1333369e495ac">emitFROUND</a>, <a href="/web-llvm/docs/api/classes/llvm/armtargetlowering/#a6820d09b4db5654cd1377d3ab63b3e01">llvm::ARMTargetLowering::EmitInstrWithCustomInserter</a>, <a href="/web-llvm/docs/api/classes/llvm/avrtargetlowering/#a336444d567b931e2ced0dd4f844148ab">llvm::AVRTargetLowering::EmitInstrWithCustomInserter</a>, <a href="/web-llvm/docs/api/classes/llvm/bpftargetlowering/#ac190f0cf5627568bd97cf1e5b24ce57d">llvm::BPFTargetLowering::EmitInstrWithCustomInserter</a>, <a href="/web-llvm/docs/api/classes/llvm/msp430targetlowering/#a948d164566e4b5aca48cf71cbf3a9ee3">llvm::MSP430TargetLowering::EmitInstrWithCustomInserter</a>, <a href="/web-llvm/docs/api/classes/llvm/ppctargetlowering/#a10d6f09e62a827099ec8b54efb4c035d">llvm::PPCTargetLowering::EmitInstrWithCustomInserter</a>, <a href="/web-llvm/docs/api/classes/llvm/xcoretargetlowering/#a13afdeda523046ab7176bead48d1c46f">llvm::XCoreTargetLowering::EmitInstrWithCustomInserter</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/riscv/riscvisellowering-cpp/#a4af8648d2e12301489dcc7b760f981ac">EmitLoweredCascadedSelect</a>, <a href="/web-llvm/docs/api/classes/llvm/ppctargetlowering/#a2e99e64e510ba34954d7fe85b1e30119">llvm::PPCTargetLowering::EmitPartwordAtomicBinary</a>, <a href="/web-llvm/docs/api/classes/llvm/ppctargetlowering/#a2cb46b1ded73af4c2924bd2d1d8db334">llvm::PPCTargetLowering::emitProbedAlloca</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/riscv/riscvisellowering-cpp/#ae20aef7ab8c13752bc5663fb0e6cbb1c">emitReadCounterWidePseudo</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/riscv/riscvisellowering-cpp/#a59f08a4b78badcbfff06545894a60e6e">emitSelectPseudo</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/csky/cskyisellowering-cpp/#a8e39c98d41d74a2147127a17c9800c7d">emitSelectPseudo</a>, <a href="/web-llvm/docs/api/classes/llvm/msp430targetlowering/#a33dd164bd4caf16d69db25a98f5d338f">llvm::MSP430TargetLowering::EmitShiftInstr</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/riscv/riscvframelowering-cpp/#a30a608df0c31b4ad3814cce66364082c">emitStackProbeInline</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/loongarch/loongarchisellowering-cpp/#accb97b288f5b7b78cc16845a383fc13c">emitVecCondBranchPseudo</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/x86/x86isellowering-cpp/#a13a9214d6e92afcb3e956a5891522bed">emitXBegin</a>, <a href="/web-llvm/docs/api/classes/llvm/amdgpuregisterbankinfo/#a533cd1035e03cdca3da433e98e77e430">llvm::AMDGPURegisterBankInfo::executeInWaterfallLoop</a>, <a href="/web-llvm/docs/api/classes/llvm/veinstrinfo/#ad99d6c93063cbfe0bf0f995a0cf12552">llvm::VEInstrInfo::expandExtendStackPseudo</a>, <a href="/web-llvm/docs/api/classes/llvm/sparctargetlowering/#a216c0fdb0cdd991dcf320bd42ff4c39e">llvm::SparcTargetLowering::expandSelectCC</a>, <a href="/web-llvm/docs/api/classes/llvm/ppcframelowering/#af0a5a3bd252aaac7b161ad8c01cf0951">llvm::PPCFrameLowering::inlineStackProbe</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/siinstrinfo-cpp/#af14ddf696e10f25864072cc0dc2e0161">loadMBUFScalarOperandsFromVGPR</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/webassembly/webassemblyisellowering-cpp/#a01bea37475bf9a1f853b90975dbf7605">LowerFPToInt</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/webassembly/webassemblyisellowering-cpp/#a1b22ed476a56f8583de43854dfe57830">LowerMemcpy</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/webassembly/webassemblyisellowering-cpp/#aa603afd757ff3057f96bf5c1ee83e8b2">LowerMemset</a>, <a href="/web-llvm/docs/api/classes/anonymous-ppcbranchcoalescing-cpp-/ppcbranchcoalescing/#a072a336f973a3de4daa8fe16e5b4570f">anonymous{PPCBranchCoalescing.cpp}::PPCBranchCoalescing::mergeCandidates</a>, <a href="/web-llvm/docs/api/classes/llvm/aarch64instrinfo/#ab9deb47df6ac29c81422ae6b4bfd924d">llvm::AArch64InstrInfo::probedStackAlloc</a>, <a href="#ac0bfa894f538166cb476b439a2cb0aea">splitAt</a>, <a href="/web-llvm/docs/api/namespaces/llvm/systemz/#a9f28b32cebb99746b65b07147c24d6cf">llvm::SystemZ::splitBlockAfter</a>, <a href="/web-llvm/docs/api/namespaces/llvm/systemz/#a175299250e6f7f5542fb5474ff0c9c6a">llvm::SystemZ::splitBlockBefore</a> and <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/siisellowering-cpp/#ac24b8552572d60a9f8943c27199fb8b2">splitBlockForLoop</a>.</p>

</div>
</div>

### updateTerminator() {#a5803a49facae20ca4b002dcba6f1d03e}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void MachineBasicBlock::updateTerminator (<a href="/web-llvm/docs/api/classes/llvm/machinebasicblock">MachineBasicBlock</a> * PreviousLayoutSuccessor)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Update the terminator instructions in block to account for changes to block layout which may have been made.</p>


<p>PreviousLayoutSuccessor should be set to the block which may have been used as fallthrough before the block layout was modified. If the block previously fell through to that block, it may now need a branch. If it previously branched to another block, it may now be able to fallthrough to the current layout successor.</p>


<p>Declaration at line 744 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/codegen/machinebasicblock-h">MachineBasicBlock.h</a>, definition at line 693 of file <a href="/web-llvm/docs/api/files/lib/lib/codegen/machinebasicblock-cpp">MachineBasicBlock.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/silowercontrolflow-cpp/#a4868c5d81c5ccc98c47aeab6244346a0">assert</a>, <a href="/web-llvm/docs/api/files/lib/lib/ir/builtingcs-cpp/#ae76959fe811ba090de4cba69ac00f1da">B</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/riscv/riscvredundantcopyelimination-cpp/#a193847098793cdbab306803186676899">Cond</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a7c46c742c31be54870e2038048e6b391">llvm::dbgs</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/arm/armslshardening-cpp/#ad467c4ab9119043f9b7750ab986be61a">DL</a>, <a href="#ad81901d0d8b768b240e78bf357999f34">findBranchDebugLoc</a>, <a href="/web-llvm/docs/api/classes/llvm/targetsubtargetinfo/#acd858ed72f11db9444617740c3622608">llvm::TargetSubtargetInfo::getInstrInfo</a>, <a href="#acf6442108e21e7e5379feb8962de65b7">getParent</a>, <a href="/web-llvm/docs/api/classes/llvm/machinefunction/#a3825368aca2bc1550d173660df4da6a6">llvm::MachineFunction::getSubtarget</a>, <a href="#a1100bfbadd996d464150c6a68fa8dc1d">isEHPad</a>, <a href="#abd85c9d7c51eb515a550069e9ad9445e">isLayoutSuccessor</a>, <a href="#adc8f1be4a77ae671ac139d5f06b44deb">isSuccessor</a>, <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/support/debug-h/#a196897517069dda1bdb549e24468f7d7">LLVM_DEBUG</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#af7881286e3ea4d7f1c4a63c87c132dac">llvm::printMBBReference</a>, <a href="#aa8d1d8d88835b75b05b14ab774785e8a">succ_empty</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/riscv/riscvredundantcopyelimination-cpp/#a1441f79530bc7f3a89118bb8067eac69">TBB</a> and <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/hexagon/hexagoncopytocombine-cpp/#a1d40004718218dbdf06b496766299101">TII</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/namespaces/llvm/#a0fdc13bfd373951ae6163637d6576c39">llvm::PeelSingleBlockLoop</a> and <a href="#aa80aaa82844ab5560ece045eee7b34ac">SplitCriticalEdge</a>.</p>

</div>
</div>

### validateSuccProbs() {#a6f0fb45670739e2756c1e41ce22c457b}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void MachineBasicBlock::validateSuccProbs ()</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Validate successors' probabilities and check if the sum of them is approximate one.</p>


<p>This only works in DEBUG mode.</p>


<p>Declaration at line 779 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/codegen/machinebasicblock-h">MachineBasicBlock.h</a>, definition at line 784 of file <a href="/web-llvm/docs/api/files/lib/lib/codegen/machinebasicblock-cpp">MachineBasicBlock.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/silowercontrolflow-cpp/#a4868c5d81c5ccc98c47aeab6244346a0">assert</a> and <a href="/web-llvm/docs/api/classes/llvm/branchprobability/#a19c752227e02f7cb26fb47fdb36dc349">llvm::BranchProbability::getDenominator</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Private Member Functions

### addPredecessor() {#ae604bff2bdb15779c0cf4fb842c05ac4}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void MachineBasicBlock::addPredecessor (<a href="/web-llvm/docs/api/classes/llvm/machinebasicblock">MachineBasicBlock</a> * Pred)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Add Pred as a predecessor of this <a href="/web-llvm/docs/api/classes/llvm/machinebasicblock">MachineBasicBlock</a>.</p>


<p>Don't do this unless you know what you're doing, because it doesn't update Pred's successors list. <a href="/web-llvm/docs/api/classes/llvm/use">Use</a> Pred-&gt;addSuccessor instead.</p>


<p>Declaration at line 1270 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/codegen/machinebasicblock-h">MachineBasicBlock.h</a>, definition at line 907 of file <a href="/web-llvm/docs/api/files/lib/lib/codegen/machinebasicblock-cpp">MachineBasicBlock.cpp</a>.</p>

</div>
</div>

### getProbabilityIterator() {#ae7e1d87fee532b477c249afd0735baa2}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">MachineBasicBlock::probability_iterator MachineBasicBlock::getProbabilityIterator (<a href="#a9936e11d7a6149f7cac8fa32a81dd488">succ_iterator</a> I)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Return probability iterator corresponding to the I successor iterator.</p>


<p>Return probability iterator corresonding to the I successor iterator.</p>


<p>Declaration at line 1255 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/codegen/machinebasicblock-h">MachineBasicBlock.h</a>, definition at line 1618 of file <a href="/web-llvm/docs/api/files/lib/lib/codegen/machinebasicblock-cpp">MachineBasicBlock.cpp</a>.</p>

</div>
</div>

### getProbabilityIterator() {#a7f82f84156c54b819f8d571d039924f1}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">MachineBasicBlock::const_probability_iterator MachineBasicBlock::getProbabilityIterator (<a href="#a3f43e04d827b07cf1d5366554d03f748">const_succ_iterator</a> I)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Return probability iterator corresonding to the I successor iterator.</p>

<p>Declaration at line 1257 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/codegen/machinebasicblock-h">MachineBasicBlock.h</a>, definition at line 1608 of file <a href="/web-llvm/docs/api/files/lib/lib/codegen/machinebasicblock-cpp">MachineBasicBlock.cpp</a>.</p>

</div>
</div>

### removePredecessor() {#a6cdb963bc7631186cc7272d8b5bd2e37}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void MachineBasicBlock::removePredecessor (<a href="/web-llvm/docs/api/classes/llvm/machinebasicblock">MachineBasicBlock</a> * Pred)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Remove Pred as a predecessor of this <a href="/web-llvm/docs/api/classes/llvm/machinebasicblock">MachineBasicBlock</a>.</p>


<p>Don't do this unless you know what you're doing, because it doesn't update Pred's successors list. <a href="/web-llvm/docs/api/classes/llvm/use">Use</a> Pred-&gt;removeSuccessor instead.</p>


<p>Declaration at line 1275 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/codegen/machinebasicblock-h">MachineBasicBlock.h</a>, definition at line 911 of file <a href="/web-llvm/docs/api/files/lib/lib/codegen/machinebasicblock-cpp">MachineBasicBlock.cpp</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Private Member Attributes

### AddressTakenIRBlock {#a03ebe9212604114c3f50a27cdc208f8c}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">BasicBlock* llvm::MachineBasicBlock::AddressTakenIRBlock = nullptr</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>If this <a href="/web-llvm/docs/api/classes/llvm/machinebasicblock">MachineBasicBlock</a> corresponds to an IR-level "blockaddress" constant, this contains a pointer to that block.</p>

<p>Definition at line 195 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/codegen/machinebasicblock-h">MachineBasicBlock.h</a>.</p>

</div>
</div>

### Alignment {#a290845d0eb80824612933eb53c1b3c3c}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">Align llvm::MachineBasicBlock::Alignment</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Alignment of the basic block.</p>


<p>One if the basic block does not need to be aligned.</p>


<p>Definition at line 180 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/codegen/machinebasicblock-h">MachineBasicBlock.h</a>.</p>

</div>
</div>

### BB {#a38abf622db4c408ea8676a8c847fce2f}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">const BasicBlock* llvm::MachineBasicBlock::BB</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 146 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/codegen/machinebasicblock-h">MachineBasicBlock.h</a>.</p>

</div>
</div>

### BBID {#af4970272a3e0bfce6f0004e2bc4b310b}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">std::optional&lt;UniqueBBID&gt; llvm::MachineBasicBlock::BBID</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Fixed unique <a href="/web-llvm/docs/api/namespaces/llvm/callingconv/#abdf8cf606905c10634e831390981b0ed">ID</a> assigned to this basic block upon creation.</p>


<p>Used with basic block sections and basic block labels.</p>


<p>Definition at line 217 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/codegen/machinebasicblock-h">MachineBasicBlock.h</a>.</p>

</div>
</div>

### CachedEHCatchretMCSymbol {#a4a66640a51268476b55b0db690e6bb61}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">MCSymbol* llvm::MachineBasicBlock::CachedEHCatchretMCSymbol = nullptr</td>
</tr>
</table>
</td>
<td class="doxyMemberLabelsRight">
<span class="doxyMemberLabels">
<span class="doxyMemberLabel mutable">mutable</span>
</span>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Cached <a href="/web-llvm/docs/api/classes/llvm/mcsymbol">MCSymbol</a> for this block (used if IsEHCatchRetTarget).</p>

<p>Definition at line 236 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/codegen/machinebasicblock-h">MachineBasicBlock.h</a>.</p>

</div>
</div>

### CachedEndMCSymbol {#a63f70ef9e743dd96169889251791eda3}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">MCSymbol* llvm::MachineBasicBlock::CachedEndMCSymbol = nullptr</td>
</tr>
</table>
</td>
<td class="doxyMemberLabelsRight">
<span class="doxyMemberLabels">
<span class="doxyMemberLabel mutable">mutable</span>
</span>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Marks the end of the basic block.</p>


<p>Used during basic block sections to calculate the size of the basic block, or the BB section ending with it.</p>


<p>Definition at line 240 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/codegen/machinebasicblock-h">MachineBasicBlock.h</a>.</p>

</div>
</div>

### CachedMCSymbol {#a3bc40e61dab48b8202763e53f5004c6b}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">MCSymbol* llvm::MachineBasicBlock::CachedMCSymbol = nullptr</td>
</tr>
</table>
</td>
<td class="doxyMemberLabelsRight">
<span class="doxyMemberLabels">
<span class="doxyMemberLabel mutable">mutable</span>
</span>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>since getSymbol is a relatively heavy-weight operation, the symbol is only computed once and is cached.</p>

<p>Definition at line 233 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/codegen/machinebasicblock-h">MachineBasicBlock.h</a>.</p>

</div>
</div>

### CallFrameSize {#a9f521bdaf2449ac14f88acbd1b5f6696}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">unsigned llvm::MachineBasicBlock::CallFrameSize = 0</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>The call frame size on entry to this basic block due to call frame setup instructions in a predecessor.</p>


<p>This is usually zero, unless basic blocks are split in the middle of a call sequence.</p>


<p>This information is only maintained until PrologEpilogInserter eliminates call frame pseudos.</p>


<p>Definition at line 155 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/codegen/machinebasicblock-h">MachineBasicBlock.h</a>.</p>

</div>
</div>

### Insts {#a066f5919ac1fb05971aa19600004a5fc}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">Instructions llvm::MachineBasicBlock::Insts</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 158 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/codegen/machinebasicblock-h">MachineBasicBlock.h</a>.</p>

</div>
</div>

### IrrLoopHeaderWeight {#ac1fb1cb844d0383b98c0c0acbc45fe13}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">std::optional&lt;uint64_t&gt; llvm::MachineBasicBlock::IrrLoopHeaderWeight</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 172 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/codegen/machinebasicblock-h">MachineBasicBlock.h</a>.</p>

</div>
</div>

### IsBeginSection {#a06e13a2a32e34a07d37c41bdc31c3bbb}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool llvm::MachineBasicBlock::IsBeginSection = false</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 223 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/codegen/machinebasicblock-h">MachineBasicBlock.h</a>.</p>

</div>
</div>

### IsCleanupFuncletEntry {#a43c07b5ce650da5578f76f478b38aa2f}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool llvm::MachineBasicBlock::IsCleanupFuncletEntry = false</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Indicate that this basic block is the entry block of a cleanup funclet.</p>

<p>Definition at line 213 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/codegen/machinebasicblock-h">MachineBasicBlock.h</a>.</p>

</div>
</div>

### IsEHCatchretTarget {#a1660c6738d59ac46b917fd08f267662a}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool llvm::MachineBasicBlock::IsEHCatchretTarget = false</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Indicates if this is a target block of a catchret.</p>

<p>Definition at line 207 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/codegen/machinebasicblock-h">MachineBasicBlock.h</a>.</p>

</div>
</div>

### IsEHFuncletEntry {#ae670ff8a9ccbc216ddd27e77f83b232d}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool llvm::MachineBasicBlock::IsEHFuncletEntry = false</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Indicate that this basic block is the entry block of an EH funclet.</p>

<p>Definition at line 210 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/codegen/machinebasicblock-h">MachineBasicBlock.h</a>.</p>

</div>
</div>

### IsEHPad {#a9e544bc758c33bf4c1854b1a2a1af8df}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool llvm::MachineBasicBlock::IsEHPad = false</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Indicate that this basic block is entered via an exception handler.</p>

<p>Definition at line 187 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/codegen/machinebasicblock-h">MachineBasicBlock.h</a>.</p>

</div>
</div>

### IsEHScopeEntry {#adadcc59c46cf7fa94a597cad0a4e9728}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool llvm::MachineBasicBlock::IsEHScopeEntry = false</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Indicate that this basic block is the entry block of an EH scope, i.e., the block that used to have a catchpad or cleanuppad instruction in the LLVM IR.</p>

<p>Definition at line 204 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/codegen/machinebasicblock-h">MachineBasicBlock.h</a>.</p>

</div>
</div>

### IsEndSection {#a27d120ff36e83bd2f88281195d3e5910}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool llvm::MachineBasicBlock::IsEndSection = false</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 226 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/codegen/machinebasicblock-h">MachineBasicBlock.h</a>.</p>

</div>
</div>

### IsInlineAsmBrIndirectTarget {#ad47740cf90b7431b29394c0c22cbbc44}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool llvm::MachineBasicBlock::IsInlineAsmBrIndirectTarget = false</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Indicate that this basic block is the indirect dest of an INLINEASM_BR.</p>

<p>Definition at line 229 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/codegen/machinebasicblock-h">MachineBasicBlock.h</a>.</p>

</div>
</div>

### LabelMustBeEmitted {#ac69b1d61d78e01506e276aa056b651f6}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool llvm::MachineBasicBlock::LabelMustBeEmitted = false</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Indicate that this basic block needs its symbol be emitted regardless of whether the flow just falls-through to it.</p>

<p>Definition at line 199 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/codegen/machinebasicblock-h">MachineBasicBlock.h</a>.</p>

</div>
</div>

### LiveIns {#a11a99edc69f45edc2edd2014a3dacc40}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">LiveInVector llvm::MachineBasicBlock::LiveIns</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 176 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/codegen/machinebasicblock-h">MachineBasicBlock.h</a>.</p>

</div>
</div>

### MachineBlockAddressTaken {#a45f2b95a6636e94c1a9a99c455a5108f}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool llvm::MachineBasicBlock::MachineBlockAddressTaken = false</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Indicate that this <a href="/web-llvm/docs/api/classes/llvm/machinebasicblock">MachineBasicBlock</a> is referenced somewhere other than as predecessor/successor, a terminator <a href="/web-llvm/docs/api/classes/llvm/machineinstr">MachineInstr</a>, or a jump table.</p>

<p>Definition at line 191 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/codegen/machinebasicblock-h">MachineBasicBlock.h</a>.</p>

</div>
</div>

### MaxBytesForAlignment {#a9b4b1df0aa33a43360c65b84c4753224}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">unsigned llvm::MachineBasicBlock::MaxBytesForAlignment = 0</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Maximum amount of bytes that can be added to align the basic block.</p>


<p>If the alignment cannot be reached in this many bytes, no bytes are emitted. Zero to represent no maximum.</p>


<p>Definition at line 184 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/codegen/machinebasicblock-h">MachineBasicBlock.h</a>.</p>

</div>
</div>

### Number {#a6b4fada343ca9edcbc94cdf9a7b641c4}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">int llvm::MachineBasicBlock::Number</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 147 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/codegen/machinebasicblock-h">MachineBasicBlock.h</a>.</p>

</div>
</div>

### Predecessors {#a0693ebc2b695da6ee922ec058ad0e4ea}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">SmallVector&lt;MachineBasicBlock *, 4&gt; llvm::MachineBasicBlock::Predecessors</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Keep track of the predecessor / successor basic blocks.</p>

<p>Definition at line 161 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/codegen/machinebasicblock-h">MachineBasicBlock.h</a>.</p>

</div>
</div>

### Probs {#a952a6ef8310d3ef92f6b38f03b5ea28d}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">std::vector&lt;BranchProbability&gt; llvm::MachineBasicBlock::Probs</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Keep track of the probabilities to the successors.</p>


<p>This vector has the same order as Successors, or it is empty if we don't use it (disable optimization).</p>


<p>Definition at line 167 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/codegen/machinebasicblock-h">MachineBasicBlock.h</a>.</p>

</div>
</div>

### SectionID {#a7ee82e7f2ea8408bbe6a52d3bfb0127b}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">MBBSectionID llvm::MachineBasicBlock::SectionID {0}</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>With basic block sections, this stores the Section <a href="/web-llvm/docs/api/namespaces/llvm/callingconv/#abdf8cf606905c10634e831390981b0ed">ID</a> of the basic block.</p>

<p>Definition at line 220 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/codegen/machinebasicblock-h">MachineBasicBlock.h</a>.</p>

</div>
</div>

### Successors {#a5b671c7ad91bd7d5a938d0a19b577904}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">SmallVector&lt;MachineBasicBlock *, 2&gt; llvm::MachineBasicBlock::Successors</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 162 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/codegen/machinebasicblock-h">MachineBasicBlock.h</a>.</p>

</div>
</div>

### xParent {#a67d186c9f4dfdca3055fcc9c2c1b13d9}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">MachineFunction* llvm::MachineBasicBlock::xParent</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 157 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/codegen/machinebasicblock-h">MachineBasicBlock.h</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Public Static Functions

### getSublistAccess() {#abf04d174151ccf42258903385338a984}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">Instructions MachineBasicBlock::* llvm::MachineBasicBlock::getSublistAccess (<a href="/web-llvm/docs/api/classes/llvm/machineinstr">MachineInstr</a> *)</td>
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

<p>Support for <a href="/web-llvm/docs/api/classes/llvm/ilist-node-with-parent/#a62ee7ece4986606d41363bc1f70d5ab2">MachineInstr::getNextNode()</a>.</p>

<p>Definition at line 380 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/codegen/machinebasicblock-h">MachineBasicBlock.h</a>.</p>

</div>
</div>

</div>

<hr/>

The documentation for this class was generated from the following files:

<ul>
<li><a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/codegen/machinebasicblock-h">MachineBasicBlock.h</a></li>
<li><a href="/web-llvm/docs/api/files/lib/lib/codegen/machinebasicblock-cpp">MachineBasicBlock.cpp</a></li>
</ul>

<hr/>

<p class="doxyGeneratedBy">Generated via <a href="https://github.com/xpack/doxygen2docusaurus">doxygen2docusaurus</a> by <a href="https://www.doxygen.nl">Doxygen</a> 1.14.0.</p>

</div>
