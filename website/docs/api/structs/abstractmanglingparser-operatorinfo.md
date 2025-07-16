---

# DO NOT EDIT!
# Automatically generated via doxygen2docusaurus by Doxygen.

slug: /api/structs/abstractmanglingparser/operatorinfo
custom_edit_url: null
toc_max_heading_level: 4
keywords:
  - doxygen
  - reference
  - struct

---

<div class="doxyPage">

# The `OperatorInfo` Struct Reference



## Declaration

<div class="doxyDeclaration">
struct AbstractManglingParser::OperatorInfo { ... }
</div>

## Included Headers

<div class="doxyIncludesList">#include "<a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/demangle/itaniumdemangle-h">llvm/Demangle/ItaniumDemangle.h</a>"
</div>

## Enumerations Index

<table class="doxyMembersIndex">

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">enum</td>
<td class="doxyMemberIndexItemName" align="left" valign="top">OIKind : unsigned char { <a href="#aafe8a42a8411e57f7e90ed1b1fcbd0a7">...</a> }</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">constexpr</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a457eef7dd9ed96f5be3310083f08a0ac">OperatorInfo</a> (const char(&amp;E)[3], OIKind K, bool F, Node::Prec P, const char *N)</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">bool</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#aaa21930c91442bbce8f2c74f9f945a4d">operator&lt;</a> (const OperatorInfo &amp;Other) const</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ad1a7825f2762f06ff8e55364f37e5705">operator&lt;</a> (const char *Peek) const</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ac6781a0b48ac43ac1221921367ddc6fa">operator==</a> (const char *Peek) const</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#accc685ee230b975afdac79d4bd9da8d3">operator!=</a> (const char *Peek) const</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">std::string_view</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#aeed1fbd4f82f1bc9c4ada7ce9835edb7">getSymbol</a> () const</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">std::string_view</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#aadf6cc286d694f0a332d72aa3ad6b121">getName</a> () const</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="#aafe8a42a8411e57f7e90ed1b1fcbd0a7">OIKind</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a8980eec0726dbc16e294875ee745d429">getKind</a> () const</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a969e625604f64730a3a9ebb77841500f">getFlag</a> () const</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/node/#aa85c347c913d5d69761682997e60220b">Node::Prec</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a833f0b876264ebdec33723d0b006835e">getPrecedence</a> () const</td>
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

## Public Member Attributes Index

<table class="doxyMembersIndex">

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">char</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a5f7a662ebbcb6e1f4383300952107663">Enc</a>[2]</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="#aafe8a42a8411e57f7e90ed1b1fcbd0a7">OIKind</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a00c30c007b21b1b668323b77f73b1ccd">Kind</a></td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a4c19071eaa1b2220d2cd94dc4e1fe4f9">Flag</a></td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/node/#aa85c347c913d5d69761682997e60220b">Node::Prec</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ad0bf5a0fc6c1e57e5b6bb32fb26c1424">Prec</a></td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ab185185df3c482db7ac04c6102b57b22">Name</a></td>
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


<p>Definition at line 2962 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/demangle/itaniumdemangle-h">ItaniumDemangle.h</a>.</p>


<div class="doxySectionDef">

## Enumerations

### OIKind {#aafe8a42a8411e57f7e90ed1b1fcbd0a7}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">enum AbstractManglingParser::OperatorInfo::OIKind : unsigned char</td>
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
<td class="doxyEnumItemName">Prefix<a id="aafe8a42a8411e57f7e90ed1b1fcbd0a7a433cbf2e47751906275610c69911564f"></a></td>
<td class="doxyEnumItemDescription"></td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">Postfix<a id="aafe8a42a8411e57f7e90ed1b1fcbd0a7a38e71f87e3a772db24bb8ac2bf2b5266"></a></td>
<td class="doxyEnumItemDescription"></td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">Binary<a id="aafe8a42a8411e57f7e90ed1b1fcbd0a7a3ec036af4b1d3fb2d5d01b2609079d26"></a></td>
<td class="doxyEnumItemDescription"></td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">Array<a id="aafe8a42a8411e57f7e90ed1b1fcbd0a7a1c5a6bdc17969975557376df54a1f3fe"></a></td>
<td class="doxyEnumItemDescription"></td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">Member<a id="aafe8a42a8411e57f7e90ed1b1fcbd0a7a33bf2208b2c609d6d2dc569cfa879fdd"></a></td>
<td class="doxyEnumItemDescription"></td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">New<a id="aafe8a42a8411e57f7e90ed1b1fcbd0a7a157a47aaf824edda98811cfc0169be06"></a></td>
<td class="doxyEnumItemDescription"></td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">Del<a id="aafe8a42a8411e57f7e90ed1b1fcbd0a7abd5ae9124fe4a8f5d2f58d3c33f71216"></a></td>
<td class="doxyEnumItemDescription"></td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">Call<a id="aafe8a42a8411e57f7e90ed1b1fcbd0a7a6abf7dc083c709c6a96a34b77bf1967f"></a></td>
<td class="doxyEnumItemDescription"></td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">CCast<a id="aafe8a42a8411e57f7e90ed1b1fcbd0a7a82810709402fac6d09282fe7fa8b67ab"></a></td>
<td class="doxyEnumItemDescription"></td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">Conditional<a id="aafe8a42a8411e57f7e90ed1b1fcbd0a7a0d3c1740500bb5a83638a2d5b78b26de"></a></td>
<td class="doxyEnumItemDescription"></td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">NameOnly<a id="aafe8a42a8411e57f7e90ed1b1fcbd0a7ac599331c223b8dd2e853d9a7d6c6c66a"></a></td>
<td class="doxyEnumItemDescription"></td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">NamedCast<a id="aafe8a42a8411e57f7e90ed1b1fcbd0a7a8045981e92d3b85c5ae925bcee4708df"></a></td>
<td class="doxyEnumItemDescription"></td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">OfIdOp<a id="aafe8a42a8411e57f7e90ed1b1fcbd0a7a104bd83845d4703c8afd6b355f0a51e8"></a></td>
<td class="doxyEnumItemDescription"></td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">Unnameable<a id="aafe8a42a8411e57f7e90ed1b1fcbd0a7ac65df57a19d87c23245c988c0caefc8a"></a></td>
<td class="doxyEnumItemDescription"> (= NamedCast)</td>
</tr>

</table>
</dd>
</dl>

<p>Definition at line 2963 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/demangle/itaniumdemangle-h">ItaniumDemangle.h</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Public Constructors

### OperatorInfo() {#a457eef7dd9ed96f5be3310083f08a0ac}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">AbstractManglingParser&lt; Derived, Alloc &gt;::OperatorInfo::OperatorInfo (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> char(&amp;) E=[3], <a href="#aafe8a42a8411e57f7e90ed1b1fcbd0a7">OIKind</a> K, bool F, <a href="/web-llvm/docs/api/classes/node/#aa85c347c913d5d69761682997e60220b">Node::Prec</a> P, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> char * N)</td>
</tr>
</table>
</td>
<td class="doxyMemberLabelsRight">
<span class="doxyMemberLabels">
<span class="doxyMemberLabel inline">inline</span>
<span class="doxyMemberLabel constexpr">constexpr</span>
</span>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 2988 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/demangle/itaniumdemangle-h">ItaniumDemangle.h</a>.</p>


<p>References <a href="/web-llvm/docs/api/files/lib/lib/ir/builtingcs-cpp/#abb2b3a60ccc38a28239e19a1646e0c8a">E</a>, <a href="#a5f7a662ebbcb6e1f4383300952107663">AbstractManglingParser&lt; Derived, Alloc &gt;::OperatorInfo::Enc</a>, <a href="/web-llvm/docs/api/files/lib/lib/support/md5-cpp/#a96d73bbd7af15cb1fc38c3f4a3bd82e9">F</a>, <a href="#a4c19071eaa1b2220d2cd94dc4e1fe4f9">AbstractManglingParser&lt; Derived, Alloc &gt;::OperatorInfo::Flag</a>, <a href="#a00c30c007b21b1b668323b77f73b1ccd">AbstractManglingParser&lt; Derived, Alloc &gt;::OperatorInfo::Kind</a>, <a href="/web-llvm/docs/api/files/lib/lib/support/regcomp-c/#a0240ac851181b84ac374872dc5434ee4">N</a>, <a href="#ab185185df3c482db7ac04c6102b57b22">AbstractManglingParser&lt; Derived, Alloc &gt;::OperatorInfo::Name</a>, <a href="/web-llvm/docs/api/files/lib/lib/option/option-cpp/#a04665169063c8ca1f2ea96c27fc7c2b2">P</a> and <a href="#ad0bf5a0fc6c1e57e5b6bb32fb26c1424">AbstractManglingParser&lt; Derived, Alloc &gt;::OperatorInfo::Prec</a>.</p>


<p>Referenced by <a href="#aaa21930c91442bbce8f2c74f9f945a4d">AbstractManglingParser&lt; Derived, Alloc &gt;::OperatorInfo::operator&lt;</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Public Operators

### operator!=() {#accc685ee230b975afdac79d4bd9da8d3}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool AbstractManglingParser&lt; Derived, Alloc &gt;::OperatorInfo::operator!= (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> char * Peek)</td>
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



<p>Definition at line 3002 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/demangle/itaniumdemangle-h">ItaniumDemangle.h</a>.</p>


<p>Reference <a href="#ac6781a0b48ac43ac1221921367ddc6fa">AbstractManglingParser&lt; Derived, Alloc &gt;::OperatorInfo::operator==</a>.</p>

</div>
</div>

### operator&lt;() {#aaa21930c91442bbce8f2c74f9f945a4d}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool AbstractManglingParser&lt; Derived, Alloc &gt;::OperatorInfo::operator&lt; (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/structs/abstractmanglingparser/operatorinfo">OperatorInfo</a> &amp; Other)</td>
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



<p>Definition at line 2993 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/demangle/itaniumdemangle-h">ItaniumDemangle.h</a>.</p>


<p>Reference <a href="#a457eef7dd9ed96f5be3310083f08a0ac">AbstractManglingParser&lt; Derived, Alloc &gt;::OperatorInfo::OperatorInfo</a>.</p>

</div>
</div>

### operator&lt;() {#ad1a7825f2762f06ff8e55364f37e5705}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool AbstractManglingParser&lt; Derived, Alloc &gt;::OperatorInfo::operator&lt; (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> char * Peek)</td>
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



<p>Definition at line 2996 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/demangle/itaniumdemangle-h">ItaniumDemangle.h</a>.</p>


<p>Reference <a href="#a5f7a662ebbcb6e1f4383300952107663">AbstractManglingParser&lt; Derived, Alloc &gt;::OperatorInfo::Enc</a>.</p>

</div>
</div>

### operator==() {#ac6781a0b48ac43ac1221921367ddc6fa}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool AbstractManglingParser&lt; Derived, Alloc &gt;::OperatorInfo::operator== (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> char * Peek)</td>
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



<p>Definition at line 2999 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/demangle/itaniumdemangle-h">ItaniumDemangle.h</a>.</p>


<p>Reference <a href="#a5f7a662ebbcb6e1f4383300952107663">AbstractManglingParser&lt; Derived, Alloc &gt;::OperatorInfo::Enc</a>.</p>


<p>Referenced by <a href="#accc685ee230b975afdac79d4bd9da8d3">AbstractManglingParser&lt; Derived, Alloc &gt;::OperatorInfo::operator!=</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Public Member Functions

### getFlag() {#a969e625604f64730a3a9ebb77841500f}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool AbstractManglingParser&lt; Derived, Alloc &gt;::OperatorInfo::getFlag ()</td>
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



<p>Definition at line 3018 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/demangle/itaniumdemangle-h">ItaniumDemangle.h</a>.</p>


<p>Reference <a href="#a4c19071eaa1b2220d2cd94dc4e1fe4f9">AbstractManglingParser&lt; Derived, Alloc &gt;::OperatorInfo::Flag</a>.</p>

</div>
</div>

### getKind() {#a8980eec0726dbc16e294875ee745d429}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">OIKind AbstractManglingParser&lt; Derived, Alloc &gt;::OperatorInfo::getKind ()</td>
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



<p>Definition at line 3017 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/demangle/itaniumdemangle-h">ItaniumDemangle.h</a>.</p>


<p>Reference <a href="#a00c30c007b21b1b668323b77f73b1ccd">AbstractManglingParser&lt; Derived, Alloc &gt;::OperatorInfo::Kind</a>.</p>

</div>
</div>

### getName() {#aadf6cc286d694f0a332d72aa3ad6b121}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">std::string_view AbstractManglingParser&lt; Derived, Alloc &gt;::OperatorInfo::getName ()</td>
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



<p>Definition at line 3016 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/demangle/itaniumdemangle-h">ItaniumDemangle.h</a>.</p>


<p>Reference <a href="#ab185185df3c482db7ac04c6102b57b22">AbstractManglingParser&lt; Derived, Alloc &gt;::OperatorInfo::Name</a>.</p>

</div>
</div>

### getPrecedence() {#a833f0b876264ebdec33723d0b006835e}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">Node::Prec AbstractManglingParser&lt; Derived, Alloc &gt;::OperatorInfo::getPrecedence ()</td>
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



<p>Definition at line 3019 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/demangle/itaniumdemangle-h">ItaniumDemangle.h</a>.</p>


<p>Reference <a href="#ad0bf5a0fc6c1e57e5b6bb32fb26c1424">AbstractManglingParser&lt; Derived, Alloc &gt;::OperatorInfo::Prec</a>.</p>

</div>
</div>

### getSymbol() {#aeed1fbd4f82f1bc9c4ada7ce9835edb7}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">std::string_view AbstractManglingParser&lt; Derived, Alloc &gt;::OperatorInfo::getSymbol ()</td>
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



<p>Definition at line 3005 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/demangle/itaniumdemangle-h">ItaniumDemangle.h</a>.</p>


<p>References <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/demangle/demangleconfig-h/#ac71d1b2a381f0070e426cf362f0ef7e2">DEMANGLE_ASSERT</a>, <a href="#a00c30c007b21b1b668323b77f73b1ccd">AbstractManglingParser&lt; Derived, Alloc &gt;::OperatorInfo::Kind</a>, <a href="#ab185185df3c482db7ac04c6102b57b22">AbstractManglingParser&lt; Derived, Alloc &gt;::OperatorInfo::Name</a>, <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/demangle/stringviewextras-h/#a5336c02c81ff675028496f2f2409d30a">starts_with</a> and <a href="#aafe8a42a8411e57f7e90ed1b1fcbd0a7ac65df57a19d87c23245c988c0caefc8a">AbstractManglingParser&lt; Derived, Alloc &gt;::OperatorInfo::Unnameable</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Public Member Attributes

### Enc {#a5f7a662ebbcb6e1f4383300952107663}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">char AbstractManglingParser&lt; Derived, Alloc &gt;::OperatorInfo::Enc[2]</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 2981 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/demangle/itaniumdemangle-h">ItaniumDemangle.h</a>.</p>


<p>Referenced by <a href="#ad1a7825f2762f06ff8e55364f37e5705">AbstractManglingParser&lt; Derived, Alloc &gt;::OperatorInfo::operator&lt;</a>, <a href="#ac6781a0b48ac43ac1221921367ddc6fa">AbstractManglingParser&lt; Derived, Alloc &gt;::OperatorInfo::operator==</a> and <a href="#a457eef7dd9ed96f5be3310083f08a0ac">AbstractManglingParser&lt; Derived, Alloc &gt;::OperatorInfo::OperatorInfo</a>.</p>

</div>
</div>

### Flag {#a4c19071eaa1b2220d2cd94dc4e1fe4f9}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool AbstractManglingParser&lt; Derived, Alloc &gt;::OperatorInfo::Flag</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 2983 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/demangle/itaniumdemangle-h">ItaniumDemangle.h</a>.</p>


<p>Referenced by <a href="#a969e625604f64730a3a9ebb77841500f">AbstractManglingParser&lt; Derived, Alloc &gt;::OperatorInfo::getFlag</a> and <a href="#a457eef7dd9ed96f5be3310083f08a0ac">AbstractManglingParser&lt; Derived, Alloc &gt;::OperatorInfo::OperatorInfo</a>.</p>

</div>
</div>

### Kind {#a00c30c007b21b1b668323b77f73b1ccd}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">OIKind AbstractManglingParser&lt; Derived, Alloc &gt;::OperatorInfo::Kind</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 2982 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/demangle/itaniumdemangle-h">ItaniumDemangle.h</a>.</p>


<p>Referenced by <a href="#a8980eec0726dbc16e294875ee745d429">AbstractManglingParser&lt; Derived, Alloc &gt;::OperatorInfo::getKind</a>, <a href="#aeed1fbd4f82f1bc9c4ada7ce9835edb7">AbstractManglingParser&lt; Derived, Alloc &gt;::OperatorInfo::getSymbol</a> and <a href="#a457eef7dd9ed96f5be3310083f08a0ac">AbstractManglingParser&lt; Derived, Alloc &gt;::OperatorInfo::OperatorInfo</a>.</p>

</div>
</div>

### Name {#ab185185df3c482db7ac04c6102b57b22}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">const char* AbstractManglingParser&lt; Derived, Alloc &gt;::OperatorInfo::Name</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 2985 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/demangle/itaniumdemangle-h">ItaniumDemangle.h</a>.</p>


<p>Referenced by <a href="#aadf6cc286d694f0a332d72aa3ad6b121">AbstractManglingParser&lt; Derived, Alloc &gt;::OperatorInfo::getName</a>, <a href="#aeed1fbd4f82f1bc9c4ada7ce9835edb7">AbstractManglingParser&lt; Derived, Alloc &gt;::OperatorInfo::getSymbol</a> and <a href="#a457eef7dd9ed96f5be3310083f08a0ac">AbstractManglingParser&lt; Derived, Alloc &gt;::OperatorInfo::OperatorInfo</a>.</p>

</div>
</div>

### Prec {#ad0bf5a0fc6c1e57e5b6bb32fb26c1424}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">Node::Prec AbstractManglingParser&lt; Derived, Alloc &gt;::OperatorInfo::Prec</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 2984 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/demangle/itaniumdemangle-h">ItaniumDemangle.h</a>.</p>


<p>Referenced by <a href="#a833f0b876264ebdec33723d0b006835e">AbstractManglingParser&lt; Derived, Alloc &gt;::OperatorInfo::getPrecedence</a> and <a href="#a457eef7dd9ed96f5be3310083f08a0ac">AbstractManglingParser&lt; Derived, Alloc &gt;::OperatorInfo::OperatorInfo</a>.</p>

</div>
</div>

</div>

<hr/>

The documentation for this struct was generated from the following file:

<ul>
<li><a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/demangle/itaniumdemangle-h">ItaniumDemangle.h</a></li>
</ul>

<hr/>

<p class="doxyGeneratedBy">Generated via <a href="https://github.com/xpack/doxygen2docusaurus">doxygen2docusaurus</a> by <a href="https://www.doxygen.nl">Doxygen</a> 1.15.0.</p>

</div>
