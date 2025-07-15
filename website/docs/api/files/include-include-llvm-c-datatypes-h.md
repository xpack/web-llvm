---

# DO NOT EDIT!
# Automatically generated via doxygen2docusaurus by Doxygen.

slug: /api/files/include/include/llvm-c/datatypes-h
custom_edit_url: null
toc_max_heading_level: 4
keywords:
  - doxygen
  - reference
  - file

---

<div class="doxyPage">

# The `DataTypes.h` File Reference



## Included Headers

<div class="doxyIncludesList">#include &lt;inttypes.h&gt;
#include &lt;stdint.h&gt;
#include &lt;sys/types.h&gt;
</div>

## Macro Definitions Index

<table class="doxyMembersIndex">

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">#define</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ad0d744f05898e32d01f73f8af3cd2071">INT64_MAX</a>&nbsp;&nbsp;&nbsp;9223372036854775807LL</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">#define</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ab21f12f372f67b8ff0aa3432336ede67">INT64_MIN</a>&nbsp;&nbsp;&nbsp;((-<a href="#ad0d744f05898e32d01f73f8af3cd2071">INT64_MAX</a>)-1)</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">#define</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a30654b4b67d97c42ca3f9b6052dda916">UINT64_MAX</a>&nbsp;&nbsp;&nbsp;0xffffffffffffffffULL</td>
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

## Macro Definitions

### INT64\_MAX {#ad0d744f05898e32d01f73f8af3cd2071}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">#define INT64_MAX&nbsp;&nbsp;&nbsp;9223372036854775807LL</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 71 of file <a href="/web-llvm/docs/api/files/include/include/llvm-c/datatypes-h">DataTypes.h</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/classes/anonymous-mcasmstreamer-cpp-/mcasmstreamer/#a79809d23367b5aafd98b71ae67a0d2d4">anonymous{MCAsmStreamer.cpp}::MCAsmStreamer::emitDwarfAdvanceLineAddr</a>, <a href="/web-llvm/docs/api/classes/anonymous-mcasmstreamer-cpp-/mcasmstreamer/#aa72d5840fe6b92c329861c90b8a7c58c">anonymous{MCAsmStreamer.cpp}::MCAsmStreamer::emitDwarfLineEndEntry</a>, <a href="/web-llvm/docs/api/classes/llvm/mcobjectstreamer/#a916d35fa28fa01868c717ca125a037af">llvm::MCObjectStreamer::emitDwarfLineEndEntry</a>, <a href="/web-llvm/docs/api/classes/llvm/mcdwarflinetable/#adf60d16739e1ceabb1cee9e9dede7ba5">llvm::MCDwarfLineTable::emitOne</a>, <a href="/web-llvm/docs/api/classes/llvm/gsym/linetable/#a41c4a2acdbcfaf2a18a61b60d42a9dc4">llvm::gsym::LineTable::encode</a>, <a href="/web-llvm/docs/api/classes/llvm/mcdwarflineaddr/#ae0f19d1d97309d2c250054dae4569622">llvm::MCDwarfLineAddr::encode</a>, <a href="/web-llvm/docs/api/classes/anonymous-hexagonasmbackend-cpp-/hexagonasmbackend/#aabc01e9899fccd76ffd3a0c7da023fb5">anonymous{HexagonAsmBackend.cpp}::HexagonAsmBackend::fixupNeedsRelaxationAdvanced</a>, <a href="/web-llvm/docs/api/classes/llvm/unopinit/#af0e0cf8fa25dde613e92575630bb9475">llvm::UnOpInit::Fold</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64isellowering-cpp/#af46d1ba5c3f2f00b06659c2ba7dc5c7c">getAArch64Cmp</a>, <a href="/web-llvm/docs/api/classes/llvm/hexagonpacketizerlist/#a5734374d530ee7ee7a3fdda172fc22cd">llvm::HexagonPacketizerList::initPacketizerState</a>, <a href="/web-llvm/docs/api/classes/llvm/hexagonpacketizerlist/#a49f30830f4e853ee33ad7b021d0f5403">llvm::HexagonPacketizerList::isLegalToPruneDependencies</a>, <a href="/web-llvm/docs/api/classes/llvm/scalednumberbase/#a93c62a567080c027645eba55c74d9d03">llvm::ScaledNumberBase::joinSigned</a>, <a href="/web-llvm/docs/api/classes/llvm/riscvinstrinfo/#aeaeffb171ae383d18f217fbd278c8717">llvm::RISCVInstrInfo::optimizeCondBranch</a>, <a href="/web-llvm/docs/api/classes/llvm/mcpseudoprobedecoder/#a4f3df2371946b59c86d154b8ffce1925">llvm::MCPseudoProbeDecoder::printProbesForAllAddresses</a>, <a href="/web-llvm/docs/api/classes/llvm/loongarchasmbackend/#a09963de4b3b90f89cf9f9b6f154af6bd">llvm::LoongArchAsmBackend::relaxDwarfLineAddr</a>, <a href="/web-llvm/docs/api/classes/llvm/riscvasmbackend/#a056a7266fa88806c3f88ab217fac6e4e">llvm::RISCVAsmBackend::relaxDwarfLineAddr</a>, <a href="/web-llvm/docs/api/classes/anonymous-x86dynallocaexpander-cpp-/x86dynallocaexpander/#a8216d146c993c13133c29a28efdded4c">anonymous{X86DynAllocaExpander.cpp}::X86DynAllocaExpander::runOnMachineFunction</a>, <a href="/web-llvm/docs/api/structs/anonymous-x86tileconfig-cpp-/x86tileconfig/#a963813efe9cac5e7b68def8df1713456">anonymous{X86TileConfig.cpp}::X86TileConfig::runOnMachineFunction</a>, <a href="/web-llvm/docs/api/namespaces/anonymous-aarch64postlegalizerlowering-cpp-/#a681a012ac18b27513b6715881d002520">anonymous{AArch64PostLegalizerLowering.cpp}::tryAdjustICmpImmAndPred</a> and <a href="/web-llvm/docs/api/classes/anonymous-aarch64asmparser-cpp-/aarch64asmparser/#a246c8dfd4ca957b7da4d52cb7805650c">anonymous{AArch64AsmParser.cpp}::AArch64AsmParser::tryParseAdjImm0_63</a>.</p>

</div>
</div>

### INT64\_MIN {#ab21f12f372f67b8ff0aa3432336ede67}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">#define INT64_MIN&nbsp;&nbsp;&nbsp;((-<a href="#ad0d744f05898e32d01f73f8af3cd2071">INT64_MAX</a>)-1)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 74 of file <a href="/web-llvm/docs/api/files/include/include/llvm-c/datatypes-h">DataTypes.h</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/x86/x86isellowering-cpp/#adc36484c228b0ce9652f549d04ae4e6e">combineMul</a>, <a href="/web-llvm/docs/api/classes/llvm/gsym/linetable/#a41c4a2acdbcfaf2a18a61b60d42a9dc4">llvm::gsym::LineTable::encode</a>, <a href="/web-llvm/docs/api/classes/llvm/binopinit/#adbe242b084763cfdb35c7850bd4098b5">llvm::BinOpInit::Fold</a>, <a href="/web-llvm/docs/api/classes/llvm/scalednumberbase/#a93c62a567080c027645eba55c74d9d03">llvm::ScaledNumberBase::joinSigned</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/riscv/riscvisellowering-cpp/#a0c73954e103eaf84aceb7fc799f4c44a">lowerBuildVectorOfConstants</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/webassembly/webassemblyisellowering-cpp/#a01bea37475bf9a1f853b90975dbf7605">LowerFPToInt</a>, <a href="/web-llvm/docs/api/classes/llvm/codeview/codeviewrecordio/#a65d7ff22f925eb1f4893ea7634b7bf59">llvm::codeview::CodeViewRecordIO::mapEncodedInteger</a>, <a href="/web-llvm/docs/api/classes/llvm/scalednumberbase/#afe42176d3878695a8d7991af3439783f">llvm::ScaledNumberBase::splitSigned</a>, <a href="/web-llvm/docs/api/namespaces/anonymous-aarch64postlegalizerlowering-cpp-/#a681a012ac18b27513b6715881d002520">anonymous{AArch64PostLegalizerLowering.cpp}::tryAdjustICmpImmAndPred</a> and <a href="/web-llvm/docs/api/classes/anonymous-aarch64asmparser-cpp-/aarch64asmparser/#a246c8dfd4ca957b7da4d52cb7805650c">anonymous{AArch64AsmParser.cpp}::AArch64AsmParser::tryParseAdjImm0_63</a>.</p>

</div>
</div>

### UINT64\_MAX {#a30654b4b67d97c42ca3f9b6052dda916}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">#define UINT64_MAX&nbsp;&nbsp;&nbsp;0xffffffffffffffffULL</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 77 of file <a href="/web-llvm/docs/api/files/include/include/llvm-c/datatypes-h">DataTypes.h</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/classes/llvm/logicalview/lvlocationsymbol/#af75748891e5832a72f023b1429c0fc1f">llvm::logicalview::LVLocationSymbol::addObject</a>, <a href="/web-llvm/docs/api/namespaces/anonymous-systemziseldagtodag-cpp-/#a68b124522ab0fdc7148417fb06f0e93e">anonymous{SystemZISelDAGToDAG.cpp}::allOnes</a>, <a href="/web-llvm/docs/api/classes/llvm/runtimedyldimpl/#a37c72a2afbbe1c6eee27d8fa2a2e2834">llvm::RuntimeDyldImpl::applyExternalSymbolRelocations</a>, <a href="/web-llvm/docs/api/files/lib/lib/analysis/blockfrequencyinfoimpl-cpp/#a63f8c3e98c54556d954cc51ca32293ca">combineWeight</a>, <a href="/web-llvm/docs/api/files/lib/lib/analysis/typebasedaliasanalysis-cpp/#aa776b44397de40feb0455262dcd73f70">createAccessTag</a>, <a href="/web-llvm/docs/api/classes/llvm/logicalview/lvbinaryreader/#ac378e86f9979cde149105568f10ee404">llvm::logicalview::LVBinaryReader::createInstructions</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a405b6cecd013148b4b443dd37854b4c4">llvm::decodeSLEB128</a>, <a href="/web-llvm/docs/api/classes/llvm/objcopy/elf/binarywriter/#a5b9da0f3636f00c8eb9dca28bf21e606">llvm::objcopy::elf::BinaryWriter::finalize</a>, <a href="/web-llvm/docs/api/classes/llvm/switchcg/switchlowering/#a41add37692675e7e74358acc1483f168">llvm::SwitchCG::SwitchLowering::findJumpTables</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64isellowering-cpp/#af46d1ba5c3f2f00b06659c2ba7dc5c7c">getAArch64Cmp</a>, <a href="/web-llvm/docs/api/files/lib/lib/ir/debuginfo-cpp/#afb6a2b1b5242599e12b7fe897140eda3">getAssignmentInfoImpl</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a36b03d4697c30b32e8762cb0dfd66761">llvm::getConstantDataArrayInfo</a>, <a href="/web-llvm/docs/api/classes/llvm/llvmcontext/#aded771687bdc915d3b992cbbee8c22c7">llvm::LLVMContext::getDiagnosticsHotnessThreshold</a>, <a href="/web-llvm/docs/api/namespaces/llvm/switchcg/#ab401f0019413b136ec7484fcb6236f68">llvm::SwitchCG::getJumpTableRange</a>, <a href="/web-llvm/docs/api/classes/llvm/apint/#ab01d8694a759a934e01f1c558c3ce862">llvm::APInt::getLimitedValue</a>, <a href="/web-llvm/docs/api/classes/llvm/constantsdnode/#a15435ec20548d5deea628d820f9f5208">llvm::ConstantSDNode::getLimitedValue</a>, <a href="/web-llvm/docs/api/classes/llvm/profilesummaryinfo/#ae48ebfb8f85e9b59325d20cdc9299f0e">llvm::ProfileSummaryInfo::getOrCompHotCountThreshold</a>, <a href="/web-llvm/docs/api/classes/anonymous-typebasedaliasanalysis-cpp-/tbaastructtagnodeimpl/#a17860fdaf03e300a82ca6974cb0769cc">anonymous{TypeBasedAliasAnalysis.cpp}::TBAAStructTagNodeImpl&lt; const MDNode &gt;::getSize</a>, <a href="/web-llvm/docs/api/classes/llvm/regbankselect/mappingcost/#a7e2284f2c68e1187be7ed8c89a0d6f88">llvm::RegBankSelect::MappingCost::ImpossibleCost</a>, <a href="/web-llvm/docs/api/structs/llvm/gsym/cuinfo/#ae36dc1e53f9c27b4d8d3d405ae3a0ce1">llvm::gsym::CUInfo::isHighestAddress</a>, <a href="/web-llvm/docs/api/classes/llvm/dwarf-linker/parallel/dependencytracker/#abab9675572d9fe6ef8cf9674b1bab8f7">llvm::dwarf_linker::parallel::DependencyTracker::isLiveSubprogramEntry</a>, <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/utils/simplifycfg-cpp/#a7c6e64e4a4dbba951d47fe2b1d188b2c">isSwitchDense</a>, <a href="/web-llvm/docs/api/structs/llvm/patternmatch/bind-const-intval-ty/#aa85832c890766440579d5e4419fc1917">llvm::PatternMatch::bind_const_intval_ty::match</a>, <a href="/web-llvm/docs/api/classes/llvm/blockfrequency/#a5bd2a8de4fde83093df0cc2415db2312">llvm::BlockFrequency::max</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#af80bd4ec8a9b2f8e7d9d75ab708a55c2">llvm::maxUIntN</a>, <a href="/web-llvm/docs/api/structs/anonymous-llparser-cpp-/mdunsignedfield/#ad05718c4ff90c5149b94b5fcc04f3b7e">anonymous{LLParser.cpp}::MDUnsignedField::MDUnsignedField</a>, <a href="/web-llvm/docs/api/classes/llvm/blockfrequency/#aa55796fd8534453c4c51b41dc3a7a141">llvm::BlockFrequency::operator+=</a>, <a href="/web-llvm/docs/api/classes/anonymous-aggressiveinstcombine-cpp-/strncmpinliner/#ac9d71bcb73b24374e675d3ac3b8f5e8b">anonymous{AggressiveInstCombine.cpp}::StrNCmpInliner::optimizeStrNCmp</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a5542d44947f8d964b5ce3b20ea719b44">llvm::PowerOf2Ceil</a>, <a href="/web-llvm/docs/api/classes/llvm/targetloweringbase/#a316297cc95186ebd04166b07ff210f06">llvm::TargetLoweringBase::rangeFitsInWord</a>, <a href="/web-llvm/docs/api/classes/anonymous-gcrootlowering-cpp-/gcmachinecodeanalysis/#a82b0862f6017d073489a4971d43ecf3a">anonymous{GCRootLowering.cpp}::GCMachineCodeAnalysis::runOnMachineFunction</a>, <a href="/web-llvm/docs/api/files/lib/lib/support/branchprobability-cpp/#aa8c7ae7da7990d5320b67c57f6fc3b59">scale</a>, <a href="/web-llvm/docs/api/classes/llvm/object/elffile/#ab64e03f049c8588f24e0ec69a568aef9">llvm::object::ELFFile&lt; ELFT &gt;::sections</a>, <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/utils/simplifycfg-cpp/#a4abbfca67cb7fc77432aa8cd48af8b0a">switchToLookupTable</a>, <a href="/web-llvm/docs/api/classes/llvm/scalednumberbase/#ac19c88b3b4cddc454681f6650e130733">llvm::ScaledNumberBase::toString</a>, <a href="/web-llvm/docs/api/namespaces/anonymous-aarch64postlegalizerlowering-cpp-/#a681a012ac18b27513b6715881d002520">anonymous{AArch64PostLegalizerLowering.cpp}::tryAdjustICmpImmAndPred</a>, <a href="/web-llvm/docs/api/classes/llvm/dwarfunit/#ac360b4709027f4534efa4a4671140ccb">llvm::DWARFUnit::updateVariableDieMap</a>, <a href="/web-llvm/docs/api/classes/anonymous-elfemitter-cpp-/contiguousblobaccumulator/#aee3c2fffc5bc19465ef3941c6c034ab0">anonymous{ELFEmitter.cpp}::ContiguousBlobAccumulator::writeAsBinary</a> and <a href="/web-llvm/docs/api/files/lib/lib/objectyaml/dwarfemitter-cpp/#a27a0ea7c31356a5938a3fe32e8eb3103">writeDWARFLists</a>.</p>

</div>
</div>

</div>

<hr/>

<p class="doxyGeneratedBy">Generated via <a href="https://github.com/xpack/doxygen2docusaurus">doxygen2docusaurus</a> by <a href="https://www.doxygen.nl">Doxygen</a> 1.14.0.</p>

</div>
