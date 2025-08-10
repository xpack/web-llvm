---

# DO NOT EDIT!
# Automatically generated via doxygen2docusaurus by Doxygen.

slug: /api/classes/llvm/noinferencemodelrunner
custom_edit_url: null
toc_max_heading_level: 4
keywords:
  - doxygen
  - reference
  - class

---

<div class="doxyPage">

# `NoInferenceModelRunner` Class

<p>A pseudo model runner. <a href="#details">More...</a></p>

## Declaration

<div class="doxyDeclaration">
class llvm::NoInferenceModelRunner { ... }
</div>

## Included Headers

<div class="doxyIncludesList">#include "<a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/analysis/noinferencemodelrunner-h">llvm/Analysis/NoInferenceModelRunner.h</a>"
</div>

## Base class

<table class="doxyMembersIndex">

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">class</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/mlmodelrunner">MLModelRunner</a></td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p><a href="/web-llvm/docs/api/classes/llvm/mlmodelrunner">MLModelRunner</a> interface: abstraction of a mechanism for evaluating a ML model. <a href="/web-llvm/docs/api/classes/llvm/mlmodelrunner/#details">More...</a></p>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a5fcded37e0026e9276e93f861f2912e6">NoInferenceModelRunner</a> (LLVMContext &amp;Ctx, const std::vector&lt; TensorSpec &gt; &amp;Inputs)</td>
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

## Private Member Functions Index

<table class="doxyMembersIndex">

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">void *</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a4765fc10bfbf703232318d4a328681f6">evaluateUntyped</a> () override</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">static bool</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a36c5b2d1458599e71de79a49ebaf33bc">classof</a> (const MLModelRunner *R)</td>
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

<p>A pseudo model runner.</p>


<p>We use it to store feature values when collecting logs for the default policy, in 'development' mode, but never ask it to 'run'.</p>


<p>Definition at line 20 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/analysis/noinferencemodelrunner-h">NoInferenceModelRunner.h</a>.</p>


<div class="doxySectionDef">

## Public Constructors

### NoInferenceModelRunner() {#a5fcded37e0026e9276e93f861f2912e6}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">NoInferenceModelRunner::NoInferenceModelRunner (<a href="/web-llvm/docs/api/classes/llvm/llvmcontext">LLVMContext</a> &amp; Ctx, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> std::vector&lt; <a href="/web-llvm/docs/api/classes/llvm/tensorspec">TensorSpec</a> &gt; &amp; Inputs)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Declaration at line 22 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/analysis/noinferencemodelrunner-h">NoInferenceModelRunner.h</a>, definition at line 17 of file <a href="/web-llvm/docs/api/files/lib/lib/analysis/noinferencemodelrunner-cpp">NoInferenceModelRunner.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/classes/llvm/mlmodelrunner/#afa197695caf1d92f3efeddd1156d9cde">llvm::MLModelRunner::Ctx</a>, <a href="/web-llvm/docs/api/classes/llvm/mlmodelrunner/#ad3a2236255bf0a1c90006508a28a21fd">llvm::MLModelRunner::MLModelRunner</a>, <a href="/web-llvm/docs/api/classes/llvm/mlmodelrunner/#a81819d92a6045c9191f144ca86044b35a60832e2e4bbebccf26555b9ba658bad5">llvm::MLModelRunner::NoOp</a>, <a href="/web-llvm/docs/api/classes/llvm/mlmodelrunner/#a8b505a9ebc9388db882b94a334daa84c">llvm::MLModelRunner::setUpBufferForTensor</a> and <a href="/web-llvm/docs/api/namespaces/llvm/#a10f3d955592ae2bc745f57e5b48ae115">llvm::size</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Private Member Functions

### evaluateUntyped() {#a4765fc10bfbf703232318d4a328681f6}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void * llvm::NoInferenceModelRunner::evaluateUntyped ()</td>
</tr>
</table>
</td>
<td class="doxyMemberLabelsRight">
<span class="doxyMemberLabels">
<span class="doxyMemberLabel inline">inline</span>
<span class="doxyMemberLabel virtual">virtual</span>
</span>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 30 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/analysis/noinferencemodelrunner-h">NoInferenceModelRunner.h</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Public Static Functions

### classof() {#a36c5b2d1458599e71de79a49ebaf33bc}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool llvm::NoInferenceModelRunner::classof (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/mlmodelrunner">MLModelRunner</a> * R)</td>
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



<p>Definition at line 25 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/analysis/noinferencemodelrunner-h">NoInferenceModelRunner.h</a>.</p>


<p>References <a href="/web-llvm/docs/api/classes/llvm/mlmodelrunner/#ad3a2236255bf0a1c90006508a28a21fd">llvm::MLModelRunner::MLModelRunner</a> and <a href="/web-llvm/docs/api/classes/llvm/mlmodelrunner/#a81819d92a6045c9191f144ca86044b35a60832e2e4bbebccf26555b9ba658bad5">llvm::MLModelRunner::NoOp</a>.</p>

</div>
</div>

</div>

<hr/>

The documentation for this class was generated from the following files:

<ul>
<li><a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/analysis/noinferencemodelrunner-h">NoInferenceModelRunner.h</a></li>
<li><a href="/web-llvm/docs/api/files/lib/lib/analysis/noinferencemodelrunner-cpp">NoInferenceModelRunner.cpp</a></li>
</ul>

<hr/>

<p class="doxyGeneratedBy">Generated via <a href="https://xpack.github.io/doxygen2docusaurus">doxygen2docusaurus</a> 2.0.0 by <a href="https://www.doxygen.nl">Doxygen</a> 1.15.0.</p>

</div>
