---

# DO NOT EDIT!
# Automatically generated via doxygen2docusaurus by Doxygen.

slug: /api/classes/llvm/vfs/inmemoryfilesystem
custom_edit_url: null
toc_max_heading_level: 4
keywords:
  - doxygen
  - reference
  - class

---

<div class="doxyPage">

# The `InMemoryFileSystem` Class Reference

<p>An in-memory file system. <a href="#details">More...</a></p>

## Declaration

<div class="doxyDeclaration">
class llvm::vfs::InMemoryFileSystem { ... }
</div>

## Included Headers

<div class="doxyIncludesList">#include "<a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/support/virtualfilesystem-h">llvm/Support/VirtualFileSystem.h</a>"
</div>

## Base class

<table class="doxyMembersIndex">

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">class</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/rttiextends">RTTIExtends&lt;ThisT, ParentT, ParentTs&gt;</a></td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Inheritance utility for extensible RTTI. <a href="/web-llvm/docs/api/classes/llvm/rttiextends/#details">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

</table>

## Private Member Typedefs Index

<table class="doxyMembersIndex">

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">using</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ab85680c265381414d7e9df0dd9aac2a6">MakeNodeFn</a> = <a href="/web-llvm/docs/api/classes/llvm/function-ref">llvm::function_ref</a>&lt; std::unique_ptr&lt; <a href="/web-llvm/docs/api/classes/llvm/vfs/detail/inmemorynode">detail::InMemoryNode</a> &gt;( <a href="/web-llvm/docs/api/structs/llvm/vfs/detail/newinmemorynodeinfo">detail::NewInMemoryNodeInfo</a>)&gt;</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a5fd6b2b27c08aa31009474233d537b0b">InMemoryFileSystem</a> (bool UseNormalizedPaths=true)</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a448d54c0555e5cb35783a82ff82e4273">~InMemoryFileSystem</a> () override</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">bool</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ae6eb3a5c9cf5ee7336e99374cbdea059">addFile</a> (const Twine &amp;Path, time_t ModificationTime, std::unique_ptr&lt; llvm::MemoryBuffer &gt; Buffer, std::optional&lt; uint32_t &gt; User=std::nullopt, std::optional&lt; uint32_t &gt; Group=std::nullopt, std::optional&lt; llvm::sys::fs::file_type &gt; Type=std::nullopt, std::optional&lt; llvm::sys::fs::perms &gt; Perms=std::nullopt)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Add a file containing a buffer or a directory to the VFS with a path. <a href="#ae6eb3a5c9cf5ee7336e99374cbdea059">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">bool</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a8328d3e20eac36fdb0b50d0192052c89">addHardLink</a> (const Twine &amp;NewLink, const Twine &amp;Target)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Add a hard link to a file. <a href="#a8328d3e20eac36fdb0b50d0192052c89">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">bool</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ac01074de42130f7440672e8b2ba920e3">addSymbolicLink</a> (const Twine &amp;NewLink, const Twine &amp;Target, time_t ModificationTime, std::optional&lt; uint32_t &gt; User=std::nullopt, std::optional&lt; uint32_t &gt; Group=std::nullopt, std::optional&lt; llvm::sys::fs::perms &gt; Perms=std::nullopt)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Add a symbolic link. <a href="#ac01074de42130f7440672e8b2ba920e3">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">bool</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#aafccb9d37b4780a41412379355a4cf41">addFileNoOwn</a> (const Twine &amp;Path, time_t ModificationTime, const llvm::MemoryBufferRef &amp;Buffer, std::optional&lt; uint32_t &gt; User=std::nullopt, std::optional&lt; uint32_t &gt; Group=std::nullopt, std::optional&lt; llvm::sys::fs::file_type &gt; Type=std::nullopt, std::optional&lt; llvm::sys::fs::perms &gt; Perms=std::nullopt)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Add a buffer to the VFS with a path. <a href="#aafccb9d37b4780a41412379355a4cf41">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">std::string</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a96dbc25996b106b6a8047a955064957e">toString</a> () const</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a64f4b7079bd98fdc3a749e8a794b1ca1">useNormalizedPaths</a> () const</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Return true if this file system normalizes . and .. in paths. <a href="#a64f4b7079bd98fdc3a749e8a794b1ca1">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/erroror">llvm::ErrorOr</a>&lt; <a href="/web-llvm/docs/api/classes/llvm/vfs/status">Status</a> &gt;</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ae74bea6914d0b037115ed1d24fd22cc5">status</a> (const Twine &amp;Path) override</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/erroror">llvm::ErrorOr</a>&lt; std::unique_ptr&lt; <a href="/web-llvm/docs/api/classes/llvm/vfs/file">File</a> &gt; &gt;</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#aeba186664b22855109a67a655dd856ea">openFileForRead</a> (const Twine &amp;Path) override</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/vfs/directory-iterator">directory_iterator</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a1e1abb9a350cc753be1d650c8f638d02">dir_begin</a> (const Twine &amp;Dir, std::error_code &amp;EC) override</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/erroror">llvm::ErrorOr</a>&lt; std::string &gt;</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a7c30e4d9f84b1f616e66972821cac3d1">getCurrentWorkingDirectory</a> () const override</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a29c7a2f361d2018ff1bae9ddc9d50cc1">getRealPath</a> (const Twine &amp;Path, SmallVectorImpl&lt; char &gt; &amp;Output) override</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Canonicalizes <span class="doxyComputerOutput">Path</span> by combining with the current working directory and normalizing the path (e.g. <a href="#a29c7a2f361d2018ff1bae9ddc9d50cc1">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">std::error_code</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a19b2edd4e88d26aea1c45ab4f7418024">isLocal</a> (const Twine &amp;Path, bool &amp;Result) override</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ac03492c3b5f13e9fcc7d28e9130902fe">setCurrentWorkingDirectory</a> (const Twine &amp;Path) override</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">void</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a6568557319fc0db7de996345f9da1a32">printImpl</a> (raw_ostream &amp;OS, PrintType Type, unsigned IndentLevel) const override</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">bool</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#aa8e098029e79c4788b35ac3a53c3a3ac">addFile</a> (const Twine &amp;Path, time_t ModificationTime, std::unique_ptr&lt; llvm::MemoryBuffer &gt; Buffer, std::optional&lt; uint32_t &gt; User, std::optional&lt; uint32_t &gt; Group, std::optional&lt; llvm::sys::fs::file_type &gt; Type, std::optional&lt; llvm::sys::fs::perms &gt; Perms, MakeNodeFn MakeNode)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Create node with <span class="doxyComputerOutput">MakeNode</span> and add it into this filesystem at <span class="doxyComputerOutput">Path</span>. <a href="#aa8e098029e79c4788b35ac3a53c3a3ac">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/vfs/detail/namednodeorerror">detail::NamedNodeOrError</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a292966e50b9139425b890a10d6284d05">lookupNode</a> (const Twine &amp;P, bool FollowFinalSymlink, size_t SymlinkDepth=0) const</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Looks up the in-memory node for the path <span class="doxyComputerOutput">P</span>. <a href="#a292966e50b9139425b890a10d6284d05">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

</table>

## Private Member Attributes Index

<table class="doxyMembersIndex">

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">std::unique_ptr&lt; <a href="/web-llvm/docs/api/classes/llvm/vfs/detail/inmemorydirectory">detail::InMemoryDirectory</a> &gt;</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#aece853fd8bb5d0a5351f67b9b8555180">Root</a></td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a1fed681319e18810f8a78930c69fa76a">WorkingDirectory</a></td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ae62e33299c9bb4c9e938d793f3958f78">UseNormalizedPaths</a> = <a href="/web-llvm/docs/api/files/lib/lib/analysis/basicaliasanalysis-cpp/#af6d5cafbdfc5313e65d990120021a3ec">true</a></td>
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

## Public Static Attributes Index

<table class="doxyMembersIndex">

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">static <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> char</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a556909b279fc59ab7fdfe3889f1485d0">ID</a> = 0</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">static constexpr size_t</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a581c67f4906221535b1d91295f30b19e">MaxSymlinkDepth</a> = 16</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Arbitrary max depth to search through symlinks. <a href="#a581c67f4906221535b1d91295f30b19e">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

</table>

## Description {#details}

<p>An in-memory file system.</p>

<p>Definition at line 537 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/support/virtualfilesystem-h">VirtualFileSystem.h</a>.</p>


<div class="doxySectionDef">

## Private Member Typedefs

### MakeNodeFn {#ab85680c265381414d7e9df0dd9aac2a6}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">using llvm::vfs::InMemoryFileSystem::MakeNodeFn =  llvm::function_ref&lt;std::unique_ptr&lt;detail::InMemoryNode&gt;(
      detail::NewInMemoryNodeInfo)&gt;</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 546 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/support/virtualfilesystem-h">VirtualFileSystem.h</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Public Constructors

### InMemoryFileSystem() {#a5fd6b2b27c08aa31009474233d537b0b}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">llvm::vfs::InMemoryFileSystem::InMemoryFileSystem (bool UseNormalizedPaths=<a href="/web-llvm/docs/api/files/lib/lib/analysis/basicaliasanalysis-cpp/#af6d5cafbdfc5313e65d990120021a3ec">true</a>)</td>
</tr>
</table>
</td>
<td class="doxyMemberLabelsRight">
<span class="doxyMemberLabels">
<span class="doxyMemberLabel explicit">explicit</span>
</span>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Declaration at line 565 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/support/virtualfilesystem-h">VirtualFileSystem.h</a>, definition at line 838 of file <a href="/web-llvm/docs/api/files/lib/lib/support/virtualfilesystem-cpp">VirtualFileSystem.cpp</a>.</p>


<p>Reference <a href="/web-llvm/docs/api/namespaces/llvm/vfs/#aadf74a30b19f30570211b95b9e379884">llvm::vfs::getDirectoryID</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/classes/llvm/vfs/inmemoryfilesystem/diriterator/#a04a4cc84fb1c698d7c808efcbd0efed1">llvm::vfs::InMemoryFileSystem::DirIterator::DirIterator</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Public Destructor

### \~InMemoryFileSystem() {#a448d54c0555e5cb35783a82ff82e4273}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">llvm::vfs::InMemoryFileSystem::~InMemoryFileSystem ()</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 566 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/support/virtualfilesystem-h">VirtualFileSystem.h</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Public Member Functions

### addFile() {#ae6eb3a5c9cf5ee7336e99374cbdea059}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool llvm::vfs::InMemoryFileSystem::addFile (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/twine">Twine</a> &amp; Path, time_t ModificationTime, std::unique_ptr&lt; <a href="/web-llvm/docs/api/classes/llvm/memorybuffer">llvm::MemoryBuffer</a> &gt; Buffer, std::optional&lt; uint32_t &gt; User=std::nullopt, std::optional&lt; uint32_t &gt; Group=std::nullopt, std::optional&lt; <a href="/web-llvm/docs/api/namespaces/llvm/sys/fs/#a6c50be965db24d7532b6b4e6b0755f5c">llvm::sys::fs::file_type</a> &gt; Type=std::nullopt, std::optional&lt; <a href="/web-llvm/docs/api/namespaces/llvm/sys/fs/#ac56b6ec1078927bdd9b65f7ba8fbda82">llvm::sys::fs::perms</a> &gt; Perms=std::nullopt)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Add a file containing a buffer or a directory to the VFS with a path.</p>


<p>The VFS owns the buffer. If present, <a href="/web-llvm/docs/api/classes/llvm/user">User</a>, Group, <a href="/web-llvm/docs/api/classes/llvm/type">Type</a> and Perms apply to the newly-created file or directory.</p>


<dl class="doxySectionUser">
<dt>Returns</dt>
<dd><p>true if the file or directory was successfully added, false if the file or directory already exists in the file system with different contents.</p></dd>
</dl>


<p>Declaration at line 574 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/support/virtualfilesystem-h">VirtualFileSystem.h</a>, definition at line 930 of file <a href="/web-llvm/docs/api/files/lib/lib/support/virtualfilesystem-cpp">VirtualFileSystem.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/structs/llvm/vfs/detail/newinmemorynodeinfo/#a669f4be4ac9f63efacbc021e46da0170">llvm::vfs::detail::NewInMemoryNodeInfo::Buffer</a>, <a href="/web-llvm/docs/api/namespaces/llvm/sys/fs/#a6c50be965db24d7532b6b4e6b0755f5ca1c3e56917e1b64d1874d5d88c085e0c9">llvm::sys::fs::directory_file</a>, <a href="/web-llvm/docs/api/classes/llvm/vfs/status/#ac81c05bfac7914be19f8a46888122e84">llvm::vfs::Status::getType</a>, <a href="/web-llvm/docs/api/structs/llvm/vfs/detail/newinmemorynodeinfo/#a397f1399c965b53a95d8dbab6b8b41a3">llvm::vfs::detail::NewInMemoryNodeInfo::makeStatus</a> and <a href="/web-llvm/docs/api/files/lib/lib/option/option-cpp/#a04665169063c8ca1f2ea96c27fc7c2b2">P</a>.</p>

</div>
</div>

### addFileNoOwn() {#aafccb9d37b4780a41412379355a4cf41}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool llvm::vfs::InMemoryFileSystem::addFileNoOwn (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/twine">Twine</a> &amp; Path, time_t ModificationTime, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/memorybufferref">llvm::MemoryBufferRef</a> &amp; Buffer, std::optional&lt; uint32_t &gt; User=std::nullopt, std::optional&lt; uint32_t &gt; Group=std::nullopt, std::optional&lt; <a href="/web-llvm/docs/api/namespaces/llvm/sys/fs/#a6c50be965db24d7532b6b4e6b0755f5c">llvm::sys::fs::file_type</a> &gt; Type=std::nullopt, std::optional&lt; <a href="/web-llvm/docs/api/namespaces/llvm/sys/fs/#ac56b6ec1078927bdd9b65f7ba8fbda82">llvm::sys::fs::perms</a> &gt; Perms=std::nullopt)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Add a buffer to the VFS with a path.</p>


<p>The VFS does not own the buffer. If present, <a href="/web-llvm/docs/api/classes/llvm/user">User</a>, Group, <a href="/web-llvm/docs/api/classes/llvm/type">Type</a> and Perms apply to the newly-created file or directory.</p>


<dl class="doxySectionUser">
<dt>Returns</dt>
<dd><p>true if the file or directory was successfully added, false if the file or directory already exists in the file system with different contents.</p></dd>
</dl>


<p>Declaration at line 617 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/support/virtualfilesystem-h">VirtualFileSystem.h</a>, definition at line 948 of file <a href="/web-llvm/docs/api/files/lib/lib/support/virtualfilesystem-cpp">VirtualFileSystem.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/structs/llvm/vfs/detail/newinmemorynodeinfo/#a669f4be4ac9f63efacbc021e46da0170">llvm::vfs::detail::NewInMemoryNodeInfo::Buffer</a>, <a href="/web-llvm/docs/api/namespaces/llvm/sys/fs/#a6c50be965db24d7532b6b4e6b0755f5ca1c3e56917e1b64d1874d5d88c085e0c9">llvm::sys::fs::directory_file</a>, <a href="/web-llvm/docs/api/classes/llvm/memorybuffer/#a0f68098734d6d3b451aacf5b38a67131">llvm::MemoryBuffer::getMemBuffer</a>, <a href="/web-llvm/docs/api/classes/llvm/vfs/status/#ac81c05bfac7914be19f8a46888122e84">llvm::vfs::Status::getType</a>, <a href="/web-llvm/docs/api/structs/llvm/vfs/detail/newinmemorynodeinfo/#a397f1399c965b53a95d8dbab6b8b41a3">llvm::vfs::detail::NewInMemoryNodeInfo::makeStatus</a> and <a href="/web-llvm/docs/api/files/lib/lib/option/option-cpp/#a04665169063c8ca1f2ea96c27fc7c2b2">P</a>.</p>

</div>
</div>

### addHardLink() {#a8328d3e20eac36fdb0b50d0192052c89}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool llvm::vfs::InMemoryFileSystem::addHardLink (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/twine">Twine</a> &amp; NewLink, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/twine">Twine</a> &amp; Target)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Add a hard link to a file.</p>


<p>Here hard links are not intended to be fully equivalent to the classical filesystem. Both the hard link and the file share the same buffer and status (and thus have the same <a href="/web-llvm/docs/api/classes/uniqueid">UniqueID</a>). Because of this there is no way to distinguish between the link and the file after the link has been added.</p>


<p>The <span class="doxyComputerOutput"><a href="/web-llvm/docs/api/classes/llvm/target">Target</a></span> path must be an existing file or a hardlink. The <span class="doxyComputerOutput">NewLink</span> file must not have been added before. The <span class="doxyComputerOutput"><a href="/web-llvm/docs/api/classes/llvm/target">Target</a></span> path must not be a directory. The <span class="doxyComputerOutput">NewLink</span> node is added as a hard link which points to the resolved file of <span class="doxyComputerOutput"><a href="/web-llvm/docs/api/classes/llvm/target">Target</a></span> node.</p>


<dl class="doxySectionUser">
<dt>Returns</dt>
<dd><p>true if the above condition is satisfied and hardlink was successfully created, false otherwise.</p></dd>
</dl>


<p>Declaration at line 595 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/support/virtualfilesystem-h">VirtualFileSystem.h</a>, definition at line 1041 of file <a href="/web-llvm/docs/api/files/lib/lib/support/virtualfilesystem-cpp">VirtualFileSystem.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/namespaces/llvm/#ac4fc845f5ed92de63cd4474f128f5fc5">llvm::cast</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a92ca992e52dddc420f4b069cae06dfbe">llvm::isa</a>, <a href="/web-llvm/docs/api/structs/llvm/vfs/detail/newinmemorynodeinfo/#aba393ab4fb8a800d21c01c7394e6d0ba">llvm::vfs::detail::NewInMemoryNodeInfo::Path</a> and <a href="/web-llvm/docs/api/classes/llvm/stringref/#a223dd14e7d12bc5cea01889b972a98b2">llvm::StringRef::str</a>.</p>

</div>
</div>

### addSymbolicLink() {#ac01074de42130f7440672e8b2ba920e3}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool llvm::vfs::InMemoryFileSystem::addSymbolicLink (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/twine">Twine</a> &amp; NewLink, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/twine">Twine</a> &amp; Target, time_t ModificationTime, std::optional&lt; uint32_t &gt; User=std::nullopt, std::optional&lt; uint32_t &gt; Group=std::nullopt, std::optional&lt; <a href="/web-llvm/docs/api/namespaces/llvm/sys/fs/#ac56b6ec1078927bdd9b65f7ba8fbda82">llvm::sys::fs::perms</a> &gt; Perms=std::nullopt)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Add a symbolic link.</p>


<p>Unlike a HardLink, because <span class="doxyComputerOutput"><a href="/web-llvm/docs/api/classes/llvm/target">Target</a></span> doesn't need to refer to a file (or refer to anything, as it happens). Also, an in-memory directory for <span class="doxyComputerOutput"><a href="/web-llvm/docs/api/classes/llvm/target">Target</a></span> isn't automatically created.</p>


<p>Declaration at line 605 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/support/virtualfilesystem-h">VirtualFileSystem.h</a>, definition at line 1060 of file <a href="/web-llvm/docs/api/files/lib/lib/support/virtualfilesystem-cpp">VirtualFileSystem.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/structs/llvm/vfs/detail/newinmemorynodeinfo/#a397f1399c965b53a95d8dbab6b8b41a3">llvm::vfs::detail::NewInMemoryNodeInfo::makeStatus</a>, <a href="/web-llvm/docs/api/namespaces/llvm/sys/fs/#a6c50be965db24d7532b6b4e6b0755f5cad978ac65911e3b23055a644703f89615">llvm::sys::fs::symlink_file</a> and <a href="/web-llvm/docs/api/classes/llvm/twine/#ae2cc7378ca67e19c45648f7800686933">llvm::Twine::toVector</a>.</p>

</div>
</div>

### dir\_begin() {#a1e1abb9a350cc753be1d650c8f638d02}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">directory_iterator llvm::vfs::InMemoryFileSystem::dir_begin (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/twine">Twine</a> &amp; Dir, std::error_code &amp; EC)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Declaration at line 632 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/support/virtualfilesystem-h">VirtualFileSystem.h</a>, definition at line 1157 of file <a href="/web-llvm/docs/api/files/lib/lib/support/virtualfilesystem-cpp">VirtualFileSystem.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/namespaces/llvm/#a22eeee01734061ac1b31ccd994c49eef">llvm::dyn_cast</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a20e3e08c7de6a230cd66f9e4322c3fbe">llvm::make_error_code</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a59739a4f15fb2ec57a6b7fcfe938546ba21e867ca95e1dfecff4701863547dcec">llvm::not_a_directory</a> and <a href="/web-llvm/docs/api/classes/llvm/twine/#a4c1c1093a7749409c70838678514cc7c">llvm::Twine::str</a>.</p>

</div>
</div>

### getCurrentWorkingDirectory() {#a7c30e4d9f84b1f616e66972821cac3d1}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">llvm::ErrorOr&lt; std::string &gt; llvm::vfs::InMemoryFileSystem::getCurrentWorkingDirectory ()</td>
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



<p>Definition at line 634 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/support/virtualfilesystem-h">VirtualFileSystem.h</a>.</p>


<p>Referenced by <a href="#a29c7a2f361d2018ff1bae9ddc9d50cc1">getRealPath</a>.</p>

</div>
</div>

### getRealPath() {#a29c7a2f361d2018ff1bae9ddc9d50cc1}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">std::error_code llvm::vfs::InMemoryFileSystem::getRealPath (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/twine">Twine</a> &amp; Path, <a href="/web-llvm/docs/api/classes/llvm/smallvectorimpl">SmallVectorImpl</a>&lt; char &gt; &amp; Output)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Canonicalizes <span class="doxyComputerOutput">Path</span> by combining with the current working directory and normalizing the path (e.g.</p>


<p>remove dots). If the current working directory is not set, this returns <a href="/web-llvm/docs/api/namespaces/llvm/#a59739a4f15fb2ec57a6b7fcfe938546ba8344b3d509942f035d5e303022f9b986">errc::operation_not_permitted</a>.</p>


<p>This doesn't resolve symlinks as they are not supported in in-memory file system.</p>


<p>Declaration at line 643 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/support/virtualfilesystem-h">VirtualFileSystem.h</a>, definition at line 1190 of file <a href="/web-llvm/docs/api/files/lib/lib/support/virtualfilesystem-cpp">VirtualFileSystem.cpp</a>.</p>


<p>References <a href="#a7c30e4d9f84b1f616e66972821cac3d1">getCurrentWorkingDirectory</a>, <a href="/web-llvm/docs/api/files/lib/lib/support/filecollector-cpp/#a20bab096e3719810afee546ab46997c3">makeAbsolute</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a59739a4f15fb2ec57a6b7fcfe938546ba8344b3d509942f035d5e303022f9b986">llvm::operation_not_permitted</a> and <a href="/web-llvm/docs/api/namespaces/llvm/sys/path/#a35c103b5fb70a66a1cb5da3b56f588a1">llvm::sys::path::remove_dots</a>.</p>

</div>
</div>

### isLocal() {#a19b2edd4e88d26aea1c45ab4f7418024}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">std::error_code llvm::vfs::InMemoryFileSystem::isLocal (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/twine">Twine</a> &amp; Path, bool &amp; Result)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Declaration at line 645 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/support/virtualfilesystem-h">VirtualFileSystem.h</a>, definition at line 1202 of file <a href="/web-llvm/docs/api/files/lib/lib/support/virtualfilesystem-cpp">VirtualFileSystem.cpp</a>.</p>

</div>
</div>

### openFileForRead() {#aeba186664b22855109a67a655dd856ea}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">llvm::ErrorOr&lt; std::unique_ptr&lt; File &gt; &gt; llvm::vfs::InMemoryFileSystem::openFileForRead (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/twine">Twine</a> &amp; Path)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Declaration at line 631 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/support/virtualfilesystem-h">VirtualFileSystem.h</a>, definition at line 1088 of file <a href="/web-llvm/docs/api/files/lib/lib/support/virtualfilesystem-cpp">VirtualFileSystem.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/namespaces/llvm/#a22eeee01734061ac1b31ccd994c49eef">llvm::dyn_cast</a>, <a href="/web-llvm/docs/api/files/lib/lib/support/md5-cpp/#a96d73bbd7af15cb1fc38c3f4a3bd82e9">F</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a59739a4f15fb2ec57a6b7fcfe938546bae55d43eabeefe5a8271b4a3c898bd18f">llvm::invalid_argument</a> and <a href="/web-llvm/docs/api/namespaces/llvm/#a20e3e08c7de6a230cd66f9e4322c3fbe">llvm::make_error_code</a>.</p>

</div>
</div>

### setCurrentWorkingDirectory() {#ac03492c3b5f13e9fcc7d28e9130902fe}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">std::error_code llvm::vfs::InMemoryFileSystem::setCurrentWorkingDirectory (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/twine">Twine</a> &amp; Path)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Declaration at line 646 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/support/virtualfilesystem-h">VirtualFileSystem.h</a>, definition at line 1173 of file <a href="/web-llvm/docs/api/files/lib/lib/support/virtualfilesystem-cpp">VirtualFileSystem.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/silowercontrolflow-cpp/#a4868c5d81c5ccc98c47aeab6244346a0">assert</a>, <a href="/web-llvm/docs/api/files/lib/lib/support/filecollector-cpp/#a20bab096e3719810afee546ab46997c3">makeAbsolute</a>, <a href="/web-llvm/docs/api/files/lib/lib/option/option-cpp/#a04665169063c8ca1f2ea96c27fc7c2b2">P</a>, <a href="/web-llvm/docs/api/namespaces/llvm/sys/path/#a35c103b5fb70a66a1cb5da3b56f588a1">llvm::sys::path::remove_dots</a> and <a href="#a64f4b7079bd98fdc3a749e8a794b1ca1">useNormalizedPaths</a>.</p>

</div>
</div>

### status() {#ae74bea6914d0b037115ed1d24fd22cc5}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">llvm::ErrorOr&lt; Status &gt; llvm::vfs::InMemoryFileSystem::status (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/twine">Twine</a> &amp; Path)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Declaration at line 629 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/support/virtualfilesystem-h">VirtualFileSystem.h</a>, definition at line 1080 of file <a href="/web-llvm/docs/api/files/lib/lib/support/virtualfilesystem-cpp">VirtualFileSystem.cpp</a>.</p>

</div>
</div>

### toString() {#a96dbc25996b106b6a8047a955064957e}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">std::string llvm::vfs::InMemoryFileSystem::toString ()</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Declaration at line 624 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/support/virtualfilesystem-h">VirtualFileSystem.h</a>, definition at line 848 of file <a href="/web-llvm/docs/api/files/lib/lib/support/virtualfilesystem-cpp">VirtualFileSystem.cpp</a>.</p>

</div>
</div>

### useNormalizedPaths() {#a64f4b7079bd98fdc3a749e8a794b1ca1}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool llvm::vfs::InMemoryFileSystem::useNormalizedPaths ()</td>
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

<p>Return true if this file system normalizes . and .. in paths.</p>

<p>Definition at line 627 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/support/virtualfilesystem-h">VirtualFileSystem.h</a>.</p>


<p>Referenced by <a href="#ac03492c3b5f13e9fcc7d28e9130902fe">setCurrentWorkingDirectory</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Protected Member Functions

### printImpl() {#a6568557319fc0db7de996345f9da1a32}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void llvm::vfs::InMemoryFileSystem::printImpl (<a href="/web-llvm/docs/api/classes/llvm/raw-ostream">raw_ostream</a> &amp; OS, PrintType Type, unsigned IndentLevel)</td>
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



<p>Declaration at line 649 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/support/virtualfilesystem-h">VirtualFileSystem.h</a>, definition at line 1207 of file <a href="/web-llvm/docs/api/files/lib/lib/support/virtualfilesystem-cpp">VirtualFileSystem.cpp</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Private Member Functions

### addFile() {#aa8e098029e79c4788b35ac3a53c3a3ac}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool llvm::vfs::InMemoryFileSystem::addFile (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/twine">Twine</a> &amp; Path, time_t ModificationTime, std::unique_ptr&lt; <a href="/web-llvm/docs/api/classes/llvm/memorybuffer">llvm::MemoryBuffer</a> &gt; Buffer, std::optional&lt; uint32_t &gt; User, std::optional&lt; uint32_t &gt; Group, std::optional&lt; <a href="/web-llvm/docs/api/namespaces/llvm/sys/fs/#a6c50be965db24d7532b6b4e6b0755f5c">llvm::sys::fs::file_type</a> &gt; Type, std::optional&lt; <a href="/web-llvm/docs/api/namespaces/llvm/sys/fs/#ac56b6ec1078927bdd9b65f7ba8fbda82">llvm::sys::fs::perms</a> &gt; Perms, <a href="/web-llvm/docs/api/classes/llvm/function-ref">MakeNodeFn</a> MakeNode)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Create node with <span class="doxyComputerOutput">MakeNode</span> and add it into this filesystem at <span class="doxyComputerOutput">Path</span>.</p>

<p>Declaration at line 550 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/support/virtualfilesystem-h">VirtualFileSystem.h</a>, definition at line 852 of file <a href="/web-llvm/docs/api/files/lib/lib/support/virtualfilesystem-cpp">VirtualFileSystem.cpp</a>.</p>

</div>
</div>

### lookupNode() {#a292966e50b9139425b890a10d6284d05}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">detail::NamedNodeOrError llvm::vfs::InMemoryFileSystem::lookupNode (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/twine">Twine</a> &amp; P, bool FollowFinalSymlink, size_t SymlinkDepth=0)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Looks up the in-memory node for the path <span class="doxyComputerOutput">P</span>.</p>


<p>If <span class="doxyComputerOutput">FollowFinalSymlink</span> is true, the returned node is guaranteed to not be a symlink and its path may differ from <span class="doxyComputerOutput">P</span>.</p>


<p>Declaration at line 559 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/support/virtualfilesystem-h">VirtualFileSystem.h</a>, definition at line 967 of file <a href="/web-llvm/docs/api/files/lib/lib/support/virtualfilesystem-cpp">VirtualFileSystem.cpp</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Private Member Attributes

### Root {#aece853fd8bb5d0a5351f67b9b8555180}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">std::unique_ptr&lt;detail::InMemoryDirectory&gt; llvm::vfs::InMemoryFileSystem::Root</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 538 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/support/virtualfilesystem-h">VirtualFileSystem.h</a>.</p>

</div>
</div>

### UseNormalizedPaths {#ae62e33299c9bb4c9e938d793f3958f78}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool llvm::vfs::InMemoryFileSystem::UseNormalizedPaths = <a href="/web-llvm/docs/api/files/lib/lib/analysis/basicaliasanalysis-cpp/#af6d5cafbdfc5313e65d990120021a3ec">true</a></td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 540 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/support/virtualfilesystem-h">VirtualFileSystem.h</a>.</p>

</div>
</div>

### WorkingDirectory {#a1fed681319e18810f8a78930c69fa76a}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">std::string llvm::vfs::InMemoryFileSystem::WorkingDirectory</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 539 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/support/virtualfilesystem-h">VirtualFileSystem.h</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Public Static Attributes

### ID {#a556909b279fc59ab7fdfe3889f1485d0}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">const char InMemoryFileSystem::ID = 0</td>
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



<p>Definition at line 543 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/support/virtualfilesystem-h">VirtualFileSystem.h</a>.</p>

</div>
</div>

### MaxSymlinkDepth {#a581c67f4906221535b1d91295f30b19e}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">size_t llvm::vfs::InMemoryFileSystem::MaxSymlinkDepth = 16</td>
</tr>
</table>
</td>
<td class="doxyMemberLabelsRight">
<span class="doxyMemberLabels">
<span class="doxyMemberLabel constexpr">constexpr</span>
<span class="doxyMemberLabel static">static</span>
</span>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Arbitrary max depth to search through symlinks.</p>


<p>We can get into problems if a link links to a link that links back to the link, for example.</p>


<p>Definition at line 599 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/support/virtualfilesystem-h">VirtualFileSystem.h</a>.</p>

</div>
</div>

</div>

<hr/>

The documentation for this class was generated from the following files:

<ul>
<li><a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/support/virtualfilesystem-h">VirtualFileSystem.h</a></li>
<li><a href="/web-llvm/docs/api/files/lib/lib/support/virtualfilesystem-cpp">VirtualFileSystem.cpp</a></li>
</ul>

<hr/>

<p class="doxyGeneratedBy">Generated via <a href="https://github.com/xpack/doxygen2docusaurus">doxygen2docusaurus</a> by <a href="https://www.doxygen.nl">Doxygen</a> 1.15.0.</p>

</div>
