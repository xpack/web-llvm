---

# DO NOT EDIT!
# Automatically generated via doxygen2docusaurus by Doxygen.

slug: /api/structs/anonymous-riscvmovemerger-cpp-/riscvmovemerge
custom_edit_url: null
toc_max_heading_level: 4
keywords:
  - doxygen
  - reference
  - struct

---

<div class="doxyPage">

# `RISCVMoveMerge` Struct



## Declaration

<div class="doxyDeclaration">
struct anonymous{RISCVMoveMerger.cpp}::RISCVMoveMerge { ... }
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#af5cb4b8cf3ee73667519e9beb5b6363d">RISCVMoveMerge</a> ()</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#aefe1d24facac964502bfd8abb006eda2">isCandidateToMergeMVA01S</a> (const DestSourcePair &amp;RegPair)</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ac2bebd1f8090a2e93e2c53c4d206c5bc">isCandidateToMergeMVSA01</a> (const DestSourcePair &amp;RegPair)</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#accee7cec1672950ec100570be21cce47">mergePairedInsns</a> (MachineBasicBlock::iterator I, MachineBasicBlock::iterator Paired, unsigned Opcode)</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a2c18d64812a6868d590fb3f27d938312">findMatchingInst</a> (MachineBasicBlock::iterator &amp;MBBI, unsigned InstOpcode, const DestSourcePair &amp;RegPair)</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a975370ee01d6566ea29b13c31c4a7ade">mergeMoveSARegPair</a> (MachineBasicBlock &amp;MBB)</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ad200cfefbe78ae182babcc1c3211aa99">runOnMachineFunction</a> (MachineFunction &amp;Fn) override</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>runOnMachineFunction - This method must be overloaded to perform the desired machine code transformation or analysis. <a href="#ad200cfefbe78ae182babcc1c3211aa99">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/stringref">StringRef</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a0615e6f135b04c9da865d46d5b92c403">getPassName</a> () const override</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>getPassName - Return a nice clean name for a pass. <a href="#a0615e6f135b04c9da865d46d5b92c403">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

</table>

## Public Member Attributes Index

<table class="doxyMembersIndex">

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/riscvinstrinfo">RISCVInstrInfo</a> *</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a5be740c373d9d5b7f4cf2082ba7129f7">TII</a></td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#aea1936b436a30f68b085902949ce537c">TRI</a></td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/liveregunits">LiveRegUnits</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#afb41144671050844a245af1825577f99">ModifiedRegUnits</a></td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/liveregunits">LiveRegUnits</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a8c4171f87a5fbc5e6183a8fd1f4c6933">UsedRegUnits</a></td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#acec8106e7e0217ba7d4ff56958ec2496">ID</a> = 0</td>
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


<p>Definition at line 22 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/riscv/riscvmovemerger-cpp">RISCVMoveMerger.cpp</a>.</p>


<div class="doxySectionDef">

## Public Constructors

### RISCVMoveMerge() {#af5cb4b8cf3ee73667519e9beb5b6363d}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">anonymous{RISCVMoveMerger.cpp}::RISCVMoveMerge::RISCVMoveMerge ()</td>
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



<p>Definition at line 25 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/riscv/riscvmovemerger-cpp">RISCVMoveMerger.cpp</a>.</p>


<p>References <a href="#acec8106e7e0217ba7d4ff56958ec2496">ID</a> and <a href="/web-llvm/docs/api/classes/llvm/machinefunctionpass/#a29c81d2386f4a727c6d33413807530c8">llvm::MachineFunctionPass::MachineFunctionPass</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/namespaces/llvm/#a1351236443b144a9ad67fce1f7dea838">llvm::createRISCVMoveMergePass</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Public Member Functions

### findMatchingInst() {#a2c18d64812a6868d590fb3f27d938312}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">MachineBasicBlock::iterator RISCVMoveMerge::findMatchingInst (<a href="/web-llvm/docs/api/classes/llvm/machinebasicblock/#ae34c996b58df9b9ce6695a0c8b70c533">MachineBasicBlock::iterator</a> &amp; MBBI, unsigned InstOpcode, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/structs/llvm/destsourcepair">DestSourcePair</a> &amp; RegPair)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 44 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/riscv/riscvmovemerger-cpp">RISCVMoveMerger.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/classes/llvm/liveregunits/#a06c3c14971a6414e21bf3a0a2652de0f">llvm::LiveRegUnits::accumulateUsedDefed</a>, <a href="/web-llvm/docs/api/structs/llvm/destsourcepair/#add799c1daa8174a58f1713d2462eab37">llvm::DestSourcePair::Destination</a>, <a href="/web-llvm/docs/api/classes/llvm/machineoperand/#ac0035d7c1c860501c877c20e6e93297b">llvm::MachineOperand::getReg</a>, <a href="/web-llvm/docs/api/files/lib/lib/support/md5-cpp/#ac0eafdc9ee161b71e7af98af736952fd">I</a>, <a href="#aefe1d24facac964502bfd8abb006eda2">isCandidateToMergeMVA01S</a>, <a href="#ac2bebd1f8090a2e93e2c53c4d206c5bc">isCandidateToMergeMVSA01</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/arm/armslshardening-cpp/#ad5f691fdc1a09aaf6df5fef958b35a3d">MBBI</a>, <a href="/web-llvm/docs/api/files/lib/lib/codegen/lib/codegen/globalisel/irtranslator-cpp/#abe44dfdea65b4f7e11e0a608ab708b76">MI</a>, <a href="#afb41144671050844a245af1825577f99">ModifiedRegUnits</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a0270bdca4aeb43f39bf91c900a398057">llvm::next_nodbg</a>, <a href="/web-llvm/docs/api/structs/llvm/destsourcepair/#a52043c7b20f16c8bc3365fdc645a6481">llvm::DestSourcePair::Source</a>, <a href="#a5be740c373d9d5b7f4cf2082ba7129f7">TII</a>, <a href="#aea1936b436a30f68b085902949ce537c">TRI</a> and <a href="#a8c4171f87a5fbc5e6183a8fd1f4c6933">UsedRegUnits</a>.</p>


<p>Referenced by <a href="#aefe1d24facac964502bfd8abb006eda2">isCandidateToMergeMVA01S</a> and <a href="#a975370ee01d6566ea29b13c31c4a7ade">mergeMoveSARegPair</a>.</p>

</div>
</div>

### getPassName() {#a0615e6f135b04c9da865d46d5b92c403}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">StringRef anonymous{RISCVMoveMerger.cpp}::RISCVMoveMerge::getPassName ()</td>
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


<p>Definition at line 49 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/riscv/riscvmovemerger-cpp">RISCVMoveMerger.cpp</a>.</p>


<p>Reference <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/riscv/riscvmovemerger-cpp/#a9f51992be89bf5fb277a595eeb10b69b">RISCV_MOVE_MERGE_NAME</a>.</p>

</div>
</div>

### isCandidateToMergeMVA01S() {#aefe1d24facac964502bfd8abb006eda2}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool anonymous{RISCVMoveMerger.cpp}::RISCVMoveMerge::isCandidateToMergeMVA01S (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/structs/llvm/destsourcepair">DestSourcePair</a> &amp; RegPair)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 33 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/riscv/riscvmovemerger-cpp">RISCVMoveMerger.cpp</a>.</p>


<p>References <a href="#a2c18d64812a6868d590fb3f27d938312">findMatchingInst</a>, <a href="/web-llvm/docs/api/files/lib/lib/support/md5-cpp/#ac0eafdc9ee161b71e7af98af736952fd">I</a>, <a href="#ac2bebd1f8090a2e93e2c53c4d206c5bc">isCandidateToMergeMVSA01</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/arm/armslshardening-cpp/#a5958512eae2979bd2eb383977996a600">MBB</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/arm/armslshardening-cpp/#ad5f691fdc1a09aaf6df5fef958b35a3d">MBBI</a>, <a href="#a975370ee01d6566ea29b13c31c4a7ade">mergeMoveSARegPair</a>, <a href="#accee7cec1672950ec100570be21cce47">mergePairedInsns</a> and <a href="#ad200cfefbe78ae182babcc1c3211aa99">runOnMachineFunction</a>.</p>


<p>Referenced by <a href="#a2c18d64812a6868d590fb3f27d938312">findMatchingInst</a> and <a href="#a975370ee01d6566ea29b13c31c4a7ade">mergeMoveSARegPair</a>.</p>

</div>
</div>

### isCandidateToMergeMVSA01() {#ac2bebd1f8090a2e93e2c53c4d206c5bc}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool RISCVMoveMerge::isCandidateToMergeMVSA01 (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/structs/llvm/destsourcepair">DestSourcePair</a> &amp; RegPair)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 34 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/riscv/riscvmovemerger-cpp">RISCVMoveMerger.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/files/lib/lib/sandboxir/value-cpp/#a34433c37334a1cde3d58cde3099257dd">contains</a>, <a href="/web-llvm/docs/api/structs/llvm/destsourcepair/#add799c1daa8174a58f1713d2462eab37">llvm::DestSourcePair::Destination</a>, <a href="/web-llvm/docs/api/classes/llvm/machineoperand/#ac0035d7c1c860501c877c20e6e93297b">llvm::MachineOperand::getReg</a> and <a href="/web-llvm/docs/api/structs/llvm/destsourcepair/#a52043c7b20f16c8bc3365fdc645a6481">llvm::DestSourcePair::Source</a>.</p>


<p>Referenced by <a href="#a2c18d64812a6868d590fb3f27d938312">findMatchingInst</a>, <a href="#aefe1d24facac964502bfd8abb006eda2">isCandidateToMergeMVA01S</a> and <a href="#a975370ee01d6566ea29b13c31c4a7ade">mergeMoveSARegPair</a>.</p>

</div>
</div>

### mergeMoveSARegPair() {#a975370ee01d6566ea29b13c31c4a7ade}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool RISCVMoveMerge::mergeMoveSARegPair (<a href="/web-llvm/docs/api/classes/llvm/machinebasicblock">MachineBasicBlock</a> &amp; MBB)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 46 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/riscv/riscvmovemerger-cpp">RISCVMoveMerger.cpp</a>.</p>


<p>References <a href="#a2c18d64812a6868d590fb3f27d938312">findMatchingInst</a>, <a href="#aefe1d24facac964502bfd8abb006eda2">isCandidateToMergeMVA01S</a>, <a href="#ac2bebd1f8090a2e93e2c53c4d206c5bc">isCandidateToMergeMVSA01</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/arm/armslshardening-cpp/#a5958512eae2979bd2eb383977996a600">MBB</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/arm/armslshardening-cpp/#ad5f691fdc1a09aaf6df5fef958b35a3d">MBBI</a>, <a href="#accee7cec1672950ec100570be21cce47">mergePairedInsns</a>, <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/scalar/loopdeletion-cpp/#a0f1c83c3d08d80b12c424962a5e94ce8a35e0c8c0b180c95d4e122e55ed62cc64">Modified</a> and <a href="#a5be740c373d9d5b7f4cf2082ba7129f7">TII</a>.</p>


<p>Referenced by <a href="#aefe1d24facac964502bfd8abb006eda2">isCandidateToMergeMVA01S</a> and <a href="#ad200cfefbe78ae182babcc1c3211aa99">runOnMachineFunction</a>.</p>

</div>
</div>

### mergePairedInsns() {#accee7cec1672950ec100570be21cce47}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">MachineBasicBlock::iterator RISCVMoveMerge::mergePairedInsns (<a href="/web-llvm/docs/api/classes/llvm/machinebasicblock/#ae34c996b58df9b9ce6695a0c8b70c533">MachineBasicBlock::iterator</a> I, <a href="/web-llvm/docs/api/classes/llvm/machinebasicblock/#ae34c996b58df9b9ce6695a0c8b70c533">MachineBasicBlock::iterator</a> Paired, unsigned Opcode)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 37 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/riscv/riscvmovemerger-cpp">RISCVMoveMerger.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/classes/llvm/machineinstrbuilder/#a713eab58694282971c413a0d6de5975c">llvm::MachineInstrBuilder::add</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a17e04afcf0c5efeb0eb6a9a45287b5e4">llvm::BuildMI</a>, <a href="/web-llvm/docs/api/structs/llvm/destsourcepair/#add799c1daa8174a58f1713d2462eab37">llvm::DestSourcePair::Destination</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/arm/armslshardening-cpp/#ad467c4ab9119043f9b7750ab986be61a">DL</a>, <a href="/web-llvm/docs/api/classes/llvm/machineoperand/#ac0035d7c1c860501c877c20e6e93297b">llvm::MachineOperand::getReg</a>, <a href="/web-llvm/docs/api/files/lib/lib/support/md5-cpp/#ac0eafdc9ee161b71e7af98af736952fd">I</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a0270bdca4aeb43f39bf91c900a398057">llvm::next_nodbg</a>, <a href="/web-llvm/docs/api/structs/llvm/destsourcepair/#a52043c7b20f16c8bc3365fdc645a6481">llvm::DestSourcePair::Source</a> and <a href="#a5be740c373d9d5b7f4cf2082ba7129f7">TII</a>.</p>


<p>Referenced by <a href="#aefe1d24facac964502bfd8abb006eda2">isCandidateToMergeMVA01S</a> and <a href="#a975370ee01d6566ea29b13c31c4a7ade">mergeMoveSARegPair</a>.</p>

</div>
</div>

### runOnMachineFunction() {#ad200cfefbe78ae182babcc1c3211aa99}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool RISCVMoveMerge::runOnMachineFunction (<a href="/web-llvm/docs/api/classes/llvm/machinefunction">MachineFunction</a> &amp; MF)</td>
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

<p>Definition at line 47 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/riscv/riscvmovemerger-cpp">RISCVMoveMerger.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/classes/llvm/machinefunction/#a977ddce262de45c645be23d951066351">llvm::MachineFunction::getFunction</a>, <a href="/web-llvm/docs/api/classes/llvm/riscvsubtarget/#ad1484b3b6dbf33deb1c526d456f1d256">llvm::RISCVSubtarget::getInstrInfo</a>, <a href="/web-llvm/docs/api/classes/llvm/riscvsubtarget/#ac548025beac55d0f686dab8fa015e968">llvm::RISCVSubtarget::getRegisterInfo</a>, <a href="/web-llvm/docs/api/classes/llvm/machinefunction/#a3825368aca2bc1550d173660df4da6a6">llvm::MachineFunction::getSubtarget</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/arm/armslshardening-cpp/#a5958512eae2979bd2eb383977996a600">MBB</a>, <a href="#a975370ee01d6566ea29b13c31c4a7ade">mergeMoveSARegPair</a>, <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/scalar/loopdeletion-cpp/#a0f1c83c3d08d80b12c424962a5e94ce8a35e0c8c0b180c95d4e122e55ed62cc64">Modified</a>, <a href="#afb41144671050844a245af1825577f99">ModifiedRegUnits</a>, <a href="/web-llvm/docs/api/classes/llvm/functionpass/#af9f5f511d75e16f09a5520cb9444cfa8">llvm::FunctionPass::skipFunction</a>, <a href="#a5be740c373d9d5b7f4cf2082ba7129f7">TII</a>, <a href="#aea1936b436a30f68b085902949ce537c">TRI</a> and <a href="#a8c4171f87a5fbc5e6183a8fd1f4c6933">UsedRegUnits</a>.</p>


<p>Referenced by <a href="#aefe1d24facac964502bfd8abb006eda2">isCandidateToMergeMVA01S</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Public Member Attributes

### ModifiedRegUnits {#afb41144671050844a245af1825577f99}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">LiveRegUnits anonymous{RISCVMoveMerger.cpp}::RISCVMoveMerge::ModifiedRegUnits</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 31 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/riscv/riscvmovemerger-cpp">RISCVMoveMerger.cpp</a>.</p>


<p>Referenced by <a href="#a2c18d64812a6868d590fb3f27d938312">findMatchingInst</a> and <a href="#ad200cfefbe78ae182babcc1c3211aa99">runOnMachineFunction</a>.</p>

</div>
</div>

### TII {#a5be740c373d9d5b7f4cf2082ba7129f7}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">const RISCVInstrInfo* anonymous{RISCVMoveMerger.cpp}::RISCVMoveMerge::TII</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 27 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/riscv/riscvmovemerger-cpp">RISCVMoveMerger.cpp</a>.</p>


<p>Referenced by <a href="#a2c18d64812a6868d590fb3f27d938312">findMatchingInst</a>, <a href="#a975370ee01d6566ea29b13c31c4a7ade">mergeMoveSARegPair</a>, <a href="#accee7cec1672950ec100570be21cce47">mergePairedInsns</a> and <a href="#ad200cfefbe78ae182babcc1c3211aa99">runOnMachineFunction</a>.</p>

</div>
</div>

### TRI {#aea1936b436a30f68b085902949ce537c}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">const TargetRegisterInfo* anonymous{RISCVMoveMerger.cpp}::RISCVMoveMerge::TRI</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 28 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/riscv/riscvmovemerger-cpp">RISCVMoveMerger.cpp</a>.</p>


<p>Referenced by <a href="#a2c18d64812a6868d590fb3f27d938312">findMatchingInst</a> and <a href="#ad200cfefbe78ae182babcc1c3211aa99">runOnMachineFunction</a>.</p>

</div>
</div>

### UsedRegUnits {#a8c4171f87a5fbc5e6183a8fd1f4c6933}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">LiveRegUnits anonymous{RISCVMoveMerger.cpp}::RISCVMoveMerge::UsedRegUnits</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 31 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/riscv/riscvmovemerger-cpp">RISCVMoveMerger.cpp</a>.</p>


<p>Referenced by <a href="#a2c18d64812a6868d590fb3f27d938312">findMatchingInst</a> and <a href="#ad200cfefbe78ae182babcc1c3211aa99">runOnMachineFunction</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Public Static Attributes

### ID {#acec8106e7e0217ba7d4ff56958ec2496}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">char anonymous{RISCVMoveMerger.cpp}::RISCVMoveMerge::ID = 0</td>
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



<p>Definition at line 23 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/riscv/riscvmovemerger-cpp">RISCVMoveMerger.cpp</a>.</p>


<p>Referenced by <a href="#af5cb4b8cf3ee73667519e9beb5b6363d">RISCVMoveMerge</a>.</p>

</div>
</div>

</div>

<hr/>

The documentation for this struct was generated from the following file:

<ul>
<li><a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/riscv/riscvmovemerger-cpp">RISCVMoveMerger.cpp</a></li>
</ul>

<hr/>

<p class="doxyGeneratedBy">Generated via <a href="https://xpack.github.io/doxygen2docusaurus">doxygen2docusaurus</a> 2.0.0 by <a href="https://www.doxygen.nl">Doxygen</a> 1.15.0.</p>

</div>
