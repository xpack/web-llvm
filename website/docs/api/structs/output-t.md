---

# DO NOT EDIT!
# Automatically generated via doxygen2docusaurus by Doxygen.

slug: /api/structs/output-t
custom_edit_url: null
toc_max_heading_level: 4
keywords:
  - doxygen
  - reference
  - struct

---

<div class="doxyPage">

# `output_t` Struct



## Declaration

<div class="doxyDeclaration">
struct output_t { ... }
</div>

## Public Member Attributes Index

<table class="doxyMembersIndex">

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">uint32_t</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ac4f9eca5e279f34c50f6e70ad449a897">input_cv</a>[8]</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ab9a8543fae164eece122f39bcdaa0bf7">counter</a></td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">uint8_t</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a67fd92399759962d96519544c737be99">block</a>[BLAKE3_BLOCK_LEN]</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">uint8_t</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a1e73cd9626b6c0a7960af035596dbf7c">block_len</a></td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">uint8_t</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#abab5d28213b91ed5b976aa4eef0f6384">flags</a></td>
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


<p>Definition at line 61 of file <a href="/web-llvm/docs/api/files/lib/lib/support/lib/support/blake3/blake3-c">blake3.c</a>.</p>


<div class="doxySectionDef">

## Public Member Attributes

### block {#a67fd92399759962d96519544c737be99}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">uint8_t output_t::block[BLAKE3_BLOCK_LEN]</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 64 of file <a href="/web-llvm/docs/api/files/lib/lib/support/lib/support/blake3/blake3-c">blake3.c</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/files/lib/lib/support/lib/support/blake3/blake3-c/#a0fb8691f907fe586830601d486049e6e">make_output</a>, <a href="/web-llvm/docs/api/files/lib/lib/support/lib/support/blake3/blake3-c/#a92376f69320e66a51477df2b47088249">output_chaining_value</a> and <a href="/web-llvm/docs/api/files/lib/lib/support/lib/support/blake3/blake3-c/#a0a194eae24fe95b572091dc7e992744f">output_root_bytes</a>.</p>

</div>
</div>

### block\_len {#a1e73cd9626b6c0a7960af035596dbf7c}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">uint8_t output_t::block_len</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 65 of file <a href="/web-llvm/docs/api/files/lib/lib/support/lib/support/blake3/blake3-c">blake3.c</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/files/lib/lib/support/lib/support/blake3/blake3-c/#a0fb8691f907fe586830601d486049e6e">make_output</a>, <a href="/web-llvm/docs/api/files/lib/lib/support/lib/support/blake3/blake3-c/#a92376f69320e66a51477df2b47088249">output_chaining_value</a> and <a href="/web-llvm/docs/api/files/lib/lib/support/lib/support/blake3/blake3-c/#a0a194eae24fe95b572091dc7e992744f">output_root_bytes</a>.</p>

</div>
</div>

### counter {#ab9a8543fae164eece122f39bcdaa0bf7}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">uint64_t output_t::counter</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 63 of file <a href="/web-llvm/docs/api/files/lib/lib/support/lib/support/blake3/blake3-c">blake3.c</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/files/lib/lib/support/lib/support/blake3/blake3-c/#a0fb8691f907fe586830601d486049e6e">make_output</a> and <a href="/web-llvm/docs/api/files/lib/lib/support/lib/support/blake3/blake3-c/#a92376f69320e66a51477df2b47088249">output_chaining_value</a>.</p>

</div>
</div>

### flags {#abab5d28213b91ed5b976aa4eef0f6384}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">uint8_t output_t::flags</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 66 of file <a href="/web-llvm/docs/api/files/lib/lib/support/lib/support/blake3/blake3-c">blake3.c</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/files/lib/lib/support/lib/support/blake3/blake3-c/#a0fb8691f907fe586830601d486049e6e">make_output</a>, <a href="/web-llvm/docs/api/files/lib/lib/support/lib/support/blake3/blake3-c/#a92376f69320e66a51477df2b47088249">output_chaining_value</a> and <a href="/web-llvm/docs/api/files/lib/lib/support/lib/support/blake3/blake3-c/#a0a194eae24fe95b572091dc7e992744f">output_root_bytes</a>.</p>

</div>
</div>

### input\_cv {#ac4f9eca5e279f34c50f6e70ad449a897}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">uint32_t output_t::input_cv[8]</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 62 of file <a href="/web-llvm/docs/api/files/lib/lib/support/lib/support/blake3/blake3-c">blake3.c</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/files/lib/lib/support/lib/support/blake3/blake3-c/#a0fb8691f907fe586830601d486049e6e">make_output</a>, <a href="/web-llvm/docs/api/files/lib/lib/support/lib/support/blake3/blake3-c/#a92376f69320e66a51477df2b47088249">output_chaining_value</a> and <a href="/web-llvm/docs/api/files/lib/lib/support/lib/support/blake3/blake3-c/#a0a194eae24fe95b572091dc7e992744f">output_root_bytes</a>.</p>

</div>
</div>

</div>

<hr/>

The documentation for this struct was generated from the following file:

<ul>
<li><a href="/web-llvm/docs/api/files/lib/lib/support/lib/support/blake3/blake3-c">blake3.c</a></li>
</ul>

<hr/>

<p class="doxyGeneratedBy">Generated via <a href="https://github.com/xpack/doxygen2docusaurus">doxygen2docusaurus</a> by <a href="https://www.doxygen.nl">Doxygen</a> 1.15.0.</p>

</div>
