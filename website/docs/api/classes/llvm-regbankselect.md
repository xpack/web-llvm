---

# DO NOT EDIT!
# Automatically generated via doxygen2docusaurus by Doxygen.

slug: /api/classes/llvm/regbankselect
custom_edit_url: null
toc_max_heading_level: 4
keywords:
  - doxygen
  - reference
  - class

---

<div class="doxyPage">

# The `RegBankSelect` Class Reference

<p>This pass implements the reg bank selector pass used in the GlobalISel pipeline. <a href="#details">More...</a></p>

## Declaration

<div class="doxyDeclaration">
class llvm::RegBankSelect { ... }
</div>

## Included Headers

<div class="doxyIncludesList">#include "<a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/codegen/include/llvm/codegen/globalisel/regbankselect-h">llvm/CodeGen/GlobalISel/RegBankSelect.h</a>"
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
<td class="doxyMemberIndexItemName" align="left" valign="top">Mode { <a href="#a033277264e702883c8bbf13871247a84">...</a> }</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>List of the modes supported by the <a href="/web-llvm/docs/api/classes/llvm/regbankselect">RegBankSelect</a> pass. <a href="#a033277264e702883c8bbf13871247a84">More...</a></p>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a550b3f084bfcea7b97658b4584ac4809">RegBankSelect</a> (Mode RunningMode=Fast)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Create a <a href="/web-llvm/docs/api/classes/llvm/regbankselect">RegBankSelect</a> pass with the specified <span class="doxyComputerOutput">RunningMode</span>. <a href="#a550b3f084bfcea7b97658b4584ac4809">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

</table>

## Public Member Functions Index

<table class="doxyMembersIndex">

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/stringref">StringRef</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ad5ce8fb12329f8cc296656bbe1c979e4">getPassName</a> () const override</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>getPassName - Return a nice clean name for a pass. <a href="#ad5ce8fb12329f8cc296656bbe1c979e4">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">void</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a9a6d36010e8ada5ee58eeda765414a89">getAnalysisUsage</a> (AnalysisUsage &amp;AU) const override</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>getAnalysisUsage - Subclasses that override getAnalysisUsage must call this. <a href="#a9a6d36010e8ada5ee58eeda765414a89">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/machinefunctionproperties">MachineFunctionProperties</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a4f33cb36edf1eebe70860431e8ce5cf9">getRequiredProperties</a> () const override</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/machinefunctionproperties">MachineFunctionProperties</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a32e55cc7580b5fb9e05ff84001d5fd1a">getSetProperties</a> () const override</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/machinefunctionproperties">MachineFunctionProperties</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a2c817913c3f5dbcf0c09a97e0bbedcbb">getClearedProperties</a> () const override</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a04620d87783d98e60cdfcaf04f783f47">checkFunctionIsLegal</a> (MachineFunction &amp;MF) const</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p><a href="/web-llvm/docs/api/namespaces/llvm/check">Check</a> that our input is fully legal: we require the function to have the Legalized property, so it should be. <a href="#a04620d87783d98e60cdfcaf04f783f47">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">bool</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a6b0bf1d2a5eba4af2825113954bb846f">assignRegisterBanks</a> (MachineFunction &amp;MF)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Walk through <span class="doxyComputerOutput">MF</span> and assign a register bank to every virtual register that are still mapped to nothing. <a href="#a6b0bf1d2a5eba4af2825113954bb846f">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">bool</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ae245b9ebf2973a3e982ccd16c9bf93f1">runOnMachineFunction</a> (MachineFunction &amp;MF) override</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>runOnMachineFunction - This method must be overloaded to perform the desired machine code transformation or analysis. <a href="#ae245b9ebf2973a3e982ccd16c9bf93f1">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

</table>

## Protected Member Functions Index

<table class="doxyMembersIndex">

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">bool</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a6553ca5670588f279c72f84d46b05033">assignInstr</a> (MachineInstr &amp;MI)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Assign the register bank of each operand of <span class="doxyComputerOutput">MI</span>. <a href="#a6553ca5670588f279c72f84d46b05033">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">void</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a6f7e57c8c003253b7da93520af8ef8c2">init</a> (MachineFunction &amp;MF)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Initialize the field members using <span class="doxyComputerOutput">MF</span>. <a href="#a6f7e57c8c003253b7da93520af8ef8c2">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">bool</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ac00dc73d1e42ba9d0e4f906e8b4edfd8">assignmentMatch</a> (Register Reg, const RegisterBankInfo::ValueMapping &amp;ValMapping, bool &amp;OnlyAssign) const</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p><a href="/web-llvm/docs/api/namespaces/llvm/check">Check</a> if <span class="doxyComputerOutput">Reg</span> is already assigned what is described by <span class="doxyComputerOutput">ValMapping</span>. <a href="#ac00dc73d1e42ba9d0e4f906e8b4edfd8">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">bool</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ac8d8bb4999d968e0efc9555c2b178a83">repairReg</a> (MachineOperand &amp;MO, const RegisterBankInfo::ValueMapping &amp;ValMapping, RegBankSelect::RepairingPlacement &amp;RepairPt, const iterator_range&lt; SmallVectorImpl&lt; Register &gt;::const_iterator &gt; &amp;NewVRegs)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Insert repairing code for <span class="doxyComputerOutput">Reg</span> as specified by <span class="doxyComputerOutput">ValMapping</span>. <a href="#ac8d8bb4999d968e0efc9555c2b178a83">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">uint64_t</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ac3cfa17f907e7258d898433ddfeb3fbf">getRepairCost</a> (const MachineOperand &amp;MO, const RegisterBankInfo::ValueMapping &amp;ValMapping) const</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Return the cost of the instruction needed to map <span class="doxyComputerOutput">MO</span> to <span class="doxyComputerOutput">ValMapping</span>. <a href="#ac3cfa17f907e7258d898433ddfeb3fbf">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/registerbankinfo/instructionmapping">RegisterBankInfo::InstructionMapping</a> &amp;</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a4dd660f230b1343ae79f15573d7da3d4">findBestMapping</a> (MachineInstr &amp;MI, RegisterBankInfo::InstructionMappings &amp;PossibleMappings, SmallVectorImpl&lt; RepairingPlacement &gt; &amp;RepairPts)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Find the best mapping for <span class="doxyComputerOutput">MI</span> from <span class="doxyComputerOutput">PossibleMappings</span>. <a href="#a4dd660f230b1343ae79f15573d7da3d4">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/regbankselect/mappingcost">MappingCost</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ac7d08af4bb81846173b6186f568fcc8b">computeMapping</a> (MachineInstr &amp;MI, const RegisterBankInfo::InstructionMapping &amp;InstrMapping, SmallVectorImpl&lt; RepairingPlacement &gt; &amp;RepairPts, const MappingCost *BestCost=nullptr)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Compute the cost of mapping <span class="doxyComputerOutput">MI</span> with <span class="doxyComputerOutput">InstrMapping</span> and compute the repairing placement for such mapping in <span class="doxyComputerOutput">RepairPts</span>. <a href="#ac7d08af4bb81846173b6186f568fcc8b">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">void</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a781bc33cca080506ba19a20d66c1c255">tryAvoidingSplit</a> (RegBankSelect::RepairingPlacement &amp;RepairPt, const MachineOperand &amp;MO, const RegisterBankInfo::ValueMapping &amp;ValMapping) const</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>When <span class="doxyComputerOutput">RepairPt</span> involves splitting to repair <span class="doxyComputerOutput">MO</span> for the given <span class="doxyComputerOutput">ValMapping</span>, try to change the way we repair such that the splitting is not required anymore. <a href="#a781bc33cca080506ba19a20d66c1c255">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">bool</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#afc5c7be6a4fbeb70b07dde19d8ebc2fd">applyMapping</a> (MachineInstr &amp;MI, const RegisterBankInfo::InstructionMapping &amp;InstrMapping, SmallVectorImpl&lt; RepairingPlacement &gt; &amp;RepairPts)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Apply <span class="doxyComputerOutput">Mapping</span> to <span class="doxyComputerOutput">MI</span>. <a href="#afc5c7be6a4fbeb70b07dde19d8ebc2fd">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

</table>

## Protected Member Attributes Index

<table class="doxyMembersIndex">

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/registerbankinfo">RegisterBankInfo</a> *</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#afa42d1c7970f30d2fa388d5399348001">RBI</a> = nullptr</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Interface to the target lowering info related to register banks. <a href="#afa42d1c7970f30d2fa388d5399348001">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/machineregisterinfo">MachineRegisterInfo</a> *</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ad8501c8e8cf2d5ffaa86880f57cd4569">MRI</a> = nullptr</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>MRI contains all the register class/bank information that this pass uses and updates. <a href="#ad8501c8e8cf2d5ffaa86880f57cd4569">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/targetregisterinfo">TargetRegisterInfo</a> *</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a98f7afadeec4309cbce64ca040635c04">TRI</a> = nullptr</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Information on the register classes for the current function. <a href="#a98f7afadeec4309cbce64ca040635c04">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/machineblockfrequencyinfo">MachineBlockFrequencyInfo</a> *</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a229ce6916aecf746e69143476a1e5686">MBFI</a> = nullptr</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Get the frequency of blocks. <a href="#a229ce6916aecf746e69143476a1e5686">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/machinebranchprobabilityinfo">MachineBranchProbabilityInfo</a> *</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ab5b60d048f9e03018f15f3730cb24921">MBPI</a> = nullptr</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Get the frequency of the edges. <a href="#ab5b60d048f9e03018f15f3730cb24921">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">std::unique_ptr&lt; <a href="/web-llvm/docs/api/classes/llvm/machineoptimizationremarkemitter">MachineOptimizationRemarkEmitter</a> &gt;</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#afc036a279f48923ec0077a63d975e158">MORE</a></td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Current optimization remark emitter. Used to report failures. <a href="#afc036a279f48923ec0077a63d975e158">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/machineirbuilder">MachineIRBuilder</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a1a75a71e05fa8fbc53f9c4437dafef20">MIRBuilder</a></td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Helper class used for every code morphing. <a href="#a1a75a71e05fa8fbc53f9c4437dafef20">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="#a033277264e702883c8bbf13871247a84">Mode</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a32ef3eb67c8ddb568ebc316b4e56bd27">OptMode</a></td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Optimization mode of the pass. <a href="#a32ef3eb67c8ddb568ebc316b4e56bd27">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/targetpassconfig">TargetPassConfig</a> *</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ae2b9166b734338bf10060074564467a0">TPC</a></td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Current target configuration. Controls how the pass handles errors. <a href="#ae2b9166b734338bf10060074564467a0">More...</a></p>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a18a280ae37dbd3b58a04012da318b687">ID</a> = 0</td>
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

<p>This pass implements the reg bank selector pass used in the GlobalISel pipeline.</p>


<p>At the end of this pass, all register operands have been assigned</p>


<p>Definition at line 91 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/codegen/include/llvm/codegen/globalisel/regbankselect-h">RegBankSelect.h</a>.</p>


<div class="doxySectionDef">

## Enumerations

### Mode {#a033277264e702883c8bbf13871247a84}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">enum llvm::RegBankSelect::Mode </td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>List of the modes supported by the <a href="/web-llvm/docs/api/classes/llvm/regbankselect">RegBankSelect</a> pass.</p>

<dl class="doxyEnumList">
<dt class="doxyEnumTableTitle">Enumeration values</dt>
<dd>
<table class="doxyEnumTable">

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">Fast<a id="a033277264e702883c8bbf13871247a84a764570eb91457744372935b426a1a397"></a></td>
<td class="doxyEnumItemDescription">Assign the register banks as fast as possible (default)</td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">Greedy<a id="a033277264e702883c8bbf13871247a84a9c9b16f1f748485bf3383411cca0bfa3"></a></td>
<td class="doxyEnumItemDescription">Greedily minimize the cost of assigning register banks</td>
</tr>

</table>
</dd>
</dl>

<p>Definition at line 96 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/codegen/include/llvm/codegen/globalisel/regbankselect-h">RegBankSelect.h</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Public Constructors

### RegBankSelect() {#a550b3f084bfcea7b97658b4584ac4809}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">llvm::RegBankSelect::RegBankSelect (<a href="#a033277264e702883c8bbf13871247a84">Mode</a> RunningMode=<a href="#a033277264e702883c8bbf13871247a84a764570eb91457744372935b426a1a397">Fast</a>)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Create a <a href="/web-llvm/docs/api/classes/llvm/regbankselect">RegBankSelect</a> pass with the specified <span class="doxyComputerOutput">RunningMode</span>.</p>

<p>Definition at line 620 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/codegen/include/llvm/codegen/globalisel/regbankselect-h">RegBankSelect.h</a>.</p>


<p>Reference <a href="#a033277264e702883c8bbf13871247a84a764570eb91457744372935b426a1a397">Fast</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Public Member Functions

### assignRegisterBanks() {#a6b0bf1d2a5eba4af2825113954bb846f}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool RegBankSelect::assignRegisterBanks (<a href="/web-llvm/docs/api/classes/llvm/machinefunction">MachineFunction</a> &amp; MF)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Walk through <span class="doxyComputerOutput">MF</span> and assign a register bank to every virtual register that are still mapped to nothing.</p>


<p>The target needs to provide a <a href="/web-llvm/docs/api/classes/llvm/registerbankinfo">RegisterBankInfo</a> and in particular override <a href="/web-llvm/docs/api/classes/llvm/registerbankinfo/#a3f495e9cf115e5d32f21d729c46a484e">RegisterBankInfo::getInstrMapping</a>.</p>


<p>Simplified algo:</p>


<div class="doxyProgramListing">

<div class="doxyCodeLine"><span class="doxyNoLineNumber">&nbsp;</span><span class="doxyLineContent"><span class="doxyHighlight"><a href="#afa42d1c7970f30d2fa388d5399348001">RBI</a> = MF.subtarget.getRegBankInfo()</span></span></div>
<div class="doxyCodeLine"><span class="doxyNoLineNumber">&nbsp;</span><span class="doxyLineContent"><span class="doxyHighlight"><a href="#a1a75a71e05fa8fbc53f9c4437dafef20">MIRBuilder</a>.setMF(MF)</span></span></div>
<div class="doxyCodeLine"><span class="doxyNoLineNumber">&nbsp;</span><span class="doxyLineContent"><span class="doxyHighlightKeywordFlow">for each</span><span class="doxyHighlight"> bb in MF</span></span></div>
<div class="doxyCodeLine"><span class="doxyNoLineNumber">&nbsp;</span><span class="doxyLineContent"><span class="doxyHighlight">  </span><span class="doxyHighlightKeywordFlow">for each</span><span class="doxyHighlight"> inst in bb</span></span></div>
<div class="doxyCodeLine"><span class="doxyNoLineNumber">&nbsp;</span><span class="doxyLineContent"><span class="doxyHighlight">    <a href="#a1a75a71e05fa8fbc53f9c4437dafef20">MIRBuilder</a>.setInstr(inst)</span></span></div>
<div class="doxyCodeLine"><span class="doxyNoLineNumber">&nbsp;</span><span class="doxyLineContent"><span class="doxyHighlight">    MappingCosts = <a href="#afa42d1c7970f30d2fa388d5399348001">RBI</a>.getMapping(inst);</span></span></div>
<div class="doxyCodeLine"><span class="doxyNoLineNumber">&nbsp;</span><span class="doxyLineContent"><span class="doxyHighlight">    Idx = findIdxOfMinCost(MappingCosts)</span></span></div>
<div class="doxyCodeLine"><span class="doxyNoLineNumber">&nbsp;</span><span class="doxyLineContent"><span class="doxyHighlight">    CurRegBank = MappingCosts[Idx].RegBank</span></span></div>
<div class="doxyCodeLine"><span class="doxyNoLineNumber">&nbsp;</span><span class="doxyLineContent"><span class="doxyHighlight">    <a href="#ad8501c8e8cf2d5ffaa86880f57cd4569">MRI</a>.setRegBank(inst.getOperand(0).getReg(), CurRegBank)</span></span></div>
<div class="doxyCodeLine"><span class="doxyNoLineNumber">&nbsp;</span><span class="doxyLineContent"><span class="doxyHighlight">    </span><span class="doxyHighlightKeywordFlow">for each</span><span class="doxyHighlight"> argument in inst</span></span></div>
<div class="doxyCodeLine"><span class="doxyNoLineNumber">&nbsp;</span><span class="doxyLineContent"><span class="doxyHighlight">      </span><span class="doxyHighlightKeywordFlow">if</span><span class="doxyHighlight"> (CurRegBank != argument.RegBank)</span></span></div>
<div class="doxyCodeLine"><span class="doxyNoLineNumber">&nbsp;</span><span class="doxyLineContent"><span class="doxyHighlight">        ArgReg = argument.getReg()</span></span></div>
<div class="doxyCodeLine"><span class="doxyNoLineNumber">&nbsp;</span><span class="doxyLineContent"><span class="doxyHighlight">        Tmp = <a href="#ad8501c8e8cf2d5ffaa86880f57cd4569">MRI</a>.createNewVirtual(<a href="#ad8501c8e8cf2d5ffaa86880f57cd4569">MRI</a>.getSize(ArgReg), CurRegBank)</span></span></div>
<div class="doxyCodeLine"><span class="doxyNoLineNumber">&nbsp;</span><span class="doxyLineContent"><span class="doxyHighlight">        <a href="#a1a75a71e05fa8fbc53f9c4437dafef20">MIRBuilder</a>.buildInstr(COPY, Tmp, ArgReg)</span></span></div>
<div class="doxyCodeLine"><span class="doxyNoLineNumber">&nbsp;</span><span class="doxyLineContent"><span class="doxyHighlight">        inst.getOperand(argument.getOperandNo()).setReg(Tmp)</span></span></div>

</div>


<p>Declaration at line 671 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/codegen/include/llvm/codegen/globalisel/regbankselect-h">RegBankSelect.h</a>, definition at line 681 of file <a href="/web-llvm/docs/api/files/lib/lib/codegen/lib/codegen/globalisel/regbankselect-cpp">RegBankSelect.cpp</a>.</p>


<p>References <a href="#a6553ca5670588f279c72f84d46b05033">assignInstr</a>, <a href="/web-llvm/docs/api/classes/llvm/smallvectortemplatecommon/#ad9a3c7bc26b130377bbafc170b5f88a2">llvm::SmallVectorTemplateCommon&lt; T, typename &gt;::empty</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#ab3aae92be65f5f16f806ad48d474027e">llvm::isTargetSpecificOpcode</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#acc7cb42b6f860b105a2da0efa01ed0ce">llvm::make_pointer_range</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/arm/armslshardening-cpp/#a5958512eae2979bd2eb383977996a600">MBB</a>, <a href="/web-llvm/docs/api/files/lib/lib/codegen/lib/codegen/globalisel/irtranslator-cpp/#abe44dfdea65b4f7e11e0a608ab708b76">MI</a>, <a href="#a1a75a71e05fa8fbc53f9c4437dafef20">MIRBuilder</a>, <a href="#afc036a279f48923ec0077a63d975e158">MORE</a>, <a href="/web-llvm/docs/api/classes/llvm/smallvectorimpl/#a0c8ffe664a36e30d49c84d0aded2fe08">llvm::SmallVectorImpl&lt; T &gt;::pop_back_val</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a7b804856a2e313abeef6f32c3c6f61eb">llvm::reportGISelFailure</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a6b0ac1fa4f05de76413c5e0ca6334035">llvm::reverse</a> and <a href="#ae2b9166b734338bf10060074564467a0">TPC</a>.</p>


<p>Referenced by <a href="#ae245b9ebf2973a3e982ccd16c9bf93f1">runOnMachineFunction</a>.</p>

</div>
</div>

### checkFunctionIsLegal() {#a04620d87783d98e60cdfcaf04f783f47}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool RegBankSelect::checkFunctionIsLegal (<a href="/web-llvm/docs/api/classes/llvm/machinefunction">MachineFunction</a> &amp; MF)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p><a href="/web-llvm/docs/api/namespaces/llvm/check">Check</a> that our input is fully legal: we require the function to have the Legalized property, so it should be.</p>


<p>FIXME: This should be in the MachineVerifier.</p>


<p>Declaration at line 646 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/codegen/include/llvm/codegen/globalisel/regbankselect-h">RegBankSelect.h</a>, definition at line 721 of file <a href="/web-llvm/docs/api/files/lib/lib/codegen/lib/codegen/globalisel/regbankselect-cpp">RegBankSelect.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/namespaces/llvm/#a6a02a3f943db168fa421df8241f843d1">llvm::DisableGISelLegalityCheck</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a86d5a37f432a0567b98815a74f54dd1e">llvm::machineFunctionIsIllegal</a>, <a href="/web-llvm/docs/api/files/lib/lib/codegen/lib/codegen/globalisel/irtranslator-cpp/#abe44dfdea65b4f7e11e0a608ab708b76">MI</a>, <a href="#afc036a279f48923ec0077a63d975e158">MORE</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a7b804856a2e313abeef6f32c3c6f61eb">llvm::reportGISelFailure</a> and <a href="#ae2b9166b734338bf10060074564467a0">TPC</a>.</p>


<p>Referenced by <a href="#ae245b9ebf2973a3e982ccd16c9bf93f1">runOnMachineFunction</a>.</p>

</div>
</div>

### getAnalysisUsage() {#a9a6d36010e8ada5ee58eeda765414a89}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void RegBankSelect::getAnalysisUsage (<a href="/web-llvm/docs/api/classes/llvm/analysisusage">AnalysisUsage</a> &amp; AU)</td>
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

<p>getAnalysisUsage - Subclasses that override getAnalysisUsage must call this.</p>


<p>For MachineFunctionPasses, calling AU.preservesCFG() indicates that the pass does not modify the <a href="/web-llvm/docs/api/classes/llvm/machinebasicblock">MachineBasicBlock</a> CFG.</p>


<p>Declaration at line 624 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/codegen/include/llvm/codegen/globalisel/regbankselect-h">RegBankSelect.h</a>, definition at line 98 of file <a href="/web-llvm/docs/api/files/lib/lib/codegen/lib/codegen/globalisel/regbankselect-cpp">RegBankSelect.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/classes/llvm/analysisusage/#ae0adcccca08fb686c9ce00f9397b660c">llvm::AnalysisUsage::addRequired</a>, <a href="#a033277264e702883c8bbf13871247a84a764570eb91457744372935b426a1a397">Fast</a>, <a href="/web-llvm/docs/api/classes/llvm/machinefunctionpass/#a864fd57b4304ef933b3281d0ef85a88e">llvm::MachineFunctionPass::getAnalysisUsage</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#aa353f9585311abf1b6f698049f5a29b7">llvm::getSelectionDAGFallbackAnalysisUsage</a> and <a href="#a32ef3eb67c8ddb568ebc316b4e56bd27">OptMode</a>.</p>

</div>
</div>

### getClearedProperties() {#a2c817913c3f5dbcf0c09a97e0bbedcbb}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">MachineFunctionProperties llvm::RegBankSelect::getClearedProperties ()</td>
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



<p>Definition at line 637 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/codegen/include/llvm/codegen/globalisel/regbankselect-h">RegBankSelect.h</a>.</p>


<p>References <a href="/web-llvm/docs/api/classes/llvm/machinefunctionproperties/#ad85237c6c667e4713efe8921e9c32ac1a76eece0bfd57256980609b66faaef22c">llvm::MachineFunctionProperties::NoPHIs</a> and <a href="/web-llvm/docs/api/classes/llvm/machinefunctionproperties/#aa7780563d7ca260d0ae67d957b56427f">llvm::MachineFunctionProperties::set</a>.</p>

</div>
</div>

### getPassName() {#ad5ce8fb12329f8cc296656bbe1c979e4}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">StringRef llvm::RegBankSelect::getPassName ()</td>
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


<p>Definition at line 622 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/codegen/include/llvm/codegen/globalisel/regbankselect-h">RegBankSelect.h</a>.</p>

</div>
</div>

### getRequiredProperties() {#a4f33cb36edf1eebe70860431e8ce5cf9}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">MachineFunctionProperties llvm::RegBankSelect::getRequiredProperties ()</td>
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



<p>Definition at line 626 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/codegen/include/llvm/codegen/globalisel/regbankselect-h">RegBankSelect.h</a>.</p>


<p>References <a href="/web-llvm/docs/api/classes/llvm/machinefunctionproperties/#ad85237c6c667e4713efe8921e9c32ac1a4fc3b812627e58da17a703f73013db96">llvm::MachineFunctionProperties::IsSSA</a>, <a href="/web-llvm/docs/api/classes/llvm/machinefunctionproperties/#ad85237c6c667e4713efe8921e9c32ac1aefa6e814420e5fc1dfad353869159a37">llvm::MachineFunctionProperties::Legalized</a> and <a href="/web-llvm/docs/api/classes/llvm/machinefunctionproperties/#aa7780563d7ca260d0ae67d957b56427f">llvm::MachineFunctionProperties::set</a>.</p>

</div>
</div>

### getSetProperties() {#a32e55cc7580b5fb9e05ff84001d5fd1a}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">MachineFunctionProperties llvm::RegBankSelect::getSetProperties ()</td>
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



<p>Definition at line 632 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/codegen/include/llvm/codegen/globalisel/regbankselect-h">RegBankSelect.h</a>.</p>


<p>References <a href="/web-llvm/docs/api/classes/llvm/machinefunctionproperties/#ad85237c6c667e4713efe8921e9c32ac1a062927be2f9d18d9995e64b0779c3dcf">llvm::MachineFunctionProperties::RegBankSelected</a> and <a href="/web-llvm/docs/api/classes/llvm/machinefunctionproperties/#aa7780563d7ca260d0ae67d957b56427f">llvm::MachineFunctionProperties::set</a>.</p>

</div>
</div>

### runOnMachineFunction() {#ae245b9ebf2973a3e982ccd16c9bf93f1}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool RegBankSelect::runOnMachineFunction (<a href="/web-llvm/docs/api/classes/llvm/machinefunction">MachineFunction</a> &amp; MF)</td>
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

<p>Declaration at line 673 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/codegen/include/llvm/codegen/globalisel/regbankselect-h">RegBankSelect.h</a>, definition at line 734 of file <a href="/web-llvm/docs/api/files/lib/lib/codegen/lib/codegen/globalisel/regbankselect-cpp">RegBankSelect.cpp</a>.</p>


<p>References <a href="#a6b0bf1d2a5eba4af2825113954bb846f">assignRegisterBanks</a>, <a href="#a04620d87783d98e60cdfcaf04f783f47">checkFunctionIsLegal</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a7c46c742c31be54870e2038048e6b391">llvm::dbgs</a>, <a href="/web-llvm/docs/api/files/lib/lib/support/md5-cpp/#a96d73bbd7af15cb1fc38c3f4a3bd82e9">F</a>, <a href="/web-llvm/docs/api/classes/llvm/machinefunctionproperties/#ad85237c6c667e4713efe8921e9c32ac1a8014afd87e04236365d1796e38bc15f5">llvm::MachineFunctionProperties::FailedISel</a>, <a href="#a033277264e702883c8bbf13871247a84a764570eb91457744372935b426a1a397">Fast</a>, <a href="/web-llvm/docs/api/classes/llvm/machinefunction/#a977ddce262de45c645be23d951066351">llvm::MachineFunction::getFunction</a>, <a href="/web-llvm/docs/api/classes/llvm/machinefunction/#a3d142c9e7c066059e15232c56dec9e2e">llvm::MachineFunction::getName</a>, <a href="/web-llvm/docs/api/classes/llvm/machinefunction/#ac1f888bba00f32cb4f9a0010c958f397">llvm::MachineFunction::getProperties</a>, <a href="/web-llvm/docs/api/classes/llvm/machinefunctionproperties/#aacef05f16d3e71703f08bb4677e1d7a2">llvm::MachineFunctionProperties::hasProperty</a>, <a href="#a6f7e57c8c003253b7da93520af8ef8c2">init</a>, <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/support/debug-h/#a196897517069dda1bdb549e24468f7d7">LLVM_DEBUG</a> and <a href="#a32ef3eb67c8ddb568ebc316b4e56bd27">OptMode</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Protected Member Functions

### applyMapping() {#afc5c7be6a4fbeb70b07dde19d8ebc2fd}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool RegBankSelect::applyMapping (<a href="/web-llvm/docs/api/classes/llvm/machineinstr">MachineInstr</a> &amp; MI, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/registerbankinfo/instructionmapping">RegisterBankInfo::InstructionMapping</a> &amp; InstrMapping, <a href="/web-llvm/docs/api/classes/llvm/smallvectorimpl">SmallVectorImpl</a>&lt; <a href="/web-llvm/docs/api/classes/llvm/regbankselect/repairingplacement">RepairingPlacement</a> &gt; &amp; RepairPts)</td>
</tr>
</table>
</td>
<td class="doxyMemberLabelsRight">
<span class="doxyMemberLabels">
<span class="doxyMemberLabel protected">protected</span>
</span>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Apply <span class="doxyComputerOutput">Mapping</span> to <span class="doxyComputerOutput">MI</span>.</p>


<p><span class="doxyComputerOutput">RepairPts</span> represents the different mapping action that need to happen for the mapping to be applied.</p>


<dl class="doxySectionUser">
<dt>Returns</dt>
<dd><p>True if the mapping was applied sucessfully, false otherwise.</p></dd>
</dl>


<p>Declaration at line 614 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/codegen/include/llvm/codegen/globalisel/regbankselect-h">RegBankSelect.h</a>, definition at line 588 of file <a href="/web-llvm/docs/api/files/lib/lib/codegen/lib/codegen/globalisel/regbankselect-cpp">RegBankSelect.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/silowercontrolflow-cpp/#a4868c5d81c5ccc98c47aeab6244346a0">assert</a>, <a href="/web-llvm/docs/api/structs/llvm/registerbankinfo/valuemapping/#ae3003e8b89a759af674cb22ed2b67d2e">llvm::RegisterBankInfo::ValueMapping::BreakDown</a>, <a href="/web-llvm/docs/api/classes/llvm/registerbankinfo/operandsmapper/#a6817453b853abea76fab37803ade6ef4">llvm::RegisterBankInfo::OperandsMapper::createVRegs</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a7c46c742c31be54870e2038048e6b391">llvm::dbgs</a>, <a href="/web-llvm/docs/api/classes/llvm/machineoperand/#ac0035d7c1c860501c877c20e6e93297b">llvm::MachineOperand::getReg</a>, <a href="/web-llvm/docs/api/classes/llvm/registerbankinfo/operandsmapper/#af23faa9ae580c4a451da006e3567b297">llvm::RegisterBankInfo::OperandsMapper::getVRegs</a>, <a href="/web-llvm/docs/api/classes/llvm/regbankselect/repairingplacement/#a66bdd17ee82024ea0ccbb0288b379dd6a98e66b30e93d741af07a3fefeb66ab1b">llvm::RegBankSelect::RepairingPlacement::Impossible</a>, <a href="/web-llvm/docs/api/classes/llvm/regbankselect/repairingplacement/#a66bdd17ee82024ea0ccbb0288b379dd6a07b4fac858ad8fc2c4d9bdc7acd6e195">llvm::RegBankSelect::RepairingPlacement::Insert</a>, <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/support/debug-h/#a196897517069dda1bdb549e24468f7d7">LLVM_DEBUG</a>, <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/support/errorhandling-h/#ace243f5c25697a1107cce46626b3dc94">llvm_unreachable</a>, <a href="/web-llvm/docs/api/files/lib/lib/codegen/lib/codegen/globalisel/irtranslator-cpp/#abe44dfdea65b4f7e11e0a608ab708b76">MI</a>, <a href="#a1a75a71e05fa8fbc53f9c4437dafef20">MIRBuilder</a>, <a href="#ad8501c8e8cf2d5ffaa86880f57cd4569">MRI</a>, <a href="/web-llvm/docs/api/classes/llvm/regbankselect/repairingplacement/#a66bdd17ee82024ea0ccbb0288b379dd6a1b5edfd2f0ed3f87981ab15c425b0165">llvm::RegBankSelect::RepairingPlacement::None</a>, <a href="/web-llvm/docs/api/structs/llvm/registerbankinfo/valuemapping/#a83b9746150eb1c8820d65bca34b8d950">llvm::RegisterBankInfo::ValueMapping::NumBreakDowns</a>, <a href="#afa42d1c7970f30d2fa388d5399348001">RBI</a>, <a href="/web-llvm/docs/api/classes/llvm/regbankselect/repairingplacement/#a66bdd17ee82024ea0ccbb0288b379dd6a756e97b1942ca89260909cfdfb64b957">llvm::RegBankSelect::RepairingPlacement::Reassign</a>, <a href="/web-llvm/docs/api/structs/llvm/registerbankinfo/partialmapping/#ae78f517f813c1983db970736287379e1">llvm::RegisterBankInfo::PartialMapping::RegBank</a> and <a href="#ac8d8bb4999d968e0efc9555c2b178a83">repairReg</a>.</p>


<p>Referenced by <a href="#a6553ca5670588f279c72f84d46b05033">assignInstr</a>.</p>

</div>
</div>

### assignInstr() {#a6553ca5670588f279c72f84d46b05033}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool RegBankSelect::assignInstr (<a href="/web-llvm/docs/api/classes/llvm/machineinstr">MachineInstr</a> &amp; MI)</td>
</tr>
</table>
</td>
<td class="doxyMemberLabelsRight">
<span class="doxyMemberLabels">
<span class="doxyMemberLabel protected">protected</span>
</span>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Assign the register bank of each operand of <span class="doxyComputerOutput">MI</span>.</p>


<dl class="doxySectionUser">
<dt>Returns</dt>
<dd><p>True on success, false otherwise.</p></dd>
</dl>


<p>Declaration at line 518 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/codegen/include/llvm/codegen/globalisel/regbankselect-h">RegBankSelect.h</a>, definition at line 633 of file <a href="/web-llvm/docs/api/files/lib/lib/codegen/lib/codegen/globalisel/regbankselect-cpp">RegBankSelect.cpp</a>.</p>


<p>References <a href="#afc5c7be6a4fbeb70b07dde19d8ebc2fd">applyMapping</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/silowercontrolflow-cpp/#a4868c5d81c5ccc98c47aeab6244346a0">assert</a>, <a href="#ac7d08af4bb81846173b6186f568fcc8b">computeMapping</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a7c46c742c31be54870e2038048e6b391">llvm::dbgs</a>, <a href="/web-llvm/docs/api/classes/llvm/smallvectortemplatecommon/#ad9a3c7bc26b130377bbafc170b5f88a2">llvm::SmallVectorTemplateCommon&lt; T, typename &gt;::empty</a>, <a href="#a033277264e702883c8bbf13871247a84a764570eb91457744372935b426a1a397">Fast</a>, <a href="#a4dd660f230b1343ae79f15573d7da3d4">findBestMapping</a>, <a href="/web-llvm/docs/api/classes/llvm/regbankselect/mappingcost/#a7e2284f2c68e1187be7ed8c89a0d6f88">llvm::RegBankSelect::MappingCost::ImpossibleCost</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a51226361b4778741a8b60487c293d43a">llvm::isPreISelGenericOptimizationHint</a>, <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/support/debug-h/#a196897517069dda1bdb549e24468f7d7">LLVM_DEBUG</a>, <a href="/web-llvm/docs/api/files/lib/lib/codegen/lib/codegen/globalisel/irtranslator-cpp/#abe44dfdea65b4f7e11e0a608ab708b76">MI</a>, <a href="#ad8501c8e8cf2d5ffaa86880f57cd4569">MRI</a>, <a href="#a32ef3eb67c8ddb568ebc316b4e56bd27">OptMode</a>, <a href="#afa42d1c7970f30d2fa388d5399348001">RBI</a>, <a href="#a98f7afadeec4309cbce64ca040635c04">TRI</a> and <a href="/web-llvm/docs/api/classes/llvm/registerbankinfo/instructionmapping/#a89e479535d719fb4ec8904104ec1e8ae">llvm::RegisterBankInfo::InstructionMapping::verify</a>.</p>


<p>Referenced by <a href="#a6b0bf1d2a5eba4af2825113954bb846f">assignRegisterBanks</a>.</p>

</div>
</div>

### assignmentMatch() {#ac00dc73d1e42ba9d0e4f906e8b4edfd8}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool RegBankSelect::assignmentMatch (<a href="/web-llvm/docs/api/classes/llvm/register">Register</a> Reg, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/structs/llvm/registerbankinfo/valuemapping">RegisterBankInfo::ValueMapping</a> &amp; ValMapping, bool &amp; OnlyAssign)</td>
</tr>
</table>
</td>
<td class="doxyMemberLabelsRight">
<span class="doxyMemberLabels">
<span class="doxyMemberLabel protected">protected</span>
</span>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p><a href="/web-llvm/docs/api/namespaces/llvm/check">Check</a> if <span class="doxyComputerOutput">Reg</span> is already assigned what is described by <span class="doxyComputerOutput">ValMapping</span>.</p>


<p><span class="doxyComputerOutput">OnlyAssign</span> == true means that <span class="doxyComputerOutput">Reg</span> just needs to be assigned a register bank. I.e., no repairing is necessary to have the assignment match.</p>


<p>Declaration at line 527 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/codegen/include/llvm/codegen/globalisel/regbankselect-h">RegBankSelect.h</a>, definition at line 110 of file <a href="/web-llvm/docs/api/files/lib/lib/codegen/lib/codegen/globalisel/regbankselect-cpp">RegBankSelect.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/silowercontrolflow-cpp/#a4868c5d81c5ccc98c47aeab6244346a0">assert</a>, <a href="/web-llvm/docs/api/structs/llvm/registerbankinfo/valuemapping/#ae3003e8b89a759af674cb22ed2b67d2e">llvm::RegisterBankInfo::ValueMapping::BreakDown</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a7c46c742c31be54870e2038048e6b391">llvm::dbgs</a>, <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/support/debug-h/#a196897517069dda1bdb549e24468f7d7">LLVM_DEBUG</a>, <a href="#ad8501c8e8cf2d5ffaa86880f57cd4569">MRI</a>, <a href="/web-llvm/docs/api/structs/llvm/registerbankinfo/valuemapping/#a83b9746150eb1c8820d65bca34b8d950">llvm::RegisterBankInfo::ValueMapping::NumBreakDowns</a>, <a href="#afa42d1c7970f30d2fa388d5399348001">RBI</a>, <a href="/web-llvm/docs/api/structs/llvm/registerbankinfo/partialmapping/#ae78f517f813c1983db970736287379e1">llvm::RegisterBankInfo::PartialMapping::RegBank</a> and <a href="#a98f7afadeec4309cbce64ca040635c04">TRI</a>.</p>


<p>Referenced by <a href="#ac7d08af4bb81846173b6186f568fcc8b">computeMapping</a>.</p>

</div>
</div>

### computeMapping() {#ac7d08af4bb81846173b6186f568fcc8b}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">RegBankSelect::MappingCost RegBankSelect::computeMapping (<a href="/web-llvm/docs/api/classes/llvm/machineinstr">MachineInstr</a> &amp; MI, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/registerbankinfo/instructionmapping">RegisterBankInfo::InstructionMapping</a> &amp; InstrMapping, <a href="/web-llvm/docs/api/classes/llvm/smallvectorimpl">SmallVectorImpl</a>&lt; <a href="/web-llvm/docs/api/classes/llvm/regbankselect/repairingplacement">RepairingPlacement</a> &gt; &amp; RepairPts, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/regbankselect/mappingcost">MappingCost</a> * BestCost=nullptr)</td>
</tr>
</table>
</td>
<td class="doxyMemberLabelsRight">
<span class="doxyMemberLabels">
<span class="doxyMemberLabel protected">protected</span>
</span>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Compute the cost of mapping <span class="doxyComputerOutput">MI</span> with <span class="doxyComputerOutput">InstrMapping</span> and compute the repairing placement for such mapping in <span class="doxyComputerOutput">RepairPts</span>.</p>


<p><span class="doxyComputerOutput">BestCost</span> is used to specify when the cost becomes too high and thus it is not worth computing the RepairPts. Moreover if <span class="doxyComputerOutput">BestCost</span> == nullptr, the mapping cost is actually not computed.</p>


<p>Declaration at line 593 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/codegen/include/llvm/codegen/globalisel/regbankselect-h">RegBankSelect.h</a>, definition at line 443 of file <a href="/web-llvm/docs/api/files/lib/lib/codegen/lib/codegen/globalisel/regbankselect-cpp">RegBankSelect.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/silowercontrolflow-cpp/#a4868c5d81c5ccc98c47aeab6244346a0">assert</a>, <a href="#ac00dc73d1e42ba9d0e4f906e8b4edfd8">assignmentMatch</a>, <a href="/web-llvm/docs/api/classes/llvm/smallvectortemplatecommon/#acd9e771a3296c6b24146955754620557">llvm::SmallVectorTemplateCommon&lt; T, typename &gt;::back</a>, <a href="/web-llvm/docs/api/classes/llvm/regbankselect/repairingplacement/#a39535988981c86b512949745cbfab81c">llvm::RegBankSelect::RepairingPlacement::canMaterialize</a>, <a href="/web-llvm/docs/api/classes/llvm/smallvectorimpl/#aac0ea55010b7b1a301e65a0baea057aa">llvm::SmallVectorImpl&lt; T &gt;::clear</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a7c46c742c31be54870e2038048e6b391">llvm::dbgs</a>, <a href="/web-llvm/docs/api/classes/llvm/smallvectorimpl/#a396fcfee6914c76974b73c3d203da6a5">llvm::SmallVectorImpl&lt; T &gt;::emplace_back</a>, <a href="/web-llvm/docs/api/classes/llvm/registerbankinfo/instructionmapping/#a4c1c4a80c61e8df88647f78ddf6de94e">llvm::RegisterBankInfo::InstructionMapping::getCost</a>, <a href="/web-llvm/docs/api/classes/llvm/registerbankinfo/instructionmapping/#a3548d4f247cf4c364934abd8f59a0483">llvm::RegisterBankInfo::InstructionMapping::getNumOperands</a>, <a href="/web-llvm/docs/api/classes/llvm/machineoperand/#ac0035d7c1c860501c877c20e6e93297b">llvm::MachineOperand::getReg</a>, <a href="#ac3cfa17f907e7258d898433ddfeb3fbf">getRepairCost</a>, <a href="/web-llvm/docs/api/classes/llvm/regbankselect/repairingplacement/#a05dcab804adfa11b36715dddba6c52db">llvm::RegBankSelect::RepairingPlacement::hasSplit</a>, <a href="/web-llvm/docs/api/classes/llvm/regbankselect/mappingcost/#a7e2284f2c68e1187be7ed8c89a0d6f88">llvm::RegBankSelect::MappingCost::ImpossibleCost</a>, <a href="/web-llvm/docs/api/classes/llvm/regbankselect/repairingplacement/#a66bdd17ee82024ea0ccbb0288b379dd6a07b4fac858ad8fc2c4d9bdc7acd6e195">llvm::RegBankSelect::RepairingPlacement::Insert</a>, <a href="/web-llvm/docs/api/classes/llvm/machineoperand/#a4c9594c955fec80c73ddd964b5efd554">llvm::MachineOperand::isReg</a>, <a href="/web-llvm/docs/api/classes/llvm/registerbankinfo/instructionmapping/#af484a43d5e4fa2ff1f1790d06f2ca94d">llvm::RegisterBankInfo::InstructionMapping::isValid</a>, <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/support/debug-h/#a196897517069dda1bdb549e24468f7d7">LLVM_DEBUG</a>, <a href="#a229ce6916aecf746e69143476a1e5686">MBFI</a>, <a href="#ab5b60d048f9e03018f15f3730cb24921">MBPI</a>, <a href="/web-llvm/docs/api/files/lib/lib/codegen/lib/codegen/globalisel/irtranslator-cpp/#abe44dfdea65b4f7e11e0a608ab708b76">MI</a>, <a href="#ad8501c8e8cf2d5ffaa86880f57cd4569">MRI</a>, <a href="/web-llvm/docs/api/classes/llvm/regbankselect/repairingplacement/#a66bdd17ee82024ea0ccbb0288b379dd6a756e97b1942ca89260909cfdfb64b957">llvm::RegBankSelect::RepairingPlacement::Reassign</a>, <a href="#a98f7afadeec4309cbce64ca040635c04">TRI</a> and <a href="#a781bc33cca080506ba19a20d66c1c255">tryAvoidingSplit</a>.</p>


<p>Referenced by <a href="#a6553ca5670588f279c72f84d46b05033">assignInstr</a> and <a href="#a4dd660f230b1343ae79f15573d7da3d4">findBestMapping</a>.</p>

</div>
</div>

### findBestMapping() {#a4dd660f230b1343ae79f15573d7da3d4}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">const RegisterBankInfo::InstructionMapping &amp; RegBankSelect::findBestMapping (<a href="/web-llvm/docs/api/classes/llvm/machineinstr">MachineInstr</a> &amp; MI, <a href="/web-llvm/docs/api/classes/llvm/registerbankinfo/#ac89dbbb6460391f27fb352c20c600769">RegisterBankInfo::InstructionMappings</a> &amp; PossibleMappings, <a href="/web-llvm/docs/api/classes/llvm/smallvectorimpl">SmallVectorImpl</a>&lt; <a href="/web-llvm/docs/api/classes/llvm/regbankselect/repairingplacement">RepairingPlacement</a> &gt; &amp; RepairPts)</td>
</tr>
</table>
</td>
<td class="doxyMemberLabelsRight">
<span class="doxyMemberLabels">
<span class="doxyMemberLabel protected">protected</span>
</span>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Find the best mapping for <span class="doxyComputerOutput">MI</span> from <span class="doxyComputerOutput">PossibleMappings</span>.</p>


<dl class="doxySectionUser">
<dt>Returns</dt>
<dd><p>a reference on the best mapping in <span class="doxyComputerOutput">PossibleMappings</span>.</p></dd>
</dl>


<p>Declaration at line 581 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/codegen/include/llvm/codegen/globalisel/regbankselect-h">RegBankSelect.h</a>, definition at line 289 of file <a href="/web-llvm/docs/api/files/lib/lib/codegen/lib/codegen/globalisel/regbankselect-cpp">RegBankSelect.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/silowercontrolflow-cpp/#a4868c5d81c5ccc98c47aeab6244346a0">assert</a>, <a href="/web-llvm/docs/api/classes/llvm/smallvectortemplatecommon/#a8a045d250952c0867382a9840ee18fdf">llvm::SmallVectorTemplateCommon&lt; T, typename &gt;::begin</a>, <a href="/web-llvm/docs/api/classes/llvm/smallvectorimpl/#aac0ea55010b7b1a301e65a0baea057aa">llvm::SmallVectorImpl&lt; T &gt;::clear</a>, <a href="#ac7d08af4bb81846173b6186f568fcc8b">computeMapping</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a7c46c742c31be54870e2038048e6b391">llvm::dbgs</a>, <a href="/web-llvm/docs/api/classes/llvm/smallvectorimpl/#a396fcfee6914c76974b73c3d203da6a5">llvm::SmallVectorImpl&lt; T &gt;::emplace_back</a>, <a href="/web-llvm/docs/api/classes/llvm/smallvectortemplatecommon/#ad9a3c7bc26b130377bbafc170b5f88a2">llvm::SmallVectorTemplateCommon&lt; T, typename &gt;::empty</a>, <a href="/web-llvm/docs/api/classes/llvm/regbankselect/repairingplacement/#a66bdd17ee82024ea0ccbb0288b379dd6a98e66b30e93d741af07a3fefeb66ab1b">llvm::RegBankSelect::RepairingPlacement::Impossible</a>, <a href="/web-llvm/docs/api/classes/llvm/regbankselect/mappingcost/#a7e2284f2c68e1187be7ed8c89a0d6f88">llvm::RegBankSelect::MappingCost::ImpossibleCost</a>, <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/support/debug-h/#a196897517069dda1bdb549e24468f7d7">LLVM_DEBUG</a>, <a href="/web-llvm/docs/api/files/lib/lib/codegen/lib/codegen/globalisel/irtranslator-cpp/#abe44dfdea65b4f7e11e0a608ab708b76">MI</a>, <a href="#ae2b9166b734338bf10060074564467a0">TPC</a> and <a href="#a98f7afadeec4309cbce64ca040635c04">TRI</a>.</p>


<p>Referenced by <a href="#a6553ca5670588f279c72f84d46b05033">assignInstr</a>.</p>

</div>
</div>

### getRepairCost() {#ac3cfa17f907e7258d898433ddfeb3fbf}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">uint64_t RegBankSelect::getRepairCost (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/machineoperand">MachineOperand</a> &amp; MO, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/structs/llvm/registerbankinfo/valuemapping">RegisterBankInfo::ValueMapping</a> &amp; ValMapping)</td>
</tr>
</table>
</td>
<td class="doxyMemberLabelsRight">
<span class="doxyMemberLabels">
<span class="doxyMemberLabel protected">protected</span>
</span>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Return the cost of the instruction needed to map <span class="doxyComputerOutput">MO</span> to <span class="doxyComputerOutput">ValMapping</span>.</p>


<p>The cost is free of basic block frequencies.</p>


<dl class="doxySectionUser">
<dt>Precondition</dt>
<dd><p>MO.isReg()</p></dd>
</dl>


<dl class="doxySectionUser">
<dt>Precondition</dt>
<dd><p>MO is assigned to a register bank.</p></dd>
</dl>


<dl class="doxySectionUser">
<dt>Precondition</dt>
<dd><p>ValMapping is a valid mapping for MO.</p></dd>
</dl>


<p>Declaration at line 575 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/codegen/include/llvm/codegen/globalisel/regbankselect-h">RegBankSelect.h</a>, definition at line 237 of file <a href="/web-llvm/docs/api/files/lib/lib/codegen/lib/codegen/globalisel/regbankselect-cpp">RegBankSelect.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/silowercontrolflow-cpp/#a4868c5d81c5ccc98c47aeab6244346a0">assert</a>, <a href="/web-llvm/docs/api/structs/llvm/registerbankinfo/valuemapping/#ae3003e8b89a759af674cb22ed2b67d2e">llvm::RegisterBankInfo::ValueMapping::BreakDown</a>, <a href="/web-llvm/docs/api/classes/llvm/machineoperand/#ac0035d7c1c860501c877c20e6e93297b">llvm::MachineOperand::getReg</a>, <a href="/web-llvm/docs/api/classes/llvm/machineoperand/#a75eb135014670ce946e78739cdc9b51b">llvm::MachineOperand::isDef</a>, <a href="/web-llvm/docs/api/classes/llvm/machineoperand/#a4c9594c955fec80c73ddd964b5efd554">llvm::MachineOperand::isReg</a>, <a href="#ad8501c8e8cf2d5ffaa86880f57cd4569">MRI</a>, <a href="/web-llvm/docs/api/structs/llvm/registerbankinfo/valuemapping/#a83b9746150eb1c8820d65bca34b8d950">llvm::RegisterBankInfo::ValueMapping::NumBreakDowns</a>, <a href="#afa42d1c7970f30d2fa388d5399348001">RBI</a>, <a href="/web-llvm/docs/api/structs/llvm/registerbankinfo/partialmapping/#ae78f517f813c1983db970736287379e1">llvm::RegisterBankInfo::PartialMapping::RegBank</a>, <a href="/web-llvm/docs/api/namespaces/std/#ab8424022895aee3e366fb9a32f2883cb">std::swap</a> and <a href="#a98f7afadeec4309cbce64ca040635c04">TRI</a>.</p>


<p>Referenced by <a href="#ac7d08af4bb81846173b6186f568fcc8b">computeMapping</a>.</p>

</div>
</div>

### init() {#a6f7e57c8c003253b7da93520af8ef8c2}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void RegBankSelect::init (<a href="/web-llvm/docs/api/classes/llvm/machinefunction">MachineFunction</a> &amp; MF)</td>
</tr>
</table>
</td>
<td class="doxyMemberLabelsRight">
<span class="doxyMemberLabels">
<span class="doxyMemberLabel protected">protected</span>
</span>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Initialize the field members using <span class="doxyComputerOutput">MF</span>.</p>

<p>Declaration at line 521 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/codegen/include/llvm/codegen/globalisel/regbankselect-h">RegBankSelect.h</a>, definition at line 81 of file <a href="/web-llvm/docs/api/files/lib/lib/codegen/lib/codegen/globalisel/regbankselect-cpp">RegBankSelect.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/silowercontrolflow-cpp/#a4868c5d81c5ccc98c47aeab6244346a0">assert</a>, <a href="#a033277264e702883c8bbf13871247a84a764570eb91457744372935b426a1a397">Fast</a>, <a href="/web-llvm/docs/api/classes/llvm/pass/#a4863e5e463fb79955269fbf7fbf52b80">llvm::Pass::getAnalysis</a>, <a href="/web-llvm/docs/api/classes/llvm/targetsubtargetinfo/#a9768b8e3c00648b38189b95d6603729b">llvm::TargetSubtargetInfo::getRegBankInfo</a>, <a href="/web-llvm/docs/api/classes/llvm/machinefunction/#a810234b6b3d223b7c74a4253fcc5ea5e">llvm::MachineFunction::getRegInfo</a>, <a href="/web-llvm/docs/api/classes/llvm/targetsubtargetinfo/#a43c530c830206ecf5ad3359364634c75">llvm::TargetSubtargetInfo::getRegisterInfo</a>, <a href="/web-llvm/docs/api/classes/llvm/machinefunction/#a3825368aca2bc1550d173660df4da6a6">llvm::MachineFunction::getSubtarget</a>, <a href="#a229ce6916aecf746e69143476a1e5686">MBFI</a>, <a href="#ab5b60d048f9e03018f15f3730cb24921">MBPI</a>, <a href="#a1a75a71e05fa8fbc53f9c4437dafef20">MIRBuilder</a>, <a href="#afc036a279f48923ec0077a63d975e158">MORE</a>, <a href="#ad8501c8e8cf2d5ffaa86880f57cd4569">MRI</a>, <a href="#a32ef3eb67c8ddb568ebc316b4e56bd27">OptMode</a>, <a href="#afa42d1c7970f30d2fa388d5399348001">RBI</a>, <a href="#ae2b9166b734338bf10060074564467a0">TPC</a> and <a href="#a98f7afadeec4309cbce64ca040635c04">TRI</a>.</p>


<p>Referenced by <a href="#ae245b9ebf2973a3e982ccd16c9bf93f1">runOnMachineFunction</a>.</p>

</div>
</div>

### repairReg() {#ac8d8bb4999d968e0efc9555c2b178a83}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool RegBankSelect::repairReg (<a href="/web-llvm/docs/api/classes/llvm/machineoperand">MachineOperand</a> &amp; MO, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/structs/llvm/registerbankinfo/valuemapping">RegisterBankInfo::ValueMapping</a> &amp; ValMapping, <a href="/web-llvm/docs/api/classes/llvm/regbankselect/repairingplacement">RegBankSelect::RepairingPlacement</a> &amp; RepairPt, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/iterator-range">iterator_range</a>&lt; <a href="/web-llvm/docs/api/classes/llvm/smallvectorimpl">SmallVectorImpl</a>&lt; <a href="/web-llvm/docs/api/classes/llvm/register">Register</a> &gt;<a href="/web-llvm/docs/api/classes/llvm/smallvectorimpl">::const_iterator</a> &gt; &amp; NewVRegs)</td>
</tr>
</table>
</td>
<td class="doxyMemberLabelsRight">
<span class="doxyMemberLabels">
<span class="doxyMemberLabel protected">protected</span>
</span>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Insert repairing code for <span class="doxyComputerOutput">Reg</span> as specified by <span class="doxyComputerOutput">ValMapping</span>.</p>


<p>The repairing placement is specified by <span class="doxyComputerOutput">RepairPt</span>. <span class="doxyComputerOutput">NewVRegs</span> contains all the registers required to remap <span class="doxyComputerOutput">Reg</span>. In other words, the number of registers in NewVRegs must be equal to ValMapping.BreakDown.size().</p>


<p>The transformation could be sketched as:</p>


<div class="doxyProgramListing">

<div class="doxyCodeLine"><span class="doxyNoLineNumber">&nbsp;</span><span class="doxyLineContent"><span class="doxyHighlight">... = <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/hexagon/hexagonbittracker-cpp/#a0ee73ba17c3a2cb54752905e99d77357">op</a> <a href="/web-llvm/docs/api/files/lib/lib/codegen/machinesink-cpp/#a359e1ff26f6d466d927a61aae45b05c3">Reg</a></span></span></div>

</div>


<p>Becomes</p>


<div class="doxyProgramListing">

<div class="doxyCodeLine"><span class="doxyNoLineNumber">&nbsp;</span><span class="doxyLineContent"><span class="doxyHighlight">&lt;NewRegs&gt; = COPY or <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/ipo/loopextractor-cpp/#a84dff14934298a71113ab11312c243f6">extract</a> <a href="/web-llvm/docs/api/files/lib/lib/codegen/machinesink-cpp/#a359e1ff26f6d466d927a61aae45b05c3">Reg</a></span></span></div>
<div class="doxyCodeLine"><span class="doxyNoLineNumber">&nbsp;</span><span class="doxyLineContent"><span class="doxyHighlight">... = <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/hexagon/hexagonbittracker-cpp/#a0ee73ba17c3a2cb54752905e99d77357">op</a> <a href="/web-llvm/docs/api/files/lib/lib/codegen/machinesink-cpp/#a359e1ff26f6d466d927a61aae45b05c3">Reg</a></span></span></div>

</div>


<p>and</p>


<div class="doxyProgramListing">

<div class="doxyCodeLine"><span class="doxyNoLineNumber">&nbsp;</span><span class="doxyLineContent"><span class="doxyHighlight"><a href="/web-llvm/docs/api/files/lib/lib/codegen/machinesink-cpp/#a359e1ff26f6d466d927a61aae45b05c3">Reg</a> = <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/hexagon/hexagonbittracker-cpp/#a0ee73ba17c3a2cb54752905e99d77357">op</a> ...</span></span></div>

</div>


<p>Becomes</p>


<div class="doxyProgramListing">

<div class="doxyCodeLine"><span class="doxyNoLineNumber">&nbsp;</span><span class="doxyLineContent"><span class="doxyHighlight"><a href="/web-llvm/docs/api/files/lib/lib/codegen/machinesink-cpp/#a359e1ff26f6d466d927a61aae45b05c3">Reg</a> = <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/hexagon/hexagonbittracker-cpp/#a0ee73ba17c3a2cb54752905e99d77357">op</a> ...</span></span></div>
<div class="doxyCodeLine"><span class="doxyNoLineNumber">&nbsp;</span><span class="doxyLineContent"><span class="doxyHighlight">Reg = COPY or build_sequence &lt;NewRegs&gt;</span></span></div>

</div>


<dl class="doxySectionUser">
<dt>Precondition</dt>
<dd><p>NewVRegs.size() == ValMapping.BreakDown.size()</p></dd>
</dl>



:::info
<p>The caller is supposed to do the rewriting of op if need be. I.e., Reg = op ... =&gt; &lt;NewRegs&gt; = NewOp ...</p>
:::


<dl class="doxySectionUser">
<dt>Returns</dt>
<dd><p>True if the repairing worked, false otherwise.</p></dd>
</dl>


<p>Declaration at line 563 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/codegen/include/llvm/codegen/globalisel/regbankselect-h">RegBankSelect.h</a>, definition at line 133 of file <a href="/web-llvm/docs/api/files/lib/lib/codegen/lib/codegen/globalisel/regbankselect-cpp">RegBankSelect.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/classes/llvm/machineinstrbuilder/#af584d2eb0342e655d6ec597c0f7958db">llvm::MachineInstrBuilder::addDef</a>, <a href="/web-llvm/docs/api/classes/llvm/machineinstrbuilder/#ad88e27102395957e457fed8e73a085cf">llvm::MachineInstrBuilder::addUse</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/silowercontrolflow-cpp/#a4868c5d81c5ccc98c47aeab6244346a0">assert</a>, <a href="/web-llvm/docs/api/structs/llvm/registerbankinfo/valuemapping/#ae3003e8b89a759af674cb22ed2b67d2e">llvm::RegisterBankInfo::ValueMapping::BreakDown</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a7c46c742c31be54870e2038048e6b391">llvm::dbgs</a>, <a href="/web-llvm/docs/api/classes/llvm/llt/#a71181d67d0bf68c3b8a535ec20463f90">llvm::LLT::getNumElements</a>, <a href="/web-llvm/docs/api/classes/llvm/regbankselect/repairingplacement/#a14dead5300c592bf7b44fadc46d5d1f3">llvm::RegBankSelect::RepairingPlacement::getNumInsertPoints</a>, <a href="/web-llvm/docs/api/classes/llvm/machineoperand/#ac0035d7c1c860501c877c20e6e93297b">llvm::MachineOperand::getReg</a>, <a href="/web-llvm/docs/api/classes/llvm/llt/#a32472b5afd0ae6edb4a233a25056a6aa">llvm::LLT::getScalarSizeInBits</a>, <a href="/web-llvm/docs/api/classes/llvm/llt/#a956ffd0de93798f523683b447646dd92">llvm::LLT::getSizeInBits</a>, <a href="/web-llvm/docs/api/classes/llvm/machineoperand/#a75eb135014670ce946e78739cdc9b51b">llvm::MachineOperand::isDef</a>, <a href="/web-llvm/docs/api/classes/llvm/llt/#a7da5cc6e8aadd4d5fb6dd68f8ec12b7e">llvm::LLT::isVector</a>, <a href="/web-llvm/docs/api/structs/llvm/registerbankinfo/partialmapping/#afac28dfebeb6f31c2c87dd1acdcd038f">llvm::RegisterBankInfo::PartialMapping::Length</a>, <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/support/debug-h/#a196897517069dda1bdb549e24468f7d7">LLVM_DEBUG</a>, <a href="/web-llvm/docs/api/files/lib/lib/codegen/lib/codegen/globalisel/irtranslator-cpp/#abe44dfdea65b4f7e11e0a608ab708b76">MI</a>, <a href="#a1a75a71e05fa8fbc53f9c4437dafef20">MIRBuilder</a>, <a href="#ad8501c8e8cf2d5ffaa86880f57cd4569">MRI</a>, <a href="/web-llvm/docs/api/structs/llvm/registerbankinfo/valuemapping/#a83b9746150eb1c8820d65bca34b8d950">llvm::RegisterBankInfo::ValueMapping::NumBreakDowns</a>, <a href="/web-llvm/docs/api/structs/llvm/registerbankinfo/valuemapping/#a73f71f2f9b3cb7e0602fcd19e648bdfc">llvm::RegisterBankInfo::ValueMapping::partsAllUniform</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#af085ea923a328b9fa6a1975f1a4ff987">llvm::printReg</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a84f1f18b0f13167b8e9c455b9524b58d">llvm::printRegClassOrBank</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a7f2a3d4dcfee70225988aec53ff1e173">llvm::report_fatal_error</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a10f3d955592ae2bc745f57e5b48ae115">llvm::size</a>, <a href="/web-llvm/docs/api/namespaces/std/#ab8424022895aee3e366fb9a32f2883cb">std::swap</a> and <a href="#a98f7afadeec4309cbce64ca040635c04">TRI</a>.</p>


<p>Referenced by <a href="#afc5c7be6a4fbeb70b07dde19d8ebc2fd">applyMapping</a>.</p>

</div>
</div>

### tryAvoidingSplit() {#a781bc33cca080506ba19a20d66c1c255}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void RegBankSelect::tryAvoidingSplit (<a href="/web-llvm/docs/api/classes/llvm/regbankselect/repairingplacement">RegBankSelect::RepairingPlacement</a> &amp; RepairPt, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/machineoperand">MachineOperand</a> &amp; MO, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/structs/llvm/registerbankinfo/valuemapping">RegisterBankInfo::ValueMapping</a> &amp; ValMapping)</td>
</tr>
</table>
</td>
<td class="doxyMemberLabelsRight">
<span class="doxyMemberLabels">
<span class="doxyMemberLabel protected">protected</span>
</span>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>When <span class="doxyComputerOutput">RepairPt</span> involves splitting to repair <span class="doxyComputerOutput">MO</span> for the given <span class="doxyComputerOutput">ValMapping</span>, try to change the way we repair such that the splitting is not required anymore.</p>


<dl class="doxySectionUser">
<dt>Precondition</dt>
<dd><p><span class="doxyComputerOutput">RepairPt.hasSplit()</span></p></dd>
</dl>


<dl class="doxySectionUser">
<dt>Precondition</dt>
<dd><p><span class="doxyComputerOutput">MO</span> == MO.getParent()-&gt;getOperand(<span class="doxyComputerOutput">RepairPt.getOpIdx()</span>)</p></dd>
</dl>


<dl class="doxySectionUser">
<dt>Precondition</dt>
<dd><p><span class="doxyComputerOutput">ValMapping</span> is the mapping of <span class="doxyComputerOutput">MO</span> for MO.getParent() that implied <span class="doxyComputerOutput">RepairPt</span>.</p></dd>
</dl>


<p>Declaration at line 606 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/codegen/include/llvm/codegen/globalisel/regbankselect-h">RegBankSelect.h</a>, definition at line 323 of file <a href="/web-llvm/docs/api/files/lib/lib/codegen/lib/codegen/globalisel/regbankselect-cpp">RegBankSelect.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/silowercontrolflow-cpp/#a4868c5d81c5ccc98c47aeab6244346a0">assert</a>, <a href="/web-llvm/docs/api/classes/llvm/regbankselect/repairingplacement/#a54f51880f9bdd786f0d0983c4f15122b">llvm::RegBankSelect::RepairingPlacement::getOpIdx</a>, <a href="/web-llvm/docs/api/classes/llvm/machineoperand/#a9719077fcba2cd439e84897257a47bb0">llvm::MachineOperand::getParent</a>, <a href="/web-llvm/docs/api/classes/llvm/machineoperand/#ac0035d7c1c860501c877c20e6e93297b">llvm::MachineOperand::getReg</a>, <a href="/web-llvm/docs/api/classes/llvm/regbankselect/repairingplacement/#a05dcab804adfa11b36715dddba6c52db">llvm::RegBankSelect::RepairingPlacement::hasSplit</a>, <a href="/web-llvm/docs/api/classes/llvm/regbankselect/repairingplacement/#a66bdd17ee82024ea0ccbb0288b379dd6a98e66b30e93d741af07a3fefeb66ab1b">llvm::RegBankSelect::RepairingPlacement::Impossible</a>, <a href="/web-llvm/docs/api/classes/llvm/machineoperand/#a75eb135014670ce946e78739cdc9b51b">llvm::MachineOperand::isDef</a>, <a href="/web-llvm/docs/api/files/lib/lib/codegen/lib/codegen/globalisel/irtranslator-cpp/#abe44dfdea65b4f7e11e0a608ab708b76">MI</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#ab13c360340346d082b959b8cd79f2c1a">llvm::Next</a>, <a href="/web-llvm/docs/api/structs/llvm/registerbankinfo/valuemapping/#a83b9746150eb1c8820d65bca34b8d950">llvm::RegisterBankInfo::ValueMapping::NumBreakDowns</a>, <a href="/web-llvm/docs/api/classes/llvm/regbankselect/repairingplacement/#a66bdd17ee82024ea0ccbb0288b379dd6a756e97b1942ca89260909cfdfb64b957">llvm::RegBankSelect::RepairingPlacement::Reassign</a> and <a href="/web-llvm/docs/api/classes/llvm/regbankselect/repairingplacement/#adb2d45f98e7457256296b0943ddd4a6c">llvm::RegBankSelect::RepairingPlacement::switchTo</a>.</p>


<p>Referenced by <a href="#ac7d08af4bb81846173b6186f568fcc8b">computeMapping</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Protected Member Attributes

### MBFI {#a229ce6916aecf746e69143476a1e5686}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">MachineBlockFrequencyInfo* llvm::RegBankSelect::MBFI = nullptr</td>
</tr>
</table>
</td>
<td class="doxyMemberLabelsRight">
<span class="doxyMemberLabels">
<span class="doxyMemberLabel protected">protected</span>
</span>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Get the frequency of blocks.</p>


<p>This is required for non-fast mode.</p>


<p>Definition at line 498 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/codegen/include/llvm/codegen/globalisel/regbankselect-h">RegBankSelect.h</a>.</p>


<p>Referenced by <a href="#ac7d08af4bb81846173b6186f568fcc8b">computeMapping</a>, <a href="/web-llvm/docs/api/classes/llvm/regbankselect/edgeinsertpoint/#a2128bef8edaf9b2e731de12723929db8">llvm::RegBankSelect::EdgeInsertPoint::frequency</a> and <a href="#a6f7e57c8c003253b7da93520af8ef8c2">init</a>.</p>

</div>
</div>

### MBPI {#ab5b60d048f9e03018f15f3730cb24921}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">MachineBranchProbabilityInfo* llvm::RegBankSelect::MBPI = nullptr</td>
</tr>
</table>
</td>
<td class="doxyMemberLabelsRight">
<span class="doxyMemberLabels">
<span class="doxyMemberLabel protected">protected</span>
</span>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Get the frequency of the edges.</p>


<p>This is required for non-fast mode.</p>


<p>Definition at line 502 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/codegen/include/llvm/codegen/globalisel/regbankselect-h">RegBankSelect.h</a>.</p>


<p>Referenced by <a href="#ac7d08af4bb81846173b6186f568fcc8b">computeMapping</a>, <a href="/web-llvm/docs/api/classes/llvm/regbankselect/edgeinsertpoint/#a2128bef8edaf9b2e731de12723929db8">llvm::RegBankSelect::EdgeInsertPoint::frequency</a> and <a href="#a6f7e57c8c003253b7da93520af8ef8c2">init</a>.</p>

</div>
</div>

### MIRBuilder {#a1a75a71e05fa8fbc53f9c4437dafef20}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">MachineIRBuilder llvm::RegBankSelect::MIRBuilder</td>
</tr>
</table>
</td>
<td class="doxyMemberLabelsRight">
<span class="doxyMemberLabels">
<span class="doxyMemberLabel protected">protected</span>
</span>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Helper class used for every code morphing.</p>

<p>Definition at line 508 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/codegen/include/llvm/codegen/globalisel/regbankselect-h">RegBankSelect.h</a>.</p>


<p>Referenced by <a href="#afc5c7be6a4fbeb70b07dde19d8ebc2fd">applyMapping</a>, <a href="#a6b0bf1d2a5eba4af2825113954bb846f">assignRegisterBanks</a>, <a href="#a6f7e57c8c003253b7da93520af8ef8c2">init</a> and <a href="#ac8d8bb4999d968e0efc9555c2b178a83">repairReg</a>.</p>

</div>
</div>

### MORE {#afc036a279f48923ec0077a63d975e158}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">std::unique_ptr&lt;MachineOptimizationRemarkEmitter&gt; llvm::RegBankSelect::MORE</td>
</tr>
</table>
</td>
<td class="doxyMemberLabelsRight">
<span class="doxyMemberLabels">
<span class="doxyMemberLabel protected">protected</span>
</span>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Current optimization remark emitter. Used to report failures.</p>

<p>Definition at line 505 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/codegen/include/llvm/codegen/globalisel/regbankselect-h">RegBankSelect.h</a>.</p>


<p>Referenced by <a href="#a6b0bf1d2a5eba4af2825113954bb846f">assignRegisterBanks</a>, <a href="#a04620d87783d98e60cdfcaf04f783f47">checkFunctionIsLegal</a> and <a href="#a6f7e57c8c003253b7da93520af8ef8c2">init</a>.</p>

</div>
</div>

### MRI {#ad8501c8e8cf2d5ffaa86880f57cd4569}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">MachineRegisterInfo* llvm::RegBankSelect::MRI = nullptr</td>
</tr>
</table>
</td>
<td class="doxyMemberLabelsRight">
<span class="doxyMemberLabels">
<span class="doxyMemberLabel protected">protected</span>
</span>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>MRI contains all the register class/bank information that this pass uses and updates.</p>

<p>Definition at line 491 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/codegen/include/llvm/codegen/globalisel/regbankselect-h">RegBankSelect.h</a>.</p>


<p>Referenced by <a href="#afc5c7be6a4fbeb70b07dde19d8ebc2fd">applyMapping</a>, <a href="#a6553ca5670588f279c72f84d46b05033">assignInstr</a>, <a href="#ac00dc73d1e42ba9d0e4f906e8b4edfd8">assignmentMatch</a>, <a href="#ac7d08af4bb81846173b6186f568fcc8b">computeMapping</a>, <a href="#ac3cfa17f907e7258d898433ddfeb3fbf">getRepairCost</a>, <a href="#a6f7e57c8c003253b7da93520af8ef8c2">init</a> and <a href="#ac8d8bb4999d968e0efc9555c2b178a83">repairReg</a>.</p>

</div>
</div>

### OptMode {#a32ef3eb67c8ddb568ebc316b4e56bd27}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">Mode llvm::RegBankSelect::OptMode</td>
</tr>
</table>
</td>
<td class="doxyMemberLabelsRight">
<span class="doxyMemberLabels">
<span class="doxyMemberLabel protected">protected</span>
</span>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Optimization mode of the pass.</p>

<p>Definition at line 511 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/codegen/include/llvm/codegen/globalisel/regbankselect-h">RegBankSelect.h</a>.</p>


<p>Referenced by <a href="#a6553ca5670588f279c72f84d46b05033">assignInstr</a>, <a href="#a9a6d36010e8ada5ee58eeda765414a89">getAnalysisUsage</a>, <a href="#a6f7e57c8c003253b7da93520af8ef8c2">init</a> and <a href="#ae245b9ebf2973a3e982ccd16c9bf93f1">runOnMachineFunction</a>.</p>

</div>
</div>

### RBI {#afa42d1c7970f30d2fa388d5399348001}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">const RegisterBankInfo* llvm::RegBankSelect::RBI = nullptr</td>
</tr>
</table>
</td>
<td class="doxyMemberLabelsRight">
<span class="doxyMemberLabels">
<span class="doxyMemberLabel protected">protected</span>
</span>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Interface to the target lowering info related to register banks.</p>

<p>Definition at line 487 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/codegen/include/llvm/codegen/globalisel/regbankselect-h">RegBankSelect.h</a>.</p>


<p>Referenced by <a href="#afc5c7be6a4fbeb70b07dde19d8ebc2fd">applyMapping</a>, <a href="#a6553ca5670588f279c72f84d46b05033">assignInstr</a>, <a href="#ac00dc73d1e42ba9d0e4f906e8b4edfd8">assignmentMatch</a>, <a href="#ac3cfa17f907e7258d898433ddfeb3fbf">getRepairCost</a> and <a href="#a6f7e57c8c003253b7da93520af8ef8c2">init</a>.</p>

</div>
</div>

### TPC {#ae2b9166b734338bf10060074564467a0}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">const TargetPassConfig* llvm::RegBankSelect::TPC</td>
</tr>
</table>
</td>
<td class="doxyMemberLabelsRight">
<span class="doxyMemberLabels">
<span class="doxyMemberLabel protected">protected</span>
</span>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Current target configuration. Controls how the pass handles errors.</p>

<p>Definition at line 514 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/codegen/include/llvm/codegen/globalisel/regbankselect-h">RegBankSelect.h</a>.</p>


<p>Referenced by <a href="#a6b0bf1d2a5eba4af2825113954bb846f">assignRegisterBanks</a>, <a href="#a04620d87783d98e60cdfcaf04f783f47">checkFunctionIsLegal</a>, <a href="#a4dd660f230b1343ae79f15573d7da3d4">findBestMapping</a> and <a href="#a6f7e57c8c003253b7da93520af8ef8c2">init</a>.</p>

</div>
</div>

### TRI {#a98f7afadeec4309cbce64ca040635c04}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">const TargetRegisterInfo* llvm::RegBankSelect::TRI = nullptr</td>
</tr>
</table>
</td>
<td class="doxyMemberLabelsRight">
<span class="doxyMemberLabels">
<span class="doxyMemberLabel protected">protected</span>
</span>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Information on the register classes for the current function.</p>

<p>Definition at line 494 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/codegen/include/llvm/codegen/globalisel/regbankselect-h">RegBankSelect.h</a>.</p>


<p>Referenced by <a href="#a6553ca5670588f279c72f84d46b05033">assignInstr</a>, <a href="#ac00dc73d1e42ba9d0e4f906e8b4edfd8">assignmentMatch</a>, <a href="#ac7d08af4bb81846173b6186f568fcc8b">computeMapping</a>, <a href="#a4dd660f230b1343ae79f15573d7da3d4">findBestMapping</a>, <a href="#ac3cfa17f907e7258d898433ddfeb3fbf">getRepairCost</a>, <a href="#a6f7e57c8c003253b7da93520af8ef8c2">init</a>, <a href="/web-llvm/docs/api/classes/llvm/regbankselect/repairingplacement/#a40139f3ca5fa604f87136efa9ca611ca">llvm::RegBankSelect::RepairingPlacement::RepairingPlacement</a> and <a href="#ac8d8bb4999d968e0efc9555c2b178a83">repairReg</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Public Static Attributes

### ID {#a18a280ae37dbd3b58a04012da318b687}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">char RegBankSelect::ID = 0</td>
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



<p>Definition at line 93 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/codegen/include/llvm/codegen/globalisel/regbankselect-h">RegBankSelect.h</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/classes/anonymous-spirvtargetmachine-cpp-/spirvpassconfig/#a59de015d004a5f101e06162d9699076a">anonymous{SPIRVTargetMachine.cpp}::SPIRVPassConfig::addRegBankSelect</a>.</p>

</div>
</div>

</div>

<hr/>

The documentation for this class was generated from the following files:

<ul>
<li><a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/codegen/include/llvm/codegen/globalisel/regbankselect-h">RegBankSelect.h</a></li>
<li><a href="/web-llvm/docs/api/files/lib/lib/codegen/lib/codegen/globalisel/regbankselect-cpp">RegBankSelect.cpp</a></li>
</ul>

<hr/>

<p class="doxyGeneratedBy">Generated via <a href="https://github.com/xpack/doxygen2docusaurus">doxygen2docusaurus</a> by <a href="https://www.doxygen.nl">Doxygen</a> 1.14.0.</p>

</div>
