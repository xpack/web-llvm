---

# DO NOT EDIT!
# Automatically generated via doxygen2docusaurus by Doxygen.

slug: /api/classes/llvm/filepermissionsapplier
custom_edit_url: null
toc_max_heading_level: 4
keywords:
  - doxygen
  - reference
  - class

---

<div class="doxyPage">

# The `FilePermissionsApplier` Class Reference

<p>FilePermssionsApplier helps to copy permissions from an input file to an output one. <a href="#details">More...</a></p>

## Declaration

<div class="doxyDeclaration">
class llvm::FilePermissionsApplier { ... }
</div>

## Included Headers

<div class="doxyIncludesList">#include "<a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/support/fileutilities-h">llvm/Support/FileUtilities.h</a>"
</div>

## Private Constructors Index

<table class="doxyMembersIndex">

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ab50293a69a6bfa922fd8de6d5ceb55be">FilePermissionsApplier</a> (StringRef InputFilename, sys::fs::file_status Status)</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/error">Error</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a958cd3b9790b98d062b8e5fb5ebc32e6">apply</a> (StringRef OutputFilename, bool CopyDates=false, std::optional&lt; sys::fs::perms &gt; OverwritePermissions=std::nullopt)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Apply stored permissions to the <span class="doxyComputerOutput">OutputFilename</span>. <a href="#a958cd3b9790b98d062b8e5fb5ebc32e6">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

</table>

## Private Member Attributes Index

<table class="doxyMembersIndex">

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/stringref">StringRef</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a77ce51c73facf197108a7005d74fd9ac">InputFilename</a></td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/sys/fs/file-status">sys::fs::file_status</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#aa41085bc1305abf4a9afe92293e0ba75">InputStatus</a></td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">static <a href="/web-llvm/docs/api/classes/llvm/expected">Expected</a>&lt; <a href="/web-llvm/docs/api/classes/llvm/filepermissionsapplier">FilePermissionsApplier</a> &gt;</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#af70a75dd83c51400048e0ad5107b8773">create</a> (StringRef InputFilename)</td>
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

<p>FilePermssionsApplier helps to copy permissions from an input file to an output one.</p>


<p>It memorizes the status of the input file and can apply permissions and dates to the output file.</p>


<p>Definition at line 82 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/support/fileutilities-h">FileUtilities.h</a>.</p>


<div class="doxySectionDef">

## Private Constructors

### FilePermissionsApplier() {#ab50293a69a6bfa922fd8de6d5ceb55be}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">llvm::FilePermissionsApplier::FilePermissionsApplier (<a href="/web-llvm/docs/api/classes/llvm/stringref">StringRef</a> InputFilename, <a href="/web-llvm/docs/api/classes/llvm/sys/fs/file-status">sys::fs::file_status</a> Status)</td>
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



<p>Definition at line 94 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/support/fileutilities-h">FileUtilities.h</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Public Member Functions

### apply() {#a958cd3b9790b98d062b8e5fb5ebc32e6}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">Error FilePermissionsApplier::apply (<a href="/web-llvm/docs/api/classes/llvm/stringref">StringRef</a> OutputFilename, bool CopyDates=false, std::optional&lt; <a href="/web-llvm/docs/api/namespaces/llvm/sys/fs/#ac56b6ec1078927bdd9b65f7ba8fbda82">sys::fs::perms</a> &gt; OverwritePermissions=std::nullopt)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Apply stored permissions to the <span class="doxyComputerOutput">OutputFilename</span>.</p>


<p>Copy LastAccess and ModificationTime if <span class="doxyComputerOutput">CopyDates</span> is true. Overwrite stored permissions if <span class="doxyComputerOutput">OverwritePermissions</span> is specified.</p>


<p>Declaration at line 90 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/support/fileutilities-h">FileUtilities.h</a>, definition at line 284 of file <a href="/web-llvm/docs/api/files/lib/lib/support/fileutilities-cpp">FileUtilities.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/namespaces/llvm/sys/fs/#a93918b3a9b70253cd229fc5864884f58a028d2e48ae4e6c34d4a5bbb70438a936">llvm::sys::fs::CD_OpenExisting</a>, <a href="/web-llvm/docs/api/namespaces/llvm/sys/fs/#a700307b3778f46a8485f4f662584e719">llvm::sys::fs::changeFileOwnership</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a0f4ffaa2f15fc8f612a233e3b45510c0">llvm::createFileError</a>, <a href="/web-llvm/docs/api/namespaces/llvm/sys/fs/#ada473c08fad5cfd4efb132d2821f4a9b">llvm::sys::fs::getUmask</a>, <a href="/web-llvm/docs/api/classes/llvm/sys/fs/basic-file-status/#ac57bcfa556142ba8d55024a174ab79ff">llvm::sys::fs::basic_file_status::getUser</a>, <a href="/web-llvm/docs/api/namespaces/llvm/sys/fs/#aaa20e3a6a1473b383695503e0b5eb871">llvm::sys::fs::openFileForWrite</a>, <a href="/web-llvm/docs/api/files/lib/lib/tablegen/main-cpp/#a896200b9a8add6ca7edf3034cb031fea">OutputFilename</a>, <a href="/web-llvm/docs/api/namespaces/llvm/sys/fs/#a6c50be965db24d7532b6b4e6b0755f5ca4676601564b208338edf7317182f473e">llvm::sys::fs::regular_file</a>, <a href="/web-llvm/docs/api/classes/llvm/sys/process/#a0777b5060c78b24c4765fffbac259f93">llvm::sys::Process::SafelyCloseFileDescriptor</a>, <a href="/web-llvm/docs/api/namespaces/llvm/sys/fs/#a35f16bd8439efd3c629fdc6e7b6cb039">llvm::sys::fs::setLastAccessAndModificationTime</a>, <a href="/web-llvm/docs/api/namespaces/llvm/sys/fs/#aed67578bdddc4f087b10f1bc9cbaab88">llvm::sys::fs::setPermissions</a>, <a href="/web-llvm/docs/api/namespaces/llvm/sys/fs/#a5f126cc7b64d31cd709215b48656d83d">llvm::sys::fs::status</a>, <a href="/web-llvm/docs/api/classes/llvm/error/#a4dfd0813c3d0e0a30439b5a3e9196b59">llvm::Error::success</a> and <a href="/web-llvm/docs/api/classes/llvm/sys/fs/basic-file-status/#ab01b92f53a9f931c5859498219da2613">llvm::sys::fs::basic_file_status::type</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Private Member Attributes

### InputFilename {#a77ce51c73facf197108a7005d74fd9ac}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">StringRef llvm::FilePermissionsApplier::InputFilename</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 97 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/support/fileutilities-h">FileUtilities.h</a>.</p>

</div>
</div>

### InputStatus {#aa41085bc1305abf4a9afe92293e0ba75}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">sys::fs::file_status llvm::FilePermissionsApplier::InputStatus</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 98 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/support/fileutilities-h">FileUtilities.h</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Public Static Functions

### create() {#af70a75dd83c51400048e0ad5107b8773}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">Expected&lt; FilePermissionsApplier &gt; FilePermissionsApplier::create (<a href="/web-llvm/docs/api/classes/llvm/stringref">StringRef</a> InputFilename)</td>
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



<p>Declaration at line 84 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/support/fileutilities-h">FileUtilities.h</a>, definition at line 271 of file <a href="/web-llvm/docs/api/files/lib/lib/support/fileutilities-cpp">FileUtilities.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/namespaces/llvm/#a0f4ffaa2f15fc8f612a233e3b45510c0">llvm::createFileError</a> and <a href="/web-llvm/docs/api/namespaces/llvm/sys/fs/#a5f126cc7b64d31cd709215b48656d83d">llvm::sys::fs::status</a>.</p>

</div>
</div>

</div>

<hr/>

The documentation for this class was generated from the following files:

<ul>
<li><a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/support/fileutilities-h">FileUtilities.h</a></li>
<li><a href="/web-llvm/docs/api/files/lib/lib/support/fileutilities-cpp">FileUtilities.cpp</a></li>
</ul>

<hr/>

<p class="doxyGeneratedBy">Generated via <a href="https://github.com/xpack/doxygen2docusaurus">doxygen2docusaurus</a> by <a href="https://www.doxygen.nl">Doxygen</a> 1.15.0.</p>

</div>
