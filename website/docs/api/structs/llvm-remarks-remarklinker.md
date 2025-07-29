---

# DO NOT EDIT!
# Automatically generated via doxygen2docusaurus by Doxygen.

slug: /api/structs/llvm/remarks/remarklinker
custom_edit_url: null
toc_max_heading_level: 4
keywords:
  - doxygen
  - reference
  - struct

---

<div class="doxyPage">

# `RemarkLinker` Struct



## Declaration

<div class="doxyDeclaration">
struct llvm::remarks::RemarkLinker { ... }
</div>

## Included Headers

<div class="doxyIncludesList">#include "<a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/remarks/remarklinker-h">llvm/Remarks/RemarkLinker.h</a>"
</div>

## Public Member Typedefs Index

<table class="doxyMembersIndex">

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">using</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a51509ff44e1e04487662ede678e76533">iterator</a> = <a href="/web-llvm/docs/api/structs/llvm/pointee-iterator">pointee_iterator</a>&lt; decltype(Remarks)::const_iterator &gt;</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Return a collection of the linked unique remarks to iterate on. <a href="#a51509ff44e1e04487662ede678e76533">More...</a></p>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a2c2acd23f65c858448855008917e63c3">setExternalFilePrependPath</a> (StringRef PrependPath)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Set a path to prepend to the external file path. <a href="#a2c2acd23f65c858448855008917e63c3">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">void</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a8d717eef5f50f721c590bc64167551e1">setKeepAllRemarks</a> (bool B)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Set KeepAllRemarks to <span class="doxyComputerOutput">B</span>. <a href="#a8d717eef5f50f721c590bc64167551e1">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/error">Error</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ac548aeb7853ce7d7cd2a3b33fb761d1b">link</a> (StringRef Buffer, std::optional&lt; Format &gt; RemarkFormat=std::nullopt)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Link the remarks found in <span class="doxyComputerOutput">Buffer</span>. <a href="#ac548aeb7853ce7d7cd2a3b33fb761d1b">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/error">Error</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a2f0b07de873627d24a364adbc61b0da3">link</a> (const object::ObjectFile &amp;Obj, std::optional&lt; Format &gt; RemarkFormat=std::nullopt)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Link the remarks found in <span class="doxyComputerOutput">Obj</span> by looking for the right section and calling the method above. <a href="#a2f0b07de873627d24a364adbc61b0da3">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/error">Error</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a520480e348343b25dce916ceca76dcd5">serialize</a> (raw_ostream &amp;OS, Format RemarksFormat) const</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Serialize the linked remarks to the stream <span class="doxyComputerOutput">OS</span>, using the format <span class="doxyComputerOutput">RemarkFormat</span>. <a href="#a520480e348343b25dce916ceca76dcd5">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">bool</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a5dcab292efb44b438d13165d728289c3">empty</a> () const</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p><a href="/web-llvm/docs/api/namespaces/llvm/check">Check</a> whether there are any remarks linked. <a href="#a5dcab292efb44b438d13165d728289c3">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/iterator-range">iterator_range</a>&lt; <a href="#a51509ff44e1e04487662ede678e76533">iterator</a> &gt;</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#aed4941ce0de71fb529dad68a145605e1">remarks</a> () const</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/structs/llvm/remarks/remark">Remark</a> &amp;</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ab9e8b05322c3596f40a9077cae508ac9">keep</a> (std::unique_ptr&lt; Remark &gt; Remark)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Keep this remark. If it's already in the set, discard it. <a href="#ab9e8b05322c3596f40a9077cae508ac9">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">bool</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a689584b7d83c06c54030883084041679">shouldKeepRemark</a> (const Remark &amp;R)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Returns true if <span class="doxyComputerOutput">R</span> should be kept. <a href="#a689584b7d83c06c54030883084041679">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

</table>

## Private Member Attributes Index

<table class="doxyMembersIndex">

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/structs/llvm/remarks/stringtable">StringTable</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#af1d42a233044ca367f9fc9fb2af1df3d">StrTab</a></td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>The main string table for the remarks. <a href="#af1d42a233044ca367f9fc9fb2af1df3d">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">std::set&lt; std::unique_ptr&lt; <a href="/web-llvm/docs/api/structs/llvm/remarks/remark">Remark</a> &gt;, RemarkPtrCompare &gt;</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a44626e555ad9e79a10df1d4b573e2f17">Remarks</a></td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>A set holding unique remarks. <a href="#a44626e555ad9e79a10df1d4b573e2f17">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">std::optional&lt; std::string &gt;</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a0f0be94f33572fc6578d3b1b142b1ac4">PrependPath</a></td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>A path to append before the external file path found in remark metadata. <a href="#a0f0be94f33572fc6578d3b1b142b1ac4">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">bool</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a404034ad5a6fe59ed2cae373244b75a0">KeepAllRemarks</a> = <a href="/web-llvm/docs/api/files/lib/lib/analysis/basicaliasanalysis-cpp/#af6d5cafbdfc5313e65d990120021a3ec">true</a></td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>If true, keep all remarks, otherwise only keep remarks with valid debug locations. <a href="#a404034ad5a6fe59ed2cae373244b75a0">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

</table>


<p>Definition at line 32 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/remarks/remarklinker-h">RemarkLinker.h</a>.</p>


<div class="doxySectionDef">

## Public Member Typedefs

### iterator {#a51509ff44e1e04487662ede678e76533}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">using llvm::remarks::RemarkLinker::iterator =  pointee_iterator&lt;decltype(Remarks)::const_iterator&gt;</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Return a collection of the linked unique remarks to iterate on.</p>


<p>Ex: for (const <a href="/web-llvm/docs/api/structs/llvm/remarks/remark">Remark</a> &amp;R : RL.remarks() { [...] }</p>


<p>Definition at line 102 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/remarks/remarklinker-h">RemarkLinker.h</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Public Member Functions

### empty() {#a5dcab292efb44b438d13165d728289c3}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool llvm::remarks::RemarkLinker::empty ()</td>
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

<p><a href="/web-llvm/docs/api/namespaces/llvm/check">Check</a> whether there are any remarks linked.</p>

<p>Definition at line 97 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/remarks/remarklinker-h">RemarkLinker.h</a>.</p>

</div>
</div>

### link() {#ac548aeb7853ce7d7cd2a3b33fb761d1b}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">Error RemarkLinker::link (<a href="/web-llvm/docs/api/classes/llvm/stringref">StringRef</a> Buffer, std::optional&lt; <a href="/web-llvm/docs/api/namespaces/llvm/remarks/#a6e038f443b9029221c590524f08be0be">Format</a> &gt; RemarkFormat=std::nullopt)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Link the remarks found in <span class="doxyComputerOutput">Buffer</span>.</p>


<p>If <span class="doxyComputerOutput">RemarkFormat</span> is not provided, try to deduce it from the metadata in <span class="doxyComputerOutput">Buffer</span>. <span class="doxyComputerOutput">Buffer</span> can be either a standalone remark container or just metadata. This takes care of uniquing and merging the remarks.</p>


<p>Declaration at line 82 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/remarks/remarklinker-h">RemarkLinker.h</a>, definition at line 69 of file <a href="/web-llvm/docs/api/files/lib/lib/remarks/remarklinker-cpp">RemarkLinker.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/silowercontrolflow-cpp/#a4868c5d81c5ccc98c47aeab6244346a0">assert</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#aee0e70be66536b9ef7b65ae2e5a45959">llvm::consumeError</a>, <a href="/web-llvm/docs/api/namespaces/llvm/remarks/#a9b0d185878d538e933f92e5827653169">llvm::remarks::createRemarkParserFromMeta</a>, <a href="/web-llvm/docs/api/namespaces/llvm/remarks/#a33db5e22d2f3b0403b2fcd906f5a2377">llvm::remarks::magicToFormat</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#ab13c360340346d082b959b8cd79f2c1a">llvm::Next</a>, <a href="/web-llvm/docs/api/structs/llvm/remarks/remarkparser/#af41ce5d552a2f97ed547661bcee5c26e">llvm::remarks::RemarkParser::next</a>, <a href="/web-llvm/docs/api/classes/llvm/error/#a4dfd0813c3d0e0a30439b5a3e9196b59">llvm::Error::success</a> and <a href="/web-llvm/docs/api/classes/llvm/expected/#a94789df4ebd03dc008e8adebaa66ac1f">llvm::Expected&lt; T &gt;::takeError</a>.</p>


<p>Referenced by <a href="#a2f0b07de873627d24a364adbc61b0da3">link</a>.</p>

</div>
</div>

### link() {#a2f0b07de873627d24a364adbc61b0da3}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">Error RemarkLinker::link (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/object/objectfile">object::ObjectFile</a> &amp; Obj, std::optional&lt; <a href="/web-llvm/docs/api/namespaces/llvm/remarks/#a6e038f443b9029221c590524f08be0be">Format</a> &gt; RemarkFormat=std::nullopt)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Link the remarks found in <span class="doxyComputerOutput">Obj</span> by looking for the right section and calling the method above.</p>

<p>Declaration at line 87 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/remarks/remarklinker-h">RemarkLinker.h</a>, definition at line 105 of file <a href="/web-llvm/docs/api/files/lib/lib/remarks/remarklinker-cpp">RemarkLinker.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/namespaces/llvm/remarks/#aff5f4a955d855eddcf05807595306406">llvm::remarks::getRemarksSectionContents</a>, <a href="#ac548aeb7853ce7d7cd2a3b33fb761d1b">link</a>, <a href="/web-llvm/docs/api/classes/llvm/error/#a4dfd0813c3d0e0a30439b5a3e9196b59">llvm::Error::success</a> and <a href="/web-llvm/docs/api/classes/llvm/expected/#a94789df4ebd03dc008e8adebaa66ac1f">llvm::Expected&lt; T &gt;::takeError</a>.</p>

</div>
</div>

### remarks() {#aed4941ce0de71fb529dad68a145605e1}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">iterator_range&lt; iterator &gt; llvm::remarks::RemarkLinker::remarks ()</td>
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



<p>Definition at line 104 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/remarks/remarklinker-h">RemarkLinker.h</a>.</p>


<p>Referenced by <a href="#a520480e348343b25dce916ceca76dcd5">serialize</a>.</p>

</div>
</div>

### serialize() {#a520480e348343b25dce916ceca76dcd5}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">Error RemarkLinker::serialize (<a href="/web-llvm/docs/api/classes/llvm/raw-ostream">raw_ostream</a> &amp; OS, <a href="/web-llvm/docs/api/namespaces/llvm/remarks/#a6e038f443b9029221c590524f08be0be">Format</a> RemarksFormat)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Serialize the linked remarks to the stream <span class="doxyComputerOutput">OS</span>, using the format <span class="doxyComputerOutput">RemarkFormat</span>.</p>


<p>This clears internal state such as the string table. Note: this implies that the serialization mode is standalone.</p>


<p>Declaration at line 94 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/remarks/remarklinker-h">RemarkLinker.h</a>, definition at line 117 of file <a href="/web-llvm/docs/api/files/lib/lib/remarks/remarklinker-cpp">RemarkLinker.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/namespaces/llvm/remarks/#a4ecdd1fa742884c757fc22ad0674d761">llvm::remarks::createRemarkSerializer</a>, <a href="#aed4941ce0de71fb529dad68a145605e1">remarks</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a0a00aed2787bd3f818d745a1ef171bf3">llvm::RemarksFormat</a>, <a href="/web-llvm/docs/api/namespaces/llvm/remarks/#ae5b0a3a7cf356fc6c7602b8279061a66a5c80f101108a356211fcb26b3f83eabb">llvm::remarks::Standalone</a>, <a href="/web-llvm/docs/api/classes/llvm/error/#a4dfd0813c3d0e0a30439b5a3e9196b59">llvm::Error::success</a> and <a href="/web-llvm/docs/api/classes/llvm/expected/#a94789df4ebd03dc008e8adebaa66ac1f">llvm::Expected&lt; T &gt;::takeError</a>.</p>

</div>
</div>

### setExternalFilePrependPath() {#a2c2acd23f65c858448855008917e63c3}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void RemarkLinker::setExternalFilePrependPath (<a href="/web-llvm/docs/api/classes/llvm/stringref">StringRef</a> PrependPath)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Set a path to prepend to the external file path.</p>

<p>Declaration at line 72 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/remarks/remarklinker-h">RemarkLinker.h</a>, definition at line 65 of file <a href="/web-llvm/docs/api/files/lib/lib/remarks/remarklinker-cpp">RemarkLinker.cpp</a>.</p>

</div>
</div>

### setKeepAllRemarks() {#a8d717eef5f50f721c590bc64167551e1}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void llvm::remarks::RemarkLinker::setKeepAllRemarks (bool B)</td>
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

<p>Set KeepAllRemarks to <span class="doxyComputerOutput">B</span>.</p>

<p>Definition at line 75 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/remarks/remarklinker-h">RemarkLinker.h</a>.</p>


<p>Reference <a href="/web-llvm/docs/api/files/lib/lib/ir/builtingcs-cpp/#ae76959fe811ba090de4cba69ac00f1da">B</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Private Member Functions

### keep() {#ab9e8b05322c3596f40a9077cae508ac9}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">Remark &amp; RemarkLinker::keep (std::unique_ptr&lt; <a href="/web-llvm/docs/api/structs/llvm/remarks/remark">Remark</a> &gt; Remark)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Keep this remark. If it's already in the set, discard it.</p>

<p>Declaration at line 62 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/remarks/remarklinker-h">RemarkLinker.h</a>, definition at line 59 of file <a href="/web-llvm/docs/api/files/lib/lib/remarks/remarklinker-cpp">RemarkLinker.cpp</a>.</p>

</div>
</div>

### shouldKeepRemark() {#a689584b7d83c06c54030883084041679}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool llvm::remarks::RemarkLinker::shouldKeepRemark (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/structs/llvm/remarks/remark">Remark</a> &amp; R)</td>
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

<p>Returns true if <span class="doxyComputerOutput">R</span> should be kept.</p>


<p>If KeepAllRemarks is false, only return true if <span class="doxyComputerOutput">R</span> has a valid debug location.</p>


<p>Definition at line 66 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/remarks/remarklinker-h">RemarkLinker.h</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Private Member Attributes

### KeepAllRemarks {#a404034ad5a6fe59ed2cae373244b75a0}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool llvm::remarks::RemarkLinker::KeepAllRemarks = <a href="/web-llvm/docs/api/files/lib/lib/analysis/basicaliasanalysis-cpp/#af6d5cafbdfc5313e65d990120021a3ec">true</a></td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>If true, keep all remarks, otherwise only keep remarks with valid debug locations.</p>

<p>Definition at line 59 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/remarks/remarklinker-h">RemarkLinker.h</a>.</p>

</div>
</div>

### PrependPath {#a0f0be94f33572fc6578d3b1b142b1ac4}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">std::optional&lt;std::string&gt; llvm::remarks::RemarkLinker::PrependPath</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>A path to append before the external file path found in remark metadata.</p>

<p>Definition at line 55 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/remarks/remarklinker-h">RemarkLinker.h</a>.</p>

</div>
</div>

### Remarks {#a44626e555ad9e79a10df1d4b573e2f17}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">std::set&lt;std::unique_ptr&lt;Remark&gt;, RemarkPtrCompare&gt; llvm::remarks::RemarkLinker::Remarks</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>A set holding unique remarks.</p>


<p>FIXME: std::set is probably not the most appropriate data structure here. Due to the limitation of having a move-only key, there isn't another obvious choice for now.</p>


<p>Definition at line 52 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/remarks/remarklinker-h">RemarkLinker.h</a>.</p>

</div>
</div>

### StrTab {#af1d42a233044ca367f9fc9fb2af1df3d}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">StringTable llvm::remarks::RemarkLinker::StrTab</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>The main string table for the remarks.</p>


<p>Note: all remarks should use the strings from this string table to avoid dangling references.</p>


<p>Definition at line 46 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/remarks/remarklinker-h">RemarkLinker.h</a>.</p>

</div>
</div>

</div>

<hr/>

The documentation for this struct was generated from the following files:

<ul>
<li><a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/remarks/remarklinker-h">RemarkLinker.h</a></li>
<li><a href="/web-llvm/docs/api/files/lib/lib/remarks/remarklinker-cpp">RemarkLinker.cpp</a></li>
</ul>

<hr/>

<p class="doxyGeneratedBy">Generated via <a href="https://github.com/xpack/doxygen2docusaurus">doxygen2docusaurus</a> by <a href="https://www.doxygen.nl">Doxygen</a> 1.15.0.</p>

</div>
