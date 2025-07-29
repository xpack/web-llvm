---

# DO NOT EDIT!
# Automatically generated via doxygen2docusaurus by Doxygen.

slug: /api/files/lib/lib/support/filecollector-cpp
custom_edit_url: null
toc_max_heading_level: 4
keywords:
  - doxygen
  - reference
  - file

---

<div class="doxyPage">

# `FileCollector.cpp` File



## Included Headers

<div class="doxyIncludesList">#include "<a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/support/filecollector-h">llvm/Support/FileCollector.h</a>"
#include "<a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/adt/smallstring-h">llvm/ADT/SmallString.h</a>"
#include "<a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/adt/twine-h">llvm/ADT/Twine.h</a>"
#include "<a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/support/filesystem-h">llvm/Support/FileSystem.h</a>"
#include "<a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/support/path-h">llvm/Support/Path.h</a>"
#include "<a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/support/process-h">llvm/Support/Process.h</a>"
</div>

## Namespaces Index

<table class="doxyMembersIndex">

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">namespace</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="/web-llvm/docs/api/namespaces/llvm">llvm</a></td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>This is an optimization pass for GlobalISel generic memory operations. <a href="/web-llvm/docs/api/namespaces/llvm/#details">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

</table>

## Classes Index

<table class="doxyMembersIndex">

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">class</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/filecollectorfilesystem">FileCollectorFileSystem</a></td>
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

## Functions Index

<table class="doxyMembersIndex">

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">static bool</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a6f06f095d55bf5da7adfd285f8b0e6ff">isCaseSensitivePath</a> (StringRef Path)</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">static void</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a20bab096e3719810afee546ab46997c3">makeAbsolute</a> (SmallVectorImpl&lt; char &gt; &amp;Path)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Make Path absolute. <a href="#a20bab096e3719810afee546ab46997c3">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">static std::error_code</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a1f7c3aa9196e89483c3ad89f2718dec3">copyAccessAndModificationTime</a> (StringRef Filename, const sys::fs::file_status &amp;Stat)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Set the access and modification time for the given file from the given status object. <a href="#a1f7c3aa9196e89483c3ad89f2718dec3">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

</table>


<div class="doxySectionDef">

## Functions

### copyAccessAndModificationTime() {#a1f7c3aa9196e89483c3ad89f2718dec3}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">std::error_code copyAccessAndModificationTime (<a href="/web-llvm/docs/api/classes/llvm/stringref">StringRef</a> Filename, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/sys/fs/file-status">sys::fs::file_status</a> &amp; Stat)</td>
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

<p>Set the access and modification time for the given file from the given status object.</p>

<p>Definition at line 160 of file <a href="/web-llvm/docs/api/files/lib/lib/support/filecollector-cpp">FileCollector.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/namespaces/llvm/sys/fs/#a93918b3a9b70253cd229fc5864884f58a028d2e48ae4e6c34d4a5bbb70438a936">llvm::sys::fs::CD_OpenExisting</a>, <a href="/web-llvm/docs/api/classes/llvm/sys/fs/basic-file-status/#ab258586eab700df6cf494d52dc282e91">llvm::sys::fs::basic_file_status::getLastAccessedTime</a>, <a href="/web-llvm/docs/api/classes/llvm/sys/fs/basic-file-status/#ae807b50b0b414d8a9195cdc0ee23b86a">llvm::sys::fs::basic_file_status::getLastModificationTime</a>, <a href="/web-llvm/docs/api/namespaces/llvm/sys/fs/#aaa20e3a6a1473b383695503e0b5eb871">llvm::sys::fs::openFileForWrite</a>, <a href="/web-llvm/docs/api/classes/llvm/sys/process/#a0777b5060c78b24c4765fffbac259f93">llvm::sys::Process::SafelyCloseFileDescriptor</a> and <a href="/web-llvm/docs/api/namespaces/llvm/sys/fs/#a35f16bd8439efd3c629fdc6e7b6cb039">llvm::sys::fs::setLastAccessAndModificationTime</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/classes/llvm/filecollector/#a71730785a9649e84e7680eaf77d0095c">llvm::FileCollector::copyFiles</a>.</p>

</div>
</div>

### isCaseSensitivePath() {#a6f06f095d55bf5da7adfd285f8b0e6ff}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool isCaseSensitivePath (<a href="/web-llvm/docs/api/classes/llvm/stringref">StringRef</a> Path)</td>
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



<p>Definition at line 34 of file <a href="/web-llvm/docs/api/files/lib/lib/support/filecollector-cpp">FileCollector.cpp</a>.</p>


<p>Reference <a href="/web-llvm/docs/api/namespaces/llvm/sys/fs/#a2363fbfbd0a348f5d81fc3d3223ecae3">llvm::sys::fs::real_path</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/classes/llvm/filecollector/#a139707bb03616dd63549f3734ce8a71a">llvm::FileCollector::writeMapping</a>.</p>

</div>
</div>

### makeAbsolute() {#a20bab096e3719810afee546ab46997c3}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void makeAbsolute (<a href="/web-llvm/docs/api/classes/llvm/smallvectorimpl">SmallVectorImpl</a>&lt; char &gt; &amp; Path)</td>
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

<p>Make Path absolute.</p>

<p>Definition at line 91 of file <a href="/web-llvm/docs/api/files/lib/lib/support/filecollector-cpp">FileCollector.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/namespaces/llvm/sys/fs/#a144ec9dcc77027317d16af9fc5fec1c8">llvm::sys::fs::make_absolute</a>, <a href="/web-llvm/docs/api/namespaces/llvm/sys/path/#a58cfd8a47c0ef96db27b451c2d6ec49fa8e5f3adee38c8fccc13c1f3be0143796">llvm::sys::path::native</a> and <a href="/web-llvm/docs/api/namespaces/llvm/sys/path/#a6aa32b6763df05d8187ad5551533b567">llvm::sys::path::remove_leading_dotslash</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/classes/llvm/filecollector/pathcanonicalizer/#ac656bc9e1653748650e52573708cdf20">llvm::FileCollector::PathCanonicalizer::canonicalize</a>, <a href="/web-llvm/docs/api/classes/llvm/vfs/inmemoryfilesystem/#a29c7a2f361d2018ff1bae9ddc9d50cc1">llvm::vfs::InMemoryFileSystem::getRealPath</a> and <a href="/web-llvm/docs/api/classes/llvm/vfs/inmemoryfilesystem/#ac03492c3b5f13e9fcc7d28e9130902fe">llvm::vfs::InMemoryFileSystem::setCurrentWorkingDirectory</a>.</p>

</div>
</div>

</div>

<hr/>

<p class="doxyGeneratedBy">Generated via <a href="https://github.com/xpack/doxygen2docusaurus">doxygen2docusaurus</a> by <a href="https://www.doxygen.nl">Doxygen</a> 1.15.0.</p>

</div>
