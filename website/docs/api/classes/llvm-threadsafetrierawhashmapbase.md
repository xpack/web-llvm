---

# DO NOT EDIT!
# Automatically generated via doxygen2docusaurus by Doxygen.

slug: /api/classes/llvm/threadsafetrierawhashmapbase
custom_edit_url: null
toc_max_heading_level: 4
keywords:
  - doxygen
  - reference
  - class

---

<div class="doxyPage">

# The `ThreadSafeTrieRawHashMapBase` Class Reference

<p>TrieRawHashMap - is a lock-free thread-safe trie that is can be used to store/index data based on a hash value. <a href="#details">More...</a></p>

## Declaration

<div class="doxyDeclaration">
class llvm::ThreadSafeTrieRawHashMapBase { ... }
</div>

## Included Headers

<div class="doxyIncludesList">#include "<a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/adt/trierawhashmap-h">llvm/ADT/TrieRawHashMap.h</a>"
</div>

## Derived Classes

<table class="doxyMembersIndex">

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">class</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/threadsafetrierawhashmap">ThreadSafeTrieRawHashMap&lt;T, NumHashBytes&gt;</a></td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Lock-free thread-safe hash-mapped trie. <a href="/web-llvm/docs/api/classes/llvm/threadsafetrierawhashmap/#details">More...</a></p>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a60c16bd183947477a36ab8c485638df3">TrieRawHashMapTestHelper</a></td>
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

## Protected Constructors Index

<table class="doxyMembersIndex">

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a6e8722a5417fddf6486c3236e835173a">ThreadSafeTrieRawHashMapBase</a> ()=delete</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a680f79939c5bb8275ff275c335b5fe5a">ThreadSafeTrieRawHashMapBase</a> (size_t ContentAllocSize, size_t ContentAllocAlign, size_t ContentOffset, std::optional&lt; size_t &gt; NumRootBits=std::nullopt, std::optional&lt; size_t &gt; NumSubtrieBits=std::nullopt)</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a900dd95fc13a72dbc38c3e95694461f8">ThreadSafeTrieRawHashMapBase</a> (ThreadSafeTrieRawHashMapBase &amp;&amp;RHS)</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#af50f504b9f39e93ea34cb323db970930">ThreadSafeTrieRawHashMapBase</a> (const ThreadSafeTrieRawHashMapBase &amp;)=delete</td>
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

## Protected Destructor Index

<table class="doxyMembersIndex">

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a538ad0b852455c782b91c9e3c994de70">~ThreadSafeTrieRawHashMapBase</a> ()</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Destructor, which asserts if there's anything to do. <a href="#a538ad0b852455c782b91c9e3c994de70">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

</table>

## Public Operators Index

<table class="doxyMembersIndex">

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">void</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#abc391c1e6c335e191a5e653ab156d0e3">operator delete</a> (void *Ptr)</td>
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

## Protected Operators Index

<table class="doxyMembersIndex">

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/threadsafetrierawhashmapbase">ThreadSafeTrieRawHashMapBase</a> &amp;</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ab47b2bca06a2ac9847d8835081b29b3b">operator=</a> (ThreadSafeTrieRawHashMapBase &amp;&amp;RHS)=delete</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/threadsafetrierawhashmapbase">ThreadSafeTrieRawHashMapBase</a> &amp;</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a52152a25da14c6579308fa9de4045935">operator=</a> (const ThreadSafeTrieRawHashMapBase &amp;)=delete</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/support/compiler-h/#aa863693eef567397d9c292da5bf22d34">LLVM_DUMP_METHOD</a> void</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a7a914a734fa37fdb1bb52291ecedc4b4">dump</a> () const</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#aafdc5312a9cc637e22a61875e1a263f0">print</a> (raw_ostream &amp;OS) const</td>
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

## Protected Member Functions Index

<table class="doxyMembersIndex">

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/threadsafetrierawhashmapbase/pointerbase">PointerBase</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a7184c737372d1fa8d3783e5000463f2b">find</a> (ArrayRef&lt; uint8_t &gt; Hash) const</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Find the stored content with hash. <a href="#a7184c737372d1fa8d3783e5000463f2b">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/threadsafetrierawhashmapbase/pointerbase">PointerBase</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#aa9dbc0a952dfbed82b71fd482c4fcdd7">insert</a> (PointerBase Hint, ArrayRef&lt; uint8_t &gt; Hash, function_ref&lt; const uint8_t *(void *Mem, ArrayRef&lt; uint8_t &gt; Hash)&gt; Constructor)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Insert and return the stored content. <a href="#aa9dbc0a952dfbed82b71fd482c4fcdd7">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">void</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a5eda088431655fae36128201cafbb19b">destroyImpl</a> (function_ref&lt; void(void *ValueMem)&gt; Destructor)</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/threadsafetrierawhashmapbase/pointerbase">PointerBase</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a9b46b32a7ad8e0bbd46ac236c458972e">getRoot</a> () const</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#aae212c2ee246515be53128a7b312bcb4">getStartBit</a> (PointerBase P) const</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a50305af280d36d1dd60dad8e19c4856e">getNumBits</a> (PointerBase P) const</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a5356949cb58c7ea85a34e88d6449de50">getNumSlotUsed</a> (PointerBase P) const</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">std::string</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#acedcd0c6ec24c3ce338800619f5d8262">getTriePrefixAsString</a> (PointerBase P) const</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a40165689c35e859e537d4c04481bd356">getNumTries</a> () const</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/threadsafetrierawhashmapbase/pointerbase">PointerBase</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a00da23e2d60556d07dfb7b85484b1ffb">getNextTrie</a> (PointerBase P) const</td>
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

## Private Member Functions Index

<table class="doxyMembersIndex">

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/threadsafetrierawhashmapbase/impltype">ImplType</a> &amp;</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#abc5645ab19a5c0519962296675b3f162">getOrCreateImpl</a> ()</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/threadsafetrierawhashmapbase/impltype">ImplType</a> *</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a4ae3c4ab38c73cfbd5ad831aada3dc7c">getImpl</a> () const</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> unsigned short</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a9852ae3ab4f202225cd3fe0983466298">ContentAllocSize</a></td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> unsigned short</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ab8e2a70084b997bfc34181535e9640f9">ContentAllocAlign</a></td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> unsigned short</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#abaf24df61cd954aad6d626f7fa0f5846">ContentOffset</a></td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">unsigned short</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a4c694abc13045c15c8bbf0921667f5df">NumRootBits</a></td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">unsigned short</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#abc756a0ab7d4eeb02d488daf87527f01">NumSubtrieBits</a></td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">std::atomic&lt; <a href="/web-llvm/docs/api/classes/threadsafetrierawhashmapbase/impltype">ImplType</a> * &gt;</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#add201817b7e28b9fdec8ba18fa6889b5">ImplPtr</a></td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">static void *</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a20cad65fc859c83271d06000ad02da44">operator new</a> (size_t Size)</td>
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

## Public Static Attributes Index

<table class="doxyMembersIndex">

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">static constexpr size_t</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ad9a3da3661129b546e7667e9655c62a5">TrieContentBaseSize</a> = 4</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#adc630f62e7131f3dfb65e014931f3876">DefaultNumRootBits</a> = 6</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a68f9fa680bc5be723927f82917a1fb9e">DefaultNumSubtrieBits</a> = 4</td>
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

## Protected Static Attributes Index

<table class="doxyMembersIndex">

<tr class="doxyMemberIndexTemplate">
<td class="doxyMemberIndexTemplate" colspan="2"><div>template &lt;class T&gt;</div></td>
</tr>
<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemTypeTemplate" align="left" valign="top">static constexpr size_t</td>
<td class="doxyMemberIndexItemNameTemplate" align="left" valign="top"><a href="#a5f41768b20810e783418ff5ae0b0f51a">DefaultContentAllocSize</a> = sizeof(AllocValueType&lt;T&gt;)</td>
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
<td class="doxyMemberIndexTemplate" colspan="2"><div>template &lt;class T&gt;</div></td>
</tr>
<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemTypeTemplate" align="left" valign="top">static constexpr size_t</td>
<td class="doxyMemberIndexItemNameTemplate" align="left" valign="top"><a href="#a634aba0be92e82ec8a94d804c5908ad2">DefaultContentAllocAlign</a> = alignof(AllocValueType&lt;T&gt;)</td>
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
<td class="doxyMemberIndexTemplate" colspan="2"><div>template &lt;class T&gt;</div></td>
</tr>
<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemTypeTemplate" align="left" valign="top">static constexpr size_t</td>
<td class="doxyMemberIndexItemNameTemplate" align="left" valign="top"><a href="#a63a45375ca4651489077dbc94d008311">DefaultContentOffset</a> = ...</td>
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

<p>TrieRawHashMap - is a lock-free thread-safe trie that is can be used to store/index data based on a hash value.</p>


<p>It can be customized to work with any hash algorithm or store any data.</p>


<p>Data structure: Data node stored in the Trie contains both hash and data: struct { HashT Hash; DataT Data; };</p>


<p>Data is stored/indexed via a prefix tree, where each node in the tree can be either the root, a sub-trie or a data node. Assuming a 4-bit hash and two data objects {0001, A} and {0100, B}, it can be stored in a trie (assuming Root has 2 bits, SubTrie has 1 bit): +-----—+ |Root[00]| -&gt; {0001, A} | [01]| -&gt; {0100, B} | [10]| (empty) | [11]| (empty) +-----—+</p>


<p>Inserting a new object {0010, C} will result in: +-----—+ +-------—+ |Root[00]| -&gt; |SubTrie[0]| -&gt; {0001, A} | | | [1]| -&gt; {0010, C} | | +-------—+ | [01]| -&gt; {0100, B} | [10]| (empty) | [11]| (empty) +-----—+ Note object A is sunk down to a sub-trie during the insertion. All the nodes are inserted through compare-exchange to ensure thread-safe and lock-free.</p>


<p>To find an object in the trie, walk the tree with prefix of the hash until the data node is found. Then the hash is compared with the hash stored in the data node to see if the is the same object.</p>


<p>Hash collision is not allowed so it is recommended to use trie with a "strong" hashing algorithm. A well-distributed hash can also result in better performance and memory usage.</p>


<p>It currently does not support iteration and deletion. Base class for a lock-free thread-safe hash-mapped trie.</p>


<p>Definition at line 66 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/adt/trierawhashmap-h">TrieRawHashMap.h</a>.</p>


<div class="doxySectionDef">

## Friends

### TrieRawHashMapTestHelper {#a60c16bd183947477a36ab8c485638df3}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">friend class TrieRawHashMapTestHelper</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">


<p>Definition at line 166 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/adt/trierawhashmap-h">TrieRawHashMap.h</a>.</p>


<p>Reference <a href="#a60c16bd183947477a36ab8c485638df3">TrieRawHashMapTestHelper</a>.</p>


<p>Referenced by <a href="#a60c16bd183947477a36ab8c485638df3">TrieRawHashMapTestHelper</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Protected Constructors

### ThreadSafeTrieRawHashMapBase() {#a6e8722a5417fddf6486c3236e835173a}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">llvm::ThreadSafeTrieRawHashMapBase::ThreadSafeTrieRawHashMapBase ()</td>
</tr>
</table>
</td>
<td class="doxyMemberLabelsRight">
<span class="doxyMemberLabels">
<span class="doxyMemberLabel protected">protected</span>
<span class="doxyMemberLabel delete">delete</span>
</span>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 129 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/adt/trierawhashmap-h">TrieRawHashMap.h</a>.</p>


<p>References <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/x86/x86partialreduction-cpp/#a87b8bfbbe9d8f7146d7f20a5fb42efd0">RHS</a> and <a href="#a6e8722a5417fddf6486c3236e835173a">ThreadSafeTrieRawHashMapBase</a>.</p>


<p>Referenced by <a href="#a52152a25da14c6579308fa9de4045935">operator=</a>, <a href="#ab47b2bca06a2ac9847d8835081b29b3b">operator=</a>, <a href="/web-llvm/docs/api/classes/llvm/threadsafetrierawhashmap/#aa8d047a4708e34aa727230ae60404c08">llvm::ThreadSafeTrieRawHashMap&lt; T, NumHashBytes &gt;::ThreadSafeTrieRawHashMap</a>, <a href="#a6e8722a5417fddf6486c3236e835173a">ThreadSafeTrieRawHashMapBase</a>, <a href="#af50f504b9f39e93ea34cb323db970930">ThreadSafeTrieRawHashMapBase</a>, <a href="#a900dd95fc13a72dbc38c3e95694461f8">ThreadSafeTrieRawHashMapBase</a> and <a href="/web-llvm/docs/api/classes/threadsafetrierawhashmapbase/impltype/#a831302f460304e1a0f0256fd8b18dea1">llvm::ThreadSafeTrieRawHashMapBase::ImplType::TrailingObjects</a>.</p>

</div>
</div>

### ThreadSafeTrieRawHashMapBase() {#a680f79939c5bb8275ff275c335b5fe5a}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">ThreadSafeTrieRawHashMapBase::ThreadSafeTrieRawHashMapBase (size_t ContentAllocSize, size_t ContentAllocAlign, size_t ContentOffset, std::optional&lt; size_t &gt; NumRootBits=std::nullopt, std::optional&lt; size_t &gt; NumSubtrieBits=std::nullopt)</td>
</tr>
</table>
</td>
<td class="doxyMemberLabelsRight">
<span class="doxyMemberLabels">
<span class="doxyMemberLabel protected">protected</span>
</span>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Declaration at line 131 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/adt/trierawhashmap-h">TrieRawHashMap.h</a>, definition at line 331 of file <a href="/web-llvm/docs/api/files/lib/lib/support/trierawhashmap-cpp">TrieRawHashMap.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/silowercontrolflow-cpp/#a4868c5d81c5ccc98c47aeab6244346a0">assert</a>, <a href="#adc630f62e7131f3dfb65e014931f3876">DefaultNumRootBits</a> and <a href="#a68f9fa680bc5be723927f82917a1fb9e">DefaultNumSubtrieBits</a>.</p>

</div>
</div>

### ThreadSafeTrieRawHashMapBase() {#a900dd95fc13a72dbc38c3e95694461f8}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">ThreadSafeTrieRawHashMapBase::ThreadSafeTrieRawHashMapBase (<a href="/web-llvm/docs/api/classes/llvm/threadsafetrierawhashmapbase">ThreadSafeTrieRawHashMapBase</a> &amp;&amp; RHS)</td>
</tr>
</table>
</td>
<td class="doxyMemberLabelsRight">
<span class="doxyMemberLabels">
<span class="doxyMemberLabel protected">protected</span>
</span>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Declaration at line 143 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/adt/trierawhashmap-h">TrieRawHashMap.h</a>, definition at line 348 of file <a href="/web-llvm/docs/api/files/lib/lib/support/trierawhashmap-cpp">TrieRawHashMap.cpp</a>.</p>


<p>Reference <a href="#a6e8722a5417fddf6486c3236e835173a">ThreadSafeTrieRawHashMapBase</a>.</p>

</div>
</div>

### ThreadSafeTrieRawHashMapBase() {#af50f504b9f39e93ea34cb323db970930}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">llvm::ThreadSafeTrieRawHashMapBase::ThreadSafeTrieRawHashMapBase (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/threadsafetrierawhashmapbase">ThreadSafeTrieRawHashMapBase</a> &amp;)</td>
</tr>
</table>
</td>
<td class="doxyMemberLabelsRight">
<span class="doxyMemberLabels">
<span class="doxyMemberLabel protected">protected</span>
<span class="doxyMemberLabel delete">delete</span>
</span>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 150 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/adt/trierawhashmap-h">TrieRawHashMap.h</a>.</p>


<p>Reference <a href="#a6e8722a5417fddf6486c3236e835173a">ThreadSafeTrieRawHashMapBase</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Protected Destructor

### \~ThreadSafeTrieRawHashMapBase() {#a538ad0b852455c782b91c9e3c994de70}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">ThreadSafeTrieRawHashMapBase::~ThreadSafeTrieRawHashMapBase ()</td>
</tr>
</table>
</td>
<td class="doxyMemberLabelsRight">
<span class="doxyMemberLabels">
<span class="doxyMemberLabel protected">protected</span>
</span>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Destructor, which asserts if there's anything to do.</p>


<p>Subclasses should call <em><a href="#a5eda088431655fae36128201cafbb19b">destroyImpl()</a></em>.</p>


<dl class="doxySectionUser">
<dt>Precondition</dt>
<dd><p><em><a href="#a5eda088431655fae36128201cafbb19b">destroyImpl()</a></em> was already called.</p></dd>
</dl>


<p>Declaration at line 140 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/adt/trierawhashmap-h">TrieRawHashMap.h</a>, definition at line 358 of file <a href="/web-llvm/docs/api/files/lib/lib/support/trierawhashmap-cpp">TrieRawHashMap.cpp</a>.</p>


<p>Reference <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/silowercontrolflow-cpp/#a4868c5d81c5ccc98c47aeab6244346a0">assert</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Public Operators

### operator delete() {#abc391c1e6c335e191a5e653ab156d0e3}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
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



<p>Definition at line 91 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/adt/trierawhashmap-h">TrieRawHashMap.h</a>.</p>


<p>Reference <a href="/web-llvm/docs/api/files/lib/lib/analysis/targetlibraryinfo-cpp/#aca185e6d0e9f423dbb24440206454872a11dbf501abf829b3ab7049c2d3a8a053">Ptr</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Protected Operators

### operator=() {#ab47b2bca06a2ac9847d8835081b29b3b}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">ThreadSafeTrieRawHashMapBase &amp; llvm::ThreadSafeTrieRawHashMapBase::operator= (<a href="/web-llvm/docs/api/classes/llvm/threadsafetrierawhashmapbase">ThreadSafeTrieRawHashMapBase</a> &amp;&amp; RHS)</td>
</tr>
</table>
</td>
<td class="doxyMemberLabelsRight">
<span class="doxyMemberLabels">
<span class="doxyMemberLabel protected">protected</span>
<span class="doxyMemberLabel delete">delete</span>
</span>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 147 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/adt/trierawhashmap-h">TrieRawHashMap.h</a>.</p>


<p>References <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/x86/x86partialreduction-cpp/#a87b8bfbbe9d8f7146d7f20a5fb42efd0">RHS</a> and <a href="#a6e8722a5417fddf6486c3236e835173a">ThreadSafeTrieRawHashMapBase</a>.</p>

</div>
</div>

### operator=() {#a52152a25da14c6579308fa9de4045935}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">ThreadSafeTrieRawHashMapBase &amp; llvm::ThreadSafeTrieRawHashMapBase::operator= (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/threadsafetrierawhashmapbase">ThreadSafeTrieRawHashMapBase</a> &amp;)</td>
</tr>
</table>
</td>
<td class="doxyMemberLabelsRight">
<span class="doxyMemberLabels">
<span class="doxyMemberLabel protected">protected</span>
<span class="doxyMemberLabel delete">delete</span>
</span>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 152 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/adt/trierawhashmap-h">TrieRawHashMap.h</a>.</p>


<p>References <a href="/web-llvm/docs/api/files/lib/lib/option/option-cpp/#a04665169063c8ca1f2ea96c27fc7c2b2">P</a> and <a href="#a6e8722a5417fddf6486c3236e835173a">ThreadSafeTrieRawHashMapBase</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Public Member Functions

### dump() {#a7a914a734fa37fdb1bb52291ecedc4b4}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
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



<p>Definition at line 93 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/adt/trierawhashmap-h">TrieRawHashMap.h</a>.</p>


<p>Reference <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/support/compiler-h/#aa863693eef567397d9c292da5bf22d34">LLVM_DUMP_METHOD</a>.</p>

</div>
</div>

### print() {#aafdc5312a9cc637e22a61875e1a263f0}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
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



<p>Definition at line 94 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/adt/trierawhashmap-h">TrieRawHashMap.h</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Protected Member Functions

### destroyImpl() {#a5eda088431655fae36128201cafbb19b}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void ThreadSafeTrieRawHashMapBase::destroyImpl (<a href="/web-llvm/docs/api/classes/llvm/function-ref">function_ref</a>&lt; void(void *ValueMem)&gt; Destructor)</td>
</tr>
</table>
</td>
<td class="doxyMemberLabelsRight">
<span class="doxyMemberLabels">
<span class="doxyMemberLabel protected">protected</span>
</span>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Declaration at line 141 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/adt/trierawhashmap-h">TrieRawHashMap.h</a>, definition at line 362 of file <a href="/web-llvm/docs/api/files/lib/lib/support/trierawhashmap-cpp">TrieRawHashMap.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/namespaces/llvm/#a5f6182886dc2f96c204299e92c1565d5">llvm::dyn_cast_or_null</a>, <a href="/web-llvm/docs/api/structs/anonymous-trierawhashmap-cpp-/triecontent/#a16f59b5cb0c1bf73505868b855d99c49">anonymous{TrieRawHashMap.cpp}::TrieContent::getValuePointer</a>, <a href="/web-llvm/docs/api/files/lib/lib/support/md5-cpp/#ac0eafdc9ee161b71e7af98af736952fd">I</a> and <a href="/web-llvm/docs/api/namespaces/llvm/#ab13c360340346d082b959b8cd79f2c1a">llvm::Next</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/classes/llvm/threadsafetrierawhashmap/#adb9395d3295ddf120895498b02e2f673">llvm::ThreadSafeTrieRawHashMap&lt; T, NumHashBytes &gt;::~ThreadSafeTrieRawHashMap</a>.</p>

</div>
</div>

### find() {#a7184c737372d1fa8d3783e5000463f2b}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">ThreadSafeTrieRawHashMapBase::PointerBase ThreadSafeTrieRawHashMapBase::find (<a href="/web-llvm/docs/api/classes/llvm/arrayref">ArrayRef</a>&lt; uint8_t &gt; Hash)</td>
</tr>
</table>
</td>
<td class="doxyMemberLabelsRight">
<span class="doxyMemberLabels">
<span class="doxyMemberLabel protected">protected</span>
</span>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Find the stored content with hash.</p>

<p>Declaration at line 121 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/adt/trierawhashmap-h">TrieRawHashMap.h</a>, definition at line 231 of file <a href="/web-llvm/docs/api/files/lib/lib/support/trierawhashmap-cpp">TrieRawHashMap.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/silowercontrolflow-cpp/#a4868c5d81c5ccc98c47aeab6244346a0">assert</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#ac4fc845f5ed92de63cd4474f128f5fc5">llvm::cast</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a22eeee01734061ac1b31ccd994c49eef">llvm::dyn_cast</a>, <a href="/web-llvm/docs/api/classes/llvm/arrayref/#ac835b8735b1b2faec0efdca236e37d94">llvm::ArrayRef&lt; T &gt;::empty</a>, <a href="/web-llvm/docs/api/structs/llvm/triehashindexgenerator/#aa71aa120340de3173855fc9c19869e81">llvm::TrieHashIndexGenerator::end</a>, <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/support/errorhandling-h/#ace243f5c25697a1107cce46626b3dc94">llvm_unreachable</a>, <a href="/web-llvm/docs/api/structs/llvm/triehashindexgenerator/#addddf0cf44f031951d26ef1f6498d7de">llvm::TrieHashIndexGenerator::next</a> and <a href="/web-llvm/docs/api/structs/llvm/triehashindexgenerator/#a1ccc1711881e6ab8fd991061d0904dd8">llvm::TrieHashIndexGenerator::StartBit</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/classes/llvm/threadsafetrierawhashmap/#a4d0d05a3c39242b69eec429ba4945c64">llvm::ThreadSafeTrieRawHashMap&lt; T, NumHashBytes &gt;::find</a> and <a href="/web-llvm/docs/api/classes/llvm/threadsafetrierawhashmap/#a702eff07aa75ca8d8cfaba044f7b3f29">llvm::ThreadSafeTrieRawHashMap&lt; T, NumHashBytes &gt;::find</a>.</p>

</div>
</div>

### getNextTrie() {#a00da23e2d60556d07dfb7b85484b1ffb}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">ThreadSafeTrieRawHashMapBase::PointerBase ThreadSafeTrieRawHashMapBase::getNextTrie (<a href="/web-llvm/docs/api/classes/llvm/threadsafetrierawhashmapbase/pointerbase">PointerBase</a> P)</td>
</tr>
</table>
</td>
<td class="doxyMemberLabelsRight">
<span class="doxyMemberLabels">
<span class="doxyMemberLabel protected">protected</span>
</span>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Declaration at line 163 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/adt/trierawhashmap-h">TrieRawHashMap.h</a>, definition at line 504 of file <a href="/web-llvm/docs/api/files/lib/lib/support/trierawhashmap-cpp">TrieRawHashMap.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/silowercontrolflow-cpp/#a4868c5d81c5ccc98c47aeab6244346a0">assert</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a22eeee01734061ac1b31ccd994c49eef">llvm::dyn_cast</a> and <a href="/web-llvm/docs/api/files/lib/lib/option/option-cpp/#a04665169063c8ca1f2ea96c27fc7c2b2">P</a>.</p>

</div>
</div>

### getNumBits() {#a50305af280d36d1dd60dad8e19c4856e}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">unsigned ThreadSafeTrieRawHashMapBase::getNumBits (<a href="/web-llvm/docs/api/classes/llvm/threadsafetrierawhashmapbase/pointerbase">PointerBase</a> P)</td>
</tr>
</table>
</td>
<td class="doxyMemberLabelsRight">
<span class="doxyMemberLabels">
<span class="doxyMemberLabel protected">protected</span>
</span>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Declaration at line 158 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/adt/trierawhashmap-h">TrieRawHashMap.h</a>, definition at line 407 of file <a href="/web-llvm/docs/api/files/lib/lib/support/trierawhashmap-cpp">TrieRawHashMap.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/silowercontrolflow-cpp/#a4868c5d81c5ccc98c47aeab6244346a0">assert</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a22eeee01734061ac1b31ccd994c49eef">llvm::dyn_cast</a> and <a href="/web-llvm/docs/api/files/lib/lib/option/option-cpp/#a04665169063c8ca1f2ea96c27fc7c2b2">P</a>.</p>

</div>
</div>

### getNumSlotUsed() {#a5356949cb58c7ea85a34e88d6449de50}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">unsigned ThreadSafeTrieRawHashMapBase::getNumSlotUsed (<a href="/web-llvm/docs/api/classes/llvm/threadsafetrierawhashmapbase/pointerbase">PointerBase</a> P)</td>
</tr>
</table>
</td>
<td class="doxyMemberLabelsRight">
<span class="doxyMemberLabels">
<span class="doxyMemberLabel protected">protected</span>
</span>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Declaration at line 159 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/adt/trierawhashmap-h">TrieRawHashMap.h</a>, definition at line 417 of file <a href="/web-llvm/docs/api/files/lib/lib/support/trierawhashmap-cpp">TrieRawHashMap.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/silowercontrolflow-cpp/#a4868c5d81c5ccc98c47aeab6244346a0">assert</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a22eeee01734061ac1b31ccd994c49eef">llvm::dyn_cast</a>, <a href="/web-llvm/docs/api/files/lib/lib/support/md5-cpp/#ac0eafdc9ee161b71e7af98af736952fd">I</a> and <a href="/web-llvm/docs/api/files/lib/lib/option/option-cpp/#a04665169063c8ca1f2ea96c27fc7c2b2">P</a>.</p>

</div>
</div>

### getNumTries() {#a40165689c35e859e537d4c04481bd356}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">unsigned ThreadSafeTrieRawHashMapBase::getNumTries ()</td>
</tr>
</table>
</td>
<td class="doxyMemberLabelsRight">
<span class="doxyMemberLabels">
<span class="doxyMemberLabel protected">protected</span>
</span>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Declaration at line 161 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/adt/trierawhashmap-h">TrieRawHashMap.h</a>, definition at line 493 of file <a href="/web-llvm/docs/api/files/lib/lib/support/trierawhashmap-cpp">TrieRawHashMap.cpp</a>.</p>

</div>
</div>

### getRoot() {#a9b46b32a7ad8e0bbd46ac236c458972e}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">ThreadSafeTrieRawHashMapBase::PointerBase ThreadSafeTrieRawHashMapBase::getRoot ()</td>
</tr>
</table>
</td>
<td class="doxyMemberLabelsRight">
<span class="doxyMemberLabels">
<span class="doxyMemberLabel protected">protected</span>
</span>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Declaration at line 156 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/adt/trierawhashmap-h">TrieRawHashMap.h</a>, definition at line 390 of file <a href="/web-llvm/docs/api/files/lib/lib/support/trierawhashmap-cpp">TrieRawHashMap.cpp</a>.</p>

</div>
</div>

### getStartBit() {#aae212c2ee246515be53128a7b312bcb4}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">unsigned ThreadSafeTrieRawHashMapBase::getStartBit (<a href="/web-llvm/docs/api/classes/llvm/threadsafetrierawhashmapbase/pointerbase">PointerBase</a> P)</td>
</tr>
</table>
</td>
<td class="doxyMemberLabelsRight">
<span class="doxyMemberLabels">
<span class="doxyMemberLabel protected">protected</span>
</span>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Declaration at line 157 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/adt/trierawhashmap-h">TrieRawHashMap.h</a>, definition at line 397 of file <a href="/web-llvm/docs/api/files/lib/lib/support/trierawhashmap-cpp">TrieRawHashMap.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/silowercontrolflow-cpp/#a4868c5d81c5ccc98c47aeab6244346a0">assert</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a22eeee01734061ac1b31ccd994c49eef">llvm::dyn_cast</a> and <a href="/web-llvm/docs/api/files/lib/lib/option/option-cpp/#a04665169063c8ca1f2ea96c27fc7c2b2">P</a>.</p>

</div>
</div>

### getTriePrefixAsString() {#acedcd0c6ec24c3ce338800619f5d8262}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">std::string ThreadSafeTrieRawHashMapBase::getTriePrefixAsString (<a href="/web-llvm/docs/api/classes/llvm/threadsafetrierawhashmapbase/pointerbase">PointerBase</a> P)</td>
</tr>
</table>
</td>
<td class="doxyMemberLabelsRight">
<span class="doxyMemberLabels">
<span class="doxyMemberLabel protected">protected</span>
</span>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Declaration at line 160 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/adt/trierawhashmap-h">TrieRawHashMap.h</a>, definition at line 432 of file <a href="/web-llvm/docs/api/files/lib/lib/support/trierawhashmap-cpp">TrieRawHashMap.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/silowercontrolflow-cpp/#a4868c5d81c5ccc98c47aeab6244346a0">assert</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a22eeee01734061ac1b31ccd994c49eef">llvm::dyn_cast</a>, <a href="/web-llvm/docs/api/files/lib/lib/support/md5-cpp/#ac0eafdc9ee161b71e7af98af736952fd">I</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#ab13c360340346d082b959b8cd79f2c1a">llvm::Next</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a05f5b9a11bdcc5feba62899f95dcf878a3134224cba2545bc57954d3b072aebb4">llvm::Offset</a>, <a href="/web-llvm/docs/api/files/lib/lib/option/option-cpp/#a04665169063c8ca1f2ea96c27fc7c2b2">P</a>, <a href="/web-llvm/docs/api/classes/llvm/stringref/#aa28286a33491b5d9a936fb6ae853baee">llvm::StringRef::take_front</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#abec19670f96ed423c2e4d4f10a4c6975">llvm::toHex</a> and <a href="/web-llvm/docs/api/namespaces/llvm/#aeeb5973ff74c4c4d279e275b34b7ef54">llvm::toStringRef</a>.</p>

</div>
</div>

### insert() {#aa9dbc0a952dfbed82b71fd482c4fcdd7}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">ThreadSafeTrieRawHashMapBase::PointerBase ThreadSafeTrieRawHashMapBase::insert (<a href="/web-llvm/docs/api/classes/llvm/threadsafetrierawhashmapbase/pointerbase">PointerBase</a> Hint, <a href="/web-llvm/docs/api/classes/llvm/arrayref">ArrayRef</a>&lt; uint8_t &gt; Hash, <a href="/web-llvm/docs/api/classes/llvm/function-ref">function_ref</a>&lt; <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> uint8_t *(void *Mem, <a href="/web-llvm/docs/api/classes/llvm/arrayref">ArrayRef</a>&lt; uint8_t &gt; Hash)&gt; Constructor)</td>
</tr>
</table>
</td>
<td class="doxyMemberLabelsRight">
<span class="doxyMemberLabels">
<span class="doxyMemberLabel protected">protected</span>
</span>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Insert and return the stored content.</p>

<p>Declaration at line 125 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/adt/trierawhashmap-h">TrieRawHashMap.h</a>, definition at line 259 of file <a href="/web-llvm/docs/api/files/lib/lib/support/trierawhashmap-cpp">TrieRawHashMap.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/silowercontrolflow-cpp/#a4868c5d81c5ccc98c47aeab6244346a0">assert</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#ac4fc845f5ed92de63cd4474f128f5fc5">llvm::cast</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a22eeee01734061ac1b31ccd994c49eef">llvm::dyn_cast</a>, <a href="/web-llvm/docs/api/classes/llvm/arrayref/#ac835b8735b1b2faec0efdca236e37d94">llvm::ArrayRef&lt; T &gt;::empty</a>, <a href="/web-llvm/docs/api/structs/llvm/triehashindexgenerator/#aa71aa120340de3173855fc9c19869e81">llvm::TrieHashIndexGenerator::end</a>, <a href="/web-llvm/docs/api/structs/llvm/triehashindexgenerator/#aa243b9e79e08ba0917b9033159b957aa">llvm::TrieHashIndexGenerator::getCollidingBits</a>, <a href="/web-llvm/docs/api/structs/llvm/triehashindexgenerator/#a5bd33f30c29b0e7770a7236748e39f51">llvm::TrieHashIndexGenerator::getNumBits</a>, <a href="/web-llvm/docs/api/structs/llvm/triehashindexgenerator/#afbc9c1828c3ba51438a1fd2d14a52a2b">llvm::TrieHashIndexGenerator::hint</a>, <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/support/errorhandling-h/#ace243f5c25697a1107cce46626b3dc94">llvm_unreachable</a>, <a href="/web-llvm/docs/api/structs/llvm/triehashindexgenerator/#addddf0cf44f031951d26ef1f6498d7de">llvm::TrieHashIndexGenerator::next</a> and <a href="/web-llvm/docs/api/classes/llvm/arrayref/#a85ffb6531d4cda988ea81f18d4e56fb7">llvm::ArrayRef&lt; T &gt;::size</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/classes/llvm/threadsafetrierawhashmap/#a6cd2c4f25dfbd382aca540c2ffeed8b9">llvm::ThreadSafeTrieRawHashMap&lt; T, NumHashBytes &gt;::insertLazy</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Private Member Functions

### getImpl() {#a4ae3c4ab38c73cfbd5ad831aada3dc7c}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">ImplType * llvm::ThreadSafeTrieRawHashMapBase::getImpl ()</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 177 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/adt/trierawhashmap-h">TrieRawHashMap.h</a>.</p>

</div>
</div>

### getOrCreateImpl() {#abc5645ab19a5c0519962296675b3f162}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">ThreadSafeTrieRawHashMapBase::ImplType &amp; ThreadSafeTrieRawHashMapBase::getOrCreateImpl ()</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Declaration at line 176 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/adt/trierawhashmap-h">TrieRawHashMap.h</a>, definition at line 212 of file <a href="/web-llvm/docs/api/files/lib/lib/support/trierawhashmap-cpp">TrieRawHashMap.cpp</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Private Member Attributes

### ContentAllocAlign {#ab8e2a70084b997bfc34181535e9640f9}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">const unsigned short llvm::ThreadSafeTrieRawHashMapBase::ContentAllocAlign</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 168 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/adt/trierawhashmap-h">TrieRawHashMap.h</a>.</p>

</div>
</div>

### ContentAllocSize {#a9852ae3ab4f202225cd3fe0983466298}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">const unsigned short llvm::ThreadSafeTrieRawHashMapBase::ContentAllocSize</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 167 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/adt/trierawhashmap-h">TrieRawHashMap.h</a>.</p>

</div>
</div>

### ContentOffset {#abaf24df61cd954aad6d626f7fa0f5846}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">const unsigned short llvm::ThreadSafeTrieRawHashMapBase::ContentOffset</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 169 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/adt/trierawhashmap-h">TrieRawHashMap.h</a>.</p>

</div>
</div>

### ImplPtr {#add201817b7e28b9fdec8ba18fa6889b5}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">std::atomic&lt;ImplType *&gt; llvm::ThreadSafeTrieRawHashMapBase::ImplPtr</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 175 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/adt/trierawhashmap-h">TrieRawHashMap.h</a>.</p>

</div>
</div>

### NumRootBits {#a4c694abc13045c15c8bbf0921667f5df}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">unsigned short llvm::ThreadSafeTrieRawHashMapBase::NumRootBits</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 170 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/adt/trierawhashmap-h">TrieRawHashMap.h</a>.</p>

</div>
</div>

### NumSubtrieBits {#abc756a0ab7d4eeb02d488daf87527f01}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">unsigned short llvm::ThreadSafeTrieRawHashMapBase::NumSubtrieBits</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 171 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/adt/trierawhashmap-h">TrieRawHashMap.h</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Public Operators

### operator new() {#a20cad65fc859c83271d06000ad02da44}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void * llvm::ThreadSafeTrieRawHashMapBase::operator new (size_t Size)</td>
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



<p>Definition at line 90 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/adt/trierawhashmap-h">TrieRawHashMap.h</a>.</p>


<p>Reference <a href="/web-llvm/docs/api/files/lib/lib/analysis/inlineorder-cpp/#a7ee6f0cb51c3b9056199e9a0001fe8c3a6f6cb72d544962fa333e2e34ce64f719">Size</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Public Static Attributes

### DefaultNumRootBits {#adc630f62e7131f3dfb65e014931f3876}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">size_t llvm::ThreadSafeTrieRawHashMapBase::DefaultNumRootBits = 6</td>
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



<p>Definition at line 69 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/adt/trierawhashmap-h">TrieRawHashMap.h</a>.</p>


<p>Referenced by <a href="#a680f79939c5bb8275ff275c335b5fe5a">ThreadSafeTrieRawHashMapBase</a>.</p>

</div>
</div>

### DefaultNumSubtrieBits {#a68f9fa680bc5be723927f82917a1fb9e}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">size_t llvm::ThreadSafeTrieRawHashMapBase::DefaultNumSubtrieBits = 4</td>
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



<p>Definition at line 70 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/adt/trierawhashmap-h">TrieRawHashMap.h</a>.</p>


<p>Referenced by <a href="#a680f79939c5bb8275ff275c335b5fe5a">ThreadSafeTrieRawHashMapBase</a>.</p>

</div>
</div>

### TrieContentBaseSize {#ad9a3da3661129b546e7667e9655c62a5}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">size_t llvm::ThreadSafeTrieRawHashMapBase::TrieContentBaseSize = 4</td>
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



<p>Definition at line 68 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/adt/trierawhashmap-h">TrieRawHashMap.h</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Protected Static Attributes

### DefaultContentAllocAlign {#a634aba0be92e82ec8a94d804c5908ad2}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<div class="doxyMemberTemplate">template &lt;class T&gt;</div>
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">size_t llvm::ThreadSafeTrieRawHashMapBase::DefaultContentAllocAlign = alignof(AllocValueType&lt;T&gt;)</td>
</tr>
</table>
</td>
<td class="doxyMemberLabelsRight">
<span class="doxyMemberLabels">
<span class="doxyMemberLabel constexpr">constexpr</span>
<span class="doxyMemberLabel protected">protected</span>
<span class="doxyMemberLabel static">static</span>
</span>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 83 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/adt/trierawhashmap-h">TrieRawHashMap.h</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/classes/llvm/threadsafetrierawhashmap/#aa8d047a4708e34aa727230ae60404c08">llvm::ThreadSafeTrieRawHashMap&lt; T, NumHashBytes &gt;::ThreadSafeTrieRawHashMap</a>.</p>

</div>
</div>

### DefaultContentAllocSize {#a5f41768b20810e783418ff5ae0b0f51a}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<div class="doxyMemberTemplate">template &lt;class T&gt;</div>
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">size_t llvm::ThreadSafeTrieRawHashMapBase::DefaultContentAllocSize = sizeof(AllocValueType&lt;T&gt;)</td>
</tr>
</table>
</td>
<td class="doxyMemberLabelsRight">
<span class="doxyMemberLabels">
<span class="doxyMemberLabel constexpr">constexpr</span>
<span class="doxyMemberLabel protected">protected</span>
<span class="doxyMemberLabel static">static</span>
</span>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 80 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/adt/trierawhashmap-h">TrieRawHashMap.h</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/classes/llvm/threadsafetrierawhashmap/#aa8d047a4708e34aa727230ae60404c08">llvm::ThreadSafeTrieRawHashMap&lt; T, NumHashBytes &gt;::ThreadSafeTrieRawHashMap</a>.</p>

</div>
</div>

### DefaultContentOffset {#a63a45375ca4651489077dbc94d008311}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<div class="doxyMemberTemplate">template &lt;class T&gt;</div>
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">size_t llvm::ThreadSafeTrieRawHashMapBase::DefaultContentOffset</td>
</tr>
</table>
</td>
<td class="doxyMemberLabelsRight">
<span class="doxyMemberLabels">
<span class="doxyMemberLabel constexpr">constexpr</span>
<span class="doxyMemberLabel protected">protected</span>
<span class="doxyMemberLabel static">static</span>
</span>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<dl class="doxySectionUser">
<dt>Initialiser</dt>
<dd>
<div class="doxyVerbatim">=
      <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/support/amdhsakerneldescriptor-h/#a276e8a32e0bbf024aadd9420b8f2d3b3">offsetof</a>(AllocValueType&lt;T&gt;, Content)
</div>
</dd>
</dl>

<p>Definition at line 86 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/adt/trierawhashmap-h">TrieRawHashMap.h</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/classes/llvm/threadsafetrierawhashmap/#aa8d047a4708e34aa727230ae60404c08">llvm::ThreadSafeTrieRawHashMap&lt; T, NumHashBytes &gt;::ThreadSafeTrieRawHashMap</a>.</p>

</div>
</div>

</div>

<hr/>

The documentation for this class was generated from the following files:

<ul>
<li><a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/adt/trierawhashmap-h">TrieRawHashMap.h</a></li>
<li><a href="/web-llvm/docs/api/files/lib/lib/support/trierawhashmap-cpp">TrieRawHashMap.cpp</a></li>
</ul>

<hr/>

<p class="doxyGeneratedBy">Generated via <a href="https://github.com/xpack/doxygen2docusaurus">doxygen2docusaurus</a> by <a href="https://www.doxygen.nl">Doxygen</a> 1.14.0.</p>

</div>
