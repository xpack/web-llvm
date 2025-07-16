---

# DO NOT EDIT!
# Automatically generated via doxygen2docusaurus by Doxygen.

slug: /api/structs/llvm/mca/pipelineoptions
custom_edit_url: null
toc_max_heading_level: 4
keywords:
  - doxygen
  - reference
  - struct

---

<div class="doxyPage">

# The `PipelineOptions` Struct Reference

<p>This is a convenience struct to hold the parameters necessary for creating the pre-built "default" out-of-order pipeline. <a href="#details">More...</a></p>

## Declaration

<div class="doxyDeclaration">
struct llvm::mca::PipelineOptions { ... }
</div>

## Included Headers

<div class="doxyIncludesList">#include "<a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/mca/context-h">llvm/MCA/Context.h</a>"
</div>

## Public Constructors Index

<table class="doxyMembersIndex">

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a0f897ceb2c227f5258d091f4c8b52122">PipelineOptions</a> (unsigned UOPQSize, unsigned DecThr, unsigned DW, unsigned RFS, unsigned LQS, unsigned SQS, bool NoAlias, bool ShouldEnableBottleneckAnalysis=false)</td>
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

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">unsigned</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a3ad9f723e0a60f417aab427cb93b9dc5">MicroOpQueueSize</a></td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ac8664b52385f44ea435a4066e33bd95f">DecodersThroughput</a></td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a5f5ee31e12d1dfbc4295181b0de64434">DispatchWidth</a></td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a446906c0241a2ba8cff6713dc7a35cb2">RegisterFileSize</a></td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a0d5d115efc4e229156b51d9ce25b6793">LoadQueueSize</a></td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a0ca056c4b6038467f238b6f91cd7c74e">StoreQueueSize</a></td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">bool</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a6df186c732754aa0cfaabb93572a8d07">AssumeNoAlias</a></td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">bool</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a512954901c309ef36e6add328f458871">EnableBottleneckAnalysis</a></td>
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

<p>This is a convenience struct to hold the parameters necessary for creating the pre-built "default" out-of-order pipeline.</p>

<p>Definition at line 33 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/mca/context-h">Context.h</a>.</p>


<div class="doxySectionDef">

## Public Constructors

### PipelineOptions() {#a0f897ceb2c227f5258d091f4c8b52122}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">llvm::mca::PipelineOptions::PipelineOptions (unsigned UOPQSize, unsigned DecThr, unsigned DW, unsigned RFS, unsigned LQS, unsigned SQS, bool NoAlias, bool ShouldEnableBottleneckAnalysis=false)</td>
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



<p>Definition at line 34 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/mca/context-h">Context.h</a>.</p>


<p>References <a href="#a6df186c732754aa0cfaabb93572a8d07">AssumeNoAlias</a>, <a href="#ac8664b52385f44ea435a4066e33bd95f">DecodersThroughput</a>, <a href="#a5f5ee31e12d1dfbc4295181b0de64434">DispatchWidth</a>, <a href="#a512954901c309ef36e6add328f458871">EnableBottleneckAnalysis</a>, <a href="#a0d5d115efc4e229156b51d9ce25b6793">LoadQueueSize</a>, <a href="#a3ad9f723e0a60f417aab427cb93b9dc5">MicroOpQueueSize</a>, <a href="#a446906c0241a2ba8cff6713dc7a35cb2">RegisterFileSize</a> and <a href="#a0ca056c4b6038467f238b6f91cd7c74e">StoreQueueSize</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Public Member Attributes

### AssumeNoAlias {#a6df186c732754aa0cfaabb93572a8d07}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool llvm::mca::PipelineOptions::AssumeNoAlias</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 47 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/mca/context-h">Context.h</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/classes/llvm/mca/context/#ae59a559d2474039c4dfb540996e84d42">llvm::mca::Context::createDefaultPipeline</a>, <a href="/web-llvm/docs/api/classes/llvm/mca/context/#a48ddd4fee83ada5df0185350904d8398">llvm::mca::Context::createInOrderPipeline</a> and <a href="#a0f897ceb2c227f5258d091f4c8b52122">PipelineOptions</a>.</p>

</div>
</div>

### DecodersThroughput {#ac8664b52385f44ea435a4066e33bd95f}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">unsigned llvm::mca::PipelineOptions::DecodersThroughput</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 42 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/mca/context-h">Context.h</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/classes/llvm/mca/context/#ae59a559d2474039c4dfb540996e84d42">llvm::mca::Context::createDefaultPipeline</a> and <a href="#a0f897ceb2c227f5258d091f4c8b52122">PipelineOptions</a>.</p>

</div>
</div>

### DispatchWidth {#a5f5ee31e12d1dfbc4295181b0de64434}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">unsigned llvm::mca::PipelineOptions::DispatchWidth</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 43 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/mca/context-h">Context.h</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/classes/llvm/mca/context/#ae59a559d2474039c4dfb540996e84d42">llvm::mca::Context::createDefaultPipeline</a> and <a href="#a0f897ceb2c227f5258d091f4c8b52122">PipelineOptions</a>.</p>

</div>
</div>

### EnableBottleneckAnalysis {#a512954901c309ef36e6add328f458871}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool llvm::mca::PipelineOptions::EnableBottleneckAnalysis</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 48 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/mca/context-h">Context.h</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/classes/llvm/mca/context/#ae59a559d2474039c4dfb540996e84d42">llvm::mca::Context::createDefaultPipeline</a> and <a href="#a0f897ceb2c227f5258d091f4c8b52122">PipelineOptions</a>.</p>

</div>
</div>

### LoadQueueSize {#a0d5d115efc4e229156b51d9ce25b6793}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">unsigned llvm::mca::PipelineOptions::LoadQueueSize</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 45 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/mca/context-h">Context.h</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/classes/llvm/mca/context/#ae59a559d2474039c4dfb540996e84d42">llvm::mca::Context::createDefaultPipeline</a>, <a href="/web-llvm/docs/api/classes/llvm/mca/context/#a48ddd4fee83ada5df0185350904d8398">llvm::mca::Context::createInOrderPipeline</a> and <a href="#a0f897ceb2c227f5258d091f4c8b52122">PipelineOptions</a>.</p>

</div>
</div>

### MicroOpQueueSize {#a3ad9f723e0a60f417aab427cb93b9dc5}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">unsigned llvm::mca::PipelineOptions::MicroOpQueueSize</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 41 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/mca/context-h">Context.h</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/classes/llvm/mca/context/#ae59a559d2474039c4dfb540996e84d42">llvm::mca::Context::createDefaultPipeline</a> and <a href="#a0f897ceb2c227f5258d091f4c8b52122">PipelineOptions</a>.</p>

</div>
</div>

### RegisterFileSize {#a446906c0241a2ba8cff6713dc7a35cb2}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">unsigned llvm::mca::PipelineOptions::RegisterFileSize</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 44 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/mca/context-h">Context.h</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/classes/llvm/mca/context/#ae59a559d2474039c4dfb540996e84d42">llvm::mca::Context::createDefaultPipeline</a>, <a href="/web-llvm/docs/api/classes/llvm/mca/context/#a48ddd4fee83ada5df0185350904d8398">llvm::mca::Context::createInOrderPipeline</a> and <a href="#a0f897ceb2c227f5258d091f4c8b52122">PipelineOptions</a>.</p>

</div>
</div>

### StoreQueueSize {#a0ca056c4b6038467f238b6f91cd7c74e}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">unsigned llvm::mca::PipelineOptions::StoreQueueSize</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 46 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/mca/context-h">Context.h</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/classes/llvm/mca/context/#ae59a559d2474039c4dfb540996e84d42">llvm::mca::Context::createDefaultPipeline</a>, <a href="/web-llvm/docs/api/classes/llvm/mca/context/#a48ddd4fee83ada5df0185350904d8398">llvm::mca::Context::createInOrderPipeline</a> and <a href="#a0f897ceb2c227f5258d091f4c8b52122">PipelineOptions</a>.</p>

</div>
</div>

</div>

<hr/>

The documentation for this struct was generated from the following file:

<ul>
<li><a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/mca/context-h">Context.h</a></li>
</ul>

<hr/>

<p class="doxyGeneratedBy">Generated via <a href="https://github.com/xpack/doxygen2docusaurus">doxygen2docusaurus</a> by <a href="https://www.doxygen.nl">Doxygen</a> 1.15.0.</p>

</div>
