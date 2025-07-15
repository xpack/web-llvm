---

# DO NOT EDIT!
# Automatically generated via doxygen2docusaurus by Doxygen.

slug: /api/classes/llvm/object/windowsresourceparser
custom_edit_url: null
toc_max_heading_level: 4
keywords:
  - doxygen
  - reference
  - class

---

<div class="doxyPage">

# The `WindowsResourceParser` Class Reference



## Declaration

<div class="doxyDeclaration">
class llvm::object::WindowsResourceParser { ... }
</div>

## Included Headers

<div class="doxyIncludesList">#include "<a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/object/windowsresource-h">llvm/Object/WindowsResource.h</a>"
</div>

## Public Constructors Index

<table class="doxyMembersIndex">

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a968c5d82069e7e3d6919529c4f2a0d83">WindowsResourceParser</a> (bool MinGW=false)</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#aedf8841ba3ea93fe05f71cf444cc18fd">parse</a> (WindowsResource *WR, std::vector&lt; std::string &gt; &amp;Duplicates)</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a5014ccfe2c08a9cca427af5185064957">parse</a> (ResourceSectionRef &amp;RSR, StringRef Filename, std::vector&lt; std::string &gt; &amp;Duplicates)</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a6b6882518203485e179f0d2ee1c25b07">cleanUpManifests</a> (std::vector&lt; std::string &gt; &amp;Duplicates)</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a88f4b60ff3c62c302ad70681dfc6264b">printTree</a> (raw_ostream &amp;OS) const</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/object/windowsresourceparser/treenode">TreeNode</a> &amp;</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a84752290bd2523d560e7807a34c0c79d">getTree</a> () const</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/arrayref">ArrayRef</a>&lt; std::vector&lt; uint8_t &gt; &gt;</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a92151fdb6cc51a6e93a30edeb41fd9f1">getData</a> () const</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/arrayref">ArrayRef</a>&lt; std::vector&lt; <a href="/web-llvm/docs/api/namespaces/llvm/#a17701f48ffa18ce5f16797db84617db2">UTF16</a> &gt; &gt;</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ade7fbd94611fd331a73d4300f8815f3c">getStringTable</a> () const</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/error">Error</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a6ab58dfd6242c950e70db139bc349430">addChildren</a> (TreeNode &amp;Node, ResourceSectionRef &amp;RSR, const coff_resource_dir_table &amp;Table, uint32_t Origin, std::vector&lt; StringOrID &gt; &amp;Context, std::vector&lt; std::string &gt; &amp;Duplicates)</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a688d0a23e2db5ce38a06a131de5273cf">shouldIgnoreDuplicate</a> (const ResourceEntryRef &amp;Entry) const</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ad38d3d43660e94479ff36e6a313ca6e9">shouldIgnoreDuplicate</a> (const std::vector&lt; StringOrID &gt; &amp;Context) const</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/object/windowsresourceparser/treenode">TreeNode</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a78c68ae6b2f73004c5217e4e1183061d">Root</a></td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">std::vector&lt; std::vector&lt; uint8_t &gt; &gt;</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ac828c885e1ef633b16f20b563c54a7db">Data</a></td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">std::vector&lt; std::vector&lt; <a href="/web-llvm/docs/api/namespaces/llvm/#a17701f48ffa18ce5f16797db84617db2">UTF16</a> &gt; &gt;</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ab9ced9e0030a2ff6dcd5f69241f136f8">StringTable</a></td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">std::vector&lt; std::string &gt;</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#aff33ce3a9acd0a738e5f0f187d117d0f">InputFilenames</a></td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a076f8d7a72fd13b158cba699bb067fb8">MinGW</a></td>
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


<p>Definition at line 153 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/object/windowsresource-h">WindowsResource.h</a>.</p>


<div class="doxySectionDef">

## Public Constructors

### WindowsResourceParser() {#a968c5d82069e7e3d6919529c4f2a0d83}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">llvm::object::WindowsResourceParser::WindowsResourceParser (bool MinGW=false)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Declaration at line 156 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/object/windowsresource-h">WindowsResource.h</a>, definition at line 139 of file <a href="/web-llvm/docs/api/files/lib/lib/object/windowsresource-cpp">WindowsResource.cpp</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Public Member Functions

### cleanUpManifests() {#a6b6882518203485e179f0d2ee1c25b07}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void llvm::object::WindowsResourceParser::cleanUpManifests (std::vector&lt; std::string &gt; &amp; Duplicates)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Declaration at line 160 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/object/windowsresource-h">WindowsResource.h</a>, definition at line 262 of file <a href="/web-llvm/docs/api/files/lib/lib/object/windowsresource-cpp">WindowsResource.cpp</a>.</p>

</div>
</div>

### getData() {#a92151fdb6cc51a6e93a30edeb41fd9f1}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">ArrayRef&lt; std::vector&lt; uint8_t &gt; &gt; llvm::object::WindowsResourceParser::getData ()</td>
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



<p>Definition at line 163 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/object/windowsresource-h">WindowsResource.h</a>.</p>

</div>
</div>

### getStringTable() {#ade7fbd94611fd331a73d4300f8815f3c}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">ArrayRef&lt; std::vector&lt; UTF16 &gt; &gt; llvm::object::WindowsResourceParser::getStringTable ()</td>
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



<p>Definition at line 164 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/object/windowsresource-h">WindowsResource.h</a>.</p>

</div>
</div>

### getTree() {#a84752290bd2523d560e7807a34c0c79d}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">const TreeNode &amp; llvm::object::WindowsResourceParser::getTree ()</td>
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



<p>Definition at line 162 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/object/windowsresource-h">WindowsResource.h</a>.</p>

</div>
</div>

### parse() {#aedf8841ba3ea93fe05f71cf444cc18fd}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">Error llvm::object::WindowsResourceParser::parse (<a href="/web-llvm/docs/api/classes/llvm/object/windowsresource">WindowsResource</a> * WR, std::vector&lt; std::string &gt; &amp; Duplicates)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Declaration at line 157 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/object/windowsresource-h">WindowsResource.h</a>, definition at line 328 of file <a href="/web-llvm/docs/api/files/lib/lib/object/windowsresource-cpp">WindowsResource.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/namespaces/llvm/#aee0e70be66536b9ef7b65ae2e5a45959">llvm::consumeError</a>, <a href="/web-llvm/docs/api/classes/llvm/object/binary/#acecdb20a61e1b407af83d42e1ad9a3f3">llvm::object::Binary::getFileName</a>, <a href="/web-llvm/docs/api/classes/llvm/object/windowsresource/#a16a13836c913549f2f653d92529f1689">llvm::object::WindowsResource::getHeadEntry</a>, <a href="/web-llvm/docs/api/namespaces/llvm/object/#a46543fe277b38905b31e0d2ec607abf5">llvm::object::makeDuplicateResourceError</a>, <a href="/web-llvm/docs/api/files/lib/lib/object/coffobjectfile-cpp/#abc4d08c5ab37d6a4cbb2271772fc3ad1">RETURN_IF_ERROR</a> and <a href="/web-llvm/docs/api/classes/llvm/error/#a4dfd0813c3d0e0a30439b5a3e9196b59">llvm::Error::success</a>.</p>

</div>
</div>

### parse() {#a5014ccfe2c08a9cca427af5185064957}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">Error llvm::object::WindowsResourceParser::parse (<a href="/web-llvm/docs/api/classes/llvm/object/resourcesectionref">ResourceSectionRef</a> &amp; RSR, <a href="/web-llvm/docs/api/classes/llvm/stringref">StringRef</a> Filename, std::vector&lt; std::string &gt; &amp; Duplicates)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Declaration at line 158 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/object/windowsresource-h">WindowsResource.h</a>, definition at line 366 of file <a href="/web-llvm/docs/api/files/lib/lib/object/windowsresource-cpp">WindowsResource.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/classes/llvm/object/resourcesectionref/#a3386583baf0f3ce4a5a55e51199c6f85">llvm::object::ResourceSectionRef::getBaseTable</a> and <a href="/web-llvm/docs/api/files/lib/lib/object/windowsresource-cpp/#a9ca34930e5cebce22ac00f4e4ac7b766">UNWRAP_REF_OR_RETURN</a>.</p>

</div>
</div>

### printTree() {#a88f4b60ff3c62c302ad70681dfc6264b}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void llvm::object::WindowsResourceParser::printTree (<a href="/web-llvm/docs/api/classes/llvm/raw-ostream">raw_ostream</a> &amp; OS)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Declaration at line 161 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/object/windowsresource-h">WindowsResource.h</a>, definition at line 375 of file <a href="/web-llvm/docs/api/files/lib/lib/object/windowsresource-cpp">WindowsResource.cpp</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Private Member Functions

### addChildren() {#a6ab58dfd6242c950e70db139bc349430}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">Error llvm::object::WindowsResourceParser::addChildren (<a href="/web-llvm/docs/api/classes/llvm/object/windowsresourceparser/treenode">TreeNode</a> &amp; Node, <a href="/web-llvm/docs/api/classes/llvm/object/resourcesectionref">ResourceSectionRef</a> &amp; RSR, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/structs/llvm/object/coff-resource-dir-table">coff_resource_dir_table</a> &amp; Table, uint32_t Origin, std::vector&lt; <a href="/web-llvm/docs/api/structs/llvm/object/windowsresourceparser/stringorid">StringOrID</a> &gt; &amp; Context, std::vector&lt; std::string &gt; &amp; Duplicates)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Declaration at line 244 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/object/windowsresource-h">WindowsResource.h</a>, definition at line 389 of file <a href="/web-llvm/docs/api/files/lib/lib/object/windowsresource-cpp">WindowsResource.cpp</a>.</p>

</div>
</div>

### shouldIgnoreDuplicate() {#a688d0a23e2db5ce38a06a131de5273cf}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool llvm::object::WindowsResourceParser::shouldIgnoreDuplicate (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/object/resourceentryref">ResourceEntryRef</a> &amp; Entry)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Declaration at line 248 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/object/windowsresource-h">WindowsResource.h</a>, definition at line 311 of file <a href="/web-llvm/docs/api/files/lib/lib/object/windowsresource-cpp">WindowsResource.cpp</a>.</p>

</div>
</div>

### shouldIgnoreDuplicate() {#ad38d3d43660e94479ff36e6a313ca6e9}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool llvm::object::WindowsResourceParser::shouldIgnoreDuplicate (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> std::vector&lt; <a href="/web-llvm/docs/api/structs/llvm/object/windowsresourceparser/stringorid">StringOrID</a> &gt; &amp; Context)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Declaration at line 249 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/object/windowsresource-h">WindowsResource.h</a>, definition at line 320 of file <a href="/web-llvm/docs/api/files/lib/lib/object/windowsresource-cpp">WindowsResource.cpp</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Private Member Attributes

### Data {#ac828c885e1ef633b16f20b563c54a7db}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">std::vector&lt;std::vector&lt;uint8_t&gt; &gt; llvm::object::WindowsResourceParser::Data</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 252 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/object/windowsresource-h">WindowsResource.h</a>.</p>

</div>
</div>

### InputFilenames {#aff33ce3a9acd0a738e5f0f187d117d0f}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">std::vector&lt;std::string&gt; llvm::object::WindowsResourceParser::InputFilenames</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 255 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/object/windowsresource-h">WindowsResource.h</a>.</p>

</div>
</div>

### MinGW {#a076f8d7a72fd13b158cba699bb067fb8}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool llvm::object::WindowsResourceParser::MinGW</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 257 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/object/windowsresource-h">WindowsResource.h</a>.</p>

</div>
</div>

### Root {#a78c68ae6b2f73004c5217e4e1183061d}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">TreeNode llvm::object::WindowsResourceParser::Root</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 251 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/object/windowsresource-h">WindowsResource.h</a>.</p>

</div>
</div>

### StringTable {#ab9ced9e0030a2ff6dcd5f69241f136f8}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">std::vector&lt;std::vector&lt;UTF16&gt; &gt; llvm::object::WindowsResourceParser::StringTable</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 253 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/object/windowsresource-h">WindowsResource.h</a>.</p>

</div>
</div>

</div>

<hr/>

The documentation for this class was generated from the following files:

<ul>
<li><a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/object/windowsresource-h">WindowsResource.h</a></li>
<li><a href="/web-llvm/docs/api/files/lib/lib/object/windowsresource-cpp">WindowsResource.cpp</a></li>
</ul>

<hr/>

<p class="doxyGeneratedBy">Generated via <a href="https://github.com/xpack/doxygen2docusaurus">doxygen2docusaurus</a> by <a href="https://www.doxygen.nl">Doxygen</a> 1.14.0.</p>

</div>
