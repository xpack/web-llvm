---

# DO NOT EDIT!
# Automatically generated via doxygen2docusaurus by Doxygen.

slug: /api/classes/llvm/msp430targetmachine
custom_edit_url: null
toc_max_heading_level: 4
keywords:
  - doxygen
  - reference
  - class

---

<div class="doxyPage">

# `MSP430TargetMachine` Class

<p><a href="/web-llvm/docs/api/classes/llvm/msp430targetmachine">MSP430TargetMachine</a>. <a href="#details">More...</a></p>

## Declaration

<div class="doxyDeclaration">
class llvm::MSP430TargetMachine { ... }
</div>

## Included Headers

<div class="doxyIncludesList">#include "<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/msp430/msp430targetmachine-h">Target/MSP430/MSP430TargetMachine.h</a>"
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a204cc56ded2a0d2743a71edbb2329524">MSP430TargetMachine</a> (const Target &amp;T, const Triple &amp;TT, StringRef CPU, StringRef FS, const TargetOptions &amp;Options, std::optional&lt; Reloc::Model &gt; RM, std::optional&lt; CodeModel::Model &gt; CM, CodeGenOptLevel OL, bool JIT)</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a6252701145bb904f1ff53028fde4ed84">~MSP430TargetMachine</a> () override</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/msp430subtarget">MSP430Subtarget</a> *</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a9a71e7c672a08247e2c9c269c1657105">getSubtargetImpl</a> (const Function &amp;F) const override</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Virtual method implemented by subclasses that returns a reference to that target's TargetSubtargetInfo-derived member variable. <a href="#a9a71e7c672a08247e2c9c269c1657105">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/targetpassconfig">TargetPassConfig</a> *</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#abf71a066eeb606a9d85b3e2462b89d60">createPassConfig</a> (PassManagerBase &amp;PM) override</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Create a pass configuration object to be used by addPassToEmitX methods for generating a pipeline of CodeGen passes. <a href="#abf71a066eeb606a9d85b3e2462b89d60">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/targetloweringobjectfile">TargetLoweringObjectFile</a> *</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#aa0beb5d45298a45d3694d77b4d9e18c0">getObjFileLowering</a> () const override</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a609559c827653fea39c974cf328f0a35">createMachineFunctionInfo</a> (BumpPtrAllocator &amp;Allocator, const Function &amp;F, const TargetSubtargetInfo *STI) const override</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Create the target's instance of <a href="/web-llvm/docs/api/structs/llvm/machinefunctioninfo">MachineFunctionInfo</a>. <a href="#a609559c827653fea39c974cf328f0a35">More...</a></p>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#acf45787154bd62a170e1ceba8bc1c8dd">TLOF</a></td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/msp430subtarget">MSP430Subtarget</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a5926e9de31a065b1e43b010a83cbc378">Subtarget</a></td>
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

<p><a href="/web-llvm/docs/api/classes/llvm/msp430targetmachine">MSP430TargetMachine</a>.</p>

<p>Definition at line 26 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/msp430/msp430targetmachine-h">MSP430TargetMachine.h</a>.</p>


<div class="doxySectionDef">

## Public Constructors

### MSP430TargetMachine() {#a204cc56ded2a0d2743a71edbb2329524}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">MSP430TargetMachine::MSP430TargetMachine (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/target">Target</a> &amp; T, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/triple">Triple</a> &amp; TT, <a href="/web-llvm/docs/api/classes/llvm/stringref">StringRef</a> CPU, <a href="/web-llvm/docs/api/classes/llvm/stringref">StringRef</a> FS, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/targetoptions">TargetOptions</a> &amp; Options, std::optional&lt; <a href="/web-llvm/docs/api/namespaces/llvm/reloc/#af59f6dc86e80aaf56f1afd155eebf568">Reloc::Model</a> &gt; RM, std::optional&lt; <a href="/web-llvm/docs/api/namespaces/llvm/codemodel/#afc59396a9e5809fc92938e203d91a8df">CodeModel::Model</a> &gt; CM, <a href="/web-llvm/docs/api/namespaces/llvm/#a8ec1bf8d7b792ca9fac56f8514db18d2">CodeGenOptLevel</a> OL, bool JIT)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Declaration at line 31 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/msp430/msp430targetmachine-h">MSP430TargetMachine.h</a>, definition at line 40 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/msp430/msp430targetmachine-cpp">MSP430TargetMachine.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/classes/llvm/codegentargetmachineimpl/#a4480a9aa1ec7c3115acc998e187f5ab3">llvm::CodeGenTargetMachineImpl::CodeGenTargetMachineImpl</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64targetmachine-cpp/#a003a58caf135efbf7273c5ed84e700d7">computeDataLayout</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a6849e9de7afb5b350a241595d9ed1911">llvm::getEffectiveCodeModel</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a63737748f52c9cdcd469b63a01cc454a">llvm::getEffectiveRelocModel</a>, <a href="/web-llvm/docs/api/classes/llvm/codegentargetmachineimpl/#a85849733e753fbf08f1c487b153c754b">llvm::CodeGenTargetMachineImpl::initAsmInfo</a>, <a href="/web-llvm/docs/api/classes/llvm/targetmachine/#ab1fb67187fc37e569cc5171cbebba873">llvm::TargetMachine::Options</a>, <a href="/web-llvm/docs/api/classes/llvm/targetmachine/#a588867fa922c392886b07e0ad42038b4">llvm::TargetMachine::RM</a> and <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/mips/mips16isellowering-cpp/#a0acb682b8260ab1c60b918599864e2e5">T</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Public Destructor

### \~MSP430TargetMachine() {#a6252701145bb904f1ff53028fde4ed84}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">MSP430TargetMachine::~MSP430TargetMachine ()</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 36 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/msp430/msp430targetmachine-h">MSP430TargetMachine.h</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Public Member Functions

### createMachineFunctionInfo() {#a609559c827653fea39c974cf328f0a35}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">MachineFunctionInfo * MSP430TargetMachine::createMachineFunctionInfo (<a href="/web-llvm/docs/api/namespaces/llvm/#a8e612822d4ba7bb36c9c79582a567108">BumpPtrAllocator</a> &amp; Allocator, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/function">Function</a> &amp; F, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/targetsubtargetinfo">TargetSubtargetInfo</a> * STI)</td>
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

<p>Declaration at line 48 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/msp430/msp430targetmachine-h">MSP430TargetMachine.h</a>, definition at line 77 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/msp430/msp430targetmachine-cpp">MSP430TargetMachine.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/structs/llvm/machinefunctioninfo/#a06ad8b2e5a8e3c0f81f05c7870fb3b23">llvm::MachineFunctionInfo::create</a>, <a href="/web-llvm/docs/api/files/lib/lib/support/md5-cpp/#a96d73bbd7af15cb1fc38c3f4a3bd82e9">F</a> and <a href="/web-llvm/docs/api/classes/llvm/targetmachine/#aaebd1c0e5f028848cc0e548bf015aaf1">llvm::TargetMachine::STI</a>.</p>

</div>
</div>

### createPassConfig() {#abf71a066eeb606a9d85b3e2462b89d60}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">TargetPassConfig * MSP430TargetMachine::createPassConfig (<a href="/web-llvm/docs/api/classes/llvm/legacy/passmanagerbase">PassManagerBase</a> &amp; PM)</td>
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


<p>Declaration at line 41 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/msp430/msp430targetmachine-h">MSP430TargetMachine.h</a>, definition at line 73 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/msp430/msp430targetmachine-cpp">MSP430TargetMachine.cpp</a>.</p>

</div>
</div>

### getObjFileLowering() {#aa0beb5d45298a45d3694d77b4d9e18c0}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">TargetLoweringObjectFile * llvm::MSP430TargetMachine::getObjFileLowering ()</td>
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



<p>Definition at line 43 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/msp430/msp430targetmachine-h">MSP430TargetMachine.h</a>.</p>

</div>
</div>

### getSubtargetImpl() {#a9a71e7c672a08247e2c9c269c1657105}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">const MSP430Subtarget * llvm::MSP430TargetMachine::getSubtargetImpl (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/function">Function</a> &amp;)</td>
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

<p>Virtual method implemented by subclasses that returns a reference to that target's TargetSubtargetInfo-derived member variable.</p>

<p>Definition at line 38 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/msp430/msp430targetmachine-h">MSP430TargetMachine.h</a>.</p>


<p>Reference <a href="/web-llvm/docs/api/files/lib/lib/support/md5-cpp/#a96d73bbd7af15cb1fc38c3f4a3bd82e9">F</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Private Member Attributes

### Subtarget {#a5926e9de31a065b1e43b010a83cbc378}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">MSP430Subtarget llvm::MSP430TargetMachine::Subtarget</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 28 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/msp430/msp430targetmachine-h">MSP430TargetMachine.h</a>.</p>

</div>
</div>

### TLOF {#acf45787154bd62a170e1ceba8bc1c8dd}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">std::unique_ptr&lt;TargetLoweringObjectFile&gt; llvm::MSP430TargetMachine::TLOF</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 27 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/msp430/msp430targetmachine-h">MSP430TargetMachine.h</a>.</p>

</div>
</div>

</div>

<hr/>

The documentation for this class was generated from the following files:

<ul>
<li><a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/msp430/msp430targetmachine-cpp">MSP430TargetMachine.cpp</a></li>
<li><a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/msp430/msp430targetmachine-h">MSP430TargetMachine.h</a></li>
</ul>

<hr/>

<p class="doxyGeneratedBy">Generated via <a href="https://github.com/xpack/doxygen2docusaurus">doxygen2docusaurus</a> by <a href="https://www.doxygen.nl">Doxygen</a> 1.15.0.</p>

</div>
