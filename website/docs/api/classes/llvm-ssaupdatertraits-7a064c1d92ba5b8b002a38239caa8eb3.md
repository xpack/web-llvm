---

# DO NOT EDIT!
# Automatically generated via doxygen2docusaurus by Doxygen.

slug: /api/classes/llvm/ssaupdatertraits-7a064c1d92ba5b8b002a38239caa8eb3
custom_edit_url: null
toc_max_heading_level: 4
keywords:
  - doxygen
  - reference
  - class

---

<div class="doxyPage">

# The `SSAUpdaterTraits` Class Template Reference



## Declaration

<div class="doxyDeclaration">
class llvm::SSAUpdaterTraits&lt;SSAUpdater&gt; { ... }
</div>

## Public Member Typedefs Index

<table class="doxyMembersIndex">

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">using</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a7afb60a9497715e7d488d83485bf5c21">BlkT</a> = <a href="/web-llvm/docs/api/classes/llvm/basicblock">BasicBlock</a></td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ae511ea4aef48e973b1b36c102b903955">ValT</a> = <a href="/web-llvm/docs/api/classes/llvm/value">Value</a> *</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a9d747ed8faca5ffa0815ba331e012281">PhiT</a> = <a href="/web-llvm/docs/api/classes/llvm/phinode">PHINode</a></td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a72fcdee6ad8a3c4f2b3e7e2a5cee312c">BlkSucc_iterator</a> = <a href="/web-llvm/docs/api/namespaces/llvm/#acc56362e89d398a34b5da66ddedb5448">succ_iterator</a></td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">static <a href="#a72fcdee6ad8a3c4f2b3e7e2a5cee312c">BlkSucc_iterator</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a32b52f992c85cb66b6b52a3d69e81dc6">BlkSucc_begin</a> (BlkT *BB)</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">static <a href="#a72fcdee6ad8a3c4f2b3e7e2a5cee312c">BlkSucc_iterator</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a2e581d0082c66a7ed5381efaab7fd9cb">BlkSucc_end</a> (BlkT *BB)</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">static <a href="/web-llvm/docs/api/classes/llvm/ssaupdatertraits/phi-iterator-8c2004dc384f8895c408f99ce225ab0c">PHI_iterator</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a7234490e9abb681a170ebcea530ce0c6">PHI_begin</a> (PhiT *PHI)</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">static <a href="/web-llvm/docs/api/classes/llvm/ssaupdatertraits/phi-iterator-8c2004dc384f8895c408f99ce225ab0c">PHI_iterator</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#acd0e2a55c9c480f7aa81c6a41bd180ab">PHI_end</a> (PhiT *PHI)</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">static void</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a58a5535f6186eecaf32ad97b8461eff4">FindPredecessorBlocks</a> (BasicBlock *BB, SmallVectorImpl&lt; BasicBlock * &gt; *Preds)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>FindPredecessorBlocks - Put the predecessors of Info-&gt;BB into the Preds vector, set Info-&gt;NumPreds, and allocate space in Info-&gt;Preds. <a href="#a58a5535f6186eecaf32ad97b8461eff4">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">static <a href="/web-llvm/docs/api/classes/llvm/value">Value</a> *</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a9c944a235e8f62b5ed7b459ce1f01072">GetPoisonVal</a> (BasicBlock *BB, SSAUpdater *Updater)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>GetPoisonVal - Get a poison value of the same type as the value being handled. <a href="#a9c944a235e8f62b5ed7b459ce1f01072">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">static <a href="/web-llvm/docs/api/classes/llvm/value">Value</a> *</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a6280f6984dd0e0455b73f22b3a5800c2">CreateEmptyPHI</a> (BasicBlock *BB, unsigned NumPreds, SSAUpdater *Updater)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>CreateEmptyPHI - Create a new PHI instruction in the specified block. <a href="#a6280f6984dd0e0455b73f22b3a5800c2">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">static void</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a7dbe4f9e5825611510efd0ab7516fc96">AddPHIOperand</a> (PHINode *PHI, Value *Val, BasicBlock *Pred)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>AddPHIOperand - Add the specified value as an operand of the PHI for the specified predecessor block. <a href="#a7dbe4f9e5825611510efd0ab7516fc96">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">static <a href="/web-llvm/docs/api/classes/llvm/phinode">PHINode</a> *</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ae1767e092b6e8e2a35c1574c6b6b6456">ValueIsPHI</a> (Value *Val, SSAUpdater *Updater)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>ValueIsPHI - <a href="/web-llvm/docs/api/namespaces/llvm/check">Check</a> if a value is a PHI. <a href="#ae1767e092b6e8e2a35c1574c6b6b6456">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">static <a href="/web-llvm/docs/api/classes/llvm/phinode">PHINode</a> *</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a7200de2cd7730b48c991d9d4062e90e7">ValueIsNewPHI</a> (Value *Val, SSAUpdater *Updater)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>ValueIsNewPHI - Like ValueIsPHI but also check if the PHI has no source operands, i.e., it was just added. <a href="#a7200de2cd7730b48c991d9d4062e90e7">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">static <a href="/web-llvm/docs/api/classes/llvm/value">Value</a> *</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a9632410a5210b4858d5ba8219f01161f">GetPHIValue</a> (PHINode *PHI)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>GetPHIValue - For the specified PHI instruction, return the value that it defines. <a href="#a9632410a5210b4858d5ba8219f01161f">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

</table>


<p>Definition at line 262 of file <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/utils/ssaupdater-cpp">SSAUpdater.cpp</a>.</p>


<div class="doxySectionDef">

## Public Member Typedefs

### BlkSucc\_iterator {#a72fcdee6ad8a3c4f2b3e7e2a5cee312c}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">using llvm::SSAUpdaterTraits&lt; SSAUpdater &gt;::BlkSucc_iterator =  succ_iterator</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 267 of file <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/utils/ssaupdater-cpp">SSAUpdater.cpp</a>.</p>

</div>
</div>

### BlkT {#a7afb60a9497715e7d488d83485bf5c21}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">using llvm::SSAUpdaterTraits&lt; SSAUpdater &gt;::BlkT =  BasicBlock</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 264 of file <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/utils/ssaupdater-cpp">SSAUpdater.cpp</a>.</p>

</div>
</div>

### PhiT {#a9d747ed8faca5ffa0815ba331e012281}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">using llvm::SSAUpdaterTraits&lt; SSAUpdater &gt;::PhiT =  PHINode</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 266 of file <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/utils/ssaupdater-cpp">SSAUpdater.cpp</a>.</p>

</div>
</div>

### ValT {#ae511ea4aef48e973b1b36c102b903955}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">using llvm::SSAUpdaterTraits&lt; SSAUpdater &gt;::ValT =  Value *</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 265 of file <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/utils/ssaupdater-cpp">SSAUpdater.cpp</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Public Static Functions

### AddPHIOperand() {#a7dbe4f9e5825611510efd0ab7516fc96}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void llvm::SSAUpdaterTraits&lt; SSAUpdater &gt;::AddPHIOperand (<a href="/web-llvm/docs/api/classes/llvm/phinode">PHINode</a> * PHI, <a href="/web-llvm/docs/api/classes/llvm/value">Value</a> * Val, <a href="/web-llvm/docs/api/classes/llvm/basicblock">BasicBlock</a> * Pred)</td>
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

<p>AddPHIOperand - Add the specified value as an operand of the PHI for the specified predecessor block.</p>

<p>Definition at line 327 of file <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/utils/ssaupdater-cpp">SSAUpdater.cpp</a>.</p>


<p>Reference <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/amdgpurewriteundefforphi-cpp/#a2e83cb1bc3f5e8986cbd14575755a134">PHI</a>.</p>

</div>
</div>

### BlkSucc\_begin() {#a32b52f992c85cb66b6b52a3d69e81dc6}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">BlkSucc_iterator llvm::SSAUpdaterTraits&lt; SSAUpdater &gt;::BlkSucc_begin (<a href="#a7afb60a9497715e7d488d83485bf5c21">BlkT</a> * BB)</td>
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



<p>Definition at line 269 of file <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/utils/ssaupdater-cpp">SSAUpdater.cpp</a>.</p>


<p>Reference <a href="/web-llvm/docs/api/namespaces/llvm/#a9aa408bc83db2292cc1a57a3e6b206c2">llvm::succ_begin</a>.</p>

</div>
</div>

### BlkSucc\_end() {#a2e581d0082c66a7ed5381efaab7fd9cb}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">BlkSucc_iterator llvm::SSAUpdaterTraits&lt; SSAUpdater &gt;::BlkSucc_end (<a href="#a7afb60a9497715e7d488d83485bf5c21">BlkT</a> * BB)</td>
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



<p>Definition at line 270 of file <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/utils/ssaupdater-cpp">SSAUpdater.cpp</a>.</p>


<p>Reference <a href="/web-llvm/docs/api/namespaces/llvm/#aa5684e4976198c1b64b694d3972ddf78">llvm::succ_end</a>.</p>

</div>
</div>

### CreateEmptyPHI() {#a6280f6984dd0e0455b73f22b3a5800c2}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">Value * llvm::SSAUpdaterTraits&lt; SSAUpdater &gt;::CreateEmptyPHI (<a href="/web-llvm/docs/api/classes/llvm/basicblock">BasicBlock</a> * BB, unsigned NumPreds, <a href="/web-llvm/docs/api/classes/llvm/ssaupdater">SSAUpdater</a> * Updater)</td>
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

<p>CreateEmptyPHI - Create a new PHI instruction in the specified block.</p>


<p>Reserve space for the operands but do not fill them in yet.</p>


<p>Definition at line 317 of file <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/utils/ssaupdater-cpp">SSAUpdater.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/classes/llvm/basicblock/#a0ed5f3ab3c2e4196ee0cffffa080c062">llvm::BasicBlock::begin</a>, <a href="/web-llvm/docs/api/classes/llvm/phinode/#af4aba918a76ca15bde1be3e14572e475">llvm::PHINode::Create</a> and <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/amdgpurewriteundefforphi-cpp/#a2e83cb1bc3f5e8986cbd14575755a134">PHI</a>.</p>

</div>
</div>

### FindPredecessorBlocks() {#a58a5535f6186eecaf32ad97b8461eff4}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void llvm::SSAUpdaterTraits&lt; SSAUpdater &gt;::FindPredecessorBlocks (<a href="/web-llvm/docs/api/classes/llvm/basicblock">BasicBlock</a> * BB, <a href="/web-llvm/docs/api/classes/llvm/smallvectorimpl">SmallVectorImpl</a>&lt; <a href="/web-llvm/docs/api/classes/llvm/basicblock">BasicBlock</a> * &gt; * Preds)</td>
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

<p>FindPredecessorBlocks - Put the predecessors of Info-&gt;BB into the Preds vector, set Info-&gt;NumPreds, and allocate space in Info-&gt;Preds.</p>

<p>Definition at line 298 of file <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/utils/ssaupdater-cpp">SSAUpdater.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/namespaces/llvm/#a39d3d23a084c4544ee5903203db10e8a">llvm::append_range</a>, <a href="/web-llvm/docs/api/classes/llvm/basicblock/#a0ed5f3ab3c2e4196ee0cffffa080c062">llvm::BasicBlock::begin</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a22eeee01734061ac1b31ccd994c49eef">llvm::dyn_cast</a> and <a href="/web-llvm/docs/api/namespaces/llvm/#acb22fb04083152eee862457e42e8dc31">llvm::predecessors</a>.</p>

</div>
</div>

### GetPHIValue() {#a9632410a5210b4858d5ba8219f01161f}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">Value * llvm::SSAUpdaterTraits&lt; SSAUpdater &gt;::GetPHIValue (<a href="/web-llvm/docs/api/classes/llvm/phinode">PHINode</a> * PHI)</td>
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

<p>GetPHIValue - For the specified PHI instruction, return the value that it defines.</p>

<p>Definition at line 347 of file <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/utils/ssaupdater-cpp">SSAUpdater.cpp</a>.</p>


<p>Reference <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/amdgpurewriteundefforphi-cpp/#a2e83cb1bc3f5e8986cbd14575755a134">PHI</a>.</p>

</div>
</div>

### GetPoisonVal() {#a9c944a235e8f62b5ed7b459ce1f01072}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">Value * llvm::SSAUpdaterTraits&lt; SSAUpdater &gt;::GetPoisonVal (<a href="/web-llvm/docs/api/classes/llvm/basicblock">BasicBlock</a> * BB, <a href="/web-llvm/docs/api/classes/llvm/ssaupdater">SSAUpdater</a> * Updater)</td>
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

<p>GetPoisonVal - Get a poison value of the same type as the value being handled.</p>

<p>Definition at line 311 of file <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/utils/ssaupdater-cpp">SSAUpdater.cpp</a>.</p>


<p>Reference <a href="/web-llvm/docs/api/classes/llvm/poisonvalue/#a1bf08613fb664a2e377a9a72c59a6b66">llvm::PoisonValue::get</a>.</p>

</div>
</div>

### PHI\_begin() {#a7234490e9abb681a170ebcea530ce0c6}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">PHI_iterator llvm::SSAUpdaterTraits&lt; SSAUpdater &gt;::PHI_begin (<a href="#a9d747ed8faca5ffa0815ba331e012281">PhiT</a> * PHI)</td>
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



<p>Definition at line 291 of file <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/utils/ssaupdater-cpp">SSAUpdater.cpp</a>.</p>


<p>Reference <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/amdgpurewriteundefforphi-cpp/#a2e83cb1bc3f5e8986cbd14575755a134">PHI</a>.</p>

</div>
</div>

### PHI\_end() {#acd0e2a55c9c480f7aa81c6a41bd180ab}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">PHI_iterator llvm::SSAUpdaterTraits&lt; SSAUpdater &gt;::PHI_end (<a href="#a9d747ed8faca5ffa0815ba331e012281">PhiT</a> * PHI)</td>
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



<p>Definition at line 292 of file <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/utils/ssaupdater-cpp">SSAUpdater.cpp</a>.</p>


<p>Reference <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/amdgpurewriteundefforphi-cpp/#a2e83cb1bc3f5e8986cbd14575755a134">PHI</a>.</p>

</div>
</div>

### ValueIsNewPHI() {#a7200de2cd7730b48c991d9d4062e90e7}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">PHINode * llvm::SSAUpdaterTraits&lt; SSAUpdater &gt;::ValueIsNewPHI (<a href="/web-llvm/docs/api/classes/llvm/value">Value</a> * Val, <a href="/web-llvm/docs/api/classes/llvm/ssaupdater">SSAUpdater</a> * Updater)</td>
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

<p>ValueIsNewPHI - Like ValueIsPHI but also check if the PHI has no source operands, i.e., it was just added.</p>

<p>Definition at line 338 of file <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/utils/ssaupdater-cpp">SSAUpdater.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/amdgpurewriteundefforphi-cpp/#a2e83cb1bc3f5e8986cbd14575755a134">PHI</a> and <a href="#ae1767e092b6e8e2a35c1574c6b6b6456">ValueIsPHI</a>.</p>

</div>
</div>

### ValueIsPHI() {#ae1767e092b6e8e2a35c1574c6b6b6456}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">PHINode * llvm::SSAUpdaterTraits&lt; SSAUpdater &gt;::ValueIsPHI (<a href="/web-llvm/docs/api/classes/llvm/value">Value</a> * Val, <a href="/web-llvm/docs/api/classes/llvm/ssaupdater">SSAUpdater</a> * Updater)</td>
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

<p>ValueIsPHI - <a href="/web-llvm/docs/api/namespaces/llvm/check">Check</a> if a value is a PHI.</p>

<p>Definition at line 332 of file <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/utils/ssaupdater-cpp">SSAUpdater.cpp</a>.</p>


<p>Reference <a href="/web-llvm/docs/api/namespaces/llvm/#a22eeee01734061ac1b31ccd994c49eef">llvm::dyn_cast</a>.</p>


<p>Referenced by <a href="#a7200de2cd7730b48c991d9d4062e90e7">ValueIsNewPHI</a>.</p>

</div>
</div>

</div>

<hr/>

The documentation for this class was generated from the following file:

<ul>
<li><a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/utils/ssaupdater-cpp">SSAUpdater.cpp</a></li>
</ul>

<hr/>

<p class="doxyGeneratedBy">Generated via <a href="https://github.com/xpack/doxygen2docusaurus">doxygen2docusaurus</a> by <a href="https://www.doxygen.nl">Doxygen</a> 1.14.0.</p>

</div>
