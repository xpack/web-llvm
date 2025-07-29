---

# DO NOT EDIT!
# Automatically generated via doxygen2docusaurus by Doxygen.

slug: /api/files/lib/lib/codegen/lib/codegen/globalisel/cseinfo-cpp
custom_edit_url: null
toc_max_heading_level: 4
keywords:
  - doxygen
  - reference
  - file

---

<div class="doxyPage">

# `CSEInfo.cpp` File



## Included Headers

<div class="doxyIncludesList">#include "<a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/codegen/include/llvm/codegen/globalisel/cseinfo-h">llvm/CodeGen/GlobalISel/CSEInfo.h</a>"
#include "<a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/codegen/machineregisterinfo-h">llvm/CodeGen/MachineRegisterInfo.h</a>"
#include "<a href="/web-llvm/docs/api/files/include/include/llvm/initializepasses-h">llvm/InitializePasses.h</a>"
#include "<a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/support/error-h">llvm/Support/Error.h</a>"
</div>

## Functions Index

<table class="doxyMembersIndex">

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a8697530926be8df335eb4268ea856aa3">INITIALIZE_PASS_BEGIN</a> (GISelCSEAnalysisWrapperPass, DEBUG_TYPE, "Analysis containing CSE Info", false, true) INITIALIZE_PASS_END(GISelCSEAnalysisWrapperPass</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">static <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> char *</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a098fa2a14ccb2f871b1c97c2080c3e84">stringify</a> (const MachineInstr *MI, std::string &amp;S)</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a030569d5a541b6110f2ae1b6a3413a58">DEBUG_TYPE</a></td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/files/lib/lib/analysis/blockfrequencyinfo-cpp/#a882e33145fd2a17174b47d3f964a6b2d">Analysis</a> containing <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/scalar/separateconstoffsetfromgep-cpp/#ac56c14d91bc69a17e4e5936093b3bc05">CSE</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a75f8a8519c2c9b30e7c06dc5e256fffa">Info</a></td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/files/lib/lib/analysis/blockfrequencyinfo-cpp/#a882e33145fd2a17174b47d3f964a6b2d">Analysis</a> containing <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/scalar/separateconstoffsetfromgep-cpp/#ac56c14d91bc69a17e4e5936093b3bc05">CSE</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a22a4c8b934523cec38b8b23c2a3476a4">false</a></td>
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

## Macro Definitions Index

<table class="doxyMembersIndex">

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">#define</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ad78e062f62e0d6e453941fb4ca843e4d">DEBUG_TYPE</a>&nbsp;&nbsp;&nbsp;"cseinfo"</td>
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

### INITIALIZE\_PASS\_BEGIN() {#a8697530926be8df335eb4268ea856aa3}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">INITIALIZE_PASS_BEGIN (<a href="/web-llvm/docs/api/classes/llvm/giselcseanalysiswrapperpass">GISelCSEAnalysisWrapperPass</a>, <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/adt/genericcycleimpl-h/#ad78e062f62e0d6e453941fb4ca843e4d">DEBUG_TYPE</a>, "Analysis containing <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/scalar/separateconstoffsetfromgep-cpp/#ac56c14d91bc69a17e4e5936093b3bc05">CSE</a> Info", false, <a href="/web-llvm/docs/api/files/lib/lib/analysis/basicaliasanalysis-cpp/#af6d5cafbdfc5313e65d990120021a3ec">true</a>)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 24 of file <a href="/web-llvm/docs/api/files/lib/lib/codegen/lib/codegen/globalisel/cseinfo-cpp">CSEInfo.cpp</a>.</p>


<p>Reference <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/adt/genericcycleimpl-h/#ad78e062f62e0d6e453941fb4ca843e4d">DEBUG_TYPE</a>.</p>

</div>
</div>

### stringify() {#a098fa2a14ccb2f871b1c97c2080c3e84}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">const char * stringify (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/machineinstr">MachineInstr</a> * MI, <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/demangle/itaniumdemangle-h/#ae2b0d0345572d6718e219aa76d1d54edab45cffe084dd3d20d928bee85e7b0f21">std::string</a> &amp; S)</td>
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



<p>Definition at line 278 of file <a href="/web-llvm/docs/api/files/lib/lib/codegen/lib/codegen/globalisel/cseinfo-cpp">CSEInfo.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/files/lib/lib/codegen/lib/codegen/globalisel/irtranslator-cpp/#abe44dfdea65b4f7e11e0a608ab708b76">MI</a> and <a href="/web-llvm/docs/api/classes/llvm/raw-string-ostream/#a6732e8d3ff8100a662ce73634840b990">llvm::raw_string_ostream::str</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/classes/llvm/giselcseinfo/#ad59eed9a40a4f5cca48396538dcb9b13">llvm::GISelCSEInfo::verify</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Variables

### DEBUG\_TYPE {#a030569d5a541b6110f2ae1b6a3413a58}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">DEBUG_TYPE</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 26 of file <a href="/web-llvm/docs/api/files/lib/lib/codegen/lib/codegen/globalisel/cseinfo-cpp">CSEInfo.cpp</a>.</p>

</div>
</div>

### false {#a22a4c8b934523cec38b8b23c2a3476a4}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">Analysis containing CSE false</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 27 of file <a href="/web-llvm/docs/api/files/lib/lib/codegen/lib/codegen/globalisel/cseinfo-cpp">CSEInfo.cpp</a>.</p>

</div>
</div>

### Info {#a75f8a8519c2c9b30e7c06dc5e256fffa}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">Analysis containing CSE Info</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 27 of file <a href="/web-llvm/docs/api/files/lib/lib/codegen/lib/codegen/globalisel/cseinfo-cpp">CSEInfo.cpp</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/files/lib/lib/codegen/liveregunits-cpp/#a09c3edd4c226f6af4965320fa45f574d">addCalleeSavedRegs</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/amdgpucalllowering-cpp/#a0f19540db0c8b48eebad9481053dc719">addCallTargetOperands</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/siisellowering-cpp/#a7667dd62b97d33296dad1c65be5b088a">addressMayBeAccessedAsPrivate</a>, <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/utils/injecttlimappings-cpp/#aaf2fe2b910650ab4ea0eeaca5922dce8">addVariantDeclaration</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/riscv/riscvinsertvsetvli-cpp/#a29c512a9a215945f15f473648f57537c">adjustIncoming</a>, <a href="/web-llvm/docs/api/namespaces/llvm/memtag/#acc2528429e7e0eb707ca49e72bb3ce49">llvm::memtag::alignAndPadAlloca</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/amdgpucalllowering-cpp/#a3986e436467855478f909c9b2226a066">allocateHSAUserSGPRs</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#ac7f4306c508478ca81791cbccef212fb">llvm::analyzeContextInfo</a>, <a href="/web-llvm/docs/api/classes/anonymous-sifixsgprcopies-cpp-/sifixsgprcopies/#af8967731195e767bf313308f20b640de">anonymous{SIFixSGPRCopies.cpp}::SIFixSGPRCopies::analyzeVGPRToSGPRCopy</a>, <a href="/web-llvm/docs/api/namespaces/llvm/memtag/#abdc52e9e6f499ad37b933391860177aa">llvm::memtag::annotateDebugRecords</a>, <a href="/web-llvm/docs/api/classes/llvm/avrasmbackend/#a863fe7b0cd779f309ac493e93c952d37">llvm::AVRAsmBackend::applyFixup</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/ve/lib/target/ve/asmparser/veasmparser-cpp/#a7e3060b58038543e52c27501d1bb957a">applyMnemonicAliases</a>, <a href="/web-llvm/docs/api/classes/llvm/legalizationartifactcombiner/artifactvaluefinder/#af452509ef47bcb2cae6feec603f566a3">llvm::LegalizationArtifactCombiner::ArtifactValueFinder::ArtifactValueFinder</a>, <a href="/web-llvm/docs/api/structs/llvm/targetlowering/asmoperandinfo/#a298e5957360e936bbd356565a323d45b">llvm::TargetLowering::AsmOperandInfo::AsmOperandInfo</a>, <a href="/web-llvm/docs/api/structs/llvm/calllowering/valueassigner/#ab1caf846fc79aa5976216a32724c9e10">llvm::CallLowering::ValueAssigner::assignArg</a>, <a href="/web-llvm/docs/api/classes/llvm/gcmetadataprinter/#a3945b002b837a5478a79b6a67b94fedc">llvm::GCMetadataPrinter::beginAssembly</a>, <a href="/web-llvm/docs/api/classes/llvm/ssaupdaterimpl/#a85cbdd891f1cd43d6c79f7d68a2caf46">llvm::SSAUpdaterImpl&lt; UpdaterT &gt;::BuildBlockList</a>, <a href="/web-llvm/docs/api/files/lib/lib/codegen/assignmenttrackinganalysis-cpp/#a4ad92667dcad9ad33a52a2e1c505a03a">buildOverlapMapAndRecordDeclares</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/powerpc/ppcisellowering-cpp/#a24d6b4ddc639fabd7fed767dbedfecc2">CalculateTailCallArgDest</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64callingconvention-cpp/#a631b12e0c91c3249444afcf60f3f538c">CC_AArch64_Custom_Block</a>, <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/scalar/constraintelimination-cpp/#ae4662629d6acdb1e1ce903027853151b">checkAndReplaceCmp</a>, <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/scalar/constraintelimination-cpp/#add6cb3c2274e68181ab8a1b4be472b90">checkAndReplaceCondition</a>, <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/scalar/constraintelimination-cpp/#a761596303fee8f03f896c70d36a18303">checkAndReplaceMinMax</a>, <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/scalar/constraintelimination-cpp/#a4bbe548f3095c981a34533d7910a909d">checkCondition</a>, <a href="/web-llvm/docs/api/namespaces/llvm/jitlink/aarch32/#a9c7b359f8ba0aa2c37bb009808262df7">llvm::jitlink::aarch32::checkOpcode</a>, <a href="/web-llvm/docs/api/namespaces/llvm/jitlink/aarch32/#ab081d8136bcb37bb0c6ab56a2714e308">llvm::jitlink::aarch32::checkOpcode</a>, <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/scalar/constraintelimination-cpp/#ab230432af09554d7dd357c77b0ec3cde">checkOrAndOpImpliedByOther</a>, <a href="/web-llvm/docs/api/classes/llvm/offloadentriesinfomanager/offloadentryinfo/#af6e133ed86880e4e491ac6d4290e3cb3">llvm::OffloadEntriesInfoManager::OffloadEntryInfo::classof</a>, <a href="/web-llvm/docs/api/classes/llvm/offloadentriesinfomanager/offloadentryinfodeviceglobalvar/#af5a59021468bb0eb60cf052071e8f3c1">llvm::OffloadEntriesInfoManager::OffloadEntryInfoDeviceGlobalVar::classof</a>, <a href="/web-llvm/docs/api/classes/llvm/offloadentriesinfomanager/offloadentryinfotargetregion/#a7dd9778086a4edb52536845cefe4f3c5">llvm::OffloadEntriesInfoManager::OffloadEntryInfoTargetRegion::classof</a>, <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/scalar/simpleloopunswitch-cpp/#a7737deb6a166cd21dc8465bb48f110b2">collectUnswitchCandidates</a>, <a href="/web-llvm/docs/api/classes/llvm/ondiskchainedhashtablegenerator/#a8b45e8efd4a7a367347aac02098ea9df">llvm::OnDiskChainedHashTableGenerator&lt; Info &gt;::contains</a>, <a href="/web-llvm/docs/api/classes/llvm/ondiskchainedhashtable/#a3898a9f75abb4c57e326727ef77eb5e1">llvm::OnDiskChainedHashTable&lt; Info &gt;::Create</a>, <a href="/web-llvm/docs/api/classes/llvm/ondiskiterablechainedhashtable/#a08f0b83b48f8790ea85409e56975bb17">llvm::OnDiskIterableChainedHashTable&lt; InstrProfLookupTrait &gt;::Create</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/lib/target/aarch64/mctargetdesc/aarch64mctargetdesc-cpp/#ad696b74a93bab0676312a56a5ac9fd6e">createAArch64InstrAnalysis</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/lib/target/amdgpu/mctargetdesc/amdgpumctargetdesc-cpp/#a697fb7093237a8f537855de0d5658c5d">createAMDGPUMCInstrAnalysis</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/arm/lib/target/arm/mctargetdesc/armmctargetdesc-cpp/#a3c086155e4aec51f304192f98dffc355">createARMMCInstrAnalysis</a>, <a href="/web-llvm/docs/api/files/lib/lib/codegen/lib/codegen/globalisel/legalizerhelper-cpp/#aa386a0afb3210b56c30181f93a434ed3">createAtomicLibcall</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/bpf/lib/target/bpf/mctargetdesc/bpfmctargetdesc-cpp/#a8daf8c434a754a1beaffbf6b1fce2762">createBPFInstrAnalysis</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/csky/lib/target/csky/mctargetdesc/cskymctargetdesc-cpp/#a66b748b5de6e99041d1e8b0e3f5edd2b">createCSKYInstrAnalysis</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/csky/lib/target/csky/mctargetdesc/cskymctargetdesc-cpp/#a30965abd308302a5dd6e0aec8c608454">createCSKYMCInstrInfo</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/csky/lib/target/csky/mctargetdesc/cskymctargetdesc-cpp/#a6f810db385349d43b47e340352b007e7">createCSKYMCRegisterInfo</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/hexagon/lib/target/hexagon/mctargetdesc/hexagonmctargetdesc-cpp/#a40aeb85e7cc10164273a5372093b2d20">createHexagonMCInstrAnalysis</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/lanai/lib/target/lanai/mctargetdesc/lanaimctargetdesc-cpp/#a09c0839ecd09c730d3bfc34f35ccaca8">createLanaiInstrAnalysis</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/loongarch/lib/target/loongarch/mctargetdesc/loongarchmctargetdesc-cpp/#a9bb0b74f4059ab83c1e1575f34334e2c">createLoongArchInstrAnalysis</a>, <a href="/web-llvm/docs/api/classes/llvm/target/#abbefc8e1344572c929eec9b2aae2aab4">llvm::Target::createMCInstrAnalysis</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/mips/lib/target/mips/mctargetdesc/mipsmctargetdesc-cpp/#ab7000ff4c930ec5b83f5247b4bd9ab2d">createMipsMCInstrAnalysis</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/powerpc/lib/target/powerpc/mctargetdesc/ppcmctargetdesc-cpp/#aad290c0bff5885f31b1a5c2f5cad29be">createPPCMCInstrAnalysis</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/riscv/lib/target/riscv/mctargetdesc/riscvmctargetdesc-cpp/#aab009e1c2d31b5ea0d6a01d6f42e8d6f">createRISCVInstrAnalysis</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/spirv/lib/target/spirv/mctargetdesc/spirvmctargetdesc-cpp/#a1a4a3698f13ae966030546abee91aaa3">createSPIRVInstrAnalysis</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/systemz/lib/target/systemz/mctargetdesc/systemzmctargetdesc-cpp/#a66288b4f433f0dbd97647337a3c30977">createSystemZMCInstrAnalysis</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/x86/lib/target/x86/mctargetdesc/x86mctargetdesc-cpp/#a7440262314ad975a4aebc1db2926ed53">createX86MCInstrAnalysis</a>, <a href="/web-llvm/docs/api/classes/llvm/ondiskiterablechainedhashtable/data-iterator/#a4a26e30c8d6ebadb103c340498d87ad8">llvm::OnDiskIterableChainedHashTable&lt; Info &gt;::data_iterator::data_iterator</a>, <a href="/web-llvm/docs/api/classes/llvm/pdb/dbimoduledescriptor/#aac49a235168a6c5da4a6b7676032a3b2">llvm::pdb::DbiModuleDescriptor::DbiModuleDescriptor</a>, <a href="/web-llvm/docs/api/classes/llvm/codeview/debugsubsectionrecord/#a6fef9071bdf5369431216a15ec9295bd">llvm::codeview::DebugSubsectionRecord::DebugSubsectionRecord</a>, <a href="/web-llvm/docs/api/files/lib/lib/ir/intrinsics-cpp/#ab29da57c63bb1608298c863ea81696cc">DecodeIITType</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/siisellowering-cpp/#a250dc58b73d94abe917ae8a5b2c45e1b">denormalModeIsFlushAllF32</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/siisellowering-cpp/#a09757ceb0f121bda7fac53a54f1fab85">denormalModeIsFlushAllF64F16</a>, <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/scalar/constraintelimination-cpp/#a61e2de2c4987a7fdaf09251933714262">eliminateConstraints</a>, <a href="/web-llvm/docs/api/classes/llvm/ondiskchainedhashtablegenerator/#a6004e80d1127db853be23ecabf61109e">llvm::OnDiskChainedHashTableGenerator&lt; Info &gt;::Emit</a>, <a href="/web-llvm/docs/api/classes/llvm/ondiskchainedhashtablegenerator/#a9c8d5a30bca2110b979dbe64063ee93d">llvm::OnDiskChainedHashTableGenerator&lt; Info &gt;::Emit</a>, <a href="/web-llvm/docs/api/classes/llvm/bitstreamwriter/#a7507fea7693cf3d8124918eca60eef85">llvm::BitstreamWriter::EmitBlockInfoAbbrev</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64framelowering-cpp/#a035d6de6da7186bb6a0a180c617c8a83">emitCalleeSavedRestores</a>, <a href="/web-llvm/docs/api/files/lib/lib/ir/debuginfo-cpp/#a9b051a25ba281897b4dc62df58312b7e">emitDbgAssign</a>, <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/instrumentation/lowerallowcheckpass-cpp/#a828a09e2cee6726e7ce806bfe21408a7">emitRemark</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64isellowering-cpp/#af13091d8b3eced08538be82392dc7d43">emitSMEStateSaveRestore</a>, <a href="/web-llvm/docs/api/classes/llvm/bitstreamwriter/#ae6a40b4a5ea89bb8b5076c26e0d0b638">llvm::BitstreamWriter::EnterSubblock</a>, <a href="/web-llvm/docs/api/groups/methods/#ga067b49dc851a8db06344fa2b594cb6bb">llvm::dwarf_linker::parallel::CompileUnit::error</a>, <a href="/web-llvm/docs/api/classes/llvm/dwarf-linker/parallel/linkingglobaldata/#a7568407b9d745b41102b67fab20774a6">llvm::dwarf_linker::parallel::LinkingGlobalData::error</a>, <a href="/web-llvm/docs/api/classes/llvm/ondiskchainedhashtable/#adacd724658c20ec2f5becd3ea127d97c">llvm::OnDiskChainedHashTable&lt; Info &gt;::find</a>, <a href="/web-llvm/docs/api/classes/llvm/ondiskchainedhashtable/#a45c3bd7cba6a48f806cccbefbfb61acd">llvm::OnDiskChainedHashTable&lt; Info &gt;::find_hashed</a>, <a href="/web-llvm/docs/api/files/lib/lib/codegen/lib/codegen/selectiondag/selectiondagbuilder-cpp/#aa469012eee439764e752d32b1a557821">findArgumentCopyElisionCandidates</a>, <a href="/web-llvm/docs/api/classes/llvm/ssaupdaterimpl/#a3d50f3f3bb104fb854ac8de326c5bb64">llvm::SSAUpdaterImpl&lt; UpdaterT &gt;::FindAvailableVals</a>, <a href="/web-llvm/docs/api/classes/llvm/ssaupdaterimpl/#a0ab1c1435c29eea38d7a8dd64f064b84">llvm::SSAUpdaterImpl&lt; UpdaterT &gt;::FindDominators</a>, <a href="/web-llvm/docs/api/classes/llvm/ssaupdaterimpl/#aad5016c6fea77df1d3f4af224e1472db">llvm::SSAUpdaterImpl&lt; UpdaterT &gt;::FindPHIPlacement</a>, <a href="/web-llvm/docs/api/classes/llvm/ssaupdaterimpl/#aa2056655c5376accdc268fe15b0683c3">llvm::SSAUpdaterImpl&lt; UpdaterT &gt;::FindSingularVal</a>, <a href="/web-llvm/docs/api/classes/llvm/gcmetadataprinter/#a359a209699c3b8ffeeae95c12889560c">llvm::GCMetadataPrinter::finishAssembly</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/bpf/bpfpreservestaticoffset-cpp/#a37f98e168f7cc70d180aa6bed1625c87">foldGEPChainAsStructAccess</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/bpf/bpfpreservestaticoffset-cpp/#a222f3ff6cc88e36df2f31491a77c102a">foldGEPChainAsU8Access</a>, <a href="/web-llvm/docs/api/classes/llvm/dwarf-linker/parallel/typeunit/#ad0634202a336bbb1a7a03b7885865ba1">llvm::dwarf_linker::parallel::TypeUnit::forEachAcceleratorRecord</a>, <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/scalar/constraintelimination-cpp/#a7ea4fb4d6b0198f2b6eac325a8d93031">generateReproducer</a>, <a href="/web-llvm/docs/api/classes/llvm/fppassmanager/#a9f705624b39de54c48bbf99554f4da75">llvm::FPPassManager::getAnalysisUsage</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/arm/lib/target/arm/mctargetdesc/armmctargetdesc-cpp/#a0d1a03784a748be72ac0447bf24aef7a">getARMLoadDeprecationInfo</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/arm/lib/target/arm/mctargetdesc/armmctargetdesc-cpp/#a0c8fda450af15c6221ae4f6ef5f6ff24">getARMStoreDeprecationInfo</a>, <a href="/web-llvm/docs/api/files/lib/lib/bitcode/lib/bitcode/reader/bitcodeanalyzer-cpp/#a1a61b4058a0d8fdb477afc3020adee5b">GetBlockName</a>, <a href="/web-llvm/docs/api/classes/llvm/aarch64functioninfo/#a217c3db3b137e03bd6ade29bb9999ac9">llvm::AArch64FunctionInfo::getCalleeSavedStackSize</a>, <a href="/web-llvm/docs/api/namespaces/llvm/amdgpu/#a32f1c4783795ef5202498f5d21283564">llvm::AMDGPU::getCanBeVOPD</a>, <a href="/web-llvm/docs/api/files/lib/lib/bitcode/lib/bitcode/reader/bitcodeanalyzer-cpp/#ad0ea28d901a2351fedec9ef3deec2663">GetCodeName</a>, <a href="/web-llvm/docs/api/namespaces/llvm/riscv/#a52a42ddb53fcd9e2a32f0a72e537ce25">llvm::RISCV::getCPUModel</a>, <a href="/web-llvm/docs/api/files/lib/lib/dwp/dwp-cpp/#a8bd04295f552ef30463ffb24174d649b">getCUIdentifiers</a>, <a href="/web-llvm/docs/api/namespaces/llvm/amdgpu/#a2c8c02eb613c071ae5ebd12779080850">llvm::AMDGPU::getFPDstSelType</a>, <a href="/web-llvm/docs/api/classes/llvm/ondiskchainedhashtable/#a28233f57b36fa8348a396074fa482697">llvm::OnDiskChainedHashTable&lt; Info &gt;::getInfoObj</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/lib/target/aarch64/mctargetdesc/aarch64instprinter-cpp/#a569a198876e563d1f7aa27fb11b83461">getLdStNInstrDesc</a>, <a href="/web-llvm/docs/api/namespaces/llvm/amdgpu/#ae0ff550663df186d7412ff2860d337e0">llvm::AMDGPU::getMAIIsDGEMM</a>, <a href="/web-llvm/docs/api/namespaces/llvm/amdgpu/#a571ab690de666287c96ccb65d6e1b9c9">llvm::AMDGPU::getMAIIsGFX940XDL</a>, <a href="/web-llvm/docs/api/namespaces/llvm/riscv/#aa1a88282ee75c6ad620fe96960537028">llvm::RISCV::getMArchFromMcpu</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/lib/target/aarch64/gisel/aarch64calllowering-cpp/#a79d70fa60cedff640ded089e56149d24">getMaskForArgs</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/arm/lib/target/arm/mctargetdesc/armmctargetdesc-cpp/#a7d9b81caded54a832c1ea707e1c189af">getMCRDeprecationInfo</a>, <a href="/web-llvm/docs/api/namespaces/llvm/amdgpu/#ad144bab75c70002b0b3227acf782ebc3">llvm::AMDGPU::getMIMGBaseOpcode</a>, <a href="/web-llvm/docs/api/namespaces/llvm/amdgpu/#a176f799037e98f7743008924c4b72266">llvm::AMDGPU::getMIMGOpcode</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/arm/lib/target/arm/mctargetdesc/armmctargetdesc-cpp/#acd2a2ba2a82e6388c9b7e00e38c7b24f">getMRCDeprecationInfo</a>, <a href="/web-llvm/docs/api/namespaces/llvm/amdgpu/#a688f3c46ebc34c00ea80c22c15a0b0c1">llvm::AMDGPU::getMTBUFBaseOpcode</a>, <a href="/web-llvm/docs/api/namespaces/llvm/amdgpu/#a23d9368d9915a85d5b54f9e0eda046dd">llvm::AMDGPU::getMTBUFElements</a>, <a href="/web-llvm/docs/api/namespaces/llvm/amdgpu/#a4d33ed416833f75e97045b3ce8380132">llvm::AMDGPU::getMTBUFHasSoffset</a>, <a href="/web-llvm/docs/api/namespaces/llvm/amdgpu/#a181d2e596332f4062206a62830426b86">llvm::AMDGPU::getMTBUFHasSrsrc</a>, <a href="/web-llvm/docs/api/namespaces/llvm/amdgpu/#aee6b630ac15f65f731a072177d51207c">llvm::AMDGPU::getMTBUFHasVAddr</a>, <a href="/web-llvm/docs/api/namespaces/llvm/amdgpu/#a9c26c5e0b091dffd780ac854e30a2d40">llvm::AMDGPU::getMTBUFOpcode</a>, <a href="/web-llvm/docs/api/namespaces/llvm/amdgpu/#a5f0dcf0fee31f552637de794eef6696e">llvm::AMDGPU::getMUBUFBaseOpcode</a>, <a href="/web-llvm/docs/api/namespaces/llvm/amdgpu/#af8ef23452a5c4ddf85e45cc9884ea3f4">llvm::AMDGPU::getMUBUFElements</a>, <a href="/web-llvm/docs/api/namespaces/llvm/amdgpu/#aa303bfa4cd838f547ba84ab62cd93c95">llvm::AMDGPU::getMUBUFHasSoffset</a>, <a href="/web-llvm/docs/api/namespaces/llvm/amdgpu/#afd9dbd4307d57a7043f5412176674de4">llvm::AMDGPU::getMUBUFHasSrsrc</a>, <a href="/web-llvm/docs/api/namespaces/llvm/amdgpu/#a723087d5f4635793f28b71ee6cdafecd">llvm::AMDGPU::getMUBUFHasVAddr</a>, <a href="/web-llvm/docs/api/namespaces/llvm/amdgpu/#ad6c6b1894340016cee9e4b730ade8af6">llvm::AMDGPU::getMUBUFIsBufferInv</a>, <a href="/web-llvm/docs/api/namespaces/llvm/amdgpu/#a55c87ec01cfedf7c509d68763d1e0ac3">llvm::AMDGPU::getMUBUFOpcode</a>, <a href="/web-llvm/docs/api/namespaces/llvm/amdgpu/#a906682f8b1321246591a09c18550243e">llvm::AMDGPU::getMUBUFTfe</a>, <a href="/web-llvm/docs/api/classes/llvm/targettransforminfo/concept/#a81dde3d93614007bf9ad6edb2dc7cdf8">llvm::TargetTransformInfo::Concept::getPointersChainCost</a>, <a href="/web-llvm/docs/api/classes/llvm/targettransforminfoimplcrtpbase/#a824c5127d35e6fc5004e7595959a5a55">llvm::TargetTransformInfoImplCRTPBase&lt; T &gt;::getPointersChainCost</a>, <a href="/web-llvm/docs/api/namespaces/llvm/amdgpu/#a406d4769ffa44a11df136d3ccd08e873">llvm::AMDGPU::getSMEMIsBuffer</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/siisellowering-cpp/#ab026557e78590060ce851bf04f1f37c8">getSPDenormModeValue</a>, <a href="/web-llvm/docs/api/classes/llvm/targettransforminfo/concept/#a71c4312004a41f84195b8130b096febf">llvm::TargetTransformInfo::Concept::getTgtMemIntrinsic</a>, <a href="/web-llvm/docs/api/classes/llvm/targettransforminfoimplbase/#a99c54bbcc352a128578fb78c3cbd715d">llvm::TargetTransformInfoImplBase::getTgtMemIntrinsic</a>, <a href="/web-llvm/docs/api/groups/vfdatabase/#ga27014498d4eea7c1e7455cc33538ca2b">llvm::VFDatabase::getVectorizedFunction</a>, <a href="/web-llvm/docs/api/namespaces/llvm/amdgpu/#a6426a76cde8500099fed57ff9beeace5">llvm::AMDGPU::getVOP1IsSingle</a>, <a href="/web-llvm/docs/api/namespaces/llvm/amdgpu/#adfd7285a06455bb3bec2d36b57380849">llvm::AMDGPU::getVOP2IsSingle</a>, <a href="/web-llvm/docs/api/namespaces/llvm/amdgpu/#a613e1ffe13a3fd0effd5d299cb5b2665">llvm::AMDGPU::getVOP3IsSingle</a>, <a href="/web-llvm/docs/api/namespaces/llvm/amdgpu/#a793e7e7fed833a9bb98eac96740e2338">llvm::AMDGPU::getVOPDComponents</a>, <a href="/web-llvm/docs/api/namespaces/llvm/amdgpu/#a72741e790a9064b40d5668e79d8fc38a">llvm::AMDGPU::getVOPDFull</a>, <a href="/web-llvm/docs/api/namespaces/llvm/amdgpu/#a5079de0e4b3493921d87dcee10f44253">llvm::AMDGPU::getVOPDOpcode</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64collectloh-cpp/#a897e4640c14c6556e0b1bc06eca81134">handleADRP</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64collectloh-cpp/#aa29bedb450469f2260b81f5500326305">handleClobber</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64collectloh-cpp/#ae251b02643ece61176adb4ce4e93784d">handleUse</a>, <a href="/web-llvm/docs/api/namespaces/llvm/riscv/#ac36b8463f42c23ad23f192d2b010cd26">llvm::RISCV::hasFastScalarUnalignedAccess</a>, <a href="/web-llvm/docs/api/namespaces/llvm/riscv/#a19983aded32f1173ffe828b87dce8dbb">llvm::RISCV::hasFastVectorUnalignedAccess</a>, <a href="/web-llvm/docs/api/classes/llvm/vfdatabase/#a5bc75b1206e95a50c02938ba2591f22f">llvm::VFDatabase::hasMaskedVariant</a>, <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/ipo/functionattrs-cpp/#a25e479981fb1f791dba4f32a891d6ff2">inferInitializes</a>, <a href="/web-llvm/docs/api/files/lib/lib/codegen/lib/codegen/selectiondag/selectiondag-cpp/#aaebdecc6b4a89094d56ba277ce310749">InferPointerInfo</a>, <a href="/web-llvm/docs/api/files/lib/lib/codegen/lib/codegen/selectiondag/selectiondag-cpp/#acbecb8c0075dadcf9bfdd8ff59beccf9">InferPointerInfo</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/riscv/riscvinsertvsetvli-cpp/#aeab9aaa0283d5249c25d93393677af94">INITIALIZE_PASS</a>, <a href="/web-llvm/docs/api/classes/llvm/ondiskchainedhashtablegenerator/#a812fa399c4340294d8c4da56a2cab86c">llvm::OnDiskChainedHashTableGenerator&lt; Info &gt;::insert</a>, <a href="/web-llvm/docs/api/classes/llvm/ondiskchainedhashtablegenerator/#af0c504f45a13781f51ece31c81d83f00">llvm::OnDiskChainedHashTableGenerator&lt; Info &gt;::insert</a>, <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/scalar/rewritestatepointsforgc-cpp/#a864a2ad11bbf83cf2b910e43d461cd02">insertParsePoints</a>, <a href="/web-llvm/docs/api/files/lib/lib/dwarflinker/lib/dwarflinker/parallel/dependencytracker-cpp/#a0bd005c8437f95e31592128ee5c97e99">isAlreadyMarked</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64machinefunctioninfo-cpp/#ad8d9de20a2440d472786e299fc96a97e">isLRSpilled</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#acc6108333e358848db3db11c51d105ef">llvm::isODRCanonicalCandidate</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64isellowering-cpp/#ab16033fb6e8c75e0dccb0cda82ec1158">isSetCCOrZExtSetCC</a>, <a href="/web-llvm/docs/api/namespaces/llvm/amdgpu/#a75b79141e48ddded5600396eeb38eb1c">llvm::AMDGPU::isTrue16Inst</a>, <a href="/web-llvm/docs/api/namespaces/llvm/ppc/#a40c4695a9cfc9ce20f0c6d8291aca7de">llvm::PPC::isValidCPU</a>, <a href="/web-llvm/docs/api/classes/llvm/ondiskchainedhashtable/iterator/#a99d7686510cf9da6974d3d1eee361e2e">llvm::OnDiskChainedHashTable&lt; Info &gt;::iterator::iterator</a>, <a href="/web-llvm/docs/api/classes/llvm/ondiskiterablechainedhashtable/key-iterator/#ac3da535a5e8cacf08a92f4a73e7ada35">llvm::OnDiskIterableChainedHashTable&lt; Info &gt;::key_iterator::key_iterator</a>, <a href="/web-llvm/docs/api/classes/llvm/mcasmparser/#ad75338a56ab81e83583aafaf2f2f1246">llvm::MCAsmParser::lookUpField</a>, <a href="/web-llvm/docs/api/classes/llvm/mcasmparser/#add0e53028d15679b96b8f66849b4e971">llvm::MCAsmParser::lookUpField</a>, <a href="/web-llvm/docs/api/files/lib/lib/targetparser/aarch64targetparser-cpp/#a9d58f2750729907893739c1d4e2d5384">lookupFMVByID</a>, <a href="/web-llvm/docs/api/classes/llvm/mcasmparsersemacallback/#abbc6b9da69750bd5103d06546ceb9328">llvm::MCAsmParserSemaCallback::LookupInlineAsmIdentifier</a>, <a href="/web-llvm/docs/api/classes/llvm/mcasmparser/#ac9dea6fd0f51f338ae588d9cef3fa6e8">llvm::MCAsmParser::lookUpType</a>, <a href="/web-llvm/docs/api/classes/llvm/calllowering/#af40849adf5cf5ed971196ae2c248b7e1">llvm::CallLowering::lowerCall</a>, <a href="/web-llvm/docs/api/structs/llvm/yaml/mappingtraits-f7c06f2fecbf5381db4e21f582702b2c/#a276e00d7c811f394734757f9805a0e3b">llvm::yaml::MappingTraits&lt; WasmYAML::DylinkExportInfo &gt;::mapping</a>, <a href="/web-llvm/docs/api/structs/llvm/yaml/mappingtraits-eddac8dc3c990dc0ad15f5117f66967c/#abed2912855aa4df0be5d9b2b1e31a809">llvm::yaml::MappingTraits&lt; WasmYAML::DylinkImportInfo &gt;::mapping</a>, <a href="/web-llvm/docs/api/structs/llvm/yaml/mappingtraits-3893a56453e0d2967d45a2698063e0bc/#ad8de3589d429d71d64908ba67d607f5d">llvm::yaml::MappingTraits&lt; WasmYAML::SymbolInfo &gt;::mapping</a>, <a href="/web-llvm/docs/api/namespaces/llvm/amdgpu/#a2006d74041f6c3411ccd43a4ce7e610b">llvm::AMDGPU::mapWMMA2AddrTo3AddrOpcode</a>, <a href="/web-llvm/docs/api/namespaces/llvm/amdgpu/#afc428424126b53a5fe6f1004854803fe">llvm::AMDGPU::mapWMMA3AddrTo2AddrOpcode</a>, <a href="/web-llvm/docs/api/classes/llvm/detail/errormatchesmono/#ab5ca366d69aa6962d4142ab273fa72b1">llvm::detail::ErrorMatchesMono&lt; InfoT &gt;::MatchAndExplain</a>, <a href="/web-llvm/docs/api/classes/llvm/detail/errormessagematches/#ac6fe268bac0c05dbccf3c63bbb54b356">llvm::detail::ErrorMessageMatches::MatchAndExplain</a>, <a href="/web-llvm/docs/api/classes/llvm/ondiskchainedhashtable/#ae8f4b4a9f62be401ef00370723d33eb3">llvm::OnDiskChainedHashTable&lt; Info &gt;::OnDiskChainedHashTable</a>, <a href="/web-llvm/docs/api/classes/llvm/ondiskiterablechainedhashtable/#aa451d1ab92d61da67ac7e7d3c198eeca">llvm::OnDiskIterableChainedHashTable&lt; InstrProfLookupTrait &gt;::OnDiskIterableChainedHashTable</a>, <a href="/web-llvm/docs/api/classes/llvm/oprofilewrapper/#abf54432b7e558fe9cc479ce12abfa249">llvm::OProfileWrapper::op_write_debug_line_info</a>, <a href="/web-llvm/docs/api/structs/llvm/varstreamarrayextractor-aa4cf4a73737d16d115dea80ff681a08/#a5245c9fad1a0cc1f3e4e9b1106fe9dc1">llvm::VarStreamArrayExtractor&lt; codeview::DebugSubsectionRecord &gt;::operator()</a>, <a href="/web-llvm/docs/api/structs/llvm/varstreamarrayextractor-4459a4f1e1f6940150dfae71388b4626/#a598d96531e2c247dfaa1b7ce4ca2c637">llvm::VarStreamArrayExtractor&lt; pdb::DbiModuleDescriptor &gt;::operator()</a>, <a href="/web-llvm/docs/api/classes/llvm/orc/unwindinfomanager/#ae29add448191f1ccd3443de11f006ee7">llvm::orc::UnwindInfoManager::operator=</a>, <a href="/web-llvm/docs/api/classes/llvm/pdb/dbimoduledescriptor/#ac48d58be2ee022d594e43c293f7544f8">llvm::pdb::DbiModuleDescriptor::operator=</a>, <a href="/web-llvm/docs/api/namespaces/llvm/riscv/#ac2398432bd0044a48418ec288f08be08">llvm::RISCV::parseCPU</a>, <a href="/web-llvm/docs/api/classes/llvm/mctargetasmparser/#a9d095012b8efc8795fe4403722dcf9d4">llvm::MCTargetAsmParser::parseInstruction</a>, <a href="/web-llvm/docs/api/classes/llvm/mctargetasmparser/#a058facd817d442129355ef40eb9a1140">llvm::MCTargetAsmParser::parseInstruction</a>, <a href="/web-llvm/docs/api/classes/anonymous-asmparser-cpp-/asmparser/#a6779c29e343b8e71d97734686a3eabd2">anonymous{AsmParser.cpp}::AsmParser::parseMSInlineAsm</a>, <a href="/web-llvm/docs/api/classes/anonymous-masmparser-cpp-/masmparser/#ae48dce9460eac00f49a306f8d48fdf11">anonymous{MasmParser.cpp}::MasmParser::parseMSInlineAsm</a>, <a href="/web-llvm/docs/api/classes/llvm/partialorderingvisitor/#afa6befc04cbb0a31a669dadbac54ac19">llvm::PartialOrderingVisitor::PartialOrderingVisitor</a>, <a href="/web-llvm/docs/api/classes/llvm/symbolize/diprinter/#ac1c0e21be7e3c3ae668b3ed67544e053">llvm::symbolize::DIPrinter::print</a>, <a href="/web-llvm/docs/api/classes/llvm/symbolize/diprinter/#a7d68ff942e7c347303116d55224b3d0c">llvm::symbolize::DIPrinter::print</a>, <a href="/web-llvm/docs/api/classes/llvm/symbolize/jsonprinter/#a808d66d93b73e4fdd1e409c9ba48671b">llvm::symbolize::JSONPrinter::print</a>, <a href="/web-llvm/docs/api/classes/llvm/symbolize/jsonprinter/#a49caccc35b75eca4c29effcf33e9717e">llvm::symbolize::JSONPrinter::print</a>, <a href="/web-llvm/docs/api/classes/llvm/symbolize/plainprinterbase/#affd94f6421b8ea9074813cb07edf9af1">llvm::symbolize::PlainPrinterBase::print</a>, <a href="/web-llvm/docs/api/classes/llvm/symbolize/plainprinterbase/#a6bff6c70586253ff2ff4384e22e4055d">llvm::symbolize::PlainPrinterBase::print</a>, <a href="/web-llvm/docs/api/classes/llvm/symbolize/plainprinterbase/#a9eceb285970ae32b1492fe2ad2e7462d">llvm::symbolize::PlainPrinterBase::print</a>, <a href="/web-llvm/docs/api/classes/llvm/symbolize/plainprinterbase/#a8ce63a033c09a94bc80b9e43ac721256">llvm::symbolize::PlainPrinterBase::printSimpleLocation</a>, <a href="/web-llvm/docs/api/classes/llvm/symbolize/plainprinterbase/#a2bba3718362838610c71e8da832d562b">llvm::symbolize::PlainPrinterBase::printStartAddress</a>, <a href="/web-llvm/docs/api/namespaces/llvm/detail/#a8e42ee77c6f653926adf1253af32dea0">llvm::detail::PrintTo</a>, <a href="/web-llvm/docs/api/classes/llvm/symbolize/plainprinterbase/#a9dfac6ddf7f17b7fd9d397483d13d091">llvm::symbolize::PlainPrinterBase::printVerbose</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/siisellowering-cpp/#a406a444512ca2224d325c9a217c31547">processPSInputArgs</a>, <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/utils/promotememorytoregister-cpp/#a6952450f0726bd9c26d303743522e227">promoteSingleBlockAlloca</a>, <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/scalar/rewritestatepointsforgc-cpp/#af864550d3c61aff5c6777610fdba8b7f">recomputeLiveInValues</a>, <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/scalar/rewritestatepointsforgc-cpp/#a55412d2c237115c95f20e12ba0d95922">relocationViaAlloca</a>, <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/scalar/rewritestatepointsforgc-cpp/#a0650e5c5d027b7ef00c23a7921c114db">rematerializeLiveValues</a>, <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/scalar/constraintelimination-cpp/#a49876ad04843c072ef3aab5f0b10dd91">removeEntryFromStack</a>, <a href="/web-llvm/docs/api/files/lib/lib/codegen/replacewithveclib-cpp/#a43ccb9c1a5081a041efc8db46bbcf7a2">replaceWithTLIFunction</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/siisellowering-cpp/#a049dfdf656884a9d492cb2bc7a664dbf">reservePrivateMemoryRegs</a>, <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/utils/promotememorytoregister-cpp/#aa231a7e6d411bd4797afdd6f0a1f8d6a">rewriteSingleStoreAlloca</a>, <a href="/web-llvm/docs/api/classes/anonymous-asmparser-cpp-/asmparser/#a1f9777a39f525bf9f8a85ce9d52cccd9">anonymous{AsmParser.cpp}::AsmParser::Run</a>, <a href="/web-llvm/docs/api/classes/anonymous-masmparser-cpp-/masmparser/#a46449244c1f2d4e4b2022d1126e7c5ab">anonymous{MasmParser.cpp}::MasmParser::Run</a>, <a href="/web-llvm/docs/api/classes/anonymous-canonicalizefreezeinloops-cpp-/canonicalizefreezeinloopsimpl/#aff534de0962628bba1821ef3c0821308">anonymous{CanonicalizeFreezeInLoops.cpp}::CanonicalizeFreezeInLoopsImpl::run</a>, <a href="/web-llvm/docs/api/classes/llvm/gcfunctionanalysis/#ac5aa6845030bc914c7c26ab65e25984e">llvm::GCFunctionAnalysis::run</a>, <a href="/web-llvm/docs/api/files/lib/lib/support/crashrecoverycontext-cpp/#a6741df1ae96240967c1fab2d6668d59a">RunSafelyOnThread_Dispatch</a>, <a href="/web-llvm/docs/api/classes/llvm/dwarf-linker/parallel/compileunit/#aa24ff91f920a0a4c418dabab4323125e">llvm::dwarf_linker::parallel::CompileUnit::saveAcceleratorInfo</a>, <a href="/web-llvm/docs/api/classes/llvm/dwarf-linker/parallel/typeunit/#a0b32b6e055f2378aeb16ea13c10dd2a1">llvm::dwarf_linker::parallel::TypeUnit::saveAcceleratorInfo</a>, <a href="/web-llvm/docs/api/classes/llvm/machineirbuilder/#ad2a55990c65a2e9965e91c74a293df22">llvm::MachineIRBuilder::setCSEInfo</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64isellowering-cpp/#a430025e146710444567fa8bd1da2d3a9">setInfoSVEStN</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/bpf/bpfcheckandadjustir-cpp/#a6e78c58ee832ea1775655021854401e6">sinkMinMaxInBB</a>, <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/ipo/globalsplit-cpp/#aa0b982cd11d8eef0277074095aca3b43">splitGlobal</a>, <a href="/web-llvm/docs/api/files/lib/lib/objectyaml/minidumpyaml-cpp/#a5a05da0184dda537b6b887e52a313801">streamMapping</a>, <a href="/web-llvm/docs/api/classes/llvm/combinerhelper/#a094194cbf835d3ebeb1039b1ed575121">llvm::CombinerHelper::tryCombine</a>, <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/scalar/constraintelimination-cpp/#acb9adec0a838b8a5664673e0c7265c4b">tryToSimplifyOverflowMath</a>, <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/utils/looppeel-cpp/#a070d953c06601ec34680fdc35c867b17">updateBranchWeights</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#ab4e285e28ea8fd6b3a8ab702133c5d97">llvm::updateChildPruning</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a931cfa6e58e63d6d65fa10e8ce2e18ff">llvm::updatePruning</a>, <a href="/web-llvm/docs/api/classes/llvm/upward-defs-iterator/#a0bddccc79dd1fe5b0ef75e4d239a381c">llvm::upward_defs_iterator::upward_defs_iterator</a>, <a href="/web-llvm/docs/api/classes/llvm/blockcoverageinference/#a6cb0caabfbfedc60d222a51bde7d5525">llvm::BlockCoverageInference::viewBlockCoverageGraph</a>, <a href="/web-llvm/docs/api/groups/methods/#ga654eee00b3eed07a03d37b22391d18e2">llvm::dwarf_linker::parallel::CompileUnit::warn</a> and <a href="/web-llvm/docs/api/classes/llvm/dwarf-linker/parallel/linkingglobaldata/#a4430fdd1c34d0b9d5014d3cbbddc9916">llvm::dwarf_linker::parallel::LinkingGlobalData::warn</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Macro Definitions

### DEBUG\_TYPE {#ad78e062f62e0d6e453941fb4ca843e4d}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">#define DEBUG_TYPE&nbsp;&nbsp;&nbsp;"cseinfo"</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 16 of file <a href="/web-llvm/docs/api/files/lib/lib/codegen/lib/codegen/globalisel/cseinfo-cpp">CSEInfo.cpp</a>.</p>

</div>
</div>

</div>

<hr/>

<p class="doxyGeneratedBy">Generated via <a href="https://github.com/xpack/doxygen2docusaurus">doxygen2docusaurus</a> by <a href="https://www.doxygen.nl">Doxygen</a> 1.15.0.</p>

</div>
