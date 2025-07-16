---

# DO NOT EDIT!
# Automatically generated via doxygen2docusaurus by Doxygen.

slug: /api/classes/llvm/dxilintrinsicexpansion
custom_edit_url: null
toc_max_heading_level: 4
keywords:
  - doxygen
  - reference
  - class

---

<div class="doxyPage">

# The `DXILIntrinsicExpansion` Class Reference

<p>A pass that transforms DXIL Intrinsics that don't have DXIL opCodes. <a href="#details">More...</a></p>

## Declaration

<div class="doxyDeclaration">
class llvm::DXILIntrinsicExpansion { ... }
</div>

## Included Headers

<div class="doxyIncludesList">#include "<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/directx/dxilintrinsicexpansion-h">Target/DirectX/DXILIntrinsicExpansion.h</a>"
</div>

## Base class

<table class="doxyMembersIndex">

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">struct</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="/web-llvm/docs/api/structs/llvm/passinfomixin">PassInfoMixin&lt;DerivedT&gt;</a></td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>A CRTP mix-in to automatically provide informational APIs needed for passes. <a href="/web-llvm/docs/api/structs/llvm/passinfomixin/#details">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

</table>

## Public Member Functions Index

<table class="doxyMembersIndex">

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">PreservedAnalyses</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a8c44e930b068104f227b3c1b0f4f3151">run</a> (Module &amp;M, ModuleAnalysisManager &amp;)</td>
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

<p>A pass that transforms DXIL Intrinsics that don't have DXIL opCodes.</p>

<p>Definition at line 18 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/directx/dxilintrinsicexpansion-h">DXILIntrinsicExpansion.h</a>.</p>


<div class="doxySectionDef">

## Public Member Functions

### run() {#a8c44e930b068104f227b3c1b0f4f3151}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">PreservedAnalyses DXILIntrinsicExpansion::run (<a href="/web-llvm/docs/api/classes/llvm/module">Module</a> &amp; M, <a href="/web-llvm/docs/api/namespaces/llvm/#af9c9208365fd9ce11392b4d79485e259">ModuleAnalysisManager</a> &amp;)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Declaration at line 20 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/directx/dxilintrinsicexpansion-h">DXILIntrinsicExpansion.h</a>, definition at line 614 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/directx/dxilintrinsicexpansion-cpp">DXILIntrinsicExpansion.cpp</a>.</p>


<p>Reference <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/directx/dxilintrinsicexpansion-cpp/#a21f26e994a4354c47e6b7752799e8672">expansionIntrinsics</a>.</p>

</div>
</div>

</div>

<hr/>

The documentation for this class was generated from the following files:

<ul>
<li><a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/directx/dxilintrinsicexpansion-cpp">DXILIntrinsicExpansion.cpp</a></li>
<li><a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/directx/dxilintrinsicexpansion-h">DXILIntrinsicExpansion.h</a></li>
</ul>

<hr/>

<p class="doxyGeneratedBy">Generated via <a href="https://github.com/xpack/doxygen2docusaurus">doxygen2docusaurus</a> by <a href="https://www.doxygen.nl">Doxygen</a> 1.15.0.</p>

</div>
