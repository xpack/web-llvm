---

# DO NOT EDIT!
# Automatically generated via doxygen2docusaurus by Doxygen.

slug: /api/structs/anonymous-trierawhashmap-cpp-/triecontent
custom_edit_url: null
toc_max_heading_level: 4
keywords:
  - doxygen
  - reference
  - struct

---

<div class="doxyPage">

# The `TrieContent` Struct Reference



## Declaration

<div class="doxyDeclaration">
struct anonymous{TrieRawHashMap.cpp}::TrieContent { ... }
</div>

## Base struct

<table class="doxyMembersIndex">

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">struct</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="/web-llvm/docs/api/structs/anonymous-trierawhashmap-cpp-/trienode">TrieNode</a></td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ae35efd73d1292b67f0cb0e21f6296b71">TrieContent</a> (size_t ContentOffset, size_t HashSize, size_t HashOffset)</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">void *</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a16f59b5cb0c1bf73505868b855d99c49">getValuePointer</a> () const</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/arrayref">ArrayRef</a>&lt; uint8_t &gt;</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ae6037f49ba958c94b808f81091318259">getHash</a> () const</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> uint8_t</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ac7a39ef95379b34a2ec4e3eeb2c42020">ContentOffset</a></td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> uint8_t</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ac252405f58b3768f6e1b9d1144966fff">HashSize</a></td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> uint8_t</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ad9e639efa89526f55e0c8914139f5aaf">HashOffset</a></td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">static bool</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a6e526c4baacef3b513f1d41d800b87db">classof</a> (const TrieNode *TN)</td>
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


<p>Definition at line 33 of file <a href="/web-llvm/docs/api/files/lib/lib/support/trierawhashmap-cpp">TrieRawHashMap.cpp</a>.</p>


<div class="doxySectionDef">

## Public Constructors

### TrieContent() {#ae35efd73d1292b67f0cb0e21f6296b71}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">anonymous{TrieRawHashMap.cpp}::TrieContent::TrieContent (size_t ContentOffset, size_t HashSize, size_t HashOffset)</td>
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



<p>Definition at line 48 of file <a href="/web-llvm/docs/api/files/lib/lib/support/trierawhashmap-cpp">TrieRawHashMap.cpp</a>.</p>


<p>References <a href="#ac7a39ef95379b34a2ec4e3eeb2c42020">ContentOffset</a>, <a href="#ad9e639efa89526f55e0c8914139f5aaf">HashOffset</a>, <a href="#ac252405f58b3768f6e1b9d1144966fff">HashSize</a> and <a href="/web-llvm/docs/api/structs/anonymous-trierawhashmap-cpp-/trienode/#ab54b4f3940baf215ef3a6a684f1ff136">anonymous{TrieRawHashMap.cpp}::TrieNode::TrieNode</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Public Member Functions

### getHash() {#ae6037f49ba958c94b808f81091318259}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">ArrayRef&lt; uint8_t &gt; anonymous{TrieRawHashMap.cpp}::TrieContent::getHash ()</td>
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



<p>Definition at line 43 of file <a href="/web-llvm/docs/api/files/lib/lib/support/trierawhashmap-cpp">TrieRawHashMap.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/namespaces/llvm/#ab9c6b351507d3c0730f4290919d43a12">llvm::ArrayRef</a>, <a href="#ad9e639efa89526f55e0c8914139f5aaf">HashOffset</a> and <a href="#ac252405f58b3768f6e1b9d1144966fff">HashSize</a>.</p>

</div>
</div>

### getValuePointer() {#a16f59b5cb0c1bf73505868b855d99c49}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void * anonymous{TrieRawHashMap.cpp}::TrieContent::getValuePointer ()</td>
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



<p>Definition at line 38 of file <a href="/web-llvm/docs/api/files/lib/lib/support/trierawhashmap-cpp">TrieRawHashMap.cpp</a>.</p>


<p>Reference <a href="#ac7a39ef95379b34a2ec4e3eeb2c42020">ContentOffset</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/classes/llvm/threadsafetrierawhashmapbase/#a5eda088431655fae36128201cafbb19b">llvm::ThreadSafeTrieRawHashMapBase::destroyImpl</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Public Member Attributes

### ContentOffset {#ac7a39ef95379b34a2ec4e3eeb2c42020}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">const uint8_t anonymous{TrieRawHashMap.cpp}::TrieContent::ContentOffset</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 34 of file <a href="/web-llvm/docs/api/files/lib/lib/support/trierawhashmap-cpp">TrieRawHashMap.cpp</a>.</p>


<p>Referenced by <a href="#a16f59b5cb0c1bf73505868b855d99c49">getValuePointer</a> and <a href="#ae35efd73d1292b67f0cb0e21f6296b71">TrieContent</a>.</p>

</div>
</div>

### HashOffset {#ad9e639efa89526f55e0c8914139f5aaf}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">const uint8_t anonymous{TrieRawHashMap.cpp}::TrieContent::HashOffset</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 36 of file <a href="/web-llvm/docs/api/files/lib/lib/support/trierawhashmap-cpp">TrieRawHashMap.cpp</a>.</p>


<p>Referenced by <a href="#ae6037f49ba958c94b808f81091318259">getHash</a> and <a href="#ae35efd73d1292b67f0cb0e21f6296b71">TrieContent</a>.</p>

</div>
</div>

### HashSize {#ac252405f58b3768f6e1b9d1144966fff}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">const uint8_t anonymous{TrieRawHashMap.cpp}::TrieContent::HashSize</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 35 of file <a href="/web-llvm/docs/api/files/lib/lib/support/trierawhashmap-cpp">TrieRawHashMap.cpp</a>.</p>


<p>Referenced by <a href="#ae6037f49ba958c94b808f81091318259">getHash</a> and <a href="#ae35efd73d1292b67f0cb0e21f6296b71">TrieContent</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Public Static Functions

### classof() {#a6e526c4baacef3b513f1d41d800b87db}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool anonymous{TrieRawHashMap.cpp}::TrieContent::classof (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/structs/anonymous-trierawhashmap-cpp-/trienode">TrieNode</a> * TN)</td>
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



<p>Definition at line 52 of file <a href="/web-llvm/docs/api/files/lib/lib/support/trierawhashmap-cpp">TrieRawHashMap.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/structs/anonymous-trierawhashmap-cpp-/trienode/#a02767dbd01474060c7c37fee066a95e3">anonymous{TrieRawHashMap.cpp}::TrieNode::IsSubtrie</a> and <a href="/web-llvm/docs/api/structs/anonymous-trierawhashmap-cpp-/trienode/#ab54b4f3940baf215ef3a6a684f1ff136">anonymous{TrieRawHashMap.cpp}::TrieNode::TrieNode</a>.</p>

</div>
</div>

</div>

<hr/>

The documentation for this struct was generated from the following file:

<ul>
<li><a href="/web-llvm/docs/api/files/lib/lib/support/trierawhashmap-cpp">TrieRawHashMap.cpp</a></li>
</ul>

<hr/>

<p class="doxyGeneratedBy">Generated via <a href="https://github.com/xpack/doxygen2docusaurus">doxygen2docusaurus</a> by <a href="https://www.doxygen.nl">Doxygen</a> 1.15.0.</p>

</div>
