---

# DO NOT EDIT!
# Automatically generated via doxygen2docusaurus by Doxygen.

slug: /api/classes/anonymous-hexagonbitsimplify-cpp-/bitsimplification
custom_edit_url: null
toc_max_heading_level: 4
keywords:
  - doxygen
  - reference
  - class

---

<div class="doxyPage">

# `BitSimplification` Class



## Declaration

<div class="doxyDeclaration">
class anonymous{HexagonBitSimplify.cpp}::BitSimplification { ... }
</div>

## Base class

<table class="doxyMembersIndex">

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">class</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="/web-llvm/docs/api/classes/anonymous-hexagonbitsimplify-cpp-/transformation">Transformation</a></td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a0a75d848a28b86d55efb76e4269b384c">BitSimplification</a> (BitTracker &amp;bt, const MachineDominatorTree &amp;mdt, const HexagonInstrInfo &amp;hii, const HexagonRegisterInfo &amp;hri, MachineRegisterInfo &amp;mri, MachineFunction &amp;mf)</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a7ae2252105ba3f43b639d6648a219a85">processBlock</a> (MachineBasicBlock &amp;B, const RegisterSet &amp;AVs) override</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#add9028221a13fd42150604744a576468">matchHalf</a> (unsigned SelfR, const BitTracker::RegisterCell &amp;RC, unsigned B, RegHalf &amp;RH)</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ab513b7c8dedcac122e861e5d009de984">validateReg</a> (BitTracker::RegisterRef R, unsigned Opc, unsigned OpNum)</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#aedfa7a89c565c7c031b16a0ee4fbae67">matchPackhl</a> (unsigned SelfR, const BitTracker::RegisterCell &amp;RC, BitTracker::RegisterRef &amp;Rs, BitTracker::RegisterRef &amp;Rt)</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">unsigned</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#adda56b4eb3c5fe2fa45603d530ece30a">getCombineOpcode</a> (bool HLow, bool LLow)</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a70a278e540c0e5716a08b7fcb7361ef1">genStoreUpperHalf</a> (MachineInstr *MI)</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a75490a2e9ae6b229ed36bde82b5663be">genStoreImmediate</a> (MachineInstr *MI)</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a0abf721cb0680b46fe561ec761e3844b">genPackhl</a> (MachineInstr *MI, BitTracker::RegisterRef RD, const BitTracker::RegisterCell &amp;RC)</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ae06894162944d92dce42d08c215e0bf8">genExtractHalf</a> (MachineInstr *MI, BitTracker::RegisterRef RD, const BitTracker::RegisterCell &amp;RC)</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a588c27cc17deff55fcec746bde01980c">genCombineHalf</a> (MachineInstr *MI, BitTracker::RegisterRef RD, const BitTracker::RegisterCell &amp;RC)</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ad1a41b2d1cb7702844d797b38f77c451">genExtractLow</a> (MachineInstr *MI, BitTracker::RegisterRef RD, const BitTracker::RegisterCell &amp;RC)</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a7c45327690c25e599229848eeb474d00">genBitSplit</a> (MachineInstr *MI, BitTracker::RegisterRef RD, const BitTracker::RegisterCell &amp;RC, const RegisterSet &amp;AVs)</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a058b7695ac1e57f7eff0c002f495ed85">simplifyTstbit</a> (MachineInstr *MI, BitTracker::RegisterRef RD, const BitTracker::RegisterCell &amp;RC)</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#aadada608f68895b72704dbfe38637866">simplifyExtractLow</a> (MachineInstr *MI, BitTracker::RegisterRef RD, const BitTracker::RegisterCell &amp;RC, const RegisterSet &amp;AVs)</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a863e2e4c31b0271b1cf4f7a0bcdd01fc">simplifyRCmp0</a> (MachineInstr *MI, BitTracker::RegisterRef RD)</td>
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

## Private Member Attributes Index

<table class="doxyMembersIndex">

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">std::vector&lt; <a href="/web-llvm/docs/api/classes/llvm/machineinstr">MachineInstr</a> * &gt;</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a58e560fc356a11bf8a81f9fb3cb1832f">NewMIs</a></td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/machinedominatortree">MachineDominatorTree</a> &amp;</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ab048aa12f127e5b46f83ca60b00163b2">MDT</a></td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/hexagoninstrinfo">HexagonInstrInfo</a> &amp;</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#abf058450b16f377ba471309d9d73c7fc">HII</a></td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/hexagonregisterinfo">HexagonRegisterInfo</a> &amp;</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a5e70aa45b3fc4174bf7398fa77d9b5da">HRI</a></td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#aef233c545cb906b66d05ca9ca0a19e3d">MRI</a></td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/machinefunction">MachineFunction</a> &amp;</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a1f971f7a92f2f1f6cad3a23d420596e4">MF</a></td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/structs/llvm/bittracker">BitTracker</a> &amp;</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#af34d51c97b1f35ce43e49549e0b05a53">BT</a></td>
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


<p>Definition at line 1773 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/hexagon/hexagonbitsimplify-cpp">HexagonBitSimplify.cpp</a>.</p>


<div class="doxySectionDef">

## Public Constructors

### BitSimplification() {#a0a75d848a28b86d55efb76e4269b384c}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">anonymous{HexagonBitSimplify.cpp}::BitSimplification::BitSimplification (<a href="/web-llvm/docs/api/structs/llvm/bittracker">BitTracker</a> &amp; bt, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/machinedominatortree">MachineDominatorTree</a> &amp; mdt, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/hexagoninstrinfo">HexagonInstrInfo</a> &amp; hii, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/hexagonregisterinfo">HexagonRegisterInfo</a> &amp; hri, <a href="/web-llvm/docs/api/classes/llvm/machineregisterinfo">MachineRegisterInfo</a> &amp; mri, <a href="/web-llvm/docs/api/classes/llvm/machinefunction">MachineFunction</a> &amp; mf)</td>
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



<p>Definition at line 1775 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/hexagon/hexagonbitsimplify-cpp">HexagonBitSimplify.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/classes/anonymous-hexagonbitsimplify-cpp-/transformation/#a567b376259e3121b97947982911e59e7">anonymous{HexagonBitSimplify.cpp}::Transformation::Transformation</a> and <a href="/web-llvm/docs/api/files/lib/lib/analysis/basicaliasanalysis-cpp/#af6d5cafbdfc5313e65d990120021a3ec">true</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Public Member Functions

### processBlock() {#a7ae2252105ba3f43b639d6648a219a85}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool BitSimplification::processBlock (<a href="/web-llvm/docs/api/classes/llvm/machinebasicblock">MachineBasicBlock</a> &amp; B, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/structs/anonymous-hexagonbitsimplify-cpp-/registerset">RegisterSet</a> &amp; AVs)</td>
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



<p>Definition at line 1781 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/hexagon/hexagonbitsimplify-cpp">HexagonBitSimplify.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/files/lib/lib/ir/builtingcs-cpp/#ae76959fe811ba090de4cba69ac00f1da">B</a>, <a href="/web-llvm/docs/api/structs/anonymous-hexagonbitsimplify-cpp-/registerset/#a98ae15330522474ced863e56cb500a05">anonymous{HexagonBitSimplify.cpp}::RegisterSet::clear</a>, <a href="/web-llvm/docs/api/structs/anonymous-hexagonbitsimplify-cpp-/registerset/#abf7adc1a515a6a5764bb86519452c462">anonymous{HexagonBitSimplify.cpp}::RegisterSet::count</a>, <a href="/web-llvm/docs/api/classes/anonymous-hexagonbitsimplify-cpp-/hexagonbitsimplify/#a8e3ebf47bfdde7c6ce8235ca71190e1b">anonymous{HexagonBitSimplify.cpp}::HexagonBitSimplify::getFinalVRegClass</a>, <a href="/web-llvm/docs/api/classes/llvm/targetregisterclass/#a32a8b65536822d50171455a6baa81da7">llvm::TargetRegisterClass::getID</a>, <a href="/web-llvm/docs/api/classes/anonymous-hexagonbitsimplify-cpp-/hexagonbitsimplify/#ac6e875574acc456304c0d27912219536">anonymous{HexagonBitSimplify.cpp}::HexagonBitSimplify::getInstrDefs</a>, <a href="/web-llvm/docs/api/files/lib/lib/support/md5-cpp/#ac0eafdc9ee161b71e7af98af736952fd">I</a>, <a href="/web-llvm/docs/api/structs/anonymous-hexagonbitsimplify-cpp-/registerset/#a91e9ba1c1c62c8534678e831d695ff41">anonymous{HexagonBitSimplify.cpp}::RegisterSet::insert</a>, <a href="/web-llvm/docs/api/classes/llvm/machineoperand/#a75eb135014670ce946e78739cdc9b51b">llvm::MachineOperand::isDef</a>, <a href="/web-llvm/docs/api/classes/llvm/machineoperand/#a4c9594c955fec80c73ddd964b5efd554">llvm::MachineOperand::isReg</a>, <a href="/web-llvm/docs/api/files/lib/lib/codegen/lib/codegen/globalisel/irtranslator-cpp/#abe44dfdea65b4f7e11e0a608ab708b76">MI</a> and <a href="/web-llvm/docs/api/structs/llvm/bittracker/registerref/#a83d460802fba9c074af90710d239f516">llvm::BitTracker::RegisterRef::Reg</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Private Member Functions

### genBitSplit() {#a7c45327690c25e599229848eeb474d00}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool BitSimplification::genBitSplit (<a href="/web-llvm/docs/api/classes/llvm/machineinstr">MachineInstr</a> * MI, <a href="/web-llvm/docs/api/structs/llvm/bittracker/registerref">BitTracker::RegisterRef</a> RD, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/structs/llvm/bittracker/registercell">BitTracker::RegisterCell</a> &amp; RC, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/structs/anonymous-hexagonbitsimplify-cpp-/registerset">RegisterSet</a> &amp; AVs)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 1806 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/hexagon/hexagonbitsimplify-cpp">HexagonBitSimplify.cpp</a>.</p>

</div>
</div>

### genCombineHalf() {#a588c27cc17deff55fcec746bde01980c}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool BitSimplification::genCombineHalf (<a href="/web-llvm/docs/api/classes/llvm/machineinstr">MachineInstr</a> * MI, <a href="/web-llvm/docs/api/structs/llvm/bittracker/registerref">BitTracker::RegisterRef</a> RD, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/structs/llvm/bittracker/registercell">BitTracker::RegisterCell</a> &amp; RC)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 1802 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/hexagon/hexagonbitsimplify-cpp">HexagonBitSimplify.cpp</a>.</p>

</div>
</div>

### genExtractHalf() {#ae06894162944d92dce42d08c215e0bf8}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool BitSimplification::genExtractHalf (<a href="/web-llvm/docs/api/classes/llvm/machineinstr">MachineInstr</a> * MI, <a href="/web-llvm/docs/api/structs/llvm/bittracker/registerref">BitTracker::RegisterRef</a> RD, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/structs/llvm/bittracker/registercell">BitTracker::RegisterCell</a> &amp; RC)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 1800 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/hexagon/hexagonbitsimplify-cpp">HexagonBitSimplify.cpp</a>.</p>

</div>
</div>

### genExtractLow() {#ad1a41b2d1cb7702844d797b38f77c451}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool BitSimplification::genExtractLow (<a href="/web-llvm/docs/api/classes/llvm/machineinstr">MachineInstr</a> * MI, <a href="/web-llvm/docs/api/structs/llvm/bittracker/registerref">BitTracker::RegisterRef</a> RD, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/structs/llvm/bittracker/registercell">BitTracker::RegisterCell</a> &amp; RC)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 1804 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/hexagon/hexagonbitsimplify-cpp">HexagonBitSimplify.cpp</a>.</p>

</div>
</div>

### genPackhl() {#a0abf721cb0680b46fe561ec761e3844b}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool BitSimplification::genPackhl (<a href="/web-llvm/docs/api/classes/llvm/machineinstr">MachineInstr</a> * MI, <a href="/web-llvm/docs/api/structs/llvm/bittracker/registerref">BitTracker::RegisterRef</a> RD, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/structs/llvm/bittracker/registercell">BitTracker::RegisterCell</a> &amp; RC)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 1798 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/hexagon/hexagonbitsimplify-cpp">HexagonBitSimplify.cpp</a>.</p>

</div>
</div>

### genStoreImmediate() {#a75490a2e9ae6b229ed36bde82b5663be}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool BitSimplification::genStoreImmediate (<a href="/web-llvm/docs/api/classes/llvm/machineinstr">MachineInstr</a> * MI)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 1797 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/hexagon/hexagonbitsimplify-cpp">HexagonBitSimplify.cpp</a>.</p>

</div>
</div>

### genStoreUpperHalf() {#a70a278e540c0e5716a08b7fcb7361ef1}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool BitSimplification::genStoreUpperHalf (<a href="/web-llvm/docs/api/classes/llvm/machineinstr">MachineInstr</a> * MI)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 1796 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/hexagon/hexagonbitsimplify-cpp">HexagonBitSimplify.cpp</a>.</p>

</div>
</div>

### getCombineOpcode() {#adda56b4eb3c5fe2fa45603d530ece30a}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">unsigned BitSimplification::getCombineOpcode (bool HLow, bool LLow)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 1794 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/hexagon/hexagonbitsimplify-cpp">HexagonBitSimplify.cpp</a>.</p>

</div>
</div>

### matchHalf() {#add9028221a13fd42150604744a576468}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool BitSimplification::matchHalf (unsigned SelfR, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/structs/llvm/bittracker/registercell">BitTracker::RegisterCell</a> &amp; RC, unsigned B, RegHalf &amp; RH)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 1788 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/hexagon/hexagonbitsimplify-cpp">HexagonBitSimplify.cpp</a>.</p>

</div>
</div>

### matchPackhl() {#aedfa7a89c565c7c031b16a0ee4fbae67}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool BitSimplification::matchPackhl (unsigned SelfR, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/structs/llvm/bittracker/registercell">BitTracker::RegisterCell</a> &amp; RC, <a href="/web-llvm/docs/api/structs/llvm/bittracker/registerref">BitTracker::RegisterRef</a> &amp; Rs, <a href="/web-llvm/docs/api/structs/llvm/bittracker/registerref">BitTracker::RegisterRef</a> &amp; Rt)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 1792 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/hexagon/hexagonbitsimplify-cpp">HexagonBitSimplify.cpp</a>.</p>

</div>
</div>

### simplifyExtractLow() {#aadada608f68895b72704dbfe38637866}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool BitSimplification::simplifyExtractLow (<a href="/web-llvm/docs/api/classes/llvm/machineinstr">MachineInstr</a> * MI, <a href="/web-llvm/docs/api/structs/llvm/bittracker/registerref">BitTracker::RegisterRef</a> RD, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/structs/llvm/bittracker/registercell">BitTracker::RegisterCell</a> &amp; RC, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/structs/anonymous-hexagonbitsimplify-cpp-/registerset">RegisterSet</a> &amp; AVs)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 1810 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/hexagon/hexagonbitsimplify-cpp">HexagonBitSimplify.cpp</a>.</p>

</div>
</div>

### simplifyRCmp0() {#a863e2e4c31b0271b1cf4f7a0bcdd01fc}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool BitSimplification::simplifyRCmp0 (<a href="/web-llvm/docs/api/classes/llvm/machineinstr">MachineInstr</a> * MI, <a href="/web-llvm/docs/api/structs/llvm/bittracker/registerref">BitTracker::RegisterRef</a> RD)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 1812 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/hexagon/hexagonbitsimplify-cpp">HexagonBitSimplify.cpp</a>.</p>

</div>
</div>

### simplifyTstbit() {#a058b7695ac1e57f7eff0c002f495ed85}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool BitSimplification::simplifyTstbit (<a href="/web-llvm/docs/api/classes/llvm/machineinstr">MachineInstr</a> * MI, <a href="/web-llvm/docs/api/structs/llvm/bittracker/registerref">BitTracker::RegisterRef</a> RD, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/structs/llvm/bittracker/registercell">BitTracker::RegisterCell</a> &amp; RC)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 1808 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/hexagon/hexagonbitsimplify-cpp">HexagonBitSimplify.cpp</a>.</p>

</div>
</div>

### validateReg() {#ab513b7c8dedcac122e861e5d009de984}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool BitSimplification::validateReg (<a href="/web-llvm/docs/api/structs/llvm/bittracker/registerref">BitTracker::RegisterRef</a> R, unsigned Opc, unsigned OpNum)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 1790 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/hexagon/hexagonbitsimplify-cpp">HexagonBitSimplify.cpp</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Private Member Attributes

### BT {#af34d51c97b1f35ce43e49549e0b05a53}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">BitTracker&amp; anonymous{HexagonBitSimplify.cpp}::BitSimplification::BT</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 1823 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/hexagon/hexagonbitsimplify-cpp">HexagonBitSimplify.cpp</a>.</p>

</div>
</div>

### HII {#abf058450b16f377ba471309d9d73c7fc}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">const HexagonInstrInfo&amp; anonymous{HexagonBitSimplify.cpp}::BitSimplification::HII</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 1819 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/hexagon/hexagonbitsimplify-cpp">HexagonBitSimplify.cpp</a>.</p>

</div>
</div>

### HRI {#a5e70aa45b3fc4174bf7398fa77d9b5da}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">const HexagonRegisterInfo&amp; anonymous{HexagonBitSimplify.cpp}::BitSimplification::HRI</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 1820 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/hexagon/hexagonbitsimplify-cpp">HexagonBitSimplify.cpp</a>.</p>

</div>
</div>

### MDT {#ab048aa12f127e5b46f83ca60b00163b2}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">const MachineDominatorTree&amp; anonymous{HexagonBitSimplify.cpp}::BitSimplification::MDT</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 1818 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/hexagon/hexagonbitsimplify-cpp">HexagonBitSimplify.cpp</a>.</p>

</div>
</div>

### MF {#a1f971f7a92f2f1f6cad3a23d420596e4}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">MachineFunction&amp; anonymous{HexagonBitSimplify.cpp}::BitSimplification::MF</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 1822 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/hexagon/hexagonbitsimplify-cpp">HexagonBitSimplify.cpp</a>.</p>

</div>
</div>

### MRI {#aef233c545cb906b66d05ca9ca0a19e3d}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">MachineRegisterInfo&amp; anonymous{HexagonBitSimplify.cpp}::BitSimplification::MRI</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 1821 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/hexagon/hexagonbitsimplify-cpp">HexagonBitSimplify.cpp</a>.</p>

</div>
</div>

### NewMIs {#a58e560fc356a11bf8a81f9fb3cb1832f}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">std::vector&lt;MachineInstr*&gt; anonymous{HexagonBitSimplify.cpp}::BitSimplification::NewMIs</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 1816 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/hexagon/hexagonbitsimplify-cpp">HexagonBitSimplify.cpp</a>.</p>

</div>
</div>

</div>

<hr/>

The documentation for this class was generated from the following file:

<ul>
<li><a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/hexagon/hexagonbitsimplify-cpp">HexagonBitSimplify.cpp</a></li>
</ul>

<hr/>

<p class="doxyGeneratedBy">Generated via <a href="https://github.com/xpack/doxygen2docusaurus">doxygen2docusaurus</a> by <a href="https://www.doxygen.nl">Doxygen</a> 1.15.0.</p>

</div>
