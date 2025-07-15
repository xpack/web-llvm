---

# DO NOT EDIT!
# Automatically generated via doxygen2docusaurus by Doxygen.

slug: /api/classes/llvm/pbqp/regalloc/matrixmetadata
custom_edit_url: null
toc_max_heading_level: 4
keywords:
  - doxygen
  - reference
  - class

---

<div class="doxyPage">

# The `MatrixMetadata` Class Reference

<p><a href="/web-llvm/docs/api/classes/llvm/metadata">Metadata</a> to speed allocatability test. <a href="#details">More...</a></p>

## Declaration

<div class="doxyDeclaration">
class llvm::PBQP::RegAlloc::MatrixMetadata { ... }
</div>

## Included Headers

<div class="doxyIncludesList">#include "<a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/codegen/regallocpbqp-h">llvm/CodeGen/RegAllocPBQP.h</a>"
</div>

## Public Constructors Index

<table class="doxyMembersIndex">

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ad47dfee7af45cc0e38738efd527bab67">MatrixMetadata</a> (const Matrix &amp;M)</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a93a64a1d9905914190fc850f6fecce5a">MatrixMetadata</a> (const MatrixMetadata &amp;)=delete</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/pbqp/regalloc/matrixmetadata">MatrixMetadata</a> &amp;</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a39f043686676ac28f2454b95de1b64fc">operator=</a> (const MatrixMetadata &amp;)=delete</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a70cfee588d43c2c9561ec6ed4cb3b1d0">getWorstRow</a> () const</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">unsigned</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a080312d104644a378bb90577794df2b9">getWorstCol</a> () const</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> bool *</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a60a8470e33e7c0296e785bd145704cb1">getUnsafeRows</a> () const</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> bool *</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a1e1206ea94aceb1d3c86ff6dd97ce917">getUnsafeCols</a> () const</td>
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

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">unsigned</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a77974863ef03b258dfe888681975e96b">WorstRow</a> = 0</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">unsigned</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a87d5ccd39198259f3ff22d2affffd4f9">WorstCol</a> = 0</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">std::unique_ptr&lt; bool[]&gt;</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ac123e0fe6a794fd640ec3a268b6718c2">UnsafeRows</a></td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">std::unique_ptr&lt; bool[]&gt;</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#accad5ff67e9afef8b495bf2d152bd44e">UnsafeCols</a></td>
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

<p><a href="/web-llvm/docs/api/classes/llvm/metadata">Metadata</a> to speed allocatability test.</p>


<p>Keeps track of the number of infinities in each row and column.</p>


<p>Definition at line 53 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/codegen/regallocpbqp-h">RegAllocPBQP.h</a>.</p>


<div class="doxySectionDef">

## Public Constructors

### MatrixMetadata() {#ad47dfee7af45cc0e38738efd527bab67}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">llvm::PBQP::RegAlloc::MatrixMetadata::MatrixMetadata (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/pbqp/matrix">Matrix</a> &amp; M)</td>
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



<p>Definition at line 55 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/codegen/regallocpbqp-h">RegAllocPBQP.h</a>.</p>


<p>Referenced by <a href="#a93a64a1d9905914190fc850f6fecce5a">MatrixMetadata</a> and <a href="#a39f043686676ac28f2454b95de1b64fc">operator=</a>.</p>

</div>
</div>

### MatrixMetadata() {#a93a64a1d9905914190fc850f6fecce5a}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">llvm::PBQP::RegAlloc::MatrixMetadata::MatrixMetadata (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/pbqp/regalloc/matrixmetadata">MatrixMetadata</a> &amp;)</td>
</tr>
</table>
</td>
<td class="doxyMemberLabelsRight">
<span class="doxyMemberLabels">
<span class="doxyMemberLabel delete">delete</span>
</span>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 78 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/codegen/regallocpbqp-h">RegAllocPBQP.h</a>.</p>


<p>Reference <a href="#ad47dfee7af45cc0e38738efd527bab67">MatrixMetadata</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Public Operators

### operator=() {#a39f043686676ac28f2454b95de1b64fc}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">MatrixMetadata &amp; llvm::PBQP::RegAlloc::MatrixMetadata::operator= (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/pbqp/regalloc/matrixmetadata">MatrixMetadata</a> &amp;)</td>
</tr>
</table>
</td>
<td class="doxyMemberLabelsRight">
<span class="doxyMemberLabels">
<span class="doxyMemberLabel delete">delete</span>
</span>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 79 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/codegen/regallocpbqp-h">RegAllocPBQP.h</a>.</p>


<p>Reference <a href="#ad47dfee7af45cc0e38738efd527bab67">MatrixMetadata</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Public Member Functions

### getUnsafeCols() {#a1e1206ea94aceb1d3c86ff6dd97ce917}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">const bool * llvm::PBQP::RegAlloc::MatrixMetadata::getUnsafeCols ()</td>
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



<p>Definition at line 84 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/codegen/regallocpbqp-h">RegAllocPBQP.h</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/classes/llvm/pbqp/regalloc/nodemetadata/#af604de88cfa10f1c5c955d781ee30d7a">llvm::PBQP::RegAlloc::NodeMetadata::handleAddEdge</a> and <a href="/web-llvm/docs/api/classes/llvm/pbqp/regalloc/nodemetadata/#a1c74e0792948c70c031151491b34da14">llvm::PBQP::RegAlloc::NodeMetadata::handleRemoveEdge</a>.</p>

</div>
</div>

### getUnsafeRows() {#a60a8470e33e7c0296e785bd145704cb1}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">const bool * llvm::PBQP::RegAlloc::MatrixMetadata::getUnsafeRows ()</td>
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



<p>Definition at line 83 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/codegen/regallocpbqp-h">RegAllocPBQP.h</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/classes/llvm/pbqp/regalloc/nodemetadata/#af604de88cfa10f1c5c955d781ee30d7a">llvm::PBQP::RegAlloc::NodeMetadata::handleAddEdge</a> and <a href="/web-llvm/docs/api/classes/llvm/pbqp/regalloc/nodemetadata/#a1c74e0792948c70c031151491b34da14">llvm::PBQP::RegAlloc::NodeMetadata::handleRemoveEdge</a>.</p>

</div>
</div>

### getWorstCol() {#a080312d104644a378bb90577794df2b9}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">unsigned llvm::PBQP::RegAlloc::MatrixMetadata::getWorstCol ()</td>
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



<p>Definition at line 82 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/codegen/regallocpbqp-h">RegAllocPBQP.h</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/classes/llvm/pbqp/regalloc/nodemetadata/#af604de88cfa10f1c5c955d781ee30d7a">llvm::PBQP::RegAlloc::NodeMetadata::handleAddEdge</a> and <a href="/web-llvm/docs/api/classes/llvm/pbqp/regalloc/nodemetadata/#a1c74e0792948c70c031151491b34da14">llvm::PBQP::RegAlloc::NodeMetadata::handleRemoveEdge</a>.</p>

</div>
</div>

### getWorstRow() {#a70cfee588d43c2c9561ec6ed4cb3b1d0}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">unsigned llvm::PBQP::RegAlloc::MatrixMetadata::getWorstRow ()</td>
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



<p>Definition at line 81 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/codegen/regallocpbqp-h">RegAllocPBQP.h</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/classes/llvm/pbqp/regalloc/nodemetadata/#af604de88cfa10f1c5c955d781ee30d7a">llvm::PBQP::RegAlloc::NodeMetadata::handleAddEdge</a> and <a href="/web-llvm/docs/api/classes/llvm/pbqp/regalloc/nodemetadata/#a1c74e0792948c70c031151491b34da14">llvm::PBQP::RegAlloc::NodeMetadata::handleRemoveEdge</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Private Member Attributes

### UnsafeCols {#accad5ff67e9afef8b495bf2d152bd44e}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">std::unique_ptr&lt;bool[]&gt; llvm::PBQP::RegAlloc::MatrixMetadata::UnsafeCols</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 90 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/codegen/regallocpbqp-h">RegAllocPBQP.h</a>.</p>

</div>
</div>

### UnsafeRows {#ac123e0fe6a794fd640ec3a268b6718c2}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">std::unique_ptr&lt;bool[]&gt; llvm::PBQP::RegAlloc::MatrixMetadata::UnsafeRows</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 89 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/codegen/regallocpbqp-h">RegAllocPBQP.h</a>.</p>

</div>
</div>

### WorstCol {#a87d5ccd39198259f3ff22d2affffd4f9}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">unsigned llvm::PBQP::RegAlloc::MatrixMetadata::WorstCol = 0</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 88 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/codegen/regallocpbqp-h">RegAllocPBQP.h</a>.</p>

</div>
</div>

### WorstRow {#a77974863ef03b258dfe888681975e96b}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">unsigned llvm::PBQP::RegAlloc::MatrixMetadata::WorstRow = 0</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 87 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/codegen/regallocpbqp-h">RegAllocPBQP.h</a>.</p>

</div>
</div>

</div>

<hr/>

The documentation for this class was generated from the following file:

<ul>
<li><a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/codegen/regallocpbqp-h">RegAllocPBQP.h</a></li>
</ul>

<hr/>

<p class="doxyGeneratedBy">Generated via <a href="https://github.com/xpack/doxygen2docusaurus">doxygen2docusaurus</a> by <a href="https://www.doxygen.nl">Doxygen</a> 1.14.0.</p>

</div>
