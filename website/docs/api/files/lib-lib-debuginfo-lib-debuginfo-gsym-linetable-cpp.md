---

# DO NOT EDIT!
# Automatically generated via doxygen2docusaurus by Doxygen.

slug: /api/files/lib/lib/debuginfo/lib/debuginfo/gsym/linetable-cpp
custom_edit_url: null
toc_max_heading_level: 4
keywords:
  - doxygen
  - reference
  - file

---

<div class="doxyPage">

# `LineTable.cpp` File



## Included Headers

<div class="doxyIncludesList">#include "<a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/debuginfo/include/llvm/debuginfo/gsym/linetable-h">llvm/DebugInfo/GSYM/LineTable.h</a>"
#include "<a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/debuginfo/include/llvm/debuginfo/gsym/filewriter-h">llvm/DebugInfo/GSYM/FileWriter.h</a>"
#include "<a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/support/dataextractor-h">llvm/Support/DataExtractor.h</a>"
</div>

## Classes Index

<table class="doxyMembersIndex">

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">struct</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="/web-llvm/docs/api/structs/deltainfo">DeltaInfo</a></td>
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

## Typedefs Index

<table class="doxyMembersIndex">

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">typedef</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="/web-llvm/docs/api/files/lib/lib/analysis/regionprinter-cpp/#aa37fbbce2360106772fd97ed06455d55">std::function</a>&lt; bool(<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/structs/llvm/gsym/lineentry">LineEntry</a> &amp;Row)&gt; <a href="#ae656f0970105f23db546305251a1b436">LineEntryCallback</a></td>
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

## Enumerations Index

<table class="doxyMembersIndex">

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">enum</td>
<td class="doxyMemberIndexItemName" align="left" valign="top">LineTableOpCode { <a href="#a90de7cef943238ae1b541e31b373ed68">...</a> }</td>
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

## Operators Index

<table class="doxyMembersIndex">

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">bool</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a74f9f8ea1f1865976d2b842a0f470a16">operator&lt;</a> (const DeltaInfo &amp;LHS, int64_t Delta)</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">static bool</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ad9cd4a2e1984be7b783ac9bb124fa83b">encodeSpecial</a> (int64_t MinLineDelta, int64_t MaxLineDelta, int64_t LineDelta, uint64_t AddrDelta, uint8_t &amp;SpecialOp)</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">static <a href="/web-llvm/docs/api/classes/llvm/error">llvm::Error</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a45e99fb329714d8911cb5e116eb8a3bc">parse</a> (DataExtractor &amp;Data, uint64_t BaseAddr, LineEntryCallback const &amp;Callback)</td>
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

## Typedefs

### LineEntryCallback {#ae656f0970105f23db546305251a1b436}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">typedef std::function&lt;bool(const LineEntry &amp;Row)&gt; LineEntryCallback</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 52 of file <a href="/web-llvm/docs/api/files/lib/lib/debuginfo/lib/debuginfo/gsym/linetable-cpp">LineTable.cpp</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Enumerations

### LineTableOpCode {#a90de7cef943238ae1b541e31b373ed68}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">enum LineTableOpCode </td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">


<dl class="doxyEnumList">
<dt class="doxyEnumTableTitle">Enumeration values</dt>
<dd>
<table class="doxyEnumTable">

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">EndSequence<a id="a90de7cef943238ae1b541e31b373ed68afd55184035d28c16fb83e0a80ecd57a6"></a></td>
<td class="doxyEnumItemDescription">End of the line table (= 0x00)</td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">SetFile<a id="a90de7cef943238ae1b541e31b373ed68a814ad7183f3b1f1aafd5d82aeef1e44d"></a></td>
<td class="doxyEnumItemDescription">Set LineTableRow.file_idx, don't push a row (= 0x01)</td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">AdvancePC<a id="a90de7cef943238ae1b541e31b373ed68afdf828b840cddca16f427cc3f2b72fac"></a></td>
<td class="doxyEnumItemDescription">Increment LineTableRow.address, and push a row (= 0x02)</td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">AdvanceLine<a id="a90de7cef943238ae1b541e31b373ed68ad70cf2d6845766439609f1cd17b9609c"></a></td>
<td class="doxyEnumItemDescription">Set LineTableRow.file_line, don't push a row (= 0x03)</td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">FirstSpecial<a id="a90de7cef943238ae1b541e31b373ed68a8c2683a4c8021dd82216826ec37144c5"></a></td>
<td class="doxyEnumItemDescription">All special opcodes push a row (= 0x04)</td>
</tr>

</table>
</dd>
</dl>

<p>Definition at line 16 of file <a href="/web-llvm/docs/api/files/lib/lib/debuginfo/lib/debuginfo/gsym/linetable-cpp">LineTable.cpp</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Operators

### operator&lt;() {#a74f9f8ea1f1865976d2b842a0f470a16}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool operator&lt; (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/structs/deltainfo">DeltaInfo</a> &amp; LHS, int64_t Delta)</td>
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



<p>Definition at line 30 of file <a href="/web-llvm/docs/api/files/lib/lib/debuginfo/lib/debuginfo/gsym/linetable-cpp">LineTable.cpp</a>.</p>


<p>Reference <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/x86/x86partialreduction-cpp/#a9e1483f7215664a2315c53c3558d9a8d">LHS</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Functions

### encodeSpecial() {#ad9cd4a2e1984be7b783ac9bb124fa83b}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool encodeSpecial (int64_t MinLineDelta, int64_t MaxLineDelta, int64_t LineDelta, uint64_t AddrDelta, uint8_t &amp; SpecialOp)</td>
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



<p>Definition at line 34 of file <a href="/web-llvm/docs/api/files/lib/lib/debuginfo/lib/debuginfo/gsym/linetable-cpp">LineTable.cpp</a>.</p>


<p>Reference <a href="#a90de7cef943238ae1b541e31b373ed68a8c2683a4c8021dd82216826ec37144c5">FirstSpecial</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/classes/llvm/gsym/linetable/#a41c4a2acdbcfaf2a18a61b60d42a9dc4">llvm::gsym::LineTable::encode</a>.</p>

</div>
</div>

### parse() {#a45e99fb329714d8911cb5e116eb8a3bc}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">llvm::Error parse (<a href="/web-llvm/docs/api/classes/llvm/dataextractor">DataExtractor</a> &amp; Data, uint64_t BaseAddr, <a href="#ae656f0970105f23db546305251a1b436">LineEntryCallback</a> <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> &amp; Callback)</td>
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



<p>Definition at line 54 of file <a href="/web-llvm/docs/api/files/lib/lib/debuginfo/lib/debuginfo/gsym/linetable-cpp">LineTable.cpp</a>.</p>


<p>References <a href="#a90de7cef943238ae1b541e31b373ed68ad70cf2d6845766439609f1cd17b9609c">AdvanceLine</a>, <a href="#a90de7cef943238ae1b541e31b373ed68afdf828b840cddca16f427cc3f2b72fac">AdvancePC</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a4d2fd926089a58d482fb67a362e11bad">llvm::createStringError</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#aa20539e89704d20b98b97e9c3feac934">llvm::Data</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a233737223c9a3dba810df5b91bc91d1fabbb9957d8adae962b153273c16bce571">llvm::Done</a>, <a href="#a90de7cef943238ae1b541e31b373ed68afd55184035d28c16fb83e0a80ecd57a6">EndSequence</a>, <a href="#a90de7cef943238ae1b541e31b373ed68a8c2683a4c8021dd82216826ec37144c5">FirstSpecial</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a05f5b9a11bdcc5feba62899f95dcf878a3134224cba2545bc57954d3b072aebb4">llvm::Offset</a>, <a href="#a90de7cef943238ae1b541e31b373ed68a814ad7183f3b1f1aafd5d82aeef1e44d">SetFile</a> and <a href="/web-llvm/docs/api/classes/llvm/error/#a4dfd0813c3d0e0a30439b5a3e9196b59">llvm::Error::success</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/classes/llvm/gsym/linetable/#a45c433311387761ffb00f0aea6be6675">llvm::gsym::LineTable::decode</a> and <a href="/web-llvm/docs/api/classes/llvm/gsym/linetable/#a9bca453dce01051bae3751cbb4d14fef">llvm::gsym::LineTable::lookup</a>.</p>

</div>
</div>

</div>

<hr/>

<p class="doxyGeneratedBy">Generated via <a href="https://xpack.github.io/doxygen2docusaurus">doxygen2docusaurus</a> 2.0.0 by <a href="https://www.doxygen.nl">Doxygen</a> 1.15.0.</p>

</div>
