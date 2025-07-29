---

# DO NOT EDIT!
# Automatically generated via doxygen2docusaurus by Doxygen.

slug: /api/classes/llvm/vpbuilder/insertpointguard
custom_edit_url: null
toc_max_heading_level: 4
keywords:
  - doxygen
  - reference
  - class

---

<div class="doxyPage">

# `InsertPointGuard` Class

<p>RAII object that stores the current insertion point and restores it when the object is destroyed. <a href="#details">More...</a></p>

## Declaration

<div class="doxyDeclaration">
class llvm::VPBuilder::InsertPointGuard { ... }
</div>

## Included Headers

<div class="doxyIncludesList">#include "<a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/vectorize/loopvectorizationplanner-h">Transforms/Vectorize/LoopVectorizationPlanner.h</a>"
</div>

## Public Constructors Index

<table class="doxyMembersIndex">

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#aa5804dc65f1760580e8b9cf1c4a1e075">InsertPointGuard</a> (VPBuilder &amp;B)</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a402ec15b3d6434c963526a1e43b1964f">InsertPointGuard</a> (const InsertPointGuard &amp;)=delete</td>
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

## Public Destructor Index

<table class="doxyMembersIndex">

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#afd2f9cc21050d4a4f6e316851bcac337">~InsertPointGuard</a> ()</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/vpbuilder/insertpointguard">InsertPointGuard</a> &amp;</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ae40252074b34589a0c56217df40174ca">operator=</a> (const InsertPointGuard &amp;)=delete</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/vpbuilder">VPBuilder</a> &amp;</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ae81f7d4dfe0df072698093bb072d649c">Builder</a></td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/vpbasicblock">VPBasicBlock</a> *</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#acfb201b1321668f57158caf3eb1d0f65">Block</a></td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/vpbasicblock/#a2fc75e7b63babbf776ed29cfed87ae65">VPBasicBlock::iterator</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#adb3cbf5bcbb8ced0437646cdcac47492">Point</a></td>
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

<p>RAII object that stores the current insertion point and restores it when the object is destroyed.</p>

<p>Definition at line 270 of file <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/vectorize/loopvectorizationplanner-h">LoopVectorizationPlanner.h</a>.</p>


<div class="doxySectionDef">

## Public Constructors

### InsertPointGuard() {#aa5804dc65f1760580e8b9cf1c4a1e075}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">llvm::VPBuilder::InsertPointGuard::InsertPointGuard (<a href="/web-llvm/docs/api/classes/llvm/vpbuilder">VPBuilder</a> &amp; B)</td>
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



<p>Definition at line 276 of file <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/vectorize/loopvectorizationplanner-h">LoopVectorizationPlanner.h</a>.</p>


<p>References <a href="/web-llvm/docs/api/files/lib/lib/ir/builtingcs-cpp/#ae76959fe811ba090de4cba69ac00f1da">B</a>, <a href="/web-llvm/docs/api/classes/llvm/vpbuilder/#a3a85632d13a4a34fc9abb885d7d0b550">llvm::VPBuilder::getInsertBlock</a>, <a href="/web-llvm/docs/api/classes/llvm/vpbuilder/#a40184db12ba57b6b8ee938a31ce70bbe">llvm::VPBuilder::getInsertPoint</a> and <a href="/web-llvm/docs/api/classes/llvm/vpbuilder/#ad0f19352a13a5eb9f4c9b05385dff290">llvm::VPBuilder::VPBuilder</a>.</p>


<p>Referenced by <a href="#a402ec15b3d6434c963526a1e43b1964f">InsertPointGuard</a> and <a href="#ae40252074b34589a0c56217df40174ca">operator=</a>.</p>

</div>
</div>

### InsertPointGuard() {#a402ec15b3d6434c963526a1e43b1964f}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">llvm::VPBuilder::InsertPointGuard::InsertPointGuard (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/vpbuilder/insertpointguard">InsertPointGuard</a> &amp;)</td>
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



<p>Definition at line 279 of file <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/vectorize/loopvectorizationplanner-h">LoopVectorizationPlanner.h</a>.</p>


<p>Reference <a href="#aa5804dc65f1760580e8b9cf1c4a1e075">InsertPointGuard</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Public Destructor

### \~InsertPointGuard() {#afd2f9cc21050d4a4f6e316851bcac337}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">llvm::VPBuilder::InsertPointGuard::~InsertPointGuard ()</td>
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



<p>Definition at line 282 of file <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/vectorize/loopvectorizationplanner-h">LoopVectorizationPlanner.h</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Public Operators

### operator=() {#ae40252074b34589a0c56217df40174ca}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">InsertPointGuard &amp; llvm::VPBuilder::InsertPointGuard::operator= (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/vpbuilder/insertpointguard">InsertPointGuard</a> &amp;)</td>
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



<p>Definition at line 280 of file <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/vectorize/loopvectorizationplanner-h">LoopVectorizationPlanner.h</a>.</p>


<p>Reference <a href="#aa5804dc65f1760580e8b9cf1c4a1e075">InsertPointGuard</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Private Member Attributes

### Block {#acfb201b1321668f57158caf3eb1d0f65}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">VPBasicBlock* llvm::VPBuilder::InsertPointGuard::Block</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 272 of file <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/vectorize/loopvectorizationplanner-h">LoopVectorizationPlanner.h</a>.</p>

</div>
</div>

### Builder {#ae81f7d4dfe0df072698093bb072d649c}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">VPBuilder&amp; llvm::VPBuilder::InsertPointGuard::Builder</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 271 of file <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/vectorize/loopvectorizationplanner-h">LoopVectorizationPlanner.h</a>.</p>

</div>
</div>

### Point {#adb3cbf5bcbb8ced0437646cdcac47492}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">VPBasicBlock::iterator llvm::VPBuilder::InsertPointGuard::Point</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 273 of file <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/vectorize/loopvectorizationplanner-h">LoopVectorizationPlanner.h</a>.</p>

</div>
</div>

</div>

<hr/>

The documentation for this class was generated from the following file:

<ul>
<li><a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/vectorize/loopvectorizationplanner-h">LoopVectorizationPlanner.h</a></li>
</ul>

<hr/>

<p class="doxyGeneratedBy">Generated via <a href="https://github.com/xpack/doxygen2docusaurus">doxygen2docusaurus</a> by <a href="https://www.doxygen.nl">Doxygen</a> 1.15.0.</p>

</div>
