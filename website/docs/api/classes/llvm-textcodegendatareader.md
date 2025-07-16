---

# DO NOT EDIT!
# Automatically generated via doxygen2docusaurus by Doxygen.

slug: /api/classes/llvm/textcodegendatareader
custom_edit_url: null
toc_max_heading_level: 4
keywords:
  - doxygen
  - reference
  - class

---

<div class="doxyPage">

# The `TextCodeGenDataReader` Class Reference

<p>This format is a simple text format that's suitable for test data. <a href="#details">More...</a></p>

## Declaration

<div class="doxyDeclaration">
class llvm::TextCodeGenDataReader { ... }
</div>

## Included Headers

<div class="doxyIncludesList">#include "<a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/cgdata/codegendatareader-h">llvm/CGData/CodeGenDataReader.h</a>"
</div>

## Base class

<table class="doxyMembersIndex">

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">class</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/codegendatareader">CodeGenDataReader</a></td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ae69f5c7f0c299614d5f4889b180df61a">TextCodeGenDataReader</a> (std::unique_ptr&lt; MemoryBuffer &gt; DataBuffer_)</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ad5450da05b9514dee92bd51ff0cc0d0f">TextCodeGenDataReader</a> (const TextCodeGenDataReader &amp;)=delete</td>
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

## Public Operators Index

<table class="doxyMembersIndex">

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/textcodegendatareader">TextCodeGenDataReader</a> &amp;</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a859c55bdbb63c4e6a96fed3caef23054">operator=</a> (const TextCodeGenDataReader &amp;)=delete</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/error">Error</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a6a6f3695c97c301eee0369ec5e669c61">read</a> () override</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Read the contents including the header. <a href="#a6a6f3695c97c301eee0369ec5e669c61">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">uint32_t</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a9bf5a794d1bc797ac2d297e53f4dd7de">getVersion</a> () const override</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Text format does not have version, so return 0. <a href="#a9bf5a794d1bc797ac2d297e53f4dd7de">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/namespaces/llvm/#a0ba893e7dc00f439ef557e79f12e899f">CGDataKind</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#af32fd4139e9b2e17498529ec3962a76b">getDataKind</a> () const override</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Return the codegen data kind. <a href="#af32fd4139e9b2e17498529ec3962a76b">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">bool</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a68854a96bdcb976a8dca5cda1d52e0ea">hasOutlinedHashTree</a> () const override</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Return true if the header indicates the data has an outlined hash tree. <a href="#a68854a96bdcb976a8dca5cda1d52e0ea">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">bool</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a2e6bd5da5516cd15d7331b544e2eb6c8">hasStableFunctionMap</a> () const override</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Return true if the header indicates the data has a stable function map. <a href="#a2e6bd5da5516cd15d7331b544e2eb6c8">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

</table>

## Private Member Attributes Index

<table class="doxyMembersIndex">

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">std::unique_ptr&lt; <a href="/web-llvm/docs/api/classes/llvm/memorybuffer">MemoryBuffer</a> &gt;</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a6431a43f318d7a67ddb36c6fe97e2fd9">DataBuffer</a></td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>The codegen data file contents. <a href="#a6431a43f318d7a67ddb36c6fe97e2fd9">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/line-iterator">line_iterator</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a9d4946c87f57039b3da880bfb463129a">Line</a></td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Iterator over the profile data. <a href="#a9d4946c87f57039b3da880bfb463129a">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/namespaces/llvm/#a0ba893e7dc00f439ef557e79f12e899f">CGDataKind</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a2955fd3874894b8fbb248fd24b752ad1">DataKind</a> = <a href="/web-llvm/docs/api/namespaces/llvm/#a0ba893e7dc00f439ef557e79f12e899fa88183b946cc5f0e8c96b2e66e1c74a7e">CGDataKind::Unknown</a></td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Describe the kind of the codegen data. <a href="#a2955fd3874894b8fbb248fd24b752ad1">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

</table>

## Public Static Functions Index

<table class="doxyMembersIndex">

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">static bool</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a0199559e6f0464acf4c2c30bcb041a03">hasFormat</a> (const MemoryBuffer &amp;Buffer)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Return true if the given buffer is in text codegen data format. <a href="#a0199559e6f0464acf4c2c30bcb041a03">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

</table>

## Description {#details}

<p>This format is a simple text format that's suitable for test data.</p>


<p>The header is a custom format starting with <span class="doxyComputerOutput">:</span> per line to indicate which codegen data is recorded. <span class="doxyComputerOutput">#</span> is used to indicate a comment. The subsequent data is a YAML format per each codegen data in order. Currently, it only has a function outlined hash tree.</p>


<p>Definition at line 142 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/cgdata/codegendatareader-h">CodeGenDataReader.h</a>.</p>


<div class="doxySectionDef">

## Public Constructors

### TextCodeGenDataReader() {#ae69f5c7f0c299614d5f4889b180df61a}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">llvm::TextCodeGenDataReader::TextCodeGenDataReader (std::unique_ptr&lt; <a href="/web-llvm/docs/api/classes/llvm/memorybuffer">MemoryBuffer</a> &gt; DataBuffer_)</td>
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



<p>Definition at line 151 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/cgdata/codegendatareader-h">CodeGenDataReader.h</a>.</p>


<p>References <a href="/web-llvm/docs/api/namespaces/llvm/#abfc9c7ecf70f66901e439f7c04ef3dbb">llvm::move</a> and <a href="/web-llvm/docs/api/files/lib/lib/analysis/basicaliasanalysis-cpp/#af6d5cafbdfc5313e65d990120021a3ec">true</a>.</p>


<p>Referenced by <a href="#a859c55bdbb63c4e6a96fed3caef23054">operator=</a> and <a href="#ad5450da05b9514dee92bd51ff0cc0d0f">TextCodeGenDataReader</a>.</p>

</div>
</div>

### TextCodeGenDataReader() {#ad5450da05b9514dee92bd51ff0cc0d0f}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">llvm::TextCodeGenDataReader::TextCodeGenDataReader (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/textcodegendatareader">TextCodeGenDataReader</a> &amp;)</td>
</tr>
</table>
</td>
<td class="doxyMemberLabelsRight">
<span class="doxyMemberLabels">
<span class="doxyMemberLabel delete">delete</span>
</span>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 153 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/cgdata/codegendatareader-h">CodeGenDataReader.h</a>.</p>


<p>Reference <a href="#ae69f5c7f0c299614d5f4889b180df61a">TextCodeGenDataReader</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Public Operators

### operator=() {#a859c55bdbb63c4e6a96fed3caef23054}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">TextCodeGenDataReader &amp; llvm::TextCodeGenDataReader::operator= (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/textcodegendatareader">TextCodeGenDataReader</a> &amp;)</td>
</tr>
</table>
</td>
<td class="doxyMemberLabelsRight">
<span class="doxyMemberLabels">
<span class="doxyMemberLabel delete">delete</span>
</span>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 154 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/cgdata/codegendatareader-h">CodeGenDataReader.h</a>.</p>


<p>Reference <a href="#ae69f5c7f0c299614d5f4889b180df61a">TextCodeGenDataReader</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Public Member Functions

### getDataKind() {#af32fd4139e9b2e17498529ec3962a76b}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">CGDataKind llvm::TextCodeGenDataReader::getDataKind ()</td>
</tr>
</table>
</td>
<td class="doxyMemberLabelsRight">
<span class="doxyMemberLabels">
<span class="doxyMemberLabel inline">inline</span>
<span class="doxyMemberLabel virtual">virtual</span>
</span>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Return the codegen data kind.</p>

<p>Definition at line 163 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/cgdata/codegendatareader-h">CodeGenDataReader.h</a>.</p>

</div>
</div>

### getVersion() {#a9bf5a794d1bc797ac2d297e53f4dd7de}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">uint32_t llvm::TextCodeGenDataReader::getVersion ()</td>
</tr>
</table>
</td>
<td class="doxyMemberLabelsRight">
<span class="doxyMemberLabels">
<span class="doxyMemberLabel inline">inline</span>
<span class="doxyMemberLabel virtual">virtual</span>
</span>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Text format does not have version, so return 0.</p>

<p>Definition at line 161 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/cgdata/codegendatareader-h">CodeGenDataReader.h</a>.</p>

</div>
</div>

### hasOutlinedHashTree() {#a68854a96bdcb976a8dca5cda1d52e0ea}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool llvm::TextCodeGenDataReader::hasOutlinedHashTree ()</td>
</tr>
</table>
</td>
<td class="doxyMemberLabelsRight">
<span class="doxyMemberLabels">
<span class="doxyMemberLabel inline">inline</span>
<span class="doxyMemberLabel virtual">virtual</span>
</span>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Return true if the header indicates the data has an outlined hash tree.</p>


<p>This does not mean that the data is still available.</p>


<p>Definition at line 166 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/cgdata/codegendatareader-h">CodeGenDataReader.h</a>.</p>


<p>Reference <a href="/web-llvm/docs/api/namespaces/llvm/#a0ba893e7dc00f439ef557e79f12e899fae43cdbf8003571786314ee11a4028215">llvm::FunctionOutlinedHashTree</a>.</p>


<p>Referenced by <a href="#a6a6f3695c97c301eee0369ec5e669c61">read</a>.</p>

</div>
</div>

### hasStableFunctionMap() {#a2e6bd5da5516cd15d7331b544e2eb6c8}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool llvm::TextCodeGenDataReader::hasStableFunctionMap ()</td>
</tr>
</table>
</td>
<td class="doxyMemberLabelsRight">
<span class="doxyMemberLabels">
<span class="doxyMemberLabel inline">inline</span>
<span class="doxyMemberLabel virtual">virtual</span>
</span>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Return true if the header indicates the data has a stable function map.</p>


<p>This does not mean that the data is still available.</p>


<p>Definition at line 172 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/cgdata/codegendatareader-h">CodeGenDataReader.h</a>.</p>


<p>Reference <a href="/web-llvm/docs/api/namespaces/llvm/#a0ba893e7dc00f439ef557e79f12e899fa6c3b28d822d5623f3a00d66057afca55">llvm::StableFunctionMergingMap</a>.</p>


<p>Referenced by <a href="#a6a6f3695c97c301eee0369ec5e669c61">read</a>.</p>

</div>
</div>

### read() {#a6a6f3695c97c301eee0369ec5e669c61}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">Error llvm::TextCodeGenDataReader::read ()</td>
</tr>
</table>
</td>
<td class="doxyMemberLabelsRight">
<span class="doxyMemberLabels">
<span class="doxyMemberLabel virtual">virtual</span>
</span>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Read the contents including the header.</p>

<p>Declaration at line 159 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/cgdata/codegendatareader-h">CodeGenDataReader.h</a>, definition at line 162 of file <a href="/web-llvm/docs/api/files/lib/lib/cgdata/codegendatareader-cpp">CodeGenDataReader.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/namespaces/llvm/#a6ea6fb3a4e8248113053829b7fd89c96adde571add68cc36593098a17df48bd45">llvm::bad_header</a>, <a href="/web-llvm/docs/api/files/lib/lib/debuginfo/lib/debuginfo/codeview/symbolrecordmapping-cpp/#a9cdf893c7d17e47fa1ed8bebf92a5da4">error</a>, <a href="/web-llvm/docs/api/classes/llvm/codegendatareader/#a83f3e8474f7cca254a19d876f2e9a3b7">llvm::CodeGenDataReader::FunctionMapRecord</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a0ba893e7dc00f439ef557e79f12e899fae43cdbf8003571786314ee11a4028215">llvm::FunctionOutlinedHashTree</a>, <a href="/web-llvm/docs/api/classes/llvm/codegendatareader/#a3897d2b4576b899d566186c2a97a7a79">llvm::CodeGenDataReader::HashTreeRecord</a>, <a href="#a68854a96bdcb976a8dca5cda1d52e0ea">hasOutlinedHashTree</a>, <a href="#a2e6bd5da5516cd15d7331b544e2eb6c8">hasStableFunctionMap</a>, <a href="/web-llvm/docs/api/files/lib/lib/analysis/inlineorder-cpp/#a7ee6f0cb51c3b9056199e9a0001fe8c3a6f6cb72d544962fa333e2e34ce64f719">Size</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a0ba893e7dc00f439ef557e79f12e899fa6c3b28d822d5623f3a00d66057afca55">llvm::StableFunctionMergingMap</a>, <a href="/web-llvm/docs/api/classes/llvm/error/#a4dfd0813c3d0e0a30439b5a3e9196b59">llvm::Error::success</a> and <a href="/web-llvm/docs/api/namespaces/llvm/#a0ba893e7dc00f439ef557e79f12e899fa88183b946cc5f0e8c96b2e66e1c74a7e">llvm::Unknown</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Private Member Attributes

### DataBuffer {#a6431a43f318d7a67ddb36c6fe97e2fd9}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">std::unique_ptr&lt;MemoryBuffer&gt; llvm::TextCodeGenDataReader::DataBuffer</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>The codegen data file contents.</p>

<p>Definition at line 144 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/cgdata/codegendatareader-h">CodeGenDataReader.h</a>.</p>

</div>
</div>

### DataKind {#a2955fd3874894b8fbb248fd24b752ad1}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">CGDataKind llvm::TextCodeGenDataReader::DataKind = <a href="/web-llvm/docs/api/namespaces/llvm/#a0ba893e7dc00f439ef557e79f12e899fa88183b946cc5f0e8c96b2e66e1c74a7e">CGDataKind::Unknown</a></td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Describe the kind of the codegen data.</p>

<p>Definition at line 148 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/cgdata/codegendatareader-h">CodeGenDataReader.h</a>.</p>

</div>
</div>

### Line {#a9d4946c87f57039b3da880bfb463129a}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">line_iterator llvm::TextCodeGenDataReader::Line</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Iterator over the profile data.</p>

<p>Definition at line 146 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/cgdata/codegendatareader-h">CodeGenDataReader.h</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Public Static Functions

### hasFormat() {#a0199559e6f0464acf4c2c30bcb041a03}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool llvm::TextCodeGenDataReader::hasFormat (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/memorybuffer">MemoryBuffer</a> &amp; Buffer)</td>
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

<p>Return true if the given buffer is in text codegen data format.</p>

<p>Declaration at line 157 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/cgdata/codegendatareader-h">CodeGenDataReader.h</a>, definition at line 156 of file <a href="/web-llvm/docs/api/files/lib/lib/cgdata/codegendatareader-cpp">CodeGenDataReader.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/namespaces/llvm/#a0d10fe510ced2849a8074fe81e5d04ce">llvm::all_of</a>, <a href="/web-llvm/docs/api/classes/llvm/memorybuffer/#a69d9843621ff4677c0b9087277dc4bd0">llvm::MemoryBuffer::getBuffer</a> and <a href="/web-llvm/docs/api/classes/llvm/stringref/#aa28286a33491b5d9a936fb6ae853baee">llvm::StringRef::take_front</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/classes/llvm/codegendatareader/#a378e68eccfba5cca99d032743ec74ad1">llvm::CodeGenDataReader::create</a>.</p>

</div>
</div>

</div>

<hr/>

The documentation for this class was generated from the following files:

<ul>
<li><a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/cgdata/codegendatareader-h">CodeGenDataReader.h</a></li>
<li><a href="/web-llvm/docs/api/files/lib/lib/cgdata/codegendatareader-cpp">CodeGenDataReader.cpp</a></li>
</ul>

<hr/>

<p class="doxyGeneratedBy">Generated via <a href="https://github.com/xpack/doxygen2docusaurus">doxygen2docusaurus</a> by <a href="https://www.doxygen.nl">Doxygen</a> 1.15.0.</p>

</div>
