---

# DO NOT EDIT!
# Automatically generated via doxygen2docusaurus by Doxygen.

slug: /api/structs/llvm/anonymous-amdgpusplitmodule-cpp-/splitgraph/edge
custom_edit_url: null
toc_max_heading_level: 4
keywords:
  - doxygen
  - reference
  - struct

---

<div class="doxyPage">

# The `Edge` Struct Reference

<p>An edge between two nodes. <a href="#details">More...</a></p>

## Declaration

<div class="doxyDeclaration">
struct llvm::anonymous{AMDGPUSplitModule.cpp}::SplitGraph::Edge { ... }
</div>

## Public Constructors Index

<table class="doxyMembersIndex">

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#aa3529470d4f761853821bde8996ab1e7">Edge</a> (Node *Src, Node *Dst, EdgeKind Kind)</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/anonymous-amdgpusplitmodule-cpp-/splitgraph/node">Node</a> *</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#abf56d6792265de2a6c12af2621ce2c34">Src</a></td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Source. <a href="#abf56d6792265de2a6c12af2621ce2c34">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/anonymous-amdgpusplitmodule-cpp-/splitgraph/node">Node</a> *</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ac1875f80e4e355c85878fe1948595b8f">Dst</a></td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Destination. <a href="#ac1875f80e4e355c85878fe1948595b8f">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/anonymous-amdgpusplitmodule-cpp-/splitgraph/#ae79abaadf50e5a44aed0e5169bedb4c9">EdgeKind</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a7ff12630fcdcbd9321fd0d6467b0e436">Kind</a></td>
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

<p>An edge between two nodes.</p>


<p>Edges are directional, and tagged with a "kind".</p>


<p>Definition at line 292 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/amdgpusplitmodule-cpp">AMDGPUSplitModule.cpp</a>.</p>


<div class="doxySectionDef">

## Public Constructors

### Edge() {#aa3529470d4f761853821bde8996ab1e7}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">llvm::anonymous{AMDGPUSplitModule.cpp}::SplitGraph::Edge::Edge (<a href="/web-llvm/docs/api/classes/llvm/anonymous-amdgpusplitmodule-cpp-/splitgraph/node">Node</a> * Src, <a href="/web-llvm/docs/api/classes/llvm/anonymous-amdgpusplitmodule-cpp-/splitgraph/node">Node</a> * Dst, <a href="/web-llvm/docs/api/classes/llvm/anonymous-amdgpusplitmodule-cpp-/splitgraph/#ae79abaadf50e5a44aed0e5169bedb4c9">EdgeKind</a> Kind)</td>
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



<p>Definition at line 293 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/amdgpusplitmodule-cpp">AMDGPUSplitModule.cpp</a>.</p>


<p>References <a href="#ac1875f80e4e355c85878fe1948595b8f">Dst</a>, <a href="#a7ff12630fcdcbd9321fd0d6467b0e436">Kind</a> and <a href="#abf56d6792265de2a6c12af2621ce2c34">Src</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Public Member Attributes

### Dst {#ac1875f80e4e355c85878fe1948595b8f}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">Node* llvm::anonymous{AMDGPUSplitModule.cpp}::SplitGraph::Edge::Dst</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Destination.</p>

<p>Definition at line 297 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/amdgpusplitmodule-cpp">AMDGPUSplitModule.cpp</a>.</p>


<p>Referenced by <a href="#aa3529470d4f761853821bde8996ab1e7">Edge</a>.</p>

</div>
</div>

### Kind {#a7ff12630fcdcbd9321fd0d6467b0e436}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">EdgeKind llvm::anonymous{AMDGPUSplitModule.cpp}::SplitGraph::Edge::Kind</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 298 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/amdgpusplitmodule-cpp">AMDGPUSplitModule.cpp</a>.</p>


<p>Referenced by <a href="#aa3529470d4f761853821bde8996ab1e7">Edge</a>.</p>

</div>
</div>

### Src {#abf56d6792265de2a6c12af2621ce2c34}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">Node* llvm::anonymous{AMDGPUSplitModule.cpp}::SplitGraph::Edge::Src</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Source.</p>

<p>Definition at line 296 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/amdgpusplitmodule-cpp">AMDGPUSplitModule.cpp</a>.</p>


<p>Referenced by <a href="#aa3529470d4f761853821bde8996ab1e7">Edge</a>.</p>

</div>
</div>

</div>

<hr/>

The documentation for this struct was generated from the following file:

<ul>
<li><a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/amdgpusplitmodule-cpp">AMDGPUSplitModule.cpp</a></li>
</ul>

<hr/>

<p class="doxyGeneratedBy">Generated via <a href="https://github.com/xpack/doxygen2docusaurus">doxygen2docusaurus</a> by <a href="https://www.doxygen.nl">Doxygen</a> 1.14.0.</p>

</div>
