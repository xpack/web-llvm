---

# DO NOT EDIT!
# Automatically generated via doxygen2docusaurus by Doxygen.

slug: /api/structs/anonymous-hexagonhardwareloops-cpp-/hexagonhardwareloops
custom_edit_url: null
toc_max_heading_level: 4
keywords:
  - doxygen
  - reference
  - struct

---

<div class="doxyPage">

# `HexagonHardwareLoops` Struct



## Declaration

<div class="doxyDeclaration">
struct anonymous{HexagonHardwareLoops.cpp}::HexagonHardwareLoops { ... }
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

## Private Member Typedefs Index

<table class="doxyMembersIndex">

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">using</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ac6b82390fefb5da9c2865eed18b778a2">LoopFeederMap</a> = std::map&lt; <a href="/web-llvm/docs/api/classes/llvm/register">Register</a>, <a href="/web-llvm/docs/api/classes/llvm/machineinstr">MachineInstr</a> * &gt;</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a7ba6007fbeaf7123afa98a38a0198dda">HexagonHardwareLoops</a> ()</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a227e7ddfafd6bce13cfb1473136e8230">runOnMachineFunction</a> (MachineFunction &amp;MF) override</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>runOnMachineFunction - This method must be overloaded to perform the desired machine code transformation or analysis. <a href="#a227e7ddfafd6bce13cfb1473136e8230">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/stringref">StringRef</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a8ea624b644f9e276a8265d50b493d74a">getPassName</a> () const override</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>getPassName - Return a nice clean name for a pass. <a href="#a8ea624b644f9e276a8265d50b493d74a">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">void</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a6883ae5f17e638eb68522e3e2cde21c6">getAnalysisUsage</a> (AnalysisUsage &amp;AU) const override</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>getAnalysisUsage - This function should be overriden by passes that need analysis information to do their job. <a href="#a6883ae5f17e638eb68522e3e2cde21c6">More...</a></p>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a43d49f23512f7554a2deb7cfe9019a44">findInductionRegister</a> (MachineLoop *L, Register &amp;Reg, int64_t &amp;IVBump, MachineInstr *&amp;IVOp) const</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Find the register that contains the loop controlling induction variable. <a href="#a43d49f23512f7554a2deb7cfe9019a44">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">Comparison::Kind</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a5ed3d2963dc0dc995190233b763a8764">getComparisonKind</a> (unsigned CondOpc, MachineOperand *InitialValue, const MachineOperand *Endvalue, int64_t IVBump) const</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Return the comparison kind for the specified opcode. <a href="#a5ed3d2963dc0dc995190233b763a8764">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/anonymous-hexagonhardwareloops-cpp-/countvalue">CountValue</a> *</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#aeaeea823712680f7bb14b421725e777a">getLoopTripCount</a> (MachineLoop *L, SmallVectorImpl&lt; MachineInstr * &gt; &amp;OldInsts)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Analyze the statements in a loop to determine if the loop has a computable trip count and, if so, return a value that represents the trip count expression. <a href="#aeaeea823712680f7bb14b421725e777a">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/anonymous-hexagonhardwareloops-cpp-/countvalue">CountValue</a> *</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a83476caf5187aa87ccc67c401ad07c39">computeCount</a> (MachineLoop *Loop, const MachineOperand *Start, const MachineOperand *End, Register IVReg, int64_t IVBump, Comparison::Kind Cmp) const</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Return the expression that represents the number of times a loop iterates. <a href="#a83476caf5187aa87ccc67c401ad07c39">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">bool</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a788ee8bfed2f5f542d7863fe950202bb">isInvalidLoopOperation</a> (const MachineInstr *MI, bool IsInnerHWLoop) const</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Return true if the instruction is not valid within a hardware loop. <a href="#a788ee8bfed2f5f542d7863fe950202bb">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">bool</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a8085af352a9541eb9ec92e82cf60098f">containsInvalidInstruction</a> (MachineLoop *L, bool IsInnerHWLoop) const</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Return true if the loop contains an instruction that inhibits using the hardware loop. <a href="#a8085af352a9541eb9ec92e82cf60098f">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">bool</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a665e9738b997cc75cc5b9716dfd0e091">convertToHardwareLoop</a> (MachineLoop *L, bool &amp;L0used, bool &amp;L1used)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Given a loop, check if we can convert it to a hardware loop. <a href="#a665e9738b997cc75cc5b9716dfd0e091">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">bool</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a86c298e486e4f1c7a505de80e0487bbe">isDead</a> (const MachineInstr *MI, SmallVectorImpl&lt; MachineInstr * &gt; &amp;DeadPhis) const</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Return true if the instruction is now dead. <a href="#a86c298e486e4f1c7a505de80e0487bbe">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">void</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a00770c8027ff9165f98e1e91d1f78d65">removeIfDead</a> (MachineInstr *MI)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Remove the instruction if it is now dead. <a href="#a00770c8027ff9165f98e1e91d1f78d65">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">bool</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a23eba50257ccba363671df08c1ff5793">orderBumpCompare</a> (MachineInstr *BumpI, MachineInstr *CmpI)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Make sure that the "bump" instruction executes before the compare. <a href="#a23eba50257ccba363671df08c1ff5793">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">bool</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a893f8a4fd143c960627a143b0c2753d4">isLoopFeeder</a> (MachineLoop *L, MachineBasicBlock *A, MachineInstr *MI, const MachineOperand *MO, LoopFeederMap &amp;LoopFeederPhi) const</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Return true if MO and MI pair is visited only once. <a href="#a893f8a4fd143c960627a143b0c2753d4">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">bool</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a66b16adf030f72742c139fac26280eb2">phiMayWrapOrUnderflow</a> (MachineInstr *Phi, const MachineOperand *EndVal, MachineBasicBlock *MBB, MachineLoop *L, LoopFeederMap &amp;LoopFeederPhi) const</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Return true if the Phi may generate a value that may underflow, or may wrap. <a href="#a66b16adf030f72742c139fac26280eb2">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">bool</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a8a3381f44509e7c4529936b7b8e1622a">loopCountMayWrapOrUnderFlow</a> (const MachineOperand *InitVal, const MachineOperand *EndVal, MachineBasicBlock *MBB, MachineLoop *L, LoopFeederMap &amp;LoopFeederPhi) const</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Return true if the induction variable may underflow an unsigned value in the first iteration. <a href="#a8a3381f44509e7c4529936b7b8e1622a">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">bool</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a3079e29992991b31a5a2c3117d37f49e">checkForImmediate</a> (const MachineOperand &amp;MO, int64_t &amp;Val) const</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Check if the given operand has a compile-time known constant value. <a href="#a3079e29992991b31a5a2c3117d37f49e">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">bool</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a807ab4ff060cd9c8ca7d5c62222b8c3a">isImmediate</a> (const MachineOperand &amp;MO) const</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Check if the operand has a compile-time known constant value. <a href="#a807ab4ff060cd9c8ca7d5c62222b8c3a">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">int64_t</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a3db634726639483c9ad746922787d07f">getImmediate</a> (const MachineOperand &amp;MO) const</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Return the immediate for the specified operand. <a href="#a3db634726639483c9ad746922787d07f">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">void</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ab1791444f0b5ea643148dbebb7c29646">setImmediate</a> (MachineOperand &amp;MO, int64_t Val)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Reset the given machine operand to now refer to a new immediate value. <a href="#ab1791444f0b5ea643148dbebb7c29646">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">bool</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#aa9f6b81556b3c4cb8f7bd7796d1e642d">fixupInductionVariable</a> (MachineLoop *L)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Fix the data flow of the induction variable. <a href="#aa9f6b81556b3c4cb8f7bd7796d1e642d">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/machinebasicblock">MachineBasicBlock</a> *</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a263f3bec0cc5b67a174a103d6572adb7">createPreheaderForLoop</a> (MachineLoop *L)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Given a loop, if it does not have a preheader, create one. <a href="#a263f3bec0cc5b67a174a103d6572adb7">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

</table>

## Public Member Attributes Index

<table class="doxyMembersIndex">

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/machineloopinfo">MachineLoopInfo</a> *</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a62d7a42ca2e5768f90f26af63eff37df">MLI</a></td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ae58f8afe564f61fab4eb19ce22aae73e">MRI</a></td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a131d6c8d567e507a8424fb2ca791ce58">MDT</a></td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/hexagoninstrinfo">HexagonInstrInfo</a> *</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a7b9acab12fb99432eab080e9197a13de">TII</a></td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/hexagonregisterinfo">HexagonRegisterInfo</a> *</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a52c5d48e3e2a57f55fe88240a9cab9f1">TRI</a></td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">static int</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#aa2b7e4cd01f1099b9b7b906c0185377f">Counter</a> = 0</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">static char</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ac40b8dc6f6e7f12eee455df7fdd5acaa">ID</a> = 0</td>
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


<p>Definition at line 100 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/hexagon/hexagonhardwareloops-cpp">HexagonHardwareLoops.cpp</a>.</p>


<div class="doxySectionDef">

## Private Member Typedefs

### LoopFeederMap {#ac6b82390fefb5da9c2865eed18b778a2}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">using anonymous{HexagonHardwareLoops.cpp}::HexagonHardwareLoops::LoopFeederMap =  std::map&lt;Register, MachineInstr *&gt;</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 126 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/hexagon/hexagonhardwareloops-cpp">HexagonHardwareLoops.cpp</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Public Constructors

### HexagonHardwareLoops() {#a7ba6007fbeaf7123afa98a38a0198dda}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">anonymous{HexagonHardwareLoops.cpp}::HexagonHardwareLoops::HexagonHardwareLoops ()</td>
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



<p>Definition at line 113 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/hexagon/hexagonhardwareloops-cpp">HexagonHardwareLoops.cpp</a>.</p>


<p>References <a href="#ac40b8dc6f6e7f12eee455df7fdd5acaa">ID</a> and <a href="/web-llvm/docs/api/classes/llvm/machinefunctionpass/#a29c81d2386f4a727c6d33413807530c8">llvm::MachineFunctionPass::MachineFunctionPass</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/namespaces/llvm/#ad334ebc2f4abb942af36808d05a32fc1">llvm::createHexagonHardwareLoops</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Public Member Functions

### getAnalysisUsage() {#a6883ae5f17e638eb68522e3e2cde21c6}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void anonymous{HexagonHardwareLoops.cpp}::HexagonHardwareLoops::getAnalysisUsage (<a href="/web-llvm/docs/api/classes/llvm/analysisusage">AnalysisUsage</a> &amp;)</td>
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


<p>Definition at line 119 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/hexagon/hexagonhardwareloops-cpp">HexagonHardwareLoops.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/classes/llvm/analysisusage/#ae0adcccca08fb686c9ce00f9397b660c">llvm::AnalysisUsage::addRequired</a> and <a href="/web-llvm/docs/api/classes/llvm/machinefunctionpass/#a864fd57b4304ef933b3281d0ef85a88e">llvm::MachineFunctionPass::getAnalysisUsage</a>.</p>

</div>
</div>

### getPassName() {#a8ea624b644f9e276a8265d50b493d74a}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">StringRef anonymous{HexagonHardwareLoops.cpp}::HexagonHardwareLoops::getPassName ()</td>
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


<p>Definition at line 117 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/hexagon/hexagonhardwareloops-cpp">HexagonHardwareLoops.cpp</a>.</p>

</div>
</div>

### runOnMachineFunction() {#a227e7ddfafd6bce13cfb1473136e8230}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool HexagonHardwareLoops::runOnMachineFunction (<a href="/web-llvm/docs/api/classes/llvm/machinefunction">MachineFunction</a> &amp; MF)</td>
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

<p>Definition at line 115 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/hexagon/hexagonhardwareloops-cpp">HexagonHardwareLoops.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/namespaces/llvm/#a7c46c742c31be54870e2038048e6b391">llvm::dbgs</a>, <a href="/web-llvm/docs/api/classes/llvm/pass/#a4863e5e463fb79955269fbf7fbf52b80">llvm::Pass::getAnalysis</a>, <a href="/web-llvm/docs/api/classes/llvm/machinefunction/#a977ddce262de45c645be23d951066351">llvm::MachineFunction::getFunction</a>, <a href="/web-llvm/docs/api/classes/llvm/hexagonsubtarget/#a21e692502cb75b1488e8b4047000ace6">llvm::HexagonSubtarget::getInstrInfo</a>, <a href="/web-llvm/docs/api/classes/llvm/machinefunction/#a810234b6b3d223b7c74a4253fcc5ea5e">llvm::MachineFunction::getRegInfo</a>, <a href="/web-llvm/docs/api/classes/llvm/hexagonsubtarget/#a33ae6b411360f4516d2765ada63756ef">llvm::HexagonSubtarget::getRegisterInfo</a>, <a href="/web-llvm/docs/api/classes/llvm/machinefunction/#a3825368aca2bc1550d173660df4da6a6">llvm::MachineFunction::getSubtarget</a>, <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/support/debug-h/#a196897517069dda1bdb549e24468f7d7">LLVM_DEBUG</a>, <a href="#a131d6c8d567e507a8424fb2ca791ce58">MDT</a>, <a href="#a62d7a42ca2e5768f90f26af63eff37df">MLI</a>, <a href="#ae58f8afe564f61fab4eb19ce22aae73e">MRI</a>, <a href="/web-llvm/docs/api/classes/llvm/functionpass/#af9f5f511d75e16f09a5520cb9444cfa8">llvm::FunctionPass::skipFunction</a>, <a href="#a7b9acab12fb99432eab080e9197a13de">TII</a> and <a href="#a52c5d48e3e2a57f55fe88240a9cab9f1">TRI</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Private Member Functions

### checkForImmediate() {#a3079e29992991b31a5a2c3117d37f49e}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool HexagonHardwareLoops::checkForImmediate (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/machineoperand">MachineOperand</a> &amp; MO, int64_t &amp; Val)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Check if the given operand has a compile-time known constant value.</p>


<p>Return true if yes, and false otherwise. When returning true, set Val to the corresponding constant value.</p>


<p>Definition at line 257 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/hexagon/hexagonhardwareloops-cpp">HexagonHardwareLoops.cpp</a>.</p>

</div>
</div>

### computeCount() {#a83476caf5187aa87ccc67c401ad07c39}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">CountValue * HexagonHardwareLoops::computeCount (<a href="/web-llvm/docs/api/classes/llvm/machineloop">MachineLoop</a> * Loop, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/machineoperand">MachineOperand</a> * Start, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/machineoperand">MachineOperand</a> * End, <a href="/web-llvm/docs/api/classes/llvm/register">Register</a> IVReg, int64_t IVBump, Comparison::Kind Cmp)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Return the expression that represents the number of times a loop iterates.</p>


<p>Helper function that returns the expression that represents the number of times a loop iterates.</p>


<p>The function takes the operands that represent the loop start value, loop end value, and induction value. Based upon these operands, the function attempts to compute the trip count. If the trip count is not directly available (as an immediate value, or a register), the function will attempt to insert computation of it to the loop's preheader.</p>


<p>The function takes the operands that represent the loop start value, loop end value, and induction value. Based upon these operands, the function attempts to compute the trip count.</p>


<p>Definition at line 204 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/hexagon/hexagonhardwareloops-cpp">HexagonHardwareLoops.cpp</a>.</p>

</div>
</div>

### containsInvalidInstruction() {#a8085af352a9541eb9ec92e82cf60098f}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool HexagonHardwareLoops::containsInvalidInstruction (<a href="/web-llvm/docs/api/classes/llvm/machineloop">MachineLoop</a> * L, bool IsInnerHWLoop)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Return true if the loop contains an instruction that inhibits using the hardware loop.</p>


<p>Return true if the loop contains an instruction that inhibits the use of the hardware loop instruction.</p>


<p>Definition at line 215 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/hexagon/hexagonhardwareloops-cpp">HexagonHardwareLoops.cpp</a>.</p>

</div>
</div>

### convertToHardwareLoop() {#a665e9738b997cc75cc5b9716dfd0e091}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool HexagonHardwareLoops::convertToHardwareLoop (<a href="/web-llvm/docs/api/classes/llvm/machineloop">MachineLoop</a> * L, bool &amp; RecL0used, bool &amp; RecL1used)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Given a loop, check if we can convert it to a hardware loop.</p>


<p>Check if the loop is a candidate for converting to a hardware loop.</p>


<p>If so, then perform the conversion and return true.</p>


<p>If so, then perform the transformation.</p>


<p>This function works on innermost loops first. A loop can be converted if it is a counting loop; either a register value or an immediate.</p>


<p>The code makes several assumptions about the representation of the loop in llvm.</p>


<p>Definition at line 219 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/hexagon/hexagonhardwareloops-cpp">HexagonHardwareLoops.cpp</a>.</p>

</div>
</div>

### createPreheaderForLoop() {#a263f3bec0cc5b67a174a103d6572adb7}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">MachineBasicBlock * HexagonHardwareLoops::createPreheaderForLoop (<a href="/web-llvm/docs/api/classes/llvm/machineloop">MachineLoop</a> * L)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Given a loop, if it does not have a preheader, create one.</p>


<p>createPreheaderForLoop - Create a preheader for a given loop.</p>


<p>Return the block that is the preheader.</p>


<p>Definition at line 301 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/hexagon/hexagonhardwareloops-cpp">HexagonHardwareLoops.cpp</a>.</p>

</div>
</div>

### findInductionRegister() {#a43d49f23512f7554a2deb7cfe9019a44}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool HexagonHardwareLoops::findInductionRegister (<a href="/web-llvm/docs/api/classes/llvm/machineloop">MachineLoop</a> * L, <a href="/web-llvm/docs/api/classes/llvm/register">Register</a> &amp; Reg, int64_t &amp; IVBump, <a href="/web-llvm/docs/api/classes/llvm/machineinstr">MachineInstr</a> *&amp; IVOp)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Find the register that contains the loop controlling induction variable.</p>


<p>If successful, it will return true and set the <span class="doxyComputerOutput">Reg</span>, <span class="doxyComputerOutput">IVBump</span> and <span class="doxyComputerOutput">IVOp</span> arguments. Otherwise it will return false. The returned induction register is the register R that follows the following induction pattern: loop: R = phi ..., [ R.next, LatchBlock ] R.next = R + #bump if (R.next &lt; <a href="/web-llvm/docs/api/files/lib/lib/support/regcomp-c/#a0240ac851181b84ac374872dc5434ee4">N</a>) goto loop IVBump is the immediate value added to R, and IVOp is the instruction "R.next = R + #bump".</p>


<p>Definition at line 182 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/hexagon/hexagonhardwareloops-cpp">HexagonHardwareLoops.cpp</a>.</p>

</div>
</div>

### fixupInductionVariable() {#aa9f6b81556b3c4cb8f7bd7796d1e642d}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool HexagonHardwareLoops::fixupInductionVariable (<a href="/web-llvm/docs/api/classes/llvm/machineloop">MachineLoop</a> * L)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Fix the data flow of the induction variable.</p>


<p>The desired flow is: phi ---&gt; bump -+-&gt; comparison-in-latch. | +-&gt; back to phi where "bump" is the increment of the induction variable: iv = iv + <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a>. Due to some prior code transformations, the actual flow may look like this: phi -+-&gt; bump ---&gt; back to phi | +-&gt; comparison-in-latch (against upper_bound-bump), i.e. the comparison that controls the loop execution may be using the value of the induction variable from before the increment.</p>


<p>Return true if the loop's flow is the desired one (i.e. it's either been fixed, or no fixing was necessary). Otherwise, return false. This can happen if the induction variable couldn't be identified, or if the value in the latch's comparison cannot be adjusted to reflect the post-bump value.</p>


<p>Definition at line 297 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/hexagon/hexagonhardwareloops-cpp">HexagonHardwareLoops.cpp</a>.</p>

</div>
</div>

### getComparisonKind() {#a5ed3d2963dc0dc995190233b763a8764}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">HexagonHardwareLoops::Comparison::Kind HexagonHardwareLoops::getComparisonKind (unsigned CondOpc, <a href="/web-llvm/docs/api/classes/llvm/machineoperand">MachineOperand</a> * InitialValue, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/machineoperand">MachineOperand</a> * Endvalue, int64_t IVBump)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Return the comparison kind for the specified opcode.</p>

<p>Definition at line 186 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/hexagon/hexagonhardwareloops-cpp">HexagonHardwareLoops.cpp</a>.</p>

</div>
</div>

### getImmediate() {#a3db634726639483c9ad746922787d07f}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">int64_t anonymous{HexagonHardwareLoops.cpp}::HexagonHardwareLoops::getImmediate (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/machineoperand">MachineOperand</a> &amp; MO)</td>
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

<p>Return the immediate for the specified operand.</p>

<p>Definition at line 266 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/hexagon/hexagonhardwareloops-cpp">HexagonHardwareLoops.cpp</a>.</p>

</div>
</div>

### getLoopTripCount() {#aeaeea823712680f7bb14b421725e777a}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">CountValue * HexagonHardwareLoops::getLoopTripCount (<a href="/web-llvm/docs/api/classes/llvm/machineloop">MachineLoop</a> * L, <a href="/web-llvm/docs/api/classes/llvm/smallvectorimpl">SmallVectorImpl</a>&lt; <a href="/web-llvm/docs/api/classes/llvm/machineinstr">MachineInstr</a> * &gt; &amp; OldInsts)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Analyze the statements in a loop to determine if the loop has a computable trip count and, if so, return a value that represents the trip count expression.</p>


<p>This function iterates over the phi nodes in the loop to check for induction variable patterns that are used in the calculation for the number of time the loop is executed.</p>


<p>Definition at line 194 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/hexagon/hexagonhardwareloops-cpp">HexagonHardwareLoops.cpp</a>.</p>

</div>
</div>

### isDead() {#a86c298e486e4f1c7a505de80e0487bbe}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool HexagonHardwareLoops::isDead (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/machineinstr">MachineInstr</a> * MI, <a href="/web-llvm/docs/api/classes/llvm/smallvectorimpl">SmallVectorImpl</a>&lt; <a href="/web-llvm/docs/api/classes/llvm/machineinstr">MachineInstr</a> * &gt; &amp; DeadPhis)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Return true if the instruction is now dead.</p>


<p>Returns true if the instruction is dead.</p>


<p>This was essentially copied from DeadMachineInstructionElim::isDead, but with special cases for inline asm, physical registers and instructions with side effects removed.</p>


<p>Definition at line 222 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/hexagon/hexagonhardwareloops-cpp">HexagonHardwareLoops.cpp</a>.</p>

</div>
</div>

### isImmediate() {#a807ab4ff060cd9c8ca7d5c62222b8c3a}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool anonymous{HexagonHardwareLoops.cpp}::HexagonHardwareLoops::isImmediate (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/machineoperand">MachineOperand</a> &amp; MO)</td>
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

<p>Check if the operand has a compile-time known constant value.</p>

<p>Definition at line 260 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/hexagon/hexagonhardwareloops-cpp">HexagonHardwareLoops.cpp</a>.</p>

</div>
</div>

### isInvalidLoopOperation() {#a788ee8bfed2f5f542d7863fe950202bb}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool HexagonHardwareLoops::isInvalidLoopOperation (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/machineinstr">MachineInstr</a> * MI, bool IsInnerHWLoop)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Return true if the instruction is not valid within a hardware loop.</p>


<p>Return true if the operation is invalid within hardware loop.</p>


<p>Definition at line 210 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/hexagon/hexagonhardwareloops-cpp">HexagonHardwareLoops.cpp</a>.</p>

</div>
</div>

### isLoopFeeder() {#a893f8a4fd143c960627a143b0c2753d4}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool HexagonHardwareLoops::isLoopFeeder (<a href="/web-llvm/docs/api/classes/llvm/machineloop">MachineLoop</a> * L, <a href="/web-llvm/docs/api/classes/llvm/machinebasicblock">MachineBasicBlock</a> * A, <a href="/web-llvm/docs/api/classes/llvm/machineinstr">MachineInstr</a> * MI, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/machineoperand">MachineOperand</a> * MO, LoopFeederMap &amp; LoopFeederPhi)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Return true if MO and MI pair is visited only once.</p>


<p>This function is required to break recursion.</p>


<p>If visited more than once, this indicates there is recursion. In such a case, return false.</p>


<p>Visiting phis in a loop may result in recursion during compilation. We break the recursion by making sure that we visit a <a href="/web-llvm/docs/api/classes/llvm/machineoperand">MachineOperand</a> and its definition in a MachineInstruction only once. If we attempt to visit more than once, then there is recursion, and will return false.</p>


<p>Definition at line 237 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/hexagon/hexagonhardwareloops-cpp">HexagonHardwareLoops.cpp</a>.</p>

</div>
</div>

### loopCountMayWrapOrUnderFlow() {#a8a3381f44509e7c4529936b7b8e1622a}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool HexagonHardwareLoops::loopCountMayWrapOrUnderFlow (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/machineoperand">MachineOperand</a> * InitVal, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/machineoperand">MachineOperand</a> * EndVal, <a href="/web-llvm/docs/api/classes/llvm/machinebasicblock">MachineBasicBlock</a> * MBB, <a href="/web-llvm/docs/api/classes/llvm/machineloop">MachineLoop</a> * L, LoopFeederMap &amp; LoopFeederPhi)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Return true if the induction variable may underflow an unsigned value in the first iteration.</p>


<p>Return true if the induction variable can underflow in the first iteration.</p>


<p>An example, is an initial unsigned value that is 0 and is decrement in the first itertion of a do-while loop. In this case, we cannot generate a hardware loop because the endloop instruction does not decrement the loop counter if it is &lt;= 1. We only need to perform this analysis if the initial value is a register.</p>


<p>This function assumes the initial value may underfow unless proven otherwise. If the type is signed, then we don't care because signed underflow is undefined. We attempt to prove the initial value is not zero by perfoming a crude analysis of the loop counter. This function checks if the initial value is used in any comparison prior to the loop and, if so, assumes the comparison is a range check. This is inexact, but will catch the simple cases.</p>


<p>Definition at line 249 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/hexagon/hexagonhardwareloops-cpp">HexagonHardwareLoops.cpp</a>.</p>

</div>
</div>

### orderBumpCompare() {#a23eba50257ccba363671df08c1ff5793}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool HexagonHardwareLoops::orderBumpCompare (<a href="/web-llvm/docs/api/classes/llvm/machineinstr">MachineInstr</a> * BumpI, <a href="/web-llvm/docs/api/classes/llvm/machineinstr">MachineInstr</a> * CmpI)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Make sure that the "bump" instruction executes before the compare.</p>


<p>We need that for the IV fixup, so that the compare instruction would not use a bumped value that has not yet been defined. If the instructions are out of order, try to reorder them.</p>


<p>Definition at line 232 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/hexagon/hexagonhardwareloops-cpp">HexagonHardwareLoops.cpp</a>.</p>

</div>
</div>

### phiMayWrapOrUnderflow() {#a66b16adf030f72742c139fac26280eb2}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool HexagonHardwareLoops::phiMayWrapOrUnderflow (<a href="/web-llvm/docs/api/classes/llvm/machineinstr">MachineInstr</a> * Phi, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/machineoperand">MachineOperand</a> * EndVal, <a href="/web-llvm/docs/api/classes/llvm/machinebasicblock">MachineBasicBlock</a> * MBB, <a href="/web-llvm/docs/api/classes/llvm/machineloop">MachineLoop</a> * L, LoopFeederMap &amp; LoopFeederPhi)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Return true if the Phi may generate a value that may underflow, or may wrap.</p>


<p>Return true if a Phi may generate a value that can underflow.</p>


<p>This function calls loopCountMayWrapOrUnderFlow for each Phi operand.</p>


<p>Definition at line 243 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/hexagon/hexagonhardwareloops-cpp">HexagonHardwareLoops.cpp</a>.</p>

</div>
</div>

### removeIfDead() {#a00770c8027ff9165f98e1e91d1f78d65}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void HexagonHardwareLoops::removeIfDead (<a href="/web-llvm/docs/api/classes/llvm/machineinstr">MachineInstr</a> * MI)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Remove the instruction if it is now dead.</p>

<p>Definition at line 226 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/hexagon/hexagonhardwareloops-cpp">HexagonHardwareLoops.cpp</a>.</p>

</div>
</div>

### setImmediate() {#ab1791444f0b5ea643148dbebb7c29646}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void HexagonHardwareLoops::setImmediate (<a href="/web-llvm/docs/api/classes/llvm/machineoperand">MachineOperand</a> &amp; MO, int64_t Val)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Reset the given machine operand to now refer to a new immediate value.</p>


<p>Assumes that the operand was already referencing an immediate value, either directly, or via a register.</p>


<p>Definition at line 276 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/hexagon/hexagonhardwareloops-cpp">HexagonHardwareLoops.cpp</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Public Member Attributes

### MDT {#a131d6c8d567e507a8424fb2ca791ce58}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">MachineDominatorTree* anonymous{HexagonHardwareLoops.cpp}::HexagonHardwareLoops::MDT</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 103 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/hexagon/hexagonhardwareloops-cpp">HexagonHardwareLoops.cpp</a>.</p>


<p>Referenced by <a href="#a227e7ddfafd6bce13cfb1473136e8230">runOnMachineFunction</a>.</p>

</div>
</div>

### MLI {#a62d7a42ca2e5768f90f26af63eff37df}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">MachineLoopInfo* anonymous{HexagonHardwareLoops.cpp}::HexagonHardwareLoops::MLI</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 101 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/hexagon/hexagonhardwareloops-cpp">HexagonHardwareLoops.cpp</a>.</p>


<p>Referenced by <a href="#a227e7ddfafd6bce13cfb1473136e8230">runOnMachineFunction</a>.</p>

</div>
</div>

### MRI {#ae58f8afe564f61fab4eb19ce22aae73e}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">MachineRegisterInfo* anonymous{HexagonHardwareLoops.cpp}::HexagonHardwareLoops::MRI</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 102 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/hexagon/hexagonhardwareloops-cpp">HexagonHardwareLoops.cpp</a>.</p>


<p>Referenced by <a href="#a227e7ddfafd6bce13cfb1473136e8230">runOnMachineFunction</a>.</p>

</div>
</div>

### TII {#a7b9acab12fb99432eab080e9197a13de}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">const HexagonInstrInfo* anonymous{HexagonHardwareLoops.cpp}::HexagonHardwareLoops::TII</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 104 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/hexagon/hexagonhardwareloops-cpp">HexagonHardwareLoops.cpp</a>.</p>


<p>Referenced by <a href="#a227e7ddfafd6bce13cfb1473136e8230">runOnMachineFunction</a>.</p>

</div>
</div>

### TRI {#a52c5d48e3e2a57f55fe88240a9cab9f1}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">const HexagonRegisterInfo* anonymous{HexagonHardwareLoops.cpp}::HexagonHardwareLoops::TRI</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 105 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/hexagon/hexagonhardwareloops-cpp">HexagonHardwareLoops.cpp</a>.</p>


<p>Referenced by <a href="#a227e7ddfafd6bce13cfb1473136e8230">runOnMachineFunction</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Public Static Attributes

### Counter {#aa2b7e4cd01f1099b9b7b906c0185377f}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">int anonymous{HexagonHardwareLoops.cpp}::HexagonHardwareLoops::Counter = 0</td>
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



<p>Definition at line 107 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/hexagon/hexagonhardwareloops-cpp">HexagonHardwareLoops.cpp</a>.</p>

</div>
</div>

### ID {#ac40b8dc6f6e7f12eee455df7fdd5acaa}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">char anonymous{HexagonHardwareLoops.cpp}::HexagonHardwareLoops::ID = 0</td>
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



<p>Definition at line 111 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/hexagon/hexagonhardwareloops-cpp">HexagonHardwareLoops.cpp</a>.</p>


<p>Referenced by <a href="#a7ba6007fbeaf7123afa98a38a0198dda">HexagonHardwareLoops</a>.</p>

</div>
</div>

</div>

<hr/>

The documentation for this struct was generated from the following file:

<ul>
<li><a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/hexagon/hexagonhardwareloops-cpp">HexagonHardwareLoops.cpp</a></li>
</ul>

<hr/>

<p class="doxyGeneratedBy">Generated via <a href="https://xpack.github.io/doxygen2docusaurus">doxygen2docusaurus</a> 2.0.0 by <a href="https://www.doxygen.nl">Doxygen</a> 1.15.0.</p>

</div>
