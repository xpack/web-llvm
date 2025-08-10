---

# DO NOT EDIT!
# Automatically generated via doxygen2docusaurus by Doxygen.

slug: /api/classes/llvm/threadsafetrierawhashmap
custom_edit_url: null
toc_max_heading_level: 4
keywords:
  - doxygen
  - reference
  - class

---

<div class="doxyPage">

# `ThreadSafeTrieRawHashMap` Class Template

<p>Lock-free thread-safe hash-mapped trie. <a href="#details">More...</a></p>

## Declaration

<div class="doxyDeclaration">
template &lt;class T, size_t NumHashBytes&gt;
class llvm::ThreadSafeTrieRawHashMap&lt;T, NumHashBytes&gt; { ... }
</div>

## Included Headers

<div class="doxyIncludesList">#include "<a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/adt/trierawhashmap-h">llvm/ADT/TrieRawHashMap.h</a>"
</div>

## Base class

<table class="doxyMembersIndex">

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">class</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/threadsafetrierawhashmapbase">ThreadSafeTrieRawHashMapBase</a></td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>TrieRawHashMap - is a lock-free thread-safe trie that is can be used to store/index data based on a hash value. <a href="/web-llvm/docs/api/classes/llvm/threadsafetrierawhashmapbase/#details">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

</table>

## Public Member Typedefs Index

<table class="doxyMembersIndex">

<tr class="doxyMemberIndexTemplate">
<td class="doxyMemberIndexTemplate" colspan="2"><div>template &lt;class T, size_t NumHashBytes&gt;</div></td>
</tr>
<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemTypeTemplate" align="left" valign="top">using</td>
<td class="doxyMemberIndexItemNameTemplate" align="left" valign="top"><a href="#a6b45384f59859e36cbf243e4dc3db505">HashT</a> = std::array&lt; uint8_t, NumHashBytes &gt;</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexTemplate">
<td class="doxyMemberIndexTemplate" colspan="2"><div>template &lt;class T, size_t NumHashBytes&gt;</div></td>
</tr>
<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemTypeTemplate" align="left" valign="top">using</td>
<td class="doxyMemberIndexItemNameTemplate" align="left" valign="top"><a href="#a6f14f688e9bc56ec427b56aaeb9267ac">HashType</a> = <a href="#a6b45384f59859e36cbf243e4dc3db505">HashT</a></td>
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

<tr class="doxyMemberIndexTemplate">
<td class="doxyMemberIndexTemplate" colspan="2"><div>template &lt;class T, size_t NumHashBytes&gt;</div></td>
</tr>
<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemNoTypeNameTemplate" colspan="2" align="left" valign="top"><a href="#aa8d047a4708e34aa727230ae60404c08">ThreadSafeTrieRawHashMap</a> (std::optional&lt; size_t &gt; NumRootBits=std::nullopt, std::optional&lt; size_t &gt; NumSubtrieBits=std::nullopt)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexTemplate">
<td class="doxyMemberIndexTemplate" colspan="2"><div>template &lt;class T, size_t NumHashBytes&gt;</div></td>
</tr>
<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemNoTypeNameTemplate" colspan="2" align="left" valign="top"><a href="#acbc649a60f30e89d28857b67dc21dde4">ThreadSafeTrieRawHashMap</a> (ThreadSafeTrieRawHashMap &amp;&amp;)=default</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexTemplate">
<td class="doxyMemberIndexTemplate" colspan="2"><div>template &lt;class T, size_t NumHashBytes&gt;</div></td>
</tr>
<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemNoTypeNameTemplate" colspan="2" align="left" valign="top"><a href="#ab2f2843e0a5a306e133d58416a6f8596">ThreadSafeTrieRawHashMap</a> (const ThreadSafeTrieRawHashMap &amp;)=delete</td>
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

<tr class="doxyMemberIndexTemplate">
<td class="doxyMemberIndexTemplate" colspan="2"><div>template &lt;class T, size_t NumHashBytes&gt;</div></td>
</tr>
<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemNoTypeNameTemplate" colspan="2" align="left" valign="top"><a href="#adb9395d3295ddf120895498b02e2f673">~ThreadSafeTrieRawHashMap</a> ()</td>
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

<tr class="doxyMemberIndexTemplate">
<td class="doxyMemberIndexTemplate" colspan="2"><div>template &lt;class T, size_t NumHashBytes&gt;</div></td>
</tr>
<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemTypeTemplate" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/threadsafetrierawhashmap">ThreadSafeTrieRawHashMap</a> &amp;</td>
<td class="doxyMemberIndexItemNameTemplate" align="left" valign="top"><a href="#a39989a41e690c1b98d46b1876309e9b3">operator=</a> (ThreadSafeTrieRawHashMap &amp;&amp;)=delete</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexTemplate">
<td class="doxyMemberIndexTemplate" colspan="2"><div>template &lt;class T, size_t NumHashBytes&gt;</div></td>
</tr>
<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemTypeTemplate" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/threadsafetrierawhashmap">ThreadSafeTrieRawHashMap</a> &amp;</td>
<td class="doxyMemberIndexItemNameTemplate" align="left" valign="top"><a href="#a0ea51e7e0db451003d50ae45d2ac385b">operator=</a> (const ThreadSafeTrieRawHashMap &amp;)=delete</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexTemplate">
<td class="doxyMemberIndexTemplate" colspan="2"><div>template &lt;class T, size_t NumHashBytes&gt;</div></td>
</tr>
<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemTypeTemplate" align="left" valign="top">void</td>
<td class="doxyMemberIndexItemNameTemplate" align="left" valign="top"><a href="#abc391c1e6c335e191a5e653ab156d0e3">operator delete</a> (void *Ptr)</td>
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

<tr class="doxyMemberIndexTemplate">
<td class="doxyMemberIndexTemplate" colspan="2"><div>template &lt;class T, size_t NumHashBytes&gt;</div></td>
</tr>
<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemTypeTemplate" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/threadsafetrierawhashmap/pointer">pointer</a></td>
<td class="doxyMemberIndexItemNameTemplate" align="left" valign="top"><a href="#a6cd2c4f25dfbd382aca540c2ffeed8b9">insertLazy</a> (const_pointer Hint, ArrayRef&lt; uint8_t &gt; Hash, function_ref&lt; void(LazyValueConstructor)&gt; OnConstruct)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Insert with a hint. <a href="#a6cd2c4f25dfbd382aca540c2ffeed8b9">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexTemplate">
<td class="doxyMemberIndexTemplate" colspan="2"><div>template &lt;class T, size_t NumHashBytes&gt;</div></td>
</tr>
<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemTypeTemplate" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/threadsafetrierawhashmap/pointer">pointer</a></td>
<td class="doxyMemberIndexItemNameTemplate" align="left" valign="top"><a href="#a100f40ca3b95104219fddde1d2c86381">insertLazy</a> (ArrayRef&lt; uint8_t &gt; Hash, function_ref&lt; void(LazyValueConstructor)&gt; OnConstruct)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexTemplate">
<td class="doxyMemberIndexTemplate" colspan="2"><div>template &lt;class T, size_t NumHashBytes&gt;</div></td>
</tr>
<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemTypeTemplate" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/threadsafetrierawhashmap/pointer">pointer</a></td>
<td class="doxyMemberIndexItemNameTemplate" align="left" valign="top"><a href="#a86b2da64c041a829f4ea723fe69cfeb6">insert</a> (const_pointer Hint, value_type &amp;&amp;HashedData)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexTemplate">
<td class="doxyMemberIndexTemplate" colspan="2"><div>template &lt;class T, size_t NumHashBytes&gt;</div></td>
</tr>
<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemTypeTemplate" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/threadsafetrierawhashmap/pointer">pointer</a></td>
<td class="doxyMemberIndexItemNameTemplate" align="left" valign="top"><a href="#a977e70a3331d8740cd387ecd59131cc0">insert</a> (const_pointer Hint, const value_type &amp;HashedData)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexTemplate">
<td class="doxyMemberIndexTemplate" colspan="2"><div>template &lt;class T, size_t NumHashBytes&gt;</div></td>
</tr>
<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemTypeTemplate" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/threadsafetrierawhashmap/pointer">pointer</a></td>
<td class="doxyMemberIndexItemNameTemplate" align="left" valign="top"><a href="#a4d0d05a3c39242b69eec429ba4945c64">find</a> (ArrayRef&lt; uint8_t &gt; Hash)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexTemplate">
<td class="doxyMemberIndexTemplate" colspan="2"><div>template &lt;class T, size_t NumHashBytes&gt;</div></td>
</tr>
<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemTypeTemplate" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/threadsafetrierawhashmap/const-pointer">const_pointer</a></td>
<td class="doxyMemberIndexItemNameTemplate" align="left" valign="top"><a href="#a702eff07aa75ca8d8cfaba044f7b3f29">find</a> (ArrayRef&lt; uint8_t &gt; Hash) const</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexTemplate">
<td class="doxyMemberIndexTemplate" colspan="2"><div>template &lt;class T, size_t NumHashBytes&gt;</div></td>
</tr>
<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemTypeTemplate" align="left" valign="top"><a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/support/compiler-h/#aa863693eef567397d9c292da5bf22d34">LLVM_DUMP_METHOD</a> void</td>
<td class="doxyMemberIndexItemNameTemplate" align="left" valign="top"><a href="#a7a914a734fa37fdb1bb52291ecedc4b4">dump</a> () const</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexTemplate">
<td class="doxyMemberIndexTemplate" colspan="2"><div>template &lt;class T, size_t NumHashBytes&gt;</div></td>
</tr>
<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemTypeTemplate" align="left" valign="top">void</td>
<td class="doxyMemberIndexItemNameTemplate" align="left" valign="top"><a href="#aafdc5312a9cc637e22a61875e1a263f0">print</a> (raw_ostream &amp;OS) const</td>
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

<p>Lock-free thread-safe hash-mapped trie.</p>

<p>Definition at line 182 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/adt/trierawhashmap-h">TrieRawHashMap.h</a>.</p>


<div class="doxySectionDef">

## Public Member Typedefs

### HashT {#a6b45384f59859e36cbf243e4dc3db505}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<div class="doxyMemberTemplate">template &lt;class T, size_t NumHashBytes&gt;</div>
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">using llvm::ThreadSafeTrieRawHashMap&lt; T, NumHashBytes &gt;::HashT =  std::array&lt;uint8_t, NumHashBytes&gt;</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 184 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/adt/trierawhashmap-h">TrieRawHashMap.h</a>.</p>

</div>
</div>

### HashType {#a6f14f688e9bc56ec427b56aaeb9267ac}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<div class="doxyMemberTemplate">template &lt;class T, size_t NumHashBytes&gt;</div>
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">using llvm::ThreadSafeTrieRawHashMap&lt; T, NumHashBytes &gt;::HashType =  HashT</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 215 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/adt/trierawhashmap-h">TrieRawHashMap.h</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Public Constructors

### ThreadSafeTrieRawHashMap() {#aa8d047a4708e34aa727230ae60404c08}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<div class="doxyMemberTemplate">template &lt;class T, size_t NumHashBytes&gt;</div>
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">llvm::ThreadSafeTrieRawHashMap&lt; T, NumHashBytes &gt;::ThreadSafeTrieRawHashMap (std::optional&lt; size_t &gt; NumRootBits=std::nullopt, std::optional&lt; size_t &gt; NumSubtrieBits=std::nullopt)</td>
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



<p>Definition at line 350 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/adt/trierawhashmap-h">TrieRawHashMap.h</a>.</p>


<p>References <a href="/web-llvm/docs/api/classes/llvm/threadsafetrierawhashmapbase/#a634aba0be92e82ec8a94d804c5908ad2">llvm::ThreadSafeTrieRawHashMapBase::DefaultContentAllocAlign</a>, <a href="/web-llvm/docs/api/classes/llvm/threadsafetrierawhashmapbase/#a5f41768b20810e783418ff5ae0b0f51a">llvm::ThreadSafeTrieRawHashMapBase::DefaultContentAllocSize</a>, <a href="/web-llvm/docs/api/classes/llvm/threadsafetrierawhashmapbase/#a63a45375ca4651489077dbc94d008311">llvm::ThreadSafeTrieRawHashMapBase::DefaultContentOffset</a> and <a href="/web-llvm/docs/api/classes/llvm/threadsafetrierawhashmapbase/#a6e8722a5417fddf6486c3236e835173a">llvm::ThreadSafeTrieRawHashMapBase::ThreadSafeTrieRawHashMapBase</a>.</p>


<p>Referenced by <a href="#a0ea51e7e0db451003d50ae45d2ac385b">llvm::ThreadSafeTrieRawHashMap&lt; T, NumHashBytes &gt;::operator=</a>, <a href="#a39989a41e690c1b98d46b1876309e9b3">llvm::ThreadSafeTrieRawHashMap&lt; T, NumHashBytes &gt;::operator=</a>, <a href="#ab2f2843e0a5a306e133d58416a6f8596">llvm::ThreadSafeTrieRawHashMap&lt; T, NumHashBytes &gt;::ThreadSafeTrieRawHashMap</a> and <a href="#acbc649a60f30e89d28857b67dc21dde4">llvm::ThreadSafeTrieRawHashMap&lt; T, NumHashBytes &gt;::ThreadSafeTrieRawHashMap</a>.</p>

</div>
</div>

### ThreadSafeTrieRawHashMap() {#acbc649a60f30e89d28857b67dc21dde4}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<div class="doxyMemberTemplate">template &lt;class T, size_t NumHashBytes&gt;</div>
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">llvm::ThreadSafeTrieRawHashMap&lt; T, NumHashBytes &gt;::ThreadSafeTrieRawHashMap (<a href="/web-llvm/docs/api/classes/llvm/threadsafetrierawhashmap">ThreadSafeTrieRawHashMap</a> &amp;&amp;)</td>
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



<p>Definition at line 366 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/adt/trierawhashmap-h">TrieRawHashMap.h</a>.</p>


<p>Reference <a href="#aa8d047a4708e34aa727230ae60404c08">llvm::ThreadSafeTrieRawHashMap&lt; T, NumHashBytes &gt;::ThreadSafeTrieRawHashMap</a>.</p>

</div>
</div>

### ThreadSafeTrieRawHashMap() {#ab2f2843e0a5a306e133d58416a6f8596}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<div class="doxyMemberTemplate">template &lt;class T, size_t NumHashBytes&gt;</div>
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">llvm::ThreadSafeTrieRawHashMap&lt; T, NumHashBytes &gt;::ThreadSafeTrieRawHashMap (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/threadsafetrierawhashmap">ThreadSafeTrieRawHashMap</a> &amp;)</td>
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



<p>Definition at line 370 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/adt/trierawhashmap-h">TrieRawHashMap.h</a>.</p>


<p>Reference <a href="#aa8d047a4708e34aa727230ae60404c08">llvm::ThreadSafeTrieRawHashMap&lt; T, NumHashBytes &gt;::ThreadSafeTrieRawHashMap</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Public Destructor

### \~ThreadSafeTrieRawHashMap() {#adb9395d3295ddf120895498b02e2f673}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<div class="doxyMemberTemplate">template &lt;class T, size_t NumHashBytes&gt;</div>
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">llvm::ThreadSafeTrieRawHashMap&lt; T, NumHashBytes &gt;::~ThreadSafeTrieRawHashMap ()</td>
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



<p>Definition at line 357 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/adt/trierawhashmap-h">TrieRawHashMap.h</a>.</p>


<p>References <a href="/web-llvm/docs/api/classes/llvm/threadsafetrierawhashmapbase/#a5eda088431655fae36128201cafbb19b">llvm::ThreadSafeTrieRawHashMapBase::destroyImpl</a> and <a href="/web-llvm/docs/api/files/lib/lib/option/option-cpp/#a04665169063c8ca1f2ea96c27fc7c2b2">P</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Public Operators

### operator delete() {#abc391c1e6c335e191a5e653ab156d0e3}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<div class="doxyMemberTemplate">template &lt;class T, size_t NumHashBytes&gt;</div>
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void llvm::ThreadSafeTrieRawHashMapBase::operator delete (void * Ptr)</td>
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



<p>Definition at line 214 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/adt/trierawhashmap-h">TrieRawHashMap.h</a>.</p>

</div>
</div>

### operator=() {#a39989a41e690c1b98d46b1876309e9b3}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<div class="doxyMemberTemplate">template &lt;class T, size_t NumHashBytes&gt;</div>
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">ThreadSafeTrieRawHashMap &amp; llvm::ThreadSafeTrieRawHashMap&lt; T, NumHashBytes &gt;::operator= (<a href="/web-llvm/docs/api/classes/llvm/threadsafetrierawhashmap">ThreadSafeTrieRawHashMap</a> &amp;&amp;)</td>
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



<p>Definition at line 369 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/adt/trierawhashmap-h">TrieRawHashMap.h</a>.</p>


<p>Reference <a href="#aa8d047a4708e34aa727230ae60404c08">llvm::ThreadSafeTrieRawHashMap&lt; T, NumHashBytes &gt;::ThreadSafeTrieRawHashMap</a>.</p>

</div>
</div>

### operator=() {#a0ea51e7e0db451003d50ae45d2ac385b}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<div class="doxyMemberTemplate">template &lt;class T, size_t NumHashBytes&gt;</div>
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">ThreadSafeTrieRawHashMap &amp; llvm::ThreadSafeTrieRawHashMap&lt; T, NumHashBytes &gt;::operator= (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/threadsafetrierawhashmap">ThreadSafeTrieRawHashMap</a> &amp;)</td>
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



<p>Definition at line 372 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/adt/trierawhashmap-h">TrieRawHashMap.h</a>.</p>


<p>Reference <a href="#aa8d047a4708e34aa727230ae60404c08">llvm::ThreadSafeTrieRawHashMap&lt; T, NumHashBytes &gt;::ThreadSafeTrieRawHashMap</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Public Member Functions

### dump() {#a7a914a734fa37fdb1bb52291ecedc4b4}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<div class="doxyMemberTemplate">template &lt;class T, size_t NumHashBytes&gt;</div>
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">LLVM_DUMP_METHOD void llvm::ThreadSafeTrieRawHashMapBase::dump ()</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 217 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/adt/trierawhashmap-h">TrieRawHashMap.h</a>.</p>

</div>
</div>

### find() {#a4d0d05a3c39242b69eec429ba4945c64}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<div class="doxyMemberTemplate">template &lt;class T, size_t NumHashBytes&gt;</div>
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">pointer llvm::ThreadSafeTrieRawHashMap&lt; T, NumHashBytes &gt;::find (<a href="/web-llvm/docs/api/classes/llvm/arrayref">ArrayRef</a>&lt; uint8_t &gt; Hash)</td>
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



<p>Definition at line 340 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/adt/trierawhashmap-h">TrieRawHashMap.h</a>.</p>


<p>References <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/silowercontrolflow-cpp/#a4868c5d81c5ccc98c47aeab6244346a0">assert</a>, <a href="/web-llvm/docs/api/classes/llvm/threadsafetrierawhashmapbase/#a7184c737372d1fa8d3783e5000463f2b">llvm::ThreadSafeTrieRawHashMapBase::find</a> and <a href="/web-llvm/docs/api/classes/llvm/arrayref/#a85ffb6531d4cda988ea81f18d4e56fb7">llvm::ArrayRef&lt; T &gt;::size</a>.</p>

</div>
</div>

### find() {#a702eff07aa75ca8d8cfaba044f7b3f29}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<div class="doxyMemberTemplate">template &lt;class T, size_t NumHashBytes&gt;</div>
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">const_pointer llvm::ThreadSafeTrieRawHashMap&lt; T, NumHashBytes &gt;::find (<a href="/web-llvm/docs/api/classes/llvm/arrayref">ArrayRef</a>&lt; uint8_t &gt; Hash)</td>
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



<p>Definition at line 345 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/adt/trierawhashmap-h">TrieRawHashMap.h</a>.</p>


<p>References <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/silowercontrolflow-cpp/#a4868c5d81c5ccc98c47aeab6244346a0">assert</a>, <a href="/web-llvm/docs/api/classes/llvm/threadsafetrierawhashmapbase/#a7184c737372d1fa8d3783e5000463f2b">llvm::ThreadSafeTrieRawHashMapBase::find</a> and <a href="/web-llvm/docs/api/classes/llvm/arrayref/#a85ffb6531d4cda988ea81f18d4e56fb7">llvm::ArrayRef&lt; T &gt;::size</a>.</p>

</div>
</div>

### insert() {#a86b2da64c041a829f4ea723fe69cfeb6}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<div class="doxyMemberTemplate">template &lt;class T, size_t NumHashBytes&gt;</div>
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">pointer llvm::ThreadSafeTrieRawHashMap&lt; T, NumHashBytes &gt;::insert (<a href="/web-llvm/docs/api/classes/llvm/threadsafetrierawhashmap/const-pointer">const_pointer</a> Hint, <a href="/web-llvm/docs/api/structs/llvm/threadsafetrierawhashmap/value-type">value_type</a> &amp;&amp; HashedData)</td>
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



<p>Definition at line 329 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/adt/trierawhashmap-h">TrieRawHashMap.h</a>.</p>


<p>References <a href="/web-llvm/docs/api/namespaces/llvm/callingconv/#ac6aa1387c4375260e2468eb5a77fdb4cafd841a49aec1539bc88abc8ff9e170fb">llvm::CallingConv::C</a> and <a href="#a6cd2c4f25dfbd382aca540c2ffeed8b9">llvm::ThreadSafeTrieRawHashMap&lt; T, NumHashBytes &gt;::insertLazy</a>.</p>

</div>
</div>

### insert() {#a977e70a3331d8740cd387ecd59131cc0}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<div class="doxyMemberTemplate">template &lt;class T, size_t NumHashBytes&gt;</div>
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">pointer llvm::ThreadSafeTrieRawHashMap&lt; T, NumHashBytes &gt;::insert (<a href="/web-llvm/docs/api/classes/llvm/threadsafetrierawhashmap/const-pointer">const_pointer</a> Hint, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/structs/llvm/threadsafetrierawhashmap/value-type">value_type</a> &amp; HashedData)</td>
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



<p>Definition at line 335 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/adt/trierawhashmap-h">TrieRawHashMap.h</a>.</p>


<p>References <a href="/web-llvm/docs/api/namespaces/llvm/callingconv/#ac6aa1387c4375260e2468eb5a77fdb4cafd841a49aec1539bc88abc8ff9e170fb">llvm::CallingConv::C</a>, <a href="/web-llvm/docs/api/structs/llvm/threadsafetrierawhashmap/value-type/#a1001bb86898858150a2512e80e55657d">llvm::ThreadSafeTrieRawHashMap&lt; T, NumHashBytes &gt;::value_type::Hash</a> and <a href="#a6cd2c4f25dfbd382aca540c2ffeed8b9">llvm::ThreadSafeTrieRawHashMap&lt; T, NumHashBytes &gt;::insertLazy</a>.</p>

</div>
</div>

### insertLazy() {#a6cd2c4f25dfbd382aca540c2ffeed8b9}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<div class="doxyMemberTemplate">template &lt;class T, size_t NumHashBytes&gt;</div>
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">pointer llvm::ThreadSafeTrieRawHashMap&lt; T, NumHashBytes &gt;::insertLazy (<a href="/web-llvm/docs/api/classes/llvm/threadsafetrierawhashmap/const-pointer">const_pointer</a> Hint, <a href="/web-llvm/docs/api/classes/llvm/arrayref">ArrayRef</a>&lt; uint8_t &gt; Hash, <a href="/web-llvm/docs/api/classes/llvm/function-ref">function_ref</a>&lt; void(<a href="/web-llvm/docs/api/classes/llvm/threadsafetrierawhashmap/lazyvalueconstructor">LazyValueConstructor</a>)&gt; OnConstruct)</td>
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

<p>Insert with a hint.</p>


<p>Default-constructed hint will work, but it's recommended to start with a lookup to avoid overhead in object creation if it already exists.</p>


<p>Definition at line 314 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/adt/trierawhashmap-h">TrieRawHashMap.h</a>.</p>


<p>Reference <a href="/web-llvm/docs/api/classes/llvm/threadsafetrierawhashmapbase/#aa9dbc0a952dfbed82b71fd482c4fcdd7">llvm::ThreadSafeTrieRawHashMapBase::insert</a>.</p>


<p>Referenced by <a href="#a977e70a3331d8740cd387ecd59131cc0">llvm::ThreadSafeTrieRawHashMap&lt; T, NumHashBytes &gt;::insert</a>, <a href="#a86b2da64c041a829f4ea723fe69cfeb6">llvm::ThreadSafeTrieRawHashMap&lt; T, NumHashBytes &gt;::insert</a> and <a href="#a100f40ca3b95104219fddde1d2c86381">llvm::ThreadSafeTrieRawHashMap&lt; T, NumHashBytes &gt;::insertLazy</a>.</p>

</div>
</div>

### insertLazy() {#a100f40ca3b95104219fddde1d2c86381}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<div class="doxyMemberTemplate">template &lt;class T, size_t NumHashBytes&gt;</div>
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">pointer llvm::ThreadSafeTrieRawHashMap&lt; T, NumHashBytes &gt;::insertLazy (<a href="/web-llvm/docs/api/classes/llvm/arrayref">ArrayRef</a>&lt; uint8_t &gt; Hash, <a href="/web-llvm/docs/api/classes/llvm/function-ref">function_ref</a>&lt; void(<a href="/web-llvm/docs/api/classes/llvm/threadsafetrierawhashmap/lazyvalueconstructor">LazyValueConstructor</a>)&gt; OnConstruct)</td>
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



<p>Definition at line 324 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/adt/trierawhashmap-h">TrieRawHashMap.h</a>.</p>


<p>Reference <a href="#a6cd2c4f25dfbd382aca540c2ffeed8b9">llvm::ThreadSafeTrieRawHashMap&lt; T, NumHashBytes &gt;::insertLazy</a>.</p>

</div>
</div>

### print() {#aafdc5312a9cc637e22a61875e1a263f0}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<div class="doxyMemberTemplate">template &lt;class T, size_t NumHashBytes&gt;</div>
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void llvm::ThreadSafeTrieRawHashMapBase::print (<a href="/web-llvm/docs/api/classes/llvm/raw-ostream">raw_ostream</a> &amp; OS)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 218 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/adt/trierawhashmap-h">TrieRawHashMap.h</a>.</p>

</div>
</div>

</div>

<hr/>

The documentation for this class was generated from the following file:

<ul>
<li><a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/adt/trierawhashmap-h">TrieRawHashMap.h</a></li>
</ul>

<hr/>

<p class="doxyGeneratedBy">Generated via <a href="https://xpack.github.io/doxygen2docusaurus">doxygen2docusaurus</a> 2.0.0 by <a href="https://www.doxygen.nl">Doxygen</a> 1.15.0.</p>

</div>
