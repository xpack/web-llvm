---

# DO NOT EDIT!
# Automatically generated via doxygen2docusaurus by Doxygen.

slug: /api/structs/anonymous-partialinlining-cpp-/functionoutlininginfo
custom_edit_url: null
toc_max_heading_level: 4
keywords:
  - doxygen
  - reference
  - struct

---

<div class="doxyPage">

# The `FunctionOutliningInfo` Struct Reference



## Declaration

<div class="doxyDeclaration">
struct anonymous{PartialInlining.cpp}::FunctionOutliningInfo { ... }
</div>

## Public Constructors Index

<table class="doxyMembersIndex">

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a499ce65b3ce70b19a57baaf626fd8c71">FunctionOutliningInfo</a> ()=default</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">unsigned</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a6fb932cf3bce1d6eed13ee21ca228a97">getNumInlinedBlocks</a> () const</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/smallvector">SmallVector</a>&lt; <a href="/web-llvm/docs/api/classes/llvm/basicblock">BasicBlock</a> *, 4 &gt;</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a6a053ec8c25e8a04257b8a55ea52116e">Entries</a></td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/basicblock">BasicBlock</a> *</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a6a5879becbc5af6475bd1cd3c1047eef">ReturnBlock</a> = nullptr</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/basicblock">BasicBlock</a> *</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a305456eb9eeef128076457cf801016d1">NonReturnBlock</a> = nullptr</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/smallvector">SmallVector</a>&lt; <a href="/web-llvm/docs/api/classes/llvm/basicblock">BasicBlock</a> *, 4 &gt;</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#aa4b6b4d3f209fa1a9ef63ad7441cb1e9">ReturnBlockPreds</a></td>
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


<p>Definition at line 147 of file <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/ipo/partialinlining-cpp">PartialInlining.cpp</a>.</p>


<div class="doxySectionDef">

## Public Constructors

### FunctionOutliningInfo() {#a499ce65b3ce70b19a57baaf626fd8c71}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">anonymous{PartialInlining.cpp}::FunctionOutliningInfo::FunctionOutliningInfo ()</td>
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



<p>Definition at line 148 of file <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/ipo/partialinlining-cpp">PartialInlining.cpp</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Public Member Functions

### getNumInlinedBlocks() {#a6fb932cf3bce1d6eed13ee21ca228a97}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">unsigned anonymous{PartialInlining.cpp}::FunctionOutliningInfo::getNumInlinedBlocks ()</td>
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



<p>Definition at line 152 of file <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/ipo/partialinlining-cpp">PartialInlining.cpp</a>.</p>


<p>Reference <a href="#a6a053ec8c25e8a04257b8a55ea52116e">Entries</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Public Member Attributes

### Entries {#a6a053ec8c25e8a04257b8a55ea52116e}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">SmallVector&lt;BasicBlock *, 4&gt; anonymous{PartialInlining.cpp}::FunctionOutliningInfo::Entries</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 156 of file <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/ipo/partialinlining-cpp">PartialInlining.cpp</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/structs/anonymous-partialinlining-cpp-/partialinlinerimpl/functioncloner/#a36fe9b66ac821eaf4492b176a50cdffb">anonymous{PartialInlining.cpp}::PartialInlinerImpl::FunctionCloner::FunctionCloner</a> and <a href="#a6fb932cf3bce1d6eed13ee21ca228a97">getNumInlinedBlocks</a>.</p>

</div>
</div>

### NonReturnBlock {#a305456eb9eeef128076457cf801016d1}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">BasicBlock* anonymous{PartialInlining.cpp}::FunctionOutliningInfo::NonReturnBlock = nullptr</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 162 of file <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/ipo/partialinlining-cpp">PartialInlining.cpp</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/structs/anonymous-partialinlining-cpp-/partialinlinerimpl/functioncloner/#a36fe9b66ac821eaf4492b176a50cdffb">anonymous{PartialInlining.cpp}::PartialInlinerImpl::FunctionCloner::FunctionCloner</a>.</p>

</div>
</div>

### ReturnBlock {#a6a5879becbc5af6475bd1cd3c1047eef}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">BasicBlock* anonymous{PartialInlining.cpp}::FunctionOutliningInfo::ReturnBlock = nullptr</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 159 of file <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/ipo/partialinlining-cpp">PartialInlining.cpp</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/structs/anonymous-partialinlining-cpp-/partialinlinerimpl/functioncloner/#a36fe9b66ac821eaf4492b176a50cdffb">anonymous{PartialInlining.cpp}::PartialInlinerImpl::FunctionCloner::FunctionCloner</a>.</p>

</div>
</div>

### ReturnBlockPreds {#aa4b6b4d3f209fa1a9ef63ad7441cb1e9}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">SmallVector&lt;BasicBlock *, 4&gt; anonymous{PartialInlining.cpp}::FunctionOutliningInfo::ReturnBlockPreds</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 165 of file <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/ipo/partialinlining-cpp">PartialInlining.cpp</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/structs/anonymous-partialinlining-cpp-/partialinlinerimpl/functioncloner/#a36fe9b66ac821eaf4492b176a50cdffb">anonymous{PartialInlining.cpp}::PartialInlinerImpl::FunctionCloner::FunctionCloner</a>.</p>

</div>
</div>

</div>

<hr/>

The documentation for this struct was generated from the following file:

<ul>
<li><a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/ipo/partialinlining-cpp">PartialInlining.cpp</a></li>
</ul>

<hr/>

<p class="doxyGeneratedBy">Generated via <a href="https://github.com/xpack/doxygen2docusaurus">doxygen2docusaurus</a> by <a href="https://www.doxygen.nl">Doxygen</a> 1.15.0.</p>

</div>
