---

# DO NOT EDIT!
# Automatically generated via doxygen2docusaurus by Doxygen.

slug: /api/structs/llvm/omf/signature
custom_edit_url: null
toc_max_heading_level: 4
keywords:
  - doxygen
  - reference
  - struct

---

<div class="doxyPage">

# The `Signature` Struct Reference



## Declaration

<div class="doxyDeclaration">
struct llvm::OMF::Signature { ... }
</div>

## Included Headers

<div class="doxyIncludesList">#include "<a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/object/cvdebugrecord-h">llvm/Object/CVDebugRecord.h</a>"
</div>

## Enumerations Index

<table class="doxyMembersIndex">

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">enum</td>
<td class="doxyMemberIndexItemName" align="left" valign="top">ID : uint32_t { <a href="#a762ecf3b150b2940a952afc331625c1d">...</a> }</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/namespaces/llvm/support/#a206b37274fa3e908017da357d12724d1">support::ulittle32_t</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a91e4cc920bb770da8881b556cfead9de">CVSignature</a></td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/namespaces/llvm/support/#a206b37274fa3e908017da357d12724d1">support::ulittle32_t</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#aa05ee6cba86f0006ec593a2ede1f2480">Offset</a></td>
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


<p>Definition at line 16 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/object/cvdebugrecord-h">CVDebugRecord.h</a>.</p>


<div class="doxySectionDef">

## Enumerations

### ID {#a762ecf3b150b2940a952afc331625c1d}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">enum llvm::OMF::Signature::ID : uint32_t</td>
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
<td class="doxyEnumItemName">PDB70<a id="a762ecf3b150b2940a952afc331625c1da5e6aae0789ad97cf1deabd5676c9b21a"></a></td>
<td class="doxyEnumItemDescription"> (= 0x53445352)</td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">PDB20<a id="a762ecf3b150b2940a952afc331625c1da470ae7933eb1c0aaa130dfaa57339243"></a></td>
<td class="doxyEnumItemDescription"> (= 0x3031424e)</td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">CV50<a id="a762ecf3b150b2940a952afc331625c1dae0367a2015a0d02bf839bee8fdd60c41"></a></td>
<td class="doxyEnumItemDescription"> (= 0x3131424e)</td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">CV41<a id="a762ecf3b150b2940a952afc331625c1da2370512809594b1e973ab15b4ee78cfc"></a></td>
<td class="doxyEnumItemDescription"> (= 0x3930424e)</td>
</tr>

</table>
</dd>
</dl>

<p>Definition at line 17 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/object/cvdebugrecord-h">CVDebugRecord.h</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Public Member Attributes

### CVSignature {#a91e4cc920bb770da8881b556cfead9de}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">support::ulittle32_t llvm::OMF::Signature::CVSignature</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 24 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/object/cvdebugrecord-h">CVDebugRecord.h</a>.</p>

</div>
</div>

### Offset {#aa05ee6cba86f0006ec593a2ede1f2480}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">support::ulittle32_t llvm::OMF::Signature::Offset</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 25 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/object/cvdebugrecord-h">CVDebugRecord.h</a>.</p>

</div>
</div>

</div>

<hr/>

The documentation for this struct was generated from the following file:

<ul>
<li><a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/object/cvdebugrecord-h">CVDebugRecord.h</a></li>
</ul>

<hr/>

<p class="doxyGeneratedBy">Generated via <a href="https://github.com/xpack/doxygen2docusaurus">doxygen2docusaurus</a> by <a href="https://www.doxygen.nl">Doxygen</a> 1.14.0.</p>

</div>
