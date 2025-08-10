---

# DO NOT EDIT!
# Automatically generated via doxygen2docusaurus by Doxygen.

slug: /api/classes/llvm/constantdatasequential
custom_edit_url: null
toc_max_heading_level: 4
keywords:
  - doxygen
  - reference
  - class

---

<div class="doxyPage">

# `ConstantDataSequential` Class

<p><a href="/web-llvm/docs/api/classes/llvm/constantdatasequential">ConstantDataSequential</a> - A vector or array constant whose element type is a simple 1/2/4/8-byte integer or half/bfloat/float/double, and whose elements are just simple data values (i.e. <a href="#details">More...</a></p>

## Declaration

<div class="doxyDeclaration">
class llvm::ConstantDataSequential { ... }
</div>

## Included Headers

<div class="doxyIncludesList">#include "<a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/ir/constants-h">llvm/IR/Constants.h</a>"
</div>

## Base class

<table class="doxyMembersIndex">

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">class</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/constantdata">ConstantData</a></td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Base class for constants with no operands. <a href="/web-llvm/docs/api/classes/llvm/constantdata/#details">More...</a></p>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/constantdataarray">ConstantDataArray</a></td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>An array constant whose element type is a simple 1/2/4/8-byte integer or float/double, and whose elements are just simple data values (i.e. <a href="/web-llvm/docs/api/classes/llvm/constantdataarray/#details">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">class</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/constantdatavector">ConstantDataVector</a></td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>A vector constant whose element type is a simple 1/2/4/8-byte integer or float/double, and whose elements are just simple data values (i.e. <a href="/web-llvm/docs/api/classes/llvm/constantdatavector/#details">More...</a></p>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#aa81f87de855d80e4275071841a7e0c83">LLVMContextImpl</a></td>
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

## Public Constructors Index

<table class="doxyMembersIndex">

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a6d0c9d2ed31e338992eeade2fbdc2af1">ConstantDataSequential</a> (const ConstantDataSequential &amp;)=delete</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#affe367e75e60cf8dfdb8f501d15eff91">ConstantDataSequential</a> (Type *ty, ValueTy VT, const char *Data)</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">uint64_t</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a9409db5c707242fc05b7b2abeba38506">getElementAsInteger</a> (unsigned i) const</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>If this is a sequential container of integers (of any size), return the specified element in the low bits of a uint64_t. <a href="#a9409db5c707242fc05b7b2abeba38506">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/apint">APInt</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a078cf198dde98fad3e6de2c02a0aef47">getElementAsAPInt</a> (unsigned i) const</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>If this is a sequential container of integers (of any size), return the specified element as an <a href="/web-llvm/docs/api/classes/llvm/apint">APInt</a>. <a href="#a078cf198dde98fad3e6de2c02a0aef47">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/apfloat">APFloat</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#afb55f797ff051b3fc29a0cf5f7465f12">getElementAsAPFloat</a> (unsigned i) const</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>If this is a sequential container of floating point type, return the specified element as an <a href="/web-llvm/docs/api/classes/llvm/apfloat">APFloat</a>. <a href="#afb55f797ff051b3fc29a0cf5f7465f12">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">float</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a74d6406a9173092c1d8042fd3d741d16">getElementAsFloat</a> (unsigned i) const</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>If this is an sequential container of floats, return the specified element as a float. <a href="#a74d6406a9173092c1d8042fd3d741d16">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">double</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a22122dfa4eb5cb8169bcaf58e2137a91">getElementAsDouble</a> (unsigned i) const</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>If this is an sequential container of doubles, return the specified element as a double. <a href="#a22122dfa4eb5cb8169bcaf58e2137a91">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/constant">Constant</a> *</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ab1cf9198def27dfd719c425b1f9c5f50">getElementAsConstant</a> (unsigned i) const</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Return a <a href="/web-llvm/docs/api/classes/llvm/constant">Constant</a> for a specified index's element. <a href="#ab1cf9198def27dfd719c425b1f9c5f50">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/type">Type</a> *</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ac0d41ea0afa3131e1a0838e07c111c0e">getElementType</a> () const</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Return the element type of the array/vector. <a href="#ac0d41ea0afa3131e1a0838e07c111c0e">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">unsigned</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#aa1bb0403aefc1f09b73e96d9243d3673">getNumElements</a> () const</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Return the number of elements in the array or vector. <a href="#aa1bb0403aefc1f09b73e96d9243d3673">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">uint64_t</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a5f05216ba8b34865b434e7fc8c96d9d4">getElementByteSize</a> () const</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Return the size (in bytes) of each element in the array/vector. <a href="#a5f05216ba8b34865b434e7fc8c96d9d4">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">bool</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a7d6c29a3f2cf33fdabaadeba33e47d78">isString</a> (unsigned CharSize=8) const</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>This method returns true if this is an array of <span class="doxyComputerOutput">CharSize</span> integers. <a href="#a7d6c29a3f2cf33fdabaadeba33e47d78">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">bool</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#aecff3ad6cfa0e4abfd4fc9484d973e7d">isCString</a> () const</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>This method returns true if the array "isString", ends with a null byte, and does not contains any other null bytes. <a href="#aecff3ad6cfa0e4abfd4fc9484d973e7d">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/stringref">StringRef</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a3486cc0d00c60d90076132d7a1829326">getAsString</a> () const</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>If this array is <a href="#a7d6c29a3f2cf33fdabaadeba33e47d78">isString()</a>, then this method returns the array as a <a href="/web-llvm/docs/api/classes/llvm/stringref">StringRef</a>. <a href="#a3486cc0d00c60d90076132d7a1829326">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/stringref">StringRef</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a83be107e09b5576cfb2fc5f8cebe56f2">getAsCString</a> () const</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>If this array is <a href="#aecff3ad6cfa0e4abfd4fc9484d973e7d">isCString()</a>, then this method returns the array (without the trailing null byte) as a <a href="/web-llvm/docs/api/classes/llvm/stringref">StringRef</a>. <a href="#a83be107e09b5576cfb2fc5f8cebe56f2">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/stringref">StringRef</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#afd2c2acb776ce93380256b041323cc6d">getRawDataValues</a> () const</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Return the raw, underlying, bytes of this data. <a href="#afd2c2acb776ce93380256b041323cc6d">More...</a></p>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#aae40572c6749c8168c56bb1ebd60af9f">destroyConstantImpl</a> ()</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> char *</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a3a082bdd92ef8a56846cc34077d9b755">getElementPointer</a> (unsigned Elt) const</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Return the start of the specified element. <a href="#a3a082bdd92ef8a56846cc34077d9b755">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

</table>

## Private Member Attributes Index

<table class="doxyMembersIndex">

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> char *</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#aef89efccf0640fc17cdf2625d0413760">DataElements</a></td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>A pointer to the bytes underlying this constant (which is owned by the uniquing <a href="/web-llvm/docs/api/classes/llvm/stringmap">StringMap</a>). <a href="#aef89efccf0640fc17cdf2625d0413760">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">std::unique_ptr&lt; <a href="/web-llvm/docs/api/classes/llvm/constantdatasequential">ConstantDataSequential</a> &gt;</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a5ef86d3a5944e2b31478478a54640ba8">Next</a></td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>This forms a link list of <a href="/web-llvm/docs/api/classes/llvm/constantdatasequential">ConstantDataSequential</a> nodes that have the same value but different type. <a href="#a5ef86d3a5944e2b31478478a54640ba8">More...</a></p>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#afdcd0a1d482f4048baba27f0bc051411">isElementTypeCompatible</a> (Type *Ty)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Return true if a <a href="/web-llvm/docs/api/classes/llvm/constantdatasequential">ConstantDataSequential</a> can be formed with a vector or array of the specified element type. <a href="#afdcd0a1d482f4048baba27f0bc051411">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">static bool</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#afc28639343332261bcbe6250b25b0309">classof</a> (const Value *V)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Methods for support type inquiry through isa, cast, and dyn_cast: <a href="#afc28639343332261bcbe6250b25b0309">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

</table>

## Protected Static Functions Index

<table class="doxyMembersIndex">

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">static <a href="/web-llvm/docs/api/classes/llvm/constant">Constant</a> *</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a9a20b607f6fdb3dd6689a3daed25f3cb">getImpl</a> (StringRef Bytes, Type *Ty)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>This is the underlying implementation of all of the ConstantDataSequential::get methods. <a href="#a9a20b607f6fdb3dd6689a3daed25f3cb">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

</table>

## Description {#details}

<p><a href="/web-llvm/docs/api/classes/llvm/constantdatasequential">ConstantDataSequential</a> - A vector or array constant whose element type is a simple 1/2/4/8-byte integer or half/bfloat/float/double, and whose elements are just simple data values (i.e.</p>


<p>ConstantInt/ConstantFP). This <a href="/web-llvm/docs/api/classes/llvm/constant">Constant</a> node has no operands because it stores all of the elements of the constant as densely packed data, instead of as Value*'s.</p>


<p>This is the common base class of <a href="/web-llvm/docs/api/classes/llvm/constantdataarray">ConstantDataArray</a> and <a href="/web-llvm/docs/api/classes/llvm/constantdatavector">ConstantDataVector</a>.</p>


<p>Definition at line 587 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/ir/constants-h">Constants.h</a>.</p>


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


<p>Definition at line 589 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/ir/constants-h">Constants.h</a>.</p>


<p>Reference <a href="#a5bd16c2fbe755cda66b18d56761038ea">Constant</a>.</p>


<p>Referenced by <a href="#a5bd16c2fbe755cda66b18d56761038ea">Constant</a>, <a href="#a6d0c9d2ed31e338992eeade2fbdc2af1">ConstantDataSequential</a>, <a href="/web-llvm/docs/api/classes/llvm/constantdatavector/#a954ef382b0bde05a9833572852ec9c47">llvm::ConstantDataVector::ConstantDataVector</a>, <a href="/web-llvm/docs/api/classes/llvm/constantdataarray/#a4a1000e5803e731e9dcc572042a98a0b">llvm::ConstantDataArray::get</a>, <a href="/web-llvm/docs/api/classes/llvm/constantdataarray/#a7a7c0ddf7f8e222e0fabf305430c7c0b">llvm::ConstantDataArray::get</a>, <a href="/web-llvm/docs/api/classes/llvm/constantdatavector/#a79459acee890c44fac5c279584480b08">llvm::ConstantDataVector::get</a>, <a href="/web-llvm/docs/api/classes/llvm/constantdatavector/#a2b15feb32345af4916487fa3fa9d6227">llvm::ConstantDataVector::get</a>, <a href="/web-llvm/docs/api/classes/llvm/constantdatavector/#a0ad360dbce483cc0903211b623b9debd">llvm::ConstantDataVector::get</a>, <a href="/web-llvm/docs/api/classes/llvm/constantdatavector/#ae5bc9cac664aeb67c181f9add7309cfa">llvm::ConstantDataVector::get</a>, <a href="/web-llvm/docs/api/classes/llvm/constantdatavector/#a8ee97870547b76f8387091128a00e90c">llvm::ConstantDataVector::get</a>, <a href="/web-llvm/docs/api/classes/llvm/constantdatavector/#ab8b693ee2fbb4c4173fa2725c110021b">llvm::ConstantDataVector::get</a>, <a href="#ab1cf9198def27dfd719c425b1f9c5f50">getElementAsConstant</a>, <a href="/web-llvm/docs/api/classes/llvm/constantdataarray/#a6eec77c77aa76611db6766a3f205570c">llvm::ConstantDataArray::getFP</a>, <a href="/web-llvm/docs/api/classes/llvm/constantdataarray/#a54e552ee615150b4efe5195ac45d4389">llvm::ConstantDataArray::getFP</a>, <a href="/web-llvm/docs/api/classes/llvm/constantdataarray/#a3d4228cf6f5c478449deca90c6ce2255">llvm::ConstantDataArray::getFP</a>, <a href="/web-llvm/docs/api/classes/llvm/constantdatavector/#acc193957138fece590fe07417912f018">llvm::ConstantDataVector::getFP</a>, <a href="/web-llvm/docs/api/classes/llvm/constantdatavector/#aeecde9516e68842cb97c340bb693a7a9">llvm::ConstantDataVector::getFP</a>, <a href="/web-llvm/docs/api/classes/llvm/constantdatavector/#aa736794cd9a0acefdb428c5ed892a66f">llvm::ConstantDataVector::getFP</a>, <a href="#a9a20b607f6fdb3dd6689a3daed25f3cb">getImpl</a>, <a href="/web-llvm/docs/api/classes/llvm/constantdataarray/#ad86e02b5bee8ad12233bbf1719d1312f">llvm::ConstantDataArray::getRaw</a>, <a href="/web-llvm/docs/api/classes/llvm/constantdatavector/#a074d013c7183283d9aaa8d7127057242">llvm::ConstantDataVector::getRaw</a>, <a href="/web-llvm/docs/api/classes/llvm/constantdatavector/#a44124e702dc442346bd6202bb03e593b">llvm::ConstantDataVector::getSplat</a>, <a href="/web-llvm/docs/api/classes/llvm/constantdatavector/#a0b66acacd6d23b2878904cf11f5d6ece">llvm::ConstantDataVector::getSplatValue</a> and <a href="/web-llvm/docs/api/classes/llvm/constantdataarray/#a3edef3fa47c611d3d10606591213e57b">llvm::ConstantDataArray::getString</a>.</p>

</div>
</div>

### LLVMContextImpl {#aa81f87de855d80e4275071841a7e0c83}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">friend class <a href="/web-llvm/docs/api/classes/llvm/llvmcontextimpl">LLVMContextImpl</a></td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">


<p>Definition at line 588 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/ir/constants-h">Constants.h</a>.</p>


<p>Reference <a href="#aa81f87de855d80e4275071841a7e0c83">LLVMContextImpl</a>.</p>


<p>Referenced by <a href="#aa81f87de855d80e4275071841a7e0c83">LLVMContextImpl</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Public Constructors

### ConstantDataSequential() {#a6d0c9d2ed31e338992eeade2fbdc2af1}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">llvm::ConstantDataSequential::ConstantDataSequential (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/constantdatasequential">ConstantDataSequential</a> &amp;)</td>
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



<p>Definition at line 610 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/ir/constants-h">Constants.h</a>.</p>


<p>References <a href="#a5bd16c2fbe755cda66b18d56761038ea">Constant</a> and <a href="#affe367e75e60cf8dfdb8f501d15eff91">ConstantDataSequential</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Protected Constructors

### ConstantDataSequential() {#affe367e75e60cf8dfdb8f501d15eff91}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">llvm::ConstantDataSequential::ConstantDataSequential (<a href="/web-llvm/docs/api/classes/llvm/type">Type</a> * ty, <a href="/web-llvm/docs/api/classes/llvm/value/#af6d11b38374c4f9e6ba3a6407da2dee0">ValueTy</a> VT, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> char * Data)</td>
</tr>
</table>
</td>
<td class="doxyMemberLabelsRight">
<span class="doxyMemberLabels">
<span class="doxyMemberLabel inline">inline</span>
<span class="doxyMemberLabel explicit">explicit</span>
<span class="doxyMemberLabel protected">protected</span>
</span>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 604 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/ir/constants-h">Constants.h</a>.</p>


<p>References <a href="/web-llvm/docs/api/classes/llvm/constantdata/#ade3ec5a4a86ffd069698509c87b6a604">llvm::ConstantData::ConstantData</a> and <a href="/web-llvm/docs/api/namespaces/llvm/#aa20539e89704d20b98b97e9c3feac934">llvm::Data</a>.</p>


<p>Referenced by <a href="#a6d0c9d2ed31e338992eeade2fbdc2af1">ConstantDataSequential</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Public Member Functions

### getAsCString() {#a83be107e09b5576cfb2fc5f8cebe56f2}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">StringRef llvm::ConstantDataSequential::getAsCString ()</td>
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

<p>If this array is <a href="#aecff3ad6cfa0e4abfd4fc9484d973e7d">isCString()</a>, then this method returns the array (without the trailing null byte) as a <a href="/web-llvm/docs/api/classes/llvm/stringref">StringRef</a>.</p>


<p>Otherwise, it asserts out.</p>


<p>Definition at line 669 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/ir/constants-h">Constants.h</a>.</p>


<p>References <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/silowercontrolflow-cpp/#a4868c5d81c5ccc98c47aeab6244346a0">assert</a>, <a href="#a3486cc0d00c60d90076132d7a1829326">getAsString</a> and <a href="#aecff3ad6cfa0e4abfd4fc9484d973e7d">isCString</a>.</p>

</div>
</div>

### getAsString() {#a3486cc0d00c60d90076132d7a1829326}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">StringRef llvm::ConstantDataSequential::getAsString ()</td>
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

<p>If this array is <a href="#a7d6c29a3f2cf33fdabaadeba33e47d78">isString()</a>, then this method returns the array as a <a href="/web-llvm/docs/api/classes/llvm/stringref">StringRef</a>.</p>


<p>Otherwise, it asserts out.</p>


<p>Definition at line 662 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/ir/constants-h">Constants.h</a>.</p>


<p>References <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/silowercontrolflow-cpp/#a4868c5d81c5ccc98c47aeab6244346a0">assert</a>, <a href="#afd2c2acb776ce93380256b041323cc6d">getRawDataValues</a> and <a href="#a7d6c29a3f2cf33fdabaadeba33e47d78">isString</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/files/lib/lib/codegen/lib/codegen/asmprinter/asmprinter-cpp/#a9fcb3f76aba8a8c062f9db30393cabfc">emitGlobalConstantDataSequential</a>, <a href="#a83be107e09b5576cfb2fc5f8cebe56f2">getAsCString</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a2bcd261c0da622d37e1c5aeb02496e12">llvm::getConstantStringInfo</a> and <a href="#aecff3ad6cfa0e4abfd4fc9484d973e7d">isCString</a>.</p>

</div>
</div>

### getElementAsAPFloat() {#afb55f797ff051b3fc29a0cf5f7465f12}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">APFloat ConstantDataSequential::getElementAsAPFloat (unsigned i)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>If this is a sequential container of floating point type, return the specified element as an <a href="/web-llvm/docs/api/classes/llvm/apfloat">APFloat</a>.</p>

<p>Declaration at line 628 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/ir/constants-h">Constants.h</a>, definition at line 3163 of file <a href="/web-llvm/docs/api/files/lib/lib/ir/constants-cpp">Constants.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/structs/llvm/apfloatbase/#ab46ff1a80ee89c9e22ca17c179a89ab1">llvm::APFloatBase::BFloat</a>, <a href="/web-llvm/docs/api/classes/llvm/type/#a5e9e1c0dd93557be1b4ad72860f3cbdaaa889d8e26c8078095629a42d1f930fa7">llvm::Type::BFloatTyID</a>, <a href="/web-llvm/docs/api/classes/llvm/type/#a5e9e1c0dd93557be1b4ad72860f3cbdaabc549945f13bb5d5f5b80c550d2b92f5">llvm::Type::DoubleTyID</a>, <a href="/web-llvm/docs/api/classes/llvm/type/#a5e9e1c0dd93557be1b4ad72860f3cbdaa6a5dd38c5c337ac6ce6d5847b1ca7f15">llvm::Type::FloatTyID</a>, <a href="#ac0d41ea0afa3131e1a0838e07c111c0e">getElementType</a>, <a href="/web-llvm/docs/api/files/lib/lib/executionengine/lib/executionengine/interpreter/externalfunctions-cpp/#a62734f5491c71583869b1da8d274dc45">getTypeID</a>, <a href="/web-llvm/docs/api/classes/llvm/type/#a5e9e1c0dd93557be1b4ad72860f3cbdaa301c3a4cc2bfd399628cfd473f383ff9">llvm::Type::HalfTyID</a>, <a href="/web-llvm/docs/api/structs/llvm/apfloatbase/#a6ba7c3d54a5a714f7a27861ee114cce3">llvm::APFloatBase::IEEEdouble</a>, <a href="/web-llvm/docs/api/structs/llvm/apfloatbase/#a86415bb448a78ef1fed893f9eb0f5d06">llvm::APFloatBase::IEEEhalf</a>, <a href="/web-llvm/docs/api/structs/llvm/apfloatbase/#a0c5765e9acba977f6e462c2917276d8f">llvm::APFloatBase::IEEEsingle</a> and <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/support/errorhandling-h/#ace243f5c25697a1107cce46626b3dc94">llvm_unreachable</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/files/lib/lib/codegen/lib/codegen/asmprinter/asmprinter-cpp/#a9fcb3f76aba8a8c062f9db30393cabfc">emitGlobalConstantDataSequential</a> and <a href="#ab1cf9198def27dfd719c425b1f9c5f50">getElementAsConstant</a>.</p>

</div>
</div>

### getElementAsAPInt() {#a078cf198dde98fad3e6de2c02a0aef47}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">APInt ConstantDataSequential::getElementAsAPInt (unsigned i)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>If this is a sequential container of integers (of any size), return the specified element as an <a href="/web-llvm/docs/api/classes/llvm/apint">APInt</a>.</p>

<p>Declaration at line 624 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/ir/constants-h">Constants.h</a>, definition at line 3135 of file <a href="/web-llvm/docs/api/files/lib/lib/ir/constants-cpp">Constants.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/silowercontrolflow-cpp/#a4868c5d81c5ccc98c47aeab6244346a0">assert</a>, <a href="#ac0d41ea0afa3131e1a0838e07c111c0e">getElementType</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a92ca992e52dddc420f4b069cae06dfbe">llvm::isa</a> and <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/support/errorhandling-h/#ace243f5c25697a1107cce46626b3dc94">llvm_unreachable</a>.</p>

</div>
</div>

### getElementAsConstant() {#ab1cf9198def27dfd719c425b1f9c5f50}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">Constant * ConstantDataSequential::getElementAsConstant (unsigned i)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Return a <a href="/web-llvm/docs/api/classes/llvm/constant">Constant</a> for a specified index's element.</p>


<p>Note that this has to compute a new constant to return, so it isn't as efficient as getElementAsInteger/Float/Double.</p>


<p>Declaration at line 641 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/ir/constants-h">Constants.h</a>, definition at line 3200 of file <a href="/web-llvm/docs/api/files/lib/lib/ir/constants-cpp">Constants.cpp</a>.</p>


<p>References <a href="#a5bd16c2fbe755cda66b18d56761038ea">Constant</a>, <a href="/web-llvm/docs/api/classes/llvm/value/#ab3fc0225d8aaf8434026c3573f961f2c">llvm::Value::getContext</a>, <a href="#afb55f797ff051b3fc29a0cf5f7465f12">getElementAsAPFloat</a>, <a href="#a9409db5c707242fc05b7b2abeba38506">getElementAsInteger</a> and <a href="#ac0d41ea0afa3131e1a0838e07c111c0e">getElementType</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/classes/llvm/constantdatavector/#a0b66acacd6d23b2878904cf11f5d6ece">llvm::ConstantDataVector::getSplatValue</a>.</p>

</div>
</div>

### getElementAsDouble() {#a22122dfa4eb5cb8169bcaf58e2137a91}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">double ConstantDataSequential::getElementAsDouble (unsigned i)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>If this is an sequential container of doubles, return the specified element as a double.</p>

<p>Declaration at line 636 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/ir/constants-h">Constants.h</a>, definition at line 3194 of file <a href="/web-llvm/docs/api/files/lib/lib/ir/constants-cpp">Constants.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/silowercontrolflow-cpp/#a4868c5d81c5ccc98c47aeab6244346a0">assert</a> and <a href="#ac0d41ea0afa3131e1a0838e07c111c0e">getElementType</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/classes/llvm/executionengine/#a0a724dad58a66f883d1b88115237ae00">llvm::ExecutionEngine::getConstantValue</a>.</p>

</div>
</div>

### getElementAsFloat() {#a74d6406a9173092c1d8042fd3d741d16}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">float ConstantDataSequential::getElementAsFloat (unsigned i)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>If this is an sequential container of floats, return the specified element as a float.</p>

<p>Declaration at line 632 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/ir/constants-h">Constants.h</a>, definition at line 3188 of file <a href="/web-llvm/docs/api/files/lib/lib/ir/constants-cpp">Constants.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/silowercontrolflow-cpp/#a4868c5d81c5ccc98c47aeab6244346a0">assert</a> and <a href="#ac0d41ea0afa3131e1a0838e07c111c0e">getElementType</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/classes/llvm/executionengine/#a0a724dad58a66f883d1b88115237ae00">llvm::ExecutionEngine::getConstantValue</a>.</p>

</div>
</div>

### getElementAsInteger() {#a9409db5c707242fc05b7b2abeba38506}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">uint64_t ConstantDataSequential::getElementAsInteger (unsigned i)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>If this is a sequential container of integers (of any size), return the specified element in the low bits of a uint64_t.</p>

<p>Declaration at line 620 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/ir/constants-h">Constants.h</a>, definition at line 3115 of file <a href="/web-llvm/docs/api/files/lib/lib/ir/constants-cpp">Constants.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/silowercontrolflow-cpp/#a4868c5d81c5ccc98c47aeab6244346a0">assert</a>, <a href="#ac0d41ea0afa3131e1a0838e07c111c0e">getElementType</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a92ca992e52dddc420f4b069cae06dfbe">llvm::isa</a> and <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/support/errorhandling-h/#ace243f5c25697a1107cce46626b3dc94">llvm_unreachable</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/files/lib/lib/codegen/lib/codegen/asmprinter/asmprinter-cpp/#a9fcb3f76aba8a8c062f9db30393cabfc">emitGlobalConstantDataSequential</a>, <a href="/web-llvm/docs/api/classes/llvm/executionengine/#a0a724dad58a66f883d1b88115237ae00">llvm::ExecutionEngine::getConstantValue</a>, <a href="#ab1cf9198def27dfd719c425b1f9c5f50">getElementAsConstant</a>, <a href="/web-llvm/docs/api/files/lib/lib/analysis/valuetracking-cpp/#a5abc0c0977f5f87b0e30e784a3d487bc">GetStringLengthH</a>, <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/aggressiveinstcombine/aggressiveinstcombine-cpp/#ac60e4a050606558fee92cecf8c6fc905">isCTTZTable</a> and <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/aggressiveinstcombine/aggressiveinstcombine-cpp/#a6594a7d514d3847ccbe52b66a49d8ee5">tryToRecognizeTableBasedCttz</a>.</p>

</div>
</div>

### getElementByteSize() {#a5f05216ba8b34865b434e7fc8c96d9d4}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">uint64_t ConstantDataSequential::getElementByteSize ()</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Return the size (in bytes) of each element in the array/vector.</p>


<p>The size of the elements is known to be a multiple of one byte.</p>


<p>Declaration at line 651 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/ir/constants-h">Constants.h</a>, definition at line 2865 of file <a href="/web-llvm/docs/api/files/lib/lib/ir/constants-cpp">Constants.cpp</a>.</p>


<p>References <a href="#ac0d41ea0afa3131e1a0838e07c111c0e">getElementType</a> and <a href="/web-llvm/docs/api/classes/llvm/type/#a833daf718a49c5cd637d8c9ddeaebe07">llvm::Type::getPrimitiveSizeInBits</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/files/lib/lib/codegen/lib/codegen/asmprinter/asmprinter-cpp/#a9fcb3f76aba8a8c062f9db30393cabfc">emitGlobalConstantDataSequential</a>, <a href="#afd2c2acb776ce93380256b041323cc6d">getRawDataValues</a>, <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/ipo/globalopt-cpp/#a4f18aa17f81c88c8fa89c76563a6d510">tryWidenGlobalArraysUsedByMemcpy</a> and <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/ipo/globalopt-cpp/#a960e756e8b2f056fbba7baa5bdcfb769">widenDestArray</a>.</p>

</div>
</div>

### getElementType() {#ac0d41ea0afa3131e1a0838e07c111c0e}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">Type * ConstantDataSequential::getElementType ()</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Return the element type of the array/vector.</p>

<p>Declaration at line 644 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/ir/constants-h">Constants.h</a>, definition at line 2832 of file <a href="/web-llvm/docs/api/files/lib/lib/ir/constants-cpp">Constants.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/namespaces/llvm/#ac4fc845f5ed92de63cd4474f128f5fc5">llvm::cast</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a22eeee01734061ac1b31ccd994c49eef">llvm::dyn_cast</a> and <a href="/web-llvm/docs/api/classes/llvm/value/#a0344a49526443edf90cc0aef3abd3337">llvm::Value::getType</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/files/lib/lib/codegen/lib/codegen/asmprinter/asmprinter-cpp/#a9fcb3f76aba8a8c062f9db30393cabfc">emitGlobalConstantDataSequential</a>, <a href="/web-llvm/docs/api/classes/llvm/executionengine/#a0a724dad58a66f883d1b88115237ae00">llvm::ExecutionEngine::getConstantValue</a>, <a href="#afb55f797ff051b3fc29a0cf5f7465f12">getElementAsAPFloat</a>, <a href="#a078cf198dde98fad3e6de2c02a0aef47">getElementAsAPInt</a>, <a href="#ab1cf9198def27dfd719c425b1f9c5f50">getElementAsConstant</a>, <a href="#a22122dfa4eb5cb8169bcaf58e2137a91">getElementAsDouble</a>, <a href="#a74d6406a9173092c1d8042fd3d741d16">getElementAsFloat</a>, <a href="#a9409db5c707242fc05b7b2abeba38506">getElementAsInteger</a>, <a href="#a5f05216ba8b34865b434e7fc8c96d9d4">getElementByteSize</a>, <a href="#a9a20b607f6fdb3dd6689a3daed25f3cb">getImpl</a> and <a href="#a7d6c29a3f2cf33fdabaadeba33e47d78">isString</a>.</p>

</div>
</div>

### getNumElements() {#aa1bb0403aefc1f09b73e96d9243d3673}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">unsigned ConstantDataSequential::getNumElements ()</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Return the number of elements in the array or vector.</p>

<p>Declaration at line 647 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/ir/constants-h">Constants.h</a>, definition at line 2858 of file <a href="/web-llvm/docs/api/files/lib/lib/ir/constants-cpp">Constants.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/namespaces/llvm/#ac4fc845f5ed92de63cd4474f128f5fc5">llvm::cast</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a22eeee01734061ac1b31ccd994c49eef">llvm::dyn_cast</a> and <a href="/web-llvm/docs/api/classes/llvm/value/#a0344a49526443edf90cc0aef3abd3337">llvm::Value::getType</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/files/lib/lib/codegen/lib/codegen/asmprinter/asmprinter-cpp/#a9fcb3f76aba8a8c062f9db30393cabfc">emitGlobalConstantDataSequential</a>, <a href="/web-llvm/docs/api/classes/llvm/executionengine/#a0a724dad58a66f883d1b88115237ae00">llvm::ExecutionEngine::getConstantValue</a>, <a href="#afd2c2acb776ce93380256b041323cc6d">getRawDataValues</a> and <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/aggressiveinstcombine/aggressiveinstcombine-cpp/#ac60e4a050606558fee92cecf8c6fc905">isCTTZTable</a>.</p>

</div>
</div>

### getRawDataValues() {#afd2c2acb776ce93380256b041323cc6d}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">StringRef ConstantDataSequential::getRawDataValues ()</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Return the raw, underlying, bytes of this data.</p>


<p>Note that this is an extremely tricky thing to work with, as it exposes the host endianness of the data elements.</p>


<p>Declaration at line 678 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/ir/constants-h">Constants.h</a>, definition at line 2838 of file <a href="/web-llvm/docs/api/files/lib/lib/ir/constants-cpp">Constants.cpp</a>.</p>


<p>References <a href="#a5f05216ba8b34865b434e7fc8c96d9d4">getElementByteSize</a> and <a href="#aa1bb0403aefc1f09b73e96d9243d3673">getNumElements</a>.</p>


<p>Referenced by <a href="#a3486cc0d00c60d90076132d7a1829326">getAsString</a> and <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/ipo/globalopt-cpp/#a2b81e19b3ddf7ec786c5105ba5470153">widenGlobalVariable</a>.</p>

</div>
</div>

### isCString() {#aecff3ad6cfa0e4abfd4fc9484d973e7d}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool ConstantDataSequential::isCString ()</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>This method returns true if the array "isString", ends with a null byte, and does not contains any other null bytes.</p>

<p>Declaration at line 658 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/ir/constants-h">Constants.h</a>, definition at line 3212 of file <a href="/web-llvm/docs/api/files/lib/lib/ir/constants-cpp">Constants.cpp</a>.</p>


<p>References <a href="#a3486cc0d00c60d90076132d7a1829326">getAsString</a> and <a href="#a7d6c29a3f2cf33fdabaadeba33e47d78">isString</a>.</p>


<p>Referenced by <a href="#a83be107e09b5576cfb2fc5f8cebe56f2">getAsCString</a>.</p>

</div>
</div>

### isString() {#a7d6c29a3f2cf33fdabaadeba33e47d78}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool ConstantDataSequential::isString (unsigned CharSize=8)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>This method returns true if this is an array of <span class="doxyComputerOutput">CharSize</span> integers.</p>

<p>Declaration at line 654 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/ir/constants-h">Constants.h</a>, definition at line 3208 of file <a href="/web-llvm/docs/api/files/lib/lib/ir/constants-cpp">Constants.cpp</a>.</p>


<p>References <a href="#ac0d41ea0afa3131e1a0838e07c111c0e">getElementType</a>, <a href="/web-llvm/docs/api/classes/llvm/value/#a0344a49526443edf90cc0aef3abd3337">llvm::Value::getType</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a92ca992e52dddc420f4b069cae06dfbe">llvm::isa</a> and <a href="/web-llvm/docs/api/classes/llvm/type/#ac6d28a9b11139182134a9618028a0d07">llvm::Type::isIntegerTy</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/files/lib/lib/codegen/lib/codegen/asmprinter/asmprinter-cpp/#a9fcb3f76aba8a8c062f9db30393cabfc">emitGlobalConstantDataSequential</a>, <a href="#a3486cc0d00c60d90076132d7a1829326">getAsString</a> and <a href="#aecff3ad6cfa0e4abfd4fc9484d973e7d">isCString</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Private Member Functions

### destroyConstantImpl() {#aae40572c6749c8168c56bb1ebd60af9f}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void ConstantDataSequential::destroyConstantImpl ()</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Declaration at line 601 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/ir/constants-h">Constants.h</a>, definition at line 2929 of file <a href="/web-llvm/docs/api/files/lib/lib/ir/constants-cpp">Constants.cpp</a>.</p>

</div>
</div>

### getElementPointer() {#a3a082bdd92ef8a56846cc34077d9b755}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">const char * ConstantDataSequential::getElementPointer (unsigned Elt)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Return the start of the specified element.</p>

<p>Declaration at line 687 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/ir/constants-h">Constants.h</a>, definition at line 2870 of file <a href="/web-llvm/docs/api/files/lib/lib/ir/constants-cpp">Constants.cpp</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Private Member Attributes

### DataElements {#aef89efccf0640fc17cdf2625d0413760}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">const char* llvm::ConstantDataSequential::DataElements</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>A pointer to the bytes underlying this constant (which is owned by the uniquing <a href="/web-llvm/docs/api/classes/llvm/stringmap">StringMap</a>).</p>

<p>Definition at line 593 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/ir/constants-h">Constants.h</a>.</p>

</div>
</div>

### Next {#a5ef86d3a5944e2b31478478a54640ba8}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">std::unique_ptr&lt;ConstantDataSequential&gt; llvm::ConstantDataSequential::Next</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>This forms a link list of <a href="/web-llvm/docs/api/classes/llvm/constantdatasequential">ConstantDataSequential</a> nodes that have the same value but different type.</p>


<p>For example, 0,0,0,1 could be a 4 element array of i8, or a 1-element array of i32. They'll both end up in the same <a href="/web-llvm/docs/api/classes/llvm/stringmap">StringMap</a> bucket, linked up.</p>


<p>Definition at line 599 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/ir/constants-h">Constants.h</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Public Static Functions

### classof() {#afc28639343332261bcbe6250b25b0309}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool llvm::ConstantDataSequential::classof (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/value">Value</a> * V)</td>
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

<p>Definition at line 681 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/ir/constants-h">Constants.h</a>.</p>

</div>
</div>

### isElementTypeCompatible() {#afdcd0a1d482f4048baba27f0bc051411}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool ConstantDataSequential::isElementTypeCompatible (<a href="/web-llvm/docs/api/classes/llvm/type">Type</a> * Ty)</td>
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

<p>Return true if a <a href="/web-llvm/docs/api/classes/llvm/constantdatasequential">ConstantDataSequential</a> can be formed with a vector or array of the specified element type.</p>


<p><a href="/web-llvm/docs/api/classes/llvm/constantdataarray">ConstantDataArray</a> only works with normal float and int types that are stored densely in memory, not with things like i42 or x86_f80.</p>


<p>Declaration at line 616 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/ir/constants-h">Constants.h</a>, definition at line 2842 of file <a href="/web-llvm/docs/api/files/lib/lib/ir/constants-cpp">Constants.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/namespaces/llvm/#a22eeee01734061ac1b31ccd994c49eef">llvm::dyn_cast</a> and <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/arm/armsubtarget-cpp/#a6f57985fa144303082fa7517a52e6db9">IT</a>.</p>


<p>Referenced by <a href="#a9a20b607f6fdb3dd6689a3daed25f3cb">getImpl</a>, <a href="/web-llvm/docs/api/classes/llvm/constantdatavector/#a44124e702dc442346bd6202bb03e593b">llvm::ConstantDataVector::getSplat</a> and <a href="/web-llvm/docs/api/classes/llvm/constantvector/#aa3b241b35b0039b413faf1ef4e873eb7">llvm::ConstantVector::getSplat</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Protected Static Functions

### getImpl() {#a9a20b607f6fdb3dd6689a3daed25f3cb}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">Constant * ConstantDataSequential::getImpl (<a href="/web-llvm/docs/api/classes/llvm/stringref">StringRef</a> Elements, <a href="/web-llvm/docs/api/classes/llvm/type">Type</a> * Ty)</td>
</tr>
</table>
</td>
<td class="doxyMemberLabelsRight">
<span class="doxyMemberLabels">
<span class="doxyMemberLabel protected">protected</span>
<span class="doxyMemberLabel static">static</span>
</span>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>This is the underlying implementation of all of the ConstantDataSequential::get methods.</p>


<p>They all thunk down to here, providing the correct element type. We take the bytes in as a <a href="/web-llvm/docs/api/classes/llvm/stringref">StringRef</a> because we <em>want</em> an underlying "char*" to avoid TBAA type punning violations.</p>


<p>Declaration at line 607 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/ir/constants-h">Constants.h</a>, definition at line 2888 of file <a href="/web-llvm/docs/api/files/lib/lib/ir/constants-cpp">Constants.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/silowercontrolflow-cpp/#a4868c5d81c5ccc98c47aeab6244346a0">assert</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#ac4fc845f5ed92de63cd4474f128f5fc5">llvm::cast</a>, <a href="#a5bd16c2fbe755cda66b18d56761038ea">Constant</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a22eeee01734061ac1b31ccd994c49eef">llvm::dyn_cast</a>, <a href="/web-llvm/docs/api/classes/llvm/constantaggregatezero/#abfa1cf8b4348407b167f93bc7c01055f">llvm::ConstantAggregateZero::get</a>, <a href="#ac0d41ea0afa3131e1a0838e07c111c0e">getElementType</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a92ca992e52dddc420f4b069cae06dfbe">llvm::isa</a>, <a href="/web-llvm/docs/api/files/lib/lib/ir/constants-cpp/#a0c9144049d9cf2b48160a4416041f852">isAllZeros</a> and <a href="#afdcd0a1d482f4048baba27f0bc051411">isElementTypeCompatible</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/classes/llvm/constantdatavector/#a79459acee890c44fac5c279584480b08">llvm::ConstantDataVector::get</a>, <a href="/web-llvm/docs/api/classes/llvm/constantdatavector/#a2b15feb32345af4916487fa3fa9d6227">llvm::ConstantDataVector::get</a>, <a href="/web-llvm/docs/api/classes/llvm/constantdatavector/#a0ad360dbce483cc0903211b623b9debd">llvm::ConstantDataVector::get</a>, <a href="/web-llvm/docs/api/classes/llvm/constantdatavector/#ae5bc9cac664aeb67c181f9add7309cfa">llvm::ConstantDataVector::get</a>, <a href="/web-llvm/docs/api/classes/llvm/constantdatavector/#a8ee97870547b76f8387091128a00e90c">llvm::ConstantDataVector::get</a>, <a href="/web-llvm/docs/api/classes/llvm/constantdatavector/#ab8b693ee2fbb4c4173fa2725c110021b">llvm::ConstantDataVector::get</a>, <a href="/web-llvm/docs/api/classes/llvm/constantdataarray/#a6eec77c77aa76611db6766a3f205570c">llvm::ConstantDataArray::getFP</a>, <a href="/web-llvm/docs/api/classes/llvm/constantdataarray/#a54e552ee615150b4efe5195ac45d4389">llvm::ConstantDataArray::getFP</a>, <a href="/web-llvm/docs/api/classes/llvm/constantdataarray/#a3d4228cf6f5c478449deca90c6ce2255">llvm::ConstantDataArray::getFP</a>, <a href="/web-llvm/docs/api/classes/llvm/constantdatavector/#acc193957138fece590fe07417912f018">llvm::ConstantDataVector::getFP</a>, <a href="/web-llvm/docs/api/classes/llvm/constantdatavector/#aeecde9516e68842cb97c340bb693a7a9">llvm::ConstantDataVector::getFP</a>, <a href="/web-llvm/docs/api/classes/llvm/constantdatavector/#aa736794cd9a0acefdb428c5ed892a66f">llvm::ConstantDataVector::getFP</a>, <a href="/web-llvm/docs/api/classes/llvm/constantdataarray/#ad86e02b5bee8ad12233bbf1719d1312f">llvm::ConstantDataArray::getRaw</a> and <a href="/web-llvm/docs/api/classes/llvm/constantdatavector/#a074d013c7183283d9aaa8d7127057242">llvm::ConstantDataVector::getRaw</a>.</p>

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
