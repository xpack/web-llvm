---

# DO NOT EDIT!
# Automatically generated via doxygen2docusaurus by Doxygen.

slug: /api/files/lib/lib/target/lib/target/arm/armhazardrecognizer-cpp
custom_edit_url: null
toc_max_heading_level: 4
keywords:
  - doxygen
  - reference
  - file

---

<div class="doxyPage">

# `ARMHazardRecognizer.cpp` File



## Included Headers

<div class="doxyIncludesList">#include "<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/arm/armhazardrecognizer-h">ARMHazardRecognizer.h</a>"
#include "<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/arm/armbaseinstrinfo-h">ARMBaseInstrInfo.h</a>"
#include "<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/arm/armsubtarget-h">ARMSubtarget.h</a>"
#include "<a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/analysis/valuetracking-h">llvm/Analysis/ValueTracking.h</a>"
#include "<a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/codegen/machineframeinfo-h">llvm/CodeGen/MachineFrameInfo.h</a>"
#include "<a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/codegen/machineinstr-h">llvm/CodeGen/MachineInstr.h</a>"
#include "<a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/codegen/scheduledag-h">llvm/CodeGen/ScheduleDAG.h</a>"
#include "<a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/codegen/targetregisterinfo-h">llvm/CodeGen/TargetRegisterInfo.h</a>"
#include "<a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/support/commandline-h">llvm/Support/CommandLine.h</a>"
</div>

## Functions Index

<table class="doxyMembersIndex">

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">static bool</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#af4b92b87cdc1663f71632274fefb42c3">hasRAWHazard</a> (MachineInstr *DefMI, MachineInstr *MI, const TargetRegisterInfo &amp;TRI)</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">static bool</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a4ffed3cc477a8981df8115ca443f6992">getBaseOffset</a> (const MachineInstr &amp;MI, const MachineOperand *&amp;BaseOp, int64_t &amp;Offset)</td>
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

## Variables Index

<table class="doxyMembersIndex">

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">static <a href="/web-llvm/docs/api/classes/llvm/cl/opt">cl::opt</a>&lt; int &gt;</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a707897eedf4751ba5d1dfe4db88528e8">DataBankMask</a>("arm-data-bank-mask", cl::init(-1), cl::Hidden)</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">static <a href="/web-llvm/docs/api/classes/llvm/cl/opt">cl::opt</a>&lt; bool &gt;</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ab59518809c781040d5d916f63b20e111">AssumeITCMConflict</a>("arm-assume-itcm-bankconflict", cl::init(false), cl::Hidden)</td>
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


<div class="doxySectionDef">

## Functions

### getBaseOffset() {#a4ffed3cc477a8981df8115ca443f6992}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool getBaseOffset (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/machineinstr">MachineInstr</a> &amp; MI, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/machineoperand">MachineOperand</a> *&amp; BaseOp, int64_t &amp; Offset)</td>
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



<p>Definition at line 107 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/arm/armhazardrecognizer-cpp">ARMHazardRecognizer.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/namespaces/llvm/armii/#a3c06fab2f468e615484900041c216ef4aeda154c828d692cd52ca6cce8765f9ae">llvm::ARMII::AddrModeMask</a>, <a href="/web-llvm/docs/api/namespaces/llvm/armii/#ace99f086a3cd38c7477a8f038dae7ff4abfbcc124d3a4fa763e275b5b199fd81b">llvm::ARMII::AddrModeT1_1</a>, <a href="/web-llvm/docs/api/namespaces/llvm/armii/#ace99f086a3cd38c7477a8f038dae7ff4a45c1a7867d7bed69326c02dca510e4cc">llvm::ARMII::AddrModeT1_2</a>, <a href="/web-llvm/docs/api/namespaces/llvm/armii/#ace99f086a3cd38c7477a8f038dae7ff4a27e4e6aef06beef44d8cc58e32c22fdc">llvm::ARMII::AddrModeT1_4</a>, <a href="/web-llvm/docs/api/namespaces/llvm/armii/#ace99f086a3cd38c7477a8f038dae7ff4a4f27c00983ba7efdb7177e52c27584b9">llvm::ARMII::AddrModeT2_i12</a>, <a href="/web-llvm/docs/api/namespaces/llvm/armii/#ace99f086a3cd38c7477a8f038dae7ff4a976ddbecac99af6819d058790e33e137">llvm::ARMII::AddrModeT2_i8</a>, <a href="/web-llvm/docs/api/namespaces/llvm/armii/#ace99f086a3cd38c7477a8f038dae7ff4af3a6218c9c9bd03381633c799e5226d9">llvm::ARMII::AddrModeT2_i8s4</a>, <a href="/web-llvm/docs/api/namespaces/llvm/armii/#a3c06fab2f468e615484900041c216ef4a090893e44b7d8da1ed8e65cc6b586ae8">llvm::ARMII::IndexModeMask</a>, <a href="/web-llvm/docs/api/namespaces/llvm/armii/#ac3c83a9ce4f6ef1a90d63ebe5722b2b9ab9fd312a3c788e0bd21fc94e46cf5ab2">llvm::ARMII::IndexModePost</a>, <a href="/web-llvm/docs/api/namespaces/llvm/armii/#ac3c83a9ce4f6ef1a90d63ebe5722b2b9abf29846376f4da85457ab5fbc9dfcc70">llvm::ARMII::IndexModePre</a>, <a href="/web-llvm/docs/api/namespaces/llvm/armii/#a3c06fab2f468e615484900041c216ef4ac928721626de611c1e5c7acfd4e05f79">llvm::ARMII::IndexModeShift</a>, <a href="/web-llvm/docs/api/namespaces/llvm/armii/#ac3c83a9ce4f6ef1a90d63ebe5722b2b9a8170f98efa38651a1ae5d7a27d0ae19c">llvm::ARMII::IndexModeUpd</a>, <a href="/web-llvm/docs/api/files/lib/lib/codegen/lib/codegen/globalisel/irtranslator-cpp/#abe44dfdea65b4f7e11e0a608ab708b76">MI</a> and <a href="/web-llvm/docs/api/namespaces/llvm/#a05f5b9a11bdcc5feba62899f95dcf878a3134224cba2545bc57954d3b072aebb4">llvm::Offset</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/classes/llvm/armbankconflicthazardrecognizer/#abd3b799a5199979babb67c1211b73c7c">llvm::ARMBankConflictHazardRecognizer::getHazardType</a>.</p>

</div>
</div>

### hasRAWHazard() {#af4b92b87cdc1663f71632274fefb42c3}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool hasRAWHazard (<a href="/web-llvm/docs/api/classes/llvm/machineinstr">MachineInstr</a> * DefMI, <a href="/web-llvm/docs/api/classes/llvm/machineinstr">MachineInstr</a> * MI, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/targetregisterinfo">TargetRegisterInfo</a> &amp; TRI)</td>
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



<p>Definition at line 26 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/arm/armhazardrecognizer-cpp">ARMHazardRecognizer.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64expandpseudoinsts-cpp/#ad3ece0ac2421637044624c9b01c42466">DefMI</a>, <a href="/web-llvm/docs/api/namespaces/llvm/armii/#a3c06fab2f468e615484900041c216ef4a96db53f04326f6421725b16e4ee7a596">llvm::ARMII::DomainMask</a>, <a href="/web-llvm/docs/api/namespaces/llvm/armii/#a3c06fab2f468e615484900041c216ef4a0f4e17fd43419980264bba50ce572d60">llvm::ARMII::DomainNEON</a>, <a href="/web-llvm/docs/api/namespaces/llvm/armii/#a3c06fab2f468e615484900041c216ef4a0fecec4134a451feb93566a8a0a75ae1">llvm::ARMII::DomainVFP</a>, <a href="/web-llvm/docs/api/files/lib/lib/codegen/lib/codegen/globalisel/irtranslator-cpp/#abe44dfdea65b4f7e11e0a608ab708b76">MI</a> and <a href="/web-llvm/docs/api/files/lib/lib/codegen/machinesink-cpp/#a0f36ed1bc17fc1aa97fe291c439a0698">TRI</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/classes/llvm/armhazardrecognizerfpmlx/#af1064d4637b93e114f1d15631abdc03f">llvm::ARMHazardRecognizerFPMLx::getHazardType</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Variables

### AssumeITCMConflict {#ab59518809c781040d5d916f63b20e111}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">cl::opt&lt; bool &gt; AssumeITCMConflict("arm-assume-itcm-bankconflict", cl::init(false), cl::Hidden)</td>
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



<p>Definition at line 23 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/arm/armhazardrecognizer-cpp">ARMHazardRecognizer.cpp</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/classes/llvm/armbankconflicthazardrecognizer/#a6c5f31df055801e23fb3b8d1e5c77600">llvm::ARMBankConflictHazardRecognizer::ARMBankConflictHazardRecognizer</a>.</p>

</div>
</div>

### DataBankMask {#a707897eedf4751ba5d1dfe4db88528e8}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">cl::opt&lt; int &gt; DataBankMask("arm-data-bank-mask", cl::init(-1), cl::Hidden)</td>
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



<p>Definition at line 21 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/arm/armhazardrecognizer-cpp">ARMHazardRecognizer.cpp</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/classes/llvm/armbankconflicthazardrecognizer/#a6c5f31df055801e23fb3b8d1e5c77600">llvm::ARMBankConflictHazardRecognizer::ARMBankConflictHazardRecognizer</a>.</p>

</div>
</div>

</div>

<hr/>

<p class="doxyGeneratedBy">Generated via <a href="https://github.com/xpack/doxygen2docusaurus">doxygen2docusaurus</a> by <a href="https://www.doxygen.nl">Doxygen</a> 1.15.0.</p>

</div>
