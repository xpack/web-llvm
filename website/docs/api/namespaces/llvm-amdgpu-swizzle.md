---

# DO NOT EDIT!
# Automatically generated via doxygen2docusaurus by Doxygen.

slug: /api/namespaces/llvm/amdgpu/swizzle
custom_edit_url: null
toc_max_heading_level: 4
keywords:
  - doxygen
  - reference
  - namespace

---

<div class="doxyPage">

# The `Swizzle` Namespace Reference



## Definition

<div class="doxyDefinition">
namespace llvm::AMDGPU::Swizzle { ... }
</div>

## Enumerations Index

<table class="doxyMembersIndex">

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">enum</td>
<td class="doxyMemberIndexItemName" align="left" valign="top">Id : unsigned { <a href="#a4f8d63108fc54934889e0b11c61f31c2">...</a> }</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top">EncBits : unsigned { <a href="#a381cab423ce806fd73e190fcb8f49a83">...</a> }</td>
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

## Variables Index

<table class="doxyMembersIndex">

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> char *<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#af86ab86293794f6553fee00cf270f36b">IdSymbolic</a>[] = ...</td>
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

### EncBits {#a381cab423ce806fd73e190fcb8f49a83}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">enum llvm::AMDGPU::Swizzle::EncBits : unsigned</td>
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
<td class="doxyEnumItemName">QUAD_PERM_ENC<a id="a381cab423ce806fd73e190fcb8f49a83ac0315a1c23874571d99e8afc42f6f1a6"></a></td>
<td class="doxyEnumItemDescription"> (= 0x8000)</td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">QUAD_PERM_ENC_MASK<a id="a381cab423ce806fd73e190fcb8f49a83a4ced925fd9bf7ea112827aea440e168c"></a></td>
<td class="doxyEnumItemDescription"> (= 0xFF00)</td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">BITMASK_PERM_ENC<a id="a381cab423ce806fd73e190fcb8f49a83ab1f81e4ef3adbe04a3a999886c6ecf21"></a></td>
<td class="doxyEnumItemDescription"> (= 0x0000)</td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">BITMASK_PERM_ENC_MASK<a id="a381cab423ce806fd73e190fcb8f49a83a3a840787e58917775b5021aafdc2046f"></a></td>
<td class="doxyEnumItemDescription"> (= 0x8000)</td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">FFT_MODE_ENC<a id="a381cab423ce806fd73e190fcb8f49a83a6d1a1fa107c0114b85ff4fd4f350249d"></a></td>
<td class="doxyEnumItemDescription"> (= 0xE000)</td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">ROTATE_MODE_ENC<a id="a381cab423ce806fd73e190fcb8f49a83a29bead916d7cd5999b54609a84f8e9f6"></a></td>
<td class="doxyEnumItemDescription"> (= 0xC000)</td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">FFT_ROTATE_MODE_MASK<a id="a381cab423ce806fd73e190fcb8f49a83af999f3564904984e6496d08d61f4aa0d"></a></td>
<td class="doxyEnumItemDescription"> (= 0xF000)</td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">ROTATE_MODE_LO<a id="a381cab423ce806fd73e190fcb8f49a83abe34b861f6846fc989fdff89c425d7d7"></a></td>
<td class="doxyEnumItemDescription"> (= 0xC000)</td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">FFT_MODE_LO<a id="a381cab423ce806fd73e190fcb8f49a83ad2abb9fb15f8060ec8838a511bb402e7"></a></td>
<td class="doxyEnumItemDescription"> (= 0xE000)</td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">LANE_MASK<a id="a381cab423ce806fd73e190fcb8f49a83a6f529fe757ee2d6b98aec1525a78da27"></a></td>
<td class="doxyEnumItemDescription"> (= 0x3)</td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">LANE_MAX<a id="a381cab423ce806fd73e190fcb8f49a83ad71af14870448db33fbb43c2e1e50672"></a></td>
<td class="doxyEnumItemDescription"> (= LANE_MASK)</td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">LANE_SHIFT<a id="a381cab423ce806fd73e190fcb8f49a83acf3ca28a336368c8e2e89d5f996b8d66"></a></td>
<td class="doxyEnumItemDescription"> (= 2)</td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">LANE_NUM<a id="a381cab423ce806fd73e190fcb8f49a83acf0725b2c90fcca9a43a6d391381232d"></a></td>
<td class="doxyEnumItemDescription"> (= 4)</td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">BITMASK_MASK<a id="a381cab423ce806fd73e190fcb8f49a83ab2da60bb7fe040845cfd4194da5d824e"></a></td>
<td class="doxyEnumItemDescription"> (= 0x1F)</td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">BITMASK_MAX<a id="a381cab423ce806fd73e190fcb8f49a83a111922802b1817b5eda4c2b2eedbe1d2"></a></td>
<td class="doxyEnumItemDescription"> (= BITMASK_MASK)</td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">BITMASK_WIDTH<a id="a381cab423ce806fd73e190fcb8f49a83ae94fe537b6f11c57e17e7b82bf923846"></a></td>
<td class="doxyEnumItemDescription"> (= 5)</td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">BITMASK_AND_SHIFT<a id="a381cab423ce806fd73e190fcb8f49a83aede0787cb665bb8b15b876f4746947cd"></a></td>
<td class="doxyEnumItemDescription"> (= 0)</td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">BITMASK_OR_SHIFT<a id="a381cab423ce806fd73e190fcb8f49a83a204d8769ddd5fd44322d6438969d9a8d"></a></td>
<td class="doxyEnumItemDescription"> (= 5)</td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">BITMASK_XOR_SHIFT<a id="a381cab423ce806fd73e190fcb8f49a83af237a8a32526c4f1cc633192ad28aad8"></a></td>
<td class="doxyEnumItemDescription"> (= 10)</td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">FFT_SWIZZLE_MASK<a id="a381cab423ce806fd73e190fcb8f49a83a68eb972ee6c3909a458ef89bc3105b73"></a></td>
<td class="doxyEnumItemDescription"> (= 0x1F)</td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">FFT_SWIZZLE_MAX<a id="a381cab423ce806fd73e190fcb8f49a83ae7e32a6f930f4121d60e606e29be59fa"></a></td>
<td class="doxyEnumItemDescription"> (= 0x1F)</td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">ROTATE_MAX_SIZE<a id="a381cab423ce806fd73e190fcb8f49a83a4d2037dcbc8b1ebc589bad3215a21012"></a></td>
<td class="doxyEnumItemDescription"> (= 0x1F)</td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">ROTATE_DIR_SHIFT<a id="a381cab423ce806fd73e190fcb8f49a83a16e0dd7f4558950530ba31b97366d546"></a></td>
<td class="doxyEnumItemDescription"> (= 10)</td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">ROTATE_DIR_MASK<a id="a381cab423ce806fd73e190fcb8f49a83a37c416c7fc6a05a860dcb1200d2de022"></a></td>
<td class="doxyEnumItemDescription"> (= 0x1)</td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">ROTATE_SIZE_SHIFT<a id="a381cab423ce806fd73e190fcb8f49a83af33d59cbb98ea3a4dca4c0bd9c4df6cf"></a></td>
<td class="doxyEnumItemDescription"> (= 5)</td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">ROTATE_SIZE_MASK<a id="a381cab423ce806fd73e190fcb8f49a83ae09c857633410a609ec59e4a5bd2d7b6"></a></td>
<td class="doxyEnumItemDescription"> (= ROTATE_MAX_SIZE)</td>
</tr>

</table>
</dd>
</dl>

<p>Definition at line 850 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/sidefines-h">SIDefines.h</a>.</p>

</div>
</div>

### Id {#a4f8d63108fc54934889e0b11c61f31c2}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">enum llvm::AMDGPU::Swizzle::Id : unsigned</td>
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
<td class="doxyEnumItemName">ID_QUAD_PERM<a id="a4f8d63108fc54934889e0b11c61f31c2adbc8019a078b4a0407e5094281305a62"></a></td>
<td class="doxyEnumItemDescription"> (= 0)</td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">ID_BITMASK_PERM<a id="a4f8d63108fc54934889e0b11c61f31c2aa82ee48b2dffe6feea7c981b40e82c0a"></a></td>
<td class="doxyEnumItemDescription"></td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">ID_SWAP<a id="a4f8d63108fc54934889e0b11c61f31c2a0c72d4f818886442d3002d7c19e80785"></a></td>
<td class="doxyEnumItemDescription"></td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">ID_REVERSE<a id="a4f8d63108fc54934889e0b11c61f31c2a5b31fa892b7889649899a01b58c02bfd"></a></td>
<td class="doxyEnumItemDescription"></td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">ID_BROADCAST<a id="a4f8d63108fc54934889e0b11c61f31c2a45963ea85feec95c4749f3e29ad4203c"></a></td>
<td class="doxyEnumItemDescription"></td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">ID_FFT<a id="a4f8d63108fc54934889e0b11c61f31c2a3453b0147852c7bcff11b218a616c2d9"></a></td>
<td class="doxyEnumItemDescription"></td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">ID_ROTATE<a id="a4f8d63108fc54934889e0b11c61f31c2a58a8662aa4261301c6ae7bdea81ba332"></a></td>
<td class="doxyEnumItemDescription"></td>
</tr>

</table>
</dd>
</dl>

<p>Definition at line 839 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/sidefines-h">SIDefines.h</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Variables

### IdSymbolic {#af86ab86293794f6553fee00cf270f36b}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">const char *const llvm::AMDGPU::Swizzle::IdSymbolic</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<dl class="doxySectionUser">
<dt>Initialiser</dt>
<dd>
<div class="doxyVerbatim">= {
  "QUAD_PERM",
  "BITMASK_PERM",
  "SWAP",
  "REVERSE",
  "BROADCAST",
  "FFT",
  "ROTATE",
}
</div>
</dd>
</dl>

<p>Definition at line 650 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/lib/target/amdgpu/utils/amdgpuasmutils-cpp">AMDGPUAsmUtils.cpp</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/classes/anonymous-amdgpuasmparser-cpp-/amdgpuasmparser/#a158cdc1506b2dfbeace5ec8c87327426">anonymous{AMDGPUAsmParser.cpp}::AMDGPUAsmParser::parseGPRIdxMacro</a>, <a href="/web-llvm/docs/api/classes/anonymous-amdgpuasmparser-cpp-/amdgpuasmparser/#a084f15a5b33b0ce4978446665fabd0b7">anonymous{AMDGPUAsmParser.cpp}::AMDGPUAsmParser::parseSwizzleMacro</a> and <a href="/web-llvm/docs/api/classes/llvm/amdgpuinstprinter/#a0124206da659398599dfb682b6a610cb">llvm::AMDGPUInstPrinter::printSwizzle</a>.</p>

</div>
</div>

</div>

<hr/>

The documentation for this namespace was generated from the following files:

<ul>
<li><a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/sidefines-h">SIDefines.h</a></li>
<li><a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/lib/target/amdgpu/utils/amdgpuasmutils-cpp">AMDGPUAsmUtils.cpp</a></li>
</ul>

<hr/>

<p class="doxyGeneratedBy">Generated via <a href="https://github.com/xpack/doxygen2docusaurus">doxygen2docusaurus</a> by <a href="https://www.doxygen.nl">Doxygen</a> 1.15.0.</p>

</div>
