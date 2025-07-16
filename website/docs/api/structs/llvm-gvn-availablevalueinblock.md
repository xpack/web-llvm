---

# DO NOT EDIT!
# Automatically generated via doxygen2docusaurus by Doxygen.

slug: /api/structs/llvm/gvn/availablevalueinblock
custom_edit_url: null
toc_max_heading_level: 4
keywords:
  - doxygen
  - reference
  - struct

---

<div class="doxyPage">

# The `AvailableValueInBlock` Struct Reference

<p>Represents an <a href="/web-llvm/docs/api/structs/llvm/gvn/availablevalue">AvailableValue</a> which can be rematerialized at the end of the associated <a href="/web-llvm/docs/api/classes/llvm/basicblock">BasicBlock</a>. <a href="#details">More...</a></p>

## Declaration

<div class="doxyDeclaration">
struct llvm::gvn::AvailableValueInBlock { ... }
</div>

## Public Member Functions Index

<table class="doxyMembersIndex">

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/value">Value</a> *</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a44205c8ff3a436b67f525234d96df0bf">MaterializeAdjustedValue</a> (LoadInst *Load, GVNPass &amp;gvn) const</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Emit code at the end of this block to adjust the value defined here to the specified type. <a href="#a44205c8ff3a436b67f525234d96df0bf">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

</table>

## Public Member Attributes Index

<table class="doxyMembersIndex">

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/basicblock">BasicBlock</a> *</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#aa9760328b70e39d067e69f06fc777089">BB</a> = nullptr</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>BB - The basic block in question. <a href="#aa9760328b70e39d067e69f06fc777089">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/structs/llvm/gvn/availablevalue">AvailableValue</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a933a08dbc5d4952d1aeb8bb59dda3e6b">AV</a></td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>AV - The actual available value. <a href="#a933a08dbc5d4952d1aeb8bb59dda3e6b">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

</table>

## Public Static Functions Index

<table class="doxyMembersIndex">

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">static <a href="/web-llvm/docs/api/structs/llvm/gvn/availablevalueinblock">AvailableValueInBlock</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a3992e373c593770700e65bbd9a957cf7">get</a> (BasicBlock *BB, AvailableValue &amp;&amp;AV)</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">static <a href="/web-llvm/docs/api/structs/llvm/gvn/availablevalueinblock">AvailableValueInBlock</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a2b3759c8c4cc24dcceead45a434546d0">get</a> (BasicBlock *BB, Value *V, unsigned Offset=0)</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">static <a href="/web-llvm/docs/api/structs/llvm/gvn/availablevalueinblock">AvailableValueInBlock</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a311f188566b0d91b585df6c8bb31eb3a">getUndef</a> (BasicBlock *BB)</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">static <a href="/web-llvm/docs/api/structs/llvm/gvn/availablevalueinblock">AvailableValueInBlock</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#aa2a77bfeac83b06ea3d42c9ed38b511a">getSelect</a> (BasicBlock *BB, SelectInst *Sel, Value *V1, Value *V2)</td>
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

<p>Represents an <a href="/web-llvm/docs/api/structs/llvm/gvn/availablevalue">AvailableValue</a> which can be rematerialized at the end of the associated <a href="/web-llvm/docs/api/classes/llvm/basicblock">BasicBlock</a>.</p>

<p>Definition at line 295 of file <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/scalar/gvn-cpp">GVN.cpp</a>.</p>


<div class="doxySectionDef">

## Public Member Functions

### MaterializeAdjustedValue() {#a44205c8ff3a436b67f525234d96df0bf}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">Value * llvm::gvn::AvailableValueInBlock::MaterializeAdjustedValue (<a href="/web-llvm/docs/api/classes/llvm/loadinst">LoadInst</a> * Load, <a href="/web-llvm/docs/api/classes/llvm/gvnpass">GVNPass</a> &amp; gvn)</td>
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

<p>Emit code at the end of this block to adjust the value defined here to the specified type.</p>


<p>This handles various coercion cases.</p>


<p>Definition at line 325 of file <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/scalar/gvn-cpp">GVN.cpp</a>.</p>


<p>References <a href="#a933a08dbc5d4952d1aeb8bb59dda3e6b">AV</a> and <a href="#aa9760328b70e39d067e69f06fc777089">BB</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Public Member Attributes

### AV {#a933a08dbc5d4952d1aeb8bb59dda3e6b}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">AvailableValue llvm::gvn::AvailableValueInBlock::AV</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>AV - The actual available value.</p>

<p>Definition at line 300 of file <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/scalar/gvn-cpp">GVN.cpp</a>.</p>


<p>Referenced by <a href="#a3992e373c593770700e65bbd9a957cf7">get</a> and <a href="#a44205c8ff3a436b67f525234d96df0bf">MaterializeAdjustedValue</a>.</p>

</div>
</div>

### BB {#aa9760328b70e39d067e69f06fc777089}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">BasicBlock* llvm::gvn::AvailableValueInBlock::BB = nullptr</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>BB - The basic block in question.</p>

<p>Definition at line 297 of file <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/scalar/gvn-cpp">GVN.cpp</a>.</p>


<p>Referenced by <a href="#a3992e373c593770700e65bbd9a957cf7">get</a>, <a href="#a2b3759c8c4cc24dcceead45a434546d0">get</a>, <a href="#aa2a77bfeac83b06ea3d42c9ed38b511a">getSelect</a>, <a href="#a311f188566b0d91b585df6c8bb31eb3a">getUndef</a> and <a href="#a44205c8ff3a436b67f525234d96df0bf">MaterializeAdjustedValue</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Public Static Functions

### get() {#a3992e373c593770700e65bbd9a957cf7}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">AvailableValueInBlock llvm::gvn::AvailableValueInBlock::get (<a href="/web-llvm/docs/api/classes/llvm/basicblock">BasicBlock</a> * BB, <a href="/web-llvm/docs/api/structs/llvm/gvn/availablevalue">AvailableValue</a> &amp;&amp; AV)</td>
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



<p>Definition at line 302 of file <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/scalar/gvn-cpp">GVN.cpp</a>.</p>


<p>References <a href="#a933a08dbc5d4952d1aeb8bb59dda3e6b">AV</a> and <a href="#aa9760328b70e39d067e69f06fc777089">BB</a>.</p>


<p>Referenced by <a href="#a2b3759c8c4cc24dcceead45a434546d0">get</a>, <a href="#aa2a77bfeac83b06ea3d42c9ed38b511a">getSelect</a> and <a href="#a311f188566b0d91b585df6c8bb31eb3a">getUndef</a>.</p>

</div>
</div>

### get() {#a2b3759c8c4cc24dcceead45a434546d0}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">AvailableValueInBlock llvm::gvn::AvailableValueInBlock::get (<a href="/web-llvm/docs/api/classes/llvm/basicblock">BasicBlock</a> * BB, <a href="/web-llvm/docs/api/classes/llvm/value">Value</a> * V, unsigned Offset=0)</td>
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



<p>Definition at line 309 of file <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/scalar/gvn-cpp">GVN.cpp</a>.</p>


<p>References <a href="#aa9760328b70e39d067e69f06fc777089">BB</a>, <a href="/web-llvm/docs/api/structs/llvm/gvn/availablevalue/#a4e01d73dca4690562ee833fea9becbfb">llvm::gvn::AvailableValue::get</a>, <a href="#a3992e373c593770700e65bbd9a957cf7">get</a> and <a href="/web-llvm/docs/api/namespaces/llvm/#a05f5b9a11bdcc5feba62899f95dcf878a3134224cba2545bc57954d3b072aebb4">llvm::Offset</a>.</p>

</div>
</div>

### getSelect() {#aa2a77bfeac83b06ea3d42c9ed38b511a}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">AvailableValueInBlock llvm::gvn::AvailableValueInBlock::getSelect (<a href="/web-llvm/docs/api/classes/llvm/basicblock">BasicBlock</a> * BB, <a href="/web-llvm/docs/api/classes/llvm/selectinst">SelectInst</a> * Sel, <a href="/web-llvm/docs/api/classes/llvm/value">Value</a> * V1, <a href="/web-llvm/docs/api/classes/llvm/value">Value</a> * V2)</td>
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



<p>Definition at line 318 of file <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/scalar/gvn-cpp">GVN.cpp</a>.</p>


<p>References <a href="#aa9760328b70e39d067e69f06fc777089">BB</a>, <a href="#a3992e373c593770700e65bbd9a957cf7">get</a> and <a href="/web-llvm/docs/api/structs/llvm/gvn/availablevalue/#a21f6f28b6684fc17f3b56b76f379fc8d">llvm::gvn::AvailableValue::getSelect</a>.</p>

</div>
</div>

### getUndef() {#a311f188566b0d91b585df6c8bb31eb3a}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">AvailableValueInBlock llvm::gvn::AvailableValueInBlock::getUndef (<a href="/web-llvm/docs/api/classes/llvm/basicblock">BasicBlock</a> * BB)</td>
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



<p>Definition at line 314 of file <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/scalar/gvn-cpp">GVN.cpp</a>.</p>


<p>References <a href="#aa9760328b70e39d067e69f06fc777089">BB</a>, <a href="#a3992e373c593770700e65bbd9a957cf7">get</a> and <a href="/web-llvm/docs/api/structs/llvm/gvn/availablevalue/#acf794f14bc9b47394083056177f8d831">llvm::gvn::AvailableValue::getUndef</a>.</p>

</div>
</div>

</div>

<hr/>

The documentation for this struct was generated from the following file:

<ul>
<li><a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/scalar/gvn-cpp">GVN.cpp</a></li>
</ul>

<hr/>

<p class="doxyGeneratedBy">Generated via <a href="https://github.com/xpack/doxygen2docusaurus">doxygen2docusaurus</a> by <a href="https://www.doxygen.nl">Doxygen</a> 1.15.0.</p>

</div>
