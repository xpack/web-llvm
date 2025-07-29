---

# DO NOT EDIT!
# Automatically generated via doxygen2docusaurus by Doxygen.

slug: /api/classes/anonymous-arctargetmachine-cpp-/arcpassconfig
custom_edit_url: null
toc_max_heading_level: 4
keywords:
  - doxygen
  - reference
  - class

---

<div class="doxyPage">

# `ARCPassConfig` Class

<p>ARC Code Generator <a href="/web-llvm/docs/api/classes/llvm/pass">Pass</a> Configuration Options. <a href="#details">More...</a></p>

## Declaration

<div class="doxyDeclaration">
class anonymous{ARCTargetMachine.cpp}::ARCPassConfig { ... }
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

## Public Constructors Index

<table class="doxyMembersIndex">

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a750e47d28588a4f75adc0763db4f62b9">ARCPassConfig</a> (ARCTargetMachine &amp;TM, PassManagerBase &amp;PM)</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/arctargetmachine">ARCTargetMachine</a> &amp;</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#abfbcc34c2343af8291863ab518a35ea2">getARCTargetMachine</a> () const</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a8f173da2371cbf3f84c04e9193f95fce">addIRPasses</a> () override</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Add common target configurable passes that perform LLVM IR to IR transforms following machine independent optimization. <a href="#a8f173da2371cbf3f84c04e9193f95fce">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">bool</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a93555eefc283fe51216d7ea6293cce0a">addInstSelector</a> () override</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>addInstSelector - This method should install an instruction selector pass, which converts from LLVM code to machine instructions. <a href="#a93555eefc283fe51216d7ea6293cce0a">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">void</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#acb7497f315f5543f55a19adf6ae2ab16">addPreEmitPass</a> () override</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>This pass may be implemented by targets that want to run passes immediately before machine code is emitted. <a href="#acb7497f315f5543f55a19adf6ae2ab16">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">void</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#aa26b83de5688206ac118784219718ccb">addPreRegAlloc</a> () override</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>This method may be implemented by targets that want to run passes immediately before register allocation. <a href="#aa26b83de5688206ac118784219718ccb">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

</table>

## Description {#details}

<p>ARC Code Generator <a href="/web-llvm/docs/api/classes/llvm/pass">Pass</a> Configuration Options.</p>

<p>Definition at line 52 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/arc/arctargetmachine-cpp">ARCTargetMachine.cpp</a>.</p>


<div class="doxySectionDef">

## Public Constructors

### ARCPassConfig() {#a750e47d28588a4f75adc0763db4f62b9}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">anonymous{ARCTargetMachine.cpp}::ARCPassConfig::ARCPassConfig (<a href="/web-llvm/docs/api/classes/llvm/arctargetmachine">ARCTargetMachine</a> &amp; TM, <a href="/web-llvm/docs/api/classes/llvm/legacy/passmanagerbase">PassManagerBase</a> &amp; PM)</td>
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



<p>Definition at line 54 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/arc/arctargetmachine-cpp">ARCTargetMachine.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/classes/llvm/targetpassconfig/#abfe879f7efa8851adee88ab786516d59">llvm::TargetPassConfig::TargetPassConfig</a> and <a href="/web-llvm/docs/api/classes/llvm/targetpassconfig/#a0e43f614336b22347dfdb6f20ea792df">llvm::TargetPassConfig::TM</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Public Member Functions

### addInstSelector() {#a93555eefc283fe51216d7ea6293cce0a}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool ARCPassConfig::addInstSelector ()</td>
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

<p>Definition at line 62 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/arc/arctargetmachine-cpp">ARCTargetMachine.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/classes/llvm/targetpassconfig/#ab2ca200281996a1a8bc064d21d4aa238">llvm::TargetPassConfig::addPass</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a882ca2f0083c5bbadf8d5234ab48dfa1">llvm::createARCISelDag</a>, <a href="#abfbcc34c2343af8291863ab518a35ea2">getARCTargetMachine</a> and <a href="/web-llvm/docs/api/classes/llvm/targetpassconfig/#a4c36a5c58e6e55c962d2d9bed0bb3ba7">llvm::TargetPassConfig::getOptLevel</a>.</p>

</div>
</div>

### addIRPasses() {#a8f173da2371cbf3f84c04e9193f95fce}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void ARCPassConfig::addIRPasses ()</td>
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

<p>Definition at line 61 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/arc/arctargetmachine-cpp">ARCTargetMachine.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/classes/llvm/targetpassconfig/#a835d2863dbd2cfd8c184a6a94923b61f">llvm::TargetPassConfig::addIRPasses</a>, <a href="/web-llvm/docs/api/classes/llvm/targetpassconfig/#ab2ca200281996a1a8bc064d21d4aa238">llvm::TargetPassConfig::addPass</a> and <a href="/web-llvm/docs/api/namespaces/llvm/#adebabb5e491a19ce4466a326d41641e0">llvm::createAtomicExpandLegacyPass</a>.</p>

</div>
</div>

### addPreEmitPass() {#acb7497f315f5543f55a19adf6ae2ab16}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void ARCPassConfig::addPreEmitPass ()</td>
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

<p>This pass may be implemented by targets that want to run passes immediately before machine code is emitted.</p>

<p>Definition at line 63 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/arc/arctargetmachine-cpp">ARCTargetMachine.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/classes/llvm/targetpassconfig/#ab2ca200281996a1a8bc064d21d4aa238">llvm::TargetPassConfig::addPass</a> and <a href="/web-llvm/docs/api/namespaces/llvm/#aeeacfdc039a11f914e30dc55484369ee">llvm::createARCBranchFinalizePass</a>.</p>

</div>
</div>

### addPreRegAlloc() {#aa26b83de5688206ac118784219718ccb}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void ARCPassConfig::addPreRegAlloc ()</td>
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

<p>This method may be implemented by targets that want to run passes immediately before register allocation.</p>

<p>Definition at line 64 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/arc/arctargetmachine-cpp">ARCTargetMachine.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/classes/llvm/targetpassconfig/#ab2ca200281996a1a8bc064d21d4aa238">llvm::TargetPassConfig::addPass</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a7f8b455b190c62aed83d55d714d29cba">llvm::createARCExpandPseudosPass</a> and <a href="/web-llvm/docs/api/namespaces/llvm/#ad8844189a4e464c7f70de1bf842c6680">llvm::createARCOptAddrMode</a>.</p>

</div>
</div>

### getARCTargetMachine() {#abfbcc34c2343af8291863ab518a35ea2}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">ARCTargetMachine &amp; anonymous{ARCTargetMachine.cpp}::ARCPassConfig::getARCTargetMachine ()</td>
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



<p>Definition at line 57 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/arc/arctargetmachine-cpp">ARCTargetMachine.cpp</a>.</p>


<p>Reference <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/simachinefunctioninfo-cpp/#a6c3673d61ea1313b5546587d80bdbe83">getTM</a>.</p>


<p>Referenced by <a href="#a93555eefc283fe51216d7ea6293cce0a">addInstSelector</a>.</p>

</div>
</div>

</div>

<hr/>

The documentation for this class was generated from the following file:

<ul>
<li><a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/arc/arctargetmachine-cpp">ARCTargetMachine.cpp</a></li>
</ul>

<hr/>

<p class="doxyGeneratedBy">Generated via <a href="https://github.com/xpack/doxygen2docusaurus">doxygen2docusaurus</a> by <a href="https://www.doxygen.nl">Doxygen</a> 1.15.0.</p>

</div>
