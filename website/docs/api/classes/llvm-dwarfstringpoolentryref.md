---

# DO NOT EDIT!
# Automatically generated via doxygen2docusaurus by Doxygen.

slug: /api/classes/llvm/dwarfstringpoolentryref
custom_edit_url: null
toc_max_heading_level: 4
keywords:
  - doxygen
  - reference
  - class

---

<div class="doxyPage">

# The `DwarfStringPoolEntryRef` Class Reference

<p><a href="/web-llvm/docs/api/classes/llvm/dwarfstringpoolentryref">DwarfStringPoolEntryRef</a>: Dwarf string pool entry reference. <a href="#details">More...</a></p>

## Declaration

<div class="doxyDeclaration">
class llvm::DwarfStringPoolEntryRef { ... }
</div>

## Included Headers

<div class="doxyIncludesList">#include "<a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/codegen/dwarfstringpoolentry-h">llvm/CodeGen/DwarfStringPoolEntry.h</a>"
</div>

## Private Member Typedefs Index

<table class="doxyMembersIndex">

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">using</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a97a7b4f7aa69407049141bb91ed299a9">ByValStringEntryPtr</a> = <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/stringmapentry">StringMapEntry</a>&lt; <a href="/web-llvm/docs/api/structs/llvm/dwarfstringpoolentry">DwarfStringPoolEntry</a> &gt; *</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Pointer type for "By value" string entry. <a href="#a97a7b4f7aa69407049141bb91ed299a9">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">using</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a711f027e6410991c771ad61e420ec220">ExtStringEntryPtr</a> = <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/structs/llvm/dwarfstringpoolentrywithextstring">DwarfStringPoolEntryWithExtString</a> *</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Pointer type for external string entry. <a href="#a711f027e6410991c771ad61e420ec220">More...</a></p>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a747c3f0eda29a4b8cea30091c7e975cd">DwarfStringPoolEntryRef</a> ()=default</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#aba578baca5b932aec30ae208a5f2d251">DwarfStringPoolEntryRef</a> (const DwarfStringPoolEntryWithExtString &amp;Entry)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>ASSUMPTION: <a href="/web-llvm/docs/api/classes/llvm/dwarfstringpoolentryref">DwarfStringPoolEntryRef</a> keeps pointer to <span class="doxyComputerOutput">Entry</span>, thus specified entry mustn`t be reallocated. <a href="#aba578baca5b932aec30ae208a5f2d251">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

</table>

## Public Operators Index

<table class="doxyMembersIndex">

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a72652b3a9ad874224db0ac8a9cf3ace2">operator bool</a> () const</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a7faec5e3c71e75f99c6fcdcdd9ca602a">operator==</a> (const DwarfStringPoolEntryRef &amp;X) const</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a0db455ae963fb767ae7ba78ccf3007ba">operator!=</a> (const DwarfStringPoolEntryRef &amp;X) const</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/mcsymbol">MCSymbol</a> *</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ae0cadcb3f3cd8b7bad5fd2d044c24643">getSymbol</a> () const</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">uint64_t</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a74ed912ccb6cd7a7c5cc2a8543da9d89">getOffset</a> () const</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">unsigned</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a357ae759731d2b8d69f8613004f8c8b2">getIndex</a> () const</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a42fcdbe75a2931cb341fcdd3815147a9">getString</a> () const</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/structs/llvm/dwarfstringpoolentry">DwarfStringPoolEntry</a> &amp;</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a19bdd968558bb15b3dcf9477866c0ace">getEntry</a> () const</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/pointerunion">PointerUnion</a>&lt; <a href="/web-llvm/docs/api/classes/llvm/stringmapentry">ByValStringEntryPtr</a>, <a href="/web-llvm/docs/api/structs/llvm/dwarfstringpoolentrywithextstring">ExtStringEntryPtr</a> &gt;</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#abfe6c7bf1a876d28273f16121fc8fc56">MapEntry</a> = nullptr</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Pointer to the dwarf string pool Entry. <a href="#abfe6c7bf1a876d28273f16121fc8fc56">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

</table>

## Description {#details}

<p><a href="/web-llvm/docs/api/classes/llvm/dwarfstringpoolentryref">DwarfStringPoolEntryRef</a>: Dwarf string pool entry reference.</p>


<p>Dwarf string pool entry keeps string value and its data. There are two variants how data are represented:</p>


<ol class="doxyList" type="1">
<li>String data in pool - <a href="/web-llvm/docs/api/classes/llvm/stringmapentry">StringMapEntry&lt;DwarfStringPoolEntry&gt;</a>.</li>
<li>External string data - <a href="/web-llvm/docs/api/structs/llvm/dwarfstringpoolentrywithextstring">DwarfStringPoolEntryWithExtString</a>.</li>
</ol>

<p>The external data variant allows reducing memory usage for the case when string pool entry does not have data: string entry does not keep any data and so no need to waste space for the full <a href="/web-llvm/docs/api/structs/llvm/dwarfstringpoolentry">DwarfStringPoolEntry</a>. It is recommended to use external variant if not all entries of dwarf string pool have corresponding <a href="/web-llvm/docs/api/structs/llvm/dwarfstringpoolentry">DwarfStringPoolEntry</a>.</p>


<p>Definition at line 49 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/codegen/dwarfstringpoolentry-h">DwarfStringPoolEntry.h</a>.</p>


<div class="doxySectionDef">

## Private Member Typedefs

### ByValStringEntryPtr {#a97a7b4f7aa69407049141bb91ed299a9}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">using llvm::DwarfStringPoolEntryRef::ByValStringEntryPtr =  const StringMapEntry&lt;DwarfStringPoolEntry&gt; *</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Pointer type for "By value" string entry.</p>

<p>Definition at line 51 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/codegen/dwarfstringpoolentry-h">DwarfStringPoolEntry.h</a>.</p>

</div>
</div>

### ExtStringEntryPtr {#a711f027e6410991c771ad61e420ec220}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">using llvm::DwarfStringPoolEntryRef::ExtStringEntryPtr =  const DwarfStringPoolEntryWithExtString *</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Pointer type for external string entry.</p>

<p>Definition at line 54 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/codegen/dwarfstringpoolentry-h">DwarfStringPoolEntry.h</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Public Constructors

### DwarfStringPoolEntryRef() {#a747c3f0eda29a4b8cea30091c7e975cd}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">llvm::DwarfStringPoolEntryRef::DwarfStringPoolEntryRef ()</td>
</tr>
</table>
</td>
<td class="doxyMemberLabelsRight">
<span class="doxyMemberLabels">
<span class="doxyMemberLabel default">default</span>
</span>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 60 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/codegen/dwarfstringpoolentry-h">DwarfStringPoolEntry.h</a>.</p>


<p>Referenced by <a href="#a0db455ae963fb767ae7ba78ccf3007ba">operator!=</a> and <a href="#a7faec5e3c71e75f99c6fcdcdd9ca602a">operator==</a>.</p>

</div>
</div>

### DwarfStringPoolEntryRef() {#aba578baca5b932aec30ae208a5f2d251}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">llvm::DwarfStringPoolEntryRef::DwarfStringPoolEntryRef (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/structs/llvm/dwarfstringpoolentrywithextstring">DwarfStringPoolEntryWithExtString</a> &amp; Entry)</td>
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

<p>ASSUMPTION: <a href="/web-llvm/docs/api/classes/llvm/dwarfstringpoolentryref">DwarfStringPoolEntryRef</a> keeps pointer to <span class="doxyComputerOutput">Entry</span>, thus specified entry mustn`t be reallocated.</p>


<p>DwarfStringPoolEntryRef(const StringMapEntry&lt;DwarfStringPoolEntry&gt; &amp;Entry) : MapEntry(&amp;Entry) {}</p>


<p>/ ASSUMPTION: <a href="/web-llvm/docs/api/classes/llvm/dwarfstringpoolentryref">DwarfStringPoolEntryRef</a> keeps pointer to <span class="doxyComputerOutput">Entry</span>, / thus specified entry mustn`t be reallocated.</p>


<p>Definition at line 69 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/codegen/dwarfstringpoolentry-h">DwarfStringPoolEntry.h</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Public Operators

### operator bool() {#a72652b3a9ad874224db0ac8a9cf3ace2}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">llvm::DwarfStringPoolEntryRef::operator bool ()</td>
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



<p>Definition at line 72 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/codegen/dwarfstringpoolentry-h">DwarfStringPoolEntry.h</a>.</p>

</div>
</div>

### operator!=() {#a0db455ae963fb767ae7ba78ccf3007ba}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool llvm::DwarfStringPoolEntryRef::operator!= (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/dwarfstringpoolentryref">DwarfStringPoolEntryRef</a> &amp; X)</td>
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



<p>Definition at line 109 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/codegen/dwarfstringpoolentry-h">DwarfStringPoolEntry.h</a>.</p>


<p>References <a href="#a747c3f0eda29a4b8cea30091c7e975cd">DwarfStringPoolEntryRef</a> and <a href="/web-llvm/docs/api/files/lib/lib/tablegen/tablegenbackendskeleton-cpp/#ab60f28d7a141ac46ccc200176a1bca8b">X</a>.</p>

</div>
</div>

### operator==() {#a7faec5e3c71e75f99c6fcdcdd9ca602a}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool llvm::DwarfStringPoolEntryRef::operator== (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/dwarfstringpoolentryref">DwarfStringPoolEntryRef</a> &amp; X)</td>
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



<p>Definition at line 105 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/codegen/dwarfstringpoolentry-h">DwarfStringPoolEntry.h</a>.</p>


<p>References <a href="#a747c3f0eda29a4b8cea30091c7e975cd">DwarfStringPoolEntryRef</a> and <a href="/web-llvm/docs/api/files/lib/lib/tablegen/tablegenbackendskeleton-cpp/#ab60f28d7a141ac46ccc200176a1bca8b">X</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Public Member Functions

### getEntry() {#a19bdd968558bb15b3dcf9477866c0ace}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">const DwarfStringPoolEntry &amp; llvm::DwarfStringPoolEntryRef::getEntry ()</td>
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




<dl class="doxySectionUser">
<dt>Returns</dt>
<dd><p>the entire string pool entry for convenience.</p></dd>
</dl>


<p>Definition at line 98 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/codegen/dwarfstringpoolentry-h">DwarfStringPoolEntry.h</a>.</p>


<p>References <a href="/web-llvm/docs/api/namespaces/llvm/#ac4fc845f5ed92de63cd4474f128f5fc5">llvm::cast</a> and <a href="/web-llvm/docs/api/namespaces/llvm/#a92ca992e52dddc420f4b069cae06dfbe">llvm::isa</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/classes/llvm/asmprinter/#a9543f11565255b1ee6791a72a9beb87e">llvm::AsmPrinter::emitDwarfStringOffset</a>, <a href="#a357ae759731d2b8d69f8613004f8c8b2">getIndex</a>, <a href="#a74ed912ccb6cd7a7c5cc2a8543da9d89">getOffset</a> and <a href="#ae0cadcb3f3cd8b7bad5fd2d044c24643">getSymbol</a>.</p>

</div>
</div>

### getIndex() {#a357ae759731d2b8d69f8613004f8c8b2}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">unsigned llvm::DwarfStringPoolEntryRef::getIndex ()</td>
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




<dl class="doxySectionUser">
<dt>Returns</dt>
<dd><p>index for the dwarf string.</p></dd>
</dl>


<p>Definition at line 84 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/codegen/dwarfstringpoolentry-h">DwarfStringPoolEntry.h</a>.</p>


<p>References <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/silowercontrolflow-cpp/#a4868c5d81c5ccc98c47aeab6244346a0">assert</a>, <a href="#a19bdd968558bb15b3dcf9477866c0ace">getEntry</a> and <a href="/web-llvm/docs/api/structs/llvm/dwarfstringpoolentry/#a5ec8790ec7c63fb9e58de82b2774fac9">llvm::DwarfStringPoolEntry::Index</a>.</p>

</div>
</div>

### getOffset() {#a74ed912ccb6cd7a7c5cc2a8543da9d89}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">uint64_t llvm::DwarfStringPoolEntryRef::getOffset ()</td>
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




<dl class="doxySectionUser">
<dt>Returns</dt>
<dd><p>offset for the dwarf string.</p></dd>
</dl>


<p>Definition at line 81 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/codegen/dwarfstringpoolentry-h">DwarfStringPoolEntry.h</a>.</p>


<p>References <a href="#a19bdd968558bb15b3dcf9477866c0ace">getEntry</a> and <a href="/web-llvm/docs/api/structs/llvm/dwarfstringpoolentry/#aa406c884c8fb2d9b2fee2aa3865d832d">llvm::DwarfStringPoolEntry::Offset</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/classes/llvm/nonrelocatablestringpool/#adcdd0ccc4040ffdb46a684d771cacf8f">llvm::NonRelocatableStringpool::getStringOffset</a>.</p>

</div>
</div>

### getString() {#a42fcdbe75a2931cb341fcdd3815147a9}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">StringRef llvm::DwarfStringPoolEntryRef::getString ()</td>
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




<dl class="doxySectionUser">
<dt>Returns</dt>
<dd><p>string.</p></dd>
</dl>


<p>Definition at line 90 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/codegen/dwarfstringpoolentry-h">DwarfStringPoolEntry.h</a>.</p>


<p>References <a href="/web-llvm/docs/api/namespaces/llvm/#ac4fc845f5ed92de63cd4474f128f5fc5">llvm::cast</a> and <a href="/web-llvm/docs/api/namespaces/llvm/#a92ca992e52dddc420f4b069cae06dfbe">llvm::isa</a>.</p>

</div>
</div>

### getSymbol() {#ae0cadcb3f3cd8b7bad5fd2d044c24643}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">MCSymbol * llvm::DwarfStringPoolEntryRef::getSymbol ()</td>
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




<dl class="doxySectionUser">
<dt>Returns</dt>
<dd><p>symbol for the dwarf string.</p></dd>
</dl>


<p>Definition at line 75 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/codegen/dwarfstringpoolentry-h">DwarfStringPoolEntry.h</a>.</p>


<p>References <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/silowercontrolflow-cpp/#a4868c5d81c5ccc98c47aeab6244346a0">assert</a>, <a href="#a19bdd968558bb15b3dcf9477866c0ace">getEntry</a> and <a href="/web-llvm/docs/api/structs/llvm/dwarfstringpoolentry/#acefe965e3ed0ea37d9578f82dc01cb7a">llvm::DwarfStringPoolEntry::Symbol</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Private Member Attributes

### MapEntry {#abfe6c7bf1a876d28273f16121fc8fc56}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">PointerUnion&lt;ByValStringEntryPtr, ExtStringEntryPtr&gt; llvm::DwarfStringPoolEntryRef::MapEntry = nullptr</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Pointer to the dwarf string pool Entry.</p>

<p>Definition at line 57 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/codegen/dwarfstringpoolentry-h">DwarfStringPoolEntry.h</a>.</p>

</div>
</div>

</div>

<hr/>

The documentation for this class was generated from the following file:

<ul>
<li><a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/codegen/dwarfstringpoolentry-h">DwarfStringPoolEntry.h</a></li>
</ul>

<hr/>

<p class="doxyGeneratedBy">Generated via <a href="https://github.com/xpack/doxygen2docusaurus">doxygen2docusaurus</a> by <a href="https://www.doxygen.nl">Doxygen</a> 1.14.0.</p>

</div>
