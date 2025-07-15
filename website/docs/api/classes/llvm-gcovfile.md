---

# DO NOT EDIT!
# Automatically generated via doxygen2docusaurus by Doxygen.

slug: /api/classes/llvm/gcovfile
custom_edit_url: null
toc_max_heading_level: 4
keywords:
  - doxygen
  - reference
  - class

---

<div class="doxyPage">

# The `GCOVFile` Class Reference

<p><a href="/web-llvm/docs/api/classes/llvm/gcovfile">GCOVFile</a> - Collects coverage information for one pair of coverage file (.gcno and .gcda). <a href="#details">More...</a></p>

## Declaration

<div class="doxyDeclaration">
class llvm::GCOVFile { ... }
</div>

## Included Headers

<div class="doxyIncludesList">#include "<a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/profiledata/gcov-h">llvm/ProfileData/GCOV.h</a>"
</div>

## Public Member Typedefs Index

<table class="doxyMembersIndex">

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">using</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#afc2cc88bb288063cf890687024807c69">iterator</a> = <a href="/web-llvm/docs/api/structs/llvm/pointee-iterator">pointee_iterator</a>&lt; <a href="/web-llvm/docs/api/classes/llvm/smallvectorimpl">SmallVectorImpl</a>&lt; std::unique_ptr&lt; <a href="/web-llvm/docs/api/classes/llvm/gcovfunction">GCOVFunction</a> &gt; &gt;::const_iterator &gt;</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a6df2a7505d04bdb3f21d1a9531ffbd74">GCOVFile</a> ()=default</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">bool</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ade10e8f0936debea56054236f5572fae">readGCNO</a> (GCOVBuffer &amp;Buffer)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>readGCNO - Read GCNO buffer. <a href="#ade10e8f0936debea56054236f5572fae">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">bool</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#afdcbd7a0714f6e4c7da08854c71f1029">readGCDA</a> (GCOVBuffer &amp;Buffer)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>readGCDA - Read GCDA buffer. <a href="#afdcbd7a0714f6e4c7da08854c71f1029">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/namespaces/llvm/gcov/#aa1bb0e8b1c685b30bf6d3247fb3feb08">GCOV::GCOVVersion</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a5bcd5cbba4c86d2c01e26080c52d1ddf">getVersion</a> () const</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a158c7d7834dd7a1148ebbabf1df42faa">print</a> (raw_ostream &amp;OS) const</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a89e385955903f2df447919378b7144ea">dump</a> () const</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>dump - Dump <a href="/web-llvm/docs/api/classes/llvm/gcovfile">GCOVFile</a> content to <a href="/web-llvm/docs/api/namespaces/llvm/#a7c46c742c31be54870e2038048e6b391">dbgs()</a> for debugging purposes. <a href="#a89e385955903f2df447919378b7144ea">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="#afc2cc88bb288063cf890687024807c69">iterator</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a198622f9f7333a231a1917be596c81bb">begin</a> () const</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="#afc2cc88bb288063cf890687024807c69">iterator</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a0eb4e6c622f425f2c22374470564fbdc">end</a> () const</td>
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

## Private Member Functions Index

<table class="doxyMembersIndex">

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">unsigned</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a5d3b1fec5cc4c5d10944122b0964ac96">addNormalizedPathToMap</a> (StringRef filename)</td>
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

## Public Member Attributes Index

<table class="doxyMembersIndex">

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">std::vector&lt; std::string &gt;</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a5a30c94383512bb7e824d0a02f049faa">filenames</a></td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/stringmap">StringMap</a>&lt; unsigned &gt;</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ac58befc0f881631f78014c59b1c47bd6">filenameToIdx</a></td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">bool</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#abfb69904761d6eccd03390b54c93b7b4">GCNOInitialized</a> = false</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/namespaces/llvm/gcov/#aa1bb0e8b1c685b30bf6d3247fb3feb08">GCOV::GCOVVersion</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a28b17feed089cad8ddb8582b2c74c731">version</a> {}</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a08d1af4544b8cda7d98ef6830ebbb1f3">checksum</a> = 0</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ab3d4cd8550770c08ffc6c06cc1895e52">cwd</a></td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/smallvector">SmallVector</a>&lt; std::unique_ptr&lt; <a href="/web-llvm/docs/api/classes/llvm/gcovfunction">GCOVFunction</a> &gt;, 16 &gt;</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a07d21623b86a2fa88bb51313f214709a">functions</a></td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">std::map&lt; uint32_t, <a href="/web-llvm/docs/api/classes/llvm/gcovfunction">GCOVFunction</a> * &gt;</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a9335b69a4e2e5eada84e28ba4fe6e52c">identToFunction</a></td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a1c183a0d869d6971add53c65c66a1e04">runCount</a> = 0</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a1b35807dda350d972ae9b6bf1a8e3d07">programCount</a> = 0</td>
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

<p><a href="/web-llvm/docs/api/classes/llvm/gcovfile">GCOVFile</a> - Collects coverage information for one pair of coverage file (.gcno and .gcda).</p>

<p>Definition at line 191 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/profiledata/gcov-h">GCOV.h</a>.</p>


<div class="doxySectionDef">

## Public Member Typedefs

### iterator {#afc2cc88bb288063cf890687024807c69}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">using llvm::GCOVFile::iterator =  pointee_iterator&lt;
      SmallVectorImpl&lt;std::unique_ptr&lt;GCOVFunction&gt;&gt;::const_iterator&gt;</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 214 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/profiledata/gcov-h">GCOV.h</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Public Constructors

### GCOVFile() {#a6df2a7505d04bdb3f21d1a9531ffbd74}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">llvm::GCOVFile::GCOVFile ()</td>
</tr>
</table>
</td>
<td class="doxyMemberLabelsRight">
<span class="doxyMemberLabels">
<span class="doxyMemberLabel default">default</span>
</span>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 193 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/profiledata/gcov-h">GCOV.h</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Public Member Functions

### begin() {#a198622f9f7333a231a1917be596c81bb}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">iterator llvm::GCOVFile::begin ()</td>
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



<p>Definition at line 216 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/profiledata/gcov-h">GCOV.h</a>.</p>


<p>Reference <a href="#a07d21623b86a2fa88bb51313f214709a">functions</a>.</p>

</div>
</div>

### dump() {#a89e385955903f2df447919378b7144ea}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">LLVM_DUMP_METHOD void GCOVFile::dump ()</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>dump - Dump <a href="/web-llvm/docs/api/classes/llvm/gcovfile">GCOVFile</a> content to <a href="/web-llvm/docs/api/namespaces/llvm/#a7c46c742c31be54870e2038048e6b391">dbgs()</a> for debugging purposes.</p>

<p>Declaration at line 199 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/profiledata/gcov-h">GCOV.h</a>, definition at line 314 of file <a href="/web-llvm/docs/api/files/lib/lib/profiledata/gcov-cpp">GCOV.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/namespaces/llvm/#a7c46c742c31be54870e2038048e6b391">llvm::dbgs</a>, <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/support/compiler-h/#aa863693eef567397d9c292da5bf22d34">LLVM_DUMP_METHOD</a> and <a href="#a158c7d7834dd7a1148ebbabf1df42faa">print</a>.</p>

</div>
</div>

### end() {#a0eb4e6c622f425f2c22374470564fbdc}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">iterator llvm::GCOVFile::end ()</td>
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



<p>Definition at line 217 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/profiledata/gcov-h">GCOV.h</a>.</p>


<p>Reference <a href="#a07d21623b86a2fa88bb51313f214709a">functions</a>.</p>

</div>
</div>

### getVersion() {#a5bcd5cbba4c86d2c01e26080c52d1ddf}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">GCOV::GCOVVersion llvm::GCOVFile::getVersion ()</td>
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



<p>Definition at line 197 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/profiledata/gcov-h">GCOV.h</a>.</p>


<p>Reference <a href="#a28b17feed089cad8ddb8582b2c74c731">version</a>.</p>

</div>
</div>

### print() {#a158c7d7834dd7a1148ebbabf1df42faa}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void GCOVFile::print (<a href="/web-llvm/docs/api/classes/llvm/raw-ostream">raw_ostream</a> &amp; OS)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Declaration at line 198 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/profiledata/gcov-h">GCOV.h</a>, definition at line 307 of file <a href="/web-llvm/docs/api/files/lib/lib/profiledata/gcov-cpp">GCOV.cpp</a>.</p>


<p>Referenced by <a href="#a89e385955903f2df447919378b7144ea">dump</a>.</p>

</div>
</div>

### readGCDA() {#afdcbd7a0714f6e4c7da08854c71f1029}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool GCOVFile::readGCDA (<a href="/web-llvm/docs/api/classes/llvm/gcovbuffer">GCOVBuffer</a> &amp; buf)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>readGCDA - Read GCDA buffer.</p>


<p>It is required that <a href="#afdcbd7a0714f6e4c7da08854c71f1029">readGCDA()</a> can only be called after <a href="#ade10e8f0936debea56054236f5572fae">readGCNO()</a>.</p>


<p>Declaration at line 196 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/profiledata/gcov-h">GCOV.h</a>, definition at line 210 of file <a href="/web-llvm/docs/api/files/lib/lib/profiledata/gcov-cpp">GCOV.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/classes/llvm/gcovblock/#a764eb334061e2095759e64778956acfa">llvm::GCOVBlock::addSrcEdge</a>, <a href="/web-llvm/docs/api/classes/llvm/gcovfunction/#ad5d1a6eeb22f95628a366e5bf514c1ff">llvm::GCOVFunction::arcs</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/silowercontrolflow-cpp/#a4868c5d81c5ccc98c47aeab6244346a0">assert</a>, <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/utils/unifyloopexits-cpp/#a4741a07a0e5675f89cfed122008e0a76">block</a>, <a href="/web-llvm/docs/api/classes/llvm/gcovfunction/#a845557fee974651576fee4cff65455e8">llvm::GCOVFunction::blocks</a>, <a href="/web-llvm/docs/api/classes/llvm/gcovfunction/#ace066d2243b766c4a3fe3d4b0433f80b">llvm::GCOVFunction::blocksRange</a>, <a href="/web-llvm/docs/api/classes/llvm/gcovfunction/#a22003977b1718b0c7f51114c03b45485">llvm::GCOVFunction::cfgChecksum</a>, <a href="#a08d1af4544b8cda7d98ef6830ebbb1f3">checksum</a>, <a href="/web-llvm/docs/api/classes/llvm/gcovbuffer/#a1533ae57f14fba1a9f835ea9f7d521d2">llvm::GCOVBuffer::cursor</a>, <a href="/web-llvm/docs/api/classes/llvm/gcovbuffer/#aa7bac54592a4de07ee31603aa6af6b03">llvm::GCOVBuffer::de</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a9a7b5c68c90f85baaedaa854cc5002cc">llvm::errs</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a939bc2108d47080767f0c06ba56caec7">llvm::format</a>, <a href="#abfb69904761d6eccd03390b54c93b7b4">GCNOInitialized</a>, <a href="/web-llvm/docs/api/files/lib/lib/profiledata/gcov-cpp/#ae767aa2082abe78425597037db02d45daa7a0ea69510c8b50567959a1e8664b06">GCOV_ARC_ON_TREE</a>, <a href="/web-llvm/docs/api/files/lib/lib/profiledata/gcov-cpp/#ae767aa2082abe78425597037db02d45da2f050f6fb1b108e9b6f9d28818998314">GCOV_TAG_COUNTER_ARCS</a>, <a href="/web-llvm/docs/api/files/lib/lib/profiledata/gcov-cpp/#ae767aa2082abe78425597037db02d45dac178d86a1ec0f8b12bc6988fef315383">GCOV_TAG_FUNCTION</a>, <a href="/web-llvm/docs/api/files/lib/lib/profiledata/gcov-cpp/#ae767aa2082abe78425597037db02d45da651b9f37c0f0d53e86dd9c60cb9b71c8">GCOV_TAG_OBJECT_SUMMARY</a>, <a href="/web-llvm/docs/api/files/lib/lib/profiledata/gcov-cpp/#ae767aa2082abe78425597037db02d45da37c7c75adf7e345cbdcabd63eafd63d9">GCOV_TAG_PROGRAM_SUMMARY</a>, <a href="/web-llvm/docs/api/classes/llvm/gcovbuffer/#ab936bbd10280d7a6c58bf9595f61dbc3">llvm::GCOVBuffer::getWord</a>, <a href="#a9335b69a4e2e5eada84e28ba4fe6e52c">identToFunction</a>, <a href="/web-llvm/docs/api/classes/llvm/gcovfunction/#ac273090f7c5c7ffca085680dd553a941">llvm::GCOVFunction::linenoChecksum</a>, <a href="/web-llvm/docs/api/classes/llvm/gcovfunction/#a3320dde2a5a38e0be2f7951306226ee6">llvm::GCOVFunction::Name</a>, <a href="#a1b35807dda350d972ae9b6bf1a8e3d07">programCount</a>, <a href="/web-llvm/docs/api/classes/llvm/gcovfunction/#a6084253c0f3954d2b8479befc2a6be61">llvm::GCOVFunction::propagateCounts</a>, <a href="/web-llvm/docs/api/classes/llvm/gcovbuffer/#afb37a1905e7f29be59a6d5406da52a32">llvm::GCOVBuffer::readGCDAFormat</a>, <a href="/web-llvm/docs/api/classes/llvm/gcovbuffer/#a6deeee5c731229c55b313c6452c3b8a2">llvm::GCOVBuffer::readGCOVVersion</a>, <a href="/web-llvm/docs/api/classes/llvm/gcovbuffer/#a09c24305d1aa0d278822f0ae9693e600">llvm::GCOVBuffer::readInt</a>, <a href="/web-llvm/docs/api/classes/llvm/gcovbuffer/#a20182b16fc75ceb2edabd413f5e5247a">llvm::GCOVBuffer::readInt64</a>, <a href="#a1c183a0d869d6971add53c65c66a1e04">runCount</a>, <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/scalar/licm-cpp/#a52b8b307321627e612e77041260ece84">sink</a>, <a href="/web-llvm/docs/api/classes/llvm/dataextractor/#aa4c4043f99a1a5b283741ef4c7cf2464">llvm::DataExtractor::skip</a>, <a href="/web-llvm/docs/api/classes/llvm/dataextractor/cursor/#a22c134bb6de5493faf9c7076ef4dfcac">llvm::DataExtractor::Cursor::tell</a>, <a href="/web-llvm/docs/api/classes/llvm/gcovfunction/#a1645a32f87c01fc94d01a6566a9e6839">llvm::GCOVFunction::treeArcs</a>, <a href="/web-llvm/docs/api/namespaces/llvm/gcov/#aa1bb0e8b1c685b30bf6d3247fb3feb08ab1e658d09f62b1e53e0cb99a37df31e3">llvm::GCOV::V1200</a>, <a href="/web-llvm/docs/api/namespaces/llvm/gcov/#aa1bb0e8b1c685b30bf6d3247fb3feb08a28fc20af08dacec19f1191703628427b">llvm::GCOV::V407</a>, <a href="/web-llvm/docs/api/namespaces/llvm/gcov/#aa1bb0e8b1c685b30bf6d3247fb3feb08a607cdde36f2294fa72393d08056f261e">llvm::GCOV::V408</a> and <a href="#a28b17feed089cad8ddb8582b2c74c731">version</a>.</p>

</div>
</div>

### readGCNO() {#ade10e8f0936debea56054236f5572fae}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool GCOVFile::readGCNO (<a href="/web-llvm/docs/api/classes/llvm/gcovbuffer">GCOVBuffer</a> &amp; Buffer)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>readGCNO - Read GCNO buffer.</p>

<p>Declaration at line 195 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/profiledata/gcov-h">GCOV.h</a>, definition at line 102 of file <a href="/web-llvm/docs/api/files/lib/lib/profiledata/gcov-cpp">GCOV.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/classes/llvm/gcovblock/#a5960e44736b1ab1fc8bbc40b14da4b25">llvm::GCOVBlock::addDstEdge</a>, <a href="/web-llvm/docs/api/classes/llvm/gcovblock/#a764eb334061e2095759e64778956acfa">llvm::GCOVBlock::addSrcEdge</a>, <a href="/web-llvm/docs/api/classes/llvm/gcovfunction/#ad5d1a6eeb22f95628a366e5bf514c1ff">llvm::GCOVFunction::arcs</a>, <a href="/web-llvm/docs/api/classes/llvm/gcovfunction/#a348690c5f8ef52ba088da1914f5ca2ed">llvm::GCOVFunction::artificial</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a0e00fad9c34de40b1e31f3aa6f8e024cae1e4c8c9ccd9fc39c391da4bcd093fb2">llvm::Block</a>, <a href="/web-llvm/docs/api/classes/llvm/gcovfunction/#a845557fee974651576fee4cff65455e8">llvm::GCOVFunction::blocks</a>, <a href="/web-llvm/docs/api/classes/llvm/gcovfunction/#a22003977b1718b0c7f51114c03b45485">llvm::GCOVFunction::cfgChecksum</a>, <a href="#a08d1af4544b8cda7d98ef6830ebbb1f3">checksum</a>, <a href="/web-llvm/docs/api/classes/llvm/gcovbuffer/#a1533ae57f14fba1a9f835ea9f7d521d2">llvm::GCOVBuffer::cursor</a>, <a href="#ab3d4cd8550770c08ffc6c06cc1895e52">cwd</a>, <a href="/web-llvm/docs/api/classes/llvm/gcovbuffer/#aa7bac54592a4de07ee31603aa6af6b03">llvm::GCOVBuffer::de</a>, <a href="/web-llvm/docs/api/classes/llvm/stringref/#a2dc80c585ad5882da8cae7b5968f7e74">llvm::StringRef::empty</a>, <a href="/web-llvm/docs/api/classes/llvm/gcovfunction/#a15a3bd454ef0bdf816806835d482661a">llvm::GCOVFunction::endColumn</a>, <a href="/web-llvm/docs/api/classes/llvm/gcovfunction/#a6e9fe8c1b52874a63570ff42027a485f">llvm::GCOVFunction::endLine</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a9a7b5c68c90f85baaedaa854cc5002cc">llvm::errs</a>, <a href="#a07d21623b86a2fa88bb51313f214709a">functions</a>, <a href="#abfb69904761d6eccd03390b54c93b7b4">GCNOInitialized</a>, <a href="/web-llvm/docs/api/files/lib/lib/profiledata/gcov-cpp/#ae767aa2082abe78425597037db02d45dabbbde587f0008e3ec00bbb36188dc3ee">GCOV_TAG_ARCS</a>, <a href="/web-llvm/docs/api/files/lib/lib/profiledata/gcov-cpp/#ae767aa2082abe78425597037db02d45daf15ae30d047358de4cc540bc97d2dd0d">GCOV_TAG_BLOCKS</a>, <a href="/web-llvm/docs/api/files/lib/lib/profiledata/gcov-cpp/#ae767aa2082abe78425597037db02d45dac178d86a1ec0f8b12bc6988fef315383">GCOV_TAG_FUNCTION</a>, <a href="/web-llvm/docs/api/files/lib/lib/profiledata/gcov-cpp/#ae767aa2082abe78425597037db02d45da0764429352799f822917e8251a2cf301">GCOV_TAG_LINES</a>, <a href="/web-llvm/docs/api/classes/llvm/gcovbuffer/#ab936bbd10280d7a6c58bf9595f61dbc3">llvm::GCOVBuffer::getWord</a>, <a href="/web-llvm/docs/api/classes/llvm/gcovfunction/#adb0a079a876b527ceeae3e43f22cb024">llvm::GCOVFunction::ident</a>, <a href="#a9335b69a4e2e5eada84e28ba4fe6e52c">identToFunction</a>, <a href="/web-llvm/docs/api/classes/llvm/gcovfunction/#ac273090f7c5c7ffca085680dd553a941">llvm::GCOVFunction::linenoChecksum</a>, <a href="/web-llvm/docs/api/classes/llvm/gcovfunction/#a3320dde2a5a38e0be2f7951306226ee6">llvm::GCOVFunction::Name</a>, <a href="/web-llvm/docs/api/classes/llvm/gcovbuffer/#ad1db2af6d2bd3952490d0ecc76aab3b1">llvm::GCOVBuffer::readGCNOFormat</a>, <a href="/web-llvm/docs/api/classes/llvm/gcovbuffer/#a6deeee5c731229c55b313c6452c3b8a2">llvm::GCOVBuffer::readGCOVVersion</a>, <a href="/web-llvm/docs/api/classes/llvm/gcovbuffer/#a09c24305d1aa0d278822f0ae9693e600">llvm::GCOVBuffer::readInt</a>, <a href="/web-llvm/docs/api/classes/llvm/gcovbuffer/#a79ab176059f9da274f454d5b4c10a7c3">llvm::GCOVBuffer::readString</a>, <a href="/web-llvm/docs/api/classes/llvm/dataextractor/#aa4c4043f99a1a5b283741ef4c7cf2464">llvm::DataExtractor::skip</a>, <a href="/web-llvm/docs/api/classes/llvm/gcovfunction/#aecfa5c1da312931caf34dfdcd4f4c1b5">llvm::GCOVFunction::srcIdx</a>, <a href="/web-llvm/docs/api/classes/llvm/gcovfunction/#aadc5eb8ab6ebb3630a7bb5f22d5523a0">llvm::GCOVFunction::startColumn</a>, <a href="/web-llvm/docs/api/classes/llvm/gcovfunction/#a9af9530cf31094834e0c2b944b49a746">llvm::GCOVFunction::startLine</a>, <a href="/web-llvm/docs/api/classes/llvm/dataextractor/cursor/#a22c134bb6de5493faf9c7076ef4dfcac">llvm::DataExtractor::Cursor::tell</a>, <a href="/web-llvm/docs/api/classes/llvm/gcovfunction/#a1645a32f87c01fc94d01a6566a9e6839">llvm::GCOVFunction::treeArcs</a>, <a href="/web-llvm/docs/api/namespaces/llvm/gcov/#aa1bb0e8b1c685b30bf6d3247fb3feb08ab1e658d09f62b1e53e0cb99a37df31e3">llvm::GCOV::V1200</a>, <a href="/web-llvm/docs/api/namespaces/llvm/gcov/#aa1bb0e8b1c685b30bf6d3247fb3feb08a28fc20af08dacec19f1191703628427b">llvm::GCOV::V407</a>, <a href="/web-llvm/docs/api/namespaces/llvm/gcov/#aa1bb0e8b1c685b30bf6d3247fb3feb08a44a2004dc53121e992331b77372bba6d">llvm::GCOV::V800</a>, <a href="/web-llvm/docs/api/namespaces/llvm/gcov/#aa1bb0e8b1c685b30bf6d3247fb3feb08a6fde43e4bd261973caa55253c97501ba">llvm::GCOV::V900</a> and <a href="#a28b17feed089cad8ddb8582b2c74c731">version</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Private Member Functions

### addNormalizedPathToMap() {#a5d3b1fec5cc4c5d10944122b0964ac96}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">unsigned GCOVFile::addNormalizedPathToMap (<a href="/web-llvm/docs/api/classes/llvm/stringref">StringRef</a> filename)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Declaration at line 220 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/profiledata/gcov-h">GCOV.h</a>, definition at line 317 of file <a href="/web-llvm/docs/api/files/lib/lib/profiledata/gcov-cpp">GCOV.cpp</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Public Member Attributes

### checksum {#a08d1af4544b8cda7d98ef6830ebbb1f3}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">uint32_t llvm::GCOVFile::checksum = 0</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 207 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/profiledata/gcov-h">GCOV.h</a>.</p>


<p>Referenced by <a href="#afdcbd7a0714f6e4c7da08854c71f1029">readGCDA</a> and <a href="#ade10e8f0936debea56054236f5572fae">readGCNO</a>.</p>

</div>
</div>

### cwd {#ab3d4cd8550770c08ffc6c06cc1895e52}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">StringRef llvm::GCOVFile::cwd</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 208 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/profiledata/gcov-h">GCOV.h</a>.</p>


<p>Referenced by <a href="#ade10e8f0936debea56054236f5572fae">readGCNO</a>.</p>

</div>
</div>

### filenames {#a5a30c94383512bb7e824d0a02f049faa}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">std::vector&lt;std::string&gt; llvm::GCOVFile::filenames</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 201 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/profiledata/gcov-h">GCOV.h</a>.</p>

</div>
</div>

### filenameToIdx {#ac58befc0f881631f78014c59b1c47bd6}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">StringMap&lt;unsigned&gt; llvm::GCOVFile::filenameToIdx</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 202 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/profiledata/gcov-h">GCOV.h</a>.</p>

</div>
</div>

### functions {#a07d21623b86a2fa88bb51313f214709a}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">SmallVector&lt;std::unique_ptr&lt;GCOVFunction&gt;, 16&gt; llvm::GCOVFile::functions</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 209 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/profiledata/gcov-h">GCOV.h</a>.</p>


<p>Referenced by <a href="#a198622f9f7333a231a1917be596c81bb">begin</a>, <a href="#a0eb4e6c622f425f2c22374470564fbdc">end</a> and <a href="#ade10e8f0936debea56054236f5572fae">readGCNO</a>.</p>

</div>
</div>

### GCNOInitialized {#abfb69904761d6eccd03390b54c93b7b4}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool llvm::GCOVFile::GCNOInitialized = false</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 205 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/profiledata/gcov-h">GCOV.h</a>.</p>


<p>Referenced by <a href="#afdcbd7a0714f6e4c7da08854c71f1029">readGCDA</a> and <a href="#ade10e8f0936debea56054236f5572fae">readGCNO</a>.</p>

</div>
</div>

### identToFunction {#a9335b69a4e2e5eada84e28ba4fe6e52c}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">std::map&lt;uint32_t, GCOVFunction *&gt; llvm::GCOVFile::identToFunction</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 210 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/profiledata/gcov-h">GCOV.h</a>.</p>


<p>Referenced by <a href="#afdcbd7a0714f6e4c7da08854c71f1029">readGCDA</a> and <a href="#ade10e8f0936debea56054236f5572fae">readGCNO</a>.</p>

</div>
</div>

### programCount {#a1b35807dda350d972ae9b6bf1a8e3d07}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">uint32_t llvm::GCOVFile::programCount = 0</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 212 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/profiledata/gcov-h">GCOV.h</a>.</p>


<p>Referenced by <a href="#afdcbd7a0714f6e4c7da08854c71f1029">readGCDA</a>.</p>

</div>
</div>

### runCount {#a1c183a0d869d6971add53c65c66a1e04}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">uint32_t llvm::GCOVFile::runCount = 0</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 211 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/profiledata/gcov-h">GCOV.h</a>.</p>


<p>Referenced by <a href="#afdcbd7a0714f6e4c7da08854c71f1029">readGCDA</a>.</p>

</div>
</div>

### version {#a28b17feed089cad8ddb8582b2c74c731}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">GCOV::GCOVVersion llvm::GCOVFile::version {}</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 206 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/profiledata/gcov-h">GCOV.h</a>.</p>


<p>Referenced by <a href="#a5bcd5cbba4c86d2c01e26080c52d1ddf">getVersion</a>, <a href="#afdcbd7a0714f6e4c7da08854c71f1029">readGCDA</a> and <a href="#ade10e8f0936debea56054236f5572fae">readGCNO</a>.</p>

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

<p class="doxyGeneratedBy">Generated via <a href="https://github.com/xpack/doxygen2docusaurus">doxygen2docusaurus</a> by <a href="https://www.doxygen.nl">Doxygen</a> 1.14.0.</p>

</div>
