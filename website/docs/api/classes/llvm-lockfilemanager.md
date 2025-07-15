---

# DO NOT EDIT!
# Automatically generated via doxygen2docusaurus by Doxygen.

slug: /api/classes/llvm/lockfilemanager
custom_edit_url: null
toc_max_heading_level: 4
keywords:
  - doxygen
  - reference
  - class

---

<div class="doxyPage">

# The `LockFileManager` Class Reference

<p>Class that manages the creation of a lock file to aid implicit coordination between different processes. <a href="#details">More...</a></p>

## Declaration

<div class="doxyDeclaration">
class llvm::LockFileManager { ... }
</div>

## Included Headers

<div class="doxyIncludesList">#include "<a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/support/lockfilemanager-h">llvm/Support/LockFileManager.h</a>"
</div>

## Enumerations Index

<table class="doxyMembersIndex">

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">enum</td>
<td class="doxyMemberIndexItemName" align="left" valign="top">LockFileState { <a href="#a1fcefc1a8c747197b9ee8b5e99d732fc">...</a> }</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Describes the state of a lock file. <a href="#a1fcefc1a8c747197b9ee8b5e99d732fc">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">enum</td>
<td class="doxyMemberIndexItemName" align="left" valign="top">WaitForUnlockResult { <a href="#a9973b06ec4b8e2f93a9308b85c1b8b30">...</a> }</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Describes the result of waiting for the owner to release the lock. <a href="#a9973b06ec4b8e2f93a9308b85c1b8b30">More...</a></p>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ae09841830258172ba68866f0376898eb">LockFileManager</a> (StringRef FileName)</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ae62726b0ef31c87d9ba9f4d644e269da">LockFileManager</a> (const LockFileManager &amp;)=delete</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a12291e21b11c09c114c05a7225bb0812">~LockFileManager</a> ()</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a2d524267ff5db7badda8ff1bfbe5a30f">operator LockFileState</a> () const</td>
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

## Private Operators Index

<table class="doxyMembersIndex">

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/lockfilemanager">LockFileManager</a> &amp;</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a9bcc381e3a964eebef1d4518f9fe4725">operator=</a> (const LockFileManager &amp;)=delete</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="#a1fcefc1a8c747197b9ee8b5e99d732fc">LockFileState</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ae2a81443bc8265b761544ed8d58cd391">getState</a> () const</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Determine the state of the lock file. <a href="#ae2a81443bc8265b761544ed8d58cd391">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="#a9973b06ec4b8e2f93a9308b85c1b8b30">WaitForUnlockResult</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a8a975a4bfeea746f3269211bd72a02e2">waitForUnlock</a> (const unsigned MaxSeconds=90)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>For a shared lock, wait until the owner releases the lock. <a href="#a8a975a4bfeea746f3269211bd72a02e2">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">std::error_code</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a69275e764ccafbee027de7780fa72e4a">unsafeRemoveLockFile</a> ()</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Remove the lock file. <a href="#a69275e764ccafbee027de7780fa72e4a">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">std::string</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a304e4ca0ae264c754c47af07ef4cfaa6">getErrorMessage</a> () const</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Get error message, or "" if there is no error. <a href="#a304e4ca0ae264c754c47af07ef4cfaa6">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">void</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a5c1d619b63ed612ce3102028fb6940af">setError</a> (const std::error_code &amp;EC, StringRef ErrorMsg="")</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Set error and error message. <a href="#a5c1d619b63ed612ce3102028fb6940af">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

</table>

## Private Member Attributes Index

<table class="doxyMembersIndex">

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/smallstring">SmallString</a>&lt; 128 &gt;</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a88c69d5283cf5c582ac621a67a7ecfbf">FileName</a></td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/smallstring">SmallString</a>&lt; 128 &gt;</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#aecdaf7644450328b99ae61bac9710e4b">LockFileName</a></td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/smallstring">SmallString</a>&lt; 128 &gt;</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#aeb82e984eb44924d6b972b46a92ad597">UniqueLockFileName</a></td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">std::optional&lt; std::pair&lt; std::string, int &gt; &gt;</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ab9eb6295f4157672c80d9b2e022f4294">Owner</a></td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#aa50a79174f3f83b36788272f35542158">ErrorCode</a></td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a5856afdace2e29052d3171ebfa78bdc5">ErrorDiagMsg</a></td>
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

## Private Static Functions Index

<table class="doxyMembersIndex">

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">static std::optional&lt; std::pair&lt; std::string, int &gt; &gt;</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ac9680279a64003d185d4c87a009de9a2">readLockFile</a> (StringRef LockFileName)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Attempt to read the lock file with the given name, if it exists. <a href="#ac9680279a64003d185d4c87a009de9a2">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">static bool</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a5ad1b8cbbcc6f591f9402652a6e10a31">processStillExecuting</a> (StringRef Hostname, int PID)</td>
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

<p>Class that manages the creation of a lock file to aid implicit coordination between different processes.</p>


<p>The implicit coordination works by creating a ".lock" file alongside the file that we're coordinating for, using the atomicity of the file system to ensure that only a single process can create that ".lock" file. When the lock file is removed, the owning process has finished the operation.</p>


<p>Definition at line 27 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/support/lockfilemanager-h">LockFileManager.h</a>.</p>


<div class="doxySectionDef">

## Enumerations

### LockFileState {#a1fcefc1a8c747197b9ee8b5e99d732fc}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">enum llvm::LockFileManager::LockFileState </td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Describes the state of a lock file.</p>

<dl class="doxyEnumList">
<dt class="doxyEnumTableTitle">Enumeration values</dt>
<dd>
<table class="doxyEnumTable">

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">LFS_Owned<a id="a1fcefc1a8c747197b9ee8b5e99d732fca78582d1ab0d9e0abbed2abbea232f529"></a></td>
<td class="doxyEnumItemDescription">The lock file has been created and is owned by this instance of the object</td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">LFS_Shared<a id="a1fcefc1a8c747197b9ee8b5e99d732fcabfd64c399ca341b115a17cf25bf161a2"></a></td>
<td class="doxyEnumItemDescription">The lock file already exists and is owned by some other instance</td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">LFS_Error<a id="a1fcefc1a8c747197b9ee8b5e99d732fca5efdb4b665559526df56fb2634198440"></a></td>
<td class="doxyEnumItemDescription">An error occurred while trying to create or find the lock file</td>
</tr>

</table>
</dd>
</dl>

<p>Definition at line 30 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/support/lockfilemanager-h">LockFileManager.h</a>.</p>

</div>
</div>

### WaitForUnlockResult {#a9973b06ec4b8e2f93a9308b85c1b8b30}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">enum llvm::LockFileManager::WaitForUnlockResult </td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Describes the result of waiting for the owner to release the lock.</p>

<dl class="doxyEnumList">
<dt class="doxyEnumTableTitle">Enumeration values</dt>
<dd>
<table class="doxyEnumTable">

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">Res_Success<a id="a9973b06ec4b8e2f93a9308b85c1b8b30a213a07aec4e7e7d016b3bd594daf9cc5"></a></td>
<td class="doxyEnumItemDescription">The lock was released successfully</td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">Res_OwnerDied<a id="a9973b06ec4b8e2f93a9308b85c1b8b30ae933c5a1f2e505b61d59df1e3937adef"></a></td>
<td class="doxyEnumItemDescription">Owner died while holding the lock</td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">Res_Timeout<a id="a9973b06ec4b8e2f93a9308b85c1b8b30a2b00d68ed92fa7423fd1e18f31945d53"></a></td>
<td class="doxyEnumItemDescription">Reached timeout while waiting for the owner to release the lock</td>
</tr>

</table>
</dd>
</dl>

<p>Definition at line 43 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/support/lockfilemanager-h">LockFileManager.h</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Public Constructors

### LockFileManager() {#ae09841830258172ba68866f0376898eb}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">LockFileManager::LockFileManager (<a href="/web-llvm/docs/api/classes/llvm/stringref">StringRef</a> FileName)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Declaration at line 71 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/support/lockfilemanager-h">LockFileManager.h</a>, definition at line 160 of file <a href="/web-llvm/docs/api/files/lib/lib/support/lockfilemanager-cpp">LockFileManager.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/classes/llvm/raw-fd-ostream/#a7b4fefe70f73556669fd513ed9d0fae4">llvm::raw_fd_ostream::clear_error</a>, <a href="/web-llvm/docs/api/classes/llvm/raw-fd-ostream/#a293545f9b5864a8e1b33e57becbc5b3a">llvm::raw_fd_ostream::close</a>, <a href="/web-llvm/docs/api/namespaces/llvm/sys/fs/#a104eea5a51402274ef2499a3ee6c64b8">llvm::sys::fs::create_link</a>, <a href="/web-llvm/docs/api/namespaces/llvm/sys/fs/#a7efe580e0855b9d68d0b884b79ebf955">llvm::sys::fs::createUniqueFile</a>, <a href="/web-llvm/docs/api/classes/llvm/raw-fd-ostream/#a215c95ed69aa5b5756dd9c0f1b1de410">llvm::raw_fd_ostream::error</a>, <a href="/web-llvm/docs/api/namespaces/llvm/sys/fs/#a645a607ffcccb12f16a5736db991e7d9">llvm::sys::fs::exists</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a59739a4f15fb2ec57a6b7fcfe938546ba41edf636e3c7b59f797348fc58472258">llvm::file_exists</a>, <a href="/web-llvm/docs/api/files/lib/lib/support/lockfilemanager-cpp/#a9a22b7220c3b5b3b0a05ab7070c8e5ff">getHostID</a>, <a href="/web-llvm/docs/api/classes/llvm/sys/process/#afee014293ce837f92658166fc36a2d15">llvm::sys::Process::getProcessId</a>, <a href="/web-llvm/docs/api/classes/llvm/raw-fd-ostream/#a0d5a564fb5459ab9ce6e56401786542b">llvm::raw_fd_ostream::has_error</a>, <a href="/web-llvm/docs/api/namespaces/llvm/sys/fs/#a144ec9dcc77027317d16af9fc5fec1c8">llvm::sys::fs::make_absolute</a>, <a href="/web-llvm/docs/api/namespaces/llvm/sys/fs/#a921e0b01f22f9a37012450f9b5f0ccb7">llvm::sys::fs::remove</a>, <a href="#a5c1d619b63ed612ce3102028fb6940af">setError</a> and <a href="/web-llvm/docs/api/classes/llvm/raw-string-ostream/#a6732e8d3ff8100a662ce73634840b990">llvm::raw_string_ostream::str</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Private Constructors

### LockFileManager() {#ae62726b0ef31c87d9ba9f4d644e269da}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">llvm::LockFileManager::LockFileManager (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/lockfilemanager">LockFileManager</a> &amp;)</td>
</tr>
</table>
</td>
<td class="doxyMemberLabelsRight">
<span class="doxyMemberLabels">
<span class="doxyMemberLabel delete">delete</span>
</span>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 61 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/support/lockfilemanager-h">LockFileManager.h</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Public Destructor

### \~LockFileManager() {#a12291e21b11c09c114c05a7225bb0812}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">LockFileManager::~LockFileManager ()</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Declaration at line 72 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/support/lockfilemanager-h">LockFileManager.h</a>, definition at line 282 of file <a href="/web-llvm/docs/api/files/lib/lib/support/lockfilemanager-cpp">LockFileManager.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/namespaces/llvm/sys/#a7936dae925973eb8b0921c01b70b16d8">llvm::sys::DontRemoveFileOnSignal</a>, <a href="#ae2a81443bc8265b761544ed8d58cd391">getState</a>, <a href="#a1fcefc1a8c747197b9ee8b5e99d732fca78582d1ab0d9e0abbed2abbea232f529">LFS_Owned</a> and <a href="/web-llvm/docs/api/namespaces/llvm/sys/fs/#a921e0b01f22f9a37012450f9b5f0ccb7">llvm::sys::fs::remove</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Public Operators

### operator LockFileState() {#a2d524267ff5db7badda8ff1bfbe5a30f}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">llvm::LockFileManager::operator LockFileState ()</td>
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



<p>Definition at line 77 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/support/lockfilemanager-h">LockFileManager.h</a>.</p>


<p>Reference <a href="#ae2a81443bc8265b761544ed8d58cd391">getState</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Private Operators

### operator=() {#a9bcc381e3a964eebef1d4518f9fe4725}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">LockFileManager &amp; llvm::LockFileManager::operator= (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/lockfilemanager">LockFileManager</a> &amp;)</td>
</tr>
</table>
</td>
<td class="doxyMemberLabelsRight">
<span class="doxyMemberLabels">
<span class="doxyMemberLabel delete">delete</span>
</span>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 62 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/support/lockfilemanager-h">LockFileManager.h</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Public Member Functions

### getErrorMessage() {#a304e4ca0ae264c754c47af07ef4cfaa6}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">std::string LockFileManager::getErrorMessage ()</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Get error message, or "" if there is no error.</p>

<p>Declaration at line 89 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/support/lockfilemanager-h">LockFileManager.h</a>, definition at line 270 of file <a href="/web-llvm/docs/api/files/lib/lib/support/lockfilemanager-cpp">LockFileManager.cpp</a>.</p>

</div>
</div>

### getState() {#ae2a81443bc8265b761544ed8d58cd391}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">LockFileManager::LockFileState LockFileManager::getState ()</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Determine the state of the lock file.</p>

<p>Declaration at line 75 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/support/lockfilemanager-h">LockFileManager.h</a>, definition at line 260 of file <a href="/web-llvm/docs/api/files/lib/lib/support/lockfilemanager-cpp">LockFileManager.cpp</a>.</p>


<p>References <a href="#a1fcefc1a8c747197b9ee8b5e99d732fca5efdb4b665559526df56fb2634198440">LFS_Error</a>, <a href="#a1fcefc1a8c747197b9ee8b5e99d732fca78582d1ab0d9e0abbed2abbea232f529">LFS_Owned</a> and <a href="#a1fcefc1a8c747197b9ee8b5e99d732fcabfd64c399ca341b115a17cf25bf161a2">LFS_Shared</a>.</p>


<p>Referenced by <a href="#a2d524267ff5db7badda8ff1bfbe5a30f">operator LockFileState</a>, <a href="#a8a975a4bfeea746f3269211bd72a02e2">waitForUnlock</a> and <a href="#a12291e21b11c09c114c05a7225bb0812">~LockFileManager</a>.</p>

</div>
</div>

### setError() {#a5c1d619b63ed612ce3102028fb6940af}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void llvm::LockFileManager::setError (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> std::error_code &amp; EC, <a href="/web-llvm/docs/api/classes/llvm/stringref">StringRef</a> ErrorMsg="")</td>
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

<p>Set error and error message.</p>

<p>Definition at line 92 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/support/lockfilemanager-h">LockFileManager.h</a>.</p>


<p>Referenced by <a href="#ae09841830258172ba68866f0376898eb">LockFileManager</a>.</p>

</div>
</div>

### unsafeRemoveLockFile() {#a69275e764ccafbee027de7780fa72e4a}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">std::error_code LockFileManager::unsafeRemoveLockFile ()</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Remove the lock file.</p>


<p>This may delete a different lock file than the one previously read if there is a race.</p>


<p>Declaration at line 86 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/support/lockfilemanager-h">LockFileManager.h</a>, definition at line 326 of file <a href="/web-llvm/docs/api/files/lib/lib/support/lockfilemanager-cpp">LockFileManager.cpp</a>.</p>


<p>Reference <a href="/web-llvm/docs/api/namespaces/llvm/sys/fs/#a921e0b01f22f9a37012450f9b5f0ccb7">llvm::sys::fs::remove</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/classes/llvm/amdgpusplitmodulepass/#a5fdf4ead69288861f3151e0f035a9877">llvm::AMDGPUSplitModulePass::run</a>.</p>

</div>
</div>

### waitForUnlock() {#a8a975a4bfeea746f3269211bd72a02e2}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">LockFileManager::WaitForUnlockResult LockFileManager::waitForUnlock (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> unsigned MaxSeconds=90)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>For a shared lock, wait until the owner releases the lock.</p>


<p>Total timeout for the file to appear is ~1.5 minutes.</p>


<dl class="doxyParamsList">
<dt class="doxyParamsTableTitle">Parameters</dt>
<dd>
<table class="doxyParamsTable">
<tr class="doxyParamItem">
<td class="doxyParamItemName">MaxSeconds</td>
<td class="doxyParamItemDescription"><p>the maximum total wait time in seconds.</p></td>
</tr>
</table>
</dd>
</dl>

<p>Declaration at line 82 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/support/lockfilemanager-h">LockFileManager.h</a>, definition at line 295 of file <a href="/web-llvm/docs/api/files/lib/lib/support/lockfilemanager-cpp">LockFileManager.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/namespaces/llvm/sys/fs/#a592297dd80c13e993380e2bf972721ac">llvm::sys::fs::access</a>, <a href="/web-llvm/docs/api/namespaces/llvm/sys/fs/#ab3cde71d019a4b19046fa286973656ebadd7f7c3323353f547eb98a8efba37ed0">llvm::sys::fs::Exist</a>, <a href="/web-llvm/docs/api/namespaces/llvm/sys/fs/#a645a607ffcccb12f16a5736db991e7d9">llvm::sys::fs::exists</a>, <a href="#ae2a81443bc8265b761544ed8d58cd391">getState</a>, <a href="#a1fcefc1a8c747197b9ee8b5e99d732fcabfd64c399ca341b115a17cf25bf161a2">LFS_Shared</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a59739a4f15fb2ec57a6b7fcfe938546ba2e70fc89b08f26fa3fc77694c91e8f7a">llvm::no_such_file_or_directory</a>, <a href="#a9973b06ec4b8e2f93a9308b85c1b8b30ae933c5a1f2e505b61d59df1e3937adef">Res_OwnerDied</a>, <a href="#a9973b06ec4b8e2f93a9308b85c1b8b30a213a07aec4e7e7d016b3bd594daf9cc5">Res_Success</a>, <a href="#a9973b06ec4b8e2f93a9308b85c1b8b30a2b00d68ed92fa7423fd1e18f31945d53">Res_Timeout</a> and <a href="/web-llvm/docs/api/classes/llvm/exponentialbackoff/#a2e8404047337057e4fff7e416f28ce3b">llvm::ExponentialBackoff::waitForNextAttempt</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/classes/llvm/amdgpusplitmodulepass/#a5fdf4ead69288861f3151e0f035a9877">llvm::AMDGPUSplitModulePass::run</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Private Member Attributes

### ErrorCode {#aa50a79174f3f83b36788272f35542158}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">std::error_code llvm::LockFileManager::ErrorCode</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 58 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/support/lockfilemanager-h">LockFileManager.h</a>.</p>

</div>
</div>

### ErrorDiagMsg {#a5856afdace2e29052d3171ebfa78bdc5}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">std::string llvm::LockFileManager::ErrorDiagMsg</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 59 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/support/lockfilemanager-h">LockFileManager.h</a>.</p>

</div>
</div>

### FileName {#a88c69d5283cf5c582ac621a67a7ecfbf}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">SmallString&lt;128&gt; llvm::LockFileManager::FileName</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 53 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/support/lockfilemanager-h">LockFileManager.h</a>.</p>

</div>
</div>

### LockFileName {#aecdaf7644450328b99ae61bac9710e4b}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">SmallString&lt;128&gt; llvm::LockFileManager::LockFileName</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 54 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/support/lockfilemanager-h">LockFileManager.h</a>.</p>

</div>
</div>

### Owner {#ab9eb6295f4157672c80d9b2e022f4294}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">std::optional&lt;std::pair&lt;std::string, int&gt; &gt; llvm::LockFileManager::Owner</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 57 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/support/lockfilemanager-h">LockFileManager.h</a>.</p>

</div>
</div>

### UniqueLockFileName {#aeb82e984eb44924d6b972b46a92ad597}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">SmallString&lt;128&gt; llvm::LockFileManager::UniqueLockFileName</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 55 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/support/lockfilemanager-h">LockFileManager.h</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Private Static Functions

### processStillExecuting() {#a5ad1b8cbbcc6f591f9402652a6e10a31}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool LockFileManager::processStillExecuting (<a href="/web-llvm/docs/api/classes/llvm/stringref">StringRef</a> Hostname, int PID)</td>
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



<p>Declaration at line 67 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/support/lockfilemanager-h">LockFileManager.h</a>, definition at line 113 of file <a href="/web-llvm/docs/api/files/lib/lib/support/lockfilemanager-cpp">LockFileManager.cpp</a>.</p>

</div>
</div>

### readLockFile() {#ac9680279a64003d185d4c87a009de9a2}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">std::optional&lt; std::pair&lt; std::string, int &gt; &gt; LockFileManager::readLockFile (<a href="/web-llvm/docs/api/classes/llvm/stringref">StringRef</a> LockFileName)</td>
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

<p>Attempt to read the lock file with the given name, if it exists.</p>


<dl class="doxyParamsList">
<dt class="doxyParamsTableTitle">Parameters</dt>
<dd>
<table class="doxyParamsTable">
<tr class="doxyParamItem">
<td class="doxyParamItemName">LockFileName</td>
<td class="doxyParamItemDescription"><p>The name of the lock file to read.</p></td>
</tr>
</table>
</dd>
</dl>

<dl class="doxySectionUser">
<dt>Returns</dt>
<dd><p>The process <a href="/web-llvm/docs/api/namespaces/llvm/callingconv/#abdf8cf606905c10634e831390981b0ed">ID</a> of the process that owns this lock file</p></dd>
</dl>


<p>Declaration at line 65 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/support/lockfilemanager-h">LockFileManager.h</a>, definition at line 55 of file <a href="/web-llvm/docs/api/files/lib/lib/support/lockfilemanager-cpp">LockFileManager.cpp</a>.</p>

</div>
</div>

</div>

<hr/>

The documentation for this class was generated from the following files:

<ul>
<li><a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/support/lockfilemanager-h">LockFileManager.h</a></li>
<li><a href="/web-llvm/docs/api/files/lib/lib/support/lockfilemanager-cpp">LockFileManager.cpp</a></li>
</ul>

<hr/>

<p class="doxyGeneratedBy">Generated via <a href="https://github.com/xpack/doxygen2docusaurus">doxygen2docusaurus</a> by <a href="https://www.doxygen.nl">Doxygen</a> 1.14.0.</p>

</div>
