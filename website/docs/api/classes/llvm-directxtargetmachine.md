---

# DO NOT EDIT!
# Automatically generated via doxygen2docusaurus by Doxygen.

slug: /api/classes/llvm/directxtargetmachine
custom_edit_url: null
toc_max_heading_level: 4
keywords:
  - doxygen
  - reference
  - class

---

<div class="doxyPage">

# `DirectXTargetMachine` Class



## Declaration

<div class="doxyDeclaration">
class llvm::DirectXTargetMachine { ... }
</div>

## Included Headers

<div class="doxyIncludesList">#include "<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/directx/directxtargetmachine-h">Target/DirectX/DirectXTargetMachine.h</a>"
</div>

## Base class

<table class="doxyMembersIndex">

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">class</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/codegentargetmachineimpl">CodeGenTargetMachineImpl</a></td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>implements a set of functionality in the <span class="doxyComputerOutput"><a href="/web-llvm/docs/api/classes/llvm/targetmachine">TargetMachine</a></span> class for targets that make use of the independent code generator (CodeGen) library. <a href="/web-llvm/docs/api/classes/llvm/codegentargetmachineimpl/#details">More...</a></p>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a6481c4d2d43db381d48cc39fa16e57ea">DirectXTargetMachine</a> (const Target &amp;T, const Triple &amp;TT, StringRef CPU, StringRef FS, const TargetOptions &amp;Options, std::optional&lt; Reloc::Model &gt; RM, std::optional&lt; CodeModel::Model &gt; CM, CodeGenOptLevel OL, bool JIT)</td>
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

## Public Destructor Index

<table class="doxyMembersIndex">

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a553980ac5f807f6d419bc4c5ca167f83">~DirectXTargetMachine</a> () override</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">bool</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ac9ec6dcf573b94dece0bcd8511579e4d">addPassesToEmitFile</a> (PassManagerBase &amp;PM, raw_pwrite_stream &amp;Out, raw_pwrite_stream *DwoOut, CodeGenFileType FileType, bool DisableVerify, MachineModuleInfoWrapperPass *MMIWP) override</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Add passes to the specified pass manager to get the specified file emitted. <a href="#ac9ec6dcf573b94dece0bcd8511579e4d">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">bool</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#af1fa9db23b9346cbce69e6842e4ef6e4">addPassesToEmitMC</a> (PassManagerBase &amp;PM, MCContext *&amp;Ctx, raw_pwrite_stream &amp;Out, bool DisableVerify) override</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Add passes to the specified pass manager to get machine code emitted with the <a href="/web-llvm/docs/api/classes/llvm/mcjit">MCJIT</a>. <a href="#af1fa9db23b9346cbce69e6842e4ef6e4">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/directxsubtarget">DirectXSubtarget</a> *</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ac2929ee021f17fceb935241fa501be4e">getSubtargetImpl</a> (const Function &amp;) const override</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Virtual method implemented by subclasses that returns a reference to that target's TargetSubtargetInfo-derived member variable. <a href="#ac2929ee021f17fceb935241fa501be4e">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/targetpassconfig">TargetPassConfig</a> *</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a34bed5e861468e6960983cbc1479cfeb">createPassConfig</a> (PassManagerBase &amp;PM) override</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Create a pass configuration object to be used by addPassToEmitX methods for generating a pipeline of CodeGen passes. <a href="#a34bed5e861468e6960983cbc1479cfeb">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/targetloweringobjectfile">TargetLoweringObjectFile</a> *</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a72596585053313c8395c5bf461e4d08a">getObjFileLowering</a> () const override</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/targettransforminfo">TargetTransformInfo</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a44bb013ebe7df275f5abd1bf27a342fe">getTargetTransformInfo</a> (const Function &amp;F) const override</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Get a <a href="/web-llvm/docs/api/classes/llvm/targettransforminfo">TargetTransformInfo</a> implementation for the target. <a href="#a44bb013ebe7df275f5abd1bf27a342fe">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">void</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#afe8c3dac47046a33c795f3de88524692">registerPassBuilderCallbacks</a> (PassBuilder &amp;PB) override</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Allow the target to modify the pass pipeline. <a href="#afe8c3dac47046a33c795f3de88524692">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

</table>

## Private Member Attributes Index

<table class="doxyMembersIndex">

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">std::unique_ptr&lt; <a href="/web-llvm/docs/api/classes/llvm/targetloweringobjectfile">TargetLoweringObjectFile</a> &gt;</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a2602203f0086eed6350312f1e3484819">TLOF</a></td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">std::unique_ptr&lt; <a href="/web-llvm/docs/api/classes/llvm/directxsubtarget">DirectXSubtarget</a> &gt;</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a1bf8c7f2a62797ec71655bf42ea65575">Subtarget</a></td>
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


<p>Definition at line 20 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/directx/directxtargetmachine-h">DirectXTargetMachine.h</a>.</p>


<div class="doxySectionDef">

## Public Constructors

### DirectXTargetMachine() {#a6481c4d2d43db381d48cc39fa16e57ea}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">DirectXTargetMachine::DirectXTargetMachine (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/target">Target</a> &amp; T, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/triple">Triple</a> &amp; TT, <a href="/web-llvm/docs/api/classes/llvm/stringref">StringRef</a> CPU, <a href="/web-llvm/docs/api/classes/llvm/stringref">StringRef</a> FS, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/targetoptions">TargetOptions</a> &amp; Options, std::optional&lt; <a href="/web-llvm/docs/api/namespaces/llvm/reloc/#af59f6dc86e80aaf56f1afd155eebf568">Reloc::Model</a> &gt; RM, std::optional&lt; <a href="/web-llvm/docs/api/namespaces/llvm/codemodel/#afc59396a9e5809fc92938e203d91a8df">CodeModel::Model</a> &gt; CM, <a href="/web-llvm/docs/api/namespaces/llvm/#a8ec1bf8d7b792ca9fac56f8514db18d2">CodeGenOptLevel</a> OL, bool JIT)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Declaration at line 25 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/directx/directxtargetmachine-h">DirectXTargetMachine.h</a>, definition at line 108 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/directx/directxtargetmachine-cpp">DirectXTargetMachine.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/classes/llvm/codegentargetmachineimpl/#a4480a9aa1ec7c3115acc998e187f5ab3">llvm::CodeGenTargetMachineImpl::CodeGenTargetMachineImpl</a>, <a href="/web-llvm/docs/api/classes/llvm/codegentargetmachineimpl/#a85849733e753fbf08f1c487b153c754b">llvm::CodeGenTargetMachineImpl::initAsmInfo</a>, <a href="/web-llvm/docs/api/classes/llvm/targetmachine/#ab1fb67187fc37e569cc5171cbebba873">llvm::TargetMachine::Options</a>, <a href="/web-llvm/docs/api/classes/llvm/targetmachine/#a588867fa922c392886b07e0ad42038b4">llvm::TargetMachine::RM</a> and <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/mips/mips16isellowering-cpp/#a0acb682b8260ab1c60b918599864e2e5">T</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Public Destructor

### \~DirectXTargetMachine() {#a553980ac5f807f6d419bc4c5ca167f83}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">DirectXTargetMachine::~DirectXTargetMachine ()</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Declaration at line 31 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/directx/directxtargetmachine-h">DirectXTargetMachine.h</a>, definition at line 124 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/directx/directxtargetmachine-cpp">DirectXTargetMachine.cpp</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Public Member Functions

### addPassesToEmitFile() {#ac9ec6dcf573b94dece0bcd8511579e4d}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool DirectXTargetMachine::addPassesToEmitFile (<a href="/web-llvm/docs/api/classes/llvm/legacy/passmanagerbase">PassManagerBase</a> &amp; PM, <a href="/web-llvm/docs/api/classes/llvm/raw-pwrite-stream">raw_pwrite_stream</a> &amp; Out, <a href="/web-llvm/docs/api/classes/llvm/raw-pwrite-stream">raw_pwrite_stream</a> * DwoOut, <a href="/web-llvm/docs/api/namespaces/llvm/#a73b761f8d40500a5a28889569526b260">CodeGenFileType</a> FileType, bool DisableVerify, <a href="/web-llvm/docs/api/classes/llvm/machinemoduleinfowrapperpass">MachineModuleInfoWrapperPass</a> * MMIWP)</td>
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

<p>Add passes to the specified pass manager to get the specified file emitted.</p>


<p>Typically this will involve several steps of code generation. <span class="doxyComputerOutput">MMIWP</span> is an optional parameter that, if set to non-nullptr, will be used to set the MachineModuloInfo for this PM.</p>


<p>Declaration at line 33 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/directx/directxtargetmachine-h">DirectXTargetMachine.h</a>, definition at line 131 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/directx/directxtargetmachine-cpp">DirectXTargetMachine.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/classes/llvm/legacy/passmanagerbase/#a2ce2eacfa52640d3a2feb2d46d561b85">llvm::legacy::PassManagerBase::add</a>, <a href="/web-llvm/docs/api/classes/llvm/codegentargetmachineimpl/#acf14ffe7608cbfcc75f2858e0eaa38e7">llvm::CodeGenTargetMachineImpl::addAsmPrinter</a>, <a href="/web-llvm/docs/api/classes/llvm/targetpassconfig/#a3082a93fec84f7658664ce7b4840b15c">llvm::TargetPassConfig::addCodeGenPrepare</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a73b761f8d40500a5a28889569526b260acb99c054b7e0e1eaaabe4deee41e5945">llvm::AssemblyFile</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a497dfeb699080e3b8888f2d8935fcc86">llvm::createDXContainerGlobalsPass</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#ab78ca7f9be0e383d7ea5e5cff4c9e2f2">llvm::createDXILEmbedderPass</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#ad83269dd85f628c29ac214437482d37f">llvm::createDXILPrettyPrinterLegacyPass</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a2a251d78dd347cd27b805f736d7e73b7">llvm::createDXILWriterPass</a>, <a href="#a34bed5e861468e6960983cbc1479cfeb">createPassConfig</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#acc83e523c1969f39981f64d42a1ba18a">llvm::createPrintModulePass</a>, <a href="/web-llvm/docs/api/classes/llvm/machinemoduleinfo/#a51904840e3bcc15ef2b99a101e972b02">llvm::MachineModuleInfo::getContext</a>, <a href="/web-llvm/docs/api/classes/llvm/machinemoduleinfowrapperpass/#ad007b7bc4433582715cfd375e3889042">llvm::MachineModuleInfoWrapperPass::getMMI</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a73b761f8d40500a5a28889569526b260abbb93ef26e3c101ff11cdd21cab08a94">llvm::Null</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a73b761f8d40500a5a28889569526b260a95aca07e95d9459c1bb31f4e7f9fda10">llvm::ObjectFile</a> and <a href="/web-llvm/docs/api/classes/llvm/targetpassconfig/#ad0db8596710a5666b67e513da0d9b415">llvm::TargetPassConfig::willCompleteCodeGenPipeline</a>.</p>

</div>
</div>

### addPassesToEmitMC() {#af1fa9db23b9346cbce69e6842e4ef6e4}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool DirectXTargetMachine::addPassesToEmitMC (<a href="/web-llvm/docs/api/classes/llvm/legacy/passmanagerbase">PassManagerBase</a> &amp; PM, <a href="/web-llvm/docs/api/classes/llvm/mccontext">MCContext</a> *&amp; Ctx, <a href="/web-llvm/docs/api/classes/llvm/raw-pwrite-stream">raw_pwrite_stream</a> &amp; Out, bool DisableVerify)</td>
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

<p>Add passes to the specified pass manager to get machine code emitted with the <a href="/web-llvm/docs/api/classes/llvm/mcjit">MCJIT</a>.</p>


<p>addPassesToEmitMC - Add passes to the specified pass manager to get machine code emitted with the <a href="/web-llvm/docs/api/classes/llvm/mcjit">MCJIT</a>.</p>


<p>This method returns true if machine code is not supported. It fills the <a href="/web-llvm/docs/api/classes/llvm/mccontext">MCContext</a> Ctx pointer which can be used to build custom <a href="/web-llvm/docs/api/classes/llvm/mcstreamer">MCStreamer</a>.</p>


<p>Declaration at line 38 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/directx/directxtargetmachine-h">DirectXTargetMachine.h</a>, definition at line 165 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/directx/directxtargetmachine-cpp">DirectXTargetMachine.cpp</a>.</p>

</div>
</div>

### createPassConfig() {#a34bed5e861468e6960983cbc1479cfeb}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">TargetPassConfig * DirectXTargetMachine::createPassConfig (<a href="/web-llvm/docs/api/classes/llvm/legacy/passmanagerbase">PassManagerBase</a> &amp; PM)</td>
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


<p>Declaration at line 43 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/directx/directxtargetmachine-h">DirectXTargetMachine.h</a>, definition at line 172 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/directx/directxtargetmachine-cpp">DirectXTargetMachine.cpp</a>.</p>


<p>Referenced by <a href="#ac9ec6dcf573b94dece0bcd8511579e4d">addPassesToEmitFile</a>.</p>

</div>
</div>

### getObjFileLowering() {#a72596585053313c8395c5bf461e4d08a}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">TargetLoweringObjectFile * llvm::DirectXTargetMachine::getObjFileLowering ()</td>
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



<p>Definition at line 45 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/directx/directxtargetmachine-h">DirectXTargetMachine.h</a>.</p>

</div>
</div>

### getSubtargetImpl() {#ac2929ee021f17fceb935241fa501be4e}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">const DirectXSubtarget * DirectXTargetMachine::getSubtargetImpl (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/function">Function</a> &amp;)</td>
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

<p>Declaration at line 41 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/directx/directxtargetmachine-h">DirectXTargetMachine.h</a>, definition at line 177 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/directx/directxtargetmachine-cpp">DirectXTargetMachine.cpp</a>.</p>

</div>
</div>

### getTargetTransformInfo() {#a44bb013ebe7df275f5abd1bf27a342fe}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">TargetTransformInfo DirectXTargetMachine::getTargetTransformInfo (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/function">Function</a> &amp; F)</td>
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


<p>Declaration at line 49 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/directx/directxtargetmachine-h">DirectXTargetMachine.h</a>, definition at line 182 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/directx/directxtargetmachine-cpp">DirectXTargetMachine.cpp</a>.</p>


<p>Reference <a href="/web-llvm/docs/api/files/lib/lib/support/md5-cpp/#a96d73bbd7af15cb1fc38c3f4a3bd82e9">F</a>.</p>

</div>
</div>

### registerPassBuilderCallbacks() {#afe8c3dac47046a33c795f3de88524692}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void DirectXTargetMachine::registerPassBuilderCallbacks (<a href="/web-llvm/docs/api/classes/llvm/passbuilder">PassBuilder</a> &amp;)</td>
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

<p>Allow the target to modify the pass pipeline.</p>

<p>Declaration at line 50 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/directx/directxtargetmachine-h">DirectXTargetMachine.h</a>, definition at line 126 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/directx/directxtargetmachine-cpp">DirectXTargetMachine.cpp</a>.</p>


<p>Reference <a href="/web-llvm/docs/api/files/lib/lib/passes/passbuilderbindings-cpp/#afd1501c49c84f3addfd108c2484f5674">PB</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Private Member Attributes

### Subtarget {#a1bf8c7f2a62797ec71655bf42ea65575}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">std::unique_ptr&lt;DirectXSubtarget&gt; llvm::DirectXTargetMachine::Subtarget</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 22 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/directx/directxtargetmachine-h">DirectXTargetMachine.h</a>.</p>

</div>
</div>

### TLOF {#a2602203f0086eed6350312f1e3484819}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">std::unique_ptr&lt;TargetLoweringObjectFile&gt; llvm::DirectXTargetMachine::TLOF</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 21 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/directx/directxtargetmachine-h">DirectXTargetMachine.h</a>.</p>

</div>
</div>

</div>

<hr/>

The documentation for this class was generated from the following files:

<ul>
<li><a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/directx/directxtargetmachine-cpp">DirectXTargetMachine.cpp</a></li>
<li><a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/directx/directxtargetmachine-h">DirectXTargetMachine.h</a></li>
</ul>

<hr/>

<p class="doxyGeneratedBy">Generated via <a href="https://github.com/xpack/doxygen2docusaurus">doxygen2docusaurus</a> by <a href="https://www.doxygen.nl">Doxygen</a> 1.15.0.</p>

</div>
