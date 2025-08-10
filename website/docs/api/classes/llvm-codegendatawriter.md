---

# DO NOT EDIT!
# Automatically generated via doxygen2docusaurus by Doxygen.

slug: /api/classes/llvm/codegendatawriter
custom_edit_url: null
toc_max_heading_level: 4
keywords:
  - doxygen
  - reference
  - class

---

<div class="doxyPage">

# `CodeGenDataWriter` Class



## Declaration

<div class="doxyDeclaration">
class llvm::CodeGenDataWriter { ... }
</div>

## Included Headers

<div class="doxyIncludesList">#include "<a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/cgdata/codegendatawriter-h">llvm/CGData/CodeGenDataWriter.h</a>"
</div>

## Public Constructors Index

<table class="doxyMembersIndex">

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a1742181610337e516c334fe4ae3a6c6a">CodeGenDataWriter</a> ()=default</td>
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

## Public Destructor Index

<table class="doxyMembersIndex">

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ac9f743a20c8bb8fcebf57eecfed9c42a">~CodeGenDataWriter</a> ()=default</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ab7cd2c3a4e458cf1daa792cf16a96247">addRecord</a> (OutlinedHashTreeRecord &amp;Record)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Add the outlined hash tree record. The input hash tree is released. <a href="#ab7cd2c3a4e458cf1daa792cf16a96247">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">void</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a453194093ce41a226868830f3fd2ab42">addRecord</a> (StableFunctionMapRecord &amp;Record)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Add the stable function map record. The input function map is released. <a href="#a453194093ce41a226868830f3fd2ab42">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/error">Error</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a861a894f3b8f9ca0f3d32291f45f1ff7">write</a> (raw_fd_ostream &amp;OS)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Write the codegen data to <span class="doxyComputerOutput">OS</span>. <a href="#a861a894f3b8f9ca0f3d32291f45f1ff7">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/error">Error</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a3d66364f052981f528220d5580ad012f">writeText</a> (raw_fd_ostream &amp;OS)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Write the codegen data in text format to <span class="doxyComputerOutput">OS</span>. <a href="#a3d66364f052981f528220d5580ad012f">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/namespaces/llvm/#a0ba893e7dc00f439ef557e79f12e899f">CGDataKind</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a0c4cc79b2c186eb7fa8c65d277b3113c">getCGDataKind</a> () const</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Return the attributes of the current CGData. <a href="#a0c4cc79b2c186eb7fa8c65d277b3113c">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">bool</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a98b7117046da2a30638d36e231346b96">hasOutlinedHashTree</a> () const</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Return true if the header indicates the data has an outlined hash tree. <a href="#a98b7117046da2a30638d36e231346b96">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">bool</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a9ba521ca543b95c7bb9cfddc8b101ca2">hasStableFunctionMap</a> () const</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Return true if the header indicates the data has a stable function map. <a href="#a9ba521ca543b95c7bb9cfddc8b101ca2">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

</table>

## Private Member Functions Index

<table class="doxyMembersIndex">

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/error">Error</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a7e3cdaca7d4b41336680f5c992e6afe2">writeHeader</a> (CGDataOStream &amp;COS)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Write the codegen data header to <span class="doxyComputerOutput">COS</span>. <a href="#a7e3cdaca7d4b41336680f5c992e6afe2">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/error">Error</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a27b7daeb649bcd969aebc9b8f5dc7a6b">writeHeaderText</a> (raw_fd_ostream &amp;OS)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Write the codegen data header in text to <span class="doxyComputerOutput">OS</span>. <a href="#a27b7daeb649bcd969aebc9b8f5dc7a6b">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/error">Error</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#afa02fc2659a3945a84014ac4a20e3700">writeImpl</a> (CGDataOStream &amp;COS)</td>
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

## Private Member Attributes Index

<table class="doxyMembersIndex">

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/structs/llvm/outlinedhashtreerecord">OutlinedHashTreeRecord</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a34d43d8b2ae8ea4ef0717d0a69a9e417">HashTreeRecord</a></td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>The outlined hash tree to be written. <a href="#a34d43d8b2ae8ea4ef0717d0a69a9e417">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/structs/llvm/stablefunctionmaprecord">StableFunctionMapRecord</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a4d468fdb28cf9c051613e5a59d06cace">FunctionMapRecord</a></td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>The stable function map to be written. <a href="#a4d468fdb28cf9c051613e5a59d06cace">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/namespaces/llvm/#a0ba893e7dc00f439ef557e79f12e899f">CGDataKind</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a3768a68eb1f01daa858f6c704087f24a">DataKind</a> = <a href="/web-llvm/docs/api/namespaces/llvm/#a0ba893e7dc00f439ef557e79f12e899fa88183b946cc5f0e8c96b2e66e1c74a7e">CGDataKind::Unknown</a></td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>A bit mask describing the kind of the codegen data. <a href="#a3768a68eb1f01daa858f6c704087f24a">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">uint64_t</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a0656791cd81b6bab7068bdf3bae14be3">OutlinedHashTreeOffset</a></td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>The offset of the outlined hash tree in the file. <a href="#a0656791cd81b6bab7068bdf3bae14be3">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">uint64_t</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a1d74409d96c926a70dc205d632e6f27c">StableFunctionMapOffset</a></td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>The offset of the stable function map in the file. <a href="#a1d74409d96c926a70dc205d632e6f27c">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

</table>


<p>Definition at line 57 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/cgdata/codegendatawriter-h">CodeGenDataWriter.h</a>.</p>


<div class="doxySectionDef">

## Public Constructors

### CodeGenDataWriter() {#a1742181610337e516c334fe4ae3a6c6a}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">llvm::CodeGenDataWriter::CodeGenDataWriter ()</td>
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



<p>Definition at line 68 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/cgdata/codegendatawriter-h">CodeGenDataWriter.h</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Public Destructor

### \~CodeGenDataWriter() {#ac9f743a20c8bb8fcebf57eecfed9c42a}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">llvm::CodeGenDataWriter::~CodeGenDataWriter ()</td>
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



<p>Definition at line 69 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/cgdata/codegendatawriter-h">CodeGenDataWriter.h</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Public Member Functions

### addRecord() {#ab7cd2c3a4e458cf1daa792cf16a96247}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void CodeGenDataWriter::addRecord (<a href="/web-llvm/docs/api/structs/llvm/outlinedhashtreerecord">OutlinedHashTreeRecord</a> &amp; Record)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Add the outlined hash tree record. The input hash tree is released.</p>

<p>Declaration at line 72 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/cgdata/codegendatawriter-h">CodeGenDataWriter.h</a>, definition at line 48 of file <a href="/web-llvm/docs/api/files/lib/lib/cgdata/codegendatawriter-cpp">CodeGenDataWriter.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/silowercontrolflow-cpp/#a4868c5d81c5ccc98c47aeab6244346a0">assert</a> and <a href="/web-llvm/docs/api/namespaces/llvm/#a0ba893e7dc00f439ef557e79f12e899fae43cdbf8003571786314ee11a4028215">llvm::FunctionOutlinedHashTree</a>.</p>

</div>
</div>

### addRecord() {#a453194093ce41a226868830f3fd2ab42}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void CodeGenDataWriter::addRecord (<a href="/web-llvm/docs/api/structs/llvm/stablefunctionmaprecord">StableFunctionMapRecord</a> &amp; Record)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Add the stable function map record. The input function map is released.</p>

<p>Declaration at line 75 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/cgdata/codegendatawriter-h">CodeGenDataWriter.h</a>, definition at line 55 of file <a href="/web-llvm/docs/api/files/lib/lib/cgdata/codegendatawriter-cpp">CodeGenDataWriter.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/silowercontrolflow-cpp/#a4868c5d81c5ccc98c47aeab6244346a0">assert</a> and <a href="/web-llvm/docs/api/namespaces/llvm/#a0ba893e7dc00f439ef557e79f12e899fa6c3b28d822d5623f3a00d66057afca55">llvm::StableFunctionMergingMap</a>.</p>

</div>
</div>

### getCGDataKind() {#a0c4cc79b2c186eb7fa8c65d277b3113c}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">CGDataKind llvm::CodeGenDataWriter::getCGDataKind ()</td>
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

<p>Return the attributes of the current CGData.</p>

<p>Definition at line 84 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/cgdata/codegendatawriter-h">CodeGenDataWriter.h</a>.</p>

</div>
</div>

### hasOutlinedHashTree() {#a98b7117046da2a30638d36e231346b96}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool llvm::CodeGenDataWriter::hasOutlinedHashTree ()</td>
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

<p>Return true if the header indicates the data has an outlined hash tree.</p>

<p>Definition at line 87 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/cgdata/codegendatawriter-h">CodeGenDataWriter.h</a>.</p>


<p>Reference <a href="/web-llvm/docs/api/namespaces/llvm/#a0ba893e7dc00f439ef557e79f12e899fae43cdbf8003571786314ee11a4028215">llvm::FunctionOutlinedHashTree</a>.</p>


<p>Referenced by <a href="#a3d66364f052981f528220d5580ad012f">writeText</a>.</p>

</div>
</div>

### hasStableFunctionMap() {#a9ba521ca543b95c7bb9cfddc8b101ca2}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool llvm::CodeGenDataWriter::hasStableFunctionMap ()</td>
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

<p>Return true if the header indicates the data has a stable function map.</p>

<p>Definition at line 92 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/cgdata/codegendatawriter-h">CodeGenDataWriter.h</a>.</p>


<p>Reference <a href="/web-llvm/docs/api/namespaces/llvm/#a0ba893e7dc00f439ef557e79f12e899fa6c3b28d822d5623f3a00d66057afca55">llvm::StableFunctionMergingMap</a>.</p>


<p>Referenced by <a href="#a3d66364f052981f528220d5580ad012f">writeText</a>.</p>

</div>
</div>

### write() {#a861a894f3b8f9ca0f3d32291f45f1ff7}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">Error CodeGenDataWriter::write (<a href="/web-llvm/docs/api/classes/llvm/raw-fd-ostream">raw_fd_ostream</a> &amp; OS)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Write the codegen data to <span class="doxyComputerOutput">OS</span>.</p>

<p>Declaration at line 78 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/cgdata/codegendatawriter-h">CodeGenDataWriter.h</a>, definition at line 62 of file <a href="/web-llvm/docs/api/files/lib/lib/cgdata/codegendatawriter-cpp">CodeGenDataWriter.cpp</a>.</p>

</div>
</div>

### writeText() {#a3d66364f052981f528220d5580ad012f}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">Error CodeGenDataWriter::writeText (<a href="/web-llvm/docs/api/classes/llvm/raw-fd-ostream">raw_fd_ostream</a> &amp; OS)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Write the codegen data in text format to <span class="doxyComputerOutput">OS</span>.</p>

<p>Declaration at line 81 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/cgdata/codegendatawriter-h">CodeGenDataWriter.h</a>, definition at line 137 of file <a href="/web-llvm/docs/api/files/lib/lib/cgdata/codegendatawriter-cpp">CodeGenDataWriter.cpp</a>.</p>


<p>References <a href="#a98b7117046da2a30638d36e231346b96">hasOutlinedHashTree</a>, <a href="#a9ba521ca543b95c7bb9cfddc8b101ca2">hasStableFunctionMap</a> and <a href="/web-llvm/docs/api/classes/llvm/error/#a4dfd0813c3d0e0a30439b5a3e9196b59">llvm::Error::success</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Private Member Functions

### writeHeader() {#a7e3cdaca7d4b41336680f5c992e6afe2}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">Error CodeGenDataWriter::writeHeader (<a href="/web-llvm/docs/api/classes/llvm/cgdataostream">CGDataOStream</a> &amp; COS)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Write the codegen data header to <span class="doxyComputerOutput">COS</span>.</p>

<p>Declaration at line 105 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/cgdata/codegendatawriter-h">CodeGenDataWriter.h</a>, definition at line 67 of file <a href="/web-llvm/docs/api/files/lib/lib/cgdata/codegendatawriter-cpp">CodeGenDataWriter.cpp</a>.</p>

</div>
</div>

### writeHeaderText() {#a27b7daeb649bcd969aebc9b8f5dc7a6b}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">Error CodeGenDataWriter::writeHeaderText (<a href="/web-llvm/docs/api/classes/llvm/raw-fd-ostream">raw_fd_ostream</a> &amp; OS)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Write the codegen data header in text to <span class="doxyComputerOutput">OS</span>.</p>

<p>Declaration at line 108 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/cgdata/codegendatawriter-h">CodeGenDataWriter.h</a>, definition at line 125 of file <a href="/web-llvm/docs/api/files/lib/lib/cgdata/codegendatawriter-cpp">CodeGenDataWriter.cpp</a>.</p>

</div>
</div>

### writeImpl() {#afa02fc2659a3945a84014ac4a20e3700}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">Error CodeGenDataWriter::writeImpl (<a href="/web-llvm/docs/api/classes/llvm/cgdataostream">CGDataOStream</a> &amp; COS)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Declaration at line 110 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/cgdata/codegendatawriter-h">CodeGenDataWriter.h</a>, definition at line 105 of file <a href="/web-llvm/docs/api/files/lib/lib/cgdata/codegendatawriter-cpp">CodeGenDataWriter.cpp</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Private Member Attributes

### DataKind {#a3768a68eb1f01daa858f6c704087f24a}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">CGDataKind llvm::CodeGenDataWriter::DataKind = <a href="/web-llvm/docs/api/namespaces/llvm/#a0ba893e7dc00f439ef557e79f12e899fa88183b946cc5f0e8c96b2e66e1c74a7e">CGDataKind::Unknown</a></td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>A bit mask describing the kind of the codegen data.</p>

<p>Definition at line 65 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/cgdata/codegendatawriter-h">CodeGenDataWriter.h</a>.</p>

</div>
</div>

### FunctionMapRecord {#a4d468fdb28cf9c051613e5a59d06cace}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">StableFunctionMapRecord llvm::CodeGenDataWriter::FunctionMapRecord</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>The stable function map to be written.</p>

<p>Definition at line 62 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/cgdata/codegendatawriter-h">CodeGenDataWriter.h</a>.</p>

</div>
</div>

### HashTreeRecord {#a34d43d8b2ae8ea4ef0717d0a69a9e417}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">OutlinedHashTreeRecord llvm::CodeGenDataWriter::HashTreeRecord</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>The outlined hash tree to be written.</p>

<p>Definition at line 59 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/cgdata/codegendatawriter-h">CodeGenDataWriter.h</a>.</p>

</div>
</div>

### OutlinedHashTreeOffset {#a0656791cd81b6bab7068bdf3bae14be3}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">uint64_t llvm::CodeGenDataWriter::OutlinedHashTreeOffset</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>The offset of the outlined hash tree in the file.</p>

<p>Definition at line 99 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/cgdata/codegendatawriter-h">CodeGenDataWriter.h</a>.</p>

</div>
</div>

### StableFunctionMapOffset {#a1d74409d96c926a70dc205d632e6f27c}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">uint64_t llvm::CodeGenDataWriter::StableFunctionMapOffset</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>The offset of the stable function map in the file.</p>

<p>Definition at line 102 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/cgdata/codegendatawriter-h">CodeGenDataWriter.h</a>.</p>

</div>
</div>

</div>

<hr/>

The documentation for this class was generated from the following files:

<ul>
<li><a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/cgdata/codegendatawriter-h">CodeGenDataWriter.h</a></li>
<li><a href="/web-llvm/docs/api/files/lib/lib/cgdata/codegendatawriter-cpp">CodeGenDataWriter.cpp</a></li>
</ul>

<hr/>

<p class="doxyGeneratedBy">Generated via <a href="https://xpack.github.io/doxygen2docusaurus">doxygen2docusaurus</a> 2.0.0 by <a href="https://www.doxygen.nl">Doxygen</a> 1.15.0.</p>

</div>
