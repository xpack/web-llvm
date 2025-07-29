---

# DO NOT EDIT!
# Automatically generated via doxygen2docusaurus by Doxygen.

slug: /api/classes/llvm/allocainst
custom_edit_url: null
toc_max_heading_level: 4
keywords:
  - doxygen
  - reference
  - class

---

<div class="doxyPage">

# `AllocaInst` Class

<p>an instruction to allocate memory on the stack <a href="#details">More...</a></p>

## Declaration

<div class="doxyDeclaration">
class llvm::AllocaInst { ... }
</div>

## Included Headers

<div class="doxyIncludesList">#include "<a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/ir/instructions-h">llvm/IR/Instructions.h</a>"
</div>

## Base class

<table class="doxyMembersIndex">

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">class</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/unaryinstruction">UnaryInstruction</a></td>
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

## Private Member Typedefs Index

<table class="doxyMembersIndex">

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">using</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ae33a775bcf5f4de4a651c3a7885b966d">AlignmentField</a> = <a href="/web-llvm/docs/api/classes/llvm/instruction/#a04f5e8259cfe79c39de8db8dd73747cb">AlignmentBitfieldElementT</a>&lt; 0 &gt;</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a5a587e02467e0887ba71a6e8f3b313a2">UsedWithInAllocaField</a> = <a href="/web-llvm/docs/api/classes/llvm/instruction/#a5575a4d18b30d5812be34d337378bf01">BoolBitfieldElementT</a>&lt; AlignmentField::NextBit &gt;</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a5c55da5520cb91e5c455aa4b7ff7983e">SwiftErrorField</a> = <a href="/web-llvm/docs/api/classes/llvm/instruction/#a5575a4d18b30d5812be34d337378bf01">BoolBitfieldElementT</a>&lt; UsedWithInAllocaField::NextBit &gt;</td>
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

</table>

## Public Constructors Index

<table class="doxyMembersIndex">

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#afc6f22df80d283b4469f0390d61fd94e">AllocaInst</a> (Type *Ty, unsigned AddrSpace, Value *ArraySize, const Twine &amp;Name, InsertPosition InsertBefore)</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a899bd58b3099eca4f778ab94130bc07d">AllocaInst</a> (Type *Ty, unsigned AddrSpace, const Twine &amp;Name, InsertPosition InsertBefore)</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a4e9132c0a4e72e51f7310163385d1d98">AllocaInst</a> (Type *Ty, unsigned AddrSpace, Value *ArraySize, Align Align, const Twine &amp;Name="", InsertPosition InsertBefore=nullptr)</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">bool</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#aea74164514e7164813ab30bcc4b7c557">isArrayAllocation</a> () const</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Return true if there is an allocation size parameter to the allocation instruction that is not 1. <a href="#aea74164514e7164813ab30bcc4b7c557">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/value">Value</a> *</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#af4283a4cef4e2b88f565d827d5857e14">getArraySize</a> () const</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Get the number of elements allocated. <a href="#af4283a4cef4e2b88f565d827d5857e14">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/value">Value</a> *</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ab8ea7e026b4ffc33dac82b184aee34ce">getArraySize</a> ()</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/pointertype">PointerType</a> *</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a5d19f3955a23e8eb2a974efcc8fb19da">getType</a> () const</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Overload to return most specific pointer type. <a href="#a5d19f3955a23e8eb2a974efcc8fb19da">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">unsigned</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ad2fb148dfac3182fce33be95fc4e9159">getAddressSpace</a> () const</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Return the address space for the allocation. <a href="#ad2fb148dfac3182fce33be95fc4e9159">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">std::optional&lt; <a href="/web-llvm/docs/api/classes/llvm/typesize">TypeSize</a> &gt;</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ad92f6c67d55ced3de1569ee791c38679">getAllocationSize</a> (const DataLayout &amp;DL) const</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Get allocation size in bytes. <a href="#ad92f6c67d55ced3de1569ee791c38679">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">std::optional&lt; <a href="/web-llvm/docs/api/classes/llvm/typesize">TypeSize</a> &gt;</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a28c9f4622595fd1e231834e260538941">getAllocationSizeInBits</a> (const DataLayout &amp;DL) const</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Get allocation size in bits. <a href="#a28c9f4622595fd1e231834e260538941">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/type">Type</a> *</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a9b5ec84ea363eca9e35ddca20a5313af">getAllocatedType</a> () const</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Return the type that is being allocated by the instruction. <a href="#a9b5ec84ea363eca9e35ddca20a5313af">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">void</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a477cdf70778ab7fa9d5f991413e11eb9">setAllocatedType</a> (Type *Ty)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>for use only in special circumstances that need to generically transform a whole instruction (eg: IR linking and vectorization). <a href="#a477cdf70778ab7fa9d5f991413e11eb9">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/structs/llvm/align">Align</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a42438d0a43720a6571c9138224481754">getAlign</a> () const</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Return the alignment of the memory that is being allocated by the instruction. <a href="#a42438d0a43720a6571c9138224481754">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">void</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#af3bb24b322533dbe8a63c84b18568fe1">setAlignment</a> (Align Align)</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a36e31f42170be95fc392dad696d9ba19">isStaticAlloca</a> () const</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Return true if this alloca is in the entry block of the function and is a constant size. <a href="#a36e31f42170be95fc392dad696d9ba19">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">bool</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a9bb98c4ac4cf77f5782e5e41f2c6f38a">isUsedWithInAlloca</a> () const</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Return true if this alloca is used as an inalloca argument to a call. <a href="#a9bb98c4ac4cf77f5782e5e41f2c6f38a">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">void</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a65c7643f31d548ce5dfe031d52a3f8fa">setUsedWithInAlloca</a> (bool V)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Specify whether this alloca is used to represent the arguments to a call. <a href="#a65c7643f31d548ce5dfe031d52a3f8fa">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">bool</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a3016b467a9ecb5506956f7d029509db5">isSwiftError</a> () const</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Return true if this alloca is used as a swifterror argument to a call. <a href="#a3016b467a9ecb5506956f7d029509db5">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">void</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a31eeebeefd320f6a2db4a867f568bee3">setSwiftError</a> (bool V)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Specify whether this alloca is used to represent a swifterror. <a href="#a31eeebeefd320f6a2db4a867f568bee3">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

</table>

## Protected Member Functions Index

<table class="doxyMembersIndex">

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/allocainst">AllocaInst</a> *</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a6a2dc8251ccd285b55edc3019e3a42bd">cloneImpl</a> () const</td>
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

<tr class="doxyMemberIndexTemplate">
<td class="doxyMemberIndexTemplate" colspan="2"><div>template &lt;typename Bitfield&gt;</div></td>
</tr>
<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemTypeTemplate" align="left" valign="top">void</td>
<td class="doxyMemberIndexItemNameTemplate" align="left" valign="top"><a href="#ad07208eefa2cf2c739c1b10533c70517">setSubclassData</a> (typename Bitfield::Type Value)</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/type">Type</a> *</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a8ef2e1131ec9c41812e4178e93e9fc2c">AllocatedType</a></td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a4f7392286bffd149ab0e3679e7d1e4fd">classof</a> (const Instruction *I)</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a2aeed7ebd03b4b16baaaeb42fe0a1838">classof</a> (const Value *V)</td>
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

<p>an instruction to allocate memory on the stack</p>

<p>Definition at line 63 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/ir/instructions-h">Instructions.h</a>.</p>


<div class="doxySectionDef">

## Private Member Typedefs

### AlignmentField {#ae33a775bcf5f4de4a651c3a7885b966d}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">using llvm::AllocaInst::AlignmentField =  AlignmentBitfieldElementT&lt;0&gt;</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 66 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/ir/instructions-h">Instructions.h</a>.</p>

</div>
</div>

### SwiftErrorField {#a5c55da5520cb91e5c455aa4b7ff7983e}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">using llvm::AllocaInst::SwiftErrorField =  BoolBitfieldElementT&lt;UsedWithInAllocaField::NextBit&gt;</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 68 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/ir/instructions-h">Instructions.h</a>.</p>

</div>
</div>

### UsedWithInAllocaField {#a5a587e02467e0887ba71a6e8f3b313a2}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">using llvm::AllocaInst::UsedWithInAllocaField =  BoolBitfieldElementT&lt;AlignmentField::NextBit&gt;</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 67 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/ir/instructions-h">Instructions.h</a>.</p>

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


<p>Definition at line 75 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/ir/instructions-h">Instructions.h</a>.</p>


<p>References <a href="#afc6f22df80d283b4469f0390d61fd94e">AllocaInst</a> and <a href="#a87273cb892a8182f137567e6b631695e">Instruction</a>.</p>


<p>Referenced by <a href="#a4f7392286bffd149ab0e3679e7d1e4fd">classof</a> and <a href="#a87273cb892a8182f137567e6b631695e">Instruction</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Public Constructors

### AllocaInst() {#afc6f22df80d283b4469f0390d61fd94e}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">AllocaInst::AllocaInst (<a href="/web-llvm/docs/api/classes/llvm/type">Type</a> * Ty, unsigned AddrSpace, <a href="/web-llvm/docs/api/classes/llvm/value">Value</a> * ArraySize, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/twine">Twine</a> &amp; Name, <a href="/web-llvm/docs/api/classes/llvm/insertposition">InsertPosition</a> InsertBefore)</td>
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



<p>Declaration at line 80 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/ir/instructions-h">Instructions.h</a>, definition at line 1208 of file <a href="/web-llvm/docs/api/files/lib/lib/ir/instructions-cpp">Instructions.cpp</a>.</p>


<p>References <a href="#afc6f22df80d283b4469f0390d61fd94e">AllocaInst</a> and <a href="/web-llvm/docs/api/files/lib/lib/ir/instructions-cpp/#a4c35e6c65a8ef063f0acbdd56264cad5">computeAllocaDefaultAlign</a>.</p>


<p>Referenced by <a href="#a899bd58b3099eca4f778ab94130bc07d">AllocaInst</a>, <a href="#afc6f22df80d283b4469f0390d61fd94e">AllocaInst</a>, <a href="#a6a2dc8251ccd285b55edc3019e3a42bd">cloneImpl</a> and <a href="#a87273cb892a8182f137567e6b631695e">Instruction</a>.</p>

</div>
</div>

### AllocaInst() {#a899bd58b3099eca4f778ab94130bc07d}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">AllocaInst::AllocaInst (<a href="/web-llvm/docs/api/classes/llvm/type">Type</a> * Ty, unsigned AddrSpace, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/twine">Twine</a> &amp; Name, <a href="/web-llvm/docs/api/classes/llvm/insertposition">InsertPosition</a> InsertBefore)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Declaration at line 83 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/ir/instructions-h">Instructions.h</a>, definition at line 1204 of file <a href="/web-llvm/docs/api/files/lib/lib/ir/instructions-cpp">Instructions.cpp</a>.</p>


<p>Reference <a href="#afc6f22df80d283b4469f0390d61fd94e">AllocaInst</a>.</p>

</div>
</div>

### AllocaInst() {#a4e9132c0a4e72e51f7310163385d1d98}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">AllocaInst::AllocaInst (<a href="/web-llvm/docs/api/classes/llvm/type">Type</a> * Ty, unsigned AddrSpace, <a href="/web-llvm/docs/api/classes/llvm/value">Value</a> * ArraySize, <a href="/web-llvm/docs/api/structs/llvm/align">Align</a> Align, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/twine">Twine</a> &amp; Name="", <a href="/web-llvm/docs/api/classes/llvm/insertposition">InsertPosition</a> InsertBefore=nullptr)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Declaration at line 86 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/ir/instructions-h">Instructions.h</a>, definition at line 1214 of file <a href="/web-llvm/docs/api/files/lib/lib/ir/instructions-cpp">Instructions.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/silowercontrolflow-cpp/#a4868c5d81c5ccc98c47aeab6244346a0">assert</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a73257f51950d9ea50955e3fb9c724a25">llvm::get</a>, <a href="/web-llvm/docs/api/files/lib/lib/ir/instructions-cpp/#abd4502cb507e24663c9bcf9129eb4060">getAISize</a>, <a href="/web-llvm/docs/api/classes/llvm/value/#ab3fc0225d8aaf8434026c3573f961f2c">llvm::Value::getContext</a>, <a href="#af3bb24b322533dbe8a63c84b18568fe1">setAlignment</a>, <a href="/web-llvm/docs/api/classes/llvm/value/#a35ee267850af7c235474a8c46c7ac5af">llvm::Value::setName</a> and <a href="/web-llvm/docs/api/classes/llvm/unaryinstruction/#ad93ca9b74c44e7d8c00c72405e51262d">llvm::UnaryInstruction::UnaryInstruction</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Public Member Functions

### getAddressSpace() {#ad2fb148dfac3182fce33be95fc4e9159}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">unsigned llvm::AllocaInst::getAddressSpace ()</td>
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

<p>Return the address space for the allocation.</p>

<p>Definition at line 104 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/ir/instructions-h">Instructions.h</a>.</p>


<p>References <a href="/web-llvm/docs/api/classes/llvm/pointertype/#af8aeced5e71d2589fa3e9791043af5cb">llvm::PointerType::getAddressSpace</a> and <a href="#a5d19f3955a23e8eb2a974efcc8fb19da">getType</a>.</p>


<p>Referenced by <a href="#a6a2dc8251ccd285b55edc3019e3a42bd">cloneImpl</a>, <a href="/web-llvm/docs/api/classes/llvm/webassemblyframelowering/#ae8c531c36381ca6a666ca73f740335cb">llvm::WebAssemblyFrameLowering::getLocalForStackObject</a>, <a href="/web-llvm/docs/api/structs/anonymous-attributorattributes-cpp-/aaallocationinfoimpl/#ac388d17329447d2fd72ceabf79fefeba">anonymous{AttributorAttributes.cpp}::AAAllocationInfoImpl::manifest</a>, <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/instcombine/instcombineloadstorealloca-cpp/#a25ea6e038ccdef52ab01b0ee3da9ee52">simplifyAllocaArraySize</a>, <a href="/web-llvm/docs/api/files/lib/lib/frontend/lib/frontend/openmp/ompirbuilder-cpp/#af7668ce8080668a4f0ceac24e70c9f00">targetParallelCallback</a> and <a href="/web-llvm/docs/api/classes/llvm/instcombinerimpl/#af99540103c8717d41b490fc2a1acad5c">llvm::InstCombinerImpl::visitAllocaInst</a>.</p>

</div>
</div>

### getAlign() {#a42438d0a43720a6571c9138224481754}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">Align llvm::AllocaInst::getAlign ()</td>
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

<p>Return the alignment of the memory that is being allocated by the instruction.</p>

<p>Definition at line 124 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/ir/instructions-h">Instructions.h</a>.</p>


<p>Reference <a href="/web-llvm/docs/api/classes/llvm/instruction/#a041694a1ea45996587ef9712d9a2bb1f">llvm::Instruction::getSubclassData</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/classes/anonymous-coroframe-cpp-/frametypebuilder/#a0644a32bfd97560ac89c5d6e9b0bf7ac">anonymous{CoroFrame.cpp}::FrameTypeBuilder::addFieldForAlloca</a>, <a href="/web-llvm/docs/api/classes/anonymous-coroframe-cpp-/frametypebuilder/#a0ee1f18526ee78ef18612b6a86dc16fc">anonymous{CoroFrame.cpp}::FrameTypeBuilder::addFieldForAllocas</a>, <a href="#a6a2dc8251ccd285b55edc3019e3a42bd">cloneImpl</a>, <a href="/web-llvm/docs/api/namespaces/anonymous-nvptxlowerargs-cpp-/#aafd9b42c5de69fbe2a25e6b94f8cc299">anonymous{NVPTXLowerArgs.cpp}::copyByValParam</a>, <a href="/web-llvm/docs/api/files/lib/lib/frontend/lib/frontend/openmp/ompirbuilder-cpp/#a3fb4884285f5bcb9a37d9378d1e33cd5">emitTargetTaskProxyFunction</a>, <a href="/web-llvm/docs/api/classes/anonymous-lowermatrixintrinsics-cpp-/lowermatrixintrinsics/#a7d8410ca3fc6fb227416067d3c2535d2">anonymous{LowerMatrixIntrinsics.cpp}::LowerMatrixIntrinsics::getNonAliasingPointer</a>, <a href="/web-llvm/docs/api/structs/anonymous-addresssanitizer-cpp-/functionstackpoisoner/#a2c1978d516a0154dd7f006e502ab4cfa">anonymous{AddressSanitizer.cpp}::FunctionStackPoisoner::handleDynamicAllocaCall</a>, <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/instcombine/instcombineloadstorealloca-cpp/#a9981d75cde69ea5ca9706536fa4bbab5">isDereferenceableForAllocaSize</a>, <a href="/web-llvm/docs/api/structs/anonymous-attributorattributes-cpp-/aaallocationinfoimpl/#ac388d17329447d2fd72ceabf79fefeba">anonymous{AttributorAttributes.cpp}::AAAllocationInfoImpl::manifest</a>, <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/instcombine/instcombineloadstorealloca-cpp/#a25ea6e038ccdef52ab01b0ee3da9ee52">simplifyAllocaArraySize</a>, <a href="/web-llvm/docs/api/files/lib/lib/codegen/lib/codegen/selectiondag/selectiondagbuilder-cpp/#ae8ee5af33e0f1b85755cf5a1e4951793">tryToElideArgumentCopy</a>, <a href="/web-llvm/docs/api/classes/anonymous-dxilflattenarrays-cpp-/dxilflattenarraysvisitor/#a29df0cec2acb067cfcb09eeeb726c7db">anonymous{DXILFlattenArrays.cpp}::DXILFlattenArraysVisitor::visitAllocaInst</a> and <a href="/web-llvm/docs/api/classes/llvm/instcombinerimpl/#af99540103c8717d41b490fc2a1acad5c">llvm::InstCombinerImpl::visitAllocaInst</a>.</p>

</div>
</div>

### getAllocatedType() {#a9b5ec84ea363eca9e35ddca20a5313af}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">Type * llvm::AllocaInst::getAllocatedType ()</td>
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

<p>Return the type that is being allocated by the instruction.</p>

<p>Definition at line 117 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/ir/instructions-h">Instructions.h</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/classes/anonymous-coroframe-cpp-/frametypebuilder/#a0644a32bfd97560ac89c5d6e9b0bf7ac">anonymous{CoroFrame.cpp}::FrameTypeBuilder::addFieldForAlloca</a>, <a href="#a6a2dc8251ccd285b55edc3019e3a42bd">cloneImpl</a>, <a href="/web-llvm/docs/api/classes/llvm/openmpirbuilder/#a0af3c7a02c1325c04c59f857604bd4f3">llvm::OpenMPIRBuilder::createTask</a>, <a href="/web-llvm/docs/api/classes/llvm/openmpirbuilder/#a827b80924bcd29f32b772a4ed162fb68">llvm::OpenMPIRBuilder::emitNonContiguousDescriptor</a>, <a href="/web-llvm/docs/api/classes/llvm/openmpirbuilder/#a752e863c1af5fe463d0f08574492c12f">llvm::OpenMPIRBuilder::emitOffloadingArrays</a>, <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/coroutines/coroframe-cpp/#a43a2acbd71eac7be9bdd1094a21bd6ab">emitSetAndGetSwiftErrorValueAround</a>, <a href="/web-llvm/docs/api/classes/anonymous-expandvariadics-cpp-/expandvariadics/#ac4cd023a642d3b6295e4c1c6db359460">anonymous{ExpandVariadics.cpp}::ExpandVariadics::expandCall</a>, <a href="/web-llvm/docs/api/files/lib/lib/codegen/lib/codegen/selectiondag/selectiondagbuilder-cpp/#aa469012eee439764e752d32b1a557821">findArgumentCopyElisionCandidates</a>, <a href="/web-llvm/docs/api/classes/llvm/memtag/stackinfobuilder/#adcaea10733b9350e0f00307e44ef2b0b">llvm::memtag::StackInfoBuilder::getAllocaInterestingness</a>, <a href="#ad92f6c67d55ced3de1569ee791c38679">getAllocationSize</a>, <a href="/web-llvm/docs/api/namespaces/llvm/at/#ae56d26e266b1d9f9e3e8abef9cd76d2a">llvm::at::getAssignmentInfo</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/amdgputargettransforminfo-cpp/#aa883d40ffa8836538699a7974632d0a0">getCallArgsTotalAllocaSize</a>, <a href="/web-llvm/docs/api/classes/llvm/gcnttiimpl/#ab2a358830eca13fbd32b219f5318a7d8">llvm::GCNTTIImpl::getCallerAllocaCost</a>, <a href="/web-llvm/docs/api/classes/llvm/webassemblyframelowering/#ae8c531c36381ca6a666ca73f740335cb">llvm::WebAssemblyFrameLowering::getLocalForStackObject</a>, <a href="/web-llvm/docs/api/namespaces/anonymous-stacksafetyanalysis-cpp-/#a9cd19dcbd2a7e975097b8bd795ac1a98">anonymous{StackSafetyAnalysis.cpp}::getStaticAllocaSizeRange</a>, <a href="/web-llvm/docs/api/classes/llvm/amdgputtiimpl/#a99fc6c25163b324f8642658b54e77687">llvm::AMDGPUTTIImpl::getUnrollingPreferences</a>, <a href="/web-llvm/docs/api/structs/anonymous-addresssanitizer-cpp-/functionstackpoisoner/#a2c1978d516a0154dd7f006e502ab4cfa">anonymous{AddressSanitizer.cpp}::FunctionStackPoisoner::handleDynamicAllocaCall</a>, <a href="/web-llvm/docs/api/classes/anonymous-expandvariadics-cpp-/expandvariadics/expandedcallframe/#ab8c5cd9d201a04d9daefd0daf67e133c">anonymous{ExpandVariadics.cpp}::ExpandVariadics::ExpandedCallFrame::initializeStructAlloca</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#ab5a3ac0a249da0743dac1bd816d8e5d5">llvm::InlineFunction</a>, <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/coroutines/coroframe-cpp/#af0885df5b78cc732639a9d52a87d040e">insertSpills</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a5023b360abc7a5d1612061fba30003a6">llvm::isAllocaPromotable</a>, <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/utils/local-cpp/#a7e06c0b653fcb0e20fbec6bee3d3d40d">isArray</a>, <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/instcombine/instcombineloadstorealloca-cpp/#a9981d75cde69ea5ca9706536fa4bbab5">isDereferenceableForAllocaSize</a>, <a href="/web-llvm/docs/api/structs/anonymous-addresssanitizer-cpp-/addresssanitizer/#a3b2938393443d2c8a8e005292eed060f">anonymous{AddressSanitizer.cpp}::AddressSanitizer::isInterestingAlloca</a>, <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/utils/local-cpp/#a226deca7d8508b6b646c8596d4c174a7">isStructure</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/amdgpupromotealloca-cpp/#ac7bc9cad62836c4073e29612a6b74071">isSupportedMemset</a>, <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/scalar/rewritestatepointsforgc-cpp/#a55412d2c237115c95f20e12ba0d95922">relocationViaAlloca</a>, <a href="/web-llvm/docs/api/classes/anonymous-sroa-cpp-/sroa/#a8317779540f30fe6a5dda2359f023675">anonymous{SROA.cpp}::SROA::runSROA</a>, <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/instcombine/instcombineloadstorealloca-cpp/#a25ea6e038ccdef52ab01b0ee3da9ee52">simplifyAllocaArraySize</a>, <a href="/web-llvm/docs/api/structs/anonymous-addresssanitizer-cpp-/functionstackpoisoner/#a2d3b181e57e15921dd726d62c5f68a5c">anonymous{AddressSanitizer.cpp}::FunctionStackPoisoner::visitAllocaInst</a>, <a href="/web-llvm/docs/api/classes/anonymous-dxilflattenarrays-cpp-/dxilflattenarraysvisitor/#a29df0cec2acb067cfcb09eeeb726c7db">anonymous{DXILFlattenArrays.cpp}::DXILFlattenArraysVisitor::visitAllocaInst</a>, <a href="/web-llvm/docs/api/classes/anonymous-webassemblyreftypemem2local-cpp-/webassemblyreftypemem2local/#a9ad64c3f2f8f51ff7edc41ed024e022b">anonymous{WebAssemblyRefTypeMem2Local.cpp}::WebAssemblyRefTypeMem2Local::visitAllocaInst</a> and <a href="/web-llvm/docs/api/classes/llvm/instcombinerimpl/#af99540103c8717d41b490fc2a1acad5c">llvm::InstCombinerImpl::visitAllocaInst</a>.</p>

</div>
</div>

### getAllocationSize() {#ad92f6c67d55ced3de1569ee791c38679}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">std::optional&lt; TypeSize &gt; AllocaInst::getAllocationSize (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/datalayout">DataLayout</a> &amp; DL)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Get allocation size in bytes.</p>


<p>Returns std::nullopt if size can't be determined, e.g. in case of a VLA.</p>


<p>Declaration at line 110 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/ir/instructions-h">Instructions.h</a>, definition at line 64 of file <a href="/web-llvm/docs/api/files/lib/lib/ir/instructions-cpp">Instructions.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/silowercontrolflow-cpp/#a4868c5d81c5ccc98c47aeab6244346a0">assert</a>, <a href="/web-llvm/docs/api/namespaces/llvm/callingconv/#ac6aa1387c4375260e2468eb5a77fdb4cafd841a49aec1539bc88abc8ff9e170fb">llvm::CallingConv::C</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a55fc80e21802a32962e170b06a030e27">llvm::checkedMulUnsigned</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/arm/armslshardening-cpp/#ad467c4ab9119043f9b7750ab986be61a">DL</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a22eeee01734061ac1b31ccd994c49eef">llvm::dyn_cast</a>, <a href="#a9b5ec84ea363eca9e35ddca20a5313af">getAllocatedType</a>, <a href="#af4283a4cef4e2b88f565d827d5857e14">getArraySize</a>, <a href="/web-llvm/docs/api/classes/llvm/typesize/#a003b4369b4130e669dc9139798e0193c">llvm::TypeSize::getFixed</a>, <a href="#aea74164514e7164813ab30bcc4b7c557">isArrayAllocation</a> and <a href="/web-llvm/docs/api/files/lib/lib/analysis/inlineorder-cpp/#a7ee6f0cb51c3b9056199e9a0001fe8c3a6f6cb72d544962fa333e2e34ce64f719">Size</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/namespaces/anonymous-nvptxlowerargs-cpp-/#aafd9b42c5de69fbe2a25e6b94f8cc299">anonymous{NVPTXLowerArgs.cpp}::copyByValParam</a>, <a href="/web-llvm/docs/api/classes/llvm/openmpirbuilder/#a752e863c1af5fe463d0f08574492c12f">llvm::OpenMPIRBuilder::emitOffloadingArrays</a>, <a href="/web-llvm/docs/api/structs/anonymous-attributorattributes-cpp-/aaallocationinfoimpl/#add9f9de8c94e7adb09555f9b279e8133">anonymous{AttributorAttributes.cpp}::AAAllocationInfoImpl::findInitialAllocationSize</a>, <a href="/web-llvm/docs/api/files/lib/lib/analysis/stacklifetime-cpp/#a29d3972bc8767a75a6956515e5fae76e">findMatchingAlloca</a>, <a href="/web-llvm/docs/api/structs/anonymous-addresssanitizer-cpp-/addresssanitizer/#a8a8741af2dcfc3312679330e1069c734">anonymous{AddressSanitizer.cpp}::AddressSanitizer::getAllocaSizeInBytes</a>, <a href="/web-llvm/docs/api/namespaces/llvm/memtag/#a892fff96fbddc1bc777dd9b3ca02b116">llvm::memtag::getAllocaSizeInBytes</a>, <a href="#a28c9f4622595fd1e231834e260538941">getAllocationSizeInBits</a> and <a href="/web-llvm/docs/api/classes/anonymous-expandvariadics-cpp-/expandvariadics/#a6736ef281ad586fdc1601b22287ae9bc">anonymous{ExpandVariadics.cpp}::ExpandVariadics::sizeOfAlloca</a>.</p>

</div>
</div>

### getAllocationSizeInBits() {#a28c9f4622595fd1e231834e260538941}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">std::optional&lt; TypeSize &gt; AllocaInst::getAllocationSizeInBits (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/datalayout">DataLayout</a> &amp; DL)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Get allocation size in bits.</p>


<p>Returns std::nullopt if size can't be determined, e.g. in case of a VLA.</p>


<p>Declaration at line 114 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/ir/instructions-h">Instructions.h</a>, definition at line 81 of file <a href="/web-llvm/docs/api/files/lib/lib/ir/instructions-cpp">Instructions.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/namespaces/llvm/#a55fc80e21802a32962e170b06a030e27">llvm::checkedMulUnsigned</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/arm/armslshardening-cpp/#ad467c4ab9119043f9b7750ab986be61a">DL</a>, <a href="/web-llvm/docs/api/classes/llvm/typesize/#a69da807c524d5328d606604a92dd53af">llvm::TypeSize::get</a>, <a href="#ad92f6c67d55ced3de1569ee791c38679">getAllocationSize</a> and <a href="/web-llvm/docs/api/files/lib/lib/analysis/inlineorder-cpp/#a7ee6f0cb51c3b9056199e9a0001fe8c3a6f6cb72d544962fa333e2e34ce64f719">Size</a>.</p>

</div>
</div>

### getArraySize() {#af4283a4cef4e2b88f565d827d5857e14}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">const Value * llvm::AllocaInst::getArraySize ()</td>
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

<p>Get the number of elements allocated.</p>


<p>For a simple allocation of a single element, this will return a constant 1 value.</p>


<p>Definition at line 95 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/ir/instructions-h">Instructions.h</a>.</p>


<p>Reference <a href="/web-llvm/docs/api/classes/llvm/user/#aa0a2cb1582d1cec317bd205085469ca1">llvm::User::getOperand</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/classes/anonymous-coroframe-cpp-/frametypebuilder/#a0644a32bfd97560ac89c5d6e9b0bf7ac">anonymous{CoroFrame.cpp}::FrameTypeBuilder::addFieldForAlloca</a>, <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/utils/inlinefunction-cpp/#ad19c97a069133d179234826fc95c3bde">allocaWouldBeStaticInEntry</a>, <a href="#ad92f6c67d55ced3de1569ee791c38679">getAllocationSize</a>, <a href="/web-llvm/docs/api/namespaces/anonymous-stacksafetyanalysis-cpp-/#a9cd19dcbd2a7e975097b8bd795ac1a98">anonymous{StackSafetyAnalysis.cpp}::getStaticAllocaSizeRange</a>, <a href="/web-llvm/docs/api/structs/anonymous-addresssanitizer-cpp-/functionstackpoisoner/#a2c1978d516a0154dd7f006e502ab4cfa">anonymous{AddressSanitizer.cpp}::FunctionStackPoisoner::handleDynamicAllocaCall</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#ab5a3ac0a249da0743dac1bd816d8e5d5">llvm::InlineFunction</a>, <a href="#a36e31f42170be95fc392dad696d9ba19">isStaticAlloca</a>, <a href="/web-llvm/docs/api/files/lib/lib/frontend/lib/frontend/openmp/ompirbuilder-cpp/#a6e4c46869d9d198562f7b8628814e407">raiseUserConstantDataAllocasToEntryBlock</a>, <a href="/web-llvm/docs/api/classes/anonymous-nvptxallocahoisting-cpp-/nvptxallocahoisting/#a3e0401219219142d6d4aa7cb0859afc7">anonymous{NVPTXAllocaHoisting.cpp}::NVPTXAllocaHoisting::runOnFunction</a>, <a href="/web-llvm/docs/api/classes/anonymous-hwaddresssanitizer-cpp-/hwaddresssanitizer/#abe3ea5f5ad2a17b7552318e8ffb3b0bb">anonymous{HWAddressSanitizer.cpp}::HWAddressSanitizer::sanitizeFunction</a>, <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/instcombine/instcombineloadstorealloca-cpp/#a25ea6e038ccdef52ab01b0ee3da9ee52">simplifyAllocaArraySize</a> and <a href="/web-llvm/docs/api/classes/llvm/instcombinerimpl/#af99540103c8717d41b490fc2a1acad5c">llvm::InstCombinerImpl::visitAllocaInst</a>.</p>

</div>
</div>

### getArraySize() {#ab8ea7e026b4ffc33dac82b184aee34ce}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">Value * llvm::AllocaInst::getArraySize ()</td>
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



<p>Definition at line 96 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/ir/instructions-h">Instructions.h</a>.</p>


<p>Reference <a href="/web-llvm/docs/api/classes/llvm/user/#aa0a2cb1582d1cec317bd205085469ca1">llvm::User::getOperand</a>.</p>

</div>
</div>

### getType() {#a5d19f3955a23e8eb2a974efcc8fb19da}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">PointerType * llvm::AllocaInst::getType ()</td>
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

<p>Overload to return most specific pointer type.</p>

<p>Definition at line 99 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/ir/instructions-h">Instructions.h</a>.</p>


<p>References <a href="/web-llvm/docs/api/namespaces/llvm/#ac4fc845f5ed92de63cd4474f128f5fc5">llvm::cast</a> and <a href="/web-llvm/docs/api/classes/llvm/value/#a0344a49526443edf90cc0aef3abd3337">llvm::Value::getType</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/classes/llvm/openmpirbuilder/#a752e863c1af5fe463d0f08574492c12f">llvm::OpenMPIRBuilder::emitOffloadingArrays</a>, <a href="/web-llvm/docs/api/classes/anonymous-aarch64fastisel-cpp-/aarch64fastisel/#a39e2fe24f8016760f80ca14ba3476ebc">anonymous{AArch64FastISel.cpp}::AArch64FastISel::fastMaterializeAlloca</a>, <a href="/web-llvm/docs/api/classes/anonymous-mipsfastisel-cpp-/mipsfastisel/#aaf94fccaa261871e44881773bcdc5ee7">anonymous{MipsFastISel.cpp}::MipsFastISel::fastMaterializeAlloca</a>, <a href="#ad2fb148dfac3182fce33be95fc4e9159">getAddressSpace</a>, <a href="/web-llvm/docs/api/namespaces/anonymous-stacksafetyanalysis-cpp-/#a9cd19dcbd2a7e975097b8bd795ac1a98">anonymous{StackSafetyAnalysis.cpp}::getStaticAllocaSizeRange</a>, <a href="/web-llvm/docs/api/structs/anonymous-addresssanitizer-cpp-/functionstackpoisoner/#a2c1978d516a0154dd7f006e502ab4cfa">anonymous{AddressSanitizer.cpp}::FunctionStackPoisoner::handleDynamicAllocaCall</a>, <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/utils/inlinefunction-cpp/#afaa78d0b3224d3175937f997dc2bc688">hasLifetimeMarkers</a>, <a href="/web-llvm/docs/api/structs/anonymous-addresssanitizer-cpp-/functionstackpoisoner/#a914ea1510476a800508ae70d159bd8c0">anonymous{AddressSanitizer.cpp}::FunctionStackPoisoner::processStaticAllocas</a> and <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/instcombine/instcombineloadstorealloca-cpp/#a25ea6e038ccdef52ab01b0ee3da9ee52">simplifyAllocaArraySize</a>.</p>

</div>
</div>

### isArrayAllocation() {#aea74164514e7164813ab30bcc4b7c557}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool AllocaInst::isArrayAllocation ()</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Return true if there is an allocation size parameter to the allocation instruction that is not 1.</p>

<p>Declaration at line 91 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/ir/instructions-h">Instructions.h</a>, definition at line 1225 of file <a href="/web-llvm/docs/api/files/lib/lib/ir/instructions-cpp">Instructions.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/namespaces/llvm/#a22eeee01734061ac1b31ccd994c49eef">llvm::dyn_cast</a> and <a href="/web-llvm/docs/api/classes/llvm/user/#aa0a2cb1582d1cec317bd205085469ca1">llvm::User::getOperand</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/classes/anonymous-coroframe-cpp-/frametypebuilder/#a0644a32bfd97560ac89c5d6e9b0bf7ac">anonymous{CoroFrame.cpp}::FrameTypeBuilder::addFieldForAlloca</a>, <a href="#ad92f6c67d55ced3de1569ee791c38679">getAllocationSize</a>, <a href="/web-llvm/docs/api/namespaces/anonymous-stacksafetyanalysis-cpp-/#a9cd19dcbd2a7e975097b8bd795ac1a98">anonymous{StackSafetyAnalysis.cpp}::getStaticAllocaSizeRange</a>, <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/coroutines/coroframe-cpp/#af0885df5b78cc732639a9d52a87d040e">insertSpills</a>, <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/utils/local-cpp/#a7e06c0b653fcb0e20fbec6bee3d3d40d">isArray</a>, <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/instcombine/instcombineloadstorealloca-cpp/#a9981d75cde69ea5ca9706536fa4bbab5">isDereferenceableForAllocaSize</a>, <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/instcombine/instcombineloadstorealloca-cpp/#a25ea6e038ccdef52ab01b0ee3da9ee52">simplifyAllocaArraySize</a> and <a href="/web-llvm/docs/api/classes/llvm/instcombinerimpl/#af99540103c8717d41b490fc2a1acad5c">llvm::InstCombinerImpl::visitAllocaInst</a>.</p>

</div>
</div>

### isStaticAlloca() {#a36e31f42170be95fc392dad696d9ba19}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool AllocaInst::isStaticAlloca ()</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Return true if this alloca is in the entry block of the function and is a constant size.</p>


<p>isStaticAlloca - Return true if this alloca is in the entry block of the function and is a constant size.</p>


<p>If so, the code generator will fold it into the prolog/epilog code, so it is basically free.</p>


<p>Declaration at line 135 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/ir/instructions-h">Instructions.h</a>, definition at line 1234 of file <a href="/web-llvm/docs/api/files/lib/lib/ir/instructions-cpp">Instructions.cpp</a>.</p>


<p>References <a href="#af4283a4cef4e2b88f565d827d5857e14">getArraySize</a>, <a href="/web-llvm/docs/api/classes/llvm/ilist-detail/node-parent-access/#a7e19e7508415378ad9523e0339b23e22">llvm::ilist_detail::node_parent_access&lt; ilist_node_impl&lt; ilist_detail::compute_node_options&lt; Instruction, Options... &gt;::type &gt;, ilist_detail::compute_node_options&lt; Instruction, Options... &gt;::type::parent_ty &gt;::getParent</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a92ca992e52dddc420f4b069cae06dfbe">llvm::isa</a> and <a href="#a9bb98c4ac4cf77f5782e5e41f2c6f38a">isUsedWithInAlloca</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/structs/anonymous-addresssanitizer-cpp-/functionstackpoisoner/#a98d7c2e28dffebb3542fd7c608e6b4cc">anonymous{AddressSanitizer.cpp}::FunctionStackPoisoner::createAllocaForLayout</a>, <a href="/web-llvm/docs/api/classes/llvm/memtag/stackinfobuilder/#adcaea10733b9350e0f00307e44ef2b0b">llvm::memtag::StackInfoBuilder::getAllocaInterestingness</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/amdgputargettransforminfo-cpp/#aa883d40ffa8836538699a7974632d0a0">getCallArgsTotalAllocaSize</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/amdgpulowerkernelarguments-cpp/#a7f5d9eaa8cd08c1bbf22faaa2dea67f4">getInsertPt</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/amdgpupromotekernelarguments-cpp/#a7f5d9eaa8cd08c1bbf22faaa2dea67f4">getInsertPt</a>, <a href="/web-llvm/docs/api/classes/llvm/amdgputtiimpl/#a99fc6c25163b324f8642658b54e77687">llvm::AMDGPUTTIImpl::getUnrollingPreferences</a>, <a href="/web-llvm/docs/api/structs/anonymous-addresssanitizer-cpp-/addresssanitizer/#a3b2938393443d2c8a8e005292eed060f">anonymous{AddressSanitizer.cpp}::AddressSanitizer::isInterestingAlloca</a>, <a href="/web-llvm/docs/api/structs/anonymous-addresssanitizer-cpp-/addresssanitizer/#a5f0e568588160e095493dcfc7b5a010e">anonymous{AddressSanitizer.cpp}::AddressSanitizer::markEscapedLocalAllocas</a>, <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/scalar/sroa-cpp/#a0346c3f86c714b9ae84f5566a95e90ac">migrateDebugInfo</a>, <a href="/web-llvm/docs/api/structs/anonymous-addresssanitizer-cpp-/functionstackpoisoner/#a2d3b181e57e15921dd726d62c5f68a5c">anonymous{AddressSanitizer.cpp}::FunctionStackPoisoner::visitAllocaInst</a> and <a href="/web-llvm/docs/api/structs/anonymous-addresssanitizer-cpp-/functionstackpoisoner/#a307e0ed6d4058b4486ae85bbc1908015">anonymous{AddressSanitizer.cpp}::FunctionStackPoisoner::visitIntrinsicInst</a>.</p>

</div>
</div>

### isSwiftError() {#a3016b467a9ecb5506956f7d029509db5}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool llvm::AllocaInst::isSwiftError ()</td>
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

<p>Return true if this alloca is used as a swifterror argument to a call.</p>

<p>Definition at line 149 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/ir/instructions-h">Instructions.h</a>.</p>


<p>Reference <a href="/web-llvm/docs/api/classes/llvm/instruction/#a041694a1ea45996587ef9712d9a2bb1f">llvm::Instruction::getSubclassData</a>.</p>


<p>Referenced by <a href="#a6a2dc8251ccd285b55edc3019e3a42bd">cloneImpl</a>, <a href="/web-llvm/docs/api/classes/llvm/memtag/stackinfobuilder/#adcaea10733b9350e0f00307e44ef2b0b">llvm::memtag::StackInfoBuilder::getAllocaInterestingness</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#ab5a3ac0a249da0743dac1bd816d8e5d5">llvm::InlineFunction</a>, <a href="/web-llvm/docs/api/structs/anonymous-addresssanitizer-cpp-/addresssanitizer/#a3b2938393443d2c8a8e005292eed060f">anonymous{AddressSanitizer.cpp}::AddressSanitizer::isInterestingAlloca</a> and <a href="/web-llvm/docs/api/files/lib/lib/codegen/lib/codegen/globalisel/irtranslator-cpp/#afa1c2daf329c473f004759910b99ac1d">isSwiftError</a>.</p>

</div>
</div>

### isUsedWithInAlloca() {#a9bb98c4ac4cf77f5782e5e41f2c6f38a}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool llvm::AllocaInst::isUsedWithInAlloca ()</td>
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

<p>Return true if this alloca is used as an inalloca argument to a call.</p>


<p>Such allocas are never considered static even if they are in the entry block.</p>


<p>Definition at line 139 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/ir/instructions-h">Instructions.h</a>.</p>


<p>Reference <a href="/web-llvm/docs/api/classes/llvm/instruction/#a041694a1ea45996587ef9712d9a2bb1f">llvm::Instruction::getSubclassData</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/utils/inlinefunction-cpp/#ad19c97a069133d179234826fc95c3bde">allocaWouldBeStaticInEntry</a>, <a href="#a6a2dc8251ccd285b55edc3019e3a42bd">cloneImpl</a>, <a href="/web-llvm/docs/api/classes/llvm/memtag/stackinfobuilder/#adcaea10733b9350e0f00307e44ef2b0b">llvm::memtag::StackInfoBuilder::getAllocaInterestingness</a>, <a href="/web-llvm/docs/api/structs/anonymous-addresssanitizer-cpp-/addresssanitizer/#a3b2938393443d2c8a8e005292eed060f">anonymous{AddressSanitizer.cpp}::AddressSanitizer::isInterestingAlloca</a>, <a href="#a36e31f42170be95fc392dad696d9ba19">isStaticAlloca</a> and <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/instcombine/instcombineloadstorealloca-cpp/#a25ea6e038ccdef52ab01b0ee3da9ee52">simplifyAllocaArraySize</a>.</p>

</div>
</div>

### setAlignment() {#af3bb24b322533dbe8a63c84b18568fe1}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void llvm::AllocaInst::setAlignment (<a href="/web-llvm/docs/api/structs/llvm/align">Align</a> Align)</td>
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



<p>Definition at line 128 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/ir/instructions-h">Instructions.h</a>.</p>


<p>Reference <a href="/web-llvm/docs/api/namespaces/llvm/#ad82de9da62635df78a534de0f16c1129">llvm::Log2</a>.</p>


<p>Referenced by <a href="#a4e9132c0a4e72e51f7310163385d1d98">AllocaInst</a>, <a href="/web-llvm/docs/api/structs/anonymous-addresssanitizer-cpp-/functionstackpoisoner/#acf9b16e74216c278e3362f8e84c16ab0">anonymous{AddressSanitizer.cpp}::FunctionStackPoisoner::copyArgsPassedByValToAllocas</a>, <a href="/web-llvm/docs/api/namespaces/anonymous-nvptxlowerargs-cpp-/#aafd9b42c5de69fbe2a25e6b94f8cc299">anonymous{NVPTXLowerArgs.cpp}::copyByValParam</a>, <a href="/web-llvm/docs/api/structs/anonymous-addresssanitizer-cpp-/functionstackpoisoner/#a98d7c2e28dffebb3542fd7c608e6b4cc">anonymous{AddressSanitizer.cpp}::FunctionStackPoisoner::createAllocaForLayout</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/x86/x86loweramxtype-cpp/#af49d9ef5881a26b9bbbcd2a1002857bb">createAllocaInstAtEntry</a>, <a href="/web-llvm/docs/api/classes/llvm/openmpirbuilder/#a6e2bd6420d3d12339e32d4d1b3ba1394">llvm::OpenMPIRBuilder::createOrderedDepend</a>, <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/ipo/argumentpromotion-cpp/#a48b0c9b087f506b1c0071e7da6054e0f">doPromotion</a>, <a href="/web-llvm/docs/api/classes/llvm/atomicinfo/#a5df935e7c87e3e1dc8b3d7e1870ee1c9">llvm::AtomicInfo::EmitAtomicLoadLibcall</a>, <a href="/web-llvm/docs/api/classes/llvm/openmpirbuilder/#a752e863c1af5fe463d0f08574492c12f">llvm::OpenMPIRBuilder::emitOffloadingArrays</a>, <a href="/web-llvm/docs/api/structs/anonymous-addresssanitizer-cpp-/functionstackpoisoner/#a2c1978d516a0154dd7f006e502ab4cfa">anonymous{AddressSanitizer.cpp}::FunctionStackPoisoner::handleDynamicAllocaCall</a>, <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/coroutines/corosplit-cpp/#ab7881567f602c3a94d11e2817f4464e0">handleNoSuspendCoroutine</a>, <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/coroutines/coroframe-cpp/#a36b39e8a1384a23b9899d2c9e2e08e72">lowerLocalAllocas</a>, <a href="/web-llvm/docs/api/classes/anonymous-dxilflattenarrays-cpp-/dxilflattenarraysvisitor/#a29df0cec2acb067cfcb09eeeb726c7db">anonymous{DXILFlattenArrays.cpp}::DXILFlattenArraysVisitor::visitAllocaInst</a>, <a href="/web-llvm/docs/api/classes/llvm/instcombinerimpl/#af99540103c8717d41b490fc2a1acad5c">llvm::InstCombinerImpl::visitAllocaInst</a> and <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/ipo/globalopt-cpp/#a960e756e8b2f056fbba7baa5bdcfb769">widenDestArray</a>.</p>

</div>
</div>

### setAllocatedType() {#a477cdf70778ab7fa9d5f991413e11eb9}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void llvm::AllocaInst::setAllocatedType (<a href="/web-llvm/docs/api/classes/llvm/type">Type</a> * Ty)</td>
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

<p>for use only in special circumstances that need to generically transform a whole instruction (eg: IR linking and vectorization).</p>

<p>Definition at line 120 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/ir/instructions-h">Instructions.h</a>.</p>

</div>
</div>

### setSwiftError() {#a31eeebeefd320f6a2db4a867f568bee3}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void llvm::AllocaInst::setSwiftError (bool V)</td>
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

<p>Specify whether this alloca is used to represent a swifterror.</p>

<p>Definition at line 151 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/ir/instructions-h">Instructions.h</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/coroutines/corosplit-cpp/#a236935b2df66a03a0a54350a6b9b84bc">replaceSwiftErrorOps</a>.</p>

</div>
</div>

### setUsedWithInAlloca() {#a65c7643f31d548ce5dfe031d52a3f8fa}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void llvm::AllocaInst::setUsedWithInAlloca (bool V)</td>
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

<p>Specify whether this alloca is used to represent the arguments to a call.</p>

<p>Definition at line 144 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/ir/instructions-h">Instructions.h</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Protected Member Functions

### cloneImpl() {#a6a2dc8251ccd285b55edc3019e3a42bd}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">AllocaInst * AllocaInst::cloneImpl ()</td>
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



<p>Declaration at line 77 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/ir/instructions-h">Instructions.h</a>, definition at line 4288 of file <a href="/web-llvm/docs/api/files/lib/lib/ir/instructions-cpp">Instructions.cpp</a>.</p>


<p>References <a href="#afc6f22df80d283b4469f0390d61fd94e">AllocaInst</a>, <a href="#ad2fb148dfac3182fce33be95fc4e9159">getAddressSpace</a>, <a href="#a42438d0a43720a6571c9138224481754">getAlign</a>, <a href="#a9b5ec84ea363eca9e35ddca20a5313af">getAllocatedType</a>, <a href="/web-llvm/docs/api/classes/llvm/user/#aa0a2cb1582d1cec317bd205085469ca1">llvm::User::getOperand</a>, <a href="#a3016b467a9ecb5506956f7d029509db5">isSwiftError</a> and <a href="#a9bb98c4ac4cf77f5782e5e41f2c6f38a">isUsedWithInAlloca</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Private Member Functions

### setSubclassData() {#ad07208eefa2cf2c739c1b10533c70517}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<div class="doxyMemberTemplate">template &lt;typename Bitfield&gt;</div>
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void llvm::AllocaInst::setSubclassData (typename Bitfield::Type Value)</td>
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



<p>Definition at line 165 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/ir/instructions-h">Instructions.h</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Private Member Attributes

### AllocatedType {#a8ef2e1131ec9c41812e4178e93e9fc2c}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">Type* llvm::AllocaInst::AllocatedType</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 64 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/ir/instructions-h">Instructions.h</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Public Static Functions

### classof() {#a4f7392286bffd149ab0e3679e7d1e4fd}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool llvm::AllocaInst::classof (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/instruction">Instruction</a> * I)</td>
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



<p>Definition at line 154 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/ir/instructions-h">Instructions.h</a>.</p>


<p>References <a href="/web-llvm/docs/api/files/lib/lib/support/md5-cpp/#ac0eafdc9ee161b71e7af98af736952fd">I</a> and <a href="#a87273cb892a8182f137567e6b631695e">Instruction</a>.</p>


<p>Referenced by <a href="#a2aeed7ebd03b4b16baaaeb42fe0a1838">classof</a>.</p>

</div>
</div>

### classof() {#a2aeed7ebd03b4b16baaaeb42fe0a1838}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool llvm::AllocaInst::classof (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/value">Value</a> * V)</td>
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



<p>Definition at line 157 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/ir/instructions-h">Instructions.h</a>.</p>


<p>References <a href="/web-llvm/docs/api/namespaces/llvm/#ac4fc845f5ed92de63cd4474f128f5fc5">llvm::cast</a>, <a href="#a4f7392286bffd149ab0e3679e7d1e4fd">classof</a> and <a href="/web-llvm/docs/api/namespaces/llvm/#a92ca992e52dddc420f4b069cae06dfbe">llvm::isa</a>.</p>

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
