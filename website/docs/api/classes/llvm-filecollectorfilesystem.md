---

# DO NOT EDIT!
# Automatically generated via doxygen2docusaurus by Doxygen.

slug: /api/classes/llvm/filecollectorfilesystem
custom_edit_url: null
toc_max_heading_level: 4
keywords:
  - doxygen
  - reference
  - class

---

<div class="doxyPage">

# `FileCollectorFileSystem` Class



## Declaration

<div class="doxyDeclaration">
class llvm::FileCollectorFileSystem { ... }
</div>

## Base class

<table class="doxyMembersIndex">

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

</table>

## Public Constructors Index

<table class="doxyMembersIndex">

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a1b9cd84418052f9859f5b73ed2d27d09">FileCollectorFileSystem</a> (IntrusiveRefCntPtr&lt; vfs::FileSystem &gt; FS, std::shared_ptr&lt; FileCollector &gt; Collector)</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/erroror">llvm::ErrorOr</a>&lt; <a href="/web-llvm/docs/api/classes/llvm/vfs/status">llvm::vfs::Status</a> &gt;</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ab286ea390bc08a54b0ae98c9d31f40a6">status</a> (const Twine &amp;Path) override</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Get the status of the entry at <span class="doxyComputerOutput">Path</span>, if one exists. <a href="#ab286ea390bc08a54b0ae98c9d31f40a6">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/erroror">llvm::ErrorOr</a>&lt; std::unique_ptr&lt; <a href="/web-llvm/docs/api/classes/llvm/vfs/file">llvm::vfs::File</a> &gt; &gt;</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#abd068075d05331fd4020773fc6230ffd">openFileForRead</a> (const Twine &amp;Path) override</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Get a <span class="doxyComputerOutput">File</span> object for the text file at <span class="doxyComputerOutput">Path</span>, if one exists. <a href="#abd068075d05331fd4020773fc6230ffd">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/vfs/directory-iterator">llvm::vfs::directory_iterator</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#abf9125ebcf588399a8812b85911ba2f4">dir_begin</a> (const llvm::Twine &amp;Dir, std::error_code &amp;EC) override</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Get a directory_iterator for <span class="doxyComputerOutput">Dir</span>. <a href="#abf9125ebcf588399a8812b85911ba2f4">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">std::error_code</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a433f751b01af0722012a9d12ae43b6e6">getRealPath</a> (const Twine &amp;Path, SmallVectorImpl&lt; char &gt; &amp;Output) override</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Gets real path of <span class="doxyComputerOutput">Path</span> e.g. <a href="#a433f751b01af0722012a9d12ae43b6e6">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">std::error_code</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#aa5edb1c03911003c4c9a6d15762544d5">isLocal</a> (const Twine &amp;Path, bool &amp;Result) override</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Is the file mounted on a local filesystem? <a href="#aa5edb1c03911003c4c9a6d15762544d5">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/erroror">llvm::ErrorOr</a>&lt; std::string &gt;</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ad1c4394d96a02f08b2dae25fbfa50a34">getCurrentWorkingDirectory</a> () const override</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Get the working directory of this file system. <a href="#ad1c4394d96a02f08b2dae25fbfa50a34">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">std::error_code</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a52cfcad492860b5d9d3b2e5bbd2c1989">setCurrentWorkingDirectory</a> (const llvm::Twine &amp;Path) override</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Set the working directory. <a href="#a52cfcad492860b5d9d3b2e5bbd2c1989">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

</table>

## Private Member Attributes Index

<table class="doxyMembersIndex">

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/intrusiverefcntptr">IntrusiveRefCntPtr</a>&lt; <a href="/web-llvm/docs/api/classes/llvm/vfs/filesystem">vfs::FileSystem</a> &gt;</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a2f298996a2363b3a36ba0c2a6a28c866">FS</a></td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">std::shared_ptr&lt; <a href="/web-llvm/docs/api/classes/llvm/filecollector">FileCollector</a> &gt;</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a618b3b0b6af747d71362a8951309d1df">Collector</a></td>
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


<p>Definition at line 257 of file <a href="/web-llvm/docs/api/files/lib/lib/support/filecollector-cpp">FileCollector.cpp</a>.</p>


<div class="doxySectionDef">

## Public Constructors

### FileCollectorFileSystem() {#a1b9cd84418052f9859f5b73ed2d27d09}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">llvm::FileCollectorFileSystem::FileCollectorFileSystem (<a href="/web-llvm/docs/api/classes/llvm/intrusiverefcntptr">IntrusiveRefCntPtr</a>&lt; <a href="/web-llvm/docs/api/classes/llvm/vfs/filesystem">vfs::FileSystem</a> &gt; FS, std::shared_ptr&lt; <a href="/web-llvm/docs/api/classes/llvm/filecollector">FileCollector</a> &gt; Collector)</td>
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



<p>Definition at line 259 of file <a href="/web-llvm/docs/api/files/lib/lib/support/filecollector-cpp">FileCollector.cpp</a>.</p>


<p>Reference <a href="/web-llvm/docs/api/namespaces/llvm/#abfc9c7ecf70f66901e439f7c04ef3dbb">llvm::move</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Public Member Functions

### dir\_begin() {#abf9125ebcf588399a8812b85911ba2f4}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">llvm::vfs::directory_iterator llvm::FileCollectorFileSystem::dir_begin (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/twine">llvm::Twine</a> &amp; Dir, std::error_code &amp; EC)</td>
</tr>
</table>
</td>
<td class="doxyMemberLabelsRight">
<span class="doxyMemberLabels">
<span class="doxyMemberLabel inline">inline</span>
<span class="doxyMemberLabel virtual">virtual</span>
</span>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Get a directory_iterator for <span class="doxyComputerOutput">Dir</span>.</p>



:::info
<p>The 'end' iterator is directory_iterator().</p>
:::


<p>Definition at line 278 of file <a href="/web-llvm/docs/api/files/lib/lib/support/filecollector-cpp">FileCollector.cpp</a>.</p>

</div>
</div>

### getCurrentWorkingDirectory() {#ad1c4394d96a02f08b2dae25fbfa50a34}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">llvm::ErrorOr&lt; std::string &gt; llvm::FileCollectorFileSystem::getCurrentWorkingDirectory ()</td>
</tr>
</table>
</td>
<td class="doxyMemberLabelsRight">
<span class="doxyMemberLabels">
<span class="doxyMemberLabel inline">inline</span>
<span class="doxyMemberLabel virtual">virtual</span>
</span>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Get the working directory of this file system.</p>

<p>Definition at line 298 of file <a href="/web-llvm/docs/api/files/lib/lib/support/filecollector-cpp">FileCollector.cpp</a>.</p>

</div>
</div>

### getRealPath() {#a433f751b01af0722012a9d12ae43b6e6}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">std::error_code llvm::FileCollectorFileSystem::getRealPath (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/twine">Twine</a> &amp; Path, <a href="/web-llvm/docs/api/classes/llvm/smallvectorimpl">SmallVectorImpl</a>&lt; char &gt; &amp; Output)</td>
</tr>
</table>
</td>
<td class="doxyMemberLabelsRight">
<span class="doxyMemberLabels">
<span class="doxyMemberLabel inline">inline</span>
<span class="doxyMemberLabel virtual">virtual</span>
</span>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Gets real path of <span class="doxyComputerOutput">Path</span> e.g.</p>


<p>collapse all . and .. patterns, resolve symlinks. For real file system, this uses <span class="doxyComputerOutput"><a href="/web-llvm/docs/api/namespaces/llvm/sys/fs/#a2363fbfbd0a348f5d81fc3d3223ecae3">llvm::sys::fs::real_path</a></span>. This returns <a href="/web-llvm/docs/api/namespaces/llvm/#a59739a4f15fb2ec57a6b7fcfe938546ba8344b3d509942f035d5e303022f9b986">errc::operation_not_permitted</a> if not implemented by subclass.</p>


<p>Definition at line 283 of file <a href="/web-llvm/docs/api/files/lib/lib/support/filecollector-cpp">FileCollector.cpp</a>.</p>


<p>Reference <a href="/web-llvm/docs/api/classes/llvm/smallvectortemplatecommon/#a1c479a8c434377c2b8cb056bdfdfc201">llvm::SmallVectorTemplateCommon&lt; T, typename &gt;::size</a>.</p>

</div>
</div>

### isLocal() {#aa5edb1c03911003c4c9a6d15762544d5}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">std::error_code llvm::FileCollectorFileSystem::isLocal (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/twine">Twine</a> &amp; Path, bool &amp; Result)</td>
</tr>
</table>
</td>
<td class="doxyMemberLabelsRight">
<span class="doxyMemberLabels">
<span class="doxyMemberLabel inline">inline</span>
<span class="doxyMemberLabel virtual">virtual</span>
</span>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Is the file mounted on a local filesystem?</p>

<p>Definition at line 294 of file <a href="/web-llvm/docs/api/files/lib/lib/support/filecollector-cpp">FileCollector.cpp</a>.</p>

</div>
</div>

### openFileForRead() {#abd068075d05331fd4020773fc6230ffd}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">llvm::ErrorOr&lt; std::unique_ptr&lt; llvm::vfs::File &gt; &gt; llvm::FileCollectorFileSystem::openFileForRead (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/twine">Twine</a> &amp; Path)</td>
</tr>
</table>
</td>
<td class="doxyMemberLabelsRight">
<span class="doxyMemberLabels">
<span class="doxyMemberLabel inline">inline</span>
<span class="doxyMemberLabel virtual">virtual</span>
</span>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Get a <span class="doxyComputerOutput">File</span> object for the text file at <span class="doxyComputerOutput">Path</span>, if one exists.</p>

<p>Definition at line 271 of file <a href="/web-llvm/docs/api/files/lib/lib/support/filecollector-cpp">FileCollector.cpp</a>.</p>

</div>
</div>

### setCurrentWorkingDirectory() {#a52cfcad492860b5d9d3b2e5bbd2c1989}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">std::error_code llvm::FileCollectorFileSystem::setCurrentWorkingDirectory (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/twine">llvm::Twine</a> &amp; Path)</td>
</tr>
</table>
</td>
<td class="doxyMemberLabelsRight">
<span class="doxyMemberLabels">
<span class="doxyMemberLabel inline">inline</span>
<span class="doxyMemberLabel virtual">virtual</span>
</span>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Set the working directory.</p>


<p>This will affect all following operations on this file system and may propagate down for nested file systems.</p>


<p>Definition at line 302 of file <a href="/web-llvm/docs/api/files/lib/lib/support/filecollector-cpp">FileCollector.cpp</a>.</p>

</div>
</div>

### status() {#ab286ea390bc08a54b0ae98c9d31f40a6}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">llvm::ErrorOr&lt; llvm::vfs::Status &gt; llvm::FileCollectorFileSystem::status (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/twine">Twine</a> &amp; Path)</td>
</tr>
</table>
</td>
<td class="doxyMemberLabelsRight">
<span class="doxyMemberLabels">
<span class="doxyMemberLabel inline">inline</span>
<span class="doxyMemberLabel virtual">virtual</span>
</span>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Get the status of the entry at <span class="doxyComputerOutput">Path</span>, if one exists.</p>

<p>Definition at line 263 of file <a href="/web-llvm/docs/api/files/lib/lib/support/filecollector-cpp">FileCollector.cpp</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Private Member Attributes

### Collector {#a618b3b0b6af747d71362a8951309d1df}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">std::shared_ptr&lt;FileCollector&gt; llvm::FileCollectorFileSystem::Collector</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 308 of file <a href="/web-llvm/docs/api/files/lib/lib/support/filecollector-cpp">FileCollector.cpp</a>.</p>

</div>
</div>

### FS {#a2f298996a2363b3a36ba0c2a6a28c866}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">IntrusiveRefCntPtr&lt;vfs::FileSystem&gt; llvm::FileCollectorFileSystem::FS</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 307 of file <a href="/web-llvm/docs/api/files/lib/lib/support/filecollector-cpp">FileCollector.cpp</a>.</p>

</div>
</div>

</div>

<hr/>

The documentation for this class was generated from the following file:

<ul>
<li><a href="/web-llvm/docs/api/files/lib/lib/support/filecollector-cpp">FileCollector.cpp</a></li>
</ul>

<hr/>

<p class="doxyGeneratedBy">Generated via <a href="https://github.com/xpack/doxygen2docusaurus">doxygen2docusaurus</a> by <a href="https://www.doxygen.nl">Doxygen</a> 1.15.0.</p>

</div>
