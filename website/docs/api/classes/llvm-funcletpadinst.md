---

# DO NOT EDIT!
# Automatically generated via doxygen2docusaurus by Doxygen.

slug: /api/classes/llvm/funcletpadinst
custom_edit_url: null
toc_max_heading_level: 4
keywords:
  - doxygen
  - reference
  - class

---

<div class="doxyPage">

# `FuncletPadInst` Class



## Declaration

<div class="doxyDeclaration">
class llvm::FuncletPadInst { ... }
</div>

## Included Headers

<div class="doxyIncludesList">#include "<a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/ir/instrtypes-h">llvm/IR/InstrTypes.h</a>"
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

## Derived Classes

<table class="doxyMembersIndex">

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">class</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/catchpadinst">CatchPadInst</a></td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/cleanuppadinst">CleanupPadInst</a></td>
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
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">class</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a86896a55c60df500e45247ae6a90c67c">CatchPadInst</a></td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ac85ed97cd7c97f1a960bca1d12ce770e">CleanupPadInst</a></td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a2c84b79048ff148c91da0accb7f5d817">FuncletPadInst</a> (const FuncletPadInst &amp;CPI, AllocInfo AllocInfo)</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ab99c9bebc035a9e9bdb8345b6a7ca0ba">FuncletPadInst</a> (Instruction::FuncletPadOps Op, Value *ParentPad, ArrayRef&lt; Value * &gt; Args, AllocInfo AllocInfo, const Twine &amp;NameStr, InsertPosition InsertBefore)</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a99548d7e661d3bdbd436e7b6693b7ac4">DECLARE_TRANSPARENT_OPERAND_ACCESSORS</a> (Value)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Provide fast operand accessors. <a href="#a99548d7e661d3bdbd436e7b6693b7ac4">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">unsigned</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a73ad527c13c3bb6367aa1f507d28ac3e">arg_size</a> () const</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>arg_size - Return the number of funcletpad arguments. <a href="#a73ad527c13c3bb6367aa1f507d28ac3e">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/value">Value</a> *</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ac0292e8b8cfe9cfc5ecd1684f841955b">getParentPad</a> () const</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Convenience accessors. <a href="#ac0292e8b8cfe9cfc5ecd1684f841955b">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">void</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a86170a400cd0f64650a497310d18eda2">setParentPad</a> (Value *ParentPad)</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/value">Value</a> *</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#af8fcc98ff5354df31b46d4cac69514ab">getArgOperand</a> (unsigned i) const</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>getArgOperand/setArgOperand - Return/set the i-th funcletpad argument. <a href="#af8fcc98ff5354df31b46d4cac69514ab">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">void</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a48ccf888b5e0d52ce54edc14d5038ad1">setArgOperand</a> (unsigned i, Value *v)</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a0e8c14ca40c93e68a85fdb1c6b5bb264">arg_operands</a> ()</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>arg_operands - iteration adapter for range-for loops. <a href="#a0e8c14ca40c93e68a85fdb1c6b5bb264">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/user/#a00c91d41d6da00a839684a27eff9b717">const_op_range</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#af82801d1b464636a280b7c6ce3e87c15">arg_operands</a> () const</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>arg_operands - iteration adapter for range-for loops. <a href="#af82801d1b464636a280b7c6ce3e87c15">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

</table>

## Protected Member Functions Index

<table class="doxyMembersIndex">

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/funcletpadinst">FuncletPadInst</a> *</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ac4b0c9384c92dc6a7a4d9ceed9bb1da5">cloneImpl</a> () const</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#aeae9573e30b027e250971b1ec0290247">init</a> (Value *ParentPad, ArrayRef&lt; Value * &gt; Args, const Twine &amp;NameStr)</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">static bool</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a01af919a45a10157fe724b4733fa5165">classof</a> (const Instruction *I)</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a7db4b0a1722f99ba6005b60a7d23be8c">classof</a> (const Value *V)</td>
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


<p>Definition at line 2327 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/ir/instrtypes-h">InstrTypes.h</a>.</p>


<div class="doxySectionDef">

## Friends

### CatchPadInst {#a86896a55c60df500e45247ae6a90c67c}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">friend class <a href="/web-llvm/docs/api/classes/llvm/catchpadinst">CatchPadInst</a></td>
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


<p>Definition at line 2340 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/ir/instrtypes-h">InstrTypes.h</a>.</p>


<p>Reference <a href="#a86896a55c60df500e45247ae6a90c67c">CatchPadInst</a>.</p>


<p>Referenced by <a href="#a86896a55c60df500e45247ae6a90c67c">CatchPadInst</a> and <a href="/web-llvm/docs/api/classes/llvm/catchpadinst/#ad9be5a921e55fbe6157c03bbc4d294c9">llvm::CatchPadInst::Create</a>.</p>

</div>
</div>

### CleanupPadInst {#ac85ed97cd7c97f1a960bca1d12ce770e}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">friend class <a href="/web-llvm/docs/api/classes/llvm/cleanuppadinst">CleanupPadInst</a></td>
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


<p>Definition at line 2341 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/ir/instrtypes-h">InstrTypes.h</a>.</p>


<p>References <a href="#ac85ed97cd7c97f1a960bca1d12ce770e">CleanupPadInst</a> and <a href="#ac4b0c9384c92dc6a7a4d9ceed9bb1da5">cloneImpl</a>.</p>


<p>Referenced by <a href="#ac85ed97cd7c97f1a960bca1d12ce770e">CleanupPadInst</a>.</p>

</div>
</div>

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


<p>Definition at line 2339 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/ir/instrtypes-h">InstrTypes.h</a>.</p>


<p>Reference <a href="#a87273cb892a8182f137567e6b631695e">Instruction</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/classes/llvm/catchpadinst/#a53564b12e6a97556b4e502d03c8ecc2b">llvm::CatchPadInst::classof</a>, <a href="/web-llvm/docs/api/classes/llvm/cleanuppadinst/#ab4cbd9ecba3658377e0704c9915a8764">llvm::CleanupPadInst::classof</a>, <a href="#a01af919a45a10157fe724b4733fa5165">classof</a> and <a href="#a87273cb892a8182f137567e6b631695e">Instruction</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Private Constructors

### FuncletPadInst() {#a2c84b79048ff148c91da0accb7f5d817}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">FuncletPadInst::FuncletPadInst (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/funcletpadinst">FuncletPadInst</a> &amp; CPI, <a href="/web-llvm/docs/api/structs/llvm/user/allocinfo">AllocInfo</a> AllocInfo)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Declaration at line 2329 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/ir/instrtypes-h">InstrTypes.h</a>, definition at line 1097 of file <a href="/web-llvm/docs/api/files/lib/lib/ir/instructions-cpp">Instructions.cpp</a>.</p>

</div>
</div>

### FuncletPadInst() {#ab99c9bebc035a9e9bdb8345b6a7ca0ba}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">FuncletPadInst::FuncletPadInst (<a href="/web-llvm/docs/api/classes/llvm/instruction/#a40bc45469579b3adf3e4eb9383ec025f">Instruction::FuncletPadOps</a> Op, <a href="/web-llvm/docs/api/classes/llvm/value">Value</a> * ParentPad, <a href="/web-llvm/docs/api/classes/llvm/arrayref">ArrayRef</a>&lt; <a href="/web-llvm/docs/api/classes/llvm/value">Value</a> * &gt; Args, <a href="/web-llvm/docs/api/structs/llvm/user/allocinfo">AllocInfo</a> AllocInfo, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/twine">Twine</a> &amp; NameStr, <a href="/web-llvm/docs/api/classes/llvm/insertposition">InsertPosition</a> InsertBefore)</td>
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



<p>Declaration at line 2331 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/ir/instrtypes-h">InstrTypes.h</a>, definition at line 1105 of file <a href="/web-llvm/docs/api/files/lib/lib/ir/instructions-cpp">Instructions.cpp</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Public Member Functions

### arg\_operands() {#a0e8c14ca40c93e68a85fdb1c6b5bb264}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">op_range llvm::FuncletPadInst::arg_operands ()</td>
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

<p>arg_operands - iteration adapter for range-for loops.</p>

<p>Definition at line 2371 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/ir/instrtypes-h">InstrTypes.h</a>.</p>


<p>References <a href="/web-llvm/docs/api/classes/llvm/user/#a2eeb1c7ed1cfe403f2ae0470e36c07e2">llvm::User::op_begin</a> and <a href="/web-llvm/docs/api/classes/llvm/user/#af41f58e730804d10b91fcff39b035f74">llvm::User::op_end</a>.</p>

</div>
</div>

### arg\_operands() {#af82801d1b464636a280b7c6ce3e87c15}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">const_op_range llvm::FuncletPadInst::arg_operands ()</td>
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

<p>arg_operands - iteration adapter for range-for loops.</p>

<p>Definition at line 2374 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/ir/instrtypes-h">InstrTypes.h</a>.</p>


<p>References <a href="/web-llvm/docs/api/classes/llvm/user/#a2eeb1c7ed1cfe403f2ae0470e36c07e2">llvm::User::op_begin</a> and <a href="/web-llvm/docs/api/classes/llvm/user/#af41f58e730804d10b91fcff39b035f74">llvm::User::op_end</a>.</p>

</div>
</div>

### arg\_size() {#a73ad527c13c3bb6367aa1f507d28ac3e}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">unsigned llvm::FuncletPadInst::arg_size ()</td>
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

<p>arg_size - Return the number of funcletpad arguments.</p>

<p>Definition at line 2351 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/ir/instrtypes-h">InstrTypes.h</a>.</p>


<p>Reference <a href="/web-llvm/docs/api/classes/llvm/user/#addec638786f763d967811b45cb662f1f">llvm::User::getNumOperands</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/files/lib/lib/codegen/lib/codegen/selectiondag/selectiondagisel-cpp/#a49830d163fb836dbd4d3af87150b1bd9">mapWasmLandingPadIndex</a>.</p>

</div>
</div>

### DECLARE\_TRANSPARENT\_OPERAND\_ACCESSORS() {#a99548d7e661d3bdbd436e7b6693b7ac4}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">llvm::FuncletPadInst::DECLARE_TRANSPARENT_OPERAND_ACCESSORS (<a href="/web-llvm/docs/api/classes/llvm/value">Value</a>)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Provide fast operand accessors.</p>

<p>Definition at line 2347 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/ir/instrtypes-h">InstrTypes.h</a>.</p>

</div>
</div>

### getArgOperand() {#af8fcc98ff5354df31b46d4cac69514ab}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">Value * llvm::FuncletPadInst::getArgOperand (unsigned i)</td>
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

<p>getArgOperand/setArgOperand - Return/set the i-th funcletpad argument.</p>

<p>Definition at line 2367 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/ir/instrtypes-h">InstrTypes.h</a>.</p>


<p>Reference <a href="/web-llvm/docs/api/classes/llvm/user/#aa0a2cb1582d1cec317bd205085469ca1">llvm::User::getOperand</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/files/lib/lib/codegen/lib/codegen/selectiondag/selectiondagisel-cpp/#a49830d163fb836dbd4d3af87150b1bd9">mapWasmLandingPadIndex</a>.</p>

</div>
</div>

### getParentPad() {#ac0292e8b8cfe9cfc5ecd1684f841955b}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">Value * llvm::FuncletPadInst::getParentPad ()</td>
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

<p>Convenience accessors.</p>


<p>Return the outer EH-pad this funclet is nested within.</p>


<p>Note: This returns the associated <a href="/web-llvm/docs/api/classes/llvm/catchswitchinst">CatchSwitchInst</a> if this <a href="/web-llvm/docs/api/classes/llvm/funcletpadinst">FuncletPadInst</a> is a <a href="/web-llvm/docs/api/classes/llvm/catchpadinst">CatchPadInst</a>.</p>


<p>Definition at line 2359 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/ir/instrtypes-h">InstrTypes.h</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/classes/llvm/instruction/#a3e6d2896c39a84cfa6c47f34cdc584ff">llvm::Instruction::copyIRFlags</a>.</p>

</div>
</div>

### setArgOperand() {#a48ccf888b5e0d52ce54edc14d5038ad1}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void llvm::FuncletPadInst::setArgOperand (unsigned i, <a href="/web-llvm/docs/api/classes/llvm/value">Value</a> * v)</td>
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



<p>Definition at line 2368 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/ir/instrtypes-h">InstrTypes.h</a>.</p>


<p>Reference <a href="/web-llvm/docs/api/classes/llvm/user/#a5fa9b8e1842b354f64c1ba6be0a4a17f">llvm::User::setOperand</a>.</p>

</div>
</div>

### setParentPad() {#a86170a400cd0f64650a497310d18eda2}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void llvm::FuncletPadInst::setParentPad (<a href="/web-llvm/docs/api/classes/llvm/value">Value</a> * ParentPad)</td>
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



<p>Definition at line 2360 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/ir/instrtypes-h">InstrTypes.h</a>.</p>


<p>Reference <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/silowercontrolflow-cpp/#a4868c5d81c5ccc98c47aeab6244346a0">assert</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/classes/llvm/instruction/#a3e6d2896c39a84cfa6c47f34cdc584ff">llvm::Instruction::copyIRFlags</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Protected Member Functions

### cloneImpl() {#ac4b0c9384c92dc6a7a4d9ceed9bb1da5}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">FuncletPadInst * FuncletPadInst::cloneImpl ()</td>
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



<p>Declaration at line 2343 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/ir/instrtypes-h">InstrTypes.h</a>, definition at line 4471 of file <a href="/web-llvm/docs/api/files/lib/lib/ir/instructions-cpp">Instructions.cpp</a>.</p>


<p>Reference <a href="/web-llvm/docs/api/classes/llvm/user/#addec638786f763d967811b45cb662f1f">llvm::User::getNumOperands</a>.</p>


<p>Referenced by <a href="#ac85ed97cd7c97f1a960bca1d12ce770e">CleanupPadInst</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Private Member Functions

### init() {#aeae9573e30b027e250971b1ec0290247}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void FuncletPadInst::init (<a href="/web-llvm/docs/api/classes/llvm/value">Value</a> * ParentPad, <a href="/web-llvm/docs/api/classes/llvm/arrayref">ArrayRef</a>&lt; <a href="/web-llvm/docs/api/classes/llvm/value">Value</a> * &gt; Args, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/twine">Twine</a> &amp; NameStr)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Declaration at line 2335 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/ir/instrtypes-h">InstrTypes.h</a>, definition at line 1089 of file <a href="/web-llvm/docs/api/files/lib/lib/ir/instructions-cpp">Instructions.cpp</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Public Static Functions

### classof() {#a01af919a45a10157fe724b4733fa5165}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool llvm::FuncletPadInst::classof (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/instruction">Instruction</a> * I)</td>
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



<p>Definition at line 2379 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/ir/instrtypes-h">InstrTypes.h</a>.</p>


<p>References <a href="/web-llvm/docs/api/files/lib/lib/support/md5-cpp/#ac0eafdc9ee161b71e7af98af736952fd">I</a> and <a href="#a87273cb892a8182f137567e6b631695e">Instruction</a>.</p>


<p>Referenced by <a href="#a7db4b0a1722f99ba6005b60a7d23be8c">classof</a>.</p>

</div>
</div>

### classof() {#a7db4b0a1722f99ba6005b60a7d23be8c}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool llvm::FuncletPadInst::classof (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/value">Value</a> * V)</td>
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



<p>Definition at line 2380 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/ir/instrtypes-h">InstrTypes.h</a>.</p>


<p>References <a href="/web-llvm/docs/api/namespaces/llvm/#ac4fc845f5ed92de63cd4474f128f5fc5">llvm::cast</a>, <a href="#a01af919a45a10157fe724b4733fa5165">classof</a> and <a href="/web-llvm/docs/api/namespaces/llvm/#a92ca992e52dddc420f4b069cae06dfbe">llvm::isa</a>.</p>

</div>
</div>

</div>

<hr/>

The documentation for this class was generated from the following files:

<ul>
<li><a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/ir/instrtypes-h">InstrTypes.h</a></li>
<li><a href="/web-llvm/docs/api/files/lib/lib/ir/instructions-cpp">Instructions.cpp</a></li>
</ul>

<hr/>

<p class="doxyGeneratedBy">Generated via <a href="https://github.com/xpack/doxygen2docusaurus">doxygen2docusaurus</a> by <a href="https://www.doxygen.nl">Doxygen</a> 1.15.0.</p>

</div>
