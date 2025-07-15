---

# DO NOT EDIT!
# Automatically generated via doxygen2docusaurus by Doxygen.

slug: /api/classes/llvm/amdgpupassconfig
custom_edit_url: null
toc_max_heading_level: 4
keywords:
  - doxygen
  - reference
  - class

---

<div class="doxyPage">

# The `AMDGPUPassConfig` Class Reference



## Declaration

<div class="doxyDeclaration">
class llvm::AMDGPUPassConfig { ... }
</div>

## Included Headers

<div class="doxyIncludesList">#include "<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/amdgputargetmachine-h">Target/AMDGPU/AMDGPUTargetMachine.h</a>"
</div>

## Base class

<table class="doxyMembersIndex">

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">class</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/targetpassconfig">TargetPassConfig</a></td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Target-Independent Code Generator <a href="/web-llvm/docs/api/classes/llvm/pass">Pass</a> Configuration Options. <a href="/web-llvm/docs/api/classes/llvm/targetpassconfig/#details">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

</table>

## Derived Classes

<table class="doxyMembersIndex">

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">class</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="/web-llvm/docs/api/classes/anonymous-amdgputargetmachine-cpp-/gcnpassconfig">GCNPassConfig</a></td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">class</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="/web-llvm/docs/api/classes/anonymous-r600targetmachine-cpp-/r600passconfig">R600PassConfig</a></td>
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

## Public Constructors Index

<table class="doxyMembersIndex">

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a79305ba9935a6139ad667945f665d6ea">AMDGPUPassConfig</a> (TargetMachine &amp;TM, PassManagerBase &amp;PM)</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/amdgputargetmachine">AMDGPUTargetMachine</a> &amp;</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a01925ea9dc3f5339a6d96badbbd494b9">getAMDGPUTargetMachine</a> () const</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/scheduledaginstrs">ScheduleDAGInstrs</a> *</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a1195605ebde16d30249261f2f9104c9b">createMachineScheduler</a> (MachineSchedContext *C) const override</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Create an instance of <a href="/web-llvm/docs/api/classes/llvm/scheduledaginstrs">ScheduleDAGInstrs</a> to be run within the standard MachineScheduler pass for this function and target at the current optimization level. <a href="#a1195605ebde16d30249261f2f9104c9b">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">void</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ab95f5ef67821cd6ddabe512d38807c69">addEarlyCSEOrGVNPass</a> ()</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a6d1d286b7f3eed2617be594252bcfafd">addStraightLineScalarOptimizationPasses</a> ()</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ab4b7f9099a377d260c73ad9d7b464615">addIRPasses</a> () override</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Add common target configurable passes that perform LLVM IR to IR transforms following machine independent optimization. <a href="#ab4b7f9099a377d260c73ad9d7b464615">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">void</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ad3c43a064022801bdca206ced049a0ff">addCodeGenPrepare</a> () override</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Add pass to prepare the LLVM IR for code generation. <a href="#ad3c43a064022801bdca206ced049a0ff">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">bool</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a32809e50f5ee8ee63d2ea8e20c0db9aa">addPreISel</a> () override</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Methods with trivial inline returns are convenient points in the common codegen pass pipeline where targets may insert passes. <a href="#a32809e50f5ee8ee63d2ea8e20c0db9aa">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">bool</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a3dfda91b1766a907bad7895b0c02c3ee">addInstSelector</a> () override</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>addInstSelector - This method should install an instruction selector pass, which converts from LLVM code to machine instructions. <a href="#a3dfda91b1766a907bad7895b0c02c3ee">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">bool</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a48a4ae24ee0bd478fa6dd7b8e10eb756">addGCPasses</a> () override</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>addGCPasses - Add late codegen passes that analyze code for garbage collection. <a href="#a48a4ae24ee0bd478fa6dd7b8e10eb756">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">std::unique_ptr&lt; <a href="/web-llvm/docs/api/classes/llvm/cseconfigbase">CSEConfigBase</a> &gt;</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a0c0af5bfedd6d1ad0d1af0a957e4de16">getCSEConfig</a> () const override</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Returns the CSEConfig object to use for the current optimization level. <a href="#a0c0af5bfedd6d1ad0d1af0a957e4de16">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">bool</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a16f2b92989c6760a2447933b3c78a755">isPassEnabled</a> (const cl::opt&lt; bool &gt; &amp;Opt, CodeGenOptLevel Level=CodeGenOptLevel::Default) const</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p><a href="/web-llvm/docs/api/namespaces/llvm/check">Check</a> if a pass is enabled given <span class="doxyComputerOutput">Opt</span> option. <a href="#a16f2b92989c6760a2447933b3c78a755">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

</table>


<p>Definition at line 124 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/amdgputargetmachine-h">AMDGPUTargetMachine.h</a>.</p>


<div class="doxySectionDef">

## Public Constructors

### AMDGPUPassConfig() {#a79305ba9935a6139ad667945f665d6ea}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">AMDGPUPassConfig::AMDGPUPassConfig (<a href="/web-llvm/docs/api/classes/llvm/targetmachine">TargetMachine</a> &amp; TM, <a href="/web-llvm/docs/api/classes/llvm/legacy/passmanagerbase">PassManagerBase</a> &amp; PM)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Declaration at line 126 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/amdgputargetmachine-h">AMDGPUTargetMachine.h</a>, definition at line 1115 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/amdgputargetmachine-cpp">AMDGPUTargetMachine.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/classes/llvm/targetpassconfig/#a978dba92612e01044c907d34c66f65b0">llvm::TargetPassConfig::disablePass</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a85d339220c3769c26cc027fe4cc4dfee">llvm::FuncletLayoutID</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a14e570cceb3bd60c8323f11b2cd22d2c">llvm::GCLoweringID</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a624227ff042d822fbb790213e9e82e16">llvm::ShadowStackGCLoweringID</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a805432189f97152d1899d08945204faa">llvm::StackMapLivenessID</a>, <a href="/web-llvm/docs/api/classes/llvm/targetpassconfig/#abfe879f7efa8851adee88ab786516d59">llvm::TargetPassConfig::TargetPassConfig</a> and <a href="/web-llvm/docs/api/classes/llvm/targetpassconfig/#a0e43f614336b22347dfdb6f20ea792df">llvm::TargetPassConfig::TM</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/classes/anonymous-amdgputargetmachine-cpp-/gcnpassconfig/#a61e14f7e670cd323bc7683448c522dc7">anonymous{AMDGPUTargetMachine.cpp}::GCNPassConfig::GCNPassConfig</a> and <a href="/web-llvm/docs/api/classes/anonymous-r600targetmachine-cpp-/r600passconfig/#ad44ef6a401c51e3887aaa689899a85cc">anonymous{R600TargetMachine.cpp}::R600PassConfig::R600PassConfig</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Public Member Functions

### addCodeGenPrepare() {#ad3c43a064022801bdca206ced049a0ff}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void AMDGPUPassConfig::addCodeGenPrepare ()</td>
</tr>
</table>
</td>
<td class="doxyMemberLabelsRight">
<span class="doxyMemberLabels">
<span class="doxyMemberLabel virtual">virtual</span>
</span>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Add pass to prepare the LLVM IR for code generation.</p>


<p>This should be done before exception handling preparation passes.</p>


<p>Declaration at line 138 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/amdgputargetmachine-h">AMDGPUTargetMachine.h</a>, definition at line 1249 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/amdgputargetmachine-cpp">AMDGPUTargetMachine.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/classes/llvm/targetpassconfig/#a3082a93fec84f7658664ce7b4840b15c">llvm::TargetPassConfig::addCodeGenPrepare</a>, <a href="/web-llvm/docs/api/classes/llvm/targetpassconfig/#ab2ca200281996a1a8bc064d21d4aa238">llvm::TargetPassConfig::addPass</a>, <a href="/web-llvm/docs/api/classes/llvm/triple/#a547abd13f7a3c063aa72c8192a868154a387d88fc1b536facc13f5a41170250b0">llvm::Triple::amdgcn</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a7f211632b99f0ebf19db46192940082b">llvm::createAMDGPUAnnotateKernelFeaturesPass</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a1fbfe8967c85c848babf2f9296af7f7e">llvm::createAMDGPULowerBufferFatPointersPass</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a7cd0ab7a0dac0a07083a4776221cd9e6">llvm::createAMDGPULowerKernelArgumentsPass</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a17a97a755982d8fe4e03d09755f11af4">llvm::createLoadStoreVectorizerPass</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#aca2878b6eed339f5ef7c6b983849f405">llvm::createLowerSwitchPass</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/amdgputargetmachine-cpp/#aa7674f1c87a00bb297f95d82ab2a4d34">EnableLoadStoreVectorizer</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/amdgputargetmachine-cpp/#a2c744b9ce60caa4eca00a83b3d09a0f6">EnableLowerKernelArguments</a>, <a href="#a16f2b92989c6760a2447933b3c78a755">isPassEnabled</a> and <a href="/web-llvm/docs/api/classes/llvm/targetpassconfig/#a0e43f614336b22347dfdb6f20ea792df">llvm::TargetPassConfig::TM</a>.</p>

</div>
</div>

### addEarlyCSEOrGVNPass() {#ab95f5ef67821cd6ddabe512d38807c69}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void AMDGPUPassConfig::addEarlyCSEOrGVNPass ()</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Declaration at line 135 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/amdgputargetmachine-h">AMDGPUTargetMachine.h</a>, definition at line 1126 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/amdgputargetmachine-cpp">AMDGPUTargetMachine.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/classes/llvm/targetpassconfig/#ab2ca200281996a1a8bc064d21d4aa238">llvm::TargetPassConfig::addPass</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a8ec1bf8d7b792ca9fac56f8514db18d2a389a96d0d9b3feb46b8c9d941566a4ae">llvm::Aggressive</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#ae28159c054fa79ac71652e2bb0972082">llvm::createEarlyCSEPass</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#aaa43409c7dab66be0480defab2d17687">llvm::createGVNPass</a> and <a href="/web-llvm/docs/api/classes/llvm/targetpassconfig/#a4c36a5c58e6e55c962d2d9bed0bb3ba7">llvm::TargetPassConfig::getOptLevel</a>.</p>


<p>Referenced by <a href="#ab4b7f9099a377d260c73ad9d7b464615">addIRPasses</a> and <a href="#a6d1d286b7f3eed2617be594252bcfafd">addStraightLineScalarOptimizationPasses</a>.</p>

</div>
</div>

### addGCPasses() {#a48a4ae24ee0bd478fa6dd7b8e10eb756}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool AMDGPUPassConfig::addGCPasses ()</td>
</tr>
</table>
</td>
<td class="doxyMemberLabelsRight">
<span class="doxyMemberLabels">
<span class="doxyMemberLabel virtual">virtual</span>
</span>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>addGCPasses - Add late codegen passes that analyze code for garbage collection.</p>


<p>Add standard GC passes.</p>


<p>This should return true if GC info should be printed after these passes.</p>


<p>Declaration at line 141 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/amdgputargetmachine-h">AMDGPUTargetMachine.h</a>, definition at line 1306 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/amdgputargetmachine-cpp">AMDGPUTargetMachine.cpp</a>.</p>

</div>
</div>

### addInstSelector() {#a3dfda91b1766a907bad7895b0c02c3ee}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool AMDGPUPassConfig::addInstSelector ()</td>
</tr>
</table>
</td>
<td class="doxyMemberLabelsRight">
<span class="doxyMemberLabels">
<span class="doxyMemberLabel virtual">virtual</span>
</span>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>addInstSelector - This method should install an instruction selector pass, which converts from LLVM code to machine instructions.</p>

<p>Declaration at line 140 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/amdgputargetmachine-h">AMDGPUTargetMachine.h</a>, definition at line 1301 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/amdgputargetmachine-cpp">AMDGPUTargetMachine.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/classes/llvm/targetpassconfig/#ab2ca200281996a1a8bc064d21d4aa238">llvm::TargetPassConfig::addPass</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#aa2e4193803a28d419723321cf3b329cd">llvm::createAMDGPUISelDag</a>, <a href="#a01925ea9dc3f5339a6d96badbbd494b9">getAMDGPUTargetMachine</a> and <a href="/web-llvm/docs/api/classes/llvm/targetpassconfig/#a4c36a5c58e6e55c962d2d9bed0bb3ba7">llvm::TargetPassConfig::getOptLevel</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/classes/anonymous-amdgputargetmachine-cpp-/gcnpassconfig/#a6f9db49e1cea1b37060681a0eedaf90c">anonymous{AMDGPUTargetMachine.cpp}::GCNPassConfig::addInstSelector</a>.</p>

</div>
</div>

### addIRPasses() {#ab4b7f9099a377d260c73ad9d7b464615}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void AMDGPUPassConfig::addIRPasses ()</td>
</tr>
</table>
</td>
<td class="doxyMemberLabelsRight">
<span class="doxyMemberLabels">
<span class="doxyMemberLabel virtual">virtual</span>
</span>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Add common target configurable passes that perform LLVM IR to IR transforms following machine independent optimization.</p>

<p>Declaration at line 137 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/amdgputargetmachine-h">AMDGPUTargetMachine.h</a>, definition at line 1150 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/amdgputargetmachine-cpp">AMDGPUTargetMachine.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/classes/llvm/aaresults/#ae4fcea773b8fc3af6c3c579ebcc7c692">llvm::AAResults::addAAResult</a>, <a href="#ab95f5ef67821cd6ddabe512d38807c69">addEarlyCSEOrGVNPass</a>, <a href="/web-llvm/docs/api/classes/llvm/targetpassconfig/#a835d2863dbd2cfd8c184a6a94923b61f">llvm::TargetPassConfig::addIRPasses</a>, <a href="/web-llvm/docs/api/classes/llvm/targetpassconfig/#ab2ca200281996a1a8bc064d21d4aa238">llvm::TargetPassConfig::addPass</a>, <a href="#a6d1d286b7f3eed2617be594252bcfafd">addStraightLineScalarOptimizationPasses</a>, <a href="/web-llvm/docs/api/classes/llvm/triple/#a547abd13f7a3c063aa72c8192a868154a387d88fc1b536facc13f5a41170250b0">llvm::Triple::amdgcn</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/amdgputargetmachine-cpp/#ae18dc569224d0d427aa4f6492414afd7">AMDGPUAtomicOptimizerStrategy</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a94d3df6f4a85e6d7f734d1ea79c6f549">llvm::createAlwaysInlinerLegacyPass</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a0970ab1f05fa4adde81a1ef0d89b7b84">llvm::createAMDGPUAAWrapperPass</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a4556b575343ffecd092458b569ec3949">llvm::createAMDGPUAlwaysInlinePass</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a60323517c9d4e91f8fd74446e26734ab">llvm::createAMDGPUAtomicOptimizerPass</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#aa28b2d290384dfe965f3520a9de18a29">llvm::createAMDGPUCodeGenPreparePass</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a204f03fe6d2a5e5c7ab7b704f7c1b377">llvm::createAMDGPUCtorDtorLoweringLegacyPass</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#ae158d380936aa0b3a81271300ba71d0f">llvm::createAMDGPUImageIntrinsicOptimizerPass</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a9a182c2c1a3860b0bc1c8c0d7918ee3c">llvm::createAMDGPULowerModuleLDSLegacyPass</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#aa2c93f14894e0aa4d82d1abf0e554e52">llvm::createAMDGPUOpenCLEnqueuedBlockLoweringLegacyPass</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a94327e069f14d60ea96b0a6defef02b9">llvm::createAMDGPUPrintfRuntimeBinding</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a9b21fd410165d44c2966caaf7c0e21af">llvm::createAMDGPUPromoteAlloca</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a9da560294c00c5594ece4760cb319ff3">llvm::createAMDGPURemoveIncompatibleFunctionsPass</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a23bfe8b42c7192a94b60c1e58a5416a5">llvm::createAMDGPUSwLowerLDSLegacyPass</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#adebabb5e491a19ce4466a326d41641e0">llvm::createAtomicExpandLegacyPass</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a1895f13235512e51a7619de25cda6f4f">llvm::createExpandVariadicsPass</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#ad0000e11ad5a4d13f48c4498fbd9d18a">llvm::createExternalAAWrapperPass</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#ac2d015931f100c1d324b07e550ae5e74">llvm::createInferAddressSpacesPass</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a52fe42f45635485443c10aa9de4e7825">llvm::createLICMPass</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#aa21e10c20c38a113fe8f605b018ec325">llvm::createR600OpenCLImageTypeLoweringPass</a>, <a href="/web-llvm/docs/api/classes/llvm/targetpassconfig/#a978dba92612e01044c907d34c66f65b0">llvm::TargetPassConfig::disablePass</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/amdgputargetmachine-cpp/#a940a102a9097d17f980c33f01c05a984">EnableAMDGPUAliasAnalysis</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/amdgputargetmachine-cpp/#a4666f73765be78d7dddd8b90072ceebe">EnableImageIntrinsicOptimizer</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/amdgputargetmachine-cpp/#a03c9aa0c85dac0e1b72a3e3f2a91b569">EnableLowerModuleLDS</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/amdgputargetmachine-cpp/#abf6ff331b4916398a8ca064fb26dd7dd">EnableScalarIRPasses</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/amdgputargetmachine-cpp/#a27a9bf5df1e9bac5d7d23128b6a4e9b7">EnableSwLowerLDS</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a85d339220c3769c26cc027fe4cc4dfee">llvm::FuncletLayoutID</a>, <a href="#a01925ea9dc3f5339a6d96badbbd494b9">getAMDGPUTargetMachine</a>, <a href="#a16f2b92989c6760a2447933b3c78a755">isPassEnabled</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a8ec1bf8d7b792ca9fac56f8514db18d2a1cfdf0e8d0c87a228c1f40d9bee7888b">llvm::Less</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/amdgputargetmachine-cpp/#a6dcde25571ce05ae09b3acb968fbd9b1">LowerCtorDtor</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a4981871ea1a597d1b8aa1a8ac9326e76a29d4416121b20dd5ccd9ffca40c05524">llvm::Lowering</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a8ec1bf8d7b792ca9fac56f8514db18d2a6adf97f83acf6453d4a6a4b1070f3754">llvm::None</a>, <a href="/web-llvm/docs/api/files/lib/lib/option/option-cpp/#a04665169063c8ca1f2ea96c27fc7c2b2">P</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a3ddae16561e646c4cbadec7e4fb5308b">llvm::PatchableFunctionID</a>, <a href="/web-llvm/docs/api/classes/llvm/triple/#a547abd13f7a3c063aa72c8192a868154a060ea888d89f5d59a5743118e429296f">llvm::Triple::r600</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/amdgputargetmachine-cpp/#abf5a8d526d96551c07ff875293def295">RemoveIncompatibleFunctions</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a805432189f97152d1899d08945204faa">llvm::StackMapLivenessID</a> and <a href="/web-llvm/docs/api/classes/llvm/targetpassconfig/#a0e43f614336b22347dfdb6f20ea792df">llvm::TargetPassConfig::TM</a>.</p>

</div>
</div>

### addPreISel() {#a32809e50f5ee8ee63d2ea8e20c0db9aa}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool AMDGPUPassConfig::addPreISel ()</td>
</tr>
</table>
</td>
<td class="doxyMemberLabelsRight">
<span class="doxyMemberLabels">
<span class="doxyMemberLabel virtual">virtual</span>
</span>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Methods with trivial inline returns are convenient points in the common codegen pass pipeline where targets may insert passes.</p>


<p>Methods with out-of-line standard implementations are major CodeGen stages called by addMachinePasses. Some targets may override major stages when inserting passes is insufficient, but maintaining overriden stages is more work. addPreISelPasses - This method should add any "last minute" LLVM-&gt;LLVM passes (which are run just before instruction selector).</p>


<p>Declaration at line 139 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/amdgputargetmachine-h">AMDGPUTargetMachine.h</a>, definition at line 1295 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/amdgputargetmachine-cpp">AMDGPUTargetMachine.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/classes/llvm/targetpassconfig/#ab2ca200281996a1a8bc064d21d4aa238">llvm::TargetPassConfig::addPass</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a04b2e2d516b1c7155db2181d2f763211">llvm::createFlattenCFGPass</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a8ec1bf8d7b792ca9fac56f8514db18d2a6adf97f83acf6453d4a6a4b1070f3754">llvm::None</a> and <a href="/web-llvm/docs/api/classes/llvm/targetpassconfig/#a0e43f614336b22347dfdb6f20ea792df">llvm::TargetPassConfig::TM</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/classes/anonymous-amdgputargetmachine-cpp-/gcnpassconfig/#a5f5e5cbdd263a4e0801b6dbf7c4e8ecd">anonymous{AMDGPUTargetMachine.cpp}::GCNPassConfig::addPreISel</a> and <a href="/web-llvm/docs/api/classes/anonymous-r600targetmachine-cpp-/r600passconfig/#acab6a8ddc61e46277bc9eb85b2cc9d7d">anonymous{R600TargetMachine.cpp}::R600PassConfig::addPreISel</a>.</p>

</div>
</div>

### addStraightLineScalarOptimizationPasses() {#a6d1d286b7f3eed2617be594252bcfafd}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void AMDGPUPassConfig::addStraightLineScalarOptimizationPasses ()</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Declaration at line 136 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/amdgputargetmachine-h">AMDGPUTargetMachine.h</a>, definition at line 1133 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/amdgputargetmachine-cpp">AMDGPUTargetMachine.cpp</a>.</p>


<p>References <a href="#ab95f5ef67821cd6ddabe512d38807c69">addEarlyCSEOrGVNPass</a>, <a href="/web-llvm/docs/api/classes/llvm/targetpassconfig/#ab2ca200281996a1a8bc064d21d4aa238">llvm::TargetPassConfig::addPass</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a8ec1bf8d7b792ca9fac56f8514db18d2a389a96d0d9b3feb46b8c9d941566a4ae">llvm::Aggressive</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#ae28159c054fa79ac71652e2bb0972082">llvm::createEarlyCSEPass</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a7c077d5ecfb6be89f42babfdce5a71d3">llvm::createLoopDataPrefetchPass</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a3cb6969a73ff0eafb38cd7a4eb892c2a">llvm::createNaryReassociatePass</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a9c0b23603da5cadac0b7602fae0dddc5">llvm::createSeparateConstOffsetFromGEPPass</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#ae040857e54926714367245b71d69155f">llvm::createStraightLineStrengthReducePass</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/amdgputargetmachine-cpp/#aaf7b119415eac8f2fe46bb4d78d85f5f">EnableLoopPrefetch</a> and <a href="#a16f2b92989c6760a2447933b3c78a755">isPassEnabled</a>.</p>


<p>Referenced by <a href="#ab4b7f9099a377d260c73ad9d7b464615">addIRPasses</a>.</p>

</div>
</div>

### createMachineScheduler() {#a1195605ebde16d30249261f2f9104c9b}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">llvm::ScheduleDAGInstrs * AMDGPUPassConfig::createMachineScheduler (<a href="/web-llvm/docs/api/structs/llvm/machineschedcontext">MachineSchedContext</a> * C)</td>
</tr>
</table>
</td>
<td class="doxyMemberLabelsRight">
<span class="doxyMemberLabels">
<span class="doxyMemberLabel virtual">virtual</span>
</span>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Create an instance of <a href="/web-llvm/docs/api/classes/llvm/scheduledaginstrs">ScheduleDAGInstrs</a> to be run within the standard MachineScheduler pass for this function and target at the current optimization level.</p>


<p>This can also be used to plug a new <a href="/web-llvm/docs/api/classes/llvm/machineschedstrategy">MachineSchedStrategy</a> into an instance of the standard <a href="/web-llvm/docs/api/classes/llvm/scheduledagmi">ScheduleDAGMI</a>: return new <a href="/web-llvm/docs/api/classes/llvm/scheduledagmi">ScheduleDAGMI</a>(C, std::make_unique&lt;MyStrategy&gt;(C), /*RemoveKillFlags=*‍/false)</p>


<p>Return NULL to select the default (generic) machine scheduler.</p>


<p>Declaration at line 133 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/amdgputargetmachine-h">AMDGPUTargetMachine.h</a>, definition at line 1312 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/amdgputargetmachine-cpp">AMDGPUTargetMachine.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/namespaces/llvm/callingconv/#ac6aa1387c4375260e2468eb5a77fdb4cafd841a49aec1539bc88abc8ff9e170fb">llvm::CallingConv::C</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a5365898dd1deb10d065e288a2babd511">llvm::createGenericSchedLive</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#ab36ef7fb029dbd7ed2314db341b9f854">llvm::createLoadClusterDAGMutation</a> and <a href="/web-llvm/docs/api/namespaces/llvm/#a7bc2ad470d8a41e9423748814b0e3596">llvm::createStoreClusterDAGMutation</a>.</p>

</div>
</div>

### getAMDGPUTargetMachine() {#a01925ea9dc3f5339a6d96badbbd494b9}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">AMDGPUTargetMachine &amp; llvm::AMDGPUPassConfig::getAMDGPUTargetMachine ()</td>
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



<p>Definition at line 128 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/amdgputargetmachine-h">AMDGPUTargetMachine.h</a>.</p>


<p>Reference <a href="/web-llvm/docs/api/classes/llvm/targetpassconfig/#aca23623f476d3929484bdad4a5ce54d8">llvm::TargetPassConfig::getTM</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/classes/anonymous-r600targetmachine-cpp-/r600passconfig/#a0aac30bcdbc669ba554c435915c8ad52">anonymous{R600TargetMachine.cpp}::R600PassConfig::addInstSelector</a>, <a href="#a3dfda91b1766a907bad7895b0c02c3ee">addInstSelector</a> and <a href="#ab4b7f9099a377d260c73ad9d7b464615">addIRPasses</a>.</p>

</div>
</div>

### getCSEConfig() {#a0c0af5bfedd6d1ad0d1af0a957e4de16}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">std::unique_ptr&lt; CSEConfigBase &gt; llvm::AMDGPUPassConfig::getCSEConfig ()</td>
</tr>
</table>
</td>
<td class="doxyMemberLabelsRight">
<span class="doxyMemberLabels">
<span class="doxyMemberLabel virtual">virtual</span>
</span>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Returns the CSEConfig object to use for the current optimization level.</p>

<p>Declaration at line 143 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/amdgputargetmachine-h">AMDGPUTargetMachine.h</a>, definition at line 1045 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/amdgputargetmachine-cpp">AMDGPUTargetMachine.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/namespaces/llvm/#a4df597e75df6566e28b92bc525a093fb">llvm::getStandardCSEConfigForOpt</a> and <a href="/web-llvm/docs/api/classes/llvm/targetpassconfig/#a0e43f614336b22347dfdb6f20ea792df">llvm::TargetPassConfig::TM</a>.</p>

</div>
</div>

### isPassEnabled() {#a16f2b92989c6760a2447933b3c78a755}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool llvm::AMDGPUPassConfig::isPassEnabled (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/cl/opt">cl::opt</a>&lt; bool &gt; &amp; Opt, <a href="/web-llvm/docs/api/namespaces/llvm/#a8ec1bf8d7b792ca9fac56f8514db18d2">CodeGenOptLevel</a> Level=<a href="/web-llvm/docs/api/namespaces/llvm/#a8ec1bf8d7b792ca9fac56f8514db18d2a7a1920d61156abc05a60135aefe8bc67">CodeGenOptLevel::Default</a>)</td>
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

<p><a href="/web-llvm/docs/api/namespaces/llvm/check">Check</a> if a pass is enabled given <span class="doxyComputerOutput">Opt</span> option.</p>


<p>The option always overrides defaults if explicitly used. Otherwise its default will be used given that a pass shall work at an optimization <span class="doxyComputerOutput">Level</span> minimum.</p>


<p>Definition at line 149 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/amdgputargetmachine-h">AMDGPUTargetMachine.h</a>.</p>


<p>References <a href="/web-llvm/docs/api/namespaces/llvm/#a8ec1bf8d7b792ca9fac56f8514db18d2a7a1920d61156abc05a60135aefe8bc67">llvm::Default</a>, <a href="/web-llvm/docs/api/classes/llvm/cl/option/#a2dc75fafb68e7669e776e19da7857cdf">llvm::cl::Option::getNumOccurrences</a> and <a href="/web-llvm/docs/api/classes/llvm/targetpassconfig/#a0e43f614336b22347dfdb6f20ea792df">llvm::TargetPassConfig::TM</a>.</p>


<p>Referenced by <a href="#ad3c43a064022801bdca206ced049a0ff">addCodeGenPrepare</a>, <a href="#ab4b7f9099a377d260c73ad9d7b464615">addIRPasses</a>, <a href="/web-llvm/docs/api/classes/anonymous-amdgputargetmachine-cpp-/gcnpassconfig/#ac27c6922c2bb7ff1be0935f45a9e51aa">anonymous{AMDGPUTargetMachine.cpp}::GCNPassConfig::addMachineSSAOptimization</a>, <a href="/web-llvm/docs/api/classes/anonymous-amdgputargetmachine-cpp-/gcnpassconfig/#a9b46039eaf0e1d0d70654fb984590de2">anonymous{AMDGPUTargetMachine.cpp}::GCNPassConfig::addOptimizedRegAlloc</a>, <a href="/web-llvm/docs/api/classes/anonymous-amdgputargetmachine-cpp-/gcnpassconfig/#aeb47f242712c201352b881147ea41e90">anonymous{AMDGPUTargetMachine.cpp}::GCNPassConfig::addPreEmitPass</a>, <a href="#a6d1d286b7f3eed2617be594252bcfafd">addStraightLineScalarOptimizationPasses</a> and <a href="/web-llvm/docs/api/classes/anonymous-amdgputargetmachine-cpp-/gcnpassconfig/#abc91f335d0788469b44e409f15109585">anonymous{AMDGPUTargetMachine.cpp}::GCNPassConfig::createPostMachineScheduler</a>.</p>

</div>
</div>

</div>

<hr/>

The documentation for this class was generated from the following files:

<ul>
<li><a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/amdgputargetmachine-cpp">AMDGPUTargetMachine.cpp</a></li>
<li><a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/amdgputargetmachine-h">AMDGPUTargetMachine.h</a></li>
</ul>

<hr/>

<p class="doxyGeneratedBy">Generated via <a href="https://github.com/xpack/doxygen2docusaurus">doxygen2docusaurus</a> by <a href="https://www.doxygen.nl">Doxygen</a> 1.14.0.</p>

</div>
