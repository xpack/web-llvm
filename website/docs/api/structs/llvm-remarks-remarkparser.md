---

# DO NOT EDIT!
# Automatically generated via doxygen2docusaurus by Doxygen.

slug: /api/structs/llvm/remarks/remarkparser
custom_edit_url: null
toc_max_heading_level: 4
keywords:
  - doxygen
  - reference
  - struct

---

<div class="doxyPage">

# `RemarkParser` Struct

<p>Parser used to parse a raw buffer to <a href="/web-llvm/docs/api/structs/llvm/remarks/remark">remarks::Remark</a> objects. <a href="#details">More...</a></p>

## Declaration

<div class="doxyDeclaration">
struct llvm::remarks::RemarkParser { ... }
</div>

## Included Headers

<div class="doxyIncludesList">#include "<a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/remarks/remarkparser-h">llvm/Remarks/RemarkParser.h</a>"
</div>

## Derived Structs

<table class="doxyMembersIndex">

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">struct</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="/web-llvm/docs/api/structs/llvm/remarks/bitstreamremarkparser">BitstreamRemarkParser</a></td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Parses and holds the state of the latest parsed remark. <a href="/web-llvm/docs/api/structs/llvm/remarks/bitstreamremarkparser/#details">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">struct</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="/web-llvm/docs/api/structs/llvm/remarks/yamlremarkparser">YAMLRemarkParser</a></td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Regular YAML to <a href="/web-llvm/docs/api/structs/llvm/remarks/remark">Remark</a> parser. <a href="/web-llvm/docs/api/structs/llvm/remarks/yamlremarkparser/#details">More...</a></p>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a6030e67087fde04ece4556c929c0d42d">RemarkParser</a> (Format ParserFormat)</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a035027435b5b3f8ff4695b00f6b0a274">~RemarkParser</a> ()=default</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/expected">Expected</a>&lt; std::unique_ptr&lt; <a href="/web-llvm/docs/api/structs/llvm/remarks/remark">Remark</a> &gt; &gt;</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#af41ce5d552a2f97ed547661bcee5c26e">next</a> ()=0</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>If no error occurs, this returns a valid <a href="/web-llvm/docs/api/structs/llvm/remarks/remark">Remark</a> object. <a href="#af41ce5d552a2f97ed547661bcee5c26e">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

</table>

## Public Member Attributes Index

<table class="doxyMembersIndex">

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/namespaces/llvm/remarks/#a6e038f443b9029221c590524f08be0be">Format</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#aa8ed51750beb4e4042b8aed388f749d9">ParserFormat</a></td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>The format of the parser. <a href="#aa8ed51750beb4e4042b8aed388f749d9">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">std::string</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a1458e6f0ecbddf1a241415d5542dfa2c">ExternalFilePrependPath</a></td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Path to prepend when opening an external remark file. <a href="#a1458e6f0ecbddf1a241415d5542dfa2c">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

</table>

## Description {#details}

<p>Parser used to parse a raw buffer to <a href="/web-llvm/docs/api/structs/llvm/remarks/remark">remarks::Remark</a> objects.</p>

<p>Definition at line 40 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/remarks/remarkparser-h">RemarkParser.h</a>.</p>


<div class="doxySectionDef">

## Public Constructors

### RemarkParser() {#a6030e67087fde04ece4556c929c0d42d}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">llvm::remarks::RemarkParser::RemarkParser (<a href="/web-llvm/docs/api/namespaces/llvm/remarks/#a6e038f443b9029221c590524f08be0be">Format</a> ParserFormat)</td>
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



<p>Definition at line 46 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/remarks/remarkparser-h">RemarkParser.h</a>.</p>


<p>Reference <a href="#aa8ed51750beb4e4042b8aed388f749d9">ParserFormat</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/structs/llvm/remarks/bitstreamremarkparser/#a87b9d7dbab269fcc020ca77e5de6b2ea">llvm::remarks::BitstreamRemarkParser::BitstreamRemarkParser</a>, <a href="/web-llvm/docs/api/structs/llvm/remarks/bitstreamremarkparser/#a807136b05ed045dc36620215addd4bdf">llvm::remarks::BitstreamRemarkParser::BitstreamRemarkParser</a>, <a href="/web-llvm/docs/api/structs/llvm/remarks/bitstreamremarkparser/#a7ccbc7f748e9c8288e37949e48a7e1f4">llvm::remarks::BitstreamRemarkParser::classof</a>, <a href="/web-llvm/docs/api/structs/llvm/remarks/yamlremarkparser/#ac6b60b1a48be520f93b115fa62c87986">llvm::remarks::YAMLRemarkParser::classof</a> and <a href="/web-llvm/docs/api/structs/llvm/remarks/yamlremarkparser/#af68bc601b3b9224bc60c53304275ce53">llvm::remarks::YAMLRemarkParser::YAMLRemarkParser</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Public Destructor

### \~RemarkParser() {#a035027435b5b3f8ff4695b00f6b0a274}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">virtual llvm::remarks::RemarkParser::~RemarkParser ()</td>
</tr>
</table>
</td>
<td class="doxyMemberLabelsRight">
<span class="doxyMemberLabels">
<span class="doxyMemberLabel virtual">virtual</span>
<span class="doxyMemberLabel default">default</span>
</span>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 55 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/remarks/remarkparser-h">RemarkParser.h</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Public Member Functions

### next() {#af41ce5d552a2f97ed547661bcee5c26e}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">virtual Expected&lt; std::unique_ptr&lt; Remark &gt; &gt; llvm::remarks::RemarkParser::next ()</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>If no error occurs, this returns a valid <a href="/web-llvm/docs/api/structs/llvm/remarks/remark">Remark</a> object.</p>


<p>If an error of type <a href="/web-llvm/docs/api/classes/llvm/remarks/endoffileerror">EndOfFileError</a> occurs, it is safe to recover from it by stopping the parsing. If any other error occurs, it should be propagated to the user. The pointer should never be null.</p>


<p>Definition at line 53 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/remarks/remarkparser-h">RemarkParser.h</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/structs/llvm/remarks/remarklinker/#ac548aeb7853ce7d7cd2a3b33fb761d1b">llvm::remarks::RemarkLinker::link</a> and <a href="/web-llvm/docs/api/groups/llvmcremarks/#gada1d7ab2d57b735d67fa095bc099cc7f">LLVMRemarkParserGetNext</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Public Member Attributes

### ExternalFilePrependPath {#a1458e6f0ecbddf1a241415d5542dfa2c}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">std::string llvm::remarks::RemarkParser::ExternalFilePrependPath</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Path to prepend when opening an external remark file.</p>

<p>Definition at line 44 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/remarks/remarkparser-h">RemarkParser.h</a>.</p>

</div>
</div>

### ParserFormat {#aa8ed51750beb4e4042b8aed388f749d9}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">Format llvm::remarks::RemarkParser::ParserFormat</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>The format of the parser.</p>

<p>Definition at line 42 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/remarks/remarkparser-h">RemarkParser.h</a>.</p>


<p>Referenced by <a href="#a6030e67087fde04ece4556c929c0d42d">RemarkParser</a>.</p>

</div>
</div>

</div>

<hr/>

The documentation for this struct was generated from the following file:

<ul>
<li><a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/remarks/remarkparser-h">RemarkParser.h</a></li>
</ul>

<hr/>

<p class="doxyGeneratedBy">Generated via <a href="https://github.com/xpack/doxygen2docusaurus">doxygen2docusaurus</a> by <a href="https://www.doxygen.nl">Doxygen</a> 1.15.0.</p>

</div>
