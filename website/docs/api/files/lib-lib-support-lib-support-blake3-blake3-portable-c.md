---

# DO NOT EDIT!
# Automatically generated via doxygen2docusaurus by Doxygen.

slug: /api/files/lib/lib/support/lib/support/blake3/blake3-portable-c
custom_edit_url: null
toc_max_heading_level: 4
keywords:
  - doxygen
  - reference
  - file

---

<div class="doxyPage">

# The `blake3_portable.c` File Reference



## Included Headers

<div class="doxyIncludesList">#include "<a href="/web-llvm/docs/api/files/lib/lib/support/lib/support/blake3/blake3-impl-h">blake3_impl.h</a>"
#include &lt;string.h&gt;
</div>

## Functions Index

<table class="doxyMembersIndex">

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/files/lib/lib/support/lib/support/blake3/blake3-impl-h/#a2eb6f9e0395b47b8d5e3eeae4fe0c116">INLINE</a> uint32_t</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a6f58e26940444cd577b8c7571d01bb77">rotr32</a> (uint32_t w, uint32_t c)</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ab5958fad499ed692422c66bb20000a39">g</a> (uint32_t *state, size_t a, size_t b, size_t c, size_t d, uint32_t x, uint32_t y)</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a87355412d6387311f7e404e04ecd5ed0">round_fn</a> (uint32_t state[16], const uint32_t *msg, size_t round)</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#adc0ded568b1b0f6df58f6d25a7212782">compress_pre</a> (uint32_t state[16], const uint32_t cv[8], const uint8_t block[BLAKE3_BLOCK_LEN], uint8_t block_len, uint64_t counter, uint8_t flags)</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a5bcdf52929f05e74d638faaa151f71ee">blake3_compress_in_place_portable</a> (uint32_t cv[8], const uint8_t block[BLAKE3_BLOCK_LEN], uint8_t block_len, uint64_t counter, uint8_t flags)</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a7ffc2926e21f55b48551bc371914946c">blake3_compress_xof_portable</a> (const uint32_t cv[8], const uint8_t block[BLAKE3_BLOCK_LEN], uint8_t block_len, uint64_t counter, uint8_t flags, uint8_t out[64])</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ac500a9f4a684624f44bfa36853747379">hash_one_portable</a> (const uint8_t *input, size_t blocks, const uint32_t key[8], uint64_t counter, uint8_t flags, uint8_t flags_start, uint8_t flags_end, uint8_t out[BLAKE3_OUT_LEN])</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a98f09f75b6ee3057c2c983542432423c">blake3_hash_many_portable</a> (const uint8_t *const *inputs, size_t num_inputs, size_t blocks, const uint32_t key[8], uint64_t counter, bool increment_counter, uint8_t flags, uint8_t flags_start, uint8_t flags_end, uint8_t *out)</td>
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

### blake3\_compress\_in\_place\_portable() {#a5bcdf52929f05e74d638faaa151f71ee}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void blake3_compress_in_place_portable (uint32_t cv=[8], <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> uint8_t block=[BLAKE3_BLOCK_LEN], uint8_t block_len, uint64_t counter, uint8_t flags)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 84 of file <a href="/web-llvm/docs/api/files/lib/lib/support/lib/support/blake3/blake3-portable-c">blake3_portable.c</a>.</p>


<p>References <a href="/web-llvm/docs/api/files/lib/lib/support/lib/support/blake3/llvm-blake3-prefix-h/#a304cb82e31ff3dc5a4b02f7fce75555e">BLAKE3_BLOCK_LEN</a>, <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/utils/unifyloopexits-cpp/#a4741a07a0e5675f89cfed122008e0a76">block</a> and <a href="#adc0ded568b1b0f6df58f6d25a7212782">compress_pre</a>.</p>

</div>
</div>

### blake3\_compress\_xof\_portable() {#a7ffc2926e21f55b48551bc371914946c}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void blake3_compress_xof_portable (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> uint32_t cv=[8], <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> uint8_t block=[BLAKE3_BLOCK_LEN], uint8_t block_len, uint64_t counter, uint8_t flags, uint8_t out=[64])</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 100 of file <a href="/web-llvm/docs/api/files/lib/lib/support/lib/support/blake3/blake3-portable-c">blake3_portable.c</a>.</p>


<p>References <a href="/web-llvm/docs/api/files/lib/lib/support/lib/support/blake3/llvm-blake3-prefix-h/#a304cb82e31ff3dc5a4b02f7fce75555e">BLAKE3_BLOCK_LEN</a>, <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/utils/unifyloopexits-cpp/#a4741a07a0e5675f89cfed122008e0a76">block</a>, <a href="#adc0ded568b1b0f6df58f6d25a7212782">compress_pre</a> and <a href="/web-llvm/docs/api/files/lib/lib/support/lib/support/blake3/blake3-impl-h/#ab44a2b80e38a954a29e770c0dceb14c0">store32</a>.</p>

</div>
</div>

### blake3\_hash\_many\_portable() {#a98f09f75b6ee3057c2c983542432423c}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void blake3_hash_many_portable (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> uint8_t *<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> * inputs, size_t num_inputs, size_t blocks, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> uint32_t key=[8], uint64_t counter, bool increment_counter, uint8_t flags, uint8_t flags_start, uint8_t flags_end, uint8_t * out)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 145 of file <a href="/web-llvm/docs/api/files/lib/lib/support/lib/support/blake3/blake3-portable-c">blake3_portable.c</a>.</p>


<p>References <a href="/web-llvm/docs/api/files/lib/lib/support/lib/support/blake3/llvm-blake3-prefix-h/#a54e230beb5e1d501702361fb91f399f0">BLAKE3_OUT_LEN</a>, <a href="/web-llvm/docs/api/files/lib/lib/codegen/basicblocksections-cpp/#a6b480a971048f2d9cc342c18046d7774">blocks</a> and <a href="#ac500a9f4a684624f44bfa36853747379">hash_one_portable</a>.</p>

</div>
</div>

### compress\_pre() {#adc0ded568b1b0f6df58f6d25a7212782}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">INLINE void compress_pre (uint32_t state=[16], <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> uint32_t cv=[8], <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> uint8_t block=[BLAKE3_BLOCK_LEN], uint8_t block_len, uint64_t counter, uint8_t flags)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 37 of file <a href="/web-llvm/docs/api/files/lib/lib/support/lib/support/blake3/blake3-portable-c">blake3_portable.c</a>.</p>


<p>References <a href="/web-llvm/docs/api/files/lib/lib/support/lib/support/blake3/llvm-blake3-prefix-h/#a304cb82e31ff3dc5a4b02f7fce75555e">BLAKE3_BLOCK_LEN</a>, <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/utils/unifyloopexits-cpp/#a4741a07a0e5675f89cfed122008e0a76">block</a>, <a href="/web-llvm/docs/api/files/lib/lib/support/lib/support/blake3/blake3-impl-h/#a7ec7b2f404362ce5bc1198981707bc7e">counter_high</a>, <a href="/web-llvm/docs/api/files/lib/lib/support/lib/support/blake3/blake3-impl-h/#afeab7ac9eaa036d9400491885ab6c6eb">counter_low</a>, <a href="/web-llvm/docs/api/files/lib/lib/support/lib/support/blake3/blake3-impl-h/#a2eb6f9e0395b47b8d5e3eeae4fe0c116">INLINE</a>, <a href="/web-llvm/docs/api/files/lib/lib/support/lib/support/blake3/blake3-impl-h/#a78823051d1dad34b9b3d8120112e674d">IV</a>, <a href="/web-llvm/docs/api/files/lib/lib/support/lib/support/blake3/blake3-impl-h/#ab1c895f6566413585caf53c2a945c644">load32</a> and <a href="#a87355412d6387311f7e404e04ecd5ed0">round_fn</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/files/lib/lib/support/lib/support/blake3/blake3-impl-h/#a5f1cca60c3c099efd97cafcc542eb4e7">blake3_compress_in_place_portable</a> and <a href="/web-llvm/docs/api/files/lib/lib/support/lib/support/blake3/blake3-impl-h/#a9b4b1cdf0d88ad62854fd20cc10c1558">blake3_compress_xof_portable</a>.</p>

</div>
</div>

### g() {#ab5958fad499ed692422c66bb20000a39}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">INLINE void g (uint32_t * state, size_t a, size_t b, size_t c, size_t d, uint32_t x, uint32_t y)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 8 of file <a href="/web-llvm/docs/api/files/lib/lib/support/lib/support/blake3/blake3-portable-c">blake3_portable.c</a>.</p>


<p>References <a href="/web-llvm/docs/api/files/lib/lib/support/lib/support/blake3/blake3-impl-h/#a2eb6f9e0395b47b8d5e3eeae4fe0c116">INLINE</a> and <a href="#a6f58e26940444cd577b8c7571d01bb77">rotr32</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/files/lib/lib/support/regcomp-c/#a7f555d714dea35fa2b3e00c2e727d0af">categorize</a>, <a href="/web-llvm/docs/api/files/lib/lib/support/regcomp-c/#acf3f78aff4143b42112848d8f0dd4d7a">findmust</a>, <a href="/web-llvm/docs/api/classes/llvm/graphwriter/#a8f3255aa53263dcfb993530f114ad7e0">llvm::GraphWriter&lt; GraphType &gt;::GraphWriter</a>, <a href="/web-llvm/docs/api/files/lib/lib/support/regcomp-c/#a988069e7f476c7dd06254b88d0a67d5a">isinsets</a>, <a href="/web-llvm/docs/api/structs/llvm/rdf/liveness/#a4b9cd23a5c66dc74c7abbd796884654c">llvm::rdf::Liveness::Liveness</a>, <a href="/web-llvm/docs/api/files/lib/lib/support/regcomp-c/#a94efd6ce730ab2988bfd211af4319873">llvm_regcomp</a>, <a href="/web-llvm/docs/api/files/lib/lib/support/regex-impl-h/#a91460c195c399d42fa14fbb37d0465a3">llvm_regexec</a>, <a href="/web-llvm/docs/api/files/lib/lib/support/regex-impl-h/#a5b067957e932003b295ff3a8bbffe882">llvm_regfree</a>, <a href="/web-llvm/docs/api/files/lib/lib/support/regcomp-c/#a37b2c71be1bd09705bd8e3fa728c6b57">p_ere_exp</a>, <a href="/web-llvm/docs/api/files/lib/lib/support/regcomp-c/#aee283f9c02a8848c8782c35713aad80c">p_simp_re</a>, <a href="/web-llvm/docs/api/files/lib/lib/support/regcomp-c/#ab868fc2a09cae3dc9ae25baea08db7a4">pluscount</a>, <a href="/web-llvm/docs/api/structs/llvm/rdf/print/#a6ad9041c2932aefb8d88f5e1d8999b63">llvm::rdf::Print&lt; T &gt;::Print</a>, <a href="/web-llvm/docs/api/structs/llvm/rdf/printnode/#a7154ec686647736226910cd55a54583d">llvm::rdf::PrintNode&lt; T &gt;::PrintNode</a>, <a href="#a87355412d6387311f7e404e04ecd5ed0">round_fn</a>, <a href="/web-llvm/docs/api/files/lib/lib/support/regcomp-c/#a0a11d04bd61f8c45fc80d7630133cf40">samesets</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a457abdc792a2b697c1031f09edb8492f">llvm::shuffle</a> and <a href="/web-llvm/docs/api/files/lib/lib/support/regcomp-c/#a0b3b7588a93de41b3dd6640e62787e2e">stripsnug</a>.</p>

</div>
</div>

### hash\_one\_portable() {#ac500a9f4a684624f44bfa36853747379}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">INLINE void hash_one_portable (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> uint8_t * input, size_t blocks, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> uint32_t key=[8], uint64_t counter, uint8_t flags, uint8_t flags_start, uint8_t flags_end, uint8_t out=[BLAKE3_OUT_LEN])</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 125 of file <a href="/web-llvm/docs/api/files/lib/lib/support/lib/support/blake3/blake3-portable-c">blake3_portable.c</a>.</p>


<p>References <a href="/web-llvm/docs/api/files/lib/lib/support/lib/support/blake3/llvm-blake3-prefix-h/#a304cb82e31ff3dc5a4b02f7fce75555e">BLAKE3_BLOCK_LEN</a>, <a href="/web-llvm/docs/api/files/lib/lib/support/lib/support/blake3/llvm-blake3-prefix-h/#ae2b22a1d466bc72087370c1b09ad2756">blake3_compress_in_place_portable</a>, <a href="/web-llvm/docs/api/files/lib/lib/support/lib/support/blake3/llvm-blake3-prefix-h/#a947bd80c6cdcbd362dd0760f3603abe6">BLAKE3_KEY_LEN</a>, <a href="/web-llvm/docs/api/files/lib/lib/support/lib/support/blake3/llvm-blake3-prefix-h/#a54e230beb5e1d501702361fb91f399f0">BLAKE3_OUT_LEN</a>, <a href="/web-llvm/docs/api/files/lib/lib/codegen/basicblocksections-cpp/#a6b480a971048f2d9cc342c18046d7774">blocks</a>, <a href="/web-llvm/docs/api/files/lib/lib/support/lib/support/blake3/blake3-impl-h/#a2eb6f9e0395b47b8d5e3eeae4fe0c116">INLINE</a> and <a href="/web-llvm/docs/api/files/lib/lib/support/lib/support/blake3/blake3-impl-h/#aa2fffe259ee56abc321b02c9790a6dfa">store_cv_words</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/files/lib/lib/support/lib/support/blake3/blake3-impl-h/#a6445e4f293da8868e140464290107427">blake3_hash_many_portable</a>.</p>

</div>
</div>

### rotr32() {#a6f58e26940444cd577b8c7571d01bb77}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">INLINE uint32_t rotr32 (uint32_t w, uint32_t c)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 4 of file <a href="/web-llvm/docs/api/files/lib/lib/support/lib/support/blake3/blake3-portable-c">blake3_portable.c</a>.</p>


<p>Reference <a href="/web-llvm/docs/api/files/lib/lib/support/lib/support/blake3/blake3-impl-h/#a2eb6f9e0395b47b8d5e3eeae4fe0c116">INLINE</a>.</p>


<p>Referenced by <a href="#ab5958fad499ed692422c66bb20000a39">g</a>.</p>

</div>
</div>

### round\_fn() {#a87355412d6387311f7e404e04ecd5ed0}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">INLINE void round_fn (uint32_t state=[16], <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> uint32_t * msg, size_t round)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 20 of file <a href="/web-llvm/docs/api/files/lib/lib/support/lib/support/blake3/blake3-portable-c">blake3_portable.c</a>.</p>


<p>References <a href="#ab5958fad499ed692422c66bb20000a39">g</a>, <a href="/web-llvm/docs/api/files/lib/lib/support/lib/support/blake3/blake3-impl-h/#a2eb6f9e0395b47b8d5e3eeae4fe0c116">INLINE</a>, <a href="/web-llvm/docs/api/files/lib/lib/support/lib/support/blake3/blake3-impl-h/#a0683f2191826e5431f112c71a12b7908">MSG_SCHEDULE</a> and <a href="/web-llvm/docs/api/files/lib/lib/support/xxhash-cpp/#ae4e947c75dafebd71b8de03cd0dbf5d6">round</a>.</p>


<p>Referenced by <a href="#adc0ded568b1b0f6df58f6d25a7212782">compress_pre</a>.</p>

</div>
</div>

</div>

<hr/>

<p class="doxyGeneratedBy">Generated via <a href="https://github.com/xpack/doxygen2docusaurus">doxygen2docusaurus</a> by <a href="https://www.doxygen.nl">Doxygen</a> 1.15.0.</p>

</div>
