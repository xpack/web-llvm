---

# DO NOT EDIT!
# Automatically generated via doxygen2docusaurus by Doxygen.

slug: /api/namespaces/llvm/wineh
custom_edit_url: null
toc_max_heading_level: 4
keywords:
  - doxygen
  - reference
  - namespace

---

<div class="doxyPage">

# The `WinEH` Namespace Reference



## Definition

<div class="doxyDefinition">
namespace llvm::WinEH { ... }
</div>

## Classes Index

<table class="doxyMembersIndex">

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">struct</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="/web-llvm/docs/api/structs/llvm/wineh/frameinfo">FrameInfo</a></td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">struct</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="/web-llvm/docs/api/structs/llvm/wineh/instruction">Instruction</a></td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">class</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/wineh/unwindemitter">UnwindEmitter</a></td>
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

## Enumerations Index

<table class="doxyMembersIndex">

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">enum class</td>
<td class="doxyMemberIndexItemName" align="left" valign="top">EncodingType { <a href="#a1c8d8103d6b914c2ade85873cb97f6d9">...</a> }</td>
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

### EncodingType {#a1c8d8103d6b914c2ade85873cb97f6d9}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">enum class llvm::WinEH::EncodingType </td>
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
<td class="doxyEnumItemName">Invalid<a id="a1c8d8103d6b914c2ade85873cb97f6d9a4bbb8f967da6d1a610596d7257179c2b"></a></td>
<td class="doxyEnumItemDescription"></td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">Alpha<a id="a1c8d8103d6b914c2ade85873cb97f6d9a6132295fcf5570fb8b0a944ef322a598"></a></td>
<td class="doxyEnumItemDescription">Invalid</td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">Alpha64<a id="a1c8d8103d6b914c2ade85873cb97f6d9a913e3bc2261166c4cd90371e7273a06c"></a></td>
<td class="doxyEnumItemDescription">Windows Alpha</td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">ARM<a id="a1c8d8103d6b914c2ade85873cb97f6d9a47f45e65244c17ec9fa8771a5c6d60e1"></a></td>
<td class="doxyEnumItemDescription">Windows AXP64</td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">CE<a id="a1c8d8103d6b914c2ade85873cb97f6d9a7a86131338bf955e0a56311f264aa6aa"></a></td>
<td class="doxyEnumItemDescription">Windows NT (Windows on <a href="/web-llvm/docs/api/namespaces/llvm/arm">ARM</a>)</td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">Itanium<a id="a1c8d8103d6b914c2ade85873cb97f6d9a19ba66c202fd06b553e4e1895204561d"></a></td>
<td class="doxyEnumItemDescription">Windows CE <a href="/web-llvm/docs/api/namespaces/llvm/arm">ARM</a>, PowerPC, SH3, SH4</td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">X86<a id="a1c8d8103d6b914c2ade85873cb97f6d9afd1a4608b5b463bc7a41d86a1662d3b7"></a></td>
<td class="doxyEnumItemDescription">Windows x64, Windows Itanium (IA-64)</td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">MIPS<a id="a1c8d8103d6b914c2ade85873cb97f6d9a16c8e070f0f6edd7ac0ae016e9bf2997"></a></td>
<td class="doxyEnumItemDescription">Windows x86, uses no CFI, just EH tables (= Alpha)</td>
</tr>

</table>
</dd>
</dl>

<p>Definition at line 35 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/mc/mcasminfo-h">MCAsmInfo.h</a>.</p>

</div>
</div>

</div>

<hr/>

The documentation for this namespace was generated from the following file:

<ul>
<li><a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/mc/mcasminfo-h">MCAsmInfo.h</a></li>
</ul>

<hr/>

<p class="doxyGeneratedBy">Generated via <a href="https://github.com/xpack/doxygen2docusaurus">doxygen2docusaurus</a> by <a href="https://www.doxygen.nl">Doxygen</a> 1.14.0.</p>

</div>
