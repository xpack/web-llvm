---

# DO NOT EDIT!
# Automatically generated via doxygen2docusaurus by Doxygen.

slug: /api/files/lib/lib/object/tapifile-cpp
custom_edit_url: null
toc_max_heading_level: 4
keywords:
  - doxygen
  - reference
  - file

---

<div class="doxyPage">

# The `TapiFile.cpp` File Reference



## Included Headers

<div class="doxyIncludesList">#include "<a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/object/tapifile-h">llvm/Object/TapiFile.h</a>"
#include "<a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/adt/stringref-h">llvm/ADT/StringRef.h</a>"
#include "<a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/binaryformat/macho-h">llvm/BinaryFormat/MachO.h</a>"
#include "<a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/support/memorybufferref-h">llvm/Support/MemoryBufferRef.h</a>"
#include "<a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/textapi/architectureset-h">llvm/TextAPI/ArchitectureSet.h</a>"
#include "<a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/textapi/interfacefile-h">llvm/TextAPI/InterfaceFile.h</a>"
#include "<a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/textapi/platform-h">llvm/TextAPI/Platform.h</a>"
#include "<a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/textapi/symbol-h">llvm/TextAPI/Symbol.h</a>"
</div>

## Functions Index

<table class="doxyMembersIndex">

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">static uint32_t</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a7a3ba7cd94762ae7f243367830320ca2">getFlags</a> (const Symbol *Sym)</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">static <a href="/web-llvm/docs/api/classes/llvm/object/symbolref/#a2ea2ecb4f81936cc379aff129e440b04">SymbolRef::Type</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a913a691648e20063bbd278e8f02d8430">getType</a> (const Symbol *Sym)</td>
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

### getFlags() {#a7a3ba7cd94762ae7f243367830320ca2}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">uint32_t getFlags (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/macho/symbol">Symbol</a> * Sym)</td>
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



<p>Definition at line 26 of file <a href="/web-llvm/docs/api/files/lib/lib/object/tapifile-cpp">TapiFile.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/classes/llvm/macho/symbol/#a4958630033c0184bc5c6d56ae9be419b">llvm::MachO::Symbol::isUndefined</a>, <a href="/web-llvm/docs/api/classes/llvm/macho/symbol/#a34316d3e86024e41a84c08239a65405d">llvm::MachO::Symbol::isWeakDefined</a>, <a href="/web-llvm/docs/api/classes/llvm/macho/symbol/#ae25e6461883a31fe9dc9868b1af23213">llvm::MachO::Symbol::isWeakReferenced</a>, <a href="/web-llvm/docs/api/classes/llvm/object/basicsymbolref/#a9004a106627deafd45a7c95ee497d431a3936e16c4ba4b109e74006ad9bdc06f8">llvm::object::BasicSymbolRef::SF_Exported</a>, <a href="/web-llvm/docs/api/classes/llvm/object/basicsymbolref/#a9004a106627deafd45a7c95ee497d431a1cc593ee22b60969ba0a3cb1e5e21b34">llvm::object::BasicSymbolRef::SF_Global</a>, <a href="/web-llvm/docs/api/classes/llvm/object/basicsymbolref/#a9004a106627deafd45a7c95ee497d431ad1131f10939b205635a0dc81ca3c45d7">llvm::object::BasicSymbolRef::SF_Undefined</a> and <a href="/web-llvm/docs/api/classes/llvm/object/basicsymbolref/#a9004a106627deafd45a7c95ee497d431ac199a3dc25299a191397723e89fd303e">llvm::object::BasicSymbolRef::SF_Weak</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/files/lib/lib/dwp/dwp-cpp/#a358c1febb02bfec774608e4761b27495">handleCompressedSection</a>, <a href="/web-llvm/docs/api/groups/llvmccoredebuginfo/#ga6bcea905cd35ad99a0d535721d8fe4ff">LLVMDITypeGetFlags</a>, <a href="/web-llvm/docs/api/structs/llvm/mdnodekeyimpl-a632dbe89953e38d9916f1f9c85a00c6/#aa3b1d4a500150aacea4fb0d1ec75efdf">llvm::MDNodeKeyImpl&lt; DIBasicType &gt;::MDNodeKeyImpl</a>, <a href="/web-llvm/docs/api/structs/llvm/mdnodekeyimpl-da9e4b682a4b3039a31f92ca230d6551/#a92dc296b7b60e0848408156781b20ec4">llvm::MDNodeKeyImpl&lt; DICompositeType &gt;::MDNodeKeyImpl</a>, <a href="/web-llvm/docs/api/structs/llvm/mdnodekeyimpl-2b01e7dc5fb21182294e60ed35cddf36/#ab24b963a11ddc0efebe8a87a99bf5709">llvm::MDNodeKeyImpl&lt; DILocalVariable &gt;::MDNodeKeyImpl</a>, <a href="/web-llvm/docs/api/structs/llvm/mdnodekeyimpl-faa368e9a849f1379853705e8fc6ebb3/#adeb53eac2ad31e8fd72358d55ff79b77">llvm::MDNodeKeyImpl&lt; DISubroutineType &gt;::MDNodeKeyImpl</a>, <a href="/web-llvm/docs/api/structs/llvm/yaml/anonymous-elfyaml-cpp-/normalizedother/#ac2713b0aecf2732a7d6ffb601b9c51ba">llvm::yaml::anonymous{ELFYAML.cpp}::NormalizedOther::NormalizedOther</a>, <a href="/web-llvm/docs/api/namespaces/anonymous-textstubv5-cpp-/stubparser/#a513f7b203ab0641c05df11c260144622">anonymous{TextStubV5.cpp}::StubParser::parseToInterfaceFile</a> and <a href="/web-llvm/docs/api/structs/llvm/yaml/anonymous-elfyaml-cpp-/normalizedother/#af3bd8dea70f65afd2d7e5f4fc90b2d99">llvm::yaml::anonymous{ELFYAML.cpp}::NormalizedOther::toValue</a>.</p>

</div>
</div>

### getType() {#a913a691648e20063bbd278e8f02d8430}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">SymbolRef::Type getType (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/macho/symbol">Symbol</a> * Sym)</td>
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



<p>Definition at line 39 of file <a href="/web-llvm/docs/api/files/lib/lib/object/tapifile-cpp">TapiFile.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/classes/llvm/macho/symbol/#a05978ef58f3565e7e40ea202098c4caf">llvm::MachO::Symbol::isData</a>, <a href="/web-llvm/docs/api/classes/llvm/macho/symbol/#ad526f1e4f52f0ed3992733045fc2e088">llvm::MachO::Symbol::isText</a>, <a href="/web-llvm/docs/api/classes/llvm/object/symbolref/#a2ea2ecb4f81936cc379aff129e440b04a8a501fedaaa3e562541580b8f1db3975">llvm::object::SymbolRef::ST_Data</a>, <a href="/web-llvm/docs/api/classes/llvm/object/symbolref/#a2ea2ecb4f81936cc379aff129e440b04a2fcf5b0171fb8526218be425765b5da1">llvm::object::SymbolRef::ST_Function</a> and <a href="/web-llvm/docs/api/classes/llvm/object/symbolref/#a2ea2ecb4f81936cc379aff129e440b04a2d334a713a4916963744a0cc31ab9552">llvm::object::SymbolRef::ST_Unknown</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/structs/llvm/calllowering/arginfo/#aec3a44a4fabb326d6561308bfa0ec87c">llvm::CallLowering::ArgInfo::ArgInfo</a>, <a href="/web-llvm/docs/api/structs/anonymous-attributorattributes-cpp-/aavaluesimplifyimpl/#ac74c71265c51cb1cd82cebadc0cfa913">anonymous{AttributorAttributes.cpp}::AAValueSimplifyImpl::askSimplifiedValueFor</a>, <a href="/web-llvm/docs/api/classes/llvm/machineirbuilder/#ae83cc330c36190cf8ee9618a28e9a300">llvm::MachineIRBuilder::buildBlockAddress</a>, <a href="/web-llvm/docs/api/classes/llvm/machineirbuilder/#a1e5b88856596e413494661b5fae9fc39">llvm::MachineIRBuilder::buildBoolExt</a>, <a href="/web-llvm/docs/api/classes/llvm/machineirbuilder/#aecf67aca8d78d0136244799c4182e52f">llvm::MachineIRBuilder::buildBrIndirect</a>, <a href="/web-llvm/docs/api/classes/llvm/machineirbuilder/#aaf1013659ccc9708197f76c0bd724936">llvm::MachineIRBuilder::buildBrJT</a>, <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/utils/amdgpuemitprintf-cpp/#a49077c24022f5ec4c84d809abf92e91e">callBufferedPrintfStart</a>, <a href="/web-llvm/docs/api/classes/llvm/shufflevectorinst/#a1552dc44fac81fb75a474feaa2ffdab8">llvm::ShuffleVectorInst::changesLength</a>, <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/coroutines/corosplit-cpp/#ab349dce775a8c8dcd72c24059e8357a2">coerceArguments</a>, <a href="/web-llvm/docs/api/files/lib/lib/analysis/scalarevolution-cpp/#a342ca2d063631fda10c6c47cbdc397f3">CompareSCEVComplexity</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#af7b6ae12af3578f7a20ccc11a4458f9f">llvm::computeMinimumValueSizes</a>, <a href="/web-llvm/docs/api/structs/anonymous-elfobjectwriter-cpp-/elfwriter/#a701e935a2d02fd488218cf26b8eedb67">anonymous{ELFObjectWriter.cpp}::ELFWriter::computeSymbolTable</a>, <a href="/web-llvm/docs/api/classes/anonymous-hexagonvectorcombine-cpp-/hexagonvectorcombine/#a3d42f23852edcd240ef3a605fdc2bcec">anonymous{HexagonVectorCombine.cpp}::HexagonVectorCombine::concat</a>, <a href="/web-llvm/docs/api/namespaces/anonymous-constantfolding-cpp-/#a72190dad796891a1a5a59d64044000dc">anonymous{ConstantFolding.cpp}::ConstantFoldIntrinsicCall2</a>, <a href="/web-llvm/docs/api/namespaces/anonymous-constantfolding-cpp-/#aa8f5a312c9865602c873621adc9d8a18">anonymous{ConstantFolding.cpp}::ConstantFoldScalarCall1</a>, <a href="/web-llvm/docs/api/classes/llvm/pdb/pdbsymboltypefunctionsig/#a4db1dbc804f6844b395b9463e2e832a3">llvm::pdb::PDBSymbolTypeFunctionSig::dumpArgList</a>, <a href="/web-llvm/docs/api/classes/llvm/vpwidenevlrecipe/#a703a08e4f8a8f64b8be733d194070cd1">llvm::VPWidenEVLRecipe::execute</a>, <a href="/web-llvm/docs/api/classes/llvm/vpwidenintorfpinductionrecipe/#a98d8cca54a99e8b64eb406f898565323">llvm::VPWidenIntOrFpInductionRecipe::execute</a>, <a href="/web-llvm/docs/api/classes/llvm/vpwidenpointerinductionrecipe/#ac53a5d033ba641288b6e15344d880186">llvm::VPWidenPointerInductionRecipe::execute</a>, <a href="/web-llvm/docs/api/structs/anonymous-sifoldoperands-cpp-/foldcandidate/#a22926b4547ee17e802fe12e69ca53915">anonymous{SIFoldOperands.cpp}::FoldCandidate::FoldCandidate</a>, <a href="/web-llvm/docs/api/classes/llvm/instcombinerimpl/#a866883cec7ed781fcf1e9cda18b24f5b">llvm::InstCombinerImpl::foldCmpLoadFromIndexedGlobal</a>, <a href="/web-llvm/docs/api/classes/llvm/scalarevolution/#aef6d2bea715d1793e956f41ddeea2320">llvm::ScalarEvolution::getAddExpr</a>, <a href="/web-llvm/docs/api/classes/llvm/scalarevolution/#a69f32678ea46cdda0318c0be9bdb1c7e">llvm::ScalarEvolution::getAddRecExpr</a>, <a href="/web-llvm/docs/api/structs/llvm/aapotentialconstantvalues/#ac6c45f02f71621808dd33da72d73cb00">llvm::AAPotentialConstantValues::getAssumedConstant</a>, <a href="/web-llvm/docs/api/classes/llvm/addrspacecastoperator/#a29379deb012f61ae64a07f817a70d6cb">llvm::AddrSpaceCastOperator::getDestAddressSpace</a>, <a href="/web-llvm/docs/api/classes/llvm/bitcastoperator/#a439a00b49e8dc5825429ead24d587e3f">llvm::BitCastOperator::getDestTy</a>, <a href="/web-llvm/docs/api/classes/llvm/machineinstr/#a620b1d8de0e32491f106ddc997914153">llvm::MachineInstr::getFirst2LLTs</a>, <a href="/web-llvm/docs/api/classes/llvm/machineinstr/#a817d92911624542113807dc07a46bfb5">llvm::MachineInstr::getFirst2RegLLTs</a>, <a href="/web-llvm/docs/api/classes/llvm/machineinstr/#abeb0ed106bd6d33c0cf49a89083a74ad">llvm::MachineInstr::getFirst3LLTs</a>, <a href="/web-llvm/docs/api/classes/llvm/machineinstr/#a31012ec441c425a3eeb652d31ab0a8ab">llvm::MachineInstr::getFirst3RegLLTs</a>, <a href="/web-llvm/docs/api/classes/llvm/machineinstr/#ad2b80d7b9f05e663c35bd72cece6ebd7">llvm::MachineInstr::getFirst4LLTs</a>, <a href="/web-llvm/docs/api/classes/llvm/machineinstr/#a80edb692b5f12ebc13ea0c6558e2cc85">llvm::MachineInstr::getFirst4RegLLTs</a>, <a href="/web-llvm/docs/api/classes/llvm/machineinstr/#a2e82295f594d02e8290f214b5a4c3551">llvm::MachineInstr::getFirst5LLTs</a>, <a href="/web-llvm/docs/api/classes/llvm/machineinstr/#a1345402d2906eacc2db93c4bb59cf861">llvm::MachineInstr::getFirst5RegLLTs</a>, <a href="/web-llvm/docs/api/files/lib/lib/ir/constants-cpp/#a490cd638a7de440f2f3f6b2a26b4fa0b">getFPSequenceIfElementsMatch</a>, <a href="/web-llvm/docs/api/classes/anonymous-gvnsink-cpp-/instructionuseexpr/#a63343d7bd10f61ce837992a212b7f517">anonymous{GVNSink.cpp}::InstructionUseExpr::getHashValue</a>, <a href="/web-llvm/docs/api/classes/llvm/targettransforminfoimplcrtpbase/#a95442a0e0980e874df3bf77d6c8dee44">llvm::TargetTransformInfoImplCRTPBase&lt; T &gt;::getInstructionCost</a>, <a href="/web-llvm/docs/api/classes/llvm/basicttiimplbase/#a05184f6230f850d3f972f6d904bd2ef5">llvm::BasicTTIImplBase&lt; BasicTTIImpl &gt;::getIntrinsicInstrCost</a>, <a href="/web-llvm/docs/api/classes/llvm/scalarevolution/#ac3221ac3fcd879a1c716aa954837df79">llvm::ScalarEvolution::getMinMaxExpr</a>, <a href="/web-llvm/docs/api/classes/llvm/scalarevolution/#ad299b0f4378f644f67168c72c763716f">llvm::ScalarEvolution::getMulExpr</a>, <a href="/web-llvm/docs/api/classes/llvm/scevaddrecexpr/#a7e688afe102c3fa48ea49cb972a0f00c">llvm::SCEVAddRecExpr::getNumIterationsInRange</a>, <a href="/web-llvm/docs/api/namespaces/llvm/intrinsic/#a0cff8be0190d8e20b7cf13646f34afa2">llvm::Intrinsic::getOrInsertDeclaration</a>, <a href="/web-llvm/docs/api/classes/anonymous-m68kelfobjectwriter-cpp-/m68kelfobjectwriter/#a8715a150e0f35a58255f4cc042d9ff87">anonymous{M68kELFObjectWriter.cpp}::M68kELFObjectWriter::getRelocType</a>, <a href="/web-llvm/docs/api/classes/llvm/scalarevolution/#a4976a99a4f39b4daee84f4f60319df03">llvm::ScalarEvolution::getSequentialMinMaxExpr</a>, <a href="/web-llvm/docs/api/classes/llvm/memtransferbase/#aa4905f44616de7dcca8ce3d51685a60b">llvm::MemTransferBase&lt; BaseCL &gt;::getSourceAddressSpace</a>, <a href="/web-llvm/docs/api/classes/llvm/constantexpr/#af54e3db199b40160eaaba21e4e19c28f">llvm::ConstantExpr::getWithOperands</a>, <a href="/web-llvm/docs/api/classes/llvm/shufflevectorinst/#a6315811e3cc527c8f1ab15ae0c789b93">llvm::ShuffleVectorInst::increasesLength</a>, <a href="/web-llvm/docs/api/structs/anonymous-attributorattributes-cpp-/aavaluesimplifyimpl/#a5aaf0b4e889521266e9e87ec9a0511ce">anonymous{AttributorAttributes.cpp}::AAValueSimplifyImpl::initialize</a>, <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/vectorize/vplanrecipes-cpp/#a204934c6800bce8f4ce892221de4ebbe">interleaveVectors</a>, <a href="/web-llvm/docs/api/classes/llvm/intrinsiccostattributes/#a6760a5137f8e0ec21dbd7b99e61b52ed">llvm::IntrinsicCostAttributes::IntrinsicCostAttributes</a>, <a href="/web-llvm/docs/api/classes/llvm/landingpadinst/#a74e94530fdc21fe0a7eb5465437c980f">llvm::LandingPadInst::isCatch</a>, <a href="/web-llvm/docs/api/structs/llvm/object/elf-sym-impl/#ae6e51a4e24562a5ad4897cb500f96bf2">llvm::object::Elf_Sym_Impl&lt; ELFType&lt; E, Is64 &gt; &gt;::isCommon</a>, <a href="/web-llvm/docs/api/namespaces/llvm/hexagonmcinstrinfo/#a52c9eaaaa5bdf33fc16541cff0a6cae4">llvm::HexagonMCInstrInfo::isCompound</a>, <a href="/web-llvm/docs/api/classes/llvm/shufflevectorinst/#a157632c803f214768bc5f6bf5e68434e">llvm::ShuffleVectorInst::isExtractSubvectorMask</a>, <a href="/web-llvm/docs/api/classes/llvm/landingpadinst/#a794866f5c0f6877de0b1dd863ceaf93e">llvm::LandingPadInst::isFilter</a>, <a href="/web-llvm/docs/api/namespaces/llvm/hexagonmcinstrinfo/#a4f9d7bda03b5f1a77b715e78ee067ee9">llvm::HexagonMCInstrInfo::isHVX</a>, <a href="/web-llvm/docs/api/classes/llvm/shufflevectorinst/#ace370e43170f9080834219e96dc1f8cc">llvm::ShuffleVectorInst::isIdentity</a>, <a href="/web-llvm/docs/api/classes/llvm/shufflevectorinst/#a6216fec0e57bbfd308e943f3da488ebd">llvm::ShuffleVectorInst::isInsertSubvectorMask</a>, <a href="/web-llvm/docs/api/classes/anonymous-x86interleavedaccess-cpp-/x86interleavedaccessgroup/#ae769158e04d7d2df19b436d90e02bb85">anonymous{X86InterleavedAccess.cpp}::X86InterleavedAccessGroup::isSupported</a>, <a href="/web-llvm/docs/api/groups/llvmcobject/#ga9325ccf978c315587e6dfe55e4c3758a">LLVMBinaryGetType</a>, <a href="/web-llvm/docs/api/groups/llvmccorevaluegeneral/#ga12179f46b79de8436852a4189d4451e0">LLVMTypeOf</a>, <a href="/web-llvm/docs/api/classes/llvm/aarch64targetlowering/#ac66d3f15510c7402f2a85a87c69f1603">llvm::AArch64TargetLowering::lowerDeinterleaveIntrinsicToLoad</a>, <a href="/web-llvm/docs/api/classes/llvm/riscvtargetlowering/#adcc5d5714e94674aee99aacd991d2b4a">llvm::RISCVTargetLowering::lowerDeinterleaveIntrinsicToLoad</a>, <a href="/web-llvm/docs/api/classes/llvm/armtargetlowering/#ad190bc43c7fc8555debc7228fc5364b9">llvm::ARMTargetLowering::lowerInterleavedLoad</a>, <a href="/web-llvm/docs/api/classes/llvm/riscvtargetlowering/#a74b80978e3ab87994e9361f4bbc767dd">llvm::RISCVTargetLowering::lowerInterleavedLoad</a>, <a href="/web-llvm/docs/api/classes/llvm/aarch64targetlowering/#ac2d9e284d06499be56d61b876e86dc8a">llvm::AArch64TargetLowering::lowerInterleaveIntrinsicToStore</a>, <a href="/web-llvm/docs/api/classes/llvm/riscvtargetlowering/#a22c6a7a1925a0177519e33d49ba91cea">llvm::RISCVTargetLowering::lowerInterleaveIntrinsicToStore</a>, <a href="/web-llvm/docs/api/classes/anonymous-x86interleavedaccess-cpp-/x86interleavedaccessgroup/#a57d756a0a03371c31155a702e0ba4d85">anonymous{X86InterleavedAccess.cpp}::X86InterleavedAccessGroup::lowerIntoOptimizedSequence</a>, <a href="/web-llvm/docs/api/structs/anonymous-attributorattributes-cpp-/aamemorybehaviorargument/#a40a41eccaeafb327b27a589542a5f106">anonymous{AttributorAttributes.cpp}::AAMemoryBehaviorArgument::manifest</a>, <a href="/web-llvm/docs/api/namespaces/llvm/fuzzerop/#a2bff55a07291d47843ff3e4a1548c154">llvm::fuzzerop::matchFirstLengthWAnyType</a>, <a href="/web-llvm/docs/api/namespaces/llvm/fuzzerop/#ad3d7a249e54c1fd78688913ffcc2e899">llvm::fuzzerop::matchFirstType</a>, <a href="/web-llvm/docs/api/files/lib/lib/fuzzmutate/operations-cpp/#ad441fdf76eac1465a3e66ea73f40bdc6">matchScalarInAggregate</a>, <a href="/web-llvm/docs/api/namespaces/llvm/fuzzerop/#a764af34b63a5c94bdfc643668bb4c885">llvm::fuzzerop::matchScalarOfFirstType</a>, <a href="/web-llvm/docs/api/namespaces/llvm/fuzzerop/#afffaaa44175e2eeebcc852c80fb03c40">llvm::fuzzerop::matchSecondType</a>, <a href="/web-llvm/docs/api/classes/llvm/machineirbuilder/#a0f2bb4d63ad6914f3783967bf881a14b">llvm::MachineIRBuilder::materializePtrAdd</a>, <a href="/web-llvm/docs/api/classes/llvm/valuelatticeelement/#aceaa5f442dd3df34f51799f2999d237e">llvm::ValueLatticeElement::mergeIn</a>, <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/scalar/simplifycfgpass-cpp/#aec97a6e447a45c9027b71a487f5732ec">performBlockTailMerging</a>, <a href="/web-llvm/docs/api/classes/llvm/vpreplicaterecipe/#a202af2dd775be9a857e92e8ca6190b4f">llvm::VPReplicateRecipe::print</a>, <a href="/web-llvm/docs/api/classes/anonymous-aarch64arm64eccalllowering-cpp-/aarch64arm64eccalllowering/#a7b0a136ac6a10743ef5d3cbc1ee0190e">anonymous{AArch64Arm64ECCallLowering.cpp}::AArch64Arm64ECCallLowering::runOnModule</a>, <a href="/web-llvm/docs/api/structs/llvm/runtimecheckingptrgroup/#a4b4d56d5d22cdc51b3d993501d57816b">llvm::RuntimeCheckingPtrGroup::RuntimeCheckingPtrGroup</a>, <a href="/web-llvm/docs/api/structs/llvm/object/elf-sym-impl/#a5e627a99cdc532223db85e31146fdc53">llvm::object::Elf_Sym_Impl&lt; ELFType&lt; E, Is64 &gt; &gt;::setBinding</a>, <a href="/web-llvm/docs/api/classes/llvm/phinode/#a88cdefb709309eddc6e5daca0be6a7b4">llvm::PHINode::setIncomingValue</a>, <a href="/web-llvm/docs/api/classes/llvm/memtransferbase/#a5127b9bac226020bc936ecdedcf72e0d">llvm::MemTransferBase&lt; BaseCL &gt;::setSource</a>, <a href="/web-llvm/docs/api/structs/llvm/object/elf-rel-impl-441322f49503dee2ae87a34528a5e21a/#a8ad0de39b91a24e1ca6b1c9da5976df2">llvm::object::Elf_Rel_Impl&lt; ELFType&lt; Endianness, false &gt;, false &gt;::setSymbol</a>, <a href="/web-llvm/docs/api/structs/llvm/object/elf-rel-impl-9e9bb875b5b3f76ac1dc313ded5403d0/#a6e93e0ecd6afc3e9bc4686669b816980">llvm::object::Elf_Rel_Impl&lt; ELFType&lt; Endianness, true &gt;, false &gt;::setSymbol</a>, <a href="/web-llvm/docs/api/classes/llvm/memsetbase/#a5145ecc9510133b8db74dfa22bbf5d3d">llvm::MemSetBase&lt; BaseCL &gt;::setValue</a>, <a href="/web-llvm/docs/api/files/lib/lib/analysis/instructionsimplify-cpp/#aa6498365e4fa2bc006fc4116b4b9b990">simplifyFPOp</a>, <a href="/web-llvm/docs/api/files/lib/lib/analysis/instructionsimplify-cpp/#aab8aaa8e44e0609f7d3e9ae822f11f7e">simplifyGEPInst</a>, <a href="/web-llvm/docs/api/namespaces/anonymous-constantfolding-cpp-/#a4fc5dce2b300d02414f7b8a99d93d300">anonymous{ConstantFolding.cpp}::SymbolicallyEvaluateGEP</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/arm/mvelaneinterleavingpass-cpp/#a9268090caaf5e5a96fa54337cb50f47b">tryInterleave</a>, <a href="/web-llvm/docs/api/files/lib/lib/ir/autoupgrade-cpp/#a4ce4b835cffc5fa4123fe82f5f39cf97">upgradeAArch64IntrinsicCall</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a085e92ed481e12744fdf1740b4751327">llvm::UpgradeIntrinsicCall</a>, <a href="/web-llvm/docs/api/files/lib/lib/ir/autoupgrade-cpp/#af61729415c4cfec66c791cd52a532eb9">upgradeX86IntrinsicCall</a>, <a href="/web-llvm/docs/api/files/lib/lib/fuzzmutate/operations-cpp/#acd02b84e30b7fa3fa475f938e522eb88">validExtractValueIndex</a>, <a href="/web-llvm/docs/api/files/lib/lib/fuzzmutate/operations-cpp/#ae2afbc4899c3d5a6034358e288eaa7c6">validInsertValueIndex</a>, <a href="/web-llvm/docs/api/files/lib/lib/fuzzmutate/operations-cpp/#a1fdfe91f1f9e82078936d0cde2af8a3f">validShuffleVectorIndex</a>, <a href="/web-llvm/docs/api/classes/anonymous-amdgpulowerbufferfatpointers-cpp-/splitptrstructs/#a6e52c5d20a66f0c24d90fcd6d2eb7916">anonymous{AMDGPULowerBufferFatPointers.cpp}::SplitPtrStructs::visitInsertElementInst</a>, <a href="/web-llvm/docs/api/classes/llvm/instcombinerimpl/#a7af99fa2202fcc7db245865dd1bcec1f">llvm::InstCombinerImpl::visitLandingPadInst</a>, <a href="/web-llvm/docs/api/classes/llvm/instcombinerimpl/#a197424adbab353be4587e6dfaee445e3">llvm::InstCombinerImpl::visitLShr</a>, <a href="/web-llvm/docs/api/classes/anonymous-amdgpulowerbufferfatpointers-cpp-/splitptrstructs/#ad2f13773cdca3ddf4fc605ebd52d3044">anonymous{AMDGPULowerBufferFatPointers.cpp}::SplitPtrStructs::visitShuffleVectorInst</a> and <a href="/web-llvm/docs/api/classes/llvm/instcombinerimpl/#a91100900b6eb1ae18127f1e1f8f8a40e">llvm::InstCombinerImpl::visitSwitchInst</a>.</p>

</div>
</div>

</div>

<hr/>

<p class="doxyGeneratedBy">Generated via <a href="https://github.com/xpack/doxygen2docusaurus">doxygen2docusaurus</a> by <a href="https://www.doxygen.nl">Doxygen</a> 1.15.0.</p>

</div>
