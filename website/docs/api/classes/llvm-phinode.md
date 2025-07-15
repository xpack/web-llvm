---

# DO NOT EDIT!
# Automatically generated via doxygen2docusaurus by Doxygen.

slug: /api/classes/llvm/phinode
custom_edit_url: null
toc_max_heading_level: 4
keywords:
  - doxygen
  - reference
  - class

---

<div class="doxyPage">

# The `PHINode` Class Reference



## Declaration

<div class="doxyDeclaration">
class llvm::PHINode { ... }
</div>

## Included Headers

<div class="doxyIncludesList">#include "<a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/ir/instructions-h">llvm/IR/Instructions.h</a>"
</div>

## Base class

<table class="doxyMembersIndex">

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">class</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/instruction">Instruction</a></td>
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

## Public Member Typedefs Index

<table class="doxyMembersIndex">

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">using</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a5349d6a485115701210ee1294ca8246b">block_iterator</a> = <a href="/web-llvm/docs/api/classes/llvm/basicblock">BasicBlock</a> **</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a770645ae7cfac7cf655d7c72b8aaaf2e">const_block_iterator</a> = <a href="/web-llvm/docs/api/classes/llvm/basicblock">BasicBlock</a> *<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> *</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a87273cb892a8182f137567e6b631695e">Instruction</a></td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Iterator for <span class="doxyComputerOutput"><a href="/web-llvm/docs/api/classes/llvm/instruction">Instruction</a></span>s in a `BasicBlock. <a href="#a87273cb892a8182f137567e6b631695e">More...</a></p>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a7cc0d5790da53c1cc1ab03981e269df2">PHINode</a> (const PHINode &amp;PN)</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a72e9a8461b1649b624b068b52bddf465">PHINode</a> (Type *Ty, unsigned NumReservedValues, const Twine &amp;NameStr="", InsertPosition InsertBefore=nullptr)</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ac7dcb39c5a2736eeb497e69dd703d25a">DECLARE_TRANSPARENT_OPERAND_ACCESSORS</a> (Value)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Provide fast operand accessors. <a href="#ac7dcb39c5a2736eeb497e69dd703d25a">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="#a770645ae7cfac7cf655d7c72b8aaaf2e">const_block_iterator</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a47670479395f375c7501109d25cb475f">block_begin</a> () const</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="#a770645ae7cfac7cf655d7c72b8aaaf2e">const_block_iterator</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#aaf337eae2193217943c7c0d7a65e61bb">block_end</a> () const</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/iterator-range">iterator_range</a>&lt; <a href="#a770645ae7cfac7cf655d7c72b8aaaf2e">const_block_iterator</a> &gt;</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a14cf6d7a36d091cb666cb83221b81d72">blocks</a> () const</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/user/#a917548288129e24325af275795e4622f">op_range</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a1f0ff79b64a40d383b891f1baba89c6b">incoming_values</a> ()</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/user/#a00c91d41d6da00a839684a27eff9b717">const_op_range</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#acff13ccb2e98a629e06757110178665f">incoming_values</a> () const</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#aef51af4b490af6b3bf2dfbc8737a8f9f">getNumIncomingValues</a> () const</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Return the number of incoming edges. <a href="#aef51af4b490af6b3bf2dfbc8737a8f9f">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/value">Value</a> *</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#aca1fd00f3ab63ec8f0f1ccc2093a9f6d">getIncomingValue</a> (unsigned i) const</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Return incoming value number x. <a href="#aca1fd00f3ab63ec8f0f1ccc2093a9f6d">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">void</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a88cdefb709309eddc6e5daca0be6a7b4">setIncomingValue</a> (unsigned i, Value *V)</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/basicblock">BasicBlock</a> *</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ac53e1aabdf64e91b8b325bcac250d8a9">getIncomingBlock</a> (unsigned i) const</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Return incoming basic block number <span class="doxyComputerOutput">i</span>. <a href="#ac53e1aabdf64e91b8b325bcac250d8a9">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/basicblock">BasicBlock</a> *</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ae7e053d6c8abe52081095ae208263ee9">getIncomingBlock</a> (const Use &amp;U) const</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Return incoming basic block corresponding to an operand of the PHI. <a href="#ae7e053d6c8abe52081095ae208263ee9">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/basicblock">BasicBlock</a> *</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a00af260cbec025b19b160364642715b9">getIncomingBlock</a> (Value::const_user_iterator I) const</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Return incoming basic block corresponding to value use iterator. <a href="#a00af260cbec025b19b160364642715b9">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">void</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a5ba57877c55dfdbe6e3bbfdacd9ef8c1">setIncomingBlock</a> (unsigned i, BasicBlock *BB)</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a9a296aeb1292ba6d7e2afa57e5ffe542">copyIncomingBlocks</a> (iterator_range&lt; const_block_iterator &gt; BBRange, uint32_t ToIdx=0)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Copies the basic blocks from <span class="doxyComputerOutput">BBRange</span> to the incoming basic block list of this <a href="/web-llvm/docs/api/classes/llvm/phinode">PHINode</a>, starting at <span class="doxyComputerOutput">ToIdx</span>. <a href="#a9a296aeb1292ba6d7e2afa57e5ffe542">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">void</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ae6c98d2f865894d646b95e8af8176a5d">replaceIncomingBlockWith</a> (const BasicBlock *Old, BasicBlock *New)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Replace every incoming basic block <span class="doxyComputerOutput">Old</span> to basic block <span class="doxyComputerOutput">New</span>. <a href="#ae6c98d2f865894d646b95e8af8176a5d">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">void</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a089cccb6f231efee72abc76d0f9c695f">addIncoming</a> (Value *V, BasicBlock *BB)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Add an incoming value to the end of the PHI list. <a href="#a089cccb6f231efee72abc76d0f9c695f">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/value">Value</a> *</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a6f01dbe965b38186b1a78378689d4105">removeIncomingValue</a> (unsigned Idx, bool DeletePHIIfEmpty=true)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Remove an incoming value. <a href="#a6f01dbe965b38186b1a78378689d4105">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/value">Value</a> *</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ad3b3f752c51597971949a3930b480ea8">removeIncomingValue</a> (const BasicBlock *BB, bool DeletePHIIfEmpty=true)</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a5197ef3eec835595e81bcecb4ee02969">removeIncomingValueIf</a> (function_ref&lt; bool(unsigned)&gt; Predicate, bool DeletePHIIfEmpty=true)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Remove all incoming values for which the predicate returns true. <a href="#a5197ef3eec835595e81bcecb4ee02969">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">int</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ae9562b96f6f3fa41bd36538c080035ee">getBasicBlockIndex</a> (const BasicBlock *BB) const</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Return the first index of the specified basic block in the value list for this PHI. <a href="#ae9562b96f6f3fa41bd36538c080035ee">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/value">Value</a> *</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ab2db7609ec72b1af2f91d47e40dc3722">getIncomingValueForBlock</a> (const BasicBlock *BB) const</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a506bcfb6f92a2184453e1fa9655f62a1">setIncomingValueForBlock</a> (const BasicBlock *BB, Value *V)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Set every incoming value(s) for block <span class="doxyComputerOutput">BB</span> to <span class="doxyComputerOutput">V</span>. <a href="#a506bcfb6f92a2184453e1fa9655f62a1">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/value">Value</a> *</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ace87755a2044122196774c1cb0368fde">hasConstantValue</a> () const</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>If the specified PHI node always merges together the same value, return the value, otherwise return null. <a href="#ace87755a2044122196774c1cb0368fde">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">bool</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a75454a3088d70df13b65e7b844e4b7a3">hasConstantOrUndefValue</a> () const</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Whether the specified PHI node always merges together the same value, assuming undefs are equal to a unique non-undef value. <a href="#a75454a3088d70df13b65e7b844e4b7a3">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">bool</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a12a188073b910647564952c1ca195386">isComplete</a> () const</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>If the PHI node is complete which means all of its parent's predecessors have incoming value in this PHI, return true, otherwise return false. <a href="#a12a188073b910647564952c1ca195386">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

</table>

## Protected Member Functions Index

<table class="doxyMembersIndex">

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/phinode">PHINode</a> *</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#add803ca8c80297f5eff951e84e7fc533">cloneImpl</a> () const</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a2d9bdd089124b3dfea76eb13c60ecac8">allocHungoffUses</a> (unsigned N)</td>
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

## Private Member Functions Index

<table class="doxyMembersIndex">

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">void</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a2db5b46b6f735552ffd2f9ac57419720">growOperands</a> ()</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>growOperands - grow operands - This grows the operand list in response to a push_back style of operation. <a href="#a2db5b46b6f735552ffd2f9ac57419720">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

</table>

## Private Member Attributes Index

<table class="doxyMembersIndex">

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">unsigned</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#abf5b03d4e2718e60e4f2f2f726c811f3">ReservedSpace</a></td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>The number of operands actually allocated. <a href="#abf5b03d4e2718e60e4f2f2f726c811f3">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

</table>

## Public Static Functions Index

<table class="doxyMembersIndex">

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">static <a href="/web-llvm/docs/api/classes/llvm/phinode">PHINode</a> *</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#af4aba918a76ca15bde1be3e14572e475">Create</a> (Type *Ty, unsigned NumReservedValues, const Twine &amp;NameStr="", InsertPosition InsertBefore=nullptr)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Constructors - NumReservedValues is a hint for the number of incoming edges that this phi node will have (use 0 if you really have no idea). <a href="#af4aba918a76ca15bde1be3e14572e475">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">static unsigned</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a928f57745ef3ec4a823afdf7100a70ad">getOperandNumForIncomingValue</a> (unsigned i)</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">static unsigned</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#aca414c43a6d42c13998208463637a20d">getIncomingValueNumForOperand</a> (unsigned i)</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">static bool</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a01d006e183e3236af8e564af83de197f">classof</a> (const Instruction *I)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Methods for support type inquiry through isa, cast, and dyn_cast: <a href="#a01d006e183e3236af8e564af83de197f">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">static bool</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a2759d9d8b288cd293f07d1c3a984bae3">classof</a> (const Value *V)</td>
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

## Private Static Attributes Index

<table class="doxyMembersIndex">

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">static constexpr <a href="/web-llvm/docs/api/structs/llvm/user/hungoffoperandsallocmarker">HungOffOperandsAllocMarker</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a394cb7794b91f99ed857e5e71ea45cf1">AllocMarker</a> {}</td>
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


<p>Definition at line 2600 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/ir/instructions-h">Instructions.h</a>.</p>


<div class="doxySectionDef">

## Public Member Typedefs

### block\_iterator {#a5349d6a485115701210ee1294ca8246b}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">using llvm::PHINode::block_iterator =  BasicBlock **</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 2650 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/ir/instructions-h">Instructions.h</a>.</p>

</div>
</div>

### const\_block\_iterator {#a770645ae7cfac7cf655d7c72b8aaaf2e}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">using llvm::PHINode::const_block_iterator =  BasicBlock * const *</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 2651 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/ir/instructions-h">Instructions.h</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Friends

### Instruction {#a87273cb892a8182f137567e6b631695e}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">friend class <a href="/web-llvm/docs/api/classes/llvm/instruction">Instruction</a></td>
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

<p>Iterator for <span class="doxyComputerOutput"><a href="/web-llvm/docs/api/classes/llvm/instruction">Instruction</a></span>s in a `BasicBlock.</p>


<p>/ \Returns an <a href="/web-llvm/docs/api/classes/llvm/sandboxir/instruction">sandboxir::Instruction</a> &amp; when derereferenced. class BBIterator { public: using difference_type = std::ptrdiff_t; using value_type = <a href="/web-llvm/docs/api/classes/llvm/instruction">Instruction</a>; using pointer = value_type *; using reference = value_type &amp;; using iterator_category = std::bidirectional_iterator_tag;</p>


<p>private: <a href="/web-llvm/docs/api/classes/llvm/basicblock">llvm::BasicBlock</a> *BB; <a href="/web-llvm/docs/api/classes/llvm/basicblock/#a98c0a84a5dfa8bce341c829709f171e5">llvm::BasicBlock::iterator</a> It; Context *Ctx; pointer getInstr(llvm::BasicBlock::iterator It) const;</p>


<p>public: BBIterator() : BB(nullptr), Ctx(nullptr) {} BBIterator(llvm::BasicBlock &lt;em&gt;BB, llvm::BasicBlock::iterator It, Context *Ctx) : BB(BB), It(It), Ctx(Ctx) {} reference operator() const { return *getInstr(It); } BBIterator &amp;operator++(); BBIterator operator++(int) { auto Copy = *this; ++*this; return Copy; } BBIterator &amp;operator--(); BBIterator operator--(int) { auto Copy = *this; –*this; return Copy; } bool operator==(const BBIterator &amp;Other) const { assert(Ctx == Other.Ctx &amp;&amp; "BBIterators in different context!"); return It == Other.It; } bool operator!=(const BBIterator &amp;Other) const { return !(*this == Other); } / \Returns the SBInstruction that corresponds to this iterator, or null if / the instruction is not found in the IR-to-SandboxIR tables. pointer get() const { return getInstr(It); } / \Returns the parent BB. <a href="/web-llvm/docs/api/classes/llvm/basicblock">BasicBlock</a> *getNodeParent() const; };</p>


<p>/ Contains a list of <a href="/web-llvm/docs/api/classes/llvm/sandboxir/instruction">sandboxir::Instruction</a>'s. class <a href="/web-llvm/docs/api/classes/llvm/basicblock">BasicBlock</a> : public <a href="/web-llvm/docs/api/classes/llvm/value">Value</a> { / Builds a graph that contains all values in <span class="doxyComputerOutput">BB</span> in their original form / i.e., no vectorization is taking place here. void buildBasicBlockFromLLVMIR(llvm::BasicBlock *LLVMBB); friend class Context; // For <span class="doxyComputerOutput">buildBasicBlockFromIR</span></p>


<p>Definition at line 2621 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/ir/instructions-h">Instructions.h</a>.</p>


<p>References <a href="#add803ca8c80297f5eff951e84e7fc533">cloneImpl</a> and <a href="#a87273cb892a8182f137567e6b631695e">Instruction</a>.</p>


<p>Referenced by <a href="#a01d006e183e3236af8e564af83de197f">classof</a> and <a href="#a87273cb892a8182f137567e6b631695e">Instruction</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Private Constructors

### PHINode() {#a7cc0d5790da53c1cc1ab03981e269df2}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">PHINode::PHINode (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/phinode">PHINode</a> &amp; PN)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Declaration at line 2607 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/ir/instructions-h">Instructions.h</a>, definition at line 125 of file <a href="/web-llvm/docs/api/files/lib/lib/ir/instructions-cpp">Instructions.cpp</a>.</p>

</div>
</div>

### PHINode() {#a72e9a8461b1649b624b068b52bddf465}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">llvm::PHINode::PHINode (<a href="/web-llvm/docs/api/classes/llvm/type">Type</a> * Ty, unsigned NumReservedValues, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/twine">Twine</a> &amp; NameStr="", <a href="/web-llvm/docs/api/classes/llvm/insertposition">InsertPosition</a> InsertBefore=nullptr)</td>
</tr>
</table>
</td>
<td class="doxyMemberLabelsRight">
<span class="doxyMemberLabels">
<span class="doxyMemberLabel inline">inline</span>
<span class="doxyMemberLabel explicit">explicit</span>
</span>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 2609 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/ir/instructions-h">Instructions.h</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Public Member Functions

### addIncoming() {#a089cccb6f231efee72abc76d0f9c695f}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void llvm::PHINode::addIncoming (<a href="/web-llvm/docs/api/classes/llvm/value">Value</a> * V, <a href="/web-llvm/docs/api/classes/llvm/basicblock">BasicBlock</a> * BB)</td>
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

<p>Add an incoming value to the end of the PHI list.</p>

<p>Definition at line 2735 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/ir/instructions-h">Instructions.h</a>.</p>


<p>References <a href="/web-llvm/docs/api/classes/llvm/instruction/#af10fa975001cd000bc6aaa88267d970f">llvm::Instruction::BasicBlock</a>, <a href="/web-llvm/docs/api/classes/llvm/user/#addec638786f763d967811b45cb662f1f">llvm::User::getNumOperands</a>, <a href="#a5ba57877c55dfdbe6e3bbfdacd9ef8c1">setIncomingBlock</a>, <a href="#a88cdefb709309eddc6e5daca0be6a7b4">setIncomingValue</a> and <a href="/web-llvm/docs/api/classes/llvm/user/#a715e8009737f71c4b3d2ea7d2abc33c4">llvm::User::setNumHungOffUseOperands</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/scalar/licm-cpp/#a25f0b41add9507b8eafadfbc4a090d6c">cloneInstructionInExitBlock</a>, <a href="/web-llvm/docs/api/classes/llvm/jumpthreadingpass/#a44f91224211f7d2538f311f9a916264d">llvm::JumpThreadingPass::cloneInstructions</a>, <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/utils/loopunrollruntime-cpp/#a399d7b7e2e6aec8e1ad80d3d73b7b1c8">CloneLoopBlocks</a>, <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/utils/loopunrollruntime-cpp/#a4ebed10d3e842e81a2df6974c2fd3760">ConnectEpilog</a>, <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/utils/loopunrollruntime-cpp/#af700561cb065af85122cd321d6c4b989">ConnectProlog</a>, <a href="/web-llvm/docs/api/classes/llvm/openmpirbuilder/#a445fa52d77040bccb16bfea111234a2e">llvm::OpenMPIRBuilder::createLoopSkeleton</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a16d5e17e2ce1be5012b2d00ab6d6669a">llvm::createMemCpyLoopKnownSize</a>, <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/utils/lowermemintrinsics-cpp/#a28eff59d4446b7289de152d575bf3cd0">createMemMoveLoopKnownSize</a>, <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/utils/lowermemintrinsics-cpp/#af1d16783f6f4b4d20427e93da6dd606f">createMemMoveLoopUnknownSize</a>, <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/utils/lowermemintrinsics-cpp/#a6472f2a2e040373d958419bde7523539">createMemSetLoop</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#aa650642c90f81466c2cd062e00ab152b">llvm::createPHIsForSplitLoopExit</a>, <a href="/web-llvm/docs/api/classes/anonymous-x86loweramxintrinsics-cpp-/x86loweramxintrinsics/#a5f7b74afe2d1d4f3cc3373cd8af2e6ad">anonymous{X86LowerAMXIntrinsics.cpp}::X86LowerAMXIntrinsics::createTileDPLoops</a>, <a href="/web-llvm/docs/api/classes/anonymous-x86loweramxintrinsics-cpp-/x86loweramxintrinsics/#a991aa40e1236f6093ee0c3d93628319c">anonymous{X86LowerAMXIntrinsics.cpp}::X86LowerAMXIntrinsics::createTileLoadStoreLoops</a>, <a href="/web-llvm/docs/api/files/lib/lib/codegen/codegenprepare-cpp/#adfad68845808cb6acd116e50b15bc281">despeculateCountZeros</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a833a6084a93d5900e8bdd493b37bbbc7">llvm::ehAwareSplitEdge</a>, <a href="/web-llvm/docs/api/classes/llvm/sitargetlowering/#aa7f6ff2830d775cf0c6a4052836c2552">llvm::SITargetLowering::emitExpandAtomicAddrSpacePredicate</a>, <a href="/web-llvm/docs/api/classes/llvm/instcombinerimpl/#ab05ba39ce6e678149dabd939c9ad4c3e">llvm::InstCombinerImpl::EvaluateInDifferentType</a>, <a href="/web-llvm/docs/api/classes/llvm/vppredinstphirecipe/#a3e63796e123d5ba9cbfa023983328c37">llvm::VPPredInstPHIRecipe::execute</a>, <a href="/web-llvm/docs/api/classes/llvm/vpwidenintorfpinductionrecipe/#a98d8cca54a99e8b64eb406f898565323">llvm::VPWidenIntOrFpInductionRecipe::execute</a>, <a href="/web-llvm/docs/api/classes/llvm/vpwidenpointerinductionrecipe/#ac53a5d033ba641288b6e15344d880186">llvm::VPWidenPointerInductionRecipe::execute</a>, <a href="/web-llvm/docs/api/files/lib/lib/codegen/expandlargefpconvert-cpp/#a46482b2bd77de78d901bfa2fd727ba0e">expandFPToI</a>, <a href="/web-llvm/docs/api/files/lib/lib/codegen/expandlargefpconvert-cpp/#a0f218e3451638c34910744dedf0b71ac">expandIToFP</a>, <a href="/web-llvm/docs/api/classes/llvm/innerloopvectorizer/#accb5ce221150790c36b2d96af1be821c">llvm::InnerLoopVectorizer::fixNonInductionPHIs</a>, <a href="/web-llvm/docs/api/classes/llvm/instcombinerimpl/#a9317f2efaf85a4afc7cde58a2c0d734b">llvm::InstCombinerImpl::foldBinopWithPhiOperands</a>, <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/instcombine/instructioncombining-cpp/#ad12cb02e2ee53655e834dcb84cd57333">foldGEPOfPhi</a>, <a href="/web-llvm/docs/api/classes/llvm/instcombinerimpl/#a6c028a26ae2c72e9018e5a80713ba819">llvm::InstCombinerImpl::foldICmpWithConstant</a>, <a href="/web-llvm/docs/api/classes/llvm/instcombinerimpl/#aab1473644ffe7926032a4e01ed4bad78">llvm::InstCombinerImpl::foldIntegerTypedPHI</a>, <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/aggressiveinstcombine/aggressiveinstcombine-cpp/#a4e1612deb487473177dba9b03302386c">foldMemChr</a>, <a href="/web-llvm/docs/api/classes/llvm/instcombinerimpl/#a2fc50d227d302eb98914f04bcc6634e1">llvm::InstCombinerImpl::foldOpIntoPhi</a>, <a href="/web-llvm/docs/api/classes/llvm/instcombinerimpl/#a4df124d92129ffa8748086388a420b73">llvm::InstCombinerImpl::foldPHIArgBinOpIntoPHI</a>, <a href="/web-llvm/docs/api/classes/llvm/instcombinerimpl/#acc9feb478a72bb822133b6eec00bef9f">llvm::InstCombinerImpl::foldPHIArgGEPIntoPHI</a>, <a href="/web-llvm/docs/api/classes/llvm/instcombinerimpl/#aa8a186c50cdf60ac11ae1d0b884d468d">llvm::InstCombinerImpl::foldPHIArgLoadIntoPHI</a>, <a href="/web-llvm/docs/api/classes/llvm/instcombinerimpl/#a7a3e32edb65b5b1c216d4454f14df21c">llvm::InstCombinerImpl::foldPHIArgOpIntoPHI</a>, <a href="/web-llvm/docs/api/classes/llvm/instcombinerimpl/#a84318f31145b081677697de64401238a">llvm::InstCombinerImpl::foldPHIArgZextsIntoPHI</a>, <a href="/web-llvm/docs/api/files/lib/lib/codegen/codegenprepare-cpp/#af950841a4443ffb7aff66ae75fee8442">foldURemOfLoopIncrement</a>, <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/utils/lcssa-cpp/#a03040e4a441982ab96f070a7f03cc910">formLCSSAForInstructionsImpl</a>, <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/utils/integerdivision-cpp/#ae01a605dfa5a83e767612e4124bb6e57">generateUnsignedDivisionCode</a>, <a href="/web-llvm/docs/api/classes/llvm/instcombiner/#ab98cb2aaf6e757aac9c471f85f113a50">llvm::InstCombiner::getFreelyInvertedImpl</a>, <a href="/web-llvm/docs/api/classes/anonymous-inlinefunction-cpp-/landingpadinlininginfo/#a232bc3cdcfa2bab0574af9b47ff90c41">anonymous{InlineFunction.cpp}::LandingPadInliningInfo::getInnerResumeDest</a>, <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/utils/amdgpuemitprintf-cpp/#af8ebafc2930bf25dfa6887c4b5bc2c33">getStrlenWithNull</a>, <a href="/web-llvm/docs/api/classes/llvm/ssaupdater/#a5b0e45dbba53e985f1b9c532fb5f200b">llvm::SSAUpdater::GetValueInMiddleOfBlock</a>, <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/instrumentation/controlheightreduction-cpp/#a071886a7b42adae6a171e653e04bd216">insertTrivialPHIs</a>, <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/utils/loopsimplify-cpp/#ae72984cd3577f73b7880883b12808a8c">insertUniqueBackedgeBlock</a>, <a href="/web-llvm/docs/api/groups/llvmccorevalueinstructionphinode/#ga0c2e68a50440ad888ae444807bcebde9">LLVMAddIncoming</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a0947c6f5b0bdcd54aa4a8447602f8283">llvm::lowerUnaryVectorIntrinsicAsLoop</a>, <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/utils/simplifycfg-cpp/#acc8066950deec241b4fafe0700ff5f2c">mergeCompatibleInvokesImpl</a>, <a href="/web-llvm/docs/api/classes/llvm/instcombinerimpl/#a9d9df487d54cc5567b4e0b1c8e0120a8">llvm::InstCombinerImpl::mergeStoreIntoSuccessor</a>, <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/scalar/loopinterchange-cpp/#a76f2308b91faa139968810fd02d26891">moveLCSSAPhis</a>, <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/coroutines/coroframe-cpp/#a642ec4238f02650fc1e70d5b4ac8d844">movePHIValuesToInsertedBlock</a>, <a href="/web-llvm/docs/api/namespaces/anonymous-lowerswitch-cpp-/#a77bc86cd5c15b83afe922fa7bbfe0f11">anonymous{LowerSwitch.cpp}::NewLeafBlock</a>, <a href="/web-llvm/docs/api/structs/anonymous-partialinlining-cpp-/partialinlinerimpl/functioncloner/#a759daba99f9b665ac7274d0dfe70ce09">anonymous{PartialInlining.cpp}::PartialInlinerImpl::FunctionCloner::normalizeReturnBlock</a>, <a href="/web-llvm/docs/api/classes/anonymous-x86loweramxtype-cpp-/x86loweramxcast/#ae812aaa917422c3c4b067cda1b1d7019">anonymous{X86LowerAMXType.cpp}::X86LowerAMXCast::optimizeAMXCastFromPhi</a>, <a href="/web-llvm/docs/api/classes/anonymous-amdgpulatecodegenprepare-cpp-/liveregoptimizer/#aa50432deded202fb241ca2c204e8137a">anonymous{AMDGPULateCodeGenPrepare.cpp}::LiveRegOptimizer::optimizeLiveType</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64targettransforminfo-cpp/#a53ef6f5be8cd25a33229fe16aca9d537">processPhiNode</a>, <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/utils/local-cpp/#ae7d61f8763322c1d7c8181f00798d9c5">redirectValuesFromPredecessorsToPhi</a>, <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/utils/simplifycfg-cpp/#aedfe10b7b8a1008ddaa4104f54e0b483">removeEmptyCleanup</a>, <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/instcombine/instcombinecompares-cpp/#a0aa7c68d8c3095ffc271ecceab16c86e">rewriteGEPAsOffset</a>, <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/scalar/sroa-cpp/#a670232d63153cd8cd2793b3106e80661">rewriteMemOpOfSelect</a>, <a href="/web-llvm/docs/api/structs/anonymous-promotememorytoregister-cpp-/promotemem2reg/#a31d32412508ee492e69d8695f88e6dcf">anonymous{PromoteMemoryToRegister.cpp}::PromoteMem2Reg::run</a>, <a href="/web-llvm/docs/api/structs/anonymous-memorysanitizer-cpp-/memorysanitizervisitor/#a8605e39e73fa355574fd811094481af4">anonymous{MemorySanitizer.cpp}::MemorySanitizerVisitor::runOnFunction</a>, <a href="/web-llvm/docs/api/classes/anonymous-numericalstabilitysanitizer-cpp-/numericalstabilitysanitizer/#afa4793367d34ae1fa72121a32b0545cb">anonymous{NumericalStabilitySanitizer.cpp}::NumericalStabilitySanitizer::sanitizeFunction</a>, <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/scalar/scalarizemaskedmemintrin-cpp/#a93ae09e320f176a41ae347e5f1dcd714">scalarizeMaskedCompressStore</a>, <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/scalar/scalarizemaskedmemintrin-cpp/#a144649d7f3db9e7517d70398cde534d8">scalarizeMaskedExpandLoad</a>, <a href="/web-llvm/docs/api/classes/llvm/jumpthreadingpass/#a064ce69a10374b5342954d481e21fa25">llvm::JumpThreadingPass::simplifyPartiallyRedundantLoad</a>, <a href="/web-llvm/docs/api/classes/llvm/instcombinerimpl/#ac8cb4401526dd424f15566e4501792f7">llvm::InstCombinerImpl::SliceUpIllegalIntegerPHI</a>, <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/scalar/sroa-cpp/#a80f5f1399bc814c650325a6c41e350e2">speculatePHINodeLoads</a>, <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/scalar/callsitesplitting-cpp/#afad0de1026bed50eff308033f7cd132b">splitCallSite</a>, <a href="/web-llvm/docs/api/classes/llvm/coro/anyretconabi/#adc7bbccb30409488c60813454af8c81d">llvm::coro::AnyRetconABI::splitCoroutine</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a502009030bffff8a6992f4e4eb9380f5">llvm::SplitIndirectBrCriticalEdges</a>, <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/utils/basicblockutils-cpp/#ae2c617685e87af2501e3d53323f91df7">SplitLandingPadPredecessorsImpl</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a2776b4c8cd41fd60781f7b9e18af9edb">llvm::splitLoopBound</a>, <a href="/web-llvm/docs/api/classes/llvm/jumpthreadingpass/#afed5e8a79fa550920f638708cc257bdf">llvm::JumpThreadingPass::threadGuard</a>, <a href="/web-llvm/docs/api/classes/llvm/jumpthreadingpass/#af1fb897c419e6a5080ecf54baf13f169">llvm::JumpThreadingPass::tryToUnfoldSelectInCurrBB</a>, <a href="/web-llvm/docs/api/namespaces/anonymous-dfajumpthreading-cpp-/#a37fd6f31f78116956f457b105ab4513c">anonymous{DFAJumpThreading.cpp}::unfold</a>, <a href="/web-llvm/docs/api/classes/llvm/jumpthreadingpass/#a7f1482a3531f0a99f5481d84bae6127e">llvm::JumpThreadingPass::unfoldSelectInstr</a>, <a href="/web-llvm/docs/api/namespaces/anonymous-unifyfunctionexitnodes-cpp-/#a06b5d6856fd9067830ab0477c0b13f31">anonymous{UnifyFunctionExitNodes.cpp}::unifyReturnBlocks</a>, <a href="/web-llvm/docs/api/classes/anonymous-amdgpuunifydivergentexitnodes-cpp-/amdgpuunifydivergentexitnodesimpl/#adb133e739b469808feb3635786aeaa01">anonymous{AMDGPUUnifyDivergentExitNodes.cpp}::AMDGPUUnifyDivergentExitNodesImpl::unifyReturnBlockSet</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#acd628d451ca9d9b021876d59f46e670b">llvm::UnrollRuntimeLoopRemainder</a>, <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/utils/basicblockutils-cpp/#a4fd3bc9dead8a151c4cdf8c60d497931">UpdatePHINodes</a>, <a href="/web-llvm/docs/api/classes/anonymous-dataflowsanitizer-cpp-/dfsanvisitor/#a3a5f2e657c4828861cdc11d66c9e0a78">anonymous{DataFlowSanitizer.cpp}::DFSanVisitor::visitPHINode</a> and <a href="/web-llvm/docs/api/classes/llvm/objectsizeoffsetevaluator/#a9a06c7811f1ea67a51787ab0de806b5a">llvm::ObjectSizeOffsetEvaluator::visitPHINode</a>.</p>

</div>
</div>

### block\_begin() {#a47670479395f375c7501109d25cb475f}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">const_block_iterator llvm::PHINode::block_begin ()</td>
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



<p>Definition at line 2653 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/ir/instructions-h">Instructions.h</a>.</p>


<p>Reference <a href="/web-llvm/docs/api/classes/llvm/user/#a2eeb1c7ed1cfe403f2ae0470e36c07e2">llvm::User::op_begin</a>.</p>


<p>Referenced by <a href="#aaf337eae2193217943c7c0d7a65e61bb">block_end</a>, <a href="#a14cf6d7a36d091cb666cb83221b81d72">blocks</a>, <a href="#a9a296aeb1292ba6d7e2afa57e5ffe542">copyIncomingBlocks</a>, <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/utils/local-cpp/#ab880924a451b73edfe368d53c3d8631c">EliminateDuplicatePHINodesSetBasedImpl</a>, <a href="#ae9562b96f6f3fa41bd36538c080035ee">getBasicBlockIndex</a>, <a href="#ac53e1aabdf64e91b8b325bcac250d8a9">getIncomingBlock</a>, <a href="#a5197ef3eec835595e81bcecb4ee02969">removeIncomingValueIf</a> and <a href="#a5ba57877c55dfdbe6e3bbfdacd9ef8c1">setIncomingBlock</a>.</p>

</div>
</div>

### block\_end() {#aaf337eae2193217943c7c0d7a65e61bb}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">const_block_iterator llvm::PHINode::block_end ()</td>
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



<p>Definition at line 2657 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/ir/instructions-h">Instructions.h</a>.</p>


<p>References <a href="#a47670479395f375c7501109d25cb475f">block_begin</a> and <a href="/web-llvm/docs/api/classes/llvm/user/#addec638786f763d967811b45cb662f1f">llvm::User::getNumOperands</a>.</p>


<p>Referenced by <a href="#a14cf6d7a36d091cb666cb83221b81d72">blocks</a>, <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/utils/local-cpp/#ab880924a451b73edfe368d53c3d8631c">EliminateDuplicatePHINodesSetBasedImpl</a> and <a href="#a5197ef3eec835595e81bcecb4ee02969">removeIncomingValueIf</a>.</p>

</div>
</div>

### blocks() {#a14cf6d7a36d091cb666cb83221b81d72}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">iterator_range&lt; const_block_iterator &gt; llvm::PHINode::blocks ()</td>
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



<p>Definition at line 2661 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/ir/instructions-h">Instructions.h</a>.</p>


<p>References <a href="#a47670479395f375c7501109d25cb475f">block_begin</a>, <a href="#aaf337eae2193217943c7c0d7a65e61bb">block_end</a> and <a href="/web-llvm/docs/api/namespaces/llvm/#a341215803e83773a3e97860dc291f121">llvm::make_range</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/classes/llvm/instcombinerimpl/#aab1473644ffe7926032a4e01ed4bad78">llvm::InstCombinerImpl::foldIntegerTypedPHI</a>, <a href="/web-llvm/docs/api/classes/llvm/instcombinerimpl/#a4df124d92129ffa8748086388a420b73">llvm::InstCombinerImpl::foldPHIArgBinOpIntoPHI</a>, <a href="/web-llvm/docs/api/classes/llvm/instcombinerimpl/#af4dbcb044eda11161781dfbf3f007f04">llvm::InstCombinerImpl::foldPHIArgExtractValueInstructionIntoPHI</a>, <a href="/web-llvm/docs/api/classes/llvm/instcombinerimpl/#acc9feb478a72bb822133b6eec00bef9f">llvm::InstCombinerImpl::foldPHIArgGEPIntoPHI</a>, <a href="/web-llvm/docs/api/classes/llvm/instcombinerimpl/#a29028fb86efd0ff0ea01f243f47684fc">llvm::InstCombinerImpl::foldPHIArgInsertValueInstructionIntoPHI</a>, <a href="/web-llvm/docs/api/classes/llvm/instcombinerimpl/#aa8a186c50cdf60ac11ae1d0b884d468d">llvm::InstCombinerImpl::foldPHIArgLoadIntoPHI</a>, <a href="/web-llvm/docs/api/classes/llvm/instcombinerimpl/#a7a3e32edb65b5b1c216d4454f14df21c">llvm::InstCombinerImpl::foldPHIArgOpIntoPHI</a>, <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/utils/simplifycfg-cpp/#a92fe4b2aa97a12f4a947e5ce99f05b15">foldTwoEntryPHINode</a>, <a href="/web-llvm/docs/api/files/lib/lib/analysis/valuetracking-cpp/#a2422018885327baa9a1a4c493e17811c">isNonEqualPHIs</a>, <a href="/web-llvm/docs/api/classes/anonymous-loopstrengthreduce-cpp-/lsrinstance/#a9bcf42be7435217d79cd175d4e6993d7">anonymous{LoopStrengthReduce.cpp}::LSRInstance::LSRInstance</a>, <a href="#a6f01dbe965b38186b1a78378689d4105">removeIncomingValue</a>, <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/instcombine/instcombinephi-cpp/#a86ed982844e004af01652f203eda23c0">simplifyUsingControlFlow</a>, <a href="/web-llvm/docs/api/classes/llvm/instcombinerimpl/#ac8cb4401526dd424f15566e4501792f7">llvm::InstCombinerImpl::SliceUpIllegalIntegerPHI</a> and <a href="/web-llvm/docs/api/classes/anonymous-dataflowsanitizer-cpp-/dfsanvisitor/#a3a5f2e657c4828861cdc11d66c9e0a78">anonymous{DataFlowSanitizer.cpp}::DFSanVisitor::visitPHINode</a>.</p>

</div>
</div>

### copyIncomingBlocks() {#a9a296aeb1292ba6d7e2afa57e5ffe542}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void llvm::PHINode::copyIncomingBlocks (<a href="/web-llvm/docs/api/classes/llvm/iterator-range">iterator_range</a>&lt; <a href="#a770645ae7cfac7cf655d7c72b8aaaf2e">const_block_iterator</a> &gt; BBRange, uint32_t ToIdx=0)</td>
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

<p>Copies the basic blocks from <span class="doxyComputerOutput">BBRange</span> to the incoming basic block list of this <a href="/web-llvm/docs/api/classes/llvm/phinode">PHINode</a>, starting at <span class="doxyComputerOutput">ToIdx</span>.</p>

<p>Definition at line 2720 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/ir/instructions-h">Instructions.h</a>.</p>


<p>References <a href="#a47670479395f375c7501109d25cb475f">block_begin</a> and <a href="/web-llvm/docs/api/namespaces/llvm/#abb650e853db0ddbb60411b885c499737">llvm::copy</a>.</p>


<p>Referenced by <a href="#a6f01dbe965b38186b1a78378689d4105">removeIncomingValue</a>.</p>

</div>
</div>

### DECLARE\_TRANSPARENT\_OPERAND\_ACCESSORS() {#ac7dcb39c5a2736eeb497e69dd703d25a}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">llvm::PHINode::DECLARE_TRANSPARENT_OPERAND_ACCESSORS (<a href="/web-llvm/docs/api/classes/llvm/value">Value</a>)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Provide fast operand accessors.</p>

<p>Definition at line 2643 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/ir/instructions-h">Instructions.h</a>.</p>

</div>
</div>

### getBasicBlockIndex() {#ae9562b96f6f3fa41bd36538c080035ee}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">int llvm::PHINode::getBasicBlockIndex (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/basicblock">BasicBlock</a> * BB)</td>
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

<p>Return the first index of the specified basic block in the value list for this PHI.</p>


<p>Returns -1 if no instance.</p>


<p>Definition at line 2768 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/ir/instructions-h">Instructions.h</a>.</p>


<p>References <a href="/web-llvm/docs/api/classes/llvm/instruction/#af10fa975001cd000bc6aaa88267d970f">llvm::Instruction::BasicBlock</a>, <a href="#a47670479395f375c7501109d25cb475f">block_begin</a> and <a href="/web-llvm/docs/api/classes/llvm/user/#addec638786f763d967811b45cb662f1f">llvm::User::getNumOperands</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/utils/loopunrollruntime-cpp/#a399d7b7e2e6aec8e1ad80d3d73b7b1c8">CloneLoopBlocks</a>, <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/utils/loopunrollruntime-cpp/#a4ebed10d3e842e81a2df6974c2fd3760">ConnectEpilog</a>, <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/scalar/loopidiomrecognize-cpp/#a3a0cafd820690b73a6169ab519d77d2a">detectShiftUntilLessThanIdiom</a>, <a href="#ab2db7609ec72b1af2f91d47e40dc3722">getIncomingValueForBlock</a>, <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/utils/simplifycfg-cpp/#ab99310a04afb6c28186b1a6428eb75b0">hoistConditionalLoadsStores</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#aca57f75a6554ba9ed3bc72ef7b7540de">llvm::isAlmostDeadIV</a>, <a href="#a12a188073b910647564952c1ca195386">isComplete</a>, <a href="/web-llvm/docs/api/namespaces/anonymous-lowerswitch-cpp-/#a77bc86cd5c15b83afe922fa7bbfe0f11">anonymous{LowerSwitch.cpp}::NewLeafBlock</a>, <a href="#ad3b3f752c51597971949a3930b480ea8">removeIncomingValue</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a4ab89e1812569bb89edf9e25c3582913">llvm::SplitKnownCriticalEdge</a> and <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/scalar/licm-cpp/#a0bb855d418108ea53140e71d7b35a2cd">splitPredecessorsOfLoopExit</a>.</p>

</div>
</div>

### getIncomingBlock() {#ac53e1aabdf64e91b8b325bcac250d8a9}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">BasicBlock * llvm::PHINode::getIncomingBlock (unsigned i)</td>
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

<p>Return incoming basic block number <span class="doxyComputerOutput">i</span>.</p>

<p>Definition at line 2695 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/ir/instructions-h">Instructions.h</a>.</p>


<p>References <a href="/web-llvm/docs/api/classes/llvm/instruction/#af10fa975001cd000bc6aaa88267d970f">llvm::Instruction::BasicBlock</a> and <a href="#a47670479395f375c7501109d25cb475f">block_begin</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/scalar/rewritestatepointsforgc-cpp/#a55b03f8424779067813a7747a82a0b45">AreEquivalentPhiNodes</a>, <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/utils/local-cpp/#aa8ec1591dd8e7639e5b5e1869b49e9b5">CanPropagatePredecessorsForPHIs</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#ae1a030c9a70b99fced16cc726e1ef9f9">llvm::CloneAndPruneIntoFromInst</a>, <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/scalar/licm-cpp/#a25f0b41add9507b8eafadfbc4a090d6c">cloneInstructionInExitBlock</a>, <a href="/web-llvm/docs/api/classes/llvm/functioncomparator/#aa359aa2850f74fbc9dbdb4650c13f4cf">llvm::FunctionComparator::cmpOperations</a>, <a href="/web-llvm/docs/api/files/lib/lib/analysis/valuetracking-cpp/#add650fe201d4951c7146442a8969cc59">ComputeNumSignBitsImpl</a>, <a href="/web-llvm/docs/api/classes/llvm/jumpthreadingpass/#a7524dbb403a24e9e73d4bca80baa768d">llvm::JumpThreadingPass::computeValueKnownInPredecessorsImpl</a>, <a href="/web-llvm/docs/api/classes/llvm/dominatortree/#afa37be9270ea603d5273c3f58e8a4c3f">llvm::DominatorTree::dominates</a>, <a href="/web-llvm/docs/api/classes/llvm/instcombinerimpl/#ab05ba39ce6e678149dabd939c9ad4c3e">llvm::InstCombinerImpl::EvaluateInDifferentType</a>, <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/scalar/rewritestatepointsforgc-cpp/#a3945796ab2f46a6790343e4c6230cdc5">findBasePointer</a>, <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/ipo/iroutliner-cpp/#a26b0639ceb3f28de2e6a283098c525b2">findCanonNumsForPHI</a>, <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/ipo/iroutliner-cpp/#a556a77d9b9acf322358b2c4131986b13">findOrCreatePHIInBlock</a>, <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/utils/loopsimplify-cpp/#a80a071231d638f7bf7976f9eb6478a4f">findPHIToPartitionLoops</a>, <a href="/web-llvm/docs/api/namespaces/anonymous-lowerswitch-cpp-/#aac383495fcc8fae9bf826d4d89467928">anonymous{LowerSwitch.cpp}::FixPhis</a>, <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/utils/simplifycfg-cpp/#ac0fb2da7eaa616e8ef8a8f52b981334b">foldCondBranchOnValueKnownInPredecessorImpl</a>, <a href="/web-llvm/docs/api/classes/llvm/instcombinerimpl/#aef28063eb280fec69a391dd35c51666e">llvm::InstCombinerImpl::foldFreezeIntoRecurrence</a>, <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/instcombine/instructioncombining-cpp/#ad12cb02e2ee53655e834dcb84cd57333">foldGEPOfPhi</a>, <a href="/web-llvm/docs/api/classes/llvm/instcombinerimpl/#a2fc50d227d302eb98914f04bcc6634e1">llvm::InstCombinerImpl::foldOpIntoPhi</a>, <a href="/web-llvm/docs/api/classes/llvm/instcombinerimpl/#a4df124d92129ffa8748086388a420b73">llvm::InstCombinerImpl::foldPHIArgBinOpIntoPHI</a>, <a href="/web-llvm/docs/api/classes/llvm/instcombinerimpl/#acc9feb478a72bb822133b6eec00bef9f">llvm::InstCombinerImpl::foldPHIArgGEPIntoPHI</a>, <a href="/web-llvm/docs/api/classes/llvm/instcombinerimpl/#aa8a186c50cdf60ac11ae1d0b884d468d">llvm::InstCombinerImpl::foldPHIArgLoadIntoPHI</a>, <a href="/web-llvm/docs/api/classes/llvm/instcombinerimpl/#a7a3e32edb65b5b1c216d4454f14df21c">llvm::InstCombinerImpl::foldPHIArgOpIntoPHI</a>, <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/utils/local-cpp/#a3bd9116f3c9e74b7c836560911000c8e">gatherIncomingValuesToPhi</a>, <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/ipo/iroutliner-cpp/#a1c7b2c4c8824cfb8d35c97f6923c3fe2">getGVNForPHINode</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a1a5751a2dd7306ff9a59eae6c1de8925">llvm::GetIfCondition</a>, <a href="#ae7e053d6c8abe52081095ae208263ee9">getIncomingBlock</a>, <a href="#a00af260cbec025b19b160364642715b9">getIncomingBlock</a>, <a href="/web-llvm/docs/api/files/lib/lib/analysis/scalarevolution-cpp/#af8996f55e648de5006cb39d80c65d60e">getOtherIncomingValue</a>, <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/utils/loopsimplify-cpp/#ae72984cd3577f73b7880883b12808a8c">insertUniqueBackedgeBlock</a>, <a href="/web-llvm/docs/api/files/lib/lib/analysis/valuetracking-cpp/#a50882a093546a573f3e879fc578f167d">isPowerOfTwoRecurrence</a>, <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/scalar/sroa-cpp/#aab37469c4748a495736ad163ac54e776">isSafePHIToSpeculate</a>, <a href="/web-llvm/docs/api/files/lib/lib/analysis/ivusers-cpp/#acd81badac05008b8ec9f327167344baa">IVUseShouldUsePostIncValue</a>, <a href="/web-llvm/docs/api/classes/anonymous-gvnsink-cpp-/modelledphi/#a3075f59b3c1d55b8e2a28a9b475689e8">anonymous{GVNSink.cpp}::ModelledPHI::ModelledPHI</a>, <a href="/web-llvm/docs/api/classes/llvm/jumpthreadingpass/#a66f4dcea5cb859a1234e2b71901a1031">llvm::JumpThreadingPass::processBranchOnPHI</a>, <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/utils/local-cpp/#ae7d61f8763322c1d7c8181f00798d9c5">redirectValuesFromPredecessorsToPhi</a>, <a href="#ae6c98d2f865894d646b95e8af8176a5d">replaceIncomingBlockWith</a>, <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/utils/local-cpp/#a705c6c2b8e570441356edb8db2dd8ddb">replaceUndefValuesInPhi</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/hexagon/hexagonisellowering-cpp/#a7bfadc5c94b9b71edf81dd6f9f5813be">returnEdge</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#acb5b48f89efd60ea799bb09abc1971ba">llvm::rewriteLoopExitValues</a>, <a href="/web-llvm/docs/api/structs/anonymous-promotememorytoregister-cpp-/promotemem2reg/#a31d32412508ee492e69d8695f88e6dcf">anonymous{PromoteMemoryToRegister.cpp}::PromoteMem2Reg::run</a>, <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/utils/loopsimplify-cpp/#add9d8e7cc38ac083f42ce6873a8defdd">separateNestedLoop</a>, <a href="#a506bcfb6f92a2184453e1fa9655f62a1">setIncomingValueForBlock</a>, <a href="/web-llvm/docs/api/structs/llvm/irsimilarity/irinstructiondata/#ab11b9d6834e7a409b18c71e0b19876f5">llvm::IRSimilarity::IRInstructionData::setPHIPredecessors</a>, <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/scalar/licm-cpp/#a52b8b307321627e612e77041260ece84">sink</a>, <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/scalar/loopsink-cpp/#a89374dd34ed723e45309afa9ac10eb83">sinkInstruction</a>, <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/scalar/sroa-cpp/#a80f5f1399bc814c650325a6c41e350e2">speculatePHINodeLoads</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a4ab89e1812569bb89edf9e25c3582913">llvm::SplitKnownCriticalEdge</a>, <a href="/web-llvm/docs/api/files/lib/lib/analysis/instructionsimplify-cpp/#a914ac5681f80badb866f2aee44fc509a">threadBinOpOverPHI</a>, <a href="/web-llvm/docs/api/files/lib/lib/analysis/instructionsimplify-cpp/#a1ec7a76fbddf5983969def6e47c0f177">threadCmpOverPHI</a>, <a href="/web-llvm/docs/api/classes/llvm/jumpthreadingpass/#ae4ca9bfe94c6cc3d952413c7907db47f">llvm::JumpThreadingPass::tryToUnfoldSelect</a>, <a href="/web-llvm/docs/api/classes/llvm/jumpthreadingpass/#aa0555f067de530264e995e433ebb7e42">llvm::JumpThreadingPass::tryToUnfoldSelect</a>, <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/utils/basicblockutils-cpp/#a4fd3bc9dead8a151c4cdf8c60d497931">UpdatePHINodes</a>, <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/scalar/jumpthreading-cpp/#ae5a9dfd216e7560889e2366f34ddd9f1">updatePredecessorProfileMetadata</a> and <a href="/web-llvm/docs/api/classes/llvm/instcombinerimpl/#a752efe4724ac3a97d07ee81d5f779c92">llvm::InstCombinerImpl::visitPHINode</a>.</p>

</div>
</div>

### getIncomingBlock() {#ae7e053d6c8abe52081095ae208263ee9}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">BasicBlock * llvm::PHINode::getIncomingBlock (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/use">Use</a> &amp; U)</td>
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

<p>Return incoming basic block corresponding to an operand of the PHI.</p>

<p>Definition at line 2702 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/ir/instructions-h">Instructions.h</a>.</p>


<p>References <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/silowercontrolflow-cpp/#a4868c5d81c5ccc98c47aeab6244346a0">assert</a>, <a href="/web-llvm/docs/api/classes/llvm/instruction/#af10fa975001cd000bc6aaa88267d970f">llvm::Instruction::BasicBlock</a>, <a href="#ac53e1aabdf64e91b8b325bcac250d8a9">getIncomingBlock</a> and <a href="/web-llvm/docs/api/classes/llvm/user/#a2eeb1c7ed1cfe403f2ae0470e36c07e2">llvm::User::op_begin</a>.</p>

</div>
</div>

### getIncomingBlock() {#a00af260cbec025b19b160364642715b9}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">BasicBlock * llvm::PHINode::getIncomingBlock (<a href="/web-llvm/docs/api/classes/llvm/value/#a146665db2d7a79fa164098370a3a34c4">Value::const_user_iterator</a> I)</td>
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

<p>Return incoming basic block corresponding to value use iterator.</p>

<p>Definition at line 2710 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/ir/instructions-h">Instructions.h</a>.</p>


<p>References <a href="/web-llvm/docs/api/classes/llvm/instruction/#af10fa975001cd000bc6aaa88267d970f">llvm::Instruction::BasicBlock</a>, <a href="#ac53e1aabdf64e91b8b325bcac250d8a9">getIncomingBlock</a> and <a href="/web-llvm/docs/api/files/lib/lib/support/md5-cpp/#ac0eafdc9ee161b71e7af98af736952fd">I</a>.</p>

</div>
</div>

### getIncomingValue() {#aca1fd00f3ab63ec8f0f1ccc2093a9f6d}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">Value * llvm::PHINode::getIncomingValue (unsigned i)</td>
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

<p>Return incoming value number x.</p>

<p>Definition at line 2675 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/ir/instructions-h">Instructions.h</a>.</p>


<p>Reference <a href="/web-llvm/docs/api/classes/llvm/user/#aa0a2cb1582d1cec317bd205085469ca1">llvm::User::getOperand</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/scalar/rewritestatepointsforgc-cpp/#a55b03f8424779067813a7747a82a0b45">AreEquivalentPhiNodes</a>, <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/instcombine/instcombinecasts-cpp/#a3d3ed8206aabad62293aeddd444bab9f">canEvaluateZExtd</a>, <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/utils/local-cpp/#aa8ec1591dd8e7639e5b5e1869b49e9b5">CanPropagatePredecessorsForPHIs</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#ae1a030c9a70b99fced16cc726e1ef9f9">llvm::CloneAndPruneIntoFromInst</a>, <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/utils/loopunrollruntime-cpp/#a399d7b7e2e6aec8e1ad80d3d73b7b1c8">CloneLoopBlocks</a>, <a href="/web-llvm/docs/api/files/lib/lib/analysis/valuetracking-cpp/#add650fe201d4951c7146442a8969cc59">ComputeNumSignBitsImpl</a>, <a href="/web-llvm/docs/api/classes/llvm/functionloweringinfo/#acada979e9424b6f61142bbca85a0fea0">llvm::FunctionLoweringInfo::ComputePHILiveOutRegInfo</a>, <a href="/web-llvm/docs/api/classes/llvm/jumpthreadingpass/#a7524dbb403a24e9e73d4bca80baa768d">llvm::JumpThreadingPass::computeValueKnownInPredecessorsImpl</a>, <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/scalar/loopidiomrecognize-cpp/#a3a0cafd820690b73a6169ab519d77d2a">detectShiftUntilLessThanIdiom</a>, <a href="/web-llvm/docs/api/classes/llvm/instcombinerimpl/#ab05ba39ce6e678149dabd939c9ad4c3e">llvm::InstCombinerImpl::EvaluateInDifferentType</a>, <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/scalar/rewritestatepointsforgc-cpp/#a3945796ab2f46a6790343e4c6230cdc5">findBasePointer</a>, <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/ipo/iroutliner-cpp/#a26b0639ceb3f28de2e6a283098c525b2">findCanonNumsForPHI</a>, <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/ipo/iroutliner-cpp/#a556a77d9b9acf322358b2c4131986b13">findOrCreatePHIInBlock</a>, <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/utils/loopsimplify-cpp/#a80a071231d638f7bf7976f9eb6478a4f">findPHIToPartitionLoops</a>, <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/instcombine/instcombinephi-cpp/#a3ef88a20b7b51243e963ed25e0e0c30e">foldDependentIVs</a>, <a href="/web-llvm/docs/api/classes/llvm/instcombinerimpl/#a2fc50d227d302eb98914f04bcc6634e1">llvm::InstCombinerImpl::foldOpIntoPhi</a>, <a href="/web-llvm/docs/api/classes/llvm/instcombinerimpl/#a4df124d92129ffa8748086388a420b73">llvm::InstCombinerImpl::foldPHIArgBinOpIntoPHI</a>, <a href="/web-llvm/docs/api/classes/llvm/instcombinerimpl/#af4dbcb044eda11161781dfbf3f007f04">llvm::InstCombinerImpl::foldPHIArgExtractValueInstructionIntoPHI</a>, <a href="/web-llvm/docs/api/classes/llvm/instcombinerimpl/#acc9feb478a72bb822133b6eec00bef9f">llvm::InstCombinerImpl::foldPHIArgGEPIntoPHI</a>, <a href="/web-llvm/docs/api/classes/llvm/instcombinerimpl/#a29028fb86efd0ff0ea01f243f47684fc">llvm::InstCombinerImpl::foldPHIArgInsertValueInstructionIntoPHI</a>, <a href="/web-llvm/docs/api/classes/llvm/instcombinerimpl/#abd122b6678d6a8f14b6ab6bc18863b27">llvm::InstCombinerImpl::foldPHIArgIntToPtrToPHI</a>, <a href="/web-llvm/docs/api/classes/llvm/instcombinerimpl/#aa8a186c50cdf60ac11ae1d0b884d468d">llvm::InstCombinerImpl::foldPHIArgLoadIntoPHI</a>, <a href="/web-llvm/docs/api/classes/llvm/instcombinerimpl/#a7a3e32edb65b5b1c216d4454f14df21c">llvm::InstCombinerImpl::foldPHIArgOpIntoPHI</a>, <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/utils/simplifycfg-cpp/#a92fe4b2aa97a12f4a947e5ce99f05b15">foldTwoEntryPHINode</a>, <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/utils/local-cpp/#a3bd9116f3c9e74b7c836560911000c8e">gatherIncomingValuesToPhi</a>, <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/ipo/iroutliner-cpp/#a1c7b2c4c8824cfb8d35c97f6923c3fe2">getGVNForPHINode</a>, <a href="#ab2db7609ec72b1af2f91d47e40dc3722">getIncomingValueForBlock</a>, <a href="/web-llvm/docs/api/files/lib/lib/analysis/scalarevolution-cpp/#af8996f55e648de5006cb39d80c65d60e">getOtherIncomingValue</a>, <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/instcombine/instcombineshifts-cpp/#ab2d3d519ed327a47cba69f5523785d2d">getShiftedValue</a>, <a href="#a75454a3088d70df13b65e7b844e4b7a3">hasConstantOrUndefValue</a>, <a href="#ace87755a2044122196774c1cb0368fde">hasConstantValue</a>, <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/utils/loopsimplify-cpp/#ae72984cd3577f73b7880883b12808a8c">insertUniqueBackedgeBlock</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#aca57f75a6554ba9ed3bc72ef7b7540de">llvm::isAlmostDeadIV</a>, <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/ipo/functionattrs-cpp/#a9ec948ba8709fe1041a2ec4a79cb6e4b">isReturnNonNull</a>, <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/scalar/sroa-cpp/#aab37469c4748a495736ad163ac54e776">isSafePHIToSpeculate</a>, <a href="/web-llvm/docs/api/files/lib/lib/analysis/valuetracking-cpp/#a80d334de5a0761d54421defdc6fbf55c">isSameUnderlyingObjectInLoop</a>, <a href="/web-llvm/docs/api/files/lib/lib/analysis/ivusers-cpp/#acd81badac05008b8ec9f327167344baa">IVUseShouldUsePostIncValue</a>, <a href="/web-llvm/docs/api/classes/anonymous-gvnsink-cpp-/modelledphi/#a3075f59b3c1d55b8e2a28a9b475689e8">anonymous{GVNSink.cpp}::ModelledPHI::ModelledPHI</a>, <a href="/web-llvm/docs/api/classes/llvm/instcombinerimpl/#ad6c837ffd3a1932f53de13120ad1551a">llvm::InstCombinerImpl::PHIArgMergedDebugLoc</a>, <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/utils/local-cpp/#ae7d61f8763322c1d7c8181f00798d9c5">redirectValuesFromPredecessorsToPhi</a>, <a href="#a6f01dbe965b38186b1a78378689d4105">removeIncomingValue</a>, <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/utils/local-cpp/#a705c6c2b8e570441356edb8db2dd8ddb">replaceUndefValuesInPhi</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/hexagon/hexagonisellowering-cpp/#a7bfadc5c94b9b71edf81dd6f9f5813be">returnEdge</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#acb5b48f89efd60ea799bb09abc1971ba">llvm::rewriteLoopExitValues</a>, <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/utils/loopsimplify-cpp/#add9d8e7cc38ac083f42ce6873a8defdd">separateNestedLoop</a>, <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/scalar/sroa-cpp/#a80f5f1399bc814c650325a6c41e350e2">speculatePHINodeLoads</a>, <a href="/web-llvm/docs/api/files/lib/lib/analysis/instructionsimplify-cpp/#a1ec7a76fbddf5983969def6e47c0f177">threadCmpOverPHI</a>, <a href="/web-llvm/docs/api/classes/llvm/jumpthreadingpass/#ae4ca9bfe94c6cc3d952413c7907db47f">llvm::JumpThreadingPass::tryToUnfoldSelect</a>, <a href="/web-llvm/docs/api/classes/llvm/jumpthreadingpass/#aa0555f067de530264e995e433ebb7e42">llvm::JumpThreadingPass::tryToUnfoldSelect</a>, <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/utils/basicblockutils-cpp/#a4fd3bc9dead8a151c4cdf8c60d497931">UpdatePHINodes</a>, <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/scalar/jumpthreading-cpp/#ae5a9dfd216e7560889e2366f34ddd9f1">updatePredecessorProfileMetadata</a> and <a href="/web-llvm/docs/api/classes/llvm/instcombinerimpl/#a752efe4724ac3a97d07ee81d5f779c92">llvm::InstCombinerImpl::visitPHINode</a>.</p>

</div>
</div>

### getIncomingValueForBlock() {#ab2db7609ec72b1af2f91d47e40dc3722}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">Value * llvm::PHINode::getIncomingValueForBlock (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/basicblock">BasicBlock</a> * BB)</td>
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



<p>Definition at line 2775 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/ir/instructions-h">Instructions.h</a>.</p>


<p>References <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/silowercontrolflow-cpp/#a4868c5d81c5ccc98c47aeab6244346a0">assert</a>, <a href="/web-llvm/docs/api/classes/llvm/instruction/#af10fa975001cd000bc6aaa88267d970f">llvm::Instruction::BasicBlock</a>, <a href="#ae9562b96f6f3fa41bd36538c080035ee">getBasicBlockIndex</a> and <a href="#aca1fd00f3ab63ec8f0f1ccc2093a9f6d">getIncomingValue</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/structs/anonymous-constraintelimination-cpp-/state/#a77dccdccff30d1cf89c684cf37cd85d8">anonymous{ConstraintElimination.cpp}::State::addInfoForInductions</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#aeacc9805af138ccb1d72bc3000ec5013">llvm::analyzeICmp</a>, <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/utils/local-cpp/#aa8ec1591dd8e7639e5b5e1869b49e9b5">CanPropagatePredecessorsForPHIs</a>, <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/scalar/loopflatten-cpp/#aadc8ada3f35f60d30e774a6daf23d02f">checkPHIs</a>, <a href="/web-llvm/docs/api/classes/llvm/jumpthreadingpass/#a44f91224211f7d2538f311f9a916264d">llvm::JumpThreadingPass::cloneInstructions</a>, <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/utils/looppeel-cpp/#a8478b291f8a10892334ba0bcf6a18528">cloneLoopBlocks</a>, <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/scalar/rewritestatepointsforgc-cpp/#a54a040cceb9c0ff9921d8eeec2966a55">computeLiveOutSeed</a>, <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/scalar/loopidiomrecognize-cpp/#a3a0cafd820690b73a6169ab519d77d2a">detectShiftUntilLessThanIdiom</a>, <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/scalar/loopidiomrecognize-cpp/#a7ff0d8853961745bbe8afef66fab99dc">detectShiftUntilZeroIdiom</a>, <a href="/web-llvm/docs/api/classes/llvm/jumpthreadingpass/#ac14ea98bd0e870e467ae0ddc75a9fa87">llvm::JumpThreadingPass::duplicateCondBranchOnPHIIntoPred</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a4cd89ca702a817aac3a4521dd2462a2e">llvm::DuplicateInstructionsInSplitBetween</a>, <a href="/web-llvm/docs/api/classes/llvm/evaluator/#aac9fd94c18d93885c8d947121ab9721e">llvm::Evaluator::EvaluateFunction</a>, <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/scalar/loopflatten-cpp/#a9bbea577bf401c708dc854d2dad600af">findLoopComponents</a>, <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/vectorize/loopvectorize-cpp/#a90ad8ccd396152c749068f986f2b751a">fixReductionScalarResumeWhenVectorizingEpilog</a>, <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/utils/simplifycfg-cpp/#ac0fb2da7eaa616e8ef8a8f52b981334b">foldCondBranchOnValueKnownInPredecessorImpl</a>, <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/utils/simplifycfg-cpp/#a92fe4b2aa97a12f4a947e5ce99f05b15">foldTwoEntryPHINode</a>, <a href="/web-llvm/docs/api/files/lib/lib/codegen/codegenprepare-cpp/#af950841a4443ffb7aff66ae75fee8442">foldURemOfLoopIncrement</a>, <a href="/web-llvm/docs/api/classes/llvm/loop/#ae731e6e33c2f2a9a6ebd1d51886ce534">llvm::Loop::getCanonicalInductionVariable</a>, <a href="/web-llvm/docs/api/files/lib/lib/codegen/codegenprepare-cpp/#a50cfddd4c98e75ef287c16996698dc1c">getIVIncrement</a>, <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/utils/simplifycfg-cpp/#ab99310a04afb6c28186b1a6428eb75b0">hoistConditionalLoadsStores</a>, <a href="/web-llvm/docs/api/files/lib/lib/analysis/valuetracking-cpp/#a2422018885327baa9a1a4c493e17811c">isNonEqualPHIs</a>, <a href="/web-llvm/docs/api/namespaces/anonymous-lowerswitch-cpp-/#a77bc86cd5c15b83afe922fa7bbfe0f11">anonymous{LowerSwitch.cpp}::NewLeafBlock</a>, <a href="/web-llvm/docs/api/structs/anonymous-partialinlining-cpp-/partialinlinerimpl/functioncloner/#a759daba99f9b665ac7274d0dfe70ce09">anonymous{PartialInlining.cpp}::PartialInlinerImpl::FunctionCloner::normalizeReturnBlock</a>, <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/vectorize/loopvectorize-cpp/#aae23f7e6fc37b0f1bb756f938023512c">preparePlanForEpilogueVectorLoop</a>, <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/utils/local-cpp/#ae7d61f8763322c1d7c8181f00798d9c5">redirectValuesFromPredecessorsToPhi</a>, <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/utils/simplifycfg-cpp/#aedfe10b7b8a1008ddaa4104f54e0b483">removeEmptyCleanup</a>, <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/scalar/indvarsimplify-cpp/#a649ac561acbab510055b0e8f48ca0617">replaceLoopPHINodesWithPreheaderValues</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a502009030bffff8a6992f4e4eb9380f5">llvm::SplitIndirectBrCriticalEdges</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#af78eb969de6e17fe20fa8834d3e9c9aa">llvm::UnrollLoop</a> and <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/utils/basicblockutils-cpp/#a4fd3bc9dead8a151c4cdf8c60d497931">UpdatePHINodes</a>.</p>

</div>
</div>

### getNumIncomingValues() {#aef51af4b490af6b3bf2dfbc8737a8f9f}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">unsigned llvm::PHINode::getNumIncomingValues ()</td>
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

<p>Return the number of incoming edges.</p>

<p>Definition at line 2671 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/ir/instructions-h">Instructions.h</a>.</p>


<p>Reference <a href="/web-llvm/docs/api/classes/llvm/user/#addec638786f763d967811b45cb662f1f">llvm::User::getNumOperands</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/structs/anonymous-constraintelimination-cpp-/state/#a77dccdccff30d1cf89c684cf37cd85d8">anonymous{ConstraintElimination.cpp}::State::addInfoForInductions</a>, <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/scalar/rewritestatepointsforgc-cpp/#a55b03f8424779067813a7747a82a0b45">AreEquivalentPhiNodes</a>, <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/instcombine/instcombinecasts-cpp/#a3d3ed8206aabad62293aeddd444bab9f">canEvaluateZExtd</a>, <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/utils/local-cpp/#aa8ec1591dd8e7639e5b5e1869b49e9b5">CanPropagatePredecessorsForPHIs</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#ae1a030c9a70b99fced16cc726e1ef9f9">llvm::CloneAndPruneIntoFromInst</a>, <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/scalar/licm-cpp/#a25f0b41add9507b8eafadfbc4a090d6c">cloneInstructionInExitBlock</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/x86/x86partialreduction-cpp/#aff1b71fb51fbfeefc8cb3c92021ee0de">collectLeaves</a>, <a href="/web-llvm/docs/api/files/lib/lib/analysis/valuetracking-cpp/#add650fe201d4951c7146442a8969cc59">ComputeNumSignBitsImpl</a>, <a href="/web-llvm/docs/api/classes/llvm/functionloweringinfo/#acada979e9424b6f61142bbca85a0fea0">llvm::FunctionLoweringInfo::ComputePHILiveOutRegInfo</a>, <a href="/web-llvm/docs/api/classes/llvm/jumpthreadingpass/#a7524dbb403a24e9e73d4bca80baa768d">llvm::JumpThreadingPass::computeValueKnownInPredecessorsImpl</a>, <a href="/web-llvm/docs/api/classes/llvm/instcombinerimpl/#ab05ba39ce6e678149dabd939c9ad4c3e">llvm::InstCombinerImpl::EvaluateInDifferentType</a>, <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/scalar/rewritestatepointsforgc-cpp/#a3945796ab2f46a6790343e4c6230cdc5">findBasePointer</a>, <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/ipo/iroutliner-cpp/#a26b0639ceb3f28de2e6a283098c525b2">findCanonNumsForPHI</a>, <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/ipo/iroutliner-cpp/#a556a77d9b9acf322358b2c4131986b13">findOrCreatePHIInBlock</a>, <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/utils/loopsimplify-cpp/#a80a071231d638f7bf7976f9eb6478a4f">findPHIToPartitionLoops</a>, <a href="/web-llvm/docs/api/namespaces/anonymous-lowerswitch-cpp-/#aac383495fcc8fae9bf826d4d89467928">anonymous{LowerSwitch.cpp}::FixPhis</a>, <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/utils/simplifycfg-cpp/#ac0fb2da7eaa616e8ef8a8f52b981334b">foldCondBranchOnValueKnownInPredecessorImpl</a>, <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/instcombine/instcombinephi-cpp/#a3ef88a20b7b51243e963ed25e0e0c30e">foldDependentIVs</a>, <a href="/web-llvm/docs/api/classes/llvm/instcombinerimpl/#aab1473644ffe7926032a4e01ed4bad78">llvm::InstCombinerImpl::foldIntegerTypedPHI</a>, <a href="/web-llvm/docs/api/classes/llvm/instcombinerimpl/#a2fc50d227d302eb98914f04bcc6634e1">llvm::InstCombinerImpl::foldOpIntoPhi</a>, <a href="/web-llvm/docs/api/classes/llvm/instcombinerimpl/#a4df124d92129ffa8748086388a420b73">llvm::InstCombinerImpl::foldPHIArgBinOpIntoPHI</a>, <a href="/web-llvm/docs/api/classes/llvm/instcombinerimpl/#af4dbcb044eda11161781dfbf3f007f04">llvm::InstCombinerImpl::foldPHIArgExtractValueInstructionIntoPHI</a>, <a href="/web-llvm/docs/api/classes/llvm/instcombinerimpl/#a29028fb86efd0ff0ea01f243f47684fc">llvm::InstCombinerImpl::foldPHIArgInsertValueInstructionIntoPHI</a>, <a href="/web-llvm/docs/api/classes/llvm/instcombinerimpl/#abd122b6678d6a8f14b6ab6bc18863b27">llvm::InstCombinerImpl::foldPHIArgIntToPtrToPHI</a>, <a href="/web-llvm/docs/api/classes/llvm/instcombinerimpl/#aa8a186c50cdf60ac11ae1d0b884d468d">llvm::InstCombinerImpl::foldPHIArgLoadIntoPHI</a>, <a href="/web-llvm/docs/api/classes/llvm/instcombinerimpl/#a7a3e32edb65b5b1c216d4454f14df21c">llvm::InstCombinerImpl::foldPHIArgOpIntoPHI</a>, <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/utils/lcssa-cpp/#a03040e4a441982ab96f070a7f03cc910">formLCSSAForInstructionsImpl</a>, <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/utils/local-cpp/#a3bd9116f3c9e74b7c836560911000c8e">gatherIncomingValuesToPhi</a>, <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/ipo/iroutliner-cpp/#a1c7b2c4c8824cfb8d35c97f6923c3fe2">getGVNForPHINode</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a1a5751a2dd7306ff9a59eae6c1de8925">llvm::GetIfCondition</a>, <a href="/web-llvm/docs/api/files/lib/lib/analysis/scalarevolution-cpp/#af8996f55e648de5006cb39d80c65d60e">getOtherIncomingValue</a>, <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/instcombine/instcombineshifts-cpp/#ab2d3d519ed327a47cba69f5523785d2d">getShiftedValue</a>, <a href="#a75454a3088d70df13b65e7b844e4b7a3">hasConstantOrUndefValue</a>, <a href="#ace87755a2044122196774c1cb0368fde">hasConstantValue</a>, <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/utils/loopsimplify-cpp/#ae72984cd3577f73b7880883b12808a8c">insertUniqueBackedgeBlock</a>, <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/ipo/functionattrs-cpp/#a9ec948ba8709fe1041a2ec4a79cb6e4b">isReturnNonNull</a>, <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/scalar/sroa-cpp/#aab37469c4748a495736ad163ac54e776">isSafePHIToSpeculate</a>, <a href="/web-llvm/docs/api/files/lib/lib/analysis/valuetracking-cpp/#a80d334de5a0761d54421defdc6fbf55c">isSameUnderlyingObjectInLoop</a>, <a href="/web-llvm/docs/api/files/lib/lib/analysis/ivusers-cpp/#acd81badac05008b8ec9f327167344baa">IVUseShouldUsePostIncValue</a>, <a href="/web-llvm/docs/api/classes/anonymous-gvnsink-cpp-/modelledphi/#a3075f59b3c1d55b8e2a28a9b475689e8">anonymous{GVNSink.cpp}::ModelledPHI::ModelledPHI</a>, <a href="/web-llvm/docs/api/structs/anonymous-partialinlining-cpp-/partialinlinerimpl/functioncloner/#a759daba99f9b665ac7274d0dfe70ce09">anonymous{PartialInlining.cpp}::PartialInlinerImpl::FunctionCloner::normalizeReturnBlock</a>, <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/ipo/iroutliner-cpp/#a84e785627d5ab55370b5fa402ad7193f">outputHasNonPHI</a>, <a href="/web-llvm/docs/api/classes/llvm/jumpthreadingpass/#a66f4dcea5cb859a1234e2b71901a1031">llvm::JumpThreadingPass::processBranchOnPHI</a>, <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/utils/local-cpp/#ae7d61f8763322c1d7c8181f00798d9c5">redirectValuesFromPredecessorsToPhi</a>, <a href="#a5197ef3eec835595e81bcecb4ee02969">removeIncomingValueIf</a>, <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/utils/local-cpp/#a705c6c2b8e570441356edb8db2dd8ddb">replaceUndefValuesInPhi</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/hexagon/hexagonisellowering-cpp/#a7bfadc5c94b9b71edf81dd6f9f5813be">returnEdge</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#acb5b48f89efd60ea799bb09abc1971ba">llvm::rewriteLoopExitValues</a>, <a href="/web-llvm/docs/api/structs/anonymous-promotememorytoregister-cpp-/promotemem2reg/#a31d32412508ee492e69d8695f88e6dcf">anonymous{PromoteMemoryToRegister.cpp}::PromoteMem2Reg::run</a>, <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/utils/loopsimplify-cpp/#add9d8e7cc38ac083f42ce6873a8defdd">separateNestedLoop</a>, <a href="/web-llvm/docs/api/structs/llvm/irsimilarity/irinstructiondata/#ab11b9d6834e7a409b18c71e0b19876f5">llvm::IRSimilarity::IRInstructionData::setPHIPredecessors</a>, <a href="/web-llvm/docs/api/classes/anonymous-simplifycfg-cpp-/simplifycfgopt/#a0cadca6f494db1ccdccb2256e49cb7fe">anonymous{SimplifyCFG.cpp}::SimplifyCFGOpt::simplifyOnce</a>, <a href="/web-llvm/docs/api/classes/llvm/instcombinerimpl/#ac8cb4401526dd424f15566e4501792f7">llvm::InstCombinerImpl::SliceUpIllegalIntegerPHI</a>, <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/scalar/sroa-cpp/#a80f5f1399bc814c650325a6c41e350e2">speculatePHINodeLoads</a>, <a href="/web-llvm/docs/api/files/lib/lib/analysis/instructionsimplify-cpp/#a1ec7a76fbddf5983969def6e47c0f177">threadCmpOverPHI</a>, <a href="/web-llvm/docs/api/classes/llvm/jumpthreadingpass/#ae4ca9bfe94c6cc3d952413c7907db47f">llvm::JumpThreadingPass::tryToUnfoldSelect</a>, <a href="/web-llvm/docs/api/classes/llvm/jumpthreadingpass/#aa0555f067de530264e995e433ebb7e42">llvm::JumpThreadingPass::tryToUnfoldSelect</a>, <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/utils/basicblockutils-cpp/#a4fd3bc9dead8a151c4cdf8c60d497931">UpdatePHINodes</a>, <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/scalar/jumpthreading-cpp/#ae5a9dfd216e7560889e2366f34ddd9f1">updatePredecessorProfileMetadata</a>, <a href="/web-llvm/docs/api/classes/anonymous-dataflowsanitizer-cpp-/dfsanvisitor/#a3a5f2e657c4828861cdc11d66c9e0a78">anonymous{DataFlowSanitizer.cpp}::DFSanVisitor::visitPHINode</a>, <a href="/web-llvm/docs/api/classes/llvm/instcombinerimpl/#a752efe4724ac3a97d07ee81d5f779c92">llvm::InstCombinerImpl::visitPHINode</a> and <a href="/web-llvm/docs/api/classes/llvm/objectsizeoffsetvisitor/#a7410acf190bc26941fa3f2662715097d">llvm::ObjectSizeOffsetVisitor::visitPHINode</a>.</p>

</div>
</div>

### hasConstantOrUndefValue() {#a75454a3088d70df13b65e7b844e4b7a3}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool PHINode::hasConstantOrUndefValue ()</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Whether the specified PHI node always merges together the same value, assuming undefs are equal to a unique non-undef value.</p>


<p>hasConstantOrUndefValue - Whether the specified PHI node always merges together the same value, assuming that undefs result in the same value as non-undefs.</p>


<p>Unlike <a href="#ace87755a2044122196774c1cb0368fde">hasConstantValue</a>, this does not return a value because the unique non-undef incoming value need not dominate the PHI node.</p>


<p>Declaration at line 2801 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/ir/instructions-h">Instructions.h</a>, definition at line 229 of file <a href="/web-llvm/docs/api/files/lib/lib/ir/instructions-cpp">Instructions.cpp</a>.</p>


<p>References <a href="#aca1fd00f3ab63ec8f0f1ccc2093a9f6d">getIncomingValue</a>, <a href="#aef51af4b490af6b3bf2dfbc8737a8f9f">getNumIncomingValues</a> and <a href="/web-llvm/docs/api/namespaces/llvm/#a92ca992e52dddc420f4b069cae06dfbe">llvm::isa</a>.</p>

</div>
</div>

### hasConstantValue() {#ace87755a2044122196774c1cb0368fde}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">Value * PHINode::hasConstantValue ()</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>If the specified PHI node always merges together the same value, return the value, otherwise return null.</p>


<p>hasConstantValue - If the specified PHI node always merges together the same value, return the value, otherwise return null.</p>


<p>Declaration at line 2796 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/ir/instructions-h">Instructions.h</a>, definition at line 209 of file <a href="/web-llvm/docs/api/files/lib/lib/ir/instructions-cpp">Instructions.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/classes/llvm/poisonvalue/#a1bf08613fb664a2e377a9a72c59a6b66">llvm::PoisonValue::get</a>, <a href="#aca1fd00f3ab63ec8f0f1ccc2093a9f6d">getIncomingValue</a>, <a href="#aef51af4b490af6b3bf2dfbc8737a8f9f">getNumIncomingValues</a> and <a href="/web-llvm/docs/api/classes/llvm/value/#a0344a49526443edf90cc0aef3abd3337">llvm::Value::getType</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/scalar/loopflatten-cpp/#aadc8ada3f35f60d30e774a6daf23d02f">checkPHIs</a> and <a href="/web-llvm/docs/api/classes/llvm/objectsizeoffsetevaluator/#a9a06c7811f1ea67a51787ab0de806b5a">llvm::ObjectSizeOffsetEvaluator::visitPHINode</a>.</p>

</div>
</div>

### incoming\_values() {#a1f0ff79b64a40d383b891f1baba89c6b}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">op_range llvm::PHINode::incoming_values ()</td>
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



<p>Definition at line 2665 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/ir/instructions-h">Instructions.h</a>.</p>


<p>Reference <a href="/web-llvm/docs/api/classes/llvm/user/#a0b931781aa589c6ebe64a76c1447e5b2">llvm::User::operands</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/instcombine/instcombinecasts-cpp/#a16e1399c07ad0fea0b83eaea29c1402e">canEvaluateSExtd</a>, <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/instcombine/instcombineshifts-cpp/#a74691e0259fabde06f09a8f8076a6517">canEvaluateShifted</a>, <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/instcombine/instcombinecasts-cpp/#aefd6331c5fd6ec51f6a9e5558f885f28">canEvaluateTruncated</a>, <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/utils/simplifycfg-cpp/#ac0fb2da7eaa616e8ef8a8f52b981334b">foldCondBranchOnValueKnownInPredecessorImpl</a>, <a href="/web-llvm/docs/api/classes/llvm/instcombinerimpl/#aef28063eb280fec69a391dd35c51666e">llvm::InstCombinerImpl::foldFreezeIntoRecurrence</a>, <a href="/web-llvm/docs/api/classes/llvm/instcombinerimpl/#aab1473644ffe7926032a4e01ed4bad78">llvm::InstCombinerImpl::foldIntegerTypedPHI</a>, <a href="/web-llvm/docs/api/classes/llvm/instcombinerimpl/#a4df124d92129ffa8748086388a420b73">llvm::InstCombinerImpl::foldPHIArgBinOpIntoPHI</a>, <a href="/web-llvm/docs/api/classes/llvm/instcombinerimpl/#af4dbcb044eda11161781dfbf3f007f04">llvm::InstCombinerImpl::foldPHIArgExtractValueInstructionIntoPHI</a>, <a href="/web-llvm/docs/api/classes/llvm/instcombinerimpl/#acc9feb478a72bb822133b6eec00bef9f">llvm::InstCombinerImpl::foldPHIArgGEPIntoPHI</a>, <a href="/web-llvm/docs/api/classes/llvm/instcombinerimpl/#a29028fb86efd0ff0ea01f243f47684fc">llvm::InstCombinerImpl::foldPHIArgInsertValueInstructionIntoPHI</a>, <a href="/web-llvm/docs/api/classes/llvm/instcombinerimpl/#aa8a186c50cdf60ac11ae1d0b884d468d">llvm::InstCombinerImpl::foldPHIArgLoadIntoPHI</a>, <a href="/web-llvm/docs/api/classes/llvm/instcombinerimpl/#a7a3e32edb65b5b1c216d4454f14df21c">llvm::InstCombinerImpl::foldPHIArgOpIntoPHI</a>, <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/ipo/functionattrs-cpp/#a46f0bc39f45a99f997c4f124c505fb50">isFunctionMallocLike</a>, <a href="/web-llvm/docs/api/groups/arcopt/#ga88b57387a1e0d73c6481fb274f076bb2">isInertARCValue</a>, <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/scalar/licm-cpp/#ad0eaec807c54661058d9a1aed11195d9">isTriviallyReplaceablePHI</a>, <a href="/web-llvm/docs/api/classes/llvm/instcombinerimpl/#ad6c837ffd3a1932f53de13120ad1551a">llvm::InstCombinerImpl::PHIArgMergedDebugLoc</a>, <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/instcombine/instcombinephi-cpp/#ad64d77ab93a00dbcc71e917573921ca9">PHIsEqualValue</a>, <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/instcombine/instcombinephi-cpp/#a86ed982844e004af01652f203eda23c0">simplifyUsingControlFlow</a>, <a href="/web-llvm/docs/api/classes/llvm/instcombinerimpl/#ac8cb4401526dd424f15566e4501792f7">llvm::InstCombinerImpl::SliceUpIllegalIntegerPHI</a>, <a href="/web-llvm/docs/api/files/lib/lib/analysis/instructionsimplify-cpp/#a914ac5681f80badb866f2aee44fc509a">threadBinOpOverPHI</a>, <a href="/web-llvm/docs/api/classes/llvm/instcombinerimpl/#a752efe4724ac3a97d07ee81d5f779c92">llvm::InstCombinerImpl::visitPHINode</a> and <a href="/web-llvm/docs/api/classes/llvm/objectsizeoffsetvisitor/#a7410acf190bc26941fa3f2662715097d">llvm::ObjectSizeOffsetVisitor::visitPHINode</a>.</p>

</div>
</div>

### incoming\_values() {#acff13ccb2e98a629e06757110178665f}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">const_op_range llvm::PHINode::incoming_values ()</td>
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



<p>Definition at line 2667 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/ir/instructions-h">Instructions.h</a>.</p>


<p>Reference <a href="/web-llvm/docs/api/classes/llvm/user/#a0b931781aa589c6ebe64a76c1447e5b2">llvm::User::operands</a>.</p>

</div>
</div>

### isComplete() {#a12a188073b910647564952c1ca195386}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool llvm::PHINode::isComplete ()</td>
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

<p>If the PHI node is complete which means all of its parent's predecessors have incoming value in this PHI, return true, otherwise return false.</p>

<p>Definition at line 2805 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/ir/instructions-h">Instructions.h</a>.</p>


<p>References <a href="/web-llvm/docs/api/namespaces/llvm/#a0d10fe510ced2849a8074fe81e5d04ce">llvm::all_of</a>, <a href="/web-llvm/docs/api/classes/llvm/instruction/#af10fa975001cd000bc6aaa88267d970f">llvm::Instruction::BasicBlock</a>, <a href="#ae9562b96f6f3fa41bd36538c080035ee">getBasicBlockIndex</a>, <a href="/web-llvm/docs/api/files/lib/lib/analysis/basicaliasanalysis-cpp/#a1b8850f1ed44c12bc3501175a71c251c">getParent</a> and <a href="/web-llvm/docs/api/namespaces/llvm/#acb22fb04083152eee862457e42e8dc31">llvm::predecessors</a>.</p>

</div>
</div>

### removeIncomingValue() {#a6f01dbe965b38186b1a78378689d4105}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">Value * PHINode::removeIncomingValue (unsigned Idx, bool DeletePHIIfEmpty=<a href="/web-llvm/docs/api/files/lib/lib/analysis/basicaliasanalysis-cpp/#af6d5cafbdfc5313e65d990120021a3ec">true</a>)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Remove an incoming value.</p>


<p>This is useful if a predecessor basic block is deleted. The value removed is returned.</p>


<p>If the last incoming value for a PHI node is removed (and DeletePHIIfEmpty is true), the PHI node is destroyed and any uses of it are replaced with dummy values. The only time there should be zero incoming values to a PHI node is when the block is dead, so this strategy is sound.</p>


<p>Declaration at line 2752 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/ir/instructions-h">Instructions.h</a>, definition at line 137 of file <a href="/web-llvm/docs/api/files/lib/lib/ir/instructions-cpp">Instructions.cpp</a>.</p>


<p>References <a href="#a14cf6d7a36d091cb666cb83221b81d72">blocks</a>, <a href="#a9a296aeb1292ba6d7e2afa57e5ffe542">copyIncomingBlocks</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a02981de53fb6ffd384d39addc4d25f37">llvm::drop_begin</a>, <a href="/web-llvm/docs/api/classes/llvm/instruction/#a601ee49a4c4e0babf29bd1cf09036570">llvm::Instruction::eraseFromParent</a>, <a href="/web-llvm/docs/api/classes/llvm/poisonvalue/#a1bf08613fb664a2e377a9a72c59a6b66">llvm::PoisonValue::get</a>, <a href="#aca1fd00f3ab63ec8f0f1ccc2093a9f6d">getIncomingValue</a>, <a href="/web-llvm/docs/api/classes/llvm/user/#addec638786f763d967811b45cb662f1f">llvm::User::getNumOperands</a>, <a href="/web-llvm/docs/api/classes/llvm/value/#a0344a49526443edf90cc0aef3abd3337">llvm::Value::getType</a>, <a href="/web-llvm/docs/api/classes/llvm/user/#a2eeb1c7ed1cfe403f2ae0470e36c07e2">llvm::User::op_begin</a>, <a href="/web-llvm/docs/api/classes/llvm/user/#af41f58e730804d10b91fcff39b035f74">llvm::User::op_end</a>, <a href="/web-llvm/docs/api/classes/llvm/value/#a3ab5fc45117b450e8bb04e564cb6e5f2">llvm::Value::replaceAllUsesWith</a> and <a href="/web-llvm/docs/api/classes/llvm/user/#a715e8009737f71c4b3d2ea7d2abc33c4">llvm::User::setNumHungOffUseOperands</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/namespaces/llvm/#ae1a030c9a70b99fced16cc726e1ef9f9">llvm::CloneAndPruneIntoFromInst</a>, <a href="/web-llvm/docs/api/namespaces/anonymous-lowerswitch-cpp-/#aac383495fcc8fae9bf826d4d89467928">anonymous{LowerSwitch.cpp}::FixPhis</a>, <a href="/web-llvm/docs/api/namespaces/anonymous-lowerswitch-cpp-/#a77bc86cd5c15b83afe922fa7bbfe0f11">anonymous{LowerSwitch.cpp}::NewLeafBlock</a>, <a href="/web-llvm/docs/api/structs/anonymous-partialinlining-cpp-/partialinlinerimpl/functioncloner/#a759daba99f9b665ac7274d0dfe70ce09">anonymous{PartialInlining.cpp}::PartialInlinerImpl::FunctionCloner::normalizeReturnBlock</a>, <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/utils/local-cpp/#ae7d61f8763322c1d7c8181f00798d9c5">redirectValuesFromPredecessorsToPhi</a>, <a href="#ad3b3f752c51597971949a3930b480ea8">removeIncomingValue</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a502009030bffff8a6992f4e4eb9380f5">llvm::SplitIndirectBrCriticalEdges</a>, <a href="/web-llvm/docs/api/namespaces/anonymous-dfajumpthreading-cpp-/#a37fd6f31f78116956f457b105ab4513c">anonymous{DFAJumpThreading.cpp}::unfold</a> and <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/utils/basicblockutils-cpp/#a4fd3bc9dead8a151c4cdf8c60d497931">UpdatePHINodes</a>.</p>

</div>
</div>

### removeIncomingValue() {#ad3b3f752c51597971949a3930b480ea8}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">Value * llvm::PHINode::removeIncomingValue (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/basicblock">BasicBlock</a> * BB, bool DeletePHIIfEmpty=<a href="/web-llvm/docs/api/files/lib/lib/analysis/basicaliasanalysis-cpp/#af6d5cafbdfc5313e65d990120021a3ec">true</a>)</td>
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



<p>Definition at line 2754 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/ir/instructions-h">Instructions.h</a>.</p>


<p>References <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/silowercontrolflow-cpp/#a4868c5d81c5ccc98c47aeab6244346a0">assert</a>, <a href="/web-llvm/docs/api/classes/llvm/instruction/#af10fa975001cd000bc6aaa88267d970f">llvm::Instruction::BasicBlock</a>, <a href="#ae9562b96f6f3fa41bd36538c080035ee">getBasicBlockIndex</a> and <a href="#a6f01dbe965b38186b1a78378689d4105">removeIncomingValue</a>.</p>

</div>
</div>

### removeIncomingValueIf() {#a5197ef3eec835595e81bcecb4ee02969}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void PHINode::removeIncomingValueIf (<a href="/web-llvm/docs/api/classes/llvm/function-ref">function_ref</a>&lt; bool(unsigned)&gt; Predicate, bool DeletePHIIfEmpty=<a href="/web-llvm/docs/api/files/lib/lib/analysis/basicaliasanalysis-cpp/#af6d5cafbdfc5313e65d990120021a3ec">true</a>)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Remove all incoming values for which the predicate returns true.</p>


<p>The predicate accepts the incoming value index.</p>


<p>Declaration at line 2762 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/ir/instructions-h">Instructions.h</a>, definition at line 161 of file <a href="/web-llvm/docs/api/files/lib/lib/ir/instructions-cpp">Instructions.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/classes/llvm/instruction/#af10fa975001cd000bc6aaa88267d970f">llvm::Instruction::BasicBlock</a>, <a href="#a47670479395f375c7501109d25cb475f">block_begin</a>, <a href="#aaf337eae2193217943c7c0d7a65e61bb">block_end</a>, <a href="/web-llvm/docs/api/classes/llvm/detail/densesetimpl/#ad409c2de8502b94c8a0b1193307c63b6">llvm::detail::DenseSetImpl&lt; ValueT, MapTy, ValueInfoT &gt;::contains</a>, <a href="/web-llvm/docs/api/classes/llvm/detail/densesetimpl/#a9a3c9d867ff6bde97841c2b7983f5c70">llvm::detail::DenseSetImpl&lt; ValueT, MapTy, ValueInfoT &gt;::empty</a>, <a href="/web-llvm/docs/api/classes/llvm/instruction/#a601ee49a4c4e0babf29bd1cf09036570">llvm::Instruction::eraseFromParent</a>, <a href="/web-llvm/docs/api/classes/llvm/poisonvalue/#a1bf08613fb664a2e377a9a72c59a6b66">llvm::PoisonValue::get</a>, <a href="#aef51af4b490af6b3bf2dfbc8737a8f9f">getNumIncomingValues</a>, <a href="/web-llvm/docs/api/classes/llvm/user/#addec638786f763d967811b45cb662f1f">llvm::User::getNumOperands</a>, <a href="/web-llvm/docs/api/classes/llvm/value/#a0344a49526443edf90cc0aef3abd3337">llvm::Value::getType</a>, <a href="/web-llvm/docs/api/classes/llvm/detail/densesetimpl/#a1b0f3ebdced8fce4b22c6a63b25d9525">llvm::detail::DenseSetImpl&lt; ValueT, MapTy, ValueInfoT &gt;::insert</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a341215803e83773a3e97860dc291f121">llvm::make_range</a>, <a href="/web-llvm/docs/api/classes/llvm/user/#af41f58e730804d10b91fcff39b035f74">llvm::User::op_end</a>, <a href="/web-llvm/docs/api/classes/llvm/user/#a0b931781aa589c6ebe64a76c1447e5b2">llvm::User::operands</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a9ec2517b6489e71067be03afebb4d350">llvm::remove_if</a>, <a href="/web-llvm/docs/api/classes/llvm/value/#a3ab5fc45117b450e8bb04e564cb6e5f2">llvm::Value::replaceAllUsesWith</a>, <a href="/web-llvm/docs/api/classes/llvm/user/#a715e8009737f71c4b3d2ea7d2abc33c4">llvm::User::setNumHungOffUseOperands</a> and <a href="/web-llvm/docs/api/classes/llvm/detail/densesetimpl/#a9a025cb106832026cd05c2b4648a699f">llvm::detail::DenseSetImpl&lt; ValueT, MapTy, ValueInfoT &gt;::size</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/utils/loopsimplify-cpp/#ae72984cd3577f73b7880883b12808a8c">insertUniqueBackedgeBlock</a> and <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/utils/basicblockutils-cpp/#a4fd3bc9dead8a151c4cdf8c60d497931">UpdatePHINodes</a>.</p>

</div>
</div>

### replaceIncomingBlockWith() {#ae6c98d2f865894d646b95e8af8176a5d}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void llvm::PHINode::replaceIncomingBlockWith (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/basicblock">BasicBlock</a> * Old, <a href="/web-llvm/docs/api/classes/llvm/basicblock">BasicBlock</a> * New)</td>
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

<p>Replace every incoming basic block <span class="doxyComputerOutput">Old</span> to basic block <span class="doxyComputerOutput">New</span>.</p>

<p>Definition at line 2726 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/ir/instructions-h">Instructions.h</a>.</p>


<p>References <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/demangle/itaniumdemangle-h/#a536e22898d28a9340a4204407a75ad5d">AbstractManglingParser&lt; Derived, Alloc &gt;::NumOps</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/silowercontrolflow-cpp/#a4868c5d81c5ccc98c47aeab6244346a0">assert</a>, <a href="/web-llvm/docs/api/classes/llvm/instruction/#af10fa975001cd000bc6aaa88267d970f">llvm::Instruction::BasicBlock</a>, <a href="#ac53e1aabdf64e91b8b325bcac250d8a9">getIncomingBlock</a>, <a href="/web-llvm/docs/api/classes/llvm/user/#addec638786f763d967811b45cb662f1f">llvm::User::getNumOperands</a> and <a href="#a5ba57877c55dfdbe6e3bbfdacd9ef8c1">setIncomingBlock</a>.</p>

</div>
</div>

### setIncomingBlock() {#a5ba57877c55dfdbe6e3bbfdacd9ef8c1}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void llvm::PHINode::setIncomingBlock (unsigned i, <a href="/web-llvm/docs/api/classes/llvm/basicblock">BasicBlock</a> * BB)</td>
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



<p>Definition at line 2714 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/ir/instructions-h">Instructions.h</a>.</p>


<p>References <a href="/web-llvm/docs/api/classes/llvm/instruction/#af10fa975001cd000bc6aaa88267d970f">llvm::Instruction::BasicBlock</a> and <a href="#a47670479395f375c7501109d25cb475f">block_begin</a>.</p>


<p>Referenced by <a href="#a089cccb6f231efee72abc76d0f9c695f">addIncoming</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#ae1a030c9a70b99fced16cc726e1ef9f9">llvm::CloneAndPruneIntoFromInst</a>, <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/utils/loopunrollruntime-cpp/#a399d7b7e2e6aec8e1ad80d3d73b7b1c8">CloneLoopBlocks</a>, <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/utils/loopunrollruntime-cpp/#a4ebed10d3e842e81a2df6974c2fd3760">ConnectEpilog</a>, <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/ipo/iroutliner-cpp/#a556a77d9b9acf322358b2c4131986b13">findOrCreatePHIInBlock</a>, <a href="/web-llvm/docs/api/namespaces/anonymous-lowerswitch-cpp-/#aac383495fcc8fae9bf826d4d89467928">anonymous{LowerSwitch.cpp}::FixPhis</a>, <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/utils/loopsimplify-cpp/#ae72984cd3577f73b7880883b12808a8c">insertUniqueBackedgeBlock</a>, <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/scalar/loopinterchange-cpp/#a76f2308b91faa139968810fd02d26891">moveLCSSAPhis</a>, <a href="/web-llvm/docs/api/namespaces/anonymous-lowerswitch-cpp-/#a77bc86cd5c15b83afe922fa7bbfe0f11">anonymous{LowerSwitch.cpp}::NewLeafBlock</a>, <a href="#ae6c98d2f865894d646b95e8af8176a5d">replaceIncomingBlockWith</a> and <a href="/web-llvm/docs/api/namespaces/llvm/#a4ab89e1812569bb89edf9e25c3582913">llvm::SplitKnownCriticalEdge</a>.</p>

</div>
</div>

### setIncomingValue() {#a88cdefb709309eddc6e5daca0be6a7b4}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void llvm::PHINode::setIncomingValue (unsigned i, <a href="/web-llvm/docs/api/classes/llvm/value">Value</a> * V)</td>
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



<p>Definition at line 2678 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/ir/instructions-h">Instructions.h</a>.</p>


<p>References <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/silowercontrolflow-cpp/#a4868c5d81c5ccc98c47aeab6244346a0">assert</a>, <a href="/web-llvm/docs/api/files/lib/lib/object/tapifile-cpp/#a913a691648e20063bbd278e8f02d8430">getType</a> and <a href="/web-llvm/docs/api/classes/llvm/user/#a5fa9b8e1842b354f64c1ba6be0a4a17f">llvm::User::setOperand</a>.</p>


<p>Referenced by <a href="#a089cccb6f231efee72abc76d0f9c695f">addIncoming</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#ae1a030c9a70b99fced16cc726e1ef9f9">llvm::CloneAndPruneIntoFromInst</a>, <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/utils/loopunrollruntime-cpp/#a399d7b7e2e6aec8e1ad80d3d73b7b1c8">CloneLoopBlocks</a>, <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/ipo/iroutliner-cpp/#a556a77d9b9acf322358b2c4131986b13">findOrCreatePHIInBlock</a>, <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/instcombine/instcombineshifts-cpp/#ab2d3d519ed327a47cba69f5523785d2d">getShiftedValue</a>, <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/utils/simplifycfg-cpp/#ab99310a04afb6c28186b1a6428eb75b0">hoistConditionalLoadsStores</a>, <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/utils/loopsimplify-cpp/#ae72984cd3577f73b7880883b12808a8c">insertUniqueBackedgeBlock</a>, <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/scalar/loopinterchange-cpp/#a76f2308b91faa139968810fd02d26891">moveLCSSAPhis</a>, <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/utils/local-cpp/#a705c6c2b8e570441356edb8db2dd8ddb">replaceUndefValuesInPhi</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#acb5b48f89efd60ea799bb09abc1971ba">llvm::rewriteLoopExitValues</a>, <a href="#a506bcfb6f92a2184453e1fa9655f62a1">setIncomingValueForBlock</a> and <a href="/web-llvm/docs/api/classes/llvm/jumpthreadingpass/#a7f1482a3531f0a99f5481d84bae6127e">llvm::JumpThreadingPass::unfoldSelectInstr</a>.</p>

</div>
</div>

### setIncomingValueForBlock() {#a506bcfb6f92a2184453e1fa9655f62a1}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void llvm::PHINode::setIncomingValueForBlock (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/basicblock">BasicBlock</a> * BB, <a href="/web-llvm/docs/api/classes/llvm/value">Value</a> * V)</td>
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

<p>Set every incoming value(s) for block <span class="doxyComputerOutput">BB</span> to <span class="doxyComputerOutput">V</span>.</p>

<p>Definition at line 2782 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/ir/instructions-h">Instructions.h</a>.</p>


<p>References <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/demangle/itaniumdemangle-h/#a536e22898d28a9340a4204407a75ad5d">AbstractManglingParser&lt; Derived, Alloc &gt;::NumOps</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/silowercontrolflow-cpp/#a4868c5d81c5ccc98c47aeab6244346a0">assert</a>, <a href="/web-llvm/docs/api/classes/llvm/instruction/#af10fa975001cd000bc6aaa88267d970f">llvm::Instruction::BasicBlock</a>, <a href="#ac53e1aabdf64e91b8b325bcac250d8a9">getIncomingBlock</a>, <a href="/web-llvm/docs/api/classes/llvm/user/#addec638786f763d967811b45cb662f1f">llvm::User::getNumOperands</a> and <a href="#a88cdefb709309eddc6e5daca0be6a7b4">setIncomingValue</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/utils/loopunrollruntime-cpp/#a4ebed10d3e842e81a2df6974c2fd3760">ConnectEpilog</a> and <a href="/web-llvm/docs/api/namespaces/llvm/#a2776b4c8cd41fd60781f7b9e18af9edb">llvm::splitLoopBound</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Protected Member Functions

### allocHungoffUses() {#a2d9bdd089124b3dfea76eb13c60ecac8}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void llvm::PHINode::allocHungoffUses (unsigned N)</td>
</tr>
</table>
</td>
<td class="doxyMemberLabelsRight">
<span class="doxyMemberLabels">
<span class="doxyMemberLabel inline">inline</span>
<span class="doxyMemberLabel protected">protected</span>
</span>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 2628 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/ir/instructions-h">Instructions.h</a>.</p>


<p>References <a href="/web-llvm/docs/api/classes/llvm/user/#a1f1febd65726339f65bf604c66f908c0">llvm::User::allocHungoffUses</a> and <a href="/web-llvm/docs/api/files/lib/lib/support/regcomp-c/#a0240ac851181b84ac374872dc5434ee4">N</a>.</p>

</div>
</div>

### cloneImpl() {#add803ca8c80297f5eff951e84e7fc533}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">PHINode * PHINode::cloneImpl ()</td>
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



<p>Declaration at line 2623 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/ir/instructions-h">Instructions.h</a>, definition at line 4410 of file <a href="/web-llvm/docs/api/files/lib/lib/ir/instructions-cpp">Instructions.cpp</a>.</p>


<p>Referenced by <a href="#a87273cb892a8182f137567e6b631695e">Instruction</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Private Member Functions

### growOperands() {#a2db5b46b6f735552ffd2f9ac57419720}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void PHINode::growOperands ()</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>growOperands - grow operands - This grows the operand list in response to a push_back style of operation.</p>


<p>This grows the number of ops by 1.5 times.</p>


<p>Declaration at line 2821 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/ir/instructions-h">Instructions.h</a>, definition at line 198 of file <a href="/web-llvm/docs/api/files/lib/lib/ir/instructions-cpp">Instructions.cpp</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Private Member Attributes

### ReservedSpace {#abf5b03d4e2718e60e4f2f2f726c811f3}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">unsigned llvm::PHINode::ReservedSpace</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>The number of operands actually allocated.</p>


<p>NumOperands is the number actually in use.</p>


<p>Definition at line 2605 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/ir/instructions-h">Instructions.h</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Public Static Functions

### classof() {#a01d006e183e3236af8e564af83de197f}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool llvm::PHINode::classof (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/instruction">Instruction</a> * I)</td>
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

<p>Methods for support type inquiry through isa, cast, and dyn_cast:</p>

<p>Definition at line 2813 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/ir/instructions-h">Instructions.h</a>.</p>


<p>References <a href="/web-llvm/docs/api/files/lib/lib/support/md5-cpp/#ac0eafdc9ee161b71e7af98af736952fd">I</a> and <a href="#a87273cb892a8182f137567e6b631695e">Instruction</a>.</p>


<p>Referenced by <a href="#a2759d9d8b288cd293f07d1c3a984bae3">classof</a>.</p>

</div>
</div>

### classof() {#a2759d9d8b288cd293f07d1c3a984bae3}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool llvm::PHINode::classof (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/value">Value</a> * V)</td>
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



<p>Definition at line 2816 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/ir/instructions-h">Instructions.h</a>.</p>


<p>References <a href="/web-llvm/docs/api/namespaces/llvm/#ac4fc845f5ed92de63cd4474f128f5fc5">llvm::cast</a>, <a href="#a01d006e183e3236af8e564af83de197f">classof</a> and <a href="/web-llvm/docs/api/namespaces/llvm/#a92ca992e52dddc420f4b069cae06dfbe">llvm::isa</a>.</p>

</div>
</div>

### Create() {#af4aba918a76ca15bde1be3e14572e475}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">PHINode * llvm::PHINode::Create (<a href="/web-llvm/docs/api/classes/llvm/type">Type</a> * Ty, unsigned NumReservedValues, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/twine">Twine</a> &amp; NameStr="", <a href="/web-llvm/docs/api/classes/llvm/insertposition">InsertPosition</a> InsertBefore=nullptr)</td>
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

<p>Constructors - NumReservedValues is a hint for the number of incoming edges that this phi node will have (use 0 if you really have no idea).</p>

<p>Definition at line 2635 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/ir/instructions-h">Instructions.h</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/scalar/simpleloopunswitch-cpp/#aea49493e2ae224d30cda2b3235d180b0">buildClonedLoopBlocks</a>, <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/utils/controlflowutils-cpp/#a0bfeadac5ccd4e56b4c5df9dc6bb8817">calcPredicateUsingBooleans</a>, <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/utils/controlflowutils-cpp/#a646829664451eb913bfa2f92920478ea">calcPredicateUsingInteger</a>, <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/scalar/licm-cpp/#a25f0b41add9507b8eafadfbc4a090d6c">cloneInstructionInExitBlock</a>, <a href="/web-llvm/docs/api/classes/llvm/jumpthreadingpass/#a44f91224211f7d2538f311f9a916264d">llvm::JumpThreadingPass::cloneInstructions</a>, <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/utils/loopunrollruntime-cpp/#a399d7b7e2e6aec8e1ad80d3d73b7b1c8">CloneLoopBlocks</a>, <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/utils/loopunrollruntime-cpp/#a4ebed10d3e842e81a2df6974c2fd3760">ConnectEpilog</a>, <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/utils/loopunrollruntime-cpp/#af700561cb065af85122cd321d6c4b989">ConnectProlog</a>, <a href="/web-llvm/docs/api/classes/llvm/ssaupdatertraits-7a064c1d92ba5b8b002a38239caa8eb3/#a6280f6984dd0e0455b73f22b3a5800c2">llvm::SSAUpdaterTraits&lt; SSAUpdater &gt;::CreateEmptyPHI</a>, <a href="/web-llvm/docs/api/classes/llvm/irbuilderbase/#a876fb556ecea804faa2cd8ad1e498ec3">llvm::IRBuilderBase::CreatePHI</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#aa650642c90f81466c2cd062e00ab152b">llvm::createPHIsForSplitLoopExit</a>, <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/utils/simplifycfg-cpp/#a5bb62631ba6a4be0ae02f7365ee4a7d7">ensureValueAvailableInSuccessor</a>, <a href="/web-llvm/docs/api/classes/llvm/instcombinerimpl/#ab05ba39ce6e678149dabd939c9ad4c3e">llvm::InstCombinerImpl::EvaluateInDifferentType</a>, <a href="/web-llvm/docs/api/structs/llvm/vpfirstorderrecurrencephirecipe/#a141e9946f635323d4da5e8b4b3f64e44">llvm::VPFirstOrderRecurrencePHIRecipe::execute</a>, <a href="/web-llvm/docs/api/classes/llvm/vpreductionphirecipe/#ad481483dac767c09d773266ba8b877e5">llvm::VPReductionPHIRecipe::execute</a>, <a href="/web-llvm/docs/api/classes/llvm/vpwidenintorfpinductionrecipe/#a98d8cca54a99e8b64eb406f898565323">llvm::VPWidenIntOrFpInductionRecipe::execute</a>, <a href="/web-llvm/docs/api/classes/llvm/vpwidenpointerinductionrecipe/#ac53a5d033ba641288b6e15344d880186">llvm::VPWidenPointerInductionRecipe::execute</a>, <a href="/web-llvm/docs/api/classes/llvm/instcombinerimpl/#a9317f2efaf85a4afc7cde58a2c0d734b">llvm::InstCombinerImpl::foldBinopWithPhiOperands</a>, <a href="/web-llvm/docs/api/classes/llvm/instcombinerimpl/#aab1473644ffe7926032a4e01ed4bad78">llvm::InstCombinerImpl::foldIntegerTypedPHI</a>, <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/aggressiveinstcombine/aggressiveinstcombine-cpp/#a4e1612deb487473177dba9b03302386c">foldMemChr</a>, <a href="/web-llvm/docs/api/classes/llvm/instcombinerimpl/#a2fc50d227d302eb98914f04bcc6634e1">llvm::InstCombinerImpl::foldOpIntoPhi</a>, <a href="/web-llvm/docs/api/classes/llvm/instcombinerimpl/#a4df124d92129ffa8748086388a420b73">llvm::InstCombinerImpl::foldPHIArgBinOpIntoPHI</a>, <a href="/web-llvm/docs/api/classes/llvm/instcombinerimpl/#af4dbcb044eda11161781dfbf3f007f04">llvm::InstCombinerImpl::foldPHIArgExtractValueInstructionIntoPHI</a>, <a href="/web-llvm/docs/api/classes/llvm/instcombinerimpl/#acc9feb478a72bb822133b6eec00bef9f">llvm::InstCombinerImpl::foldPHIArgGEPIntoPHI</a>, <a href="/web-llvm/docs/api/classes/llvm/instcombinerimpl/#a29028fb86efd0ff0ea01f243f47684fc">llvm::InstCombinerImpl::foldPHIArgInsertValueInstructionIntoPHI</a>, <a href="/web-llvm/docs/api/classes/llvm/instcombinerimpl/#aa8a186c50cdf60ac11ae1d0b884d468d">llvm::InstCombinerImpl::foldPHIArgLoadIntoPHI</a>, <a href="/web-llvm/docs/api/classes/llvm/instcombinerimpl/#a7a3e32edb65b5b1c216d4454f14df21c">llvm::InstCombinerImpl::foldPHIArgOpIntoPHI</a>, <a href="/web-llvm/docs/api/classes/llvm/instcombinerimpl/#a84318f31145b081677697de64401238a">llvm::InstCombinerImpl::foldPHIArgZextsIntoPHI</a>, <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/utils/lcssa-cpp/#a03040e4a441982ab96f070a7f03cc910">formLCSSAForInstructionsImpl</a>, <a href="/web-llvm/docs/api/classes/anonymous-inlinefunction-cpp-/landingpadinlininginfo/#a232bc3cdcfa2bab0574af9b47ff90c41">anonymous{InlineFunction.cpp}::LandingPadInliningInfo::getInnerResumeDest</a>, <a href="/web-llvm/docs/api/classes/llvm/ssaupdater/#a5b0e45dbba53e985f1b9c532fb5f200b">llvm::SSAUpdater::GetValueInMiddleOfBlock</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#ab5a3ac0a249da0743dac1bd816d8e5d5">llvm::InlineFunction</a>, <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/instrumentation/controlheightreduction-cpp/#a071886a7b42adae6a171e653e04bd216">insertTrivialPHIs</a>, <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/utils/loopsimplify-cpp/#ae72984cd3577f73b7880883b12808a8c">insertUniqueBackedgeBlock</a>, <a href="/web-llvm/docs/api/structs/anonymous-attributorattributes-cpp-/aaindirectcallinfocallsite/#afc99e48bf0eed3b2fc9a2c3b25e3bd73">anonymous{AttributorAttributes.cpp}::AAIndirectCallInfoCallSite::manifest</a>, <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/utils/simplifycfg-cpp/#acc8066950deec241b4fafe0700ff5f2c">mergeCompatibleInvokesImpl</a>, <a href="/web-llvm/docs/api/classes/llvm/instcombinerimpl/#a9d9df487d54cc5567b4e0b1c8e0120a8">llvm::InstCombinerImpl::mergeStoreIntoSuccessor</a>, <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/coroutines/coroframe-cpp/#a642ec4238f02650fc1e70d5b4ac8d844">movePHIValuesToInsertedBlock</a>, <a href="/web-llvm/docs/api/classes/llvm/insertphistrategy/#a55f9b306ebb441abea69179650c2a4ad">llvm::InsertPHIStrategy::mutate</a>, <a href="/web-llvm/docs/api/structs/anonymous-partialinlining-cpp-/partialinlinerimpl/functioncloner/#a759daba99f9b665ac7274d0dfe70ce09">anonymous{PartialInlining.cpp}::PartialInlinerImpl::FunctionCloner::normalizeReturnBlock</a>, <a href="/web-llvm/docs/api/classes/anonymous-amdgpulatecodegenprepare-cpp-/liveregoptimizer/#aa50432deded202fb241ca2c204e8137a">anonymous{AMDGPULateCodeGenPrepare.cpp}::LiveRegOptimizer::optimizeLiveType</a>, <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/scalar/simplifycfgpass-cpp/#aec97a6e447a45c9027b71a487f5732ec">performBlockTailMerging</a>, <a href="/web-llvm/docs/api/classes/anonymous-looploadelimination-cpp-/loadeliminationforloop/#acc9ee85c11fa2173c85a1ba82797d9fb">anonymous{LoopLoadElimination.cpp}::LoadEliminationForLoop::propagateStoredValueToLoadUsers</a>, <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/utils/controlflowutils-cpp/#a1f69c303174793beec42b1ebaf13cfb6">reconnectPhis</a>, <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/instcombine/instcombinecompares-cpp/#a0aa7c68d8c3095ffc271ecceab16c86e">rewriteGEPAsOffset</a>, <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/scalar/sroa-cpp/#a670232d63153cd8cd2793b3106e80661">rewriteMemOpOfSelect</a>, <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/scalar/simpleloopunswitch-cpp/#a9a1db01205f9a51a14b99e53e3068da1">rewritePHINodesForExitAndUnswitchedBlocks</a>, <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/coroutines/coroframe-cpp/#a5a93b5fcf433128b2fd9d563792eb4cd">rewritePHIs</a>, <a href="/web-llvm/docs/api/files/lib/lib/codegen/indirectbrexpandpass-cpp/#a241c916e6342b5f14a7492f1b91cc715">runImpl</a>, <a href="/web-llvm/docs/api/classes/llvm/jumpthreadingpass/#a064ce69a10374b5342954d481e21fa25">llvm::JumpThreadingPass::simplifyPartiallyRedundantLoad</a>, <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/utils/simplifycfg-cpp/#abf69483b802f1e342399912142341c60">sinkLastInstruction</a>, <a href="/web-llvm/docs/api/classes/llvm/instcombinerimpl/#ac8cb4401526dd424f15566e4501792f7">llvm::InstCombinerImpl::SliceUpIllegalIntegerPHI</a>, <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/scalar/callsitesplitting-cpp/#afad0de1026bed50eff308033f7cd132b">splitCallSite</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a502009030bffff8a6992f4e4eb9380f5">llvm::SplitIndirectBrCriticalEdges</a>, <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/utils/basicblockutils-cpp/#ae2c617685e87af2501e3d53323f91df7">SplitLandingPadPredecessorsImpl</a>, <a href="/web-llvm/docs/api/classes/llvm/jumpthreadingpass/#afed5e8a79fa550920f638708cc257bdf">llvm::JumpThreadingPass::threadGuard</a>, <a href="/web-llvm/docs/api/classes/llvm/jumpthreadingpass/#af1fb897c419e6a5080ecf54baf13f169">llvm::JumpThreadingPass::tryToUnfoldSelectInCurrBB</a>, <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/scalar/simpleloopunswitch-cpp/#a2e6301db15e4516c92e21f33761886c6">turnSelectIntoBranch</a>, <a href="/web-llvm/docs/api/namespaces/anonymous-dfajumpthreading-cpp-/#a37fd6f31f78116956f457b105ab4513c">anonymous{DFAJumpThreading.cpp}::unfold</a>, <a href="/web-llvm/docs/api/namespaces/anonymous-unifyfunctionexitnodes-cpp-/#a06b5d6856fd9067830ab0477c0b13f31">anonymous{UnifyFunctionExitNodes.cpp}::unifyReturnBlocks</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#acd628d451ca9d9b021876d59f46e670b">llvm::UnrollRuntimeLoopRemainder</a>, <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/utils/basicblockutils-cpp/#a4fd3bc9dead8a151c4cdf8c60d497931">UpdatePHINodes</a>, <a href="/web-llvm/docs/api/classes/anonymous-dataflowsanitizer-cpp-/dfsanvisitor/#a3a5f2e657c4828861cdc11d66c9e0a78">anonymous{DataFlowSanitizer.cpp}::DFSanVisitor::visitPHINode</a> and <a href="/web-llvm/docs/api/classes/anonymous-simplifyindvar-cpp-/wideniv/#a39eadf98e4773739cd4e7b4befee6fb5">anonymous{SimplifyIndVar.cpp}::WidenIV::widenIVUse</a>.</p>

</div>
</div>

### getIncomingValueNumForOperand() {#aca414c43a6d42c13998208463637a20d}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">unsigned llvm::PHINode::getIncomingValueNumForOperand (unsigned i)</td>
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



<p>Definition at line 2689 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/ir/instructions-h">Instructions.h</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/classes/llvm/sandboxir/phinode/#ad83e0971736712b3d8e93cb35b0cadc9">llvm::sandboxir::PHINode::getIncomingValueNumForOperand</a>, <a href="/web-llvm/docs/api/classes/anonymous-loopinterchange-cpp-/loopinterchangelegality/#ade3ca81f3a303345f66492c713c0e4ec">anonymous{LoopInterchange.cpp}::LoopInterchangeLegality::isLoopStructureUnderstood</a>, <a href="/web-llvm/docs/api/classes/anonymous-objcarccontract-cpp-/objcarccontract/#a6b6cfbee1f1d7c9f17eb52722c89564d">anonymous{ObjCARCContract.cpp}::ObjCARCContract::run</a>, <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/scalar/sink-cpp/#afa4c018bf923954bfd4ce5b6bf15b68b">SinkInstruction</a> and <a href="/web-llvm/docs/api/classes/llvm/innerloopvectorizer/#a0a5c60e5cebd520f95b9813fd9807016">llvm::InnerLoopVectorizer::sinkScalarOperands</a>.</p>

</div>
</div>

### getOperandNumForIncomingValue() {#a928f57745ef3ec4a823afdf7100a70ad}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">unsigned llvm::PHINode::getOperandNumForIncomingValue (unsigned i)</td>
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



<p>Definition at line 2685 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/ir/instructions-h">Instructions.h</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/utils/lcssa-cpp/#a03040e4a441982ab96f070a7f03cc910">formLCSSAForInstructionsImpl</a>, <a href="/web-llvm/docs/api/classes/llvm/sandboxir/phinode/#af6ed4ade3a52412ca81f68798ee33dc9">llvm::sandboxir::PHINode::getOperandNumForIncomingValue</a> and <a href="/web-llvm/docs/api/classes/anonymous-objcarccontract-cpp-/objcarccontract/#a6b6cfbee1f1d7c9f17eb52722c89564d">anonymous{ObjCARCContract.cpp}::ObjCARCContract::run</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Private Static Attributes

### AllocMarker {#a394cb7794b91f99ed857e5e71ea45cf1}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">HungOffOperandsAllocMarker llvm::PHINode::AllocMarker {}</td>
</tr>
</table>
</td>
<td class="doxyMemberLabelsRight">
<span class="doxyMemberLabels">
<span class="doxyMemberLabel constexpr">constexpr</span>
<span class="doxyMemberLabel static">static</span>
</span>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 2601 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/ir/instructions-h">Instructions.h</a>.</p>

</div>
</div>

</div>

<hr/>

The documentation for this class was generated from the following files:

<ul>
<li><a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/ir/instructions-h">Instructions.h</a></li>
<li><a href="/web-llvm/docs/api/files/lib/lib/ir/instructions-cpp">Instructions.cpp</a></li>
</ul>

<hr/>

<p class="doxyGeneratedBy">Generated via <a href="https://github.com/xpack/doxygen2docusaurus">doxygen2docusaurus</a> by <a href="https://www.doxygen.nl">Doxygen</a> 1.14.0.</p>

</div>
