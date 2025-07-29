---

# DO NOT EDIT!
# Automatically generated via doxygen2docusaurus by Doxygen.

slug: /api/files/lib/lib/support/lib/support/blake3/blake3-impl-h
custom_edit_url: null
toc_max_heading_level: 4
keywords:
  - doxygen
  - reference
  - file

---

<div class="doxyPage">

# `blake3_impl.h` File



## Included Headers

<div class="doxyIncludesList">#include &lt;assert.h&gt;
#include &lt;stdbool.h&gt;
#include &lt;stddef.h&gt;
#include &lt;stdint.h&gt;
#include &lt;string.h&gt;
#include "<a href="/web-llvm/docs/api/files/include/include/llvm-c/blake3-h">llvm-c/blake3.h</a>"
#include "<a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/support/compiler-h">llvm/Support/Compiler.h</a>"
#include "<a href="/web-llvm/docs/api/files/lib/lib/support/lib/support/blake3/llvm-blake3-prefix-h">llvm_blake3_prefix.h</a>"
</div>

## Enumerations Index

<table class="doxyMembersIndex">

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">enum</td>
<td class="doxyMemberIndexItemName" align="left" valign="top">blake3_flags { <a href="#af1f12c808c513e84d39a88930812b5cb">...</a> }</td>
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

## Functions Index

<table class="doxyMembersIndex">

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">static unsigned int</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a78a2cd88183a3c1deca67c84098e9a5b">highest_one</a> (uint64_t x)</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="#a2eb6f9e0395b47b8d5e3eeae4fe0c116">INLINE</a> unsigned int</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a1817d7ef688b133f9befd300d9e971a0">popcnt</a> (uint64_t x)</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="#a2eb6f9e0395b47b8d5e3eeae4fe0c116">INLINE</a> uint64_t</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#aa512c33323d4cb6599016c57337832fe">round_down_to_power_of_2</a> (uint64_t x)</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="#a2eb6f9e0395b47b8d5e3eeae4fe0c116">INLINE</a> uint32_t</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#afeab7ac9eaa036d9400491885ab6c6eb">counter_low</a> (uint64_t counter)</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="#a2eb6f9e0395b47b8d5e3eeae4fe0c116">INLINE</a> uint32_t</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a7ec7b2f404362ce5bc1198981707bc7e">counter_high</a> (uint64_t counter)</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="#a2eb6f9e0395b47b8d5e3eeae4fe0c116">INLINE</a> uint32_t</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ab1c895f6566413585caf53c2a945c644">load32</a> (const void *src)</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="#a2eb6f9e0395b47b8d5e3eeae4fe0c116">INLINE</a> void</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a8b7b7d6918ecd7ddb8669390f1a321f4">load_key_words</a> (const uint8_t key[BLAKE3_KEY_LEN], uint32_t key_words[8])</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="#a2eb6f9e0395b47b8d5e3eeae4fe0c116">INLINE</a> void</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ab44a2b80e38a954a29e770c0dceb14c0">store32</a> (void *dst, uint32_t w)</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="#a2eb6f9e0395b47b8d5e3eeae4fe0c116">INLINE</a> void</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#aa2fffe259ee56abc321b02c9790a6dfa">store_cv_words</a> (uint8_t bytes_out[32], uint32_t cv_words[8])</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/support/compiler-h/#a662e21bcce5c9c71b6cc511fa04f900f">LLVM_LIBRARY_VISIBILITY</a> void</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a5cb29887012aff247704c482c5e1c8ee">blake3_compress_in_place</a> (uint32_t cv[8], const uint8_t block[BLAKE3_BLOCK_LEN], uint8_t block_len, uint64_t counter, uint8_t flags)</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/support/compiler-h/#a662e21bcce5c9c71b6cc511fa04f900f">LLVM_LIBRARY_VISIBILITY</a> void</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#aa958450e1cae8c4abe6682bc3f8bb41c">blake3_compress_xof</a> (const uint32_t cv[8], const uint8_t block[BLAKE3_BLOCK_LEN], uint8_t block_len, uint64_t counter, uint8_t flags, uint8_t out[64])</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/support/compiler-h/#a662e21bcce5c9c71b6cc511fa04f900f">LLVM_LIBRARY_VISIBILITY</a> void</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#af25d3285085e125ece00909331f36635">blake3_hash_many</a> (const uint8_t *const *inputs, size_t num_inputs, size_t blocks, const uint32_t key[8], uint64_t counter, bool increment_counter, uint8_t flags, uint8_t flags_start, uint8_t flags_end, uint8_t *out)</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/support/compiler-h/#a662e21bcce5c9c71b6cc511fa04f900f">LLVM_LIBRARY_VISIBILITY</a> size_t</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a2a4a163e26880e0692540881194c065c">blake3_simd_degree</a> (void)</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/support/compiler-h/#a662e21bcce5c9c71b6cc511fa04f900f">LLVM_LIBRARY_VISIBILITY</a> void</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a5f1cca60c3c099efd97cafcc542eb4e7">blake3_compress_in_place_portable</a> (uint32_t cv[8], const uint8_t block[BLAKE3_BLOCK_LEN], uint8_t block_len, uint64_t counter, uint8_t flags)</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/support/compiler-h/#a662e21bcce5c9c71b6cc511fa04f900f">LLVM_LIBRARY_VISIBILITY</a> void</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a9b4b1cdf0d88ad62854fd20cc10c1558">blake3_compress_xof_portable</a> (const uint32_t cv[8], const uint8_t block[BLAKE3_BLOCK_LEN], uint8_t block_len, uint64_t counter, uint8_t flags, uint8_t out[64])</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/support/compiler-h/#a662e21bcce5c9c71b6cc511fa04f900f">LLVM_LIBRARY_VISIBILITY</a> void</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a6445e4f293da8868e140464290107427">blake3_hash_many_portable</a> (const uint8_t *const *inputs, size_t num_inputs, size_t blocks, const uint32_t key[8], uint64_t counter, bool increment_counter, uint8_t flags, uint8_t flags_start, uint8_t flags_end, uint8_t *out)</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">static <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> uint32_t</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a78823051d1dad34b9b3d8120112e674d">IV</a>[8] = ...</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">static <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> uint8_t</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a0683f2191826e5431f112c71a12b7908">MSG_SCHEDULE</a>[7][16] = ...</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a2eb6f9e0395b47b8d5e3eeae4fe0c116">INLINE</a>&nbsp;&nbsp;&nbsp;static <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/ipo/alwaysinliner-cpp/#a46ccdc20c42bb5ae5b9d313e12a68421">inline</a> __attribute__((always_inline))</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a0d639f60776bf346e13e20458f9bb7c0">BLAKE3_USE_NEON</a>&nbsp;&nbsp;&nbsp;0</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a464a51e01f71c6dfc24ebba1126ff7dd">MAX_SIMD_DEGREE</a>&nbsp;&nbsp;&nbsp;1</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a8ee4a6d154e907312d4a54eb962388da">MAX_SIMD_DEGREE_OR_2</a>&nbsp;&nbsp;&nbsp;(<a href="#a464a51e01f71c6dfc24ebba1126ff7dd">MAX_SIMD_DEGREE</a> &gt; 2 ? <a href="#a464a51e01f71c6dfc24ebba1126ff7dd">MAX_SIMD_DEGREE</a> : 2)</td>
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

## Enumerations

### blake3\_flags {#af1f12c808c513e84d39a88930812b5cb}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">enum blake3_flags </td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">


<dl class="doxyEnumList">
<dt class="doxyEnumTableTitle">Enumeration values</dt>
<dd>
<table class="doxyEnumTable">

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">CHUNK_START<a id="af1f12c808c513e84d39a88930812b5cba1ee5b64a429be6a437f316619ccf377f"></a></td>
<td class="doxyEnumItemDescription"> (= 1 &lt;&lt; 0)</td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">CHUNK_END<a id="af1f12c808c513e84d39a88930812b5cbad611fba49fcf900148ebefa6649d82fd"></a></td>
<td class="doxyEnumItemDescription"> (= 1 &lt;&lt; 1)</td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">PARENT<a id="af1f12c808c513e84d39a88930812b5cba283df3974c567b21c067198a24cd78e6"></a></td>
<td class="doxyEnumItemDescription"> (= 1 &lt;&lt; 2)</td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">ROOT<a id="af1f12c808c513e84d39a88930812b5cbad41208b99e347d1726824779b11ea11b"></a></td>
<td class="doxyEnumItemDescription"> (= 1 &lt;&lt; 3)</td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">KEYED_HASH<a id="af1f12c808c513e84d39a88930812b5cba372c16918d756eb61949611abeb28fa5"></a></td>
<td class="doxyEnumItemDescription"> (= 1 &lt;&lt; 4)</td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">DERIVE_KEY_CONTEXT<a id="af1f12c808c513e84d39a88930812b5cba891ca3ed53dd8464f1aa3bc5ca792cce"></a></td>
<td class="doxyEnumItemDescription"> (= 1 &lt;&lt; 5)</td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">DERIVE_KEY_MATERIAL<a id="af1f12c808c513e84d39a88930812b5cba399b62381341913e02639d8e1d3e8744"></a></td>
<td class="doxyEnumItemDescription"> (= 1 &lt;&lt; 6)</td>
</tr>

</table>
</dd>
</dl>

<p>Definition at line 17 of file <a href="/web-llvm/docs/api/files/lib/lib/support/lib/support/blake3/blake3-impl-h">blake3_impl.h</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Functions

### blake3\_compress\_in\_place() {#a5cb29887012aff247704c482c5e1c8ee}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">LLVM_LIBRARY_VISIBILITY void blake3_compress_in_place (uint32_t cv=[8], <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> uint8_t block=[BLAKE3_BLOCK_LEN], uint8_t block_len, uint64_t counter, uint8_t flags)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Declaration at line 187 of file <a href="/web-llvm/docs/api/files/lib/lib/support/lib/support/blake3/blake3-impl-h">blake3_impl.h</a>, definition at line 137 of file <a href="/web-llvm/docs/api/files/lib/lib/support/lib/support/blake3/blake3-dispatch-c">blake3_dispatch.c</a>.</p>


<p>References <a href="/web-llvm/docs/api/files/lib/lib/support/lib/support/blake3/blake3-dispatch-c/#a6efa629275df21393eef82e3bf972460a265a413615d057502fd743b974730e0e">AVX512VL</a>, <a href="/web-llvm/docs/api/files/lib/lib/support/lib/support/blake3/llvm-blake3-prefix-h/#a304cb82e31ff3dc5a4b02f7fce75555e">BLAKE3_BLOCK_LEN</a>, <a href="/web-llvm/docs/api/files/lib/lib/support/lib/support/blake3/llvm-blake3-prefix-h/#af94d87a1e3c7e9fa1f8a83b81893f322">blake3_compress_in_place_avx512</a>, <a href="/web-llvm/docs/api/files/lib/lib/support/lib/support/blake3/llvm-blake3-prefix-h/#ae2b22a1d466bc72087370c1b09ad2756">blake3_compress_in_place_portable</a>, <a href="/web-llvm/docs/api/files/lib/lib/support/lib/support/blake3/llvm-blake3-prefix-h/#a686b949247a2ca54dbe0202b6b69d441">blake3_compress_in_place_sse2</a>, <a href="/web-llvm/docs/api/files/lib/lib/support/lib/support/blake3/llvm-blake3-prefix-h/#a02eaea0cccda6df21b4d6793d3fc61de">blake3_compress_in_place_sse41</a>, <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/utils/unifyloopexits-cpp/#a4741a07a0e5675f89cfed122008e0a76">block</a>, <a href="/web-llvm/docs/api/files/lib/lib/support/lib/support/blake3/blake3-dispatch-c/#a66b3e1af9044caa59fc75f60f72ee8e4">get_cpu_features</a>, <a href="/web-llvm/docs/api/files/lib/lib/support/lib/support/blake3/blake3-dispatch-c/#a3282fda96b0ba454bf4a8254c41e466a">MAYBE_UNUSED</a>, <a href="/web-llvm/docs/api/files/lib/lib/support/lib/support/blake3/blake3-dispatch-c/#a6efa629275df21393eef82e3bf972460a8d896e4fb625a47eaa49059a390971df">SSE2</a> and <a href="/web-llvm/docs/api/files/lib/lib/support/lib/support/blake3/blake3-dispatch-c/#a6efa629275df21393eef82e3bf972460a220a8c2c340905b520fa539836209d55">SSE41</a>.</p>

</div>
</div>

### blake3\_compress\_in\_place\_portable() {#a5f1cca60c3c099efd97cafcc542eb4e7}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">LLVM_LIBRARY_VISIBILITY void blake3_compress_in_place_portable (uint32_t cv=[8], <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> uint8_t block=[BLAKE3_BLOCK_LEN], uint8_t block_len, uint64_t counter, uint8_t flags)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Declaration at line 210 of file <a href="/web-llvm/docs/api/files/lib/lib/support/lib/support/blake3/blake3-impl-h">blake3_impl.h</a>, definition at line 84 of file <a href="/web-llvm/docs/api/files/lib/lib/support/lib/support/blake3/blake3-portable-c">blake3_portable.c</a>.</p>


<p>References <a href="/web-llvm/docs/api/files/lib/lib/support/lib/support/blake3/llvm-blake3-prefix-h/#a304cb82e31ff3dc5a4b02f7fce75555e">BLAKE3_BLOCK_LEN</a>, <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/utils/unifyloopexits-cpp/#a4741a07a0e5675f89cfed122008e0a76">block</a> and <a href="/web-llvm/docs/api/files/lib/lib/support/lib/support/blake3/blake3-portable-c/#adc0ded568b1b0f6df58f6d25a7212782">compress_pre</a>.</p>

</div>
</div>

### blake3\_compress\_xof() {#aa958450e1cae8c4abe6682bc3f8bb41c}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">LLVM_LIBRARY_VISIBILITY void blake3_compress_xof (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> uint32_t cv=[8], <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> uint8_t block=[BLAKE3_BLOCK_LEN], uint8_t block_len, uint64_t counter, uint8_t flags, uint8_t out=[64])</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Declaration at line 193 of file <a href="/web-llvm/docs/api/files/lib/lib/support/lib/support/blake3/blake3-impl-h">blake3_impl.h</a>, definition at line 166 of file <a href="/web-llvm/docs/api/files/lib/lib/support/lib/support/blake3/blake3-dispatch-c">blake3_dispatch.c</a>.</p>


<p>References <a href="/web-llvm/docs/api/files/lib/lib/support/lib/support/blake3/blake3-dispatch-c/#a6efa629275df21393eef82e3bf972460a265a413615d057502fd743b974730e0e">AVX512VL</a>, <a href="/web-llvm/docs/api/files/lib/lib/support/lib/support/blake3/llvm-blake3-prefix-h/#a304cb82e31ff3dc5a4b02f7fce75555e">BLAKE3_BLOCK_LEN</a>, <a href="/web-llvm/docs/api/files/lib/lib/support/lib/support/blake3/llvm-blake3-prefix-h/#a78a4c9adffa375af3169dc2204b8d80f">blake3_compress_xof_avx512</a>, <a href="/web-llvm/docs/api/files/lib/lib/support/lib/support/blake3/llvm-blake3-prefix-h/#a9daf63c58deb178310661d2154195b15">blake3_compress_xof_portable</a>, <a href="/web-llvm/docs/api/files/lib/lib/support/lib/support/blake3/llvm-blake3-prefix-h/#a2e0ee76a977bb5a3267115af768d601d">blake3_compress_xof_sse2</a>, <a href="/web-llvm/docs/api/files/lib/lib/support/lib/support/blake3/llvm-blake3-prefix-h/#a57629035a0b0d5c75e599848a1791ee3">blake3_compress_xof_sse41</a>, <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/utils/unifyloopexits-cpp/#a4741a07a0e5675f89cfed122008e0a76">block</a>, <a href="/web-llvm/docs/api/files/lib/lib/support/lib/support/blake3/blake3-dispatch-c/#a66b3e1af9044caa59fc75f60f72ee8e4">get_cpu_features</a>, <a href="/web-llvm/docs/api/files/lib/lib/support/lib/support/blake3/blake3-dispatch-c/#a3282fda96b0ba454bf4a8254c41e466a">MAYBE_UNUSED</a>, <a href="/web-llvm/docs/api/files/lib/lib/support/lib/support/blake3/blake3-dispatch-c/#a6efa629275df21393eef82e3bf972460a8d896e4fb625a47eaa49059a390971df">SSE2</a> and <a href="/web-llvm/docs/api/files/lib/lib/support/lib/support/blake3/blake3-dispatch-c/#a6efa629275df21393eef82e3bf972460a220a8c2c340905b520fa539836209d55">SSE41</a>.</p>

</div>
</div>

### blake3\_compress\_xof\_portable() {#a9b4b1cdf0d88ad62854fd20cc10c1558}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">LLVM_LIBRARY_VISIBILITY void blake3_compress_xof_portable (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> uint32_t cv=[8], <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> uint8_t block=[BLAKE3_BLOCK_LEN], uint8_t block_len, uint64_t counter, uint8_t flags, uint8_t out=[64])</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Declaration at line 216 of file <a href="/web-llvm/docs/api/files/lib/lib/support/lib/support/blake3/blake3-impl-h">blake3_impl.h</a>, definition at line 100 of file <a href="/web-llvm/docs/api/files/lib/lib/support/lib/support/blake3/blake3-portable-c">blake3_portable.c</a>.</p>


<p>References <a href="/web-llvm/docs/api/files/lib/lib/support/lib/support/blake3/llvm-blake3-prefix-h/#a304cb82e31ff3dc5a4b02f7fce75555e">BLAKE3_BLOCK_LEN</a>, <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/utils/unifyloopexits-cpp/#a4741a07a0e5675f89cfed122008e0a76">block</a>, <a href="/web-llvm/docs/api/files/lib/lib/support/lib/support/blake3/blake3-portable-c/#adc0ded568b1b0f6df58f6d25a7212782">compress_pre</a> and <a href="#ab44a2b80e38a954a29e770c0dceb14c0">store32</a>.</p>

</div>
</div>

### blake3\_hash\_many() {#af25d3285085e125ece00909331f36635}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">LLVM_LIBRARY_VISIBILITY void blake3_hash_many (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> uint8_t *<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> * inputs, size_t num_inputs, size_t blocks, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> uint32_t key=[8], uint64_t counter, bool increment_counter, uint8_t flags, uint8_t flags_start, uint8_t flags_end, uint8_t * out)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Declaration at line 199 of file <a href="/web-llvm/docs/api/files/lib/lib/support/lib/support/blake3/blake3-impl-h">blake3_impl.h</a>, definition at line 195 of file <a href="/web-llvm/docs/api/files/lib/lib/support/lib/support/blake3/blake3-dispatch-c">blake3_dispatch.c</a>.</p>


<p>References <a href="/web-llvm/docs/api/files/lib/lib/support/lib/support/blake3/blake3-dispatch-c/#a6efa629275df21393eef82e3bf972460a7b9822126e7b712535af7b882409bf8b">AVX2</a>, <a href="/web-llvm/docs/api/files/lib/lib/support/lib/support/blake3/blake3-dispatch-c/#a6efa629275df21393eef82e3bf972460a698bc47a8c40306f69be562fbc5119fb">AVX512F</a>, <a href="/web-llvm/docs/api/files/lib/lib/support/lib/support/blake3/blake3-dispatch-c/#a6efa629275df21393eef82e3bf972460a265a413615d057502fd743b974730e0e">AVX512VL</a>, <a href="/web-llvm/docs/api/files/lib/lib/support/lib/support/blake3/llvm-blake3-prefix-h/#a1fdc4924759d96608eed27da957714e7">blake3_hash_many_avx2</a>, <a href="/web-llvm/docs/api/files/lib/lib/support/lib/support/blake3/llvm-blake3-prefix-h/#a16f5ea82cd86b9294904063f0ccfcc49">blake3_hash_many_avx512</a>, <a href="/web-llvm/docs/api/files/lib/lib/support/lib/support/blake3/llvm-blake3-prefix-h/#a0eca43e40d730c5f98b68adfb530d8c7">blake3_hash_many_neon</a>, <a href="/web-llvm/docs/api/files/lib/lib/support/lib/support/blake3/llvm-blake3-prefix-h/#aa247d17d10d5ce32fdf0aeb1cb25a717">blake3_hash_many_portable</a>, <a href="/web-llvm/docs/api/files/lib/lib/support/lib/support/blake3/llvm-blake3-prefix-h/#ab4760fe488f905b24eb9529777a682a0">blake3_hash_many_sse2</a>, <a href="/web-llvm/docs/api/files/lib/lib/support/lib/support/blake3/llvm-blake3-prefix-h/#a37a92103b58f72a302f5fa64ebe6f30a">blake3_hash_many_sse41</a>, <a href="/web-llvm/docs/api/files/lib/lib/codegen/basicblocksections-cpp/#a6b480a971048f2d9cc342c18046d7774">blocks</a>, <a href="/web-llvm/docs/api/files/lib/lib/support/lib/support/blake3/blake3-dispatch-c/#a66b3e1af9044caa59fc75f60f72ee8e4">get_cpu_features</a>, <a href="/web-llvm/docs/api/files/lib/lib/support/lib/support/blake3/blake3-dispatch-c/#a3282fda96b0ba454bf4a8254c41e466a">MAYBE_UNUSED</a>, <a href="/web-llvm/docs/api/files/lib/lib/support/lib/support/blake3/blake3-dispatch-c/#a6efa629275df21393eef82e3bf972460a8d896e4fb625a47eaa49059a390971df">SSE2</a> and <a href="/web-llvm/docs/api/files/lib/lib/support/lib/support/blake3/blake3-dispatch-c/#a6efa629275df21393eef82e3bf972460a220a8c2c340905b520fa539836209d55">SSE41</a>.</p>

</div>
</div>

### blake3\_hash\_many\_portable() {#a6445e4f293da8868e140464290107427}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">LLVM_LIBRARY_VISIBILITY void blake3_hash_many_portable (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> uint8_t *<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> * inputs, size_t num_inputs, size_t blocks, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> uint32_t key=[8], uint64_t counter, bool increment_counter, uint8_t flags, uint8_t flags_start, uint8_t flags_end, uint8_t * out)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Declaration at line 222 of file <a href="/web-llvm/docs/api/files/lib/lib/support/lib/support/blake3/blake3-impl-h">blake3_impl.h</a>, definition at line 145 of file <a href="/web-llvm/docs/api/files/lib/lib/support/lib/support/blake3/blake3-portable-c">blake3_portable.c</a>.</p>


<p>References <a href="/web-llvm/docs/api/files/lib/lib/support/lib/support/blake3/llvm-blake3-prefix-h/#a54e230beb5e1d501702361fb91f399f0">BLAKE3_OUT_LEN</a>, <a href="/web-llvm/docs/api/files/lib/lib/codegen/basicblocksections-cpp/#a6b480a971048f2d9cc342c18046d7774">blocks</a> and <a href="/web-llvm/docs/api/files/lib/lib/support/lib/support/blake3/blake3-portable-c/#ac500a9f4a684624f44bfa36853747379">hash_one_portable</a>.</p>

</div>
</div>

### blake3\_simd\_degree() {#a2a4a163e26880e0692540881194c065c}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">LLVM_LIBRARY_VISIBILITY size_t blake3_simd_degree (void)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Declaration at line 205 of file <a href="/web-llvm/docs/api/files/lib/lib/support/lib/support/blake3/blake3-impl-h">blake3_impl.h</a>, definition at line 248 of file <a href="/web-llvm/docs/api/files/lib/lib/support/lib/support/blake3/blake3-dispatch-c">blake3_dispatch.c</a>.</p>


<p>References <a href="/web-llvm/docs/api/files/lib/lib/support/lib/support/blake3/blake3-dispatch-c/#a6efa629275df21393eef82e3bf972460a7b9822126e7b712535af7b882409bf8b">AVX2</a>, <a href="/web-llvm/docs/api/files/lib/lib/support/lib/support/blake3/blake3-dispatch-c/#a6efa629275df21393eef82e3bf972460a698bc47a8c40306f69be562fbc5119fb">AVX512F</a>, <a href="/web-llvm/docs/api/files/lib/lib/support/lib/support/blake3/blake3-dispatch-c/#a6efa629275df21393eef82e3bf972460a265a413615d057502fd743b974730e0e">AVX512VL</a>, <a href="/web-llvm/docs/api/files/lib/lib/support/lib/support/blake3/blake3-dispatch-c/#a66b3e1af9044caa59fc75f60f72ee8e4">get_cpu_features</a>, <a href="/web-llvm/docs/api/files/lib/lib/support/lib/support/blake3/blake3-dispatch-c/#a3282fda96b0ba454bf4a8254c41e466a">MAYBE_UNUSED</a>, <a href="/web-llvm/docs/api/files/lib/lib/support/lib/support/blake3/blake3-dispatch-c/#a6efa629275df21393eef82e3bf972460a8d896e4fb625a47eaa49059a390971df">SSE2</a> and <a href="/web-llvm/docs/api/files/lib/lib/support/lib/support/blake3/blake3-dispatch-c/#a6efa629275df21393eef82e3bf972460a220a8c2c340905b520fa539836209d55">SSE41</a>.</p>

</div>
</div>

### counter\_high() {#a7ec7b2f404362ce5bc1198981707bc7e}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">INLINE uint32_t counter_high (uint64_t counter)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 145 of file <a href="/web-llvm/docs/api/files/lib/lib/support/lib/support/blake3/blake3-impl-h">blake3_impl.h</a>.</p>


<p>Reference <a href="#a2eb6f9e0395b47b8d5e3eeae4fe0c116">INLINE</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/files/lib/lib/support/lib/support/blake3/blake3-avx512-c/#a963ad8f4da448c3d11d29a95d4881355">compress_pre</a> and <a href="/web-llvm/docs/api/files/lib/lib/support/lib/support/blake3/blake3-portable-c/#adc0ded568b1b0f6df58f6d25a7212782">compress_pre</a>.</p>

</div>
</div>

### counter\_low() {#afeab7ac9eaa036d9400491885ab6c6eb}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">INLINE uint32_t counter_low (uint64_t counter)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 143 of file <a href="/web-llvm/docs/api/files/lib/lib/support/lib/support/blake3/blake3-impl-h">blake3_impl.h</a>.</p>


<p>Reference <a href="#a2eb6f9e0395b47b8d5e3eeae4fe0c116">INLINE</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/files/lib/lib/support/lib/support/blake3/blake3-avx512-c/#a963ad8f4da448c3d11d29a95d4881355">compress_pre</a> and <a href="/web-llvm/docs/api/files/lib/lib/support/lib/support/blake3/blake3-portable-c/#adc0ded568b1b0f6df58f6d25a7212782">compress_pre</a>.</p>

</div>
</div>

### highest\_one() {#a78a2cd88183a3c1deca67c84098e9a5b}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">unsigned int highest_one (uint64_t x)</td>
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



<p>Definition at line 94 of file <a href="/web-llvm/docs/api/files/lib/lib/support/lib/support/blake3/blake3-impl-h">blake3_impl.h</a>.</p>


<p>Referenced by <a href="#aa512c33323d4cb6599016c57337832fe">round_down_to_power_of_2</a>.</p>

</div>
</div>

### load\_key\_words() {#a8b7b7d6918ecd7ddb8669390f1a321f4}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">INLINE void load_key_words (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> uint8_t key=[BLAKE3_KEY_LEN], uint32_t key_words=[8])</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 155 of file <a href="/web-llvm/docs/api/files/lib/lib/support/lib/support/blake3/blake3-impl-h">blake3_impl.h</a>.</p>


<p>References <a href="/web-llvm/docs/api/files/lib/lib/support/lib/support/blake3/llvm-blake3-prefix-h/#a947bd80c6cdcbd362dd0760f3603abe6">BLAKE3_KEY_LEN</a>, <a href="#a2eb6f9e0395b47b8d5e3eeae4fe0c116">INLINE</a> and <a href="#ab1c895f6566413585caf53c2a945c644">load32</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/files/lib/lib/support/lib/support/blake3/blake3-c/#acf30a68b4c258e1c1af255c60e880aac">llvm_blake3_hasher_init_derive_key_raw</a> and <a href="/web-llvm/docs/api/files/lib/lib/support/lib/support/blake3/blake3-c/#ac4c4231fe195d56ec58b572d0badc2e6">llvm_blake3_hasher_init_keyed</a>.</p>

</div>
</div>

### load32() {#ab1c895f6566413585caf53c2a945c644}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">INLINE uint32_t load32 (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> void * src)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 149 of file <a href="/web-llvm/docs/api/files/lib/lib/support/lib/support/blake3/blake3-impl-h">blake3_impl.h</a>.</p>


<p>Reference <a href="#a2eb6f9e0395b47b8d5e3eeae4fe0c116">INLINE</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/files/lib/lib/support/lib/support/blake3/blake3-portable-c/#adc0ded568b1b0f6df58f6d25a7212782">compress_pre</a> and <a href="#a8b7b7d6918ecd7ddb8669390f1a321f4">load_key_words</a>.</p>

</div>
</div>

### popcnt() {#a1817d7ef688b133f9befd300d9e971a0}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">INLINE unsigned int popcnt (uint64_t x)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 124 of file <a href="/web-llvm/docs/api/files/lib/lib/support/lib/support/blake3/blake3-impl-h">blake3_impl.h</a>.</p>


<p>Reference <a href="#a2eb6f9e0395b47b8d5e3eeae4fe0c116">INLINE</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/files/lib/lib/support/lib/support/blake3/blake3-c/#a63183e27546bc2e072233e0268400e83">hasher_merge_cv_stack</a>.</p>

</div>
</div>

### round\_down\_to\_power\_of\_2() {#aa512c33323d4cb6599016c57337832fe}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">INLINE uint64_t round_down_to_power_of_2 (uint64_t x)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 139 of file <a href="/web-llvm/docs/api/files/lib/lib/support/lib/support/blake3/blake3-impl-h">blake3_impl.h</a>.</p>


<p>References <a href="#a78a2cd88183a3c1deca67c84098e9a5b">highest_one</a> and <a href="#a2eb6f9e0395b47b8d5e3eeae4fe0c116">INLINE</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/files/lib/lib/support/lib/support/blake3/blake3-c/#af1487a6d4f0aec866d05311a3e42ab30">left_len</a> and <a href="/web-llvm/docs/api/files/lib/lib/support/lib/support/blake3/blake3-c/#a63f3b0c97048b549ce37f5e6a4da701d">llvm_blake3_hasher_update</a>.</p>

</div>
</div>

### store\_cv\_words() {#aa2fffe259ee56abc321b02c9790a6dfa}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">INLINE void store_cv_words (uint8_t bytes_out=[32], uint32_t cv_words=[8])</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 175 of file <a href="/web-llvm/docs/api/files/lib/lib/support/lib/support/blake3/blake3-impl-h">blake3_impl.h</a>.</p>


<p>References <a href="#a2eb6f9e0395b47b8d5e3eeae4fe0c116">INLINE</a> and <a href="#ab44a2b80e38a954a29e770c0dceb14c0">store32</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/files/lib/lib/support/lib/support/blake3/blake3-portable-c/#ac500a9f4a684624f44bfa36853747379">hash_one_portable</a> and <a href="/web-llvm/docs/api/files/lib/lib/support/lib/support/blake3/blake3-c/#a92376f69320e66a51477df2b47088249">output_chaining_value</a>.</p>

</div>
</div>

### store32() {#ab44a2b80e38a954a29e770c0dceb14c0}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">INLINE void store32 (void * dst, uint32_t w)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 167 of file <a href="/web-llvm/docs/api/files/lib/lib/support/lib/support/blake3/blake3-impl-h">blake3_impl.h</a>.</p>


<p>Reference <a href="#a2eb6f9e0395b47b8d5e3eeae4fe0c116">INLINE</a>.</p>


<p>Referenced by <a href="#a9b4b1cdf0d88ad62854fd20cc10c1558">blake3_compress_xof_portable</a> and <a href="#aa2fffe259ee56abc321b02c9790a6dfa">store_cv_words</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Variables

### IV {#a78823051d1dad34b9b3d8120112e674d}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">const uint32_t IV[8]</td>
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



<dl class="doxySectionUser">
<dt>Initialiser</dt>
<dd>
<div class="doxyVerbatim">= {0x6A09E667UL, 0xBB67AE85UL, 0x3C6EF372UL,
                               0xA54FF53AUL, 0x510E527FUL, 0x9B05688CUL,
                               0x1F83D9ABUL, 0x5BE0CD19UL}
</div>
</dd>
</dl>

<p>Definition at line 78 of file <a href="/web-llvm/docs/api/files/lib/lib/support/lib/support/blake3/blake3-impl-h">blake3_impl.h</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/vectorize/loopvectorize-cpp/#ababcaf6e2e00fc3fc8791ea2c3acbda5">addFullyUnrolledInstructionsToIgnore</a>, <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/scalar/jumpthreading-cpp/#a77ce0ad30f134042ba819a49315238d8">addPHINodeEntriesForMappedBlock</a>, <a href="/web-llvm/docs/api/structs/llvm/mcelfstreamer/attributeitem/#a34f36ab6768686360817688ce9f65df4">llvm::MCELFStreamer::AttributeItem::AttributeItem</a>, <a href="/web-llvm/docs/api/files/lib/lib/support/lib/support/blake3/blake3-avx512-c/#a70bc2eed96d3dbb878f77cf42434871f">blake3_hash16_avx512</a>, <a href="/web-llvm/docs/api/files/lib/lib/support/lib/support/blake3/blake3-avx512-c/#afa6d10795b484494db61dafc00ef734b">blake3_hash4_avx512</a>, <a href="/web-llvm/docs/api/files/lib/lib/support/lib/support/blake3/blake3-sse2-c/#adf95023f6edf29bf171700cbced2cf30">blake3_hash4_sse2</a>, <a href="/web-llvm/docs/api/files/lib/lib/support/lib/support/blake3/blake3-sse41-c/#ab9db1c5b05bdca5437891512850ef529">blake3_hash4_sse41</a>, <a href="/web-llvm/docs/api/files/lib/lib/support/lib/support/blake3/blake3-avx2-c/#a8d38698831e5a94b8040641495a835f6">blake3_hash8_avx2</a>, <a href="/web-llvm/docs/api/files/lib/lib/support/lib/support/blake3/blake3-avx512-c/#a9fd5b5d20831064bbb6a1084a54a23aa">blake3_hash8_avx512</a>, <a href="/web-llvm/docs/api/files/lib/lib/support/lib/support/blake3/blake3-avx512-c/#a963ad8f4da448c3d11d29a95d4881355">compress_pre</a>, <a href="/web-llvm/docs/api/files/lib/lib/support/lib/support/blake3/blake3-portable-c/#adc0ded568b1b0f6df58f6d25a7212782">compress_pre</a>, <a href="/web-llvm/docs/api/classes/llvm/openmpirbuilder/#ac669acbd0f638c6ef32977575362052e">llvm::OpenMPIRBuilder::createCanonicalLoop</a>, <a href="/web-llvm/docs/api/classes/llvm/vprecipebuilder/#a826173bded23a3839e30074a98ad34a1">llvm::VPRecipeBuilder::createHeaderMask</a>, <a href="/web-llvm/docs/api/classes/llvm/vpbuilder/#a9bdebe594005618b27255ea3ea2d2cdb">llvm::VPBuilder::createScalarIVSteps</a>, <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/scalar/loopidiomrecognize-cpp/#ab329d363cb73927378483de592986282">detectShiftUntilZeroIdiom</a>, <a href="/web-llvm/docs/api/classes/llvm/jumpthreadingpass/#ac14ea98bd0e870e467ae0ddc75a9fa87">llvm::JumpThreadingPass::duplicateCondBranchOnPHIIntoPred</a>, <a href="/web-llvm/docs/api/classes/anonymous-simplifyindvar-cpp-/simplifyindvar/#a6f5eb28a130d94e94dff2f9e798617ab">anonymous{SimplifyIndVar.cpp}::SimplifyIndvar::eliminateTrunc</a>, <a href="/web-llvm/docs/api/classes/anonymous-msp430asmprinter-cpp-/msp430asmprinter/#a94bff456a6f3ec56f6db8eb5c0aa1acb">anonymous{MSP430AsmPrinter.cpp}::MSP430AsmPrinter::EmitInterruptVectorSection</a>, <a href="/web-llvm/docs/api/classes/llvm/vplan/#ad80b94848142a7c633976aff96d4c408">llvm::VPlan::execute</a>, <a href="/web-llvm/docs/api/classes/llvm/instcombinerimpl/#acad657182350311f85bc33387733e506">llvm::InstCombinerImpl::foldAggregateConstructionIntoAggregateReuse</a>, <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/vectorize/slpvectorizer-cpp/#ad7d5504ae0acaa8a22f450dceccae9b5">getAggregateSize</a>, <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/vectorize/slpvectorizer-cpp/#a77fa69a2017071ea8148d68badf475d1">getElementIndex</a>, <a href="/web-llvm/docs/api/structs/llvm/densemapinfo-bf8488e649e092188a07e41a842f72b6/#a120ab39052b2d339d40eadd7ae4b619e">llvm::DenseMapInfo&lt; PointerIntPair&lt; PointerTy, IntBits, IntType &gt;, void &gt;::getHashValue</a>, <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/scalar/loopstrengthreduce-cpp/#a6612c20f7ca23077265026ea4991e2b6">GetInductionVariable</a>, <a href="/web-llvm/docs/api/classes/anonymous-selectoptimize-cpp-/selectoptimizeimpl/selectlike/#aad811cf3b50296c6f065133a96294e28">anonymous{SelectOptimize.cpp}::SelectOptimizeImpl::SelectLike::getOpCostOnBranch</a>, <a href="/web-llvm/docs/api/files/lib/lib/codegen/selectoptimize-cpp/#a4dc7ba91a5e7ef22fbcc182ad7c83fb3">getTrueOrFalseValue</a>, <a href="/web-llvm/docs/api/classes/anonymous-indvarsimplify-cpp-/indvarsimplifyvisitor/#a1678bb22f6944c1d96d64e30d538a77d">anonymous{IndVarSimplify.cpp}::IndVarSimplifyVisitor::IndVarSimplifyVisitor</a>, <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/utils/loopsimplify-cpp/#ae72984cd3577f73b7880883b12808a8c">insertUniqueBackedgeBlock</a>, <a href="/web-llvm/docs/api/namespaces/llvm/vputils/#a002a77cdbc23293b8f7a8458ffd0f905">llvm::vputils::isUniformAfterVectorization</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a3eb7a9b091032d4d053727b7a578a97e">llvm::isUniformLoop</a>, <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/scalar/gvn-cpp/#a96179307953b47569983bcd440f76130">IsValueFullyAvailableInBlock</a>, <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/instcombine/instcombineloadstorealloca-cpp/#ad32864e83b171a9c8c05bb7da05ceffd">likeBitCastFromVector</a>, <a href="/web-llvm/docs/api/files/lib/lib/support/lib/support/blake3/blake3-c/#a3723853888e765d1049d9f3b9e48dfed">llvm_blake3_hasher_init</a>, <a href="/web-llvm/docs/api/files/lib/lib/support/lib/support/blake3/blake3-c/#acf30a68b4c258e1c1af255c60e880aac">llvm_blake3_hasher_init_derive_key_raw</a>, <a href="/web-llvm/docs/api/groups/llvmccorevalueinstructioninsertvalue/#ga5286df6172a6d8f399761d1a386e0799">LLVMGetIndices</a>, <a href="/web-llvm/docs/api/groups/llvmccorevalueinstructioninsertvalue/#gabdcae5a93cfc74e4dbb5099855bb6435">LLVMGetNumIndices</a>, <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/vectorize/loopvectorize-cpp/#aae23f7e6fc37b0f1bb756f938023512c">preparePlanForEpilogueVectorLoop</a>, <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/scalar/loopstrengthreduce-cpp/#ac33f356faceb9655cb64611d2971d24f">ReduceLoopStrength</a>, <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/vectorize/vplantransforms-cpp/#a2ff7a57c84a06ee83b0a28763db85c3f">removeRedundantInductionCasts</a>, <a href="/web-llvm/docs/api/classes/anonymous-simplifyindvar-cpp-/simplifyindvar/#a16096e55b9292113f13073fa2343b9c7">anonymous{SimplifyIndVar.cpp}::SimplifyIndvar::replaceFloatIVWithIntegerIV</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a2043c82134190abe45de829d07042606">llvm::replaceSignedInst</a>, <a href="/web-llvm/docs/api/classes/anonymous-siinsertwaitcnts-cpp-/siinsertwaitcnts/#aab6a5b3788b7384e1928f2ccd79f26b7">anonymous{SIInsertWaitcnts.cpp}::SIInsertWaitcnts::runOnMachineFunction</a>, <a href="/web-llvm/docs/api/files/lib/lib/analysis/instructionsimplify-cpp/#a3ef524444504c738f1da4b4fb0b5a238">simplifyInstructionWithOperands</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a32aaa22eb69c944393cd5a1c79fa0d35">llvm::SplitBlockAndInsertSimpleForLoop</a>, <a href="/web-llvm/docs/api/classes/llvm/sccpinstvisitor/#a74dbf3215dd56f387425123cbff44a36">llvm::SCCPInstVisitor::trackValueOfGlobalVariable</a>, <a href="/web-llvm/docs/api/classes/llvm/memoryssaupdater/#a989bdd9e36b5327a04ad8db2a7014741">llvm::MemorySSAUpdater::updatePhisWhenInsertingUniqueBackedgeBlock</a>, <a href="/web-llvm/docs/api/classes/llvm/slpvectorizer/boupslp/#a99b79343fdc586cce804ebabf3d419e2">llvm::slpvectorizer::BoUpSLP::vectorizeTree</a>, <a href="/web-llvm/docs/api/classes/llvm/instcombinerimpl/#a679f36556ace611ccc56580cb497973a">llvm::InstCombinerImpl::visitExtractValueInst</a>, <a href="/web-llvm/docs/api/classes/llvm/instcombinerimpl/#a752efe4724ac3a97d07ee81d5f779c92">llvm::InstCombinerImpl::visitPHINode</a>, <a href="/web-llvm/docs/api/classes/llvm/instcombinerimpl/#a62e2ba967b974d6e68931532ab1aa4e8">llvm::InstCombinerImpl::visitSelectInst</a>, <a href="/web-llvm/docs/api/classes/llvm/vpderivedivrecipe/#a8f3e759c33e9fa8f5e604e96c981b955">llvm::VPDerivedIVRecipe::VPDerivedIVRecipe</a>, <a href="/web-llvm/docs/api/classes/llvm/vpscalarivstepsrecipe/#a71852a79224b1fc11ef13ea5055fe0fb">llvm::VPScalarIVStepsRecipe::VPScalarIVStepsRecipe</a>, <a href="/web-llvm/docs/api/classes/llvm/vpscalarivstepsrecipe/#a86f8e3e79f9e3f33b9d5096454eeb57f">llvm::VPScalarIVStepsRecipe::VPScalarIVStepsRecipe</a>, <a href="/web-llvm/docs/api/classes/llvm/vpwideninductionrecipe/#a6df9383fcb4e6c458747b018afc83e15">llvm::VPWidenInductionRecipe::VPWidenInductionRecipe</a>, <a href="/web-llvm/docs/api/classes/llvm/vpwidenintorfpinductionrecipe/#aa01db46604297aadfc584687815e75a4">llvm::VPWidenIntOrFpInductionRecipe::VPWidenIntOrFpInductionRecipe</a>, <a href="/web-llvm/docs/api/classes/llvm/vpwidenintorfpinductionrecipe/#a46123306a8f5c93638c730e6f57581ed">llvm::VPWidenIntOrFpInductionRecipe::VPWidenIntOrFpInductionRecipe</a> and <a href="/web-llvm/docs/api/classes/llvm/instcombinerimpl/#a14d35a77d4b1f7036fd49cee4d138f21">llvm::InstCombinerImpl::~InstCombinerImpl</a>.</p>

</div>
</div>

### MSG\_SCHEDULE {#a0683f2191826e5431f112c71a12b7908}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">const uint8_t MSG_SCHEDULE[7][16]</td>
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



<dl class="doxySectionUser">
<dt>Initialiser</dt>
<dd>
<div class="doxyVerbatim">= {
    {0, 1, 2, 3, 4, 5, 6, 7, 8, 9, 10, 11, 12, 13, 14, 15},
    {2, 6, 3, 10, 7, 0, 4, 13, 1, 11, 12, 5, 9, 14, 15, 8},
    {3, 4, 10, 12, 13, 2, 7, 14, 6, 5, 9, 0, 11, 15, 8, 1},
    {10, 7, 12, 9, 14, 3, 13, 15, 4, 0, 11, 2, 5, 8, 1, 6},
    {12, 13, 9, 11, 15, 10, 14, 8, 7, 2, 5, 3, 0, 1, 6, 4},
    {9, 14, 11, 5, 8, 12, 15, 1, 13, 3, 0, 10, 2, 6, 4, 7},
    {11, 15, 5, 0, 1, 9, 8, 6, 14, 10, 2, 12, 3, 4, 7, 13},
}
</div>
</dd>
</dl>

<p>Definition at line 82 of file <a href="/web-llvm/docs/api/files/lib/lib/support/lib/support/blake3/blake3-impl-h">blake3_impl.h</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/files/lib/lib/support/lib/support/blake3/blake3-sse2-c/#a70d89421ec3c9849593f6e96b3e40c07">round_fn</a>, <a href="/web-llvm/docs/api/files/lib/lib/support/lib/support/blake3/blake3-avx2-c/#a4ca2ab8ee6f1de52a09a740c7a4dc2a2">round_fn</a>, <a href="/web-llvm/docs/api/files/lib/lib/support/lib/support/blake3/blake3-portable-c/#a87355412d6387311f7e404e04ecd5ed0">round_fn</a>, <a href="/web-llvm/docs/api/files/lib/lib/support/lib/support/blake3/blake3-avx512-c/#a30739b84d2b0eae5880770d599d80a53">round_fn16</a>, <a href="/web-llvm/docs/api/files/lib/lib/support/lib/support/blake3/blake3-avx512-c/#aa5f1285c7e774c601fa3e743e1526ecf">round_fn4</a> and <a href="/web-llvm/docs/api/files/lib/lib/support/lib/support/blake3/blake3-avx512-c/#ac77dfe2fb0375dc564e5adbacbee80be">round_fn8</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Macro Definitions

### BLAKE3\_USE\_NEON {#a0d639f60776bf346e13e20458f9bb7c0}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">#define BLAKE3_USE_NEON&nbsp;&nbsp;&nbsp;0</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 62 of file <a href="/web-llvm/docs/api/files/lib/lib/support/lib/support/blake3/blake3-impl-h">blake3_impl.h</a>.</p>

</div>
</div>

### INLINE {#a2eb6f9e0395b47b8d5e3eeae4fe0c116}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">#define INLINE&nbsp;&nbsp;&nbsp;static <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/ipo/alwaysinliner-cpp/#a46ccdc20c42bb5ae5b9d313e12a68421">inline</a> __attribute__((always_inline))</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 32 of file <a href="/web-llvm/docs/api/files/lib/lib/support/lib/support/blake3/blake3-impl-h">blake3_impl.h</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/files/lib/lib/support/lib/support/blake3/blake3-avx512-c/#a6dfb343c3ca4bccb7751311fe96692b8">add_128</a>, <a href="/web-llvm/docs/api/files/lib/lib/support/lib/support/blake3/blake3-avx512-c/#ad9ac052f4305c1e00f16feaf03b3f46f">add_256</a>, <a href="/web-llvm/docs/api/files/lib/lib/support/lib/support/blake3/blake3-avx512-c/#a4e816e84375901a43dc887675dc862ff">add_512</a>, <a href="/web-llvm/docs/api/files/lib/lib/support/lib/support/blake3/blake3-sse2-c/#aca2e11aeb5d05238b3609b587922806e">addv</a>, <a href="/web-llvm/docs/api/files/lib/lib/support/lib/support/blake3/blake3-avx2-c/#a676a8157485b4579f737a716c3237752">addv</a>, <a href="/web-llvm/docs/api/files/lib/lib/support/lib/support/blake3/blake3-sse2-c/#a5d43f9b00b3972592458651dd4a1d44e">blend_epi16</a>, <a href="/web-llvm/docs/api/files/lib/lib/support/lib/support/blake3/blake3-c/#a4e0d6518720be3eb321cbccd3cd8768a">chunk_state_fill_buf</a>, <a href="/web-llvm/docs/api/files/lib/lib/support/lib/support/blake3/blake3-c/#a4db94e2dcf16f8659a69b1636897baeb">chunk_state_init</a>, <a href="/web-llvm/docs/api/files/lib/lib/support/lib/support/blake3/blake3-c/#a2c1ba208c88f9efdc6702769ecd006da">chunk_state_len</a>, <a href="/web-llvm/docs/api/files/lib/lib/support/lib/support/blake3/blake3-c/#a792a24e99fd3fbeb39db66599ace7ae0">chunk_state_maybe_start_flag</a>, <a href="/web-llvm/docs/api/files/lib/lib/support/lib/support/blake3/blake3-c/#acc3e5ba813b5fb930b49c67f1edadf41">chunk_state_output</a>, <a href="/web-llvm/docs/api/files/lib/lib/support/lib/support/blake3/blake3-c/#ac3fec0f8016731502a8a1ad30cea4f3d">chunk_state_reset</a>, <a href="/web-llvm/docs/api/files/lib/lib/support/lib/support/blake3/blake3-c/#a1c4270490e141bac2a6053af9ef01f6b">chunk_state_update</a>, <a href="/web-llvm/docs/api/files/lib/lib/support/lib/support/blake3/blake3-c/#a5b7c95b4370497f963cb03981f87613f">compress_chunks_parallel</a>, <a href="/web-llvm/docs/api/files/lib/lib/support/lib/support/blake3/blake3-c/#ab6b82b4dfe8b1cf5e6cdf18c4dd46097">compress_parents_parallel</a>, <a href="/web-llvm/docs/api/files/lib/lib/support/lib/support/blake3/blake3-avx512-c/#a963ad8f4da448c3d11d29a95d4881355">compress_pre</a>, <a href="/web-llvm/docs/api/files/lib/lib/support/lib/support/blake3/blake3-portable-c/#adc0ded568b1b0f6df58f6d25a7212782">compress_pre</a>, <a href="/web-llvm/docs/api/files/lib/lib/support/lib/support/blake3/blake3-c/#abd0aa960e3f0e3ebab8baccea1f3808a">compress_subtree_to_parent_node</a>, <a href="#a7ec7b2f404362ce5bc1198981707bc7e">counter_high</a>, <a href="#afeab7ac9eaa036d9400491885ab6c6eb">counter_low</a>, <a href="/web-llvm/docs/api/files/lib/lib/support/lib/support/blake3/blake3-avx512-c/#a70c979e8d315a9dbc9e7b19b15524c01">diagonalize</a>, <a href="/web-llvm/docs/api/files/lib/lib/support/lib/support/blake3/blake3-portable-c/#ab5958fad499ed692422c66bb20000a39">g</a>, <a href="/web-llvm/docs/api/files/lib/lib/support/lib/support/blake3/blake3-avx512-c/#a227d420457072179f60b78aaa25c9d69">g1</a>, <a href="/web-llvm/docs/api/files/lib/lib/support/lib/support/blake3/blake3-avx512-c/#a9a112855b64e521690699ce9d8cbabc6">g2</a>, <a href="/web-llvm/docs/api/files/lib/lib/support/lib/support/blake3/blake3-avx512-c/#a37c7357e371a02d89d2bc73d8749e6e4">hash_one_avx512</a>, <a href="/web-llvm/docs/api/files/lib/lib/support/lib/support/blake3/blake3-portable-c/#ac500a9f4a684624f44bfa36853747379">hash_one_portable</a>, <a href="/web-llvm/docs/api/files/lib/lib/support/lib/support/blake3/blake3-sse2-c/#a1e88636b91a8b17c44084bc2d93c5ef2">hash_one_sse2</a>, <a href="/web-llvm/docs/api/files/lib/lib/support/lib/support/blake3/blake3-sse41-c/#ae4d3e60989e66a9a539f56f81426ca8a">hash_one_sse41</a>, <a href="/web-llvm/docs/api/files/lib/lib/support/lib/support/blake3/blake3-c/#a3b12f6c109442edaa63ab03ba8a6caec">hasher_init_base</a>, <a href="/web-llvm/docs/api/files/lib/lib/support/lib/support/blake3/blake3-c/#a63183e27546bc2e072233e0268400e83">hasher_merge_cv_stack</a>, <a href="/web-llvm/docs/api/files/lib/lib/support/lib/support/blake3/blake3-c/#ae7004860c25afdef231d29688cfdb2ff">hasher_push_cv</a>, <a href="/web-llvm/docs/api/files/lib/lib/support/lib/support/blake3/blake3-c/#af1487a6d4f0aec866d05311a3e42ab30">left_len</a>, <a href="#ab1c895f6566413585caf53c2a945c644">load32</a>, <a href="/web-llvm/docs/api/files/lib/lib/support/lib/support/blake3/blake3-sse2-c/#a9472e29b0a5e9aff142545b491584541">load_counters</a>, <a href="/web-llvm/docs/api/files/lib/lib/support/lib/support/blake3/blake3-avx2-c/#a9fc11bc6388acc4f8e29f312c02e5ce9">load_counters</a>, <a href="/web-llvm/docs/api/files/lib/lib/support/lib/support/blake3/blake3-avx512-c/#a75ae50cea7fd5dbedccc602f4a00b078">load_counters16</a>, <a href="/web-llvm/docs/api/files/lib/lib/support/lib/support/blake3/blake3-avx512-c/#a97848bbb6c01d822fa40eaf17661d7da">load_counters4</a>, <a href="/web-llvm/docs/api/files/lib/lib/support/lib/support/blake3/blake3-avx512-c/#a6cea42dede3ee231c75a3fceb5c813b0">load_counters8</a>, <a href="#a8b7b7d6918ecd7ddb8669390f1a321f4">load_key_words</a>, <a href="/web-llvm/docs/api/files/lib/lib/support/lib/support/blake3/blake3-sse2-c/#ae35186d1b0c22228f120019cdb76634a">loadu</a>, <a href="/web-llvm/docs/api/files/lib/lib/support/lib/support/blake3/blake3-avx2-c/#a190d0e1301d8e8afb108f276f83092f4">loadu</a>, <a href="/web-llvm/docs/api/files/lib/lib/support/lib/support/blake3/blake3-avx512-c/#a5817fcd02d768ab2d50855656f67503d">loadu_128</a>, <a href="/web-llvm/docs/api/files/lib/lib/support/lib/support/blake3/blake3-avx512-c/#aa362ae1523e4e2e15e22f2bb5e153992">loadu_256</a>, <a href="/web-llvm/docs/api/files/lib/lib/support/lib/support/blake3/blake3-avx512-c/#a2c0350b1bf45107a56a8a86831d770f4">loadu_512</a>, <a href="/web-llvm/docs/api/files/lib/lib/support/lib/support/blake3/blake3-c/#a0fb8691f907fe586830601d486049e6e">make_output</a>, <a href="/web-llvm/docs/api/files/lib/lib/support/lib/support/blake3/blake3-c/#a92376f69320e66a51477df2b47088249">output_chaining_value</a>, <a href="/web-llvm/docs/api/files/lib/lib/support/lib/support/blake3/blake3-c/#a0a194eae24fe95b572091dc7e992744f">output_root_bytes</a>, <a href="/web-llvm/docs/api/files/lib/lib/support/lib/support/blake3/blake3-c/#ab18874614dade172d2726abc3e88d480">parent_output</a>, <a href="#a1817d7ef688b133f9befd300d9e971a0">popcnt</a>, <a href="/web-llvm/docs/api/files/lib/lib/support/lib/support/blake3/blake3-sse2-c/#a06685bee684106afaa118d04297cb14a">rot12</a>, <a href="/web-llvm/docs/api/files/lib/lib/support/lib/support/blake3/blake3-avx2-c/#ace54ab93e6ce327a15b768ba92fa97bf">rot12</a>, <a href="/web-llvm/docs/api/files/lib/lib/support/lib/support/blake3/blake3-avx512-c/#a5ee3593d7f772b17beb17121f50ba01c">rot12_128</a>, <a href="/web-llvm/docs/api/files/lib/lib/support/lib/support/blake3/blake3-avx512-c/#a5fd287223129634151aec02113431363">rot12_256</a>, <a href="/web-llvm/docs/api/files/lib/lib/support/lib/support/blake3/blake3-avx512-c/#af8b34b45c8bea58bbde2d7142864e45a">rot12_512</a>, <a href="/web-llvm/docs/api/files/lib/lib/support/lib/support/blake3/blake3-sse2-c/#ac2a0d0a804e2ef11d923d48a88c1343e">rot16</a>, <a href="/web-llvm/docs/api/files/lib/lib/support/lib/support/blake3/blake3-avx2-c/#ad1dda0c8d1548b2925d0e9f959d93a15">rot16</a>, <a href="/web-llvm/docs/api/files/lib/lib/support/lib/support/blake3/blake3-avx512-c/#a07a790a133a5c7644000a49ff7eca92f">rot16_128</a>, <a href="/web-llvm/docs/api/files/lib/lib/support/lib/support/blake3/blake3-avx512-c/#a772249cf85a6ca655a7825bf7dca29c6">rot16_256</a>, <a href="/web-llvm/docs/api/files/lib/lib/support/lib/support/blake3/blake3-avx512-c/#a35bfcbfee1b597542ff8b101a805da76">rot16_512</a>, <a href="/web-llvm/docs/api/files/lib/lib/support/lib/support/blake3/blake3-sse2-c/#a2e30cc476745a6ee0c69491f7a4f506f">rot7</a>, <a href="/web-llvm/docs/api/files/lib/lib/support/lib/support/blake3/blake3-avx2-c/#aacf758a78a80782adc01dd77eae9586f">rot7</a>, <a href="/web-llvm/docs/api/files/lib/lib/support/lib/support/blake3/blake3-avx512-c/#adb8eb425d8bc69044f3922b889d4c23d">rot7_128</a>, <a href="/web-llvm/docs/api/files/lib/lib/support/lib/support/blake3/blake3-avx512-c/#a308c32a5885fd1a660aa9f2ec4e2f8fe">rot7_256</a>, <a href="/web-llvm/docs/api/files/lib/lib/support/lib/support/blake3/blake3-avx512-c/#aa7a8127b0d42a25a8ed065062b3f3b0d">rot7_512</a>, <a href="/web-llvm/docs/api/files/lib/lib/support/lib/support/blake3/blake3-sse2-c/#afcfbfe4f044b6746769505f3ffb1556a">rot8</a>, <a href="/web-llvm/docs/api/files/lib/lib/support/lib/support/blake3/blake3-avx2-c/#a6e8e953194c0d9e9fbfe72b9d106101a">rot8</a>, <a href="/web-llvm/docs/api/files/lib/lib/support/lib/support/blake3/blake3-avx512-c/#a3b682bf6df8cfc07532aa3d4c1ab35f7">rot8_128</a>, <a href="/web-llvm/docs/api/files/lib/lib/support/lib/support/blake3/blake3-avx512-c/#a2b2d390aeb1f1b025f7ba84fcef24a17">rot8_256</a>, <a href="/web-llvm/docs/api/files/lib/lib/support/lib/support/blake3/blake3-avx512-c/#a0a8c91bcad2a7df64c309007884bae02">rot8_512</a>, <a href="/web-llvm/docs/api/files/lib/lib/support/lib/support/blake3/blake3-portable-c/#a6f58e26940444cd577b8c7571d01bb77">rotr32</a>, <a href="#aa512c33323d4cb6599016c57337832fe">round_down_to_power_of_2</a>, <a href="/web-llvm/docs/api/files/lib/lib/support/lib/support/blake3/blake3-sse2-c/#a70d89421ec3c9849593f6e96b3e40c07">round_fn</a>, <a href="/web-llvm/docs/api/files/lib/lib/support/lib/support/blake3/blake3-avx2-c/#a4ca2ab8ee6f1de52a09a740c7a4dc2a2">round_fn</a>, <a href="/web-llvm/docs/api/files/lib/lib/support/lib/support/blake3/blake3-portable-c/#a87355412d6387311f7e404e04ecd5ed0">round_fn</a>, <a href="/web-llvm/docs/api/files/lib/lib/support/lib/support/blake3/blake3-avx512-c/#a30739b84d2b0eae5880770d599d80a53">round_fn16</a>, <a href="/web-llvm/docs/api/files/lib/lib/support/lib/support/blake3/blake3-avx512-c/#aa5f1285c7e774c601fa3e743e1526ecf">round_fn4</a>, <a href="/web-llvm/docs/api/files/lib/lib/support/lib/support/blake3/blake3-avx512-c/#ac77dfe2fb0375dc564e5adbacbee80be">round_fn8</a>, <a href="/web-llvm/docs/api/files/lib/lib/support/lib/support/blake3/blake3-avx2-c/#a631aff3f8b622b153bf3155ac44d622c">set1</a>, <a href="/web-llvm/docs/api/files/lib/lib/support/lib/support/blake3/blake3-avx512-c/#a2811db1c6207d1cc140a55f86fa748fe">set1_128</a>, <a href="/web-llvm/docs/api/files/lib/lib/support/lib/support/blake3/blake3-avx512-c/#a11943b732bf85a25a1091f86d98ee0ad">set1_256</a>, <a href="/web-llvm/docs/api/files/lib/lib/support/lib/support/blake3/blake3-avx512-c/#a2b120901f9b4f6ae006342691df0b40a">set1_512</a>, <a href="/web-llvm/docs/api/files/lib/lib/support/lib/support/blake3/blake3-avx512-c/#a0dca48047d04d92458c4517e41d8696e">set4</a>, <a href="#ab44a2b80e38a954a29e770c0dceb14c0">store32</a>, <a href="#aa2fffe259ee56abc321b02c9790a6dfa">store_cv_words</a>, <a href="/web-llvm/docs/api/files/lib/lib/support/lib/support/blake3/blake3-sse2-c/#a3c669d6cadadea22e9ccb18a62bcf146">storeu</a>, <a href="/web-llvm/docs/api/files/lib/lib/support/lib/support/blake3/blake3-avx2-c/#a6a21d6ddb93d1fb94f8aadd3d50bbf50">storeu</a>, <a href="/web-llvm/docs/api/files/lib/lib/support/lib/support/blake3/blake3-avx512-c/#a17b399be366d99ebf4d0d556eb049581">storeu_128</a>, <a href="/web-llvm/docs/api/files/lib/lib/support/lib/support/blake3/blake3-avx512-c/#a348f83b3a9f54be97640e8df8d1736cf">storeu_256</a>, <a href="/web-llvm/docs/api/files/lib/lib/support/lib/support/blake3/blake3-sse2-c/#a3caa7b083de1b12f95de768df9174737">transpose_msg_vecs</a>, <a href="/web-llvm/docs/api/files/lib/lib/support/lib/support/blake3/blake3-avx2-c/#aa8b1396a4c576050e51bd164fa569c9a">transpose_msg_vecs</a>, <a href="/web-llvm/docs/api/files/lib/lib/support/lib/support/blake3/blake3-avx512-c/#abc67f36249d94e163e17fb1ed5c47952">transpose_msg_vecs16</a>, <a href="/web-llvm/docs/api/files/lib/lib/support/lib/support/blake3/blake3-avx512-c/#a821478286a39d4d2b7d3de1029671f6c">transpose_msg_vecs4</a>, <a href="/web-llvm/docs/api/files/lib/lib/support/lib/support/blake3/blake3-avx512-c/#a86bb45f2c9dde435365cd29cc50f0e50">transpose_msg_vecs8</a>, <a href="/web-llvm/docs/api/files/lib/lib/support/lib/support/blake3/blake3-sse2-c/#a8c2bc17aeee6c1a4560747ff5c7565fe">transpose_vecs</a>, <a href="/web-llvm/docs/api/files/lib/lib/support/lib/support/blake3/blake3-avx2-c/#a685d95b087d2f7e12541d09a86551ca1">transpose_vecs</a>, <a href="/web-llvm/docs/api/files/lib/lib/support/lib/support/blake3/blake3-avx512-c/#a389c01f091ae27628ac1343b55d8ffa9">transpose_vecs_128</a>, <a href="/web-llvm/docs/api/files/lib/lib/support/lib/support/blake3/blake3-avx512-c/#aa9fcfa997be0e1657d08fb0fbd6402f0">transpose_vecs_256</a>, <a href="/web-llvm/docs/api/files/lib/lib/support/lib/support/blake3/blake3-avx512-c/#a415cf10dd80134c63e8da7630f93b2c9">transpose_vecs_512</a>, <a href="/web-llvm/docs/api/files/lib/lib/support/lib/support/blake3/blake3-avx512-c/#a922b09bcc81fca32a8ecbfe2d318d4b7">undiagonalize</a>, <a href="/web-llvm/docs/api/files/lib/lib/support/lib/support/blake3/blake3-avx512-c/#ad4321ef7336fc544d580142351381aef">unpack_hi_128</a>, <a href="/web-llvm/docs/api/files/lib/lib/support/lib/support/blake3/blake3-avx512-c/#a7f3c01c73dd0c4b6b5b543483a3fedee">unpack_lo_128</a>, <a href="/web-llvm/docs/api/files/lib/lib/support/lib/support/blake3/blake3-avx512-c/#af1565f865babf10788bb62b46715bb94">xor_128</a>, <a href="/web-llvm/docs/api/files/lib/lib/support/lib/support/blake3/blake3-avx512-c/#a4f79709f3456ef2295a5ae84225f87c8">xor_256</a>, <a href="/web-llvm/docs/api/files/lib/lib/support/lib/support/blake3/blake3-avx512-c/#af1db7ce0c9ee03ae8dde5b0ac6fae619">xor_512</a>, <a href="/web-llvm/docs/api/files/lib/lib/support/lib/support/blake3/blake3-sse2-c/#a7ca307336afa43789f46c77031a43fc9">xorv</a> and <a href="/web-llvm/docs/api/files/lib/lib/support/lib/support/blake3/blake3-avx2-c/#ac0ce23484157fabd2e2d19756d636020">xorv</a>.</p>

</div>
</div>

### MAX\_SIMD\_DEGREE {#a464a51e01f71c6dfc24ebba1126ff7dd}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">#define MAX_SIMD_DEGREE&nbsp;&nbsp;&nbsp;1</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 71 of file <a href="/web-llvm/docs/api/files/lib/lib/support/lib/support/blake3/blake3-impl-h">blake3_impl.h</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/files/lib/lib/support/lib/support/blake3/blake3-c/#a5b7c95b4370497f963cb03981f87613f">compress_chunks_parallel</a>.</p>

</div>
</div>

### MAX\_SIMD\_DEGREE\_OR\_2 {#a8ee4a6d154e907312d4a54eb962388da}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">#define MAX_SIMD_DEGREE_OR_2&nbsp;&nbsp;&nbsp;(<a href="#a464a51e01f71c6dfc24ebba1126ff7dd">MAX_SIMD_DEGREE</a> &gt; 2 ? <a href="#a464a51e01f71c6dfc24ebba1126ff7dd">MAX_SIMD_DEGREE</a> : 2)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 76 of file <a href="/web-llvm/docs/api/files/lib/lib/support/lib/support/blake3/blake3-impl-h">blake3_impl.h</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/files/lib/lib/support/lib/support/blake3/blake3-c/#a6f1fd4d6d509893d09c8b8eb1aa5291c">blake3_compress_subtree_wide</a>, <a href="/web-llvm/docs/api/files/lib/lib/support/lib/support/blake3/blake3-c/#ab6b82b4dfe8b1cf5e6cdf18c4dd46097">compress_parents_parallel</a> and <a href="/web-llvm/docs/api/files/lib/lib/support/lib/support/blake3/blake3-c/#abd0aa960e3f0e3ebab8baccea1f3808a">compress_subtree_to_parent_node</a>.</p>

</div>
</div>

</div>

<hr/>

<p class="doxyGeneratedBy">Generated via <a href="https://github.com/xpack/doxygen2docusaurus">doxygen2docusaurus</a> by <a href="https://www.doxygen.nl">Doxygen</a> 1.15.0.</p>

</div>
