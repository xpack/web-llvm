---

# DO NOT EDIT!
# Automatically generated via doxygen2docusaurus by Doxygen.

slug: /api/classes/llvm/interferencecache/cursor
custom_edit_url: null
toc_max_heading_level: 4
keywords:
  - doxygen
  - reference
  - class

---

<div class="doxyPage">

# `Cursor` Class

<p><a href="/web-llvm/docs/api/classes/llvm/interferencecache/cursor">Cursor</a> - The primary query interface for the block interference cache. <a href="#details">More...</a></p>

## Declaration

<div class="doxyDeclaration">
class llvm::InterferenceCache::Cursor { ... }
</div>

## Included Headers

<div class="doxyIncludesList">#include "<a href="/web-llvm/docs/api/files/lib/lib/codegen/interferencecache-h">CodeGen/InterferenceCache.h</a>"
</div>

## Public Constructors Index

<table class="doxyMembersIndex">

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#aa0a4f1d8cf62c8cd37b9f930553f8c29">Cursor</a> ()=default</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p><a href="/web-llvm/docs/api/classes/llvm/interferencecache/cursor">Cursor</a> - Create a dangling cursor. <a href="#aa0a4f1d8cf62c8cd37b9f930553f8c29">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a79007e62f19d3152b1a76485129b342e">Cursor</a> (const Cursor &amp;O)</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a060dacad6880105cf20d825899c972f6">~Cursor</a> ()</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/interferencecache/cursor">Cursor</a> &amp;</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a613d7fdbbbe55f7417d17817b88906fb">operator=</a> (const Cursor &amp;O)</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ab224963b17c0a01b9d763dc0147fd445">setPhysReg</a> (InterferenceCache &amp;Cache, MCRegister PhysReg)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>setPhysReg - Point this cursor to PhysReg's interference. <a href="#ab224963b17c0a01b9d763dc0147fd445">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">void</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a9983769d5d0bcab7fb0385864fc52621">moveToBlock</a> (unsigned MBBNum)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>moveTo - Move cursor to basic block MBBNum. <a href="#a9983769d5d0bcab7fb0385864fc52621">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">bool</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a898f7966b7db810dc1487ac6ca267fd2">hasInterference</a> ()</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>hasInterference - Return true if the current block has any interference. <a href="#a898f7966b7db810dc1487ac6ca267fd2">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/slotindex">SlotIndex</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a00dd59b7037ee092a891c2ef1cd9e782">first</a> ()</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>first - Return the starting index of the first interfering range in the current block. <a href="#a00dd59b7037ee092a891c2ef1cd9e782">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/slotindex">SlotIndex</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a0166e26fb57071dbbb9f99570865616b">last</a> ()</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>last - Return the ending index of the last interfering range in the current block. <a href="#a0166e26fb57071dbbb9f99570865616b">More...</a></p>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ae06ef5bbcf1eccff583841f3c4e1496f">setEntry</a> (Entry *E)</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">Entry *</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a461f764cc7450659dc412df7def3c23d">CacheEntry</a> = nullptr</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> BlockInterference *</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a40ea0129e9f22f7c6b2d17a429cfbc8b">Current</a> = nullptr</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">static <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> BlockInterference</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a925e3c0aa153923df3148a322b45d334">NoInterference</a></td>
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

<p><a href="/web-llvm/docs/api/classes/llvm/interferencecache/cursor">Cursor</a> - The primary query interface for the block interference cache.</p>

<p>Definition at line 177 of file <a href="/web-llvm/docs/api/files/lib/lib/codegen/interferencecache-h">InterferenceCache.h</a>.</p>


<div class="doxySectionDef">

## Public Constructors

### Cursor() {#aa0a4f1d8cf62c8cd37b9f930553f8c29}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">llvm::InterferenceCache::Cursor::Cursor ()</td>
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

<p><a href="/web-llvm/docs/api/classes/llvm/interferencecache/cursor">Cursor</a> - Create a dangling cursor.</p>

<p>Definition at line 195 of file <a href="/web-llvm/docs/api/files/lib/lib/codegen/interferencecache-h">InterferenceCache.h</a>.</p>


<p>Referenced by <a href="#a79007e62f19d3152b1a76485129b342e">Cursor</a> and <a href="#a613d7fdbbbe55f7417d17817b88906fb">operator=</a>.</p>

</div>
</div>

### Cursor() {#a79007e62f19d3152b1a76485129b342e}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">llvm::InterferenceCache::Cursor::Cursor (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/interferencecache/cursor">Cursor</a> &amp; O)</td>
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



<p>Definition at line 197 of file <a href="/web-llvm/docs/api/files/lib/lib/codegen/interferencecache-h">InterferenceCache.h</a>.</p>


<p>Reference <a href="#aa0a4f1d8cf62c8cd37b9f930553f8c29">Cursor</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Public Destructor

### \~Cursor() {#a060dacad6880105cf20d825899c972f6}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">llvm::InterferenceCache::Cursor::~Cursor ()</td>
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



<p>Definition at line 206 of file <a href="/web-llvm/docs/api/files/lib/lib/codegen/interferencecache-h">InterferenceCache.h</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Public Operators

### operator=() {#a613d7fdbbbe55f7417d17817b88906fb}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">Cursor &amp; llvm::InterferenceCache::Cursor::operator= (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/interferencecache/cursor">Cursor</a> &amp; O)</td>
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



<p>Definition at line 201 of file <a href="/web-llvm/docs/api/files/lib/lib/codegen/interferencecache-h">InterferenceCache.h</a>.</p>


<p>Reference <a href="#aa0a4f1d8cf62c8cd37b9f930553f8c29">Cursor</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Public Member Functions

### first() {#a00dd59b7037ee092a891c2ef1cd9e782}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">SlotIndex llvm::InterferenceCache::Cursor::first ()</td>
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

<p>first - Return the starting index of the first interfering range in the current block.</p>

<p>Definition at line 229 of file <a href="/web-llvm/docs/api/files/lib/lib/codegen/interferencecache-h">InterferenceCache.h</a>.</p>

</div>
</div>

### hasInterference() {#a898f7966b7db810dc1487ac6ca267fd2}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool llvm::InterferenceCache::Cursor::hasInterference ()</td>
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

<p>hasInterference - Return true if the current block has any interference.</p>

<p>Definition at line 223 of file <a href="/web-llvm/docs/api/files/lib/lib/codegen/interferencecache-h">InterferenceCache.h</a>.</p>

</div>
</div>

### last() {#a0166e26fb57071dbbb9f99570865616b}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">SlotIndex llvm::InterferenceCache::Cursor::last ()</td>
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

<p>last - Return the ending index of the last interfering range in the current block.</p>

<p>Definition at line 235 of file <a href="/web-llvm/docs/api/files/lib/lib/codegen/interferencecache-h">InterferenceCache.h</a>.</p>

</div>
</div>

### moveToBlock() {#a9983769d5d0bcab7fb0385864fc52621}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void llvm::InterferenceCache::Cursor::moveToBlock (unsigned MBBNum)</td>
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

<p>moveTo - Move cursor to basic block MBBNum.</p>

<p>Definition at line 218 of file <a href="/web-llvm/docs/api/files/lib/lib/codegen/interferencecache-h">InterferenceCache.h</a>.</p>

</div>
</div>

### setPhysReg() {#ab224963b17c0a01b9d763dc0147fd445}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void llvm::InterferenceCache::Cursor::setPhysReg (<a href="/web-llvm/docs/api/classes/llvm/interferencecache">InterferenceCache</a> &amp; Cache, <a href="/web-llvm/docs/api/classes/llvm/mcregister">MCRegister</a> PhysReg)</td>
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

<p>setPhysReg - Point this cursor to PhysReg's interference.</p>

<p>Definition at line 209 of file <a href="/web-llvm/docs/api/files/lib/lib/codegen/interferencecache-h">InterferenceCache.h</a>.</p>


<p>References <a href="/web-llvm/docs/api/classes/llvm/interferencecache/#a84fcd8d255d4e68ab7c5beedb1f59194">llvm::InterferenceCache::InterferenceCache</a> and <a href="/web-llvm/docs/api/classes/llvm/mcregister/#a127e2906913fb89109f3e86397a559ad">llvm::MCRegister::isValid</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Private Member Functions

### setEntry() {#ae06ef5bbcf1eccff583841f3c4e1496f}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void llvm::InterferenceCache::Cursor::setEntry (Entry * E)</td>
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



<p>Definition at line 182 of file <a href="/web-llvm/docs/api/files/lib/lib/codegen/interferencecache-h">InterferenceCache.h</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Private Member Attributes

### CacheEntry {#a461f764cc7450659dc412df7def3c23d}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">Entry* llvm::InterferenceCache::Cursor::CacheEntry = nullptr</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 178 of file <a href="/web-llvm/docs/api/files/lib/lib/codegen/interferencecache-h">InterferenceCache.h</a>.</p>

</div>
</div>

### Current {#a40ea0129e9f22f7c6b2d17a429cfbc8b}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">const BlockInterference* llvm::InterferenceCache::Cursor::Current = nullptr</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 179 of file <a href="/web-llvm/docs/api/files/lib/lib/codegen/interferencecache-h">InterferenceCache.h</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Private Static Attributes

### NoInterference {#a925e3c0aa153923df3148a322b45d334}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">const InterferenceCache::BlockInterference InterferenceCache::Cursor::NoInterference</td>
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



<p>Definition at line 180 of file <a href="/web-llvm/docs/api/files/lib/lib/codegen/interferencecache-h">InterferenceCache.h</a>.</p>

</div>
</div>

</div>

<hr/>

The documentation for this class was generated from the following file:

<ul>
<li><a href="/web-llvm/docs/api/files/lib/lib/codegen/interferencecache-h">InterferenceCache.h</a></li>
</ul>

<hr/>

<p class="doxyGeneratedBy">Generated via <a href="https://github.com/xpack/doxygen2docusaurus">doxygen2docusaurus</a> by <a href="https://www.doxygen.nl">Doxygen</a> 1.15.0.</p>

</div>
