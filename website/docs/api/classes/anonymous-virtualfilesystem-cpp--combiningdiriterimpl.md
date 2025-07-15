---

# DO NOT EDIT!
# Automatically generated via doxygen2docusaurus by Doxygen.

slug: /api/classes/anonymous-virtualfilesystem-cpp-/combiningdiriterimpl
custom_edit_url: null
toc_max_heading_level: 4
keywords:
  - doxygen
  - reference
  - class

---

<div class="doxyPage">

# The `CombiningDirIterImpl` Class Reference

<p>Combines and deduplicates directory entries across multiple file systems. <a href="#details">More...</a></p>

## Declaration

<div class="doxyDeclaration">
class anonymous{VirtualFileSystem.cpp}::CombiningDirIterImpl { ... }
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

## Private Member Typedefs Index

<table class="doxyMembersIndex">

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">using</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a733b6262596e57bc384524e33f3444de">FileSystemPtr</a> = <a href="/web-llvm/docs/api/classes/llvm/intrusiverefcntptr">llvm::IntrusiveRefCntPtr</a>&lt; <a href="/web-llvm/docs/api/classes/llvm/vfs/filesystem">llvm::vfs::FileSystem</a> &gt;</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#add1e4acd30e068fc7a65f3c2be9c1855">CombiningDirIterImpl</a> (ArrayRef&lt; FileSystemPtr &gt; FileSystems, std::string Dir, std::error_code &amp;EC)</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a96ad1ece88bc5aa08748719dfedb1f72">CombiningDirIterImpl</a> (ArrayRef&lt; directory_iterator &gt; DirIters, std::error_code &amp;EC)</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ad8a53f1ef68a1a1afce7b963b6595f35">increment</a> () override</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Sets <span class="doxyComputerOutput">CurrentEntry</span> to the next entry in the directory on success, to directory_entry() at end, or returns a system-defined <span class="doxyComputerOutput">error_code</span>. <a href="#ad8a53f1ef68a1a1afce7b963b6595f35">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

</table>

## Private Member Functions Index

<table class="doxyMembersIndex">

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">std::error_code</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a5f2f93276b9db1f297cb866902b2b361">incrementIter</a> (bool IsFirstTime)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Sets <span class="doxyComputerOutput">CurrentDirIter</span> to the next iterator in the list, or leaves it as is (at its end position) if we've already gone through them all. <a href="#a5f2f93276b9db1f297cb866902b2b361">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">std::error_code</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a7a10bf78fcb3a2346bb8a5ea3f9e5bb5">incrementDirIter</a> (bool IsFirstTime)</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a1f714c92e6306858050d7aadb02ea517">incrementImpl</a> (bool IsFirstTime)</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/smallvector">SmallVector</a>&lt; <a href="/web-llvm/docs/api/classes/llvm/vfs/directory-iterator">directory_iterator</a>, 8 &gt;</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a398a04f87f073dd3871a095bb62a56a0">IterList</a></td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Iterators to combine, processed in reverse order. <a href="#a398a04f87f073dd3871a095bb62a56a0">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/vfs/directory-iterator">directory_iterator</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a75f1b975f66d79af0161bcb6ca23c528">CurrentDirIter</a></td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>The iterator currently being traversed. <a href="#a75f1b975f66d79af0161bcb6ca23c528">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/stringset">llvm::StringSet</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a6ad5df9637e06d12d99f087c61cb75e7">SeenNames</a></td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>The set of names already returned as entries. <a href="#a6ad5df9637e06d12d99f087c61cb75e7">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

</table>

## Description {#details}

<p>Combines and deduplicates directory entries across multiple file systems.</p>

<p>Definition at line 537 of file <a href="/web-llvm/docs/api/files/lib/lib/support/virtualfilesystem-cpp">VirtualFileSystem.cpp</a>.</p>


<div class="doxySectionDef">

## Private Member Typedefs

### FileSystemPtr {#a733b6262596e57bc384524e33f3444de}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">using anonymous{VirtualFileSystem.cpp}::CombiningDirIterImpl::FileSystemPtr =  llvm::IntrusiveRefCntPtr&lt;llvm::vfs::FileSystem&gt;</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 538 of file <a href="/web-llvm/docs/api/files/lib/lib/support/virtualfilesystem-cpp">VirtualFileSystem.cpp</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Public Constructors

### CombiningDirIterImpl() {#add1e4acd30e068fc7a65f3c2be9c1855}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">anonymous{VirtualFileSystem.cpp}::CombiningDirIterImpl::CombiningDirIterImpl (<a href="/web-llvm/docs/api/classes/llvm/arrayref">ArrayRef</a>&lt; <a href="/web-llvm/docs/api/classes/llvm/intrusiverefcntptr">FileSystemPtr</a> &gt; FileSystems, std::string Dir, std::error_code &amp; EC)</td>
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



<p>Definition at line 589 of file <a href="/web-llvm/docs/api/files/lib/lib/support/virtualfilesystem-cpp">VirtualFileSystem.cpp</a>.</p>


<p>Reference <a href="/web-llvm/docs/api/namespaces/llvm/#a59739a4f15fb2ec57a6b7fcfe938546ba2e70fc89b08f26fa3fc77694c91e8f7a">llvm::no_such_file_or_directory</a>.</p>

</div>
</div>

### CombiningDirIterImpl() {#a96ad1ece88bc5aa08748719dfedb1f72}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">anonymous{VirtualFileSystem.cpp}::CombiningDirIterImpl::CombiningDirIterImpl (<a href="/web-llvm/docs/api/classes/llvm/arrayref">ArrayRef</a>&lt; <a href="/web-llvm/docs/api/classes/llvm/vfs/directory-iterator">directory_iterator</a> &gt; DirIters, std::error_code &amp; EC)</td>
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



<p>Definition at line 604 of file <a href="/web-llvm/docs/api/files/lib/lib/support/virtualfilesystem-cpp">VirtualFileSystem.cpp</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Public Member Functions

### increment() {#ad8a53f1ef68a1a1afce7b963b6595f35}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">std::error_code anonymous{VirtualFileSystem.cpp}::CombiningDirIterImpl::increment ()</td>
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

<p>Definition at line 610 of file <a href="/web-llvm/docs/api/files/lib/lib/support/virtualfilesystem-cpp">VirtualFileSystem.cpp</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Private Member Functions

### incrementDirIter() {#a7a10bf78fcb3a2346bb8a5ea3f9e5bb5}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">std::error_code anonymous{VirtualFileSystem.cpp}::CombiningDirIterImpl::incrementDirIter (bool IsFirstTime)</td>
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



<p>Definition at line 562 of file <a href="/web-llvm/docs/api/files/lib/lib/support/virtualfilesystem-cpp">VirtualFileSystem.cpp</a>.</p>

</div>
</div>

### incrementImpl() {#a1f714c92e6306858050d7aadb02ea517}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">std::error_code anonymous{VirtualFileSystem.cpp}::CombiningDirIterImpl::incrementImpl (bool IsFirstTime)</td>
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



<p>Definition at line 573 of file <a href="/web-llvm/docs/api/files/lib/lib/support/virtualfilesystem-cpp">VirtualFileSystem.cpp</a>.</p>

</div>
</div>

### incrementIter() {#a5f2f93276b9db1f297cb866902b2b361}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">std::error_code anonymous{VirtualFileSystem.cpp}::CombiningDirIterImpl::incrementIter (bool IsFirstTime)</td>
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

<p>Sets <span class="doxyComputerOutput">CurrentDirIter</span> to the next iterator in the list, or leaves it as is (at its end position) if we've already gone through them all.</p>

<p>Definition at line 549 of file <a href="/web-llvm/docs/api/files/lib/lib/support/virtualfilesystem-cpp">VirtualFileSystem.cpp</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Private Member Attributes

### CurrentDirIter {#a75f1b975f66d79af0161bcb6ca23c528}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">directory_iterator anonymous{VirtualFileSystem.cpp}::CombiningDirIterImpl::CurrentDirIter</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>The iterator currently being traversed.</p>

<p>Definition at line 543 of file <a href="/web-llvm/docs/api/files/lib/lib/support/virtualfilesystem-cpp">VirtualFileSystem.cpp</a>.</p>

</div>
</div>

### IterList {#a398a04f87f073dd3871a095bb62a56a0}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">SmallVector&lt;directory_iterator, 8&gt; anonymous{VirtualFileSystem.cpp}::CombiningDirIterImpl::IterList</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Iterators to combine, processed in reverse order.</p>

<p>Definition at line 541 of file <a href="/web-llvm/docs/api/files/lib/lib/support/virtualfilesystem-cpp">VirtualFileSystem.cpp</a>.</p>

</div>
</div>

### SeenNames {#a6ad5df9637e06d12d99f087c61cb75e7}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">llvm::StringSet anonymous{VirtualFileSystem.cpp}::CombiningDirIterImpl::SeenNames</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>The set of names already returned as entries.</p>

<p>Definition at line 545 of file <a href="/web-llvm/docs/api/files/lib/lib/support/virtualfilesystem-cpp">VirtualFileSystem.cpp</a>.</p>

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
