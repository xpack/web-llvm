---

# DO NOT EDIT!
# Automatically generated via doxygen2docusaurus by Doxygen.

slug: /api/classes/llvm/object/archive/symbol
custom_edit_url: null
toc_max_heading_level: 4
keywords:
  - doxygen
  - reference
  - class

---

<div class="doxyPage">

# The `Symbol` Class Reference



## Declaration

<div class="doxyDeclaration">
class llvm::object::Archive::Symbol { ... }
</div>

## Included Headers

<div class="doxyIncludesList">#include "<a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/object/archive-h">llvm/Object/Archive.h</a>"
</div>

## Public Constructors Index

<table class="doxyMembersIndex">

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a6fd90d0abf2981b4a1db908db7a8082e">Symbol</a> (const Archive *p, uint32_t symi, uint32_t stri)</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#aa6d0f12e76077b298a2fa61f1e4616a4">operator==</a> (const Symbol &amp;other) const</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/stringref">StringRef</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#aaccb27d091e3f4899c01d6ebc1100967">getName</a> () const</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/expected">Expected</a>&lt; <a href="/web-llvm/docs/api/classes/llvm/object/archive/child">Child</a> &gt;</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#aa53f9de42b9d8eeaf9af259f59f4a1be">getMember</a> () const</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/object/archive/symbol">Symbol</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a12a9df192d55690ac61ec468d47f14d3">getNext</a> () const</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#aeb1bbb5b3923c7601fdb06c4f1b7d196">isECSymbol</a> () const</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/object/archive">Archive</a> *</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a42648c77040ecca1b461eb0ce5d40481">Parent</a></td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">uint32_t</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a054c2503956bc970ff351cc910e04e74">SymbolIndex</a></td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">uint32_t</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#addd413e576b00f76959ec3ade5476a08">StringIndex</a></td>
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


<p>Definition at line 289 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/object/archive-h">Archive.h</a>.</p>


<div class="doxySectionDef">

## Public Constructors

### Symbol() {#a6fd90d0abf2981b4a1db908db7a8082e}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">llvm::object::Archive::Symbol::Symbol (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/object/archive">Archive</a> * p, uint32_t symi, uint32_t stri)</td>
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



<p>Definition at line 295 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/object/archive-h">Archive.h</a>.</p>


<p>Reference <a href="/web-llvm/docs/api/classes/llvm/object/archive/#a8ad341cb471333b07af638089e1dc7c9">llvm::object::Archive::Archive</a>.</p>


<p>Referenced by <a href="#a12a9df192d55690ac61ec468d47f14d3">getNext</a> and <a href="#aa6d0f12e76077b298a2fa61f1e4616a4">operator==</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Public Operators

### operator==() {#aa6d0f12e76077b298a2fa61f1e4616a4}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool llvm::object::Archive::Symbol::operator== (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/object/archive/symbol">Symbol</a> &amp; other)</td>
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



<p>Definition at line 298 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/object/archive-h">Archive.h</a>.</p>


<p>Reference <a href="#a6fd90d0abf2981b4a1db908db7a8082e">Symbol</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Public Member Functions

### getMember() {#aa53f9de42b9d8eeaf9af259f59f4a1be}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">Expected&lt; Archive::Child &gt; Archive::Symbol::getMember ()</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Declaration at line 303 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/object/archive-h">Archive.h</a>, definition at line 1020 of file <a href="/web-llvm/docs/api/files/lib/lib/object/archive-cpp">Archive.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/namespaces/llvm/callingconv/#ac6aa1387c4375260e2468eb5a77fdb4cafd841a49aec1539bc88abc8ff9e170fb">llvm::CallingConv::C</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#ad10875fd499e8e285aaeef615e9b11aa">llvm::errorCodeToError</a>, <a href="#aeb1bbb5b3923c7601fdb06c4f1b7d196">isECSymbol</a>, <a href="/web-llvm/docs/api/classes/llvm/object/archive/#ab288378fa8bfa0678dd25e36b5198a87a1ce3ba6f0ac952cb8105e17115093810">llvm::object::Archive::K_AIXBIG</a>, <a href="/web-llvm/docs/api/classes/llvm/object/archive/#ab288378fa8bfa0678dd25e36b5198a87a769a0d23f23121590187fb224cfa650f">llvm::object::Archive::K_BSD</a>, <a href="/web-llvm/docs/api/classes/llvm/object/archive/#ab288378fa8bfa0678dd25e36b5198a87ad2085dbd9869a86d285bec7525920d8a">llvm::object::Archive::K_DARWIN64</a>, <a href="/web-llvm/docs/api/classes/llvm/object/archive/#ab288378fa8bfa0678dd25e36b5198a87a63a070d89ebf9a74c22a38ec25719ae7">llvm::object::Archive::K_GNU</a>, <a href="/web-llvm/docs/api/classes/llvm/object/archive/#ab288378fa8bfa0678dd25e36b5198a87af59b87258f3f4e04b99d21c79bdd7c20">llvm::object::Archive::K_GNU64</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a05f5b9a11bdcc5feba62899f95dcf878a3134224cba2545bc57954d3b072aebb4">llvm::Offset</a>, <a href="/web-llvm/docs/api/namespaces/llvm/object/#a6f5880f200b9731436d9ea163568ee20aeae74d57b1e6d55a1e2e3d4addd22b0b">llvm::object::parse_failed</a>, <a href="/web-llvm/docs/api/namespaces/llvm/support/endian/#a17a3ace88f2bb1abf73bf887cdc88e5f">llvm::support::endian::read16le</a>, <a href="/web-llvm/docs/api/namespaces/llvm/support/endian/#a7a225814d4cc0d175373f7ffc59f66b4">llvm::support::endian::read32be</a>, <a href="/web-llvm/docs/api/namespaces/llvm/support/endian/#ae865d5defb8785b365f342375822beaa">llvm::support::endian::read32le</a>, <a href="/web-llvm/docs/api/namespaces/llvm/support/endian/#a4ec2abec8101a7b16ee520e882cc7d34">llvm::support::endian::read64be</a>, <a href="/web-llvm/docs/api/namespaces/llvm/support/endian/#a0fa2f859066acd16820ab083040158c9">llvm::support::endian::read64le</a> and <a href="/web-llvm/docs/api/classes/llvm/error/#a4dfd0813c3d0e0a30439b5a3e9196b59">llvm::Error::success</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/classes/llvm/object/archive/#ad6942d34da0ae42a687cccd3e4b4a7f3">llvm::object::Archive::findSym</a>.</p>

</div>
</div>

### getName() {#aaccb27d091e3f4899c01d6ebc1100967}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">StringRef Archive::Symbol::getName ()</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Declaration at line 302 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/object/archive-h">Archive.h</a>, definition at line 1014 of file <a href="/web-llvm/docs/api/files/lib/lib/object/archive-cpp">Archive.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/classes/llvm/stringref/#a46f643f1eb1939362c7dd79361bcbd0e">llvm::StringRef::begin</a> and <a href="#aeb1bbb5b3923c7601fdb06c4f1b7d196">isECSymbol</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/classes/llvm/object/archive/#ad6942d34da0ae42a687cccd3e4b4a7f3">llvm::object::Archive::findSym</a>.</p>

</div>
</div>

### getNext() {#a12a9df192d55690ac61ec468d47f14d3}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">Archive::Symbol Archive::Symbol::getNext ()</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Declaration at line 304 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/object/archive-h">Archive.h</a>, definition at line 1090 of file <a href="/web-llvm/docs/api/files/lib/lib/object/archive-cpp">Archive.cpp</a>.</p>


<p>References <a href="#aeb1bbb5b3923c7601fdb06c4f1b7d196">isECSymbol</a>, <a href="/web-llvm/docs/api/classes/llvm/object/archive/#ab288378fa8bfa0678dd25e36b5198a87a769a0d23f23121590187fb224cfa650f">llvm::object::Archive::K_BSD</a>, <a href="/web-llvm/docs/api/namespaces/llvm/support/endian/#ae865d5defb8785b365f342375822beaa">llvm::support::endian::read32le</a> and <a href="#a6fd90d0abf2981b4a1db908db7a8082e">Symbol</a>.</p>

</div>
</div>

### isECSymbol() {#aeb1bbb5b3923c7601fdb06c4f1b7d196}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool Archive::Symbol::isECSymbol ()</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Declaration at line 305 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/object/archive-h">Archive.h</a>, definition at line 1006 of file <a href="/web-llvm/docs/api/files/lib/lib/object/archive-cpp">Archive.cpp</a>.</p>


<p>Referenced by <a href="#aa53f9de42b9d8eeaf9af259f59f4a1be">getMember</a>, <a href="#aaccb27d091e3f4899c01d6ebc1100967">getName</a> and <a href="#a12a9df192d55690ac61ec468d47f14d3">getNext</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Private Member Attributes

### Parent {#a42648c77040ecca1b461eb0ce5d40481}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">const Archive* llvm::object::Archive::Symbol::Parent</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 290 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/object/archive-h">Archive.h</a>.</p>

</div>
</div>

### StringIndex {#addd413e576b00f76959ec3ade5476a08}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">uint32_t llvm::object::Archive::Symbol::StringIndex</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 292 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/object/archive-h">Archive.h</a>.</p>

</div>
</div>

### SymbolIndex {#a054c2503956bc970ff351cc910e04e74}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">uint32_t llvm::object::Archive::Symbol::SymbolIndex</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 291 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/object/archive-h">Archive.h</a>.</p>

</div>
</div>

</div>

<hr/>

The documentation for this class was generated from the following files:

<ul>
<li><a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/object/archive-h">Archive.h</a></li>
<li><a href="/web-llvm/docs/api/files/lib/lib/object/archive-cpp">Archive.cpp</a></li>
</ul>

<hr/>

<p class="doxyGeneratedBy">Generated via <a href="https://github.com/xpack/doxygen2docusaurus">doxygen2docusaurus</a> by <a href="https://www.doxygen.nl">Doxygen</a> 1.14.0.</p>

</div>
