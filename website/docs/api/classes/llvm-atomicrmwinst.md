---

# DO NOT EDIT!
# Automatically generated via doxygen2docusaurus by Doxygen.

slug: /api/classes/llvm/atomicrmwinst
custom_edit_url: null
toc_max_heading_level: 4
keywords:
  - doxygen
  - reference
  - class

---

<div class="doxyPage">

# `AtomicRMWInst` Class

<p>an instruction that atomically reads a memory location, combines it with another value, and then stores the result back. <a href="#details">More...</a></p>

## Declaration

<div class="doxyDeclaration">
class llvm::AtomicRMWInst { ... }
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#af16c2ba54e582d7defb6101e4ba347b0">VolatileField</a> = <a href="/web-llvm/docs/api/classes/llvm/instruction/#a5575a4d18b30d5812be34d337378bf01">BoolBitfieldElementT</a>&lt; 0 &gt;</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#afe38a2b5e32581883c13c9943cb9e9d5">AtomicOrderingField</a> = <a href="/web-llvm/docs/api/classes/llvm/instruction/#a1ff5195448fd2558e384c94cb605cbaa">AtomicOrderingBitfieldElementT</a>&lt; VolatileField::NextBit &gt;</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a3ad0a609a9f84c16c5ad92a46dc9c05b">OperationField</a> = BinOpBitfieldElement&lt; AtomicOrderingField::NextBit &gt;</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#af15780fccb14f6eeddfbf40a5d724dd6">AlignmentField</a> = <a href="/web-llvm/docs/api/classes/llvm/instruction/#a04f5e8259cfe79c39de8db8dd73747cb">AlignmentBitfieldElementT</a>&lt; OperationField::NextBit &gt;</td>
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

<tr class="doxyMemberIndexTemplate">
<td class="doxyMemberIndexTemplate" colspan="2"><div>template &lt;unsigned Offset&gt;</div></td>
</tr>
<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemTypeTemplate" align="left" valign="top">using</td>
<td class="doxyMemberIndexItemNameTemplate" align="left" valign="top"><a href="#a96ed33b586bc233392694d2519d3051f">AtomicOrderingBitfieldElement</a> = typename <a href="/web-llvm/docs/api/structs/llvm/bitfield/element">Bitfield::Element</a>&lt; <a href="/web-llvm/docs/api/namespaces/llvm/#a9bccbe67aaab722783ca4e7c504aaaa7">AtomicOrdering</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a05f5b9a11bdcc5feba62899f95dcf878a3134224cba2545bc57954d3b072aebb4">Offset</a>, 3, <a href="/web-llvm/docs/api/namespaces/llvm/#a9bccbe67aaab722783ca4e7c504aaaa7af447f5c03508de4d88e340390ba7c78f">AtomicOrdering::LAST</a> &gt;</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexTemplate">
<td class="doxyMemberIndexTemplate" colspan="2"><div>template &lt;unsigned Offset&gt;</div></td>
</tr>
<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemTypeTemplate" align="left" valign="top">using</td>
<td class="doxyMemberIndexItemNameTemplate" align="left" valign="top"><a href="#a1a33e41f35a44986c487ff5f809f71c9">BinOpBitfieldElement</a> = typename <a href="/web-llvm/docs/api/structs/llvm/bitfield/element">Bitfield::Element</a>&lt; <a href="#a461cfbbb5c7a57ab73210498923cf615">BinOp</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a05f5b9a11bdcc5feba62899f95dcf878a3134224cba2545bc57954d3b072aebb4">Offset</a>, 5, <a href="#a461cfbbb5c7a57ab73210498923cf615a4afdbe301c2ed66ac3752096b8962226">BinOp::LAST_BINOP</a> &gt;</td>
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

## Enumerations Index

<table class="doxyMembersIndex">

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">enum</td>
<td class="doxyMemberIndexItemName" align="left" valign="top">BinOp : unsigned { <a href="#a461cfbbb5c7a57ab73210498923cf615">...</a> }</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>This enumeration lists the possible modifications atomicrmw can make. <a href="#a461cfbbb5c7a57ab73210498923cf615">More...</a></p>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ac70749f79f9e80a53b791daf274fb6a0">AtomicRMWInst</a> (BinOp Operation, Value *Ptr, Value *Val, Align Alignment, AtomicOrdering Ordering, SyncScope::ID SSID, InsertPosition InsertBefore=nullptr)</td>
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

## Public Operators Index

<table class="doxyMembersIndex">

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">void *</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ab8bd9b791cbdcb7d28e958a12049e027">operator new</a> (size_t S)</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#adbc027331eeb5e7f1f96efee0908324c">operator delete</a> (void *Ptr)</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="#a461cfbbb5c7a57ab73210498923cf615">BinOp</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a99fd4ef84981d6a2774c14c741b5ed65">getOperation</a> () const</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a85b3e8d240c7fef7c341a5224f492895">setOperation</a> (BinOp Operation)</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/structs/llvm/align">Align</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a0b5bee42a0652f7f46ec24c924e610d7">getAlign</a> () const</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Return the alignment of the memory that is being allocated by the instruction. <a href="#a0b5bee42a0652f7f46ec24c924e610d7">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">void</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ae3245a9289f9b8fb4e8a9edeb4ed21f7">setAlignment</a> (Align Align)</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a34f1aa991a80c9618af5d4e84aafcb9c">isVolatile</a> () const</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Return true if this is a RMW on a volatile memory location. <a href="#a34f1aa991a80c9618af5d4e84aafcb9c">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">void</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a361ca9304555f6c2e0dd2b3188439b33">setVolatile</a> (bool V)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Specify whether this is a volatile RMW or not. <a href="#a361ca9304555f6c2e0dd2b3188439b33">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a4ec673561070b07b5dfc1d00bd107bcc">DECLARE_TRANSPARENT_OPERAND_ACCESSORS</a> (Value)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Transparently provide more efficient getOperand methods. <a href="#a4ec673561070b07b5dfc1d00bd107bcc">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/namespaces/llvm/#a9bccbe67aaab722783ca4e7c504aaaa7">AtomicOrdering</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#aefa60bfe67b4721c395ce966ac73b439">getOrdering</a> () const</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Returns the ordering constraint of this rmw instruction. <a href="#aefa60bfe67b4721c395ce966ac73b439">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">void</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a5d1f392e4e23933104dbc6f0a5e78497">setOrdering</a> (AtomicOrdering Ordering)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Sets the ordering constraint of this rmw instruction. <a href="#a5d1f392e4e23933104dbc6f0a5e78497">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/namespaces/llvm/syncscope/#a80741d3f96133391b683effd8e5b77f0">SyncScope::ID</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ac97b19e5c8e2843543087d67e47be222">getSyncScopeID</a> () const</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Returns the synchronization scope <a href="/web-llvm/docs/api/namespaces/llvm/callingconv/#abdf8cf606905c10634e831390981b0ed">ID</a> of this rmw instruction. <a href="#ac97b19e5c8e2843543087d67e47be222">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">void</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a47cb069b9a3fdb9dd78d5a5055eb4689">setSyncScopeID</a> (SyncScope::ID SSID)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Sets the synchronization scope <a href="/web-llvm/docs/api/namespaces/llvm/callingconv/#abdf8cf606905c10634e831390981b0ed">ID</a> of this rmw instruction. <a href="#a47cb069b9a3fdb9dd78d5a5055eb4689">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/value">Value</a> *</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a506260aecca4d92e8633628f8d4b83ae">getPointerOperand</a> ()</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/value">Value</a> *</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a814122750c83afb9be6da920367d6f62">getPointerOperand</a> () const</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ae55438e0a802a1a20d6dcabf71b552ad">getValOperand</a> ()</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/value">Value</a> *</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ab0f672c61169f876c4f21615cf856a55">getValOperand</a> () const</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#af39e1cad69b6406376c47e4b111228dc">getPointerAddressSpace</a> () const</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Returns the address space of the pointer operand. <a href="#af39e1cad69b6406376c47e4b111228dc">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">bool</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a667d327df48643f4d2111a0065b192f2">isFloatingPointOperation</a> () const</td>
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

## Protected Member Functions Index

<table class="doxyMembersIndex">

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/atomicrmwinst">AtomicRMWInst</a> *</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a25a1f4bf68a202e553b2f4e227fb5eea">cloneImpl</a> () const</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a4873836d567d176e4cf143ec4d6fd6ca">Init</a> (BinOp Operation, Value *Ptr, Value *Val, Align Align, AtomicOrdering Ordering, SyncScope::ID SSID)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexTemplate">
<td class="doxyMemberIndexTemplate" colspan="2"><div>template &lt;typename Bitfield&gt;</div></td>
</tr>
<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemTypeTemplate" align="left" valign="top">void</td>
<td class="doxyMemberIndexItemNameTemplate" align="left" valign="top"><a href="#a8a2f744b34043496091bc0bb45c52a8a">setSubclassData</a> (typename Bitfield::Type Value)</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/namespaces/llvm/syncscope/#a80741d3f96133391b683effd8e5b77f0">SyncScope::ID</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#abd37edff365a11a8942c156a26746dc0">SSID</a></td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>The synchronization scope <a href="/web-llvm/docs/api/namespaces/llvm/callingconv/#abdf8cf606905c10634e831390981b0ed">ID</a> of this rmw instruction. <a href="#abd37edff365a11a8942c156a26746dc0">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

</table>

## Public Static Functions Index

<table class="doxyMembersIndex">

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">static <a href="/web-llvm/docs/api/classes/llvm/stringref">StringRef</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ae8a61b9349a5ea2fb1b3d856bd4e9ab2">getOperationName</a> (BinOp Op)</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a1bf3744f15082a41d139af3d01e9644d">isFPOperation</a> (BinOp Op)</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a2f8f88574a509cf4545cd6420b405aaf">getPointerOperandIndex</a> ()</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a6856195e004f0312d81613d253c144aa">classof</a> (const Instruction *I)</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a892c67a0c6eec011b6c22be9733ecf95">classof</a> (const Value *V)</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">static constexpr <a href="/web-llvm/docs/api/structs/llvm/user/intrusiveoperandsallocmarker">IntrusiveOperandsAllocMarker</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a9b48f20421056e857255f7ceaf7c2538">AllocMarker</a> {2}</td>
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

<p>an instruction that atomically reads a memory location, combines it with another value, and then stores the result back.</p>


<p>Returns the old value.</p>


<p>Definition at line 704 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/ir/instructions-h">Instructions.h</a>.</p>


<div class="doxySectionDef">

## Public Member Typedefs

### AlignmentField {#af15780fccb14f6eeddfbf40a5d724dd6}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">using llvm::AtomicRMWInst::AlignmentField =  AlignmentBitfieldElementT&lt;OperationField::NextBit&gt;</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 800 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/ir/instructions-h">Instructions.h</a>.</p>

</div>
</div>

### AtomicOrderingField {#afe38a2b5e32581883c13c9943cb9e9d5}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">using llvm::AtomicRMWInst::AtomicOrderingField = 
      AtomicOrderingBitfieldElementT&lt;VolatileField::NextBit&gt;</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 797 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/ir/instructions-h">Instructions.h</a>.</p>

</div>
</div>

### OperationField {#a3ad0a609a9f84c16c5ad92a46dc9c05b}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">using llvm::AtomicRMWInst::OperationField =  BinOpBitfieldElement&lt;AtomicOrderingField::NextBit&gt;</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 799 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/ir/instructions-h">Instructions.h</a>.</p>

</div>
</div>

### VolatileField {#af16c2ba54e582d7defb6101e4ba347b0}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">using llvm::AtomicRMWInst::VolatileField =  BoolBitfieldElementT&lt;0&gt;</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 796 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/ir/instructions-h">Instructions.h</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Private Member Typedefs

### AtomicOrderingBitfieldElement {#a96ed33b586bc233392694d2519d3051f}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<div class="doxyMemberTemplate">template &lt;unsigned Offset&gt;</div>
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">using llvm::AtomicRMWInst::AtomicOrderingBitfieldElement = 
      typename Bitfield::Element&lt;AtomicOrdering, Offset, 3,
                                 AtomicOrdering::LAST&gt;</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 777 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/ir/instructions-h">Instructions.h</a>.</p>

</div>
</div>

### BinOpBitfieldElement {#a1a33e41f35a44986c487ff5f809f71c9}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<div class="doxyMemberTemplate">template &lt;unsigned Offset&gt;</div>
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">using llvm::AtomicRMWInst::BinOpBitfieldElement = 
      typename Bitfield::Element&lt;BinOp, Offset, 5, BinOp::LAST_BINOP&gt;</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 782 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/ir/instructions-h">Instructions.h</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Enumerations

### BinOp {#a461cfbbb5c7a57ab73210498923cf615}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">enum llvm::AtomicRMWInst::BinOp : unsigned</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>This enumeration lists the possible modifications atomicrmw can make.</p>

<dl class="doxyEnumList">
<dt class="doxyEnumTableTitle">Enumeration values</dt>
<dd>
<table class="doxyEnumTable">

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">Xchg<a id="a461cfbbb5c7a57ab73210498923cf615afc870a548088c5b7a93a34f648889d77"></a></td>
<td class="doxyEnumItemDescription">*p = v</td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">Add<a id="a461cfbbb5c7a57ab73210498923cf615a0794c42b44989f9d9f1454d79ca0dd88"></a></td>
<td class="doxyEnumItemDescription">*p = old + v</td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">Sub<a id="a461cfbbb5c7a57ab73210498923cf615a5db6ca0c3e18acd87290f22ccb2ce564"></a></td>
<td class="doxyEnumItemDescription">*p = old - v</td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">And<a id="a461cfbbb5c7a57ab73210498923cf615a660a31179bfecd737a256372e5fd6122"></a></td>
<td class="doxyEnumItemDescription">*p = old &amp; v</td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">Nand<a id="a461cfbbb5c7a57ab73210498923cf615afdcdc631cf4fa6829fd7499cd06a306b"></a></td>
<td class="doxyEnumItemDescription">*p = ~(old &amp; v)</td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">Or<a id="a461cfbbb5c7a57ab73210498923cf615a5954f59053121b87ebe0c5fe79942c6e"></a></td>
<td class="doxyEnumItemDescription">*p = old | v</td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">Xor<a id="a461cfbbb5c7a57ab73210498923cf615a71aab8ee954b6d71a4eed315e8f6556e"></a></td>
<td class="doxyEnumItemDescription">*p = old ^ v</td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">Max<a id="a461cfbbb5c7a57ab73210498923cf615aa1184a7e35e94d162a2d40f2b11beeb2"></a></td>
<td class="doxyEnumItemDescription">*p = old &gt;signed v ? old : v</td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">Min<a id="a461cfbbb5c7a57ab73210498923cf615a39edb6e51c1ad37244e8b32a2af4077d"></a></td>
<td class="doxyEnumItemDescription">*p = old &lt;signed v ? old : v</td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">UMax<a id="a461cfbbb5c7a57ab73210498923cf615abe171d96ba8de66fb30e08c00211591e"></a></td>
<td class="doxyEnumItemDescription">*p = old &gt;unsigned v ? old : v</td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">UMin<a id="a461cfbbb5c7a57ab73210498923cf615aa53854e09143f57d2ff2ad6ac89dc55d"></a></td>
<td class="doxyEnumItemDescription">*p = old &lt;unsigned v ? old : v</td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">FAdd<a id="a461cfbbb5c7a57ab73210498923cf615a08ef06068dcd583c2476568dda59b324"></a></td>
<td class="doxyEnumItemDescription">*p = old + v</td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">FSub<a id="a461cfbbb5c7a57ab73210498923cf615a92f66d4bc04fc8514bee80509f3e78d4"></a></td>
<td class="doxyEnumItemDescription">*p = old - v</td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">FMax<a id="a461cfbbb5c7a57ab73210498923cf615acce124326ba87b0127b36c412bf555fd"></a></td>
<td class="doxyEnumItemDescription">*p = maxnum(old, v) <span class="doxyComputerOutput">maxnum</span> matches the behavior of <span class="doxyComputerOutput"><a href="/web-llvm/docs/api/namespaces/llvm/#a636de400e4dd2bc090b729329a99e75b">llvm.maxnum</a></span></td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">FMin<a id="a461cfbbb5c7a57ab73210498923cf615abd5e733a10a36f3572105b1a67538e18"></a></td>
<td class="doxyEnumItemDescription">*p = minnum(old, v) <span class="doxyComputerOutput">minnum</span> matches the behavior of <span class="doxyComputerOutput"><a href="/web-llvm/docs/api/namespaces/llvm/#aa656aa475d13ec6a900414eadabe86b0">llvm.minnum</a></span></td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">UIncWrap<a id="a461cfbbb5c7a57ab73210498923cf615a9334c9815ddc2b25804c6c03b68cc39b"></a></td>
<td class="doxyEnumItemDescription">Increment one up to a maximum value</td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">UDecWrap<a id="a461cfbbb5c7a57ab73210498923cf615ad3ed1a8c334bc3a50d59aaa57ee9e9f3"></a></td>
<td class="doxyEnumItemDescription">Decrement one until a minimum value or zero</td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">USubCond<a id="a461cfbbb5c7a57ab73210498923cf615a0f94e2ef083268e45d22a220f92567a4"></a></td>
<td class="doxyEnumItemDescription">Subtract only if no unsigned overflow</td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">USubSat<a id="a461cfbbb5c7a57ab73210498923cf615a7bf1abb23eccced685c706917aff605c"></a></td>
<td class="doxyEnumItemDescription">*p = usub.sat(old, v) <span class="doxyComputerOutput">usub.sat</span> matches the behavior of <span class="doxyComputerOutput">llvm.usub.sat</span></td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">FIRST_BINOP<a id="a461cfbbb5c7a57ab73210498923cf615ad76dfbda6c10d959f44e01788b4c0f66"></a></td>
<td class="doxyEnumItemDescription"> (= Xchg)</td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">LAST_BINOP<a id="a461cfbbb5c7a57ab73210498923cf615a4afdbe301c2ed66ac3752096b8962226"></a></td>
<td class="doxyEnumItemDescription"> (= USubSat)</td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">BAD_BINOP<a id="a461cfbbb5c7a57ab73210498923cf615a497e8f347648b1b2823ee0338c95f65f"></a></td>
<td class="doxyEnumItemDescription"></td>
</tr>

</table>
</dd>
</dl>


<p>In the descriptions, 'p' is the pointer to the instruction's memory location, 'old' is the initial value of *p, and 'v' is the other value passed to the instruction. These instructions always return 'old'.</p>


<p>Definition at line 716 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/ir/instructions-h">Instructions.h</a>.</p>

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


<p>Definition at line 707 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/ir/instructions-h">Instructions.h</a>.</p>


<p>References <a href="#ac70749f79f9e80a53b791daf274fb6a0">AtomicRMWInst</a>, <a href="#a25a1f4bf68a202e553b2f4e227fb5eea">cloneImpl</a> and <a href="#a87273cb892a8182f137567e6b631695e">Instruction</a>.</p>


<p>Referenced by <a href="#ac70749f79f9e80a53b791daf274fb6a0">AtomicRMWInst</a>, <a href="#a6856195e004f0312d81613d253c144aa">classof</a> and <a href="#a87273cb892a8182f137567e6b631695e">Instruction</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Public Constructors

### AtomicRMWInst() {#ac70749f79f9e80a53b791daf274fb6a0}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">AtomicRMWInst::AtomicRMWInst (<a href="#a461cfbbb5c7a57ab73210498923cf615">BinOp</a> Operation, <a href="/web-llvm/docs/api/classes/llvm/value">Value</a> * Ptr, <a href="/web-llvm/docs/api/classes/llvm/value">Value</a> * Val, <a href="/web-llvm/docs/api/structs/llvm/align">Align</a> Alignment, <a href="/web-llvm/docs/api/namespaces/llvm/#a9bccbe67aaab722783ca4e7c504aaaa7">AtomicOrdering</a> Ordering, <a href="/web-llvm/docs/api/namespaces/llvm/syncscope/#a80741d3f96133391b683effd8e5b77f0">SyncScope::ID</a> SSID, <a href="/web-llvm/docs/api/classes/llvm/insertposition">InsertPosition</a> InsertBefore=nullptr)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Declaration at line 788 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/ir/instructions-h">Instructions.h</a>, definition at line 1385 of file <a href="/web-llvm/docs/api/files/lib/lib/ir/instructions-cpp">Instructions.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/classes/llvm/value/#a0344a49526443edf90cc0aef3abd3337">llvm::Value::getType</a>, <a href="#a87273cb892a8182f137567e6b631695e">Instruction</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/powerpc/ppcreducecrlogicals-cpp/#a5b2aa9d3f9f3a7b2d123fef7c5328b8f">Operation</a> and <a href="/web-llvm/docs/api/files/lib/lib/analysis/targetlibraryinfo-cpp/#aca185e6d0e9f423dbb24440206454872a11dbf501abf829b3ab7049c2d3a8a053">Ptr</a>.</p>


<p>Referenced by <a href="#a25a1f4bf68a202e553b2f4e227fb5eea">cloneImpl</a> and <a href="#a87273cb892a8182f137567e6b631695e">Instruction</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Public Operators

### operator delete() {#adbc027331eeb5e7f1f96efee0908324c}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void llvm::AtomicRMWInst::operator delete (void * Ptr)</td>
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



<p>Definition at line 794 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/ir/instructions-h">Instructions.h</a>.</p>


<p>Reference <a href="/web-llvm/docs/api/files/lib/lib/analysis/targetlibraryinfo-cpp/#aca185e6d0e9f423dbb24440206454872a11dbf501abf829b3ab7049c2d3a8a053">Ptr</a>.</p>

</div>
</div>

### operator new() {#ab8bd9b791cbdcb7d28e958a12049e027}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void * llvm::AtomicRMWInst::operator new (size_t S)</td>
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



<p>Definition at line 793 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/ir/instructions-h">Instructions.h</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Public Member Functions

### DECLARE\_TRANSPARENT\_OPERAND\_ACCESSORS() {#a4ec673561070b07b5dfc1d00bd107bcc}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">llvm::AtomicRMWInst::DECLARE_TRANSPARENT_OPERAND_ACCESSORS (<a href="/web-llvm/docs/api/classes/llvm/value">Value</a>)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Transparently provide more efficient getOperand methods.</p>

<p>Definition at line 844 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/ir/instructions-h">Instructions.h</a>.</p>

</div>
</div>

### getAlign() {#a0b5bee42a0652f7f46ec24c924e610d7}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">Align llvm::AtomicRMWInst::getAlign ()</td>
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

<p>Definition at line 827 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/ir/instructions-h">Instructions.h</a>.</p>


<p>Reference <a href="/web-llvm/docs/api/classes/llvm/instruction/#a041694a1ea45996587ef9712d9a2bb1f">llvm::Instruction::getSubclassData</a>.</p>


<p>Referenced by <a href="#a25a1f4bf68a202e553b2f4e227fb5eea">cloneImpl</a>, <a href="/web-llvm/docs/api/classes/llvm/loongarchtargetlowering/#a6afb7e7298c87508bd965772db54ec19">llvm::LoongArchTargetLowering::emitMaskedAtomicRMWIntrinsic</a>, <a href="/web-llvm/docs/api/classes/llvm/riscvtargetlowering/#a241b3032c605e4faafb173c3adf15105">llvm::RISCVTargetLowering::emitMaskedAtomicRMWIntrinsic</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#aa59c4ae8c95bb222039942e9ba995c3e">llvm::expandAtomicRMWToCmpXchg</a>, <a href="/web-llvm/docs/api/classes/llvm/sitargetlowering/#a818d0dbc281d144e0f02a0a75c7af1ee">llvm::SITargetLowering::lowerIdempotentRMWIntoFencedLoad</a> and <a href="/web-llvm/docs/api/classes/anonymous-amdgpulowerbufferfatpointers-cpp-/splitptrstructs/#af2a279d40332c538cc1a05dc6b7981e8">anonymous{AMDGPULowerBufferFatPointers.cpp}::SplitPtrStructs::visitAtomicRMWInst</a>.</p>

</div>
</div>

### getOperation() {#a99fd4ef84981d6a2774c14c741b5ed65}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">BinOp llvm::AtomicRMWInst::getOperation ()</td>
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



<p>Definition at line 805 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/ir/instructions-h">Instructions.h</a>.</p>


<p>Reference <a href="/web-llvm/docs/api/classes/llvm/instruction/#a041694a1ea45996587ef9712d9a2bb1f">llvm::Instruction::getSubclassData</a>.</p>


<p>Referenced by <a href="#a25a1f4bf68a202e553b2f4e227fb5eea">cloneImpl</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/siisellowering-cpp/#a70c624e7362eb836118fe7ee02737b43">emitAtomicRMWLegalRemark</a>, <a href="/web-llvm/docs/api/classes/llvm/loongarchtargetlowering/#ad3d0b842e1c779edc912cf2863bd5fcd">llvm::LoongArchTargetLowering::emitExpandAtomicRMW</a>, <a href="/web-llvm/docs/api/classes/llvm/sitargetlowering/#ab4fd10263a383f485f869614143490be">llvm::SITargetLowering::emitExpandAtomicRMW</a>, <a href="/web-llvm/docs/api/classes/llvm/loongarchtargetlowering/#a6afb7e7298c87508bd965772db54ec19">llvm::LoongArchTargetLowering::emitMaskedAtomicRMWIntrinsic</a>, <a href="/web-llvm/docs/api/classes/llvm/ppctargetlowering/#a0e0d3c023e19c20fbf01b40d36aced80">llvm::PPCTargetLowering::emitMaskedAtomicRMWIntrinsic</a>, <a href="/web-llvm/docs/api/classes/llvm/riscvtargetlowering/#a241b3032c605e4faafb173c3adf15105">llvm::RISCVTargetLowering::emitMaskedAtomicRMWIntrinsic</a>, <a href="#a667d327df48643f4d2111a0065b192f2">isFloatingPointOperation</a>, <a href="/web-llvm/docs/api/namespaces/anonymous-instcombineatomicrmw-cpp-/#aa285536df532aacbbbac1e2ce635e782">anonymous{InstCombineAtomicRMW.cpp}::isIdempotentRMW</a>, <a href="/web-llvm/docs/api/namespaces/anonymous-instcombineatomicrmw-cpp-/#abf26bb40d8d6d203e6cfa2339cbaca8c">anonymous{InstCombineAtomicRMW.cpp}::isSaturating</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#ac963dddf8453fc717992d3ce36a27d8b">llvm::lowerAtomicRMWInst</a>, <a href="/web-llvm/docs/api/classes/llvm/targetloweringbase/#a93fa81ce3759c975472e23d85d14bec1">llvm::TargetLoweringBase::shouldCastAtomicRMWIInIR</a>, <a href="/web-llvm/docs/api/classes/llvm/aarch64targetlowering/#a7c188b2e9f8e7ab4da2a49c83acd299c">llvm::AArch64TargetLowering::shouldExpandAtomicRMWInIR</a>, <a href="/web-llvm/docs/api/classes/llvm/loongarchtargetlowering/#a5916c5a40e28fd6b62ec267bfe57e43d">llvm::LoongArchTargetLowering::shouldExpandAtomicRMWInIR</a>, <a href="/web-llvm/docs/api/classes/llvm/nvptxtargetlowering/#ac4cecb5dac1dff98c076e4ab11e37f93">llvm::NVPTXTargetLowering::shouldExpandAtomicRMWInIR</a>, <a href="/web-llvm/docs/api/classes/llvm/ppctargetlowering/#a5047a95accb91898b9135182491d547c">llvm::PPCTargetLowering::shouldExpandAtomicRMWInIR</a>, <a href="/web-llvm/docs/api/classes/llvm/riscvtargetlowering/#a7a07b54d60a81306d5f8c4f12fe8d0cb">llvm::RISCVTargetLowering::shouldExpandAtomicRMWInIR</a>, <a href="/web-llvm/docs/api/classes/llvm/sitargetlowering/#a874edeab85418837bb65d4d2ec4c5d0b">llvm::SITargetLowering::shouldExpandAtomicRMWInIR</a>, <a href="/web-llvm/docs/api/classes/llvm/sparctargetlowering/#a29137845e271a0520a8f1c3c397faf50">llvm::SparcTargetLowering::shouldExpandAtomicRMWInIR</a>, <a href="/web-llvm/docs/api/classes/llvm/systemztargetlowering/#a8f438755ea4e823390b7d3eef773bbd8">llvm::SystemZTargetLowering::shouldExpandAtomicRMWInIR</a>, <a href="/web-llvm/docs/api/classes/llvm/vetargetlowering/#a6b4bb4b3ed23a97d092a81bc7afa1cef">llvm::VETargetLowering::shouldExpandAtomicRMWInIR</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/x86/x86isellowering-cpp/#a53e9a46c5489f12eb459b3ecce3db181">shouldExpandCmpArithRMWInIR</a> and <a href="/web-llvm/docs/api/classes/llvm/instcombinerimpl/#a3d5d32552609554018891c30a532f1d6">llvm::InstCombinerImpl::visitAtomicRMWInst</a>.</p>

</div>
</div>

### getOrdering() {#aefa60bfe67b4721c395ce966ac73b439}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">AtomicOrdering llvm::AtomicRMWInst::getOrdering ()</td>
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

<p>Returns the ordering constraint of this rmw instruction.</p>

<p>Definition at line 847 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/ir/instructions-h">Instructions.h</a>.</p>


<p>Reference <a href="/web-llvm/docs/api/classes/llvm/instruction/#a041694a1ea45996587ef9712d9a2bb1f">llvm::Instruction::getSubclassData</a>.</p>


<p>Referenced by <a href="#a25a1f4bf68a202e553b2f4e227fb5eea">cloneImpl</a>, <a href="/web-llvm/docs/api/classes/llvm/loongarchtargetlowering/#ad3d0b842e1c779edc912cf2863bd5fcd">llvm::LoongArchTargetLowering::emitExpandAtomicRMW</a>, <a href="/web-llvm/docs/api/classes/llvm/loongarchtargetlowering/#a6afb7e7298c87508bd965772db54ec19">llvm::LoongArchTargetLowering::emitMaskedAtomicRMWIntrinsic</a>, <a href="/web-llvm/docs/api/classes/llvm/riscvtargetlowering/#a241b3032c605e4faafb173c3adf15105">llvm::RISCVTargetLowering::emitMaskedAtomicRMWIntrinsic</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#aa59c4ae8c95bb222039942e9ba995c3e">llvm::expandAtomicRMWToCmpXchg</a>, <a href="/web-llvm/docs/api/classes/llvm/aaresults/#ae1b052f14fb4b833786d84bef32008a8">llvm::AAResults::getModRefInfo</a>, <a href="/web-llvm/docs/api/classes/llvm/instruction/#a3287172f2d13af086e6d66364e8c6de3">llvm::Instruction::getNumSuccessors</a>, <a href="/web-llvm/docs/api/classes/llvm/sitargetlowering/#a818d0dbc281d144e0f02a0a75c7af1ee">llvm::SITargetLowering::lowerIdempotentRMWIntoFencedLoad</a>, <a href="/web-llvm/docs/api/classes/anonymous-amdgpulowerbufferfatpointers-cpp-/splitptrstructs/#af2a279d40332c538cc1a05dc6b7981e8">anonymous{AMDGPULowerBufferFatPointers.cpp}::SplitPtrStructs::visitAtomicRMWInst</a> and <a href="/web-llvm/docs/api/classes/llvm/instcombinerimpl/#a3d5d32552609554018891c30a532f1d6">llvm::InstCombinerImpl::visitAtomicRMWInst</a>.</p>

</div>
</div>

### getPointerAddressSpace() {#af39e1cad69b6406376c47e4b111228dc}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">unsigned llvm::AtomicRMWInst::getPointerAddressSpace ()</td>
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

<p>Definition at line 878 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/ir/instructions-h">Instructions.h</a>.</p>


<p>References <a href="/web-llvm/docs/api/classes/llvm/type/#a5ab2d0b0f0b8ceec3b907184e7567197">llvm::Type::getPointerAddressSpace</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a54b19432f9c7d4df0f2f2307175f73e4">llvm::getPointerOperand</a> and <a href="/web-llvm/docs/api/classes/llvm/value/#a0344a49526443edf90cc0aef3abd3337">llvm::Value::getType</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/classes/llvm/sitargetlowering/#ab4fd10263a383f485f869614143490be">llvm::SITargetLowering::emitExpandAtomicRMW</a> and <a href="/web-llvm/docs/api/classes/llvm/sitargetlowering/#a874edeab85418837bb65d4d2ec4c5d0b">llvm::SITargetLowering::shouldExpandAtomicRMWInIR</a>.</p>

</div>
</div>

### getPointerOperand() {#a506260aecca4d92e8633628f8d4b83ae}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">Value * llvm::AtomicRMWInst::getPointerOperand ()</td>
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



<p>Definition at line 870 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/ir/instructions-h">Instructions.h</a>.</p>


<p>Reference <a href="/web-llvm/docs/api/classes/llvm/user/#aa0a2cb1582d1cec317bd205085469ca1">llvm::User::getOperand</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/classes/llvm/loongarchtargetlowering/#ad3d0b842e1c779edc912cf2863bd5fcd">llvm::LoongArchTargetLowering::emitExpandAtomicRMW</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#aa59c4ae8c95bb222039942e9ba995c3e">llvm::expandAtomicRMWToCmpXchg</a>, <a href="/web-llvm/docs/api/classes/llvm/memorylocation/#a46d61c561714322cb42bd3db9f1609fa">llvm::MemoryLocation::get</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#ac963dddf8453fc717992d3ce36a27d8b">llvm::lowerAtomicRMWInst</a>, <a href="/web-llvm/docs/api/classes/llvm/sitargetlowering/#a818d0dbc281d144e0f02a0a75c7af1ee">llvm::SITargetLowering::lowerIdempotentRMWIntoFencedLoad</a> and <a href="/web-llvm/docs/api/classes/anonymous-amdgpulowerbufferfatpointers-cpp-/splitptrstructs/#af2a279d40332c538cc1a05dc6b7981e8">anonymous{AMDGPULowerBufferFatPointers.cpp}::SplitPtrStructs::visitAtomicRMWInst</a>.</p>

</div>
</div>

### getPointerOperand() {#a814122750c83afb9be6da920367d6f62}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">const Value * llvm::AtomicRMWInst::getPointerOperand ()</td>
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



<p>Definition at line 871 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/ir/instructions-h">Instructions.h</a>.</p>


<p>Reference <a href="/web-llvm/docs/api/classes/llvm/user/#aa0a2cb1582d1cec317bd205085469ca1">llvm::User::getOperand</a>.</p>

</div>
</div>

### getSyncScopeID() {#ac97b19e5c8e2843543087d67e47be222}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">SyncScope::ID llvm::AtomicRMWInst::getSyncScopeID ()</td>
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

<p>Returns the synchronization scope <a href="/web-llvm/docs/api/namespaces/llvm/callingconv/#abdf8cf606905c10634e831390981b0ed">ID</a> of this rmw instruction.</p>

<p>Definition at line 861 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/ir/instructions-h">Instructions.h</a>.</p>


<p>Referenced by <a href="#a25a1f4bf68a202e553b2f4e227fb5eea">cloneImpl</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/siisellowering-cpp/#a70c624e7362eb836118fe7ee02737b43">emitAtomicRMWLegalRemark</a>, <a href="/web-llvm/docs/api/classes/llvm/loongarchtargetlowering/#ad3d0b842e1c779edc912cf2863bd5fcd">llvm::LoongArchTargetLowering::emitExpandAtomicRMW</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#aa59c4ae8c95bb222039942e9ba995c3e">llvm::expandAtomicRMWToCmpXchg</a>, <a href="/web-llvm/docs/api/classes/llvm/sitargetlowering/#a818d0dbc281d144e0f02a0a75c7af1ee">llvm::SITargetLowering::lowerIdempotentRMWIntoFencedLoad</a>, <a href="/web-llvm/docs/api/classes/llvm/sitargetlowering/#a874edeab85418837bb65d4d2ec4c5d0b">llvm::SITargetLowering::shouldExpandAtomicRMWInIR</a> and <a href="/web-llvm/docs/api/classes/anonymous-amdgpulowerbufferfatpointers-cpp-/splitptrstructs/#af2a279d40332c538cc1a05dc6b7981e8">anonymous{AMDGPULowerBufferFatPointers.cpp}::SplitPtrStructs::visitAtomicRMWInst</a>.</p>

</div>
</div>

### getValOperand() {#ae55438e0a802a1a20d6dcabf71b552ad}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">Value * llvm::AtomicRMWInst::getValOperand ()</td>
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



<p>Definition at line 874 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/ir/instructions-h">Instructions.h</a>.</p>


<p>Reference <a href="/web-llvm/docs/api/classes/llvm/user/#aa0a2cb1582d1cec317bd205085469ca1">llvm::User::getOperand</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/classes/llvm/loongarchtargetlowering/#ad3d0b842e1c779edc912cf2863bd5fcd">llvm::LoongArchTargetLowering::emitExpandAtomicRMW</a>, <a href="/web-llvm/docs/api/classes/llvm/sitargetlowering/#ab4fd10263a383f485f869614143490be">llvm::SITargetLowering::emitExpandAtomicRMW</a>, <a href="/web-llvm/docs/api/classes/llvm/loongarchtargetlowering/#a6afb7e7298c87508bd965772db54ec19">llvm::LoongArchTargetLowering::emitMaskedAtomicRMWIntrinsic</a>, <a href="/web-llvm/docs/api/classes/llvm/riscvtargetlowering/#a241b3032c605e4faafb173c3adf15105">llvm::RISCVTargetLowering::emitMaskedAtomicRMWIntrinsic</a>, <a href="/web-llvm/docs/api/classes/llvm/memorylocation/#a46d61c561714322cb42bd3db9f1609fa">llvm::MemoryLocation::get</a>, <a href="/web-llvm/docs/api/files/lib/lib/codegen/atomicexpandpass-cpp/#a48ac978d44f5d426d300a400142708b5">getAtomicOpSize</a>, <a href="/web-llvm/docs/api/namespaces/anonymous-instcombineatomicrmw-cpp-/#aa285536df532aacbbbac1e2ce635e782">anonymous{InstCombineAtomicRMW.cpp}::isIdempotentRMW</a>, <a href="/web-llvm/docs/api/namespaces/anonymous-instcombineatomicrmw-cpp-/#abf26bb40d8d6d203e6cfa2339cbaca8c">anonymous{InstCombineAtomicRMW.cpp}::isSaturating</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#ac963dddf8453fc717992d3ce36a27d8b">llvm::lowerAtomicRMWInst</a>, <a href="/web-llvm/docs/api/classes/llvm/targetloweringbase/#a93fa81ce3759c975472e23d85d14bec1">llvm::TargetLoweringBase::shouldCastAtomicRMWIInIR</a>, <a href="/web-llvm/docs/api/classes/llvm/nvptxtargetlowering/#ac4cecb5dac1dff98c076e4ab11e37f93">llvm::NVPTXTargetLowering::shouldExpandAtomicRMWInIR</a>, <a href="/web-llvm/docs/api/classes/llvm/sitargetlowering/#a874edeab85418837bb65d4d2ec4c5d0b">llvm::SITargetLowering::shouldExpandAtomicRMWInIR</a> and <a href="/web-llvm/docs/api/classes/anonymous-amdgpulowerbufferfatpointers-cpp-/splitptrstructs/#af2a279d40332c538cc1a05dc6b7981e8">anonymous{AMDGPULowerBufferFatPointers.cpp}::SplitPtrStructs::visitAtomicRMWInst</a>.</p>

</div>
</div>

### getValOperand() {#ab0f672c61169f876c4f21615cf856a55}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">const Value * llvm::AtomicRMWInst::getValOperand ()</td>
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



<p>Definition at line 875 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/ir/instructions-h">Instructions.h</a>.</p>


<p>Reference <a href="/web-llvm/docs/api/classes/llvm/user/#aa0a2cb1582d1cec317bd205085469ca1">llvm::User::getOperand</a>.</p>

</div>
</div>

### isFloatingPointOperation() {#a667d327df48643f4d2111a0065b192f2}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool llvm::AtomicRMWInst::isFloatingPointOperation ()</td>
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



<p>Definition at line 882 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/ir/instructions-h">Instructions.h</a>.</p>


<p>References <a href="#a99fd4ef84981d6a2774c14c741b5ed65">getOperation</a> and <a href="#a1bf3744f15082a41d139af3d01e9644d">isFPOperation</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64isellowering-cpp/#a52cff5d33f36f7d74476e993b0118f58">rmwOpMayLowerToLibcall</a>, <a href="/web-llvm/docs/api/classes/llvm/aarch64targetlowering/#a7c188b2e9f8e7ab4da2a49c83acd299c">llvm::AArch64TargetLowering::shouldExpandAtomicRMWInIR</a>, <a href="/web-llvm/docs/api/classes/llvm/armtargetlowering/#a6ed1fafeaecc08fe13e54b080e259dd2">llvm::ARMTargetLowering::shouldExpandAtomicRMWInIR</a>, <a href="/web-llvm/docs/api/classes/llvm/loongarchtargetlowering/#a5916c5a40e28fd6b62ec267bfe57e43d">llvm::LoongArchTargetLowering::shouldExpandAtomicRMWInIR</a>, <a href="/web-llvm/docs/api/classes/llvm/nvptxtargetlowering/#ac4cecb5dac1dff98c076e4ab11e37f93">llvm::NVPTXTargetLowering::shouldExpandAtomicRMWInIR</a>, <a href="/web-llvm/docs/api/classes/llvm/riscvtargetlowering/#a7a07b54d60a81306d5f8c4f12fe8d0cb">llvm::RISCVTargetLowering::shouldExpandAtomicRMWInIR</a>, <a href="/web-llvm/docs/api/classes/llvm/targetloweringbase/#acbe42d1632a205dcd01568e46caee587">llvm::TargetLoweringBase::shouldExpandAtomicRMWInIR</a> and <a href="/web-llvm/docs/api/structs/anonymous-autoupgrade-cpp-/amdgpuunsafefpatomicsupgradevisitor/#aa5a373065be6eabfcc9eeb46018af87c">anonymous{AutoUpgrade.cpp}::AMDGPUUnsafeFPAtomicsUpgradeVisitor::visitAtomicRMWInst</a>.</p>

</div>
</div>

### isVolatile() {#a34f1aa991a80c9618af5d4e84aafcb9c}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool llvm::AtomicRMWInst::isVolatile ()</td>
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

<p>Return true if this is a RMW on a volatile memory location.</p>

<p>Definition at line 837 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/ir/instructions-h">Instructions.h</a>.</p>


<p>Reference <a href="/web-llvm/docs/api/classes/llvm/instruction/#a041694a1ea45996587ef9712d9a2bb1f">llvm::Instruction::getSubclassData</a>.</p>


<p>Referenced by <a href="#a25a1f4bf68a202e553b2f4e227fb5eea">cloneImpl</a>, <a href="/web-llvm/docs/api/classes/llvm/instruction/#a55743bd32282bf6f87aeb49237b1fb68">llvm::Instruction::isCommutative</a>, <a href="/web-llvm/docs/api/classes/anonymous-amdgpulowerbufferfatpointers-cpp-/splitptrstructs/#af2a279d40332c538cc1a05dc6b7981e8">anonymous{AMDGPULowerBufferFatPointers.cpp}::SplitPtrStructs::visitAtomicRMWInst</a> and <a href="/web-llvm/docs/api/classes/llvm/instcombinerimpl/#a3d5d32552609554018891c30a532f1d6">llvm::InstCombinerImpl::visitAtomicRMWInst</a>.</p>

</div>
</div>

### setAlignment() {#ae3245a9289f9b8fb4e8a9edeb4ed21f7}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void llvm::AtomicRMWInst::setAlignment (<a href="/web-llvm/docs/api/structs/llvm/align">Align</a> Align)</td>
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



<p>Definition at line 831 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/ir/instructions-h">Instructions.h</a>.</p>


<p>Reference <a href="/web-llvm/docs/api/namespaces/llvm/#ad82de9da62635df78a534de0f16c1129">llvm::Log2</a>.</p>

</div>
</div>

### setOperation() {#a85b3e8d240c7fef7c341a5224f492895}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void llvm::AtomicRMWInst::setOperation (<a href="#a461cfbbb5c7a57ab73210498923cf615">BinOp</a> Operation)</td>
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



<p>Definition at line 821 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/ir/instructions-h">Instructions.h</a>.</p>


<p>Reference <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/powerpc/ppcreducecrlogicals-cpp/#a5b2aa9d3f9f3a7b2d123fef7c5328b8f">Operation</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/classes/llvm/sitargetlowering/#ab4fd10263a383f485f869614143490be">llvm::SITargetLowering::emitExpandAtomicRMW</a> and <a href="/web-llvm/docs/api/classes/llvm/instcombinerimpl/#a3d5d32552609554018891c30a532f1d6">llvm::InstCombinerImpl::visitAtomicRMWInst</a>.</p>

</div>
</div>

### setOrdering() {#a5d1f392e4e23933104dbc6f0a5e78497}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void llvm::AtomicRMWInst::setOrdering (<a href="/web-llvm/docs/api/namespaces/llvm/#a9bccbe67aaab722783ca4e7c504aaaa7">AtomicOrdering</a> Ordering)</td>
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

<p>Sets the ordering constraint of this rmw instruction.</p>

<p>Definition at line 852 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/ir/instructions-h">Instructions.h</a>.</p>


<p>References <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/silowercontrolflow-cpp/#a4868c5d81c5ccc98c47aeab6244346a0">assert</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a9bccbe67aaab722783ca4e7c504aaaa7a56a57d29a3f9dda8671b4d6490a94b08">llvm::NotAtomic</a> and <a href="/web-llvm/docs/api/namespaces/llvm/#a9bccbe67aaab722783ca4e7c504aaaa7a288d468c5e0969f26a310773eda65603">llvm::Unordered</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/classes/llvm/instruction/#a3287172f2d13af086e6d66364e8c6de3">llvm::Instruction::getNumSuccessors</a>.</p>

</div>
</div>

### setSyncScopeID() {#a47cb069b9a3fdb9dd78d5a5055eb4689}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void llvm::AtomicRMWInst::setSyncScopeID (<a href="/web-llvm/docs/api/namespaces/llvm/syncscope/#a80741d3f96133391b683effd8e5b77f0">SyncScope::ID</a> SSID)</td>
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

<p>Sets the synchronization scope <a href="/web-llvm/docs/api/namespaces/llvm/callingconv/#abdf8cf606905c10634e831390981b0ed">ID</a> of this rmw instruction.</p>

<p>Definition at line 866 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/ir/instructions-h">Instructions.h</a>.</p>

</div>
</div>

### setVolatile() {#a361ca9304555f6c2e0dd2b3188439b33}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void llvm::AtomicRMWInst::setVolatile (bool V)</td>
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

<p>Specify whether this is a volatile RMW or not.</p>

<p>Definition at line 841 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/ir/instructions-h">Instructions.h</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/classes/llvm/instruction/#a55743bd32282bf6f87aeb49237b1fb68">llvm::Instruction::isCommutative</a>, <a href="/web-llvm/docs/api/classes/anonymous-amdgpuswlowerlds-cpp-/amdgpuswlowerlds/#a132e2ed28fb57bfad40af5505d2db16a">anonymous{AMDGPUSwLowerLDS.cpp}::AMDGPUSwLowerLDS::translateLDSMemoryOperationsToGlobalMemory</a> and <a href="/web-llvm/docs/api/files/lib/lib/ir/autoupgrade-cpp/#a9d9ad1173db1cee0c288f1b773baaf65">upgradeAMDGCNIntrinsicCall</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Protected Member Functions

### cloneImpl() {#a25a1f4bf68a202e553b2f4e227fb5eea}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">AtomicRMWInst * AtomicRMWInst::cloneImpl ()</td>
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



<p>Declaration at line 709 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/ir/instructions-h">Instructions.h</a>, definition at line 4315 of file <a href="/web-llvm/docs/api/files/lib/lib/ir/instructions-cpp">Instructions.cpp</a>.</p>


<p>References <a href="#ac70749f79f9e80a53b791daf274fb6a0">AtomicRMWInst</a>, <a href="#a0b5bee42a0652f7f46ec24c924e610d7">getAlign</a>, <a href="/web-llvm/docs/api/classes/llvm/user/#aa0a2cb1582d1cec317bd205085469ca1">llvm::User::getOperand</a>, <a href="#a99fd4ef84981d6a2774c14c741b5ed65">getOperation</a>, <a href="#aefa60bfe67b4721c395ce966ac73b439">getOrdering</a>, <a href="#ac97b19e5c8e2843543087d67e47be222">getSyncScopeID</a> and <a href="#a34f1aa991a80c9618af5d4e84aafcb9c">isVolatile</a>.</p>


<p>Referenced by <a href="#a87273cb892a8182f137567e6b631695e">Instruction</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Private Member Functions

### Init() {#a4873836d567d176e4cf143ec4d6fd6ca}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void AtomicRMWInst::Init (<a href="#a461cfbbb5c7a57ab73210498923cf615">BinOp</a> Operation, <a href="/web-llvm/docs/api/classes/llvm/value">Value</a> * Ptr, <a href="/web-llvm/docs/api/classes/llvm/value">Value</a> * Val, <a href="/web-llvm/docs/api/structs/llvm/align">Align</a> Align, <a href="/web-llvm/docs/api/namespaces/llvm/#a9bccbe67aaab722783ca4e7c504aaaa7">AtomicOrdering</a> Ordering, <a href="/web-llvm/docs/api/namespaces/llvm/syncscope/#a80741d3f96133391b683effd8e5b77f0">SyncScope::ID</a> SSID)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Declaration at line 895 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/ir/instructions-h">Instructions.h</a>, definition at line 1364 of file <a href="/web-llvm/docs/api/files/lib/lib/ir/instructions-cpp">Instructions.cpp</a>.</p>

</div>
</div>

### setSubclassData() {#a8a2f744b34043496091bc0bb45c52a8a}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<div class="doxyMemberTemplate">template &lt;typename Bitfield&gt;</div>
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void llvm::AtomicRMWInst::setSubclassData (typename Bitfield::Type Value)</td>
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



<p>Definition at line 901 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/ir/instructions-h">Instructions.h</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Private Member Attributes

### SSID {#abd37edff365a11a8942c156a26746dc0}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">SyncScope::ID llvm::AtomicRMWInst::SSID</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>The synchronization scope <a href="/web-llvm/docs/api/namespaces/llvm/callingconv/#abdf8cf606905c10634e831390981b0ed">ID</a> of this rmw instruction.</p>


<p>Not quite enough room in SubClassData for everything, so synchronization scope <a href="/web-llvm/docs/api/namespaces/llvm/callingconv/#abdf8cf606905c10634e831390981b0ed">ID</a> gets its own field.</p>


<p>Definition at line 908 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/ir/instructions-h">Instructions.h</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Public Static Functions

### classof() {#a6856195e004f0312d81613d253c144aa}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool llvm::AtomicRMWInst::classof (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/instruction">Instruction</a> * I)</td>
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



<p>Definition at line 887 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/ir/instructions-h">Instructions.h</a>.</p>


<p>References <a href="/web-llvm/docs/api/files/lib/lib/support/md5-cpp/#ac0eafdc9ee161b71e7af98af736952fd">I</a> and <a href="#a87273cb892a8182f137567e6b631695e">Instruction</a>.</p>


<p>Referenced by <a href="#a892c67a0c6eec011b6c22be9733ecf95">classof</a>.</p>

</div>
</div>

### classof() {#a892c67a0c6eec011b6c22be9733ecf95}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool llvm::AtomicRMWInst::classof (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/value">Value</a> * V)</td>
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



<p>Definition at line 890 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/ir/instructions-h">Instructions.h</a>.</p>


<p>References <a href="/web-llvm/docs/api/namespaces/llvm/#ac4fc845f5ed92de63cd4474f128f5fc5">llvm::cast</a>, <a href="#a6856195e004f0312d81613d253c144aa">classof</a> and <a href="/web-llvm/docs/api/namespaces/llvm/#a92ca992e52dddc420f4b069cae06dfbe">llvm::isa</a>.</p>

</div>
</div>

### getOperationName() {#ae8a61b9349a5ea2fb1b3d856bd4e9ab2}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">StringRef AtomicRMWInst::getOperationName (<a href="#a461cfbbb5c7a57ab73210498923cf615">BinOp</a> Op)</td>
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



<p>Declaration at line 807 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/ir/instructions-h">Instructions.h</a>, definition at line 1392 of file <a href="/web-llvm/docs/api/files/lib/lib/ir/instructions-cpp">Instructions.cpp</a>.</p>


<p>References <a href="#a461cfbbb5c7a57ab73210498923cf615a0794c42b44989f9d9f1454d79ca0dd88">Add</a>, <a href="#a461cfbbb5c7a57ab73210498923cf615a660a31179bfecd737a256372e5fd6122">And</a>, <a href="#a461cfbbb5c7a57ab73210498923cf615a497e8f347648b1b2823ee0338c95f65f">BAD_BINOP</a>, <a href="#a461cfbbb5c7a57ab73210498923cf615a08ef06068dcd583c2476568dda59b324">FAdd</a>, <a href="#a461cfbbb5c7a57ab73210498923cf615acce124326ba87b0127b36c412bf555fd">FMax</a>, <a href="#a461cfbbb5c7a57ab73210498923cf615abd5e733a10a36f3572105b1a67538e18">FMin</a>, <a href="#a461cfbbb5c7a57ab73210498923cf615a92f66d4bc04fc8514bee80509f3e78d4">FSub</a>, <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/support/errorhandling-h/#ace243f5c25697a1107cce46626b3dc94">llvm_unreachable</a>, <a href="#a461cfbbb5c7a57ab73210498923cf615aa1184a7e35e94d162a2d40f2b11beeb2">Max</a>, <a href="#a461cfbbb5c7a57ab73210498923cf615a39edb6e51c1ad37244e8b32a2af4077d">Min</a>, <a href="#a461cfbbb5c7a57ab73210498923cf615afdcdc631cf4fa6829fd7499cd06a306b">Nand</a>, <a href="#a461cfbbb5c7a57ab73210498923cf615a5954f59053121b87ebe0c5fe79942c6e">Or</a>, <a href="#a461cfbbb5c7a57ab73210498923cf615a5db6ca0c3e18acd87290f22ccb2ce564">Sub</a>, <a href="#a461cfbbb5c7a57ab73210498923cf615ad3ed1a8c334bc3a50d59aaa57ee9e9f3">UDecWrap</a>, <a href="#a461cfbbb5c7a57ab73210498923cf615a9334c9815ddc2b25804c6c03b68cc39b">UIncWrap</a>, <a href="#a461cfbbb5c7a57ab73210498923cf615abe171d96ba8de66fb30e08c00211591e">UMax</a>, <a href="#a461cfbbb5c7a57ab73210498923cf615aa53854e09143f57d2ff2ad6ac89dc55d">UMin</a>, <a href="#a461cfbbb5c7a57ab73210498923cf615a0f94e2ef083268e45d22a220f92567a4">USubCond</a>, <a href="#a461cfbbb5c7a57ab73210498923cf615a7bf1abb23eccced685c706917aff605c">USubSat</a>, <a href="#a461cfbbb5c7a57ab73210498923cf615afc870a548088c5b7a93a34f648889d77">Xchg</a> and <a href="#a461cfbbb5c7a57ab73210498923cf615a71aab8ee954b6d71a4eed315e8f6556e">Xor</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/siisellowering-cpp/#a70c624e7362eb836118fe7ee02737b43">emitAtomicRMWLegalRemark</a>, <a href="/web-llvm/docs/api/classes/llvm/sandboxir/atomicrmwinst/#a9afd0acf6e39251c6787d6080e38d3cf">llvm::sandboxir::AtomicRMWInst::getOperationName</a> and <a href="/web-llvm/docs/api/classes/anonymous-asmwriter-cpp-/assemblywriter/#a27130c5f74c2f20dd183f5ab83f54e6c">anonymous{AsmWriter.cpp}::AssemblyWriter::printInstruction</a>.</p>

</div>
</div>

### getPointerOperandIndex() {#a2f8f88574a509cf4545cd6420b405aaf}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">unsigned llvm::AtomicRMWInst::getPointerOperandIndex ()</td>
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



<p>Definition at line 872 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/ir/instructions-h">Instructions.h</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/classes/llvm/sitargetlowering/#aa7f6ff2830d775cf0c6a4052836c2552">llvm::SITargetLowering::emitExpandAtomicAddrSpacePredicate</a> and <a href="/web-llvm/docs/api/files/lib/lib/codegen/codegenprepare-cpp/#a498962c0029b14cf3cc8fb08c5e20ab2">FindAllMemoryUses</a>.</p>

</div>
</div>

### isFPOperation() {#a1bf3744f15082a41d139af3d01e9644d}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool llvm::AtomicRMWInst::isFPOperation (<a href="#a461cfbbb5c7a57ab73210498923cf615">BinOp</a> Op)</td>
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



<p>Definition at line 809 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/ir/instructions-h">Instructions.h</a>.</p>


<p>References <a href="#a461cfbbb5c7a57ab73210498923cf615a08ef06068dcd583c2476568dda59b324">FAdd</a>, <a href="#a461cfbbb5c7a57ab73210498923cf615acce124326ba87b0127b36c412bf555fd">FMax</a>, <a href="#a461cfbbb5c7a57ab73210498923cf615abd5e733a10a36f3572105b1a67538e18">FMin</a> and <a href="#a461cfbbb5c7a57ab73210498923cf615a92f66d4bc04fc8514bee80509f3e78d4">FSub</a>.</p>


<p>Referenced by <a href="#a667d327df48643f4d2111a0065b192f2">isFloatingPointOperation</a>, <a href="/web-llvm/docs/api/classes/llvm/sandboxir/atomicrmwinst/#af60564affb4bbaceb162e5ec53668c57">llvm::sandboxir::AtomicRMWInst::isFPOperation</a> and <a href="/web-llvm/docs/api/classes/anonymous-amdgpuatomicoptimizer-cpp-/amdgpuatomicoptimizerimpl/#a7686ed8fbdeb649c6997dd8906b0833a">anonymous{AMDGPUAtomicOptimizer.cpp}::AMDGPUAtomicOptimizerImpl::visitAtomicRMWInst</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Private Static Attributes

### AllocMarker {#a9b48f20421056e857255f7ceaf7c2538}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">IntrusiveOperandsAllocMarker llvm::AtomicRMWInst::AllocMarker {2}</td>
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



<p>Definition at line 785 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/ir/instructions-h">Instructions.h</a>.</p>

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
