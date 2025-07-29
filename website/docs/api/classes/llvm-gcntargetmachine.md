---

# DO NOT EDIT!
# Automatically generated via doxygen2docusaurus by Doxygen.

slug: /api/classes/llvm/gcntargetmachine
custom_edit_url: null
toc_max_heading_level: 4
keywords:
  - doxygen
  - reference
  - class

---

<div class="doxyPage">

# `GCNTargetMachine` Class



## Declaration

<div class="doxyDeclaration">
class llvm::GCNTargetMachine { ... }
</div>

## Included Headers

<div class="doxyIncludesList">#include "<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/amdgputargetmachine-h">Target/AMDGPU/AMDGPUTargetMachine.h</a>"
</div>

## Base class

<table class="doxyMembersIndex">

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">class</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/amdgputargetmachine">AMDGPUTargetMachine</a></td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a8e592210e9540d3f23611c42ac500170">GCNTargetMachine</a> (const Target &amp;T, const Triple &amp;TT, StringRef CPU, StringRef FS, const TargetOptions &amp;Options, std::optional&lt; Reloc::Model &gt; RM, std::optional&lt; CodeModel::Model &gt; CM, CodeGenOptLevel OL, bool JIT)</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/targetpassconfig">TargetPassConfig</a> *</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a704ab5e98d818dd7cd40cfd96eb5ec3c">createPassConfig</a> (PassManagerBase &amp;PM) override</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Create a pass configuration object to be used by addPassToEmitX methods for generating a pipeline of CodeGen passes. <a href="#a704ab5e98d818dd7cd40cfd96eb5ec3c">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/targetsubtargetinfo">TargetSubtargetInfo</a> *</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a0fec1667ac50cd92d5de25da9c53f704">getSubtargetImpl</a> (const Function &amp;) const override</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Virtual method implemented by subclasses that returns a reference to that target's TargetSubtargetInfo-derived member variable. <a href="#a0fec1667ac50cd92d5de25da9c53f704">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/targettransforminfo">TargetTransformInfo</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a0644592b5179f66e392d08df484285d2">getTargetTransformInfo</a> (const Function &amp;F) const override</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Get a <a href="/web-llvm/docs/api/classes/llvm/targettransforminfo">TargetTransformInfo</a> implementation for the target. <a href="#a0644592b5179f66e392d08df484285d2">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">bool</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a83877dfabd05e12d6735da11cfab7f5d">useIPRA</a> () const override</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>True if the target wants to use interprocedural register allocation by default. <a href="#a83877dfabd05e12d6735da11cfab7f5d">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/error">Error</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a6b558554de041312d8c8cd3f1609c90c">buildCodeGenPipeline</a> (ModulePassManager &amp;MPM, raw_pwrite_stream &amp;Out, raw_pwrite_stream *DwoOut, CodeGenFileType FileType, const CGPassBuilderOption &amp;Opts, PassInstrumentationCallbacks *PIC) override</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a5280c4cea74a327750a50fbbc7ca77d7">registerMachineRegisterInfoCallback</a> (MachineFunction &amp;MF) const override</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/structs/llvm/machinefunctioninfo">MachineFunctionInfo</a> *</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ae59b54cd21fc309e4ee5c08d209d011b">createMachineFunctionInfo</a> (BumpPtrAllocator &amp;Allocator, const Function &amp;F, const TargetSubtargetInfo *STI) const override</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Create the target's instance of <a href="/web-llvm/docs/api/structs/llvm/machinefunctioninfo">MachineFunctionInfo</a>. <a href="#ae59b54cd21fc309e4ee5c08d209d011b">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/structs/llvm/yaml/machinefunctioninfo">yaml::MachineFunctionInfo</a> *</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a6d6bfef3aab11a4138ad665a8a29ad07">createDefaultFuncInfoYAML</a> () const override</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Allocate and return a default initialized instance of the YAML representation for the <a href="/web-llvm/docs/api/structs/llvm/machinefunctioninfo">MachineFunctionInfo</a>. <a href="#a6d6bfef3aab11a4138ad665a8a29ad07">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/structs/llvm/yaml/machinefunctioninfo">yaml::MachineFunctionInfo</a> *</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a5f21271c9d2a610d15219c54ba44bef3">convertFuncInfoToYAML</a> (const MachineFunction &amp;MF) const override</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Allocate and initialize an instance of the YAML representation of the <a href="/web-llvm/docs/api/structs/llvm/machinefunctioninfo">MachineFunctionInfo</a>. <a href="#a5f21271c9d2a610d15219c54ba44bef3">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">bool</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a546e4834a3dc92d96ef8b7598f552a45">parseMachineFunctionInfo</a> (const yaml::MachineFunctionInfo &amp;, PerFunctionMIParsingState &amp;PFS, SMDiagnostic &amp;Error, SMRange &amp;SourceRange) const override</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Parse out the target's <a href="/web-llvm/docs/api/structs/llvm/machinefunctioninfo">MachineFunctionInfo</a> from the YAML reprsentation. <a href="#a546e4834a3dc92d96ef8b7598f552a45">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

</table>

## Private Member Attributes Index

<table class="doxyMembersIndex">

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/stringmap">StringMap</a>&lt; std::unique_ptr&lt; <a href="/web-llvm/docs/api/classes/llvm/gcnsubtarget">GCNSubtarget</a> &gt; &gt;</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a1337593b581c7684a1fe7a8bc2bbef4d">SubtargetMap</a></td>
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


<p>Definition at line 80 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/amdgputargetmachine-h">AMDGPUTargetMachine.h</a>.</p>


<div class="doxySectionDef">

## Public Constructors

### GCNTargetMachine() {#a8e592210e9540d3f23611c42ac500170}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">GCNTargetMachine::GCNTargetMachine (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/target">Target</a> &amp; T, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/triple">Triple</a> &amp; TT, <a href="/web-llvm/docs/api/classes/llvm/stringref">StringRef</a> CPU, <a href="/web-llvm/docs/api/classes/llvm/stringref">StringRef</a> FS, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/targetoptions">TargetOptions</a> &amp; Options, std::optional&lt; <a href="/web-llvm/docs/api/namespaces/llvm/reloc/#af59f6dc86e80aaf56f1afd155eebf568">Reloc::Model</a> &gt; RM, std::optional&lt; <a href="/web-llvm/docs/api/namespaces/llvm/codemodel/#afc59396a9e5809fc92938e203d91a8df">CodeModel::Model</a> &gt; CM, <a href="/web-llvm/docs/api/namespaces/llvm/#a8ec1bf8d7b792ca9fac56f8514db18d2">CodeGenOptLevel</a> OL, bool JIT)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Declaration at line 85 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/amdgputargetmachine-h">AMDGPUTargetMachine.h</a>, definition at line 998 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/amdgputargetmachine-cpp">AMDGPUTargetMachine.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/classes/llvm/amdgputargetmachine/#a5d81421a7c6e65b440e6a2deff9beaa6">llvm::AMDGPUTargetMachine::AMDGPUTargetMachine</a>, <a href="/web-llvm/docs/api/classes/llvm/targetmachine/#ab1fb67187fc37e569cc5171cbebba873">llvm::TargetMachine::Options</a>, <a href="/web-llvm/docs/api/classes/llvm/targetmachine/#a588867fa922c392886b07e0ad42038b4">llvm::TargetMachine::RM</a> and <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/mips/mips16isellowering-cpp/#a0acb682b8260ab1c60b918599864e2e5">T</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Public Member Functions

### buildCodeGenPipeline() {#a6b558554de041312d8c8cd3f1609c90c}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">Error GCNTargetMachine::buildCodeGenPipeline (<a href="/web-llvm/docs/api/namespaces/llvm/#a79ab9199d2ba6a1c9cac2b79efc194a3">ModulePassManager</a> &amp; MPM, <a href="/web-llvm/docs/api/classes/llvm/raw-pwrite-stream">raw_pwrite_stream</a> &amp; Out, <a href="/web-llvm/docs/api/classes/llvm/raw-pwrite-stream">raw_pwrite_stream</a> * DwoOut, <a href="/web-llvm/docs/api/namespaces/llvm/#a73b761f8d40500a5a28889569526b260">CodeGenFileType</a> FileType, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/structs/llvm/cgpassbuilderoption">CGPassBuilderOption</a> &amp; Opts, <a href="/web-llvm/docs/api/classes/llvm/passinstrumentationcallbacks">PassInstrumentationCallbacks</a> * PIC)</td>
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



<p>Declaration at line 99 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/amdgputargetmachine-h">AMDGPUTargetMachine.h</a>, definition at line 1033 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/amdgputargetmachine-cpp">AMDGPUTargetMachine.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/classes/llvm/codegenpassbuilder/#a6476029eb211f7d7bc0bf419d58ac6c6">llvm::CodeGenPassBuilder&lt; DerivedT, TargetMachineT &gt;::buildPipeline</a> and <a href="/web-llvm/docs/api/files/lib/lib/passes/passbuilderbindings-cpp/#ad4d247df65c12507f447383be37d7ccb">PIC</a>.</p>

</div>
</div>

### convertFuncInfoToYAML() {#a5f21271c9d2a610d15219c54ba44bef3}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">yaml::MachineFunctionInfo * GCNTargetMachine::convertFuncInfoToYAML (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/machinefunction">MachineFunction</a> &amp; MF)</td>
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

<p>Allocate and initialize an instance of the YAML representation of the <a href="/web-llvm/docs/api/structs/llvm/machinefunctioninfo">MachineFunctionInfo</a>.</p>

<p>Declaration at line 113 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/amdgputargetmachine-h">AMDGPUTargetMachine.h</a>, definition at line 1704 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/amdgputargetmachine-cpp">AMDGPUTargetMachine.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/classes/llvm/machinefunction/#ab7feae1932b436c8630e247166ec42b7">llvm::MachineFunction::getInfo</a>, <a href="/web-llvm/docs/api/classes/llvm/gcnsubtarget/#a4e872608c63bfb1bed8f7d133d96c178">llvm::GCNSubtarget::getRegisterInfo</a> and <a href="/web-llvm/docs/api/classes/llvm/machinefunction/#a3825368aca2bc1550d173660df4da6a6">llvm::MachineFunction::getSubtarget</a>.</p>

</div>
</div>

### createDefaultFuncInfoYAML() {#a6d6bfef3aab11a4138ad665a8a29ad07}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">yaml::MachineFunctionInfo * GCNTargetMachine::createDefaultFuncInfoYAML ()</td>
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

<p>Allocate and return a default initialized instance of the YAML representation for the <a href="/web-llvm/docs/api/structs/llvm/machinefunctioninfo">MachineFunctionInfo</a>.</p>

<p>Declaration at line 111 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/amdgputargetmachine-h">AMDGPUTargetMachine.h</a>, definition at line 1699 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/amdgputargetmachine-cpp">AMDGPUTargetMachine.cpp</a>.</p>

</div>
</div>

### createMachineFunctionInfo() {#ae59b54cd21fc309e4ee5c08d209d011b}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">MachineFunctionInfo * GCNTargetMachine::createMachineFunctionInfo (<a href="/web-llvm/docs/api/namespaces/llvm/#a8e612822d4ba7bb36c9c79582a567108">BumpPtrAllocator</a> &amp; Allocator, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/function">Function</a> &amp; F, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/targetsubtargetinfo">TargetSubtargetInfo</a> * STI)</td>
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

<p>Create the target's instance of <a href="/web-llvm/docs/api/structs/llvm/machinefunctioninfo">MachineFunctionInfo</a>.</p>

<p>Declaration at line 108 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/amdgputargetmachine-h">AMDGPUTargetMachine.h</a>, definition at line 1692 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/amdgputargetmachine-cpp">AMDGPUTargetMachine.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/structs/llvm/machinefunctioninfo/#a06ad8b2e5a8e3c0f81f05c7870fb3b23">llvm::MachineFunctionInfo::create</a>, <a href="/web-llvm/docs/api/files/lib/lib/support/md5-cpp/#a96d73bbd7af15cb1fc38c3f4a3bd82e9">F</a> and <a href="/web-llvm/docs/api/classes/llvm/targetmachine/#aaebd1c0e5f028848cc0e548bf015aaf1">llvm::TargetMachine::STI</a>.</p>

</div>
</div>

### createPassConfig() {#a704ab5e98d818dd7cd40cfd96eb5ec3c}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">TargetPassConfig * GCNTargetMachine::createPassConfig (<a href="/web-llvm/docs/api/classes/llvm/legacy/passmanagerbase">PassManagerBase</a> &amp; PM)</td>
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

<p>Create a pass configuration object to be used by addPassToEmitX methods for generating a pipeline of CodeGen passes.</p>


<p>createPassConfig - Create a pass configuration object to be used by addPassToEmitX methods for generating a pipeline of CodeGen passes.</p>


<p>Targets may override this to extend <a href="/web-llvm/docs/api/classes/llvm/targetpassconfig">TargetPassConfig</a>.</p>


<p>Declaration at line 91 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/amdgputargetmachine-h">AMDGPUTargetMachine.h</a>, definition at line 1682 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/amdgputargetmachine-cpp">AMDGPUTargetMachine.cpp</a>.</p>

</div>
</div>

### getSubtargetImpl() {#a0fec1667ac50cd92d5de25da9c53f704}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">const TargetSubtargetInfo * GCNTargetMachine::getSubtargetImpl (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/function">Function</a> &amp;)</td>
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

<p>Virtual method implemented by subclasses that returns a reference to that target's TargetSubtargetInfo-derived member variable.</p>

<p>Declaration at line 93 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/amdgputargetmachine-h">AMDGPUTargetMachine.h</a>, definition at line 1007 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/amdgputargetmachine-cpp">AMDGPUTargetMachine.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/classes/llvm/smallstring/#ac22cf1a1c08b7ccaefc51508536312a4">llvm::SmallString&lt; InternalLen &gt;::append</a>, <a href="/web-llvm/docs/api/files/lib/lib/support/md5-cpp/#a96d73bbd7af15cb1fc38c3f4a3bd82e9">F</a>, <a href="/web-llvm/docs/api/classes/llvm/amdgputargetmachine/#a388dd65231ec660233341f507f02f91d">llvm::AMDGPUTargetMachine::getFeatureString</a>, <a href="/web-llvm/docs/api/classes/llvm/amdgputargetmachine/#ac7c7ab2466ba18c193faea8966362085">llvm::AMDGPUTargetMachine::getGPUName</a>, <a href="/web-llvm/docs/api/files/lib/lib/support/md5-cpp/#ac0eafdc9ee161b71e7af98af736952fd">I</a>, <a href="/web-llvm/docs/api/classes/llvm/targetmachine/#af0a50afebb9bed07d36be2bac4c6f729">llvm::TargetMachine::resetTargetOptions</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/amdgputargetmachine-cpp/#af321bb5b53cba648dec8306c269407ad">ScalarizeGlobal</a> and <a href="/web-llvm/docs/api/classes/llvm/targetmachine/#a05856d96e88224279af8b29edfd1c9ad">llvm::TargetMachine::TargetTriple</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/classes/anonymous-nvptxtargetmachine-cpp-/nvptxpassconfig/#a579752615e6d1eb6de1d78a9c96f984e">anonymous{NVPTXTargetMachine.cpp}::NVPTXPassConfig::addIRPasses</a>.</p>

</div>
</div>

### getTargetTransformInfo() {#a0644592b5179f66e392d08df484285d2}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">TargetTransformInfo GCNTargetMachine::getTargetTransformInfo (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/function">Function</a> &amp; F)</td>
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

<p>Get a <a href="/web-llvm/docs/api/classes/llvm/targettransforminfo">TargetTransformInfo</a> implementation for the target.</p>


<p>The <a href="/web-llvm/docs/api/namespaces/llvm/#aa0d69e81725c10fa5407f0bf34462068">TTI</a> returned uses the common code generator to answer queries about the IR.</p>


<p>Declaration at line 95 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/amdgputargetmachine-h">AMDGPUTargetMachine.h</a>, definition at line 1029 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/amdgputargetmachine-cpp">AMDGPUTargetMachine.cpp</a>.</p>


<p>Reference <a href="/web-llvm/docs/api/files/lib/lib/support/md5-cpp/#a96d73bbd7af15cb1fc38c3f4a3bd82e9">F</a>.</p>

</div>
</div>

### parseMachineFunctionInfo() {#a546e4834a3dc92d96ef8b7598f552a45}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool GCNTargetMachine::parseMachineFunctionInfo (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/structs/llvm/yaml/machinefunctioninfo">yaml::MachineFunctionInfo</a> &amp;, <a href="/web-llvm/docs/api/structs/llvm/perfunctionmiparsingstate">PerFunctionMIParsingState</a> &amp; PFS, <a href="/web-llvm/docs/api/classes/llvm/smdiagnostic">SMDiagnostic</a> &amp; Error, <a href="/web-llvm/docs/api/classes/llvm/smrange">SMRange</a> &amp; SourceRange)</td>
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

<p>Parse out the target's <a href="/web-llvm/docs/api/structs/llvm/machinefunctioninfo">MachineFunctionInfo</a> from the YAML reprsentation.</p>

<p>Declaration at line 114 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/amdgputargetmachine-h">AMDGPUTargetMachine.h</a>, definition at line 1710 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/amdgputargetmachine-cpp">AMDGPUTargetMachine.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/hexagon/lib/target/hexagon/mctargetdesc/hexagonmccodeemitter-cpp/#ae4dfd7b0d66121016d6466d2ff10e8ba">_</a>, <a href="/web-llvm/docs/api/files/lib/lib/ir/builtingcs-cpp/#a2e38c85003a042421cde1647632d0b72">A</a>, <a href="/web-llvm/docs/api/structs/llvm/yaml/simachinefunctioninfo/#ae201cd41bc4b333606be1bbb656c1333">llvm::yaml::SIMachineFunctionInfo::ArgInfo</a>, <a href="/web-llvm/docs/api/structs/llvm/argdescriptor/#a5ba9ffd4c829c39d10d780ebd8c55ed9">llvm::ArgDescriptor::createArg</a>, <a href="/web-llvm/docs/api/structs/llvm/argdescriptor/#ab80da72ac9122b5c4e4a0a2cfaa25d9e">llvm::ArgDescriptor::createRegister</a>, <a href="/web-llvm/docs/api/structs/llvm/argdescriptor/#a2b90780a92bdcaed0a47e50d86ec6e6b">llvm::ArgDescriptor::createStack</a>, <a href="/web-llvm/docs/api/structs/llvm/amdgpufunctionarginfo/#a42381ce8015f81db8cf591030d5e5863">llvm::AMDGPUFunctionArgInfo::DispatchID</a>, <a href="/web-llvm/docs/api/structs/llvm/amdgpufunctionarginfo/#ade8d1371d868ed5faaea7710aced1eff">llvm::AMDGPUFunctionArgInfo::DispatchPtr</a>, <a href="/web-llvm/docs/api/classes/llvm/sourcemgr/#a346262ff27e71aff626fe6548ef8a777adaf658d40b0b4eb15c0350864c87c2b8">llvm::SourceMgr::DK_Error</a>, <a href="/web-llvm/docs/api/structs/llvm/simoderegisterdefaults/#a5eff9b4ca99cdc0544e946f36ba98458">llvm::SIModeRegisterDefaults::DX10Clamp</a>, <a href="/web-llvm/docs/api/structs/llvm/yaml/simode/#a1d5dd9919ead63bd4811537de31545da">llvm::yaml::SIMode::DX10Clamp</a>, <a href="/web-llvm/docs/api/structs/llvm/amdgpufunctionarginfo/#ade04e61f515d6522a4f300c88bea66d6">llvm::AMDGPUFunctionArgInfo::FlatScratchInit</a>, <a href="/web-llvm/docs/api/structs/llvm/simoderegisterdefaults/#af1d0653d028bac2c78f7eec72f32472e">llvm::SIModeRegisterDefaults::FP32Denormals</a>, <a href="/web-llvm/docs/api/structs/llvm/yaml/simode/#ac5f42c763551470eb4c1a27d0788da2c">llvm::yaml::SIMode::FP32InputDenormals</a>, <a href="/web-llvm/docs/api/structs/llvm/yaml/simode/#a5d7371d8fab663c0d97f18685bf447e2">llvm::yaml::SIMode::FP32OutputDenormals</a>, <a href="/web-llvm/docs/api/structs/llvm/simoderegisterdefaults/#a69743300b37bda17c4cf7690f2dc2fac">llvm::SIModeRegisterDefaults::FP64FP16Denormals</a>, <a href="/web-llvm/docs/api/structs/llvm/yaml/simode/#a3a533dd67ac0ca8ec6364d2ac6c38160">llvm::yaml::SIMode::FP64FP16InputDenormals</a>, <a href="/web-llvm/docs/api/structs/llvm/yaml/simode/#a2e23011de5029d40391d62210c2ec781">llvm::yaml::SIMode::FP64FP16OutputDenormals</a>, <a href="/web-llvm/docs/api/structs/llvm/yaml/simachinefunctioninfo/#a820d8ccceda9b8f7790330579694ef91">llvm::yaml::SIMachineFunctionInfo::FrameOffsetReg</a>, <a href="/web-llvm/docs/api/classes/llvm/memorybuffer/#a2037f11968aa30bfda0b4de9f335624d">llvm::MemoryBuffer::getBufferIdentifier</a>, <a href="/web-llvm/docs/api/classes/llvm/machinefunction/#ab7feae1932b436c8630e247166ec42b7">llvm::MachineFunction::getInfo</a>, <a href="/web-llvm/docs/api/classes/llvm/sourcemgr/#a208a36067279ac9669eb29f34ae9daed">llvm::SourceMgr::getMainFileID</a>, <a href="/web-llvm/docs/api/classes/llvm/sourcemgr/#a56740d2dab215f8642e6acf4ff49c62d">llvm::SourceMgr::getMemoryBuffer</a>, <a href="/web-llvm/docs/api/classes/llvm/machinefunction/#a3825368aca2bc1550d173660df4da6a6">llvm::MachineFunction::getSubtarget</a>, <a href="/web-llvm/docs/api/structs/llvm/yaml/simachinefunctioninfo/#adfffa2c248385b2fec7ee03ba4d052ae">llvm::yaml::SIMachineFunctionInfo::HasInitWholeWave</a>, <a href="/web-llvm/docs/api/structs/llvm/denormalmode/#a29b26e3ae30f3f6ec4106ff181282893ad6fd23eb0b98a2d4551582753191b6da">llvm::DenormalMode::IEEE</a>, <a href="/web-llvm/docs/api/structs/llvm/simoderegisterdefaults/#a7238526aeceaef9a0db1ab0c21a0cf0e">llvm::SIModeRegisterDefaults::IEEE</a>, <a href="/web-llvm/docs/api/structs/llvm/yaml/simode/#a0609f372b1e45f378d3b89ddf97ceaa0">llvm::yaml::SIMode::IEEE</a>, <a href="/web-llvm/docs/api/structs/llvm/amdgpufunctionarginfo/#a4367370c92803e2cf72ee3bc26f97520">llvm::AMDGPUFunctionArgInfo::ImplicitArgPtr</a>, <a href="/web-llvm/docs/api/structs/llvm/amdgpufunctionarginfo/#ae747b1bb20161699442a10c32d1c83fc">llvm::AMDGPUFunctionArgInfo::ImplicitBufferPtr</a>, <a href="/web-llvm/docs/api/classes/llvm/simachinefunctioninfo/#a06cda8485133e5602199f315fd0c304e">llvm::SIMachineFunctionInfo::initializeBaseYamlFields</a>, <a href="/web-llvm/docs/api/structs/llvm/denormalmode/#a1b79f1995991b0a757a4d04969c3717f">llvm::DenormalMode::Input</a>, <a href="/web-llvm/docs/api/structs/llvm/amdgpufunctionarginfo/#ab0303f30b08e804220730feac44a5880">llvm::AMDGPUFunctionArgInfo::KernargSegmentPtr</a>, <a href="/web-llvm/docs/api/structs/llvm/amdgpufunctionarginfo/#a9202294e9cdcac74422aabd2c041c1e9">llvm::AMDGPUFunctionArgInfo::LDSKernelId</a>, <a href="/web-llvm/docs/api/structs/llvm/yaml/simachinefunctioninfo/#a8567716d726b82e9ea28bdf407454514">llvm::yaml::SIMachineFunctionInfo::LongBranchReservedReg</a>, <a href="/web-llvm/docs/api/structs/llvm/perfunctionmiparsingstate/#ae7f8c6f160583712d2adaafb4cca24fe">llvm::PerFunctionMIParsingState::MF</a>, <a href="/web-llvm/docs/api/structs/llvm/yaml/simachinefunctioninfo/#ade7132a796d315b462bdc59fb10d3a99">llvm::yaml::SIMachineFunctionInfo::Mode</a>, <a href="/web-llvm/docs/api/structs/llvm/denormalmode/#aa1be940c9e7d0c7ed20dfdaf5731b082">llvm::DenormalMode::Output</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#ae6d6d411dc7c73c8f28c468492c6a0e2">llvm::parseNamedRegisterReference</a>, <a href="/web-llvm/docs/api/structs/llvm/denormalmode/#a29b26e3ae30f3f6ec4106ff181282893a40bc80ae1d362a1461703637e946cbd8">llvm::DenormalMode::PreserveSign</a>, <a href="/web-llvm/docs/api/structs/llvm/amdgpufunctionarginfo/#a15c9948424096818cda93327de8345a8">llvm::AMDGPUFunctionArgInfo::PrivateSegmentBuffer</a>, <a href="/web-llvm/docs/api/structs/llvm/amdgpufunctionarginfo/#a3efcfd6546ab809d0d133983190eaff8">llvm::AMDGPUFunctionArgInfo::PrivateSegmentSize</a>, <a href="/web-llvm/docs/api/structs/llvm/amdgpufunctionarginfo/#a62ee299b4c716abdc806cd12ff8cd007">llvm::AMDGPUFunctionArgInfo::PrivateSegmentWaveByteOffset</a>, <a href="/web-llvm/docs/api/structs/llvm/amdgpufunctionarginfo/#aaf94e49aaa7a9c033bb73e45f3d491c2">llvm::AMDGPUFunctionArgInfo::QueuePtr</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/ve/lvlgen-cpp/#a0a198e38a5def54ba58bebc655eda8e7">RegName</a>, <a href="/web-llvm/docs/api/classes/llvm/simachinefunctioninfo/#afaed20eb9e5f290239aa67ce0e8d7a0c">llvm::SIMachineFunctionInfo::reserveWWMRegister</a>, <a href="/web-llvm/docs/api/structs/llvm/yaml/simachinefunctioninfo/#afae943f235ffb0ac6224181bc5d3b213">llvm::yaml::SIMachineFunctionInfo::ScratchRSrcReg</a>, <a href="/web-llvm/docs/api/classes/llvm/simachinefunctioninfo/#a24a896bd0b1be4f6ce1c3458612e5216">llvm::SIMachineFunctionInfo::setFlag</a>, <a href="/web-llvm/docs/api/classes/llvm/amdgpumachinefunction/#a10b5e43cf76cb088fdcd63d47146b703">llvm::AMDGPUMachineFunction::setInitWholeWave</a>, <a href="/web-llvm/docs/api/structs/llvm/yaml/simachinefunctioninfo/#a11b88b42beff3cee85a89eb7e5d3dfd3">llvm::yaml::SIMachineFunctionInfo::SGPRForEXECCopy</a>, <a href="/web-llvm/docs/api/structs/llvm/perfunctionmiparsingstate/#a04c6eaa02b55eaf51e4b182bd0c640cb">llvm::PerFunctionMIParsingState::SM</a>, <a href="/web-llvm/docs/api/structs/llvm/yaml/simachinefunctioninfo/#aee024587ab03348def87a3e3923fd5c9">llvm::yaml::SIMachineFunctionInfo::SpillPhysVGPRS</a>, <a href="/web-llvm/docs/api/structs/llvm/yaml/simachinefunctioninfo/#afba5cd76321da56b47ddaf51c4727576">llvm::yaml::SIMachineFunctionInfo::StackPtrOffsetReg</a>, <a href="/web-llvm/docs/api/structs/llvm/yaml/simachinefunctioninfo/#adc4e12fe2a000305ad25837db0d188f5">llvm::yaml::SIMachineFunctionInfo::VGPRForAGPRCopy</a>, <a href="/web-llvm/docs/api/structs/llvm/perfunctionmiparsingstate/#af04a49c4719319a475237aa431d2c1ba">llvm::PerFunctionMIParsingState::VRegInfos</a>, <a href="/web-llvm/docs/api/structs/llvm/perfunctionmiparsingstate/#a6c00589d8b2d82496406b0ceeb825d2a">llvm::PerFunctionMIParsingState::VRegInfosNamed</a>, <a href="/web-llvm/docs/api/structs/llvm/amdgpufunctionarginfo/#afd191e63ef0aa2a01dd831061eef82ce">llvm::AMDGPUFunctionArgInfo::WorkGroupIDX</a>, <a href="/web-llvm/docs/api/structs/llvm/amdgpufunctionarginfo/#a161c5fd1ec307e6a2ee486cb085d2fbf">llvm::AMDGPUFunctionArgInfo::WorkGroupIDY</a>, <a href="/web-llvm/docs/api/structs/llvm/amdgpufunctionarginfo/#a21dd05fd0635d96f9ec6aeb2581cfc50">llvm::AMDGPUFunctionArgInfo::WorkGroupIDZ</a>, <a href="/web-llvm/docs/api/structs/llvm/amdgpufunctionarginfo/#a6918593b5d70a5a1779e27e3bb6ad20c">llvm::AMDGPUFunctionArgInfo::WorkGroupInfo</a>, <a href="/web-llvm/docs/api/structs/llvm/amdgpufunctionarginfo/#ada579eecd637ec5006a3bd6528b4bcc5">llvm::AMDGPUFunctionArgInfo::WorkItemIDX</a>, <a href="/web-llvm/docs/api/structs/llvm/amdgpufunctionarginfo/#a89c7432158b2f308f29bd9d024990df0">llvm::AMDGPUFunctionArgInfo::WorkItemIDY</a>, <a href="/web-llvm/docs/api/structs/llvm/amdgpufunctionarginfo/#a6a2845dd7c699ffbb46fc6e809ffd2e4">llvm::AMDGPUFunctionArgInfo::WorkItemIDZ</a> and <a href="/web-llvm/docs/api/structs/llvm/yaml/simachinefunctioninfo/#a2e7d99cf6836e2e91f35895642a4772b">llvm::yaml::SIMachineFunctionInfo::WWMReservedRegs</a>.</p>

</div>
</div>

### registerMachineRegisterInfoCallback() {#a5280c4cea74a327750a50fbbc7ca77d7}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void GCNTargetMachine::registerMachineRegisterInfoCallback (<a href="/web-llvm/docs/api/classes/llvm/machinefunction">MachineFunction</a> &amp; MF)</td>
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



<p>Declaration at line 105 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/amdgputargetmachine-h">AMDGPUTargetMachine.h</a>, definition at line 1686 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/amdgputargetmachine-cpp">AMDGPUTargetMachine.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/classes/llvm/machineregisterinfo/#a8ff1430f9e38299f37b3ce2b84d5b2d8">llvm::MachineRegisterInfo::addDelegate</a>, <a href="/web-llvm/docs/api/classes/llvm/machinefunction/#ab7feae1932b436c8630e247166ec42b7">llvm::MachineFunction::getInfo</a> and <a href="/web-llvm/docs/api/classes/llvm/machinefunction/#a810234b6b3d223b7c74a4253fcc5ea5e">llvm::MachineFunction::getRegInfo</a>.</p>

</div>
</div>

### useIPRA() {#a83877dfabd05e12d6735da11cfab7f5d}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool llvm::GCNTargetMachine::useIPRA ()</td>
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

<p>True if the target wants to use interprocedural register allocation by default.</p>


<p>The -enable-ipra flag can be used to override this.</p>


<p>Definition at line 97 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/amdgputargetmachine-h">AMDGPUTargetMachine.h</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Private Member Attributes

### SubtargetMap {#a1337593b581c7684a1fe7a8bc2bbef4d}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">StringMap&lt;std::unique_ptr&lt;GCNSubtarget&gt; &gt; llvm::GCNTargetMachine::SubtargetMap</td>
</tr>
</table>
</td>
<td class="doxyMemberLabelsRight">
<span class="doxyMemberLabels">
<span class="doxyMemberLabel mutable">mutable</span>
</span>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 82 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/amdgputargetmachine-h">AMDGPUTargetMachine.h</a>.</p>

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

<p class="doxyGeneratedBy">Generated via <a href="https://github.com/xpack/doxygen2docusaurus">doxygen2docusaurus</a> by <a href="https://www.doxygen.nl">Doxygen</a> 1.15.0.</p>

</div>
