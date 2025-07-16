---

# DO NOT EDIT!
# Automatically generated via doxygen2docusaurus by Doxygen.

slug: /api/files/lib/lib/target/lib/target/aarch64/smeabipass-cpp
custom_edit_url: null
toc_max_heading_level: 4
keywords:
  - doxygen
  - reference
  - file

---

<div class="doxyPage">

# The `SMEABIPass.cpp` File Reference



## Included Headers

<div class="doxyIncludesList">#include "<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64-h">AArch64.h</a>"
#include "<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/lib/target/aarch64/utils/aarch64smeattributes-h">Utils/AArch64SMEAttributes.h</a>"
#include "<a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/adt/stringref-h">llvm/ADT/StringRef.h</a>"
#include "<a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/ir/irbuilder-h">llvm/IR/IRBuilder.h</a>"
#include "<a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/ir/instructions-h">llvm/IR/Instructions.h</a>"
#include "llvm/IR/IntrinsicsAArch64.h"
#include "<a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/ir/llvmcontext-h">llvm/IR/LLVMContext.h</a>"
#include "<a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/ir/module-h">llvm/IR/Module.h</a>"
#include "<a href="/web-llvm/docs/api/files/include/include/llvm/initializepasses-h">llvm/InitializePasses.h</a>"
#include "<a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/transforms/include/llvm/transforms/utils/cloning-h">llvm/Transforms/Utils/Cloning.h</a>"
</div>

## Namespaces Index

<table class="doxyMembersIndex">

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">namespace</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="/web-llvm/docs/api/namespaces/anonymous-smeabipass-cpp-">anonymous{SMEABIPass.cpp}</a></td>
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

## Classes Index

<table class="doxyMembersIndex">

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">struct</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="/web-llvm/docs/api/structs/anonymous-smeabipass-cpp-/smeabi">SMEABI</a></td>
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

## Functions Index

<table class="doxyMembersIndex">

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">void</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a925bbfb44898a7e8da7d6170278aaf71">emitTPIDR2Save</a> (Module *M, IRBuilder&lt;&gt; &amp;Builder, bool ZT0IsUndef=false)</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">static <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> char *</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a8f8f80d37794cde9472343e4487ba3eb">name</a> = "SME ABI Pass"</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ad78e062f62e0d6e453941fb4ca843e4d">DEBUG_TYPE</a>&nbsp;&nbsp;&nbsp;"aarch64-sme-abi"</td>
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

### emitTPIDR2Save() {#a925bbfb44898a7e8da7d6170278aaf71}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void emitTPIDR2Save (<a href="/web-llvm/docs/api/classes/llvm/module">Module</a> * M, <a href="/web-llvm/docs/api/classes/llvm/irbuilder">IRBuilder</a>&lt;&gt; &amp; Builder, bool ZT0IsUndef=false)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 57 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/smeabipass-cpp">SMEABIPass.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/namespaces/llvm/callingconv/#ac6aa1387c4375260e2468eb5a77fdb4ca7c23dce1e95fc36e9d2c168f9e036cc7">llvm::CallingConv::AArch64_SME_ABI_Support_Routines_PreserveMost_From_X0</a>, <a href="/web-llvm/docs/api/classes/llvm/attributelist/#a54ec2da7f0fb48a9208234c425f83ea6">llvm::AttributeList::addFnAttribute</a>, <a href="/web-llvm/docs/api/classes/llvm/irbuilderbase/#ab086c5b9f9563eda0cdd703f454e041e">llvm::IRBuilderBase::CreateCall</a>, <a href="/web-llvm/docs/api/classes/llvm/attribute/#a43708098bd7085788a680fd02f47c750">llvm::Attribute::get</a>, <a href="/web-llvm/docs/api/classes/llvm/functiontype/#af8be7844c269f201ebcee1e15048c378">llvm::FunctionType::get</a>, <a href="/web-llvm/docs/api/classes/llvm/function/#a21075305f0e463b24aafc2fb99514ace">llvm::Function::getFunctionType</a>, <a href="/web-llvm/docs/api/classes/llvm/irbuilderbase/#a73f286a780fbb8c82c0a8574540719ea">llvm::IRBuilderBase::getInt64</a>, <a href="/web-llvm/docs/api/namespaces/llvm/intrinsic/#a0cff8be0190d8e20b7cf13646f34afa2">llvm::Intrinsic::getOrInsertDeclaration</a> and <a href="/web-llvm/docs/api/classes/llvm/irbuilderbase/#ad0243f1634f75e231041023ffaa8501a">llvm::IRBuilderBase::getVoidTy</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Variables

### name {#a8f8f80d37794cde9472343e4487ba3eb}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">const char* name = "SME ABI Pass"</td>
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



<p>Definition at line 46 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/smeabipass-cpp">SMEABIPass.cpp</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/files/lib/lib/support/lib/support/rpmalloc/rpmalloc-c/#a66c4be5ac967e1374b25eb8ac80f68d9">_rpmalloc_set_name</a>, <a href="/web-llvm/docs/api/namespaces/llvm/object/#a2582ad4e03989cb2e2712ae5ddf5e2a9">llvm::object::applyNameType</a>, <a href="/web-llvm/docs/api/structs/llvm/ltocodegenerator/#a933d031a629f7261df21829fbea78f94">llvm::LTOCodeGenerator::compileOptimized</a>, <a href="/web-llvm/docs/api/structs/anonymous-memorysanitizer-cpp-/memorysanitizervisitor/#a6c2f0057515e3f4b8e14cfb9dcb789ae">anonymous{MemorySanitizer.cpp}::MemorySanitizerVisitor::convertToBool</a>, <a href="/web-llvm/docs/api/classes/llvm/pdb/diarawsymbol/#afc40184fefae68d8c008089f04a0a0bc">llvm::pdb::DIARawSymbol::dump</a>, <a href="/web-llvm/docs/api/classes/llvm/gsym/outputaggregator/#a987b74f13eb2c94d22fb702c55b55527">llvm::gsym::OutputAggregator::EnumerateResults</a>, <a href="/web-llvm/docs/api/classes/llvm/outputcategoryaggregator/#a510c2589de8e9d00cebbede77e5c9f30">llvm::OutputCategoryAggregator::EnumerateResults</a>, <a href="/web-llvm/docs/api/namespaces/llvm/mips16hardfloatinfo/#a69fe9395c105f669ee4e8e7b03b4c3ca">llvm::Mips16HardFloatInfo::findFuncSignature</a>, <a href="/web-llvm/docs/api/classes/llvm/object/archive/#ad6942d34da0ae42a687cccd3e4b4a7f3">llvm::object::Archive::findSym</a>, <a href="/web-llvm/docs/api/classes/llvm/cl/generic-parser-base/genericoptioninfo/#a214f5c8166fad66fe65a998662e6c2db">llvm::cl::generic_parser_base::GenericOptionInfo::GenericOptionInfo</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/lib/target/amdgpu/utils/amdkernelcodetutils-cpp/#af84e76651e34842ce3d8f63acb485b42">get_amd_kernel_code_t_FieldIndex</a>, <a href="/web-llvm/docs/api/classes/llvm/nvptxregisterinfo/#ae271370eae878e78d2bad43aa2d68e1d">llvm::NVPTXRegisterInfo::getDwarfRegNum</a>, <a href="/web-llvm/docs/api/classes/llvm/sys/process/#a8806fc38b760a88a96d5d7fb67de545f">llvm::sys::Process::GetEnv</a>, <a href="/web-llvm/docs/api/classes/llvm/object/coffimportfile/#aae96e0d873c421f268163eb04aa27b72">llvm::object::COFFImportFile::getExportName</a>, <a href="/web-llvm/docs/api/classes/llvm/loongarchmcexpr/#a66cc3e0b06526eb09333e4c407425c2a">llvm::LoongArchMCExpr::getVariantKindForName</a>, <a href="/web-llvm/docs/api/classes/llvm/riscvmcexpr/#af71a001d22873f5487311a525ee014d7">llvm::RISCVMCExpr::getVariantKindForName</a>, <a href="/web-llvm/docs/api/classes/llvm/xtensamcexpr/#a1f6ac568faece433f8a855bcb5397ff9">llvm::XtensaMCExpr::getVariantKindForName</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/sveintrinsicopts-cpp/#a2bb87eb1bcbc74783a83ae945eb8fa36">INITIALIZE_PASS_DEPENDENCY</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/x86/lib/target/x86/disassembler/x86disassembler-cpp/#a652270ec0bdb03b5a7f934524412aa7f">is64Bit</a>, <a href="/web-llvm/docs/api/classes/llvm/mcasmbackend/#a919e61fbc03b7b8a1660337897db7094">llvm::MCAsmBackend::isDarwinCanonicalPersonality</a>, <a href="/web-llvm/docs/api/classes/llvm/xtensatargetlowering/#ab0d338abd21b7cc0711741b492330a9d">llvm::XtensaTargetLowering::LowerCall</a>, <a href="/web-llvm/docs/api/groups/llvmclto/#gadfde0ad97850e1479009556404f5bc61">lto_codegen_compile_to_file</a>, <a href="/web-llvm/docs/api/structs/llvm/ltomodule/#a506f8e95d7b36007cf41322e49e3668c">llvm::LTOModule::makeBuffer</a>, <a href="/web-llvm/docs/api/classes/llvm/mcgendwarflabelentry/#a1f902c7cbb6e98bc37647201920768ca">llvm::MCGenDwarfLabelEntry::MCGenDwarfLabelEntry</a>, <a href="/web-llvm/docs/api/classes/llvm/gsym/outputaggregator/#af65bf7475eed416d9de9a4a5e5e5ad2f">llvm::gsym::OutputAggregator::Merge</a>, <a href="/web-llvm/docs/api/classes/llvm/cl/parser/optioninfo/#a987453299a7a73498e737e9a9f00b24c">llvm::cl::parser&lt; DataType &gt;::OptionInfo::OptionInfo</a>, <a href="/web-llvm/docs/api/classes/llvm/elfattributeparser/#abf992f403d584a1d6b24de79a3a658b5">llvm::ELFAttributeParser::parseStringAttribute</a>, <a href="/web-llvm/docs/api/classes/llvm/sparcmcexpr/#a8f8493d80b8e10f21a7d4ea16ac003ea">llvm::SparcMCExpr::parseVariantKind</a>, <a href="/web-llvm/docs/api/classes/llvm/vemcexpr/#a34980fe75ddfddc6b82e729a114d63ee">llvm::VEMCExpr::parseVariantKind</a>, <a href="/web-llvm/docs/api/classes/llvm/passinfo/#a9120a17cdcf88826fb07b59bc7db1b20">llvm::PassInfo::PassInfo</a>, <a href="/web-llvm/docs/api/classes/llvm/readyqueue/#aac7f48e9f4ecf77fe560c016c853edf9">llvm::ReadyQueue::ReadyQueue</a>, <a href="/web-llvm/docs/api/classes/llvm/scevexpander/#a86fc272b516cc390141710ff1b16b74b">llvm::SCEVExpander::SCEVExpander</a>, <a href="/web-llvm/docs/api/classes/llvm/sectionentry/#a1ad97e5dd44927d49dffdc1a40229fec">llvm::SectionEntry::SectionEntry</a>, <a href="/web-llvm/docs/api/groups/llvmctlto/#ga04d8f6924e666ac75b707c5159935056">thinlto_codegen_add_cross_referenced_symbol</a>, <a href="/web-llvm/docs/api/groups/llvmctlto/#gaac473108a947da1a6b02d8bb32d50e23">thinlto_codegen_add_must_preserve_symbol</a>, <a href="/web-llvm/docs/api/namespaces/llvm/dwarf/#a819d2b14dff40e21d0706c3bc5cc90b4">llvm::dwarf::toDW_LANG</a>, <a href="/web-llvm/docs/api/classes/anonymous-elfobjectwriter-cpp-/symboltablewriter/#a9b91d63de477829a841c50e79b34f52a">anonymous{ELFObjectWriter.cpp}::SymbolTableWriter::writeSymbol</a> and <a href="/web-llvm/docs/api/structs/llvm/ltomodule/#acacfc05f60d5fb8b67833cca46725781">llvm::LTOModule::~LTOModule</a>.</p>

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
<td class="doxyMemberName">#define DEBUG_TYPE&nbsp;&nbsp;&nbsp;"aarch64-sme-abi"</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 28 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/smeabipass-cpp">SMEABIPass.cpp</a>.</p>

</div>
</div>

</div>

<hr/>

<p class="doxyGeneratedBy">Generated via <a href="https://github.com/xpack/doxygen2docusaurus">doxygen2docusaurus</a> by <a href="https://www.doxygen.nl">Doxygen</a> 1.15.0.</p>

</div>
