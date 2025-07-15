---

# DO NOT EDIT!
# Automatically generated via doxygen2docusaurus by Doxygen.

slug: /api/structs/llvm/bittracker/machineevaluator
custom_edit_url: null
toc_max_heading_level: 4
keywords:
  - doxygen
  - reference
  - struct

---

<div class="doxyPage">

# The `MachineEvaluator` Struct Reference



## Declaration

<div class="doxyDeclaration">
struct llvm::BitTracker::MachineEvaluator { ... }
</div>

## Included Headers

<div class="doxyIncludesList">#include "<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/hexagon/bittracker-h">Target/Hexagon/BitTracker.h</a>"
</div>

## Derived Structs

<table class="doxyMembersIndex">

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">struct</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="/web-llvm/docs/api/structs/llvm/hexagonevaluator">HexagonEvaluator</a></td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a4301e1f2a5607d796c5505a5a5919501">MachineEvaluator</a> (const TargetRegisterInfo &amp;T, MachineRegisterInfo &amp;M)</td>
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

## Public Destructor Index

<table class="doxyMembersIndex">

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ae25072ca0ead457f1c782c2859f9664b">~MachineEvaluator</a> ()=default</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">uint16_t</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a64ee9ca87205e764e0382240030f87ee">getRegBitWidth</a> (const RegisterRef &amp;RR) const</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/structs/llvm/bittracker/registercell">RegisterCell</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a9a70d4969d8d43a9c9b324f692bc8ecd">getCell</a> (const RegisterRef &amp;RR, const CellMapType &amp;M) const</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a8944fc547212f985ad3f9706eb5b8725">putCell</a> (const RegisterRef &amp;RR, RegisterCell RC, CellMapType &amp;M) const</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/structs/llvm/bittracker/registercell">RegisterCell</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a12f55884970b0bcf4c909891e891225b">getRef</a> (const RegisterRef &amp;RR, const CellMapType &amp;M) const</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a6a2033c0f951975bebfc27e263f5e9c0">isInt</a> (const RegisterCell &amp;A) const</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">uint64_t</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ab0604c5bb97437a4cee3ef8ce1806732">toInt</a> (const RegisterCell &amp;A) const</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/structs/llvm/bittracker/registercell">RegisterCell</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a4ba2ddc1335f8aec90d6af171f4d5a3e">eIMM</a> (int64_t V, uint16_t W) const</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/structs/llvm/bittracker/registercell">RegisterCell</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a3a0c8954d256d696edee542fa50c725b">eIMM</a> (const ConstantInt *CI) const</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/structs/llvm/bittracker/registercell">RegisterCell</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#adbf082422e6f7a82cea21dfa3273811d">eADD</a> (const RegisterCell &amp;A1, const RegisterCell &amp;A2) const</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/structs/llvm/bittracker/registercell">RegisterCell</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#add47c55cf111a92da1ded367147668eb">eSUB</a> (const RegisterCell &amp;A1, const RegisterCell &amp;A2) const</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/structs/llvm/bittracker/registercell">RegisterCell</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a6032f746ffa25df648aa38680d1e891e">eMLS</a> (const RegisterCell &amp;A1, const RegisterCell &amp;A2) const</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/structs/llvm/bittracker/registercell">RegisterCell</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a518631233431d2324f15075cf91ffab2">eMLU</a> (const RegisterCell &amp;A1, const RegisterCell &amp;A2) const</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/structs/llvm/bittracker/registercell">RegisterCell</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a86f3525b5df439dd04caea2c1d4f567d">eASL</a> (const RegisterCell &amp;A1, uint16_t Sh) const</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/structs/llvm/bittracker/registercell">RegisterCell</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a4d418e3defa1322e8e55b020eef30475">eLSR</a> (const RegisterCell &amp;A1, uint16_t Sh) const</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/structs/llvm/bittracker/registercell">RegisterCell</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a83c32395e0a0c8e1d12e4dbdc5483928">eASR</a> (const RegisterCell &amp;A1, uint16_t Sh) const</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/structs/llvm/bittracker/registercell">RegisterCell</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ab4b48cf5ad86cd432b03b6f5b254f227">eAND</a> (const RegisterCell &amp;A1, const RegisterCell &amp;A2) const</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/structs/llvm/bittracker/registercell">RegisterCell</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#abe57eebc5c101a825f3c31712fdd617b">eORL</a> (const RegisterCell &amp;A1, const RegisterCell &amp;A2) const</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/structs/llvm/bittracker/registercell">RegisterCell</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a2c519d1784e4a4beee0fd668ed8d3900">eXOR</a> (const RegisterCell &amp;A1, const RegisterCell &amp;A2) const</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/structs/llvm/bittracker/registercell">RegisterCell</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a4aa1e4c6871a0b6056bba979f7c546bb">eNOT</a> (const RegisterCell &amp;A1) const</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/structs/llvm/bittracker/registercell">RegisterCell</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#aff2732336b8dfd24292c6db1fa6a64e2">eSET</a> (const RegisterCell &amp;A1, uint16_t BitN) const</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/structs/llvm/bittracker/registercell">RegisterCell</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a13d0509a1380fb9679b433c16d4688a1">eCLR</a> (const RegisterCell &amp;A1, uint16_t BitN) const</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/structs/llvm/bittracker/registercell">RegisterCell</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a6a2e09403daa9d3a9d40a68895e90aa9">eCLB</a> (const RegisterCell &amp;A1, bool B, uint16_t W) const</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/structs/llvm/bittracker/registercell">RegisterCell</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a8fa571f010447594afbfb0dd92cdb917">eCTB</a> (const RegisterCell &amp;A1, bool B, uint16_t W) const</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/structs/llvm/bittracker/registercell">RegisterCell</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ac2da26c1aaa137602b14f3b3da367f61">eSXT</a> (const RegisterCell &amp;A1, uint16_t FromN) const</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/structs/llvm/bittracker/registercell">RegisterCell</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a57424565b80f4f8fef7b5a8e11735f34">eZXT</a> (const RegisterCell &amp;A1, uint16_t FromN) const</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/structs/llvm/bittracker/registercell">RegisterCell</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#aefa1e921dff52ae9ac378bf26a32b4d2">eXTR</a> (const RegisterCell &amp;A1, uint16_t B, uint16_t E) const</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/structs/llvm/bittracker/registercell">RegisterCell</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#aceb7efc236b586c36f36b047db000db9">eINS</a> (const RegisterCell &amp;A1, const RegisterCell &amp;A2, uint16_t AtN) const</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/structs/llvm/bittracker/bitmask">BitMask</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ac0e6b7c81164e9fdd0d67fa47ed2b925">mask</a> (Register Reg, unsigned Sub) const</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a8466bee1159e47fe78597c5cd617270f">track</a> (const TargetRegisterClass *RC) const</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a1366c4865d7c8ca31dcf403406e3b291">evaluate</a> (const MachineInstr &amp;MI, const CellMapType &amp;Inputs, CellMapType &amp;Outputs) const</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a1df9a32f4a8e2df262de386b5bf3ab2d">evaluate</a> (const MachineInstr &amp;BI, const CellMapType &amp;Inputs, BranchTargetList &amp;Targets, bool &amp;FallsThru) const =0</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/targetregisterclass">TargetRegisterClass</a> &amp;</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a79c108ab366b6e0b42294e9a0e75a51e">composeWithSubRegIndex</a> (const TargetRegisterClass &amp;RC, unsigned Idx) const</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">uint16_t</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a983992af4e6d9497a917c11bb9212306">getPhysRegBitWidth</a> (MCRegister Reg) const</td>
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

## Public Member Attributes Index

<table class="doxyMembersIndex">

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/targetregisterinfo">TargetRegisterInfo</a> &amp;</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a440983b5e0f6fc9cd9771b51f1f998dd">TRI</a></td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/machineregisterinfo">MachineRegisterInfo</a> &amp;</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a6d5cfd7739a2939cd9418586c8aa1a3c">MRI</a></td>
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


<p>Definition at line 392 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/hexagon/bittracker-h">BitTracker.h</a>.</p>


<div class="doxySectionDef">

## Public Constructors

### MachineEvaluator() {#a4301e1f2a5607d796c5505a5a5919501}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">llvm::BitTracker::MachineEvaluator::MachineEvaluator (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/targetregisterinfo">TargetRegisterInfo</a> &amp; T, <a href="/web-llvm/docs/api/classes/llvm/machineregisterinfo">MachineRegisterInfo</a> &amp; M)</td>
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



<p>Definition at line 393 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/hexagon/bittracker-h">BitTracker.h</a>.</p>


<p>References <a href="#a6d5cfd7739a2939cd9418586c8aa1a3c">MRI</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/mips/mips16isellowering-cpp/#a0acb682b8260ab1c60b918599864e2e5">T</a> and <a href="#a440983b5e0f6fc9cd9771b51f1f998dd">TRI</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/structs/llvm/hexagonevaluator/#a5c2b22f49f8bb9c6c2d5c4ff5211d9e9">llvm::HexagonEvaluator::HexagonEvaluator</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Public Destructor

### \~MachineEvaluator() {#ae25072ca0ead457f1c782c2859f9664b}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">virtual llvm::BitTracker::MachineEvaluator::~MachineEvaluator ()</td>
</tr>
</table>
</td>
<td class="doxyMemberLabelsRight">
<span class="doxyMemberLabels">
<span class="doxyMemberLabel virtual">virtual</span>
<span class="doxyMemberLabel default">default</span>
</span>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 395 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/hexagon/bittracker-h">BitTracker.h</a>.</p>


<p>References <a href="#a9a70d4969d8d43a9c9b324f692bc8ecd">getCell</a>, <a href="#a64ee9ca87205e764e0382240030f87ee">getRegBitWidth</a> and <a href="#a8944fc547212f985ad3f9706eb5b8725">putCell</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Public Member Functions

### composeWithSubRegIndex() {#a79c108ab366b6e0b42294e9a0e75a51e}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">virtual const TargetRegisterClass &amp; llvm::BitTracker::MachineEvaluator::composeWithSubRegIndex (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/targetregisterclass">TargetRegisterClass</a> &amp; RC, unsigned Idx)</td>
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



<p>Definition at line 482 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/hexagon/bittracker-h">BitTracker.h</a>.</p>


<p>Reference <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/support/errorhandling-h/#ace243f5c25697a1107cce46626b3dc94">llvm_unreachable</a>.</p>


<p>Referenced by <a href="#a64ee9ca87205e764e0382240030f87ee">getRegBitWidth</a>.</p>

</div>
</div>

### eADD() {#adbf082422e6f7a82cea21dfa3273811d}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">BT::RegisterCell BT::MachineEvaluator::eADD (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/structs/llvm/bittracker/registercell">RegisterCell</a> &amp; A1, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/structs/llvm/bittracker/registercell">RegisterCell</a> &amp; A2)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Declaration at line 421 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/hexagon/bittracker-h">BitTracker.h</a>, definition at line 432 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/hexagon/bittracker-cpp">BitTracker.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/silowercontrolflow-cpp/#a4868c5d81c5ccc98c47aeab6244346a0">assert</a>, <a href="/web-llvm/docs/api/files/lib/lib/support/md5-cpp/#ac0eafdc9ee161b71e7af98af736952fd">I</a>, <a href="/web-llvm/docs/api/structs/llvm/bittracker/bitvalue/#abdda211d574b7a9074aa1cdb1b0b204b">llvm::BitTracker::BitValue::is</a>, <a href="/web-llvm/docs/api/structs/llvm/bittracker/bitvalue/#adcd0b7d53f566f3bfb0ede8423b08e28">llvm::BitTracker::BitValue::num</a>, <a href="/web-llvm/docs/api/structs/llvm/bittracker/bitvalue/#a701348c13b6afb4d3ee38ec978ea0e49">llvm::BitTracker::BitValue::ref</a>, <a href="/web-llvm/docs/api/structs/llvm/bittracker/bitvalue/#ad20a19c881ef4af1b3a270bf06fa8d89">llvm::BitTracker::BitValue::self</a> and <a href="/web-llvm/docs/api/structs/llvm/bittracker/registercell/#a56acc95a5fa4a319c87879ce52766595">llvm::BitTracker::RegisterCell::width</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/structs/llvm/hexagonevaluator/#a49b4d08c8b0024b97c7e090a0b3e50f6">llvm::HexagonEvaluator::evaluate</a>.</p>

</div>
</div>

### eAND() {#ab4b48cf5ad86cd432b03b6f5b254f227}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">BT::RegisterCell BT::MachineEvaluator::eAND (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/structs/llvm/bittracker/registercell">RegisterCell</a> &amp; A1, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/structs/llvm/bittracker/registercell">RegisterCell</a> &amp; A2)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Declaration at line 432 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/hexagon/bittracker-h">BitTracker.h</a>, definition at line 548 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/hexagon/bittracker-cpp">BitTracker.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/silowercontrolflow-cpp/#a4868c5d81c5ccc98c47aeab6244346a0">assert</a>, <a href="/web-llvm/docs/api/structs/llvm/bittracker/bitvalue/#abdda211d574b7a9074aa1cdb1b0b204b">llvm::BitTracker::BitValue::is</a>, <a href="/web-llvm/docs/api/structs/llvm/bittracker/bitvalue/#a701348c13b6afb4d3ee38ec978ea0e49">llvm::BitTracker::BitValue::ref</a>, <a href="/web-llvm/docs/api/structs/llvm/bittracker/bitvalue/#ad20a19c881ef4af1b3a270bf06fa8d89">llvm::BitTracker::BitValue::self</a>, <a href="/web-llvm/docs/api/structs/llvm/bittracker/registercell/#a56acc95a5fa4a319c87879ce52766595">llvm::BitTracker::RegisterCell::width</a> and <a href="/web-llvm/docs/api/structs/llvm/bittracker/bitvalue/#a8e191c51f58f07f7efa53510f3bdda94abab00433c23a81e220b50a1550320b9a">llvm::BitTracker::BitValue::Zero</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/structs/llvm/hexagonevaluator/#a49b4d08c8b0024b97c7e090a0b3e50f6">llvm::HexagonEvaluator::evaluate</a>.</p>

</div>
</div>

### eASL() {#a86f3525b5df439dd04caea2c1d4f567d}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">BT::RegisterCell BT::MachineEvaluator::eASL (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/structs/llvm/bittracker/registercell">RegisterCell</a> &amp; A1, uint16_t Sh)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Declaration at line 427 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/hexagon/bittracker-h">BitTracker.h</a>, definition at line 518 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/hexagon/bittracker-cpp">BitTracker.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/silowercontrolflow-cpp/#a4868c5d81c5ccc98c47aeab6244346a0">assert</a>, <a href="/web-llvm/docs/api/structs/llvm/bittracker/registercell/#a79b7d643ade1a355ff1b560a6d86a5c3">llvm::BitTracker::RegisterCell::fill</a>, <a href="/web-llvm/docs/api/structs/llvm/bittracker/registercell/#a4e73984cdacfb5cd24df684bbe6af7a7">llvm::BitTracker::RegisterCell::ref</a>, <a href="/web-llvm/docs/api/structs/llvm/bittracker/registercell/#ae272af7a7e6e5254fca24ec9fc2ed91c">llvm::BitTracker::RegisterCell::rol</a>, <a href="/web-llvm/docs/api/structs/llvm/bittracker/registercell/#a56acc95a5fa4a319c87879ce52766595">llvm::BitTracker::RegisterCell::width</a> and <a href="/web-llvm/docs/api/structs/llvm/bittracker/bitvalue/#a8e191c51f58f07f7efa53510f3bdda94abab00433c23a81e220b50a1550320b9a">llvm::BitTracker::BitValue::Zero</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/structs/llvm/hexagonevaluator/#a49b4d08c8b0024b97c7e090a0b3e50f6">llvm::HexagonEvaluator::evaluate</a>.</p>

</div>
</div>

### eASR() {#a83c32395e0a0c8e1d12e4dbdc5483928}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">BT::RegisterCell BT::MachineEvaluator::eASR (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/structs/llvm/bittracker/registercell">RegisterCell</a> &amp; A1, uint16_t Sh)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Declaration at line 429 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/hexagon/bittracker-h">BitTracker.h</a>, definition at line 537 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/hexagon/bittracker-cpp">BitTracker.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/silowercontrolflow-cpp/#a4868c5d81c5ccc98c47aeab6244346a0">assert</a>, <a href="/web-llvm/docs/api/structs/llvm/bittracker/registercell/#a79b7d643ade1a355ff1b560a6d86a5c3">llvm::BitTracker::RegisterCell::fill</a>, <a href="/web-llvm/docs/api/structs/llvm/bittracker/registercell/#a4e73984cdacfb5cd24df684bbe6af7a7">llvm::BitTracker::RegisterCell::ref</a>, <a href="/web-llvm/docs/api/structs/llvm/bittracker/registercell/#ae272af7a7e6e5254fca24ec9fc2ed91c">llvm::BitTracker::RegisterCell::rol</a> and <a href="/web-llvm/docs/api/structs/llvm/bittracker/registercell/#a56acc95a5fa4a319c87879ce52766595">llvm::BitTracker::RegisterCell::width</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/structs/llvm/hexagonevaluator/#a49b4d08c8b0024b97c7e090a0b3e50f6">llvm::HexagonEvaluator::evaluate</a>.</p>

</div>
</div>

### eCLB() {#a6a2e09403daa9d3a9d40a68895e90aa9}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">BT::RegisterCell BT::MachineEvaluator::eCLB (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/structs/llvm/bittracker/registercell">RegisterCell</a> &amp; A1, bool B, uint16_t W)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Declaration at line 442 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/hexagon/bittracker-h">BitTracker.h</a>, definition at line 643 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/hexagon/bittracker-cpp">BitTracker.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/files/lib/lib/ir/builtingcs-cpp/#ae76959fe811ba090de4cba69ac00f1da">B</a>, <a href="/web-llvm/docs/api/namespaces/llvm/callingconv/#ac6aa1387c4375260e2468eb5a77fdb4cafd841a49aec1539bc88abc8ff9e170fb">llvm::CallingConv::C</a>, <a href="/web-llvm/docs/api/structs/llvm/bittracker/registercell/#ad9770ab6f8b5455a3a84789a4ef8e94d">llvm::BitTracker::RegisterCell::cl</a>, <a href="#a4ba2ddc1335f8aec90d6af171f4d5a3e">eIMM</a>, <a href="/web-llvm/docs/api/structs/llvm/bittracker/registercell/#a4b372ece8559169470a7fcfb471c2302">llvm::BitTracker::RegisterCell::self</a> and <a href="/web-llvm/docs/api/structs/llvm/bittracker/registercell/#a56acc95a5fa4a319c87879ce52766595">llvm::BitTracker::RegisterCell::width</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/structs/llvm/hexagonevaluator/#a49b4d08c8b0024b97c7e090a0b3e50f6">llvm::HexagonEvaluator::evaluate</a>.</p>

</div>
</div>

### eCLR() {#a13d0509a1380fb9679b433c16d4688a1}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">BT::RegisterCell BT::MachineEvaluator::eCLR (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/structs/llvm/bittracker/registercell">RegisterCell</a> &amp; A1, uint16_t BitN)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Declaration at line 439 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/hexagon/bittracker-h">BitTracker.h</a>, definition at line 635 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/hexagon/bittracker-cpp">BitTracker.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/silowercontrolflow-cpp/#a4868c5d81c5ccc98c47aeab6244346a0">assert</a>, <a href="/web-llvm/docs/api/structs/llvm/bittracker/registercell/#a4e73984cdacfb5cd24df684bbe6af7a7">llvm::BitTracker::RegisterCell::ref</a>, <a href="/web-llvm/docs/api/structs/llvm/bittracker/registercell/#a56acc95a5fa4a319c87879ce52766595">llvm::BitTracker::RegisterCell::width</a> and <a href="/web-llvm/docs/api/structs/llvm/bittracker/bitvalue/#a8e191c51f58f07f7efa53510f3bdda94abab00433c23a81e220b50a1550320b9a">llvm::BitTracker::BitValue::Zero</a>.</p>

</div>
</div>

### eCTB() {#a8fa571f010447594afbfb0dd92cdb917}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">BT::RegisterCell BT::MachineEvaluator::eCTB (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/structs/llvm/bittracker/registercell">RegisterCell</a> &amp; A1, bool B, uint16_t W)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Declaration at line 443 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/hexagon/bittracker-h">BitTracker.h</a>, definition at line 653 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/hexagon/bittracker-cpp">BitTracker.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/files/lib/lib/ir/builtingcs-cpp/#ae76959fe811ba090de4cba69ac00f1da">B</a>, <a href="/web-llvm/docs/api/namespaces/llvm/callingconv/#ac6aa1387c4375260e2468eb5a77fdb4cafd841a49aec1539bc88abc8ff9e170fb">llvm::CallingConv::C</a>, <a href="/web-llvm/docs/api/structs/llvm/bittracker/registercell/#ab3fa9c47bf9d313125b4dbe582b2eaad">llvm::BitTracker::RegisterCell::ct</a>, <a href="#a4ba2ddc1335f8aec90d6af171f4d5a3e">eIMM</a>, <a href="/web-llvm/docs/api/structs/llvm/bittracker/registercell/#a4b372ece8559169470a7fcfb471c2302">llvm::BitTracker::RegisterCell::self</a> and <a href="/web-llvm/docs/api/structs/llvm/bittracker/registercell/#a56acc95a5fa4a319c87879ce52766595">llvm::BitTracker::RegisterCell::width</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/structs/llvm/hexagonevaluator/#a49b4d08c8b0024b97c7e090a0b3e50f6">llvm::HexagonEvaluator::evaluate</a>.</p>

</div>
</div>

### eIMM() {#a4ba2ddc1335f8aec90d6af171f4d5a3e}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">BT::RegisterCell BT::MachineEvaluator::eIMM (int64_t V, uint16_t W)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Declaration at line 417 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/hexagon/bittracker-h">BitTracker.h</a>, definition at line 412 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/hexagon/bittracker-cpp">BitTracker.cpp</a>.</p>


<p>Referenced by <a href="#a6a2e09403daa9d3a9d40a68895e90aa9">eCLB</a>, <a href="#a8fa571f010447594afbfb0dd92cdb917">eCTB</a> and <a href="/web-llvm/docs/api/structs/llvm/hexagonevaluator/#a49b4d08c8b0024b97c7e090a0b3e50f6">llvm::HexagonEvaluator::evaluate</a>.</p>

</div>
</div>

### eIMM() {#a3a0c8954d256d696edee542fa50c725b}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">BT::RegisterCell BT::MachineEvaluator::eIMM (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/constantint">ConstantInt</a> * CI)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Declaration at line 418 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/hexagon/bittracker-h">BitTracker.h</a>, definition at line 422 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/hexagon/bittracker-cpp">BitTracker.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/files/lib/lib/ir/builtingcs-cpp/#a2e38c85003a042421cde1647632d0b72">A</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/silowercontrolflow-cpp/#a4868c5d81c5ccc98c47aeab6244346a0">assert</a> and <a href="/web-llvm/docs/api/classes/llvm/constantint/#af7e1934ed72a405ef073ea5f9bbe828e">llvm::ConstantInt::getValue</a>.</p>

</div>
</div>

### eINS() {#aceb7efc236b586c36f36b047db000db9}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">BT::RegisterCell BT::MachineEvaluator::eINS (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/structs/llvm/bittracker/registercell">RegisterCell</a> &amp; A1, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/structs/llvm/bittracker/registercell">RegisterCell</a> &amp; A2, uint16_t AtN)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Declaration at line 453 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/hexagon/bittracker-h">BitTracker.h</a>, definition at line 695 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/hexagon/bittracker-cpp">BitTracker.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/silowercontrolflow-cpp/#a4868c5d81c5ccc98c47aeab6244346a0">assert</a>, <a href="/web-llvm/docs/api/structs/llvm/bittracker/registercell/#ab436b1402523817d32ee31d1d7eb7a0c">llvm::BitTracker::RegisterCell::insert</a>, <a href="/web-llvm/docs/api/structs/llvm/bittracker/registercell/#a4e73984cdacfb5cd24df684bbe6af7a7">llvm::BitTracker::RegisterCell::ref</a> and <a href="/web-llvm/docs/api/structs/llvm/bittracker/registercell/#a56acc95a5fa4a319c87879ce52766595">llvm::BitTracker::RegisterCell::width</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/structs/llvm/hexagonevaluator/#a49b4d08c8b0024b97c7e090a0b3e50f6">llvm::HexagonEvaluator::evaluate</a>.</p>

</div>
</div>

### eLSR() {#a4d418e3defa1322e8e55b020eef30475}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">BT::RegisterCell BT::MachineEvaluator::eLSR (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/structs/llvm/bittracker/registercell">RegisterCell</a> &amp; A1, uint16_t Sh)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Declaration at line 428 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/hexagon/bittracker-h">BitTracker.h</a>, definition at line 527 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/hexagon/bittracker-cpp">BitTracker.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/silowercontrolflow-cpp/#a4868c5d81c5ccc98c47aeab6244346a0">assert</a>, <a href="/web-llvm/docs/api/structs/llvm/bittracker/registercell/#a79b7d643ade1a355ff1b560a6d86a5c3">llvm::BitTracker::RegisterCell::fill</a>, <a href="/web-llvm/docs/api/structs/llvm/bittracker/registercell/#a4e73984cdacfb5cd24df684bbe6af7a7">llvm::BitTracker::RegisterCell::ref</a>, <a href="/web-llvm/docs/api/structs/llvm/bittracker/registercell/#ae272af7a7e6e5254fca24ec9fc2ed91c">llvm::BitTracker::RegisterCell::rol</a>, <a href="/web-llvm/docs/api/structs/llvm/bittracker/registercell/#a56acc95a5fa4a319c87879ce52766595">llvm::BitTracker::RegisterCell::width</a> and <a href="/web-llvm/docs/api/structs/llvm/bittracker/bitvalue/#a8e191c51f58f07f7efa53510f3bdda94abab00433c23a81e220b50a1550320b9a">llvm::BitTracker::BitValue::Zero</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/structs/llvm/hexagonevaluator/#a49b4d08c8b0024b97c7e090a0b3e50f6">llvm::HexagonEvaluator::evaluate</a>.</p>

</div>
</div>

### eMLS() {#a6032f746ffa25df648aa38680d1e891e}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">BT::RegisterCell BT::MachineEvaluator::eMLS (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/structs/llvm/bittracker/registercell">RegisterCell</a> &amp; A1, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/structs/llvm/bittracker/registercell">RegisterCell</a> &amp; A2)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Declaration at line 423 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/hexagon/bittracker-h">BitTracker.h</a>, definition at line 498 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/hexagon/bittracker-cpp">BitTracker.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/structs/llvm/bittracker/registercell/#ab3fa9c47bf9d313125b4dbe582b2eaad">llvm::BitTracker::RegisterCell::ct</a>, <a href="/web-llvm/docs/api/structs/llvm/bittracker/registercell/#a79b7d643ade1a355ff1b560a6d86a5c3">llvm::BitTracker::RegisterCell::fill</a>, <a href="/web-llvm/docs/api/structs/llvm/bittracker/bitvalue/#ad20a19c881ef4af1b3a270bf06fa8d89">llvm::BitTracker::BitValue::self</a>, <a href="/web-llvm/docs/api/structs/llvm/bittracker/registercell/#a56acc95a5fa4a319c87879ce52766595">llvm::BitTracker::RegisterCell::width</a> and <a href="/web-llvm/docs/api/structs/llvm/bittracker/bitvalue/#a8e191c51f58f07f7efa53510f3bdda94abab00433c23a81e220b50a1550320b9a">llvm::BitTracker::BitValue::Zero</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/structs/llvm/hexagonevaluator/#a49b4d08c8b0024b97c7e090a0b3e50f6">llvm::HexagonEvaluator::evaluate</a>.</p>

</div>
</div>

### eMLU() {#a518631233431d2324f15075cf91ffab2}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">BT::RegisterCell BT::MachineEvaluator::eMLU (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/structs/llvm/bittracker/registercell">RegisterCell</a> &amp; A1, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/structs/llvm/bittracker/registercell">RegisterCell</a> &amp; A2)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Declaration at line 424 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/hexagon/bittracker-h">BitTracker.h</a>, definition at line 508 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/hexagon/bittracker-cpp">BitTracker.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/structs/llvm/bittracker/registercell/#ab3fa9c47bf9d313125b4dbe582b2eaad">llvm::BitTracker::RegisterCell::ct</a>, <a href="/web-llvm/docs/api/structs/llvm/bittracker/registercell/#a79b7d643ade1a355ff1b560a6d86a5c3">llvm::BitTracker::RegisterCell::fill</a>, <a href="/web-llvm/docs/api/structs/llvm/bittracker/bitvalue/#ad20a19c881ef4af1b3a270bf06fa8d89">llvm::BitTracker::BitValue::self</a>, <a href="/web-llvm/docs/api/structs/llvm/bittracker/registercell/#a56acc95a5fa4a319c87879ce52766595">llvm::BitTracker::RegisterCell::width</a> and <a href="/web-llvm/docs/api/structs/llvm/bittracker/bitvalue/#a8e191c51f58f07f7efa53510f3bdda94abab00433c23a81e220b50a1550320b9a">llvm::BitTracker::BitValue::Zero</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/structs/llvm/hexagonevaluator/#a49b4d08c8b0024b97c7e090a0b3e50f6">llvm::HexagonEvaluator::evaluate</a>.</p>

</div>
</div>

### eNOT() {#a4aa1e4c6871a0b6056bba979f7c546bb}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">BT::RegisterCell BT::MachineEvaluator::eNOT (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/structs/llvm/bittracker/registercell">RegisterCell</a> &amp; A1)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Declaration at line 435 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/hexagon/bittracker-h">BitTracker.h</a>, definition at line 612 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/hexagon/bittracker-cpp">BitTracker.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/structs/llvm/bittracker/bitvalue/#a8e191c51f58f07f7efa53510f3bdda94a86e84878fc26bf4a4fd39f94424b730b">llvm::BitTracker::BitValue::One</a>, <a href="/web-llvm/docs/api/structs/llvm/bittracker/bitvalue/#ad20a19c881ef4af1b3a270bf06fa8d89">llvm::BitTracker::BitValue::self</a>, <a href="/web-llvm/docs/api/structs/llvm/bittracker/registercell/#a56acc95a5fa4a319c87879ce52766595">llvm::BitTracker::RegisterCell::width</a> and <a href="/web-llvm/docs/api/structs/llvm/bittracker/bitvalue/#a8e191c51f58f07f7efa53510f3bdda94abab00433c23a81e220b50a1550320b9a">llvm::BitTracker::BitValue::Zero</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/structs/llvm/hexagonevaluator/#a49b4d08c8b0024b97c7e090a0b3e50f6">llvm::HexagonEvaluator::evaluate</a>.</p>

</div>
</div>

### eORL() {#abe57eebc5c101a825f3c31712fdd617b}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">BT::RegisterCell BT::MachineEvaluator::eORL (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/structs/llvm/bittracker/registercell">RegisterCell</a> &amp; A1, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/structs/llvm/bittracker/registercell">RegisterCell</a> &amp; A2)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Declaration at line 433 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/hexagon/bittracker-h">BitTracker.h</a>, definition at line 570 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/hexagon/bittracker-cpp">BitTracker.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/silowercontrolflow-cpp/#a4868c5d81c5ccc98c47aeab6244346a0">assert</a>, <a href="/web-llvm/docs/api/structs/llvm/bittracker/bitvalue/#abdda211d574b7a9074aa1cdb1b0b204b">llvm::BitTracker::BitValue::is</a>, <a href="/web-llvm/docs/api/structs/llvm/bittracker/bitvalue/#a8e191c51f58f07f7efa53510f3bdda94a86e84878fc26bf4a4fd39f94424b730b">llvm::BitTracker::BitValue::One</a>, <a href="/web-llvm/docs/api/structs/llvm/bittracker/bitvalue/#a701348c13b6afb4d3ee38ec978ea0e49">llvm::BitTracker::BitValue::ref</a>, <a href="/web-llvm/docs/api/structs/llvm/bittracker/bitvalue/#ad20a19c881ef4af1b3a270bf06fa8d89">llvm::BitTracker::BitValue::self</a> and <a href="/web-llvm/docs/api/structs/llvm/bittracker/registercell/#a56acc95a5fa4a319c87879ce52766595">llvm::BitTracker::RegisterCell::width</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/structs/llvm/hexagonevaluator/#a49b4d08c8b0024b97c7e090a0b3e50f6">llvm::HexagonEvaluator::evaluate</a>.</p>

</div>
</div>

### eSET() {#aff2732336b8dfd24292c6db1fa6a64e2}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">BT::RegisterCell BT::MachineEvaluator::eSET (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/structs/llvm/bittracker/registercell">RegisterCell</a> &amp; A1, uint16_t BitN)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Declaration at line 438 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/hexagon/bittracker-h">BitTracker.h</a>, definition at line 627 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/hexagon/bittracker-cpp">BitTracker.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/silowercontrolflow-cpp/#a4868c5d81c5ccc98c47aeab6244346a0">assert</a>, <a href="/web-llvm/docs/api/structs/llvm/bittracker/bitvalue/#a8e191c51f58f07f7efa53510f3bdda94a86e84878fc26bf4a4fd39f94424b730b">llvm::BitTracker::BitValue::One</a>, <a href="/web-llvm/docs/api/structs/llvm/bittracker/registercell/#a4e73984cdacfb5cd24df684bbe6af7a7">llvm::BitTracker::RegisterCell::ref</a> and <a href="/web-llvm/docs/api/structs/llvm/bittracker/registercell/#a56acc95a5fa4a319c87879ce52766595">llvm::BitTracker::RegisterCell::width</a>.</p>

</div>
</div>

### eSUB() {#add47c55cf111a92da1ded367147668eb}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">BT::RegisterCell BT::MachineEvaluator::eSUB (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/structs/llvm/bittracker/registercell">RegisterCell</a> &amp; A1, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/structs/llvm/bittracker/registercell">RegisterCell</a> &amp; A2)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Declaration at line 422 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/hexagon/bittracker-h">BitTracker.h</a>, definition at line 465 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/hexagon/bittracker-cpp">BitTracker.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/silowercontrolflow-cpp/#a4868c5d81c5ccc98c47aeab6244346a0">assert</a>, <a href="/web-llvm/docs/api/files/lib/lib/support/md5-cpp/#ac0eafdc9ee161b71e7af98af736952fd">I</a>, <a href="/web-llvm/docs/api/structs/llvm/bittracker/bitvalue/#abdda211d574b7a9074aa1cdb1b0b204b">llvm::BitTracker::BitValue::is</a>, <a href="/web-llvm/docs/api/structs/llvm/bittracker/bitvalue/#adcd0b7d53f566f3bfb0ede8423b08e28">llvm::BitTracker::BitValue::num</a>, <a href="/web-llvm/docs/api/structs/llvm/bittracker/bitvalue/#a701348c13b6afb4d3ee38ec978ea0e49">llvm::BitTracker::BitValue::ref</a>, <a href="/web-llvm/docs/api/structs/llvm/bittracker/bitvalue/#ad20a19c881ef4af1b3a270bf06fa8d89">llvm::BitTracker::BitValue::self</a> and <a href="/web-llvm/docs/api/structs/llvm/bittracker/registercell/#a56acc95a5fa4a319c87879ce52766595">llvm::BitTracker::RegisterCell::width</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/structs/llvm/hexagonevaluator/#a49b4d08c8b0024b97c7e090a0b3e50f6">llvm::HexagonEvaluator::evaluate</a>.</p>

</div>
</div>

### eSXT() {#ac2da26c1aaa137602b14f3b3da367f61}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">BT::RegisterCell BT::MachineEvaluator::eSXT (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/structs/llvm/bittracker/registercell">RegisterCell</a> &amp; A1, uint16_t FromN)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Declaration at line 446 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/hexagon/bittracker-h">BitTracker.h</a>, definition at line 663 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/hexagon/bittracker-cpp">BitTracker.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/silowercontrolflow-cpp/#a4868c5d81c5ccc98c47aeab6244346a0">assert</a>, <a href="/web-llvm/docs/api/structs/llvm/bittracker/registercell/#a79b7d643ade1a355ff1b560a6d86a5c3">llvm::BitTracker::RegisterCell::fill</a>, <a href="/web-llvm/docs/api/structs/llvm/bittracker/registercell/#a4e73984cdacfb5cd24df684bbe6af7a7">llvm::BitTracker::RegisterCell::ref</a> and <a href="/web-llvm/docs/api/structs/llvm/bittracker/registercell/#a56acc95a5fa4a319c87879ce52766595">llvm::BitTracker::RegisterCell::width</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/structs/llvm/hexagonevaluator/#a49b4d08c8b0024b97c7e090a0b3e50f6">llvm::HexagonEvaluator::evaluate</a>.</p>

</div>
</div>

### evaluate() {#a1366c4865d7c8ca31dcf403406e3b291}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool BT::MachineEvaluator::evaluate (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/machineinstr">MachineInstr</a> &amp; MI, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/structs/llvm/bittracker/#ac0eea221b9e05301dfd8cb9ac47bc7d8">CellMapType</a> &amp; Inputs, <a href="/web-llvm/docs/api/structs/llvm/bittracker/#ac0eea221b9e05301dfd8cb9ac47bc7d8">CellMapType</a> &amp; Outputs)</td>
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



<p>Declaration at line 471 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/hexagon/bittracker-h">BitTracker.h</a>, definition at line 719 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/hexagon/bittracker-cpp">BitTracker.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/silowercontrolflow-cpp/#a4868c5d81c5ccc98c47aeab6244346a0">assert</a>, <a href="/web-llvm/docs/api/structs/llvm/bittracker/registercell/#a79b7d643ade1a355ff1b560a6d86a5c3">llvm::BitTracker::RegisterCell::fill</a>, <a href="#a9a70d4969d8d43a9c9b324f692bc8ecd">getCell</a>, <a href="#a64ee9ca87205e764e0382240030f87ee">getRegBitWidth</a>, <a href="/web-llvm/docs/api/structs/llvm/bittracker/registercell/#ab436b1402523817d32ee31d1d7eb7a0c">llvm::BitTracker::RegisterCell::insert</a>, <a href="#ac0e6b7c81164e9fdd0d67fa47ed2b925">mask</a>, <a href="/web-llvm/docs/api/files/lib/lib/codegen/lib/codegen/globalisel/irtranslator-cpp/#abe44dfdea65b4f7e11e0a608ab708b76">MI</a>, <a href="#a8944fc547212f985ad3f9706eb5b8725">putCell</a>, <a href="/web-llvm/docs/api/structs/llvm/bittracker/registercell/#a4e73984cdacfb5cd24df684bbe6af7a7">llvm::BitTracker::RegisterCell::ref</a>, <a href="/web-llvm/docs/api/structs/llvm/bittracker/registerref/#a83d460802fba9c074af90710d239f516">llvm::BitTracker::RegisterRef::Reg</a>, <a href="/web-llvm/docs/api/structs/llvm/bittracker/registerref/#afd26bd676aebea77891d6d204dd804d5">llvm::BitTracker::RegisterRef::Sub</a> and <a href="/web-llvm/docs/api/structs/llvm/bittracker/bitvalue/#a8e191c51f58f07f7efa53510f3bdda94abab00433c23a81e220b50a1550320b9a">llvm::BitTracker::BitValue::Zero</a>.</p>

</div>
</div>

### evaluate() {#a1df9a32f4a8e2df262de386b5bf3ab2d}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">virtual bool llvm::BitTracker::MachineEvaluator::evaluate (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/machineinstr">MachineInstr</a> &amp; BI, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/structs/llvm/bittracker/#ac0eea221b9e05301dfd8cb9ac47bc7d8">CellMapType</a> &amp; Inputs, <a href="/web-llvm/docs/api/structs/llvm/bittracker/#a47ead69576339dc99f21824830f15fcc">BranchTargetList</a> &amp; Targets, bool &amp; FallsThru)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 477 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/hexagon/bittracker-h">BitTracker.h</a>.</p>

</div>
</div>

### eXOR() {#a2c519d1784e4a4beee0fd668ed8d3900}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">BT::RegisterCell BT::MachineEvaluator::eXOR (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/structs/llvm/bittracker/registercell">RegisterCell</a> &amp; A1, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/structs/llvm/bittracker/registercell">RegisterCell</a> &amp; A2)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Declaration at line 434 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/hexagon/bittracker-h">BitTracker.h</a>, definition at line 592 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/hexagon/bittracker-cpp">BitTracker.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/silowercontrolflow-cpp/#a4868c5d81c5ccc98c47aeab6244346a0">assert</a>, <a href="/web-llvm/docs/api/structs/llvm/bittracker/bitvalue/#abdda211d574b7a9074aa1cdb1b0b204b">llvm::BitTracker::BitValue::is</a>, <a href="/web-llvm/docs/api/structs/llvm/bittracker/bitvalue/#a701348c13b6afb4d3ee38ec978ea0e49">llvm::BitTracker::BitValue::ref</a>, <a href="/web-llvm/docs/api/structs/llvm/bittracker/bitvalue/#ad20a19c881ef4af1b3a270bf06fa8d89">llvm::BitTracker::BitValue::self</a>, <a href="/web-llvm/docs/api/structs/llvm/bittracker/registercell/#a56acc95a5fa4a319c87879ce52766595">llvm::BitTracker::RegisterCell::width</a> and <a href="/web-llvm/docs/api/structs/llvm/bittracker/bitvalue/#a8e191c51f58f07f7efa53510f3bdda94abab00433c23a81e220b50a1550320b9a">llvm::BitTracker::BitValue::Zero</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/structs/llvm/hexagonevaluator/#a49b4d08c8b0024b97c7e090a0b3e50f6">llvm::HexagonEvaluator::evaluate</a>.</p>

</div>
</div>

### eXTR() {#aefa1e921dff52ae9ac378bf26a32b4d2}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">BT::RegisterCell BT::MachineEvaluator::eXTR (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/structs/llvm/bittracker/registercell">RegisterCell</a> &amp; A1, uint16_t B, uint16_t E)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Declaration at line 452 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/hexagon/bittracker-h">BitTracker.h</a>, definition at line 683 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/hexagon/bittracker-cpp">BitTracker.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/silowercontrolflow-cpp/#a4868c5d81c5ccc98c47aeab6244346a0">assert</a>, <a href="/web-llvm/docs/api/files/lib/lib/ir/builtingcs-cpp/#ae76959fe811ba090de4cba69ac00f1da">B</a>, <a href="/web-llvm/docs/api/structs/llvm/bittracker/registercell/#a900f393e2eebd18ebe5696a0b5d309e5">llvm::BitTracker::RegisterCell::extract</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#ac10d13c57a7adf4a1f140afd5321309bad55b30607c2a9a2616347d6edb789f6b">llvm::Last</a>, <a href="/web-llvm/docs/api/structs/llvm/bittracker/registercell/#a4e73984cdacfb5cd24df684bbe6af7a7">llvm::BitTracker::RegisterCell::ref</a> and <a href="/web-llvm/docs/api/structs/llvm/bittracker/registercell/#a56acc95a5fa4a319c87879ce52766595">llvm::BitTracker::RegisterCell::width</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/structs/llvm/hexagonevaluator/#a49b4d08c8b0024b97c7e090a0b3e50f6">llvm::HexagonEvaluator::evaluate</a>.</p>

</div>
</div>

### eZXT() {#a57424565b80f4f8fef7b5a8e11735f34}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">BT::RegisterCell BT::MachineEvaluator::eZXT (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/structs/llvm/bittracker/registercell">RegisterCell</a> &amp; A1, uint16_t FromN)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Declaration at line 447 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/hexagon/bittracker-h">BitTracker.h</a>, definition at line 674 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/hexagon/bittracker-cpp">BitTracker.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/silowercontrolflow-cpp/#a4868c5d81c5ccc98c47aeab6244346a0">assert</a>, <a href="/web-llvm/docs/api/structs/llvm/bittracker/registercell/#a79b7d643ade1a355ff1b560a6d86a5c3">llvm::BitTracker::RegisterCell::fill</a>, <a href="/web-llvm/docs/api/structs/llvm/bittracker/registercell/#a4e73984cdacfb5cd24df684bbe6af7a7">llvm::BitTracker::RegisterCell::ref</a>, <a href="/web-llvm/docs/api/structs/llvm/bittracker/registercell/#a56acc95a5fa4a319c87879ce52766595">llvm::BitTracker::RegisterCell::width</a> and <a href="/web-llvm/docs/api/structs/llvm/bittracker/bitvalue/#a8e191c51f58f07f7efa53510f3bdda94abab00433c23a81e220b50a1550320b9a">llvm::BitTracker::BitValue::Zero</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/structs/llvm/hexagonevaluator/#a49b4d08c8b0024b97c7e090a0b3e50f6">llvm::HexagonEvaluator::evaluate</a>.</p>

</div>
</div>

### getCell() {#a9a70d4969d8d43a9c9b324f692bc8ecd}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">BT::RegisterCell BT::MachineEvaluator::getCell (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/structs/llvm/bittracker/registerref">RegisterRef</a> &amp; RR, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/structs/llvm/bittracker/#ac0eea221b9e05301dfd8cb9ac47bc7d8">CellMapType</a> &amp; M)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Declaration at line 399 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/hexagon/bittracker-h">BitTracker.h</a>, definition at line 348 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/hexagon/bittracker-cpp">BitTracker.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/silowercontrolflow-cpp/#a4868c5d81c5ccc98c47aeab6244346a0">assert</a>, <a href="/web-llvm/docs/api/namespaces/llvm/callingconv/#ac6aa1387c4375260e2468eb5a77fdb4cafd841a49aec1539bc88abc8ff9e170fb">llvm::CallingConv::C</a>, <a href="/web-llvm/docs/api/files/lib/lib/support/md5-cpp/#a96d73bbd7af15cb1fc38c3f4a3bd82e9">F</a>, <a href="#a64ee9ca87205e764e0382240030f87ee">getRegBitWidth</a>, <a href="/web-llvm/docs/api/classes/llvm/register/#affdbf5b92ed7e01352e2f39466efbe21">llvm::Register::isPhysical</a>, <a href="/web-llvm/docs/api/classes/llvm/register/#ab203bbcbc320180b1da9e9a92ee0c784">llvm::Register::isVirtual</a>, <a href="#ac0e6b7c81164e9fdd0d67fa47ed2b925">mask</a>, <a href="#a6d5cfd7739a2939cd9418586c8aa1a3c">MRI</a>, <a href="/web-llvm/docs/api/structs/llvm/bittracker/registerref/#a83d460802fba9c074af90710d239f516">llvm::BitTracker::RegisterRef::Reg</a>, <a href="/web-llvm/docs/api/structs/llvm/bittracker/registercell/#a4b372ece8559169470a7fcfb471c2302">llvm::BitTracker::RegisterCell::self</a>, <a href="/web-llvm/docs/api/structs/llvm/bittracker/registerref/#afd26bd676aebea77891d6d204dd804d5">llvm::BitTracker::RegisterRef::Sub</a>, <a href="/web-llvm/docs/api/structs/llvm/bittracker/registercell/#ab51d511c99890c779e2853504511f7d7">llvm::BitTracker::RegisterCell::top</a> and <a href="#a8466bee1159e47fe78597c5cd617270f">track</a>.</p>


<p>Referenced by <a href="#a1366c4865d7c8ca31dcf403406e3b291">evaluate</a>, <a href="/web-llvm/docs/api/structs/llvm/hexagonevaluator/#a6e8a4f85c8a56769ce682ff88d5b60f1">llvm::HexagonEvaluator::evaluate</a>, <a href="#a12f55884970b0bcf4c909891e891225b">getRef</a> and <a href="#ae25072ca0ead457f1c782c2859f9664b">~MachineEvaluator</a>.</p>

</div>
</div>

### getPhysRegBitWidth() {#a983992af4e6d9497a917c11bb9212306}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">uint16_t BT::MachineEvaluator::getPhysRegBitWidth (<a href="/web-llvm/docs/api/classes/llvm/mcregister">MCRegister</a> Reg)</td>
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



<p>Declaration at line 488 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/hexagon/bittracker-h">BitTracker.h</a>, definition at line 714 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/hexagon/bittracker-cpp">BitTracker.cpp</a>.</p>


<p>Reference <a href="#a440983b5e0f6fc9cd9771b51f1f998dd">TRI</a>.</p>


<p>Referenced by <a href="#a64ee9ca87205e764e0382240030f87ee">getRegBitWidth</a>.</p>

</div>
</div>

### getRef() {#a12f55884970b0bcf4c909891e891225b}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">RegisterCell llvm::BitTracker::MachineEvaluator::getRef (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/structs/llvm/bittracker/registerref">RegisterRef</a> &amp; RR, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/structs/llvm/bittracker/#ac0eea221b9e05301dfd8cb9ac47bc7d8">CellMapType</a> &amp; M)</td>
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



<p>Definition at line 405 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/hexagon/bittracker-h">BitTracker.h</a>.</p>


<p>References <a href="#a9a70d4969d8d43a9c9b324f692bc8ecd">getCell</a> and <a href="/web-llvm/docs/api/structs/llvm/bittracker/registercell/#a4e73984cdacfb5cd24df684bbe6af7a7">llvm::BitTracker::RegisterCell::ref</a>.</p>

</div>
</div>

### getRegBitWidth() {#a64ee9ca87205e764e0382240030f87ee}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">uint16_t BT::MachineEvaluator::getRegBitWidth (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/structs/llvm/bittracker/registerref">RegisterRef</a> &amp; RR)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Declaration at line 397 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/hexagon/bittracker-h">BitTracker.h</a>, definition at line 329 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/hexagon/bittracker-cpp">BitTracker.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/classes/llvm/register/#a49effcc0d9e7a321043ade70145d11f6">llvm::Register::asMCReg</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/silowercontrolflow-cpp/#a4868c5d81c5ccc98c47aeab6244346a0">assert</a>, <a href="#a79c108ab366b6e0b42294e9a0e75a51e">composeWithSubRegIndex</a>, <a href="#a983992af4e6d9497a917c11bb9212306">getPhysRegBitWidth</a>, <a href="/web-llvm/docs/api/classes/llvm/register/#affdbf5b92ed7e01352e2f39466efbe21">llvm::Register::isPhysical</a>, <a href="/web-llvm/docs/api/classes/llvm/register/#ab203bbcbc320180b1da9e9a92ee0c784">llvm::Register::isVirtual</a>, <a href="#a6d5cfd7739a2939cd9418586c8aa1a3c">MRI</a>, <a href="/web-llvm/docs/api/structs/llvm/bittracker/registerref/#a83d460802fba9c074af90710d239f516">llvm::BitTracker::RegisterRef::Reg</a>, <a href="/web-llvm/docs/api/structs/llvm/bittracker/registerref/#afd26bd676aebea77891d6d204dd804d5">llvm::BitTracker::RegisterRef::Sub</a> and <a href="#a440983b5e0f6fc9cd9771b51f1f998dd">TRI</a>.</p>


<p>Referenced by <a href="#a1366c4865d7c8ca31dcf403406e3b291">evaluate</a>, <a href="/web-llvm/docs/api/structs/llvm/hexagonevaluator/#a49b4d08c8b0024b97c7e090a0b3e50f6">llvm::HexagonEvaluator::evaluate</a>, <a href="#a9a70d4969d8d43a9c9b324f692bc8ecd">getCell</a>, <a href="#ac0e6b7c81164e9fdd0d67fa47ed2b925">mask</a>, <a href="/web-llvm/docs/api/structs/llvm/hexagonevaluator/#a26c72fb657ffaea1a961279c6d3a80fb">llvm::HexagonEvaluator::mask</a> and <a href="#ae25072ca0ead457f1c782c2859f9664b">~MachineEvaluator</a>.</p>

</div>
</div>

### isInt() {#a6a2033c0f951975bebfc27e263f5e9c0}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool BT::MachineEvaluator::isInt (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/structs/llvm/bittracker/registercell">RegisterCell</a> &amp; A)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Declaration at line 412 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/hexagon/bittracker-h">BitTracker.h</a>, definition at line 388 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/hexagon/bittracker-cpp">BitTracker.cpp</a>.</p>


<p>Reference <a href="/web-llvm/docs/api/files/lib/lib/ir/builtingcs-cpp/#a2e38c85003a042421cde1647632d0b72">A</a>.</p>


<p>Referenced by <a href="#ab0604c5bb97437a4cee3ef8ce1806732">toInt</a>.</p>

</div>
</div>

### mask() {#ac0e6b7c81164e9fdd0d67fa47ed2b925}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">BT::BitMask BT::MachineEvaluator::mask (<a href="/web-llvm/docs/api/classes/llvm/register">Register</a> Reg, unsigned Sub)</td>
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



<p>Declaration at line 465 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/hexagon/bittracker-h">BitTracker.h</a>, definition at line 707 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/hexagon/bittracker-cpp">BitTracker.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/silowercontrolflow-cpp/#a4868c5d81c5ccc98c47aeab6244346a0">assert</a> and <a href="#a64ee9ca87205e764e0382240030f87ee">getRegBitWidth</a>.</p>


<p>Referenced by <a href="#a1366c4865d7c8ca31dcf403406e3b291">evaluate</a> and <a href="#a9a70d4969d8d43a9c9b324f692bc8ecd">getCell</a>.</p>

</div>
</div>

### putCell() {#a8944fc547212f985ad3f9706eb5b8725}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void BT::MachineEvaluator::putCell (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/structs/llvm/bittracker/registerref">RegisterRef</a> &amp; RR, <a href="/web-llvm/docs/api/structs/llvm/bittracker/registercell">RegisterCell</a> RC, <a href="/web-llvm/docs/api/structs/llvm/bittracker/#ac0eea221b9e05301dfd8cb9ac47bc7d8">CellMapType</a> &amp; M)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Declaration at line 400 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/hexagon/bittracker-h">BitTracker.h</a>, definition at line 375 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/hexagon/bittracker-cpp">BitTracker.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/silowercontrolflow-cpp/#a4868c5d81c5ccc98c47aeab6244346a0">assert</a>, <a href="/web-llvm/docs/api/classes/llvm/register/#ab203bbcbc320180b1da9e9a92ee0c784">llvm::Register::isVirtual</a>, <a href="/web-llvm/docs/api/structs/llvm/bittracker/registerref/#a83d460802fba9c074af90710d239f516">llvm::BitTracker::RegisterRef::Reg</a>, <a href="/web-llvm/docs/api/structs/llvm/bittracker/registercell/#aa6e2cfce750a7dddf5e3bc60ad55f1b1">llvm::BitTracker::RegisterCell::regify</a> and <a href="/web-llvm/docs/api/structs/llvm/bittracker/registerref/#afd26bd676aebea77891d6d204dd804d5">llvm::BitTracker::RegisterRef::Sub</a>.</p>


<p>Referenced by <a href="#a1366c4865d7c8ca31dcf403406e3b291">evaluate</a>, <a href="/web-llvm/docs/api/structs/llvm/hexagonevaluator/#a49b4d08c8b0024b97c7e090a0b3e50f6">llvm::HexagonEvaluator::evaluate</a> and <a href="#ae25072ca0ead457f1c782c2859f9664b">~MachineEvaluator</a>.</p>

</div>
</div>

### toInt() {#ab0604c5bb97437a4cee3ef8ce1806732}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">uint64_t BT::MachineEvaluator::toInt (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/structs/llvm/bittracker/registercell">RegisterCell</a> &amp; A)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Declaration at line 414 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/hexagon/bittracker-h">BitTracker.h</a>, definition at line 397 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/hexagon/bittracker-cpp">BitTracker.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/files/lib/lib/ir/builtingcs-cpp/#a2e38c85003a042421cde1647632d0b72">A</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/silowercontrolflow-cpp/#a4868c5d81c5ccc98c47aeab6244346a0">assert</a> and <a href="#a6a2033c0f951975bebfc27e263f5e9c0">isInt</a>.</p>

</div>
</div>

### track() {#a8466bee1159e47fe78597c5cd617270f}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">virtual bool llvm::BitTracker::MachineEvaluator::track (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/targetregisterclass">TargetRegisterClass</a> * RC)</td>
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



<p>Definition at line 467 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/hexagon/bittracker-h">BitTracker.h</a>.</p>


<p>Referenced by <a href="#a9a70d4969d8d43a9c9b324f692bc8ecd">getCell</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Public Member Attributes

### MRI {#a6d5cfd7739a2939cd9418586c8aa1a3c}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">MachineRegisterInfo&amp; llvm::BitTracker::MachineEvaluator::MRI</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 491 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/hexagon/bittracker-h">BitTracker.h</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/structs/llvm/hexagonevaluator/#a49b4d08c8b0024b97c7e090a0b3e50f6">llvm::HexagonEvaluator::evaluate</a>, <a href="#a9a70d4969d8d43a9c9b324f692bc8ecd">getCell</a>, <a href="#a64ee9ca87205e764e0382240030f87ee">getRegBitWidth</a>, <a href="#a4301e1f2a5607d796c5505a5a5919501">MachineEvaluator</a> and <a href="/web-llvm/docs/api/structs/llvm/hexagonevaluator/#a26c72fb657ffaea1a961279c6d3a80fb">llvm::HexagonEvaluator::mask</a>.</p>

</div>
</div>

### TRI {#a440983b5e0f6fc9cd9771b51f1f998dd}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">const TargetRegisterInfo&amp; llvm::BitTracker::MachineEvaluator::TRI</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 490 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/hexagon/bittracker-h">BitTracker.h</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/structs/llvm/hexagonevaluator/#a82ef22a357f6b3f17e77b598df0ca45f">llvm::HexagonEvaluator::composeWithSubRegIndex</a>, <a href="#a983992af4e6d9497a917c11bb9212306">getPhysRegBitWidth</a>, <a href="/web-llvm/docs/api/structs/llvm/hexagonevaluator/#a34cd40aa7d878b134c54cf218b4fb5a6">llvm::HexagonEvaluator::getPhysRegBitWidth</a>, <a href="#a64ee9ca87205e764e0382240030f87ee">getRegBitWidth</a>, <a href="#a4301e1f2a5607d796c5505a5a5919501">MachineEvaluator</a> and <a href="/web-llvm/docs/api/structs/llvm/hexagonevaluator/#a26c72fb657ffaea1a961279c6d3a80fb">llvm::HexagonEvaluator::mask</a>.</p>

</div>
</div>

</div>

<hr/>

The documentation for this struct was generated from the following files:

<ul>
<li><a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/hexagon/bittracker-cpp">BitTracker.cpp</a></li>
<li><a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/hexagon/bittracker-h">BitTracker.h</a></li>
</ul>

<hr/>

<p class="doxyGeneratedBy">Generated via <a href="https://github.com/xpack/doxygen2docusaurus">doxygen2docusaurus</a> by <a href="https://www.doxygen.nl">Doxygen</a> 1.14.0.</p>

</div>
