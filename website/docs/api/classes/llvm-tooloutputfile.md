---

# DO NOT EDIT!
# Automatically generated via doxygen2docusaurus by Doxygen.

slug: /api/classes/llvm/tooloutputfile
custom_edit_url: null
toc_max_heading_level: 4
keywords:
  - doxygen
  - reference
  - class

---

<div class="doxyPage">

# `ToolOutputFile` Class

<p>This class contains a <a href="/web-llvm/docs/api/classes/llvm/raw-fd-ostream">raw_fd_ostream</a> and adds a few extra features commonly needed for compiler-like tool output files: <a href="#details">More...</a></p>

## Declaration

<div class="doxyDeclaration">
class llvm::ToolOutputFile { ... }
</div>

## Included Headers

<div class="doxyIncludesList">#include "<a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/support/tooloutputfile-h">llvm/Support/ToolOutputFile.h</a>"
</div>

## Public Constructors Index

<table class="doxyMembersIndex">

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#aa8a96aefbfc916ad99ab353e418f79d7">ToolOutputFile</a> (StringRef Filename, std::error_code &amp;EC, sys::fs::OpenFlags Flags)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>This constructor's arguments are passed to <a href="/web-llvm/docs/api/classes/llvm/raw-fd-ostream">raw_fd_ostream</a>'s constructor. <a href="#aa8a96aefbfc916ad99ab353e418f79d7">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#aa127e0fb1a98579c7beefba26a158d47">ToolOutputFile</a> (StringRef Filename, int FD)</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/raw-fd-ostream">raw_fd_ostream</a> &amp;</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#afd739434d6e7e26f93a9e87c23e4e7a3">os</a> ()</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Return the contained <a href="/web-llvm/docs/api/classes/llvm/raw-fd-ostream">raw_fd_ostream</a>. <a href="#afd739434d6e7e26f93a9e87c23e4e7a3">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/stringref">StringRef</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#af02008b66e30ded00be776da162139bd">getFilename</a> ()</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Return the filename initialized with. <a href="#af02008b66e30ded00be776da162139bd">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">void</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a736bcda698a82e4ae3a92310d706868d">keep</a> ()</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Indicate that the tool's job wrt this output file has been successful and the file should not be deleted. <a href="#a736bcda698a82e4ae3a92310d706868d">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> std::string &amp;</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a56ad3912abad8031d0c157e8afbedcbd">outputFilename</a> ()</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/cleanupinstaller">CleanupInstaller</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a5f8cb5ad0f072fd2c14be5c2e271aaca">Installer</a></td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>This class is declared before the <a href="/web-llvm/docs/api/classes/llvm/raw-fd-ostream">raw_fd_ostream</a> so that it is constructed before the <a href="/web-llvm/docs/api/classes/llvm/raw-fd-ostream">raw_fd_ostream</a> is constructed and destructed after the <a href="/web-llvm/docs/api/classes/llvm/raw-fd-ostream">raw_fd_ostream</a> is destructed. <a href="#a5f8cb5ad0f072fd2c14be5c2e271aaca">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">std::optional&lt; <a href="/web-llvm/docs/api/classes/llvm/raw-fd-ostream">raw_fd_ostream</a> &gt;</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#adee6a8935097a79e0c91d9aeb5f48777">OSHolder</a></td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Storage for the stream, if we're owning our own stream. <a href="#adee6a8935097a79e0c91d9aeb5f48777">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/raw-fd-ostream">raw_fd_ostream</a> *</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a253eb69060aac6dfd3a7e204a968f9c7">OS</a></td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>The actual stream to use. <a href="#a253eb69060aac6dfd3a7e204a968f9c7">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

</table>

## Description {#details}

<p>This class contains a <a href="/web-llvm/docs/api/classes/llvm/raw-fd-ostream">raw_fd_ostream</a> and adds a few extra features commonly needed for compiler-like tool output files:</p>


<ul class="doxyList ">
<li>The file is automatically deleted if the process is killed.</li>
<li>The file is automatically deleted when the <a href="/web-llvm/docs/api/classes/llvm/tooloutputfile">ToolOutputFile</a> object is destroyed unless the client calls <a href="#a736bcda698a82e4ae3a92310d706868d">keep()</a>.</li>
</ul>

<p>Definition at line 39 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/support/tooloutputfile-h">ToolOutputFile.h</a>.</p>


<div class="doxySectionDef">

## Public Constructors

### ToolOutputFile() {#aa8a96aefbfc916ad99ab353e418f79d7}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">ToolOutputFile::ToolOutputFile (<a href="/web-llvm/docs/api/classes/llvm/stringref">StringRef</a> Filename, std::error_code &amp; EC, <a href="/web-llvm/docs/api/namespaces/llvm/sys/fs/#a662978c0cdf81de0d448032f142a3695">sys::fs::OpenFlags</a> Flags)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>This constructor's arguments are passed to <a href="/web-llvm/docs/api/classes/llvm/raw-fd-ostream">raw_fd_ostream</a>'s constructor.</p>

<p>Declaration at line 56 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/support/tooloutputfile-h">ToolOutputFile.h</a>, definition at line 40 of file <a href="/web-llvm/docs/api/files/lib/lib/support/tooloutputfile-cpp">ToolOutputFile.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/files/lib/lib/support/tooloutputfile-cpp/#a718b79f3760a7f4b55a872176f9ee8d8">isStdout</a> and <a href="/web-llvm/docs/api/namespaces/llvm/#a2d79a00fa7c56f57b87f2fe2a3f118c7">llvm::outs</a>.</p>

</div>
</div>

### ToolOutputFile() {#aa127e0fb1a98579c7beefba26a158d47}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">ToolOutputFile::ToolOutputFile (<a href="/web-llvm/docs/api/classes/llvm/stringref">StringRef</a> Filename, int FD)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Declaration at line 59 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/support/tooloutputfile-h">ToolOutputFile.h</a>, definition at line 55 of file <a href="/web-llvm/docs/api/files/lib/lib/support/tooloutputfile-cpp">ToolOutputFile.cpp</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Public Member Functions

### getFilename() {#af02008b66e30ded00be776da162139bd}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">StringRef llvm::ToolOutputFile::getFilename ()</td>
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

<p>Return the filename initialized with.</p>

<p>Definition at line 65 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/support/tooloutputfile-h">ToolOutputFile.h</a>.</p>

</div>
</div>

### keep() {#a736bcda698a82e4ae3a92310d706868d}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void llvm::ToolOutputFile::keep ()</td>
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

<p>Indicate that the tool's job wrt this output file has been successful and the file should not be deleted.</p>

<p>Definition at line 69 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/support/tooloutputfile-h">ToolOutputFile.h</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/files/lib/lib/tablegen/main-cpp/#a5cdb223afb9f4268a3716aaac56826bd">createDependencyFile</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a969d49f2536556ecd3442e9a8279fe15">llvm::TableGenMain</a> and <a href="/web-llvm/docs/api/structs/llvm/ltocodegenerator/#ae6c084cf21df6bb57da846088680146b">llvm::LTOCodeGenerator::writeMergedModules</a>.</p>

</div>
</div>

### os() {#afd739434d6e7e26f93a9e87c23e4e7a3}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">raw_fd_ostream &amp; llvm::ToolOutputFile::os ()</td>
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

<p>Return the contained <a href="/web-llvm/docs/api/classes/llvm/raw-fd-ostream">raw_fd_ostream</a>.</p>

<p>Definition at line 62 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/support/tooloutputfile-h">ToolOutputFile.h</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/files/lib/lib/tablegen/main-cpp/#a5cdb223afb9f4268a3716aaac56826bd">createDependencyFile</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a969d49f2536556ecd3442e9a8279fe15">llvm::TableGenMain</a> and <a href="/web-llvm/docs/api/structs/llvm/ltocodegenerator/#ae6c084cf21df6bb57da846088680146b">llvm::LTOCodeGenerator::writeMergedModules</a>.</p>

</div>
</div>

### outputFilename() {#a56ad3912abad8031d0c157e8afbedcbd}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">const std::string &amp; llvm::ToolOutputFile::outputFilename ()</td>
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



<p>Definition at line 71 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/support/tooloutputfile-h">ToolOutputFile.h</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Private Member Attributes

### Installer {#a5f8cb5ad0f072fd2c14be5c2e271aaca}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">CleanupInstaller llvm::ToolOutputFile::Installer</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>This class is declared before the <a href="/web-llvm/docs/api/classes/llvm/raw-fd-ostream">raw_fd_ostream</a> so that it is constructed before the <a href="/web-llvm/docs/api/classes/llvm/raw-fd-ostream">raw_fd_ostream</a> is constructed and destructed after the <a href="/web-llvm/docs/api/classes/llvm/raw-fd-ostream">raw_fd_ostream</a> is destructed.</p>


<p>It installs cleanups in its constructor and uninstalls them in its destructor.</p>


<p>Definition at line 44 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/support/tooloutputfile-h">ToolOutputFile.h</a>.</p>

</div>
</div>

### OS {#a253eb69060aac6dfd3a7e204a968f9c7}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">raw_fd_ostream* llvm::ToolOutputFile::OS</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>The actual stream to use.</p>

<p>Definition at line 51 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/support/tooloutputfile-h">ToolOutputFile.h</a>.</p>

</div>
</div>

### OSHolder {#adee6a8935097a79e0c91d9aeb5f48777}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">std::optional&lt;raw_fd_ostream&gt; llvm::ToolOutputFile::OSHolder</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Storage for the stream, if we're owning our own stream.</p>


<p>This is intentionally declared after Installer.</p>


<p>Definition at line 48 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/support/tooloutputfile-h">ToolOutputFile.h</a>.</p>

</div>
</div>

</div>

<hr/>

The documentation for this class was generated from the following files:

<ul>
<li><a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/support/tooloutputfile-h">ToolOutputFile.h</a></li>
<li><a href="/web-llvm/docs/api/files/lib/lib/support/tooloutputfile-cpp">ToolOutputFile.cpp</a></li>
</ul>

<hr/>

<p class="doxyGeneratedBy">Generated via <a href="https://xpack.github.io/doxygen2docusaurus">doxygen2docusaurus</a> 2.0.0 by <a href="https://www.doxygen.nl">Doxygen</a> 1.15.0.</p>

</div>
