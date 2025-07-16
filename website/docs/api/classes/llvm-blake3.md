---

# DO NOT EDIT!
# Automatically generated via doxygen2docusaurus by Doxygen.

slug: /api/classes/llvm/blake3
custom_edit_url: null
toc_max_heading_level: 4
keywords:
  - doxygen
  - reference
  - class

---

<div class="doxyPage">

# The `BLAKE3` Class Reference

<p>A class that wraps the <a href="/web-llvm/docs/api/classes/llvm/blake3">BLAKE3</a> algorithm. <a href="#details">More...</a></p>

## Declaration

<div class="doxyDeclaration">
class llvm::BLAKE3 { ... }
</div>

## Included Headers

<div class="doxyIncludesList">#include "<a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/support/blake3-h">llvm/Support/BLAKE3.h</a>"
</div>

## Derived Classes

<table class="doxyMembersIndex">

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">class</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/truncatedblake3">TruncatedBLAKE3&lt;NumBytes&gt;</a></td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Like <span class="doxyComputerOutput"><a href="/web-llvm/docs/api/classes/llvm/blake3">BLAKE3</a></span> but using a class-level template parameter for specifying the hash size of the <span class="doxyComputerOutput"><a href="/web-llvm/docs/api/classes/llvm/truncatedblake3/#a74a099d51430f54417d27af6f552d183">final()</a></span> and <span class="doxyComputerOutput"><a href="/web-llvm/docs/api/classes/llvm/truncatedblake3/#adda4f5df8b748e9f3c27dc9872b52330">result()</a></span> functions. <a href="/web-llvm/docs/api/classes/llvm/truncatedblake3/#details">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

</table>

## Public Constructors Index

<table class="doxyMembersIndex">

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a644fa97693cc8ab6aa3e6b36d0986e73">BLAKE3</a> ()</td>
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

## Public Member Functions Index

<table class="doxyMembersIndex">

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">void</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ac459cabc1efbb1af18f617940113eccb">init</a> ()</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Reinitialize the internal state. <a href="#ac459cabc1efbb1af18f617940113eccb">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">void</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ad247de2450380eeba2fab0e794d5e44f">update</a> (ArrayRef&lt; uint8_t &gt; Data)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Digest more data. <a href="#ad247de2450380eeba2fab0e794d5e44f">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">void</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a33ed2c1e4bb4b2bc6d3eb5c18bb8e754">update</a> (StringRef Str)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Digest more data. <a href="#a33ed2c1e4bb4b2bc6d3eb5c18bb8e754">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexTemplate">
<td class="doxyMemberIndexTemplate" colspan="2"><div>template &lt;size_t NumBytes = LLVM_BLAKE3_OUT_LEN&gt;</div></td>
</tr>
<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemTypeTemplate" align="left" valign="top">void</td>
<td class="doxyMemberIndexItemNameTemplate" align="left" valign="top"><a href="#a006c25a3aced3ec5ff196b8141161592">final</a> (BLAKE3Result&lt; NumBytes &gt; &amp;Result)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Finalize the hasher and put the result in <span class="doxyComputerOutput">Result</span>. <a href="#a006c25a3aced3ec5ff196b8141161592">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexTemplate">
<td class="doxyMemberIndexTemplate" colspan="2"><div>template &lt;size_t NumBytes = LLVM_BLAKE3_OUT_LEN&gt;</div></td>
</tr>
<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemTypeTemplate" align="left" valign="top">auto </td>
<td class="doxyMemberIndexItemNameTemplate" align="left" valign="top"><a href="#a1d9661e1a088c345ba2868f46caaf460">final</a> () -&gt; <a href="/web-llvm/docs/api/namespaces/llvm/#a081d38a75bd71be1f6b2db493b46c70e">BLAKE3Result</a>&lt; NumBytes &gt;</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Finalize the hasher and return an output of any length, given in bytes. <a href="#a1d9661e1a088c345ba2868f46caaf460">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexTemplate">
<td class="doxyMemberIndexTemplate" colspan="2"><div>template &lt;size_t NumBytes = LLVM_BLAKE3_OUT_LEN&gt;</div></td>
</tr>
<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemTypeTemplate" align="left" valign="top">auto </td>
<td class="doxyMemberIndexItemNameTemplate" align="left" valign="top"><a href="#ab6da7d121372343d7fced230ad454f18">result</a> () -&gt; <a href="/web-llvm/docs/api/namespaces/llvm/#a081d38a75bd71be1f6b2db493b46c70e">BLAKE3Result</a>&lt; NumBytes &gt;</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Return the current output for the digested data since the last call to <a href="#ac459cabc1efbb1af18f617940113eccb">init()</a>. <a href="#ab6da7d121372343d7fced230ad454f18">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

</table>

## Private Member Attributes Index

<table class="doxyMembersIndex">

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/structs/llvm-blake3-hasher">llvm_blake3_hasher</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a7583b8e13e8680cc8e6e2f7d88eefde6">Hasher</a></td>
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

## Public Static Functions Index

<table class="doxyMembersIndex">

<tr class="doxyMemberIndexTemplate">
<td class="doxyMemberIndexTemplate" colspan="2"><div>template &lt;size_t NumBytes = LLVM_BLAKE3_OUT_LEN&gt;</div></td>
</tr>
<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemTypeTemplate" align="left" valign="top">static auto </td>
<td class="doxyMemberIndexItemNameTemplate" align="left" valign="top"><a href="#a9dbdb16a7c1e784048a1a7f65821f5be">hash</a> (ArrayRef&lt; uint8_t &gt; Data) -&gt; <a href="/web-llvm/docs/api/namespaces/llvm/#a081d38a75bd71be1f6b2db493b46c70e">BLAKE3Result</a>&lt; NumBytes &gt;</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Returns a <a href="/web-llvm/docs/api/classes/llvm/blake3">BLAKE3</a> hash for the given data. <a href="#a9dbdb16a7c1e784048a1a7f65821f5be">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

</table>

## Description {#details}

<p>A class that wraps the <a href="/web-llvm/docs/api/classes/llvm/blake3">BLAKE3</a> algorithm.</p>

<p>Definition at line 38 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/support/blake3-h">BLAKE3.h</a>.</p>


<div class="doxySectionDef">

## Public Constructors

### BLAKE3() {#a644fa97693cc8ab6aa3e6b36d0986e73}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">llvm::BLAKE3::BLAKE3 ()</td>
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



<p>Definition at line 40 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/support/blake3-h">BLAKE3.h</a>.</p>


<p>Reference <a href="#ac459cabc1efbb1af18f617940113eccb">init</a>.</p>


<p>Referenced by <a href="#a9dbdb16a7c1e784048a1a7f65821f5be">hash</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Public Member Functions

### final() {#a006c25a3aced3ec5ff196b8141161592}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<div class="doxyMemberTemplate">template &lt;size_t NumBytes = LLVM_BLAKE3_OUT_LEN&gt;</div>
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void llvm::BLAKE3::final (<a href="/web-llvm/docs/api/namespaces/llvm/#a081d38a75bd71be1f6b2db493b46c70e">BLAKE3Result</a>&lt; NumBytes &gt; &amp; Result)</td>
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

<p>Finalize the hasher and put the result in <span class="doxyComputerOutput">Result</span>.</p>


<p>This doesn't modify the hasher itself, and it's possible to finalize again after adding more input.</p>


<p>Definition at line 59 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/support/blake3-h">BLAKE3.h</a>.</p>


<p>Reference <a href="/web-llvm/docs/api/files/include/include/llvm-c/blake3-h/#a269ade5376073ccdb1307a0daddaa1de">llvm_blake3_hasher_finalize</a>.</p>

</div>
</div>

### final() {#a1d9661e1a088c345ba2868f46caaf460}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<div class="doxyMemberTemplate">template &lt;size_t NumBytes = LLVM_BLAKE3_OUT_LEN&gt;</div>
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">BLAKE3Result&lt; NumBytes &gt; llvm::BLAKE3::final ()</td>
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

<p>Finalize the hasher and return an output of any length, given in bytes.</p>


<p>This doesn't modify the hasher itself, and it's possible to finalize again after adding more input.</p>


<p>Definition at line 67 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/support/blake3-h">BLAKE3.h</a>.</p>


<p>Reference <a href="/web-llvm/docs/api/files/include/include/llvm-c/blake3-h/#a269ade5376073ccdb1307a0daddaa1de">llvm_blake3_hasher_finalize</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/classes/llvm/truncatedblake3/#a74a099d51430f54417d27af6f552d183">llvm::TruncatedBLAKE3&lt; NumBytes &gt;::final</a>, <a href="/web-llvm/docs/api/classes/llvm/truncatedblake3/#a289292a235757336d881f2d2786b09bd">llvm::TruncatedBLAKE3&lt; NumBytes &gt;::final</a> and <a href="#ab6da7d121372343d7fced230ad454f18">result</a>.</p>

</div>
</div>

### init() {#ac459cabc1efbb1af18f617940113eccb}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void llvm::BLAKE3::init ()</td>
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

<p>Reinitialize the internal state.</p>

<p>Definition at line 43 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/support/blake3-h">BLAKE3.h</a>.</p>


<p>Reference <a href="/web-llvm/docs/api/files/include/include/llvm-c/blake3-h/#a8a051c13b70081b426f0c0693e6977af">llvm_blake3_hasher_init</a>.</p>


<p>Referenced by <a href="#a644fa97693cc8ab6aa3e6b36d0986e73">BLAKE3</a> and <a href="/web-llvm/docs/api/structs/llvm/codeview/globallyhashedtype/#acc7b052c15351bf328b64c17027eae9d">llvm::codeview::GloballyHashedType::hashType</a>.</p>

</div>
</div>

### result() {#ab6da7d121372343d7fced230ad454f18}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<div class="doxyMemberTemplate">template &lt;size_t NumBytes = LLVM_BLAKE3_OUT_LEN&gt;</div>
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">BLAKE3Result&lt; NumBytes &gt; llvm::BLAKE3::result ()</td>
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

<p>Return the current output for the digested data since the last call to <a href="#ac459cabc1efbb1af18f617940113eccb">init()</a>.</p>


<p>Other hash functions distinguish between <span class="doxyComputerOutput"><a href="#ab6da7d121372343d7fced230ad454f18">result()</a></span> and <span class="doxyComputerOutput"><a href="#a1d9661e1a088c345ba2868f46caaf460">final()</a></span>, with <span class="doxyComputerOutput"><a href="#ab6da7d121372343d7fced230ad454f18">result()</a></span> allowing more calls into <span class="doxyComputerOutput"><a href="#ad247de2450380eeba2fab0e794d5e44f">update()</a></span>, but there's no</p>


<p>Definition at line 80 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/support/blake3-h">BLAKE3.h</a>.</p>


<p>Reference <a href="#a1d9661e1a088c345ba2868f46caaf460">final</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/classes/llvm/truncatedblake3/#adda4f5df8b748e9f3c27dc9872b52330">llvm::TruncatedBLAKE3&lt; NumBytes &gt;::result</a>.</p>

</div>
</div>

### update() {#ad247de2450380eeba2fab0e794d5e44f}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void llvm::BLAKE3::update (<a href="/web-llvm/docs/api/classes/llvm/arrayref">ArrayRef</a>&lt; uint8_t &gt; Data)</td>
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

<p>Digest more data.</p>

<p>Definition at line 46 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/support/blake3-h">BLAKE3.h</a>.</p>


<p>References <a href="/web-llvm/docs/api/namespaces/llvm/#aa20539e89704d20b98b97e9c3feac934">llvm::Data</a> and <a href="/web-llvm/docs/api/files/include/include/llvm-c/blake3-h/#a75e25f25c6fc1db9056087bbc458a0bc">llvm_blake3_hasher_update</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/structs/llvm/codeview/globallyhashedtype/#acc7b052c15351bf328b64c17027eae9d">llvm::codeview::GloballyHashedType::hashType</a>.</p>

</div>
</div>

### update() {#a33ed2c1e4bb4b2bc6d3eb5c18bb8e754}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void llvm::BLAKE3::update (<a href="/web-llvm/docs/api/classes/llvm/stringref">StringRef</a> Str)</td>
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

<p>Digest more data.</p>

<p>Definition at line 51 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/support/blake3-h">BLAKE3.h</a>.</p>


<p>Reference <a href="/web-llvm/docs/api/files/include/include/llvm-c/blake3-h/#a75e25f25c6fc1db9056087bbc458a0bc">llvm_blake3_hasher_update</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Private Member Attributes

### Hasher {#a7583b8e13e8680cc8e6e2f7d88eefde6}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">llvm_blake3_hasher llvm::BLAKE3::Hasher</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 93 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/support/blake3-h">BLAKE3.h</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Public Static Functions

### hash() {#a9dbdb16a7c1e784048a1a7f65821f5be}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<div class="doxyMemberTemplate">template &lt;size_t NumBytes = LLVM_BLAKE3_OUT_LEN&gt;</div>
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">BLAKE3Result&lt; NumBytes &gt; llvm::BLAKE3::hash (<a href="/web-llvm/docs/api/classes/llvm/arrayref">ArrayRef</a>&lt; uint8_t &gt; Data)</td>
</tr>
</table>
</td>
<td class="doxyMemberLabelsRight">
<span class="doxyMemberLabels">
<span class="doxyMemberLabel inline">inline</span>
<span class="doxyMemberLabel static">static</span>
</span>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Returns a <a href="/web-llvm/docs/api/classes/llvm/blake3">BLAKE3</a> hash for the given data.</p>

<p>Definition at line 86 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/support/blake3-h">BLAKE3.h</a>.</p>


<p>References <a href="#a644fa97693cc8ab6aa3e6b36d0986e73">BLAKE3</a> and <a href="/web-llvm/docs/api/namespaces/llvm/#aa20539e89704d20b98b97e9c3feac934">llvm::Data</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/classes/llvm/orc/rt-bootstrap/executorsharedmemorymapperservice/#aded6fc2ddd0d73f2f6b24beff42b70ea">llvm::orc::rt_bootstrap::ExecutorSharedMemoryMapperService::reserve</a> and <a href="/web-llvm/docs/api/classes/llvm/orc/sharedmemorymapper/#a422f2a2c01a04dbb4fe4100fc74b90ca">llvm::orc::SharedMemoryMapper::reserve</a>.</p>

</div>
</div>

</div>

<hr/>

The documentation for this class was generated from the following file:

<ul>
<li><a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/support/blake3-h">BLAKE3.h</a></li>
</ul>

<hr/>

<p class="doxyGeneratedBy">Generated via <a href="https://github.com/xpack/doxygen2docusaurus">doxygen2docusaurus</a> by <a href="https://www.doxygen.nl">Doxygen</a> 1.15.0.</p>

</div>
