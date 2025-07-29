---

# DO NOT EDIT!
# Automatically generated via doxygen2docusaurus by Doxygen.

slug: /api/files/lib/lib/support/lib/support/blake3/blake3-avx512-c
custom_edit_url: null
toc_max_heading_level: 4
keywords:
  - doxygen
  - reference
  - file

---

<div class="doxyPage">

# `blake3_avx512.c` File



## Included Headers

<div class="doxyIncludesList">#include "<a href="/web-llvm/docs/api/files/lib/lib/support/lib/support/blake3/blake3-impl-h">blake3_impl.h</a>"
#include &lt;immintrin.h&gt;
</div>

## Functions Index

<table class="doxyMembersIndex">

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/files/lib/lib/support/lib/support/blake3/blake3-impl-h/#a2eb6f9e0395b47b8d5e3eeae4fe0c116">INLINE</a> __m128i</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a5817fcd02d768ab2d50855656f67503d">loadu_128</a> (const uint8_t src[16])</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#aa362ae1523e4e2e15e22f2bb5e153992">loadu_256</a> (const uint8_t src[32])</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/files/lib/lib/support/lib/support/blake3/blake3-impl-h/#a2eb6f9e0395b47b8d5e3eeae4fe0c116">INLINE</a> __m512i</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a2c0350b1bf45107a56a8a86831d770f4">loadu_512</a> (const uint8_t src[64])</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a17b399be366d99ebf4d0d556eb049581">storeu_128</a> (__m128i src, uint8_t dest[16])</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a348f83b3a9f54be97640e8df8d1736cf">storeu_256</a> (__m256i src, uint8_t dest[16])</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a6dfb343c3ca4bccb7751311fe96692b8">add_128</a> (__m128i a, __m128i b)</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ad9ac052f4305c1e00f16feaf03b3f46f">add_256</a> (__m256i a, __m256i b)</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/files/lib/lib/support/lib/support/blake3/blake3-impl-h/#a2eb6f9e0395b47b8d5e3eeae4fe0c116">INLINE</a> __m512i</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a4e816e84375901a43dc887675dc862ff">add_512</a> (__m512i a, __m512i b)</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#af1565f865babf10788bb62b46715bb94">xor_128</a> (__m128i a, __m128i b)</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a4f79709f3456ef2295a5ae84225f87c8">xor_256</a> (__m256i a, __m256i b)</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/files/lib/lib/support/lib/support/blake3/blake3-impl-h/#a2eb6f9e0395b47b8d5e3eeae4fe0c116">INLINE</a> __m512i</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#af1db7ce0c9ee03ae8dde5b0ac6fae619">xor_512</a> (__m512i a, __m512i b)</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a2811db1c6207d1cc140a55f86fa748fe">set1_128</a> (uint32_t x)</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a11943b732bf85a25a1091f86d98ee0ad">set1_256</a> (uint32_t x)</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/files/lib/lib/support/lib/support/blake3/blake3-impl-h/#a2eb6f9e0395b47b8d5e3eeae4fe0c116">INLINE</a> __m512i</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a2b120901f9b4f6ae006342691df0b40a">set1_512</a> (uint32_t x)</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a07a790a133a5c7644000a49ff7eca92f">rot16_128</a> (__m128i x)</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a772249cf85a6ca655a7825bf7dca29c6">rot16_256</a> (__m256i x)</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/files/lib/lib/support/lib/support/blake3/blake3-impl-h/#a2eb6f9e0395b47b8d5e3eeae4fe0c116">INLINE</a> __m512i</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a35bfcbfee1b597542ff8b101a805da76">rot16_512</a> (__m512i x)</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a5ee3593d7f772b17beb17121f50ba01c">rot12_128</a> (__m128i x)</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a5fd287223129634151aec02113431363">rot12_256</a> (__m256i x)</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/files/lib/lib/support/lib/support/blake3/blake3-impl-h/#a2eb6f9e0395b47b8d5e3eeae4fe0c116">INLINE</a> __m512i</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#af8b34b45c8bea58bbde2d7142864e45a">rot12_512</a> (__m512i x)</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a3b682bf6df8cfc07532aa3d4c1ab35f7">rot8_128</a> (__m128i x)</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a2b2d390aeb1f1b025f7ba84fcef24a17">rot8_256</a> (__m256i x)</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/files/lib/lib/support/lib/support/blake3/blake3-impl-h/#a2eb6f9e0395b47b8d5e3eeae4fe0c116">INLINE</a> __m512i</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a0a8c91bcad2a7df64c309007884bae02">rot8_512</a> (__m512i x)</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#adb8eb425d8bc69044f3922b889d4c23d">rot7_128</a> (__m128i x)</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a308c32a5885fd1a660aa9f2ec4e2f8fe">rot7_256</a> (__m256i x)</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/files/lib/lib/support/lib/support/blake3/blake3-impl-h/#a2eb6f9e0395b47b8d5e3eeae4fe0c116">INLINE</a> __m512i</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#aa7a8127b0d42a25a8ed065062b3f3b0d">rot7_512</a> (__m512i x)</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a8c9bce27c4efaff2266c650c111ac5e5">blake3_compress_xof_avx512</a> (const uint32_t cv[8], const uint8_t block[BLAKE3_BLOCK_LEN], uint8_t block_len, uint64_t counter, uint8_t flags, uint8_t out[64])</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a3e2dd97881e59bb3ebf430b782fd03fb">blake3_compress_in_place_avx512</a> (uint32_t cv[8], const uint8_t block[BLAKE3_BLOCK_LEN], uint8_t block_len, uint64_t counter, uint8_t flags)</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#aa5f1285c7e774c601fa3e743e1526ecf">round_fn4</a> (__m128i v[16], __m128i m[16], size_t r)</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a389c01f091ae27628ac1343b55d8ffa9">transpose_vecs_128</a> (__m128i vecs[4])</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a821478286a39d4d2b7d3de1029671f6c">transpose_msg_vecs4</a> (const uint8_t *const *inputs, size_t block_offset, __m128i out[16])</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a97848bbb6c01d822fa40eaf17661d7da">load_counters4</a> (uint64_t counter, bool increment_counter, __m128i *out_lo, __m128i *out_hi)</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#afa6d10795b484494db61dafc00ef734b">blake3_hash4_avx512</a> (const uint8_t *const *inputs, size_t blocks, const uint32_t key[8], uint64_t counter, bool increment_counter, uint8_t flags, uint8_t flags_start, uint8_t flags_end, uint8_t *out)</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ac77dfe2fb0375dc564e5adbacbee80be">round_fn8</a> (__m256i v[16], __m256i m[16], size_t r)</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#aa9fcfa997be0e1657d08fb0fbd6402f0">transpose_vecs_256</a> (__m256i vecs[8])</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a86bb45f2c9dde435365cd29cc50f0e50">transpose_msg_vecs8</a> (const uint8_t *const *inputs, size_t block_offset, __m256i out[16])</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a6cea42dede3ee231c75a3fceb5c813b0">load_counters8</a> (uint64_t counter, bool increment_counter, __m256i *out_lo, __m256i *out_hi)</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a9fd5b5d20831064bbb6a1084a54a23aa">blake3_hash8_avx512</a> (const uint8_t *const *inputs, size_t blocks, const uint32_t key[8], uint64_t counter, bool increment_counter, uint8_t flags, uint8_t flags_start, uint8_t flags_end, uint8_t *out)</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a30739b84d2b0eae5880770d599d80a53">round_fn16</a> (__m512i v[16], __m512i m[16], size_t r)</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/files/lib/lib/support/lib/support/blake3/blake3-impl-h/#a2eb6f9e0395b47b8d5e3eeae4fe0c116">INLINE</a> __m512i</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a7f3c01c73dd0c4b6b5b543483a3fedee">unpack_lo_128</a> (__m512i a, __m512i b)</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/files/lib/lib/support/lib/support/blake3/blake3-impl-h/#a2eb6f9e0395b47b8d5e3eeae4fe0c116">INLINE</a> __m512i</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ad4321ef7336fc544d580142351381aef">unpack_hi_128</a> (__m512i a, __m512i b)</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a415cf10dd80134c63e8da7630f93b2c9">transpose_vecs_512</a> (__m512i vecs[16])</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#abc67f36249d94e163e17fb1ed5c47952">transpose_msg_vecs16</a> (const uint8_t *const *inputs, size_t block_offset, __m512i out[16])</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a75ae50cea7fd5dbedccc602f4a00b078">load_counters16</a> (uint64_t counter, bool increment_counter, __m512i *out_lo, __m512i *out_hi)</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a70bc2eed96d3dbb878f77cf42434871f">blake3_hash16_avx512</a> (const uint8_t *const *inputs, size_t blocks, const uint32_t key[8], uint64_t counter, bool increment_counter, uint8_t flags, uint8_t flags_start, uint8_t flags_end, uint8_t *out)</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a37c7357e371a02d89d2bc73d8749e6e4">hash_one_avx512</a> (const uint8_t *input, size_t blocks, const uint32_t key[8], uint64_t counter, uint8_t flags, uint8_t flags_start, uint8_t flags_end, uint8_t out[BLAKE3_OUT_LEN])</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#aa6adfc4c100ace1a487ade1cc7923fdb">blake3_hash_many_avx512</a> (const uint8_t *const *inputs, size_t num_inputs, size_t blocks, const uint32_t key[8], uint64_t counter, bool increment_counter, uint8_t flags, uint8_t flags_start, uint8_t flags_end, uint8_t *out)</td>
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

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">#define</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a9b99271af46084872ed880b1d85b4d4b">LO_IMM8</a>&nbsp;&nbsp;&nbsp;136</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a930a13dad6aaeb4be3c084c2cb31af6a">HI_IMM8</a>&nbsp;&nbsp;&nbsp;221</td>
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

### add\_128() {#a6dfb343c3ca4bccb7751311fe96692b8}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">INLINE __m128i add_128 (__m128i a, __m128i b)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 29 of file <a href="/web-llvm/docs/api/files/lib/lib/support/lib/support/blake3/blake3-avx512-c">blake3_avx512.c</a>.</p>


<p>Reference <a href="/web-llvm/docs/api/files/lib/lib/support/lib/support/blake3/blake3-impl-h/#a2eb6f9e0395b47b8d5e3eeae4fe0c116">INLINE</a>.</p>


<p>Referenced by <a href="#a227d420457072179f60b78aaa25c9d69">g1</a>, <a href="#a9a112855b64e521690699ce9d8cbabc6">g2</a> and <a href="#aa5f1285c7e774c601fa3e743e1526ecf">round_fn4</a>.</p>

</div>
</div>

### add\_256() {#ad9ac052f4305c1e00f16feaf03b3f46f}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">INLINE __m256i add_256 (__m256i a, __m256i b)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 31 of file <a href="/web-llvm/docs/api/files/lib/lib/support/lib/support/blake3/blake3-avx512-c">blake3_avx512.c</a>.</p>


<p>Reference <a href="/web-llvm/docs/api/files/lib/lib/support/lib/support/blake3/blake3-impl-h/#a2eb6f9e0395b47b8d5e3eeae4fe0c116">INLINE</a>.</p>


<p>Referenced by <a href="#ac77dfe2fb0375dc564e5adbacbee80be">round_fn8</a>.</p>

</div>
</div>

### add\_512() {#a4e816e84375901a43dc887675dc862ff}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">INLINE __m512i add_512 (__m512i a, __m512i b)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 33 of file <a href="/web-llvm/docs/api/files/lib/lib/support/lib/support/blake3/blake3-avx512-c">blake3_avx512.c</a>.</p>


<p>Reference <a href="/web-llvm/docs/api/files/lib/lib/support/lib/support/blake3/blake3-impl-h/#a2eb6f9e0395b47b8d5e3eeae4fe0c116">INLINE</a>.</p>


<p>Referenced by <a href="#a30739b84d2b0eae5880770d599d80a53">round_fn16</a>.</p>

</div>
</div>

### blake3\_compress\_in\_place\_avx512() {#a3e2dd97881e59bb3ebf430b782fd03fb}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void blake3_compress_in_place_avx512 (uint32_t cv=[8], <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> uint8_t block=[BLAKE3_BLOCK_LEN], uint8_t block_len, uint64_t counter, uint8_t flags)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 299 of file <a href="/web-llvm/docs/api/files/lib/lib/support/lib/support/blake3/blake3-avx512-c">blake3_avx512.c</a>.</p>


<p>References <a href="/web-llvm/docs/api/files/lib/lib/support/lib/support/blake3/llvm-blake3-prefix-h/#a304cb82e31ff3dc5a4b02f7fce75555e">BLAKE3_BLOCK_LEN</a>, <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/utils/unifyloopexits-cpp/#a4741a07a0e5675f89cfed122008e0a76">block</a>, <a href="#a963ad8f4da448c3d11d29a95d4881355">compress_pre</a>, <a href="#a17b399be366d99ebf4d0d556eb049581">storeu_128</a> and <a href="#af1565f865babf10788bb62b46715bb94">xor_128</a>.</p>

</div>
</div>

### blake3\_compress\_xof\_avx512() {#a8c9bce27c4efaff2266c650c111ac5e5}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void blake3_compress_xof_avx512 (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> uint32_t cv=[8], <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> uint8_t block=[BLAKE3_BLOCK_LEN], uint8_t block_len, uint64_t counter, uint8_t flags, uint8_t out=[64])</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 287 of file <a href="/web-llvm/docs/api/files/lib/lib/support/lib/support/blake3/blake3-avx512-c">blake3_avx512.c</a>.</p>


<p>References <a href="/web-llvm/docs/api/files/lib/lib/support/lib/support/blake3/llvm-blake3-prefix-h/#a304cb82e31ff3dc5a4b02f7fce75555e">BLAKE3_BLOCK_LEN</a>, <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/utils/unifyloopexits-cpp/#a4741a07a0e5675f89cfed122008e0a76">block</a>, <a href="#a963ad8f4da448c3d11d29a95d4881355">compress_pre</a>, <a href="#a5817fcd02d768ab2d50855656f67503d">loadu_128</a>, <a href="#a17b399be366d99ebf4d0d556eb049581">storeu_128</a> and <a href="#af1565f865babf10788bb62b46715bb94">xor_128</a>.</p>

</div>
</div>

### blake3\_hash\_many\_avx512() {#aa6adfc4c100ace1a487ade1cc7923fdb}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void blake3_hash_many_avx512 (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> uint8_t *<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> * inputs, size_t num_inputs, size_t blocks, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> uint32_t key=[8], uint64_t counter, bool increment_counter, uint8_t flags, uint8_t flags_start, uint8_t flags_end, uint8_t * out)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 1162 of file <a href="/web-llvm/docs/api/files/lib/lib/support/lib/support/blake3/blake3-avx512-c">blake3_avx512.c</a>.</p>


<p>References <a href="#a70bc2eed96d3dbb878f77cf42434871f">blake3_hash16_avx512</a>, <a href="#afa6d10795b484494db61dafc00ef734b">blake3_hash4_avx512</a>, <a href="#a9fd5b5d20831064bbb6a1084a54a23aa">blake3_hash8_avx512</a>, <a href="/web-llvm/docs/api/files/lib/lib/support/lib/support/blake3/llvm-blake3-prefix-h/#a54e230beb5e1d501702361fb91f399f0">BLAKE3_OUT_LEN</a>, <a href="/web-llvm/docs/api/files/lib/lib/codegen/basicblocksections-cpp/#a6b480a971048f2d9cc342c18046d7774">blocks</a> and <a href="#a37c7357e371a02d89d2bc73d8749e6e4">hash_one_avx512</a>.</p>

</div>
</div>

### blake3\_hash16\_avx512() {#a70bc2eed96d3dbb878f77cf42434871f}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void blake3_hash16_avx512 (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> uint8_t *<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> * inputs, size_t blocks, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> uint32_t key=[8], uint64_t counter, bool increment_counter, uint8_t flags, uint8_t flags_start, uint8_t flags_end, uint8_t * out)</td>
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



<p>Definition at line 1060 of file <a href="/web-llvm/docs/api/files/lib/lib/support/lib/support/blake3/blake3-avx512-c">blake3_avx512.c</a>.</p>


<p>References <a href="/web-llvm/docs/api/files/lib/lib/support/lib/support/blake3/llvm-blake3-prefix-h/#a304cb82e31ff3dc5a4b02f7fce75555e">BLAKE3_BLOCK_LEN</a>, <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/utils/unifyloopexits-cpp/#a4741a07a0e5675f89cfed122008e0a76">block</a>, <a href="/web-llvm/docs/api/files/lib/lib/codegen/basicblocksections-cpp/#a6b480a971048f2d9cc342c18046d7774">blocks</a>, <a href="/web-llvm/docs/api/files/lib/lib/support/lib/support/blake3/blake3-impl-h/#a78823051d1dad34b9b3d8120112e674d">IV</a>, <a href="#a75ae50cea7fd5dbedccc602f4a00b078">load_counters16</a>, <a href="#a30739b84d2b0eae5880770d599d80a53">round_fn16</a>, <a href="#a2b120901f9b4f6ae006342691df0b40a">set1_512</a>, <a href="#abc67f36249d94e163e17fb1ed5c47952">transpose_msg_vecs16</a>, <a href="#a415cf10dd80134c63e8da7630f93b2c9">transpose_vecs_512</a> and <a href="#af1db7ce0c9ee03ae8dde5b0ac6fae619">xor_512</a>.</p>


<p>Referenced by <a href="#aa6adfc4c100ace1a487ade1cc7923fdb">blake3_hash_many_avx512</a>.</p>

</div>
</div>

### blake3\_hash4\_avx512() {#afa6d10795b484494db61dafc00ef734b}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void blake3_hash4_avx512 (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> uint8_t *<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> * inputs, size_t blocks, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> uint32_t key=[8], uint64_t counter, bool increment_counter, uint8_t flags, uint8_t flags_start, uint8_t flags_end, uint8_t * out)</td>
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



<p>Definition at line 492 of file <a href="/web-llvm/docs/api/files/lib/lib/support/lib/support/blake3/blake3-avx512-c">blake3_avx512.c</a>.</p>


<p>References <a href="/web-llvm/docs/api/files/lib/lib/support/lib/support/blake3/llvm-blake3-prefix-h/#a304cb82e31ff3dc5a4b02f7fce75555e">BLAKE3_BLOCK_LEN</a>, <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/utils/unifyloopexits-cpp/#a4741a07a0e5675f89cfed122008e0a76">block</a>, <a href="/web-llvm/docs/api/files/lib/lib/codegen/basicblocksections-cpp/#a6b480a971048f2d9cc342c18046d7774">blocks</a>, <a href="/web-llvm/docs/api/files/lib/lib/support/lib/support/blake3/blake3-impl-h/#a78823051d1dad34b9b3d8120112e674d">IV</a>, <a href="#a97848bbb6c01d822fa40eaf17661d7da">load_counters4</a>, <a href="#aa5f1285c7e774c601fa3e743e1526ecf">round_fn4</a>, <a href="#a2811db1c6207d1cc140a55f86fa748fe">set1_128</a>, <a href="#a17b399be366d99ebf4d0d556eb049581">storeu_128</a>, <a href="#a821478286a39d4d2b7d3de1029671f6c">transpose_msg_vecs4</a>, <a href="#a389c01f091ae27628ac1343b55d8ffa9">transpose_vecs_128</a> and <a href="#af1565f865babf10788bb62b46715bb94">xor_128</a>.</p>


<p>Referenced by <a href="#aa6adfc4c100ace1a487ade1cc7923fdb">blake3_hash_many_avx512</a>.</p>

</div>
</div>

### blake3\_hash8\_avx512() {#a9fd5b5d20831064bbb6a1084a54a23aa}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void blake3_hash8_avx512 (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> uint8_t *<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> * inputs, size_t blocks, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> uint32_t key=[8], uint64_t counter, bool increment_counter, uint8_t flags, uint8_t flags_start, uint8_t flags_end, uint8_t * out)</td>
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



<p>Definition at line 747 of file <a href="/web-llvm/docs/api/files/lib/lib/support/lib/support/blake3/blake3-avx512-c">blake3_avx512.c</a>.</p>


<p>References <a href="/web-llvm/docs/api/files/lib/lib/support/lib/support/blake3/llvm-blake3-prefix-h/#a304cb82e31ff3dc5a4b02f7fce75555e">BLAKE3_BLOCK_LEN</a>, <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/utils/unifyloopexits-cpp/#a4741a07a0e5675f89cfed122008e0a76">block</a>, <a href="/web-llvm/docs/api/files/lib/lib/codegen/basicblocksections-cpp/#a6b480a971048f2d9cc342c18046d7774">blocks</a>, <a href="/web-llvm/docs/api/files/lib/lib/support/lib/support/blake3/blake3-impl-h/#a78823051d1dad34b9b3d8120112e674d">IV</a>, <a href="#a6cea42dede3ee231c75a3fceb5c813b0">load_counters8</a>, <a href="#ac77dfe2fb0375dc564e5adbacbee80be">round_fn8</a>, <a href="#a11943b732bf85a25a1091f86d98ee0ad">set1_256</a>, <a href="#a348f83b3a9f54be97640e8df8d1736cf">storeu_256</a>, <a href="#a86bb45f2c9dde435365cd29cc50f0e50">transpose_msg_vecs8</a>, <a href="#aa9fcfa997be0e1657d08fb0fbd6402f0">transpose_vecs_256</a> and <a href="#a4f79709f3456ef2295a5ae84225f87c8">xor_256</a>.</p>


<p>Referenced by <a href="#aa6adfc4c100ace1a487ade1cc7923fdb">blake3_hash_many_avx512</a>.</p>

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



<p>Definition at line 116 of file <a href="/web-llvm/docs/api/files/lib/lib/support/lib/support/blake3/blake3-avx512-c">blake3_avx512.c</a>.</p>


<p>References <a href="#a0f76993cc7906c818531cf239959c993">_mm_shuffle_ps2</a>, <a href="/web-llvm/docs/api/files/lib/lib/support/lib/support/blake3/llvm-blake3-prefix-h/#a304cb82e31ff3dc5a4b02f7fce75555e">BLAKE3_BLOCK_LEN</a>, <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/utils/unifyloopexits-cpp/#a4741a07a0e5675f89cfed122008e0a76">block</a>, <a href="/web-llvm/docs/api/files/lib/lib/support/lib/support/blake3/blake3-impl-h/#a7ec7b2f404362ce5bc1198981707bc7e">counter_high</a>, <a href="/web-llvm/docs/api/files/lib/lib/support/lib/support/blake3/blake3-impl-h/#afeab7ac9eaa036d9400491885ab6c6eb">counter_low</a>, <a href="#a70c979e8d315a9dbc9e7b19b15524c01">diagonalize</a>, <a href="#a227d420457072179f60b78aaa25c9d69">g1</a>, <a href="#a9a112855b64e521690699ce9d8cbabc6">g2</a>, <a href="/web-llvm/docs/api/files/lib/lib/support/lib/support/blake3/blake3-impl-h/#a2eb6f9e0395b47b8d5e3eeae4fe0c116">INLINE</a>, <a href="/web-llvm/docs/api/files/lib/lib/support/lib/support/blake3/blake3-impl-h/#a78823051d1dad34b9b3d8120112e674d">IV</a>, <a href="#a5817fcd02d768ab2d50855656f67503d">loadu_128</a>, <a href="#a0dca48047d04d92458c4517e41d8696e">set4</a> and <a href="#a922b09bcc81fca32a8ecbfe2d318d4b7">undiagonalize</a>.</p>


<p>Referenced by <a href="#a3e2dd97881e59bb3ebf430b782fd03fb">blake3_compress_in_place_avx512</a> and <a href="#a8c9bce27c4efaff2266c650c111ac5e5">blake3_compress_xof_avx512</a>.</p>

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



<p>Definition at line 104 of file <a href="/web-llvm/docs/api/files/lib/lib/support/lib/support/blake3/blake3-avx512-c">blake3_avx512.c</a>.</p>


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



<p>Definition at line 81 of file <a href="/web-llvm/docs/api/files/lib/lib/support/lib/support/blake3/blake3-avx512-c">blake3_avx512.c</a>.</p>


<p>References <a href="#a6dfb343c3ca4bccb7751311fe96692b8">add_128</a>, <a href="/web-llvm/docs/api/files/lib/lib/support/lib/support/blake3/blake3-impl-h/#a2eb6f9e0395b47b8d5e3eeae4fe0c116">INLINE</a>, <a href="#a5ee3593d7f772b17beb17121f50ba01c">rot12_128</a>, <a href="#a07a790a133a5c7644000a49ff7eca92f">rot16_128</a> and <a href="#af1565f865babf10788bb62b46715bb94">xor_128</a>.</p>


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



<p>Definition at line 91 of file <a href="/web-llvm/docs/api/files/lib/lib/support/lib/support/blake3/blake3-avx512-c">blake3_avx512.c</a>.</p>


<p>References <a href="#a6dfb343c3ca4bccb7751311fe96692b8">add_128</a>, <a href="/web-llvm/docs/api/files/lib/lib/support/lib/support/blake3/blake3-impl-h/#a2eb6f9e0395b47b8d5e3eeae4fe0c116">INLINE</a>, <a href="#adb8eb425d8bc69044f3922b889d4c23d">rot7_128</a>, <a href="#a3b682bf6df8cfc07532aa3d4c1ab35f7">rot8_128</a> and <a href="#af1565f865babf10788bb62b46715bb94">xor_128</a>.</p>


<p>Referenced by <a href="#a963ad8f4da448c3d11d29a95d4881355">compress_pre</a>.</p>

</div>
</div>

### hash\_one\_avx512() {#a37c7357e371a02d89d2bc73d8749e6e4}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">INLINE void hash_one_avx512 (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> uint8_t * input, size_t blocks, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> uint32_t key=[8], uint64_t counter, uint8_t flags, uint8_t flags_start, uint8_t flags_end, uint8_t out=[BLAKE3_OUT_LEN])</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 1142 of file <a href="/web-llvm/docs/api/files/lib/lib/support/lib/support/blake3/blake3-avx512-c">blake3_avx512.c</a>.</p>


<p>References <a href="/web-llvm/docs/api/files/lib/lib/support/lib/support/blake3/llvm-blake3-prefix-h/#a304cb82e31ff3dc5a4b02f7fce75555e">BLAKE3_BLOCK_LEN</a>, <a href="/web-llvm/docs/api/files/lib/lib/support/lib/support/blake3/llvm-blake3-prefix-h/#af94d87a1e3c7e9fa1f8a83b81893f322">blake3_compress_in_place_avx512</a>, <a href="/web-llvm/docs/api/files/lib/lib/support/lib/support/blake3/llvm-blake3-prefix-h/#a947bd80c6cdcbd362dd0760f3603abe6">BLAKE3_KEY_LEN</a>, <a href="/web-llvm/docs/api/files/lib/lib/support/lib/support/blake3/llvm-blake3-prefix-h/#a54e230beb5e1d501702361fb91f399f0">BLAKE3_OUT_LEN</a>, <a href="/web-llvm/docs/api/files/lib/lib/codegen/basicblocksections-cpp/#a6b480a971048f2d9cc342c18046d7774">blocks</a> and <a href="/web-llvm/docs/api/files/lib/lib/support/lib/support/blake3/blake3-impl-h/#a2eb6f9e0395b47b8d5e3eeae4fe0c116">INLINE</a>.</p>


<p>Referenced by <a href="#aa6adfc4c100ace1a487ade1cc7923fdb">blake3_hash_many_avx512</a>.</p>

</div>
</div>

### load\_counters16() {#a75ae50cea7fd5dbedccc602f4a00b078}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">INLINE void load_counters16 (uint64_t counter, bool increment_counter, __m512i * out_lo, __m512i * out_hi)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 1047 of file <a href="/web-llvm/docs/api/files/lib/lib/support/lib/support/blake3/blake3-avx512-c">blake3_avx512.c</a>.</p>


<p>Reference <a href="/web-llvm/docs/api/files/lib/lib/support/lib/support/blake3/blake3-impl-h/#a2eb6f9e0395b47b8d5e3eeae4fe0c116">INLINE</a>.</p>


<p>Referenced by <a href="#a70bc2eed96d3dbb878f77cf42434871f">blake3_hash16_avx512</a>.</p>

</div>
</div>

### load\_counters4() {#a97848bbb6c01d822fa40eaf17661d7da}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">INLINE void load_counters4 (uint64_t counter, bool increment_counter, __m128i * out_lo, __m128i * out_hi)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 479 of file <a href="/web-llvm/docs/api/files/lib/lib/support/lib/support/blake3/blake3-avx512-c">blake3_avx512.c</a>.</p>


<p>Reference <a href="/web-llvm/docs/api/files/lib/lib/support/lib/support/blake3/blake3-impl-h/#a2eb6f9e0395b47b8d5e3eeae4fe0c116">INLINE</a>.</p>


<p>Referenced by <a href="#afa6d10795b484494db61dafc00ef734b">blake3_hash4_avx512</a>.</p>

</div>
</div>

### load\_counters8() {#a6cea42dede3ee231c75a3fceb5c813b0}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">INLINE void load_counters8 (uint64_t counter, bool increment_counter, __m256i * out_lo, __m256i * out_hi)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 734 of file <a href="/web-llvm/docs/api/files/lib/lib/support/lib/support/blake3/blake3-avx512-c">blake3_avx512.c</a>.</p>


<p>Reference <a href="/web-llvm/docs/api/files/lib/lib/support/lib/support/blake3/blake3-impl-h/#a2eb6f9e0395b47b8d5e3eeae4fe0c116">INLINE</a>.</p>


<p>Referenced by <a href="#a9fd5b5d20831064bbb6a1084a54a23aa">blake3_hash8_avx512</a>.</p>

</div>
</div>

### loadu\_128() {#a5817fcd02d768ab2d50855656f67503d}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">INLINE __m128i loadu_128 (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> uint8_t src=[16])</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 9 of file <a href="/web-llvm/docs/api/files/lib/lib/support/lib/support/blake3/blake3-avx512-c">blake3_avx512.c</a>.</p>


<p>Reference <a href="/web-llvm/docs/api/files/lib/lib/support/lib/support/blake3/blake3-impl-h/#a2eb6f9e0395b47b8d5e3eeae4fe0c116">INLINE</a>.</p>


<p>Referenced by <a href="#a8c9bce27c4efaff2266c650c111ac5e5">blake3_compress_xof_avx512</a>, <a href="#a963ad8f4da448c3d11d29a95d4881355">compress_pre</a> and <a href="#a821478286a39d4d2b7d3de1029671f6c">transpose_msg_vecs4</a>.</p>

</div>
</div>

### loadu\_256() {#aa362ae1523e4e2e15e22f2bb5e153992}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">INLINE __m256i loadu_256 (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> uint8_t src=[32])</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 13 of file <a href="/web-llvm/docs/api/files/lib/lib/support/lib/support/blake3/blake3-avx512-c">blake3_avx512.c</a>.</p>


<p>Reference <a href="/web-llvm/docs/api/files/lib/lib/support/lib/support/blake3/blake3-impl-h/#a2eb6f9e0395b47b8d5e3eeae4fe0c116">INLINE</a>.</p>


<p>Referenced by <a href="#a86bb45f2c9dde435365cd29cc50f0e50">transpose_msg_vecs8</a>.</p>

</div>
</div>

### loadu\_512() {#a2c0350b1bf45107a56a8a86831d770f4}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">INLINE __m512i loadu_512 (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> uint8_t src=[64])</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 17 of file <a href="/web-llvm/docs/api/files/lib/lib/support/lib/support/blake3/blake3-avx512-c">blake3_avx512.c</a>.</p>


<p>Reference <a href="/web-llvm/docs/api/files/lib/lib/support/lib/support/blake3/blake3-impl-h/#a2eb6f9e0395b47b8d5e3eeae4fe0c116">INLINE</a>.</p>


<p>Referenced by <a href="#abc67f36249d94e163e17fb1ed5c47952">transpose_msg_vecs16</a>.</p>

</div>
</div>

### rot12\_128() {#a5ee3593d7f772b17beb17121f50ba01c}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">INLINE __m128i rot12_128 (__m128i x)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 57 of file <a href="/web-llvm/docs/api/files/lib/lib/support/lib/support/blake3/blake3-avx512-c">blake3_avx512.c</a>.</p>


<p>Reference <a href="/web-llvm/docs/api/files/lib/lib/support/lib/support/blake3/blake3-impl-h/#a2eb6f9e0395b47b8d5e3eeae4fe0c116">INLINE</a>.</p>


<p>Referenced by <a href="#a227d420457072179f60b78aaa25c9d69">g1</a> and <a href="#aa5f1285c7e774c601fa3e743e1526ecf">round_fn4</a>.</p>

</div>
</div>

### rot12\_256() {#a5fd287223129634151aec02113431363}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">INLINE __m256i rot12_256 (__m256i x)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 59 of file <a href="/web-llvm/docs/api/files/lib/lib/support/lib/support/blake3/blake3-avx512-c">blake3_avx512.c</a>.</p>


<p>Reference <a href="/web-llvm/docs/api/files/lib/lib/support/lib/support/blake3/blake3-impl-h/#a2eb6f9e0395b47b8d5e3eeae4fe0c116">INLINE</a>.</p>


<p>Referenced by <a href="#ac77dfe2fb0375dc564e5adbacbee80be">round_fn8</a>.</p>

</div>
</div>

### rot12\_512() {#af8b34b45c8bea58bbde2d7142864e45a}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">INLINE __m512i rot12_512 (__m512i x)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 61 of file <a href="/web-llvm/docs/api/files/lib/lib/support/lib/support/blake3/blake3-avx512-c">blake3_avx512.c</a>.</p>


<p>Reference <a href="/web-llvm/docs/api/files/lib/lib/support/lib/support/blake3/blake3-impl-h/#a2eb6f9e0395b47b8d5e3eeae4fe0c116">INLINE</a>.</p>


<p>Referenced by <a href="#a30739b84d2b0eae5880770d599d80a53">round_fn16</a>.</p>

</div>
</div>

### rot16\_128() {#a07a790a133a5c7644000a49ff7eca92f}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">INLINE __m128i rot16_128 (__m128i x)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 51 of file <a href="/web-llvm/docs/api/files/lib/lib/support/lib/support/blake3/blake3-avx512-c">blake3_avx512.c</a>.</p>


<p>Reference <a href="/web-llvm/docs/api/files/lib/lib/support/lib/support/blake3/blake3-impl-h/#a2eb6f9e0395b47b8d5e3eeae4fe0c116">INLINE</a>.</p>


<p>Referenced by <a href="#a227d420457072179f60b78aaa25c9d69">g1</a> and <a href="#aa5f1285c7e774c601fa3e743e1526ecf">round_fn4</a>.</p>

</div>
</div>

### rot16\_256() {#a772249cf85a6ca655a7825bf7dca29c6}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">INLINE __m256i rot16_256 (__m256i x)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 53 of file <a href="/web-llvm/docs/api/files/lib/lib/support/lib/support/blake3/blake3-avx512-c">blake3_avx512.c</a>.</p>


<p>Reference <a href="/web-llvm/docs/api/files/lib/lib/support/lib/support/blake3/blake3-impl-h/#a2eb6f9e0395b47b8d5e3eeae4fe0c116">INLINE</a>.</p>


<p>Referenced by <a href="#ac77dfe2fb0375dc564e5adbacbee80be">round_fn8</a>.</p>

</div>
</div>

### rot16\_512() {#a35bfcbfee1b597542ff8b101a805da76}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">INLINE __m512i rot16_512 (__m512i x)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 55 of file <a href="/web-llvm/docs/api/files/lib/lib/support/lib/support/blake3/blake3-avx512-c">blake3_avx512.c</a>.</p>


<p>Reference <a href="/web-llvm/docs/api/files/lib/lib/support/lib/support/blake3/blake3-impl-h/#a2eb6f9e0395b47b8d5e3eeae4fe0c116">INLINE</a>.</p>


<p>Referenced by <a href="#a30739b84d2b0eae5880770d599d80a53">round_fn16</a>.</p>

</div>
</div>

### rot7\_128() {#adb8eb425d8bc69044f3922b889d4c23d}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">INLINE __m128i rot7_128 (__m128i x)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 69 of file <a href="/web-llvm/docs/api/files/lib/lib/support/lib/support/blake3/blake3-avx512-c">blake3_avx512.c</a>.</p>


<p>Reference <a href="/web-llvm/docs/api/files/lib/lib/support/lib/support/blake3/blake3-impl-h/#a2eb6f9e0395b47b8d5e3eeae4fe0c116">INLINE</a>.</p>


<p>Referenced by <a href="#a9a112855b64e521690699ce9d8cbabc6">g2</a> and <a href="#aa5f1285c7e774c601fa3e743e1526ecf">round_fn4</a>.</p>

</div>
</div>

### rot7\_256() {#a308c32a5885fd1a660aa9f2ec4e2f8fe}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">INLINE __m256i rot7_256 (__m256i x)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 71 of file <a href="/web-llvm/docs/api/files/lib/lib/support/lib/support/blake3/blake3-avx512-c">blake3_avx512.c</a>.</p>


<p>Reference <a href="/web-llvm/docs/api/files/lib/lib/support/lib/support/blake3/blake3-impl-h/#a2eb6f9e0395b47b8d5e3eeae4fe0c116">INLINE</a>.</p>


<p>Referenced by <a href="#ac77dfe2fb0375dc564e5adbacbee80be">round_fn8</a>.</p>

</div>
</div>

### rot7\_512() {#aa7a8127b0d42a25a8ed065062b3f3b0d}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">INLINE __m512i rot7_512 (__m512i x)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 73 of file <a href="/web-llvm/docs/api/files/lib/lib/support/lib/support/blake3/blake3-avx512-c">blake3_avx512.c</a>.</p>


<p>Reference <a href="/web-llvm/docs/api/files/lib/lib/support/lib/support/blake3/blake3-impl-h/#a2eb6f9e0395b47b8d5e3eeae4fe0c116">INLINE</a>.</p>


<p>Referenced by <a href="#a30739b84d2b0eae5880770d599d80a53">round_fn16</a>.</p>

</div>
</div>

### rot8\_128() {#a3b682bf6df8cfc07532aa3d4c1ab35f7}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">INLINE __m128i rot8_128 (__m128i x)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 63 of file <a href="/web-llvm/docs/api/files/lib/lib/support/lib/support/blake3/blake3-avx512-c">blake3_avx512.c</a>.</p>


<p>Reference <a href="/web-llvm/docs/api/files/lib/lib/support/lib/support/blake3/blake3-impl-h/#a2eb6f9e0395b47b8d5e3eeae4fe0c116">INLINE</a>.</p>


<p>Referenced by <a href="#a9a112855b64e521690699ce9d8cbabc6">g2</a> and <a href="#aa5f1285c7e774c601fa3e743e1526ecf">round_fn4</a>.</p>

</div>
</div>

### rot8\_256() {#a2b2d390aeb1f1b025f7ba84fcef24a17}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">INLINE __m256i rot8_256 (__m256i x)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 65 of file <a href="/web-llvm/docs/api/files/lib/lib/support/lib/support/blake3/blake3-avx512-c">blake3_avx512.c</a>.</p>


<p>Reference <a href="/web-llvm/docs/api/files/lib/lib/support/lib/support/blake3/blake3-impl-h/#a2eb6f9e0395b47b8d5e3eeae4fe0c116">INLINE</a>.</p>


<p>Referenced by <a href="#ac77dfe2fb0375dc564e5adbacbee80be">round_fn8</a>.</p>

</div>
</div>

### rot8\_512() {#a0a8c91bcad2a7df64c309007884bae02}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">INLINE __m512i rot8_512 (__m512i x)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 67 of file <a href="/web-llvm/docs/api/files/lib/lib/support/lib/support/blake3/blake3-avx512-c">blake3_avx512.c</a>.</p>


<p>Reference <a href="/web-llvm/docs/api/files/lib/lib/support/lib/support/blake3/blake3-impl-h/#a2eb6f9e0395b47b8d5e3eeae4fe0c116">INLINE</a>.</p>


<p>Referenced by <a href="#a30739b84d2b0eae5880770d599d80a53">round_fn16</a>.</p>

</div>
</div>

### round\_fn16() {#a30739b84d2b0eae5880770d599d80a53}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">INLINE void round_fn16 (__m512i v=[16], __m512i m=[16], size_t r)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 811 of file <a href="/web-llvm/docs/api/files/lib/lib/support/lib/support/blake3/blake3-avx512-c">blake3_avx512.c</a>.</p>


<p>References <a href="#a4e816e84375901a43dc887675dc862ff">add_512</a>, <a href="/web-llvm/docs/api/files/lib/lib/support/lib/support/blake3/blake3-impl-h/#a2eb6f9e0395b47b8d5e3eeae4fe0c116">INLINE</a>, <a href="/web-llvm/docs/api/files/lib/lib/support/lib/support/blake3/blake3-impl-h/#a0683f2191826e5431f112c71a12b7908">MSG_SCHEDULE</a>, <a href="#af8b34b45c8bea58bbde2d7142864e45a">rot12_512</a>, <a href="#a35bfcbfee1b597542ff8b101a805da76">rot16_512</a>, <a href="#aa7a8127b0d42a25a8ed065062b3f3b0d">rot7_512</a>, <a href="#a0a8c91bcad2a7df64c309007884bae02">rot8_512</a> and <a href="#af1db7ce0c9ee03ae8dde5b0ac6fae619">xor_512</a>.</p>


<p>Referenced by <a href="#a70bc2eed96d3dbb878f77cf42434871f">blake3_hash16_avx512</a>.</p>

</div>
</div>

### round\_fn4() {#aa5f1285c7e774c601fa3e743e1526ecf}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">INLINE void round_fn4 (__m128i v=[16], __m128i m=[16], size_t r)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 315 of file <a href="/web-llvm/docs/api/files/lib/lib/support/lib/support/blake3/blake3-avx512-c">blake3_avx512.c</a>.</p>


<p>References <a href="#a6dfb343c3ca4bccb7751311fe96692b8">add_128</a>, <a href="/web-llvm/docs/api/files/lib/lib/support/lib/support/blake3/blake3-impl-h/#a2eb6f9e0395b47b8d5e3eeae4fe0c116">INLINE</a>, <a href="/web-llvm/docs/api/files/lib/lib/support/lib/support/blake3/blake3-impl-h/#a0683f2191826e5431f112c71a12b7908">MSG_SCHEDULE</a>, <a href="#a5ee3593d7f772b17beb17121f50ba01c">rot12_128</a>, <a href="#a07a790a133a5c7644000a49ff7eca92f">rot16_128</a>, <a href="#adb8eb425d8bc69044f3922b889d4c23d">rot7_128</a>, <a href="#a3b682bf6df8cfc07532aa3d4c1ab35f7">rot8_128</a> and <a href="#af1565f865babf10788bb62b46715bb94">xor_128</a>.</p>


<p>Referenced by <a href="#afa6d10795b484494db61dafc00ef734b">blake3_hash4_avx512</a>.</p>

</div>
</div>

### round\_fn8() {#ac77dfe2fb0375dc564e5adbacbee80be}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">INLINE void round_fn8 (__m256i v=[16], __m256i m=[16], size_t r)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 559 of file <a href="/web-llvm/docs/api/files/lib/lib/support/lib/support/blake3/blake3-avx512-c">blake3_avx512.c</a>.</p>


<p>References <a href="#ad9ac052f4305c1e00f16feaf03b3f46f">add_256</a>, <a href="/web-llvm/docs/api/files/lib/lib/support/lib/support/blake3/blake3-impl-h/#a2eb6f9e0395b47b8d5e3eeae4fe0c116">INLINE</a>, <a href="/web-llvm/docs/api/files/lib/lib/support/lib/support/blake3/blake3-impl-h/#a0683f2191826e5431f112c71a12b7908">MSG_SCHEDULE</a>, <a href="#a5fd287223129634151aec02113431363">rot12_256</a>, <a href="#a772249cf85a6ca655a7825bf7dca29c6">rot16_256</a>, <a href="#a308c32a5885fd1a660aa9f2ec4e2f8fe">rot7_256</a>, <a href="#a2b2d390aeb1f1b025f7ba84fcef24a17">rot8_256</a> and <a href="#a4f79709f3456ef2295a5ae84225f87c8">xor_256</a>.</p>


<p>Referenced by <a href="#a9fd5b5d20831064bbb6a1084a54a23aa">blake3_hash8_avx512</a>.</p>

</div>
</div>

### set1\_128() {#a2811db1c6207d1cc140a55f86fa748fe}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">INLINE __m128i set1_128 (uint32_t x)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 41 of file <a href="/web-llvm/docs/api/files/lib/lib/support/lib/support/blake3/blake3-avx512-c">blake3_avx512.c</a>.</p>


<p>Reference <a href="/web-llvm/docs/api/files/lib/lib/support/lib/support/blake3/blake3-impl-h/#a2eb6f9e0395b47b8d5e3eeae4fe0c116">INLINE</a>.</p>


<p>Referenced by <a href="#afa6d10795b484494db61dafc00ef734b">blake3_hash4_avx512</a>.</p>

</div>
</div>

### set1\_256() {#a11943b732bf85a25a1091f86d98ee0ad}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">INLINE __m256i set1_256 (uint32_t x)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 43 of file <a href="/web-llvm/docs/api/files/lib/lib/support/lib/support/blake3/blake3-avx512-c">blake3_avx512.c</a>.</p>


<p>Reference <a href="/web-llvm/docs/api/files/lib/lib/support/lib/support/blake3/blake3-impl-h/#a2eb6f9e0395b47b8d5e3eeae4fe0c116">INLINE</a>.</p>


<p>Referenced by <a href="#a9fd5b5d20831064bbb6a1084a54a23aa">blake3_hash8_avx512</a>.</p>

</div>
</div>

### set1\_512() {#a2b120901f9b4f6ae006342691df0b40a}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">INLINE __m512i set1_512 (uint32_t x)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 45 of file <a href="/web-llvm/docs/api/files/lib/lib/support/lib/support/blake3/blake3-avx512-c">blake3_avx512.c</a>.</p>


<p>Reference <a href="/web-llvm/docs/api/files/lib/lib/support/lib/support/blake3/blake3-impl-h/#a2eb6f9e0395b47b8d5e3eeae4fe0c116">INLINE</a>.</p>


<p>Referenced by <a href="#a70bc2eed96d3dbb878f77cf42434871f">blake3_hash16_avx512</a>.</p>

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



<p>Definition at line 47 of file <a href="/web-llvm/docs/api/files/lib/lib/support/lib/support/blake3/blake3-avx512-c">blake3_avx512.c</a>.</p>


<p>Reference <a href="/web-llvm/docs/api/files/lib/lib/support/lib/support/blake3/blake3-impl-h/#a2eb6f9e0395b47b8d5e3eeae4fe0c116">INLINE</a>.</p>


<p>Referenced by <a href="#a963ad8f4da448c3d11d29a95d4881355">compress_pre</a>.</p>

</div>
</div>

### storeu\_128() {#a17b399be366d99ebf4d0d556eb049581}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">INLINE void storeu_128 (__m128i src, uint8_t dest=[16])</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 21 of file <a href="/web-llvm/docs/api/files/lib/lib/support/lib/support/blake3/blake3-avx512-c">blake3_avx512.c</a>.</p>


<p>Reference <a href="/web-llvm/docs/api/files/lib/lib/support/lib/support/blake3/blake3-impl-h/#a2eb6f9e0395b47b8d5e3eeae4fe0c116">INLINE</a>.</p>


<p>Referenced by <a href="#a3e2dd97881e59bb3ebf430b782fd03fb">blake3_compress_in_place_avx512</a>, <a href="#a8c9bce27c4efaff2266c650c111ac5e5">blake3_compress_xof_avx512</a> and <a href="#afa6d10795b484494db61dafc00ef734b">blake3_hash4_avx512</a>.</p>

</div>
</div>

### storeu\_256() {#a348f83b3a9f54be97640e8df8d1736cf}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">INLINE void storeu_256 (__m256i src, uint8_t dest=[16])</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 25 of file <a href="/web-llvm/docs/api/files/lib/lib/support/lib/support/blake3/blake3-avx512-c">blake3_avx512.c</a>.</p>


<p>Reference <a href="/web-llvm/docs/api/files/lib/lib/support/lib/support/blake3/blake3-impl-h/#a2eb6f9e0395b47b8d5e3eeae4fe0c116">INLINE</a>.</p>


<p>Referenced by <a href="#a9fd5b5d20831064bbb6a1084a54a23aa">blake3_hash8_avx512</a>.</p>

</div>
</div>

### transpose\_msg\_vecs16() {#abc67f36249d94e163e17fb1ed5c47952}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">INLINE void transpose_msg_vecs16 (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> uint8_t *<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> * inputs, size_t block_offset, __m512i out=[16])</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 1023 of file <a href="/web-llvm/docs/api/files/lib/lib/support/lib/support/blake3/blake3-avx512-c">blake3_avx512.c</a>.</p>


<p>References <a href="/web-llvm/docs/api/files/lib/lib/support/lib/support/blake3/blake3-impl-h/#a2eb6f9e0395b47b8d5e3eeae4fe0c116">INLINE</a>, <a href="#a2c0350b1bf45107a56a8a86831d770f4">loadu_512</a> and <a href="#a415cf10dd80134c63e8da7630f93b2c9">transpose_vecs_512</a>.</p>


<p>Referenced by <a href="#a70bc2eed96d3dbb878f77cf42434871f">blake3_hash16_avx512</a>.</p>

</div>
</div>

### transpose\_msg\_vecs4() {#a821478286a39d4d2b7d3de1029671f6c}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">INLINE void transpose_msg_vecs4 (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> uint8_t *<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> * inputs, size_t block_offset, __m128i out=[16])</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 452 of file <a href="/web-llvm/docs/api/files/lib/lib/support/lib/support/blake3/blake3-avx512-c">blake3_avx512.c</a>.</p>


<p>References <a href="/web-llvm/docs/api/files/lib/lib/support/lib/support/blake3/blake3-impl-h/#a2eb6f9e0395b47b8d5e3eeae4fe0c116">INLINE</a>, <a href="#a5817fcd02d768ab2d50855656f67503d">loadu_128</a> and <a href="#a389c01f091ae27628ac1343b55d8ffa9">transpose_vecs_128</a>.</p>


<p>Referenced by <a href="#afa6d10795b484494db61dafc00ef734b">blake3_hash4_avx512</a>.</p>

</div>
</div>

### transpose\_msg\_vecs8() {#a86bb45f2c9dde435365cd29cc50f0e50}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">INLINE void transpose_msg_vecs8 (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> uint8_t *<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> * inputs, size_t block_offset, __m256i out=[16])</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 709 of file <a href="/web-llvm/docs/api/files/lib/lib/support/lib/support/blake3/blake3-avx512-c">blake3_avx512.c</a>.</p>


<p>References <a href="/web-llvm/docs/api/files/lib/lib/support/lib/support/blake3/blake3-impl-h/#a2eb6f9e0395b47b8d5e3eeae4fe0c116">INLINE</a>, <a href="#aa362ae1523e4e2e15e22f2bb5e153992">loadu_256</a> and <a href="#aa9fcfa997be0e1657d08fb0fbd6402f0">transpose_vecs_256</a>.</p>


<p>Referenced by <a href="#a9fd5b5d20831064bbb6a1084a54a23aa">blake3_hash8_avx512</a>.</p>

</div>
</div>

### transpose\_vecs\_128() {#a389c01f091ae27628ac1343b55d8ffa9}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">INLINE void transpose_vecs_128 (__m128i vecs=[4])</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 431 of file <a href="/web-llvm/docs/api/files/lib/lib/support/lib/support/blake3/blake3-avx512-c">blake3_avx512.c</a>.</p>


<p>Reference <a href="/web-llvm/docs/api/files/lib/lib/support/lib/support/blake3/blake3-impl-h/#a2eb6f9e0395b47b8d5e3eeae4fe0c116">INLINE</a>.</p>


<p>Referenced by <a href="#afa6d10795b484494db61dafc00ef734b">blake3_hash4_avx512</a> and <a href="#a821478286a39d4d2b7d3de1029671f6c">transpose_msg_vecs4</a>.</p>

</div>
</div>

### transpose\_vecs\_256() {#aa9fcfa997be0e1657d08fb0fbd6402f0}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">INLINE void transpose_vecs_256 (__m256i vecs=[8])</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 675 of file <a href="/web-llvm/docs/api/files/lib/lib/support/lib/support/blake3/blake3-avx512-c">blake3_avx512.c</a>.</p>


<p>Reference <a href="/web-llvm/docs/api/files/lib/lib/support/lib/support/blake3/blake3-impl-h/#a2eb6f9e0395b47b8d5e3eeae4fe0c116">INLINE</a>.</p>


<p>Referenced by <a href="#a9fd5b5d20831064bbb6a1084a54a23aa">blake3_hash8_avx512</a> and <a href="#a86bb45f2c9dde435365cd29cc50f0e50">transpose_msg_vecs8</a>.</p>

</div>
</div>

### transpose\_vecs\_512() {#a415cf10dd80134c63e8da7630f93b2c9}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">INLINE void transpose_vecs_512 (__m512i vecs=[16])</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 941 of file <a href="/web-llvm/docs/api/files/lib/lib/support/lib/support/blake3/blake3-avx512-c">blake3_avx512.c</a>.</p>


<p>References <a href="/web-llvm/docs/api/files/lib/lib/support/lib/support/blake3/blake3-impl-h/#a2eb6f9e0395b47b8d5e3eeae4fe0c116">INLINE</a>, <a href="#ad4321ef7336fc544d580142351381aef">unpack_hi_128</a> and <a href="#a7f3c01c73dd0c4b6b5b543483a3fedee">unpack_lo_128</a>.</p>


<p>Referenced by <a href="#a70bc2eed96d3dbb878f77cf42434871f">blake3_hash16_avx512</a> and <a href="#abc67f36249d94e163e17fb1ed5c47952">transpose_msg_vecs16</a>.</p>

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



<p>Definition at line 110 of file <a href="/web-llvm/docs/api/files/lib/lib/support/lib/support/blake3/blake3-avx512-c">blake3_avx512.c</a>.</p>


<p>Reference <a href="/web-llvm/docs/api/files/lib/lib/support/lib/support/blake3/blake3-impl-h/#a2eb6f9e0395b47b8d5e3eeae4fe0c116">INLINE</a>.</p>


<p>Referenced by <a href="#a963ad8f4da448c3d11d29a95d4881355">compress_pre</a>.</p>

</div>
</div>

### unpack\_hi\_128() {#ad4321ef7336fc544d580142351381aef}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">INLINE __m512i unpack_hi_128 (__m512i a, __m512i b)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 937 of file <a href="/web-llvm/docs/api/files/lib/lib/support/lib/support/blake3/blake3-avx512-c">blake3_avx512.c</a>.</p>


<p>References <a href="#a930a13dad6aaeb4be3c084c2cb31af6a">HI_IMM8</a> and <a href="/web-llvm/docs/api/files/lib/lib/support/lib/support/blake3/blake3-impl-h/#a2eb6f9e0395b47b8d5e3eeae4fe0c116">INLINE</a>.</p>


<p>Referenced by <a href="#a415cf10dd80134c63e8da7630f93b2c9">transpose_vecs_512</a>.</p>

</div>
</div>

### unpack\_lo\_128() {#a7f3c01c73dd0c4b6b5b543483a3fedee}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">INLINE __m512i unpack_lo_128 (__m512i a, __m512i b)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 930 of file <a href="/web-llvm/docs/api/files/lib/lib/support/lib/support/blake3/blake3-avx512-c">blake3_avx512.c</a>.</p>


<p>References <a href="/web-llvm/docs/api/files/lib/lib/support/lib/support/blake3/blake3-impl-h/#a2eb6f9e0395b47b8d5e3eeae4fe0c116">INLINE</a> and <a href="#a9b99271af46084872ed880b1d85b4d4b">LO_IMM8</a>.</p>


<p>Referenced by <a href="#a415cf10dd80134c63e8da7630f93b2c9">transpose_vecs_512</a>.</p>

</div>
</div>

### xor\_128() {#af1565f865babf10788bb62b46715bb94}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">INLINE __m128i xor_128 (__m128i a, __m128i b)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 35 of file <a href="/web-llvm/docs/api/files/lib/lib/support/lib/support/blake3/blake3-avx512-c">blake3_avx512.c</a>.</p>


<p>Reference <a href="/web-llvm/docs/api/files/lib/lib/support/lib/support/blake3/blake3-impl-h/#a2eb6f9e0395b47b8d5e3eeae4fe0c116">INLINE</a>.</p>


<p>Referenced by <a href="#a3e2dd97881e59bb3ebf430b782fd03fb">blake3_compress_in_place_avx512</a>, <a href="#a8c9bce27c4efaff2266c650c111ac5e5">blake3_compress_xof_avx512</a>, <a href="#afa6d10795b484494db61dafc00ef734b">blake3_hash4_avx512</a>, <a href="#a227d420457072179f60b78aaa25c9d69">g1</a>, <a href="#a9a112855b64e521690699ce9d8cbabc6">g2</a> and <a href="#aa5f1285c7e774c601fa3e743e1526ecf">round_fn4</a>.</p>

</div>
</div>

### xor\_256() {#a4f79709f3456ef2295a5ae84225f87c8}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">INLINE __m256i xor_256 (__m256i a, __m256i b)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 37 of file <a href="/web-llvm/docs/api/files/lib/lib/support/lib/support/blake3/blake3-avx512-c">blake3_avx512.c</a>.</p>


<p>Reference <a href="/web-llvm/docs/api/files/lib/lib/support/lib/support/blake3/blake3-impl-h/#a2eb6f9e0395b47b8d5e3eeae4fe0c116">INLINE</a>.</p>


<p>Referenced by <a href="#a9fd5b5d20831064bbb6a1084a54a23aa">blake3_hash8_avx512</a> and <a href="#ac77dfe2fb0375dc564e5adbacbee80be">round_fn8</a>.</p>

</div>
</div>

### xor\_512() {#af1db7ce0c9ee03ae8dde5b0ac6fae619}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">INLINE __m512i xor_512 (__m512i a, __m512i b)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 39 of file <a href="/web-llvm/docs/api/files/lib/lib/support/lib/support/blake3/blake3-avx512-c">blake3_avx512.c</a>.</p>


<p>Reference <a href="/web-llvm/docs/api/files/lib/lib/support/lib/support/blake3/blake3-impl-h/#a2eb6f9e0395b47b8d5e3eeae4fe0c116">INLINE</a>.</p>


<p>Referenced by <a href="#a70bc2eed96d3dbb878f77cf42434871f">blake3_hash16_avx512</a> and <a href="#a30739b84d2b0eae5880770d599d80a53">round_fn16</a>.</p>

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

<p>Definition at line 5 of file <a href="/web-llvm/docs/api/files/lib/lib/support/lib/support/blake3/blake3-avx512-c">blake3_avx512.c</a>.</p>


<p>Referenced by <a href="#a963ad8f4da448c3d11d29a95d4881355">compress_pre</a>.</p>

</div>
</div>

### HI\_IMM8 {#a930a13dad6aaeb4be3c084c2cb31af6a}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">#define HI_IMM8&nbsp;&nbsp;&nbsp;221</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 935 of file <a href="/web-llvm/docs/api/files/lib/lib/support/lib/support/blake3/blake3-avx512-c">blake3_avx512.c</a>.</p>


<p>Referenced by <a href="#ad4321ef7336fc544d580142351381aef">unpack_hi_128</a>.</p>

</div>
</div>

### LO\_IMM8 {#a9b99271af46084872ed880b1d85b4d4b}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">#define LO_IMM8&nbsp;&nbsp;&nbsp;136</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 928 of file <a href="/web-llvm/docs/api/files/lib/lib/support/lib/support/blake3/blake3-avx512-c">blake3_avx512.c</a>.</p>


<p>Referenced by <a href="#a7f3c01c73dd0c4b6b5b543483a3fedee">unpack_lo_128</a>.</p>

</div>
</div>

</div>

<hr/>

<p class="doxyGeneratedBy">Generated via <a href="https://github.com/xpack/doxygen2docusaurus">doxygen2docusaurus</a> by <a href="https://www.doxygen.nl">Doxygen</a> 1.15.0.</p>

</div>
