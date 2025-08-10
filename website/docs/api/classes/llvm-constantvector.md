---

# DO NOT EDIT!
# Automatically generated via doxygen2docusaurus by Doxygen.

slug: /api/classes/llvm/constantvector
custom_edit_url: null
toc_max_heading_level: 4
keywords:
  - doxygen
  - reference
  - class

---

<div class="doxyPage">

# `ConstantVector` Class

<p><a href="/web-llvm/docs/api/classes/llvm/constant">Constant</a> Vector Declarations. <a href="#details">More...</a></p>

## Declaration

<div class="doxyDeclaration">
class llvm::ConstantVector { ... }
</div>

## Included Headers

<div class="doxyIncludesList">#include "<a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/ir/constants-h">llvm/IR/Constants.h</a>"
</div>

## Base class

<table class="doxyMembersIndex">

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">class</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/constantaggregate">ConstantAggregate</a></td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Base class for aggregate constants (with operands). <a href="/web-llvm/docs/api/classes/llvm/constantaggregate/#details">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

</table>

## Friends Index

<table class="doxyMembersIndex">

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">struct</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a3303185b518020172a73c84adf57771e">ConstantAggrKeyType&lt; ConstantVector &gt;</a></td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a5bd16c2fbe755cda66b18d56761038ea">Constant</a></td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a6f4e7734419235821174786c6857bf60">ConstantVector</a> (VectorType *T, ArrayRef&lt; Constant * &gt; Val, AllocInfo AllocInfo)</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/fixedvectortype">FixedVectorType</a> *</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a905aa2c18ca16ed8304461695f373120">getType</a> () const</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Specialize the <a href="#a905aa2c18ca16ed8304461695f373120">getType()</a> method to always return a <a href="/web-llvm/docs/api/classes/llvm/fixedvectortype">FixedVectorType</a>, which reduces the amount of casting needed in parts of the compiler. <a href="#a905aa2c18ca16ed8304461695f373120">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/constant">Constant</a> *</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#aa2ea20974430e8820f962083ca421c05">getSplatValue</a> (bool AllowPoison=false) const</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>If all elements of the vector constant have the same value, return that value. <a href="#aa2ea20974430e8820f962083ca421c05">More...</a></p>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#af238f21a2519b540a426171b3051c6bc">destroyConstantImpl</a> ()</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Remove the constant from the constant table. <a href="#af238f21a2519b540a426171b3051c6bc">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/value">Value</a> *</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a26f0b3e4114653ff66b05f5f81ff1c05">handleOperandChangeImpl</a> (Value *From, Value *To)</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">static <a href="/web-llvm/docs/api/classes/llvm/constant">Constant</a> *</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ade9fa017ca3aa82f7694a47090547bc1">get</a> (ArrayRef&lt; Constant * &gt; V)</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">static <a href="/web-llvm/docs/api/classes/llvm/constant">Constant</a> *</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#aa3b241b35b0039b413faf1ef4e873eb7">getSplat</a> (ElementCount EC, Constant *Elt)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Return a <a href="/web-llvm/docs/api/classes/llvm/constantvector">ConstantVector</a> with the specified constant in each element. <a href="#aa3b241b35b0039b413faf1ef4e873eb7">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">static bool</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a1d4534ed3914224cd544eb3dc3f58f05">classof</a> (const Value *V)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Methods for support type inquiry through isa, cast, and dyn_cast: <a href="#a1d4534ed3914224cd544eb3dc3f58f05">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

</table>

## Private Static Functions Index

<table class="doxyMembersIndex">

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">static <a href="/web-llvm/docs/api/classes/llvm/constant">Constant</a> *</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a309f3c62954552f077916c5085761bc4">getImpl</a> (ArrayRef&lt; Constant * &gt; V)</td>
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

<p><a href="/web-llvm/docs/api/classes/llvm/constant">Constant</a> Vector Declarations.</p>

<p>Definition at line 511 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/ir/constants-h">Constants.h</a>.</p>


<div class="doxySectionDef">

## Friends

### Constant {#a5bd16c2fbe755cda66b18d56761038ea}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">friend class <a href="/web-llvm/docs/api/classes/llvm/constant">Constant</a></td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">


<p>Definition at line 513 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/ir/constants-h">Constants.h</a>.</p>


<p>References <a href="#a5bd16c2fbe755cda66b18d56761038ea">Constant</a> and <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/mips/mips16isellowering-cpp/#a0acb682b8260ab1c60b918599864e2e5">T</a>.</p>


<p>Referenced by <a href="#a5bd16c2fbe755cda66b18d56761038ea">Constant</a>, <a href="#ade9fa017ca3aa82f7694a47090547bc1">get</a>, <a href="#aa3b241b35b0039b413faf1ef4e873eb7">getSplat</a> and <a href="#aa2ea20974430e8820f962083ca421c05">getSplatValue</a>.</p>

</div>
</div>

### ConstantAggrKeyType&lt; ConstantVector &gt; {#a3303185b518020172a73c84adf57771e}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">friend struct <a href="/web-llvm/docs/api/structs/llvm/constantaggrkeytype">ConstantAggrKeyType</a>&lt; <a href="/web-llvm/docs/api/classes/llvm/constantvector">ConstantVector</a> &gt;</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">


<p>Definition at line 503 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/ir/constants-h">Constants.h</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Private Constructors

### ConstantVector() {#a6f4e7734419235821174786c6857bf60}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">ConstantVector::ConstantVector (<a href="/web-llvm/docs/api/classes/llvm/vectortype">VectorType</a> * T, <a href="/web-llvm/docs/api/classes/llvm/arrayref">ArrayRef</a>&lt; <a href="/web-llvm/docs/api/classes/llvm/constant">Constant</a> * &gt; Val, <a href="/web-llvm/docs/api/structs/llvm/user/allocinfo">AllocInfo</a> AllocInfo)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Declaration at line 515 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/ir/constants-h">Constants.h</a>, definition at line 1413 of file <a href="/web-llvm/docs/api/files/lib/lib/ir/constants-cpp">Constants.cpp</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Public Member Functions

### getSplatValue() {#aa2ea20974430e8820f962083ca421c05}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">Constant * ConstantVector::getSplatValue (bool AllowPoison=false)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>If all elements of the vector constant have the same value, return that value.</p>


<p>Otherwise, return nullptr. Ignore poison elements by setting AllowPoison to true.</p>


<p>Declaration at line 541 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/ir/constants-h">Constants.h</a>, definition at line 1744 of file <a href="/web-llvm/docs/api/files/lib/lib/ir/constants-cpp">Constants.cpp</a>.</p>


<p>References <a href="#a5bd16c2fbe755cda66b18d56761038ea">Constant</a>, <a href="/web-llvm/docs/api/classes/llvm/user/#addec638786f763d967811b45cb662f1f">llvm::User::getNumOperands</a>, <a href="/web-llvm/docs/api/classes/llvm/user/#aa0a2cb1582d1cec317bd205085469ca1">llvm::User::getOperand</a>, <a href="/web-llvm/docs/api/files/lib/lib/support/md5-cpp/#ac0eafdc9ee161b71e7af98af736952fd">I</a> and <a href="/web-llvm/docs/api/namespaces/llvm/#a92ca992e52dddc420f4b069cae06dfbe">llvm::isa</a>.</p>

</div>
</div>

### getType() {#a905aa2c18ca16ed8304461695f373120}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">FixedVectorType * llvm::ConstantVector::getType ()</td>
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

<p>Specialize the <a href="#a905aa2c18ca16ed8304461695f373120">getType()</a> method to always return a <a href="/web-llvm/docs/api/classes/llvm/fixedvectortype">FixedVectorType</a>, which reduces the amount of casting needed in parts of the compiler.</p>

<p>Definition at line 534 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/ir/constants-h">Constants.h</a>.</p>


<p>References <a href="/web-llvm/docs/api/namespaces/llvm/#ac4fc845f5ed92de63cd4474f128f5fc5">llvm::cast</a> and <a href="/web-llvm/docs/api/classes/llvm/value/#a0344a49526443edf90cc0aef3abd3337">llvm::Value::getType</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/spirv/spirvregularizer-cpp/#a70c9d5004bb64ce7c4ed2dab4acda63b">INITIALIZE_PASS</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Private Member Functions

### destroyConstantImpl() {#af238f21a2519b540a426171b3051c6bc}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void ConstantVector::destroyConstantImpl ()</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Remove the constant from the constant table.</p>

<p>Declaration at line 517 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/ir/constants-h">Constants.h</a>, definition at line 1704 of file <a href="/web-llvm/docs/api/files/lib/lib/ir/constants-cpp">Constants.cpp</a>.</p>

</div>
</div>

### handleOperandChangeImpl() {#a26f0b3e4114653ff66b05f5f81ff1c05}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">Value * ConstantVector::handleOperandChangeImpl (<a href="/web-llvm/docs/api/classes/llvm/value">Value</a> * From, <a href="/web-llvm/docs/api/classes/llvm/value">Value</a> * To)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Declaration at line 518 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/ir/constants-h">Constants.h</a>, definition at line 3368 of file <a href="/web-llvm/docs/api/files/lib/lib/ir/constants-cpp">Constants.cpp</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Public Static Functions

### classof() {#a1d4534ed3914224cd544eb3dc3f58f05}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool llvm::ConstantVector::classof (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/value">Value</a> * V)</td>
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

<p>Definition at line 544 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/ir/constants-h">Constants.h</a>.</p>

</div>
</div>

### get() {#ade9fa017ca3aa82f7694a47090547bc1}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">Constant * ConstantVector::get (<a href="/web-llvm/docs/api/classes/llvm/arrayref">ArrayRef</a>&lt; <a href="/web-llvm/docs/api/classes/llvm/constant">Constant</a> * &gt; V)</td>
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



<p>Declaration at line 522 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/ir/constants-h">Constants.h</a>, definition at line 1421 of file <a href="/web-llvm/docs/api/files/lib/lib/ir/constants-cpp">Constants.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/namespaces/llvm/callingconv/#ac6aa1387c4375260e2468eb5a77fdb4cafd841a49aec1539bc88abc8ff9e170fb">llvm::CallingConv::C</a>, <a href="#a5bd16c2fbe755cda66b18d56761038ea">Constant</a> and <a href="/web-llvm/docs/api/classes/llvm/fixedvectortype/#af9a870d5df50fe0133a410b7c9114c80">llvm::FixedVectorType::get</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/x86/x86isellowering-cpp/#a8af6dae0cb4e67d7004c888ed265f82a">combineTargetShuffle</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#af6674e64f01f197cffff55abcc6d2050">llvm::ConstantFoldBinaryInstruction</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#ad797efb6c6fbbb2038d5ed8f8379561f">llvm::ConstantFoldCastInstruction</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a293a0cb64e182e693cdd406f8da7ced5">llvm::ConstantFoldCompareInstruction</a>, <a href="/web-llvm/docs/api/namespaces/anonymous-constantfolding-cpp-/#a072e839b87b48a47db1efaad541c7dd0">anonymous{ConstantFolding.cpp}::ConstantFoldConstantImpl</a>, <a href="/web-llvm/docs/api/namespaces/anonymous-constantfolding-cpp-/#ad60130f0b45a3ff1e759b010afefb94d">anonymous{ConstantFolding.cpp}::ConstantFoldFixedVectorCall</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a7bf95d0980fad19452f4c9aca445af3f">llvm::ConstantFoldInsertElementInstruction</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a11c89e0918b007ef2cf1d6b03c4b4948">llvm::ConstantFoldSelectInstruction</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#addd1c6bc523b9a0eb56167da95dc5156">llvm::ConstantFoldShuffleVectorInstruction</a>, <a href="/web-llvm/docs/api/namespaces/anonymous-constantfolding-cpp-/#a294b49713de411cd8aadad66d82f205b">anonymous{ConstantFolding.cpp}::ConstantFoldStructCall</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a2c4fe17695dd008139cd08a7d460744e">llvm::ConstantFoldUnaryInstruction</a>, <a href="/web-llvm/docs/api/classes/llvm/shufflevectorinst/#ad06dcf793a8b91871327c682d6f3f909">llvm::ShuffleVectorInst::convertShuffleMaskForBitcode</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a673cf7e3d4e84d3e3dfa9dc000499cba">llvm::createBitMaskForGaps</a>, <a href="/web-llvm/docs/api/structs/anonymous-memorysanitizer-cpp-/memorysanitizervisitor/#a850fb4fba9984eb18393c06aa6fe3a51">anonymous{MemorySanitizer.cpp}::MemorySanitizerVisitor::createDppMask</a>, <a href="/web-llvm/docs/api/classes/llvm/irbuilderbase/#ae934d6e99e0516d606ae8e65ff6aed63">llvm::IRBuilderBase::CreateStepVector</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64isellowering-cpp/#a5aade91cf963bd6be461be24ff3a284c">createTblForTrunc</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a69211e2fb3d1eed7ee14964bfc04e261">llvm::FlushFPConstant</a>, <a href="/web-llvm/docs/api/namespaces/anonymous-constantfolding-cpp-/#aa5ea18feb56580024a1693b1f98fb3f6">anonymous{ConstantFolding.cpp}::FoldBitCast</a>, <a href="/web-llvm/docs/api/files/lib/lib/ir/constantfold-cpp/#a79061cbffefa2eccfe0d30d1c07eed78">FoldBitCast</a>, <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/instcombine/instcombinevectorops-cpp/#a01aa2c4724ae9bf421d1cfff3a1c7fa5">foldConstantInsEltIntoShuffle</a>, <a href="/web-llvm/docs/api/classes/llvm/instcombinerimpl/#acbf4c17d9f1b9f6729602a3c2a6c5b9d">llvm::InstCombinerImpl::foldVectorBinop</a>, <a href="/web-llvm/docs/api/classes/boupslp/shufflecostestimator/#a7d3b40cff3ff8c00007cf9a3f0d785f1">llvm::slpvectorizer::BoUpSLP::ShuffleCostEstimator::gather</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/x86/x86isellowering-cpp/#a1abbecb57e09bf906ab1503722015802">getConstantVector</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/x86/x86isellowering-cpp/#abee99e97f96cb26e6b8208e4d6c98fec">getConstantVector</a>, <a href="/web-llvm/docs/api/classes/llvm/constantexpr/#af46fd5126112a587bb12f09b1c0e385b">llvm::ConstantExpr::getExactLogBase2</a>, <a href="/web-llvm/docs/api/classes/llvm/instcombiner/#acf9cbfcb493b0042022c94230e9350e2">llvm::InstCombiner::getSafeVectorConstantForBinop</a>, <a href="#aa3b241b35b0039b413faf1ef4e873eb7">getSplat</a>, <a href="/web-llvm/docs/api/structs/anonymous-memorysanitizer-cpp-/memorysanitizervisitor/#a1f4b3d9a1db2a863f398981ea5c1d641">anonymous{MemorySanitizer.cpp}::MemorySanitizerVisitor::handleMulByConstant</a>, <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/scalar/sroa-cpp/#a75cf62ffe10261611bab4d74598ab0e4">insertVector</a>, <a href="/web-llvm/docs/api/groups/llvmccorevalueconstantcomposite/#ga41cff8b1e11707f8298ddf0530e5a995">LLVMConstVector</a>, <a href="/web-llvm/docs/api/classes/llvm/hexagontargetlowering/#a5098d901f0c198948883d51adc575bcf">llvm::HexagonTargetLowering::LowerConstantPool</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/x86/x86isellowering-cpp/#a1d727a45696ad380a24b7fd8445182d8">LowerUINT_TO_FP_i64</a>, <a href="/web-llvm/docs/api/classes/anonymous-valuemapper-cpp-/mapper/#a7d5502a6047fb27d6c33ea2820608c2c">anonymous{ValueMapper.cpp}::Mapper::mapValue</a>, <a href="/web-llvm/docs/api/classes/llvm/constant/#a31dbd9cf336966a863e37c5653b6c134">llvm::Constant::mergeUndefsWith</a>, <a href="/web-llvm/docs/api/files/lib/lib/analysis/instructionsimplify-cpp/#a20728ab5a970c250099d56e721746064">propagateNaN</a>, <a href="/web-llvm/docs/api/classes/llvm/constant/#a174c8fd19771468c53842a7fde8ddce1">llvm::Constant::replaceUndefsWith</a>, <a href="/web-llvm/docs/api/classes/llvm/instcombinerimpl/#a37cce7aa1875173688e5971c5d6fa9e0">llvm::InstCombinerImpl::SimplifyDemandedVectorElts</a>, <a href="/web-llvm/docs/api/classes/llvm/x86targetlowering/#a5681faab09fa140f67d47577193f2665">llvm::X86TargetLowering::SimplifyDemandedVectorEltsForTargetShuffle</a>, <a href="/web-llvm/docs/api/files/lib/lib/analysis/instructionsimplify-cpp/#a38dc339806a701c1f11ec31cf76936ff">simplifySelectInst</a>, <a href="/web-llvm/docs/api/files/lib/lib/analysis/instructionsimplify-cpp/#a0bf04415ab72b83b24140635c6a7ea52">simplifyShuffleVectorInst</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/x86/x86instcombineintrinsic-cpp/#adbe56869c99b539068e8a442d8738dae">simplifyX86extrq</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/x86/x86instcombineintrinsic-cpp/#a158032a7de947df4dc475c236414f0a2">simplifyX86insertq</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/x86/x86instcombineintrinsic-cpp/#afbcb72ff3dcc4f5818f711ca564b9dc1">simplifyX86varShift</a> and <a href="/web-llvm/docs/api/classes/llvm/instcombinerimpl/#a411aa95504f966614c8f5d5aeeef1f04">llvm::InstCombinerImpl::visitSRem</a>.</p>

</div>
</div>

### getSplat() {#aa3b241b35b0039b413faf1ef4e873eb7}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">Constant * ConstantVector::getSplat (<a href="/web-llvm/docs/api/classes/llvm/elementcount">ElementCount</a> EC, <a href="/web-llvm/docs/api/classes/llvm/constant">Constant</a> * Elt)</td>
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

<p>Return a <a href="/web-llvm/docs/api/classes/llvm/constantvector">ConstantVector</a> with the specified constant in each element.</p>


<p>Note that this might not return an instance of <a href="/web-llvm/docs/api/classes/llvm/constantvector">ConstantVector</a></p>


<p>Declaration at line 530 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/ir/constants-h">Constants.h</a>, definition at line 1472 of file <a href="/web-llvm/docs/api/files/lib/lib/ir/constants-cpp">Constants.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/namespaces/llvm/#ac4fc845f5ed92de63cd4474f128f5fc5">llvm::cast</a>, <a href="#a5bd16c2fbe755cda66b18d56761038ea">Constant</a>, <a href="/web-llvm/docs/api/classes/llvm/constantaggregatezero/#abfa1cf8b4348407b167f93bc7c01055f">llvm::ConstantAggregateZero::get</a>, <a href="#ade9fa017ca3aa82f7694a47090547bc1">get</a>, <a href="/web-llvm/docs/api/classes/llvm/poisonvalue/#a1bf08613fb664a2e377a9a72c59a6b66">llvm::PoisonValue::get</a>, <a href="/web-llvm/docs/api/classes/llvm/undefvalue/#a4ae5ff22b700a42bcc5d889233721335">llvm::UndefValue::get</a>, <a href="/web-llvm/docs/api/classes/llvm/vectortype/#a861be1e2092622462053c6d31dddbfd5">llvm::VectorType::get</a>, <a href="/web-llvm/docs/api/classes/llvm/constantexpr/#a64d6bd55aa4447bb25f1361993223450">llvm::ConstantExpr::getInsertElement</a>, <a href="/web-llvm/docs/api/classes/llvm/type/#a05186fa23e4d11b9855a9599ba87a4b7">llvm::Type::getInt64Ty</a>, <a href="/web-llvm/docs/api/classes/llvm/constantexpr/#a6f6506f0bc515fe29da3b58565300017">llvm::ConstantExpr::getShuffleVector</a>, <a href="/web-llvm/docs/api/classes/llvm/constantdatavector/#a44124e702dc442346bd6202bb03e593b">llvm::ConstantDataVector::getSplat</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a92ca992e52dddc420f4b069cae06dfbe">llvm::isa</a>, <a href="/web-llvm/docs/api/classes/llvm/constantdatasequential/#afdcd0a1d482f4048baba27f0bc051411">llvm::ConstantDataSequential::isElementTypeCompatible</a>, <a href="/web-llvm/docs/api/files/lib/lib/ir/constants-cpp/#ab76da5b7a9f69067436e3346458a875e">UseConstantFPForFixedLengthSplat</a>, <a href="/web-llvm/docs/api/files/lib/lib/ir/constants-cpp/#a8dc603949c7be710e926d9585b6b6f2b">UseConstantFPForScalableSplat</a>, <a href="/web-llvm/docs/api/files/lib/lib/ir/constants-cpp/#a41593aef66ded35c17e5ee7390db0c59">UseConstantIntForFixedLengthSplat</a> and <a href="/web-llvm/docs/api/files/lib/lib/ir/constants-cpp/#a29794bed9379c8c9d9522d233458ddd4">UseConstantIntForScalableSplat</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/files/lib/lib/analysis/instructionsimplify-cpp/#adc235173f78d0b2a260bb5438267139e">computePointerDifference</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#af6674e64f01f197cffff55abcc6d2050">llvm::ConstantFoldBinaryInstruction</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#ad797efb6c6fbbb2038d5ed8f8379561f">llvm::ConstantFoldCastInstruction</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a293a0cb64e182e693cdd406f8da7ced5">llvm::ConstantFoldCompareInstruction</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a491cbe61681e7c63ac7d01ce209a4682">llvm::ConstantFoldGetElementPtr</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#addd1c6bc523b9a0eb56167da95dc5156">llvm::ConstantFoldShuffleVectorInstruction</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a2c4fe17695dd008139cd08a7d460744e">llvm::ConstantFoldUnaryInstruction</a>, <a href="/web-llvm/docs/api/structs/anonymous-memorysanitizer-cpp-/memorysanitizervisitor/#a06d139c7ee04d81813f05083f784f67b">anonymous{MemorySanitizer.cpp}::MemorySanitizerVisitor::constToIntPtr</a>, <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/instcombine/instcombinecompares-cpp/#a291e8c83a8c02664076faa0896f1dbc4">createLogicFromTable</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/directx/dxilintrinsicexpansion-cpp/#ae2198d73f3c2de2cee53f3d15db39abe">expandAbs</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/directx/dxilintrinsicexpansion-cpp/#adc12bf3c911b1e25c4a14ce8f4ad7634">expandAnyOrAllIntrinsic</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/directx/dxilintrinsicexpansion-cpp/#ab26ebd710695202964347075355c501d">expandExpIntrinsic</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/directx/dxilintrinsicexpansion-cpp/#a8be283da675a1b678e17fd283f14945c">expandLogIntrinsic</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/directx/dxilintrinsicexpansion-cpp/#a7b29eea052e72ee9e9d598d992aa82e2">expandStepIntrinsic</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a69211e2fb3d1eed7ee14964bfc04e261">llvm::FlushFPConstant</a>, <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/instcombine/instcombinecompares-cpp/#a26105b2c5dc3071155303a10ef8c3923">foldVectorCmp</a>, <a href="/web-llvm/docs/api/classes/boupslp/shufflecostestimator/#a7d3b40cff3ff8c00007cf9a3f0d785f1">llvm::slpvectorizer::BoUpSLP::ShuffleCostEstimator::gather</a>, <a href="/web-llvm/docs/api/classes/llvm/constantfp/#ac698873f7b353f3a37cb8577b74acf72">llvm::ConstantFP::get</a>, <a href="/web-llvm/docs/api/classes/llvm/constantfp/#a5eb8f7a5d3cfdd127ad9db2e425e14eb">llvm::ConstantFP::get</a>, <a href="/web-llvm/docs/api/classes/llvm/constantfp/#a009b3ec306eb0a0f09616000d59062db">llvm::ConstantFP::get</a>, <a href="/web-llvm/docs/api/classes/llvm/constantint/#abbea9023c416eec84936925717eea370">llvm::ConstantInt::get</a>, <a href="/web-llvm/docs/api/classes/llvm/constantint/#a969709dd49c28865a482d8b870f87c46">llvm::ConstantInt::get</a>, <a href="/web-llvm/docs/api/classes/llvm/constant/#a4d51384de6e1798bb6aa875aebeea9f0">llvm::Constant::getAllOnesValue</a>, <a href="/web-llvm/docs/api/classes/anonymous-hexagonvectorcombine-cpp-/hexagonvectorcombine/#a7e5734d2a814bfa1aea953e1685df678">anonymous{HexagonVectorCombine.cpp}::HexagonVectorCombine::getConstSplat</a>, <a href="/web-llvm/docs/api/classes/llvm/constantint/#a0f06dab61f3f83b6b36caa6f2f15e013">llvm::ConstantInt::getFalse</a>, <a href="/web-llvm/docs/api/classes/anonymous-hexagonvectorcombine-cpp-/hexagonvectorcombine/#a484c25c2e1d843bdf3009c7fff82607b">anonymous{HexagonVectorCombine.cpp}::HexagonVectorCombine::getFullValue</a>, <a href="/web-llvm/docs/api/classes/llvm/constantexpr/#aa0e2f7f2755f0a5cb30f1cc35957cb27">llvm::ConstantExpr::getGetElementPtr</a>, <a href="/web-llvm/docs/api/classes/llvm/constantfp/#a6f2864671b22c9f6135b6ae5d41bcf54">llvm::ConstantFP::getInfinity</a>, <a href="/web-llvm/docs/api/classes/llvm/constant/#a0154da1d06b29a1d5649607ae2dfc389">llvm::Constant::getIntegerValue</a>, <a href="/web-llvm/docs/api/classes/llvm/constantfp/#ab21342133676f10340dc3f541b128f24">llvm::ConstantFP::getNaN</a>, <a href="/web-llvm/docs/api/classes/anonymous-hexagonvectorcombine-cpp-/hexagonvectorcombine/#af6ada80a87f31679cc7ab3e579349b32">anonymous{HexagonVectorCombine.cpp}::HexagonVectorCombine::getNullValue</a>, <a href="/web-llvm/docs/api/classes/llvm/spirvglobalregistry/#a3dddf52f700258ac37fa137527588809">llvm::SPIRVGlobalRegistry::getOrCreateConsIntVector</a>, <a href="/web-llvm/docs/api/classes/llvm/spirvglobalregistry/#aea5285dbe63b422dcaf313ec0fe7473d">llvm::SPIRVGlobalRegistry::getOrCreateConstVector</a>, <a href="/web-llvm/docs/api/classes/llvm/spirvglobalregistry/#abea0d5a07369a9502280335b276b3ccb">llvm::SPIRVGlobalRegistry::getOrCreateConstVector</a>, <a href="/web-llvm/docs/api/classes/llvm/constantfp/#ae1c0cea3240ade5ee715cdaadd6166ca">llvm::ConstantFP::getQNaN</a>, <a href="/web-llvm/docs/api/classes/llvm/constantfp/#a2d4899e7eb5175d079ff8523d226ded9">llvm::ConstantFP::getSNaN</a>, <a href="/web-llvm/docs/api/classes/llvm/constantdatavector/#a44124e702dc442346bd6202bb03e593b">llvm::ConstantDataVector::getSplat</a>, <a href="/web-llvm/docs/api/classes/llvm/constantint/#a1d728e83e9e0fa85b0b58b33ec9c3197">llvm::ConstantInt::getTrue</a>, <a href="/web-llvm/docs/api/classes/llvm/constantfp/#a75071440d60c24178371ca1299f4ef07">llvm::ConstantFP::getZero</a> and <a href="/web-llvm/docs/api/namespaces/llvm/fuzzerop/#a5172beb0382e24b2305c8bc0e46ee1f4">llvm::fuzzerop::makeConstantsWithType</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Private Static Functions

### getImpl() {#a309f3c62954552f077916c5085761bc4}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">Constant * ConstantVector::getImpl (<a href="/web-llvm/docs/api/classes/llvm/arrayref">ArrayRef</a>&lt; <a href="/web-llvm/docs/api/classes/llvm/constant">Constant</a> * &gt; V)</td>
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



<p>Declaration at line 525 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/ir/constants-h">Constants.h</a>, definition at line 1428 of file <a href="/web-llvm/docs/api/files/lib/lib/ir/constants-cpp">Constants.cpp</a>.</p>

</div>
</div>

</div>

<hr/>

The documentation for this class was generated from the following files:

<ul>
<li><a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/ir/constants-h">Constants.h</a></li>
<li><a href="/web-llvm/docs/api/files/lib/lib/ir/constants-cpp">Constants.cpp</a></li>
</ul>

<hr/>

<p class="doxyGeneratedBy">Generated via <a href="https://xpack.github.io/doxygen2docusaurus">doxygen2docusaurus</a> 2.0.0 by <a href="https://www.doxygen.nl">Doxygen</a> 1.15.0.</p>

</div>
