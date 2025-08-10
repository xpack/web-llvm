---

# DO NOT EDIT!
# Automatically generated via doxygen2docusaurus by Doxygen.

slug: /api/classes/anonymous-armmctargetdesc-cpp-/armmcinstranalysis
custom_edit_url: null
toc_max_heading_level: 4
keywords:
  - doxygen
  - reference
  - class

---

<div class="doxyPage">

# `ARMMCInstrAnalysis` Class



## Declaration

<div class="doxyDeclaration">
class anonymous{ARMMCTargetDesc.cpp}::ARMMCInstrAnalysis { ... }
</div>

## Base class

<table class="doxyMembersIndex">

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">class</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/mcinstranalysis">MCInstrAnalysis</a></td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ab78c0f885d392578accc4e58f094905a">ARMMCInstrAnalysis</a> (const MCInstrInfo *Info)</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ac389d403d77a77be4f5125065acbc9ee">isUnconditionalBranch</a> (const MCInst &amp;Inst) const override</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#af9b1c01689e16efd902204d7835455d8">isConditionalBranch</a> (const MCInst &amp;Inst) const override</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#abd75f1cc002f438f42d32f12e0326122">evaluateBranch</a> (const MCInst &amp;Inst, uint64_t Addr, uint64_t Size, uint64_t &amp;Target) const override</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Given a branch instruction try to get the address the branch targets. <a href="#abd75f1cc002f438f42d32f12e0326122">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">std::optional&lt; uint64_t &gt;</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a49422093293e285d52290f1491a42f33">evaluateMemoryOperandAddress</a> (const MCInst &amp;Inst, const MCSubtargetInfo *STI, uint64_t Addr, uint64_t Size) const override</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Given an instruction tries to get the address of a memory operand. <a href="#a49422093293e285d52290f1491a42f33">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

</table>


<p>Definition at line 397 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/arm/lib/target/arm/mctargetdesc/armmctargetdesc-cpp">ARMMCTargetDesc.cpp</a>.</p>


<div class="doxySectionDef">

## Public Constructors

### ARMMCInstrAnalysis() {#ab78c0f885d392578accc4e58f094905a}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">anonymous{ARMMCTargetDesc.cpp}::ARMMCInstrAnalysis::ARMMCInstrAnalysis (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/mcinstrinfo">MCInstrInfo</a> * Info)</td>
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



<p>Definition at line 399 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/arm/lib/target/arm/mctargetdesc/armmctargetdesc-cpp">ARMMCTargetDesc.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/classes/llvm/mcinstranalysis/#ad26d74f7a49154af0b73be4e105d361b">llvm::MCInstrAnalysis::Info</a> and <a href="/web-llvm/docs/api/classes/llvm/mcinstranalysis/#ad3b05756e9ba8f98ac91be359f4ea275">llvm::MCInstrAnalysis::MCInstrAnalysis</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/arm/lib/target/arm/mctargetdesc/armmctargetdesc-cpp/#a3c086155e4aec51f304192f98dffc355">createARMMCInstrAnalysis</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Public Member Functions

### evaluateBranch() {#abd75f1cc002f438f42d32f12e0326122}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool anonymous{ARMMCTargetDesc.cpp}::ARMMCInstrAnalysis::evaluateBranch (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/mcinst">MCInst</a> &amp; Inst, uint64_t Addr, uint64_t Size, uint64_t &amp; Target)</td>
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

<p>Given a branch instruction try to get the address the branch targets.</p>


<p>Return true on success, and the address in Target.</p>


<p>Definition at line 415 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/arm/lib/target/arm/mctargetdesc/armmctargetdesc-cpp">ARMMCTargetDesc.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/namespaces/llvm/arm-mc/#adea9a50e399e313a7a8a5b2007639b49">llvm::ARM_MC::evaluateBranchTarget</a>, <a href="/web-llvm/docs/api/classes/llvm/mcoperand/#a4509c43893edc940979f690c468664c1">llvm::MCOperand::getImm</a>, <a href="/web-llvm/docs/api/classes/llvm/mcinst/#a5c26b1db954c27889986dba3b310a8e4">llvm::MCInst::getOpcode</a>, <a href="/web-llvm/docs/api/classes/llvm/mcinst/#aef5de3ac30fe221c5b4e702574ab46a9">llvm::MCInst::getOperand</a>, <a href="/web-llvm/docs/api/classes/llvm/mcinstranalysis/#ad26d74f7a49154af0b73be4e105d361b">llvm::MCInstrAnalysis::Info</a>, <a href="/web-llvm/docs/api/classes/llvm/mcoperand/#a5f639fdcd3fc673fcbdb47f2e88b2b41">llvm::MCOperand::isImm</a>, <a href="/web-llvm/docs/api/namespaces/llvm/mcoi/#ad9dfed338ec3d47f30c593ee49cbf96da4ab8ff4de9da34b9b60f04a21860aec1">llvm::MCOI::OPERAND_PCREL</a>, <a href="/web-llvm/docs/api/files/lib/lib/analysis/inlineorder-cpp/#a7ee6f0cb51c3b9056199e9a0001fe8c3a6f6cb72d544962fa333e2e34ce64f719">Size</a> and <a href="/web-llvm/docs/api/classes/llvm/mcinstranalysis/#aaec4eb5c2964764409c3ecc82bb90f57">llvm::MCInstrAnalysis::Target</a>.</p>

</div>
</div>

### evaluateMemoryOperandAddress() {#a49422093293e285d52290f1491a42f33}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">std::optional&lt; uint64_t &gt; ARMMCInstrAnalysis::evaluateMemoryOperandAddress (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/mcinst">MCInst</a> &amp; Inst, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/mcsubtargetinfo">MCSubtargetInfo</a> * STI, uint64_t Addr, uint64_t Size)</td>
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

<p>Given an instruction tries to get the address of a memory operand.</p>


<p>Returns the address on success.</p>


<p>Definition at line 432 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/arm/lib/target/arm/mctargetdesc/armmctargetdesc-cpp">ARMMCTargetDesc.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/namespaces/llvm/armii/#ace99f086a3cd38c7477a8f038dae7ff4a3e943d975799a4c55333c54eac1a7991">llvm::ARMII::AddrMode3</a>, <a href="/web-llvm/docs/api/namespaces/llvm/armii/#ace99f086a3cd38c7477a8f038dae7ff4a0209ae669364c237e24dbc0c4df6036e">llvm::ARMII::AddrMode5</a>, <a href="/web-llvm/docs/api/namespaces/llvm/armii/#ace99f086a3cd38c7477a8f038dae7ff4a3747b57333522e1d11664379a2d9917a">llvm::ARMII::AddrMode5FP16</a>, <a href="/web-llvm/docs/api/namespaces/llvm/armii/#ace99f086a3cd38c7477a8f038dae7ff4a44874e651b75b372574cc861fee08896">llvm::ARMII::AddrMode_i12</a>, <a href="/web-llvm/docs/api/namespaces/llvm/armii/#a3c06fab2f468e615484900041c216ef4aeda154c828d692cd52ca6cce8765f9ae">llvm::ARMII::AddrModeMask</a>, <a href="/web-llvm/docs/api/namespaces/llvm/armii/#ace99f086a3cd38c7477a8f038dae7ff4a147ee44cd2b5425325839f5f0fa897ad">llvm::ARMII::AddrModeT1_s</a>, <a href="/web-llvm/docs/api/namespaces/llvm/armii/#ace99f086a3cd38c7477a8f038dae7ff4af3a6218c9c9bd03381633c799e5226d9">llvm::ARMII::AddrModeT2_i8s4</a>, <a href="/web-llvm/docs/api/namespaces/llvm/armii/#ace99f086a3cd38c7477a8f038dae7ff4af9852c0cf1e5c1418ab8ac2b480e1190">llvm::ARMII::AddrModeT2_pc</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/arm/lib/target/arm/mctargetdesc/armmctargetdesc-cpp/#a3a10338918837225d81648bf78971876">evaluateMemOpAddrForAddrMode3</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/arm/lib/target/arm/mctargetdesc/armmctargetdesc-cpp/#a90ccaddf3b14b7a19c3174cd9e5651d9">evaluateMemOpAddrForAddrMode5</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/arm/lib/target/arm/mctargetdesc/armmctargetdesc-cpp/#a4ffbbb48662d27de4440a7b157ee9c95">evaluateMemOpAddrForAddrMode5FP16</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/arm/lib/target/arm/mctargetdesc/armmctargetdesc-cpp/#a03dbfe41dfe176bfe1e76230128d4e4a">evaluateMemOpAddrForAddrMode_i12</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/arm/lib/target/arm/mctargetdesc/armmctargetdesc-cpp/#a2f2a83555cee9cf58b969c9b2b3d79dc">evaluateMemOpAddrForAddrModeT1_s</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/arm/lib/target/arm/mctargetdesc/armmctargetdesc-cpp/#ad34ddc3f73b297a15a8fdfdd78534fed">evaluateMemOpAddrForAddrModeT2_i8s4</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/arm/lib/target/arm/mctargetdesc/armmctargetdesc-cpp/#a74107612c997d67a0fadb5fb642fc61d">evaluateMemOpAddrForAddrModeT2_pc</a>, <a href="/web-llvm/docs/api/namespaces/llvm/armii/#a3c06fab2f468e615484900041c216ef4a2adb030227483dbcc19765434c480053">llvm::ARMII::FormMask</a>, <a href="/web-llvm/docs/api/classes/llvm/mcinst/#a5c26b1db954c27889986dba3b310a8e4">llvm::MCInst::getOpcode</a>, <a href="/web-llvm/docs/api/classes/llvm/mcsubtargetinfo/#a0ad14e9a81239b54fd64089b3290bfde">llvm::MCSubtargetInfo::hasFeature</a>, <a href="/web-llvm/docs/api/namespaces/llvm/armii/#a3c06fab2f468e615484900041c216ef4a090893e44b7d8da1ed8e65cc6b586ae8">llvm::ARMII::IndexModeMask</a>, <a href="/web-llvm/docs/api/namespaces/llvm/armii/#ac3c83a9ce4f6ef1a90d63ebe5722b2b9a02d5ab304efd1b563cbe831bd5f7ba40">llvm::ARMII::IndexModeNone</a>, <a href="/web-llvm/docs/api/namespaces/llvm/armii/#a3c06fab2f468e615484900041c216ef4ac928721626de611c1e5c7acfd4e05f79">llvm::ARMII::IndexModeShift</a>, <a href="/web-llvm/docs/api/classes/llvm/mcinstranalysis/#ad26d74f7a49154af0b73be4e105d361b">llvm::MCInstrAnalysis::Info</a>, <a href="/web-llvm/docs/api/namespaces/llvm/mcoi/#ad9dfed338ec3d47f30c593ee49cbf96da777022119f804325c388f44ccd8524e5">llvm::MCOI::OPERAND_MEMORY</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/spirv/spirvmoduleanalysis-cpp/#acaab1e2660e7055669741c9f485e26c5">OpIndex</a>, <a href="/web-llvm/docs/api/files/lib/lib/analysis/inlineorder-cpp/#a7ee6f0cb51c3b9056199e9a0001fe8c3a6f6cb72d544962fa333e2e34ce64f719">Size</a>, <a href="/web-llvm/docs/api/namespaces/llvm/armii/#a3c06fab2f468e615484900041c216ef4a9fbfad472c878dd4554adbfae06693a9">llvm::ARMII::ThumbFrm</a> and <a href="/web-llvm/docs/api/namespaces/llvm/armii/#a3c06fab2f468e615484900041c216ef4a083e564b421567ee4954f484ba5ece1a">llvm::ARMII::VFPLdStFrm</a>.</p>

</div>
</div>

### isConditionalBranch() {#af9b1c01689e16efd902204d7835455d8}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool anonymous{ARMMCTargetDesc.cpp}::ARMMCInstrAnalysis::isConditionalBranch (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/mcinst">MCInst</a> &amp; Inst)</td>
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



<p>Definition at line 408 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/arm/lib/target/arm/mctargetdesc/armmctargetdesc-cpp">ARMMCTargetDesc.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/namespaces/llvm/armcc/#ac8391dd6b8083baa870dee5142ff22b6a8b2ef77967dee1220cc6ee5aee595e11">llvm::ARMCC::AL</a>, <a href="/web-llvm/docs/api/classes/llvm/mcoperand/#a4509c43893edc940979f690c468664c1">llvm::MCOperand::getImm</a>, <a href="/web-llvm/docs/api/classes/llvm/mcinst/#a5c26b1db954c27889986dba3b310a8e4">llvm::MCInst::getOpcode</a>, <a href="/web-llvm/docs/api/classes/llvm/mcinst/#aef5de3ac30fe221c5b4e702574ab46a9">llvm::MCInst::getOperand</a> and <a href="/web-llvm/docs/api/classes/llvm/mcinstranalysis/#aabfb496421d3e86668396b0b97d5a431">llvm::MCInstrAnalysis::isConditionalBranch</a>.</p>

</div>
</div>

### isUnconditionalBranch() {#ac389d403d77a77be4f5125065acbc9ee}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool anonymous{ARMMCTargetDesc.cpp}::ARMMCInstrAnalysis::isUnconditionalBranch (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/mcinst">MCInst</a> &amp; Inst)</td>
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



<p>Definition at line 401 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/arm/lib/target/arm/mctargetdesc/armmctargetdesc-cpp">ARMMCTargetDesc.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/namespaces/llvm/armcc/#ac8391dd6b8083baa870dee5142ff22b6a8b2ef77967dee1220cc6ee5aee595e11">llvm::ARMCC::AL</a>, <a href="/web-llvm/docs/api/classes/llvm/mcoperand/#a4509c43893edc940979f690c468664c1">llvm::MCOperand::getImm</a>, <a href="/web-llvm/docs/api/classes/llvm/mcinst/#a5c26b1db954c27889986dba3b310a8e4">llvm::MCInst::getOpcode</a>, <a href="/web-llvm/docs/api/classes/llvm/mcinst/#aef5de3ac30fe221c5b4e702574ab46a9">llvm::MCInst::getOperand</a> and <a href="/web-llvm/docs/api/classes/llvm/mcinstranalysis/#a4e5be94e4462c129c3b5e4ba2af1c2bc">llvm::MCInstrAnalysis::isUnconditionalBranch</a>.</p>

</div>
</div>

</div>

<hr/>

The documentation for this class was generated from the following file:

<ul>
<li><a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/arm/lib/target/arm/mctargetdesc/armmctargetdesc-cpp">ARMMCTargetDesc.cpp</a></li>
</ul>

<hr/>

<p class="doxyGeneratedBy">Generated via <a href="https://xpack.github.io/doxygen2docusaurus">doxygen2docusaurus</a> 2.0.0 by <a href="https://www.doxygen.nl">Doxygen</a> 1.15.0.</p>

</div>
