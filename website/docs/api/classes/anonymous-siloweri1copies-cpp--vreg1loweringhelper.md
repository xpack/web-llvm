---

# DO NOT EDIT!
# Automatically generated via doxygen2docusaurus by Doxygen.

slug: /api/classes/anonymous-siloweri1copies-cpp-/vreg1loweringhelper
custom_edit_url: null
toc_max_heading_level: 4
keywords:
  - doxygen
  - reference
  - class

---

<div class="doxyPage">

# `Vreg1LoweringHelper` Class



## Declaration

<div class="doxyDeclaration">
class anonymous{SILowerI1Copies.cpp}::Vreg1LoweringHelper { ... }
</div>

## Base class

<table class="doxyMembersIndex">

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">class</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/philoweringhelper">PhiLoweringHelper</a></td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a22a13176b4055ad945163e17b880be43">Vreg1LoweringHelper</a> (MachineFunction *MF, MachineDominatorTree *DT, MachinePostDominatorTree *PDT)</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a2961ec025986c8fb2c4e9981302383a6">markAsLaneMask</a> (Register DstReg) const override</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ae033ec699e4956dff9206a339674990f">getCandidatesForLowering</a> (SmallVectorImpl&lt; MachineInstr * &gt; &amp;Vreg1Phis) const override</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ad8ddb8460838860b8d1d38555049f08b">collectIncomingValuesFromPhi</a> (const MachineInstr *MI, SmallVectorImpl&lt; Incoming &gt; &amp;Incomings) const override</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a2034914dc6524f4ca5b13bbd22635446">replaceDstReg</a> (Register NewReg, Register OldReg, MachineBasicBlock *MBB) override</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#aa667006252ada935940ba209eef256e3">buildMergeLaneMasks</a> (MachineBasicBlock &amp;MBB, MachineBasicBlock::iterator I, const DebugLoc &amp;DL, Register DstReg, Register PrevReg, Register CurReg) override</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#aaf318c1f57715eaebecb023edf2005f9">constrainAsLaneMask</a> (Incoming &amp;In) override</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a6cf0eec5c3acd7ff97e6e5dec15a97d6">lowerCopiesFromI1</a> ()</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#adaf0e50d1e23ce068ed74fe079552d51">lowerCopiesToI1</a> ()</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ab0d21052f1c1a7b915dfa38ab641db71">cleanConstrainRegs</a> (bool Changed)</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a7705c8d988a3ccfc9c35783759cd7334">isVreg1</a> (Register Reg) const</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/denseset">DenseSet</a>&lt; <a href="/web-llvm/docs/api/classes/llvm/register">Register</a> &gt;</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ae361a8e710393612bfb5dd0721915984">ConstrainRegs</a></td>
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


<p>Definition at line 39 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/siloweri1copies-cpp">SILowerI1Copies.cpp</a>.</p>


<div class="doxySectionDef">

## Public Constructors

### Vreg1LoweringHelper() {#a22a13176b4055ad945163e17b880be43}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">anonymous{SILowerI1Copies.cpp}::Vreg1LoweringHelper::Vreg1LoweringHelper (<a href="/web-llvm/docs/api/classes/llvm/machinefunction">MachineFunction</a> * MF, <a href="/web-llvm/docs/api/classes/llvm/machinedominatortree">MachineDominatorTree</a> * DT, <a href="/web-llvm/docs/api/classes/llvm/machinepostdominatortree">MachinePostDominatorTree</a> * PDT)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 41 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/siloweri1copies-cpp">SILowerI1Copies.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/classes/llvm/philoweringhelper/#a5c654bc63075ea6446978668af9b23c7">llvm::PhiLoweringHelper::DT</a>, <a href="/web-llvm/docs/api/classes/llvm/philoweringhelper/#a80b1d6c9ae89f83c6918aaee904070c3">llvm::PhiLoweringHelper::MF</a>, <a href="/web-llvm/docs/api/classes/llvm/philoweringhelper/#aa60a09fb7712789a3e5e58806b4aa10d">llvm::PhiLoweringHelper::PDT</a> and <a href="/web-llvm/docs/api/classes/llvm/philoweringhelper/#a2a55e57cd0a8346f83e5e2ebe32beb65">llvm::PhiLoweringHelper::PhiLoweringHelper</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Public Member Functions

### buildMergeLaneMasks() {#aa667006252ada935940ba209eef256e3}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void Vreg1LoweringHelper::buildMergeLaneMasks (<a href="/web-llvm/docs/api/classes/llvm/machinebasicblock">MachineBasicBlock</a> &amp; MBB, <a href="/web-llvm/docs/api/classes/llvm/machinebasicblock/#ae34c996b58df9b9ce6695a0c8b70c533">MachineBasicBlock::iterator</a> I, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/debugloc">DebugLoc</a> &amp; DL, <a href="/web-llvm/docs/api/classes/llvm/register">Register</a> DstReg, <a href="/web-llvm/docs/api/classes/llvm/register">Register</a> PrevReg, <a href="/web-llvm/docs/api/classes/llvm/register">Register</a> CurReg)</td>
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



<p>Definition at line 56 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/siloweri1copies-cpp">SILowerI1Copies.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/classes/llvm/machineinstrbuilder/#a6c1f959947905135c7dd215b64957654">llvm::MachineInstrBuilder::addImm</a>, <a href="/web-llvm/docs/api/classes/llvm/machineinstrbuilder/#a927857fc69e4b4f0cde307f86f180df5">llvm::MachineInstrBuilder::addReg</a>, <a href="/web-llvm/docs/api/classes/llvm/philoweringhelper/#af740485c69305e62a9c4f68369437174">llvm::PhiLoweringHelper::AndN2Op</a>, <a href="/web-llvm/docs/api/classes/llvm/philoweringhelper/#a4f5a15970e967ccbd3fe821e6d843fdb">llvm::PhiLoweringHelper::AndOp</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a17e04afcf0c5efeb0eb6a9a45287b5e4">llvm::BuildMI</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a94b43ba7ddb7fcd4dab5bf28c829a423">llvm::createLaneMaskReg</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/arm/armslshardening-cpp/#ad467c4ab9119043f9b7750ab986be61a">DL</a>, <a href="/web-llvm/docs/api/classes/llvm/philoweringhelper/#ab28c61f3424d42ec86dca0bce1b10266">llvm::PhiLoweringHelper::ExecReg</a>, <a href="/web-llvm/docs/api/files/lib/lib/support/md5-cpp/#ac0eafdc9ee161b71e7af98af736952fd">I</a>, <a href="/web-llvm/docs/api/classes/llvm/philoweringhelper/#ae3b1d4a4b487362c26550bdbab4ea36a">llvm::PhiLoweringHelper::isConstantLaneMask</a>, <a href="/web-llvm/docs/api/classes/llvm/philoweringhelper/#acefa582f93360081f06fe71aef54da34">llvm::PhiLoweringHelper::LaneMaskRegAttrs</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/arm/armslshardening-cpp/#a5958512eae2979bd2eb383977996a600">MBB</a>, <a href="/web-llvm/docs/api/classes/llvm/philoweringhelper/#a587ec89e73d2290668b58a5e7f771f35">llvm::PhiLoweringHelper::MRI</a>, <a href="/web-llvm/docs/api/classes/llvm/philoweringhelper/#a1e02e6fd3b0984f62948db4061d4ca44">llvm::PhiLoweringHelper::OrN2Op</a>, <a href="/web-llvm/docs/api/classes/llvm/philoweringhelper/#a579b1d38ea323d182d66c8db95263877">llvm::PhiLoweringHelper::OrOp</a>, <a href="/web-llvm/docs/api/classes/llvm/philoweringhelper/#ab37b9650dd3ff2294ac2556672c52eb3">llvm::PhiLoweringHelper::TII</a> and <a href="/web-llvm/docs/api/classes/llvm/philoweringhelper/#a4d640108a701d456f16d8b3ea85a7aa1">llvm::PhiLoweringHelper::XorOp</a>.</p>


<p>Referenced by <a href="#adaf0e50d1e23ce068ed74fe079552d51">lowerCopiesToI1</a>.</p>

</div>
</div>

### cleanConstrainRegs() {#ab0d21052f1c1a7b915dfa38ab641db71}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool anonymous{SILowerI1Copies.cpp}::Vreg1LoweringHelper::cleanConstrainRegs (bool Changed)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 64 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/siloweri1copies-cpp">SILowerI1Copies.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/silowercontrolflow-cpp/#a4868c5d81c5ccc98c47aeab6244346a0">assert</a> and <a href="/web-llvm/docs/api/classes/llvm/philoweringhelper/#a587ec89e73d2290668b58a5e7f771f35">llvm::PhiLoweringHelper::MRI</a>.</p>

</div>
</div>

### collectIncomingValuesFromPhi() {#ad8ddb8460838860b8d1d38555049f08b}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void Vreg1LoweringHelper::collectIncomingValuesFromPhi (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/machineinstr">MachineInstr</a> * MI, <a href="/web-llvm/docs/api/classes/llvm/smallvectorimpl">SmallVectorImpl</a>&lt; <a href="/web-llvm/docs/api/structs/llvm/incoming">Incoming</a> &gt; &amp; Incomings)</td>
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



<p>Definition at line 51 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/siloweri1copies-cpp">SILowerI1Copies.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/silowercontrolflow-cpp/#a4868c5d81c5ccc98c47aeab6244346a0">assert</a>, <a href="/web-llvm/docs/api/classes/llvm/smallvectorimpl/#a396fcfee6914c76974b73c3d203da6a5">llvm::SmallVectorImpl&lt; T &gt;::emplace_back</a>, <a href="/web-llvm/docs/api/classes/llvm/machineinstr/#a0363204b5fbab08a46f5a7cd7f376f78">llvm::MachineInstr::getOpcode</a>, <a href="/web-llvm/docs/api/classes/llvm/machineinstr/#ad67c9230577a0b640c52852c75c93939">llvm::MachineInstr::getOperand</a>, <a href="/web-llvm/docs/api/classes/llvm/machineoperand/#ac0035d7c1c860501c877c20e6e93297b">llvm::MachineOperand::getReg</a>, <a href="/web-llvm/docs/api/classes/llvm/machineoperand/#a028a8c5113d40d8c3f4427053bf36738">llvm::MachineOperand::getSubReg</a>, <a href="/web-llvm/docs/api/classes/llvm/philoweringhelper/#a4b9e1c74c0536fbade814091fd3c8ee3">llvm::PhiLoweringHelper::isLaneMaskReg</a>, <a href="/web-llvm/docs/api/classes/llvm/machineinstr/#ad43bf1af480830a4d6604e969e3f38e9">llvm::MachineInstr::isPHI</a>, <a href="#a7705c8d988a3ccfc9c35783759cd7334">isVreg1</a>, <a href="/web-llvm/docs/api/files/lib/lib/codegen/lib/codegen/globalisel/irtranslator-cpp/#abe44dfdea65b4f7e11e0a608ab708b76">MI</a>, <a href="/web-llvm/docs/api/classes/llvm/philoweringhelper/#a587ec89e73d2290668b58a5e7f771f35">llvm::PhiLoweringHelper::MRI</a>, <a href="/web-llvm/docs/api/classes/llvm/philoweringhelper/#a5cb5b9ea9fecf728e509eb1d1c749e36">llvm::PhiLoweringHelper::PhiRegisters</a> and <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/utils/mem2reg-cpp/#a6fde3eb6ca09ddf2fd76432176d817bb">Register</a>.</p>

</div>
</div>

### constrainAsLaneMask() {#aaf318c1f57715eaebecb023edf2005f9}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void Vreg1LoweringHelper::constrainAsLaneMask (<a href="/web-llvm/docs/api/structs/llvm/incoming">Incoming</a> &amp; In)</td>
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



<p>Definition at line 60 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/siloweri1copies-cpp">SILowerI1Copies.cpp</a>.</p>

</div>
</div>

### getCandidatesForLowering() {#ae033ec699e4956dff9206a339674990f}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void Vreg1LoweringHelper::getCandidatesForLowering (<a href="/web-llvm/docs/api/classes/llvm/smallvectorimpl">SmallVectorImpl</a>&lt; <a href="/web-llvm/docs/api/classes/llvm/machineinstr">MachineInstr</a> * &gt; &amp; Vreg1Phis)</td>
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



<p>Definition at line 49 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/siloweri1copies-cpp">SILowerI1Copies.cpp</a>.</p>


<p>References <a href="#a7705c8d988a3ccfc9c35783759cd7334">isVreg1</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/arm/armslshardening-cpp/#a5958512eae2979bd2eb383977996a600">MBB</a>, <a href="/web-llvm/docs/api/classes/llvm/philoweringhelper/#a80b1d6c9ae89f83c6918aaee904070c3">llvm::PhiLoweringHelper::MF</a>, <a href="/web-llvm/docs/api/files/lib/lib/codegen/lib/codegen/globalisel/irtranslator-cpp/#abe44dfdea65b4f7e11e0a608ab708b76">MI</a> and <a href="/web-llvm/docs/api/classes/llvm/smallvectortemplatebase/#af42bfbc067df27c19ee2fc859df58799">llvm::SmallVectorTemplateBase&lt; T, bool &gt;::push_back</a>.</p>

</div>
</div>

### isVreg1() {#a7705c8d988a3ccfc9c35783759cd7334}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool anonymous{SILowerI1Copies.cpp}::Vreg1LoweringHelper::isVreg1 (<a href="/web-llvm/docs/api/classes/llvm/register">Register</a> Reg)</td>
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



<p>Definition at line 65 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/siloweri1copies-cpp">SILowerI1Copies.cpp</a>.</p>


<p>Reference <a href="/web-llvm/docs/api/classes/llvm/philoweringhelper/#a587ec89e73d2290668b58a5e7f771f35">llvm::PhiLoweringHelper::MRI</a>.</p>


<p>Referenced by <a href="#ad8ddb8460838860b8d1d38555049f08b">collectIncomingValuesFromPhi</a>, <a href="#ae033ec699e4956dff9206a339674990f">getCandidatesForLowering</a>, <a href="#a6cf0eec5c3acd7ff97e6e5dec15a97d6">lowerCopiesFromI1</a> and <a href="#adaf0e50d1e23ce068ed74fe079552d51">lowerCopiesToI1</a>.</p>

</div>
</div>

### lowerCopiesFromI1() {#a6cf0eec5c3acd7ff97e6e5dec15a97d6}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool Vreg1LoweringHelper::lowerCopiesFromI1 ()</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 62 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/siloweri1copies-cpp">SILowerI1Copies.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/classes/llvm/machineinstrbuilder/#a6c1f959947905135c7dd215b64957654">llvm::MachineInstrBuilder::addImm</a>, <a href="/web-llvm/docs/api/classes/llvm/machineinstrbuilder/#a927857fc69e4b4f0cde307f86f180df5">llvm::MachineInstrBuilder::addReg</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/silowercontrolflow-cpp/#a4868c5d81c5ccc98c47aeab6244346a0">assert</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a17e04afcf0c5efeb0eb6a9a45287b5e4">llvm::BuildMI</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a7c46c742c31be54870e2038048e6b391">llvm::dbgs</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/arm/armslshardening-cpp/#ad467c4ab9119043f9b7750ab986be61a">DL</a>, <a href="/web-llvm/docs/api/classes/llvm/philoweringhelper/#a4b9e1c74c0536fbade814091fd3c8ee3">llvm::PhiLoweringHelper::isLaneMaskReg</a>, <a href="#a7705c8d988a3ccfc9c35783759cd7334">isVreg1</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/siloweri1copies-cpp/#a9f76c7673322a26dbad00fca14f23e3d">isVRegCompatibleReg</a>, <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/support/debug-h/#a196897517069dda1bdb549e24468f7d7">LLVM_DEBUG</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/arm/armslshardening-cpp/#a5958512eae2979bd2eb383977996a600">MBB</a>, <a href="/web-llvm/docs/api/classes/llvm/philoweringhelper/#a80b1d6c9ae89f83c6918aaee904070c3">llvm::PhiLoweringHelper::MF</a>, <a href="/web-llvm/docs/api/files/lib/lib/codegen/lib/codegen/globalisel/irtranslator-cpp/#abe44dfdea65b4f7e11e0a608ab708b76">MI</a>, <a href="/web-llvm/docs/api/classes/llvm/philoweringhelper/#a587ec89e73d2290668b58a5e7f771f35">llvm::PhiLoweringHelper::MRI</a>, <a href="/web-llvm/docs/api/classes/llvm/smallvectortemplatebase/#af42bfbc067df27c19ee2fc859df58799">llvm::SmallVectorTemplateBase&lt; T, bool &gt;::push_back</a> and <a href="/web-llvm/docs/api/classes/llvm/philoweringhelper/#ab37b9650dd3ff2294ac2556672c52eb3">llvm::PhiLoweringHelper::TII</a>.</p>

</div>
</div>

### lowerCopiesToI1() {#adaf0e50d1e23ce068ed74fe079552d51}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool Vreg1LoweringHelper::lowerCopiesToI1 ()</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 63 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/siloweri1copies-cpp">SILowerI1Copies.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/classes/llvm/ssaupdater/#af0d1a82b4e629e834c2ed53e5cbe22ef">llvm::SSAUpdater::AddAvailableValue</a>, <a href="/web-llvm/docs/api/classes/llvm/machineinstrbuilder/#a6c1f959947905135c7dd215b64957654">llvm::MachineInstrBuilder::addImm</a>, <a href="/web-llvm/docs/api/classes/anonymous-siloweri1copies-cpp-/loopfinder/#a2386e395c05803dc5a92d85297b9d6a1">anonymous{SILowerI1Copies.cpp}::LoopFinder::addLoopEntries</a>, <a href="/web-llvm/docs/api/classes/llvm/machineinstrbuilder/#a927857fc69e4b4f0cde307f86f180df5">llvm::MachineInstrBuilder::addReg</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/silowercontrolflow-cpp/#a4868c5d81c5ccc98c47aeab6244346a0">assert</a>, <a href="#aa667006252ada935940ba209eef256e3">buildMergeLaneMasks</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a17e04afcf0c5efeb0eb6a9a45287b5e4">llvm::BuildMI</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a94b43ba7ddb7fcd4dab5bf28c829a423">llvm::createLaneMaskReg</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a7c46c742c31be54870e2038048e6b391">llvm::dbgs</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/arm/armslshardening-cpp/#ad467c4ab9119043f9b7750ab986be61a">DL</a>, <a href="/web-llvm/docs/api/classes/llvm/philoweringhelper/#a5c654bc63075ea6446978668af9b23c7">llvm::PhiLoweringHelper::DT</a>, <a href="/web-llvm/docs/api/classes/anonymous-siloweri1copies-cpp-/loopfinder/#ac7e76dcb7cf9c36d512e2c8b2056f55e">anonymous{SILowerI1Copies.cpp}::LoopFinder::findLoop</a>, <a href="/web-llvm/docs/api/classes/llvm/ssaupdater/#a5b0e45dbba53e985f1b9c532fb5f200b">llvm::SSAUpdater::GetValueInMiddleOfBlock</a>, <a href="/web-llvm/docs/api/classes/llvm/ssaupdater/#a4fe3279aae4f726813a672d4a9b26cb1">llvm::SSAUpdater::Initialize</a>, <a href="/web-llvm/docs/api/classes/anonymous-siloweri1copies-cpp-/loopfinder/#a0cf63cd3280918e038371b0ba86571cc">anonymous{SILowerI1Copies.cpp}::LoopFinder::initialize</a>, <a href="/web-llvm/docs/api/classes/llvm/philoweringhelper/#add0c3d95c2434973b3b5795aecadf243">llvm::PhiLoweringHelper::initializeLaneMaskRegisterAttributes</a>, <a href="/web-llvm/docs/api/classes/llvm/philoweringhelper/#a4b9e1c74c0536fbade814091fd3c8ee3">llvm::PhiLoweringHelper::isLaneMaskReg</a>, <a href="/web-llvm/docs/api/classes/llvm/register/#ab203bbcbc320180b1da9e9a92ee0c784">llvm::Register::isVirtual</a>, <a href="#a7705c8d988a3ccfc9c35783759cd7334">isVreg1</a>, <a href="/web-llvm/docs/api/classes/llvm/philoweringhelper/#acefa582f93360081f06fe71aef54da34">llvm::PhiLoweringHelper::LaneMaskRegAttrs</a>, <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/support/debug-h/#a196897517069dda1bdb549e24468f7d7">LLVM_DEBUG</a>, <a href="#a2961ec025986c8fb2c4e9981302383a6">markAsLaneMask</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/arm/armslshardening-cpp/#a5958512eae2979bd2eb383977996a600">MBB</a>, <a href="/web-llvm/docs/api/classes/llvm/philoweringhelper/#a80b1d6c9ae89f83c6918aaee904070c3">llvm::PhiLoweringHelper::MF</a>, <a href="/web-llvm/docs/api/files/lib/lib/codegen/lib/codegen/globalisel/irtranslator-cpp/#abe44dfdea65b4f7e11e0a608ab708b76">MI</a>, <a href="/web-llvm/docs/api/classes/llvm/philoweringhelper/#a587ec89e73d2290668b58a5e7f771f35">llvm::PhiLoweringHelper::MRI</a>, <a href="/web-llvm/docs/api/classes/llvm/philoweringhelper/#aa60a09fb7712789a3e5e58806b4aa10d">llvm::PhiLoweringHelper::PDT</a>, <a href="/web-llvm/docs/api/classes/llvm/smallvectortemplatebase/#af42bfbc067df27c19ee2fc859df58799">llvm::SmallVectorTemplateBase&lt; T, bool &gt;::push_back</a> and <a href="/web-llvm/docs/api/classes/llvm/philoweringhelper/#ab37b9650dd3ff2294ac2556672c52eb3">llvm::PhiLoweringHelper::TII</a>.</p>

</div>
</div>

### markAsLaneMask() {#a2961ec025986c8fb2c4e9981302383a6}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void Vreg1LoweringHelper::markAsLaneMask (<a href="/web-llvm/docs/api/classes/llvm/register">Register</a> DstReg)</td>
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



<p>Definition at line 48 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/siloweri1copies-cpp">SILowerI1Copies.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/classes/llvm/philoweringhelper/#a587ec89e73d2290668b58a5e7f771f35">llvm::PhiLoweringHelper::MRI</a> and <a href="/web-llvm/docs/api/classes/llvm/philoweringhelper/#aaada4db8807fee28bb4785a3ab1f9df1">llvm::PhiLoweringHelper::ST</a>.</p>


<p>Referenced by <a href="#adaf0e50d1e23ce068ed74fe079552d51">lowerCopiesToI1</a>.</p>

</div>
</div>

### replaceDstReg() {#a2034914dc6524f4ca5b13bbd22635446}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void Vreg1LoweringHelper::replaceDstReg (<a href="/web-llvm/docs/api/classes/llvm/register">Register</a> NewReg, <a href="/web-llvm/docs/api/classes/llvm/register">Register</a> OldReg, <a href="/web-llvm/docs/api/classes/llvm/machinebasicblock">MachineBasicBlock</a> * MBB)</td>
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



<p>Definition at line 54 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/siloweri1copies-cpp">SILowerI1Copies.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/arm/armslshardening-cpp/#a5958512eae2979bd2eb383977996a600">MBB</a> and <a href="/web-llvm/docs/api/classes/llvm/philoweringhelper/#a587ec89e73d2290668b58a5e7f771f35">llvm::PhiLoweringHelper::MRI</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Private Member Attributes

### ConstrainRegs {#ae361a8e710393612bfb5dd0721915984}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">DenseSet&lt;Register&gt; anonymous{SILowerI1Copies.cpp}::Vreg1LoweringHelper::ConstrainRegs</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 45 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/siloweri1copies-cpp">SILowerI1Copies.cpp</a>.</p>

</div>
</div>

</div>

<hr/>

The documentation for this class was generated from the following file:

<ul>
<li><a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/siloweri1copies-cpp">SILowerI1Copies.cpp</a></li>
</ul>

<hr/>

<p class="doxyGeneratedBy">Generated via <a href="https://github.com/xpack/doxygen2docusaurus">doxygen2docusaurus</a> by <a href="https://www.doxygen.nl">Doxygen</a> 1.15.0.</p>

</div>
