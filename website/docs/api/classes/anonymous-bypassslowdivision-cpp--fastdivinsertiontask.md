---

# DO NOT EDIT!
# Automatically generated via doxygen2docusaurus by Doxygen.

slug: /api/classes/anonymous-bypassslowdivision-cpp-/fastdivinsertiontask
custom_edit_url: null
toc_max_heading_level: 4
keywords:
  - doxygen
  - reference
  - class

---

<div class="doxyPage">

# `FastDivInsertionTask` Class



## Declaration

<div class="doxyDeclaration">
class anonymous{BypassSlowDivision.cpp}::FastDivInsertionTask { ... }
</div>

## Public Constructors Index

<table class="doxyMembersIndex">

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ab953cd204338514e8d564c615763d13f">FastDivInsertionTask</a> (Instruction *I, const BypassWidthsTy &amp;BypassWidths)</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/value">Value</a> *</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#af373b68c535969d897e55c3857997583">getReplacement</a> (DivCacheTy &amp;Cache)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Reuses previously-computed dividend or remainder from the current BB if operands and operation are identical. <a href="#af373b68c535969d897e55c3857997583">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

</table>

## Private Member Functions Index

<table class="doxyMembersIndex">

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">bool</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a1cab8ec021a9c3c9f9245468005b59e1">isHashLikeValue</a> (Value *V, VisitedSetTy &amp;Visited)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Check if a value looks like a hash. <a href="#a1cab8ec021a9c3c9f9245468005b59e1">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/namespaces/anonymous-bypassslowdivision-cpp-/#a36d0c5907e0a6a90e175f343a59b1206">ValueRange</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a24ac2d7697cecde67c9ef8b576559f19">getValueRange</a> (Value *Op, VisitedSetTy &amp;Visited)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Check if an integer value fits into our bypass type. <a href="#a24ac2d7697cecde67c9ef8b576559f19">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/structs/anonymous-bypassslowdivision-cpp-/quotremwithbb">QuotRemWithBB</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a379a96da7f1b4be0b9f5e081210fba5d">createSlowBB</a> (BasicBlock *Successor)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Add new basic block for slow div and rem operations and put it before SuccessorBB. <a href="#a379a96da7f1b4be0b9f5e081210fba5d">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/structs/anonymous-bypassslowdivision-cpp-/quotremwithbb">QuotRemWithBB</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a86c5ad21a2d56d1af3c5f2b39331c02b">createFastBB</a> (BasicBlock *Successor)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Add new basic block for fast div and rem operations and put it before SuccessorBB. <a href="#a86c5ad21a2d56d1af3c5f2b39331c02b">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/structs/anonymous-bypassslowdivision-cpp-/quotrempair">QuotRemPair</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a0dd8d4ba03c7b55182b1b9fa5ae5d053">createDivRemPhiNodes</a> (QuotRemWithBB &amp;LHS, QuotRemWithBB &amp;RHS, BasicBlock *PhiBB)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Creates Phi nodes for result of Div and Rem. <a href="#a0dd8d4ba03c7b55182b1b9fa5ae5d053">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/value">Value</a> *</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#af0d64e9189eea24fe6f912a3eb090d26">insertOperandRuntimeCheck</a> (Value *Op1, Value *Op2)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Creates a runtime check to test whether both the divisor and dividend fit into BypassType. <a href="#af0d64e9189eea24fe6f912a3eb090d26">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">std::optional&lt; <a href="/web-llvm/docs/api/structs/anonymous-bypassslowdivision-cpp-/quotrempair">QuotRemPair</a> &gt;</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#af95a5c370fd009c032a7b9e7d474d2df">insertFastDivAndRem</a> ()</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Substitutes the div/rem instruction with code that checks the value of the operands and uses a shorter-faster div/rem instruction when possible. <a href="#af95a5c370fd009c032a7b9e7d474d2df">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">bool</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#aed199058015f21db56caa286f64a1f70">isSignedOp</a> ()</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ab3997bfeb71ab5591fd057a579b2f890">isDivisionOp</a> ()</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/type">Type</a> *</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a90797c748af6eee89837b818f74a9ab2">getSlowType</a> ()</td>
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

## Private Member Attributes Index

<table class="doxyMembersIndex">

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">bool</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a068deab70166725d76545344d2d34b2e">IsValidTask</a> = false</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/instruction">Instruction</a> *</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#abe37de33f2bc8d341b4c00d42136e819">SlowDivOrRem</a> = nullptr</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/integertype">IntegerType</a> *</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a67b61296e3c5c023a62678de9122ed22">BypassType</a> = nullptr</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a01b0d7b04704d6876e0a2871f3d0d0fa">MainBB</a> = nullptr</td>
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


<p>Definition at line 74 of file <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/utils/bypassslowdivision-cpp">BypassSlowDivision.cpp</a>.</p>


<div class="doxySectionDef">

## Public Constructors

### FastDivInsertionTask() {#ab953cd204338514e8d564c615763d13f}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">FastDivInsertionTask::FastDivInsertionTask (<a href="/web-llvm/docs/api/classes/llvm/instruction">Instruction</a> * I, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/namespaces/anonymous-bypassslowdivision-cpp-/#af59a5e0e43be3e24b0a48311ea4f3b0d">BypassWidthsTy</a> &amp; BypassWidths)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 102 of file <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/utils/bypassslowdivision-cpp">BypassSlowDivision.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/namespaces/llvm/#a22eeee01734061ac1b31ccd994c49eef">llvm::dyn_cast</a>, <a href="/web-llvm/docs/api/classes/llvm/densemapbase/#a65520b9c67759099e313d0f4e7b5ff9e">llvm::DenseMapBase&lt; DerivedT, KeyT, ValueT, KeyInfoT, BucketT &gt;::end</a>, <a href="/web-llvm/docs/api/classes/llvm/densemapbase/#a0c047f127ed4380a6f383d70bec4eb94">llvm::DenseMapBase&lt; DerivedT, KeyT, ValueT, KeyInfoT, BucketT &gt;::find</a>, <a href="/web-llvm/docs/api/classes/llvm/integertype/#a14f7b4f1aed38192fb6b7772eb506bdb">llvm::IntegerType::get</a>, <a href="/web-llvm/docs/api/classes/llvm/integertype/#a90b790ccb1af4ea5ccd69db4b8cd2d81">llvm::IntegerType::getBitWidth</a> and <a href="/web-llvm/docs/api/files/lib/lib/support/md5-cpp/#ac0eafdc9ee161b71e7af98af736952fd">I</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Public Member Functions

### getReplacement() {#af373b68c535969d897e55c3857997583}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">Value * FastDivInsertionTask::getReplacement (<a href="/web-llvm/docs/api/namespaces/anonymous-bypassslowdivision-cpp-/#ab0c88d4f81519e479e544b0173e59466">DivCacheTy</a> &amp; Cache)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Reuses previously-computed dividend or remainder from the current BB if operands and operation are identical.</p>


<p>Otherwise calls insertFastDivAndRem to perform the optimization and caches the resulting dividend and remainder. If no replacement can be generated, nullptr is returned.</p>


<p>Definition at line 104 of file <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/utils/bypassslowdivision-cpp">BypassSlowDivision.cpp</a>.</p>


<p>Reference <a href="/web-llvm/docs/api/namespaces/llvm/#a98c6256d0644613c6b5b3e2ef06ef5ce">llvm::InnerAnalysisManagerProxy&lt; AnalysisManagerT, IRUnitT, ExtraArgTs... &gt;::Key</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Private Member Functions

### createDivRemPhiNodes() {#a0dd8d4ba03c7b55182b1b9fa5ae5d053}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">QuotRemPair FastDivInsertionTask::createDivRemPhiNodes (<a href="/web-llvm/docs/api/structs/anonymous-bypassslowdivision-cpp-/quotremwithbb">QuotRemWithBB</a> &amp; LHS, <a href="/web-llvm/docs/api/structs/anonymous-bypassslowdivision-cpp-/quotremwithbb">QuotRemWithBB</a> &amp; RHS, <a href="/web-llvm/docs/api/classes/llvm/basicblock">BasicBlock</a> * PhiBB)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Creates Phi nodes for result of Div and Rem.</p>

<p>Definition at line 84 of file <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/utils/bypassslowdivision-cpp">BypassSlowDivision.cpp</a>.</p>

</div>
</div>

### createFastBB() {#a86c5ad21a2d56d1af3c5f2b39331c02b}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">QuotRemWithBB FastDivInsertionTask::createFastBB (<a href="/web-llvm/docs/api/classes/llvm/basicblock">BasicBlock</a> * Successor)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Add new basic block for fast div and rem operations and put it before SuccessorBB.</p>

<p>Definition at line 83 of file <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/utils/bypassslowdivision-cpp">BypassSlowDivision.cpp</a>.</p>

</div>
</div>

### createSlowBB() {#a379a96da7f1b4be0b9f5e081210fba5d}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">QuotRemWithBB FastDivInsertionTask::createSlowBB (<a href="/web-llvm/docs/api/classes/llvm/basicblock">BasicBlock</a> * Successor)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Add new basic block for slow div and rem operations and put it before SuccessorBB.</p>

<p>Definition at line 82 of file <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/utils/bypassslowdivision-cpp">BypassSlowDivision.cpp</a>.</p>

</div>
</div>

### getSlowType() {#a90797c748af6eee89837b818f74a9ab2}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">Type * anonymous{BypassSlowDivision.cpp}::FastDivInsertionTask::getSlowType ()</td>
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



<p>Definition at line 99 of file <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/utils/bypassslowdivision-cpp">BypassSlowDivision.cpp</a>.</p>

</div>
</div>

### getValueRange() {#a24ac2d7697cecde67c9ef8b576559f19}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">ValueRange FastDivInsertionTask::getValueRange (<a href="/web-llvm/docs/api/classes/llvm/value">Value</a> * Op, <a href="/web-llvm/docs/api/namespaces/anonymous-bypassslowdivision-cpp-/#ad9ba66f337464ca75cd451c4c7a1cbbe">VisitedSetTy</a> &amp; Visited)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Check if an integer value fits into our bypass type.</p>

<p>Definition at line 81 of file <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/utils/bypassslowdivision-cpp">BypassSlowDivision.cpp</a>.</p>

</div>
</div>

### insertFastDivAndRem() {#af95a5c370fd009c032a7b9e7d474d2df}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">std::optional&lt; QuotRemPair &gt; FastDivInsertionTask::insertFastDivAndRem ()</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Substitutes the div/rem instruction with code that checks the value of the operands and uses a shorter-faster div/rem instruction when possible.</p>

<p>Definition at line 87 of file <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/utils/bypassslowdivision-cpp">BypassSlowDivision.cpp</a>.</p>

</div>
</div>

### insertOperandRuntimeCheck() {#af0d64e9189eea24fe6f912a3eb090d26}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">Value * FastDivInsertionTask::insertOperandRuntimeCheck (<a href="/web-llvm/docs/api/classes/llvm/value">Value</a> * Op1, <a href="/web-llvm/docs/api/classes/llvm/value">Value</a> * Op2)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Creates a runtime check to test whether both the divisor and dividend fit into BypassType.</p>


<p>The check is inserted at the end of MainBB. True return value means that the operands fit. Either of the operands may be NULL if it doesn't need a runtime check.</p>


<p>Definition at line 86 of file <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/utils/bypassslowdivision-cpp">BypassSlowDivision.cpp</a>.</p>

</div>
</div>

### isDivisionOp() {#ab3997bfeb71ab5591fd057a579b2f890}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool anonymous{BypassSlowDivision.cpp}::FastDivInsertionTask::isDivisionOp ()</td>
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



<p>Definition at line 94 of file <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/utils/bypassslowdivision-cpp">BypassSlowDivision.cpp</a>.</p>

</div>
</div>

### isHashLikeValue() {#a1cab8ec021a9c3c9f9245468005b59e1}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool FastDivInsertionTask::isHashLikeValue (<a href="/web-llvm/docs/api/classes/llvm/value">Value</a> * V, <a href="/web-llvm/docs/api/namespaces/anonymous-bypassslowdivision-cpp-/#ad9ba66f337464ca75cd451c4c7a1cbbe">VisitedSetTy</a> &amp; Visited)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Check if a value looks like a hash.</p>


<p>The routine is expected to detect values computed using the most common hash algorithms. Typically, hash computations end with one of the following instructions:</p>


<p>1) MUL with a constant wider than BypassType 2) XOR instruction</p>


<p>And even if we are wrong and the value is not a hash, it is still quite unlikely that such values will fit into BypassType.</p>


<p>To detect string hash algorithms like FNV we have to look through PHI-nodes. It is implemented as a depth-first search for values that look neither long nor hash-like.</p>


<p>Definition at line 80 of file <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/utils/bypassslowdivision-cpp">BypassSlowDivision.cpp</a>.</p>

</div>
</div>

### isSignedOp() {#aed199058015f21db56caa286f64a1f70}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool anonymous{BypassSlowDivision.cpp}::FastDivInsertionTask::isSignedOp ()</td>
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



<p>Definition at line 89 of file <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/utils/bypassslowdivision-cpp">BypassSlowDivision.cpp</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Private Member Attributes

### BypassType {#a67b61296e3c5c023a62678de9122ed22}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">IntegerType* anonymous{BypassSlowDivision.cpp}::FastDivInsertionTask::BypassType = nullptr</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 77 of file <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/utils/bypassslowdivision-cpp">BypassSlowDivision.cpp</a>.</p>

</div>
</div>

### IsValidTask {#a068deab70166725d76545344d2d34b2e}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool anonymous{BypassSlowDivision.cpp}::FastDivInsertionTask::IsValidTask = false</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 75 of file <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/utils/bypassslowdivision-cpp">BypassSlowDivision.cpp</a>.</p>

</div>
</div>

### MainBB {#a01b0d7b04704d6876e0a2871f3d0d0fa}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">BasicBlock* anonymous{BypassSlowDivision.cpp}::FastDivInsertionTask::MainBB = nullptr</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 78 of file <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/utils/bypassslowdivision-cpp">BypassSlowDivision.cpp</a>.</p>

</div>
</div>

### SlowDivOrRem {#abe37de33f2bc8d341b4c00d42136e819}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">Instruction* anonymous{BypassSlowDivision.cpp}::FastDivInsertionTask::SlowDivOrRem = nullptr</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 76 of file <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/utils/bypassslowdivision-cpp">BypassSlowDivision.cpp</a>.</p>

</div>
</div>

</div>

<hr/>

The documentation for this class was generated from the following file:

<ul>
<li><a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/utils/bypassslowdivision-cpp">BypassSlowDivision.cpp</a></li>
</ul>

<hr/>

<p class="doxyGeneratedBy">Generated via <a href="https://github.com/xpack/doxygen2docusaurus">doxygen2docusaurus</a> by <a href="https://www.doxygen.nl">Doxygen</a> 1.15.0.</p>

</div>
