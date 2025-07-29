---

# DO NOT EDIT!
# Automatically generated via doxygen2docusaurus by Doxygen.

slug: /api/classes/llvm/withcolor
custom_edit_url: null
toc_max_heading_level: 4
keywords:
  - doxygen
  - reference
  - class

---

<div class="doxyPage">

# `WithColor` Class

<p>An RAII object that temporarily switches an output stream to a specific color. <a href="#details">More...</a></p>

## Declaration

<div class="doxyDeclaration">
class llvm::WithColor { ... }
</div>

## Included Headers

<div class="doxyIncludesList">#include "<a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/support/withcolor-h">llvm/Support/WithColor.h</a>"
</div>

## Public Member Typedefs Index

<table class="doxyMembersIndex">

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">using</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a5f76e2d718b584bd59ec66a543c72751">AutoDetectFunctionType</a> = bool(*)(<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/raw-ostream">raw_ostream</a> &amp;OS)</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/support/compiler-h/#a49fbbceaed01be1497ada6623f2ba42f">LLVM_CTOR_NODISCARD</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a0b7d62735f94b418859340f4949299bf">WithColor</a> (raw_ostream &amp;OS, HighlightColor S, ColorMode Mode=ColorMode::Auto)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>To be used like this: WithColor(OS, HighlightColor::String) &lt;&lt; "text";. <a href="#a0b7d62735f94b418859340f4949299bf">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/support/compiler-h/#a49fbbceaed01be1497ada6623f2ba42f">LLVM_CTOR_NODISCARD</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a49d88ad31bfdaa61d47dd7720c083823">WithColor</a> (raw_ostream &amp;OS, raw_ostream::Colors Color=raw_ostream::SAVEDCOLOR, bool Bold=false, bool BG=false, ColorMode Mode=ColorMode::Auto)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>To be used like this: WithColor(OS, raw_ostream::BLACK) &lt;&lt; "text";. <a href="#a49d88ad31bfdaa61d47dd7720c083823">More...</a></p>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a3eb6bded04ddbc54bd7b5b8ff6c827fe">~WithColor</a> ()</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a8ac094dc2861f4fc6b7fc0213d52699c">operator raw_ostream &amp;</a> ()</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexTemplate">
<td class="doxyMemberIndexTemplate" colspan="2"><div>template &lt;typename T&gt;</div></td>
</tr>
<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemTypeTemplate" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/withcolor">WithColor</a> &amp;</td>
<td class="doxyMemberIndexItemNameTemplate" align="left" valign="top"><a href="#af12ea16e75cf7fba508e3d1bae0b7449">operator&lt;&lt;</a> (T &amp;O)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexTemplate">
<td class="doxyMemberIndexTemplate" colspan="2"><div>template &lt;typename T&gt;</div></td>
</tr>
<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemTypeTemplate" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/withcolor">WithColor</a> &amp;</td>
<td class="doxyMemberIndexItemNameTemplate" align="left" valign="top"><a href="#a0cdb1fdc0d073ea5d9a12b36107f729c">operator&lt;&lt;</a> (const T &amp;O)</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/raw-ostream">raw_ostream</a> &amp;</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a986df42e8d99e128c31168ef61b02f5a">get</a> ()</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a119ef8d948bd6e2bf01db3c5e6b772f7">colorsEnabled</a> ()</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Determine whether colors are displayed. <a href="#a119ef8d948bd6e2bf01db3c5e6b772f7">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/withcolor">WithColor</a> &amp;</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a06e589e7787dc00edd3b93f2fdbe514b">changeColor</a> (raw_ostream::Colors Color, bool Bold=false, bool BG=false)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Change the color of text that will be output from this point forward. <a href="#a06e589e7787dc00edd3b93f2fdbe514b">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/withcolor">WithColor</a> &amp;</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a76f42a78c2e8f8afcd4a7ca994d8a84f">resetColor</a> ()</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Reset the colors to terminal defaults. <a href="#a76f42a78c2e8f8afcd4a7ca994d8a84f">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

</table>

## Private Member Attributes Index

<table class="doxyMembersIndex">

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/raw-ostream">raw_ostream</a> &amp;</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#af8ac3521a17d99182f7b93567f16513d">OS</a></td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/namespaces/llvm/#afdccf3ff7a8dfaa084b07c1fb417bbe2">ColorMode</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a016ace39c72022004f54c7e2f074f61c">Mode</a></td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">static <a href="/web-llvm/docs/api/classes/llvm/raw-ostream">raw_ostream</a> &amp;</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a59d59f7f8aa89b08f44ad6a87e8ebb1a">error</a> ()</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Convenience method for printing "error: " to stderr. <a href="#a59d59f7f8aa89b08f44ad6a87e8ebb1a">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">static <a href="/web-llvm/docs/api/classes/llvm/raw-ostream">raw_ostream</a> &amp;</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a237ad6eae22f6b2746a542c02d309a5b">warning</a> ()</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Convenience method for printing "warning: " to stderr. <a href="#a237ad6eae22f6b2746a542c02d309a5b">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">static <a href="/web-llvm/docs/api/classes/llvm/raw-ostream">raw_ostream</a> &amp;</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ab5313a760f20fc53b44cc8dbabfd1ae1">note</a> ()</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Convenience method for printing "note: " to stderr. <a href="#ab5313a760f20fc53b44cc8dbabfd1ae1">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">static <a href="/web-llvm/docs/api/classes/llvm/raw-ostream">raw_ostream</a> &amp;</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#afdcd08052180c0b87e06a2808b062c01">remark</a> ()</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Convenience method for printing "remark: " to stderr. <a href="#afdcd08052180c0b87e06a2808b062c01">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">static <a href="/web-llvm/docs/api/classes/llvm/raw-ostream">raw_ostream</a> &amp;</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a5254e7538d6a07134ed56800efc14a39">error</a> (raw_ostream &amp;OS, StringRef Prefix="", bool DisableColors=false)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Convenience method for printing "error: " to the given stream. <a href="#a5254e7538d6a07134ed56800efc14a39">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">static <a href="/web-llvm/docs/api/classes/llvm/raw-ostream">raw_ostream</a> &amp;</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ade51780899828c5352637d84d847a2b1">warning</a> (raw_ostream &amp;OS, StringRef Prefix="", bool DisableColors=false)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Convenience method for printing "warning: " to the given stream. <a href="#ade51780899828c5352637d84d847a2b1">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">static <a href="/web-llvm/docs/api/classes/llvm/raw-ostream">raw_ostream</a> &amp;</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a028b04cefc83e8374898708f803b0242">note</a> (raw_ostream &amp;OS, StringRef Prefix="", bool DisableColors=false)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Convenience method for printing "note: " to the given stream. <a href="#a028b04cefc83e8374898708f803b0242">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">static <a href="/web-llvm/docs/api/classes/llvm/raw-ostream">raw_ostream</a> &amp;</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a9f22bc56f93bc45e4dbd5ecf1daa1746">remark</a> (raw_ostream &amp;OS, StringRef Prefix="", bool DisableColors=false)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Convenience method for printing "remark: " to the given stream. <a href="#a9f22bc56f93bc45e4dbd5ecf1daa1746">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">static void</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#aa125c88f5418a9e78bd9f1f20b774b08">defaultErrorHandler</a> (Error Err)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Implement default handling for <a href="/web-llvm/docs/api/classes/llvm/error">Error</a>. <a href="#aa125c88f5418a9e78bd9f1f20b774b08">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">static void</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a0ab9ce7767ba8ad9a3cb17cd35d81a1f">defaultWarningHandler</a> (Error Warning)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Implement default handling for Warning. <a href="#a0ab9ce7767ba8ad9a3cb17cd35d81a1f">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">static <a href="#a5f76e2d718b584bd59ec66a543c72751">AutoDetectFunctionType</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#acc596b1a9d4cf50b3096702e25b42d70">defaultAutoDetectFunction</a> ()</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Retrieve the default color auto detection function. <a href="#acc596b1a9d4cf50b3096702e25b42d70">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">static void</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ad8a533ac5cd1bd14e1999bab57a7c863">setAutoDetectFunction</a> (AutoDetectFunctionType NewAutoDetectFunction)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Change the global auto detection function. <a href="#ad8a533ac5cd1bd14e1999bab57a7c863">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

</table>

## Private Static Attributes Index

<table class="doxyMembersIndex">

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">static <a href="#a5f76e2d718b584bd59ec66a543c72751">AutoDetectFunctionType</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a3c8b0e65081603ac3d45c22953d0f227">AutoDetectFunction</a> = ...</td>
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

<p>An RAII object that temporarily switches an output stream to a specific color.</p>

<p>Definition at line 54 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/support/withcolor-h">WithColor.h</a>.</p>


<div class="doxySectionDef">

## Public Member Typedefs

### AutoDetectFunctionType {#a5f76e2d718b584bd59ec66a543c72751}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">using llvm::WithColor::AutoDetectFunctionType =  bool (*)(const raw_ostream &amp;OS)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 56 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/support/withcolor-h">WithColor.h</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Public Constructors

### WithColor() {#a0b7d62735f94b418859340f4949299bf}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">WithColor::WithColor (<a href="/web-llvm/docs/api/classes/llvm/raw-ostream">raw_ostream</a> &amp; OS, <a href="/web-llvm/docs/api/namespaces/llvm/#ac226f3d2b9ca090171a8e0a8cb92c343">HighlightColor</a> S, <a href="/web-llvm/docs/api/namespaces/llvm/#afdccf3ff7a8dfaa084b07c1fb417bbe2">ColorMode</a> Mode=<a href="/web-llvm/docs/api/namespaces/llvm/#afdccf3ff7a8dfaa084b07c1fb417bbe2a06b9281e396db002010bde1de57262eb">ColorMode::Auto</a>)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>To be used like this: WithColor(OS, HighlightColor::String) &lt;&lt; "text";.</p>


<dl class="doxyParamsList">
<dt class="doxyParamsTableTitle">Parameters</dt>
<dd>
<table class="doxyParamsTable">
<tr class="doxyParamItem">
<td class="doxyParamItemName">OS</td>
<td class="doxyParamItemDescription"><p>The output stream</p></td>
</tr>
<tr class="doxyParamItem">
<td class="doxyParamItemName">S</td>
<td class="doxyParamItemDescription"><p>Symbolic name for syntax element to color</p></td>
</tr>
<tr class="doxyParamItem">
<td class="doxyParamItemName">Mode</td>
<td class="doxyParamItemDescription"><p>Enable, disable or compute whether to use colors.</p></td>
</tr>
</table>
</dd>
</dl>

<p>Declaration at line 62 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/support/withcolor-h">WithColor.h</a>, definition at line 44 of file <a href="/web-llvm/docs/api/files/lib/lib/support/withcolor-cpp">WithColor.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/namespaces/llvm/#ac226f3d2b9ca090171a8e0a8cb92c343add7bf230fde8d4836917806aff6a6b27">llvm::Address</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#ac226f3d2b9ca090171a8e0a8cb92c343af2bbdf9f72c085adc4d0404e370f0f4c">llvm::Attribute</a>, <a href="/web-llvm/docs/api/classes/llvm/raw-ostream/#ad7fa72c34a893a70df723e8c90410864">llvm::raw_ostream::BLACK</a>, <a href="/web-llvm/docs/api/classes/llvm/raw-ostream/#a63c9d9dc86ce5675ba81e57258408628">llvm::raw_ostream::BLUE</a>, <a href="#a119ef8d948bd6e2bf01db3c5e6b772f7">colorsEnabled</a>, <a href="/web-llvm/docs/api/classes/llvm/raw-ostream/#a1b89c1fc567cf8889baeccead5083434">llvm::raw_ostream::CYAN</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#ac226f3d2b9ca090171a8e0a8cb92c343a30309b565fa53a27f30668e22f7cf058">llvm::Enumerator</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#ac226f3d2b9ca090171a8e0a8cb92c343a902b0d55fddef6f8d651fe1035b7d4bd">llvm::Error</a>, <a href="/web-llvm/docs/api/classes/llvm/raw-ostream/#ae56223ff7592f05301a6b496ae46299c">llvm::raw_ostream::GREEN</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#ac226f3d2b9ca090171a8e0a8cb92c343a4374cf34c5d58482ffae982196bd2114">llvm::Macro</a>, <a href="/web-llvm/docs/api/classes/llvm/raw-ostream/#abab3a5904ddc74e76f0a8021d383866f">llvm::raw_ostream::MAGENTA</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#ac226f3d2b9ca090171a8e0a8cb92c343a3b0649c72650c313a357338dcdfb64ec">llvm::Note</a>, <a href="/web-llvm/docs/api/classes/llvm/raw-ostream/#ae7b7856e1bc7aea739f05e4d65d5276b">llvm::raw_ostream::RED</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#ac226f3d2b9ca090171a8e0a8cb92c343a91921ada405fd6ba65dff028df047cb6">llvm::Remark</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#ac226f3d2b9ca090171a8e0a8cb92c343a27118326006d3829667a400ad23d5d98">llvm::String</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#ac226f3d2b9ca090171a8e0a8cb92c343ac101058e7ea21bbbf2a5ac893088e90b">llvm::Tag</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#ac226f3d2b9ca090171a8e0a8cb92c343a0eaadb4fcb48a0a0ed7bc9868be9fbaa">llvm::Warning</a> and <a href="/web-llvm/docs/api/classes/llvm/raw-ostream/#a026561b02ba397a040ff1e681d2fb0ae">llvm::raw_ostream::YELLOW</a>.</p>


<p>Referenced by <a href="#a06e589e7787dc00edd3b93f2fdbe514b">changeColor</a>, <a href="#a5254e7538d6a07134ed56800efc14a39">error</a>, <a href="#a028b04cefc83e8374898708f803b0242">note</a>, <a href="#a0cdb1fdc0d073ea5d9a12b36107f729c">operator&lt;&lt;</a>, <a href="#af12ea16e75cf7fba508e3d1bae0b7449">operator&lt;&lt;</a>, <a href="#a9f22bc56f93bc45e4dbd5ecf1daa1746">remark</a>, <a href="#a76f42a78c2e8f8afcd4a7ca994d8a84f">resetColor</a> and <a href="#ade51780899828c5352637d84d847a2b1">warning</a>.</p>

</div>
</div>

### WithColor() {#a49d88ad31bfdaa61d47dd7720c083823}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">LLVM_CTOR_NODISCARD llvm::WithColor::WithColor (<a href="/web-llvm/docs/api/classes/llvm/raw-ostream">raw_ostream</a> &amp; OS, <a href="/web-llvm/docs/api/classes/llvm/raw-ostream/#a1d5efc43dd5669473ac2fe47d5aaf965">raw_ostream::Colors</a> Color=<a href="/web-llvm/docs/api/classes/llvm/raw-ostream/#ad55e55b3692fe8ec3e8b724d3d5bade0">raw_ostream::SAVEDCOLOR</a>, bool Bold=false, bool BG=false, <a href="/web-llvm/docs/api/namespaces/llvm/#afdccf3ff7a8dfaa084b07c1fb417bbe2">ColorMode</a> Mode=<a href="/web-llvm/docs/api/namespaces/llvm/#afdccf3ff7a8dfaa084b07c1fb417bbe2a06b9281e396db002010bde1de57262eb">ColorMode::Auto</a>)</td>
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

<p>To be used like this: WithColor(OS, raw_ostream::BLACK) &lt;&lt; "text";.</p>


<dl class="doxyParamsList">
<dt class="doxyParamsTableTitle">Parameters</dt>
<dd>
<table class="doxyParamsTable">
<tr class="doxyParamItem">
<td class="doxyParamItemName">OS</td>
<td class="doxyParamItemDescription"><p>The output stream</p></td>
</tr>
<tr class="doxyParamItem">
<td class="doxyParamItemName">Color</td>
<td class="doxyParamItemDescription"><p>ANSI color to use, the special SAVEDCOLOR can be used to change only the bold attribute, and keep colors untouched</p></td>
</tr>
<tr class="doxyParamItem">
<td class="doxyParamItemName">Bold</td>
<td class="doxyParamItemDescription"><p>Bold/brighter text, default false</p></td>
</tr>
<tr class="doxyParamItem">
<td class="doxyParamItemName">BG</td>
<td class="doxyParamItemDescription"><p>If true, change the background, default: change foreground</p></td>
</tr>
<tr class="doxyParamItem">
<td class="doxyParamItemName">Mode</td>
<td class="doxyParamItemDescription"><p>Enable, disable or compute whether to use colors.</p></td>
</tr>
</table>
</dd>
</dl>

<p>Definition at line 71 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/support/withcolor-h">WithColor.h</a>.</p>


<p>References <a href="/web-llvm/docs/api/namespaces/llvm/#afdccf3ff7a8dfaa084b07c1fb417bbe2a06b9281e396db002010bde1de57262eb">llvm::Auto</a>, <a href="#a06e589e7787dc00edd3b93f2fdbe514b">changeColor</a>, <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/support/compiler-h/#a49fbbceaed01be1497ada6623f2ba42f">LLVM_CTOR_NODISCARD</a> and <a href="/web-llvm/docs/api/classes/llvm/raw-ostream/#ad55e55b3692fe8ec3e8b724d3d5bade0">llvm::raw_ostream::SAVEDCOLOR</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Public Destructor

### \~WithColor() {#a3eb6bded04ddbc54bd7b5b8ff6c827fe}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">WithColor::~WithColor ()</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Declaration at line 77 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/support/withcolor-h">WithColor.h</a>, definition at line 156 of file <a href="/web-llvm/docs/api/files/lib/lib/support/withcolor-cpp">WithColor.cpp</a>.</p>


<p>Reference <a href="#a76f42a78c2e8f8afcd4a7ca994d8a84f">resetColor</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Public Operators

### operator raw\_ostream &amp;() {#a8ac094dc2861f4fc6b7fc0213d52699c}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">llvm::WithColor::operator raw_ostream &amp; ()</td>
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



<p>Definition at line 80 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/support/withcolor-h">WithColor.h</a>.</p>

</div>
</div>

### operator&lt;&lt;() {#af12ea16e75cf7fba508e3d1bae0b7449}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<div class="doxyMemberTemplate">template &lt;typename T&gt;</div>
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">WithColor &amp; llvm::WithColor::operator&lt;&lt; (T &amp; O)</td>
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



<p>Definition at line 81 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/support/withcolor-h">WithColor.h</a>.</p>


<p>References <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/mips/mips16isellowering-cpp/#a0acb682b8260ab1c60b918599864e2e5">T</a> and <a href="#a0b7d62735f94b418859340f4949299bf">WithColor</a>.</p>

</div>
</div>

### operator&lt;&lt;() {#a0cdb1fdc0d073ea5d9a12b36107f729c}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<div class="doxyMemberTemplate">template &lt;typename T&gt;</div>
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">WithColor &amp; llvm::WithColor::operator&lt;&lt; (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> T &amp; O)</td>
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



<p>Definition at line 85 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/support/withcolor-h">WithColor.h</a>.</p>


<p>References <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/mips/mips16isellowering-cpp/#a0acb682b8260ab1c60b918599864e2e5">T</a> and <a href="#a0b7d62735f94b418859340f4949299bf">WithColor</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Public Member Functions

### changeColor() {#a06e589e7787dc00edd3b93f2fdbe514b}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">WithColor &amp; WithColor::changeColor (<a href="/web-llvm/docs/api/classes/llvm/raw-ostream/#a1d5efc43dd5669473ac2fe47d5aaf965">raw_ostream::Colors</a> Color, bool Bold=false, bool BG=false)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Change the color of text that will be output from this point forward.</p>


<dl class="doxyParamsList">
<dt class="doxyParamsTableTitle">Parameters</dt>
<dd>
<table class="doxyParamsTable">
<tr class="doxyParamItem">
<td class="doxyParamItemName">Color</td>
<td class="doxyParamItemDescription"><p>ANSI color to use, the special SAVEDCOLOR can be used to change only the bold attribute, and keep colors untouched</p></td>
</tr>
<tr class="doxyParamItem">
<td class="doxyParamItemName">Bold</td>
<td class="doxyParamItemDescription"><p>Bold/brighter text, default false</p></td>
</tr>
<tr class="doxyParamItem">
<td class="doxyParamItemName">BG</td>
<td class="doxyParamItemDescription"><p>If true, change the background, default: change foreground</p></td>
</tr>
</table>
</dd>
</dl>

<p>Declaration at line 120 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/support/withcolor-h">WithColor.h</a>, definition at line 143 of file <a href="/web-llvm/docs/api/files/lib/lib/support/withcolor-cpp">WithColor.cpp</a>.</p>


<p>References <a href="#a06e589e7787dc00edd3b93f2fdbe514b">changeColor</a>, <a href="#a119ef8d948bd6e2bf01db3c5e6b772f7">colorsEnabled</a> and <a href="#a0b7d62735f94b418859340f4949299bf">WithColor</a>.</p>


<p>Referenced by <a href="#a06e589e7787dc00edd3b93f2fdbe514b">changeColor</a> and <a href="#a49d88ad31bfdaa61d47dd7720c083823">WithColor</a>.</p>

</div>
</div>

### colorsEnabled() {#a119ef8d948bd6e2bf01db3c5e6b772f7}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool WithColor::colorsEnabled ()</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Determine whether colors are displayed.</p>

<p>Declaration at line 113 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/support/withcolor-h">WithColor.h</a>, definition at line 131 of file <a href="/web-llvm/docs/api/files/lib/lib/support/withcolor-cpp">WithColor.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/namespaces/llvm/#afdccf3ff7a8dfaa084b07c1fb417bbe2a06b9281e396db002010bde1de57262eb">llvm::Auto</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#afdccf3ff7a8dfaa084b07c1fb417bbe2abcfaccebf745acfd5e75351095a5394a">llvm::Disable</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#afdccf3ff7a8dfaa084b07c1fb417bbe2a2faec1f9f8cc7f8f40d521c4dd574f49">llvm::Enable</a> and <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/support/errorhandling-h/#ace243f5c25697a1107cce46626b3dc94">llvm_unreachable</a>.</p>


<p>Referenced by <a href="#a06e589e7787dc00edd3b93f2fdbe514b">changeColor</a>, <a href="#a76f42a78c2e8f8afcd4a7ca994d8a84f">resetColor</a> and <a href="#a0b7d62735f94b418859340f4949299bf">WithColor</a>.</p>

</div>
</div>

### get() {#a986df42e8d99e128c31168ef61b02f5a}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">raw_ostream &amp; llvm::WithColor::get ()</td>
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



<p>Definition at line 79 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/support/withcolor-h">WithColor.h</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/classes/llvm/dwarfdebugmacro/#a8911330a1f029ab78880b5b7c5a6230e">llvm::DWARFDebugMacro::dump</a>, <a href="/web-llvm/docs/api/classes/llvm/dwarfdie/#aff52b4e2a5b1e91ab933fbd3ad52bba0">llvm::DWARFDie::dump</a> and <a href="/web-llvm/docs/api/classes/llvm/dwarfformvalue/#abccb4aa356ed1bf8bae692df185a885a">llvm::DWARFFormValue::dump</a>.</p>

</div>
</div>

### resetColor() {#a76f42a78c2e8f8afcd4a7ca994d8a84f}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">WithColor &amp; WithColor::resetColor ()</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Reset the colors to terminal defaults.</p>


<p>Call this when you are done outputting colored text, or before program exit.</p>


<p>Declaration at line 125 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/support/withcolor-h">WithColor.h</a>, definition at line 150 of file <a href="/web-llvm/docs/api/files/lib/lib/support/withcolor-cpp">WithColor.cpp</a>.</p>


<p>References <a href="#a119ef8d948bd6e2bf01db3c5e6b772f7">colorsEnabled</a>, <a href="#a76f42a78c2e8f8afcd4a7ca994d8a84f">resetColor</a> and <a href="#a0b7d62735f94b418859340f4949299bf">WithColor</a>.</p>


<p>Referenced by <a href="#a76f42a78c2e8f8afcd4a7ca994d8a84f">resetColor</a> and <a href="#a3eb6bded04ddbc54bd7b5b8ff6c827fe">~WithColor</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Private Member Attributes

### Mode {#a016ace39c72022004f54c7e2f074f61c}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">ColorMode llvm::WithColor::Mode</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 144 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/support/withcolor-h">WithColor.h</a>.</p>

</div>
</div>

### OS {#af8ac3521a17d99182f7b93567f16513d}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">raw_ostream&amp; llvm::WithColor::OS</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 143 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/support/withcolor-h">WithColor.h</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Public Static Functions

### defaultAutoDetectFunction() {#acc596b1a9d4cf50b3096702e25b42d70}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">WithColor::AutoDetectFunctionType WithColor::defaultAutoDetectFunction ()</td>
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

<p>Retrieve the default color auto detection function.</p>

<p>Declaration at line 136 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/support/withcolor-h">WithColor.h</a>, definition at line 170 of file <a href="/web-llvm/docs/api/files/lib/lib/support/withcolor-cpp">WithColor.cpp</a>.</p>


<p>Reference <a href="/web-llvm/docs/api/files/lib/lib/support/withcolor-cpp/#a217ca6e38806a2d0ea3712d69c0b06f6">DefaultAutoDetectFunction</a>.</p>

</div>
</div>

### defaultErrorHandler() {#aa125c88f5418a9e78bd9f1f20b774b08}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void WithColor::defaultErrorHandler (<a href="/web-llvm/docs/api/classes/llvm/error">Error</a> Err)</td>
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

<p>Implement default handling for <a href="/web-llvm/docs/api/classes/llvm/error">Error</a>.</p>


<p>Print "error: " to stderr.</p>


<p>Declaration at line 129 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/support/withcolor-h">WithColor.h</a>, definition at line 158 of file <a href="/web-llvm/docs/api/files/lib/lib/support/withcolor-cpp">WithColor.cpp</a>.</p>


<p>References <a href="#a59d59f7f8aa89b08f44ad6a87e8ebb1a">error</a> and <a href="/web-llvm/docs/api/namespaces/llvm/#a2aa0f5c36ac6291f5d5f2b4efd9ffe70">llvm::handleAllErrors</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/classes/llvm/dwarfcontext/#a1c1413d062f12285c899c61c634ae216">llvm::DWARFContext::DWARFContextState</a> and <a href="/web-llvm/docs/api/classes/anonymous-dwarfcontext-cpp-/threadunsafedwarfcontextstate/#a54233894e754c548da87c0d21d69003d">anonymous{DWARFContext.cpp}::ThreadUnsafeDWARFContextState::getDWOContext</a>.</p>

</div>
</div>

### defaultWarningHandler() {#a0ab9ce7767ba8ad9a3cb17cd35d81a1f}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void WithColor::defaultWarningHandler (<a href="/web-llvm/docs/api/classes/llvm/error">Error</a> Warning)</td>
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

<p>Implement default handling for Warning.</p>


<p>Print "warning: " to stderr.</p>


<p>Declaration at line 133 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/support/withcolor-h">WithColor.h</a>, definition at line 164 of file <a href="/web-llvm/docs/api/files/lib/lib/support/withcolor-cpp">WithColor.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/namespaces/llvm/#a2aa0f5c36ac6291f5d5f2b4efd9ffe70">llvm::handleAllErrors</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#ac226f3d2b9ca090171a8e0a8cb92c343a0eaadb4fcb48a0a0ed7bc9868be9fbaa">llvm::Warning</a> and <a href="#a237ad6eae22f6b2746a542c02d309a5b">warning</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/classes/llvm/dwarfcontext/#a1c1413d062f12285c899c61c634ae216">llvm::DWARFContext::DWARFContextState</a>, <a href="/web-llvm/docs/api/classes/anonymous-dwarfcontext-cpp-/threadunsafedwarfcontextstate/#a54233894e754c548da87c0d21d69003d">anonymous{DWARFContext.cpp}::ThreadUnsafeDWARFContextState::getDWOContext</a> and <a href="/web-llvm/docs/api/files/lib/lib/dwp/dwp-cpp/#a96eeab61680e6721ce83aee14fa6b3f2">sectionOverflowErrorOrWarning</a>.</p>

</div>
</div>

### error() {#a59d59f7f8aa89b08f44ad6a87e8ebb1a}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">raw_ostream &amp; WithColor::error ()</td>
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

<p>Convenience method for printing "error: " to stderr.</p>

<p>Declaration at line 91 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/support/withcolor-h">WithColor.h</a>, definition at line 83 of file <a href="/web-llvm/docs/api/files/lib/lib/support/withcolor-cpp">WithColor.cpp</a>.</p>


<p>References <a href="#a59d59f7f8aa89b08f44ad6a87e8ebb1a">error</a> and <a href="/web-llvm/docs/api/namespaces/llvm/#a9a7b5c68c90f85baaedaa854cc5002cc">llvm::errs</a>.</p>


<p>Referenced by <a href="#aa125c88f5418a9e78bd9f1f20b774b08">defaultErrorHandler</a>, <a href="#a59d59f7f8aa89b08f44ad6a87e8ebb1a">error</a>, <a href="/web-llvm/docs/api/classes/llvm/smdiagnostic/#a0653e9bbc6598528d50ec97cad565b74">llvm::SMDiagnostic::print</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a37310d4cb640733ed81281942c314d05">llvm::PrintError</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a98e0a088275cce1befcf07fb2f9debff">llvm::PrintError</a>, <a href="/web-llvm/docs/api/classes/llvm/dwarf-linker/parallel/dependencytracker/#a066fd5533813e5df6d52cb59fc8afd4e">llvm::dwarf_linker::parallel::DependencyTracker::verifyKeepChain</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a02b44f93159b4b08e7998a4fb4d7705f">llvm::verifyKeepChain</a> and <a href="/web-llvm/docs/api/files/lib/lib/objectyaml/coffemitter-cpp/#ab42bb96f4eedf10f2f2437b807a77f8b">writeCOFF</a>.</p>

</div>
</div>

### error() {#a5254e7538d6a07134ed56800efc14a39}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">raw_ostream &amp; WithColor::error (<a href="/web-llvm/docs/api/classes/llvm/raw-ostream">raw_ostream</a> &amp; OS, <a href="/web-llvm/docs/api/classes/llvm/stringref">StringRef</a> Prefix="", bool DisableColors=false)</td>
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

<p>Convenience method for printing "error: " to the given stream.</p>

<p>Declaration at line 100 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/support/withcolor-h">WithColor.h</a>, definition at line 91 of file <a href="/web-llvm/docs/api/files/lib/lib/support/withcolor-cpp">WithColor.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/namespaces/llvm/#afdccf3ff7a8dfaa084b07c1fb417bbe2a06b9281e396db002010bde1de57262eb">llvm::Auto</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#afdccf3ff7a8dfaa084b07c1fb417bbe2abcfaccebf745acfd5e75351095a5394a">llvm::Disable</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#ac226f3d2b9ca090171a8e0a8cb92c343a902b0d55fddef6f8d651fe1035b7d4bd">llvm::Error</a> and <a href="#a0b7d62735f94b418859340f4949299bf">WithColor</a>.</p>

</div>
</div>

### note() {#ab5313a760f20fc53b44cc8dbabfd1ae1}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">raw_ostream &amp; WithColor::note ()</td>
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

<p>Convenience method for printing "note: " to stderr.</p>

<p>Declaration at line 95 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/support/withcolor-h">WithColor.h</a>, definition at line 87 of file <a href="/web-llvm/docs/api/files/lib/lib/support/withcolor-cpp">WithColor.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/namespaces/llvm/#a9a7b5c68c90f85baaedaa854cc5002cc">llvm::errs</a> and <a href="#ab5313a760f20fc53b44cc8dbabfd1ae1">note</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/namespaces/llvm/mca/#a65c7a8ebc9a13366a19e1573563cbe0c">llvm::mca::initializeUsedResources</a>, <a href="#ab5313a760f20fc53b44cc8dbabfd1ae1">note</a>, <a href="/web-llvm/docs/api/classes/llvm/smdiagnostic/#a0653e9bbc6598528d50ec97cad565b74">llvm::SMDiagnostic::print</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a8a905581e928850b24011d053170d423">llvm::PrintNote</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#aab10f4d4b95e7f071fe9eb2875559234">llvm::PrintNote</a> and <a href="/web-llvm/docs/api/namespaces/llvm/cgdata/#a491b7adc108c1d48b21caa972d15ba0c">llvm::cgdata::warn</a>.</p>

</div>
</div>

### note() {#a028b04cefc83e8374898708f803b0242}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">raw_ostream &amp; WithColor::note (<a href="/web-llvm/docs/api/classes/llvm/raw-ostream">raw_ostream</a> &amp; OS, <a href="/web-llvm/docs/api/classes/llvm/stringref">StringRef</a> Prefix="", bool DisableColors=false)</td>
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

<p>Convenience method for printing "note: " to the given stream.</p>

<p>Declaration at line 106 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/support/withcolor-h">WithColor.h</a>, definition at line 111 of file <a href="/web-llvm/docs/api/files/lib/lib/support/withcolor-cpp">WithColor.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/namespaces/llvm/#afdccf3ff7a8dfaa084b07c1fb417bbe2a06b9281e396db002010bde1de57262eb">llvm::Auto</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#afdccf3ff7a8dfaa084b07c1fb417bbe2abcfaccebf745acfd5e75351095a5394a">llvm::Disable</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#ac226f3d2b9ca090171a8e0a8cb92c343a3b0649c72650c313a357338dcdfb64ec">llvm::Note</a> and <a href="#a0b7d62735f94b418859340f4949299bf">WithColor</a>.</p>

</div>
</div>

### remark() {#afdcd08052180c0b87e06a2808b062c01}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">raw_ostream &amp; WithColor::remark ()</td>
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

<p>Convenience method for printing "remark: " to stderr.</p>

<p>Declaration at line 97 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/support/withcolor-h">WithColor.h</a>, definition at line 89 of file <a href="/web-llvm/docs/api/files/lib/lib/support/withcolor-cpp">WithColor.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/namespaces/llvm/#a9a7b5c68c90f85baaedaa854cc5002cc">llvm::errs</a> and <a href="#afdcd08052180c0b87e06a2808b062c01">remark</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/classes/llvm/smdiagnostic/#a0653e9bbc6598528d50ec97cad565b74">llvm::SMDiagnostic::print</a> and <a href="#afdcd08052180c0b87e06a2808b062c01">remark</a>.</p>

</div>
</div>

### remark() {#a9f22bc56f93bc45e4dbd5ecf1daa1746}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">raw_ostream &amp; WithColor::remark (<a href="/web-llvm/docs/api/classes/llvm/raw-ostream">raw_ostream</a> &amp; OS, <a href="/web-llvm/docs/api/classes/llvm/stringref">StringRef</a> Prefix="", bool DisableColors=false)</td>
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

<p>Convenience method for printing "remark: " to the given stream.</p>

<p>Declaration at line 109 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/support/withcolor-h">WithColor.h</a>, definition at line 121 of file <a href="/web-llvm/docs/api/files/lib/lib/support/withcolor-cpp">WithColor.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/namespaces/llvm/#afdccf3ff7a8dfaa084b07c1fb417bbe2a06b9281e396db002010bde1de57262eb">llvm::Auto</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#afdccf3ff7a8dfaa084b07c1fb417bbe2abcfaccebf745acfd5e75351095a5394a">llvm::Disable</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#ac226f3d2b9ca090171a8e0a8cb92c343a91921ada405fd6ba65dff028df047cb6">llvm::Remark</a> and <a href="#a0b7d62735f94b418859340f4949299bf">WithColor</a>.</p>

</div>
</div>

### setAutoDetectFunction() {#ad8a533ac5cd1bd14e1999bab57a7c863}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void WithColor::setAutoDetectFunction (<a href="#a5f76e2d718b584bd59ec66a543c72751">AutoDetectFunctionType</a> NewAutoDetectFunction)</td>
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

<p>Change the global auto detection function.</p>

<p>Declaration at line 140 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/support/withcolor-h">WithColor.h</a>, definition at line 174 of file <a href="/web-llvm/docs/api/files/lib/lib/support/withcolor-cpp">WithColor.cpp</a>.</p>

</div>
</div>

### warning() {#a237ad6eae22f6b2746a542c02d309a5b}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">raw_ostream &amp; WithColor::warning ()</td>
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

<p>Convenience method for printing "warning: " to stderr.</p>

<p>Declaration at line 93 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/support/withcolor-h">WithColor.h</a>, definition at line 85 of file <a href="/web-llvm/docs/api/files/lib/lib/support/withcolor-cpp">WithColor.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/namespaces/llvm/#a9a7b5c68c90f85baaedaa854cc5002cc">llvm::errs</a> and <a href="#a237ad6eae22f6b2746a542c02d309a5b">warning</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/classes/llvm/targetpassconfig/#a821092b65a0bd12e6aab341164fd4e93">llvm::TargetPassConfig::addMachinePasses</a>, <a href="#a0ab9ce7767ba8ad9a3cb17cd35d81a1f">defaultWarningHandler</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#ae37fdf2c48e64e5ec89afa5a44774e99">llvm::getHeaders</a>, <a href="/web-llvm/docs/api/namespaces/llvm/mca/#a65c7a8ebc9a13366a19e1573563cbe0c">llvm::mca::initializeUsedResources</a>, <a href="/web-llvm/docs/api/namespaces/anonymous-basicblockpathcloning-cpp-/#abbaff7e4a8cdaa59924d29ba6e305f4a">anonymous{BasicBlockPathCloning.cpp}::IsValidCloning</a>, <a href="/web-llvm/docs/api/classes/llvm/smdiagnostic/#a0653e9bbc6598528d50ec97cad565b74">llvm::SMDiagnostic::print</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a642c8e7f7e73fb7e5ab61bff641886f4">llvm::PrintWarning</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#aabba6d27907082520ad2eb977c8e406b">llvm::pruneCache</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a916e9619e70faa6bc1f4daf0c21292c5">llvm::reportInvalidSizeRequest</a>, <a href="/web-llvm/docs/api/namespaces/llvm/cgdata/#a491b7adc108c1d48b21caa972d15ba0c">llvm::cgdata::warn</a> and <a href="#a237ad6eae22f6b2746a542c02d309a5b">warning</a>.</p>

</div>
</div>

### warning() {#ade51780899828c5352637d84d847a2b1}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">raw_ostream &amp; WithColor::warning (<a href="/web-llvm/docs/api/classes/llvm/raw-ostream">raw_ostream</a> &amp; OS, <a href="/web-llvm/docs/api/classes/llvm/stringref">StringRef</a> Prefix="", bool DisableColors=false)</td>
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

<p>Convenience method for printing "warning: " to the given stream.</p>

<p>Declaration at line 103 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/support/withcolor-h">WithColor.h</a>, definition at line 101 of file <a href="/web-llvm/docs/api/files/lib/lib/support/withcolor-cpp">WithColor.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/namespaces/llvm/#afdccf3ff7a8dfaa084b07c1fb417bbe2a06b9281e396db002010bde1de57262eb">llvm::Auto</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#afdccf3ff7a8dfaa084b07c1fb417bbe2abcfaccebf745acfd5e75351095a5394a">llvm::Disable</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#ac226f3d2b9ca090171a8e0a8cb92c343a0eaadb4fcb48a0a0ed7bc9868be9fbaa">llvm::Warning</a> and <a href="#a0b7d62735f94b418859340f4949299bf">WithColor</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Private Static Attributes

### AutoDetectFunction {#a3c8b0e65081603ac3d45c22953d0f227}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">WithColor::AutoDetectFunctionType WithColor::AutoDetectFunction</td>
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
<dt>Initialiser</dt>
<dd>
<div class="doxyVerbatim">=
    <a href="/web-llvm/docs/api/files/lib/lib/support/withcolor-cpp/#a217ca6e38806a2d0ea3712d69c0b06f6">DefaultAutoDetectFunction</a>
</div>
</dd>
</dl>

<p>Definition at line 146 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/support/withcolor-h">WithColor.h</a>.</p>

</div>
</div>

</div>

<hr/>

The documentation for this class was generated from the following files:

<ul>
<li><a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/support/withcolor-h">WithColor.h</a></li>
<li><a href="/web-llvm/docs/api/files/lib/lib/support/withcolor-cpp">WithColor.cpp</a></li>
</ul>

<hr/>

<p class="doxyGeneratedBy">Generated via <a href="https://github.com/xpack/doxygen2docusaurus">doxygen2docusaurus</a> by <a href="https://www.doxygen.nl">Doxygen</a> 1.15.0.</p>

</div>
