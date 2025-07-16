---

# DO NOT EDIT!
# Automatically generated via doxygen2docusaurus by Doxygen.

slug: /api/files/lib/lib/target/lib/target/spirv/spirvtargetmachine-cpp
custom_edit_url: null
toc_max_heading_level: 4
keywords:
  - doxygen
  - reference
  - file

---

<div class="doxyPage">

# The `SPIRVTargetMachine.cpp` File Reference



## Included Headers

<div class="doxyIncludesList">#include "<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/spirv/spirvtargetmachine-h">SPIRVTargetMachine.h</a>"
#include "<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/spirv/spirv-h">SPIRV.h</a>"
#include "<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/spirv/spirvcalllowering-h">SPIRVCallLowering.h</a>"
#include "<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/spirv/spirvglobalregistry-h">SPIRVGlobalRegistry.h</a>"
#include "<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/spirv/spirvlegalizerinfo-h">SPIRVLegalizerInfo.h</a>"
#include "<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/spirv/spirvstructurizerwrapper-h">SPIRVStructurizerWrapper.h</a>"
#include "<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/spirv/spirvtargetobjectfile-h">SPIRVTargetObjectFile.h</a>"
#include "<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/spirv/spirvtargettransforminfo-h">SPIRVTargetTransformInfo.h</a>"
#include "<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/spirv/lib/target/spirv/targetinfo/spirvtargetinfo-h">TargetInfo/SPIRVTargetInfo.h</a>"
#include "<a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/codegen/include/llvm/codegen/globalisel/irtranslator-h">llvm/CodeGen/GlobalISel/IRTranslator.h</a>"
#include "<a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/codegen/include/llvm/codegen/globalisel/instructionselect-h">llvm/CodeGen/GlobalISel/InstructionSelect.h</a>"
#include "<a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/codegen/include/llvm/codegen/globalisel/legalizer-h">llvm/CodeGen/GlobalISel/Legalizer.h</a>"
#include "<a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/codegen/include/llvm/codegen/globalisel/regbankselect-h">llvm/CodeGen/GlobalISel/RegBankSelect.h</a>"
#include "<a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/codegen/passes-h">llvm/CodeGen/Passes.h</a>"
#include "<a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/codegen/targetloweringobjectfileimpl-h">llvm/CodeGen/TargetLoweringObjectFileImpl.h</a>"
#include "<a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/codegen/targetpassconfig-h">llvm/CodeGen/TargetPassConfig.h</a>"
#include "<a href="/web-llvm/docs/api/files/include/include/llvm/initializepasses-h">llvm/InitializePasses.h</a>"
#include "<a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/mc/targetregistry-h">llvm/MC/TargetRegistry.h</a>"
#include "<a href="/web-llvm/docs/api/files/include/include/llvm/pass-h">llvm/Pass.h</a>"
#include "<a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/passes/passbuilder-h">llvm/Passes/PassBuilder.h</a>"
#include "<a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/target/targetoptions-h">llvm/Target/TargetOptions.h</a>"
#include "<a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/transforms/include/llvm/transforms/scalar/reg2mem-h">llvm/Transforms/Scalar/Reg2Mem.h</a>"
#include "<a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/transforms/utils-h">llvm/Transforms/Utils.h</a>"
#include &lt;optional&gt;
#include "llvm/Passes/TargetPassRegistry.inc"
</div>

## Namespaces Index

<table class="doxyMembersIndex">

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">namespace</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="/web-llvm/docs/api/namespaces/anonymous-spirvtargetmachine-cpp-">anonymous{SPIRVTargetMachine.cpp}</a></td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="/web-llvm/docs/api/classes/anonymous-spirvtargetmachine-cpp-/spirvpassconfig">SPIRVPassConfig</a></td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">class</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="/web-llvm/docs/api/classes/anonymous-spirvtargetmachine-cpp-/spirvinstructionselect">SPIRVInstructionSelect</a></td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/support/compiler-h/#adeb6f14d9f377993d79fae2efb34ecac">LLVM_EXTERNAL_VISIBILITY</a> void</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#aa3b9ca78bbd44f9b9c4417b261aa1175">LLVMInitializeSPIRVTarget</a> ()</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">static <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/demangle/itaniumdemangle-h/#ae2b0d0345572d6718e219aa76d1d54edab45cffe084dd3d20d928bee85e7b0f21">std::string</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#aefdbcd6131ef195da070cef7fdaf0532">computeDataLayout</a> (const Triple &amp;TT)</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">static <a href="/web-llvm/docs/api/namespaces/llvm/reloc/#af59f6dc86e80aaf56f1afd155eebf568">Reloc::Model</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a906e08cf722c544eeff0ae4295cdc0e9">getEffectiveRelocModel</a> (std::optional&lt; Reloc::Model &gt; RM)</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">static <a href="/web-llvm/docs/api/classes/llvm/cl/opt">cl::opt</a>&lt; bool &gt;</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ac77e1ee06f61d312b16f5250e6f6c17e">SPVEnableNonSemanticDI</a>("spv-emit-nonsemantic-debug-info", cl::desc("Emit SPIR-V NonSemantic.Shader.DebugInfo.100 instructions"), cl::Optional, cl::init(false))</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#aba71ac83fc0882e97760c16e84ed9599">GET_PASS_REGISTRY</a>&nbsp;&nbsp;&nbsp;"SPIRVPassRegistry.def"</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a785883ec0154b6773dd0c47b13588a1a">ADD_CLASS_PASS_TO_PASS_NAME</a>(NAME, CREATE_PASS)&nbsp;&nbsp;&nbsp;  <a href="/web-llvm/docs/api/files/lib/lib/passes/passbuilderbindings-cpp/#ad4d247df65c12507f447383be37d7ccb">PIC</a>-&gt;addClassToPassName(decltype(CREATE_PASS)<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/smeabipass-cpp/#a8f8f80d37794cde9472343e4487ba3eb">::name</a>(), NAME);</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a30af641d5b42457b0cb49ad7eeeba6d3">ADD_CLASS_PASS_TO_PASS_NAME_WITH_PARAMS</a>(NAME, CLASS)&nbsp;&nbsp;&nbsp;  <a href="/web-llvm/docs/api/files/lib/lib/passes/passbuilderbindings-cpp/#ad4d247df65c12507f447383be37d7ccb">PIC</a>-&gt;addClassToPassName(CLASS, NAME);</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ae630e66bd51cb0c84874bd406b12f4a3">MODULE_ANALYSIS</a>(NAME, CREATE_PASS)&nbsp;&nbsp;&nbsp;  <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/amdgputargetmachine-cpp/#a785883ec0154b6773dd0c47b13588a1a">ADD_CLASS_PASS_TO_PASS_NAME</a>(NAME, CREATE_PASS)</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a582c86fdb6a64efb8ec4a59327aa6793">MODULE_PASS</a>(NAME, CREATE_PASS)&nbsp;&nbsp;&nbsp;  <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/amdgputargetmachine-cpp/#a785883ec0154b6773dd0c47b13588a1a">ADD_CLASS_PASS_TO_PASS_NAME</a>(NAME, CREATE_PASS)</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a97a1c5adfbad7cfb551750d9dec6b013">MODULE_PASS_WITH_PARAMS</a>(NAME, CLASS, CREATE_PASS, PARSER, PARAMS)&nbsp;&nbsp;&nbsp;  <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/amdgputargetmachine-cpp/#a30af641d5b42457b0cb49ad7eeeba6d3">ADD_CLASS_PASS_TO_PASS_NAME_WITH_PARAMS</a>(NAME, CLASS)</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a67c895b5207a31e73cf972bb58ab5aa9">FUNCTION_ANALYSIS</a>(NAME, CREATE_PASS)&nbsp;&nbsp;&nbsp;  <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/amdgputargetmachine-cpp/#a785883ec0154b6773dd0c47b13588a1a">ADD_CLASS_PASS_TO_PASS_NAME</a>(NAME, CREATE_PASS)</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a613be0a47ad4283b033171c7d91ebce9">FUNCTION_ALIAS_ANALYSIS</a>(NAME, CREATE_PASS)&nbsp;&nbsp;&nbsp;  <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/amdgputargetmachine-cpp/#a785883ec0154b6773dd0c47b13588a1a">ADD_CLASS_PASS_TO_PASS_NAME</a>(NAME, CREATE_PASS)</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a6263fb21d44822c311d528df14c7d1d3">FUNCTION_PASS</a>(NAME, CREATE_PASS)&nbsp;&nbsp;&nbsp;  <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/amdgputargetmachine-cpp/#a785883ec0154b6773dd0c47b13588a1a">ADD_CLASS_PASS_TO_PASS_NAME</a>(NAME, CREATE_PASS)</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a39f2a031848ee3c43432d32ba6d42300">FUNCTION_PASS_WITH_PARAMS</a>(NAME, CLASS, CREATE_PASS, PARSER, PARAMS)&nbsp;&nbsp;&nbsp;  <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/amdgputargetmachine-cpp/#a30af641d5b42457b0cb49ad7eeeba6d3">ADD_CLASS_PASS_TO_PASS_NAME_WITH_PARAMS</a>(NAME, CLASS)</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a153ed55c08dcea6b7bee890741e2465f">LOOP_ANALYSIS</a>(NAME, CREATE_PASS)&nbsp;&nbsp;&nbsp;  <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/amdgputargetmachine-cpp/#a785883ec0154b6773dd0c47b13588a1a">ADD_CLASS_PASS_TO_PASS_NAME</a>(NAME, CREATE_PASS)</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a54aaec23a0af37818d0b521b9c7cd10d">LOOP_PASS</a>(NAME, CREATE_PASS)&nbsp;&nbsp;&nbsp;  <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/amdgputargetmachine-cpp/#a785883ec0154b6773dd0c47b13588a1a">ADD_CLASS_PASS_TO_PASS_NAME</a>(NAME, CREATE_PASS)</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ae8bee684ed42fc73cd9184c6c924b57c">MACHINE_FUNCTION_ANALYSIS</a>(NAME, CREATE_PASS)&nbsp;&nbsp;&nbsp;  <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/amdgputargetmachine-cpp/#a785883ec0154b6773dd0c47b13588a1a">ADD_CLASS_PASS_TO_PASS_NAME</a>(NAME, CREATE_PASS)</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a70051016d8672632182efe9799c4c083">MACHINE_FUNCTION_PASS</a>(NAME, CREATE_PASS)&nbsp;&nbsp;&nbsp;  <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/amdgputargetmachine-cpp/#a785883ec0154b6773dd0c47b13588a1a">ADD_CLASS_PASS_TO_PASS_NAME</a>(NAME, CREATE_PASS)</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a41d7c2793b719b960a6cf9b5fe2aa4e8">MACHINE_FUNCTION_PASS_WITH_PARAMS</a>(NAME, CLASS, CREATE_PASS, PARSER, PARAMS)&nbsp;&nbsp;&nbsp;  <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/amdgputargetmachine-cpp/#a30af641d5b42457b0cb49ad7eeeba6d3">ADD_CLASS_PASS_TO_PASS_NAME_WITH_PARAMS</a>(NAME, CLASS)</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a7e81816a66f7a306d304777ce3b1d3dc">ADD_PASS</a>(NAME, CREATE_PASS)&nbsp;&nbsp;&nbsp;...</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a60cfccc5fc706d773a18ba77db9c807f">ADD_PASS_WITH_PARAMS</a>(NAME, CREATE_PASS, PARSER)&nbsp;&nbsp;&nbsp;...</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a0b0ff03a6bb4a70e73fd5083c3679e52">MODULE_PASS</a>(NAME, CREATE_PASS)&nbsp;&nbsp;&nbsp;<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/amdgputargetmachine-cpp/#a7e81816a66f7a306d304777ce3b1d3dc">ADD_PASS</a>(NAME, CREATE_PASS)</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a7500ad7948c3ddde5d682816f775f4e1">MODULE_PASS_WITH_PARAMS</a>(NAME, CLASS, CREATE_PASS, PARSER, PARAMS)&nbsp;&nbsp;&nbsp;  <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/amdgputargetmachine-cpp/#a60cfccc5fc706d773a18ba77db9c807f">ADD_PASS_WITH_PARAMS</a>(NAME, CREATE_PASS, PARSER)</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a2fe799143be34291491c183ed9c0eea7">FUNCTION_PASS</a>(NAME, CREATE_PASS)&nbsp;&nbsp;&nbsp;<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/amdgputargetmachine-cpp/#a7e81816a66f7a306d304777ce3b1d3dc">ADD_PASS</a>(NAME, CREATE_PASS)</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a311ebbf608e96c2cf18b6720168da442">FUNCTION_PASS_WITH_PARAMS</a>(NAME, CLASS, CREATE_PASS, PARSER, PARAMS)&nbsp;&nbsp;&nbsp;  <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/amdgputargetmachine-cpp/#a60cfccc5fc706d773a18ba77db9c807f">ADD_PASS_WITH_PARAMS</a>(NAME, CREATE_PASS, PARSER)</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a23c129b1a117c00315516028a20df042">LOOP_PASS</a>(NAME, CREATE_PASS)&nbsp;&nbsp;&nbsp;<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/amdgputargetmachine-cpp/#a7e81816a66f7a306d304777ce3b1d3dc">ADD_PASS</a>(NAME, CREATE_PASS)</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ac6116ae7b86d8db66ba2cf3f1f061ce1">MACHINE_FUNCTION_PASS</a>(NAME, CREATE_PASS)&nbsp;&nbsp;&nbsp;<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/amdgputargetmachine-cpp/#a7e81816a66f7a306d304777ce3b1d3dc">ADD_PASS</a>(NAME, CREATE_PASS)</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a0e7b7a2c70f63ae1138cb04e1479bf2e">MACHINE_FUNCTION_PASS_WITH_PARAMS</a>(NAME, CLASS, CREATE_PASS, PARSER, PARAMS)&nbsp;&nbsp;&nbsp;  <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/amdgputargetmachine-cpp/#a60cfccc5fc706d773a18ba77db9c807f">ADD_PASS_WITH_PARAMS</a>(NAME, CREATE_PASS, PARSER)</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a0dec599234592c714174fee76a88c710">MODULE_ANALYSIS</a>(NAME, CREATE_PASS)&nbsp;&nbsp;&nbsp;  AM.registerPass([&amp;] { return CREATE_PASS; });</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a2873b9291c09bb8bac44be66f5f79b0c">FUNCTION_ANALYSIS</a>(NAME, CREATE_PASS)&nbsp;&nbsp;&nbsp;  AM.registerPass([&amp;] { return CREATE_PASS; });</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a53b4a11b77c533a402e27bd36033e5f5">FUNCTION_ALIAS_ANALYSIS</a>(NAME, CREATE_PASS)&nbsp;&nbsp;&nbsp;...</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a4c6fd949900e2be4f909ae96a018bef9">LOOP_ANALYSIS</a>(NAME, CREATE_PASS)&nbsp;&nbsp;&nbsp;  AM.registerPass([&amp;] { return CREATE_PASS; });</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a304fa0b7b45d6b32d5742c05f852b1f2">MACHINE_FUNCTION_ANALYSIS</a>(NAME, CREATE_PASS)&nbsp;&nbsp;&nbsp;  AM.registerPass([&amp;] { return CREATE_PASS; });</td>
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

### computeDataLayout() {#aefdbcd6131ef195da070cef7fdaf0532}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">std::string computeDataLayout (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/triple">Triple</a> &amp; TT)</td>
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



<p>Definition at line 54 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/spirv/spirvtargetmachine-cpp">SPIRVTargetMachine.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/classes/llvm/triple/#a96fe35195867c94aef1adf2ad0e20eeca77be73c19a4451fa0580ac5b9018357b">llvm::Triple::AMD</a>, <a href="/web-llvm/docs/api/classes/llvm/triple/#a3cfefc755ab656000934f91193afb1cda0a0dddcf03f8f66f7c13558b3c81d845">llvm::Triple::AMDHSA</a> and <a href="/web-llvm/docs/api/classes/llvm/triple/#a547abd13f7a3c063aa72c8192a868154afc429c7efea3699ead2afe26b7db09df">llvm::Triple::spirv32</a>.</p>

</div>
</div>

### getEffectiveRelocModel() {#a906e08cf722c544eeff0ae4295cdc0e9}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">Reloc::Model getEffectiveRelocModel (std::optional&lt; <a href="/web-llvm/docs/api/namespaces/llvm/reloc/#af59f6dc86e80aaf56f1afd155eebf568">Reloc::Model</a> &gt; RM)</td>
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



<p>Definition at line 72 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/spirv/spirvtargetmachine-cpp">SPIRVTargetMachine.cpp</a>.</p>


<p>Reference <a href="/web-llvm/docs/api/namespaces/llvm/reloc/#af59f6dc86e80aaf56f1afd155eebf568adc2075e13a68142b26e05ac08bbfc320">llvm::Reloc::PIC_</a>.</p>

</div>
</div>

### LLVMInitializeSPIRVTarget() {#aa3b9ca78bbd44f9b9c4417b261aa1175}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">LLVM_EXTERNAL_VISIBILITY void LLVMInitializeSPIRVTarget ()</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 40 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/spirv/spirvtargetmachine-cpp">SPIRVTargetMachine.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/classes/llvm/passregistry/#a05a729900b76c89e808c6c3094921b2f">llvm::PassRegistry::getPassRegistry</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a20fa774c08e0782fb15cf575c66e4825">llvm::getTheSPIRV32Target</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a94dbd3c342b8a45d80840da6846bd4cc">llvm::getTheSPIRV64Target</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#aa89d0cf3231444c3a2e29a98a82bcd75">llvm::getTheSPIRVLogicalTarget</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#aa096f48562c0dd3a59ef81dd9126239a">llvm::initializeGlobalISel</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#adaa44393ed0798adda014d62bd9bffbe">llvm::initializeSPIRVConvergenceRegionAnalysisWrapperPassPass</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a5e8de101b8e8ca2d8c925d1a5aa46424">llvm::initializeSPIRVModuleAnalysisPass</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a5239c818e6fa8771fcf97cbf5b0c46d3">llvm::initializeSPIRVPreLegalizerCombinerPass</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#abb0ce1887c5b0d934a3f8dee52ee2904">llvm::initializeSPIRVStructurizerPass</a>, <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/support/compiler-h/#adeb6f14d9f377993d79fae2efb34ecac">LLVM_EXTERNAL_VISIBILITY</a>, <a href="/web-llvm/docs/api/files/lib/lib/tablegen/tablegenbackendskeleton-cpp/#ab60f28d7a141ac46ccc200176a1bca8b">X</a> and <a href="/web-llvm/docs/api/files/lib/lib/tablegen/tablegenbackendskeleton-cpp/#a262774d3e5186511427e5b2414a85f7f">Y</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/namespaces/anonymous-spirvapi-cpp-/#aab23f4c76e5ebe2ab3d8ae0a0babffc6">anonymous{SPIRVAPI.cpp}::InitializeSPIRVTarget</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Variables

### SPVEnableNonSemanticDI {#ac77e1ee06f61d312b16f5250e6f6c17e}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">cl::opt&lt; bool &gt; SPVEnableNonSemanticDI("spv-emit-nonsemantic-debug-info", cl::desc("Emit SPIR-V NonSemantic.Shader.DebugInfo.100 instructions"), cl::Optional, cl::init(false))</td>
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



<p>Definition at line 238 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/spirv/spirvtargetmachine-cpp">SPIRVTargetMachine.cpp</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/classes/anonymous-spirvtargetmachine-cpp-/spirvpassconfig/#a2d6613bd083d0f038d36a9b65ac3dfd1">anonymous{SPIRVTargetMachine.cpp}::SPIRVPassConfig::addPreEmitPass</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Macro Definitions

### ADD\_CLASS\_PASS\_TO\_PASS\_NAME {#a785883ec0154b6773dd0c47b13588a1a}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">#define ADD_CLASS_PASS_TO_PASS_NAME(NAME, CREATE_PASS)&nbsp;&nbsp;&nbsp;  <a href="/web-llvm/docs/api/files/lib/lib/passes/passbuilderbindings-cpp/#ad4d247df65c12507f447383be37d7ccb">PIC</a>-&gt;addClassToPassName(decltype(CREATE_PASS)<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/smeabipass-cpp/#a8f8f80d37794cde9472343e4487ba3eb">::name</a>(), NAME);</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 30 of file TargetPassRegistry.inc.</p>

</div>
</div>

### ADD\_CLASS\_PASS\_TO\_PASS\_NAME\_WITH\_PARAMS {#a30af641d5b42457b0cb49ad7eeeba6d3}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">#define ADD_CLASS_PASS_TO_PASS_NAME_WITH_PARAMS(NAME, CLASS)&nbsp;&nbsp;&nbsp;  <a href="/web-llvm/docs/api/files/lib/lib/passes/passbuilderbindings-cpp/#ad4d247df65c12507f447383be37d7ccb">PIC</a>-&gt;addClassToPassName(CLASS, NAME);</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 32 of file TargetPassRegistry.inc.</p>

</div>
</div>

### ADD\_PASS {#a7e81816a66f7a306d304777ce3b1d3dc}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">#define ADD_PASS(NAME, CREATE_PASS)&nbsp;&nbsp;&nbsp;...</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<dl class="doxySectionUser">
<dt>Value</dt>
<dd>
<div class="doxyVerbatim">  <a href="/web-llvm/docs/api/files/lib/lib/passes/passbuilderbindings-cpp/#acdfbcf188e2d4a80837e89de2ccdffab">if</a> (Name == NAME) {                                                          \
    PM.addPass(CREATE_PASS);                                                   \
    return <a href="/web-llvm/docs/api/files/lib/lib/analysis/basicaliasanalysis-cpp/#af6d5cafbdfc5313e65d990120021a3ec">true</a>;                                                               \
  }
</div>
</dd>
</dl>

<p>Definition at line 78 of file TargetPassRegistry.inc.</p>

</div>
</div>

### ADD\_PASS\_WITH\_PARAMS {#a60cfccc5fc706d773a18ba77db9c807f}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">#define ADD_PASS_WITH_PARAMS(NAME, CREATE_PASS, PARSER)&nbsp;&nbsp;&nbsp;...</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<dl class="doxySectionUser">
<dt>Value</dt>
<dd>
<div class="doxyVerbatim">  <a href="/web-llvm/docs/api/files/lib/lib/passes/passbuilderbindings-cpp/#acdfbcf188e2d4a80837e89de2ccdffab">if</a> (PassBuilder::checkParametrizedPassName(Name, NAME)) {                    \
    auto Params = PassBuilder::parsePassParameters(PARSER, Name, NAME);        \
    <a href="/web-llvm/docs/api/files/lib/lib/passes/passbuilderbindings-cpp/#acdfbcf188e2d4a80837e89de2ccdffab">if</a> (!Params) {                                                             \
      errs() &lt;&lt; NAME ": " &lt;&lt; <a href="/web-llvm/docs/api/files/lib/lib/codegen/lib/codegen/mirparser/miparser-cpp/#a7206d13e3a41147c732071c64bd84825">toString</a>(Params.takeError()) &lt;&lt; '\n';             \
      return false;                                                            \
    }                                                                          \
    PM.addPass(CREATE_PASS(Params.get()));                                     \
    return <a href="/web-llvm/docs/api/files/lib/lib/analysis/basicaliasanalysis-cpp/#af6d5cafbdfc5313e65d990120021a3ec">true</a>;                                                               \
  }
</div>
</dd>
</dl>

<p>Definition at line 84 of file TargetPassRegistry.inc.</p>

</div>
</div>

### FUNCTION\_ALIAS\_ANALYSIS {#a613be0a47ad4283b033171c7d91ebce9}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">#define FUNCTION_ALIAS_ANALYSIS(NAME, CREATE_PASS)&nbsp;&nbsp;&nbsp;  <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/amdgputargetmachine-cpp/#a785883ec0154b6773dd0c47b13588a1a">ADD_CLASS_PASS_TO_PASS_NAME</a>(NAME, CREATE_PASS)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 43 of file TargetPassRegistry.inc.</p>

</div>
</div>

### FUNCTION\_ALIAS\_ANALYSIS {#a53b4a11b77c533a402e27bd36033e5f5}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">#define FUNCTION_ALIAS_ANALYSIS(NAME, CREATE_PASS)&nbsp;&nbsp;&nbsp;...</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<dl class="doxySectionUser">
<dt>Value</dt>
<dd>
<div class="doxyVerbatim">  <a href="/web-llvm/docs/api/files/lib/lib/passes/passbuilderbindings-cpp/#acdfbcf188e2d4a80837e89de2ccdffab">if</a> (Name == NAME) {                                                          \
    AM.registerFunctionAnalysis&lt;                                               \
        std::remove_reference_t&lt;decltype(CREATE_PASS)&gt;&gt;();                     \
    return <a href="/web-llvm/docs/api/files/lib/lib/analysis/basicaliasanalysis-cpp/#af6d5cafbdfc5313e65d990120021a3ec">true</a>;                                                               \
  }
</div>
</dd>
</dl>

<p>Definition at line 172 of file TargetPassRegistry.inc.</p>

</div>
</div>

### FUNCTION\_ANALYSIS {#a67c895b5207a31e73cf972bb58ab5aa9}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">#define FUNCTION_ANALYSIS(NAME, CREATE_PASS)&nbsp;&nbsp;&nbsp;  <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/amdgputargetmachine-cpp/#a785883ec0154b6773dd0c47b13588a1a">ADD_CLASS_PASS_TO_PASS_NAME</a>(NAME, CREATE_PASS)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 41 of file TargetPassRegistry.inc.</p>

</div>
</div>

### FUNCTION\_ANALYSIS {#a2873b9291c09bb8bac44be66f5f79b0c}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">#define FUNCTION_ANALYSIS(NAME, CREATE_PASS)&nbsp;&nbsp;&nbsp;  AM.registerPass([&amp;] { return CREATE_PASS; });</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 165 of file TargetPassRegistry.inc.</p>

</div>
</div>

### FUNCTION\_PASS {#a6263fb21d44822c311d528df14c7d1d3}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">#define FUNCTION_PASS(NAME, CREATE_PASS)&nbsp;&nbsp;&nbsp;  <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/amdgputargetmachine-cpp/#a785883ec0154b6773dd0c47b13588a1a">ADD_CLASS_PASS_TO_PASS_NAME</a>(NAME, CREATE_PASS)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 45 of file TargetPassRegistry.inc.</p>

</div>
</div>

### FUNCTION\_PASS {#a2fe799143be34291491c183ed9c0eea7}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">#define FUNCTION_PASS(NAME, CREATE_PASS)&nbsp;&nbsp;&nbsp;<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/amdgputargetmachine-cpp/#a7e81816a66f7a306d304777ce3b1d3dc">ADD_PASS</a>(NAME, CREATE_PASS)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 114 of file TargetPassRegistry.inc.</p>

</div>
</div>

### FUNCTION\_PASS\_WITH\_PARAMS {#a39f2a031848ee3c43432d32ba6d42300}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">#define FUNCTION_PASS_WITH_PARAMS(NAME, CLASS, CREATE_PASS, PARSER, PARAMS)&nbsp;&nbsp;&nbsp;  <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/amdgputargetmachine-cpp/#a30af641d5b42457b0cb49ad7eeeba6d3">ADD_CLASS_PASS_TO_PASS_NAME_WITH_PARAMS</a>(NAME, CLASS)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 47 of file TargetPassRegistry.inc.</p>

</div>
</div>

### FUNCTION\_PASS\_WITH\_PARAMS {#a311ebbf608e96c2cf18b6720168da442}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">#define FUNCTION_PASS_WITH_PARAMS(NAME, CLASS, CREATE_PASS, PARSER, PARAMS)&nbsp;&nbsp;&nbsp;  <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/amdgputargetmachine-cpp/#a60cfccc5fc706d773a18ba77db9c807f">ADD_PASS_WITH_PARAMS</a>(NAME, CREATE_PASS, PARSER)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 122 of file TargetPassRegistry.inc.</p>

</div>
</div>

### GET\_PASS\_REGISTRY {#aba71ac83fc0882e97760c16e84ed9599}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">#define GET_PASS_REGISTRY&nbsp;&nbsp;&nbsp;"SPIRVPassRegistry.def"</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 100 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/spirv/spirvtargetmachine-cpp">SPIRVTargetMachine.cpp</a>.</p>

</div>
</div>

### LOOP\_ANALYSIS {#a153ed55c08dcea6b7bee890741e2465f}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">#define LOOP_ANALYSIS(NAME, CREATE_PASS)&nbsp;&nbsp;&nbsp;  <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/amdgputargetmachine-cpp/#a785883ec0154b6773dd0c47b13588a1a">ADD_CLASS_PASS_TO_PASS_NAME</a>(NAME, CREATE_PASS)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 49 of file TargetPassRegistry.inc.</p>

</div>
</div>

### LOOP\_ANALYSIS {#a4c6fd949900e2be4f909ae96a018bef9}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">#define LOOP_ANALYSIS(NAME, CREATE_PASS)&nbsp;&nbsp;&nbsp;  AM.registerPass([&amp;] { return CREATE_PASS; });</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 184 of file TargetPassRegistry.inc.</p>

</div>
</div>

### LOOP\_PASS {#a54aaec23a0af37818d0b521b9c7cd10d}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">#define LOOP_PASS(NAME, CREATE_PASS)&nbsp;&nbsp;&nbsp;  <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/amdgputargetmachine-cpp/#a785883ec0154b6773dd0c47b13588a1a">ADD_CLASS_PASS_TO_PASS_NAME</a>(NAME, CREATE_PASS)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 51 of file TargetPassRegistry.inc.</p>

</div>
</div>

### LOOP\_PASS {#a23c129b1a117c00315516028a20df042}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">#define LOOP_PASS(NAME, CREATE_PASS)&nbsp;&nbsp;&nbsp;<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/amdgputargetmachine-cpp/#a7e81816a66f7a306d304777ce3b1d3dc">ADD_PASS</a>(NAME, CREATE_PASS)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 131 of file TargetPassRegistry.inc.</p>

</div>
</div>

### MACHINE\_FUNCTION\_ANALYSIS {#ae8bee684ed42fc73cd9184c6c924b57c}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">#define MACHINE_FUNCTION_ANALYSIS(NAME, CREATE_PASS)&nbsp;&nbsp;&nbsp;  <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/amdgputargetmachine-cpp/#a785883ec0154b6773dd0c47b13588a1a">ADD_CLASS_PASS_TO_PASS_NAME</a>(NAME, CREATE_PASS)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 53 of file TargetPassRegistry.inc.</p>

</div>
</div>

### MACHINE\_FUNCTION\_ANALYSIS {#a304fa0b7b45d6b32d5742c05f852b1f2}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">#define MACHINE_FUNCTION_ANALYSIS(NAME, CREATE_PASS)&nbsp;&nbsp;&nbsp;  AM.registerPass([&amp;] { return CREATE_PASS; });</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 191 of file TargetPassRegistry.inc.</p>

</div>
</div>

### MACHINE\_FUNCTION\_PASS {#a70051016d8672632182efe9799c4c083}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">#define MACHINE_FUNCTION_PASS(NAME, CREATE_PASS)&nbsp;&nbsp;&nbsp;  <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/amdgputargetmachine-cpp/#a785883ec0154b6773dd0c47b13588a1a">ADD_CLASS_PASS_TO_PASS_NAME</a>(NAME, CREATE_PASS)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 55 of file TargetPassRegistry.inc.</p>

</div>
</div>

### MACHINE\_FUNCTION\_PASS {#ac6116ae7b86d8db66ba2cf3f1f061ce1}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">#define MACHINE_FUNCTION_PASS(NAME, CREATE_PASS)&nbsp;&nbsp;&nbsp;<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/amdgputargetmachine-cpp/#a7e81816a66f7a306d304777ce3b1d3dc">ADD_PASS</a>(NAME, CREATE_PASS)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 139 of file TargetPassRegistry.inc.</p>

</div>
</div>

### MACHINE\_FUNCTION\_PASS\_WITH\_PARAMS {#a41d7c2793b719b960a6cf9b5fe2aa4e8}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">#define MACHINE_FUNCTION_PASS_WITH_PARAMS(NAME, CLASS, CREATE_PASS, PARSER, PARAMS)&nbsp;&nbsp;&nbsp;  <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/amdgputargetmachine-cpp/#a30af641d5b42457b0cb49ad7eeeba6d3">ADD_CLASS_PASS_TO_PASS_NAME_WITH_PARAMS</a>(NAME, CLASS)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 58 of file TargetPassRegistry.inc.</p>

</div>
</div>

### MACHINE\_FUNCTION\_PASS\_WITH\_PARAMS {#a0e7b7a2c70f63ae1138cb04e1479bf2e}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">#define MACHINE_FUNCTION_PASS_WITH_PARAMS(NAME, CLASS, CREATE_PASS, PARSER, PARAMS)&nbsp;&nbsp;&nbsp;  <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/amdgputargetmachine-cpp/#a60cfccc5fc706d773a18ba77db9c807f">ADD_PASS_WITH_PARAMS</a>(NAME, CREATE_PASS, PARSER)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 147 of file TargetPassRegistry.inc.</p>

</div>
</div>

### MODULE\_ANALYSIS {#ae630e66bd51cb0c84874bd406b12f4a3}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">#define MODULE_ANALYSIS(NAME, CREATE_PASS)&nbsp;&nbsp;&nbsp;  <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/amdgputargetmachine-cpp/#a785883ec0154b6773dd0c47b13588a1a">ADD_CLASS_PASS_TO_PASS_NAME</a>(NAME, CREATE_PASS)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 35 of file TargetPassRegistry.inc.</p>

</div>
</div>

### MODULE\_ANALYSIS {#a0dec599234592c714174fee76a88c710}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">#define MODULE_ANALYSIS(NAME, CREATE_PASS)&nbsp;&nbsp;&nbsp;  AM.registerPass([&amp;] { return CREATE_PASS; });</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 158 of file TargetPassRegistry.inc.</p>

</div>
</div>

### MODULE\_PASS {#a582c86fdb6a64efb8ec4a59327aa6793}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">#define MODULE_PASS(NAME, CREATE_PASS)&nbsp;&nbsp;&nbsp;  <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/amdgputargetmachine-cpp/#a785883ec0154b6773dd0c47b13588a1a">ADD_CLASS_PASS_TO_PASS_NAME</a>(NAME, CREATE_PASS)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 37 of file TargetPassRegistry.inc.</p>

</div>
</div>

### MODULE\_PASS {#a0b0ff03a6bb4a70e73fd5083c3679e52}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">#define MODULE_PASS(NAME, CREATE_PASS)&nbsp;&nbsp;&nbsp;<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/amdgputargetmachine-cpp/#a7e81816a66f7a306d304777ce3b1d3dc">ADD_PASS</a>(NAME, CREATE_PASS)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 97 of file TargetPassRegistry.inc.</p>

</div>
</div>

### MODULE\_PASS\_WITH\_PARAMS {#a97a1c5adfbad7cfb551750d9dec6b013}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">#define MODULE_PASS_WITH_PARAMS(NAME, CLASS, CREATE_PASS, PARSER, PARAMS)&nbsp;&nbsp;&nbsp;  <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/amdgputargetmachine-cpp/#a30af641d5b42457b0cb49ad7eeeba6d3">ADD_CLASS_PASS_TO_PASS_NAME_WITH_PARAMS</a>(NAME, CLASS)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 39 of file TargetPassRegistry.inc.</p>

</div>
</div>

### MODULE\_PASS\_WITH\_PARAMS {#a7500ad7948c3ddde5d682816f775f4e1}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">#define MODULE_PASS_WITH_PARAMS(NAME, CLASS, CREATE_PASS, PARSER, PARAMS)&nbsp;&nbsp;&nbsp;  <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/amdgputargetmachine-cpp/#a60cfccc5fc706d773a18ba77db9c807f">ADD_PASS_WITH_PARAMS</a>(NAME, CREATE_PASS, PARSER)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 105 of file TargetPassRegistry.inc.</p>

</div>
</div>

</div>

<hr/>

<p class="doxyGeneratedBy">Generated via <a href="https://github.com/xpack/doxygen2docusaurus">doxygen2docusaurus</a> by <a href="https://www.doxygen.nl">Doxygen</a> 1.15.0.</p>

</div>
