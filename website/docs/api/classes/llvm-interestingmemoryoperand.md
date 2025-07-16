---

# DO NOT EDIT!
# Automatically generated via doxygen2docusaurus by Doxygen.

slug: /api/classes/llvm/interestingmemoryoperand
custom_edit_url: null
toc_max_heading_level: 4
keywords:
  - doxygen
  - reference
  - class

---

<div class="doxyPage">

# The `InterestingMemoryOperand` Class Reference



## Declaration

<div class="doxyDeclaration">
class llvm::InterestingMemoryOperand { ... }
</div>

## Included Headers

<div class="doxyIncludesList">#include "<a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/transforms/include/llvm/transforms/instrumentation/addresssanitizercommon-h">llvm/Transforms/Instrumentation/AddressSanitizerCommon.h</a>"
</div>

## Public Constructors Index

<table class="doxyMembersIndex">

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#aeecf413732260947c9a170f380df9a5f">InterestingMemoryOperand</a> (Instruction *I, unsigned OperandNo, bool IsWrite, class Type *OpType, MaybeAlign Alignment, Value *MaybeMask=nullptr, Value *MaybeEVL=nullptr, Value *MaybeStride=nullptr)</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/instruction">Instruction</a> *</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#aadbb9468214087969b31815059b46c70">getInsn</a> ()</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ad8c22d08a24da667e9e218230faafa68">getPtr</a> ()</td>
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

## Public Member Attributes Index

<table class="doxyMembersIndex">

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/use">Use</a> *</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a7c19fa1627732c3e872871b7aafa1165">PtrUse</a></td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a7e5974f4bc7f2453c70e4148d4a68f21">IsWrite</a></td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a773c2d3ddf76c0c52d5d96382bfa6e72">OpType</a></td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/typesize">TypeSize</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#af7de3fa82f38cc4a2a7d4f051a4f9299">TypeStoreSize</a> = <a href="/web-llvm/docs/api/classes/llvm/typesize/#a003b4369b4130e669dc9139798e0193c">TypeSize::getFixed</a>(0)</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/structs/llvm/maybealign">MaybeAlign</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a48f4ff737824d3a86e04e4a9cd1e5b25">Alignment</a></td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ae083681bb438af6e7e8efe39b3adc8ef">MaybeMask</a></td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a9bd8dec583cb88d194dad7e45103527e">MaybeEVL</a></td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a1fa2b3b3c4ffe11dcab9e26e3ce39878">MaybeStride</a></td>
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


<p>Definition at line 25 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/transforms/include/llvm/transforms/instrumentation/addresssanitizercommon-h">AddressSanitizerCommon.h</a>.</p>


<div class="doxySectionDef">

## Public Constructors

### InterestingMemoryOperand() {#aeecf413732260947c9a170f380df9a5f}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">llvm::InterestingMemoryOperand::InterestingMemoryOperand (<a href="/web-llvm/docs/api/classes/llvm/instruction">Instruction</a> * I, unsigned OperandNo, bool IsWrite, class <a href="/web-llvm/docs/api/classes/llvm/type">Type</a> * OpType, <a href="/web-llvm/docs/api/structs/llvm/maybealign">MaybeAlign</a> Alignment, <a href="/web-llvm/docs/api/classes/llvm/value">Value</a> * MaybeMask=nullptr, <a href="/web-llvm/docs/api/classes/llvm/value">Value</a> * MaybeEVL=nullptr, <a href="/web-llvm/docs/api/classes/llvm/value">Value</a> * MaybeStride=nullptr)</td>
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



<p>Definition at line 39 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/transforms/include/llvm/transforms/instrumentation/addresssanitizercommon-h">AddressSanitizerCommon.h</a>.</p>


<p>References <a href="#a48f4ff737824d3a86e04e4a9cd1e5b25">Alignment</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/arm/armslshardening-cpp/#ad467c4ab9119043f9b7750ab986be61a">DL</a>, <a href="/web-llvm/docs/api/files/lib/lib/support/md5-cpp/#ac0eafdc9ee161b71e7af98af736952fd">I</a>, <a href="#a7e5974f4bc7f2453c70e4148d4a68f21">IsWrite</a>, <a href="#a9bd8dec583cb88d194dad7e45103527e">MaybeEVL</a>, <a href="#ae083681bb438af6e7e8efe39b3adc8ef">MaybeMask</a>, <a href="#a1fa2b3b3c4ffe11dcab9e26e3ce39878">MaybeStride</a>, <a href="#a773c2d3ddf76c0c52d5d96382bfa6e72">OpType</a>, <a href="#a7c19fa1627732c3e872871b7aafa1165">PtrUse</a> and <a href="#af7de3fa82f38cc4a2a7d4f051a4f9299">TypeStoreSize</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Public Member Functions

### getInsn() {#aadbb9468214087969b31815059b46c70}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">Instruction * llvm::InterestingMemoryOperand::getInsn ()</td>
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



<p>Definition at line 51 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/transforms/include/llvm/transforms/instrumentation/addresssanitizercommon-h">AddressSanitizerCommon.h</a>.</p>


<p>References <a href="/web-llvm/docs/api/namespaces/llvm/#ac4fc845f5ed92de63cd4474f128f5fc5">llvm::cast</a> and <a href="#a7c19fa1627732c3e872871b7aafa1165">PtrUse</a>.</p>

</div>
</div>

### getPtr() {#ad8c22d08a24da667e9e218230faafa68}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">Value * llvm::InterestingMemoryOperand::getPtr ()</td>
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



<p>Definition at line 53 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/transforms/include/llvm/transforms/instrumentation/addresssanitizercommon-h">AddressSanitizerCommon.h</a>.</p>


<p>Reference <a href="#a7c19fa1627732c3e872871b7aafa1165">PtrUse</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Public Member Attributes

### Alignment {#a48f4ff737824d3a86e04e4a9cd1e5b25}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">MaybeAlign llvm::InterestingMemoryOperand::Alignment</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 31 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/transforms/include/llvm/transforms/instrumentation/addresssanitizercommon-h">AddressSanitizerCommon.h</a>.</p>


<p>Referenced by <a href="#aeecf413732260947c9a170f380df9a5f">InterestingMemoryOperand</a>.</p>

</div>
</div>

### IsWrite {#a7e5974f4bc7f2453c70e4148d4a68f21}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool llvm::InterestingMemoryOperand::IsWrite</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 28 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/transforms/include/llvm/transforms/instrumentation/addresssanitizercommon-h">AddressSanitizerCommon.h</a>.</p>


<p>Referenced by <a href="#aeecf413732260947c9a170f380df9a5f">InterestingMemoryOperand</a>.</p>

</div>
</div>

### MaybeEVL {#a9bd8dec583cb88d194dad7e45103527e}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">Value* llvm::InterestingMemoryOperand::MaybeEVL</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 35 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/transforms/include/llvm/transforms/instrumentation/addresssanitizercommon-h">AddressSanitizerCommon.h</a>.</p>


<p>Referenced by <a href="#aeecf413732260947c9a170f380df9a5f">InterestingMemoryOperand</a>.</p>

</div>
</div>

### MaybeMask {#ae083681bb438af6e7e8efe39b3adc8ef}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">Value* llvm::InterestingMemoryOperand::MaybeMask</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 33 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/transforms/include/llvm/transforms/instrumentation/addresssanitizercommon-h">AddressSanitizerCommon.h</a>.</p>


<p>Referenced by <a href="#aeecf413732260947c9a170f380df9a5f">InterestingMemoryOperand</a>.</p>

</div>
</div>

### MaybeStride {#a1fa2b3b3c4ffe11dcab9e26e3ce39878}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">Value* llvm::InterestingMemoryOperand::MaybeStride</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 37 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/transforms/include/llvm/transforms/instrumentation/addresssanitizercommon-h">AddressSanitizerCommon.h</a>.</p>


<p>Referenced by <a href="#aeecf413732260947c9a170f380df9a5f">InterestingMemoryOperand</a>.</p>

</div>
</div>

### OpType {#a773c2d3ddf76c0c52d5d96382bfa6e72}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">Type* llvm::InterestingMemoryOperand::OpType</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 29 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/transforms/include/llvm/transforms/instrumentation/addresssanitizercommon-h">AddressSanitizerCommon.h</a>.</p>


<p>Referenced by <a href="#aeecf413732260947c9a170f380df9a5f">InterestingMemoryOperand</a>.</p>

</div>
</div>

### PtrUse {#a7c19fa1627732c3e872871b7aafa1165}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">Use* llvm::InterestingMemoryOperand::PtrUse</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 27 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/transforms/include/llvm/transforms/instrumentation/addresssanitizercommon-h">AddressSanitizerCommon.h</a>.</p>


<p>Referenced by <a href="#aadbb9468214087969b31815059b46c70">getInsn</a>, <a href="#ad8c22d08a24da667e9e218230faafa68">getPtr</a> and <a href="#aeecf413732260947c9a170f380df9a5f">InterestingMemoryOperand</a>.</p>

</div>
</div>

### TypeStoreSize {#af7de3fa82f38cc4a2a7d4f051a4f9299}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">TypeSize llvm::InterestingMemoryOperand::TypeStoreSize = <a href="/web-llvm/docs/api/classes/llvm/typesize/#a003b4369b4130e669dc9139798e0193c">TypeSize::getFixed</a>(0)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 30 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/transforms/include/llvm/transforms/instrumentation/addresssanitizercommon-h">AddressSanitizerCommon.h</a>.</p>


<p>Referenced by <a href="#aeecf413732260947c9a170f380df9a5f">InterestingMemoryOperand</a>.</p>

</div>
</div>

</div>

<hr/>

The documentation for this class was generated from the following file:

<ul>
<li><a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/transforms/include/llvm/transforms/instrumentation/addresssanitizercommon-h">AddressSanitizerCommon.h</a></li>
</ul>

<hr/>

<p class="doxyGeneratedBy">Generated via <a href="https://github.com/xpack/doxygen2docusaurus">doxygen2docusaurus</a> by <a href="https://www.doxygen.nl">Doxygen</a> 1.15.0.</p>

</div>
