---

# DO NOT EDIT!
# Automatically generated via doxygen2docusaurus by Doxygen.

slug: /api/structs/llvm/gsym/mergedfunctionsinfo
custom_edit_url: null
toc_max_heading_level: 4
keywords:
  - doxygen
  - reference
  - struct

---

<div class="doxyPage">

# The `MergedFunctionsInfo` Struct Reference



## Declaration

<div class="doxyDeclaration">
struct llvm::gsym::MergedFunctionsInfo { ... }
</div>

## Included Headers

<div class="doxyIncludesList">#include "<a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/debuginfo/include/llvm/debuginfo/gsym/mergedfunctionsinfo-h">llvm/DebugInfo/GSYM/MergedFunctionsInfo.h</a>"
</div>

## Public Member Functions Index

<table class="doxyMembersIndex">

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">void</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a941447d150c12ba63d0d725b0b19119b">clear</a> ()</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ac50be94c3b5ffa5f679104dc29fdfcc4">isValid</a> ()</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Query if a <a href="/web-llvm/docs/api/structs/llvm/gsym/mergedfunctionsinfo">MergedFunctionsInfo</a> object is valid. <a href="#ac50be94c3b5ffa5f679104dc29fdfcc4">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/error">llvm::Error</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#acf6e5aa620d3dbd266db4b6d03388ed7">encode</a> (FileWriter &amp;O) const</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Encode this <a href="/web-llvm/docs/api/structs/llvm/gsym/mergedfunctionsinfo">MergedFunctionsInfo</a> object into <a href="/web-llvm/docs/api/classes/llvm/gsym/filewriter">FileWriter</a> stream. <a href="#acf6e5aa620d3dbd266db4b6d03388ed7">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

</table>

## Public Member Attributes Index

<table class="doxyMembersIndex">

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">std::vector&lt; <a href="/web-llvm/docs/api/structs/llvm/gsym/functioninfo">FunctionInfo</a> &gt;</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ae75acbb7c5b01b67f75181b26cfe11a6">MergedFunctions</a></td>
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

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">static <a href="/web-llvm/docs/api/classes/llvm/expected">llvm::Expected</a>&lt; std::vector&lt; <a href="/web-llvm/docs/api/classes/llvm/dataextractor">DataExtractor</a> &gt; &gt;</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a494857c857bfb2ff33cc151c34c200d1">getFuncsDataExtractors</a> (DataExtractor &amp;Data)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Get a vector of <a href="/web-llvm/docs/api/classes/llvm/dataextractor">DataExtractor</a> objects for the functions in this <a href="/web-llvm/docs/api/structs/llvm/gsym/mergedfunctionsinfo">MergedFunctionsInfo</a> object. <a href="#a494857c857bfb2ff33cc151c34c200d1">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">static <a href="/web-llvm/docs/api/classes/llvm/expected">llvm::Expected</a>&lt; <a href="/web-llvm/docs/api/structs/llvm/gsym/mergedfunctionsinfo">MergedFunctionsInfo</a> &gt;</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a3f8f8f0e7e46eb22afffe9c8c5dbe50e">decode</a> (DataExtractor &amp;Data, uint64_t BaseAddr)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Decode an <a href="/web-llvm/docs/api/structs/llvm/gsym/mergedfunctionsinfo">MergedFunctionsInfo</a> object from a binary data stream. <a href="#a3f8f8f0e7e46eb22afffe9c8c5dbe50e">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

</table>


<p>Definition at line 24 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/debuginfo/include/llvm/debuginfo/gsym/mergedfunctionsinfo-h">MergedFunctionsInfo.h</a>.</p>


<div class="doxySectionDef">

## Public Member Functions

### clear() {#a941447d150c12ba63d0d725b0b19119b}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void MergedFunctionsInfo::clear ()</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Declaration at line 27 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/debuginfo/include/llvm/debuginfo/gsym/mergedfunctionsinfo-h">MergedFunctionsInfo.h</a>, definition at line 17 of file <a href="/web-llvm/docs/api/files/lib/lib/debuginfo/lib/debuginfo/gsym/mergedfunctionsinfo-cpp">MergedFunctionsInfo.cpp</a>.</p>


<p>References <a href="#a941447d150c12ba63d0d725b0b19119b">clear</a> and <a href="#ae75acbb7c5b01b67f75181b26cfe11a6">MergedFunctions</a>.</p>


<p>Referenced by <a href="#a941447d150c12ba63d0d725b0b19119b">clear</a>.</p>

</div>
</div>

### encode() {#acf6e5aa620d3dbd266db4b6d03388ed7}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">llvm::Error MergedFunctionsInfo::encode (<a href="/web-llvm/docs/api/classes/llvm/gsym/filewriter">FileWriter</a> &amp; O)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Encode this <a href="/web-llvm/docs/api/structs/llvm/gsym/mergedfunctionsinfo">MergedFunctionsInfo</a> object into <a href="/web-llvm/docs/api/classes/llvm/gsym/filewriter">FileWriter</a> stream.</p>


<dl class="doxyParamsList">
<dt class="doxyParamsTableTitle">Parameters</dt>
<dd>
<table class="doxyParamsTable">
<tr class="doxyParamItem">
<td class="doxyParamItemName">O</td>
<td class="doxyParamItemDescription"><p>The binary stream to write the data to at the current file position.</p></td>
</tr>
</table>
</dd>
</dl>

<dl class="doxySectionUser">
<dt>Returns</dt>
<dd><p>An error object that indicates success or failure for the encoding process.</p></dd>
</dl>


<p>Declaration at line 65 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/debuginfo/include/llvm/debuginfo/gsym/mergedfunctionsinfo-h">MergedFunctionsInfo.h</a>, definition at line 19 of file <a href="/web-llvm/docs/api/files/lib/lib/debuginfo/lib/debuginfo/gsym/mergedfunctionsinfo-cpp">MergedFunctionsInfo.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/files/lib/lib/support/md5-cpp/#a96d73bbd7af15cb1fc38c3f4a3bd82e9">F</a>, <a href="/web-llvm/docs/api/classes/llvm/gsym/filewriter/#a23334fee66fedcc03e7c74ed4295611c">llvm::gsym::FileWriter::fixup32</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a05f5b9a11bdcc5feba62899f95dcf878af6d9f1c7b49b7601fae6a545002a6763">llvm::Length</a>, <a href="#ae75acbb7c5b01b67f75181b26cfe11a6">MergedFunctions</a>, <a href="/web-llvm/docs/api/classes/llvm/error/#a4dfd0813c3d0e0a30439b5a3e9196b59">llvm::Error::success</a>, <a href="/web-llvm/docs/api/classes/llvm/expected/#a94789df4ebd03dc008e8adebaa66ac1f">llvm::Expected&lt; T &gt;::takeError</a>, <a href="/web-llvm/docs/api/classes/llvm/gsym/filewriter/#a1462db57acbef343fec398bfbf85391a">llvm::gsym::FileWriter::tell</a> and <a href="/web-llvm/docs/api/classes/llvm/gsym/filewriter/#a766e343d0ff12c414ffa59f35c1f562d">llvm::gsym::FileWriter::writeU32</a>.</p>

</div>
</div>

### isValid() {#ac50be94c3b5ffa5f679104dc29fdfcc4}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool llvm::gsym::MergedFunctionsInfo::isValid ()</td>
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

<p>Query if a <a href="/web-llvm/docs/api/structs/llvm/gsym/mergedfunctionsinfo">MergedFunctionsInfo</a> object is valid.</p>


<dl class="doxySectionUser">
<dt>Returns</dt>
<dd><p>A boolean indicating if this <a href="/web-llvm/docs/api/structs/llvm/gsym/functioninfo">FunctionInfo</a> is valid.</p></dd>
</dl>


<p>Definition at line 32 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/debuginfo/include/llvm/debuginfo/gsym/mergedfunctionsinfo-h">MergedFunctionsInfo.h</a>.</p>


<p>Reference <a href="#ae75acbb7c5b01b67f75181b26cfe11a6">MergedFunctions</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Public Member Attributes

### MergedFunctions {#ae75acbb7c5b01b67f75181b26cfe11a6}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">std::vector&lt;FunctionInfo&gt; llvm::gsym::MergedFunctionsInfo::MergedFunctions</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 25 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/debuginfo/include/llvm/debuginfo/gsym/mergedfunctionsinfo-h">MergedFunctionsInfo.h</a>.</p>


<p>Referenced by <a href="#a941447d150c12ba63d0d725b0b19119b">clear</a>, <a href="#a3f8f8f0e7e46eb22afffe9c8c5dbe50e">decode</a>, <a href="/web-llvm/docs/api/classes/llvm/gsym/gsymreader/#a4e9110bbf8007555e8e6b1135609d4d7">llvm::gsym::GsymReader::dump</a>, <a href="#acf6e5aa620d3dbd266db4b6d03388ed7">encode</a> and <a href="#ac50be94c3b5ffa5f679104dc29fdfcc4">isValid</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Public Static Functions

### decode() {#a3f8f8f0e7e46eb22afffe9c8c5dbe50e}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">llvm::Expected&lt; MergedFunctionsInfo &gt; MergedFunctionsInfo::decode (<a href="/web-llvm/docs/api/classes/llvm/dataextractor">DataExtractor</a> &amp; Data, uint64_t BaseAddr)</td>
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

<p>Decode an <a href="/web-llvm/docs/api/structs/llvm/gsym/mergedfunctionsinfo">MergedFunctionsInfo</a> object from a binary data stream.</p>


<dl class="doxyParamsList">
<dt class="doxyParamsTableTitle">Parameters</dt>
<dd>
<table class="doxyParamsTable">
<tr class="doxyParamItem">
<td class="doxyParamItemName">Data</td>
<td class="doxyParamItemDescription"><p>The binary stream to read the data from. This object must have the data for the <a href="/web-llvm/docs/api/structs/llvm/gsym/mergedfunctionsinfo">MergedFunctionsInfo</a> object starting at offset zero. The data can contain more data than needed.</p></td>
</tr>
<tr class="doxyParamItem">
<td class="doxyParamItemName">BaseAddr</td>
<td class="doxyParamItemDescription"><p>The base address to use when encoding all address ranges.</p></td>
</tr>
</table>
</dd>
</dl>

<dl class="doxySectionUser">
<dt>Returns</dt>
<dd><p>An <a href="/web-llvm/docs/api/structs/llvm/gsym/mergedfunctionsinfo">MergedFunctionsInfo</a> or an error describing the issue that was encountered during decoding.</p></dd>
</dl>


<p>Declaration at line 56 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/debuginfo/include/llvm/debuginfo/gsym/mergedfunctionsinfo-h">MergedFunctionsInfo.h</a>, definition at line 36 of file <a href="/web-llvm/docs/api/files/lib/lib/debuginfo/lib/debuginfo/gsym/mergedfunctionsinfo-cpp">MergedFunctionsInfo.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/namespaces/llvm/#aa20539e89704d20b98b97e9c3feac934">llvm::Data</a>, <a href="/web-llvm/docs/api/structs/llvm/gsym/functioninfo/#aea38a34c36c8f1cb37754bd3bd336053">llvm::gsym::FunctionInfo::decode</a>, <a href="#a494857c857bfb2ff33cc151c34c200d1">getFuncsDataExtractors</a>, <a href="#ae75acbb7c5b01b67f75181b26cfe11a6">MergedFunctions</a> and <a href="/web-llvm/docs/api/classes/llvm/expected/#a94789df4ebd03dc008e8adebaa66ac1f">llvm::Expected&lt; T &gt;::takeError</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/structs/llvm/gsym/functioninfo/#aea38a34c36c8f1cb37754bd3bd336053">llvm::gsym::FunctionInfo::decode</a>.</p>

</div>
</div>

### getFuncsDataExtractors() {#a494857c857bfb2ff33cc151c34c200d1}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">llvm::Expected&lt; std::vector&lt; DataExtractor &gt; &gt; MergedFunctionsInfo::getFuncsDataExtractors (<a href="/web-llvm/docs/api/classes/llvm/dataextractor">DataExtractor</a> &amp; Data)</td>
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

<p>Get a vector of <a href="/web-llvm/docs/api/classes/llvm/dataextractor">DataExtractor</a> objects for the functions in this <a href="/web-llvm/docs/api/structs/llvm/gsym/mergedfunctionsinfo">MergedFunctionsInfo</a> object.</p>


<dl class="doxyParamsList">
<dt class="doxyParamsTableTitle">Parameters</dt>
<dd>
<table class="doxyParamsTable">
<tr class="doxyParamItem">
<td class="doxyParamItemName">Data</td>
<td class="doxyParamItemDescription"><p>The binary stream to read the data from. This object must have the data for the <a href="/web-llvm/docs/api/structs/llvm/gsym/mergedfunctionsinfo">MergedFunctionsInfo</a> object starting at offset zero. The data can contain more data than needed.</p></td>
</tr>
</table>
</dd>
</dl>

<dl class="doxySectionUser">
<dt>Returns</dt>
<dd><p>An <a href="/web-llvm/docs/api/classes/llvm/expected">llvm::Expected</a> containing a vector of <a href="/web-llvm/docs/api/classes/llvm/dataextractor">DataExtractor</a> objects on success, or an error object if parsing fails.</p></dd>
</dl>


<p>Declaration at line 44 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/debuginfo/include/llvm/debuginfo/gsym/mergedfunctionsinfo-h">MergedFunctionsInfo.h</a>, definition at line 54 of file <a href="/web-llvm/docs/api/files/lib/lib/debuginfo/lib/debuginfo/gsym/mergedfunctionsinfo-cpp">MergedFunctionsInfo.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/namespaces/llvm/#a845e08be4b0320d66901a66b0c0e9509">llvm::Count</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a4d2fd926089a58d482fb67a362e11bad">llvm::createStringError</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#aa20539e89704d20b98b97e9c3feac934">llvm::Data</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a05f5b9a11bdcc5feba62899f95dcf878a3134224cba2545bc57954d3b072aebb4">llvm::Offset</a> and <a href="/web-llvm/docs/api/files/lib/lib/analysis/aliasanalysis-cpp/#a7e344cff0feadf0b02223fee63cc7475">Results</a>.</p>


<p>Referenced by <a href="#a3f8f8f0e7e46eb22afffe9c8c5dbe50e">decode</a> and <a href="/web-llvm/docs/api/classes/llvm/gsym/gsymreader/#afab544245beb837bd2fd89c12e060c3f">llvm::gsym::GsymReader::lookupAll</a>.</p>

</div>
</div>

</div>

<hr/>

The documentation for this struct was generated from the following files:

<ul>
<li><a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/debuginfo/include/llvm/debuginfo/gsym/mergedfunctionsinfo-h">MergedFunctionsInfo.h</a></li>
<li><a href="/web-llvm/docs/api/files/lib/lib/debuginfo/lib/debuginfo/gsym/mergedfunctionsinfo-cpp">MergedFunctionsInfo.cpp</a></li>
</ul>

<hr/>

<p class="doxyGeneratedBy">Generated via <a href="https://github.com/xpack/doxygen2docusaurus">doxygen2docusaurus</a> by <a href="https://www.doxygen.nl">Doxygen</a> 1.15.0.</p>

</div>
