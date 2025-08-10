---

# DO NOT EDIT!
# Automatically generated via doxygen2docusaurus by Doxygen.

slug: /api/structs/llvm/vfs/redirectingfilesystem/lookupresult
custom_edit_url: null
toc_max_heading_level: 4
keywords:
  - doxygen
  - reference
  - struct

---

<div class="doxyPage">

# `LookupResult` Struct

<p>Represents the result of a path lookup into the <a href="/web-llvm/docs/api/classes/llvm/vfs/redirectingfilesystem">RedirectingFileSystem</a>. <a href="#details">More...</a></p>

## Declaration

<div class="doxyDeclaration">
struct llvm::vfs::RedirectingFileSystem::LookupResult { ... }
</div>

## Included Headers

<div class="doxyIncludesList">#include "<a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/support/virtualfilesystem-h">llvm/Support/VirtualFileSystem.h</a>"
</div>

## Public Constructors Index

<table class="doxyMembersIndex">

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#aa3989e2bdf4525841695dae351252b79">LookupResult</a> (Entry *E, sys::path::const_iterator Start, sys::path::const_iterator End)</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">std::optional&lt; <a href="/web-llvm/docs/api/classes/llvm/stringref">StringRef</a> &gt;</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a124bbf0bcca319d0cad7086bc6091e29">getExternalRedirect</a> () const</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>If the found <a href="/web-llvm/docs/api/classes/llvm/vfs/redirectingfilesystem/entry">Entry</a> maps the input path to a path in the external file system (i.e. <a href="#a124bbf0bcca319d0cad7086bc6091e29">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">void</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#aaaa3106261fa4af53b07b638d39a1ae3">getPath</a> (llvm::SmallVectorImpl&lt; char &gt; &amp;Path) const</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Get the (canonical) path of the found entry. <a href="#aaaa3106261fa4af53b07b638d39a1ae3">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

</table>

## Public Member Attributes Index

<table class="doxyMembersIndex">

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/smallvector">llvm::SmallVector</a>&lt; <a href="/web-llvm/docs/api/classes/llvm/vfs/redirectingfilesystem/entry">Entry</a> *, 32 &gt;</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ac7cef64065fa5eb111e8933b82bf99c3">Parents</a></td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Chain of parent directory entries for <span class="doxyComputerOutput">E</span>. <a href="#ac7cef64065fa5eb111e8933b82bf99c3">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/vfs/redirectingfilesystem/entry">Entry</a> *</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#aa08d8fa6ea0d38d9a46da1e24d23b036">E</a></td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>The entry the looked-up path corresponds to. <a href="#aa08d8fa6ea0d38d9a46da1e24d23b036">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

</table>

## Private Member Attributes Index

<table class="doxyMembersIndex">

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">std::optional&lt; std::string &gt;</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a80fcc18a102b170bdc4ab84ab2c3bf60">ExternalRedirect</a></td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>When the found <a href="/web-llvm/docs/api/classes/llvm/vfs/redirectingfilesystem/entry">Entry</a> is a <a href="/web-llvm/docs/api/classes/llvm/vfs/redirectingfilesystem/directoryremapentry">DirectoryRemapEntry</a>, stores the path in the external file system that the looked-up path in the virtual file system. <a href="#a80fcc18a102b170bdc4ab84ab2c3bf60">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

</table>

## Description {#details}

<p>Represents the result of a path lookup into the <a href="/web-llvm/docs/api/classes/llvm/vfs/redirectingfilesystem">RedirectingFileSystem</a>.</p>

<p>Definition at line 911 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/support/virtualfilesystem-h">VirtualFileSystem.h</a>.</p>


<div class="doxySectionDef">

## Public Constructors

### LookupResult() {#aa3989e2bdf4525841695dae351252b79}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">RedirectingFileSystem::LookupResult::LookupResult (<a href="/web-llvm/docs/api/classes/llvm/vfs/redirectingfilesystem/entry">Entry</a> * E, <a href="/web-llvm/docs/api/classes/llvm/sys/path/const-iterator">sys::path::const_iterator</a> Start, <a href="/web-llvm/docs/api/classes/llvm/sys/path/const-iterator">sys::path::const_iterator</a> End)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Declaration at line 925 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/support/virtualfilesystem-h">VirtualFileSystem.h</a>, definition at line 2271 of file <a href="/web-llvm/docs/api/files/lib/lib/support/virtualfilesystem-cpp">VirtualFileSystem.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/namespaces/llvm/sys/path/#acb80894344c78dacf8d5ff8c23be697d">llvm::sys::path::append</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/silowercontrolflow-cpp/#a4868c5d81c5ccc98c47aeab6244346a0">assert</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a22eeee01734061ac1b31ccd994c49eef">llvm::dyn_cast</a> and <a href="#aa08d8fa6ea0d38d9a46da1e24d23b036">E</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Public Member Functions

### getExternalRedirect() {#a124bbf0bcca319d0cad7086bc6091e29}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">std::optional&lt; StringRef &gt; llvm::vfs::RedirectingFileSystem::LookupResult::getExternalRedirect ()</td>
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

<p>If the found <a href="/web-llvm/docs/api/classes/llvm/vfs/redirectingfilesystem/entry">Entry</a> maps the input path to a path in the external file system (i.e.</p>


<p>it is a <a href="/web-llvm/docs/api/classes/llvm/vfs/redirectingfilesystem/fileentry">FileEntry</a> or <a href="/web-llvm/docs/api/classes/llvm/vfs/redirectingfilesystem/directoryremapentry">DirectoryRemapEntry</a>), returns that path.</p>


<p>Definition at line 931 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/support/virtualfilesystem-h">VirtualFileSystem.h</a>.</p>


<p>References <a href="/web-llvm/docs/api/namespaces/llvm/#a22eeee01734061ac1b31ccd994c49eef">llvm::dyn_cast</a>, <a href="#aa08d8fa6ea0d38d9a46da1e24d23b036">E</a> and <a href="/web-llvm/docs/api/namespaces/llvm/#a92ca992e52dddc420f4b069cae06dfbe">llvm::isa</a>.</p>

</div>
</div>

### getPath() {#aaaa3106261fa4af53b07b638d39a1ae3}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void RedirectingFileSystem::LookupResult::getPath (<a href="/web-llvm/docs/api/classes/llvm/smallvectorimpl">llvm::SmallVectorImpl</a>&lt; char &gt; &amp; Path)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Get the (canonical) path of the found entry.</p>


<p>This uses the as-written path components from the VFS specification.</p>


<p>Declaration at line 941 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/support/virtualfilesystem-h">VirtualFileSystem.h</a>, definition at line 2286 of file <a href="/web-llvm/docs/api/files/lib/lib/support/virtualfilesystem-cpp">VirtualFileSystem.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/namespaces/llvm/sys/path/#acb80894344c78dacf8d5ff8c23be697d">llvm::sys::path::append</a>, <a href="#aa08d8fa6ea0d38d9a46da1e24d23b036">E</a> and <a href="#ac7cef64065fa5eb111e8933b82bf99c3">Parents</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Public Member Attributes

### E {#aa08d8fa6ea0d38d9a46da1e24d23b036}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">Entry* llvm::vfs::RedirectingFileSystem::LookupResult::E</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>The entry the looked-up path corresponds to.</p>

<p>Definition at line 916 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/support/virtualfilesystem-h">VirtualFileSystem.h</a>.</p>


<p>Referenced by <a href="#a124bbf0bcca319d0cad7086bc6091e29">getExternalRedirect</a>, <a href="#aaaa3106261fa4af53b07b638d39a1ae3">getPath</a> and <a href="#aa3989e2bdf4525841695dae351252b79">LookupResult</a>.</p>

</div>
</div>

### Parents {#ac7cef64065fa5eb111e8933b82bf99c3}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">llvm::SmallVector&lt;Entry *, 32&gt; llvm::vfs::RedirectingFileSystem::LookupResult::Parents</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Chain of parent directory entries for <span class="doxyComputerOutput">E</span>.</p>

<p>Definition at line 913 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/support/virtualfilesystem-h">VirtualFileSystem.h</a>.</p>


<p>Referenced by <a href="#aaaa3106261fa4af53b07b638d39a1ae3">getPath</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Private Member Attributes

### ExternalRedirect {#a80fcc18a102b170bdc4ab84ab2c3bf60}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">std::optional&lt;std::string&gt; llvm::vfs::RedirectingFileSystem::LookupResult::ExternalRedirect</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>When the found <a href="/web-llvm/docs/api/classes/llvm/vfs/redirectingfilesystem/entry">Entry</a> is a <a href="/web-llvm/docs/api/classes/llvm/vfs/redirectingfilesystem/directoryremapentry">DirectoryRemapEntry</a>, stores the path in the external file system that the looked-up path in the virtual file system.</p>

<p>Definition at line 922 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/support/virtualfilesystem-h">VirtualFileSystem.h</a>.</p>

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

<p class="doxyGeneratedBy">Generated via <a href="https://xpack.github.io/doxygen2docusaurus">doxygen2docusaurus</a> 2.0.0 by <a href="https://www.doxygen.nl">Doxygen</a> 1.15.0.</p>

</div>
