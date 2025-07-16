---

# DO NOT EDIT!
# Automatically generated via doxygen2docusaurus by Doxygen.

slug: /api/classes/anonymous-trierawhashmap-cpp-/triesubtrie
custom_edit_url: null
toc_max_heading_level: 4
keywords:
  - doxygen
  - reference
  - class

---

<div class="doxyPage">

# The `TrieSubtrie` Class Reference



## Declaration

<div class="doxyDeclaration">
class anonymous{TrieRawHashMap.cpp}::TrieSubtrie { ... }
</div>

## Base classes

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

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">class</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/trailingobjects">TrailingObjects&lt;BaseTy, TrailingTys&gt;</a></td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>See the file comment for details on the usage of the <a href="/web-llvm/docs/api/classes/llvm/trailingobjects">TrailingObjects</a> type. <a href="/web-llvm/docs/api/classes/llvm/trailingobjects/#details">More...</a></p>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a6996c570b76cf93ceb23d8f79348e2c2">Slot</a> = <a href="/web-llvm/docs/api/classes/llvm/lazyatomicpointer">LazyAtomicPointer</a>&lt; <a href="/web-llvm/docs/api/structs/anonymous-trierawhashmap-cpp-/trienode">TrieNode</a> &gt;</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a3058c4ae5e409b596a7b67af7f17e85d">llvm::ThreadSafeTrieRawHashMapBase</a></td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a831302f460304e1a0f0256fd8b18dea1">TrailingObjects</a></td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ad54871b3c817ff398c171e1e7fbc0978">TrieSubtrie</a> (size_t StartBit, size_t NumBits)</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="#a6996c570b76cf93ceb23d8f79348e2c2">Slot</a> &amp;</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a0fd383c00ab91f474abbb555d5e0840a">get</a> (size_t I)</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/structs/anonymous-trierawhashmap-cpp-/trienode">TrieNode</a> *</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a54f178ce84acefa6273a28f53e683438">load</a> (size_t I)</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a52c171146d9925ceee3351f9e339df1d">size</a> () const</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/anonymous-trierawhashmap-cpp-/triesubtrie">TrieSubtrie</a> *</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a31659d1af0527dde2c09079a42f9b216">sink</a> (size_t I, TrieContent &amp;Content, size_t NumSubtrieBits, size_t NewI, function_ref&lt; TrieSubtrie *(std::unique_ptr&lt; TrieSubtrie &gt;)&gt; Saver)</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">std::atomic&lt; <a href="/web-llvm/docs/api/classes/anonymous-trierawhashmap-cpp-/triesubtrie">TrieSubtrie</a> * &gt;</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a91056092060b2147bd8a8db168b7a52a">Next</a></td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Linked list for ownership of tries. The pointer is owned by <a href="/web-llvm/docs/api/classes/anonymous-trierawhashmap-cpp-/triesubtrie">TrieSubtrie</a>. <a href="#a91056092060b2147bd8a8db168b7a52a">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

</table>

## Private Member Attributes Index

<table class="doxyMembersIndex">

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">unsigned</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a9b7a73df76a627a51363116c79b4c7df">StartBit</a> = 0</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ad9a38ef60fc186852b8fdca56d952906">NumBits</a> = 0</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a0f998d2ac8301f56a0107346c9baf5cb">Size</a> = 0</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">static std::unique_ptr&lt; <a href="/web-llvm/docs/api/classes/anonymous-trierawhashmap-cpp-/triesubtrie">TrieSubtrie</a> &gt;</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a448cf4d7e13002d18ee5d82acfbcc087">create</a> (size_t StartBit, size_t NumBits)</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ab493c7187c7ac00e0183fd7fc6c7f7ca">classof</a> (const TrieNode *TN)</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">static constexpr size_t</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#add438f47dd390bd20e70745aeb21e9cb">sizeToAlloc</a> (unsigned NumBits)</td>
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


<p>Definition at line 59 of file <a href="/web-llvm/docs/api/files/lib/lib/support/trierawhashmap-cpp">TrieRawHashMap.cpp</a>.</p>


<div class="doxySectionDef">

## Public Member Typedefs

### Slot {#a6996c570b76cf93ceb23d8f79348e2c2}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">using anonymous{TrieRawHashMap.cpp}::TrieSubtrie::Slot =  LazyAtomicPointer&lt;TrieNode&gt;</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 63 of file <a href="/web-llvm/docs/api/files/lib/lib/support/trierawhashmap-cpp">TrieRawHashMap.cpp</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Friends

### llvm::ThreadSafeTrieRawHashMapBase {#a3058c4ae5e409b596a7b67af7f17e85d}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">friend class <a href="/web-llvm/docs/api/classes/llvm/threadsafetrierawhashmapbase">llvm::ThreadSafeTrieRawHashMapBase</a></td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">


<p>Definition at line 110 of file <a href="/web-llvm/docs/api/files/lib/lib/support/trierawhashmap-cpp">TrieRawHashMap.cpp</a>.</p>

</div>
</div>

### TrailingObjects {#a831302f460304e1a0f0256fd8b18dea1}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">friend class <a href="/web-llvm/docs/api/classes/llvm/trailingobjects">TrailingObjects</a></td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">


<p>Definition at line 111 of file <a href="/web-llvm/docs/api/files/lib/lib/support/trierawhashmap-cpp">TrieRawHashMap.cpp</a>.</p>


<p>Reference <a href="#a831302f460304e1a0f0256fd8b18dea1">TrailingObjects</a>.</p>


<p>Referenced by <a href="#a831302f460304e1a0f0256fd8b18dea1">TrailingObjects</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Public Constructors

### TrieSubtrie() {#ad54871b3c817ff398c171e1e7fbc0978}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">TrieSubtrie::TrieSubtrie (size_t StartBit, size_t NumBits)</td>
</tr>
</table>
</td>
<td class="doxyMemberLabelsRight">
<span class="doxyMemberLabels">
<span class="doxyMemberLabel explicit">explicit</span>
</span>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 76 of file <a href="/web-llvm/docs/api/files/lib/lib/support/trierawhashmap-cpp">TrieRawHashMap.cpp</a>.</p>


<p>References <a href="#a0fd383c00ab91f474abbb555d5e0840a">get</a>, <a href="/web-llvm/docs/api/files/lib/lib/support/md5-cpp/#ac0eafdc9ee161b71e7af98af736952fd">I</a>, <a href="#a91056092060b2147bd8a8db168b7a52a">Next</a>, <a href="/web-llvm/docs/api/structs/anonymous-trierawhashmap-cpp-/trienode/#ab54b4f3940baf215ef3a6a684f1ff136">anonymous{TrieRawHashMap.cpp}::TrieNode::TrieNode</a> and <a href="/web-llvm/docs/api/files/lib/lib/analysis/basicaliasanalysis-cpp/#af6d5cafbdfc5313e65d990120021a3ec">true</a>.</p>


<p>Referenced by <a href="#a448cf4d7e13002d18ee5d82acfbcc087">create</a> and <a href="#a31659d1af0527dde2c09079a42f9b216">sink</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Public Member Functions

### get() {#a0fd383c00ab91f474abbb555d5e0840a}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">Slot &amp; anonymous{TrieRawHashMap.cpp}::TrieSubtrie::get (size_t I)</td>
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



<p>Definition at line 65 of file <a href="/web-llvm/docs/api/files/lib/lib/support/trierawhashmap-cpp">TrieRawHashMap.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/classes/llvm/trailingobjects/#ab5f3828c41150c05c9b8142e98c35218">llvm::TrailingObjects&lt; TrieSubtrie, LazyAtomicPointer&lt; TrieNode &gt; &gt;::getTrailingObjects</a> and <a href="/web-llvm/docs/api/files/lib/lib/support/md5-cpp/#ac0eafdc9ee161b71e7af98af736952fd">I</a>.</p>


<p>Referenced by <a href="#a31659d1af0527dde2c09079a42f9b216">sink</a> and <a href="#ad54871b3c817ff398c171e1e7fbc0978">TrieSubtrie</a>.</p>

</div>
</div>

### load() {#a54f178ce84acefa6273a28f53e683438}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">TrieNode * anonymous{TrieRawHashMap.cpp}::TrieSubtrie::load (size_t I)</td>
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



<p>Definition at line 66 of file <a href="/web-llvm/docs/api/files/lib/lib/support/trierawhashmap-cpp">TrieRawHashMap.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/namespaces/llvm/#a73257f51950d9ea50955e3fb9c724a25">llvm::get</a>, <a href="/web-llvm/docs/api/files/lib/lib/support/md5-cpp/#ac0eafdc9ee161b71e7af98af736952fd">I</a> and <a href="/web-llvm/docs/api/structs/anonymous-trierawhashmap-cpp-/trienode/#ab54b4f3940baf215ef3a6a684f1ff136">anonymous{TrieRawHashMap.cpp}::TrieNode::TrieNode</a>.</p>

</div>
</div>

### sink() {#a31659d1af0527dde2c09079a42f9b216}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">TrieSubtrie * TrieSubtrie::sink (size_t I, <a href="/web-llvm/docs/api/structs/anonymous-trierawhashmap-cpp-/triecontent">TrieContent</a> &amp; Content, size_t NumSubtrieBits, size_t NewI, <a href="/web-llvm/docs/api/classes/llvm/function-ref">function_ref</a>&lt; <a href="/web-llvm/docs/api/classes/anonymous-trierawhashmap-cpp-/triesubtrie">TrieSubtrie</a> *(std::unique_ptr&lt; <a href="/web-llvm/docs/api/classes/anonymous-trierawhashmap-cpp-/triesubtrie">TrieSubtrie</a> &gt;)&gt; Saver)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 71 of file <a href="/web-llvm/docs/api/files/lib/lib/support/trierawhashmap-cpp">TrieRawHashMap.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/silowercontrolflow-cpp/#a4868c5d81c5ccc98c47aeab6244346a0">assert</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#ac4fc845f5ed92de63cd4474f128f5fc5">llvm::cast</a>, <a href="#a448cf4d7e13002d18ee5d82acfbcc087">create</a>, <a href="#a0fd383c00ab91f474abbb555d5e0840a">get</a>, <a href="/web-llvm/docs/api/files/lib/lib/support/md5-cpp/#ac0eafdc9ee161b71e7af98af736952fd">I</a>, <a href="/web-llvm/docs/api/structs/anonymous-trierawhashmap-cpp-/trienode/#ab54b4f3940baf215ef3a6a684f1ff136">anonymous{TrieRawHashMap.cpp}::TrieNode::TrieNode</a> and <a href="#ad54871b3c817ff398c171e1e7fbc0978">TrieSubtrie</a>.</p>

</div>
</div>

### size() {#a52c171146d9925ceee3351f9e339df1d}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">unsigned anonymous{TrieRawHashMap.cpp}::TrieSubtrie::size ()</td>
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



<p>Definition at line 68 of file <a href="/web-llvm/docs/api/files/lib/lib/support/trierawhashmap-cpp">TrieRawHashMap.cpp</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Public Member Attributes

### Next {#a91056092060b2147bd8a8db168b7a52a}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">std::atomic&lt;TrieSubtrie *&gt; anonymous{TrieRawHashMap.cpp}::TrieSubtrie::Next</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Linked list for ownership of tries. The pointer is owned by <a href="/web-llvm/docs/api/classes/anonymous-trierawhashmap-cpp-/triesubtrie">TrieSubtrie</a>.</p>

<p>Definition at line 115 of file <a href="/web-llvm/docs/api/files/lib/lib/support/trierawhashmap-cpp">TrieRawHashMap.cpp</a>.</p>


<p>Referenced by <a href="#ad54871b3c817ff398c171e1e7fbc0978">TrieSubtrie</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Private Member Attributes

### NumBits {#ad9a38ef60fc186852b8fdca56d952906}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">unsigned anonymous{TrieRawHashMap.cpp}::TrieSubtrie::NumBits = 0</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 108 of file <a href="/web-llvm/docs/api/files/lib/lib/support/trierawhashmap-cpp">TrieRawHashMap.cpp</a>.</p>

</div>
</div>

### Size {#a0f998d2ac8301f56a0107346c9baf5cb}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">unsigned anonymous{TrieRawHashMap.cpp}::TrieSubtrie::Size = 0</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 109 of file <a href="/web-llvm/docs/api/files/lib/lib/support/trierawhashmap-cpp">TrieRawHashMap.cpp</a>.</p>

</div>
</div>

### StartBit {#a9b7a73df76a627a51363116c79b4c7df}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">unsigned anonymous{TrieRawHashMap.cpp}::TrieSubtrie::StartBit = 0</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 107 of file <a href="/web-llvm/docs/api/files/lib/lib/support/trierawhashmap-cpp">TrieRawHashMap.cpp</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Public Static Functions

### classof() {#ab493c7187c7ac00e0183fd7fc6c7f7ca}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool anonymous{TrieRawHashMap.cpp}::TrieSubtrie::classof (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/structs/anonymous-trierawhashmap-cpp-/trienode">TrieNode</a> * TN)</td>
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



<p>Definition at line 78 of file <a href="/web-llvm/docs/api/files/lib/lib/support/trierawhashmap-cpp">TrieRawHashMap.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/structs/anonymous-trierawhashmap-cpp-/trienode/#a02767dbd01474060c7c37fee066a95e3">anonymous{TrieRawHashMap.cpp}::TrieNode::IsSubtrie</a> and <a href="/web-llvm/docs/api/structs/anonymous-trierawhashmap-cpp-/trienode/#ab54b4f3940baf215ef3a6a684f1ff136">anonymous{TrieRawHashMap.cpp}::TrieNode::TrieNode</a>.</p>

</div>
</div>

### create() {#a448cf4d7e13002d18ee5d82acfbcc087}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">std::unique_ptr&lt; TrieSubtrie &gt; TrieSubtrie::create (size_t StartBit, size_t NumBits)</td>
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



<p>Definition at line 74 of file <a href="/web-llvm/docs/api/files/lib/lib/support/trierawhashmap-cpp">TrieRawHashMap.cpp</a>.</p>


<p>References <a href="#add438f47dd390bd20e70745aeb21e9cb">sizeToAlloc</a> and <a href="#ad54871b3c817ff398c171e1e7fbc0978">TrieSubtrie</a>.</p>


<p>Referenced by <a href="#a31659d1af0527dde2c09079a42f9b216">sink</a>.</p>

</div>
</div>

### sizeToAlloc() {#add438f47dd390bd20e70745aeb21e9cb}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">constexpr size_t anonymous{TrieRawHashMap.cpp}::TrieSubtrie::sizeToAlloc (unsigned NumBits)</td>
</tr>
</table>
</td>
<td class="doxyMemberLabelsRight">
<span class="doxyMemberLabels">
<span class="doxyMemberLabel inline">inline</span>
<span class="doxyMemberLabel constexpr">constexpr</span>
<span class="doxyMemberLabel static">static</span>
</span>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 80 of file <a href="/web-llvm/docs/api/files/lib/lib/support/trierawhashmap-cpp">TrieRawHashMap.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/silowercontrolflow-cpp/#a4868c5d81c5ccc98c47aeab6244346a0">assert</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a845e08be4b0320d66901a66b0c0e9509">llvm::Count</a> and <a href="/web-llvm/docs/api/classes/llvm/trailingobjects/#a5b733cf2a7d7206c2d2601cc5b024488">llvm::TrailingObjects&lt; TrieSubtrie, LazyAtomicPointer&lt; TrieNode &gt; &gt;::totalSizeToAlloc</a>.</p>


<p>Referenced by <a href="#a448cf4d7e13002d18ee5d82acfbcc087">create</a> and <a href="/web-llvm/docs/api/classes/threadsafetrierawhashmapbase/impltype/#a6391503422f5981b6d2af8320a80d870">llvm::ThreadSafeTrieRawHashMapBase::ImplType::create</a>.</p>

</div>
</div>

</div>

<hr/>

The documentation for this class was generated from the following file:

<ul>
<li><a href="/web-llvm/docs/api/files/lib/lib/support/trierawhashmap-cpp">TrieRawHashMap.cpp</a></li>
</ul>

<hr/>

<p class="doxyGeneratedBy">Generated via <a href="https://github.com/xpack/doxygen2docusaurus">doxygen2docusaurus</a> by <a href="https://www.doxygen.nl">Doxygen</a> 1.15.0.</p>

</div>
