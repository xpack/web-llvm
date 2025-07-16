---

# DO NOT EDIT!
# Automatically generated via doxygen2docusaurus by Doxygen.

slug: /api/classes/llvm/yaml/stream
custom_edit_url: null
toc_max_heading_level: 4
keywords:
  - doxygen
  - reference
  - class

---

<div class="doxyPage">

# The `Stream` Class Reference

<p>This class represents a YAML stream potentially containing multiple documents. <a href="#details">More...</a></p>

## Declaration

<div class="doxyDeclaration">
class llvm::yaml::Stream { ... }
</div>

## Included Headers

<div class="doxyIncludesList">#include "<a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/support/yamlparser-h">llvm/Support/YAMLParser.h</a>"
</div>

## Friends Index

<table class="doxyMembersIndex">

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">class</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a883538034e58fc5c0de7d4e4cab3cef7">Document</a></td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a81f32d7292abb241f01ff42afae94fb0">Stream</a> (StringRef Input, SourceMgr &amp;, bool ShowColors=true, std::error_code *EC=nullptr)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>This keeps a reference to the string referenced by <span class="doxyComputerOutput"><a href="/web-llvm/docs/api/classes/llvm/yaml/input">Input</a></span>. <a href="#a81f32d7292abb241f01ff42afae94fb0">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a2dd8df0455bfe6fa9abe2a853e690806">Stream</a> (MemoryBufferRef InputBuffer, SourceMgr &amp;, bool ShowColors=true, std::error_code *EC=nullptr)</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a6dc4517a9e6a87abb662fcd14c2ea969">~Stream</a> ()</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/yaml/document-iterator">document_iterator</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a28a9f3738483f46eb7087f114ec3c074">begin</a> ()</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/yaml/document-iterator">document_iterator</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a19ac1ea26f1dc39bc0922145ebc30ed3">end</a> ()</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#af2acd5606c7ff8246f7b934f0b26e44d">skip</a> ()</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a82d94fbcfe1fb093c3950debd670ab5b">failed</a> ()</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a056bb79cd0db023f1b76455543f166f0">validate</a> ()</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ab14d4901b18c31b9707f2ea52d0f82f0">printError</a> (Node *N, const Twine &amp;Msg, SourceMgr::DiagKind Kind=SourceMgr::DK_Error)</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#aa25720e4929269e0bd11425ca4f00b32">printError</a> (const SMRange &amp;Range, const Twine &amp;Msg, SourceMgr::DiagKind Kind=SourceMgr::DK_Error)</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">std::unique_ptr&lt; <a href="/web-llvm/docs/api/classes/llvm/yaml/scanner">Scanner</a> &gt;</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a8c9e044cd1ec196065484286b9c630f8">scanner</a></td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">std::unique_ptr&lt; <a href="/web-llvm/docs/api/classes/llvm/yaml/document">Document</a> &gt;</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#afc6293489ba748924422080fd4409872">CurrentDoc</a></td>
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

<p>This class represents a YAML stream potentially containing multiple documents.</p>

<p>Definition at line 86 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/support/yamlparser-h">YAMLParser.h</a>.</p>


<div class="doxySectionDef">

## Friends

### Document {#a883538034e58fc5c0de7d4e4cab3cef7}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">friend class <a href="/web-llvm/docs/api/classes/llvm/yaml/document">Document</a></td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">


<p>Definition at line 112 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/support/yamlparser-h">YAMLParser.h</a>.</p>


<p>Reference <a href="#a883538034e58fc5c0de7d4e4cab3cef7">Document</a>.</p>


<p>Referenced by <a href="#a28a9f3738483f46eb7087f114ec3c074">begin</a>, <a href="#a883538034e58fc5c0de7d4e4cab3cef7">Document</a> and <a href="#af2acd5606c7ff8246f7b934f0b26e44d">skip</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Public Constructors

### Stream() {#a81f32d7292abb241f01ff42afae94fb0}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">Stream::Stream (<a href="/web-llvm/docs/api/classes/llvm/stringref">StringRef</a> Input, <a href="/web-llvm/docs/api/classes/llvm/sourcemgr">SourceMgr</a> &amp; SM, bool ShowColors=<a href="/web-llvm/docs/api/files/lib/lib/analysis/basicaliasanalysis-cpp/#af6d5cafbdfc5313e65d990120021a3ec">true</a>, std::error_code * EC=nullptr)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>This keeps a reference to the string referenced by <span class="doxyComputerOutput"><a href="/web-llvm/docs/api/classes/llvm/yaml/input">Input</a></span>.</p>

<p>Declaration at line 89 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/support/yamlparser-h">YAMLParser.h</a>, definition at line 1914 of file <a href="/web-llvm/docs/api/files/lib/lib/support/yamlparser-cpp">YAMLParser.cpp</a>.</p>

</div>
</div>

### Stream() {#a2dd8df0455bfe6fa9abe2a853e690806}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">Stream::Stream (<a href="/web-llvm/docs/api/classes/llvm/memorybufferref">MemoryBufferRef</a> InputBuffer, <a href="/web-llvm/docs/api/classes/llvm/sourcemgr">SourceMgr</a> &amp; SM, bool ShowColors=<a href="/web-llvm/docs/api/files/lib/lib/analysis/basicaliasanalysis-cpp/#af6d5cafbdfc5313e65d990120021a3ec">true</a>, std::error_code * EC=nullptr)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Declaration at line 92 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/support/yamlparser-h">YAMLParser.h</a>, definition at line 1918 of file <a href="/web-llvm/docs/api/files/lib/lib/support/yamlparser-cpp">YAMLParser.cpp</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Public Destructor

### \~Stream() {#a6dc4517a9e6a87abb662fcd14c2ea969}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">Stream::~Stream ()</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 94 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/support/yamlparser-h">YAMLParser.h</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Public Member Functions

### begin() {#a28a9f3738483f46eb7087f114ec3c074}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">document_iterator Stream::begin ()</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Declaration at line 96 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/support/yamlparser-h">YAMLParser.h</a>, definition at line 1935 of file <a href="/web-llvm/docs/api/files/lib/lib/support/yamlparser-cpp">YAMLParser.cpp</a>.</p>


<p>References <a href="#a883538034e58fc5c0de7d4e4cab3cef7">Document</a> and <a href="/web-llvm/docs/api/namespaces/llvm/#a7f2a3d4dcfee70225988aec53ff1e173">llvm::report_fatal_error</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/classes/llvm/vfs/redirectingfilesystem/#a9f274211d8e2baf7f13ec1e030e09de6">llvm::vfs::RedirectingFileSystem::create</a>.</p>

</div>
</div>

### end() {#a19ac1ea26f1dc39bc0922145ebc30ed3}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">document_iterator Stream::end ()</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Declaration at line 97 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/support/yamlparser-h">YAMLParser.h</a>, definition at line 1946 of file <a href="/web-llvm/docs/api/files/lib/lib/support/yamlparser-cpp">YAMLParser.cpp</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/classes/llvm/vfs/redirectingfilesystem/#a9f274211d8e2baf7f13ec1e030e09de6">llvm::vfs::RedirectingFileSystem::create</a>.</p>

</div>
</div>

### failed() {#a82d94fbcfe1fb093c3950debd670ab5b}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool Stream::failed ()</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Declaration at line 99 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/support/yamlparser-h">YAMLParser.h</a>, definition at line 1924 of file <a href="/web-llvm/docs/api/files/lib/lib/support/yamlparser-cpp">YAMLParser.cpp</a>.</p>


<p>Referenced by <a href="#a056bb79cd0db023f1b76455543f166f0">validate</a>.</p>

</div>
</div>

### printError() {#ab14d4901b18c31b9707f2ea52d0f82f0}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void Stream::printError (<a href="/web-llvm/docs/api/classes/llvm/yaml/node">Node</a> * N, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/twine">Twine</a> &amp; Msg, <a href="/web-llvm/docs/api/classes/llvm/sourcemgr/#a346262ff27e71aff626fe6548ef8a777">SourceMgr::DiagKind</a> Kind=<a href="/web-llvm/docs/api/classes/llvm/sourcemgr/#a346262ff27e71aff626fe6548ef8a777adaf658d40b0b4eb15c0350864c87c2b8">SourceMgr::DK_Error</a>)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Declaration at line 106 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/support/yamlparser-h">YAMLParser.h</a>, definition at line 1926 of file <a href="/web-llvm/docs/api/files/lib/lib/support/yamlparser-cpp">YAMLParser.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/files/lib/lib/support/regcomp-c/#a0240ac851181b84ac374872dc5434ee4">N</a> and <a href="#ab14d4901b18c31b9707f2ea52d0f82f0">printError</a>.</p>


<p>Referenced by <a href="#ab14d4901b18c31b9707f2ea52d0f82f0">printError</a> and <a href="/web-llvm/docs/api/classes/llvm/remarks/yamlparseerror/#aee75e19211cebf7bf53859a98bd5ac61">llvm::remarks::YAMLParseError::YAMLParseError</a>.</p>

</div>
</div>

### printError() {#aa25720e4929269e0bd11425ca4f00b32}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void Stream::printError (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/smrange">SMRange</a> &amp; Range, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/twine">Twine</a> &amp; Msg, <a href="/web-llvm/docs/api/classes/llvm/sourcemgr/#a346262ff27e71aff626fe6548ef8a777">SourceMgr::DiagKind</a> Kind=<a href="/web-llvm/docs/api/classes/llvm/sourcemgr/#a346262ff27e71aff626fe6548ef8a777adaf658d40b0b4eb15c0350864c87c2b8">SourceMgr::DK_Error</a>)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Declaration at line 108 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/support/yamlparser-h">YAMLParser.h</a>, definition at line 1930 of file <a href="/web-llvm/docs/api/files/lib/lib/support/yamlparser-cpp">YAMLParser.cpp</a>.</p>


<p>Reference <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/nvptx/nvvmintrrange-cpp/#a34bd74317e3f04bfc4318c2d1a470877">Range</a>.</p>

</div>
</div>

### skip() {#af2acd5606c7ff8246f7b934f0b26e44d}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void Stream::skip ()</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Declaration at line 98 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/support/yamlparser-h">YAMLParser.h</a>, definition at line 1950 of file <a href="/web-llvm/docs/api/files/lib/lib/support/yamlparser-cpp">YAMLParser.cpp</a>.</p>


<p>References <a href="#a883538034e58fc5c0de7d4e4cab3cef7">Document</a> and <a href="/web-llvm/docs/api/classes/llvm/yaml/document/#a3cb9cf1d6e2fa720e8c93f46648200e9">llvm::yaml::Document::skip</a>.</p>


<p>Referenced by <a href="#a056bb79cd0db023f1b76455543f166f0">validate</a>.</p>

</div>
</div>

### validate() {#a056bb79cd0db023f1b76455543f166f0}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool llvm::yaml::Stream::validate ()</td>
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



<p>Definition at line 101 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/support/yamlparser-h">YAMLParser.h</a>.</p>


<p>References <a href="#a82d94fbcfe1fb093c3950debd670ab5b">failed</a> and <a href="#af2acd5606c7ff8246f7b934f0b26e44d">skip</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Private Member Attributes

### CurrentDoc {#afc6293489ba748924422080fd4409872}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">std::unique_ptr&lt;Document&gt; llvm::yaml::Stream::CurrentDoc</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 115 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/support/yamlparser-h">YAMLParser.h</a>.</p>

</div>
</div>

### scanner {#a8c9e044cd1ec196065484286b9c630f8}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">std::unique_ptr&lt;Scanner&gt; llvm::yaml::Stream::scanner</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 114 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/support/yamlparser-h">YAMLParser.h</a>.</p>

</div>
</div>

</div>

<hr/>

The documentation for this class was generated from the following files:

<ul>
<li><a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/support/yamlparser-h">YAMLParser.h</a></li>
<li><a href="/web-llvm/docs/api/files/lib/lib/support/yamlparser-cpp">YAMLParser.cpp</a></li>
</ul>

<hr/>

<p class="doxyGeneratedBy">Generated via <a href="https://github.com/xpack/doxygen2docusaurus">doxygen2docusaurus</a> by <a href="https://www.doxygen.nl">Doxygen</a> 1.15.0.</p>

</div>
