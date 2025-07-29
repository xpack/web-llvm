---

# DO NOT EDIT!
# Automatically generated via doxygen2docusaurus by Doxygen.

slug: /api/classes/llvm/constantaggregatezero
custom_edit_url: null
toc_max_heading_level: 4
keywords:
  - doxygen
  - reference
  - class

---

<div class="doxyPage">

# `ConstantAggregateZero` Class

<p>All zero aggregate value. <a href="#details">More...</a></p>

## Declaration

<div class="doxyDeclaration">
class llvm::ConstantAggregateZero { ... }
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a5a8d7187aebeaafac8e3824ec235a11f">ConstantAggregateZero</a> (const ConstantAggregateZero &amp;)=delete</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a344d28bc035af46b0c69b75747633b7d">ConstantAggregateZero</a> (Type *Ty)</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/constant">Constant</a> *</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a63af5f287e94f3d11f879c1512b2f0f1">getSequentialElement</a> () const</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>If this CAZ has array or vector type, return a zero with the right element type. <a href="#a63af5f287e94f3d11f879c1512b2f0f1">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/constant">Constant</a> *</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#aa91e37c28a0db63d2acfc33ecb15e0aa">getStructElement</a> (unsigned Elt) const</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>If this CAZ has struct type, return a zero with the right element type for the specified element. <a href="#aa91e37c28a0db63d2acfc33ecb15e0aa">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/constant">Constant</a> *</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a9e8fadb6ef05bea5f591cae0125344e1">getElementValue</a> (Constant *C) const</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Return a zero of the right value for the specified GEP index if we can, otherwise return null (e.g. <a href="#a9e8fadb6ef05bea5f591cae0125344e1">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/constant">Constant</a> *</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a4b63206cf34ac604b93967cda7c6b7e5">getElementValue</a> (unsigned Idx) const</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Return a zero of the right value for the specified GEP index. <a href="#a4b63206cf34ac604b93967cda7c6b7e5">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/elementcount">ElementCount</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a36b782c6eb416c7d3b1086d5f50b2e54">getElementCount</a> () const</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Return the number of elements in the array, vector, or struct. <a href="#a36b782c6eb416c7d3b1086d5f50b2e54">More...</a></p>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ab3c08eac3b746ab8615c4aa82f9e8406">destroyConstantImpl</a> ()</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Remove the constant from the constant table. <a href="#ab3c08eac3b746ab8615c4aa82f9e8406">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

</table>

## Public Static Functions Index

<table class="doxyMembersIndex">

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">static <a href="/web-llvm/docs/api/classes/llvm/constantaggregatezero">ConstantAggregateZero</a> *</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#abfa1cf8b4348407b167f93bc7c01055f">get</a> (Type *Ty)</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a5b7f1f06fa09656ec3ec84b7847cba5b">classof</a> (const Value *V)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Methods for support type inquiry through isa, cast, and dyn_cast: <a href="#a5b7f1f06fa09656ec3ec84b7847cba5b">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

</table>

## Description {#details}

<p>All zero aggregate value.</p>

<p>Definition at line 353 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/ir/constants-h">Constants.h</a>.</p>


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


<p>Definition at line 354 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/ir/constants-h">Constants.h</a>.</p>


<p>References <a href="#a5bd16c2fbe755cda66b18d56761038ea">Constant</a> and <a href="/web-llvm/docs/api/classes/llvm/constantdata/#ade3ec5a4a86ffd069698509c87b6a604">llvm::ConstantData::ConstantData</a>.</p>


<p>Referenced by <a href="#a5bd16c2fbe755cda66b18d56761038ea">Constant</a>, <a href="#a5a8d7187aebeaafac8e3824ec235a11f">ConstantAggregateZero</a>, <a href="#a9e8fadb6ef05bea5f591cae0125344e1">getElementValue</a>, <a href="#a4b63206cf34ac604b93967cda7c6b7e5">getElementValue</a>, <a href="#a63af5f287e94f3d11f879c1512b2f0f1">getSequentialElement</a> and <a href="#aa91e37c28a0db63d2acfc33ecb15e0aa">getStructElement</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Public Constructors

### ConstantAggregateZero() {#a5a8d7187aebeaafac8e3824ec235a11f}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">llvm::ConstantAggregateZero::ConstantAggregateZero (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/constantaggregatezero">ConstantAggregateZero</a> &amp;)</td>
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



<p>Definition at line 362 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/ir/constants-h">Constants.h</a>.</p>


<p>References <a href="/web-llvm/docs/api/namespaces/llvm/callingconv/#ac6aa1387c4375260e2468eb5a77fdb4cafd841a49aec1539bc88abc8ff9e170fb">llvm::CallingConv::C</a> and <a href="#a5bd16c2fbe755cda66b18d56761038ea">Constant</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Private Constructors

### ConstantAggregateZero() {#a344d28bc035af46b0c69b75747633b7d}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">llvm::ConstantAggregateZero::ConstantAggregateZero (<a href="/web-llvm/docs/api/classes/llvm/type">Type</a> * Ty)</td>
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



<p>Definition at line 356 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/ir/constants-h">Constants.h</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Public Member Functions

### getElementCount() {#a36b782c6eb416c7d3b1086d5f50b2e54}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">ElementCount ConstantAggregateZero::getElementCount ()</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Return the number of elements in the array, vector, or struct.</p>

<p>Declaration at line 382 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/ir/constants-h">Constants.h</a>, definition at line 1154 of file <a href="/web-llvm/docs/api/files/lib/lib/ir/constants-cpp">Constants.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/namespaces/llvm/#a22eeee01734061ac1b31ccd994c49eef">llvm::dyn_cast</a>, <a href="/web-llvm/docs/api/classes/llvm/elementcount/#a584cb8dfa0090b33a969c4dda27337f6">llvm::ElementCount::getFixed</a> and <a href="/web-llvm/docs/api/classes/llvm/value/#a0344a49526443edf90cc0aef3abd3337">llvm::Value::getType</a>.</p>

</div>
</div>

### getElementValue() {#a9e8fadb6ef05bea5f591cae0125344e1}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">Constant * ConstantAggregateZero::getElementValue (<a href="/web-llvm/docs/api/classes/llvm/constant">Constant</a> * C)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Return a zero of the right value for the specified GEP index if we can, otherwise return null (e.g.</p>


<p>if C is a <a href="/web-llvm/docs/api/classes/llvm/constantexpr">ConstantExpr</a>).</p>


<p>Declaration at line 376 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/ir/constants-h">Constants.h</a>, definition at line 1142 of file <a href="/web-llvm/docs/api/files/lib/lib/ir/constants-cpp">Constants.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/namespaces/llvm/callingconv/#ac6aa1387c4375260e2468eb5a77fdb4cafd841a49aec1539bc88abc8ff9e170fb">llvm::CallingConv::C</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#ac4fc845f5ed92de63cd4474f128f5fc5">llvm::cast</a>, <a href="#a5bd16c2fbe755cda66b18d56761038ea">Constant</a>, <a href="#a63af5f287e94f3d11f879c1512b2f0f1">getSequentialElement</a>, <a href="#aa91e37c28a0db63d2acfc33ecb15e0aa">getStructElement</a>, <a href="/web-llvm/docs/api/classes/llvm/value/#a0344a49526443edf90cc0aef3abd3337">llvm::Value::getType</a> and <a href="/web-llvm/docs/api/namespaces/llvm/#a92ca992e52dddc420f4b069cae06dfbe">llvm::isa</a>.</p>

</div>
</div>

### getElementValue() {#a4b63206cf34ac604b93967cda7c6b7e5}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">Constant * ConstantAggregateZero::getElementValue (unsigned Idx)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Return a zero of the right value for the specified GEP index.</p>

<p>Declaration at line 379 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/ir/constants-h">Constants.h</a>, definition at line 1148 of file <a href="/web-llvm/docs/api/files/lib/lib/ir/constants-cpp">Constants.cpp</a>.</p>


<p>References <a href="#a5bd16c2fbe755cda66b18d56761038ea">Constant</a>, <a href="#a63af5f287e94f3d11f879c1512b2f0f1">getSequentialElement</a>, <a href="#aa91e37c28a0db63d2acfc33ecb15e0aa">getStructElement</a>, <a href="/web-llvm/docs/api/classes/llvm/value/#a0344a49526443edf90cc0aef3abd3337">llvm::Value::getType</a> and <a href="/web-llvm/docs/api/namespaces/llvm/#a92ca992e52dddc420f4b069cae06dfbe">llvm::isa</a>.</p>

</div>
</div>

### getSequentialElement() {#a63af5f287e94f3d11f879c1512b2f0f1}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">Constant * ConstantAggregateZero::getSequentialElement ()</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>If this CAZ has array or vector type, return a zero with the right element type.</p>

<p>Declaration at line 368 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/ir/constants-h">Constants.h</a>, definition at line 1132 of file <a href="/web-llvm/docs/api/files/lib/lib/ir/constants-cpp">Constants.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/namespaces/llvm/#ac4fc845f5ed92de63cd4474f128f5fc5">llvm::cast</a>, <a href="#a5bd16c2fbe755cda66b18d56761038ea">Constant</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a22eeee01734061ac1b31ccd994c49eef">llvm::dyn_cast</a>, <a href="/web-llvm/docs/api/classes/llvm/constant/#aa6574d526b3e38a28f688a7bb4325c2c">llvm::Constant::getNullValue</a> and <a href="/web-llvm/docs/api/classes/llvm/value/#a0344a49526443edf90cc0aef3abd3337">llvm::Value::getType</a>.</p>


<p>Referenced by <a href="#a9e8fadb6ef05bea5f591cae0125344e1">getElementValue</a> and <a href="#a4b63206cf34ac604b93967cda7c6b7e5">getElementValue</a>.</p>

</div>
</div>

### getStructElement() {#aa91e37c28a0db63d2acfc33ecb15e0aa}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">Constant * ConstantAggregateZero::getStructElement (unsigned Elt)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>If this CAZ has struct type, return a zero with the right element type for the specified element.</p>

<p>Declaration at line 372 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/ir/constants-h">Constants.h</a>, definition at line 1138 of file <a href="/web-llvm/docs/api/files/lib/lib/ir/constants-cpp">Constants.cpp</a>.</p>


<p>References <a href="#a5bd16c2fbe755cda66b18d56761038ea">Constant</a>, <a href="/web-llvm/docs/api/classes/llvm/constant/#aa6574d526b3e38a28f688a7bb4325c2c">llvm::Constant::getNullValue</a> and <a href="/web-llvm/docs/api/classes/llvm/value/#a0344a49526443edf90cc0aef3abd3337">llvm::Value::getType</a>.</p>


<p>Referenced by <a href="#a9e8fadb6ef05bea5f591cae0125344e1">getElementValue</a> and <a href="#a4b63206cf34ac604b93967cda7c6b7e5">getElementValue</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Private Member Functions

### destroyConstantImpl() {#ab3c08eac3b746ab8615c4aa82f9e8406}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void ConstantAggregateZero::destroyConstantImpl ()</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Remove the constant from the constant table.</p>

<p>Declaration at line 359 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/ir/constants-h">Constants.h</a>, definition at line 1685 of file <a href="/web-llvm/docs/api/files/lib/lib/ir/constants-cpp">Constants.cpp</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Public Static Functions

### classof() {#a5b7f1f06fa09656ec3ec84b7847cba5b}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool llvm::ConstantAggregateZero::classof (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/value">Value</a> * V)</td>
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

<p>Definition at line 386 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/ir/constants-h">Constants.h</a>.</p>

</div>
</div>

### get() {#abfa1cf8b4348407b167f93bc7c01055f}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">ConstantAggregateZero * ConstantAggregateZero::get (<a href="/web-llvm/docs/api/classes/llvm/type">Type</a> * Ty)</td>
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



<p>Declaration at line 364 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/ir/constants-h">Constants.h</a>, definition at line 1672 of file <a href="/web-llvm/docs/api/files/lib/lib/ir/constants-cpp">Constants.cpp</a>.</p>


<p>Reference <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/silowercontrolflow-cpp/#a4868c5d81c5ccc98c47aeab6244346a0">assert</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/namespaces/llvm/#addd1c6bc523b9a0eb56167da95dc5156">llvm::ConstantFoldShuffleVectorInstruction</a>, <a href="/web-llvm/docs/api/classes/anonymous-lowermatrixintrinsics-cpp-/lowermatrixintrinsics/#a1fb67d47830d47e72144d7456dbb7fa0">anonymous{LowerMatrixIntrinsics.cpp}::LowerMatrixIntrinsics::createTiledLoops</a>, <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/instcombine/instcombinevectorops-cpp/#a06358c30f3e98d9e57f4ae9162f33c72">evaluateInDifferentElementOrder</a>, <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/scalar/rewritestatepointsforgc-cpp/#aa421c7018618b7f06cab7230bf12f872">findBaseDefiningValueOfVector</a>, <a href="/web-llvm/docs/api/classes/llvm/constantstruct/#a54fcfa620deb80373f489ba2fdad7643">llvm::ConstantStruct::get</a>, <a href="/web-llvm/docs/api/classes/llvm/sandboxir/constantaggregatezero/#a09c96c69df3622356393568825d39227">llvm::sandboxir::ConstantAggregateZero::get</a>, <a href="/web-llvm/docs/api/classes/llvm/constantdatasequential/#a9a20b607f6fdb3dd6689a3daed25f3cb">llvm::ConstantDataSequential::getImpl</a>, <a href="/web-llvm/docs/api/classes/llvm/constant/#aa6574d526b3e38a28f688a7bb4325c2c">llvm::Constant::getNullValue</a>, <a href="/web-llvm/docs/api/namespaces/llvm/offloading/#af023297673da795cc027d7aa8fd62817">llvm::offloading::getOffloadEntryArray</a>, <a href="/web-llvm/docs/api/classes/llvm/constantvector/#aa3b241b35b0039b413faf1ef4e873eb7">llvm::ConstantVector::getSplat</a>, <a href="/web-llvm/docs/api/classes/anonymous-lowermatrixintrinsics-cpp-/lowermatrixintrinsics/#a897ffb621380e9230778c792ca27d9c4">anonymous{LowerMatrixIntrinsics.cpp}::LowerMatrixIntrinsics::getZeroMatrix</a>, <a href="/web-llvm/docs/api/classes/llvm/x86ttiimpl/#a47cb7185e35282131b486036ff7c45df">llvm::X86TTIImpl::instCombineIntrinsic</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64targettransforminfo-cpp/#a4e5c7b6a107ed8c6fa33ce4b8a6f97c2">instCombineLD1GatherIndex</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64targettransforminfo-cpp/#afdcb3be103dc32527286d0352eeacdd6">instCombineSVEDupqLane</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64targettransforminfo-cpp/#ac80824cf7bdae0e18c7032eb8ce5214c">instCombineSVELD1</a>, <a href="/web-llvm/docs/api/classes/anonymous-valuemapper-cpp-/mapper/#a7d5502a6047fb27d6c33ea2820608c2c">anonymous{ValueMapper.cpp}::Mapper::mapValue</a>, <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/scalar/rewritestatepointsforgc-cpp/#a55412d2c237115c95f20e12ba0d95922">relocationViaAlloca</a>, <a href="/web-llvm/docs/api/classes/llvm/x86ttiimpl/#afd63c73f7201b4ed318ed3a3c56b6cad">llvm::X86TTIImpl::simplifyDemandedVectorEltsIntrinsic</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/x86/x86instcombineintrinsic-cpp/#adbe56869c99b539068e8a442d8738dae">simplifyX86extrq</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/x86/x86instcombineintrinsic-cpp/#a093d9c63af2a86ce11aab9d16508faa5">simplifyX86immShift</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/x86/x86instcombineintrinsic-cpp/#ac9b860e591f79a6fb767cb04b3135f7f">simplifyX86insertps</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/x86/x86instcombineintrinsic-cpp/#abf44819ee45fe0465818d5244da90f68">simplifyX86pmadd</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/x86/x86instcombineintrinsic-cpp/#a7db2eee6dd2ea98d0ec3c05950be2915">simplifyX86pmulh</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/directx/dxilflattenarrays-cpp/#ac9966bce879b21a4a601daab59e25c97">transformInitializer</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/directx/dxildatascalarization-cpp/#ab9bfb7e130ccc022600bc9c1aea8bba0">transformInitializer</a>, <a href="/web-llvm/docs/api/files/lib/lib/ir/autoupgrade-cpp/#a4ce4b835cffc5fa4123fe82f5f39cf97">upgradeAArch64IntrinsicCall</a>, <a href="/web-llvm/docs/api/files/lib/lib/ir/autoupgrade-cpp/#abbe50b1b6428dd6884355b64360f2f29">upgradeX86ConcatShift</a>, <a href="/web-llvm/docs/api/files/lib/lib/ir/autoupgrade-cpp/#af61729415c4cfec66c791cd52a532eb9">upgradeX86IntrinsicCall</a>, <a href="/web-llvm/docs/api/files/lib/lib/ir/autoupgrade-cpp/#a02b56bd888812aead982e69819ce8452">upgradeX86VPERMT2Intrinsics</a> and <a href="/web-llvm/docs/api/classes/llvm/instcombinerimpl/#afa2581e2e1ac6959cd02e28062a7c1d5">llvm::InstCombinerImpl::visitCallInst</a>.</p>

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

<p class="doxyGeneratedBy">Generated via <a href="https://github.com/xpack/doxygen2docusaurus">doxygen2docusaurus</a> by <a href="https://www.doxygen.nl">Doxygen</a> 1.15.0.</p>

</div>
