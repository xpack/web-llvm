---

# DO NOT EDIT!
# Automatically generated via doxygen2docusaurus by Doxygen.

slug: /api/structs/llvm/gcnregpressureprinter
custom_edit_url: null
toc_max_heading_level: 4
keywords:
  - doxygen
  - reference
  - struct

---

<div class="doxyPage">

# The `GCNRegPressurePrinter` Struct Reference



## Declaration

<div class="doxyDeclaration">
struct llvm::GCNRegPressurePrinter { ... }
</div>

## Included Headers

<div class="doxyIncludesList">#include "<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/gcnregpressure-h">Target/AMDGPU/GCNRegPressure.h</a>"
</div>

## Base struct

<table class="doxyMembersIndex">

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">class</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/machinefunctionpass">MachineFunctionPass</a></td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p><a href="/web-llvm/docs/api/classes/llvm/machinefunctionpass">MachineFunctionPass</a> - This class adapts the <a href="/web-llvm/docs/api/classes/llvm/functionpass">FunctionPass</a> interface to allow convenient creation of passes that operate on the <a href="/web-llvm/docs/api/classes/llvm/machinefunction">MachineFunction</a> representation. <a href="/web-llvm/docs/api/classes/llvm/machinefunctionpass/#details">More...</a></p>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#aea81b74630f80ed0fee7748a9beb0992">GCNRegPressurePrinter</a> ()</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a28746f937314058fd6bfee7784530996">runOnMachineFunction</a> (MachineFunction &amp;MF) override</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>runOnMachineFunction - This method must be overloaded to perform the desired machine code transformation or analysis. <a href="#a28746f937314058fd6bfee7784530996">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">void</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a09fac16a8dbd49b56f447fb67c25a7f6">getAnalysisUsage</a> (AnalysisUsage &amp;AU) const override</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>getAnalysisUsage - This function should be overriden by passes that need analysis information to do their job. <a href="#a09fac16a8dbd49b56f447fb67c25a7f6">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

</table>

## Public Static Attributes Index

<table class="doxyMembersIndex">

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">static char</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a4c78216508c874805cf765901f442c3c">ID</a> = 0</td>
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


<p>Definition at line 407 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/gcnregpressure-h">GCNRegPressure.h</a>.</p>


<div class="doxySectionDef">

## Public Constructors

### GCNRegPressurePrinter() {#aea81b74630f80ed0fee7748a9beb0992}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">llvm::GCNRegPressurePrinter::GCNRegPressurePrinter ()</td>
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



<p>Definition at line 411 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/gcnregpressure-h">GCNRegPressure.h</a>.</p>


<p>References <a href="#a4c78216508c874805cf765901f442c3c">ID</a> and <a href="/web-llvm/docs/api/classes/llvm/machinefunctionpass/#a29c81d2386f4a727c6d33413807530c8">llvm::MachineFunctionPass::MachineFunctionPass</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Public Member Functions

### getAnalysisUsage() {#a09fac16a8dbd49b56f447fb67c25a7f6}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void llvm::GCNRegPressurePrinter::getAnalysisUsage (<a href="/web-llvm/docs/api/classes/llvm/analysisusage">AnalysisUsage</a> &amp;)</td>
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

<p>getAnalysisUsage - This function should be overriden by passes that need analysis information to do their job.</p>


<p>If a pass specifies that it uses a particular analysis result to this function, it can then use the <a href="/web-llvm/docs/api/classes/llvm/pass/#a4863e5e463fb79955269fbf7fbf52b80">getAnalysis&lt;AnalysisType&gt;()</a> function, below.</p>


<p>Definition at line 415 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/gcnregpressure-h">GCNRegPressure.h</a>.</p>


<p>References <a href="/web-llvm/docs/api/classes/llvm/analysisusage/#ae0adcccca08fb686c9ce00f9397b660c">llvm::AnalysisUsage::addRequired</a>, <a href="/web-llvm/docs/api/classes/llvm/machinefunctionpass/#a864fd57b4304ef933b3281d0ef85a88e">llvm::MachineFunctionPass::getAnalysisUsage</a> and <a href="/web-llvm/docs/api/classes/llvm/analysisusage/#af22b06a6a4f9df80454071685a0d6a02">llvm::AnalysisUsage::setPreservesAll</a>.</p>

</div>
</div>

### runOnMachineFunction() {#a28746f937314058fd6bfee7784530996}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool GCNRegPressurePrinter::runOnMachineFunction (<a href="/web-llvm/docs/api/classes/llvm/machinefunction">MachineFunction</a> &amp; MF)</td>
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

<p>runOnMachineFunction - This method must be overloaded to perform the desired machine code transformation or analysis.</p>

<p>Declaration at line 413 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/gcnregpressure-h">GCNRegPressure.h</a>, definition at line 792 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/gcnregpressure-cpp">GCNRegPressure.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/classes/llvm/gcndownwardrptracker/#a222d514d23098e92ecbd53e36b3c5084">llvm::GCNDownwardRPTracker::advanceBeforeNext</a>, <a href="/web-llvm/docs/api/classes/llvm/gcndownwardrptracker/#adda01c47a26407d9bf35e27efc904136">llvm::GCNDownwardRPTracker::advanceToNext</a>, <a href="/web-llvm/docs/api/structs/llvm/lanebitmask/#a72988cca7ab2262ef68fdd0c5ae54940">llvm::LaneBitmask::any</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a7c46c742c31be54870e2038048e6b391">llvm::dbgs</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a939bc2108d47080767f0c06ba56caec7">llvm::format</a>, <a href="/web-llvm/docs/api/classes/llvm/pass/#a4863e5e463fb79955269fbf7fbf52b80">llvm::Pass::getAnalysis</a>, <a href="/web-llvm/docs/api/classes/llvm/gcnrptracker/#a14f66c7653ea1f0ac33bfcf4006aef57">llvm::GCNRPTracker::getLiveRegs</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a62ab92d2e2752422a6a0995188d64b77">llvm::getLiveRegs</a>, <a href="/web-llvm/docs/api/classes/llvm/gcnupwardrptracker/#aa8aa539949578dbd4e8abca2b4732cdd">llvm::GCNUpwardRPTracker::getMaxPressure</a>, <a href="/web-llvm/docs/api/classes/llvm/slotindexes/#a662867d9274595cdac0092afa45888be">llvm::SlotIndexes::getMBBEndIdx</a>, <a href="/web-llvm/docs/api/classes/llvm/slotindexes/#aaf0c07cc1cdb9c78c6dfdfdd5913420a">llvm::SlotIndexes::getMBBStartIdx</a>, <a href="/web-llvm/docs/api/classes/llvm/machinefunction/#a3d142c9e7c066059e15232c56dec9e2e">llvm::MachineFunction::getName</a>, <a href="/web-llvm/docs/api/classes/llvm/gcnrptracker/#a0e57238eeb231fb02499568087b29559">llvm::GCNRPTracker::getPressure</a>, <a href="/web-llvm/docs/api/classes/llvm/machinefunction/#a810234b6b3d223b7c74a4253fcc5ea5e">llvm::MachineFunction::getRegInfo</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/gcnregpressure-cpp/#ade1f2320fe436fd570559a11f1167746">getRegLiveThroughMask</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a273ec9d4a470ecb7362abd00438e9b26">llvm::getRegPressure</a>, <a href="/web-llvm/docs/api/classes/llvm/liveintervals/#a334e584aeef0fcf744450fdf41fe8a84">llvm::LiveIntervals::getSlotIndexes</a>, <a href="/web-llvm/docs/api/files/lib/lib/support/md5-cpp/#ac0eafdc9ee161b71e7af98af736952fd">I</a>, <a href="/web-llvm/docs/api/classes/llvm/densemapbase/#a0b2ca98dc28c61793ff5c90d23e5f14e">llvm::DenseMapBase&lt; DerivedT, KeyT, ValueT, KeyInfoT, BucketT &gt;::lookup</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/arm/armslshardening-cpp/#a5958512eae2979bd2eb383977996a600">MBB</a>, <a href="/web-llvm/docs/api/files/lib/lib/codegen/lib/codegen/globalisel/irtranslator-cpp/#abe44dfdea65b4f7e11e0a608ab708b76">MI</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64advsimdscalarpass-cpp/#aacd2ab195054a3e6a74bfbb9d5d571c8">MRI</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/gcnregpressure-cpp/#a176e4c39a833f4d01f0ecd322c0f4343">PFX</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a50bf746ca1858c0e272e3a802fc27942">llvm::print</a>, <a href="/web-llvm/docs/api/classes/llvm/gcnupwardrptracker/#a7838950673480bf3ece5ddf4f4fe0132">llvm::GCNUpwardRPTracker::recede</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#af2b74085541381aa878e3cbad0cb7b71">llvm::reportMismatch</a>, <a href="/web-llvm/docs/api/classes/llvm/gcndownwardrptracker/#a95cb78cfa1044889fefc65225f611e33">llvm::GCNDownwardRPTracker::reset</a>, <a href="/web-llvm/docs/api/classes/llvm/gcnupwardrptracker/#a548b7703f8bbf29d5782c5bcfbe0cb5c">llvm::GCNUpwardRPTracker::reset</a>, <a href="/web-llvm/docs/api/classes/llvm/gcnupwardrptracker/#aba3d281c877c68f0361b70beff7c0c23">llvm::GCNUpwardRPTracker::resetMaxPressure</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a6b0ac1fa4f05de76413c5e0ca6334035">llvm::reverse</a>, <a href="/web-llvm/docs/api/files/lib/lib/codegen/machinesink-cpp/#a0f36ed1bc17fc1aa97fe291c439a0698">TRI</a> and <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/gcnregpressure-cpp/#a321de14815a8b8290b3bc3c4d5e49c47">UseDownwardTracker</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Public Static Attributes

### ID {#a4c78216508c874805cf765901f442c3c}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">char llvm::GCNRegPressurePrinter::ID = 0</td>
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



<p>Definition at line 408 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/gcnregpressure-h">GCNRegPressure.h</a>.</p>


<p>Referenced by <a href="#aea81b74630f80ed0fee7748a9beb0992">GCNRegPressurePrinter</a>.</p>

</div>
</div>

</div>

<hr/>

The documentation for this struct was generated from the following files:

<ul>
<li><a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/gcnregpressure-cpp">GCNRegPressure.cpp</a></li>
<li><a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/gcnregpressure-h">GCNRegPressure.h</a></li>
</ul>

<hr/>

<p class="doxyGeneratedBy">Generated via <a href="https://github.com/xpack/doxygen2docusaurus">doxygen2docusaurus</a> by <a href="https://www.doxygen.nl">Doxygen</a> 1.14.0.</p>

</div>
