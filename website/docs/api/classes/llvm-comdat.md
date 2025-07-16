---

# DO NOT EDIT!
# Automatically generated via doxygen2docusaurus by Doxygen.

slug: /api/classes/llvm/comdat
custom_edit_url: null
toc_max_heading_level: 4
keywords:
  - doxygen
  - reference
  - class

---

<div class="doxyPage">

# The `Comdat` Class Reference



## Declaration

<div class="doxyDeclaration">
class llvm::Comdat { ... }
</div>

## Included Headers

<div class="doxyIncludesList">#include "<a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/ir/comdat-h">llvm/IR/Comdat.h</a>"
</div>

## Enumerations Index

<table class="doxyMembersIndex">

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">enum</td>
<td class="doxyMemberIndexItemName" align="left" valign="top">SelectionKind { <a href="#ab40cbf8243fad70968f9ecf82f48a035">...</a> }</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a21f639900c480510650969df9c74d17d">Module</a></td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ac177bc079fe0a6e9b3d3115702db3bc3">GlobalObject</a></td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a043e6f44e1cfe8d486c9c26a243b644a">Comdat</a> (const Comdat &amp;)=delete</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a54acbfbb862d3db746e219159bd2520d">Comdat</a> (Comdat &amp;&amp;C)</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a14c3bc360111810f571802f3b5d42f84">Comdat</a> ()</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="#ab40cbf8243fad70968f9ecf82f48a035">SelectionKind</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#afad14be926fcf2e071f21f178f99c28d">getSelectionKind</a> () const</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ad8e5834e05be0104c4d64a3b4edeb51b">setSelectionKind</a> (SelectionKind Val)</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/stringref">StringRef</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a699b34b3b6301ffc6632c7c6f643b96a">getName</a> () const</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a56cb601c486724c2c35a0c99db7a6c1e">print</a> (raw_ostream &amp;OS, bool IsForDebug=false) const</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a91e83c8a019bcde0518af21a79396a42">dump</a> () const</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/smallptrsetimpl">SmallPtrSetImpl</a>&lt; <a href="/web-llvm/docs/api/classes/llvm/globalobject">GlobalObject</a> * &gt; &amp;</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a9598f370d4b11aa2ec3944f5e373ecf2">getUsers</a> () const</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">void</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a76334781fcb6707962232f64d5219a30">addUser</a> (GlobalObject *GO)</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#af291b53540df8cb96ebb5badaf800ea1">removeUser</a> (GlobalObject *GO)</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/stringmapentry">StringMapEntry</a>&lt; <a href="/web-llvm/docs/api/classes/llvm/comdat">Comdat</a> &gt; *</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ad6a41799097c51b56ffb6e75261a49d4">Name</a> = nullptr</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="#ab40cbf8243fad70968f9ecf82f48a035">SelectionKind</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a881f4ba346092df04e72e90bfff315f4">SK</a> = <a href="/web-llvm/docs/api/classes/llvm/any">Any</a></td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/smallptrset">SmallPtrSet</a>&lt; <a href="/web-llvm/docs/api/classes/llvm/globalobject">GlobalObject</a> *, 2 &gt;</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a9f2334a64047acabb465417e092d7340">Users</a></td>
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


<p>Definition at line 33 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/ir/comdat-h">Comdat.h</a>.</p>


<div class="doxySectionDef">

## Enumerations

### SelectionKind {#ab40cbf8243fad70968f9ecf82f48a035}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">enum llvm::Comdat::SelectionKind </td>
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
<td class="doxyEnumItemName">Any<a id="ab40cbf8243fad70968f9ecf82f48a035a8c4ae4df3d085db275a58182612ff3be"></a></td>
<td class="doxyEnumItemDescription">The linker may choose any COMDAT</td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">ExactMatch<a id="ab40cbf8243fad70968f9ecf82f48a035acceb065ea69a5e06e80bd6ceddd7b9a7"></a></td>
<td class="doxyEnumItemDescription">The data referenced by the COMDAT must be the same</td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">Largest<a id="ab40cbf8243fad70968f9ecf82f48a035a2444b05a47619decc80c2ce0cc224dc8"></a></td>
<td class="doxyEnumItemDescription">The linker will choose the largest COMDAT</td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">NoDeduplicate<a id="ab40cbf8243fad70968f9ecf82f48a035ab2d0d4bc9ba11b7324f5ffc20a9dc37a"></a></td>
<td class="doxyEnumItemDescription">No deduplication is performed</td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">SameSize<a id="ab40cbf8243fad70968f9ecf82f48a035a8b148d3d05688ddb23b7abb81527b7ce"></a></td>
<td class="doxyEnumItemDescription">The data referenced by the COMDAT must be the same size</td>
</tr>

</table>
</dd>
</dl>

<p>Definition at line 35 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/ir/comdat-h">Comdat.h</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Friends

### GlobalObject {#ac177bc079fe0a6e9b3d3115702db3bc3}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">friend class <a href="/web-llvm/docs/api/classes/llvm/globalobject">GlobalObject</a></td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">


<p>Definition at line 55 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/ir/comdat-h">Comdat.h</a>.</p>


<p>References <a href="#ab40cbf8243fad70968f9ecf82f48a035a8c4ae4df3d085db275a58182612ff3be">Any</a> and <a href="#ac177bc079fe0a6e9b3d3115702db3bc3">GlobalObject</a>.</p>


<p>Referenced by <a href="#ac177bc079fe0a6e9b3d3115702db3bc3">GlobalObject</a>.</p>

</div>
</div>

### Module {#a21f639900c480510650969df9c74d17d}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">friend class <a href="/web-llvm/docs/api/classes/llvm/module">Module</a></td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">


<p>Definition at line 54 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/ir/comdat-h">Comdat.h</a>.</p>


<p>Reference <a href="#a21f639900c480510650969df9c74d17d">Module</a>.</p>


<p>Referenced by <a href="#a21f639900c480510650969df9c74d17d">Module</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Public Constructors

### Comdat() {#a043e6f44e1cfe8d486c9c26a243b644a}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">llvm::Comdat::Comdat (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/comdat">Comdat</a> &amp;)</td>
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



<p>Definition at line 43 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/ir/comdat-h">Comdat.h</a>.</p>


<p>References <a href="/web-llvm/docs/api/namespaces/llvm/callingconv/#ac6aa1387c4375260e2468eb5a77fdb4cafd841a49aec1539bc88abc8ff9e170fb">llvm::CallingConv::C</a> and <a href="#a043e6f44e1cfe8d486c9c26a243b644a">Comdat</a>.</p>


<p>Referenced by <a href="#a54acbfbb862d3db746e219159bd2520d">Comdat</a> and <a href="#a043e6f44e1cfe8d486c9c26a243b644a">Comdat</a>.</p>

</div>
</div>

### Comdat() {#a54acbfbb862d3db746e219159bd2520d}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">Comdat::Comdat (<a href="/web-llvm/docs/api/classes/llvm/comdat">Comdat</a> &amp;&amp; C)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Declaration at line 44 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/ir/comdat-h">Comdat.h</a>, definition at line 24 of file <a href="/web-llvm/docs/api/files/lib/lib/ir/comdat-cpp">Comdat.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/namespaces/llvm/callingconv/#ac6aa1387c4375260e2468eb5a77fdb4cafd841a49aec1539bc88abc8ff9e170fb">llvm::CallingConv::C</a> and <a href="#a043e6f44e1cfe8d486c9c26a243b644a">Comdat</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Private Constructors

### Comdat() {#a14c3bc360111810f571802f3b5d42f84}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">Comdat::Comdat ()</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 57 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/ir/comdat-h">Comdat.h</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Public Member Functions

### dump() {#a91e83c8a019bcde0518af21a79396a42}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">LLVM_DUMP_METHOD void Comdat::dump ()</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Declaration at line 50 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/ir/comdat-h">Comdat.h</a>, definition at line 5330 of file <a href="/web-llvm/docs/api/files/lib/lib/ir/asmwriter-cpp">AsmWriter.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/namespaces/llvm/#a7c46c742c31be54870e2038048e6b391">llvm::dbgs</a> and <a href="/web-llvm/docs/api/files/lib/lib/object/archivewriter-cpp/#aa9f638c7ae7fdd206a6c60e26bef9751">print</a>.</p>

</div>
</div>

### getName() {#a699b34b3b6301ffc6632c7c6f643b96a}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">StringRef Comdat::getName ()</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Declaration at line 48 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/ir/comdat-h">Comdat.h</a>, definition at line 28 of file <a href="/web-llvm/docs/api/files/lib/lib/ir/comdat-cpp">Comdat.cpp</a>.</p>

</div>
</div>

### getSelectionKind() {#afad14be926fcf2e071f21f178f99c28d}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">SelectionKind llvm::Comdat::getSelectionKind ()</td>
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



<p>Definition at line 46 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/ir/comdat-h">Comdat.h</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/files/lib/lib/codegen/loweremutls-cpp/#a101d392f12933ec345c1cef1f552809e">copyLinkageVisibility</a> and <a href="#a56cb601c486724c2c35a0c99db7a6c1e">print</a>.</p>

</div>
</div>

### getUsers() {#a9598f370d4b11aa2ec3944f5e373ecf2}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">const SmallPtrSetImpl&lt; GlobalObject * &gt; &amp; llvm::Comdat::getUsers ()</td>
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



<p>Definition at line 51 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/ir/comdat-h">Comdat.h</a>.</p>

</div>
</div>

### print() {#a56cb601c486724c2c35a0c99db7a6c1e}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void Comdat::print (<a href="/web-llvm/docs/api/classes/llvm/raw-ostream">raw_ostream</a> &amp; OS, bool IsForDebug=false)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Declaration at line 49 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/ir/comdat-h">Comdat.h</a>, definition at line 4944 of file <a href="/web-llvm/docs/api/files/lib/lib/ir/asmwriter-cpp">AsmWriter.cpp</a>.</p>


<p>References <a href="#ab40cbf8243fad70968f9ecf82f48a035a8c4ae4df3d085db275a58182612ff3be">Any</a>, <a href="/web-llvm/docs/api/files/lib/lib/ir/asmwriter-cpp/#aec73ab739d6b324c9753c7071afd6c2faef4db6f596a5ad992a85da3510c31c48">ComdatPrefix</a>, <a href="#ab40cbf8243fad70968f9ecf82f48a035acceb065ea69a5e06e80bd6ceddd7b9a7">ExactMatch</a>, <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/objcarc/provenanceanalysisevaluator-cpp/#a2ee79648e8bce3ddbb26358ff10e3e82">getName</a>, <a href="#afad14be926fcf2e071f21f178f99c28d">getSelectionKind</a>, <a href="#ab40cbf8243fad70968f9ecf82f48a035a2444b05a47619decc80c2ce0cc224dc8">Largest</a>, <a href="#ab40cbf8243fad70968f9ecf82f48a035ab2d0d4bc9ba11b7324f5ffc20a9dc37a">NoDeduplicate</a>, <a href="/web-llvm/docs/api/files/lib/lib/ir/asmwriter-cpp/#a3d6e60a917bf5f4052dbb2673f11e087">PrintLLVMName</a> and <a href="#ab40cbf8243fad70968f9ecf82f48a035a8b148d3d05688ddb23b7abb81527b7ce">SameSize</a>.</p>

</div>
</div>

### setSelectionKind() {#ad8e5834e05be0104c4d64a3b4edeb51b}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void llvm::Comdat::setSelectionKind (<a href="#ab40cbf8243fad70968f9ecf82f48a035">SelectionKind</a> Val)</td>
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



<p>Definition at line 47 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/ir/comdat-h">Comdat.h</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/utils/clonemodule-cpp/#a04b8f04da3f1b0bf1c9a2802f73e2d05">copyComdat</a>, <a href="/web-llvm/docs/api/files/lib/lib/codegen/loweremutls-cpp/#a101d392f12933ec345c1cef1f552809e">copyLinkageVisibility</a>, <a href="/web-llvm/docs/api/groups/llvmccorecomdat/#ga770da47f1db21be71881a94b5842a808">LLVMSetComdatSelectionKind</a> and <a href="/web-llvm/docs/api/structs/anonymous-wholeprogramdevirt-cpp-/devirtmodule/#ae9f4748bfea60c7f38b8a1f4357b0150">anonymous{WholeProgramDevirt.cpp}::DevirtModule::trySingleImplDevirt</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Private Member Functions

### addUser() {#a76334781fcb6707962232f64d5219a30}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void Comdat::addUser (<a href="/web-llvm/docs/api/classes/llvm/globalobject">GlobalObject</a> * GO)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Declaration at line 58 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/ir/comdat-h">Comdat.h</a>, definition at line 30 of file <a href="/web-llvm/docs/api/files/lib/lib/ir/comdat-cpp">Comdat.cpp</a>.</p>

</div>
</div>

### removeUser() {#af291b53540df8cb96ebb5badaf800ea1}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void Comdat::removeUser (<a href="/web-llvm/docs/api/classes/llvm/globalobject">GlobalObject</a> * GO)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Declaration at line 59 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/ir/comdat-h">Comdat.h</a>, definition at line 32 of file <a href="/web-llvm/docs/api/files/lib/lib/ir/comdat-cpp">Comdat.cpp</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Private Member Attributes

### Name {#ad6a41799097c51b56ffb6e75261a49d4}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">StringMapEntry&lt;Comdat&gt;* llvm::Comdat::Name = nullptr</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 62 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/ir/comdat-h">Comdat.h</a>.</p>

</div>
</div>

### SK {#a881f4ba346092df04e72e90bfff315f4}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">SelectionKind llvm::Comdat::SK = <a href="/web-llvm/docs/api/classes/llvm/any">Any</a></td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 63 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/ir/comdat-h">Comdat.h</a>.</p>

</div>
</div>

### Users {#a9f2334a64047acabb465417e092d7340}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">SmallPtrSet&lt;GlobalObject *, 2&gt; llvm::Comdat::Users</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 65 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/ir/comdat-h">Comdat.h</a>.</p>

</div>
</div>

</div>

<hr/>

The documentation for this class was generated from the following files:

<ul>
<li><a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/ir/comdat-h">Comdat.h</a></li>
<li><a href="/web-llvm/docs/api/files/lib/lib/ir/asmwriter-cpp">AsmWriter.cpp</a></li>
<li><a href="/web-llvm/docs/api/files/lib/lib/ir/comdat-cpp">Comdat.cpp</a></li>
</ul>

<hr/>

<p class="doxyGeneratedBy">Generated via <a href="https://github.com/xpack/doxygen2docusaurus">doxygen2docusaurus</a> by <a href="https://www.doxygen.nl">Doxygen</a> 1.15.0.</p>

</div>
