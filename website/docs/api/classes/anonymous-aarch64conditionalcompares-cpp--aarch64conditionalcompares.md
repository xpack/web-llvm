---

# DO NOT EDIT!
# Automatically generated via doxygen2docusaurus by Doxygen.

slug: /api/classes/anonymous-aarch64conditionalcompares-cpp-/aarch64conditionalcompares
custom_edit_url: null
toc_max_heading_level: 4
keywords:
  - doxygen
  - reference
  - class

---

<div class="doxyPage">

# `AArch64ConditionalCompares` Class



## Declaration

<div class="doxyDeclaration">
class anonymous{AArch64ConditionalCompares.cpp}::AArch64ConditionalCompares { ... }
</div>

## Base class

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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a8e9494d7e3bf515011c0961efe205868">AArch64ConditionalCompares</a> ()</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a79c4f2a0f6ffc1499b12ed125d7eb037">getAnalysisUsage</a> (AnalysisUsage &amp;AU) const override</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>getAnalysisUsage - This function should be overriden by passes that need analysis information to do their job. <a href="#a79c4f2a0f6ffc1499b12ed125d7eb037">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">bool</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#af7b7982c58340c2b9b066e30a4fd558f">runOnMachineFunction</a> (MachineFunction &amp;MF) override</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>runOnMachineFunction - This method must be overloaded to perform the desired machine code transformation or analysis. <a href="#af7b7982c58340c2b9b066e30a4fd558f">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/stringref">StringRef</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a1256112f73b9774072765f629fa69669">getPassName</a> () const override</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>getPassName - Return a nice clean name for a pass. <a href="#a1256112f73b9774072765f629fa69669">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

</table>

## Private Member Functions Index

<table class="doxyMembersIndex">

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">bool</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a41daf25a175cbef7623f444f3f2bc40b">tryConvert</a> (MachineBasicBlock *)</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ade1446bf3cce928c72bbc0fb396cd5ca">updateDomTree</a> (ArrayRef&lt; MachineBasicBlock * &gt; Removed)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Update the dominator tree after if-conversion erased some blocks. <a href="#ade1446bf3cce928c72bbc0fb396cd5ca">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">void</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ac1a7df132f6690b3c6665d85e11b3bc7">updateLoops</a> (ArrayRef&lt; MachineBasicBlock * &gt; Removed)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Update <a href="/web-llvm/docs/api/classes/llvm/loopinfo">LoopInfo</a> after if-conversion. <a href="#ac1a7df132f6690b3c6665d85e11b3bc7">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">void</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a41b4aed26dd983ee6b56bff4aa1db970">invalidateTraces</a> ()</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Invalidate <a href="/web-llvm/docs/api/classes/llvm/machinetracemetrics">MachineTraceMetrics</a> before if-conversion. <a href="#a41b4aed26dd983ee6b56bff4aa1db970">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">bool</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ac92d903b6bafe8dce56fd18e5c34f48e">shouldConvert</a> ()</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Apply cost model and heuristics to the if-conversion in IfConv. <a href="#ac92d903b6bafe8dce56fd18e5c34f48e">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

</table>

## Private Member Attributes Index

<table class="doxyMembersIndex">

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/machinebranchprobabilityinfo">MachineBranchProbabilityInfo</a> *</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ac3fb83156010967391ed7e99eafb4ac2">MBPI</a></td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/targetinstrinfo">TargetInstrInfo</a> *</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ac8e9b2a9f621c77f2ed1bb053ebd76d1">TII</a></td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/targetregisterinfo">TargetRegisterInfo</a> *</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a9c2192a90160305b689249ac3f3570f1">TRI</a></td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/structs/llvm/mcschedmodel">MCSchedModel</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a7f0aef06442fd90df95049ca8c4a04a4">SchedModel</a></td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a8d7d275c18596c95e1f6bf25f0528fd8">MinSize</a></td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/machineregisterinfo">MachineRegisterInfo</a> *</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a15454ee3268536ae83e108de4a392bf5">MRI</a></td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/machinedominatortree">MachineDominatorTree</a> *</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a0231825e509cfd7dedd2df643ce5b4b3">DomTree</a></td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/machineloopinfo">MachineLoopInfo</a> *</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#aa444787155bbee03dc525d36b222d5ee">Loops</a></td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/machinetracemetrics">MachineTraceMetrics</a> *</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a1e4012e1bd5fccf100a6d96b574dee6c">Traces</a></td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/machinetracemetrics/ensemble">MachineTraceMetrics::Ensemble</a> *</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a847bb1d2b296428ab143052cba179f76">MinInstr</a></td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/anonymous-aarch64conditionalcompares-cpp-/ssaccmpconv">SSACCmpConv</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#aea1d91f593b414e94354557d143aff7c">CmpConv</a></td>
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

## Public Static Attributes Index

<table class="doxyMembersIndex">

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">static char</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ab3d46fafd09dda8465a2094b605a4483">ID</a> = 0</td>
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


<p>Definition at line 758 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64conditionalcompares-cpp">AArch64ConditionalCompares.cpp</a>.</p>


<div class="doxySectionDef">

## Public Constructors

### AArch64ConditionalCompares() {#a8e9494d7e3bf515011c0961efe205868}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">anonymous{AArch64ConditionalCompares.cpp}::AArch64ConditionalCompares::AArch64ConditionalCompares ()</td>
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



<p>Definition at line 774 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64conditionalcompares-cpp">AArch64ConditionalCompares.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/classes/llvm/passregistry/#a05a729900b76c89e808c6c3094921b2f">llvm::PassRegistry::getPassRegistry</a>, <a href="#ab3d46fafd09dda8465a2094b605a4483">ID</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#ade08d45fe60a1c623b06feb812f49972">llvm::initializeAArch64ConditionalComparesPass</a> and <a href="/web-llvm/docs/api/classes/llvm/machinefunctionpass/#a29c81d2386f4a727c6d33413807530c8">llvm::MachineFunctionPass::MachineFunctionPass</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/namespaces/llvm/#a6a63d56b5981bfe70febc2adc7e3672e">llvm::createAArch64ConditionalCompares</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Public Member Functions

### getAnalysisUsage() {#a79c4f2a0f6ffc1499b12ed125d7eb037}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void AArch64ConditionalCompares::getAnalysisUsage (<a href="/web-llvm/docs/api/classes/llvm/analysisusage">AnalysisUsage</a> &amp;)</td>
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

<p>getAnalysisUsage - This function should be overriden by passes that need analysis information to do their job.</p>


<p>If a pass specifies that it uses a particular analysis result to this function, it can then use the <a href="/web-llvm/docs/api/classes/llvm/pass/#a4863e5e463fb79955269fbf7fbf52b80">getAnalysis&lt;AnalysisType&gt;()</a> function, below.</p>


<p>Definition at line 777 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64conditionalcompares-cpp">AArch64ConditionalCompares.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/classes/llvm/analysisusage/#ae9356b720f6fbab112d809738dcc4f2a">llvm::AnalysisUsage::addPreserved</a>, <a href="/web-llvm/docs/api/classes/llvm/analysisusage/#ae0adcccca08fb686c9ce00f9397b660c">llvm::AnalysisUsage::addRequired</a> and <a href="/web-llvm/docs/api/classes/llvm/machinefunctionpass/#a864fd57b4304ef933b3281d0ef85a88e">llvm::MachineFunctionPass::getAnalysisUsage</a>.</p>

</div>
</div>

### getPassName() {#a1256112f73b9774072765f629fa69669}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">StringRef anonymous{AArch64ConditionalCompares.cpp}::AArch64ConditionalCompares::getPassName ()</td>
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

<p>getPassName - Return a nice clean name for a pass.</p>


<p>This usually implemented in terms of the name that is registered by one of the Registration templates, but can be overloaded directly.</p>


<p>Definition at line 779 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64conditionalcompares-cpp">AArch64ConditionalCompares.cpp</a>.</p>

</div>
</div>

### runOnMachineFunction() {#af7b7982c58340c2b9b066e30a4fd558f}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool AArch64ConditionalCompares::runOnMachineFunction (<a href="/web-llvm/docs/api/classes/llvm/machinefunction">MachineFunction</a> &amp; MF)</td>
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

<p>Definition at line 778 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64conditionalcompares-cpp">AArch64ConditionalCompares.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/namespaces/llvm/#a7c46c742c31be54870e2038048e6b391">llvm::dbgs</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#ad6e19a09aeed4c56617c284e099c81de">llvm::depth_first</a>, <a href="/web-llvm/docs/api/classes/llvm/pass/#a4863e5e463fb79955269fbf7fbf52b80">llvm::Pass::getAnalysis</a>, <a href="/web-llvm/docs/api/classes/llvm/machinefunction/#a977ddce262de45c645be23d951066351">llvm::MachineFunction::getFunction</a>, <a href="/web-llvm/docs/api/classes/llvm/targetsubtargetinfo/#acd858ed72f11db9444617740c3622608">llvm::TargetSubtargetInfo::getInstrInfo</a>, <a href="/web-llvm/docs/api/classes/llvm/machinefunction/#a3d142c9e7c066059e15232c56dec9e2e">llvm::MachineFunction::getName</a>, <a href="/web-llvm/docs/api/classes/llvm/machinefunction/#a810234b6b3d223b7c74a4253fcc5ea5e">llvm::MachineFunction::getRegInfo</a>, <a href="/web-llvm/docs/api/classes/llvm/targetsubtargetinfo/#a43c530c830206ecf5ad3359364634c75">llvm::TargetSubtargetInfo::getRegisterInfo</a>, <a href="/web-llvm/docs/api/classes/llvm/mcsubtargetinfo/#af907ecc18c1f4f0bce8a9e2eb449ffb8">llvm::MCSubtargetInfo::getSchedModel</a>, <a href="/web-llvm/docs/api/classes/llvm/machinefunction/#a3825368aca2bc1550d173660df4da6a6">llvm::MachineFunction::getSubtarget</a>, <a href="/web-llvm/docs/api/classes/llvm/function/#a548cfb9440f36ba67fc5566b8e967fc6">llvm::Function::hasMinSize</a>, <a href="/web-llvm/docs/api/files/lib/lib/support/md5-cpp/#ac0eafdc9ee161b71e7af98af736952fd">I</a>, <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/support/debug-h/#a196897517069dda1bdb549e24468f7d7">LLVM_DEBUG</a> and <a href="/web-llvm/docs/api/classes/llvm/functionpass/#af9f5f511d75e16f09a5520cb9444cfa8">llvm::FunctionPass::skipFunction</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Private Member Functions

### invalidateTraces() {#a41b4aed26dd983ee6b56bff4aa1db970}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void AArch64ConditionalCompares::invalidateTraces ()</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Invalidate <a href="/web-llvm/docs/api/classes/llvm/machinetracemetrics">MachineTraceMetrics</a> before if-conversion.</p>

<p>Definition at line 787 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64conditionalcompares-cpp">AArch64ConditionalCompares.cpp</a>.</p>

</div>
</div>

### shouldConvert() {#ac92d903b6bafe8dce56fd18e5c34f48e}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool AArch64ConditionalCompares::shouldConvert ()</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Apply cost model and heuristics to the if-conversion in IfConv.</p>


<p>Return true if the conversion is a good idea.</p>


<p>Definition at line 788 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64conditionalcompares-cpp">AArch64ConditionalCompares.cpp</a>.</p>

</div>
</div>

### tryConvert() {#a41daf25a175cbef7623f444f3f2bc40b}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool AArch64ConditionalCompares::tryConvert (<a href="/web-llvm/docs/api/classes/llvm/machinebasicblock">MachineBasicBlock</a> * MBB)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 784 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64conditionalcompares-cpp">AArch64ConditionalCompares.cpp</a>.</p>

</div>
</div>

### updateDomTree() {#ade1446bf3cce928c72bbc0fb396cd5ca}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void AArch64ConditionalCompares::updateDomTree (<a href="/web-llvm/docs/api/classes/llvm/arrayref">ArrayRef</a>&lt; <a href="/web-llvm/docs/api/classes/llvm/machinebasicblock">MachineBasicBlock</a> * &gt; Removed)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Update the dominator tree after if-conversion erased some blocks.</p>

<p>Definition at line 785 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64conditionalcompares-cpp">AArch64ConditionalCompares.cpp</a>.</p>

</div>
</div>

### updateLoops() {#ac1a7df132f6690b3c6665d85e11b3bc7}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void AArch64ConditionalCompares::updateLoops (<a href="/web-llvm/docs/api/classes/llvm/arrayref">ArrayRef</a>&lt; <a href="/web-llvm/docs/api/classes/llvm/machinebasicblock">MachineBasicBlock</a> * &gt; Removed)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Update <a href="/web-llvm/docs/api/classes/llvm/loopinfo">LoopInfo</a> after if-conversion.</p>

<p>Definition at line 786 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64conditionalcompares-cpp">AArch64ConditionalCompares.cpp</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Private Member Attributes

### CmpConv {#aea1d91f593b414e94354557d143aff7c}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">SSACCmpConv anonymous{AArch64ConditionalCompares.cpp}::AArch64ConditionalCompares::CmpConv</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 770 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64conditionalcompares-cpp">AArch64ConditionalCompares.cpp</a>.</p>

</div>
</div>

### DomTree {#a0231825e509cfd7dedd2df643ce5b4b3}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">MachineDominatorTree* anonymous{AArch64ConditionalCompares.cpp}::AArch64ConditionalCompares::DomTree</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 766 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64conditionalcompares-cpp">AArch64ConditionalCompares.cpp</a>.</p>

</div>
</div>

### Loops {#aa444787155bbee03dc525d36b222d5ee}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">MachineLoopInfo* anonymous{AArch64ConditionalCompares.cpp}::AArch64ConditionalCompares::Loops</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 767 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64conditionalcompares-cpp">AArch64ConditionalCompares.cpp</a>.</p>

</div>
</div>

### MBPI {#ac3fb83156010967391ed7e99eafb4ac2}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">const MachineBranchProbabilityInfo* anonymous{AArch64ConditionalCompares.cpp}::AArch64ConditionalCompares::MBPI</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 759 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64conditionalcompares-cpp">AArch64ConditionalCompares.cpp</a>.</p>

</div>
</div>

### MinInstr {#a847bb1d2b296428ab143052cba179f76}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">MachineTraceMetrics::Ensemble* anonymous{AArch64ConditionalCompares.cpp}::AArch64ConditionalCompares::MinInstr</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 769 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64conditionalcompares-cpp">AArch64ConditionalCompares.cpp</a>.</p>

</div>
</div>

### MinSize {#a8d7d275c18596c95e1f6bf25f0528fd8}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool anonymous{AArch64ConditionalCompares.cpp}::AArch64ConditionalCompares::MinSize</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 764 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64conditionalcompares-cpp">AArch64ConditionalCompares.cpp</a>.</p>

</div>
</div>

### MRI {#a15454ee3268536ae83e108de4a392bf5}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">MachineRegisterInfo* anonymous{AArch64ConditionalCompares.cpp}::AArch64ConditionalCompares::MRI</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 765 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64conditionalcompares-cpp">AArch64ConditionalCompares.cpp</a>.</p>

</div>
</div>

### SchedModel {#a7f0aef06442fd90df95049ca8c4a04a4}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">MCSchedModel anonymous{AArch64ConditionalCompares.cpp}::AArch64ConditionalCompares::SchedModel</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 762 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64conditionalcompares-cpp">AArch64ConditionalCompares.cpp</a>.</p>

</div>
</div>

### TII {#ac8e9b2a9f621c77f2ed1bb053ebd76d1}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">const TargetInstrInfo* anonymous{AArch64ConditionalCompares.cpp}::AArch64ConditionalCompares::TII</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 760 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64conditionalcompares-cpp">AArch64ConditionalCompares.cpp</a>.</p>

</div>
</div>

### Traces {#a1e4012e1bd5fccf100a6d96b574dee6c}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">MachineTraceMetrics* anonymous{AArch64ConditionalCompares.cpp}::AArch64ConditionalCompares::Traces</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 768 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64conditionalcompares-cpp">AArch64ConditionalCompares.cpp</a>.</p>

</div>
</div>

### TRI {#a9c2192a90160305b689249ac3f3570f1}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">const TargetRegisterInfo* anonymous{AArch64ConditionalCompares.cpp}::AArch64ConditionalCompares::TRI</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 761 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64conditionalcompares-cpp">AArch64ConditionalCompares.cpp</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Public Static Attributes

### ID {#ab3d46fafd09dda8465a2094b605a4483}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">char AArch64ConditionalCompares::ID = 0</td>
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



<p>Definition at line 773 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64conditionalcompares-cpp">AArch64ConditionalCompares.cpp</a>.</p>


<p>Referenced by <a href="#a8e9494d7e3bf515011c0961efe205868">AArch64ConditionalCompares</a>.</p>

</div>
</div>

</div>

<hr/>

The documentation for this class was generated from the following file:

<ul>
<li><a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64conditionalcompares-cpp">AArch64ConditionalCompares.cpp</a></li>
</ul>

<hr/>

<p class="doxyGeneratedBy">Generated via <a href="https://github.com/xpack/doxygen2docusaurus">doxygen2docusaurus</a> by <a href="https://www.doxygen.nl">Doxygen</a> 1.15.0.</p>

</div>
