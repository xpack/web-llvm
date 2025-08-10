---

# DO NOT EDIT!
# Automatically generated via doxygen2docusaurus by Doxygen.

slug: /api/classes/llvm/sandboxir/sandboxvectorizerpassbuilder
custom_edit_url: null
toc_max_heading_level: 4
keywords:
  - doxygen
  - reference
  - class

---

<div class="doxyPage">

# `SandboxVectorizerPassBuilder` Class



## Declaration

<div class="doxyDeclaration">
class llvm::sandboxir::SandboxVectorizerPassBuilder { ... }
</div>

## Included Headers

<div class="doxyIncludesList">#include "<a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/transforms/include/llvm/transforms/vectorize/include/llvm/transforms/vectorize/sandboxvectorizer/sandboxvectorizerpassbuilder-h">llvm/Transforms/Vectorize/SandboxVectorizer/SandboxVectorizerPassBuilder.h</a>"
</div>

## Public Static Functions Index

<table class="doxyMembersIndex">

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">static std::unique_ptr&lt; <a href="/web-llvm/docs/api/classes/llvm/sandboxir/functionpass">FunctionPass</a> &gt;</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a96d6b1f7d833da13be8ad18203510c17">createFunctionPass</a> (StringRef Name, StringRef Args)</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">static std::unique_ptr&lt; <a href="/web-llvm/docs/api/classes/llvm/sandboxir/regionpass">RegionPass</a> &gt;</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a34c78560b8a3f8d44084170e8ca1ed13">createRegionPass</a> (StringRef Name, StringRef Args)</td>
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


<p>Definition at line 22 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/transforms/include/llvm/transforms/vectorize/include/llvm/transforms/vectorize/sandboxvectorizer/sandboxvectorizerpassbuilder-h">SandboxVectorizerPassBuilder.h</a>.</p>


<div class="doxySectionDef">

## Public Static Functions

### createFunctionPass() {#a96d6b1f7d833da13be8ad18203510c17}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">std::unique_ptr&lt; sandboxir::FunctionPass &gt; llvm::sandboxir::SandboxVectorizerPassBuilder::createFunctionPass (<a href="/web-llvm/docs/api/classes/llvm/stringref">StringRef</a> Name, <a href="/web-llvm/docs/api/classes/llvm/stringref">StringRef</a> Args)</td>
</tr>
</table>
</td>
<td class="doxyMemberLabelsRight">
<span class="doxyMemberLabels">
<span class="doxyMemberLabel static">static</span>
</span>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Declaration at line 24 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/transforms/include/llvm/transforms/vectorize/include/llvm/transforms/vectorize/sandboxvectorizer/sandboxvectorizerpassbuilder-h">SandboxVectorizerPassBuilder.h</a>, definition at line 23 of file <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/vectorize/lib/transforms/vectorize/sandboxvectorizer/sandboxvectorizerpassbuilder-cpp">SandboxVectorizerPassBuilder.cpp</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/classes/llvm/sandboxvectorizerpass/#ae97d039e6b45730ff7a132e723b925e1">llvm::SandboxVectorizerPass::SandboxVectorizerPass</a>.</p>

</div>
</div>

### createRegionPass() {#a34c78560b8a3f8d44084170e8ca1ed13}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">std::unique_ptr&lt; sandboxir::RegionPass &gt; llvm::sandboxir::SandboxVectorizerPassBuilder::createRegionPass (<a href="/web-llvm/docs/api/classes/llvm/stringref">StringRef</a> Name, <a href="/web-llvm/docs/api/classes/llvm/stringref">StringRef</a> Args)</td>
</tr>
</table>
</td>
<td class="doxyMemberLabelsRight">
<span class="doxyMemberLabels">
<span class="doxyMemberLabel static">static</span>
</span>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Declaration at line 26 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/transforms/include/llvm/transforms/vectorize/include/llvm/transforms/vectorize/sandboxvectorizer/sandboxvectorizerpassbuilder-h">SandboxVectorizerPassBuilder.h</a>, definition at line 11 of file <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/vectorize/lib/transforms/vectorize/sandboxvectorizer/sandboxvectorizerpassbuilder-cpp">SandboxVectorizerPassBuilder.cpp</a>.</p>

</div>
</div>

</div>

<hr/>

The documentation for this class was generated from the following files:

<ul>
<li><a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/transforms/include/llvm/transforms/vectorize/include/llvm/transforms/vectorize/sandboxvectorizer/sandboxvectorizerpassbuilder-h">SandboxVectorizerPassBuilder.h</a></li>
<li><a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/vectorize/lib/transforms/vectorize/sandboxvectorizer/sandboxvectorizerpassbuilder-cpp">SandboxVectorizerPassBuilder.cpp</a></li>
</ul>

<hr/>

<p class="doxyGeneratedBy">Generated via <a href="https://xpack.github.io/doxygen2docusaurus">doxygen2docusaurus</a> 2.0.0 by <a href="https://www.doxygen.nl">Doxygen</a> 1.15.0.</p>

</div>
