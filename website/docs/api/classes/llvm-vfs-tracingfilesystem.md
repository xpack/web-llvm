---

# DO NOT EDIT!
# Automatically generated via doxygen2docusaurus by Doxygen.

slug: /api/classes/llvm/vfs/tracingfilesystem
custom_edit_url: null
toc_max_heading_level: 4
keywords:
  - doxygen
  - reference
  - class

---

<div class="doxyPage">

# `TracingFileSystem` Class

<p><a href="/web-llvm/docs/api/classes/llvm/vfs/file">File</a> system that tracks the number of calls to the underlying file system. <a href="#details">More...</a></p>

## Declaration

<div class="doxyDeclaration">
class llvm::vfs::TracingFileSystem { ... }
</div>

## Included Headers

<div class="doxyIncludesList">#include "<a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/support/virtualfilesystem-h">llvm/Support/VirtualFileSystem.h</a>"
</div>

## Base class

<table class="doxyMembersIndex">

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">class</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/rttiextends">RTTIExtends&lt;ThisT, ParentT, ParentTs&gt;</a></td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Inheritance utility for extensible RTTI. <a href="/web-llvm/docs/api/classes/llvm/rttiextends/#details">More...</a></p>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a2ca4181d77c0223e2f6057c1553a6988">TracingFileSystem</a> (llvm::IntrusiveRefCntPtr&lt; llvm::vfs::FileSystem &gt; FS)</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/erroror">ErrorOr</a>&lt; <a href="/web-llvm/docs/api/classes/llvm/vfs/status">Status</a> &gt;</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ac2187fbb2d8bec12a2720c71e16d1f0d">status</a> (const Twine &amp;Path) override</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/erroror">ErrorOr</a>&lt; std::unique_ptr&lt; <a href="/web-llvm/docs/api/classes/llvm/vfs/file">File</a> &gt; &gt;</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a67e40e195bff74dce84f813a0b28a143">openFileForRead</a> (const Twine &amp;Path) override</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/vfs/directory-iterator">directory_iterator</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a8a0fc3dae0f95f1b2d52e17365baf920">dir_begin</a> (const Twine &amp;Dir, std::error_code &amp;EC) override</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#afa4726a227bcd4283360710c30a89e36">getRealPath</a> (const Twine &amp;Path, SmallVectorImpl&lt; char &gt; &amp;Output) override</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">bool</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a07ee7e51f39261916d17c3b2e9d975cb">exists</a> (const Twine &amp;Path) override</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#acfb710f5331e1263fefa83266150e4a1">isLocal</a> (const Twine &amp;Path, bool &amp;Result) override</td>
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

## Protected Member Functions Index

<table class="doxyMembersIndex">

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">void</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#acb844eb6bc89340c1c01be7165e34d39">printImpl</a> (raw_ostream &amp;OS, PrintType Type, unsigned IndentLevel) const override</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">std::size_t</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ae0bf5bfbef74c7484ac9ddb7fff718ae">NumStatusCalls</a> = 0</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">std::size_t</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a7f92635c852320d89342e6b9bff1a6e8">NumOpenFileForReadCalls</a> = 0</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">std::size_t</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#adc9b192c32adbbb41348b58fc83dc072">NumDirBeginCalls</a> = 0</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">std::size_t</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#adf62777350f469bdb7d9dd4d284485d2">NumGetRealPathCalls</a> = 0</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">std::size_t</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a8baac6969b700d8fb08f793108b66ef8">NumExistsCalls</a> = 0</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">std::size_t</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a858f3f7d351e8ded5f1e537db6638b9c">NumIsLocalCalls</a> = 0</td>
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

## Public Static Attributes Index

<table class="doxyMembersIndex">

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">static <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> char</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a6275c96f7cfa18f51d5ec0ce6adde040">ID</a> = 0</td>
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

<p><a href="/web-llvm/docs/api/classes/llvm/vfs/file">File</a> system that tracks the number of calls to the underlying file system.</p>


<p>This is particularly useful when wrapped around <span class="doxyComputerOutput">RealFileSystem</span> to add lightweight tracking of expensive syscalls.</p>


<p>Definition at line 1151 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/support/virtualfilesystem-h">VirtualFileSystem.h</a>.</p>


<div class="doxySectionDef">

## Public Constructors

### TracingFileSystem() {#a2ca4181d77c0223e2f6057c1553a6988}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">llvm::vfs::TracingFileSystem::TracingFileSystem (<a href="/web-llvm/docs/api/classes/llvm/intrusiverefcntptr">llvm::IntrusiveRefCntPtr</a>&lt; <a href="/web-llvm/docs/api/classes/llvm/vfs/filesystem">llvm::vfs::FileSystem</a> &gt; FS)</td>
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



<p>Definition at line 1163 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/support/virtualfilesystem-h">VirtualFileSystem.h</a>.</p>


<p>Reference <a href="/web-llvm/docs/api/namespaces/llvm/#abfc9c7ecf70f66901e439f7c04ef3dbb">llvm::move</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Public Member Functions

### dir\_begin() {#a8a0fc3dae0f95f1b2d52e17365baf920}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">directory_iterator llvm::vfs::TracingFileSystem::dir_begin (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/twine">Twine</a> &amp; Dir, std::error_code &amp; EC)</td>
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



<p>Definition at line 1176 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/support/virtualfilesystem-h">VirtualFileSystem.h</a>.</p>


<p>References <a href="/web-llvm/docs/api/classes/llvm/vfs/proxyfilesystem/#a4bb4ce76862804877ef0b475e3ba5a60">llvm::vfs::ProxyFileSystem::dir_begin</a> and <a href="#adc9b192c32adbbb41348b58fc83dc072">NumDirBeginCalls</a>.</p>

</div>
</div>

### exists() {#a07ee7e51f39261916d17c3b2e9d975cb}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool llvm::vfs::TracingFileSystem::exists (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/twine">Twine</a> &amp; Path)</td>
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



<p>Definition at line 1187 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/support/virtualfilesystem-h">VirtualFileSystem.h</a>.</p>


<p>References <a href="/web-llvm/docs/api/classes/llvm/vfs/proxyfilesystem/#a6a9f05a5eb39fb29205ce7f14ec95fa3">llvm::vfs::ProxyFileSystem::exists</a> and <a href="#a8baac6969b700d8fb08f793108b66ef8">NumExistsCalls</a>.</p>

</div>
</div>

### getRealPath() {#afa4726a227bcd4283360710c30a89e36}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">std::error_code llvm::vfs::TracingFileSystem::getRealPath (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/twine">Twine</a> &amp; Path, <a href="/web-llvm/docs/api/classes/llvm/smallvectorimpl">SmallVectorImpl</a>&lt; char &gt; &amp; Output)</td>
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



<p>Definition at line 1181 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/support/virtualfilesystem-h">VirtualFileSystem.h</a>.</p>


<p>References <a href="/web-llvm/docs/api/classes/llvm/vfs/proxyfilesystem/#a4927b5d914cc479e16765fa99f8c592d">llvm::vfs::ProxyFileSystem::getRealPath</a> and <a href="#adf62777350f469bdb7d9dd4d284485d2">NumGetRealPathCalls</a>.</p>

</div>
</div>

### isLocal() {#acfb710f5331e1263fefa83266150e4a1}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">std::error_code llvm::vfs::TracingFileSystem::isLocal (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/twine">Twine</a> &amp; Path, bool &amp; Result)</td>
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



<p>Definition at line 1192 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/support/virtualfilesystem-h">VirtualFileSystem.h</a>.</p>


<p>References <a href="/web-llvm/docs/api/classes/llvm/vfs/proxyfilesystem/#a7c222f3375c08b10369608b541212ba7">llvm::vfs::ProxyFileSystem::isLocal</a> and <a href="#a858f3f7d351e8ded5f1e537db6638b9c">NumIsLocalCalls</a>.</p>

</div>
</div>

### openFileForRead() {#a67e40e195bff74dce84f813a0b28a143}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">ErrorOr&lt; std::unique_ptr&lt; File &gt; &gt; llvm::vfs::TracingFileSystem::openFileForRead (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/twine">Twine</a> &amp; Path)</td>
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



<p>Definition at line 1171 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/support/virtualfilesystem-h">VirtualFileSystem.h</a>.</p>


<p>References <a href="#a7f92635c852320d89342e6b9bff1a6e8">NumOpenFileForReadCalls</a> and <a href="/web-llvm/docs/api/classes/llvm/vfs/proxyfilesystem/#a1f45f206f0656d3a6302c7efae657b45">llvm::vfs::ProxyFileSystem::openFileForRead</a>.</p>

</div>
</div>

### status() {#ac2187fbb2d8bec12a2720c71e16d1f0d}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">ErrorOr&lt; Status &gt; llvm::vfs::TracingFileSystem::status (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/twine">Twine</a> &amp; Path)</td>
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



<p>Definition at line 1166 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/support/virtualfilesystem-h">VirtualFileSystem.h</a>.</p>


<p>References <a href="#ae0bf5bfbef74c7484ac9ddb7fff718ae">NumStatusCalls</a> and <a href="/web-llvm/docs/api/classes/llvm/vfs/proxyfilesystem/#a56478dc201c28e789ea153bedd26a031">llvm::vfs::ProxyFileSystem::status</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Protected Member Functions

### printImpl() {#acb844eb6bc89340c1c01be7165e34d39}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void TracingFileSystem::printImpl (<a href="/web-llvm/docs/api/classes/llvm/raw-ostream">raw_ostream</a> &amp; OS, PrintType Type, unsigned IndentLevel)</td>
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



<p>Declaration at line 1198 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/support/virtualfilesystem-h">VirtualFileSystem.h</a>, definition at line 2961 of file <a href="/web-llvm/docs/api/files/lib/lib/support/virtualfilesystem-cpp">VirtualFileSystem.cpp</a>.</p>


<p>References <a href="#adc9b192c32adbbb41348b58fc83dc072">NumDirBeginCalls</a>, <a href="#a8baac6969b700d8fb08f793108b66ef8">NumExistsCalls</a>, <a href="#adf62777350f469bdb7d9dd4d284485d2">NumGetRealPathCalls</a>, <a href="#a858f3f7d351e8ded5f1e537db6638b9c">NumIsLocalCalls</a>, <a href="#a7f92635c852320d89342e6b9bff1a6e8">NumOpenFileForReadCalls</a>, <a href="#ae0bf5bfbef74c7484ac9ddb7fff718ae">NumStatusCalls</a> and <a href="/web-llvm/docs/api/classes/llvm/type/#a91bbc1ac424839ba7e85d2d8542c288a">llvm::Type::print</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Public Member Attributes

### NumDirBeginCalls {#adc9b192c32adbbb41348b58fc83dc072}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">std::size_t llvm::vfs::TracingFileSystem::NumDirBeginCalls = 0</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 1158 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/support/virtualfilesystem-h">VirtualFileSystem.h</a>.</p>


<p>Referenced by <a href="#a8a0fc3dae0f95f1b2d52e17365baf920">dir_begin</a> and <a href="#acb844eb6bc89340c1c01be7165e34d39">printImpl</a>.</p>

</div>
</div>

### NumExistsCalls {#a8baac6969b700d8fb08f793108b66ef8}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">std::size_t llvm::vfs::TracingFileSystem::NumExistsCalls = 0</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 1160 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/support/virtualfilesystem-h">VirtualFileSystem.h</a>.</p>


<p>Referenced by <a href="#a07ee7e51f39261916d17c3b2e9d975cb">exists</a> and <a href="#acb844eb6bc89340c1c01be7165e34d39">printImpl</a>.</p>

</div>
</div>

### NumGetRealPathCalls {#adf62777350f469bdb7d9dd4d284485d2}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">std::size_t llvm::vfs::TracingFileSystem::NumGetRealPathCalls = 0</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 1159 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/support/virtualfilesystem-h">VirtualFileSystem.h</a>.</p>


<p>Referenced by <a href="#afa4726a227bcd4283360710c30a89e36">getRealPath</a> and <a href="#acb844eb6bc89340c1c01be7165e34d39">printImpl</a>.</p>

</div>
</div>

### NumIsLocalCalls {#a858f3f7d351e8ded5f1e537db6638b9c}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">std::size_t llvm::vfs::TracingFileSystem::NumIsLocalCalls = 0</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 1161 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/support/virtualfilesystem-h">VirtualFileSystem.h</a>.</p>


<p>Referenced by <a href="#acfb710f5331e1263fefa83266150e4a1">isLocal</a> and <a href="#acb844eb6bc89340c1c01be7165e34d39">printImpl</a>.</p>

</div>
</div>

### NumOpenFileForReadCalls {#a7f92635c852320d89342e6b9bff1a6e8}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">std::size_t llvm::vfs::TracingFileSystem::NumOpenFileForReadCalls = 0</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 1157 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/support/virtualfilesystem-h">VirtualFileSystem.h</a>.</p>


<p>Referenced by <a href="#a67e40e195bff74dce84f813a0b28a143">openFileForRead</a> and <a href="#acb844eb6bc89340c1c01be7165e34d39">printImpl</a>.</p>

</div>
</div>

### NumStatusCalls {#ae0bf5bfbef74c7484ac9ddb7fff718ae}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">std::size_t llvm::vfs::TracingFileSystem::NumStatusCalls = 0</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 1156 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/support/virtualfilesystem-h">VirtualFileSystem.h</a>.</p>


<p>Referenced by <a href="#acb844eb6bc89340c1c01be7165e34d39">printImpl</a> and <a href="#ac2187fbb2d8bec12a2720c71e16d1f0d">status</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Public Static Attributes

### ID {#a6275c96f7cfa18f51d5ec0ce6adde040}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">const char TracingFileSystem::ID = 0</td>
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



<p>Definition at line 1154 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/support/virtualfilesystem-h">VirtualFileSystem.h</a>.</p>

</div>
</div>

</div>

<hr/>

The documentation for this class was generated from the following files:

<ul>
<li><a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/support/virtualfilesystem-h">VirtualFileSystem.h</a></li>
<li><a href="/web-llvm/docs/api/files/lib/lib/support/virtualfilesystem-cpp">VirtualFileSystem.cpp</a></li>
</ul>

<hr/>

<p class="doxyGeneratedBy">Generated via <a href="https://xpack.github.io/doxygen2docusaurus">doxygen2docusaurus</a> 2.0.0 by <a href="https://www.doxygen.nl">Doxygen</a> 1.15.0.</p>

</div>
