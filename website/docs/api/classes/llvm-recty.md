---

# DO NOT EDIT!
# Automatically generated via doxygen2docusaurus by Doxygen.

slug: /api/classes/llvm/recty
custom_edit_url: null
toc_max_heading_level: 4
keywords:
  - doxygen
  - reference
  - class

---

<div class="doxyPage">

# The `RecTy` Class Reference



## Declaration

<div class="doxyDeclaration">
class llvm::RecTy { ... }
</div>

## Included Headers

<div class="doxyIncludesList">#include "<a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/tablegen/record-h">llvm/TableGen/Record.h</a>"
</div>

## Derived Classes

<table class="doxyMembersIndex">

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">class</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/bitrecty">BitRecTy</a></td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>'bit' - Represent a single bit <a href="/web-llvm/docs/api/classes/llvm/bitrecty/#details">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">class</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/bitsrecty">BitsRecTy</a></td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>'bits&lt;n&gt;' - Represent a fixed number of bits <a href="/web-llvm/docs/api/classes/llvm/bitsrecty/#details">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">class</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/dagrecty">DagRecTy</a></td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>'dag' - Represent a dag fragment <a href="/web-llvm/docs/api/classes/llvm/dagrecty/#details">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">class</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/intrecty">IntRecTy</a></td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>'int' - Represent an integer value of no particular size <a href="/web-llvm/docs/api/classes/llvm/intrecty/#details">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">class</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/listrecty">ListRecTy</a></td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>'list&lt;Ty&gt;' - Represent a list of element values, all of which must be of the specified type. <a href="/web-llvm/docs/api/classes/llvm/listrecty/#details">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">class</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/recordrecty">RecordRecTy</a></td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>'[classname]' - <a href="/web-llvm/docs/api/classes/llvm/type">Type</a> of record values that have zero or more superclasses. <a href="/web-llvm/docs/api/classes/llvm/recordrecty/#details">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">class</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/stringrecty">StringRecTy</a></td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>'string' - Represent an string value <a href="/web-llvm/docs/api/classes/llvm/stringrecty/#details">More...</a></p>
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
<td class="doxyMemberIndexItemName" align="left" valign="top">RecTyKind { <a href="#a49953f670acd87339563c3ea7716f07d">...</a> }</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Subclass discriminator (for dyn_cast&lt;&gt; et al.) <a href="#a49953f670acd87339563c3ea7716f07d">More...</a></p>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a6de9b82387c10021fbe937b3e52bd9f3">RecTy</a> (RecTyKind K, RecordKeeper &amp;RK)</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ac9be9d80acf843fb5738b6665a3d52ba">~RecTy</a> ()=default</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="#a49953f670acd87339563c3ea7716f07d">RecTyKind</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a9894d44bbb655ddbc92eec56c53111b4">getRecTyKind</a> () const</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/recordkeeper">RecordKeeper</a> &amp;</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a18724be9882f42a3a6de8a53951f2646">getRecordKeeper</a> () const</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Return the <a href="/web-llvm/docs/api/classes/llvm/recordkeeper">RecordKeeper</a> that uniqued this <a href="/web-llvm/docs/api/classes/llvm/type">Type</a>. <a href="#a18724be9882f42a3a6de8a53951f2646">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">std::string</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a7aa55697f48dc46c49a6f300bc2fdbe1">getAsString</a> () const =0</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#af1d585b91ac3c4ec4176c17f8393f0c6">print</a> (raw_ostream &amp;OS) const</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ac08f7b9bc62aa901700eef03da46e0e2">dump</a> () const</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a28ff8427d52e8183da03e65ad86a16a3">typeIsConvertibleTo</a> (const RecTy *RHS) const</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Return true if all values of 'this' type can be converted to the specified type. <a href="#a28ff8427d52e8183da03e65ad86a16a3">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">bool</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a23e3a41457328832976a6b1e66aa3906">typeIsA</a> (const RecTy *RHS) const</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Return true if 'this' type is equal to or a subtype of RHS. <a href="#a23e3a41457328832976a6b1e66aa3906">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/listrecty">ListRecTy</a> *</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ae14ece8a218b77b8099cf25498cd88df">getListTy</a> () const</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Returns the type representing list&lt;thistype&gt;. <a href="#ae14ece8a218b77b8099cf25498cd88df">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

</table>

## Private Member Attributes Index

<table class="doxyMembersIndex">

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="#a49953f670acd87339563c3ea7716f07d">RecTyKind</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a0e85a91dbcaca644c62da61a5987baea">Kind</a></td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/recordkeeper">RecordKeeper</a> &amp;</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a8f88b7d315c3f6e1897e98f750437810">RK</a></td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>The <a href="/web-llvm/docs/api/classes/llvm/recordkeeper">RecordKeeper</a> that uniqued this <a href="/web-llvm/docs/api/classes/llvm/type">Type</a>. <a href="#a8f88b7d315c3f6e1897e98f750437810">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/listrecty">ListRecTy</a> *</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ab421261cdc647312b7cc2b7a7f725a4c">ListTy</a> = nullptr</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p><a href="/web-llvm/docs/api/classes/llvm/listrecty">ListRecTy</a> of the list that has elements of this type. <a href="#ab421261cdc647312b7cc2b7a7f725a4c">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

</table>


<p>Definition at line 60 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/tablegen/record-h">Record.h</a>.</p>


<div class="doxySectionDef">

## Enumerations

### RecTyKind {#a49953f670acd87339563c3ea7716f07d}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">enum llvm::RecTy::RecTyKind </td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Subclass discriminator (for dyn_cast&lt;&gt; et al.)</p>

<dl class="doxyEnumList">
<dt class="doxyEnumTableTitle">Enumeration values</dt>
<dd>
<table class="doxyEnumTable">

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">BitRecTyKind<a id="a49953f670acd87339563c3ea7716f07daf1d5e2e84e2ab3bee666d2fa92aaccf8"></a></td>
<td class="doxyEnumItemDescription"></td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">BitsRecTyKind<a id="a49953f670acd87339563c3ea7716f07daccd899f53a22271bc819022c83c8d4b7"></a></td>
<td class="doxyEnumItemDescription"></td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">IntRecTyKind<a id="a49953f670acd87339563c3ea7716f07dad618f0a45a62c5b48dae9cf044f865ad"></a></td>
<td class="doxyEnumItemDescription"></td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">StringRecTyKind<a id="a49953f670acd87339563c3ea7716f07dae90be69532328534a4a90dc14ef2348d"></a></td>
<td class="doxyEnumItemDescription"></td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">ListRecTyKind<a id="a49953f670acd87339563c3ea7716f07da5d0dc5db84fdc8b39afa900fe973cf46"></a></td>
<td class="doxyEnumItemDescription"></td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">DagRecTyKind<a id="a49953f670acd87339563c3ea7716f07dad078692c46283deb0591f1138d409073"></a></td>
<td class="doxyEnumItemDescription"></td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">RecordRecTyKind<a id="a49953f670acd87339563c3ea7716f07da2fd621bf3ff3925ebb021c8a21f2c9f4"></a></td>
<td class="doxyEnumItemDescription"></td>
</tr>

</table>
</dd>
</dl>

<p>Definition at line 63 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/tablegen/record-h">Record.h</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Public Constructors

### RecTy() {#a6de9b82387c10021fbe937b3e52bd9f3}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">llvm::RecTy::RecTy (<a href="#a49953f670acd87339563c3ea7716f07d">RecTyKind</a> K, <a href="/web-llvm/docs/api/classes/llvm/recordkeeper">RecordKeeper</a> &amp; RK)</td>
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



<p>Definition at line 82 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/tablegen/record-h">Record.h</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/classes/llvm/bitrecty/#a10fc79959cefd39ad6adf316d2422e3c">llvm::BitRecTy::classof</a>, <a href="/web-llvm/docs/api/classes/llvm/bitsrecty/#a53d22a3844f4363e2c19964512dfda0a">llvm::BitsRecTy::classof</a>, <a href="/web-llvm/docs/api/classes/llvm/dagrecty/#abc2077c57a2695b2763c293b2a334507">llvm::DagRecTy::classof</a>, <a href="/web-llvm/docs/api/classes/llvm/intrecty/#af35edaec8367a4040379b6b8056044ae">llvm::IntRecTy::classof</a>, <a href="/web-llvm/docs/api/classes/llvm/listrecty/#a159a259f0593280fabe44881063363c8">llvm::ListRecTy::classof</a>, <a href="/web-llvm/docs/api/classes/llvm/recordrecty/#af381176703e7971128f8ae8a8ed6c228">llvm::RecordRecTy::classof</a>, <a href="/web-llvm/docs/api/classes/llvm/stringrecty/#a4589967500ac611518c098427f89e8b3">llvm::StringRecTy::classof</a>, <a href="/web-llvm/docs/api/classes/llvm/listrecty/#a7b1aee7f3d5b878a43d1e323a448111c">llvm::ListRecTy::get</a>, <a href="/web-llvm/docs/api/classes/llvm/listrecty/#a104574cc6d0a1015f0d1ec0aad8778a3">llvm::ListRecTy::getElementType</a>, <a href="/web-llvm/docs/api/classes/llvm/recordrecty/#a697483987cfb91e205b5be2a8f6752c7">llvm::RecordRecTy::Record</a>, <a href="/web-llvm/docs/api/classes/llvm/listrecty/#ae4f475332861f1f8a3d808661f51096a">llvm::ListRecTy::RecTy::getListTy</a>, <a href="/web-llvm/docs/api/classes/llvm/listrecty/#a2f7d6945bc0d35fdad873ace0368c6e8">llvm::ListRecTy::typeIsA</a>, <a href="/web-llvm/docs/api/classes/llvm/recordrecty/#ae6271d4724a3de32d5ae16687e15d9f4">llvm::RecordRecTy::typeIsA</a>, <a href="#a23e3a41457328832976a6b1e66aa3906">typeIsA</a>, <a href="/web-llvm/docs/api/classes/llvm/bitrecty/#aa1b8fc94cbdd470db35dd86a269405b5">llvm::BitRecTy::typeIsConvertibleTo</a>, <a href="/web-llvm/docs/api/classes/llvm/bitsrecty/#a26af9ff0b126b032c3c230aa0b0c0ff8">llvm::BitsRecTy::typeIsConvertibleTo</a>, <a href="/web-llvm/docs/api/classes/llvm/intrecty/#a7d363350502d10ca54385ae7a112ea20">llvm::IntRecTy::typeIsConvertibleTo</a>, <a href="/web-llvm/docs/api/classes/llvm/listrecty/#aa54318ab59a8e0b754082df2a2e073fe">llvm::ListRecTy::typeIsConvertibleTo</a>, <a href="/web-llvm/docs/api/classes/llvm/recordrecty/#a07654f780f26ed3415d59969c16e6aa9">llvm::RecordRecTy::typeIsConvertibleTo</a>, <a href="#a28ff8427d52e8183da03e65ad86a16a3">typeIsConvertibleTo</a> and <a href="/web-llvm/docs/api/classes/llvm/stringrecty/#afbb99fb474c35ba655560d371196402a">llvm::StringRecTy::typeIsConvertibleTo</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Public Destructor

### \~RecTy() {#ac9be9d80acf843fb5738b6665a3d52ba}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">virtual llvm::RecTy::~RecTy ()</td>
</tr>
</table>
</td>
<td class="doxyMemberLabelsRight">
<span class="doxyMemberLabels">
<span class="doxyMemberLabel virtual">virtual</span>
<span class="doxyMemberLabel default">default</span>
</span>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 83 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/tablegen/record-h">Record.h</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Public Member Functions

### dump() {#ac08f7b9bc62aa901700eef03da46e0e2}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">LLVM_DUMP_METHOD void RecTy::dump ()</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Declaration at line 92 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/tablegen/record-h">Record.h</a>, definition at line 137 of file <a href="/web-llvm/docs/api/files/lib/lib/tablegen/record-cpp">Record.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/namespaces/llvm/#a9a7b5c68c90f85baaedaa854cc5002cc">llvm::errs</a>, <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/support/compiler-h/#aa863693eef567397d9c292da5bf22d34">LLVM_DUMP_METHOD</a> and <a href="#af1d585b91ac3c4ec4176c17f8393f0c6">print</a>.</p>

</div>
</div>

### getAsString() {#a7aa55697f48dc46c49a6f300bc2fdbe1}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">virtual std::string llvm::RecTy::getAsString ()</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 90 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/tablegen/record-h">Record.h</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/classes/llvm/unopinit/#af0e0cf8fa25dde613e92575630bb9475">llvm::UnOpInit::Fold</a>, <a href="/web-llvm/docs/api/classes/llvm/binopinit/#a5d801c7bc5e5db15b1a6ec6bc5035c17">llvm::BinOpInit::getAsString</a>, <a href="/web-llvm/docs/api/classes/llvm/unopinit/#ae5510ac03650631d17eb8d28aeec63b9">llvm::UnOpInit::getAsString</a> and <a href="#af1d585b91ac3c4ec4176c17f8393f0c6">print</a>.</p>

</div>
</div>

### getListTy() {#ae14ece8a218b77b8099cf25498cd88df}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">const ListRecTy * RecTy::getListTy ()</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Returns the type representing list&lt;thistype&gt;.</p>

<p>Declaration at line 103 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/tablegen/record-h">Record.h</a>, definition at line 140 of file <a href="/web-llvm/docs/api/files/lib/lib/tablegen/record-cpp">Record.cpp</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/namespaces/llvm/#ade4b1e4b6d6b9605eca98ac01e8a1931">llvm::resolveTypes</a>.</p>

</div>
</div>

### getRecordKeeper() {#a18724be9882f42a3a6de8a53951f2646}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">RecordKeeper &amp; llvm::RecTy::getRecordKeeper ()</td>
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

<p>Return the <a href="/web-llvm/docs/api/classes/llvm/recordkeeper">RecordKeeper</a> that uniqued this <a href="/web-llvm/docs/api/classes/llvm/type">Type</a>.</p>

<p>Definition at line 88 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/tablegen/record-h">Record.h</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/classes/llvm/listinit/#a43379a4cffc2ed53c7bf95fe72e60454">llvm::ListInit::get</a> and <a href="/web-llvm/docs/api/classes/llvm/listrecty/#ae4f475332861f1f8a3d808661f51096a">llvm::ListRecTy::RecTy::getListTy</a>.</p>

</div>
</div>

### getRecTyKind() {#a9894d44bbb655ddbc92eec56c53111b4}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">RecTyKind llvm::RecTy::getRecTyKind ()</td>
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



<p>Definition at line 85 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/tablegen/record-h">Record.h</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/classes/llvm/bitrecty/#a10fc79959cefd39ad6adf316d2422e3c">llvm::BitRecTy::classof</a>, <a href="/web-llvm/docs/api/classes/llvm/bitsrecty/#a53d22a3844f4363e2c19964512dfda0a">llvm::BitsRecTy::classof</a>, <a href="/web-llvm/docs/api/classes/llvm/dagrecty/#abc2077c57a2695b2763c293b2a334507">llvm::DagRecTy::classof</a>, <a href="/web-llvm/docs/api/classes/llvm/intrecty/#af35edaec8367a4040379b6b8056044ae">llvm::IntRecTy::classof</a>, <a href="/web-llvm/docs/api/classes/llvm/listrecty/#a159a259f0593280fabe44881063363c8">llvm::ListRecTy::classof</a>, <a href="/web-llvm/docs/api/classes/llvm/recordrecty/#af381176703e7971128f8ae8a8ed6c228">llvm::RecordRecTy::classof</a> and <a href="/web-llvm/docs/api/classes/llvm/stringrecty/#a4589967500ac611518c098427f89e8b3">llvm::StringRecTy::classof</a>.</p>

</div>
</div>

### print() {#af1d585b91ac3c4ec4176c17f8393f0c6}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void llvm::RecTy::print (<a href="/web-llvm/docs/api/classes/llvm/raw-ostream">raw_ostream</a> &amp; OS)</td>
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



<p>Definition at line 91 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/tablegen/record-h">Record.h</a>.</p>


<p>Reference <a href="#a7aa55697f48dc46c49a6f300bc2fdbe1">getAsString</a>.</p>


<p>Referenced by <a href="#ac08f7b9bc62aa901700eef03da46e0e2">dump</a>.</p>

</div>
</div>

### typeIsA() {#a23e3a41457328832976a6b1e66aa3906}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool RecTy::typeIsA (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/recty">RecTy</a> * RHS)</td>
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

<p>Return true if 'this' type is equal to or a subtype of RHS.</p>


<p>For example, a bit set is not an int, but they are convertible.</p>


<p>Declaration at line 100 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/tablegen/record-h">Record.h</a>, definition at line 151 of file <a href="/web-llvm/docs/api/files/lib/lib/tablegen/record-cpp">Record.cpp</a>.</p>


<p>Reference <a href="#a6de9b82387c10021fbe937b3e52bd9f3">RecTy</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/classes/llvm/unopinit/#af0e0cf8fa25dde613e92575630bb9475">llvm::UnOpInit::Fold</a> and <a href="/web-llvm/docs/api/classes/llvm/listrecty/#a2f7d6945bc0d35fdad873ace0368c6e8">llvm::ListRecTy::typeIsA</a>.</p>

</div>
</div>

### typeIsConvertibleTo() {#a28ff8427d52e8183da03e65ad86a16a3}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool RecTy::typeIsConvertibleTo (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/recty">RecTy</a> * RHS)</td>
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

<p>Return true if all values of 'this' type can be converted to the specified type.</p>

<p>Declaration at line 96 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/tablegen/record-h">Record.h</a>, definition at line 146 of file <a href="/web-llvm/docs/api/files/lib/lib/tablegen/record-cpp">Record.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/silowercontrolflow-cpp/#a4868c5d81c5ccc98c47aeab6244346a0">assert</a> and <a href="#a6de9b82387c10021fbe937b3e52bd9f3">RecTy</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/classes/llvm/bitrecty/#aa1b8fc94cbdd470db35dd86a269405b5">llvm::BitRecTy::typeIsConvertibleTo</a> and <a href="/web-llvm/docs/api/classes/llvm/bitsrecty/#a26af9ff0b126b032c3c230aa0b0c0ff8">llvm::BitsRecTy::typeIsConvertibleTo</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Private Member Attributes

### Kind {#a0e85a91dbcaca644c62da61a5987baea}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">RecTyKind llvm::RecTy::Kind</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 74 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/tablegen/record-h">Record.h</a>.</p>

</div>
</div>

### ListTy {#ab421261cdc647312b7cc2b7a7f725a4c}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">const ListRecTy* llvm::RecTy::ListTy = nullptr</td>
</tr>
</table>
</td>
<td class="doxyMemberLabelsRight">
<span class="doxyMemberLabels">
<span class="doxyMemberLabel mutable">mutable</span>
</span>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p><a href="/web-llvm/docs/api/classes/llvm/listrecty">ListRecTy</a> of the list that has elements of this type.</p>


<p>Its a cache that is populated on demand.</p>


<p>Definition at line 79 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/tablegen/record-h">Record.h</a>.</p>

</div>
</div>

### RK {#a8f88b7d315c3f6e1897e98f750437810}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">RecordKeeper&amp; llvm::RecTy::RK</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>The <a href="/web-llvm/docs/api/classes/llvm/recordkeeper">RecordKeeper</a> that uniqued this <a href="/web-llvm/docs/api/classes/llvm/type">Type</a>.</p>

<p>Definition at line 76 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/tablegen/record-h">Record.h</a>.</p>

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
