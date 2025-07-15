---

# DO NOT EDIT!
# Automatically generated via doxygen2docusaurus by Doxygen.

slug: /api/classes/llvm/slotindexes
custom_edit_url: null
toc_max_heading_level: 4
keywords:
  - doxygen
  - reference
  - class

---

<div class="doxyPage">

# The `SlotIndexes` Class Reference

<p><a href="/web-llvm/docs/api/classes/llvm/slotindexes">SlotIndexes</a> pass. <a href="#details">More...</a></p>

## Declaration

<div class="doxyDeclaration">
class llvm::SlotIndexes { ... }
</div>

## Included Headers

<div class="doxyIncludesList">#include "<a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/codegen/slotindexes-h">llvm/CodeGen/SlotIndexes.h</a>"
</div>

## Public Member Typedefs Index

<table class="doxyMembersIndex">

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">using</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a960aca5467c09d62292856c116ac9291">MBBIndexIterator</a> = <a href="/web-llvm/docs/api/classes/llvm/smallvectorimpl">SmallVectorImpl</a>&lt; <a href="/web-llvm/docs/api/namespaces/llvm/#a906e44aee29a06c01bd067475f10e7b4">IdxMBBPair</a> &gt;::const_iterator</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Iterator over the idx2MBBMap (sorted pairs of slot index of basic block begin and basic block) <a href="#a960aca5467c09d62292856c116ac9291">More...</a></p>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a5f335b23ff47f871e040ea5c0a9ba9b4">IndexList</a> = <a href="/web-llvm/docs/api/classes/llvm/simple-ilist">simple_ilist</a>&lt; <a href="/web-llvm/docs/api/classes/llvm/indexlistentry">IndexListEntry</a> &gt;</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ab1f2d617862d9db060b21808f380aa41">Mi2IndexMap</a> = <a href="/web-llvm/docs/api/classes/llvm/densemap">DenseMap</a>&lt; <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/machineinstr">MachineInstr</a> *, <a href="/web-llvm/docs/api/classes/llvm/slotindex">SlotIndex</a> &gt;</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#afdbd6d41821f020763e2216207eba140">SlotIndexesWrapperPass</a></td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a2841585dd75b3635949c39269adec017">SlotIndexes</a> (SlotIndexes &amp;&amp;)=default</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#aa3bdaefbd2a25ebb5c3dda49c20b3bcf">SlotIndexes</a> (MachineFunction &amp;MF)</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ae597d16319281f1fc8744104e5fc9e36">SlotIndexes</a> ()=default</td>
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

## Public Destructor Index

<table class="doxyMembersIndex">

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#aac440a2faa289432c4287f79299139c2">~SlotIndexes</a> ()</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">void</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a6436a96f9d3be5a2ef92e1ea2b2eb1e7">reanalyze</a> (MachineFunction &amp;MF)</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ae0e0577e6178c0dfda4edf688163beea">print</a> (raw_ostream &amp;OS) const</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a40e7a4cc6e14f421c36f936f9f8dff58">dump</a> () const</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Dump the indexes. <a href="#a40e7a4cc6e14f421c36f936f9f8dff58">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">void</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a453e4d014fa115aebac6e1416cf7d64c">repairIndexesInRange</a> (MachineBasicBlock *MBB, MachineBasicBlock::iterator Begin, MachineBasicBlock::iterator End)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Repair indexes after adding and removing instructions. <a href="#a453e4d014fa115aebac6e1416cf7d64c">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/slotindex">SlotIndex</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ae87b945bbb68117e870cfca419e4c845">getZeroIndex</a> ()</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Returns the zero index for this analysis. <a href="#ae87b945bbb68117e870cfca419e4c845">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/slotindex">SlotIndex</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a08d65216af6fc79fe34347db3b9d8e75">getLastIndex</a> ()</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Returns the base index of the last slot in this analysis. <a href="#a08d65216af6fc79fe34347db3b9d8e75">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">bool</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ad05ea5ba061f9397ac8d15d02d77c812">hasIndex</a> (const MachineInstr &amp;instr) const</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Returns true if the given machine instr is mapped to an index, otherwise returns false. <a href="#ad05ea5ba061f9397ac8d15d02d77c812">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/slotindex">SlotIndex</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#aa429e211fd041cb42d26e49dd5d95d75">getInstructionIndex</a> (const MachineInstr &amp;MI, bool IgnoreBundle=false) const</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Returns the base index for the given instruction. <a href="#aa429e211fd041cb42d26e49dd5d95d75">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/machineinstr">MachineInstr</a> *</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#af454bfc85311cf45162476f6b4e5dee8">getInstructionFromIndex</a> (SlotIndex index) const</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Returns the instruction for the given index, or null if the given index has no instruction associated with it. <a href="#af454bfc85311cf45162476f6b4e5dee8">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/slotindex">SlotIndex</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a7ac607fdc1b84333c84cc74903c352a4">getNextNonNullIndex</a> (SlotIndex Index)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Returns the next non-null index, if one exists. <a href="#a7ac607fdc1b84333c84cc74903c352a4">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/slotindex">SlotIndex</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ae300b9628007f942d7a1b2cfaedc7d48">getIndexBefore</a> (const MachineInstr &amp;MI) const</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>getIndexBefore - Returns the index of the last indexed instruction before MI, or the start index of its basic block. <a href="#ae300b9628007f942d7a1b2cfaedc7d48">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/slotindex">SlotIndex</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#aa8dc9674b9f3ceb9d9f8c62b30d548c8">getIndexAfter</a> (const MachineInstr &amp;MI) const</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>getIndexAfter - Returns the index of the first indexed instruction after MI, or the end index of its basic block. <a href="#aa8dc9674b9f3ceb9d9f8c62b30d548c8">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> std::pair&lt; <a href="/web-llvm/docs/api/classes/llvm/slotindex">SlotIndex</a>, <a href="/web-llvm/docs/api/classes/llvm/slotindex">SlotIndex</a> &gt; &amp;</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a5fc7ba94df57761786b6eed9fb298e7f">getMBBRange</a> (unsigned Num) const</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Return the (start,end) range of the given basic block number. <a href="#a5fc7ba94df57761786b6eed9fb298e7f">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> std::pair&lt; <a href="/web-llvm/docs/api/classes/llvm/slotindex">SlotIndex</a>, <a href="/web-llvm/docs/api/classes/llvm/slotindex">SlotIndex</a> &gt; &amp;</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#af451ff49c872624c4a6edca15f86c15f">getMBBRange</a> (const MachineBasicBlock *MBB) const</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Return the (start,end) range of the given basic block. <a href="#af451ff49c872624c4a6edca15f86c15f">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/slotindex">SlotIndex</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#aaf0c07cc1cdb9c78c6dfdfdd5913420a">getMBBStartIdx</a> (unsigned Num) const</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Returns the first index in the given basic block number. <a href="#aaf0c07cc1cdb9c78c6dfdfdd5913420a">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/slotindex">SlotIndex</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#af3f1e187bfa207f2d69b28b4f33762bc">getMBBStartIdx</a> (const MachineBasicBlock *mbb) const</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Returns the first index in the given basic block. <a href="#af3f1e187bfa207f2d69b28b4f33762bc">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/slotindex">SlotIndex</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a662867d9274595cdac0092afa45888be">getMBBEndIdx</a> (unsigned Num) const</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Returns the last index in the given basic block number. <a href="#a662867d9274595cdac0092afa45888be">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/slotindex">SlotIndex</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#aeaa2d1ed05199629d415c200b6d29464">getMBBEndIdx</a> (const MachineBasicBlock *mbb) const</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Returns the last index in the given basic block. <a href="#aeaa2d1ed05199629d415c200b6d29464">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="#a960aca5467c09d62292856c116ac9291">MBBIndexIterator</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a585f282a33928e37e525e8fe915b2f95">getMBBLowerBound</a> (MBBIndexIterator Start, SlotIndex Idx) const</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Get an iterator pointing to the first <a href="/web-llvm/docs/api/namespaces/llvm/#a906e44aee29a06c01bd067475f10e7b4">IdxMBBPair</a> with <a href="/web-llvm/docs/api/classes/llvm/slotindex">SlotIndex</a> greater than or equal to <span class="doxyComputerOutput">Idx</span>. <a href="#a585f282a33928e37e525e8fe915b2f95">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="#a960aca5467c09d62292856c116ac9291">MBBIndexIterator</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a72118ac84ca6eaa92ca28a05f0c75b4f">getMBBLowerBound</a> (SlotIndex Idx) const</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="#a960aca5467c09d62292856c116ac9291">MBBIndexIterator</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a9a6bc6995f3ffbbbb8ac57ace10bf69e">getMBBUpperBound</a> (SlotIndex Idx) const</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Get an iterator pointing to the first <a href="/web-llvm/docs/api/namespaces/llvm/#a906e44aee29a06c01bd067475f10e7b4">IdxMBBPair</a> with <a href="/web-llvm/docs/api/classes/llvm/slotindex">SlotIndex</a> greater than <span class="doxyComputerOutput">Idx</span>. <a href="#a9a6bc6995f3ffbbbb8ac57ace10bf69e">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="#a960aca5467c09d62292856c116ac9291">MBBIndexIterator</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a75bbfe8114f6c9f657eab3635862096a">MBBIndexBegin</a> () const</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Returns an iterator for the begin of the idx2MBBMap. <a href="#a75bbfe8114f6c9f657eab3635862096a">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="#a960aca5467c09d62292856c116ac9291">MBBIndexIterator</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a93fd119f823122ff34d4da7c927ef2c2">MBBIndexEnd</a> () const</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Return an iterator for the end of the idx2MBBMap. <a href="#a93fd119f823122ff34d4da7c927ef2c2">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/machinebasicblock">MachineBasicBlock</a> *</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a3266945305cfb9bbf018e2fbe5fca335">getMBBFromIndex</a> (SlotIndex index) const</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Returns the basic block which the given index falls in. <a href="#a3266945305cfb9bbf018e2fbe5fca335">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/slotindex">SlotIndex</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a10aea73adf903930a8ce4c133dfa5a1e">insertMachineInstrInMaps</a> (MachineInstr &amp;MI, bool Late=false)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Insert the given machine instruction into the mapping. <a href="#a10aea73adf903930a8ce4c133dfa5a1e">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">void</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a2aace9fd8246b0bdb9c352c5aa32f88d">removeMachineInstrFromMaps</a> (MachineInstr &amp;MI, bool AllowBundled=false)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Removes machine instruction (bundle) <span class="doxyComputerOutput">MI</span> from the mapping. <a href="#a2aace9fd8246b0bdb9c352c5aa32f88d">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">void</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a6deb0bbae86f32a9b473d23778795d0b">removeSingleMachineInstrFromMaps</a> (MachineInstr &amp;MI)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Removes a single machine instruction <span class="doxyComputerOutput">MI</span> from the mapping. <a href="#a6deb0bbae86f32a9b473d23778795d0b">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/slotindex">SlotIndex</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ae59d457759eabf9feb31656d3a8bb8b0">replaceMachineInstrInMaps</a> (MachineInstr &amp;MI, MachineInstr &amp;NewMI)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>ReplaceMachineInstrInMaps - Replacing a machine instr with a new one in maps used by register allocator. <a href="#ae59d457759eabf9feb31656d3a8bb8b0">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">void</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a55bd6e17074a39a9aad2ee8cd6f541fb">insertMBBInMaps</a> (MachineBasicBlock *mbb)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Add the given <a href="/web-llvm/docs/api/classes/llvm/machinebasicblock">MachineBasicBlock</a> into the maps. <a href="#a55bd6e17074a39a9aad2ee8cd6f541fb">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">void</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ac7cbb2d2dbf1e42fd9df000ab172f9cd">packIndexes</a> ()</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Renumber all indexes using the default instruction distance. <a href="#ac7cbb2d2dbf1e42fd9df000ab172f9cd">More...</a></p>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a5468c04e7b4892cba2975af73cee1d7f">clear</a> ()</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#af1d6ddd780d2855886fad30962c2341f">analyze</a> (MachineFunction &amp;MF)</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/indexlistentry">IndexListEntry</a> *</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a50793adf6ce5adaa19babec4c3f5ad3d">createEntry</a> (MachineInstr *mi, unsigned index)</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ac8322d69be5c5a5c8c626e54c91544c3">renumberIndexes</a> (IndexList::iterator curItr)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Renumber locally after inserting curItr. <a href="#ac8322d69be5c5a5c8c626e54c91544c3">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

</table>

## Private Member Attributes Index

<table class="doxyMembersIndex">

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/namespaces/llvm/#a8e612822d4ba7bb36c9c79582a567108">BumpPtrAllocator</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a8094b2baf30ad934a054e61ec4d2c4cf">ileAllocator</a></td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/simple-ilist">IndexList</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a882864181513ff3b61cd2a7cb50e1650">indexList</a></td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/machinefunction">MachineFunction</a> *</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a468eab3f4737076c5b5130ab3faf5986">mf</a> = nullptr</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/densemap">Mi2IndexMap</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a002eb4ce0f0d354554ee222d805cc3d2">mi2iMap</a></td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/smallvector">SmallVector</a>&lt; std::pair&lt; <a href="/web-llvm/docs/api/classes/llvm/slotindex">SlotIndex</a>, <a href="/web-llvm/docs/api/classes/llvm/slotindex">SlotIndex</a> &gt;, 8 &gt;</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a820b80cf98f73aef0b80b275324e4cb5">MBBRanges</a></td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>MBBRanges - Map MBB number to (start, stop) indexes. <a href="#a820b80cf98f73aef0b80b275324e4cb5">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/smallvector">SmallVector</a>&lt; <a href="/web-llvm/docs/api/namespaces/llvm/#a906e44aee29a06c01bd067475f10e7b4">IdxMBBPair</a>, 8 &gt;</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a746367c2957c43eec0fd695aa1e4af19">idx2MBBMap</a></td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Idx2MBBMap - Sorted list of pairs of index of first instruction and MBB id. <a href="#a746367c2957c43eec0fd695aa1e4af19">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

</table>

## Description {#details}

<p><a href="/web-llvm/docs/api/classes/llvm/slotindexes">SlotIndexes</a> pass.</p>


<p>This pass assigns indexes to each instruction.</p>


<p>Definition at line 297 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/codegen/slotindexes-h">SlotIndexes.h</a>.</p>


<div class="doxySectionDef">

## Public Member Typedefs

### MBBIndexIterator {#a960aca5467c09d62292856c116ac9291}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">using llvm::SlotIndexes::MBBIndexIterator =  SmallVectorImpl&lt;IdxMBBPair&gt;::const_iterator</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Iterator over the idx2MBBMap (sorted pairs of slot index of basic block begin and basic block)</p>

<p>Definition at line 481 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/codegen/slotindexes-h">SlotIndexes.h</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Private Member Typedefs

### IndexList {#a5f335b23ff47f871e040ea5c0a9ba9b4}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">using llvm::SlotIndexes::IndexList =  simple_ilist&lt;IndexListEntry&gt;</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 304 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/codegen/slotindexes-h">SlotIndexes.h</a>.</p>

</div>
</div>

### Mi2IndexMap {#ab1f2d617862d9db060b21808f380aa41}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">using llvm::SlotIndexes::Mi2IndexMap =  DenseMap&lt;const MachineInstr *, SlotIndex&gt;</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 309 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/codegen/slotindexes-h">SlotIndexes.h</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Friends

### SlotIndexesWrapperPass {#afdbd6d41821f020763e2216207eba140}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">friend class <a href="/web-llvm/docs/api/classes/llvm/slotindexeswrapperpass">SlotIndexesWrapperPass</a></td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">


<p>Definition at line 298 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/codegen/slotindexes-h">SlotIndexes.h</a>.</p>


<p>Reference <a href="#afdbd6d41821f020763e2216207eba140">SlotIndexesWrapperPass</a>.</p>


<p>Referenced by <a href="#afdbd6d41821f020763e2216207eba140">SlotIndexesWrapperPass</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Public Constructors

### SlotIndexes() {#a2841585dd75b3635949c39269adec017}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">llvm::SlotIndexes::SlotIndexes (<a href="/web-llvm/docs/api/classes/llvm/slotindexes">SlotIndexes</a> &amp;&amp;)</td>
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



<p>Definition at line 340 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/codegen/slotindexes-h">SlotIndexes.h</a>.</p>

</div>
</div>

### SlotIndexes() {#aa3bdaefbd2a25ebb5c3dda49c20b3bcf}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">llvm::SlotIndexes::SlotIndexes (<a href="/web-llvm/docs/api/classes/llvm/machinefunction">MachineFunction</a> &amp; MF)</td>
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



<p>Definition at line 342 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/codegen/slotindexes-h">SlotIndexes.h</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Private Constructors

### SlotIndexes() {#ae597d16319281f1fc8744104e5fc9e36}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">llvm::SlotIndexes::SlotIndexes ()</td>
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



<p>Definition at line 320 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/codegen/slotindexes-h">SlotIndexes.h</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Public Destructor

### \~SlotIndexes() {#aac440a2faa289432c4287f79299139c2}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">SlotIndexes::~SlotIndexes ()</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Declaration at line 344 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/codegen/slotindexes-h">SlotIndexes.h</a>, definition at line 42 of file <a href="/web-llvm/docs/api/files/lib/lib/codegen/slotindexes-cpp">SlotIndexes.cpp</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Public Member Functions

### dump() {#a40e7a4cc6e14f421c36f936f9f8dff58}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">LLVM_DUMP_METHOD void SlotIndexes::dump ()</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Dump the indexes.</p>

<p>Declaration at line 354 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/codegen/slotindexes-h">SlotIndexes.h</a>, definition at line 273 of file <a href="/web-llvm/docs/api/files/lib/lib/codegen/slotindexes-cpp">SlotIndexes.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/namespaces/llvm/#a7c46c742c31be54870e2038048e6b391">llvm::dbgs</a>, <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/support/compiler-h/#aa863693eef567397d9c292da5bf22d34">LLVM_DUMP_METHOD</a> and <a href="#ae0e0577e6178c0dfda4edf688163beea">print</a>.</p>

</div>
</div>

### getIndexAfter() {#aa8dc9674b9f3ceb9d9f8c62b30d548c8}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">SlotIndex llvm::SlotIndexes::getIndexAfter (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/machineinstr">MachineInstr</a> &amp; MI)</td>
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

<p>getIndexAfter - Returns the index of the first indexed instruction after MI, or the end index of its basic block.</p>


<p>MI is not required to have an index.</p>


<p>Definition at line 433 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/codegen/slotindexes-h">SlotIndexes.h</a>.</p>


<p>References <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/silowercontrolflow-cpp/#a4868c5d81c5ccc98c47aeab6244346a0">assert</a>, <a href="/web-llvm/docs/api/files/lib/lib/ir/builtingcs-cpp/#abb2b3a60ccc38a28239e19a1646e0c8a">E</a>, <a href="#a662867d9274595cdac0092afa45888be">getMBBEndIdx</a>, <a href="/web-llvm/docs/api/files/lib/lib/support/md5-cpp/#ac0eafdc9ee161b71e7af98af736952fd">I</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/arm/armslshardening-cpp/#a5958512eae2979bd2eb383977996a600">MBB</a> and <a href="/web-llvm/docs/api/files/lib/lib/codegen/lib/codegen/globalisel/irtranslator-cpp/#abe44dfdea65b4f7e11e0a608ab708b76">MI</a>.</p>


<p>Referenced by <a href="#a10aea73adf903930a8ce4c133dfa5a1e">insertMachineInstrInMaps</a>.</p>

</div>
</div>

### getIndexBefore() {#ae300b9628007f942d7a1b2cfaedc7d48}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">SlotIndex llvm::SlotIndexes::getIndexBefore (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/machineinstr">MachineInstr</a> &amp; MI)</td>
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

<p>getIndexBefore - Returns the index of the last indexed instruction before MI, or the start index of its basic block.</p>


<p>MI is not required to have an index.</p>


<p>Definition at line 416 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/codegen/slotindexes-h">SlotIndexes.h</a>.</p>


<p>References <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/silowercontrolflow-cpp/#a4868c5d81c5ccc98c47aeab6244346a0">assert</a>, <a href="/web-llvm/docs/api/files/lib/lib/ir/builtingcs-cpp/#ae76959fe811ba090de4cba69ac00f1da">B</a>, <a href="#aaf0c07cc1cdb9c78c6dfdfdd5913420a">getMBBStartIdx</a>, <a href="/web-llvm/docs/api/files/lib/lib/support/md5-cpp/#ac0eafdc9ee161b71e7af98af736952fd">I</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/arm/armslshardening-cpp/#a5958512eae2979bd2eb383977996a600">MBB</a> and <a href="/web-llvm/docs/api/files/lib/lib/codegen/lib/codegen/globalisel/irtranslator-cpp/#abe44dfdea65b4f7e11e0a608ab708b76">MI</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/classes/anonymous-livedebugvariables-cpp-/uservalue/#a5addc8b01ca0cce0a572d5fe3ef86654">anonymous{LiveDebugVariables.cpp}::UserValue::computeIntervals</a> and <a href="#a10aea73adf903930a8ce4c133dfa5a1e">insertMachineInstrInMaps</a>.</p>

</div>
</div>

### getInstructionFromIndex() {#af454bfc85311cf45162476f6b4e5dee8}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">MachineInstr * llvm::SlotIndexes::getInstructionFromIndex (<a href="/web-llvm/docs/api/classes/llvm/slotindex">SlotIndex</a> index)</td>
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

<p>Returns the instruction for the given index, or null if the given index has no instruction associated with it.</p>

<p>Definition at line 397 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/codegen/slotindexes-h">SlotIndexes.h</a>.</p>


<p>Reference <a href="/web-llvm/docs/api/classes/llvm/indexlistentry/#a8bfb4079d14047ea3879341e0f2deb86">llvm::IndexListEntry::getInstr</a>.</p>


<p>Referenced by <a href="#a3266945305cfb9bbf018e2fbe5fca335">getMBBFromIndex</a>, <a href="/web-llvm/docs/api/classes/llvm/liverange/#af4d61431580966063160f1cc3fdc1d2e">llvm::LiveRange::overlaps</a>, <a href="/web-llvm/docs/api/classes/llvm/hexagonregisterinfo/#a8a7cb54f8347286b106be184c8c125e1">llvm::HexagonRegisterInfo::shouldCoalesce</a> and <a href="/web-llvm/docs/api/files/lib/lib/codegen/liveinterval-cpp/#aeb309e71b02f8298a437ec465645fe99">stripValuesNotDefiningMask</a>.</p>

</div>
</div>

### getInstructionIndex() {#aa429e211fd041cb42d26e49dd5d95d75}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">SlotIndex llvm::SlotIndexes::getInstructionIndex (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/machineinstr">MachineInstr</a> &amp; MI, bool IgnoreBundle=false)</td>
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

<p>Returns the base index for the given instruction.</p>

<p>Definition at line 379 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/codegen/slotindexes-h">SlotIndexes.h</a>.</p>


<p>References <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/silowercontrolflow-cpp/#a4868c5d81c5ccc98c47aeab6244346a0">assert</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a7f2b7ecbdbe9013ca2794761934d2bd9">llvm::getBundleEnd</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a0b1a8d3b98bc35fd5cb5b04843beeea5">llvm::getBundleStart</a>, <a href="/web-llvm/docs/api/classes/llvm/machineinstr/#a42020afbcac5113c831c00294a0ac37f">llvm::MachineInstr::isDebugInstr</a>, <a href="/web-llvm/docs/api/files/lib/lib/codegen/lib/codegen/globalisel/irtranslator-cpp/#abe44dfdea65b4f7e11e0a608ab708b76">MI</a> and <a href="/web-llvm/docs/api/namespaces/llvm/#a5bacbbd03e9261f7b30dc174f26d680c">llvm::skipDebugInstructionsForward</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/webassembly/webassemblyregcoloring-cpp/#a363e3f71faf094bba68a16bb32f43cff">buildVRegToDbgValueMap</a>, <a href="/web-llvm/docs/api/classes/llvm/liveinterval/#af4a07ae5c460ac08439a1a71d15e0166">llvm::LiveInterval::computeSubRangeUndefs</a>, <a href="/web-llvm/docs/api/files/lib/lib/codegen/liveintervalcalc-cpp/#a70e2de8376b84c468e8a5762fda4c419">createDeadDef</a>, <a href="/web-llvm/docs/api/classes/llvm/systemzinstrinfo/#af3524773747ed9e90b586d5e6752e1c2">llvm::SystemZInstrInfo::foldMemoryOperandImpl</a>, <a href="/web-llvm/docs/api/namespaces/anonymous-riscvinsertvsetvli-cpp-/#a6bdc7e7c639e6ec0018642b921042036">anonymous{RISCVInsertVSETVLI.cpp}::getVNInfoFromReg</a>, <a href="#a55bd6e17074a39a9aad2ee8cd6f541fb">insertMBBInMaps</a>, <a href="/web-llvm/docs/api/classes/llvm/machinebasicblock/#a5a4302f4590a281bb84e08b30c80591c">llvm::MachineBasicBlock::print</a> and <a href="#a453e4d014fa115aebac6e1416cf7d64c">repairIndexesInRange</a>.</p>

</div>
</div>

### getLastIndex() {#a08d65216af6fc79fe34347db3b9d8e75}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">SlotIndex llvm::SlotIndexes::getLastIndex ()</td>
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

<p>Returns the base index of the last slot in this analysis.</p>

<p>Definition at line 368 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/codegen/slotindexes-h">SlotIndexes.h</a>.</p>


<p>Referenced by <a href="#a7ac607fdc1b84333c84cc74903c352a4">getNextNonNullIndex</a>.</p>

</div>
</div>

### getMBBEndIdx() {#a662867d9274595cdac0092afa45888be}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">SlotIndex llvm::SlotIndexes::getMBBEndIdx (unsigned Num)</td>
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

<p>Returns the last index in the given basic block number.</p>

<p>Definition at line 470 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/codegen/slotindexes-h">SlotIndexes.h</a>.</p>


<p>Reference <a href="#a5fc7ba94df57761786b6eed9fb298e7f">getMBBRange</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/webassembly/webassemblyregcoloring-cpp/#a363e3f71faf094bba68a16bb32f43cff">buildVRegToDbgValueMap</a>, <a href="#aa8dc9674b9f3ceb9d9f8c62b30d548c8">getIndexAfter</a>, <a href="#a3266945305cfb9bbf018e2fbe5fca335">getMBBFromIndex</a>, <a href="#a55bd6e17074a39a9aad2ee8cd6f541fb">insertMBBInMaps</a>, <a href="#a453e4d014fa115aebac6e1416cf7d64c">repairIndexesInRange</a>, <a href="/web-llvm/docs/api/structs/llvm/gcnregpressureprinter/#a28746f937314058fd6bfee7784530996">llvm::GCNRegPressurePrinter::runOnMachineFunction</a> and <a href="/web-llvm/docs/api/classes/llvm/machinebasicblock/#aa80aaa82844ab5560ece045eee7b34ac">llvm::MachineBasicBlock::SplitCriticalEdge</a>.</p>

</div>
</div>

### getMBBEndIdx() {#aeaa2d1ed05199629d415c200b6d29464}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">SlotIndex llvm::SlotIndexes::getMBBEndIdx (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/machinebasicblock">MachineBasicBlock</a> * mbb)</td>
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

<p>Returns the last index in the given basic block.</p>

<p>Definition at line 475 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/codegen/slotindexes-h">SlotIndexes.h</a>.</p>


<p>Reference <a href="#a5fc7ba94df57761786b6eed9fb298e7f">getMBBRange</a>.</p>

</div>
</div>

### getMBBFromIndex() {#a3266945305cfb9bbf018e2fbe5fca335}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">MachineBasicBlock * llvm::SlotIndexes::getMBBFromIndex (<a href="/web-llvm/docs/api/classes/llvm/slotindex">SlotIndex</a> index)</td>
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

<p>Returns the basic block which the given index falls in.</p>

<p>Definition at line 515 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/codegen/slotindexes-h">SlotIndexes.h</a>.</p>


<p>References <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/silowercontrolflow-cpp/#a4868c5d81c5ccc98c47aeab6244346a0">assert</a>, <a href="#af454bfc85311cf45162476f6b4e5dee8">getInstructionFromIndex</a>, <a href="#a662867d9274595cdac0092afa45888be">getMBBEndIdx</a>, <a href="#a9a6bc6995f3ffbbbb8ac57ace10bf69e">getMBBUpperBound</a>, <a href="/web-llvm/docs/api/files/lib/lib/support/md5-cpp/#ac0eafdc9ee161b71e7af98af736952fd">I</a>, <a href="#a93fd119f823122ff34d4da7c927ef2c2">MBBIndexEnd</a> and <a href="/web-llvm/docs/api/files/lib/lib/codegen/lib/codegen/globalisel/irtranslator-cpp/#abe44dfdea65b4f7e11e0a608ab708b76">MI</a>.</p>

</div>
</div>

### getMBBLowerBound() {#a585f282a33928e37e525e8fe915b2f95}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">MBBIndexIterator llvm::SlotIndexes::getMBBLowerBound (<a href="#a960aca5467c09d62292856c116ac9291">MBBIndexIterator</a> Start, <a href="/web-llvm/docs/api/classes/llvm/slotindex">SlotIndex</a> Idx)</td>
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

<p>Get an iterator pointing to the first <a href="/web-llvm/docs/api/namespaces/llvm/#a906e44aee29a06c01bd067475f10e7b4">IdxMBBPair</a> with <a href="/web-llvm/docs/api/classes/llvm/slotindex">SlotIndex</a> greater than or equal to <span class="doxyComputerOutput">Idx</span>.</p>


<p>If <span class="doxyComputerOutput">Start</span> is provided, only search the range from <span class="doxyComputerOutput">Start</span> to the end of the function.</p>


<p>Definition at line 486 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/codegen/slotindexes-h">SlotIndexes.h</a>.</p>


<p>Reference <a href="#a93fd119f823122ff34d4da7c927ef2c2">MBBIndexEnd</a>.</p>


<p>Referenced by <a href="#a72118ac84ca6eaa92ca28a05f0c75b4f">getMBBLowerBound</a>.</p>

</div>
</div>

### getMBBLowerBound() {#a72118ac84ca6eaa92ca28a05f0c75b4f}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">MBBIndexIterator llvm::SlotIndexes::getMBBLowerBound (<a href="/web-llvm/docs/api/classes/llvm/slotindex">SlotIndex</a> Idx)</td>
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



<p>Definition at line 492 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/codegen/slotindexes-h">SlotIndexes.h</a>.</p>


<p>References <a href="#a585f282a33928e37e525e8fe915b2f95">getMBBLowerBound</a> and <a href="#a75bbfe8114f6c9f657eab3635862096a">MBBIndexBegin</a>.</p>

</div>
</div>

### getMBBRange() {#a5fc7ba94df57761786b6eed9fb298e7f}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">const std::pair&lt; SlotIndex, SlotIndex &gt; &amp; llvm::SlotIndexes::getMBBRange (unsigned Num)</td>
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

<p>Return the (start,end) range of the given basic block number.</p>

<p>Definition at line 449 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/codegen/slotindexes-h">SlotIndexes.h</a>.</p>


<p>Referenced by <a href="#aeaa2d1ed05199629d415c200b6d29464">getMBBEndIdx</a>, <a href="#a662867d9274595cdac0092afa45888be">getMBBEndIdx</a>, <a href="#af451ff49c872624c4a6edca15f86c15f">getMBBRange</a>, <a href="#af3f1e187bfa207f2d69b28b4f33762bc">getMBBStartIdx</a> and <a href="#aaf0c07cc1cdb9c78c6dfdfdd5913420a">getMBBStartIdx</a>.</p>

</div>
</div>

### getMBBRange() {#af451ff49c872624c4a6edca15f86c15f}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">const std::pair&lt; SlotIndex, SlotIndex &gt; &amp; llvm::SlotIndexes::getMBBRange (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/machinebasicblock">MachineBasicBlock</a> * MBB)</td>
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

<p>Return the (start,end) range of the given basic block.</p>

<p>Definition at line 455 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/codegen/slotindexes-h">SlotIndexes.h</a>.</p>


<p>References <a href="#a5fc7ba94df57761786b6eed9fb298e7f">getMBBRange</a> and <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/arm/armslshardening-cpp/#a5958512eae2979bd2eb383977996a600">MBB</a>.</p>

</div>
</div>

### getMBBStartIdx() {#aaf0c07cc1cdb9c78c6dfdfdd5913420a}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">SlotIndex llvm::SlotIndexes::getMBBStartIdx (unsigned Num)</td>
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

<p>Returns the first index in the given basic block number.</p>

<p>Definition at line 460 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/codegen/slotindexes-h">SlotIndexes.h</a>.</p>


<p>Reference <a href="#a5fc7ba94df57761786b6eed9fb298e7f">getMBBRange</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/webassembly/webassemblyregcoloring-cpp/#a363e3f71faf094bba68a16bb32f43cff">buildVRegToDbgValueMap</a>, <a href="#ae300b9628007f942d7a1b2cfaedc7d48">getIndexBefore</a>, <a href="/web-llvm/docs/api/classes/llvm/machinebasicblock/#a5a4302f4590a281bb84e08b30c80591c">llvm::MachineBasicBlock::print</a>, <a href="#a453e4d014fa115aebac6e1416cf7d64c">repairIndexesInRange</a>, <a href="/web-llvm/docs/api/classes/anonymous-registercoalescer-cpp-/registercoalescer/#aa408ab9747b8ce0bd0a81465c10e8f29">anonymous{RegisterCoalescer.cpp}::RegisterCoalescer::runOnMachineFunction</a>, <a href="/web-llvm/docs/api/structs/llvm/gcnregpressureprinter/#a28746f937314058fd6bfee7784530996">llvm::GCNRegPressurePrinter::runOnMachineFunction</a> and <a href="/web-llvm/docs/api/classes/llvm/livedebugvariables/ldvimpl/#a4e5a4f513cd277250d246664b49e066b">llvm::LiveDebugVariables::LDVImpl::runOnMachineFunction</a>.</p>

</div>
</div>

### getMBBStartIdx() {#af3f1e187bfa207f2d69b28b4f33762bc}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">SlotIndex llvm::SlotIndexes::getMBBStartIdx (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/machinebasicblock">MachineBasicBlock</a> * mbb)</td>
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

<p>Returns the first index in the given basic block.</p>

<p>Definition at line 465 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/codegen/slotindexes-h">SlotIndexes.h</a>.</p>


<p>Reference <a href="#a5fc7ba94df57761786b6eed9fb298e7f">getMBBRange</a>.</p>

</div>
</div>

### getMBBUpperBound() {#a9a6bc6995f3ffbbbb8ac57ace10bf69e}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">MBBIndexIterator llvm::SlotIndexes::getMBBUpperBound (<a href="/web-llvm/docs/api/classes/llvm/slotindex">SlotIndex</a> Idx)</td>
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

<p>Get an iterator pointing to the first <a href="/web-llvm/docs/api/namespaces/llvm/#a906e44aee29a06c01bd067475f10e7b4">IdxMBBPair</a> with <a href="/web-llvm/docs/api/classes/llvm/slotindex">SlotIndex</a> greater than <span class="doxyComputerOutput">Idx</span>.</p>

<p>Definition at line 498 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/codegen/slotindexes-h">SlotIndexes.h</a>.</p>


<p>References <a href="#a75bbfe8114f6c9f657eab3635862096a">MBBIndexBegin</a> and <a href="#a93fd119f823122ff34d4da7c927ef2c2">MBBIndexEnd</a>.</p>


<p>Referenced by <a href="#a3266945305cfb9bbf018e2fbe5fca335">getMBBFromIndex</a>.</p>

</div>
</div>

### getNextNonNullIndex() {#a7ac607fdc1b84333c84cc74903c352a4}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">SlotIndex llvm::SlotIndexes::getNextNonNullIndex (<a href="/web-llvm/docs/api/classes/llvm/slotindex">SlotIndex</a> Index)</td>
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

<p>Returns the next non-null index, if one exists.</p>


<p>Otherwise returns <a href="#a08d65216af6fc79fe34347db3b9d8e75">getLastIndex()</a>.</p>


<p>Definition at line 403 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/codegen/slotindexes-h">SlotIndexes.h</a>.</p>


<p>References <a href="/web-llvm/docs/api/files/lib/lib/ir/builtingcs-cpp/#abb2b3a60ccc38a28239e19a1646e0c8a">E</a>, <a href="#a08d65216af6fc79fe34347db3b9d8e75">getLastIndex</a> and <a href="/web-llvm/docs/api/files/lib/lib/support/md5-cpp/#ac0eafdc9ee161b71e7af98af736952fd">I</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/classes/llvm/liverange/#a61f530037a29a00a48799b14104a68d1">llvm::LiveRange::isZeroLength</a> and <a href="/web-llvm/docs/api/classes/anonymous-amdgpumarklastscratchload-cpp-/amdgpumarklastscratchload/#adb457e87e019538757ec91bec7a7e5f0">anonymous{AMDGPUMarkLastScratchLoad.cpp}::AMDGPUMarkLastScratchLoad::runOnMachineFunction</a>.</p>

</div>
</div>

### getZeroIndex() {#ae87b945bbb68117e870cfca419e4c845}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">SlotIndex llvm::SlotIndexes::getZeroIndex ()</td>
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

<p>Returns the zero index for this analysis.</p>

<p>Definition at line 362 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/codegen/slotindexes-h">SlotIndexes.h</a>.</p>


<p>Reference <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/silowercontrolflow-cpp/#a4868c5d81c5ccc98c47aeab6244346a0">assert</a>.</p>

</div>
</div>

### hasIndex() {#ad05ea5ba061f9397ac8d15d02d77c812}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool llvm::SlotIndexes::hasIndex (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/machineinstr">MachineInstr</a> &amp; instr)</td>
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

<p>Returns true if the given machine instr is mapped to an index, otherwise returns false.</p>

<p>Definition at line 374 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/codegen/slotindexes-h">SlotIndexes.h</a>.</p>


<p>Reference <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64stacktagging-cpp/#a8e818224d2d1de9b995783ff897b0083af12bc59169afda2918e9f23e3501c2b6">instr</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/classes/llvm/machinebasicblock/#a5a4302f4590a281bb84e08b30c80591c">llvm::MachineBasicBlock::print</a>.</p>

</div>
</div>

### insertMachineInstrInMaps() {#a10aea73adf903930a8ce4c133dfa5a1e}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">SlotIndex llvm::SlotIndexes::insertMachineInstrInMaps (<a href="/web-llvm/docs/api/classes/llvm/machineinstr">MachineInstr</a> &amp; MI, bool Late=false)</td>
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

<p>Insert the given machine instruction into the mapping.</p>


<p>Returns the assigned index. If Late is set and there are null indexes between mi's neighboring instructions, create the new index after the null indexes instead of before them.</p>


<p>Definition at line 531 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/codegen/slotindexes-h">SlotIndexes.h</a>.</p>


<p>References <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/silowercontrolflow-cpp/#a4868c5d81c5ccc98c47aeab6244346a0">assert</a>, <a href="#aa8dc9674b9f3ceb9d9f8c62b30d548c8">getIndexAfter</a>, <a href="#ae300b9628007f942d7a1b2cfaedc7d48">getIndexBefore</a>, <a href="/web-llvm/docs/api/classes/llvm/ilist-node-impl/#af719fc783be6589465137d997701a432">llvm::ilist_node_impl&lt; OptionsT &gt;::getIterator</a> and <a href="/web-llvm/docs/api/files/lib/lib/codegen/lib/codegen/globalisel/irtranslator-cpp/#abe44dfdea65b4f7e11e0a608ab708b76">MI</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/silowersgprspills-cpp/#a3c627e9f404e8f9cf66e5a4a27860347">insertCSRRestores</a>, <a href="/web-llvm/docs/api/classes/llvm/siinstrinfo/#a6ef020b54917711fa4fbe9b8ad48258b">llvm::SIInstrInfo::insertScratchExecCopy</a>, <a href="#a453e4d014fa115aebac6e1416cf7d64c">repairIndexesInRange</a>, <a href="/web-llvm/docs/api/classes/llvm/siinstrinfo/#a1e3fa2ce8f194193f39ed6428a86c05f">llvm::SIInstrInfo::restoreExec</a>, <a href="/web-llvm/docs/api/classes/llvm/siregisterinfo/#a2ab71844c6563b3998af3c09ff2e3368">llvm::SIRegisterInfo::restoreSGPR</a>, <a href="/web-llvm/docs/api/classes/anonymous-siformmemoryclauses-cpp-/siformmemoryclauses/#a3b412b093194b8e66d1d42d1cc79d692">anonymous{SIFormMemoryClauses.cpp}::SIFormMemoryClauses::runOnMachineFunction</a> and <a href="/web-llvm/docs/api/classes/llvm/siregisterinfo/#ad48896d5bbe85488559a5007c3a4b7df">llvm::SIRegisterInfo::spillSGPR</a>.</p>

</div>
</div>

### insertMBBInMaps() {#a55bd6e17074a39a9aad2ee8cd6f541fb}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void llvm::SlotIndexes::insertMBBInMaps (<a href="/web-llvm/docs/api/classes/llvm/machinebasicblock">MachineBasicBlock</a> * mbb)</td>
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

<p>Add the given <a href="/web-llvm/docs/api/classes/llvm/machinebasicblock">MachineBasicBlock</a> into the maps.</p>


<p>If it contains any instructions then they must already be in the maps. This is used after a block has been split by moving some suffix of its instructions into a newly created block.</p>


<p>Definition at line 606 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/codegen/slotindexes-h">SlotIndexes.h</a>.</p>


<p>References <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/silowercontrolflow-cpp/#a4868c5d81c5ccc98c47aeab6244346a0">assert</a>, <a href="/web-llvm/docs/api/classes/llvm/machinebasicblock/#a095ce2d870dadf620a4c887ecc0efef8">llvm::MachineBasicBlock::empty</a>, <a href="/web-llvm/docs/api/classes/llvm/machinebasicblock/#aeedc2554f9637d1e27befa7a85c70ec9">llvm::MachineBasicBlock::front</a>, <a href="/web-llvm/docs/api/classes/llvm/machinefunction/#ac8ca28de0f4dcee651340e7ef0c45233">llvm::MachineFunction::front</a>, <a href="#aa429e211fd041cb42d26e49dd5d95d75">getInstructionIndex</a>, <a href="/web-llvm/docs/api/classes/llvm/ilist-node-impl/#af719fc783be6589465137d997701a432">llvm::ilist_node_impl&lt; OptionsT &gt;::getIterator</a>, <a href="#a662867d9274595cdac0092afa45888be">getMBBEndIdx</a>, <a href="/web-llvm/docs/api/classes/llvm/machinebasicblock/#a3aa22d521bd6a7e6b9f35545dc7b0f1e">llvm::MachineBasicBlock::getNumber</a>, <a href="/web-llvm/docs/api/classes/llvm/machinebasicblock/#acf6442108e21e7e5379feb8962de65b7">llvm::MachineBasicBlock::getParent</a> and <a href="/web-llvm/docs/api/namespaces/llvm/#a74cdbd1e4f731e7d7cd83461b8b1de0b">llvm::sort</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/classes/llvm/machinebasicblock/#aa80aaa82844ab5560ece045eee7b34ac">llvm::MachineBasicBlock::SplitCriticalEdge</a>.</p>

</div>
</div>

### MBBIndexBegin() {#a75bbfe8114f6c9f657eab3635862096a}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">MBBIndexIterator llvm::SlotIndexes::MBBIndexBegin ()</td>
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

<p>Returns an iterator for the begin of the idx2MBBMap.</p>

<p>Definition at line 505 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/codegen/slotindexes-h">SlotIndexes.h</a>.</p>


<p>Referenced by <a href="#a72118ac84ca6eaa92ca28a05f0c75b4f">getMBBLowerBound</a> and <a href="#a9a6bc6995f3ffbbbb8ac57ace10bf69e">getMBBUpperBound</a>.</p>

</div>
</div>

### MBBIndexEnd() {#a93fd119f823122ff34d4da7c927ef2c2}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">MBBIndexIterator llvm::SlotIndexes::MBBIndexEnd ()</td>
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

<p>Return an iterator for the end of the idx2MBBMap.</p>

<p>Definition at line 510 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/codegen/slotindexes-h">SlotIndexes.h</a>.</p>


<p>Referenced by <a href="#a3266945305cfb9bbf018e2fbe5fca335">getMBBFromIndex</a>, <a href="#a585f282a33928e37e525e8fe915b2f95">getMBBLowerBound</a> and <a href="#a9a6bc6995f3ffbbbb8ac57ace10bf69e">getMBBUpperBound</a>.</p>

</div>
</div>

### packIndexes() {#ac7cbb2d2dbf1e42fd9df000ab172f9cd}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void SlotIndexes::packIndexes ()</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Renumber all indexes using the default instruction distance.</p>

<p>Declaration at line 636 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/codegen/slotindexes-h">SlotIndexes.h</a>, definition at line 252 of file <a href="/web-llvm/docs/api/files/lib/lib/codegen/slotindexes-cpp">SlotIndexes.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/namespaces/llvm/#a206e2134ddd2312c3488d0632d98f554">llvm::enumerate</a> and <a href="/web-llvm/docs/api/classes/llvm/slotindex/#a5b8b6416308ea52c3b8712b32764c9fea0d0c291488b64cffb191fda8a4e90ef0">llvm::SlotIndex::InstrDist</a>.</p>

</div>
</div>

### print() {#ae0e0577e6178c0dfda4edf688163beea}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void SlotIndexes::print (<a href="/web-llvm/docs/api/classes/llvm/raw-ostream">raw_ostream</a> &amp; OS)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Declaration at line 351 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/codegen/slotindexes-h">SlotIndexes.h</a>, definition at line 257 of file <a href="/web-llvm/docs/api/files/lib/lib/codegen/slotindexes-cpp">SlotIndexes.cpp</a>.</p>


<p>Referenced by <a href="#a40e7a4cc6e14f421c36f936f9f8dff58">dump</a>.</p>

</div>
</div>

### reanalyze() {#a6436a96f9d3be5a2ef92e1ea2b2eb1e7}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void llvm::SlotIndexes::reanalyze (<a href="/web-llvm/docs/api/classes/llvm/machinefunction">MachineFunction</a> &amp; MF)</td>
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



<p>Definition at line 346 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/codegen/slotindexes-h">SlotIndexes.h</a>.</p>

</div>
</div>

### removeMachineInstrFromMaps() {#a2aace9fd8246b0bdb9c352c5aa32f88d}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void SlotIndexes::removeMachineInstrFromMaps (<a href="/web-llvm/docs/api/classes/llvm/machineinstr">MachineInstr</a> &amp; MI, bool AllowBundled=false)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Removes machine instruction (bundle) <span class="doxyComputerOutput">MI</span> from the mapping.</p>


<p>This should be called before <a href="/web-llvm/docs/api/classes/llvm/machineinstr/#ac2421adbb9996e1b15f03a8abb6c70a8">MachineInstr::eraseFromParent()</a> is used to remove a whole bundle or an unbundled instruction. If <span class="doxyComputerOutput">AllowBundled</span> is set then this can be used on a bundled instruction; however, this exists to support handleMoveIntoBundle, and in general removeSingleMachineInstrFromMaps should be used instead.</p>


<p>Declaration at line 577 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/codegen/slotindexes-h">SlotIndexes.h</a>, definition at line 127 of file <a href="/web-llvm/docs/api/files/lib/lib/codegen/slotindexes-cpp">SlotIndexes.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/silowercontrolflow-cpp/#a4868c5d81c5ccc98c47aeab6244346a0">assert</a>, <a href="/web-llvm/docs/api/classes/llvm/indexlistentry/#a8bfb4079d14047ea3879341e0f2deb86">llvm::IndexListEntry::getInstr</a>, <a href="/web-llvm/docs/api/files/lib/lib/codegen/lib/codegen/globalisel/irtranslator-cpp/#abe44dfdea65b4f7e11e0a608ab708b76">MI</a> and <a href="/web-llvm/docs/api/classes/llvm/indexlistentry/#a4833e21157914694621b075b9dac451b">llvm::IndexListEntry::setInstr</a>.</p>


<p>Referenced by <a href="#a453e4d014fa115aebac6e1416cf7d64c">repairIndexesInRange</a>.</p>

</div>
</div>

### removeSingleMachineInstrFromMaps() {#a6deb0bbae86f32a9b473d23778795d0b}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void SlotIndexes::removeSingleMachineInstrFromMaps (<a href="/web-llvm/docs/api/classes/llvm/machineinstr">MachineInstr</a> &amp; MI)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Removes a single machine instruction <span class="doxyComputerOutput">MI</span> from the mapping.</p>


<p>This should be called before <a href="/web-llvm/docs/api/classes/llvm/machineinstr/#a9891e442de101ced8a1533a71511dbed">MachineInstr::eraseFromBundle()</a> is used to remove a single instruction (out of a bundle).</p>


<p>Declaration at line 583 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/codegen/slotindexes-h">SlotIndexes.h</a>, definition at line 143 of file <a href="/web-llvm/docs/api/files/lib/lib/codegen/slotindexes-cpp">SlotIndexes.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/silowercontrolflow-cpp/#a4868c5d81c5ccc98c47aeab6244346a0">assert</a>, <a href="/web-llvm/docs/api/classes/llvm/indexlistentry/#a8bfb4079d14047ea3879341e0f2deb86">llvm::IndexListEntry::getInstr</a>, <a href="/web-llvm/docs/api/files/lib/lib/codegen/lib/codegen/globalisel/irtranslator-cpp/#abe44dfdea65b4f7e11e0a608ab708b76">MI</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#ab13c360340346d082b959b8cd79f2c1a">llvm::Next</a> and <a href="/web-llvm/docs/api/classes/llvm/indexlistentry/#a4833e21157914694621b075b9dac451b">llvm::IndexListEntry::setInstr</a>.</p>

</div>
</div>

### repairIndexesInRange() {#a453e4d014fa115aebac6e1416cf7d64c}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void SlotIndexes::repairIndexesInRange (<a href="/web-llvm/docs/api/classes/llvm/machinebasicblock">MachineBasicBlock</a> * MBB, <a href="/web-llvm/docs/api/classes/llvm/machinebasicblock/#ae34c996b58df9b9ce6695a0c8b70c533">MachineBasicBlock::iterator</a> Begin, <a href="/web-llvm/docs/api/classes/llvm/machinebasicblock/#ae34c996b58df9b9ce6695a0c8b70c533">MachineBasicBlock::iterator</a> End)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Repair indexes after adding and removing instructions.</p>

<p>Declaration at line 357 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/codegen/slotindexes-h">SlotIndexes.h</a>, definition at line 191 of file <a href="/web-llvm/docs/api/files/lib/lib/codegen/slotindexes-cpp">SlotIndexes.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/silowercontrolflow-cpp/#a4868c5d81c5ccc98c47aeab6244346a0">assert</a>, <a href="#aa429e211fd041cb42d26e49dd5d95d75">getInstructionIndex</a>, <a href="/web-llvm/docs/api/classes/llvm/ilist-node-impl/#af719fc783be6589465137d997701a432">llvm::ilist_node_impl&lt; OptionsT &gt;::getIterator</a>, <a href="#a662867d9274595cdac0092afa45888be">getMBBEndIdx</a>, <a href="#aaf0c07cc1cdb9c78c6dfdfdd5913420a">getMBBStartIdx</a>, <a href="/web-llvm/docs/api/files/lib/lib/support/md5-cpp/#ac0eafdc9ee161b71e7af98af736952fd">I</a>, <a href="#a10aea73adf903930a8ce4c133dfa5a1e">insertMachineInstrInMaps</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/arm/armslshardening-cpp/#a5958512eae2979bd2eb383977996a600">MBB</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/arm/armslshardening-cpp/#ad5f691fdc1a09aaf6df5fef958b35a3d">MBBI</a>, <a href="/web-llvm/docs/api/files/lib/lib/codegen/lib/codegen/globalisel/irtranslator-cpp/#abe44dfdea65b4f7e11e0a608ab708b76">MI</a> and <a href="#a2aace9fd8246b0bdb9c352c5aa32f88d">removeMachineInstrFromMaps</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/classes/anonymous-hexagontfrcleanup-cpp-/hexagontfrcleanup/#aa7619322b2d38567f6b30b0bc454a28e">anonymous{HexagonTfrCleanup.cpp}::HexagonTfrCleanup::runOnMachineFunction</a>.</p>

</div>
</div>

### replaceMachineInstrInMaps() {#ae59d457759eabf9feb31656d3a8bb8b0}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">SlotIndex llvm::SlotIndexes::replaceMachineInstrInMaps (<a href="/web-llvm/docs/api/classes/llvm/machineinstr">MachineInstr</a> &amp; MI, <a href="/web-llvm/docs/api/classes/llvm/machineinstr">MachineInstr</a> &amp; NewMI)</td>
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

<p>ReplaceMachineInstrInMaps - Replacing a machine instr with a new one in maps used by register allocator.</p>


<dl class="doxySectionUser">
<dt>Returns</dt>
<dd><p>the index where the new instruction was inserted.</p></dd>
</dl>


<p>Definition at line 588 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/codegen/slotindexes-h">SlotIndexes.h</a>.</p>


<p>References <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/silowercontrolflow-cpp/#a4868c5d81c5ccc98c47aeab6244346a0">assert</a>, <a href="/web-llvm/docs/api/classes/llvm/indexlistentry/#a8bfb4079d14047ea3879341e0f2deb86">llvm::IndexListEntry::getInstr</a>, <a href="/web-llvm/docs/api/files/lib/lib/codegen/lib/codegen/globalisel/irtranslator-cpp/#abe44dfdea65b4f7e11e0a608ab708b76">MI</a> and <a href="/web-llvm/docs/api/classes/llvm/indexlistentry/#a4833e21157914694621b075b9dac451b">llvm::IndexListEntry::setInstr</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/classes/llvm/siregisterinfo/#a2ab71844c6563b3998af3c09ff2e3368">llvm::SIRegisterInfo::restoreSGPR</a> and <a href="/web-llvm/docs/api/classes/llvm/siregisterinfo/#ad48896d5bbe85488559a5007c3a4b7df">llvm::SIRegisterInfo::spillSGPR</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Private Member Functions

### analyze() {#af1d6ddd780d2855886fad30962c2341f}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void SlotIndexes::analyze (<a href="/web-llvm/docs/api/classes/llvm/machinefunction">MachineFunction</a> &amp; MF)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Declaration at line 324 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/codegen/slotindexes-h">SlotIndexes.h</a>, definition at line 65 of file <a href="/web-llvm/docs/api/files/lib/lib/codegen/slotindexes-cpp">SlotIndexes.cpp</a>.</p>

</div>
</div>

### clear() {#a5468c04e7b4892cba2975af73cee1d7f}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void SlotIndexes::clear ()</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Declaration at line 322 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/codegen/slotindexes-h">SlotIndexes.h</a>, definition at line 57 of file <a href="/web-llvm/docs/api/files/lib/lib/codegen/slotindexes-cpp">SlotIndexes.cpp</a>.</p>

</div>
</div>

### createEntry() {#a50793adf6ce5adaa19babec4c3f5ad3d}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">IndexListEntry * llvm::SlotIndexes::createEntry (<a href="/web-llvm/docs/api/classes/llvm/machineinstr">MachineInstr</a> * mi, unsigned index)</td>
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



<p>Definition at line 326 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/codegen/slotindexes-h">SlotIndexes.h</a>.</p>

</div>
</div>

### renumberIndexes() {#ac8322d69be5c5a5c8c626e54c91544c3}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void SlotIndexes::renumberIndexes (<a href="/web-llvm/docs/api/classes/llvm/simple-ilist/#aaa26237d7a40d3f5207b306d693babbd">IndexList::iterator</a> curItr)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Renumber locally after inserting curItr.</p>

<p>Declaration at line 337 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/codegen/slotindexes-h">SlotIndexes.h</a>, definition at line 172 of file <a href="/web-llvm/docs/api/files/lib/lib/codegen/slotindexes-cpp">SlotIndexes.cpp</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Private Member Attributes

### idx2MBBMap {#a746367c2957c43eec0fd695aa1e4af19}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">SmallVector&lt;IdxMBBPair, 8&gt; llvm::SlotIndexes::idx2MBBMap</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Idx2MBBMap - Sorted list of pairs of index of first instruction and MBB id.</p>

<p>Definition at line 317 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/codegen/slotindexes-h">SlotIndexes.h</a>.</p>

</div>
</div>

### ileAllocator {#a8094b2baf30ad934a054e61ec4d2c4cf}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">BumpPtrAllocator llvm::SlotIndexes::ileAllocator</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 302 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/codegen/slotindexes-h">SlotIndexes.h</a>.</p>

</div>
</div>

### indexList {#a882864181513ff3b61cd2a7cb50e1650}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">IndexList llvm::SlotIndexes::indexList</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 305 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/codegen/slotindexes-h">SlotIndexes.h</a>.</p>

</div>
</div>

### MBBRanges {#a820b80cf98f73aef0b80b275324e4cb5}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">SmallVector&lt;std::pair&lt;SlotIndex, SlotIndex&gt;, 8&gt; llvm::SlotIndexes::MBBRanges</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>MBBRanges - Map MBB number to (start, stop) indexes.</p>

<p>Definition at line 313 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/codegen/slotindexes-h">SlotIndexes.h</a>.</p>

</div>
</div>

### mf {#a468eab3f4737076c5b5130ab3faf5986}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">MachineFunction* llvm::SlotIndexes::mf = nullptr</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 307 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/codegen/slotindexes-h">SlotIndexes.h</a>.</p>

</div>
</div>

### mi2iMap {#a002eb4ce0f0d354554ee222d805cc3d2}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">Mi2IndexMap llvm::SlotIndexes::mi2iMap</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 310 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/codegen/slotindexes-h">SlotIndexes.h</a>.</p>

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

<p class="doxyGeneratedBy">Generated via <a href="https://github.com/xpack/doxygen2docusaurus">doxygen2docusaurus</a> by <a href="https://www.doxygen.nl">Doxygen</a> 1.14.0.</p>

</div>
