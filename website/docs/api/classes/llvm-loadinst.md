---

# DO NOT EDIT!
# Automatically generated via doxygen2docusaurus by Doxygen.

slug: /api/classes/llvm/loadinst
custom_edit_url: null
toc_max_heading_level: 4
keywords:
  - doxygen
  - reference
  - class

---

<div class="doxyPage">

# `LoadInst` Class

<p>An instruction for reading from memory. <a href="#details">More...</a></p>

## Declaration

<div class="doxyDeclaration">
class llvm::LoadInst { ... }
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#acd49b2dd0d4d4007fdc3256609bf3e88">VolatileField</a> = <a href="/web-llvm/docs/api/classes/llvm/instruction/#a5575a4d18b30d5812be34d337378bf01">BoolBitfieldElementT</a>&lt; 0 &gt;</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#afe19903d0d6d31b69cfbdee3c81efd84">AlignmentField</a> = <a href="/web-llvm/docs/api/classes/llvm/instruction/#a04f5e8259cfe79c39de8db8dd73747cb">AlignmentBitfieldElementT</a>&lt; VolatileField::NextBit &gt;</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#abc92c7a3a674675182865b5960f5a12d">OrderingField</a> = <a href="/web-llvm/docs/api/classes/llvm/instruction/#a1ff5195448fd2558e384c94cb605cbaa">AtomicOrderingBitfieldElementT</a>&lt; AlignmentField::NextBit &gt;</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#aec14df5680e9e290707c08bcc55cbefc">LoadInst</a> (Type *Ty, Value *Ptr, const Twine &amp;NameStr, InsertPosition InsertBefore)</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ab28da565aa592176c65b94caab7b64b5">LoadInst</a> (Type *Ty, Value *Ptr, const Twine &amp;NameStr, bool isVolatile, InsertPosition InsertBefore)</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a3ee1ba57332277b72feb38a82c4e63bb">LoadInst</a> (Type *Ty, Value *Ptr, const Twine &amp;NameStr, bool isVolatile, Align Align, InsertPosition InsertBefore=nullptr)</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ab8d13cc98fc2777a70c49a4e6ede971f">LoadInst</a> (Type *Ty, Value *Ptr, const Twine &amp;NameStr, bool isVolatile, Align Align, AtomicOrdering Order, SyncScope::ID SSID=SyncScope::System, InsertPosition InsertBefore=nullptr)</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a2eccc19f9061eeb7ad1e30e21f76034d">isVolatile</a> () const</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Return true if this is a load from a volatile memory location. <a href="#a2eccc19f9061eeb7ad1e30e21f76034d">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">void</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ac363814e84ac1a3aa74798ff4d358a53">setVolatile</a> (bool V)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Specify whether this is a volatile load or not. <a href="#ac363814e84ac1a3aa74798ff4d358a53">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/structs/llvm/align">Align</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#af51c113a039c82f6870df5dc9666b5e3">getAlign</a> () const</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Return the alignment of the access that is being performed. <a href="#af51c113a039c82f6870df5dc9666b5e3">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">void</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a2b1268b642e9bf4373b6fb31c482c9ca">setAlignment</a> (Align Align)</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/namespaces/llvm/#a9bccbe67aaab722783ca4e7c504aaaa7">AtomicOrdering</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a93603fe0d4168b92a901f06015ecb2e7">getOrdering</a> () const</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Returns the ordering constraint of this load instruction. <a href="#a93603fe0d4168b92a901f06015ecb2e7">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">void</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a46adba111f7580ebfbb869a008de1818">setOrdering</a> (AtomicOrdering Ordering)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Sets the ordering constraint of this load instruction. <a href="#a46adba111f7580ebfbb869a008de1818">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/namespaces/llvm/syncscope/#a80741d3f96133391b683effd8e5b77f0">SyncScope::ID</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#aca6c2de6950cb093f509ed2b67e02da2">getSyncScopeID</a> () const</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Returns the synchronization scope <a href="/web-llvm/docs/api/namespaces/llvm/callingconv/#abdf8cf606905c10634e831390981b0ed">ID</a> of this load instruction. <a href="#aca6c2de6950cb093f509ed2b67e02da2">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">void</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a6406dc0bd5ecd638220d1f0d01f35d60">setSyncScopeID</a> (SyncScope::ID SSID)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Sets the synchronization scope <a href="/web-llvm/docs/api/namespaces/llvm/callingconv/#abdf8cf606905c10634e831390981b0ed">ID</a> of this load instruction. <a href="#a6406dc0bd5ecd638220d1f0d01f35d60">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">void</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a6ae88dc44b078c80ce3a25401fd4b05b">setAtomic</a> (AtomicOrdering Ordering, SyncScope::ID SSID=SyncScope::System)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Sets the ordering constraint and the synchronization scope <a href="/web-llvm/docs/api/namespaces/llvm/callingconv/#abdf8cf606905c10634e831390981b0ed">ID</a> of this load instruction. <a href="#a6ae88dc44b078c80ce3a25401fd4b05b">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">bool</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#aeb534c1a0391ce24551c226a582099a7">isSimple</a> () const</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ac072f8698be17d52f20bb63d59e6ce41">isUnordered</a> () const</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a2d1ff28d6923802e165905b8d1766e76">getPointerOperand</a> ()</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a1df3c027228bc08d14c6aa380a251625">getPointerOperand</a> () const</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a945c21ff70f310de538153db17e7b857">getPointerOperandType</a> () const</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a161c2db145827f4e181e7fe662b53a81">getPointerAddressSpace</a> () const</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Returns the address space of the pointer operand. <a href="#a161c2db145827f4e181e7fe662b53a81">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

</table>

## Protected Member Functions Index

<table class="doxyMembersIndex">

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/loadinst">LoadInst</a> *</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a8195fc57735a947a24bc9abee4a9c4d5">cloneImpl</a> () const</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ab4bafe3e2e2c70048f3b37ad0d091298">AssertOK</a> ()</td>
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
<td class="doxyMemberIndexItemNameTemplate" align="left" valign="top"><a href="#aa5e88511e1455dde998eaf471ececf76">setSubclassData</a> (typename Bitfield::Type Value)</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a2e57cd6a2e4658f06a7612360849f1f0">SSID</a></td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>The synchronization scope <a href="/web-llvm/docs/api/namespaces/llvm/callingconv/#abdf8cf606905c10634e831390981b0ed">ID</a> of this load instruction. <a href="#a2e57cd6a2e4658f06a7612360849f1f0">More...</a></p>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a976e49f35fef77df271900abfdc42cd5">getPointerOperandIndex</a> ()</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a3116b34bb86f0d908a2e82391f1ed38c">classof</a> (const Instruction *I)</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a482653d083d290f1c16ba289bd4d49fd">classof</a> (const Value *V)</td>
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

<p>An instruction for reading from memory.</p>


<p>This uses the SubclassData field in <a href="/web-llvm/docs/api/classes/llvm/value">Value</a> to store whether or not the load is volatile.</p>


<p>Definition at line 176 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/ir/instructions-h">Instructions.h</a>.</p>


<div class="doxySectionDef">

## Private Member Typedefs

### AlignmentField {#afe19903d0d6d31b69cfbdee3c81efd84}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">using llvm::LoadInst::AlignmentField =  AlignmentBitfieldElementT&lt;VolatileField::NextBit&gt;</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 178 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/ir/instructions-h">Instructions.h</a>.</p>

</div>
</div>

### OrderingField {#abc92c7a3a674675182865b5960f5a12d}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">using llvm::LoadInst::OrderingField =  AtomicOrderingBitfieldElementT&lt;AlignmentField::NextBit&gt;</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 179 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/ir/instructions-h">Instructions.h</a>.</p>

</div>
</div>

### VolatileField {#acd49b2dd0d4d4007fdc3256609bf3e88}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">using llvm::LoadInst::VolatileField =  BoolBitfieldElementT&lt;0&gt;</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 177 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/ir/instructions-h">Instructions.h</a>.</p>

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


<p>Definition at line 188 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/ir/instructions-h">Instructions.h</a>.</p>


<p>References <a href="#a87273cb892a8182f137567e6b631695e">Instruction</a>, <a href="#a2eccc19f9061eeb7ad1e30e21f76034d">isVolatile</a>, <a href="#aec14df5680e9e290707c08bcc55cbefc">LoadInst</a>, <a href="/web-llvm/docs/api/files/lib/lib/analysis/targetlibraryinfo-cpp/#aca185e6d0e9f423dbb24440206454872a11dbf501abf829b3ab7049c2d3a8a053">Ptr</a> and <a href="/web-llvm/docs/api/namespaces/llvm/syncscope/#a15caddcf5c9b41f2f15c2ec363589f6caf9706a2e196638078e8323bfd9ba17de">llvm::SyncScope::System</a>.</p>


<p>Referenced by <a href="#a3116b34bb86f0d908a2e82391f1ed38c">classof</a> and <a href="#a87273cb892a8182f137567e6b631695e">Instruction</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Public Constructors

### LoadInst() {#aec14df5680e9e290707c08bcc55cbefc}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">LoadInst::LoadInst (<a href="/web-llvm/docs/api/classes/llvm/type">Type</a> * Ty, <a href="/web-llvm/docs/api/classes/llvm/value">Value</a> * Ptr, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/twine">Twine</a> &amp; NameStr, <a href="/web-llvm/docs/api/classes/llvm/insertposition">InsertPosition</a> InsertBefore)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Declaration at line 193 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/ir/instructions-h">Instructions.h</a>, definition at line 1262 of file <a href="/web-llvm/docs/api/files/lib/lib/ir/instructions-cpp">Instructions.cpp</a>.</p>


<p>References <a href="#aec14df5680e9e290707c08bcc55cbefc">LoadInst</a> and <a href="/web-llvm/docs/api/files/lib/lib/analysis/targetlibraryinfo-cpp/#aca185e6d0e9f423dbb24440206454872a11dbf501abf829b3ab7049c2d3a8a053">Ptr</a>.</p>


<p>Referenced by <a href="#a8195fc57735a947a24bc9abee4a9c4d5">cloneImpl</a>, <a href="#a87273cb892a8182f137567e6b631695e">Instruction</a>, <a href="#a3ee1ba57332277b72feb38a82c4e63bb">LoadInst</a>, <a href="#ab28da565aa592176c65b94caab7b64b5">LoadInst</a> and <a href="#aec14df5680e9e290707c08bcc55cbefc">LoadInst</a>.</p>

</div>
</div>

### LoadInst() {#ab28da565aa592176c65b94caab7b64b5}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">LoadInst::LoadInst (<a href="/web-llvm/docs/api/classes/llvm/type">Type</a> * Ty, <a href="/web-llvm/docs/api/classes/llvm/value">Value</a> * Ptr, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/twine">Twine</a> &amp; NameStr, bool isVolatile, <a href="/web-llvm/docs/api/classes/llvm/insertposition">InsertPosition</a> InsertBefore)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Declaration at line 195 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/ir/instructions-h">Instructions.h</a>, definition at line 1266 of file <a href="/web-llvm/docs/api/files/lib/lib/ir/instructions-cpp">Instructions.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/files/lib/lib/ir/instructions-cpp/#a057e15a122129dc790055a5f344ddf2f">computeLoadStoreDefaultAlign</a>, <a href="#a2eccc19f9061eeb7ad1e30e21f76034d">isVolatile</a>, <a href="#aec14df5680e9e290707c08bcc55cbefc">LoadInst</a> and <a href="/web-llvm/docs/api/files/lib/lib/analysis/targetlibraryinfo-cpp/#aca185e6d0e9f423dbb24440206454872a11dbf501abf829b3ab7049c2d3a8a053">Ptr</a>.</p>

</div>
</div>

### LoadInst() {#a3ee1ba57332277b72feb38a82c4e63bb}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">LoadInst::LoadInst (<a href="/web-llvm/docs/api/classes/llvm/type">Type</a> * Ty, <a href="/web-llvm/docs/api/classes/llvm/value">Value</a> * Ptr, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/twine">Twine</a> &amp; NameStr, bool isVolatile, <a href="/web-llvm/docs/api/structs/llvm/align">Align</a> Align, <a href="/web-llvm/docs/api/classes/llvm/insertposition">InsertPosition</a> InsertBefore=nullptr)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Declaration at line 197 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/ir/instructions-h">Instructions.h</a>, definition at line 1271 of file <a href="/web-llvm/docs/api/files/lib/lib/ir/instructions-cpp">Instructions.cpp</a>.</p>


<p>References <a href="#a2eccc19f9061eeb7ad1e30e21f76034d">isVolatile</a>, <a href="#aec14df5680e9e290707c08bcc55cbefc">LoadInst</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a9bccbe67aaab722783ca4e7c504aaaa7a56a57d29a3f9dda8671b4d6490a94b08">llvm::NotAtomic</a> and <a href="/web-llvm/docs/api/files/lib/lib/analysis/targetlibraryinfo-cpp/#aca185e6d0e9f423dbb24440206454872a11dbf501abf829b3ab7049c2d3a8a053">Ptr</a>.</p>

</div>
</div>

### LoadInst() {#ab8d13cc98fc2777a70c49a4e6ede971f}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">LoadInst::LoadInst (<a href="/web-llvm/docs/api/classes/llvm/type">Type</a> * Ty, <a href="/web-llvm/docs/api/classes/llvm/value">Value</a> * Ptr, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/twine">Twine</a> &amp; NameStr, bool isVolatile, <a href="/web-llvm/docs/api/structs/llvm/align">Align</a> Align, <a href="/web-llvm/docs/api/namespaces/llvm/#a9bccbe67aaab722783ca4e7c504aaaa7">AtomicOrdering</a> Order, <a href="/web-llvm/docs/api/namespaces/llvm/syncscope/#a80741d3f96133391b683effd8e5b77f0">SyncScope::ID</a> SSID=<a href="/web-llvm/docs/api/namespaces/llvm/syncscope/#a15caddcf5c9b41f2f15c2ec363589f6caf9706a2e196638078e8323bfd9ba17de">SyncScope::System</a>, <a href="/web-llvm/docs/api/classes/llvm/insertposition">InsertPosition</a> InsertBefore=nullptr)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Declaration at line 199 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/ir/instructions-h">Instructions.h</a>, definition at line 1276 of file <a href="/web-llvm/docs/api/files/lib/lib/ir/instructions-cpp">Instructions.cpp</a>.</p>


<p>References <a href="#a2eccc19f9061eeb7ad1e30e21f76034d">isVolatile</a>, <a href="/web-llvm/docs/api/files/lib/lib/analysis/targetlibraryinfo-cpp/#aca185e6d0e9f423dbb24440206454872a11dbf501abf829b3ab7049c2d3a8a053">Ptr</a>, <a href="#a2b1268b642e9bf4373b6fb31c482c9ca">setAlignment</a>, <a href="#a6ae88dc44b078c80ce3a25401fd4b05b">setAtomic</a>, <a href="/web-llvm/docs/api/classes/llvm/value/#a35ee267850af7c235474a8c46c7ac5af">llvm::Value::setName</a>, <a href="#ac363814e84ac1a3aa74798ff4d358a53">setVolatile</a> and <a href="/web-llvm/docs/api/classes/llvm/unaryinstruction/#ad93ca9b74c44e7d8c00c72405e51262d">llvm::UnaryInstruction::UnaryInstruction</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Public Member Functions

### getAlign() {#af51c113a039c82f6870df5dc9666b5e3}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">Align llvm::LoadInst::getAlign ()</td>
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

<p>Return the alignment of the access that is being performed.</p>

<p>Definition at line 211 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/ir/instructions-h">Instructions.h</a>.</p>


<p>Reference <a href="/web-llvm/docs/api/classes/llvm/instruction/#a041694a1ea45996587ef9712d9a2bb1f">llvm::Instruction::getSubclassData</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/classes/anonymous-amdgpulatecodegenprepare-cpp-/amdgpulatecodegenprepare/#a92c9a1a2b05d0e6310b69180af44554a">anonymous{AMDGPULateCodeGenPrepare.cpp}::AMDGPULateCodeGenPrepare::canWidenScalarExtLoad</a>, <a href="#a8195fc57735a947a24bc9abee4a9c4d5">cloneImpl</a>, <a href="/web-llvm/docs/api/classes/llvm/instcombinerimpl/#ad7586c4efa39c8f9162c7608ff9a57cf">llvm::InstCombinerImpl::combineLoadToNewType</a>, <a href="/web-llvm/docs/api/classes/llvm/openmpirbuilder/#a388d5a62753f4e7ff4b72e54c1233fbc">llvm::OpenMPIRBuilder::createAtomicRead</a>, <a href="/web-llvm/docs/api/classes/anonymous-lowermatrixintrinsics-cpp-/lowermatrixintrinsics/#a133fc35b714b7fc4b5a0935c811ed37a">anonymous{LowerMatrixIntrinsics.cpp}::LowerMatrixIntrinsics::emitSIMDTiling</a>, <a href="/web-llvm/docs/api/classes/llvm/instcombinerimpl/#aa8a186c50cdf60ac11ae1d0b884d468d">llvm::InstCombinerImpl::foldPHIArgLoadIntoPHI</a>, <a href="/web-llvm/docs/api/classes/llvm/targetloweringbase/#a76e90df9d2b35d9174077de99d909165">llvm::TargetLoweringBase::getLoadMemOperandFlags</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#aeba325403d8d6430ee4a41b2cea631f5">llvm::isDereferenceableAndAlignedInLoop</a>, <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/scalar/sroa-cpp/#af029ac9445c750f9a2a2d90c2aeab9e3">isSafeLoadOfSelectToSpeculate</a>, <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/scalar/sroa-cpp/#aab37469c4748a495736ad163ac54e776">isSafePHIToSpeculate</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a5e36553611d3def8cf698c722239718f">llvm::isSafeToSpeculativelyExecuteWithOpcode</a>, <a href="/web-llvm/docs/api/classes/llvm/riscvtargetlowering/#adcc5d5714e94674aee99aacd991d2b4a">llvm::RISCVTargetLowering::lowerDeinterleaveIntrinsicToLoad</a>, <a href="/web-llvm/docs/api/classes/llvm/armtargetlowering/#ad190bc43c7fc8555debc7228fc5364b9">llvm::ARMTargetLowering::lowerInterleavedLoad</a>, <a href="/web-llvm/docs/api/classes/llvm/riscvtargetlowering/#a74b80978e3ab87994e9361f4bbc767dd">llvm::RISCVTargetLowering::lowerInterleavedLoad</a>, <a href="/web-llvm/docs/api/classes/anonymous-looploadelimination-cpp-/loadeliminationforloop/#acc9ee85c11fa2173c85a1ba82797d9fb">anonymous{LoopLoadElimination.cpp}::LoadEliminationForLoop::propagateStoredValueToLoadUsers</a>, <a href="/web-llvm/docs/api/classes/llvm/jumpthreadingpass/#a064ce69a10374b5342954d481e21fa25">llvm::JumpThreadingPass::simplifyPartiallyRedundantLoad</a>, <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/scalar/sroa-cpp/#a80f5f1399bc814c650325a6c41e350e2">speculatePHINodeLoads</a>, <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/scalar/sroa-cpp/#ace8766b97ac54db2bec8c29e4016f3f6">speculateSelectInstLoads</a>, <a href="/web-llvm/docs/api/classes/anonymous-x86fastisel-cpp-/x86fastisel/#aa1616cca9834ae9c228730c62f4f8b43">anonymous{X86FastISel.cpp}::X86FastISel::tryToFoldLoadIntoMI</a>, <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/instcombine/instcombineloadstorealloca-cpp/#aa0014a4c2da32289f871b8d5a1aa538b">unpackLoadToAggregate</a>, <a href="/web-llvm/docs/api/classes/anonymous-lowermatrixintrinsics-cpp-/lowermatrixintrinsics/#a49e11eb7774b75fb97d50d78ed1de951">anonymous{LowerMatrixIntrinsics.cpp}::LowerMatrixIntrinsics::VisitLoad</a>, <a href="/web-llvm/docs/api/classes/anonymous-amdgpulatecodegenprepare-cpp-/amdgpulatecodegenprepare/#ac006d6756149a16407027bc971cedab0">anonymous{AMDGPULateCodeGenPrepare.cpp}::AMDGPULateCodeGenPrepare::visitLoadInst</a>, <a href="/web-llvm/docs/api/classes/anonymous-amdgpulowerbufferfatpointers-cpp-/splitptrstructs/#a6710af6aa118958e7ce91327582b3a98">anonymous{AMDGPULowerBufferFatPointers.cpp}::SplitPtrStructs::visitLoadInst</a>, <a href="/web-llvm/docs/api/classes/anonymous-dataflowsanitizer-cpp-/dfsanvisitor/#ab1f923b66b5437b4912f28e87b6076ff">anonymous{DataFlowSanitizer.cpp}::DFSanVisitor::visitLoadInst</a>, <a href="/web-llvm/docs/api/classes/anonymous-dxilflattenarrays-cpp-/dxilflattenarraysvisitor/#a9498339e26b296572a463a1300bf1a13">anonymous{DXILFlattenArrays.cpp}::DXILFlattenArraysVisitor::visitLoadInst</a>, <a href="/web-llvm/docs/api/classes/anonymous-scalarizer-cpp-/scalarizervisitor/#aa9a049f0da67dd58d8854ac1de525ac7">anonymous{Scalarizer.cpp}::ScalarizerVisitor::visitLoadInst</a>, <a href="/web-llvm/docs/api/classes/datascalarizervisitor/#a7c94d0952ba1d6986f0e78b62c303074">DataScalarizerVisitor::visitLoadInst</a> and <a href="/web-llvm/docs/api/classes/llvm/instcombinerimpl/#a3ba96a0d49ec5f1a062b075f54536a3c">llvm::InstCombinerImpl::visitLoadInst</a>.</p>

</div>
</div>

### getOrdering() {#a93603fe0d4168b92a901f06015ecb2e7}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">AtomicOrdering llvm::LoadInst::getOrdering ()</td>
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

<p>Returns the ordering constraint of this load instruction.</p>

<p>Definition at line 220 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/ir/instructions-h">Instructions.h</a>.</p>


<p>Reference <a href="/web-llvm/docs/api/classes/llvm/instruction/#a041694a1ea45996587ef9712d9a2bb1f">llvm::Instruction::getSubclassData</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/classes/llvm/aliassettracker/#a7f77b833b9cb8cf108202087d9447001">llvm::AliasSetTracker::add</a>, <a href="/web-llvm/docs/api/files/lib/lib/analysis/memoryssa-cpp/#ac01b3bf4dda9266ec05d70b2f55281fa">areLoadsReorderable</a>, <a href="#a8195fc57735a947a24bc9abee4a9c4d5">cloneImpl</a>, <a href="/web-llvm/docs/api/classes/llvm/instcombinerimpl/#ad7586c4efa39c8f9162c7608ff9a57cf">llvm::InstCombinerImpl::combineLoadToNewType</a>, <a href="#ac072f8698be17d52f20bb63d59e6ce41">isUnordered</a>, <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/ipo/globalopt-cpp/#a31b17b67a86749cfd99e97041c819791">OptimizeGlobalAddressOfAllocation</a>, <a href="/web-llvm/docs/api/classes/llvm/jumpthreadingpass/#a064ce69a10374b5342954d481e21fa25">llvm::JumpThreadingPass::simplifyPartiallyRedundantLoad</a>, <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/ipo/globalopt-cpp/#a77de6d50432bef62e38fd24f2030026c">TryToShrinkGlobalToBoolean</a>, <a href="/web-llvm/docs/api/classes/anonymous-amdgpulowerbufferfatpointers-cpp-/splitptrstructs/#a6710af6aa118958e7ce91327582b3a98">anonymous{AMDGPULowerBufferFatPointers.cpp}::SplitPtrStructs::visitLoadInst</a>, <a href="/web-llvm/docs/api/classes/anonymous-dataflowsanitizer-cpp-/dfsanvisitor/#ab1f923b66b5437b4912f28e87b6076ff">anonymous{DataFlowSanitizer.cpp}::DFSanVisitor::visitLoadInst</a> and <a href="/web-llvm/docs/api/classes/llvm/instcombinerimpl/#a3ba96a0d49ec5f1a062b075f54536a3c">llvm::InstCombinerImpl::visitLoadInst</a>.</p>

</div>
</div>

### getPointerAddressSpace() {#a161c2db145827f4e181e7fe662b53a81}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">unsigned llvm::LoadInst::getPointerAddressSpace ()</td>
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

<p>Definition at line 261 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/ir/instructions-h">Instructions.h</a>.</p>


<p>References <a href="/web-llvm/docs/api/classes/llvm/type/#a5ab2d0b0f0b8ceec3b907184e7567197">llvm::Type::getPointerAddressSpace</a> and <a href="#a945c21ff70f310de538153db17e7b857">getPointerOperandType</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/instcombine/instcombineloadstorealloca-cpp/#a495e0c2946cb54155fefdf25d2cf8454">canSimplifyNullLoadOrGEP</a>, <a href="/web-llvm/docs/api/classes/anonymous-amdgpulatecodegenprepare-cpp-/amdgpulatecodegenprepare/#a92c9a1a2b05d0e6310b69180af44554a">anonymous{AMDGPULateCodeGenPrepare.cpp}::AMDGPULateCodeGenPrepare::canWidenScalarExtLoad</a>, <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/aggressiveinstcombine/aggressiveinstcombine-cpp/#a8f64e8576d57bb362e730214c7e6fae9">foldLoadsRecursive</a>, <a href="/web-llvm/docs/api/classes/llvm/instcombinerimpl/#aa8a186c50cdf60ac11ae1d0b884d468d">llvm::InstCombinerImpl::foldPHIArgLoadIntoPHI</a>, <a href="/web-llvm/docs/api/classes/llvm/riscvtargetlowering/#adcc5d5714e94674aee99aacd991d2b4a">llvm::RISCVTargetLowering::lowerDeinterleaveIntrinsicToLoad</a>, <a href="/web-llvm/docs/api/classes/llvm/armtargetlowering/#ad190bc43c7fc8555debc7228fc5364b9">llvm::ARMTargetLowering::lowerInterleavedLoad</a>, <a href="/web-llvm/docs/api/classes/llvm/riscvtargetlowering/#a74b80978e3ab87994e9361f4bbc767dd">llvm::RISCVTargetLowering::lowerInterleavedLoad</a>, <a href="/web-llvm/docs/api/classes/llvm/sitargetlowering/#a6027e99a9e19921f271d143258be3545">llvm::SITargetLowering::shouldExpandAtomicLoadInIR</a> and <a href="/web-llvm/docs/api/classes/llvm/instcombinerimpl/#a3ba96a0d49ec5f1a062b075f54536a3c">llvm::InstCombinerImpl::visitLoadInst</a>.</p>

</div>
</div>

### getPointerOperand() {#a2d1ff28d6923802e165905b8d1766e76}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">Value * llvm::LoadInst::getPointerOperand ()</td>
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



<p>Definition at line 255 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/ir/instructions-h">Instructions.h</a>.</p>


<p>Reference <a href="/web-llvm/docs/api/classes/llvm/user/#aa0a2cb1582d1cec317bd205085469ca1">llvm::User::getOperand</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/classes/llvm/memorydepchecker/#ac35e34e7ae9695a3d616ee7a311d0e54">llvm::MemoryDepChecker::addAccess</a>, <a href="/web-llvm/docs/api/namespaces/llvm/vncoercion/#a9534d3bff0727cc904e6bbc1064d2e2f">llvm::VNCoercion::analyzeLoadFromClobberingLoad</a>, <a href="/web-llvm/docs/api/classes/llvm/instcombinerimpl/#ad7586c4efa39c8f9162c7608ff9a57cf">llvm::InstCombinerImpl::combineLoadToNewType</a>, <a href="/web-llvm/docs/api/structs/anonymous-interleavedloadcombinepass-cpp-/vectorinfo/#a0cb38e302133457f235fdcc6723abeac">anonymous{InterleavedLoadCombinePass.cpp}::VectorInfo::computeFromLI</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#ab057ca6ed74ccfa73d1a0d2cf15b2300">llvm::copyNonnullMetadata</a>, <a href="/web-llvm/docs/api/classes/llvm/openmpirbuilder/#a388d5a62753f4e7ff4b72e54c1233fbc">llvm::OpenMPIRBuilder::createAtomicRead</a>, <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/vectorize/slpvectorizer-cpp/#a596e8b6e6b71f454b18f982f947e5e03">doesInTreeUserNeedToExtract</a>, <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/aggressiveinstcombine/aggressiveinstcombine-cpp/#a8f64e8576d57bb362e730214c7e6fae9">foldLoadsRecursive</a>, <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/vectorize/slpvectorizer-cpp/#a9e4f7b81913ac2176cac1eaa2b66a0b7">gatherPossiblyVectorizableLoads</a>, <a href="/web-llvm/docs/api/classes/llvm/memorylocation/#a18e5a3f1d71ba10a624f2a8e5121cf1f">llvm::MemoryLocation::get</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64targettransforminfo-cpp/#a0ef183a0f2f6e678cc5f7223aca82535">getFalkorUnrollingPreferences</a>, <a href="/web-llvm/docs/api/classes/llvm/memorydependenceresults/#a81ed5939e93e21552b452f5f82a73a38">llvm::MemoryDependenceResults::getInvariantGroupPointerDependency</a>, <a href="/web-llvm/docs/api/classes/llvm/targetloweringbase/#a76e90df9d2b35d9174077de99d909165">llvm::TargetLoweringBase::getLoadMemOperandFlags</a>, <a href="#a945c21ff70f310de538153db17e7b857">getPointerOperandType</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#aeba325403d8d6430ee4a41b2cea631f5">llvm::isDereferenceableAndAlignedInLoop</a>, <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/scalar/licm-cpp/#a831a5dec04e512d616fccb6e1f474e79">isLoadInvariantInLoop</a>, <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/utils/simplifylibcalls-cpp/#a766df1ea3c4bf3cbc8586f310562034f">isReportingError</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a5e36553611d3def8cf698c722239718f">llvm::isSafeToSpeculativelyExecuteWithOpcode</a>, <a href="/web-llvm/docs/api/classes/llvm/aarch64targetlowering/#ac66d3f15510c7402f2a85a87c69f1603">llvm::AArch64TargetLowering::lowerDeinterleaveIntrinsicToLoad</a>, <a href="/web-llvm/docs/api/classes/llvm/riscvtargetlowering/#adcc5d5714e94674aee99aacd991d2b4a">llvm::RISCVTargetLowering::lowerDeinterleaveIntrinsicToLoad</a>, <a href="/web-llvm/docs/api/classes/llvm/aarch64targetlowering/#a6cbcd096f254563525e65e58557ed901">llvm::AArch64TargetLowering::lowerInterleavedLoad</a>, <a href="/web-llvm/docs/api/classes/llvm/armtargetlowering/#ad190bc43c7fc8555debc7228fc5364b9">llvm::ARMTargetLowering::lowerInterleavedLoad</a>, <a href="/web-llvm/docs/api/classes/llvm/riscvtargetlowering/#a74b80978e3ab87994e9361f4bbc767dd">llvm::RISCVTargetLowering::lowerInterleavedLoad</a>, <a href="/web-llvm/docs/api/classes/anonymous-slpvectorizer-cpp-/horizontalreduction/#a7df4bae7dbd152d7a3c399384a110fe8">anonymous{SLPVectorizer.cpp}::HorizontalReduction::matchAssociativeReduction</a>, <a href="/web-llvm/docs/api/namespaces/anonymous-mergeicmps-cpp-/#a5289777e58accae64ebded1a95e4c8b0">anonymous{MergeICmps.cpp}::mergeComparisons</a>, <a href="/web-llvm/docs/api/classes/anonymous-looploadelimination-cpp-/loadeliminationforloop/#acc9ee85c11fa2173c85a1ba82797d9fb">anonymous{LoopLoadElimination.cpp}::LoadEliminationForLoop::propagateStoredValueToLoadUsers</a>, <a href="/web-llvm/docs/api/structs/llvm/pgoindirectcallvisitor/#aba025734aa83b5cacf35c35bd572ee0e">llvm::PGOIndirectCallVisitor::tryGetVTableInstruction</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#ad3219f7b717320ae52f53ccb09ad5a84">llvm::tryPromoteCall</a>, <a href="/web-llvm/docs/api/classes/anonymous-x86fastisel-cpp-/x86fastisel/#aa1616cca9834ae9c228730c62f4f8b43">anonymous{X86FastISel.cpp}::X86FastISel::tryToFoldLoadIntoMI</a>, <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/aggressiveinstcombine/aggressiveinstcombine-cpp/#a6594a7d514d3847ccbe52b66a49d8ee5">tryToRecognizeTableBasedCttz</a>, <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/instcombine/instcombineloadstorealloca-cpp/#aa0014a4c2da32289f871b8d5a1aa538b">unpackLoadToAggregate</a>, <a href="/web-llvm/docs/api/classes/anonymous-amdgpulatecodegenprepare-cpp-/amdgpulatecodegenprepare/#ac006d6756149a16407027bc971cedab0">anonymous{AMDGPULateCodeGenPrepare.cpp}::AMDGPULateCodeGenPrepare::visitLoadInst</a>, <a href="/web-llvm/docs/api/classes/anonymous-amdgpulowerbufferfatpointers-cpp-/splitptrstructs/#a6710af6aa118958e7ce91327582b3a98">anonymous{AMDGPULowerBufferFatPointers.cpp}::SplitPtrStructs::visitLoadInst</a>, <a href="/web-llvm/docs/api/classes/anonymous-dataflowsanitizer-cpp-/dfsanvisitor/#ab1f923b66b5437b4912f28e87b6076ff">anonymous{DataFlowSanitizer.cpp}::DFSanVisitor::visitLoadInst</a> and <a href="/web-llvm/docs/api/classes/anonymous-scalarizer-cpp-/scalarizervisitor/#aa9a049f0da67dd58d8854ac1de525ac7">anonymous{Scalarizer.cpp}::ScalarizerVisitor::visitLoadInst</a>.</p>

</div>
</div>

### getPointerOperand() {#a1df3c027228bc08d14c6aa380a251625}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">const Value * llvm::LoadInst::getPointerOperand ()</td>
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



<p>Definition at line 256 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/ir/instructions-h">Instructions.h</a>.</p>


<p>Reference <a href="/web-llvm/docs/api/classes/llvm/user/#aa0a2cb1582d1cec317bd205085469ca1">llvm::User::getOperand</a>.</p>

</div>
</div>

### getPointerOperandType() {#a945c21ff70f310de538153db17e7b857}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">Type * llvm::LoadInst::getPointerOperandType ()</td>
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



<p>Definition at line 258 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/ir/instructions-h">Instructions.h</a>.</p>


<p>References <a href="#a2d1ff28d6923802e165905b8d1766e76">getPointerOperand</a> and <a href="/web-llvm/docs/api/classes/llvm/value/#a0344a49526443edf90cc0aef3abd3337">llvm::Value::getType</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/classes/llvm/loopvectorizationcostmodel/#a556ec90a0fa1e168a9f22db1deb1fee6">llvm::LoopVectorizationCostModel::getInstructionCost</a>, <a href="#a161c2db145827f4e181e7fe662b53a81">getPointerAddressSpace</a>, <a href="/web-llvm/docs/api/classes/llvm/aarch64targetlowering/#ac66d3f15510c7402f2a85a87c69f1603">llvm::AArch64TargetLowering::lowerDeinterleaveIntrinsicToLoad</a>, <a href="/web-llvm/docs/api/classes/llvm/riscvtargetlowering/#adcc5d5714e94674aee99aacd991d2b4a">llvm::RISCVTargetLowering::lowerDeinterleaveIntrinsicToLoad</a>, <a href="/web-llvm/docs/api/classes/llvm/aarch64targetlowering/#a6cbcd096f254563525e65e58557ed901">llvm::AArch64TargetLowering::lowerInterleavedLoad</a>, <a href="/web-llvm/docs/api/classes/llvm/riscvtargetlowering/#a74b80978e3ab87994e9361f4bbc767dd">llvm::RISCVTargetLowering::lowerInterleavedLoad</a> and <a href="/web-llvm/docs/api/classes/anonymous-amdgpulowerbufferfatpointers-cpp-/splitptrstructs/#a6710af6aa118958e7ce91327582b3a98">anonymous{AMDGPULowerBufferFatPointers.cpp}::SplitPtrStructs::visitLoadInst</a>.</p>

</div>
</div>

### getSyncScopeID() {#aca6c2de6950cb093f509ed2b67e02da2}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">SyncScope::ID llvm::LoadInst::getSyncScopeID ()</td>
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

<p>Returns the synchronization scope <a href="/web-llvm/docs/api/namespaces/llvm/callingconv/#abdf8cf606905c10634e831390981b0ed">ID</a> of this load instruction.</p>

<p>Definition at line 230 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/ir/instructions-h">Instructions.h</a>.</p>


<p>Referenced by <a href="#a8195fc57735a947a24bc9abee4a9c4d5">cloneImpl</a>, <a href="/web-llvm/docs/api/classes/llvm/instcombinerimpl/#ad7586c4efa39c8f9162c7608ff9a57cf">llvm::InstCombinerImpl::combineLoadToNewType</a>, <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/ipo/globalopt-cpp/#a31b17b67a86749cfd99e97041c819791">OptimizeGlobalAddressOfAllocation</a>, <a href="/web-llvm/docs/api/classes/llvm/jumpthreadingpass/#a064ce69a10374b5342954d481e21fa25">llvm::JumpThreadingPass::simplifyPartiallyRedundantLoad</a>, <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/ipo/globalopt-cpp/#a77de6d50432bef62e38fd24f2030026c">TryToShrinkGlobalToBoolean</a>, <a href="/web-llvm/docs/api/classes/anonymous-amdgpulowerbufferfatpointers-cpp-/splitptrstructs/#a6710af6aa118958e7ce91327582b3a98">anonymous{AMDGPULowerBufferFatPointers.cpp}::SplitPtrStructs::visitLoadInst</a> and <a href="/web-llvm/docs/api/classes/llvm/instcombinerimpl/#a3ba96a0d49ec5f1a062b075f54536a3c">llvm::InstCombinerImpl::visitLoadInst</a>.</p>

</div>
</div>

### isSimple() {#aeb534c1a0391ce24551c226a582099a7}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool llvm::LoadInst::isSimple ()</td>
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



<p>Definition at line 247 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/ir/instructions-h">Instructions.h</a>.</p>


<p>References <a href="/web-llvm/docs/api/classes/llvm/instruction/#a57efb022f2ee2e19e4cdf582f4d27f2d">llvm::Instruction::isAtomic</a> and <a href="#a2eccc19f9061eeb7ad1e30e21f76034d">isVolatile</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/classes/anonymous-amdgpulatecodegenprepare-cpp-/amdgpulatecodegenprepare/#a92c9a1a2b05d0e6310b69180af44554a">anonymous{AMDGPULateCodeGenPrepare.cpp}::AMDGPULateCodeGenPrepare::canWidenScalarExtLoad</a>, <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/aggressiveinstcombine/aggressiveinstcombine-cpp/#a8f64e8576d57bb362e730214c7e6fae9">foldLoadsRecursive</a>, <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/scalar/sroa-cpp/#af029ac9445c750f9a2a2d90c2aeab9e3">isSafeLoadOfSelectToSpeculate</a>, <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/scalar/sroa-cpp/#aab37469c4748a495736ad163ac54e776">isSafePHIToSpeculate</a>, <a href="/web-llvm/docs/api/classes/llvm/riscvtargetlowering/#adcc5d5714e94674aee99aacd991d2b4a">llvm::RISCVTargetLowering::lowerDeinterleaveIntrinsicToLoad</a>, <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/scalar/sroa-cpp/#ace8766b97ac54db2bec8c29e4016f3f6">speculateSelectInstLoads</a>, <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/instcombine/instcombineloadstorealloca-cpp/#aa0014a4c2da32289f871b8d5a1aa538b">unpackLoadToAggregate</a> and <a href="/web-llvm/docs/api/classes/anonymous-scalarizer-cpp-/scalarizervisitor/#aa9a049f0da67dd58d8854ac1de525ac7">anonymous{Scalarizer.cpp}::ScalarizerVisitor::visitLoadInst</a>.</p>

</div>
</div>

### isUnordered() {#ac072f8698be17d52f20bb63d59e6ce41}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool llvm::LoadInst::isUnordered ()</td>
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



<p>Definition at line 249 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/ir/instructions-h">Instructions.h</a>.</p>


<p>References <a href="#a93603fe0d4168b92a901f06015ecb2e7">getOrdering</a>, <a href="#a2eccc19f9061eeb7ad1e30e21f76034d">isVolatile</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a9bccbe67aaab722783ca4e7c504aaaa7a56a57d29a3f9dda8671b4d6490a94b08">llvm::NotAtomic</a> and <a href="/web-llvm/docs/api/namespaces/llvm/#a9bccbe67aaab722783ca4e7c504aaaa7a288d468c5e0969f26a310773eda65603">llvm::Unordered</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/classes/llvm/ppctargetlowering/#a857dba88c2223d0a509b5d390f7144f0">llvm::PPCTargetLowering::isProfitableToHoist</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a423120c6a3bab0386276333090b574f8">llvm::mustSuppressSpeculation</a>, <a href="/web-llvm/docs/api/classes/llvm/jumpthreadingpass/#a064ce69a10374b5342954d481e21fa25">llvm::JumpThreadingPass::simplifyPartiallyRedundantLoad</a> and <a href="/web-llvm/docs/api/classes/llvm/instcombinerimpl/#a3ba96a0d49ec5f1a062b075f54536a3c">llvm::InstCombinerImpl::visitLoadInst</a>.</p>

</div>
</div>

### isVolatile() {#a2eccc19f9061eeb7ad1e30e21f76034d}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool llvm::LoadInst::isVolatile ()</td>
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

<p>Return true if this is a load from a volatile memory location.</p>

<p>Definition at line 205 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/ir/instructions-h">Instructions.h</a>.</p>


<p>Reference <a href="/web-llvm/docs/api/classes/llvm/instruction/#a041694a1ea45996587ef9712d9a2bb1f">llvm::Instruction::getSubclassData</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/files/lib/lib/analysis/memoryssa-cpp/#ac01b3bf4dda9266ec05d70b2f55281fa">areLoadsReorderable</a>, <a href="#a8195fc57735a947a24bc9abee4a9c4d5">cloneImpl</a>, <a href="/web-llvm/docs/api/classes/llvm/instcombinerimpl/#ad7586c4efa39c8f9162c7608ff9a57cf">llvm::InstCombinerImpl::combineLoadToNewType</a>, <a href="/web-llvm/docs/api/structs/anonymous-interleavedloadcombinepass-cpp-/vectorinfo/#a0cb38e302133457f235fdcc6723abeac">anonymous{InterleavedLoadCombinePass.cpp}::VectorInfo::computeFromLI</a>, <a href="/web-llvm/docs/api/classes/anonymous-lowermatrixintrinsics-cpp-/lowermatrixintrinsics/#a133fc35b714b7fc4b5a0935c811ed37a">anonymous{LowerMatrixIntrinsics.cpp}::LowerMatrixIntrinsics::emitSIMDTiling</a>, <a href="/web-llvm/docs/api/classes/llvm/instcombinerimpl/#a866883cec7ed781fcf1e9cda18b24f5b">llvm::InstCombinerImpl::foldCmpLoadFromIndexedGlobal</a>, <a href="/web-llvm/docs/api/classes/llvm/instcombinerimpl/#aa8a186c50cdf60ac11ae1d0b884d468d">llvm::InstCombinerImpl::foldPHIArgLoadIntoPHI</a>, <a href="/web-llvm/docs/api/classes/llvm/targetloweringbase/#a76e90df9d2b35d9174077de99d909165">llvm::TargetLoweringBase::getLoadMemOperandFlags</a>, <a href="#a87273cb892a8182f137567e6b631695e">Instruction</a>, <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/scalar/sroa-cpp/#a593afa69fb7cfbb4506f605bd785f923">isIntegerWideningViableForSlice</a>, <a href="#aeb534c1a0391ce24551c226a582099a7">isSimple</a>, <a href="#ac072f8698be17d52f20bb63d59e6ce41">isUnordered</a>, <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/scalar/sroa-cpp/#ab4c31035e44c7bda618eb2eb81dcf314">isVectorPromotionViableForSlice</a>, <a href="#ab8d13cc98fc2777a70c49a4e6ede971f">LoadInst</a>, <a href="#a3ee1ba57332277b72feb38a82c4e63bb">LoadInst</a>, <a href="#ab28da565aa592176c65b94caab7b64b5">LoadInst</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a99fa28f2d78ae2ce889b621ab275a4ad">llvm::simplifyLoadInst</a>, <a href="/web-llvm/docs/api/classes/llvm/fastisel/#a5a81ca548cc88df15a58aed766bdd890">llvm::FastISel::tryToFoldLoad</a>, <a href="/web-llvm/docs/api/classes/anonymous-lowermatrixintrinsics-cpp-/lowermatrixintrinsics/#a49e11eb7774b75fb97d50d78ed1de951">anonymous{LowerMatrixIntrinsics.cpp}::LowerMatrixIntrinsics::VisitLoad</a> and <a href="/web-llvm/docs/api/classes/anonymous-amdgpulowerbufferfatpointers-cpp-/splitptrstructs/#a6710af6aa118958e7ce91327582b3a98">anonymous{AMDGPULowerBufferFatPointers.cpp}::SplitPtrStructs::visitLoadInst</a>.</p>

</div>
</div>

### setAlignment() {#a2b1268b642e9bf4373b6fb31c482c9ca}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void llvm::LoadInst::setAlignment (<a href="/web-llvm/docs/api/structs/llvm/align">Align</a> Align)</td>
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



<p>Definition at line 215 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/ir/instructions-h">Instructions.h</a>.</p>


<p>Reference <a href="/web-llvm/docs/api/namespaces/llvm/#ad82de9da62635df78a534de0f16c1129">llvm::Log2</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/structs/anonymous-expandvectorpredication-cpp-/cachingvpexpander/#a1f1f1359a986d8e4d1b107ae4c524a32">anonymous{ExpandVectorPredication.cpp}::CachingVPExpander::expandPredicationInMemoryIntrinsic</a>, <a href="#ab8d13cc98fc2777a70c49a4e6ede971f">LoadInst</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#ae8cc923f4e20540201f1cd1225811b9f">llvm::promoteLoopAccessesToScalars</a>, <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/scalar/sroa-cpp/#ace8766b97ac54db2bec8c29e4016f3f6">speculateSelectInstLoads</a>, <a href="/web-llvm/docs/api/classes/anonymous-amdgpulatecodegenprepare-cpp-/amdgpulatecodegenprepare/#ac006d6756149a16407027bc971cedab0">anonymous{AMDGPULateCodeGenPrepare.cpp}::AMDGPULateCodeGenPrepare::visitLoadInst</a>, <a href="/web-llvm/docs/api/classes/anonymous-dxilflattenarrays-cpp-/dxilflattenarraysvisitor/#a9498339e26b296572a463a1300bf1a13">anonymous{DXILFlattenArrays.cpp}::DXILFlattenArraysVisitor::visitLoadInst</a>, <a href="/web-llvm/docs/api/classes/datascalarizervisitor/#a7c94d0952ba1d6986f0e78b62c303074">DataScalarizerVisitor::visitLoadInst</a> and <a href="/web-llvm/docs/api/classes/llvm/instcombinerimpl/#a3ba96a0d49ec5f1a062b075f54536a3c">llvm::InstCombinerImpl::visitLoadInst</a>.</p>

</div>
</div>

### setAtomic() {#a6ae88dc44b078c80ce3a25401fd4b05b}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void llvm::LoadInst::setAtomic (<a href="/web-llvm/docs/api/namespaces/llvm/#a9bccbe67aaab722783ca4e7c504aaaa7">AtomicOrdering</a> Ordering, <a href="/web-llvm/docs/api/namespaces/llvm/syncscope/#a80741d3f96133391b683effd8e5b77f0">SyncScope::ID</a> SSID=<a href="/web-llvm/docs/api/namespaces/llvm/syncscope/#a15caddcf5c9b41f2f15c2ec363589f6caf9706a2e196638078e8323bfd9ba17de">SyncScope::System</a>)</td>
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

<p>Sets the ordering constraint and the synchronization scope <a href="/web-llvm/docs/api/namespaces/llvm/callingconv/#abdf8cf606905c10634e831390981b0ed">ID</a> of this load instruction.</p>

<p>Definition at line 241 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/ir/instructions-h">Instructions.h</a>.</p>


<p>References <a href="#a46adba111f7580ebfbb869a008de1818">setOrdering</a>, <a href="#a6406dc0bd5ecd638220d1f0d01f35d60">setSyncScopeID</a> and <a href="/web-llvm/docs/api/namespaces/llvm/syncscope/#a15caddcf5c9b41f2f15c2ec363589f6caf9706a2e196638078e8323bfd9ba17de">llvm::SyncScope::System</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/classes/llvm/instcombinerimpl/#ad7586c4efa39c8f9162c7608ff9a57cf">llvm::InstCombinerImpl::combineLoadToNewType</a>, <a href="/web-llvm/docs/api/classes/llvm/openmpirbuilder/#a388d5a62753f4e7ff4b72e54c1233fbc">llvm::OpenMPIRBuilder::createAtomicRead</a>, <a href="#ab8d13cc98fc2777a70c49a4e6ede971f">LoadInst</a>, <a href="/web-llvm/docs/api/classes/llvm/sitargetlowering/#a818d0dbc281d144e0f02a0a75c7af1ee">llvm::SITargetLowering::lowerIdempotentRMWIntoFencedLoad</a>, <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/scalar/loweratomicpass-cpp/#a533cef247257a2fdcfbf3caed9edded6">LowerLoadInst</a>, <a href="/web-llvm/docs/api/classes/anonymous-amdgpuswlowerlds-cpp-/amdgpuswlowerlds/#a132e2ed28fb57bfad40af5505d2db16a">anonymous{AMDGPUSwLowerLDS.cpp}::AMDGPUSwLowerLDS::translateLDSMemoryOperationsToGlobalMemory</a> and <a href="/web-llvm/docs/api/classes/llvm/instcombinerimpl/#a3ba96a0d49ec5f1a062b075f54536a3c">llvm::InstCombinerImpl::visitLoadInst</a>.</p>

</div>
</div>

### setOrdering() {#a46adba111f7580ebfbb869a008de1818}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void llvm::LoadInst::setOrdering (<a href="/web-llvm/docs/api/namespaces/llvm/#a9bccbe67aaab722783ca4e7c504aaaa7">AtomicOrdering</a> Ordering)</td>
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

<p>Sets the ordering constraint of this load instruction.</p>


<p>May not be Release or AcquireRelease.</p>


<p>Definition at line 225 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/ir/instructions-h">Instructions.h</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/namespaces/llvm/#ae8cc923f4e20540201f1cd1225811b9f">llvm::promoteLoopAccessesToScalars</a>, <a href="#a6ae88dc44b078c80ce3a25401fd4b05b">setAtomic</a> and <a href="/web-llvm/docs/api/classes/anonymous-dataflowsanitizer-cpp-/dfsanvisitor/#ab1f923b66b5437b4912f28e87b6076ff">anonymous{DataFlowSanitizer.cpp}::DFSanVisitor::visitLoadInst</a>.</p>

</div>
</div>

### setSyncScopeID() {#a6406dc0bd5ecd638220d1f0d01f35d60}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void llvm::LoadInst::setSyncScopeID (<a href="/web-llvm/docs/api/namespaces/llvm/syncscope/#a80741d3f96133391b683effd8e5b77f0">SyncScope::ID</a> SSID)</td>
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

<p>Sets the synchronization scope <a href="/web-llvm/docs/api/namespaces/llvm/callingconv/#abdf8cf606905c10634e831390981b0ed">ID</a> of this load instruction.</p>

<p>Definition at line 235 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/ir/instructions-h">Instructions.h</a>.</p>


<p>Referenced by <a href="#a6ae88dc44b078c80ce3a25401fd4b05b">setAtomic</a>.</p>

</div>
</div>

### setVolatile() {#ac363814e84ac1a3aa74798ff4d358a53}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void llvm::LoadInst::setVolatile (bool V)</td>
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

<p>Specify whether this is a volatile load or not.</p>

<p>Definition at line 208 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/ir/instructions-h">Instructions.h</a>.</p>


<p>Referenced by <a href="#ab8d13cc98fc2777a70c49a4e6ede971f">LoadInst</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Protected Member Functions

### cloneImpl() {#a8195fc57735a947a24bc9abee4a9c4d5}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">LoadInst * LoadInst::cloneImpl ()</td>
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



<p>Declaration at line 190 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/ir/instructions-h">Instructions.h</a>, definition at line 4296 of file <a href="/web-llvm/docs/api/files/lib/lib/ir/instructions-cpp">Instructions.cpp</a>.</p>


<p>References <a href="#af51c113a039c82f6870df5dc9666b5e3">getAlign</a>, <a href="/web-llvm/docs/api/classes/llvm/user/#aa0a2cb1582d1cec317bd205085469ca1">llvm::User::getOperand</a>, <a href="#a93603fe0d4168b92a901f06015ecb2e7">getOrdering</a>, <a href="#aca6c2de6950cb093f509ed2b67e02da2">getSyncScopeID</a>, <a href="/web-llvm/docs/api/classes/llvm/value/#a0344a49526443edf90cc0aef3abd3337">llvm::Value::getType</a>, <a href="#a2eccc19f9061eeb7ad1e30e21f76034d">isVolatile</a> and <a href="#aec14df5680e9e290707c08bcc55cbefc">LoadInst</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Private Member Functions

### AssertOK() {#ab4bafe3e2e2c70048f3b37ad0d091298}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void LoadInst::AssertOK ()</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Declaration at line 184 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/ir/instructions-h">Instructions.h</a>, definition at line 1247 of file <a href="/web-llvm/docs/api/files/lib/lib/ir/instructions-cpp">Instructions.cpp</a>.</p>

</div>
</div>

### setSubclassData() {#aa5e88511e1455dde998eaf471ececf76}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<div class="doxyMemberTemplate">template &lt;typename Bitfield&gt;</div>
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void llvm::LoadInst::setSubclassData (typename Bitfield::Type Value)</td>
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



<p>Definition at line 277 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/ir/instructions-h">Instructions.h</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Private Member Attributes

### SSID {#a2e57cd6a2e4658f06a7612360849f1f0}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">SyncScope::ID llvm::LoadInst::SSID</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>The synchronization scope <a href="/web-llvm/docs/api/namespaces/llvm/callingconv/#abdf8cf606905c10634e831390981b0ed">ID</a> of this load instruction.</p>


<p>Not quite enough room in SubClassData for everything, so synchronization scope <a href="/web-llvm/docs/api/namespaces/llvm/callingconv/#abdf8cf606905c10634e831390981b0ed">ID</a> gets its own field.</p>


<p>Definition at line 284 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/ir/instructions-h">Instructions.h</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Public Static Functions

### classof() {#a3116b34bb86f0d908a2e82391f1ed38c}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool llvm::LoadInst::classof (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/instruction">Instruction</a> * I)</td>
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



<p>Definition at line 266 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/ir/instructions-h">Instructions.h</a>.</p>


<p>References <a href="/web-llvm/docs/api/files/lib/lib/support/md5-cpp/#ac0eafdc9ee161b71e7af98af736952fd">I</a> and <a href="#a87273cb892a8182f137567e6b631695e">Instruction</a>.</p>


<p>Referenced by <a href="#a482653d083d290f1c16ba289bd4d49fd">classof</a>.</p>

</div>
</div>

### classof() {#a482653d083d290f1c16ba289bd4d49fd}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool llvm::LoadInst::classof (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/value">Value</a> * V)</td>
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



<p>Definition at line 269 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/ir/instructions-h">Instructions.h</a>.</p>


<p>References <a href="/web-llvm/docs/api/namespaces/llvm/#ac4fc845f5ed92de63cd4474f128f5fc5">llvm::cast</a>, <a href="#a3116b34bb86f0d908a2e82391f1ed38c">classof</a> and <a href="/web-llvm/docs/api/namespaces/llvm/#a92ca992e52dddc420f4b069cae06dfbe">llvm::isa</a>.</p>

</div>
</div>

### getPointerOperandIndex() {#a976e49f35fef77df271900abfdc42cd5}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">unsigned llvm::LoadInst::getPointerOperandIndex ()</td>
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



<p>Definition at line 257 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/ir/instructions-h">Instructions.h</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/ipo/argumentpromotion-cpp/#a48b0c9b087f506b1c0071e7da6054e0f">doPromotion</a> and <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/utils/simplifycfg-cpp/#a7da8333874d1ad28bd987d4e7c474e53">sinkCommonCodeFromPredecessors</a>.</p>

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
