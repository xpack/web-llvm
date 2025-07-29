---

# DO NOT EDIT!
# Automatically generated via doxygen2docusaurus by Doxygen.

slug: /api/classes/llvm/passconfigimpl
custom_edit_url: null
toc_max_heading_level: 4
keywords:
  - doxygen
  - reference
  - class

---

<div class="doxyPage">

# `PassConfigImpl` Class



## Declaration

<div class="doxyDeclaration">
class llvm::PassConfigImpl { ... }
</div>

## Public Member Attributes Index

<table class="doxyMembersIndex">

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/densemap">DenseMap</a>&lt; <a href="/web-llvm/docs/api/namespaces/llvm/#af8dcbb0c9f8f0e566a07488f68418d5b">AnalysisID</a>, <a href="/web-llvm/docs/api/classes/llvm/identifyingpassptr">IdentifyingPassPtr</a> &gt;</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a38252b37b428ccf0f3d32cc9a73a9449">TargetPasses</a></td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/smallvector">SmallVector</a>&lt; InsertedPass, 4 &gt;</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#af67847e84ee6b929f205b118666bb1aa">InsertedPasses</a></td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Store the pairs of &lt;<a href="/web-llvm/docs/api/namespaces/llvm/#af8dcbb0c9f8f0e566a07488f68418d5b">AnalysisID</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#af8dcbb0c9f8f0e566a07488f68418d5b">AnalysisID</a>&gt; of which the second pass is inserted after each instance of the first one. <a href="#af67847e84ee6b929f205b118666bb1aa">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

</table>


<p>Definition at line 394 of file <a href="/web-llvm/docs/api/files/lib/lib/codegen/targetpassconfig-cpp">TargetPassConfig.cpp</a>.</p>


<div class="doxySectionDef">

## Public Member Attributes

### InsertedPasses {#af67847e84ee6b929f205b118666bb1aa}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">SmallVector&lt;InsertedPass, 4&gt; llvm::PassConfigImpl::InsertedPasses</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Store the pairs of &lt;<a href="/web-llvm/docs/api/namespaces/llvm/#af8dcbb0c9f8f0e566a07488f68418d5b">AnalysisID</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#af8dcbb0c9f8f0e566a07488f68418d5b">AnalysisID</a>&gt; of which the second pass is inserted after each instance of the first one.</p>

<p>Definition at line 407 of file <a href="/web-llvm/docs/api/files/lib/lib/codegen/targetpassconfig-cpp">TargetPassConfig.cpp</a>.</p>

</div>
</div>

### TargetPasses {#a38252b37b428ccf0f3d32cc9a73a9449}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">DenseMap&lt;AnalysisID,IdentifyingPassPtr&gt; llvm::PassConfigImpl::TargetPasses</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 403 of file <a href="/web-llvm/docs/api/files/lib/lib/codegen/targetpassconfig-cpp">TargetPassConfig.cpp</a>.</p>

</div>
</div>

</div>

<hr/>

The documentation for this class was generated from the following file:

<ul>
<li><a href="/web-llvm/docs/api/files/lib/lib/codegen/targetpassconfig-cpp">TargetPassConfig.cpp</a></li>
</ul>

<hr/>

<p class="doxyGeneratedBy">Generated via <a href="https://github.com/xpack/doxygen2docusaurus">doxygen2docusaurus</a> by <a href="https://www.doxygen.nl">Doxygen</a> 1.15.0.</p>

</div>
