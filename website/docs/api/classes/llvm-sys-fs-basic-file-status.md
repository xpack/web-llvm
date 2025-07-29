---

# DO NOT EDIT!
# Automatically generated via doxygen2docusaurus by Doxygen.

slug: /api/classes/llvm/sys/fs/basic-file-status
custom_edit_url: null
toc_max_heading_level: 4
keywords:
  - doxygen
  - reference
  - class

---

<div class="doxyPage">

# `basic_file_status` Class

<p>Represents the result of a call to directory_iterator::status(). <a href="#details">More...</a></p>

## Declaration

<div class="doxyDeclaration">
class llvm::sys::fs::basic_file_status { ... }
</div>

## Included Headers

<div class="doxyIncludesList">#include "<a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/support/filesystem-h">llvm/Support/FileSystem.h</a>"
</div>

## Derived Classes

<table class="doxyMembersIndex">

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">class</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/sys/fs/file-status">file_status</a></td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Represents the result of a call to <a href="/web-llvm/docs/api/namespaces/llvm/sys/fs/#a5f126cc7b64d31cd709215b48656d83d">sys::fs::status()</a>. <a href="/web-llvm/docs/api/classes/llvm/sys/fs/file-status/#details">More...</a></p>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a2255c425a39d9ec9788aa1f77d5badce">basic_file_status</a> ()=default</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ae7e88b89cf58ea85ecc6acdc824ab4d8">basic_file_status</a> (file_type Type)</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a16d8e6cdd1ccb3a201eb8b85dcb56797">basic_file_status</a> (file_type Type, perms Perms, time_t ATime, uint32_t ATimeNSec, time_t MTime, uint32_t MTimeNSec, uid_t UID, gid_t GID, off_t Size)</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/namespaces/llvm/sys/fs/#a6c50be965db24d7532b6b4e6b0755f5c">file_type</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ab01b92f53a9f931c5859498219da2613">type</a> () const</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/namespaces/llvm/sys/fs/#ac56b6ec1078927bdd9b65f7ba8fbda82">perms</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a910720fdb892e47f864eb03fc7bebc3a">permissions</a> () const</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/namespaces/llvm/sys/#a52f2c3fdd7f80c1991d8c7079489efff">TimePoint</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ab258586eab700df6cf494d52dc282e91">getLastAccessedTime</a> () const</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>The file access time as reported from the underlying file system. <a href="#ab258586eab700df6cf494d52dc282e91">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/namespaces/llvm/sys/#a52f2c3fdd7f80c1991d8c7079489efff">TimePoint</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ae807b50b0b414d8a9195cdc0ee23b86a">getLastModificationTime</a> () const</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>The file modification time as reported from the underlying file system. <a href="#ae807b50b0b414d8a9195cdc0ee23b86a">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">uint32_t</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ac57bcfa556142ba8d55024a174ab79ff">getUser</a> () const</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a823d8ed4ec65cbd4535f21ee548e839f">getGroup</a> () const</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">uint64_t</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a46987fdc0db0174f80aea26291fde5d8">getSize</a> () const</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a382d1df8c510fbaec45f5fccdfcb5c4b">type</a> (file_type v)</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a18b2c1b3b9e5df3762d922a99bd0781a">permissions</a> (perms p)</td>
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

## Protected Member Attributes Index

<table class="doxyMembersIndex">

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">time_t</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a41147a2ba5ca97edfafe0c046514e625">fs_st_atime</a> = 0</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ade32b78fd380f83f8450c49280cb1f70">fs_st_mtime</a> = 0</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a51cff82c846cf0d2c88333efe377d335">fs_st_atime_nsec</a> = 0</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a19a9f914503e759f6321b7cb06deb67b">fs_st_mtime_nsec</a> = 0</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">uid_t</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a10f19674f74e144b01b07f45e8795a45">fs_st_uid</a> = 0</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">gid_t</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#aa8273d2dd62e2fa406a0cfb0dbd009d1">fs_st_gid</a> = 0</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">off_t</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a03bab17d92e5629864b798aa0d3a37a4">fs_st_size</a> = 0</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/namespaces/llvm/sys/fs/#a6c50be965db24d7532b6b4e6b0755f5c">file_type</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#afef5c100e6543383a11df67699cc5ced">Type</a> = <a href="/web-llvm/docs/api/namespaces/llvm/sys/fs/#a6c50be965db24d7532b6b4e6b0755f5ca39fe2d3c413eb8d3f1d2f3b199fd29de">file_type::status_error</a></td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/namespaces/llvm/sys/fs/#ac56b6ec1078927bdd9b65f7ba8fbda82">perms</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a237aed551cb5292a2606caa4232234b5">Perms</a> = <a href="/web-llvm/docs/api/namespaces/llvm/sys/fs/#ac56b6ec1078927bdd9b65f7ba8fbda82ab52f98686d024f7db0196d6c3f1e791d">perms_not_known</a></td>
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

<p>Represents the result of a call to directory_iterator::status().</p>


<p>This is a subset of the information returned by a regular <a href="/web-llvm/docs/api/namespaces/llvm/sys/fs/#a5f126cc7b64d31cd709215b48656d83d">sys::fs::status()</a> call, and represents the information provided by Windows FileFirstFile/FindNextFile.</p>


<p>Definition at line 132 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/support/filesystem-h">FileSystem.h</a>.</p>


<div class="doxySectionDef">

## Public Constructors

### basic\_file\_status() {#a2255c425a39d9ec9788aa1f77d5badce}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">llvm::sys::fs::basic_file_status::basic_file_status ()</td>
</tr>
</table>
</td>
<td class="doxyMemberLabelsRight">
<span class="doxyMemberLabels">
<span class="doxyMemberLabel default">default</span>
</span>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 154 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/support/filesystem-h">FileSystem.h</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/classes/llvm/sys/fs/file-status/#ab20647acd1a246cf271bb08287820aa4">llvm::sys::fs::file_status::file_status</a> and <a href="/web-llvm/docs/api/classes/llvm/sys/fs/file-status/#a726f996c27ab1ab4baf0297160fd000d">llvm::sys::fs::file_status::file_status</a>.</p>

</div>
</div>

### basic\_file\_status() {#ae7e88b89cf58ea85ecc6acdc824ab4d8}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">llvm::sys::fs::basic_file_status::basic_file_status (<a href="/web-llvm/docs/api/namespaces/llvm/sys/fs/#a6c50be965db24d7532b6b4e6b0755f5c">file_type</a> Type)</td>
</tr>
</table>
</td>
<td class="doxyMemberLabelsRight">
<span class="doxyMemberLabels">
<span class="doxyMemberLabel inline">inline</span>
<span class="doxyMemberLabel explicit">explicit</span>
</span>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 156 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/support/filesystem-h">FileSystem.h</a>.</p>


<p>Reference <a href="#afef5c100e6543383a11df67699cc5ced">Type</a>.</p>

</div>
</div>

### basic\_file\_status() {#a16d8e6cdd1ccb3a201eb8b85dcb56797}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">llvm::sys::fs::basic_file_status::basic_file_status (<a href="/web-llvm/docs/api/namespaces/llvm/sys/fs/#a6c50be965db24d7532b6b4e6b0755f5c">file_type</a> Type, <a href="/web-llvm/docs/api/namespaces/llvm/sys/fs/#ac56b6ec1078927bdd9b65f7ba8fbda82">perms</a> Perms, time_t ATime, uint32_t ATimeNSec, time_t MTime, uint32_t MTimeNSec, uid_t UID, gid_t GID, off_t Size)</td>
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



<p>Definition at line 159 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/support/filesystem-h">FileSystem.h</a>.</p>


<p>References <a href="#a41147a2ba5ca97edfafe0c046514e625">fs_st_atime</a>, <a href="#a51cff82c846cf0d2c88333efe377d335">fs_st_atime_nsec</a>, <a href="#aa8273d2dd62e2fa406a0cfb0dbd009d1">fs_st_gid</a>, <a href="#ade32b78fd380f83f8450c49280cb1f70">fs_st_mtime</a>, <a href="#a19a9f914503e759f6321b7cb06deb67b">fs_st_mtime_nsec</a>, <a href="#a03bab17d92e5629864b798aa0d3a37a4">fs_st_size</a>, <a href="#a10f19674f74e144b01b07f45e8795a45">fs_st_uid</a>, <a href="#a237aed551cb5292a2606caa4232234b5">Perms</a>, <a href="/web-llvm/docs/api/files/lib/lib/analysis/inlineorder-cpp/#a7ee6f0cb51c3b9056199e9a0001fe8c3a6f6cb72d544962fa333e2e34ce64f719">Size</a> and <a href="#afef5c100e6543383a11df67699cc5ced">Type</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Public Member Functions

### getGroup() {#a823d8ed4ec65cbd4535f21ee548e839f}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">uint32_t llvm::sys::fs::basic_file_status::getGroup ()</td>
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



<p>Definition at line 199 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/support/filesystem-h">FileSystem.h</a>.</p>


<p>Reference <a href="#aa8273d2dd62e2fa406a0cfb0dbd009d1">fs_st_gid</a>.</p>

</div>
</div>

### getLastAccessedTime() {#ab258586eab700df6cf494d52dc282e91}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">TimePoint llvm::sys::fs::basic_file_status::getLastAccessedTime ()</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>The file access time as reported from the underlying file system.</p>


<p>Also see comments on <span class="doxyComputerOutput"><a href="#ae807b50b0b414d8a9195cdc0ee23b86a">getLastModificationTime()</a></span> related to the precision of the returned value.</p>


<p>Definition at line 186 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/support/filesystem-h">FileSystem.h</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/files/lib/lib/support/filecollector-cpp/#a1f7c3aa9196e89483c3ad89f2718dec3">copyAccessAndModificationTime</a>.</p>

</div>
</div>

### getLastModificationTime() {#ae807b50b0b414d8a9195cdc0ee23b86a}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">TimePoint llvm::sys::fs::basic_file_status::getLastModificationTime ()</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>The file modification time as reported from the underlying file system.</p>


<p>The returned value allows for nanosecond precision but the actual resolution is an implementation detail of the underlying file system. There is no guarantee for what kind of resolution you can expect, the resolution can differ across platforms and even across mountpoints on the same machine.</p>


<p>Definition at line 195 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/support/filesystem-h">FileSystem.h</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/files/lib/lib/support/filecollector-cpp/#a1f7c3aa9196e89483c3ad89f2718dec3">copyAccessAndModificationTime</a> and <a href="/web-llvm/docs/api/namespaces/llvm/#aabba6d27907082520ad2eb977c8e406b">llvm::pruneCache</a>.</p>

</div>
</div>

### getSize() {#a46987fdc0db0174f80aea26291fde5d8}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">uint64_t llvm::sys::fs::basic_file_status::getSize ()</td>
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



<p>Definition at line 200 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/support/filesystem-h">FileSystem.h</a>.</p>


<p>Reference <a href="#a03bab17d92e5629864b798aa0d3a37a4">fs_st_size</a>.</p>

</div>
</div>

### getUser() {#ac57bcfa556142ba8d55024a174ab79ff}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">uint32_t llvm::sys::fs::basic_file_status::getUser ()</td>
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



<p>Definition at line 198 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/support/filesystem-h">FileSystem.h</a>.</p>


<p>Reference <a href="#a10f19674f74e144b01b07f45e8795a45">fs_st_uid</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/classes/llvm/filepermissionsapplier/#a958cd3b9790b98d062b8e5fb5ebc32e6">llvm::FilePermissionsApplier::apply</a>.</p>

</div>
</div>

### permissions() {#a910720fdb892e47f864eb03fc7bebc3a}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">perms llvm::sys::fs::basic_file_status::permissions ()</td>
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



<p>Definition at line 180 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/support/filesystem-h">FileSystem.h</a>.</p>


<p>Reference <a href="#a237aed551cb5292a2606caa4232234b5">Perms</a>.</p>

</div>
</div>

### permissions() {#a18b2c1b3b9e5df3762d922a99bd0781a}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void llvm::sys::fs::basic_file_status::permissions (<a href="/web-llvm/docs/api/namespaces/llvm/sys/fs/#ac56b6ec1078927bdd9b65f7ba8fbda82">perms</a> p)</td>
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



<p>Definition at line 217 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/support/filesystem-h">FileSystem.h</a>.</p>


<p>Reference <a href="#a237aed551cb5292a2606caa4232234b5">Perms</a>.</p>

</div>
</div>

### type() {#ab01b92f53a9f931c5859498219da2613}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">file_type llvm::sys::fs::basic_file_status::type ()</td>
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



<p>Definition at line 179 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/support/filesystem-h">FileSystem.h</a>.</p>


<p>Reference <a href="#afef5c100e6543383a11df67699cc5ced">Type</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/classes/llvm/filepermissionsapplier/#a958cd3b9790b98d062b8e5fb5ebc32e6">llvm::FilePermissionsApplier::apply</a>, <a href="/web-llvm/docs/api/classes/llvm/filecollector/#a71730785a9649e84e7680eaf77d0095c">llvm::FileCollector::copyFiles</a>, <a href="/web-llvm/docs/api/classes/llvm/fileoutputbuffer/#a3a10ce8cad8fee5d6a4c55270866aa05">llvm::FileOutputBuffer::create</a>, <a href="/web-llvm/docs/api/namespaces/llvm/sys/fs/#ab6b1bd66ad75f18d0cd7c00900142900">llvm::sys::fs::get_file_type</a> and <a href="/web-llvm/docs/api/namespaces/llvm/sys/fs/#ab045f8d8e569caf1cedd6c3dadd1b2ee">llvm::sys::fs::status_known</a>.</p>

</div>
</div>

### type() {#a382d1df8c510fbaec45f5fccdfcb5c4b}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void llvm::sys::fs::basic_file_status::type (<a href="/web-llvm/docs/api/namespaces/llvm/sys/fs/#a6c50be965db24d7532b6b4e6b0755f5c">file_type</a> v)</td>
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



<p>Definition at line 216 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/support/filesystem-h">FileSystem.h</a>.</p>


<p>Reference <a href="#afef5c100e6543383a11df67699cc5ced">Type</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Protected Member Attributes

### fs\_st\_atime {#a41147a2ba5ca97edfafe0c046514e625}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">time_t llvm::sys::fs::basic_file_status::fs_st_atime = 0</td>
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



<p>Definition at line 135 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/support/filesystem-h">FileSystem.h</a>.</p>


<p>Referenced by <a href="#a16d8e6cdd1ccb3a201eb8b85dcb56797">basic_file_status</a>.</p>

</div>
</div>

### fs\_st\_atime\_nsec {#a51cff82c846cf0d2c88333efe377d335}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">uint32_t llvm::sys::fs::basic_file_status::fs_st_atime_nsec = 0</td>
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



<p>Definition at line 137 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/support/filesystem-h">FileSystem.h</a>.</p>


<p>Referenced by <a href="#a16d8e6cdd1ccb3a201eb8b85dcb56797">basic_file_status</a>.</p>

</div>
</div>

### fs\_st\_gid {#aa8273d2dd62e2fa406a0cfb0dbd009d1}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">gid_t llvm::sys::fs::basic_file_status::fs_st_gid = 0</td>
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



<p>Definition at line 140 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/support/filesystem-h">FileSystem.h</a>.</p>


<p>Referenced by <a href="#a16d8e6cdd1ccb3a201eb8b85dcb56797">basic_file_status</a> and <a href="#a823d8ed4ec65cbd4535f21ee548e839f">getGroup</a>.</p>

</div>
</div>

### fs\_st\_mtime {#ade32b78fd380f83f8450c49280cb1f70}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">time_t llvm::sys::fs::basic_file_status::fs_st_mtime = 0</td>
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



<p>Definition at line 136 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/support/filesystem-h">FileSystem.h</a>.</p>


<p>Referenced by <a href="#a16d8e6cdd1ccb3a201eb8b85dcb56797">basic_file_status</a>.</p>

</div>
</div>

### fs\_st\_mtime\_nsec {#a19a9f914503e759f6321b7cb06deb67b}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">uint32_t llvm::sys::fs::basic_file_status::fs_st_mtime_nsec = 0</td>
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



<p>Definition at line 138 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/support/filesystem-h">FileSystem.h</a>.</p>


<p>Referenced by <a href="#a16d8e6cdd1ccb3a201eb8b85dcb56797">basic_file_status</a>.</p>

</div>
</div>

### fs\_st\_size {#a03bab17d92e5629864b798aa0d3a37a4}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">off_t llvm::sys::fs::basic_file_status::fs_st_size = 0</td>
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



<p>Definition at line 141 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/support/filesystem-h">FileSystem.h</a>.</p>


<p>Referenced by <a href="#a16d8e6cdd1ccb3a201eb8b85dcb56797">basic_file_status</a> and <a href="#a46987fdc0db0174f80aea26291fde5d8">getSize</a>.</p>

</div>
</div>

### fs\_st\_uid {#a10f19674f74e144b01b07f45e8795a45}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">uid_t llvm::sys::fs::basic_file_status::fs_st_uid = 0</td>
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



<p>Definition at line 139 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/support/filesystem-h">FileSystem.h</a>.</p>


<p>Referenced by <a href="#a16d8e6cdd1ccb3a201eb8b85dcb56797">basic_file_status</a> and <a href="#ac57bcfa556142ba8d55024a174ab79ff">getUser</a>.</p>

</div>
</div>

### Perms {#a237aed551cb5292a2606caa4232234b5}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">perms llvm::sys::fs::basic_file_status::Perms = <a href="/web-llvm/docs/api/namespaces/llvm/sys/fs/#ac56b6ec1078927bdd9b65f7ba8fbda82ab52f98686d024f7db0196d6c3f1e791d">perms_not_known</a></td>
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



<p>Definition at line 151 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/support/filesystem-h">FileSystem.h</a>.</p>


<p>Referenced by <a href="#a16d8e6cdd1ccb3a201eb8b85dcb56797">basic_file_status</a>, <a href="/web-llvm/docs/api/classes/llvm/sys/fs/file-status/#a726f996c27ab1ab4baf0297160fd000d">llvm::sys::fs::file_status::file_status</a>, <a href="#a910720fdb892e47f864eb03fc7bebc3a">permissions</a> and <a href="#a18b2c1b3b9e5df3762d922a99bd0781a">permissions</a>.</p>

</div>
</div>

### Type {#afef5c100e6543383a11df67699cc5ced}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">file_type llvm::sys::fs::basic_file_status::Type = <a href="/web-llvm/docs/api/namespaces/llvm/sys/fs/#a6c50be965db24d7532b6b4e6b0755f5ca39fe2d3c413eb8d3f1d2f3b199fd29de">file_type::status_error</a></td>
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



<p>Definition at line 150 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/support/filesystem-h">FileSystem.h</a>.</p>


<p>Referenced by <a href="#ae7e88b89cf58ea85ecc6acdc824ab4d8">basic_file_status</a>, <a href="#a16d8e6cdd1ccb3a201eb8b85dcb56797">basic_file_status</a>, <a href="/web-llvm/docs/api/classes/llvm/sys/fs/file-status/#ab20647acd1a246cf271bb08287820aa4">llvm::sys::fs::file_status::file_status</a>, <a href="/web-llvm/docs/api/classes/llvm/sys/fs/file-status/#a726f996c27ab1ab4baf0297160fd000d">llvm::sys::fs::file_status::file_status</a>, <a href="#ab01b92f53a9f931c5859498219da2613">type</a> and <a href="#a382d1df8c510fbaec45f5fccdfcb5c4b">type</a>.</p>

</div>
</div>

</div>

<hr/>

The documentation for this class was generated from the following file:

<ul>
<li><a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/support/filesystem-h">FileSystem.h</a></li>
</ul>

<hr/>

<p class="doxyGeneratedBy">Generated via <a href="https://github.com/xpack/doxygen2docusaurus">doxygen2docusaurus</a> by <a href="https://www.doxygen.nl">Doxygen</a> 1.15.0.</p>

</div>
