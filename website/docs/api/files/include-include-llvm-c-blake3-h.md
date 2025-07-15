---

# DO NOT EDIT!
# Automatically generated via doxygen2docusaurus by Doxygen.

slug: /api/files/include/include/llvm-c/blake3-h
custom_edit_url: null
toc_max_heading_level: 4
keywords:
  - doxygen
  - reference
  - file

---

<div class="doxyPage">

# The `blake3.h` File Reference



## Included Headers

<div class="doxyIncludesList">#include &lt;stddef.h&gt;
#include &lt;stdint.h&gt;
</div>

## Classes Index

<table class="doxyMembersIndex">

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">struct</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="/web-llvm/docs/api/structs/llvm-blake3-chunk-state">llvm_blake3_chunk_state</a></td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">struct</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="/web-llvm/docs/api/structs/llvm-blake3-hasher">llvm_blake3_hasher</a></td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">void</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a8a051c13b70081b426f0c0693e6977af">llvm_blake3_hasher_init</a> (llvm_blake3_hasher *self)</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#aaf8dcf7da9729af05bec0662d3873280">llvm_blake3_hasher_init_keyed</a> (llvm_blake3_hasher *self, const uint8_t key[LLVM_BLAKE3_KEY_LEN])</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#acd67a8b965297a5e15381f1fea23fce6">llvm_blake3_hasher_init_derive_key</a> (llvm_blake3_hasher *self, const char *context)</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ae9a8ac402d13484bcb44c12d572fecb8">llvm_blake3_hasher_init_derive_key_raw</a> (llvm_blake3_hasher *self, const void *context, size_t context_len)</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a75e25f25c6fc1db9056087bbc458a0bc">llvm_blake3_hasher_update</a> (llvm_blake3_hasher *self, const void *input, size_t input_len)</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a269ade5376073ccdb1307a0daddaa1de">llvm_blake3_hasher_finalize</a> (const llvm_blake3_hasher *self, uint8_t *out, size_t out_len)</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ad3added645a514c2976352a72152c472">llvm_blake3_hasher_finalize_seek</a> (const llvm_blake3_hasher *self, uint64_t seek, uint8_t *out, size_t out_len)</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a368118adf27068d9bf7b8f34b8f9be7a">llvm_blake3_hasher_reset</a> (llvm_blake3_hasher *self)</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a8216867f66d19e003262d415eca974b6">LLVM_BLAKE3_VERSION_STRING</a>&nbsp;&nbsp;&nbsp;"1.3.1"</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ac6e51ba539cfceb419c6ba3f03338b47">LLVM_BLAKE3_KEY_LEN</a>&nbsp;&nbsp;&nbsp;32</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a9a7048b8a78d415916d028f4b8477cc3">LLVM_BLAKE3_OUT_LEN</a>&nbsp;&nbsp;&nbsp;32</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a5d4d4fedc4606bff70c4bf3e056cb074">LLVM_BLAKE3_BLOCK_LEN</a>&nbsp;&nbsp;&nbsp;64</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a1491f6d2cbf75dd218680d3c6bce5f0b">LLVM_BLAKE3_CHUNK_LEN</a>&nbsp;&nbsp;&nbsp;1024</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ab16d20f7cf5cddbaad0beb71b8313f89">LLVM_BLAKE3_MAX_DEPTH</a>&nbsp;&nbsp;&nbsp;54</td>
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

### llvm\_blake3\_hasher\_finalize() {#a269ade5376073ccdb1307a0daddaa1de}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void llvm_blake3_hasher_finalize (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/structs/llvm-blake3-hasher">llvm_blake3_hasher</a> * self, uint8_t * out, size_t out_len)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 68 of file <a href="/web-llvm/docs/api/files/include/include/llvm-c/blake3-h">blake3.h</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/classes/llvm/blake3/#a1d9661e1a088c345ba2868f46caaf460">llvm::BLAKE3::final</a> and <a href="/web-llvm/docs/api/classes/llvm/blake3/#a006c25a3aced3ec5ff196b8141161592">llvm::BLAKE3::final</a>.</p>

</div>
</div>

### llvm\_blake3\_hasher\_finalize\_seek() {#ad3added645a514c2976352a72152c472}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void llvm_blake3_hasher_finalize_seek (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/structs/llvm-blake3-hasher">llvm_blake3_hasher</a> * self, uint64_t seek, uint8_t * out, size_t out_len)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 70 of file <a href="/web-llvm/docs/api/files/include/include/llvm-c/blake3-h">blake3.h</a>.</p>

</div>
</div>

### llvm\_blake3\_hasher\_init() {#a8a051c13b70081b426f0c0693e6977af}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void llvm_blake3_hasher_init (<a href="/web-llvm/docs/api/structs/llvm-blake3-hasher">llvm_blake3_hasher</a> * self)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 58 of file <a href="/web-llvm/docs/api/files/include/include/llvm-c/blake3-h">blake3.h</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/classes/llvm/blake3/#ac459cabc1efbb1af18f617940113eccb">llvm::BLAKE3::init</a>.</p>

</div>
</div>

### llvm\_blake3\_hasher\_init\_derive\_key() {#acd67a8b965297a5e15381f1fea23fce6}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void llvm_blake3_hasher_init_derive_key (<a href="/web-llvm/docs/api/structs/llvm-blake3-hasher">llvm_blake3_hasher</a> * self, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> char * context)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 61 of file <a href="/web-llvm/docs/api/files/include/include/llvm-c/blake3-h">blake3.h</a>.</p>

</div>
</div>

### llvm\_blake3\_hasher\_init\_derive\_key\_raw() {#ae9a8ac402d13484bcb44c12d572fecb8}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void llvm_blake3_hasher_init_derive_key_raw (<a href="/web-llvm/docs/api/structs/llvm-blake3-hasher">llvm_blake3_hasher</a> * self, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> void * context, size_t context_len)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 63 of file <a href="/web-llvm/docs/api/files/include/include/llvm-c/blake3-h">blake3.h</a>.</p>

</div>
</div>

### llvm\_blake3\_hasher\_init\_keyed() {#aaf8dcf7da9729af05bec0662d3873280}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void llvm_blake3_hasher_init_keyed (<a href="/web-llvm/docs/api/structs/llvm-blake3-hasher">llvm_blake3_hasher</a> * self, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> uint8_t key=[LLVM_BLAKE3_KEY_LEN])</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 59 of file <a href="/web-llvm/docs/api/files/include/include/llvm-c/blake3-h">blake3.h</a>.</p>


<p>Reference <a href="#ac6e51ba539cfceb419c6ba3f03338b47">LLVM_BLAKE3_KEY_LEN</a>.</p>

</div>
</div>

### llvm\_blake3\_hasher\_reset() {#a368118adf27068d9bf7b8f34b8f9be7a}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void llvm_blake3_hasher_reset (<a href="/web-llvm/docs/api/structs/llvm-blake3-hasher">llvm_blake3_hasher</a> * self)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 73 of file <a href="/web-llvm/docs/api/files/include/include/llvm-c/blake3-h">blake3.h</a>.</p>

</div>
</div>

### llvm\_blake3\_hasher\_update() {#a75e25f25c6fc1db9056087bbc458a0bc}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void llvm_blake3_hasher_update (<a href="/web-llvm/docs/api/structs/llvm-blake3-hasher">llvm_blake3_hasher</a> * self, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> void * input, size_t input_len)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 66 of file <a href="/web-llvm/docs/api/files/include/include/llvm-c/blake3-h">blake3.h</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/classes/llvm/blake3/#ad247de2450380eeba2fab0e794d5e44f">llvm::BLAKE3::update</a> and <a href="/web-llvm/docs/api/classes/llvm/blake3/#a33ed2c1e4bb4b2bc6d3eb5c18bb8e754">llvm::BLAKE3::update</a>.</p>

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



<p>Declaration at line 57 of file <a href="/web-llvm/docs/api/files/include/include/llvm-c/blake3-h">blake3.h</a>, definition at line 15 of file <a href="/web-llvm/docs/api/files/lib/lib/support/lib/support/blake3/blake3-c">blake3.c</a>.</p>


<p>Reference <a href="/web-llvm/docs/api/files/lib/lib/support/lib/support/blake3/llvm-blake3-prefix-h/#a98986aaaab2221d6639d3e60f3682a91">BLAKE3_VERSION_STRING</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Macro Definitions

### LLVM\_BLAKE3\_BLOCK\_LEN {#a5d4d4fedc4606bff70c4bf3e056cb074}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">#define LLVM_BLAKE3_BLOCK_LEN&nbsp;&nbsp;&nbsp;64</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 30 of file <a href="/web-llvm/docs/api/files/include/include/llvm-c/blake3-h">blake3.h</a>.</p>

</div>
</div>

### LLVM\_BLAKE3\_CHUNK\_LEN {#a1491f6d2cbf75dd218680d3c6bce5f0b}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">#define LLVM_BLAKE3_CHUNK_LEN&nbsp;&nbsp;&nbsp;1024</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 31 of file <a href="/web-llvm/docs/api/files/include/include/llvm-c/blake3-h">blake3.h</a>.</p>

</div>
</div>

### LLVM\_BLAKE3\_KEY\_LEN {#ac6e51ba539cfceb419c6ba3f03338b47}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">#define LLVM_BLAKE3_KEY_LEN&nbsp;&nbsp;&nbsp;32</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 28 of file <a href="/web-llvm/docs/api/files/include/include/llvm-c/blake3-h">blake3.h</a>.</p>


<p>Referenced by <a href="#aaf8dcf7da9729af05bec0662d3873280">llvm_blake3_hasher_init_keyed</a>.</p>

</div>
</div>

### LLVM\_BLAKE3\_MAX\_DEPTH {#ab16d20f7cf5cddbaad0beb71b8313f89}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">#define LLVM_BLAKE3_MAX_DEPTH&nbsp;&nbsp;&nbsp;54</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 32 of file <a href="/web-llvm/docs/api/files/include/include/llvm-c/blake3-h">blake3.h</a>.</p>

</div>
</div>

### LLVM\_BLAKE3\_OUT\_LEN {#a9a7048b8a78d415916d028f4b8477cc3}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">#define LLVM_BLAKE3_OUT_LEN&nbsp;&nbsp;&nbsp;32</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 29 of file <a href="/web-llvm/docs/api/files/include/include/llvm-c/blake3-h">blake3.h</a>.</p>

</div>
</div>

### LLVM\_BLAKE3\_VERSION\_STRING {#a8216867f66d19e003262d415eca974b6}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">#define LLVM_BLAKE3_VERSION_STRING&nbsp;&nbsp;&nbsp;"1.3.1"</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 27 of file <a href="/web-llvm/docs/api/files/include/include/llvm-c/blake3-h">blake3.h</a>.</p>

</div>
</div>

</div>

<hr/>

<p class="doxyGeneratedBy">Generated via <a href="https://github.com/xpack/doxygen2docusaurus">doxygen2docusaurus</a> by <a href="https://www.doxygen.nl">Doxygen</a> 1.14.0.</p>

</div>
