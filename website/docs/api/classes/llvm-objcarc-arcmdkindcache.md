---

# DO NOT EDIT!
# Automatically generated via doxygen2docusaurus by Doxygen.

slug: /api/classes/llvm/objcarc/arcmdkindcache
custom_edit_url: null
toc_max_heading_level: 4
keywords:
  - doxygen
  - reference
  - class

---

<div class="doxyPage">

# `ARCMDKindCache` Class

<p>A cache of MDKinds used by various ARC optimizations. <a href="#details">More...</a></p>

## Declaration

<div class="doxyDeclaration">
class llvm::objcarc::ARCMDKindCache { ... }
</div>

## Included Headers

<div class="doxyIncludesList">#include "<a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/analysis/objcarcanalysisutils-h">llvm/Analysis/ObjCARCAnalysisUtils.h</a>"
</div>

## Public Member Functions Index

<table class="doxyMembersIndex">

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">void</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ac5f061881a93af61a34d1dca1a0036dc">init</a> (Module *Mod)</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a062cf10f8ea9fc45291d700b2e8da648">get</a> (ARCMDKindID ID)</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/module">Module</a> *</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a672436be02f680814f91457bb86982f3">M</a></td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">std::optional&lt; unsigned &gt;</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ac8b4801abadb738d089609a55e8897ef">ImpreciseReleaseMDKind</a></td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>The <a href="/web-llvm/docs/api/classes/llvm/metadata">Metadata</a> Kind for clang.imprecise_release metadata. <a href="#ac8b4801abadb738d089609a55e8897ef">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">std::optional&lt; unsigned &gt;</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a49af42379d07927d519cf8896e6fad1d">CopyOnEscapeMDKind</a></td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>The <a href="/web-llvm/docs/api/classes/llvm/metadata">Metadata</a> Kind for clang.arc.copy_on_escape metadata. <a href="#a49af42379d07927d519cf8896e6fad1d">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">std::optional&lt; unsigned &gt;</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ad9bfaab1fca4dca98659f984075b682f">NoObjCARCExceptionsMDKind</a></td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>The <a href="/web-llvm/docs/api/classes/llvm/metadata">Metadata</a> Kind for clang.arc.no_objc_arc_exceptions metadata. <a href="#ad9bfaab1fca4dca98659f984075b682f">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

</table>

## Description {#details}

<p>A cache of MDKinds used by various ARC optimizations.</p>

<p>Definition at line 228 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/analysis/objcarcanalysisutils-h">ObjCARCAnalysisUtils.h</a>.</p>


<div class="doxySectionDef">

## Public Member Functions

### get() {#a062cf10f8ea9fc45291d700b2e8da648}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">unsigned llvm::objcarc::ARCMDKindCache::get (<a href="/web-llvm/docs/api/namespaces/llvm/objcarc/#a749ec59e4812b00a3cf7e7036fb39c06">ARCMDKindID</a> ID)</td>
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



<p>Definition at line 248 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/analysis/objcarcanalysisutils-h">ObjCARCAnalysisUtils.h</a>.</p>


<p>References <a href="/web-llvm/docs/api/namespaces/llvm/objcarc/#a749ec59e4812b00a3cf7e7036fb39c06a385ea43b0901f4c23e77e7e1c92026fb">llvm::objcarc::CopyOnEscape</a>, <a href="/web-llvm/docs/api/namespaces/llvm/objcarc/#a749ec59e4812b00a3cf7e7036fb39c06ab1ec2e3fd61b7a763d9173e07016906c">llvm::objcarc::ImpreciseRelease</a>, <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/support/errorhandling-h/#ace243f5c25697a1107cce46626b3dc94">llvm_unreachable</a> and <a href="/web-llvm/docs/api/namespaces/llvm/objcarc/#a749ec59e4812b00a3cf7e7036fb39c06adfb5efff844959d1f14f5450c9cefe8f">llvm::objcarc::NoObjCARCExceptions</a>.</p>

</div>
</div>

### init() {#ac5f061881a93af61a34d1dca1a0036dc}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void llvm::objcarc::ARCMDKindCache::init (<a href="/web-llvm/docs/api/classes/llvm/module">Module</a> * Mod)</td>
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



<p>Definition at line 241 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/analysis/objcarcanalysisutils-h">ObjCARCAnalysisUtils.h</a>.</p>


<p>Reference <a href="/web-llvm/docs/api/namespaces/llvm/#a9db8c44b250b90e3ab7e4d144e7c9c2ea7aeb0277500c86e4aa6bd23f9a737942">llvm::Mod</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Private Member Attributes

### CopyOnEscapeMDKind {#a49af42379d07927d519cf8896e6fad1d}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">std::optional&lt;unsigned&gt; llvm::objcarc::ARCMDKindCache::CopyOnEscapeMDKind</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>The <a href="/web-llvm/docs/api/classes/llvm/metadata">Metadata</a> Kind for clang.arc.copy_on_escape metadata.</p>

<p>Definition at line 235 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/analysis/objcarcanalysisutils-h">ObjCARCAnalysisUtils.h</a>.</p>

</div>
</div>

### ImpreciseReleaseMDKind {#ac8b4801abadb738d089609a55e8897ef}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">std::optional&lt;unsigned&gt; llvm::objcarc::ARCMDKindCache::ImpreciseReleaseMDKind</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>The <a href="/web-llvm/docs/api/classes/llvm/metadata">Metadata</a> Kind for clang.imprecise_release metadata.</p>

<p>Definition at line 232 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/analysis/objcarcanalysisutils-h">ObjCARCAnalysisUtils.h</a>.</p>

</div>
</div>

### M {#a672436be02f680814f91457bb86982f3}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">Module* llvm::objcarc::ARCMDKindCache::M</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 229 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/analysis/objcarcanalysisutils-h">ObjCARCAnalysisUtils.h</a>.</p>

</div>
</div>

### NoObjCARCExceptionsMDKind {#ad9bfaab1fca4dca98659f984075b682f}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">std::optional&lt;unsigned&gt; llvm::objcarc::ARCMDKindCache::NoObjCARCExceptionsMDKind</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>The <a href="/web-llvm/docs/api/classes/llvm/metadata">Metadata</a> Kind for clang.arc.no_objc_arc_exceptions metadata.</p>

<p>Definition at line 238 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/analysis/objcarcanalysisutils-h">ObjCARCAnalysisUtils.h</a>.</p>

</div>
</div>

</div>

<hr/>

The documentation for this class was generated from the following file:

<ul>
<li><a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/analysis/objcarcanalysisutils-h">ObjCARCAnalysisUtils.h</a></li>
</ul>

<hr/>

<p class="doxyGeneratedBy">Generated via <a href="https://github.com/xpack/doxygen2docusaurus">doxygen2docusaurus</a> by <a href="https://www.doxygen.nl">Doxygen</a> 1.15.0.</p>

</div>
