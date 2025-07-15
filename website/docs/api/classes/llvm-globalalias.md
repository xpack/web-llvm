---

# DO NOT EDIT!
# Automatically generated via doxygen2docusaurus by Doxygen.

slug: /api/classes/llvm/globalalias
custom_edit_url: null
toc_max_heading_level: 4
keywords:
  - doxygen
  - reference
  - class

---

<div class="doxyPage">

# The `GlobalAlias` Class Reference



## Declaration

<div class="doxyDeclaration">
class llvm::GlobalAlias { ... }
</div>

## Included Headers

<div class="doxyIncludesList">#include "<a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/ir/globalalias-h">llvm/IR/GlobalAlias.h</a>"
</div>

## Base classes

<table class="doxyMembersIndex">

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">class</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/globalvalue">GlobalValue</a></td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/ilist-node">ilist_node&lt;T, Options&gt;</a></td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a1989fb0fd1aa69b4142d1e911b92ba50">SymbolTableListTraits&lt; GlobalAlias &gt;</a></td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a9f70809a4765edc206f1b0f2be117949">GlobalAlias</a> (const GlobalAlias &amp;)=delete</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a4e33b2c56fb940dfc118b4d4830521e9">GlobalAlias</a> (Type *Ty, unsigned AddressSpace, LinkageTypes Linkage, const Twine &amp;Name, Constant *Aliasee, Module *Parent)</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/globalalias">GlobalAlias</a> &amp;</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a4b5d91825bd05a14280768680626e294">operator=</a> (const GlobalAlias &amp;)=delete</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">void *</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ab140130ab000324601c8af55931bd26e">operator new</a> (size_t S)</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a4d87bf0fdece33f14f7ef6754bf6feb0">operator delete</a> (void *Ptr)</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a4e6d4520d4b49c5d66c42219f06f5d9d">DECLARE_TRANSPARENT_OPERAND_ACCESSORS</a> (Constant)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Provide fast operand accessors. <a href="#a4e6d4520d4b49c5d66c42219f06f5d9d">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">void</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ae7c767109f051b172dd61a1c18735749">copyAttributesFrom</a> (const GlobalAlias *Src)</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#aa4afd53102b414c23761c32f33b6cd08">removeFromParent</a> ()</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>removeFromParent - This method unlinks 'this' from the containing module, but does not delete it. <a href="#aa4afd53102b414c23761c32f33b6cd08">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">void</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a09b07d472515f1d307c0e8229f6856fb">eraseFromParent</a> ()</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>eraseFromParent - This method unlinks 'this' from the containing module and deletes it. <a href="#a09b07d472515f1d307c0e8229f6856fb">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">void</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a629a9b41f0b6dfa91f5b0a7ac34f2d1a">setAliasee</a> (Constant *Aliasee)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>These methods retrieve and set alias target. <a href="#a629a9b41f0b6dfa91f5b0a7ac34f2d1a">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/constant">Constant</a> *</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a7666cc7bd9294c7ae9992c41c591e08b">getAliasee</a> () const</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/constant">Constant</a> *</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a6313d8c02c396afb981e61ef25088ff2">getAliasee</a> ()</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/globalobject">GlobalObject</a> *</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a311a097af4f0f77da22ac7acddc496f5">getAliaseeObject</a> () const</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/globalobject">GlobalObject</a> *</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ab9a6b2e3a9031fd10478e37b630b4304">getAliaseeObject</a> ()</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">static <a href="/web-llvm/docs/api/classes/llvm/globalalias">GlobalAlias</a> *</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a8a638534b520f72ab7f2c886da739a6c">create</a> (Type *Ty, unsigned AddressSpace, LinkageTypes Linkage, const Twine &amp;Name, Constant *Aliasee, Module *Parent)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>If a parent module is specified, the alias is automatically inserted into the end of the specified module's alias list. <a href="#a8a638534b520f72ab7f2c886da739a6c">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">static <a href="/web-llvm/docs/api/classes/llvm/globalalias">GlobalAlias</a> *</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a1726164ac15b6aa13ed5bbdd07f0a576">create</a> (Type *Ty, unsigned AddressSpace, LinkageTypes Linkage, const Twine &amp;Name, Module *Parent)</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">static <a href="/web-llvm/docs/api/classes/llvm/globalalias">GlobalAlias</a> *</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ab815632298cb8e2271e2a0e7062a7360">create</a> (Type *Ty, unsigned AddressSpace, LinkageTypes Linkage, const Twine &amp;Name, GlobalValue *Aliasee)</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">static <a href="/web-llvm/docs/api/classes/llvm/globalalias">GlobalAlias</a> *</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#acc7ae6e57000b1f2e276fb96eba06213">create</a> (LinkageTypes Linkage, const Twine &amp;Name, GlobalValue *Aliasee)</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">static <a href="/web-llvm/docs/api/classes/llvm/globalalias">GlobalAlias</a> *</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a51d2023749f953a981e41484ca4ebfa6">create</a> (const Twine &amp;Name, GlobalValue *Aliasee)</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a0dc1071ac8fdde2dc10ba6c7700598f4">isValidLinkage</a> (LinkageTypes L)</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a880feb280a26a7ee3156dd427fa12502">classof</a> (const Value *V)</td>
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

## Private Static Attributes Index

<table class="doxyMembersIndex">

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">static constexpr <a href="/web-llvm/docs/api/structs/llvm/user/intrusiveoperandsallocmarker">IntrusiveOperandsAllocMarker</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a8999b0a08927a9dac47a6a44b711c38f">AllocMarker</a> {1}</td>
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


<p>Definition at line 28 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/ir/globalalias-h">GlobalAlias.h</a>.</p>


<div class="doxySectionDef">

## Friends

### SymbolTableListTraits&lt; GlobalAlias &gt; {#a1989fb0fd1aa69b4142d1e911b92ba50}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">friend class <a href="/web-llvm/docs/api/classes/llvm/symboltablelisttraits">SymbolTableListTraits</a>&lt; <a href="/web-llvm/docs/api/classes/llvm/globalalias">GlobalAlias</a> &gt;</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">


<p>Definition at line 1 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/ir/globalalias-h">GlobalAlias.h</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Public Constructors

### GlobalAlias() {#a9f70809a4765edc206f1b0f2be117949}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">llvm::GlobalAlias::GlobalAlias (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/globalalias">GlobalAlias</a> &amp;)</td>
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



<p>Definition at line 37 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/ir/globalalias-h">GlobalAlias.h</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Private Constructors

### GlobalAlias() {#a4e33b2c56fb940dfc118b4d4830521e9}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">GlobalAlias::GlobalAlias (<a href="/web-llvm/docs/api/classes/llvm/type">Type</a> * Ty, unsigned AddressSpace, <a href="/web-llvm/docs/api/classes/llvm/globalvalue/#aedfa75f0c85c4aa85b257f066fbea57c">LinkageTypes</a> Linkage, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/twine">Twine</a> &amp; Name, <a href="/web-llvm/docs/api/classes/llvm/constant">Constant</a> * Aliasee, <a href="/web-llvm/docs/api/classes/llvm/module">Module</a> * Parent)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Declaration at line 33 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/ir/globalalias-h">GlobalAlias.h</a>, definition at line 547 of file <a href="/web-llvm/docs/api/files/lib/lib/ir/globals-cpp">Globals.cpp</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Public Operators

### operator delete() {#a4d87bf0fdece33f14f7ef6754bf6feb0}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void llvm::GlobalAlias::operator delete (void * Ptr)</td>
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



<p>Definition at line 65 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/ir/globalalias-h">GlobalAlias.h</a>.</p>


<p>Reference <a href="/web-llvm/docs/api/files/lib/lib/analysis/targetlibraryinfo-cpp/#aca185e6d0e9f423dbb24440206454872a11dbf501abf829b3ab7049c2d3a8a053">Ptr</a>.</p>

</div>
</div>

### operator new() {#ab140130ab000324601c8af55931bd26e}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void * llvm::GlobalAlias::operator new (size_t S)</td>
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



<p>Definition at line 64 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/ir/globalalias-h">GlobalAlias.h</a>.</p>

</div>
</div>

### operator=() {#a4b5d91825bd05a14280768680626e294}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">GlobalAlias &amp; llvm::GlobalAlias::operator= (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/globalalias">GlobalAlias</a> &amp;)</td>
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



<p>Definition at line 38 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/ir/globalalias-h">GlobalAlias.h</a>.</p>


<p>References <a href="/web-llvm/docs/api/classes/llvm/globalvalue/#a5bd16c2fbe755cda66b18d56761038ea">llvm::GlobalValue::Constant</a>, <a href="/web-llvm/docs/api/classes/llvm/globalvalue/#af38a8629ae32606b01eacbbd667d831c">llvm::GlobalValue::GlobalValue</a>, <a href="/web-llvm/docs/api/classes/llvm/globalvalue/#ad61abcbd08169ff119e819ef0482744d">llvm::GlobalValue::Linkage</a> and <a href="/web-llvm/docs/api/classes/llvm/globalvalue/#acb71c8012dfaa189618d2cdafb58b4b0">llvm::GlobalValue::Parent</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Public Member Functions

### copyAttributesFrom() {#ae7c767109f051b172dd61a1c18735749}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void llvm::GlobalAlias::copyAttributesFrom (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/globalalias">GlobalAlias</a> * Src)</td>
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



<p>Definition at line 70 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/ir/globalalias-h">GlobalAlias.h</a>.</p>


<p>Reference <a href="/web-llvm/docs/api/classes/llvm/globalvalue/#a96c9558e69f588728273b57eb5a1fe73">llvm::GlobalValue::copyAttributesFrom</a>.</p>

</div>
</div>

### DECLARE\_TRANSPARENT\_OPERAND\_ACCESSORS() {#a4e6d4520d4b49c5d66c42219f06f5d9d}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">llvm::GlobalAlias::DECLARE_TRANSPARENT_OPERAND_ACCESSORS (<a href="/web-llvm/docs/api/classes/llvm/constant">Constant</a>)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Provide fast operand accessors.</p>

<p>Definition at line 68 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/ir/globalalias-h">GlobalAlias.h</a>.</p>


<p>Reference <a href="/web-llvm/docs/api/classes/llvm/globalvalue/#a5bd16c2fbe755cda66b18d56761038ea">llvm::GlobalValue::Constant</a>.</p>

</div>
</div>

### eraseFromParent() {#a09b07d472515f1d307c0e8229f6856fb}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void GlobalAlias::eraseFromParent ()</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>eraseFromParent - This method unlinks 'this' from the containing module and deletes it.</p>

<p>Declaration at line 82 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/ir/globalalias-h">GlobalAlias.h</a>, definition at line 587 of file <a href="/web-llvm/docs/api/files/lib/lib/ir/globals-cpp">Globals.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/classes/llvm/module/#a9a2bb9b6dfce993d3eddec7345684f42">llvm::Module::eraseAlias</a> and <a href="/web-llvm/docs/api/classes/llvm/globalvalue/#a739b30c811f1eece61b05320ddf44e5b">llvm::GlobalValue::getParent</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/classes/anonymous-lowertypetests-cpp-/lowertypetestsmodule/#a7c206887f3f0887f2c6ac58910c09c41">anonymous{LowerTypeTests.cpp}::LowerTypeTestsModule::lower</a> and <a href="/web-llvm/docs/api/classes/anonymous-dataflowsanitizer-cpp-/dataflowsanitizer/#ab4d94a2774e8420abe5e331d94334cec">anonymous{DataFlowSanitizer.cpp}::DataFlowSanitizer::runImpl</a>.</p>

</div>
</div>

### getAliasee() {#a7666cc7bd9294c7ae9992c41c591e08b}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">const Constant * llvm::GlobalAlias::getAliasee ()</td>
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



<p>Definition at line 86 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/ir/globalalias-h">GlobalAlias.h</a>.</p>


<p>Reference <a href="/web-llvm/docs/api/classes/llvm/globalvalue/#a5bd16c2fbe755cda66b18d56761038ea">llvm::GlobalValue::Constant</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/classes/anonymous-aarch64arm64eccalllowering-cpp-/aarch64arm64eccalllowering/#a3f27dda1e68a24fab4b3ed4a9cfc0e7c">anonymous{AArch64Arm64ECCallLowering.cpp}::AArch64Arm64ECCallLowering::buildPatchableThunk</a>, <a href="/web-llvm/docs/api/namespaces/llvm/orc/#aaa5acf165c5a3bec2ff360c59f2f9448">llvm::orc::cloneGlobalAliasDecl</a>, <a href="/web-llvm/docs/api/classes/llvm/asmprinter/#a2773eb6f0be68426806ef8f68bdd4393">llvm::AsmPrinter::emitGlobalAlias</a>, <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/ipo/globalopt-cpp/#ae17d0aeb924fa0611500eb8cb09a70d9">hasUsesToReplace</a>, <a href="/web-llvm/docs/api/classes/anonymous-asmwriter-cpp-/assemblywriter/#ae9005670841925a061ef19fe62955bce">anonymous{AsmWriter.cpp}::AssemblyWriter::printAlias</a> and <a href="/web-llvm/docs/api/classes/llvm/objectsizeoffsetvisitor/#a81bb5b0675c34a74c62b2547865c8d7b">llvm::ObjectSizeOffsetVisitor::visitGlobalAlias</a>.</p>

</div>
</div>

### getAliasee() {#a6313d8c02c396afb981e61ef25088ff2}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">Constant * llvm::GlobalAlias::getAliasee ()</td>
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



<p>Definition at line 89 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/ir/globalalias-h">GlobalAlias.h</a>.</p>


<p>Reference <a href="/web-llvm/docs/api/classes/llvm/globalvalue/#a5bd16c2fbe755cda66b18d56761038ea">llvm::GlobalValue::Constant</a>.</p>

</div>
</div>

### getAliaseeObject() {#a311a097af4f0f77da22ac7acddc496f5}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">const GlobalObject * GlobalAlias::getAliaseeObject ()</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Declaration at line 91 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/ir/globalalias-h">GlobalAlias.h</a>, definition at line 595 of file <a href="/web-llvm/docs/api/files/lib/lib/ir/globals-cpp">Globals.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/files/lib/lib/ir/globals-cpp/#ade220311d6a189eb0902d703f4beef36">findBaseObject</a>, <a href="/web-llvm/docs/api/classes/llvm/user/#aa0a2cb1582d1cec317bd205085469ca1">llvm::User::getOperand</a> and <a href="/web-llvm/docs/api/classes/llvm/globalvalue/#af38a8629ae32606b01eacbbd667d831c">llvm::GlobalValue::GlobalValue</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/powerpc/ppcisellowering-cpp/#a43a17d867ea4d3bca00dfb065f8cc811">callsShareTOCBase</a>, <a href="/web-llvm/docs/api/classes/llvm/asmprinter/#a2773eb6f0be68426806ef8f68bdd4393">llvm::AsmPrinter::emitGlobalAlias</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/systemz/systemzisellowering-cpp/#ac9d0f2b6d9ec3c966243a29f8c8c7494">getADAEntry</a>, <a href="/web-llvm/docs/api/classes/llvm/ppcsubtarget/#ad1da03c90232fadc79f4c8d041bbce56">llvm::PPCSubtarget::getCodeModel</a>, <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/ipo/functionimport-cpp/#ac926ba61257c2262ebca3deca2cc8c76">replaceAliasWithAliasee</a> and <a href="/web-llvm/docs/api/classes/anonymous-dataflowsanitizer-cpp-/dataflowsanitizer/#ab4d94a2774e8420abe5e331d94334cec">anonymous{DataFlowSanitizer.cpp}::DataFlowSanitizer::runImpl</a>.</p>

</div>
</div>

### getAliaseeObject() {#ab9a6b2e3a9031fd10478e37b630b4304}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">GlobalObject * llvm::GlobalAlias::getAliaseeObject ()</td>
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



<p>Definition at line 92 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/ir/globalalias-h">GlobalAlias.h</a>.</p>

</div>
</div>

### removeFromParent() {#aa4afd53102b414c23761c32f33b6cd08}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void GlobalAlias::removeFromParent ()</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>removeFromParent - This method unlinks 'this' from the containing module, but does not delete it.</p>

<p>Declaration at line 77 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/ir/globalalias-h">GlobalAlias.h</a>, definition at line 585 of file <a href="/web-llvm/docs/api/files/lib/lib/ir/globals-cpp">Globals.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/classes/llvm/globalvalue/#a739b30c811f1eece61b05320ddf44e5b">llvm::GlobalValue::getParent</a> and <a href="/web-llvm/docs/api/classes/llvm/module/#a5724c4a6f094c94f6652a4a6c5d59f93">llvm::Module::removeAlias</a>.</p>

</div>
</div>

### setAliasee() {#a629a9b41f0b6dfa91f5b0a7ac34f2d1a}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void GlobalAlias::setAliasee (<a href="/web-llvm/docs/api/classes/llvm/constant">Constant</a> * Aliasee)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>These methods retrieve and set alias target.</p>

<p>Declaration at line 85 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/ir/globalalias-h">GlobalAlias.h</a>, definition at line 589 of file <a href="/web-llvm/docs/api/files/lib/lib/ir/globals-cpp">Globals.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/silowercontrolflow-cpp/#a4868c5d81c5ccc98c47aeab6244346a0">assert</a>, <a href="/web-llvm/docs/api/classes/llvm/globalvalue/#a5bd16c2fbe755cda66b18d56761038ea">llvm::GlobalValue::Constant</a>, <a href="/web-llvm/docs/api/classes/llvm/globalvalue/#a913a5d4b2cddde762446bd494e81a3f2">llvm::GlobalValue::getType</a> and <a href="/web-llvm/docs/api/classes/llvm/value/#a0344a49526443edf90cc0aef3abd3337">llvm::Value::getType</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/classes/anonymous-aarch64arm64eccalllowering-cpp-/aarch64arm64eccalllowering/#a3f27dda1e68a24fab4b3ed4a9cfc0e7c">anonymous{AArch64Arm64ECCallLowering.cpp}::AArch64Arm64ECCallLowering::buildPatchableThunk</a> and <a href="/web-llvm/docs/api/namespaces/llvm/#ab371d6b308eb9772bdec63cf7a041407">llvm::CloneModule</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Public Static Functions

### classof() {#a880feb280a26a7ee3156dd427fa12502}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool llvm::GlobalAlias::classof (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/value">Value</a> * V)</td>
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



<p>Definition at line 103 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/ir/globalalias-h">GlobalAlias.h</a>.</p>

</div>
</div>

### create() {#a8a638534b520f72ab7f2c886da739a6c}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">GlobalAlias * GlobalAlias::create (<a href="/web-llvm/docs/api/classes/llvm/type">Type</a> * Ty, unsigned AddressSpace, <a href="/web-llvm/docs/api/classes/llvm/globalvalue/#aedfa75f0c85c4aa85b257f066fbea57c">LinkageTypes</a> Linkage, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/twine">Twine</a> &amp; Name, <a href="/web-llvm/docs/api/classes/llvm/constant">Constant</a> * Aliasee, <a href="/web-llvm/docs/api/classes/llvm/module">Module</a> * Parent)</td>
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

<p>If a parent module is specified, the alias is automatically inserted into the end of the specified module's alias list.</p>

<p>Declaration at line 42 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/ir/globalalias-h">GlobalAlias.h</a>, definition at line 557 of file <a href="/web-llvm/docs/api/files/lib/lib/ir/globals-cpp">Globals.cpp</a>.</p>


<p>Reference <a href="/web-llvm/docs/api/classes/llvm/globalvalue/#a5bd16c2fbe755cda66b18d56761038ea">llvm::GlobalValue::Constant</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/namespaces/llvm/orc/#aaa5acf165c5a3bec2ff360c59f2f9448">llvm::orc::cloneGlobalAliasDecl</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#ab371d6b308eb9772bdec63cf7a041407">llvm::CloneModule</a>, <a href="#a51d2023749f953a981e41484ca4ebfa6">create</a>, <a href="#acc7ae6e57000b1f2e276fb96eba06213">create</a>, <a href="#ab815632298cb8e2271e2a0e7062a7360">create</a>, <a href="#a1726164ac15b6aa13ed5bbdd07f0a576">create</a>, <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/ipo/memprofcontextdisambiguation-cpp/#a0282ad8b650e02a78742f8a718f888f4">createFunctionClones</a>, <a href="/web-llvm/docs/api/classes/anonymous-ppcasmprinter-cpp-/ppcaixasmprinter/#ab50c4c40350eb077f3f414ff6b9226ab">anonymous{PPCAsmPrinter.cpp}::PPCAIXAsmPrinter::emitXXStructorList</a>, <a href="/web-llvm/docs/api/structs/anonymous-wholeprogramdevirt-cpp-/devirtmodule/#a16a470a2b40fa6e28a35af849806450b">anonymous{WholeProgramDevirt.cpp}::DevirtModule::exportGlobal</a>, <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/instrumentation/instrprofiling-cpp/#a97235ab99e26ebd8fe54f629666f6bd2">getFuncAddrForProfData</a>, <a href="/web-llvm/docs/api/groups/llvmcorevalueconstantglobalalias/#gad4dfb6341f8c010227673b2756d09aeb">LLVMAddAlias2</a>, <a href="/web-llvm/docs/api/classes/anonymous-lowertypetests-cpp-/lowertypetestsmodule/#a7c206887f3f0887f2c6ac58910c09c41">anonymous{LowerTypeTests.cpp}::LowerTypeTestsModule::lower</a>, <a href="/web-llvm/docs/api/structs/anonymous-wholeprogramdevirt-cpp-/devirtmodule/#a12cea94e94a75a84e5e5c0a649d1ef78">anonymous{WholeProgramDevirt.cpp}::DevirtModule::rebuildGlobal</a>, <a href="/web-llvm/docs/api/classes/anonymous-passbuilder-cpp-/triggerverifiererrorpass/#ada1d133949e3d808f4e13f5cadf21495">anonymous{PassBuilder.cpp}::TriggerVerifierErrorPass::run</a> and <a href="/web-llvm/docs/api/classes/anonymous-aarch64arm64eccalllowering-cpp-/aarch64arm64eccalllowering/#a7b0a136ac6a10743ef5d3cbc1ee0190e">anonymous{AArch64Arm64ECCallLowering.cpp}::AArch64Arm64ECCallLowering::runOnModule</a>.</p>

</div>
</div>

### create() {#a1726164ac15b6aa13ed5bbdd07f0a576}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">GlobalAlias * GlobalAlias::create (<a href="/web-llvm/docs/api/classes/llvm/type">Type</a> * Ty, unsigned AddressSpace, <a href="/web-llvm/docs/api/classes/llvm/globalvalue/#aedfa75f0c85c4aa85b257f066fbea57c">LinkageTypes</a> Linkage, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/twine">Twine</a> &amp; Name, <a href="/web-llvm/docs/api/classes/llvm/module">Module</a> * Parent)</td>
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



<p>Declaration at line 47 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/ir/globalalias-h">GlobalAlias.h</a>, definition at line 563 of file <a href="/web-llvm/docs/api/files/lib/lib/ir/globals-cpp">Globals.cpp</a>.</p>


<p>References <a href="#a8a638534b520f72ab7f2c886da739a6c">create</a>, <a href="/web-llvm/docs/api/classes/llvm/globalvalue/#ad61abcbd08169ff119e819ef0482744d">llvm::GlobalValue::Linkage</a> and <a href="/web-llvm/docs/api/classes/llvm/globalvalue/#acb71c8012dfaa189618d2cdafb58b4b0">llvm::GlobalValue::Parent</a>.</p>

</div>
</div>

### create() {#ab815632298cb8e2271e2a0e7062a7360}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">GlobalAlias * GlobalAlias::create (<a href="/web-llvm/docs/api/classes/llvm/type">Type</a> * Ty, unsigned AddressSpace, <a href="/web-llvm/docs/api/classes/llvm/globalvalue/#aedfa75f0c85c4aa85b257f066fbea57c">LinkageTypes</a> Linkage, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/twine">Twine</a> &amp; Name, <a href="/web-llvm/docs/api/classes/llvm/globalvalue">GlobalValue</a> * Aliasee)</td>
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



<p>Declaration at line 52 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/ir/globalalias-h">GlobalAlias.h</a>, definition at line 569 of file <a href="/web-llvm/docs/api/files/lib/lib/ir/globals-cpp">Globals.cpp</a>.</p>


<p>References <a href="#a8a638534b520f72ab7f2c886da739a6c">create</a>, <a href="/web-llvm/docs/api/classes/llvm/globalvalue/#a739b30c811f1eece61b05320ddf44e5b">llvm::GlobalValue::getParent</a>, <a href="/web-llvm/docs/api/classes/llvm/globalvalue/#af38a8629ae32606b01eacbbd667d831c">llvm::GlobalValue::GlobalValue</a> and <a href="/web-llvm/docs/api/classes/llvm/globalvalue/#ad61abcbd08169ff119e819ef0482744d">llvm::GlobalValue::Linkage</a>.</p>

</div>
</div>

### create() {#acc7ae6e57000b1f2e276fb96eba06213}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">GlobalAlias * GlobalAlias::create (<a href="/web-llvm/docs/api/classes/llvm/globalvalue/#aedfa75f0c85c4aa85b257f066fbea57c">LinkageTypes</a> Linkage, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/twine">Twine</a> &amp; Name, <a href="/web-llvm/docs/api/classes/llvm/globalvalue">GlobalValue</a> * Aliasee)</td>
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



<p>Declaration at line 57 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/ir/globalalias-h">GlobalAlias.h</a>, definition at line 575 of file <a href="/web-llvm/docs/api/files/lib/lib/ir/globals-cpp">Globals.cpp</a>.</p>


<p>References <a href="#a8a638534b520f72ab7f2c886da739a6c">create</a>, <a href="/web-llvm/docs/api/classes/llvm/globalvalue/#a702d4986803a1782ba305b1c7a0f1c21">llvm::GlobalValue::getAddressSpace</a>, <a href="/web-llvm/docs/api/classes/llvm/globalvalue/#af1dd2acfc2950742e41a64a342b15c80">llvm::GlobalValue::getValueType</a> and <a href="/web-llvm/docs/api/classes/llvm/globalvalue/#af38a8629ae32606b01eacbbd667d831c">llvm::GlobalValue::GlobalValue</a>.</p>

</div>
</div>

### create() {#a51d2023749f953a981e41484ca4ebfa6}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">GlobalAlias * GlobalAlias::create (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/twine">Twine</a> &amp; Name, <a href="/web-llvm/docs/api/classes/llvm/globalvalue">GlobalValue</a> * Aliasee)</td>
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



<p>Declaration at line 61 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/ir/globalalias-h">GlobalAlias.h</a>, definition at line 581 of file <a href="/web-llvm/docs/api/files/lib/lib/ir/globals-cpp">Globals.cpp</a>.</p>


<p>References <a href="#a8a638534b520f72ab7f2c886da739a6c">create</a>, <a href="/web-llvm/docs/api/classes/llvm/globalvalue/#a3547d58a060ee2e4a29cbea85bef91af">llvm::GlobalValue::getLinkage</a> and <a href="/web-llvm/docs/api/classes/llvm/globalvalue/#af38a8629ae32606b01eacbbd667d831c">llvm::GlobalValue::GlobalValue</a>.</p>

</div>
</div>

### isValidLinkage() {#a0dc1071ac8fdde2dc10ba6c7700598f4}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool llvm::GlobalAlias::isValidLinkage (<a href="/web-llvm/docs/api/classes/llvm/globalvalue/#aedfa75f0c85c4aa85b257f066fbea57c">LinkageTypes</a> L)</td>
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



<p>Definition at line 97 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/ir/globalalias-h">GlobalAlias.h</a>.</p>


<p>References <a href="/web-llvm/docs/api/classes/llvm/globalvalue/#a578061260691a59a9e7b0455fd68359c">llvm::GlobalValue::isAvailableExternallyLinkage</a>, <a href="/web-llvm/docs/api/classes/llvm/globalvalue/#a89a664b58385307fbb24c02e141d864b">llvm::GlobalValue::isExternalLinkage</a>, <a href="/web-llvm/docs/api/classes/llvm/globalvalue/#a4f4d5111c78b4b976e362d12f01ad782">llvm::GlobalValue::isLinkOnceLinkage</a>, <a href="/web-llvm/docs/api/classes/llvm/globalvalue/#a308b65a044b4f53e31a2026a81c991d2">llvm::GlobalValue::isLocalLinkage</a> and <a href="/web-llvm/docs/api/classes/llvm/globalvalue/#ad48190a47d8af6ce16465cda531725a9">llvm::GlobalValue::isWeakLinkage</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/classes/llvm/sandboxir/globalalias/#a12b24936a54e0a5f7c2e4f949a1d7da8">llvm::sandboxir::GlobalAlias::isValidLinkage</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Private Static Attributes

### AllocMarker {#a8999b0a08927a9dac47a6a44b711c38f}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">IntrusiveOperandsAllocMarker llvm::GlobalAlias::AllocMarker {1}</td>
</tr>
</table>
</td>
<td class="doxyMemberLabelsRight">
<span class="doxyMemberLabels">
<span class="doxyMemberLabel constexpr">constexpr</span>
<span class="doxyMemberLabel static">static</span>
</span>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 31 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/ir/globalalias-h">GlobalAlias.h</a>.</p>

</div>
</div>

</div>

<hr/>

The documentation for this class was generated from the following files:

<ul>
<li><a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/ir/globalalias-h">GlobalAlias.h</a></li>
<li><a href="/web-llvm/docs/api/files/lib/lib/ir/globals-cpp">Globals.cpp</a></li>
</ul>

<hr/>

<p class="doxyGeneratedBy">Generated via <a href="https://github.com/xpack/doxygen2docusaurus">doxygen2docusaurus</a> by <a href="https://www.doxygen.nl">Doxygen</a> 1.14.0.</p>

</div>
