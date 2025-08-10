---

# DO NOT EDIT!
# Automatically generated via doxygen2docusaurus by Doxygen.

slug: /api/structs/llvm/hexagonvectorloopcarriedreusepass
custom_edit_url: null
toc_max_heading_level: 4
keywords:
  - doxygen
  - reference
  - struct

---

<div class="doxyPage">

# `HexagonVectorLoopCarriedReusePass` Struct

<p><a href="/web-llvm/docs/api/namespaces/llvm/hexagon">Hexagon</a> Vector <a href="/web-llvm/docs/api/classes/llvm/loop">Loop</a> Carried Reuse <a href="/web-llvm/docs/api/classes/llvm/pass">Pass</a>. <a href="#details">More...</a></p>

## Declaration

<div class="doxyDeclaration">
struct llvm::HexagonVectorLoopCarriedReusePass { ... }
</div>

## Included Headers

<div class="doxyIncludesList">#include "<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/hexagon/hexagonvectorloopcarriedreuse-h">Target/Hexagon/HexagonVectorLoopCarriedReuse.h</a>"
</div>

## Base struct

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

## Public Constructors Index

<table class="doxyMembersIndex">

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a52ba23deb54308528d86b65258256a45">HexagonVectorLoopCarriedReusePass</a> ()=default</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">PreservedAnalyses</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a32948988705da5dd73dba608197477fc">run</a> (Loop &amp;L, LoopAnalysisManager &amp;LAM, LoopStandardAnalysisResults &amp;AR, LPMUpdater &amp;U)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Run pass over the <a href="/web-llvm/docs/api/classes/llvm/loop">Loop</a>. <a href="#a32948988705da5dd73dba608197477fc">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

</table>

## Description {#details}

<p><a href="/web-llvm/docs/api/namespaces/llvm/hexagon">Hexagon</a> Vector <a href="/web-llvm/docs/api/classes/llvm/loop">Loop</a> Carried Reuse <a href="/web-llvm/docs/api/classes/llvm/pass">Pass</a>.</p>

<p>Definition at line 128 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/hexagon/hexagonvectorloopcarriedreuse-h">HexagonVectorLoopCarriedReuse.h</a>.</p>


<div class="doxySectionDef">

## Public Constructors

### HexagonVectorLoopCarriedReusePass() {#a52ba23deb54308528d86b65258256a45}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">llvm::HexagonVectorLoopCarriedReusePass::HexagonVectorLoopCarriedReusePass ()</td>
</tr>
</table>
</td>
<td class="doxyMemberLabelsRight">
<span class="doxyMemberLabels">
<span class="doxyMemberLabel default">default</span>
</span>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 130 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/hexagon/hexagonvectorloopcarriedreuse-h">HexagonVectorLoopCarriedReuse.h</a>.</p>


<p>Reference <a href="/web-llvm/docs/api/files/lib/lib/passes/passbuilderbindings-cpp/#a7cfe61417446ebb812e81293bde22a29">LAM</a>.</p>


<p>Referenced by <a href="#a32948988705da5dd73dba608197477fc">run</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Public Member Functions

### run() {#a32948988705da5dd73dba608197477fc}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">hexagon Hexagon specific predictive commoning for HVX false PreservedAnalyses HexagonVectorLoopCarriedReusePass::run (<a href="/web-llvm/docs/api/classes/llvm/loop">Loop</a> &amp; L, <a href="/web-llvm/docs/api/namespaces/llvm/#a58dde534a0ea2a23cb6c779c5c283f75">LoopAnalysisManager</a> &amp; LAM, <a href="/web-llvm/docs/api/structs/llvm/loopstandardanalysisresults">LoopStandardAnalysisResults</a> &amp; AR, <a href="/web-llvm/docs/api/classes/llvm/lpmupdater">LPMUpdater</a> &amp; U)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Run pass over the <a href="/web-llvm/docs/api/classes/llvm/loop">Loop</a>.</p>

<p>Declaration at line 133 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/hexagon/hexagonvectorloopcarriedreuse-h">HexagonVectorLoopCarriedReuse.h</a>, definition at line 222 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/hexagon/hexagonvectorloopcarriedreuse-cpp">HexagonVectorLoopCarriedReuse.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/classes/anonymous-hexagonvectorloopcarriedreuse-cpp-/hexagonvectorloopcarriedreuse/#a4ba607242f7d65239dced4700893c89e">anonymous{HexagonVectorLoopCarriedReuse.cpp}::HexagonVectorLoopCarriedReuse::HexagonVectorLoopCarriedReuse</a>, <a href="#a52ba23deb54308528d86b65258256a45">HexagonVectorLoopCarriedReusePass</a>, <a href="/web-llvm/docs/api/files/lib/lib/passes/passbuilderbindings-cpp/#a7cfe61417446ebb812e81293bde22a29">LAM</a> and <a href="#a32948988705da5dd73dba608197477fc">run</a>.</p>


<p>Referenced by <a href="#a32948988705da5dd73dba608197477fc">run</a>.</p>

</div>
</div>

</div>

<hr/>

The documentation for this struct was generated from the following files:

<ul>
<li><a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/hexagon/hexagonvectorloopcarriedreuse-cpp">HexagonVectorLoopCarriedReuse.cpp</a></li>
<li><a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/hexagon/hexagonvectorloopcarriedreuse-h">HexagonVectorLoopCarriedReuse.h</a></li>
</ul>

<hr/>

<p class="doxyGeneratedBy">Generated via <a href="https://xpack.github.io/doxygen2docusaurus">doxygen2docusaurus</a> 2.0.0 by <a href="https://www.doxygen.nl">Doxygen</a> 1.15.0.</p>

</div>
