---

# DO NOT EDIT!
# Automatically generated via doxygen2docusaurus by Doxygen.

slug: /api/files/lib/lib/support/lib/support/blake3/blake3-avx2-c
custom_edit_url: null
toc_max_heading_level: 4
keywords:
  - doxygen
  - reference
  - file

---

<div class="doxyPage">

# `blake3_avx2.c` File



## Included Headers

<div class="doxyIncludesList">#include "<a href="/web-llvm/docs/api/files/lib/lib/support/lib/support/blake3/blake3-impl-h">blake3_impl.h</a>"
#include &lt;immintrin.h&gt;
</div>

## Functions Index

<table class="doxyMembersIndex">

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/files/lib/lib/support/lib/support/blake3/blake3-impl-h/#a2eb6f9e0395b47b8d5e3eeae4fe0c116">INLINE</a> __m256i</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a190d0e1301d8e8afb108f276f83092f4">loadu</a> (const uint8_t src[32])</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a6a21d6ddb93d1fb94f8aadd3d50bbf50">storeu</a> (__m256i src, uint8_t dest[16])</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/files/lib/lib/support/lib/support/blake3/blake3-impl-h/#a2eb6f9e0395b47b8d5e3eeae4fe0c116">INLINE</a> __m256i</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a676a8157485b4579f737a716c3237752">addv</a> (__m256i a, __m256i b)</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/files/lib/lib/support/lib/support/blake3/blake3-impl-h/#a2eb6f9e0395b47b8d5e3eeae4fe0c116">INLINE</a> __m256i</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ac0ce23484157fabd2e2d19756d636020">xorv</a> (__m256i a, __m256i b)</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/files/lib/lib/support/lib/support/blake3/blake3-impl-h/#a2eb6f9e0395b47b8d5e3eeae4fe0c116">INLINE</a> __m256i</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a631aff3f8b622b153bf3155ac44d622c">set1</a> (uint32_t x)</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/files/lib/lib/support/lib/support/blake3/blake3-impl-h/#a2eb6f9e0395b47b8d5e3eeae4fe0c116">INLINE</a> __m256i</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ad1dda0c8d1548b2925d0e9f959d93a15">rot16</a> (__m256i x)</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/files/lib/lib/support/lib/support/blake3/blake3-impl-h/#a2eb6f9e0395b47b8d5e3eeae4fe0c116">INLINE</a> __m256i</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ace54ab93e6ce327a15b768ba92fa97bf">rot12</a> (__m256i x)</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/files/lib/lib/support/lib/support/blake3/blake3-impl-h/#a2eb6f9e0395b47b8d5e3eeae4fe0c116">INLINE</a> __m256i</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a6e8e953194c0d9e9fbfe72b9d106101a">rot8</a> (__m256i x)</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/files/lib/lib/support/lib/support/blake3/blake3-impl-h/#a2eb6f9e0395b47b8d5e3eeae4fe0c116">INLINE</a> __m256i</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#aacf758a78a80782adc01dd77eae9586f">rot7</a> (__m256i x)</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a4ca2ab8ee6f1de52a09a740c7a4dc2a2">round_fn</a> (__m256i v[16], __m256i m[16], size_t r)</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a685d95b087d2f7e12541d09a86551ca1">transpose_vecs</a> (__m256i vecs[DEGREE])</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#aa8b1396a4c576050e51bd164fa569c9a">transpose_msg_vecs</a> (const uint8_t *const *inputs, size_t block_offset, __m256i out[16])</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a9fc11bc6388acc4f8e29f312c02e5ce9">load_counters</a> (uint64_t counter, bool increment_counter, __m256i *out_lo, __m256i *out_hi)</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a8d38698831e5a94b8040641495a835f6">blake3_hash8_avx2</a> (const uint8_t *const *inputs, size_t blocks, const uint32_t key[8], uint64_t counter, bool increment_counter, uint8_t flags, uint8_t flags_start, uint8_t flags_end, uint8_t *out)</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ad5daae07b2a1b3bcad41ad58c9cb4e85">blake3_hash_many_sse41</a> (const uint8_t *const *inputs, size_t num_inputs, size_t blocks, const uint32_t key[8], uint64_t counter, bool increment_counter, uint8_t flags, uint8_t flags_start, uint8_t flags_end, uint8_t *out)</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#afafeb9e2f3c47a85a3455aba2ee5f454">blake3_hash_many_avx2</a> (const uint8_t *const *inputs, size_t num_inputs, size_t blocks, const uint32_t key[8], uint64_t counter, bool increment_counter, uint8_t flags, uint8_t flags_start, uint8_t flags_end, uint8_t *out)</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a5d88b17d70c985f2f2b8e987037fd6dd">DEGREE</a>&nbsp;&nbsp;&nbsp;8</td>
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

### addv() {#a676a8157485b4579f737a716c3237752}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">INLINE __m256i addv (__m256i a, __m256i b)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 15 of file <a href="/web-llvm/docs/api/files/lib/lib/support/lib/support/blake3/blake3-avx2-c">blake3_avx2.c</a>.</p>


<p>Reference <a href="/web-llvm/docs/api/files/lib/lib/support/lib/support/blake3/blake3-impl-h/#a2eb6f9e0395b47b8d5e3eeae4fe0c116">INLINE</a>.</p>


<p>Referenced by <a href="#a4ca2ab8ee6f1de52a09a740c7a4dc2a2">round_fn</a>.</p>

</div>
</div>

### blake3\_hash\_many\_avx2() {#afafeb9e2f3c47a85a3455aba2ee5f454}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void blake3_hash_many_avx2 (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> uint8_t *<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> * inputs, size_t num_inputs, size_t blocks, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> uint32_t key=[8], uint64_t counter, bool increment_counter, uint8_t flags, uint8_t flags_start, uint8_t flags_end, uint8_t * out)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 303 of file <a href="/web-llvm/docs/api/files/lib/lib/support/lib/support/blake3/blake3-avx2-c">blake3_avx2.c</a>.</p>


<p>References <a href="#a8d38698831e5a94b8040641495a835f6">blake3_hash8_avx2</a>, <a href="/web-llvm/docs/api/files/lib/lib/support/lib/support/blake3/llvm-blake3-prefix-h/#aa247d17d10d5ce32fdf0aeb1cb25a717">blake3_hash_many_portable</a>, <a href="/web-llvm/docs/api/files/lib/lib/support/lib/support/blake3/llvm-blake3-prefix-h/#a37a92103b58f72a302f5fa64ebe6f30a">blake3_hash_many_sse41</a>, <a href="/web-llvm/docs/api/files/lib/lib/support/lib/support/blake3/llvm-blake3-prefix-h/#a54e230beb5e1d501702361fb91f399f0">BLAKE3_OUT_LEN</a>, <a href="/web-llvm/docs/api/files/lib/lib/codegen/basicblocksections-cpp/#a6b480a971048f2d9cc342c18046d7774">blocks</a> and <a href="#a5d88b17d70c985f2f2b8e987037fd6dd">DEGREE</a>.</p>

</div>
</div>

### blake3\_hash\_many\_sse41() {#ad5daae07b2a1b3bcad41ad58c9cb4e85}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void blake3_hash_many_sse41 (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> uint8_t *<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> * inputs, size_t num_inputs, size_t blocks, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> uint32_t key=[8], uint64_t counter, bool increment_counter, uint8_t flags, uint8_t flags_start, uint8_t flags_end, uint8_t * out)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Declaration at line 290 of file <a href="/web-llvm/docs/api/files/lib/lib/support/lib/support/blake3/blake3-avx2-c">blake3_avx2.c</a>, definition at line 535 of file <a href="/web-llvm/docs/api/files/lib/lib/support/lib/support/blake3/blake3-sse41-c">blake3_sse41.c</a>.</p>


<p>References <a href="/web-llvm/docs/api/files/lib/lib/support/lib/support/blake3/blake3-sse41-c/#ab9db1c5b05bdca5437891512850ef529">blake3_hash4_sse41</a>, <a href="/web-llvm/docs/api/files/lib/lib/support/lib/support/blake3/llvm-blake3-prefix-h/#a54e230beb5e1d501702361fb91f399f0">BLAKE3_OUT_LEN</a>, <a href="/web-llvm/docs/api/files/lib/lib/codegen/basicblocksections-cpp/#a6b480a971048f2d9cc342c18046d7774">blocks</a>, <a href="#a5d88b17d70c985f2f2b8e987037fd6dd">DEGREE</a> and <a href="/web-llvm/docs/api/files/lib/lib/support/lib/support/blake3/blake3-sse41-c/#ae4d3e60989e66a9a539f56f81426ca8a">hash_one_sse41</a>.</p>

</div>
</div>

### blake3\_hash8\_avx2() {#a8d38698831e5a94b8040641495a835f6}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void blake3_hash8_avx2 (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> uint8_t *<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> * inputs, size_t blocks, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> uint32_t key=[8], uint64_t counter, bool increment_counter, uint8_t flags, uint8_t flags_start, uint8_t flags_end, uint8_t * out)</td>
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



<p>Definition at line 231 of file <a href="/web-llvm/docs/api/files/lib/lib/support/lib/support/blake3/blake3-avx2-c">blake3_avx2.c</a>.</p>


<p>References <a href="/web-llvm/docs/api/files/lib/lib/support/lib/support/blake3/llvm-blake3-prefix-h/#a304cb82e31ff3dc5a4b02f7fce75555e">BLAKE3_BLOCK_LEN</a>, <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/utils/unifyloopexits-cpp/#a4741a07a0e5675f89cfed122008e0a76">block</a>, <a href="/web-llvm/docs/api/files/lib/lib/codegen/basicblocksections-cpp/#a6b480a971048f2d9cc342c18046d7774">blocks</a>, <a href="/web-llvm/docs/api/files/lib/lib/support/lib/support/blake3/blake3-impl-h/#a78823051d1dad34b9b3d8120112e674d">IV</a>, <a href="#a9fc11bc6388acc4f8e29f312c02e5ce9">load_counters</a>, <a href="#a4ca2ab8ee6f1de52a09a740c7a4dc2a2">round_fn</a>, <a href="#a631aff3f8b622b153bf3155ac44d622c">set1</a>, <a href="#a6a21d6ddb93d1fb94f8aadd3d50bbf50">storeu</a>, <a href="#aa8b1396a4c576050e51bd164fa569c9a">transpose_msg_vecs</a>, <a href="#a685d95b087d2f7e12541d09a86551ca1">transpose_vecs</a> and <a href="#ac0ce23484157fabd2e2d19756d636020">xorv</a>.</p>


<p>Referenced by <a href="#afafeb9e2f3c47a85a3455aba2ee5f454">blake3_hash_many_avx2</a>.</p>

</div>
</div>

### load\_counters() {#a9fc11bc6388acc4f8e29f312c02e5ce9}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">INLINE void load_counters (uint64_t counter, bool increment_counter, __m256i * out_lo, __m256i * out_hi)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 217 of file <a href="/web-llvm/docs/api/files/lib/lib/support/lib/support/blake3/blake3-avx2-c">blake3_avx2.c</a>.</p>


<p>Reference <a href="/web-llvm/docs/api/files/lib/lib/support/lib/support/blake3/blake3-impl-h/#a2eb6f9e0395b47b8d5e3eeae4fe0c116">INLINE</a>.</p>


<p>Referenced by <a href="#a8d38698831e5a94b8040641495a835f6">blake3_hash8_avx2</a>.</p>

</div>
</div>

### loadu() {#a190d0e1301d8e8afb108f276f83092f4}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">INLINE __m256i loadu (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> uint8_t src=[32])</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 7 of file <a href="/web-llvm/docs/api/files/lib/lib/support/lib/support/blake3/blake3-avx2-c">blake3_avx2.c</a>.</p>


<p>Reference <a href="/web-llvm/docs/api/files/lib/lib/support/lib/support/blake3/blake3-impl-h/#a2eb6f9e0395b47b8d5e3eeae4fe0c116">INLINE</a>.</p>


<p>Referenced by <a href="#aa8b1396a4c576050e51bd164fa569c9a">transpose_msg_vecs</a>.</p>

</div>
</div>

### rot12() {#ace54ab93e6ce327a15b768ba92fa97bf}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">INLINE __m256i rot12 (__m256i x)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 28 of file <a href="/web-llvm/docs/api/files/lib/lib/support/lib/support/blake3/blake3-avx2-c">blake3_avx2.c</a>.</p>


<p>Reference <a href="/web-llvm/docs/api/files/lib/lib/support/lib/support/blake3/blake3-impl-h/#a2eb6f9e0395b47b8d5e3eeae4fe0c116">INLINE</a>.</p>


<p>Referenced by <a href="#a4ca2ab8ee6f1de52a09a740c7a4dc2a2">round_fn</a>.</p>

</div>
</div>

### rot16() {#ad1dda0c8d1548b2925d0e9f959d93a15}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">INLINE __m256i rot16 (__m256i x)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 22 of file <a href="/web-llvm/docs/api/files/lib/lib/support/lib/support/blake3/blake3-avx2-c">blake3_avx2.c</a>.</p>


<p>Reference <a href="/web-llvm/docs/api/files/lib/lib/support/lib/support/blake3/blake3-impl-h/#a2eb6f9e0395b47b8d5e3eeae4fe0c116">INLINE</a>.</p>


<p>Referenced by <a href="#a4ca2ab8ee6f1de52a09a740c7a4dc2a2">round_fn</a>.</p>

</div>
</div>

### rot7() {#aacf758a78a80782adc01dd77eae9586f}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">INLINE __m256i rot7 (__m256i x)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 38 of file <a href="/web-llvm/docs/api/files/lib/lib/support/lib/support/blake3/blake3-avx2-c">blake3_avx2.c</a>.</p>


<p>Reference <a href="/web-llvm/docs/api/files/lib/lib/support/lib/support/blake3/blake3-impl-h/#a2eb6f9e0395b47b8d5e3eeae4fe0c116">INLINE</a>.</p>


<p>Referenced by <a href="#a4ca2ab8ee6f1de52a09a740c7a4dc2a2">round_fn</a>.</p>

</div>
</div>

### rot8() {#a6e8e953194c0d9e9fbfe72b9d106101a}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">INLINE __m256i rot8 (__m256i x)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 32 of file <a href="/web-llvm/docs/api/files/lib/lib/support/lib/support/blake3/blake3-avx2-c">blake3_avx2.c</a>.</p>


<p>Reference <a href="/web-llvm/docs/api/files/lib/lib/support/lib/support/blake3/blake3-impl-h/#a2eb6f9e0395b47b8d5e3eeae4fe0c116">INLINE</a>.</p>


<p>Referenced by <a href="#a4ca2ab8ee6f1de52a09a740c7a4dc2a2">round_fn</a>.</p>

</div>
</div>

### round\_fn() {#a4ca2ab8ee6f1de52a09a740c7a4dc2a2}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">INLINE void round_fn (__m256i v=[16], __m256i m=[16], size_t r)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 42 of file <a href="/web-llvm/docs/api/files/lib/lib/support/lib/support/blake3/blake3-avx2-c">blake3_avx2.c</a>.</p>


<p>References <a href="#a676a8157485b4579f737a716c3237752">addv</a>, <a href="/web-llvm/docs/api/files/lib/lib/support/lib/support/blake3/blake3-impl-h/#a2eb6f9e0395b47b8d5e3eeae4fe0c116">INLINE</a>, <a href="/web-llvm/docs/api/files/lib/lib/support/lib/support/blake3/blake3-impl-h/#a0683f2191826e5431f112c71a12b7908">MSG_SCHEDULE</a>, <a href="#ace54ab93e6ce327a15b768ba92fa97bf">rot12</a>, <a href="#ad1dda0c8d1548b2925d0e9f959d93a15">rot16</a>, <a href="#aacf758a78a80782adc01dd77eae9586f">rot7</a>, <a href="#a6e8e953194c0d9e9fbfe72b9d106101a">rot8</a> and <a href="#ac0ce23484157fabd2e2d19756d636020">xorv</a>.</p>


<p>Referenced by <a href="#a8d38698831e5a94b8040641495a835f6">blake3_hash8_avx2</a>.</p>

</div>
</div>

### set1() {#a631aff3f8b622b153bf3155ac44d622c}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">INLINE __m256i set1 (uint32_t x)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 20 of file <a href="/web-llvm/docs/api/files/lib/lib/support/lib/support/blake3/blake3-avx2-c">blake3_avx2.c</a>.</p>


<p>Reference <a href="/web-llvm/docs/api/files/lib/lib/support/lib/support/blake3/blake3-impl-h/#a2eb6f9e0395b47b8d5e3eeae4fe0c116">INLINE</a>.</p>


<p>Referenced by <a href="#a8d38698831e5a94b8040641495a835f6">blake3_hash8_avx2</a>.</p>

</div>
</div>

### storeu() {#a6a21d6ddb93d1fb94f8aadd3d50bbf50}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">INLINE void storeu (__m256i src, uint8_t dest=[16])</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 11 of file <a href="/web-llvm/docs/api/files/lib/lib/support/lib/support/blake3/blake3-avx2-c">blake3_avx2.c</a>.</p>


<p>Reference <a href="/web-llvm/docs/api/files/lib/lib/support/lib/support/blake3/blake3-impl-h/#a2eb6f9e0395b47b8d5e3eeae4fe0c116">INLINE</a>.</p>


<p>Referenced by <a href="#a8d38698831e5a94b8040641495a835f6">blake3_hash8_avx2</a>.</p>

</div>
</div>

### transpose\_msg\_vecs() {#aa8b1396a4c576050e51bd164fa569c9a}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">INLINE void transpose_msg_vecs (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> uint8_t *<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> * inputs, size_t block_offset, __m256i out=[16])</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 192 of file <a href="/web-llvm/docs/api/files/lib/lib/support/lib/support/blake3/blake3-avx2-c">blake3_avx2.c</a>.</p>


<p>References <a href="/web-llvm/docs/api/files/lib/lib/support/lib/support/blake3/blake3-impl-h/#a2eb6f9e0395b47b8d5e3eeae4fe0c116">INLINE</a>, <a href="#a190d0e1301d8e8afb108f276f83092f4">loadu</a> and <a href="#a685d95b087d2f7e12541d09a86551ca1">transpose_vecs</a>.</p>


<p>Referenced by <a href="#a8d38698831e5a94b8040641495a835f6">blake3_hash8_avx2</a>.</p>

</div>
</div>

### transpose\_vecs() {#a685d95b087d2f7e12541d09a86551ca1}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">INLINE void transpose_vecs (__m256i vecs=[DEGREE])</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 158 of file <a href="/web-llvm/docs/api/files/lib/lib/support/lib/support/blake3/blake3-avx2-c">blake3_avx2.c</a>.</p>


<p>References <a href="#a5d88b17d70c985f2f2b8e987037fd6dd">DEGREE</a> and <a href="/web-llvm/docs/api/files/lib/lib/support/lib/support/blake3/blake3-impl-h/#a2eb6f9e0395b47b8d5e3eeae4fe0c116">INLINE</a>.</p>


<p>Referenced by <a href="#a8d38698831e5a94b8040641495a835f6">blake3_hash8_avx2</a> and <a href="#aa8b1396a4c576050e51bd164fa569c9a">transpose_msg_vecs</a>.</p>

</div>
</div>

### xorv() {#ac0ce23484157fabd2e2d19756d636020}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">INLINE __m256i xorv (__m256i a, __m256i b)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 18 of file <a href="/web-llvm/docs/api/files/lib/lib/support/lib/support/blake3/blake3-avx2-c">blake3_avx2.c</a>.</p>


<p>Reference <a href="/web-llvm/docs/api/files/lib/lib/support/lib/support/blake3/blake3-impl-h/#a2eb6f9e0395b47b8d5e3eeae4fe0c116">INLINE</a>.</p>


<p>Referenced by <a href="#a8d38698831e5a94b8040641495a835f6">blake3_hash8_avx2</a> and <a href="#a4ca2ab8ee6f1de52a09a740c7a4dc2a2">round_fn</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Macro Definitions

### DEGREE {#a5d88b17d70c985f2f2b8e987037fd6dd}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">#define DEGREE&nbsp;&nbsp;&nbsp;8</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 5 of file <a href="/web-llvm/docs/api/files/lib/lib/support/lib/support/blake3/blake3-avx2-c">blake3_avx2.c</a>.</p>


<p>Referenced by <a href="#afafeb9e2f3c47a85a3455aba2ee5f454">blake3_hash_many_avx2</a>, <a href="/web-llvm/docs/api/files/lib/lib/support/lib/support/blake3/blake3-sse2-c/#aa113f171b931c01e1d430d100cbaa9a5">blake3_hash_many_sse2</a>, <a href="#ad5daae07b2a1b3bcad41ad58c9cb4e85">blake3_hash_many_sse41</a>, <a href="/web-llvm/docs/api/files/lib/lib/support/lib/support/blake3/blake3-sse2-c/#a8c2bc17aeee6c1a4560747ff5c7565fe">transpose_vecs</a> and <a href="#a685d95b087d2f7e12541d09a86551ca1">transpose_vecs</a>.</p>

</div>
</div>

</div>

<hr/>

<p class="doxyGeneratedBy">Generated via <a href="https://xpack.github.io/doxygen2docusaurus">doxygen2docusaurus</a> 2.0.0 by <a href="https://www.doxygen.nl">Doxygen</a> 1.15.0.</p>

</div>
