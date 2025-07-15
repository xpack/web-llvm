---

# DO NOT EDIT!
# Automatically generated via doxygen2docusaurus by Doxygen.

slug: /api/classes/llvm/sys/fs/mapped-file-region
custom_edit_url: null
toc_max_heading_level: 4
keywords:
  - doxygen
  - reference
  - class

---

<div class="doxyPage">

# The `mapped_file_region` Class Reference

<p>This class represents a memory mapped file. <a href="#details">More...</a></p>

## Declaration

<div class="doxyDeclaration">
class llvm::sys::fs::mapped_file_region { ... }
</div>

## Included Headers

<div class="doxyIncludesList">#include "<a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/support/filesystem-h">llvm/Support/FileSystem.h</a>"
</div>

## Enumerations Index

<table class="doxyMembersIndex">

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">enum</td>
<td class="doxyMemberIndexItemName" align="left" valign="top">mapmode { <a href="#a7d087bce12e64c2578f57ca0e1884919">...</a> }</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a678d384c05b8f6378cd4c243588deca0">mapped_file_region</a> ()=default</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a5085f46e72dbe2016ab2a105437892a8">mapped_file_region</a> (mapped_file_region &amp;&amp;Moved)</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#abb07ba99ff7835df49038b06e7a9eddf">mapped_file_region</a> (const mapped_file_region &amp;)=delete</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#aa3075f29b82c6459738db3b20ca5c8b2">mapped_file_region</a> (sys::fs::file_t fd, mapmode mode, size_t length, uint64_t offset, std::error_code &amp;ec)</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a5a204cf5791edfe80b59287f106c0336">~mapped_file_region</a> ()</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/sys/fs/mapped-file-region">mapped_file_region</a> &amp;</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a9547156df57cad5a7d202275b6a0e69e">operator=</a> (mapped_file_region &amp;&amp;Moved)</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/sys/fs/mapped-file-region">mapped_file_region</a> &amp;</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ad2fcb1656d2d32bf54eec5ca71669853">operator=</a> (const mapped_file_region &amp;)=delete</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a0392a5c13a86efb1be14b811ef411bb2">operator bool</a> () const</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p><a href="/web-llvm/docs/api/namespaces/llvm/check">Check</a> if this is a valid mapping. <a href="#a0392a5c13a86efb1be14b811ef411bb2">More...</a></p>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a9029973e3b8a55ce565c3b12aa4f76b9">unmap</a> ()</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Unmap. <a href="#a9029973e3b8a55ce565c3b12aa4f76b9">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">void</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ae15885686bedfe404ef0f5fb09e409ec">dontNeed</a> ()</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">size_t</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a1acf074d04e204669531e149b2c6f9c3">size</a> () const</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">char *</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ac1c8135d48119f3ec27065ad285bb400">data</a> () const</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> char *</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#aa80d445968f5c5c4c520fc20d961722c">const_data</a> () const</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Get a const view of the data. <a href="#aa80d445968f5c5c4c520fc20d961722c">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

</table>

## Private Member Functions Index

<table class="doxyMembersIndex">

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">void</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a4ac79cf23afd46241292aaff56cdc6b4">copyFrom</a> (const mapped_file_region &amp;Copied)</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a3cc5725dbb19d035002db8c2f6624bf5">moveFromImpl</a> (mapped_file_region &amp;Moved)</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ae985346b8237eb609ff9ea0a4bdbea69">unmapImpl</a> ()</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ae65ba4b0d3dfe8a236ac1360df79914e">dontNeedImpl</a> ()</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">std::error_code</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a93fb83249d78eb5fdd6f6a7e893eda2a">init</a> (sys::fs::file_t FD, uint64_t Offset, mapmode Mode)</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">size_t</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ab585a50d66a7871f3c5ece4c325b5a17">Size</a> = 0</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Platform-specific mapping state. <a href="#ab585a50d66a7871f3c5ece4c325b5a17">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">void *</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a104099c1123d3155c171df82d103df3c">Mapping</a> = nullptr</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="#a7d087bce12e64c2578f57ca0e1884919">mapmode</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a473e77d61cddfb6cf231db79cda1471a">Mode</a> = <a href="#a7d087bce12e64c2578f57ca0e1884919a816892378873d0045cdb238bbef751be">readonly</a></td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">static int</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ac507954b50856d809009e3bfa4a0bd6f">alignment</a> ()</td>
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

<p>This class represents a memory mapped file.</p>


<p>It is based on boost::iostreams::mapped_file.</p>


<p>Definition at line 1262 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/support/filesystem-h">FileSystem.h</a>.</p>


<div class="doxySectionDef">

## Enumerations

### mapmode {#a7d087bce12e64c2578f57ca0e1884919}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">enum llvm::sys::fs::mapped_file_region::mapmode </td>
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
<td class="doxyEnumItemName">readonly<a id="a7d087bce12e64c2578f57ca0e1884919a816892378873d0045cdb238bbef751be"></a></td>
<td class="doxyEnumItemDescription">May only access map via const_data as read only</td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">readwrite<a id="a7d087bce12e64c2578f57ca0e1884919afbac192dfef7b435728686ff9f82dad5"></a></td>
<td class="doxyEnumItemDescription">May access map via data and modify it. Written to path</td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">priv<a id="a7d087bce12e64c2578f57ca0e1884919a668043b129889a0df2d6a8d3740cb646"></a></td>
<td class="doxyEnumItemDescription">May modify via data, but changes are lost on destruction</td>
</tr>

</table>
</dd>
</dl>

<p>Definition at line 1264 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/support/filesystem-h">FileSystem.h</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Public Constructors

### mapped\_file\_region() {#a678d384c05b8f6378cd4c243588deca0}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">llvm::sys::fs::mapped_file_region::mapped_file_region ()</td>
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



<p>Definition at line 1299 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/support/filesystem-h">FileSystem.h</a>.</p>


<p>Referenced by <a href="#abb07ba99ff7835df49038b06e7a9eddf">mapped_file_region</a>, <a href="#a5085f46e72dbe2016ab2a105437892a8">mapped_file_region</a>, <a href="#ad2fcb1656d2d32bf54eec5ca71669853">operator=</a>, <a href="#a9547156df57cad5a7d202275b6a0e69e">operator=</a> and <a href="#a9029973e3b8a55ce565c3b12aa4f76b9">unmap</a>.</p>

</div>
</div>

### mapped\_file\_region() {#a5085f46e72dbe2016ab2a105437892a8}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">llvm::sys::fs::mapped_file_region::mapped_file_region (<a href="/web-llvm/docs/api/classes/llvm/sys/fs/mapped-file-region">mapped_file_region</a> &amp;&amp; Moved)</td>
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



<p>Definition at line 1300 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/support/filesystem-h">FileSystem.h</a>.</p>


<p>Reference <a href="#a678d384c05b8f6378cd4c243588deca0">mapped_file_region</a>.</p>

</div>
</div>

### mapped\_file\_region() {#abb07ba99ff7835df49038b06e7a9eddf}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">llvm::sys::fs::mapped_file_region::mapped_file_region (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/sys/fs/mapped-file-region">mapped_file_region</a> &amp;)</td>
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



<p>Definition at line 1307 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/support/filesystem-h">FileSystem.h</a>.</p>


<p>Reference <a href="#a678d384c05b8f6378cd4c243588deca0">mapped_file_region</a>.</p>

</div>
</div>

### mapped\_file\_region() {#aa3075f29b82c6459738db3b20ca5c8b2}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">llvm::sys::fs::mapped_file_region::mapped_file_region (<a href="/web-llvm/docs/api/namespaces/llvm/sys/fs/#a8ec705e6a361f51bca14123110ecb75d">sys::fs::file_t</a> fd, <a href="#a7d087bce12e64c2578f57ca0e1884919">mapmode</a> mode, size_t length, uint64_t offset, std::error_code &amp; ec)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">




<dl class="doxyParamsList">
<dt class="doxyParamsTableTitle">Parameters</dt>
<dd>
<table class="doxyParamsTable">
<tr class="doxyParamItem">
<td class="doxyParamItemName">fd</td>
<td class="doxyParamItemDescription"><p>An open file descriptor to map. Does not take ownership of fd.</p></td>
</tr>
</table>
</dd>
</dl>

<p>Definition at line 1311 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/support/filesystem-h">FileSystem.h</a>.</p>


<p>Reference <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/hexagon/hexagonoptaddrmode-cpp/#abdd61257a7f5e75ed961036299f26498">mode</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Public Destructor

### \~mapped\_file\_region() {#a5a204cf5791edfe80b59287f106c0336}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">llvm::sys::fs::mapped_file_region::~mapped_file_region ()</td>
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



<p>Definition at line 1314 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/support/filesystem-h">FileSystem.h</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Public Operators

### operator bool() {#a0392a5c13a86efb1be14b811ef411bb2}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">llvm::sys::fs::mapped_file_region::operator bool ()</td>
</tr>
</table>
</td>
<td class="doxyMemberLabelsRight">
<span class="doxyMemberLabels">
<span class="doxyMemberLabel inline">inline</span>
<span class="doxyMemberLabel explicit">explicit</span>
</span>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p><a href="/web-llvm/docs/api/namespaces/llvm/check">Check</a> if this is a valid mapping.</p>

<p>Definition at line 1317 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/support/filesystem-h">FileSystem.h</a>.</p>

</div>
</div>

### operator=() {#a9547156df57cad5a7d202275b6a0e69e}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">mapped_file_region &amp; llvm::sys::fs::mapped_file_region::operator= (<a href="/web-llvm/docs/api/classes/llvm/sys/fs/mapped-file-region">mapped_file_region</a> &amp;&amp; Moved)</td>
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



<p>Definition at line 1301 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/support/filesystem-h">FileSystem.h</a>.</p>


<p>References <a href="#a678d384c05b8f6378cd4c243588deca0">mapped_file_region</a> and <a href="#a9029973e3b8a55ce565c3b12aa4f76b9">unmap</a>.</p>

</div>
</div>

### operator=() {#ad2fcb1656d2d32bf54eec5ca71669853}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">mapped_file_region &amp; llvm::sys::fs::mapped_file_region::operator= (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/sys/fs/mapped-file-region">mapped_file_region</a> &amp;)</td>
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



<p>Definition at line 1308 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/support/filesystem-h">FileSystem.h</a>.</p>


<p>Reference <a href="#a678d384c05b8f6378cd4c243588deca0">mapped_file_region</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Public Member Functions

### const\_data() {#aa80d445968f5c5c4c520fc20d961722c}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">const char * llvm::sys::fs::mapped_file_region::const_data ()</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Get a const view of the data.</p>


<p>Modifying this memory has undefined behavior.</p>


<p>Declaration at line 1331 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/support/filesystem-h">FileSystem.h</a>, definition at line 1169 of file <a href="/web-llvm/docs/api/files/lib/lib/support/path-cpp">Path.cpp</a>.</p>


<p>Reference <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/silowercontrolflow-cpp/#a4868c5d81c5ccc98c47aeab6244346a0">assert</a>.</p>

</div>
</div>

### data() {#ac1c8135d48119f3ec27065ad285bb400}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">char * llvm::sys::fs::mapped_file_region::data ()</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Declaration at line 1327 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/support/filesystem-h">FileSystem.h</a>, definition at line 1164 of file <a href="/web-llvm/docs/api/files/lib/lib/support/path-cpp">Path.cpp</a>.</p>


<p>Reference <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/silowercontrolflow-cpp/#a4868c5d81c5ccc98c47aeab6244346a0">assert</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/namespaces/llvm/xray/#ab67d7aaee3e9b7f980823af5cde41fcb">llvm::xray::loadProfile</a>, <a href="/web-llvm/docs/api/namespaces/llvm/xray/#a6d387644a0d53428ceb3dfad35a51922">llvm::xray::loadTraceFile</a> and <a href="/web-llvm/docs/api/files/lib/lib/xray/instrumentationmap-cpp/#a740748c1b9bf73c9456e1d823f34c5f2">loadYAML</a>.</p>

</div>
</div>

### dontNeed() {#ae15885686bedfe404ef0f5fb09e409ec}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void llvm::sys::fs::mapped_file_region::dontNeed ()</td>
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



<p>Definition at line 1324 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/support/filesystem-h">FileSystem.h</a>.</p>

</div>
</div>

### size() {#a1acf074d04e204669531e149b2c6f9c3}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">size_t llvm::sys::fs::mapped_file_region::size ()</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Declaration at line 1326 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/support/filesystem-h">FileSystem.h</a>, definition at line 1159 of file <a href="/web-llvm/docs/api/files/lib/lib/support/path-cpp">Path.cpp</a>.</p>


<p>Reference <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/silowercontrolflow-cpp/#a4868c5d81c5ccc98c47aeab6244346a0">assert</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/namespaces/llvm/xray/#ab67d7aaee3e9b7f980823af5cde41fcb">llvm::xray::loadProfile</a>, <a href="/web-llvm/docs/api/namespaces/llvm/xray/#a6d387644a0d53428ceb3dfad35a51922">llvm::xray::loadTraceFile</a> and <a href="/web-llvm/docs/api/files/lib/lib/xray/instrumentationmap-cpp/#a740748c1b9bf73c9456e1d823f34c5f2">loadYAML</a>.</p>

</div>
</div>

### unmap() {#a9029973e3b8a55ce565c3b12aa4f76b9}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void llvm::sys::fs::mapped_file_region::unmap ()</td>
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

<p>Unmap.</p>

<p>Definition at line 1320 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/support/filesystem-h">FileSystem.h</a>.</p>


<p>Reference <a href="#a678d384c05b8f6378cd4c243588deca0">mapped_file_region</a>.</p>


<p>Referenced by <a href="#a9547156df57cad5a7d202275b6a0e69e">operator=</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Private Member Functions

### copyFrom() {#a4ac79cf23afd46241292aaff56cdc6b4}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void llvm::sys::fs::mapped_file_region::copyFrom (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/sys/fs/mapped-file-region">mapped_file_region</a> &amp; Copied)</td>
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



<p>Definition at line 1279 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/support/filesystem-h">FileSystem.h</a>.</p>

</div>
</div>

### dontNeedImpl() {#ae65ba4b0d3dfe8a236ac1360df79914e}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void llvm::sys::fs::mapped_file_region::dontNeedImpl ()</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 1294 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/support/filesystem-h">FileSystem.h</a>.</p>

</div>
</div>

### init() {#a93fb83249d78eb5fdd6f6a7e893eda2a}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">std::error_code llvm::sys::fs::mapped_file_region::init (<a href="/web-llvm/docs/api/namespaces/llvm/sys/fs/#a8ec705e6a361f51bca14123110ecb75d">sys::fs::file_t</a> FD, uint64_t Offset, <a href="#a7d087bce12e64c2578f57ca0e1884919">mapmode</a> Mode)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 1296 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/support/filesystem-h">FileSystem.h</a>.</p>

</div>
</div>

### moveFromImpl() {#a3cc5725dbb19d035002db8c2f6624bf5}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void llvm::sys::fs::mapped_file_region::moveFromImpl (<a href="/web-llvm/docs/api/classes/llvm/sys/fs/mapped-file-region">mapped_file_region</a> &amp; Moved)</td>
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



<p>Definition at line 1288 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/support/filesystem-h">FileSystem.h</a>.</p>

</div>
</div>

### unmapImpl() {#ae985346b8237eb609ff9ea0a4bdbea69}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void llvm::sys::fs::mapped_file_region::unmapImpl ()</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 1293 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/support/filesystem-h">FileSystem.h</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Private Member Attributes

### Mapping {#a104099c1123d3155c171df82d103df3c}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void* llvm::sys::fs::mapped_file_region::Mapping = nullptr</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 1273 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/support/filesystem-h">FileSystem.h</a>.</p>

</div>
</div>

### Mode {#a473e77d61cddfb6cf231db79cda1471a}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">mapmode llvm::sys::fs::mapped_file_region::Mode = <a href="#a7d087bce12e64c2578f57ca0e1884919a816892378873d0045cdb238bbef751be">readonly</a></td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 1277 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/support/filesystem-h">FileSystem.h</a>.</p>

</div>
</div>

### Size {#ab585a50d66a7871f3c5ece4c325b5a17}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">size_t llvm::sys::fs::mapped_file_region::Size = 0</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Platform-specific mapping state.</p>

<p>Definition at line 1272 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/support/filesystem-h">FileSystem.h</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Public Static Functions

### alignment() {#ac507954b50856d809009e3bfa4a0bd6f}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">int llvm::sys::fs::mapped_file_region::alignment ()</td>
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




<dl class="doxySectionUser">
<dt>Returns</dt>
<dd><p>The minimum alignment offset must be.</p></dd>
</dl>


<p>Definition at line 1334 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/support/filesystem-h">FileSystem.h</a>.</p>

</div>
</div>

</div>

<hr/>

The documentation for this class was generated from the following files:

<ul>
<li><a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/support/filesystem-h">FileSystem.h</a></li>
<li><a href="/web-llvm/docs/api/files/lib/lib/support/path-cpp">Path.cpp</a></li>
</ul>

<hr/>

<p class="doxyGeneratedBy">Generated via <a href="https://github.com/xpack/doxygen2docusaurus">doxygen2docusaurus</a> by <a href="https://www.doxygen.nl">Doxygen</a> 1.14.0.</p>

</div>
