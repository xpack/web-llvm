---

# DO NOT EDIT!
# Automatically generated via doxygen2docusaurus by Doxygen.

slug: /api/files/lib/lib/codegen/mirnamerpass-cpp
custom_edit_url: null
toc_max_heading_level: 4
keywords:
  - doxygen
  - reference
  - file

---

<div class="doxyPage">

# The `MIRNamerPass.cpp` File Reference



## Included Headers

<div class="doxyIncludesList">#include "<a href="/web-llvm/docs/api/files/lib/lib/codegen/mirvregnamerutils-h">MIRVRegNamerUtils.h</a>"
#include "<a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/adt/postorderiterator-h">llvm/ADT/PostOrderIterator.h</a>"
#include "<a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/codegen/machinefunctionpass-h">llvm/CodeGen/MachineFunctionPass.h</a>"
#include "<a href="/web-llvm/docs/api/files/include/include/llvm/initializepasses-h">llvm/InitializePasses.h</a>"
</div>

## Namespaces Index

<table class="doxyMembersIndex">

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">namespace</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="/web-llvm/docs/api/namespaces/llvm">llvm</a></td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>This is an optimization pass for GlobalISel generic memory operations. <a href="/web-llvm/docs/api/namespaces/llvm/#details">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">namespace</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="/web-llvm/docs/api/namespaces/anonymous-mirnamerpass-cpp-">anonymous{MIRNamerPass.cpp}</a></td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">class</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="/web-llvm/docs/api/classes/anonymous-mirnamerpass-cpp-/mirnamer">MIRNamer</a></td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a9317bf54798d81088e8ce1732f85ebbd">INITIALIZE_PASS_BEGIN</a> (MIRNamer, "mir-namer", "Rename Register Operands", false, false) INITIALIZE_PASS_END(MIRNamer</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">mir</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a7733f2c587d7fd73020509ca53c27380">namer</a></td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">mir Rename <a href="/web-llvm/docs/api/classes/llvm/register">Register</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a05e4be4ec3e2c3587dda0e376bb6822c">Operands</a></td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">mir Rename <a href="/web-llvm/docs/api/classes/llvm/register">Register</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#af2d59bcfa592c909af64f3702d268f0b">false</a></td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ad78e062f62e0d6e453941fb4ca843e4d">DEBUG_TYPE</a>&nbsp;&nbsp;&nbsp;"mir-namer"</td>
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

### INITIALIZE\_PASS\_BEGIN() {#a9317bf54798d81088e8ce1732f85ebbd}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">INITIALIZE_PASS_BEGIN (MIRNamer, "mir-namer", "Rename <a href="/web-llvm/docs/api/classes/llvm/register">Register</a> Operands", false, false)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 71 of file <a href="/web-llvm/docs/api/files/lib/lib/codegen/mirnamerpass-cpp">MIRNamerPass.cpp</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Variables

### false {#af2d59bcfa592c909af64f3702d268f0b}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">mir Rename Register false</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 74 of file <a href="/web-llvm/docs/api/files/lib/lib/codegen/mirnamerpass-cpp">MIRNamerPass.cpp</a>.</p>

</div>
</div>

### namer {#a7733f2c587d7fd73020509ca53c27380}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">mir namer</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 74 of file <a href="/web-llvm/docs/api/files/lib/lib/codegen/mirnamerpass-cpp">MIRNamerPass.cpp</a>.</p>

</div>
</div>

### Operands {#a05e4be4ec3e2c3587dda0e376bb6822c}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">mir Rename Register Operands</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 74 of file <a href="/web-llvm/docs/api/files/lib/lib/codegen/mirnamerpass-cpp">MIRNamerPass.cpp</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/lib/target/aarch64/asmparser/aarch64asmparser-cpp/#a8855c5802c329038446df58c5e996089">AArch64MnemonicSpellCheck</a>, <a href="/web-llvm/docs/api/classes/anonymous-webassemblyasmparser-cpp-/webassemblyasmparser/#ad76fa083052e876035888bd8a71240a8">anonymous{WebAssemblyAsmParser.cpp}::WebAssemblyAsmParser::addBlockTypeOperand</a>, <a href="/web-llvm/docs/api/classes/llvm/logicalview/lvsymbol/#a30ba8bccfc8e6977be4eb7d3dead67ac">llvm::logicalview::LVSymbol::addLocationOperands</a>, <a href="/web-llvm/docs/api/classes/llvm/amdgpuregisterbankinfo/#a7af7bb833a1702eacc1b0974ee514698">llvm::AMDGPURegisterBankInfo::addMappingFromTable</a>, <a href="/web-llvm/docs/api/classes/llvm/logicalview/lvlocation/#ac0d3a88f4c64f6db96717d05346955e4">llvm::logicalview::LVLocation::addObject</a>, <a href="/web-llvm/docs/api/classes/llvm/logicalview/lvlocationsymbol/#adb1dca396c7797d483c3f9e24729bddf">llvm::logicalview::LVLocationSymbol::addObject</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/lib/target/amdgpu/asmparser/amdgpuasmparser-cpp/#ac9d379c622b78d95b1ecd4823ccb15ac">addOptionalImmOperand</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/lib/target/amdgpu/asmparser/amdgpuasmparser-cpp/#ab8e8537ee53695e10c4b4d9e0f1da12e">addSrcModifiersAndSrc</a>, <a href="/web-llvm/docs/api/classes/llvm/riscvdagtodagisel/#a824579538728c6e67cf9a6191e5894e3">llvm::RISCVDAGToDAGISel::addVectorLoadStoreOperands</a>, <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/scalar/loopunrollpass-cpp/#a76ff59dafad74689cfe1966b0ed9fa3c">analyzeLoopUnrollCost</a>, <a href="/web-llvm/docs/api/classes/llvm/combinerhelper/#afcc62af19a5d1f2ea5f0e51b3e31893b">llvm::CombinerHelper::applyCombineUnmergeMergeToPlainValues</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/arm/lib/target/arm/asmparser/armasmparser-cpp/#a7e3060b58038543e52c27501d1bb957a">applyMnemonicAliases</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/ve/lib/target/ve/asmparser/veasmparser-cpp/#a7e3060b58038543e52c27501d1bb957a">applyMnemonicAliases</a>, <a href="/web-llvm/docs/api/classes/llvm/vplanslp/#a58eaa1512d1998338ab6f9e8e710a46e">llvm::VPlanSlp::buildGraph</a>, <a href="/web-llvm/docs/api/classes/llvm/r600instrinfo/#aca2b6568c134ce283d74d23db8d6b665">llvm::R600InstrInfo::buildSlotOfVectorInstruction</a>, <a href="/web-llvm/docs/api/classes/anonymous-armasmparser-cpp-/armasmparser/#a837cebf4290b760bbe740756cb60d6fe">anonymous{ARMAsmParser.cpp}::ARMAsmParser::checkEarlyTargetMatchPredicate</a>, <a href="/web-llvm/docs/api/classes/llvm/mctargetasmparser/#a5536b53eb6981ae394724632e464ae05">llvm::MCTargetAsmParser::checkEarlyTargetMatchPredicate</a>, <a href="/web-llvm/docs/api/classes/anonymous-webassemblyasmparser-cpp-/webassemblyasmparser/#a820bfb5af5692fdc662f2a2157d8830f">anonymous{WebAssemblyAsmParser.cpp}::WebAssemblyAsmParser::checkForP2AlignIfLoadStore</a>, <a href="/web-llvm/docs/api/classes/llvm/selectiondagisel/#a59165f42726267ed79287fd85ae682c9">llvm::SelectionDAGISel::CheckNodePredicateWithOperands</a>, <a href="/web-llvm/docs/api/classes/llvm/vpinstruction/#a4a5678fa8d469e9dd49b7e389c22d5c7">llvm::VPInstruction::clone</a>, <a href="/web-llvm/docs/api/classes/llvm/vpwidenrecipe/#a0075161c54fc525d16130fa2e1891ad2">llvm::VPWidenRecipe::computeCost</a>, <a href="/web-llvm/docs/api/structs/llvm/vpwidenselectrecipe/#a7805b21c1397d70002fd216481351f5e">llvm::VPWidenSelectRecipe::computeCost</a>, <a href="/web-llvm/docs/api/structs/llvm/constantexprkeytype/#adf16e652f4ba111247577ce870fdb85f">llvm::ConstantExprKeyType::ConstantExprKeyType</a>, <a href="/web-llvm/docs/api/namespaces/anonymous-constantfolding-cpp-/#a48ef6764a965598939c3ecf43eeb9fb0">anonymous{ConstantFolding.cpp}::ConstantFoldAMDGCNPermIntrinsic</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a4e3a3843bf5e85d3d55c2a252ec235bd">llvm::ConstantFoldCall</a>, <a href="/web-llvm/docs/api/namespaces/anonymous-constantfolding-cpp-/#ad60130f0b45a3ff1e759b010afefb94d">anonymous{ConstantFolding.cpp}::ConstantFoldFixedVectorCall</a>, <a href="/web-llvm/docs/api/namespaces/anonymous-constantfolding-cpp-/#a72190dad796891a1a5a59d64044000dc">anonymous{ConstantFolding.cpp}::ConstantFoldIntrinsicCall2</a>, <a href="/web-llvm/docs/api/namespaces/anonymous-constantfolding-cpp-/#af8730ce5a51609308adda5bc1de4a859">anonymous{ConstantFolding.cpp}::ConstantFoldLibCall2</a>, <a href="/web-llvm/docs/api/namespaces/anonymous-constantfolding-cpp-/#a0826c581880101a3069e74c70c76dad8">anonymous{ConstantFolding.cpp}::ConstantFoldScalableVectorCall</a>, <a href="/web-llvm/docs/api/namespaces/anonymous-constantfolding-cpp-/#a60c22952bdb1f70670aed956cb8afa52">anonymous{ConstantFolding.cpp}::ConstantFoldScalarCall</a>, <a href="/web-llvm/docs/api/namespaces/anonymous-constantfolding-cpp-/#aa8f5a312c9865602c873621adc9d8a18">anonymous{ConstantFolding.cpp}::ConstantFoldScalarCall1</a>, <a href="/web-llvm/docs/api/namespaces/anonymous-constantfolding-cpp-/#a505a295564c761e2006b8e48647f6f7d">anonymous{ConstantFolding.cpp}::ConstantFoldScalarCall3</a>, <a href="/web-llvm/docs/api/namespaces/anonymous-constantfolding-cpp-/#a294b49713de411cd8aadad66d82f205b">anonymous{ConstantFolding.cpp}::ConstantFoldStructCall</a>, <a href="/web-llvm/docs/api/classes/llvm/mctargetasmparser/#a095b27c5a40818758515ab898d07b5e3">llvm::MCTargetAsmParser::convertToMapAndConstraints</a>, <a href="/web-llvm/docs/api/classes/llvm/vpbuilder/#a85573e0f4a76b833f5c57beed6eb7a38">llvm::VPBuilder::createNaryOp</a>, <a href="/web-llvm/docs/api/classes/llvm/vpbuilder/#accbbcc76f9eb947b3804ad96beb2bbd2">llvm::VPBuilder::createNaryOp</a>, <a href="/web-llvm/docs/api/classes/llvm/vpbuilder/#ad317d7042dcaca782db6fe84324d6059">llvm::VPBuilder::createNaryOp</a>, <a href="/web-llvm/docs/api/classes/llvm/logicalview/lvreader/#ad06aaf2479ae6fe75fa6343470c9a8b3">llvm::logicalview::LVReader::createOperation</a>, <a href="/web-llvm/docs/api/classes/llvm/vpbuilder/#ab3b191f35221f351f77883447fef4019">llvm::VPBuilder::createOverflowingOp</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/csky/lib/target/csky/asmparser/cskyasmparser-cpp/#a9c7934fb7eadb7706d59f28a53db3e83">CSKYMnemonicSpellCheck</a>, <a href="/web-llvm/docs/api/classes/anonymous-amdgpuasmparser-cpp-/amdgpuasmparser/#adfaf977dc82c560bd265a68c807cd1a0">anonymous{AMDGPUAsmParser.cpp}::AMDGPUAsmParser::cvtDPP</a>, <a href="/web-llvm/docs/api/classes/anonymous-amdgpuasmparser-cpp-/amdgpuasmparser/#a15aaf557b5842153fe4a540281698b35">anonymous{AMDGPUAsmParser.cpp}::AMDGPUAsmParser::cvtDPP8</a>, <a href="/web-llvm/docs/api/classes/anonymous-amdgpuasmparser-cpp-/amdgpuasmparser/#a38abdd95e7f5b6e9f4fc534bb392f8b8">anonymous{AMDGPUAsmParser.cpp}::AMDGPUAsmParser::cvtExp</a>, <a href="/web-llvm/docs/api/classes/anonymous-amdgpuasmparser-cpp-/amdgpuasmparser/#a7d59a38f68d5236ad8c34c43351ce8cc">anonymous{AMDGPUAsmParser.cpp}::AMDGPUAsmParser::cvtMubuf</a>, <a href="/web-llvm/docs/api/classes/anonymous-amdgpuasmparser-cpp-/amdgpuasmparser/#a6986b4213079ebe325963a5422becbf3">anonymous{AMDGPUAsmParser.cpp}::AMDGPUAsmParser::cvtMubufAtomic</a>, <a href="/web-llvm/docs/api/classes/anonymous-amdgpuasmparser-cpp-/amdgpuasmparser/#a57878d0e3afa7d6e659b92b9d71c0923">anonymous{AMDGPUAsmParser.cpp}::AMDGPUAsmParser::cvtSDWA</a>, <a href="/web-llvm/docs/api/classes/anonymous-amdgpuasmparser-cpp-/amdgpuasmparser/#ade74ac635e66be70c5b81ab88d578d88">anonymous{AMDGPUAsmParser.cpp}::AMDGPUAsmParser::cvtSdwaVOP1</a>, <a href="/web-llvm/docs/api/classes/anonymous-amdgpuasmparser-cpp-/amdgpuasmparser/#a91b1e73c724242ec19e9e99688540dc6">anonymous{AMDGPUAsmParser.cpp}::AMDGPUAsmParser::cvtSdwaVOP2</a>, <a href="/web-llvm/docs/api/classes/anonymous-amdgpuasmparser-cpp-/amdgpuasmparser/#aa705db92f05d9b4e557da7c69c4a6960">anonymous{AMDGPUAsmParser.cpp}::AMDGPUAsmParser::cvtSdwaVOP2b</a>, <a href="/web-llvm/docs/api/classes/anonymous-amdgpuasmparser-cpp-/amdgpuasmparser/#aa5f806029a40f8f5bcb8210ce52841ce">anonymous{AMDGPUAsmParser.cpp}::AMDGPUAsmParser::cvtSdwaVOP2e</a>, <a href="/web-llvm/docs/api/classes/anonymous-amdgpuasmparser-cpp-/amdgpuasmparser/#af5e01806d4b89fadd4b471243098cc12">anonymous{AMDGPUAsmParser.cpp}::AMDGPUAsmParser::cvtSdwaVOPC</a>, <a href="/web-llvm/docs/api/classes/anonymous-amdgpuasmparser-cpp-/amdgpuasmparser/#a238abfd2ac2842861ab322354aec3d64">anonymous{AMDGPUAsmParser.cpp}::AMDGPUAsmParser::cvtSWMMAC</a>, <a href="/web-llvm/docs/api/classes/anonymous-amdgpuasmparser-cpp-/amdgpuasmparser/#ac4e2add1506387486f82ff6117a6a0e4">anonymous{AMDGPUAsmParser.cpp}::AMDGPUAsmParser::cvtVINTERP</a>, <a href="/web-llvm/docs/api/classes/anonymous-amdgpuasmparser-cpp-/amdgpuasmparser/#a21584d32fc8f81d68e30d7dac7838ff5">anonymous{AMDGPUAsmParser.cpp}::AMDGPUAsmParser::cvtVOP3</a>, <a href="/web-llvm/docs/api/classes/anonymous-amdgpuasmparser-cpp-/amdgpuasmparser/#a4547aa57e2b9056a73e2a8b26cc18d5b">anonymous{AMDGPUAsmParser.cpp}::AMDGPUAsmParser::cvtVOP3</a>, <a href="/web-llvm/docs/api/classes/anonymous-amdgpuasmparser-cpp-/amdgpuasmparser/#a81d4a718e3a11c1c3507fb28db101cf6">anonymous{AMDGPUAsmParser.cpp}::AMDGPUAsmParser::cvtVOP3DPP</a>, <a href="/web-llvm/docs/api/classes/anonymous-amdgpuasmparser-cpp-/amdgpuasmparser/#aa5e7317f66ba20d6de650a0294a112c4">anonymous{AMDGPUAsmParser.cpp}::AMDGPUAsmParser::cvtVOP3DPP8</a>, <a href="/web-llvm/docs/api/classes/anonymous-amdgpuasmparser-cpp-/amdgpuasmparser/#af30bfdcbe6574a1d0de2c2c59c1a8f18">anonymous{AMDGPUAsmParser.cpp}::AMDGPUAsmParser::cvtVOP3Interp</a>, <a href="/web-llvm/docs/api/classes/anonymous-amdgpuasmparser-cpp-/amdgpuasmparser/#af9f84a232dd5f4bc0758374c9d26203f">anonymous{AMDGPUAsmParser.cpp}::AMDGPUAsmParser::cvtVOP3OpSel</a>, <a href="/web-llvm/docs/api/classes/anonymous-amdgpuasmparser-cpp-/amdgpuasmparser/#a169daf8f1c8486c073f4faa87b0f402e">anonymous{AMDGPUAsmParser.cpp}::AMDGPUAsmParser::cvtVOP3OpSel</a>, <a href="/web-llvm/docs/api/classes/anonymous-amdgpuasmparser-cpp-/amdgpuasmparser/#a54a0d60e48d43aad665fd4096d2b4945">anonymous{AMDGPUAsmParser.cpp}::AMDGPUAsmParser::cvtVOP3P</a>, <a href="/web-llvm/docs/api/classes/anonymous-amdgpuasmparser-cpp-/amdgpuasmparser/#a21401db3d85754eab356474360dd2394">anonymous{AMDGPUAsmParser.cpp}::AMDGPUAsmParser::cvtVOP3P</a>, <a href="/web-llvm/docs/api/classes/anonymous-amdgpuasmparser-cpp-/amdgpuasmparser/#a0b9f3d685a06c0789d0e594e044be2b9">anonymous{AMDGPUAsmParser.cpp}::AMDGPUAsmParser::cvtVOPD</a>, <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/utils/buildlibcalls-cpp/#a62d6c0a5c9dd42949245eb28ab9c37c8">emitLibCall</a>, <a href="/web-llvm/docs/api/classes/llvm/sandboxir/erasefromparent/#af1b0632cc2cf266696f1d57796553534">llvm::sandboxir::EraseFromParent::EraseFromParent</a>, <a href="/web-llvm/docs/api/files/lib/lib/analysis/scalarevolution-cpp/#ad62d5df272037a3079a05b96be49cc44">EvaluateExpression</a>, <a href="/web-llvm/docs/api/classes/anonymous-armasmparser-cpp-/armasmparser/#a43ffe9d0de2c3fc1eb0c8bb0b6c7526d">anonymous{ARMAsmParser.cpp}::ARMAsmParser::FilterNearMisses</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/arm/lib/target/arm/asmparser/armasmparser-cpp/#a35a12d4e22f970f10bee0942b22c2cc4">findCCOutInd</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/arm/lib/target/arm/asmparser/armasmparser-cpp/#ae96d1e834df05c3b400fa14a46812f51">findCondCodeInd</a>, <a href="/web-llvm/docs/api/classes/llvm/instcombinerimpl/#ad4fde4387244f67f320e62602af17b68">llvm::InstCombinerImpl::foldAllocaCmp</a>, <a href="/web-llvm/docs/api/structs/anonymous-delinearization-cpp-/scevcollectaddrecmultiplies/#af9f93d27133d9adf30cee18517b280cc">anonymous{Delinearization.cpp}::SCEVCollectAddRecMultiplies::follow</a>, <a href="/web-llvm/docs/api/classes/llvm/scalarevolution/#a659b27f6737fcb7eaf333b0279da1154">llvm::ScalarEvolution::getAddRecExpr</a>, <a href="/web-llvm/docs/api/classes/llvm/scalarevolution/#a6df0ad4a470aaae9009ab0dc0e7b2149">llvm::ScalarEvolution::getAddRecExpr</a>, <a href="/web-llvm/docs/api/classes/llvm/scalarevolution/#a69f32678ea46cdda0318c0be9bdb1c7e">llvm::ScalarEvolution::getAddRecExpr</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64targettransforminfo-cpp/#a78171da3a30a449d469ccebbff57760e">getAppleRuntimeUnrollPreferences</a>, <a href="/web-llvm/docs/api/classes/llvm/aarch64ttiimpl/#a031124353d199e69bbc9101bde19b023">llvm::AArch64TTIImpl::getCastInstrCost</a>, <a href="/web-llvm/docs/api/classes/llvm/loopvectorizationcostmodel/#ad8398a35cd187d6a75b460fcf54b5236">llvm::LoopVectorizationCostModel::getDivRemSpeculationCost</a>, <a href="/web-llvm/docs/api/classes/anonymous-typebasedaliasanalysis-cpp-/tbaastructtypenode/#adf4acdd27d93ff0b0eec8cda6af26de3">anonymous{TypeBasedAliasAnalysis.cpp}::TBAAStructTypeNode::getField</a>, <a href="/web-llvm/docs/api/classes/llvm/basicttiimplbase/#a6f9f77c0b6c55a744114bbcaa5f9a341">llvm::BasicTTIImplBase&lt; BasicTTIImpl &gt;::getGEPCost</a>, <a href="/web-llvm/docs/api/classes/llvm/targettransforminfo/concept/#a46f66e6aada93d91fd17f0ece4d662f8">llvm::TargetTransformInfo::Concept::getGEPCost</a>, <a href="/web-llvm/docs/api/classes/llvm/targettransforminfo/#a57fca44604259f23a346fdc969aaefeb">llvm::TargetTransformInfo::getGEPCost</a>, <a href="/web-llvm/docs/api/classes/llvm/targettransforminfoimplbase/#ae1ba2055802f801ea22d2ff5936e2365">llvm::TargetTransformInfoImplBase::getGEPCost</a>, <a href="/web-llvm/docs/api/classes/llvm/targettransforminfoimplcrtpbase/#a655cabf7c0f1a0d1e8312338e86abb84">llvm::TargetTransformInfoImplCRTPBase&lt; T &gt;::getGEPCost</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a2541c2671bd6870bffd5ee14f08d0ac5">llvm::getGuaranteedNonPoisonOps</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a6a22c931852d3ca2de0c40db6424394f">llvm::getGuaranteedWellDefinedOps</a>, <a href="/web-llvm/docs/api/classes/llvm/hexagonttiimpl/#acee4a569a0d284e1397899937aad7836">llvm::HexagonTTIImpl::getInstructionCost</a>, <a href="/web-llvm/docs/api/classes/llvm/loopvectorizationcostmodel/#a556ec90a0fa1e168a9f22db1deb1fee6">llvm::LoopVectorizationCostModel::getInstructionCost</a>, <a href="/web-llvm/docs/api/classes/llvm/ppcttiimpl/#ada4520fadc98f59acef021bda2d6e608">llvm::PPCTTIImpl::getInstructionCost</a>, <a href="/web-llvm/docs/api/classes/llvm/targettransforminfo/concept/#a59b03a961dc84dbd6ddf8397340cd98b">llvm::TargetTransformInfo::Concept::getInstructionCost</a>, <a href="/web-llvm/docs/api/classes/llvm/targettransforminfo/#ac77dbedcfd916a5c9b58e753b2678a98">llvm::TargetTransformInfo::getInstructionCost</a>, <a href="/web-llvm/docs/api/classes/llvm/targettransforminfo/#a3e2a0583912318be02194abf401fdf1e">llvm::TargetTransformInfo::getInstructionCost</a>, <a href="/web-llvm/docs/api/classes/llvm/targettransforminfoimplcrtpbase/#a95442a0e0980e874df3bf77d6c8dee44">llvm::TargetTransformInfoImplCRTPBase&lt; T &gt;::getInstructionCost</a>, <a href="/web-llvm/docs/api/classes/llvm/scalarevolution/#a4bab447a6422427e5fc92bbbc0c12fba">llvm::ScalarEvolution::getLosslessPtrToIntExpr</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/arm/lib/target/arm/asmparser/armasmparser-cpp/#ade574bf5f9f58e50d61357e33fdcab6b">getMnemonicOpsEndInd</a>, <a href="/web-llvm/docs/api/classes/llvm/scalarevolution/#ad299b0f4378f644f67168c72c763716f">llvm::ScalarEvolution::getMulExpr</a>, <a href="/web-llvm/docs/api/files/lib/lib/ir/metadata-cpp/#a81e3dc463e57367ea1eeafe570110894">getNMDOps</a>, <a href="/web-llvm/docs/api/classes/llvm/scevaddrecexpr/#a7e688afe102c3fa48ea49cb972a0f00c">llvm::SCEVAddRecExpr::getNumIterationsInRange</a>, <a href="/web-llvm/docs/api/namespaces/llvm/sandboxir/#ac9a69bf52a5b93bb710536d9ae8245c6">llvm::sandboxir::getOperand</a>, <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/vectorize/vplanslp-cpp/#aca0e935964c3957530233849a972e1ea">getOperands</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/x86/lib/target/x86/asmparser/x86asmparser-cpp/#a5d903d68c5460070cd9342e9302983c7">getPrefixes</a>, <a href="/web-llvm/docs/api/classes/llvm/logicalview/lvcodeviewreader/#a50c7683b6e84562ebcc173bd25a76deb">llvm::logicalview::LVCodeViewReader::getRegisterName</a>, <a href="/web-llvm/docs/api/classes/llvm/logicalview/lvdwarfreader/#a6e3d7579887f71bf2b4cf7def5a3d77b">llvm::logicalview::LVDWARFReader::getRegisterName</a>, <a href="/web-llvm/docs/api/classes/llvm/logicalview/lvreader/#a4ba7d69a179758cfe95b692774eb95ab">llvm::logicalview::LVReader::getRegisterName</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/arm/lib/target/arm/asmparser/armasmparser-cpp/#a5d2db8a89250507cfba04ea5eefa2262">getRegListInd</a>, <a href="/web-llvm/docs/api/classes/llvm/gimatchtableexecutor/#ae8bba411b15797dcf6969c2f6e636bcd">llvm::GIMatchTableExecutor::getRemainingOperands</a>, <a href="/web-llvm/docs/api/classes/llvm/scalarevolution/#a643b61ddaf17331f3ff1d4f85c7c9a23">llvm::ScalarEvolution::getSignExtendExprImpl</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/lib/target/aarch64/asmparser/aarch64asmparser-cpp/#a63d4d2d7515d06593ca4f644f012a7e6">getSubtargetFeatureName</a>, <a href="/web-llvm/docs/api/classes/llvm/scalarevolution/#a83c084b0947edf4ae748f9a73babf7b8">llvm::ScalarEvolution::getTruncateExpr</a>, <a href="/web-llvm/docs/api/classes/llvm/scalarevolution/#aeca82ae7bafbb557b7026f7d035643b8">llvm::ScalarEvolution::getUDivExactExpr</a>, <a href="/web-llvm/docs/api/classes/llvm/scalarevolution/#a6c03d18ed744dc3b34829ec5485a68b0">llvm::ScalarEvolution::getUDivExpr</a>, <a href="/web-llvm/docs/api/classes/llvm/armttiimpl/#a6c22989c03e43928e4b09cfa60a804f5">llvm::ARMTTIImpl::getUnrollingPreferences</a>, <a href="/web-llvm/docs/api/classes/llvm/riscvttiimpl/#a978825baa870839107dcb64531311bca">llvm::RISCVTTIImpl::getUnrollingPreferences</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/riscv/riscvisellowering-cpp/#a617e46f89d289e06bc822202c7d7b158">getVCIXISDNodeVOID</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/riscv/riscvisellowering-cpp/#add9ae062b13708c4ce1091ad75204109">getVCIXISDNodeWCHAIN</a>, <a href="/web-llvm/docs/api/files/lib/lib/codegen/interleavedaccesspass-cpp/#a1bf96ea28c04f3533cf028a1d471eae4">getVectorInterleaveFactor</a>, <a href="/web-llvm/docs/api/classes/llvm/scalarevolution/#a26ffa319e1953452b1d1df84923f2108">llvm::ScalarEvolution::getZeroExtendExprImpl</a>, <a href="/web-llvm/docs/api/classes/anonymous-hexagonasmparser-cpp-/hexagonasmparser/#add28cb403c9cdb90cf5aab64b9adaff6">anonymous{HexagonAsmParser.cpp}::HexagonAsmParser::implicitExpressionLocation</a>, <a href="/web-llvm/docs/api/classes/anonymous-inlinecost-cpp-/callanalyzer/#a6cd79b520cf0ecc13ef7f9fe36db74fc">anonymous{InlineCost.cpp}::CallAnalyzer::isGEPFree</a>, <a href="/web-llvm/docs/api/files/lib/lib/codegen/lib/codegen/mirparser/miparser-cpp/#ac71ff55e5082eff77950ab8122aad429">isImplicitOperandIn</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/lib/target/amdgpu/asmparser/amdgpuasmparser-cpp/#ae58d7ce01c34f2ecb225e1dedfa736e3">isInvalidVOPDY</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/lanai/lib/target/lanai/asmparser/lanaiasmparser-cpp/#a14c5fa321a079e20b4a884fee7b7788a">IsMemoryAssignmentError</a>, <a href="/web-llvm/docs/api/classes/anonymous-amdgpuasmparser-cpp-/amdgpuasmparser/#a3c48b1ea644084c3a3e9751a96f10a11">anonymous{AMDGPUAsmParser.cpp}::AMDGPUAsmParser::isSupportedDPPCtrl</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/siisellowering-cpp/#a3dbdbf556532f2d39ea38114cb7a5a23">lowerLaneOp</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/riscv/riscvisellowering-cpp/#a602b901d40f2b6bc5bf489a131309eef">lowerShuffleViaVRegSplitting</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/riscv/riscvisellowering-cpp/#a95bb2318cffbd613f244603838b30094">lowerVectorIntrinsicScalars</a>, <a href="/web-llvm/docs/api/classes/llvm/vprecipebuilder/#a537d8b3b5160caeb94b20a21a9f6dcff">llvm::VPRecipeBuilder::mapToVPValues</a>, <a href="/web-llvm/docs/api/classes/llvm/anonymous-armlatencymutations-cpp-/instructioninformation/#acd87bac3058ade9f773fd2c79abdde8d">llvm::anonymous{ARMLatencyMutations.cpp}::InstructionInformation::markDPProducersConsumers</a>, <a href="/web-llvm/docs/api/classes/anonymous-amdgpuasmparser-cpp-/amdgpuasmparser/#a6bffa32d06d1516ee01e79b5a250c72e">anonymous{AMDGPUAsmParser.cpp}::AMDGPUAsmParser::matchAndEmitInstruction</a>, <a href="/web-llvm/docs/api/classes/anonymous-armasmparser-cpp-/armasmparser/#a25385ca3fbc7a797f0786eb6e4faf8bf">anonymous{ARMAsmParser.cpp}::ARMAsmParser::matchAndEmitInstruction</a>, <a href="/web-llvm/docs/api/classes/anonymous-m68kasmparser-cpp-/m68kasmparser/#a9fa1168e106748c0618d6c0f432558b7">anonymous{M68kAsmParser.cpp}::M68kAsmParser::matchAndEmitInstruction</a>, <a href="/web-llvm/docs/api/classes/anonymous-systemzasmparser-cpp-/systemzasmparser/#a0b228c0975660d76b206b2f9220b3cc3">anonymous{SystemZAsmParser.cpp}::SystemZAsmParser::matchAndEmitInstruction</a>, <a href="/web-llvm/docs/api/classes/anonymous-webassemblyasmparser-cpp-/webassemblyasmparser/#abeebd6c3e48c1d92d186d8ffafbf5e2b">anonymous{WebAssemblyAsmParser.cpp}::WebAssemblyAsmParser::matchAndEmitInstruction</a>, <a href="/web-llvm/docs/api/classes/llvm/mctargetasmparser/#a85856339f3e9598112e6e6268ad13614">llvm::MCTargetAsmParser::matchAndEmitInstruction</a>, <a href="/web-llvm/docs/api/classes/llvm/combinerhelper/#afc1c60085dd818c0586c87f44db3d10a">llvm::CombinerHelper::matchCombineUnmergeMergeToPlainValues</a>, <a href="/web-llvm/docs/api/classes/anonymous-armasmparser-cpp-/armasmparser/#ab27e65f978739f8a4075962e72373af5">anonymous{ARMAsmParser.cpp}::ARMAsmParser::MatchInstruction</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/avr/lib/target/avr/asmparser/avrasmparser-cpp/#a12e31c0c30a774b7e1a19becc5fa1890">MatchRegisterAltName</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/lanai/lib/target/lanai/asmparser/lanaiasmparser-cpp/#aa381725d28ae64fbe2941e262ad59353">MaybePredicatedInst</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/arm/lib/target/arm/asmparser/armasmparser-cpp/#ab4a9775a81f01a468151cb247d55555e">operandsContainWide</a>, <a href="/web-llvm/docs/api/classes/anonymous-miparser-cpp-/miparser/#a9d7f3f2b0dc486075d4d462b7d744174">anonymous{MIParser.cpp}::MIParser::parse</a>, <a href="/web-llvm/docs/api/structs/llvm/dwarfdebugline/linetable/#a49eb2522e1fc6988c75f9936c3061bb6">llvm::DWARFDebugLine::LineTable::parse</a>, <a href="/web-llvm/docs/api/classes/anonymous-systemzasmparser-cpp-/systemzasmparser/#a5e5e329690a5ff07018f729a95afe792">anonymous{SystemZAsmParser.cpp}::SystemZAsmParser::parseADDR128</a>, <a href="/web-llvm/docs/api/classes/anonymous-systemzasmparser-cpp-/systemzasmparser/#a58ef740f7dc46c8f4fd193e19fa95f5f">anonymous{SystemZAsmParser.cpp}::SystemZAsmParser::parseADDR32</a>, <a href="/web-llvm/docs/api/classes/anonymous-systemzasmparser-cpp-/systemzasmparser/#a554db9b4aa0de4c0a487f5987ba54bd1">anonymous{SystemZAsmParser.cpp}::SystemZAsmParser::parseADDR64</a>, <a href="/web-llvm/docs/api/classes/anonymous-systemzasmparser-cpp-/systemzasmparser/#a823c797b7c9fc190228ae4ebf73d2acf">anonymous{SystemZAsmParser.cpp}::SystemZAsmParser::parseAnyReg</a>, <a href="/web-llvm/docs/api/classes/anonymous-systemzasmparser-cpp-/systemzasmparser/#ae16de6abb2bbe5c763bdaca1babcdc9c">anonymous{SystemZAsmParser.cpp}::SystemZAsmParser::parseAR32</a>, <a href="/web-llvm/docs/api/classes/anonymous-systemzasmparser-cpp-/systemzasmparser/#a3dd1379711b9f8a20874cc2afc9ee566">anonymous{SystemZAsmParser.cpp}::SystemZAsmParser::parseBDAddr32</a>, <a href="/web-llvm/docs/api/classes/anonymous-systemzasmparser-cpp-/systemzasmparser/#aef8cb1914235736e85822cf8ba80595f">anonymous{SystemZAsmParser.cpp}::SystemZAsmParser::parseBDAddr64</a>, <a href="/web-llvm/docs/api/classes/anonymous-systemzasmparser-cpp-/systemzasmparser/#aeb5a7e89f81c79bfe25d01a0edb82baa">anonymous{SystemZAsmParser.cpp}::SystemZAsmParser::parseBDLAddr64</a>, <a href="/web-llvm/docs/api/classes/anonymous-systemzasmparser-cpp-/systemzasmparser/#ad36d087eb445892056e41a809c8a2960">anonymous{SystemZAsmParser.cpp}::SystemZAsmParser::parseBDRAddr64</a>, <a href="/web-llvm/docs/api/classes/anonymous-systemzasmparser-cpp-/systemzasmparser/#a475f0dc86afe9dccd52240fbd54bae8b">anonymous{SystemZAsmParser.cpp}::SystemZAsmParser::parseBDVAddr64</a>, <a href="/web-llvm/docs/api/classes/anonymous-systemzasmparser-cpp-/systemzasmparser/#a77dbf6b4646b24856b2bf82426e78a5a">anonymous{SystemZAsmParser.cpp}::SystemZAsmParser::parseBDXAddr64</a>, <a href="/web-llvm/docs/api/classes/anonymous-amdgpuasmparser-cpp-/amdgpuasmparser/#a3ad635dcc304d17a852fa28adac99bb9">anonymous{AMDGPUAsmParser.cpp}::AMDGPUAsmParser::parseBLGP</a>, <a href="/web-llvm/docs/api/classes/anonymous-amdgpuasmparser-cpp-/amdgpuasmparser/#a5c229c26ac4e66cb56bd6d00cb6e86d4">anonymous{AMDGPUAsmParser.cpp}::AMDGPUAsmParser::parseBoolReg</a>, <a href="/web-llvm/docs/api/classes/anonymous-webassemblyasmparser-cpp-/webassemblyasmparser/#a4009b2b10bf09c0de7daf3062a89d803">anonymous{WebAssemblyAsmParser.cpp}::WebAssemblyAsmParser::parseCatchList</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/ve/lib/target/ve/asmparser/veasmparser-cpp/#a874fe455718e3ea10454347888391fc2">parseCC</a>, <a href="/web-llvm/docs/api/classes/anonymous-amdgpuasmparser-cpp-/amdgpuasmparser/#a905978e46c9c9a277645e938f41e1876">anonymous{AMDGPUAsmParser.cpp}::AMDGPUAsmParser::parseCPol</a>, <a href="/web-llvm/docs/api/classes/anonymous-systemzasmparser-cpp-/systemzasmparser/#aa3c104c634d223fb2225b27af2ec0884">anonymous{SystemZAsmParser.cpp}::SystemZAsmParser::parseCR64</a>, <a href="/web-llvm/docs/api/classes/anonymous-amdgpuasmparser-cpp-/amdgpuasmparser/#a877255e198cc72078a64aa635548b03b">anonymous{AMDGPUAsmParser.cpp}::AMDGPUAsmParser::parseCustomOperand</a>, <a href="/web-llvm/docs/api/classes/anonymous-amdgpuasmparser-cpp-/amdgpuasmparser/#aec0a91539564d9315907e97bc05acdbb">anonymous{AMDGPUAsmParser.cpp}::AMDGPUAsmParser::parseDepCtr</a>, <a href="/web-llvm/docs/api/classes/anonymous-amdgpuasmparser-cpp-/amdgpuasmparser/#aa54525f0109858da308fa32559539255">anonymous{AMDGPUAsmParser.cpp}::AMDGPUAsmParser::parseDepCtr</a>, <a href="/web-llvm/docs/api/classes/anonymous-amdgpuasmparser-cpp-/amdgpuasmparser/#a4c31665501f9b711e245f1b4e201683b">anonymous{AMDGPUAsmParser.cpp}::AMDGPUAsmParser::parseDim</a>, <a href="/web-llvm/docs/api/classes/anonymous-amdgpuasmparser-cpp-/amdgpuasmparser/#a59d9c798683c4a134a731c43840d62aa">anonymous{AMDGPUAsmParser.cpp}::AMDGPUAsmParser::parseDPP8</a>, <a href="/web-llvm/docs/api/classes/anonymous-amdgpuasmparser-cpp-/amdgpuasmparser/#af1e3005e43d45d207eb661fa024b1753">anonymous{AMDGPUAsmParser.cpp}::AMDGPUAsmParser::parseDPPCtrl</a>, <a href="/web-llvm/docs/api/classes/anonymous-amdgpuasmparser-cpp-/amdgpuasmparser/#a0b822486044ee842c7c868f39ff4830b">anonymous{AMDGPUAsmParser.cpp}::AMDGPUAsmParser::parseEndpgm</a>, <a href="/web-llvm/docs/api/classes/anonymous-hexagonasmparser-cpp-/hexagonasmparser/#a1e6614f21ef1971dca42492c7318b5b7">anonymous{HexagonAsmParser.cpp}::HexagonAsmParser::parseExpressionOrOperand</a>, <a href="/web-llvm/docs/api/classes/anonymous-amdgpuasmparser-cpp-/amdgpuasmparser/#a26a8456ca91f0f85ed2f854837b0dc29">anonymous{AMDGPUAsmParser.cpp}::AMDGPUAsmParser::parseExpTgt</a>, <a href="/web-llvm/docs/api/classes/anonymous-amdgpuasmparser-cpp-/amdgpuasmparser/#af9a4f566ce16209db2301b23edfe1573">anonymous{AMDGPUAsmParser.cpp}::AMDGPUAsmParser::parseFlatOffset</a>, <a href="/web-llvm/docs/api/classes/anonymous-amdgpuasmparser-cpp-/amdgpuasmparser/#aae18974f031b21f7dd37b072a1cbe24d">anonymous{AMDGPUAsmParser.cpp}::AMDGPUAsmParser::parseFORMAT</a>, <a href="/web-llvm/docs/api/classes/anonymous-systemzasmparser-cpp-/systemzasmparser/#a0930f144b0a621c04ee41e0998f9fcde">anonymous{SystemZAsmParser.cpp}::SystemZAsmParser::parseFP128</a>, <a href="/web-llvm/docs/api/classes/anonymous-systemzasmparser-cpp-/systemzasmparser/#a53025eb97289450566eb0b690604fa5e">anonymous{SystemZAsmParser.cpp}::SystemZAsmParser::parseFP32</a>, <a href="/web-llvm/docs/api/classes/anonymous-systemzasmparser-cpp-/systemzasmparser/#a1f0ceca272b89e97c2017c50696fb2bd">anonymous{SystemZAsmParser.cpp}::SystemZAsmParser::parseFP64</a>, <a href="/web-llvm/docs/api/classes/anonymous-amdgpuasmparser-cpp-/amdgpuasmparser/#ad03402b69301c9df929a7ca211df947c">anonymous{AMDGPUAsmParser.cpp}::AMDGPUAsmParser::parseGPRIdxMode</a>, <a href="/web-llvm/docs/api/classes/anonymous-riscvasmparser-cpp-/riscvasmparser/#a320fc842d9d7ffee6e2bffb42354fc45">anonymous{RISCVAsmParser.cpp}::RISCVAsmParser::parseGPRPair</a>, <a href="/web-llvm/docs/api/classes/anonymous-systemzasmparser-cpp-/systemzasmparser/#a5cd4177f037cd97d521c007d80f3b32e">anonymous{SystemZAsmParser.cpp}::SystemZAsmParser::parseGR128</a>, <a href="/web-llvm/docs/api/classes/anonymous-systemzasmparser-cpp-/systemzasmparser/#a76700942e0fd98cb257cc036aa32e8b4">anonymous{SystemZAsmParser.cpp}::SystemZAsmParser::parseGR32</a>, <a href="/web-llvm/docs/api/classes/anonymous-systemzasmparser-cpp-/systemzasmparser/#a3f51d5294d14407ea4bb301e725401d1">anonymous{SystemZAsmParser.cpp}::SystemZAsmParser::parseGR64</a>, <a href="/web-llvm/docs/api/classes/anonymous-systemzasmparser-cpp-/systemzasmparser/#ae35fa883c867767e979d0c81defc3865">anonymous{SystemZAsmParser.cpp}::SystemZAsmParser::parseGRH32</a>, <a href="/web-llvm/docs/api/classes/anonymous-systemzasmparser-cpp-/systemzasmparser/#abb0a1232e0a64728d20b5fa584b24880">anonymous{SystemZAsmParser.cpp}::SystemZAsmParser::parseGRX32</a>, <a href="/web-llvm/docs/api/classes/anonymous-amdgpuasmparser-cpp-/amdgpuasmparser/#a16bbeaa5435876a2a30093aa9f7adc09">anonymous{AMDGPUAsmParser.cpp}::AMDGPUAsmParser::parseHwreg</a>, <a href="/web-llvm/docs/api/classes/anonymous-amdgpuasmparser-cpp-/amdgpuasmparser/#a62ccca1cd262d040e8aee057ab0d22d5">anonymous{AMDGPUAsmParser.cpp}::AMDGPUAsmParser::parseImm</a>, <a href="/web-llvm/docs/api/classes/anonymous-amdgpuasmparser-cpp-/amdgpuasmparser/#a8a20622d48ff74bd05f5de0cafcba3ab">anonymous{AMDGPUAsmParser.cpp}::AMDGPUAsmParser::parseIndexKey16bit</a>, <a href="/web-llvm/docs/api/classes/anonymous-amdgpuasmparser-cpp-/amdgpuasmparser/#a9c025a975a2c1bb92eeff1c356d17df3">anonymous{AMDGPUAsmParser.cpp}::AMDGPUAsmParser::parseIndexKey8bit</a>, <a href="/web-llvm/docs/api/classes/anonymous-aarch64asmparser-cpp-/aarch64asmparser/#adc0358b42d36242d132980b3fe8260de">anonymous{AArch64AsmParser.cpp}::AArch64AsmParser::parseInstruction</a>, <a href="/web-llvm/docs/api/classes/anonymous-amdgpuasmparser-cpp-/amdgpuasmparser/#af09dfe84acccdfc6a55c91388892da8e">anonymous{AMDGPUAsmParser.cpp}::AMDGPUAsmParser::parseInstruction</a>, <a href="/web-llvm/docs/api/classes/anonymous-armasmparser-cpp-/armasmparser/#a89eeee4c3ec5d281810e8ac7572ddee4">anonymous{ARMAsmParser.cpp}::ARMAsmParser::parseInstruction</a>, <a href="/web-llvm/docs/api/classes/anonymous-hexagonasmparser-cpp-/hexagonasmparser/#ac9c92aad21e10d61c23982f88c094ef3">anonymous{HexagonAsmParser.cpp}::HexagonAsmParser::parseInstruction</a>, <a href="/web-llvm/docs/api/classes/anonymous-hexagonasmparser-cpp-/hexagonasmparser/#a824717c2bf3eae4a888e53092a2ea962">anonymous{HexagonAsmParser.cpp}::HexagonAsmParser::parseInstruction</a>, <a href="/web-llvm/docs/api/classes/anonymous-hexagonasmparser-cpp-/hexagonasmparser/#ae7f146d81c6cddcff295972985bfcc86">anonymous{HexagonAsmParser.cpp}::HexagonAsmParser::parseInstruction</a>, <a href="/web-llvm/docs/api/classes/anonymous-m68kasmparser-cpp-/m68kasmparser/#a6ed1f4d7f56e05cf30cc258a8f248bf7">anonymous{M68kAsmParser.cpp}::M68kAsmParser::parseInstruction</a>, <a href="/web-llvm/docs/api/classes/anonymous-ppcasmparser-cpp-/ppcasmparser/#a7a8526125b46eeca9eb066fedddefa6f">anonymous{PPCAsmParser.cpp}::PPCAsmParser::parseInstruction</a>, <a href="/web-llvm/docs/api/classes/anonymous-systemzasmparser-cpp-/systemzasmparser/#ad79a6d97b50d37cfcc0ba24dfc387b10">anonymous{SystemZAsmParser.cpp}::SystemZAsmParser::parseInstruction</a>, <a href="/web-llvm/docs/api/classes/anonymous-webassemblyasmparser-cpp-/webassemblyasmparser/#a0cacf6ffb7a5ce2195bd33f0e9c0087c">anonymous{WebAssemblyAsmParser.cpp}::WebAssemblyAsmParser::parseInstruction</a>, <a href="/web-llvm/docs/api/classes/anonymous-x86asmparser-cpp-/x86asmparser/#abf6230cdb8093ea54524821d036b2203">anonymous{X86AsmParser.cpp}::X86AsmParser::parseInstruction</a>, <a href="/web-llvm/docs/api/classes/llvm/mctargetasmparser/#a9d095012b8efc8795fe4403722dcf9d4">llvm::MCTargetAsmParser::parseInstruction</a>, <a href="/web-llvm/docs/api/classes/llvm/mctargetasmparser/#a058facd817d442129355ef40eb9a1140">llvm::MCTargetAsmParser::parseInstruction</a>, <a href="/web-llvm/docs/api/classes/anonymous-amdgpuasmparser-cpp-/amdgpuasmparser/#a5c3abd5a0df4ec19738884622846a92b">anonymous{AMDGPUAsmParser.cpp}::AMDGPUAsmParser::parseInterpAttr</a>, <a href="/web-llvm/docs/api/classes/anonymous-amdgpuasmparser-cpp-/amdgpuasmparser/#abc5a32fe7c02fdcfc1484e926e376ce0">anonymous{AMDGPUAsmParser.cpp}::AMDGPUAsmParser::parseInterpSlot</a>, <a href="/web-llvm/docs/api/classes/anonymous-amdgpuasmparser-cpp-/amdgpuasmparser/#a82b29753ac1baad9801c7217c0a97dd4">anonymous{AMDGPUAsmParser.cpp}::AMDGPUAsmParser::parseIntWithPrefix</a>, <a href="/web-llvm/docs/api/classes/anonymous-amdgpuasmparser-cpp-/amdgpuasmparser/#a4bbb3e5e0e2e2c935c2a911665fff611">anonymous{AMDGPUAsmParser.cpp}::AMDGPUAsmParser::parseIntWithPrefix</a>, <a href="/web-llvm/docs/api/classes/anonymous-systemzasmparser-cpp-/systemzasmparser/#a8c7be4c67a0803255f3324950046a37c">anonymous{SystemZAsmParser.cpp}::SystemZAsmParser::parseLXAAddr64</a>, <a href="/web-llvm/docs/api/classes/anonymous-amdgpuasmparser-cpp-/amdgpuasmparser/#ab2ff8b8fa2100a684cea688b74d329ab">anonymous{AMDGPUAsmParser.cpp}::AMDGPUAsmParser::parseNamedBit</a>, <a href="/web-llvm/docs/api/classes/anonymous-amdgpuasmparser-cpp-/amdgpuasmparser/#a9d5e44bae726c6d5f1d1af4aba4a48ff">anonymous{AMDGPUAsmParser.cpp}::AMDGPUAsmParser::parseOModSI</a>, <a href="/web-llvm/docs/api/classes/anonymous-amdgpuasmparser-cpp-/amdgpuasmparser/#a2f6673e616e48f8b6505d19ef64eddab">anonymous{AMDGPUAsmParser.cpp}::AMDGPUAsmParser::parseOperand</a>, <a href="/web-llvm/docs/api/classes/anonymous-hexagonasmparser-cpp-/hexagonasmparser/#a64ef2d014c82249a7bc8cb033757d7f1">anonymous{HexagonAsmParser.cpp}::HexagonAsmParser::parseOperand</a>, <a href="/web-llvm/docs/api/classes/anonymous-amdgpuasmparser-cpp-/amdgpuasmparser/#ac9d07a4881948a410fcba201eeb36480">anonymous{AMDGPUAsmParser.cpp}::AMDGPUAsmParser::parseOperandArrayWithPrefix</a>, <a href="/web-llvm/docs/api/classes/anonymous-systemzasmparser-cpp-/systemzasmparser/#ab90ca0e810f338dce2fa9cf1cac8765d">anonymous{SystemZAsmParser.cpp}::SystemZAsmParser::parsePCRel12</a>, <a href="/web-llvm/docs/api/classes/anonymous-systemzasmparser-cpp-/systemzasmparser/#aedd6310a770635f86dd97e4a9cb4e536">anonymous{SystemZAsmParser.cpp}::SystemZAsmParser::parsePCRel16</a>, <a href="/web-llvm/docs/api/classes/anonymous-systemzasmparser-cpp-/systemzasmparser/#aa80f7bd462801a35209abab594da09b0">anonymous{SystemZAsmParser.cpp}::SystemZAsmParser::parsePCRel24</a>, <a href="/web-llvm/docs/api/classes/anonymous-systemzasmparser-cpp-/systemzasmparser/#a3f4355cb530d104dc4ae4c3c15c662ae">anonymous{SystemZAsmParser.cpp}::SystemZAsmParser::parsePCRel32</a>, <a href="/web-llvm/docs/api/classes/anonymous-systemzasmparser-cpp-/systemzasmparser/#a1f0d0b57f624ccda39fb3a853aff15ae">anonymous{SystemZAsmParser.cpp}::SystemZAsmParser::parsePCRelTLS16</a>, <a href="/web-llvm/docs/api/classes/anonymous-systemzasmparser-cpp-/systemzasmparser/#a281378977cb3e48d62d8d3095248a303">anonymous{SystemZAsmParser.cpp}::SystemZAsmParser::parsePCRelTLS32</a>, <a href="/web-llvm/docs/api/classes/anonymous-amdgpuasmparser-cpp-/amdgpuasmparser/#aa73d0a8ecc958df50e46e59e1ad97478">anonymous{AMDGPUAsmParser.cpp}::AMDGPUAsmParser::parseR128A16</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/ve/lib/target/ve/asmparser/veasmparser-cpp/#ad81a87b3f8bbc548c08e343f068aab79">parseRD</a>, <a href="/web-llvm/docs/api/classes/anonymous-amdgpuasmparser-cpp-/amdgpuasmparser/#ab2ca31c142db4eaa8c629f36d61339bf">anonymous{AMDGPUAsmParser.cpp}::AMDGPUAsmParser::parseReg</a>, <a href="/web-llvm/docs/api/classes/anonymous-amdgpuasmparser-cpp-/amdgpuasmparser/#a60728802d4e08feb0abc5cc75c3eefc9">anonymous{AMDGPUAsmParser.cpp}::AMDGPUAsmParser::parseRegOrImm</a>, <a href="/web-llvm/docs/api/classes/anonymous-amdgpuasmparser-cpp-/amdgpuasmparser/#a74b6654d186e55d185e29c67ebd46cc6">anonymous{AMDGPUAsmParser.cpp}::AMDGPUAsmParser::parseRegOrImmWithFPInputMods</a>, <a href="/web-llvm/docs/api/classes/anonymous-amdgpuasmparser-cpp-/amdgpuasmparser/#a2d208597e9458f13c660462e0d3a4a6a">anonymous{AMDGPUAsmParser.cpp}::AMDGPUAsmParser::parseRegOrImmWithIntInputMods</a>, <a href="/web-llvm/docs/api/classes/anonymous-amdgpuasmparser-cpp-/amdgpuasmparser/#a21f740d984294cfbcc067eab247ed24d">anonymous{AMDGPUAsmParser.cpp}::AMDGPUAsmParser::parseRegWithFPInputMods</a>, <a href="/web-llvm/docs/api/classes/anonymous-amdgpuasmparser-cpp-/amdgpuasmparser/#aabf72174f316fbcb2e171c231b94d743">anonymous{AMDGPUAsmParser.cpp}::AMDGPUAsmParser::parseRegWithIntInputMods</a>, <a href="/web-llvm/docs/api/classes/anonymous-amdgpuasmparser-cpp-/amdgpuasmparser/#a1a55d776c65cd09db2546fb584a2de47">anonymous{AMDGPUAsmParser.cpp}::AMDGPUAsmParser::parseScope</a>, <a href="/web-llvm/docs/api/classes/anonymous-amdgpuasmparser-cpp-/amdgpuasmparser/#a493337bf1e3308881e03af9142a5bb5a">anonymous{AMDGPUAsmParser.cpp}::AMDGPUAsmParser::parseSDelayALU</a>, <a href="/web-llvm/docs/api/classes/anonymous-amdgpuasmparser-cpp-/amdgpuasmparser/#a37e7a53cd92512fc5eb8f7a59be76557">anonymous{AMDGPUAsmParser.cpp}::AMDGPUAsmParser::parseSDWADstUnused</a>, <a href="/web-llvm/docs/api/classes/anonymous-amdgpuasmparser-cpp-/amdgpuasmparser/#abb4f66c7a0618aeff77aba400ebda133">anonymous{AMDGPUAsmParser.cpp}::AMDGPUAsmParser::parseSDWASel</a>, <a href="/web-llvm/docs/api/classes/anonymous-amdgpuasmparser-cpp-/amdgpuasmparser/#a7e026648ec951bc9ce02a0e99e31f583">anonymous{AMDGPUAsmParser.cpp}::AMDGPUAsmParser::parseSendMsg</a>, <a href="/web-llvm/docs/api/classes/anonymous-sparcasmparser-cpp-/sparcasmparser/#a2a338087cbd108168ba920ad7906f6b8">anonymous{SparcAsmParser.cpp}::SparcAsmParser::parseShiftAmtImm</a>, <a href="/web-llvm/docs/api/classes/anonymous-webassemblyasmparser-cpp-/webassemblyasmparser/#a5b552ef481435267fbd31f081a657dcb">anonymous{WebAssemblyAsmParser.cpp}::WebAssemblyAsmParser::parseSingleFloat</a>, <a href="/web-llvm/docs/api/classes/anonymous-webassemblyasmparser-cpp-/webassemblyasmparser/#abad1835ebfb774d8120b648346e95ad8">anonymous{WebAssemblyAsmParser.cpp}::WebAssemblyAsmParser::parseSingleInteger</a>, <a href="/web-llvm/docs/api/classes/anonymous-amdgpuasmparser-cpp-/amdgpuasmparser/#a082f5bbf706dd5cd5bcb35d7bdf5564f">anonymous{AMDGPUAsmParser.cpp}::AMDGPUAsmParser::parseSOPPBrTarget</a>, <a href="/web-llvm/docs/api/classes/anonymous-webassemblyasmparser-cpp-/webassemblyasmparser/#a9a2233d6320ffeb67a07589d9a74a369">anonymous{WebAssemblyAsmParser.cpp}::WebAssemblyAsmParser::parseSpecialFloatMaybe</a>, <a href="/web-llvm/docs/api/classes/anonymous-amdgpuasmparser-cpp-/amdgpuasmparser/#a11669d3b022f7e99114faaf694659b89">anonymous{AMDGPUAsmParser.cpp}::AMDGPUAsmParser::parseStringOrIntWithPrefix</a>, <a href="/web-llvm/docs/api/classes/anonymous-amdgpuasmparser-cpp-/amdgpuasmparser/#a066421d8538981830a93a7598a571e8f">anonymous{AMDGPUAsmParser.cpp}::AMDGPUAsmParser::parseStringOrIntWithPrefix</a>, <a href="/web-llvm/docs/api/classes/anonymous-amdgpuasmparser-cpp-/amdgpuasmparser/#ac3b25b92e123263ee61ca38bdee04828">anonymous{AMDGPUAsmParser.cpp}::AMDGPUAsmParser::parseSWaitCnt</a>, <a href="/web-llvm/docs/api/classes/anonymous-amdgpuasmparser-cpp-/amdgpuasmparser/#a45d3320cf47a5c534c3e884ea6501728">anonymous{AMDGPUAsmParser.cpp}::AMDGPUAsmParser::parseSwizzle</a>, <a href="/web-llvm/docs/api/classes/anonymous-sparcasmparser-cpp-/sparcasmparser/#abdef83570b9c07195a0570f8744b2fc0">anonymous{SparcAsmParser.cpp}::SparcAsmParser::parseTailRelocSym</a>, <a href="/web-llvm/docs/api/classes/anonymous-amdgpuasmparser-cpp-/amdgpuasmparser/#a3a4cad862e9d4dda82fe89b5a2557e97">anonymous{AMDGPUAsmParser.cpp}::AMDGPUAsmParser::parseTH</a>, <a href="/web-llvm/docs/api/classes/anonymous-amdgpuasmparser-cpp-/amdgpuasmparser/#a40cae821d596ce5a10da36c3d1836dac">anonymous{AMDGPUAsmParser.cpp}::AMDGPUAsmParser::parseTokenOp</a>, <a href="/web-llvm/docs/api/classes/anonymous-systemzasmparser-cpp-/systemzasmparser/#a1ef54a2d9c4b1ab00ccb7af54edde7f9">anonymous{SystemZAsmParser.cpp}::SystemZAsmParser::parseVF128</a>, <a href="/web-llvm/docs/api/classes/anonymous-amdgpuasmparser-cpp-/amdgpuasmparser/#a4c71cb47a3f1bcc8147c44cc1395ed63">anonymous{AMDGPUAsmParser.cpp}::AMDGPUAsmParser::parseVOPD</a>, <a href="/web-llvm/docs/api/classes/anonymous-systemzasmparser-cpp-/systemzasmparser/#a7738ce96581f5db54604cbcc1589b7c8">anonymous{SystemZAsmParser.cpp}::SystemZAsmParser::parseVR128</a>, <a href="/web-llvm/docs/api/classes/anonymous-systemzasmparser-cpp-/systemzasmparser/#a24db8d8098bd5edd5a345e57ce40a09e">anonymous{SystemZAsmParser.cpp}::SystemZAsmParser::parseVR32</a>, <a href="/web-llvm/docs/api/classes/anonymous-systemzasmparser-cpp-/systemzasmparser/#a6012cb153b6b828dc989a6a81ced6326">anonymous{SystemZAsmParser.cpp}::SystemZAsmParser::parseVR64</a>, <a href="/web-llvm/docs/api/classes/anonymous-amdgpuasmparser-cpp-/amdgpuasmparser/#aad55de4993c720c50d992a7cbda3d8d3">anonymous{AMDGPUAsmParser.cpp}::AMDGPUAsmParser::parseVReg32OrOff</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a5a44455c55b4b88c16930cd31cf4d20b">llvm::prettyPrintBaseTypeRef</a>, <a href="/web-llvm/docs/api/classes/llvm/dwarfexpression/#aeb9094ce3f495cf3f81c2c7aa6a975f5">llvm::DWARFExpression::prettyPrintRegisterOp</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/hexagon/lib/target/hexagon/asmparser/hexagonasmparser-cpp/#a9b92870ea1113bbbf2380a032c4eae73">previousEqual</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/hexagon/lib/target/hexagon/asmparser/hexagonasmparser-cpp/#accda3532bec4aea38f55a77098eb0f75">previousIsLoop</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/riscv/riscvisellowering-cpp/#abdeadd26a96d6a775100a198f9a93082">processVCIXOperands</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/riscv/riscvisellowering-cpp/#a1e4c4f01eb41b2197d78ab15c9dd7b4c">promoteVCIXScalar</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/mips/lib/target/mips/asmparser/mipsasmparser-cpp/#afa1518b04451f89bea1eb5442116a439">RefineErrorLoc</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/xtensa/lib/target/xtensa/asmparser/xtensaasmparser-cpp/#afa1518b04451f89bea1eb5442116a439">RefineErrorLoc</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/arm/lib/target/arm/asmparser/armasmparser-cpp/#a8cb4130d9f8753eb8aa3d106fd74dbdb">removeCCOut</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/arm/lib/target/arm/asmparser/armasmparser-cpp/#accaed50082dc7e7f4e1a2ee2d1705942">removeCondCode</a>, <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/ipo/stripsymbols-cpp/#addcd760c25761414f393db38ac94aad7">RemoveDeadConstant</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/arm/lib/target/arm/asmparser/armasmparser-cpp/#af76ec3d8e5a97454c9a0f8df7cb4b674">removeVPTCondCode</a>, <a href="/web-llvm/docs/api/classes/llvm/constantuniquemap/#ab75052e07cd5f53ef80288b2a4e5f88a">llvm::ConstantUniqueMap&lt; ConstantArray &gt;::replaceOperandsInPlace</a>, <a href="/web-llvm/docs/api/classes/anonymous-armasmparser-cpp-/armasmparser/#abe395f22cd402da225ebfe07e79bc053">anonymous{ARMAsmParser.cpp}::ARMAsmParser::ReportNearMisses</a>, <a href="/web-llvm/docs/api/classes/llvm/sandboxir/erasefromparent/#a9ba180aa3a4465acc6759c0f8fe30268">llvm::sandboxir::EraseFromParent::revert</a>, <a href="/web-llvm/docs/api/classes/llvm/scalarevolution/loopguards/#afc980d8379c6a1d12d091ba6b33aa05f">llvm::ScalarEvolution::LoopGuards::rewrite</a>, <a href="/web-llvm/docs/api/classes/llvm/riscvdagtodagisel/#a7d60a41c0d5e450f770042d3427928d0">llvm::RISCVDAGToDAGISel::Select</a>, <a href="/web-llvm/docs/api/classes/llvm/selectiondagisel/#a624f21782a600e972eacbae3e4818fcc">llvm::SelectionDAGISel::SelectCodeCommon</a>, <a href="/web-llvm/docs/api/classes/llvm/riscvdagtodagisel/#a491dd364e0fd3440074a55eeec66b267">llvm::RISCVDAGToDAGISel::selectSF_VC_X_SE</a>, <a href="/web-llvm/docs/api/classes/llvm/riscvdagtodagisel/#a8fa52705ef408e923efaab38cd62597a">llvm::RISCVDAGToDAGISel::selectVLSEG</a>, <a href="/web-llvm/docs/api/classes/llvm/riscvdagtodagisel/#a4165c3b90d08f85ae15b915d4d4bdf65">llvm::RISCVDAGToDAGISel::selectVLSEGFF</a>, <a href="/web-llvm/docs/api/classes/llvm/riscvdagtodagisel/#af390be4480c0588fa6c3fc6cd05e4166">llvm::RISCVDAGToDAGISel::selectVLXSEG</a>, <a href="/web-llvm/docs/api/classes/llvm/riscvdagtodagisel/#abf23f63b97b9f5f99c3dd3c3a986e418">llvm::RISCVDAGToDAGISel::selectVSSEG</a>, <a href="/web-llvm/docs/api/classes/llvm/riscvdagtodagisel/#a35a4f3715a02bc5b5d9ced3b5324f439">llvm::RISCVDAGToDAGISel::selectVSXSEG</a>, <a href="/web-llvm/docs/api/classes/anonymous-irnormalizer-cpp-/irnormalizer/#a8b47bdab305c78760e89e5fb43dfb5e2">anonymous{IRNormalizer.cpp}::IRNormalizer::sortCommutativeOperands</a>, <a href="/web-llvm/docs/api/classes/anonymous-hexagonasmparser-cpp-/hexagonasmparser/#a7bdaa9e163b23aed343a6a8f7589d008">anonymous{HexagonAsmParser.cpp}::HexagonAsmParser::splitIdentifier</a>, <a href="/web-llvm/docs/api/classes/anonymous-aarch64asmparser-cpp-/aarch64asmparser/#a246c8dfd4ca957b7da4d52cb7805650c">anonymous{AArch64AsmParser.cpp}::AArch64AsmParser::tryParseAdjImm0_63</a>, <a href="/web-llvm/docs/api/classes/anonymous-aarch64asmparser-cpp-/aarch64asmparser/#a0ff7af77f414b9796ed948a2723f6199">anonymous{AArch64AsmParser.cpp}::AArch64AsmParser::tryParseFPImm</a>, <a href="/web-llvm/docs/api/classes/anonymous-aarch64asmparser-cpp-/aarch64asmparser/#a72482e46711748fee7ce49e1d66002de">anonymous{AArch64AsmParser.cpp}::AArch64AsmParser::tryParseGPROperand</a>, <a href="/web-llvm/docs/api/classes/anonymous-amdgpuasmparser-cpp-/amdgpuasmparser/#a971176e60129a0824a8c1e2a193e6b62">anonymous{AMDGPUAsmParser.cpp}::AMDGPUAsmParser::tryParseIndexKey</a>, <a href="/web-llvm/docs/api/classes/anonymous-aarch64asmparser-cpp-/aarch64asmparser/#a3836dbcbb0e7b8207e5b1f40a85269af">anonymous{AArch64AsmParser.cpp}::AArch64AsmParser::tryParsePrefetch</a>, <a href="/web-llvm/docs/api/classes/anonymous-aarch64asmparser-cpp-/aarch64asmparser/#aedd4ddd3d36c07298e0d1c8ea2903593">anonymous{AArch64AsmParser.cpp}::AArch64AsmParser::tryParseSVEDataVector</a>, <a href="/web-llvm/docs/api/classes/anonymous-aarch64asmparser-cpp-/aarch64asmparser/#aef98635d49b1c38ba8b291b28df6a62d">anonymous{AArch64AsmParser.cpp}::AArch64AsmParser::tryParseSVEPredicateVector</a>, <a href="/web-llvm/docs/api/classes/anonymous-aarch64asmparser-cpp-/aarch64asmparser/#ac039137a2de44626abac897fe2382ef7">anonymous{AArch64AsmParser.cpp}::AArch64AsmParser::tryParseVectorList</a>, <a href="/web-llvm/docs/api/classes/llvm/vprecipebuilder/#a06a097fb3e3b640d70709b4770408024">llvm::VPRecipeBuilder::tryToCreatePartialReduction</a>, <a href="/web-llvm/docs/api/classes/llvm/vprecipebuilder/#a760fb390c24b907500c0a181fada9590">llvm::VPRecipeBuilder::tryToCreateWidenRecipe</a>, <a href="/web-llvm/docs/api/classes/llvm/webassemblyasmtypecheck/#ad05058e6bb44815e9906be40ff6bb88d">llvm::WebAssemblyAsmTypeCheck::typeCheck</a>, <a href="/web-llvm/docs/api/classes/llvm/selectiondag/#a305a3a4874c597243cd5ba04af01339e">llvm::SelectionDAG::UnrollVectorOp</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/powerpc/lib/target/powerpc/asmparser/ppcasmparser-cpp/#a185e7e0c07e5d9a0faa11b0ab5f40b97">validateMemOp</a>, <a href="/web-llvm/docs/api/classes/llvm/scevrewritevisitor/#a526f03cb420e8f64cd03750939bff699">llvm::SCEVRewriteVisitor&lt; SC &gt;::visitAddExpr</a>, <a href="/web-llvm/docs/api/structs/anonymous-scalarevolutionnormalization-cpp-/normalizedenormalizerewriter/#ac9bcd9133d19e4e656a82dd8e900d3f8">anonymous{ScalarEvolutionNormalization.cpp}::NormalizeDenormalizeRewriter::visitAddRecExpr</a>, <a href="/web-llvm/docs/api/classes/llvm/scevloopaddrecrewriter/#a286583ef8d17944c4d4a4e3abcf65fef">llvm::SCEVLoopAddRecRewriter::visitAddRecExpr</a>, <a href="/web-llvm/docs/api/classes/llvm/scevrewritevisitor/#ae7723e8cfb7ea733908442f8ef2d5d85">llvm::SCEVRewriteVisitor&lt; SC &gt;::visitAddRecExpr</a>, <a href="/web-llvm/docs/api/classes/llvm/scevrewritevisitor/#a7ba1cee011d4868e8966a81a41ffff38">llvm::SCEVRewriteVisitor&lt; SC &gt;::visitMulExpr</a>, <a href="/web-llvm/docs/api/classes/llvm/scevrewritevisitor/#a4a27c503b298dbe2a78b945b8c9025f6">llvm::SCEVRewriteVisitor&lt; SC &gt;::visitSequentialUMinExpr</a>, <a href="/web-llvm/docs/api/classes/llvm/scevrewritevisitor/#ac90f8a765813f19c8c20f90153a7cc82">llvm::SCEVRewriteVisitor&lt; SC &gt;::visitSMaxExpr</a>, <a href="/web-llvm/docs/api/classes/llvm/scevrewritevisitor/#a38b17b6e44b9937c10d4a4277a7abecb">llvm::SCEVRewriteVisitor&lt; SC &gt;::visitSMinExpr</a>, <a href="/web-llvm/docs/api/classes/llvm/scevrewritevisitor/#aba42491077efa5e60b2c439f0a59a645">llvm::SCEVRewriteVisitor&lt; SC &gt;::visitUMaxExpr</a>, <a href="/web-llvm/docs/api/classes/llvm/scevrewritevisitor/#a5481db1a659c011e71a0a75ce7416735">llvm::SCEVRewriteVisitor&lt; SC &gt;::visitUMinExpr</a>, <a href="/web-llvm/docs/api/classes/llvm/vpinstruction/#a432b57e3924afb475fc91aafb56b5e0d">llvm::VPInstruction::VPInstruction</a>, <a href="/web-llvm/docs/api/classes/llvm/vpinstruction/#aaab87e71e2ce50030cb513bc3151eef9">llvm::VPInstruction::VPInstruction</a>, <a href="/web-llvm/docs/api/classes/llvm/vpinstruction/#ab8ab6c89f88924902569eab504c112e8">llvm::VPInstruction::VPInstruction</a>, <a href="/web-llvm/docs/api/classes/llvm/vpinstruction/#a256e4c0d88c74db616499748f0a224a1">llvm::VPInstruction::VPInstruction</a>, <a href="/web-llvm/docs/api/classes/llvm/vpinstruction/#aa008922f90e2a3966fb4582c3abd4f1d">llvm::VPInstruction::VPInstruction</a>, <a href="/web-llvm/docs/api/classes/llvm/vpreplicaterecipe/#acb424057b318d4f0d94f58c87edb8e54">llvm::VPReplicateRecipe::VPReplicateRecipe</a>, <a href="/web-llvm/docs/api/classes/llvm/vpwidenevlrecipe/#a46b99b127f56b83e8e377f47db747158">llvm::VPWidenEVLRecipe::VPWidenEVLRecipe</a>, <a href="/web-llvm/docs/api/classes/llvm/vpwidengeprecipe/#ae1555a62444119fa96252a26dcf4894a">llvm::VPWidenGEPRecipe::VPWidenGEPRecipe</a>, <a href="/web-llvm/docs/api/classes/llvm/vpwidenrecipe/#a9ba7a710745a037bdc5fd84132906f3b">llvm::VPWidenRecipe::VPWidenRecipe</a>, <a href="/web-llvm/docs/api/classes/llvm/vpwidenrecipe/#ab536824eb33f00c91befa326c11c1570">llvm::VPWidenRecipe::VPWidenRecipe</a>, <a href="/web-llvm/docs/api/structs/llvm/vpwidenselectrecipe/#a15b2d34037ce5ecddecce8d53a2ce7cf">llvm::VPWidenSelectRecipe::VPWidenSelectRecipe</a>, <a href="/web-llvm/docs/api/classes/llvm/logicalview/lvlocationsymbol/#abee93c48073d99494fe4bf3932f43364">llvm::logicalview::LVLocationSymbol::~LVLocationSymbol</a> and <a href="/web-llvm/docs/api/classes/llvm/vplanslp/#a96f922c1baaec337b43042bf26f641cb">llvm::VPlanSlp::~VPlanSlp</a>.</p>

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
<td class="doxyMemberName">#define DEBUG_TYPE&nbsp;&nbsp;&nbsp;"mir-namer"</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 30 of file <a href="/web-llvm/docs/api/files/lib/lib/codegen/mirnamerpass-cpp">MIRNamerPass.cpp</a>.</p>

</div>
</div>

</div>

<hr/>

<p class="doxyGeneratedBy">Generated via <a href="https://github.com/xpack/doxygen2docusaurus">doxygen2docusaurus</a> by <a href="https://www.doxygen.nl">Doxygen</a> 1.14.0.</p>

</div>
