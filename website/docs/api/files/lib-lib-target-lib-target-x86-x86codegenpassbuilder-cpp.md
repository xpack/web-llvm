---

# DO NOT EDIT!
# Automatically generated via doxygen2docusaurus by Doxygen.

slug: /api/files/lib/lib/target/lib/target/x86/x86codegenpassbuilder-cpp
custom_edit_url: null
toc_max_heading_level: 4
keywords:
  - doxygen
  - reference
  - file

---

<div class="doxyPage">

# The `X86CodeGenPassBuilder.cpp` File Reference

<p>This file contains <a href="/web-llvm/docs/api/namespaces/llvm/x86">X86</a> CodeGen pipeline builder. <a href="#details">More...</a></p>

## Included Headers

<div class="doxyIncludesList">#include "<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/x86/x86iseldagtodag-h">X86ISelDAGToDAG.h</a>"
#include "<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/x86/x86targetmachine-h">X86TargetMachine.h</a>"
#include "<a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/mc/mcstreamer-h">llvm/MC/MCStreamer.h</a>"
#include "<a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/passes/codegenpassbuilder-h">llvm/Passes/CodeGenPassBuilder.h</a>"
#include "<a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/passes/passbuilder-h">llvm/Passes/PassBuilder.h</a>"
#include "llvm/Passes/TargetPassRegistry.inc"
</div>

## Namespaces Index

<table class="doxyMembersIndex">

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">namespace</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="/web-llvm/docs/api/namespaces/anonymous-x86codegenpassbuilder-cpp-">anonymous{X86CodeGenPassBuilder.cpp}</a></td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="/web-llvm/docs/api/classes/anonymous-x86codegenpassbuilder-cpp-/x86codegenpassbuilder">X86CodeGenPassBuilder</a></td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#aba71ac83fc0882e97760c16e84ed9599">GET_PASS_REGISTRY</a>&nbsp;&nbsp;&nbsp;"X86PassRegistry.def"</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a582c86fdb6a64efb8ec4a59327aa6793">MODULE_PASS</a>(NAME, CREATE_PASS)&nbsp;&nbsp;&nbsp;<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/amdgputargetmachine-cpp/#a7e81816a66f7a306d304777ce3b1d3dc">ADD_PASS</a>(NAME, CREATE_PASS)</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a97a1c5adfbad7cfb551750d9dec6b013">MODULE_PASS_WITH_PARAMS</a>(NAME, CLASS, CREATE_PASS, PARSER, PARAMS)&nbsp;&nbsp;&nbsp;  <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/amdgputargetmachine-cpp/#a60cfccc5fc706d773a18ba77db9c807f">ADD_PASS_WITH_PARAMS</a>(NAME, CREATE_PASS, PARSER)</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a6263fb21d44822c311d528df14c7d1d3">FUNCTION_PASS</a>(NAME, CREATE_PASS)&nbsp;&nbsp;&nbsp;<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/amdgputargetmachine-cpp/#a7e81816a66f7a306d304777ce3b1d3dc">ADD_PASS</a>(NAME, CREATE_PASS)</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a39f2a031848ee3c43432d32ba6d42300">FUNCTION_PASS_WITH_PARAMS</a>(NAME, CLASS, CREATE_PASS, PARSER, PARAMS)&nbsp;&nbsp;&nbsp;  <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/amdgputargetmachine-cpp/#a60cfccc5fc706d773a18ba77db9c807f">ADD_PASS_WITH_PARAMS</a>(NAME, CREATE_PASS, PARSER)</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a54aaec23a0af37818d0b521b9c7cd10d">LOOP_PASS</a>(NAME, CREATE_PASS)&nbsp;&nbsp;&nbsp;<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/amdgputargetmachine-cpp/#a7e81816a66f7a306d304777ce3b1d3dc">ADD_PASS</a>(NAME, CREATE_PASS)</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a70051016d8672632182efe9799c4c083">MACHINE_FUNCTION_PASS</a>(NAME, CREATE_PASS)&nbsp;&nbsp;&nbsp;<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/amdgputargetmachine-cpp/#a7e81816a66f7a306d304777ce3b1d3dc">ADD_PASS</a>(NAME, CREATE_PASS)</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a41d7c2793b719b960a6cf9b5fe2aa4e8">MACHINE_FUNCTION_PASS_WITH_PARAMS</a>(NAME, CLASS, CREATE_PASS, PARSER, PARAMS)&nbsp;&nbsp;&nbsp;  <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/amdgputargetmachine-cpp/#a60cfccc5fc706d773a18ba77db9c807f">ADD_PASS_WITH_PARAMS</a>(NAME, CREATE_PASS, PARSER)</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ae630e66bd51cb0c84874bd406b12f4a3">MODULE_ANALYSIS</a>(NAME, CREATE_PASS)&nbsp;&nbsp;&nbsp;  AM.registerPass([&amp;] { return CREATE_PASS; });</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a67c895b5207a31e73cf972bb58ab5aa9">FUNCTION_ANALYSIS</a>(NAME, CREATE_PASS)&nbsp;&nbsp;&nbsp;  AM.registerPass([&amp;] { return CREATE_PASS; });</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a613be0a47ad4283b033171c7d91ebce9">FUNCTION_ALIAS_ANALYSIS</a>(NAME, CREATE_PASS)&nbsp;&nbsp;&nbsp;...</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a153ed55c08dcea6b7bee890741e2465f">LOOP_ANALYSIS</a>(NAME, CREATE_PASS)&nbsp;&nbsp;&nbsp;  AM.registerPass([&amp;] { return CREATE_PASS; });</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ae8bee684ed42fc73cd9184c6c924b57c">MACHINE_FUNCTION_ANALYSIS</a>(NAME, CREATE_PASS)&nbsp;&nbsp;&nbsp;  AM.registerPass([&amp;] { return CREATE_PASS; });</td>
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

## Description {#details}

<p>This file contains <a href="/web-llvm/docs/api/namespaces/llvm/x86">X86</a> CodeGen pipeline builder.</p>


<p>TODO: Port CodeGen passes to new pass manager.</p>


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

### FUNCTION\_ALIAS\_ANALYSIS {#a613be0a47ad4283b033171c7d91ebce9}

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

### FUNCTION\_ANALYSIS {#a67c895b5207a31e73cf972bb58ab5aa9}

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

### FUNCTION\_PASS {#a6263fb21d44822c311d528df14c7d1d3}

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

### FUNCTION\_PASS\_WITH\_PARAMS {#a39f2a031848ee3c43432d32ba6d42300}

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
<td class="doxyMemberName">#define GET_PASS_REGISTRY&nbsp;&nbsp;&nbsp;"X86PassRegistry.def"</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 54 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/x86/x86codegenpassbuilder-cpp">X86CodeGenPassBuilder.cpp</a>.</p>

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

### LOOP\_ANALYSIS {#a153ed55c08dcea6b7bee890741e2465f}

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

### LOOP\_PASS {#a54aaec23a0af37818d0b521b9c7cd10d}

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

### MACHINE\_FUNCTION\_ANALYSIS {#ae8bee684ed42fc73cd9184c6c924b57c}

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

### MACHINE\_FUNCTION\_PASS {#a70051016d8672632182efe9799c4c083}

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

### MACHINE\_FUNCTION\_PASS\_WITH\_PARAMS {#a41d7c2793b719b960a6cf9b5fe2aa4e8}

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

### MODULE\_ANALYSIS {#ae630e66bd51cb0c84874bd406b12f4a3}

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

### MODULE\_PASS {#a582c86fdb6a64efb8ec4a59327aa6793}

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

### MODULE\_PASS\_WITH\_PARAMS {#a97a1c5adfbad7cfb551750d9dec6b013}

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

<p class="doxyGeneratedBy">Generated via <a href="https://github.com/xpack/doxygen2docusaurus">doxygen2docusaurus</a> by <a href="https://www.doxygen.nl">Doxygen</a> 1.14.0.</p>

</div>
