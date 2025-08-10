---

# DO NOT EDIT!
# Automatically generated via doxygen2docusaurus by Doxygen.

slug: /api/files/lib/lib/support/lib/support/blake3/blake3-dispatch-c
custom_edit_url: null
toc_max_heading_level: 4
keywords:
  - doxygen
  - reference
  - file

---

<div class="doxyPage">

# `blake3_dispatch.c` File



## Included Headers

<div class="doxyIncludesList">#include &lt;stdbool.h&gt;
#include &lt;stddef.h&gt;
#include &lt;stdint.h&gt;
#include "<a href="/web-llvm/docs/api/files/lib/lib/support/lib/support/blake3/blake3-impl-h">blake3_impl.h</a>"
</div>

## Enumerations Index

<table class="doxyMembersIndex">

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">enum</td>
<td class="doxyMemberIndexItemName" align="left" valign="top">cpu_feature { <a href="#a6efa629275df21393eef82e3bf972460">...</a> }</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">static <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/support/compiler-h/#a6881c00738b22a600dfee25a1c32dab3">LLVM_ATTRIBUTE_USED</a> enum <a href="#a6efa629275df21393eef82e3bf972460">cpu_feature</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a66b3e1af9044caa59fc75f60f72ee8e4">get_cpu_features</a> (void)</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ae806b06af6fd96ce3036e82a66a972fc">blake3_compress_in_place</a> (uint32_t cv[8], const uint8_t block[BLAKE3_BLOCK_LEN], uint8_t block_len, uint64_t counter, uint8_t flags)</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#aa7ad14d63d0421eb5638eac60a4faff2">blake3_compress_xof</a> (const uint32_t cv[8], const uint8_t block[BLAKE3_BLOCK_LEN], uint8_t block_len, uint64_t counter, uint8_t flags, uint8_t out[64])</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#aa719af4ac5bfa12c07fce4e03d654400">blake3_hash_many</a> (const uint8_t *const *inputs, size_t num_inputs, size_t blocks, const uint32_t key[8], uint64_t counter, bool increment_counter, uint8_t flags, uint8_t flags_start, uint8_t flags_end, uint8_t *out)</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">size_t</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a49b18dbf52f8c1a6ad492a2b1f3a0ca5">blake3_simd_degree</a> (void)</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">static enum <a href="#a6efa629275df21393eef82e3bf972460">cpu_feature</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a5501a9f880066178c676be718e8a5d0a">g_cpu_features</a> = <a href="#a6efa629275df21393eef82e3bf972460a605159e8a4c32319fd69b5d151369d93">UNDEFINED</a></td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a3282fda96b0ba454bf4a8254c41e466a">MAYBE_UNUSED</a>(x)&nbsp;&nbsp;&nbsp;(void)((x))</td>
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

### cpu\_feature {#a6efa629275df21393eef82e3bf972460}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">enum cpu_feature </td>
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
<td class="doxyEnumItemName">SSE2<a id="a6efa629275df21393eef82e3bf972460a8d896e4fb625a47eaa49059a390971df"></a></td>
<td class="doxyEnumItemDescription"> (= 1 &lt;&lt; 0)</td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">SSSE3<a id="a6efa629275df21393eef82e3bf972460a3bf865c30966497ad2f666485802e94b"></a></td>
<td class="doxyEnumItemDescription"> (= 1 &lt;&lt; 1)</td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">SSE41<a id="a6efa629275df21393eef82e3bf972460a220a8c2c340905b520fa539836209d55"></a></td>
<td class="doxyEnumItemDescription"> (= 1 &lt;&lt; 2)</td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">AVX<a id="a6efa629275df21393eef82e3bf972460a0f2500907bbad2fb795fba8fafd31b2a"></a></td>
<td class="doxyEnumItemDescription"> (= 1 &lt;&lt; 3)</td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">AVX2<a id="a6efa629275df21393eef82e3bf972460a7b9822126e7b712535af7b882409bf8b"></a></td>
<td class="doxyEnumItemDescription"> (= 1 &lt;&lt; 4)</td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">AVX512F<a id="a6efa629275df21393eef82e3bf972460a698bc47a8c40306f69be562fbc5119fb"></a></td>
<td class="doxyEnumItemDescription"> (= 1 &lt;&lt; 5)</td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">AVX512VL<a id="a6efa629275df21393eef82e3bf972460a265a413615d057502fd743b974730e0e"></a></td>
<td class="doxyEnumItemDescription"> (= 1 &lt;&lt; 6)</td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">UNDEFINED<a id="a6efa629275df21393eef82e3bf972460a605159e8a4c32319fd69b5d151369d93"></a></td>
<td class="doxyEnumItemDescription"> (= 1 &lt;&lt; 30)</td>
</tr>

</table>
</dd>
</dl>

<p>Definition at line 64 of file <a href="/web-llvm/docs/api/files/lib/lib/support/lib/support/blake3/blake3-dispatch-c">blake3_dispatch.c</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Functions

### blake3\_compress\_in\_place() {#ae806b06af6fd96ce3036e82a66a972fc}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void blake3_compress_in_place (uint32_t cv=[8], <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> uint8_t block=[BLAKE3_BLOCK_LEN], uint8_t block_len, uint64_t counter, uint8_t flags)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 137 of file <a href="/web-llvm/docs/api/files/lib/lib/support/lib/support/blake3/blake3-dispatch-c">blake3_dispatch.c</a>.</p>


<p>References <a href="#a6efa629275df21393eef82e3bf972460a265a413615d057502fd743b974730e0e">AVX512VL</a>, <a href="/web-llvm/docs/api/files/lib/lib/support/lib/support/blake3/llvm-blake3-prefix-h/#a304cb82e31ff3dc5a4b02f7fce75555e">BLAKE3_BLOCK_LEN</a>, <a href="/web-llvm/docs/api/files/lib/lib/support/lib/support/blake3/llvm-blake3-prefix-h/#af94d87a1e3c7e9fa1f8a83b81893f322">blake3_compress_in_place_avx512</a>, <a href="/web-llvm/docs/api/files/lib/lib/support/lib/support/blake3/llvm-blake3-prefix-h/#ae2b22a1d466bc72087370c1b09ad2756">blake3_compress_in_place_portable</a>, <a href="/web-llvm/docs/api/files/lib/lib/support/lib/support/blake3/llvm-blake3-prefix-h/#a686b949247a2ca54dbe0202b6b69d441">blake3_compress_in_place_sse2</a>, <a href="/web-llvm/docs/api/files/lib/lib/support/lib/support/blake3/llvm-blake3-prefix-h/#a02eaea0cccda6df21b4d6793d3fc61de">blake3_compress_in_place_sse41</a>, <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/utils/unifyloopexits-cpp/#a4741a07a0e5675f89cfed122008e0a76">block</a>, <a href="#a66b3e1af9044caa59fc75f60f72ee8e4">get_cpu_features</a>, <a href="#a3282fda96b0ba454bf4a8254c41e466a">MAYBE_UNUSED</a>, <a href="#a6efa629275df21393eef82e3bf972460a8d896e4fb625a47eaa49059a390971df">SSE2</a> and <a href="#a6efa629275df21393eef82e3bf972460a220a8c2c340905b520fa539836209d55">SSE41</a>.</p>

</div>
</div>

### blake3\_compress\_xof() {#aa7ad14d63d0421eb5638eac60a4faff2}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void blake3_compress_xof (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> uint32_t cv=[8], <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> uint8_t block=[BLAKE3_BLOCK_LEN], uint8_t block_len, uint64_t counter, uint8_t flags, uint8_t out=[64])</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 166 of file <a href="/web-llvm/docs/api/files/lib/lib/support/lib/support/blake3/blake3-dispatch-c">blake3_dispatch.c</a>.</p>


<p>References <a href="#a6efa629275df21393eef82e3bf972460a265a413615d057502fd743b974730e0e">AVX512VL</a>, <a href="/web-llvm/docs/api/files/lib/lib/support/lib/support/blake3/llvm-blake3-prefix-h/#a304cb82e31ff3dc5a4b02f7fce75555e">BLAKE3_BLOCK_LEN</a>, <a href="/web-llvm/docs/api/files/lib/lib/support/lib/support/blake3/llvm-blake3-prefix-h/#a78a4c9adffa375af3169dc2204b8d80f">blake3_compress_xof_avx512</a>, <a href="/web-llvm/docs/api/files/lib/lib/support/lib/support/blake3/llvm-blake3-prefix-h/#a9daf63c58deb178310661d2154195b15">blake3_compress_xof_portable</a>, <a href="/web-llvm/docs/api/files/lib/lib/support/lib/support/blake3/llvm-blake3-prefix-h/#a2e0ee76a977bb5a3267115af768d601d">blake3_compress_xof_sse2</a>, <a href="/web-llvm/docs/api/files/lib/lib/support/lib/support/blake3/llvm-blake3-prefix-h/#a57629035a0b0d5c75e599848a1791ee3">blake3_compress_xof_sse41</a>, <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/utils/unifyloopexits-cpp/#a4741a07a0e5675f89cfed122008e0a76">block</a>, <a href="#a66b3e1af9044caa59fc75f60f72ee8e4">get_cpu_features</a>, <a href="#a3282fda96b0ba454bf4a8254c41e466a">MAYBE_UNUSED</a>, <a href="#a6efa629275df21393eef82e3bf972460a8d896e4fb625a47eaa49059a390971df">SSE2</a> and <a href="#a6efa629275df21393eef82e3bf972460a220a8c2c340905b520fa539836209d55">SSE41</a>.</p>

</div>
</div>

### blake3\_hash\_many() {#aa719af4ac5bfa12c07fce4e03d654400}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void blake3_hash_many (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> uint8_t *<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> * inputs, size_t num_inputs, size_t blocks, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> uint32_t key=[8], uint64_t counter, bool increment_counter, uint8_t flags, uint8_t flags_start, uint8_t flags_end, uint8_t * out)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 195 of file <a href="/web-llvm/docs/api/files/lib/lib/support/lib/support/blake3/blake3-dispatch-c">blake3_dispatch.c</a>.</p>


<p>References <a href="#a6efa629275df21393eef82e3bf972460a7b9822126e7b712535af7b882409bf8b">AVX2</a>, <a href="#a6efa629275df21393eef82e3bf972460a698bc47a8c40306f69be562fbc5119fb">AVX512F</a>, <a href="#a6efa629275df21393eef82e3bf972460a265a413615d057502fd743b974730e0e">AVX512VL</a>, <a href="/web-llvm/docs/api/files/lib/lib/support/lib/support/blake3/llvm-blake3-prefix-h/#a1fdc4924759d96608eed27da957714e7">blake3_hash_many_avx2</a>, <a href="/web-llvm/docs/api/files/lib/lib/support/lib/support/blake3/llvm-blake3-prefix-h/#a16f5ea82cd86b9294904063f0ccfcc49">blake3_hash_many_avx512</a>, <a href="/web-llvm/docs/api/files/lib/lib/support/lib/support/blake3/llvm-blake3-prefix-h/#a0eca43e40d730c5f98b68adfb530d8c7">blake3_hash_many_neon</a>, <a href="/web-llvm/docs/api/files/lib/lib/support/lib/support/blake3/llvm-blake3-prefix-h/#aa247d17d10d5ce32fdf0aeb1cb25a717">blake3_hash_many_portable</a>, <a href="/web-llvm/docs/api/files/lib/lib/support/lib/support/blake3/llvm-blake3-prefix-h/#ab4760fe488f905b24eb9529777a682a0">blake3_hash_many_sse2</a>, <a href="/web-llvm/docs/api/files/lib/lib/support/lib/support/blake3/llvm-blake3-prefix-h/#a37a92103b58f72a302f5fa64ebe6f30a">blake3_hash_many_sse41</a>, <a href="/web-llvm/docs/api/files/lib/lib/codegen/basicblocksections-cpp/#a6b480a971048f2d9cc342c18046d7774">blocks</a>, <a href="#a66b3e1af9044caa59fc75f60f72ee8e4">get_cpu_features</a>, <a href="#a3282fda96b0ba454bf4a8254c41e466a">MAYBE_UNUSED</a>, <a href="#a6efa629275df21393eef82e3bf972460a8d896e4fb625a47eaa49059a390971df">SSE2</a> and <a href="#a6efa629275df21393eef82e3bf972460a220a8c2c340905b520fa539836209d55">SSE41</a>.</p>

</div>
</div>

### blake3\_simd\_degree() {#a49b18dbf52f8c1a6ad492a2b1f3a0ca5}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">size_t blake3_simd_degree (void)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 248 of file <a href="/web-llvm/docs/api/files/lib/lib/support/lib/support/blake3/blake3-dispatch-c">blake3_dispatch.c</a>.</p>


<p>References <a href="#a6efa629275df21393eef82e3bf972460a7b9822126e7b712535af7b882409bf8b">AVX2</a>, <a href="#a6efa629275df21393eef82e3bf972460a698bc47a8c40306f69be562fbc5119fb">AVX512F</a>, <a href="#a6efa629275df21393eef82e3bf972460a265a413615d057502fd743b974730e0e">AVX512VL</a>, <a href="#a66b3e1af9044caa59fc75f60f72ee8e4">get_cpu_features</a>, <a href="#a3282fda96b0ba454bf4a8254c41e466a">MAYBE_UNUSED</a>, <a href="#a6efa629275df21393eef82e3bf972460a8d896e4fb625a47eaa49059a390971df">SSE2</a> and <a href="#a6efa629275df21393eef82e3bf972460a220a8c2c340905b520fa539836209d55">SSE41</a>.</p>

</div>
</div>

### get\_cpu\_features() {#a66b3e1af9044caa59fc75f60f72ee8e4}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">LLVM_ATTRIBUTE_USED enum cpu_feature get_cpu_features (void)</td>
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



<p>Definition at line 86 of file <a href="/web-llvm/docs/api/files/lib/lib/support/lib/support/blake3/blake3-dispatch-c">blake3_dispatch.c</a>.</p>


<p>References <a href="#a6efa629275df21393eef82e3bf972460a0f2500907bbad2fb795fba8fafd31b2a">AVX</a>, <a href="#a6efa629275df21393eef82e3bf972460a7b9822126e7b712535af7b882409bf8b">AVX2</a>, <a href="#a6efa629275df21393eef82e3bf972460a698bc47a8c40306f69be562fbc5119fb">AVX512F</a>, <a href="#a6efa629275df21393eef82e3bf972460a265a413615d057502fd743b974730e0e">AVX512VL</a>, <a href="#a5501a9f880066178c676be718e8a5d0a">g_cpu_features</a>, <a href="#a6efa629275df21393eef82e3bf972460a8d896e4fb625a47eaa49059a390971df">SSE2</a>, <a href="#a6efa629275df21393eef82e3bf972460a220a8c2c340905b520fa539836209d55">SSE41</a>, <a href="#a6efa629275df21393eef82e3bf972460a3bf865c30966497ad2f666485802e94b">SSSE3</a> and <a href="#a6efa629275df21393eef82e3bf972460a605159e8a4c32319fd69b5d151369d93">UNDEFINED</a>.</p>


<p>Referenced by <a href="#ae806b06af6fd96ce3036e82a66a972fc">blake3_compress_in_place</a>, <a href="#aa7ad14d63d0421eb5638eac60a4faff2">blake3_compress_xof</a>, <a href="#aa719af4ac5bfa12c07fce4e03d654400">blake3_hash_many</a> and <a href="#a49b18dbf52f8c1a6ad492a2b1f3a0ca5">blake3_simd_degree</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Variables

### g\_cpu\_features {#a5501a9f880066178c676be718e8a5d0a}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">enum cpu_feature g_cpu_features = <a href="#a6efa629275df21393eef82e3bf972460a605159e8a4c32319fd69b5d151369d93">UNDEFINED</a></td>
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



<p>Definition at line 79 of file <a href="/web-llvm/docs/api/files/lib/lib/support/lib/support/blake3/blake3-dispatch-c">blake3_dispatch.c</a>.</p>


<p>Referenced by <a href="#a66b3e1af9044caa59fc75f60f72ee8e4">get_cpu_features</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Macro Definitions

### MAYBE\_UNUSED {#a3282fda96b0ba454bf4a8254c41e466a}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">#define MAYBE_UNUSED(x)&nbsp;&nbsp;&nbsp;(void)((x))</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 17 of file <a href="/web-llvm/docs/api/files/lib/lib/support/lib/support/blake3/blake3-dispatch-c">blake3_dispatch.c</a>.</p>


<p>Referenced by <a href="#ae806b06af6fd96ce3036e82a66a972fc">blake3_compress_in_place</a>, <a href="#aa7ad14d63d0421eb5638eac60a4faff2">blake3_compress_xof</a>, <a href="#aa719af4ac5bfa12c07fce4e03d654400">blake3_hash_many</a> and <a href="#a49b18dbf52f8c1a6ad492a2b1f3a0ca5">blake3_simd_degree</a>.</p>

</div>
</div>

</div>

<hr/>

<p class="doxyGeneratedBy">Generated via <a href="https://xpack.github.io/doxygen2docusaurus">doxygen2docusaurus</a> 2.0.0 by <a href="https://www.doxygen.nl">Doxygen</a> 1.15.0.</p>

</div>
