---

# DO NOT EDIT!
# Automatically generated via doxygen2docusaurus by Doxygen.

slug: /api/classes/llvm/pbqp/poolcostallocator
custom_edit_url: null
toc_max_heading_level: 4
keywords:
  - doxygen
  - reference
  - class

---

<div class="doxyPage">

# `PoolCostAllocator` Class Template



## Declaration

<div class="doxyDeclaration">
template &lt;typename VectorT, typename MatrixT&gt;
class llvm::PBQP::PoolCostAllocator&lt;VectorT, MatrixT&gt; { ... }
</div>

## Included Headers

<div class="doxyIncludesList">#include "<a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/codegen/include/llvm/codegen/pbqp/costallocator-h">llvm/CodeGen/PBQP/CostAllocator.h</a>"
</div>

## Public Member Typedefs Index

<table class="doxyMembersIndex">

<tr class="doxyMemberIndexTemplate">
<td class="doxyMemberIndexTemplate" colspan="2"><div>template &lt;typename VectorT, typename MatrixT&gt;</div></td>
</tr>
<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemTypeTemplate" align="left" valign="top">using</td>
<td class="doxyMemberIndexItemNameTemplate" align="left" valign="top"><a href="#a734cbf0601acd6261705b2bd5fcc56fd">Vector</a> = VectorT</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexTemplate">
<td class="doxyMemberIndexTemplate" colspan="2"><div>template &lt;typename VectorT, typename MatrixT&gt;</div></td>
</tr>
<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemTypeTemplate" align="left" valign="top">using</td>
<td class="doxyMemberIndexItemNameTemplate" align="left" valign="top"><a href="#aaea2d72f11d77ef8e8d7fb437fe11771">Matrix</a> = MatrixT</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexTemplate">
<td class="doxyMemberIndexTemplate" colspan="2"><div>template &lt;typename VectorT, typename MatrixT&gt;</div></td>
</tr>
<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemTypeTemplate" align="left" valign="top">using</td>
<td class="doxyMemberIndexItemNameTemplate" align="left" valign="top"><a href="#ad301f021ba079b855e00831836158a0e">VectorPtr</a> = typename <a href="/web-llvm/docs/api/classes/llvm/pbqp/valuepool/#ab7c10a02f8ab0a4e772aec0a15ab8687">VectorCostPool::PoolRef</a></td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexTemplate">
<td class="doxyMemberIndexTemplate" colspan="2"><div>template &lt;typename VectorT, typename MatrixT&gt;</div></td>
</tr>
<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemTypeTemplate" align="left" valign="top">using</td>
<td class="doxyMemberIndexItemNameTemplate" align="left" valign="top"><a href="#a1767d3783cff030897dba8e1d693df37">MatrixPtr</a> = typename <a href="/web-llvm/docs/api/classes/llvm/pbqp/valuepool/#ab7c10a02f8ab0a4e772aec0a15ab8687">MatrixCostPool::PoolRef</a></td>
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

## Private Member Typedefs Index

<table class="doxyMembersIndex">

<tr class="doxyMemberIndexTemplate">
<td class="doxyMemberIndexTemplate" colspan="2"><div>template &lt;typename VectorT, typename MatrixT&gt;</div></td>
</tr>
<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemTypeTemplate" align="left" valign="top">using</td>
<td class="doxyMemberIndexItemNameTemplate" align="left" valign="top"><a href="#a921be642ffdfa4f2e52d76c73aa94d30">VectorCostPool</a> = <a href="/web-llvm/docs/api/classes/llvm/pbqp/valuepool">ValuePool</a>&lt; VectorT &gt;</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexTemplate">
<td class="doxyMemberIndexTemplate" colspan="2"><div>template &lt;typename VectorT, typename MatrixT&gt;</div></td>
</tr>
<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemTypeTemplate" align="left" valign="top">using</td>
<td class="doxyMemberIndexItemNameTemplate" align="left" valign="top"><a href="#ab6c073262eb5c9cef2b8a7110b941570">MatrixCostPool</a> = <a href="/web-llvm/docs/api/classes/llvm/pbqp/valuepool">ValuePool</a>&lt; MatrixT &gt;</td>
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

<tr class="doxyMemberIndexTemplate">
<td class="doxyMemberIndexTemplate" colspan="2"><div>template &lt;typename VectorKeyT&gt;</div></td>
</tr>
<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemTypeTemplate" align="left" valign="top"><a href="#ad301f021ba079b855e00831836158a0e">VectorPtr</a></td>
<td class="doxyMemberIndexItemNameTemplate" align="left" valign="top"><a href="#a14f7bce6e353ae9af5e5b8fbc40c9fac">getVector</a> (VectorKeyT v)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexTemplate">
<td class="doxyMemberIndexTemplate" colspan="2"><div>template &lt;typename MatrixKeyT&gt;</div></td>
</tr>
<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemTypeTemplate" align="left" valign="top"><a href="#a1767d3783cff030897dba8e1d693df37">MatrixPtr</a></td>
<td class="doxyMemberIndexItemNameTemplate" align="left" valign="top"><a href="#a275c5aa3290b27bdb50d40712743610d">getMatrix</a> (MatrixKeyT m)</td>
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

## Private Member Attributes Index

<table class="doxyMembersIndex">

<tr class="doxyMemberIndexTemplate">
<td class="doxyMemberIndexTemplate" colspan="2"><div>template &lt;typename VectorT, typename MatrixT&gt;</div></td>
</tr>
<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemTypeTemplate" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/pbqp/valuepool">VectorCostPool</a></td>
<td class="doxyMemberIndexItemNameTemplate" align="left" valign="top"><a href="#a384b6bd6848a625f33fcd6949e94b7c1">VectorPool</a></td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexTemplate">
<td class="doxyMemberIndexTemplate" colspan="2"><div>template &lt;typename VectorT, typename MatrixT&gt;</div></td>
</tr>
<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemTypeTemplate" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/pbqp/valuepool">MatrixCostPool</a></td>
<td class="doxyMemberIndexItemNameTemplate" align="left" valign="top"><a href="#a28bbf00f33e1bf2ec12b155ca908bfc1">MatrixPool</a></td>
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


<p>Definition at line 107 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/codegen/include/llvm/codegen/pbqp/costallocator-h">CostAllocator.h</a>.</p>


<div class="doxySectionDef">

## Public Member Typedefs

### Matrix {#aaea2d72f11d77ef8e8d7fb437fe11771}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<div class="doxyMemberTemplate">template &lt;typename VectorT, typename MatrixT&gt;</div>
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">using llvm::PBQP::PoolCostAllocator&lt; VectorT, MatrixT &gt;::Matrix =  MatrixT</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 114 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/codegen/include/llvm/codegen/pbqp/costallocator-h">CostAllocator.h</a>.</p>

</div>
</div>

### MatrixPtr {#a1767d3783cff030897dba8e1d693df37}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<div class="doxyMemberTemplate">template &lt;typename VectorT, typename MatrixT&gt;</div>
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">using llvm::PBQP::PoolCostAllocator&lt; VectorT, MatrixT &gt;::MatrixPtr =  typename MatrixCostPool::PoolRef</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 116 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/codegen/include/llvm/codegen/pbqp/costallocator-h">CostAllocator.h</a>.</p>

</div>
</div>

### Vector {#a734cbf0601acd6261705b2bd5fcc56fd}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<div class="doxyMemberTemplate">template &lt;typename VectorT, typename MatrixT&gt;</div>
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">using llvm::PBQP::PoolCostAllocator&lt; VectorT, MatrixT &gt;::Vector =  VectorT</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 113 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/codegen/include/llvm/codegen/pbqp/costallocator-h">CostAllocator.h</a>.</p>

</div>
</div>

### VectorPtr {#ad301f021ba079b855e00831836158a0e}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<div class="doxyMemberTemplate">template &lt;typename VectorT, typename MatrixT&gt;</div>
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">using llvm::PBQP::PoolCostAllocator&lt; VectorT, MatrixT &gt;::VectorPtr =  typename VectorCostPool::PoolRef</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 115 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/codegen/include/llvm/codegen/pbqp/costallocator-h">CostAllocator.h</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Private Member Typedefs

### MatrixCostPool {#ab6c073262eb5c9cef2b8a7110b941570}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<div class="doxyMemberTemplate">template &lt;typename VectorT, typename MatrixT&gt;</div>
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">using llvm::PBQP::PoolCostAllocator&lt; VectorT, MatrixT &gt;::MatrixCostPool =  ValuePool&lt;MatrixT&gt;</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 110 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/codegen/include/llvm/codegen/pbqp/costallocator-h">CostAllocator.h</a>.</p>

</div>
</div>

### VectorCostPool {#a921be642ffdfa4f2e52d76c73aa94d30}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<div class="doxyMemberTemplate">template &lt;typename VectorT, typename MatrixT&gt;</div>
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">using llvm::PBQP::PoolCostAllocator&lt; VectorT, MatrixT &gt;::VectorCostPool =  ValuePool&lt;VectorT&gt;</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 109 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/codegen/include/llvm/codegen/pbqp/costallocator-h">CostAllocator.h</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Public Member Functions

### getMatrix() {#a275c5aa3290b27bdb50d40712743610d}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<div class="doxyMemberTemplate">template &lt;typename MatrixKeyT&gt;</div>
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">MatrixPtr llvm::PBQP::PoolCostAllocator&lt; VectorT, MatrixT &gt;::getMatrix (MatrixKeyT m)</td>
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



<p>Definition at line 122 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/codegen/include/llvm/codegen/pbqp/costallocator-h">CostAllocator.h</a>.</p>

</div>
</div>

### getVector() {#a14f7bce6e353ae9af5e5b8fbc40c9fac}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<div class="doxyMemberTemplate">template &lt;typename VectorKeyT&gt;</div>
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">VectorPtr llvm::PBQP::PoolCostAllocator&lt; VectorT, MatrixT &gt;::getVector (VectorKeyT v)</td>
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



<p>Definition at line 118 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/codegen/include/llvm/codegen/pbqp/costallocator-h">CostAllocator.h</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Private Member Attributes

### MatrixPool {#a28bbf00f33e1bf2ec12b155ca908bfc1}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<div class="doxyMemberTemplate">template &lt;typename VectorT, typename MatrixT&gt;</div>
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">MatrixCostPool llvm::PBQP::PoolCostAllocator&lt; VectorT, MatrixT &gt;::MatrixPool</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 128 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/codegen/include/llvm/codegen/pbqp/costallocator-h">CostAllocator.h</a>.</p>

</div>
</div>

### VectorPool {#a384b6bd6848a625f33fcd6949e94b7c1}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<div class="doxyMemberTemplate">template &lt;typename VectorT, typename MatrixT&gt;</div>
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">VectorCostPool llvm::PBQP::PoolCostAllocator&lt; VectorT, MatrixT &gt;::VectorPool</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 127 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/codegen/include/llvm/codegen/pbqp/costallocator-h">CostAllocator.h</a>.</p>

</div>
</div>

</div>

<hr/>

The documentation for this class was generated from the following file:

<ul>
<li><a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/codegen/include/llvm/codegen/pbqp/costallocator-h">CostAllocator.h</a></li>
</ul>

<hr/>

<p class="doxyGeneratedBy">Generated via <a href="https://github.com/xpack/doxygen2docusaurus">doxygen2docusaurus</a> by <a href="https://www.doxygen.nl">Doxygen</a> 1.15.0.</p>

</div>
