---

# DO NOT EDIT!
# Automatically generated via doxygen2docusaurus by Doxygen.

slug: /api/classes/anonymous-x86domainreassignment-cpp-/x86domainreassignment
custom_edit_url: null
toc_max_heading_level: 4
keywords:
  - doxygen
  - reference
  - class

---

<div class="doxyPage">

# The `X86DomainReassignment` Class Reference



## Declaration

<div class="doxyDeclaration">
class anonymous{X86DomainReassignment.cpp}::X86DomainReassignment { ... }
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a85080598351fd5940840450d6068f882">X86DomainReassignment</a> ()</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#acab3ec701472799353f6542ba0affd6a">runOnMachineFunction</a> (MachineFunction &amp;MF) override</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>runOnMachineFunction - This method must be overloaded to perform the desired machine code transformation or analysis. <a href="#acab3ec701472799353f6542ba0affd6a">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">void</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a65886b817d882e7c94ed64d866989c85">getAnalysisUsage</a> (AnalysisUsage &amp;AU) const override</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>getAnalysisUsage - Subclasses that override getAnalysisUsage must call this. <a href="#a65886b817d882e7c94ed64d866989c85">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/stringref">StringRef</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a62de40fdabff0688e3ca9310158e929f">getPassName</a> () const override</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>getPassName - Return a nice clean name for a pass. <a href="#a62de40fdabff0688e3ca9310158e929f">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

</table>

## Private Member Functions Index

<table class="doxyMembersIndex">

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">void</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a81a7e51b6379743089e2e3f6ecd31bbf">initConverters</a> ()</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Initialize Converters map. <a href="#a81a7e51b6379743089e2e3f6ecd31bbf">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">void</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a12fd07c4b91f77afea3ec20f5b2b3a90">buildClosure</a> (Closure &amp;, Register Reg)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Starting from \Reg, expand the closure as much as possible. <a href="#a12fd07c4b91f77afea3ec20f5b2b3a90">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">bool</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a1b3afd3b3378cf84739f481660251246">visitRegister</a> (Closure &amp;, Register Reg, RegDomain &amp;Domain, SmallVectorImpl&lt; unsigned &gt; &amp;Worklist)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Enqueue <span class="doxyComputerOutput">Reg</span> to be considered for addition to the closure. <a href="#a1b3afd3b3378cf84739f481660251246">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">void</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#abd72efc755f20a326f879333bc82f889">reassign</a> (const Closure &amp;C, RegDomain Domain) const</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Reassign the closure to <span class="doxyComputerOutput"><a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/scalar/correlatedvaluepropagation-cpp/#aad75d6f4f14a7b791076c6785aa59be4">Domain</a></span>. <a href="#abd72efc755f20a326f879333bc82f889">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">bool</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a19fe934234c479373b9ef7a19d4dfbb6">encloseInstr</a> (Closure &amp;C, MachineInstr *MI)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Add <span class="doxyComputerOutput">MI</span> to the closure. <a href="#a19fe934234c479373b9ef7a19d4dfbb6">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">bool</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ac31011e51f38a8d7452c8db241785a62">isReassignmentProfitable</a> (const Closure &amp;C, RegDomain Domain) const</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>/returns true if it is profitable to reassign the closure to <span class="doxyComputerOutput"><a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/scalar/correlatedvaluepropagation-cpp/#aad75d6f4f14a7b791076c6785aa59be4">Domain</a></span>. <a href="#ac31011e51f38a8d7452c8db241785a62">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">double</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#abb46ecfc71c357485ec1b5744039ed06">calculateCost</a> (const Closure &amp;C, RegDomain Domain) const</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Calculate the total cost of reassigning the closure to <span class="doxyComputerOutput"><a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/scalar/correlatedvaluepropagation-cpp/#aad75d6f4f14a7b791076c6785aa59be4">Domain</a></span>. <a href="#abb46ecfc71c357485ec1b5744039ed06">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

</table>

## Private Member Attributes Index

<table class="doxyMembersIndex">

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/x86subtarget">X86Subtarget</a> *</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#af4967cc90e8c92fe46e2512440b17a2d">STI</a> = nullptr</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ae2f85ff6230cc8d327befb1b496b7af4">MRI</a> = nullptr</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/x86instrinfo">X86InstrInfo</a> *</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a66f4a706d94f0f6278152791083abcf3">TII</a> = nullptr</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/densemap">DenseMap</a>&lt; <a href="/web-llvm/docs/api/classes/llvm/register">Register</a>, unsigned &gt;</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a88021f213fe66e9d6e8de178aa51ba4e">EnclosedEdges</a></td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>All edges that are included in some closure. <a href="#a88021f213fe66e9d6e8de178aa51ba4e">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/densemap">DenseMap</a>&lt; <a href="/web-llvm/docs/api/classes/llvm/machineinstr">MachineInstr</a> *, unsigned &gt;</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#aeb808b150baea3c58d81462816acf291">EnclosedInstrs</a></td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>All instructions that are included in some closure. <a href="#aeb808b150baea3c58d81462816acf291">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/namespaces/anonymous-x86domainreassignment-cpp-/#a1f33a3c438c119c2d319010f84067feb">InstrConverterBaseMap</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ae98b0aabff85c2028f987baa8db61f78">Converters</a></td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>A map of available <a href="/web-llvm/docs/api/classes/llvm/instruction">Instruction</a> Converters. <a href="#ae98b0aabff85c2028f987baa8db61f78">More...</a></p>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a6647537afc0d8d820cb701b5a073df69">ID</a> = 0</td>
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


<p>Definition at line 363 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/x86/x86domainreassignment-cpp">X86DomainReassignment.cpp</a>.</p>


<div class="doxySectionDef">

## Public Constructors

### X86DomainReassignment() {#a85080598351fd5940840450d6068f882}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">anonymous{X86DomainReassignment.cpp}::X86DomainReassignment::X86DomainReassignment ()</td>
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



<p>Definition at line 377 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/x86/x86domainreassignment-cpp">X86DomainReassignment.cpp</a>.</p>


<p>References <a href="#a6647537afc0d8d820cb701b5a073df69">ID</a> and <a href="/web-llvm/docs/api/classes/llvm/machinefunctionpass/#a29c81d2386f4a727c6d33413807530c8">llvm::MachineFunctionPass::MachineFunctionPass</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/x86/x86domainreassignment-cpp/#ae75f64d82b1a0268e73e32f4f3e2b5b2">INITIALIZE_PASS</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Public Member Functions

### getAnalysisUsage() {#a65886b817d882e7c94ed64d866989c85}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void anonymous{X86DomainReassignment.cpp}::X86DomainReassignment::getAnalysisUsage (<a href="/web-llvm/docs/api/classes/llvm/analysisusage">AnalysisUsage</a> &amp; AU)</td>
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

<p>getAnalysisUsage - Subclasses that override getAnalysisUsage must call this.</p>


<p>For MachineFunctionPasses, calling AU.preservesCFG() indicates that the pass does not modify the MachineBasicBlock CFG.</p>


<p>Definition at line 381 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/x86/x86domainreassignment-cpp">X86DomainReassignment.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/classes/llvm/machinefunctionpass/#a864fd57b4304ef933b3281d0ef85a88e">llvm::MachineFunctionPass::getAnalysisUsage</a> and <a href="/web-llvm/docs/api/classes/llvm/analysisusage/#af11a6ebf7ab3c388234cb6d5378439a3">llvm::AnalysisUsage::setPreservesCFG</a>.</p>

</div>
</div>

### getPassName() {#a62de40fdabff0688e3ca9310158e929f}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">StringRef anonymous{X86DomainReassignment.cpp}::X86DomainReassignment::getPassName ()</td>
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


<p>Definition at line 386 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/x86/x86domainreassignment-cpp">X86DomainReassignment.cpp</a>.</p>

</div>
</div>

### runOnMachineFunction() {#acab3ec701472799353f6542ba0affd6a}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool X86DomainReassignment::runOnMachineFunction (<a href="/web-llvm/docs/api/classes/llvm/machinefunction">MachineFunction</a> &amp; MF)</td>
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

<p>Definition at line 379 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/x86/x86domainreassignment-cpp">X86DomainReassignment.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/silowercontrolflow-cpp/#a4868c5d81c5ccc98c47aeab6244346a0">assert</a>, <a href="/web-llvm/docs/api/namespaces/llvm/callingconv/#ac6aa1387c4375260e2468eb5a77fdb4cafd841a49aec1539bc88abc8ff9e170fb">llvm::CallingConv::C</a>, <a href="/web-llvm/docs/api/groups/arcopt/#gaa57b1a4e6a1c79233913139635169cf1">Changed</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a7c46c742c31be54870e2038048e6b391">llvm::dbgs</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/x86/x86domainreassignment-cpp/#a672a2e6a497879d02bf627af5566ece1">DisableX86DomainReassignment</a>, <a href="/web-llvm/docs/api/classes/llvm/machinefunction/#a977ddce262de45c645be23d951066351">llvm::MachineFunction::getFunction</a>, <a href="/web-llvm/docs/api/classes/llvm/machinefunction/#a810234b6b3d223b7c74a4253fcc5ea5e">llvm::MachineFunction::getRegInfo</a>, <a href="/web-llvm/docs/api/classes/llvm/machinefunction/#a3825368aca2bc1550d173660df4da6a6">llvm::MachineFunction::getSubtarget</a>, <a href="/web-llvm/docs/api/classes/llvm/register/#a1979c563289f871907832e419889f979">llvm::Register::index2VirtReg</a>, <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/support/debug-h/#a196897517069dda1bdb549e24468f7d7">LLVM_DEBUG</a>, <a href="/web-llvm/docs/api/namespaces/anonymous-x86domainreassignment-cpp-/#a5591a13a87c6247cd8404d747136716aa1ac7e8f8e1cd0714e0a6daf9891ae354">anonymous{X86DomainReassignment.cpp}::MaskDomain</a>, <a href="/web-llvm/docs/api/classes/llvm/machinefunction/#ad9c9c8915579c517eff56e638c1a643c">llvm::MachineFunction::print</a> and <a href="/web-llvm/docs/api/classes/llvm/functionpass/#af9f5f511d75e16f09a5520cb9444cfa8">llvm::FunctionPass::skipFunction</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Private Member Functions

### buildClosure() {#a12fd07c4b91f77afea3ec20f5b2b3a90}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void X86DomainReassignment::buildClosure (<a href="/web-llvm/docs/api/classes/anonymous-x86domainreassignment-cpp-/closure">Closure</a> &amp; C, <a href="/web-llvm/docs/api/classes/llvm/register">Register</a> Reg)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Starting from \Reg, expand the closure as much as possible.</p>

<p>Definition at line 398 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/x86/x86domainreassignment-cpp">X86DomainReassignment.cpp</a>.</p>

</div>
</div>

### calculateCost() {#abb46ecfc71c357485ec1b5744039ed06}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">double X86DomainReassignment::calculateCost (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/anonymous-x86domainreassignment-cpp-/closure">Closure</a> &amp; C, <a href="/web-llvm/docs/api/namespaces/anonymous-x86domainreassignment-cpp-/#a5591a13a87c6247cd8404d747136716a">RegDomain</a> Domain)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Calculate the total cost of reassigning the closure to <span class="doxyComputerOutput"><a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/scalar/correlatedvaluepropagation-cpp/#aad75d6f4f14a7b791076c6785aa59be4">Domain</a></span>.</p>

<p>Definition at line 416 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/x86/x86domainreassignment-cpp">X86DomainReassignment.cpp</a>.</p>

</div>
</div>

### encloseInstr() {#a19fe934234c479373b9ef7a19d4dfbb6}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool X86DomainReassignment::encloseInstr (<a href="/web-llvm/docs/api/classes/anonymous-x86domainreassignment-cpp-/closure">Closure</a> &amp; C, <a href="/web-llvm/docs/api/classes/llvm/machineinstr">MachineInstr</a> * MI)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Add <span class="doxyComputerOutput">MI</span> to the closure.</p>


<p>Return false if the closure becomes invalid.</p>


<p>Definition at line 410 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/x86/x86domainreassignment-cpp">X86DomainReassignment.cpp</a>.</p>

</div>
</div>

### initConverters() {#a81a7e51b6379743089e2e3f6ecd31bbf}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void X86DomainReassignment::initConverters ()</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Initialize Converters map.</p>

<p>Definition at line 395 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/x86/x86domainreassignment-cpp">X86DomainReassignment.cpp</a>.</p>

</div>
</div>

### isReassignmentProfitable() {#ac31011e51f38a8d7452c8db241785a62}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool X86DomainReassignment::isReassignmentProfitable (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/anonymous-x86domainreassignment-cpp-/closure">Closure</a> &amp; C, <a href="/web-llvm/docs/api/namespaces/anonymous-x86domainreassignment-cpp-/#a5591a13a87c6247cd8404d747136716a">RegDomain</a> Domain)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>/returns true if it is profitable to reassign the closure to <span class="doxyComputerOutput"><a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/scalar/correlatedvaluepropagation-cpp/#aad75d6f4f14a7b791076c6785aa59be4">Domain</a></span>.</p>

<p>Definition at line 413 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/x86/x86domainreassignment-cpp">X86DomainReassignment.cpp</a>.</p>

</div>
</div>

### reassign() {#abd72efc755f20a326f879333bc82f889}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void X86DomainReassignment::reassign (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/anonymous-x86domainreassignment-cpp-/closure">Closure</a> &amp; C, <a href="/web-llvm/docs/api/namespaces/anonymous-x86domainreassignment-cpp-/#a5591a13a87c6247cd8404d747136716a">RegDomain</a> Domain)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Reassign the closure to <span class="doxyComputerOutput"><a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/scalar/correlatedvaluepropagation-cpp/#aad75d6f4f14a7b791076c6785aa59be4">Domain</a></span>.</p>

<p>Definition at line 406 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/x86/x86domainreassignment-cpp">X86DomainReassignment.cpp</a>.</p>

</div>
</div>

### visitRegister() {#a1b3afd3b3378cf84739f481660251246}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool X86DomainReassignment::visitRegister (<a href="/web-llvm/docs/api/classes/anonymous-x86domainreassignment-cpp-/closure">Closure</a> &amp; C, <a href="/web-llvm/docs/api/classes/llvm/register">Register</a> Reg, <a href="/web-llvm/docs/api/namespaces/anonymous-x86domainreassignment-cpp-/#a5591a13a87c6247cd8404d747136716a">RegDomain</a> &amp; Domain, <a href="/web-llvm/docs/api/classes/llvm/smallvectorimpl">SmallVectorImpl</a>&lt; unsigned &gt; &amp; Worklist)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Enqueue <span class="doxyComputerOutput">Reg</span> to be considered for addition to the closure.</p>


<p>Return false if the closure becomes invalid.</p>


<p>Definition at line 402 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/x86/x86domainreassignment-cpp">X86DomainReassignment.cpp</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Private Member Attributes

### Converters {#ae98b0aabff85c2028f987baa8db61f78}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">InstrConverterBaseMap anonymous{X86DomainReassignment.cpp}::X86DomainReassignment::Converters</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>A map of available <a href="/web-llvm/docs/api/classes/llvm/instruction">Instruction</a> Converters.</p>

<p>Definition at line 392 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/x86/x86domainreassignment-cpp">X86DomainReassignment.cpp</a>.</p>

</div>
</div>

### EnclosedEdges {#a88021f213fe66e9d6e8de178aa51ba4e}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">DenseMap&lt;Register, unsigned&gt; anonymous{X86DomainReassignment.cpp}::X86DomainReassignment::EnclosedEdges</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>All edges that are included in some closure.</p>

<p>Definition at line 369 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/x86/x86domainreassignment-cpp">X86DomainReassignment.cpp</a>.</p>

</div>
</div>

### EnclosedInstrs {#aeb808b150baea3c58d81462816acf291}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">DenseMap&lt;MachineInstr *, unsigned&gt; anonymous{X86DomainReassignment.cpp}::X86DomainReassignment::EnclosedInstrs</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>All instructions that are included in some closure.</p>

<p>Definition at line 372 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/x86/x86domainreassignment-cpp">X86DomainReassignment.cpp</a>.</p>

</div>
</div>

### MRI {#ae2f85ff6230cc8d327befb1b496b7af4}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">MachineRegisterInfo* anonymous{X86DomainReassignment.cpp}::X86DomainReassignment::MRI = nullptr</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 365 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/x86/x86domainreassignment-cpp">X86DomainReassignment.cpp</a>.</p>

</div>
</div>

### STI {#af4967cc90e8c92fe46e2512440b17a2d}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">const X86Subtarget* anonymous{X86DomainReassignment.cpp}::X86DomainReassignment::STI = nullptr</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 364 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/x86/x86domainreassignment-cpp">X86DomainReassignment.cpp</a>.</p>

</div>
</div>

### TII {#a66f4a706d94f0f6278152791083abcf3}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">const X86InstrInfo* anonymous{X86DomainReassignment.cpp}::X86DomainReassignment::TII = nullptr</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 366 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/x86/x86domainreassignment-cpp">X86DomainReassignment.cpp</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Public Static Attributes

### ID {#a6647537afc0d8d820cb701b5a073df69}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">char anonymous{X86DomainReassignment.cpp}::X86DomainReassignment::ID = 0</td>
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



<p>Definition at line 375 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/x86/x86domainreassignment-cpp">X86DomainReassignment.cpp</a>.</p>


<p>Referenced by <a href="#a85080598351fd5940840450d6068f882">X86DomainReassignment</a>.</p>

</div>
</div>

</div>

<hr/>

The documentation for this class was generated from the following file:

<ul>
<li><a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/x86/x86domainreassignment-cpp">X86DomainReassignment.cpp</a></li>
</ul>

<hr/>

<p class="doxyGeneratedBy">Generated via <a href="https://github.com/xpack/doxygen2docusaurus">doxygen2docusaurus</a> by <a href="https://www.doxygen.nl">Doxygen</a> 1.14.0.</p>

</div>
