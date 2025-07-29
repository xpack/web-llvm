---

# DO NOT EDIT!
# Automatically generated via doxygen2docusaurus by Doxygen.

slug: /api/classes/llvm/ptrtointinst
custom_edit_url: null
toc_max_heading_level: 4
keywords:
  - doxygen
  - reference
  - class

---

<div class="doxyPage">

# `PtrToIntInst` Class

<p>This class represents a cast from a pointer to an integer. <a href="#details">More...</a></p>

## Declaration

<div class="doxyDeclaration">
class llvm::PtrToIntInst { ... }
</div>

## Included Headers

<div class="doxyIncludesList">#include "<a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/ir/instructions-h">llvm/IR/Instructions.h</a>"
</div>

## Base class

<table class="doxyMembersIndex">

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">class</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/castinst">CastInst</a></td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>This is the base class for all instructions that perform data casts. <a href="/web-llvm/docs/api/classes/llvm/castinst/#details">More...</a></p>
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

</table>

## Public Constructors Index

<table class="doxyMembersIndex">

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#abe54ccb1d2b334b625b8579e840e2d49">PtrToIntInst</a> (Value *S, Type *Ty, const Twine &amp;NameStr="", InsertPosition InsertBefore=nullptr)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Constructor with insert-before-instruction semantics. <a href="#abe54ccb1d2b334b625b8579e840e2d49">More...</a></p>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a220f067bbc33b6db6cc2c7ff5a912902">getPointerOperand</a> ()</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Gets the pointer operand. <a href="#a220f067bbc33b6db6cc2c7ff5a912902">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/value">Value</a> *</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a541950f244e5ba649e145ad8b386a27d">getPointerOperand</a> () const</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Gets the pointer operand. <a href="#a541950f244e5ba649e145ad8b386a27d">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">unsigned</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a378cf64c77de950ae67fc6e279e34620">getPointerAddressSpace</a> () const</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Returns the address space of the pointer operand. <a href="#a378cf64c77de950ae67fc6e279e34620">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

</table>

## Protected Member Functions Index

<table class="doxyMembersIndex">

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/ptrtointinst">PtrToIntInst</a> *</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#aea9834ebaa7797545bf6d263a66e9d2b">cloneImpl</a> () const</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Clone an identical <a href="/web-llvm/docs/api/classes/llvm/ptrtointinst">PtrToIntInst</a>. <a href="#aea9834ebaa7797545bf6d263a66e9d2b">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

</table>

## Public Static Functions Index

<table class="doxyMembersIndex">

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">static unsigned</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a75d1bebcc0111e2be176c0609d3be59c">getPointerOperandIndex</a> ()</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Gets the operand index of the pointer operand. <a href="#a75d1bebcc0111e2be176c0609d3be59c">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">static bool</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a98d03a442762a9facb0690a622b71537">classof</a> (const Instruction *I)</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a3fc9452fb94d5d13a7eff38a5ef98c44">classof</a> (const Value *V)</td>
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

<p>This class represents a cast from a pointer to an integer.</p>

<p>Definition at line 4851 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/ir/instructions-h">Instructions.h</a>.</p>


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


<p>Definition at line 4854 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/ir/instructions-h">Instructions.h</a>.</p>


<p>References <a href="#a87273cb892a8182f137567e6b631695e">Instruction</a> and <a href="#abe54ccb1d2b334b625b8579e840e2d49">PtrToIntInst</a>.</p>


<p>Referenced by <a href="#a98d03a442762a9facb0690a622b71537">classof</a> and <a href="#a87273cb892a8182f137567e6b631695e">Instruction</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Public Constructors

### PtrToIntInst() {#abe54ccb1d2b334b625b8579e840e2d49}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">PtrToIntInst::PtrToIntInst (<a href="/web-llvm/docs/api/classes/llvm/value">Value</a> * S, <a href="/web-llvm/docs/api/classes/llvm/type">Type</a> * Ty, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/twine">Twine</a> &amp; NameStr="", <a href="/web-llvm/docs/api/classes/llvm/insertposition">InsertPosition</a> InsertBefore=nullptr)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Constructor with insert-before-instruction semantics.</p>

<p>Declaration at line 4861 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/ir/instructions-h">Instructions.h</a>, definition at line 3394 of file <a href="/web-llvm/docs/api/files/lib/lib/ir/instructions-cpp">Instructions.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/silowercontrolflow-cpp/#a4868c5d81c5ccc98c47aeab6244346a0">assert</a>, <a href="/web-llvm/docs/api/classes/llvm/castinst/#a8eadc0b6c1d49a31d389dd611f44b08f">llvm::CastInst::CastInst</a>, <a href="/web-llvm/docs/api/classes/llvm/castinst/#af0e9f16b79d49af44209f202b31290a1">llvm::CastInst::castIsValid</a> and <a href="/web-llvm/docs/api/classes/llvm/castinst/#a3685b2128d8e6917000e4adc3b266ff6">llvm::CastInst::getOpcode</a>.</p>


<p>Referenced by <a href="#aea9834ebaa7797545bf6d263a66e9d2b">cloneImpl</a> and <a href="#a87273cb892a8182f137567e6b631695e">Instruction</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Public Member Functions

### getPointerAddressSpace() {#a378cf64c77de950ae67fc6e279e34620}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">unsigned llvm::PtrToIntInst::getPointerAddressSpace ()</td>
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

<p>Returns the address space of the pointer operand.</p>

<p>Definition at line 4876 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/ir/instructions-h">Instructions.h</a>.</p>


<p>References <a href="/web-llvm/docs/api/classes/llvm/type/#a5ab2d0b0f0b8ceec3b907184e7567197">llvm::Type::getPointerAddressSpace</a>, <a href="#a220f067bbc33b6db6cc2c7ff5a912902">getPointerOperand</a> and <a href="/web-llvm/docs/api/classes/llvm/value/#a0344a49526443edf90cc0aef3abd3337">llvm::Value::getType</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/classes/llvm/instcombinerimpl/#a50b0daca4f05a8d2af14aec07f64f3cc">llvm::InstCombinerImpl::visitPtrToInt</a>.</p>

</div>
</div>

### getPointerOperand() {#a220f067bbc33b6db6cc2c7ff5a912902}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">Value * llvm::PtrToIntInst::getPointerOperand ()</td>
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

<p>Gets the pointer operand.</p>

<p>Definition at line 4869 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/ir/instructions-h">Instructions.h</a>.</p>


<p>Reference <a href="/web-llvm/docs/api/classes/llvm/user/#aa0a2cb1582d1cec317bd205085469ca1">llvm::User::getOperand</a>.</p>


<p>Referenced by <a href="#a378cf64c77de950ae67fc6e279e34620">getPointerAddressSpace</a>, <a href="/web-llvm/docs/api/classes/llvm/instcombinerimpl/#a50b0daca4f05a8d2af14aec07f64f3cc">llvm::InstCombinerImpl::visitPtrToInt</a> and <a href="/web-llvm/docs/api/classes/anonymous-amdgpulowerbufferfatpointers-cpp-/splitptrstructs/#a5b6ac7240be29b8a3a611a734a45d4a6">anonymous{AMDGPULowerBufferFatPointers.cpp}::SplitPtrStructs::visitPtrToIntInst</a>.</p>

</div>
</div>

### getPointerOperand() {#a541950f244e5ba649e145ad8b386a27d}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">const Value * llvm::PtrToIntInst::getPointerOperand ()</td>
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

<p>Gets the pointer operand.</p>

<p>Definition at line 4871 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/ir/instructions-h">Instructions.h</a>.</p>


<p>Reference <a href="/web-llvm/docs/api/classes/llvm/user/#aa0a2cb1582d1cec317bd205085469ca1">llvm::User::getOperand</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Protected Member Functions

### cloneImpl() {#aea9834ebaa7797545bf6d263a66e9d2b}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">PtrToIntInst * PtrToIntInst::cloneImpl ()</td>
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

<p>Clone an identical <a href="/web-llvm/docs/api/classes/llvm/ptrtointinst">PtrToIntInst</a>.</p>

<p>Declaration at line 4857 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/ir/instructions-h">Instructions.h</a>, definition at line 4363 of file <a href="/web-llvm/docs/api/files/lib/lib/ir/instructions-cpp">Instructions.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/classes/llvm/user/#aa0a2cb1582d1cec317bd205085469ca1">llvm::User::getOperand</a>, <a href="/web-llvm/docs/api/classes/llvm/value/#a0344a49526443edf90cc0aef3abd3337">llvm::Value::getType</a> and <a href="#abe54ccb1d2b334b625b8579e840e2d49">PtrToIntInst</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Public Static Functions

### classof() {#a98d03a442762a9facb0690a622b71537}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool llvm::PtrToIntInst::classof (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/instruction">Instruction</a> * I)</td>
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



<p>Definition at line 4881 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/ir/instructions-h">Instructions.h</a>.</p>


<p>References <a href="/web-llvm/docs/api/files/lib/lib/support/md5-cpp/#ac0eafdc9ee161b71e7af98af736952fd">I</a> and <a href="#a87273cb892a8182f137567e6b631695e">Instruction</a>.</p>


<p>Referenced by <a href="#a3fc9452fb94d5d13a7eff38a5ef98c44">classof</a>.</p>

</div>
</div>

### classof() {#a3fc9452fb94d5d13a7eff38a5ef98c44}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool llvm::PtrToIntInst::classof (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/value">Value</a> * V)</td>
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



<p>Definition at line 4884 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/ir/instructions-h">Instructions.h</a>.</p>


<p>References <a href="/web-llvm/docs/api/namespaces/llvm/#ac4fc845f5ed92de63cd4474f128f5fc5">llvm::cast</a>, <a href="#a98d03a442762a9facb0690a622b71537">classof</a> and <a href="/web-llvm/docs/api/namespaces/llvm/#a92ca992e52dddc420f4b069cae06dfbe">llvm::isa</a>.</p>

</div>
</div>

### getPointerOperandIndex() {#a75d1bebcc0111e2be176c0609d3be59c}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">unsigned llvm::PtrToIntInst::getPointerOperandIndex ()</td>
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

<p>Gets the operand index of the pointer operand.</p>

<p>Definition at line 4873 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/ir/instructions-h">Instructions.h</a>.</p>

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

<p class="doxyGeneratedBy">Generated via <a href="https://github.com/xpack/doxygen2docusaurus">doxygen2docusaurus</a> by <a href="https://www.doxygen.nl">Doxygen</a> 1.15.0.</p>

</div>
