---

# DO NOT EDIT!
# Automatically generated via doxygen2docusaurus by Doxygen.

slug: /api/classes/llvm/mdstring
custom_edit_url: null
toc_max_heading_level: 4
keywords:
  - doxygen
  - reference
  - class

---

<div class="doxyPage">

# The `MDString` Class Reference

<p>A single uniqued string. <a href="#details">More...</a></p>

## Declaration

<div class="doxyDeclaration">
class llvm::MDString { ... }
</div>

## Included Headers

<div class="doxyIncludesList">#include "<a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/ir/metadata-h">llvm/IR/Metadata.h</a>"
</div>

## Base class

<table class="doxyMembersIndex">

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">class</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/metadata">Metadata</a></td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Root of the metadata hierarchy. <a href="/web-llvm/docs/api/classes/llvm/metadata/#details">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

</table>

## Public Member Typedefs Index

<table class="doxyMembersIndex">

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">using</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#af5cb2da72a1899a861bdc32543192221">iterator</a> = <a href="/web-llvm/docs/api/classes/llvm/stringref/#a20d37563688a61a452fb26e317e37308">StringRef::iterator</a></td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a08d8fe1cd92e8c7f4e5685cc16d375dc">StringMapEntryStorage&lt; MDString &gt;</a></td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a3fef673f00b9e0e41583888c939dbe9c">MDString</a> (const MDString &amp;)=delete</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#acce9213c68103ac42078fc8fac23214b">MDString</a> ()</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/mdstring">MDString</a> &amp;</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a504aee07150fb0746bdbbfa327ebf576">operator=</a> (MDString &amp;&amp;)=delete</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/mdstring">MDString</a> &amp;</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#abe5957da46ec2bf145f4270ddc5c21b2">operator=</a> (const MDString &amp;)=delete</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ae44259d9edd71181ea8b89d18f27a967">getString</a> () const</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a24660608cb7d9de914c25457314ce881">getLength</a> () const</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="#af5cb2da72a1899a861bdc32543192221">iterator</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#aa6b5121c08e5d0f73aa31df414038205">begin</a> () const</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Pointer to the first byte of the string. <a href="#aa6b5121c08e5d0f73aa31df414038205">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="#af5cb2da72a1899a861bdc32543192221">iterator</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#afc7d9f82fb18fa4d24ef3667e89e9e6d">end</a> () const</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Pointer to one byte past the end of the string. <a href="#afc7d9f82fb18fa4d24ef3667e89e9e6d">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> unsigned char *</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a2a4ff2bbf405d8d803f239b15c88b2dd">bytes_begin</a> () const</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> unsigned char *</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#aa3641bf7a7d81855bc0518f1f102bc01">bytes_end</a> () const</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/stringmapentry">StringMapEntry</a>&lt; <a href="/web-llvm/docs/api/classes/llvm/mdstring">MDString</a> &gt; *</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#afa4c4bc5170ef1d2533022fc3431e434">Entry</a> = nullptr</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">static <a href="/web-llvm/docs/api/classes/llvm/mdstring">MDString</a> *</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#affbb7e2e9ad8d18114816f2443d672b9">get</a> (LLVMContext &amp;Context, StringRef Str)</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">static <a href="/web-llvm/docs/api/classes/llvm/mdstring">MDString</a> *</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a4b1b82b8b27267ef672fc3b3bad7fc56">get</a> (LLVMContext &amp;Context, const char *Str)</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a78dc01a1546e4f8b88d378910889b5a6">classof</a> (const Metadata *MD)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Methods for support type inquiry through isa, cast, and dyn_cast. <a href="#a78dc01a1546e4f8b88d378910889b5a6">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

</table>

## Description {#details}

<p>A single uniqued string.</p>


<p>These are used to efficiently contain a byte sequence for metadata. <a href="/web-llvm/docs/api/classes/llvm/mdstring">MDString</a> is always unnamed.</p>


<p>Definition at line 724 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/ir/metadata-h">Metadata.h</a>.</p>


<div class="doxySectionDef">

## Public Member Typedefs

### iterator {#af5cb2da72a1899a861bdc32543192221}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">using llvm::MDString::iterator =  StringRef::iterator</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 745 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/ir/metadata-h">Metadata.h</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Friends

### StringMapEntryStorage&lt; MDString &gt; {#a08d8fe1cd92e8c7f4e5685cc16d375dc}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">friend class <a href="/web-llvm/docs/api/classes/llvm/stringmapentrystorage">StringMapEntryStorage</a>&lt; <a href="/web-llvm/docs/api/classes/llvm/mdstring">MDString</a> &gt;</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">


<p>Definition at line 641 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/ir/metadata-h">Metadata.h</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Public Constructors

### MDString() {#a3fef673f00b9e0e41583888c939dbe9c}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">llvm::MDString::MDString (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/mdstring">MDString</a> &amp;)</td>
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



<p>Definition at line 732 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/ir/metadata-h">Metadata.h</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Private Constructors

### MDString() {#acce9213c68103ac42078fc8fac23214b}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">llvm::MDString::MDString ()</td>
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



<p>Definition at line 729 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/ir/metadata-h">Metadata.h</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Public Operators

### operator=() {#a504aee07150fb0746bdbbfa327ebf576}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">MDString &amp; llvm::MDString::operator= (<a href="/web-llvm/docs/api/classes/llvm/mdstring">MDString</a> &amp;&amp;)</td>
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



<p>Definition at line 733 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/ir/metadata-h">Metadata.h</a>.</p>

</div>
</div>

### operator=() {#abe5957da46ec2bf145f4270ddc5c21b2}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">MDString &amp; llvm::MDString::operator= (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/mdstring">MDString</a> &amp;)</td>
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



<p>Definition at line 734 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/ir/metadata-h">Metadata.h</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Public Member Functions

### begin() {#aa6b5121c08e5d0f73aa31df414038205}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">iterator llvm::MDString::begin ()</td>
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

<p>Pointer to the first byte of the string.</p>

<p>Definition at line 748 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/ir/metadata-h">Metadata.h</a>.</p>


<p>References <a href="/web-llvm/docs/api/classes/llvm/stringref/#a46f643f1eb1939362c7dd79361bcbd0e">llvm::StringRef::begin</a> and <a href="#ae44259d9edd71181ea8b89d18f27a967">getString</a>.</p>

</div>
</div>

### bytes\_begin() {#a2a4ff2bbf405d8d803f239b15c88b2dd}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">const unsigned char * llvm::MDString::bytes_begin ()</td>
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



<p>Definition at line 753 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/ir/metadata-h">Metadata.h</a>.</p>


<p>References <a href="/web-llvm/docs/api/classes/llvm/stringref/#adbc826dc76fd535f887e035d1795aa84">llvm::StringRef::bytes_begin</a> and <a href="#ae44259d9edd71181ea8b89d18f27a967">getString</a>.</p>

</div>
</div>

### bytes\_end() {#aa3641bf7a7d81855bc0518f1f102bc01}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">const unsigned char * llvm::MDString::bytes_end ()</td>
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



<p>Definition at line 754 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/ir/metadata-h">Metadata.h</a>.</p>


<p>References <a href="/web-llvm/docs/api/classes/llvm/stringref/#a25ba44ae8e92a80fde434e1ab19994cc">llvm::StringRef::bytes_end</a> and <a href="#ae44259d9edd71181ea8b89d18f27a967">getString</a>.</p>

</div>
</div>

### end() {#afc7d9f82fb18fa4d24ef3667e89e9e6d}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">iterator llvm::MDString::end ()</td>
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

<p>Pointer to one byte past the end of the string.</p>

<p>Definition at line 751 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/ir/metadata-h">Metadata.h</a>.</p>


<p>References <a href="/web-llvm/docs/api/classes/llvm/stringref/#a996c7ca3dd6843ba5d55a7c217770270">llvm::StringRef::end</a> and <a href="#ae44259d9edd71181ea8b89d18f27a967">getString</a>.</p>

</div>
</div>

### getLength() {#a24660608cb7d9de914c25457314ce881}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">unsigned llvm::MDString::getLength ()</td>
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



<p>Definition at line 743 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/ir/metadata-h">Metadata.h</a>.</p>


<p>References <a href="#ae44259d9edd71181ea8b89d18f27a967">getString</a> and <a href="/web-llvm/docs/api/classes/llvm/stringref/#a5db9240c74644c67759dd0f901fc3c7d">llvm::StringRef::size</a>.</p>

</div>
</div>

### getString() {#ae44259d9edd71181ea8b89d18f27a967}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">StringRef MDString::getString ()</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Declaration at line 741 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/ir/metadata-h">Metadata.h</a>, definition at line 616 of file <a href="/web-llvm/docs/api/files/lib/lib/ir/metadata-cpp">Metadata.cpp</a>.</p>


<p>Reference <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/silowercontrolflow-cpp/#a4868c5d81c5ccc98c47aeab6244346a0">assert</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/namespaces/llvm/#a55c9054d63d1c6a39e9c09ba13a482fa">llvm::addStringMetadataToLoop</a>, <a href="#aa6b5121c08e5d0f73aa31df414038205">begin</a>, <a href="#a2a4ff2bbf405d8d803f239b15c88b2dd">bytes_begin</a>, <a href="#aa3641bf7a7d81855bc0518f1f102bc01">bytes_end</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a78b74816ecfd86997bf31b5bc2eb0cd1">llvm::cacheAnnotationFromMD</a>, <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/instrumentation/memprofiler-cpp/#adced657ead8595f4da252cea6e2f3dd8">createProfileFileNameVar</a>, <a href="/web-llvm/docs/api/classes/llvm/webassemblyasmprinter/#af0cbac92300c3074e6bb81d58e92a86b">llvm::WebAssemblyAsmPrinter::emitEndOfAsmFile</a>, <a href="/web-llvm/docs/api/classes/anonymous-ppcasmprinter-cpp-/ppcaixasmprinter/#a3275b7a3457510661d5af13a82bb48ca">anonymous{PPCAsmPrinter.cpp}::PPCAIXAsmPrinter::emitModuleCommandLines</a>, <a href="#afc7d9f82fb18fa4d24ef3667e89e9e6d">end</a>, <a href="/web-llvm/docs/api/namespaces/anonymous-offloadbinary-cpp-/#a0f076ea04eda5249d0527c704881cdf1">anonymous{OffloadBinary.cpp}::extractFromBitcode</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#af96352a2cdb90eba4c80ba0a8109b269">llvm::findOptionMDForLoopID</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/spirv/spirvcalllowering-cpp/#a576d2f74177afc1ccafbf88b2ab0ab67">getArgAccessQual</a>, <a href="/web-llvm/docs/api/namespaces/llvm/omp/#a7f2eade374bf61ed94ab98b04803a079">llvm::omp::getDeviceKernels</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/r600openclimagetypeloweringpass-cpp/#a5bfeca5996966d19706f2a277e7c2341">GetFunctionFromMDNode</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/x86/x86framelowering-cpp/#ae2c3c56fbe514f4a3ee837a4af0499a8">getHiPELiteral</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/spirv/spirvcalllowering-cpp/#af66ee86d05581a75015e5b8d032c711a">getKernelArgTypeQual</a>, <a href="#a24660608cb7d9de914c25457314ce881">getLength</a>, <a href="/web-llvm/docs/api/files/lib/lib/ir/profilesummary-cpp/#a7a97b2924a1eec42ca579af0ce9de9e4">getSummaryFromMD</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#af455c80b53029287f35a7e3441eed512">llvm::GetUnrollMetadata</a>, <a href="/web-llvm/docs/api/files/lib/lib/ir/profilesummary-cpp/#a05ecd1a31f056076a50ef077fcf24ade">getValMD</a>, <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/scalar/loopunrollandjampass-cpp/#a9919c2ab68b72db8776ce21a276a6ba6">hasAnyUnrollPragma</a>, <a href="/web-llvm/docs/api/files/lib/lib/ir/debuginfometadata-cpp/#a97d418be7ec7fc90283cc2fee34599ce">isCanonical</a>, <a href="/web-llvm/docs/api/files/lib/lib/ir/profilesummary-cpp/#a29d2a01f35bf2e47da161025497073a9">isKeyValuePair</a>, <a href="/web-llvm/docs/api/classes/llvm/legalizerhelper/#a76df0b752eddd8b0711d1af16a3658ad">llvm::LegalizerHelper::lowerReadWriteRegister</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#ac8a1ae2e1de53a840bee516d1f5bb173">llvm::makePostTransformationMetadata</a> and <a href="/web-llvm/docs/api/classes/anonymous-bitcodereader-cpp-/bitcodereader/#a9154b11bdab240adc9c8acd18cf89717">anonymous{BitcodeReader.cpp}::BitcodeReader::materialize</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Private Member Attributes

### Entry {#afa4c4bc5170ef1d2533022fc3431e434}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">StringMapEntry&lt;MDString&gt;* llvm::MDString::Entry = nullptr</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 727 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/ir/metadata-h">Metadata.h</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Public Static Functions

### classof() {#a78dc01a1546e4f8b88d378910889b5a6}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool llvm::MDString::classof (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/metadata">Metadata</a> * MD)</td>
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

<p>Methods for support type inquiry through isa, cast, and dyn_cast.</p>

<p>Definition at line 757 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/ir/metadata-h">Metadata.h</a>.</p>


<p>References <a href="/web-llvm/docs/api/classes/llvm/metadata/#a91c7b9c7cf6694f41b9030429b582d26">llvm::Metadata::getMetadataID</a> and <a href="/web-llvm/docs/api/classes/llvm/metadata/#ac265aa582f1e66e4e45d6a964b9bd303">llvm::Metadata::Metadata</a>.</p>

</div>
</div>

### get() {#affbb7e2e9ad8d18114816f2443d672b9}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">MDString * MDString::get (<a href="/web-llvm/docs/api/classes/llvm/llvmcontext">LLVMContext</a> &amp; Context, <a href="/web-llvm/docs/api/classes/llvm/stringref">StringRef</a> Str)</td>
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



<p>Declaration at line 736 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/ir/metadata-h">Metadata.h</a>, definition at line 606 of file <a href="/web-llvm/docs/api/files/lib/lib/ir/metadata-cpp">Metadata.cpp</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/namespaces/anonymous-nvptxctordtorlowering-cpp-/#ae1b043855cc598a229a8389f9a116f74">anonymous{NVPTXCtorDtorLowering.cpp}::addKernelMetadata</a>, <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/vectorize/loopvectorize-cpp/#a033bb363914fbd3c2cd990330959036c">addRuntimeUnrollDisableMetaData</a>, <a href="/web-llvm/docs/api/classes/llvm/openmpirbuilder/#acd1fbb2df257f945afda92919be322f3">llvm::OpenMPIRBuilder::applySimd</a>, <a href="/web-llvm/docs/api/classes/anonymous-aarch64arm64eccalllowering-cpp-/aarch64arm64eccalllowering/#a7990af2ca325a18286d49b694c835c98">anonymous{AArch64Arm64ECCallLowering.cpp}::AArch64Arm64ECCallLowering::buildGuestExitThunk</a>, <a href="/web-llvm/docs/api/structs/anonymous-clonefunction-cpp-/pruningfunctioncloner/#afbf9fd3d3729664031c88766bcefcdf0">anonymous{CloneFunction.cpp}::PruningFunctionCloner::cloneInstruction</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/directx/dxiltranslatemetadata-cpp/#adcb7e087ebdb7b3e360160af660827c7">constructEntryMetadata</a>, <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/ipo/elimavailextern-cpp/#a0dff0e83176712b3e57686c7164eb7c0">convertToLocalCopy</a>, <a href="/web-llvm/docs/api/classes/llvm/coro/basecloner/#acfb266590cdac3ed6480244efcd5899c">llvm::coro::BaseCloner::create</a>, <a href="/web-llvm/docs/api/files/lib/lib/analysis/memoryprofileinfo-cpp/#a7cbecc17bbb64783431627bcf1f433c7">createMIBNode</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a21576774815efd6bd8374d3ac55c65f6">llvm::createPGONameMetadata</a>, <a href="/web-llvm/docs/api/classes/llvm/mdbuilder/#a7939b917f71d9664707d8ec51da88418">llvm::MDBuilder::createString</a>, <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/utils/looputils-cpp/#a6bfe058b12abe3443b07d4f4d55d863f">createStringMetadata</a>, <a href="/web-llvm/docs/api/classes/llvm/dibuilder/#a093b77c3612cbef1a9b29e680006f982">llvm::DIBuilder::createTemplateTemplateParameter</a>, <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/utils/loopconstrainer-cpp/#acd2295e6d5f183d1cad636c7a564660e">DisableAllLoopOptsOnLoop</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#ae744a53dbb2720e5678fb879156761e9">llvm::embedBufferInModule</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a5eeb42cfad58d947c605b1e21376e0b7">llvm::emitAMDGPUPrintfCall</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/directx/dxiltranslatemetadata-cpp/#aff40ddd6d0fc8a142d051bce619c2dee">emitShaderModelVersionMD</a>, <a href="#a4b1b82b8b27267ef672fc3b3bad7fc56">get</a>, <a href="/web-llvm/docs/api/classes/llvm/dxil/resourcebindinginfo/#a49b774bba229107958382054969b49bc">llvm::dxil::ResourceBindingInfo::getAsMetadata</a>, <a href="/web-llvm/docs/api/classes/llvm/dimacronode/#a9dc998f25a7d62a23a4ed8bde5b116c9">llvm::DIMacroNode::getCanonicalMDString</a>, <a href="/web-llvm/docs/api/classes/llvm/dinode/#a1c6cc0fd9d9b1a21354f035a9e1536e3">llvm::DINode::getCanonicalMDString</a>, <a href="/web-llvm/docs/api/files/lib/lib/ir/profilesummary-cpp/#a11c2adb7d4fc89c31daa94b1f8ced5a2">getKeyFPValMD</a>, <a href="/web-llvm/docs/api/files/lib/lib/ir/profilesummary-cpp/#a78a3f424681d435ef921cd141d3647ee">getKeyValMD</a>, <a href="/web-llvm/docs/api/files/lib/lib/ir/profilesummary-cpp/#a95456b3a4f4b949345b6f7c3fac2d4c4">getKeyValMD</a>, <a href="/web-llvm/docs/api/classes/llvm/mmrametadata/#a21debae1a7f83353999791930c1f54d2">llvm::MMRAMetadata::getTagMD</a>, <a href="/web-llvm/docs/api/classes/llvm/gcnttiimpl/#ae3d1835a72f8f0ba85ace9e2c0fbfc96">llvm::GCNTTIImpl::instCombineIntrinsic</a>, <a href="/web-llvm/docs/api/groups/llvmccorevaluemetadata/#gaa19549aa848905ca658ce4efe7f7b07b">LLVMMDStringInContext</a>, <a href="/web-llvm/docs/api/groups/llvmccorevaluemetadata/#ga645a6ce741bdd4d657c8ce1ca457075c">LLVMMDStringInContext2</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/spirv/spirvpreparefunctions-cpp/#a5e5cf24df0a45159407988a98fe42700">lowerPtrAnnotation</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/spirv/spirvpreparefunctions-cpp/#a90003a10d0a38bad6982d3037ffaf2e1">parseAnnotation</a>, <a href="/web-llvm/docs/api/classes/llvm/llparser/#a48a9cfa41a13b34d64b9dcb824d9075a">llvm::LLParser::parseMDField</a>, <a href="/web-llvm/docs/api/classes/anonymous-miparser-cpp-/miparser/#a83428d68b950a2dd6afc4c3292a82f49">anonymous{MIParser.cpp}::MIParser::parseMetadata</a>, <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/scalar/simpleloopunswitch-cpp/#a45007554e260296266b8ae927dde223f">postUnswitch</a>, <a href="/web-llvm/docs/api/classes/anonymous-aarch64arm64eccalllowering-cpp-/aarch64arm64eccalllowering/#a471ef961ae64095de93c59dea0a3262f">anonymous{AArch64Arm64ECCallLowering.cpp}::AArch64Arm64ECCallLowering::processFunction</a>, <a href="/web-llvm/docs/api/namespaces/anonymous-thinltobitcodewriter-cpp-/#a0a084f86091fd327d3113e8674c54192">anonymous{ThinLTOBitcodeWriter.cpp}::promoteTypeIds</a>, <a href="/web-llvm/docs/api/classes/llvm/sandboxir/region/#a8533fbc97a477c3f6a68cbef21bcb811">llvm::sandboxir::Region::Region</a>, <a href="/web-llvm/docs/api/files/lib/lib/codegen/jmcinstrumenter-cpp/#a8fe56fea0dcbc78bba2366b7e2918a41">runImpl</a>, <a href="/web-llvm/docs/api/classes/anonymous-aarch64arm64eccalllowering-cpp-/aarch64arm64eccalllowering/#a7b0a136ac6a10743ef5d3cbc1ee0190e">anonymous{AArch64Arm64ECCallLowering.cpp}::AArch64Arm64ECCallLowering::runOnModule</a>, <a href="/web-llvm/docs/api/classes/llvm/loopvectorizehints/#aa2f5ef2d522fb80de283a23d5bed6d86">llvm::LoopVectorizeHints::setAlreadyVectorized</a>, <a href="/web-llvm/docs/api/classes/llvm/loop/#ae27590daf21d575c9bb75c966fe256f2">llvm::Loop::setLoopAlreadyUnrolled</a>, <a href="/web-llvm/docs/api/classes/llvm/loop/#aa0930d54ec09b50bbfa09ec317e0df42">llvm::Loop::setLoopMustProgress</a>, <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/coroutines/coroframe-cpp/#acdaf5010e3f77d9d6e8ae04f5e0248e8">solveTypeName</a>, <a href="/web-llvm/docs/api/classes/llvm/openmpirbuilder/#a28a2a9806d828609fe107f766d2dd569">llvm::OpenMPIRBuilder::unrollLoopFull</a>, <a href="/web-llvm/docs/api/classes/llvm/openmpirbuilder/#a4ca0068cb6a50615c74ecdb8f23839e0">llvm::OpenMPIRBuilder::unrollLoopHeuristic</a>, <a href="/web-llvm/docs/api/classes/llvm/openmpirbuilder/#a5e2b7ac5f48193117a340aa15b085719">llvm::OpenMPIRBuilder::unrollLoopPartial</a>, <a href="/web-llvm/docs/api/files/lib/lib/frontend/lib/frontend/openmp/ompirbuilder-cpp/#a457f42a32df73079ac4526c572a2d7fd">updateNVPTXMetadata</a>, <a href="/web-llvm/docs/api/files/lib/lib/ir/autoupgrade-cpp/#a438f99943621d64eb8920e5075719b36">upgradeLoopTag</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a40c011ab750e2b4ea0d6b8076345cb0c">llvm::UpgradeModuleFlags</a>, <a href="/web-llvm/docs/api/files/lib/lib/ir/autoupgrade-cpp/#a227ca4549b5e29e59345b6a9bb74e531">upgradeRetainReleaseMarker</a>, <a href="/web-llvm/docs/api/classes/anonymous-spirvemitintrinsics-cpp-/spirvemitintrinsics/#ac6e0980539d623cb69d94e25d2e52481">anonymous{SPIRVEmitIntrinsics.cpp}::SPIRVEmitIntrinsics::visitCallInst</a> and <a href="/web-llvm/docs/api/classes/llvm/dxil/resourcebase/#aed1823c584ef7b7a15606d92eb4e2907">llvm::dxil::ResourceBase::write</a>.</p>

</div>
</div>

### get() {#a4b1b82b8b27267ef672fc3b3bad7fc56}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">MDString * llvm::MDString::get (<a href="/web-llvm/docs/api/classes/llvm/llvmcontext">LLVMContext</a> &amp; Context, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> char * Str)</td>
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



<p>Definition at line 737 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/ir/metadata-h">Metadata.h</a>.</p>


<p>Reference <a href="#affbb7e2e9ad8d18114816f2443d672b9">get</a>.</p>

</div>
</div>

</div>

<hr/>

The documentation for this class was generated from the following files:

<ul>
<li><a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/ir/metadata-h">Metadata.h</a></li>
<li><a href="/web-llvm/docs/api/files/lib/lib/ir/metadata-cpp">Metadata.cpp</a></li>
</ul>

<hr/>

<p class="doxyGeneratedBy">Generated via <a href="https://github.com/xpack/doxygen2docusaurus">doxygen2docusaurus</a> by <a href="https://www.doxygen.nl">Doxygen</a> 1.14.0.</p>

</div>
