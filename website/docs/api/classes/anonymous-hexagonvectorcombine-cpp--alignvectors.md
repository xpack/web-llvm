---

# DO NOT EDIT!
# Automatically generated via doxygen2docusaurus by Doxygen.

slug: /api/classes/anonymous-hexagonvectorcombine-cpp-/alignvectors
custom_edit_url: null
toc_max_heading_level: 4
keywords:
  - doxygen
  - reference
  - class

---

<div class="doxyPage">

# `AlignVectors` Class



## Declaration

<div class="doxyDeclaration">
class anonymous{HexagonVectorCombine.cpp}::AlignVectors { ... }
</div>

## Private Member Typedefs Index

<table class="doxyMembersIndex">

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">using</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a03701c4c3bbfe9942fa3ff01212c6b54">InstList</a> = std::vector&lt; <a href="/web-llvm/docs/api/classes/llvm/instruction">Instruction</a> * &gt;</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a108bfa56a2bd7beabba8cf5d233acb99">InstMap</a> = <a href="/web-llvm/docs/api/classes/llvm/densemap">DenseMap</a>&lt; <a href="/web-llvm/docs/api/classes/llvm/instruction">Instruction</a> *, <a href="/web-llvm/docs/api/classes/llvm/instruction">Instruction</a> * &gt;</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a85d53c265b74f8cbe644d58f077fc9c4">AddrList</a> = std::vector&lt; AddrInfo &gt;</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a1c2b43d47ca759b828e51aa100e998e0">DepList</a> = std::set&lt; <a href="/web-llvm/docs/api/classes/llvm/instruction">Instruction</a> *, InstrLess &gt;</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#abc18e02675f6d3e9b2c01a5507fd6af5">MoveList</a> = std::vector&lt; MoveGroup &gt;</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/raw-ostream">raw_ostream</a> &amp;</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#af86eed218a2f23e635b305f41b7776c3">operator&lt;&lt;</a></td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/raw-ostream">raw_ostream</a> &amp;</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a3789ab3a37c200857c779df88cb1eb66">operator&lt;&lt;</a></td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/raw-ostream">raw_ostream</a> &amp;</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a7ffda6fa2834d056ca241fdfdaf0d295">operator&lt;&lt;</a></td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/raw-ostream">raw_ostream</a> &amp;</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a26cf3791a03bbae7e52e4c0ed4c56c1d">operator&lt;&lt;</a></td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a048d7ea6a08f90db101b47ef7222dcbc">AlignVectors</a> (const HexagonVectorCombine &amp;HVC_)</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a7dcfba7d6e95162242f017635caffdab">run</a> ()</td>
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
<td class="doxyMemberIndexTemplate" colspan="2"><div>template &lt;typename T&gt;</div></td>
</tr>
<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemTypeTemplate" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/densemap">InstMap</a></td>
<td class="doxyMemberIndexItemNameTemplate" align="left" valign="top"><a href="#a1fd5c12cfca233a4f1c67d08934dc672">cloneBefore</a> (BasicBlock::iterator To, T &amp;&amp;Insts) const</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/structs/llvm/align">Align</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#aca38cd8c6b8f845c21b772f0aa0b6d00">getAlignFromValue</a> (const Value *V) const</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">std::optional&lt; AddrInfo &gt;</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a8dcf831f825ecd5ced06e1976bb32e64">getAddrInfo</a> (Instruction &amp;In) const</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ab73bbd5379cbdbe02734483e7c0a75e2">isHvx</a> (const AddrInfo &amp;AI) const</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a29639e792be8613a455e17f37c0fdaca">isSectorTy</a> (Type *Ty) const</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a88aa1296a7b6936875f8b36070cb7dc2">getPayload</a> (Value *Val) const</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a7e16ae35c9a29f6d92b697e8131a5aa2">getMask</a> (Value *Val) const</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#aa95749066f9fb0c77863d6ad7afa3980">getPassThrough</a> (Value *Val) const</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a65390852210625732be8f09dc5efcfa7">createAdjustedPointer</a> (IRBuilderBase &amp;Builder, Value *Ptr, Type *ValTy, int Adjust, const InstMap &amp;CloneMap=InstMap()) const</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a6c94b01ce3fc8ddba51b6d54cf96c5cd">createAlignedPointer</a> (IRBuilderBase &amp;Builder, Value *Ptr, Type *ValTy, int Alignment, const InstMap &amp;CloneMap=InstMap()) const</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ac96feef306d71ce55efb09dcd186211b">createLoad</a> (IRBuilderBase &amp;Builder, Type *ValTy, Value *Ptr, Value *Predicate, int Alignment, Value *Mask, Value *PassThru, ArrayRef&lt; Value * &gt; MDSources={}) const</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a86a2978bd142d12b9212d1a151097867">createSimpleLoad</a> (IRBuilderBase &amp;Builder, Type *ValTy, Value *Ptr, int Alignment, ArrayRef&lt; Value * &gt; MDSources={}) const</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a64dbaeffe5ed6d36fc9e385d8463ace5">createStore</a> (IRBuilderBase &amp;Builder, Value *Val, Value *Ptr, Value *Predicate, int Alignment, Value *Mask, ArrayRef&lt; Value * &gt; MDSources={}) const</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a009a06a38cea706ec867a3d4e9a7fef1">createSimpleStore</a> (IRBuilderBase &amp;Builder, Value *Val, Value *Ptr, int Alignment, ArrayRef&lt; Value * &gt; MDSources={}) const</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#aacceaa210f75e9326452832a0e0a6213">createPredicatedLoad</a> (IRBuilderBase &amp;Builder, Type *ValTy, Value *Ptr, Value *Predicate, int Alignment, ArrayRef&lt; Value * &gt; MDSources={}) const</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a3e12737014a7e50547c492871614105e">createPredicatedStore</a> (IRBuilderBase &amp;Builder, Value *Val, Value *Ptr, Value *Predicate, int Alignment, ArrayRef&lt; Value * &gt; MDSources={}) const</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">DepList</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a92e73a5c61e9e6aa1ec394e69eed9ac5">getUpwardDeps</a> (Instruction *In, Instruction *Base) const</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ac5bd8f768a034af15f391744fb4ea359">createAddressGroups</a> ()</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">MoveList</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a34dc3d4f358c28b8b179b6902bf262af">createLoadGroups</a> (const AddrList &amp;Group) const</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">MoveList</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#afd6ebaca7c6beaede8ecbf51dbae63cb">createStoreGroups</a> (const AddrList &amp;Group) const</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ab49a8d46898fb4a2ad6491636f3c421e">moveTogether</a> (MoveGroup &amp;Move) const</td>
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
<td class="doxyMemberIndexTemplate" colspan="2"><div>template &lt;typename T&gt;</div></td>
</tr>
<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemTypeTemplate" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/densemap">InstMap</a></td>
<td class="doxyMemberIndexItemNameTemplate" align="left" valign="top"><a href="#a952367da29c2c13e18547526f3a58362">cloneBefore</a> (BasicBlock::iterator To, T &amp;&amp;Insts) const</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ab307f772aabfb93fa78f9b417c56c53a">realignLoadGroup</a> (IRBuilderBase &amp;Builder, const ByteSpan &amp;VSpan, int ScLen, Value *AlignVal, Value *AlignAddr) const</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a54625ad5c5136694cf0dd031097fe10f">realignStoreGroup</a> (IRBuilderBase &amp;Builder, const ByteSpan &amp;VSpan, int ScLen, Value *AlignVal, Value *AlignAddr) const</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ad3f154c94ca78d2e16deb266c56a4da5">realignGroup</a> (const MoveGroup &amp;Move) const</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a40bc3e29ca85451da5f83598a0ab966a">makeTestIfUnaligned</a> (IRBuilderBase &amp;Builder, Value *AlignVal, int Alignment) const</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">std::map&lt; <a href="/web-llvm/docs/api/classes/llvm/instruction">Instruction</a> *, AddrList &gt;</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a7a342982bc0a5949e38ffe563e8d51f6">AddrGroups</a></td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/anonymous-hexagonvectorcombine-cpp-/hexagonvectorcombine">HexagonVectorCombine</a> &amp;</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a27673916bc359d404097367bd4d6c99e">HVC</a></td>
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


<p>Definition at line 183 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/hexagon/hexagonvectorcombine-cpp">HexagonVectorCombine.cpp</a>.</p>


<div class="doxySectionDef">

## Private Member Typedefs

### AddrList {#a85d53c265b74f8cbe644d58f077fc9c4}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">using anonymous{HexagonVectorCombine.cpp}::AlignVectors::AddrList =  std::vector&lt;AddrInfo&gt;</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 224 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/hexagon/hexagonvectorcombine-cpp">HexagonVectorCombine.cpp</a>.</p>

</div>
</div>

### DepList {#a1c2b43d47ca759b828e51aa100e998e0}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">using anonymous{HexagonVectorCombine.cpp}::AlignVectors::DepList =  std::set&lt;Instruction *, InstrLess&gt;</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 231 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/hexagon/hexagonvectorcombine-cpp">HexagonVectorCombine.cpp</a>.</p>

</div>
</div>

### InstList {#a03701c4c3bbfe9942fa3ff01212c6b54}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">using anonymous{HexagonVectorCombine.cpp}::AlignVectors::InstList =  std::vector&lt;Instruction *&gt;</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 204 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/hexagon/hexagonvectorcombine-cpp">HexagonVectorCombine.cpp</a>.</p>

</div>
</div>

### InstMap {#a108bfa56a2bd7beabba8cf5d233acb99}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">using anonymous{HexagonVectorCombine.cpp}::AlignVectors::InstMap =  DenseMap&lt;Instruction *, Instruction *&gt;</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 205 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/hexagon/hexagonvectorcombine-cpp">HexagonVectorCombine.cpp</a>.</p>

</div>
</div>

### MoveList {#abc18e02675f6d3e9b2c01a5507fd6af5}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">using anonymous{HexagonVectorCombine.cpp}::AlignVectors::MoveList =  std::vector&lt;MoveGroup&gt;</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 244 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/hexagon/hexagonvectorcombine-cpp">HexagonVectorCombine.cpp</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Friends

### operator&lt;&lt; {#af86eed218a2f23e635b305f41b7776c3}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">friend <a href="/web-llvm/docs/api/classes/llvm/raw-ostream">raw_ostream</a> &amp; <a href="/web-llvm/docs/api/classes/llvm/raw-ostream">raw_ostream</a> &amp; OS, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> AddrInfo &amp; AI</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">


<p>Definition at line 357 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/hexagon/hexagonvectorcombine-cpp">HexagonVectorCombine.cpp</a>.</p>


<p>Reference <a href="/web-llvm/docs/api/structs/llvm/align/#a80735739b49cf97a491922c8f9af2cc1">llvm::Align::value</a>.</p>

</div>
</div>

### operator&lt;&lt; {#a3789ab3a37c200857c779df88cb1eb66}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">friend <a href="/web-llvm/docs/api/classes/llvm/raw-ostream">raw_ostream</a> &amp; <a href="/web-llvm/docs/api/classes/llvm/raw-ostream">raw_ostream</a> &amp; OS, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> MoveGroup &amp; MG</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">


<p>Definition at line 358 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/hexagon/hexagonvectorcombine-cpp">HexagonVectorCombine.cpp</a>.</p>


<p>Reference <a href="/web-llvm/docs/api/files/lib/lib/support/md5-cpp/#ac0eafdc9ee161b71e7af98af736952fd">I</a>.</p>

</div>
</div>

### operator&lt;&lt; {#a7ffda6fa2834d056ca241fdfdaf0d295}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">friend <a href="/web-llvm/docs/api/classes/llvm/raw-ostream">raw_ostream</a> &amp; <a href="/web-llvm/docs/api/classes/llvm/raw-ostream">raw_ostream</a> &amp; OS, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/structs/anonymous-hexagonvectorcombine-cpp-/alignvectors/bytespan/block">ByteSpan::Block</a> &amp; B</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">


<p>Definition at line 359 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/hexagon/hexagonvectorcombine-cpp">HexagonVectorCombine.cpp</a>.</p>


<p>Reference <a href="/web-llvm/docs/api/files/lib/lib/ir/builtingcs-cpp/#ae76959fe811ba090de4cba69ac00f1da">B</a>.</p>

</div>
</div>

### operator&lt;&lt; {#a26cf3791a03bbae7e52e4c0ed4c56c1d}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">friend <a href="/web-llvm/docs/api/classes/llvm/raw-ostream">raw_ostream</a> &amp; <a href="/web-llvm/docs/api/classes/llvm/raw-ostream">raw_ostream</a> &amp; OS, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> ByteSpan &amp; BS</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">


<p>Definition at line 360 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/hexagon/hexagonvectorcombine-cpp">HexagonVectorCombine.cpp</a>.</p>


<p>Reference <a href="/web-llvm/docs/api/files/lib/lib/ir/builtingcs-cpp/#ae76959fe811ba090de4cba69ac00f1da">B</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Public Constructors

### AlignVectors() {#a048d7ea6a08f90db101b47ef7222dcbc}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">anonymous{HexagonVectorCombine.cpp}::AlignVectors::AlignVectors (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/anonymous-hexagonvectorcombine-cpp-/hexagonvectorcombine">HexagonVectorCombine</a> &amp; HVC_)</td>
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



<p>Definition at line 199 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/hexagon/hexagonvectorcombine-cpp">HexagonVectorCombine.cpp</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/classes/anonymous-hexagonvectorcombine-cpp-/hexagonvectorcombine/#afdfbd9fd3f130ac0d25f12d43f34a439">anonymous{HexagonVectorCombine.cpp}::HexagonVectorCombine::run</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Public Member Functions

### cloneBefore() {#a1fd5c12cfca233a4f1c67d08934dc672}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<div class="doxyMemberTemplate">template &lt;typename T&gt;</div>
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">InstMap anonymous{HexagonVectorCombine.cpp}::AlignVectors::cloneBefore (<a href="/web-llvm/docs/api/classes/llvm/basicblock/#a98c0a84a5dfa8bce341c829709f171e5">BasicBlock::iterator</a> To, T &amp;&amp; Insts)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 1080 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/hexagon/hexagonvectorcombine-cpp">HexagonVectorCombine.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/silowercontrolflow-cpp/#a4868c5d81c5ccc98c47aeab6244346a0">assert</a>, <a href="/web-llvm/docs/api/namespaces/llvm/callingconv/#ac6aa1387c4375260e2468eb5a77fdb4cafd841a49aec1539bc88abc8ff9e170fb">llvm::CallingConv::C</a> and <a href="/web-llvm/docs/api/files/lib/lib/support/md5-cpp/#ac0eafdc9ee161b71e7af98af736952fd">I</a>.</p>

</div>
</div>

### run() {#a7dcfba7d6e95162242f017635caffdab}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">auto AlignVectors::run ()</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 201 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/hexagon/hexagonvectorcombine-cpp">HexagonVectorCombine.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/namespaces/llvm/#a39d3d23a084c4544ee5903203db10e8a">llvm::append_range</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a7c46c742c31be54870e2038048e6b391">llvm::dbgs</a>, <a href="/web-llvm/docs/api/files/lib/lib/support/md5-cpp/#ad96b7cf3182ce2ba85e5a7a93b12c441">G</a>, <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/support/debug-h/#a196897517069dda1bdb549e24468f7d7">LLVM_DEBUG</a> and <a href="/web-llvm/docs/api/namespaces/anonymous-hexagonvectorcombine-cpp-/#a0a21c76c62a2c0a30b2059b5abafb61d">anonymous{HexagonVectorCombine.cpp}::VAGroupCountLimit</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Private Member Functions

### cloneBefore() {#a952367da29c2c13e18547526f3a58362}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<div class="doxyMemberTemplate">template &lt;typename T&gt;</div>
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">InstMap anonymous{HexagonVectorCombine.cpp}::AlignVectors::cloneBefore (<a href="/web-llvm/docs/api/classes/llvm/basicblock/#a98c0a84a5dfa8bce341c829709f171e5">BasicBlock::iterator</a> To, T &amp;&amp; Insts)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 346 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/hexagon/hexagonvectorcombine-cpp">HexagonVectorCombine.cpp</a>.</p>

</div>
</div>

### createAddressGroups() {#ac5bd8f768a034af15f391744fb4ea359}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">auto AlignVectors::createAddressGroups ()</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 341 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/hexagon/hexagonvectorcombine-cpp">HexagonVectorCombine.cpp</a>.</p>

</div>
</div>

### createAdjustedPointer() {#a65390852210625732be8f09dc5efcfa7}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">auto AlignVectors::createAdjustedPointer (<a href="/web-llvm/docs/api/classes/llvm/irbuilderbase">IRBuilderBase</a> &amp; Builder, <a href="/web-llvm/docs/api/classes/llvm/value">Value</a> * Ptr, <a href="/web-llvm/docs/api/classes/llvm/type">Type</a> * ValTy, int Adjust, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/densemap">InstMap</a> &amp; CloneMap=<a href="/web-llvm/docs/api/classes/llvm/densemap">InstMap</a>())</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 312 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/hexagon/hexagonvectorcombine-cpp">HexagonVectorCombine.cpp</a>.</p>

</div>
</div>

### createAlignedPointer() {#a6c94b01ce3fc8ddba51b6d54cf96c5cd}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">auto AlignVectors::createAlignedPointer (<a href="/web-llvm/docs/api/classes/llvm/irbuilderbase">IRBuilderBase</a> &amp; Builder, <a href="/web-llvm/docs/api/classes/llvm/value">Value</a> * Ptr, <a href="/web-llvm/docs/api/classes/llvm/type">Type</a> * ValTy, int Alignment, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/densemap">InstMap</a> &amp; CloneMap=<a href="/web-llvm/docs/api/classes/llvm/densemap">InstMap</a>())</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 315 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/hexagon/hexagonvectorcombine-cpp">HexagonVectorCombine.cpp</a>.</p>

</div>
</div>

### createLoad() {#ac96feef306d71ce55efb09dcd186211b}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">auto AlignVectors::createLoad (<a href="/web-llvm/docs/api/classes/llvm/irbuilderbase">IRBuilderBase</a> &amp; Builder, <a href="/web-llvm/docs/api/classes/llvm/type">Type</a> * ValTy, <a href="/web-llvm/docs/api/classes/llvm/value">Value</a> * Ptr, <a href="/web-llvm/docs/api/classes/llvm/value">Value</a> * Predicate, int Alignment, <a href="/web-llvm/docs/api/classes/llvm/value">Value</a> * Mask, <a href="/web-llvm/docs/api/classes/llvm/value">Value</a> * PassThru, <a href="/web-llvm/docs/api/classes/llvm/arrayref">ArrayRef</a>&lt; <a href="/web-llvm/docs/api/classes/llvm/value">Value</a> * &gt; MDSources={})</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 319 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/hexagon/hexagonvectorcombine-cpp">HexagonVectorCombine.cpp</a>.</p>

</div>
</div>

### createLoadGroups() {#a34dc3d4f358c28b8b179b6902bf262af}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">auto AlignVectors::createLoadGroups (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> AddrList &amp; Group)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 342 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/hexagon/hexagonvectorcombine-cpp">HexagonVectorCombine.cpp</a>.</p>

</div>
</div>

### createPredicatedLoad() {#aacceaa210f75e9326452832a0e0a6213}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">auto AlignVectors::createPredicatedLoad (<a href="/web-llvm/docs/api/classes/llvm/irbuilderbase">IRBuilderBase</a> &amp; Builder, <a href="/web-llvm/docs/api/classes/llvm/type">Type</a> * ValTy, <a href="/web-llvm/docs/api/classes/llvm/value">Value</a> * Ptr, <a href="/web-llvm/docs/api/classes/llvm/value">Value</a> * Predicate, int Alignment, <a href="/web-llvm/docs/api/classes/llvm/arrayref">ArrayRef</a>&lt; <a href="/web-llvm/docs/api/classes/llvm/value">Value</a> * &gt; MDSources={})</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 333 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/hexagon/hexagonvectorcombine-cpp">HexagonVectorCombine.cpp</a>.</p>

</div>
</div>

### createPredicatedStore() {#a3e12737014a7e50547c492871614105e}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">auto AlignVectors::createPredicatedStore (<a href="/web-llvm/docs/api/classes/llvm/irbuilderbase">IRBuilderBase</a> &amp; Builder, <a href="/web-llvm/docs/api/classes/llvm/value">Value</a> * Val, <a href="/web-llvm/docs/api/classes/llvm/value">Value</a> * Ptr, <a href="/web-llvm/docs/api/classes/llvm/value">Value</a> * Predicate, int Alignment, <a href="/web-llvm/docs/api/classes/llvm/arrayref">ArrayRef</a>&lt; <a href="/web-llvm/docs/api/classes/llvm/value">Value</a> * &gt; MDSources={})</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 336 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/hexagon/hexagonvectorcombine-cpp">HexagonVectorCombine.cpp</a>.</p>

</div>
</div>

### createSimpleLoad() {#a86a2978bd142d12b9212d1a151097867}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">auto AlignVectors::createSimpleLoad (<a href="/web-llvm/docs/api/classes/llvm/irbuilderbase">IRBuilderBase</a> &amp; Builder, <a href="/web-llvm/docs/api/classes/llvm/type">Type</a> * ValTy, <a href="/web-llvm/docs/api/classes/llvm/value">Value</a> * Ptr, int Alignment, <a href="/web-llvm/docs/api/classes/llvm/arrayref">ArrayRef</a>&lt; <a href="/web-llvm/docs/api/classes/llvm/value">Value</a> * &gt; MDSources={})</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 322 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/hexagon/hexagonvectorcombine-cpp">HexagonVectorCombine.cpp</a>.</p>

</div>
</div>

### createSimpleStore() {#a009a06a38cea706ec867a3d4e9a7fef1}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">auto AlignVectors::createSimpleStore (<a href="/web-llvm/docs/api/classes/llvm/irbuilderbase">IRBuilderBase</a> &amp; Builder, <a href="/web-llvm/docs/api/classes/llvm/value">Value</a> * Val, <a href="/web-llvm/docs/api/classes/llvm/value">Value</a> * Ptr, int Alignment, <a href="/web-llvm/docs/api/classes/llvm/arrayref">ArrayRef</a>&lt; <a href="/web-llvm/docs/api/classes/llvm/value">Value</a> * &gt; MDSources={})</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 329 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/hexagon/hexagonvectorcombine-cpp">HexagonVectorCombine.cpp</a>.</p>

</div>
</div>

### createStore() {#a64dbaeffe5ed6d36fc9e385d8463ace5}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">auto AlignVectors::createStore (<a href="/web-llvm/docs/api/classes/llvm/irbuilderbase">IRBuilderBase</a> &amp; Builder, <a href="/web-llvm/docs/api/classes/llvm/value">Value</a> * Val, <a href="/web-llvm/docs/api/classes/llvm/value">Value</a> * Ptr, <a href="/web-llvm/docs/api/classes/llvm/value">Value</a> * Predicate, int Alignment, <a href="/web-llvm/docs/api/classes/llvm/value">Value</a> * Mask, <a href="/web-llvm/docs/api/classes/llvm/arrayref">ArrayRef</a>&lt; <a href="/web-llvm/docs/api/classes/llvm/value">Value</a> * &gt; MDSources={})</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 326 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/hexagon/hexagonvectorcombine-cpp">HexagonVectorCombine.cpp</a>.</p>

</div>
</div>

### createStoreGroups() {#afd6ebaca7c6beaede8ecbf51dbae63cb}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">auto AlignVectors::createStoreGroups (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> AddrList &amp; Group)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 343 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/hexagon/hexagonvectorcombine-cpp">HexagonVectorCombine.cpp</a>.</p>

</div>
</div>

### getAddrInfo() {#a8dcf831f825ecd5ced06e1976bb32e64}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">auto AlignVectors::getAddrInfo (<a href="/web-llvm/docs/api/classes/llvm/instruction">Instruction</a> &amp; In)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 303 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/hexagon/hexagonvectorcombine-cpp">HexagonVectorCombine.cpp</a>.</p>

</div>
</div>

### getAlignFromValue() {#aca38cd8c6b8f845c21b772f0aa0b6d00}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">auto AlignVectors::getAlignFromValue (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/value">Value</a> * V)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 302 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/hexagon/hexagonvectorcombine-cpp">HexagonVectorCombine.cpp</a>.</p>

</div>
</div>

### getMask() {#a7e16ae35c9a29f6d92b697e8131a5aa2}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">auto AlignVectors::getMask (<a href="/web-llvm/docs/api/classes/llvm/value">Value</a> * Val)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 309 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/hexagon/hexagonvectorcombine-cpp">HexagonVectorCombine.cpp</a>.</p>

</div>
</div>

### getPassThrough() {#aa95749066f9fb0c77863d6ad7afa3980}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">auto AlignVectors::getPassThrough (<a href="/web-llvm/docs/api/classes/llvm/value">Value</a> * Val)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 310 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/hexagon/hexagonvectorcombine-cpp">HexagonVectorCombine.cpp</a>.</p>

</div>
</div>

### getPayload() {#a88aa1296a7b6936875f8b36070cb7dc2}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">auto AlignVectors::getPayload (<a href="/web-llvm/docs/api/classes/llvm/value">Value</a> * Val)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 308 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/hexagon/hexagonvectorcombine-cpp">HexagonVectorCombine.cpp</a>.</p>

</div>
</div>

### getUpwardDeps() {#a92e73a5c61e9e6aa1ec394e69eed9ac5}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">auto AlignVectors::getUpwardDeps (<a href="/web-llvm/docs/api/classes/llvm/instruction">Instruction</a> * In, <a href="/web-llvm/docs/api/classes/llvm/instruction">Instruction</a> * Base)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 340 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/hexagon/hexagonvectorcombine-cpp">HexagonVectorCombine.cpp</a>.</p>

</div>
</div>

### isHvx() {#ab73bbd5379cbdbe02734483e7c0a75e2}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">auto AlignVectors::isHvx (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> AddrInfo &amp; AI)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 304 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/hexagon/hexagonvectorcombine-cpp">HexagonVectorCombine.cpp</a>.</p>

</div>
</div>

### isSectorTy() {#a29639e792be8613a455e17f37c0fdaca}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">auto AlignVectors::isSectorTy (<a href="/web-llvm/docs/api/classes/llvm/type">Type</a> * Ty)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 306 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/hexagon/hexagonvectorcombine-cpp">HexagonVectorCombine.cpp</a>.</p>

</div>
</div>

### makeTestIfUnaligned() {#a40bc3e29ca85451da5f83598a0ab966a}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">auto AlignVectors::makeTestIfUnaligned (<a href="/web-llvm/docs/api/classes/llvm/irbuilderbase">IRBuilderBase</a> &amp; Builder, <a href="/web-llvm/docs/api/classes/llvm/value">Value</a> * AlignVal, int Alignment)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 354 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/hexagon/hexagonvectorcombine-cpp">HexagonVectorCombine.cpp</a>.</p>

</div>
</div>

### moveTogether() {#ab49a8d46898fb4a2ad6491636f3c421e}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">auto AlignVectors::moveTogether (MoveGroup &amp; Move)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 344 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/hexagon/hexagonvectorcombine-cpp">HexagonVectorCombine.cpp</a>.</p>

</div>
</div>

### realignGroup() {#ad3f154c94ca78d2e16deb266c56a4da5}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">auto AlignVectors::realignGroup (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> MoveGroup &amp; Move)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 352 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/hexagon/hexagonvectorcombine-cpp">HexagonVectorCombine.cpp</a>.</p>

</div>
</div>

### realignLoadGroup() {#ab307f772aabfb93fa78f9b417c56c53a}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">auto AlignVectors::realignLoadGroup (<a href="/web-llvm/docs/api/classes/llvm/irbuilderbase">IRBuilderBase</a> &amp; Builder, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> ByteSpan &amp; VSpan, int ScLen, <a href="/web-llvm/docs/api/classes/llvm/value">Value</a> * AlignVal, <a href="/web-llvm/docs/api/classes/llvm/value">Value</a> * AlignAddr)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 348 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/hexagon/hexagonvectorcombine-cpp">HexagonVectorCombine.cpp</a>.</p>

</div>
</div>

### realignStoreGroup() {#a54625ad5c5136694cf0dd031097fe10f}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">auto AlignVectors::realignStoreGroup (<a href="/web-llvm/docs/api/classes/llvm/irbuilderbase">IRBuilderBase</a> &amp; Builder, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> ByteSpan &amp; VSpan, int ScLen, <a href="/web-llvm/docs/api/classes/llvm/value">Value</a> * AlignVal, <a href="/web-llvm/docs/api/classes/llvm/value">Value</a> * AlignAddr)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 350 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/hexagon/hexagonvectorcombine-cpp">HexagonVectorCombine.cpp</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Private Member Attributes

### AddrGroups {#a7a342982bc0a5949e38ffe563e8d51f6}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">std::map&lt;Instruction *, AddrList&gt; anonymous{HexagonVectorCombine.cpp}::AlignVectors::AddrGroups</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 362 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/hexagon/hexagonvectorcombine-cpp">HexagonVectorCombine.cpp</a>.</p>

</div>
</div>

### HVC {#a27673916bc359d404097367bd4d6c99e}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">const HexagonVectorCombine&amp; anonymous{HexagonVectorCombine.cpp}::AlignVectors::HVC</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 363 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/hexagon/hexagonvectorcombine-cpp">HexagonVectorCombine.cpp</a>.</p>

</div>
</div>

</div>

<hr/>

The documentation for this class was generated from the following file:

<ul>
<li><a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/hexagon/hexagonvectorcombine-cpp">HexagonVectorCombine.cpp</a></li>
</ul>

<hr/>

<p class="doxyGeneratedBy">Generated via <a href="https://github.com/xpack/doxygen2docusaurus">doxygen2docusaurus</a> by <a href="https://www.doxygen.nl">Doxygen</a> 1.15.0.</p>

</div>
