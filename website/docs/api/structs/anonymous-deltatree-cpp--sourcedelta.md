---

# DO NOT EDIT!
# Automatically generated via doxygen2docusaurus by Doxygen.

slug: /api/structs/anonymous-deltatree-cpp-/sourcedelta
custom_edit_url: null
toc_max_heading_level: 4
keywords:
  - doxygen
  - reference
  - struct

---

<div class="doxyPage">

# `SourceDelta` Struct

<p><a href="/web-llvm/docs/api/structs/anonymous-deltatree-cpp-/sourcedelta">SourceDelta</a> - As code in the original input buffer is added and deleted, <a href="/web-llvm/docs/api/structs/anonymous-deltatree-cpp-/sourcedelta">SourceDelta</a> records are used to keep track of how the input SourceLocation object is mapped into the output buffer. <a href="#details">More...</a></p>

## Declaration

<div class="doxyDeclaration">
struct anonymous{DeltaTree.cpp}::SourceDelta { ... }
</div>

## Public Member Attributes Index

<table class="doxyMembersIndex">

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">unsigned</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a645fac4dad15bc20be3537887a7fa953">FileLoc</a></td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ab1aa86bc36b4f16f872619d117cee52e">Delta</a></td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">static <a href="/web-llvm/docs/api/structs/anonymous-deltatree-cpp-/sourcedelta">SourceDelta</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a10b1c635492d34dbd3411ac6eaef817f">get</a> (unsigned Loc, int D)</td>
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

<p><a href="/web-llvm/docs/api/structs/anonymous-deltatree-cpp-/sourcedelta">SourceDelta</a> - As code in the original input buffer is added and deleted, <a href="/web-llvm/docs/api/structs/anonymous-deltatree-cpp-/sourcedelta">SourceDelta</a> records are used to keep track of how the input SourceLocation object is mapped into the output buffer.</p>

<p>Definition at line 40 of file <a href="/web-llvm/docs/api/files/lib/lib/support/deltatree-cpp">DeltaTree.cpp</a>.</p>


<div class="doxySectionDef">

## Public Member Attributes

### Delta {#ab1aa86bc36b4f16f872619d117cee52e}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">int anonymous{DeltaTree.cpp}::SourceDelta::Delta</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 42 of file <a href="/web-llvm/docs/api/files/lib/lib/support/deltatree-cpp">DeltaTree.cpp</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/classes/anonymous-deltatree-cpp-/deltatreenode/#ad744e6529f224d58855be55473bb3d8e">anonymous{DeltaTree.cpp}::DeltaTreeNode::DoInsertion</a> and <a href="#a10b1c635492d34dbd3411ac6eaef817f">get</a>.</p>

</div>
</div>

### FileLoc {#a645fac4dad15bc20be3537887a7fa953}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">unsigned anonymous{DeltaTree.cpp}::SourceDelta::FileLoc</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 41 of file <a href="/web-llvm/docs/api/files/lib/lib/support/deltatree-cpp">DeltaTree.cpp</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/classes/anonymous-deltatree-cpp-/deltatreenode/#ad744e6529f224d58855be55473bb3d8e">anonymous{DeltaTree.cpp}::DeltaTreeNode::DoInsertion</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Public Static Functions

### get() {#a10b1c635492d34dbd3411ac6eaef817f}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">SourceDelta anonymous{DeltaTree.cpp}::SourceDelta::get (unsigned Loc, int D)</td>
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



<p>Definition at line 44 of file <a href="/web-llvm/docs/api/files/lib/lib/support/deltatree-cpp">DeltaTree.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/files/lib/lib/ir/builtingcs-cpp/#a6a9f043784cf87001c84980afa76da82">D</a> and <a href="#ab1aa86bc36b4f16f872619d117cee52e">Delta</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/classes/anonymous-deltatree-cpp-/deltatreenode/#ad744e6529f224d58855be55473bb3d8e">anonymous{DeltaTree.cpp}::DeltaTreeNode::DoInsertion</a>.</p>

</div>
</div>

</div>

<hr/>

The documentation for this struct was generated from the following file:

<ul>
<li><a href="/web-llvm/docs/api/files/lib/lib/support/deltatree-cpp">DeltaTree.cpp</a></li>
</ul>

<hr/>

<p class="doxyGeneratedBy">Generated via <a href="https://github.com/xpack/doxygen2docusaurus">doxygen2docusaurus</a> by <a href="https://www.doxygen.nl">Doxygen</a> 1.15.0.</p>

</div>
