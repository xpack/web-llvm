---

# DO NOT EDIT!
# Automatically generated via doxygen2docusaurus by Doxygen.

slug: /api/files/lib/lib/target/lib/target/spirv/spirvlegalizerinfo-cpp
custom_edit_url: null
toc_max_heading_level: 4
keywords:
  - doxygen
  - reference
  - file

---

<div class="doxyPage">

# The `SPIRVLegalizerInfo.cpp` File Reference



## Included Headers

<div class="doxyIncludesList">#include "<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/spirv/spirvlegalizerinfo-h">SPIRVLegalizerInfo.h</a>"
#include "<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/spirv/spirv-h">SPIRV.h</a>"
#include "<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/spirv/spirvglobalregistry-h">SPIRVGlobalRegistry.h</a>"
#include "<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/spirv/spirvsubtarget-h">SPIRVSubtarget.h</a>"
#include "<a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/codegen/include/llvm/codegen/globalisel/legalizerhelper-h">llvm/CodeGen/GlobalISel/LegalizerHelper.h</a>"
#include "<a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/codegen/include/llvm/codegen/globalisel/machineirbuilder-h">llvm/CodeGen/GlobalISel/MachineIRBuilder.h</a>"
#include "<a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/codegen/machineinstr-h">llvm/CodeGen/MachineInstr.h</a>"
#include "<a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/codegen/machineregisterinfo-h">llvm/CodeGen/MachineRegisterInfo.h</a>"
#include "<a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/codegen/targetopcodes-h">llvm/CodeGen/TargetOpcodes.h</a>"
</div>

## Functions Index

<table class="doxyMembersIndex">

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">bool</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a4c9f91a5fc5778c118de4960dae29807">isTypeFoldingSupported</a> (unsigned Opcode)</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/namespaces/llvm/#a652895328c6f5785e94ac8b51b37d63c">LegalityPredicate</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a8168e6624c049ce57176697ad5ab5369">typeOfExtendedScalars</a> (unsigned TypeIdx, bool IsExtendedInts)</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">static <a href="/web-llvm/docs/api/classes/llvm/register">Register</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a3b8f2c8dafaf2b1007b8661546ce5aca">convertPtrToInt</a> (Register Reg, LLT ConvTy, SPIRVType *SpvType, LegalizerHelper &amp;Helper, MachineRegisterInfo &amp;MRI, SPIRVGlobalRegistry *GR)</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">static <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> std::set&lt; unsigned &gt;</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a25890802036e95dcac60b123783e089a">TypeFoldingSupportingOpcs</a> = ...</td>
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

### convertPtrToInt() {#a3b8f2c8dafaf2b1007b8661546ce5aca}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">Register convertPtrToInt (<a href="/web-llvm/docs/api/classes/llvm/register">Register</a> Reg, <a href="/web-llvm/docs/api/classes/llvm/llt">LLT</a> ConvTy, <a href="/web-llvm/docs/api/namespaces/llvm/#a8555f84b0afdf8f97a3dff75ed354ec2">SPIRVType</a> * SpvType, <a href="/web-llvm/docs/api/classes/llvm/legalizerhelper">LegalizerHelper</a> &amp; Helper, <a href="/web-llvm/docs/api/classes/llvm/machineregisterinfo">MachineRegisterInfo</a> &amp; MRI, <a href="/web-llvm/docs/api/classes/llvm/spirvglobalregistry">SPIRVGlobalRegistry</a> * GR)</td>
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



<p>Definition at line 375 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/spirv/spirvlegalizerinfo-cpp">SPIRVLegalizerInfo.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/classes/llvm/machineinstrbuilder/#af584d2eb0342e655d6ec597c0f7958db">llvm::MachineInstrBuilder::addDef</a>, <a href="/web-llvm/docs/api/classes/llvm/machineinstrbuilder/#ad88e27102395957e457fed8e73a085cf">llvm::MachineInstrBuilder::addUse</a>, <a href="/web-llvm/docs/api/classes/llvm/spirvglobalregistry/#a24a8bf11a7b9112db6517027fcd834e8">llvm::SPIRVGlobalRegistry::assignSPIRVTypeToVReg</a>, <a href="/web-llvm/docs/api/classes/llvm/machineirbuilder/#a8bc92b8a902afb7675480ecc729a66d4">llvm::MachineIRBuilder::buildInstr</a>, <a href="/web-llvm/docs/api/classes/llvm/machineirbuilder/#a9ec04f3692b9601036d2d4477c4c3749">llvm::MachineIRBuilder::getMF</a>, <a href="/web-llvm/docs/api/classes/llvm/spirvglobalregistry/#ab6e454de3dfa112cc7e30219ac7298cd">llvm::SPIRVGlobalRegistry::getRegClass</a>, <a href="/web-llvm/docs/api/classes/llvm/legalizerhelper/#ae50d11fc026093629c27142780ff1405">llvm::LegalizerHelper::MIRBuilder</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64advsimdscalarpass-cpp/#aacd2ab195054a3e6a74bfbb9d5d571c8">MRI</a> and <a href="/web-llvm/docs/api/files/lib/lib/codegen/machinesink-cpp/#a359e1ff26f6d466d927a61aae45b05c3">Reg</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/classes/llvm/spirvlegalizerinfo/#a6bd6caf03c29de76c97c536f89349bd7">llvm::SPIRVLegalizerInfo::legalizeCustom</a>.</p>

</div>
</div>

### isTypeFoldingSupported() {#a4c9f91a5fc5778c118de4960dae29807}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool isTypeFoldingSupported (unsigned Opcode)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 60 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/spirv/spirvlegalizerinfo-cpp">SPIRVLegalizerInfo.cpp</a>.</p>


<p>Reference <a href="#a25890802036e95dcac60b123783e089a">TypeFoldingSupportingOpcs</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/classes/llvm/spirvlegalizerinfo/#a6bd6caf03c29de76c97c536f89349bd7">llvm::SPIRVLegalizerInfo::legalizeCustom</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/spirv/spirvinstructionselector-cpp/#a2f96d0dcf6fbd53defac3a80db42f2e4">mayApplyGenericSelection</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/spirv/spirvpostlegalizer-cpp/#af25ad65bd4e5bdd2398d9e1d38cc203e">mayBeInserted</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/spirv/spirvprelegalizer-cpp/#a570ff19cb726a63610a693c8a9a8cfa5">processInstrsWithTypeFolding</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/spirv/spirvpostlegalizer-cpp/#af352e338e2b9a8cd58a97aca55d421e4">processNewInstrs</a> and <a href="/web-llvm/docs/api/classes/anonymous-spirvinstructionselector-cpp-/spirvinstructionselector/#a4a8b881c0637c6f85c3eb6891abcfab4">anonymous{SPIRVInstructionSelector.cpp}::SPIRVInstructionSelector::select</a>.</p>

</div>
</div>

### typeOfExtendedScalars() {#a8168e6624c049ce57176697ad5ab5369}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">LegalityPredicate typeOfExtendedScalars (unsigned TypeIdx, bool IsExtendedInts)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 64 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/spirv/spirvlegalizerinfo-cpp">SPIRVLegalizerInfo.cpp</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/classes/llvm/spirvlegalizerinfo/#a6b747313719abb32e3599ab33501ea17">llvm::SPIRVLegalizerInfo::SPIRVLegalizerInfo</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Variables

### TypeFoldingSupportingOpcs {#a25890802036e95dcac60b123783e089a}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">const std::set&lt;unsigned&gt; TypeFoldingSupportingOpcs</td>
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



<dl class="doxySectionUser">
<dt>Initialiser</dt>
<dd>
<div class="doxyVerbatim">= {
    TargetOpcode::G_ADD,
    TargetOpcode::G_FADD,
    TargetOpcode::G_STRICT_FADD,
    TargetOpcode::G_SUB,
    TargetOpcode::G_FSUB,
    TargetOpcode::G_STRICT_FSUB,
    TargetOpcode::G_MUL,
    TargetOpcode::G_FMUL,
    TargetOpcode::G_STRICT_FMUL,
    TargetOpcode::G_SDIV,
    TargetOpcode::G_UDIV,
    TargetOpcode::G_FDIV,
    TargetOpcode::G_STRICT_FDIV,
    TargetOpcode::G_SREM,
    TargetOpcode::G_UREM,
    TargetOpcode::G_FREM,
    TargetOpcode::G_STRICT_FREM,
    TargetOpcode::G_FNEG,
    TargetOpcode::G_CONSTANT,
    TargetOpcode::G_FCONSTANT,
    TargetOpcode::G_AND,
    TargetOpcode::G_OR,
    TargetOpcode::G_XOR,
    TargetOpcode::G_SHL,
    TargetOpcode::G_ASHR,
    TargetOpcode::G_LSHR,
    TargetOpcode::G_SELECT,
    TargetOpcode::G_EXTRACT_VECTOR_ELT,
}
</div>
</dd>
</dl>

<p>Definition at line 28 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/spirv/spirvlegalizerinfo-cpp">SPIRVLegalizerInfo.cpp</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/spirv/spirvinstructionselector-cpp/#a4c9f91a5fc5778c118de4960dae29807">isTypeFoldingSupported</a> and <a href="/web-llvm/docs/api/classes/llvm/spirvlegalizerinfo/#a6b747313719abb32e3599ab33501ea17">llvm::SPIRVLegalizerInfo::SPIRVLegalizerInfo</a>.</p>

</div>
</div>

</div>

<hr/>

<p class="doxyGeneratedBy">Generated via <a href="https://github.com/xpack/doxygen2docusaurus">doxygen2docusaurus</a> by <a href="https://www.doxygen.nl">Doxygen</a> 1.14.0.</p>

</div>
