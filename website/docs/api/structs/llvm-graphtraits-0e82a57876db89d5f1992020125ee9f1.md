---

# DO NOT EDIT!
# Automatically generated via doxygen2docusaurus by Doxygen.

slug: /api/structs/llvm/graphtraits-0e82a57876db89d5f1992020125ee9f1
custom_edit_url: null
toc_max_heading_level: 4
keywords:
  - doxygen
  - reference
  - struct

---

<div class="doxyPage">

# The `GraphTraits` Struct Template Reference



## Declaration

<div class="doxyDeclaration">
struct llvm::GraphTraits&lt;MachineRegionInfoPass *&gt; { ... }
</div>

## Included Headers

<div class="doxyIncludesList">#include "<a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/codegen/machineregioninfo-h">llvm/CodeGen/MachineRegionInfo.h</a>"
</div>

## Base struct

<table class="doxyMembersIndex">

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">struct</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="/web-llvm/docs/api/structs/llvm/graphtraits-92d367d772136c0b801e6582c305ddf5">GraphTraits&lt;MachineRegionInfo *&gt;</a></td>
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

## Public Member Typedefs Index

<table class="doxyMembersIndex">

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">using</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a6c4affa1be2fe83189314fce93be2ea5">nodes_iterator</a> = <a href="/web-llvm/docs/api/classes/llvm/df-iterator">df_iterator</a>&lt; <a href="/web-llvm/docs/api/structs/llvm/graphtraits/#a741f7d63af17a7bd0bcf63f68e8658bd">NodeRef</a>, <a href="/web-llvm/docs/api/structs/llvm/df-iterator-default-set">df_iterator_default_set</a>&lt; <a href="/web-llvm/docs/api/structs/llvm/graphtraits/#a741f7d63af17a7bd0bcf63f68e8658bd">NodeRef</a> &gt;, false, <a href="/web-llvm/docs/api/structs/llvm/graphtraits">GraphTraits</a>&lt; <a href="/web-llvm/docs/api/classes/llvm/flatit">FlatIt</a>&lt; <a href="/web-llvm/docs/api/structs/llvm/graphtraits/#a741f7d63af17a7bd0bcf63f68e8658bd">NodeRef</a> &gt; &gt; &gt;</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">using</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="/web-llvm/docs/api/structs/llvm/graphtraits/#a741f7d63af17a7bd0bcf63f68e8658bd">NodeRef</a> = typename <a href="/web-llvm/docs/api/classes/llvm/machineregioninfopass">MachineRegionInfoPass</a> *::UnknownGraphTypeError</td>
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

## Public Static Functions Index

<table class="doxyMembersIndex">

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">static <a href="/web-llvm/docs/api/structs/llvm/graphtraits/#a741f7d63af17a7bd0bcf63f68e8658bd">NodeRef</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a653f88b177076c5b72744a6e75264ec2">getEntryNode</a> (MachineRegionInfoPass *RI)</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">static <a href="#a6c4affa1be2fe83189314fce93be2ea5">nodes_iterator</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#af10a31bc3b1ddd615018b1f124f9bac4">nodes_begin</a> (MachineRegionInfoPass *RI)</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">static <a href="#a6c4affa1be2fe83189314fce93be2ea5">nodes_iterator</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#aabfdda1ad68013475b120c65164af110">nodes_end</a> (MachineRegionInfoPass *RI)</td>
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


<p>Definition at line 157 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/codegen/machineregioninfo-h">MachineRegionInfo.h</a>.</p>


<div class="doxySectionDef">

## Public Member Typedefs

### NodeRef {#a741f7d63af17a7bd0bcf63f68e8658bd}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">using llvm::GraphTraits&lt; MachineRegionInfoPass * &gt;::NodeRef = </td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 95 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/adt/graphtraits-h">GraphTraits.h</a>.</p>

</div>
</div>

### nodes\_iterator {#a6c4affa1be2fe83189314fce93be2ea5}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">using llvm::GraphTraits&lt; MachineRegionInfoPass * &gt;::nodes_iterator =  df_iterator&lt;NodeRef, df_iterator_default_set&lt;NodeRef&gt;,
                                     false, GraphTraits&lt;FlatIt&lt;NodeRef&gt;&gt;&gt;</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 159 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/codegen/machineregioninfo-h">MachineRegionInfo.h</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Public Static Functions

### getEntryNode() {#a653f88b177076c5b72744a6e75264ec2}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">NodeRef llvm::GraphTraits&lt; MachineRegionInfoPass * &gt;::getEntryNode (<a href="/web-llvm/docs/api/classes/llvm/machineregioninfopass">MachineRegionInfoPass</a> * RI)</td>
</tr>
</table>
</td>
<td class="doxyMemberLabelsRight">
<span class="doxyMemberLabels">
<span class="doxyMemberLabel inline">inline</span>
<span class="doxyMemberLabel static">static</span>
</span>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 162 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/codegen/machineregioninfo-h">MachineRegionInfo.h</a>.</p>


<p>Reference <a href="/web-llvm/docs/api/classes/llvm/machineregioninfopass/#a562b87543e8feec99bedc63adb486f34">llvm::MachineRegionInfoPass::getRegionInfo</a>.</p>

</div>
</div>

### nodes\_begin() {#af10a31bc3b1ddd615018b1f124f9bac4}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">nodes_iterator llvm::GraphTraits&lt; MachineRegionInfoPass * &gt;::nodes_begin (<a href="/web-llvm/docs/api/classes/llvm/machineregioninfopass">MachineRegionInfoPass</a> * RI)</td>
</tr>
</table>
</td>
<td class="doxyMemberLabelsRight">
<span class="doxyMemberLabels">
<span class="doxyMemberLabel inline">inline</span>
<span class="doxyMemberLabel static">static</span>
</span>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 166 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/codegen/machineregioninfo-h">MachineRegionInfo.h</a>.</p>


<p>Reference <a href="/web-llvm/docs/api/classes/llvm/machineregioninfopass/#a562b87543e8feec99bedc63adb486f34">llvm::MachineRegionInfoPass::getRegionInfo</a>.</p>

</div>
</div>

### nodes\_end() {#aabfdda1ad68013475b120c65164af110}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">nodes_iterator llvm::GraphTraits&lt; MachineRegionInfoPass * &gt;::nodes_end (<a href="/web-llvm/docs/api/classes/llvm/machineregioninfopass">MachineRegionInfoPass</a> * RI)</td>
</tr>
</table>
</td>
<td class="doxyMemberLabelsRight">
<span class="doxyMemberLabels">
<span class="doxyMemberLabel inline">inline</span>
<span class="doxyMemberLabel static">static</span>
</span>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 170 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/codegen/machineregioninfo-h">MachineRegionInfo.h</a>.</p>


<p>Reference <a href="/web-llvm/docs/api/classes/llvm/machineregioninfopass/#a562b87543e8feec99bedc63adb486f34">llvm::MachineRegionInfoPass::getRegionInfo</a>.</p>

</div>
</div>

</div>

<hr/>

The documentation for this struct was generated from the following files:

<ul>
<li><a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/adt/graphtraits-h">GraphTraits.h</a></li>
<li><a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/codegen/machineregioninfo-h">MachineRegionInfo.h</a></li>
</ul>

<hr/>

<p class="doxyGeneratedBy">Generated via <a href="https://github.com/xpack/doxygen2docusaurus">doxygen2docusaurus</a> by <a href="https://www.doxygen.nl">Doxygen</a> 1.14.0.</p>

</div>
