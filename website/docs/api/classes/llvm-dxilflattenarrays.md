---

# DO NOT EDIT!
# Automatically generated via doxygen2docusaurus by Doxygen.

slug: /api/classes/llvm/dxilflattenarrays
custom_edit_url: null
toc_max_heading_level: 4
keywords:
  - doxygen
  - reference
  - class

---

<div class="doxyPage">

# `DXILFlattenArrays` Class

<p>A pass that transforms multidimensional arrays into one-dimensional arrays. <a href="#details">More...</a></p>

## Declaration

<div class="doxyDeclaration">
class llvm::DXILFlattenArrays { ... }
</div>

## Included Headers

<div class="doxyIncludesList">#include "<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/directx/dxilflattenarrays-h">Target/DirectX/DXILFlattenArrays.h</a>"
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a6c2e417054f84cfe4021992ebaa98169">run</a> (Module &amp;M, ModuleAnalysisManager &amp;)</td>
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

<p>A pass that transforms multidimensional arrays into one-dimensional arrays.</p>

<p>Definition at line 17 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/directx/dxilflattenarrays-h">DXILFlattenArrays.h</a>.</p>


<div class="doxySectionDef">

## Public Member Functions

### run() {#a6c2e417054f84cfe4021992ebaa98169}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">PreservedAnalyses DXILFlattenArrays::run (<a href="/web-llvm/docs/api/classes/llvm/module">Module</a> &amp; M, <a href="/web-llvm/docs/api/namespaces/llvm/#af9c9208365fd9ce11392b4d79485e259">ModuleAnalysisManager</a> &amp;)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Declaration at line 19 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/directx/dxilflattenarrays-h">DXILFlattenArrays.h</a>, definition at line 435 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/directx/dxilflattenarrays-cpp">DXILFlattenArrays.cpp</a>.</p>


<p>Reference <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/directx/dxilflattenarrays-cpp/#aaf0983b9048a116b67822e4cb1f52679">flattenArrays</a>.</p>

</div>
</div>

</div>

<hr/>

The documentation for this class was generated from the following files:

<ul>
<li><a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/directx/dxilflattenarrays-cpp">DXILFlattenArrays.cpp</a></li>
<li><a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/directx/dxilflattenarrays-h">DXILFlattenArrays.h</a></li>
</ul>

<hr/>

<p class="doxyGeneratedBy">Generated via <a href="https://github.com/xpack/doxygen2docusaurus">doxygen2docusaurus</a> by <a href="https://www.doxygen.nl">Doxygen</a> 1.15.0.</p>

</div>
