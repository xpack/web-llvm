---

# DO NOT EDIT!
# Automatically generated via doxygen2docusaurus by Doxygen.

slug: /api/structs/llvm/hashing/detail/hash-combine-recursive-helper
custom_edit_url: null
toc_max_heading_level: 4
keywords:
  - doxygen
  - reference
  - struct

---

<div class="doxyPage">

# The `hash_combine_recursive_helper` Struct Reference

<p>Helper class to manage the recursive combining of hash_combine arguments. <a href="#details">More...</a></p>

## Declaration

<div class="doxyDeclaration">
struct llvm::hashing::detail::hash_combine_recursive_helper { ... }
</div>

## Included Headers

<div class="doxyIncludesList">#include "<a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/adt/hashing-h">llvm/ADT/Hashing.h</a>"
</div>

## Public Constructors Index

<table class="doxyMembersIndex">

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#aed86896537853171897bf29f113e382f">hash_combine_recursive_helper</a> ()</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Construct a recursive hash combining helper. <a href="#aed86896537853171897bf29f113e382f">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

</table>

## Public Member Functions Index

<table class="doxyMembersIndex">

<tr class="doxyMemberIndexTemplate">
<td class="doxyMemberIndexTemplate" colspan="2"><div>template &lt;typename T&gt;</div></td>
</tr>
<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemTypeTemplate" align="left" valign="top">char *</td>
<td class="doxyMemberIndexItemNameTemplate" align="left" valign="top"><a href="#a87cb33524db506474a9207907036a397">combine_data</a> (size_t &amp;length, char *buffer_ptr, char *buffer_end, T data)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Combine one chunk of data into the current in-flight hash. <a href="#a87cb33524db506474a9207907036a397">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexTemplate">
<td class="doxyMemberIndexTemplate" colspan="2"><div>template &lt;typename T, typename ... Ts&gt;</div></td>
</tr>
<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemTypeTemplate" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/hash-code">hash_code</a></td>
<td class="doxyMemberIndexItemNameTemplate" align="left" valign="top"><a href="#ae78cbf87cf9f0f59522d779be5d49cbb">combine</a> (size_t length, char *buffer_ptr, char *buffer_end, const T &amp;arg, const Ts &amp;...args)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Recursive, variadic combining method. <a href="#ae78cbf87cf9f0f59522d779be5d49cbb">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/hash-code">hash_code</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a3f4bcef234eab8fcdd8e4496777e5a9b">combine</a> (size_t length, char *buffer_ptr, char *buffer_end)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Base case for recursive, variadic combining. <a href="#a3f4bcef234eab8fcdd8e4496777e5a9b">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

</table>

## Public Member Attributes Index

<table class="doxyMembersIndex">

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">char</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a9e4f6895ae5d3fc7cef9a42a9a6667e2">buffer</a>[64] = {}</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/structs/llvm/hashing/detail/hash-state">hash_state</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ab3a478c7eb60d5611567b565b6d7a036">state</a></td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> uint64_t</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ae2729f7986639d793d41f13ab4707c7b">seed</a></td>
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

## Description {#details}

<p>Helper class to manage the recursive combining of hash_combine arguments.</p>


<p>This class exists to manage the state and various calls involved in the recursive combining of arguments used in hash_combine. It is particularly useful at minimizing the code in the recursive calls to ease the pain caused by a lack of variadic functions.</p>


<p>Definition at line 484 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/adt/hashing-h">Hashing.h</a>.</p>


<div class="doxySectionDef">

## Public Constructors

### hash\_combine\_recursive\_helper() {#aed86896537853171897bf29f113e382f}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">llvm::hashing::detail::hash_combine_recursive_helper::hash_combine_recursive_helper ()</td>
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

<p>Construct a recursive hash combining helper.</p>


<p>This sets up the state for a recursive hash combine, including getting the seed and buffer setup.</p>


<p>Definition at line 494 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/adt/hashing-h">Hashing.h</a>.</p>


<p>References <a href="/web-llvm/docs/api/namespaces/llvm/hashing/detail/#a8a572c218eb50cd07af7265347c113a8">llvm::hashing::detail::get_execution_seed</a> and <a href="#ae2729f7986639d793d41f13ab4707c7b">seed</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Public Member Functions

### combine() {#ae78cbf87cf9f0f59522d779be5d49cbb}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<div class="doxyMemberTemplate">template &lt;typename T, typename ... Ts&gt;</div>
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">hash_code llvm::hashing::detail::hash_combine_recursive_helper::combine (size_t length, char * buffer_ptr, char * buffer_end, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> T &amp; arg, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> Ts &amp;... args)</td>
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

<p>Recursive, variadic combining method.</p>


<p>This function recurses through each argument, combining that argument into a single hash.</p>


<p>Definition at line 543 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/adt/hashing-h">Hashing.h</a>.</p>


<p>References <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/nvptx/nvptxlowerargs-cpp/#a4d6da696b3c753c5e5fbcc4d21d4cb71">args</a>, <a href="#ae78cbf87cf9f0f59522d779be5d49cbb">combine</a>, <a href="#a87cb33524db506474a9207907036a397">combine_data</a>, <a href="/web-llvm/docs/api/namespaces/llvm/hashing/detail/#a4d42cd18d93c269fe8878db27f2ff8cc">llvm::hashing::detail::get_hashable_data</a> and <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/mips/mips16isellowering-cpp/#a0acb682b8260ab1c60b918599864e2e5">T</a>.</p>


<p>Referenced by <a href="#ae78cbf87cf9f0f59522d779be5d49cbb">combine</a> and <a href="/web-llvm/docs/api/namespaces/llvm/#add71474638430694c84640146383fc44">llvm::hash_combine</a>.</p>

</div>
</div>

### combine() {#a3f4bcef234eab8fcdd8e4496777e5a9b}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">hash_code llvm::hashing::detail::hash_combine_recursive_helper::combine (size_t length, char * buffer_ptr, char * buffer_end)</td>
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

<p>Base case for recursive, variadic combining.</p>


<p>The base case when combining arguments recursively is reached when all arguments have been handled. It flushes the remaining buffer and constructs a <a href="/web-llvm/docs/api/classes/llvm/hash-code">hash_code</a>.</p>


<p>Definition at line 556 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/adt/hashing-h">Hashing.h</a>.</p>


<p>References <a href="#a9e4f6895ae5d3fc7cef9a42a9a6667e2">buffer</a>, <a href="/web-llvm/docs/api/namespaces/llvm/hashing/detail/#a9f8d3250fbca36e49b9c1304f31bdfb8">llvm::hashing::detail::hash_short</a>, <a href="#ae2729f7986639d793d41f13ab4707c7b">seed</a> and <a href="#ab3a478c7eb60d5611567b565b6d7a036">state</a>.</p>

</div>
</div>

### combine\_data() {#a87cb33524db506474a9207907036a397}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<div class="doxyMemberTemplate">template &lt;typename T&gt;</div>
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">char * llvm::hashing::detail::hash_combine_recursive_helper::combine_data (size_t &amp; length, char * buffer_ptr, char * buffer_end, T data)</td>
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

<p>Combine one chunk of data into the current in-flight hash.</p>


<p>This merges one chunk of data into the hash. First it tries to buffer the data. If the buffer is full, it hashes the buffer into its <a href="/web-llvm/docs/api/structs/llvm/hashing/detail/hash-state">hash_state</a>, empties it, and then merges the new chunk in. This also handles cases where the data straddles the end of the buffer.</p>


<p>Definition at line 504 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/adt/hashing-h">Hashing.h</a>.</p>


<p>References <a href="#a9e4f6895ae5d3fc7cef9a42a9a6667e2">buffer</a>, <a href="/web-llvm/docs/api/files/lib/lib/codegen/staticdatasplitter-cpp/#ad2fefd8832b4b1ea3dbb1f621063bbff">data</a>, <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/support/errorhandling-h/#ace243f5c25697a1107cce46626b3dc94">llvm_unreachable</a>, <a href="#ae2729f7986639d793d41f13ab4707c7b">seed</a>, <a href="#ab3a478c7eb60d5611567b565b6d7a036">state</a>, <a href="/web-llvm/docs/api/namespaces/llvm/hashing/detail/#a0e6505cf45fca2d42d6d02ba7fcde5b8">llvm::hashing::detail::store_and_advance</a> and <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/mips/mips16isellowering-cpp/#a0acb682b8260ab1c60b918599864e2e5">T</a>.</p>


<p>Referenced by <a href="#ae78cbf87cf9f0f59522d779be5d49cbb">combine</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Public Member Attributes

### buffer {#a9e4f6895ae5d3fc7cef9a42a9a6667e2}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">char llvm::hashing::detail::hash_combine_recursive_helper::buffer[64] = {}</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 485 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/adt/hashing-h">Hashing.h</a>.</p>


<p>Referenced by <a href="#a3f4bcef234eab8fcdd8e4496777e5a9b">combine</a>, <a href="#a87cb33524db506474a9207907036a397">combine_data</a> and <a href="/web-llvm/docs/api/namespaces/llvm/#add71474638430694c84640146383fc44">llvm::hash_combine</a>.</p>

</div>
</div>

### seed {#ae2729f7986639d793d41f13ab4707c7b}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">const uint64_t llvm::hashing::detail::hash_combine_recursive_helper::seed</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 487 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/adt/hashing-h">Hashing.h</a>.</p>


<p>Referenced by <a href="#a3f4bcef234eab8fcdd8e4496777e5a9b">combine</a>, <a href="#a87cb33524db506474a9207907036a397">combine_data</a> and <a href="#aed86896537853171897bf29f113e382f">hash_combine_recursive_helper</a>.</p>

</div>
</div>

### state {#ab3a478c7eb60d5611567b565b6d7a036}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">hash_state llvm::hashing::detail::hash_combine_recursive_helper::state</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 486 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/adt/hashing-h">Hashing.h</a>.</p>


<p>Referenced by <a href="#a3f4bcef234eab8fcdd8e4496777e5a9b">combine</a> and <a href="#a87cb33524db506474a9207907036a397">combine_data</a>.</p>

</div>
</div>

</div>

<hr/>

The documentation for this struct was generated from the following file:

<ul>
<li><a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/adt/hashing-h">Hashing.h</a></li>
</ul>

<hr/>

<p class="doxyGeneratedBy">Generated via <a href="https://github.com/xpack/doxygen2docusaurus">doxygen2docusaurus</a> by <a href="https://www.doxygen.nl">Doxygen</a> 1.14.0.</p>

</div>
