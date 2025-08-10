---

# DO NOT EDIT!
# Automatically generated via doxygen2docusaurus by Doxygen.

slug: /api/files/lib/lib/support/lib/support/blake3/blake3-c
custom_edit_url: null
toc_max_heading_level: 4
keywords:
  - doxygen
  - reference
  - file

---

<div class="doxyPage">

# `blake3.c` File



## Included Headers

<div class="doxyIncludesList">#include &lt;assert.h&gt;
#include &lt;stdbool.h&gt;
#include &lt;string.h&gt;
#include "<a href="/web-llvm/docs/api/files/lib/lib/support/lib/support/blake3/blake3-impl-h">blake3_impl.h</a>"
</div>

## Classes Index

<table class="doxyMembersIndex">

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">struct</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="/web-llvm/docs/api/structs/output-t">output_t</a></td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> char *</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ab9d435f061dc1e6e693d1d4886250754">llvm_blake3_version</a> (void)</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a4db94e2dcf16f8659a69b1636897baeb">chunk_state_init</a> (blake3_chunk_state *self, const uint32_t key[8], uint8_t flags)</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ac3fec0f8016731502a8a1ad30cea4f3d">chunk_state_reset</a> (blake3_chunk_state *self, const uint32_t key[8], uint64_t chunk_counter)</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/files/lib/lib/support/lib/support/blake3/blake3-impl-h/#a2eb6f9e0395b47b8d5e3eeae4fe0c116">INLINE</a> size_t</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a2c1ba208c88f9efdc6702769ecd006da">chunk_state_len</a> (const blake3_chunk_state *self)</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/files/lib/lib/support/lib/support/blake3/blake3-impl-h/#a2eb6f9e0395b47b8d5e3eeae4fe0c116">INLINE</a> size_t</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a4e0d6518720be3eb321cbccd3cd8768a">chunk_state_fill_buf</a> (blake3_chunk_state *self, const uint8_t *input, size_t input_len)</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/files/lib/lib/support/lib/support/blake3/blake3-impl-h/#a2eb6f9e0395b47b8d5e3eeae4fe0c116">INLINE</a> uint8_t</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a792a24e99fd3fbeb39db66599ace7ae0">chunk_state_maybe_start_flag</a> (const blake3_chunk_state *self)</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/files/lib/lib/support/lib/support/blake3/blake3-impl-h/#a2eb6f9e0395b47b8d5e3eeae4fe0c116">INLINE</a> <a href="/web-llvm/docs/api/structs/output-t">output_t</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a0fb8691f907fe586830601d486049e6e">make_output</a> (const uint32_t input_cv[8], const uint8_t block[BLAKE3_BLOCK_LEN], uint8_t block_len, uint64_t counter, uint8_t flags)</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a92376f69320e66a51477df2b47088249">output_chaining_value</a> (const output_t *self, uint8_t cv[32])</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a0a194eae24fe95b572091dc7e992744f">output_root_bytes</a> (const output_t *self, uint64_t seek, uint8_t *out, size_t out_len)</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a1c4270490e141bac2a6053af9ef01f6b">chunk_state_update</a> (blake3_chunk_state *self, const uint8_t *input, size_t input_len)</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/files/lib/lib/support/lib/support/blake3/blake3-impl-h/#a2eb6f9e0395b47b8d5e3eeae4fe0c116">INLINE</a> <a href="/web-llvm/docs/api/structs/output-t">output_t</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#acc3e5ba813b5fb930b49c67f1edadf41">chunk_state_output</a> (const blake3_chunk_state *self)</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/files/lib/lib/support/lib/support/blake3/blake3-impl-h/#a2eb6f9e0395b47b8d5e3eeae4fe0c116">INLINE</a> <a href="/web-llvm/docs/api/structs/output-t">output_t</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ab18874614dade172d2726abc3e88d480">parent_output</a> (const uint8_t block[BLAKE3_BLOCK_LEN], const uint32_t key[8], uint8_t flags)</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/files/lib/lib/support/lib/support/blake3/blake3-impl-h/#a2eb6f9e0395b47b8d5e3eeae4fe0c116">INLINE</a> size_t</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#af1487a6d4f0aec866d05311a3e42ab30">left_len</a> (size_t content_len)</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/files/lib/lib/support/lib/support/blake3/blake3-impl-h/#a2eb6f9e0395b47b8d5e3eeae4fe0c116">INLINE</a> size_t</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a5b7c95b4370497f963cb03981f87613f">compress_chunks_parallel</a> (const uint8_t *input, size_t input_len, const uint32_t key[8], uint64_t chunk_counter, uint8_t flags, uint8_t *out)</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/files/lib/lib/support/lib/support/blake3/blake3-impl-h/#a2eb6f9e0395b47b8d5e3eeae4fe0c116">INLINE</a> size_t</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ab6b82b4dfe8b1cf5e6cdf18c4dd46097">compress_parents_parallel</a> (const uint8_t *child_chaining_values, size_t num_chaining_values, const uint32_t key[8], uint8_t flags, uint8_t *out)</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">static size_t</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a6f1fd4d6d509893d09c8b8eb1aa5291c">blake3_compress_subtree_wide</a> (const uint8_t *input, size_t input_len, const uint32_t key[8], uint64_t chunk_counter, uint8_t flags, uint8_t *out)</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#abd0aa960e3f0e3ebab8baccea1f3808a">compress_subtree_to_parent_node</a> (const uint8_t *input, size_t input_len, const uint32_t key[8], uint64_t chunk_counter, uint8_t flags, uint8_t out[2 *BLAKE3_OUT_LEN])</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a3b12f6c109442edaa63ab03ba8a6caec">hasher_init_base</a> (blake3_hasher *self, const uint32_t key[8], uint8_t flags)</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a3723853888e765d1049d9f3b9e48dfed">llvm_blake3_hasher_init</a> (blake3_hasher *self)</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ac4c4231fe195d56ec58b572d0badc2e6">llvm_blake3_hasher_init_keyed</a> (blake3_hasher *self, const uint8_t key[BLAKE3_KEY_LEN])</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#acf30a68b4c258e1c1af255c60e880aac">llvm_blake3_hasher_init_derive_key_raw</a> (blake3_hasher *self, const void *context, size_t context_len)</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ad0b8fa0cf17c5aa764845fbd3739c85b">llvm_blake3_hasher_init_derive_key</a> (blake3_hasher *self, const char *context)</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a63183e27546bc2e072233e0268400e83">hasher_merge_cv_stack</a> (blake3_hasher *self, uint64_t total_len)</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ae7004860c25afdef231d29688cfdb2ff">hasher_push_cv</a> (blake3_hasher *self, uint8_t new_cv[BLAKE3_OUT_LEN], uint64_t chunk_counter)</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a63f3b0c97048b549ce37f5e6a4da701d">llvm_blake3_hasher_update</a> (blake3_hasher *self, const void *input, size_t input_len)</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a6f1551c11ac8a08c294ee4bf7bf08623">llvm_blake3_hasher_finalize</a> (const blake3_hasher *self, uint8_t *out, size_t out_len)</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ab6b397feba4ec3af8a0b09c3d7c5bffb">llvm_blake3_hasher_finalize_seek</a> (const blake3_hasher *self, uint64_t seek, uint8_t *out, size_t out_len)</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a465d8d4d0fdcb5bf75858c000e3e54f0">llvm_blake3_hasher_reset</a> (blake3_hasher *self)</td>
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

### blake3\_compress\_subtree\_wide() {#a6f1fd4d6d509893d09c8b8eb1aa5291c}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">size_t blake3_compress_subtree_wide (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> uint8_t * input, size_t input_len, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> uint32_t key=[8], uint64_t chunk_counter, uint8_t flags, uint8_t * out)</td>
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



<p>Definition at line 269 of file <a href="/web-llvm/docs/api/files/lib/lib/support/lib/support/blake3/blake3-c">blake3.c</a>.</p>


<p>References <a href="/web-llvm/docs/api/files/lib/lib/support/lib/support/blake3/llvm-blake3-prefix-h/#abcc4f732a672ef43bbfd2dc707e4d15e">BLAKE3_CHUNK_LEN</a>, <a href="#a6f1fd4d6d509893d09c8b8eb1aa5291c">blake3_compress_subtree_wide</a>, <a href="/web-llvm/docs/api/files/lib/lib/support/lib/support/blake3/llvm-blake3-prefix-h/#a54e230beb5e1d501702361fb91f399f0">BLAKE3_OUT_LEN</a>, <a href="/web-llvm/docs/api/files/lib/lib/support/lib/support/blake3/llvm-blake3-prefix-h/#a6e3c3e900f34e7af779867b28b54336d">blake3_simd_degree</a>, <a href="#a5b7c95b4370497f963cb03981f87613f">compress_chunks_parallel</a>, <a href="#ab6b82b4dfe8b1cf5e6cdf18c4dd46097">compress_parents_parallel</a>, <a href="#af1487a6d4f0aec866d05311a3e42ab30">left_len</a> and <a href="/web-llvm/docs/api/files/lib/lib/support/lib/support/blake3/blake3-impl-h/#a8ee4a6d154e907312d4a54eb962388da">MAX_SIMD_DEGREE_OR_2</a>.</p>


<p>Referenced by <a href="#a6f1fd4d6d509893d09c8b8eb1aa5291c">blake3_compress_subtree_wide</a> and <a href="#abd0aa960e3f0e3ebab8baccea1f3808a">compress_subtree_to_parent_node</a>.</p>

</div>
</div>

### chunk\_state\_fill\_buf() {#a4e0d6518720be3eb321cbccd3cd8768a}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">INLINE size_t chunk_state_fill_buf (<a href="/web-llvm/docs/api/files/lib/lib/support/lib/support/blake3/llvm-blake3-prefix-h/#aed21153389299a4d7f8effa38ba58f3b">blake3_chunk_state</a> * self, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> uint8_t * input, size_t input_len)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 41 of file <a href="/web-llvm/docs/api/files/lib/lib/support/lib/support/blake3/blake3-c">blake3.c</a>.</p>


<p>References <a href="/web-llvm/docs/api/files/lib/lib/support/lib/support/blake3/llvm-blake3-prefix-h/#a304cb82e31ff3dc5a4b02f7fce75555e">BLAKE3_BLOCK_LEN</a>, <a href="/web-llvm/docs/api/files/lib/lib/support/lib/support/blake3/llvm-blake3-prefix-h/#aed21153389299a4d7f8effa38ba58f3b">blake3_chunk_state</a> and <a href="/web-llvm/docs/api/files/lib/lib/support/lib/support/blake3/blake3-impl-h/#a2eb6f9e0395b47b8d5e3eeae4fe0c116">INLINE</a>.</p>


<p>Referenced by <a href="#a1c4270490e141bac2a6053af9ef01f6b">chunk_state_update</a>.</p>

</div>
</div>

### chunk\_state\_init() {#a4db94e2dcf16f8659a69b1636897baeb}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">INLINE void chunk_state_init (<a href="/web-llvm/docs/api/files/lib/lib/support/lib/support/blake3/llvm-blake3-prefix-h/#aed21153389299a4d7f8effa38ba58f3b">blake3_chunk_state</a> * self, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> uint32_t key=[8], uint8_t flags)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 17 of file <a href="/web-llvm/docs/api/files/lib/lib/support/lib/support/blake3/blake3-c">blake3.c</a>.</p>


<p>References <a href="/web-llvm/docs/api/files/lib/lib/support/lib/support/blake3/llvm-blake3-prefix-h/#a304cb82e31ff3dc5a4b02f7fce75555e">BLAKE3_BLOCK_LEN</a>, <a href="/web-llvm/docs/api/files/lib/lib/support/lib/support/blake3/llvm-blake3-prefix-h/#aed21153389299a4d7f8effa38ba58f3b">blake3_chunk_state</a>, <a href="/web-llvm/docs/api/files/lib/lib/support/lib/support/blake3/llvm-blake3-prefix-h/#a947bd80c6cdcbd362dd0760f3603abe6">BLAKE3_KEY_LEN</a> and <a href="/web-llvm/docs/api/files/lib/lib/support/lib/support/blake3/blake3-impl-h/#a2eb6f9e0395b47b8d5e3eeae4fe0c116">INLINE</a>.</p>


<p>Referenced by <a href="#a5b7c95b4370497f963cb03981f87613f">compress_chunks_parallel</a>, <a href="#a3b12f6c109442edaa63ab03ba8a6caec">hasher_init_base</a> and <a href="#a63f3b0c97048b549ce37f5e6a4da701d">llvm_blake3_hasher_update</a>.</p>

</div>
</div>

### chunk\_state\_len() {#a2c1ba208c88f9efdc6702769ecd006da}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">INLINE size_t chunk_state_len (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/files/lib/lib/support/lib/support/blake3/llvm-blake3-prefix-h/#aed21153389299a4d7f8effa38ba58f3b">blake3_chunk_state</a> * self)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 36 of file <a href="/web-llvm/docs/api/files/lib/lib/support/lib/support/blake3/blake3-c">blake3.c</a>.</p>


<p>References <a href="/web-llvm/docs/api/files/lib/lib/support/lib/support/blake3/llvm-blake3-prefix-h/#a304cb82e31ff3dc5a4b02f7fce75555e">BLAKE3_BLOCK_LEN</a>, <a href="/web-llvm/docs/api/files/lib/lib/support/lib/support/blake3/llvm-blake3-prefix-h/#aed21153389299a4d7f8effa38ba58f3b">blake3_chunk_state</a> and <a href="/web-llvm/docs/api/files/lib/lib/support/lib/support/blake3/blake3-impl-h/#a2eb6f9e0395b47b8d5e3eeae4fe0c116">INLINE</a>.</p>


<p>Referenced by <a href="#ab6b397feba4ec3af8a0b09c3d7c5bffb">llvm_blake3_hasher_finalize_seek</a> and <a href="#a63f3b0c97048b549ce37f5e6a4da701d">llvm_blake3_hasher_update</a>.</p>

</div>
</div>

### chunk\_state\_maybe\_start\_flag() {#a792a24e99fd3fbeb39db66599ace7ae0}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">INLINE uint8_t chunk_state_maybe_start_flag (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/files/lib/lib/support/lib/support/blake3/llvm-blake3-prefix-h/#aed21153389299a4d7f8effa38ba58f3b">blake3_chunk_state</a> * self)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 53 of file <a href="/web-llvm/docs/api/files/lib/lib/support/lib/support/blake3/blake3-c">blake3.c</a>.</p>


<p>References <a href="/web-llvm/docs/api/files/lib/lib/support/lib/support/blake3/llvm-blake3-prefix-h/#aed21153389299a4d7f8effa38ba58f3b">blake3_chunk_state</a>, <a href="/web-llvm/docs/api/files/lib/lib/support/lib/support/blake3/blake3-impl-h/#af1f12c808c513e84d39a88930812b5cba1ee5b64a429be6a437f316619ccf377f">CHUNK_START</a> and <a href="/web-llvm/docs/api/files/lib/lib/support/lib/support/blake3/blake3-impl-h/#a2eb6f9e0395b47b8d5e3eeae4fe0c116">INLINE</a>.</p>


<p>Referenced by <a href="#acc3e5ba813b5fb930b49c67f1edadf41">chunk_state_output</a> and <a href="#a1c4270490e141bac2a6053af9ef01f6b">chunk_state_update</a>.</p>

</div>
</div>

### chunk\_state\_output() {#acc3e5ba813b5fb930b49c67f1edadf41}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">INLINE output_t chunk_state_output (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/files/lib/lib/support/lib/support/blake3/llvm-blake3-prefix-h/#aed21153389299a4d7f8effa38ba58f3b">blake3_chunk_state</a> * self)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 147 of file <a href="/web-llvm/docs/api/files/lib/lib/support/lib/support/blake3/blake3-c">blake3.c</a>.</p>


<p>References <a href="/web-llvm/docs/api/files/lib/lib/support/lib/support/blake3/llvm-blake3-prefix-h/#aed21153389299a4d7f8effa38ba58f3b">blake3_chunk_state</a>, <a href="/web-llvm/docs/api/files/lib/lib/support/lib/support/blake3/blake3-impl-h/#af1f12c808c513e84d39a88930812b5cbad611fba49fcf900148ebefa6649d82fd">CHUNK_END</a>, <a href="#a792a24e99fd3fbeb39db66599ace7ae0">chunk_state_maybe_start_flag</a>, <a href="/web-llvm/docs/api/files/lib/lib/support/lib/support/blake3/blake3-impl-h/#a2eb6f9e0395b47b8d5e3eeae4fe0c116">INLINE</a> and <a href="#a0fb8691f907fe586830601d486049e6e">make_output</a>.</p>


<p>Referenced by <a href="#a5b7c95b4370497f963cb03981f87613f">compress_chunks_parallel</a>, <a href="#ab6b397feba4ec3af8a0b09c3d7c5bffb">llvm_blake3_hasher_finalize_seek</a> and <a href="#a63f3b0c97048b549ce37f5e6a4da701d">llvm_blake3_hasher_update</a>.</p>

</div>
</div>

### chunk\_state\_reset() {#ac3fec0f8016731502a8a1ad30cea4f3d}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">INLINE void chunk_state_reset (<a href="/web-llvm/docs/api/files/lib/lib/support/lib/support/blake3/llvm-blake3-prefix-h/#aed21153389299a4d7f8effa38ba58f3b">blake3_chunk_state</a> * self, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> uint32_t key=[8], uint64_t chunk_counter)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 27 of file <a href="/web-llvm/docs/api/files/lib/lib/support/lib/support/blake3/blake3-c">blake3.c</a>.</p>


<p>References <a href="/web-llvm/docs/api/files/lib/lib/support/lib/support/blake3/llvm-blake3-prefix-h/#a304cb82e31ff3dc5a4b02f7fce75555e">BLAKE3_BLOCK_LEN</a>, <a href="/web-llvm/docs/api/files/lib/lib/support/lib/support/blake3/llvm-blake3-prefix-h/#aed21153389299a4d7f8effa38ba58f3b">blake3_chunk_state</a>, <a href="/web-llvm/docs/api/files/lib/lib/support/lib/support/blake3/llvm-blake3-prefix-h/#a947bd80c6cdcbd362dd0760f3603abe6">BLAKE3_KEY_LEN</a> and <a href="/web-llvm/docs/api/files/lib/lib/support/lib/support/blake3/blake3-impl-h/#a2eb6f9e0395b47b8d5e3eeae4fe0c116">INLINE</a>.</p>


<p>Referenced by <a href="#a465d8d4d0fdcb5bf75858c000e3e54f0">llvm_blake3_hasher_reset</a> and <a href="#a63f3b0c97048b549ce37f5e6a4da701d">llvm_blake3_hasher_update</a>.</p>

</div>
</div>

### chunk\_state\_update() {#a1c4270490e141bac2a6053af9ef01f6b}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">INLINE void chunk_state_update (<a href="/web-llvm/docs/api/files/lib/lib/support/lib/support/blake3/llvm-blake3-prefix-h/#aed21153389299a4d7f8effa38ba58f3b">blake3_chunk_state</a> * self, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> uint8_t * input, size_t input_len)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 119 of file <a href="/web-llvm/docs/api/files/lib/lib/support/lib/support/blake3/blake3-c">blake3.c</a>.</p>


<p>References <a href="/web-llvm/docs/api/files/lib/lib/support/lib/support/blake3/llvm-blake3-prefix-h/#a304cb82e31ff3dc5a4b02f7fce75555e">BLAKE3_BLOCK_LEN</a>, <a href="/web-llvm/docs/api/files/lib/lib/support/lib/support/blake3/llvm-blake3-prefix-h/#aed21153389299a4d7f8effa38ba58f3b">blake3_chunk_state</a>, <a href="/web-llvm/docs/api/files/lib/lib/support/lib/support/blake3/llvm-blake3-prefix-h/#a720451c4882eb74f48bb24d1af5b7368">blake3_compress_in_place</a>, <a href="#a4e0d6518720be3eb321cbccd3cd8768a">chunk_state_fill_buf</a>, <a href="#a792a24e99fd3fbeb39db66599ace7ae0">chunk_state_maybe_start_flag</a> and <a href="/web-llvm/docs/api/files/lib/lib/support/lib/support/blake3/blake3-impl-h/#a2eb6f9e0395b47b8d5e3eeae4fe0c116">INLINE</a>.</p>


<p>Referenced by <a href="#a5b7c95b4370497f963cb03981f87613f">compress_chunks_parallel</a> and <a href="#a63f3b0c97048b549ce37f5e6a4da701d">llvm_blake3_hasher_update</a>.</p>

</div>
</div>

### compress\_chunks\_parallel() {#a5b7c95b4370497f963cb03981f87613f}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">INLINE size_t compress_chunks_parallel (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> uint8_t * input, size_t input_len, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> uint32_t key=[8], uint64_t chunk_counter, uint8_t flags, uint8_t * out)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 173 of file <a href="/web-llvm/docs/api/files/lib/lib/support/lib/support/blake3/blake3-c">blake3.c</a>.</p>


<p>References <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/silowercontrolflow-cpp/#a4868c5d81c5ccc98c47aeab6244346a0">assert</a>, <a href="/web-llvm/docs/api/files/lib/lib/support/lib/support/blake3/llvm-blake3-prefix-h/#a304cb82e31ff3dc5a4b02f7fce75555e">BLAKE3_BLOCK_LEN</a>, <a href="/web-llvm/docs/api/files/lib/lib/support/lib/support/blake3/llvm-blake3-prefix-h/#abcc4f732a672ef43bbfd2dc707e4d15e">BLAKE3_CHUNK_LEN</a>, <a href="/web-llvm/docs/api/files/lib/lib/support/lib/support/blake3/llvm-blake3-prefix-h/#aed21153389299a4d7f8effa38ba58f3b">blake3_chunk_state</a>, <a href="/web-llvm/docs/api/files/lib/lib/support/lib/support/blake3/llvm-blake3-prefix-h/#a5ea78fa6f9e8732fc336ad0739d3e76e">blake3_hash_many</a>, <a href="/web-llvm/docs/api/files/lib/lib/support/lib/support/blake3/llvm-blake3-prefix-h/#a54e230beb5e1d501702361fb91f399f0">BLAKE3_OUT_LEN</a>, <a href="/web-llvm/docs/api/files/lib/lib/support/lib/support/blake3/blake3-impl-h/#af1f12c808c513e84d39a88930812b5cbad611fba49fcf900148ebefa6649d82fd">CHUNK_END</a>, <a href="/web-llvm/docs/api/files/lib/lib/support/lib/support/blake3/blake3-impl-h/#af1f12c808c513e84d39a88930812b5cba1ee5b64a429be6a437f316619ccf377f">CHUNK_START</a>, <a href="#a4db94e2dcf16f8659a69b1636897baeb">chunk_state_init</a>, <a href="#acc3e5ba813b5fb930b49c67f1edadf41">chunk_state_output</a>, <a href="#a1c4270490e141bac2a6053af9ef01f6b">chunk_state_update</a>, <a href="/web-llvm/docs/api/files/lib/lib/support/lib/support/blake3/blake3-impl-h/#a2eb6f9e0395b47b8d5e3eeae4fe0c116">INLINE</a>, <a href="/web-llvm/docs/api/files/lib/lib/support/lib/support/blake3/blake3-impl-h/#a464a51e01f71c6dfc24ebba1126ff7dd">MAX_SIMD_DEGREE</a> and <a href="#a92376f69320e66a51477df2b47088249">output_chaining_value</a>.</p>


<p>Referenced by <a href="#a6f1fd4d6d509893d09c8b8eb1aa5291c">blake3_compress_subtree_wide</a>.</p>

</div>
</div>

### compress\_parents\_parallel() {#ab6b82b4dfe8b1cf5e6cdf18c4dd46097}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">INLINE size_t compress_parents_parallel (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> uint8_t * child_chaining_values, size_t num_chaining_values, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> uint32_t key=[8], uint8_t flags, uint8_t * out)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 217 of file <a href="/web-llvm/docs/api/files/lib/lib/support/lib/support/blake3/blake3-c">blake3.c</a>.</p>


<p>References <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/silowercontrolflow-cpp/#a4868c5d81c5ccc98c47aeab6244346a0">assert</a>, <a href="/web-llvm/docs/api/files/lib/lib/support/lib/support/blake3/llvm-blake3-prefix-h/#a5ea78fa6f9e8732fc336ad0739d3e76e">blake3_hash_many</a>, <a href="/web-llvm/docs/api/files/lib/lib/support/lib/support/blake3/llvm-blake3-prefix-h/#a54e230beb5e1d501702361fb91f399f0">BLAKE3_OUT_LEN</a>, <a href="/web-llvm/docs/api/files/lib/lib/support/lib/support/blake3/blake3-impl-h/#a2eb6f9e0395b47b8d5e3eeae4fe0c116">INLINE</a>, <a href="/web-llvm/docs/api/files/lib/lib/support/lib/support/blake3/blake3-impl-h/#a8ee4a6d154e907312d4a54eb962388da">MAX_SIMD_DEGREE_OR_2</a> and <a href="/web-llvm/docs/api/files/lib/lib/support/lib/support/blake3/blake3-impl-h/#af1f12c808c513e84d39a88930812b5cba283df3974c567b21c067198a24cd78e6">PARENT</a>.</p>


<p>Referenced by <a href="#a6f1fd4d6d509893d09c8b8eb1aa5291c">blake3_compress_subtree_wide</a> and <a href="#abd0aa960e3f0e3ebab8baccea1f3808a">compress_subtree_to_parent_node</a>.</p>

</div>
</div>

### compress\_subtree\_to\_parent\_node() {#abd0aa960e3f0e3ebab8baccea1f3808a}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">INLINE void compress_subtree_to_parent_node (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> uint8_t * input, size_t input_len, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> uint32_t key=[8], uint64_t chunk_counter, uint8_t flags, uint8_t out=[2 *BLAKE3_OUT_LEN])</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 338 of file <a href="/web-llvm/docs/api/files/lib/lib/support/lib/support/blake3/blake3-c">blake3.c</a>.</p>


<p>References <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/silowercontrolflow-cpp/#a4868c5d81c5ccc98c47aeab6244346a0">assert</a>, <a href="/web-llvm/docs/api/files/lib/lib/support/lib/support/blake3/llvm-blake3-prefix-h/#abcc4f732a672ef43bbfd2dc707e4d15e">BLAKE3_CHUNK_LEN</a>, <a href="#a6f1fd4d6d509893d09c8b8eb1aa5291c">blake3_compress_subtree_wide</a>, <a href="/web-llvm/docs/api/files/lib/lib/support/lib/support/blake3/llvm-blake3-prefix-h/#a54e230beb5e1d501702361fb91f399f0">BLAKE3_OUT_LEN</a>, <a href="#ab6b82b4dfe8b1cf5e6cdf18c4dd46097">compress_parents_parallel</a>, <a href="/web-llvm/docs/api/files/lib/lib/support/lib/support/blake3/blake3-impl-h/#a2eb6f9e0395b47b8d5e3eeae4fe0c116">INLINE</a> and <a href="/web-llvm/docs/api/files/lib/lib/support/lib/support/blake3/blake3-impl-h/#a8ee4a6d154e907312d4a54eb962388da">MAX_SIMD_DEGREE_OR_2</a>.</p>


<p>Referenced by <a href="#a63f3b0c97048b549ce37f5e6a4da701d">llvm_blake3_hasher_update</a>.</p>

</div>
</div>

### hasher\_init\_base() {#a3b12f6c109442edaa63ab03ba8a6caec}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">INLINE void hasher_init_base (<a href="/web-llvm/docs/api/files/lib/lib/support/lib/support/blake3/llvm-blake3-prefix-h/#a720ce7ad2dc122aeb214c6a5d4731f46">blake3_hasher</a> * self, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> uint32_t key=[8], uint8_t flags)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 367 of file <a href="/web-llvm/docs/api/files/lib/lib/support/lib/support/blake3/blake3-c">blake3.c</a>.</p>


<p>References <a href="/web-llvm/docs/api/files/lib/lib/support/lib/support/blake3/llvm-blake3-prefix-h/#a720ce7ad2dc122aeb214c6a5d4731f46">blake3_hasher</a>, <a href="/web-llvm/docs/api/files/lib/lib/support/lib/support/blake3/llvm-blake3-prefix-h/#a947bd80c6cdcbd362dd0760f3603abe6">BLAKE3_KEY_LEN</a>, <a href="#a4db94e2dcf16f8659a69b1636897baeb">chunk_state_init</a> and <a href="/web-llvm/docs/api/files/lib/lib/support/lib/support/blake3/blake3-impl-h/#a2eb6f9e0395b47b8d5e3eeae4fe0c116">INLINE</a>.</p>


<p>Referenced by <a href="#a3723853888e765d1049d9f3b9e48dfed">llvm_blake3_hasher_init</a>, <a href="#acf30a68b4c258e1c1af255c60e880aac">llvm_blake3_hasher_init_derive_key_raw</a> and <a href="#ac4c4231fe195d56ec58b572d0badc2e6">llvm_blake3_hasher_init_keyed</a>.</p>

</div>
</div>

### hasher\_merge\_cv\_stack() {#a63183e27546bc2e072233e0268400e83}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">INLINE void hasher_merge_cv_stack (<a href="/web-llvm/docs/api/files/lib/lib/support/lib/support/blake3/llvm-blake3-prefix-h/#a720ce7ad2dc122aeb214c6a5d4731f46">blake3_hasher</a> * self, uint64_t total_len)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 409 of file <a href="/web-llvm/docs/api/files/lib/lib/support/lib/support/blake3/blake3-c">blake3.c</a>.</p>


<p>References <a href="/web-llvm/docs/api/files/lib/lib/support/lib/support/blake3/llvm-blake3-prefix-h/#a720ce7ad2dc122aeb214c6a5d4731f46">blake3_hasher</a>, <a href="/web-llvm/docs/api/files/lib/lib/support/lib/support/blake3/llvm-blake3-prefix-h/#a54e230beb5e1d501702361fb91f399f0">BLAKE3_OUT_LEN</a>, <a href="/web-llvm/docs/api/files/lib/lib/support/lib/support/blake3/blake3-impl-h/#a2eb6f9e0395b47b8d5e3eeae4fe0c116">INLINE</a>, <a href="#a92376f69320e66a51477df2b47088249">output_chaining_value</a>, <a href="#ab18874614dade172d2726abc3e88d480">parent_output</a> and <a href="/web-llvm/docs/api/files/lib/lib/support/lib/support/blake3/blake3-impl-h/#a1817d7ef688b133f9befd300d9e971a0">popcnt</a>.</p>


<p>Referenced by <a href="#ae7004860c25afdef231d29688cfdb2ff">hasher_push_cv</a> and <a href="#a63f3b0c97048b549ce37f5e6a4da701d">llvm_blake3_hasher_update</a>.</p>

</div>
</div>

### hasher\_push\_cv() {#ae7004860c25afdef231d29688cfdb2ff}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">INLINE void hasher_push_cv (<a href="/web-llvm/docs/api/files/lib/lib/support/lib/support/blake3/llvm-blake3-prefix-h/#a720ce7ad2dc122aeb214c6a5d4731f46">blake3_hasher</a> * self, uint8_t new_cv=[BLAKE3_OUT_LEN], uint64_t chunk_counter)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 452 of file <a href="/web-llvm/docs/api/files/lib/lib/support/lib/support/blake3/blake3-c">blake3.c</a>.</p>


<p>References <a href="/web-llvm/docs/api/files/lib/lib/support/lib/support/blake3/llvm-blake3-prefix-h/#a720ce7ad2dc122aeb214c6a5d4731f46">blake3_hasher</a>, <a href="/web-llvm/docs/api/files/lib/lib/support/lib/support/blake3/llvm-blake3-prefix-h/#a54e230beb5e1d501702361fb91f399f0">BLAKE3_OUT_LEN</a>, <a href="#a63183e27546bc2e072233e0268400e83">hasher_merge_cv_stack</a> and <a href="/web-llvm/docs/api/files/lib/lib/support/lib/support/blake3/blake3-impl-h/#a2eb6f9e0395b47b8d5e3eeae4fe0c116">INLINE</a>.</p>


<p>Referenced by <a href="#a63f3b0c97048b549ce37f5e6a4da701d">llvm_blake3_hasher_update</a>.</p>

</div>
</div>

### left\_len() {#af1487a6d4f0aec866d05311a3e42ab30}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">INLINE size_t left_len (size_t content_len)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 162 of file <a href="/web-llvm/docs/api/files/lib/lib/support/lib/support/blake3/blake3-c">blake3.c</a>.</p>


<p>References <a href="/web-llvm/docs/api/files/lib/lib/support/lib/support/blake3/llvm-blake3-prefix-h/#abcc4f732a672ef43bbfd2dc707e4d15e">BLAKE3_CHUNK_LEN</a>, <a href="/web-llvm/docs/api/files/lib/lib/support/lib/support/blake3/blake3-impl-h/#a2eb6f9e0395b47b8d5e3eeae4fe0c116">INLINE</a> and <a href="/web-llvm/docs/api/files/lib/lib/support/lib/support/blake3/blake3-impl-h/#aa512c33323d4cb6599016c57337832fe">round_down_to_power_of_2</a>.</p>


<p>Referenced by <a href="#a6f1fd4d6d509893d09c8b8eb1aa5291c">blake3_compress_subtree_wide</a>.</p>

</div>
</div>

### llvm\_blake3\_hasher\_finalize() {#a6f1551c11ac8a08c294ee4bf7bf08623}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void llvm_blake3_hasher_finalize (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/files/lib/lib/support/lib/support/blake3/llvm-blake3-prefix-h/#a720ce7ad2dc122aeb214c6a5d4731f46">blake3_hasher</a> * self, uint8_t * out, size_t out_len)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 569 of file <a href="/web-llvm/docs/api/files/lib/lib/support/lib/support/blake3/blake3-c">blake3.c</a>.</p>


<p>References <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/support/compiler-h/#a7b6ebda5fec619759c0522722503be67">__msan_unpoison</a>, <a href="/web-llvm/docs/api/files/lib/lib/support/lib/support/blake3/llvm-blake3-prefix-h/#a720ce7ad2dc122aeb214c6a5d4731f46">blake3_hasher</a> and <a href="#ab6b397feba4ec3af8a0b09c3d7c5bffb">llvm_blake3_hasher_finalize_seek</a>.</p>


<p>Referenced by <a href="#acf30a68b4c258e1c1af255c60e880aac">llvm_blake3_hasher_init_derive_key_raw</a>.</p>

</div>
</div>

### llvm\_blake3\_hasher\_finalize\_seek() {#ab6b397feba4ec3af8a0b09c3d7c5bffb}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void llvm_blake3_hasher_finalize_seek (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/files/lib/lib/support/lib/support/blake3/llvm-blake3-prefix-h/#a720ce7ad2dc122aeb214c6a5d4731f46">blake3_hasher</a> * self, uint64_t seek, uint8_t * out, size_t out_len)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 578 of file <a href="/web-llvm/docs/api/files/lib/lib/support/lib/support/blake3/blake3-c">blake3.c</a>.</p>


<p>References <a href="/web-llvm/docs/api/files/lib/lib/support/lib/support/blake3/llvm-blake3-prefix-h/#a304cb82e31ff3dc5a4b02f7fce75555e">BLAKE3_BLOCK_LEN</a>, <a href="/web-llvm/docs/api/files/lib/lib/support/lib/support/blake3/llvm-blake3-prefix-h/#a720ce7ad2dc122aeb214c6a5d4731f46">blake3_hasher</a>, <a href="#a2c1ba208c88f9efdc6702769ecd006da">chunk_state_len</a>, <a href="#acc3e5ba813b5fb930b49c67f1edadf41">chunk_state_output</a>, <a href="#a92376f69320e66a51477df2b47088249">output_chaining_value</a>, <a href="#a0a194eae24fe95b572091dc7e992744f">output_root_bytes</a> and <a href="#ab18874614dade172d2726abc3e88d480">parent_output</a>.</p>


<p>Referenced by <a href="#a6f1551c11ac8a08c294ee4bf7bf08623">llvm_blake3_hasher_finalize</a>.</p>

</div>
</div>

### llvm\_blake3\_hasher\_init() {#a3723853888e765d1049d9f3b9e48dfed}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void llvm_blake3_hasher_init (<a href="/web-llvm/docs/api/files/lib/lib/support/lib/support/blake3/llvm-blake3-prefix-h/#a720ce7ad2dc122aeb214c6a5d4731f46">blake3_hasher</a> * self)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 374 of file <a href="/web-llvm/docs/api/files/lib/lib/support/lib/support/blake3/blake3-c">blake3.c</a>.</p>


<p>References <a href="/web-llvm/docs/api/files/lib/lib/support/lib/support/blake3/llvm-blake3-prefix-h/#a720ce7ad2dc122aeb214c6a5d4731f46">blake3_hasher</a>, <a href="#a3b12f6c109442edaa63ab03ba8a6caec">hasher_init_base</a> and <a href="/web-llvm/docs/api/files/lib/lib/support/lib/support/blake3/blake3-impl-h/#a78823051d1dad34b9b3d8120112e674d">IV</a>.</p>

</div>
</div>

### llvm\_blake3\_hasher\_init\_derive\_key() {#ad0b8fa0cf17c5aa764845fbd3739c85b}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void llvm_blake3_hasher_init_derive_key (<a href="/web-llvm/docs/api/files/lib/lib/support/lib/support/blake3/llvm-blake3-prefix-h/#a720ce7ad2dc122aeb214c6a5d4731f46">blake3_hasher</a> * self, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> char * context)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 395 of file <a href="/web-llvm/docs/api/files/lib/lib/support/lib/support/blake3/blake3-c">blake3.c</a>.</p>


<p>References <a href="/web-llvm/docs/api/files/lib/lib/support/lib/support/blake3/llvm-blake3-prefix-h/#a720ce7ad2dc122aeb214c6a5d4731f46">blake3_hasher</a> and <a href="#acf30a68b4c258e1c1af255c60e880aac">llvm_blake3_hasher_init_derive_key_raw</a>.</p>

</div>
</div>

### llvm\_blake3\_hasher\_init\_derive\_key\_raw() {#acf30a68b4c258e1c1af255c60e880aac}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void llvm_blake3_hasher_init_derive_key_raw (<a href="/web-llvm/docs/api/files/lib/lib/support/lib/support/blake3/llvm-blake3-prefix-h/#a720ce7ad2dc122aeb214c6a5d4731f46">blake3_hasher</a> * self, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> void * context, size_t context_len)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 383 of file <a href="/web-llvm/docs/api/files/lib/lib/support/lib/support/blake3/blake3-c">blake3.c</a>.</p>


<p>References <a href="/web-llvm/docs/api/files/lib/lib/support/lib/support/blake3/llvm-blake3-prefix-h/#a720ce7ad2dc122aeb214c6a5d4731f46">blake3_hasher</a>, <a href="/web-llvm/docs/api/files/lib/lib/support/lib/support/blake3/llvm-blake3-prefix-h/#a947bd80c6cdcbd362dd0760f3603abe6">BLAKE3_KEY_LEN</a>, <a href="/web-llvm/docs/api/files/lib/lib/support/lib/support/blake3/blake3-impl-h/#af1f12c808c513e84d39a88930812b5cba891ca3ed53dd8464f1aa3bc5ca792cce">DERIVE_KEY_CONTEXT</a>, <a href="/web-llvm/docs/api/files/lib/lib/support/lib/support/blake3/blake3-impl-h/#af1f12c808c513e84d39a88930812b5cba399b62381341913e02639d8e1d3e8744">DERIVE_KEY_MATERIAL</a>, <a href="#a3b12f6c109442edaa63ab03ba8a6caec">hasher_init_base</a>, <a href="/web-llvm/docs/api/files/lib/lib/support/lib/support/blake3/blake3-impl-h/#a78823051d1dad34b9b3d8120112e674d">IV</a>, <a href="#a6f1551c11ac8a08c294ee4bf7bf08623">llvm_blake3_hasher_finalize</a>, <a href="#a63f3b0c97048b549ce37f5e6a4da701d">llvm_blake3_hasher_update</a> and <a href="/web-llvm/docs/api/files/lib/lib/support/lib/support/blake3/blake3-impl-h/#a8b7b7d6918ecd7ddb8669390f1a321f4">load_key_words</a>.</p>


<p>Referenced by <a href="#ad0b8fa0cf17c5aa764845fbd3739c85b">llvm_blake3_hasher_init_derive_key</a>.</p>

</div>
</div>

### llvm\_blake3\_hasher\_init\_keyed() {#ac4c4231fe195d56ec58b572d0badc2e6}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void llvm_blake3_hasher_init_keyed (<a href="/web-llvm/docs/api/files/lib/lib/support/lib/support/blake3/llvm-blake3-prefix-h/#a720ce7ad2dc122aeb214c6a5d4731f46">blake3_hasher</a> * self, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> uint8_t key=[BLAKE3_KEY_LEN])</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 376 of file <a href="/web-llvm/docs/api/files/lib/lib/support/lib/support/blake3/blake3-c">blake3.c</a>.</p>


<p>References <a href="/web-llvm/docs/api/files/lib/lib/support/lib/support/blake3/llvm-blake3-prefix-h/#a720ce7ad2dc122aeb214c6a5d4731f46">blake3_hasher</a>, <a href="/web-llvm/docs/api/files/lib/lib/support/lib/support/blake3/llvm-blake3-prefix-h/#a947bd80c6cdcbd362dd0760f3603abe6">BLAKE3_KEY_LEN</a>, <a href="#a3b12f6c109442edaa63ab03ba8a6caec">hasher_init_base</a>, <a href="/web-llvm/docs/api/files/lib/lib/support/lib/support/blake3/blake3-impl-h/#af1f12c808c513e84d39a88930812b5cba372c16918d756eb61949611abeb28fa5">KEYED_HASH</a> and <a href="/web-llvm/docs/api/files/lib/lib/support/lib/support/blake3/blake3-impl-h/#a8b7b7d6918ecd7ddb8669390f1a321f4">load_key_words</a>.</p>

</div>
</div>

### llvm\_blake3\_hasher\_reset() {#a465d8d4d0fdcb5bf75858c000e3e54f0}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void llvm_blake3_hasher_reset (<a href="/web-llvm/docs/api/files/lib/lib/support/lib/support/blake3/llvm-blake3-prefix-h/#a720ce7ad2dc122aeb214c6a5d4731f46">blake3_hasher</a> * self)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 622 of file <a href="/web-llvm/docs/api/files/lib/lib/support/lib/support/blake3/blake3-c">blake3.c</a>.</p>


<p>References <a href="/web-llvm/docs/api/files/lib/lib/support/lib/support/blake3/llvm-blake3-prefix-h/#a720ce7ad2dc122aeb214c6a5d4731f46">blake3_hasher</a> and <a href="#ac3fec0f8016731502a8a1ad30cea4f3d">chunk_state_reset</a>.</p>

</div>
</div>

### llvm\_blake3\_hasher\_update() {#a63f3b0c97048b549ce37f5e6a4da701d}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void llvm_blake3_hasher_update (<a href="/web-llvm/docs/api/files/lib/lib/support/lib/support/blake3/llvm-blake3-prefix-h/#a720ce7ad2dc122aeb214c6a5d4731f46">blake3_hasher</a> * self, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> void * input, size_t input_len)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 460 of file <a href="/web-llvm/docs/api/files/lib/lib/support/lib/support/blake3/blake3-c">blake3.c</a>.</p>


<p>References <a href="/web-llvm/docs/api/files/lib/lib/support/lib/support/blake3/llvm-blake3-prefix-h/#abcc4f732a672ef43bbfd2dc707e4d15e">BLAKE3_CHUNK_LEN</a>, <a href="/web-llvm/docs/api/files/lib/lib/support/lib/support/blake3/llvm-blake3-prefix-h/#aed21153389299a4d7f8effa38ba58f3b">blake3_chunk_state</a>, <a href="/web-llvm/docs/api/files/lib/lib/support/lib/support/blake3/llvm-blake3-prefix-h/#a720ce7ad2dc122aeb214c6a5d4731f46">blake3_hasher</a>, <a href="/web-llvm/docs/api/files/lib/lib/support/lib/support/blake3/llvm-blake3-prefix-h/#a54e230beb5e1d501702361fb91f399f0">BLAKE3_OUT_LEN</a>, <a href="#a4db94e2dcf16f8659a69b1636897baeb">chunk_state_init</a>, <a href="#a2c1ba208c88f9efdc6702769ecd006da">chunk_state_len</a>, <a href="#acc3e5ba813b5fb930b49c67f1edadf41">chunk_state_output</a>, <a href="#ac3fec0f8016731502a8a1ad30cea4f3d">chunk_state_reset</a>, <a href="#a1c4270490e141bac2a6053af9ef01f6b">chunk_state_update</a>, <a href="#abd0aa960e3f0e3ebab8baccea1f3808a">compress_subtree_to_parent_node</a>, <a href="#a63183e27546bc2e072233e0268400e83">hasher_merge_cv_stack</a>, <a href="#ae7004860c25afdef231d29688cfdb2ff">hasher_push_cv</a>, <a href="#a92376f69320e66a51477df2b47088249">output_chaining_value</a> and <a href="/web-llvm/docs/api/files/lib/lib/support/lib/support/blake3/blake3-impl-h/#aa512c33323d4cb6599016c57337832fe">round_down_to_power_of_2</a>.</p>


<p>Referenced by <a href="#acf30a68b4c258e1c1af255c60e880aac">llvm_blake3_hasher_init_derive_key_raw</a>.</p>

</div>
</div>

### llvm\_blake3\_version() {#ab9d435f061dc1e6e693d1d4886250754}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">const char * llvm_blake3_version (void)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 15 of file <a href="/web-llvm/docs/api/files/lib/lib/support/lib/support/blake3/blake3-c">blake3.c</a>.</p>


<p>Reference <a href="/web-llvm/docs/api/files/lib/lib/support/lib/support/blake3/llvm-blake3-prefix-h/#a98986aaaab2221d6639d3e60f3682a91">BLAKE3_VERSION_STRING</a>.</p>

</div>
</div>

### make\_output() {#a0fb8691f907fe586830601d486049e6e}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">INLINE output_t make_output (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> uint32_t input_cv=[8], <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> uint8_t block=[BLAKE3_BLOCK_LEN], uint8_t block_len, uint64_t counter, uint8_t flags)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 69 of file <a href="/web-llvm/docs/api/files/lib/lib/support/lib/support/blake3/blake3-c">blake3.c</a>.</p>


<p>References <a href="/web-llvm/docs/api/files/lib/lib/support/lib/support/blake3/llvm-blake3-prefix-h/#a304cb82e31ff3dc5a4b02f7fce75555e">BLAKE3_BLOCK_LEN</a>, <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/utils/unifyloopexits-cpp/#a4741a07a0e5675f89cfed122008e0a76">block</a>, <a href="/web-llvm/docs/api/structs/output-t/#a67fd92399759962d96519544c737be99">output_t::block</a>, <a href="/web-llvm/docs/api/structs/output-t/#a1e73cd9626b6c0a7960af035596dbf7c">output_t::block_len</a>, <a href="/web-llvm/docs/api/structs/output-t/#ab9a8543fae164eece122f39bcdaa0bf7">output_t::counter</a>, <a href="/web-llvm/docs/api/structs/output-t/#abab5d28213b91ed5b976aa4eef0f6384">output_t::flags</a>, <a href="/web-llvm/docs/api/files/lib/lib/support/lib/support/blake3/blake3-impl-h/#a2eb6f9e0395b47b8d5e3eeae4fe0c116">INLINE</a> and <a href="/web-llvm/docs/api/structs/output-t/#ac4f9eca5e279f34c50f6e70ad449a897">output_t::input_cv</a>.</p>


<p>Referenced by <a href="#acc3e5ba813b5fb930b49c67f1edadf41">chunk_state_output</a> and <a href="#ab18874614dade172d2726abc3e88d480">parent_output</a>.</p>

</div>
</div>

### output\_chaining\_value() {#a92376f69320e66a51477df2b47088249}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">INLINE void output_chaining_value (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/structs/output-t">output_t</a> * self, uint8_t cv=[32])</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 88 of file <a href="/web-llvm/docs/api/files/lib/lib/support/lib/support/blake3/blake3-c">blake3.c</a>.</p>


<p>References <a href="/web-llvm/docs/api/files/lib/lib/support/lib/support/blake3/llvm-blake3-prefix-h/#a720451c4882eb74f48bb24d1af5b7368">blake3_compress_in_place</a>, <a href="/web-llvm/docs/api/structs/output-t/#a67fd92399759962d96519544c737be99">output_t::block</a>, <a href="/web-llvm/docs/api/structs/output-t/#a1e73cd9626b6c0a7960af035596dbf7c">output_t::block_len</a>, <a href="/web-llvm/docs/api/structs/output-t/#ab9a8543fae164eece122f39bcdaa0bf7">output_t::counter</a>, <a href="/web-llvm/docs/api/structs/output-t/#abab5d28213b91ed5b976aa4eef0f6384">output_t::flags</a>, <a href="/web-llvm/docs/api/files/lib/lib/support/lib/support/blake3/blake3-impl-h/#a2eb6f9e0395b47b8d5e3eeae4fe0c116">INLINE</a>, <a href="/web-llvm/docs/api/structs/output-t/#ac4f9eca5e279f34c50f6e70ad449a897">output_t::input_cv</a> and <a href="/web-llvm/docs/api/files/lib/lib/support/lib/support/blake3/blake3-impl-h/#aa2fffe259ee56abc321b02c9790a6dfa">store_cv_words</a>.</p>


<p>Referenced by <a href="#a5b7c95b4370497f963cb03981f87613f">compress_chunks_parallel</a>, <a href="#a63183e27546bc2e072233e0268400e83">hasher_merge_cv_stack</a>, <a href="#ab6b397feba4ec3af8a0b09c3d7c5bffb">llvm_blake3_hasher_finalize_seek</a> and <a href="#a63f3b0c97048b549ce37f5e6a4da701d">llvm_blake3_hasher_update</a>.</p>

</div>
</div>

### output\_root\_bytes() {#a0a194eae24fe95b572091dc7e992744f}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">INLINE void output_root_bytes (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/structs/output-t">output_t</a> * self, uint64_t seek, uint8_t * out, size_t out_len)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 96 of file <a href="/web-llvm/docs/api/files/lib/lib/support/lib/support/blake3/blake3-c">blake3.c</a>.</p>


<p>References <a href="/web-llvm/docs/api/files/lib/lib/support/lib/support/blake3/llvm-blake3-prefix-h/#a4a33a8bd63bbab7dc6625881ecf9cf4b">blake3_compress_xof</a>, <a href="/web-llvm/docs/api/structs/output-t/#a67fd92399759962d96519544c737be99">output_t::block</a>, <a href="/web-llvm/docs/api/structs/output-t/#a1e73cd9626b6c0a7960af035596dbf7c">output_t::block_len</a>, <a href="/web-llvm/docs/api/structs/output-t/#abab5d28213b91ed5b976aa4eef0f6384">output_t::flags</a>, <a href="/web-llvm/docs/api/files/lib/lib/support/lib/support/blake3/blake3-impl-h/#a2eb6f9e0395b47b8d5e3eeae4fe0c116">INLINE</a>, <a href="/web-llvm/docs/api/structs/output-t/#ac4f9eca5e279f34c50f6e70ad449a897">output_t::input_cv</a> and <a href="/web-llvm/docs/api/files/lib/lib/support/lib/support/blake3/blake3-impl-h/#af1f12c808c513e84d39a88930812b5cbad41208b99e347d1726824779b11ea11b">ROOT</a>.</p>


<p>Referenced by <a href="#ab6b397feba4ec3af8a0b09c3d7c5bffb">llvm_blake3_hasher_finalize_seek</a>.</p>

</div>
</div>

### parent\_output() {#ab18874614dade172d2726abc3e88d480}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">INLINE output_t parent_output (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> uint8_t block=[BLAKE3_BLOCK_LEN], <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> uint32_t key=[8], uint8_t flags)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 154 of file <a href="/web-llvm/docs/api/files/lib/lib/support/lib/support/blake3/blake3-c">blake3.c</a>.</p>


<p>References <a href="/web-llvm/docs/api/files/lib/lib/support/lib/support/blake3/llvm-blake3-prefix-h/#a304cb82e31ff3dc5a4b02f7fce75555e">BLAKE3_BLOCK_LEN</a>, <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/utils/unifyloopexits-cpp/#a4741a07a0e5675f89cfed122008e0a76">block</a>, <a href="/web-llvm/docs/api/files/lib/lib/support/lib/support/blake3/blake3-impl-h/#a2eb6f9e0395b47b8d5e3eeae4fe0c116">INLINE</a>, <a href="#a0fb8691f907fe586830601d486049e6e">make_output</a> and <a href="/web-llvm/docs/api/files/lib/lib/support/lib/support/blake3/blake3-impl-h/#af1f12c808c513e84d39a88930812b5cba283df3974c567b21c067198a24cd78e6">PARENT</a>.</p>


<p>Referenced by <a href="#a63183e27546bc2e072233e0268400e83">hasher_merge_cv_stack</a> and <a href="#ab6b397feba4ec3af8a0b09c3d7c5bffb">llvm_blake3_hasher_finalize_seek</a>.</p>

</div>
</div>

</div>

<hr/>

<p class="doxyGeneratedBy">Generated via <a href="https://xpack.github.io/doxygen2docusaurus">doxygen2docusaurus</a> 2.0.0 by <a href="https://www.doxygen.nl">Doxygen</a> 1.15.0.</p>

</div>
