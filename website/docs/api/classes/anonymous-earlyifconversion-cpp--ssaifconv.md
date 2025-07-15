---

# DO NOT EDIT!
# Automatically generated via doxygen2docusaurus by Doxygen.

slug: /api/classes/anonymous-earlyifconversion-cpp-/ssaifconv
custom_edit_url: null
toc_max_heading_level: 4
keywords:
  - doxygen
  - reference
  - class

---

<div class="doxyPage">

# The `SSAIfConv` Class Reference



## Declaration

<div class="doxyDeclaration">
class anonymous{EarlyIfConversion.cpp}::SSAIfConv { ... }
</div>

## Public Member Functions Index

<table class="doxyMembersIndex">

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">bool</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a3b593861590a1dcbc9347cbf328716a0">isTriangle</a> () const</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>isTriangle - When there is no 'else' block, either TBB or FBB will be equal to Tail. <a href="#a3b593861590a1dcbc9347cbf328716a0">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/machinebasicblock">MachineBasicBlock</a> *</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a1ca88bfdd49d84f433b3fafe21f3e405">getTPred</a> () const</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Returns the Tail predecessor for the True side. <a href="#a1ca88bfdd49d84f433b3fafe21f3e405">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/machinebasicblock">MachineBasicBlock</a> *</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#af57530f34a5e06746f55f54be2883063">getFPred</a> () const</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Returns the Tail predecessor for the False side. <a href="#af57530f34a5e06746f55f54be2883063">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">void</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#af3aabd84356a278f0f3c9c91e17a7ad6">init</a> (MachineFunction &amp;MF)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>init - Initialize per-function data structures. <a href="#af3aabd84356a278f0f3c9c91e17a7ad6">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">bool</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ad73f79350d54fe535469c4a148943e3a">canConvertIf</a> (MachineBasicBlock *MBB, bool Predicate=false)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>canConvertIf - If the sub-CFG headed by MBB can be if-converted, initialize the internal state, and return true. <a href="#ad73f79350d54fe535469c4a148943e3a">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">void</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a97a97757150c110b5bceb79ae0fedc1f">convertIf</a> (SmallVectorImpl&lt; MachineBasicBlock * &gt; &amp;RemoveBlocks, bool Predicate=false)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>convertIf - If-convert the last block passed to <a href="#ad73f79350d54fe535469c4a148943e3a">canConvertIf()</a>, assuming it is possible. <a href="#a97a97757150c110b5bceb79ae0fedc1f">More...</a></p>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#afd124267ebb1dac07ea430c9c972df30">canSpeculateInstrs</a> (MachineBasicBlock *MBB)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Return true if all non-terminator instructions in MBB can be safely speculated. <a href="#afd124267ebb1dac07ea430c9c972df30">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">bool</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a119c82679da82706e636a64abedbe783">canPredicateInstrs</a> (MachineBasicBlock *MBB)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Return true if all non-terminator instructions in MBB can be safely predicated. <a href="#a119c82679da82706e636a64abedbe783">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">bool</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a1a41d44033d3fbc13cd7552a4a739395">InstrDependenciesAllowIfConv</a> (MachineInstr *I)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Scan through instruction dependencies and update InsertAfter array. <a href="#a1a41d44033d3fbc13cd7552a4a739395">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">void</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a20c380bd19b7fb1b0bd4dcc43bbde79d">PredicateBlock</a> (MachineBasicBlock *MBB, bool ReversePredicate)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p><a href="/web-llvm/docs/api/classes/predicate">Predicate</a> all instructions of the basic block with current condition except for terminators. <a href="#a20c380bd19b7fb1b0bd4dcc43bbde79d">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">bool</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a20eab3651bf239488a271898bb2259bb">findInsertionPoint</a> ()</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Find a valid insertion point in Head. <a href="#a20eab3651bf239488a271898bb2259bb">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">void</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a3d4ad9bdf4c8464c29b50d2958b84327">replacePHIInstrs</a> ()</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Replace PHI instructions in Tail with selects. <a href="#a3d4ad9bdf4c8464c29b50d2958b84327">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">void</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#adbfc8fedd475e0bb6f6d3cb8a172c613">rewritePHIOperands</a> ()</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Insert selects and rewrite PHI operands to use them. <a href="#adbfc8fedd475e0bb6f6d3cb8a172c613">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

</table>

## Public Member Attributes Index

<table class="doxyMembersIndex">

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/machinebasicblock">MachineBasicBlock</a> *</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ad6bc8960aa2f6e095e5c0e5f94e5346f">Head</a></td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>The block containing the conditional branch. <a href="#ad6bc8960aa2f6e095e5c0e5f94e5346f">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/machinebasicblock">MachineBasicBlock</a> *</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a4dd1e49b0b30ae3bb5c38830b7746c2d">Tail</a></td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>The block containing phis after the if-then-else. <a href="#a4dd1e49b0b30ae3bb5c38830b7746c2d">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/machinebasicblock">MachineBasicBlock</a> *</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a1b3b3598bb57cd2effa9855494991ec0">TBB</a></td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>The 'true' conditional block as determined by analyzeBranch. <a href="#a1b3b3598bb57cd2effa9855494991ec0">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/machinebasicblock">MachineBasicBlock</a> *</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ac8887eea1c886be7e0f815b255858620">FBB</a></td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>The 'false' conditional block as determined by analyzeBranch. <a href="#ac8887eea1c886be7e0f815b255858620">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/smallvector">SmallVector</a>&lt; <a href="/web-llvm/docs/api/structs/anonymous-earlyifconversion-cpp-/ssaifconv/phiinfo">PHIInfo</a>, 8 &gt;</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a3c87a2cc5c7078904af87a008e6abc28">PHIs</a></td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/smallvector">SmallVector</a>&lt; <a href="/web-llvm/docs/api/classes/llvm/machineoperand">MachineOperand</a>, 4 &gt;</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a21312f1e765687ad983427e2d56acba2">Cond</a></td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>The branch condition determined by analyzeBranch. <a href="#a21312f1e765687ad983427e2d56acba2">More...</a></p>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a880025d7747eb7c79382fd05820cc1c8">TII</a></td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#aa98eddf15c3c34666109b769d15a34a7">TRI</a></td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ae3f1cf2f8f357401e2cb44bd96fd0380">MRI</a></td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/smallptrset">SmallPtrSet</a>&lt; <a href="/web-llvm/docs/api/classes/llvm/machineinstr">MachineInstr</a> *, 8 &gt;</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a5a18f2ac8debb03aa41e443d13c43655">InsertAfter</a></td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Instructions in Head that define values used by the conditional blocks. <a href="#a5a18f2ac8debb03aa41e443d13c43655">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/bitvector">BitVector</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a6c18c59fd4efcf28c5fdb12faf6046d7">ClobberedRegUnits</a></td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p><a href="/web-llvm/docs/api/classes/llvm/register">Register</a> units clobbered by the conditional blocks. <a href="#a6c18c59fd4efcf28c5fdb12faf6046d7">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/sparseset">SparseSet</a>&lt; unsigned &gt;</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a4bb154da909ffcd16d9066c8e7980d15">LiveRegUnits</a></td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/machinebasicblock/#ae34c996b58df9b9ce6695a0c8b70c533">MachineBasicBlock::iterator</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a4bdf27b0dba16bde26dd8a328a5ace99">InsertionPoint</a></td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Insertion point in Head for speculatively executed instructions form TBB and FBB. <a href="#a4bdf27b0dba16bde26dd8a328a5ace99">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

</table>


<p>Definition at line 83 of file <a href="/web-llvm/docs/api/files/lib/lib/codegen/earlyifconversion-cpp">EarlyIfConversion.cpp</a>.</p>


<div class="doxySectionDef">

## Public Member Functions

### canConvertIf() {#ad73f79350d54fe535469c4a148943e3a}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool SSAIfConv::canConvertIf (<a href="/web-llvm/docs/api/classes/llvm/machinebasicblock">MachineBasicBlock</a> * MBB, bool Predicate=false)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>canConvertIf - If the sub-CFG headed by MBB can be if-converted, initialize the internal state, and return true.</p>


<p>canConvertIf - analyze the sub-cfg rooted in MBB, and return true if it is a potential candidate for if-conversion.</p>


<p>If predicate is set try to predicate the block otherwise try to speculatively execute it.</p>


<p>Fill out the internal state.</p>


<p>Definition at line 182 of file <a href="/web-llvm/docs/api/files/lib/lib/codegen/earlyifconversion-cpp">EarlyIfConversion.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/silowercontrolflow-cpp/#a4868c5d81c5ccc98c47aeab6244346a0">assert</a>, <a href="#a21312f1e765687ad983427e2d56acba2">Cond</a>, <a href="/web-llvm/docs/api/structs/anonymous-earlyifconversion-cpp-/ssaifconv/phiinfo/#a3a9f081155f41f6d60057df747552e26">anonymous{EarlyIfConversion.cpp}::SSAIfConv::PHIInfo::CondCycles</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a7c46c742c31be54870e2038048e6b391">llvm::dbgs</a>, <a href="#ac8887eea1c886be7e0f815b255858620">FBB</a>, <a href="/web-llvm/docs/api/structs/anonymous-earlyifconversion-cpp-/ssaifconv/phiinfo/#a819adab6311032e0ca5c1d47860acd61">anonymous{EarlyIfConversion.cpp}::SSAIfConv::PHIInfo::FCycles</a>, <a href="/web-llvm/docs/api/structs/anonymous-earlyifconversion-cpp-/ssaifconv/phiinfo/#abc1a53d3e7659ab129bebc327851fa7c">anonymous{EarlyIfConversion.cpp}::SSAIfConv::PHIInfo::FReg</a>, <a href="#af57530f34a5e06746f55f54be2883063">getFPred</a>, <a href="/web-llvm/docs/api/classes/llvm/machineoperand/#a57e64b633278df75c699e6b98ce15031">llvm::MachineOperand::getMBB</a>, <a href="/web-llvm/docs/api/classes/llvm/machineinstr/#a432824f0975bb863478bf4ef3a5df258">llvm::MachineInstr::getNumOperands</a>, <a href="/web-llvm/docs/api/classes/llvm/machineinstr/#ad67c9230577a0b640c52852c75c93939">llvm::MachineInstr::getOperand</a>, <a href="/web-llvm/docs/api/classes/llvm/machineoperand/#ac0035d7c1c860501c877c20e6e93297b">llvm::MachineOperand::getReg</a>, <a href="#a1ca88bfdd49d84f433b3fafe21f3e405">getTPred</a>, <a href="#ad6bc8960aa2f6e095e5c0e5f94e5346f">Head</a>, <a href="/web-llvm/docs/api/files/lib/lib/support/md5-cpp/#ac0eafdc9ee161b71e7af98af736952fd">I</a>, <a href="#a3b593861590a1dcbc9347cbf328716a0">isTriangle</a>, <a href="/web-llvm/docs/api/classes/llvm/register/#ac6bf744f357352cde7578931007c0b6f">llvm::Register::isVirtualRegister</a>, <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/support/debug-h/#a196897517069dda1bdb549e24468f7d7">LLVM_DEBUG</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/arm/armslshardening-cpp/#a5958512eae2979bd2eb383977996a600">MBB</a>, <a href="/web-llvm/docs/api/structs/anonymous-earlyifconversion-cpp-/ssaifconv/phiinfo/#a0e9c227e7b5e1c0c54f4ec6e01a886ed">anonymous{EarlyIfConversion.cpp}::SSAIfConv::PHIInfo::PHI</a>, <a href="#a3c87a2cc5c7078904af87a008e6abc28">PHIs</a>, <a href="/web-llvm/docs/api/classes/llvm/machinebasicblock/#a03936a9b37da541420049422204ab206">llvm::MachineBasicBlock::pred_size</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#af7881286e3ea4d7f1c4a63c87c132dac">llvm::printMBBReference</a>, <a href="/web-llvm/docs/api/classes/llvm/machinebasicblock/#a6321b189ea8fd5058663f8a87d6c23e9">llvm::MachineBasicBlock::succ_begin</a>, <a href="/web-llvm/docs/api/classes/llvm/machinebasicblock/#a81626de817a0cb021ff8e915cf1942ed">llvm::MachineBasicBlock::succ_size</a>, <a href="/web-llvm/docs/api/namespaces/std/#ab8424022895aee3e366fb9a32f2883cb">std::swap</a>, <a href="#a4dd1e49b0b30ae3bb5c38830b7746c2d">Tail</a>, <a href="#a1b3b3598bb57cd2effa9855494991ec0">TBB</a>, <a href="/web-llvm/docs/api/structs/anonymous-earlyifconversion-cpp-/ssaifconv/phiinfo/#a6d8ce1a758100bc574487f06392d73cd">anonymous{EarlyIfConversion.cpp}::SSAIfConv::PHIInfo::TCycles</a> and <a href="/web-llvm/docs/api/structs/anonymous-earlyifconversion-cpp-/ssaifconv/phiinfo/#ac328beb7b3b253c454f85d42a621423f">anonymous{EarlyIfConversion.cpp}::SSAIfConv::PHIInfo::TReg</a>.</p>

</div>
</div>

### convertIf() {#a97a97757150c110b5bceb79ae0fedc1f}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void SSAIfConv::convertIf (<a href="/web-llvm/docs/api/classes/llvm/smallvectorimpl">SmallVectorImpl</a>&lt; <a href="/web-llvm/docs/api/classes/llvm/machinebasicblock">MachineBasicBlock</a> * &gt; &amp; RemoveBlocks, bool Predicate=false)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>convertIf - If-convert the last block passed to <a href="#ad73f79350d54fe535469c4a148943e3a">canConvertIf()</a>, assuming it is possible.</p>


<p>convertIf - Execute the if conversion after canConvertIf has determined the feasibility.</p>


<p>Add any blocks that are to be erased to RemoveBlocks.</p>


<p><a href="/web-llvm/docs/api/classes/llvm/any">Any</a> basic blocks that need to be erased will be added to RemoveBlocks.</p>


<p>Definition at line 186 of file <a href="/web-llvm/docs/api/files/lib/lib/codegen/earlyifconversion-cpp">EarlyIfConversion.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/silowercontrolflow-cpp/#a4868c5d81c5ccc98c47aeab6244346a0">assert</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a7c46c742c31be54870e2038048e6b391">llvm::dbgs</a>, <a href="#ac8887eea1c886be7e0f815b255858620">FBB</a>, <a href="#ad6bc8960aa2f6e095e5c0e5f94e5346f">Head</a>, <a href="#a3b593861590a1dcbc9347cbf328716a0">isTriangle</a>, <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/support/debug-h/#a196897517069dda1bdb549e24468f7d7">LLVM_DEBUG</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#af7881286e3ea4d7f1c4a63c87c132dac">llvm::printMBBReference</a>, <a href="/web-llvm/docs/api/classes/llvm/smallvectortemplatebase/#af42bfbc067df27c19ee2fc859df58799">llvm::SmallVectorTemplateBase&lt; T, bool &gt;::push_back</a>, <a href="#a4dd1e49b0b30ae3bb5c38830b7746c2d">Tail</a> and <a href="#a1b3b3598bb57cd2effa9855494991ec0">TBB</a>.</p>

</div>
</div>

### getFPred() {#af57530f34a5e06746f55f54be2883063}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">MachineBasicBlock * anonymous{EarlyIfConversion.cpp}::SSAIfConv::getFPred ()</td>
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

<p>Returns the Tail predecessor for the False side.</p>

<p>Definition at line 109 of file <a href="/web-llvm/docs/api/files/lib/lib/codegen/earlyifconversion-cpp">EarlyIfConversion.cpp</a>.</p>


<p>References <a href="#ac8887eea1c886be7e0f815b255858620">FBB</a>, <a href="#ad6bc8960aa2f6e095e5c0e5f94e5346f">Head</a> and <a href="#a4dd1e49b0b30ae3bb5c38830b7746c2d">Tail</a>.</p>


<p>Referenced by <a href="#ad73f79350d54fe535469c4a148943e3a">canConvertIf</a>.</p>

</div>
</div>

### getTPred() {#a1ca88bfdd49d84f433b3fafe21f3e405}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">MachineBasicBlock * anonymous{EarlyIfConversion.cpp}::SSAIfConv::getTPred ()</td>
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

<p>Returns the Tail predecessor for the True side.</p>

<p>Definition at line 106 of file <a href="/web-llvm/docs/api/files/lib/lib/codegen/earlyifconversion-cpp">EarlyIfConversion.cpp</a>.</p>


<p>References <a href="#ad6bc8960aa2f6e095e5c0e5f94e5346f">Head</a>, <a href="#a4dd1e49b0b30ae3bb5c38830b7746c2d">Tail</a> and <a href="#a1b3b3598bb57cd2effa9855494991ec0">TBB</a>.</p>


<p>Referenced by <a href="#ad73f79350d54fe535469c4a148943e3a">canConvertIf</a>.</p>

</div>
</div>

### init() {#af3aabd84356a278f0f3c9c91e17a7ad6}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void anonymous{EarlyIfConversion.cpp}::SSAIfConv::init (<a href="/web-llvm/docs/api/classes/llvm/machinefunction">MachineFunction</a> &amp; MF)</td>
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

<p>init - Initialize per-function data structures.</p>

<p>Definition at line 168 of file <a href="/web-llvm/docs/api/files/lib/lib/codegen/earlyifconversion-cpp">EarlyIfConversion.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/classes/llvm/targetsubtargetinfo/#acd858ed72f11db9444617740c3622608">llvm::TargetSubtargetInfo::getInstrInfo</a>, <a href="/web-llvm/docs/api/classes/llvm/machinefunction/#a810234b6b3d223b7c74a4253fcc5ea5e">llvm::MachineFunction::getRegInfo</a>, <a href="/web-llvm/docs/api/classes/llvm/targetsubtargetinfo/#a43c530c830206ecf5ad3359364634c75">llvm::TargetSubtargetInfo::getRegisterInfo</a> and <a href="/web-llvm/docs/api/classes/llvm/machinefunction/#a3825368aca2bc1550d173660df4da6a6">llvm::MachineFunction::getSubtarget</a>.</p>

</div>
</div>

### isTriangle() {#a3b593861590a1dcbc9347cbf328716a0}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool anonymous{EarlyIfConversion.cpp}::SSAIfConv::isTriangle ()</td>
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

<p>isTriangle - When there is no 'else' block, either TBB or FBB will be equal to Tail.</p>

<p>Definition at line 103 of file <a href="/web-llvm/docs/api/files/lib/lib/codegen/earlyifconversion-cpp">EarlyIfConversion.cpp</a>.</p>


<p>References <a href="#ac8887eea1c886be7e0f815b255858620">FBB</a>, <a href="#a4dd1e49b0b30ae3bb5c38830b7746c2d">Tail</a> and <a href="#a1b3b3598bb57cd2effa9855494991ec0">TBB</a>.</p>


<p>Referenced by <a href="#ad73f79350d54fe535469c4a148943e3a">canConvertIf</a> and <a href="#a97a97757150c110b5bceb79ae0fedc1f">convertIf</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Private Member Functions

### canPredicateInstrs() {#a119c82679da82706e636a64abedbe783}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool SSAIfConv::canPredicateInstrs (<a href="/web-llvm/docs/api/classes/llvm/machinebasicblock">MachineBasicBlock</a> * MBB)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Return true if all non-terminator instructions in MBB can be safely predicated.</p>


<p>canPredicateInstrs - Returns true if all the instructions in MBB can safely be predicates.</p>


<p>The terminators are not considered.</p>


<p>If instructions use any values that are defined in the head basic block, the defining instructions are added to InsertAfter.</p>


<p><a href="/web-llvm/docs/api/classes/llvm/any">Any</a> clobbered regunits are added to ClobberedRegUnits.</p>


<p>Definition at line 147 of file <a href="/web-llvm/docs/api/files/lib/lib/codegen/earlyifconversion-cpp">EarlyIfConversion.cpp</a>.</p>

</div>
</div>

### canSpeculateInstrs() {#afd124267ebb1dac07ea430c9c972df30}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool SSAIfConv::canSpeculateInstrs (<a href="/web-llvm/docs/api/classes/llvm/machinebasicblock">MachineBasicBlock</a> * MBB)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Return true if all non-terminator instructions in MBB can be safely speculated.</p>


<p>canSpeculateInstrs - Returns true if all the instructions in MBB can safely be speculated.</p>


<p>The terminators are not considered.</p>


<p>If instructions use any values that are defined in the head basic block, the defining instructions are added to InsertAfter.</p>


<p><a href="/web-llvm/docs/api/classes/llvm/any">Any</a> clobbered regunits are added to ClobberedRegUnits.</p>


<p>Definition at line 143 of file <a href="/web-llvm/docs/api/files/lib/lib/codegen/earlyifconversion-cpp">EarlyIfConversion.cpp</a>.</p>

</div>
</div>

### findInsertionPoint() {#a20eab3651bf239488a271898bb2259bb}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool SSAIfConv::findInsertionPoint ()</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Find a valid insertion point in Head.</p>


<p>Find an insertion point in Head for the speculated instructions.</p>


<p>The insertion point must be:</p>


<ol class="doxyList" type="1">
<li>Before any terminators.</li>
<li>After any instructions in InsertAfter.</li>
<li>Not have any clobbered regunits live.</li>
</ol>

<p>This function sets <a href="/web-llvm/docs/api/structs/insertionpoint">InsertionPoint</a> and returns true when successful, it returns false if no valid insertion point could be found.</p>


<p>Definition at line 158 of file <a href="/web-llvm/docs/api/files/lib/lib/codegen/earlyifconversion-cpp">EarlyIfConversion.cpp</a>.</p>

</div>
</div>

### InstrDependenciesAllowIfConv() {#a1a41d44033d3fbc13cd7552a4a739395}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool SSAIfConv::InstrDependenciesAllowIfConv (<a href="/web-llvm/docs/api/classes/llvm/machineinstr">MachineInstr</a> * I)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Scan through instruction dependencies and update InsertAfter array.</p>


<p>Check that there is no dependencies preventing if conversion.</p>


<p>Return false if any dependency is incompatible with if conversion.</p>


<p>If instruction uses any values that are defined in the head basic block, the defining instructions are added to InsertAfter.</p>


<p>Definition at line 151 of file <a href="/web-llvm/docs/api/files/lib/lib/codegen/earlyifconversion-cpp">EarlyIfConversion.cpp</a>.</p>

</div>
</div>

### PredicateBlock() {#a20c380bd19b7fb1b0bd4dcc43bbde79d}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void SSAIfConv::PredicateBlock (<a href="/web-llvm/docs/api/classes/llvm/machinebasicblock">MachineBasicBlock</a> * MBB, bool ReversePredicate)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p><a href="/web-llvm/docs/api/classes/predicate">Predicate</a> all instructions of the basic block with current condition except for terminators.</p>


<p>Reverse the condition if ReversePredicate is set.</p>


<p>Definition at line 155 of file <a href="/web-llvm/docs/api/files/lib/lib/codegen/earlyifconversion-cpp">EarlyIfConversion.cpp</a>.</p>

</div>
</div>

### replacePHIInstrs() {#a3d4ad9bdf4c8464c29b50d2958b84327}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void SSAIfConv::replacePHIInstrs ()</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Replace PHI instructions in Tail with selects.</p>


<p>replacePHIInstrs - Completely replace PHI instructions with selects.</p>


<p>This is possible when the only Tail predecessors are the if-converted blocks.</p>


<p>Definition at line 161 of file <a href="/web-llvm/docs/api/files/lib/lib/codegen/earlyifconversion-cpp">EarlyIfConversion.cpp</a>.</p>

</div>
</div>

### rewritePHIOperands() {#adbfc8fedd475e0bb6f6d3cb8a172c613}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void SSAIfConv::rewritePHIOperands ()</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Insert selects and rewrite PHI operands to use them.</p>


<p>rewritePHIOperands - When there are additional Tail predecessors, insert select instructions in Head and rewrite PHI operands to use the selects.</p>


<p>Keep the PHI instructions in Tail to handle the other predecessors.</p>


<p>Definition at line 164 of file <a href="/web-llvm/docs/api/files/lib/lib/codegen/earlyifconversion-cpp">EarlyIfConversion.cpp</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Public Member Attributes

### Cond {#a21312f1e765687ad983427e2d56acba2}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">SmallVector&lt;MachineOperand, 4&gt; anonymous{EarlyIfConversion.cpp}::SSAIfConv::Cond</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>The branch condition determined by analyzeBranch.</p>

<p>Definition at line 124 of file <a href="/web-llvm/docs/api/files/lib/lib/codegen/earlyifconversion-cpp">EarlyIfConversion.cpp</a>.</p>


<p>Referenced by <a href="#ad73f79350d54fe535469c4a148943e3a">canConvertIf</a>.</p>

</div>
</div>

### FBB {#ac8887eea1c886be7e0f815b255858620}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">MachineBasicBlock* anonymous{EarlyIfConversion.cpp}::SSAIfConv::FBB</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>The 'false' conditional block as determined by analyzeBranch.</p>

<p>Definition at line 99 of file <a href="/web-llvm/docs/api/files/lib/lib/codegen/earlyifconversion-cpp">EarlyIfConversion.cpp</a>.</p>


<p>Referenced by <a href="#ad73f79350d54fe535469c4a148943e3a">canConvertIf</a>, <a href="#a97a97757150c110b5bceb79ae0fedc1f">convertIf</a>, <a href="#af57530f34a5e06746f55f54be2883063">getFPred</a> and <a href="#a3b593861590a1dcbc9347cbf328716a0">isTriangle</a>.</p>

</div>
</div>

### Head {#ad6bc8960aa2f6e095e5c0e5f94e5346f}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">MachineBasicBlock* anonymous{EarlyIfConversion.cpp}::SSAIfConv::Head</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>The block containing the conditional branch.</p>

<p>Definition at line 90 of file <a href="/web-llvm/docs/api/files/lib/lib/codegen/earlyifconversion-cpp">EarlyIfConversion.cpp</a>.</p>


<p>Referenced by <a href="#ad73f79350d54fe535469c4a148943e3a">canConvertIf</a>, <a href="#a97a97757150c110b5bceb79ae0fedc1f">convertIf</a>, <a href="#af57530f34a5e06746f55f54be2883063">getFPred</a>, <a href="#a1ca88bfdd49d84f433b3fafe21f3e405">getTPred</a> and <a href="/web-llvm/docs/api/namespaces/anonymous-earlyifconversion-cpp-/#a35766d8bc1206e4e88ebb72f397c0296">anonymous{EarlyIfConversion.cpp}::updateDomTree</a>.</p>

</div>
</div>

### PHIs {#a3c87a2cc5c7078904af87a008e6abc28}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">SmallVector&lt;PHIInfo, 8&gt; anonymous{EarlyIfConversion.cpp}::SSAIfConv::PHIs</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 121 of file <a href="/web-llvm/docs/api/files/lib/lib/codegen/earlyifconversion-cpp">EarlyIfConversion.cpp</a>.</p>


<p>Referenced by <a href="#ad73f79350d54fe535469c4a148943e3a">canConvertIf</a>.</p>

</div>
</div>

### Tail {#a4dd1e49b0b30ae3bb5c38830b7746c2d}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">MachineBasicBlock* anonymous{EarlyIfConversion.cpp}::SSAIfConv::Tail</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>The block containing phis after the if-then-else.</p>

<p>Definition at line 93 of file <a href="/web-llvm/docs/api/files/lib/lib/codegen/earlyifconversion-cpp">EarlyIfConversion.cpp</a>.</p>


<p>Referenced by <a href="#ad73f79350d54fe535469c4a148943e3a">canConvertIf</a>, <a href="#a97a97757150c110b5bceb79ae0fedc1f">convertIf</a>, <a href="#af57530f34a5e06746f55f54be2883063">getFPred</a>, <a href="#a1ca88bfdd49d84f433b3fafe21f3e405">getTPred</a>, <a href="#a3b593861590a1dcbc9347cbf328716a0">isTriangle</a> and <a href="/web-llvm/docs/api/namespaces/anonymous-earlyifconversion-cpp-/#a35766d8bc1206e4e88ebb72f397c0296">anonymous{EarlyIfConversion.cpp}::updateDomTree</a>.</p>

</div>
</div>

### TBB {#a1b3b3598bb57cd2effa9855494991ec0}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">MachineBasicBlock* anonymous{EarlyIfConversion.cpp}::SSAIfConv::TBB</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>The 'true' conditional block as determined by analyzeBranch.</p>

<p>Definition at line 96 of file <a href="/web-llvm/docs/api/files/lib/lib/codegen/earlyifconversion-cpp">EarlyIfConversion.cpp</a>.</p>


<p>Referenced by <a href="#ad73f79350d54fe535469c4a148943e3a">canConvertIf</a>, <a href="#a97a97757150c110b5bceb79ae0fedc1f">convertIf</a>, <a href="#a1ca88bfdd49d84f433b3fafe21f3e405">getTPred</a> and <a href="#a3b593861590a1dcbc9347cbf328716a0">isTriangle</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Private Member Attributes

### ClobberedRegUnits {#a6c18c59fd4efcf28c5fdb12faf6046d7}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">BitVector anonymous{EarlyIfConversion.cpp}::SSAIfConv::ClobberedRegUnits</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p><a href="/web-llvm/docs/api/classes/llvm/register">Register</a> units clobbered by the conditional blocks.</p>

<p>Definition at line 132 of file <a href="/web-llvm/docs/api/files/lib/lib/codegen/earlyifconversion-cpp">EarlyIfConversion.cpp</a>.</p>

</div>
</div>

### InsertAfter {#a5a18f2ac8debb03aa41e443d13c43655}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">SmallPtrSet&lt;MachineInstr*, 8&gt; anonymous{EarlyIfConversion.cpp}::SSAIfConv::InsertAfter</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Instructions in Head that define values used by the conditional blocks.</p>


<p>The hoisted instructions must be inserted after these instructions.</p>


<p>Definition at line 129 of file <a href="/web-llvm/docs/api/files/lib/lib/codegen/earlyifconversion-cpp">EarlyIfConversion.cpp</a>.</p>

</div>
</div>

### InsertionPoint {#a4bdf27b0dba16bde26dd8a328a5ace99}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">MachineBasicBlock::iterator anonymous{EarlyIfConversion.cpp}::SSAIfConv::InsertionPoint</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Insertion point in Head for speculatively executed instructions form TBB and FBB.</p>

<p>Definition at line 139 of file <a href="/web-llvm/docs/api/files/lib/lib/codegen/earlyifconversion-cpp">EarlyIfConversion.cpp</a>.</p>

</div>
</div>

### LiveRegUnits {#a4bb154da909ffcd16d9066c8e7980d15}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">SparseSet&lt;unsigned&gt; anonymous{EarlyIfConversion.cpp}::SSAIfConv::LiveRegUnits</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 135 of file <a href="/web-llvm/docs/api/files/lib/lib/codegen/earlyifconversion-cpp">EarlyIfConversion.cpp</a>.</p>

</div>
</div>

### MRI {#ae3f1cf2f8f357401e2cb44bd96fd0380}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">MachineRegisterInfo* anonymous{EarlyIfConversion.cpp}::SSAIfConv::MRI</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 86 of file <a href="/web-llvm/docs/api/files/lib/lib/codegen/earlyifconversion-cpp">EarlyIfConversion.cpp</a>.</p>

</div>
</div>

### TII {#a880025d7747eb7c79382fd05820cc1c8}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">const TargetInstrInfo* anonymous{EarlyIfConversion.cpp}::SSAIfConv::TII</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 84 of file <a href="/web-llvm/docs/api/files/lib/lib/codegen/earlyifconversion-cpp">EarlyIfConversion.cpp</a>.</p>

</div>
</div>

### TRI {#aa98eddf15c3c34666109b769d15a34a7}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">const TargetRegisterInfo* anonymous{EarlyIfConversion.cpp}::SSAIfConv::TRI</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 85 of file <a href="/web-llvm/docs/api/files/lib/lib/codegen/earlyifconversion-cpp">EarlyIfConversion.cpp</a>.</p>

</div>
</div>

</div>

<hr/>

The documentation for this class was generated from the following file:

<ul>
<li><a href="/web-llvm/docs/api/files/lib/lib/codegen/earlyifconversion-cpp">EarlyIfConversion.cpp</a></li>
</ul>

<hr/>

<p class="doxyGeneratedBy">Generated via <a href="https://github.com/xpack/doxygen2docusaurus">doxygen2docusaurus</a> by <a href="https://www.doxygen.nl">Doxygen</a> 1.14.0.</p>

</div>
