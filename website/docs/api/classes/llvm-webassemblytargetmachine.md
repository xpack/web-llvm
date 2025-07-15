---

# DO NOT EDIT!
# Automatically generated via doxygen2docusaurus by Doxygen.

slug: /api/classes/llvm/webassemblytargetmachine
custom_edit_url: null
toc_max_heading_level: 4
keywords:
  - doxygen
  - reference
  - class

---

<div class="doxyPage">

# The `WebAssemblyTargetMachine` Class Reference



## Declaration

<div class="doxyDeclaration">
class llvm::WebAssemblyTargetMachine { ... }
</div>

## Included Headers

<div class="doxyIncludesList">#include "<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/webassembly/webassemblytargetmachine-h">Target/WebAssembly/WebAssemblyTargetMachine.h</a>"
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a39f4b4edb8abb1954310e3b6915afc81">WebAssemblyTargetMachine</a> (const Target &amp;T, const Triple &amp;TT, StringRef CPU, StringRef FS, const TargetOptions &amp;Options, std::optional&lt; Reloc::Model &gt; RM, std::optional&lt; CodeModel::Model &gt; CM, CodeGenOptLevel OL, bool JIT)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Create an <a href="/web-llvm/docs/api/namespaces/llvm/webassembly">WebAssembly</a> architecture model. <a href="#a39f4b4edb8abb1954310e3b6915afc81">More...</a></p>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a93070052836fb225c17940ec8b370417">~WebAssemblyTargetMachine</a> () override</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/webassemblysubtarget">WebAssemblySubtarget</a> *</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a719713d67ba4d30b964d4a4f3228e157">getSubtargetImpl</a> () const</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/webassemblysubtarget">WebAssemblySubtarget</a> *</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a4e77be6f302bb2cc258a5f5ee0a8fd44">getSubtargetImpl</a> (std::string CPU, std::string FS) const</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/webassemblysubtarget">WebAssemblySubtarget</a> *</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ac5c975b4faf36ed756851c7a84d870ea">getSubtargetImpl</a> (const Function &amp;F) const override</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Virtual method implemented by subclasses that returns a reference to that target's TargetSubtargetInfo-derived member variable. <a href="#ac5c975b4faf36ed756851c7a84d870ea">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/targetpassconfig">TargetPassConfig</a> *</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a4740e3f15f0d96477caddde4b1b199ae">createPassConfig</a> (PassManagerBase &amp;PM) override</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Create a pass configuration object to be used by addPassToEmitX methods for generating a pipeline of CodeGen passes. <a href="#a4740e3f15f0d96477caddde4b1b199ae">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/targetloweringobjectfile">TargetLoweringObjectFile</a> *</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a642097b192708731c3e907ac59c1a874">getObjFileLowering</a> () const override</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a82e19c7266681b3283fe1ce9ec23e180">createMachineFunctionInfo</a> (BumpPtrAllocator &amp;Allocator, const Function &amp;F, const TargetSubtargetInfo *STI) const override</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Create the target's instance of <a href="/web-llvm/docs/api/structs/llvm/machinefunctioninfo">MachineFunctionInfo</a>. <a href="#a82e19c7266681b3283fe1ce9ec23e180">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/targettransforminfo">TargetTransformInfo</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a9bf333c6c83111588f567e7f191dc984">getTargetTransformInfo</a> (const Function &amp;F) const override</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Get a <a href="/web-llvm/docs/api/classes/llvm/targettransforminfo">TargetTransformInfo</a> implementation for the target. <a href="#a9bf333c6c83111588f567e7f191dc984">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">bool</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a701dee57c09638d9b213b905d2269d4d">usesPhysRegsForValues</a> () const override</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>True if the target uses physical regs (as nearly all targets do). <a href="#a701dee57c09638d9b213b905d2269d4d">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/structs/llvm/yaml/machinefunctioninfo">yaml::MachineFunctionInfo</a> *</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a0195626aaa892d3e13e560237694ab6e">createDefaultFuncInfoYAML</a> () const override</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Allocate and return a default initialized instance of the YAML representation for the <a href="/web-llvm/docs/api/structs/llvm/machinefunctioninfo">MachineFunctionInfo</a>. <a href="#a0195626aaa892d3e13e560237694ab6e">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/structs/llvm/yaml/machinefunctioninfo">yaml::MachineFunctionInfo</a> *</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#aad505019362a8cf081bda4ca50f0092d">convertFuncInfoToYAML</a> (const MachineFunction &amp;MF) const override</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Allocate and initialize an instance of the YAML representation of the <a href="/web-llvm/docs/api/structs/llvm/machinefunctioninfo">MachineFunctionInfo</a>. <a href="#aad505019362a8cf081bda4ca50f0092d">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">bool</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a1f105b1ab02dcb52f17181b399c004f2">parseMachineFunctionInfo</a> (const yaml::MachineFunctionInfo &amp;, PerFunctionMIParsingState &amp;PFS, SMDiagnostic &amp;Error, SMRange &amp;SourceRange) const override</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Parse out the target's <a href="/web-llvm/docs/api/structs/llvm/machinefunctioninfo">MachineFunctionInfo</a> from the YAML reprsentation. <a href="#a1f105b1ab02dcb52f17181b399c004f2">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">bool</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ad253efc6f21958ec5f33165bae10be24">usesMultivalueABI</a> () const</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">std::unique_ptr&lt; <a href="/web-llvm/docs/api/classes/llvm/targetloweringobjectfile">TargetLoweringObjectFile</a> &gt;</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ade6ed0dcd6e80adab9fb7e7f5d21fece">TLOF</a></td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/stringmap">StringMap</a>&lt; std::unique_ptr&lt; <a href="/web-llvm/docs/api/classes/llvm/webassemblysubtarget">WebAssemblySubtarget</a> &gt; &gt;</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#acaa6e41a65d6a7aa5854840d6c411e90">SubtargetMap</a></td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ad8a7255f92dbfbd1fd2bd069661efd1f">UsesMultivalueABI</a> = false</td>
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


<p>Definition at line 24 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/webassembly/webassemblytargetmachine-h">WebAssemblyTargetMachine.h</a>.</p>


<div class="doxySectionDef">

## Public Constructors

### WebAssemblyTargetMachine() {#a39f4b4edb8abb1954310e3b6915afc81}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">WebAssemblyTargetMachine::WebAssemblyTargetMachine (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/target">Target</a> &amp; T, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/triple">Triple</a> &amp; TT, <a href="/web-llvm/docs/api/classes/llvm/stringref">StringRef</a> CPU, <a href="/web-llvm/docs/api/classes/llvm/stringref">StringRef</a> FS, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/targetoptions">TargetOptions</a> &amp; Options, std::optional&lt; <a href="/web-llvm/docs/api/namespaces/llvm/reloc/#af59f6dc86e80aaf56f1afd155eebf568">Reloc::Model</a> &gt; RM, std::optional&lt; <a href="/web-llvm/docs/api/namespaces/llvm/codemodel/#afc59396a9e5809fc92938e203d91a8df">CodeModel::Model</a> &gt; CM, <a href="/web-llvm/docs/api/namespaces/llvm/#a8ec1bf8d7b792ca9fac56f8514db18d2">CodeGenOptLevel</a> OL, bool JIT)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Create an <a href="/web-llvm/docs/api/namespaces/llvm/webassembly">WebAssembly</a> architecture model.</p>

<p>Declaration at line 30 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/webassembly/webassemblytargetmachine-h">WebAssemblyTargetMachine.h</a>, definition at line 113 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/webassembly/webassemblytargetmachine-cpp">WebAssemblyTargetMachine.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/classes/llvm/codegentargetmachineimpl/#a4480a9aa1ec7c3115acc998e187f5ab3">llvm::CodeGenTargetMachineImpl::CodeGenTargetMachineImpl</a>, <a href="/web-llvm/docs/api/classes/llvm/targetoptions/#ad0c7f9f16d88de8a481dd162ead65c7f">llvm::TargetOptions::DataSections</a>, <a href="/web-llvm/docs/api/classes/llvm/targetoptions/#abb646e2505e21a891497f665187963b3">llvm::TargetOptions::FunctionSections</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a6849e9de7afb5b350a241595d9ed1911">llvm::getEffectiveCodeModel</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a63737748f52c9cdcd469b63a01cc454a">llvm::getEffectiveRelocModel</a>, <a href="/web-llvm/docs/api/classes/llvm/codegentargetmachineimpl/#a85849733e753fbf08f1c487b153c754b">llvm::CodeGenTargetMachineImpl::initAsmInfo</a>, <a href="/web-llvm/docs/api/classes/llvm/targetoptions/#acd83fce25de1ac9f6c975135a8235c22">llvm::TargetOptions::NoTrapAfterNoreturn</a>, <a href="/web-llvm/docs/api/classes/llvm/targetmachine/#ab1fb67187fc37e569cc5171cbebba873">llvm::TargetMachine::Options</a>, <a href="/web-llvm/docs/api/classes/llvm/targetmachine/#a588867fa922c392886b07e0ad42038b4">llvm::TargetMachine::RM</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/mips/mips16isellowering-cpp/#a0acb682b8260ab1c60b918599864e2e5">T</a>, <a href="/web-llvm/docs/api/classes/llvm/targetoptions/#ae511cb5018c52294bcff10ccde3f6789">llvm::TargetOptions::TrapUnreachable</a> and <a href="/web-llvm/docs/api/classes/llvm/targetoptions/#aaeee4d390f75162b6cf22adb0f1fbb78">llvm::TargetOptions::UniqueSectionNames</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Public Destructor

### \~WebAssemblyTargetMachine() {#a93070052836fb225c17940ec8b370417}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">WebAssemblyTargetMachine::~WebAssemblyTargetMachine ()</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 36 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/webassembly/webassemblytargetmachine-h">WebAssemblyTargetMachine.h</a>.</p>


<p>Reference <a href="/web-llvm/docs/api/files/lib/lib/support/md5-cpp/#a96d73bbd7af15cb1fc38c3f4a3bd82e9">F</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Public Member Functions

### convertFuncInfoToYAML() {#aad505019362a8cf081bda4ca50f0092d}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">yaml::MachineFunctionInfo * WebAssemblyTargetMachine::convertFuncInfoToYAML (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/machinefunction">MachineFunction</a> &amp; MF)</td>
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

<p>Declaration at line 61 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/webassembly/webassemblytargetmachine-h">WebAssemblyTargetMachine.h</a>, definition at line 657 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/webassembly/webassemblytargetmachine-cpp">WebAssemblyTargetMachine.cpp</a>.</p>


<p>Reference <a href="/web-llvm/docs/api/classes/llvm/machinefunction/#ab7feae1932b436c8630e247166ec42b7">llvm::MachineFunction::getInfo</a>.</p>

</div>
</div>

### createDefaultFuncInfoYAML() {#a0195626aaa892d3e13e560237694ab6e}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">yaml::MachineFunctionInfo * WebAssemblyTargetMachine::createDefaultFuncInfoYAML ()</td>
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

<p>Declaration at line 59 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/webassembly/webassemblytargetmachine-h">WebAssemblyTargetMachine.h</a>, definition at line 653 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/webassembly/webassemblytargetmachine-cpp">WebAssemblyTargetMachine.cpp</a>.</p>

</div>
</div>

### createMachineFunctionInfo() {#a82e19c7266681b3283fe1ce9ec23e180}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">MachineFunctionInfo * WebAssemblyTargetMachine::createMachineFunctionInfo (<a href="/web-llvm/docs/api/namespaces/llvm/#a8e612822d4ba7bb36c9c79582a567108">BumpPtrAllocator</a> &amp; Allocator, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/function">Function</a> &amp; F, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/targetsubtargetinfo">TargetSubtargetInfo</a> * STI)</td>
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

<p>Declaration at line 52 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/webassembly/webassemblytargetmachine-h">WebAssemblyTargetMachine.h</a>, definition at line 379 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/webassembly/webassemblytargetmachine-cpp">WebAssemblyTargetMachine.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/structs/llvm/machinefunctioninfo/#a06ad8b2e5a8e3c0f81f05c7870fb3b23">llvm::MachineFunctionInfo::create</a>, <a href="/web-llvm/docs/api/files/lib/lib/support/md5-cpp/#a96d73bbd7af15cb1fc38c3f4a3bd82e9">F</a> and <a href="/web-llvm/docs/api/classes/llvm/targetmachine/#aaebd1c0e5f028848cc0e548bf015aaf1">llvm::TargetMachine::STI</a>.</p>

</div>
</div>

### createPassConfig() {#a4740e3f15f0d96477caddde4b1b199ae}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">TargetPassConfig * WebAssemblyTargetMachine::createPassConfig (<a href="/web-llvm/docs/api/classes/llvm/legacy/passmanagerbase">PassManagerBase</a> &amp; PM)</td>
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


<p>Declaration at line 45 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/webassembly/webassemblytargetmachine-h">WebAssemblyTargetMachine.h</a>, definition at line 392 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/webassembly/webassemblytargetmachine-cpp">WebAssemblyTargetMachine.cpp</a>.</p>

</div>
</div>

### getObjFileLowering() {#a642097b192708731c3e907ac59c1a874}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">TargetLoweringObjectFile * llvm::WebAssemblyTargetMachine::getObjFileLowering ()</td>
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



<p>Definition at line 47 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/webassembly/webassemblytargetmachine-h">WebAssemblyTargetMachine.h</a>.</p>

</div>
</div>

### getSubtargetImpl() {#a719713d67ba4d30b964d4a4f3228e157}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">const WebAssemblySubtarget * WebAssemblyTargetMachine::getSubtargetImpl ()</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Declaration at line 38 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/webassembly/webassemblytargetmachine-h">WebAssemblyTargetMachine.h</a>, definition at line 157 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/webassembly/webassemblytargetmachine-cpp">WebAssemblyTargetMachine.cpp</a>.</p>


<p>References <a href="#a719713d67ba4d30b964d4a4f3228e157">getSubtargetImpl</a>, <a href="/web-llvm/docs/api/classes/llvm/targetmachine/#a8d4930d9bba5bf85a86c2177b950c10f">llvm::TargetMachine::getTargetCPU</a> and <a href="/web-llvm/docs/api/classes/llvm/targetmachine/#a81b02eb89292775ff6e6a2ece94f961f">llvm::TargetMachine::getTargetFeatureString</a>.</p>


<p>Referenced by <a href="#a719713d67ba4d30b964d4a4f3228e157">getSubtargetImpl</a> and <a href="#ac5c975b4faf36ed756851c7a84d870ea">getSubtargetImpl</a>.</p>

</div>
</div>

### getSubtargetImpl() {#a4e77be6f302bb2cc258a5f5ee0a8fd44}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">const WebAssemblySubtarget * WebAssemblyTargetMachine::getSubtargetImpl (std::string CPU, std::string FS)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Declaration at line 39 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/webassembly/webassemblytargetmachine-h">WebAssemblyTargetMachine.h</a>, definition at line 163 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/webassembly/webassemblytargetmachine-cpp">WebAssemblyTargetMachine.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/files/lib/lib/support/md5-cpp/#ac0eafdc9ee161b71e7af98af736952fd">I</a> and <a href="/web-llvm/docs/api/classes/llvm/targetmachine/#a05856d96e88224279af8b29edfd1c9ad">llvm::TargetMachine::TargetTriple</a>.</p>

</div>
</div>

### getSubtargetImpl() {#ac5c975b4faf36ed756851c7a84d870ea}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">const WebAssemblySubtarget * WebAssemblyTargetMachine::getSubtargetImpl (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/function">Function</a> &amp;)</td>
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

<p>Declaration at line 42 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/webassembly/webassemblytargetmachine-h">WebAssemblyTargetMachine.h</a>, definition at line 173 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/webassembly/webassemblytargetmachine-cpp">WebAssemblyTargetMachine.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/files/lib/lib/support/md5-cpp/#a96d73bbd7af15cb1fc38c3f4a3bd82e9">F</a>, <a href="#a719713d67ba4d30b964d4a4f3228e157">getSubtargetImpl</a>, <a href="/web-llvm/docs/api/classes/llvm/attribute/#a968930aea9d9efa8d46dd890fce75643">llvm::Attribute::getValueAsString</a>, <a href="/web-llvm/docs/api/classes/llvm/attribute/#adf4d22686e85732b2fef71e3c45531c6">llvm::Attribute::isValid</a>, <a href="/web-llvm/docs/api/classes/llvm/targetmachine/#af0a50afebb9bed07d36be2bac4c6f729">llvm::TargetMachine::resetTargetOptions</a>, <a href="/web-llvm/docs/api/classes/llvm/stringref/#a223dd14e7d12bc5cea01889b972a98b2">llvm::StringRef::str</a>, <a href="/web-llvm/docs/api/classes/llvm/targetmachine/#a9ca45577ddb8efe4904398939fae28d1">llvm::TargetMachine::TargetCPU</a> and <a href="/web-llvm/docs/api/classes/llvm/targetmachine/#a795cc09ce82b6ef057e5400a5cee7d68">llvm::TargetMachine::TargetFS</a>.</p>

</div>
</div>

### getTargetTransformInfo() {#a9bf333c6c83111588f567e7f191dc984}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">TargetTransformInfo WebAssemblyTargetMachine::getTargetTransformInfo (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/function">Function</a> &amp; F)</td>
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


<p>Declaration at line 55 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/webassembly/webassemblytargetmachine-h">WebAssemblyTargetMachine.h</a>, definition at line 387 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/webassembly/webassemblytargetmachine-cpp">WebAssemblyTargetMachine.cpp</a>.</p>


<p>Reference <a href="/web-llvm/docs/api/files/lib/lib/support/md5-cpp/#a96d73bbd7af15cb1fc38c3f4a3bd82e9">F</a>.</p>

</div>
</div>

### parseMachineFunctionInfo() {#a1f105b1ab02dcb52f17181b399c004f2}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool WebAssemblyTargetMachine::parseMachineFunctionInfo (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/structs/llvm/yaml/machinefunctioninfo">yaml::MachineFunctionInfo</a> &amp;, <a href="/web-llvm/docs/api/structs/llvm/perfunctionmiparsingstate">PerFunctionMIParsingState</a> &amp; PFS, <a href="/web-llvm/docs/api/classes/llvm/smdiagnostic">SMDiagnostic</a> &amp; Error, <a href="/web-llvm/docs/api/classes/llvm/smrange">SMRange</a> &amp; SourceRange)</td>
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

<p>Declaration at line 62 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/webassembly/webassemblytargetmachine-h">WebAssemblyTargetMachine.h</a>, definition at line 663 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/webassembly/webassemblytargetmachine-cpp">WebAssemblyTargetMachine.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/classes/llvm/machinefunction/#ab7feae1932b436c8630e247166ec42b7">llvm::MachineFunction::getInfo</a> and <a href="/web-llvm/docs/api/structs/llvm/perfunctionmiparsingstate/#ae7f8c6f160583712d2adaafb4cca24fe">llvm::PerFunctionMIParsingState::MF</a>.</p>

</div>
</div>

### usesMultivalueABI() {#ad253efc6f21958ec5f33165bae10be24}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool llvm::WebAssemblyTargetMachine::usesMultivalueABI ()</td>
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



<p>Definition at line 67 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/webassembly/webassemblytargetmachine-h">WebAssemblyTargetMachine.h</a>.</p>

</div>
</div>

### usesPhysRegsForValues() {#a701dee57c09638d9b213b905d2269d4d}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool llvm::WebAssemblyTargetMachine::usesPhysRegsForValues ()</td>
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

<p>True if the target uses physical regs (as nearly all targets do).</p>


<p>False for stack machines such as <a href="/web-llvm/docs/api/namespaces/llvm/webassembly">WebAssembly</a> and other virtual-register machines. If true, all vregs must be allocated before PEI. If false, then callee-save register spilling and scavenging are not needed or used. If false, implicitly defined registers will still be assumed to be physical registers, except that variadic defs will be allocated vregs.</p>


<p>Definition at line 57 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/webassembly/webassemblytargetmachine-h">WebAssemblyTargetMachine.h</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Private Member Attributes

### SubtargetMap {#acaa6e41a65d6a7aa5854840d6c411e90}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">StringMap&lt;std::unique_ptr&lt;WebAssemblySubtarget&gt; &gt; llvm::WebAssemblyTargetMachine::SubtargetMap</td>
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



<p>Definition at line 26 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/webassembly/webassemblytargetmachine-h">WebAssemblyTargetMachine.h</a>.</p>

</div>
</div>

### TLOF {#ade6ed0dcd6e80adab9fb7e7f5d21fece}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">std::unique_ptr&lt;TargetLoweringObjectFile&gt; llvm::WebAssemblyTargetMachine::TLOF</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 25 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/webassembly/webassemblytargetmachine-h">WebAssemblyTargetMachine.h</a>.</p>

</div>
</div>

### UsesMultivalueABI {#ad8a7255f92dbfbd1fd2bd069661efd1f}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool llvm::WebAssemblyTargetMachine::UsesMultivalueABI = false</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 27 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/webassembly/webassemblytargetmachine-h">WebAssemblyTargetMachine.h</a>.</p>

</div>
</div>

</div>

<hr/>

The documentation for this class was generated from the following files:

<ul>
<li><a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/webassembly/webassemblytargetmachine-cpp">WebAssemblyTargetMachine.cpp</a></li>
<li><a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/webassembly/webassemblytargetmachine-h">WebAssemblyTargetMachine.h</a></li>
</ul>

<hr/>

<p class="doxyGeneratedBy">Generated via <a href="https://github.com/xpack/doxygen2docusaurus">doxygen2docusaurus</a> by <a href="https://www.doxygen.nl">Doxygen</a> 1.14.0.</p>

</div>
