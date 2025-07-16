---

# DO NOT EDIT!
# Automatically generated via doxygen2docusaurus by Doxygen.

slug: /api/classes/llvm/binopinit
custom_edit_url: null
toc_max_heading_level: 4
keywords:
  - doxygen
  - reference
  - class

---

<div class="doxyPage">

# The `BinOpInit` Class Reference

<p>!op (X, Y) - Combine two inits. <a href="#details">More...</a></p>

## Declaration

<div class="doxyDeclaration">
class llvm::BinOpInit { ... }
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
<td class="doxyMemberIndexItemName" align="left" valign="top">BinaryOp : uint8_t { <a href="#a230d59e4f1bf22a18e10ef716378bc3a">...</a> }</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ada4cb2e44a5994818dcaaecc41576355">BinOpInit</a> (const BinOpInit &amp;)=delete</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a8644149800e1689ec1c8569edcdef61b">BinOpInit</a> (BinaryOp opc, const Init *lhs, const Init *rhs, const RecTy *Type)</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/binopinit">BinOpInit</a> &amp;</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a76d88d5e7e252d62455a057e3f6aceab">operator=</a> (const BinOpInit &amp;)=delete</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a3b5436bebef6bc757e1cdd29ce4131f0">Profile</a> (FoldingSetNodeID &amp;ID) const</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="#a230d59e4f1bf22a18e10ef716378bc3a">BinaryOp</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a74a17044f10f3fe747ea0d037e6b9085">getOpcode</a> () const</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a9175b6b98a5386ff669713e3921e0d24">getLHS</a> () const</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a803e39da63606020c081ef328a0b519e">getRHS</a> () const</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">std::optional&lt; bool &gt;</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a909a53b386dc20dfa36a2fb86d63ec36">CompareInit</a> (unsigned Opc, const Init *LHS, const Init *RHS) const</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#adbe242b084763cfdb35c7850bd4098b5">Fold</a> (const Record *CurRec) const</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a3b8eca57b47e415cd91ef858793a273f">resolveReferences</a> (Resolver &amp;R) const override</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>This function is used by classes that refer to other variables which may not be defined at the time the expression is formed. <a href="#a3b8eca57b47e415cd91ef858793a273f">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">std::string</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a5d801c7bc5e5db15b1a6ec6bc5035c17">getAsString</a> () const override</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Convert this value to a literal form. <a href="#a5d801c7bc5e5db15b1a6ec6bc5035c17">More...</a></p>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a619a354bd5364bca01dcb5ca8a8c2a61">LHS</a></td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ad7038fd9b8221740f6a9ac5f1dd2ba20">RHS</a></td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#aadbefbd58603b586e3f14f737a3a3513">classof</a> (const Init *I)</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">static <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/binopinit">BinOpInit</a> *</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a1717b7dc956fb447c4fd0a8ce3941b05">get</a> (BinaryOp opc, const Init *lhs, const Init *rhs, const RecTy *Type)</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">static <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/init">Init</a> *</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a540b4a99be94bc991bf4948b8f97e9bb">getStrConcat</a> (const Init *lhs, const Init *rhs)</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">static <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/init">Init</a> *</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ac7f6f688790cfbd57020c047cb467af7">getListConcat</a> (const TypedInit *lhs, const Init *rhs)</td>
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

<p>!op (X, Y) - Combine two inits.</p>

<p>Definition at line 891 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/tablegen/record-h">Record.h</a>.</p>


<div class="doxySectionDef">

## Enumerations

### BinaryOp {#a230d59e4f1bf22a18e10ef716378bc3a}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">enum llvm::BinOpInit::BinaryOp : uint8_t</td>
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
<td class="doxyEnumItemName">ADD<a id="a230d59e4f1bf22a18e10ef716378bc3aa9cba5c276fd2378d01ffd9bcf4613d86"></a></td>
<td class="doxyEnumItemDescription"></td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">SUB<a id="a230d59e4f1bf22a18e10ef716378bc3aa4ee9daa431b7f022fbe04156eb41cfda"></a></td>
<td class="doxyEnumItemDescription"></td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">MUL<a id="a230d59e4f1bf22a18e10ef716378bc3aa0aef6cb75f68082beb0493f3c625d51b"></a></td>
<td class="doxyEnumItemDescription"></td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">DIV<a id="a230d59e4f1bf22a18e10ef716378bc3aae0aae4e03c53f39dc2137b378178fca9"></a></td>
<td class="doxyEnumItemDescription"></td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">AND<a id="a230d59e4f1bf22a18e10ef716378bc3aa522cdb7f884d91e629dc391f336b8335"></a></td>
<td class="doxyEnumItemDescription"></td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">OR<a id="a230d59e4f1bf22a18e10ef716378bc3aa32d32b80ea1b0771948bbb9c278fd667"></a></td>
<td class="doxyEnumItemDescription"></td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">XOR<a id="a230d59e4f1bf22a18e10ef716378bc3aabb5b34d237f8c3e6e26edf918eac7a9b"></a></td>
<td class="doxyEnumItemDescription"></td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">SHL<a id="a230d59e4f1bf22a18e10ef716378bc3aa36bbc83b8a201db62e9a09ea31198390"></a></td>
<td class="doxyEnumItemDescription"></td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">SRA<a id="a230d59e4f1bf22a18e10ef716378bc3aac2ac5594d02bbb607ba28f8bdbdb81b7"></a></td>
<td class="doxyEnumItemDescription"></td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">SRL<a id="a230d59e4f1bf22a18e10ef716378bc3aaf0784a23764ddff84d580f8359dd7b9c"></a></td>
<td class="doxyEnumItemDescription"></td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">LISTCONCAT<a id="a230d59e4f1bf22a18e10ef716378bc3aa5b93deafe88e79a6ec1ff5274d52ce57"></a></td>
<td class="doxyEnumItemDescription"></td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">LISTSPLAT<a id="a230d59e4f1bf22a18e10ef716378bc3aa30665252c3d1a4d7d60b9b337f128058"></a></td>
<td class="doxyEnumItemDescription"></td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">LISTREMOVE<a id="a230d59e4f1bf22a18e10ef716378bc3aa6c01339d62afd64db871f1c401e0e868"></a></td>
<td class="doxyEnumItemDescription"></td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">LISTELEM<a id="a230d59e4f1bf22a18e10ef716378bc3aa4ce148031042dd5309e79b511d8c606c"></a></td>
<td class="doxyEnumItemDescription"></td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">LISTSLICE<a id="a230d59e4f1bf22a18e10ef716378bc3aac865bf004e53b9f0727dce22c7d8cbb1"></a></td>
<td class="doxyEnumItemDescription"></td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">RANGEC<a id="a230d59e4f1bf22a18e10ef716378bc3aaae136a842aaa052363499f02007d79ca"></a></td>
<td class="doxyEnumItemDescription"></td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">STRCONCAT<a id="a230d59e4f1bf22a18e10ef716378bc3aa958a422acb672d6187c96d6780f1adc0"></a></td>
<td class="doxyEnumItemDescription"></td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">INTERLEAVE<a id="a230d59e4f1bf22a18e10ef716378bc3aafec616d0c4028890d5b56244d107a485"></a></td>
<td class="doxyEnumItemDescription"></td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">CONCAT<a id="a230d59e4f1bf22a18e10ef716378bc3aafdd00230027b7ddbb9d855ececcf7da3"></a></td>
<td class="doxyEnumItemDescription"></td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">EQ<a id="a230d59e4f1bf22a18e10ef716378bc3aace80b63253cf19d5267ad26c18503382"></a></td>
<td class="doxyEnumItemDescription"></td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">NE<a id="a230d59e4f1bf22a18e10ef716378bc3aafe2dd433d87545224159e66fc2e24b1a"></a></td>
<td class="doxyEnumItemDescription"></td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">LE<a id="a230d59e4f1bf22a18e10ef716378bc3aa594510c0e55d1e8a21f0927d5506a9d7"></a></td>
<td class="doxyEnumItemDescription"></td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">LT<a id="a230d59e4f1bf22a18e10ef716378bc3aa5220187d6e2ff450325e956af659e8a2"></a></td>
<td class="doxyEnumItemDescription"></td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">GE<a id="a230d59e4f1bf22a18e10ef716378bc3aae1133238abe2d72246321cd3d1340b10"></a></td>
<td class="doxyEnumItemDescription"></td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">GT<a id="a230d59e4f1bf22a18e10ef716378bc3aafdffd22404898760e97ac31a77df5fdd"></a></td>
<td class="doxyEnumItemDescription"></td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">GETDAGARG<a id="a230d59e4f1bf22a18e10ef716378bc3aa0d7b3d49aa2a1e8caeb4f6e3f00ba486"></a></td>
<td class="doxyEnumItemDescription"></td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">GETDAGNAME<a id="a230d59e4f1bf22a18e10ef716378bc3aa1b01ea74804630ca76c4587df5d6c979"></a></td>
<td class="doxyEnumItemDescription"></td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">SETDAGOP<a id="a230d59e4f1bf22a18e10ef716378bc3aaaca9bb67122466883585f20f16c215ff"></a></td>
<td class="doxyEnumItemDescription"></td>
</tr>

</table>
</dd>
</dl>

<p>Definition at line 893 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/tablegen/record-h">Record.h</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Public Constructors

### BinOpInit() {#ada4cb2e44a5994818dcaaecc41576355}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">llvm::BinOpInit::BinOpInit (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/binopinit">BinOpInit</a> &amp;)</td>
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



<p>Definition at line 931 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/tablegen/record-h">Record.h</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Private Constructors

### BinOpInit() {#a8644149800e1689ec1c8569edcdef61b}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">llvm::BinOpInit::BinOpInit (<a href="#a230d59e4f1bf22a18e10ef716378bc3a">BinaryOp</a> opc, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/init">Init</a> * lhs, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/init">Init</a> * rhs, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/recty">RecTy</a> * Type)</td>
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



<p>Definition at line 927 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/tablegen/record-h">Record.h</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Public Operators

### operator=() {#a76d88d5e7e252d62455a057e3f6aceab}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">BinOpInit &amp; llvm::BinOpInit::operator= (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/binopinit">BinOpInit</a> &amp;)</td>
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



<p>Definition at line 932 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/tablegen/record-h">Record.h</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Public Member Functions

### CompareInit() {#a909a53b386dc20dfa36a2fb86d63ec36}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">std::optional&lt; bool &gt; BinOpInit::CompareInit (unsigned Opc, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/init">Init</a> * LHS, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/init">Init</a> * RHS)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Declaration at line 949 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/tablegen/record-h">Record.h</a>, definition at line 1177 of file <a href="/web-llvm/docs/api/files/lib/lib/tablegen/record-cpp">Record.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/namespaces/llvm/#a22eeee01734061ac1b31ccd994c49eef">llvm::dyn_cast</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a5f6182886dc2f96c204299e92c1565d5">llvm::dyn_cast_or_null</a>, <a href="#a230d59e4f1bf22a18e10ef716378bc3aace80b63253cf19d5267ad26c18503382">EQ</a>, <a href="#a230d59e4f1bf22a18e10ef716378bc3aae1133238abe2d72246321cd3d1340b10">GE</a>, <a href="/web-llvm/docs/api/classes/llvm/intrecty/#a2540ed5217ebc374b948bf4a097d7c5b">llvm::IntRecTy::get</a>, <a href="/web-llvm/docs/api/classes/llvm/typedinit/#a8392de5e010c92649df6d559e702a694">llvm::TypedInit::getRecordKeeper</a>, <a href="#a230d59e4f1bf22a18e10ef716378bc3aafdffd22404898760e97ac31a77df5fdd">GT</a>, <a href="#a230d59e4f1bf22a18e10ef716378bc3aa594510c0e55d1e8a21f0927d5506a9d7">LE</a>, <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/support/errorhandling-h/#ace243f5c25697a1107cce46626b3dc94">llvm_unreachable</a>, <a href="#a230d59e4f1bf22a18e10ef716378bc3aa5220187d6e2ff450325e956af659e8a2">LT</a>, <a href="#a230d59e4f1bf22a18e10ef716378bc3aafe2dd433d87545224159e66fc2e24b1a">NE</a> and <a href="/web-llvm/docs/api/classes/llvm/init/#a033dc74493053e93fde93554c95a288c">llvm::Init::Opc</a>.</p>


<p>Referenced by <a href="#adbe242b084763cfdb35c7850bd4098b5">Fold</a>.</p>

</div>
</div>

### Fold() {#adbe242b084763cfdb35c7850bd4098b5}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">const Init * BinOpInit::Fold (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/record">Record</a> * CurRec)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Declaration at line 954 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/tablegen/record-h">Record.h</a>, definition at line 1287 of file <a href="/web-llvm/docs/api/files/lib/lib/tablegen/record-cpp">Record.cpp</a>.</p>


<p>References <a href="#a230d59e4f1bf22a18e10ef716378bc3aa9cba5c276fd2378d01ffd9bcf4613d86">ADD</a>, <a href="#a230d59e4f1bf22a18e10ef716378bc3aa522cdb7f884d91e629dc391f336b8335">AND</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a39d3d23a084c4544ee5903203db10e8a">llvm::append_range</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/silowercontrolflow-cpp/#a4868c5d81c5ccc98c47aeab6244346a0">assert</a>, <a href="#a909a53b386dc20dfa36a2fb86d63ec36">CompareInit</a>, <a href="#a230d59e4f1bf22a18e10ef716378bc3aafdd00230027b7ddbb9d855ececcf7da3">CONCAT</a>, <a href="/web-llvm/docs/api/files/lib/lib/tablegen/record-cpp/#a3eb03bef656ad82043fbb7742038dba2">ConcatStringInits</a>, <a href="#a230d59e4f1bf22a18e10ef716378bc3aae0aae4e03c53f39dc2137b378178fca9">DIV</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a22eeee01734061ac1b31ccd994c49eef">llvm::dyn_cast</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a5f6182886dc2f96c204299e92c1565d5">llvm::dyn_cast_or_null</a>, <a href="#a230d59e4f1bf22a18e10ef716378bc3aace80b63253cf19d5267ad26c18503382">EQ</a>, <a href="#a230d59e4f1bf22a18e10ef716378bc3aae1133238abe2d72246321cd3d1340b10">GE</a>, <a href="/web-llvm/docs/api/classes/llvm/bitinit/#a783941ee3db6dc99f068008ebca36a55">llvm::BitInit::get</a>, <a href="/web-llvm/docs/api/classes/llvm/daginit/#a8068bfe8ffd6450e61e72665e6887abc">llvm::DagInit::get</a>, <a href="/web-llvm/docs/api/classes/llvm/intinit/#a1687f29bfe4a2532bf2351ce5fdba915">llvm::IntInit::get</a>, <a href="/web-llvm/docs/api/classes/llvm/intrecty/#a2540ed5217ebc374b948bf4a097d7c5b">llvm::IntRecTy::get</a>, <a href="/web-llvm/docs/api/classes/llvm/listinit/#a43379a4cffc2ed53c7bf95fe72e60454">llvm::ListInit::get</a>, <a href="/web-llvm/docs/api/classes/llvm/unsetinit/#acb3d05f3711c0d2090e0c20ad9a7ffbd">llvm::UnsetInit::get</a>, <a href="#a230d59e4f1bf22a18e10ef716378bc3aa0d7b3d49aa2a1e8caeb4f6e3f00ba486">GETDAGARG</a>, <a href="/web-llvm/docs/api/files/lib/lib/tablegen/record-cpp/#a27d10be0c551c20cfa23ab3bd627ac11">getDagArgNoByKey</a>, <a href="#a230d59e4f1bf22a18e10ef716378bc3aa1b01ea74804630ca76c4587df5d6c979">GETDAGNAME</a>, <a href="/web-llvm/docs/api/classes/llvm/record/#a1440b4c6fda0655f260750f386c9d92a">llvm::Record::getLoc</a>, <a href="#a74a17044f10f3fe747ea0d037e6b9085">getOpcode</a>, <a href="/web-llvm/docs/api/classes/llvm/typedinit/#a8392de5e010c92649df6d559e702a694">llvm::TypedInit::getRecordKeeper</a>, <a href="/web-llvm/docs/api/classes/llvm/typedinit/#acdd9719e6d661022e6d5b1da9548c36e">llvm::TypedInit::getType</a>, <a href="/web-llvm/docs/api/classes/llvm/value/#a0344a49526443edf90cc0aef3abd3337">llvm::Value::getType</a>, <a href="#a230d59e4f1bf22a18e10ef716378bc3aafdffd22404898760e97ac31a77df5fdd">GT</a>, <a href="/web-llvm/docs/api/files/lib/lib/support/md5-cpp/#ac0eafdc9ee161b71e7af98af736952fd">I</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/nvptx/nvvmintrrange-cpp/#ac5804672fc0850438d63caec770647f8">II</a>, <a href="/web-llvm/docs/api/files/include/include/llvm-c/datatypes-h/#ab21f12f372f67b8ff0aa3432336ede67">INT64_MIN</a>, <a href="#a230d59e4f1bf22a18e10ef716378bc3aafec616d0c4028890d5b56244d107a485">INTERLEAVE</a>, <a href="/web-llvm/docs/api/files/lib/lib/tablegen/record-cpp/#af0eb0dadf7ba9a14e87659d331e08dd7">interleaveIntList</a>, <a href="/web-llvm/docs/api/files/lib/lib/tablegen/record-cpp/#a992db0fd61c3d017f025ef8ca64827cc">interleaveStringList</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a92ca992e52dddc420f4b069cae06dfbe">llvm::isa</a>, <a href="#a230d59e4f1bf22a18e10ef716378bc3aa594510c0e55d1e8a21f0927d5506a9d7">LE</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#acefe92adee8725ad904c7c43649790e8a4ee29ca12c7d126654bd0e5275de6135">llvm::List</a>, <a href="#a230d59e4f1bf22a18e10ef716378bc3aa5b93deafe88e79a6ec1ff5274d52ce57">LISTCONCAT</a>, <a href="#a230d59e4f1bf22a18e10ef716378bc3aa4ce148031042dd5309e79b511d8c606c">LISTELEM</a>, <a href="#a230d59e4f1bf22a18e10ef716378bc3aa6c01339d62afd64db871f1c401e0e868">LISTREMOVE</a>, <a href="#a230d59e4f1bf22a18e10ef716378bc3aac865bf004e53b9f0727dce22c7d8cbb1">LISTSLICE</a>, <a href="#a230d59e4f1bf22a18e10ef716378bc3aa30665252c3d1a4d7d60b9b337f128058">LISTSPLAT</a>, <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/support/errorhandling-h/#ace243f5c25697a1107cce46626b3dc94">llvm_unreachable</a>, <a href="#a230d59e4f1bf22a18e10ef716378bc3aa5220187d6e2ff450325e956af659e8a2">LT</a>, <a href="#a230d59e4f1bf22a18e10ef716378bc3aa0aef6cb75f68082beb0493f3c625d51b">MUL</a>, <a href="#a230d59e4f1bf22a18e10ef716378bc3aafe2dd433d87545224159e66fc2e24b1a">NE</a>, <a href="#a230d59e4f1bf22a18e10ef716378bc3aa32d32b80ea1b0771948bbb9c278fd667">OR</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a37310d4cb640733ed81281942c314d05">llvm::PrintError</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a2d33cbf73d16f36bdf9d289cf01d0006">llvm::PrintFatalError</a>, <a href="/web-llvm/docs/api/classes/llvm/smallvectortemplatebase/#af42bfbc067df27c19ee2fc859df58799">llvm::SmallVectorTemplateBase&lt; T, bool &gt;::push_back</a>, <a href="#a230d59e4f1bf22a18e10ef716378bc3aaae136a842aaa052363499f02007d79ca">RANGEC</a>, <a href="#a230d59e4f1bf22a18e10ef716378bc3aaaca9bb67122466883585f20f16c215ff">SETDAGOP</a>, <a href="#a230d59e4f1bf22a18e10ef716378bc3aa36bbc83b8a201db62e9a09ea31198390">SHL</a>, <a href="/web-llvm/docs/api/files/lib/lib/analysis/inlineorder-cpp/#a7ee6f0cb51c3b9056199e9a0001fe8c3a6f6cb72d544962fa333e2e34ce64f719">Size</a>, <a href="#a230d59e4f1bf22a18e10ef716378bc3aac2ac5594d02bbb607ba28f8bdbdb81b7">SRA</a>, <a href="#a230d59e4f1bf22a18e10ef716378bc3aaf0784a23764ddff84d580f8359dd7b9c">SRL</a>, <a href="#a230d59e4f1bf22a18e10ef716378bc3aa958a422acb672d6187c96d6780f1adc0">STRCONCAT</a>, <a href="#a230d59e4f1bf22a18e10ef716378bc3aa4ee9daa431b7f022fbe04156eb41cfda">SUB</a> and <a href="#a230d59e4f1bf22a18e10ef716378bc3aabb5b34d237f8c3e6e26edf918eac7a9b">XOR</a>.</p>

</div>
</div>

### getAsString() {#a5d801c7bc5e5db15b1a6ec6bc5035c17}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">std::string BinOpInit::getAsString ()</td>
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

<p>Declaration at line 958 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/tablegen/record-h">Record.h</a>, definition at line 1580 of file <a href="/web-llvm/docs/api/files/lib/lib/tablegen/record-cpp">Record.cpp</a>.</p>


<p>References <a href="#a230d59e4f1bf22a18e10ef716378bc3aa9cba5c276fd2378d01ffd9bcf4613d86">ADD</a>, <a href="#a230d59e4f1bf22a18e10ef716378bc3aa522cdb7f884d91e629dc391f336b8335">AND</a>, <a href="#a230d59e4f1bf22a18e10ef716378bc3aafdd00230027b7ddbb9d855ececcf7da3">CONCAT</a>, <a href="#a230d59e4f1bf22a18e10ef716378bc3aae0aae4e03c53f39dc2137b378178fca9">DIV</a>, <a href="#a230d59e4f1bf22a18e10ef716378bc3aace80b63253cf19d5267ad26c18503382">EQ</a>, <a href="#a230d59e4f1bf22a18e10ef716378bc3aae1133238abe2d72246321cd3d1340b10">GE</a>, <a href="/web-llvm/docs/api/classes/llvm/recty/#a7aa55697f48dc46c49a6f300bc2fdbe1">llvm::RecTy::getAsString</a>, <a href="#a230d59e4f1bf22a18e10ef716378bc3aa0d7b3d49aa2a1e8caeb4f6e3f00ba486">GETDAGARG</a>, <a href="#a230d59e4f1bf22a18e10ef716378bc3aa1b01ea74804630ca76c4587df5d6c979">GETDAGNAME</a>, <a href="#a74a17044f10f3fe747ea0d037e6b9085">getOpcode</a>, <a href="/web-llvm/docs/api/classes/llvm/typedinit/#acdd9719e6d661022e6d5b1da9548c36e">llvm::TypedInit::getType</a>, <a href="#a230d59e4f1bf22a18e10ef716378bc3aafdffd22404898760e97ac31a77df5fdd">GT</a>, <a href="#a230d59e4f1bf22a18e10ef716378bc3aafec616d0c4028890d5b56244d107a485">INTERLEAVE</a>, <a href="#a230d59e4f1bf22a18e10ef716378bc3aa594510c0e55d1e8a21f0927d5506a9d7">LE</a>, <a href="#a230d59e4f1bf22a18e10ef716378bc3aa5b93deafe88e79a6ec1ff5274d52ce57">LISTCONCAT</a>, <a href="#a230d59e4f1bf22a18e10ef716378bc3aa4ce148031042dd5309e79b511d8c606c">LISTELEM</a>, <a href="#a230d59e4f1bf22a18e10ef716378bc3aa6c01339d62afd64db871f1c401e0e868">LISTREMOVE</a>, <a href="#a230d59e4f1bf22a18e10ef716378bc3aac865bf004e53b9f0727dce22c7d8cbb1">LISTSLICE</a>, <a href="#a230d59e4f1bf22a18e10ef716378bc3aa30665252c3d1a4d7d60b9b337f128058">LISTSPLAT</a>, <a href="#a230d59e4f1bf22a18e10ef716378bc3aa5220187d6e2ff450325e956af659e8a2">LT</a>, <a href="#a230d59e4f1bf22a18e10ef716378bc3aa0aef6cb75f68082beb0493f3c625d51b">MUL</a>, <a href="#a230d59e4f1bf22a18e10ef716378bc3aafe2dd433d87545224159e66fc2e24b1a">NE</a>, <a href="#a230d59e4f1bf22a18e10ef716378bc3aa32d32b80ea1b0771948bbb9c278fd667">OR</a>, <a href="#a230d59e4f1bf22a18e10ef716378bc3aaae136a842aaa052363499f02007d79ca">RANGEC</a>, <a href="#a230d59e4f1bf22a18e10ef716378bc3aaaca9bb67122466883585f20f16c215ff">SETDAGOP</a>, <a href="#a230d59e4f1bf22a18e10ef716378bc3aa36bbc83b8a201db62e9a09ea31198390">SHL</a>, <a href="#a230d59e4f1bf22a18e10ef716378bc3aac2ac5594d02bbb607ba28f8bdbdb81b7">SRA</a>, <a href="#a230d59e4f1bf22a18e10ef716378bc3aaf0784a23764ddff84d580f8359dd7b9c">SRL</a>, <a href="#a230d59e4f1bf22a18e10ef716378bc3aa958a422acb672d6187c96d6780f1adc0">STRCONCAT</a>, <a href="#a230d59e4f1bf22a18e10ef716378bc3aa4ee9daa431b7f022fbe04156eb41cfda">SUB</a> and <a href="#a230d59e4f1bf22a18e10ef716378bc3aabb5b34d237f8c3e6e26edf918eac7a9b">XOR</a>.</p>

</div>
</div>

### getLHS() {#a9175b6b98a5386ff669713e3921e0d24}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">const Init * llvm::BinOpInit::getLHS ()</td>
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



<p>Definition at line 946 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/tablegen/record-h">Record.h</a>.</p>


<p>Referenced by <a href="#a3b5436bebef6bc757e1cdd29ce4131f0">Profile</a>.</p>

</div>
</div>

### getOpcode() {#a74a17044f10f3fe747ea0d037e6b9085}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">BinaryOp llvm::BinOpInit::getOpcode ()</td>
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



<p>Definition at line 945 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/tablegen/record-h">Record.h</a>.</p>


<p>Reference <a href="/web-llvm/docs/api/classes/llvm/init/#a033dc74493053e93fde93554c95a288c">llvm::Init::Opc</a>.</p>


<p>Referenced by <a href="#adbe242b084763cfdb35c7850bd4098b5">Fold</a>, <a href="#a5d801c7bc5e5db15b1a6ec6bc5035c17">getAsString</a>, <a href="#a3b5436bebef6bc757e1cdd29ce4131f0">Profile</a> and <a href="#a3b8eca57b47e415cd91ef858793a273f">resolveReferences</a>.</p>

</div>
</div>

### getRHS() {#a803e39da63606020c081ef328a0b519e}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">const Init * llvm::BinOpInit::getRHS ()</td>
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



<p>Definition at line 947 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/tablegen/record-h">Record.h</a>.</p>


<p>Referenced by <a href="#a3b5436bebef6bc757e1cdd29ce4131f0">Profile</a>.</p>

</div>
</div>

### Profile() {#a3b5436bebef6bc757e1cdd29ce4131f0}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void BinOpInit::Profile (<a href="/web-llvm/docs/api/classes/llvm/foldingsetnodeid">FoldingSetNodeID</a> &amp; ID)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Declaration at line 943 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/tablegen/record-h">Record.h</a>, definition at line 1094 of file <a href="/web-llvm/docs/api/files/lib/lib/tablegen/record-cpp">Record.cpp</a>.</p>


<p>References <a href="#a9175b6b98a5386ff669713e3921e0d24">getLHS</a>, <a href="#a74a17044f10f3fe747ea0d037e6b9085">getOpcode</a>, <a href="#a803e39da63606020c081ef328a0b519e">getRHS</a>, <a href="/web-llvm/docs/api/classes/llvm/typedinit/#acdd9719e6d661022e6d5b1da9548c36e">llvm::TypedInit::getType</a> and <a href="/web-llvm/docs/api/files/lib/lib/tablegen/record-cpp/#a298cb81f4bf2eb8cd9c5bd8b2324647d">ProfileBinOpInit</a>.</p>

</div>
</div>

### resolveReferences() {#a3b8eca57b47e415cd91ef858793a273f}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">const Init * BinOpInit::resolveReferences (<a href="/web-llvm/docs/api/classes/llvm/resolver">Resolver</a> &amp; R)</td>
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


<p>Declaration at line 956 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/tablegen/record-h">Record.h</a>, definition at line 1553 of file <a href="/web-llvm/docs/api/files/lib/lib/tablegen/record-cpp">Record.cpp</a>.</p>


<p>References <a href="#a230d59e4f1bf22a18e10ef716378bc3aa522cdb7f884d91e629dc391f336b8335">AND</a>, <a href="/web-llvm/docs/api/classes/llvm/init/#ab33fcbf534985fedfc7a1795aa54175b">llvm::Init::convertInitializerTo</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a5f6182886dc2f96c204299e92c1565d5">llvm::dyn_cast_or_null</a>, <a href="#a1717b7dc956fb447c4fd0a8ce3941b05">get</a>, <a href="/web-llvm/docs/api/classes/llvm/intrecty/#a2540ed5217ebc374b948bf4a097d7c5b">llvm::IntRecTy::get</a>, <a href="#a74a17044f10f3fe747ea0d037e6b9085">getOpcode</a>, <a href="/web-llvm/docs/api/classes/llvm/typedinit/#a8392de5e010c92649df6d559e702a694">llvm::TypedInit::getRecordKeeper</a>, <a href="/web-llvm/docs/api/classes/llvm/typedinit/#acdd9719e6d661022e6d5b1da9548c36e">llvm::TypedInit::getType</a>, <a href="/web-llvm/docs/api/classes/llvm/init/#a033dc74493053e93fde93554c95a288c">llvm::Init::Opc</a>, <a href="#a230d59e4f1bf22a18e10ef716378bc3aa32d32b80ea1b0771948bbb9c278fd667">OR</a> and <a href="/web-llvm/docs/api/classes/llvm/init/#a00581957c4bb1587a458c3fbf4326f7a">llvm::Init::resolveReferences</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Private Member Attributes

### LHS {#a619a354bd5364bca01dcb5ca8a8c2a61}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">const Init* llvm::BinOpInit::LHS</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 925 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/tablegen/record-h">Record.h</a>.</p>

</div>
</div>

### RHS {#ad7038fd9b8221740f6a9ac5f1dd2ba20}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">const Init * llvm::BinOpInit::RHS</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 925 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/tablegen/record-h">Record.h</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Public Static Functions

### classof() {#aadbefbd58603b586e3f14f737a3a3513}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool llvm::BinOpInit::classof (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/init">Init</a> * I)</td>
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



<p>Definition at line 934 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/tablegen/record-h">Record.h</a>.</p>


<p>References <a href="/web-llvm/docs/api/files/lib/lib/support/md5-cpp/#ac0eafdc9ee161b71e7af98af736952fd">I</a> and <a href="/web-llvm/docs/api/classes/llvm/init/#a54e3c8e4571f5bf7daf2f792e4f1997ea93fa5283ed205e13f03d8a255ac7f36b">llvm::Init::IK_BinOpInit</a>.</p>

</div>
</div>

### get() {#a1717b7dc956fb447c4fd0a8ce3941b05}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">const BinOpInit * BinOpInit::get (<a href="#a230d59e4f1bf22a18e10ef716378bc3a">BinaryOp</a> opc, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/init">Init</a> * lhs, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/init">Init</a> * rhs, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/recty">RecTy</a> * Type)</td>
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



<p>Declaration at line 938 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/tablegen/record-h">Record.h</a>, definition at line 1079 of file <a href="/web-llvm/docs/api/files/lib/lib/tablegen/record-cpp">Record.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/structs/llvm/detail/recordkeeperimpl/#abc3aa7225f620417d5fb1e00b916c84c">llvm::detail::RecordKeeperImpl::Allocator</a>, <a href="/web-llvm/docs/api/files/lib/lib/support/md5-cpp/#ac0eafdc9ee161b71e7af98af736952fd">I</a>, <a href="/web-llvm/docs/api/classes/llvm/init/#a033dc74493053e93fde93554c95a288c">llvm::Init::Opc</a>, <a href="/web-llvm/docs/api/files/lib/lib/tablegen/record-cpp/#a298cb81f4bf2eb8cd9c5bd8b2324647d">ProfileBinOpInit</a> and <a href="/web-llvm/docs/api/structs/llvm/detail/recordkeeperimpl/#a31064463a9e071281b851e026f38dd09">llvm::detail::RecordKeeperImpl::TheBinOpInitPool</a>.</p>


<p>Referenced by <a href="#ac7f6f688790cfbd57020c047cb467af7">getListConcat</a>, <a href="#a540b4a99be94bc991bf4948b8f97e9bb">getStrConcat</a> and <a href="#a3b8eca57b47e415cd91ef858793a273f">resolveReferences</a>.</p>

</div>
</div>

### getListConcat() {#ac7f6f688790cfbd57020c047cb467af7}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">const Init * BinOpInit::getListConcat (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/typedinit">TypedInit</a> * lhs, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/init">Init</a> * rhs)</td>
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



<p>Declaration at line 941 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/tablegen/record-h">Record.h</a>, definition at line 1167 of file <a href="/web-llvm/docs/api/files/lib/lib/tablegen/record-cpp">Record.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/silowercontrolflow-cpp/#a4868c5d81c5ccc98c47aeab6244346a0">assert</a>, <a href="/web-llvm/docs/api/files/lib/lib/tablegen/record-cpp/#a73ac2b1804a613362a20bd325329c87f">ConcatListInits</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a22eeee01734061ac1b31ccd994c49eef">llvm::dyn_cast</a>, <a href="#a1717b7dc956fb447c4fd0a8ce3941b05">get</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a92ca992e52dddc420f4b069cae06dfbe">llvm::isa</a> and <a href="#a230d59e4f1bf22a18e10ef716378bc3aa5b93deafe88e79a6ec1ff5274d52ce57">LISTCONCAT</a>.</p>

</div>
</div>

### getStrConcat() {#a540b4a99be94bc991bf4948b8f97e9bb}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">const Init * BinOpInit::getStrConcat (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/init">Init</a> * lhs, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/init">Init</a> * rhs)</td>
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



<p>Declaration at line 940 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/tablegen/record-h">Record.h</a>, definition at line 1150 of file <a href="/web-llvm/docs/api/files/lib/lib/tablegen/record-cpp">Record.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/files/lib/lib/tablegen/record-cpp/#a3eb03bef656ad82043fbb7742038dba2">ConcatStringInits</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a22eeee01734061ac1b31ccd994c49eef">llvm::dyn_cast</a>, <a href="#a1717b7dc956fb447c4fd0a8ce3941b05">get</a>, <a href="/web-llvm/docs/api/classes/llvm/stringrecty/#ad4b14749b521864736b5f40898f0a43a">llvm::StringRecTy::get</a>, <a href="/web-llvm/docs/api/classes/llvm/init/#aceb63812efd39ed325fc5579b10213f3">llvm::Init::getRecordKeeper</a> and <a href="#a230d59e4f1bf22a18e10ef716378bc3aa958a422acb672d6187c96d6780f1adc0">STRCONCAT</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/files/lib/lib/tablegen/tgparser-cpp/#a678066d868a6e0abb3151be33bb7232e">QualifyName</a>.</p>

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

<p class="doxyGeneratedBy">Generated via <a href="https://github.com/xpack/doxygen2docusaurus">doxygen2docusaurus</a> by <a href="https://www.doxygen.nl">Doxygen</a> 1.15.0.</p>

</div>
