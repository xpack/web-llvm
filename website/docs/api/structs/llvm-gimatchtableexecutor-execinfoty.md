---

# DO NOT EDIT!
# Automatically generated via doxygen2docusaurus by Doxygen.

slug: /api/structs/llvm/gimatchtableexecutor/execinfoty
custom_edit_url: null
toc_max_heading_level: 4
keywords:
  - doxygen
  - reference
  - struct

---

<div class="doxyPage">

# `ExecInfoTy` Struct Template



## Declaration

<div class="doxyDeclaration">
template &lt;class PredicateBitset, class ComplexMatcherMemFn, class CustomRendererFn&gt;
struct llvm::GIMatchTableExecutor::ExecInfoTy&lt;PredicateBitset, ComplexMatcherMemFn, CustomRendererFn&gt; { ... }
</div>

## Included Headers

<div class="doxyIncludesList">#include "<a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/codegen/include/llvm/codegen/globalisel/gimatchtableexecutor-h">llvm/CodeGen/GlobalISel/GIMatchTableExecutor.h</a>"
</div>

## Public Constructors Index

<table class="doxyMembersIndex">

<tr class="doxyMemberIndexTemplate">
<td class="doxyMemberIndexTemplate" colspan="2"><div>template &lt; ... &gt;</div></td>
</tr>
<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemNoTypeNameTemplate" colspan="2" align="left" valign="top"><a href="#a74c4e8ea2b704b3f435bc9b39b40533c">ExecInfoTy</a> (const LLT *TypeObjects, size_t NumTypeObjects, const PredicateBitset *FeatureBitsets, const ComplexMatcherMemFn *ComplexPredicates, const CustomRendererFn *CustomRenderers)</td>
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

<tr class="doxyMemberIndexTemplate">
<td class="doxyMemberIndexTemplate" colspan="2"><div>template &lt; ... &gt;</div></td>
</tr>
<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemTypeTemplate" align="left" valign="top"><a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/llt">LLT</a> *</td>
<td class="doxyMemberIndexItemNameTemplate" align="left" valign="top"><a href="#a32f82439a0e15f9e31515bcc7150df94">TypeObjects</a></td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexTemplate">
<td class="doxyMemberIndexTemplate" colspan="2"><div>template &lt; ... &gt;</div></td>
</tr>
<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemTypeTemplate" align="left" valign="top"><a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> PredicateBitset *</td>
<td class="doxyMemberIndexItemNameTemplate" align="left" valign="top"><a href="#adfaf0a5cc6cb9b94145c30553caeace4">FeatureBitsets</a></td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexTemplate">
<td class="doxyMemberIndexTemplate" colspan="2"><div>template &lt; ... &gt;</div></td>
</tr>
<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemTypeTemplate" align="left" valign="top"><a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> ComplexMatcherMemFn *</td>
<td class="doxyMemberIndexItemNameTemplate" align="left" valign="top"><a href="#aa0441f44fd3b7133723f769c0da5bc10">ComplexPredicates</a></td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexTemplate">
<td class="doxyMemberIndexTemplate" colspan="2"><div>template &lt; ... &gt;</div></td>
</tr>
<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemTypeTemplate" align="left" valign="top"><a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> CustomRendererFn *</td>
<td class="doxyMemberIndexItemNameTemplate" align="left" valign="top"><a href="#a85c636b7f99842fe3e0756bccd52a6e5">CustomRenderers</a></td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexTemplate">
<td class="doxyMemberIndexTemplate" colspan="2"><div>template &lt; ... &gt;</div></td>
</tr>
<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemTypeTemplate" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/smalldensemap">SmallDenseMap</a>&lt; <a href="/web-llvm/docs/api/classes/llvm/llt">LLT</a>, unsigned, 64 &gt;</td>
<td class="doxyMemberIndexItemNameTemplate" align="left" valign="top"><a href="#a9ca01bc8856409a03f8fa62e4cbcd9ed">TypeIDMap</a></td>
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


<p>Definition at line 650 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/codegen/include/llvm/codegen/globalisel/gimatchtableexecutor-h">GIMatchTableExecutor.h</a>.</p>


<div class="doxySectionDef">

## Public Constructors

### ExecInfoTy() {#a74c4e8ea2b704b3f435bc9b39b40533c}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<div class="doxyMemberTemplate">template &lt;class PredicateBitset, class ComplexMatcherMemFn, class CustomRendererFn&gt;</div>
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">llvm::GIMatchTableExecutor::ExecInfoTy&lt; PredicateBitset, ComplexMatcherMemFn, CustomRendererFn &gt;::ExecInfoTy (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/llt">LLT</a> * TypeObjects, size_t NumTypeObjects, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> PredicateBitset * FeatureBitsets, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> ComplexMatcherMemFn * ComplexPredicates, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> CustomRendererFn * CustomRenderers)</td>
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



<p>Definition at line 651 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/codegen/include/llvm/codegen/globalisel/gimatchtableexecutor-h">GIMatchTableExecutor.h</a>.</p>


<p>References <a href="#aa0441f44fd3b7133723f769c0da5bc10">llvm::GIMatchTableExecutor::ExecInfoTy&lt; PredicateBitset, ComplexMatcherMemFn, CustomRendererFn &gt;::ComplexPredicates</a>, <a href="#a85c636b7f99842fe3e0756bccd52a6e5">llvm::GIMatchTableExecutor::ExecInfoTy&lt; PredicateBitset, ComplexMatcherMemFn, CustomRendererFn &gt;::CustomRenderers</a>, <a href="#adfaf0a5cc6cb9b94145c30553caeace4">llvm::GIMatchTableExecutor::ExecInfoTy&lt; PredicateBitset, ComplexMatcherMemFn, CustomRendererFn &gt;::FeatureBitsets</a>, <a href="/web-llvm/docs/api/files/lib/lib/support/md5-cpp/#ac0eafdc9ee161b71e7af98af736952fd">I</a>, <a href="#a9ca01bc8856409a03f8fa62e4cbcd9ed">llvm::GIMatchTableExecutor::ExecInfoTy&lt; PredicateBitset, ComplexMatcherMemFn, CustomRendererFn &gt;::TypeIDMap</a> and <a href="#a32f82439a0e15f9e31515bcc7150df94">llvm::GIMatchTableExecutor::ExecInfoTy&lt; PredicateBitset, ComplexMatcherMemFn, CustomRendererFn &gt;::TypeObjects</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Public Member Attributes

### ComplexPredicates {#aa0441f44fd3b7133723f769c0da5bc10}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<div class="doxyMemberTemplate">template &lt;class PredicateBitset, class ComplexMatcherMemFn, class CustomRendererFn&gt;</div>
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">const ComplexMatcherMemFn* llvm::GIMatchTableExecutor::ExecInfoTy&lt; PredicateBitset, ComplexMatcherMemFn, CustomRendererFn &gt;::ComplexPredicates</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 664 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/codegen/include/llvm/codegen/globalisel/gimatchtableexecutor-h">GIMatchTableExecutor.h</a>.</p>


<p>Referenced by <a href="#a74c4e8ea2b704b3f435bc9b39b40533c">llvm::GIMatchTableExecutor::ExecInfoTy&lt; PredicateBitset, ComplexMatcherMemFn, CustomRendererFn &gt;::ExecInfoTy</a> and <a href="/web-llvm/docs/api/classes/llvm/gimatchtableexecutor/#a0a2955a941402b4280306f0142b21061">llvm::GIMatchTableExecutor::executeMatchTable</a>.</p>

</div>
</div>

### CustomRenderers {#a85c636b7f99842fe3e0756bccd52a6e5}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<div class="doxyMemberTemplate">template &lt;class PredicateBitset, class ComplexMatcherMemFn, class CustomRendererFn&gt;</div>
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">const CustomRendererFn* llvm::GIMatchTableExecutor::ExecInfoTy&lt; PredicateBitset, ComplexMatcherMemFn, CustomRendererFn &gt;::CustomRenderers</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 665 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/codegen/include/llvm/codegen/globalisel/gimatchtableexecutor-h">GIMatchTableExecutor.h</a>.</p>


<p>Referenced by <a href="#a74c4e8ea2b704b3f435bc9b39b40533c">llvm::GIMatchTableExecutor::ExecInfoTy&lt; PredicateBitset, ComplexMatcherMemFn, CustomRendererFn &gt;::ExecInfoTy</a> and <a href="/web-llvm/docs/api/classes/llvm/gimatchtableexecutor/#a0a2955a941402b4280306f0142b21061">llvm::GIMatchTableExecutor::executeMatchTable</a>.</p>

</div>
</div>

### FeatureBitsets {#adfaf0a5cc6cb9b94145c30553caeace4}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<div class="doxyMemberTemplate">template &lt;class PredicateBitset, class ComplexMatcherMemFn, class CustomRendererFn&gt;</div>
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">const PredicateBitset* llvm::GIMatchTableExecutor::ExecInfoTy&lt; PredicateBitset, ComplexMatcherMemFn, CustomRendererFn &gt;::FeatureBitsets</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 663 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/codegen/include/llvm/codegen/globalisel/gimatchtableexecutor-h">GIMatchTableExecutor.h</a>.</p>


<p>Referenced by <a href="#a74c4e8ea2b704b3f435bc9b39b40533c">llvm::GIMatchTableExecutor::ExecInfoTy&lt; PredicateBitset, ComplexMatcherMemFn, CustomRendererFn &gt;::ExecInfoTy</a> and <a href="/web-llvm/docs/api/classes/llvm/gimatchtableexecutor/#a0a2955a941402b4280306f0142b21061">llvm::GIMatchTableExecutor::executeMatchTable</a>.</p>

</div>
</div>

### TypeIDMap {#a9ca01bc8856409a03f8fa62e4cbcd9ed}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<div class="doxyMemberTemplate">template &lt;class PredicateBitset, class ComplexMatcherMemFn, class CustomRendererFn&gt;</div>
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">SmallDenseMap&lt;LLT, unsigned, 64&gt; llvm::GIMatchTableExecutor::ExecInfoTy&lt; PredicateBitset, ComplexMatcherMemFn, CustomRendererFn &gt;::TypeIDMap</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 667 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/codegen/include/llvm/codegen/globalisel/gimatchtableexecutor-h">GIMatchTableExecutor.h</a>.</p>


<p>Referenced by <a href="#a74c4e8ea2b704b3f435bc9b39b40533c">llvm::GIMatchTableExecutor::ExecInfoTy&lt; PredicateBitset, ComplexMatcherMemFn, CustomRendererFn &gt;::ExecInfoTy</a> and <a href="/web-llvm/docs/api/classes/llvm/gimatchtableexecutor/#a0a2955a941402b4280306f0142b21061">llvm::GIMatchTableExecutor::executeMatchTable</a>.</p>

</div>
</div>

### TypeObjects {#a32f82439a0e15f9e31515bcc7150df94}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<div class="doxyMemberTemplate">template &lt;class PredicateBitset, class ComplexMatcherMemFn, class CustomRendererFn&gt;</div>
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">const LLT* llvm::GIMatchTableExecutor::ExecInfoTy&lt; PredicateBitset, ComplexMatcherMemFn, CustomRendererFn &gt;::TypeObjects</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 662 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/codegen/include/llvm/codegen/globalisel/gimatchtableexecutor-h">GIMatchTableExecutor.h</a>.</p>


<p>Referenced by <a href="#a74c4e8ea2b704b3f435bc9b39b40533c">llvm::GIMatchTableExecutor::ExecInfoTy&lt; PredicateBitset, ComplexMatcherMemFn, CustomRendererFn &gt;::ExecInfoTy</a> and <a href="/web-llvm/docs/api/classes/llvm/gimatchtableexecutor/#a0a2955a941402b4280306f0142b21061">llvm::GIMatchTableExecutor::executeMatchTable</a>.</p>

</div>
</div>

</div>

<hr/>

The documentation for this struct was generated from the following file:

<ul>
<li><a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/codegen/include/llvm/codegen/globalisel/gimatchtableexecutor-h">GIMatchTableExecutor.h</a></li>
</ul>

<hr/>

<p class="doxyGeneratedBy">Generated via <a href="https://xpack.github.io/doxygen2docusaurus">doxygen2docusaurus</a> 2.0.0 by <a href="https://www.doxygen.nl">Doxygen</a> 1.15.0.</p>

</div>
