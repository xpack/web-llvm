---

# DO NOT EDIT!
# Automatically generated via doxygen2docusaurus by Doxygen.

slug: /api/structs/llvm/gvnoptions
custom_edit_url: null
toc_max_heading_level: 4
keywords:
  - doxygen
  - reference
  - struct

---

<div class="doxyPage">

# The `GVNOptions` Struct Reference

<p>A set of parameters to control various transforms performed by GVN pass. <a href="#details">More...</a></p>

## Declaration

<div class="doxyDeclaration">
struct llvm::GVNOptions { ... }
</div>

## Included Headers

<div class="doxyIncludesList">#include "<a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/transforms/include/llvm/transforms/scalar/gvn-h">llvm/Transforms/Scalar/GVN.h</a>"
</div>

## Public Constructors Index

<table class="doxyMembersIndex">

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ad317faa6ef441fc9afbadc1600b228c2">GVNOptions</a> ()=default</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/structs/llvm/gvnoptions">GVNOptions</a> &amp;</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a584701a8b7ab9cd7041180a30f0c21f1">setPRE</a> (bool PRE)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Enables or disables PRE in GVN. <a href="#a584701a8b7ab9cd7041180a30f0c21f1">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/structs/llvm/gvnoptions">GVNOptions</a> &amp;</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a1a88f46e232058fa2f38561394c0568a">setLoadPRE</a> (bool LoadPRE)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Enables or disables PRE of loads in GVN. <a href="#a1a88f46e232058fa2f38561394c0568a">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/structs/llvm/gvnoptions">GVNOptions</a> &amp;</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a6252ee4b682c8e1fb43cf0075bcf24c4">setLoadInLoopPRE</a> (bool LoadInLoopPRE)</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/structs/llvm/gvnoptions">GVNOptions</a> &amp;</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#aa76f5d125c799144263a396569fc42fa">setLoadPRESplitBackedge</a> (bool LoadPRESplitBackedge)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Enables or disables PRE of loads in GVN. <a href="#aa76f5d125c799144263a396569fc42fa">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/structs/llvm/gvnoptions">GVNOptions</a> &amp;</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a8f1e7a8db3a9cbdc63b0c5d5b3396017">setMemDep</a> (bool MemDep)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Enables or disables use of MemDepAnalysis. <a href="#a8f1e7a8db3a9cbdc63b0c5d5b3396017">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/structs/llvm/gvnoptions">GVNOptions</a> &amp;</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ade043703ab858de7304776f0b79c79e0">setMemorySSA</a> (bool MemSSA)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Enables or disables use of <a href="/web-llvm/docs/api/classes/llvm/memoryssa">MemorySSA</a>. <a href="#ade043703ab858de7304776f0b79c79e0">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

</table>

## Public Member Attributes Index

<table class="doxyMembersIndex">

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">std::optional&lt; bool &gt;</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a6ddc630f2fb57ab4a1f05c681519c4e7">AllowPRE</a></td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">std::optional&lt; bool &gt;</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#aa59260de65b23347a78426da4553dcbe">AllowLoadPRE</a></td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">std::optional&lt; bool &gt;</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a746d52952cfb4a76286e71d186aa7090">AllowLoadInLoopPRE</a></td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">std::optional&lt; bool &gt;</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a29e212bd1ed59b642ae8f32393c188ae">AllowLoadPRESplitBackedge</a></td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">std::optional&lt; bool &gt;</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a897e7d708586d9ba2dba64c12913bd78">AllowMemDep</a></td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">std::optional&lt; bool &gt;</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#abaf7ba38dcb90aa8e6199bfc371236f3">AllowMemorySSA</a></td>
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

<p>A set of parameters to control various transforms performed by GVN pass.</p>


<p>true - enabling the transformation. false - disabling the transformation. None - relying on a global default. Intended use is to create a default object, modify parameters with additional setters and then pass it to GVN.</p>


<p>Definition at line 74 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/transforms/include/llvm/transforms/scalar/gvn-h">GVN.h</a>.</p>


<div class="doxySectionDef">

## Public Constructors

### GVNOptions() {#ad317faa6ef441fc9afbadc1600b228c2}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">llvm::GVNOptions::GVNOptions ()</td>
</tr>
</table>
</td>
<td class="doxyMemberLabelsRight">
<span class="doxyMemberLabels">
<span class="doxyMemberLabel default">default</span>
</span>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 82 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/transforms/include/llvm/transforms/scalar/gvn-h">GVN.h</a>.</p>


<p>Referenced by <a href="#a6252ee4b682c8e1fb43cf0075bcf24c4">setLoadInLoopPRE</a>, <a href="#a1a88f46e232058fa2f38561394c0568a">setLoadPRE</a>, <a href="#aa76f5d125c799144263a396569fc42fa">setLoadPRESplitBackedge</a>, <a href="#a8f1e7a8db3a9cbdc63b0c5d5b3396017">setMemDep</a>, <a href="#ade043703ab858de7304776f0b79c79e0">setMemorySSA</a> and <a href="#a584701a8b7ab9cd7041180a30f0c21f1">setPRE</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Public Member Functions

### setLoadInLoopPRE() {#a6252ee4b682c8e1fb43cf0075bcf24c4}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">GVNOptions &amp; llvm::GVNOptions::setLoadInLoopPRE (bool LoadInLoopPRE)</td>
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



<p>Definition at line 96 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/transforms/include/llvm/transforms/scalar/gvn-h">GVN.h</a>.</p>


<p>References <a href="#a746d52952cfb4a76286e71d186aa7090">AllowLoadInLoopPRE</a> and <a href="#ad317faa6ef441fc9afbadc1600b228c2">GVNOptions</a>.</p>

</div>
</div>

### setLoadPRE() {#a1a88f46e232058fa2f38561394c0568a}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">GVNOptions &amp; llvm::GVNOptions::setLoadPRE (bool LoadPRE)</td>
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

<p>Enables or disables PRE of loads in GVN.</p>

<p>Definition at line 91 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/transforms/include/llvm/transforms/scalar/gvn-h">GVN.h</a>.</p>


<p>References <a href="#aa59260de65b23347a78426da4553dcbe">AllowLoadPRE</a> and <a href="#ad317faa6ef441fc9afbadc1600b228c2">GVNOptions</a>.</p>

</div>
</div>

### setLoadPRESplitBackedge() {#aa76f5d125c799144263a396569fc42fa}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">GVNOptions &amp; llvm::GVNOptions::setLoadPRESplitBackedge (bool LoadPRESplitBackedge)</td>
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

<p>Enables or disables PRE of loads in GVN.</p>

<p>Definition at line 102 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/transforms/include/llvm/transforms/scalar/gvn-h">GVN.h</a>.</p>


<p>References <a href="#a29e212bd1ed59b642ae8f32393c188ae">AllowLoadPRESplitBackedge</a> and <a href="#ad317faa6ef441fc9afbadc1600b228c2">GVNOptions</a>.</p>

</div>
</div>

### setMemDep() {#a8f1e7a8db3a9cbdc63b0c5d5b3396017}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">GVNOptions &amp; llvm::GVNOptions::setMemDep (bool MemDep)</td>
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

<p>Enables or disables use of MemDepAnalysis.</p>

<p>Definition at line 108 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/transforms/include/llvm/transforms/scalar/gvn-h">GVN.h</a>.</p>


<p>References <a href="#a897e7d708586d9ba2dba64c12913bd78">AllowMemDep</a> and <a href="#ad317faa6ef441fc9afbadc1600b228c2">GVNOptions</a>.</p>

</div>
</div>

### setMemorySSA() {#ade043703ab858de7304776f0b79c79e0}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">GVNOptions &amp; llvm::GVNOptions::setMemorySSA (bool MemSSA)</td>
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

<p>Enables or disables use of <a href="/web-llvm/docs/api/classes/llvm/memoryssa">MemorySSA</a>.</p>

<p>Definition at line 114 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/transforms/include/llvm/transforms/scalar/gvn-h">GVN.h</a>.</p>


<p>References <a href="#abaf7ba38dcb90aa8e6199bfc371236f3">AllowMemorySSA</a> and <a href="#ad317faa6ef441fc9afbadc1600b228c2">GVNOptions</a>.</p>

</div>
</div>

### setPRE() {#a584701a8b7ab9cd7041180a30f0c21f1}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">GVNOptions &amp; llvm::GVNOptions::setPRE (bool PRE)</td>
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

<p>Enables or disables PRE in GVN.</p>

<p>Definition at line 85 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/transforms/include/llvm/transforms/scalar/gvn-h">GVN.h</a>.</p>


<p>References <a href="#a6ddc630f2fb57ab4a1f05c681519c4e7">AllowPRE</a> and <a href="#ad317faa6ef441fc9afbadc1600b228c2">GVNOptions</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Public Member Attributes

### AllowLoadInLoopPRE {#a746d52952cfb4a76286e71d186aa7090}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">std::optional&lt;bool&gt; llvm::GVNOptions::AllowLoadInLoopPRE</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 77 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/transforms/include/llvm/transforms/scalar/gvn-h">GVN.h</a>.</p>


<p>Referenced by <a href="#a6252ee4b682c8e1fb43cf0075bcf24c4">setLoadInLoopPRE</a>.</p>

</div>
</div>

### AllowLoadPRE {#aa59260de65b23347a78426da4553dcbe}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">std::optional&lt;bool&gt; llvm::GVNOptions::AllowLoadPRE</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 76 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/transforms/include/llvm/transforms/scalar/gvn-h">GVN.h</a>.</p>


<p>Referenced by <a href="#a1a88f46e232058fa2f38561394c0568a">setLoadPRE</a>.</p>

</div>
</div>

### AllowLoadPRESplitBackedge {#a29e212bd1ed59b642ae8f32393c188ae}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">std::optional&lt;bool&gt; llvm::GVNOptions::AllowLoadPRESplitBackedge</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 78 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/transforms/include/llvm/transforms/scalar/gvn-h">GVN.h</a>.</p>


<p>Referenced by <a href="#aa76f5d125c799144263a396569fc42fa">setLoadPRESplitBackedge</a>.</p>

</div>
</div>

### AllowMemDep {#a897e7d708586d9ba2dba64c12913bd78}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">std::optional&lt;bool&gt; llvm::GVNOptions::AllowMemDep</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 79 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/transforms/include/llvm/transforms/scalar/gvn-h">GVN.h</a>.</p>


<p>Referenced by <a href="#a8f1e7a8db3a9cbdc63b0c5d5b3396017">setMemDep</a>.</p>

</div>
</div>

### AllowMemorySSA {#abaf7ba38dcb90aa8e6199bfc371236f3}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">std::optional&lt;bool&gt; llvm::GVNOptions::AllowMemorySSA</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 80 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/transforms/include/llvm/transforms/scalar/gvn-h">GVN.h</a>.</p>


<p>Referenced by <a href="#ade043703ab858de7304776f0b79c79e0">setMemorySSA</a>.</p>

</div>
</div>

### AllowPRE {#a6ddc630f2fb57ab4a1f05c681519c4e7}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">std::optional&lt;bool&gt; llvm::GVNOptions::AllowPRE</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 75 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/transforms/include/llvm/transforms/scalar/gvn-h">GVN.h</a>.</p>


<p>Referenced by <a href="#a584701a8b7ab9cd7041180a30f0c21f1">setPRE</a>.</p>

</div>
</div>

</div>

<hr/>

The documentation for this struct was generated from the following file:

<ul>
<li><a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/transforms/include/llvm/transforms/scalar/gvn-h">GVN.h</a></li>
</ul>

<hr/>

<p class="doxyGeneratedBy">Generated via <a href="https://github.com/xpack/doxygen2docusaurus">doxygen2docusaurus</a> by <a href="https://www.doxygen.nl">Doxygen</a> 1.15.0.</p>

</div>
