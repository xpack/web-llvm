---

# DO NOT EDIT!
# Automatically generated via doxygen2docusaurus by Doxygen.

slug: /api/structs/anonymous-dagcombiner-cpp-/loadedslice
custom_edit_url: null
toc_max_heading_level: 4
keywords:
  - doxygen
  - reference
  - struct

---

<div class="doxyPage">

# The `LoadedSlice` Struct Reference

<p>Helper structure used to slice a load in smaller loads. <a href="#details">More...</a></p>

## Declaration

<div class="doxyDeclaration">
struct anonymous{DAGCombiner.cpp}::LoadedSlice { ... }
</div>

## Public Constructors Index

<table class="doxyMembersIndex">

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#adf78f2cdf71d35423c85759c3cfc1dab">LoadedSlice</a> (SDNode *Inst=nullptr, LoadSDNode *Origin=nullptr, unsigned Shift=0, SelectionDAG *DAG=nullptr)</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/apint">APInt</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#af4baa77e580192624b604fa2192ff41b">getUsedBits</a> () const</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Get the bits used in a chunk of bits <span class="doxyComputerOutput">BitWidth</span> large. <a href="#af4baa77e580192624b604fa2192ff41b">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">unsigned</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#aee19053815830c5e2ae9a61c2944319b">getLoadedSize</a> () const</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Get the size of the slice to be loaded in bytes. <a href="#aee19053815830c5e2ae9a61c2944319b">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/structs/llvm/evt">EVT</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a194d0b24bfe82015617637c7feafd34f">getLoadedType</a> () const</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Get the type that will be loaded for this slice. <a href="#a194d0b24bfe82015617637c7feafd34f">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/structs/llvm/align">Align</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a44391e7c48a75eb286fba96cde238ca9">getAlign</a> () const</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Get the alignment of the load used for this slice. <a href="#a44391e7c48a75eb286fba96cde238ca9">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">bool</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#aa8b06263dc30cdbef2780acdf3e73c69">isLegal</a> () const</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Check if this slice can be rewritten with legal operations. <a href="#aa8b06263dc30cdbef2780acdf3e73c69">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">uint64_t</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a6d14121fe4268a2a96c2107adfd49d17">getOffsetFromBase</a> () const</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Get the offset in bytes of this slice in the original chunk of bits. <a href="#a6d14121fe4268a2a96c2107adfd49d17">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/sdvalue">SDValue</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#aa9a4f93bd21587fb8d5a9b6260ee7207">loadSlice</a> () const</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Generate the sequence of instructions to load the slice represented by this object and redirect the uses of this slice to this new sequence of instructions. <a href="#aa9a4f93bd21587fb8d5a9b6260ee7207">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">bool</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a3359f38a412c6b9685e8fd39bd81b6a7">canMergeExpensiveCrossRegisterBankCopy</a> () const</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Check if this slice can be merged with an expensive cross register bank copy. <a href="#a3359f38a412c6b9685e8fd39bd81b6a7">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

</table>

## Public Member Attributes Index

<table class="doxyMembersIndex">

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/sdnode">SDNode</a> *</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#afe30281b52ba48dad1465288c71a7a12">Inst</a></td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/loadsdnode">LoadSDNode</a> *</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#adfb1fd0c5e3757fe133c9b55e0d15a69">Origin</a></td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#aca0f4d62fea425484c4b37fff2088ecb">Shift</a></td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/selectiondag">SelectionDAG</a> *</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a7f463f043a6be9a1851d95387217a272">DAG</a></td>
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

<p>Helper structure used to slice a load in smaller loads.</p>


<p>Basically a slice is obtained from the following sequence: Origin = load Ty1, Base Shift = srl Ty1 Origin, CstTy Amount Inst = trunc Shift to Ty2</p>


<p>Then, it will be rewritten into: Slice = load SliceTy, Base + SliceOffset [Inst = zext Slice to Ty2], only if SliceTy &lt;&gt; Ty2</p>


<p>SliceTy is deduced from the number of bits that are actually used to build Inst.</p>


<p>Definition at line 19624 of file <a href="/web-llvm/docs/api/files/lib/lib/codegen/lib/codegen/selectiondag/dagcombiner-cpp">DAGCombiner.cpp</a>.</p>


<div class="doxySectionDef">

## Public Constructors

### LoadedSlice() {#adf78f2cdf71d35423c85759c3cfc1dab}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">anonymous{DAGCombiner.cpp}::LoadedSlice::LoadedSlice (<a href="/web-llvm/docs/api/classes/llvm/sdnode">SDNode</a> * Inst=nullptr, <a href="/web-llvm/docs/api/classes/llvm/loadsdnode">LoadSDNode</a> * Origin=nullptr, unsigned Shift=0, <a href="/web-llvm/docs/api/classes/llvm/selectiondag">SelectionDAG</a> * DAG=nullptr)</td>
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



<p>Definition at line 19717 of file <a href="/web-llvm/docs/api/files/lib/lib/codegen/lib/codegen/selectiondag/dagcombiner-cpp">DAGCombiner.cpp</a>.</p>


<p>References <a href="#a7f463f043a6be9a1851d95387217a272">DAG</a>, <a href="#afe30281b52ba48dad1465288c71a7a12">Inst</a>, <a href="#adfb1fd0c5e3757fe133c9b55e0d15a69">Origin</a> and <a href="#aca0f4d62fea425484c4b37fff2088ecb">Shift</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/structs/anonymous-dagcombiner-cpp-/loadedslice/cost/#aa01a35c82abf5af510f7613fb60a71d1">anonymous{DAGCombiner.cpp}::LoadedSlice::Cost::addSliceGain</a>, <a href="/web-llvm/docs/api/files/lib/lib/codegen/lib/codegen/selectiondag/dagcombiner-cpp/#a3ceb460ebf70a2fe9a7eb07de595b3d1">adjustCostForPairing</a>, <a href="/web-llvm/docs/api/structs/anonymous-dagcombiner-cpp-/loadedslice/cost/#a93147f6d190705a36b6ab9994e243e26">anonymous{DAGCombiner.cpp}::LoadedSlice::Cost::Cost</a> and <a href="/web-llvm/docs/api/files/lib/lib/codegen/lib/codegen/selectiondag/dagcombiner-cpp/#af94365b75e01f45bde3699f009aa431e">isSlicingProfitable</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Public Member Functions

### canMergeExpensiveCrossRegisterBankCopy() {#a3359f38a412c6b9685e8fd39bd81b6a7}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool anonymous{DAGCombiner.cpp}::LoadedSlice::canMergeExpensiveCrossRegisterBankCopy ()</td>
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

<p>Check if this slice can be merged with an expensive cross register bank copy.</p>


<p>E.g., i = load i32 f = bitcast i32 i to float</p>


<p>Definition at line 19872 of file <a href="/web-llvm/docs/api/files/lib/lib/codegen/lib/codegen/selectiondag/dagcombiner-cpp">DAGCombiner.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/classes/llvm/targetloweringbase/#aabebd01d497720c5f7f25f1112c14ebf">llvm::TargetLoweringBase::allowsMemoryAccess</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/silowercontrolflow-cpp/#a4868c5d81c5ccc98c47aeab6244346a0">assert</a>, <a href="#a7f463f043a6be9a1851d95387217a272">DAG</a>, <a href="#a44391e7c48a75eb286fba96cde238ca9">getAlign</a>, <a href="#a194d0b24bfe82015617637c7feafd34f">getLoadedType</a>, <a href="/web-llvm/docs/api/classes/llvm/user/#aa0a2cb1582d1cec317bd205085469ca1">llvm::User::getOperand</a>, <a href="/web-llvm/docs/api/classes/llvm/targetloweringbase/#a1a78b9f867cb5be3a052d6ad972484ca">llvm::TargetLoweringBase::getRegClassFor</a>, <a href="/web-llvm/docs/api/structs/llvm/evt/#a6a81c1cc06a00a0096d839032b5984e9">llvm::EVT::getSimpleVT</a>, <a href="#afe30281b52ba48dad1465288c71a7a12">Inst</a>, <a href="/web-llvm/docs/api/classes/llvm/targetloweringbase/#a9245ed740fe76aaad3e5b0650da21c98">llvm::TargetLoweringBase::isOperationLegal</a>, <a href="#adfb1fd0c5e3757fe133c9b55e0d15a69">Origin</a> and <a href="/web-llvm/docs/api/files/lib/lib/codegen/machinesink-cpp/#a0f36ed1bc17fc1aa97fe291c439a0698">TRI</a>.</p>

</div>
</div>

### getAlign() {#a44391e7c48a75eb286fba96cde238ca9}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">Align anonymous{DAGCombiner.cpp}::LoadedSlice::getAlign ()</td>
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

<p>Get the alignment of the load used for this slice.</p>

<p>Definition at line 19757 of file <a href="/web-llvm/docs/api/files/lib/lib/codegen/lib/codegen/selectiondag/dagcombiner-cpp">DAGCombiner.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/namespaces/llvm/#acd6aa057934751aaac54e5c18bcc18eb">llvm::commonAlignment</a>, <a href="#a6d14121fe4268a2a96c2107adfd49d17">getOffsetFromBase</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a05f5b9a11bdcc5feba62899f95dcf878a3134224cba2545bc57954d3b072aebb4">llvm::Offset</a>, <a href="#adfb1fd0c5e3757fe133c9b55e0d15a69">Origin</a> and <a href="/web-llvm/docs/api/structs/llvm/align/#a80735739b49cf97a491922c8f9af2cc1">llvm::Align::value</a>.</p>


<p>Referenced by <a href="#a3359f38a412c6b9685e8fd39bd81b6a7">canMergeExpensiveCrossRegisterBankCopy</a> and <a href="#aa9a4f93bd21587fb8d5a9b6260ee7207">loadSlice</a>.</p>

</div>
</div>

### getLoadedSize() {#aee19053815830c5e2ae9a61c2944319b}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">unsigned anonymous{DAGCombiner.cpp}::LoadedSlice::getLoadedSize ()</td>
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

<p>Get the size of the slice to be loaded in bytes.</p>

<p>Definition at line 19742 of file <a href="/web-llvm/docs/api/files/lib/lib/codegen/lib/codegen/selectiondag/dagcombiner-cpp">DAGCombiner.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/silowercontrolflow-cpp/#a4868c5d81c5ccc98c47aeab6244346a0">assert</a> and <a href="#af4baa77e580192624b604fa2192ff41b">getUsedBits</a>.</p>


<p>Referenced by <a href="#a194d0b24bfe82015617637c7feafd34f">getLoadedType</a> and <a href="#a6d14121fe4268a2a96c2107adfd49d17">getOffsetFromBase</a>.</p>

</div>
</div>

### getLoadedType() {#a194d0b24bfe82015617637c7feafd34f}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">EVT anonymous{DAGCombiner.cpp}::LoadedSlice::getLoadedType ()</td>
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

<p>Get the type that will be loaded for this slice.</p>


<p>Note: This may not be the final type for the slice.</p>


<p>Definition at line 19750 of file <a href="/web-llvm/docs/api/files/lib/lib/codegen/lib/codegen/selectiondag/dagcombiner-cpp">DAGCombiner.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/silowercontrolflow-cpp/#a4868c5d81c5ccc98c47aeab6244346a0">assert</a>, <a href="#a7f463f043a6be9a1851d95387217a272">DAG</a>, <a href="/web-llvm/docs/api/structs/llvm/evt/#a752372e170e4e7c595bf8810bb52adf2">llvm::EVT::getIntegerVT</a> and <a href="#aee19053815830c5e2ae9a61c2944319b">getLoadedSize</a>.</p>


<p>Referenced by <a href="#a3359f38a412c6b9685e8fd39bd81b6a7">canMergeExpensiveCrossRegisterBankCopy</a>, <a href="#aa8b06263dc30cdbef2780acdf3e73c69">isLegal</a> and <a href="#aa9a4f93bd21587fb8d5a9b6260ee7207">loadSlice</a>.</p>

</div>
</div>

### getOffsetFromBase() {#a6d14121fe4268a2a96c2107adfd49d17}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">uint64_t anonymous{DAGCombiner.cpp}::LoadedSlice::getOffsetFromBase ()</td>
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

<p>Get the offset in bytes of this slice in the original chunk of bits.</p>


<dl class="doxySectionUser">
<dt>Precondition</dt>
<dd><p>DAG != nullptr.</p></dd>
</dl>


<p>Definition at line 19812 of file <a href="/web-llvm/docs/api/files/lib/lib/codegen/lib/codegen/selectiondag/dagcombiner-cpp">DAGCombiner.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/silowercontrolflow-cpp/#a4868c5d81c5ccc98c47aeab6244346a0">assert</a>, <a href="#a7f463f043a6be9a1851d95387217a272">DAG</a>, <a href="#aee19053815830c5e2ae9a61c2944319b">getLoadedSize</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a05f5b9a11bdcc5feba62899f95dcf878a3134224cba2545bc57954d3b072aebb4">llvm::Offset</a>, <a href="#adfb1fd0c5e3757fe133c9b55e0d15a69">Origin</a> and <a href="#aca0f4d62fea425484c4b37fff2088ecb">Shift</a>.</p>


<p>Referenced by <a href="#a44391e7c48a75eb286fba96cde238ca9">getAlign</a>, <a href="#aa8b06263dc30cdbef2780acdf3e73c69">isLegal</a> and <a href="#aa9a4f93bd21587fb8d5a9b6260ee7207">loadSlice</a>.</p>

</div>
</div>

### getUsedBits() {#af4baa77e580192624b604fa2192ff41b}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">APInt anonymous{DAGCombiner.cpp}::LoadedSlice::getUsedBits ()</td>
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

<p>Get the bits used in a chunk of bits <span class="doxyComputerOutput">BitWidth</span> large.</p>


<dl class="doxySectionUser">
<dt>Returns</dt>
<dd><p>Result is <span class="doxyComputerOutput">BitWidth</span> and has used bits set to 1 and not used bits set to 0.</p></dd>
</dl>


<p>Definition at line 19724 of file <a href="/web-llvm/docs/api/files/lib/lib/codegen/lib/codegen/selectiondag/dagcombiner-cpp">DAGCombiner.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/silowercontrolflow-cpp/#a4868c5d81c5ccc98c47aeab6244346a0">assert</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#abee0df5f7f703bb4462aba260ba0a60f">llvm::BitWidth</a>, <a href="#afe30281b52ba48dad1465288c71a7a12">Inst</a>, <a href="#adfb1fd0c5e3757fe133c9b55e0d15a69">Origin</a>, <a href="/web-llvm/docs/api/classes/llvm/apint/#ab6fff8a97bcb55e50e9be0ecf0c99b63">llvm::APInt::setAllBits</a>, <a href="#aca0f4d62fea425484c4b37fff2088ecb">Shift</a> and <a href="/web-llvm/docs/api/classes/llvm/apint/#a1dc76cc8bf703e6ada68bededcbb9573">llvm::APInt::zext</a>.</p>


<p>Referenced by <a href="#aee19053815830c5e2ae9a61c2944319b">getLoadedSize</a>.</p>

</div>
</div>

### isLegal() {#aa8b06263dc30cdbef2780acdf3e73c69}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool anonymous{DAGCombiner.cpp}::LoadedSlice::isLegal ()</td>
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

<p>Check if this slice can be rewritten with legal operations.</p>

<p>Definition at line 19766 of file <a href="/web-llvm/docs/api/files/lib/lib/codegen/lib/codegen/selectiondag/dagcombiner-cpp">DAGCombiner.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/namespaces/llvm/isd/#a22ea9cec080dd5f4f47ba234c2f59110a269996b43a1f3e1d1f84a70fd4387535">llvm::ISD::ADD</a>, <a href="#a7f463f043a6be9a1851d95387217a272">DAG</a>, <a href="#a194d0b24bfe82015617637c7feafd34f">getLoadedType</a>, <a href="#a6d14121fe4268a2a96c2107adfd49d17">getOffsetFromBase</a>, <a href="#afe30281b52ba48dad1465288c71a7a12">Inst</a>, <a href="/web-llvm/docs/api/structs/llvm/evt/#abda309a31acb43c06215c1772727bf1c">llvm::EVT::isExtended</a>, <a href="/web-llvm/docs/api/classes/llvm/targetloweringbase/#a8ccde50eadcc47f62c4076681b969864">llvm::TargetLoweringBase::isLegalAddImmediate</a>, <a href="/web-llvm/docs/api/classes/llvm/targetloweringbase/#a9245ed740fe76aaad3e5b0650da21c98">llvm::TargetLoweringBase::isOperationLegal</a>, <a href="/web-llvm/docs/api/classes/llvm/targetloweringbase/#a80b305b278aa0e04f80312e15b2b6d54">llvm::TargetLoweringBase::isTypeLegal</a>, <a href="#adfb1fd0c5e3757fe133c9b55e0d15a69">Origin</a> and <a href="/web-llvm/docs/api/namespaces/llvm/isd/#a22ea9cec080dd5f4f47ba234c2f59110a93fdf85eff945f1a668b4915a051453e">llvm::ISD::ZERO_EXTEND</a>.</p>

</div>
</div>

### loadSlice() {#aa9a4f93bd21587fb8d5a9b6260ee7207}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">SDValue anonymous{DAGCombiner.cpp}::LoadedSlice::loadSlice ()</td>
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

<p>Generate the sequence of instructions to load the slice represented by this object and redirect the uses of this slice to this new sequence of instructions.</p>


<dl class="doxySectionUser">
<dt>Precondition</dt>
<dd><p>this-&gt;Inst &amp;&amp; this-&gt;Origin are valid Instructions and this object passed the legal check: <a href="#aa8b06263dc30cdbef2780acdf3e73c69">LoadedSlice::isLegal</a> returned true.</p></dd>
</dl>


<dl class="doxySectionUser">
<dt>Returns</dt>
<dd><p>The last instruction of the sequence used to load the slice.</p></dd>
</dl>


<p>Definition at line 19836 of file <a href="/web-llvm/docs/api/files/lib/lib/codegen/lib/codegen/selectiondag/dagcombiner-cpp">DAGCombiner.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/namespaces/llvm/isd/#a22ea9cec080dd5f4f47ba234c2f59110a269996b43a1f3e1d1f84a70fd4387535">llvm::ISD::ADD</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/silowercontrolflow-cpp/#a4868c5d81c5ccc98c47aeab6244346a0">assert</a>, <a href="#a7f463f043a6be9a1851d95387217a272">DAG</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/arm/armslshardening-cpp/#ad467c4ab9119043f9b7750ab986be61a">DL</a>, <a href="#a44391e7c48a75eb286fba96cde238ca9">getAlign</a>, <a href="#a194d0b24bfe82015617637c7feafd34f">getLoadedType</a>, <a href="#a6d14121fe4268a2a96c2107adfd49d17">getOffsetFromBase</a>, <a href="#afe30281b52ba48dad1465288c71a7a12">Inst</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a05f5b9a11bdcc5feba62899f95dcf878a3134224cba2545bc57954d3b072aebb4">llvm::Offset</a>, <a href="#adfb1fd0c5e3757fe133c9b55e0d15a69">Origin</a> and <a href="/web-llvm/docs/api/namespaces/llvm/isd/#a22ea9cec080dd5f4f47ba234c2f59110a93fdf85eff945f1a668b4915a051453e">llvm::ISD::ZERO_EXTEND</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Public Member Attributes

### DAG {#a7f463f043a6be9a1851d95387217a272}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">SelectionDAG* anonymous{DAGCombiner.cpp}::LoadedSlice::DAG</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 19715 of file <a href="/web-llvm/docs/api/files/lib/lib/codegen/lib/codegen/selectiondag/dagcombiner-cpp">DAGCombiner.cpp</a>.</p>


<p>Referenced by <a href="#a3359f38a412c6b9685e8fd39bd81b6a7">canMergeExpensiveCrossRegisterBankCopy</a>, <a href="#a194d0b24bfe82015617637c7feafd34f">getLoadedType</a>, <a href="#a6d14121fe4268a2a96c2107adfd49d17">getOffsetFromBase</a>, <a href="#aa8b06263dc30cdbef2780acdf3e73c69">isLegal</a>, <a href="#adf78f2cdf71d35423c85759c3cfc1dab">LoadedSlice</a> and <a href="#aa9a4f93bd21587fb8d5a9b6260ee7207">loadSlice</a>.</p>

</div>
</div>

### Inst {#afe30281b52ba48dad1465288c71a7a12}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">SDNode* anonymous{DAGCombiner.cpp}::LoadedSlice::Inst</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 19705 of file <a href="/web-llvm/docs/api/files/lib/lib/codegen/lib/codegen/selectiondag/dagcombiner-cpp">DAGCombiner.cpp</a>.</p>


<p>Referenced by <a href="#a3359f38a412c6b9685e8fd39bd81b6a7">canMergeExpensiveCrossRegisterBankCopy</a>, <a href="#af4baa77e580192624b604fa2192ff41b">getUsedBits</a>, <a href="#aa8b06263dc30cdbef2780acdf3e73c69">isLegal</a>, <a href="#adf78f2cdf71d35423c85759c3cfc1dab">LoadedSlice</a> and <a href="#aa9a4f93bd21587fb8d5a9b6260ee7207">loadSlice</a>.</p>

</div>
</div>

### Origin {#adfb1fd0c5e3757fe133c9b55e0d15a69}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">LoadSDNode* anonymous{DAGCombiner.cpp}::LoadedSlice::Origin</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 19708 of file <a href="/web-llvm/docs/api/files/lib/lib/codegen/lib/codegen/selectiondag/dagcombiner-cpp">DAGCombiner.cpp</a>.</p>


<p>Referenced by <a href="#a3359f38a412c6b9685e8fd39bd81b6a7">canMergeExpensiveCrossRegisterBankCopy</a>, <a href="#a44391e7c48a75eb286fba96cde238ca9">getAlign</a>, <a href="#a6d14121fe4268a2a96c2107adfd49d17">getOffsetFromBase</a>, <a href="#af4baa77e580192624b604fa2192ff41b">getUsedBits</a>, <a href="#aa8b06263dc30cdbef2780acdf3e73c69">isLegal</a>, <a href="#adf78f2cdf71d35423c85759c3cfc1dab">LoadedSlice</a> and <a href="#aa9a4f93bd21587fb8d5a9b6260ee7207">loadSlice</a>.</p>

</div>
</div>

### Shift {#aca0f4d62fea425484c4b37fff2088ecb}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">unsigned anonymous{DAGCombiner.cpp}::LoadedSlice::Shift</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 19711 of file <a href="/web-llvm/docs/api/files/lib/lib/codegen/lib/codegen/selectiondag/dagcombiner-cpp">DAGCombiner.cpp</a>.</p>


<p>Referenced by <a href="#a6d14121fe4268a2a96c2107adfd49d17">getOffsetFromBase</a>, <a href="#af4baa77e580192624b604fa2192ff41b">getUsedBits</a> and <a href="#adf78f2cdf71d35423c85759c3cfc1dab">LoadedSlice</a>.</p>

</div>
</div>

</div>

<hr/>

The documentation for this struct was generated from the following file:

<ul>
<li><a href="/web-llvm/docs/api/files/lib/lib/codegen/lib/codegen/selectiondag/dagcombiner-cpp">DAGCombiner.cpp</a></li>
</ul>

<hr/>

<p class="doxyGeneratedBy">Generated via <a href="https://github.com/xpack/doxygen2docusaurus">doxygen2docusaurus</a> by <a href="https://www.doxygen.nl">Doxygen</a> 1.14.0.</p>

</div>
