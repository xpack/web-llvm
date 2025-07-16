---

# DO NOT EDIT!
# Automatically generated via doxygen2docusaurus by Doxygen.

slug: /api/structs/llvm/pgooptions
custom_edit_url: null
toc_max_heading_level: 4
keywords:
  - doxygen
  - reference
  - struct

---

<div class="doxyPage">

# The `PGOOptions` Struct Reference

<p>A struct capturing PGO tunables. <a href="#details">More...</a></p>

## Declaration

<div class="doxyDeclaration">
struct llvm::PGOOptions { ... }
</div>

## Included Headers

<div class="doxyIncludesList">#include "<a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/support/pgooptions-h">llvm/Support/PGOOptions.h</a>"
</div>

## Enumerations Index

<table class="doxyMembersIndex">

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">enum</td>
<td class="doxyMemberIndexItemName" align="left" valign="top">PGOAction { <a href="#a13bd589bcabdfc073bac5711f76dd2b6">...</a> }</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">enum</td>
<td class="doxyMemberIndexItemName" align="left" valign="top">CSPGOAction { <a href="#acf3f319824303e495d7326e35538b250">...</a> }</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">enum class</td>
<td class="doxyMemberIndexItemName" align="left" valign="top">ColdFuncOpt { <a href="#af4530e1e6451953635146d6119977bb2">...</a> }</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#abecf1367ac7d47f476843266fdd52746">PGOOptions</a> (std::string ProfileFile, std::string CSProfileGenFile, std::string ProfileRemappingFile, std::string MemoryProfile, IntrusiveRefCntPtr&lt; vfs::FileSystem &gt; FS, PGOAction Action=NoAction, CSPGOAction CSAction=NoCSAction, ColdFuncOpt ColdType=ColdFuncOpt::Default, bool DebugInfoForProfiling=false, bool PseudoProbeForProfiling=false, bool AtomicCounterUpdate=false)</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a7db4b6526e80b48898fbfff1d876c124">PGOOptions</a> (const PGOOptions &amp;)</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#afe4d2ed68c8aa5bfc987dec67c94441d">~PGOOptions</a> ()</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/structs/llvm/pgooptions">PGOOptions</a> &amp;</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a715c658b021e474d28ba09e9ea76d8aa">operator=</a> (const PGOOptions &amp;)</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a1dc698e393d30e1f0dec08b7d7b949ad">ProfileFile</a></td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a202eacc3e4a07d9fa906a9a6b1c14994">CSProfileGenFile</a></td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ac406114c9c061be62a7c3d92628c401e">ProfileRemappingFile</a></td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a1656a91be517410c1276796f8545fe17">MemoryProfile</a></td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="#a13bd589bcabdfc073bac5711f76dd2b6">PGOAction</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a397f21f26d84b8b96853a2cfb8786463">Action</a></td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="#acf3f319824303e495d7326e35538b250">CSPGOAction</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ac60e6389adf6ca172208e0bd19a235b3">CSAction</a></td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="#af4530e1e6451953635146d6119977bb2">ColdFuncOpt</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a4a0b041aa52bfeb36c2005bfc100d47d">ColdOptType</a></td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a146dd98d3a2ece9d9c3bbf32bbf99d14">DebugInfoForProfiling</a></td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#afc6f95edb784741b9d326d83632ca8f0">PseudoProbeForProfiling</a></td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#acb180480fa9edd1780c80c0c78df77f9">AtomicCounterUpdate</a></td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/intrusiverefcntptr">IntrusiveRefCntPtr</a>&lt; <a href="/web-llvm/docs/api/classes/llvm/vfs/filesystem">vfs::FileSystem</a> &gt;</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a9bc64b487f8d2dab8d560849bf965b5d">FS</a></td>
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

<p>A struct capturing PGO tunables.</p>

<p>Definition at line 27 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/support/pgooptions-h">PGOOptions.h</a>.</p>


<div class="doxySectionDef">

## Enumerations

### ColdFuncOpt {#af4530e1e6451953635146d6119977bb2}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">enum class llvm::PGOOptions::ColdFuncOpt </td>
</tr>
</table>
</td>
<td class="doxyMemberLabelsRight">
<span class="doxyMemberLabels">
<span class="doxyMemberLabel strong">strong</span>
</span>
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
<td class="doxyEnumItemName">Default<a id="af4530e1e6451953635146d6119977bb2a7a1920d61156abc05a60135aefe8bc67"></a></td>
<td class="doxyEnumItemDescription"></td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">OptSize<a id="af4530e1e6451953635146d6119977bb2a3976101903526c8f3dc93e91fb094f7e"></a></td>
<td class="doxyEnumItemDescription"></td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">MinSize<a id="af4530e1e6451953635146d6119977bb2a4ec7376ba0b26f029ef85de800c42c43"></a></td>
<td class="doxyEnumItemDescription"></td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">OptNone<a id="af4530e1e6451953635146d6119977bb2af826f7065d147888b6ff27476ed52c40"></a></td>
<td class="doxyEnumItemDescription"></td>
</tr>

</table>
</dd>
</dl>

<p>Definition at line 30 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/support/pgooptions-h">PGOOptions.h</a>.</p>

</div>
</div>

### CSPGOAction {#acf3f319824303e495d7326e35538b250}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">enum llvm::PGOOptions::CSPGOAction </td>
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
<td class="doxyEnumItemName">NoCSAction<a id="acf3f319824303e495d7326e35538b250a3f7a9bea8b72b3ad453ccf95bcbca22b"></a></td>
<td class="doxyEnumItemDescription"></td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">CSIRInstr<a id="acf3f319824303e495d7326e35538b250ad626f6abde9ca8fb0a8e97125114f11c"></a></td>
<td class="doxyEnumItemDescription"></td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">CSIRUse<a id="acf3f319824303e495d7326e35538b250a0003b9f9d3be4b2a2bef9c7ceec1d77b"></a></td>
<td class="doxyEnumItemDescription"></td>
</tr>

</table>
</dd>
</dl>

<p>Definition at line 29 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/support/pgooptions-h">PGOOptions.h</a>.</p>

</div>
</div>

### PGOAction {#a13bd589bcabdfc073bac5711f76dd2b6}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">enum llvm::PGOOptions::PGOAction </td>
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
<td class="doxyEnumItemName">NoAction<a id="a13bd589bcabdfc073bac5711f76dd2b6a5c70c58ba2d09ff71654a055ea617020"></a></td>
<td class="doxyEnumItemDescription"></td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">IRInstr<a id="a13bd589bcabdfc073bac5711f76dd2b6a0ee4f7584b41e663a274753a6e9a9c34"></a></td>
<td class="doxyEnumItemDescription"></td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">IRUse<a id="a13bd589bcabdfc073bac5711f76dd2b6a0c03d67d2ee41484066dade662f2fca5"></a></td>
<td class="doxyEnumItemDescription"></td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">SampleUse<a id="a13bd589bcabdfc073bac5711f76dd2b6a9cbf1cb1b0731fc75926a6930592968a"></a></td>
<td class="doxyEnumItemDescription"></td>
</tr>

</table>
</dd>
</dl>

<p>Definition at line 28 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/support/pgooptions-h">PGOOptions.h</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Public Constructors

### PGOOptions() {#abecf1367ac7d47f476843266fdd52746}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">PGOOptions::PGOOptions (std::string ProfileFile, std::string CSProfileGenFile, std::string ProfileRemappingFile, std::string MemoryProfile, <a href="/web-llvm/docs/api/classes/llvm/intrusiverefcntptr">IntrusiveRefCntPtr</a>&lt; <a href="/web-llvm/docs/api/classes/llvm/vfs/filesystem">vfs::FileSystem</a> &gt; FS, <a href="#a13bd589bcabdfc073bac5711f76dd2b6">PGOAction</a> Action=<a href="#a13bd589bcabdfc073bac5711f76dd2b6a5c70c58ba2d09ff71654a055ea617020">NoAction</a>, <a href="#acf3f319824303e495d7326e35538b250">CSPGOAction</a> CSAction=<a href="#acf3f319824303e495d7326e35538b250a3f7a9bea8b72b3ad453ccf95bcbca22b">NoCSAction</a>, <a href="#af4530e1e6451953635146d6119977bb2">ColdFuncOpt</a> ColdType=<a href="#af4530e1e6451953635146d6119977bb2a7a1920d61156abc05a60135aefe8bc67">ColdFuncOpt::Default</a>, bool DebugInfoForProfiling=false, bool PseudoProbeForProfiling=false, bool AtomicCounterUpdate=false)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Declaration at line 31 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/support/pgooptions-h">PGOOptions.h</a>, definition at line 14 of file <a href="/web-llvm/docs/api/files/lib/lib/support/pgooptions-cpp">PGOOptions.cpp</a>.</p>


<p>References <a href="#a397f21f26d84b8b96853a2cfb8786463">Action</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/silowercontrolflow-cpp/#a4868c5d81c5ccc98c47aeab6244346a0">assert</a>, <a href="#acb180480fa9edd1780c80c0c78df77f9">AtomicCounterUpdate</a>, <a href="#a4a0b041aa52bfeb36c2005bfc100d47d">ColdOptType</a>, <a href="#ac60e6389adf6ca172208e0bd19a235b3">CSAction</a>, <a href="#acf3f319824303e495d7326e35538b250ad626f6abde9ca8fb0a8e97125114f11c">CSIRInstr</a>, <a href="#acf3f319824303e495d7326e35538b250a0003b9f9d3be4b2a2bef9c7ceec1d77b">CSIRUse</a>, <a href="#a202eacc3e4a07d9fa906a9a6b1c14994">CSProfileGenFile</a>, <a href="#a146dd98d3a2ece9d9c3bbf32bbf99d14">DebugInfoForProfiling</a>, <a href="#a9bc64b487f8d2dab8d560849bf965b5d">FS</a>, <a href="#a13bd589bcabdfc073bac5711f76dd2b6a0ee4f7584b41e663a274753a6e9a9c34">IRInstr</a>, <a href="#a13bd589bcabdfc073bac5711f76dd2b6a0c03d67d2ee41484066dade662f2fca5">IRUse</a>, <a href="#a1656a91be517410c1276796f8545fe17">MemoryProfile</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#abfc9c7ecf70f66901e439f7c04ef3dbb">llvm::move</a>, <a href="#a13bd589bcabdfc073bac5711f76dd2b6a5c70c58ba2d09ff71654a055ea617020">NoAction</a>, <a href="#acf3f319824303e495d7326e35538b250a3f7a9bea8b72b3ad453ccf95bcbca22b">NoCSAction</a>, <a href="#a1dc698e393d30e1f0dec08b7d7b949ad">ProfileFile</a>, <a href="#ac406114c9c061be62a7c3d92628c401e">ProfileRemappingFile</a>, <a href="#afc6f95edb784741b9d326d83632ca8f0">PseudoProbeForProfiling</a> and <a href="#a13bd589bcabdfc073bac5711f76dd2b6a9cbf1cb1b0731fc75926a6930592968a">SampleUse</a>.</p>


<p>Referenced by <a href="#a715c658b021e474d28ba09e9ea76d8aa">operator=</a> and <a href="#a7db4b6526e80b48898fbfff1d876c124">PGOOptions</a>.</p>

</div>
</div>

### PGOOptions() {#a7db4b6526e80b48898fbfff1d876c124}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">PGOOptions::PGOOptions (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/structs/llvm/pgooptions">PGOOptions</a> &amp;)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 39 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/support/pgooptions-h">PGOOptions.h</a>.</p>


<p>Reference <a href="#abecf1367ac7d47f476843266fdd52746">PGOOptions</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Public Destructor

### \~PGOOptions() {#afe4d2ed68c8aa5bfc987dec67c94441d}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">PGOOptions::~PGOOptions ()</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 40 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/support/pgooptions-h">PGOOptions.h</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Public Operators

### operator=() {#a715c658b021e474d28ba09e9ea76d8aa}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">PGOOptions &amp; PGOOptions::operator= (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/structs/llvm/pgooptions">PGOOptions</a> &amp; O)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 41 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/support/pgooptions-h">PGOOptions.h</a>.</p>


<p>Reference <a href="#abecf1367ac7d47f476843266fdd52746">PGOOptions</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Public Member Attributes

### Action {#a397f21f26d84b8b96853a2cfb8786463}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">PGOAction llvm::PGOOptions::Action</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 47 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/support/pgooptions-h">PGOOptions.h</a>.</p>


<p>Referenced by <a href="#abecf1367ac7d47f476843266fdd52746">PGOOptions</a>.</p>

</div>
</div>

### AtomicCounterUpdate {#acb180480fa9edd1780c80c0c78df77f9}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool llvm::PGOOptions::AtomicCounterUpdate</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 52 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/support/pgooptions-h">PGOOptions.h</a>.</p>


<p>Referenced by <a href="#abecf1367ac7d47f476843266fdd52746">PGOOptions</a>.</p>

</div>
</div>

### ColdOptType {#a4a0b041aa52bfeb36c2005bfc100d47d}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">ColdFuncOpt llvm::PGOOptions::ColdOptType</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 49 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/support/pgooptions-h">PGOOptions.h</a>.</p>


<p>Referenced by <a href="#abecf1367ac7d47f476843266fdd52746">PGOOptions</a>.</p>

</div>
</div>

### CSAction {#ac60e6389adf6ca172208e0bd19a235b3}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">CSPGOAction llvm::PGOOptions::CSAction</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 48 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/support/pgooptions-h">PGOOptions.h</a>.</p>


<p>Referenced by <a href="#abecf1367ac7d47f476843266fdd52746">PGOOptions</a>.</p>

</div>
</div>

### CSProfileGenFile {#a202eacc3e4a07d9fa906a9a6b1c14994}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">std::string llvm::PGOOptions::CSProfileGenFile</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 44 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/support/pgooptions-h">PGOOptions.h</a>.</p>


<p>Referenced by <a href="#abecf1367ac7d47f476843266fdd52746">PGOOptions</a>.</p>

</div>
</div>

### DebugInfoForProfiling {#a146dd98d3a2ece9d9c3bbf32bbf99d14}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool llvm::PGOOptions::DebugInfoForProfiling</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 50 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/support/pgooptions-h">PGOOptions.h</a>.</p>


<p>Referenced by <a href="#abecf1367ac7d47f476843266fdd52746">PGOOptions</a>.</p>

</div>
</div>

### FS {#a9bc64b487f8d2dab8d560849bf965b5d}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">IntrusiveRefCntPtr&lt;vfs::FileSystem&gt; llvm::PGOOptions::FS</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 53 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/support/pgooptions-h">PGOOptions.h</a>.</p>


<p>Referenced by <a href="#abecf1367ac7d47f476843266fdd52746">PGOOptions</a>.</p>

</div>
</div>

### MemoryProfile {#a1656a91be517410c1276796f8545fe17}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">std::string llvm::PGOOptions::MemoryProfile</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 46 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/support/pgooptions-h">PGOOptions.h</a>.</p>


<p>Referenced by <a href="#abecf1367ac7d47f476843266fdd52746">PGOOptions</a>.</p>

</div>
</div>

### ProfileFile {#a1dc698e393d30e1f0dec08b7d7b949ad}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">std::string llvm::PGOOptions::ProfileFile</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 43 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/support/pgooptions-h">PGOOptions.h</a>.</p>


<p>Referenced by <a href="#abecf1367ac7d47f476843266fdd52746">PGOOptions</a>.</p>

</div>
</div>

### ProfileRemappingFile {#ac406114c9c061be62a7c3d92628c401e}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">std::string llvm::PGOOptions::ProfileRemappingFile</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 45 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/support/pgooptions-h">PGOOptions.h</a>.</p>


<p>Referenced by <a href="#abecf1367ac7d47f476843266fdd52746">PGOOptions</a>.</p>

</div>
</div>

### PseudoProbeForProfiling {#afc6f95edb784741b9d326d83632ca8f0}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool llvm::PGOOptions::PseudoProbeForProfiling</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 51 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/support/pgooptions-h">PGOOptions.h</a>.</p>


<p>Referenced by <a href="#abecf1367ac7d47f476843266fdd52746">PGOOptions</a>.</p>

</div>
</div>

</div>

<hr/>

The documentation for this struct was generated from the following files:

<ul>
<li><a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/support/pgooptions-h">PGOOptions.h</a></li>
<li><a href="/web-llvm/docs/api/files/lib/lib/support/pgooptions-cpp">PGOOptions.cpp</a></li>
</ul>

<hr/>

<p class="doxyGeneratedBy">Generated via <a href="https://github.com/xpack/doxygen2docusaurus">doxygen2docusaurus</a> by <a href="https://www.doxygen.nl">Doxygen</a> 1.15.0.</p>

</div>
