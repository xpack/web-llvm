---

# DO NOT EDIT!
# Automatically generated via doxygen2docusaurus by Doxygen.

slug: /api/classes/llvm/slotindex
custom_edit_url: null
toc_max_heading_level: 4
keywords:
  - doxygen
  - reference
  - class

---

<div class="doxyPage">

# `SlotIndex` Class

<p><a href="/web-llvm/docs/api/classes/llvm/slotindex">SlotIndex</a> - An opaque wrapper around machine indexes. <a href="#details">More...</a></p>

## Declaration

<div class="doxyDeclaration">
class llvm::SlotIndex { ... }
</div>

## Included Headers

<div class="doxyIncludesList">#include "<a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/codegen/slotindexes-h">llvm/CodeGen/SlotIndexes.h</a>"
</div>

## Enumerations Index

<table class="doxyMembersIndex">

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">enum</td>
<td class="doxyMemberIndexItemName" align="left" valign="top">Slot { <a href="#a625931951b2fd15a4f704feb89c28242">...</a> }</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">anonymous enum</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"> { <a href="#a5b8b6416308ea52c3b8712b32764c9fe">...</a> }</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ae49565c8ae048ab5c0c3fc0a3ae91e83">SlotIndexes</a></td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a2603859284443a0eb8b167ea6c41094b">SlotIndex</a> ()=default</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Construct an invalid index. <a href="#a2603859284443a0eb8b167ea6c41094b">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#aaf7f562d018e75d82f89068e056acf19">SlotIndex</a> (IndexListEntry *entry, unsigned slot)</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#abb3d97e2d9f073146030b31551485066">SlotIndex</a> (const SlotIndex &amp;li, Slot s)</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#acc9918789f16e2162e4c21c237519e35">operator bool</a> () const</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Return true for a valid index. <a href="#acc9918789f16e2162e4c21c237519e35">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">bool</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ae9f05ed2def49c28220e2ead957d73b1">operator==</a> (SlotIndex other) const</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Compare two <a href="/web-llvm/docs/api/classes/llvm/slotindex">SlotIndex</a> objects for equality. <a href="#ae9f05ed2def49c28220e2ead957d73b1">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">bool</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a677d37bf8b400b37552f591b17ab106f">operator!=</a> (SlotIndex other) const</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Compare two <a href="/web-llvm/docs/api/classes/llvm/slotindex">SlotIndex</a> objects for inequality. <a href="#a677d37bf8b400b37552f591b17ab106f">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">bool</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ac8a0846cc4715efd19857f99311056d3">operator&lt;</a> (SlotIndex other) const</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Compare two <a href="/web-llvm/docs/api/classes/llvm/slotindex">SlotIndex</a> objects. <a href="#ac8a0846cc4715efd19857f99311056d3">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">bool</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ad04bf5ce18c35ca53edccfa1fa808e48">operator&lt;=</a> (SlotIndex other) const</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Compare two <a href="/web-llvm/docs/api/classes/llvm/slotindex">SlotIndex</a> objects. <a href="#ad04bf5ce18c35ca53edccfa1fa808e48">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">bool</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a4902ee3930133969696312262c56168e">operator&gt;</a> (SlotIndex other) const</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Compare two <a href="/web-llvm/docs/api/classes/llvm/slotindex">SlotIndex</a> objects. <a href="#a4902ee3930133969696312262c56168e">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">bool</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a3844144e89644d3432c982179cb53923">operator&gt;=</a> (SlotIndex other) const</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Compare two <a href="/web-llvm/docs/api/classes/llvm/slotindex">SlotIndex</a> objects. <a href="#a3844144e89644d3432c982179cb53923">More...</a></p>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a5bcdd85778add4287db384472cde8acd">isValid</a> () const</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Returns true if this is a valid index. <a href="#a5bcdd85778add4287db384472cde8acd">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">void</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ac2683f7e08d14ae4a3509d8c55d83bb6">print</a> (raw_ostream &amp;os) const</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Print this index to the given <a href="/web-llvm/docs/api/classes/llvm/raw-ostream">raw_ostream</a>. <a href="#ac2683f7e08d14ae4a3509d8c55d83bb6">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">void</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ab4592056c4ff0764824d139d4c65116f">dump</a> () const</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Dump this index to stderr. <a href="#ab4592056c4ff0764824d139d4c65116f">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">int</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a3dd5f1d73bfabd16cd66faed5108534c">distance</a> (SlotIndex other) const</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Return the distance from this index to the given one. <a href="#a3dd5f1d73bfabd16cd66faed5108534c">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">int</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#addead5fcbbc3d5611ee3b43c184d99b0">getApproxInstrDistance</a> (SlotIndex other) const</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Return the scaled distance from this index to the given one, where all slots on the same instruction have zero distance, assuming that the slot indices are packed as densely as possible. <a href="#addead5fcbbc3d5611ee3b43c184d99b0">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">bool</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a0c74422518b3479395817926489e9eec">isBlock</a> () const</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>isBlock - Returns true if this is a block boundary slot. <a href="#a0c74422518b3479395817926489e9eec">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">bool</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a305ac7d0553ef0ce21d461f5eabfe71c">isEarlyClobber</a> () const</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>isEarlyClobber - Returns true if this is an early-clobber slot. <a href="#a305ac7d0553ef0ce21d461f5eabfe71c">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">bool</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a5e861d6342e1d7e2bc9d2002d70a4567">isRegister</a> () const</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>isRegister - Returns true if this is a normal register use/def slot. <a href="#a5e861d6342e1d7e2bc9d2002d70a4567">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">bool</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#af7b521cd03cfcb1115186e877d0e820d">isDead</a> () const</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>isDead - Returns true if this is a dead def kill slot. <a href="#af7b521cd03cfcb1115186e877d0e820d">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/slotindex">SlotIndex</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#aa94e57689dd16c1c4de909511f1b2ea8">getBaseIndex</a> () const</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Returns the base index for associated with this index. <a href="#aa94e57689dd16c1c4de909511f1b2ea8">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/slotindex">SlotIndex</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a9ee9e2030e830feecf0a2c27c6f3c09f">getBoundaryIndex</a> () const</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Returns the boundary index for associated with this index. <a href="#a9ee9e2030e830feecf0a2c27c6f3c09f">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/slotindex">SlotIndex</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ae3b98982e2036f3d26806de5ed5e02d0">getRegSlot</a> (bool EC=false) const</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Returns the register use/def slot in the current instruction for a normal or early-clobber def. <a href="#ae3b98982e2036f3d26806de5ed5e02d0">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/slotindex">SlotIndex</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a11bad3e34d11ffb7b0412de6bbd294b3">getDeadSlot</a> () const</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Returns the dead def kill slot for the current instruction. <a href="#a11bad3e34d11ffb7b0412de6bbd294b3">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/slotindex">SlotIndex</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ac3782d262b2a58da44d43c6d995aef9d">getNextSlot</a> () const</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Returns the next slot in the index list. <a href="#ac3782d262b2a58da44d43c6d995aef9d">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/slotindex">SlotIndex</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a10ffbec8bd7a2d9bc3c995e572ddc430">getNextIndex</a> () const</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Returns the next index. <a href="#a10ffbec8bd7a2d9bc3c995e572ddc430">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/slotindex">SlotIndex</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ac832da130f4d71a4533a69d98315fb19">getPrevSlot</a> () const</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Returns the previous slot in the index list. <a href="#ac832da130f4d71a4533a69d98315fb19">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/slotindex">SlotIndex</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ac0e7a3dd45019c076653747e34bbb9f2">getPrevIndex</a> () const</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Returns the previous index. <a href="#ac0e7a3dd45019c076653747e34bbb9f2">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

</table>

## Private Member Functions Index

<table class="doxyMembersIndex">

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/indexlistentry">IndexListEntry</a> *</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ad335a48f9056ac08dfb964a0df4244b4">listEntry</a> () const</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#aa4cacbbfe0ee0e7b8aa6a2b8d6de2628">getIndex</a> () const</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">Slot</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#af5fd86f6f63d94906c0dcf5fab077da1">getSlot</a> () const</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Returns the slot for this <a href="/web-llvm/docs/api/classes/llvm/slotindex">SlotIndex</a>. <a href="#af5fd86f6f63d94906c0dcf5fab077da1">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

</table>

## Private Member Attributes Index

<table class="doxyMembersIndex">

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/pointerintpair">PointerIntPair</a>&lt; <a href="/web-llvm/docs/api/classes/llvm/indexlistentry">IndexListEntry</a> *, 2, unsigned &gt;</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a3ce9557ba0cd82a6643ee27f486e2ee8">lie</a></td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a0b73244049319d841fd11a238f35b5d1">isSameInstr</a> (SlotIndex A, SlotIndex B)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>isSameInstr - Return true if A and B refer to the same instruction. <a href="#a0b73244049319d841fd11a238f35b5d1">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">static bool</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a19695ead28a0fbdcea66c6253aebc44f">isEarlierInstr</a> (SlotIndex A, SlotIndex B)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>isEarlierInstr - Return true if A refers to an instruction earlier than B. <a href="#a19695ead28a0fbdcea66c6253aebc44f">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">static bool</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a9a3b4f5099b0b155a28643224061e584">isEarlierEqualInstr</a> (SlotIndex A, SlotIndex B)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Return true if A refers to the same instruction as B or an earlier one. <a href="#a9a3b4f5099b0b155a28643224061e584">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

</table>

## Description {#details}

<p><a href="/web-llvm/docs/api/classes/llvm/slotindex">SlotIndex</a> - An opaque wrapper around machine indexes.</p>

<p>Definition at line 65 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/codegen/slotindexes-h">SlotIndexes.h</a>.</p>


<div class="doxySectionDef">

## Enumerations

### anonymous enum  {#a5b8b6416308ea52c3b8712b32764c9fe}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">anonymous enum </td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">


<dl class="doxyEnumList">
<dt class="doxyEnumTableTitle">Enumeration values</dt>
<dd>
<table class="doxyEnumTable">

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">InstrDist<a id="a5b8b6416308ea52c3b8712b32764c9fea0d0c291488b64cffb191fda8a4e90ef0"></a></td>
<td class="doxyEnumItemDescription">The default distance between instructions as returned by <a href="#a3dd5f1d73bfabd16cd66faed5108534c">distance()</a> (= 4 * Slot_Count)</td>
</tr>

</table>
</dd>
</dl>

<p>Definition at line 109 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/codegen/slotindexes-h">SlotIndexes.h</a>.</p>

</div>
</div>

### Slot {#a625931951b2fd15a4f704feb89c28242}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">enum llvm::SlotIndex::Slot </td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">


<dl class="doxyEnumList">
<dt class="doxyEnumTableTitle">Enumeration values</dt>
<dd>
<table class="doxyEnumTable">

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">Slot_Block<a id="a625931951b2fd15a4f704feb89c28242a64f6aad23c1f0351884c083881d799e8"></a></td>
<td class="doxyEnumItemDescription">Basic block boundary</td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">Slot_EarlyClobber<a id="a625931951b2fd15a4f704feb89c28242ad9cccac29906a4fe96c423bcc99dcc70"></a></td>
<td class="doxyEnumItemDescription">Early-clobber register use/def slot</td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">Slot_Register<a id="a625931951b2fd15a4f704feb89c28242ad081484b9f0fb628c623e177230ab090"></a></td>
<td class="doxyEnumItemDescription">Normal register use/def slot</td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">Slot_Dead<a id="a625931951b2fd15a4f704feb89c28242aebcd131d687f6240340671f8b1a9c91f"></a></td>
<td class="doxyEnumItemDescription">Dead def kill point</td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">Slot_Count<a id="a625931951b2fd15a4f704feb89c28242a99055533ea66205027893354b0a56be7"></a></td>
<td class="doxyEnumItemDescription"></td>
</tr>

</table>
</dd>
</dl>

<p>Definition at line 68 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/codegen/slotindexes-h">SlotIndexes.h</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Friends

### SlotIndexes {#ae49565c8ae048ab5c0c3fc0a3ae91e83}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">friend class <a href="/web-llvm/docs/api/classes/llvm/slotindexes">SlotIndexes</a></td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">


<p>Definition at line 66 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/codegen/slotindexes-h">SlotIndexes.h</a>.</p>


<p>Reference <a href="#ae49565c8ae048ab5c0c3fc0a3ae91e83">SlotIndexes</a>.</p>


<p>Referenced by <a href="#ae49565c8ae048ab5c0c3fc0a3ae91e83">SlotIndexes</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Public Constructors

### SlotIndex() {#a2603859284443a0eb8b167ea6c41094b}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">llvm::SlotIndex::SlotIndex ()</td>
</tr>
</table>
</td>
<td class="doxyMemberLabelsRight">
<span class="doxyMemberLabels">
<span class="doxyMemberLabel default">default</span>
</span>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Construct an invalid index.</p>

<p>Definition at line 116 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/codegen/slotindexes-h">SlotIndexes.h</a>.</p>


<p>Referenced by <a href="#a3dd5f1d73bfabd16cd66faed5108534c">distance</a>, <a href="#addead5fcbbc3d5611ee3b43c184d99b0">getApproxInstrDistance</a>, <a href="#aa94e57689dd16c1c4de909511f1b2ea8">getBaseIndex</a>, <a href="#a9ee9e2030e830feecf0a2c27c6f3c09f">getBoundaryIndex</a>, <a href="#a11bad3e34d11ffb7b0412de6bbd294b3">getDeadSlot</a>, <a href="#a10ffbec8bd7a2d9bc3c995e572ddc430">getNextIndex</a>, <a href="#ac3782d262b2a58da44d43c6d995aef9d">getNextSlot</a>, <a href="#ac0e7a3dd45019c076653747e34bbb9f2">getPrevIndex</a>, <a href="#ac832da130f4d71a4533a69d98315fb19">getPrevSlot</a>, <a href="#ae3b98982e2036f3d26806de5ed5e02d0">getRegSlot</a>, <a href="#a9a3b4f5099b0b155a28643224061e584">isEarlierEqualInstr</a>, <a href="#a19695ead28a0fbdcea66c6253aebc44f">isEarlierInstr</a>, <a href="#a0b73244049319d841fd11a238f35b5d1">isSameInstr</a>, <a href="#a677d37bf8b400b37552f591b17ab106f">operator!=</a>, <a href="#ac8a0846cc4715efd19857f99311056d3">operator&lt;</a>, <a href="#ad04bf5ce18c35ca53edccfa1fa808e48">operator&lt;=</a>, <a href="#ae9f05ed2def49c28220e2ead957d73b1">operator==</a>, <a href="#a4902ee3930133969696312262c56168e">operator&gt;</a>, <a href="#a3844144e89644d3432c982179cb53923">operator&gt;=</a> and <a href="#abb3d97e2d9f073146030b31551485066">SlotIndex</a>.</p>

</div>
</div>

### SlotIndex() {#aaf7f562d018e75d82f89068e056acf19}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">llvm::SlotIndex::SlotIndex (<a href="/web-llvm/docs/api/classes/llvm/indexlistentry">IndexListEntry</a> * entry, unsigned slot)</td>
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



<p>Definition at line 121 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/codegen/slotindexes-h">SlotIndexes.h</a>.</p>

</div>
</div>

### SlotIndex() {#abb3d97e2d9f073146030b31551485066}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">llvm::SlotIndex::SlotIndex (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/slotindex">SlotIndex</a> &amp; li, Slot s)</td>
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



<p>Definition at line 124 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/codegen/slotindexes-h">SlotIndexes.h</a>.</p>


<p>References <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/silowercontrolflow-cpp/#a4868c5d81c5ccc98c47aeab6244346a0">assert</a>, <a href="#a5bcdd85778add4287db384472cde8acd">isValid</a> and <a href="#a2603859284443a0eb8b167ea6c41094b">SlotIndex</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Public Operators

### operator bool() {#acc9918789f16e2162e4c21c237519e35}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">llvm::SlotIndex::operator bool ()</td>
</tr>
</table>
</td>
<td class="doxyMemberLabelsRight">
<span class="doxyMemberLabels">
<span class="doxyMemberLabel inline">inline</span>
<span class="doxyMemberLabel explicit">explicit</span>
</span>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Return true for a valid index.</p>

<p>Definition at line 135 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/codegen/slotindexes-h">SlotIndexes.h</a>.</p>


<p>Reference <a href="#a5bcdd85778add4287db384472cde8acd">isValid</a>.</p>

</div>
</div>

### operator!=() {#a677d37bf8b400b37552f591b17ab106f}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool llvm::SlotIndex::operator!= (<a href="/web-llvm/docs/api/classes/llvm/slotindex">SlotIndex</a> other)</td>
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

<p>Compare two <a href="/web-llvm/docs/api/classes/llvm/slotindex">SlotIndex</a> objects for inequality.</p>

<p>Definition at line 148 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/codegen/slotindexes-h">SlotIndexes.h</a>.</p>


<p>Reference <a href="#a2603859284443a0eb8b167ea6c41094b">SlotIndex</a>.</p>

</div>
</div>

### operator&lt;() {#ac8a0846cc4715efd19857f99311056d3}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool llvm::SlotIndex::operator&lt; (<a href="/web-llvm/docs/api/classes/llvm/slotindex">SlotIndex</a> other)</td>
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

<p>Compare two <a href="/web-llvm/docs/api/classes/llvm/slotindex">SlotIndex</a> objects.</p>


<p>Return true if the first index is strictly lower than the second.</p>


<p>Definition at line 154 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/codegen/slotindexes-h">SlotIndexes.h</a>.</p>


<p>Reference <a href="#a2603859284443a0eb8b167ea6c41094b">SlotIndex</a>.</p>

</div>
</div>

### operator&lt;=() {#ad04bf5ce18c35ca53edccfa1fa808e48}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool llvm::SlotIndex::operator&lt;= (<a href="/web-llvm/docs/api/classes/llvm/slotindex">SlotIndex</a> other)</td>
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

<p>Compare two <a href="/web-llvm/docs/api/classes/llvm/slotindex">SlotIndex</a> objects.</p>


<p>Return true if the first index is lower than, or equal to, the second.</p>


<p>Definition at line 159 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/codegen/slotindexes-h">SlotIndexes.h</a>.</p>


<p>Reference <a href="#a2603859284443a0eb8b167ea6c41094b">SlotIndex</a>.</p>

</div>
</div>

### operator==() {#ae9f05ed2def49c28220e2ead957d73b1}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool llvm::SlotIndex::operator== (<a href="/web-llvm/docs/api/classes/llvm/slotindex">SlotIndex</a> other)</td>
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

<p>Compare two <a href="/web-llvm/docs/api/classes/llvm/slotindex">SlotIndex</a> objects for equality.</p>

<p>Definition at line 144 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/codegen/slotindexes-h">SlotIndexes.h</a>.</p>


<p>Reference <a href="#a2603859284443a0eb8b167ea6c41094b">SlotIndex</a>.</p>

</div>
</div>

### operator&gt;() {#a4902ee3930133969696312262c56168e}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool llvm::SlotIndex::operator&gt; (<a href="/web-llvm/docs/api/classes/llvm/slotindex">SlotIndex</a> other)</td>
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

<p>Compare two <a href="/web-llvm/docs/api/classes/llvm/slotindex">SlotIndex</a> objects.</p>


<p>Return true if the first index is greater than the second.</p>


<p>Definition at line 165 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/codegen/slotindexes-h">SlotIndexes.h</a>.</p>


<p>Reference <a href="#a2603859284443a0eb8b167ea6c41094b">SlotIndex</a>.</p>

</div>
</div>

### operator&gt;=() {#a3844144e89644d3432c982179cb53923}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool llvm::SlotIndex::operator&gt;= (<a href="/web-llvm/docs/api/classes/llvm/slotindex">SlotIndex</a> other)</td>
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

<p>Compare two <a href="/web-llvm/docs/api/classes/llvm/slotindex">SlotIndex</a> objects.</p>


<p>Return true if the first index is greater than, or equal to, the second.</p>


<p>Definition at line 171 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/codegen/slotindexes-h">SlotIndexes.h</a>.</p>


<p>Reference <a href="#a2603859284443a0eb8b167ea6c41094b">SlotIndex</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Public Member Functions

### distance() {#a3dd5f1d73bfabd16cd66faed5108534c}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">int llvm::SlotIndex::distance (<a href="/web-llvm/docs/api/classes/llvm/slotindex">SlotIndex</a> other)</td>
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

<p>Return the distance from this index to the given one.</p>

<p>Definition at line 193 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/codegen/slotindexes-h">SlotIndexes.h</a>.</p>


<p>Reference <a href="#a2603859284443a0eb8b167ea6c41094b">SlotIndex</a>.</p>

</div>
</div>

### dump() {#ab4592056c4ff0764824d139d4c65116f}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">LLVM_DUMP_METHOD void SlotIndex::dump ()</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Dump this index to stderr.</p>

<p>Declaration at line 141 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/codegen/slotindexes-h">SlotIndexes.h</a>, definition at line 286 of file <a href="/web-llvm/docs/api/files/lib/lib/codegen/slotindexes-cpp">SlotIndexes.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/namespaces/llvm/#a7c46c742c31be54870e2038048e6b391">llvm::dbgs</a>, <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/support/compiler-h/#aa863693eef567397d9c292da5bf22d34">LLVM_DUMP_METHOD</a> and <a href="#ac2683f7e08d14ae4a3509d8c55d83bb6">print</a>.</p>

</div>
</div>

### getApproxInstrDistance() {#addead5fcbbc3d5611ee3b43c184d99b0}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">int llvm::SlotIndex::getApproxInstrDistance (<a href="/web-llvm/docs/api/classes/llvm/slotindex">SlotIndex</a> other)</td>
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

<p>Return the scaled distance from this index to the given one, where all slots on the same instruction have zero distance, assuming that the slot indices are packed as densely as possible.</p>


<p>There are normally gaps between instructions, so this assumption often doesn't hold. This results in this function often returning a value greater than the actual instruction distance.</p>


<p>Definition at line 203 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/codegen/slotindexes-h">SlotIndexes.h</a>.</p>


<p>References <a href="/web-llvm/docs/api/classes/llvm/indexlistentry/#ae2ed101cb3163db1db35700e3a62d2bd">llvm::IndexListEntry::getIndex</a> and <a href="#a2603859284443a0eb8b167ea6c41094b">SlotIndex</a>.</p>

</div>
</div>

### getBaseIndex() {#aa94e57689dd16c1c4de909511f1b2ea8}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">SlotIndex llvm::SlotIndex::getBaseIndex ()</td>
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

<p>Returns the base index for associated with this index.</p>


<p>The base index is the one associated with the Slot_Block slot for the instruction pointed to by this index.</p>


<p>Definition at line 224 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/codegen/slotindexes-h">SlotIndexes.h</a>.</p>


<p>Reference <a href="#a2603859284443a0eb8b167ea6c41094b">SlotIndex</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/classes/llvm/registeroperands/#a8affa4b2a934ff08aa04e63253a00126">llvm::RegisterOperands::adjustLaneLiveness</a>, <a href="/web-llvm/docs/api/classes/llvm/x86instrinfo/#acf40b35a88eb365bc4f4047a03bb1ece">llvm::X86InstrInfo::classifyLEAReg</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/gcnregpressure-cpp/#a08414c5d48fed44354cf4c4ea6ca464c">collectVirtualRegUses</a>, <a href="/web-llvm/docs/api/classes/llvm/spliteditor/#a88924909b2d83abe8eb4ba2ac84eec6c">llvm::SplitEditor::enterIntvBefore</a>, <a href="/web-llvm/docs/api/files/lib/lib/codegen/livedebugvariables-cpp/#a73c2c11c6c943efa25ec3a0802c4ac52">findInsertLocation</a>, <a href="/web-llvm/docs/api/classes/llvm/gcnrptracker/#abbe36a4a2c040ff3e4a6040a900b0997">llvm::GCNRPTracker::getLastUsedLanes</a>, <a href="/web-llvm/docs/api/classes/llvm/regpressuretracker/#acba0d5ed53c0ebfa11cc3310e6aef4b1">llvm::RegPressureTracker::getLastUsedLanes</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#adb88334dcf6976de300fb1e3667430d7">llvm::getLiveRegsBefore</a>, <a href="/web-llvm/docs/api/classes/llvm/liverange/#a61f530037a29a00a48799b14104a68d1">llvm::LiveRange::isZeroLength</a>, <a href="/web-llvm/docs/api/classes/llvm/spliteditor/#a9899a3945a73e70c7bb2800ef3865017">llvm::SplitEditor::leaveIntvBefore</a>, <a href="/web-llvm/docs/api/classes/llvm/liverange/#a6eb0e49d283729a5f8b99d4efa1be7c1">llvm::LiveRange::Query</a>, <a href="/web-llvm/docs/api/classes/llvm/liveintervals/#ac332ca27d85adc8d21edd708be55dfe3">llvm::LiveIntervals::removeVRegDefAt</a>, <a href="/web-llvm/docs/api/classes/llvm/spliteditor/#ab181eb57b4d30c914d782ad60b8d913f">llvm::SplitEditor::splitLiveThroughBlock</a> and <a href="/web-llvm/docs/api/classes/llvm/spliteditor/#a8534c37f85077c1dd9fc3468f70d4618">llvm::SplitEditor::splitRegOutBlock</a>.</p>

</div>
</div>

### getBoundaryIndex() {#a9ee9e2030e830feecf0a2c27c6f3c09f}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">SlotIndex llvm::SlotIndex::getBoundaryIndex ()</td>
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

<p>Returns the boundary index for associated with this index.</p>


<p>The boundary index is the one associated with the Slot_Block slot for the instruction pointed to by this index.</p>


<p>Definition at line 231 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/codegen/slotindexes-h">SlotIndexes.h</a>.</p>


<p>Reference <a href="#a2603859284443a0eb8b167ea6c41094b">SlotIndex</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/classes/llvm/spliteditor/#a8808112c59febd729a9964ac6509d7d4">llvm::SplitEditor::enterIntvAfter</a>, <a href="/web-llvm/docs/api/classes/llvm/liverange/#ae17e7d305505cddb57d8093ee934c387">llvm::LiveRange::isLocal</a>, <a href="/web-llvm/docs/api/classes/llvm/spliteditor/#a8ab989120222d67308b4e03b2772fb6a">llvm::SplitEditor::leaveIntvAfter</a>, <a href="/web-llvm/docs/api/classes/llvm/spliteditor/#ab181eb57b4d30c914d782ad60b8d913f">llvm::SplitEditor::splitLiveThroughBlock</a> and <a href="/web-llvm/docs/api/classes/llvm/spliteditor/#a9d2296ecca42f33ce641b7341fde67d9">llvm::SplitEditor::splitRegInBlock</a>.</p>

</div>
</div>

### getDeadSlot() {#a11bad3e34d11ffb7b0412de6bbd294b3}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">SlotIndex llvm::SlotIndex::getDeadSlot ()</td>
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

<p>Returns the dead def kill slot for the current instruction.</p>

<p>Definition at line 242 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/codegen/slotindexes-h">SlotIndexes.h</a>.</p>


<p>Reference <a href="#a2603859284443a0eb8b167ea6c41094b">SlotIndex</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/classes/llvm/registeroperands/#a8affa4b2a934ff08aa04e63253a00126">llvm::RegisterOperands::adjustLaneLiveness</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a62c28bacc64f2e1f9c9296f9314d6c75">llvm::getLiveRegsAfter</a>, <a href="/web-llvm/docs/api/classes/llvm/regpressuretracker/#ad8b14ec0777ac642d3403470e0753533">llvm::RegPressureTracker::getLiveThroughAt</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/webassembly/webassemblyregstackify-cpp/#a2281004fe6686c5e3700682448b77f90">rematerializeCheapDef</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/webassembly/webassemblymemintrinsicresults-cpp/#abd14b1720a6213a3a1251afdbd671c62">replaceDominatedUses</a>, <a href="/web-llvm/docs/api/classes/llvm/liveintervals/#a42083019e0bdb164e55da49ab9f4d717">llvm::LiveIntervals::shrinkToUses</a> and <a href="/web-llvm/docs/api/structs/anonymous-machineverifier-cpp-/machineverifier/#abc440c9fad640641c26ddae8c08dce82">anonymous{MachineVerifier.cpp}::MachineVerifier::verifyLiveRangeSegment</a>.</p>

</div>
</div>

### getNextIndex() {#a10ffbec8bd7a2d9bc3c995e572ddc430}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">SlotIndex llvm::SlotIndex::getNextIndex ()</td>
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

<p>Returns the next index.</p>


<p>This is the index corresponding to the this index's slot, but for the next instruction.</p>


<p>Definition at line 262 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/codegen/slotindexes-h">SlotIndexes.h</a>.</p>


<p>Reference <a href="#a2603859284443a0eb8b167ea6c41094b">SlotIndex</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/classes/anonymous-livedebugvariables-cpp-/uservalue/#a5addc8b01ca0cce0a572d5fe3ef86654">anonymous{LiveDebugVariables.cpp}::UserValue::computeIntervals</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a47832d6753036cd8ce039993854b3162">llvm::extractInstructionFeatures</a> and <a href="/web-llvm/docs/api/classes/anonymous-siformmemoryclauses-cpp-/siformmemoryclauses/#a3b412b093194b8e66d1d42d1cc79d692">anonymous{SIFormMemoryClauses.cpp}::SIFormMemoryClauses::runOnMachineFunction</a>.</p>

</div>
</div>

### getNextSlot() {#ac3782d262b2a58da44d43c6d995aef9d}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">SlotIndex llvm::SlotIndex::getNextSlot ()</td>
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

<p>Returns the next slot in the index list.</p>


<p>This could be either the next slot for the instruction pointed to by this index or, if this index is a STORE, the first slot for the next instruction. WARNING: This method is considerably more expensive than the methods that return specific slots (getUseIndex(), etc). If you can - please use one of those methods.</p>


<p>Definition at line 252 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/codegen/slotindexes-h">SlotIndexes.h</a>.</p>


<p>Reference <a href="#a2603859284443a0eb8b167ea6c41094b">SlotIndex</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/classes/anonymous-livedebugvariables-cpp-/uservalue/#a2f56e0c8e37796630334366257d1b7e3">anonymous{LiveDebugVariables.cpp}::UserValue::addDef</a>, <a href="/web-llvm/docs/api/classes/anonymous-livedebugvariables-cpp-/uservalue/#ac0a0c1bb8dc69992e326ead7f5faf286">anonymous{LiveDebugVariables.cpp}::UserValue::addDefsFromCopies</a>, <a href="/web-llvm/docs/api/classes/llvm/spliteditor/#a8ab989120222d67308b4e03b2772fb6a">llvm::SplitEditor::leaveIntvAfter</a> and <a href="/web-llvm/docs/api/classes/llvm/spliteditor/#a9899a3945a73e70c7bb2800ef3865017">llvm::SplitEditor::leaveIntvBefore</a>.</p>

</div>
</div>

### getPrevIndex() {#ac0e7a3dd45019c076653747e34bbb9f2}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">SlotIndex llvm::SlotIndex::getPrevIndex ()</td>
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

<p>Returns the previous index.</p>


<p>This is the index corresponding to this index's slot, but for the previous instruction.</p>


<p>Definition at line 282 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/codegen/slotindexes-h">SlotIndexes.h</a>.</p>


<p>Reference <a href="#a2603859284443a0eb8b167ea6c41094b">SlotIndex</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/files/lib/lib/codegen/livedebugvariables-cpp/#a73c2c11c6c943efa25ec3a0802c4ac52">findInsertLocation</a>.</p>

</div>
</div>

### getPrevSlot() {#ac832da130f4d71a4533a69d98315fb19}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">SlotIndex llvm::SlotIndex::getPrevSlot ()</td>
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

<p>Returns the previous slot in the index list.</p>


<p>This could be either the previous slot for the instruction pointed to by this index or, if this index is a Slot_Block, the last slot for the previous instruction. WARNING: This method is considerably more expensive than the methods that return specific slots (getUseIndex(), etc). If you can - please use one of those methods.</p>


<p>Definition at line 272 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/codegen/slotindexes-h">SlotIndexes.h</a>.</p>


<p>Reference <a href="#a2603859284443a0eb8b167ea6c41094b">SlotIndex</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/classes/llvm/spliteditor/#a94fd41d857393a092523f88b19d1bef3">llvm::SplitEditor::enterIntvAtEnd</a>, <a href="/web-llvm/docs/api/classes/llvm/liverange/#a7e1ec6260b229b2f5913405b758bc146">llvm::LiveRange::getVNInfoBefore</a>, <a href="/web-llvm/docs/api/classes/llvm/liveintervals/#a0d7e0d23a0453390a4c1e9a61afccdca">llvm::LiveIntervals::repairIntervalsInRange</a>, <a href="/web-llvm/docs/api/classes/llvm/machinebasicblock/#aa80aaa82844ab5560ece045eee7b34ac">llvm::MachineBasicBlock::SplitCriticalEdge</a> and <a href="/web-llvm/docs/api/structs/anonymous-machineverifier-cpp-/machineverifier/#abc440c9fad640641c26ddae8c08dce82">anonymous{MachineVerifier.cpp}::MachineVerifier::verifyLiveRangeSegment</a>.</p>

</div>
</div>

### getRegSlot() {#ae3b98982e2036f3d26806de5ed5e02d0}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">SlotIndex llvm::SlotIndex::getRegSlot (bool EC=false)</td>
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

<p>Returns the register use/def slot in the current instruction for a normal or early-clobber def.</p>

<p>Definition at line 237 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/codegen/slotindexes-h">SlotIndexes.h</a>.</p>


<p>Reference <a href="#a2603859284443a0eb8b167ea6c41094b">SlotIndex</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/classes/anonymous-livedebugvariables-cpp-/uservalue/#ac0a0c1bb8dc69992e326ead7f5faf286">anonymous{LiveDebugVariables.cpp}::UserValue::addDefsFromCopies</a>, <a href="/web-llvm/docs/api/classes/anonymous-inlinespiller-cpp-/hoistspillhelper/#a802b241b8cfc1f00f85b1d4da7eeed73">anonymous{InlineSpiller.cpp}::HoistSpillHelper::addToMergeableSpills</a>, <a href="/web-llvm/docs/api/classes/llvm/liverangeedit/#ad930b47a8263b4fcc37e6209e387b897">llvm::LiveRangeEdit::allUsesAvailableAt</a>, <a href="/web-llvm/docs/api/classes/llvm/regpressuretracker/#a2b8b6196a7458b6a84480f03e2f1355d">llvm::RegPressureTracker::bumpDownwardPressure</a>, <a href="/web-llvm/docs/api/classes/llvm/regpressuretracker/#ab0885ecf357ddad3594c9a2a5a9527f2">llvm::RegPressureTracker::bumpUpwardPressure</a>, <a href="/web-llvm/docs/api/structs/anonymous-machineverifier-cpp-/machineverifier/#aa2b8ab3df737c2492c7967447e7abac9">anonymous{MachineVerifier.cpp}::MachineVerifier::checkLiveness</a>, <a href="/web-llvm/docs/api/classes/llvm/x86instrinfo/#acf40b35a88eb365bc4f4047a03bb1ece">llvm::X86InstrInfo::classifyLEAReg</a>, <a href="/web-llvm/docs/api/classes/llvm/liveinterval/#af4a07ae5c460ac08439a1a71d15e0166">llvm::LiveInterval::computeSubRangeUndefs</a>, <a href="/web-llvm/docs/api/classes/llvm/riscvinstrinfo/#a061f47e0bf17eed5f4fb190668a20858">llvm::RISCVInstrInfo::convertToThreeAddress</a>, <a href="/web-llvm/docs/api/classes/llvm/siinstrinfo/#ad4445a2ce5876c120e2a6e6796edaf5c">llvm::SIInstrInfo::convertToThreeAddress</a>, <a href="/web-llvm/docs/api/files/lib/lib/codegen/liveintervalcalc-cpp/#a70e2de8376b84c468e8a5762fda4c419">createDeadDef</a>, <a href="/web-llvm/docs/api/files/lib/lib/codegen/inlinespiller-cpp/#a3a62b5d1e83ec172369441613b538fce">dumpMachineInstrRangeWithSlotIndex</a>, <a href="/web-llvm/docs/api/files/lib/lib/codegen/registerpressure-cpp/#ac9883c9ec5baeee39d4215b9af8e0a70">findUseBetween</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/gcnregpressure-cpp/#ab457e04adca93e5cb81989a2414b1a49">findUseBetween</a>, <a href="/web-llvm/docs/api/classes/llvm/systemzinstrinfo/#af3524773747ed9e90b586d5e6752e1c2">llvm::SystemZInstrInfo::foldMemoryOperandImpl</a>, <a href="/web-llvm/docs/api/classes/llvm/regpressuretracker/#ad8b14ec0777ac642d3403470e0753533">llvm::RegPressureTracker::getLiveThroughAt</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/webassembly/webassemblyregstackify-cpp/#a881b49c730ea9d71536df2bf6847f4d0">hasOneNonDBGUse</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/sioptimizeexecmaskingprera-cpp/#aa0224ce6f8dd63f7674a2a1f032e23ae">isDefBetween</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/simachinescheduler-cpp/#a9dbfc6f968f0d6cbfd77760b62a9b552">isDefBetween</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/webassembly/webassemblyregstackify-cpp/#ad7ed3a1e19bd5b3c4ea5a74413371900">moveAndTeeForMultiUse</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/webassembly/webassemblyregstackify-cpp/#a9317ef8571eae8a49591ed8912c4d102">moveForSingleUse</a>, <a href="/web-llvm/docs/api/structs/anonymous-ppcvsxfmamutate-cpp-/ppcvsxfmamutate/#acd5cf076b2f9e98086a68b9d7e0f8710">anonymous{PPCVSXFMAMutate.cpp}::PPCVSXFMAMutate::processBlock</a>, <a href="/web-llvm/docs/api/classes/llvm/regpressuretracker/#a126f33e8085746e4f69b4411b61102dc">llvm::RegPressureTracker::recede</a>, <a href="/web-llvm/docs/api/classes/llvm/regpressuretracker/#a20a8136fbbb55939ae03e734232ce942">llvm::RegPressureTracker::recede</a>, <a href="/web-llvm/docs/api/classes/llvm/regpressuretracker/#a354c230443b1586633f5697aec0bcd8e">llvm::RegPressureTracker::recedeSkipDebugValues</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/webassembly/webassemblyregstackify-cpp/#a2281004fe6686c5e3700682448b77f90">rematerializeCheapDef</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/webassembly/webassemblymemintrinsicresults-cpp/#abd14b1720a6213a3a1251afdbd671c62">replaceDominatedUses</a>, <a href="/web-llvm/docs/api/classes/anonymous-inlinespiller-cpp-/hoistspillhelper/#a4bed72d6ec635da0c0a6c57442012e6e">anonymous{InlineSpiller.cpp}::HoistSpillHelper::rmFromMergeableSpills</a>, <a href="/web-llvm/docs/api/classes/anonymous-twoaddressinstructionpass-cpp-/twoaddressinstructionimpl/#a7bc0a5064c340800de9ce752c881316d">anonymous{TwoAddressInstructionPass.cpp}::TwoAddressInstructionImpl::run</a>, <a href="/web-llvm/docs/api/classes/llvm/liveintervals/#ac7446b2819c44bf459763351b5bcc29b">llvm::LiveIntervals::shrinkToUses</a>, <a href="/web-llvm/docs/api/classes/llvm/liveintervals/#a42083019e0bdb164e55da49ab9f4d717">llvm::LiveIntervals::shrinkToUses</a> and <a href="/web-llvm/docs/api/structs/anonymous-machineverifier-cpp-/machineverifier/#a16957e467c8bf1aa4c3c8614d7315709">anonymous{MachineVerifier.cpp}::MachineVerifier::visitMachineOperand</a>.</p>

</div>
</div>

### isBlock() {#a0c74422518b3479395817926489e9eec}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool llvm::SlotIndex::isBlock ()</td>
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

<p>isBlock - Returns true if this is a block boundary slot.</p>

<p>Definition at line 209 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/codegen/slotindexes-h">SlotIndexes.h</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/classes/llvm/liveintervals/#abc913cf0bab81b94548cd3c8eeb33117">llvm::LiveIntervals::intervalIsInOneMBB</a>, <a href="/web-llvm/docs/api/classes/anonymous-amdgpumarklastscratchload-cpp-/amdgpumarklastscratchload/#adb457e87e019538757ec91bec7a7e5f0">anonymous{AMDGPUMarkLastScratchLoad.cpp}::AMDGPUMarkLastScratchLoad::runOnMachineFunction</a> and <a href="/web-llvm/docs/api/structs/anonymous-machineverifier-cpp-/machineverifier/#abc440c9fad640641c26ddae8c08dce82">anonymous{MachineVerifier.cpp}::MachineVerifier::verifyLiveRangeSegment</a>.</p>

</div>
</div>

### isDead() {#af7b521cd03cfcb1115186e877d0e820d}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool llvm::SlotIndex::isDead ()</td>
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

<p>isDead - Returns true if this is a dead def kill slot.</p>

<p>Definition at line 219 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/codegen/slotindexes-h">SlotIndexes.h</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/files/lib/lib/codegen/registercoalescer-cpp/#a61eeba1f176225faf4761e4d9b25cc43">addSegmentsWithValNo</a> and <a href="/web-llvm/docs/api/structs/anonymous-machineverifier-cpp-/machineverifier/#abc440c9fad640641c26ddae8c08dce82">anonymous{MachineVerifier.cpp}::MachineVerifier::verifyLiveRangeSegment</a>.</p>

</div>
</div>

### isEarlyClobber() {#a305ac7d0553ef0ce21d461f5eabfe71c}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool llvm::SlotIndex::isEarlyClobber ()</td>
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

<p>isEarlyClobber - Returns true if this is an early-clobber slot.</p>

<p>Definition at line 212 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/codegen/slotindexes-h">SlotIndexes.h</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/classes/anonymous-registercoalescer-cpp-/joinvals/#add7c3bdd8428904f63f53569807b8df6">anonymous{RegisterCoalescer.cpp}::JoinVals::resolveConflicts</a>, <a href="/web-llvm/docs/api/structs/anonymous-machineverifier-cpp-/machineverifier/#abc440c9fad640641c26ddae8c08dce82">anonymous{MachineVerifier.cpp}::MachineVerifier::verifyLiveRangeSegment</a> and <a href="/web-llvm/docs/api/structs/anonymous-machineverifier-cpp-/machineverifier/#a38cfbca05868eacdc315641e8ed182d4">anonymous{MachineVerifier.cpp}::MachineVerifier::verifyLiveRangeValue</a>.</p>

</div>
</div>

### isRegister() {#a5e861d6342e1d7e2bc9d2002d70a4567}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool llvm::SlotIndex::isRegister ()</td>
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

<p>isRegister - Returns true if this is a normal register use/def slot.</p>


<p>Note that early-clobber slots may also be used for uses and defs.</p>


<p>Definition at line 216 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/codegen/slotindexes-h">SlotIndexes.h</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/structs/anonymous-machineverifier-cpp-/machineverifier/#a4d40a357c884c36942205713e7bf3244">anonymous{MachineVerifier.cpp}::MachineVerifier::checkLivenessAtDef</a> and <a href="/web-llvm/docs/api/structs/anonymous-machineverifier-cpp-/machineverifier/#a38cfbca05868eacdc315641e8ed182d4">anonymous{MachineVerifier.cpp}::MachineVerifier::verifyLiveRangeValue</a>.</p>

</div>
</div>

### isValid() {#a5bcdd85778add4287db384472cde8acd}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool llvm::SlotIndex::isValid ()</td>
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

<p>Returns true if this is a valid index.</p>


<p>Invalid indices do not point into an index table, and cannot be compared.</p>


<p>Definition at line 130 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/codegen/slotindexes-h">SlotIndexes.h</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/classes/anonymous-registercoalescer-cpp-/joinvals/#a1659a196eabbdd653b9a5d529ccfcb6e">anonymous{RegisterCoalescer.cpp}::JoinVals::eraseInstrs</a>, <a href="/web-llvm/docs/api/classes/llvm/siregisterinfo/#a96cdbab4e65a936880975a58e0dde922">llvm::SIRegisterInfo::findReachingDef</a>, <a href="#acc9918789f16e2162e4c21c237519e35">operator bool</a>, <a href="#ac2683f7e08d14ae4a3509d8c55d83bb6">print</a> and <a href="#abb3d97e2d9f073146030b31551485066">SlotIndex</a>.</p>

</div>
</div>

### print() {#ac2683f7e08d14ae4a3509d8c55d83bb6}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void SlotIndex::print (<a href="/web-llvm/docs/api/classes/llvm/raw-ostream">raw_ostream</a> &amp; os)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Print this index to the given <a href="/web-llvm/docs/api/classes/llvm/raw-ostream">raw_ostream</a>.</p>

<p>Declaration at line 138 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/codegen/slotindexes-h">SlotIndexes.h</a>, definition at line 277 of file <a href="/web-llvm/docs/api/files/lib/lib/codegen/slotindexes-cpp">SlotIndexes.cpp</a>.</p>


<p>Reference <a href="#a5bcdd85778add4287db384472cde8acd">isValid</a>.</p>


<p>Referenced by <a href="#ab4592056c4ff0764824d139d4c65116f">dump</a> and <a href="/web-llvm/docs/api/namespaces/llvm/#a5f358149a70d9298ac0730c96f346a20">llvm::operator&lt;&lt;</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Private Member Functions

### getIndex() {#aa4cacbbfe0ee0e7b8aa6a2b8d6de2628}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">unsigned llvm::SlotIndex::getIndex ()</td>
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



<p>Definition at line 99 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/codegen/slotindexes-h">SlotIndexes.h</a>.</p>

</div>
</div>

### getSlot() {#af5fd86f6f63d94906c0dcf5fab077da1}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">Slot llvm::SlotIndex::getSlot ()</td>
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

<p>Returns the slot for this <a href="/web-llvm/docs/api/classes/llvm/slotindex">SlotIndex</a>.</p>

<p>Definition at line 104 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/codegen/slotindexes-h">SlotIndexes.h</a>.</p>

</div>
</div>

### listEntry() {#ad335a48f9056ac08dfb964a0df4244b4}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">IndexListEntry * llvm::SlotIndex::listEntry ()</td>
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



<p>Definition at line 94 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/codegen/slotindexes-h">SlotIndexes.h</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Private Member Attributes

### lie {#a3ce9557ba0cd82a6643ee27f486e2ee8}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">PointerIntPair&lt;IndexListEntry*, 2, unsigned&gt; llvm::SlotIndex::lie</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 92 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/codegen/slotindexes-h">SlotIndexes.h</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Public Static Functions

### isEarlierEqualInstr() {#a9a3b4f5099b0b155a28643224061e584}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool llvm::SlotIndex::isEarlierEqualInstr (<a href="/web-llvm/docs/api/classes/llvm/slotindex">SlotIndex</a> A, <a href="/web-llvm/docs/api/classes/llvm/slotindex">SlotIndex</a> B)</td>
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

<p>Return true if A refers to the same instruction as B or an earlier one.</p>


<p>This is equivalent to !isEarlierInstr(B, A).</p>


<p>Definition at line 188 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/codegen/slotindexes-h">SlotIndexes.h</a>.</p>


<p>References <a href="/web-llvm/docs/api/files/lib/lib/ir/builtingcs-cpp/#a2e38c85003a042421cde1647632d0b72">A</a>, <a href="/web-llvm/docs/api/files/lib/lib/ir/builtingcs-cpp/#ae76959fe811ba090de4cba69ac00f1da">B</a>, <a href="#a19695ead28a0fbdcea66c6253aebc44f">isEarlierInstr</a> and <a href="#a2603859284443a0eb8b167ea6c41094b">SlotIndex</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/files/lib/lib/codegen/livedebugvariables-cpp/#a8b1a8fc118e74550d4d11d8740ae10eb">findNextInsertLocation</a>.</p>

</div>
</div>

### isEarlierInstr() {#a19695ead28a0fbdcea66c6253aebc44f}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool llvm::SlotIndex::isEarlierInstr (<a href="/web-llvm/docs/api/classes/llvm/slotindex">SlotIndex</a> A, <a href="/web-llvm/docs/api/classes/llvm/slotindex">SlotIndex</a> B)</td>
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

<p>isEarlierInstr - Return true if A refers to an instruction earlier than B.</p>


<p>This is equivalent to A &lt; B &amp;&amp; !isSameInstr(A, B).</p>


<p>Definition at line 182 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/codegen/slotindexes-h">SlotIndexes.h</a>.</p>


<p>References <a href="/web-llvm/docs/api/files/lib/lib/ir/builtingcs-cpp/#a2e38c85003a042421cde1647632d0b72">A</a>, <a href="/web-llvm/docs/api/files/lib/lib/ir/builtingcs-cpp/#ae76959fe811ba090de4cba69ac00f1da">B</a> and <a href="#a2603859284443a0eb8b167ea6c41094b">SlotIndex</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/classes/anonymous-liveinterval-cpp-/calcliverangeutilbase/#acc30e10385342c3caf14a3bf391bc72b">anonymous{LiveInterval.cpp}::CalcLiveRangeUtilBase&lt; CalcLiveRangeUtilVector, LiveRange::iterator, LiveRange::Segments &gt;::createDeadDef</a>, <a href="#a9a3b4f5099b0b155a28643224061e584">isEarlierEqualInstr</a> and <a href="/web-llvm/docs/api/classes/llvm/liverange/#a6eb0e49d283729a5f8b99d4efa1be7c1">llvm::LiveRange::Query</a>.</p>

</div>
</div>

### isSameInstr() {#a0b73244049319d841fd11a238f35b5d1}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool llvm::SlotIndex::isSameInstr (<a href="/web-llvm/docs/api/classes/llvm/slotindex">SlotIndex</a> A, <a href="/web-llvm/docs/api/classes/llvm/slotindex">SlotIndex</a> B)</td>
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

<p>isSameInstr - Return true if A and B refer to the same instruction.</p>

<p>Definition at line 176 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/codegen/slotindexes-h">SlotIndexes.h</a>.</p>


<p>References <a href="/web-llvm/docs/api/files/lib/lib/ir/builtingcs-cpp/#a2e38c85003a042421cde1647632d0b72">A</a>, <a href="/web-llvm/docs/api/files/lib/lib/ir/builtingcs-cpp/#ae76959fe811ba090de4cba69ac00f1da">B</a> and <a href="#a2603859284443a0eb8b167ea6c41094b">SlotIndex</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/classes/llvm/liverangeedit/#ad930b47a8263b4fcc37e6209e387b897">llvm::LiveRangeEdit::allUsesAvailableAt</a>, <a href="/web-llvm/docs/api/structs/anonymous-machineverifier-cpp-/machineverifier/#a4d40a357c884c36942205713e7bf3244">anonymous{MachineVerifier.cpp}::MachineVerifier::checkLivenessAtDef</a>, <a href="/web-llvm/docs/api/classes/anonymous-machinescheduler-cpp-/copyconstrain/#aee8fb987217bee89c0f2059168e834ec">anonymous{MachineScheduler.cpp}::CopyConstrain::constrainLocalCopy</a>, <a href="/web-llvm/docs/api/classes/anonymous-liveinterval-cpp-/calcliverangeutilbase/#acc30e10385342c3caf14a3bf391bc72b">anonymous{LiveInterval.cpp}::CalcLiveRangeUtilBase&lt; CalcLiveRangeUtilVector, LiveRange::iterator, LiveRange::Segments &gt;::createDeadDef</a>, <a href="/web-llvm/docs/api/structs/llvm/splitanalysis/blockinfo/#a5a04f02eff679552af69729e22e8f1a2">llvm::SplitAnalysis::BlockInfo::isOneInstr</a>, <a href="/web-llvm/docs/api/classes/llvm/spliteditor/#a8ab989120222d67308b4e03b2772fb6a">llvm::SplitEditor::leaveIntvAfter</a>, <a href="/web-llvm/docs/api/classes/llvm/liverange/#a6eb0e49d283729a5f8b99d4efa1be7c1">llvm::LiveRange::Query</a>, <a href="/web-llvm/docs/api/classes/anonymous-registercoalescer-cpp-/joinvals/#add7c3bdd8428904f63f53569807b8df6">anonymous{RegisterCoalescer.cpp}::JoinVals::resolveConflicts</a> and <a href="/web-llvm/docs/api/structs/anonymous-machineverifier-cpp-/machineverifier/#abc440c9fad640641c26ddae8c08dce82">anonymous{MachineVerifier.cpp}::MachineVerifier::verifyLiveRangeSegment</a>.</p>

</div>
</div>

</div>

<hr/>

The documentation for this class was generated from the following files:

<ul>
<li><a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/codegen/slotindexes-h">SlotIndexes.h</a></li>
<li><a href="/web-llvm/docs/api/files/lib/lib/codegen/slotindexes-cpp">SlotIndexes.cpp</a></li>
</ul>

<hr/>

<p class="doxyGeneratedBy">Generated via <a href="https://github.com/xpack/doxygen2docusaurus">doxygen2docusaurus</a> by <a href="https://www.doxygen.nl">Doxygen</a> 1.15.0.</p>

</div>
