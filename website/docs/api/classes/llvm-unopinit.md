---

# DO NOT EDIT!
# Automatically generated via doxygen2docusaurus by Doxygen.

slug: /api/classes/llvm/unopinit
custom_edit_url: null
toc_max_heading_level: 4
keywords:
  - doxygen
  - reference
  - class

---

<div class="doxyPage">

# `UnOpInit` Class

<p>!op (X) - Transform an init. <a href="#details">More...</a></p>

## Declaration

<div class="doxyDeclaration">
class llvm::UnOpInit { ... }
</div>

## Included Headers

<div class="doxyIncludesList">#include "<a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/tablegen/record-h">llvm/TableGen/Record.h</a>"
</div>

## Base classes

<table class="doxyMembersIndex">

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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/foldingsetbase/node">Node</a></td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p><a href="/web-llvm/docs/api/classes/llvm/foldingsetbase/node">Node</a> - This class is used to maintain the singly linked bucket list in a folding set. <a href="/web-llvm/docs/api/classes/llvm/foldingsetbase/node/#details">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

</table>

## Enumerations Index

<table class="doxyMembersIndex">

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">enum</td>
<td class="doxyMemberIndexItemName" align="left" valign="top">UnaryOp : uint8_t { <a href="#ac03d2cc4ff2a382b0eb7999ac9ff0ca3">...</a> }</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ab2389d89fa4826927c27abdc525df338">UnOpInit</a> (const UnOpInit &amp;)=delete</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a7d19c19a7294cf25dd96757925ea5e84">UnOpInit</a> (UnaryOp opc, const Init *lhs, const RecTy *Type)</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/unopinit">UnOpInit</a> &amp;</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a33924ccd636d4e2142d8a50c6ee09ea4">operator=</a> (const UnOpInit &amp;)=delete</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ab3b5e79324a22bdea975e1a62aadcf9c">Profile</a> (FoldingSetNodeID &amp;ID) const</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="#ac03d2cc4ff2a382b0eb7999ac9ff0ca3">UnaryOp</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a83abcaad6f9e99aa316e38329c8889b6">getOpcode</a> () const</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/init">Init</a> *</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a01fed6c593b85eb1d4f759e40aa90b85">getOperand</a> () const</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/init">Init</a> *</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#af0e0cf8fa25dde613e92575630bb9475">Fold</a> (const Record *CurRec, bool IsFinal=false) const</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/init">Init</a> *</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ac56f3b64a789146946b48afe5613c2f5">resolveReferences</a> (Resolver &amp;R) const override</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>This function is used by classes that refer to other variables which may not be defined at the time the expression is formed. <a href="#ac56f3b64a789146946b48afe5613c2f5">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">std::string</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ae5510ac03650631d17eb8d28aeec63b9">getAsString</a> () const override</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Convert this value to a literal form. <a href="#ae5510ac03650631d17eb8d28aeec63b9">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

</table>

## Private Member Attributes Index

<table class="doxyMembersIndex">

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/init">Init</a> *</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a8786ae84665eea19052c101a4a453eb8">LHS</a></td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a7a41c91fce1ae50ec797b6f19106db17">classof</a> (const Init *I)</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">static <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/unopinit">UnOpInit</a> *</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#aa8ac284a20b1ea9f96469bf3d39d1f81">get</a> (UnaryOp opc, const Init *lhs, const RecTy *Type)</td>
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

<p>!op (X) - Transform an init.</p>

<p>Definition at line 842 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/tablegen/record-h">Record.h</a>.</p>


<div class="doxySectionDef">

## Enumerations

### UnaryOp {#ac03d2cc4ff2a382b0eb7999ac9ff0ca3}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">enum llvm::UnOpInit::UnaryOp : uint8_t</td>
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
<td class="doxyEnumItemName">TOLOWER<a id="ac03d2cc4ff2a382b0eb7999ac9ff0ca3aff10ccb4bdbd1a163a686db9886a24d6"></a></td>
<td class="doxyEnumItemDescription"></td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">TOUPPER<a id="ac03d2cc4ff2a382b0eb7999ac9ff0ca3a1fb08e7386aec11ef074190d30afe284"></a></td>
<td class="doxyEnumItemDescription"></td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">CAST<a id="ac03d2cc4ff2a382b0eb7999ac9ff0ca3aab4ee971c2ba1beb7ed1700ae7955b79"></a></td>
<td class="doxyEnumItemDescription"></td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">NOT<a id="ac03d2cc4ff2a382b0eb7999ac9ff0ca3abded462c3c8e85ef79327bab8f73efd6"></a></td>
<td class="doxyEnumItemDescription"></td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">HEAD<a id="ac03d2cc4ff2a382b0eb7999ac9ff0ca3a33cba82be6410ca26755494a93351eff"></a></td>
<td class="doxyEnumItemDescription"></td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">TAIL<a id="ac03d2cc4ff2a382b0eb7999ac9ff0ca3ae0e5d441bf3f167560d89d6e82535b5c"></a></td>
<td class="doxyEnumItemDescription"></td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">SIZE<a id="ac03d2cc4ff2a382b0eb7999ac9ff0ca3aa564303ab4af94485da6a68923fcdd51"></a></td>
<td class="doxyEnumItemDescription"></td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">EMPTY<a id="ac03d2cc4ff2a382b0eb7999ac9ff0ca3a99aa51ae9174f57bdf8b9a6688cfd3c8"></a></td>
<td class="doxyEnumItemDescription"></td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">GETDAGOP<a id="ac03d2cc4ff2a382b0eb7999ac9ff0ca3af1522bead6ac89c25ef351d3950e03ba"></a></td>
<td class="doxyEnumItemDescription"></td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">LOG2<a id="ac03d2cc4ff2a382b0eb7999ac9ff0ca3a0aee399f59c7ca285eca4e6f1de255f1"></a></td>
<td class="doxyEnumItemDescription"></td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">REPR<a id="ac03d2cc4ff2a382b0eb7999ac9ff0ca3a0a840f924ad0693584c5ca9f95d448cb"></a></td>
<td class="doxyEnumItemDescription"></td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">LISTFLATTEN<a id="ac03d2cc4ff2a382b0eb7999ac9ff0ca3afd91aabe29e5c4c63a79c21a5150261d"></a></td>
<td class="doxyEnumItemDescription"></td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">INITIALIZED<a id="ac03d2cc4ff2a382b0eb7999ac9ff0ca3a9997237fbfc2085ace20949b0cb8653f"></a></td>
<td class="doxyEnumItemDescription"></td>
</tr>

</table>
</dd>
</dl>

<p>Definition at line 844 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/tablegen/record-h">Record.h</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Public Constructors

### UnOpInit() {#ab2389d89fa4826927c27abdc525df338}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">llvm::UnOpInit::UnOpInit (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/unopinit">UnOpInit</a> &amp;)</td>
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



<p>Definition at line 867 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/tablegen/record-h">Record.h</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Private Constructors

### UnOpInit() {#a7d19c19a7294cf25dd96757925ea5e84}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">llvm::UnOpInit::UnOpInit (<a href="#ac03d2cc4ff2a382b0eb7999ac9ff0ca3">UnaryOp</a> opc, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/init">Init</a> * lhs, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/recty">RecTy</a> * Type)</td>
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



<p>Definition at line 863 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/tablegen/record-h">Record.h</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Public Operators

### operator=() {#a33924ccd636d4e2142d8a50c6ee09ea4}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">UnOpInit &amp; llvm::UnOpInit::operator= (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/unopinit">UnOpInit</a> &amp;)</td>
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



<p>Definition at line 868 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/tablegen/record-h">Record.h</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Public Member Functions

### Fold() {#af0e0cf8fa25dde613e92575630bb9475}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">const Init * UnOpInit::Fold (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/record">Record</a> * CurRec, bool IsFinal=false)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Declaration at line 883 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/tablegen/record-h">Record.h</a>, definition at line 835 of file <a href="/web-llvm/docs/api/files/lib/lib/tablegen/record-cpp">Record.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/silowercontrolflow-cpp/#a4868c5d81c5ccc98c47aeab6244346a0">assert</a>, <a href="#ac03d2cc4ff2a382b0eb7999ac9ff0ca3aab4ee971c2ba1beb7ed1700ae7955b79">CAST</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#ac4fc845f5ed92de63cd4474f128f5fc5">llvm::cast</a>, <a href="/web-llvm/docs/api/classes/llvm/init/#ab33fcbf534985fedfc7a1795aa54175b">llvm::Init::convertInitializerTo</a>, <a href="/web-llvm/docs/api/files/lib/lib/ir/builtingcs-cpp/#a6a9f043784cf87001c84980afa76da82">D</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a22eeee01734061ac1b31ccd994c49eef">llvm::dyn_cast</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a5f6182886dc2f96c204299e92c1565d5">llvm::dyn_cast_or_null</a>, <a href="#ac03d2cc4ff2a382b0eb7999ac9ff0ca3a99aa51ae9174f57bdf8b9a6688cfd3c8">EMPTY</a>, <a href="/web-llvm/docs/api/classes/llvm/intinit/#a1687f29bfe4a2532bf2351ce5fdba915">llvm::IntInit::get</a>, <a href="/web-llvm/docs/api/classes/llvm/intrecty/#a2540ed5217ebc374b948bf4a097d7c5b">llvm::IntRecTy::get</a>, <a href="/web-llvm/docs/api/classes/llvm/listinit/#a43379a4cffc2ed53c7bf95fe72e60454">llvm::ListInit::get</a>, <a href="/web-llvm/docs/api/classes/llvm/stringinit/#a63edb20ca7b47e34fcb1f8df74d6424f">llvm::StringInit::get</a>, <a href="/web-llvm/docs/api/classes/llvm/recty/#a7aa55697f48dc46c49a6f300bc2fdbe1">llvm::RecTy::getAsString</a>, <a href="#ae5510ac03650631d17eb8d28aeec63b9">getAsString</a>, <a href="#ac03d2cc4ff2a382b0eb7999ac9ff0ca3af1522bead6ac89c25ef351d3950e03ba">GETDAGOP</a>, <a href="/web-llvm/docs/api/classes/llvm/recordkeeper/#add572f2574d7922cdddd4f717a4e615b">llvm::RecordKeeper::getDef</a>, <a href="/web-llvm/docs/api/classes/llvm/record/#a1440b4c6fda0655f260750f386c9d92a">llvm::Record::getLoc</a>, <a href="/web-llvm/docs/api/classes/llvm/record/#af1d89cc30867b3edb73449f0577ec5b2">llvm::Record::getNameInit</a>, <a href="#a83abcaad6f9e99aa316e38329c8889b6">getOpcode</a>, <a href="/web-llvm/docs/api/classes/llvm/typedinit/#a8392de5e010c92649df6d559e702a694">llvm::TypedInit::getRecordKeeper</a>, <a href="/web-llvm/docs/api/classes/llvm/typedinit/#acdd9719e6d661022e6d5b1da9548c36e">llvm::TypedInit::getType</a>, <a href="#ac03d2cc4ff2a382b0eb7999ac9ff0ca3a33cba82be6410ca26755494a93351eff">HEAD</a>, <a href="#ac03d2cc4ff2a382b0eb7999ac9ff0ca3a9997237fbfc2085ace20949b0cb8653f">INITIALIZED</a>, <a href="/web-llvm/docs/api/files/include/include/llvm-c/datatypes-h/#ad0d744f05898e32d01f73f8af3cd2071">INT64_MAX</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a92ca992e52dddc420f4b069cae06dfbe">llvm::isa</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#acefe92adee8725ad904c7c43649790e8a4ee29ca12c7d126654bd0e5275de6135">llvm::List</a>, <a href="#ac03d2cc4ff2a382b0eb7999ac9ff0ca3afd91aabe29e5c4c63a79c21a5150261d">LISTFLATTEN</a>, <a href="#ac03d2cc4ff2a382b0eb7999ac9ff0ca3a0aee399f59c7ca285eca4e6f1de255f1">LOG2</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a4f42ed6fd2569fa43f03814a17f9d94a">llvm::Log2_64</a>, <a href="#ac03d2cc4ff2a382b0eb7999ac9ff0ca3abded462c3c8e85ef79327bab8f73efd6">NOT</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a2d33cbf73d16f36bdf9d289cf01d0006">llvm::PrintFatalError</a>, <a href="#ac03d2cc4ff2a382b0eb7999ac9ff0ca3a0a840f924ad0693584c5ca9f95d448cb">REPR</a>, <a href="#ac03d2cc4ff2a382b0eb7999ac9ff0ca3aa564303ab4af94485da6a68923fcdd51">SIZE</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/mips/mips16isellowering-cpp/#a0acb682b8260ab1c60b918599864e2e5">T</a>, <a href="#ac03d2cc4ff2a382b0eb7999ac9ff0ca3ae0e5d441bf3f167560d89d6e82535b5c">TAIL</a>, <a href="#ac03d2cc4ff2a382b0eb7999ac9ff0ca3aff10ccb4bdbd1a163a686db9886a24d6">TOLOWER</a>, <a href="#ac03d2cc4ff2a382b0eb7999ac9ff0ca3a1fb08e7386aec11ef074190d30afe284">TOUPPER</a> and <a href="/web-llvm/docs/api/classes/llvm/recty/#a23e3a41457328832976a6b1e66aa3906">llvm::RecTy::typeIsA</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/classes/llvm/typedinit/#abfdfeb6e9f368848e73a8eba175a99fb">llvm::TypedInit::getCastTo</a>.</p>

</div>
</div>

### getAsString() {#ae5510ac03650631d17eb8d28aeec63b9}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">std::string UnOpInit::getAsString ()</td>
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

<p>Convert this value to a literal form.</p>

<p>Declaration at line 887 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/tablegen/record-h">Record.h</a>, definition at line 1040 of file <a href="/web-llvm/docs/api/files/lib/lib/tablegen/record-cpp">Record.cpp</a>.</p>


<p>References <a href="#ac03d2cc4ff2a382b0eb7999ac9ff0ca3aab4ee971c2ba1beb7ed1700ae7955b79">CAST</a>, <a href="#ac03d2cc4ff2a382b0eb7999ac9ff0ca3a99aa51ae9174f57bdf8b9a6688cfd3c8">EMPTY</a>, <a href="/web-llvm/docs/api/classes/llvm/recty/#a7aa55697f48dc46c49a6f300bc2fdbe1">llvm::RecTy::getAsString</a>, <a href="#ac03d2cc4ff2a382b0eb7999ac9ff0ca3af1522bead6ac89c25ef351d3950e03ba">GETDAGOP</a>, <a href="#a83abcaad6f9e99aa316e38329c8889b6">getOpcode</a>, <a href="/web-llvm/docs/api/classes/llvm/typedinit/#acdd9719e6d661022e6d5b1da9548c36e">llvm::TypedInit::getType</a>, <a href="#ac03d2cc4ff2a382b0eb7999ac9ff0ca3a33cba82be6410ca26755494a93351eff">HEAD</a>, <a href="#ac03d2cc4ff2a382b0eb7999ac9ff0ca3a9997237fbfc2085ace20949b0cb8653f">INITIALIZED</a>, <a href="#ac03d2cc4ff2a382b0eb7999ac9ff0ca3afd91aabe29e5c4c63a79c21a5150261d">LISTFLATTEN</a>, <a href="#ac03d2cc4ff2a382b0eb7999ac9ff0ca3a0aee399f59c7ca285eca4e6f1de255f1">LOG2</a>, <a href="#ac03d2cc4ff2a382b0eb7999ac9ff0ca3abded462c3c8e85ef79327bab8f73efd6">NOT</a>, <a href="#ac03d2cc4ff2a382b0eb7999ac9ff0ca3a0a840f924ad0693584c5ca9f95d448cb">REPR</a>, <a href="#ac03d2cc4ff2a382b0eb7999ac9ff0ca3aa564303ab4af94485da6a68923fcdd51">SIZE</a>, <a href="#ac03d2cc4ff2a382b0eb7999ac9ff0ca3ae0e5d441bf3f167560d89d6e82535b5c">TAIL</a>, <a href="#ac03d2cc4ff2a382b0eb7999ac9ff0ca3aff10ccb4bdbd1a163a686db9886a24d6">TOLOWER</a> and <a href="#ac03d2cc4ff2a382b0eb7999ac9ff0ca3a1fb08e7386aec11ef074190d30afe284">TOUPPER</a>.</p>


<p>Referenced by <a href="#af0e0cf8fa25dde613e92575630bb9475">Fold</a>.</p>

</div>
</div>

### getOpcode() {#a83abcaad6f9e99aa316e38329c8889b6}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">UnaryOp llvm::UnOpInit::getOpcode ()</td>
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



<p>Definition at line 878 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/tablegen/record-h">Record.h</a>.</p>


<p>Reference <a href="/web-llvm/docs/api/classes/llvm/init/#a033dc74493053e93fde93554c95a288c">llvm::Init::Opc</a>.</p>


<p>Referenced by <a href="#af0e0cf8fa25dde613e92575630bb9475">Fold</a>, <a href="#ae5510ac03650631d17eb8d28aeec63b9">getAsString</a>, <a href="#ab3b5e79324a22bdea975e1a62aadcf9c">Profile</a> and <a href="#ac56f3b64a789146946b48afe5613c2f5">resolveReferences</a>.</p>

</div>
</div>

### getOperand() {#a01fed6c593b85eb1d4f759e40aa90b85}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">const Init * llvm::UnOpInit::getOperand ()</td>
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



<p>Definition at line 879 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/tablegen/record-h">Record.h</a>.</p>


<p>Referenced by <a href="#ab3b5e79324a22bdea975e1a62aadcf9c">Profile</a>.</p>

</div>
</div>

### Profile() {#ab3b5e79324a22bdea975e1a62aadcf9c}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void UnOpInit::Profile (<a href="/web-llvm/docs/api/classes/llvm/foldingsetnodeid">FoldingSetNodeID</a> &amp; ID)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Declaration at line 876 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/tablegen/record-h">Record.h</a>, definition at line 831 of file <a href="/web-llvm/docs/api/files/lib/lib/tablegen/record-cpp">Record.cpp</a>.</p>


<p>References <a href="#a83abcaad6f9e99aa316e38329c8889b6">getOpcode</a>, <a href="#a01fed6c593b85eb1d4f759e40aa90b85">getOperand</a>, <a href="/web-llvm/docs/api/classes/llvm/typedinit/#acdd9719e6d661022e6d5b1da9548c36e">llvm::TypedInit::getType</a> and <a href="/web-llvm/docs/api/files/lib/lib/tablegen/record-cpp/#abe73c09caaaa9cdcf4cc68e775757179">ProfileUnOpInit</a>.</p>

</div>
</div>

### resolveReferences() {#ac56f3b64a789146946b48afe5613c2f5}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">const Init * UnOpInit::resolveReferences (<a href="/web-llvm/docs/api/classes/llvm/resolver">Resolver</a> &amp; R)</td>
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

<p>This function is used by classes that refer to other variables which may not be defined at the time the expression is formed.</p>


<p>If a value is set for the variable later, this method will be called on users of the value to allow the value to propagate out.</p>


<p>Declaration at line 885 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/tablegen/record-h">Record.h</a>, definition at line 1031 of file <a href="/web-llvm/docs/api/files/lib/lib/tablegen/record-cpp">Record.cpp</a>.</p>


<p>References <a href="#ac03d2cc4ff2a382b0eb7999ac9ff0ca3aab4ee971c2ba1beb7ed1700ae7955b79">CAST</a>, <a href="#aa8ac284a20b1ea9f96469bf3d39d1f81">get</a>, <a href="#a83abcaad6f9e99aa316e38329c8889b6">getOpcode</a>, <a href="/web-llvm/docs/api/classes/llvm/typedinit/#acdd9719e6d661022e6d5b1da9548c36e">llvm::TypedInit::getType</a> and <a href="/web-llvm/docs/api/classes/llvm/init/#a00581957c4bb1587a458c3fbf4326f7a">llvm::Init::resolveReferences</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Private Member Attributes

### LHS {#a8786ae84665eea19052c101a4a453eb8}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">const Init* llvm::UnOpInit::LHS</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 861 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/tablegen/record-h">Record.h</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Public Static Functions

### classof() {#a7a41c91fce1ae50ec797b6f19106db17}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool llvm::UnOpInit::classof (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/init">Init</a> * I)</td>
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



<p>Definition at line 870 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/tablegen/record-h">Record.h</a>.</p>


<p>References <a href="/web-llvm/docs/api/files/lib/lib/support/md5-cpp/#ac0eafdc9ee161b71e7af98af736952fd">I</a> and <a href="/web-llvm/docs/api/classes/llvm/init/#a54e3c8e4571f5bf7daf2f792e4f1997eab695de26e5ff59ed2298833533d45a1b">llvm::Init::IK_UnOpInit</a>.</p>

</div>
</div>

### get() {#aa8ac284a20b1ea9f96469bf3d39d1f81}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">const UnOpInit * UnOpInit::get (<a href="#ac03d2cc4ff2a382b0eb7999ac9ff0ca3">UnaryOp</a> opc, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/init">Init</a> * lhs, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/recty">RecTy</a> * Type)</td>
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



<p>Declaration at line 874 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/tablegen/record-h">Record.h</a>, definition at line 817 of file <a href="/web-llvm/docs/api/files/lib/lib/tablegen/record-cpp">Record.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/structs/llvm/detail/recordkeeperimpl/#abc3aa7225f620417d5fb1e00b916c84c">llvm::detail::RecordKeeperImpl::Allocator</a>, <a href="/web-llvm/docs/api/files/lib/lib/support/md5-cpp/#ac0eafdc9ee161b71e7af98af736952fd">I</a>, <a href="/web-llvm/docs/api/classes/llvm/init/#a033dc74493053e93fde93554c95a288c">llvm::Init::Opc</a>, <a href="/web-llvm/docs/api/files/lib/lib/tablegen/record-cpp/#abe73c09caaaa9cdcf4cc68e775757179">ProfileUnOpInit</a> and <a href="/web-llvm/docs/api/structs/llvm/detail/recordkeeperimpl/#a7d3a1d7b1cdd5547d33b9573954e4ccc">llvm::detail::RecordKeeperImpl::TheUnOpInitPool</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/classes/llvm/typedinit/#abfdfeb6e9f368848e73a8eba175a99fb">llvm::TypedInit::getCastTo</a> and <a href="#ac56f3b64a789146946b48afe5613c2f5">resolveReferences</a>.</p>

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

<p class="doxyGeneratedBy">Generated via <a href="https://xpack.github.io/doxygen2docusaurus">doxygen2docusaurus</a> 2.0.0 by <a href="https://www.doxygen.nl">Doxygen</a> 1.15.0.</p>

</div>
