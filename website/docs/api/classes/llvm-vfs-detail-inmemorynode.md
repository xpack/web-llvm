---

# DO NOT EDIT!
# Automatically generated via doxygen2docusaurus by Doxygen.

slug: /api/classes/llvm/vfs/detail/inmemorynode
custom_edit_url: null
toc_max_heading_level: 4
keywords:
  - doxygen
  - reference
  - class

---

<div class="doxyPage">

# The `InMemoryNode` Class Reference

<p>The in memory file system is a tree of Nodes. <a href="#details">More...</a></p>

## Declaration

<div class="doxyDeclaration">
class llvm::vfs::detail::InMemoryNode { ... }
</div>

## Derived Classes

<table class="doxyMembersIndex">

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">class</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/vfs/detail/inmemorydirectory">InMemoryDirectory</a></td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/vfs/detail/inmemoryfile">InMemoryFile</a></td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/vfs/detail/anonymous-virtualfilesystem-cpp-/inmemoryhardlink">InMemoryHardLink</a></td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/vfs/detail/anonymous-virtualfilesystem-cpp-/inmemorysymboliclink">InMemorySymbolicLink</a></td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a76c71ae0c618a59d2e3f0b0099e1a525">InMemoryNode</a> (llvm::StringRef FileName, InMemoryNodeKind Kind)</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a5dcd1e94f7d7e237337d1b8fd84861e2">~InMemoryNode</a> ()=default</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/vfs/status">Status</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a8a5eea012d0e707ee3bce1d2730a2996">getStatus</a> (const Twine &amp;RequestedName) const =0</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Return the <span class="doxyComputerOutput"><a href="/web-llvm/docs/api/classes/llvm/vfs/status">Status</a></span> for this node. <a href="#a8a5eea012d0e707ee3bce1d2730a2996">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/stringref">StringRef</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a2fa8970e181e5ee3896a1a9c30b936de">getFileName</a> () const</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Get the filename of this node (the name without the directory part). <a href="#a2fa8970e181e5ee3896a1a9c30b936de">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/namespaces/llvm/vfs/detail/#aec9ebb37bafc86364affd2ffee6ae447">InMemoryNodeKind</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a59cf271a4e1096c53a5bfcaf44f95ba2">getKind</a> () const</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a857af836c0fe63feb612932f5bdd911a">toString</a> (unsigned Indent) const =0</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/namespaces/llvm/vfs/detail/#aec9ebb37bafc86364affd2ffee6ae447">InMemoryNodeKind</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a3000d348a4513c9644520b863bb00785">Kind</a></td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#acf879ab1616aca401e477b1ffd0f5e9c">FileName</a></td>
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

<p>The in memory file system is a tree of Nodes.</p>


<p>Every node can either be a file, symlink, hardlink or a directory.</p>


<p>Definition at line 640 of file <a href="/web-llvm/docs/api/files/lib/lib/support/virtualfilesystem-cpp">VirtualFileSystem.cpp</a>.</p>


<div class="doxySectionDef">

## Public Constructors

### InMemoryNode() {#a76c71ae0c618a59d2e3f0b0099e1a525}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">llvm::vfs::detail::InMemoryNode::InMemoryNode (<a href="/web-llvm/docs/api/classes/llvm/stringref">llvm::StringRef</a> FileName, <a href="/web-llvm/docs/api/namespaces/llvm/vfs/detail/#aec9ebb37bafc86364affd2ffee6ae447">InMemoryNodeKind</a> Kind)</td>
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



<p>Definition at line 645 of file <a href="/web-llvm/docs/api/files/lib/lib/support/virtualfilesystem-cpp">VirtualFileSystem.cpp</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/classes/llvm/vfs/detail/inmemorydirectory/#a57bba2c572adc06c3128994da1ec6936">llvm::vfs::detail::InMemoryDirectory::addChild</a>, <a href="/web-llvm/docs/api/classes/llvm/vfs/detail/anonymous-virtualfilesystem-cpp-/inmemoryhardlink/#aad125d3741d419bd479000e56998653c">llvm::vfs::detail::anonymous{VirtualFileSystem.cpp}::InMemoryHardLink::classof</a>, <a href="/web-llvm/docs/api/classes/llvm/vfs/detail/anonymous-virtualfilesystem-cpp-/inmemorysymboliclink/#a50f473dcc7e5def476076fe7fe5fb688">llvm::vfs::detail::anonymous{VirtualFileSystem.cpp}::InMemorySymbolicLink::classof</a>, <a href="/web-llvm/docs/api/classes/llvm/vfs/detail/inmemorydirectory/#a7437c0371863a9e1dc57c1ae51de51c4">llvm::vfs::detail::InMemoryDirectory::classof</a>, <a href="/web-llvm/docs/api/classes/llvm/vfs/detail/inmemoryfile/#aa8d36f36b3b68d5a51117802c5930169">llvm::vfs::detail::InMemoryFile::classof</a>, <a href="/web-llvm/docs/api/classes/llvm/vfs/detail/inmemorydirectory/#aa1939178f58de4931ecf4c35952fdfce">llvm::vfs::detail::InMemoryDirectory::getChild</a>, <a href="/web-llvm/docs/api/classes/llvm/vfs/detail/inmemorydirectory/#a344f873a748fb3ee5a781af697dba6b3">llvm::vfs::detail::InMemoryDirectory::InMemoryDirectory</a>, <a href="/web-llvm/docs/api/classes/llvm/vfs/detail/inmemoryfile/#a68bc45ba833afa528bcf4ad1d3893796">llvm::vfs::detail::InMemoryFile::InMemoryFile</a>, <a href="/web-llvm/docs/api/classes/llvm/vfs/detail/anonymous-virtualfilesystem-cpp-/inmemoryhardlink/#a52333122f3549c0314338986a41d34d9">llvm::vfs::detail::anonymous{VirtualFileSystem.cpp}::InMemoryHardLink::InMemoryHardLink</a> and <a href="/web-llvm/docs/api/classes/llvm/vfs/detail/anonymous-virtualfilesystem-cpp-/inmemorysymboliclink/#a422bb804824fee2915c93e4224b81c3e">llvm::vfs::detail::anonymous{VirtualFileSystem.cpp}::InMemorySymbolicLink::InMemorySymbolicLink</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Public Destructor

### \~InMemoryNode() {#a5dcd1e94f7d7e237337d1b8fd84861e2}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">virtual llvm::vfs::detail::InMemoryNode::~InMemoryNode ()</td>
</tr>
</table>
</td>
<td class="doxyMemberLabelsRight">
<span class="doxyMemberLabels">
<span class="doxyMemberLabel virtual">virtual</span>
<span class="doxyMemberLabel default">default</span>
</span>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 648 of file <a href="/web-llvm/docs/api/files/lib/lib/support/virtualfilesystem-cpp">VirtualFileSystem.cpp</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Public Member Functions

### getFileName() {#a2fa8970e181e5ee3896a1a9c30b936de}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">StringRef llvm::vfs::detail::InMemoryNode::getFileName ()</td>
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

<p>Get the filename of this node (the name without the directory part).</p>

<p>Definition at line 656 of file <a href="/web-llvm/docs/api/files/lib/lib/support/virtualfilesystem-cpp">VirtualFileSystem.cpp</a>.</p>

</div>
</div>

### getKind() {#a59cf271a4e1096c53a5bfcaf44f95ba2}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">InMemoryNodeKind llvm::vfs::detail::InMemoryNode::getKind ()</td>
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



<p>Definition at line 657 of file <a href="/web-llvm/docs/api/files/lib/lib/support/virtualfilesystem-cpp">VirtualFileSystem.cpp</a>.</p>

</div>
</div>

### getStatus() {#a8a5eea012d0e707ee3bce1d2730a2996}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">virtual Status llvm::vfs::detail::InMemoryNode::getStatus (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/twine">Twine</a> &amp; RequestedName)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Return the <span class="doxyComputerOutput"><a href="/web-llvm/docs/api/classes/llvm/vfs/status">Status</a></span> for this node.</p>


<p><span class="doxyComputerOutput">RequestedName</span> should be the name through which the caller referred to this node. It will override <span class="doxyComputerOutput">Status::Name</span> in the return value, to mimic the behavior of <span class="doxyComputerOutput">RealFile</span>.</p>


<p>Definition at line 653 of file <a href="/web-llvm/docs/api/files/lib/lib/support/virtualfilesystem-cpp">VirtualFileSystem.cpp</a>.</p>

</div>
</div>

### toString() {#a857af836c0fe63feb612932f5bdd911a}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">virtual std::string llvm::vfs::detail::InMemoryNode::toString (unsigned Indent)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 658 of file <a href="/web-llvm/docs/api/files/lib/lib/support/virtualfilesystem-cpp">VirtualFileSystem.cpp</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Private Member Attributes

### FileName {#acf879ab1616aca401e477b1ffd0f5e9c}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">std::string llvm::vfs::detail::InMemoryNode::FileName</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 642 of file <a href="/web-llvm/docs/api/files/lib/lib/support/virtualfilesystem-cpp">VirtualFileSystem.cpp</a>.</p>

</div>
</div>

### Kind {#a3000d348a4513c9644520b863bb00785}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">InMemoryNodeKind llvm::vfs::detail::InMemoryNode::Kind</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 641 of file <a href="/web-llvm/docs/api/files/lib/lib/support/virtualfilesystem-cpp">VirtualFileSystem.cpp</a>.</p>

</div>
</div>

</div>

<hr/>

The documentation for this class was generated from the following file:

<ul>
<li><a href="/web-llvm/docs/api/files/lib/lib/support/virtualfilesystem-cpp">VirtualFileSystem.cpp</a></li>
</ul>

<hr/>

<p class="doxyGeneratedBy">Generated via <a href="https://github.com/xpack/doxygen2docusaurus">doxygen2docusaurus</a> by <a href="https://www.doxygen.nl">Doxygen</a> 1.15.0.</p>

</div>
