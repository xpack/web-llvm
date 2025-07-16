---

# DO NOT EDIT!
# Automatically generated via doxygen2docusaurus by Doxygen.

slug: /api/classes/llvm/structtype
custom_edit_url: null
toc_max_heading_level: 4
keywords:
  - doxygen
  - reference
  - class

---

<div class="doxyPage">

# The `StructType` Class Reference

<p>Class to represent struct types. <a href="#details">More...</a></p>

## Declaration

<div class="doxyDeclaration">
class llvm::StructType { ... }
</div>

## Included Headers

<div class="doxyIncludesList">#include "<a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/ir/derivedtypes-h">llvm/IR/DerivedTypes.h</a>"
</div>

## Base class

<table class="doxyMembersIndex">

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">class</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/type">Type</a></td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>The instances of the <a href="/web-llvm/docs/api/classes/llvm/type">Type</a> class are immutable: once they are created, they are never changed. <a href="/web-llvm/docs/api/classes/llvm/type/#details">More...</a></p>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#aef631c67bbe94f9b5a7b9a1292bf225f">element_iterator</a> = <a href="/web-llvm/docs/api/classes/llvm/type/#a5325d504915a0e903f78cd39bbc59bb5">Type::subtype_iterator</a></td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">anonymous enum</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"> { <a href="#a8deeb6e90c1baf7957582dc80915ba65">...</a> }</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a2b14429579f26779cf3a61b67c1d547d">StructType</a> (const StructType &amp;)=delete</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ab59edc77b838bbb56cb3113242121e89">StructType</a> (LLVMContext &amp;C)</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/structtype">StructType</a> &amp;</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#aa7ab521107c655d90b8cfac53b3170bf">operator=</a> (const StructType &amp;)=delete</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a84b61ef997688651dd4e06cb7567cfed">isPacked</a> () const</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ac96253748333192d7c1c05079d7d5446">isLiteral</a> () const</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Return true if this type is uniqued by structural equivalence, false if it is a struct definition. <a href="#ac96253748333192d7c1c05079d7d5446">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">bool</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#aec7c3cecd0559788b36c46df1b2181c1">isOpaque</a> () const</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Return true if this is a type with an identity that has no body specified yet. <a href="#aec7c3cecd0559788b36c46df1b2181c1">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">bool</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a8c3464a21d1db49faba7899d5bd30b5c">isSized</a> (SmallPtrSetImpl&lt; Type * &gt; *Visited=nullptr) const</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>isSized - Return true if this is a sized type. <a href="#a8c3464a21d1db49faba7899d5bd30b5c">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">bool</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#adadba14e740ac7af0ecdface90097843">isScalableTy</a> (SmallPtrSetImpl&lt; const Type * &gt; &amp;Visited) const</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Returns true if this struct contains a scalable vector. <a href="#adadba14e740ac7af0ecdface90097843">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">bool</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a67952c7d76fbc68996a180511599605c">containsNonGlobalTargetExtType</a> (SmallPtrSetImpl&lt; const Type * &gt; &amp;Visited) const</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Return true if this type is or contains a target extension type that disallows being used as a global. <a href="#a67952c7d76fbc68996a180511599605c">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">bool</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a3470f0ea6ba4abfd8d3e7d00ffa021fd">containsNonLocalTargetExtType</a> (SmallPtrSetImpl&lt; const Type * &gt; &amp;Visited) const</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Return true if this type is or contains a target extension type that disallows being used as a local. <a href="#a3470f0ea6ba4abfd8d3e7d00ffa021fd">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">bool</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a3f0523418cc1edc3db74e7aadf8c1e67">containsHomogeneousScalableVectorTypes</a> () const</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Returns true if this struct contains homogeneous scalable vector types. <a href="#a3f0523418cc1edc3db74e7aadf8c1e67">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">bool</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a5f6b348f370750290aa65a3c91bbd695">containsHomogeneousTypes</a> () const</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Return true if this struct is non-empty and all element types are the same. <a href="#a5f6b348f370750290aa65a3c91bbd695">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">bool</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ac5186fcd4c0b2928da92ab126cbe4cd2">hasName</a> () const</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Return true if this is a named struct that has a non-empty name. <a href="#ac5186fcd4c0b2928da92ab126cbe4cd2">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/stringref">StringRef</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#aff252107dbc6129b4dacaac73dd673dd">getName</a> () const</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Return the name for this struct type if it has an identity. <a href="#aff252107dbc6129b4dacaac73dd673dd">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">void</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#aae66135c154b054d4c1469497a34b04a">setName</a> (StringRef Name)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Change the name of this type to the specified name, or to a name with a suffix if there is a collision. <a href="#aae66135c154b054d4c1469497a34b04a">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">void</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a3861d2f045e00a8114f99f751371ec68">setBody</a> (ArrayRef&lt; Type * &gt; Elements, bool isPacked=false)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Specify a body for an opaque identified type, which must not make the type recursive. <a href="#a3861d2f045e00a8114f99f751371ec68">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/error">Error</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#abd30ef90eb46b6ec20daf57888433380">setBodyOrError</a> (ArrayRef&lt; Type * &gt; Elements, bool isPacked=false)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Specify a body for an opaque identified type or return an error if it would make the type recursive. <a href="#abd30ef90eb46b6ec20daf57888433380">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/error">Error</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a586d9700a173a63ae1e26e725bc70ff5">checkBody</a> (ArrayRef&lt; Type * &gt; Elements)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Return an error if the body for an opaque identified type would make it recursive. <a href="#a586d9700a173a63ae1e26e725bc70ff5">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="#aef631c67bbe94f9b5a7b9a1292bf225f">element_iterator</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a69c7da4aea6df614c83c075aa246261a">element_begin</a> () const</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="#aef631c67bbe94f9b5a7b9a1292bf225f">element_iterator</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a1d854d7ca4568e7840af5520a9012960">element_end</a> () const</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/arrayref">ArrayRef</a>&lt; <a href="/web-llvm/docs/api/classes/llvm/type">Type</a> * &gt;</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a339ac1c5133ca49e7a5fb1e37ce0a308">elements</a> () const</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ab45c5514ecd4390e8702c69b19705742">isLayoutIdentical</a> (StructType *Other) const</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Return true if this is layout identical to the specified struct. <a href="#ab45c5514ecd4390e8702c69b19705742">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">unsigned</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a858efd7b61654c0de28c56f9adafa13d">getNumElements</a> () const</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Random access to the elements. <a href="#a858efd7b61654c0de28c56f9adafa13d">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/type">Type</a> *</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#aee3c78d73273cb8449cd10cc15edcb83">getElementType</a> (unsigned N) const</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#abe11230ab448dd37adc9feb99ac7d3da">getTypeAtIndex</a> (const Value *V) const</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Given an index value into the type, return the type of the element. <a href="#abe11230ab448dd37adc9feb99ac7d3da">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/type">Type</a> *</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#aa4a68dda48893ebd98fe7d4878ba0830">getTypeAtIndex</a> (unsigned N) const</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a119364540bae4b4766a944d14cf5dcb5">indexValid</a> (const Value *V) const</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ad8ae602ae369cf6d5f70b0f87884f3b8">indexValid</a> (unsigned Idx) const</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#abc3508a388e7f7545f2a4c745f087916">isScalableTy</a> () const</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ae7b43432683c09a40d81b9b245a05565">containsNonGlobalTargetExtType</a> () const</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ae77d4c2d7f8556667a38ab71c72cb54f">containsNonLocalTargetExtType</a> () const</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">void *</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#aeece89c7043c0b3cb0d1187392f330b7">SymbolTableEntry</a> = nullptr</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>For a named struct that actually has a name, this is a pointer to the symbol table entry (maintained by <a href="/web-llvm/docs/api/classes/llvm/llvmcontext">LLVMContext</a>) for the struct. <a href="#aeece89c7043c0b3cb0d1187392f330b7">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

</table>

## Public Static Functions Index

<table class="doxyMembersIndex">

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">static <a href="/web-llvm/docs/api/classes/llvm/structtype">StructType</a> *</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a82648246c07eb8a33f628eea28cb988c">create</a> (LLVMContext &amp;Context, StringRef Name)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>This creates an identified struct. <a href="#a82648246c07eb8a33f628eea28cb988c">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">static <a href="/web-llvm/docs/api/classes/llvm/structtype">StructType</a> *</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a5dee0347289a045dab07afcc91096b9a">create</a> (LLVMContext &amp;Context)</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">static <a href="/web-llvm/docs/api/classes/llvm/structtype">StructType</a> *</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#aa8ad1ff46b037ecf04611c5b8593317a">create</a> (ArrayRef&lt; Type * &gt; Elements, StringRef Name, bool isPacked=false)</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">static <a href="/web-llvm/docs/api/classes/llvm/structtype">StructType</a> *</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ab44af1bc6e5faaafdc9c8822b95ce047">create</a> (ArrayRef&lt; Type * &gt; Elements)</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">static <a href="/web-llvm/docs/api/classes/llvm/structtype">StructType</a> *</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ab6c57734c1613c9cb4629578d7ac611a">create</a> (LLVMContext &amp;Context, ArrayRef&lt; Type * &gt; Elements, StringRef Name, bool isPacked=false)</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">static <a href="/web-llvm/docs/api/classes/llvm/structtype">StructType</a> *</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a7cf5280be35cd0c973f40c7d87a11acd">create</a> (LLVMContext &amp;Context, ArrayRef&lt; Type * &gt; Elements)</td>
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
<td class="doxyMemberIndexTemplate" colspan="2"><div>template &lt;class... Tys&gt;</div></td>
</tr>
<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemTypeTemplate" align="left" valign="top">static auto </td>
<td class="doxyMemberIndexItemNameTemplate" align="left" valign="top"><a href="#a0d4dbd83b976a1e591bd54c45ecbb3bf">create</a> (StringRef Name, Type *elt1, Tys *... elts) -&gt; std::enable_if_t&lt; <a href="/web-llvm/docs/api/namespaces/llvm/#ae58e012ec4ada45dc3a97ffe84b67290">are_base_of</a>&lt; <a href="/web-llvm/docs/api/classes/llvm/type">Type</a>, Tys... &gt;::value, <a href="/web-llvm/docs/api/classes/llvm/structtype">StructType</a> * &gt;</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">static <a href="/web-llvm/docs/api/classes/llvm/structtype">StructType</a> *</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a18fc4545474c6ebb6f7c547f64f4fb31">get</a> (LLVMContext &amp;Context, ArrayRef&lt; Type * &gt; Elements, bool isPacked=false)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>This static method is the primary way to create a literal <a href="/web-llvm/docs/api/classes/llvm/structtype">StructType</a>. <a href="#a18fc4545474c6ebb6f7c547f64f4fb31">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">static <a href="/web-llvm/docs/api/classes/llvm/structtype">StructType</a> *</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ab49b84f1bf1a79a51d9616ab47b79f71">get</a> (LLVMContext &amp;Context, bool isPacked=false)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Create an empty structure type. <a href="#ab49b84f1bf1a79a51d9616ab47b79f71">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexTemplate">
<td class="doxyMemberIndexTemplate" colspan="2"><div>template &lt;class... Tys&gt;</div></td>
</tr>
<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemTypeTemplate" align="left" valign="top">static auto </td>
<td class="doxyMemberIndexItemNameTemplate" align="left" valign="top"><a href="#af335143f4a0fb6ac98d6102219f9795a">get</a> (Type *elt1, Tys *... elts) -&gt; std::enable_if_t&lt; <a href="/web-llvm/docs/api/namespaces/llvm/#ae58e012ec4ada45dc3a97ffe84b67290">are_base_of</a>&lt; <a href="/web-llvm/docs/api/classes/llvm/type">Type</a>, Tys... &gt;::value, <a href="/web-llvm/docs/api/classes/llvm/structtype">StructType</a> * &gt;</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>This static method is a convenience method for creating structure types by specifying the elements as arguments. <a href="#af335143f4a0fb6ac98d6102219f9795a">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">static <a href="/web-llvm/docs/api/classes/llvm/structtype">StructType</a> *</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a75a89f1513d9f9bdcf0366a436ca43b5">getTypeByName</a> (LLVMContext &amp;C, StringRef Name)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Return the type with the specified name, or null if there is none by that name. <a href="#a75a89f1513d9f9bdcf0366a436ca43b5">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">static bool</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a85475695bba20ea9883c49ce9f890a8a">isValidElementType</a> (Type *ElemTy)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Return true if the specified type is valid as a element type. <a href="#a85475695bba20ea9883c49ce9f890a8a">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">static bool</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a045d43b7a18aec2cec079a3bde8ce16d">classof</a> (const Type *T)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Methods for support type inquiry through isa, cast, and dyn_cast. <a href="#a045d43b7a18aec2cec079a3bde8ce16d">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

</table>

## Description {#details}

<p>Class to represent struct types.</p>


<p>There are two different kinds of struct types: Literal structs and Identified structs.</p>


<p>Literal struct types (e.g. { i32, i32 }) are uniqued structurally, and must always have a body when created. You can get one of these by using one of the <a href="#a18fc4545474c6ebb6f7c547f64f4fb31">StructType::get()</a> forms.</p>


<p>Identified structs (e.g. foo or %42) may optionally have a name and are not uniqued. The names for identified structs are managed at the <a href="/web-llvm/docs/api/classes/llvm/llvmcontext">LLVMContext</a> level, so there can only be a single identified struct with a given name in a particular <a href="/web-llvm/docs/api/classes/llvm/llvmcontext">LLVMContext</a>. Identified structs may also optionally be opaque (have no body specified). You get one of these by using one of the <a href="#a82648246c07eb8a33f628eea28cb988c">StructType::create()</a> forms.</p>


<p>Independent of what kind of struct you have, the body of a struct type are laid out in memory consecutively with the elements directly one after the other (if the struct is packed) or (if not packed) with padding between the elements as defined by <a href="/web-llvm/docs/api/classes/llvm/datalayout">DataLayout</a> (which is required to match what the code generator for a target expects).</p>


<p>Definition at line 218 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/ir/derivedtypes-h">DerivedTypes.h</a>.</p>


<div class="doxySectionDef">

## Public Member Typedefs

### element\_iterator {#aef631c67bbe94f9b5a7b9a1292bf225f}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">using llvm::StructType::element_iterator =  Type::subtype_iterator</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 353 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/ir/derivedtypes-h">DerivedTypes.h</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Enumerations

### anonymous enum  {#a8deeb6e90c1baf7957582dc80915ba65}

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
<td class="doxyEnumItemName">SCDB_HasBody<a id="a8deeb6e90c1baf7957582dc80915ba65a02a73de1cb2092121eb7efed03e69759"></a></td>
<td class="doxyEnumItemDescription">This is the contents of the SubClassData field (= 1)</td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">SCDB_Packed<a id="a8deeb6e90c1baf7957582dc80915ba65aa0767850cabb5fc1699ff565778d769a"></a></td>
<td class="doxyEnumItemDescription"> (= 2)</td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">SCDB_IsLiteral<a id="a8deeb6e90c1baf7957582dc80915ba65a9c49d093a26dbc62e44dd981c2216ecb"></a></td>
<td class="doxyEnumItemDescription"> (= 4)</td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">SCDB_IsSized<a id="a8deeb6e90c1baf7957582dc80915ba65afe1fba7209dacb476197bb51c3555767"></a></td>
<td class="doxyEnumItemDescription"> (= 8)</td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">SCDB_ContainsScalableVector<a id="a8deeb6e90c1baf7957582dc80915ba65a98f215eccf80e7e665e830874af5e849"></a></td>
<td class="doxyEnumItemDescription"> (= 16)</td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">SCDB_NotContainsScalableVector<a id="a8deeb6e90c1baf7957582dc80915ba65a59bd9e3ad1a5b5cab2c27455b08ad547"></a></td>
<td class="doxyEnumItemDescription"> (= 32)</td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">SCDB_ContainsNonGlobalTargetExtType<a id="a8deeb6e90c1baf7957582dc80915ba65a6d811de89b1f6e58566337bd4e766daa"></a></td>
<td class="doxyEnumItemDescription"> (= 64)</td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">SCDB_NotContainsNonGlobalTargetExtType<a id="a8deeb6e90c1baf7957582dc80915ba65a05e8b88893a7aeac0958bfc456076d76"></a></td>
<td class="doxyEnumItemDescription"> (= 128)</td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">SCDB_ContainsNonLocalTargetExtType<a id="a8deeb6e90c1baf7957582dc80915ba65ad3c91460642b31366d95f9923857717a"></a></td>
<td class="doxyEnumItemDescription"> (= 64)</td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">SCDB_NotContainsNonLocalTargetExtType<a id="a8deeb6e90c1baf7957582dc80915ba65a2049f53b9f1530ea1c3adc8b82d0fe6b"></a></td>
<td class="doxyEnumItemDescription"> (= 128)</td>
</tr>

</table>
</dd>
</dl>

<p>Definition at line 221 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/ir/derivedtypes-h">DerivedTypes.h</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Public Constructors

### StructType() {#a2b14429579f26779cf3a61b67c1d547d}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">llvm::StructType::StructType (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/structtype">StructType</a> &amp;)</td>
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



<p>Definition at line 242 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/ir/derivedtypes-h">DerivedTypes.h</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Private Constructors

### StructType() {#ab59edc77b838bbb56cb3113242121e89}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">llvm::StructType::StructType (<a href="/web-llvm/docs/api/classes/llvm/llvmcontext">LLVMContext</a> &amp; C)</td>
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



<p>Definition at line 219 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/ir/derivedtypes-h">DerivedTypes.h</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Public Operators

### operator=() {#aa7ab521107c655d90b8cfac53b3170bf}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">StructType &amp; llvm::StructType::operator= (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/structtype">StructType</a> &amp;)</td>
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



<p>Definition at line 243 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/ir/derivedtypes-h">DerivedTypes.h</a>.</p>


<p>References <a href="#a84b61ef997688651dd4e06cb7567cfed">isPacked</a> and <a href="/web-llvm/docs/api/classes/llvm/type/#a817dfd76b27697e96a20f80f7bb68251">llvm::Type::Type</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Public Member Functions

### checkBody() {#a586d9700a173a63ae1e26e725bc70ff5}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">Error StructType::checkBody (<a href="/web-llvm/docs/api/classes/llvm/arrayref">ArrayRef</a>&lt; <a href="/web-llvm/docs/api/classes/llvm/type">Type</a> * &gt; Elements)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Return an error if the body for an opaque identified type would make it recursive.</p>

<p>Declaration at line 347 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/ir/derivedtypes-h">DerivedTypes.h</a>, definition at line 549 of file <a href="/web-llvm/docs/api/files/lib/lib/sandboxir/type-cpp">Type.cpp</a>.</p>

</div>
</div>

### containsHomogeneousScalableVectorTypes() {#a3f0523418cc1edc3db74e7aadf8c1e67}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool StructType::containsHomogeneousScalableVectorTypes ()</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Returns true if this struct contains homogeneous scalable vector types.</p>


<p>Note that the definition of homogeneous scalable vector type is not recursive here. That means the following structure will return false when calling this function. {{&lt;vscale x 2 x i32&gt;, &lt;vscale x 4 x i64&gt;}, {&lt;vscale x 2 x i32&gt;, &lt;vscale x 4 x i64&gt;}}</p>


<p>Declaration at line 319 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/ir/derivedtypes-h">DerivedTypes.h</a>, definition at line 516 of file <a href="/web-llvm/docs/api/files/lib/lib/sandboxir/type-cpp">Type.cpp</a>.</p>

</div>
</div>

### containsHomogeneousTypes() {#a5f6b348f370750290aa65a3c91bbd695}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool StructType::containsHomogeneousTypes ()</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Return true if this struct is non-empty and all element types are the same.</p>

<p>Declaration at line 323 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/ir/derivedtypes-h">DerivedTypes.h</a>, definition at line 522 of file <a href="/web-llvm/docs/api/files/lib/lib/sandboxir/type-cpp">Type.cpp</a>.</p>

</div>
</div>

### containsNonGlobalTargetExtType() {#a67952c7d76fbc68996a180511599605c}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool StructType::containsNonGlobalTargetExtType (<a href="/web-llvm/docs/api/classes/llvm/smallptrsetimpl">SmallPtrSetImpl</a>&lt; <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/type">Type</a> * &gt; &amp; Visited)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Return true if this type is or contains a target extension type that disallows being used as a global.</p>

<p>Declaration at line 304 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/ir/derivedtypes-h">DerivedTypes.h</a>, definition at line 460 of file <a href="/web-llvm/docs/api/files/lib/lib/sandboxir/type-cpp">Type.cpp</a>.</p>

</div>
</div>

### containsNonGlobalTargetExtType() {#ae7b43432683c09a40d81b9b245a05565}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool Type::containsNonGlobalTargetExtType ()</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Declaration at line 305 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/ir/derivedtypes-h">DerivedTypes.h</a>, definition at line 86 of file <a href="/web-llvm/docs/api/files/lib/lib/sandboxir/type-cpp">Type.cpp</a>.</p>

</div>
</div>

### containsNonLocalTargetExtType() {#a3470f0ea6ba4abfd8d3e7d00ffa021fd}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool StructType::containsNonLocalTargetExtType (<a href="/web-llvm/docs/api/classes/llvm/smallptrsetimpl">SmallPtrSetImpl</a>&lt; <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/type">Type</a> * &gt; &amp; Visited)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Return true if this type is or contains a target extension type that disallows being used as a local.</p>

<p>Declaration at line 310 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/ir/derivedtypes-h">DerivedTypes.h</a>, definition at line 488 of file <a href="/web-llvm/docs/api/files/lib/lib/sandboxir/type-cpp">Type.cpp</a>.</p>

</div>
</div>

### containsNonLocalTargetExtType() {#ae77d4c2d7f8556667a38ab71c72cb54f}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool Type::containsNonLocalTargetExtType ()</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Declaration at line 311 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/ir/derivedtypes-h">DerivedTypes.h</a>, definition at line 102 of file <a href="/web-llvm/docs/api/files/lib/lib/sandboxir/type-cpp">Type.cpp</a>.</p>

</div>
</div>

### element\_begin() {#a69c7da4aea6df614c83c075aa246261a}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">element_iterator llvm::StructType::element_begin ()</td>
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



<p>Definition at line 355 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/ir/derivedtypes-h">DerivedTypes.h</a>.</p>


<p>Reference <a href="/web-llvm/docs/api/classes/llvm/type/#a96d2037eb473457f3222e5cbe7ea22b5">llvm::Type::ContainedTys</a>.</p>


<p>Referenced by <a href="#a339ac1c5133ca49e7a5fb1e37ce0a308">elements</a> and <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/scalar/sroa-cpp/#ad866ad1da941867a398da262103469b1">getTypePartition</a>.</p>

</div>
</div>

### element\_end() {#a1d854d7ca4568e7840af5520a9012960}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">element_iterator llvm::StructType::element_end ()</td>
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



<p>Definition at line 356 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/ir/derivedtypes-h">DerivedTypes.h</a>.</p>


<p>References <a href="/web-llvm/docs/api/classes/llvm/type/#a96d2037eb473457f3222e5cbe7ea22b5">llvm::Type::ContainedTys</a> and <a href="/web-llvm/docs/api/classes/llvm/type/#a679d8ea00092eb9cd392643bb2d1b7f9">llvm::Type::NumContainedTys</a>.</p>


<p>Referenced by <a href="#a339ac1c5133ca49e7a5fb1e37ce0a308">elements</a> and <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/scalar/sroa-cpp/#ad866ad1da941867a398da262103469b1">getTypePartition</a>.</p>

</div>
</div>

### elements() {#a339ac1c5133ca49e7a5fb1e37ce0a308}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">ArrayRef&lt; Type * &gt; llvm::StructType::elements ()</td>
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



<p>Definition at line 357 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/ir/derivedtypes-h">DerivedTypes.h</a>.</p>


<p>References <a href="/web-llvm/docs/api/namespaces/llvm/#ab9c6b351507d3c0730f4290919d43a12">llvm::ArrayRef</a>, <a href="#a69c7da4aea6df614c83c075aa246261a">element_begin</a> and <a href="#a1d854d7ca4568e7840af5520a9012960">element_end</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/namespaces/llvm/#a15795bcb48d8b3c37995ae4459f0af7d">llvm::canVectorizeStructTy</a>, <a href="/web-llvm/docs/api/files/lib/lib/analysis/modulesummaryanalysis-cpp/#a221bfefa2a7606c89cb5a8635375f891">findFuncPointers</a>, <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/ipo/globalopt-cpp/#ace2885fc42e68606f270bfd3180d5f26">isLeakCheckerRoot</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#af917412cc13ec525beaccfd6d149df70">llvm::isVectorizedStructTy</a>, <a href="/web-llvm/docs/api/classes/anonymous-asmwriter-cpp-/typeprinting/#a5d0d67de3d911ed1af72a285d25e2282">anonymous{AsmWriter.cpp}::TypePrinting::printStructBody</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#af3d7a362fea3dd362c790529f2afcbfa">llvm::toScalarizedStructTy</a> and <a href="/web-llvm/docs/api/namespaces/llvm/#a77e211e8fb596ed21bb29f80aeacc211">llvm::toVectorizedStructTy</a>.</p>

</div>
</div>

### getElementType() {#aee3c78d73273cb8449cd10cc15edcb83}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">Type * llvm::StructType::getElementType (unsigned N)</td>
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



<p>Definition at line 366 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/ir/derivedtypes-h">DerivedTypes.h</a>.</p>


<p>References <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/silowercontrolflow-cpp/#a4868c5d81c5ccc98c47aeab6244346a0">assert</a>, <a href="/web-llvm/docs/api/classes/llvm/type/#a96d2037eb473457f3222e5cbe7ea22b5">llvm::Type::ContainedTys</a>, <a href="/web-llvm/docs/api/files/lib/lib/support/regcomp-c/#a0240ac851181b84ac374872dc5434ee4">N</a>, <a href="/web-llvm/docs/api/classes/llvm/type/#a679d8ea00092eb9cd392643bb2d1b7f9">llvm::Type::NumContainedTys</a> and <a href="/web-llvm/docs/api/classes/llvm/type/#a817dfd76b27697e96a20f80f7bb68251">llvm::Type::Type</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/coroutines/coroframe-cpp/#a86c6fee36a1f17461710c01e694ee8df">buildFrameDebugInfo</a>, <a href="/web-llvm/docs/api/files/lib/lib/analysis/valuetracking-cpp/#afbd7f8e7654d71a5771a4eaa8b622bd2">BuildSubAggregate</a>, <a href="/web-llvm/docs/api/classes/llvm/functioncomparator/#a96167048c547bb562d69720cee2a48a6">llvm::FunctionComparator::cmpTypes</a>, <a href="#aa4a68dda48893ebd98fe7d4878ba0830">getTypeAtIndex</a>, <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/scalar/sroa-cpp/#ad866ad1da941867a398da262103469b1">getTypePartition</a>, <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/coroutines/coroframe-cpp/#af0885df5b78cc732639a9d52a87d040e">insertSpills</a>, <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/ipo/attributorattributes-cpp/#abe341eed08efd4655f89b7a07faa66be">isDenselyPacked</a> and <a href="/web-llvm/docs/api/namespaces/llvm/#a95b7e7311ec52352ada27699c3c9c470">llvm::UpgradeGlobalVariable</a>.</p>

</div>
</div>

### getName() {#aff252107dbc6129b4dacaac73dd673dd}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">StringRef StructType::getName ()</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Return the name for this struct type if it has an identity.</p>


<p>This may return an empty string for an unnamed struct type. Do not call this on an literal type.</p>


<p>Declaration at line 331 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/ir/derivedtypes-h">DerivedTypes.h</a>, definition at line 689 of file <a href="/web-llvm/docs/api/files/lib/lib/sandboxir/type-cpp">Type.cpp</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/classes/llvm/btfdebug/#adc24c0346dea71c12facfce5d4d4d4b7">llvm::BTFDebug::endModule</a> and <a href="/web-llvm/docs/api/classes/anonymous-asmwriter-cpp-/typeprinting/#a0ec5edfa2f5d23c2b6b630469f22e875">anonymous{AsmWriter.cpp}::TypePrinting::print</a>.</p>

</div>
</div>

### getNumElements() {#a858efd7b61654c0de28c56f9adafa13d}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">unsigned llvm::StructType::getNumElements ()</td>
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

<p>Random access to the elements.</p>

<p>Definition at line 365 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/ir/derivedtypes-h">DerivedTypes.h</a>.</p>


<p>Reference <a href="/web-llvm/docs/api/classes/llvm/type/#a679d8ea00092eb9cd392643bb2d1b7f9">llvm::Type::NumContainedTys</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/utils/moduleutils-cpp/#a8508f3dbb1f9429445f50282297b4f9a">appendToGlobalArray</a>, <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/coroutines/coroframe-cpp/#a86c6fee36a1f17461710c01e694ee8df">buildFrameDebugInfo</a>, <a href="/web-llvm/docs/api/files/lib/lib/analysis/valuetracking-cpp/#afbd7f8e7654d71a5771a4eaa8b622bd2">BuildSubAggregate</a>, <a href="/web-llvm/docs/api/classes/llvm/functioncomparator/#a96167048c547bb562d69720cee2a48a6">llvm::FunctionComparator::cmpTypes</a>, <a href="/web-llvm/docs/api/files/lib/lib/codegen/lib/codegen/asmprinter/asmprinter-cpp/#ab23c37279d90814b87d6c8ab25b43d0b">emitGlobalConstantImpl</a>, <a href="#ad8ae602ae369cf6d5f70b0f87884f3b8">indexValid</a>, <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/ipo/attributorattributes-cpp/#abe341eed08efd4655f89b7a07faa66be">isDenselyPacked</a>, <a href="/web-llvm/docs/api/classes/llvm/sccpinstvisitor/#abbe263f1f7adf177d16f061137dd8c19">llvm::SCCPInstVisitor::isStructLatticeConstant</a>, <a href="/web-llvm/docs/api/classes/anonymous-asmwriter-cpp-/typeprinting/#a5d0d67de3d911ed1af72a285d25e2282">anonymous{AsmWriter.cpp}::TypePrinting::printStructBody</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a95b7e7311ec52352ada27699c3c9c470">llvm::UpgradeGlobalVariable</a> and <a href="/web-llvm/docs/api/classes/llvm/inlineasm/#adfcd3a2486f54c348da1859c41f6cc09">llvm::InlineAsm::verify</a>.</p>

</div>
</div>

### getTypeAtIndex() {#abe11230ab448dd37adc9feb99ac7d3da}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">Type * StructType::getTypeAtIndex (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/value">Value</a> * V)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Given an index value into the type, return the type of the element.</p>

<p>Declaration at line 371 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/ir/derivedtypes-h">DerivedTypes.h</a>, definition at line 711 of file <a href="/web-llvm/docs/api/files/lib/lib/sandboxir/type-cpp">Type.cpp</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/coroutines/corosplit-cpp/#aa6734dd82cf736e89074802287b0abfe">markCoroutineAsDone</a>.</p>

</div>
</div>

### getTypeAtIndex() {#aa4a68dda48893ebd98fe7d4878ba0830}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">Type * llvm::StructType::getTypeAtIndex (unsigned N)</td>
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



<p>Definition at line 372 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/ir/derivedtypes-h">DerivedTypes.h</a>.</p>


<p>References <a href="#aee3c78d73273cb8449cd10cc15edcb83">getElementType</a>, <a href="/web-llvm/docs/api/files/lib/lib/support/regcomp-c/#a0240ac851181b84ac374872dc5434ee4">N</a> and <a href="/web-llvm/docs/api/classes/llvm/type/#a817dfd76b27697e96a20f80f7bb68251">llvm::Type::Type</a>.</p>

</div>
</div>

### hasName() {#ac5186fcd4c0b2928da92ab126cbe4cd2}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool llvm::StructType::hasName ()</td>
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

<p>Return true if this is a named struct that has a non-empty name.</p>

<p>Definition at line 326 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/ir/derivedtypes-h">DerivedTypes.h</a>.</p>

</div>
</div>

### indexValid() {#a119364540bae4b4766a944d14cf5dcb5}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool StructType::indexValid (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/value">Value</a> * V)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Declaration at line 373 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/ir/derivedtypes-h">DerivedTypes.h</a>, definition at line 717 of file <a href="/web-llvm/docs/api/files/lib/lib/sandboxir/type-cpp">Type.cpp</a>.</p>

</div>
</div>

### indexValid() {#ad8ae602ae369cf6d5f70b0f87884f3b8}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool llvm::StructType::indexValid (unsigned Idx)</td>
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



<p>Definition at line 374 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/ir/derivedtypes-h">DerivedTypes.h</a>.</p>


<p>Reference <a href="#a858efd7b61654c0de28c56f9adafa13d">getNumElements</a>.</p>

</div>
</div>

### isLayoutIdentical() {#ab45c5514ecd4390e8702c69b19705742}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool StructType::isLayoutIdentical (<a href="/web-llvm/docs/api/classes/llvm/structtype">StructType</a> * Other)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Return true if this is layout identical to the specified struct.</p>

<p>Declaration at line 362 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/ir/derivedtypes-h">DerivedTypes.h</a>, definition at line 702 of file <a href="/web-llvm/docs/api/files/lib/lib/sandboxir/type-cpp">Type.cpp</a>.</p>

</div>
</div>

### isLiteral() {#ac96253748333192d7c1c05079d7d5446}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool llvm::StructType::isLiteral ()</td>
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

<p>Return true if this type is uniqued by structural equivalence, false if it is a struct definition.</p>

<p>Definition at line 288 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/ir/derivedtypes-h">DerivedTypes.h</a>.</p>


<p>Reference <a href="/web-llvm/docs/api/classes/llvm/type/#a977023a135a15dc3aadcf1e8246631f8">llvm::Type::getSubclassData</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/namespaces/llvm/#a28db78be8569f9cabe49007baf76cff2">llvm::isUnpackedStructLiteral</a>, <a href="/web-llvm/docs/api/structs/false/gepnode/#a8702875a47c894f09fb5b7f502b0b1f4">false::GepNode::operator&lt;&lt;</a> and <a href="/web-llvm/docs/api/classes/anonymous-asmwriter-cpp-/typeprinting/#a0ec5edfa2f5d23c2b6b630469f22e875">anonymous{AsmWriter.cpp}::TypePrinting::print</a>.</p>

</div>
</div>

### isOpaque() {#aec7c3cecd0559788b36c46df1b2181c1}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool llvm::StructType::isOpaque ()</td>
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

<p>Return true if this is a type with an identity that has no body specified yet.</p>


<p>These prints as 'opaque' in .ll files.</p>


<p>Definition at line 292 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/ir/derivedtypes-h">DerivedTypes.h</a>.</p>


<p>Reference <a href="/web-llvm/docs/api/classes/llvm/type/#a977023a135a15dc3aadcf1e8246631f8">llvm::Type::getSubclassData</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/ipo/globalopt-cpp/#ace2885fc42e68606f270bfd3180d5f26">isLeakCheckerRoot</a>, <a href="/web-llvm/docs/api/classes/anonymous-irmover-cpp-/typemapty/#a9458e9521315cb278dee23c71634b48e">anonymous{IRMover.cpp}::TypeMapTy::linkDefinedTypeBodies</a> and <a href="/web-llvm/docs/api/classes/anonymous-asmwriter-cpp-/typeprinting/#a5d0d67de3d911ed1af72a285d25e2282">anonymous{AsmWriter.cpp}::TypePrinting::printStructBody</a>.</p>

</div>
</div>

### isPacked() {#a84b61ef997688651dd4e06cb7567cfed}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool llvm::StructType::isPacked ()</td>
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



<p>Definition at line 284 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/ir/derivedtypes-h">DerivedTypes.h</a>.</p>


<p>Reference <a href="/web-llvm/docs/api/classes/llvm/type/#a977023a135a15dc3aadcf1e8246631f8">llvm::Type::getSubclassData</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/classes/llvm/functioncomparator/#a96167048c547bb562d69720cee2a48a6">llvm::FunctionComparator::cmpTypes</a>, <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/scalar/sroa-cpp/#ad866ad1da941867a398da262103469b1">getTypePartition</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a28db78be8569f9cabe49007baf76cff2">llvm::isUnpackedStructLiteral</a>, <a href="#aa7ab521107c655d90b8cfac53b3170bf">operator=</a> and <a href="/web-llvm/docs/api/classes/anonymous-asmwriter-cpp-/typeprinting/#a5d0d67de3d911ed1af72a285d25e2282">anonymous{AsmWriter.cpp}::TypePrinting::printStructBody</a>.</p>

</div>
</div>

### isScalableTy() {#adadba14e740ac7af0ecdface90097843}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool StructType::isScalableTy (<a href="/web-llvm/docs/api/classes/llvm/smallptrsetimpl">SmallPtrSetImpl</a>&lt; <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/type">Type</a> * &gt; &amp; Visited)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Returns true if this struct contains a scalable vector.</p>

<p>Declaration at line 298 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/ir/derivedtypes-h">DerivedTypes.h</a>, definition at line 433 of file <a href="/web-llvm/docs/api/files/lib/lib/sandboxir/type-cpp">Type.cpp</a>.</p>

</div>
</div>

### isScalableTy() {#abc3508a388e7f7545f2a4c745f087916}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool Type::isScalableTy ()</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Declaration at line 299 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/ir/derivedtypes-h">DerivedTypes.h</a>, definition at line 70 of file <a href="/web-llvm/docs/api/files/lib/lib/sandboxir/type-cpp">Type.cpp</a>.</p>

</div>
</div>

### isSized() {#a8c3464a21d1db49faba7899d5bd30b5c}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool StructType::isSized (<a href="/web-llvm/docs/api/classes/llvm/smallptrsetimpl">SmallPtrSetImpl</a>&lt; <a href="/web-llvm/docs/api/classes/llvm/type">Type</a> * &gt; * Visited=nullptr)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>isSized - Return true if this is a sized type.</p>

<p>Declaration at line 295 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/ir/derivedtypes-h">DerivedTypes.h</a>, definition at line 651 of file <a href="/web-llvm/docs/api/files/lib/lib/sandboxir/type-cpp">Type.cpp</a>.</p>

</div>
</div>

### setBody() {#a3861d2f045e00a8114f99f751371ec68}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void StructType::setBody (<a href="/web-llvm/docs/api/classes/llvm/arrayref">ArrayRef</a>&lt; <a href="/web-llvm/docs/api/classes/llvm/type">Type</a> * &gt; Elements, bool isPacked=false)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Specify a body for an opaque identified type, which must not make the type recursive.</p>

<p>Declaration at line 339 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/ir/derivedtypes-h">DerivedTypes.h</a>, definition at line 527 of file <a href="/web-llvm/docs/api/files/lib/lib/sandboxir/type-cpp">Type.cpp</a>.</p>

</div>
</div>

### setBodyOrError() {#abd30ef90eb46b6ec20daf57888433380}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">Error StructType::setBodyOrError (<a href="/web-llvm/docs/api/classes/llvm/arrayref">ArrayRef</a>&lt; <a href="/web-llvm/docs/api/classes/llvm/type">Type</a> * &gt; Elements, bool isPacked=false)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Specify a body for an opaque identified type or return an error if it would make the type recursive.</p>

<p>Declaration at line 343 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/ir/derivedtypes-h">DerivedTypes.h</a>, definition at line 531 of file <a href="/web-llvm/docs/api/files/lib/lib/sandboxir/type-cpp">Type.cpp</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/classes/anonymous-irmover-cpp-/typemapty/#a9458e9521315cb278dee23c71634b48e">anonymous{IRMover.cpp}::TypeMapTy::linkDefinedTypeBodies</a>.</p>

</div>
</div>

### setName() {#aae66135c154b054d4c1469497a34b04a}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void StructType::setName (<a href="/web-llvm/docs/api/classes/llvm/stringref">StringRef</a> Name)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Change the name of this type to the specified name, or to a name with a suffix if there is a collision.</p>


<p>Do not call this on an literal type.</p>


<p>Declaration at line 335 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/ir/derivedtypes-h">DerivedTypes.h</a>, definition at line 561 of file <a href="/web-llvm/docs/api/files/lib/lib/sandboxir/type-cpp">Type.cpp</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Private Member Attributes

### SymbolTableEntry {#aeece89c7043c0b3cb0d1187392f330b7}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void* llvm::StructType::SymbolTableEntry = nullptr</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>For a named struct that actually has a name, this is a pointer to the symbol table entry (maintained by <a href="/web-llvm/docs/api/classes/llvm/llvmcontext">LLVMContext</a>) for the struct.</p>


<p>This is null if the type is an literal struct or if it is a identified type that has an empty name.</p>


<p>Definition at line 239 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/ir/derivedtypes-h">DerivedTypes.h</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Public Static Functions

### classof() {#a045d43b7a18aec2cec079a3bde8ce16d}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool llvm::StructType::classof (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/type">Type</a> * T)</td>
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

<p>Methods for support type inquiry through isa, cast, and dyn_cast.</p>

<p>Definition at line 377 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/ir/derivedtypes-h">DerivedTypes.h</a>.</p>


<p>References <a href="/web-llvm/docs/api/classes/llvm/type/#a5e9e1c0dd93557be1b4ad72860f3cbdaa812a573d23fbb37aacd025e2a0588156">llvm::Type::StructTyID</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/mips/mips16isellowering-cpp/#a0acb682b8260ab1c60b918599864e2e5">T</a> and <a href="/web-llvm/docs/api/classes/llvm/type/#a817dfd76b27697e96a20f80f7bb68251">llvm::Type::Type</a>.</p>

</div>
</div>

### create() {#a82648246c07eb8a33f628eea28cb988c}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">StructType * StructType::create (<a href="/web-llvm/docs/api/classes/llvm/llvmcontext">LLVMContext</a> &amp; Context, <a href="/web-llvm/docs/api/classes/llvm/stringref">StringRef</a> Name)</td>
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

<p>This creates an identified struct.</p>

<p>Declaration at line 246 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/ir/derivedtypes-h">DerivedTypes.h</a>, definition at line 612 of file <a href="/web-llvm/docs/api/files/lib/lib/sandboxir/type-cpp">Type.cpp</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/files/lib/lib/codegen/loweremutls-cpp/#aeddd04f458fd6e9db5a892543636e240">addEmuTlsVar</a>, <a href="/web-llvm/docs/api/classes/anonymous-expandvariadics-cpp-/expandvariadics/expandedcallframe/#a1d6faa7f2b8675618a76304049e2ecee">anonymous{ExpandVariadics.cpp}::ExpandVariadics::ExpandedCallFrame::asStruct</a>, <a href="#a0d4dbd83b976a1e591bd54c45ecbb3bf">create</a>, <a href="/web-llvm/docs/api/classes/llvm/dxil/resourcetypeinfo/#a643353cc59fa74e91cb3212e25475f58">llvm::dxil::ResourceTypeInfo::createElementStruct</a>, <a href="/web-llvm/docs/api/classes/llvm/openmpirbuilder/#aaa655ca8bca40c564d0b7c81ebaf8ff9">llvm::OpenMPIRBuilder::createReductionsGPU</a>, <a href="/web-llvm/docs/api/classes/anonymous-shadowstackgclowering-cpp-/shadowstackgcloweringimpl/#a285f4b41becdfd4385ddb237bfc744fc">anonymous{ShadowStackGCLowering.cpp}::ShadowStackGCLoweringImpl::doInitialization</a>, <a href="/web-llvm/docs/api/classes/llvm/orc/irspeculationlayer/#ac443c17bb572b2276321acc44b417ec7">llvm::orc::IRSpeculationLayer::emit</a>, <a href="/web-llvm/docs/api/classes/llvm/openmpirbuilder/#a827b80924bcd29f32b772a4ed162fb68">llvm::OpenMPIRBuilder::emitNonContiguousDescriptor</a>, <a href="/web-llvm/docs/api/classes/anonymous-coroframe-cpp-/frametypebuilder/#abe0dacfb2237ff8fb43d5ad22ac45d5f">anonymous{CoroFrame.cpp}::FrameTypeBuilder::finish</a>, <a href="/web-llvm/docs/api/namespaces/anonymous-offloadwrapper-cpp-/#a604c924e11ca5df4475086acc8db0f4e">anonymous{OffloadWrapper.cpp}::getBinDescTy</a>, <a href="/web-llvm/docs/api/namespaces/anonymous-offloadwrapper-cpp-/#a8ba7541c9160f54941d8b6029ec4d2ae">anonymous{OffloadWrapper.cpp}::getDeviceImageTy</a>, <a href="/web-llvm/docs/api/namespaces/llvm/offloading/#a6955657cb7867972e6b8f046e9cf5a02">llvm::offloading::getEntryTy</a>, <a href="/web-llvm/docs/api/namespaces/anonymous-offloadwrapper-cpp-/#ad046f69ab8abe8d2605589e6daf42612">anonymous{OffloadWrapper.cpp}::getFatbinWrapperTy</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/directx/dxilopbuilder-cpp/#a9b36c3934c9c2e8a2dc9fcb4cdee876b">getOrCreateStructType</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/directx/dxilopbuilder-cpp/#aff234d51ccd591da6c1332a3d52fbe1e">getResBindType</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/directx/dxilopbuilder-cpp/#af69be60078714a34c733e198b5aab9af">getResPropsType</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/directx/dxilopbuilder-cpp/#a5f6846040fc48f21e5969492bbb88fdc">getSplitDoubleType</a>, <a href="/web-llvm/docs/api/classes/llvm/basicttiimplbase/#ae2b0b2a1ae237432c1c272406a8b4667">llvm::BasicTTIImplBase&lt; BasicTTIImpl &gt;::getTypeBasedIntrinsicInstrCost</a>, <a href="/web-llvm/docs/api/groups/llvmccoretypestruct/#gaf3bed4d4b79664d613acf8b9dbfbccb7">LLVMStructCreateNamed</a>, <a href="/web-llvm/docs/api/classes/anonymous-amdgpuswlowerlds-cpp-/amdgpuswlowerlds/#a7bc472aa7f200453c2fb1d5fbc404b66">anonymous{AMDGPUSwLowerLDS.cpp}::AMDGPUSwLowerLDS::populateSwMetadataGlobal</a>, <a href="/web-llvm/docs/api/classes/anonymous-amdgpuopenclenqueuedblocklowering-cpp-/amdgpuopenclenqueuedblocklowering/#ac3eeb5c96b81aa7ad07041b3c20eeb04">anonymous{AMDGPUOpenCLEnqueuedBlockLowering.cpp}::AMDGPUOpenCLEnqueuedBlockLowering::run</a>, <a href="/web-llvm/docs/api/classes/anonymous-amdgpurewriteoutarguments-cpp-/amdgpurewriteoutarguments/#af9d46a08167454a31f6a9157eb65a44a">anonymous{AMDGPURewriteOutArguments.cpp}::AMDGPURewriteOutArguments::runOnFunction</a> and <a href="/web-llvm/docs/api/classes/anonymous-lljit-cpp-/genericllvmirplatformsupport/#a27bbd3687e81d99d0ad1333b8f5e7f08">anonymous{LLJIT.cpp}::GenericLLVMIRPlatformSupport::setupJITDylib</a>.</p>

</div>
</div>

### create() {#a5dee0347289a045dab07afcc91096b9a}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">StructType * StructType::create (<a href="/web-llvm/docs/api/classes/llvm/llvmcontext">LLVMContext</a> &amp; Context)</td>
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



<p>Declaration at line 247 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/ir/derivedtypes-h">DerivedTypes.h</a>, definition at line 634 of file <a href="/web-llvm/docs/api/files/lib/lib/sandboxir/type-cpp">Type.cpp</a>.</p>

</div>
</div>

### create() {#aa8ad1ff46b037ecf04611c5b8593317a}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">StructType * StructType::create (<a href="/web-llvm/docs/api/classes/llvm/arrayref">ArrayRef</a>&lt; <a href="/web-llvm/docs/api/classes/llvm/type">Type</a> * &gt; Elements, <a href="/web-llvm/docs/api/classes/llvm/stringref">StringRef</a> Name, bool isPacked=false)</td>
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



<p>Declaration at line 249 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/ir/derivedtypes-h">DerivedTypes.h</a>, definition at line 638 of file <a href="/web-llvm/docs/api/files/lib/lib/sandboxir/type-cpp">Type.cpp</a>.</p>

</div>
</div>

### create() {#ab44af1bc6e5faaafdc9c8822b95ce047}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">StructType * StructType::create (<a href="/web-llvm/docs/api/classes/llvm/arrayref">ArrayRef</a>&lt; <a href="/web-llvm/docs/api/classes/llvm/type">Type</a> * &gt; Elements)</td>
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



<p>Declaration at line 251 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/ir/derivedtypes-h">DerivedTypes.h</a>, definition at line 645 of file <a href="/web-llvm/docs/api/files/lib/lib/sandboxir/type-cpp">Type.cpp</a>.</p>

</div>
</div>

### create() {#ab6c57734c1613c9cb4629578d7ac611a}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">StructType * StructType::create (<a href="/web-llvm/docs/api/classes/llvm/llvmcontext">LLVMContext</a> &amp; Context, <a href="/web-llvm/docs/api/classes/llvm/arrayref">ArrayRef</a>&lt; <a href="/web-llvm/docs/api/classes/llvm/type">Type</a> * &gt; Elements, <a href="/web-llvm/docs/api/classes/llvm/stringref">StringRef</a> Name, bool isPacked=false)</td>
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



<p>Declaration at line 252 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/ir/derivedtypes-h">DerivedTypes.h</a>, definition at line 623 of file <a href="/web-llvm/docs/api/files/lib/lib/sandboxir/type-cpp">Type.cpp</a>.</p>

</div>
</div>

### create() {#a7cf5280be35cd0c973f40c7d87a11acd}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">StructType * StructType::create (<a href="/web-llvm/docs/api/classes/llvm/llvmcontext">LLVMContext</a> &amp; Context, <a href="/web-llvm/docs/api/classes/llvm/arrayref">ArrayRef</a>&lt; <a href="/web-llvm/docs/api/classes/llvm/type">Type</a> * &gt; Elements)</td>
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



<p>Declaration at line 254 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/ir/derivedtypes-h">DerivedTypes.h</a>, definition at line 630 of file <a href="/web-llvm/docs/api/files/lib/lib/sandboxir/type-cpp">Type.cpp</a>.</p>

</div>
</div>

### create() {#a0d4dbd83b976a1e591bd54c45ecbb3bf}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<div class="doxyMemberTemplate">template &lt;class... Tys&gt;</div>
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">std::enable_if_t&lt; are_base_of&lt; Type, Tys... &gt;::value, StructType * &gt; llvm::StructType::create (<a href="/web-llvm/docs/api/classes/llvm/stringref">StringRef</a> Name, <a href="/web-llvm/docs/api/classes/llvm/type">Type</a> * elt1, Tys *... elts)</td>
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



<p>Definition at line 257 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/ir/derivedtypes-h">DerivedTypes.h</a>.</p>


<p>References <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/silowercontrolflow-cpp/#a4868c5d81c5ccc98c47aeab6244346a0">assert</a>, <a href="#a82648246c07eb8a33f628eea28cb988c">create</a> and <a href="/web-llvm/docs/api/classes/llvm/type/#a817dfd76b27697e96a20f80f7bb68251">llvm::Type::Type</a>.</p>

</div>
</div>

### get() {#a18fc4545474c6ebb6f7c547f64f4fb31}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">StructType * StructType::get (<a href="/web-llvm/docs/api/classes/llvm/llvmcontext">LLVMContext</a> &amp; Context, <a href="/web-llvm/docs/api/classes/llvm/arrayref">ArrayRef</a>&lt; <a href="/web-llvm/docs/api/classes/llvm/type">Type</a> * &gt; Elements, bool isPacked=false)</td>
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

<p>This static method is the primary way to create a literal <a href="/web-llvm/docs/api/classes/llvm/structtype">StructType</a>.</p>

<p>Declaration at line 263 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/ir/derivedtypes-h">DerivedTypes.h</a>, definition at line 406 of file <a href="/web-llvm/docs/api/files/lib/lib/sandboxir/type-cpp">Type.cpp</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/namespaces/llvm/memtag/#acc2528429e7e0eb707ca49e72bb3ce49">llvm::memtag::alignAndPadAlloca</a>, <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/utils/moduleutils-cpp/#a8508f3dbb1f9429445f50282297b4f9a">appendToGlobalArray</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/directx/lib/target/directx/directxirpasses/pointertypeanalysis-cpp/#a86d26a3e2f2b7996916c7040cd7b40b4">classifyConstantWithOpaquePtr</a>, <a href="/web-llvm/docs/api/files/lib/lib/codegen/lib/codegen/globalisel/legalizerhelper-cpp/#aa386a0afb3210b56c30181f93a434ed3">createAtomicLibcall</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/directx/dxilresourceaccess-cpp/#a55693c3374f66a0794daf3c1dbd00974">createRawLoad</a>, <a href="/web-llvm/docs/api/classes/llvm/openmpirbuilder/#a0af3c7a02c1325c04c59f857604bd4f3">llvm::OpenMPIRBuilder::createTask</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/directx/dxilresourceaccess-cpp/#a83ab43e08fac8e86c8bf333048ed60e2">createTypedBufferLoad</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/directx/dxilresourceaccess-cpp/#ab8ffe62be4273e6e7903125e60943b0d">createTypedBufferStore</a>, <a href="/web-llvm/docs/api/classes/anonymous-pgoctxproflowering-cpp-/ctxinstrumentationlowerer/#a52c340457da98320b6872f2c0ccbae1b">anonymous{PGOCtxProfLowering.cpp}::CtxInstrumentationLowerer::CtxInstrumentationLowerer</a>, <a href="/web-llvm/docs/api/files/lib/lib/ir/intrinsics-cpp/#ad2818cfb16c332aba0ca0ae99d9e40a7">DecodeFixedType</a>, <a href="/web-llvm/docs/api/classes/anonymous-sjljehprepare-cpp-/sjljehprepareimpl/#a046c6262fc6fc6743bf539c87761083f">anonymous{SjLjEHPrepare.cpp}::SjLjEHPrepareImpl::doInitialization</a>, <a href="/web-llvm/docs/api/classes/anonymous-wasmehprepare-cpp-/wasmehprepare/#a9c2e59efe190445d435773ae019b4bd0">anonymous{WasmEHPrepare.cpp}::WasmEHPrepare::doInitialization</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#ad721b230836c9430afd9a392db0c7c5a">llvm::emitHotColdSizeReturningNew</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#adf8c11d60a5385f70c3a140c03f136e4">llvm::emitHotColdSizeReturningNewAligned</a>, <a href="#af335143f4a0fb6ac98d6102219f9795a">get</a>, <a href="/web-llvm/docs/api/classes/llvm/constantexpr/#a0af04c89840d424b7b33ae71d7c8cd28">llvm::ConstantExpr::getAlignOf</a>, <a href="/web-llvm/docs/api/structs/anonymous-memorysanitizer-cpp-/memorysanitizervisitor/#a03dd63ac617c1242b7694a4b0ae4ed25">anonymous{MemorySanitizer.cpp}::MemorySanitizerVisitor::getShadowTy</a>, <a href="/web-llvm/docs/api/classes/llvm/constantstruct/#ab836b949b176d53b81b27de4e1f19f10">llvm::ConstantStruct::getTypeForElements</a>, <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/scalar/sroa-cpp/#ad866ad1da941867a398da262103469b1">getTypePartition</a>, <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/utils/simplifylibcalls-cpp/#a24da6451c0e494831c85fa96cb572c9a">insertSinCosCall</a>, <a href="/web-llvm/docs/api/classes/llvm/type/#a2ff127c9924cd3337080c4445c324aea">llvm::Type::isScalableTy</a>, <a href="/web-llvm/docs/api/files/lib/lib/analysis/targetlibraryinfo-cpp/#abb3e0c28998ff9684b75e9efa0697919">isValidProtoForSizeReturningNew</a>, <a href="/web-llvm/docs/api/classes/llvm/armlegalizerinfo/#a2aeed55e4456de4086b3592eb92dc2e2">llvm::ARMLegalizerInfo::legalizeCustom</a>, <a href="/web-llvm/docs/api/groups/llvmccoretypestruct/#gaff2af74740a22f7d18701f0d8c3e5a6f">LLVMStructTypeInContext</a>, <a href="/web-llvm/docs/api/classes/llvm/riscvtargetlowering/#adcc5d5714e94674aee99aacd991d2b4a">llvm::RISCVTargetLowering::lowerDeinterleaveIntrinsicToLoad</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/x86/x86isellowering-cpp/#a51e11fac59331e5e9704295214a2d5ee">LowerFSINCOS</a>, <a href="/web-llvm/docs/api/classes/anonymous-pgoctxproflowering-cpp-/ctxinstrumentationlowerer/#a0106bab2d4d5ef7149415e2af1dfb180">anonymous{PGOCtxProfLowering.cpp}::CtxInstrumentationLowerer::lowerFunction</a>, <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/coroutines/corocleanup-cpp/#a77b6227cc85a61fcbce08b8387c575a9">lowerSubFn</a>, <a href="/web-llvm/docs/api/classes/llvm/escapeenumerator/#ac63ecd195310b8a31b445bb613028893">llvm::EscapeEnumerator::Next</a>, <a href="/web-llvm/docs/api/classes/anonymous-amdgpulowerbufferfatpointers-cpp-/bufferfatptrtostructtypemap/#a520d2b97d6b2eb0958cc182161938cd1">anonymous{AMDGPULowerBufferFatPointers.cpp}::BufferFatPtrToStructTypeMap::remapScalar</a>, <a href="/web-llvm/docs/api/classes/anonymous-amdgpulowerbufferfatpointers-cpp-/bufferfatptrtostructtypemap/#a0b50be89487f7186a5eb7ff1bc82efc0">anonymous{AMDGPULowerBufferFatPointers.cpp}::BufferFatPtrToStructTypeMap::remapVector</a>, <a href="/web-llvm/docs/api/classes/llvm/wasmehpreparepass/#a2cbdc4bc7c2c1dc4c48d00376ab271a1">llvm::WasmEHPreparePass::run</a>, <a href="/web-llvm/docs/api/classes/anonymous-webassemblyloweremscriptenehsjlj-cpp-/webassemblyloweremscriptenehsjlj/#a4e54683754f6664c17d470ae3a097486">anonymous{WebAssemblyLowerEmscriptenEHSjLj.cpp}::WebAssemblyLowerEmscriptenEHSjLj::runOnModule</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#af3d7a362fea3dd362c790529f2afcbfa">llvm::toScalarizedStructTy</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a77e211e8fb596ed21bb29f80aeacc211">llvm::toVectorizedStructTy</a> and <a href="/web-llvm/docs/api/namespaces/llvm/#a95b7e7311ec52352ada27699c3c9c470">llvm::UpgradeGlobalVariable</a>.</p>

</div>
</div>

### get() {#ab49b84f1bf1a79a51d9616ab47b79f71}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">StructType * StructType::get (<a href="/web-llvm/docs/api/classes/llvm/llvmcontext">LLVMContext</a> &amp; Context, bool isPacked=false)</td>
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

<p>Create an empty structure type.</p>

<p>Declaration at line 267 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/ir/derivedtypes-h">DerivedTypes.h</a>, definition at line 619 of file <a href="/web-llvm/docs/api/files/lib/lib/sandboxir/type-cpp">Type.cpp</a>.</p>

</div>
</div>

### get() {#af335143f4a0fb6ac98d6102219f9795a}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<div class="doxyMemberTemplate">template &lt;class... Tys&gt;</div>
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">std::enable_if_t&lt; are_base_of&lt; Type, Tys... &gt;::value, StructType * &gt; llvm::StructType::get (<a href="/web-llvm/docs/api/classes/llvm/type">Type</a> * elt1, Tys *... elts)</td>
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

<p>This static method is a convenience method for creating structure types by specifying the elements as arguments.</p>


<p>Note that this method always returns a non-packed struct, and requires at least one element type.</p>


<p>Definition at line 274 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/ir/derivedtypes-h">DerivedTypes.h</a>.</p>


<p>References <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/silowercontrolflow-cpp/#a4868c5d81c5ccc98c47aeab6244346a0">assert</a>, <a href="#a18fc4545474c6ebb6f7c547f64f4fb31">get</a>, <a href="/web-llvm/docs/api/classes/llvm/type/#a909eca4ba9e5eefc203c8e3770bdab25">llvm::Type::getContext</a> and <a href="/web-llvm/docs/api/classes/llvm/type/#a817dfd76b27697e96a20f80f7bb68251">llvm::Type::Type</a>.</p>

</div>
</div>

### getTypeByName() {#a75a89f1513d9f9bdcf0366a436ca43b5}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">StructType * StructType::getTypeByName (<a href="/web-llvm/docs/api/classes/llvm/llvmcontext">LLVMContext</a> &amp; C, <a href="/web-llvm/docs/api/classes/llvm/stringref">StringRef</a> Name)</td>
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

<p>Return the type with the specified name, or null if there is none by that name.</p>

<p>Declaration at line 282 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/ir/derivedtypes-h">DerivedTypes.h</a>, definition at line 731 of file <a href="/web-llvm/docs/api/files/lib/lib/sandboxir/type-cpp">Type.cpp</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/namespaces/anonymous-offloadwrapper-cpp-/#a604c924e11ca5df4475086acc8db0f4e">anonymous{OffloadWrapper.cpp}::getBinDescTy</a>, <a href="/web-llvm/docs/api/namespaces/anonymous-offloadwrapper-cpp-/#a8ba7541c9160f54941d8b6029ec4d2ae">anonymous{OffloadWrapper.cpp}::getDeviceImageTy</a>, <a href="/web-llvm/docs/api/namespaces/llvm/offloading/#a6955657cb7867972e6b8f046e9cf5a02">llvm::offloading::getEntryTy</a>, <a href="/web-llvm/docs/api/namespaces/anonymous-offloadwrapper-cpp-/#ad046f69ab8abe8d2605589e6daf42612">anonymous{OffloadWrapper.cpp}::getFatbinWrapperTy</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/directx/dxilopbuilder-cpp/#a9b36c3934c9c2e8a2dc9fcb4cdee876b">getOrCreateStructType</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/directx/dxilopbuilder-cpp/#aff234d51ccd591da6c1332a3d52fbe1e">getResBindType</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/directx/dxilopbuilder-cpp/#af69be60078714a34c733e198b5aab9af">getResPropsType</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/directx/dxilopbuilder-cpp/#a5f6846040fc48f21e5969492bbb88fdc">getSplitDoubleType</a>, <a href="/web-llvm/docs/api/groups/llvmccoremodule/#ga29066e749e093fba6fedb5efa0962177">LLVMGetTypeByName</a> and <a href="/web-llvm/docs/api/groups/llvmccorecontext/#gaab9d54afadb0989f7835e4c9306cb516">LLVMGetTypeByName2</a>.</p>

</div>
</div>

### isValidElementType() {#a85475695bba20ea9883c49ce9f890a8a}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool StructType::isValidElementType (<a href="/web-llvm/docs/api/classes/llvm/type">Type</a> * ElemTy)</td>
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

<p>Return true if the specified type is valid as a element type.</p>

<p>Declaration at line 350 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/ir/derivedtypes-h">DerivedTypes.h</a>, definition at line 696 of file <a href="/web-llvm/docs/api/files/lib/lib/sandboxir/type-cpp">Type.cpp</a>.</p>

</div>
</div>

</div>

<hr/>

The documentation for this class was generated from the following files:

<ul>
<li><a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/ir/derivedtypes-h">DerivedTypes.h</a></li>
<li><a href="/web-llvm/docs/api/files/lib/lib/sandboxir/type-cpp">Type.cpp</a></li>
</ul>

<hr/>

<p class="doxyGeneratedBy">Generated via <a href="https://github.com/xpack/doxygen2docusaurus">doxygen2docusaurus</a> by <a href="https://www.doxygen.nl">Doxygen</a> 1.15.0.</p>

</div>
