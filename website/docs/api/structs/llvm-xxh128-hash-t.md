---

# DO NOT EDIT!
# Automatically generated via doxygen2docusaurus by Doxygen.

slug: /api/structs/llvm/xxh128-hash-t
custom_edit_url: null
toc_max_heading_level: 4
keywords:
  - doxygen
  - reference
  - struct

---

<div class="doxyPage">

# `XXH128_hash_t` Struct

<p>The return value from 128-bit hashes. <a href="#details">More...</a></p>

## Declaration

<div class="doxyDeclaration">
struct llvm::XXH128_hash_t { ... }
</div>

## Included Headers

<div class="doxyIncludesList">#include "<a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/support/xxhash-h">llvm/Support/xxhash.h</a>"
</div>

## Public Operators Index

<table class="doxyMembersIndex">

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">bool</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a44f807f4f91117f28d7150d724fb1015">operator==</a> (const XXH128_hash_t rhs) const</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Convenience equality check operator. <a href="#a44f807f4f91117f28d7150d724fb1015">More...</a></p>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a994e5b99d3dceafee44f8c983d75103b">low64</a></td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p><span class="doxyComputerOutput">value &amp; 0xFFFFFFFFFFFFFFFF</span> <a href="#a994e5b99d3dceafee44f8c983d75103b">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">uint64_t</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#af6ae9edb7b299ab65fcbc7eca03b381a">high64</a></td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p><span class="doxyComputerOutput">value &gt;&gt; 64</span> <a href="#af6ae9edb7b299ab65fcbc7eca03b381a">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

</table>

## Description {#details}

<p>The return value from 128-bit hashes.</p>


<p>Stored in little endian order, although the fields themselves are in native endianness.</p>


<p>Definition at line 64 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/support/xxhash-h">xxhash.h</a>.</p>


<div class="doxySectionDef">

## Public Operators

### operator==() {#a44f807f4f91117f28d7150d724fb1015}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool llvm::XXH128_hash_t::operator== (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/structs/llvm/xxh128-hash-t">XXH128_hash_t</a> rhs)</td>
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

<p>Convenience equality check operator.</p>

<p>Definition at line 69 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/support/xxhash-h">xxhash.h</a>.</p>


<p>References <a href="#af6ae9edb7b299ab65fcbc7eca03b381a">high64</a> and <a href="#a994e5b99d3dceafee44f8c983d75103b">low64</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Public Member Attributes

### high64 {#af6ae9edb7b299ab65fcbc7eca03b381a}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">uint64_t llvm::XXH128_hash_t::high64</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p><span class="doxyComputerOutput">value &gt;&gt; 64</span></p>

<p>Definition at line 66 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/support/xxhash-h">xxhash.h</a>.</p>


<p>Referenced by <a href="#a44f807f4f91117f28d7150d724fb1015">operator==</a>, <a href="/web-llvm/docs/api/files/lib/lib/support/xxhash-cpp/#abfad913bbf7470e15bdfa2349f67a258">XXH3_hashLong_128b</a>, <a href="/web-llvm/docs/api/files/lib/lib/support/xxhash-cpp/#a6f213bbbdebd84c8536a43217f014dbc">XXH3_len_0to16_128b</a>, <a href="/web-llvm/docs/api/files/lib/lib/support/xxhash-cpp/#a67de1b04da6de33341dc7ffc6854fa9f">XXH3_len_129to240_128b</a>, <a href="/web-llvm/docs/api/files/lib/lib/support/xxhash-cpp/#a43d708e6a6393ad5f59e3ade57f205d2">XXH3_len_17to128_128b</a>, <a href="/web-llvm/docs/api/files/lib/lib/support/xxhash-cpp/#a1f9fe4a69b646dae9518d991adc12a00">XXH3_len_1to3_128b</a>, <a href="/web-llvm/docs/api/files/lib/lib/support/xxhash-cpp/#a611ba08ac061c11dce0a30072099ba3c">XXH3_len_4to8_128b</a>, <a href="/web-llvm/docs/api/files/lib/lib/support/xxhash-cpp/#a68128490131d65e06f6066616f80ddf5">XXH3_len_9to16_128b</a> and <a href="/web-llvm/docs/api/files/lib/lib/support/xxhash-cpp/#a5a010401dcddb43e0a6fdcac9564d69b">XXH_mult64to128</a>.</p>

</div>
</div>

### low64 {#a994e5b99d3dceafee44f8c983d75103b}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">uint64_t llvm::XXH128_hash_t::low64</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p><span class="doxyComputerOutput">value &amp; 0xFFFFFFFFFFFFFFFF</span></p>

<p>Definition at line 65 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/support/xxhash-h">xxhash.h</a>.</p>


<p>Referenced by <a href="#a44f807f4f91117f28d7150d724fb1015">operator==</a>, <a href="/web-llvm/docs/api/files/lib/lib/support/xxhash-cpp/#a2fa22ae762463bb383e63bd381952344">XXH128_mix32B</a>, <a href="/web-llvm/docs/api/files/lib/lib/support/xxhash-cpp/#abfad913bbf7470e15bdfa2349f67a258">XXH3_hashLong_128b</a>, <a href="/web-llvm/docs/api/files/lib/lib/support/xxhash-cpp/#a6f213bbbdebd84c8536a43217f014dbc">XXH3_len_0to16_128b</a>, <a href="/web-llvm/docs/api/files/lib/lib/support/xxhash-cpp/#a67de1b04da6de33341dc7ffc6854fa9f">XXH3_len_129to240_128b</a>, <a href="/web-llvm/docs/api/files/lib/lib/support/xxhash-cpp/#a43d708e6a6393ad5f59e3ade57f205d2">XXH3_len_17to128_128b</a>, <a href="/web-llvm/docs/api/files/lib/lib/support/xxhash-cpp/#a1f9fe4a69b646dae9518d991adc12a00">XXH3_len_1to3_128b</a>, <a href="/web-llvm/docs/api/files/lib/lib/support/xxhash-cpp/#a611ba08ac061c11dce0a30072099ba3c">XXH3_len_4to8_128b</a>, <a href="/web-llvm/docs/api/files/lib/lib/support/xxhash-cpp/#a68128490131d65e06f6066616f80ddf5">XXH3_len_9to16_128b</a> and <a href="/web-llvm/docs/api/files/lib/lib/support/xxhash-cpp/#a5a010401dcddb43e0a6fdcac9564d69b">XXH_mult64to128</a>.</p>

</div>
</div>

</div>

<hr/>

The documentation for this struct was generated from the following file:

<ul>
<li><a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/support/xxhash-h">xxhash.h</a></li>
</ul>

<hr/>

<p class="doxyGeneratedBy">Generated via <a href="https://github.com/xpack/doxygen2docusaurus">doxygen2docusaurus</a> by <a href="https://www.doxygen.nl">Doxygen</a> 1.15.0.</p>

</div>
