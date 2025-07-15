---

# DO NOT EDIT!
# Automatically generated via doxygen2docusaurus by Doxygen.

slug: /api/classes/llvm/user
custom_edit_url: null
toc_max_heading_level: 4
keywords:
  - doxygen
  - reference
  - class

---

<div class="doxyPage">

# The `User` Class Reference



## Declaration

<div class="doxyDeclaration">
class llvm::User { ... }
</div>

## Included Headers

<div class="doxyIncludesList">#include "<a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/ir/user-h">llvm/IR/User.h</a>"
</div>

## Base class

<table class="doxyMembersIndex">

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">class</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/value">Value</a></td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>LLVM <a href="/web-llvm/docs/api/classes/llvm/value">Value</a> Representation. <a href="/web-llvm/docs/api/classes/llvm/value/#details">More...</a></p>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/constant">Constant</a></td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>This is an important base class in LLVM. <a href="/web-llvm/docs/api/classes/llvm/constant/#details">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">class</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/deriveduser">DerivedUser</a></td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p><a href="/web-llvm/docs/api/structs/extension">Extension</a> point for the <a href="/web-llvm/docs/api/classes/llvm/value">Value</a> hierarchy. <a href="/web-llvm/docs/api/classes/llvm/deriveduser/#details">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

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

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">class</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/operator">Operator</a></td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>This is a utility class that provides an abstraction for the common functionality between Instructions and ConstantExprs. <a href="/web-llvm/docs/api/classes/llvm/operator/#details">More...</a></p>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a0126e6f10273e8db07142833979a0c8f">op_iterator</a> = <a href="/web-llvm/docs/api/classes/llvm/use">Use</a> *</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a670a0fc44293ba68935a3cff3b871893">const_op_iterator</a> = <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/use">Use</a> *</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a917548288129e24325af275795e4622f">op_range</a> = <a href="/web-llvm/docs/api/classes/llvm/iterator-range">iterator_range</a>&lt; <a href="#a0126e6f10273e8db07142833979a0c8f">op_iterator</a> &gt;</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a00c91d41d6da00a839684a27eff9b717">const_op_range</a> = <a href="/web-llvm/docs/api/classes/llvm/iterator-range">iterator_range</a>&lt; <a href="#a670a0fc44293ba68935a3cff3b871893">const_op_iterator</a> &gt;</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">struct</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a5fe79114a3ec7954798970ab57ad954a">HungoffOperandTraits</a></td>
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
<td class="doxyMemberIndexTemplate" colspan="2"><div>template &lt;class ConstantClass&gt;</div></td>
</tr>
<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemTypeTemplate" align="left" valign="top">struct</td>
<td class="doxyMemberIndexItemNameTemplate" align="left" valign="top"><a href="#ad772de3fed881a64ad7437da1599cf19">ConstantAggrKeyType</a></td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#abcc26789f64ec564961893b4ddba5c24">User</a> (const User &amp;)=delete</td>
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

## Protected Constructors Index

<table class="doxyMembersIndex">

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a282fa3e9586425313e0a954c18deee15">User</a> (Type *ty, unsigned vty, AllocInfo AllocInfo)</td>
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

## Protected Destructor Index

<table class="doxyMembersIndex">

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#aa56ec414c4256c8435f4c97ec192019a">~User</a> ()=default</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">void</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a96c162b315ccc10487a1359cb15f8c98">operator delete</a> (void *Usr)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Free memory allocated for <a href="/web-llvm/docs/api/classes/llvm/user">User</a> and <a href="/web-llvm/docs/api/classes/llvm/use">Use</a> objects. <a href="#a96c162b315ccc10487a1359cb15f8c98">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">void</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a247006d94472c8d80b5cf143a9c5a2b9">operator delete</a> (void *Usr, HungOffOperandsAllocMarker)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Placement delete - required by std, called if the ctor throws. <a href="#a247006d94472c8d80b5cf143a9c5a2b9">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">void</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a3ba87e798a0df56e983d393e0a1abc1a">operator delete</a> (void *Usr, IntrusiveOperandsAllocMarker)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Placement delete - required by std, called if the ctor throws. <a href="#a3ba87e798a0df56e983d393e0a1abc1a">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">void</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#acb6e60cad24aed54fa19ce71074c7ecb">operator delete</a> (void *Usr, IntrusiveOperandsAndDescriptorAllocMarker)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Placement delete - required by std, called if the ctor throws. <a href="#acb6e60cad24aed54fa19ce71074c7ecb">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

</table>

## Protected Operators Index

<table class="doxyMembersIndex">

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">void *</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a6fe0552bc8842bffe58e1d7873346f7b">operator new</a> (size_t Size)=delete</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">void *</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ad379730885bf082d40fd8aa4af1e553d">operator new</a> (size_t Size, HungOffOperandsAllocMarker)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Allocate a <a href="/web-llvm/docs/api/classes/llvm/user">User</a> with an operand pointer co-allocated. <a href="#ad379730885bf082d40fd8aa4af1e553d">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">void *</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a1324a54e2b6221c9dc2e74725a3570c1">operator new</a> (size_t Size, IntrusiveOperandsAllocMarker allocTrait)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Allocate a <a href="/web-llvm/docs/api/classes/llvm/user">User</a> with the operands co-allocated. <a href="#a1324a54e2b6221c9dc2e74725a3570c1">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">void *</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#aee898f8818ca582daae5d35eaf92f4cf">operator new</a> (size_t Size, IntrusiveOperandsAndDescriptorAllocMarker allocTrait)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Allocate a <a href="/web-llvm/docs/api/classes/llvm/user">User</a> with the operands co-allocated. <a href="#aee898f8818ca582daae5d35eaf92f4cf">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

</table>

## Public Member Functions Index

<table class="doxyMembersIndex">

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/use">Use</a> *</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a024c7e10ce431a93ffdb4e5e6401e0be">getOperandList</a> () const</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/use">Use</a> *</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a6155b029eaffe271cf2a711141fbd0e3">getOperandList</a> ()</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#aa0a2cb1582d1cec317bd205085469ca1">getOperand</a> (unsigned i) const</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a5fa9b8e1842b354f64c1ba6be0a4a17f">setOperand</a> (unsigned i, Value *Val)</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/use">Use</a> &amp;</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a3f3b252f63d32a9a6e05208ce26562bf">getOperandUse</a> (unsigned i) const</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/use">Use</a> &amp;</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a6b69f170344729a16c5f3bbf89aea84d">getOperandUse</a> (unsigned i)</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#addec638786f763d967811b45cb662f1f">getNumOperands</a> () const</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/arrayref">ArrayRef</a>&lt; <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> uint8_t &gt;</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a0d4a83cd78f12aa1ab452c4d94b9cb7b">getDescriptor</a> () const</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Returns the descriptor co-allocated with this <a href="/web-llvm/docs/api/classes/llvm/user">User</a> instance. <a href="#a0d4a83cd78f12aa1ab452c4d94b9cb7b">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/mutablearrayref">MutableArrayRef</a>&lt; uint8_t &gt;</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a068b54eba6b02473bb14f3b13b85d086">getDescriptor</a> ()</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Returns the descriptor co-allocated with this <a href="/web-llvm/docs/api/classes/llvm/user">User</a> instance. <a href="#a068b54eba6b02473bb14f3b13b85d086">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">void</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a715e8009737f71c4b3d2ea7d2abc33c4">setNumHungOffUseOperands</a> (unsigned NumOps)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Subclasses with hung off uses need to manage the operand count themselves. <a href="#a715e8009737f71c4b3d2ea7d2abc33c4">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">bool</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#af6a49991304b167c94f4a9756d3fd48f">isDroppable</a> () const</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>A droppable user is a user for which uses can be dropped without affecting correctness and should be dropped rather than preventing a transformation from happening. <a href="#af6a49991304b167c94f4a9756d3fd48f">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="#a0126e6f10273e8db07142833979a0c8f">op_iterator</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a2eeb1c7ed1cfe403f2ae0470e36c07e2">op_begin</a> ()</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="#a670a0fc44293ba68935a3cff3b871893">const_op_iterator</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a418704eb3b3a706e679e0a2d42b5dc7c">op_begin</a> () const</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="#a0126e6f10273e8db07142833979a0c8f">op_iterator</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#af41f58e730804d10b91fcff39b035f74">op_end</a> ()</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="#a670a0fc44293ba68935a3cff3b871893">const_op_iterator</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a49d32fbcf8305d76cfff528214a4eca0">op_end</a> () const</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="#a917548288129e24325af275795e4622f">op_range</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a0b931781aa589c6ebe64a76c1447e5b2">operands</a> ()</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="#a00c91d41d6da00a839684a27eff9b717">const_op_range</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#acbac91af886d94a4cd0b41c506f7051b">operands</a> () const</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/structs/llvm/user/value-op-iterator">value_op_iterator</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ad93396a26f6fd589ed400bb280319836">value_op_begin</a> ()</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/structs/llvm/user/value-op-iterator">value_op_iterator</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a5d1730a173d0a69624b80e1e22e6d225">value_op_end</a> ()</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/iterator-range">iterator_range</a>&lt; <a href="/web-llvm/docs/api/structs/llvm/user/value-op-iterator">value_op_iterator</a> &gt;</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ae9c77e5d2298423b0699e93642d17f0c">operand_values</a> ()</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/structs/llvm/user/const-value-op-iterator">const_value_op_iterator</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a7018c8ee154176141c4c5c055bd341c6">value_op_begin</a> () const</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/structs/llvm/user/const-value-op-iterator">const_value_op_iterator</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#af4e94f12cf6145d21c3acc13c4f557ab">value_op_end</a> () const</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/iterator-range">iterator_range</a>&lt; <a href="/web-llvm/docs/api/structs/llvm/user/const-value-op-iterator">const_value_op_iterator</a> &gt;</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ac493cefe3e5d3113828e0720bb16b85f">operand_values</a> () const</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a48ec5fcee6d2c17c723e8e67f169f948">dropAllReferences</a> ()</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Drop all references to operands. <a href="#a48ec5fcee6d2c17c723e8e67f169f948">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">bool</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a1600c7959045cb6b6a5f5a1d427ec67e">replaceUsesOfWith</a> (Value *From, Value *To)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Replace uses of one <a href="/web-llvm/docs/api/classes/llvm/value">Value</a> with another. <a href="#a1600c7959045cb6b6a5f5a1d427ec67e">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

</table>

## Protected Member Functions Index

<table class="doxyMembersIndex">

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">void</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a1f1febd65726339f65bf604c66f908c0">allocHungoffUses</a> (unsigned N, bool IsPhi=false)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Allocate the array of Uses, followed by a pointer (with bottom bit set) to the <a href="/web-llvm/docs/api/classes/llvm/user">User</a>. <a href="#a1f1febd65726339f65bf604c66f908c0">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">void</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#af834e5d5dd096241c0bcc01c5a9c0902">growHungoffUses</a> (unsigned N, bool IsPhi=false)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Grow the number of hung off uses. <a href="#af834e5d5dd096241c0bcc01c5a9c0902">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexTemplate">
<td class="doxyMemberIndexTemplate" colspan="2"><div>template &lt;int Idx&gt;</div></td>
</tr>
<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemTypeTemplate" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/use">Use</a> &amp;</td>
<td class="doxyMemberIndexItemNameTemplate" align="left" valign="top"><a href="#a72f80871b9f46788c255158fbab96879">Op</a> ()</td>
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
<td class="doxyMemberIndexTemplate" colspan="2"><div>template &lt;int Idx&gt;</div></td>
</tr>
<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemTypeTemplate" align="left" valign="top"><a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/use">Use</a> &amp;</td>
<td class="doxyMemberIndexItemNameTemplate" align="left" valign="top"><a href="#acba04f54d37b4a11c622d3772236b7cb">Op</a> () const</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/use">Use</a> *</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#aff3a029b436bf45c9631851afa28f1b3">getHungOffOperands</a> () const</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/use">Use</a> *&amp;</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a19c9b2f405fca7f9dfc92a239343ecf0">getHungOffOperands</a> ()</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/use">Use</a> *</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a5fc05778d9aaaf953b05b85937524388">getIntrusiveOperands</a> () const</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/use">Use</a> *</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a3eae5b927e52ad4138bcef4c36ea785c">getIntrusiveOperands</a> ()</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ab1577cd2fe7c3aad5f9213fa5614e808">setOperandList</a> (Use *NewList)</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a8fc5e85e2959f635fbb7492697aec86e">classof</a> (const Value *V)</td>
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

## Protected Static Functions Index

<table class="doxyMembersIndex">

<tr class="doxyMemberIndexTemplate">
<td class="doxyMemberIndexTemplate" colspan="2"><div>template &lt;int Idx, typename U&gt;</div></td>
</tr>
<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemTypeTemplate" align="left" valign="top">static <a href="/web-llvm/docs/api/classes/llvm/use">Use</a> &amp;</td>
<td class="doxyMemberIndexItemNameTemplate" align="left" valign="top"><a href="#a9f3fe741b6c50ae123d7452a2222e271">OpFrom</a> (const U *that)</td>
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

## Private Static Functions Index

<table class="doxyMembersIndex">

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">static <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/support/compiler-h/#a338bdf98e9e600f582b7bef274bc9388">LLVM_ATTRIBUTE_ALWAYS_INLINE</a> void *</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#af3ac6e51c02a43008441858af1a9e405">allocateFixedOperandUser</a> (size_t, unsigned, unsigned)</td>
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


<p>Definition at line 44 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/ir/user-h">User.h</a>.</p>


<div class="doxySectionDef">

## Public Member Typedefs

### const\_op\_iterator {#a670a0fc44293ba68935a3cff3b871893}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">using llvm::User::const_op_iterator =  const Use*</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 276 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/ir/user-h">User.h</a>.</p>

</div>
</div>

### const\_op\_range {#a00c91d41d6da00a839684a27eff9b717}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">using llvm::User::const_op_range =  iterator_range&lt;const_op_iterator&gt;</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 278 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/ir/user-h">User.h</a>.</p>

</div>
</div>

### op\_iterator {#a0126e6f10273e8db07142833979a0c8f}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">using llvm::User::op_iterator =  Use*</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 275 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/ir/user-h">User.h</a>.</p>

</div>
</div>

### op\_range {#a917548288129e24325af275795e4622f}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">using llvm::User::op_range =  iterator_range&lt;op_iterator&gt;</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 277 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/ir/user-h">User.h</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Friends

### ConstantAggrKeyType {#ad772de3fed881a64ad7437da1599cf19}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">friend struct <a href="/web-llvm/docs/api/structs/llvm/constantaggrkeytype">ConstantAggrKeyType</a></td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">


<p>Definition at line 46 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/ir/user-h">User.h</a>.</p>


<p>References <a href="#ad772de3fed881a64ad7437da1599cf19">ConstantAggrKeyType</a> and <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/support/compiler-h/#a338bdf98e9e600f582b7bef274bc9388">LLVM_ATTRIBUTE_ALWAYS_INLINE</a>.</p>


<p>Referenced by <a href="#ad772de3fed881a64ad7437da1599cf19">ConstantAggrKeyType</a>.</p>

</div>
</div>

### HungoffOperandTraits {#a5fe79114a3ec7954798970ab57ad954a}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">friend struct <a href="/web-llvm/docs/api/structs/llvm/hungoffoperandtraits">HungoffOperandTraits</a></td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">


<p>Definition at line 45 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/ir/user-h">User.h</a>.</p>


<p>Reference <a href="#a5fe79114a3ec7954798970ab57ad954a">HungoffOperandTraits</a>.</p>


<p>Referenced by <a href="#a5fe79114a3ec7954798970ab57ad954a">HungoffOperandTraits</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Public Constructors

### User() {#abcc26789f64ec564961893b4ddba5c24}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">llvm::User::User (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/user">User</a> &amp;)</td>
</tr>
</table>
</td>
<td class="doxyMemberLabelsRight">
<span class="doxyMemberLabels">
<span class="doxyMemberLabel delete">delete</span>
</span>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 143 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/ir/user-h">User.h</a>.</p>


<p>Reference <a href="#a282fa3e9586425313e0a954c18deee15">User</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Protected Constructors

### User() {#a282fa3e9586425313e0a954c18deee15}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">llvm::User::User (<a href="/web-llvm/docs/api/classes/llvm/type">Type</a> * ty, unsigned vty, <a href="/web-llvm/docs/api/structs/llvm/user/allocinfo">AllocInfo</a> AllocInfo)</td>
</tr>
</table>
</td>
<td class="doxyMemberLabelsRight">
<span class="doxyMemberLabels">
<span class="doxyMemberLabel inline">inline</span>
<span class="doxyMemberLabel protected">protected</span>
</span>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 115 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/ir/user-h">User.h</a>.</p>


<p>References <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/silowercontrolflow-cpp/#a4868c5d81c5ccc98c47aeab6244346a0">assert</a>, <a href="#a024c7e10ce431a93ffdb4e5e6401e0be">getOperandList</a>, <a href="/web-llvm/docs/api/structs/llvm/user/allocinfo/#a17a7288e5138b931c742e91d4b5ba8dc">llvm::User::AllocInfo::HasDescriptor</a>, <a href="/web-llvm/docs/api/classes/llvm/value/#ae534948f447c9e41a6890b01a8c13f0a">llvm::Value::HasDescriptor</a>, <a href="/web-llvm/docs/api/structs/llvm/user/allocinfo/#ac6da98c660d7d472a7342c2354d93bf2">llvm::User::AllocInfo::HasHungOffUses</a>, <a href="/web-llvm/docs/api/classes/llvm/value/#abe68086704afcf3325b6b9b14ca4b625">llvm::Value::HasHungOffUses</a>, <a href="/web-llvm/docs/api/structs/llvm/user/allocinfo/#afa9b194bef622c25f3ae7401627b451c">llvm::User::AllocInfo::NumOps</a>, <a href="/web-llvm/docs/api/classes/llvm/value/#ab9ef1cd0d25962bbb4785ae14258ed5d">llvm::Value::NumUserOperands</a>, <a href="/web-llvm/docs/api/classes/llvm/value/#a19833a77591e9d860373ab7fc4793044a6050aee72ddd23b6d91ec3f126679fec">llvm::Value::NumUserOperandsBits</a> and <a href="/web-llvm/docs/api/classes/llvm/value/#a18dbfcb332af7515599ee795cf462843">llvm::Value::Value</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/classes/llvm/constant/#a6659b3192e82624cd45d835e9178f8f7">llvm::Constant::Constant</a>, <a href="/web-llvm/docs/api/classes/llvm/deriveduser/#a88f2e1a4bb7547921039149d75b78c05">llvm::DerivedUser::DerivedUser</a>, <a href="#a6155b029eaffe271cf2a711141fbd0e3">getOperandList</a>, <a href="/web-llvm/docs/api/classes/llvm/constant/#ac63a8c5280ada17077a6aa14363348b3">llvm::Constant::isConstantUsed</a>, <a href="/web-llvm/docs/api/classes/llvm/constant/#a960620248182018e566b095f06a605df">llvm::Constant::removeDeadConstantUsers</a>, <a href="#abcc26789f64ec564961893b4ddba5c24">User</a> and <a href="/web-llvm/docs/api/classes/llvm/slpvectorizer/boupslp/#a99b79343fdc586cce804ebabf3d419e2">llvm::slpvectorizer::BoUpSLP::vectorizeTree</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Protected Destructor

### \~User() {#aa56ec414c4256c8435f4c97ec192019a}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">llvm::User::~User ()</td>
</tr>
</table>
</td>
<td class="doxyMemberLabelsRight">
<span class="doxyMemberLabels">
<span class="doxyMemberLabel protected">protected</span>
<span class="doxyMemberLabel default">default</span>
</span>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 140 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/ir/user-h">User.h</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Public Operators

### operator delete() {#a96c162b315ccc10487a1359cb15f8c98}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">LLVM_NO_SANITIZE_MEMORY_ATTRIBUTE void llvm::User::operator delete (void * Usr)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Free memory allocated for <a href="/web-llvm/docs/api/classes/llvm/user">User</a> and <a href="/web-llvm/docs/api/classes/llvm/use">Use</a> objects.</p>

<p>Declaration at line 146 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/ir/user-h">User.h</a>, definition at line 191 of file <a href="/web-llvm/docs/api/files/lib/lib/sandboxir/user-cpp">User.cpp</a>.</p>

</div>
</div>

### operator delete() {#a247006d94472c8d80b5cf143a9c5a2b9}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void llvm::User::operator delete (void * Usr, <a href="/web-llvm/docs/api/structs/llvm/user/hungoffoperandsallocmarker">HungOffOperandsAllocMarker</a>)</td>
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

<p>Placement delete - required by std, called if the ctor throws.</p>

<p>Definition at line 148 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/ir/user-h">User.h</a>.</p>


<p>Reference <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/support/errorhandling-h/#ace243f5c25697a1107cce46626b3dc94">llvm_unreachable</a>.</p>

</div>
</div>

### operator delete() {#a3ba87e798a0df56e983d393e0a1abc1a}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void llvm::User::operator delete (void * Usr, <a href="/web-llvm/docs/api/structs/llvm/user/intrusiveoperandsallocmarker">IntrusiveOperandsAllocMarker</a>)</td>
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

<p>Placement delete - required by std, called if the ctor throws.</p>

<p>Definition at line 161 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/ir/user-h">User.h</a>.</p>


<p>Reference <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/support/errorhandling-h/#ace243f5c25697a1107cce46626b3dc94">llvm_unreachable</a>.</p>

</div>
</div>

### operator delete() {#acb6e60cad24aed54fa19ce71074c7ecb}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void llvm::User::operator delete (void * Usr, <a href="/web-llvm/docs/api/structs/llvm/user/intrusiveoperandsanddescriptorallocmarker">IntrusiveOperandsAndDescriptorAllocMarker</a>)</td>
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

<p>Placement delete - required by std, called if the ctor throws.</p>

<p>Definition at line 173 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/ir/user-h">User.h</a>.</p>


<p>Reference <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/support/errorhandling-h/#ace243f5c25697a1107cce46626b3dc94">llvm_unreachable</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Protected Operators

### operator new() {#a6fe0552bc8842bffe58e1d7873346f7b}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void * llvm::User::operator new (size_t Size)</td>
</tr>
</table>
</td>
<td class="doxyMemberLabelsRight">
<span class="doxyMemberLabels">
<span class="doxyMemberLabel protected">protected</span>
<span class="doxyMemberLabel delete">delete</span>
</span>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 54 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/ir/user-h">User.h</a>.</p>


<p>Reference <a href="/web-llvm/docs/api/files/lib/lib/analysis/inlineorder-cpp/#a7ee6f0cb51c3b9056199e9a0001fe8c3a6f6cb72d544962fa333e2e34ce64f719">Size</a>.</p>

</div>
</div>

### operator new() {#ad379730885bf082d40fd8aa4af1e553d}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void * llvm::User::operator new (size_t Size, <a href="/web-llvm/docs/api/structs/llvm/user/hungoffoperandsallocmarker">HungOffOperandsAllocMarker</a>)</td>
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

<p>Allocate a <a href="/web-llvm/docs/api/classes/llvm/user">User</a> with an operand pointer co-allocated.</p>


<p>This is used for subclasses which need to allocate a variable number of operands, ie, 'hung off uses'.</p>


<p>Declaration at line 102 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/ir/user-h">User.h</a>, definition at line 173 of file <a href="/web-llvm/docs/api/files/lib/lib/sandboxir/user-cpp">User.cpp</a>.</p>

</div>
</div>

### operator new() {#a1324a54e2b6221c9dc2e74725a3570c1}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void * llvm::User::operator new (size_t Size, <a href="/web-llvm/docs/api/structs/llvm/user/intrusiveoperandsallocmarker">IntrusiveOperandsAllocMarker</a> allocTrait)</td>
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

<p>Allocate a <a href="/web-llvm/docs/api/classes/llvm/user">User</a> with the operands co-allocated.</p>


<p>This is used for subclasses which have a fixed number of operands.</p>


<p>Declaration at line 107 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/ir/user-h">User.h</a>, definition at line 163 of file <a href="/web-llvm/docs/api/files/lib/lib/sandboxir/user-cpp">User.cpp</a>.</p>

</div>
</div>

### operator new() {#aee898f8818ca582daae5d35eaf92f4cf}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void * llvm::User::operator new (size_t Size, <a href="/web-llvm/docs/api/structs/llvm/user/intrusiveoperandsanddescriptorallocmarker">IntrusiveOperandsAndDescriptorAllocMarker</a> allocTrait)</td>
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

<p>Allocate a <a href="/web-llvm/docs/api/classes/llvm/user">User</a> with the operands co-allocated.</p>


<p>If DescBytes is non-zero then allocate an additional DescBytes bytes before the operands. These bytes can be accessed by calling getDescriptor.</p>


<p>Declaration at line 112 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/ir/user-h">User.h</a>, definition at line 167 of file <a href="/web-llvm/docs/api/files/lib/lib/sandboxir/user-cpp">User.cpp</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Public Member Functions

### dropAllReferences() {#a48ec5fcee6d2c17c723e8e67f169f948}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void llvm::User::dropAllReferences ()</td>
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

<p>Drop all references to operands.</p>


<p>This function is in charge of "letting go" of all objects that this <a href="/web-llvm/docs/api/classes/llvm/user">User</a> refers to. This allows one to 'delete' a whole class at a time, even though there may be circular references... First all references are dropped, and all use counts go to zero. Then everything is deleted for real. Note that no operations are valid on an object that has "dropped
all references", except operator delete.</p>


<p>Definition at line 345 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/ir/user-h">User.h</a>.</p>


<p>Reference <a href="#a0b931781aa589c6ebe64a76c1447e5b2">operands</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/classes/llvm/globalvariable/#af99541657316d3a761845dc5b8d845d9">llvm::GlobalVariable::dropAllReferences</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a08d3e8ce57fb65481a42b256d26c264d">llvm::expandDivision</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a83cfb58d48c02daaaa8ee7e924e9fb36">llvm::expandDivisionUpTo32Bits</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a6c6db1ba2b3654c01ec2363b2bc34ce4">llvm::expandDivisionUpTo64Bits</a>, <a href="/web-llvm/docs/api/files/lib/lib/codegen/expandlargefpconvert-cpp/#a46482b2bd77de78d901bfa2fd727ba0e">expandFPToI</a>, <a href="/web-llvm/docs/api/files/lib/lib/codegen/expandlargefpconvert-cpp/#a0f218e3451638c34910744dedf0b71ac">expandIToFP</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#ad0154d60f04a5d8549b44635852557f0">llvm::expandRemainder</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a090725add53936fcebc89f58fc9a7da1">llvm::expandRemainderUpTo32Bits</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a27da54a97fcba955457048148b1fef99">llvm::expandRemainderUpTo64Bits</a>, <a href="/web-llvm/docs/api/classes/llvm/memoryssaupdater/#aa0c15073f16693ebc44c2410986cacec">llvm::MemorySSAUpdater::removeBlocks</a>, <a href="/web-llvm/docs/api/files/lib/lib/codegen/expandlargedivrem-cpp/#a5c0f04dd919f2fa52e52f277a68b1ac1">scalarize</a> and <a href="/web-llvm/docs/api/classes/llvm/memoryssa/#ae7375c161ecaf6b6f4ebd6abfcb5ce71">llvm::MemorySSA::~MemorySSA</a>.</p>

</div>
</div>

### getDescriptor() {#a0d4a83cd78f12aa1ab452c4d94b9cb7b}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">ArrayRef&lt; const uint8_t &gt; llvm::User::getDescriptor ()</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Returns the descriptor co-allocated with this <a href="/web-llvm/docs/api/classes/llvm/user">User</a> instance.</p>

<p>Declaration at line 253 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/ir/user-h">User.h</a>, definition at line 99 of file <a href="/web-llvm/docs/api/files/lib/lib/sandboxir/user-cpp">User.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/classes/llvm/use/#ad77c21b5dd2c8765f87e3fb054d68def">llvm::Use::get</a>, <a href="/web-llvm/docs/api/classes/llvm/sandboxir/user/#ac600a3ffce54e05ca28e586af7a04831">llvm::sandboxir::User::getNumOperands</a>, <a href="/web-llvm/docs/api/classes/llvm/sandboxir/user/#acb9166dd8e540f8c9e6efad7e9cccba0">llvm::sandboxir::User::getOperandUse</a> and <a href="/web-llvm/docs/api/namespaces/llvm/#adc4eb8be6f7a12ede962987fb9cabb47">llvm::seq</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/classes/llvm/callbase/#a09fff26473ca9a3d9d1ff51633e048c1">llvm::CallBase::bundle_op_info_begin</a> and <a href="/web-llvm/docs/api/classes/llvm/callbase/#a418564b6605d97c81db3dc3ddc4cb948">llvm::CallBase::bundle_op_info_end</a>.</p>

</div>
</div>

### getDescriptor() {#a068b54eba6b02473bb14f3b13b85d086}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">MutableArrayRef&lt; uint8_t &gt; llvm::User::getDescriptor ()</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Returns the descriptor co-allocated with this <a href="/web-llvm/docs/api/classes/llvm/user">User</a> instance.</p>

<p>Declaration at line 256 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/ir/user-h">User.h</a>, definition at line 104 of file <a href="/web-llvm/docs/api/files/lib/lib/sandboxir/user-cpp">User.cpp</a>.</p>

</div>
</div>

### getNumOperands() {#addec638786f763d967811b45cb662f1f}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">unsigned llvm::User::getNumOperands ()</td>
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



<p>Definition at line 250 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/ir/user-h">User.h</a>.</p>


<p>Reference <a href="/web-llvm/docs/api/classes/llvm/value/#ab9ef1cd0d25962bbb4785ae14258ed5d">llvm::Value::NumUserOperands</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/classes/llvm/switchinst/#a62abc2475d09c01d583ba24a487898fd">llvm::SwitchInst::addCase</a>, <a href="/web-llvm/docs/api/classes/llvm/landingpadinst/#a3a936522e13d33927dc23f0488e421d8">llvm::LandingPadInst::addClause</a>, <a href="/web-llvm/docs/api/classes/llvm/indirectbrinst/#a08b418bd465a9f2ff316beb04005f6d7">llvm::IndirectBrInst::addDestination</a>, <a href="/web-llvm/docs/api/classes/llvm/catchswitchinst/#a4b1438bbee79540a0cca9a2c018b71ec">llvm::CatchSwitchInst::addHandler</a>, <a href="/web-llvm/docs/api/classes/llvm/memoryphi/#ab9945ed381faa9dbee65a92e6225768d">llvm::MemoryPhi::addIncoming</a>, <a href="/web-llvm/docs/api/classes/llvm/phinode/#a089cccb6f231efee72abc76d0f9c695f">llvm::PHINode::addIncoming</a>, <a href="/web-llvm/docs/api/classes/llvm/funcletpadinst/#a73ad527c13c3bb6367aa1f507d28ac3e">llvm::FuncletPadInst::arg_size</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/directx/dxiloplowering-cpp/#a4ec8ddbebba100a1e902badbdb4b3f0a">argVectorFlatten</a>, <a href="/web-llvm/docs/api/classes/llvm/memoryphi/#a25e282709502b83ff4420255c43c233c">llvm::MemoryPhi::block_end</a>, <a href="/web-llvm/docs/api/classes/llvm/memoryphi/#a142301ebfda0d3036fd6758c7760e8dd">llvm::MemoryPhi::block_end</a>, <a href="/web-llvm/docs/api/classes/llvm/phinode/#aaf337eae2193217943c7c0d7a65e61bb">llvm::PHINode::block_end</a>, <a href="/web-llvm/docs/api/structs/anonymous-attributorattributes-cpp-/aavalueconstantrangefloating/#a9fe92d5d425b0ddab77a3bd58e734a74">anonymous{AttributorAttributes.cpp}::AAValueConstantRangeFloating::calculateCastInst</a>, <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/instcombine/instcombineloadstorealloca-cpp/#a4380ad0de0940297354df2effeb021ad">canReplaceGEPIdxWithZero</a>, <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/utils/simplifycfg-cpp/#ae9efb27478c86bece81f1bf5bca2d348">canSinkInstructions</a>, <a href="/web-llvm/docs/api/classes/llvm/branchinst/#a6caa25d916f318fa81a44bdbbf51fcd4">llvm::BranchInst::cloneImpl</a>, <a href="/web-llvm/docs/api/classes/llvm/callbrinst/#ad9c2018082a0bb908947e363733b3c25">llvm::CallBrInst::cloneImpl</a>, <a href="/web-llvm/docs/api/classes/llvm/callinst/#a9e52b82293f11aed8b26862a02fc3f54">llvm::CallInst::cloneImpl</a>, <a href="/web-llvm/docs/api/classes/llvm/cleanupreturninst/#ad9f0c9392c79ff966962d43498213ff8">llvm::CleanupReturnInst::cloneImpl</a>, <a href="/web-llvm/docs/api/classes/llvm/funcletpadinst/#ac4b0c9384c92dc6a7a4d9ceed9bb1da5">llvm::FuncletPadInst::cloneImpl</a>, <a href="/web-llvm/docs/api/classes/llvm/getelementptrinst/#ad52a138f2146bcccf15ae6c2c8ba8ba9">llvm::GetElementPtrInst::cloneImpl</a>, <a href="/web-llvm/docs/api/classes/llvm/invokeinst/#a307d5a58d01ab9dd06f2e3acc2ac1437">llvm::InvokeInst::cloneImpl</a>, <a href="/web-llvm/docs/api/classes/llvm/returninst/#a9db09777dd13dcc023b038b5265f754e">llvm::ReturnInst::cloneImpl</a>, <a href="/web-llvm/docs/api/structs/anonymous-clonefunction-cpp-/pruningfunctioncloner/#afbf9fd3d3729664031c88766bcefcdf0">anonymous{CloneFunction.cpp}::PruningFunctionCloner::cloneInstruction</a>, <a href="/web-llvm/docs/api/classes/llvm/functioncomparator/#aecc5ef45f49070634ddd53a04ed5548e">llvm::FunctionComparator::cmpConstants</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/arm/armisellowering-cpp/#aa4c17cc7964441daaea8b4bee6c18f93">CombineBaseUpdate</a>, <a href="/web-llvm/docs/api/structs/anonymous-dataflowsanitizer-cpp-/dfsanfunction/#a609c78a9c329baf4d3aa095a80784a4c">anonymous{DataFlowSanitizer.cpp}::DFSanFunction::combineOperandOrigins</a>, <a href="/web-llvm/docs/api/structs/anonymous-dataflowsanitizer-cpp-/dfsanfunction/#ad7d79bd0b027705195d79619a1d0450a">anonymous{DataFlowSanitizer.cpp}::DFSanFunction::combineOperandShadows</a>, <a href="/web-llvm/docs/api/namespaces/anonymous-nvptxctordtorlowering-cpp-/#aab0bb9923065afc9aca06aec133ff91e">anonymous{NVPTXCtorDtorLowering.cpp}::createInitOrFiniGlobals</a>, <a href="/web-llvm/docs/api/namespaces/anonymous-amdgpuctordtorlowering-cpp-/#a0d730fa8562179d7bcfc965fe37dfbd7">anonymous{AMDGPUCtorDtorLowering.cpp}::createInitOrFiniKernel</a>, <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/scalar/loopidiomrecognize-cpp/#a3a0cafd820690b73a6169ab519d77d2a">detectShiftUntilLessThanIdiom</a>, <a href="/web-llvm/docs/api/files/lib/lib/codegen/lib/codegen/asmprinter/asmprinter-cpp/#af7fb6d7d97dc4e12a6ac3a9efebcd71a">emitGlobalConstantArray</a>, <a href="/web-llvm/docs/api/files/lib/lib/codegen/lib/codegen/asmprinter/asmprinter-cpp/#a9ec5fb3e521efb1fdb547aa3c3c43c75">emitGlobalConstantStruct</a>, <a href="/web-llvm/docs/api/classes/llvm/evaluator/#aac9fd94c18d93885c8d947121ab9721e">llvm::Evaluator::EvaluateFunction</a>, <a href="/web-llvm/docs/api/structs/anonymous-expandvectorpredication-cpp-/cachingvpexpander/#a62f9944dba24143c8954964d7dff45b8">anonymous{ExpandVectorPredication.cpp}::CachingVPExpander::expandPredicationToFPCall</a>, <a href="/web-llvm/docs/api/structs/anonymous-expandvectorpredication-cpp-/cachingvpexpander/#ad2529fdcdfd78c5eccd6079fc3c74ad3">anonymous{ExpandVectorPredication.cpp}::CachingVPExpander::expandPredicationToIntCall</a>, <a href="/web-llvm/docs/api/classes/llvm/aarch64targetlowering/#a790e9b70f12899a4cb2aefd33826ee7d">llvm::AArch64TargetLowering::fallBackToDAGISel</a>, <a href="/web-llvm/docs/api/classes/llvm/riscvtargetlowering/#a6914b95d1fcf7a5aca24fe82bf4100c2">llvm::RISCVTargetLowering::fallBackToDAGISel</a>, <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/ipo/constantmerge-cpp/#a8c82bb68e32af4477888125c41741a7f">FindUsedValues</a>, <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/ipo/stripsymbols-cpp/#a348eede5b05a57edfafe7f8595cced8b">findUsedValues</a>, <a href="/web-llvm/docs/api/classes/llvm/instcombinerimpl/#afc78cb7aeb92b0fc9223239dd827f7e3">llvm::InstCombinerImpl::foldGEPICmp</a>, <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/instcombine/instructioncombining-cpp/#ad12cb02e2ee53655e834dcb84cd57333">foldGEPOfPhi</a>, <a href="/web-llvm/docs/api/classes/llvm/instcombinerimpl/#acc9feb478a72bb822133b6eec00bef9f">llvm::InstCombinerImpl::foldPHIArgGEPIntoPHI</a>, <a href="/web-llvm/docs/api/classes/llvm/instcombinerimpl/#a4bd29d381405675f36964e4a5382dae4">llvm::InstCombinerImpl::foldSelectOpOp</a>, <a href="/web-llvm/docs/api/classes/llvm/dbgassignintrinsic/#ab13971dbdc6d1c069f75e59f337fa078">llvm::DbgAssignIntrinsic::getAddress</a>, <a href="/web-llvm/docs/api/classes/llvm/constantexpr/#af9fc0080b4accc0b19bfbbc624701e30">llvm::ConstantExpr::getAsInstruction</a>, <a href="/web-llvm/docs/api/classes/llvm/memoryphi/#aea0bb94cc4c6ee8016dc150efd4753c1">llvm::MemoryPhi::getBasicBlockIndex</a>, <a href="/web-llvm/docs/api/classes/llvm/phinode/#ae9562b96f6f3fa41bd36538c080035ee">llvm::PHINode::getBasicBlockIndex</a>, <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/scalar/lowerexpectintrinsic-cpp/#a4c4c33f562e18b287ca4ca5b0e0eedc7">getBranchWeight</a>, <a href="/web-llvm/docs/api/files/lib/lib/analysis/loopaccessanalysis-cpp/#a5fe252ea76c22a7e9bed5af0446d4fdb">getGEPInductionOperand</a>, <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/scalar/indvarsimplify-cpp/#ab8fbf8890afc93e88d19a28877c13fad">getLoopPhiForCounter</a>, <a href="/web-llvm/docs/api/classes/llvm/systemzttiimpl/#a97ebd00c769b1d7c67f7db4b58137c93">llvm::SystemZTTIImpl::getMemoryOpCost</a>, <a href="/web-llvm/docs/api/classes/llvm/switchinst/#ab009e4ea0d53969a9f6fb36e3da14517">llvm::SwitchInst::getNumCases</a>, <a href="/web-llvm/docs/api/classes/llvm/landingpadinst/#a1d25e478c9de2656ce4c793a8b80e537">llvm::LandingPadInst::getNumClauses</a>, <a href="/web-llvm/docs/api/classes/llvm/indirectbrinst/#abd4f6893d4f810f4162a70f89b2452fe">llvm::IndirectBrInst::getNumDestinations</a>, <a href="/web-llvm/docs/api/classes/llvm/catchswitchinst/#a60def7b50a06b2005b76a821a076756d">llvm::CatchSwitchInst::getNumHandlers</a>, <a href="/web-llvm/docs/api/classes/llvm/memoryphi/#a1c403c86f16af563cec6961666e8cc2e">llvm::MemoryPhi::getNumIncomingValues</a>, <a href="/web-llvm/docs/api/classes/llvm/phinode/#aef51af4b490af6b3bf2dfbc8737a8f9f">llvm::PHINode::getNumIncomingValues</a>, <a href="/web-llvm/docs/api/classes/llvm/gepoperator/#a43f7ebb9a6f2819acad2ea4085b8ee4d">llvm::GEPOperator::getNumIndices</a>, <a href="/web-llvm/docs/api/classes/llvm/getelementptrinst/#ae1d9fcb64e19da7f15dc5117dd51aa03">llvm::GetElementPtrInst::getNumIndices</a>, <a href="/web-llvm/docs/api/classes/llvm/catchswitchinst/#a2a4db441570ddfd542e5303b22b065c4">llvm::CatchSwitchInst::getNumSuccessors</a>, <a href="/web-llvm/docs/api/classes/llvm/indirectbrinst/#ae80f6ab761f1b6434fa8da984bfea4b5">llvm::IndirectBrInst::getNumSuccessors</a>, <a href="/web-llvm/docs/api/classes/llvm/switchinst/#a90d8c814f871c58dbda5dccce5c4110e">llvm::SwitchInst::getNumSuccessors</a>, <a href="/web-llvm/docs/api/classes/llvm/returninst/#a6c2dee0852138a5cb8a4fef5883db9ec">llvm::ReturnInst::getReturnValue</a>, <a href="/web-llvm/docs/api/classes/llvm/constantvector/#aa2ea20974430e8820f962083ca421c05">llvm::ConstantVector::getSplatValue</a>, <a href="/web-llvm/docs/api/classes/llvm/constantexpr/#aab577cba8223fe4bb96df5591d49d98a">llvm::ConstantExpr::getWithOperands</a>, <a href="/web-llvm/docs/api/classes/llvm/getelementptrinst/#a47fef2802996b78f0530c9b77abca9ed">llvm::GetElementPtrInst::hasAllConstantIndices</a>, <a href="/web-llvm/docs/api/classes/llvm/getelementptrinst/#a0a9d2347ed3426150ef852d09dbcbaf2">llvm::GetElementPtrInst::hasAllZeroIndices</a>, <a href="/web-llvm/docs/api/classes/llvm/gepoperator/#ab52b529f03851cdc98af7aa85382ee93">llvm::GEPOperator::hasIndices</a>, <a href="/web-llvm/docs/api/classes/llvm/getelementptrinst/#ae3912ec2e54cd2f00754ea725f147371">llvm::GetElementPtrInst::hasIndices</a>, <a href="/web-llvm/docs/api/classes/llvm/branchinst/#a7e4be8b16fbd68c9045a388904044e01">llvm::BranchInst::isConditional</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/nvptx/nvptxasmprinter-cpp/#a044419a3533ccf34b2d18b641dc053d2">isEmptyXXStructor</a>, <a href="/web-llvm/docs/api/structs/anonymous-attributorattributes-cpp-/aanoaliascallsiteargument/#a0a41d500fe5dcf2f575b99316d25ec30">anonymous{AttributorAttributes.cpp}::AANoAliasCallSiteArgument::isKnownNoAliasDueToNoAliasPreservation</a>, <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/scalar/licm-cpp/#a0581d6d5dc280ba2a39087a557050a6a">isNotUsedOrFoldableInLoop</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a5e36553611d3def8cf698c722239718f">llvm::isSafeToSpeculativelyExecuteWithOpcode</a>, <a href="/web-llvm/docs/api/classes/llvm/branchinst/#ad56f6a9b5cd05940017c4544df48bc30">llvm::BranchInst::isUnconditional</a>, <a href="/web-llvm/docs/api/structs/llvm/variadicoperandtraits/#a57416fa14ce5900d2f8fd39cdc407b8e">llvm::VariadicOperandTraits&lt; SubClass &gt;::op_begin</a>, <a href="/web-llvm/docs/api/classes/llvm/orc/ctordtoriterator/#a760366cc3bd5fb351f3ea815d7f08346">llvm::orc::CtorDtorIterator::operator*</a>, <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/utils/ctorutils-cpp/#a30e49f13bd17ed097579ddf598241386">parseGlobalCtors</a>, <a href="/web-llvm/docs/api/classes/llvm/ppctargetlowering/#ab4ccdcee4c7a2e0892715d0a8094b86e">llvm::PPCTargetLowering::PerformDAGCombine</a>, <a href="/web-llvm/docs/api/classes/llvm/switchinst/#aff8bc09200ccc3617a5cb37e0d2f23ff">llvm::SwitchInst::removeCase</a>, <a href="/web-llvm/docs/api/classes/llvm/indirectbrinst/#ac0cc9b34e16910d245245642350d4456">llvm::IndirectBrInst::removeDestination</a>, <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/utils/ctorutils-cpp/#a26771a5b06ef10e47546922cc377044b">removeGlobalCtors</a>, <a href="/web-llvm/docs/api/classes/llvm/catchswitchinst/#aea4f52695ae91c16ae1269f91caf4d5f">llvm::CatchSwitchInst::removeHandler</a>, <a href="/web-llvm/docs/api/classes/llvm/phinode/#a6f01dbe965b38186b1a78378689d4105">llvm::PHINode::removeIncomingValue</a>, <a href="/web-llvm/docs/api/classes/llvm/phinode/#a5197ef3eec835595e81bcecb4ee02969">llvm::PHINode::removeIncomingValueIf</a>, <a href="/web-llvm/docs/api/namespaces/anonymous-loadstorevectorizer-cpp-/#ae31219d422e76099c3c5dfaa2c7171cb">anonymous{LoadStoreVectorizer.cpp}::reorder</a>, <a href="/web-llvm/docs/api/classes/llvm/phinode/#ae6c98d2f865894d646b95e8af8176a5d">llvm::PHINode::replaceIncomingBlockWith</a>, <a href="/web-llvm/docs/api/classes/llvm/vpvalue/#ae3773dd8f9c831f0dde091319b2ff7d0">llvm::VPValue::replaceUsesWithIf</a>, <a href="/web-llvm/docs/api/classes/llvm/dagtypelegalizer/#a39cafb39798d9b0f3b611b9ee0fff149">llvm::DAGTypeLegalizer::run</a>, <a href="/web-llvm/docs/api/classes/llvm/executionengine/#a60823e6b4ff77b319b51c9eb634241e2">llvm::ExecutionEngine::runStaticConstructorsDestructors</a>, <a href="/web-llvm/docs/api/classes/llvm/phinode/#a506bcfb6f92a2184453e1fa9655f62a1">llvm::PHINode::setIncomingValueForBlock</a>, <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/utils/simplifycfg-cpp/#abf69483b802f1e342399912142341c60">sinkLastInstruction</a>, <a href="/web-llvm/docs/api/classes/llvm/memoryphi/#a56d097f1cf3fce666e9c5adf3e75307d">llvm::MemoryPhi::unorderedDeleteIncoming</a>, <a href="/web-llvm/docs/api/classes/llvm/memoryphi/#a4a6dfce2c88679057e980a0f1cf58222">llvm::MemoryPhi::unorderedDeleteIncomingIf</a>, <a href="/web-llvm/docs/api/structs/anonymous-attributorattributes-cpp-/aapotentialconstantvaluesfloating/#af8fd85d6783b4f0fbb5f4a8d6bf40bdc">anonymous{AttributorAttributes.cpp}::AAPotentialConstantValuesFloating::updateWithCastInst</a>, <a href="/web-llvm/docs/api/files/lib/lib/ir/autoupgrade-cpp/#a9d9ad1173db1cee0c288f1b773baaf65">upgradeAMDGCNIntrinsicCall</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a085e92ed481e12744fdf1740b4751327">llvm::UpgradeIntrinsicCall</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/riscv/riscviseldagtodag-cpp/#aadd8c5bb4ccd3134cdde19afc01eb291">vectorPseudoHasAllNBitUsers</a>, <a href="/web-llvm/docs/api/structs/anonymous-memorysanitizer-cpp-/memorysanitizervisitor/#a27c9f05f074b1acd44859e85c1212bc1">anonymous{MemorySanitizer.cpp}::MemorySanitizerVisitor::visitAsmInstruction</a>, <a href="/web-llvm/docs/api/classes/datascalarizervisitor/#a32bd3fc6040488f54b8fb322216218a5">DataScalarizerVisitor::visitGetElementPtrInst</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/nvptx/nvptxasmprinter-cpp/#ab0cd64194576d6d882ceabaf9b3a2c29">VisitGlobalVariableForEmission</a>, <a href="/web-llvm/docs/api/classes/anonymous-dxilflattenarrays-cpp-/dxilflattenarraysvisitor/#a9498339e26b296572a463a1300bf1a13">anonymous{DXILFlattenArrays.cpp}::DXILFlattenArraysVisitor::visitLoadInst</a>, <a href="/web-llvm/docs/api/classes/datascalarizervisitor/#a7c94d0952ba1d6986f0e78b62c303074">DataScalarizerVisitor::visitLoadInst</a> and <a href="/web-llvm/docs/api/classes/anonymous-simplifyindvar-cpp-/wideniv/#acd093283d4e8d1301859f0a98a157680">anonymous{SimplifyIndVar.cpp}::WidenIV::widenWithVariantUse</a>.</p>

</div>
</div>

### getOperand() {#aa0a2cb1582d1cec317bd205085469ca1}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">Value * llvm::User::getOperand (unsigned i)</td>
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



<p>Definition at line 228 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/ir/user-h">User.h</a>.</p>


<p>References <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/silowercontrolflow-cpp/#a4868c5d81c5ccc98c47aeab6244346a0">assert</a>, <a href="#a024c7e10ce431a93ffdb4e5e6401e0be">getOperandList</a>, <a href="/web-llvm/docs/api/classes/llvm/value/#ab9ef1cd0d25962bbb4785ae14258ed5d">llvm::Value::NumUserOperands</a> and <a href="/web-llvm/docs/api/classes/llvm/value/#a18dbfcb332af7515599ee795cf462843">llvm::Value::Value</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/classes/llvm/recurrencedescriptor/#ae3b1b80ef450d6706f42f3a929e51ce5">llvm::RecurrenceDescriptor::AddReductionVar</a>, <a href="/web-llvm/docs/api/classes/llvm/lanaiinstrinfo/#a492be44ddc8ccbf85c4ef650b6111868">llvm::LanaiInstrInfo::analyzeBranch</a>, <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/utils/simplifycfg-cpp/#a47aa12b3f79390c9835ac99904b2cb51">areIdenticalUpToCommutativity</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/directx/dxiloplowering-cpp/#a4ec8ddbebba100a1e902badbdb4b3f0a">argVectorFlatten</a>, <a href="/web-llvm/docs/api/classes/llvm/canonicalloopinfo/#a32ff799dcb39887a8d21322020f305ba">llvm::CanonicalLoopInfo::assertOK</a>, <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/scalar/reassociate-cpp/#a420bedce165a865417db21cdc88307cb">BreakUpSubtract</a>, <a href="/web-llvm/docs/api/structs/anonymous-attributorattributes-cpp-/aavalueconstantrangefloating/#a9fe92d5d425b0ddab77a3bd58e734a74">anonymous{AttributorAttributes.cpp}::AAValueConstantRangeFloating::calculateCastInst</a>, <a href="/web-llvm/docs/api/structs/anonymous-attributorattributes-cpp-/aavalueconstantrangefloating/#a28797a7ad88ceb957e31f0bc5802395f">anonymous{AttributorAttributes.cpp}::AAValueConstantRangeFloating::calculateCmpInst</a>, <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/instcombine/instcombineshifts-cpp/#aaba35705ce5c614a4b4d1a6ed6e8bb57">canEvaluateShiftedShift</a>, <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/scalar/looptermfold-cpp/#a0e67dc55f94f7419d24a39fa5b79c42f">canFoldTermCondOfLoop</a>, <a href="/web-llvm/docs/api/files/lib/lib/codegen/hardwareloops-cpp/#adb6fcf2b6da127679d3169f4474e6912">CanGenerateTest</a>, <a href="/web-llvm/docs/api/structs/anonymous-dagcombiner-cpp-/loadedslice/#a3359f38a412c6b9685e8fd39bd81b6a7">anonymous{DAGCombiner.cpp}::LoadedSlice::canMergeExpensiveCrossRegisterBankCopy</a>, <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/instcombine/instcombinecasts-cpp/#a3e2793cc62829d80622b78cc681b25c2">canonicalizeBitCastExtElt</a>, <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/instcombine/instcombinevectorops-cpp/#a6e6cf92e2cfe0eb48abec55606e0481e">canonicalizeInsertSplat</a>, <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/instcombine/instcombineselect-cpp/#a3c4424f4bbcee5f3dd484c2822221812">canonicalizeSaturatedAdd</a>, <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/instcombine/instcombineselect-cpp/#a65c587ebfe84f7c55b3d2266ff0500f9">canonicalizeSaturatedSubtract</a>, <a href="/web-llvm/docs/api/files/lib/lib/analysis/phitransaddr-cpp/#a2c64eb39d5bdd73f8ac9d47338931ce8">canPHITrans</a>, <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/instcombine/instcombineloadstorealloca-cpp/#a4380ad0de0940297354df2effeb021ad">canReplaceGEPIdxWithZero</a>, <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/utils/simplifycfg-cpp/#ae9efb27478c86bece81f1bf5bca2d348">canSinkInstructions</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/riscv/riscvtargettransforminfo-cpp/#acd24a6bcdc57348f4127e25aee7cb173">canUseShiftPair</a>, <a href="/web-llvm/docs/api/files/lib/lib/codegen/lib/codegen/selectiondag/scheduledagsdnodes-cpp/#a7d574da13bc65b93810a42059eada04f">CheckForPhysRegDependency</a>, <a href="/web-llvm/docs/api/classes/llvm/sitargetlowering/#a0e8adf21ba4a3e746edcd3b9cf9c5d14">llvm::SITargetLowering::checkForPhysRegDependency</a>, <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/vectorize/loadstorevectorizer-cpp/#ac79b06c4793c56d8155eb7c18aafa1d3">checkIfSafeAddSequence</a>, <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/scalar/constraintelimination-cpp/#ab230432af09554d7dd357c77b0ec3cde">checkOrAndOpImpliedByOther</a>, <a href="/web-llvm/docs/api/classes/anonymous-simplifyindvar-cpp-/wideniv/#aee57a451f8dea6781fa17e7728ee78b5">anonymous{SimplifyIndVar.cpp}::WidenIV::cloneArithmeticIVUser</a>, <a href="/web-llvm/docs/api/classes/anonymous-simplifyindvar-cpp-/wideniv/#ae5441d4cfeb857eb3f3afad58fd88c08">anonymous{SimplifyIndVar.cpp}::WidenIV::cloneBitwiseIVUser</a>, <a href="/web-llvm/docs/api/classes/llvm/addrspacecastinst/#a420b662320c3ba54d9560ad49c30caf0">llvm::AddrSpaceCastInst::cloneImpl</a>, <a href="/web-llvm/docs/api/classes/llvm/allocainst/#a6a2dc8251ccd285b55edc3019e3a42bd">llvm::AllocaInst::cloneImpl</a>, <a href="/web-llvm/docs/api/classes/llvm/atomiccmpxchginst/#a81e03125e154267cfae6d229fb39979b">llvm::AtomicCmpXchgInst::cloneImpl</a>, <a href="/web-llvm/docs/api/classes/llvm/atomicrmwinst/#a25a1f4bf68a202e553b2f4e227fb5eea">llvm::AtomicRMWInst::cloneImpl</a>, <a href="/web-llvm/docs/api/classes/llvm/bitcastinst/#ad5ec02209a56c591743ec4305e386a61">llvm::BitCastInst::cloneImpl</a>, <a href="/web-llvm/docs/api/classes/llvm/extractelementinst/#a1290667f7caecbc49dcf22c026300b94">llvm::ExtractElementInst::cloneImpl</a>, <a href="/web-llvm/docs/api/classes/llvm/fpextinst/#a8190171a29cd1785d483398540a7780b">llvm::FPExtInst::cloneImpl</a>, <a href="/web-llvm/docs/api/classes/llvm/fptosiinst/#a9d32ae6d5354d203c018765133684ef7">llvm::FPToSIInst::cloneImpl</a>, <a href="/web-llvm/docs/api/classes/llvm/fptouiinst/#ab4e319070c915544d080418cc7a5bf3d">llvm::FPToUIInst::cloneImpl</a>, <a href="/web-llvm/docs/api/classes/llvm/fptruncinst/#aa430e04b2876ce2df6e2645f47529f5f">llvm::FPTruncInst::cloneImpl</a>, <a href="/web-llvm/docs/api/classes/llvm/freezeinst/#aa6dc871e42f824ca36ddd54fbffda466">llvm::FreezeInst::cloneImpl</a>, <a href="/web-llvm/docs/api/classes/llvm/insertelementinst/#a1a447df416de02482b8b4b2d6220eb54">llvm::InsertElementInst::cloneImpl</a>, <a href="/web-llvm/docs/api/classes/llvm/inttoptrinst/#a5f59d3a0dab4262848e614ae0b73f37a">llvm::IntToPtrInst::cloneImpl</a>, <a href="/web-llvm/docs/api/classes/llvm/loadinst/#a8195fc57735a947a24bc9abee4a9c4d5">llvm::LoadInst::cloneImpl</a>, <a href="/web-llvm/docs/api/classes/llvm/ptrtointinst/#aea9834ebaa7797545bf6d263a66e9d2b">llvm::PtrToIntInst::cloneImpl</a>, <a href="/web-llvm/docs/api/classes/llvm/selectinst/#a79aeabf6f06fb0f75a2f37d4a10d165f">llvm::SelectInst::cloneImpl</a>, <a href="/web-llvm/docs/api/classes/llvm/sextinst/#ae1a62d40883ff9a1008509b322d5d0b3">llvm::SExtInst::cloneImpl</a>, <a href="/web-llvm/docs/api/classes/llvm/shufflevectorinst/#a815ceab21b998b00b5f6d31a1e59cbf2">llvm::ShuffleVectorInst::cloneImpl</a>, <a href="/web-llvm/docs/api/classes/llvm/sitofpinst/#a04cba684a78bb685e087842264cc121e">llvm::SIToFPInst::cloneImpl</a>, <a href="/web-llvm/docs/api/classes/llvm/storeinst/#a9d671a4abcc5302e512b2ace75b58656">llvm::StoreInst::cloneImpl</a>, <a href="/web-llvm/docs/api/classes/llvm/truncinst/#a29fae577a052d379c000bd4a08948105">llvm::TruncInst::cloneImpl</a>, <a href="/web-llvm/docs/api/classes/llvm/uitofpinst/#aa89899a2dfe4b0ae836cdc5a23100971">llvm::UIToFPInst::cloneImpl</a>, <a href="/web-llvm/docs/api/classes/llvm/vaarginst/#ae9ff6645dc0055fe932aa1bd5644d89c">llvm::VAArgInst::cloneImpl</a>, <a href="/web-llvm/docs/api/classes/llvm/zextinst/#aebe48c365b31c0267d1ce8b91e566c4e">llvm::ZExtInst::cloneImpl</a>, <a href="/web-llvm/docs/api/structs/anonymous-clonefunction-cpp-/pruningfunctioncloner/#afbf9fd3d3729664031c88766bcefcdf0">anonymous{CloneFunction.cpp}::PruningFunctionCloner::cloneInstruction</a>, <a href="/web-llvm/docs/api/classes/llvm/functioncomparator/#aecc5ef45f49070634ddd53a04ed5548e">llvm::FunctionComparator::cmpConstants</a>, <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/instcombine/instcombinevectorops-cpp/#a1e502a1ec39cc64d6b86e9e68b29be89">collectShuffleElements</a>, <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/instcombine/instcombinevectorops-cpp/#a0f22159dceed07fd0d5d47915a80dc72">collectSingleShuffleElements</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/arm/armisellowering-cpp/#aa4c17cc7964441daaea8b4bee6c18f93">CombineBaseUpdate</a>, <a href="/web-llvm/docs/api/classes/anonymous-x86loweramxtype-cpp-/x86loweramxcast/#a4edfadcff6e889811bf08326ee359fb3">anonymous{X86LowerAMXType.cpp}::X86LowerAMXCast::combineCastStore</a>, <a href="/web-llvm/docs/api/structs/anonymous-dataflowsanitizer-cpp-/dfsanfunction/#a609c78a9c329baf4d3aa095a80784a4c">anonymous{DataFlowSanitizer.cpp}::DFSanFunction::combineOperandOrigins</a>, <a href="/web-llvm/docs/api/structs/anonymous-dataflowsanitizer-cpp-/dfsanfunction/#ad7d79bd0b027705195d79619a1d0450a">anonymous{DataFlowSanitizer.cpp}::DFSanFunction::combineOperandShadows</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/x86/x86isellowering-cpp/#a2d9fefea85a815cc1227bbd3eee1fab3">combineSCALAR_TO_VECTOR</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/x86/x86isellowering-cpp/#a8af6dae0cb4e67d7004c888ed265f82a">combineTargetShuffle</a>, <a href="/web-llvm/docs/api/classes/llvm/instcombinerimpl/#a6adc65f05e61f4929966c0e4429c6fc7">llvm::InstCombinerImpl::commonCastTransforms</a>, <a href="/web-llvm/docs/api/classes/llvm/instcombinerimpl/#aa831d259fa5719e16927b5f4877988db">llvm::InstCombinerImpl::commonShiftTransforms</a>, <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/vectorize/slpvectorizer-cpp/#af5d61d0124d62ee38726acc83dcdc037">compareCmp</a>, <a href="/web-llvm/docs/api/structs/anonymous-interleavedloadcombinepass-cpp-/vectorinfo/#a30656b818497e335ff16282be4fe6300">anonymous{InterleavedLoadCombinePass.cpp}::VectorInfo::computeFromBCI</a>, <a href="/web-llvm/docs/api/files/lib/lib/analysis/valuetracking-cpp/#a6f66a5dafb459495626be404e48fbe51">computeKnownBitsFromOperator</a>, <a href="/web-llvm/docs/api/structs/anonymous-interleavedloadcombinepass-cpp-/vectorinfo/#a2088d6a1f9882689fbea2dff8f09494c">anonymous{InterleavedLoadCombinePass.cpp}::VectorInfo::computePolynomialBinOp</a>, <a href="/web-llvm/docs/api/structs/anonymous-interleavedloadcombinepass-cpp-/vectorinfo/#a38a01001593bf75700ee024b15bdf413">anonymous{InterleavedLoadCombinePass.cpp}::VectorInfo::computePolynomialFromPointer</a>, <a href="/web-llvm/docs/api/files/lib/lib/analysis/branchprobabilityinfo-cpp/#ade155905429b0a259a1030f418c04ad9">computeUnlikelySuccessors</a>, <a href="/web-llvm/docs/api/files/lib/lib/analysis/lazyvalueinfo-cpp/#a7467c1c3eff398cd97c3d8a2b2cebac0">constantFoldUser</a>, <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/scalar/reassociate-cpp/#a5ccdf0465e957f46ac1241b63af00864">ConvertShiftToMul</a>, <a href="/web-llvm/docs/api/files/lib/lib/codegen/globalmergefunctions-cpp/#a89a4b57af49436df2fd5796f26a34dc5">createMergedFunction</a>, <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/scalar/indvarsimplify-cpp/#a8160c4d5a8fc34f6085af951980dbaa6">createReplacement</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64isellowering-cpp/#a5aade91cf963bd6be461be24ff3a284c">createTblForTrunc</a>, <a href="/web-llvm/docs/api/files/lib/lib/codegen/codegenprepare-cpp/#adfad68845808cb6acd116e50b15bc281">despeculateCountZeros</a>, <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/scalar/loopidiomrecognize-cpp/#a48f061a53492f73dc9d82812f4350b44">detectPopcountIdiom</a>, <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/scalar/loopidiomrecognize-cpp/#a3a0cafd820690b73a6169ab519d77d2a">detectShiftUntilLessThanIdiom</a>, <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/scalar/loopidiomrecognize-cpp/#a7ff0d8853961745bbe8afef66fab99dc">detectShiftUntilZeroIdiom</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/arc/arcoptaddrmode-cpp/#a488daa300aea64109710b4e2fe0cbc44">dominatesAllUsesOf</a>, <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/instcombine/instcombineshifts-cpp/#a33e48dd73f38cb005f9a57fa3965879e">dropRedundantMaskingOfLeftShiftInput</a>, <a href="/web-llvm/docs/api/classes/anonymous-simplifyindvar-cpp-/simplifyindvar/#acccaf0eaeef2b860b1182f8985f59e94">anonymous{SimplifyIndVar.cpp}::SimplifyIndvar::eliminateIVComparison</a>, <a href="/web-llvm/docs/api/classes/anonymous-simplifyindvar-cpp-/simplifyindvar/#a664aaf46532d6ebeed0dfeb704308d33">anonymous{SimplifyIndVar.cpp}::SimplifyIndvar::eliminateSDiv</a>, <a href="/web-llvm/docs/api/classes/anonymous-simplifyindvar-cpp-/simplifyindvar/#a6f5eb28a130d94e94dff2f9e798617ab">anonymous{SimplifyIndVar.cpp}::SimplifyIndvar::eliminateTrunc</a>, <a href="/web-llvm/docs/api/classes/llvm/sitargetlowering/#aa7f6ff2830d775cf0c6a4052836c2552">llvm::SITargetLowering::emitExpandAtomicAddrSpacePredicate</a>, <a href="/web-llvm/docs/api/files/lib/lib/codegen/lib/codegen/asmprinter/asmprinter-cpp/#af7fb6d7d97dc4e12a6ac3a9efebcd71a">emitGlobalConstantArray</a>, <a href="/web-llvm/docs/api/files/lib/lib/codegen/lib/codegen/asmprinter/asmprinter-cpp/#a9ec5fb3e521efb1fdb547aa3c3c43c75">emitGlobalConstantStruct</a>, <a href="/web-llvm/docs/api/classes/llvm/evaluator/#aac9fd94c18d93885c8d947121ab9721e">llvm::Evaluator::EvaluateFunction</a>, <a href="/web-llvm/docs/api/files/lib/lib/ir/constantfold-cpp/#aefdc5e2a3d0696ee5c5bf0b467e5f0c5">evaluateICmpRelation</a>, <a href="/web-llvm/docs/api/classes/llvm/vppredinstphirecipe/#a3e63796e123d5ba9cbfa023983328c37">llvm::VPPredInstPHIRecipe::execute</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/directx/dxilintrinsicexpansion-cpp/#ae2198d73f3c2de2cee53f3d15db39abe">expandAbs</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/directx/dxilintrinsicexpansion-cpp/#adc12bf3c911b1e25c4a14ce8f4ad7634">expandAnyOrAllIntrinsic</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/directx/dxilintrinsicexpansion-cpp/#a720b783746c2f472ba1a810c8a3fe600">expandAtan2Intrinsic</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/directx/dxilintrinsicexpansion-cpp/#a173642074e60da6c0f10a1feb08211f3">expandClampIntrinsic</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/directx/dxilintrinsicexpansion-cpp/#a505ddaadef479f2d0c0810c203000eaa">expandCrossIntrinsic</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/directx/dxilintrinsicexpansion-cpp/#a8c2d1e168bee4b98922fbe0926972650">expandDegreesIntrinsic</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a08d3e8ce57fb65481a42b256d26c264d">llvm::expandDivision</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a83cfb58d48c02daaaa8ee7e924e9fb36">llvm::expandDivisionUpTo32Bits</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a6c6db1ba2b3654c01ec2363b2bc34ce4">llvm::expandDivisionUpTo64Bits</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/directx/dxilintrinsicexpansion-cpp/#ab26ebd710695202964347075355c501d">expandExpIntrinsic</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/directx/dxilintrinsicexpansion-cpp/#a55168fd53b4a5aba23e6c6394149cca6">expandFloatDotIntrinsic</a>, <a href="/web-llvm/docs/api/files/lib/lib/codegen/expandlargefpconvert-cpp/#a46482b2bd77de78d901bfa2fd727ba0e">expandFPToI</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/directx/dxilintrinsicexpansion-cpp/#a7d02bfd7df1433b9ff3e6e237aed1e00">expandIntegerDotIntrinsic</a>, <a href="/web-llvm/docs/api/files/lib/lib/codegen/expandlargefpconvert-cpp/#a0f218e3451638c34910744dedf0b71ac">expandIToFP</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/directx/dxilintrinsicexpansion-cpp/#a4cd18d853f78e52f086aaefadf5e3e04">expandLerpIntrinsic</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/directx/dxilintrinsicexpansion-cpp/#a8be283da675a1b678e17fd283f14945c">expandLogIntrinsic</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/directx/dxilintrinsicexpansion-cpp/#a017debc0002d97577349af103f3bbe4d">expandNormalizeIntrinsic</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/directx/dxilintrinsicexpansion-cpp/#a7e60b335a21054740045b2f77975841f">expandPowIntrinsic</a>, <a href="/web-llvm/docs/api/structs/anonymous-expandvectorpredication-cpp-/cachingvpexpander/#aee759d5807e7eb77e631717da4461426">anonymous{ExpandVectorPredication.cpp}::CachingVPExpander::expandPredication</a>, <a href="/web-llvm/docs/api/structs/anonymous-expandvectorpredication-cpp-/cachingvpexpander/#a3eba8b3e2e38c997d14bc2ee850be29a">anonymous{ExpandVectorPredication.cpp}::CachingVPExpander::expandPredicationInBinaryOperator</a>, <a href="/web-llvm/docs/api/structs/anonymous-expandvectorpredication-cpp-/cachingvpexpander/#a5afd2ab39f4d739286d175f8babb8e6b">anonymous{ExpandVectorPredication.cpp}::CachingVPExpander::expandPredicationInComparison</a>, <a href="/web-llvm/docs/api/structs/anonymous-expandvectorpredication-cpp-/cachingvpexpander/#a2153c46ea6d560ce96b6ad7e822d2c70">anonymous{ExpandVectorPredication.cpp}::CachingVPExpander::expandPredicationInReduction</a>, <a href="/web-llvm/docs/api/structs/anonymous-expandvectorpredication-cpp-/cachingvpexpander/#a5cd88dbe6fb8f2ddbd621296ca4ebd5f">anonymous{ExpandVectorPredication.cpp}::CachingVPExpander::expandPredicationToCastIntrinsic</a>, <a href="/web-llvm/docs/api/structs/anonymous-expandvectorpredication-cpp-/cachingvpexpander/#a62f9944dba24143c8954964d7dff45b8">anonymous{ExpandVectorPredication.cpp}::CachingVPExpander::expandPredicationToFPCall</a>, <a href="/web-llvm/docs/api/structs/anonymous-expandvectorpredication-cpp-/cachingvpexpander/#ad2529fdcdfd78c5eccd6079fc3c74ad3">anonymous{ExpandVectorPredication.cpp}::CachingVPExpander::expandPredicationToIntCall</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/directx/dxilintrinsicexpansion-cpp/#ae86dda8e59bb02221dadee65fde3bb8e">expandRadiansIntrinsic</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#ad0154d60f04a5d8549b44635852557f0">llvm::expandRemainder</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a090725add53936fcebc89f58fc9a7da1">llvm::expandRemainderUpTo32Bits</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a27da54a97fcba955457048148b1fef99">llvm::expandRemainderUpTo64Bits</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/directx/dxilintrinsicexpansion-cpp/#ad28c25a19888a3846117d94821e75042">expandSignIntrinsic</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/directx/dxilintrinsicexpansion-cpp/#a7b29eea052e72ee9e9d598d992aa82e2">expandStepIntrinsic</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/directx/dxilintrinsicexpansion-cpp/#a6662ac36c814abaeac2680e22c889b27">expandVecReduceAdd</a>, <a href="/web-llvm/docs/api/files/lib/lib/codegen/lib/codegen/selectiondag/dagcombiner-cpp/#a021f42abfec39ba02f6b719a449b21db">ExtendUsesToFormExtLoad</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/x86/x86fixupvectorconstants-cpp/#a5929353367b8b1f607f74b6137017d9a">extractConstantBits</a>, <a href="/web-llvm/docs/api/classes/llvm/aarch64targetlowering/#a790e9b70f12899a4cb2aefd33826ee7d">llvm::AArch64TargetLowering::fallBackToDAGISel</a>, <a href="/web-llvm/docs/api/classes/llvm/riscvtargetlowering/#a6914b95d1fcf7a5aca24fe82bf4100c2">llvm::RISCVTargetLowering::fallBackToDAGISel</a>, <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/vectorize/slpvectorizer-cpp/#a3c995d3af67d9f0024160f8480989563">findBuildAggregate_rec</a>, <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/instcombine/instcombinevectorops-cpp/#aa5aa7648807905cd7b63153812029fe2">findDemandedEltsBySingleUser</a>, <a href="/web-llvm/docs/api/files/lib/lib/analysis/loopinfo-cpp/#aab83ba77d9d7f1be86b2f06abe3f1bdb">findFinalIVValue</a>, <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/utils/ctorutils-cpp/#aac8ef9c8745bf77faa38eb1cd16fb4a7">findGlobalCtors</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#adf87a16be872504ce4d0ab9714dc6217">llvm::findHistogram</a>, <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/instcombine/instcombinecalls-cpp/#ac6d7cb2af5197dfb40fa54302fbe06d1">findInitTrampoline</a>, <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/instcombine/instcombinecalls-cpp/#a1eea4a3473408dad3e81030a130a51ca">findInitTrampolineFromAlloca</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#ab09fc7dee4f7e02c60f7a9c928dc1603">llvm::findScalarElement</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/amdgpucodegenprepare-cpp/#a9f80c73009332bada61d1493b0a34e6b">findSelectThroughCast</a>, <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/scalar/reassociate-cpp/#a45d0fa60c81eecbff60c1b2bb673e87b">FindSingleUseMultiplyFactors</a>, <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/ipo/constantmerge-cpp/#a8c82bb68e32af4477888125c41741a7f">FindUsedValues</a>, <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/ipo/stripsymbols-cpp/#a348eede5b05a57edfafe7f8595cced8b">findUsedValues</a>, <a href="/web-llvm/docs/api/classes/anonymous-amdgpucodegenprepare-cpp-/amdgpucodegenprepareimpl/#a36b7410be1f86b52970bb1381904e282">anonymous{AMDGPUCodeGenPrepare.cpp}::AMDGPUCodeGenPrepareImpl::foldBinOpIntoSelect</a>, <a href="/web-llvm/docs/api/classes/llvm/instcombinerimpl/#a9317f2efaf85a4afc7cde58a2c0d734b">llvm::InstCombinerImpl::foldBinopWithPhiOperands</a>, <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/instcombine/instcombinecasts-cpp/#a6556e45ee27ad333bf33eda6b1f04b8a">foldBitCastBitwiseLogic</a>, <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/instcombine/instcombinecasts-cpp/#a5d0fa3868fb321fcd4b5d632028db897">foldBitCastSelect</a>, <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/instcombine/instcombinevectorops-cpp/#ab737e320d75547e2b43f6044fc3f3bcc">foldCastShuffle</a>, <a href="/web-llvm/docs/api/classes/llvm/instcombinerimpl/#a866883cec7ed781fcf1e9cda18b24f5b">llvm::InstCombinerImpl::foldCmpLoadFromIndexedGlobal</a>, <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/instcombine/instcombinevectorops-cpp/#a01aa2c4724ae9bf421d1cfff3a1c7fa5">foldConstantInsEltIntoShuffle</a>, <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/instcombine/instcombinecompares-cpp/#a48239fe2dd570dc10b58a6a89ce6dd72">foldFCmpFSubIntoFCmp</a>, <a href="/web-llvm/docs/api/classes/llvm/instcombinerimpl/#a901cc1fd9cbb0ec57e3d7f53a70ecd09">llvm::InstCombinerImpl::foldFCmpIntToFPConst</a>, <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/instcombine/instcombinecompares-cpp/#a0397bc5569b1651e9f2e3e4faf2ade34">foldFCmpReciprocalAndZero</a>, <a href="/web-llvm/docs/api/files/lib/lib/codegen/codegenprepare-cpp/#a1f580ab00002a65787ab52ef2aa9a439">foldFCmpToFPClassTest</a>, <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/instcombine/instcombinecasts-cpp/#a568e85197421e091a259bf80e19c6765">foldFPtoI</a>, <a href="/web-llvm/docs/api/classes/llvm/instcombinerimpl/#afc78cb7aeb92b0fc9223239dd827f7e3">llvm::InstCombinerImpl::foldGEPICmp</a>, <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/instcombine/instructioncombining-cpp/#ad12cb02e2ee53655e834dcb84cd57333">foldGEPOfPhi</a>, <a href="/web-llvm/docs/api/classes/llvm/instcombinerimpl/#ab60c98e34bf6a4b6b599ab93a3f12b06">llvm::InstCombinerImpl::foldICmpAndShift</a>, <a href="/web-llvm/docs/api/classes/llvm/instcombinerimpl/#a36ef4128d8b08242e337bcbed0dce3c8">llvm::InstCombinerImpl::foldICmpBinOp</a>, <a href="/web-llvm/docs/api/classes/llvm/instcombinerimpl/#a78aa741a7874614a21b66826ffe6e5ce">llvm::InstCombinerImpl::foldICmpBinOpEqualityWithConstant</a>, <a href="/web-llvm/docs/api/classes/llvm/instcombinerimpl/#a8efbb860a56c4deccffeca4d2963fb70">llvm::InstCombinerImpl::foldICmpDivConstant</a>, <a href="/web-llvm/docs/api/classes/llvm/instcombinerimpl/#a3d58c11c9787c2764e5f11bb127ced00">llvm::InstCombinerImpl::foldICmpInstWithConstantNotInt</a>, <a href="/web-llvm/docs/api/classes/llvm/instcombinerimpl/#abe15d83fb0501730bbfe840143cedc08">llvm::InstCombinerImpl::foldICmpShlConstant</a>, <a href="/web-llvm/docs/api/classes/llvm/instcombinerimpl/#a037006a1d44974a6840403beb4febd30">llvm::InstCombinerImpl::foldICmpShrConstant</a>, <a href="/web-llvm/docs/api/classes/llvm/instcombinerimpl/#a06131a96d98381fd2b73c4ef401d416c">llvm::InstCombinerImpl::foldICmpSRemConstant</a>, <a href="/web-llvm/docs/api/classes/llvm/instcombinerimpl/#a39e315cb89b7144083895c083cc958e0">llvm::InstCombinerImpl::foldICmpSubConstant</a>, <a href="/web-llvm/docs/api/classes/llvm/instcombinerimpl/#a9bbadd565d3ba2855a90a04101d8d4cf">llvm::InstCombinerImpl::foldICmpTruncConstant</a>, <a href="/web-llvm/docs/api/classes/llvm/instcombinerimpl/#a9175bf0e4b0c3a18e2f86bb11270ee78">llvm::InstCombinerImpl::foldICmpUDivConstant</a>, <a href="/web-llvm/docs/api/classes/llvm/instcombinerimpl/#a7c9fd9f2dba79c2289639f72457fcea1">llvm::InstCombinerImpl::foldICmpUsingBoolRange</a>, <a href="/web-llvm/docs/api/classes/llvm/instcombinerimpl/#a9ab27a13577b53506529f28d41aa0672">llvm::InstCombinerImpl::foldICmpWithCastOp</a>, <a href="/web-llvm/docs/api/classes/llvm/instcombinerimpl/#a7caf9cd5dff4734b8af500d6f0f07437">llvm::InstCombinerImpl::foldICmpWithTrunc</a>, <a href="/web-llvm/docs/api/classes/llvm/instcombinerimpl/#a04d40b2885dcf7e80feed09ba6209e54">llvm::InstCombinerImpl::foldICmpWithZextOrSext</a>, <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/instcombine/instcombinevectorops-cpp/#a42c33c78c903c369b359db824b70cb1b">foldIdentityExtractShuffle</a>, <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/instcombine/instcombinevectorops-cpp/#a332e7f93c5c4782c1a628a1b11ab5032">foldIdentityPaddedShuffles</a>, <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/instcombine/instcombinevectorops-cpp/#ae13bc9134960231b8354f62cfa902782">foldInsEltIntoIdentityShuffle</a>, <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/instcombine/instcombinevectorops-cpp/#a542a88a5b133e2ac8bd9ceb3f8c77dc9">foldInsEltIntoSplat</a>, <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/instcombine/instcombinevectorops-cpp/#ad3259dc4dae742caac6c6e4f577d1760">foldInsSequenceIntoSplat</a>, <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/instcombine/instcombinecalls-cpp/#a9fc15c7f338806b191bd2977f4be2513">foldIntrinsicUsingDistributiveLaws</a>, <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/instcombine/instcombineandorxor-cpp/#a22b32bcfbb9aec8a8fcb9826f40a3955">foldIsPowerOf2</a>, <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/instcombine/instcombineandorxor-cpp/#a034d63ecfce76136f23c28e698d7a720">foldIsPowerOf2OrZero</a>, <a href="/web-llvm/docs/api/classes/llvm/instcombinerimpl/#a78d5bb4c6437373debabeb3f816645cb">llvm::InstCombinerImpl::foldItoFPtoI</a>, <a href="/web-llvm/docs/api/classes/anonymous-simplifyindvar-cpp-/simplifyindvar/#a12f6125cdd608cb0459585ddb68ead53">anonymous{SimplifyIndVar.cpp}::SimplifyIndvar::foldIVUser</a>, <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/instcombine/instcombineandorxor-cpp/#a45705c727d8388c014471504b4ab0c4e">foldLogicCastConstant</a>, <a href="/web-llvm/docs/api/classes/llvm/instcombinerimpl/#a4df124d92129ffa8748086388a420b73">llvm::InstCombinerImpl::foldPHIArgBinOpIntoPHI</a>, <a href="/web-llvm/docs/api/classes/llvm/instcombinerimpl/#acc9feb478a72bb822133b6eec00bef9f">llvm::InstCombinerImpl::foldPHIArgGEPIntoPHI</a>, <a href="/web-llvm/docs/api/classes/llvm/instcombinerimpl/#aa8a186c50cdf60ac11ae1d0b884d468d">llvm::InstCombinerImpl::foldPHIArgLoadIntoPHI</a>, <a href="/web-llvm/docs/api/classes/llvm/instcombinerimpl/#a7a3e32edb65b5b1c216d4454f14df21c">llvm::InstCombinerImpl::foldPHIArgOpIntoPHI</a>, <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/instcombine/instcombineselect-cpp/#a917f93b85c9b8cfe9ad68ba6d49966ba">foldSelectBinOpIdentity</a>, <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/instcombine/instcombineselect-cpp/#ad51f65187d4c6b69d6bf8f71e027e4de">foldSelectICmpAndBinOp</a>, <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/instcombine/instcombineselect-cpp/#ad76042aae559769f4dc50ee2f9548789">foldSelectICmpLshrAshr</a>, <a href="/web-llvm/docs/api/classes/llvm/instcombinerimpl/#a4bd29d381405675f36964e4a5382dae4">llvm::InstCombinerImpl::foldSelectOpOp</a>, <a href="/web-llvm/docs/api/classes/llvm/instcombinerimpl/#a3b73df3a995af9ca26c9d024c957c45a">llvm::InstCombinerImpl::foldSelectShuffle</a>, <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/instcombine/instcombinevectorops-cpp/#a98282716af42c878d4638603c6efb350">foldSelectShuffleOfSelectShuffle</a>, <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/instcombine/instcombinevectorops-cpp/#a2c05df65ce7ce7ec1d78348be2452e8d">foldSelectShuffleWith1Binop</a>, <a href="/web-llvm/docs/api/classes/llvm/instcombinerimpl/#ad3f7f3eaea6d34ab9ade1af54174f5a2">llvm::InstCombinerImpl::FoldShiftByConstant</a>, <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/instcombine/instcombineshifts-cpp/#a04e846746dd1839f88b9a39847f5d643">foldShiftedShift</a>, <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/instcombine/instcombinecompares-cpp/#aaf025e558f9fe2914e3f8c52e046fb21">foldShiftIntoShiftInAnotherHandOfAndInICmp</a>, <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/instcombine/instcombinevectorops-cpp/#aabcb01976dc50b78faed7491a6d43042">foldShuffleOfUnaryOps</a>, <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/instcombine/instcombinevectorops-cpp/#a661440047dc1b2af077911d9cf92236a">foldShuffleWithInsert</a>, <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/instcombine/instcombineandorxor-cpp/#a1f569ebf4402ad560d7c147f688ac05a">foldSignedTruncationCheck</a>, <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/instcombine/instcombinevectorops-cpp/#a1f6c8af64ed18f5f5810f78abf9b4f33">foldTruncInsEltPair</a>, <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/instcombine/instcombinevectorops-cpp/#a747cca8cf8e4c4e41b81bb1cbf146a11">foldTruncShuffle</a>, <a href="/web-llvm/docs/api/classes/llvm/instcombinerimpl/#a2511e442d198696042ad2a39cad89059">llvm::InstCombinerImpl::foldUsingDistributiveLaws</a>, <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/instcombine/instcombinecasts-cpp/#aa1c33c4fbbe149ca5deb130bca410ef2">foldVecExtTruncToExtElt</a>, <a href="/web-llvm/docs/api/classes/llvm/instcombinerimpl/#acbf4c17d9f1b9f6729602a3c2a6c5b9d">llvm::InstCombinerImpl::foldVectorBinop</a>, <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/instcombine/instcombinecasts-cpp/#aee3e98b16f1c8d8d8b30b9a459a6a602">foldVecTruncToExtElt</a>, <a href="/web-llvm/docs/api/classes/anonymous-inlinefunction-cpp-/landingpadinlininginfo/#adcbc4d7e8bf9926797b48a2b3603e3a4">anonymous{InlineFunction.cpp}::LandingPadInliningInfo::forwardResume</a>, <a href="/web-llvm/docs/api/classes/llvm/instcombinerimpl/#af59c587eddc75748a1e201369cd3dbac">llvm::InstCombinerImpl::freezeOtherUses</a>, <a href="/web-llvm/docs/api/classes/llvm/indirectbrinst/#a47ee004c9106856aaea0fc3e063105a7">llvm::IndirectBrInst::getAddress</a>, <a href="/web-llvm/docs/api/classes/llvm/indirectbrinst/#a320bc10750b3569ed75d922dcf31c46f">llvm::IndirectBrInst::getAddress</a>, <a href="/web-llvm/docs/api/classes/llvm/extractvalueinst/#ab6fc714572e1434db6d1b2a240877039">llvm::ExtractValueInst::getAggregateOperand</a>, <a href="/web-llvm/docs/api/classes/llvm/extractvalueinst/#a9e93077f179928791e7e762809d81d14">llvm::ExtractValueInst::getAggregateOperand</a>, <a href="/web-llvm/docs/api/classes/llvm/insertvalueinst/#a3db71439018213c109610b5cde061ee8">llvm::InsertValueInst::getAggregateOperand</a>, <a href="/web-llvm/docs/api/classes/llvm/insertvalueinst/#ae0ceea9b86b06db476f92680ed54bd09">llvm::InsertValueInst::getAggregateOperand</a>, <a href="/web-llvm/docs/api/classes/llvm/globalalias/#a311a097af4f0f77da22ac7acddc496f5">llvm::GlobalAlias::getAliaseeObject</a>, <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/instcombine/instcombinevectorops-cpp/#af7e7c9415c23ae336af651877798a377">getAlternateBinop</a>, <a href="/web-llvm/docs/api/classes/llvm/callbase/#aabd76e6a8a23a5af1ce4d3c310d88bcd">llvm::CallBase::getArgOperand</a>, <a href="/web-llvm/docs/api/classes/llvm/funcletpadinst/#af8fcc98ff5354df31b46d4cac69514ab">llvm::FuncletPadInst::getArgOperand</a>, <a href="/web-llvm/docs/api/classes/llvm/aarch64ttiimpl/#aae70ddddbfd05ed5831918fa1836b947">llvm::AArch64TTIImpl::getArithmeticInstrCost</a>, <a href="/web-llvm/docs/api/classes/llvm/allocainst/#ab8ea7e026b4ffc33dac82b184aee34ce">llvm::AllocaInst::getArraySize</a>, <a href="/web-llvm/docs/api/classes/llvm/allocainst/#af4283a4cef4e2b88f565d827d5857e14">llvm::AllocaInst::getArraySize</a>, <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/instrumentation/pgoinstrumentation-cpp/#af0e4d9315f1815020f42edec6a27ad1f">getBranchCondString</a>, <a href="/web-llvm/docs/api/structs/llvm/loop/loopbounds/#acfa250dd5ec97448681f9833e22d50cf">llvm::Loop::LoopBounds::getCanonicalPredicate</a>, <a href="/web-llvm/docs/api/classes/llvm/atomiccmpxchginst/#a39126826c171851bae4062b25b48e74e">llvm::AtomicCmpXchgInst::getCompareOperand</a>, <a href="/web-llvm/docs/api/classes/llvm/atomiccmpxchginst/#a0e3cb18f50272a795fa9e470039c7f26">llvm::AtomicCmpXchgInst::getCompareOperand</a>, <a href="/web-llvm/docs/api/classes/llvm/switchinst/#add8214051c768ea9d437cac4b6d50c56">llvm::SwitchInst::getCondition</a>, <a href="/web-llvm/docs/api/classes/llvm/executionengine/#a0a724dad58a66f883d1b88115237ae00">llvm::ExecutionEngine::getConstantValue</a>, <a href="/web-llvm/docs/api/classes/llvm/switchinst/#a0943fb5f399be0ac6ffbe8c977b619c8">llvm::SwitchInst::getDefaultDest</a>, <a href="/web-llvm/docs/api/classes/llvm/memoryuseordef/#a20455da69cab73871b8c0111f0afe712">llvm::MemoryUseOrDef::getDefiningAccess</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/x86/x86isellowering-cpp/#a1749d6a76a90f1117d344826f3e1e428">getExtractedDemandedElts</a>, <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/instcombine/instcombinemuldivrem-cpp/#a41add7dc9178ec10f8f2d4d6fd2a6f9a">getFSqrtDivOptPattern</a>, <a href="/web-llvm/docs/api/files/lib/lib/analysis/loopaccessanalysis-cpp/#a5fe252ea76c22a7e9bed5af0446d4fdb">getGEPInductionOperand</a>, <a href="/web-llvm/docs/api/classes/llvm/memoryphi/#ad9a4d921199ae54b411ddadde3530a0f">llvm::MemoryPhi::getIncomingValue</a>, <a href="/web-llvm/docs/api/classes/llvm/phinode/#aca1fd00f3ab63ec8f0f1ccc2093a9f6d">llvm::PHINode::getIncomingValue</a>, <a href="/web-llvm/docs/api/classes/llvm/callbrinst/#aae2d74b7aa304f8f6126f4b1e6e00dd0">llvm::CallBrInst::getIndirectDestLabel</a>, <a href="/web-llvm/docs/api/classes/llvm/loop/#ab05e97728516fbeeaa9426496257c800">llvm::Loop::getInductionVariable</a>, <a href="/web-llvm/docs/api/classes/llvm/insertvalueinst/#a006ff879dadad159fda97f1c5a5f5616">llvm::InsertValueInst::getInsertedValueOperand</a>, <a href="/web-llvm/docs/api/classes/llvm/insertvalueinst/#af59fe7c90e219aaabd7f72117753d0d5">llvm::InsertValueInst::getInsertedValueOperand</a>, <a href="/web-llvm/docs/api/files/lib/lib/analysis/valuetracking-cpp/#ac475c1bc115b2d8b03a7959be84b1ca9">getInvertibleOperands</a>, <a href="/web-llvm/docs/api/classes/llvm/scevexpander/#aece02adc8e4cc74296bfe410eabe287b">llvm::SCEVExpander::getIVIncOperand</a>, <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/scalar/indvarsimplify-cpp/#ab8fbf8890afc93e88d19a28877c13fad">getLoopPhiForCounter</a>, <a href="/web-llvm/docs/api/classes/llvm/systemzttiimpl/#a97ebd00c769b1d7c67f7db4b58137c93">llvm::SystemZTTIImpl::getMemoryOpCost</a>, <a href="/web-llvm/docs/api/classes/llvm/atomiccmpxchginst/#a13c9a4cc2733456213b8eab8511cd568">llvm::AtomicCmpXchgInst::getNewValOperand</a>, <a href="/web-llvm/docs/api/classes/llvm/atomiccmpxchginst/#addce628d1f566b746032ece8472b9acb">llvm::AtomicCmpXchgInst::getNewValOperand</a>, <a href="/web-llvm/docs/api/classes/llvm/memorydef/#a37da5c4d19e2ce9984b3f8ab7a9c46c5">llvm::MemoryDef::getOptimized</a>, <a href="/web-llvm/docs/api/classes/llvm/catchswitchinst/#a74d56dd1a8531d108c9b4883bfff61a6">llvm::CatchSwitchInst::getParentPad</a>, <a href="/web-llvm/docs/api/classes/llvm/addrspacecastinst/#a560c308b4df9fbe80a3a22381f178fd1">llvm::AddrSpaceCastInst::getPointerOperand</a>, <a href="/web-llvm/docs/api/classes/llvm/addrspacecastinst/#a0e45922a20baf3d576ce41abf9d7df5c">llvm::AddrSpaceCastInst::getPointerOperand</a>, <a href="/web-llvm/docs/api/classes/llvm/addrspacecastoperator/#aa0f8dc609558dac5e8b659ebf23ab1b0">llvm::AddrSpaceCastOperator::getPointerOperand</a>, <a href="/web-llvm/docs/api/classes/llvm/addrspacecastoperator/#a09608315704150b3980e0360223c8c2c">llvm::AddrSpaceCastOperator::getPointerOperand</a>, <a href="/web-llvm/docs/api/classes/llvm/atomiccmpxchginst/#a6c4b659279dd2c617f262bfd36a5eee3">llvm::AtomicCmpXchgInst::getPointerOperand</a>, <a href="/web-llvm/docs/api/classes/llvm/atomiccmpxchginst/#a8a654df5bd09e7e24fd8b6189e942e83">llvm::AtomicCmpXchgInst::getPointerOperand</a>, <a href="/web-llvm/docs/api/classes/llvm/atomicrmwinst/#a506260aecca4d92e8633628f8d4b83ae">llvm::AtomicRMWInst::getPointerOperand</a>, <a href="/web-llvm/docs/api/classes/llvm/atomicrmwinst/#a814122750c83afb9be6da920367d6f62">llvm::AtomicRMWInst::getPointerOperand</a>, <a href="/web-llvm/docs/api/classes/llvm/gepoperator/#a9eed94bc40cf3c61f97c72de0b1190d8">llvm::GEPOperator::getPointerOperand</a>, <a href="/web-llvm/docs/api/classes/llvm/gepoperator/#a23458a8fae63673c8029c260ba89642b">llvm::GEPOperator::getPointerOperand</a>, <a href="/web-llvm/docs/api/classes/llvm/getelementptrinst/#a0621d26039722d96ad6da863edbf60f9">llvm::GetElementPtrInst::getPointerOperand</a>, <a href="/web-llvm/docs/api/classes/llvm/getelementptrinst/#aeefd341ed1a0ae73f89ec5add43a9b15">llvm::GetElementPtrInst::getPointerOperand</a>, <a href="/web-llvm/docs/api/classes/llvm/loadinst/#a2d1ff28d6923802e165905b8d1766e76">llvm::LoadInst::getPointerOperand</a>, <a href="/web-llvm/docs/api/classes/llvm/loadinst/#a1df3c027228bc08d14c6aa380a251625">llvm::LoadInst::getPointerOperand</a>, <a href="/web-llvm/docs/api/classes/llvm/ptrtointinst/#a220f067bbc33b6db6cc2c7ff5a912902">llvm::PtrToIntInst::getPointerOperand</a>, <a href="/web-llvm/docs/api/classes/llvm/ptrtointinst/#a541950f244e5ba649e145ad8b386a27d">llvm::PtrToIntInst::getPointerOperand</a>, <a href="/web-llvm/docs/api/classes/llvm/ptrtointoperator/#af9c43ddd3010a5eab3e955761ebe9a0b">llvm::PtrToIntOperator::getPointerOperand</a>, <a href="/web-llvm/docs/api/classes/llvm/ptrtointoperator/#ae84bd8b649028e257bf1b74ed893b0ab">llvm::PtrToIntOperator::getPointerOperand</a>, <a href="/web-llvm/docs/api/classes/llvm/storeinst/#aefb15964facf7f35f22a6e8a7fb67285">llvm::StoreInst::getPointerOperand</a>, <a href="/web-llvm/docs/api/classes/llvm/storeinst/#a316d15ff7b59df8125c14360f847135c">llvm::StoreInst::getPointerOperand</a>, <a href="/web-llvm/docs/api/classes/llvm/vaarginst/#a53d1a683af75c9ba45f6194fc8d10964">llvm::VAArgInst::getPointerOperand</a>, <a href="/web-llvm/docs/api/classes/llvm/vaarginst/#a83a33993635954f5b7b776ee7d8f8b41">llvm::VAArgInst::getPointerOperand</a>, <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/scalar/loopidiomrecognize-cpp/#a0554350a6af85d4e8cf06cd9ca2b5556">getRecurrenceVar</a>, <a href="/web-llvm/docs/api/classes/llvm/loopvectorizationcostmodel/#a4e307866e6d65e87d1e6884b0d13306c">llvm::LoopVectorizationCostModel::getReductionPatternCost</a>, <a href="/web-llvm/docs/api/namespaces/llvm/objcarc/#a14c7178bc4d56dc8482dbb51fa6979b8">llvm::objcarc::getreturnRVOperand</a>, <a href="/web-llvm/docs/api/classes/llvm/returninst/#a6c2dee0852138a5cb8a4fef5883db9ec">llvm::ReturnInst::getReturnValue</a>, <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/utils/local-cpp/#a55a8ce252bfbfa1af642af05f2c31e10">getSalvageOpsForBinOp</a>, <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/utils/local-cpp/#a7b323f2153ac64cdbab7e81c15575c0d">getSalvageOpsForIcmpOp</a>, <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/vectorize/slpvectorizer-cpp/#acb2c6a8dafac1cdf8927e67b28baab1c">getSameOpcode</a>, <a href="/web-llvm/docs/api/classes/llvm/noaliasscopedeclinst/#a34f6aa565eff649a89e0406f516d12a5">llvm::NoAliasScopeDeclInst::getScopeList</a>, <a href="/web-llvm/docs/api/files/lib/lib/analysis/valuetracking-cpp/#a0096a88b01feba943407155e0b6a1e77">getShuffleDemandedElts</a>, <a href="/web-llvm/docs/api/classes/llvm/constantvector/#aa2ea20974430e8820f962083ca421c05">llvm::ConstantVector::getSplatValue</a>, <a href="/web-llvm/docs/api/classes/llvm/bitcastoperator/#ab53d020ce9103d77797a9484c438d35d">llvm::BitCastOperator::getSrcTy</a>, <a href="/web-llvm/docs/api/classes/llvm/castinst/#a01cc70c1e8052996fb44f59fa63a015c">llvm::CastInst::getSrcTy</a>, <a href="/web-llvm/docs/api/classes/llvm/scalarevolution/#aa6a8e1063693697569fead19a720c43c">llvm::ScalarEvolution::getStrengthenedNoWrapFlagsFromBinOp</a>, <a href="/web-llvm/docs/api/classes/llvm/catchswitchinst/#ab67f867e4c275996050a92cc4853819e">llvm::CatchSwitchInst::getSuccessor</a>, <a href="/web-llvm/docs/api/classes/llvm/indirectbrinst/#a8cc0c502b60875a5b8086c6e029a56c8">llvm::IndirectBrInst::getSuccessor</a>, <a href="/web-llvm/docs/api/classes/llvm/switchinst/#a30f79d54afada3c9005d24ab8743a9d6">llvm::SwitchInst::getSuccessor</a>, <a href="/web-llvm/docs/api/classes/llvm/sitargetlowering/#ae2b19bc21d3201e045841292463888ba">llvm::SITargetLowering::getTgtMemIntrinsic</a>, <a href="/web-llvm/docs/api/classes/llvm/slpvectorizer/boupslp/#a7800714c330f8f3952e8058b090e001b">llvm::slpvectorizer::BoUpSLP::getTreeCost</a>, <a href="/web-llvm/docs/api/classes/llvm/canonicalloopinfo/#a01560f4a4ff7bfc8a96bd406b6f17ea2">llvm::CanonicalLoopInfo::getTripCount</a>, <a href="/web-llvm/docs/api/classes/llvm/catchswitchinst/#ab04dbc468ae6f1e7ff304ec5ba903b66">llvm::CatchSwitchInst::getUnwindDest</a>, <a href="/web-llvm/docs/api/classes/llvm/atomicrmwinst/#ae55438e0a802a1a20d6dcabf71b552ad">llvm::AtomicRMWInst::getValOperand</a>, <a href="/web-llvm/docs/api/classes/llvm/atomicrmwinst/#ab0f672c61169f876c4f21615cf856a55">llvm::AtomicRMWInst::getValOperand</a>, <a href="/web-llvm/docs/api/classes/llvm/storeinst/#a89caf38fb409b0217360689351f3b457">llvm::StoreInst::getValueOperand</a>, <a href="/web-llvm/docs/api/classes/llvm/storeinst/#a722a24ca17e68ca0d4380c7e73742f9b">llvm::StoreInst::getValueOperand</a>, <a href="/web-llvm/docs/api/files/lib/lib/codegen/interleavedaccesspass-cpp/#a1bf96ea28c04f3533cf028a1d471eae4">getVectorInterleaveFactor</a>, <a href="/web-llvm/docs/api/classes/llvm/constantexpr/#aab577cba8223fe4bb96df5591d49d98a">llvm::ConstantExpr::getWithOperands</a>, <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/scalar/lowerexpectintrinsic-cpp/#a6ac9067dc7c125cd83855df3e480e04c">handleBrSelExpect</a>, <a href="/web-llvm/docs/api/files/lib/lib/codegen/lib/codegen/asmprinter/asmprinter-cpp/#a5fe1d9854fec640792f7f305f75002f3">handleIndirectSymViaGOTPCRel</a>, <a href="/web-llvm/docs/api/classes/llvm/getelementptrinst/#a47fef2802996b78f0530c9b77abca9ed">llvm::GetElementPtrInst::hasAllConstantIndices</a>, <a href="/web-llvm/docs/api/classes/llvm/riscvdagtodagisel/#a0c47c47ebffcc56ccf426575cc7688f1">llvm::RISCVDAGToDAGISel::hasAllNBitUsers</a>, <a href="/web-llvm/docs/api/classes/llvm/getelementptrinst/#a0a9d2347ed3426150ef852d09dbcbaf2">llvm::GetElementPtrInst::hasAllZeroIndices</a>, <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/utils/simplifycfg-cpp/#ab99310a04afb6c28186b1a6428eb75b0">hoistConditionalLoadsStores</a>, <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/instcombine/instcombinevectorops-cpp/#a9a97530480ce0284bb6dace4356e906c">hoistInsEltConst</a>, <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/scalar/licm-cpp/#a697cde840957bbc0b2848a593c3e0d5a">hoistMulAddAssociation</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/riscv/riscvvectorpeephole-cpp/#af4707f2d4fe8e86f046089a400af7e72">INITIALIZE_PASS</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64targettransforminfo-cpp/#aa6ab3fab9efb1a05c605f74d579db034">instCombineSVEDup</a>, <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/instcombine/instructioncombining-cpp/#a5d94ee8aaee00c42c11954aaa6022894">isAllocSiteRemovable</a>, <a href="/web-llvm/docs/api/classes/llvm/gcnttiimpl/#a11fb81052cf8abb712c95daa2f0344d6">llvm::GCNTTIImpl::isAlwaysUniform</a>, <a href="/web-llvm/docs/api/classes/llvm/allocainst/#aea74164514e7164813ab30bcc4b7c557">llvm::AllocaInst::isArrayAllocation</a>, <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/vectorize/slpvectorizer-cpp/#a807bb3d2ecc2999993a91d499bd26543">isCmpSameOrSwapped</a>, <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/scalar/earlycse-cpp/#aa60423084fe7d27af0ffbba889cbdf1a">isEqualImpl</a>, <a href="/web-llvm/docs/api/files/lib/lib/codegen/codegenprepare-cpp/#a19e2fd6fce422c4ab3cea555782abbb6">isExtractBitsCandidateUse</a>, <a href="/web-llvm/docs/api/classes/llvm/systemzttiimpl/#a710fc966df72f9cae9f17ec7eb76f5e8">llvm::SystemZTTIImpl::isFoldableLoad</a>, <a href="/web-llvm/docs/api/classes/llvm/inductiondescriptor/#adb1a03152610d15e008c2fdcb93602ed">llvm::InductionDescriptor::isFPInductionPHI</a>, <a href="/web-llvm/docs/api/files/lib/lib/codegen/lib/codegen/asmprinter/asmprinter-cpp/#a1db077f1815950aa2f419be901c429c6">isGOTEquivalentCandidate</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/systemz/systemzisellowering-cpp/#a26c84133695829e63f3a69adaddbe6b4">isI128MovedToParts</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/ve/veisellowering-cpp/#aa4af5de1f29bd00a557083800ec079b3">isI32Insn</a>, <a href="/web-llvm/docs/api/classes/llvm/castinst/#aeb1b55a34e106493b57164146f40623b">llvm::CastInst::isIntegerCast</a>, <a href="/web-llvm/docs/api/classes/llvm/shufflevectorinst/#a891d016891d8c8ba74acaf3f6fec2c95">llvm::ShuffleVectorInst::isInterleave</a>, <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/scalar/indvarsimplify-cpp/#a23d78b7d4dbea0ecc84dc55313ad1f25">isLoopExitTestBasedOn</a>, <a href="/web-llvm/docs/api/classes/llvm/aarch64targetlowering/#a9a2764d23b64e6bb68a0025d4eab6b29">llvm::AArch64TargetLowering::isMaskAndCmp0FoldingBeneficial</a>, <a href="/web-llvm/docs/api/classes/llvm/armtargetlowering/#af1478848ccc7623d55d4666d293bb6d5">llvm::ARMTargetLowering::isMaskAndCmp0FoldingBeneficial</a>, <a href="/web-llvm/docs/api/classes/llvm/riscvtargetlowering/#aeb0825b5f56c1effcfad1203cb8d4bbe">llvm::RISCVTargetLowering::isMaskAndCmp0FoldingBeneficial</a>, <a href="/web-llvm/docs/api/classes/llvm/systemztargetlowering/#a0ab408ba2e1e6e409f6b07a1789e3b3e">llvm::SystemZTargetLowering::isMaskAndCmp0FoldingBeneficial</a>, <a href="/web-llvm/docs/api/files/lib/lib/analysis/valuetracking-cpp/#a5423e9ec6ad1dea3f9a596429e72d463">isModifyingBinopOfNonZero</a>, <a href="/web-llvm/docs/api/classes/llvm/castinst/#a1438002c91e6e1c7a587a194b268239d">llvm::CastInst::isNoopCast</a>, <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/scalar/inferaddressspaces-cpp/#a44232befb736ff8d861bd991a5a68239">isNoopPtrIntCastPair</a>, <a href="/web-llvm/docs/api/files/lib/lib/analysis/valuetracking-cpp/#a50882a093546a573f3e879fc578f167d">isPowerOfTwoRecurrence</a>, <a href="/web-llvm/docs/api/classes/llvm/aarch64targetlowering/#a9d2e61bef8fbdb714e9f0a739bf49a58">llvm::AArch64TargetLowering::isProfitableToHoist</a>, <a href="/web-llvm/docs/api/classes/llvm/ppctargetlowering/#a857dba88c2223d0a509b5d390f7144f0">llvm::PPCTargetLowering::isProfitableToHoist</a>, <a href="/web-llvm/docs/api/classes/llvm/aarch64ttiimpl/#a2bfff40c1bfc02a21a5ed0b64a99f8a2">llvm::AArch64TTIImpl::isProfitableToSinkOperands</a>, <a href="/web-llvm/docs/api/classes/llvm/armttiimpl/#a0eee77cb45ab15bd00718f8801a3fc53">llvm::ARMTTIImpl::isProfitableToSinkOperands</a>, <a href="/web-llvm/docs/api/files/lib/lib/codegen/lib/codegen/asmprinter/asmprinter-cpp/#aba2d236a616de0db030aeb404f2d41d5">isRepeatedByteSequence</a>, <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/ipo/functionattrs-cpp/#a9ec948ba8709fe1041a2ec4a79cb6e4b">isReturnNonNull</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a5e36553611d3def8cf698c722239718f">llvm::isSafeToSpeculativelyExecuteWithOpcode</a>, <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/instcombine/instcombinevectorops-cpp/#ace7029cdad3163ebfb8172d25e8a59e3">isShuffleEquivalentToSelect</a>, <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/instcombine/instcombinevectorops-cpp/#ae8f4745a87bae0a614d6bda1cc55ab01">isShuffleExtractingFromLHS</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/arm/armtargettransforminfo-cpp/#a0deafca5c66f3b900139bcf024085e8f">isSSATMinMaxPattern</a>, <a href="/web-llvm/docs/api/files/lib/lib/analysis/valuetracking-cpp/#a343ee023c7b7336ca66fd4c296db0feb">lookThroughCast</a>, <a href="/web-llvm/docs/api/files/lib/lib/analysis/valuetracking-cpp/#a88b0909bfe0684c1c286237dd9985ce9">lookThroughCastConst</a>, <a href="/web-llvm/docs/api/classes/anonymous-lowertypetests-cpp-/lowertypetestsmodule/#a7c206887f3f0887f2c6ac58910c09c41">anonymous{LowerTypeTests.cpp}::LowerTypeTestsModule::lower</a>, <a href="/web-llvm/docs/api/classes/llvm/fastisel/#a429785d5b6015aff39a7a998d9e70fa3">llvm::FastISel::lowerCallTo</a>, <a href="/web-llvm/docs/api/classes/llvm/aarch64targetlowering/#aa4094e6b2a8203e5c8b67ecf186d51a9">llvm::AArch64TargetLowering::lowerInterleavedStore</a>, <a href="/web-llvm/docs/api/classes/llvm/armtargetlowering/#aa3168bc53fc117710cec207cc6f60518">llvm::ARMTargetLowering::lowerInterleavedStore</a>, <a href="/web-llvm/docs/api/classes/llvm/riscvtargetlowering/#ab33d2ce475c619c3e4412b33aac3b5bb">llvm::RISCVTargetLowering::lowerInterleavedStore</a>, <a href="/web-llvm/docs/api/classes/llvm/intrinsiclowering/#a065baf0b078aae98e7c9703d6717e15e">llvm::IntrinsicLowering::LowerIntrinsicCall</a>, <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/scalar/reassociate-cpp/#a790c96adef17241b1ba4dbf475c3e57e">LowerNegateToMultiply</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/x86/x86isellowering-cpp/#aeefb78459638421a22efc227acbf0a2a">lowerShufflePairAsUNPCKAndPermute</a>, <a href="/web-llvm/docs/api/classes/anonymous-simplifyindvar-cpp-/simplifyindvar/#a304f0837129322608c9e0384d193a0ba">anonymous{SimplifyIndVar.cpp}::SimplifyIndvar::makeIVComparisonInvariant</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#abf62ca503c047621e9b9047c548f231f">llvm::matchDecomposedSelectPattern</a>, <a href="/web-llvm/docs/api/namespaces/anonymous-mergeicmps-cpp-/#a5289777e58accae64ebded1a95e4c8b0">anonymous{MergeICmps.cpp}::mergeComparisons</a>, <a href="/web-llvm/docs/api/classes/llvm/instmodificationirstrategy/#abd12a5e2bbbe4379385128cc1a481463">llvm::InstModificationIRStrategy::mutate</a>, <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/instcombine/instcombinevectorops-cpp/#acb762c0dfb2a90596163f59e2dfbd029">narrowInsElt</a>, <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/instcombine/instcombinevectorops-cpp/#a746205e6d7f5c0bb265ecc8a911d5b82">narrowVectorSelect</a>, <a href="/web-llvm/docs/api/classes/llvm/orc/ctordtoriterator/#a760366cc3bd5fb351f3ea815d7f08346">llvm::orc::CtorDtorIterator::operator*</a>, <a href="/web-llvm/docs/api/classes/anonymous-x86loweramxtype-cpp-/x86loweramxcast/#ae812aaa917422c3c4b067cda1b1d7019">anonymous{X86LowerAMXType.cpp}::X86LowerAMXCast::optimizeAMXCastFromPhi</a>, <a href="/web-llvm/docs/api/classes/llvm/fastisel/#aa26a7d0b19ce017fda518be95485fb8e">llvm::FastISel::optimizeCmpPredicate</a>, <a href="/web-llvm/docs/api/files/lib/lib/codegen/codegenprepare-cpp/#a2c05548feac70b16d31caf0cfb225714">OptimizeExtractBits</a>, <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/instcombine/instcombinecasts-cpp/#a8f948dd0c375dfeb4cdf99bc33905e66">optimizeIntegerToVectorInsertions</a>, <a href="/web-llvm/docs/api/files/lib/lib/codegen/codegenprepare-cpp/#a3b82cff474790446f1288f1a086c1cd6">OptimizeNoopCopyExpression</a>, <a href="/web-llvm/docs/api/classes/anonymous-spirvasmprinter-cpp-/spirvasmprinter/#aef83676a470a77d6e089737fb024de94">anonymous{SPIRVAsmPrinter.cpp}::SPIRVAsmPrinter::outputAnnotations</a>, <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/utils/ctorutils-cpp/#a30e49f13bd17ed097579ddf598241386">parseGlobalCtors</a>, <a href="/web-llvm/docs/api/structs/llvm/loopstructure/#adc8650d6098e0949f6ecc6368c2ebb99">llvm::LoopStructure::parseLoopStructure</a>, <a href="/web-llvm/docs/api/classes/llvm/ppctargetlowering/#ab4ccdcee4c7a2e0892715d0a8094b86e">llvm::PPCTargetLowering::PerformDAGCombine</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/arm/armisellowering-cpp/#a77f2232fb1d07b3f88edaef89e94e673">PerformMVEVLDCombine</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64isellowering-cpp/#a2fbb20906245b5a07551c13da1409712">performNEONPostLDSTCombine</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64isellowering-cpp/#abdbf7e16d7027d0bbbc9d4e8bf100840">performPostLD1Combine</a>, <a href="/web-llvm/docs/api/classes/llvm/basicttiimplbase/#a1080880d0ca078dceb9d3c8923576ae1">llvm::BasicTTIImplBase&lt; BasicTTIImpl &gt;::preferToKeepConstantsAttached</a>, <a href="/web-llvm/docs/api/classes/llvm/asmprinter/#ad7ad4b4d9c6fc993c58ff56612f4031b">llvm::AsmPrinter::preprocessXXStructorList</a>, <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/scalar/correlatedvaluepropagation-cpp/#aae58203af8c9b9d7e5551badc9094d90">processAShr</a>, <a href="/web-llvm/docs/api/classes/llvm/jumpthreadingpass/#a071cd98d76a1c63f215ad16388bfdfe2">llvm::JumpThreadingPass::processBranchOnXOR</a>, <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/scalar/correlatedvaluepropagation-cpp/#aad984958be92d8e57544ae979a2a897e">processSDiv</a>, <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/scalar/correlatedvaluepropagation-cpp/#a75f37a01df1919449e22c14ec860d8b1">processSRem</a>, <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/instcombine/instcombinecompares-cpp/#aae87c326017fc14f5ba90a036e45438a">processUGT_ADDCST_ADD</a>, <a href="/web-llvm/docs/api/classes/llvm/instcombinerimpl/#ab7805c1d4f86c20199da1dd1fab589f0">llvm::InstCombinerImpl::pushFreezeToPreventPoisonFromPropagating</a>, <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/instcombine/instcombineandorxor-cpp/#a8208d3cd3c60073f5c9ceefec06ab2e3">reassociateFCmps</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#ae573064e881a6a5e07f9904117a9102e">llvm::refineInstruction</a>, <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/utils/ctorutils-cpp/#a26771a5b06ef10e47546922cc377044b">removeGlobalCtors</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/bpf/bpfpreservestaticoffset-cpp/#a4601f3a29dbb6d4ea9da7f4dd26e2ae7">removeMarkerCall</a>, <a href="/web-llvm/docs/api/namespaces/anonymous-loadstorevectorizer-cpp-/#ae31219d422e76099c3c5dfaa2c7171cb">anonymous{LoadStoreVectorizer.cpp}::reorder</a>, <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/scalar/lowerconstantintrinsics-cpp/#aa39118ddf6c73ece724a5c5e93d0db1e">replaceConditionalBranchesOnConstant</a>, <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/instcombine/instcombinevectorops-cpp/#a801d960feba2403acf8dbd07ee3f34b6">replaceExtractElements</a>, <a href="/web-llvm/docs/api/classes/anonymous-simplifyindvar-cpp-/simplifyindvar/#a16096e55b9292113f13073fa2343b9c7">anonymous{SimplifyIndVar.cpp}::SimplifyIndvar::replaceFloatIVWithIntegerIV</a>, <a href="/web-llvm/docs/api/classes/anonymous-simplifyindvar-cpp-/simplifyindvar/#ad4ea440b89ee11cd2aaecfd52290e069">anonymous{SimplifyIndVar.cpp}::SimplifyIndvar::replaceRemWithNumerator</a>, <a href="/web-llvm/docs/api/classes/anonymous-simplifyindvar-cpp-/simplifyindvar/#a645f6e970e94d7ca51922b3932338f51">anonymous{SimplifyIndVar.cpp}::SimplifyIndvar::replaceRemWithNumeratorOrZero</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a2043c82134190abe45de829d07042606">llvm::replaceSignedInst</a>, <a href="/web-llvm/docs/api/classes/anonymous-simplifyindvar-cpp-/simplifyindvar/#a8a96c9b1143670a73852464de9950e8e">anonymous{SimplifyIndVar.cpp}::SimplifyIndvar::replaceSRemWithURem</a>, <a href="/web-llvm/docs/api/classes/llvm/vpvalue/#ae3773dd8f9c831f0dde091319b2ff7d0">llvm::VPValue::replaceUsesWithIf</a>, <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/utils/simplifycfg-cpp/#ad75372cc26ff6f641159aed90d5fc11e">reuseTableCompare</a>, <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/utils/promotememorytoregister-cpp/#aa231a7e6d411bd4797afdd6f0a1f8d6a">rewriteSingleStoreAlloca</a>, <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/utils/lowerglobaldtors-cpp/#aa2a67dbc6220273da3430b0a15735487">runImpl</a>, <a href="/web-llvm/docs/api/structs/anonymous-hexagonoptimizeszextends-cpp-/hexagonoptimizeszextends/#a4240fc0963676b19a8cbf8448a599700">anonymous{HexagonOptimizeSZextends.cpp}::HexagonOptimizeSZextends::runOnFunction</a>, <a href="/web-llvm/docs/api/classes/llvm/executionengine/#a60823e6b4ff77b319b51c9eb634241e2">llvm::ExecutionEngine::runStaticConstructorsDestructors</a>, <a href="/web-llvm/docs/api/files/lib/lib/codegen/expandlargedivrem-cpp/#a5c0f04dd919f2fa52e52f277a68b1ac1">scalarize</a>, <a href="/web-llvm/docs/api/classes/llvm/fastisel/#a1434fc5d1782f15a392af0320f13f6c7">llvm::FastISel::selectExtractValue</a>, <a href="/web-llvm/docs/api/files/lib/lib/analysis/valuetracking-cpp/#a34007246c68dde9443b1afc2a5b59318">setLimitsForBinOp</a>, <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/scalar/reassociate-cpp/#a19d2abc5a580be68aa7751c0e1ce7263">ShouldBreakUpSubtract</a>, <a href="/web-llvm/docs/api/classes/llvm/armtargetlowering/#ac4b5d6d1333be49386e35e56c28647fe">llvm::ARMTargetLowering::shouldExpandAtomicCmpXchgInIR</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/x86/x86isellowering-cpp/#a53e9a46c5489f12eb459b3ecce3db181">shouldExpandCmpArithRMWInIR</a>, <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/instcombine/instcombinecasts-cpp/#a77aac577d89abc9411adfdf918d7d539">shrinkInsertElt</a>, <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/instcombine/instcombinecasts-cpp/#a40c4c6660c6d108c0202fd73c28f2834">shrinkSplatShuffle</a>, <a href="/web-llvm/docs/api/files/lib/lib/analysis/instructionsimplify-cpp/#a496b149294586554f0cd9fd240d8d80d">simplifyAndOfICmpsWithAdd</a>, <a href="/web-llvm/docs/api/files/lib/lib/analysis/instructionsimplify-cpp/#ae5781faa80a27cf51fa316feaa2ad363">simplifyAndOrOfICmpsWithConstants</a>, <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/instcombine/instructioncombining-cpp/#a41c00c458f7416c93927bc2f332b3898">simplifyAssocCastAssoc</a>, <a href="/web-llvm/docs/api/files/lib/lib/analysis/instructionsimplify-cpp/#a8863b1b71b53dbab1dd0bd7933ddb3cf">simplifyAssociativeBinOp</a>, <a href="/web-llvm/docs/api/classes/llvm/instcombinerimpl/#a225d5b1dcc0015e743f1dbbf348a9c36">llvm::InstCombinerImpl::SimplifyAssociativeOrCommutative</a>, <a href="/web-llvm/docs/api/classes/llvm/instcombinerimpl/#ab18666f9305cc63df7009c9e4ec0e35a">llvm::InstCombinerImpl::simplifyBinOpSplats</a>, <a href="/web-llvm/docs/api/classes/llvm/instcombinerimpl/#a37cce7aa1875173688e5971c5d6fa9e0">llvm::InstCombinerImpl::SimplifyDemandedVectorElts</a>, <a href="/web-llvm/docs/api/files/lib/lib/analysis/instructionsimplify-cpp/#a47a81cb5e93cfda95b1de100dd5b9919">simplifyICmpInst</a>, <a href="/web-llvm/docs/api/files/lib/lib/analysis/instructionsimplify-cpp/#a64cb0c5ab10b63f22110e1b0183a648f">simplifyICmpWithBinOp</a>, <a href="/web-llvm/docs/api/classes/anonymous-simplifyindvar-cpp-/simplifyindvar/#a9a4e22418fd040f349bdecefdc303c2e">anonymous{SimplifyIndVar.cpp}::SimplifyIndvar::simplifyIVRemainder</a>, <a href="/web-llvm/docs/api/files/lib/lib/analysis/instructionsimplify-cpp/#a7b473dc0c6603bb29f38c46858df840e">simplifyOrOfICmpsWithAdd</a>, <a href="/web-llvm/docs/api/classes/llvm/jumpthreadingpass/#a064ce69a10374b5342954d481e21fa25">llvm::JumpThreadingPass::simplifyPartiallyRedundantLoad</a>, <a href="/web-llvm/docs/api/classes/llvm/instcombinerimpl/#aa4100f52d21246ec944e97fe1b64b124">llvm::InstCombinerImpl::simplifyRangeCheck</a>, <a href="/web-llvm/docs/api/files/lib/lib/analysis/instructionsimplify-cpp/#a2c78ae45454d731f51f0ce021a729816">simplifyRelativeLoad</a>, <a href="/web-llvm/docs/api/classes/llvm/instcombinerimpl/#a93a6fd2ea0b1d80347d4d5eff6462428">llvm::InstCombinerImpl::simplifyShrShlDemandedBits</a>, <a href="/web-llvm/docs/api/files/lib/lib/codegen/codegenprepare-cpp/#a0049977ff1075a98e9f512bbf4d181a6">sinkAndCmp0Expression</a>, <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/utils/simplifycfg-cpp/#abf69483b802f1e342399912142341c60">sinkLastInstruction</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/bpf/bpfcheckandadjustir-cpp/#a6e78c58ee832ea1775655021854401e6">sinkMinMaxInBB</a>, <a href="/web-llvm/docs/api/files/lib/lib/codegen/codegenprepare-cpp/#a0327169186859791aafa580e4fb547e2">SinkShiftAndTruncate</a>, <a href="/web-llvm/docs/api/classes/llvm/instcombinerimpl/#ac8cb4401526dd424f15566e4501792f7">llvm::InstCombinerImpl::SliceUpIllegalIntegerPHI</a>, <a href="/web-llvm/docs/api/classes/anonymous-x86loweramxtype-cpp-/x86loweramxcast/#a5ca29e57ad15a06f70b6676ec2665f34">anonymous{X86LowerAMXType.cpp}::X86LowerAMXCast::transformAMXCast</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64isellowering-cpp/#a1a7f46d2de90f91e6bf8103dd5f52afe">tryCombineMULLWithUZP1</a>, <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/vectorize/slpvectorizer-cpp/#ad25cdf8e7c874eae6f692b4319c6afe4">tryGetSecondaryReductionRoot</a>, <a href="/web-llvm/docs/api/files/lib/lib/codegen/lib/codegen/selectiondag/dagcombiner-cpp/#a07529501831cc322901e5a24586b7720">tryToFoldExtOfLoad</a>, <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/ipo/globalopt-cpp/#a77de6d50432bef62e38fd24f2030026c">TryToShrinkGlobalToBoolean</a>, <a href="/web-llvm/docs/api/classes/llvm/jumpthreadingpass/#ae4ca9bfe94c6cc3d952413c7907db47f">llvm::JumpThreadingPass::tryToUnfoldSelect</a>, <a href="/web-llvm/docs/api/files/lib/lib/codegen/codegenprepare-cpp/#a8528dea79f0940669c4fcb751940ca94">tryUnmergingGEPsAcrossIndirectBr</a>, <a href="/web-llvm/docs/api/structs/anonymous-attributorattributes-cpp-/aapotentialconstantvaluesfloating/#af8fd85d6783b4f0fbb5f4a8d6bf40bdc">anonymous{AttributorAttributes.cpp}::AAPotentialConstantValuesFloating::updateWithCastInst</a>, <a href="/web-llvm/docs/api/structs/anonymous-attributorattributes-cpp-/aapotentialconstantvaluesfloating/#a6903727302b4d2ede04403999ffd2827">anonymous{AttributorAttributes.cpp}::AAPotentialConstantValuesFloating::updateWithICmpInst</a>, <a href="/web-llvm/docs/api/files/lib/lib/ir/autoupgrade-cpp/#a4ce4b835cffc5fa4123fe82f5f39cf97">upgradeAArch64IntrinsicCall</a>, <a href="/web-llvm/docs/api/files/lib/lib/ir/autoupgrade-cpp/#a90bcc9afc1cc990c8790a5424a93c926">upgradeARMIntrinsicCall</a>, <a href="/web-llvm/docs/api/files/lib/lib/ir/autoupgrade-cpp/#ad37834e4f8e16e808997aef286954fd0">upgradeNVVMIntrinsicCall</a>, <a href="/web-llvm/docs/api/files/lib/lib/ir/autoupgrade-cpp/#ad194379f5156fa6a9ec196923d80df3a">upgradeX86BinaryIntrinsics</a>, <a href="/web-llvm/docs/api/files/lib/lib/ir/autoupgrade-cpp/#abbe50b1b6428dd6884355b64360f2f29">upgradeX86ConcatShift</a>, <a href="/web-llvm/docs/api/files/lib/lib/ir/autoupgrade-cpp/#af61729415c4cfec66c791cd52a532eb9">upgradeX86IntrinsicCall</a>, <a href="/web-llvm/docs/api/files/lib/lib/ir/autoupgrade-cpp/#a2e38c407c9078c144f8aa68eef3ac0ac">upgradeX86Rotate</a>, <a href="/web-llvm/docs/api/classes/llvm/slpvectorizer/boupslp/#a99b79343fdc586cce804ebabf3d419e2">llvm::slpvectorizer::BoUpSLP::vectorizeTree</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/riscv/riscviseldagtodag-cpp/#aadd8c5bb4ccd3134cdde19afc01eb291">vectorPseudoHasAllNBitUsers</a>, <a href="/web-llvm/docs/api/classes/anonymous-riscvcodegenprepare-cpp-/riscvcodegenprepare/#a6cde9aa5130a6fb02753799ff1cc6c93">anonymous{RISCVCodeGenPrepare.cpp}::RISCVCodeGenPrepare::visitAnd</a>, <a href="/web-llvm/docs/api/classes/llvm/instcombinerimpl/#a648710a93ceb0bbddf0a2ae7a8bb2ca5">llvm::InstCombinerImpl::visitAnd</a>, <a href="/web-llvm/docs/api/structs/anonymous-memorysanitizer-cpp-/memorysanitizervisitor/#a27c9f05f074b1acd44859e85c1212bc1">anonymous{MemorySanitizer.cpp}::MemorySanitizerVisitor::visitAsmInstruction</a>, <a href="/web-llvm/docs/api/classes/anonymous-lowermatrixintrinsics-cpp-/lowermatrixintrinsics/#aa6977569e4724e3cb0b65e13d0e2a8eb">anonymous{LowerMatrixIntrinsics.cpp}::LowerMatrixIntrinsics::VisitBinaryOperator</a>, <a href="/web-llvm/docs/api/classes/llvm/instcombinerimpl/#a89ab5eaec7693029761c8d0b3ded3b00">llvm::InstCombinerImpl::visitBitCast</a>, <a href="/web-llvm/docs/api/classes/anonymous-dataflowsanitizer-cpp-/dfsanvisitor/#abba8b2d831670c64909cdcb0190fa6d9">anonymous{DataFlowSanitizer.cpp}::DFSanVisitor::visitBitCastInst</a>, <a href="/web-llvm/docs/api/classes/anonymous-scalarizer-cpp-/scalarizervisitor/#aabb3d90405099bce8007a11942f3ab92">anonymous{Scalarizer.cpp}::ScalarizerVisitor::visitBitCastInst</a>, <a href="/web-llvm/docs/api/classes/anonymous-scalarizer-cpp-/scalarizervisitor/#a48bf838fb202d25d6b13ba8048182fba">anonymous{Scalarizer.cpp}::ScalarizerVisitor::visitCastInst</a>, <a href="/web-llvm/docs/api/classes/anonymous-scalarizer-cpp-/scalarizervisitor/#a16eb5732b0dacdde9b666ba69f630a16">anonymous{Scalarizer.cpp}::ScalarizerVisitor::visitExtractElementInst</a>, <a href="/web-llvm/docs/api/classes/llvm/instcombinerimpl/#a71ef354bd1ea9e02d70146d7218a7d39">llvm::InstCombinerImpl::visitExtractElementInst</a>, <a href="/web-llvm/docs/api/classes/anonymous-scalarizer-cpp-/scalarizervisitor/#aee075a4b7e853e004ad694f7ef959f28">anonymous{Scalarizer.cpp}::ScalarizerVisitor::visitExtractValueInst</a>, <a href="/web-llvm/docs/api/classes/llvm/instcombinerimpl/#a86b0437dceb8e39c8185dc7def325011">llvm::InstCombinerImpl::visitFCmpInst</a>, <a href="/web-llvm/docs/api/classes/anonymous-amdgpucodegenprepare-cpp-/amdgpucodegenprepareimpl/#ae534b46b7607eb604ddd8c66baa8d2d1">anonymous{AMDGPUCodeGenPrepare.cpp}::AMDGPUCodeGenPrepareImpl::visitFDiv</a>, <a href="/web-llvm/docs/api/classes/llvm/instcombinerimpl/#a7eb1707b3b9ea994955ac9d230535261">llvm::InstCombinerImpl::visitFPTrunc</a>, <a href="/web-llvm/docs/api/classes/anonymous-scalarizer-cpp-/scalarizervisitor/#ac6bed7ccafa0ac0022efe4b392497224">anonymous{Scalarizer.cpp}::ScalarizerVisitor::visitGetElementPtrInst</a>, <a href="/web-llvm/docs/api/classes/datascalarizervisitor/#a32bd3fc6040488f54b8fb322216218a5">DataScalarizerVisitor::visitGetElementPtrInst</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/nvptx/nvptxasmprinter-cpp/#ab0cd64194576d6d882ceabaf9b3a2c29">VisitGlobalVariableForEmission</a>, <a href="/web-llvm/docs/api/namespaces/anonymous-mergeicmps-cpp-/#aaa39273101436002f3e3bd16293327be">anonymous{MergeICmps.cpp}::visitICmp</a>, <a href="/web-llvm/docs/api/classes/anonymous-scalarizer-cpp-/scalarizervisitor/#a013a34181c208fa05a664e3f27bbad95">anonymous{Scalarizer.cpp}::ScalarizerVisitor::visitInsertElementInst</a>, <a href="/web-llvm/docs/api/classes/llvm/instcombinerimpl/#a9567d315d63f844326900f461f5b3d7a">llvm::InstCombinerImpl::visitIntToPtr</a>, <a href="/web-llvm/docs/api/classes/anonymous-amdgpulowerbufferfatpointers-cpp-/splitptrstructs/#a180c318fe2fe1f2f7d4f4ca4dccfd2f1">anonymous{AMDGPULowerBufferFatPointers.cpp}::SplitPtrStructs::visitIntToPtrInst</a>, <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/scalar/indvarsimplify-cpp/#a57aff0646c7151c4158d839c386332cc">visitIVCast</a>, <a href="/web-llvm/docs/api/classes/llvm/instcombinerimpl/#a7af99fa2202fcc7db245865dd1bcec1f">llvm::InstCombinerImpl::visitLandingPadInst</a>, <a href="/web-llvm/docs/api/classes/anonymous-dxilflattenarrays-cpp-/dxilflattenarraysvisitor/#a9498339e26b296572a463a1300bf1a13">anonymous{DXILFlattenArrays.cpp}::DXILFlattenArraysVisitor::visitLoadInst</a>, <a href="/web-llvm/docs/api/classes/datascalarizervisitor/#a7c94d0952ba1d6986f0e78b62c303074">DataScalarizerVisitor::visitLoadInst</a>, <a href="/web-llvm/docs/api/classes/llvm/instcombinerimpl/#a3ba96a0d49ec5f1a062b075f54536a3c">llvm::InstCombinerImpl::visitLoadInst</a>, <a href="/web-llvm/docs/api/classes/llvm/instcombinerimpl/#a01ed915fb2acf9fd660ca752edeec0db">llvm::InstCombinerImpl::visitMul</a>, <a href="/web-llvm/docs/api/classes/llvm/instcombinerimpl/#a752efe4724ac3a97d07ee81d5f779c92">llvm::InstCombinerImpl::visitPHINode</a>, <a href="/web-llvm/docs/api/classes/llvm/instcombinerimpl/#a2a5120238e6845643a37d5a4675a5342">llvm::InstCombinerImpl::visitSExt</a>, <a href="/web-llvm/docs/api/classes/llvm/instcombinerimpl/#a90fcdfa591c9bd0cf511f2803198b355">llvm::InstCombinerImpl::visitShl</a>, <a href="/web-llvm/docs/api/classes/anonymous-scalarizer-cpp-/scalarizervisitor/#a22ba91d5d49420a24b01342672953762">anonymous{Scalarizer.cpp}::ScalarizerVisitor::visitShuffleVectorInst</a>, <a href="/web-llvm/docs/api/classes/llvm/instcombinerimpl/#ad31108b4f7156db7565eadba1285c93a">llvm::InstCombinerImpl::visitShuffleVectorInst</a>, <a href="/web-llvm/docs/api/classes/llvm/instcombinerimpl/#a5c5efa376b5dcc0c0b0628d89882a498">llvm::InstCombinerImpl::visitSIToFP</a>, <a href="/web-llvm/docs/api/classes/anonymous-amdgpucodegenprepare-cpp-/amdgpucodegenprepareimpl/#ae42afee90ff90eb3b8fa78ad91d8858b">anonymous{AMDGPUCodeGenPrepare.cpp}::AMDGPUCodeGenPrepareImpl::visitSqrt</a>, <a href="/web-llvm/docs/api/classes/llvm/instcombinerimpl/#a43a1d060dacb05eb645cf91ea86d7bd3">llvm::InstCombinerImpl::visitTrunc</a>, <a href="/web-llvm/docs/api/classes/llvm/instcombinerimpl/#a4d45f96f90c7ddd805c6bae2949077de">llvm::InstCombinerImpl::visitUIToFP</a>, <a href="/web-llvm/docs/api/classes/anonymous-lowermatrixintrinsics-cpp-/lowermatrixintrinsics/#a851ca1290a8ae078a9e084871aa2e9d7">anonymous{LowerMatrixIntrinsics.cpp}::LowerMatrixIntrinsics::VisitUnaryOperator</a>, <a href="/web-llvm/docs/api/classes/llvm/instcombinerimpl/#a2175862566372c3684fe4f7bf62e3143">llvm::InstCombinerImpl::visitZExt</a> and <a href="/web-llvm/docs/api/classes/anonymous-simplifyindvar-cpp-/wideniv/#acd093283d4e8d1301859f0a98a157680">anonymous{SimplifyIndVar.cpp}::WidenIV::widenWithVariantUse</a>.</p>

</div>
</div>

### getOperandList() {#a024c7e10ce431a93ffdb4e5e6401e0be}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">const Use * llvm::User::getOperandList ()</td>
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



<p>Definition at line 221 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/ir/user-h">User.h</a>.</p>


<p>Reference <a href="/web-llvm/docs/api/classes/llvm/value/#abe68086704afcf3325b6b9b14ca4b625">llvm::Value::HasHungOffUses</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/classes/llvm/landingpadinst/#a3a936522e13d33927dc23f0488e421d8">llvm::LandingPadInst::addClause</a>, <a href="/web-llvm/docs/api/classes/llvm/indirectbrinst/#a08b418bd465a9f2ff316beb04005f6d7">llvm::IndirectBrInst::addDestination</a>, <a href="/web-llvm/docs/api/classes/llvm/catchswitchinst/#a4b1438bbee79540a0cca9a2c018b71ec">llvm::CatchSwitchInst::addHandler</a>, <a href="/web-llvm/docs/api/classes/llvm/landingpadinst/#a836dacc5f24807bbc216145ff7de36ab">llvm::LandingPadInst::getClause</a>, <a href="#aa0a2cb1582d1cec317bd205085469ca1">getOperand</a>, <a href="#a6b69f170344729a16c5f3bbf89aea84d">getOperandUse</a>, <a href="#a3f3b252f63d32a9a6e05208ce26562bf">getOperandUse</a>, <a href="/web-llvm/docs/api/classes/llvm/landingpadinst/#a74e94530fdc21fe0a7eb5465437c980f">llvm::LandingPadInst::isCatch</a>, <a href="/web-llvm/docs/api/classes/llvm/landingpadinst/#a794866f5c0f6877de0b1dd863ceaf93e">llvm::LandingPadInst::isFilter</a>, <a href="#a2eeb1c7ed1cfe403f2ae0470e36c07e2">op_begin</a>, <a href="#a418704eb3b3a706e679e0a2d42b5dc7c">op_begin</a>, <a href="#af41f58e730804d10b91fcff39b035f74">op_end</a>, <a href="#a49d32fbcf8305d76cfff528214a4eca0">op_end</a>, <a href="/web-llvm/docs/api/classes/llvm/switchinst/#aff8bc09200ccc3617a5cb37e0d2f23ff">llvm::SwitchInst::removeCase</a>, <a href="/web-llvm/docs/api/classes/llvm/indirectbrinst/#ac0cc9b34e16910d245245642350d4456">llvm::IndirectBrInst::removeDestination</a>, <a href="#a5fa9b8e1842b354f64c1ba6be0a4a17f">setOperand</a> and <a href="#a282fa3e9586425313e0a954c18deee15">User</a>.</p>

</div>
</div>

### getOperandList() {#a6155b029eaffe271cf2a711141fbd0e3}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">Use * llvm::User::getOperandList ()</td>
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



<p>Definition at line 224 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/ir/user-h">User.h</a>.</p>


<p>Reference <a href="#a282fa3e9586425313e0a954c18deee15">User</a>.</p>

</div>
</div>

### getOperandUse() {#a3f3b252f63d32a9a6e05208ce26562bf}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">const Use &amp; llvm::User::getOperandUse (unsigned i)</td>
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



<p>Definition at line 241 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/ir/user-h">User.h</a>.</p>


<p>References <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/silowercontrolflow-cpp/#a4868c5d81c5ccc98c47aeab6244346a0">assert</a>, <a href="#a024c7e10ce431a93ffdb4e5e6401e0be">getOperandList</a> and <a href="/web-llvm/docs/api/classes/llvm/value/#ab9ef1cd0d25962bbb4785ae14258ed5d">llvm::Value::NumUserOperands</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/utils/simplifycfg-cpp/#ae9efb27478c86bece81f1bf5bca2d348">canSinkInstructions</a>, <a href="/web-llvm/docs/api/files/lib/lib/codegen/codegenprepare-cpp/#adfad68845808cb6acd116e50b15bc281">despeculateCountZeros</a>, <a href="/web-llvm/docs/api/classes/llvm/sitargetlowering/#aa7f6ff2830d775cf0c6a4052836c2552">llvm::SITargetLowering::emitExpandAtomicAddrSpacePredicate</a>, <a href="/web-llvm/docs/api/classes/anonymous-inductiverangecheckelimination-cpp-/inductiverangecheck/#a715a08cb04246d426e200c8196ecf0ea">anonymous{InductiveRangeCheckElimination.cpp}::InductiveRangeCheck::extractRangeChecksFromBranch</a>, <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/utils/lcssa-cpp/#a03040e4a441982ab96f070a7f03cc910">formLCSSAForInstructionsImpl</a>, <a href="/web-llvm/docs/api/classes/llvm/callbase/#a2f7ef00950294f037ed4b63aa7ebfa0b">llvm::CallBase::getArgOperandUse</a>, <a href="/web-llvm/docs/api/classes/llvm/callbase/#aa1c6e6fdb0e2812d7f3b97ae16caeb44">llvm::CallBase::getArgOperandUse</a>, <a href="/web-llvm/docs/api/classes/llvm/abstractcallsite/#a377c884b7ab6a21ce8f1113da49094f1">llvm::AbstractCallSite::getCalleeUseForCallback</a>, <a href="/web-llvm/docs/api/classes/anonymous-safepointirverifier-cpp-/cfgdeadness/#a7839b6e2958308f5941b95e49c69b1e8">anonymous{SafepointIRVerifier.cpp}::CFGDeadness::getEdge</a>, <a href="/web-llvm/docs/api/classes/llvm/callbrinst/#a7929a2a96611a7af6f8a0f45d823c2b3">llvm::CallBrInst::getIndirectDestLabelUse</a>, <a href="/web-llvm/docs/api/classes/anonymous-safepointirverifier-cpp-/cfgdeadness/#abafc68a948c0a4deac7648103a979a70">anonymous{SafepointIRVerifier.cpp}::CFGDeadness::hasLiveIncomingEdges</a>, <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/scalar/licm-cpp/#a697cde840957bbc0b2848a593c3e0d5a">hoistMulAddAssociation</a>, <a href="/web-llvm/docs/api/files/lib/lib/codegen/globalmergefunctions-cpp/#ad9f376137b3a3160390ab81821f205f6">isCalleeOperand</a>, <a href="/web-llvm/docs/api/classes/llvm/aarch64ttiimpl/#a2bfff40c1bfc02a21a5ed0b64a99f8a2">llvm::AArch64TTIImpl::isProfitableToSinkOperands</a>, <a href="/web-llvm/docs/api/classes/llvm/armttiimpl/#a0eee77cb45ab15bd00718f8801a3fc53">llvm::ARMTTIImpl::isProfitableToSinkOperands</a>, <a href="/web-llvm/docs/api/structs/anonymous-attributorattributes-cpp-/aaisdeadreturned/#a5fbd0b238ec5abc8ab5dbc065b002c7a">anonymous{AttributorAttributes.cpp}::AAIsDeadReturned::manifest</a>, <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/scalar/correlatedvaluepropagation-cpp/#aae58203af8c9b9d7e5551badc9094d90">processAShr</a>, <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/scalar/correlatedvaluepropagation-cpp/#aaa116d55b70fa3716c4ee6f0eb3488d8">processCmpIntrinsic</a>, <a href="/web-llvm/docs/api/classes/anonymous-safepointirverifier-cpp-/cfgdeadness/#a9bcd938340c81deac2844875dfd6086e">anonymous{SafepointIRVerifier.cpp}::CFGDeadness::processFunction</a>, <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/scalar/correlatedvaluepropagation-cpp/#a6d4d9e7eb49fd2f51ffcb0596b37c596">processMinMaxIntrinsic</a>, <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/scalar/correlatedvaluepropagation-cpp/#ad47460e620c33c83309f749ea8f34c6b">processSExt</a>, <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/scalar/correlatedvaluepropagation-cpp/#ace24fe825742577e78df32f725ad7b26">processSIToFP</a>, <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/scalar/inferaddressspaces-cpp/#a1924b531241bed91254345513fce314f">replaceOperandIfSame</a>, <a href="/web-llvm/docs/api/classes/anonymous-canonicalizefreezeinloops-cpp-/canonicalizefreezeinloopsimpl/#aff534de0962628bba1821ef3c0821308">anonymous{CanonicalizeFreezeInLoops.cpp}::CanonicalizeFreezeInLoopsImpl::run</a>, <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/utils/simplifycfg-cpp/#abf69483b802f1e342399912142341c60">sinkLastInstruction</a> and <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/scalar/correlatedvaluepropagation-cpp/#a52da671999cb61370bfe5c7e9fee966f">willNotOverflow</a>.</p>

</div>
</div>

### getOperandUse() {#a6b69f170344729a16c5f3bbf89aea84d}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">Use &amp; llvm::User::getOperandUse (unsigned i)</td>
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



<p>Definition at line 245 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/ir/user-h">User.h</a>.</p>


<p>References <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/silowercontrolflow-cpp/#a4868c5d81c5ccc98c47aeab6244346a0">assert</a>, <a href="#a024c7e10ce431a93ffdb4e5e6401e0be">getOperandList</a> and <a href="/web-llvm/docs/api/classes/llvm/value/#ab9ef1cd0d25962bbb4785ae14258ed5d">llvm::Value::NumUserOperands</a>.</p>

</div>
</div>

### isDroppable() {#af6a49991304b167c94f4a9756d3fd48f}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool llvm::User::isDroppable ()</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>A droppable user is a user for which uses can be dropped without affecting correctness and should be dropped rather than preventing a transformation from happening.</p>

<p>Declaration at line 270 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/ir/user-h">User.h</a>, definition at line 115 of file <a href="/web-llvm/docs/api/files/lib/lib/sandboxir/user-cpp">User.cpp</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/utils/promotememorytoregister-cpp/#a82f896385cac84a2e477159ad31ace74">removeIntrinsicUsers</a>, <a href="/web-llvm/docs/api/classes/llvm/instcombinerimpl/#ac5d3cfa0755b34bcbd3f2298e9fa28ed">llvm::InstCombinerImpl::run</a> and <a href="/web-llvm/docs/api/structs/anonymous-attributorattributes-cpp-/aamemorybehaviorfloating/#a31f2a80a770f0aa93c1fab42e9d41407">anonymous{AttributorAttributes.cpp}::AAMemoryBehaviorFloating::updateImpl</a>.</p>

</div>
</div>

### op\_begin() {#a2eeb1c7ed1cfe403f2ae0470e36c07e2}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">op_iterator llvm::User::op_begin ()</td>
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



<p>Definition at line 280 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/ir/user-h">User.h</a>.</p>


<p>Reference <a href="#a024c7e10ce431a93ffdb4e5e6401e0be">getOperandList</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/classes/llvm/callbase/#a4fb513d744ca72275932b2c7003f16f6">llvm::CallBase::arg_begin</a>, <a href="/web-llvm/docs/api/classes/llvm/funcletpadinst/#a0e8c14ca40c93e68a85fdb1c6b5bb264">llvm::FuncletPadInst::arg_operands</a>, <a href="/web-llvm/docs/api/classes/llvm/funcletpadinst/#af82801d1b464636a280b7c6ce3e87c15">llvm::FuncletPadInst::arg_operands</a>, <a href="/web-llvm/docs/api/classes/llvm/memoryphi/#af709830d69338472c10f3110975a065d">llvm::MemoryPhi::block_begin</a>, <a href="/web-llvm/docs/api/classes/llvm/memoryphi/#a3f227e9887141006973ecb94e027d67d">llvm::MemoryPhi::block_begin</a>, <a href="/web-llvm/docs/api/classes/llvm/phinode/#a47670479395f375c7501109d25cb475f">llvm::PHINode::block_begin</a>, <a href="/web-llvm/docs/api/classes/llvm/constantaggregate/#abecd8e154b2d3fb93c6b32596a899fc5">llvm::ConstantAggregate::ConstantAggregate</a>, <a href="/web-llvm/docs/api/classes/llvm/callbase/#a3085b56a4d6537a84c58e62e535adb71">llvm::CallBase::data_operands_begin</a>, <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/instcombine/instructioncombining-cpp/#ad12cb02e2ee53655e834dcb84cd57333">foldGEPOfPhi</a>, <a href="/web-llvm/docs/api/classes/llvm/instcombinerimpl/#acc9feb478a72bb822133b6eec00bef9f">llvm::InstCombinerImpl::foldPHIArgGEPIntoPHI</a>, <a href="/web-llvm/docs/api/classes/llvm/memoryphi/#a159e11bdff83fe6a5cf8ce8853adaac4">llvm::MemoryPhi::getIncomingBlock</a>, <a href="/web-llvm/docs/api/classes/llvm/phinode/#ae7e053d6c8abe52081095ae208263ee9">llvm::PHINode::getIncomingBlock</a>, <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/vectorize/slpvectorizer-cpp/#acb2c6a8dafac1cdf8927e67b28baab1c">getSameOpcode</a>, <a href="/web-llvm/docs/api/classes/llvm/constantexpr/#aab577cba8223fe4bb96df5591d49d98a">llvm::ConstantExpr::getWithOperands</a>, <a href="/web-llvm/docs/api/classes/llvm/catchswitchinst/#aca67373088fb518e1fa42d7c0f9342be">llvm::CatchSwitchInst::handler_begin</a>, <a href="/web-llvm/docs/api/classes/llvm/catchswitchinst/#a399078b56a421ae40a7db543e53a048b">llvm::CatchSwitchInst::handler_begin</a>, <a href="/web-llvm/docs/api/classes/llvm/gepoperator/#a9d4f83fc113ed4b161e4e89743efb1e4">llvm::GEPOperator::idx_begin</a>, <a href="/web-llvm/docs/api/classes/llvm/gepoperator/#a355becb10a5cb4996c4e543600db7d94">llvm::GEPOperator::idx_begin</a>, <a href="/web-llvm/docs/api/classes/llvm/getelementptrinst/#aceaa5a2bd964e34d0dbf3ed1f146abc7">llvm::GetElementPtrInst::idx_begin</a>, <a href="/web-llvm/docs/api/classes/llvm/getelementptrinst/#ad40c0b0e469caee40b5a87d508e7ce3b">llvm::GetElementPtrInst::idx_begin</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/spirv/spirvregularizer-cpp/#a70c9d5004bb64ce7c4ed2dab4acda63b">INITIALIZE_PASS</a>, <a href="/web-llvm/docs/api/classes/llvm/callbase/#a5fb497a3113f10b593158ab55bfd1e1c">llvm::CallBase::isBundleOperand</a>, <a href="/web-llvm/docs/api/classes/llvm/callbase/#a1b6cd42ee6d8d51324f79e5e5e5d5f74">llvm::CallBase::operandBundleFromBundleOpInfo</a>, <a href="#a0b931781aa589c6ebe64a76c1447e5b2">operands</a>, <a href="#acbac91af886d94a4cd0b41c506f7051b">operands</a>, <a href="/web-llvm/docs/api/classes/llvm/callbase/#a93f122dff654f8336680531a3898375c">llvm::CallBase::populateBundleOperandInfos</a>, <a href="/web-llvm/docs/api/classes/llvm/phinode/#a6f01dbe965b38186b1a78378689d4105">llvm::PHINode::removeIncomingValue</a>, <a href="/web-llvm/docs/api/classes/llvm/innerloopvectorizer/#a0a5c60e5cebd520f95b9813fd9807016">llvm::InnerLoopVectorizer::sinkScalarOperands</a>, <a href="/web-llvm/docs/api/structs/anonymous-assumebundlebuilder-cpp-/assumebuilderstate/#aba1e9ea5dd5dfc2b1559cb6cef8b4854">anonymous{AssumeBundleBuilder.cpp}::AssumeBuilderState::tryToPreserveWithoutAddingAssume</a>, <a href="#ad93396a26f6fd589ed400bb280319836">value_op_begin</a> and <a href="#a7018c8ee154176141c4c5c055bd341c6">value_op_begin</a>.</p>

</div>
</div>

### op\_begin() {#a418704eb3b3a706e679e0a2d42b5dc7c}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">const_op_iterator llvm::User::op_begin ()</td>
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



<p>Definition at line 281 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/ir/user-h">User.h</a>.</p>


<p>Reference <a href="#a024c7e10ce431a93ffdb4e5e6401e0be">getOperandList</a>.</p>

</div>
</div>

### op\_end() {#af41f58e730804d10b91fcff39b035f74}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">op_iterator llvm::User::op_end ()</td>
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



<p>Definition at line 282 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/ir/user-h">User.h</a>.</p>


<p>References <a href="#a024c7e10ce431a93ffdb4e5e6401e0be">getOperandList</a> and <a href="/web-llvm/docs/api/classes/llvm/value/#ab9ef1cd0d25962bbb4785ae14258ed5d">llvm::Value::NumUserOperands</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/classes/llvm/funcletpadinst/#a0e8c14ca40c93e68a85fdb1c6b5bb264">llvm::FuncletPadInst::arg_operands</a>, <a href="/web-llvm/docs/api/classes/llvm/funcletpadinst/#af82801d1b464636a280b7c6ce3e87c15">llvm::FuncletPadInst::arg_operands</a>, <a href="/web-llvm/docs/api/classes/llvm/callbase/#a8448c3e780b73347f00055dbbbc98a47">llvm::CallBase::data_operands_end</a>, <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/instcombine/instructioncombining-cpp/#ad12cb02e2ee53655e834dcb84cd57333">foldGEPOfPhi</a>, <a href="/web-llvm/docs/api/classes/llvm/instcombinerimpl/#acc9feb478a72bb822133b6eec00bef9f">llvm::InstCombinerImpl::foldPHIArgGEPIntoPHI</a>, <a href="/web-llvm/docs/api/classes/llvm/catchswitchinst/#aaf71dcc496858ab263fec095ca47448a">llvm::CatchSwitchInst::handler_end</a>, <a href="/web-llvm/docs/api/classes/llvm/catchswitchinst/#ab88baa637990c50eee5f350f29e98130">llvm::CatchSwitchInst::handler_end</a>, <a href="/web-llvm/docs/api/classes/llvm/gepoperator/#a630f2e601df642f71613ccf6d7ea889c">llvm::GEPOperator::idx_end</a>, <a href="/web-llvm/docs/api/classes/llvm/gepoperator/#a165208bc52bf227e27432d2ca5c59943">llvm::GEPOperator::idx_end</a>, <a href="/web-llvm/docs/api/classes/llvm/getelementptrinst/#a63d9ee4f6ab51fd7586c7ad7510a5b33">llvm::GetElementPtrInst::idx_end</a>, <a href="/web-llvm/docs/api/classes/llvm/getelementptrinst/#aed425c9ff7fbca1ee04f841c7ed0b2b2">llvm::GetElementPtrInst::idx_end</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/spirv/spirvregularizer-cpp/#a70c9d5004bb64ce7c4ed2dab4acda63b">INITIALIZE_PASS</a>, <a href="#a0b931781aa589c6ebe64a76c1447e5b2">operands</a>, <a href="#acbac91af886d94a4cd0b41c506f7051b">operands</a>, <a href="/web-llvm/docs/api/classes/llvm/catchswitchinst/#aea4f52695ae91c16ae1269f91caf4d5f">llvm::CatchSwitchInst::removeHandler</a>, <a href="/web-llvm/docs/api/classes/llvm/phinode/#a6f01dbe965b38186b1a78378689d4105">llvm::PHINode::removeIncomingValue</a>, <a href="/web-llvm/docs/api/classes/llvm/phinode/#a5197ef3eec835595e81bcecb4ee02969">llvm::PHINode::removeIncomingValueIf</a>, <a href="/web-llvm/docs/api/classes/llvm/innerloopvectorizer/#a0a5c60e5cebd520f95b9813fd9807016">llvm::InnerLoopVectorizer::sinkScalarOperands</a>, <a href="#a5d1730a173d0a69624b80e1e22e6d225">value_op_end</a> and <a href="#af4e94f12cf6145d21c3acc13c4f557ab">value_op_end</a>.</p>

</div>
</div>

### op\_end() {#a49d32fbcf8305d76cfff528214a4eca0}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">const_op_iterator llvm::User::op_end ()</td>
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



<p>Definition at line 285 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/ir/user-h">User.h</a>.</p>


<p>References <a href="#a024c7e10ce431a93ffdb4e5e6401e0be">getOperandList</a> and <a href="/web-llvm/docs/api/classes/llvm/value/#ab9ef1cd0d25962bbb4785ae14258ed5d">llvm::Value::NumUserOperands</a>.</p>

</div>
</div>

### operand\_values() {#ae9c77e5d2298423b0699e93642d17f0c}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">iterator_range&lt; value_op_iterator &gt; llvm::User::operand_values ()</td>
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



<p>Definition at line 312 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/ir/user-h">User.h</a>.</p>


<p>References <a href="/web-llvm/docs/api/namespaces/llvm/#a341215803e83773a3e97860dc291f121">llvm::make_range</a>, <a href="#ad93396a26f6fd589ed400bb280319836">value_op_begin</a> and <a href="#a5d1730a173d0a69624b80e1e22e6d225">value_op_end</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/classes/llvm/gepoperator/#a5c00e7e76ef5e98c6ffec8d31f63970a">llvm::GEPOperator::accumulateConstantOffset</a>, <a href="/web-llvm/docs/api/classes/llvm/constant/#a5a4d3145c046afe97789b9739a200971">llvm::Constant::isManifestConstant</a>, <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/coroutines/coroelide-cpp/#af24b62f595dff4d0a3f8de923bbb7797">operandReferences</a> and <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/scalar/rewritestatepointsforgc-cpp/#a948aaf9d2ae438b3e2369223f55ec841">rematerializeChain</a>.</p>

</div>
</div>

### operand\_values() {#ac493cefe3e5d3113828e0720bb16b85f}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">iterator_range&lt; const_value_op_iterator &gt; llvm::User::operand_values ()</td>
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



<p>Definition at line 333 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/ir/user-h">User.h</a>.</p>


<p>References <a href="/web-llvm/docs/api/namespaces/llvm/#a341215803e83773a3e97860dc291f121">llvm::make_range</a>, <a href="#ad93396a26f6fd589ed400bb280319836">value_op_begin</a> and <a href="#a5d1730a173d0a69624b80e1e22e6d225">value_op_end</a>.</p>

</div>
</div>

### operands() {#a0b931781aa589c6ebe64a76c1447e5b2}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">op_range llvm::User::operands ()</td>
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



<p>Definition at line 288 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/ir/user-h">User.h</a>.</p>


<p>References <a href="#a2eeb1c7ed1cfe403f2ae0470e36c07e2">op_begin</a> and <a href="#af41f58e730804d10b91fcff39b035f74">op_end</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/utils/simplifycfg-cpp/#a47aa12b3f79390c9835ac99904b2cb51">areIdenticalUpToCommutativity</a>, <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/utils/simplifylibcalls-cpp/#ae56877b571bfd107841dabb130c9f2ca">callHasFloatingPointArgument</a>, <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/utils/simplifylibcalls-cpp/#ae817e73e41b3b26068e6b8a50cd447af">callHasFP128Argument</a>, <a href="/web-llvm/docs/api/classes/anonymous-mergeicmps-cpp-/bcecmpblock/#a851916c7b9610597c4339a0d74f8e449">anonymous{MergeICmps.cpp}::BCECmpBlock::canSinkBCECmpInst</a>, <a href="/web-llvm/docs/api/namespaces/llvm/objcarc/#af467748c4e634ace0c19cbbeb0af5fee">llvm::objcarc::CanUse</a>, <a href="/web-llvm/docs/api/namespaces/anonymous-nvptxctordtorlowering-cpp-/#aab0bb9923065afc9aca06aec133ff91e">anonymous{NVPTXCtorDtorLowering.cpp}::createInitOrFiniGlobals</a>, <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/utils/rellookuptableconverter-cpp/#a1ca1f5b41c1408be83df43ab024cdd69">createRelLookupTable</a>, <a href="/web-llvm/docs/api/structs/anonymous-deadstoreelimination-cpp-/dsestate/#a32e5e2e67b52bcd45fef4487f664f9ec">anonymous{DeadStoreElimination.cpp}::DSEState::deleteDeadInstruction</a>, <a href="#a48ec5fcee6d2c17c723e8e67f169f948">dropAllReferences</a>, <a href="/web-llvm/docs/api/classes/llvm/webassemblyasmprinter/#aedbc3a6b1ed39b77650edac4239774cf">llvm::WebAssemblyAsmPrinter::EmitFunctionAttributes</a>, <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/utils/ctorutils-cpp/#aac8ef9c8745bf77faa38eb1cd16fb4a7">findGlobalCtors</a>, <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/instcombine/instructioncombining-cpp/#ad12cb02e2ee53655e834dcb84cd57333">foldGEPOfPhi</a>, <a href="/web-llvm/docs/api/classes/llvm/instcombinerimpl/#a2fc50d227d302eb98914f04bcc6634e1">llvm::InstCombinerImpl::foldOpIntoPhi</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a2e4b18daaf5f20f1ade3a9f66b86d843">llvm::FoldReturnIntoUncondBranch</a>, <a href="/web-llvm/docs/api/classes/anonymous-vectorcombine-cpp-/scalarizationresult/#a8f82e0f7727e14383b5983a7bb15ada5">anonymous{VectorCombine.cpp}::ScalarizationResult::freeze</a>, <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/instcombine/instcombinephi-cpp/#a2e25b4d49c29e587a6a408e19f57ab0e">getAnyNonZeroConstInt</a>, <a href="/web-llvm/docs/api/classes/llvm/constantexpr/#af9fc0080b4accc0b19bfbbc624701e30">llvm::ConstantExpr::getAsInstruction</a>, <a href="/web-llvm/docs/api/files/lib/lib/analysis/scalarevolution-cpp/#af278ae155bd811822054e98b8f056c56">getConstantEvolvingPHIOperands</a>, <a href="/web-llvm/docs/api/classes/llvm/scevexpander/#aece02adc8e4cc74296bfe410eabe287b">llvm::SCEVExpander::getIVIncOperand</a>, <a href="/web-llvm/docs/api/classes/llvm/slpvectorizer/boupslp/#aee3b49d7f15550d64c7db0e29a124c6d">llvm::slpvectorizer::BoUpSLP::getSpillCost</a>, <a href="/web-llvm/docs/api/classes/anonymous-structuralhash-cpp-/structuralhashimpl/#ac2717c2132c268d29f71c5c86cc40971">anonymous{StructuralHash.cpp}::StructuralHashImpl::hashInstruction</a>, <a href="/web-llvm/docs/api/classes/llvm/memoryphi/#acbd808882e7deaaf05f04a9e259c961a">llvm::MemoryPhi::incoming_values</a>, <a href="/web-llvm/docs/api/classes/llvm/memoryphi/#a7b2f62d1da7a099812c689cf6fab35cb">llvm::MemoryPhi::incoming_values</a>, <a href="/web-llvm/docs/api/classes/llvm/phinode/#a1f0ff79b64a40d383b891f1baba89c6b">llvm::PHINode::incoming_values</a>, <a href="/web-llvm/docs/api/classes/llvm/phinode/#acff13ccb2e98a629e06757110178665f">llvm::PHINode::incoming_values</a>, <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/utils/codeextractor-cpp/#a5a7fe53bda3cbce584280a177a18d5ab">isBlockValidForExtraction</a>, <a href="/web-llvm/docs/api/files/lib/lib/analysis/valuetracking-cpp/#a50882a093546a573f3e879fc578f167d">isPowerOfTwoRecurrence</a>, <a href="/web-llvm/docs/api/classes/anonymous-lowertypetests-cpp-/lowertypetestsmodule/#a41245c88cdf19ddbfe8a2dffba0a500d">anonymous{LowerTypeTests.cpp}::LowerTypeTestsModule::LowerTypeTestsModule</a>, <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/utils/simplifycfg-cpp/#acc8066950deec241b4fafe0700ff5f2c">mergeCompatibleInvokesImpl</a>, <a href="/web-llvm/docs/api/classes/llvm/loopinfo/#aee580d948709366b6a676f8b48460137">llvm::LoopInfo::movementPreservesLCSSAForm</a>, <a href="/web-llvm/docs/api/files/lib/lib/analysis/memoryssaupdater-cpp/#af38807ff8788bf371c9e216dd5ac6206">onlySingleValue</a>, <a href="/web-llvm/docs/api/classes/anonymous-spirvasmprinter-cpp-/spirvasmprinter/#aef83676a470a77d6e089737fb024de94">anonymous{SPIRVAsmPrinter.cpp}::SPIRVAsmPrinter::outputAnnotations</a>, <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/utils/ctorutils-cpp/#a30e49f13bd17ed097579ddf598241386">parseGlobalCtors</a>, <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/scalar/simplifycfgpass-cpp/#aec97a6e447a45c9027b71a487f5732ec">performBlockTailMerging</a>, <a href="/web-llvm/docs/api/classes/llvm/memoryphi/#ad75b48c94bacfc6a1d166164bd51af8b">llvm::MemoryPhi::print</a>, <a href="/web-llvm/docs/api/classes/llvm/phinode/#a5197ef3eec835595e81bcecb4ee02969">llvm::PHINode::removeIncomingValueIf</a>, <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/utils/lowerglobaldtors-cpp/#aa2a67dbc6220273da3430b0a15735487">runImpl</a>, <a href="/web-llvm/docs/api/classes/anonymous-codegenprepare-cpp-/vectorpromotehelper/#aa46482c59b5d71b890df4cfaada1e6c7">anonymous{CodeGenPrepare.cpp}::VectorPromoteHelper::shouldPromote</a>, <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/instcombine/instcombinephi-cpp/#a86ed982844e004af01652f203eda23c0">simplifyUsingControlFlow</a>, <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/scalar/loopinterchange-cpp/#ae5687ce1ab4b7719d53c0173d87355aa">updateSuccessor</a>, <a href="/web-llvm/docs/api/files/lib/lib/analysis/lazyvalueinfo-cpp/#a7313a8e8cc1cfd30545ed00b1eb3a11d">usesOperand</a> and <a href="/web-llvm/docs/api/structs/llvm/vplantransforms/#ad210afaefb4884ac5008dd5fbaf1cbf8">llvm::VPlanTransforms::VPInstructionsToVPRecipes</a>.</p>

</div>
</div>

### operands() {#acbac91af886d94a4cd0b41c506f7051b}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">const_op_range llvm::User::operands ()</td>
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



<p>Definition at line 291 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/ir/user-h">User.h</a>.</p>


<p>References <a href="#a2eeb1c7ed1cfe403f2ae0470e36c07e2">op_begin</a> and <a href="#af41f58e730804d10b91fcff39b035f74">op_end</a>.</p>

</div>
</div>

### replaceUsesOfWith() {#a1600c7959045cb6b6a5f5a1d427ec67e}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool llvm::User::replaceUsesOfWith (<a href="/web-llvm/docs/api/classes/llvm/value">Value</a> * From, <a href="/web-llvm/docs/api/classes/llvm/value">Value</a> * To)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Replace uses of one <a href="/web-llvm/docs/api/classes/llvm/value">Value</a> with another.</p>


<p>Replaces all references to the "From" definition with references to the "To" definition. Returns whether any uses were replaced.</p>


<p>Declaration at line 354 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/ir/user-h">User.h</a>, definition at line 21 of file <a href="/web-llvm/docs/api/files/lib/lib/sandboxir/user-cpp">User.cpp</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/utils/callpromotionutils-cpp/#a8c9ae0be5e6bcad90cdf141962a117f3">createRetBitCast</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a6467fad9a534208a2ae56241d19cbba7">llvm::DemotePHIToStack</a>, <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/instcombine/instructioncombining-cpp/#a7b9a62f04a493cc8b8dadc64100578f8">foldOperationIntoSelectOperand</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#ae819b62ec706cb229654ea5fb6553501">llvm::lowerGlobalIFuncUsersAsGlobalCtor</a>, <a href="/web-llvm/docs/api/structs/anonymous-attributorattributes-cpp-/aaindirectcallinfocallsite/#afc99e48bf0eed3b2fc9a2c3b25e3bd73">anonymous{AttributorAttributes.cpp}::AAIndirectCallInfoCallSite::manifest</a>, <a href="/web-llvm/docs/api/namespaces/anonymous-mergeicmps-cpp-/#a5289777e58accae64ebded1a95e4c8b0">anonymous{MergeICmps.cpp}::mergeComparisons</a>, <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/scalar/rewritestatepointsforgc-cpp/#a948aaf9d2ae438b3e2369223f55ec841">rematerializeChain</a>, <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/scalar/rewritestatepointsforgc-cpp/#aa175634946d91981b87f76ed9a583f27">rematerializeLiveValuesAtUses</a>, <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/utils/simplifycfg-cpp/#aedfe10b7b8a1008ddaa4104f54e0b483">removeEmptyCleanup</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/x86/x86loweramxtype-cpp/#a20c7ea50a73d61a91772d1c57f2baade">replaceWithTileLoad</a>, <a href="/web-llvm/docs/api/classes/llvm/loopconstrainer/#af041772a16751b1c52d52ae08cd5046d">llvm::LoopConstrainer::run</a>, <a href="/web-llvm/docs/api/classes/anonymous-simplifyindvar-cpp-/wideniv/#a821be8169bc31b8413a69cd7f22ff9ab">anonymous{SimplifyIndVar.cpp}::WidenIV::truncateIVUse</a>, <a href="/web-llvm/docs/api/namespaces/anonymous-dfajumpthreading-cpp-/#a37fd6f31f78116956f457b105ab4513c">anonymous{DFAJumpThreading.cpp}::unfold</a>, <a href="/web-llvm/docs/api/classes/llvm/slpvectorizer/boupslp/#a99b79343fdc586cce804ebabf3d419e2">llvm::slpvectorizer::BoUpSLP::vectorizeTree</a>, <a href="/web-llvm/docs/api/classes/anonymous-simplifyindvar-cpp-/wideniv/#a39eadf98e4773739cd4e7b4befee6fb5">anonymous{SimplifyIndVar.cpp}::WidenIV::widenIVUse</a> and <a href="/web-llvm/docs/api/classes/anonymous-simplifyindvar-cpp-/wideniv/#aa9eefc297d0b2b8097701f80c06ba19d">anonymous{SimplifyIndVar.cpp}::WidenIV::widenLoopCompare</a>.</p>

</div>
</div>

### setNumHungOffUseOperands() {#a715e8009737f71c4b3d2ea7d2abc33c4}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void llvm::User::setNumHungOffUseOperands (unsigned NumOps)</td>
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

<p>Subclasses with hung off uses need to manage the operand count themselves.</p>


<p>In these instances, the operand count isn't used to find the OperandList, so there's no issue in having the operand count change.</p>


<p>Definition at line 261 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/ir/user-h">User.h</a>.</p>


<p>References <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/demangle/itaniumdemangle-h/#a536e22898d28a9340a4204407a75ad5d">AbstractManglingParser&lt; Derived, Alloc &gt;::NumOps</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/silowercontrolflow-cpp/#a4868c5d81c5ccc98c47aeab6244346a0">assert</a>, <a href="/web-llvm/docs/api/classes/llvm/value/#abe68086704afcf3325b6b9b14ca4b625">llvm::Value::HasHungOffUses</a>, <a href="/web-llvm/docs/api/classes/llvm/value/#ab9ef1cd0d25962bbb4785ae14258ed5d">llvm::Value::NumUserOperands</a> and <a href="/web-llvm/docs/api/classes/llvm/value/#a19833a77591e9d860373ab7fc4793044a6050aee72ddd23b6d91ec3f126679fec">llvm::Value::NumUserOperandsBits</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/classes/llvm/switchinst/#a62abc2475d09c01d583ba24a487898fd">llvm::SwitchInst::addCase</a>, <a href="/web-llvm/docs/api/classes/llvm/landingpadinst/#a3a936522e13d33927dc23f0488e421d8">llvm::LandingPadInst::addClause</a>, <a href="/web-llvm/docs/api/classes/llvm/indirectbrinst/#a08b418bd465a9f2ff316beb04005f6d7">llvm::IndirectBrInst::addDestination</a>, <a href="/web-llvm/docs/api/classes/llvm/catchswitchinst/#a4b1438bbee79540a0cca9a2c018b71ec">llvm::CatchSwitchInst::addHandler</a>, <a href="/web-llvm/docs/api/classes/llvm/memoryphi/#ab9945ed381faa9dbee65a92e6225768d">llvm::MemoryPhi::addIncoming</a>, <a href="/web-llvm/docs/api/classes/llvm/phinode/#a089cccb6f231efee72abc76d0f9c695f">llvm::PHINode::addIncoming</a>, <a href="/web-llvm/docs/api/classes/llvm/switchinst/#aff8bc09200ccc3617a5cb37e0d2f23ff">llvm::SwitchInst::removeCase</a>, <a href="/web-llvm/docs/api/classes/llvm/indirectbrinst/#ac0cc9b34e16910d245245642350d4456">llvm::IndirectBrInst::removeDestination</a>, <a href="/web-llvm/docs/api/classes/llvm/catchswitchinst/#aea4f52695ae91c16ae1269f91caf4d5f">llvm::CatchSwitchInst::removeHandler</a>, <a href="/web-llvm/docs/api/classes/llvm/phinode/#a6f01dbe965b38186b1a78378689d4105">llvm::PHINode::removeIncomingValue</a>, <a href="/web-llvm/docs/api/classes/llvm/phinode/#a5197ef3eec835595e81bcecb4ee02969">llvm::PHINode::removeIncomingValueIf</a> and <a href="/web-llvm/docs/api/classes/llvm/memoryphi/#a56d097f1cf3fce666e9c5adf3e75307d">llvm::MemoryPhi::unorderedDeleteIncoming</a>.</p>

</div>
</div>

### setOperand() {#a5fa9b8e1842b354f64c1ba6be0a4a17f}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void llvm::User::setOperand (unsigned i, <a href="/web-llvm/docs/api/classes/llvm/value">Value</a> * Val)</td>
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



<p>Definition at line 233 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/ir/user-h">User.h</a>.</p>


<p>References <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/silowercontrolflow-cpp/#a4868c5d81c5ccc98c47aeab6244346a0">assert</a>, <a href="#a024c7e10ce431a93ffdb4e5e6401e0be">getOperandList</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a92ca992e52dddc420f4b069cae06dfbe">llvm::isa</a>, <a href="/web-llvm/docs/api/classes/llvm/value/#ab9ef1cd0d25962bbb4785ae14258ed5d">llvm::Value::NumUserOperands</a> and <a href="/web-llvm/docs/api/classes/llvm/value/#a18dbfcb332af7515599ee795cf462843">llvm::Value::Value</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/scalar/reassociate-cpp/#a420bedce165a865417db21cdc88307cb">BreakUpSubtract</a>, <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/scalar/constraintelimination-cpp/#ab230432af09554d7dd357c77b0ec3cde">checkOrAndOpImpliedByOther</a>, <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/scalar/reassociate-cpp/#a5ccdf0465e957f46ac1241b63af00864">ConvertShiftToMul</a>, <a href="/web-llvm/docs/api/classes/anonymous-hardwareloops-cpp-/hardwareloop/#a0a36c4c84a791cc940e176459b0675ee">anonymous{HardwareLoops.cpp}::HardwareLoop::Create</a>, <a href="/web-llvm/docs/api/classes/llvm/vplan/#ad80b94848142a7c633976aff96d4c408">llvm::VPlan::execute</a>, <a href="/web-llvm/docs/api/classes/anonymous-simplifyindvar-cpp-/simplifyindvar/#a12f6125cdd608cb0459585ddb68ead53">anonymous{SimplifyIndVar.cpp}::SimplifyIndvar::foldIVUser</a>, <a href="/web-llvm/docs/api/classes/llvm/instcombinerimpl/#aa8a186c50cdf60ac11ae1d0b884d468d">llvm::InstCombinerImpl::foldPHIArgLoadIntoPHI</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a2e4b18daaf5f20f1ade3a9f66b86d843">llvm::FoldReturnIntoUncondBranch</a>, <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/instcombine/instcombineshifts-cpp/#a04e846746dd1839f88b9a39847f5d643">foldShiftedShift</a>, <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/scalar/lowerexpectintrinsic-cpp/#a6ac9067dc7c125cd83855df3e480e04c">handleBrSelExpect</a>, <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/scalar/licm-cpp/#a2f46552f3c07dc30e7acc64cdab53056">hoistAdd</a>, <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/scalar/licm-cpp/#aabf61131f4fe5c83b4f3dccf4adb5e96">hoistSub</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#ab5a3ac0a249da0743dac1bd816d8e5d5">llvm::InlineFunction</a>, <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/scalar/reassociate-cpp/#a790c96adef17241b1ba4dbf475c3e57e">LowerNegateToMultiply</a>, <a href="/web-llvm/docs/api/classes/anonymous-simplifyindvar-cpp-/simplifyindvar/#a304f0837129322608c9e0384d193a0ba">anonymous{SimplifyIndVar.cpp}::SimplifyIndvar::makeIVComparisonInvariant</a>, <a href="/web-llvm/docs/api/classes/llvm/instmodificationirstrategy/#abd12a5e2bbbe4379385128cc1a481463">llvm::InstModificationIRStrategy::mutate</a>, <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/scalar/divrempairs-cpp/#a6e3883483a49e3be2520667d933b25f8">optimizeDivRem</a>, <a href="/web-llvm/docs/api/classes/llvm/jumpthreadingpass/#a071cd98d76a1c63f215ad16388bfdfe2">llvm::JumpThreadingPass::processBranchOnXOR</a>, <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/instcombine/instcombinecompares-cpp/#a67cafe6badc04395d797929d9d4e8efe">processUMulZExtIdiom</a>, <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/ipo/iroutliner-cpp/#a96b5bd50d8e96b4c76ffc26508ce774d">replaceArgumentUses</a>, <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/coroutines/corosplit-cpp/#af678f41709f265e2589f247e883aa738">replaceAsyncResumeFunction</a>, <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/instcombine/instcombineloadstorealloca-cpp/#a23239d94380595765d9caf8bae661d7a">replaceGEPIdxWithZero</a>, <a href="/web-llvm/docs/api/classes/llvm/vpvalue/#ae3773dd8f9c831f0dde091319b2ff7d0">llvm::VPValue::replaceUsesWithIf</a>, <a href="/web-llvm/docs/api/classes/llvm/memorydef/#a2531f35f826de9886540ea39428e144c">llvm::MemoryDef::resetOptimized</a>, <a href="/web-llvm/docs/api/classes/anonymous-aarch64stacktagging-cpp-/aarch64stacktagging/#a53fcf95621b95aa7165074a98b5df0b3">anonymous{AArch64StackTagging.cpp}::AArch64StackTagging::runOnFunction</a>, <a href="/web-llvm/docs/api/classes/anonymous-amdgpurewriteoutarguments-cpp-/amdgpurewriteoutarguments/#af9d46a08167454a31f6a9157eb65a44a">anonymous{AMDGPURewriteOutArguments.cpp}::AMDGPURewriteOutArguments::runOnFunction</a>, <a href="/web-llvm/docs/api/classes/llvm/innerloopvectorizer/#a4690286163882c35068b1908f4d752fd">llvm::InnerLoopVectorizer::scalarizeInstruction</a>, <a href="/web-llvm/docs/api/classes/llvm/indirectbrinst/#ae355076f6a214f650375e7da8e96a163">llvm::IndirectBrInst::setAddress</a>, <a href="/web-llvm/docs/api/classes/llvm/callbase/#abc10b887caad109288ffceb230493a85">llvm::CallBase::setArgOperand</a>, <a href="/web-llvm/docs/api/classes/llvm/funcletpadinst/#a48ccf888b5e0d52ce54edc14d5038ad1">llvm::FuncletPadInst::setArgOperand</a>, <a href="/web-llvm/docs/api/classes/llvm/switchinst/#a48f1c68131a864a29455ce86c1d571b2">llvm::SwitchInst::setCondition</a>, <a href="/web-llvm/docs/api/classes/llvm/switchinst/#aa22bdae1cee3c836f2b4cf8307fc7598">llvm::SwitchInst::setDefaultDest</a>, <a href="/web-llvm/docs/api/classes/llvm/memoryuseordef/#a5c00de32cf1426ab78c346e7a251d608">llvm::MemoryUseOrDef::setDefiningAccess</a>, <a href="/web-llvm/docs/api/classes/llvm/memoryphi/#a055daa2efd196d7b72c0f2d36019854e">llvm::MemoryPhi::setIncomingValue</a>, <a href="/web-llvm/docs/api/classes/llvm/phinode/#a88cdefb709309eddc6e5daca0be6a7b4">llvm::PHINode::setIncomingValue</a>, <a href="/web-llvm/docs/api/classes/llvm/dbgvariableintrinsic/#aae6ec69f4fdb9928d76326e4db900317">llvm::DbgVariableIntrinsic::setOperand</a>, <a href="/web-llvm/docs/api/classes/llvm/memorydef/#af8ce9c4c2a0f042aa8a7c365a293d642">llvm::MemoryDef::setOptimized</a>, <a href="/web-llvm/docs/api/classes/llvm/memoryuse/#ad8b436737742919b2ba59790edaaf64a">llvm::MemoryUse::setOptimized</a>, <a href="/web-llvm/docs/api/classes/llvm/catchswitchinst/#a892d35100f9c5c657d7fe1b4a8e5a990">llvm::CatchSwitchInst::setParentPad</a>, <a href="/web-llvm/docs/api/classes/llvm/noaliasscopedeclinst/#a2defed486cd9ee3d4ff214afbd0c9066">llvm::NoAliasScopeDeclInst::setScopeList</a>, <a href="/web-llvm/docs/api/classes/llvm/catchswitchinst/#a6f874c755633c971f75b47cba784955e">llvm::CatchSwitchInst::setSuccessor</a>, <a href="/web-llvm/docs/api/classes/llvm/indirectbrinst/#add548a093823a9bc99babe5e2f9282f3">llvm::IndirectBrInst::setSuccessor</a>, <a href="/web-llvm/docs/api/classes/llvm/switchinst/#a7fc7899c254935205ca29b6bd7baa926">llvm::SwitchInst::setSuccessor</a>, <a href="/web-llvm/docs/api/classes/llvm/catchswitchinst/#a03f8f04a7ac9266f16326fb7ba5786d3">llvm::CatchSwitchInst::setUnwindDest</a>, <a href="/web-llvm/docs/api/classes/llvm/memoryphi/#a56d097f1cf3fce666e9c5adf3e75307d">llvm::MemoryPhi::unorderedDeleteIncoming</a>, <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/scalar/constanthoisting-cpp/#a0b724dd85384f743a87c3815aace6037">updateOperand</a>, <a href="/web-llvm/docs/api/classes/anonymous-riscvcodegenprepare-cpp-/riscvcodegenprepare/#a6cde9aa5130a6fb02753799ff1cc6c93">anonymous{RISCVCodeGenPrepare.cpp}::RISCVCodeGenPrepare::visitAnd</a> and <a href="/web-llvm/docs/api/classes/datascalarizervisitor/#a7c94d0952ba1d6986f0e78b62c303074">DataScalarizerVisitor::visitLoadInst</a>.</p>

</div>
</div>

### value\_op\_begin() {#ad93396a26f6fd589ed400bb280319836}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">value_op_iterator llvm::User::value_op_begin ()</td>
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



<p>Definition at line 306 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/ir/user-h">User.h</a>.</p>


<p>Reference <a href="#a2eeb1c7ed1cfe403f2ae0470e36c07e2">op_begin</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/classes/llvm/vpwidenrecipe/#a0075161c54fc525d16130fa2e1891ad2">llvm::VPWidenRecipe::computeCost</a>, <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/utils/local-cpp/#ab880924a451b73edfe368d53c3d8631c">EliminateDuplicatePHINodesSetBasedImpl</a>, <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/scalar/earlycse-cpp/#aa52ac704c30d37ea926b7e186f4fac83">getHashValueImpl</a>, <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/scalar/earlycse-cpp/#ad4cae6fe0d617016d48331d85dffa4c8">hashCallInst</a>, <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/utils/local-cpp/#a0af4594038f5cb46e7a4c86713520c95">markAliveBlocks</a>, <a href="#ae9c77e5d2298423b0699e93642d17f0c">operand_values</a>, <a href="#ac493cefe3e5d3113828e0720bb16b85f">operand_values</a>, <a href="/web-llvm/docs/api/classes/llvm/branchinst/#a254b2cfabe80269ee4f53f6698452db6">llvm::BranchInst::successors</a>, <a href="/web-llvm/docs/api/classes/llvm/branchinst/#af1b864f41057ebc4d889b1b31f71bc18">llvm::BranchInst::successors</a>, <a href="/web-llvm/docs/api/classes/llvm/indirectbrinst/#af4bc0143c6827fd1a4306b273c947b12">llvm::IndirectBrInst::successors</a> and <a href="/web-llvm/docs/api/classes/llvm/indirectbrinst/#a934f272cd0defc74e252b2fc99b0b100">llvm::IndirectBrInst::successors</a>.</p>

</div>
</div>

### value\_op\_begin() {#a7018c8ee154176141c4c5c055bd341c6}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">const_value_op_iterator llvm::User::value_op_begin ()</td>
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



<p>Definition at line 327 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/ir/user-h">User.h</a>.</p>


<p>Reference <a href="#a2eeb1c7ed1cfe403f2ae0470e36c07e2">op_begin</a>.</p>

</div>
</div>

### value\_op\_end() {#a5d1730a173d0a69624b80e1e22e6d225}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">value_op_iterator llvm::User::value_op_end ()</td>
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



<p>Definition at line 309 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/ir/user-h">User.h</a>.</p>


<p>Reference <a href="#af41f58e730804d10b91fcff39b035f74">op_end</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/classes/llvm/vpwidenrecipe/#a0075161c54fc525d16130fa2e1891ad2">llvm::VPWidenRecipe::computeCost</a>, <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/utils/local-cpp/#ab880924a451b73edfe368d53c3d8631c">EliminateDuplicatePHINodesSetBasedImpl</a>, <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/scalar/earlycse-cpp/#aa52ac704c30d37ea926b7e186f4fac83">getHashValueImpl</a>, <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/scalar/earlycse-cpp/#ad4cae6fe0d617016d48331d85dffa4c8">hashCallInst</a>, <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/utils/local-cpp/#a0af4594038f5cb46e7a4c86713520c95">markAliveBlocks</a>, <a href="#ae9c77e5d2298423b0699e93642d17f0c">operand_values</a>, <a href="#ac493cefe3e5d3113828e0720bb16b85f">operand_values</a>, <a href="/web-llvm/docs/api/classes/llvm/branchinst/#a254b2cfabe80269ee4f53f6698452db6">llvm::BranchInst::successors</a>, <a href="/web-llvm/docs/api/classes/llvm/branchinst/#af1b864f41057ebc4d889b1b31f71bc18">llvm::BranchInst::successors</a>, <a href="/web-llvm/docs/api/classes/llvm/indirectbrinst/#af4bc0143c6827fd1a4306b273c947b12">llvm::IndirectBrInst::successors</a> and <a href="/web-llvm/docs/api/classes/llvm/indirectbrinst/#a934f272cd0defc74e252b2fc99b0b100">llvm::IndirectBrInst::successors</a>.</p>

</div>
</div>

### value\_op\_end() {#af4e94f12cf6145d21c3acc13c4f557ab}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">const_value_op_iterator llvm::User::value_op_end ()</td>
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



<p>Definition at line 330 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/ir/user-h">User.h</a>.</p>


<p>Reference <a href="#af41f58e730804d10b91fcff39b035f74">op_end</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Protected Member Functions

### allocHungoffUses() {#a1f1febd65726339f65bf604c66f908c0}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void llvm::User::allocHungoffUses (unsigned N, bool IsPhi=false)</td>
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

<p>Allocate the array of Uses, followed by a pointer (with bottom bit set) to the <a href="/web-llvm/docs/api/classes/llvm/user">User</a>.</p>


<dl class="doxyParamsList">
<dt class="doxyParamsTableTitle">Parameters</dt>
<dd>
<table class="doxyParamsTable">
<tr class="doxyParamItem">
<td class="doxyParamItemName">IsPhi</td>
<td class="doxyParamItemDescription"><p>identifies callers which are phi nodes and which need N BasicBlock* allocated along with N</p></td>
</tr>
</table>
</dd>
</dl>

<p>Declaration at line 133 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/ir/user-h">User.h</a>, definition at line 50 of file <a href="/web-llvm/docs/api/files/lib/lib/sandboxir/user-cpp">User.cpp</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/classes/llvm/memoryphi/#a0238c3903f55dd3155d2a791e5a0ea2c">llvm::MemoryPhi::allocHungoffUses</a> and <a href="/web-llvm/docs/api/classes/llvm/phinode/#a2d9bdd089124b3dfea76eb13c60ecac8">llvm::PHINode::allocHungoffUses</a>.</p>

</div>
</div>

### growHungoffUses() {#af834e5d5dd096241c0bcc01c5a9c0902}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void llvm::User::growHungoffUses (unsigned N, bool IsPhi=false)</td>
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

<p>Grow the number of hung off uses.</p>


<p>Note that allocHungoffUses should be called if there are no uses.</p>


<p>Declaration at line 137 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/ir/user-h">User.h</a>, definition at line 67 of file <a href="/web-llvm/docs/api/files/lib/lib/sandboxir/user-cpp">User.cpp</a>.</p>

</div>
</div>

### Op() {#a72f80871b9f46788c255158fbab96879}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<div class="doxyMemberTemplate">template &lt;int Idx&gt;</div>
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">Use &amp; llvm::User::Op ()</td>
</tr>
</table>
</td>
<td class="doxyMemberLabelsRight">
<span class="doxyMemberLabels">
<span class="doxyMemberLabel inline">inline</span>
<span class="doxyMemberLabel protected">protected</span>
</span>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 192 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/ir/user-h">User.h</a>.</p>


<p>Reference <a href="#a9f3fe741b6c50ae123d7452a2222e271">OpFrom</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/classes/llvm/instruction/#a9a7c63edb94ce4fab2a5bb34dbf6079a">llvm::Instruction::addAnnotationMetadata</a>, <a href="/web-llvm/docs/api/classes/llvm/instruction/#a00fe6a3df205f2bb5b21ac4ef7a2dca1">llvm::Instruction::getStableDebugLoc</a>, <a href="/web-llvm/docs/api/classes/llvm/constant/#a5a4d3145c046afe97789b9739a200971">llvm::Constant::isManifestConstant</a> and <a href="/web-llvm/docs/api/classes/llvm/instruction/#ae959364e4640ac025bbc046d3d7c7e61">llvm::Instruction::setSuccessor</a>.</p>

</div>
</div>

### Op() {#acba04f54d37b4a11c622d3772236b7cb}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<div class="doxyMemberTemplate">template &lt;int Idx&gt;</div>
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">const Use &amp; llvm::User::Op ()</td>
</tr>
</table>
</td>
<td class="doxyMemberLabelsRight">
<span class="doxyMemberLabels">
<span class="doxyMemberLabel inline">inline</span>
<span class="doxyMemberLabel protected">protected</span>
</span>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 195 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/ir/user-h">User.h</a>.</p>


<p>Reference <a href="#a9f3fe741b6c50ae123d7452a2222e271">OpFrom</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Private Member Functions

### getHungOffOperands() {#aff3a029b436bf45c9631851afa28f1b3}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">const Use * llvm::User::getHungOffOperands ()</td>
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



<p>Definition at line 200 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/ir/user-h">User.h</a>.</p>

</div>
</div>

### getHungOffOperands() {#a19c9b2f405fca7f9dfc92a239343ecf0}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">Use *&amp; llvm::User::getHungOffOperands ()</td>
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



<p>Definition at line 204 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/ir/user-h">User.h</a>.</p>

</div>
</div>

### getIntrusiveOperands() {#a5fc05778d9aaaf953b05b85937524388}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">const Use * llvm::User::getIntrusiveOperands ()</td>
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



<p>Definition at line 206 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/ir/user-h">User.h</a>.</p>

</div>
</div>

### getIntrusiveOperands() {#a3eae5b927e52ad4138bcef4c36ea785c}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">Use * llvm::User::getIntrusiveOperands ()</td>
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



<p>Definition at line 210 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/ir/user-h">User.h</a>.</p>

</div>
</div>

### setOperandList() {#ab1577cd2fe7c3aad5f9213fa5614e808}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void llvm::User::setOperandList (<a href="/web-llvm/docs/api/classes/llvm/use">Use</a> * NewList)</td>
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



<p>Definition at line 214 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/ir/user-h">User.h</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Public Static Functions

### classof() {#a8fc5e85e2959f635fbb7492697aec86e}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool llvm::User::classof (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/value">Value</a> * V)</td>
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



<p>Definition at line 357 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/ir/user-h">User.h</a>.</p>


<p>References <a href="/web-llvm/docs/api/namespaces/llvm/#a92ca992e52dddc420f4b069cae06dfbe">llvm::isa</a> and <a href="/web-llvm/docs/api/classes/llvm/value/#a18dbfcb332af7515599ee795cf462843">llvm::Value::Value</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Protected Static Functions

### OpFrom() {#a9f3fe741b6c50ae123d7452a2222e271}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<div class="doxyMemberTemplate">template &lt;int Idx, typename U&gt;</div>
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">Use &amp; llvm::User::OpFrom (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> U * that)</td>
</tr>
</table>
</td>
<td class="doxyMemberLabelsRight">
<span class="doxyMemberLabels">
<span class="doxyMemberLabel inline">inline</span>
<span class="doxyMemberLabel protected">protected</span>
<span class="doxyMemberLabel static">static</span>
</span>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 186 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/ir/user-h">User.h</a>.</p>


<p>Referenced by <a href="#a72f80871b9f46788c255158fbab96879">Op</a> and <a href="#acba04f54d37b4a11c622d3772236b7cb">Op</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Private Static Functions

### allocateFixedOperandUser() {#af3ac6e51c02a43008441858af1a9e405}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void * llvm::User::allocateFixedOperandUser (size_t Size, unsigned Us, unsigned DescBytes)</td>
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



<p>Declaration at line 49 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/ir/user-h">User.h</a>, definition at line 133 of file <a href="/web-llvm/docs/api/files/lib/lib/sandboxir/user-cpp">User.cpp</a>.</p>

</div>
</div>

</div>

<hr/>

The documentation for this class was generated from the following files:

<ul>
<li><a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/ir/user-h">User.h</a></li>
<li><a href="/web-llvm/docs/api/files/lib/lib/sandboxir/user-cpp">User.cpp</a></li>
</ul>

<hr/>

<p class="doxyGeneratedBy">Generated via <a href="https://github.com/xpack/doxygen2docusaurus">doxygen2docusaurus</a> by <a href="https://www.doxygen.nl">Doxygen</a> 1.14.0.</p>

</div>
