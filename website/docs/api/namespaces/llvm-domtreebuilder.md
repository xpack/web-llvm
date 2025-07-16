---

# DO NOT EDIT!
# Automatically generated via doxygen2docusaurus by Doxygen.

slug: /api/namespaces/llvm/domtreebuilder
custom_edit_url: null
toc_max_heading_level: 4
keywords:
  - doxygen
  - reference
  - namespace

---

<div class="doxyPage">

# The `DomTreeBuilder` Namespace Reference



## Definition

<div class="doxyDefinition">
namespace llvm::DomTreeBuilder { ... }
</div>

## Classes Index

<table class="doxyMembersIndex">

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">struct</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="/web-llvm/docs/api/structs/llvm/domtreebuilder/semincainfo">SemiNCAInfo&lt;DomTreeT&gt;</a></td>
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

## Typedefs Index

<table class="doxyMembersIndex">

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">using</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a7ba97ff80916ae98ebb1e5133018514a">MBBDomTree</a> = <a href="/web-llvm/docs/api/namespaces/llvm/#a763915fd0a536cc2d1ebe99595e3eeaf">DomTreeBase</a>&lt; <a href="/web-llvm/docs/api/classes/llvm/machinebasicblock">MachineBasicBlock</a> &gt;</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a72fbc42db8f760d7cf35e6df5f438fc0">MBBUpdates</a> = <a href="/web-llvm/docs/api/classes/llvm/arrayref">ArrayRef</a>&lt; <a href="/web-llvm/docs/api/classes/llvm/cfg/update">llvm::cfg::Update</a>&lt; <a href="/web-llvm/docs/api/classes/llvm/machinebasicblock">MachineBasicBlock</a> * &gt; &gt;</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a44d472917e0ba31d8fc2bd45b31e9929">MBBDomTreeGraphDiff</a> = <a href="/web-llvm/docs/api/classes/llvm/graphdiff">GraphDiff</a>&lt; <a href="/web-llvm/docs/api/classes/llvm/machinebasicblock">MachineBasicBlock</a> *, false &gt;</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#abb8afc64e82a69f280b2c140f5970ad3">MBBPostDomTree</a> = <a href="/web-llvm/docs/api/namespaces/llvm/#a42a6aebb3458a7c7e43d89338c1a6816">PostDomTreeBase</a>&lt; <a href="/web-llvm/docs/api/classes/llvm/machinebasicblock">MachineBasicBlock</a> &gt;</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a89d2d339de9a1ba83a5846fbb670fdc0">MBBPostDomTreeGraphDiff</a> = <a href="/web-llvm/docs/api/classes/llvm/graphdiff">GraphDiff</a>&lt; <a href="/web-llvm/docs/api/classes/llvm/machinebasicblock">MachineBasicBlock</a> *, <a href="/web-llvm/docs/api/files/lib/lib/analysis/basicaliasanalysis-cpp/#af6d5cafbdfc5313e65d990120021a3ec">true</a> &gt;</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ae5476cfab53290776b8a0fbe98e391f2">BBDomTree</a> = <a href="/web-llvm/docs/api/namespaces/llvm/#a763915fd0a536cc2d1ebe99595e3eeaf">DomTreeBase</a>&lt; <a href="/web-llvm/docs/api/classes/llvm/basicblock">BasicBlock</a> &gt;</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a8731d7b756fd9c7b437d98139bd91d5f">BBPostDomTree</a> = <a href="/web-llvm/docs/api/namespaces/llvm/#a42a6aebb3458a7c7e43d89338c1a6816">PostDomTreeBase</a>&lt; <a href="/web-llvm/docs/api/classes/llvm/basicblock">BasicBlock</a> &gt;</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a2a9e2a2431f6f6ecbb7996d72036bbbb">BBUpdates</a> = <a href="/web-llvm/docs/api/classes/llvm/arrayref">ArrayRef</a>&lt; <a href="/web-llvm/docs/api/classes/llvm/cfg/update">llvm::cfg::Update</a>&lt; <a href="/web-llvm/docs/api/classes/llvm/basicblock">BasicBlock</a> * &gt; &gt;</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a1ccc446b66a8994516d52174ebdc5997">BBDomTreeGraphDiff</a> = <a href="/web-llvm/docs/api/classes/llvm/graphdiff">GraphDiff</a>&lt; <a href="/web-llvm/docs/api/classes/llvm/basicblock">BasicBlock</a> *, false &gt;</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a561eb121d8b2ba449558167d79017f66">BBPostDomTreeGraphDiff</a> = <a href="/web-llvm/docs/api/classes/llvm/graphdiff">GraphDiff</a>&lt; <a href="/web-llvm/docs/api/classes/llvm/basicblock">BasicBlock</a> *, <a href="/web-llvm/docs/api/files/lib/lib/analysis/basicaliasanalysis-cpp/#af6d5cafbdfc5313e65d990120021a3ec">true</a> &gt;</td>
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

## Functions Index

<table class="doxyMembersIndex">

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">template void</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#adff7ae80c8014b62d115538468bc492e">Calculate&lt; MBBDomTree &gt;</a> (MBBDomTree &amp;DT)</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">template void</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a59b7def6f9a0aaea35f4f9f505be0b90">CalculateWithUpdates&lt; MBBDomTree &gt;</a> (MBBDomTree &amp;DT, MBBUpdates U)</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">template void</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a182500419f45afad28ca899486fb604e">InsertEdge&lt; MBBDomTree &gt;</a> (MBBDomTree &amp;DT, MachineBasicBlock *From, MachineBasicBlock *To)</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">template void</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#aa3c3a6d38770a512ad88d8f93e712fa8">DeleteEdge&lt; MBBDomTree &gt;</a> (MBBDomTree &amp;DT, MachineBasicBlock *From, MachineBasicBlock *To)</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">template void</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#aa336a166db161a6e751fa346e5276abe">ApplyUpdates&lt; MBBDomTree &gt;</a> (MBBDomTree &amp;DT, MBBDomTreeGraphDiff &amp;, MBBDomTreeGraphDiff *)</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">template bool</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a659b7948ad350618063f0f32ae32a48c">Verify&lt; MBBDomTree &gt;</a> (const MBBDomTree &amp;DT, MBBDomTree::VerificationLevel VL)</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">template void</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a9a29e77e1f177cf87eb4c699b54a78ad">Calculate&lt; MBBPostDomTree &gt;</a> (MBBPostDomTree &amp;DT)</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">template void</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a96265f1ebb19092c2113c1c36194eefa">InsertEdge&lt; MBBPostDomTree &gt;</a> (MBBPostDomTree &amp;DT, MachineBasicBlock *From, MachineBasicBlock *To)</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">template void</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a3f78bc73a2657e5aec01426b43999eee">DeleteEdge&lt; MBBPostDomTree &gt;</a> (MBBPostDomTree &amp;DT, MachineBasicBlock *From, MachineBasicBlock *To)</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">template void</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a01ea174d1b698fdebe265d67e9779506">ApplyUpdates&lt; MBBPostDomTree &gt;</a> (MBBPostDomTree &amp;DT, MBBPostDomTreeGraphDiff &amp;, MBBPostDomTreeGraphDiff *)</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">template bool</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#af28b2ee35845fe578c45762a804b38d3">Verify&lt; MBBPostDomTree &gt;</a> (const MBBPostDomTree &amp;DT, MBBPostDomTree::VerificationLevel VL)</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">template void</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#aa26fe66c2748d0f78172d437757aa7c8">Calculate&lt; BBDomTree &gt;</a> (BBDomTree &amp;DT)</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">template void</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a564410e4ac3327418110aedb128ac13f">CalculateWithUpdates&lt; BBDomTree &gt;</a> (BBDomTree &amp;DT, BBUpdates U)</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">template void</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ac665f884e260ad1b9e5b884d867ab0a5">Calculate&lt; BBPostDomTree &gt;</a> (BBPostDomTree &amp;DT)</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">template void</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a5449041d5e18230e4a363b26af5df12b">InsertEdge&lt; BBDomTree &gt;</a> (BBDomTree &amp;DT, BasicBlock *From, BasicBlock *To)</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">template void</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a27ec4347579e18c40c46c3cefb30fbd6">InsertEdge&lt; BBPostDomTree &gt;</a> (BBPostDomTree &amp;DT, BasicBlock *From, BasicBlock *To)</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">template void</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a46ac32dfbf9d56c5f208658231db8520">DeleteEdge&lt; BBDomTree &gt;</a> (BBDomTree &amp;DT, BasicBlock *From, BasicBlock *To)</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">template void</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a25100b7c77d571169537304b86c83fe9">DeleteEdge&lt; BBPostDomTree &gt;</a> (BBPostDomTree &amp;DT, BasicBlock *From, BasicBlock *To)</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">template void</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a224130ec5ff4246475699efc5920a93e">ApplyUpdates&lt; BBDomTree &gt;</a> (BBDomTree &amp;DT, BBDomTreeGraphDiff &amp;, BBDomTreeGraphDiff *)</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">template void</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a651cf2aa7dbea7b4cbaa709680f971b0">ApplyUpdates&lt; BBPostDomTree &gt;</a> (BBPostDomTree &amp;DT, BBPostDomTreeGraphDiff &amp;, BBPostDomTreeGraphDiff *)</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">template bool</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a576a71437577117b396471810b312f37">Verify&lt; BBDomTree &gt;</a> (const BBDomTree &amp;DT, BBDomTree::VerificationLevel VL)</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">template bool</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#af21812b908ed1568213b0cb027e77c99">Verify&lt; BBPostDomTree &gt;</a> (const BBPostDomTree &amp;DT, BBPostDomTree::VerificationLevel VL)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexTemplate">
<td class="doxyMemberIndexTemplate" colspan="2"><div>template &lt;typename DomTreeT&gt;</div></td>
</tr>
<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemTypeTemplate" align="left" valign="top">void</td>
<td class="doxyMemberIndexItemNameTemplate" align="left" valign="top"><a href="#a73e198fec8305bc64938bc784a8f0d1c">Calculate</a> (DomTreeT &amp;DT)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexTemplate">
<td class="doxyMemberIndexTemplate" colspan="2"><div>template &lt;typename DomTreeT&gt;</div></td>
</tr>
<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemTypeTemplate" align="left" valign="top">void</td>
<td class="doxyMemberIndexItemNameTemplate" align="left" valign="top"><a href="#a21425ba1759b3e091d72ce8333be2ff1">CalculateWithUpdates</a> (DomTreeT &amp;DT, ArrayRef&lt; typename DomTreeT::UpdateType &gt; Updates)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexTemplate">
<td class="doxyMemberIndexTemplate" colspan="2"><div>template &lt;typename DomTreeT&gt;</div></td>
</tr>
<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemTypeTemplate" align="left" valign="top">void</td>
<td class="doxyMemberIndexItemNameTemplate" align="left" valign="top"><a href="#ab5e2b97e90221527d92449f4ac5159f6">InsertEdge</a> (DomTreeT &amp;DT, typename DomTreeT::NodePtr From, typename DomTreeT::NodePtr To)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexTemplate">
<td class="doxyMemberIndexTemplate" colspan="2"><div>template &lt;typename DomTreeT&gt;</div></td>
</tr>
<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemTypeTemplate" align="left" valign="top">void</td>
<td class="doxyMemberIndexItemNameTemplate" align="left" valign="top"><a href="#a70aa6f22ccb403c6b716d03783275dfd">DeleteEdge</a> (DomTreeT &amp;DT, typename DomTreeT::NodePtr From, typename DomTreeT::NodePtr To)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexTemplate">
<td class="doxyMemberIndexTemplate" colspan="2"><div>template &lt;typename DomTreeT&gt;</div></td>
</tr>
<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemTypeTemplate" align="left" valign="top">void</td>
<td class="doxyMemberIndexItemNameTemplate" align="left" valign="top"><a href="#a938230b97505e69266ab1f8ac0eb5db7">ApplyUpdates</a> (DomTreeT &amp;DT, GraphDiff&lt; typename DomTreeT::NodePtr, DomTreeT::IsPostDominator &gt; &amp;PreViewCFG, GraphDiff&lt; typename DomTreeT::NodePtr, DomTreeT::IsPostDominator &gt; *PostViewCFG)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexTemplate">
<td class="doxyMemberIndexTemplate" colspan="2"><div>template &lt;typename DomTreeT&gt;</div></td>
</tr>
<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemTypeTemplate" align="left" valign="top">bool</td>
<td class="doxyMemberIndexItemNameTemplate" align="left" valign="top"><a href="#a1348bf219185f1a9896e890ab4c2061d">Verify</a> (const DomTreeT &amp;DT, typename DomTreeT::VerificationLevel VL)</td>
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


<div class="doxySectionDef">

## Typedefs

### BBDomTree {#ae5476cfab53290776b8a0fbe98e391f2}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">using llvm::DomTreeBuilder::BBDomTree =  DomTreeBase&lt;BasicBlock&gt;</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 53 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/ir/dominators-h">Dominators.h</a>.</p>

</div>
</div>

### BBDomTreeGraphDiff {#a1ccc446b66a8994516d52174ebdc5997}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">using llvm::DomTreeBuilder::BBDomTreeGraphDiff =  GraphDiff&lt;BasicBlock *, false&gt;</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 58 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/ir/dominators-h">Dominators.h</a>.</p>

</div>
</div>

### BBPostDomTree {#a8731d7b756fd9c7b437d98139bd91d5f}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">using llvm::DomTreeBuilder::BBPostDomTree =  PostDomTreeBase&lt;BasicBlock&gt;</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 54 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/ir/dominators-h">Dominators.h</a>.</p>

</div>
</div>

### BBPostDomTreeGraphDiff {#a561eb121d8b2ba449558167d79017f66}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">using llvm::DomTreeBuilder::BBPostDomTreeGraphDiff =  GraphDiff&lt;BasicBlock *, true&gt;</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 59 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/ir/dominators-h">Dominators.h</a>.</p>

</div>
</div>

### BBUpdates {#a2a9e2a2431f6f6ecbb7996d72036bbbb}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">using llvm::DomTreeBuilder::BBUpdates =  ArrayRef&lt;llvm::cfg::Update&lt;BasicBlock *&gt;&gt;</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 56 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/ir/dominators-h">Dominators.h</a>.</p>

</div>
</div>

### MBBDomTree {#a7ba97ff80916ae98ebb1e5133018514a}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">using llvm::DomTreeBuilder::MBBDomTree =  DomTreeBase&lt;MachineBasicBlock&gt;</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 47 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/codegen/machinedominators-h">MachineDominators.h</a>.</p>

</div>
</div>

### MBBDomTreeGraphDiff {#a44d472917e0ba31d8fc2bd45b31e9929}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">using llvm::DomTreeBuilder::MBBDomTreeGraphDiff =  GraphDiff&lt;MachineBasicBlock *, false&gt;</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 49 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/codegen/machinedominators-h">MachineDominators.h</a>.</p>

</div>
</div>

### MBBPostDomTree {#abb8afc64e82a69f280b2c140f5970ad3}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">using llvm::DomTreeBuilder::MBBPostDomTree =  PostDomTreeBase&lt;MachineBasicBlock&gt;</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 24 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/codegen/machinepostdominators-h">MachinePostDominators.h</a>.</p>

</div>
</div>

### MBBPostDomTreeGraphDiff {#a89d2d339de9a1ba83a5846fbb670fdc0}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">using llvm::DomTreeBuilder::MBBPostDomTreeGraphDiff =  GraphDiff&lt;MachineBasicBlock *, true&gt;</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 25 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/codegen/machinepostdominators-h">MachinePostDominators.h</a>.</p>

</div>
</div>

### MBBUpdates {#a72fbc42db8f760d7cf35e6df5f438fc0}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">using llvm::DomTreeBuilder::MBBUpdates =  ArrayRef&lt;llvm::cfg::Update&lt;MachineBasicBlock *&gt;&gt;</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 48 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/codegen/machinedominators-h">MachineDominators.h</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Functions

### ApplyUpdates() {#a938230b97505e69266ab1f8ac0eb5db7}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<div class="doxyMemberTemplate">template &lt;typename DomTreeT&gt;</div>
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void llvm::DomTreeBuilder::ApplyUpdates (DomTreeT &amp; DT, <a href="/web-llvm/docs/api/classes/llvm/graphdiff">GraphDiff</a>&lt; typename DomTreeT::NodePtr, DomTreeT::IsPostDominator &gt; &amp; PreViewCFG, <a href="/web-llvm/docs/api/classes/llvm/graphdiff">GraphDiff</a>&lt; typename DomTreeT::NodePtr, DomTreeT::IsPostDominator &gt; * PostViewCFG)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 1582 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/support/genericdomtreeconstruction-h">GenericDomTreeConstruction.h</a>.</p>


<p>Reference <a href="/web-llvm/docs/api/structs/llvm/domtreebuilder/semincainfo/#a597a58e3cc8ada27fdd127488b9f6d46">llvm::DomTreeBuilder::SemiNCAInfo&lt; DomTreeT &gt;::ApplyUpdates</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/classes/llvm/dominatortreebase/#a470b5b573c7915fe13bd529b22c9adbc">llvm::DominatorTreeBase&lt; BlockT, false &gt;::applyUpdates</a>, <a href="/web-llvm/docs/api/classes/llvm/dominatortreebase/#acbf2b914f43ca98a8c1ea9bd11a92de4">llvm::DominatorTreeBase&lt; BlockT, false &gt;::applyUpdates</a>, <a href="#a224130ec5ff4246475699efc5920a93e">ApplyUpdates&lt; BBDomTree &gt;</a>, <a href="#a651cf2aa7dbea7b4cbaa709680f971b0">ApplyUpdates&lt; BBPostDomTree &gt;</a>, <a href="#aa336a166db161a6e751fa346e5276abe">ApplyUpdates&lt; MBBDomTree &gt;</a>, <a href="#a01ea174d1b698fdebe265d67e9779506">ApplyUpdates&lt; MBBPostDomTree &gt;</a>, <a href="/web-llvm/docs/api/files/lib/lib/ir/dominators-cpp/#a39f672fee6d2831cd0496eb0d2ea7662">llvm::DomTreeBuilder::ApplyUpdates&lt; DomTreeBuilder::BBDomTree &gt;</a> and <a href="/web-llvm/docs/api/files/lib/lib/ir/dominators-cpp/#add34b4af126da632596f57a404e78865">llvm::DomTreeBuilder::ApplyUpdates&lt; DomTreeBuilder::BBPostDomTree &gt;</a>.</p>

</div>
</div>

### ApplyUpdates&lt; BBDomTree &gt;() {#a224130ec5ff4246475699efc5920a93e}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">template void llvm::DomTreeBuilder::ApplyUpdates&lt; BBDomTree &gt; (<a href="#ae5476cfab53290776b8a0fbe98e391f2">BBDomTree</a> &amp; DT, <a href="#a1ccc446b66a8994516d52174ebdc5997">BBDomTreeGraphDiff</a> &amp;, <a href="#a1ccc446b66a8994516d52174ebdc5997">BBDomTreeGraphDiff</a> *)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 79 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/ir/dominators-h">Dominators.h</a>.</p>


<p>Reference <a href="#a938230b97505e69266ab1f8ac0eb5db7">ApplyUpdates</a>.</p>

</div>
</div>

### ApplyUpdates&lt; BBPostDomTree &gt;() {#a651cf2aa7dbea7b4cbaa709680f971b0}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">template void llvm::DomTreeBuilder::ApplyUpdates&lt; BBPostDomTree &gt; (<a href="#a8731d7b756fd9c7b437d98139bd91d5f">BBPostDomTree</a> &amp; DT, <a href="#a561eb121d8b2ba449558167d79017f66">BBPostDomTreeGraphDiff</a> &amp;, <a href="#a561eb121d8b2ba449558167d79017f66">BBPostDomTreeGraphDiff</a> *)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 82 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/ir/dominators-h">Dominators.h</a>.</p>


<p>Reference <a href="#a938230b97505e69266ab1f8ac0eb5db7">ApplyUpdates</a>.</p>

</div>
</div>

### ApplyUpdates&lt; MBBDomTree &gt;() {#aa336a166db161a6e751fa346e5276abe}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">template void llvm::DomTreeBuilder::ApplyUpdates&lt; MBBDomTree &gt; (<a href="#a7ba97ff80916ae98ebb1e5133018514a">MBBDomTree</a> &amp; DT, <a href="#a44d472917e0ba31d8fc2bd45b31e9929">MBBDomTreeGraphDiff</a> &amp;, <a href="#a44d472917e0ba31d8fc2bd45b31e9929">MBBDomTreeGraphDiff</a> *)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 63 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/codegen/machinedominators-h">MachineDominators.h</a>.</p>


<p>Reference <a href="#a938230b97505e69266ab1f8ac0eb5db7">ApplyUpdates</a>.</p>

</div>
</div>

### ApplyUpdates&lt; MBBPostDomTree &gt;() {#a01ea174d1b698fdebe265d67e9779506}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">template void llvm::DomTreeBuilder::ApplyUpdates&lt; MBBPostDomTree &gt; (<a href="#abb8afc64e82a69f280b2c140f5970ad3">MBBPostDomTree</a> &amp; DT, <a href="#a89d2d339de9a1ba83a5846fbb670fdc0">MBBPostDomTreeGraphDiff</a> &amp;, <a href="#a89d2d339de9a1ba83a5846fbb670fdc0">MBBPostDomTreeGraphDiff</a> *)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 34 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/codegen/machinepostdominators-h">MachinePostDominators.h</a>.</p>


<p>Reference <a href="#a938230b97505e69266ab1f8ac0eb5db7">ApplyUpdates</a>.</p>

</div>
</div>

### Calculate() {#a73e198fec8305bc64938bc784a8f0d1c}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<div class="doxyMemberTemplate">template &lt;typename DomTreeT&gt;</div>
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void llvm::DomTreeBuilder::Calculate (DomTreeT &amp; DT)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 1552 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/support/genericdomtreeconstruction-h">GenericDomTreeConstruction.h</a>.</p>


<p>Reference <a href="/web-llvm/docs/api/structs/llvm/domtreebuilder/semincainfo/#a91b2ad7a91962494b1608aa174ac8ff3">llvm::DomTreeBuilder::SemiNCAInfo&lt; DomTreeT &gt;::CalculateFromScratch</a>.</p>


<p>Referenced by <a href="#aa26fe66c2748d0f78172d437757aa7c8">Calculate&lt; BBDomTree &gt;</a>, <a href="#ac665f884e260ad1b9e5b884d867ab0a5">Calculate&lt; BBPostDomTree &gt;</a>, <a href="#adff7ae80c8014b62d115538468bc492e">Calculate&lt; MBBDomTree &gt;</a>, <a href="#a9a29e77e1f177cf87eb4c699b54a78ad">Calculate&lt; MBBPostDomTree &gt;</a>, <a href="/web-llvm/docs/api/files/lib/lib/ir/dominators-cpp/#a2180255e12b0a1061b66fda7197a06a6">llvm::DomTreeBuilder::Calculate&lt; DomTreeBuilder::BBDomTree &gt;</a>, <a href="/web-llvm/docs/api/files/lib/lib/ir/dominators-cpp/#a7fac961cb4c1a6abcc9833a70e0da6bf">llvm::DomTreeBuilder::Calculate&lt; DomTreeBuilder::BBPostDomTree &gt;</a> and <a href="/web-llvm/docs/api/classes/llvm/dominatortreebase/#aa0641ae965656ff9988d67a35140e4d9">llvm::DominatorTreeBase&lt; BlockT, false &gt;::recalculate</a>.</p>

</div>
</div>

### Calculate&lt; BBDomTree &gt;() {#aa26fe66c2748d0f78172d437757aa7c8}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">template void llvm::DomTreeBuilder::Calculate&lt; BBDomTree &gt; (<a href="#ae5476cfab53290776b8a0fbe98e391f2">BBDomTree</a> &amp; DT)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 61 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/ir/dominators-h">Dominators.h</a>.</p>


<p>Reference <a href="#a73e198fec8305bc64938bc784a8f0d1c">Calculate</a>.</p>

</div>
</div>

### Calculate&lt; BBPostDomTree &gt;() {#ac665f884e260ad1b9e5b884d867ab0a5}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">template void llvm::DomTreeBuilder::Calculate&lt; BBPostDomTree &gt; (<a href="#a8731d7b756fd9c7b437d98139bd91d5f">BBPostDomTree</a> &amp; DT)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 65 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/ir/dominators-h">Dominators.h</a>.</p>


<p>Reference <a href="#a73e198fec8305bc64938bc784a8f0d1c">Calculate</a>.</p>

</div>
</div>

### Calculate&lt; MBBDomTree &gt;() {#adff7ae80c8014b62d115538468bc492e}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">template void llvm::DomTreeBuilder::Calculate&lt; MBBDomTree &gt; (<a href="#a7ba97ff80916ae98ebb1e5133018514a">MBBDomTree</a> &amp; DT)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 51 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/codegen/machinedominators-h">MachineDominators.h</a>.</p>


<p>Reference <a href="#a73e198fec8305bc64938bc784a8f0d1c">Calculate</a>.</p>

</div>
</div>

### Calculate&lt; MBBPostDomTree &gt;() {#a9a29e77e1f177cf87eb4c699b54a78ad}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">template void llvm::DomTreeBuilder::Calculate&lt; MBBPostDomTree &gt; (<a href="#abb8afc64e82a69f280b2c140f5970ad3">MBBPostDomTree</a> &amp; DT)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 27 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/codegen/machinepostdominators-h">MachinePostDominators.h</a>.</p>


<p>Reference <a href="#a73e198fec8305bc64938bc784a8f0d1c">Calculate</a>.</p>

</div>
</div>

### CalculateWithUpdates() {#a21425ba1759b3e091d72ce8333be2ff1}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<div class="doxyMemberTemplate">template &lt;typename DomTreeT&gt;</div>
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void llvm::DomTreeBuilder::CalculateWithUpdates (DomTreeT &amp; DT, <a href="/web-llvm/docs/api/classes/llvm/arrayref">ArrayRef</a>&lt; typename DomTreeT::UpdateType &gt; Updates)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 1557 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/support/genericdomtreeconstruction-h">GenericDomTreeConstruction.h</a>.</p>


<p>Reference <a href="/web-llvm/docs/api/structs/llvm/domtreebuilder/semincainfo/#a91b2ad7a91962494b1608aa174ac8ff3">llvm::DomTreeBuilder::SemiNCAInfo&lt; DomTreeT &gt;::CalculateFromScratch</a>.</p>


<p>Referenced by <a href="#a564410e4ac3327418110aedb128ac13f">CalculateWithUpdates&lt; BBDomTree &gt;</a>, <a href="#a59b7def6f9a0aaea35f4f9f505be0b90">CalculateWithUpdates&lt; MBBDomTree &gt;</a>, <a href="/web-llvm/docs/api/files/lib/lib/ir/dominators-cpp/#a81522f9a7315b9e828a7d30e0fb4cf85">llvm::DomTreeBuilder::CalculateWithUpdates&lt; DomTreeBuilder::BBDomTree &gt;</a> and <a href="/web-llvm/docs/api/classes/llvm/dominatortreebase/#a7dd2a25cb133a3d75887ea740201311d">llvm::DominatorTreeBase&lt; BlockT, false &gt;::recalculate</a>.</p>

</div>
</div>

### CalculateWithUpdates&lt; BBDomTree &gt;() {#a564410e4ac3327418110aedb128ac13f}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">template void llvm::DomTreeBuilder::CalculateWithUpdates&lt; BBDomTree &gt; (<a href="#ae5476cfab53290776b8a0fbe98e391f2">BBDomTree</a> &amp; DT, <a href="#a2a9e2a2431f6f6ecbb7996d72036bbbb">BBUpdates</a> U)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 62 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/ir/dominators-h">Dominators.h</a>.</p>


<p>Reference <a href="#a21425ba1759b3e091d72ce8333be2ff1">CalculateWithUpdates</a>.</p>

</div>
</div>

### CalculateWithUpdates&lt; MBBDomTree &gt;() {#a59b7def6f9a0aaea35f4f9f505be0b90}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">template void llvm::DomTreeBuilder::CalculateWithUpdates&lt; MBBDomTree &gt; (<a href="#a7ba97ff80916ae98ebb1e5133018514a">MBBDomTree</a> &amp; DT, <a href="#a72fbc42db8f760d7cf35e6df5f438fc0">MBBUpdates</a> U)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 52 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/codegen/machinedominators-h">MachineDominators.h</a>.</p>


<p>Reference <a href="#a21425ba1759b3e091d72ce8333be2ff1">CalculateWithUpdates</a>.</p>

</div>
</div>

### DeleteEdge() {#a70aa6f22ccb403c6b716d03783275dfd}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<div class="doxyMemberTemplate">template &lt;typename DomTreeT&gt;</div>
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void llvm::DomTreeBuilder::DeleteEdge (DomTreeT &amp; DT, typename DomTreeT::NodePtr From, typename DomTreeT::NodePtr To)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 1575 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/support/genericdomtreeconstruction-h">GenericDomTreeConstruction.h</a>.</p>


<p>References <a href="/web-llvm/docs/api/structs/llvm/domtreebuilder/semincainfo/#a0733c415f27a3fa6f962bb5d5353ec1b">llvm::DomTreeBuilder::SemiNCAInfo&lt; DomTreeT &gt;::DeleteEdge</a> and <a href="/web-llvm/docs/api/namespaces/std/#ab8424022895aee3e366fb9a32f2883cb">std::swap</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/classes/llvm/dominatortreebase/#ab0f09aefdf088f84a0bff7cba86454b4">llvm::DominatorTreeBase&lt; BlockT, false &gt;::deleteEdge</a>, <a href="#a46ac32dfbf9d56c5f208658231db8520">DeleteEdge&lt; BBDomTree &gt;</a>, <a href="#a25100b7c77d571169537304b86c83fe9">DeleteEdge&lt; BBPostDomTree &gt;</a>, <a href="#aa3c3a6d38770a512ad88d8f93e712fa8">DeleteEdge&lt; MBBDomTree &gt;</a>, <a href="#a3f78bc73a2657e5aec01426b43999eee">DeleteEdge&lt; MBBPostDomTree &gt;</a>, <a href="/web-llvm/docs/api/files/lib/lib/ir/dominators-cpp/#ac78e40bd018a93040a8ff4cfc22994ea">llvm::DomTreeBuilder::DeleteEdge&lt; DomTreeBuilder::BBDomTree &gt;</a> and <a href="/web-llvm/docs/api/files/lib/lib/ir/dominators-cpp/#a0ebf7df7248c9593df45b80653d8164c">llvm::DomTreeBuilder::DeleteEdge&lt; DomTreeBuilder::BBPostDomTree &gt;</a>.</p>

</div>
</div>

### DeleteEdge&lt; BBDomTree &gt;() {#a46ac32dfbf9d56c5f208658231db8520}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">template void llvm::DomTreeBuilder::DeleteEdge&lt; BBDomTree &gt; (<a href="#ae5476cfab53290776b8a0fbe98e391f2">BBDomTree</a> &amp; DT, <a href="/web-llvm/docs/api/classes/llvm/basicblock">BasicBlock</a> * From, <a href="/web-llvm/docs/api/classes/llvm/basicblock">BasicBlock</a> * To)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 73 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/ir/dominators-h">Dominators.h</a>.</p>


<p>Reference <a href="#a70aa6f22ccb403c6b716d03783275dfd">DeleteEdge</a>.</p>

</div>
</div>

### DeleteEdge&lt; BBPostDomTree &gt;() {#a25100b7c77d571169537304b86c83fe9}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">template void llvm::DomTreeBuilder::DeleteEdge&lt; BBPostDomTree &gt; (<a href="#a8731d7b756fd9c7b437d98139bd91d5f">BBPostDomTree</a> &amp; DT, <a href="/web-llvm/docs/api/classes/llvm/basicblock">BasicBlock</a> * From, <a href="/web-llvm/docs/api/classes/llvm/basicblock">BasicBlock</a> * To)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 75 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/ir/dominators-h">Dominators.h</a>.</p>


<p>Reference <a href="#a70aa6f22ccb403c6b716d03783275dfd">DeleteEdge</a>.</p>

</div>
</div>

### DeleteEdge&lt; MBBDomTree &gt;() {#aa3c3a6d38770a512ad88d8f93e712fa8}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">template void llvm::DomTreeBuilder::DeleteEdge&lt; MBBDomTree &gt; (<a href="#a7ba97ff80916ae98ebb1e5133018514a">MBBDomTree</a> &amp; DT, <a href="/web-llvm/docs/api/classes/llvm/machinebasicblock">MachineBasicBlock</a> * From, <a href="/web-llvm/docs/api/classes/llvm/machinebasicblock">MachineBasicBlock</a> * To)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 59 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/codegen/machinedominators-h">MachineDominators.h</a>.</p>


<p>Reference <a href="#a70aa6f22ccb403c6b716d03783275dfd">DeleteEdge</a>.</p>

</div>
</div>

### DeleteEdge&lt; MBBPostDomTree &gt;() {#a3f78bc73a2657e5aec01426b43999eee}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">template void llvm::DomTreeBuilder::DeleteEdge&lt; MBBPostDomTree &gt; (<a href="#abb8afc64e82a69f280b2c140f5970ad3">MBBPostDomTree</a> &amp; DT, <a href="/web-llvm/docs/api/classes/llvm/machinebasicblock">MachineBasicBlock</a> * From, <a href="/web-llvm/docs/api/classes/llvm/machinebasicblock">MachineBasicBlock</a> * To)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 31 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/codegen/machinepostdominators-h">MachinePostDominators.h</a>.</p>


<p>Reference <a href="#a70aa6f22ccb403c6b716d03783275dfd">DeleteEdge</a>.</p>

</div>
</div>

### InsertEdge() {#ab5e2b97e90221527d92449f4ac5159f6}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<div class="doxyMemberTemplate">template &lt;typename DomTreeT&gt;</div>
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void llvm::DomTreeBuilder::InsertEdge (DomTreeT &amp; DT, typename DomTreeT::NodePtr From, typename DomTreeT::NodePtr To)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 1568 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/support/genericdomtreeconstruction-h">GenericDomTreeConstruction.h</a>.</p>


<p>References <a href="/web-llvm/docs/api/structs/llvm/domtreebuilder/semincainfo/#ae13a8bd8e24f12a9040cbbc5407d4b87">llvm::DomTreeBuilder::SemiNCAInfo&lt; DomTreeT &gt;::InsertEdge</a> and <a href="/web-llvm/docs/api/namespaces/std/#ab8424022895aee3e366fb9a32f2883cb">std::swap</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/classes/llvm/dominatortreebase/#a51145a3ae24ea73b3692a17088edea7b">llvm::DominatorTreeBase&lt; BlockT, false &gt;::insertEdge</a>, <a href="#a5449041d5e18230e4a363b26af5df12b">InsertEdge&lt; BBDomTree &gt;</a>, <a href="#a27ec4347579e18c40c46c3cefb30fbd6">InsertEdge&lt; BBPostDomTree &gt;</a>, <a href="#a182500419f45afad28ca899486fb604e">InsertEdge&lt; MBBDomTree &gt;</a>, <a href="#a96265f1ebb19092c2113c1c36194eefa">InsertEdge&lt; MBBPostDomTree &gt;</a>, <a href="/web-llvm/docs/api/files/lib/lib/ir/dominators-cpp/#ac6070220b820e82fc8aef505435e8f1e">llvm::DomTreeBuilder::InsertEdge&lt; DomTreeBuilder::BBDomTree &gt;</a> and <a href="/web-llvm/docs/api/files/lib/lib/ir/dominators-cpp/#a37cb26c6ab42b3bba699c4c81272edbd">llvm::DomTreeBuilder::InsertEdge&lt; DomTreeBuilder::BBPostDomTree &gt;</a>.</p>

</div>
</div>

### InsertEdge&lt; BBDomTree &gt;() {#a5449041d5e18230e4a363b26af5df12b}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">template void llvm::DomTreeBuilder::InsertEdge&lt; BBDomTree &gt; (<a href="#ae5476cfab53290776b8a0fbe98e391f2">BBDomTree</a> &amp; DT, <a href="/web-llvm/docs/api/classes/llvm/basicblock">BasicBlock</a> * From, <a href="/web-llvm/docs/api/classes/llvm/basicblock">BasicBlock</a> * To)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 67 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/ir/dominators-h">Dominators.h</a>.</p>


<p>Reference <a href="#ab5e2b97e90221527d92449f4ac5159f6">InsertEdge</a>.</p>

</div>
</div>

### InsertEdge&lt; BBPostDomTree &gt;() {#a27ec4347579e18c40c46c3cefb30fbd6}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">template void llvm::DomTreeBuilder::InsertEdge&lt; BBPostDomTree &gt; (<a href="#a8731d7b756fd9c7b437d98139bd91d5f">BBPostDomTree</a> &amp; DT, <a href="/web-llvm/docs/api/classes/llvm/basicblock">BasicBlock</a> * From, <a href="/web-llvm/docs/api/classes/llvm/basicblock">BasicBlock</a> * To)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 69 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/ir/dominators-h">Dominators.h</a>.</p>


<p>Reference <a href="#ab5e2b97e90221527d92449f4ac5159f6">InsertEdge</a>.</p>

</div>
</div>

### InsertEdge&lt; MBBDomTree &gt;() {#a182500419f45afad28ca899486fb604e}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">template void llvm::DomTreeBuilder::InsertEdge&lt; MBBDomTree &gt; (<a href="#a7ba97ff80916ae98ebb1e5133018514a">MBBDomTree</a> &amp; DT, <a href="/web-llvm/docs/api/classes/llvm/machinebasicblock">MachineBasicBlock</a> * From, <a href="/web-llvm/docs/api/classes/llvm/machinebasicblock">MachineBasicBlock</a> * To)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 55 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/codegen/machinedominators-h">MachineDominators.h</a>.</p>


<p>Reference <a href="#ab5e2b97e90221527d92449f4ac5159f6">InsertEdge</a>.</p>

</div>
</div>

### InsertEdge&lt; MBBPostDomTree &gt;() {#a96265f1ebb19092c2113c1c36194eefa}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">template void llvm::DomTreeBuilder::InsertEdge&lt; MBBPostDomTree &gt; (<a href="#abb8afc64e82a69f280b2c140f5970ad3">MBBPostDomTree</a> &amp; DT, <a href="/web-llvm/docs/api/classes/llvm/machinebasicblock">MachineBasicBlock</a> * From, <a href="/web-llvm/docs/api/classes/llvm/machinebasicblock">MachineBasicBlock</a> * To)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 28 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/codegen/machinepostdominators-h">MachinePostDominators.h</a>.</p>


<p>Reference <a href="#ab5e2b97e90221527d92449f4ac5159f6">InsertEdge</a>.</p>

</div>
</div>

### Verify() {#a1348bf219185f1a9896e890ab4c2061d}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<div class="doxyMemberTemplate">template &lt;typename DomTreeT&gt;</div>
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool llvm::DomTreeBuilder::Verify (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> DomTreeT &amp; DT, typename DomTreeT::VerificationLevel VL)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 1591 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/support/genericdomtreeconstruction-h">GenericDomTreeConstruction.h</a>.</p>


<p>References <a href="/web-llvm/docs/api/structs/llvm/domtreebuilder/semincainfo/#a4ea2d791b0cb2b452a1d9ccfaf181712">llvm::DomTreeBuilder::SemiNCAInfo&lt; DomTreeT &gt;::IsSameAsFreshTree</a>, <a href="/web-llvm/docs/api/structs/llvm/domtreebuilder/semincainfo/#aba197972422fd98e9318e22f0419e0a8">llvm::DomTreeBuilder::SemiNCAInfo&lt; DomTreeT &gt;::VerifyDFSNumbers</a>, <a href="/web-llvm/docs/api/structs/llvm/domtreebuilder/semincainfo/#a4714e88fbf38f2aaf7fd427dfb17a3a0">llvm::DomTreeBuilder::SemiNCAInfo&lt; DomTreeT &gt;::VerifyLevels</a>, <a href="/web-llvm/docs/api/structs/llvm/domtreebuilder/semincainfo/#aeeca9e1d5c151829946fa95f9b9b30c7">llvm::DomTreeBuilder::SemiNCAInfo&lt; DomTreeT &gt;::verifyParentProperty</a>, <a href="/web-llvm/docs/api/structs/llvm/domtreebuilder/semincainfo/#a4bed97020476a2d93eb433776597d3de">llvm::DomTreeBuilder::SemiNCAInfo&lt; DomTreeT &gt;::verifyReachability</a>, <a href="/web-llvm/docs/api/structs/llvm/domtreebuilder/semincainfo/#aeff699bd020f8620eb57bc0ffd9ce847">llvm::DomTreeBuilder::SemiNCAInfo&lt; DomTreeT &gt;::verifyRoots</a> and <a href="/web-llvm/docs/api/structs/llvm/domtreebuilder/semincainfo/#a647a59b37db18cd302d604f723ba2ec4">llvm::DomTreeBuilder::SemiNCAInfo&lt; DomTreeT &gt;::verifySiblingProperty</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/files/lib/lib/ir/dominators-cpp/#a70b7d91571e3e5ac29d7ee116efa0fc8">llvm::DomTreeBuilder::Verify&lt; DomTreeBuilder::BBDomTree &gt;</a>, <a href="/web-llvm/docs/api/files/lib/lib/ir/dominators-cpp/#ad5a5e7c5a7587a2023cb7f86ea90dc6d">llvm::DomTreeBuilder::Verify&lt; DomTreeBuilder::BBPostDomTree &gt;</a>, <a href="/web-llvm/docs/api/classes/llvm/dominatortreebase/#a1f08f2925fec05b265e540d29066b9c8">llvm::DominatorTreeBase&lt; BlockT, false &gt;::verify</a>, <a href="#a576a71437577117b396471810b312f37">Verify&lt; BBDomTree &gt;</a>, <a href="#af21812b908ed1568213b0cb027e77c99">Verify&lt; BBPostDomTree &gt;</a>, <a href="#a659b7948ad350618063f0f32ae32a48c">Verify&lt; MBBDomTree &gt;</a> and <a href="#af28b2ee35845fe578c45762a804b38d3">Verify&lt; MBBPostDomTree &gt;</a>.</p>

</div>
</div>

### Verify&lt; BBDomTree &gt;() {#a576a71437577117b396471810b312f37}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">template bool llvm::DomTreeBuilder::Verify&lt; BBDomTree &gt; (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="#ae5476cfab53290776b8a0fbe98e391f2">BBDomTree</a> &amp; DT, <a href="/web-llvm/docs/api/classes/llvm/dominatortreebase/#aad6e57a3b7c184bded15b616e790781f">BBDomTree::VerificationLevel</a> VL)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 86 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/ir/dominators-h">Dominators.h</a>.</p>


<p>Reference <a href="#a1348bf219185f1a9896e890ab4c2061d">Verify</a>.</p>

</div>
</div>

### Verify&lt; BBPostDomTree &gt;() {#af21812b908ed1568213b0cb027e77c99}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">template bool llvm::DomTreeBuilder::Verify&lt; BBPostDomTree &gt; (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="#a8731d7b756fd9c7b437d98139bd91d5f">BBPostDomTree</a> &amp; DT, <a href="/web-llvm/docs/api/classes/llvm/dominatortreebase/#aad6e57a3b7c184bded15b616e790781f">BBPostDomTree::VerificationLevel</a> VL)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 88 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/ir/dominators-h">Dominators.h</a>.</p>


<p>Reference <a href="#a1348bf219185f1a9896e890ab4c2061d">Verify</a>.</p>

</div>
</div>

### Verify&lt; MBBDomTree &gt;() {#a659b7948ad350618063f0f32ae32a48c}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">template bool llvm::DomTreeBuilder::Verify&lt; MBBDomTree &gt; (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="#a7ba97ff80916ae98ebb1e5133018514a">MBBDomTree</a> &amp; DT, <a href="/web-llvm/docs/api/classes/llvm/dominatortreebase/#aad6e57a3b7c184bded15b616e790781f">MBBDomTree::VerificationLevel</a> VL)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 67 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/codegen/machinedominators-h">MachineDominators.h</a>.</p>


<p>Reference <a href="#a1348bf219185f1a9896e890ab4c2061d">Verify</a>.</p>

</div>
</div>

### Verify&lt; MBBPostDomTree &gt;() {#af28b2ee35845fe578c45762a804b38d3}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">template bool llvm::DomTreeBuilder::Verify&lt; MBBPostDomTree &gt; (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="#abb8afc64e82a69f280b2c140f5970ad3">MBBPostDomTree</a> &amp; DT, <a href="/web-llvm/docs/api/classes/llvm/dominatortreebase/#aad6e57a3b7c184bded15b616e790781f">MBBPostDomTree::VerificationLevel</a> VL)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 37 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/codegen/machinepostdominators-h">MachinePostDominators.h</a>.</p>


<p>Reference <a href="#a1348bf219185f1a9896e890ab4c2061d">Verify</a>.</p>

</div>
</div>

</div>

<hr/>

The documentation for this namespace was generated from the following files:

<ul>
<li><a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/codegen/machinedominators-h">MachineDominators.h</a></li>
<li><a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/codegen/machinepostdominators-h">MachinePostDominators.h</a></li>
<li><a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/ir/dominators-h">Dominators.h</a></li>
<li><a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/support/genericdomtreeconstruction-h">GenericDomTreeConstruction.h</a></li>
</ul>

<hr/>

<p class="doxyGeneratedBy">Generated via <a href="https://github.com/xpack/doxygen2docusaurus">doxygen2docusaurus</a> by <a href="https://www.doxygen.nl">Doxygen</a> 1.15.0.</p>

</div>
