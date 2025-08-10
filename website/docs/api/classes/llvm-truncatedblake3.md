---

# DO NOT EDIT!
# Automatically generated via doxygen2docusaurus by Doxygen.

slug: /api/classes/llvm/truncatedblake3
custom_edit_url: null
toc_max_heading_level: 4
keywords:
  - doxygen
  - reference
  - class

---

<div class="doxyPage">

# `TruncatedBLAKE3` Class Template

<p>Like <span class="doxyComputerOutput"><a href="/web-llvm/docs/api/classes/llvm/blake3">BLAKE3</a></span> but using a class-level template parameter for specifying the hash size of the <span class="doxyComputerOutput"><a href="#a74a099d51430f54417d27af6f552d183">final()</a></span> and <span class="doxyComputerOutput"><a href="#adda4f5df8b748e9f3c27dc9872b52330">result()</a></span> functions. <a href="#details">More...</a></p>

## Declaration

<div class="doxyDeclaration">
template &lt;size_t NumBytes&gt;
class llvm::TruncatedBLAKE3&lt;NumBytes&gt; { ... }
</div>

## Included Headers

<div class="doxyIncludesList">#include "<a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/support/blake3-h">llvm/Support/BLAKE3.h</a>"
</div>

## Base class

<table class="doxyMembersIndex">

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">class</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/blake3">BLAKE3</a></td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>A class that wraps the <a href="/web-llvm/docs/api/classes/llvm/blake3">BLAKE3</a> algorithm. <a href="/web-llvm/docs/api/classes/llvm/blake3/#details">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

</table>

## Public Member Functions Index

<table class="doxyMembersIndex">

<tr class="doxyMemberIndexTemplate">
<td class="doxyMemberIndexTemplate" colspan="2"><div>template &lt;size_t NumBytes&gt;</div></td>
</tr>
<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemTypeTemplate" align="left" valign="top">void</td>
<td class="doxyMemberIndexItemNameTemplate" align="left" valign="top"><a href="#a289292a235757336d881f2d2786b09bd">final</a> (BLAKE3Result&lt; NumBytes &gt; &amp;Result)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Finalize the hasher and put the result in <span class="doxyComputerOutput">Result</span>. <a href="#a289292a235757336d881f2d2786b09bd">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexTemplate">
<td class="doxyMemberIndexTemplate" colspan="2"><div>template &lt;size_t NumBytes&gt;</div></td>
</tr>
<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemTypeTemplate" align="left" valign="top">auto </td>
<td class="doxyMemberIndexItemNameTemplate" align="left" valign="top"><a href="#a74a099d51430f54417d27af6f552d183">final</a> () -&gt; <a href="/web-llvm/docs/api/namespaces/llvm/#a081d38a75bd71be1f6b2db493b46c70e">BLAKE3Result</a>&lt; NumBytes &gt;</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Finalize the hasher and return an output of any length, given in bytes. <a href="#a74a099d51430f54417d27af6f552d183">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexTemplate">
<td class="doxyMemberIndexTemplate" colspan="2"><div>template &lt;size_t NumBytes&gt;</div></td>
</tr>
<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemTypeTemplate" align="left" valign="top">auto </td>
<td class="doxyMemberIndexItemNameTemplate" align="left" valign="top"><a href="#adda4f5df8b748e9f3c27dc9872b52330">result</a> () -&gt; <a href="/web-llvm/docs/api/namespaces/llvm/#a081d38a75bd71be1f6b2db493b46c70e">BLAKE3Result</a>&lt; NumBytes &gt;</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Return the current output for the digested data since the last call to <a href="/web-llvm/docs/api/classes/llvm/blake3/#ac459cabc1efbb1af18f617940113eccb">init()</a>. <a href="#adda4f5df8b748e9f3c27dc9872b52330">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

</table>

## Description {#details}

<p>Like <span class="doxyComputerOutput"><a href="/web-llvm/docs/api/classes/llvm/blake3">BLAKE3</a></span> but using a class-level template parameter for specifying the hash size of the <span class="doxyComputerOutput"><a href="#a74a099d51430f54417d27af6f552d183">final()</a></span> and <span class="doxyComputerOutput"><a href="#adda4f5df8b748e9f3c27dc9872b52330">result()</a></span> functions.</p>


<p>This is useful for using <a href="/web-llvm/docs/api/classes/llvm/blake3">BLAKE3</a> as the hasher type for <span class="doxyComputerOutput"><a href="/web-llvm/docs/api/classes/llvm/hashbuilder">HashBuilder</a></span> with non-default hash sizes.</p>


<p>Definition at line 101 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/support/blake3-h">BLAKE3.h</a>.</p>


<div class="doxySectionDef">

## Public Member Functions

### final() {#a289292a235757336d881f2d2786b09bd}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<div class="doxyMemberTemplate">template &lt;size_t NumBytes&gt;</div>
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void llvm::TruncatedBLAKE3&lt; NumBytes &gt;::final (<a href="/web-llvm/docs/api/namespaces/llvm/#a081d38a75bd71be1f6b2db493b46c70e">BLAKE3Result</a>&lt; NumBytes &gt; &amp; Result)</td>
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


<p>Definition at line 106 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/support/blake3-h">BLAKE3.h</a>.</p>


<p>Reference <a href="/web-llvm/docs/api/classes/llvm/blake3/#a1d9661e1a088c345ba2868f46caaf460">llvm::BLAKE3::final</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/structs/llvm/codeview/globallyhashedtype/#acc7b052c15351bf328b64c17027eae9d">llvm::codeview::GloballyHashedType::hashType</a>.</p>

</div>
</div>

### final() {#a74a099d51430f54417d27af6f552d183}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<div class="doxyMemberTemplate">template &lt;size_t NumBytes&gt;</div>
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">BLAKE3Result&lt; NumBytes &gt; llvm::TruncatedBLAKE3&lt; NumBytes &gt;::final ()</td>
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


<p>Definition at line 111 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/support/blake3-h">BLAKE3.h</a>.</p>


<p>Reference <a href="/web-llvm/docs/api/classes/llvm/blake3/#a1d9661e1a088c345ba2868f46caaf460">llvm::BLAKE3::final</a>.</p>

</div>
</div>

### result() {#adda4f5df8b748e9f3c27dc9872b52330}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<div class="doxyMemberTemplate">template &lt;size_t NumBytes&gt;</div>
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">BLAKE3Result&lt; NumBytes &gt; llvm::TruncatedBLAKE3&lt; NumBytes &gt;::result ()</td>
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

<p>Return the current output for the digested data since the last call to <a href="/web-llvm/docs/api/classes/llvm/blake3/#ac459cabc1efbb1af18f617940113eccb">init()</a>.</p>


<p>Other hash functions distinguish between <span class="doxyComputerOutput"><a href="#adda4f5df8b748e9f3c27dc9872b52330">result()</a></span> and <span class="doxyComputerOutput"><a href="#a74a099d51430f54417d27af6f552d183">final()</a></span>, with <span class="doxyComputerOutput"><a href="#adda4f5df8b748e9f3c27dc9872b52330">result()</a></span> allowing more calls into <span class="doxyComputerOutput"><a href="/web-llvm/docs/api/classes/llvm/blake3/#ad247de2450380eeba2fab0e794d5e44f">update()</a></span>, but there's no</p>


<p>Definition at line 119 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/support/blake3-h">BLAKE3.h</a>.</p>


<p>Reference <a href="/web-llvm/docs/api/classes/llvm/blake3/#ab6da7d121372343d7fced230ad454f18">llvm::BLAKE3::result</a>.</p>

</div>
</div>

</div>

<hr/>

The documentation for this class was generated from the following file:

<ul>
<li><a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/support/blake3-h">BLAKE3.h</a></li>
</ul>

<hr/>

<p class="doxyGeneratedBy">Generated via <a href="https://xpack.github.io/doxygen2docusaurus">doxygen2docusaurus</a> 2.0.0 by <a href="https://www.doxygen.nl">Doxygen</a> 1.15.0.</p>

</div>
