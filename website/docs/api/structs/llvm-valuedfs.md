---

# DO NOT EDIT!
# Automatically generated via doxygen2docusaurus by Doxygen.

slug: /api/structs/llvm/valuedfs
custom_edit_url: null
toc_max_heading_level: 4
keywords:
  - doxygen
  - reference
  - struct

---

<div class="doxyPage">

# `ValueDFS` Struct



## Declaration

<div class="doxyDeclaration">
struct llvm::ValueDFS { ... }
</div>

## Public Member Attributes Index

<table class="doxyMembersIndex">

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">int</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#abcf869d6b4e1360809b2b7ce8d319cdc">DFSIn</a> = 0</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a19d8714858d8500a598848f43b46f925">DFSOut</a> = 0</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">unsigned int</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a5607c7a08912063c13fa6893a6404525">LocalNum</a> = <a href="/web-llvm/docs/api/namespaces/llvm/#a897d843742d5f7e0eba427a397c52775a68fdabff8b3118c0e68625dce3b18c8c">LN_Middle</a></td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/value">Value</a> *</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a16ce56a5aafba7067cead02831a1195c">Def</a> = nullptr</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/use">Use</a> *</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a209c5ea40a3297a48893d027b7b3f35b">U</a> = nullptr</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/predicatebase">PredicateBase</a> *</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a4d7a18adbe6f80dc385304f220e9fdb1">PInfo</a> = nullptr</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a60d00f6e83c6c5925bd23e4b033d1983">EdgeOnly</a> = false</td>
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


<p>Definition at line 85 of file <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/utils/predicateinfo-cpp">PredicateInfo.cpp</a>.</p>


<div class="doxySectionDef">

## Public Member Attributes

### Def {#a16ce56a5aafba7067cead02831a1195c}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">Value* llvm::ValueDFS::Def = nullptr</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 90 of file <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/utils/predicateinfo-cpp">PredicateInfo.cpp</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/structs/llvm/valuedfs-compare/#a025277d3135d6afe0bda3b482611eff5">llvm::ValueDFS_Compare::getBlockEdge</a> and <a href="/web-llvm/docs/api/structs/llvm/valuedfs-compare/#ad889a638f68e28fd676799e94298e697">llvm::ValueDFS_Compare::getMiddleDef</a>.</p>

</div>
</div>

### DFSIn {#abcf869d6b4e1360809b2b7ce8d319cdc}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">int llvm::ValueDFS::DFSIn = 0</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 86 of file <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/utils/predicateinfo-cpp">PredicateInfo.cpp</a>.</p>

</div>
</div>

### DFSOut {#a19d8714858d8500a598848f43b46f925}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">int llvm::ValueDFS::DFSOut = 0</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 87 of file <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/utils/predicateinfo-cpp">PredicateInfo.cpp</a>.</p>

</div>
</div>

### EdgeOnly {#a60d00f6e83c6c5925bd23e4b033d1983}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool llvm::ValueDFS::EdgeOnly = false</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 94 of file <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/utils/predicateinfo-cpp">PredicateInfo.cpp</a>.</p>

</div>
</div>

### LocalNum {#a5607c7a08912063c13fa6893a6404525}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">unsigned int llvm::ValueDFS::LocalNum = <a href="/web-llvm/docs/api/namespaces/llvm/#a897d843742d5f7e0eba427a397c52775a68fdabff8b3118c0e68625dce3b18c8c">LN_Middle</a></td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 88 of file <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/utils/predicateinfo-cpp">PredicateInfo.cpp</a>.</p>

</div>
</div>

### PInfo {#a4d7a18adbe6f80dc385304f220e9fdb1}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">PredicateBase* llvm::ValueDFS::PInfo = nullptr</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 93 of file <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/utils/predicateinfo-cpp">PredicateInfo.cpp</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/structs/llvm/valuedfs-compare/#a025277d3135d6afe0bda3b482611eff5">llvm::ValueDFS_Compare::getBlockEdge</a> and <a href="/web-llvm/docs/api/structs/llvm/valuedfs-compare/#ad889a638f68e28fd676799e94298e697">llvm::ValueDFS_Compare::getMiddleDef</a>.</p>

</div>
</div>

### U {#a209c5ea40a3297a48893d027b7b3f35b}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">Use* llvm::ValueDFS::U = nullptr</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 91 of file <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/utils/predicateinfo-cpp">PredicateInfo.cpp</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/structs/llvm/valuedfs-compare/#a025277d3135d6afe0bda3b482611eff5">llvm::ValueDFS_Compare::getBlockEdge</a> and <a href="/web-llvm/docs/api/structs/llvm/valuedfs-compare/#ad889a638f68e28fd676799e94298e697">llvm::ValueDFS_Compare::getMiddleDef</a>.</p>

</div>
</div>

</div>

<hr/>

The documentation for this struct was generated from the following file:

<ul>
<li><a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/utils/predicateinfo-cpp">PredicateInfo.cpp</a></li>
</ul>

<hr/>

<p class="doxyGeneratedBy">Generated via <a href="https://xpack.github.io/doxygen2docusaurus">doxygen2docusaurus</a> 2.0.0 by <a href="https://www.doxygen.nl">Doxygen</a> 1.15.0.</p>

</div>
