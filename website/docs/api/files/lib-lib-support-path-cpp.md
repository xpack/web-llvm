---

# DO NOT EDIT!
# Automatically generated via doxygen2docusaurus by Doxygen.

slug: /api/files/lib/lib/support/path-cpp
custom_edit_url: null
toc_max_heading_level: 4
keywords:
  - doxygen
  - reference
  - file

---

<div class="doxyPage">

# The `Path.cpp` File Reference



## Included Headers

<div class="doxyIncludesList">#include "<a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/support/path-h">llvm/Support/Path.h</a>"
#include "<a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/adt/arrayref-h">llvm/ADT/ArrayRef.h</a>"
#include "<a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/adt/scopeexit-h">llvm/ADT/ScopeExit.h</a>"
#include "<a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/adt/stringextras-h">llvm/ADT/StringExtras.h</a>"
#include "llvm/Config/config.h"
#include "llvm/Config/llvm-config.h"
#include "<a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/support/errc-h">llvm/Support/Errc.h</a>"
#include "<a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/support/errorhandling-h">llvm/Support/ErrorHandling.h</a>"
#include "<a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/support/filesystem-h">llvm/Support/FileSystem.h</a>"
#include "<a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/support/process-h">llvm/Support/Process.h</a>"
#include "<a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/support/signals-h">llvm/Support/Signals.h</a>"
#include &lt;cctype&gt;
#include &lt;unistd.h&gt;
#include "Unix/Path.inc"
</div>

## Namespaces Index

<table class="doxyMembersIndex">

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">namespace</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="/web-llvm/docs/api/namespaces/anonymous-path-cpp-">anonymous{Path.cpp}</a></td>
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

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">namespace</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="/web-llvm/docs/api/namespaces/llvm/sys">sys</a></td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">namespace</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="/web-llvm/docs/api/namespaces/llvm/sys/path">path</a></td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">namespace</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="/web-llvm/docs/api/namespaces/llvm/sys/fs">fs</a></td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="/web-llvm/docs/api/classes/anonymous-path-cpp-/stringref">StringRef</a></td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p><a href="/web-llvm/docs/api/classes/anonymous-path-cpp-/stringref">StringRef</a> - Represent a constant reference to a string, i.e. <a href="/web-llvm/docs/api/classes/anonymous-path-cpp-/stringref/#details">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

</table>

## Enumerations Index

<table class="doxyMembersIndex">

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">enum</td>
<td class="doxyMemberIndexItemName" align="left" valign="top">FSEntity { <a href="#a91338f0c7a4d528f3cfcbf0a350e1708">...</a> }</td>
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

## Functions Index

<table class="doxyMembersIndex">

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">static std::error_code</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a29c8f00b8e38e6ff83c39923934de954">createUniqueEntity</a> (const Twine &amp;Model, int &amp;ResultFD, SmallVectorImpl&lt; char &gt; &amp;ResultPath, bool MakeAbsolute, FSEntity Type, sys::fs::OpenFlags Flags=sys::fs::OF_None, unsigned Mode=0)</td>
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

## Enumerations

### FSEntity {#a91338f0c7a4d528f3cfcbf0a350e1708}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">enum FSEntity </td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">


<dl class="doxyEnumList">
<dt class="doxyEnumTableTitle">Enumeration values</dt>
<dd>
<table class="doxyEnumTable">

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">FS_Dir<a id="a91338f0c7a4d528f3cfcbf0a350e1708a78aad3eff7e12dbc239f25f4dcd9746b"></a></td>
<td class="doxyEnumItemDescription"></td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">FS_File<a id="a91338f0c7a4d528f3cfcbf0a350e1708ada79551c1e938d96e9f7229ab55a1f84"></a></td>
<td class="doxyEnumItemDescription"></td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">FS_Name<a id="a91338f0c7a4d528f3cfcbf0a350e1708afaef3b894884346950bda46decc1803c"></a></td>
<td class="doxyEnumItemDescription"></td>
</tr>

</table>
</dd>
</dl>

<p>Definition at line 163 of file <a href="/web-llvm/docs/api/files/lib/lib/support/path-cpp">Path.cpp</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Functions

### createUniqueEntity() {#a29c8f00b8e38e6ff83c39923934de954}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">std::error_code createUniqueEntity (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/twine">Twine</a> &amp; Model, int &amp; ResultFD, <a href="/web-llvm/docs/api/classes/llvm/smallvectorimpl">SmallVectorImpl</a>&lt; char &gt; &amp; ResultPath, bool MakeAbsolute, <a href="#a91338f0c7a4d528f3cfcbf0a350e1708">FSEntity</a> Type, <a href="/web-llvm/docs/api/namespaces/llvm/sys/fs/#a662978c0cdf81de0d448032f142a3695">sys::fs::OpenFlags</a> Flags=sys::fs::OF_None, unsigned Mode=0)</td>
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



<p>Definition at line 170 of file <a href="/web-llvm/docs/api/files/lib/lib/support/path-cpp">Path.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/namespaces/llvm/sys/fs/#a592297dd80c13e993380e2bf972721ac">llvm::sys::fs::access</a>, <a href="/web-llvm/docs/api/classes/llvm/smallvectortemplatecommon/#a8a045d250952c0867382a9840ee18fdf">llvm::SmallVectorTemplateCommon&lt; T, typename &gt;::begin</a>, <a href="/web-llvm/docs/api/namespaces/llvm/sys/fs/#a93918b3a9b70253cd229fc5864884f58af22f16292faab0a453a71f72efe29c83">llvm::sys::fs::CD_CreateNew</a>, <a href="/web-llvm/docs/api/namespaces/llvm/sys/fs/#a8ba6f296474de05208b3e1cffe779120">llvm::sys::fs::create_directory</a>, <a href="/web-llvm/docs/api/namespaces/llvm/sys/fs/#aa37537b95a42a73ea04d8dd2803378da">llvm::sys::fs::createUniquePath</a>, <a href="/web-llvm/docs/api/namespaces/llvm/sys/fs/#ab3cde71d019a4b19046fa286973656ebadd7f7c3323353f547eb98a8efba37ed0">llvm::sys::fs::Exist</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a59739a4f15fb2ec57a6b7fcfe938546ba41edf636e3c7b59f797348fc58472258">llvm::file_exists</a>, <a href="#a91338f0c7a4d528f3cfcbf0a350e1708a78aad3eff7e12dbc239f25f4dcd9746b">FS_Dir</a>, <a href="#a91338f0c7a4d528f3cfcbf0a350e1708ada79551c1e938d96e9f7229ab55a1f84">FS_File</a>, <a href="#a91338f0c7a4d528f3cfcbf0a350e1708afaef3b894884346950bda46decc1803c">FS_Name</a>, <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/support/errorhandling-h/#ace243f5c25697a1107cce46626b3dc94">llvm_unreachable</a>, <a href="/web-llvm/docs/api/files/lib/lib/codegen/regallocevictionadvisor-cpp/#aef71c4b21823f236e70cc6d62375adcd">Mode</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a59739a4f15fb2ec57a6b7fcfe938546ba2e70fc89b08f26fa3fc77694c91e8f7a">llvm::no_such_file_or_directory</a>, <a href="/web-llvm/docs/api/namespaces/llvm/sys/fs/#a662978c0cdf81de0d448032f142a3695a8ae6a0a158ab49e5bbe92cbc2cabcbcd">llvm::sys::fs::OF_None</a>, <a href="/web-llvm/docs/api/namespaces/llvm/sys/fs/#a1ec43af01f0dd39a262169ec4109692b">llvm::sys::fs::openFileForReadWrite</a> and <a href="/web-llvm/docs/api/namespaces/llvm/#a59739a4f15fb2ec57a6b7fcfe938546bae8ee838822072f02738dbd7d97ea03fc">llvm::permission_denied</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/namespaces/llvm/sys/fs/#afa70d6de13d68c2e91c3a845211bb49a">llvm::sys::fs::createTemporaryFile</a>, <a href="/web-llvm/docs/api/namespaces/llvm/sys/fs/#abf677459f5137cfb49f6d81b27ea54a1">llvm::sys::fs::createUniqueDirectory</a>, <a href="/web-llvm/docs/api/namespaces/llvm/sys/fs/#a7efe580e0855b9d68d0b884b79ebf955">llvm::sys::fs::createUniqueFile</a> and <a href="/web-llvm/docs/api/namespaces/llvm/sys/fs/#a444469c1ee24eddb7c1efd5067a0a86f">llvm::sys::fs::getPotentiallyUniqueFileName</a>.</p>

</div>
</div>

</div>

<hr/>

<p class="doxyGeneratedBy">Generated via <a href="https://github.com/xpack/doxygen2docusaurus">doxygen2docusaurus</a> by <a href="https://www.doxygen.nl">Doxygen</a> 1.15.0.</p>

</div>
