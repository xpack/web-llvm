---

# DO NOT EDIT!
# Automatically generated via doxygen2docusaurus by Doxygen.

slug: /api/classes/anonymous-virtualfilesystem-cpp-/redirectingfsdirremapiterimpl
custom_edit_url: null
toc_max_heading_level: 4
keywords:
  - doxygen
  - reference
  - class

---

<div class="doxyPage">

# The `RedirectingFSDirRemapIterImpl` Class Reference

<p>Directory iterator implementation for <span class="doxyComputerOutput"><a href="/web-llvm/docs/api/classes/llvm/vfs/redirectingfilesystem">RedirectingFileSystem</a>'s</span> directory remap entries that maps the paths reported by the external file system's directory iterator back to the virtual directory's path. <a href="#details">More...</a></p>

## Declaration

<div class="doxyDeclaration">
class anonymous{VirtualFileSystem.cpp}::RedirectingFSDirRemapIterImpl { ... }
</div>

## Base class

<table class="doxyMembersIndex">

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">struct</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="/web-llvm/docs/api/structs/llvm/vfs/detail/diriterimpl">DirIterImpl</a></td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>An interface for virtual file systems to provide an iterator over the (non-recursive) contents of a directory. <a href="/web-llvm/docs/api/structs/llvm/vfs/detail/diriterimpl/#details">More...</a></p>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a7d070f6d8648473280f63344badb98ff">RedirectingFSDirRemapIterImpl</a> (std::string DirPath, llvm::vfs::directory_iterator ExtIter)</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">void</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ad69a8251f6cfe071e414c7c3cf78cb9c">setCurrentEntry</a> ()</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a7b47ac6c38e751be3080530aab594a84">increment</a> () override</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Sets <span class="doxyComputerOutput">CurrentEntry</span> to the next entry in the directory on success, to directory_entry() at end, or returns a system-defined <span class="doxyComputerOutput">error_code</span>. <a href="#a7b47ac6c38e751be3080530aab594a84">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

</table>

## Private Member Attributes Index

<table class="doxyMembersIndex">

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">std::string</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#aeb68afa1c562e29e48bd56d903b022a4">Dir</a></td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/namespaces/llvm/sys/path/#a58cfd8a47c0ef96db27b451c2d6ec49f">llvm::sys::path::Style</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ab191662d2e15314e5d093b85ecd1f019">DirStyle</a></td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a1d29a28aeb7f08f99c222f3a3de77f52">ExternalIter</a></td>
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

<p>Directory iterator implementation for <span class="doxyComputerOutput"><a href="/web-llvm/docs/api/classes/llvm/vfs/redirectingfilesystem">RedirectingFileSystem</a>'s</span> directory remap entries that maps the paths reported by the external file system's directory iterator back to the virtual directory's path.</p>

<p>Definition at line 1315 of file <a href="/web-llvm/docs/api/files/lib/lib/support/virtualfilesystem-cpp">VirtualFileSystem.cpp</a>.</p>


<div class="doxySectionDef">

## Public Constructors

### RedirectingFSDirRemapIterImpl() {#a7d070f6d8648473280f63344badb98ff}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">anonymous{VirtualFileSystem.cpp}::RedirectingFSDirRemapIterImpl::RedirectingFSDirRemapIterImpl (std::string DirPath, <a href="/web-llvm/docs/api/classes/llvm/vfs/directory-iterator">llvm::vfs::directory_iterator</a> ExtIter)</td>
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



<p>Definition at line 1321 of file <a href="/web-llvm/docs/api/files/lib/lib/support/virtualfilesystem-cpp">VirtualFileSystem.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/namespaces/anonymous-virtualfilesystem-cpp-/#af37b1b2c545fd96b71361d7b41e37fbb">anonymous{VirtualFileSystem.cpp}::getExistingStyle</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#abfc9c7ecf70f66901e439f7c04ef3dbb">llvm::move</a> and <a href="#ad69a8251f6cfe071e414c7c3cf78cb9c">setCurrentEntry</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Public Member Functions

### increment() {#a7b47ac6c38e751be3080530aab594a84}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">std::error_code anonymous{VirtualFileSystem.cpp}::RedirectingFSDirRemapIterImpl::increment ()</td>
</tr>
</table>
</td>
<td class="doxyMemberLabelsRight">
<span class="doxyMemberLabels">
<span class="doxyMemberLabel inline">inline</span>
<span class="doxyMemberLabel virtual">virtual</span>
</span>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Sets <span class="doxyComputerOutput">CurrentEntry</span> to the next entry in the directory on success, to directory_entry() at end, or returns a system-defined <span class="doxyComputerOutput">error_code</span>.</p>

<p>Definition at line 1340 of file <a href="/web-llvm/docs/api/files/lib/lib/support/virtualfilesystem-cpp">VirtualFileSystem.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/structs/llvm/vfs/detail/diriterimpl/#a918b2aff106378329b31a61236e2d1f8">llvm::vfs::detail::DirIterImpl::CurrentEntry</a> and <a href="#ad69a8251f6cfe071e414c7c3cf78cb9c">setCurrentEntry</a>.</p>

</div>
</div>

### setCurrentEntry() {#ad69a8251f6cfe071e414c7c3cf78cb9c}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void anonymous{VirtualFileSystem.cpp}::RedirectingFSDirRemapIterImpl::setCurrentEntry ()</td>
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



<p>Definition at line 1329 of file <a href="/web-llvm/docs/api/files/lib/lib/support/virtualfilesystem-cpp">VirtualFileSystem.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/namespaces/llvm/sys/path/#acb80894344c78dacf8d5ff8c23be697d">llvm::sys::path::append</a>, <a href="/web-llvm/docs/api/structs/llvm/vfs/detail/diriterimpl/#a918b2aff106378329b31a61236e2d1f8">llvm::vfs::detail::DirIterImpl::CurrentEntry</a>, <a href="/web-llvm/docs/api/namespaces/llvm/sys/path/#aa56d25bb5127dd7a5831c25764f76cbe">llvm::sys::path::filename</a> and <a href="/web-llvm/docs/api/namespaces/anonymous-virtualfilesystem-cpp-/#af37b1b2c545fd96b71361d7b41e37fbb">anonymous{VirtualFileSystem.cpp}::getExistingStyle</a>.</p>


<p>Referenced by <a href="#a7b47ac6c38e751be3080530aab594a84">increment</a> and <a href="#a7d070f6d8648473280f63344badb98ff">RedirectingFSDirRemapIterImpl</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Private Member Attributes

### Dir {#aeb68afa1c562e29e48bd56d903b022a4}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">std::string anonymous{VirtualFileSystem.cpp}::RedirectingFSDirRemapIterImpl::Dir</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 1316 of file <a href="/web-llvm/docs/api/files/lib/lib/support/virtualfilesystem-cpp">VirtualFileSystem.cpp</a>.</p>

</div>
</div>

### DirStyle {#ab191662d2e15314e5d093b85ecd1f019}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">llvm::sys::path::Style anonymous{VirtualFileSystem.cpp}::RedirectingFSDirRemapIterImpl::DirStyle</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 1317 of file <a href="/web-llvm/docs/api/files/lib/lib/support/virtualfilesystem-cpp">VirtualFileSystem.cpp</a>.</p>

</div>
</div>

### ExternalIter {#a1d29a28aeb7f08f99c222f3a3de77f52}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">llvm::vfs::directory_iterator anonymous{VirtualFileSystem.cpp}::RedirectingFSDirRemapIterImpl::ExternalIter</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 1318 of file <a href="/web-llvm/docs/api/files/lib/lib/support/virtualfilesystem-cpp">VirtualFileSystem.cpp</a>.</p>

</div>
</div>

</div>

<hr/>

The documentation for this class was generated from the following file:

<ul>
<li><a href="/web-llvm/docs/api/files/lib/lib/support/virtualfilesystem-cpp">VirtualFileSystem.cpp</a></li>
</ul>

<hr/>

<p class="doxyGeneratedBy">Generated via <a href="https://github.com/xpack/doxygen2docusaurus">doxygen2docusaurus</a> by <a href="https://www.doxygen.nl">Doxygen</a> 1.14.0.</p>

</div>
