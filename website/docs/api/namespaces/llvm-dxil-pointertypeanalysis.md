---

# DO NOT EDIT!
# Automatically generated via doxygen2docusaurus by Doxygen.

slug: /api/namespaces/llvm/dxil/pointertypeanalysis
custom_edit_url: null
toc_max_heading_level: 4
keywords:
  - doxygen
  - reference
  - namespace

---

<div class="doxyPage">

# `PointerTypeAnalysis` Namespace

<p>An analysis to compute the <span class="doxyComputerOutput">PointerTypes</span> for pointers in a <span class="doxyComputerOutput"><a href="/web-llvm/docs/api/classes/llvm/module">Module</a></span>. <a href="#details">More...</a></p>

## Definition

<div class="doxyDefinition">
namespace llvm::dxil::PointerTypeAnalysis { ... }
</div>

## Functions Index

<table class="doxyMembersIndex">

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/namespaces/llvm/dxil/#a57d4be532c191d9bb111cecdd1a63709">PointerTypeMap</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ae574a4c1d84b9e67bc94489f356805b4">run</a> (const Module &amp;M)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Compute the <span class="doxyComputerOutput"><a href="/web-llvm/docs/api/namespaces/llvm/dxil/#a57d4be532c191d9bb111cecdd1a63709">PointerTypeMap</a></span> for the module <span class="doxyComputerOutput">M</span>. <a href="#ae574a4c1d84b9e67bc94489f356805b4">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

</table>

## Description {#details}

<p>An analysis to compute the <span class="doxyComputerOutput">PointerTypes</span> for pointers in a <span class="doxyComputerOutput"><a href="/web-llvm/docs/api/classes/llvm/module">Module</a></span>.</p>


<p>Since this analysis is only run during codegen and the new pass manager doesn't support codegen passes, this is wrtten as a function in a namespace. It is very simple to transform it into a proper analysis pass. This code relies on typed pointers existing as LLVM types, but could be migrated to a custom <a href="/web-llvm/docs/api/classes/llvm/type">Type</a> if <a href="/web-llvm/docs/api/classes/llvm/pointertype">PointerType</a> loses typed support.</p>


<div class="doxySectionDef">

## Functions

### run() {#ae574a4c1d84b9e67bc94489f356805b4}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">PointerTypeMap llvm::dxil::PointerTypeAnalysis::run (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/module">Module</a> &amp; M)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Compute the <span class="doxyComputerOutput"><a href="/web-llvm/docs/api/namespaces/llvm/dxil/#a57d4be532c191d9bb111cecdd1a63709">PointerTypeMap</a></span> for the module <span class="doxyComputerOutput">M</span>.</p>

<p>Declaration at line 37 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/directx/lib/target/directx/directxirpasses/pointertypeanalysis-h">PointerTypeAnalysis.h</a>, definition at line 191 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/directx/lib/target/directx/directxirpasses/pointertypeanalysis-cpp">PointerTypeAnalysis.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/files/lib/lib/ir/builtingcs-cpp/#ae76959fe811ba090de4cba69ac00f1da">B</a>, <a href="/web-llvm/docs/api/namespaces/anonymous-pointertypeanalysis-cpp-/#ac10c52fc6c6c8328779f3175fce68067">anonymous{PointerTypeAnalysis.cpp}::classifyFunctionType</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/directx/lib/target/directx/directxirpasses/pointertypeanalysis-cpp/#ac6745cfa7af2beebe88a7d3609c7875d">classifyGlobalCtorPointerType</a>, <a href="/web-llvm/docs/api/namespaces/anonymous-pointertypeanalysis-cpp-/#aba29b35909e39c48517e7475412c776a">anonymous{PointerTypeAnalysis.cpp}::classifyPointerType</a>, <a href="/web-llvm/docs/api/files/lib/lib/support/md5-cpp/#a96d73bbd7af15cb1fc38c3f4a3bd82e9">F</a>, <a href="/web-llvm/docs/api/files/lib/lib/support/md5-cpp/#ad96b7cf3182ce2ba85e5a7a93b12c441">G</a> and <a href="/web-llvm/docs/api/files/lib/lib/support/md5-cpp/#ac0eafdc9ee161b71e7af98af736952fd">I</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/classes/anonymous-dxilprepare-cpp-/dxilpreparemodule/#a6bcc20d3d2e7ec05e259efe87ba8fd0c">anonymous{DXILPrepare.cpp}::DXILPrepareModule::runOnModule</a>.</p>

</div>
</div>

</div>

<hr/>

The documentation for this namespace was generated from the following files:

<ul>
<li><a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/directx/lib/target/directx/directxirpasses/pointertypeanalysis-cpp">PointerTypeAnalysis.cpp</a></li>
<li><a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/directx/lib/target/directx/directxirpasses/pointertypeanalysis-h">PointerTypeAnalysis.h</a></li>
</ul>

<hr/>

<p class="doxyGeneratedBy">Generated via <a href="https://github.com/xpack/doxygen2docusaurus">doxygen2docusaurus</a> by <a href="https://www.doxygen.nl">Doxygen</a> 1.15.0.</p>

</div>
