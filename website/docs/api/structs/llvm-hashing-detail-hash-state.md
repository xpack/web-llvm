---

# DO NOT EDIT!
# Automatically generated via doxygen2docusaurus by Doxygen.

slug: /api/structs/llvm/hashing/detail/hash-state
custom_edit_url: null
toc_max_heading_level: 4
keywords:
  - doxygen
  - reference
  - struct

---

<div class="doxyPage">

# `hash_state` Struct

<p>The intermediate state used during hashing. <a href="#details">More...</a></p>

## Declaration

<div class="doxyDeclaration">
struct llvm::hashing::detail::hash_state { ... }
</div>

## Included Headers

<div class="doxyIncludesList">#include "<a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/adt/hashing-h">llvm/ADT/Hashing.h</a>"
</div>

## Public Member Functions Index

<table class="doxyMembersIndex">

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">void</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ab7b8ef7c970f0050e15688a0a3241fde">mix</a> (const char *s)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Mix in a 64-byte buffer of data. <a href="#ab7b8ef7c970f0050e15688a0a3241fde">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">uint64_t</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a559abae71ae014e4c9420a7a23d25dc6">finalize</a> (size_t length)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Compute the final 64-bit hash code value based on the current state and the length of bytes hashed. <a href="#a559abae71ae014e4c9420a7a23d25dc6">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

</table>

## Public Member Attributes Index

<table class="doxyMembersIndex">

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">uint64_t</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#afd7bc94b3368f293d73243e0c2252199">h0</a> = 0</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a066e9765c5bc2a3e6240cea24123e89a">h1</a> = 0</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ac3fb731f4a7cf1257cc129b1d3119b71">h2</a> = 0</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a472772dcef33b525c2f458ce5ed37554">h3</a> = 0</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#afae92e6488bf8e65c72f1d96ad9edb8c">h4</a> = 0</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a92a5fa1b3b425299ac1ce8d7daff0b27">h5</a> = 0</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#adeeb0bb9c8445a9f89e46c8af40553fe">h6</a> = 0</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">static <a href="/web-llvm/docs/api/structs/llvm/hashing/detail/hash-state">hash_state</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a304239d286ddae5c8c7c04974964e1e4">create</a> (const char *s, uint64_t seed)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Create a new <a href="/web-llvm/docs/api/structs/llvm/hashing/detail/hash-state">hash_state</a> structure and initialize it based on the seed and the first 64-byte chunk. <a href="#a304239d286ddae5c8c7c04974964e1e4">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">static void</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a6e2b4cb1c01e3fd1504a02bd613677fd">mix_32_bytes</a> (const char *s, uint64_t &amp;a, uint64_t &amp;b)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Mix 32-bytes from the input sequence into the 16-bytes of 'a' and 'b', including whatever is already in 'a' and 'b'. <a href="#a6e2b4cb1c01e3fd1504a02bd613677fd">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

</table>

## Description {#details}

<p>The intermediate state used during hashing.</p>


<p>Currently, the algorithm for computing hash codes is based on CityHash and keeps 56 bytes of arbitrary state.</p>


<p>Definition at line 252 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/adt/hashing-h">Hashing.h</a>.</p>


<div class="doxySectionDef">

## Public Member Functions

### finalize() {#a559abae71ae014e4c9420a7a23d25dc6}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">uint64_t llvm::hashing::detail::hash_state::finalize (size_t length)</td>
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

<p>Compute the final 64-bit hash code value based on the current state and the length of bytes hashed.</p>

<p>Definition at line 303 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/adt/hashing-h">Hashing.h</a>.</p>


<p>References <a href="#afd7bc94b3368f293d73243e0c2252199">h0</a>, <a href="#a066e9765c5bc2a3e6240cea24123e89a">h1</a>, <a href="#ac3fb731f4a7cf1257cc129b1d3119b71">h2</a>, <a href="#a472772dcef33b525c2f458ce5ed37554">h3</a>, <a href="#afae92e6488bf8e65c72f1d96ad9edb8c">h4</a>, <a href="#a92a5fa1b3b425299ac1ce8d7daff0b27">h5</a>, <a href="#adeeb0bb9c8445a9f89e46c8af40553fe">h6</a>, <a href="/web-llvm/docs/api/namespaces/llvm/hashing/detail/#ad83862adf1fbf2399e28c062421d6a9b">llvm::hashing::detail::hash_16_bytes</a>, <a href="/web-llvm/docs/api/namespaces/llvm/hashing/detail/#a8024b8ff1557e1fb8d1c607b1420de02">llvm::hashing::detail::k1</a> and <a href="/web-llvm/docs/api/namespaces/llvm/hashing/detail/#aaebf1b7abefd58ee53874924675a8884">llvm::hashing::detail::shift_mix</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/namespaces/llvm/hashing/detail/#a4b425f997c3d2172f7b92a4598332b37">llvm::hashing::detail::hash_combine_range_impl</a>.</p>

</div>
</div>

### mix() {#ab7b8ef7c970f0050e15688a0a3241fde}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void llvm::hashing::detail::hash_state::mix (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> char * s)</td>
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

<p>Mix in a 64-byte buffer of data.</p>


<p>We mix all 64 bytes even when the chunk length is smaller, but we record the actual length.</p>


<p>Definition at line 286 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/adt/hashing-h">Hashing.h</a>.</p>


<p>References <a href="/web-llvm/docs/api/namespaces/llvm/hashing/detail/#a6af5e05ffaf0980f306a818bbe587f41">llvm::hashing::detail::fetch64</a>, <a href="#afd7bc94b3368f293d73243e0c2252199">h0</a>, <a href="#a066e9765c5bc2a3e6240cea24123e89a">h1</a>, <a href="#ac3fb731f4a7cf1257cc129b1d3119b71">h2</a>, <a href="#a472772dcef33b525c2f458ce5ed37554">h3</a>, <a href="#afae92e6488bf8e65c72f1d96ad9edb8c">h4</a>, <a href="#a92a5fa1b3b425299ac1ce8d7daff0b27">h5</a>, <a href="#adeeb0bb9c8445a9f89e46c8af40553fe">h6</a>, <a href="/web-llvm/docs/api/namespaces/llvm/hashing/detail/#a8024b8ff1557e1fb8d1c607b1420de02">llvm::hashing::detail::k1</a>, <a href="#a6e2b4cb1c01e3fd1504a02bd613677fd">mix_32_bytes</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a06620855572cf0307aea15a25099df47">llvm::rotr</a> and <a href="/web-llvm/docs/api/namespaces/std/#ab8424022895aee3e366fb9a32f2883cb">std::swap</a>.</p>


<p>Referenced by <a href="#a304239d286ddae5c8c7c04974964e1e4">create</a> and <a href="/web-llvm/docs/api/namespaces/llvm/hashing/detail/#a4b425f997c3d2172f7b92a4598332b37">llvm::hashing::detail::hash_combine_range_impl</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Public Member Attributes

### h0 {#afd7bc94b3368f293d73243e0c2252199}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">uint64_t llvm::hashing::detail::hash_state::h0 = 0</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 253 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/adt/hashing-h">Hashing.h</a>.</p>


<p>Referenced by <a href="#a559abae71ae014e4c9420a7a23d25dc6">finalize</a> and <a href="#ab7b8ef7c970f0050e15688a0a3241fde">mix</a>.</p>

</div>
</div>

### h1 {#a066e9765c5bc2a3e6240cea24123e89a}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">uint64_t llvm::hashing::detail::hash_state::h1 = 0</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 253 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/adt/hashing-h">Hashing.h</a>.</p>


<p>Referenced by <a href="#a559abae71ae014e4c9420a7a23d25dc6">finalize</a> and <a href="#ab7b8ef7c970f0050e15688a0a3241fde">mix</a>.</p>

</div>
</div>

### h2 {#ac3fb731f4a7cf1257cc129b1d3119b71}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">uint64_t llvm::hashing::detail::hash_state::h2 = 0</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 253 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/adt/hashing-h">Hashing.h</a>.</p>


<p>Referenced by <a href="#a559abae71ae014e4c9420a7a23d25dc6">finalize</a> and <a href="#ab7b8ef7c970f0050e15688a0a3241fde">mix</a>.</p>

</div>
</div>

### h3 {#a472772dcef33b525c2f458ce5ed37554}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">uint64_t llvm::hashing::detail::hash_state::h3 = 0</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 253 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/adt/hashing-h">Hashing.h</a>.</p>


<p>Referenced by <a href="#a559abae71ae014e4c9420a7a23d25dc6">finalize</a> and <a href="#ab7b8ef7c970f0050e15688a0a3241fde">mix</a>.</p>

</div>
</div>

### h4 {#afae92e6488bf8e65c72f1d96ad9edb8c}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">uint64_t llvm::hashing::detail::hash_state::h4 = 0</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 253 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/adt/hashing-h">Hashing.h</a>.</p>


<p>Referenced by <a href="#a304239d286ddae5c8c7c04974964e1e4">create</a>, <a href="#a559abae71ae014e4c9420a7a23d25dc6">finalize</a> and <a href="#ab7b8ef7c970f0050e15688a0a3241fde">mix</a>.</p>

</div>
</div>

### h5 {#a92a5fa1b3b425299ac1ce8d7daff0b27}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">uint64_t llvm::hashing::detail::hash_state::h5 = 0</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 253 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/adt/hashing-h">Hashing.h</a>.</p>


<p>Referenced by <a href="#a304239d286ddae5c8c7c04974964e1e4">create</a>, <a href="#a559abae71ae014e4c9420a7a23d25dc6">finalize</a> and <a href="#ab7b8ef7c970f0050e15688a0a3241fde">mix</a>.</p>

</div>
</div>

### h6 {#adeeb0bb9c8445a9f89e46c8af40553fe}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">uint64_t llvm::hashing::detail::hash_state::h6 = 0</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 253 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/adt/hashing-h">Hashing.h</a>.</p>


<p>Referenced by <a href="#a304239d286ddae5c8c7c04974964e1e4">create</a>, <a href="#a559abae71ae014e4c9420a7a23d25dc6">finalize</a> and <a href="#ab7b8ef7c970f0050e15688a0a3241fde">mix</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Public Static Functions

### create() {#a304239d286ddae5c8c7c04974964e1e4}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">hash_state llvm::hashing::detail::hash_state::create (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> char * s, uint64_t seed)</td>
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

<p>Create a new <a href="/web-llvm/docs/api/structs/llvm/hashing/detail/hash-state">hash_state</a> structure and initialize it based on the seed and the first 64-byte chunk.</p>


<p>This effectively performs the initial mix.</p>


<p>Definition at line 258 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/adt/hashing-h">Hashing.h</a>.</p>


<p>References <a href="#afae92e6488bf8e65c72f1d96ad9edb8c">h4</a>, <a href="#a92a5fa1b3b425299ac1ce8d7daff0b27">h5</a>, <a href="#adeeb0bb9c8445a9f89e46c8af40553fe">h6</a>, <a href="/web-llvm/docs/api/namespaces/llvm/hashing/detail/#ad83862adf1fbf2399e28c062421d6a9b">llvm::hashing::detail::hash_16_bytes</a>, <a href="/web-llvm/docs/api/namespaces/llvm/hashing/detail/#a8024b8ff1557e1fb8d1c607b1420de02">llvm::hashing::detail::k1</a>, <a href="#ab7b8ef7c970f0050e15688a0a3241fde">mix</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a06620855572cf0307aea15a25099df47">llvm::rotr</a> and <a href="/web-llvm/docs/api/namespaces/llvm/hashing/detail/#aaebf1b7abefd58ee53874924675a8884">llvm::hashing::detail::shift_mix</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/namespaces/llvm/hashing/detail/#a4b425f997c3d2172f7b92a4598332b37">llvm::hashing::detail::hash_combine_range_impl</a> and <a href="/web-llvm/docs/api/namespaces/llvm/hashing/detail/#a3978afe88908efc4773a9c2a7796e27b">llvm::hashing::detail::hash_combine_range_impl</a>.</p>

</div>
</div>

### mix\_32\_bytes() {#a6e2b4cb1c01e3fd1504a02bd613677fd}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void llvm::hashing::detail::hash_state::mix_32_bytes (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> char * s, uint64_t &amp; a, uint64_t &amp; b)</td>
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

<p>Mix 32-bytes from the input sequence into the 16-bytes of 'a' and 'b', including whatever is already in 'a' and 'b'.</p>

<p>Definition at line 273 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/adt/hashing-h">Hashing.h</a>.</p>


<p>References <a href="/web-llvm/docs/api/namespaces/llvm/hashing/detail/#a6af5e05ffaf0980f306a818bbe587f41">llvm::hashing::detail::fetch64</a> and <a href="/web-llvm/docs/api/namespaces/llvm/#a06620855572cf0307aea15a25099df47">llvm::rotr</a>.</p>


<p>Referenced by <a href="#ab7b8ef7c970f0050e15688a0a3241fde">mix</a>.</p>

</div>
</div>

</div>

<hr/>

The documentation for this struct was generated from the following file:

<ul>
<li><a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/adt/hashing-h">Hashing.h</a></li>
</ul>

<hr/>

<p class="doxyGeneratedBy">Generated via <a href="https://xpack.github.io/doxygen2docusaurus">doxygen2docusaurus</a> 2.0.0 by <a href="https://www.doxygen.nl">Doxygen</a> 1.15.0.</p>

</div>
