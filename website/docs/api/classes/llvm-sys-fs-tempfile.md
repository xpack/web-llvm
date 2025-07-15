---

# DO NOT EDIT!
# Automatically generated via doxygen2docusaurus by Doxygen.

slug: /api/classes/llvm/sys/fs/tempfile
custom_edit_url: null
toc_max_heading_level: 4
keywords:
  - doxygen
  - reference
  - class

---

<div class="doxyPage">

# The `TempFile` Class Reference

<p>Represents a temporary file. <a href="#details">More...</a></p>

## Declaration

<div class="doxyDeclaration">
class llvm::sys::fs::TempFile { ... }
</div>

## Included Headers

<div class="doxyIncludesList">#include "<a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/support/filesystem-h">llvm/Support/FileSystem.h</a>"
</div>

## Public Constructors Index

<table class="doxyMembersIndex">

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ac1989b93733b111bf3505736da4a50d3">TempFile</a> (TempFile &amp;&amp;Other)</td>
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

## Private Constructors Index

<table class="doxyMembersIndex">

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a511cacc9a43df4edbed203657d1f62e4">TempFile</a> (StringRef Name, int FD)</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a34cc1ff3b84abef11b7f9205df54586a">~TempFile</a> ()</td>
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

## Public Operators Index

<table class="doxyMembersIndex">

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/sys/fs/tempfile">TempFile</a> &amp;</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ac57d2b0173b16ebf3ab8f110bce530c5">operator=</a> (TempFile &amp;&amp;Other)</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ad0b321ee190fd8f67b1f1792b30ff998">keep</a> (const Twine &amp;Name)</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/error">Error</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a218862a665465ddb719d8ac441e0b5ab">keep</a> ()</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/error">Error</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ac804c3ad178df1dd809e2232f9837e50">discard</a> ()</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">std::string</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a71e2844783eeee86b99de4edaaefed5a">TmpName</a></td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">int</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#aaf40303570c1faadddf7420f19a25acd">FD</a> = -1</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">bool</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a2f4c3a2a2a3e5168dffa70dc6e89c7b6">Done</a> = false</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">static <a href="/web-llvm/docs/api/classes/llvm/expected">Expected</a>&lt; <a href="/web-llvm/docs/api/classes/llvm/sys/fs/tempfile">TempFile</a> &gt;</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ad1d2e9ae2eb5ea7e7b60f8bcb715b2e9">create</a> (const Twine &amp;Model, unsigned Mode=all_read|all_write, OpenFlags ExtraFlags=OF_None)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>This creates a temporary file with createUniqueFile and schedules it for deletion with <a href="/web-llvm/docs/api/namespaces/llvm/sys/#aee27cc5336ecd3f21eeda4ad2826b915">sys::RemoveFileOnSignal</a>. <a href="#ad1d2e9ae2eb5ea7e7b60f8bcb715b2e9">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

</table>

## Description {#details}

<p>Represents a temporary file.</p>


<p>The temporary file must be eventually discarded or given a final name and kept.</p>


<p>The destructor doesn't implicitly discard because there is no way to properly handle errors in a destructor.</p>


<p>Definition at line 843 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/support/filesystem-h">FileSystem.h</a>.</p>


<div class="doxySectionDef">

## Public Constructors

### TempFile() {#ac1989b93733b111bf3505736da4a50d3}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">llvm::sys::fs::TempFile::TempFile (<a href="/web-llvm/docs/api/classes/llvm/sys/fs/tempfile">TempFile</a> &amp;&amp; Other)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Declaration at line 853 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/support/filesystem-h">FileSystem.h</a>, definition at line 1211 of file <a href="/web-llvm/docs/api/files/lib/lib/support/path-cpp">Path.cpp</a>.</p>


<p>Reference <a href="/web-llvm/docs/api/namespaces/llvm/#a9eb4f5b98b70ee4fab9614ed58282c1fa6311ae17c1ee52b36e68aaf4ad066387">llvm::Other</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Private Constructors

### TempFile() {#a511cacc9a43df4edbed203657d1f62e4}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">llvm::sys::fs::TempFile::TempFile (<a href="/web-llvm/docs/api/classes/llvm/stringref">StringRef</a> Name, int FD)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Declaration at line 845 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/support/filesystem-h">FileSystem.h</a>, definition at line 1209 of file <a href="/web-llvm/docs/api/files/lib/lib/support/path-cpp">Path.cpp</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Public Destructor

### \~TempFile() {#a34cc1ff3b84abef11b7f9205df54586a}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">llvm::sys::fs::TempFile::~TempFile ()</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Declaration at line 877 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/support/filesystem-h">FileSystem.h</a>, definition at line 1224 of file <a href="/web-llvm/docs/api/files/lib/lib/support/path-cpp">Path.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/silowercontrolflow-cpp/#a4868c5d81c5ccc98c47aeab6244346a0">assert</a> and <a href="#a34cc1ff3b84abef11b7f9205df54586a">~TempFile</a>.</p>


<p>Referenced by <a href="#a34cc1ff3b84abef11b7f9205df54586a">~TempFile</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Public Operators

### operator=() {#ac57d2b0173b16ebf3ab8f110bce530c5}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">TempFile &amp; llvm::sys::fs::TempFile::operator= (<a href="/web-llvm/docs/api/classes/llvm/sys/fs/tempfile">TempFile</a> &amp;&amp; Other)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Declaration at line 854 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/support/filesystem-h">FileSystem.h</a>, definition at line 1212 of file <a href="/web-llvm/docs/api/files/lib/lib/support/path-cpp">Path.cpp</a>.</p>


<p>References <a href="#aaf40303570c1faadddf7420f19a25acd">FD</a>, <a href="#ac57d2b0173b16ebf3ab8f110bce530c5">operator=</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a9eb4f5b98b70ee4fab9614ed58282c1fa6311ae17c1ee52b36e68aaf4ad066387">llvm::Other</a> and <a href="#a71e2844783eeee86b99de4edaaefed5a">TmpName</a>.</p>


<p>Referenced by <a href="#ac57d2b0173b16ebf3ab8f110bce530c5">operator=</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Public Member Functions

### discard() {#ac804c3ad178df1dd809e2232f9837e50}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">Error llvm::sys::fs::TempFile::discard ()</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Declaration at line 874 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/support/filesystem-h">FileSystem.h</a>, definition at line 1226 of file <a href="/web-llvm/docs/api/files/lib/lib/support/path-cpp">Path.cpp</a>.</p>


<p>References <a href="#ac804c3ad178df1dd809e2232f9837e50">discard</a>, <a href="/web-llvm/docs/api/namespaces/llvm/sys/#a7936dae925973eb8b0921c01b70b16d8">llvm::sys::DontRemoveFileOnSignal</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#ae075c94db10b09d6d5876d32219eaf0d">llvm::errnoAsErrorCode</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#ad10875fd499e8e285aaeef615e9b11aa">llvm::errorCodeToError</a>, <a href="#aaf40303570c1faadddf7420f19a25acd">FD</a>, <a href="/web-llvm/docs/api/namespaces/llvm/sys/fs/#a921e0b01f22f9a37012450f9b5f0ccb7">llvm::sys::fs::remove</a> and <a href="#a71e2844783eeee86b99de4edaaefed5a">TmpName</a>.</p>


<p>Referenced by <a href="#ac804c3ad178df1dd809e2232f9837e50">discard</a> and <a href="/web-llvm/docs/api/namespaces/llvm/#af73b4fcac77298355025a0e5975edcf0">llvm::localCache</a>.</p>

</div>
</div>

### keep() {#ad0b321ee190fd8f67b1f1792b30ff998}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">Error llvm::sys::fs::TempFile::keep (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/twine">Twine</a> &amp; Name)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Declaration at line 868 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/support/filesystem-h">FileSystem.h</a>, definition at line 1254 of file <a href="/web-llvm/docs/api/files/lib/lib/support/path-cpp">Path.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/silowercontrolflow-cpp/#a4868c5d81c5ccc98c47aeab6244346a0">assert</a>, <a href="/web-llvm/docs/api/namespaces/llvm/sys/fs/#abe768b38d21bfc2bc91a1c1d09cd84de">llvm::sys::fs::copy_file</a>, <a href="/web-llvm/docs/api/namespaces/llvm/sys/#a7936dae925973eb8b0921c01b70b16d8">llvm::sys::DontRemoveFileOnSignal</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#ae075c94db10b09d6d5876d32219eaf0d">llvm::errnoAsErrorCode</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#ad10875fd499e8e285aaeef615e9b11aa">llvm::errorCodeToError</a>, <a href="#aaf40303570c1faadddf7420f19a25acd">FD</a>, <a href="/web-llvm/docs/api/files/lib/lib/support/md5-cpp/#ae42219072d798876e6b08e6b78614ff6">H</a>, <a href="#ad0b321ee190fd8f67b1f1792b30ff998">keep</a>, <a href="/web-llvm/docs/api/namespaces/llvm/sys/fs/#a921e0b01f22f9a37012450f9b5f0ccb7">llvm::sys::fs::remove</a>, <a href="/web-llvm/docs/api/namespaces/llvm/sys/fs/#a4d0e197f8a614f1a6a60a1ef636a3e0d">llvm::sys::fs::rename</a> and <a href="#a71e2844783eeee86b99de4edaaefed5a">TmpName</a>.</p>


<p>Referenced by <a href="#a218862a665465ddb719d8ac441e0b5ab">keep</a>, <a href="#ad0b321ee190fd8f67b1f1792b30ff998">keep</a> and <a href="/web-llvm/docs/api/namespaces/llvm/#af73b4fcac77298355025a0e5975edcf0">llvm::localCache</a>.</p>

</div>
</div>

### keep() {#a218862a665465ddb719d8ac441e0b5ab}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">Error llvm::sys::fs::TempFile::keep ()</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Declaration at line 871 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/support/filesystem-h">FileSystem.h</a>, definition at line 1305 of file <a href="/web-llvm/docs/api/files/lib/lib/support/path-cpp">Path.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/silowercontrolflow-cpp/#a4868c5d81c5ccc98c47aeab6244346a0">assert</a>, <a href="/web-llvm/docs/api/namespaces/llvm/sys/#a7936dae925973eb8b0921c01b70b16d8">llvm::sys::DontRemoveFileOnSignal</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#ae075c94db10b09d6d5876d32219eaf0d">llvm::errnoAsErrorCode</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#ad10875fd499e8e285aaeef615e9b11aa">llvm::errorCodeToError</a>, <a href="#aaf40303570c1faadddf7420f19a25acd">FD</a>, <a href="/web-llvm/docs/api/files/lib/lib/support/md5-cpp/#ae42219072d798876e6b08e6b78614ff6">H</a>, <a href="#ad0b321ee190fd8f67b1f1792b30ff998">keep</a>, <a href="/web-llvm/docs/api/classes/llvm/error/#a4dfd0813c3d0e0a30439b5a3e9196b59">llvm::Error::success</a> and <a href="#a71e2844783eeee86b99de4edaaefed5a">TmpName</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Public Member Attributes

### FD {#aaf40303570c1faadddf7420f19a25acd}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">int llvm::sys::fs::TempFile::FD = -1</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 860 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/support/filesystem-h">FileSystem.h</a>.</p>


<p>Referenced by <a href="#ad1d2e9ae2eb5ea7e7b60f8bcb715b2e9">create</a>, <a href="#ac804c3ad178df1dd809e2232f9837e50">discard</a>, <a href="#a218862a665465ddb719d8ac441e0b5ab">keep</a>, <a href="#ad0b321ee190fd8f67b1f1792b30ff998">keep</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#af73b4fcac77298355025a0e5975edcf0">llvm::localCache</a> and <a href="#ac57d2b0173b16ebf3ab8f110bce530c5">operator=</a>.</p>

</div>
</div>

### TmpName {#a71e2844783eeee86b99de4edaaefed5a}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">std::string llvm::sys::fs::TempFile::TmpName</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 857 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/support/filesystem-h">FileSystem.h</a>.</p>


<p>Referenced by <a href="#ac804c3ad178df1dd809e2232f9837e50">discard</a>, <a href="#a218862a665465ddb719d8ac441e0b5ab">keep</a>, <a href="#ad0b321ee190fd8f67b1f1792b30ff998">keep</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#af73b4fcac77298355025a0e5975edcf0">llvm::localCache</a> and <a href="#ac57d2b0173b16ebf3ab8f110bce530c5">operator=</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Private Member Attributes

### Done {#a2f4c3a2a2a3e5168dffa70dc6e89c7b6}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool llvm::sys::fs::TempFile::Done = false</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 844 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/support/filesystem-h">FileSystem.h</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Public Static Functions

### create() {#ad1d2e9ae2eb5ea7e7b60f8bcb715b2e9}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">Expected&lt; TempFile &gt; llvm::sys::fs::TempFile::create (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/twine">Twine</a> &amp; Model, unsigned Mode=<a href="/web-llvm/docs/api/namespaces/llvm/sys/fs/#ac56b6ec1078927bdd9b65f7ba8fbda82ab5e842a50787e803e6e66bc9cc73f634">all_read</a>|<a href="/web-llvm/docs/api/namespaces/llvm/sys/fs/#ac56b6ec1078927bdd9b65f7ba8fbda82a1c2301837e9bfe7c9c8421b540d92822">all_write</a>, <a href="/web-llvm/docs/api/namespaces/llvm/sys/fs/#a662978c0cdf81de0d448032f142a3695">OpenFlags</a> ExtraFlags=<a href="/web-llvm/docs/api/namespaces/llvm/sys/fs/#a662978c0cdf81de0d448032f142a3695a8ae6a0a158ab49e5bbe92cbc2cabcbcd">OF_None</a>)</td>
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

<p>This creates a temporary file with createUniqueFile and schedules it for deletion with <a href="/web-llvm/docs/api/namespaces/llvm/sys/#aee27cc5336ecd3f21eeda4ad2826b915">sys::RemoveFileOnSignal</a>.</p>

<p>Declaration at line 850 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/support/filesystem-h">FileSystem.h</a>, definition at line 1325 of file <a href="/web-llvm/docs/api/files/lib/lib/support/path-cpp">Path.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/namespaces/llvm/#aee0e70be66536b9ef7b65ae2e5a45959">llvm::consumeError</a>, <a href="#ad1d2e9ae2eb5ea7e7b60f8bcb715b2e9">create</a>, <a href="/web-llvm/docs/api/namespaces/llvm/sys/fs/#a7efe580e0855b9d68d0b884b79ebf955">llvm::sys::fs::createUniqueFile</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#ad10875fd499e8e285aaeef615e9b11aa">llvm::errorCodeToError</a>, <a href="#aaf40303570c1faadddf7420f19a25acd">FD</a>, <a href="/web-llvm/docs/api/files/lib/lib/support/md5-cpp/#ae42219072d798876e6b08e6b78614ff6">H</a>, <a href="/web-llvm/docs/api/namespaces/llvm/sys/fs/#a662978c0cdf81de0d448032f142a3695a1dc24818b1dbdad67273366de980998b">llvm::sys::fs::OF_Delete</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a59739a4f15fb2ec57a6b7fcfe938546ba8344b3d509942f035d5e303022f9b986">llvm::operation_not_permitted</a> and <a href="/web-llvm/docs/api/namespaces/llvm/sys/#aee27cc5336ecd3f21eeda4ad2826b915">llvm::sys::RemoveFileOnSignal</a>.</p>


<p>Referenced by <a href="#ad1d2e9ae2eb5ea7e7b60f8bcb715b2e9">create</a>, <a href="/web-llvm/docs/api/files/lib/lib/support/fileoutputbuffer-cpp/#a31b5a8b8b08e1fc483335974755720ed">createOnDiskBuffer</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#af73b4fcac77298355025a0e5975edcf0">llvm::localCache</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a1437ccb0a1879b013ec4e26ed265bc4a">llvm::writeArchive</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a80a1017cd2662da510365c7ee41a782a">llvm::writeToOutput</a> and <a href="/web-llvm/docs/api/namespaces/llvm/object/#a747323aef7153b9358ab839fdcfc4468">llvm::object::writeUniversalBinary</a>.</p>

</div>
</div>

</div>

<hr/>

The documentation for this class was generated from the following files:

<ul>
<li><a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/support/filesystem-h">FileSystem.h</a></li>
<li><a href="/web-llvm/docs/api/files/lib/lib/support/path-cpp">Path.cpp</a></li>
</ul>

<hr/>

<p class="doxyGeneratedBy">Generated via <a href="https://github.com/xpack/doxygen2docusaurus">doxygen2docusaurus</a> by <a href="https://www.doxygen.nl">Doxygen</a> 1.14.0.</p>

</div>
