---

# DO NOT EDIT!
# Automatically generated via doxygen2docusaurus by Doxygen.

slug: /api/structs/llvm/vfs/detail/diriterimpl
custom_edit_url: null
toc_max_heading_level: 4
keywords:
  - doxygen
  - reference
  - struct

---

<div class="doxyPage">

# `DirIterImpl` Struct

<p>An interface for virtual file systems to provide an iterator over the (non-recursive) contents of a directory. <a href="#details">More...</a></p>

## Declaration

<div class="doxyDeclaration">
struct llvm::vfs::detail::DirIterImpl { ... }
</div>

## Included Headers

<div class="doxyIncludesList">#include "<a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/support/virtualfilesystem-h">llvm/Support/VirtualFileSystem.h</a>"
</div>

## Derived Structs

<table class="doxyMembersIndex">

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">class</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="/web-llvm/docs/api/classes/anonymous-virtualfilesystem-cpp-/combiningdiriterimpl">CombiningDirIterImpl</a></td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Combines and deduplicates directory entries across multiple file systems. <a href="/web-llvm/docs/api/classes/anonymous-virtualfilesystem-cpp-/combiningdiriterimpl/#details">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">class</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="/web-llvm/docs/api/classes/anonymous-virtualfilesystem-cpp-/realfsdiriter">RealFSDirIter</a></td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">class</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="/web-llvm/docs/api/classes/anonymous-virtualfilesystem-cpp-/redirectingfsdirremapiterimpl">RedirectingFSDirRemapIterImpl</a></td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Directory iterator implementation for <span class="doxyComputerOutput"><a href="/web-llvm/docs/api/classes/llvm/vfs/redirectingfilesystem">RedirectingFileSystem</a>'s</span> directory remap entries that maps the paths reported by the external file system's directory iterator back to the virtual directory's path. <a href="/web-llvm/docs/api/classes/anonymous-virtualfilesystem-cpp-/redirectingfsdirremapiterimpl/#details">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">class</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/vfs/inmemoryfilesystem/diriterator">DirIterator</a></td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Adaptor from InMemoryDir::iterator to <a href="/web-llvm/docs/api/classes/llvm/vfs/directory-iterator">directory_iterator</a>. <a href="/web-llvm/docs/api/classes/llvm/vfs/inmemoryfilesystem/diriterator/#details">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">class</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/vfs/redirectingfsdiriterimpl">RedirectingFSDirIterImpl</a></td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Directory iterator implementation for <span class="doxyComputerOutput"><a href="/web-llvm/docs/api/classes/llvm/vfs/redirectingfilesystem">RedirectingFileSystem</a>'s</span> directory entries. <a href="/web-llvm/docs/api/classes/llvm/vfs/redirectingfsdiriterimpl/#details">More...</a></p>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a4e76fbf32c9cbec19f7eab6bdca3383a">~DirIterImpl</a> ()</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">std::error_code</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a340b632c7fe3533e603e37b3fea83c92">increment</a> ()=0</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Sets <span class="doxyComputerOutput">CurrentEntry</span> to the next entry in the directory on success, to directory_entry() at end, or returns a system-defined <span class="doxyComputerOutput">error_code</span>. <a href="#a340b632c7fe3533e603e37b3fea83c92">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

</table>

## Public Member Attributes Index

<table class="doxyMembersIndex">

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/vfs/directory-entry">directory_entry</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a918b2aff106378329b31a61236e2d1f8">CurrentEntry</a></td>
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

<p>An interface for virtual file systems to provide an iterator over the (non-recursive) contents of a directory.</p>

<p>Definition at line 165 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/support/virtualfilesystem-h">VirtualFileSystem.h</a>.</p>


<div class="doxySectionDef">

## Public Destructor

### \~DirIterImpl() {#a4e76fbf32c9cbec19f7eab6bdca3383a}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">llvm::vfs::detail::DirIterImpl::~DirIterImpl ()</td>
</tr>
</table>
</td>
<td class="doxyMemberLabelsRight">
<span class="doxyMemberLabels">
<span class="doxyMemberLabel virtual">virtual</span>
</span>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 166 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/support/virtualfilesystem-h">VirtualFileSystem.h</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Public Member Functions

### increment() {#a340b632c7fe3533e603e37b3fea83c92}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">virtual std::error_code llvm::vfs::detail::DirIterImpl::increment ()</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Sets <span class="doxyComputerOutput">CurrentEntry</span> to the next entry in the directory on success, to directory_entry() at end, or returns a system-defined <span class="doxyComputerOutput">error_code</span>.</p>

<p>Definition at line 170 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/support/virtualfilesystem-h">VirtualFileSystem.h</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Public Member Attributes

### CurrentEntry {#a918b2aff106378329b31a61236e2d1f8}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">directory_entry llvm::vfs::detail::DirIterImpl::CurrentEntry</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 172 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/support/virtualfilesystem-h">VirtualFileSystem.h</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/classes/anonymous-virtualfilesystem-cpp-/realfsdiriter/#a06791f6716c261bf185bbc92c10f51c3">anonymous{VirtualFileSystem.cpp}::RealFSDirIter::increment</a>, <a href="/web-llvm/docs/api/classes/anonymous-virtualfilesystem-cpp-/redirectingfsdirremapiterimpl/#a7b47ac6c38e751be3080530aab594a84">anonymous{VirtualFileSystem.cpp}::RedirectingFSDirRemapIterImpl::increment</a>, <a href="/web-llvm/docs/api/classes/anonymous-virtualfilesystem-cpp-/realfsdiriter/#afc36245765d761ea5d413d0d11f066d7">anonymous{VirtualFileSystem.cpp}::RealFSDirIter::RealFSDirIter</a> and <a href="/web-llvm/docs/api/classes/anonymous-virtualfilesystem-cpp-/redirectingfsdirremapiterimpl/#ad69a8251f6cfe071e414c7c3cf78cb9c">anonymous{VirtualFileSystem.cpp}::RedirectingFSDirRemapIterImpl::setCurrentEntry</a>.</p>

</div>
</div>

</div>

<hr/>

The documentation for this struct was generated from the following file:

<ul>
<li><a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/support/virtualfilesystem-h">VirtualFileSystem.h</a></li>
</ul>

<hr/>

<p class="doxyGeneratedBy">Generated via <a href="https://github.com/xpack/doxygen2docusaurus">doxygen2docusaurus</a> by <a href="https://www.doxygen.nl">Doxygen</a> 1.15.0.</p>

</div>
