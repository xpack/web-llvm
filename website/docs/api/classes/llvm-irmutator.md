---

# DO NOT EDIT!
# Automatically generated via doxygen2docusaurus by Doxygen.

slug: /api/classes/llvm/irmutator
custom_edit_url: null
toc_max_heading_level: 4
keywords:
  - doxygen
  - reference
  - class

---

<div class="doxyPage">

# The `IRMutator` Class Reference

<p>Entry point for configuring and running IR mutations. <a href="#details">More...</a></p>

## Declaration

<div class="doxyDeclaration">
class llvm::IRMutator { ... }
</div>

## Included Headers

<div class="doxyIncludesList">#include "<a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/fuzzmutate/irmutator-h">llvm/FuzzMutate/IRMutator.h</a>"
</div>

## Public Constructors Index

<table class="doxyMembersIndex">

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a3598020d849bbf2b263a2d193c9e37e0">IRMutator</a> (std::vector&lt; TypeGetter &gt; &amp;&amp;AllowedTypes, std::vector&lt; std::unique_ptr&lt; IRMutationStrategy &gt; &gt; &amp;&amp;Strategies)</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">void</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a46815db3771a03cb8892981fd9649760">mutateModule</a> (Module &amp;M, int Seed, size_t MaxSize)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Mutate given module. <a href="#a46815db3771a03cb8892981fd9649760">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

</table>

## Private Member Attributes Index

<table class="doxyMembersIndex">

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">std::vector&lt; <a href="/web-llvm/docs/api/namespaces/llvm/#a6461079ae46b652ff58d740bae43a1b3">TypeGetter</a> &gt;</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#adeee3a0217500a276f18db432cce37f8">AllowedTypes</a></td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">std::vector&lt; std::unique_ptr&lt; <a href="/web-llvm/docs/api/classes/llvm/irmutationstrategy">IRMutationStrategy</a> &gt; &gt;</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ae02478eda563daaad061111a9701f7f6">Strategies</a></td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">static size_t</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#af5fee21c07b28b75bf37c6f85d8a8740">getModuleSize</a> (const Module &amp;M)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Calculate the size of module as the number of objects in it, i.e. <a href="#af5fee21c07b28b75bf37c6f85d8a8740">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

</table>

## Description {#details}

<p>Entry point for configuring and running IR mutations.</p>

<p>Definition at line 63 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/fuzzmutate/irmutator-h">IRMutator.h</a>.</p>


<div class="doxySectionDef">

## Public Constructors

### IRMutator() {#a3598020d849bbf2b263a2d193c9e37e0}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">llvm::IRMutator::IRMutator (std::vector&lt; <a href="/web-llvm/docs/api/namespaces/llvm/#a6461079ae46b652ff58d740bae43a1b3">TypeGetter</a> &gt; &amp;&amp; AllowedTypes, std::vector&lt; std::unique_ptr&lt; <a href="/web-llvm/docs/api/classes/llvm/irmutationstrategy">IRMutationStrategy</a> &gt; &gt; &amp;&amp; Strategies)</td>
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



<p>Definition at line 68 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/fuzzmutate/irmutator-h">IRMutator.h</a>.</p>


<p>Reference <a href="/web-llvm/docs/api/namespaces/llvm/#abfc9c7ecf70f66901e439f7c04ef3dbb">llvm::move</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Public Member Functions

### mutateModule() {#a46815db3771a03cb8892981fd9649760}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void IRMutator::mutateModule (<a href="/web-llvm/docs/api/classes/llvm/module">Module</a> &amp; M, int Seed, size_t MaxSize)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Mutate given module.</p>


<p>No change will be made if no strategy is selected.</p>


<dl class="doxyParamsList">
<dt class="doxyParamsTableTitle">Parameters</dt>
<dd>
<table class="doxyParamsTable">
<tr class="doxyParamItem">
<td class="doxyParamItemName">M</td>
<td class="doxyParamItemDescription"><p>module to mutate</p></td>
</tr>
<tr class="doxyParamItem">
<td class="doxyParamItemName">Seed</td>
<td class="doxyParamItemDescription"><p>seed for random mutation</p></td>
</tr>
<tr class="doxyParamItem">
<td class="doxyParamItemName">MaxSize</td>
<td class="doxyParamItemDescription"><p>max module size (see getModuleSize)</p></td>
</tr>
</table>
</dd>
</dl>

<p>Declaration at line 85 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/fuzzmutate/irmutator-h">IRMutator.h</a>, definition at line 64 of file <a href="/web-llvm/docs/api/files/lib/lib/fuzzmutate/irmutator-cpp">IRMutator.cpp</a>.</p>


<p>References <a href="#af5fee21c07b28b75bf37c6f85d8a8740">getModuleSize</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a6695fbc0cb8edb5aede4af74f2ef95d0">llvm::makeSampler</a> and <a href="/web-llvm/docs/api/files/lib/lib/support/randomnumbergenerator-cpp/#a0c7bb0b4761ae4c3f875fb9b0a235a93">Seed</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Private Member Attributes

### AllowedTypes {#adeee3a0217500a276f18db432cce37f8}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">std::vector&lt;TypeGetter&gt; llvm::IRMutator::AllowedTypes</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 64 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/fuzzmutate/irmutator-h">IRMutator.h</a>.</p>

</div>
</div>

### Strategies {#ae02478eda563daaad061111a9701f7f6}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">std::vector&lt;std::unique_ptr&lt;IRMutationStrategy&gt; &gt; llvm::IRMutator::Strategies</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 65 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/fuzzmutate/irmutator-h">IRMutator.h</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Public Static Functions

### getModuleSize() {#af5fee21c07b28b75bf37c6f85d8a8740}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">size_t llvm::IRMutator::getModuleSize (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/module">Module</a> &amp; M)</td>
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

<p>Calculate the size of module as the number of objects in it, i.e.</p>


<p>instructions, basic blocks, functions, and aliases.</p>


<dl class="doxyParamsList">
<dt class="doxyParamsTableTitle">Parameters</dt>
<dd>
<table class="doxyParamsTable">
<tr class="doxyParamItem">
<td class="doxyParamItemName">M</td>
<td class="doxyParamItemDescription"><p>module</p></td>
</tr>
</table>
</dd>
</dl>

<dl class="doxySectionUser">
<dt>Returns</dt>
<dd><p>number of objects in module</p></dd>
</dl>


<p>Declaration at line 78 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/fuzzmutate/irmutator-h">IRMutator.h</a>, definition at line 60 of file <a href="/web-llvm/docs/api/files/lib/lib/fuzzmutate/irmutator-cpp">IRMutator.cpp</a>.</p>


<p>Referenced by <a href="#a46815db3771a03cb8892981fd9649760">mutateModule</a>.</p>

</div>
</div>

</div>

<hr/>

The documentation for this class was generated from the following files:

<ul>
<li><a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/fuzzmutate/irmutator-h">IRMutator.h</a></li>
<li><a href="/web-llvm/docs/api/files/lib/lib/fuzzmutate/irmutator-cpp">IRMutator.cpp</a></li>
</ul>

<hr/>

<p class="doxyGeneratedBy">Generated via <a href="https://github.com/xpack/doxygen2docusaurus">doxygen2docusaurus</a> by <a href="https://www.doxygen.nl">Doxygen</a> 1.15.0.</p>

</div>
