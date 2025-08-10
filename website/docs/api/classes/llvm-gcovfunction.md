---

# DO NOT EDIT!
# Automatically generated via doxygen2docusaurus by Doxygen.

slug: /api/classes/llvm/gcovfunction
custom_edit_url: null
toc_max_heading_level: 4
keywords:
  - doxygen
  - reference
  - class

---

<div class="doxyPage">

# `GCOVFunction` Class

<p><a href="/web-llvm/docs/api/classes/llvm/gcovfunction">GCOVFunction</a> - Collects function information. <a href="#details">More...</a></p>

## Declaration

<div class="doxyDeclaration">
class llvm::GCOVFunction { ... }
</div>

## Included Headers

<div class="doxyIncludesList">#include "<a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/profiledata/gcov-h">llvm/ProfileData/GCOV.h</a>"
</div>

## Public Member Typedefs Index

<table class="doxyMembersIndex">

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">using</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a961fd4597715386f3ce5244a5fe07a73">BlockIterator</a> = <a href="/web-llvm/docs/api/structs/llvm/pointee-iterator">pointee_iterator</a>&lt; <a href="/web-llvm/docs/api/classes/llvm/smallvectorimpl">SmallVectorImpl</a>&lt; std::unique_ptr&lt; <a href="/web-llvm/docs/api/classes/llvm/gcovblock">GCOVBlock</a> &gt; &gt;::const_iterator &gt;</td>
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

## Public Constructors Index

<table class="doxyMembersIndex">

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a22131fa32c37ccbdeadb5746b9263df2">GCOVFunction</a> (GCOVFile &amp;file)</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/stringref">StringRef</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a2068e0d7a06079b029d2632a74c2bffb">getName</a> (bool demangle) const</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/stringref">StringRef</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a958ded96222c13408529a306519cfae4">getFilename</a> () const</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a11dcd83808897700bfb59a491075a617">getEntryCount</a> () const</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>getEntryCount - Get the number of times the function was called by retrieving the entry block's count. <a href="#a11dcd83808897700bfb59a491075a617">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/gcovblock">GCOVBlock</a> &amp;</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a943e410bc93266b2a958d6eaf067900c">getExitBlock</a> () const</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/iterator-range">iterator_range</a>&lt; <a href="#a961fd4597715386f3ce5244a5fe07a73">BlockIterator</a> &gt;</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ace066d2243b766c4a3fe3d4b0433f80b">blocksRange</a> () const</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a6084253c0f3954d2b8479befc2a6be61">propagateCounts</a> (const GCOVBlock &amp;v, GCOVArc *pred)</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#aa65cb033d62b0ae935401c1e96501e9f">print</a> (raw_ostream &amp;OS) const</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a287ea9a8032be9c72e6334b75c8c2d3e">dump</a> () const</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>dump - Dump <a href="/web-llvm/docs/api/classes/llvm/gcovfunction">GCOVFunction</a> content to <a href="/web-llvm/docs/api/namespaces/llvm/#a7c46c742c31be54870e2038048e6b391">dbgs()</a> for debugging purposes. <a href="#a287ea9a8032be9c72e6334b75c8c2d3e">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

</table>

## Public Member Attributes Index

<table class="doxyMembersIndex">

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/gcovfile">GCOVFile</a> &amp;</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#af98e7c3a67ac59ccffa6505a99d32e3b">file</a></td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">uint32_t</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#adb0a079a876b527ceeae3e43f22cb024">ident</a> = 0</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">uint32_t</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ac273090f7c5c7ffca085680dd553a941">linenoChecksum</a></td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">uint32_t</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a22003977b1718b0c7f51114c03b45485">cfgChecksum</a> = 0</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">uint32_t</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a9af9530cf31094834e0c2b944b49a746">startLine</a> = 0</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">uint32_t</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#aadc5eb8ab6ebb3630a7bb5f22d5523a0">startColumn</a> = 0</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">uint32_t</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a6e9fe8c1b52874a63570ff42027a485f">endLine</a> = 0</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">uint32_t</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a15a3bd454ef0bdf816806835d482661a">endColumn</a> = 0</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a348690c5f8ef52ba088da1914f5ca2ed">artificial</a> = 0</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/stringref">StringRef</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a3320dde2a5a38e0be2f7951306226ee6">Name</a></td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/smallstring">SmallString</a>&lt; 0 &gt;</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a9f15078efde7b591220ce148c349b2af">demangled</a></td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">unsigned</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#aecfa5c1da312931caf34dfdcd4f4c1b5">srcIdx</a></td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/smallvector">SmallVector</a>&lt; std::unique_ptr&lt; <a href="/web-llvm/docs/api/classes/llvm/gcovblock">GCOVBlock</a> &gt;, 0 &gt;</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a845557fee974651576fee4cff65455e8">blocks</a></td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/smallvector">SmallVector</a>&lt; std::unique_ptr&lt; <a href="/web-llvm/docs/api/structs/llvm/gcovarc">GCOVArc</a> &gt;, 0 &gt;</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ad5d1a6eeb22f95628a366e5bf514c1ff">arcs</a></td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/smallvector">SmallVector</a>&lt; std::unique_ptr&lt; <a href="/web-llvm/docs/api/structs/llvm/gcovarc">GCOVArc</a> &gt;, 0 &gt;</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a1645a32f87c01fc94d01a6566a9e6839">treeArcs</a></td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/denseset">DenseSet</a>&lt; <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/gcovblock">GCOVBlock</a> * &gt;</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a970bbd4d9b74b51c4ec85c4c9d785ded">visited</a></td>
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

<p><a href="/web-llvm/docs/api/classes/llvm/gcovfunction">GCOVFunction</a> - Collects function information.</p>

<p>Definition at line 236 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/profiledata/gcov-h">GCOV.h</a>.</p>


<div class="doxySectionDef">

## Public Member Typedefs

### BlockIterator {#a961fd4597715386f3ce5244a5fe07a73}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">using llvm::GCOVFunction::BlockIterator =  pointee_iterator&lt;
      SmallVectorImpl&lt;std::unique_ptr&lt;GCOVBlock&gt;&gt;::const_iterator&gt;</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 238 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/profiledata/gcov-h">GCOV.h</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Public Constructors

### GCOVFunction() {#a22131fa32c37ccbdeadb5746b9263df2}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">llvm::GCOVFunction::GCOVFunction (<a href="/web-llvm/docs/api/classes/llvm/gcovfile">GCOVFile</a> &amp; file)</td>
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



<p>Definition at line 241 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/profiledata/gcov-h">GCOV.h</a>.</p>


<p>Reference <a href="#af98e7c3a67ac59ccffa6505a99d32e3b">file</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Public Member Functions

### blocksRange() {#ace066d2243b766c4a3fe3d4b0433f80b}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">iterator_range&lt; BlockIterator &gt; llvm::GCOVFunction::blocksRange ()</td>
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



<p>Definition at line 248 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/profiledata/gcov-h">GCOV.h</a>.</p>


<p>References <a href="#a845557fee974651576fee4cff65455e8">blocks</a> and <a href="/web-llvm/docs/api/namespaces/llvm/#a341215803e83773a3e97860dc291f121">llvm::make_range</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/classes/llvm/gcovfile/#afdcbd7a0714f6e4c7da08854c71f1029">llvm::GCOVFile::readGCDA</a>.</p>

</div>
</div>

### dump() {#a287ea9a8032be9c72e6334b75c8c2d3e}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">LLVM_DUMP_METHOD void GCOVFunction::dump ()</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>dump - Dump <a href="/web-llvm/docs/api/classes/llvm/gcovfunction">GCOVFunction</a> content to <a href="/web-llvm/docs/api/namespaces/llvm/#a7c46c742c31be54870e2038048e6b391">dbgs()</a> for debugging purposes.</p>

<p>Declaration at line 254 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/profiledata/gcov-h">GCOV.h</a>, definition at line 433 of file <a href="/web-llvm/docs/api/files/lib/lib/profiledata/gcov-cpp">GCOV.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/namespaces/llvm/#a7c46c742c31be54870e2038048e6b391">llvm::dbgs</a>, <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/support/compiler-h/#aa863693eef567397d9c292da5bf22d34">LLVM_DUMP_METHOD</a> and <a href="#aa65cb033d62b0ae935401c1e96501e9f">print</a>.</p>

</div>
</div>

### getEntryCount() {#a11dcd83808897700bfb59a491075a617}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">uint64_t GCOVFunction::getEntryCount ()</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>getEntryCount - Get the number of times the function was called by retrieving the entry block's count.</p>

<p>Declaration at line 245 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/profiledata/gcov-h">GCOV.h</a>, definition at line 357 of file <a href="/web-llvm/docs/api/files/lib/lib/profiledata/gcov-cpp">GCOV.cpp</a>.</p>


<p>Reference <a href="#a845557fee974651576fee4cff65455e8">blocks</a>.</p>

</div>
</div>

### getExitBlock() {#a943e410bc93266b2a958d6eaf067900c}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">GCOVBlock &amp; GCOVFunction::getExitBlock ()</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Declaration at line 246 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/profiledata/gcov-h">GCOV.h</a>, definition at line 361 of file <a href="/web-llvm/docs/api/files/lib/lib/profiledata/gcov-cpp">GCOV.cpp</a>.</p>


<p>References <a href="#a845557fee974651576fee4cff65455e8">blocks</a>, <a href="#af98e7c3a67ac59ccffa6505a99d32e3b">file</a> and <a href="/web-llvm/docs/api/namespaces/llvm/gcov/#aa1bb0e8b1c685b30bf6d3247fb3feb08a607cdde36f2294fa72393d08056f261e">llvm::GCOV::V408</a>.</p>

</div>
</div>

### getFilename() {#a958ded96222c13408529a306519cfae4}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">StringRef GCOVFunction::getFilename ()</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Declaration at line 244 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/profiledata/gcov-h">GCOV.h</a>, definition at line 353 of file <a href="/web-llvm/docs/api/files/lib/lib/profiledata/gcov-cpp">GCOV.cpp</a>.</p>


<p>References <a href="#af98e7c3a67ac59ccffa6505a99d32e3b">file</a> and <a href="#aecfa5c1da312931caf34dfdcd4f4c1b5">srcIdx</a>.</p>


<p>Referenced by <a href="#aa65cb033d62b0ae935401c1e96501e9f">print</a> and <a href="/web-llvm/docs/api/classes/anonymous-gcovprofiling-cpp-/gcovfunction/#a9141ca1168edd7cd985be48a52bd218f">anonymous{GCOVProfiling.cpp}::GCOVFunction::writeOut</a>.</p>

</div>
</div>

### getName() {#a2068e0d7a06079b029d2632a74c2bffb}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">StringRef GCOVFunction::getName (bool demangle)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Declaration at line 243 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/profiledata/gcov-h">GCOV.h</a>, definition at line 335 of file <a href="/web-llvm/docs/api/files/lib/lib/profiledata/gcov-cpp">GCOV.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/namespaces/llvm/#ab996639d406a5466d5c8a1586fb4a9d8">llvm::demangle</a>, <a href="#a9f15078efde7b591220ce148c349b2af">demangled</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a7b3603860e0761afd058a6dd5f518363">llvm::itaniumDemangle</a> and <a href="#a3320dde2a5a38e0be2f7951306226ee6">Name</a>.</p>

</div>
</div>

### print() {#aa65cb033d62b0ae935401c1e96501e9f}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void GCOVFunction::print (<a href="/web-llvm/docs/api/classes/llvm/raw-ostream">raw_ostream</a> &amp; OS)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Declaration at line 253 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/profiledata/gcov-h">GCOV.h</a>, definition at line 424 of file <a href="/web-llvm/docs/api/files/lib/lib/profiledata/gcov-cpp">GCOV.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/namespaces/llvm/#a0e00fad9c34de40b1e31f3aa6f8e024cae1e4c8c9ccd9fc39c391da4bcd093fb2">llvm::Block</a>, <a href="#a845557fee974651576fee4cff65455e8">blocks</a>, <a href="#a958ded96222c13408529a306519cfae4">getFilename</a>, <a href="#adb0a079a876b527ceeae3e43f22cb024">ident</a>, <a href="#a3320dde2a5a38e0be2f7951306226ee6">Name</a> and <a href="#a9af9530cf31094834e0c2b944b49a746">startLine</a>.</p>


<p>Referenced by <a href="#a287ea9a8032be9c72e6334b75c8c2d3e">dump</a>.</p>

</div>
</div>

### propagateCounts() {#a6084253c0f3954d2b8479befc2a6be61}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void GCOVFunction::propagateCounts (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/gcovblock">GCOVBlock</a> &amp; v, <a href="/web-llvm/docs/api/structs/llvm/gcovarc">GCOVArc</a> * pred)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Declaration at line 252 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/profiledata/gcov-h">GCOV.h</a>, definition at line 372 of file <a href="/web-llvm/docs/api/files/lib/lib/profiledata/gcov-cpp">GCOV.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/classes/llvm/smallvectortemplatecommon/#acd9e771a3296c6b24146955754620557">llvm::SmallVectorTemplateCommon&lt; T, typename &gt;::back</a>, <a href="/web-llvm/docs/api/classes/llvm/smallvectortemplatecommon/#ad9a3c7bc26b130377bbafc170b5f88a2">llvm::SmallVectorTemplateCommon&lt; T, typename &gt;::empty</a>, <a href="/web-llvm/docs/api/classes/llvm/smallvectortemplatebase/#ad97688dfe9cd802e2a0691cbe620218a">llvm::SmallVectorTemplateBase&lt; T, bool &gt;::pop_back</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/hexagon/hexagongenpredicate-cpp/#a0de1bf31f56b17312cc34b911d86faa4">pred</a>, <a href="/web-llvm/docs/api/classes/llvm/smallvectortemplatebase/#af42bfbc067df27c19ee2fc859df58799">llvm::SmallVectorTemplateBase&lt; T, bool &gt;::push_back</a> and <a href="#a970bbd4d9b74b51c4ec85c4c9d785ded">visited</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/classes/llvm/gcovfile/#afdcbd7a0714f6e4c7da08854c71f1029">llvm::GCOVFile::readGCDA</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Public Member Attributes

### arcs {#ad5d1a6eeb22f95628a366e5bf514c1ff}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">SmallVector&lt;std::unique_ptr&lt;GCOVArc&gt;, 0&gt; llvm::GCOVFunction::arcs</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 269 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/profiledata/gcov-h">GCOV.h</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/classes/llvm/gcovfile/#afdcbd7a0714f6e4c7da08854c71f1029">llvm::GCOVFile::readGCDA</a> and <a href="/web-llvm/docs/api/classes/llvm/gcovfile/#ade10e8f0936debea56054236f5572fae">llvm::GCOVFile::readGCNO</a>.</p>

</div>
</div>

### artificial {#a348690c5f8ef52ba088da1914f5ca2ed}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">uint8_t llvm::GCOVFunction::artificial = 0</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 264 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/profiledata/gcov-h">GCOV.h</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/classes/llvm/gcovfile/#ade10e8f0936debea56054236f5572fae">llvm::GCOVFile::readGCNO</a>.</p>

</div>
</div>

### blocks {#a845557fee974651576fee4cff65455e8}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">SmallVector&lt;std::unique_ptr&lt;GCOVBlock&gt;, 0&gt; llvm::GCOVFunction::blocks</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 268 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/profiledata/gcov-h">GCOV.h</a>.</p>


<p>Referenced by <a href="#ace066d2243b766c4a3fe3d4b0433f80b">blocksRange</a>, <a href="#a11dcd83808897700bfb59a491075a617">getEntryCount</a>, <a href="#a943e410bc93266b2a958d6eaf067900c">getExitBlock</a>, <a href="#aa65cb033d62b0ae935401c1e96501e9f">print</a>, <a href="/web-llvm/docs/api/classes/llvm/gcovfile/#afdcbd7a0714f6e4c7da08854c71f1029">llvm::GCOVFile::readGCDA</a> and <a href="/web-llvm/docs/api/classes/llvm/gcovfile/#ade10e8f0936debea56054236f5572fae">llvm::GCOVFile::readGCNO</a>.</p>

</div>
</div>

### cfgChecksum {#a22003977b1718b0c7f51114c03b45485}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">uint32_t llvm::GCOVFunction::cfgChecksum = 0</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 259 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/profiledata/gcov-h">GCOV.h</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/classes/llvm/gcovfile/#afdcbd7a0714f6e4c7da08854c71f1029">llvm::GCOVFile::readGCDA</a> and <a href="/web-llvm/docs/api/classes/llvm/gcovfile/#ade10e8f0936debea56054236f5572fae">llvm::GCOVFile::readGCNO</a>.</p>

</div>
</div>

### demangled {#a9f15078efde7b591220ce148c349b2af}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">SmallString&lt;0&gt; llvm::GCOVFunction::demangled</td>
</tr>
</table>
</td>
<td class="doxyMemberLabelsRight">
<span class="doxyMemberLabels">
<span class="doxyMemberLabel mutable">mutable</span>
</span>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 266 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/profiledata/gcov-h">GCOV.h</a>.</p>


<p>Referenced by <a href="#a2068e0d7a06079b029d2632a74c2bffb">getName</a>.</p>

</div>
</div>

### endColumn {#a15a3bd454ef0bdf816806835d482661a}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">uint32_t llvm::GCOVFunction::endColumn = 0</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 263 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/profiledata/gcov-h">GCOV.h</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/classes/llvm/gcovfile/#ade10e8f0936debea56054236f5572fae">llvm::GCOVFile::readGCNO</a>.</p>

</div>
</div>

### endLine {#a6e9fe8c1b52874a63570ff42027a485f}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">uint32_t llvm::GCOVFunction::endLine = 0</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 262 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/profiledata/gcov-h">GCOV.h</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/classes/llvm/gcovfile/#ade10e8f0936debea56054236f5572fae">llvm::GCOVFile::readGCNO</a>.</p>

</div>
</div>

### file {#af98e7c3a67ac59ccffa6505a99d32e3b}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">GCOVFile&amp; llvm::GCOVFunction::file</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 256 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/profiledata/gcov-h">GCOV.h</a>.</p>


<p>Referenced by <a href="#a22131fa32c37ccbdeadb5746b9263df2">GCOVFunction</a>, <a href="#a943e410bc93266b2a958d6eaf067900c">getExitBlock</a> and <a href="#a958ded96222c13408529a306519cfae4">getFilename</a>.</p>

</div>
</div>

### ident {#adb0a079a876b527ceeae3e43f22cb024}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">uint32_t llvm::GCOVFunction::ident = 0</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 257 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/profiledata/gcov-h">GCOV.h</a>.</p>


<p>Referenced by <a href="#aa65cb033d62b0ae935401c1e96501e9f">print</a> and <a href="/web-llvm/docs/api/classes/llvm/gcovfile/#ade10e8f0936debea56054236f5572fae">llvm::GCOVFile::readGCNO</a>.</p>

</div>
</div>

### linenoChecksum {#ac273090f7c5c7ffca085680dd553a941}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">uint32_t llvm::GCOVFunction::linenoChecksum</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 258 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/profiledata/gcov-h">GCOV.h</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/classes/llvm/gcovfile/#afdcbd7a0714f6e4c7da08854c71f1029">llvm::GCOVFile::readGCDA</a> and <a href="/web-llvm/docs/api/classes/llvm/gcovfile/#ade10e8f0936debea56054236f5572fae">llvm::GCOVFile::readGCNO</a>.</p>

</div>
</div>

### Name {#a3320dde2a5a38e0be2f7951306226ee6}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">StringRef llvm::GCOVFunction::Name</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 265 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/profiledata/gcov-h">GCOV.h</a>.</p>


<p>Referenced by <a href="#a2068e0d7a06079b029d2632a74c2bffb">getName</a>, <a href="#aa65cb033d62b0ae935401c1e96501e9f">print</a>, <a href="/web-llvm/docs/api/classes/llvm/gcovfile/#afdcbd7a0714f6e4c7da08854c71f1029">llvm::GCOVFile::readGCDA</a> and <a href="/web-llvm/docs/api/classes/llvm/gcovfile/#ade10e8f0936debea56054236f5572fae">llvm::GCOVFile::readGCNO</a>.</p>

</div>
</div>

### srcIdx {#aecfa5c1da312931caf34dfdcd4f4c1b5}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">unsigned llvm::GCOVFunction::srcIdx</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 267 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/profiledata/gcov-h">GCOV.h</a>.</p>


<p>Referenced by <a href="#a958ded96222c13408529a306519cfae4">getFilename</a> and <a href="/web-llvm/docs/api/classes/llvm/gcovfile/#ade10e8f0936debea56054236f5572fae">llvm::GCOVFile::readGCNO</a>.</p>

</div>
</div>

### startColumn {#aadc5eb8ab6ebb3630a7bb5f22d5523a0}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">uint32_t llvm::GCOVFunction::startColumn = 0</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 261 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/profiledata/gcov-h">GCOV.h</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/classes/llvm/gcovfile/#ade10e8f0936debea56054236f5572fae">llvm::GCOVFile::readGCNO</a>.</p>

</div>
</div>

### startLine {#a9af9530cf31094834e0c2b944b49a746}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">uint32_t llvm::GCOVFunction::startLine = 0</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 260 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/profiledata/gcov-h">GCOV.h</a>.</p>


<p>Referenced by <a href="#aa65cb033d62b0ae935401c1e96501e9f">print</a> and <a href="/web-llvm/docs/api/classes/llvm/gcovfile/#ade10e8f0936debea56054236f5572fae">llvm::GCOVFile::readGCNO</a>.</p>

</div>
</div>

### treeArcs {#a1645a32f87c01fc94d01a6566a9e6839}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">SmallVector&lt;std::unique_ptr&lt;GCOVArc&gt;, 0&gt; llvm::GCOVFunction::treeArcs</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 269 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/profiledata/gcov-h">GCOV.h</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/classes/llvm/gcovfile/#afdcbd7a0714f6e4c7da08854c71f1029">llvm::GCOVFile::readGCDA</a> and <a href="/web-llvm/docs/api/classes/llvm/gcovfile/#ade10e8f0936debea56054236f5572fae">llvm::GCOVFile::readGCNO</a>.</p>

</div>
</div>

### visited {#a970bbd4d9b74b51c4ec85c4c9d785ded}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">DenseSet&lt;const GCOVBlock *&gt; llvm::GCOVFunction::visited</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 270 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/profiledata/gcov-h">GCOV.h</a>.</p>


<p>Referenced by <a href="#a6084253c0f3954d2b8479befc2a6be61">propagateCounts</a>.</p>

</div>
</div>

</div>

<hr/>

The documentation for this class was generated from the following files:

<ul>
<li><a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/profiledata/gcov-h">GCOV.h</a></li>
<li><a href="/web-llvm/docs/api/files/lib/lib/profiledata/gcov-cpp">GCOV.cpp</a></li>
</ul>

<hr/>

<p class="doxyGeneratedBy">Generated via <a href="https://xpack.github.io/doxygen2docusaurus">doxygen2docusaurus</a> 2.0.0 by <a href="https://www.doxygen.nl">Doxygen</a> 1.15.0.</p>

</div>
