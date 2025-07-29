---

# DO NOT EDIT!
# Automatically generated via doxygen2docusaurus by Doxygen.

slug: /api/namespaces/llvm/vfs
custom_edit_url: null
toc_max_heading_level: 4
keywords:
  - doxygen
  - reference
  - namespace

---

<div class="doxyPage">

# `vfs` Namespace



## Definition

<div class="doxyDefinition">
namespace llvm::vfs { ... }
</div>

## Namespaces Index

<table class="doxyMembersIndex">

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">namespace</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="/web-llvm/docs/api/namespaces/llvm/vfs/detail">detail</a></td>
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

## Classes Index

<table class="doxyMembersIndex">

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">class</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/vfs/status">Status</a></td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>The result of a <span class="doxyComputerOutput">status</span> operation. <a href="/web-llvm/docs/api/classes/llvm/vfs/status/#details">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">class</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/vfs/file">File</a></td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Represents an open file. <a href="/web-llvm/docs/api/classes/llvm/vfs/file/#details">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">class</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/vfs/directory-entry">directory_entry</a></td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>A member of a directory, yielded by a <a href="/web-llvm/docs/api/classes/llvm/vfs/directory-iterator">directory_iterator</a>. <a href="/web-llvm/docs/api/classes/llvm/vfs/directory-entry/#details">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">class</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/vfs/directory-iterator">directory_iterator</a></td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>An input iterator over the entries in a virtual path, similar to <a href="/web-llvm/docs/api/classes/llvm/sys/fs/directory-iterator">llvm::sys::fs::directory_iterator</a>. <a href="/web-llvm/docs/api/classes/llvm/vfs/directory-iterator/#details">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">class</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/vfs/recursive-directory-iterator">recursive_directory_iterator</a></td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>An input iterator over the recursive contents of a virtual path, similar to <a href="/web-llvm/docs/api/classes/llvm/sys/fs/recursive-directory-iterator">llvm::sys::fs::recursive_directory_iterator</a>. <a href="/web-llvm/docs/api/classes/llvm/vfs/recursive-directory-iterator/#details">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">class</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/vfs/filesystem">FileSystem</a></td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>The virtual file system interface. <a href="/web-llvm/docs/api/classes/llvm/vfs/filesystem/#details">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">class</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/vfs/overlayfilesystem">OverlayFileSystem</a></td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>A file system that allows overlaying one <span class="doxyComputerOutput">AbstractFileSystem</span> on top of another. <a href="/web-llvm/docs/api/classes/llvm/vfs/overlayfilesystem/#details">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">class</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/vfs/proxyfilesystem">ProxyFileSystem</a></td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>By default, this delegates all calls to the underlying file system. <a href="/web-llvm/docs/api/classes/llvm/vfs/proxyfilesystem/#details">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">class</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/vfs/inmemoryfilesystem">InMemoryFileSystem</a></td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>An in-memory file system. <a href="/web-llvm/docs/api/classes/llvm/vfs/inmemoryfilesystem/#details">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">struct</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="/web-llvm/docs/api/structs/llvm/vfs/yamlvfsentry">YAMLVFSEntry</a></td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/vfs/redirectingfilesystem">RedirectingFileSystem</a></td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>A virtual file system parsed from a YAML file. <a href="/web-llvm/docs/api/classes/llvm/vfs/redirectingfilesystem/#details">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">class</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/vfs/yamlvfswriter">YAMLVFSWriter</a></td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/vfs/tracingfilesystem">TracingFileSystem</a></td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p><a href="/web-llvm/docs/api/classes/llvm/vfs/file">File</a> system that tracks the number of calls to the underlying file system. <a href="/web-llvm/docs/api/classes/llvm/vfs/tracingfilesystem/#details">More...</a></p>
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

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">class</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/vfs/redirectingfilesystemparser">RedirectingFileSystemParser</a></td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>A helper class to hold the common YAML parsing state. <a href="/web-llvm/docs/api/classes/llvm/vfs/redirectingfilesystemparser/#details">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

</table>

## Functions Index

<table class="doxyMembersIndex">

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/intrusiverefcntptr">IntrusiveRefCntPtr</a>&lt; <a href="/web-llvm/docs/api/classes/llvm/vfs/filesystem">FileSystem</a> &gt;</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a9878c6a5a53d24e17c7c1002be31364c">getRealFileSystem</a> ()</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Gets an <span class="doxyComputerOutput"><a href="/web-llvm/docs/api/classes/llvm/vfs/filesystem">vfs::FileSystem</a></span> for the 'real' file system, as seen by the operating system. <a href="#a9878c6a5a53d24e17c7c1002be31364c">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">std::unique_ptr&lt; <a href="/web-llvm/docs/api/classes/llvm/vfs/filesystem">FileSystem</a> &gt;</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a6b309a3a56a77467114e10a162bcc2a3">createPhysicalFileSystem</a> ()</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Create an <span class="doxyComputerOutput"><a href="/web-llvm/docs/api/classes/llvm/vfs/filesystem">vfs::FileSystem</a></span> for the 'real' file system, as seen by the operating system. <a href="#a6b309a3a56a77467114e10a162bcc2a3">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/sys/fs/uniqueid">llvm::sys::fs::UniqueID</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a7065249494c24a6413b5fd0146ebcc26">getNextVirtualUniqueID</a> ()</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Get a globally unique <a href="/web-llvm/docs/api/namespaces/llvm/callingconv/#abdf8cf606905c10634e831390981b0ed">ID</a> for a virtual file or directory. <a href="#a7065249494c24a6413b5fd0146ebcc26">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">std::unique_ptr&lt; <a href="/web-llvm/docs/api/classes/llvm/vfs/filesystem">FileSystem</a> &gt;</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a52ebaf7577ad1061d056fdfbfafb9ddf">getVFSFromYAML</a> (std::unique_ptr&lt; llvm::MemoryBuffer &gt; Buffer, llvm::SourceMgr::DiagHandlerTy DiagHandler, StringRef YAMLFilePath, void *DiagContext=nullptr, IntrusiveRefCntPtr&lt; FileSystem &gt; ExternalFS=getRealFileSystem())</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Gets a <span class="doxyComputerOutput"><a href="/web-llvm/docs/api/classes/llvm/vfs/filesystem">FileSystem</a></span> for a virtual file system described in YAML format. <a href="#a52ebaf7577ad1061d056fdfbfafb9ddf">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">void</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a46113a125eb290e06b4d7fa98225a616">collectVFSFromYAML</a> (std::unique_ptr&lt; llvm::MemoryBuffer &gt; Buffer, llvm::SourceMgr::DiagHandlerTy DiagHandler, StringRef YAMLFilePath, SmallVectorImpl&lt; YAMLVFSEntry &gt; &amp;CollectedEntries, void *DiagContext=nullptr, IntrusiveRefCntPtr&lt; FileSystem &gt; ExternalFS=getRealFileSystem())</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Collect all pairs of &lt;virtual path, real path&gt; entries from the <span class="doxyComputerOutput">YAMLFilePath</span>. <a href="#a46113a125eb290e06b4d7fa98225a616">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">static <a href="/web-llvm/docs/api/classes/llvm/sys/fs/uniqueid">sys::fs::UniqueID</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a706e7f6e44dfa930a6e48122c581c009">getUniqueID</a> (hash_code Hash)</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">static <a href="/web-llvm/docs/api/classes/llvm/sys/fs/uniqueid">sys::fs::UniqueID</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a6d887ec0b854b52f125578e7e3b5ac03">getFileID</a> (sys::fs::UniqueID Parent, llvm::StringRef Name, llvm::StringRef Contents)</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">static <a href="/web-llvm/docs/api/classes/llvm/sys/fs/uniqueid">sys::fs::UniqueID</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#aadf74a30b19f30570211b95b9e379884">getDirectoryID</a> (sys::fs::UniqueID Parent, llvm::StringRef Name)</td>
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


<div class="doxySectionDef">

## Functions

### collectVFSFromYAML() {#a46113a125eb290e06b4d7fa98225a616}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void llvm::vfs::collectVFSFromYAML (std::unique_ptr&lt; <a href="/web-llvm/docs/api/classes/llvm/memorybuffer">llvm::MemoryBuffer</a> &gt; Buffer, <a href="/web-llvm/docs/api/classes/llvm/sourcemgr/#acf78be89ec851a45f37a776a5a58bfe8">llvm::SourceMgr::DiagHandlerTy</a> DiagHandler, <a href="/web-llvm/docs/api/classes/llvm/stringref">StringRef</a> YAMLFilePath, <a href="/web-llvm/docs/api/classes/llvm/smallvectorimpl">SmallVectorImpl</a>&lt; <a href="/web-llvm/docs/api/structs/llvm/vfs/yamlvfsentry">YAMLVFSEntry</a> &gt; &amp; CollectedEntries, void * DiagContext=nullptr, <a href="/web-llvm/docs/api/classes/llvm/intrusiverefcntptr">IntrusiveRefCntPtr</a>&lt; <a href="/web-llvm/docs/api/classes/llvm/vfs/filesystem">FileSystem</a> &gt; ExternalFS=<a href="#a9878c6a5a53d24e17c7c1002be31364c">getRealFileSystem</a>())</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Collect all pairs of &lt;virtual path, real path&gt; entries from the <span class="doxyComputerOutput">YAMLFilePath</span>.</p>


<p>This is used by the module dependency collector to forward the entries into the reproducer output VFS YAML file.</p>


<p>Definition at line 1110 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/support/virtualfilesystem-h">VirtualFileSystem.h</a>.</p>


<p>Reference <a href="/web-llvm/docs/api/files/lib/lib/textapi/textstub-cpp/#aa9f07add63589fb3b28821d089f069a7">DiagHandler</a>.</p>

</div>
</div>

### createPhysicalFileSystem() {#a6b309a3a56a77467114e10a162bcc2a3}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">std::unique_ptr&lt; FileSystem &gt; llvm::vfs::createPhysicalFileSystem ()</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Create an <span class="doxyComputerOutput"><a href="/web-llvm/docs/api/classes/llvm/vfs/filesystem">vfs::FileSystem</a></span> for the 'real' file system, as seen by the operating system.</p>


<p>It has its own working directory, independent of (but initially equal to) that of the process.</p>


<p>Declaration at line 379 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/support/virtualfilesystem-h">VirtualFileSystem.h</a>, definition at line 404 of file <a href="/web-llvm/docs/api/files/lib/lib/support/virtualfilesystem-cpp">VirtualFileSystem.cpp</a>.</p>

</div>
</div>

### getDirectoryID() {#aadf74a30b19f30570211b95b9e379884}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">sys::fs::UniqueID llvm::vfs::getDirectoryID (<a href="/web-llvm/docs/api/classes/llvm/sys/fs/uniqueid">sys::fs::UniqueID</a> Parent, <a href="/web-llvm/docs/api/classes/llvm/stringref">llvm::StringRef</a> Name)</td>
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



<p>Definition at line 823 of file <a href="/web-llvm/docs/api/files/lib/lib/support/virtualfilesystem-cpp">VirtualFileSystem.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/classes/llvm/sys/fs/uniqueid/#aa24a935122d883d1475f528311317151">llvm::sys::fs::UniqueID::getFile</a>, <a href="#a706e7f6e44dfa930a6e48122c581c009">getUniqueID</a> and <a href="/web-llvm/docs/api/namespaces/llvm/#add71474638430694c84640146383fc44">llvm::hash_combine</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/classes/llvm/vfs/inmemoryfilesystem/#a5fd6b2b27c08aa31009474233d537b0b">llvm::vfs::InMemoryFileSystem::InMemoryFileSystem</a> and <a href="/web-llvm/docs/api/structs/llvm/vfs/detail/newinmemorynodeinfo/#a397f1399c965b53a95d8dbab6b8b41a3">llvm::vfs::detail::NewInMemoryNodeInfo::makeStatus</a>.</p>

</div>
</div>

### getFileID() {#a6d887ec0b854b52f125578e7e3b5ac03}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">sys::fs::UniqueID llvm::vfs::getFileID (<a href="/web-llvm/docs/api/classes/llvm/sys/fs/uniqueid">sys::fs::UniqueID</a> Parent, <a href="/web-llvm/docs/api/classes/llvm/stringref">llvm::StringRef</a> Name, <a href="/web-llvm/docs/api/classes/llvm/stringref">llvm::StringRef</a> Contents)</td>
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



<p>Definition at line 818 of file <a href="/web-llvm/docs/api/files/lib/lib/support/virtualfilesystem-cpp">VirtualFileSystem.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/classes/llvm/sys/fs/uniqueid/#aa24a935122d883d1475f528311317151">llvm::sys::fs::UniqueID::getFile</a>, <a href="#a706e7f6e44dfa930a6e48122c581c009">getUniqueID</a> and <a href="/web-llvm/docs/api/namespaces/llvm/#add71474638430694c84640146383fc44">llvm::hash_combine</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/structs/llvm/vfs/detail/newinmemorynodeinfo/#a397f1399c965b53a95d8dbab6b8b41a3">llvm::vfs::detail::NewInMemoryNodeInfo::makeStatus</a>.</p>

</div>
</div>

### getNextVirtualUniqueID() {#a7065249494c24a6413b5fd0146ebcc26}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">UniqueID llvm::vfs::getNextVirtualUniqueID ()</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Get a globally unique <a href="/web-llvm/docs/api/namespaces/llvm/callingconv/#abdf8cf606905c10634e831390981b0ed">ID</a> for a virtual file or directory.</p>

<p>Declaration at line 654 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/support/virtualfilesystem-h">VirtualFileSystem.h</a>, definition at line 2729 of file <a href="/web-llvm/docs/api/files/lib/lib/support/virtualfilesystem-cpp">VirtualFileSystem.cpp</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/classes/llvm/vfs/redirectingfilesystemparser/#ac3b4d9a8bed01afc755fcbd6ecdee265">llvm::vfs::RedirectingFileSystemParser::lookupOrCreateEntry</a>.</p>

</div>
</div>

### getRealFileSystem() {#a9878c6a5a53d24e17c7c1002be31364c}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">IntrusiveRefCntPtr&lt; FileSystem &gt; llvm::vfs::getRealFileSystem ()</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Gets an <span class="doxyComputerOutput"><a href="/web-llvm/docs/api/classes/llvm/vfs/filesystem">vfs::FileSystem</a></span> for the 'real' file system, as seen by the operating system.</p>


<p>The working directory is linked to the process's working directory. (This is usually thread-hostile).</p>


<p>Declaration at line 373 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/support/virtualfilesystem-h">VirtualFileSystem.h</a>, definition at line 399 of file <a href="/web-llvm/docs/api/files/lib/lib/support/virtualfilesystem-cpp">VirtualFileSystem.cpp</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/structs/llvm/overlapstats/#a1cc444c0141edfa6f0c92e71fa3d3dda">llvm::OverlapStats::accumulateCounts</a>, <a href="/web-llvm/docs/api/classes/llvm/filecollectorbase/#a0a129db2a04ba5fb6e7e81926aa0c3fe">llvm::FileCollectorBase::addDirectory</a>, <a href="/web-llvm/docs/api/classes/anonymous-dataflowsanitizer-cpp-/dataflowsanitizer/#a991cf3988b07a606932e1d69f8f8507f">anonymous{DataFlowSanitizer.cpp}::DataFlowSanitizer::DataFlowSanitizer</a>, <a href="/web-llvm/docs/api/classes/llvm/codegendata/#af860defbaa2aa3a19cd8e5ef4edb5aed">llvm::CodeGenData::getInstance</a>, <a href="/web-llvm/docs/api/classes/llvm/memprofusepass/#a8cccd785edfbd932a0e26b62ac7d9592">llvm::MemProfUsePass::MemProfUsePass</a>, <a href="/web-llvm/docs/api/classes/llvm/mirprofileloaderpass/#a8d5394931a02fac4d0784e318196cf7c">llvm::MIRProfileLoaderPass::MIRProfileLoaderPass</a>, <a href="/web-llvm/docs/api/classes/llvm/pgoinstrumentationuse/#a016467155ff27477979a58b78577db80">llvm::PGOInstrumentationUse::PGOInstrumentationUse</a>, <a href="/web-llvm/docs/api/classes/llvm/sampleprofileloaderpass/#a324d3696b255beea7cfd1e8b901b2363">llvm::SampleProfileLoaderPass::run</a>, <a href="/web-llvm/docs/api/classes/llvm/sanitizerbinarymetadatapass/#a4c4b3aea1ab9cc4a61033672c29e3c69">llvm::SanitizerBinaryMetadataPass::run</a>, <a href="/web-llvm/docs/api/files/lib/lib/lto/ltobackend-cpp/#af5d1d807d38250523b2335cec221c2f1">runNewPMPasses</a> and <a href="/web-llvm/docs/api/classes/llvm/sanitizercoveragepass/#a4bda9a7c3b3d5d112826474bc35081e0">llvm::SanitizerCoveragePass::SanitizerCoveragePass</a>.</p>

</div>
</div>

### getUniqueID() {#a706e7f6e44dfa930a6e48122c581c009}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">sys::fs::UniqueID llvm::vfs::getUniqueID (<a href="/web-llvm/docs/api/classes/llvm/hash-code">hash_code</a> Hash)</td>
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



<p>Definition at line 814 of file <a href="/web-llvm/docs/api/files/lib/lib/support/virtualfilesystem-cpp">VirtualFileSystem.cpp</a>.</p>


<p>Referenced by <a href="#aadf74a30b19f30570211b95b9e379884">getDirectoryID</a> and <a href="#a6d887ec0b854b52f125578e7e3b5ac03">getFileID</a>.</p>

</div>
</div>

### getVFSFromYAML() {#a52ebaf7577ad1061d056fdfbfafb9ddf}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">std::unique_ptr&lt; FileSystem &gt; llvm::vfs::getVFSFromYAML (std::unique_ptr&lt; <a href="/web-llvm/docs/api/classes/llvm/memorybuffer">llvm::MemoryBuffer</a> &gt; Buffer, <a href="/web-llvm/docs/api/classes/llvm/sourcemgr/#acf78be89ec851a45f37a776a5a58bfe8">llvm::SourceMgr::DiagHandlerTy</a> DiagHandler, <a href="/web-llvm/docs/api/classes/llvm/stringref">StringRef</a> YAMLFilePath, void * DiagContext=nullptr, <a href="/web-llvm/docs/api/classes/llvm/intrusiverefcntptr">IntrusiveRefCntPtr</a>&lt; <a href="/web-llvm/docs/api/classes/llvm/vfs/filesystem">FileSystem</a> &gt; ExternalFS=<a href="#a9878c6a5a53d24e17c7c1002be31364c">getRealFileSystem</a>())</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Gets a <span class="doxyComputerOutput"><a href="/web-llvm/docs/api/classes/llvm/vfs/filesystem">FileSystem</a></span> for a virtual file system described in YAML format.</p>

<p>Definition at line 659 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/support/virtualfilesystem-h">VirtualFileSystem.h</a>.</p>


<p>Reference <a href="/web-llvm/docs/api/files/lib/lib/textapi/textstub-cpp/#aa9f07add63589fb3b28821d089f069a7">DiagHandler</a>.</p>

</div>
</div>

</div>

<hr/>

The documentation for this namespace was generated from the following files:

<ul>
<li><a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/support/virtualfilesystem-h">VirtualFileSystem.h</a></li>
<li><a href="/web-llvm/docs/api/files/lib/lib/support/virtualfilesystem-cpp">VirtualFileSystem.cpp</a></li>
</ul>

<hr/>

<p class="doxyGeneratedBy">Generated via <a href="https://github.com/xpack/doxygen2docusaurus">doxygen2docusaurus</a> by <a href="https://www.doxygen.nl">Doxygen</a> 1.15.0.</p>

</div>
