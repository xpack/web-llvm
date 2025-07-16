---

# DO NOT EDIT!
# Automatically generated via doxygen2docusaurus by Doxygen.

slug: /api/structs/llvm/xray/anonymous-fdrtracewriter-cpp-/indexedwriter
custom_edit_url: null
toc_max_heading_level: 4
keywords:
  - doxygen
  - reference
  - struct

---

<div class="doxyPage">

# The `IndexedWriter` Struct Template Reference



## Declaration

<div class="doxyDeclaration">
template &lt;size_t Index&gt;
struct llvm::xray::anonymous{FDRTraceWriter.cpp}::IndexedWriter&lt;Index&gt; { ... }
</div>

## Public Static Functions Index

<table class="doxyMembersIndex">

<tr class="doxyMemberIndexTemplate">
<td class="doxyMemberIndexTemplate" colspan="2"><div>template &lt; ... &gt;</div></td>
</tr>
<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemTypeTemplate" align="left" valign="top">static size_t</td>
<td class="doxyMemberIndexItemNameTemplate" align="left" valign="top"><a href="#a1c231cc18850380661428875e8c99822">write</a> (support::endian::Writer &amp;OS, Tuple &amp;&amp;T)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexTemplate">
<td class="doxyMemberIndexTemplate" colspan="2"><div>template &lt; ... &gt;</div></td>
</tr>
<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemTypeTemplate" align="left" valign="top">static size_t</td>
<td class="doxyMemberIndexItemNameTemplate" align="left" valign="top"><a href="#ae45fee095a4a7fd821218b2a2e5f0de7">write</a> (support::endian::Writer &amp;OS, Tuple &amp;&amp;)</td>
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


<p>Definition at line 20 of file <a href="/web-llvm/docs/api/files/lib/lib/xray/fdrtracewriter-cpp">FDRTraceWriter.cpp</a>.</p>


<div class="doxySectionDef">

## Public Static Functions

### write() {#a1c231cc18850380661428875e8c99822}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<div class="doxyMemberTemplate">template &lt;class Tuple, std::enable_if_t&lt;(Index&lt; std::tuple_size&lt; std::remove_reference_t&lt; Tuple &gt; &gt;::value), int &gt; = 0&gt;</div>
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">size_t llvm::xray::anonymous{FDRTraceWriter.cpp}::IndexedWriter&lt; Index &gt;::write (<a href="/web-llvm/docs/api/structs/llvm/support/endian/writer">support::endian::Writer</a> &amp; OS, Tuple &amp;&amp; T)</td>
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



<p>Definition at line 26 of file <a href="/web-llvm/docs/api/files/lib/lib/xray/fdrtracewriter-cpp">FDRTraceWriter.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/mips/mips16isellowering-cpp/#a0acb682b8260ab1c60b918599864e2e5">T</a>, <a href="/web-llvm/docs/api/structs/llvm/support/endian/writer/#a16a69d4248bb11c84536099421ea833b">llvm::support::endian::Writer::write</a> and <a href="#a1c231cc18850380661428875e8c99822">llvm::xray::anonymous{FDRTraceWriter.cpp}::IndexedWriter&lt; Index &gt;::write</a>.</p>


<p>Referenced by <a href="#a1c231cc18850380661428875e8c99822">llvm::xray::anonymous{FDRTraceWriter.cpp}::IndexedWriter&lt; Index &gt;::write</a> and <a href="/web-llvm/docs/api/namespaces/llvm/xray/anonymous-fdrtracewriter-cpp-/#a53787fd7c0f79784e176e673a77a071f">llvm::xray::anonymous{FDRTraceWriter.cpp}::writeMetadata</a>.</p>

</div>
</div>

### write() {#ae45fee095a4a7fd821218b2a2e5f0de7}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<div class="doxyMemberTemplate">template &lt;class Tuple, std::enable_if_t&lt;(Index &gt;=std::tuple_size&lt; std::remove_reference_t&lt; Tuple &gt; &gt;::value), int &gt; = 0&gt;</div>
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">size_t llvm::xray::anonymous{FDRTraceWriter.cpp}::IndexedWriter&lt; Index &gt;::write (<a href="/web-llvm/docs/api/structs/llvm/support/endian/writer">support::endian::Writer</a> &amp; OS, Tuple &amp;&amp;)</td>
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



<p>Definition at line 36 of file <a href="/web-llvm/docs/api/files/lib/lib/xray/fdrtracewriter-cpp">FDRTraceWriter.cpp</a>.</p>

</div>
</div>

</div>

<hr/>

The documentation for this struct was generated from the following file:

<ul>
<li><a href="/web-llvm/docs/api/files/lib/lib/xray/fdrtracewriter-cpp">FDRTraceWriter.cpp</a></li>
</ul>

<hr/>

<p class="doxyGeneratedBy">Generated via <a href="https://github.com/xpack/doxygen2docusaurus">doxygen2docusaurus</a> by <a href="https://www.doxygen.nl">Doxygen</a> 1.15.0.</p>

</div>
