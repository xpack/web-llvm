---

# DO NOT EDIT!
# Automatically generated via doxygen2docusaurus by Doxygen.

slug: /api/files/lib/lib/windowsdriver/msvcpaths-cpp
custom_edit_url: null
toc_max_heading_level: 4
keywords:
  - doxygen
  - reference
  - file

---

<div class="doxyPage">

# The `MSVCPaths.cpp` File Reference



## Included Headers

<div class="doxyIncludesList">#include "<a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/windowsdriver/msvcpaths-h">llvm/WindowsDriver/MSVCPaths.h</a>"
#include "<a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/adt/smallstring-h">llvm/ADT/SmallString.h</a>"
#include "<a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/adt/smallvector-h">llvm/ADT/SmallVector.h</a>"
#include "<a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/adt/stringextras-h">llvm/ADT/StringExtras.h</a>"
#include "<a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/adt/stringref-h">llvm/ADT/StringRef.h</a>"
#include "<a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/adt/twine-h">llvm/ADT/Twine.h</a>"
#include "<a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/support/path-h">llvm/Support/Path.h</a>"
#include "<a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/support/process-h">llvm/Support/Process.h</a>"
#include "<a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/support/program-h">llvm/Support/Program.h</a>"
#include "<a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/support/versiontuple-h">llvm/Support/VersionTuple.h</a>"
#include "<a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/support/virtualfilesystem-h">llvm/Support/VirtualFileSystem.h</a>"
#include "<a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/targetparser/host-h">llvm/TargetParser/Host.h</a>"
#include "<a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/targetparser/triple-h">llvm/TargetParser/Triple.h</a>"
#include &lt;optional&gt;
#include &lt;string&gt;
</div>

## Namespaces Index

<table class="doxyMembersIndex">

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">namespace</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="/web-llvm/docs/api/namespaces/llvm">llvm</a></td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>This is an optimization pass for GlobalISel generic memory operations. <a href="/web-llvm/docs/api/namespaces/llvm/#details">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

</table>

## Functions Index

<table class="doxyMembersIndex">

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">static <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/demangle/itaniumdemangle-h/#ae2b0d0345572d6718e219aa76d1d54edab45cffe084dd3d20d928bee85e7b0f21">std::string</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#aceedb180a9ae58c316577d97c5850392">getHighestNumericTupleInDirectory</a> (llvm::vfs::FileSystem &amp;VFS, llvm::StringRef Directory)</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">static bool</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#aaab71b93eca9d982bc9970e71076230f">getWindows10SDKVersionFromPath</a> (llvm::vfs::FileSystem &amp;VFS, const std::string &amp;SDKPath, std::string &amp;SDKVersion)</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">static bool</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a8805ce08308a58e2e99c8ab39d4ebdc2">getWindowsSDKDirViaCommandLine</a> (llvm::vfs::FileSystem &amp;VFS, std::optional&lt; llvm::StringRef &gt; WinSdkDir, std::optional&lt; llvm::StringRef &gt; WinSdkVersion, std::optional&lt; llvm::StringRef &gt; WinSysRoot, std::string &amp;Path, int &amp;Major, std::string &amp;Version)</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">static bool</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a721a1e2b9fcfe5e633cb413a6eabed8b">getSystemRegistryString</a> (const char *keyPath, const char *valueName, std::string &amp;value, std::string *phValue)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Read registry string. <a href="#a721a1e2b9fcfe5e633cb413a6eabed8b">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

</table>


<div class="doxySectionDef">

## Functions

### getHighestNumericTupleInDirectory() {#aceedb180a9ae58c316577d97c5850392}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">std::string getHighestNumericTupleInDirectory (<a href="/web-llvm/docs/api/classes/llvm/vfs/filesystem">llvm::vfs::FileSystem</a> &amp; VFS, <a href="/web-llvm/docs/api/classes/llvm/stringref">llvm::StringRef</a> Directory)</td>
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



<p>Definition at line 63 of file <a href="/web-llvm/docs/api/files/lib/lib/windowsdriver/msvcpaths-cpp">MSVCPaths.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/classes/llvm/vfs/filesystem/#a864ab0cadce5efa12c143f4f1429b22d">llvm::vfs::FileSystem::dir_begin</a>, <a href="/web-llvm/docs/api/namespaces/llvm/sys/path/#aa56d25bb5127dd7a5831c25764f76cbe">llvm::sys::path::filename</a>, <a href="/web-llvm/docs/api/classes/llvm/vfs/filesystem/#aff88129c51b36391cd8eb9f41747a03d">llvm::vfs::FileSystem::status</a> and <a href="/web-llvm/docs/api/classes/llvm/stringref/#a223dd14e7d12bc5cea01889b972a98b2">llvm::StringRef::str</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/namespaces/llvm/#a22439c20979b1335d2c672289f5a1d06">llvm::findVCToolChainViaCommandLine</a>, <a href="#aaab71b93eca9d982bc9970e71076230f">getWindows10SDKVersionFromPath</a> and <a href="#a8805ce08308a58e2e99c8ab39d4ebdc2">getWindowsSDKDirViaCommandLine</a>.</p>

</div>
</div>

### getSystemRegistryString() {#a721a1e2b9fcfe5e633cb413a6eabed8b}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool getSystemRegistryString (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> char * keyPath, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> char * valueName, <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/demangle/itaniumdemangle-h/#ae2b0d0345572d6718e219aa76d1d54edab45cffe084dd3d20d928bee85e7b0f21">std::string</a> &amp; value, <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/demangle/itaniumdemangle-h/#ae2b0d0345572d6718e219aa76d1d54edab45cffe084dd3d20d928bee85e7b0f21">std::string</a> * phValue)</td>
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

<p>Read registry string.</p>


<p>This also supports a means to look for high-versioned keys by use of a $VERSION placeholder in the key path. $VERSION in the key path is a placeholder for the version number, causing the highest value path to be searched for and used. I.e. "SOFTWARE\\Microsoft\\VisualStudio\\$VERSION". There can be additional characters in the component. Only the numeric characters are compared. This function only searches HKLM.</p>


<p>Definition at line 175 of file <a href="/web-llvm/docs/api/files/lib/lib/windowsdriver/msvcpaths-cpp">MSVCPaths.cpp</a>.</p>


<p>Reference <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/nvptx/nvvmreflect-cpp/#ac934769d93af95250952646a3829df4c">size</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/namespaces/llvm/#aee9b1b3966b67cad2185aac5d1159358">llvm::findVCToolChainViaRegistry</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#af944c296925180c38c773968d6970623">llvm::getUniversalCRTSdkDir</a> and <a href="/web-llvm/docs/api/namespaces/llvm/#a3f08996be2dce22d6d6777faaa4cbe41">llvm::getWindowsSDKDir</a>.</p>

</div>
</div>

### getWindows10SDKVersionFromPath() {#aaab71b93eca9d982bc9970e71076230f}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool getWindows10SDKVersionFromPath (<a href="/web-llvm/docs/api/classes/llvm/vfs/filesystem">llvm::vfs::FileSystem</a> &amp; VFS, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/demangle/itaniumdemangle-h/#ae2b0d0345572d6718e219aa76d1d54edab45cffe084dd3d20d928bee85e7b0f21">std::string</a> &amp; SDKPath, <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/demangle/itaniumdemangle-h/#ae2b0d0345572d6718e219aa76d1d54edab45cffe084dd3d20d928bee85e7b0f21">std::string</a> &amp; SDKVersion)</td>
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



<p>Definition at line 88 of file <a href="/web-llvm/docs/api/files/lib/lib/windowsdriver/msvcpaths-cpp">MSVCPaths.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/namespaces/llvm/sys/path/#acb80894344c78dacf8d5ff8c23be697d">llvm::sys::path::append</a> and <a href="#aceedb180a9ae58c316577d97c5850392">getHighestNumericTupleInDirectory</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/namespaces/llvm/#af944c296925180c38c773968d6970623">llvm::getUniversalCRTSdkDir</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a3f08996be2dce22d6d6777faaa4cbe41">llvm::getWindowsSDKDir</a> and <a href="#a8805ce08308a58e2e99c8ab39d4ebdc2">getWindowsSDKDirViaCommandLine</a>.</p>

</div>
</div>

### getWindowsSDKDirViaCommandLine() {#a8805ce08308a58e2e99c8ab39d4ebdc2}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool getWindowsSDKDirViaCommandLine (<a href="/web-llvm/docs/api/classes/llvm/vfs/filesystem">llvm::vfs::FileSystem</a> &amp; VFS, std::optional&lt; <a href="/web-llvm/docs/api/classes/llvm/stringref">llvm::StringRef</a> &gt; WinSdkDir, std::optional&lt; <a href="/web-llvm/docs/api/classes/llvm/stringref">llvm::StringRef</a> &gt; WinSdkVersion, std::optional&lt; <a href="/web-llvm/docs/api/classes/llvm/stringref">llvm::StringRef</a> &gt; WinSysRoot, <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/demangle/itaniumdemangle-h/#ae2b0d0345572d6718e219aa76d1d54edab45cffe084dd3d20d928bee85e7b0f21">std::string</a> &amp; Path, int &amp; Major, <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/demangle/itaniumdemangle-h/#ae2b0d0345572d6718e219aa76d1d54edab45cffe084dd3d20d928bee85e7b0f21">std::string</a> &amp; Version)</td>
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



<p>Definition at line 97 of file <a href="/web-llvm/docs/api/files/lib/lib/windowsdriver/msvcpaths-cpp">MSVCPaths.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/namespaces/llvm/sys/path/#acb80894344c78dacf8d5ff8c23be697d">llvm::sys::path::append</a>, <a href="/web-llvm/docs/api/classes/llvm/versiontuple/#ad07e5841d788dc29bdda972b3f92be6b">llvm::VersionTuple::empty</a>, <a href="/web-llvm/docs/api/classes/llvm/versiontuple/#a87d3c6e7d460d48dfe0ddd2c31793fa7">llvm::VersionTuple::getAsString</a>, <a href="#aceedb180a9ae58c316577d97c5850392">getHighestNumericTupleInDirectory</a>, <a href="/web-llvm/docs/api/classes/llvm/versiontuple/#a56a72b8793b8e0df7217c9b19a83320b">llvm::VersionTuple::getMajor</a>, <a href="#aaab71b93eca9d982bc9970e71076230f">getWindows10SDKVersionFromPath</a> and <a href="/web-llvm/docs/api/classes/llvm/versiontuple/#a6b61483aaba059f71022975a37737e15">llvm::VersionTuple::tryParse</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/namespaces/llvm/#af944c296925180c38c773968d6970623">llvm::getUniversalCRTSdkDir</a> and <a href="/web-llvm/docs/api/namespaces/llvm/#a3f08996be2dce22d6d6777faaa4cbe41">llvm::getWindowsSDKDir</a>.</p>

</div>
</div>

</div>

<hr/>

<p class="doxyGeneratedBy">Generated via <a href="https://github.com/xpack/doxygen2docusaurus">doxygen2docusaurus</a> by <a href="https://www.doxygen.nl">Doxygen</a> 1.15.0.</p>

</div>
