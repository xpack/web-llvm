---

# DO NOT EDIT!
# Automatically generated via doxygen2docusaurus by Doxygen.

slug: /api/structs/llvm/newarchivemember
custom_edit_url: null
toc_max_heading_level: 4
keywords:
  - doxygen
  - reference
  - struct

---

<div class="doxyPage">

# The `NewArchiveMember` Struct Reference



## Declaration

<div class="doxyDeclaration">
struct llvm::NewArchiveMember { ... }
</div>

## Included Headers

<div class="doxyIncludesList">#include "<a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/object/archivewriter-h">llvm/Object/ArchiveWriter.h</a>"
</div>

## Public Constructors Index

<table class="doxyMembersIndex">

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a819ab70892ae7fafe651297777f7f2a9">NewArchiveMember</a> ()=default</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a1863485e5e5de4a4aa8d6b24bffe1942">NewArchiveMember</a> (MemoryBufferRef BufRef)</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/object/archive/#ab288378fa8bfa0678dd25e36b5198a87">object::Archive::Kind</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a5b9ae09da2b1f1939e37ba537fdf9eb1">detectKindFromObject</a> () const</td>
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

## Public Member Attributes Index

<table class="doxyMembersIndex">

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">std::unique_ptr&lt; <a href="/web-llvm/docs/api/classes/llvm/memorybuffer">MemoryBuffer</a> &gt;</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ad8431daf1941f63c4a89b99ca3e33f57">Buf</a></td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/stringref">StringRef</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a4d79bbd205e6d14a3cc5b9508328ed57">MemberName</a></td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/namespaces/llvm/sys/#a52f2c3fdd7f80c1991d8c7079489efff">sys::TimePoint</a>&lt; std::chrono::seconds &gt;</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a066a7e8b32b6dc02b8c8788d94833f4e">ModTime</a></td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">unsigned</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a033b1dad5a8082131b7d2690fbf390ee">UID</a> = 0</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">unsigned</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ad9d0dad734b371d1921ec0c2823eddc0">GID</a> = 0</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">unsigned</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a53759908d671ac2d228890c0099199c2">Perms</a> = 0644</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">static <a href="/web-llvm/docs/api/classes/llvm/expected">Expected</a>&lt; <a href="/web-llvm/docs/api/structs/llvm/newarchivemember">NewArchiveMember</a> &gt;</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#aadff13fd008345361aa920977e0c9e32">getOldMember</a> (const object::Archive::Child &amp;OldMember, bool Deterministic)</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">static <a href="/web-llvm/docs/api/classes/llvm/expected">Expected</a>&lt; <a href="/web-llvm/docs/api/structs/llvm/newarchivemember">NewArchiveMember</a> &gt;</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#aabc893bb91367b69e0edf27249081a78">getFile</a> (StringRef FileName, bool Deterministic)</td>
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


<p>Definition at line 20 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/object/archivewriter-h">ArchiveWriter.h</a>.</p>


<div class="doxySectionDef">

## Public Constructors

### NewArchiveMember() {#a819ab70892ae7fafe651297777f7f2a9}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">llvm::NewArchiveMember::NewArchiveMember ()</td>
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



<p>Definition at line 26 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/object/archivewriter-h">ArchiveWriter.h</a>.</p>


<p>Referenced by <a href="#aabc893bb91367b69e0edf27249081a78">getFile</a> and <a href="#aadff13fd008345361aa920977e0c9e32">getOldMember</a>.</p>

</div>
</div>

### NewArchiveMember() {#a1863485e5e5de4a4aa8d6b24bffe1942}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">NewArchiveMember::NewArchiveMember (<a href="/web-llvm/docs/api/classes/llvm/memorybufferref">MemoryBufferRef</a> BufRef)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Declaration at line 27 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/object/archivewriter-h">ArchiveWriter.h</a>, definition at line 56 of file <a href="/web-llvm/docs/api/files/lib/lib/object/archivewriter-cpp">ArchiveWriter.cpp</a>.</p>


<p>References <a href="#ad8431daf1941f63c4a89b99ca3e33f57">Buf</a> and <a href="#a4d79bbd205e6d14a3cc5b9508328ed57">MemberName</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Public Member Functions

### detectKindFromObject() {#a5b9ae09da2b1f1939e37ba537fdf9eb1}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">object::Archive::Kind NewArchiveMember::detectKindFromObject ()</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Declaration at line 32 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/object/archivewriter-h">ArchiveWriter.h</a>, definition at line 60 of file <a href="/web-llvm/docs/api/files/lib/lib/object/archivewriter-cpp">ArchiveWriter.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/structs/llvm/file-magic/#a39d74d9fa08229878443101289698b3aa9b217cf59bac16d57cf52c3e76f3ce50">llvm::file_magic::bitcode</a>, <a href="#ad8431daf1941f63c4a89b99ca3e33f57">Buf</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#ac4fc845f5ed92de63cd4474f128f5fc5">llvm::cast</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#aee0e70be66536b9ef7b65ae2e5a45959">llvm::consumeError</a>, <a href="/web-llvm/docs/api/classes/llvm/object/objectfile/#a926af6aca697fdbacb3e3ea1000f0ec4">llvm::object::ObjectFile::createObjectFile</a>, <a href="/web-llvm/docs/api/classes/llvm/object/symbolicfile/#a4ee418c47f5baa9b4b570371fc9630ce">llvm::object::SymbolicFile::createSymbolicFile</a>, <a href="/web-llvm/docs/api/classes/llvm/object/archive/#a6eb4b14d68eff7cfdc9457db1603fea7">llvm::object::Archive::getDefaultKind</a>, <a href="/web-llvm/docs/api/classes/llvm/object/archive/#aa37a8365d81258109c2093aac933e8a2">llvm::object::Archive::getDefaultKindForTriple</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a00941e59a16ad6eb14e905557a612501">llvm::identify_magic</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a92ca992e52dddc420f4b069cae06dfbe">llvm::isa</a>, <a href="/web-llvm/docs/api/classes/llvm/object/archive/#ab288378fa8bfa0678dd25e36b5198a87a1ce3ba6f0ac952cb8105e17115093810">llvm::object::Archive::K_AIXBIG</a>, <a href="/web-llvm/docs/api/classes/llvm/object/archive/#ab288378fa8bfa0678dd25e36b5198a87abfe17ba5950004cbd4a1a8ad6276676f">llvm::object::Archive::K_COFF</a>, <a href="/web-llvm/docs/api/classes/llvm/object/archive/#ab288378fa8bfa0678dd25e36b5198a87a521625eb71f7beb3f5764da18be48ae8">llvm::object::Archive::K_DARWIN</a>, <a href="/web-llvm/docs/api/classes/llvm/object/archive/#ab288378fa8bfa0678dd25e36b5198a87a63a070d89ebf9a74c22a38ec25719ae7">llvm::object::Archive::K_GNU</a> and <a href="/web-llvm/docs/api/classes/llvm/expected/#a94789df4ebd03dc008e8adebaa66ac1f">llvm::Expected&lt; T &gt;::takeError</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Public Member Attributes

### Buf {#ad8431daf1941f63c4a89b99ca3e33f57}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">std::unique_ptr&lt;MemoryBuffer&gt; llvm::NewArchiveMember::Buf</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 21 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/object/archivewriter-h">ArchiveWriter.h</a>.</p>


<p>Referenced by <a href="#a5b9ae09da2b1f1939e37ba537fdf9eb1">detectKindFromObject</a>, <a href="/web-llvm/docs/api/files/lib/lib/tooldrivers/lib/tooldrivers/llvm-lib/libdriver-cpp/#a3fd1142983d978a08b0fc7f697d6ca14">getDefaultOutputPath</a> and <a href="#a1863485e5e5de4a4aa8d6b24bffe1942">NewArchiveMember</a>.</p>

</div>
</div>

### GID {#ad9d0dad734b371d1921ec0c2823eddc0}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">unsigned llvm::NewArchiveMember::GID = 0</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 24 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/object/archivewriter-h">ArchiveWriter.h</a>.</p>

</div>
</div>

### MemberName {#a4d79bbd205e6d14a3cc5b9508328ed57}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">StringRef llvm::NewArchiveMember::MemberName</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 22 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/object/archivewriter-h">ArchiveWriter.h</a>.</p>


<p>Referenced by <a href="#a1863485e5e5de4a4aa8d6b24bffe1942">NewArchiveMember</a>.</p>

</div>
</div>

### ModTime {#a066a7e8b32b6dc02b8c8788d94833f4e}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">sys::TimePoint&lt;std::chrono::seconds&gt; llvm::NewArchiveMember::ModTime</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 23 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/object/archivewriter-h">ArchiveWriter.h</a>.</p>

</div>
</div>

### Perms {#a53759908d671ac2d228890c0099199c2}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">unsigned llvm::NewArchiveMember::Perms = 0644</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 24 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/object/archivewriter-h">ArchiveWriter.h</a>.</p>

</div>
</div>

### UID {#a033b1dad5a8082131b7d2690fbf390ee}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">unsigned llvm::NewArchiveMember::UID = 0</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 24 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/object/archivewriter-h">ArchiveWriter.h</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Public Static Functions

### getFile() {#aabc893bb91367b69e0edf27249081a78}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">Expected&lt; NewArchiveMember &gt; NewArchiveMember::getFile (<a href="/web-llvm/docs/api/classes/llvm/stringref">StringRef</a> FileName, bool Deterministic)</td>
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



<p>Declaration at line 37 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/object/archivewriter-h">ArchiveWriter.h</a>, definition at line 128 of file <a href="/web-llvm/docs/api/files/lib/lib/object/archivewriter-cpp">ArchiveWriter.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/silowercontrolflow-cpp/#a4868c5d81c5ccc98c47aeab6244346a0">assert</a>, <a href="/web-llvm/docs/api/namespaces/llvm/sys/fs/#a43548658b3d92c080577422f81f38038">llvm::sys::fs::closeFile</a>, <a href="/web-llvm/docs/api/namespaces/llvm/sys/fs/#a6c50be965db24d7532b6b4e6b0755f5ca1c3e56917e1b64d1874d5d88c085e0c9">llvm::sys::fs::directory_file</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#ad10875fd499e8e285aaeef615e9b11aa">llvm::errorCodeToError</a>, <a href="/web-llvm/docs/api/classes/llvm/erroror/#a8300c72908f1845c931951ed4b2a2375">llvm::ErrorOr&lt; T &gt;::getError</a>, <a href="/web-llvm/docs/api/classes/llvm/memorybuffer/#a0163ef693f4fd640ec72a5fe74e5852c">llvm::MemoryBuffer::getOpenFile</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a59739a4f15fb2ec57a6b7fcfe938546baf3c51d7ea75a76f26c0a2bdc00c4e006">llvm::is_a_directory</a>, <a href="/web-llvm/docs/api/namespaces/llvm/sys/fs/#a21f0ed93a281893d2081a0ec4620315b">llvm::sys::fs::kInvalidFile</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a20e3e08c7de6a230cd66f9e4322c3fbe">llvm::make_error_code</a>, <a href="#a819ab70892ae7fafe651297777f7f2a9">NewArchiveMember</a>, <a href="/web-llvm/docs/api/namespaces/llvm/sys/fs/#ae025e411759250214ffc53ab8d8a5e1d">llvm::sys::fs::openNativeFileForRead</a> and <a href="/web-llvm/docs/api/namespaces/llvm/sys/fs/#a5f126cc7b64d31cd709215b48656d83d">llvm::sys::fs::status</a>.</p>

</div>
</div>

### getOldMember() {#aadff13fd008345361aa920977e0c9e32}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">Expected&lt; NewArchiveMember &gt; NewArchiveMember::getOldMember (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/object/archive/child">object::Archive::Child</a> &amp; OldMember, bool Deterministic)</td>
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



<p>Declaration at line 35 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/object/archivewriter-h">ArchiveWriter.h</a>, definition at line 98 of file <a href="/web-llvm/docs/api/files/lib/lib/object/archivewriter-cpp">ArchiveWriter.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/classes/llvm/expected/#ad26ecbb6920f4ea55f5ed4f64e52342d">llvm::Expected&lt; T &gt;::get</a>, <a href="/web-llvm/docs/api/classes/llvm/object/archive/child/#ab8e1ab8fcc1aa249d1c6a01a263ef303">llvm::object::Archive::Child::getAccessMode</a>, <a href="/web-llvm/docs/api/classes/llvm/object/archive/child/#a5cbd281cdf1331330da601c219e452e9">llvm::object::Archive::Child::getGID</a>, <a href="/web-llvm/docs/api/classes/llvm/object/archive/child/#abea74633b8c0af7cb53addc66ce55ec1">llvm::object::Archive::Child::getLastModified</a>, <a href="/web-llvm/docs/api/classes/llvm/memorybuffer/#a0f68098734d6d3b451aacf5b38a67131">llvm::MemoryBuffer::getMemBuffer</a>, <a href="/web-llvm/docs/api/classes/llvm/object/archive/child/#a7fa0bfbc8489a0b3472e2dd834e03c80">llvm::object::Archive::Child::getMemoryBufferRef</a>, <a href="/web-llvm/docs/api/classes/llvm/object/archive/child/#a91f4f1c730ddfa9b53bed05548b656fa">llvm::object::Archive::Child::getUID</a>, <a href="#a819ab70892ae7fafe651297777f7f2a9">NewArchiveMember</a> and <a href="/web-llvm/docs/api/classes/llvm/expected/#a94789df4ebd03dc008e8adebaa66ac1f">llvm::Expected&lt; T &gt;::takeError</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/namespaces/llvm/objcopy/#afb660c7a07ee04be6dac1b6ce20de6d6">llvm::objcopy::createNewArchiveMembers</a>.</p>

</div>
</div>

</div>

<hr/>

The documentation for this struct was generated from the following files:

<ul>
<li><a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/object/archivewriter-h">ArchiveWriter.h</a></li>
<li><a href="/web-llvm/docs/api/files/lib/lib/object/archivewriter-cpp">ArchiveWriter.cpp</a></li>
</ul>

<hr/>

<p class="doxyGeneratedBy">Generated via <a href="https://github.com/xpack/doxygen2docusaurus">doxygen2docusaurus</a> by <a href="https://www.doxygen.nl">Doxygen</a> 1.15.0.</p>

</div>
