---

# DO NOT EDIT!
# Automatically generated via doxygen2docusaurus by Doxygen.

slug: /api/classes/llvm/filecollector
custom_edit_url: null
toc_max_heading_level: 4
keywords:
  - doxygen
  - reference
  - class

---

<div class="doxyPage">

# `FileCollector` Class

<p>Captures file system interaction and generates data to be later replayed with the RedirectingFileSystem. <a href="#details">More...</a></p>

## Declaration

<div class="doxyDeclaration">
class llvm::FileCollector { ... }
</div>

## Included Headers

<div class="doxyIncludesList">#include "<a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/support/filecollector-h">llvm/Support/FileCollector.h</a>"
</div>

## Base class

<table class="doxyMembersIndex">

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">class</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/filecollectorbase">FileCollectorBase</a></td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a2da94c8c4b02f2361f1add04a67b0a47">FileCollector</a> (std::string Root, std::string OverlayRoot)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p><span class="doxyComputerOutput">Root</span> is the directory where collected files are will be stored. <a href="#a2da94c8c4b02f2361f1add04a67b0a47">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

</table>

## Public Member Functions Index

<table class="doxyMembersIndex">

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">std::error_code</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a139707bb03616dd63549f3734ce8a71a">writeMapping</a> (StringRef MappingFile)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Write the yaml mapping (for the VFS) to the given file. <a href="#a139707bb03616dd63549f3734ce8a71a">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">std::error_code</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a71730785a9649e84e7680eaf77d0095c">copyFiles</a> (bool StopOnError=true)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Copy the files into the root directory. <a href="#a71730785a9649e84e7680eaf77d0095c">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

</table>

## Protected Member Functions Index

<table class="doxyMembersIndex">

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">void</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ace0419c07a92964cb26904561edc7203">addFileImpl</a> (StringRef SrcPath) override</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/vfs/directory-iterator">llvm::vfs::directory_iterator</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a045f98bf82edccad8ca80e5a233584a7">addDirectoryImpl</a> (const llvm::Twine &amp;Dir, IntrusiveRefCntPtr&lt; vfs::FileSystem &gt; FS, std::error_code &amp;EC) override</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">void</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a5562f23f45b2c3112dc8e172306e536b">addFileToMapping</a> (StringRef VirtualPath, StringRef RealPath)</td>
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

## Protected Member Attributes Index

<table class="doxyMembersIndex">

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> std::string</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#aace40749449142a325fdad80ea0d6611">Root</a></td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>The directory where collected files are copied to in <a href="#a71730785a9649e84e7680eaf77d0095c">copyFiles()</a>. <a href="#aace40749449142a325fdad80ea0d6611">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> std::string</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a84f5443c248164ed63e454ea00ecb356">OverlayRoot</a></td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>The root directory where the VFS overlay lives. <a href="#a84f5443c248164ed63e454ea00ecb356">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/vfs/yamlvfswriter">vfs::YAMLVFSWriter</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ac8c37afef3ccf4635d955de9b09b4480">VFSWriter</a></td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>The yaml mapping writer. <a href="#ac8c37afef3ccf4635d955de9b09b4480">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/filecollector/pathcanonicalizer">PathCanonicalizer</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a87ed48aba24052e1fffbca44b37fe6a6">Canonicalizer</a></td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Helper utility for canonicalizing paths. <a href="#a87ed48aba24052e1fffbca44b37fe6a6">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

</table>

## Private Member Attributes Index

<table class="doxyMembersIndex">

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">friend</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a7192f778f7c5c4da705b3da8e52c7129">FileCollectorFileSystem</a></td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">static <a href="/web-llvm/docs/api/classes/llvm/intrusiverefcntptr">IntrusiveRefCntPtr</a>&lt; <a href="/web-llvm/docs/api/classes/llvm/vfs/filesystem">vfs::FileSystem</a> &gt;</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#aef90d74b908382e0d81ae5ba389471dc">createCollectorVFS</a> (IntrusiveRefCntPtr&lt; vfs::FileSystem &gt; BaseFS, std::shared_ptr&lt; FileCollector &gt; Collector)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Create a VFS that uses <span class="doxyComputerOutput">Collector</span> to collect files accessed via <span class="doxyComputerOutput">BaseFS</span>. <a href="#aef90d74b908382e0d81ae5ba389471dc">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

</table>

## Description {#details}

<p>Captures file system interaction and generates data to be later replayed with the RedirectingFileSystem.</p>


<p>For any file that gets accessed we eventually create:</p>


<ul class="doxyList ">
<li>a copy of the file inside Root</li>
<li>a record in RedirectingFileSystem mapping that maps: current real path -&gt; path to the copy in Root</li>
</ul>

<p>That intent is that later when the mapping is used by RedirectingFileSystem it simulates the state of FS that we collected.</p>


<p>We generate file copies and mapping lazily - see writeMapping and copyFiles. We don't try to capture the state of the file at the exact time when it's accessed. Files might get changed, deleted ... we record only the "final" state.</p>


<p>In order to preserve the relative topology of files we use their real paths as relative paths inside of the Root.</p>


<p>Definition at line 69 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/support/filecollector-h">FileCollector.h</a>.</p>


<div class="doxySectionDef">

## Public Constructors

### FileCollector() {#a2da94c8c4b02f2361f1add04a67b0a47}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">FileCollector::FileCollector (std::string Root, std::string OverlayRoot)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p><span class="doxyComputerOutput">Root</span> is the directory where collected files are will be stored.</p>


<p><span class="doxyComputerOutput">OverlayRoot</span> is VFS mapping root. <span class="doxyComputerOutput">Root</span> directory gets created in copyFiles unless it already exists.</p>


<p>Declaration at line 95 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/support/filecollector-h">FileCollector.h</a>, definition at line 52 of file <a href="/web-llvm/docs/api/files/lib/lib/support/filecollector-cpp">FileCollector.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/silowercontrolflow-cpp/#a4868c5d81c5ccc98c47aeab6244346a0">assert</a>, <a href="/web-llvm/docs/api/namespaces/llvm/sys/path/#ac35ec1dacb408d4c65d55249c0e02474">llvm::sys::path::is_absolute</a>, <a href="#a84f5443c248164ed63e454ea00ecb356">OverlayRoot</a> and <a href="#aace40749449142a325fdad80ea0d6611">Root</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Public Member Functions

### copyFiles() {#a71730785a9649e84e7680eaf77d0095c}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">std::error_code FileCollector::copyFiles (bool StopOnError=<a href="/web-llvm/docs/api/files/lib/lib/analysis/basicaliasanalysis-cpp/#af6d5cafbdfc5313e65d990120021a3ec">true</a>)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Copy the files into the root directory.</p>


<p>When StopOnError is true (the default) we abort as soon as one file cannot be copied. This is relatively common, for example when a file was removed after it was added to the mapping.</p>


<p>Declaration at line 105 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/support/filecollector-h">FileCollector.h</a>, definition at line 178 of file <a href="/web-llvm/docs/api/files/lib/lib/support/filecollector-cpp">FileCollector.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/namespaces/llvm/sys/fs/#abe768b38d21bfc2bc91a1c1d09cd84de">llvm::sys::fs::copy_file</a>, <a href="/web-llvm/docs/api/files/lib/lib/support/filecollector-cpp/#a1f7c3aa9196e89483c3ad89f2718dec3">copyAccessAndModificationTime</a>, <a href="/web-llvm/docs/api/namespaces/llvm/sys/fs/#ab0231205adf0a10ac89540dbcfdcd2d7">llvm::sys::fs::create_directories</a>, <a href="/web-llvm/docs/api/namespaces/llvm/sys/fs/#a6c50be965db24d7532b6b4e6b0755f5ca1c3e56917e1b64d1874d5d88c085e0c9">llvm::sys::fs::directory_file</a>, <a href="/web-llvm/docs/api/namespaces/llvm/sys/fs/#a6c50be965db24d7532b6b4e6b0755f5ca4cbd4f831bcb7891ccf9a70c3957cf49">llvm::sys::fs::file_not_found</a>, <a href="/web-llvm/docs/api/namespaces/llvm/sys/fs/#a3557ebbcffdf16638e216d7f06d900a5">llvm::sys::fs::getPermissions</a>, <a href="/web-llvm/docs/api/classes/llvm/filecollectorbase/#a0806e58da61ce291d83268f8c6182931">llvm::FileCollectorBase::Mutex</a>, <a href="/web-llvm/docs/api/namespaces/llvm/sys/path/#a5326427c87607b2364a1fcdf13fa0eea">llvm::sys::path::parent_path</a>, <a href="#aace40749449142a325fdad80ea0d6611">Root</a>, <a href="/web-llvm/docs/api/namespaces/llvm/sys/fs/#aed67578bdddc4f087b10f1bc9cbaab88">llvm::sys::fs::setPermissions</a>, <a href="/web-llvm/docs/api/namespaces/llvm/sys/fs/#a5f126cc7b64d31cd709215b48656d83d">llvm::sys::fs::status</a>, <a href="/web-llvm/docs/api/classes/llvm/sys/fs/basic-file-status/#ab01b92f53a9f931c5859498219da2613">llvm::sys::fs::basic_file_status::type</a> and <a href="#ac8c37afef3ccf4635d955de9b09b4480">VFSWriter</a>.</p>

</div>
</div>

### writeMapping() {#a139707bb03616dd63549f3734ce8a71a}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">std::error_code FileCollector::writeMapping (<a href="/web-llvm/docs/api/classes/llvm/stringref">StringRef</a> MappingFile)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Write the yaml mapping (for the VFS) to the given file.</p>

<p>Declaration at line 98 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/support/filecollector-h">FileCollector.h</a>, definition at line 238 of file <a href="/web-llvm/docs/api/files/lib/lib/support/filecollector-cpp">FileCollector.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/files/lib/lib/support/filecollector-cpp/#a6f06f095d55bf5da7adfd285f8b0e6ff">isCaseSensitivePath</a>, <a href="/web-llvm/docs/api/classes/llvm/filecollectorbase/#a0806e58da61ce291d83268f8c6182931">llvm::FileCollectorBase::Mutex</a>, <a href="/web-llvm/docs/api/namespaces/llvm/sys/fs/#a662978c0cdf81de0d448032f142a3695ab505c2c79499fbe180989bffbf108a50">llvm::sys::fs::OF_TextWithCRLF</a>, <a href="#a84f5443c248164ed63e454ea00ecb356">OverlayRoot</a> and <a href="#ac8c37afef3ccf4635d955de9b09b4480">VFSWriter</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Protected Member Functions

### addDirectoryImpl() {#a045f98bf82edccad8ca80e5a233584a7}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">llvm::vfs::directory_iterator FileCollector::addDirectoryImpl (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/twine">llvm::Twine</a> &amp; Dir, <a href="/web-llvm/docs/api/classes/llvm/intrusiverefcntptr">IntrusiveRefCntPtr</a>&lt; <a href="/web-llvm/docs/api/classes/llvm/vfs/filesystem">vfs::FileSystem</a> &gt; FS, std::error_code &amp; EC)</td>
</tr>
</table>
</td>
<td class="doxyMemberLabelsRight">
<span class="doxyMemberLabels">
<span class="doxyMemberLabel protected">protected</span>
<span class="doxyMemberLabel virtual">virtual</span>
</span>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Declaration at line 127 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/support/filecollector-h">FileCollector.h</a>, definition at line 137 of file <a href="/web-llvm/docs/api/files/lib/lib/support/filecollector-cpp">FileCollector.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/classes/llvm/filecollectorbase/#a53d29d37b72f5187d31c14d52eb656e7">llvm::FileCollectorBase::addFile</a>, <a href="/web-llvm/docs/api/namespaces/llvm/sys/fs/#a6c50be965db24d7532b6b4e6b0755f5ca1c3e56917e1b64d1874d5d88c085e0c9">llvm::sys::fs::directory_file</a>, <a href="/web-llvm/docs/api/namespaces/llvm/sys/fs/#a6c50be965db24d7532b6b4e6b0755f5ca4676601564b208338edf7317182f473e">llvm::sys::fs::regular_file</a> and <a href="/web-llvm/docs/api/namespaces/llvm/sys/fs/#a6c50be965db24d7532b6b4e6b0755f5cad978ac65911e3b23055a644703f89615">llvm::sys::fs::symlink_file</a>.</p>

</div>
</div>

### addFileImpl() {#ace0419c07a92964cb26904561edc7203}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void FileCollector::addFileImpl (<a href="/web-llvm/docs/api/classes/llvm/stringref">StringRef</a> SrcPath)</td>
</tr>
</table>
</td>
<td class="doxyMemberLabelsRight">
<span class="doxyMemberLabels">
<span class="doxyMemberLabel protected">protected</span>
<span class="doxyMemberLabel virtual">virtual</span>
</span>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Declaration at line 124 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/support/filecollector-h">FileCollector.h</a>, definition at line 122 of file <a href="/web-llvm/docs/api/files/lib/lib/support/filecollector-cpp">FileCollector.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/namespaces/llvm/sys/path/#acb80894344c78dacf8d5ff8c23be697d">llvm::sys::path::append</a>, <a href="#a87ed48aba24052e1fffbca44b37fe6a6">Canonicalizer</a>, <a href="/web-llvm/docs/api/namespaces/llvm/sys/path/#af426cbaa47678fc354ad421fb67e180e">llvm::sys::path::relative_path</a> and <a href="#aace40749449142a325fdad80ea0d6611">Root</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Private Member Functions

### addFileToMapping() {#a5562f23f45b2c3112dc8e172306e536b}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void llvm::FileCollector::addFileToMapping (<a href="/web-llvm/docs/api/classes/llvm/stringref">StringRef</a> VirtualPath, <a href="/web-llvm/docs/api/classes/llvm/stringref">StringRef</a> RealPath)</td>
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



<p>Definition at line 116 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/support/filecollector-h">FileCollector.h</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Protected Member Attributes

### Canonicalizer {#a87ed48aba24052e1fffbca44b37fe6a6}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">PathCanonicalizer llvm::FileCollector::Canonicalizer</td>
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

<p>Helper utility for canonicalizing paths.</p>

<p>Definition at line 141 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/support/filecollector-h">FileCollector.h</a>.</p>


<p>Referenced by <a href="#ace0419c07a92964cb26904561edc7203">addFileImpl</a>.</p>

</div>
</div>

### OverlayRoot {#a84f5443c248164ed63e454ea00ecb356}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">const std::string llvm::FileCollector::OverlayRoot</td>
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

<p>The root directory where the VFS overlay lives.</p>

<p>Definition at line 135 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/support/filecollector-h">FileCollector.h</a>.</p>


<p>Referenced by <a href="#a2da94c8c4b02f2361f1add04a67b0a47">FileCollector</a> and <a href="#a139707bb03616dd63549f3734ce8a71a">writeMapping</a>.</p>

</div>
</div>

### Root {#aace40749449142a325fdad80ea0d6611}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">const std::string llvm::FileCollector::Root</td>
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

<p>The directory where collected files are copied to in <a href="#a71730785a9649e84e7680eaf77d0095c">copyFiles()</a>.</p>

<p>Definition at line 132 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/support/filecollector-h">FileCollector.h</a>.</p>


<p>Referenced by <a href="#ace0419c07a92964cb26904561edc7203">addFileImpl</a>, <a href="#a71730785a9649e84e7680eaf77d0095c">copyFiles</a> and <a href="#a2da94c8c4b02f2361f1add04a67b0a47">FileCollector</a>.</p>

</div>
</div>

### VFSWriter {#ac8c37afef3ccf4635d955de9b09b4480}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">vfs::YAMLVFSWriter llvm::FileCollector::VFSWriter</td>
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

<p>The yaml mapping writer.</p>

<p>Definition at line 138 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/support/filecollector-h">FileCollector.h</a>.</p>


<p>Referenced by <a href="#a71730785a9649e84e7680eaf77d0095c">copyFiles</a> and <a href="#a139707bb03616dd63549f3734ce8a71a">writeMapping</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Private Member Attributes

### FileCollectorFileSystem {#a7192f778f7c5c4da705b3da8e52c7129}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">friend llvm::FileCollector::FileCollectorFileSystem</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 114 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/support/filecollector-h">FileCollector.h</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Public Static Functions

### createCollectorVFS() {#aef90d74b908382e0d81ae5ba389471dc}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">IntrusiveRefCntPtr&lt; vfs::FileSystem &gt; FileCollector::createCollectorVFS (<a href="/web-llvm/docs/api/classes/llvm/intrusiverefcntptr">IntrusiveRefCntPtr</a>&lt; <a href="/web-llvm/docs/api/classes/llvm/vfs/filesystem">vfs::FileSystem</a> &gt; BaseFS, std::shared_ptr&lt; <a href="/web-llvm/docs/api/classes/llvm/filecollector">FileCollector</a> &gt; Collector)</td>
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

<p>Create a VFS that uses <span class="doxyComputerOutput">Collector</span> to collect files accessed via <span class="doxyComputerOutput">BaseFS</span>.</p>

<p>Declaration at line 110 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/support/filecollector-h">FileCollector.h</a>, definition at line 314 of file <a href="/web-llvm/docs/api/files/lib/lib/support/filecollector-cpp">FileCollector.cpp</a>.</p>


<p>Reference <a href="/web-llvm/docs/api/files/lib/lib/codegen/regusageinfocollector-cpp/#a56152063c87e42d184c62fab1f3b0481">Collector</a>.</p>

</div>
</div>

</div>

<hr/>

The documentation for this class was generated from the following files:

<ul>
<li><a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/support/filecollector-h">FileCollector.h</a></li>
<li><a href="/web-llvm/docs/api/files/lib/lib/support/filecollector-cpp">FileCollector.cpp</a></li>
</ul>

<hr/>

<p class="doxyGeneratedBy">Generated via <a href="https://xpack.github.io/doxygen2docusaurus">doxygen2docusaurus</a> 2.0.0 by <a href="https://www.doxygen.nl">Doxygen</a> 1.15.0.</p>

</div>
