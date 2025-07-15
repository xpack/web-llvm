---

# DO NOT EDIT!
# Automatically generated via doxygen2docusaurus by Doxygen.

slug: /api/classes/llvm/undefvalue
custom_edit_url: null
toc_max_heading_level: 4
keywords:
  - doxygen
  - reference
  - class

---

<div class="doxyPage">

# The `UndefValue` Class Reference

<p>'undef' values are things that do not have specified contents. <a href="#details">More...</a></p>

## Declaration

<div class="doxyDeclaration">
class llvm::UndefValue { ... }
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/poisonvalue">PoisonValue</a></td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>In order to facilitate speculative execution, many instructions do not invoke immediate undefined behavior when provided with illegal operands, and return a poison value instead. <a href="/web-llvm/docs/api/classes/llvm/poisonvalue/#details">More...</a></p>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a3a383ca68aee92c82e2a3b2b05734ea9">UndefValue</a> (const UndefValue &amp;)=delete</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a8521a5b97189c7afb085145667e42891">UndefValue</a> (Type *T, ValueTy vty)</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a4c7b693ae173afe8da954bdf01c2b52e">UndefValue</a> (Type *T)</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/undefvalue">UndefValue</a> *</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ac1a71ad4196bd3e400699fa02e152958">getSequentialElement</a> () const</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>If this Undef has array or vector type, return a undef with the right element type. <a href="#ac1a71ad4196bd3e400699fa02e152958">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/undefvalue">UndefValue</a> *</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a28582f3720134b47468804fff5ac5368">getStructElement</a> (unsigned Elt) const</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>If this undef has struct type, return a undef with the right element type for the specified element. <a href="#a28582f3720134b47468804fff5ac5368">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/undefvalue">UndefValue</a> *</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a081de928f8254a95de78630b968e5b4b">getElementValue</a> (Constant *C) const</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Return an undef of the right value for the specified GEP index if we can, otherwise return null (e.g. <a href="#a081de928f8254a95de78630b968e5b4b">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/undefvalue">UndefValue</a> *</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a0fd8c8463763315a08157f4f1ae5ddeb">getElementValue</a> (unsigned Idx) const</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Return an undef of the right value for the specified GEP index. <a href="#a0fd8c8463763315a08157f4f1ae5ddeb">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">unsigned</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a6854d18eda81a9867ab5b4aefb844db0">getNumElements</a> () const</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Return the number of elements in the array, vector, or struct. <a href="#a6854d18eda81a9867ab5b4aefb844db0">More...</a></p>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a31c48d27a157776bd7825f60f84014a7">destroyConstantImpl</a> ()</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Remove the constant from the constant table. <a href="#a31c48d27a157776bd7825f60f84014a7">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

</table>

## Public Static Functions Index

<table class="doxyMembersIndex">

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">static <a href="/web-llvm/docs/api/classes/llvm/undefvalue">UndefValue</a> *</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a4ae5ff22b700a42bcc5d889233721335">get</a> (Type *T)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Static factory methods - Return an 'undef' object of the specified type. <a href="#a4ae5ff22b700a42bcc5d889233721335">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">static bool</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a72f33f26b467287ba52d3adf82b7afb5">classof</a> (const Value *V)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Methods for support type inquiry through isa, cast, and dyn_cast: <a href="#a72f33f26b467287ba52d3adf82b7afb5">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

</table>

## Description {#details}

<p>'undef' values are things that do not have specified contents.</p>


<p>These are used for a variety of purposes, including global variable initializers and operands to instructions. 'undef' values can occur with any first-class type.</p>


<p>Undef values aren't exactly constants; if they have multiple uses, they can appear to have different bit patterns at each use. See LangRef.html#undefvalues for details.</p>


<p>Definition at line 1412 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/ir/constants-h">Constants.h</a>.</p>


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


<p>Definition at line 1413 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/ir/constants-h">Constants.h</a>.</p>


<p>References <a href="#a5bd16c2fbe755cda66b18d56761038ea">Constant</a>, <a href="/web-llvm/docs/api/classes/llvm/constantdata/#ade3ec5a4a86ffd069698509c87b6a604">llvm::ConstantData::ConstantData</a> and <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/mips/mips16isellowering-cpp/#a0acb682b8260ab1c60b918599864e2e5">T</a>.</p>


<p>Referenced by <a href="#a5bd16c2fbe755cda66b18d56761038ea">Constant</a>, <a href="#a081de928f8254a95de78630b968e5b4b">getElementValue</a> and <a href="#a3a383ca68aee92c82e2a3b2b05734ea9">UndefValue</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Public Constructors

### UndefValue() {#a3a383ca68aee92c82e2a3b2b05734ea9}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">llvm::UndefValue::UndefValue (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/undefvalue">UndefValue</a> &amp;)</td>
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



<p>Definition at line 1423 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/ir/constants-h">Constants.h</a>.</p>


<p>References <a href="/web-llvm/docs/api/namespaces/llvm/callingconv/#ac6aa1387c4375260e2468eb5a77fdb4cafd841a49aec1539bc88abc8ff9e170fb">llvm::CallingConv::C</a>, <a href="#a5bd16c2fbe755cda66b18d56761038ea">Constant</a>, <a href="#a081de928f8254a95de78630b968e5b4b">getElementValue</a>, <a href="#ac1a71ad4196bd3e400699fa02e152958">getSequentialElement</a>, <a href="#a28582f3720134b47468804fff5ac5368">getStructElement</a> and <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/mips/mips16isellowering-cpp/#a0acb682b8260ab1c60b918599864e2e5">T</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Protected Constructors

### UndefValue() {#a8521a5b97189c7afb085145667e42891}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">llvm::UndefValue::UndefValue (<a href="/web-llvm/docs/api/classes/llvm/type">Type</a> * T, <a href="/web-llvm/docs/api/classes/llvm/value/#af6d11b38374c4f9e6ba3a6407da2dee0">ValueTy</a> vty)</td>
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



<p>Definition at line 1420 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/ir/constants-h">Constants.h</a>.</p>


<p>References <a href="/web-llvm/docs/api/classes/llvm/constantdata/#ade3ec5a4a86ffd069698509c87b6a604">llvm::ConstantData::ConstantData</a> and <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/mips/mips16isellowering-cpp/#a0acb682b8260ab1c60b918599864e2e5">T</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Private Constructors

### UndefValue() {#a4c7b693ae173afe8da954bdf01c2b52e}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">llvm::UndefValue::UndefValue (<a href="/web-llvm/docs/api/classes/llvm/type">Type</a> * T)</td>
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



<p>Definition at line 1415 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/ir/constants-h">Constants.h</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Public Member Functions

### getElementValue() {#a081de928f8254a95de78630b968e5b4b}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">UndefValue * UndefValue::getElementValue (<a href="/web-llvm/docs/api/classes/llvm/constant">Constant</a> * C)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Return an undef of the right value for the specified GEP index if we can, otherwise return null (e.g.</p>


<p>if C is a <a href="/web-llvm/docs/api/classes/llvm/constantexpr">ConstantExpr</a>).</p>


<p>Declaration at line 1438 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/ir/constants-h">Constants.h</a>, definition at line 1177 of file <a href="/web-llvm/docs/api/files/lib/lib/ir/constants-cpp">Constants.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/namespaces/llvm/callingconv/#ac6aa1387c4375260e2468eb5a77fdb4cafd841a49aec1539bc88abc8ff9e170fb">llvm::CallingConv::C</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#ac4fc845f5ed92de63cd4474f128f5fc5">llvm::cast</a>, <a href="#a5bd16c2fbe755cda66b18d56761038ea">Constant</a>, <a href="#ac1a71ad4196bd3e400699fa02e152958">getSequentialElement</a>, <a href="#a28582f3720134b47468804fff5ac5368">getStructElement</a>, <a href="/web-llvm/docs/api/classes/llvm/value/#a0344a49526443edf90cc0aef3abd3337">llvm::Value::getType</a> and <a href="/web-llvm/docs/api/namespaces/llvm/#a92ca992e52dddc420f4b069cae06dfbe">llvm::isa</a>.</p>


<p>Referenced by <a href="#a3a383ca68aee92c82e2a3b2b05734ea9">UndefValue</a>.</p>

</div>
</div>

### getElementValue() {#a0fd8c8463763315a08157f4f1ae5ddeb}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">UndefValue * UndefValue::getElementValue (unsigned Idx)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Return an undef of the right value for the specified GEP index.</p>

<p>Declaration at line 1441 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/ir/constants-h">Constants.h</a>, definition at line 1183 of file <a href="/web-llvm/docs/api/files/lib/lib/ir/constants-cpp">Constants.cpp</a>.</p>


<p>References <a href="#ac1a71ad4196bd3e400699fa02e152958">getSequentialElement</a>, <a href="#a28582f3720134b47468804fff5ac5368">getStructElement</a>, <a href="/web-llvm/docs/api/classes/llvm/value/#a0344a49526443edf90cc0aef3abd3337">llvm::Value::getType</a> and <a href="/web-llvm/docs/api/namespaces/llvm/#a92ca992e52dddc420f4b069cae06dfbe">llvm::isa</a>.</p>

</div>
</div>

### getNumElements() {#a6854d18eda81a9867ab5b4aefb844db0}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">unsigned UndefValue::getNumElements ()</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Return the number of elements in the array, vector, or struct.</p>

<p>Declaration at line 1444 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/ir/constants-h">Constants.h</a>, definition at line 1189 of file <a href="/web-llvm/docs/api/files/lib/lib/ir/constants-cpp">Constants.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/namespaces/llvm/#ac4fc845f5ed92de63cd4474f128f5fc5">llvm::cast</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a22eeee01734061ac1b31ccd994c49eef">llvm::dyn_cast</a> and <a href="/web-llvm/docs/api/classes/llvm/value/#a0344a49526443edf90cc0aef3abd3337">llvm::Value::getType</a>.</p>

</div>
</div>

### getSequentialElement() {#ac1a71ad4196bd3e400699fa02e152958}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">UndefValue * UndefValue::getSequentialElement ()</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>If this Undef has array or vector type, return a undef with the right element type.</p>

<p>Declaration at line 1430 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/ir/constants-h">Constants.h</a>, definition at line 1167 of file <a href="/web-llvm/docs/api/files/lib/lib/ir/constants-cpp">Constants.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/namespaces/llvm/#ac4fc845f5ed92de63cd4474f128f5fc5">llvm::cast</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a22eeee01734061ac1b31ccd994c49eef">llvm::dyn_cast</a>, <a href="#a4ae5ff22b700a42bcc5d889233721335">get</a> and <a href="/web-llvm/docs/api/classes/llvm/value/#a0344a49526443edf90cc0aef3abd3337">llvm::Value::getType</a>.</p>


<p>Referenced by <a href="#a081de928f8254a95de78630b968e5b4b">getElementValue</a>, <a href="#a0fd8c8463763315a08157f4f1ae5ddeb">getElementValue</a> and <a href="#a3a383ca68aee92c82e2a3b2b05734ea9">UndefValue</a>.</p>

</div>
</div>

### getStructElement() {#a28582f3720134b47468804fff5ac5368}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">UndefValue * UndefValue::getStructElement (unsigned Elt)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>If this undef has struct type, return a undef with the right element type for the specified element.</p>

<p>Declaration at line 1434 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/ir/constants-h">Constants.h</a>, definition at line 1173 of file <a href="/web-llvm/docs/api/files/lib/lib/ir/constants-cpp">Constants.cpp</a>.</p>


<p>References <a href="#a4ae5ff22b700a42bcc5d889233721335">get</a> and <a href="/web-llvm/docs/api/classes/llvm/value/#a0344a49526443edf90cc0aef3abd3337">llvm::Value::getType</a>.</p>


<p>Referenced by <a href="#a081de928f8254a95de78630b968e5b4b">getElementValue</a>, <a href="#a0fd8c8463763315a08157f4f1ae5ddeb">getElementValue</a> and <a href="#a3a383ca68aee92c82e2a3b2b05734ea9">UndefValue</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Private Member Functions

### destroyConstantImpl() {#a31c48d27a157776bd7825f60f84014a7}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void UndefValue::destroyConstantImpl ()</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Remove the constant from the constant table.</p>

<p>Declaration at line 1417 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/ir/constants-h">Constants.h</a>, definition at line 1868 of file <a href="/web-llvm/docs/api/files/lib/lib/ir/constants-cpp">Constants.cpp</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Public Static Functions

### classof() {#a72f33f26b467287ba52d3adf82b7afb5}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool llvm::UndefValue::classof (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/value">Value</a> * V)</td>
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

<p>Definition at line 1447 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/ir/constants-h">Constants.h</a>.</p>

</div>
</div>

### get() {#a4ae5ff22b700a42bcc5d889233721335}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">UndefValue * UndefValue::get (<a href="/web-llvm/docs/api/classes/llvm/type">Type</a> * T)</td>
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

<p>Static factory methods - Return an 'undef' object of the specified type.</p>

<p>Declaration at line 1426 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/ir/constants-h">Constants.h</a>, definition at line 1859 of file <a href="/web-llvm/docs/api/files/lib/lib/ir/constants-cpp">Constants.cpp</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/structs/anonymous-attributorattributes-cpp-/aapotentialvaluesimpl/#a135bd9f6645b2fba9c7652cbd7b8a157">anonymous{AttributorAttributes.cpp}::AAPotentialValuesImpl::addValue</a>, <a href="/web-llvm/docs/api/classes/anonymous-hexagonvectorcombine-cpp-/hexagonvectorcombine/#a3d42f23852edcd240ef3a605fdc2bcec">anonymous{HexagonVectorCombine.cpp}::HexagonVectorCombine::concat</a>, <a href="/web-llvm/docs/api/namespaces/anonymous-constantfolding-cpp-/#a48ef6764a965598939c3ecf43eeb9fb0">anonymous{ConstantFolding.cpp}::ConstantFoldAMDGCNPermIntrinsic</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#af6674e64f01f197cffff55abcc6d2050">llvm::ConstantFoldBinaryInstruction</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#ad797efb6c6fbbb2038d5ed8f8379561f">llvm::ConstantFoldCastInstruction</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a293a0cb64e182e693cdd406f8da7ced5">llvm::ConstantFoldCompareInstruction</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a9f6c692bb79cca65ae3097ddd4c47e69">llvm::ConstantFoldExtractElementInstruction</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a491cbe61681e7c63ac7d01ce209a4682">llvm::ConstantFoldGetElementPtr</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#ab6be6270337c6f7620007555247401ce">llvm::ConstantFoldInstruction</a>, <a href="/web-llvm/docs/api/namespaces/anonymous-constantfolding-cpp-/#a72190dad796891a1a5a59d64044000dc">anonymous{ConstantFolding.cpp}::ConstantFoldIntrinsicCall2</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a65bb0005c2f40b94623bae2e9a51fe48">llvm::ConstantFoldLoadFromUniformValue</a>, <a href="/web-llvm/docs/api/namespaces/anonymous-constantfolding-cpp-/#a505a295564c761e2006b8e48647f6f7d">anonymous{ConstantFolding.cpp}::ConstantFoldScalarCall3</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#addd1c6bc523b9a0eb56167da95dc5156">llvm::ConstantFoldShuffleVectorInstruction</a>, <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/instcombine/instcombinevectorops-cpp/#a06358c30f3e98d9e57f4ae9162f33c72">evaluateInDifferentElementOrder</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/directx/dxilintrinsicexpansion-cpp/#a505ddaadef479f2d0c0810c203000eaa">expandCrossIntrinsic</a>, <a href="/web-llvm/docs/api/structs/anonymous-dataflowsanitizer-cpp-/dfsanfunction/#af512bce8ac0099600eaf443bde3d975f">anonymous{DataFlowSanitizer.cpp}::DFSanFunction::expandFromPrimitiveShadow</a>, <a href="/web-llvm/docs/api/namespaces/anonymous-constantfolding-cpp-/#aa5ea18feb56580024a1693b1f98fb3f6">anonymous{ConstantFolding.cpp}::FoldBitCast</a>, <a href="/web-llvm/docs/api/classes/boupslp/shufflecostestimator/#a7d3b40cff3ff8c00007cf9a3f0d785f1">llvm::slpvectorizer::BoUpSLP::ShuffleCostEstimator::gather</a>, <a href="/web-llvm/docs/api/classes/llvm/constantstruct/#a54fcfa620deb80373f489ba2fdad7643">llvm::ConstantStruct::get</a>, <a href="/web-llvm/docs/api/classes/llvm/sandboxir/undefvalue/#a44c447df510d12200660b17520fc0972">llvm::sandboxir::UndefValue::get</a>, <a href="/web-llvm/docs/api/structs/llvm/aapotentialconstantvalues/#ac6c45f02f71621808dd33da72d73cb00">llvm::AAPotentialConstantValues::getAssumedConstant</a>, <a href="/web-llvm/docs/api/classes/llvm/gcrelocateinst/#ab825396e92860b35839338f7f1df75ad">llvm::GCRelocateInst::getBasePtr</a>, <a href="/web-llvm/docs/api/classes/llvm/sccpinstvisitor/#a77590453ed3ac517979894f1f40bca12">llvm::SCCPInstVisitor::getConstantOrNull</a>, <a href="/web-llvm/docs/api/classes/llvm/executionengine/#a0a724dad58a66f883d1b88115237ae00">llvm::ExecutionEngine::getConstantValue</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/x86/x86isellowering-cpp/#a1abbecb57e09bf906ab1503722015802">getConstantVector</a>, <a href="/web-llvm/docs/api/classes/llvm/gcrelocateinst/#ae587391ac557593d998dbca4e62f0dab">llvm::GCRelocateInst::getDerivedPtr</a>, <a href="/web-llvm/docs/api/namespaces/llvm/aa/#abdc024165477822f664fda55551f8a66">llvm::AA::getInitialValueForObj</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a108b6e33f153eda5019d322f0ac909b0">llvm::getInitialValueOfAllocation</a>, <a href="/web-llvm/docs/api/classes/llvm/spirvglobalregistry/#a35c2ba2ad91e2fe027f8f64e92a7502f">llvm::SPIRVGlobalRegistry::getOrCreateUndef</a>, <a href="#ac1a71ad4196bd3e400699fa02e152958">getSequentialElement</a>, <a href="/web-llvm/docs/api/structs/llvm/aapotentialvalues/#afbaf43cc6d56847d8f8202623b7f61e7">llvm::AAPotentialValues::getSingleValue</a>, <a href="/web-llvm/docs/api/classes/llvm/constantvector/#aa3b241b35b0039b413faf1ef4e873eb7">llvm::ConstantVector::getSplat</a>, <a href="/web-llvm/docs/api/classes/llvm/gcprojectioninst/#a6cffcfabac72ca61185ea24c1208b937">llvm::GCProjectionInst::getStatepoint</a>, <a href="#a28582f3720134b47468804fff5ac5368">getStructElement</a>, <a href="/web-llvm/docs/api/files/lib/lib/bitcode/lib/bitcode/reader/metadataloader-cpp/#a3addcf81365bceaf72c4f59bfdd16ba5">getValueFwdRef</a>, <a href="/web-llvm/docs/api/classes/basicloadandstorepromoter/#acdcd864d0eb9e68ec66a4350b1390e26">BasicLoadAndStorePromoter::getValueToUseForAlloca</a>, <a href="/web-llvm/docs/api/namespaces/llvm/aa/#af967a81762eaaf67f292abee4a00180c">llvm::AA::getWithType</a>, <a href="/web-llvm/docs/api/structs/anonymous-attributorattributes-cpp-/aapotentialvaluesfloating/#a9dfa7d879ffc886a8014f1c9714ec166">anonymous{AttributorAttributes.cpp}::AAPotentialValuesFloating::handleCmp</a>, <a href="/web-llvm/docs/api/files/lib/lib/codegen/lib/codegen/selectiondag/selectiondagbuilder-cpp/#a4e84a47e3ca9c1684a752533e2881cd7">handleDanglingVariadicDebugInfo</a>, <a href="/web-llvm/docs/api/classes/anonymous-hexagonvectorcombine-cpp-/hexagonvectorcombine/#a8a0358fb6de2fdee39a22ff89eae26d1">anonymous{HexagonVectorCombine.cpp}::HexagonVectorCombine::insertb</a>, <a href="/web-llvm/docs/api/structs/anonymous-openmpopt-cpp-/aakernelinfofunction/#ad822c761168baefbdcd6c0d9fd928a6d">anonymous{OpenMPOpt.cpp}::AAKernelInfoFunction::insertInstructionGuardsHelper</a>, <a href="/web-llvm/docs/api/classes/llvm/gcnttiimpl/#ae3d1835a72f8f0ba85ace9e2c0fbfc96">llvm::GCNTTIImpl::instCombineIntrinsic</a>, <a href="/web-llvm/docs/api/classes/llvm/ppcttiimpl/#a04dad23556e58f793c9a508a1a2d9aa5">llvm::PPCTTIImpl::instCombineIntrinsic</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64targettransforminfo-cpp/#ac798b3bd7ffd81421fe4b75b8af36c7c">instCombineSVEAllOrNoActiveUnary</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#acab8f775ddc87695d750e4838231b3ba">llvm::isBytewiseValue</a>, <a href="/web-llvm/docs/api/groups/llvmccorevalueconstant/#ga15e12ed1ce1622c0d571eea68acd8bb4">LLVMGetUndef</a>, <a href="/web-llvm/docs/api/classes/anonymous-dxiloplowering-cpp-/oplowerer/#a4275af81cdeb1801deeae02ea2a0fb3b">anonymous{DXILOpLowering.cpp}::OpLowerer::lowerBufferStore</a>, <a href="/web-llvm/docs/api/classes/llvm/aarch64targetlowering/#aa4094e6b2a8203e5c8b67ecf186d51a9">llvm::AArch64TargetLowering::lowerInterleavedStore</a>, <a href="/web-llvm/docs/api/classes/anonymous-dxiloplowering-cpp-/oplowerer/#a70502c89919d53c74320c78b78d5c282">anonymous{DXILOpLowering.cpp}::OpLowerer::lowerTypedBufferLoad</a>, <a href="/web-llvm/docs/api/namespaces/llvm/fuzzerop/#a5172beb0382e24b2305c8bc0e46ee1f4">llvm::fuzzerop::makeConstantsWithType</a>, <a href="/web-llvm/docs/api/structs/anonymous-attributorattributes-cpp-/aaisdeadcallsiteargument/#a5d6050f7be56f61036d2d194ac7f66f8">anonymous{AttributorAttributes.cpp}::AAIsDeadCallSiteArgument::manifest</a>, <a href="/web-llvm/docs/api/structs/anonymous-attributorattributes-cpp-/aaisdeadreturned/#a5fbd0b238ec5abc8ab5dbc065b002c7a">anonymous{AttributorAttributes.cpp}::AAIsDeadReturned::manifest</a>, <a href="/web-llvm/docs/api/structs/anonymous-attributorattributes-cpp-/aavaluesimplifyimpl/#a469217e1991252d89a236638f25c5293">anonymous{AttributorAttributes.cpp}::AAValueSimplifyImpl::manifestReplacementValue</a>, <a href="/web-llvm/docs/api/classes/anonymous-valuemapper-cpp-/mapper/#a7d5502a6047fb27d6c33ea2820608c2c">anonymous{ValueMapper.cpp}::Mapper::mapValue</a>, <a href="/web-llvm/docs/api/classes/llvm/constant/#a31dbd9cf336966a863e37c5653b6c134">llvm::Constant::mergeUndefsWith</a>, <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/ipo/globalopt-cpp/#a31b17b67a86749cfd99e97041c819791">OptimizeGlobalAddressOfAllocation</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/amdgpuimageintrinsicoptimizer-cpp/#a0751e03131065414fffaa087c9e084cb">optimizeSection</a>, <a href="/web-llvm/docs/api/classes/llvm/jumpthreadingpass/#a071cd98d76a1c63f215ad16388bfdfe2">llvm::JumpThreadingPass::processBranchOnXOR</a>, <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/utils/promotememorytoregister-cpp/#a6952450f0726bd9c26d303743522e227">promoteSingleBlockAlloca</a>, <a href="/web-llvm/docs/api/classes/anonymous-dxiloplowering-cpp-/oplowerer/#a583a2a6c920de4695807c6ad35c5e35d">anonymous{DXILOpLowering.cpp}::OpLowerer::replaceResRetUses</a>, <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/utils/local-cpp/#a705c6c2b8e570441356edb8db2dd8ddb">replaceUndefValuesInPhi</a>, <a href="/web-llvm/docs/api/classes/llvm/selectiondagbuilder/#ab898c0fc6a2159b032a398271add3927">llvm::SelectionDAGBuilder::resolveDanglingDebugInfo</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a70727db13f5962a76e5dd0ffd21ecd07">llvm::returnTypeIsEligibleForTailCall</a>, <a href="/web-llvm/docs/api/structs/anonymous-promotememorytoregister-cpp-/promotemem2reg/#a31d32412508ee492e69d8695f88e6dcf">anonymous{PromoteMemoryToRegister.cpp}::PromoteMem2Reg::run</a>, <a href="/web-llvm/docs/api/classes/spirvstripconvergentintrinsics/#a4d2b7f7dd9786ee2f5eba35539cbd397">SPIRVStripConvergentIntrinsics::runOnFunction</a>, <a href="/web-llvm/docs/api/classes/llvm/replaceablemetadataimpl/#a26887fb6f8b3127e6b28c2075dacbc11">llvm::ReplaceableMetadataImpl::SalvageDebugInfo</a>, <a href="/web-llvm/docs/api/classes/llvm/selectiondagbuilder/#a8cf671ed90e3e80717aaa6318b24794c">llvm::SelectionDAGBuilder::salvageUnresolvedDbgValue</a>, <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/instcombine/instcombinecasts-cpp/#a77aac577d89abc9411adfdf918d7d539">shrinkInsertElt</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#ab720ac4c86a5f16a755b1e5cd0d32c80">llvm::simplifyBinaryIntrinsic</a>, <a href="/web-llvm/docs/api/classes/llvm/instcombinerimpl/#a7e500d9f027b07d62374f0cee5d56724">llvm::InstCombinerImpl::SimplifyDemandedBits</a>, <a href="/web-llvm/docs/api/classes/llvm/x86targetlowering/#a5681faab09fa140f67d47577193f2665">llvm::X86TargetLowering::SimplifyDemandedVectorEltsForTargetShuffle</a>, <a href="/web-llvm/docs/api/files/lib/lib/analysis/instructionsimplify-cpp/#a48ebda753879b3d5d55fa0e1566b5439">simplifyExtractElementInst</a>, <a href="/web-llvm/docs/api/files/lib/lib/analysis/instructionsimplify-cpp/#aab8aaa8e44e0609f7d3e9ae822f11f7e">simplifyGEPInst</a>, <a href="/web-llvm/docs/api/files/lib/lib/analysis/instructionsimplify-cpp/#a47a81cb5e93cfda95b1de100dd5b9919">simplifyICmpInst</a>, <a href="/web-llvm/docs/api/files/lib/lib/analysis/instructionsimplify-cpp/#a554988e4897106ec290097646fd1a84e">simplifyIntrinsic</a>, <a href="/web-llvm/docs/api/files/lib/lib/analysis/instructionsimplify-cpp/#a308de6b87d4d431477642d086b268a7c">simplifyPHINode</a>, <a href="/web-llvm/docs/api/files/lib/lib/analysis/instructionsimplify-cpp/#a0e278bb318fd700a9c8d4f4a7c8caba9">simplifySubInst</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/x86/x86instcombineintrinsic-cpp/#adbe56869c99b539068e8a442d8738dae">simplifyX86extrq</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/x86/x86instcombineintrinsic-cpp/#a158032a7de947df4dc475c236414f0a2">simplifyX86insertq</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/x86/x86instcombineintrinsic-cpp/#a2784f2480fde374684ff993c8ae92991">simplifyX86pack</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/x86/x86instcombineintrinsic-cpp/#afbcb72ff3dcc4f5818f711ca564b9dc1">simplifyX86varShift</a>, <a href="/web-llvm/docs/api/namespaces/llvm/at/#a5c4090098e3eaedb61973431af4898b1">llvm::at::trackAssignments</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/directx/dxilflattenarrays-cpp/#ac9966bce879b21a4a601daab59e25c97">transformInitializer</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/directx/dxildatascalarization-cpp/#ab9bfb7e130ccc022600bc9c1aea8bba0">transformInitializer</a>, <a href="/web-llvm/docs/api/classes/anonymous-spirvemitintrinsics-cpp-/spirvemitintrinsics/#ac6e0980539d623cb69d94e25d2e52481">anonymous{SPIRVEmitIntrinsics.cpp}::SPIRVEmitIntrinsics::visitCallInst</a>, <a href="/web-llvm/docs/api/classes/llvm/instcombinerimpl/#a687fa4390149f0cb751d8ad89dca6a3c">llvm::InstCombinerImpl::visitInsertElementInst</a>, <a href="/web-llvm/docs/api/classes/anonymous-spirvemitintrinsics-cpp-/spirvemitintrinsics/#ac82cec8662dd4fd79e0903869407274c">anonymous{SPIRVEmitIntrinsics.cpp}::SPIRVEmitIntrinsics::visitInsertValueInst</a>, <a href="/web-llvm/docs/api/classes/anonymous-dataflowsanitizer-cpp-/dfsanvisitor/#a3a5f2e657c4828861cdc11d66c9e0a78">anonymous{DataFlowSanitizer.cpp}::DFSanVisitor::visitPHINode</a> and <a href="/web-llvm/docs/api/classes/llvm/instcombinerimpl/#ad31108b4f7156db7565eadba1285c93a">llvm::InstCombinerImpl::visitShuffleVectorInst</a>.</p>

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

<p class="doxyGeneratedBy">Generated via <a href="https://github.com/xpack/doxygen2docusaurus">doxygen2docusaurus</a> by <a href="https://www.doxygen.nl">Doxygen</a> 1.14.0.</p>

</div>
