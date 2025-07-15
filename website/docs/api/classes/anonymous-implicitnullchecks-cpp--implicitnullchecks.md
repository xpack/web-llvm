---

# DO NOT EDIT!
# Automatically generated via doxygen2docusaurus by Doxygen.

slug: /api/classes/anonymous-implicitnullchecks-cpp-/implicitnullchecks
custom_edit_url: null
toc_max_heading_level: 4
keywords:
  - doxygen
  - reference
  - class

---

<div class="doxyPage">

# The `ImplicitNullChecks` Class Reference



## Declaration

<div class="doxyDeclaration">
class anonymous{ImplicitNullChecks.cpp}::ImplicitNullChecks { ... }
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

## Enumerations Index

<table class="doxyMembersIndex">

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">enum</td>
<td class="doxyMemberIndexItemName" align="left" valign="top">AliasResult { <a href="#abf3ba12a46d9333437a168a90a0fd6d5">...</a> }</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">enum</td>
<td class="doxyMemberIndexItemName" align="left" valign="top">SuitabilityResult { <a href="#a23dbe65ae79bc71d9866eff35d3bacc4">...</a> }</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a85677a944f59f0cffed7481333a790c1">ImplicitNullChecks</a> ()</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#adfa9682269920db0fdac767478243124">runOnMachineFunction</a> (MachineFunction &amp;MF) override</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>runOnMachineFunction - This method must be overloaded to perform the desired machine code transformation or analysis. <a href="#adfa9682269920db0fdac767478243124">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">void</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ab1fc2ec69c6bd7e03ab4f5ff67e90728">getAnalysisUsage</a> (AnalysisUsage &amp;AU) const override</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>getAnalysisUsage - This function should be overriden by passes that need analysis information to do their job. <a href="#ab1fc2ec69c6bd7e03ab4f5ff67e90728">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/machinefunctionproperties">MachineFunctionProperties</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#abea1dc15403c395ed6ec0b7e31bc4f1d">getRequiredProperties</a> () const override</td>
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

## Private Member Functions Index

<table class="doxyMembersIndex">

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">bool</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#adfee430f817e41eae6c79e90e7f5a4f9">canReorder</a> (const MachineInstr *A, const MachineInstr *B)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Helper function for <span class="doxyComputerOutput">computeDependence</span>. <a href="#adfee430f817e41eae6c79e90e7f5a4f9">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">DependenceResult</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ae7dfc9dc5a26c2a030ae4248cd3a8b03">computeDependence</a> (const MachineInstr *MI, ArrayRef&lt; MachineInstr * &gt; Block)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Compute a result for the following question: can <span class="doxyComputerOutput">MI</span> be re-ordered from after <span class="doxyComputerOutput">Insts</span> to before it. <a href="#ae7dfc9dc5a26c2a030ae4248cd3a8b03">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">bool</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a0aa4c3ee1566defb522e5a81efb25d55">analyzeBlockForNullChecks</a> (MachineBasicBlock &amp;MBB, SmallVectorImpl&lt; NullCheck &gt; &amp;NullCheckList)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Analyze MBB to check if its terminating branch can be turned into an implicit null check. <a href="#a0aa4c3ee1566defb522e5a81efb25d55">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/machineinstr">MachineInstr</a> *</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a2f0e00bd225668b440e440776b6d5a99">insertFaultingInstr</a> (MachineInstr *MI, MachineBasicBlock *MBB, MachineBasicBlock *HandlerMBB)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Wrap a machine instruction, MI, into a FAULTING machine instruction. <a href="#a2f0e00bd225668b440e440776b6d5a99">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">void</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a4c9c1035fb37fa33c511e54f1f8d8c26">rewriteNullChecks</a> (ArrayRef&lt; NullCheck &gt; NullCheckList)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Rewrite the null checks in NullCheckList into implicit null checks. <a href="#a4c9c1035fb37fa33c511e54f1f8d8c26">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">AliasResult</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a59099c49591f4c1963b9f00f9e7ab6e5">areMemoryOpsAliased</a> (const MachineInstr &amp;MI, const MachineInstr *PrevMI) const</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Returns AR_NoAlias if <span class="doxyComputerOutput">MI</span> memory operation does not alias with <span class="doxyComputerOutput">PrevMI</span>, AR_MayAlias if they may alias and AR_WillAliasEverything if they may alias and any further memory operation may alias with <span class="doxyComputerOutput">PrevMI</span>. <a href="#a59099c49591f4c1963b9f00f9e7ab6e5">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">SuitabilityResult</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a08f2b458663f8b2b601698fd6473e664">isSuitableMemoryOp</a> (const MachineInstr &amp;MI, unsigned PointerReg, ArrayRef&lt; MachineInstr * &gt; PrevInsts)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Return SR_Suitable if <span class="doxyComputerOutput">MI</span> a memory operation that can be used to implicitly null check the value in <span class="doxyComputerOutput">PointerReg</span>, SR_Unsuitable if <span class="doxyComputerOutput">MI</span> cannot be used to null check and SR_Impossible if there is no sense to continue lookup due to any other instruction will not be able to be used. <a href="#a08f2b458663f8b2b601698fd6473e664">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">bool</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ad746f35eac4854193631fdd32ea2443f">canDependenceHoistingClobberLiveIns</a> (MachineInstr *DependenceMI, MachineBasicBlock *NullSucc)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Returns true if <span class="doxyComputerOutput">DependenceMI</span> can clobber the liveIns in NullSucc block if it was hoisted to the NullCheck block. <a href="#ad746f35eac4854193631fdd32ea2443f">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">bool</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a5a0e9eac1f084fb3ed61b409760a4ee2">canHoistInst</a> (MachineInstr *FaultingMI, ArrayRef&lt; MachineInstr * &gt; InstsSeenSoFar, MachineBasicBlock *NullSucc, MachineInstr *&amp;Dependence)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Return true if <span class="doxyComputerOutput">FaultingMI</span> can be hoisted from after the instructions in <span class="doxyComputerOutput">InstsSeenSoFar</span> to before them. <a href="#a5a0e9eac1f084fb3ed61b409760a4ee2">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

</table>

## Private Member Attributes Index

<table class="doxyMembersIndex">

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/targetinstrinfo">TargetInstrInfo</a> *</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a676456962da59f525a1cbc78eccca742">TII</a> = nullptr</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a25eab9454fc18b6437d2ec0d705556d8">TRI</a> = nullptr</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/namespaces/llvm/#ae457f1cf451ed893666c4a384e58f8e5">AliasAnalysis</a> *</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ae3e9548f1ff40da4e51f13ee77d46985">AA</a> = nullptr</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/machineframeinfo">MachineFrameInfo</a> *</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a61e6bd36945d177b18b42ef8eaad13b2">MFI</a> = nullptr</td>
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

## Private Static Functions Index

<table class="doxyMembersIndex">

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">static bool</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#add62b073232a8c0d6232a784f276d2e0">canHandle</a> (const MachineInstr *MI)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Return true if <span class="doxyComputerOutput">computeDependence</span> can process <span class="doxyComputerOutput">MI</span>. <a href="#add62b073232a8c0d6232a784f276d2e0">More...</a></p>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a56d0401ba9ef1c1adf4bb6734f7c4857">ID</a> = 0</td>
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


<p>Definition at line 79 of file <a href="/web-llvm/docs/api/files/lib/lib/codegen/implicitnullchecks-cpp">ImplicitNullChecks.cpp</a>.</p>


<div class="doxySectionDef">

## Enumerations

### AliasResult {#abf3ba12a46d9333437a168a90a0fd6d5}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">enum anonymous{ImplicitNullChecks.cpp}::ImplicitNullChecks::AliasResult </td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">


<dl class="doxyEnumList">
<dt class="doxyEnumTableTitle">Enumeration values</dt>
<dd>
<table class="doxyEnumTable">

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">AR_NoAlias<a id="abf3ba12a46d9333437a168a90a0fd6d5ac15f328e163091ec7dc10e03af8e3756"></a></td>
<td class="doxyEnumItemDescription"></td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">AR_MayAlias<a id="abf3ba12a46d9333437a168a90a0fd6d5a7162163385d34e2aab5f5ad37ad869dd"></a></td>
<td class="doxyEnumItemDescription"></td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">AR_WillAliasEverything<a id="abf3ba12a46d9333437a168a90a0fd6d5a7548cf656551e412fef19f03452fe7fe"></a></td>
<td class="doxyEnumItemDescription"></td>
</tr>

</table>
</dd>
</dl>

<p>Definition at line 173 of file <a href="/web-llvm/docs/api/files/lib/lib/codegen/implicitnullchecks-cpp">ImplicitNullChecks.cpp</a>.</p>

</div>
</div>

### SuitabilityResult {#a23dbe65ae79bc71d9866eff35d3bacc4}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">enum anonymous{ImplicitNullChecks.cpp}::ImplicitNullChecks::SuitabilityResult </td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">


<dl class="doxyEnumList">
<dt class="doxyEnumTableTitle">Enumeration values</dt>
<dd>
<table class="doxyEnumTable">

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">SR_Suitable<a id="a23dbe65ae79bc71d9866eff35d3bacc4ac85b5a338d44e35f8a9942a6083dad20"></a></td>
<td class="doxyEnumItemDescription"></td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">SR_Unsuitable<a id="a23dbe65ae79bc71d9866eff35d3bacc4ad5f5d2c1098b9e7aca7414c8b5f00543"></a></td>
<td class="doxyEnumItemDescription"></td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">SR_Impossible<a id="a23dbe65ae79bc71d9866eff35d3bacc4a2ee4618ce664f5a2c12c0032df0cfb66"></a></td>
<td class="doxyEnumItemDescription"></td>
</tr>

</table>
</dd>
</dl>

<p>Definition at line 185 of file <a href="/web-llvm/docs/api/files/lib/lib/codegen/implicitnullchecks-cpp">ImplicitNullChecks.cpp</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Public Constructors

### ImplicitNullChecks() {#a85677a944f59f0cffed7481333a790c1}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">anonymous{ImplicitNullChecks.cpp}::ImplicitNullChecks::ImplicitNullChecks ()</td>
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



<p>Definition at line 217 of file <a href="/web-llvm/docs/api/files/lib/lib/codegen/implicitnullchecks-cpp">ImplicitNullChecks.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/classes/llvm/passregistry/#a05a729900b76c89e808c6c3094921b2f">llvm::PassRegistry::getPassRegistry</a>, <a href="#a56d0401ba9ef1c1adf4bb6734f7c4857">ID</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#ae4fed34333ce5d5538f60a55cfdcc328">llvm::initializeImplicitNullChecksPass</a> and <a href="/web-llvm/docs/api/classes/llvm/machinefunctionpass/#a29c81d2386f4a727c6d33413807530c8">llvm::MachineFunctionPass::MachineFunctionPass</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Public Member Functions

### getAnalysisUsage() {#ab1fc2ec69c6bd7e03ab4f5ff67e90728}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void anonymous{ImplicitNullChecks.cpp}::ImplicitNullChecks::getAnalysisUsage (<a href="/web-llvm/docs/api/classes/llvm/analysisusage">AnalysisUsage</a> &amp;)</td>
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


<p>Definition at line 223 of file <a href="/web-llvm/docs/api/files/lib/lib/codegen/implicitnullchecks-cpp">ImplicitNullChecks.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/classes/llvm/analysisusage/#ae0adcccca08fb686c9ce00f9397b660c">llvm::AnalysisUsage::addRequired</a> and <a href="/web-llvm/docs/api/classes/llvm/machinefunctionpass/#a864fd57b4304ef933b3281d0ef85a88e">llvm::MachineFunctionPass::getAnalysisUsage</a>.</p>

</div>
</div>

### getRequiredProperties() {#abea1dc15403c395ed6ec0b7e31bc4f1d}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">MachineFunctionProperties anonymous{ImplicitNullChecks.cpp}::ImplicitNullChecks::getRequiredProperties ()</td>
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



<p>Definition at line 228 of file <a href="/web-llvm/docs/api/files/lib/lib/codegen/implicitnullchecks-cpp">ImplicitNullChecks.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/classes/llvm/machinefunctionproperties/#ad85237c6c667e4713efe8921e9c32ac1a72f7d830dd5ddb30f06d8e9639558ac3">llvm::MachineFunctionProperties::NoVRegs</a> and <a href="/web-llvm/docs/api/classes/llvm/machinefunctionproperties/#aa7780563d7ca260d0ae67d957b56427f">llvm::MachineFunctionProperties::set</a>.</p>

</div>
</div>

### runOnMachineFunction() {#adfa9682269920db0fdac767478243124}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool ImplicitNullChecks::runOnMachineFunction (<a href="/web-llvm/docs/api/classes/llvm/machinefunction">MachineFunction</a> &amp; MF)</td>
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

<p>Definition at line 221 of file <a href="/web-llvm/docs/api/files/lib/lib/codegen/implicitnullchecks-cpp">ImplicitNullChecks.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/classes/llvm/smallvectortemplatecommon/#ad9a3c7bc26b130377bbafc170b5f88a2">llvm::SmallVectorTemplateCommon&lt; T, typename &gt;::empty</a>, <a href="/web-llvm/docs/api/classes/llvm/pass/#a4863e5e463fb79955269fbf7fbf52b80">llvm::Pass::getAnalysis</a>, <a href="/web-llvm/docs/api/classes/llvm/machinefunction/#a54f334a9c8ca6d105eae383ae87e4524">llvm::MachineFunction::getFrameInfo</a>, <a href="/web-llvm/docs/api/classes/llvm/targetsubtargetinfo/#acd858ed72f11db9444617740c3622608">llvm::TargetSubtargetInfo::getInstrInfo</a>, <a href="/web-llvm/docs/api/classes/llvm/machinefunction/#a810234b6b3d223b7c74a4253fcc5ea5e">llvm::MachineFunction::getRegInfo</a>, <a href="/web-llvm/docs/api/classes/llvm/machinefunction/#a3825368aca2bc1550d173660df4da6a6">llvm::MachineFunction::getSubtarget</a>, <a href="/web-llvm/docs/api/classes/llvm/machineregisterinfo/#ab79ea5367e2539a9cca11f9db6f92c06">llvm::MachineRegisterInfo::getTargetRegisterInfo</a> and <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/arm/armslshardening-cpp/#a5958512eae2979bd2eb383977996a600">MBB</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Private Member Functions

### analyzeBlockForNullChecks() {#a0aa4c3ee1566defb522e5a81efb25d55}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool ImplicitNullChecks::analyzeBlockForNullChecks (<a href="/web-llvm/docs/api/classes/llvm/machinebasicblock">MachineBasicBlock</a> &amp; MBB, <a href="/web-llvm/docs/api/classes/llvm/smallvectorimpl">SmallVectorImpl</a>&lt; NullCheck &gt; &amp; NullCheckList)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Analyze MBB to check if its terminating branch can be turned into an implicit null check.</p>


<p>If yes, append a description of the said null check to NullCheckList and return true, else return false.</p>


<p>Definition at line 167 of file <a href="/web-llvm/docs/api/files/lib/lib/codegen/implicitnullchecks-cpp">ImplicitNullChecks.cpp</a>.</p>

</div>
</div>

### areMemoryOpsAliased() {#a59099c49591f4c1963b9f00f9e7ab6e5}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">ImplicitNullChecks::AliasResult ImplicitNullChecks::areMemoryOpsAliased (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/machineinstr">MachineInstr</a> &amp; MI, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/machineinstr">MachineInstr</a> * PrevMI)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Returns AR_NoAlias if <span class="doxyComputerOutput">MI</span> memory operation does not alias with <span class="doxyComputerOutput">PrevMI</span>, AR_MayAlias if they may alias and AR_WillAliasEverything if they may alias and any further memory operation may alias with <span class="doxyComputerOutput">PrevMI</span>.</p>

<p>Definition at line 182 of file <a href="/web-llvm/docs/api/files/lib/lib/codegen/implicitnullchecks-cpp">ImplicitNullChecks.cpp</a>.</p>

</div>
</div>

### canDependenceHoistingClobberLiveIns() {#ad746f35eac4854193631fdd32ea2443f}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool ImplicitNullChecks::canDependenceHoistingClobberLiveIns (<a href="/web-llvm/docs/api/classes/llvm/machineinstr">MachineInstr</a> * DependenceMI, <a href="/web-llvm/docs/api/classes/llvm/machinebasicblock">MachineBasicBlock</a> * NullSucc)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Returns true if <span class="doxyComputerOutput">DependenceMI</span> can clobber the liveIns in NullSucc block if it was hoisted to the NullCheck block.</p>


<p>This is used by caller canHoistInst to decide if DependenceMI can be hoisted safely.</p>


<p>Definition at line 204 of file <a href="/web-llvm/docs/api/files/lib/lib/codegen/implicitnullchecks-cpp">ImplicitNullChecks.cpp</a>.</p>

</div>
</div>

### canHoistInst() {#a5a0e9eac1f084fb3ed61b409760a4ee2}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool ImplicitNullChecks::canHoistInst (<a href="/web-llvm/docs/api/classes/llvm/machineinstr">MachineInstr</a> * FaultingMI, <a href="/web-llvm/docs/api/classes/llvm/arrayref">ArrayRef</a>&lt; <a href="/web-llvm/docs/api/classes/llvm/machineinstr">MachineInstr</a> * &gt; InstsSeenSoFar, <a href="/web-llvm/docs/api/classes/llvm/machinebasicblock">MachineBasicBlock</a> * NullSucc, <a href="/web-llvm/docs/api/classes/llvm/machineinstr">MachineInstr</a> *&amp; Dependence)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Return true if <span class="doxyComputerOutput">FaultingMI</span> can be hoisted from after the instructions in <span class="doxyComputerOutput">InstsSeenSoFar</span> to before them.</p>


<p>Set <span class="doxyComputerOutput"><a href="/web-llvm/docs/api/classes/llvm/dependence">Dependence</a></span> to a non-null value if we also need to (and legally can) hoist a dependency.</p>


<p>Definition at line 210 of file <a href="/web-llvm/docs/api/files/lib/lib/codegen/implicitnullchecks-cpp">ImplicitNullChecks.cpp</a>.</p>

</div>
</div>

### canReorder() {#adfee430f817e41eae6c79e90e7f5a4f9}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool ImplicitNullChecks::canReorder (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/machineinstr">MachineInstr</a> * A, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/machineinstr">MachineInstr</a> * B)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Helper function for <span class="doxyComputerOutput">computeDependence</span>.</p>


<p>Return true if <span class="doxyComputerOutput">A</span> and <span class="doxyComputerOutput">B</span> do not have any dependences between them, and can be re-ordered without changing program semantics.</p>


<p>Definition at line 86 of file <a href="/web-llvm/docs/api/files/lib/lib/codegen/implicitnullchecks-cpp">ImplicitNullChecks.cpp</a>.</p>

</div>
</div>

### computeDependence() {#ae7dfc9dc5a26c2a030ae4248cd3a8b03}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">ImplicitNullChecks::DependenceResult ImplicitNullChecks::computeDependence (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/machineinstr">MachineInstr</a> * MI, <a href="/web-llvm/docs/api/classes/llvm/arrayref">ArrayRef</a>&lt; <a href="/web-llvm/docs/api/classes/llvm/machineinstr">MachineInstr</a> * &gt; Block)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Compute a result for the following question: can <span class="doxyComputerOutput">MI</span> be re-ordered from after <span class="doxyComputerOutput">Insts</span> to before it.</p>


<p><span class="doxyComputerOutput">canHandle</span> should return true for all instructions in <span class="doxyComputerOutput">Insts</span>.</p>


<p>Definition at line 115 of file <a href="/web-llvm/docs/api/files/lib/lib/codegen/implicitnullchecks-cpp">ImplicitNullChecks.cpp</a>.</p>

</div>
</div>

### insertFaultingInstr() {#a2f0e00bd225668b440e440776b6d5a99}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">MachineInstr * ImplicitNullChecks::insertFaultingInstr (<a href="/web-llvm/docs/api/classes/llvm/machineinstr">MachineInstr</a> * MI, <a href="/web-llvm/docs/api/classes/llvm/machinebasicblock">MachineBasicBlock</a> * MBB, <a href="/web-llvm/docs/api/classes/llvm/machinebasicblock">MachineBasicBlock</a> * HandlerMBB)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Wrap a machine instruction, MI, into a FAULTING machine instruction.</p>


<p>The FAULTING instruction does the same load/store as MI (defining the same register), and branches to HandlerMBB if the mem access faults. The FAULTING instruction is inserted at the end of MBB.</p>


<p>Definition at line 169 of file <a href="/web-llvm/docs/api/files/lib/lib/codegen/implicitnullchecks-cpp">ImplicitNullChecks.cpp</a>.</p>

</div>
</div>

### isSuitableMemoryOp() {#a08f2b458663f8b2b601698fd6473e664}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">ImplicitNullChecks::SuitabilityResult ImplicitNullChecks::isSuitableMemoryOp (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/machineinstr">MachineInstr</a> &amp; MI, unsigned PointerReg, <a href="/web-llvm/docs/api/classes/llvm/arrayref">ArrayRef</a>&lt; <a href="/web-llvm/docs/api/classes/llvm/machineinstr">MachineInstr</a> * &gt; PrevInsts)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Return SR_Suitable if <span class="doxyComputerOutput">MI</span> a memory operation that can be used to implicitly null check the value in <span class="doxyComputerOutput">PointerReg</span>, SR_Unsuitable if <span class="doxyComputerOutput">MI</span> cannot be used to null check and SR_Impossible if there is no sense to continue lookup due to any other instruction will not be able to be used.</p>


<p><span class="doxyComputerOutput">PrevInsts</span> is the set of instruction seen since the explicit null check on <span class="doxyComputerOutput">PointerReg</span>.</p>


<p>Definition at line 197 of file <a href="/web-llvm/docs/api/files/lib/lib/codegen/implicitnullchecks-cpp">ImplicitNullChecks.cpp</a>.</p>

</div>
</div>

### rewriteNullChecks() {#a4c9c1035fb37fa33c511e54f1f8d8c26}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void ImplicitNullChecks::rewriteNullChecks (<a href="/web-llvm/docs/api/classes/llvm/arrayref">ArrayRef</a>&lt; NullCheck &gt; NullCheckList)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Rewrite the null checks in NullCheckList into implicit null checks.</p>

<p>Definition at line 171 of file <a href="/web-llvm/docs/api/files/lib/lib/codegen/implicitnullchecks-cpp">ImplicitNullChecks.cpp</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Private Member Attributes

### AA {#ae3e9548f1ff40da4e51f13ee77d46985}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">AliasAnalysis* anonymous{ImplicitNullChecks.cpp}::ImplicitNullChecks::AA = nullptr</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 164 of file <a href="/web-llvm/docs/api/files/lib/lib/codegen/implicitnullchecks-cpp">ImplicitNullChecks.cpp</a>.</p>

</div>
</div>

### MFI {#a61e6bd36945d177b18b42ef8eaad13b2}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">MachineFrameInfo* anonymous{ImplicitNullChecks.cpp}::ImplicitNullChecks::MFI = nullptr</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 165 of file <a href="/web-llvm/docs/api/files/lib/lib/codegen/implicitnullchecks-cpp">ImplicitNullChecks.cpp</a>.</p>

</div>
</div>

### TII {#a676456962da59f525a1cbc78eccca742}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">const TargetInstrInfo* anonymous{ImplicitNullChecks.cpp}::ImplicitNullChecks::TII = nullptr</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 162 of file <a href="/web-llvm/docs/api/files/lib/lib/codegen/implicitnullchecks-cpp">ImplicitNullChecks.cpp</a>.</p>

</div>
</div>

### TRI {#a25eab9454fc18b6437d2ec0d705556d8}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">const TargetRegisterInfo* anonymous{ImplicitNullChecks.cpp}::ImplicitNullChecks::TRI = nullptr</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 163 of file <a href="/web-llvm/docs/api/files/lib/lib/codegen/implicitnullchecks-cpp">ImplicitNullChecks.cpp</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Private Static Functions

### canHandle() {#add62b073232a8c0d6232a784f276d2e0}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool ImplicitNullChecks::canHandle (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/machineinstr">MachineInstr</a> * MI)</td>
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

<p>Return true if <span class="doxyComputerOutput">computeDependence</span> can process <span class="doxyComputerOutput">MI</span>.</p>

<p>Definition at line 81 of file <a href="/web-llvm/docs/api/files/lib/lib/codegen/implicitnullchecks-cpp">ImplicitNullChecks.cpp</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Public Static Attributes

### ID {#a56d0401ba9ef1c1adf4bb6734f7c4857}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">char ImplicitNullChecks::ID = 0</td>
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



<p>Definition at line 215 of file <a href="/web-llvm/docs/api/files/lib/lib/codegen/implicitnullchecks-cpp">ImplicitNullChecks.cpp</a>.</p>


<p>Referenced by <a href="#a85677a944f59f0cffed7481333a790c1">ImplicitNullChecks</a>.</p>

</div>
</div>

</div>

<hr/>

The documentation for this class was generated from the following file:

<ul>
<li><a href="/web-llvm/docs/api/files/lib/lib/codegen/implicitnullchecks-cpp">ImplicitNullChecks.cpp</a></li>
</ul>

<hr/>

<p class="doxyGeneratedBy">Generated via <a href="https://github.com/xpack/doxygen2docusaurus">doxygen2docusaurus</a> by <a href="https://www.doxygen.nl">Doxygen</a> 1.14.0.</p>

</div>
