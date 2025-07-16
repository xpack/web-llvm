---

# DO NOT EDIT!
# Automatically generated via doxygen2docusaurus by Doxygen.

slug: /api/files/lib/lib/support/lib/support/blake3/blake3-sse2-c
custom_edit_url: null
toc_max_heading_level: 4
keywords:
  - doxygen
  - reference
  - file

---

<div class="doxyPage">

# The `blake3_sse2.c` File Reference



## Included Headers

<div class="doxyIncludesList">#include "<a href="/web-llvm/docs/api/files/lib/lib/support/lib/support/blake3/blake3-impl-h">blake3_impl.h</a>"
#include &lt;immintrin.h&gt;
</div>

## Functions Index

<table class="doxyMembersIndex">

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/files/lib/lib/support/lib/support/blake3/blake3-impl-h/#a2eb6f9e0395b47b8d5e3eeae4fe0c116">INLINE</a> __m128i</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ae35186d1b0c22228f120019cdb76634a">loadu</a> (const uint8_t src[16])</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/files/lib/lib/support/lib/support/blake3/blake3-impl-h/#a2eb6f9e0395b47b8d5e3eeae4fe0c116">INLINE</a> void</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a3c669d6cadadea22e9ccb18a62bcf146">storeu</a> (__m128i src, uint8_t dest[16])</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/files/lib/lib/support/lib/support/blake3/blake3-impl-h/#a2eb6f9e0395b47b8d5e3eeae4fe0c116">INLINE</a> __m128i</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#aca2e11aeb5d05238b3609b587922806e">addv</a> (__m128i a, __m128i b)</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/files/lib/lib/support/lib/support/blake3/blake3-impl-h/#a2eb6f9e0395b47b8d5e3eeae4fe0c116">INLINE</a> __m128i</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a7ca307336afa43789f46c77031a43fc9">xorv</a> (__m128i a, __m128i b)</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/files/lib/lib/support/lib/support/blake3/blake3-impl-h/#a2eb6f9e0395b47b8d5e3eeae4fe0c116">INLINE</a> __m128i</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#af553b9391d0b6fc5c18b1be16400792d">set1</a> (uint32_t x)</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/files/lib/lib/support/lib/support/blake3/blake3-impl-h/#a2eb6f9e0395b47b8d5e3eeae4fe0c116">INLINE</a> __m128i</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a0dca48047d04d92458c4517e41d8696e">set4</a> (uint32_t a, uint32_t b, uint32_t c, uint32_t d)</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/files/lib/lib/support/lib/support/blake3/blake3-impl-h/#a2eb6f9e0395b47b8d5e3eeae4fe0c116">INLINE</a> __m128i</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ac2a0d0a804e2ef11d923d48a88c1343e">rot16</a> (__m128i x)</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/files/lib/lib/support/lib/support/blake3/blake3-impl-h/#a2eb6f9e0395b47b8d5e3eeae4fe0c116">INLINE</a> __m128i</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a06685bee684106afaa118d04297cb14a">rot12</a> (__m128i x)</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/files/lib/lib/support/lib/support/blake3/blake3-impl-h/#a2eb6f9e0395b47b8d5e3eeae4fe0c116">INLINE</a> __m128i</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#afcfbfe4f044b6746769505f3ffb1556a">rot8</a> (__m128i x)</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/files/lib/lib/support/lib/support/blake3/blake3-impl-h/#a2eb6f9e0395b47b8d5e3eeae4fe0c116">INLINE</a> __m128i</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a2e30cc476745a6ee0c69491f7a4f506f">rot7</a> (__m128i x)</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/files/lib/lib/support/lib/support/blake3/blake3-impl-h/#a2eb6f9e0395b47b8d5e3eeae4fe0c116">INLINE</a> void</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a227d420457072179f60b78aaa25c9d69">g1</a> (__m128i *row0, __m128i *row1, __m128i *row2, __m128i *row3, __m128i m)</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/files/lib/lib/support/lib/support/blake3/blake3-impl-h/#a2eb6f9e0395b47b8d5e3eeae4fe0c116">INLINE</a> void</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a9a112855b64e521690699ce9d8cbabc6">g2</a> (__m128i *row0, __m128i *row1, __m128i *row2, __m128i *row3, __m128i m)</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/files/lib/lib/support/lib/support/blake3/blake3-impl-h/#a2eb6f9e0395b47b8d5e3eeae4fe0c116">INLINE</a> void</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a70c979e8d315a9dbc9e7b19b15524c01">diagonalize</a> (__m128i *row0, __m128i *row2, __m128i *row3)</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/files/lib/lib/support/lib/support/blake3/blake3-impl-h/#a2eb6f9e0395b47b8d5e3eeae4fe0c116">INLINE</a> void</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a922b09bcc81fca32a8ecbfe2d318d4b7">undiagonalize</a> (__m128i *row0, __m128i *row2, __m128i *row3)</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/files/lib/lib/support/lib/support/blake3/blake3-impl-h/#a2eb6f9e0395b47b8d5e3eeae4fe0c116">INLINE</a> __m128i</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a5d43f9b00b3972592458651dd4a1d44e">blend_epi16</a> (__m128i a, __m128i b, const int16_t imm8)</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/files/lib/lib/support/lib/support/blake3/blake3-impl-h/#a2eb6f9e0395b47b8d5e3eeae4fe0c116">INLINE</a> void</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a963ad8f4da448c3d11d29a95d4881355">compress_pre</a> (__m128i rows[4], const uint32_t cv[8], const uint8_t block[BLAKE3_BLOCK_LEN], uint8_t block_len, uint64_t counter, uint8_t flags)</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#aefa24b59e3f43932466c584ff493fab2">blake3_compress_in_place_sse2</a> (uint32_t cv[8], const uint8_t block[BLAKE3_BLOCK_LEN], uint8_t block_len, uint64_t counter, uint8_t flags)</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ae6d20f2ff68c8e935e628a486b9d842b">blake3_compress_xof_sse2</a> (const uint32_t cv[8], const uint8_t block[BLAKE3_BLOCK_LEN], uint8_t block_len, uint64_t counter, uint8_t flags, uint8_t out[64])</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/files/lib/lib/support/lib/support/blake3/blake3-impl-h/#a2eb6f9e0395b47b8d5e3eeae4fe0c116">INLINE</a> void</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a70d89421ec3c9849593f6e96b3e40c07">round_fn</a> (__m128i v[16], __m128i m[16], size_t r)</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/files/lib/lib/support/lib/support/blake3/blake3-impl-h/#a2eb6f9e0395b47b8d5e3eeae4fe0c116">INLINE</a> void</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a8c2bc17aeee6c1a4560747ff5c7565fe">transpose_vecs</a> (__m128i vecs[DEGREE])</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/files/lib/lib/support/lib/support/blake3/blake3-impl-h/#a2eb6f9e0395b47b8d5e3eeae4fe0c116">INLINE</a> void</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a3caa7b083de1b12f95de768df9174737">transpose_msg_vecs</a> (const uint8_t *const *inputs, size_t block_offset, __m128i out[16])</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/files/lib/lib/support/lib/support/blake3/blake3-impl-h/#a2eb6f9e0395b47b8d5e3eeae4fe0c116">INLINE</a> void</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a9472e29b0a5e9aff142545b491584541">load_counters</a> (uint64_t counter, bool increment_counter, __m128i *out_lo, __m128i *out_hi)</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">static void</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#adf95023f6edf29bf171700cbced2cf30">blake3_hash4_sse2</a> (const uint8_t *const *inputs, size_t blocks, const uint32_t key[8], uint64_t counter, bool increment_counter, uint8_t flags, uint8_t flags_start, uint8_t flags_end, uint8_t *out)</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/files/lib/lib/support/lib/support/blake3/blake3-impl-h/#a2eb6f9e0395b47b8d5e3eeae4fe0c116">INLINE</a> void</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a1e88636b91a8b17c44084bc2d93c5ef2">hash_one_sse2</a> (const uint8_t *input, size_t blocks, const uint32_t key[8], uint64_t counter, uint8_t flags, uint8_t flags_start, uint8_t flags_end, uint8_t out[BLAKE3_OUT_LEN])</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#aa113f171b931c01e1d430d100cbaa9a5">blake3_hash_many_sse2</a> (const uint8_t *const *inputs, size_t num_inputs, size_t blocks, const uint32_t key[8], uint64_t counter, bool increment_counter, uint8_t flags, uint8_t flags_start, uint8_t flags_end, uint8_t *out)</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a5d88b17d70c985f2f2b8e987037fd6dd">DEGREE</a>&nbsp;&nbsp;&nbsp;4</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a0f76993cc7906c818531cf239959c993">_mm_shuffle_ps2</a>(a, b, c)&nbsp;&nbsp;&nbsp;...</td>
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

### addv() {#aca2e11aeb5d05238b3609b587922806e}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">INLINE __m128i addv (__m128i a, __m128i b)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 19 of file <a href="/web-llvm/docs/api/files/lib/lib/support/lib/support/blake3/blake3-sse2-c">blake3_sse2.c</a>.</p>


<p>Reference <a href="/web-llvm/docs/api/files/lib/lib/support/lib/support/blake3/blake3-impl-h/#a2eb6f9e0395b47b8d5e3eeae4fe0c116">INLINE</a>.</p>


<p>Referenced by <a href="#a227d420457072179f60b78aaa25c9d69">g1</a>, <a href="#a9a112855b64e521690699ce9d8cbabc6">g2</a> and <a href="#a70d89421ec3c9849593f6e96b3e40c07">round_fn</a>.</p>

</div>
</div>

### blake3\_compress\_in\_place\_sse2() {#aefa24b59e3f43932466c584ff493fab2}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void blake3_compress_in_place_sse2 (uint32_t cv=[8], <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> uint8_t block=[BLAKE3_BLOCK_LEN], uint8_t block_len, uint64_t counter, uint8_t flags)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 260 of file <a href="/web-llvm/docs/api/files/lib/lib/support/lib/support/blake3/blake3-sse2-c">blake3_sse2.c</a>.</p>


<p>References <a href="/web-llvm/docs/api/files/lib/lib/support/lib/support/blake3/llvm-blake3-prefix-h/#a304cb82e31ff3dc5a4b02f7fce75555e">BLAKE3_BLOCK_LEN</a>, <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/utils/unifyloopexits-cpp/#a4741a07a0e5675f89cfed122008e0a76">block</a>, <a href="#a963ad8f4da448c3d11d29a95d4881355">compress_pre</a>, <a href="#a3c669d6cadadea22e9ccb18a62bcf146">storeu</a> and <a href="#a7ca307336afa43789f46c77031a43fc9">xorv</a>.</p>

</div>
</div>

### blake3\_compress\_xof\_sse2() {#ae6d20f2ff68c8e935e628a486b9d842b}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void blake3_compress_xof_sse2 (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> uint32_t cv=[8], <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> uint8_t block=[BLAKE3_BLOCK_LEN], uint8_t block_len, uint64_t counter, uint8_t flags, uint8_t out=[64])</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 270 of file <a href="/web-llvm/docs/api/files/lib/lib/support/lib/support/blake3/blake3-sse2-c">blake3_sse2.c</a>.</p>


<p>References <a href="/web-llvm/docs/api/files/lib/lib/support/lib/support/blake3/llvm-blake3-prefix-h/#a304cb82e31ff3dc5a4b02f7fce75555e">BLAKE3_BLOCK_LEN</a>, <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/utils/unifyloopexits-cpp/#a4741a07a0e5675f89cfed122008e0a76">block</a>, <a href="#a963ad8f4da448c3d11d29a95d4881355">compress_pre</a>, <a href="#ae35186d1b0c22228f120019cdb76634a">loadu</a>, <a href="#a3c669d6cadadea22e9ccb18a62bcf146">storeu</a> and <a href="#a7ca307336afa43789f46c77031a43fc9">xorv</a>.</p>

</div>
</div>

### blake3\_hash\_many\_sse2() {#aa113f171b931c01e1d430d100cbaa9a5}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void blake3_hash_many_sse2 (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> uint8_t *<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> * inputs, size_t num_inputs, size_t blocks, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> uint32_t key=[8], uint64_t counter, bool increment_counter, uint8_t flags, uint8_t flags_start, uint8_t flags_end, uint8_t * out)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 541 of file <a href="/web-llvm/docs/api/files/lib/lib/support/lib/support/blake3/blake3-sse2-c">blake3_sse2.c</a>.</p>


<p>References <a href="#adf95023f6edf29bf171700cbced2cf30">blake3_hash4_sse2</a>, <a href="/web-llvm/docs/api/files/lib/lib/support/lib/support/blake3/llvm-blake3-prefix-h/#a54e230beb5e1d501702361fb91f399f0">BLAKE3_OUT_LEN</a>, <a href="/web-llvm/docs/api/files/lib/lib/codegen/basicblocksections-cpp/#a6b480a971048f2d9cc342c18046d7774">blocks</a>, <a href="/web-llvm/docs/api/files/lib/lib/support/lib/support/blake3/blake3-avx2-c/#a5d88b17d70c985f2f2b8e987037fd6dd">DEGREE</a> and <a href="#a1e88636b91a8b17c44084bc2d93c5ef2">hash_one_sse2</a>.</p>

</div>
</div>

### blake3\_hash4\_sse2() {#adf95023f6edf29bf171700cbced2cf30}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void blake3_hash4_sse2 (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> uint8_t *<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> * inputs, size_t blocks, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> uint32_t key=[8], uint64_t counter, bool increment_counter, uint8_t flags, uint8_t flags_start, uint8_t flags_end, uint8_t * out)</td>
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



<p>Definition at line 460 of file <a href="/web-llvm/docs/api/files/lib/lib/support/lib/support/blake3/blake3-sse2-c">blake3_sse2.c</a>.</p>


<p>References <a href="/web-llvm/docs/api/files/lib/lib/support/lib/support/blake3/llvm-blake3-prefix-h/#a304cb82e31ff3dc5a4b02f7fce75555e">BLAKE3_BLOCK_LEN</a>, <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/utils/unifyloopexits-cpp/#a4741a07a0e5675f89cfed122008e0a76">block</a>, <a href="/web-llvm/docs/api/files/lib/lib/codegen/basicblocksections-cpp/#a6b480a971048f2d9cc342c18046d7774">blocks</a>, <a href="/web-llvm/docs/api/files/lib/lib/support/lib/support/blake3/blake3-impl-h/#a78823051d1dad34b9b3d8120112e674d">IV</a>, <a href="#a9472e29b0a5e9aff142545b491584541">load_counters</a>, <a href="#a70d89421ec3c9849593f6e96b3e40c07">round_fn</a>, <a href="#af553b9391d0b6fc5c18b1be16400792d">set1</a>, <a href="#a3c669d6cadadea22e9ccb18a62bcf146">storeu</a>, <a href="#a3caa7b083de1b12f95de768df9174737">transpose_msg_vecs</a>, <a href="#a8c2bc17aeee6c1a4560747ff5c7565fe">transpose_vecs</a> and <a href="#a7ca307336afa43789f46c77031a43fc9">xorv</a>.</p>


<p>Referenced by <a href="#aa113f171b931c01e1d430d100cbaa9a5">blake3_hash_many_sse2</a>.</p>

</div>
</div>

### blend\_epi16() {#a5d43f9b00b3972592458651dd4a1d44e}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">INLINE __m128i blend_epi16 (__m128i a, __m128i b, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> int16_t imm8)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 81 of file <a href="/web-llvm/docs/api/files/lib/lib/support/lib/support/blake3/blake3-sse2-c">blake3_sse2.c</a>.</p>


<p>Reference <a href="/web-llvm/docs/api/files/lib/lib/support/lib/support/blake3/blake3-impl-h/#a2eb6f9e0395b47b8d5e3eeae4fe0c116">INLINE</a>.</p>


<p>Referenced by <a href="#a963ad8f4da448c3d11d29a95d4881355">compress_pre</a>.</p>

</div>
</div>

### compress\_pre() {#a963ad8f4da448c3d11d29a95d4881355}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">INLINE void compress_pre (__m128i rows=[4], <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> uint32_t cv=[8], <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> uint8_t block=[BLAKE3_BLOCK_LEN], uint8_t block_len, uint64_t counter, uint8_t flags)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 89 of file <a href="/web-llvm/docs/api/files/lib/lib/support/lib/support/blake3/blake3-sse2-c">blake3_sse2.c</a>.</p>


<p>References <a href="#a0f76993cc7906c818531cf239959c993">_mm_shuffle_ps2</a>, <a href="/web-llvm/docs/api/files/lib/lib/support/lib/support/blake3/llvm-blake3-prefix-h/#a304cb82e31ff3dc5a4b02f7fce75555e">BLAKE3_BLOCK_LEN</a>, <a href="#a5d43f9b00b3972592458651dd4a1d44e">blend_epi16</a>, <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/utils/unifyloopexits-cpp/#a4741a07a0e5675f89cfed122008e0a76">block</a>, <a href="/web-llvm/docs/api/files/lib/lib/support/lib/support/blake3/blake3-impl-h/#a7ec7b2f404362ce5bc1198981707bc7e">counter_high</a>, <a href="/web-llvm/docs/api/files/lib/lib/support/lib/support/blake3/blake3-impl-h/#afeab7ac9eaa036d9400491885ab6c6eb">counter_low</a>, <a href="#a70c979e8d315a9dbc9e7b19b15524c01">diagonalize</a>, <a href="#a227d420457072179f60b78aaa25c9d69">g1</a>, <a href="#a9a112855b64e521690699ce9d8cbabc6">g2</a>, <a href="/web-llvm/docs/api/files/lib/lib/support/lib/support/blake3/blake3-impl-h/#a2eb6f9e0395b47b8d5e3eeae4fe0c116">INLINE</a>, <a href="/web-llvm/docs/api/files/lib/lib/support/lib/support/blake3/blake3-impl-h/#a78823051d1dad34b9b3d8120112e674d">IV</a>, <a href="#ae35186d1b0c22228f120019cdb76634a">loadu</a>, <a href="#a0dca48047d04d92458c4517e41d8696e">set4</a> and <a href="#a922b09bcc81fca32a8ecbfe2d318d4b7">undiagonalize</a>.</p>


<p>Referenced by <a href="#aefa24b59e3f43932466c584ff493fab2">blake3_compress_in_place_sse2</a> and <a href="#ae6d20f2ff68c8e935e628a486b9d842b">blake3_compress_xof_sse2</a>.</p>

</div>
</div>

### diagonalize() {#a70c979e8d315a9dbc9e7b19b15524c01}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">INLINE void diagonalize (__m128i * row0, __m128i * row2, __m128i * row3)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 69 of file <a href="/web-llvm/docs/api/files/lib/lib/support/lib/support/blake3/blake3-sse2-c">blake3_sse2.c</a>.</p>


<p>Reference <a href="/web-llvm/docs/api/files/lib/lib/support/lib/support/blake3/blake3-impl-h/#a2eb6f9e0395b47b8d5e3eeae4fe0c116">INLINE</a>.</p>


<p>Referenced by <a href="#a963ad8f4da448c3d11d29a95d4881355">compress_pre</a>.</p>

</div>
</div>

### g1() {#a227d420457072179f60b78aaa25c9d69}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">INLINE void g1 (__m128i * row0, __m128i * row1, __m128i * row2, __m128i * row3, __m128i m)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 46 of file <a href="/web-llvm/docs/api/files/lib/lib/support/lib/support/blake3/blake3-sse2-c">blake3_sse2.c</a>.</p>


<p>References <a href="#aca2e11aeb5d05238b3609b587922806e">addv</a>, <a href="/web-llvm/docs/api/files/lib/lib/support/lib/support/blake3/blake3-impl-h/#a2eb6f9e0395b47b8d5e3eeae4fe0c116">INLINE</a>, <a href="#a06685bee684106afaa118d04297cb14a">rot12</a>, <a href="#ac2a0d0a804e2ef11d923d48a88c1343e">rot16</a> and <a href="#a7ca307336afa43789f46c77031a43fc9">xorv</a>.</p>


<p>Referenced by <a href="#a963ad8f4da448c3d11d29a95d4881355">compress_pre</a>.</p>

</div>
</div>

### g2() {#a9a112855b64e521690699ce9d8cbabc6}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">INLINE void g2 (__m128i * row0, __m128i * row1, __m128i * row2, __m128i * row3, __m128i m)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 56 of file <a href="/web-llvm/docs/api/files/lib/lib/support/lib/support/blake3/blake3-sse2-c">blake3_sse2.c</a>.</p>


<p>References <a href="#aca2e11aeb5d05238b3609b587922806e">addv</a>, <a href="/web-llvm/docs/api/files/lib/lib/support/lib/support/blake3/blake3-impl-h/#a2eb6f9e0395b47b8d5e3eeae4fe0c116">INLINE</a>, <a href="#a2e30cc476745a6ee0c69491f7a4f506f">rot7</a>, <a href="#afcfbfe4f044b6746769505f3ffb1556a">rot8</a> and <a href="#a7ca307336afa43789f46c77031a43fc9">xorv</a>.</p>


<p>Referenced by <a href="#a963ad8f4da448c3d11d29a95d4881355">compress_pre</a>.</p>

</div>
</div>

### hash\_one\_sse2() {#a1e88636b91a8b17c44084bc2d93c5ef2}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">INLINE void hash_one_sse2 (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> uint8_t * input, size_t blocks, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> uint32_t key=[8], uint64_t counter, uint8_t flags, uint8_t flags_start, uint8_t flags_end, uint8_t out=[BLAKE3_OUT_LEN])</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 521 of file <a href="/web-llvm/docs/api/files/lib/lib/support/lib/support/blake3/blake3-sse2-c">blake3_sse2.c</a>.</p>


<p>References <a href="/web-llvm/docs/api/files/lib/lib/support/lib/support/blake3/llvm-blake3-prefix-h/#a304cb82e31ff3dc5a4b02f7fce75555e">BLAKE3_BLOCK_LEN</a>, <a href="/web-llvm/docs/api/files/lib/lib/support/lib/support/blake3/llvm-blake3-prefix-h/#a686b949247a2ca54dbe0202b6b69d441">blake3_compress_in_place_sse2</a>, <a href="/web-llvm/docs/api/files/lib/lib/support/lib/support/blake3/llvm-blake3-prefix-h/#a947bd80c6cdcbd362dd0760f3603abe6">BLAKE3_KEY_LEN</a>, <a href="/web-llvm/docs/api/files/lib/lib/support/lib/support/blake3/llvm-blake3-prefix-h/#a54e230beb5e1d501702361fb91f399f0">BLAKE3_OUT_LEN</a>, <a href="/web-llvm/docs/api/files/lib/lib/codegen/basicblocksections-cpp/#a6b480a971048f2d9cc342c18046d7774">blocks</a> and <a href="/web-llvm/docs/api/files/lib/lib/support/lib/support/blake3/blake3-impl-h/#a2eb6f9e0395b47b8d5e3eeae4fe0c116">INLINE</a>.</p>


<p>Referenced by <a href="#aa113f171b931c01e1d430d100cbaa9a5">blake3_hash_many_sse2</a>.</p>

</div>
</div>

### load\_counters() {#a9472e29b0a5e9aff142545b491584541}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">INLINE void load_counters (uint64_t counter, bool increment_counter, __m128i * out_lo, __m128i * out_hi)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 446 of file <a href="/web-llvm/docs/api/files/lib/lib/support/lib/support/blake3/blake3-sse2-c">blake3_sse2.c</a>.</p>


<p>Reference <a href="/web-llvm/docs/api/files/lib/lib/support/lib/support/blake3/blake3-impl-h/#a2eb6f9e0395b47b8d5e3eeae4fe0c116">INLINE</a>.</p>


<p>Referenced by <a href="#adf95023f6edf29bf171700cbced2cf30">blake3_hash4_sse2</a>.</p>

</div>
</div>

### loadu() {#ae35186d1b0c22228f120019cdb76634a}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">INLINE __m128i loadu (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> uint8_t src=[16])</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 11 of file <a href="/web-llvm/docs/api/files/lib/lib/support/lib/support/blake3/blake3-sse2-c">blake3_sse2.c</a>.</p>


<p>Reference <a href="/web-llvm/docs/api/files/lib/lib/support/lib/support/blake3/blake3-impl-h/#a2eb6f9e0395b47b8d5e3eeae4fe0c116">INLINE</a>.</p>


<p>Referenced by <a href="#ae6d20f2ff68c8e935e628a486b9d842b">blake3_compress_xof_sse2</a>, <a href="#a963ad8f4da448c3d11d29a95d4881355">compress_pre</a> and <a href="#a3caa7b083de1b12f95de768df9174737">transpose_msg_vecs</a>.</p>

</div>
</div>

### rot12() {#a06685bee684106afaa118d04297cb14a}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">INLINE __m128i rot12 (__m128i x)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 34 of file <a href="/web-llvm/docs/api/files/lib/lib/support/lib/support/blake3/blake3-sse2-c">blake3_sse2.c</a>.</p>


<p>References <a href="/web-llvm/docs/api/files/lib/lib/support/lib/support/blake3/blake3-impl-h/#a2eb6f9e0395b47b8d5e3eeae4fe0c116">INLINE</a> and <a href="#a7ca307336afa43789f46c77031a43fc9">xorv</a>.</p>


<p>Referenced by <a href="#a227d420457072179f60b78aaa25c9d69">g1</a> and <a href="#a70d89421ec3c9849593f6e96b3e40c07">round_fn</a>.</p>

</div>
</div>

### rot16() {#ac2a0d0a804e2ef11d923d48a88c1343e}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">INLINE __m128i rot16 (__m128i x)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 30 of file <a href="/web-llvm/docs/api/files/lib/lib/support/lib/support/blake3/blake3-sse2-c">blake3_sse2.c</a>.</p>


<p>Reference <a href="/web-llvm/docs/api/files/lib/lib/support/lib/support/blake3/blake3-impl-h/#a2eb6f9e0395b47b8d5e3eeae4fe0c116">INLINE</a>.</p>


<p>Referenced by <a href="#a227d420457072179f60b78aaa25c9d69">g1</a> and <a href="#a70d89421ec3c9849593f6e96b3e40c07">round_fn</a>.</p>

</div>
</div>

### rot7() {#a2e30cc476745a6ee0c69491f7a4f506f}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">INLINE __m128i rot7 (__m128i x)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 42 of file <a href="/web-llvm/docs/api/files/lib/lib/support/lib/support/blake3/blake3-sse2-c">blake3_sse2.c</a>.</p>


<p>References <a href="/web-llvm/docs/api/files/lib/lib/support/lib/support/blake3/blake3-impl-h/#a2eb6f9e0395b47b8d5e3eeae4fe0c116">INLINE</a> and <a href="#a7ca307336afa43789f46c77031a43fc9">xorv</a>.</p>


<p>Referenced by <a href="#a9a112855b64e521690699ce9d8cbabc6">g2</a> and <a href="#a70d89421ec3c9849593f6e96b3e40c07">round_fn</a>.</p>

</div>
</div>

### rot8() {#afcfbfe4f044b6746769505f3ffb1556a}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">INLINE __m128i rot8 (__m128i x)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 38 of file <a href="/web-llvm/docs/api/files/lib/lib/support/lib/support/blake3/blake3-sse2-c">blake3_sse2.c</a>.</p>


<p>References <a href="/web-llvm/docs/api/files/lib/lib/support/lib/support/blake3/blake3-impl-h/#a2eb6f9e0395b47b8d5e3eeae4fe0c116">INLINE</a> and <a href="#a7ca307336afa43789f46c77031a43fc9">xorv</a>.</p>


<p>Referenced by <a href="#a9a112855b64e521690699ce9d8cbabc6">g2</a> and <a href="#a70d89421ec3c9849593f6e96b3e40c07">round_fn</a>.</p>

</div>
</div>

### round\_fn() {#a70d89421ec3c9849593f6e96b3e40c07}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">INLINE void round_fn (__m128i v=[16], __m128i m=[16], size_t r)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 282 of file <a href="/web-llvm/docs/api/files/lib/lib/support/lib/support/blake3/blake3-sse2-c">blake3_sse2.c</a>.</p>


<p>References <a href="#aca2e11aeb5d05238b3609b587922806e">addv</a>, <a href="/web-llvm/docs/api/files/lib/lib/support/lib/support/blake3/blake3-impl-h/#a2eb6f9e0395b47b8d5e3eeae4fe0c116">INLINE</a>, <a href="/web-llvm/docs/api/files/lib/lib/support/lib/support/blake3/blake3-impl-h/#a0683f2191826e5431f112c71a12b7908">MSG_SCHEDULE</a>, <a href="#a06685bee684106afaa118d04297cb14a">rot12</a>, <a href="#ac2a0d0a804e2ef11d923d48a88c1343e">rot16</a>, <a href="#a2e30cc476745a6ee0c69491f7a4f506f">rot7</a>, <a href="#afcfbfe4f044b6746769505f3ffb1556a">rot8</a> and <a href="#a7ca307336afa43789f46c77031a43fc9">xorv</a>.</p>


<p>Referenced by <a href="#adf95023f6edf29bf171700cbced2cf30">blake3_hash4_sse2</a>.</p>

</div>
</div>

### set1() {#af553b9391d0b6fc5c18b1be16400792d}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">INLINE __m128i set1 (uint32_t x)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 24 of file <a href="/web-llvm/docs/api/files/lib/lib/support/lib/support/blake3/blake3-sse2-c">blake3_sse2.c</a>.</p>


<p>Reference <a href="/web-llvm/docs/api/files/lib/lib/support/lib/support/blake3/blake3-impl-h/#a2eb6f9e0395b47b8d5e3eeae4fe0c116">INLINE</a>.</p>


<p>Referenced by <a href="#adf95023f6edf29bf171700cbced2cf30">blake3_hash4_sse2</a>.</p>

</div>
</div>

### set4() {#a0dca48047d04d92458c4517e41d8696e}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">INLINE __m128i set4 (uint32_t a, uint32_t b, uint32_t c, uint32_t d)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 26 of file <a href="/web-llvm/docs/api/files/lib/lib/support/lib/support/blake3/blake3-sse2-c">blake3_sse2.c</a>.</p>


<p>Reference <a href="/web-llvm/docs/api/files/lib/lib/support/lib/support/blake3/blake3-impl-h/#a2eb6f9e0395b47b8d5e3eeae4fe0c116">INLINE</a>.</p>


<p>Referenced by <a href="#a963ad8f4da448c3d11d29a95d4881355">compress_pre</a>.</p>

</div>
</div>

### storeu() {#a3c669d6cadadea22e9ccb18a62bcf146}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">INLINE void storeu (__m128i src, uint8_t dest=[16])</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 15 of file <a href="/web-llvm/docs/api/files/lib/lib/support/lib/support/blake3/blake3-sse2-c">blake3_sse2.c</a>.</p>


<p>Reference <a href="/web-llvm/docs/api/files/lib/lib/support/lib/support/blake3/blake3-impl-h/#a2eb6f9e0395b47b8d5e3eeae4fe0c116">INLINE</a>.</p>


<p>Referenced by <a href="#aefa24b59e3f43932466c584ff493fab2">blake3_compress_in_place_sse2</a>, <a href="#ae6d20f2ff68c8e935e628a486b9d842b">blake3_compress_xof_sse2</a> and <a href="#adf95023f6edf29bf171700cbced2cf30">blake3_hash4_sse2</a>.</p>

</div>
</div>

### transpose\_msg\_vecs() {#a3caa7b083de1b12f95de768df9174737}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">INLINE void transpose_msg_vecs (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> uint8_t *<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> * inputs, size_t block_offset, __m128i out=[16])</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 419 of file <a href="/web-llvm/docs/api/files/lib/lib/support/lib/support/blake3/blake3-sse2-c">blake3_sse2.c</a>.</p>


<p>References <a href="/web-llvm/docs/api/files/lib/lib/support/lib/support/blake3/blake3-impl-h/#a2eb6f9e0395b47b8d5e3eeae4fe0c116">INLINE</a>, <a href="#ae35186d1b0c22228f120019cdb76634a">loadu</a> and <a href="#a8c2bc17aeee6c1a4560747ff5c7565fe">transpose_vecs</a>.</p>


<p>Referenced by <a href="#adf95023f6edf29bf171700cbced2cf30">blake3_hash4_sse2</a>.</p>

</div>
</div>

### transpose\_vecs() {#a8c2bc17aeee6c1a4560747ff5c7565fe}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">INLINE void transpose_vecs (__m128i vecs=[DEGREE])</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 398 of file <a href="/web-llvm/docs/api/files/lib/lib/support/lib/support/blake3/blake3-sse2-c">blake3_sse2.c</a>.</p>


<p>References <a href="/web-llvm/docs/api/files/lib/lib/support/lib/support/blake3/blake3-avx2-c/#a5d88b17d70c985f2f2b8e987037fd6dd">DEGREE</a> and <a href="/web-llvm/docs/api/files/lib/lib/support/lib/support/blake3/blake3-impl-h/#a2eb6f9e0395b47b8d5e3eeae4fe0c116">INLINE</a>.</p>


<p>Referenced by <a href="#adf95023f6edf29bf171700cbced2cf30">blake3_hash4_sse2</a> and <a href="#a3caa7b083de1b12f95de768df9174737">transpose_msg_vecs</a>.</p>

</div>
</div>

### undiagonalize() {#a922b09bcc81fca32a8ecbfe2d318d4b7}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">INLINE void undiagonalize (__m128i * row0, __m128i * row2, __m128i * row3)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 75 of file <a href="/web-llvm/docs/api/files/lib/lib/support/lib/support/blake3/blake3-sse2-c">blake3_sse2.c</a>.</p>


<p>Reference <a href="/web-llvm/docs/api/files/lib/lib/support/lib/support/blake3/blake3-impl-h/#a2eb6f9e0395b47b8d5e3eeae4fe0c116">INLINE</a>.</p>


<p>Referenced by <a href="#a963ad8f4da448c3d11d29a95d4881355">compress_pre</a>.</p>

</div>
</div>

### xorv() {#a7ca307336afa43789f46c77031a43fc9}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">INLINE __m128i xorv (__m128i a, __m128i b)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 22 of file <a href="/web-llvm/docs/api/files/lib/lib/support/lib/support/blake3/blake3-sse2-c">blake3_sse2.c</a>.</p>


<p>Reference <a href="/web-llvm/docs/api/files/lib/lib/support/lib/support/blake3/blake3-impl-h/#a2eb6f9e0395b47b8d5e3eeae4fe0c116">INLINE</a>.</p>


<p>Referenced by <a href="#aefa24b59e3f43932466c584ff493fab2">blake3_compress_in_place_sse2</a>, <a href="#ae6d20f2ff68c8e935e628a486b9d842b">blake3_compress_xof_sse2</a>, <a href="#adf95023f6edf29bf171700cbced2cf30">blake3_hash4_sse2</a>, <a href="#a227d420457072179f60b78aaa25c9d69">g1</a>, <a href="#a9a112855b64e521690699ce9d8cbabc6">g2</a>, <a href="#a06685bee684106afaa118d04297cb14a">rot12</a>, <a href="#a2e30cc476745a6ee0c69491f7a4f506f">rot7</a>, <a href="#afcfbfe4f044b6746769505f3ffb1556a">rot8</a> and <a href="#a70d89421ec3c9849593f6e96b3e40c07">round_fn</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Macro Definitions

### \_mm\_shuffle\_ps2 {#a0f76993cc7906c818531cf239959c993}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">#define _mm_shuffle_ps2(a, b, c)&nbsp;&nbsp;&nbsp;...</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<dl class="doxySectionUser">
<dt>Value</dt>
<dd>
<div class="doxyVerbatim">  (_mm_castps_si128(                                                           \
      _mm_shuffle_ps(_mm_castsi128_ps(a), _mm_castsi128_ps(b), (c))))
</div>
</dd>
</dl>

<p>Definition at line 7 of file <a href="/web-llvm/docs/api/files/lib/lib/support/lib/support/blake3/blake3-sse2-c">blake3_sse2.c</a>.</p>


<p>Referenced by <a href="#a963ad8f4da448c3d11d29a95d4881355">compress_pre</a>.</p>

</div>
</div>

### DEGREE {#a5d88b17d70c985f2f2b8e987037fd6dd}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">#define DEGREE&nbsp;&nbsp;&nbsp;4</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 5 of file <a href="/web-llvm/docs/api/files/lib/lib/support/lib/support/blake3/blake3-sse2-c">blake3_sse2.c</a>.</p>

</div>
</div>

</div>

<hr/>

<p class="doxyGeneratedBy">Generated via <a href="https://github.com/xpack/doxygen2docusaurus">doxygen2docusaurus</a> by <a href="https://www.doxygen.nl">Doxygen</a> 1.15.0.</p>

</div>
