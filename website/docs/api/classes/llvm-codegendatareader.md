---

# DO NOT EDIT!
# Automatically generated via doxygen2docusaurus by Doxygen.

slug: /api/classes/llvm/codegendatareader
custom_edit_url: null
toc_max_heading_level: 4
keywords:
  - doxygen
  - reference
  - class

---

<div class="doxyPage">

# `CodeGenDataReader` Class



## Declaration

<div class="doxyDeclaration">
class llvm::CodeGenDataReader { ... }
</div>

## Included Headers

<div class="doxyIncludesList">#include "<a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/cgdata/codegendatareader-h">llvm/CGData/CodeGenDataReader.h</a>"
</div>

## Derived Classes

<table class="doxyMembersIndex">

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">class</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/indexedcodegendatareader">IndexedCodeGenDataReader</a></td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">class</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/textcodegendatareader">TextCodeGenDataReader</a></td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>This format is a simple text format that's suitable for test data. <a href="/web-llvm/docs/api/classes/llvm/textcodegendatareader/#details">More...</a></p>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a4938a6e9b87fda35e4f530f2e7131a6a">CodeGenDataReader</a> ()=default</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a25c012e7b2b088babfa4effb8b594235">~CodeGenDataReader</a> ()=default</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#aa20fa4c4ea01f7b1432d0b99deb1c691">read</a> ()=0</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Read the header. Required before reading first record. <a href="#aa20fa4c4ea01f7b1432d0b99deb1c691">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">uint32_t</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a386744755a9d21a971e5087e05199c10">getVersion</a> () const =0</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Return the codegen data version. <a href="#a386744755a9d21a971e5087e05199c10">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/namespaces/llvm/#a0ba893e7dc00f439ef557e79f12e899f">CGDataKind</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a8cea1e14735c7e639093889ef58d358c">getDataKind</a> () const =0</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Return the codegen data kind. <a href="#a8cea1e14735c7e639093889ef58d358c">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">bool</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a1952f67f7a36cf1438bb35532e2c9681">hasOutlinedHashTree</a> () const =0</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Return true if the data has an outlined hash tree. <a href="#a1952f67f7a36cf1438bb35532e2c9681">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">bool</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a340784b8d4d214561c2e4115e7796d97">hasStableFunctionMap</a> () const =0</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Return true if the data has a stable function map. <a href="#a340784b8d4d214561c2e4115e7796d97">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">std::unique_ptr&lt; <a href="/web-llvm/docs/api/classes/llvm/outlinedhashtree">OutlinedHashTree</a> &gt;</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ad418978423ac3f031d4a4aab04708310">releaseOutlinedHashTree</a> ()</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Return the outlined hash tree that is released from the reader. <a href="#ad418978423ac3f031d4a4aab04708310">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">std::unique_ptr&lt; <a href="/web-llvm/docs/api/structs/llvm/stablefunctionmap">StableFunctionMap</a> &gt;</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a50647452c64c1fab25b232c4827ccd2b">releaseStableFunctionMap</a> ()</td>
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

## Protected Member Functions Index

<table class="doxyMembersIndex">

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/error">Error</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a4d9d859b066e0d93458a74c4763cf553">error</a> (cgdata_error Err, const std::string &amp;ErrMsg="")</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Set the current error and return same. <a href="#a4d9d859b066e0d93458a74c4763cf553">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/error">Error</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#aa674edf94147d4f7be423bcb307ab377">error</a> (Error &amp;&amp;E)</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/error">Error</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a1ef2fb8f19fa17d3e0445cc0f00b8a9a">success</a> ()</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Clear the current error and return a successful one. <a href="#a1ef2fb8f19fa17d3e0445cc0f00b8a9a">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

</table>

## Protected Member Attributes Index

<table class="doxyMembersIndex">

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/structs/llvm/outlinedhashtreerecord">OutlinedHashTreeRecord</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a3897d2b4576b899d566186c2a97a7a79">HashTreeRecord</a></td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>The outlined hash tree that has been read. <a href="#a3897d2b4576b899d566186c2a97a7a79">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/structs/llvm/stablefunctionmaprecord">StableFunctionMapRecord</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a83f3e8474f7cca254a19d876f2e9a3b7">FunctionMapRecord</a></td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>The stable function map that has been read. When it's released by. <a href="#a83f3e8474f7cca254a19d876f2e9a3b7">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

</table>

## Private Member Attributes Index

<table class="doxyMembersIndex">

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/namespaces/llvm/#a6ea6fb3a4e8248113053829b7fd89c96">cgdata_error</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a7c4ba6ccf58e5a5fa45201d104e292df">LastError</a> = <a href="/web-llvm/docs/api/namespaces/llvm/#a6ea6fb3a4e8248113053829b7fd89c96a260ca9dd8a4577fc00b7bd5810298076">cgdata_error::success</a></td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">std::string</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a799df984e412f88b0176674d7dd6b7c2">LastErrorMsg</a></td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">static <a href="/web-llvm/docs/api/classes/llvm/expected">Expected</a>&lt; std::unique_ptr&lt; <a href="/web-llvm/docs/api/classes/llvm/codegendatareader">CodeGenDataReader</a> &gt; &gt;</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a4a44372ad9be897766236ba844f560e5">create</a> (const Twine &amp;Path, vfs::FileSystem &amp;FS)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Factory method to create an appropriately typed reader for the given codegen data file path and file system. <a href="#a4a44372ad9be897766236ba844f560e5">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">static <a href="/web-llvm/docs/api/classes/llvm/expected">Expected</a>&lt; std::unique_ptr&lt; <a href="/web-llvm/docs/api/classes/llvm/codegendatareader">CodeGenDataReader</a> &gt; &gt;</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a378e68eccfba5cca99d032743ec74ad1">create</a> (std::unique_ptr&lt; MemoryBuffer &gt; Buffer)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Factory method to create an appropriately typed reader for the given memory buffer. <a href="#a378e68eccfba5cca99d032743ec74ad1">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">static <a href="/web-llvm/docs/api/classes/llvm/error">Error</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ad41848e26234890d2d908a09f6709022">mergeFromObjectFile</a> (const object::ObjectFile *Obj, OutlinedHashTreeRecord &amp;GlobalOutlineRecord, StableFunctionMapRecord &amp;GlobalFunctionMapRecord, stable_hash *CombinedHash=nullptr)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Extract the cgdata embedded in sections from the given object file and merge them into the GlobalOutlineRecord. <a href="#ad41848e26234890d2d908a09f6709022">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

</table>


<p>Definition at line 24 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/cgdata/codegendatareader-h">CodeGenDataReader.h</a>.</p>


<div class="doxySectionDef">

## Public Constructors

### CodeGenDataReader() {#a4938a6e9b87fda35e4f530f2e7131a6a}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">llvm::CodeGenDataReader::CodeGenDataReader ()</td>
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



<p>Definition at line 29 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/cgdata/codegendatareader-h">CodeGenDataReader.h</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Public Destructor

### \~CodeGenDataReader() {#a25c012e7b2b088babfa4effb8b594235}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">virtual llvm::CodeGenDataReader::~CodeGenDataReader ()</td>
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



<p>Definition at line 30 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/cgdata/codegendatareader-h">CodeGenDataReader.h</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Public Member Functions

### getDataKind() {#a8cea1e14735c7e639093889ef58d358c}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">virtual CGDataKind llvm::CodeGenDataReader::getDataKind ()</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Return the codegen data kind.</p>

<p>Definition at line 37 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/cgdata/codegendatareader-h">CodeGenDataReader.h</a>.</p>

</div>
</div>

### getVersion() {#a386744755a9d21a971e5087e05199c10}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">virtual uint32_t llvm::CodeGenDataReader::getVersion ()</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Return the codegen data version.</p>

<p>Definition at line 35 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/cgdata/codegendatareader-h">CodeGenDataReader.h</a>.</p>

</div>
</div>

### hasOutlinedHashTree() {#a1952f67f7a36cf1438bb35532e2c9681}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">virtual bool llvm::CodeGenDataReader::hasOutlinedHashTree ()</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Return true if the data has an outlined hash tree.</p>

<p>Definition at line 39 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/cgdata/codegendatareader-h">CodeGenDataReader.h</a>.</p>

</div>
</div>

### hasStableFunctionMap() {#a340784b8d4d214561c2e4115e7796d97}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">virtual bool llvm::CodeGenDataReader::hasStableFunctionMap ()</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Return true if the data has a stable function map.</p>

<p>Definition at line 41 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/cgdata/codegendatareader-h">CodeGenDataReader.h</a>.</p>

</div>
</div>

### read() {#aa20fa4c4ea01f7b1432d0b99deb1c691}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">virtual Error llvm::CodeGenDataReader::read ()</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Read the header. Required before reading first record.</p>

<p>Definition at line 33 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/cgdata/codegendatareader-h">CodeGenDataReader.h</a>.</p>

</div>
</div>

### releaseOutlinedHashTree() {#ad418978423ac3f031d4a4aab04708310}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">std::unique_ptr&lt; OutlinedHashTree &gt; llvm::CodeGenDataReader::releaseOutlinedHashTree ()</td>
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

<p>Return the outlined hash tree that is released from the reader.</p>

<p>Definition at line 43 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/cgdata/codegendatareader-h">CodeGenDataReader.h</a>.</p>


<p>Reference <a href="#a3897d2b4576b899d566186c2a97a7a79">HashTreeRecord</a>.</p>

</div>
</div>

### releaseStableFunctionMap() {#a50647452c64c1fab25b232c4827ccd2b}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">std::unique_ptr&lt; StableFunctionMap &gt; llvm::CodeGenDataReader::releaseStableFunctionMap ()</td>
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



<p>Definition at line 46 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/cgdata/codegendatareader-h">CodeGenDataReader.h</a>.</p>


<p>Reference <a href="#a83f3e8474f7cca254a19d876f2e9a3b7">FunctionMapRecord</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Protected Member Functions

### error() {#a4d9d859b066e0d93458a74c4763cf553}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">Error llvm::CodeGenDataReader::error (<a href="/web-llvm/docs/api/namespaces/llvm/#a6ea6fb3a4e8248113053829b7fd89c96">cgdata_error</a> Err, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> std::string &amp; ErrMsg="")</td>
</tr>
</table>
</td>
<td class="doxyMemberLabelsRight">
<span class="doxyMemberLabels">
<span class="doxyMemberLabel inline">inline</span>
<span class="doxyMemberLabel protected">protected</span>
</span>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Set the current error and return same.</p>

<p>Definition at line 81 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/cgdata/codegendatareader-h">CodeGenDataReader.h</a>.</p>


<p>References <a href="/web-llvm/docs/api/namespaces/llvm/#a9999bd897fc8a1648bd69b36fee2d357">llvm::make_error</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a6ea6fb3a4e8248113053829b7fd89c96a260ca9dd8a4577fc00b7bd5810298076">llvm::success</a> and <a href="/web-llvm/docs/api/classes/llvm/error/#a4dfd0813c3d0e0a30439b5a3e9196b59">llvm::Error::success</a>.</p>

</div>
</div>

### error() {#aa674edf94147d4f7be423bcb307ab377}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">Error llvm::CodeGenDataReader::error (<a href="/web-llvm/docs/api/classes/llvm/error">Error</a> &amp;&amp; E)</td>
</tr>
</table>
</td>
<td class="doxyMemberLabelsRight">
<span class="doxyMemberLabels">
<span class="doxyMemberLabel inline">inline</span>
<span class="doxyMemberLabel protected">protected</span>
</span>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 89 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/cgdata/codegendatareader-h">CodeGenDataReader.h</a>.</p>


<p>References <a href="/web-llvm/docs/api/files/lib/lib/ir/builtingcs-cpp/#abb2b3a60ccc38a28239e19a1646e0c8a">E</a>, <a href="/web-llvm/docs/api/classes/llvm/cgdataerror/#af723597667ca015a380525ed878859b9">llvm::CGDataError::get</a>, <a href="/web-llvm/docs/api/classes/llvm/cgdataerror/#a1990c5de7fed9ac92508512f4328580f">llvm::CGDataError::getMessage</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a2aa0f5c36ac6291f5d5f2b4efd9ffe70">llvm::handleAllErrors</a> and <a href="/web-llvm/docs/api/namespaces/llvm/#a9999bd897fc8a1648bd69b36fee2d357">llvm::make_error</a>.</p>

</div>
</div>

### success() {#a1ef2fb8f19fa17d3e0445cc0f00b8a9a}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">Error llvm::CodeGenDataReader::success ()</td>
</tr>
</table>
</td>
<td class="doxyMemberLabelsRight">
<span class="doxyMemberLabels">
<span class="doxyMemberLabel inline">inline</span>
<span class="doxyMemberLabel protected">protected</span>
</span>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Clear the current error and return a successful one.</p>

<p>Definition at line 98 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/cgdata/codegendatareader-h">CodeGenDataReader.h</a>.</p>


<p>References <a href="/web-llvm/docs/api/files/lib/lib/debuginfo/lib/debuginfo/codeview/symbolrecordmapping-cpp/#a9cdf893c7d17e47fa1ed8bebf92a5da4">error</a> and <a href="/web-llvm/docs/api/namespaces/llvm/#a6ea6fb3a4e8248113053829b7fd89c96a260ca9dd8a4577fc00b7bd5810298076">llvm::success</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/classes/llvm/indexedcodegendatareader/#a3f022987ea846df57d06f91074954335">llvm::IndexedCodeGenDataReader::read</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Protected Member Attributes

### FunctionMapRecord {#a83f3e8474f7cca254a19d876f2e9a3b7}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">StableFunctionMapRecord llvm::CodeGenDataReader::FunctionMapRecord</td>
</tr>
</table>
</td>
<td class="doxyMemberLabelsRight">
<span class="doxyMemberLabels">
<span class="doxyMemberLabel protected">protected</span>
</span>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>The stable function map that has been read. When it's released by.</p>

<p>Definition at line 78 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/cgdata/codegendatareader-h">CodeGenDataReader.h</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/classes/llvm/indexedcodegendatareader/#a3f022987ea846df57d06f91074954335">llvm::IndexedCodeGenDataReader::read</a>, <a href="/web-llvm/docs/api/classes/llvm/textcodegendatareader/#a6a6f3695c97c301eee0369ec5e669c61">llvm::TextCodeGenDataReader::read</a> and <a href="#a50647452c64c1fab25b232c4827ccd2b">releaseStableFunctionMap</a>.</p>

</div>
</div>

### HashTreeRecord {#a3897d2b4576b899d566186c2a97a7a79}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">OutlinedHashTreeRecord llvm::CodeGenDataReader::HashTreeRecord</td>
</tr>
</table>
</td>
<td class="doxyMemberLabelsRight">
<span class="doxyMemberLabels">
<span class="doxyMemberLabel protected">protected</span>
</span>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>The outlined hash tree that has been read.</p>


<p>When it's released by <a href="#ad418978423ac3f031d4a4aab04708310">releaseOutlinedHashTree()</a>, it's no longer valid.</p>


<p>Definition at line 74 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/cgdata/codegendatareader-h">CodeGenDataReader.h</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/classes/llvm/indexedcodegendatareader/#a3f022987ea846df57d06f91074954335">llvm::IndexedCodeGenDataReader::read</a>, <a href="/web-llvm/docs/api/classes/llvm/textcodegendatareader/#a6a6f3695c97c301eee0369ec5e669c61">llvm::TextCodeGenDataReader::read</a> and <a href="#ad418978423ac3f031d4a4aab04708310">releaseOutlinedHashTree</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Private Member Attributes

### LastError {#a7c4ba6ccf58e5a5fa45201d104e292df}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">cgdata_error llvm::CodeGenDataReader::LastError = <a href="/web-llvm/docs/api/namespaces/llvm/#a6ea6fb3a4e8248113053829b7fd89c96a260ca9dd8a4577fc00b7bd5810298076">cgdata_error::success</a></td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 25 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/cgdata/codegendatareader-h">CodeGenDataReader.h</a>.</p>

</div>
</div>

### LastErrorMsg {#a799df984e412f88b0176674d7dd6b7c2}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">std::string llvm::CodeGenDataReader::LastErrorMsg</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 26 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/cgdata/codegendatareader-h">CodeGenDataReader.h</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Public Static Functions

### create() {#a4a44372ad9be897766236ba844f560e5}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">Expected&lt; std::unique_ptr&lt; CodeGenDataReader &gt; &gt; llvm::CodeGenDataReader::create (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/twine">Twine</a> &amp; Path, <a href="/web-llvm/docs/api/classes/llvm/vfs/filesystem">vfs::FileSystem</a> &amp; FS)</td>
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

<p>Factory method to create an appropriately typed reader for the given codegen data file path and file system.</p>

<p>Declaration at line 53 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/cgdata/codegendatareader-h">CodeGenDataReader.h</a>, definition at line 116 of file <a href="/web-llvm/docs/api/files/lib/lib/cgdata/codegendatareader-cpp">CodeGenDataReader.cpp</a>.</p>


<p>References <a href="#a4a44372ad9be897766236ba844f560e5">create</a> and <a href="/web-llvm/docs/api/namespaces/llvm/#a0c339cfce77238670cd7657a636f4303">llvm::setupMemoryBuffer</a>.</p>


<p>Referenced by <a href="#a4a44372ad9be897766236ba844f560e5">create</a> and <a href="/web-llvm/docs/api/classes/llvm/codegendata/#af860defbaa2aa3a19cd8e5ef4edb5aed">llvm::CodeGenData::getInstance</a>.</p>

</div>
</div>

### create() {#a378e68eccfba5cca99d032743ec74ad1}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">Expected&lt; std::unique_ptr&lt; CodeGenDataReader &gt; &gt; llvm::CodeGenDataReader::create (std::unique_ptr&lt; <a href="/web-llvm/docs/api/classes/llvm/memorybuffer">MemoryBuffer</a> &gt; Buffer)</td>
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

<p>Factory method to create an appropriately typed reader for the given memory buffer.</p>

<p>Declaration at line 58 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/cgdata/codegendatareader-h">CodeGenDataReader.h</a>, definition at line 125 of file <a href="/web-llvm/docs/api/files/lib/lib/cgdata/codegendatareader-cpp">CodeGenDataReader.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/namespaces/llvm/#a6ea6fb3a4e8248113053829b7fd89c96a7fa280f7e48ee78c16e6ceec49532736">llvm::empty_cgdata</a>, <a href="/web-llvm/docs/api/classes/llvm/indexedcodegendatareader/#a3d830a3c802045bb715c15756112ab48">llvm::IndexedCodeGenDataReader::hasFormat</a>, <a href="/web-llvm/docs/api/classes/llvm/textcodegendatareader/#a0199559e6f0464acf4c2c30bcb041a03">llvm::TextCodeGenDataReader::hasFormat</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a9999bd897fc8a1648bd69b36fee2d357">llvm::make_error</a> and <a href="/web-llvm/docs/api/namespaces/llvm/#a6ea6fb3a4e8248113053829b7fd89c96a7596fdd04dba990373ab2f3da0c7dd3f">llvm::malformed</a>.</p>

</div>
</div>

### mergeFromObjectFile() {#ad41848e26234890d2d908a09f6709022}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">Error llvm::CodeGenDataReader::mergeFromObjectFile (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/object/objectfile">object::ObjectFile</a> * Obj, <a href="/web-llvm/docs/api/structs/llvm/outlinedhashtreerecord">OutlinedHashTreeRecord</a> &amp; GlobalOutlineRecord, <a href="/web-llvm/docs/api/structs/llvm/stablefunctionmaprecord">StableFunctionMapRecord</a> &amp; GlobalFunctionMapRecord, <a href="/web-llvm/docs/api/namespaces/llvm/#a3f07bd5ee30b6a57ddc214f64d5fd941">stable_hash</a> * CombinedHash=nullptr)</td>
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

<p>Extract the cgdata embedded in sections from the given object file and merge them into the GlobalOutlineRecord.</p>


<p>This is a static helper that is used by <span class="doxyComputerOutput">llvm-cgdata --merge</span> or ThinLTO's two-codegen rounds. Optionally, <span class="doxyComputerOutput">CombinedHash</span> can be used to compuate the combined hash of the merged data.</p>


<p>Declaration at line 66 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/cgdata/codegendatareader-h">CodeGenDataReader.h</a>, definition at line 33 of file <a href="/web-llvm/docs/api/files/lib/lib/cgdata/codegendatareader-cpp">CodeGenDataReader.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/namespaces/llvm/#aa20539e89704d20b98b97e9c3feac934">llvm::Data</a>, <a href="/web-llvm/docs/api/structs/llvm/outlinedhashtreerecord/#a2c9fcdfa14dafa4bf635b6bdd88e0c77">llvm::OutlinedHashTreeRecord::deserialize</a>, <a href="/web-llvm/docs/api/structs/llvm/stablefunctionmaprecord/#a46fcb6ab7d4a17276796efb4fd9ef091">llvm::StableFunctionMapRecord::deserialize</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#aff79775a78397e420bbe8bbed80f2a21">llvm::getCodeGenDataSectionName</a>, <a href="/web-llvm/docs/api/classes/llvm/object/objectfile/#a6f6cda42b5be79b59179a5ca1a3e7bfa">llvm::object::ObjectFile::makeTriple</a>, <a href="/web-llvm/docs/api/structs/llvm/outlinedhashtreerecord/#ab4486d597859e5cabe3b4a691a4bb5ee">llvm::OutlinedHashTreeRecord::merge</a>, <a href="/web-llvm/docs/api/structs/llvm/stablefunctionmaprecord/#a0621093b5be0060d05b4dd5336611229">llvm::StableFunctionMapRecord::merge</a>, <a href="/web-llvm/docs/api/classes/llvm/object/objectfile/#a7f73649118e365a230be4870d824e7cf">llvm::object::ObjectFile::sections</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#ae12d768edcecd309ab9fa48c23f9bc07">llvm::stable_hash_combine</a>, <a href="/web-llvm/docs/api/classes/llvm/error/#a4dfd0813c3d0e0a30439b5a3e9196b59">llvm::Error::success</a>, <a href="/web-llvm/docs/api/classes/llvm/expected/#a94789df4ebd03dc008e8adebaa66ac1f">llvm::Expected&lt; T &gt;::takeError</a> and <a href="/web-llvm/docs/api/namespaces/llvm/#a23db35042db15bf83edbd2250ea0ee90">llvm::xxh3_64bits</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/namespaces/llvm/cgdata/#a05b4c070c172287759f5f2f437a3edcb">llvm::cgdata::mergeCodeGenData</a>.</p>

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
