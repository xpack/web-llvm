---

# DO NOT EDIT!
# Automatically generated via doxygen2docusaurus by Doxygen.

slug: /api/classes/llvm/sandboxir/extractvalueinst
custom_edit_url: null
toc_max_heading_level: 4
keywords:
  - doxygen
  - reference
  - class

---

<div class="doxyPage">

# The `ExtractValueInst` Class Reference



## Declaration

<div class="doxyDeclaration">
class llvm::sandboxir::ExtractValueInst { ... }
</div>

## Included Headers

<div class="doxyIncludesList">#include "<a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/sandboxir/instruction-h">llvm/SandboxIR/Instruction.h</a>"
</div>

## Base class

<table class="doxyMembersIndex">

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">class</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/sandboxir/unaryinstruction">UnaryInstruction</a></td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>An abstract class, parent of unary instructions. <a href="/web-llvm/docs/api/classes/llvm/sandboxir/unaryinstruction/#details">More...</a></p>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#adf7793f30a46f97efd26e35d29150776">idx_iterator</a> = <a href="/web-llvm/docs/api/classes/llvm/extractvalueinst/#a5b2f9684792e863925e85a460f3ccff0">llvm::ExtractValueInst::idx_iterator</a></td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#aca406284c1ee36b29cf70d6a42031052">ExtractValueInst</a> (llvm::ExtractValueInst *EVI, Context &amp;Ctx)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p><a href="/web-llvm/docs/api/classes/llvm/sandboxir/use">Use</a> <a href="/web-llvm/docs/api/classes/llvm/sandboxir/context/#ab02a987dcbbb52bd5ca013939320377a">Context::createExtractValueInst()</a> instead. <a href="#aca406284c1ee36b29cf70d6a42031052">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

</table>

## Public Member Functions Index

<table class="doxyMembersIndex">

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="#adf7793f30a46f97efd26e35d29150776">idx_iterator</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a3d71b9c5bcaa346b3bcc77d01a731b92">idx_begin</a> () const</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="#adf7793f30a46f97efd26e35d29150776">idx_iterator</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#af679e1725fe477cd15bac8b2a6075c24">idx_end</a> () const</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/iterator-range">iterator_range</a>&lt; <a href="#adf7793f30a46f97efd26e35d29150776">idx_iterator</a> &gt;</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#af3de205b4adfeb53855ac60f9029ac05">indices</a> () const</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/sandboxir/value">Value</a> *</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a73efa393d80ccb5c8817b8bd1830f333">getAggregateOperand</a> ()</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/sandboxir/value">Value</a> *</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a2c112440d261a84437b343ee2b4c511f">getAggregateOperand</a> () const</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/arrayref">ArrayRef</a>&lt; unsigned &gt;</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a3ff81b5eec88f21330371593f8f49917">getIndices</a> () const</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a11d78b11327a0d66d0eaa7c34aff37a9">getNumIndices</a> () const</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#acff03e25a823347e541847b09c1b4866">hasIndices</a> () const</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">friend</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a7924fe58f16c17efb916e1516be24b39">Context</a></td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">static <a href="/web-llvm/docs/api/classes/llvm/sandboxir/value">Value</a> *</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a2990a7387ba4a5f3171b1a69e26cc13c">create</a> (Value *Agg, ArrayRef&lt; unsigned &gt; Idxs, InsertPosition Pos, Context &amp;Ctx, const Twine &amp;Name="")</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#aeb806dab024fffd71f87e56146305a96">classof</a> (const Value *From)</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">static <a href="/web-llvm/docs/api/classes/llvm/sandboxir/type">Type</a> *</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a4e6ed8a1c14cfbc9d22aa336c96e4e0b">getIndexedType</a> (Type *Agg, ArrayRef&lt; unsigned &gt; Idxs)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Returns the type of the element that would be extracted with an extractvalue instruction with the specified parameters. <a href="#a4e6ed8a1c14cfbc9d22aa336c96e4e0b">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">static unsigned</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a3059c2c0fecec64aa43358bb25a006d7">getAggregateOperandIndex</a> ()</td>
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


<p>Definition at line 1104 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/sandboxir/instruction-h">Instruction.h</a>.</p>


<div class="doxySectionDef">

## Public Member Typedefs

### idx\_iterator {#adf7793f30a46f97efd26e35d29150776}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">using llvm::sandboxir::ExtractValueInst::idx_iterator =  llvm::ExtractValueInst::idx_iterator</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 1125 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/sandboxir/instruction-h">Instruction.h</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Private Constructors

### ExtractValueInst() {#aca406284c1ee36b29cf70d6a42031052}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">llvm::sandboxir::ExtractValueInst::ExtractValueInst (<a href="/web-llvm/docs/api/classes/llvm/extractvalueinst">llvm::ExtractValueInst</a> * EVI, <a href="/web-llvm/docs/api/classes/llvm/sandboxir/context">Context</a> &amp; Ctx)</td>
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

<p><a href="/web-llvm/docs/api/classes/llvm/sandboxir/use">Use</a> <a href="/web-llvm/docs/api/classes/llvm/sandboxir/context/#ab02a987dcbbb52bd5ca013939320377a">Context::createExtractValueInst()</a> instead.</p>

<p>Definition at line 1106 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/sandboxir/instruction-h">Instruction.h</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Public Member Functions

### getAggregateOperand() {#a73efa393d80ccb5c8817b8bd1830f333}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">Value * llvm::sandboxir::ExtractValueInst::getAggregateOperand ()</td>
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



<p>Definition at line 1137 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/sandboxir/instruction-h">Instruction.h</a>.</p>


<p>References <a href="#a3059c2c0fecec64aa43358bb25a006d7">getAggregateOperandIndex</a> and <a href="/web-llvm/docs/api/namespaces/llvm/sandboxir/#ac9a69bf52a5b93bb710536d9ae8245c6">llvm::sandboxir::getOperand</a>.</p>

</div>
</div>

### getAggregateOperand() {#a2c112440d261a84437b343ee2b4c511f}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">const Value * llvm::sandboxir::ExtractValueInst::getAggregateOperand ()</td>
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



<p>Definition at line 1140 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/sandboxir/instruction-h">Instruction.h</a>.</p>


<p>References <a href="#a3059c2c0fecec64aa43358bb25a006d7">getAggregateOperandIndex</a> and <a href="/web-llvm/docs/api/namespaces/llvm/sandboxir/#ac9a69bf52a5b93bb710536d9ae8245c6">llvm::sandboxir::getOperand</a>.</p>

</div>
</div>

### getIndices() {#a3ff81b5eec88f21330371593f8f49917}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">ArrayRef&lt; unsigned &gt; llvm::sandboxir::ExtractValueInst::getIndices ()</td>
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



<p>Definition at line 1147 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/sandboxir/instruction-h">Instruction.h</a>.</p>


<p>References <a href="/web-llvm/docs/api/namespaces/llvm/#ac4fc845f5ed92de63cd4474f128f5fc5">llvm::cast</a> and <a href="/web-llvm/docs/api/classes/llvm/sandboxir/value/#a0c4530f3c64d8c2eafac20fb87105d8a">llvm::sandboxir::Value::Val</a>.</p>

</div>
</div>

### getNumIndices() {#a11d78b11327a0d66d0eaa7c34aff37a9}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">unsigned llvm::sandboxir::ExtractValueInst::getNumIndices ()</td>
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



<p>Definition at line 1151 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/sandboxir/instruction-h">Instruction.h</a>.</p>


<p>References <a href="/web-llvm/docs/api/namespaces/llvm/#ac4fc845f5ed92de63cd4474f128f5fc5">llvm::cast</a> and <a href="/web-llvm/docs/api/classes/llvm/sandboxir/value/#a0c4530f3c64d8c2eafac20fb87105d8a">llvm::sandboxir::Value::Val</a>.</p>

</div>
</div>

### hasIndices() {#acff03e25a823347e541847b09c1b4866}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">unsigned llvm::sandboxir::ExtractValueInst::hasIndices ()</td>
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



<p>Definition at line 1155 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/sandboxir/instruction-h">Instruction.h</a>.</p>


<p>References <a href="/web-llvm/docs/api/namespaces/llvm/#ac4fc845f5ed92de63cd4474f128f5fc5">llvm::cast</a> and <a href="/web-llvm/docs/api/classes/llvm/sandboxir/value/#a0c4530f3c64d8c2eafac20fb87105d8a">llvm::sandboxir::Value::Val</a>.</p>

</div>
</div>

### idx\_begin() {#a3d71b9c5bcaa346b3bcc77d01a731b92}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">idx_iterator llvm::sandboxir::ExtractValueInst::idx_begin ()</td>
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



<p>Definition at line 1127 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/sandboxir/instruction-h">Instruction.h</a>.</p>


<p>References <a href="/web-llvm/docs/api/namespaces/llvm/#ac4fc845f5ed92de63cd4474f128f5fc5">llvm::cast</a> and <a href="/web-llvm/docs/api/classes/llvm/sandboxir/value/#a0c4530f3c64d8c2eafac20fb87105d8a">llvm::sandboxir::Value::Val</a>.</p>

</div>
</div>

### idx\_end() {#af679e1725fe477cd15bac8b2a6075c24}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">idx_iterator llvm::sandboxir::ExtractValueInst::idx_end ()</td>
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



<p>Definition at line 1130 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/sandboxir/instruction-h">Instruction.h</a>.</p>


<p>References <a href="/web-llvm/docs/api/namespaces/llvm/#ac4fc845f5ed92de63cd4474f128f5fc5">llvm::cast</a> and <a href="/web-llvm/docs/api/classes/llvm/sandboxir/value/#a0c4530f3c64d8c2eafac20fb87105d8a">llvm::sandboxir::Value::Val</a>.</p>

</div>
</div>

### indices() {#af3de205b4adfeb53855ac60f9029ac05}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">iterator_range&lt; idx_iterator &gt; llvm::sandboxir::ExtractValueInst::indices ()</td>
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



<p>Definition at line 1133 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/sandboxir/instruction-h">Instruction.h</a>.</p>


<p>References <a href="/web-llvm/docs/api/namespaces/llvm/#ac4fc845f5ed92de63cd4474f128f5fc5">llvm::cast</a> and <a href="/web-llvm/docs/api/classes/llvm/sandboxir/value/#a0c4530f3c64d8c2eafac20fb87105d8a">llvm::sandboxir::Value::Val</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Private Member Attributes

### Context {#a7924fe58f16c17efb916e1516be24b39}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">friend llvm::sandboxir::ExtractValueInst::Context</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 1109 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/sandboxir/instruction-h">Instruction.h</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Public Static Functions

### classof() {#aeb806dab024fffd71f87e56146305a96}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool llvm::sandboxir::ExtractValueInst::classof (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/sandboxir/value">Value</a> * From)</td>
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



<p>Definition at line 1115 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/sandboxir/instruction-h">Instruction.h</a>.</p>


<p>Reference <a href="/web-llvm/docs/api/classes/llvm/sandboxir/value/#a27b9af008c6420f3340805e50297f9fb">llvm::sandboxir::Value::getSubclassID</a>.</p>

</div>
</div>

### create() {#a2990a7387ba4a5f3171b1a69e26cc13c}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">Value * llvm::sandboxir::ExtractValueInst::create (<a href="/web-llvm/docs/api/classes/llvm/sandboxir/value">Value</a> * Agg, <a href="/web-llvm/docs/api/classes/llvm/arrayref">ArrayRef</a>&lt; unsigned &gt; Idxs, <a href="/web-llvm/docs/api/classes/llvm/sandboxir/insertposition">InsertPosition</a> Pos, <a href="/web-llvm/docs/api/classes/llvm/sandboxir/context">Context</a> &amp; Ctx, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/twine">Twine</a> &amp; Name="")</td>
</tr>
</table>
</td>
<td class="doxyMemberLabelsRight">
<span class="doxyMemberLabels">
<span class="doxyMemberLabel static">static</span>
</span>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Declaration at line 1112 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/sandboxir/instruction-h">Instruction.h</a>, definition at line 1527 of file <a href="/web-llvm/docs/api/files/lib/lib/sandboxir/instruction-cpp">Instruction.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/silowercontrolflow-cpp/#a4868c5d81c5ccc98c47aeab6244346a0">assert</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#ac4fc845f5ed92de63cd4474f128f5fc5">llvm::cast</a>, <a href="/web-llvm/docs/api/classes/llvm/irbuilderbase/#a41cf66866b0b0e5a10038bfb77477419">llvm::IRBuilderBase::CreateExtractValue</a>, <a href="/web-llvm/docs/api/classes/llvm/sandboxir/value/#a4705ee51ec0da1ba978f2353d2c47f27">llvm::sandboxir::Value::Ctx</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a22eeee01734061ac1b31ccd994c49eef">llvm::dyn_cast</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a92ca992e52dddc420f4b069cae06dfbe">llvm::isa</a>, <a href="/web-llvm/docs/api/classes/llvm/sandboxir/instruction/#a034571bc982742eb2cb2d135dee93eb2">llvm::sandboxir::Instruction::setInsertPos</a> and <a href="/web-llvm/docs/api/classes/llvm/sandboxir/value/#a0c4530f3c64d8c2eafac20fb87105d8a">llvm::sandboxir::Value::Val</a>.</p>

</div>
</div>

### getAggregateOperandIndex() {#a3059c2c0fecec64aa43358bb25a006d7}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">unsigned llvm::sandboxir::ExtractValueInst::getAggregateOperandIndex ()</td>
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



<p>Definition at line 1143 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/sandboxir/instruction-h">Instruction.h</a>.</p>


<p>Reference <a href="/web-llvm/docs/api/classes/llvm/extractvalueinst/#ad1d8a683feb5dd83ddf119c15922eee1">llvm::ExtractValueInst::getAggregateOperandIndex</a>.</p>


<p>Referenced by <a href="#a73efa393d80ccb5c8817b8bd1830f333">getAggregateOperand</a> and <a href="#a2c112440d261a84437b343ee2b4c511f">getAggregateOperand</a>.</p>

</div>
</div>

### getIndexedType() {#a4e6ed8a1c14cfbc9d22aa336c96e4e0b}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">Type * llvm::sandboxir::ExtractValueInst::getIndexedType (<a href="/web-llvm/docs/api/classes/llvm/sandboxir/type">Type</a> * Agg, <a href="/web-llvm/docs/api/classes/llvm/arrayref">ArrayRef</a>&lt; unsigned &gt; Idxs)</td>
</tr>
</table>
</td>
<td class="doxyMemberLabelsRight">
<span class="doxyMemberLabels">
<span class="doxyMemberLabel static">static</span>
</span>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Returns the type of the element that would be extracted with an extractvalue instruction with the specified parameters.</p>


<p>Null is returned if the indices are invalid for the specified type.</p>


<p>Declaration at line 1123 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/sandboxir/instruction-h">Instruction.h</a>, definition at line 1538 of file <a href="/web-llvm/docs/api/files/lib/lib/sandboxir/instruction-cpp">Instruction.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/classes/llvm/sandboxir/type/#ae662f556252fe75768094c7976518409">llvm::sandboxir::Type::getContext</a>, <a href="/web-llvm/docs/api/classes/llvm/extractvalueinst/#a32a446b2a178bcd482521e3d273beeaf">llvm::ExtractValueInst::getIndexedType</a>, <a href="/web-llvm/docs/api/classes/llvm/sandboxir/context/#a5d72c7051da5356cbfbfa16ecb7dca8a">llvm::sandboxir::Context::getType</a> and <a href="/web-llvm/docs/api/classes/llvm/sandboxir/type/#a330bbaf89b90196df6960be4724513c6">llvm::sandboxir::Type::LLVMTy</a>.</p>

</div>
</div>

</div>

<hr/>

The documentation for this class was generated from the following files:

<ul>
<li><a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/sandboxir/instruction-h">Instruction.h</a></li>
<li><a href="/web-llvm/docs/api/files/lib/lib/sandboxir/instruction-cpp">Instruction.cpp</a></li>
</ul>

<hr/>

<p class="doxyGeneratedBy">Generated via <a href="https://github.com/xpack/doxygen2docusaurus">doxygen2docusaurus</a> by <a href="https://www.doxygen.nl">Doxygen</a> 1.14.0.</p>

</div>
