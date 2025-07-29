---

# DO NOT EDIT!
# Automatically generated via doxygen2docusaurus by Doxygen.

slug: /api/files/lib/lib/support/xxhash-cpp
custom_edit_url: null
toc_max_heading_level: 4
keywords:
  - doxygen
  - reference
  - file

---

<div class="doxyPage">

# `xxhash.cpp` File



## Included Headers

<div class="doxyIncludesList">#include "<a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/support/xxhash-h">llvm/Support/xxhash.h</a>"
#include "<a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/support/compiler-h">llvm/Support/Compiler.h</a>"
#include "<a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/support/endian-h">llvm/Support/Endian.h</a>"
#include &lt;stdlib.h&gt;
</div>

## Functions Index

<table class="doxyMembersIndex">

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">static uint64_t</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#abfb1fc3e8788d6965f172f6f0d1f9e04">rotl64</a> (uint64_t X, size_t R)</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">static uint64_t</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ae4e947c75dafebd71b8de03cd0dbf5d6">round</a> (uint64_t Acc, uint64_t Input)</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">static uint64_t</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a0822bb275b7fdd5cf225585e27c59631">mergeRound</a> (uint64_t Acc, uint64_t Val)</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">static uint64_t</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#acc6968c79b8da93dea87b708f2fe2734">XXH64_avalanche</a> (uint64_t hash)</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">static uint64_t</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ae07c124bf50a0ad869649d3e1d0def90">XXH3_mul128_fold64</a> (uint64_t lhs, uint64_t rhs)</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">static uint64_t</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a5f41b833306622b3b79b209e3829bbb1">XXH3_avalanche</a> (uint64_t hash)</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">static uint64_t</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a25817408849438429707b1d7c48e5fcd">XXH3_len_1to3_64b</a> (const uint8_t *input, size_t len, const uint8_t *secret, uint64_t seed)</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">static uint64_t</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a14f60c710e7d2ab06a8211b0ba1e5306">XXH3_len_4to8_64b</a> (const uint8_t *input, size_t len, const uint8_t *secret, uint64_t seed)</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">static uint64_t</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a00cd136a7e5ebdb8f1920e7353349525">XXH3_len_9to16_64b</a> (const uint8_t *input, size_t len, const uint8_t *secret, uint64_t const seed)</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">static <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/support/compiler-h/#a338bdf98e9e600f582b7bef274bc9388">LLVM_ATTRIBUTE_ALWAYS_INLINE</a> uint64_t</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#adf1ca5feb6e370f2f2d4ceb328c927e6">XXH3_len_0to16_64b</a> (const uint8_t *input, size_t len, const uint8_t *secret, uint64_t const seed)</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">static uint64_t</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a3bdcfa0a87da5bece4e02edac5b0446f">XXH3_mix16B</a> (const uint8_t *input, uint8_t const *secret, uint64_t seed)</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">static <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/support/compiler-h/#a338bdf98e9e600f582b7bef274bc9388">LLVM_ATTRIBUTE_ALWAYS_INLINE</a> uint64_t</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a7b1955f2dfac4943d24dd55944b86062">XXH3_len_17to128_64b</a> (const uint8_t *input, size_t len, const uint8_t *secret, uint64_t const seed)</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">static <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/support/compiler-h/#ac6a5e0eb6a9944baf6ba14b640eab6e1">LLVM_ATTRIBUTE_NOINLINE</a> uint64_t</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a7c06bb47122eb6d599f8477e9781bd4c">XXH3_len_129to240_64b</a> (const uint8_t *input, size_t len, const uint8_t *secret, uint64_t seed)</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">static <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/support/compiler-h/#a338bdf98e9e600f582b7bef274bc9388">LLVM_ATTRIBUTE_ALWAYS_INLINE</a> void</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#adc9c81b2946609f0260dabe87fea8821">XXH3_accumulate_512_scalar</a> (uint64_t *acc, const uint8_t *input, const uint8_t *secret)</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">static <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/support/compiler-h/#a338bdf98e9e600f582b7bef274bc9388">LLVM_ATTRIBUTE_ALWAYS_INLINE</a> void</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ad36d7562c24a3eed4705f092dd82ca23">XXH3_scrambleAcc_scalar</a> (uint64_t *acc, const uint8_t *secret)</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">static <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/support/compiler-h/#a338bdf98e9e600f582b7bef274bc9388">LLVM_ATTRIBUTE_ALWAYS_INLINE</a> void</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a1e182c7dbecb63c4c47a78a965ec9909">XXH3_accumulate</a> (uint64_t *acc, const uint8_t *input, const uint8_t *secret, size_t nbStripes)</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">static uint64_t</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#add6dbf56c8f88ad835ce0c76e4fa3acc">XXH3_mix2Accs</a> (const uint64_t *acc, const uint8_t *secret)</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">static uint64_t</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a3b22297ce97b41b9ea8df1e9ec9d6d9a">XXH3_mergeAccs</a> (const uint64_t *acc, const uint8_t *key, uint64_t start)</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">static <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/support/compiler-h/#ac6a5e0eb6a9944baf6ba14b640eab6e1">LLVM_ATTRIBUTE_NOINLINE</a> uint64_t</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a1a58a266c5393605d6eb9b9f26e3ab29">XXH3_hashLong_64b</a> (const uint8_t *input, size_t len, const uint8_t *secret, size_t secretSize)</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">static <a href="/web-llvm/docs/api/structs/llvm/xxh128-hash-t">XXH128_hash_t</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a5a010401dcddb43e0a6fdcac9564d69b">XXH_mult64to128</a> (uint64_t lhs, uint64_t rhs)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Calculates a 64-&gt;128-bit long multiply. <a href="#a5a010401dcddb43e0a6fdcac9564d69b">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/support/compiler-h/#a338bdf98e9e600f582b7bef274bc9388">LLVM_ATTRIBUTE_ALWAYS_INLINE</a> constexpr uint64_t</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#aace3bad147eeed78a2f1cab33d506d59">XXH_xorshift64</a> (uint64_t v64, int shift)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Seems to produce slightly better code on GCC for some reason. <a href="#aace3bad147eeed78a2f1cab33d506d59">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">static <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/support/compiler-h/#a338bdf98e9e600f582b7bef274bc9388">LLVM_ATTRIBUTE_ALWAYS_INLINE</a> <a href="/web-llvm/docs/api/structs/llvm/xxh128-hash-t">XXH128_hash_t</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a1f9fe4a69b646dae9518d991adc12a00">XXH3_len_1to3_128b</a> (const uint8_t *input, size_t len, const uint8_t *secret, uint64_t seed)</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">static <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/support/compiler-h/#a338bdf98e9e600f582b7bef274bc9388">LLVM_ATTRIBUTE_ALWAYS_INLINE</a> <a href="/web-llvm/docs/api/structs/llvm/xxh128-hash-t">XXH128_hash_t</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a611ba08ac061c11dce0a30072099ba3c">XXH3_len_4to8_128b</a> (const uint8_t *input, size_t len, const uint8_t *secret, uint64_t seed)</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">static <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/support/compiler-h/#a338bdf98e9e600f582b7bef274bc9388">LLVM_ATTRIBUTE_ALWAYS_INLINE</a> <a href="/web-llvm/docs/api/structs/llvm/xxh128-hash-t">XXH128_hash_t</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a68128490131d65e06f6066616f80ddf5">XXH3_len_9to16_128b</a> (const uint8_t *input, size_t len, const uint8_t *secret, uint64_t seed)</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">static <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/support/compiler-h/#a338bdf98e9e600f582b7bef274bc9388">LLVM_ATTRIBUTE_ALWAYS_INLINE</a> <a href="/web-llvm/docs/api/structs/llvm/xxh128-hash-t">XXH128_hash_t</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a6f213bbbdebd84c8536a43217f014dbc">XXH3_len_0to16_128b</a> (const uint8_t *input, size_t len, const uint8_t *secret, uint64_t seed)</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">static <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/support/compiler-h/#a338bdf98e9e600f582b7bef274bc9388">LLVM_ATTRIBUTE_ALWAYS_INLINE</a> <a href="/web-llvm/docs/api/structs/llvm/xxh128-hash-t">XXH128_hash_t</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a2fa22ae762463bb383e63bd381952344">XXH128_mix32B</a> (XXH128_hash_t acc, const uint8_t *input_1, const uint8_t *input_2, const uint8_t *secret, uint64_t seed)</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">static <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/support/compiler-h/#a338bdf98e9e600f582b7bef274bc9388">LLVM_ATTRIBUTE_ALWAYS_INLINE</a> <a href="/web-llvm/docs/api/structs/llvm/xxh128-hash-t">XXH128_hash_t</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a43d708e6a6393ad5f59e3ade57f205d2">XXH3_len_17to128_128b</a> (const uint8_t *input, size_t len, const uint8_t *secret, size_t secretSize, uint64_t seed)</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">static <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/support/compiler-h/#ac6a5e0eb6a9944baf6ba14b640eab6e1">LLVM_ATTRIBUTE_NOINLINE</a> <a href="/web-llvm/docs/api/structs/llvm/xxh128-hash-t">XXH128_hash_t</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a67de1b04da6de33341dc7ffc6854fa9f">XXH3_len_129to240_128b</a> (const uint8_t *input, size_t len, const uint8_t *secret, size_t secretSize, uint64_t seed)</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/support/compiler-h/#a338bdf98e9e600f582b7bef274bc9388">LLVM_ATTRIBUTE_ALWAYS_INLINE</a> <a href="/web-llvm/docs/api/structs/llvm/xxh128-hash-t">XXH128_hash_t</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#abfad913bbf7470e15bdfa2349f67a258">XXH3_hashLong_128b</a> (const uint8_t *input, size_t len, const uint8_t *secret, size_t secretSize)</td>
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

## Variables Index

<table class="doxyMembersIndex">

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">constexpr uint32_t</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a6c0de75169f0f5ffd3d63059d77fa81c">PRIME32_1</a> = 0x9E3779B1</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">constexpr uint32_t</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a6db4d465a9f3c93ce1369c017071c9fb">PRIME32_2</a> = 0x85EBCA77</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">constexpr uint32_t</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a88fbf55eb4adbc5271b7340dc8b46992">PRIME32_3</a> = 0xC2B2AE3D</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">static <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> uint64_t</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a502e23a6442aeb2e9d55069d0f600e7e">PRIME64_1</a> = 11400714785074694791ULL</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">static <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> uint64_t</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a713d2b3b0b93699da8b5140e49ae0724">PRIME64_2</a> = 14029467366897019727ULL</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">static <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> uint64_t</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a26ec2310be052725d92271c3ce0ea530">PRIME64_3</a> = 1609587929392839161ULL</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">static <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> uint64_t</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a8faeab42c1df0e8e3113f802e6ee0fb7">PRIME64_4</a> = 9650029242287828579ULL</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">static <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> uint64_t</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#aa89ac3cdaaa1e088d332977e864af1e2">PRIME64_5</a> = 2870177450012600261ULL</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">constexpr size_t</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a664aa3b693f86bf4a82b7022a34defd3">XXH3_SECRETSIZE_MIN</a> = 136</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">constexpr size_t</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ad54096aad01dc78abb39fcc6af421abf">XXH_SECRET_DEFAULT_SIZE</a> = 192</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">constexpr uint8_t</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a789b8647bf303ff177d153fb36e07083">kSecret</a>[XXH_SECRET_DEFAULT_SIZE] = ...</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">constexpr uint64_t</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ad941dff9ebd5cdcb0211a1a1cf4360a1">PRIME_MX1</a> = 0x165667919E3779F9</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">constexpr uint64_t</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#af96c90d6eedd426a1e2213b4f9fbbc27">PRIME_MX2</a> = 0x9FB21C651E98DF25</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">constexpr size_t</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a89842525985161520ed4732a91f716f6">XXH_STRIPE_LEN</a> = 64</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">constexpr size_t</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ae53fc54ef119c31f40b8656a76911afb">XXH_SECRET_CONSUME_RATE</a> = 8</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">constexpr size_t</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a9ea37a7b5fe9a6a0d4f8b268a3c3414f">XXH_ACC_NB</a> = <a href="#a89842525985161520ed4732a91f716f6">XXH_STRIPE_LEN</a> / sizeof(uint64_t)</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">constexpr size_t</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a76cb2d6f9c4fc976d85ff8ed764b3c93">XXH3_MIDSIZE_MAX</a> = 240</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">constexpr size_t</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ade8a17ad42d2de81b0dbce47fd36618e">XXH3_MIDSIZE_STARTOFFSET</a> = 3</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">constexpr size_t</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#aff6d4d2c6782a3970af32558ac0d87a1">XXH3_MIDSIZE_LASTOFFSET</a> = 17</td>
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

## Macro Definitions Index

<table class="doxyMembersIndex">

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">#define</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a14e0090d82a5322599d194a2348986c9">LLVM_XXH_USE_NEON</a>&nbsp;&nbsp;&nbsp;0</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">#define</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a5ffe3391e408f75f726da56c67701f8f">XXH3_accumulate_512</a>&nbsp;&nbsp;&nbsp;<a href="#adc9c81b2946609f0260dabe87fea8821">XXH3_accumulate_512_scalar</a></td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">#define</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a90fcb30d61f3d5fc00e56081205f4a30">XXH3_scrambleAcc</a>&nbsp;&nbsp;&nbsp;<a href="#ad36d7562c24a3eed4705f092dd82ca23">XXH3_scrambleAcc_scalar</a></td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">#define</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a70a4b202f9523a2a811da16cde3f52eb">XXH_rotl32</a>(x, r)&nbsp;&nbsp;&nbsp;(((x) &lt;&lt; (r)) | ((x) &gt;&gt; (32 - (r))))</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">#define</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a056473e50ab5e7acb43d00ca3d41632e">XXH_rotl64</a>(x, r)&nbsp;&nbsp;&nbsp;(((x) &lt;&lt; (r)) | ((x) &gt;&gt; (64 - (r))))</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">#define</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a08f3f09f1c097e41499563c7468d031c">XXH_mult32to64</a>(x, y)&nbsp;&nbsp;&nbsp;((uint64_t)(uint32_t)(x) * (uint64_t)(uint32_t)(y))</td>
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

### mergeRound() {#a0822bb275b7fdd5cf225585e27c59631}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">uint64_t mergeRound (uint64_t Acc, uint64_t Val)</td>
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



<p>Definition at line 87 of file <a href="/web-llvm/docs/api/files/lib/lib/support/xxhash-cpp">xxhash.cpp</a>.</p>


<p>References <a href="#a502e23a6442aeb2e9d55069d0f600e7e">PRIME64_1</a>, <a href="#a8faeab42c1df0e8e3113f802e6ee0fb7">PRIME64_4</a> and <a href="#ae4e947c75dafebd71b8de03cd0dbf5d6">round</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/namespaces/llvm/#afd78f9f642d72c07d9082f228a6389db">llvm::xxHash64</a>.</p>

</div>
</div>

### rotl64() {#abfb1fc3e8788d6965f172f6f0d1f9e04}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">uint64_t rotl64 (uint64_t X, size_t R)</td>
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



<p>Definition at line 66 of file <a href="/web-llvm/docs/api/files/lib/lib/support/xxhash-cpp">xxhash.cpp</a>.</p>


<p>Reference <a href="/web-llvm/docs/api/files/lib/lib/tablegen/tablegenbackendskeleton-cpp/#ab60f28d7a141ac46ccc200176a1bca8b">X</a>.</p>


<p>Referenced by <a href="#ae4e947c75dafebd71b8de03cd0dbf5d6">round</a>, <a href="#a14f60c710e7d2ab06a8211b0ba1e5306">XXH3_len_4to8_64b</a> and <a href="/web-llvm/docs/api/namespaces/llvm/#afd78f9f642d72c07d9082f228a6389db">llvm::xxHash64</a>.</p>

</div>
</div>

### round() {#ae4e947c75dafebd71b8de03cd0dbf5d6}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">uint64_t round (uint64_t Acc, uint64_t Input)</td>
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



<p>Definition at line 80 of file <a href="/web-llvm/docs/api/files/lib/lib/support/xxhash-cpp">xxhash.cpp</a>.</p>


<p>References <a href="#a502e23a6442aeb2e9d55069d0f600e7e">PRIME64_1</a>, <a href="#a713d2b3b0b93699da8b5140e49ae0724">PRIME64_2</a> and <a href="#abfb1fc3e8788d6965f172f6f0d1f9e04">rotl64</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/classes/llvm/sampleprof/defaultfunctionpruningstrategy/#a8abb143feff2f640ccc483ba91019c1b">llvm::sampleprof::DefaultFunctionPruningStrategy::Erase</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a389a9c4d07846d6ff47386499cc7415f">llvm::getHeatColor</a>, <a href="#a0822bb275b7fdd5cf225585e27c59631">mergeRound</a>, <a href="/web-llvm/docs/api/files/lib/lib/support/lib/support/blake3/blake3-portable-c/#a87355412d6387311f7e404e04ecd5ed0">round_fn</a>, <a href="/web-llvm/docs/api/classes/llvm/apint/#af48b6a9423c3b72b453f0eb881129d3b">llvm::APInt::sqrt</a> and <a href="/web-llvm/docs/api/namespaces/llvm/#afd78f9f642d72c07d9082f228a6389db">llvm::xxHash64</a>.</p>

</div>
</div>

### XXH\_mult64to128() {#a5a010401dcddb43e0a6fdcac9564d69b}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">XXH128_hash_t XXH_mult64to128 (uint64_t lhs, uint64_t rhs)</td>
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

<p>Calculates a 64-&gt;128-bit long multiply.</p>


<p>Uses <span class="doxyComputerOutput">__uint128_t</span> and <span class="doxyComputerOutput">_umul128</span> if available, otherwise uses a scalar version.</p>


<dl class="doxyParamsList">
<dt class="doxyParamsTableTitle">Parameters</dt>
<dd>
<table class="doxyParamsTable">
<tr class="doxyParamItem">
<td class="doxyParamItemName">lhs, rhs</td>
<td class="doxyParamItemDescription"><p>The 64-bit integers to be multiplied</p></td>
</tr>
</table>
</dd>
</dl>

<dl class="doxySectionUser">
<dt>Returns</dt>
<dd><p>The 128-bit result represented in an XXH128_hash_t.</p></dd>
</dl>


<p>Definition at line 620 of file <a href="/web-llvm/docs/api/files/lib/lib/support/xxhash-cpp">xxhash.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/structs/llvm/xxh128-hash-t/#af6ae9edb7b299ab65fcbc7eca03b381a">llvm::XXH128_hash_t::high64</a>, <a href="/web-llvm/docs/api/structs/llvm/xxh128-hash-t/#a994e5b99d3dceafee44f8c983d75103b">llvm::XXH128_hash_t::low64</a> and <a href="#a08f3f09f1c097e41499563c7468d031c">XXH_mult32to64</a>.</p>


<p>Referenced by <a href="#a611ba08ac061c11dce0a30072099ba3c">XXH3_len_4to8_128b</a> and <a href="#a68128490131d65e06f6066616f80ddf5">XXH3_len_9to16_128b</a>.</p>

</div>
</div>

### XXH\_xorshift64() {#aace3bad147eeed78a2f1cab33d506d59}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">LLVM_ATTRIBUTE_ALWAYS_INLINE constexpr uint64_t XXH_xorshift64 (uint64_t v64, int shift)</td>
</tr>
</table>
</td>
<td class="doxyMemberLabelsRight">
<span class="doxyMemberLabels">
<span class="doxyMemberLabel constexpr">constexpr</span>
</span>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Seems to produce slightly better code on GCC for some reason.</p>

<p>Definition at line 744 of file <a href="/web-llvm/docs/api/files/lib/lib/support/xxhash-cpp">xxhash.cpp</a>.</p>


<p>Reference <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/support/compiler-h/#a338bdf98e9e600f582b7bef274bc9388">LLVM_ATTRIBUTE_ALWAYS_INLINE</a>.</p>


<p>Referenced by <a href="#a611ba08ac061c11dce0a30072099ba3c">XXH3_len_4to8_128b</a>.</p>

</div>
</div>

### XXH128\_mix32B() {#a2fa22ae762463bb383e63bd381952344}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">LLVM_ATTRIBUTE_ALWAYS_INLINE XXH128_hash_t XXH128_mix32B (<a href="/web-llvm/docs/api/structs/llvm/xxh128-hash-t">XXH128_hash_t</a> acc, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> uint8_t * input_1, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> uint8_t * input_2, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> uint8_t * secret, uint64_t seed)</td>
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



<p>Definition at line 900 of file <a href="/web-llvm/docs/api/files/lib/lib/support/xxhash-cpp">xxhash.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/structs/llvm/xxh128-hash-t/#a994e5b99d3dceafee44f8c983d75103b">llvm::XXH128_hash_t::low64</a>, <a href="/web-llvm/docs/api/namespaces/llvm/support/endian/#a0fa2f859066acd16820ab083040158c9">llvm::support::endian::read64le</a> and <a href="#a3bdcfa0a87da5bece4e02edac5b0446f">XXH3_mix16B</a>.</p>


<p>Referenced by <a href="#a67de1b04da6de33341dc7ffc6854fa9f">XXH3_len_129to240_128b</a> and <a href="#a43d708e6a6393ad5f59e3ade57f205d2">XXH3_len_17to128_128b</a>.</p>

</div>
</div>

### XXH3\_accumulate() {#a1e182c7dbecb63c4c47a78a965ec9909}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">LLVM_ATTRIBUTE_ALWAYS_INLINE void XXH3_accumulate (uint64_t * acc, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> uint8_t * input, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> uint8_t * secret, size_t nbStripes)</td>
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



<p>Definition at line 499 of file <a href="/web-llvm/docs/api/files/lib/lib/support/xxhash-cpp">xxhash.cpp</a>.</p>


<p>References <a href="#a5ffe3391e408f75f726da56c67701f8f">XXH3_accumulate_512</a>, <a href="#ae53fc54ef119c31f40b8656a76911afb">XXH_SECRET_CONSUME_RATE</a> and <a href="#a89842525985161520ed4732a91f716f6">XXH_STRIPE_LEN</a>.</p>


<p>Referenced by <a href="#abfad913bbf7470e15bdfa2349f67a258">XXH3_hashLong_128b</a> and <a href="#a1a58a266c5393605d6eb9b9f26e3ab29">XXH3_hashLong_64b</a>.</p>

</div>
</div>

### XXH3\_accumulate\_512\_scalar() {#adc9c81b2946609f0260dabe87fea8821}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">LLVM_ATTRIBUTE_ALWAYS_INLINE void XXH3_accumulate_512_scalar (uint64_t * acc, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> uint8_t * input, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> uint8_t * secret)</td>
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



<p>Definition at line 478 of file <a href="/web-llvm/docs/api/files/lib/lib/support/xxhash-cpp">xxhash.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/namespaces/llvm/support/endian/#a0fa2f859066acd16820ab083040158c9">llvm::support::endian::read64le</a> and <a href="#a9ea37a7b5fe9a6a0d4f8b268a3c3414f">XXH_ACC_NB</a>.</p>

</div>
</div>

### XXH3\_avalanche() {#a5f41b833306622b3b79b209e3829bbb1}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">uint64_t XXH3_avalanche (uint64_t hash)</td>
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



<p>Definition at line 218 of file <a href="/web-llvm/docs/api/files/lib/lib/support/xxhash-cpp">xxhash.cpp</a>.</p>


<p>Reference <a href="#ad941dff9ebd5cdcb0211a1a1cf4360a1">PRIME_MX1</a>.</p>


<p>Referenced by <a href="#a67de1b04da6de33341dc7ffc6854fa9f">XXH3_len_129to240_128b</a>, <a href="#a7c06bb47122eb6d599f8477e9781bd4c">XXH3_len_129to240_64b</a>, <a href="#a43d708e6a6393ad5f59e3ade57f205d2">XXH3_len_17to128_128b</a>, <a href="#a7b1955f2dfac4943d24dd55944b86062">XXH3_len_17to128_64b</a>, <a href="#a611ba08ac061c11dce0a30072099ba3c">XXH3_len_4to8_128b</a>, <a href="#a68128490131d65e06f6066616f80ddf5">XXH3_len_9to16_128b</a>, <a href="#a00cd136a7e5ebdb8f1920e7353349525">XXH3_len_9to16_64b</a> and <a href="#a3b22297ce97b41b9ea8df1e9ec9d6d9a">XXH3_mergeAccs</a>.</p>

</div>
</div>

### XXH3\_hashLong\_128b() {#abfad913bbf7470e15bdfa2349f67a258}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">LLVM_ATTRIBUTE_ALWAYS_INLINE XXH128_hash_t XXH3_hashLong_128b (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> uint8_t * input, size_t len, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> uint8_t * secret, size_t secretSize)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 984 of file <a href="/web-llvm/docs/api/files/lib/lib/support/xxhash-cpp">xxhash.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/silowercontrolflow-cpp/#a4868c5d81c5ccc98c47aeab6244346a0">assert</a>, <a href="/web-llvm/docs/api/structs/llvm/xxh128-hash-t/#af6ae9edb7b299ab65fcbc7eca03b381a">llvm::XXH128_hash_t::high64</a>, <a href="/web-llvm/docs/api/structs/llvm/xxh128-hash-t/#a994e5b99d3dceafee44f8c983d75103b">llvm::XXH128_hash_t::low64</a>, <a href="#a6c0de75169f0f5ffd3d63059d77fa81c">PRIME32_1</a>, <a href="#a6db4d465a9f3c93ce1369c017071c9fb">PRIME32_2</a>, <a href="#a88fbf55eb4adbc5271b7340dc8b46992">PRIME32_3</a>, <a href="#a502e23a6442aeb2e9d55069d0f600e7e">PRIME64_1</a>, <a href="#a713d2b3b0b93699da8b5140e49ae0724">PRIME64_2</a>, <a href="#a26ec2310be052725d92271c3ce0ea530">PRIME64_3</a>, <a href="#a8faeab42c1df0e8e3113f802e6ee0fb7">PRIME64_4</a>, <a href="#aa89ac3cdaaa1e088d332977e864af1e2">PRIME64_5</a>, <a href="#a1e182c7dbecb63c4c47a78a965ec9909">XXH3_accumulate</a>, <a href="#a5ffe3391e408f75f726da56c67701f8f">XXH3_accumulate_512</a>, <a href="#a3b22297ce97b41b9ea8df1e9ec9d6d9a">XXH3_mergeAccs</a>, <a href="#a90fcb30d61f3d5fc00e56081205f4a30">XXH3_scrambleAcc</a>, <a href="#a9ea37a7b5fe9a6a0d4f8b268a3c3414f">XXH_ACC_NB</a>, <a href="#ae53fc54ef119c31f40b8656a76911afb">XXH_SECRET_CONSUME_RATE</a> and <a href="#a89842525985161520ed4732a91f716f6">XXH_STRIPE_LEN</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/namespaces/llvm/#a498db3edd7603cb3f985a6cde33c6827">llvm::xxh3_128bits</a>.</p>

</div>
</div>

### XXH3\_hashLong\_64b() {#a1a58a266c5393605d6eb9b9f26e3ab29}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">LLVM_ATTRIBUTE_NOINLINE uint64_t XXH3_hashLong_64b (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> uint8_t * input, size_t len, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> uint8_t * secret, size_t secretSize)</td>
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



<p>Definition at line 521 of file <a href="/web-llvm/docs/api/files/lib/lib/support/xxhash-cpp">xxhash.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/silowercontrolflow-cpp/#a4868c5d81c5ccc98c47aeab6244346a0">assert</a>, <a href="#a6c0de75169f0f5ffd3d63059d77fa81c">PRIME32_1</a>, <a href="#a6db4d465a9f3c93ce1369c017071c9fb">PRIME32_2</a>, <a href="#a88fbf55eb4adbc5271b7340dc8b46992">PRIME32_3</a>, <a href="#a502e23a6442aeb2e9d55069d0f600e7e">PRIME64_1</a>, <a href="#a713d2b3b0b93699da8b5140e49ae0724">PRIME64_2</a>, <a href="#a26ec2310be052725d92271c3ce0ea530">PRIME64_3</a>, <a href="#a8faeab42c1df0e8e3113f802e6ee0fb7">PRIME64_4</a>, <a href="#aa89ac3cdaaa1e088d332977e864af1e2">PRIME64_5</a>, <a href="#a1e182c7dbecb63c4c47a78a965ec9909">XXH3_accumulate</a>, <a href="#a5ffe3391e408f75f726da56c67701f8f">XXH3_accumulate_512</a>, <a href="#a3b22297ce97b41b9ea8df1e9ec9d6d9a">XXH3_mergeAccs</a>, <a href="#a90fcb30d61f3d5fc00e56081205f4a30">XXH3_scrambleAcc</a>, <a href="#a9ea37a7b5fe9a6a0d4f8b268a3c3414f">XXH_ACC_NB</a>, <a href="#ae53fc54ef119c31f40b8656a76911afb">XXH_SECRET_CONSUME_RATE</a> and <a href="#a89842525985161520ed4732a91f716f6">XXH_STRIPE_LEN</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/namespaces/llvm/#a23db35042db15bf83edbd2250ea0ee90">llvm::xxh3_64bits</a>.</p>

</div>
</div>

### XXH3\_len\_0to16\_128b() {#a6f213bbbdebd84c8536a43217f014dbc}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">LLVM_ATTRIBUTE_ALWAYS_INLINE XXH128_hash_t XXH3_len_0to16_128b (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> uint8_t * input, size_t len, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> uint8_t * secret, uint64_t seed)</td>
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



<p>Definition at line 878 of file <a href="/web-llvm/docs/api/files/lib/lib/support/xxhash-cpp">xxhash.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/structs/llvm/xxh128-hash-t/#af6ae9edb7b299ab65fcbc7eca03b381a">llvm::XXH128_hash_t::high64</a>, <a href="/web-llvm/docs/api/structs/llvm/xxh128-hash-t/#a994e5b99d3dceafee44f8c983d75103b">llvm::XXH128_hash_t::low64</a>, <a href="/web-llvm/docs/api/namespaces/llvm/support/endian/#a0fa2f859066acd16820ab083040158c9">llvm::support::endian::read64le</a>, <a href="#a1f9fe4a69b646dae9518d991adc12a00">XXH3_len_1to3_128b</a>, <a href="#a611ba08ac061c11dce0a30072099ba3c">XXH3_len_4to8_128b</a>, <a href="#a68128490131d65e06f6066616f80ddf5">XXH3_len_9to16_128b</a> and <a href="#acc6968c79b8da93dea87b708f2fe2734">XXH64_avalanche</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/namespaces/llvm/#a498db3edd7603cb3f985a6cde33c6827">llvm::xxh3_128bits</a>.</p>

</div>
</div>

### XXH3\_len\_0to16\_64b() {#adf1ca5feb6e370f2f2d4ceb328c927e6}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">LLVM_ATTRIBUTE_ALWAYS_INLINE uint64_t XXH3_len_0to16_64b (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> uint8_t * input, size_t len, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> uint8_t * secret, uint64_t <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> seed)</td>
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



<p>Definition at line 269 of file <a href="/web-llvm/docs/api/files/lib/lib/support/xxhash-cpp">xxhash.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/support/compiler-h/#ae5b35beb6f127e5f47269e9124b886fb">LLVM_LIKELY</a>, <a href="/web-llvm/docs/api/namespaces/llvm/support/endian/#a0fa2f859066acd16820ab083040158c9">llvm::support::endian::read64le</a>, <a href="#a25817408849438429707b1d7c48e5fcd">XXH3_len_1to3_64b</a>, <a href="#a14f60c710e7d2ab06a8211b0ba1e5306">XXH3_len_4to8_64b</a>, <a href="#a00cd136a7e5ebdb8f1920e7353349525">XXH3_len_9to16_64b</a> and <a href="#acc6968c79b8da93dea87b708f2fe2734">XXH64_avalanche</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/namespaces/llvm/#a23db35042db15bf83edbd2250ea0ee90">llvm::xxh3_64bits</a>.</p>

</div>
</div>

### XXH3\_len\_129to240\_128b() {#a67de1b04da6de33341dc7ffc6854fa9f}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">LLVM_ATTRIBUTE_NOINLINE XXH128_hash_t XXH3_len_129to240_128b (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> uint8_t * input, size_t len, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> uint8_t * secret, size_t secretSize, uint64_t seed)</td>
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



<p>Definition at line 939 of file <a href="/web-llvm/docs/api/files/lib/lib/support/xxhash-cpp">xxhash.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/structs/llvm/xxh128-hash-t/#af6ae9edb7b299ab65fcbc7eca03b381a">llvm::XXH128_hash_t::high64</a>, <a href="/web-llvm/docs/api/structs/llvm/xxh128-hash-t/#a994e5b99d3dceafee44f8c983d75103b">llvm::XXH128_hash_t::low64</a>, <a href="#a502e23a6442aeb2e9d55069d0f600e7e">PRIME64_1</a>, <a href="#a713d2b3b0b93699da8b5140e49ae0724">PRIME64_2</a>, <a href="#a8faeab42c1df0e8e3113f802e6ee0fb7">PRIME64_4</a>, <a href="#a2fa22ae762463bb383e63bd381952344">XXH128_mix32B</a>, <a href="#a5f41b833306622b3b79b209e3829bbb1">XXH3_avalanche</a>, <a href="#aff6d4d2c6782a3970af32558ac0d87a1">XXH3_MIDSIZE_LASTOFFSET</a>, <a href="#ade8a17ad42d2de81b0dbce47fd36618e">XXH3_MIDSIZE_STARTOFFSET</a> and <a href="#a664aa3b693f86bf4a82b7022a34defd3">XXH3_SECRETSIZE_MIN</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/namespaces/llvm/#a498db3edd7603cb3f985a6cde33c6827">llvm::xxh3_128bits</a>.</p>

</div>
</div>

### XXH3\_len\_129to240\_64b() {#a7c06bb47122eb6d599f8477e9781bd4c}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">LLVM_ATTRIBUTE_NOINLINE uint64_t XXH3_len_129to240_64b (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> uint8_t * input, size_t len, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> uint8_t * secret, uint64_t seed)</td>
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



<p>Definition at line 320 of file <a href="/web-llvm/docs/api/files/lib/lib/support/xxhash-cpp">xxhash.cpp</a>.</p>


<p>References <a href="#a502e23a6442aeb2e9d55069d0f600e7e">PRIME64_1</a>, <a href="#a5f41b833306622b3b79b209e3829bbb1">XXH3_avalanche</a>, <a href="#aff6d4d2c6782a3970af32558ac0d87a1">XXH3_MIDSIZE_LASTOFFSET</a>, <a href="#ade8a17ad42d2de81b0dbce47fd36618e">XXH3_MIDSIZE_STARTOFFSET</a>, <a href="#a3bdcfa0a87da5bece4e02edac5b0446f">XXH3_mix16B</a> and <a href="#a664aa3b693f86bf4a82b7022a34defd3">XXH3_SECRETSIZE_MIN</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/namespaces/llvm/#a23db35042db15bf83edbd2250ea0ee90">llvm::xxh3_64bits</a>.</p>

</div>
</div>

### XXH3\_len\_17to128\_128b() {#a43d708e6a6393ad5f59e3ade57f205d2}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">LLVM_ATTRIBUTE_ALWAYS_INLINE XXH128_hash_t XXH3_len_17to128_128b (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> uint8_t * input, size_t len, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> uint8_t * secret, size_t secretSize, uint64_t seed)</td>
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



<p>Definition at line 910 of file <a href="/web-llvm/docs/api/files/lib/lib/support/xxhash-cpp">xxhash.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/structs/llvm/xxh128-hash-t/#af6ae9edb7b299ab65fcbc7eca03b381a">llvm::XXH128_hash_t::high64</a>, <a href="/web-llvm/docs/api/structs/llvm/xxh128-hash-t/#a994e5b99d3dceafee44f8c983d75103b">llvm::XXH128_hash_t::low64</a>, <a href="#a502e23a6442aeb2e9d55069d0f600e7e">PRIME64_1</a>, <a href="#a713d2b3b0b93699da8b5140e49ae0724">PRIME64_2</a>, <a href="#a8faeab42c1df0e8e3113f802e6ee0fb7">PRIME64_4</a>, <a href="#a2fa22ae762463bb383e63bd381952344">XXH128_mix32B</a> and <a href="#a5f41b833306622b3b79b209e3829bbb1">XXH3_avalanche</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/namespaces/llvm/#a498db3edd7603cb3f985a6cde33c6827">llvm::xxh3_128bits</a>.</p>

</div>
</div>

### XXH3\_len\_17to128\_64b() {#a7b1955f2dfac4943d24dd55944b86062}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">LLVM_ATTRIBUTE_ALWAYS_INLINE uint64_t XXH3_len_17to128_64b (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> uint8_t * input, size_t len, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> uint8_t * secret, uint64_t <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> seed)</td>
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



<p>Definition at line 294 of file <a href="/web-llvm/docs/api/files/lib/lib/support/xxhash-cpp">xxhash.cpp</a>.</p>


<p>References <a href="#a502e23a6442aeb2e9d55069d0f600e7e">PRIME64_1</a>, <a href="#a5f41b833306622b3b79b209e3829bbb1">XXH3_avalanche</a> and <a href="#a3bdcfa0a87da5bece4e02edac5b0446f">XXH3_mix16B</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/namespaces/llvm/#a23db35042db15bf83edbd2250ea0ee90">llvm::xxh3_64bits</a>.</p>

</div>
</div>

### XXH3\_len\_1to3\_128b() {#a1f9fe4a69b646dae9518d991adc12a00}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">LLVM_ATTRIBUTE_ALWAYS_INLINE XXH128_hash_t XXH3_len_1to3_128b (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> uint8_t * input, size_t len, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> uint8_t * secret, uint64_t seed)</td>
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



<p>Definition at line 750 of file <a href="/web-llvm/docs/api/files/lib/lib/support/xxhash-cpp">xxhash.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/namespaces/llvm/#a2a584ab307c8e962527df226089a7470">llvm::byteswap</a>, <a href="/web-llvm/docs/api/structs/llvm/xxh128-hash-t/#af6ae9edb7b299ab65fcbc7eca03b381a">llvm::XXH128_hash_t::high64</a>, <a href="/web-llvm/docs/api/structs/llvm/xxh128-hash-t/#a994e5b99d3dceafee44f8c983d75103b">llvm::XXH128_hash_t::low64</a>, <a href="/web-llvm/docs/api/namespaces/llvm/support/endian/#ae865d5defb8785b365f342375822beaa">llvm::support::endian::read32le</a>, <a href="#acc6968c79b8da93dea87b708f2fe2734">XXH64_avalanche</a> and <a href="#a70a4b202f9523a2a811da16cde3f52eb">XXH_rotl32</a>.</p>


<p>Referenced by <a href="#a6f213bbbdebd84c8536a43217f014dbc">XXH3_len_0to16_128b</a>.</p>

</div>
</div>

### XXH3\_len\_1to3\_64b() {#a25817408849438429707b1d7c48e5fcd}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">uint64_t XXH3_len_1to3_64b (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> uint8_t * input, size_t len, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> uint8_t * secret, uint64_t seed)</td>
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



<p>Definition at line 225 of file <a href="/web-llvm/docs/api/files/lib/lib/support/xxhash-cpp">xxhash.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/namespaces/llvm/support/endian/#ae865d5defb8785b365f342375822beaa">llvm::support::endian::read32le</a> and <a href="#acc6968c79b8da93dea87b708f2fe2734">XXH64_avalanche</a>.</p>


<p>Referenced by <a href="#adf1ca5feb6e370f2f2d4ceb328c927e6">XXH3_len_0to16_64b</a>.</p>

</div>
</div>

### XXH3\_len\_4to8\_128b() {#a611ba08ac061c11dce0a30072099ba3c}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">LLVM_ATTRIBUTE_ALWAYS_INLINE XXH128_hash_t XXH3_len_4to8_128b (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> uint8_t * input, size_t len, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> uint8_t * secret, uint64_t seed)</td>
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



<p>Definition at line 777 of file <a href="/web-llvm/docs/api/files/lib/lib/support/xxhash-cpp">xxhash.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/namespaces/llvm/#a2a584ab307c8e962527df226089a7470">llvm::byteswap</a>, <a href="/web-llvm/docs/api/structs/llvm/xxh128-hash-t/#af6ae9edb7b299ab65fcbc7eca03b381a">llvm::XXH128_hash_t::high64</a>, <a href="/web-llvm/docs/api/structs/llvm/xxh128-hash-t/#a994e5b99d3dceafee44f8c983d75103b">llvm::XXH128_hash_t::low64</a>, <a href="#a502e23a6442aeb2e9d55069d0f600e7e">PRIME64_1</a>, <a href="#af96c90d6eedd426a1e2213b4f9fbbc27">PRIME_MX2</a>, <a href="/web-llvm/docs/api/namespaces/llvm/support/endian/#ae865d5defb8785b365f342375822beaa">llvm::support::endian::read32le</a>, <a href="/web-llvm/docs/api/namespaces/llvm/support/endian/#a0fa2f859066acd16820ab083040158c9">llvm::support::endian::read64le</a>, <a href="#a5f41b833306622b3b79b209e3829bbb1">XXH3_avalanche</a>, <a href="#a5a010401dcddb43e0a6fdcac9564d69b">XXH_mult64to128</a> and <a href="#aace3bad147eeed78a2f1cab33d506d59">XXH_xorshift64</a>.</p>


<p>Referenced by <a href="#a6f213bbbdebd84c8536a43217f014dbc">XXH3_len_0to16_128b</a>.</p>

</div>
</div>

### XXH3\_len\_4to8\_64b() {#a14f60c710e7d2ab06a8211b0ba1e5306}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">uint64_t XXH3_len_4to8_64b (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> uint8_t * input, size_t len, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> uint8_t * secret, uint64_t seed)</td>
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



<p>Definition at line 238 of file <a href="/web-llvm/docs/api/files/lib/lib/support/xxhash-cpp">xxhash.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/namespaces/llvm/#a2a584ab307c8e962527df226089a7470">llvm::byteswap</a>, <a href="#af96c90d6eedd426a1e2213b4f9fbbc27">PRIME_MX2</a>, <a href="/web-llvm/docs/api/namespaces/llvm/support/endian/#ae865d5defb8785b365f342375822beaa">llvm::support::endian::read32le</a>, <a href="/web-llvm/docs/api/namespaces/llvm/support/endian/#a0fa2f859066acd16820ab083040158c9">llvm::support::endian::read64le</a> and <a href="#abfb1fc3e8788d6965f172f6f0d1f9e04">rotl64</a>.</p>


<p>Referenced by <a href="#adf1ca5feb6e370f2f2d4ceb328c927e6">XXH3_len_0to16_64b</a>.</p>

</div>
</div>

### XXH3\_len\_9to16\_128b() {#a68128490131d65e06f6066616f80ddf5}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">LLVM_ATTRIBUTE_ALWAYS_INLINE XXH128_hash_t XXH3_len_9to16_128b (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> uint8_t * input, size_t len, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> uint8_t * secret, uint64_t seed)</td>
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



<p>Definition at line 802 of file <a href="/web-llvm/docs/api/files/lib/lib/support/xxhash-cpp">xxhash.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/namespaces/llvm/#a2a584ab307c8e962527df226089a7470">llvm::byteswap</a>, <a href="/web-llvm/docs/api/structs/llvm/xxh128-hash-t/#af6ae9edb7b299ab65fcbc7eca03b381a">llvm::XXH128_hash_t::high64</a>, <a href="/web-llvm/docs/api/structs/llvm/xxh128-hash-t/#a994e5b99d3dceafee44f8c983d75103b">llvm::XXH128_hash_t::low64</a>, <a href="#a6db4d465a9f3c93ce1369c017071c9fb">PRIME32_2</a>, <a href="#a502e23a6442aeb2e9d55069d0f600e7e">PRIME64_1</a>, <a href="#a713d2b3b0b93699da8b5140e49ae0724">PRIME64_2</a>, <a href="/web-llvm/docs/api/namespaces/llvm/support/endian/#a0fa2f859066acd16820ab083040158c9">llvm::support::endian::read64le</a>, <a href="#a5f41b833306622b3b79b209e3829bbb1">XXH3_avalanche</a>, <a href="#a08f3f09f1c097e41499563c7468d031c">XXH_mult32to64</a> and <a href="#a5a010401dcddb43e0a6fdcac9564d69b">XXH_mult64to128</a>.</p>


<p>Referenced by <a href="#a6f213bbbdebd84c8536a43217f014dbc">XXH3_len_0to16_128b</a>.</p>

</div>
</div>

### XXH3\_len\_9to16\_64b() {#a00cd136a7e5ebdb8f1920e7353349525}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">uint64_t XXH3_len_9to16_64b (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> uint8_t * input, size_t len, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> uint8_t * secret, uint64_t <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> seed)</td>
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



<p>Definition at line 255 of file <a href="/web-llvm/docs/api/files/lib/lib/support/xxhash-cpp">xxhash.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/namespaces/llvm/#a2a584ab307c8e962527df226089a7470">llvm::byteswap</a>, <a href="/web-llvm/docs/api/namespaces/llvm/support/endian/#a0fa2f859066acd16820ab083040158c9">llvm::support::endian::read64le</a>, <a href="#a5f41b833306622b3b79b209e3829bbb1">XXH3_avalanche</a> and <a href="#ae07c124bf50a0ad869649d3e1d0def90">XXH3_mul128_fold64</a>.</p>


<p>Referenced by <a href="#adf1ca5feb6e370f2f2d4ceb328c927e6">XXH3_len_0to16_64b</a>.</p>

</div>
</div>

### XXH3\_mergeAccs() {#a3b22297ce97b41b9ea8df1e9ec9d6d9a}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">uint64_t XXH3_mergeAccs (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> uint64_t * acc, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> uint8_t * key, uint64_t start)</td>
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



<p>Definition at line 512 of file <a href="/web-llvm/docs/api/files/lib/lib/support/xxhash-cpp">xxhash.cpp</a>.</p>


<p>References <a href="#a5f41b833306622b3b79b209e3829bbb1">XXH3_avalanche</a> and <a href="#add6dbf56c8f88ad835ce0c76e4fa3acc">XXH3_mix2Accs</a>.</p>


<p>Referenced by <a href="#abfad913bbf7470e15bdfa2349f67a258">XXH3_hashLong_128b</a> and <a href="#a1a58a266c5393605d6eb9b9f26e3ab29">XXH3_hashLong_64b</a>.</p>

</div>
</div>

### XXH3\_mix16B() {#a3bdcfa0a87da5bece4e02edac5b0446f}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">uint64_t XXH3_mix16B (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> uint8_t * input, uint8_t <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> * secret, uint64_t seed)</td>
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



<p>Definition at line 281 of file <a href="/web-llvm/docs/api/files/lib/lib/support/xxhash-cpp">xxhash.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/namespaces/llvm/support/endian/#a0fa2f859066acd16820ab083040158c9">llvm::support::endian::read64le</a> and <a href="#ae07c124bf50a0ad869649d3e1d0def90">XXH3_mul128_fold64</a>.</p>


<p>Referenced by <a href="#a2fa22ae762463bb383e63bd381952344">XXH128_mix32B</a>, <a href="#a7c06bb47122eb6d599f8477e9781bd4c">XXH3_len_129to240_64b</a> and <a href="#a7b1955f2dfac4943d24dd55944b86062">XXH3_len_17to128_64b</a>.</p>

</div>
</div>

### XXH3\_mix2Accs() {#add6dbf56c8f88ad835ce0c76e4fa3acc}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">uint64_t XXH3_mix2Accs (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> uint64_t * acc, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> uint8_t * secret)</td>
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



<p>Definition at line 507 of file <a href="/web-llvm/docs/api/files/lib/lib/support/xxhash-cpp">xxhash.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/namespaces/llvm/support/endian/#a0fa2f859066acd16820ab083040158c9">llvm::support::endian::read64le</a> and <a href="#ae07c124bf50a0ad869649d3e1d0def90">XXH3_mul128_fold64</a>.</p>


<p>Referenced by <a href="#a3b22297ce97b41b9ea8df1e9ec9d6d9a">XXH3_mergeAccs</a>.</p>

</div>
</div>

### XXH3\_mul128\_fold64() {#ae07c124bf50a0ad869649d3e1d0def90}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">uint64_t XXH3_mul128_fold64 (uint64_t lhs, uint64_t rhs)</td>
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



<p>Definition at line 192 of file <a href="/web-llvm/docs/api/files/lib/lib/support/xxhash-cpp">xxhash.cpp</a>.</p>


<p>Referenced by <a href="#a00cd136a7e5ebdb8f1920e7353349525">XXH3_len_9to16_64b</a>, <a href="#a3bdcfa0a87da5bece4e02edac5b0446f">XXH3_mix16B</a> and <a href="#add6dbf56c8f88ad835ce0c76e4fa3acc">XXH3_mix2Accs</a>.</p>

</div>
</div>

### XXH3\_scrambleAcc\_scalar() {#ad36d7562c24a3eed4705f092dd82ca23}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">LLVM_ATTRIBUTE_ALWAYS_INLINE void XXH3_scrambleAcc_scalar (uint64_t * acc, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> uint8_t * secret)</td>
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



<p>Definition at line 489 of file <a href="/web-llvm/docs/api/files/lib/lib/support/xxhash-cpp">xxhash.cpp</a>.</p>


<p>References <a href="#a6c0de75169f0f5ffd3d63059d77fa81c">PRIME32_1</a>, <a href="/web-llvm/docs/api/namespaces/llvm/support/endian/#a0fa2f859066acd16820ab083040158c9">llvm::support::endian::read64le</a> and <a href="#a9ea37a7b5fe9a6a0d4f8b268a3c3414f">XXH_ACC_NB</a>.</p>

</div>
</div>

### XXH64\_avalanche() {#acc6968c79b8da93dea87b708f2fe2734}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">uint64_t XXH64_avalanche (uint64_t hash)</td>
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



<p>Definition at line 94 of file <a href="/web-llvm/docs/api/files/lib/lib/support/xxhash-cpp">xxhash.cpp</a>.</p>


<p>References <a href="#a713d2b3b0b93699da8b5140e49ae0724">PRIME64_2</a> and <a href="#a26ec2310be052725d92271c3ce0ea530">PRIME64_3</a>.</p>


<p>Referenced by <a href="#a6f213bbbdebd84c8536a43217f014dbc">XXH3_len_0to16_128b</a>, <a href="#adf1ca5feb6e370f2f2d4ceb328c927e6">XXH3_len_0to16_64b</a>, <a href="#a1f9fe4a69b646dae9518d991adc12a00">XXH3_len_1to3_128b</a>, <a href="#a25817408849438429707b1d7c48e5fcd">XXH3_len_1to3_64b</a> and <a href="/web-llvm/docs/api/namespaces/llvm/#afd78f9f642d72c07d9082f228a6389db">llvm::xxHash64</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Variables

### kSecret {#a789b8647bf303ff177d153fb36e07083}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">uint8_t kSecret[XXH_SECRET_DEFAULT_SIZE]</td>
</tr>
</table>
</td>
<td class="doxyMemberLabelsRight">
<span class="doxyMemberLabels">
<span class="doxyMemberLabel constexpr">constexpr</span>
</span>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<dl class="doxySectionUser">
<dt>Initialiser</dt>
<dd>
<div class="doxyVerbatim">= {
    0xb8, 0xfe, 0x6c, 0x39, 0x23, 0xa4, 0x4b, 0xbe, 0x7c, 0x01, 0x81, 0x2c, 0xf7, 0x21, 0xad, 0x1c,
    0xde, 0xd4, 0x6d, 0xe9, 0x83, 0x90, 0x97, 0xdb, 0x72, 0x40, 0xa4, 0xa4, 0xb7, 0xb3, 0x67, 0x1f,
    0xcb, 0x79, 0xe6, 0x4e, 0xcc, 0xc0, 0xe5, 0x78, 0x82, 0x5a, 0xd0, 0x7d, 0xcc, 0xff, 0x72, 0x21,
    0xb8, 0x08, 0x46, 0x74, 0xf7, 0x43, 0x24, 0x8e, 0xe0, 0x35, 0x90, 0xe6, 0x81, 0x3a, 0x26, 0x4c,
    0x3c, 0x28, 0x52, 0xbb, 0x91, 0xc3, 0x00, 0xcb, 0x88, 0xd0, 0x65, 0x8b, 0x1b, 0x53, 0x2e, 0xa3,
    0x71, 0x64, 0x48, 0x97, 0xa2, 0x0d, 0xf9, 0x4e, 0x38, 0x19, 0xef, 0x46, 0xa9, 0xde, 0xac, 0xd8,
    0xa8, 0xfa, 0x76, 0x3f, 0xe3, 0x9c, 0x34, 0x3f, 0xf9, 0xdc, 0xbb, 0xc7, 0xc7, 0x0b, 0x4f, 0x1d,
    0x8a, 0x51, 0xe0, 0x4b, 0xcd, 0xb4, 0x59, 0x31, 0xc8, 0x9f, 0x7e, 0xc9, 0xd9, 0x78, 0x73, 0x64,
    0xea, 0xc5, 0xac, 0x83, 0x34, 0xd3, 0xeb, 0xc3, 0xc5, 0x81, 0xa0, 0xff, 0xfa, 0x13, 0x63, 0xeb,
    0x17, 0x0d, 0xdd, 0x51, 0xb7, 0xf0, 0xda, 0x49, 0xd3, 0x16, 0x55, 0x26, 0x29, 0xd4, 0x68, 0x9e,
    0x2b, 0x16, 0xbe, 0x58, 0x7d, 0x47, 0xa1, 0xfc, 0x8f, 0xf8, 0xb8, 0xd1, 0x7a, 0xd0, 0x31, 0xce,
    0x45, 0xcb, 0x3a, 0x8f, 0x95, 0x16, 0x04, 0x28, 0xaf, 0xd7, 0xfb, 0xca, 0xbb, 0x4b, 0x40, 0x7e,
}
</div>
</dd>
</dl>

<p>Definition at line 172 of file <a href="/web-llvm/docs/api/files/lib/lib/support/xxhash-cpp">xxhash.cpp</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/namespaces/llvm/#a498db3edd7603cb3f985a6cde33c6827">llvm::xxh3_128bits</a> and <a href="/web-llvm/docs/api/namespaces/llvm/#a23db35042db15bf83edbd2250ea0ee90">llvm::xxh3_64bits</a>.</p>

</div>
</div>

### PRIME\_MX1 {#ad941dff9ebd5cdcb0211a1a1cf4360a1}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">uint64_t PRIME_MX1 = 0x165667919E3779F9</td>
</tr>
</table>
</td>
<td class="doxyMemberLabelsRight">
<span class="doxyMemberLabels">
<span class="doxyMemberLabel constexpr">constexpr</span>
</span>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 188 of file <a href="/web-llvm/docs/api/files/lib/lib/support/xxhash-cpp">xxhash.cpp</a>.</p>


<p>Referenced by <a href="#a5f41b833306622b3b79b209e3829bbb1">XXH3_avalanche</a>.</p>

</div>
</div>

### PRIME\_MX2 {#af96c90d6eedd426a1e2213b4f9fbbc27}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">uint64_t PRIME_MX2 = 0x9FB21C651E98DF25</td>
</tr>
</table>
</td>
<td class="doxyMemberLabelsRight">
<span class="doxyMemberLabels">
<span class="doxyMemberLabel constexpr">constexpr</span>
</span>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 189 of file <a href="/web-llvm/docs/api/files/lib/lib/support/xxhash-cpp">xxhash.cpp</a>.</p>


<p>Referenced by <a href="#a611ba08ac061c11dce0a30072099ba3c">XXH3_len_4to8_128b</a> and <a href="#a14f60c710e7d2ab06a8211b0ba1e5306">XXH3_len_4to8_64b</a>.</p>

</div>
</div>

### PRIME32\_1 {#a6c0de75169f0f5ffd3d63059d77fa81c}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">uint32_t PRIME32_1 = 0x9E3779B1</td>
</tr>
</table>
</td>
<td class="doxyMemberLabelsRight">
<span class="doxyMemberLabels">
<span class="doxyMemberLabel constexpr">constexpr</span>
</span>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 70 of file <a href="/web-llvm/docs/api/files/lib/lib/support/xxhash-cpp">xxhash.cpp</a>.</p>


<p>Referenced by <a href="#abfad913bbf7470e15bdfa2349f67a258">XXH3_hashLong_128b</a>, <a href="#a1a58a266c5393605d6eb9b9f26e3ab29">XXH3_hashLong_64b</a> and <a href="#ad36d7562c24a3eed4705f092dd82ca23">XXH3_scrambleAcc_scalar</a>.</p>

</div>
</div>

### PRIME32\_2 {#a6db4d465a9f3c93ce1369c017071c9fb}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">uint32_t PRIME32_2 = 0x85EBCA77</td>
</tr>
</table>
</td>
<td class="doxyMemberLabelsRight">
<span class="doxyMemberLabels">
<span class="doxyMemberLabel constexpr">constexpr</span>
</span>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 71 of file <a href="/web-llvm/docs/api/files/lib/lib/support/xxhash-cpp">xxhash.cpp</a>.</p>


<p>Referenced by <a href="#abfad913bbf7470e15bdfa2349f67a258">XXH3_hashLong_128b</a>, <a href="#a1a58a266c5393605d6eb9b9f26e3ab29">XXH3_hashLong_64b</a> and <a href="#a68128490131d65e06f6066616f80ddf5">XXH3_len_9to16_128b</a>.</p>

</div>
</div>

### PRIME32\_3 {#a88fbf55eb4adbc5271b7340dc8b46992}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">uint32_t PRIME32_3 = 0xC2B2AE3D</td>
</tr>
</table>
</td>
<td class="doxyMemberLabelsRight">
<span class="doxyMemberLabels">
<span class="doxyMemberLabel constexpr">constexpr</span>
</span>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 72 of file <a href="/web-llvm/docs/api/files/lib/lib/support/xxhash-cpp">xxhash.cpp</a>.</p>


<p>Referenced by <a href="#abfad913bbf7470e15bdfa2349f67a258">XXH3_hashLong_128b</a> and <a href="#a1a58a266c5393605d6eb9b9f26e3ab29">XXH3_hashLong_64b</a>.</p>

</div>
</div>

### PRIME64\_1 {#a502e23a6442aeb2e9d55069d0f600e7e}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">const uint64_t PRIME64_1 = 11400714785074694791ULL</td>
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



<p>Definition at line 74 of file <a href="/web-llvm/docs/api/files/lib/lib/support/xxhash-cpp">xxhash.cpp</a>.</p>


<p>Referenced by <a href="#a0822bb275b7fdd5cf225585e27c59631">mergeRound</a>, <a href="#ae4e947c75dafebd71b8de03cd0dbf5d6">round</a>, <a href="#abfad913bbf7470e15bdfa2349f67a258">XXH3_hashLong_128b</a>, <a href="#a1a58a266c5393605d6eb9b9f26e3ab29">XXH3_hashLong_64b</a>, <a href="#a67de1b04da6de33341dc7ffc6854fa9f">XXH3_len_129to240_128b</a>, <a href="#a7c06bb47122eb6d599f8477e9781bd4c">XXH3_len_129to240_64b</a>, <a href="#a43d708e6a6393ad5f59e3ade57f205d2">XXH3_len_17to128_128b</a>, <a href="#a7b1955f2dfac4943d24dd55944b86062">XXH3_len_17to128_64b</a>, <a href="#a611ba08ac061c11dce0a30072099ba3c">XXH3_len_4to8_128b</a>, <a href="#a68128490131d65e06f6066616f80ddf5">XXH3_len_9to16_128b</a> and <a href="/web-llvm/docs/api/namespaces/llvm/#afd78f9f642d72c07d9082f228a6389db">llvm::xxHash64</a>.</p>

</div>
</div>

### PRIME64\_2 {#a713d2b3b0b93699da8b5140e49ae0724}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">const uint64_t PRIME64_2 = 14029467366897019727ULL</td>
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



<p>Definition at line 75 of file <a href="/web-llvm/docs/api/files/lib/lib/support/xxhash-cpp">xxhash.cpp</a>.</p>


<p>Referenced by <a href="#ae4e947c75dafebd71b8de03cd0dbf5d6">round</a>, <a href="#abfad913bbf7470e15bdfa2349f67a258">XXH3_hashLong_128b</a>, <a href="#a1a58a266c5393605d6eb9b9f26e3ab29">XXH3_hashLong_64b</a>, <a href="#a67de1b04da6de33341dc7ffc6854fa9f">XXH3_len_129to240_128b</a>, <a href="#a43d708e6a6393ad5f59e3ade57f205d2">XXH3_len_17to128_128b</a>, <a href="#a68128490131d65e06f6066616f80ddf5">XXH3_len_9to16_128b</a>, <a href="#acc6968c79b8da93dea87b708f2fe2734">XXH64_avalanche</a> and <a href="/web-llvm/docs/api/namespaces/llvm/#afd78f9f642d72c07d9082f228a6389db">llvm::xxHash64</a>.</p>

</div>
</div>

### PRIME64\_3 {#a26ec2310be052725d92271c3ce0ea530}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">const uint64_t PRIME64_3 = 1609587929392839161ULL</td>
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



<p>Definition at line 76 of file <a href="/web-llvm/docs/api/files/lib/lib/support/xxhash-cpp">xxhash.cpp</a>.</p>


<p>Referenced by <a href="#abfad913bbf7470e15bdfa2349f67a258">XXH3_hashLong_128b</a>, <a href="#a1a58a266c5393605d6eb9b9f26e3ab29">XXH3_hashLong_64b</a>, <a href="#acc6968c79b8da93dea87b708f2fe2734">XXH64_avalanche</a> and <a href="/web-llvm/docs/api/namespaces/llvm/#afd78f9f642d72c07d9082f228a6389db">llvm::xxHash64</a>.</p>

</div>
</div>

### PRIME64\_4 {#a8faeab42c1df0e8e3113f802e6ee0fb7}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">const uint64_t PRIME64_4 = 9650029242287828579ULL</td>
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



<p>Definition at line 77 of file <a href="/web-llvm/docs/api/files/lib/lib/support/xxhash-cpp">xxhash.cpp</a>.</p>


<p>Referenced by <a href="#a0822bb275b7fdd5cf225585e27c59631">mergeRound</a>, <a href="#abfad913bbf7470e15bdfa2349f67a258">XXH3_hashLong_128b</a>, <a href="#a1a58a266c5393605d6eb9b9f26e3ab29">XXH3_hashLong_64b</a>, <a href="#a67de1b04da6de33341dc7ffc6854fa9f">XXH3_len_129to240_128b</a>, <a href="#a43d708e6a6393ad5f59e3ade57f205d2">XXH3_len_17to128_128b</a> and <a href="/web-llvm/docs/api/namespaces/llvm/#afd78f9f642d72c07d9082f228a6389db">llvm::xxHash64</a>.</p>

</div>
</div>

### PRIME64\_5 {#aa89ac3cdaaa1e088d332977e864af1e2}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">const uint64_t PRIME64_5 = 2870177450012600261ULL</td>
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



<p>Definition at line 78 of file <a href="/web-llvm/docs/api/files/lib/lib/support/xxhash-cpp">xxhash.cpp</a>.</p>


<p>Referenced by <a href="#abfad913bbf7470e15bdfa2349f67a258">XXH3_hashLong_128b</a>, <a href="#a1a58a266c5393605d6eb9b9f26e3ab29">XXH3_hashLong_64b</a> and <a href="/web-llvm/docs/api/namespaces/llvm/#afd78f9f642d72c07d9082f228a6389db">llvm::xxHash64</a>.</p>

</div>
</div>

### XXH\_ACC\_NB {#a9ea37a7b5fe9a6a0d4f8b268a3c3414f}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">size_t XXH_ACC_NB = <a href="#a89842525985161520ed4732a91f716f6">XXH_STRIPE_LEN</a> / sizeof(uint64_t)</td>
</tr>
</table>
</td>
<td class="doxyMemberLabelsRight">
<span class="doxyMemberLabels">
<span class="doxyMemberLabel constexpr">constexpr</span>
</span>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 216 of file <a href="/web-llvm/docs/api/files/lib/lib/support/xxhash-cpp">xxhash.cpp</a>.</p>


<p>Referenced by <a href="#adc9c81b2946609f0260dabe87fea8821">XXH3_accumulate_512_scalar</a>, <a href="#abfad913bbf7470e15bdfa2349f67a258">XXH3_hashLong_128b</a>, <a href="#a1a58a266c5393605d6eb9b9f26e3ab29">XXH3_hashLong_64b</a> and <a href="#ad36d7562c24a3eed4705f092dd82ca23">XXH3_scrambleAcc_scalar</a>.</p>

</div>
</div>

### XXH\_SECRET\_CONSUME\_RATE {#ae53fc54ef119c31f40b8656a76911afb}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">size_t XXH_SECRET_CONSUME_RATE = 8</td>
</tr>
</table>
</td>
<td class="doxyMemberLabelsRight">
<span class="doxyMemberLabels">
<span class="doxyMemberLabel constexpr">constexpr</span>
</span>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 215 of file <a href="/web-llvm/docs/api/files/lib/lib/support/xxhash-cpp">xxhash.cpp</a>.</p>


<p>Referenced by <a href="#a1e182c7dbecb63c4c47a78a965ec9909">XXH3_accumulate</a>, <a href="#abfad913bbf7470e15bdfa2349f67a258">XXH3_hashLong_128b</a> and <a href="#a1a58a266c5393605d6eb9b9f26e3ab29">XXH3_hashLong_64b</a>.</p>

</div>
</div>

### XXH\_SECRET\_DEFAULT\_SIZE {#ad54096aad01dc78abb39fcc6af421abf}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">size_t XXH_SECRET_DEFAULT_SIZE = 192</td>
</tr>
</table>
</td>
<td class="doxyMemberLabelsRight">
<span class="doxyMemberLabels">
<span class="doxyMemberLabel constexpr">constexpr</span>
</span>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 168 of file <a href="/web-llvm/docs/api/files/lib/lib/support/xxhash-cpp">xxhash.cpp</a>.</p>

</div>
</div>

### XXH\_STRIPE\_LEN {#a89842525985161520ed4732a91f716f6}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">size_t XXH_STRIPE_LEN = 64</td>
</tr>
</table>
</td>
<td class="doxyMemberLabelsRight">
<span class="doxyMemberLabels">
<span class="doxyMemberLabel constexpr">constexpr</span>
</span>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 214 of file <a href="/web-llvm/docs/api/files/lib/lib/support/xxhash-cpp">xxhash.cpp</a>.</p>


<p>Referenced by <a href="#a1e182c7dbecb63c4c47a78a965ec9909">XXH3_accumulate</a>, <a href="#abfad913bbf7470e15bdfa2349f67a258">XXH3_hashLong_128b</a> and <a href="#a1a58a266c5393605d6eb9b9f26e3ab29">XXH3_hashLong_64b</a>.</p>

</div>
</div>

### XXH3\_MIDSIZE\_LASTOFFSET {#aff6d4d2c6782a3970af32558ac0d87a1}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">size_t XXH3_MIDSIZE_LASTOFFSET = 17</td>
</tr>
</table>
</td>
<td class="doxyMemberLabelsRight">
<span class="doxyMemberLabels">
<span class="doxyMemberLabel constexpr">constexpr</span>
</span>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 317 of file <a href="/web-llvm/docs/api/files/lib/lib/support/xxhash-cpp">xxhash.cpp</a>.</p>


<p>Referenced by <a href="#a67de1b04da6de33341dc7ffc6854fa9f">XXH3_len_129to240_128b</a> and <a href="#a7c06bb47122eb6d599f8477e9781bd4c">XXH3_len_129to240_64b</a>.</p>

</div>
</div>

### XXH3\_MIDSIZE\_MAX {#a76cb2d6f9c4fc976d85ff8ed764b3c93}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">size_t XXH3_MIDSIZE_MAX = 240</td>
</tr>
</table>
</td>
<td class="doxyMemberLabelsRight">
<span class="doxyMemberLabels">
<span class="doxyMemberLabel constexpr">constexpr</span>
</span>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 315 of file <a href="/web-llvm/docs/api/files/lib/lib/support/xxhash-cpp">xxhash.cpp</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/namespaces/llvm/#a498db3edd7603cb3f985a6cde33c6827">llvm::xxh3_128bits</a> and <a href="/web-llvm/docs/api/namespaces/llvm/#a23db35042db15bf83edbd2250ea0ee90">llvm::xxh3_64bits</a>.</p>

</div>
</div>

### XXH3\_MIDSIZE\_STARTOFFSET {#ade8a17ad42d2de81b0dbce47fd36618e}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">size_t XXH3_MIDSIZE_STARTOFFSET = 3</td>
</tr>
</table>
</td>
<td class="doxyMemberLabelsRight">
<span class="doxyMemberLabels">
<span class="doxyMemberLabel constexpr">constexpr</span>
</span>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 316 of file <a href="/web-llvm/docs/api/files/lib/lib/support/xxhash-cpp">xxhash.cpp</a>.</p>


<p>Referenced by <a href="#a67de1b04da6de33341dc7ffc6854fa9f">XXH3_len_129to240_128b</a> and <a href="#a7c06bb47122eb6d599f8477e9781bd4c">XXH3_len_129to240_64b</a>.</p>

</div>
</div>

### XXH3\_SECRETSIZE\_MIN {#a664aa3b693f86bf4a82b7022a34defd3}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">size_t XXH3_SECRETSIZE_MIN = 136</td>
</tr>
</table>
</td>
<td class="doxyMemberLabelsRight">
<span class="doxyMemberLabels">
<span class="doxyMemberLabel constexpr">constexpr</span>
</span>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 167 of file <a href="/web-llvm/docs/api/files/lib/lib/support/xxhash-cpp">xxhash.cpp</a>.</p>


<p>Referenced by <a href="#a67de1b04da6de33341dc7ffc6854fa9f">XXH3_len_129to240_128b</a> and <a href="#a7c06bb47122eb6d599f8477e9781bd4c">XXH3_len_129to240_64b</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Macro Definitions

### LLVM\_XXH\_USE\_NEON {#a14e0090d82a5322599d194a2348986c9}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">#define LLVM_XXH_USE_NEON&nbsp;&nbsp;&nbsp;0</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 55 of file <a href="/web-llvm/docs/api/files/lib/lib/support/xxhash-cpp">xxhash.cpp</a>.</p>

</div>
</div>

### XXH\_mult32to64 {#a08f3f09f1c097e41499563c7468d031c}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">#define XXH_mult32to64(x, y)&nbsp;&nbsp;&nbsp;((uint64_t)(uint32_t)(x) * (uint64_t)(uint32_t)(y))</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 609 of file <a href="/web-llvm/docs/api/files/lib/lib/support/xxhash-cpp">xxhash.cpp</a>.</p>


<p>Referenced by <a href="#a68128490131d65e06f6066616f80ddf5">XXH3_len_9to16_128b</a> and <a href="#a5a010401dcddb43e0a6fdcac9564d69b">XXH_mult64to128</a>.</p>

</div>
</div>

### XXH\_rotl32 {#a70a4b202f9523a2a811da16cde3f52eb}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">#define XXH_rotl32(x, r)&nbsp;&nbsp;&nbsp;(((x) &lt;&lt; (r)) | ((x) &gt;&gt; (32 - (r))))</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 605 of file <a href="/web-llvm/docs/api/files/lib/lib/support/xxhash-cpp">xxhash.cpp</a>.</p>


<p>Referenced by <a href="#a1f9fe4a69b646dae9518d991adc12a00">XXH3_len_1to3_128b</a>.</p>

</div>
</div>

### XXH\_rotl64 {#a056473e50ab5e7acb43d00ca3d41632e}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">#define XXH_rotl64(x, r)&nbsp;&nbsp;&nbsp;(((x) &lt;&lt; (r)) | ((x) &gt;&gt; (64 - (r))))</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 606 of file <a href="/web-llvm/docs/api/files/lib/lib/support/xxhash-cpp">xxhash.cpp</a>.</p>

</div>
</div>

### XXH3\_accumulate\_512 {#a5ffe3391e408f75f726da56c67701f8f}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">#define XXH3_accumulate_512&nbsp;&nbsp;&nbsp;<a href="#adc9c81b2946609f0260dabe87fea8821">XXH3_accumulate_512_scalar</a></td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 474 of file <a href="/web-llvm/docs/api/files/lib/lib/support/xxhash-cpp">xxhash.cpp</a>.</p>


<p>Referenced by <a href="#a1e182c7dbecb63c4c47a78a965ec9909">XXH3_accumulate</a>, <a href="#abfad913bbf7470e15bdfa2349f67a258">XXH3_hashLong_128b</a> and <a href="#a1a58a266c5393605d6eb9b9f26e3ab29">XXH3_hashLong_64b</a>.</p>

</div>
</div>

### XXH3\_scrambleAcc {#a90fcb30d61f3d5fc00e56081205f4a30}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">#define XXH3_scrambleAcc&nbsp;&nbsp;&nbsp;<a href="#ad36d7562c24a3eed4705f092dd82ca23">XXH3_scrambleAcc_scalar</a></td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 475 of file <a href="/web-llvm/docs/api/files/lib/lib/support/xxhash-cpp">xxhash.cpp</a>.</p>


<p>Referenced by <a href="#abfad913bbf7470e15bdfa2349f67a258">XXH3_hashLong_128b</a> and <a href="#a1a58a266c5393605d6eb9b9f26e3ab29">XXH3_hashLong_64b</a>.</p>

</div>
</div>

</div>

<hr/>

<p class="doxyGeneratedBy">Generated via <a href="https://github.com/xpack/doxygen2docusaurus">doxygen2docusaurus</a> by <a href="https://www.doxygen.nl">Doxygen</a> 1.15.0.</p>

</div>
