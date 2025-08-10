---

# DO NOT EDIT!
# Automatically generated via doxygen2docusaurus by Doxygen.

slug: /api/classes/llvm/vfs/redirectingfilesystem/directoryentry
custom_edit_url: null
toc_max_heading_level: 4
keywords:
  - doxygen
  - reference
  - class

---

<div class="doxyPage">

# `DirectoryEntry` Class

<p>A directory in the vfs with explicitly specified contents. <a href="#details">More...</a></p>

## Declaration

<div class="doxyDeclaration">
class llvm::vfs::RedirectingFileSystem::DirectoryEntry { ... }
</div>

## Included Headers

<div class="doxyIncludesList">#include "<a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/support/virtualfilesystem-h">llvm/Support/VirtualFileSystem.h</a>"
</div>

## Base class

<table class="doxyMembersIndex">

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">class</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/vfs/redirectingfilesystem/entry">Entry</a></td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>A single file or directory in the VFS. <a href="/web-llvm/docs/api/classes/llvm/vfs/redirectingfilesystem/entry/#details">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

</table>

## Public Member Typedefs Index

<table class="doxyMembersIndex">

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">using</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a990617ce1528156dde294436f7ecbd47">iterator</a> = decltype(Contents)::iterator</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a87e305705d19a7a1321db8581f6593bc">DirectoryEntry</a> (StringRef Name, std::vector&lt; std::unique_ptr&lt; Entry &gt; &gt; Contents, Status S)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Constructs a directory entry with explicitly specified contents. <a href="#a87e305705d19a7a1321db8581f6593bc">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a792ec5cfed4259776ab3129fcccb1cb5">DirectoryEntry</a> (StringRef Name, Status S)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Constructs an empty directory entry. <a href="#a792ec5cfed4259776ab3129fcccb1cb5">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

</table>

## Public Member Functions Index

<table class="doxyMembersIndex">

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/vfs/status">Status</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a1a5096a6c44bd08aea8f23190c582bee">getStatus</a> ()</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">void</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ab51184c16823ce088238f26d7f7cdab8">addContent</a> (std::unique_ptr&lt; Entry &gt; Content)</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/vfs/redirectingfilesystem/entry">Entry</a> *</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#adb48303ccda000179a55f1bfde182369">getLastContent</a> () const</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="#a990617ce1528156dde294436f7ecbd47">iterator</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a0996b6a5a38c9cb68fad58d5caafab4e">contents_begin</a> ()</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="#a990617ce1528156dde294436f7ecbd47">iterator</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a702e0d33d0b00b4c39106d612a5395d8">contents_end</a> ()</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">std::vector&lt; std::unique_ptr&lt; <a href="/web-llvm/docs/api/classes/llvm/vfs/redirectingfilesystem/entry">Entry</a> &gt; &gt;</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#afa6fbc4f3cb7fdd798cfbc1bc0fa6168">Contents</a></td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/vfs/status">Status</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a043d1d516385ab4881067dfd866296b0">S</a></td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">static bool</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a42a9149f1c6741e80329ba86214930e2">classof</a> (const Entry *E)</td>
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

<p>A directory in the vfs with explicitly specified contents.</p>

<p>Definition at line 821 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/support/virtualfilesystem-h">VirtualFileSystem.h</a>.</p>


<div class="doxySectionDef">

## Public Member Typedefs

### iterator {#a990617ce1528156dde294436f7ecbd47}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">using llvm::vfs::RedirectingFileSystem::DirectoryEntry::iterator =  decltype(Contents)::iterator</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 844 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/support/virtualfilesystem-h">VirtualFileSystem.h</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Public Constructors

### DirectoryEntry() {#a87e305705d19a7a1321db8581f6593bc}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">llvm::vfs::RedirectingFileSystem::DirectoryEntry::DirectoryEntry (<a href="/web-llvm/docs/api/classes/llvm/stringref">StringRef</a> Name, std::vector&lt; std::unique_ptr&lt; <a href="/web-llvm/docs/api/classes/llvm/vfs/redirectingfilesystem/entry">Entry</a> &gt; &gt; Contents, <a href="/web-llvm/docs/api/classes/llvm/vfs/status">Status</a> S)</td>
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

<p>Constructs a directory entry with explicitly specified contents.</p>

<p>Definition at line 827 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/support/virtualfilesystem-h">VirtualFileSystem.h</a>.</p>


<p>References <a href="/web-llvm/docs/api/classes/llvm/vfs/redirectingfilesystem/#a9507b40bcb88580411b40aaf59c105aea53dd0141cf4c202d8b1167608b16368e">llvm::vfs::RedirectingFileSystem::EK_Directory</a>, <a href="/web-llvm/docs/api/classes/llvm/vfs/redirectingfilesystem/entry/#adc99721caac098b0991c99848e25375c">llvm::vfs::RedirectingFileSystem::Entry::Entry</a> and <a href="/web-llvm/docs/api/namespaces/llvm/#abfc9c7ecf70f66901e439f7c04ef3dbb">llvm::move</a>.</p>

</div>
</div>

### DirectoryEntry() {#a792ec5cfed4259776ab3129fcccb1cb5}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">llvm::vfs::RedirectingFileSystem::DirectoryEntry::DirectoryEntry (<a href="/web-llvm/docs/api/classes/llvm/stringref">StringRef</a> Name, <a href="/web-llvm/docs/api/classes/llvm/vfs/status">Status</a> S)</td>
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

<p>Constructs an empty directory entry.</p>

<p>Definition at line 833 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/support/virtualfilesystem-h">VirtualFileSystem.h</a>.</p>


<p>References <a href="/web-llvm/docs/api/classes/llvm/vfs/redirectingfilesystem/#a9507b40bcb88580411b40aaf59c105aea53dd0141cf4c202d8b1167608b16368e">llvm::vfs::RedirectingFileSystem::EK_Directory</a>, <a href="/web-llvm/docs/api/classes/llvm/vfs/redirectingfilesystem/entry/#adc99721caac098b0991c99848e25375c">llvm::vfs::RedirectingFileSystem::Entry::Entry</a> and <a href="/web-llvm/docs/api/namespaces/llvm/#abfc9c7ecf70f66901e439f7c04ef3dbb">llvm::move</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Public Member Functions

### addContent() {#ab51184c16823ce088238f26d7f7cdab8}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void llvm::vfs::RedirectingFileSystem::DirectoryEntry::addContent (std::unique_ptr&lt; <a href="/web-llvm/docs/api/classes/llvm/vfs/redirectingfilesystem/entry">Entry</a> &gt; Content)</td>
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



<p>Definition at line 838 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/support/virtualfilesystem-h">VirtualFileSystem.h</a>.</p>

</div>
</div>

### contents\_begin() {#a0996b6a5a38c9cb68fad58d5caafab4e}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">iterator llvm::vfs::RedirectingFileSystem::DirectoryEntry::contents_begin ()</td>
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



<p>Definition at line 846 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/support/virtualfilesystem-h">VirtualFileSystem.h</a>.</p>

</div>
</div>

### contents\_end() {#a702e0d33d0b00b4c39106d612a5395d8}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">iterator llvm::vfs::RedirectingFileSystem::DirectoryEntry::contents_end ()</td>
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



<p>Definition at line 847 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/support/virtualfilesystem-h">VirtualFileSystem.h</a>.</p>

</div>
</div>

### getLastContent() {#adb48303ccda000179a55f1bfde182369}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">Entry * llvm::vfs::RedirectingFileSystem::DirectoryEntry::getLastContent ()</td>
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



<p>Definition at line 842 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/support/virtualfilesystem-h">VirtualFileSystem.h</a>.</p>


<p>Reference <a href="/web-llvm/docs/api/classes/llvm/vfs/redirectingfilesystem/entry/#adc99721caac098b0991c99848e25375c">llvm::vfs::RedirectingFileSystem::Entry::Entry</a>.</p>

</div>
</div>

### getStatus() {#a1a5096a6c44bd08aea8f23190c582bee}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">Status llvm::vfs::RedirectingFileSystem::DirectoryEntry::getStatus ()</td>
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



<p>Definition at line 836 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/support/virtualfilesystem-h">VirtualFileSystem.h</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Private Member Attributes

### Contents {#afa6fbc4f3cb7fdd798cfbc1bc0fa6168}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">std::vector&lt;std::unique_ptr&lt;Entry&gt; &gt; llvm::vfs::RedirectingFileSystem::DirectoryEntry::Contents</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 822 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/support/virtualfilesystem-h">VirtualFileSystem.h</a>.</p>

</div>
</div>

### S {#a043d1d516385ab4881067dfd866296b0}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">Status llvm::vfs::RedirectingFileSystem::DirectoryEntry::S</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 823 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/support/virtualfilesystem-h">VirtualFileSystem.h</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Public Static Functions

### classof() {#a42a9149f1c6741e80329ba86214930e2}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool llvm::vfs::RedirectingFileSystem::DirectoryEntry::classof (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/vfs/redirectingfilesystem/entry">Entry</a> * E)</td>
</tr>
</table>
</td>
<td class="doxyMemberLabelsRight">
<span class="doxyMemberLabels">
<span class="doxyMemberLabel inline">inline</span>
<span class="doxyMemberLabel static">static</span>
</span>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 849 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/support/virtualfilesystem-h">VirtualFileSystem.h</a>.</p>


<p>References <a href="/web-llvm/docs/api/files/lib/lib/ir/builtingcs-cpp/#abb2b3a60ccc38a28239e19a1646e0c8a">E</a>, <a href="/web-llvm/docs/api/classes/llvm/vfs/redirectingfilesystem/#a9507b40bcb88580411b40aaf59c105aea53dd0141cf4c202d8b1167608b16368e">llvm::vfs::RedirectingFileSystem::EK_Directory</a> and <a href="/web-llvm/docs/api/classes/llvm/vfs/redirectingfilesystem/entry/#adc99721caac098b0991c99848e25375c">llvm::vfs::RedirectingFileSystem::Entry::Entry</a>.</p>

</div>
</div>

</div>

<hr/>

The documentation for this class was generated from the following file:

<ul>
<li><a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/support/virtualfilesystem-h">VirtualFileSystem.h</a></li>
</ul>

<hr/>

<p class="doxyGeneratedBy">Generated via <a href="https://xpack.github.io/doxygen2docusaurus">doxygen2docusaurus</a> 2.0.0 by <a href="https://www.doxygen.nl">Doxygen</a> 1.15.0.</p>

</div>
