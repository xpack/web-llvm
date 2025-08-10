---

# DO NOT EDIT!
# Automatically generated via doxygen2docusaurus by Doxygen.

slug: /api/files/lib/lib/transforms/lib/transforms/objcarc/provenanceanalysisevaluator-cpp
custom_edit_url: null
toc_max_heading_level: 4
keywords:
  - doxygen
  - reference
  - file

---

<div class="doxyPage">

# `ProvenanceAnalysisEvaluator.cpp` File



## Included Headers

<div class="doxyIncludesList">#include "<a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/objcarc/provenanceanalysis-h">ProvenanceAnalysis.h</a>"
#include "<a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/transforms/objcarc-h">llvm/Transforms/ObjCARC.h</a>"
#include "<a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/adt/setvector-h">llvm/ADT/SetVector.h</a>"
#include "<a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/analysis/aliasanalysis-h">llvm/Analysis/AliasAnalysis.h</a>"
#include "<a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/ir/function-h">llvm/IR/Function.h</a>"
#include "<a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/ir/institerator-h">llvm/IR/InstIterator.h</a>"
#include "<a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/support/raw-ostream-h">llvm/Support/raw_ostream.h</a>"
</div>

## Functions Index

<table class="doxyMembersIndex">

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">static <a href="/web-llvm/docs/api/classes/llvm/stringref">StringRef</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a2ee79648e8bce3ddbb26358ff10e3e82">getName</a> (Value *V)</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">static void</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a0ee64ae4a4584421c26f09361f6bd0ec">insertIfNamed</a> (SetVector&lt; Value * &gt; &amp;Values, Value *V)</td>
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

### getName() {#a2ee79648e8bce3ddbb26358ff10e3e82}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">StringRef getName (<a href="/web-llvm/docs/api/classes/llvm/value">Value</a> * V)</td>
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



<p>Definition at line 20 of file <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/objcarc/provenanceanalysisevaluator-cpp">ProvenanceAnalysisEvaluator.cpp</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/classes/llvm/ssaupdaterbulk/#a95c1eb0b213b4b0f797053144466f06d">llvm::SSAUpdaterBulk::AddUse</a>, <a href="/web-llvm/docs/api/classes/llvm/blockdatat/#aae656f290bebfcd62ee9f52271e26e4d">llvm::BlockDataT&lt; T &gt;::BlockDataT</a>, <a href="/web-llvm/docs/api/classes/llvm/blockdatat/#a9beb21ec4450e7770f1b6c33ce522ddb">llvm::BlockDataT&lt; T &gt;::BlockDataT</a>, <a href="/web-llvm/docs/api/classes/llvm/btftypederived/#aafc0c2b5c27c6910122cc4c6eaec7de3">llvm::BTFTypeDerived::BTFTypeDerived</a>, <a href="/web-llvm/docs/api/classes/llvm/vpbasicblock/#a6516e17cd03806dc29350794ce78ef42">llvm::VPBasicBlock::clone</a>, <a href="/web-llvm/docs/api/classes/llvm/vpregionblock/#a0001ec4686be34ad7e56cb0798bef1b0">llvm::VPRegionBlock::clone</a>, <a href="/web-llvm/docs/api/structs/llvm/attributor/#a45f6cbf770c1d990014838ceb300e936">llvm::Attributor::createShallowWrapper</a>, <a href="/web-llvm/docs/api/classes/llvm/orc/jitdylib/#a574566a131a23ad62ff846ac8a7901f4">llvm::orc::JITDylib::dump</a>, <a href="/web-llvm/docs/api/classes/llvm/atomicinfo/#a5df935e7c87e3e1dc8b3d7e1870ee1c9">llvm::AtomicInfo::EmitAtomicLoadLibcall</a>, <a href="/web-llvm/docs/api/classes/llvm/vpbasicblock/#aa45aa859516b55fd0d010570b3f16170">llvm::VPBasicBlock::executeRecipes</a>, <a href="/web-llvm/docs/api/classes/anonymous-erlanggcprinter-cpp-/erlanggcprinter/#a574679a34186d5db3a7b14b0ce5c5078">anonymous{ErlangGCPrinter.cpp}::ErlangGCPrinter::finishAssembly</a>, <a href="/web-llvm/docs/api/classes/anonymous-ocamlgcprinter-cpp-/ocamlgcmetadataprinter/#a6abb5b979094dd3eba1a0375a96e365a">anonymous{OcamlGCPrinter.cpp}::OcamlGCMetadataPrinter::finishAssembly</a>, <a href="/web-llvm/docs/api/classes/llvm/hexagoninstrinfo/#abbab66c4fbf9fd6512efa4efae8f69ef">llvm::HexagonInstrInfo::genAllInsnTimingClasses</a>, <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/scalar/constraintelimination-cpp/#a7ea4fb4d6b0198f2b6eac325a8d93031">generateReproducer</a>, <a href="/web-llvm/docs/api/namespaces/llvm/csky/#ae0afc37c0fe40d24d2021c7eba023b2a">llvm::CSKY::getArchName</a>, <a href="/web-llvm/docs/api/structs/anonymous-amdgpuattributor-cpp-/aaamdsizerangeattribute/#a6cca267d184aa0f88f69f9423e2bd573">anonymous{AMDGPUAttributor.cpp}::AAAMDSizeRangeAttribute::getAsStr</a>, <a href="/web-llvm/docs/api/namespaces/llvm/intrinsic/#aa1731508126b77035ab3ba9d71d5374b">llvm::Intrinsic::getDeclarationIfExists</a>, <a href="/web-llvm/docs/api/classes/llvm/object/archive/child/#a22ece0b78ccffb215a68d44b94b46e2f">llvm::object::Archive::Child::getFullName</a>, <a href="/web-llvm/docs/api/structs/llvm/itaniumpartialdemangler/#a2effd15853bfffbeec4d08451f1fa81c">llvm::ItaniumPartialDemangler::getFunctionBaseName</a>, <a href="/web-llvm/docs/api/structs/llvm/itaniumpartialdemangler/#aea51879b3b2822d1c0f74c71cff9bc2e">llvm::ItaniumPartialDemangler::getFunctionDeclContextName</a>, <a href="/web-llvm/docs/api/structs/llvm/itaniumpartialdemangler/#a483d97b0a650319638b62209a03b1dea">llvm::ItaniumPartialDemangler::getFunctionName</a>, <a href="/web-llvm/docs/api/classes/llvm/object/archive/child/#a7fa0bfbc8489a0b3472e2dd834e03c80">llvm::object::Archive::Child::getMemoryBufferRef</a>, <a href="/web-llvm/docs/api/classes/llvm/regionbase/#a1021f58f09c63db71a8b20b187d9d1c3">llvm::RegionBase&lt; Tr &gt;::getNameStr</a>, <a href="/web-llvm/docs/api/classes/llvm/object/archive/child/#a137ad5829c3f2470a0da63800c59385e">llvm::object::Archive::Child::getNext</a>, <a href="/web-llvm/docs/api/namespaces/llvm/intrinsic/#a0cff8be0190d8e20b7cf13646f34afa2">llvm::Intrinsic::getOrInsertDeclaration</a>, <a href="/web-llvm/docs/api/classes/llvm/riscvtargetlowering/#abc0c3e45d7d6be3fd7f5038a7e9e16de">llvm::RISCVTargetLowering::getTgtMemIntrinsic</a>, <a href="/web-llvm/docs/api/classes/llvm/vfs/detail/inmemorydirectory/#a344f873a748fb3ee5a781af697dba6b3">llvm::vfs::detail::InMemoryDirectory::InMemoryDirectory</a>, <a href="/web-llvm/docs/api/classes/llvm/vfs/detail/inmemoryfile/#a68bc45ba833afa528bcf4ad1d3893796">llvm::vfs::detail::InMemoryFile::InMemoryFile</a>, <a href="/web-llvm/docs/api/classes/llvm/machinetracemetrics/ensemble/#a063217bcbb8b81adfdc88feb1a52ddcb">llvm::MachineTraceMetrics::Ensemble::invalidate</a>, <a href="/web-llvm/docs/api/structs/llvm/itaniumpartialdemangler/#adc2764e156977abc23c40ce1344427ed">llvm::ItaniumPartialDemangler::isCtorOrDtor</a>, <a href="/web-llvm/docs/api/classes/objcprotoname/#a0dd966c7b564bde7037477b4fa2f3140">ObjCProtoName::isObjCObject</a>, <a href="/web-llvm/docs/api/classes/llvm/hexagoninstrinfo/#a53372200df2c3350a7b61c797e578be7">llvm::HexagonInstrInfo::isValidOffset</a>, <a href="/web-llvm/docs/api/structs/llvm/targetexttypekeyinfo/keyty/#aaad7efe520c4e36e3946c4ab50277907">llvm::TargetExtTypeKeyInfo::KeyTy::KeyTy</a>, <a href="/web-llvm/docs/api/groups/llvmcobject/#ga4a57d024c433cf88a0da658ea1627093">LLVMGetSectionName</a>, <a href="/web-llvm/docs/api/groups/llvmcobject/#gace82127e9d25bb0a018ea2d621fda00a">LLVMGetSymbolName</a>, <a href="/web-llvm/docs/api/classes/llvm/runtimedyldmacho/#ab606ca40d5870295837712aa2056f90e">llvm::RuntimeDyldMachO::populateIndirectSymbolPointersSection</a>, <a href="/web-llvm/docs/api/structs/llvm/abstractattribute/#adca255bafe3002c3988f715a5179c2c1">llvm::AbstractAttribute::print</a>, <a href="/web-llvm/docs/api/classes/llvm/comdat/#a56cb601c486724c2c35a0c99db7a6c1e">llvm::Comdat::print</a>, <a href="/web-llvm/docs/api/classes/llvm/machinetracemetrics/ensemble/#ac7672297acdaf5409f8e9c116fb4b207">llvm::MachineTraceMetrics::Ensemble::print</a>, <a href="/web-llvm/docs/api/classes/llvm/sandboxir/passmanager/#a3f75ee2e53d1aab594375a3345fbddea">llvm::sandboxir::PassManager&lt; ParentPass, ContainedPass &gt;::print</a>, <a href="/web-llvm/docs/api/classes/llvm/vpbasicblock/#abaf6ac959836f909c24a39b8913ec22f">llvm::VPBasicBlock::print</a>, <a href="/web-llvm/docs/api/classes/llvm/vplan/#adef61e4746c6f7f0e2e75da307e77c42">llvm::VPlan::print</a>, <a href="/web-llvm/docs/api/classes/llvm/vpregionblock/#ab02924e690f0a12f4b58c4e40e4ead42">llvm::VPRegionBlock::print</a>, <a href="/web-llvm/docs/api/classes/llvm/sandboxir/passmanager/#a14ca239a766dfe1029be1c5838a13ffb">llvm::sandboxir::PassManager&lt; ParentPass, ContainedPass &gt;::printPipeline</a>, <a href="/web-llvm/docs/api/classes/llvm/runtimedyldimpl/#a13ed1aa385513404b0d2bcad53502041">llvm::RuntimeDyldImpl::reassignSectionAddress</a>, <a href="/web-llvm/docs/api/structs/remarkinfo/#a1b5cf8ba776df7b10906174971d7225e">RemarkInfo::RemarkInfo</a>, <a href="/web-llvm/docs/api/structs/llvm/paevalpass/#a7f0dda30879f62ea4eefdc53cfbb0e1d">llvm::PAEvalPass::run</a>, <a href="/web-llvm/docs/api/classes/llvm/vpbasicblock/#a9b75fcd70de89596b8f04904aa42e2cd">llvm::VPBasicBlock::splitAt</a>, <a href="/web-llvm/docs/api/structs/anonymous-amdgpuattributor-cpp-/aaamdmaxnumworkgroups/#a78b300aeab76328894717218a55b32d1">anonymous{AMDGPUAttributor.cpp}::AAAMDMaxNumWorkgroups::updateImpl</a>, <a href="/web-llvm/docs/api/structs/anonymous-amdgpuattributor-cpp-/aaamdwavespereu/#a6e7ec06ac86c48e6d651e37817ed7359">anonymous{AMDGPUAttributor.cpp}::AAAMDWavesPerEU::updateImpl</a>, <a href="/web-llvm/docs/api/structs/anonymous-amdgpuattributor-cpp-/aauniformworkgroupsizefunction/#a8aba32ec039ca723fa00f67c6f462cfa">anonymous{AMDGPUAttributor.cpp}::AAUniformWorkGroupSizeFunction::updateImpl</a>, <a href="/web-llvm/docs/api/structs/anonymous-attributorattributes-cpp-/aadenormalfpmathfunction/#a40c2cb36cf0ed7535884f2e86de3aa55">anonymous{AttributorAttributes.cpp}::AADenormalFPMathFunction::updateImpl</a>, <a href="/web-llvm/docs/api/structs/anonymous-amdgpuattributor-cpp-/aaamdsizerangeattribute/#a29bd4b6b1ce02623406f833daf4668cc">anonymous{AMDGPUAttributor.cpp}::AAAMDSizeRangeAttribute::updateImplImpl</a>, <a href="/web-llvm/docs/api/classes/llvm/function/#aeac4ca2dcb29682747f7d637b47c8327">llvm::Function::viewCFG</a> and <a href="/web-llvm/docs/api/classes/llvm/selectiondag/#a6ec02a7ebbe56dfc864242c77c5a194f">llvm::SelectionDAG::viewGraph</a>.</p>

</div>
</div>

### insertIfNamed() {#a0ee64ae4a4584421c26f09361f6bd0ec}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void insertIfNamed (<a href="/web-llvm/docs/api/classes/llvm/setvector">SetVector</a>&lt; <a href="/web-llvm/docs/api/classes/llvm/value">Value</a> * &gt; &amp; Values, <a href="/web-llvm/docs/api/classes/llvm/value">Value</a> * V)</td>
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



<p>Definition at line 27 of file <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/objcarc/provenanceanalysisevaluator-cpp">ProvenanceAnalysisEvaluator.cpp</a>.</p>


<p>Reference <a href="/web-llvm/docs/api/classes/llvm/setvector/#af34eb71cc483e84d2eca80575cb9ccde">llvm::SetVector&lt; T, Vector, Set, N &gt;::insert</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/structs/llvm/paevalpass/#a7f0dda30879f62ea4eefdc53cfbb0e1d">llvm::PAEvalPass::run</a>.</p>

</div>
</div>

</div>

<hr/>

<p class="doxyGeneratedBy">Generated via <a href="https://xpack.github.io/doxygen2docusaurus">doxygen2docusaurus</a> 2.0.0 by <a href="https://www.doxygen.nl">Doxygen</a> 1.15.0.</p>

</div>
