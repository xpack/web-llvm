---

# DO NOT EDIT!
# Automatically generated via doxygen2docusaurus by Doxygen.

slug: /api/classes/llvm/typedinit
custom_edit_url: null
toc_max_heading_level: 4
keywords:
  - doxygen
  - reference
  - class

---

<div class="doxyPage">

# The `TypedInit` Class Reference

<p>This is the common superclass of types that have a specific, explicit type, stored in ValueTy. <a href="#details">More...</a></p>

## Declaration

<div class="doxyDeclaration">
class llvm::TypedInit { ... }
</div>

## Included Headers

<div class="doxyIncludesList">#include "<a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/tablegen/record-h">llvm/TableGen/Record.h</a>"
</div>

## Base class

<table class="doxyMembersIndex">

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">class</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/init">Init</a></td>
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

## Derived Classes

<table class="doxyMembersIndex">

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">class</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/anonymousnameinit">AnonymousNameInit</a></td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>"anonymous_n" - Represent an anonymous record name <a href="/web-llvm/docs/api/classes/llvm/anonymousnameinit/#details">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">class</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/bitinit">BitInit</a></td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>'true'/'false' - Represent a concrete initializer for a bit. <a href="/web-llvm/docs/api/classes/llvm/bitinit/#details">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">class</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/bitsinit">BitsInit</a></td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>'{ a, b, c }' - Represents an initializer for a <a href="/web-llvm/docs/api/classes/llvm/bitsrecty">BitsRecTy</a> value. <a href="/web-llvm/docs/api/classes/llvm/bitsinit/#details">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">class</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/condopinit">CondOpInit</a></td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>!cond(condition_1: value1, ... , condition_n: value) Selects the first value for which condition is true. <a href="/web-llvm/docs/api/classes/llvm/condopinit/#details">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">class</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/daginit">DagInit</a></td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>(v a, b) - Represent a DAG tree value. <a href="/web-llvm/docs/api/classes/llvm/daginit/#details">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">class</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/definit">DefInit</a></td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>AL - Represent a reference to a 'def' in the description. <a href="/web-llvm/docs/api/classes/llvm/definit/#details">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">class</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/existsopinit">ExistsOpInit</a></td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>!exists&lt;type&gt;(expr) - Dynamically determine if a record of <span class="doxyComputerOutput">type</span> named <span class="doxyComputerOutput">expr</span> exists. <a href="/web-llvm/docs/api/classes/llvm/existsopinit/#details">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">class</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/fieldinit">FieldInit</a></td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>X.Y - Represent a reference to a subfield of a variable. <a href="/web-llvm/docs/api/classes/llvm/fieldinit/#details">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">class</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/foldopinit">FoldOpInit</a></td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>!foldl (a, b, expr, start, lst) - Fold over a list. <a href="/web-llvm/docs/api/classes/llvm/foldopinit/#details">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">class</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/intinit">IntInit</a></td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>'7' - Represent an initialization by a literal integer value. <a href="/web-llvm/docs/api/classes/llvm/intinit/#details">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">class</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/isaopinit">IsAOpInit</a></td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>!isa&lt;type&gt;(expr) - Dynamically determine the type of an expression. <a href="/web-llvm/docs/api/classes/llvm/isaopinit/#details">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">class</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/listinit">ListInit</a></td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>[AL, AH, CL] - Represent a list of defs <a href="/web-llvm/docs/api/classes/llvm/listinit/#details">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">class</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/opinit">OpInit</a></td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Base class for operators. <a href="/web-llvm/docs/api/classes/llvm/opinit/#details">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">class</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/stringinit">StringInit</a></td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>"foo" - Represent an initialization by a string value. <a href="/web-llvm/docs/api/classes/llvm/stringinit/#details">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">class</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/varbitinit">VarBitInit</a></td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Opcode{0} - Represent access to one bit of a variable or field. <a href="/web-llvm/docs/api/classes/llvm/varbitinit/#details">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">class</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/vardefinit">VarDefInit</a></td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>classname&lt;targs...&gt; - Represent an uninstantiated anonymous class instantiation. <a href="/web-llvm/docs/api/classes/llvm/vardefinit/#details">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">class</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/varinit">VarInit</a></td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>'Opcode' - Represent a reference to an entire variable object. <a href="/web-llvm/docs/api/classes/llvm/varinit/#details">More...</a></p>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a95e5db7f16bbe474baf4fde341822ec6">TypedInit</a> (const TypedInit &amp;)=delete</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a3a850231a595c63f918ebc27fed94e08">TypedInit</a> (InitKind K, const RecTy *T, uint8_t Opc=0)</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/typedinit">TypedInit</a> &amp;</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#abb373b2cdf42818214cbcb7d78edae11">operator=</a> (const TypedInit &amp;)=delete</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/recty">RecTy</a> *</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#acdd9719e6d661022e6d5b1da9548c36e">getType</a> () const</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Get the type of the <a href="/web-llvm/docs/api/classes/llvm/init">Init</a> as a <a href="/web-llvm/docs/api/classes/llvm/recty">RecTy</a>. <a href="#acdd9719e6d661022e6d5b1da9548c36e">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/recordkeeper">RecordKeeper</a> &amp;</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a8392de5e010c92649df6d559e702a694">getRecordKeeper</a> () const</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Get the record keeper that initialized this <a href="/web-llvm/docs/api/classes/llvm/init">Init</a>. <a href="#a8392de5e010c92649df6d559e702a694">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/init">Init</a> *</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#abfdfeb6e9f368848e73a8eba175a99fb">getCastTo</a> (const RecTy *Ty) const override</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>If this value is convertible to type <span class="doxyComputerOutput">Ty</span>, return a value whose type is <span class="doxyComputerOutput">Ty</span>, generating a !cast operation if required. <a href="#abfdfeb6e9f368848e73a8eba175a99fb">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/init">Init</a> *</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ac19efdca0970a26cd20c2130876ad6a7">convertInitializerTo</a> (const RecTy *Ty) const override</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Convert to a value whose type is <span class="doxyComputerOutput">Ty</span>, or return null if this is not possible. <a href="#ac19efdca0970a26cd20c2130876ad6a7">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/init">Init</a> *</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a60ed010e5b9fd39c0775648ac9198887">convertInitializerBitRange</a> (ArrayRef&lt; unsigned &gt; Bits) const override</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>This function is used to implement the bit range selection operator. <a href="#a60ed010e5b9fd39c0775648ac9198887">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/recty">RecTy</a> *</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a226551c7f4d2fd9c7bfcb4b56f489417">getFieldType</a> (const StringInit *FieldName) const override</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>This method is used to implement the <a href="/web-llvm/docs/api/classes/llvm/fieldinit">FieldInit</a> class. <a href="#a226551c7f4d2fd9c7bfcb4b56f489417">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

</table>

## Private Member Attributes Index

<table class="doxyMembersIndex">

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/recty">RecTy</a> *</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#aee08ab32b5534d1413241ff9eef05b36">ValueTy</a></td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a32bb9980f9ceade4933ea81fa4d6fc96">classof</a> (const Init *I)</td>
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

<p>This is the common superclass of types that have a specific, explicit type, stored in ValueTy.</p>

<p>Definition at line 416 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/tablegen/record-h">Record.h</a>.</p>


<div class="doxySectionDef">

## Public Constructors

### TypedInit() {#a95e5db7f16bbe474baf4fde341822ec6}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">llvm::TypedInit::TypedInit (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/typedinit">TypedInit</a> &amp;)</td>
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



<p>Definition at line 424 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/tablegen/record-h">Record.h</a>.</p>


<p>Reference <a href="#a3a850231a595c63f918ebc27fed94e08">TypedInit</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Protected Constructors

### TypedInit() {#a3a850231a595c63f918ebc27fed94e08}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">llvm::TypedInit::TypedInit (<a href="/web-llvm/docs/api/classes/llvm/init/#a54e3c8e4571f5bf7daf2f792e4f1997e">InitKind</a> K, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/recty">RecTy</a> * T, uint8_t Opc=0)</td>
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



<p>Definition at line 420 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/tablegen/record-h">Record.h</a>.</p>


<p>References <a href="/web-llvm/docs/api/classes/llvm/init/#ae13588eb910e6f97e1b213f2c875ca8e">llvm::Init::Init</a>, <a href="/web-llvm/docs/api/classes/llvm/init/#a033dc74493053e93fde93554c95a288c">llvm::Init::Opc</a> and <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/mips/mips16isellowering-cpp/#a0acb682b8260ab1c60b918599864e2e5">T</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/classes/llvm/varbitinit/#a0496581f233ebba1beda1293a803b573">llvm::VarBitInit::get</a>, <a href="#abb373b2cdf42818214cbcb7d78edae11">operator=</a>, <a href="/web-llvm/docs/api/classes/llvm/opinit/#ae1153460ec9adaa262e589e9d017895d">llvm::OpInit::OpInit</a> and <a href="#a95e5db7f16bbe474baf4fde341822ec6">TypedInit</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Public Operators

### operator=() {#abb373b2cdf42818214cbcb7d78edae11}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">TypedInit &amp; llvm::TypedInit::operator= (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/typedinit">TypedInit</a> &amp;)</td>
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



<p>Definition at line 425 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/tablegen/record-h">Record.h</a>.</p>


<p>Reference <a href="#a3a850231a595c63f918ebc27fed94e08">TypedInit</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Public Member Functions

### convertInitializerBitRange() {#a60ed010e5b9fd39c0775648ac9198887}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">const Init * TypedInit::convertInitializerBitRange (<a href="/web-llvm/docs/api/classes/llvm/arrayref">ArrayRef</a>&lt; unsigned &gt; Bits)</td>
</tr>
</table>
</td>
<td class="doxyMemberLabelsRight">
<span class="doxyMemberLabels">
<span class="doxyMemberLabel virtual">virtual</span>
</span>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>This function is used to implement the bit range selection operator.</p>


<p>Given a value, it selects the specified bits, returning them as a new <span class="doxyComputerOutput"><a href="/web-llvm/docs/api/classes/llvm/init">Init</a></span> of type <span class="doxyComputerOutput">bits</span>. If it is not legal to use the bit selection operator on this value, null is returned.</p>


<p>Declaration at line 442 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/tablegen/record-h">Record.h</a>, definition at line 2224 of file <a href="/web-llvm/docs/api/files/lib/lib/tablegen/record-cpp">Record.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/namespaces/llvm/#a22eeee01734061ac1b31ccd994c49eef">llvm::dyn_cast</a>, <a href="/web-llvm/docs/api/classes/llvm/bitsinit/#ad964d60acd20953d20b1e673a397d5e2">llvm::BitsInit::get</a>, <a href="/web-llvm/docs/api/classes/llvm/varbitinit/#a0496581f233ebba1beda1293a803b573">llvm::VarBitInit::get</a>, <a href="#a8392de5e010c92649df6d559e702a694">getRecordKeeper</a>, <a href="#acdd9719e6d661022e6d5b1da9548c36e">getType</a>, <a href="/web-llvm/docs/api/classes/llvm/smallvectortemplatebase/#af42bfbc067df27c19ee2fc859df58799">llvm::SmallVectorTemplateBase&lt; T, bool &gt;::push_back</a>, <a href="/web-llvm/docs/api/classes/llvm/smallvectorimpl/#a499ea32ca1b8d16cedfe01d1e5b08f29">llvm::SmallVectorImpl&lt; T &gt;::reserve</a> and <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/mips/mips16isellowering-cpp/#a0acb682b8260ab1c60b918599864e2e5">T</a>.</p>

</div>
</div>

### convertInitializerTo() {#ac19efdca0970a26cd20c2130876ad6a7}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">const Init * TypedInit::convertInitializerTo (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/recty">RecTy</a> * Ty)</td>
</tr>
</table>
</td>
<td class="doxyMemberLabelsRight">
<span class="doxyMemberLabels">
<span class="doxyMemberLabel virtual">virtual</span>
</span>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Convert to a value whose type is <span class="doxyComputerOutput">Ty</span>, or return null if this is not possible.</p>


<p>This can happen if the value's type is convertible to <span class="doxyComputerOutput">Ty</span>, but there are unresolved references.</p>


<p>Declaration at line 439 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/tablegen/record-h">Record.h</a>, definition at line 2212 of file <a href="/web-llvm/docs/api/files/lib/lib/tablegen/record-cpp">Record.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/namespaces/llvm/#ac4fc845f5ed92de63cd4474f128f5fc5">llvm::cast</a>, <a href="/web-llvm/docs/api/classes/llvm/bitsinit/#ad964d60acd20953d20b1e673a397d5e2">llvm::BitsInit::get</a>, <a href="#a8392de5e010c92649df6d559e702a694">getRecordKeeper</a>, <a href="#acdd9719e6d661022e6d5b1da9548c36e">getType</a>, <a href="/web-llvm/docs/api/classes/llvm/init/#ae13588eb910e6f97e1b213f2c875ca8e">llvm::Init::Init</a> and <a href="/web-llvm/docs/api/namespaces/llvm/#a92ca992e52dddc420f4b069cae06dfbe">llvm::isa</a>.</p>


<p>Referenced by <a href="#abfdfeb6e9f368848e73a8eba175a99fb">getCastTo</a>.</p>

</div>
</div>

### getCastTo() {#abfdfeb6e9f368848e73a8eba175a99fb}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">const Init * TypedInit::getCastTo (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/recty">RecTy</a> * Ty)</td>
</tr>
</table>
</td>
<td class="doxyMemberLabelsRight">
<span class="doxyMemberLabels">
<span class="doxyMemberLabel virtual">virtual</span>
</span>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>If this value is convertible to type <span class="doxyComputerOutput">Ty</span>, return a value whose type is <span class="doxyComputerOutput">Ty</span>, generating a !cast operation if required.</p>


<p>Otherwise, return null.</p>


<p>Declaration at line 438 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/tablegen/record-h">Record.h</a>, definition at line 2240 of file <a href="/web-llvm/docs/api/files/lib/lib/tablegen/record-cpp">Record.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/silowercontrolflow-cpp/#a4868c5d81c5ccc98c47aeab6244346a0">assert</a>, <a href="/web-llvm/docs/api/classes/llvm/unopinit/#ac03d2cc4ff2a382b0eb7999ac9ff0ca3aab4ee971c2ba1beb7ed1700ae7955b79">llvm::UnOpInit::CAST</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#ac4fc845f5ed92de63cd4474f128f5fc5">llvm::cast</a>, <a href="#ac19efdca0970a26cd20c2130876ad6a7">convertInitializerTo</a>, <a href="/web-llvm/docs/api/classes/llvm/unopinit/#af0e0cf8fa25dde613e92575630bb9475">llvm::UnOpInit::Fold</a>, <a href="/web-llvm/docs/api/classes/llvm/unopinit/#aa8ac284a20b1ea9f96469bf3d39d1f81">llvm::UnOpInit::get</a>, <a href="#acdd9719e6d661022e6d5b1da9548c36e">getType</a>, <a href="/web-llvm/docs/api/classes/llvm/init/#ae13588eb910e6f97e1b213f2c875ca8e">llvm::Init::Init</a> and <a href="/web-llvm/docs/api/namespaces/llvm/#a92ca992e52dddc420f4b069cae06dfbe">llvm::isa</a>.</p>

</div>
</div>

### getFieldType() {#a226551c7f4d2fd9c7bfcb4b56f489417}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">const RecTy * TypedInit::getFieldType (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/stringinit">StringInit</a> * FieldName)</td>
</tr>
</table>
</td>
<td class="doxyMemberLabelsRight">
<span class="doxyMemberLabels">
<span class="doxyMemberLabel virtual">virtual</span>
</span>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>This method is used to implement the <a href="/web-llvm/docs/api/classes/llvm/fieldinit">FieldInit</a> class.</p>


<p>Implementors of this method should return the type of the named field if they are of type record.</p>


<p>Declaration at line 447 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/tablegen/record-h">Record.h</a>, definition at line 2202 of file <a href="/web-llvm/docs/api/files/lib/lib/tablegen/record-cpp">Record.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/namespaces/llvm/#a22eeee01734061ac1b31ccd994c49eef">llvm::dyn_cast</a> and <a href="#acdd9719e6d661022e6d5b1da9548c36e">getType</a>.</p>

</div>
</div>

### getRecordKeeper() {#a8392de5e010c92649df6d559e702a694}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">RecordKeeper &amp; llvm::TypedInit::getRecordKeeper ()</td>
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

<p>Get the record keeper that initialized this <a href="/web-llvm/docs/api/classes/llvm/init">Init</a>.</p>

<p>Definition at line 436 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/tablegen/record-h">Record.h</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/classes/llvm/binopinit/#a909a53b386dc20dfa36a2fb86d63ec36">llvm::BinOpInit::CompareInit</a>, <a href="/web-llvm/docs/api/files/lib/lib/tablegen/record-cpp/#a3eb03bef656ad82043fbb7742038dba2">ConcatStringInits</a>, <a href="/web-llvm/docs/api/classes/llvm/bitsinit/#aa2c02786149c8b64a7047e8ad20209e5">llvm::BitsInit::convertInitializerBitRange</a>, <a href="/web-llvm/docs/api/classes/llvm/intinit/#a269320a25f13a22f2aebeb9136063a91">llvm::IntInit::convertInitializerBitRange</a>, <a href="#a60ed010e5b9fd39c0775648ac9198887">convertInitializerBitRange</a>, <a href="/web-llvm/docs/api/classes/llvm/bitinit/#ae0a2c1bf6f739220d3c473c0bdcd588b">llvm::BitInit::convertInitializerTo</a>, <a href="/web-llvm/docs/api/classes/llvm/bitsinit/#ac88ed97cdf23651423069ebc764ce6bf">llvm::BitsInit::convertInitializerTo</a>, <a href="/web-llvm/docs/api/classes/llvm/intinit/#ae0acbf48b19610c4bcfecabba532c4a9">llvm::IntInit::convertInitializerTo</a>, <a href="#ac19efdca0970a26cd20c2130876ad6a7">convertInitializerTo</a>, <a href="/web-llvm/docs/api/classes/llvm/binopinit/#adbe242b084763cfdb35c7850bd4098b5">llvm::BinOpInit::Fold</a>, <a href="/web-llvm/docs/api/classes/llvm/condopinit/#a1f8ad2f0a11458133631759e29f2b54a">llvm::CondOpInit::Fold</a>, <a href="/web-llvm/docs/api/classes/llvm/existsopinit/#adb91410c35b4cb3b300041319c35608a">llvm::ExistsOpInit::Fold</a>, <a href="/web-llvm/docs/api/classes/llvm/isaopinit/#afc837e9b32ef1f8622f7cebbbf738c64">llvm::IsAOpInit::Fold</a>, <a href="/web-llvm/docs/api/classes/llvm/ternopinit/#a40e75ea14a528e6ffb58da993ab983a8">llvm::TernOpInit::Fold</a>, <a href="/web-llvm/docs/api/classes/llvm/unopinit/#af0e0cf8fa25dde613e92575630bb9475">llvm::UnOpInit::Fold</a>, <a href="/web-llvm/docs/api/classes/llvm/fieldinit/#a7c819ab8d133b39b5bfbb560e909b0e7">llvm::FieldInit::getBit</a>, <a href="/web-llvm/docs/api/classes/llvm/intinit/#a3e3e4db89b4fcc494328ef01234a7b30">llvm::IntInit::getBit</a>, <a href="/web-llvm/docs/api/classes/llvm/opinit/#ab74934e338995e59f6ada2d046e5804d">llvm::OpInit::getBit</a>, <a href="/web-llvm/docs/api/classes/llvm/varinit/#a721bbe17adfaba22cb66cbca55477f1e">llvm::VarInit::getBit</a>, <a href="/web-llvm/docs/api/classes/llvm/anonymousnameinit/#a4bfa93128d9f7ad2cea7342dfe9737e1">llvm::AnonymousNameInit::getNameInit</a>, <a href="/web-llvm/docs/api/classes/llvm/binopinit/#a3b8eca57b47e415cd91ef858793a273f">llvm::BinOpInit::resolveReferences</a>, <a href="/web-llvm/docs/api/classes/llvm/bitsinit/#ac80663dd5a98becc34254b6f72fc0339">llvm::BitsInit::resolveReferences</a> and <a href="/web-llvm/docs/api/classes/llvm/ternopinit/#aee884b61ea9174997b34ece042bde0f8">llvm::TernOpInit::resolveReferences</a>.</p>

</div>
</div>

### getType() {#acdd9719e6d661022e6d5b1da9548c36e}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">const RecTy * llvm::TypedInit::getType ()</td>
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

<p>Get the type of the <a href="/web-llvm/docs/api/classes/llvm/init">Init</a> as a <a href="/web-llvm/docs/api/classes/llvm/recty">RecTy</a>.</p>

<p>Definition at line 433 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/tablegen/record-h">Record.h</a>.</p>


<p>Referenced by <a href="#a60ed010e5b9fd39c0775648ac9198887">convertInitializerBitRange</a>, <a href="/web-llvm/docs/api/classes/llvm/definit/#a7ced8e8f8b179f7958450a9d1a1ee7d9">llvm::DefInit::convertInitializerTo</a>, <a href="/web-llvm/docs/api/classes/llvm/listinit/#a9cd2348c22c203136a09b4c77d4f600c">llvm::ListInit::convertInitializerTo</a>, <a href="#ac19efdca0970a26cd20c2130876ad6a7">convertInitializerTo</a>, <a href="/web-llvm/docs/api/classes/llvm/binopinit/#adbe242b084763cfdb35c7850bd4098b5">llvm::BinOpInit::Fold</a>, <a href="/web-llvm/docs/api/classes/llvm/ternopinit/#a40e75ea14a528e6ffb58da993ab983a8">llvm::TernOpInit::Fold</a>, <a href="/web-llvm/docs/api/classes/llvm/unopinit/#af0e0cf8fa25dde613e92575630bb9475">llvm::UnOpInit::Fold</a>, <a href="/web-llvm/docs/api/classes/llvm/binopinit/#a5d801c7bc5e5db15b1a6ec6bc5035c17">llvm::BinOpInit::getAsString</a>, <a href="/web-llvm/docs/api/classes/llvm/unopinit/#ae5510ac03650631d17eb8d28aeec63b9">llvm::UnOpInit::getAsString</a>, <a href="/web-llvm/docs/api/classes/llvm/fieldinit/#a7c819ab8d133b39b5bfbb560e909b0e7">llvm::FieldInit::getBit</a>, <a href="/web-llvm/docs/api/classes/llvm/opinit/#ab74934e338995e59f6ada2d046e5804d">llvm::OpInit::getBit</a>, <a href="/web-llvm/docs/api/classes/llvm/varinit/#a721bbe17adfaba22cb66cbca55477f1e">llvm::VarInit::getBit</a>, <a href="#abfdfeb6e9f368848e73a8eba175a99fb">getCastTo</a>, <a href="/web-llvm/docs/api/classes/llvm/listinit/#a1df971a09013eb33976bce9eaa86b044">llvm::ListInit::getElementType</a>, <a href="#a226551c7f4d2fd9c7bfcb4b56f489417">getFieldType</a>, <a href="/web-llvm/docs/api/classes/llvm/binopinit/#a3b5436bebef6bc757e1cdd29ce4131f0">llvm::BinOpInit::Profile</a>, <a href="/web-llvm/docs/api/classes/llvm/foldopinit/#ae62f9edbd30a30c8efbc74780eab58ad">llvm::FoldOpInit::Profile</a>, <a href="/web-llvm/docs/api/classes/llvm/listinit/#aa1879c42d29f8c98375e297fa08bd098">llvm::ListInit::Profile</a>, <a href="/web-llvm/docs/api/classes/llvm/ternopinit/#a7d82747df5bb4e9bfc66096f7998de90">llvm::TernOpInit::Profile</a>, <a href="/web-llvm/docs/api/classes/llvm/unopinit/#ab3b5e79324a22bdea975e1a62aadcf9c">llvm::UnOpInit::Profile</a>, <a href="/web-llvm/docs/api/classes/llvm/binopinit/#a3b8eca57b47e415cd91ef858793a273f">llvm::BinOpInit::resolveReferences</a>, <a href="/web-llvm/docs/api/classes/llvm/foldopinit/#abf5c6303f8771b4a93c937eea625e4a8">llvm::FoldOpInit::resolveReferences</a>, <a href="/web-llvm/docs/api/classes/llvm/ternopinit/#aee884b61ea9174997b34ece042bde0f8">llvm::TernOpInit::resolveReferences</a> and <a href="/web-llvm/docs/api/classes/llvm/unopinit/#ac56f3b64a789146946b48afe5613c2f5">llvm::UnOpInit::resolveReferences</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Private Member Attributes

### ValueTy {#aee08ab32b5534d1413241ff9eef05b36}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">const RecTy* llvm::TypedInit::ValueTy</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 417 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/tablegen/record-h">Record.h</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Public Static Functions

### classof() {#a32bb9980f9ceade4933ea81fa4d6fc96}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool llvm::TypedInit::classof (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/init">Init</a> * I)</td>
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



<p>Definition at line 427 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/tablegen/record-h">Record.h</a>.</p>


<p>References <a href="/web-llvm/docs/api/files/lib/lib/support/md5-cpp/#ac0eafdc9ee161b71e7af98af736952fd">I</a>, <a href="/web-llvm/docs/api/classes/llvm/init/#a54e3c8e4571f5bf7daf2f792e4f1997ea9519e0da45d9a461afb0020309b440c5">llvm::Init::IK_FirstTypedInit</a>, <a href="/web-llvm/docs/api/classes/llvm/init/#a54e3c8e4571f5bf7daf2f792e4f1997ea2adede9ed3f67560b90f9634ca52f03e">llvm::Init::IK_LastTypedInit</a> and <a href="/web-llvm/docs/api/classes/llvm/init/#ae13588eb910e6f97e1b213f2c875ca8e">llvm::Init::Init</a>.</p>

</div>
</div>

</div>

<hr/>

The documentation for this class was generated from the following files:

<ul>
<li><a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/tablegen/record-h">Record.h</a></li>
<li><a href="/web-llvm/docs/api/files/lib/lib/tablegen/record-cpp">Record.cpp</a></li>
</ul>

<hr/>

<p class="doxyGeneratedBy">Generated via <a href="https://github.com/xpack/doxygen2docusaurus">doxygen2docusaurus</a> by <a href="https://www.doxygen.nl">Doxygen</a> 1.14.0.</p>

</div>
