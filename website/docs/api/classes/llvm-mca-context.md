---

# DO NOT EDIT!
# Automatically generated via doxygen2docusaurus by Doxygen.

slug: /api/classes/llvm/mca/context
custom_edit_url: null
toc_max_heading_level: 4
keywords:
  - doxygen
  - reference
  - class

---

<div class="doxyPage">

# `Context` Class



## Declaration

<div class="doxyDeclaration">
class llvm::mca::Context { ... }
</div>

## Included Headers

<div class="doxyIncludesList">#include "<a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/mca/context-h">llvm/MCA/Context.h</a>"
</div>

## Public Constructors Index

<table class="doxyMembersIndex">

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a96b32d54194d31238bc78f0311e283b0">Context</a> (const MCRegisterInfo &amp;R, const MCSubtargetInfo &amp;S)</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#afeb746f2140a60d79bd221ba37764ee7">Context</a> (const Context &amp;C)=delete</td>
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

## Public Operators Index

<table class="doxyMembersIndex">

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/mca/context">Context</a> &amp;</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a6c8c82c9a58a490b9da75321ef53531f">operator=</a> (const Context &amp;C)=delete</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/mcregisterinfo">MCRegisterInfo</a> &amp;</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a506df6e4a8f6730f3af9513321d7dd83">getMCRegisterInfo</a> () const</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/mcsubtargetinfo">MCSubtargetInfo</a> &amp;</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a0f75a5159ef43222b676269c47985474">getMCSubtargetInfo</a> () const</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">void</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ade3369aca1d7613aaa9356e6a38ceb00">addHardwareUnit</a> (std::unique_ptr&lt; HardwareUnit &gt; H)</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">std::unique_ptr&lt; <a href="/web-llvm/docs/api/classes/llvm/mca/pipeline">Pipeline</a> &gt;</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ae59a559d2474039c4dfb540996e84d42">createDefaultPipeline</a> (const PipelineOptions &amp;Opts, SourceMgr &amp;SrcMgr, CustomBehaviour &amp;CB)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Construct a basic pipeline for simulating an out-of-order pipeline. <a href="#ae59a559d2474039c4dfb540996e84d42">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">std::unique_ptr&lt; <a href="/web-llvm/docs/api/classes/llvm/mca/pipeline">Pipeline</a> &gt;</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a48ddd4fee83ada5df0185350904d8398">createInOrderPipeline</a> (const PipelineOptions &amp;Opts, SourceMgr &amp;SrcMgr, CustomBehaviour &amp;CB)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Construct a basic pipeline for simulating an in-order pipeline. <a href="#a48ddd4fee83ada5df0185350904d8398">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

</table>

## Private Member Attributes Index

<table class="doxyMembersIndex">

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/smallvector">SmallVector</a>&lt; std::unique_ptr&lt; <a href="/web-llvm/docs/api/classes/llvm/mca/hardwareunit">HardwareUnit</a> &gt;, 4 &gt;</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a895659dac43a33905f753011c28b2385">Hardware</a></td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/mcregisterinfo">MCRegisterInfo</a> &amp;</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a1964974cbd3460bde58a47eef0ecf37a">MRI</a></td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/mcsubtargetinfo">MCSubtargetInfo</a> &amp;</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a18977be9bb18e64d4abb04f2fd803fa0">STI</a></td>
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


<p>Definition at line 51 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/mca/context-h">Context.h</a>.</p>


<div class="doxySectionDef">

## Public Constructors

### Context() {#a96b32d54194d31238bc78f0311e283b0}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">llvm::mca::Context::Context (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/mcregisterinfo">MCRegisterInfo</a> &amp; R, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/mcsubtargetinfo">MCSubtargetInfo</a> &amp; S)</td>
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



<p>Definition at line 57 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/mca/context-h">Context.h</a>.</p>


<p>Referenced by <a href="#afeb746f2140a60d79bd221ba37764ee7">Context</a> and <a href="#a6c8c82c9a58a490b9da75321ef53531f">operator=</a>.</p>

</div>
</div>

### Context() {#afeb746f2140a60d79bd221ba37764ee7}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">llvm::mca::Context::Context (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/mca/context">Context</a> &amp; C)</td>
</tr>
</table>
</td>
<td class="doxyMemberLabelsRight">
<span class="doxyMemberLabels">
<span class="doxyMemberLabel delete">delete</span>
</span>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 58 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/mca/context-h">Context.h</a>.</p>


<p>References <a href="/web-llvm/docs/api/namespaces/llvm/callingconv/#ac6aa1387c4375260e2468eb5a77fdb4cafd841a49aec1539bc88abc8ff9e170fb">llvm::CallingConv::C</a> and <a href="#a96b32d54194d31238bc78f0311e283b0">Context</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Public Operators

### operator=() {#a6c8c82c9a58a490b9da75321ef53531f}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">Context &amp; llvm::mca::Context::operator= (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/mca/context">Context</a> &amp; C)</td>
</tr>
</table>
</td>
<td class="doxyMemberLabelsRight">
<span class="doxyMemberLabels">
<span class="doxyMemberLabel delete">delete</span>
</span>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 59 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/mca/context-h">Context.h</a>.</p>


<p>References <a href="/web-llvm/docs/api/namespaces/llvm/callingconv/#ac6aa1387c4375260e2468eb5a77fdb4cafd841a49aec1539bc88abc8ff9e170fb">llvm::CallingConv::C</a> and <a href="#a96b32d54194d31238bc78f0311e283b0">Context</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Public Member Functions

### addHardwareUnit() {#ade3369aca1d7613aaa9356e6a38ceb00}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void llvm::mca::Context::addHardwareUnit (std::unique_ptr&lt; <a href="/web-llvm/docs/api/classes/llvm/mca/hardwareunit">HardwareUnit</a> &gt; H)</td>
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



<p>Definition at line 64 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/mca/context-h">Context.h</a>.</p>


<p>Reference <a href="/web-llvm/docs/api/files/lib/lib/support/md5-cpp/#ae42219072d798876e6b08e6b78614ff6">H</a>.</p>


<p>Referenced by <a href="#ae59a559d2474039c4dfb540996e84d42">createDefaultPipeline</a> and <a href="#a48ddd4fee83ada5df0185350904d8398">createInOrderPipeline</a>.</p>

</div>
</div>

### createDefaultPipeline() {#ae59a559d2474039c4dfb540996e84d42}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">std::unique_ptr&lt; Pipeline &gt; llvm::mca::Context::createDefaultPipeline (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/structs/llvm/mca/pipelineoptions">PipelineOptions</a> &amp; Opts, <a href="/web-llvm/docs/api/structs/llvm/mca/sourcemgr">SourceMgr</a> &amp; SrcMgr, <a href="/web-llvm/docs/api/classes/llvm/mca/custombehaviour">CustomBehaviour</a> &amp; CB)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Construct a basic pipeline for simulating an out-of-order pipeline.</p>


<p>This pipeline consists of Fetch, Dispatch, Execute, and Retire stages.</p>


<p>Declaration at line 70 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/mca/context-h">Context.h</a>, definition at line 32 of file <a href="/web-llvm/docs/api/files/lib/lib/mca/context-cpp">Context.cpp</a>.</p>


<p>References <a href="#ade3369aca1d7613aaa9356e6a38ceb00">addHardwareUnit</a>, <a href="/web-llvm/docs/api/structs/llvm/mca/pipelineoptions/#a6df186c732754aa0cfaabb93572a8d07">llvm::mca::PipelineOptions::AssumeNoAlias</a>, <a href="#a48ddd4fee83ada5df0185350904d8398">createInOrderPipeline</a>, <a href="/web-llvm/docs/api/structs/llvm/mca/pipelineoptions/#ac8664b52385f44ea435a4066e33bd95f">llvm::mca::PipelineOptions::DecodersThroughput</a>, <a href="/web-llvm/docs/api/structs/llvm/mca/pipelineoptions/#a5f5ee31e12d1dfbc4295181b0de64434">llvm::mca::PipelineOptions::DispatchWidth</a>, <a href="/web-llvm/docs/api/structs/llvm/mca/pipelineoptions/#a512954901c309ef36e6add328f458871">llvm::mca::PipelineOptions::EnableBottleneckAnalysis</a>, <a href="/web-llvm/docs/api/files/lib/lib/support/program-cpp/#a3cc4767a85e498eea6b41bfbbdb4d2e9">Execute</a>, <a href="/web-llvm/docs/api/structs/llvm/mcschedmodel/#a17c82641b0ce9632ce1baaf54a71db6e">llvm::MCSchedModel::isOutOfOrder</a>, <a href="/web-llvm/docs/api/structs/llvm/mca/pipelineoptions/#a0d5d115efc4e229156b51d9ce25b6793">llvm::mca::PipelineOptions::LoadQueueSize</a>, <a href="/web-llvm/docs/api/structs/llvm/mca/pipelineoptions/#a3ad9f723e0a60f417aab427cb93b9dc5">llvm::mca::PipelineOptions::MicroOpQueueSize</a>, <a href="/web-llvm/docs/api/structs/llvm/mca/pipelineoptions/#a446906c0241a2ba8cff6713dc7a35cb2">llvm::mca::PipelineOptions::RegisterFileSize</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a5f3f23062c5d5636bee27c54f4a407f0">llvm::SrcMgr</a> and <a href="/web-llvm/docs/api/structs/llvm/mca/pipelineoptions/#a0ca056c4b6038467f238b6f91cd7c74e">llvm::mca::PipelineOptions::StoreQueueSize</a>.</p>

</div>
</div>

### createInOrderPipeline() {#a48ddd4fee83ada5df0185350904d8398}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">std::unique_ptr&lt; Pipeline &gt; llvm::mca::Context::createInOrderPipeline (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/structs/llvm/mca/pipelineoptions">PipelineOptions</a> &amp; Opts, <a href="/web-llvm/docs/api/structs/llvm/mca/sourcemgr">SourceMgr</a> &amp; SrcMgr, <a href="/web-llvm/docs/api/classes/llvm/mca/custombehaviour">CustomBehaviour</a> &amp; CB)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Construct a basic pipeline for simulating an in-order pipeline.</p>


<p>This pipeline consists of Fetch, InOrderIssue, and Retire stages.</p>


<p>Declaration at line 76 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/mca/context-h">Context.h</a>, definition at line 73 of file <a href="/web-llvm/docs/api/files/lib/lib/mca/context-cpp">Context.cpp</a>.</p>


<p>References <a href="#ade3369aca1d7613aaa9356e6a38ceb00">addHardwareUnit</a>, <a href="/web-llvm/docs/api/structs/llvm/mca/pipelineoptions/#a6df186c732754aa0cfaabb93572a8d07">llvm::mca::PipelineOptions::AssumeNoAlias</a>, <a href="/web-llvm/docs/api/structs/llvm/mca/pipelineoptions/#a0d5d115efc4e229156b51d9ce25b6793">llvm::mca::PipelineOptions::LoadQueueSize</a>, <a href="/web-llvm/docs/api/structs/llvm/mca/pipelineoptions/#a446906c0241a2ba8cff6713dc7a35cb2">llvm::mca::PipelineOptions::RegisterFileSize</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a5f3f23062c5d5636bee27c54f4a407f0">llvm::SrcMgr</a> and <a href="/web-llvm/docs/api/structs/llvm/mca/pipelineoptions/#a0ca056c4b6038467f238b6f91cd7c74e">llvm::mca::PipelineOptions::StoreQueueSize</a>.</p>


<p>Referenced by <a href="#ae59a559d2474039c4dfb540996e84d42">createDefaultPipeline</a>.</p>

</div>
</div>

### getMCRegisterInfo() {#a506df6e4a8f6730f3af9513321d7dd83}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">const MCRegisterInfo &amp; llvm::mca::Context::getMCRegisterInfo ()</td>
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



<p>Definition at line 61 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/mca/context-h">Context.h</a>.</p>

</div>
</div>

### getMCSubtargetInfo() {#a0f75a5159ef43222b676269c47985474}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">const MCSubtargetInfo &amp; llvm::mca::Context::getMCSubtargetInfo ()</td>
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



<p>Definition at line 62 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/mca/context-h">Context.h</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Private Member Attributes

### Hardware {#a895659dac43a33905f753011c28b2385}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">SmallVector&lt;std::unique_ptr&lt;HardwareUnit&gt;, 4&gt; llvm::mca::Context::Hardware</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 52 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/mca/context-h">Context.h</a>.</p>

</div>
</div>

### MRI {#a1964974cbd3460bde58a47eef0ecf37a}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">const MCRegisterInfo&amp; llvm::mca::Context::MRI</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 53 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/mca/context-h">Context.h</a>.</p>

</div>
</div>

### STI {#a18977be9bb18e64d4abb04f2fd803fa0}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">const MCSubtargetInfo&amp; llvm::mca::Context::STI</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 54 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/mca/context-h">Context.h</a>.</p>

</div>
</div>

</div>

<hr/>

The documentation for this class was generated from the following files:

<ul>
<li><a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/mca/context-h">Context.h</a></li>
<li><a href="/web-llvm/docs/api/files/lib/lib/mca/context-cpp">Context.cpp</a></li>
</ul>

<hr/>

<p class="doxyGeneratedBy">Generated via <a href="https://xpack.github.io/doxygen2docusaurus">doxygen2docusaurus</a> 2.0.0 by <a href="https://www.doxygen.nl">Doxygen</a> 1.15.0.</p>

</div>
