---

# DO NOT EDIT!
# Automatically generated via doxygen2docusaurus by Doxygen.

slug: /api/structs/llvm/vfs/detail/newinmemorynodeinfo
custom_edit_url: null
toc_max_heading_level: 4
keywords:
  - doxygen
  - reference
  - struct

---

<div class="doxyPage">

# `NewInMemoryNodeInfo` Struct



## Declaration

<div class="doxyDeclaration">
struct llvm::vfs::detail::NewInMemoryNodeInfo { ... }
</div>

## Included Headers

<div class="doxyIncludesList">#include "<a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/support/virtualfilesystem-h">llvm/Support/VirtualFileSystem.h</a>"
</div>

## Public Member Functions Index

<table class="doxyMembersIndex">

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/vfs/status">Status</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a397f1399c965b53a95d8dbab6b8b41a3">makeStatus</a> () const</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/sys/fs/uniqueid">llvm::sys::fs::UniqueID</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#aa48813ac974ef243b5975b30f98c9f7d">DirUID</a></td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#aba393ab4fb8a800d21c01c7394e6d0ba">Path</a></td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a9e5e37283fbf3711540f88c8b1106ca3">Name</a></td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">time_t</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a606c2f702c323637e2bb3dad4205e04f">ModificationTime</a></td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">std::unique_ptr&lt; <a href="/web-llvm/docs/api/classes/llvm/memorybuffer">llvm::MemoryBuffer</a> &gt;</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a669f4be4ac9f63efacbc021e46da0170">Buffer</a></td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">uint32_t</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a1fd7831d0ff6eec761f27c37ee2949d1">User</a></td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">uint32_t</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ab17dc9b0df772492a098cf5ad241ee3e">Group</a></td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/namespaces/llvm/sys/fs/#a6c50be965db24d7532b6b4e6b0755f5c">llvm::sys::fs::file_type</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a4474ee6dd8ccbd72eda8e6d6f62b15f8">Type</a></td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/namespaces/llvm/sys/fs/#ac56b6ec1078927bdd9b65f7ba8fbda82">llvm::sys::fs::perms</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a821c8f2a48cb79a1afcd8d129d856b36">Perms</a></td>
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


<p>Definition at line 502 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/support/virtualfilesystem-h">VirtualFileSystem.h</a>.</p>


<div class="doxySectionDef">

## Public Member Functions

### makeStatus() {#a397f1399c965b53a95d8dbab6b8b41a3}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">Status llvm::vfs::detail::NewInMemoryNodeInfo::makeStatus ()</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Declaration at line 513 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/support/virtualfilesystem-h">VirtualFileSystem.h</a>, definition at line 828 of file <a href="/web-llvm/docs/api/files/lib/lib/support/virtualfilesystem-cpp">VirtualFileSystem.cpp</a>.</p>


<p>References <a href="#a669f4be4ac9f63efacbc021e46da0170">Buffer</a>, <a href="/web-llvm/docs/api/namespaces/llvm/sys/fs/#a6c50be965db24d7532b6b4e6b0755f5ca1c3e56917e1b64d1874d5d88c085e0c9">llvm::sys::fs::directory_file</a>, <a href="#aa48813ac974ef243b5975b30f98c9f7d">DirUID</a>, <a href="/web-llvm/docs/api/namespaces/llvm/vfs/#aadf74a30b19f30570211b95b9e379884">llvm::vfs::getDirectoryID</a>, <a href="/web-llvm/docs/api/namespaces/llvm/vfs/#a6d887ec0b854b52f125578e7e3b5ac03">llvm::vfs::getFileID</a>, <a href="#ab17dc9b0df772492a098cf5ad241ee3e">Group</a>, <a href="#a606c2f702c323637e2bb3dad4205e04f">ModificationTime</a>, <a href="#a9e5e37283fbf3711540f88c8b1106ca3">Name</a>, <a href="#aba393ab4fb8a800d21c01c7394e6d0ba">Path</a>, <a href="#a821c8f2a48cb79a1afcd8d129d856b36">Perms</a>, <a href="/web-llvm/docs/api/namespaces/llvm/sys/#a7e0c6b3661b9c9f048aaef620463f1bc">llvm::sys::toTimePoint</a>, <a href="#a4474ee6dd8ccbd72eda8e6d6f62b15f8">Type</a> and <a href="#a1fd7831d0ff6eec761f27c37ee2949d1">User</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/classes/llvm/vfs/inmemoryfilesystem/#ae6eb3a5c9cf5ee7336e99374cbdea059">llvm::vfs::InMemoryFileSystem::addFile</a>, <a href="/web-llvm/docs/api/classes/llvm/vfs/inmemoryfilesystem/#aafccb9d37b4780a41412379355a4cf41">llvm::vfs::InMemoryFileSystem::addFileNoOwn</a> and <a href="/web-llvm/docs/api/classes/llvm/vfs/inmemoryfilesystem/#ac01074de42130f7440672e8b2ba920e3">llvm::vfs::InMemoryFileSystem::addSymbolicLink</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Public Member Attributes

### Buffer {#a669f4be4ac9f63efacbc021e46da0170}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">std::unique_ptr&lt;llvm::MemoryBuffer&gt; llvm::vfs::detail::NewInMemoryNodeInfo::Buffer</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 507 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/support/virtualfilesystem-h">VirtualFileSystem.h</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/classes/llvm/vfs/inmemoryfilesystem/#ae6eb3a5c9cf5ee7336e99374cbdea059">llvm::vfs::InMemoryFileSystem::addFile</a>, <a href="/web-llvm/docs/api/classes/llvm/vfs/inmemoryfilesystem/#aafccb9d37b4780a41412379355a4cf41">llvm::vfs::InMemoryFileSystem::addFileNoOwn</a> and <a href="#a397f1399c965b53a95d8dbab6b8b41a3">makeStatus</a>.</p>

</div>
</div>

### DirUID {#aa48813ac974ef243b5975b30f98c9f7d}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">llvm::sys::fs::UniqueID llvm::vfs::detail::NewInMemoryNodeInfo::DirUID</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 503 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/support/virtualfilesystem-h">VirtualFileSystem.h</a>.</p>


<p>Referenced by <a href="#a397f1399c965b53a95d8dbab6b8b41a3">makeStatus</a>.</p>

</div>
</div>

### Group {#ab17dc9b0df772492a098cf5ad241ee3e}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">uint32_t llvm::vfs::detail::NewInMemoryNodeInfo::Group</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 509 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/support/virtualfilesystem-h">VirtualFileSystem.h</a>.</p>


<p>Referenced by <a href="#a397f1399c965b53a95d8dbab6b8b41a3">makeStatus</a>.</p>

</div>
</div>

### ModificationTime {#a606c2f702c323637e2bb3dad4205e04f}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">time_t llvm::vfs::detail::NewInMemoryNodeInfo::ModificationTime</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 506 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/support/virtualfilesystem-h">VirtualFileSystem.h</a>.</p>


<p>Referenced by <a href="#a397f1399c965b53a95d8dbab6b8b41a3">makeStatus</a>.</p>

</div>
</div>

### Name {#a9e5e37283fbf3711540f88c8b1106ca3}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">StringRef llvm::vfs::detail::NewInMemoryNodeInfo::Name</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 505 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/support/virtualfilesystem-h">VirtualFileSystem.h</a>.</p>


<p>Referenced by <a href="#a397f1399c965b53a95d8dbab6b8b41a3">makeStatus</a>.</p>

</div>
</div>

### Path {#aba393ab4fb8a800d21c01c7394e6d0ba}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">StringRef llvm::vfs::detail::NewInMemoryNodeInfo::Path</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 504 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/support/virtualfilesystem-h">VirtualFileSystem.h</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/classes/llvm/vfs/inmemoryfilesystem/#a8328d3e20eac36fdb0b50d0192052c89">llvm::vfs::InMemoryFileSystem::addHardLink</a> and <a href="#a397f1399c965b53a95d8dbab6b8b41a3">makeStatus</a>.</p>

</div>
</div>

### Perms {#a821c8f2a48cb79a1afcd8d129d856b36}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">llvm::sys::fs::perms llvm::vfs::detail::NewInMemoryNodeInfo::Perms</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 511 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/support/virtualfilesystem-h">VirtualFileSystem.h</a>.</p>


<p>Referenced by <a href="#a397f1399c965b53a95d8dbab6b8b41a3">makeStatus</a>.</p>

</div>
</div>

### Type {#a4474ee6dd8ccbd72eda8e6d6f62b15f8}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">llvm::sys::fs::file_type llvm::vfs::detail::NewInMemoryNodeInfo::Type</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 510 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/support/virtualfilesystem-h">VirtualFileSystem.h</a>.</p>


<p>Referenced by <a href="#a397f1399c965b53a95d8dbab6b8b41a3">makeStatus</a>.</p>

</div>
</div>

### User {#a1fd7831d0ff6eec761f27c37ee2949d1}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">uint32_t llvm::vfs::detail::NewInMemoryNodeInfo::User</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 508 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/support/virtualfilesystem-h">VirtualFileSystem.h</a>.</p>


<p>Referenced by <a href="#a397f1399c965b53a95d8dbab6b8b41a3">makeStatus</a>.</p>

</div>
</div>

</div>

<hr/>

The documentation for this struct was generated from the following files:

<ul>
<li><a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/support/virtualfilesystem-h">VirtualFileSystem.h</a></li>
<li><a href="/web-llvm/docs/api/files/lib/lib/support/virtualfilesystem-cpp">VirtualFileSystem.cpp</a></li>
</ul>

<hr/>

<p class="doxyGeneratedBy">Generated via <a href="https://github.com/xpack/doxygen2docusaurus">doxygen2docusaurus</a> by <a href="https://www.doxygen.nl">Doxygen</a> 1.15.0.</p>

</div>
