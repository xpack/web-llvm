---

# DO NOT EDIT!
# Automatically generated via doxygen2docusaurus by Doxygen.

slug: /api/namespaces/llvm/hashing/detail
custom_edit_url: null
toc_max_heading_level: 4
keywords:
  - doxygen
  - reference
  - namespace

---

<div class="doxyPage">

# The `detail` Namespace Reference



## Definition

<div class="doxyDefinition">
namespace llvm::hashing::detail { ... }
</div>

## Classes Index

<table class="doxyMembersIndex">

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">struct</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="/web-llvm/docs/api/structs/llvm/hashing/detail/hash-state">hash_state</a></td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>The intermediate state used during hashing. <a href="/web-llvm/docs/api/structs/llvm/hashing/detail/hash-state/#details">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">struct</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="/web-llvm/docs/api/structs/llvm/hashing/detail/is-hashable-data">is_hashable_data&lt;T&gt;</a></td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Trait to indicate whether a type's bits can be hashed directly. <a href="/web-llvm/docs/api/structs/llvm/hashing/detail/is-hashable-data/#details">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">struct</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="/web-llvm/docs/api/structs/llvm/hashing/detail/is-hashable-data-c5ff1c17472038b6f5efad36061925b9">is_hashable_data&lt;std::pair&lt; T, U &gt;&gt;</a></td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">struct</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="/web-llvm/docs/api/structs/llvm/hashing/detail/hash-combine-recursive-helper">hash_combine_recursive_helper</a></td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Helper class to manage the recursive combining of hash_combine arguments. <a href="/web-llvm/docs/api/structs/llvm/hashing/detail/hash-combine-recursive-helper/#details">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

</table>

## Functions Index

<table class="doxyMembersIndex">

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">uint64_t</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a6af5e05ffaf0980f306a818bbe587f41">fetch64</a> (const char *p)</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a8b7aec03f89d9512ce1a14a3308ca161">fetch32</a> (const char *p)</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a4ffb910d18d978660569ea44ac87e494">rotate</a> (uint64_t val, size_t shift)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Bitwise right rotate. <a href="#a4ffb910d18d978660569ea44ac87e494">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">uint64_t</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#aaebf1b7abefd58ee53874924675a8884">shift_mix</a> (uint64_t val)</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ad83862adf1fbf2399e28c062421d6a9b">hash_16_bytes</a> (uint64_t low, uint64_t high)</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a04c178b7e1b96b98934763374a4485d9">hash_1to3_bytes</a> (const char *s, size_t len, uint64_t seed)</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a47f5fadf2eb86ee5088924d5760dae3f">hash_4to8_bytes</a> (const char *s, size_t len, uint64_t seed)</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a17851b50e69ca9482ea8fb104ae202b3">hash_9to16_bytes</a> (const char *s, size_t len, uint64_t seed)</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a6fd531b33128989cc9e90c8e08b876d3">hash_17to32_bytes</a> (const char *s, size_t len, uint64_t seed)</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ab41bb88af8fda8fa4eaa0f41ccc98042">hash_33to64_bytes</a> (const char *s, size_t len, uint64_t seed)</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a9f8d3250fbca36e49b9c1304f31bdfb8">hash_short</a> (const char *s, size_t length, uint64_t seed)</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a8a572c218eb50cd07af7265347c113a8">get_execution_seed</a> ()</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>In LLVM_ENABLE_ABI_BREAKING_CHECKS builds, the seed is non-deterministic per process (address of a function in LLVMSupport) to prevent having users depend on the particular hash values. <a href="#a8a572c218eb50cd07af7265347c113a8">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexTemplate">
<td class="doxyMemberIndexTemplate" colspan="2"><div>template &lt;typename T&gt;</div></td>
</tr>
<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemTypeTemplate" align="left" valign="top">auto </td>
<td class="doxyMemberIndexItemNameTemplate" align="left" valign="top"><a href="#a4d42cd18d93c269fe8878db27f2ff8cc">get_hashable_data</a> (const T &amp;value) -&gt; std::enable_if_t&lt; <a href="/web-llvm/docs/api/structs/llvm/hashing/detail/is-hashable-data">is_hashable_data</a>&lt; T &gt;::value, T &gt;</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Helper to get the hashable data representation for a type. <a href="#a4d42cd18d93c269fe8878db27f2ff8cc">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexTemplate">
<td class="doxyMemberIndexTemplate" colspan="2"><div>template &lt;typename T&gt;</div></td>
</tr>
<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemTypeTemplate" align="left" valign="top">auto </td>
<td class="doxyMemberIndexItemNameTemplate" align="left" valign="top"><a href="#a1b139223f5e7f4da69193a531a5f1082">get_hashable_data</a> (const T &amp;value) -&gt; std::enable_if_t&lt;!<a href="/web-llvm/docs/api/structs/llvm/hashing/detail/is-hashable-data">is_hashable_data</a>&lt; T &gt;::value, size_t &gt;</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Helper to get the hashable data representation for a type. <a href="#a1b139223f5e7f4da69193a531a5f1082">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexTemplate">
<td class="doxyMemberIndexTemplate" colspan="2"><div>template &lt;typename T&gt;</div></td>
</tr>
<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemTypeTemplate" align="left" valign="top">bool</td>
<td class="doxyMemberIndexItemNameTemplate" align="left" valign="top"><a href="#a0e6505cf45fca2d42d6d02ba7fcde5b8">store_and_advance</a> (char *&amp;buffer_ptr, char *buffer_end, const T &amp;value, size_t offset=0)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Helper to store data from a value into a buffer and advance the pointer into that buffer. <a href="#a0e6505cf45fca2d42d6d02ba7fcde5b8">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexTemplate">
<td class="doxyMemberIndexTemplate" colspan="2"><div>template &lt;typename InputIteratorT&gt;</div></td>
</tr>
<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemTypeTemplate" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/hash-code">hash_code</a></td>
<td class="doxyMemberIndexItemNameTemplate" align="left" valign="top"><a href="#a4b425f997c3d2172f7b92a4598332b37">hash_combine_range_impl</a> (InputIteratorT first, InputIteratorT last)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Implement the combining of integral values into a <a href="/web-llvm/docs/api/classes/llvm/hash-code">hash_code</a>. <a href="#a4b425f997c3d2172f7b92a4598332b37">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexTemplate">
<td class="doxyMemberIndexTemplate" colspan="2"><div>template &lt;typename ValueT&gt;</div></td>
</tr>
<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemTypeTemplate" align="left" valign="top">auto </td>
<td class="doxyMemberIndexItemNameTemplate" align="left" valign="top"><a href="#a3978afe88908efc4773a9c2a7796e27b">hash_combine_range_impl</a> (ValueT *first, ValueT *last) -&gt; std::enable_if_t&lt; <a href="/web-llvm/docs/api/structs/llvm/hashing/detail/is-hashable-data">is_hashable_data</a>&lt; ValueT &gt;::value, <a href="/web-llvm/docs/api/classes/llvm/hash-code">hash_code</a> &gt;</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Implement the combining of integral values into a <a href="/web-llvm/docs/api/classes/llvm/hash-code">hash_code</a>. <a href="#a3978afe88908efc4773a9c2a7796e27b">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/hash-code">hash_code</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a4fa6656e1c72b2fb9a6ed0659d3e248f">hash_integer_value</a> (uint64_t value)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Helper to hash the value of a single integer. <a href="#a4fa6656e1c72b2fb9a6ed0659d3e248f">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

</table>

## Variables Index

<table class="doxyMembersIndex">

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">static constexpr uint64_t</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#aa14801ceabdb9a21f12353bb2157bd9f">k0</a> = 0xc3a5c85c97cb3127ULL</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Some primes between 2^63 and 2^64 for various uses. <a href="#aa14801ceabdb9a21f12353bb2157bd9f">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">static constexpr uint64_t</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a8024b8ff1557e1fb8d1c607b1420de02">k1</a> = 0xb492b66fbe98f273ULL</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">static constexpr uint64_t</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a56c87fc8a8726f0caf29ef182189d3b3">k2</a> = 0x9ae16a3b2f90404fULL</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">static constexpr uint64_t</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a955d5d8e5c62042ded7184cc9e0516de">k3</a> = 0xc949d7c7509e6557ULL</td>
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


<div class="doxySectionDef">

## Functions

### fetch32() {#a8b7aec03f89d9512ce1a14a3308ca161}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">uint32_t llvm::hashing::detail::fetch32 (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> char * p)</td>
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



<p>Definition at line 144 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/adt/hashing-h">Hashing.h</a>.</p>


<p>References <a href="/web-llvm/docs/api/namespaces/llvm/sys/#ab9f705441a3a825d4b8a93ca4476d4e7">llvm::sys::IsBigEndianHost</a> and <a href="/web-llvm/docs/api/namespaces/llvm/sys/#ad0e418047a3e04c4fd1fb83325b571ae">llvm::sys::swapByteOrder</a>.</p>


<p>Referenced by <a href="#a47f5fadf2eb86ee5088924d5760dae3f">hash_4to8_bytes</a> and <a href="#a4fa6656e1c72b2fb9a6ed0659d3e248f">hash_integer_value</a>.</p>

</div>
</div>

### fetch64() {#a6af5e05ffaf0980f306a818bbe587f41}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">uint64_t llvm::hashing::detail::fetch64 (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> char * p)</td>
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



<p>Definition at line 136 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/adt/hashing-h">Hashing.h</a>.</p>


<p>References <a href="/web-llvm/docs/api/namespaces/llvm/sys/#ab9f705441a3a825d4b8a93ca4476d4e7">llvm::sys::IsBigEndianHost</a> and <a href="/web-llvm/docs/api/namespaces/llvm/sys/#ad0e418047a3e04c4fd1fb83325b571ae">llvm::sys::swapByteOrder</a>.</p>


<p>Referenced by <a href="#a6fd531b33128989cc9e90c8e08b876d3">hash_17to32_bytes</a>, <a href="#ab41bb88af8fda8fa4eaa0f41ccc98042">hash_33to64_bytes</a>, <a href="#a17851b50e69ca9482ea8fb104ae202b3">hash_9to16_bytes</a>, <a href="/web-llvm/docs/api/structs/llvm/hashing/detail/hash-state/#ab7b8ef7c970f0050e15688a0a3241fde">llvm::hashing::detail::hash_state::mix</a> and <a href="/web-llvm/docs/api/structs/llvm/hashing/detail/hash-state/#a6e2b4cb1c01e3fd1504a02bd613677fd">llvm::hashing::detail::hash_state::mix_32_bytes</a>.</p>

</div>
</div>

### get\_execution\_seed() {#a8a572c218eb50cd07af7265347c113a8}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">uint64_t llvm::hashing::detail::get_execution_seed ()</td>
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

<p>In LLVM_ENABLE_ABI_BREAKING_CHECKS builds, the seed is non-deterministic per process (address of a function in LLVMSupport) to prevent having users depend on the particular hash values.</p>


<p>On platforms without ASLR, this is still likely non-deterministic per build.</p>


<p>Definition at line 313 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/adt/hashing-h">Hashing.h</a>.</p>


<p>Reference <a href="/web-llvm/docs/api/namespaces/llvm/#a2aeb96bbf49b1dd8f8a6cf1ceb4e86a7">llvm::install_fatal_error_handler</a>.</p>


<p>Referenced by <a href="#a4b425f997c3d2172f7b92a4598332b37">hash_combine_range_impl</a>, <a href="#a3978afe88908efc4773a9c2a7796e27b">hash_combine_range_impl</a>, <a href="/web-llvm/docs/api/structs/llvm/hashing/detail/hash-combine-recursive-helper/#aed86896537853171897bf29f113e382f">llvm::hashing::detail::hash_combine_recursive_helper::hash_combine_recursive_helper</a> and <a href="#a4fa6656e1c72b2fb9a6ed0659d3e248f">hash_integer_value</a>.</p>

</div>
</div>

### get\_hashable\_data() {#a4d42cd18d93c269fe8878db27f2ff8cc}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<div class="doxyMemberTemplate">template &lt;typename T&gt;</div>
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">std::enable_if_t&lt; is_hashable_data&lt; T &gt;::value, T &gt; llvm::hashing::detail::get_hashable_data (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> T &amp; value)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Helper to get the hashable data representation for a type.</p>


<p>This variant is enabled when the type itself can be used.</p>


<p>Definition at line 354 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/adt/hashing-h">Hashing.h</a>.</p>


<p>Reference <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/mips/mips16isellowering-cpp/#a0acb682b8260ab1c60b918599864e2e5">T</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/structs/llvm/hashing/detail/hash-combine-recursive-helper/#ae78cbf87cf9f0f59522d779be5d49cbb">llvm::hashing::detail::hash_combine_recursive_helper::combine</a> and <a href="#a4b425f997c3d2172f7b92a4598332b37">hash_combine_range_impl</a>.</p>

</div>
</div>

### get\_hashable\_data() {#a1b139223f5e7f4da69193a531a5f1082}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<div class="doxyMemberTemplate">template &lt;typename T&gt;</div>
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">std::enable_if_t&lt;!is_hashable_data&lt; T &gt;::value, size_t &gt; llvm::hashing::detail::get_hashable_data (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> T &amp; value)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Helper to get the hashable data representation for a type.</p>


<p>This variant is enabled when we must first call hash_value and use the result as our data.</p>


<p>Definition at line 362 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/adt/hashing-h">Hashing.h</a>.</p>


<p>References <a href="/web-llvm/docs/api/namespaces/llvm/#a0e2e479cf4860dc8a00614e36ee3d5e9">llvm::hash_value</a> and <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/mips/mips16isellowering-cpp/#a0acb682b8260ab1c60b918599864e2e5">T</a>.</p>

</div>
</div>

### hash\_16\_bytes() {#ad83862adf1fbf2399e28c062421d6a9b}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">uint64_t llvm::hashing::detail::hash_16_bytes (uint64_t low, uint64_t high)</td>
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



<p>Definition at line 170 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/adt/hashing-h">Hashing.h</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/structs/llvm/hashing/detail/hash-state/#a304239d286ddae5c8c7c04974964e1e4">llvm::hashing::detail::hash_state::create</a>, <a href="/web-llvm/docs/api/structs/llvm/hashing/detail/hash-state/#a559abae71ae014e4c9420a7a23d25dc6">llvm::hashing::detail::hash_state::finalize</a>, <a href="#a6fd531b33128989cc9e90c8e08b876d3">hash_17to32_bytes</a>, <a href="#a47f5fadf2eb86ee5088924d5760dae3f">hash_4to8_bytes</a>, <a href="#a17851b50e69ca9482ea8fb104ae202b3">hash_9to16_bytes</a> and <a href="#a4fa6656e1c72b2fb9a6ed0659d3e248f">hash_integer_value</a>.</p>

</div>
</div>

### hash\_17to32\_bytes() {#a6fd531b33128989cc9e90c8e08b876d3}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">uint64_t llvm::hashing::detail::hash_17to32_bytes (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> char * s, size_t len, uint64_t seed)</td>
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



<p>Definition at line 201 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/adt/hashing-h">Hashing.h</a>.</p>


<p>References <a href="#a6af5e05ffaf0980f306a818bbe587f41">fetch64</a>, <a href="#ad83862adf1fbf2399e28c062421d6a9b">hash_16_bytes</a>, <a href="#aa14801ceabdb9a21f12353bb2157bd9f">k0</a>, <a href="#a8024b8ff1557e1fb8d1c607b1420de02">k1</a>, <a href="#a56c87fc8a8726f0caf29ef182189d3b3">k2</a>, <a href="#a955d5d8e5c62042ded7184cc9e0516de">k3</a> and <a href="/web-llvm/docs/api/namespaces/llvm/#a06620855572cf0307aea15a25099df47">llvm::rotr</a>.</p>


<p>Referenced by <a href="#a9f8d3250fbca36e49b9c1304f31bdfb8">hash_short</a>.</p>

</div>
</div>

### hash\_1to3\_bytes() {#a04c178b7e1b96b98934763374a4485d9}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">uint64_t llvm::hashing::detail::hash_1to3_bytes (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> char * s, size_t len, uint64_t seed)</td>
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



<p>Definition at line 181 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/adt/hashing-h">Hashing.h</a>.</p>


<p>References <a href="#a56c87fc8a8726f0caf29ef182189d3b3">k2</a>, <a href="#a955d5d8e5c62042ded7184cc9e0516de">k3</a> and <a href="#aaebf1b7abefd58ee53874924675a8884">shift_mix</a>.</p>


<p>Referenced by <a href="#a9f8d3250fbca36e49b9c1304f31bdfb8">hash_short</a>.</p>

</div>
</div>

### hash\_33to64\_bytes() {#ab41bb88af8fda8fa4eaa0f41ccc98042}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">uint64_t llvm::hashing::detail::hash_33to64_bytes (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> char * s, size_t len, uint64_t seed)</td>
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



<p>Definition at line 211 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/adt/hashing-h">Hashing.h</a>.</p>


<p>References <a href="#a6af5e05ffaf0980f306a818bbe587f41">fetch64</a>, <a href="#aa14801ceabdb9a21f12353bb2157bd9f">k0</a>, <a href="#a56c87fc8a8726f0caf29ef182189d3b3">k2</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a06620855572cf0307aea15a25099df47">llvm::rotr</a> and <a href="#aaebf1b7abefd58ee53874924675a8884">shift_mix</a>.</p>


<p>Referenced by <a href="#a9f8d3250fbca36e49b9c1304f31bdfb8">hash_short</a>.</p>

</div>
</div>

### hash\_4to8\_bytes() {#a47f5fadf2eb86ee5088924d5760dae3f}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">uint64_t llvm::hashing::detail::hash_4to8_bytes (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> char * s, size_t len, uint64_t seed)</td>
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



<p>Definition at line 190 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/adt/hashing-h">Hashing.h</a>.</p>


<p>References <a href="#a8b7aec03f89d9512ce1a14a3308ca161">fetch32</a> and <a href="#ad83862adf1fbf2399e28c062421d6a9b">hash_16_bytes</a>.</p>


<p>Referenced by <a href="#a9f8d3250fbca36e49b9c1304f31bdfb8">hash_short</a>.</p>

</div>
</div>

### hash\_9to16\_bytes() {#a17851b50e69ca9482ea8fb104ae202b3}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">uint64_t llvm::hashing::detail::hash_9to16_bytes (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> char * s, size_t len, uint64_t seed)</td>
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



<p>Definition at line 195 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/adt/hashing-h">Hashing.h</a>.</p>


<p>References <a href="#a6af5e05ffaf0980f306a818bbe587f41">fetch64</a>, <a href="#ad83862adf1fbf2399e28c062421d6a9b">hash_16_bytes</a> and <a href="#a4ffb910d18d978660569ea44ac87e494">rotate</a>.</p>


<p>Referenced by <a href="#a9f8d3250fbca36e49b9c1304f31bdfb8">hash_short</a>.</p>

</div>
</div>

### hash\_combine\_range\_impl() {#a4b425f997c3d2172f7b92a4598332b37}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<div class="doxyMemberTemplate">template &lt;typename InputIteratorT&gt;</div>
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">hash_code llvm::hashing::detail::hash_combine_range_impl (InputIteratorT first, InputIteratorT last)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Implement the combining of integral values into a <a href="/web-llvm/docs/api/classes/llvm/hash-code">hash_code</a>.</p>


<p>This overload is selected when the value type of the iterator is integral. Rather than computing a <a href="/web-llvm/docs/api/classes/llvm/hash-code">hash_code</a> for each object and then combining them, this (as an optimization) directly combines the integers.</p>


<p>Definition at line 392 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/adt/hashing-h">Hashing.h</a>.</p>


<p>References <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/silowercontrolflow-cpp/#a4868c5d81c5ccc98c47aeab6244346a0">assert</a>, <a href="/web-llvm/docs/api/structs/llvm/hashing/detail/hash-state/#a304239d286ddae5c8c7c04974964e1e4">llvm::hashing::detail::hash_state::create</a>, <a href="/web-llvm/docs/api/structs/llvm/hashing/detail/hash-state/#a559abae71ae014e4c9420a7a23d25dc6">llvm::hashing::detail::hash_state::finalize</a>, <a href="#a8a572c218eb50cd07af7265347c113a8">get_execution_seed</a>, <a href="#a4d42cd18d93c269fe8878db27f2ff8cc">get_hashable_data</a>, <a href="#a9f8d3250fbca36e49b9c1304f31bdfb8">hash_short</a>, <a href="/web-llvm/docs/api/structs/llvm/hashing/detail/hash-state/#ab7b8ef7c970f0050e15688a0a3241fde">llvm::hashing::detail::hash_state::mix</a> and <a href="#a0e6505cf45fca2d42d6d02ba7fcde5b8">store_and_advance</a>.</p>

</div>
</div>

### hash\_combine\_range\_impl() {#a3978afe88908efc4773a9c2a7796e27b}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<div class="doxyMemberTemplate">template &lt;typename ValueT&gt;</div>
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">std::enable_if_t&lt; is_hashable_data&lt; ValueT &gt;::value, hash_code &gt; llvm::hashing::detail::hash_combine_range_impl (ValueT * first, ValueT * last)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Implement the combining of integral values into a <a href="/web-llvm/docs/api/classes/llvm/hash-code">hash_code</a>.</p>


<p>This overload is selected when the value type of the iterator is integral and when the input iterator is actually a pointer. Rather than computing a <a href="/web-llvm/docs/api/classes/llvm/hash-code">hash_code</a> for each object and then combining them, this (as an optimization) directly combines the integers. Also, because the integers are stored in contiguous memory, this routine avoids copying each value and directly reads from the underlying memory.</p>


<p>Definition at line 436 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/adt/hashing-h">Hashing.h</a>.</p>


<p>References <a href="/web-llvm/docs/api/structs/llvm/hashing/detail/hash-state/#a304239d286ddae5c8c7c04974964e1e4">llvm::hashing::detail::hash_state::create</a>, <a href="#a8a572c218eb50cd07af7265347c113a8">get_execution_seed</a> and <a href="#a9f8d3250fbca36e49b9c1304f31bdfb8">hash_short</a>.</p>

</div>
</div>

### hash\_integer\_value() {#a4fa6656e1c72b2fb9a6ed0659d3e248f}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">hash_code llvm::hashing::detail::hash_integer_value (uint64_t value)</td>
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

<p>Helper to hash the value of a single integer.</p>


<p>Overloads for smaller integer types are not provided to ensure consistent behavior in the presence of integral promotions. Essentially, "hash_value('4')" and "hash_value('0' + 4)" should be the same.</p>


<p>Definition at line 606 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/adt/hashing-h">Hashing.h</a>.</p>


<p>References <a href="#a8b7aec03f89d9512ce1a14a3308ca161">fetch32</a>, <a href="#a8a572c218eb50cd07af7265347c113a8">get_execution_seed</a> and <a href="#ad83862adf1fbf2399e28c062421d6a9b">hash_16_bytes</a>.</p>

</div>
</div>

### hash\_short() {#a9f8d3250fbca36e49b9c1304f31bdfb8}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">uint64_t llvm::hashing::detail::hash_short (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> char * s, size_t length, uint64_t seed)</td>
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



<p>Definition at line 234 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/adt/hashing-h">Hashing.h</a>.</p>


<p>References <a href="#a6fd531b33128989cc9e90c8e08b876d3">hash_17to32_bytes</a>, <a href="#a04c178b7e1b96b98934763374a4485d9">hash_1to3_bytes</a>, <a href="#ab41bb88af8fda8fa4eaa0f41ccc98042">hash_33to64_bytes</a>, <a href="#a47f5fadf2eb86ee5088924d5760dae3f">hash_4to8_bytes</a>, <a href="#a17851b50e69ca9482ea8fb104ae202b3">hash_9to16_bytes</a> and <a href="#a56c87fc8a8726f0caf29ef182189d3b3">k2</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/structs/llvm/hashing/detail/hash-combine-recursive-helper/#a3f4bcef234eab8fcdd8e4496777e5a9b">llvm::hashing::detail::hash_combine_recursive_helper::combine</a>, <a href="#a4b425f997c3d2172f7b92a4598332b37">hash_combine_range_impl</a> and <a href="#a3978afe88908efc4773a9c2a7796e27b">hash_combine_range_impl</a>.</p>

</div>
</div>

### rotate() {#a4ffb910d18d978660569ea44ac87e494}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">uint64_t llvm::hashing::detail::rotate (uint64_t val, size_t shift)</td>
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

<p>Bitwise right rotate.</p>


<p>Normally this will compile to a single instruction, especially if the shift is a manifest constant.</p>


<p>Definition at line 161 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/adt/hashing-h">Hashing.h</a>.</p>


<p>Referenced by <a href="#a17851b50e69ca9482ea8fb104ae202b3">hash_9to16_bytes</a>.</p>

</div>
</div>

### shift\_mix() {#aaebf1b7abefd58ee53874924675a8884}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">uint64_t llvm::hashing::detail::shift_mix (uint64_t val)</td>
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



<p>Definition at line 166 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/adt/hashing-h">Hashing.h</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/structs/llvm/hashing/detail/hash-state/#a304239d286ddae5c8c7c04974964e1e4">llvm::hashing::detail::hash_state::create</a>, <a href="/web-llvm/docs/api/structs/llvm/hashing/detail/hash-state/#a559abae71ae014e4c9420a7a23d25dc6">llvm::hashing::detail::hash_state::finalize</a>, <a href="#a04c178b7e1b96b98934763374a4485d9">hash_1to3_bytes</a> and <a href="#ab41bb88af8fda8fa4eaa0f41ccc98042">hash_33to64_bytes</a>.</p>

</div>
</div>

### store\_and\_advance() {#a0e6505cf45fca2d42d6d02ba7fcde5b8}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<div class="doxyMemberTemplate">template &lt;typename T&gt;</div>
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool llvm::hashing::detail::store_and_advance (char *&amp; buffer_ptr, char * buffer_end, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> T &amp; value, size_t offset=0)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Helper to store data from a value into a buffer and advance the pointer into that buffer.</p>


<p>This routine first checks whether there is enough space in the provided buffer, and if not immediately returns false. If there is space, it copies the underlying bytes of value into the buffer, advances the buffer_ptr past the copied bytes, and returns true.</p>


<p>Definition at line 375 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/adt/hashing-h">Hashing.h</a>.</p>


<p>Reference <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/mips/mips16isellowering-cpp/#a0acb682b8260ab1c60b918599864e2e5">T</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/structs/llvm/hashing/detail/hash-combine-recursive-helper/#a87cb33524db506474a9207907036a397">llvm::hashing::detail::hash_combine_recursive_helper::combine_data</a> and <a href="#a4b425f997c3d2172f7b92a4598332b37">hash_combine_range_impl</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Variables

### k0 {#aa14801ceabdb9a21f12353bb2157bd9f}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">uint64_t llvm::hashing::detail::k0 = 0xc3a5c85c97cb3127ULL</td>
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

<p>Some primes between 2^63 and 2^64 for various uses.</p>

<p>Definition at line 153 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/adt/hashing-h">Hashing.h</a>.</p>


<p>Referenced by <a href="#a6fd531b33128989cc9e90c8e08b876d3">hash_17to32_bytes</a> and <a href="#ab41bb88af8fda8fa4eaa0f41ccc98042">hash_33to64_bytes</a>.</p>

</div>
</div>

### k1 {#a8024b8ff1557e1fb8d1c607b1420de02}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">uint64_t llvm::hashing::detail::k1 = 0xb492b66fbe98f273ULL</td>
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



<p>Definition at line 154 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/adt/hashing-h">Hashing.h</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/structs/llvm/hashing/detail/hash-state/#a304239d286ddae5c8c7c04974964e1e4">llvm::hashing::detail::hash_state::create</a>, <a href="/web-llvm/docs/api/structs/llvm/hashing/detail/hash-state/#a559abae71ae014e4c9420a7a23d25dc6">llvm::hashing::detail::hash_state::finalize</a>, <a href="#a6fd531b33128989cc9e90c8e08b876d3">hash_17to32_bytes</a> and <a href="/web-llvm/docs/api/structs/llvm/hashing/detail/hash-state/#ab7b8ef7c970f0050e15688a0a3241fde">llvm::hashing::detail::hash_state::mix</a>.</p>

</div>
</div>

### k2 {#a56c87fc8a8726f0caf29ef182189d3b3}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">uint64_t llvm::hashing::detail::k2 = 0x9ae16a3b2f90404fULL</td>
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



<p>Definition at line 155 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/adt/hashing-h">Hashing.h</a>.</p>


<p>Referenced by <a href="#a6fd531b33128989cc9e90c8e08b876d3">hash_17to32_bytes</a>, <a href="#a04c178b7e1b96b98934763374a4485d9">hash_1to3_bytes</a>, <a href="#ab41bb88af8fda8fa4eaa0f41ccc98042">hash_33to64_bytes</a> and <a href="#a9f8d3250fbca36e49b9c1304f31bdfb8">hash_short</a>.</p>

</div>
</div>

### k3 {#a955d5d8e5c62042ded7184cc9e0516de}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">uint64_t llvm::hashing::detail::k3 = 0xc949d7c7509e6557ULL</td>
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



<p>Definition at line 156 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/adt/hashing-h">Hashing.h</a>.</p>


<p>Referenced by <a href="#a6fd531b33128989cc9e90c8e08b876d3">hash_17to32_bytes</a> and <a href="#a04c178b7e1b96b98934763374a4485d9">hash_1to3_bytes</a>.</p>

</div>
</div>

</div>

<hr/>

The documentation for this namespace was generated from the following file:

<ul>
<li><a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/adt/hashing-h">Hashing.h</a></li>
</ul>

<hr/>

<p class="doxyGeneratedBy">Generated via <a href="https://github.com/xpack/doxygen2docusaurus">doxygen2docusaurus</a> by <a href="https://www.doxygen.nl">Doxygen</a> 1.15.0.</p>

</div>
