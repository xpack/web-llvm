---

# DO NOT EDIT!
# Automatically generated via doxygen2docusaurus by Doxygen.

slug: /api/structs/llvm/threadsafetrierawhashmap/value-type
custom_edit_url: null
toc_max_heading_level: 4
keywords:
  - doxygen
  - reference
  - struct

---

<div class="doxyPage">

# The `value_type` Struct Reference



## Declaration

<div class="doxyDeclaration">
struct llvm::ThreadSafeTrieRawHashMap::value_type { ... }
</div>

## Included Headers

<div class="doxyIncludesList">#include "<a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/adt/trierawhashmap-h">llvm/ADT/TrieRawHashMap.h</a>"
</div>

## Friends Index

<table class="doxyMembersIndex">

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">class</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a2962e2d74d5cbf89eaf9f75a82b2587e">LazyValueConstructor</a></td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#abac6482630a5a63d95aa3c5720f77610">value_type</a> (value_type &amp;&amp;)=default</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#aa63a7d2922c5ddd047875f538f18325b">value_type</a> (const value_type &amp;)=default</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#af3e944e2eb077ae6be4a3166252d94ff">value_type</a> (ArrayRef&lt; uint8_t &gt; Hash, const T &amp;Data)</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#abd488ac8fea3e9549f3bb896e2e00569">value_type</a> (ArrayRef&lt; uint8_t &gt; Hash, T &amp;&amp;Data)</td>
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

<tr class="doxyMemberIndexTemplate">
<td class="doxyMemberIndexTemplate" colspan="2"><div>template &lt;class... ArgsT&gt;</div></td>
</tr>
<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemNoTypeNameTemplate" colspan="2" align="left" valign="top"><a href="#a4c270b2371e10c4c16d9408008d70dd4">value_type</a> (ArrayRef&lt; uint8_t &gt; Hash, EmplaceTag, ArgsT &amp;&amp;...Args)</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/threadsafetrierawhashmap/#a6b45384f59859e36cbf243e4dc3db505">HashT</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a1001bb86898858150a2512e80e55657d">Hash</a></td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">T</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a0b50c0144b1c7d8dbee4772bc0d89247">Data</a></td>
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

## Private Static Functions Index

<table class="doxyMembersIndex">

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">static <a href="/web-llvm/docs/api/classes/llvm/threadsafetrierawhashmap/#a6b45384f59859e36cbf243e4dc3db505">HashT</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#aeb32432e657217adca68972c8b16f5cb">makeHash</a> (ArrayRef&lt; uint8_t &gt; HashRef)</td>
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


<p>Definition at line 187 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/adt/trierawhashmap-h">TrieRawHashMap.h</a>.</p>


<div class="doxySectionDef">

## Friends

### LazyValueConstructor {#a2962e2d74d5cbf89eaf9f75a82b2587e}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">friend class <a href="/web-llvm/docs/api/classes/llvm/threadsafetrierawhashmap/lazyvalueconstructor">LazyValueConstructor</a></td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">


<p>Definition at line 200 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/adt/trierawhashmap-h">TrieRawHashMap.h</a>.</p>


<p>Reference <a href="#a2962e2d74d5cbf89eaf9f75a82b2587e">llvm::ThreadSafeTrieRawHashMap&lt; T, NumHashBytes &gt;::value_type::LazyValueConstructor</a>.</p>


<p>Referenced by <a href="#a2962e2d74d5cbf89eaf9f75a82b2587e">llvm::ThreadSafeTrieRawHashMap&lt; T, NumHashBytes &gt;::value_type::LazyValueConstructor</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Public Constructors

### value\_type() {#abac6482630a5a63d95aa3c5720f77610}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">llvm::ThreadSafeTrieRawHashMap&lt; T, NumHashBytes &gt;::value_type::value_type (<a href="/web-llvm/docs/api/structs/llvm/threadsafetrierawhashmap/value-type">value_type</a> &amp;&amp;)</td>
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



<p>Definition at line 191 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/adt/trierawhashmap-h">TrieRawHashMap.h</a>.</p>


<p>Reference <a href="#abac6482630a5a63d95aa3c5720f77610">llvm::ThreadSafeTrieRawHashMap&lt; T, NumHashBytes &gt;::value_type::value_type</a>.</p>


<p>Referenced by <a href="#aa63a7d2922c5ddd047875f538f18325b">llvm::ThreadSafeTrieRawHashMap&lt; T, NumHashBytes &gt;::value_type::value_type</a> and <a href="#abac6482630a5a63d95aa3c5720f77610">llvm::ThreadSafeTrieRawHashMap&lt; T, NumHashBytes &gt;::value_type::value_type</a>.</p>

</div>
</div>

### value\_type() {#aa63a7d2922c5ddd047875f538f18325b}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">llvm::ThreadSafeTrieRawHashMap&lt; T, NumHashBytes &gt;::value_type::value_type (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/structs/llvm/threadsafetrierawhashmap/value-type">value_type</a> &amp;)</td>
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



<p>Definition at line 192 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/adt/trierawhashmap-h">TrieRawHashMap.h</a>.</p>


<p>Reference <a href="#abac6482630a5a63d95aa3c5720f77610">llvm::ThreadSafeTrieRawHashMap&lt; T, NumHashBytes &gt;::value_type::value_type</a>.</p>

</div>
</div>

### value\_type() {#af3e944e2eb077ae6be4a3166252d94ff}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">llvm::ThreadSafeTrieRawHashMap&lt; T, NumHashBytes &gt;::value_type::value_type (<a href="/web-llvm/docs/api/classes/llvm/arrayref">ArrayRef</a>&lt; uint8_t &gt; Hash, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> T &amp; Data)</td>
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



<p>Definition at line 194 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/adt/trierawhashmap-h">TrieRawHashMap.h</a>.</p>


<p>References <a href="#a0b50c0144b1c7d8dbee4772bc0d89247">llvm::ThreadSafeTrieRawHashMap&lt; T, NumHashBytes &gt;::value_type::Data</a>, <a href="#a1001bb86898858150a2512e80e55657d">llvm::ThreadSafeTrieRawHashMap&lt; T, NumHashBytes &gt;::value_type::Hash</a> and <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/mips/mips16isellowering-cpp/#a0acb682b8260ab1c60b918599864e2e5">T</a>.</p>

</div>
</div>

### value\_type() {#abd488ac8fea3e9549f3bb896e2e00569}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">llvm::ThreadSafeTrieRawHashMap&lt; T, NumHashBytes &gt;::value_type::value_type (<a href="/web-llvm/docs/api/classes/llvm/arrayref">ArrayRef</a>&lt; uint8_t &gt; Hash, T &amp;&amp; Data)</td>
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



<p>Definition at line 196 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/adt/trierawhashmap-h">TrieRawHashMap.h</a>.</p>


<p>References <a href="#a0b50c0144b1c7d8dbee4772bc0d89247">llvm::ThreadSafeTrieRawHashMap&lt; T, NumHashBytes &gt;::value_type::Data</a>, <a href="#a1001bb86898858150a2512e80e55657d">llvm::ThreadSafeTrieRawHashMap&lt; T, NumHashBytes &gt;::value_type::Hash</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#abfc9c7ecf70f66901e439f7c04ef3dbb">llvm::move</a> and <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/mips/mips16isellowering-cpp/#a0acb682b8260ab1c60b918599864e2e5">T</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Private Constructors

### value\_type() {#a4c270b2371e10c4c16d9408008d70dd4}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<div class="doxyMemberTemplate">template &lt;class... ArgsT&gt;</div>
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">llvm::ThreadSafeTrieRawHashMap&lt; T, NumHashBytes &gt;::value_type::value_type (<a href="/web-llvm/docs/api/classes/llvm/arrayref">ArrayRef</a>&lt; uint8_t &gt; Hash, EmplaceTag, ArgsT &amp;&amp;... Args)</td>
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



<p>Definition at line 204 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/adt/trierawhashmap-h">TrieRawHashMap.h</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Public Member Attributes

### Data {#a0b50c0144b1c7d8dbee4772bc0d89247}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">T llvm::ThreadSafeTrieRawHashMap&lt; T, NumHashBytes &gt;::value_type::Data</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 189 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/adt/trierawhashmap-h">TrieRawHashMap.h</a>.</p>


<p>Referenced by <a href="#af3e944e2eb077ae6be4a3166252d94ff">llvm::ThreadSafeTrieRawHashMap&lt; T, NumHashBytes &gt;::value_type::value_type</a> and <a href="#abd488ac8fea3e9549f3bb896e2e00569">llvm::ThreadSafeTrieRawHashMap&lt; T, NumHashBytes &gt;::value_type::value_type</a>.</p>

</div>
</div>

### Hash {#a1001bb86898858150a2512e80e55657d}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">const HashT llvm::ThreadSafeTrieRawHashMap&lt; T, NumHashBytes &gt;::value_type::Hash</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 188 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/adt/trierawhashmap-h">TrieRawHashMap.h</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/classes/llvm/threadsafetrierawhashmap/#a977e70a3331d8740cd387ecd59131cc0">llvm::ThreadSafeTrieRawHashMap&lt; T, NumHashBytes &gt;::insert</a>, <a href="#af3e944e2eb077ae6be4a3166252d94ff">llvm::ThreadSafeTrieRawHashMap&lt; T, NumHashBytes &gt;::value_type::value_type</a> and <a href="#abd488ac8fea3e9549f3bb896e2e00569">llvm::ThreadSafeTrieRawHashMap&lt; T, NumHashBytes &gt;::value_type::value_type</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Private Static Functions

### makeHash() {#aeb32432e657217adca68972c8b16f5cb}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">HashT llvm::ThreadSafeTrieRawHashMap&lt; T, NumHashBytes &gt;::value_type::makeHash (<a href="/web-llvm/docs/api/classes/llvm/arrayref">ArrayRef</a>&lt; uint8_t &gt; HashRef)</td>
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



<p>Definition at line 207 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/adt/trierawhashmap-h">TrieRawHashMap.h</a>.</p>

</div>
</div>

</div>

<hr/>

The documentation for this struct was generated from the following file:

<ul>
<li><a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/adt/trierawhashmap-h">TrieRawHashMap.h</a></li>
</ul>

<hr/>

<p class="doxyGeneratedBy">Generated via <a href="https://github.com/xpack/doxygen2docusaurus">doxygen2docusaurus</a> by <a href="https://www.doxygen.nl">Doxygen</a> 1.15.0.</p>

</div>
