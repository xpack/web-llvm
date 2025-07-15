---

# DO NOT EDIT!
# Automatically generated via doxygen2docusaurus by Doxygen.

slug: /api/files/lib/lib/target/lib/target/amdgpu/amdgpulegalizerinfo-cpp
custom_edit_url: null
toc_max_heading_level: 4
keywords:
  - doxygen
  - reference
  - file

---

<div class="doxyPage">

# The `AMDGPULegalizerInfo.cpp` File Reference

<p>This file implements the targeting of the Machinelegalizer class for <a href="/web-llvm/docs/api/namespaces/llvm/amdgpu">AMDGPU</a>. <a href="#details">More...</a></p>

## Included Headers

<div class="doxyIncludesList">#include "<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/amdgpulegalizerinfo-h">AMDGPULegalizerInfo.h</a>"
#include "<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/amdgpu-h">AMDGPU.h</a>"
#include "<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/amdgpuglobaliselutils-h">AMDGPUGlobalISelUtils.h</a>"
#include "<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/amdgpuinstrinfo-h">AMDGPUInstrInfo.h</a>"
#include "<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/amdgpumemoryutils-h">AMDGPUMemoryUtils.h</a>"
#include "<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/amdgputargetmachine-h">AMDGPUTargetMachine.h</a>"
#include "<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/lib/target/amdgpu/mctargetdesc/amdgpumctargetdesc-h">MCTargetDesc/AMDGPUMCTargetDesc.h</a>"
#include "<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/siinstrinfo-h">SIInstrInfo.h</a>"
#include "<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/simachinefunctioninfo-h">SIMachineFunctionInfo.h</a>"
#include "<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/siregisterinfo-h">SIRegisterInfo.h</a>"
#include "<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/lib/target/amdgpu/utils/amdgpubaseinfo-h">Utils/AMDGPUBaseInfo.h</a>"
#include "<a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/adt/scopeexit-h">llvm/ADT/ScopeExit.h</a>"
#include "<a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/codegen/include/llvm/codegen/globalisel/genericmachineinstrs-h">llvm/CodeGen/GlobalISel/GenericMachineInstrs.h</a>"
#include "<a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/codegen/include/llvm/codegen/globalisel/legalizerhelper-h">llvm/CodeGen/GlobalISel/LegalizerHelper.h</a>"
#include "<a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/codegen/include/llvm/codegen/globalisel/mipatternmatch-h">llvm/CodeGen/GlobalISel/MIPatternMatch.h</a>"
#include "<a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/codegen/include/llvm/codegen/globalisel/machineirbuilder-h">llvm/CodeGen/GlobalISel/MachineIRBuilder.h</a>"
#include "<a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/codegen/include/llvm/codegen/globalisel/utils-h">llvm/CodeGen/GlobalISel/Utils.h</a>"
#include "<a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/codegen/targetopcodes-h">llvm/CodeGen/TargetOpcodes.h</a>"
#include "<a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/ir/diagnosticinfo-h">llvm/IR/DiagnosticInfo.h</a>"
#include "llvm/IR/IntrinsicsAMDGPU.h"
#include "llvm/IR/IntrinsicsR600.h"
</div>

## Functions Index

<table class="doxyMembersIndex">

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">static <a href="/web-llvm/docs/api/classes/llvm/llt">LLT</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ae6dc00935578ac3d7b43326b5f02b2bc">getPow2VectorType</a> (LLT Ty)</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">static <a href="/web-llvm/docs/api/classes/llvm/llt">LLT</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ae9bc1717e31ed947b2eae89a230c744b">getPow2ScalarType</a> (LLT Ty)</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">static <a href="/web-llvm/docs/api/namespaces/llvm/#a652895328c6f5785e94ac8b51b37d63c">LegalityPredicate</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a0dbe048033c8b5adaf283b8fe7de3ba1">isSmallOddVector</a> (unsigned TypeIdx)</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">static <a href="/web-llvm/docs/api/namespaces/llvm/#a652895328c6f5785e94ac8b51b37d63c">LegalityPredicate</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#afa3cedfbe23049312e516145f0e46cbb">sizeIsMultipleOf32</a> (unsigned TypeIdx)</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">static <a href="/web-llvm/docs/api/namespaces/llvm/#a652895328c6f5785e94ac8b51b37d63c">LegalityPredicate</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a3d552c29a563f3462800870d14e72b0f">isWideVec16</a> (unsigned TypeIdx)</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">static <a href="/web-llvm/docs/api/namespaces/llvm/#a31da885e5f80ee375b306057d2a852ab">LegalizeMutation</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a0e3fd79bb281f248eefd08814023d8c8">oneMoreElement</a> (unsigned TypeIdx)</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">static <a href="/web-llvm/docs/api/namespaces/llvm/#a31da885e5f80ee375b306057d2a852ab">LegalizeMutation</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a3b5805e73f162bbb84584fbc2091806e">fewerEltsToSize64Vector</a> (unsigned TypeIdx)</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">static <a href="/web-llvm/docs/api/namespaces/llvm/#a31da885e5f80ee375b306057d2a852ab">LegalizeMutation</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ad64f039266036a2ac4d704000928d65b">moreEltsToNext32Bit</a> (unsigned TypeIdx)</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">static <a href="/web-llvm/docs/api/namespaces/llvm/#a31da885e5f80ee375b306057d2a852ab">LegalizeMutation</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a4b2db808be70ea68e0f121c1942982a9">moreElementsToNextExistingRegClass</a> (unsigned TypeIdx)</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">static <a href="/web-llvm/docs/api/classes/llvm/llt">LLT</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a0440dee786271aa77b3f640b1c63363c">getBufferRsrcScalarType</a> (const LLT Ty)</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">static <a href="/web-llvm/docs/api/classes/llvm/llt">LLT</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a64443e60c47deb77ad3bb491d2da3c5f">getBufferRsrcRegisterType</a> (const LLT Ty)</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">static <a href="/web-llvm/docs/api/classes/llvm/llt">LLT</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a639711ef50cb300db9e9ade1445ccf07">getBitcastRegisterType</a> (const LLT Ty)</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">static <a href="/web-llvm/docs/api/namespaces/llvm/#a31da885e5f80ee375b306057d2a852ab">LegalizeMutation</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a6eb46b558dd23ba908853adcc6ba76b7">bitcastToRegisterType</a> (unsigned TypeIdx)</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">static <a href="/web-llvm/docs/api/namespaces/llvm/#a31da885e5f80ee375b306057d2a852ab">LegalizeMutation</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a0aab1c76215e1773caa058744d6ae6af">bitcastToVectorElement32</a> (unsigned TypeIdx)</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">static <a href="/web-llvm/docs/api/namespaces/llvm/#a652895328c6f5785e94ac8b51b37d63c">LegalityPredicate</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a144b2ed41ce4f22842225b0b1b117a58">vectorSmallerThan</a> (unsigned TypeIdx, unsigned Size)</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">static <a href="/web-llvm/docs/api/namespaces/llvm/#a652895328c6f5785e94ac8b51b37d63c">LegalityPredicate</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a2d0beabfcf00e6fd23c97eff8ee516a6">vectorWiderThan</a> (unsigned TypeIdx, unsigned Size)</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">static <a href="/web-llvm/docs/api/namespaces/llvm/#a652895328c6f5785e94ac8b51b37d63c">LegalityPredicate</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a8e4a67e6620c2b437e4b7a7707ac0914">numElementsNotEven</a> (unsigned TypeIdx)</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">static bool</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a3986167503ccf79606f2249e660c9961">isRegisterSize</a> (unsigned Size)</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">static bool</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a31648fb7411d04ec274b46d8dd635564">isRegisterVectorElementType</a> (LLT EltTy)</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">static bool</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#af6ee8616537a0f758b8962b4e5076b35">isRegisterVectorType</a> (LLT Ty)</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">static bool</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a2ea867ab6af309ac37d89c0ac9242600">isRegisterType</a> (LLT Ty)</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">static <a href="/web-llvm/docs/api/namespaces/llvm/#a652895328c6f5785e94ac8b51b37d63c">LegalityPredicate</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a6828238e57f3a265b56fb009a227af4e">isRegisterType</a> (unsigned TypeIdx)</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">static <a href="/web-llvm/docs/api/namespaces/llvm/#a652895328c6f5785e94ac8b51b37d63c">LegalityPredicate</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#aa5fe965eac66ae9ebc69835fe44c679d">isIllegalRegisterType</a> (unsigned TypeIdx)</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">static <a href="/web-llvm/docs/api/namespaces/llvm/#a652895328c6f5785e94ac8b51b37d63c">LegalityPredicate</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#aed4feaa9baf8df7fe949b9a5ce246646">elementTypeIsLegal</a> (unsigned TypeIdx)</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">static bool</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a8ac13bffc4ec5811abc67aaa4166e9a8">isRegisterClassType</a> (LLT Ty)</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">static <a href="/web-llvm/docs/api/namespaces/llvm/#a652895328c6f5785e94ac8b51b37d63c">LegalityPredicate</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a6f96e69af9b47cc95fd19cc091b0aea1">isRegisterClassType</a> (unsigned TypeIdx)</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">static <a href="/web-llvm/docs/api/namespaces/llvm/#a652895328c6f5785e94ac8b51b37d63c">LegalityPredicate</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ab92c68720091c48aa146f82db0f9ce88">isWideScalarExtLoadTruncStore</a> (unsigned TypeIdx)</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">static unsigned</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a807f9ab682878abe0a704736d1f9f298">maxSizeForAddrSpace</a> (const GCNSubtarget &amp;ST, unsigned AS, bool IsLoad, bool IsAtomic)</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">static bool</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a812ebabddd1ad2d8f8bbc6194346e2ed">isLoadStoreSizeLegal</a> (const GCNSubtarget &amp;ST, const LegalityQuery &amp;Query)</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">static bool</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#abb71b9eb64250d4491336cf106be74eb">hasBufferRsrcWorkaround</a> (const LLT Ty)</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">static bool</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ac6f0c363a0260f50a2e3dae5b8c00d21">loadStoreBitcastWorkaround</a> (const LLT Ty)</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">static bool</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ad2c8a875d4d2a4e73f7a48e64226b265">isLoadStoreLegal</a> (const GCNSubtarget &amp;ST, const LegalityQuery &amp;Query)</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">static bool</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a1c42298ffb49a95c87577d3e5de46aea">shouldBitcastLoadStoreType</a> (const GCNSubtarget &amp;ST, const LLT Ty, const LLT MemTy)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Return true if a load or store of the type should be lowered with a bitcast to a different type. <a href="#a1c42298ffb49a95c87577d3e5de46aea">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">static bool</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a2d595a51e66614b8adb83efbc8114401">shouldWidenLoad</a> (const GCNSubtarget &amp;ST, LLT MemoryTy, uint64_t AlignInBits, unsigned AddrSpace, unsigned Opcode)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Return true if we should legalize a load by widening an odd sized memory access up to the alignment. <a href="#a2d595a51e66614b8adb83efbc8114401">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">static bool</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a9ae9993cc0e622c6d10e6e9a2aad0a05">shouldWidenLoad</a> (const GCNSubtarget &amp;ST, const LegalityQuery &amp;Query, unsigned Opcode)</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">static <a href="/web-llvm/docs/api/classes/llvm/llt">LLT</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a78249707a06ea5161d8c6bbb442ea46c">castBufferRsrcFromV4I32</a> (MachineInstr &amp;MI, MachineIRBuilder &amp;B, MachineRegisterInfo &amp;MRI, unsigned Idx)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Mutates IR (typicaly a load instruction) to use a &lt;4 x s32&gt; as the initial type of the operand <span class="doxyComputerOutput">idx</span> and then to transform it to a <span class="doxyComputerOutput">p8</span> via bitcasts and inttoptr. <a href="#a78249707a06ea5161d8c6bbb442ea46c">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">static <a href="/web-llvm/docs/api/classes/llvm/register">Register</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a5a32fa3ab512ce8c3afa4e68c2b56765">castBufferRsrcToV4I32</a> (Register Pointer, MachineIRBuilder &amp;B)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Cast a buffer resource (an address space 8 pointer) into a 4xi32, which is the form in which the value must be in order to be passed to the low-level representations used for MUBUF/MTBUF intrinsics. <a href="#a5a32fa3ab512ce8c3afa4e68c2b56765">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">static void</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a9d84441ae7638d9c27873f5a3810cb88">castBufferRsrcArgToV4I32</a> (MachineInstr &amp;MI, MachineIRBuilder &amp;B, unsigned Idx)</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">static bool</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#aff707b57a26889c4290a79001f12fd20">isKnownNonNull</a> (Register Val, MachineRegisterInfo &amp;MRI, const AMDGPUTargetMachine &amp;TM, unsigned AddrSpace)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Return true if the value is a known valid address, such that a null check is not necessary. <a href="#aff707b57a26889c4290a79001f12fd20">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">static <a href="/web-llvm/docs/api/classes/llvm/machineinstrbuilder">MachineInstrBuilder</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a47ea7f32b98178dbcb9bf3d1ff00daa1">extractF64Exponent</a> (Register Hi, MachineIRBuilder &amp;B)</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">static <a href="/web-llvm/docs/api/classes/llvm/llt">LLT</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#acbd3ab3957032feb181df036bb6a8d27">widenToNextPowerOf2</a> (LLT Ty)</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">static bool</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a344a4fa1e7c1a3a6f6ede4213058ad12">valueIsKnownNeverF32Denorm</a> (const MachineRegisterInfo &amp;MRI, Register Src)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Return true if it's known that <span class="doxyComputerOutput">Src</span> can never be an f32 denormal value. <a href="#a344a4fa1e7c1a3a6f6ede4213058ad12">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">static bool</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a16c22435b21cfe335c972d971e29b0d7">allowApproxFunc</a> (const MachineFunction &amp;MF, unsigned Flags)</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">static bool</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a092571cd6865fc5f86e2a594265ff717">needsDenormHandlingF32</a> (const MachineFunction &amp;MF, Register Src, unsigned Flags)</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a879e21eca00dd442c2623c505ca81b6e">getMad</a> (MachineIRBuilder &amp;B, LLT Ty, Register X, Register Y, Register Z, unsigned Flags)</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a716801caf6a489a6af735be940932003">stripAnySourceMods</a> (Register OrigSrc, MachineRegisterInfo &amp;MRI)</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">static bool</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#accff22ec9fbd872b5976a4a2dc20ef56">isNot</a> (const MachineRegisterInfo &amp;MRI, const MachineInstr &amp;MI)</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">static <a href="/web-llvm/docs/api/classes/llvm/machineinstr">MachineInstr</a> *</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a87e58e9d24983c7890c502fbe731f950">verifyCFIntrinsic</a> (MachineInstr &amp;MI, MachineRegisterInfo &amp;MRI, MachineInstr *&amp;Br, MachineBasicBlock *&amp;UncondBrTarget, bool &amp;Negated)</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">static bool</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a79158bc80349e2c5ecd857cb098db65e">replaceWithConstant</a> (MachineIRBuilder &amp;B, MachineInstr &amp;MI, int64_t C)</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">static std::pair&lt; <a href="/web-llvm/docs/api/classes/llvm/register">Register</a>, <a href="/web-llvm/docs/api/classes/llvm/register">Register</a> &gt;</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a62e3406e85438cd0a8d5e3de179ef6eb">emitReciprocalU64</a> (MachineIRBuilder &amp;B, Register Val)</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#abceca15aff80aa1ea3b5e7603981f878">toggleSPDenormMode</a> (bool Enable, MachineIRBuilder &amp;B, const GCNSubtarget &amp;ST, SIModeRegisterDefaults Mode)</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ae6e9dca782411211a3526572f6ebeb33">buildBufferLoad</a> (unsigned Opc, Register LoadDstReg, Register RSrc, Register VIndex, Register VOffset, Register SOffset, unsigned ImmOffset, unsigned Format, unsigned AuxiliaryData, MachineMemOperand *MMO, bool IsTyped, bool HasVIndex, MachineIRBuilder &amp;B)</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">static unsigned</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a0356a7c051be3c82d2c7da7e0bdb229c">getBufferAtomicPseudo</a> (Intrinsic::ID IntrID)</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a0022aa73e6337684561159d1f7929966">packImage16bitOpsToDwords</a> (MachineIRBuilder &amp;B, MachineInstr &amp;MI, SmallVectorImpl&lt; Register &gt; &amp;PackedAddrs, unsigned ArgOffset, const AMDGPU::ImageDimIntrinsicInfo *Intr, bool IsA16, bool IsG16)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Turn a set of s16 typed registers in <span class="doxyComputerOutput">AddrRegs</span> into a dword sized vector with s16 typed elements. <a href="#a0022aa73e6337684561159d1f7929966">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">static void</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ad049a79d46df2c25561d90e9d80fb5e3">convertImageAddrToPacked</a> (MachineIRBuilder &amp;B, MachineInstr &amp;MI, int DimIdx, int NumVAddrs)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Convert from separate vaddr components to a single vector address register, and replace the remaining operands with $noreg. <a href="#ad049a79d46df2c25561d90e9d80fb5e3">More...</a></p>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a051bcca9a10dfdb5c382173aa0d5a860">EnableNewLegality</a>("amdgpu-global-isel-new-legality", cl::desc("Use GlobalISel desired legality, rather than try to use" "rules compatible with selection patterns"), cl::init(false), cl::ReallyHidden)</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">static constexpr unsigned</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#aabec8e9bc89e3e905a71769f8be922c1">MaxRegisterSize</a> = 1024</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">static <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/llt">LLT</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a22eabd3566ae5f32cb6f594f4f343399">S1</a> = LLT::scalar(1)</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">static <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/llt">LLT</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#af00ba7c018760702ba16a5009cec810c">S8</a> = LLT::scalar(8)</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">static <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/llt">LLT</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#acd57bd926bf1c8815e21e1291a54d151">S16</a> = LLT::scalar(16)</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">static <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/llt">LLT</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a33c95d7d51d4b0b421aaf3d40796b859">S32</a> = LLT::scalar(32)</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">static <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/llt">LLT</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#affe0a8af32c1d4e53b07959b240641b4">F32</a> = LLT::float32()</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">static <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/llt">LLT</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a2b96ee4926f7c19420d19ecaf7adc1a8">S64</a> = LLT::scalar(64)</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">static <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/llt">LLT</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a563bbae35885ba289017e47ec57235fa">F64</a> = LLT::float64()</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">static <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/llt">LLT</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ac721ed1f1b2048a37c89fa31e662cd3a">S96</a> = LLT::scalar(96)</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">static <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/llt">LLT</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a0a82f21bb2863eb65c5f28fb9d34a954">S128</a> = LLT::scalar(128)</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">static <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/llt">LLT</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a8d3731c41acd28da69f691b8ce22edd4">S160</a> = LLT::scalar(160)</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">static <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/llt">LLT</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a7654aba611cb44b8c9d4a43398099bf6">S192</a> = LLT::scalar(192)</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">static <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/llt">LLT</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#af775f87ae257bdc6f0b5e5eac41ad51a">S224</a> = LLT::scalar(224)</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">static <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/llt">LLT</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ae61a7658a9585eba0ff27a47e0c8aea1">S256</a> = LLT::scalar(256)</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">static <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/llt">LLT</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a7fcbdd8fbd887c5c2c68588ab6179c64">S512</a> = LLT::scalar(512)</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">static <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/llt">LLT</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a482bcb2c405924538af22abc4c9e85fc">S1024</a> = LLT::scalar(1024)</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">static <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/llt">LLT</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#abb0782aaccc0907cc36fe566a642c71b">MaxScalar</a> = LLT::scalar(<a href="#aabec8e9bc89e3e905a71769f8be922c1">MaxRegisterSize</a>)</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">static <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/llt">LLT</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ab8e5c09740bb85eb6c2d25b534f91570">V2S8</a> = LLT::fixed_vector(2, 8)</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">static <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/llt">LLT</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a1a23ce3b10dc058d258a405a87e06a1a">V2S16</a> = LLT::fixed_vector(2, 16)</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">static <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/llt">LLT</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a52e4f67b333637f707e6fe59057c7348">V4S16</a> = LLT::fixed_vector(4, 16)</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">static <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/llt">LLT</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#af54c894f1513d925a199547dec0ef2b2">V6S16</a> = LLT::fixed_vector(6, 16)</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">static <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/llt">LLT</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#af904a5a62bedccf8107722036a8df0ce">V8S16</a> = LLT::fixed_vector(8, 16)</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">static <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/llt">LLT</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ace4e8d195c9498b419467f234000a72e">V10S16</a> = LLT::fixed_vector(10, 16)</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">static <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/llt">LLT</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a7a3fa97d0457d84638593bf3da5e21f6">V12S16</a> = LLT::fixed_vector(12, 16)</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">static <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/llt">LLT</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a09d7d8b975bcef9c12bd114d3b593b00">V16S16</a> = LLT::fixed_vector(16, 16)</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">static <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/llt">LLT</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ade55769087ba2b628fd60dc76161764f">V2F16</a> = LLT::fixed_vector(2, LLT::float16())</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">static <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/llt">LLT</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#aa6c31d3f7f1803b32735d9b3568e7f12">V2BF16</a> = <a href="#ade55769087ba2b628fd60dc76161764f">V2F16</a></td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">static <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/llt">LLT</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a0b000f228cb40bf4aee0a19815ce4d99">V2S32</a> = LLT::fixed_vector(2, 32)</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">static <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/llt">LLT</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a257279ea49c58180217364b89917c6c3">V3S32</a> = LLT::fixed_vector(3, 32)</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">static <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/llt">LLT</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a0af4f63c268470ef2eac6477d33fdce4">V4S32</a> = LLT::fixed_vector(4, 32)</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">static <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/llt">LLT</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a4d742b8db1d6a22581da42b9b758e2be">V5S32</a> = LLT::fixed_vector(5, 32)</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">static <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/llt">LLT</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a495ae51584ec946579f24bda39b4fa84">V6S32</a> = LLT::fixed_vector(6, 32)</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">static <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/llt">LLT</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a4c29a6c597e1cb2db05e41d65f76d338">V7S32</a> = LLT::fixed_vector(7, 32)</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">static <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/llt">LLT</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a1348f6cfe026c7a1dca9a61c8713ab07">V8S32</a> = LLT::fixed_vector(8, 32)</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">static <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/llt">LLT</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a7261ab9abe3b6583e7e094677e84b50d">V9S32</a> = LLT::fixed_vector(9, 32)</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">static <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/llt">LLT</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a73e961aa3509555c9944d502a52d1303">V10S32</a> = LLT::fixed_vector(10, 32)</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">static <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/llt">LLT</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a53954ac3898aff9426fc131d14a84f11">V11S32</a> = LLT::fixed_vector(11, 32)</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">static <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/llt">LLT</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a11d102c56b1f897e6886c283d8f16ce4">V12S32</a> = LLT::fixed_vector(12, 32)</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">static <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/llt">LLT</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a83756b36d1fca7fb0054ab52622cda67">V16S32</a> = LLT::fixed_vector(16, 32)</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">static <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/llt">LLT</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a61cf1ca010a7d653f1cf0ddefa7a8e6d">V32S32</a> = LLT::fixed_vector(32, 32)</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">static <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/llt">LLT</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#acb4ecd614e176840d5b2360a176f1333">V2S64</a> = LLT::fixed_vector(2, 64)</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">static <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/llt">LLT</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a0900073ce203e689dc42c702ba6a5c98">V3S64</a> = LLT::fixed_vector(3, 64)</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">static <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/llt">LLT</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a214d79cea6eb493a2f95b0170886311a">V4S64</a> = LLT::fixed_vector(4, 64)</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">static <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/llt">LLT</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a8c4f0c5559c18078956303fa71b2a027">V5S64</a> = LLT::fixed_vector(5, 64)</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">static <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/llt">LLT</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#aa95cd588b298b4861271199e3afe971f">V6S64</a> = LLT::fixed_vector(6, 64)</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">static <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/llt">LLT</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a839fd594af5fb0c910f8c3fa13e154a9">V7S64</a> = LLT::fixed_vector(7, 64)</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">static <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/llt">LLT</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a0c9c5c4bf19122ed92afa6fe3e70b158">V8S64</a> = LLT::fixed_vector(8, 64)</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">static <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/llt">LLT</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a7af378812d0f59470e1ad5ff1ac40679">V16S64</a> = LLT::fixed_vector(16, 64)</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">static <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/llt">LLT</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ad61c521a33598d8ca5b07dd4e0f03087">V2S128</a> = LLT::fixed_vector(2, 128)</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">static <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/llt">LLT</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a9e404048aa9a1687a9ec6f9d9420bf39">V4S128</a> = LLT::fixed_vector(4, 128)</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">static std::initializer_list&lt; <a href="/web-llvm/docs/api/classes/llvm/llt">LLT</a> &gt;</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ada70cb9213ffddaebab099c55f886d19">AllScalarTypes</a> = ...</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">static std::initializer_list&lt; <a href="/web-llvm/docs/api/classes/llvm/llt">LLT</a> &gt;</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a60fec3ee73a795e286972083bf85a68e">AllS16Vectors</a> = ...</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">static std::initializer_list&lt; <a href="/web-llvm/docs/api/classes/llvm/llt">LLT</a> &gt;</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a4b69b2b66bc8186c8b21b62fe41d444d">AllS32Vectors</a> = ...</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">static std::initializer_list&lt; <a href="/web-llvm/docs/api/classes/llvm/llt">LLT</a> &gt;</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#abf8037dd8ffb10bb4c5fe61c6d0c5c6c">AllS64Vectors</a> = ...</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">static constexpr unsigned</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a795662e773d2eda28caf873fa6eb70c4">SPDenormModeBitField</a> = ...</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">static constexpr unsigned</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a1fff431f58bc2af2caae5f611ba0791f">FPEnvModeBitField</a> = ...</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">static constexpr unsigned</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#aa0516ba249c5d556a3ee34bfd27737f3">FPEnvTrapBitField</a> = ...</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ad78e062f62e0d6e453941fb4ca843e4d">DEBUG_TYPE</a>&nbsp;&nbsp;&nbsp;"amdgpu-legalinfo"</td>
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

<p>This file implements the targeting of the Machinelegalizer class for <a href="/web-llvm/docs/api/namespaces/llvm/amdgpu">AMDGPU</a>.</p>


<div class="doxyXrefSect">
<dl class="doxyXrefSectList">
<dt class="doxyXrefSectTitle"><a href=/web-llvm/docs/api/pages/todo/#_todo000011>Todo</a></dt>
<dd class="doxyXrefSectDescription">
<p>This should be generated by <a href="/web-llvm/docs/api/namespaces/llvm/tablegen">TableGen</a>.</p>
</dd>
</dl>
</div>

<div class="doxySectionDef">

## Functions

### allowApproxFunc() {#a16c22435b21cfe335c972d971e29b0d7}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool allowApproxFunc (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/machinefunction">MachineFunction</a> &amp; MF, unsigned Flags)</td>
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



<p>Definition at line 3266 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/amdgpulegalizerinfo-cpp">AMDGPULegalizerInfo.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/classes/llvm/machineinstr/#aafacf84de1cb994a92dc045f4aa1d518a4802af6d0cf3b900adb6296bccedf2a0">llvm::MachineInstr::FmAfn</a>, <a href="/web-llvm/docs/api/classes/llvm/machinefunction/#af777ff93c9e07a6ff5ffe3226deb3e76">llvm::MachineFunction::getTarget</a>, <a href="/web-llvm/docs/api/classes/llvm/targetmachine/#ab1fb67187fc37e569cc5171cbebba873">llvm::TargetMachine::Options</a> and <a href="/web-llvm/docs/api/files/lib/lib/debuginfo/lib/debuginfo/logicalview/lib/debuginfo/logicalview/core/lvoptions-cpp/#ab4088b7a11f3cbc38ac16a6e9c72494e">Options</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/classes/llvm/amdgpulegalizerinfo/#a5552c2fa1505412508e493149af31543">llvm::AMDGPULegalizerInfo::legalizeFExp</a> and <a href="/web-llvm/docs/api/classes/llvm/amdgpulegalizerinfo/#a20562025b5dd6e948bb3346d29417237">llvm::AMDGPULegalizerInfo::legalizeFSQRTF32</a>.</p>

</div>
</div>

### bitcastToRegisterType() {#a6eb46b558dd23ba908853adcc6ba76b7}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">LegalizeMutation bitcastToRegisterType (unsigned TypeIdx)</td>
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



<p>Definition at line 188 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/amdgpulegalizerinfo-cpp">AMDGPULegalizerInfo.cpp</a>.</p>


<p>Reference <a href="#a639711ef50cb300db9e9ade1445ccf07">getBitcastRegisterType</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/classes/llvm/amdgpulegalizerinfo/#a44a4d4c034685aa34a4e8f62b0976e6c">llvm::AMDGPULegalizerInfo::AMDGPULegalizerInfo</a>.</p>

</div>
</div>

### bitcastToVectorElement32() {#a0aab1c76215e1773caa058744d6ae6af}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">LegalizeMutation bitcastToVectorElement32 (unsigned TypeIdx)</td>
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



<p>Definition at line 195 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/amdgpulegalizerinfo-cpp">AMDGPULegalizerInfo.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/silowercontrolflow-cpp/#a4868c5d81c5ccc98c47aeab6244346a0">assert</a>, <a href="/web-llvm/docs/api/classes/llvm/elementcount/#a584cb8dfa0090b33a969c4dda27337f6">llvm::ElementCount::getFixed</a>, <a href="/web-llvm/docs/api/classes/llvm/llt/#ae74a60e5edcee0609a1e4fddc62a8a01">llvm::LLT::scalarOrVector</a> and <a href="/web-llvm/docs/api/files/lib/lib/analysis/inlineorder-cpp/#a7ee6f0cb51c3b9056199e9a0001fe8c3a6f6cb72d544962fa333e2e34ce64f719">Size</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/classes/llvm/amdgpulegalizerinfo/#a44a4d4c034685aa34a4e8f62b0976e6c">llvm::AMDGPULegalizerInfo::AMDGPULegalizerInfo</a>.</p>

</div>
</div>

### buildBufferLoad() {#ae6e9dca782411211a3526572f6ebeb33}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void buildBufferLoad (unsigned Opc, <a href="/web-llvm/docs/api/classes/llvm/register">Register</a> LoadDstReg, <a href="/web-llvm/docs/api/classes/llvm/register">Register</a> RSrc, <a href="/web-llvm/docs/api/classes/llvm/register">Register</a> VIndex, <a href="/web-llvm/docs/api/classes/llvm/register">Register</a> VOffset, <a href="/web-llvm/docs/api/classes/llvm/register">Register</a> SOffset, unsigned ImmOffset, unsigned Format, unsigned AuxiliaryData, <a href="/web-llvm/docs/api/classes/llvm/machinememoperand">MachineMemOperand</a> * MMO, bool IsTyped, bool HasVIndex, <a href="/web-llvm/docs/api/classes/llvm/machineirbuilder">MachineIRBuilder</a> &amp; B)</td>
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



<p>Definition at line 5956 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/amdgpulegalizerinfo-cpp">AMDGPULegalizerInfo.cpp</a>.</p>


<p>Reference <a href="/web-llvm/docs/api/files/lib/lib/ir/builtingcs-cpp/#ae76959fe811ba090de4cba69ac00f1da">B</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/classes/llvm/amdgpulegalizerinfo/#a89e5277b1b90b54ea21a51120f9a4206">llvm::AMDGPULegalizerInfo::legalizeBufferLoad</a>.</p>

</div>
</div>

### castBufferRsrcArgToV4I32() {#a9d84441ae7638d9c27873f5a3810cb88}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void castBufferRsrcArgToV4I32 (<a href="/web-llvm/docs/api/classes/llvm/machineinstr">MachineInstr</a> &amp; MI, <a href="/web-llvm/docs/api/classes/llvm/machineirbuilder">MachineIRBuilder</a> &amp; B, unsigned Idx)</td>
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



<p>Definition at line 645 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/amdgpulegalizerinfo-cpp">AMDGPULegalizerInfo.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/files/lib/lib/ir/builtingcs-cpp/#ae76959fe811ba090de4cba69ac00f1da">B</a>, <a href="#a5a32fa3ab512ce8c3afa4e68c2b56765">castBufferRsrcToV4I32</a>, <a href="/web-llvm/docs/api/classes/llvm/machineoperand/#ac0035d7c1c860501c877c20e6e93297b">llvm::MachineOperand::getReg</a>, <a href="#abb71b9eb64250d4491336cf106be74eb">hasBufferRsrcWorkaround</a>, <a href="/web-llvm/docs/api/files/lib/lib/codegen/lib/codegen/globalisel/irtranslator-cpp/#abe44dfdea65b4f7e11e0a608ab708b76">MI</a> and <a href="/web-llvm/docs/api/classes/llvm/machineoperand/#a682ba82f42f7903d0000ffbb13ea3b57">llvm::MachineOperand::setReg</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/classes/llvm/amdgpulegalizerinfo/#a3cc7860fbf211f566f62809ac1144023">llvm::AMDGPULegalizerInfo::legalizeBufferAtomic</a>, <a href="/web-llvm/docs/api/classes/llvm/amdgpulegalizerinfo/#a89e5277b1b90b54ea21a51120f9a4206">llvm::AMDGPULegalizerInfo::legalizeBufferLoad</a>, <a href="/web-llvm/docs/api/classes/llvm/amdgpulegalizerinfo/#a2324ad614c957fc91b34a00f32e89d60">llvm::AMDGPULegalizerInfo::legalizeBufferStore</a>, <a href="/web-llvm/docs/api/classes/llvm/amdgpulegalizerinfo/#a51ac04efbaa3282a12478341fa0a7b9a">llvm::AMDGPULegalizerInfo::legalizeSBufferPrefetch</a> and <a href="/web-llvm/docs/api/classes/llvm/amdgpulegalizerinfo/#a5fb58d2b96b0e7a4a021fbe21869aaa8">llvm::AMDGPULegalizerInfo::legalizeStore</a>.</p>

</div>
</div>

### castBufferRsrcFromV4I32() {#a78249707a06ea5161d8c6bbb442ea46c}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">LLT castBufferRsrcFromV4I32 (<a href="/web-llvm/docs/api/classes/llvm/machineinstr">MachineInstr</a> &amp; MI, <a href="/web-llvm/docs/api/classes/llvm/machineirbuilder">MachineIRBuilder</a> &amp; B, <a href="/web-llvm/docs/api/classes/llvm/machineregisterinfo">MachineRegisterInfo</a> &amp; MRI, unsigned Idx)</td>
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

<p>Mutates IR (typicaly a load instruction) to use a &lt;4 x s32&gt; as the initial type of the operand <span class="doxyComputerOutput">idx</span> and then to transform it to a <span class="doxyComputerOutput">p8</span> via bitcasts and inttoptr.</p>


<p>In addition, handle vectors of p8. Returns the new type.</p>


<p>Definition at line 585 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/amdgpulegalizerinfo-cpp">AMDGPULegalizerInfo.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/files/lib/lib/ir/builtingcs-cpp/#ae76959fe811ba090de4cba69ac00f1da">B</a>, <a href="#a64443e60c47deb77ad3bb491d2da3c5f">getBufferRsrcRegisterType</a>, <a href="#a0440dee786271aa77b3f640b1c63363c">getBufferRsrcScalarType</a>, <a href="/web-llvm/docs/api/classes/llvm/machineoperand/#ac0035d7c1c860501c877c20e6e93297b">llvm::MachineOperand::getReg</a>, <a href="#abb71b9eb64250d4491336cf106be74eb">hasBufferRsrcWorkaround</a>, <a href="/web-llvm/docs/api/files/lib/lib/support/md5-cpp/#ac0eafdc9ee161b71e7af98af736952fd">I</a>, <a href="/web-llvm/docs/api/files/lib/lib/codegen/lib/codegen/globalisel/irtranslator-cpp/#abe44dfdea65b4f7e11e0a608ab708b76">MI</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64advsimdscalarpass-cpp/#aacd2ab195054a3e6a74bfbb9d5d571c8">MRI</a>, <a href="#a33c95d7d51d4b0b421aaf3d40796b859">S32</a>, <a href="/web-llvm/docs/api/classes/llvm/llt/#a67021459c7ef8f9a634b4eac7ffd0f96">llvm::LLT::scalar</a> and <a href="/web-llvm/docs/api/classes/llvm/machineoperand/#a682ba82f42f7903d0000ffbb13ea3b57">llvm::MachineOperand::setReg</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/classes/llvm/amdgpulegalizerinfo/#a89e5277b1b90b54ea21a51120f9a4206">llvm::AMDGPULegalizerInfo::legalizeBufferLoad</a>, <a href="/web-llvm/docs/api/classes/llvm/amdgpulegalizerinfo/#af13d2c38b3bf7586a8f07d511eda68e8">llvm::AMDGPULegalizerInfo::legalizeLoad</a> and <a href="/web-llvm/docs/api/classes/llvm/amdgpulegalizerinfo/#ae0d1532576a7c6e3bda2d8966700d27a">llvm::AMDGPULegalizerInfo::legalizeSBufferLoad</a>.</p>

</div>
</div>

### castBufferRsrcToV4I32() {#a5a32fa3ab512ce8c3afa4e68c2b56765}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">Register castBufferRsrcToV4I32 (<a href="/web-llvm/docs/api/classes/llvm/register">Register</a> Pointer, <a href="/web-llvm/docs/api/classes/llvm/machineirbuilder">MachineIRBuilder</a> &amp; B)</td>
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

<p>Cast a buffer resource (an address space 8 pointer) into a 4xi32, which is the form in which the value must be in order to be passed to the low-level representations used for MUBUF/MTBUF intrinsics.</p>


<p>This is a hack, which is needed in order to account for the fact that we can't define a register class for s128 without breaking <a href="/web-llvm/docs/api/classes/llvm/selectiondag">SelectionDAG</a>.</p>


<p>Definition at line 626 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/amdgpulegalizerinfo-cpp">AMDGPULegalizerInfo.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/files/lib/lib/ir/builtingcs-cpp/#ae76959fe811ba090de4cba69ac00f1da">B</a>, <a href="#a64443e60c47deb77ad3bb491d2da3c5f">getBufferRsrcRegisterType</a>, <a href="#a0440dee786271aa77b3f640b1c63363c">getBufferRsrcScalarType</a>, <a href="/web-llvm/docs/api/files/lib/lib/support/md5-cpp/#ac0eafdc9ee161b71e7af98af736952fd">I</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64advsimdscalarpass-cpp/#aacd2ab195054a3e6a74bfbb9d5d571c8">MRI</a>, <a href="/web-llvm/docs/api/classes/llvm/smallvectortemplatebase/#af42bfbc067df27c19ee2fc859df58799">llvm::SmallVectorTemplateBase&lt; T, bool &gt;::push_back</a> and <a href="/web-llvm/docs/api/classes/llvm/llt/#a67021459c7ef8f9a634b4eac7ffd0f96">llvm::LLT::scalar</a>.</p>


<p>Referenced by <a href="#a9d84441ae7638d9c27873f5a3810cb88">castBufferRsrcArgToV4I32</a> and <a href="/web-llvm/docs/api/classes/llvm/amdgpulegalizerinfo/#af3c20d55579ac56788b8134a4d3e724f">llvm::AMDGPULegalizerInfo::fixStoreSourceType</a>.</p>

</div>
</div>

### convertImageAddrToPacked() {#ad049a79d46df2c25561d90e9d80fb5e3}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void convertImageAddrToPacked (<a href="/web-llvm/docs/api/classes/llvm/machineirbuilder">MachineIRBuilder</a> &amp; B, <a href="/web-llvm/docs/api/classes/llvm/machineinstr">MachineInstr</a> &amp; MI, int DimIdx, int NumVAddrs)</td>
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

<p>Convert from separate vaddr components to a single vector address register, and replace the remaining operands with $noreg.</p>

<p>Definition at line 6356 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/amdgpulegalizerinfo-cpp">AMDGPULegalizerInfo.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/silowercontrolflow-cpp/#a4868c5d81c5ccc98c47aeab6244346a0">assert</a>, <a href="/web-llvm/docs/api/files/lib/lib/ir/builtingcs-cpp/#ae76959fe811ba090de4cba69ac00f1da">B</a>, <a href="/web-llvm/docs/api/classes/llvm/llt/#acd1eca3232b7b3072543294cd2377a37">llvm::LLT::fixed_vector</a>, <a href="/web-llvm/docs/api/classes/llvm/srcop/#ae229785d0c8a8ce25d34be18fe150a54">llvm::SrcOp::getReg</a>, <a href="/web-llvm/docs/api/files/lib/lib/support/md5-cpp/#ac0eafdc9ee161b71e7af98af736952fd">I</a>, <a href="/web-llvm/docs/api/files/lib/lib/codegen/lib/codegen/globalisel/irtranslator-cpp/#abe44dfdea65b4f7e11e0a608ab708b76">MI</a>, <a href="/web-llvm/docs/api/classes/llvm/smallvectortemplatebase/#af42bfbc067df27c19ee2fc859df58799">llvm::SmallVectorTemplateBase&lt; T, bool &gt;::push_back</a>, <a href="#a33c95d7d51d4b0b421aaf3d40796b859">S32</a>, <a href="/web-llvm/docs/api/classes/llvm/llt/#a67021459c7ef8f9a634b4eac7ffd0f96">llvm::LLT::scalar</a> and <a href="/web-llvm/docs/api/classes/llvm/smallvectortemplatecommon/#a1c479a8c434377c2b8cb056bdfdfc201">llvm::SmallVectorTemplateCommon&lt; T, typename &gt;::size</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/classes/llvm/amdgpulegalizerinfo/#ad0be6e871a184d6f7b814515324eee1b">llvm::AMDGPULegalizerInfo::legalizeImageIntrinsic</a>.</p>

</div>
</div>

### elementTypeIsLegal() {#aed4feaa9baf8df7fe949b9a5ce246646}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">LegalityPredicate elementTypeIsLegal (unsigned TypeIdx)</td>
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



<p>Definition at line 272 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/amdgpulegalizerinfo-cpp">AMDGPULegalizerInfo.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/classes/llvm/llt/#aa24450f600cabd7212bd264a6dbc190c">llvm::LLT::getElementType</a>, <a href="/web-llvm/docs/api/classes/llvm/llt/#a956ffd0de93798f523683b447646dd92">llvm::LLT::getSizeInBits</a>, <a href="/web-llvm/docs/api/classes/llvm/llt/#a7da5cc6e8aadd4d5fb6dd68f8ec12b7e">llvm::LLT::isVector</a> and <a href="/web-llvm/docs/api/classes/llvm/llt/#a67021459c7ef8f9a634b4eac7ffd0f96">llvm::LLT::scalar</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/classes/llvm/amdgpulegalizerinfo/#a44a4d4c034685aa34a4e8f62b0976e6c">llvm::AMDGPULegalizerInfo::AMDGPULegalizerInfo</a>.</p>

</div>
</div>

### emitReciprocalU64() {#a62e3406e85438cd0a8d5e3de179ef6eb}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">std::pair&lt; Register, Register &gt; emitReciprocalU64 (<a href="/web-llvm/docs/api/classes/llvm/machineirbuilder">MachineIRBuilder</a> &amp; B, <a href="/web-llvm/docs/api/classes/llvm/register">Register</a> Val)</td>
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



<p>Definition at line 4540 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/amdgpulegalizerinfo-cpp">AMDGPULegalizerInfo.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/files/lib/lib/ir/builtingcs-cpp/#ae76959fe811ba090de4cba69ac00f1da">B</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#aab3863f16cb0767af49f0dd63bc5aa90">llvm::bit_cast</a>, <a href="#a33c95d7d51d4b0b421aaf3d40796b859">S32</a> and <a href="/web-llvm/docs/api/classes/llvm/llt/#a67021459c7ef8f9a634b4eac7ffd0f96">llvm::LLT::scalar</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/classes/llvm/amdgpulegalizerinfo/#a93bbde2af63d129f752ef7c3a0f84c15">llvm::AMDGPULegalizerInfo::legalizeUnsignedDIV_REM64Impl</a>.</p>

</div>
</div>

### extractF64Exponent() {#a47ea7f32b98178dbcb9bf3d1ff00daa1}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">MachineInstrBuilder extractF64Exponent (<a href="/web-llvm/docs/api/classes/llvm/register">Register</a> Hi, <a href="/web-llvm/docs/api/classes/llvm/machineirbuilder">MachineIRBuilder</a> &amp; B)</td>
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



<p>Definition at line 2508 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/amdgpulegalizerinfo-cpp">AMDGPULegalizerInfo.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/files/lib/lib/ir/builtingcs-cpp/#ae76959fe811ba090de4cba69ac00f1da">B</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a9ac8e4e13ad96a39c3f8db9ed633ad2bac1a5298f939e87e8f962a5edfc206918">llvm::Hi</a>, <a href="#a33c95d7d51d4b0b421aaf3d40796b859">S32</a> and <a href="/web-llvm/docs/api/classes/llvm/llt/#a67021459c7ef8f9a634b4eac7ffd0f96">llvm::LLT::scalar</a>.</p>

</div>
</div>

### fewerEltsToSize64Vector() {#a3b5805e73f162bbb84584fbc2091806e}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">LegalizeMutation fewerEltsToSize64Vector (unsigned TypeIdx)</td>
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



<p>Definition at line 110 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/amdgpulegalizerinfo-cpp">AMDGPULegalizerInfo.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/classes/llvm/elementcount/#a584cb8dfa0090b33a969c4dda27337f6">llvm::ElementCount::getFixed</a>, <a href="/web-llvm/docs/api/classes/llvm/llt/#ae74a60e5edcee0609a1e4fddc62a8a01">llvm::LLT::scalarOrVector</a> and <a href="/web-llvm/docs/api/files/lib/lib/analysis/inlineorder-cpp/#a7ee6f0cb51c3b9056199e9a0001fe8c3a6f6cb72d544962fa333e2e34ce64f719">Size</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/classes/llvm/amdgpulegalizerinfo/#a44a4d4c034685aa34a4e8f62b0976e6c">llvm::AMDGPULegalizerInfo::AMDGPULegalizerInfo</a>.</p>

</div>
</div>

### getBitcastRegisterType() {#a639711ef50cb300db9e9ade1445ccf07}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">LLT getBitcastRegisterType (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/llt">LLT</a> Ty)</td>
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



<p>Definition at line 176 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/amdgpulegalizerinfo-cpp">AMDGPULegalizerInfo.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/classes/llvm/elementcount/#a584cb8dfa0090b33a969c4dda27337f6">llvm::ElementCount::getFixed</a>, <a href="/web-llvm/docs/api/classes/llvm/llt/#a67021459c7ef8f9a634b4eac7ffd0f96">llvm::LLT::scalar</a>, <a href="/web-llvm/docs/api/classes/llvm/llt/#ae74a60e5edcee0609a1e4fddc62a8a01">llvm::LLT::scalarOrVector</a> and <a href="/web-llvm/docs/api/files/lib/lib/analysis/inlineorder-cpp/#a7ee6f0cb51c3b9056199e9a0001fe8c3a6f6cb72d544962fa333e2e34ce64f719">Size</a>.</p>


<p>Referenced by <a href="#a6eb46b558dd23ba908853adcc6ba76b7">bitcastToRegisterType</a>, <a href="/web-llvm/docs/api/classes/llvm/amdgpulegalizerinfo/#af3c20d55579ac56788b8134a4d3e724f">llvm::AMDGPULegalizerInfo::fixStoreSourceType</a>, <a href="/web-llvm/docs/api/classes/llvm/amdgpulegalizerinfo/#a89e5277b1b90b54ea21a51120f9a4206">llvm::AMDGPULegalizerInfo::legalizeBufferLoad</a> and <a href="/web-llvm/docs/api/classes/llvm/amdgpulegalizerinfo/#ae0d1532576a7c6e3bda2d8966700d27a">llvm::AMDGPULegalizerInfo::legalizeSBufferLoad</a>.</p>

</div>
</div>

### getBufferAtomicPseudo() {#a0356a7c051be3c82d2c7da7e0bdb229c}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">unsigned getBufferAtomicPseudo (<a href="/web-llvm/docs/api/namespaces/llvm/intrinsic/#a80add6b3b1cdaec560907995127adc16">Intrinsic::ID</a> IntrID)</td>
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



<p>Definition at line 6138 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/amdgpulegalizerinfo-cpp">AMDGPULegalizerInfo.cpp</a>.</p>


<p>Reference <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/support/errorhandling-h/#ace243f5c25697a1107cce46626b3dc94">llvm_unreachable</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/classes/llvm/amdgpulegalizerinfo/#a3cc7860fbf211f566f62809ac1144023">llvm::AMDGPULegalizerInfo::legalizeBufferAtomic</a>.</p>

</div>
</div>

### getBufferRsrcRegisterType() {#a64443e60c47deb77ad3bb491d2da3c5f}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">LLT getBufferRsrcRegisterType (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/llt">LLT</a> Ty)</td>
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



<p>Definition at line 169 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/amdgpulegalizerinfo-cpp">AMDGPULegalizerInfo.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/classes/llvm/llt/#acd1eca3232b7b3072543294cd2377a37">llvm::LLT::fixed_vector</a> and <a href="/web-llvm/docs/api/classes/llvm/llt/#a67021459c7ef8f9a634b4eac7ffd0f96">llvm::LLT::scalar</a>.</p>


<p>Referenced by <a href="#a78249707a06ea5161d8c6bbb442ea46c">castBufferRsrcFromV4I32</a> and <a href="#a5a32fa3ab512ce8c3afa4e68c2b56765">castBufferRsrcToV4I32</a>.</p>

</div>
</div>

### getBufferRsrcScalarType() {#a0440dee786271aa77b3f640b1c63363c}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">LLT getBufferRsrcScalarType (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/llt">LLT</a> Ty)</td>
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



<p>Definition at line 162 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/amdgpulegalizerinfo-cpp">AMDGPULegalizerInfo.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/classes/llvm/llt/#a67021459c7ef8f9a634b4eac7ffd0f96">llvm::LLT::scalar</a> and <a href="/web-llvm/docs/api/classes/llvm/llt/#a5360139c6b31d85cf3e29e2e6b7cf873">llvm::LLT::vector</a>.</p>


<p>Referenced by <a href="#a78249707a06ea5161d8c6bbb442ea46c">castBufferRsrcFromV4I32</a> and <a href="#a5a32fa3ab512ce8c3afa4e68c2b56765">castBufferRsrcToV4I32</a>.</p>

</div>
</div>

### getMad() {#a879e21eca00dd442c2623c505ca81b6e}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">Register getMad (<a href="/web-llvm/docs/api/classes/llvm/machineirbuilder">MachineIRBuilder</a> &amp; B, <a href="/web-llvm/docs/api/classes/llvm/llt">LLT</a> Ty, <a href="/web-llvm/docs/api/classes/llvm/register">Register</a> X, <a href="/web-llvm/docs/api/classes/llvm/register">Register</a> Y, <a href="/web-llvm/docs/api/classes/llvm/register">Register</a> Z, unsigned Flags)</td>
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



<p>Definition at line 3351 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/amdgpulegalizerinfo-cpp">AMDGPULegalizerInfo.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/files/lib/lib/ir/builtingcs-cpp/#ae76959fe811ba090de4cba69ac00f1da">B</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#aac36edd0f1ce976f0025c98e88d3830eab48b2a9934af7a531cfd7236ded9d50e">llvm::FMul</a>, <a href="/web-llvm/docs/api/files/lib/lib/tablegen/tablegenbackendskeleton-cpp/#ab60f28d7a141ac46ccc200176a1bca8b">X</a> and <a href="/web-llvm/docs/api/files/lib/lib/tablegen/tablegenbackendskeleton-cpp/#a262774d3e5186511427e5b2414a85f7f">Y</a>.</p>

</div>
</div>

### getPow2ScalarType() {#ae9bc1717e31ed947b2eae89a230c744b}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">LLT getPow2ScalarType (<a href="/web-llvm/docs/api/classes/llvm/llt">LLT</a> Ty)</td>
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



<p>Definition at line 63 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/amdgpulegalizerinfo-cpp">AMDGPULegalizerInfo.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/namespaces/llvm/#a058782b98991f0719657d9008d3df41b">llvm::Log2_32_Ceil</a> and <a href="/web-llvm/docs/api/classes/llvm/llt/#a67021459c7ef8f9a634b4eac7ffd0f96">llvm::LLT::scalar</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/classes/llvm/amdgpulegalizerinfo/#ae0d1532576a7c6e3bda2d8966700d27a">llvm::AMDGPULegalizerInfo::legalizeSBufferLoad</a>.</p>

</div>
</div>

### getPow2VectorType() {#ae6dc00935578ac3d7b43326b5f02b2bc}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">LLT getPow2VectorType (<a href="/web-llvm/docs/api/classes/llvm/llt">LLT</a> Ty)</td>
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



<p>Definition at line 56 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/amdgpulegalizerinfo-cpp">AMDGPULegalizerInfo.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/classes/llvm/elementcount/#a584cb8dfa0090b33a969c4dda27337f6">llvm::ElementCount::getFixed</a> and <a href="/web-llvm/docs/api/namespaces/llvm/#a058782b98991f0719657d9008d3df41b">llvm::Log2_32_Ceil</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/classes/llvm/amdgpulegalizerinfo/#ae0d1532576a7c6e3bda2d8966700d27a">llvm::AMDGPULegalizerInfo::legalizeSBufferLoad</a>.</p>

</div>
</div>

### hasBufferRsrcWorkaround() {#abb71b9eb64250d4491336cf106be74eb}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool hasBufferRsrcWorkaround (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/llt">LLT</a> Ty)</td>
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



<p>Definition at line 478 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/amdgpulegalizerinfo-cpp">AMDGPULegalizerInfo.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/namespaces/llvm/amdgpuas/#a899ad5bfccfc22965a6714929a3dfae1af3a547aa91b97183a165b876de8e24d8">llvm::AMDGPUAS::BUFFER_RESOURCE</a> and <a href="#abb71b9eb64250d4491336cf106be74eb">hasBufferRsrcWorkaround</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/classes/llvm/amdgpulegalizerinfo/#a44a4d4c034685aa34a4e8f62b0976e6c">llvm::AMDGPULegalizerInfo::AMDGPULegalizerInfo</a>, <a href="#a9d84441ae7638d9c27873f5a3810cb88">castBufferRsrcArgToV4I32</a>, <a href="#a78249707a06ea5161d8c6bbb442ea46c">castBufferRsrcFromV4I32</a>, <a href="/web-llvm/docs/api/classes/llvm/amdgpulegalizerinfo/#af3c20d55579ac56788b8134a4d3e724f">llvm::AMDGPULegalizerInfo::fixStoreSourceType</a>, <a href="#abb71b9eb64250d4491336cf106be74eb">hasBufferRsrcWorkaround</a>, <a href="#ad2c8a875d4d2a4e73f7a48e64226b265">isLoadStoreLegal</a>, <a href="/web-llvm/docs/api/classes/llvm/amdgpulegalizerinfo/#a89e5277b1b90b54ea21a51120f9a4206">llvm::AMDGPULegalizerInfo::legalizeBufferLoad</a>, <a href="/web-llvm/docs/api/classes/llvm/amdgpulegalizerinfo/#af13d2c38b3bf7586a8f07d511eda68e8">llvm::AMDGPULegalizerInfo::legalizeLoad</a>, <a href="/web-llvm/docs/api/classes/llvm/amdgpulegalizerinfo/#ae0d1532576a7c6e3bda2d8966700d27a">llvm::AMDGPULegalizerInfo::legalizeSBufferLoad</a>, <a href="/web-llvm/docs/api/classes/llvm/amdgpulegalizerinfo/#a5fb58d2b96b0e7a4a021fbe21869aaa8">llvm::AMDGPULegalizerInfo::legalizeStore</a> and <a href="#ac6f0c363a0260f50a2e3dae5b8c00d21">loadStoreBitcastWorkaround</a>.</p>

</div>
</div>

### isIllegalRegisterType() {#aa5fe965eac66ae9ebc69835fe44c679d}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">LegalityPredicate isIllegalRegisterType (unsigned TypeIdx)</td>
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



<p>Definition at line 264 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/amdgpulegalizerinfo-cpp">AMDGPULegalizerInfo.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/classes/llvm/siregisterinfo/#a7d8aef424553a9b93de21ced693f0b09">llvm::SIRegisterInfo::getSGPRClassForBitWidth</a> and <a href="#a2ea867ab6af309ac37d89c0ac9242600">isRegisterType</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/classes/llvm/amdgpulegalizerinfo/#a44a4d4c034685aa34a4e8f62b0976e6c">llvm::AMDGPULegalizerInfo::AMDGPULegalizerInfo</a>.</p>

</div>
</div>

### isKnownNonNull() {#aff707b57a26889c4290a79001f12fd20}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool isKnownNonNull (<a href="/web-llvm/docs/api/classes/llvm/register">Register</a> Val, <a href="/web-llvm/docs/api/classes/llvm/machineregisterinfo">MachineRegisterInfo</a> &amp; MRI, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/amdgputargetmachine">AMDGPUTargetMachine</a> &amp; TM, unsigned AddrSpace)</td>
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

<p>Return true if the value is a known valid address, such that a null check is not necessary.</p>

<p>Definition at line 2292 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/amdgpulegalizerinfo-cpp">AMDGPULegalizerInfo.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/classes/llvm/constantint/#aa8f4be0661aa64f5b1f20b15e93bb403">llvm::ConstantInt::getSExtValue</a> and <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64advsimdscalarpass-cpp/#aacd2ab195054a3e6a74bfbb9d5d571c8">MRI</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/classes/llvm/amdgpulegalizerinfo/#a805950c6af7deaddb2d8fbcaf4ea011b">llvm::AMDGPULegalizerInfo::legalizeAddrSpaceCast</a>.</p>

</div>
</div>

### isLoadStoreLegal() {#ad2c8a875d4d2a4e73f7a48e64226b265}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool isLoadStoreLegal (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/gcnsubtarget">GCNSubtarget</a> &amp; ST, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/structs/llvm/legalityquery">LegalityQuery</a> &amp; Query)</td>
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



<p>Definition at line 511 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/amdgpulegalizerinfo-cpp">AMDGPULegalizerInfo.cpp</a>.</p>


<p>References <a href="#abb71b9eb64250d4491336cf106be74eb">hasBufferRsrcWorkaround</a>, <a href="#a812ebabddd1ad2d8f8bbc6194346e2ed">isLoadStoreSizeLegal</a>, <a href="#a2ea867ab6af309ac37d89c0ac9242600">isRegisterType</a>, <a href="#ac6f0c363a0260f50a2e3dae5b8c00d21">loadStoreBitcastWorkaround</a> and <a href="/web-llvm/docs/api/structs/llvm/legalityquery/#ab28fca6f8145be28b70ad89bb0c741b0">llvm::LegalityQuery::Types</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/classes/llvm/amdgpulegalizerinfo/#a44a4d4c034685aa34a4e8f62b0976e6c">llvm::AMDGPULegalizerInfo::AMDGPULegalizerInfo</a>.</p>

</div>
</div>

### isLoadStoreSizeLegal() {#a812ebabddd1ad2d8f8bbc6194346e2ed}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool isLoadStoreSizeLegal (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/gcnsubtarget">GCNSubtarget</a> &amp; ST, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/structs/llvm/legalityquery">LegalityQuery</a> &amp; Query)</td>
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



<p>Definition at line 405 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/amdgpulegalizerinfo-cpp">AMDGPULegalizerInfo.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/classes/llvm/sitargetlowering/#a21805127d5ae570ea5776ee098c951f1">llvm::SITargetLowering::allowsMisalignedMemoryAccessesImpl</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/silowercontrolflow-cpp/#a4868c5d81c5ccc98c47aeab6244346a0">assert</a>, <a href="/web-llvm/docs/api/namespaces/llvm/amdgpuas/#a899ad5bfccfc22965a6714929a3dfae1a1caf1e287a5fe7250388d66ed72aa0c1">llvm::AMDGPUAS::CONSTANT_ADDRESS_32BIT</a>, <a href="#a807f9ab682878abe0a704736d1f9f298">maxSizeForAddrSpace</a>, <a href="/web-llvm/docs/api/structs/llvm/legalityquery/#a9e26ab57991dfde2757e4790a626d6a3">llvm::LegalityQuery::MMODescrs</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a9bccbe67aaab722783ca4e7c504aaaa7a56a57d29a3f9dda8671b4d6490a94b08">llvm::NotAtomic</a>, <a href="/web-llvm/docs/api/structs/llvm/legalityquery/#afd4ab894cdbdc5888a2d10fa5e5f8333">llvm::LegalityQuery::Opcode</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64mipeepholeopt-cpp/#a9c374320ed4e895f9afa199987182bd2">RegSize</a>, <a href="/web-llvm/docs/api/files/lib/lib/analysis/inlineorder-cpp/#a7ee6f0cb51c3b9056199e9a0001fe8c3a6f6cb72d544962fa333e2e34ce64f719">Size</a> and <a href="/web-llvm/docs/api/structs/llvm/legalityquery/#ab28fca6f8145be28b70ad89bb0c741b0">llvm::LegalityQuery::Types</a>.</p>


<p>Referenced by <a href="#ad2c8a875d4d2a4e73f7a48e64226b265">isLoadStoreLegal</a>.</p>

</div>
</div>

### isNot() {#accff22ec9fbd872b5976a4a2dc20ef56}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool isNot (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/machineregisterinfo">MachineRegisterInfo</a> &amp; MRI, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/machineinstr">MachineInstr</a> &amp; MI)</td>
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



<p>Definition at line 4225 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/amdgpulegalizerinfo-cpp">AMDGPULegalizerInfo.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/namespaces/llvm/#a56f5d55460d7e31fc6c3318882f36ac7">llvm::getIConstantVRegSExtVal</a>, <a href="/web-llvm/docs/api/files/lib/lib/codegen/lib/codegen/globalisel/irtranslator-cpp/#abe44dfdea65b4f7e11e0a608ab708b76">MI</a> and <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64advsimdscalarpass-cpp/#aacd2ab195054a3e6a74bfbb9d5d571c8">MRI</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/classes/anonymous-darwinasmparser-cpp-/darwinasmparser/#a1a972ee6fe54b3bdbfbcf505162a75ea">anonymous{DarwinAsmParser.cpp}::DarwinAsmParser::parseBuildVersion</a>, <a href="/web-llvm/docs/api/classes/anonymous-x86asmparser-cpp-/x86asmparser/#a605f317c5671abb87131f5dcb6b2fe4a">anonymous{X86AsmParser.cpp}::X86AsmParser::ParseDirective</a>, <a href="/web-llvm/docs/api/classes/llvm/mcasmparserextension/#acb5fd683cbbfb19a2e0d78ee46bb283c">llvm::MCAsmParserExtension::parseDirectiveCGProfile</a>, <a href="/web-llvm/docs/api/classes/anonymous-darwinasmparser-cpp-/darwinasmparser/#a6f0111046854925fdf5c7a297f6751c2">anonymous{DarwinAsmParser.cpp}::DarwinAsmParser::parseDirectiveDataRegionEnd</a>, <a href="/web-llvm/docs/api/classes/anonymous-darwinasmparser-cpp-/darwinasmparser/#a7f3b0cb9ef7b3869b91009f946b1d560">anonymous{DarwinAsmParser.cpp}::DarwinAsmParser::parseDirectiveDesc</a>, <a href="/web-llvm/docs/api/classes/anonymous-darwinasmparser-cpp-/darwinasmparser/#aea6c0e51b6f9cf34090c9a86852d932a">anonymous{DarwinAsmParser.cpp}::DarwinAsmParser::parseDirectiveDumpOrLoad</a>, <a href="/web-llvm/docs/api/classes/anonymous-wasmasmparser-cpp-/wasmasmparser/#a83962858abc75bcaf9f4fb6c2390bd64">anonymous{WasmAsmParser.cpp}::WasmAsmParser::ParseDirectiveIdent</a>, <a href="/web-llvm/docs/api/classes/anonymous-elfasmparser-cpp-/elfasmparser/#af1a73cf78dff00db0419941f61c292e6">anonymous{ELFAsmParser.cpp}::ELFAsmParser::parseDirectiveIdent</a>, <a href="/web-llvm/docs/api/classes/anonymous-darwinasmparser-cpp-/darwinasmparser/#adb14af816964063e2e902f6d9586abcd">anonymous{DarwinAsmParser.cpp}::DarwinAsmParser::parseDirectiveIndirectSymbol</a>, <a href="/web-llvm/docs/api/classes/anonymous-darwinasmparser-cpp-/darwinasmparser/#ac817c5437e692128f921c71df5da2fba">anonymous{DarwinAsmParser.cpp}::DarwinAsmParser::parseDirectiveLinkerOption</a>, <a href="/web-llvm/docs/api/classes/anonymous-darwinasmparser-cpp-/darwinasmparser/#a022d1cc063e7491e1378663102c8a4b5">anonymous{DarwinAsmParser.cpp}::DarwinAsmParser::parseDirectiveLsym</a>, <a href="/web-llvm/docs/api/classes/anonymous-darwinasmparser-cpp-/darwinasmparser/#a757668838f5767cbf28d9a5b1201a646">anonymous{DarwinAsmParser.cpp}::DarwinAsmParser::parseDirectiveSection</a>, <a href="/web-llvm/docs/api/classes/anonymous-darwinasmparser-cpp-/darwinasmparser/#a35c606c799d33998f19368dbd9fb5c3a">anonymous{DarwinAsmParser.cpp}::DarwinAsmParser::parseDirectiveSecureLogReset</a>, <a href="/web-llvm/docs/api/classes/anonymous-darwinasmparser-cpp-/darwinasmparser/#a3237e027b109101104739097a3e415da">anonymous{DarwinAsmParser.cpp}::DarwinAsmParser::parseDirectiveSecureLogUnique</a>, <a href="/web-llvm/docs/api/classes/anonymous-elfasmparser-cpp-/elfasmparser/#a532bb23147c49dda31fbd4d08fcef7f1">anonymous{ELFAsmParser.cpp}::ELFAsmParser::parseDirectiveSize</a>, <a href="/web-llvm/docs/api/classes/anonymous-elfasmparser-cpp-/elfasmparser/#a1a1853bf4db9f8b2acf588859ee22f76">anonymous{ELFAsmParser.cpp}::ELFAsmParser::parseDirectiveSubsection</a>, <a href="/web-llvm/docs/api/classes/anonymous-darwinasmparser-cpp-/darwinasmparser/#aa48439c82acdd2f356bfbf9e120e3bb9">anonymous{DarwinAsmParser.cpp}::DarwinAsmParser::parseDirectiveSubsectionsViaSymbols</a>, <a href="/web-llvm/docs/api/classes/anonymous-wasmasmparser-cpp-/wasmasmparser/#adca7252d5d5b7cb17458ac9e482e8bde">anonymous{WasmAsmParser.cpp}::WasmAsmParser::ParseDirectiveSymbolAttribute</a>, <a href="/web-llvm/docs/api/classes/anonymous-elfasmparser-cpp-/elfasmparser/#ace33fcaf2869f1932feb764d96a621fa">anonymous{ELFAsmParser.cpp}::ELFAsmParser::parseDirectiveSymbolAttribute</a>, <a href="/web-llvm/docs/api/classes/anonymous-elfasmparser-cpp-/elfasmparser/#a8a6fc804faec94d60ddd3e1f938a834d">anonymous{ELFAsmParser.cpp}::ELFAsmParser::parseDirectiveSymver</a>, <a href="/web-llvm/docs/api/classes/anonymous-darwinasmparser-cpp-/darwinasmparser/#a865b1c6f63f4309779f26c93bd7030bf">anonymous{DarwinAsmParser.cpp}::DarwinAsmParser::parseDirectiveTBSS</a>, <a href="/web-llvm/docs/api/classes/anonymous-elfasmparser-cpp-/elfasmparser/#a0f36747e0996fc4eecbce6b59683ae50">anonymous{ELFAsmParser.cpp}::ELFAsmParser::parseDirectiveType</a>, <a href="/web-llvm/docs/api/classes/anonymous-elfasmparser-cpp-/elfasmparser/#ae1fb494059109cc71a5ece2c7b99390e">anonymous{ELFAsmParser.cpp}::ELFAsmParser::parseDirectiveVersion</a>, <a href="/web-llvm/docs/api/classes/anonymous-elfasmparser-cpp-/elfasmparser/#ace16ef6d099a8623f20283a2d4f08291">anonymous{ELFAsmParser.cpp}::ELFAsmParser::parseDirectiveWeakref</a>, <a href="/web-llvm/docs/api/classes/anonymous-darwinasmparser-cpp-/darwinasmparser/#a684c8f59f91c7a9a03ed144fef80ba6a">anonymous{DarwinAsmParser.cpp}::DarwinAsmParser::parseDirectiveZerofill</a>, <a href="/web-llvm/docs/api/classes/anonymous-asmparser-cpp-/asmparser/#aa91d3c1b093e3561b948794724961f4b">anonymous{AsmParser.cpp}::AsmParser::parseIdentifier</a>, <a href="/web-llvm/docs/api/classes/anonymous-aarch64asmparser-cpp-/aarch64asmparser/#adc0358b42d36242d132980b3fe8260de">anonymous{AArch64AsmParser.cpp}::AArch64AsmParser::parseInstruction</a>, <a href="/web-llvm/docs/api/classes/anonymous-armasmparser-cpp-/armasmparser/#a89eeee4c3ec5d281810e8ac7572ddee4">anonymous{ARMAsmParser.cpp}::ARMAsmParser::parseInstruction</a>, <a href="/web-llvm/docs/api/classes/anonymous-systemzasmparser-cpp-/systemzasmparser/#ad79a6d97b50d37cfcc0ba24dfc387b10">anonymous{SystemZAsmParser.cpp}::SystemZAsmParser::parseInstruction</a>, <a href="/web-llvm/docs/api/classes/anonymous-x86asmparser-cpp-/x86asmparser/#abf6230cdb8093ea54524821d036b2203">anonymous{X86AsmParser.cpp}::X86AsmParser::parseInstruction</a>, <a href="/web-llvm/docs/api/classes/anonymous-darwinasmparser-cpp-/darwinasmparser/#ada48b8f406d37c059696406dd6177d32">anonymous{DarwinAsmParser.cpp}::DarwinAsmParser::parseMajorMinorVersionComponent</a>, <a href="/web-llvm/docs/api/classes/anonymous-asmparser-cpp-/asmparser/#a6779c29e343b8e71d97734686a3eabd2">anonymous{AsmParser.cpp}::AsmParser::parseMSInlineAsm</a>, <a href="/web-llvm/docs/api/classes/anonymous-masmparser-cpp-/masmparser/#ae48dce9460eac00f49a306f8d48fdf11">anonymous{MasmParser.cpp}::MasmParser::parseMSInlineAsm</a>, <a href="/web-llvm/docs/api/classes/anonymous-darwinasmparser-cpp-/darwinasmparser/#ac2097c2b524a1f2b8a81abdf82679654">anonymous{DarwinAsmParser.cpp}::DarwinAsmParser::parseOptionalTrailingVersionComponent</a>, <a href="/web-llvm/docs/api/classes/anonymous-asmparser-cpp-/hlasmasmparser/#a7ab8a603879e4abd860791912451799c">anonymous{AsmParser.cpp}::HLASMAsmParser::parseStatement</a>, <a href="/web-llvm/docs/api/classes/anonymous-darwinasmparser-cpp-/darwinasmparser/#a11a4d51524eaad36622be26b13c78256">anonymous{DarwinAsmParser.cpp}::DarwinAsmParser::parseVersion</a>, <a href="/web-llvm/docs/api/classes/anonymous-aarch64asmparser-cpp-/aarch64asmparser/#a246c8dfd4ca957b7da4d52cb7805650c">anonymous{AArch64AsmParser.cpp}::AArch64AsmParser::tryParseAdjImm0_63</a>, <a href="/web-llvm/docs/api/classes/anonymous-aarch64asmparser-cpp-/aarch64asmparser/#a72482e46711748fee7ce49e1d66002de">anonymous{AArch64AsmParser.cpp}::AArch64AsmParser::tryParseGPROperand</a>, <a href="/web-llvm/docs/api/classes/anonymous-aarch64asmparser-cpp-/aarch64asmparser/#aedd4ddd3d36c07298e0d1c8ea2903593">anonymous{AArch64AsmParser.cpp}::AArch64AsmParser::tryParseSVEDataVector</a>, <a href="/web-llvm/docs/api/classes/anonymous-aarch64asmparser-cpp-/aarch64asmparser/#aef98635d49b1c38ba8b291b28df6a62d">anonymous{AArch64AsmParser.cpp}::AArch64AsmParser::tryParseSVEPredicateVector</a> and <a href="#a87e58e9d24983c7890c502fbe731f950">verifyCFIntrinsic</a>.</p>

</div>
</div>

### isRegisterClassType() {#a8ac13bffc4ec5811abc67aaa4166e9a8}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool isRegisterClassType (<a href="/web-llvm/docs/api/classes/llvm/llt">LLT</a> Ty)</td>
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



<p>Definition at line 351 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/amdgpulegalizerinfo-cpp">AMDGPULegalizerInfo.cpp</a>.</p>


<p>References <a href="#a60fec3ee73a795e286972083bf85a68e">AllS16Vectors</a>, <a href="#a4b69b2b66bc8186c8b21b62fe41d444d">AllS32Vectors</a>, <a href="#abf8037dd8ffb10bb4c5fe61c6d0c5c6c">AllS64Vectors</a>, <a href="#ada70cb9213ffddaebab099c55f886d19">AllScalarTypes</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#acd1cd968cb420c82d70926920fcdc7d7">llvm::is_contained</a> and <a href="/web-llvm/docs/api/classes/llvm/llt/#a67021459c7ef8f9a634b4eac7ffd0f96">llvm::LLT::scalar</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/classes/llvm/amdgpulegalizerinfo/#a44a4d4c034685aa34a4e8f62b0976e6c">llvm::AMDGPULegalizerInfo::AMDGPULegalizerInfo</a> and <a href="#a6f96e69af9b47cc95fd19cc091b0aea1">isRegisterClassType</a>.</p>

</div>
</div>

### isRegisterClassType() {#a6f96e69af9b47cc95fd19cc091b0aea1}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">LegalityPredicate isRegisterClassType (unsigned TypeIdx)</td>
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



<p>Definition at line 359 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/amdgpulegalizerinfo-cpp">AMDGPULegalizerInfo.cpp</a>.</p>


<p>Reference <a href="#a8ac13bffc4ec5811abc67aaa4166e9a8">isRegisterClassType</a>.</p>

</div>
</div>

### isRegisterSize() {#a3986167503ccf79606f2249e660c9961}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool isRegisterSize (unsigned Size)</td>
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



<p>Definition at line 226 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/amdgpulegalizerinfo-cpp">AMDGPULegalizerInfo.cpp</a>.</p>


<p>References <a href="#aabec8e9bc89e3e905a71769f8be922c1">MaxRegisterSize</a> and <a href="/web-llvm/docs/api/files/lib/lib/analysis/inlineorder-cpp/#a7ee6f0cb51c3b9056199e9a0001fe8c3a6f6cb72d544962fa333e2e34ce64f719">Size</a>.</p>


<p>Referenced by <a href="#a2ea867ab6af309ac37d89c0ac9242600">isRegisterType</a> and <a href="#a1c42298ffb49a95c87577d3e5de46aea">shouldBitcastLoadStoreType</a>.</p>

</div>
</div>

### isRegisterType() {#a2ea867ab6af309ac37d89c0ac9242600}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool isRegisterType (<a href="/web-llvm/docs/api/classes/llvm/llt">LLT</a> Ty)</td>
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



<p>Definition at line 243 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/amdgpulegalizerinfo-cpp">AMDGPULegalizerInfo.cpp</a>.</p>


<p>References <a href="#a3986167503ccf79606f2249e660c9961">isRegisterSize</a> and <a href="#af6ee8616537a0f758b8962b4e5076b35">isRegisterVectorType</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/classes/llvm/amdgpulegalizerinfo/#a44a4d4c034685aa34a4e8f62b0976e6c">llvm::AMDGPULegalizerInfo::AMDGPULegalizerInfo</a>, <a href="#aa5fe965eac66ae9ebc69835fe44c679d">isIllegalRegisterType</a>, <a href="#ad2c8a875d4d2a4e73f7a48e64226b265">isLoadStoreLegal</a>, <a href="#a6828238e57f3a265b56fb009a227af4e">isRegisterType</a>, <a href="/web-llvm/docs/api/classes/llvm/amdgpulegalizerinfo/#af13d2c38b3bf7586a8f07d511eda68e8">llvm::AMDGPULegalizerInfo::legalizeLoad</a>, <a href="/web-llvm/docs/api/classes/llvm/ppclegalizerinfo/#ae83d1a82dbe98543ff9238ae236b5e20">llvm::PPCLegalizerInfo::PPCLegalizerInfo</a> and <a href="#a1c42298ffb49a95c87577d3e5de46aea">shouldBitcastLoadStoreType</a>.</p>

</div>
</div>

### isRegisterType() {#a6828238e57f3a265b56fb009a227af4e}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">LegalityPredicate isRegisterType (unsigned TypeIdx)</td>
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



<p>Definition at line 255 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/amdgpulegalizerinfo-cpp">AMDGPULegalizerInfo.cpp</a>.</p>


<p>Reference <a href="#a2ea867ab6af309ac37d89c0ac9242600">isRegisterType</a>.</p>

</div>
</div>

### isRegisterVectorElementType() {#a31648fb7411d04ec274b46d8dd635564}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool isRegisterVectorElementType (<a href="/web-llvm/docs/api/classes/llvm/llt">LLT</a> EltTy)</td>
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



<p>Definition at line 230 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/amdgpulegalizerinfo-cpp">AMDGPULegalizerInfo.cpp</a>.</p>


<p>Reference <a href="/web-llvm/docs/api/classes/llvm/llt/#a956ffd0de93798f523683b447646dd92">llvm::LLT::getSizeInBits</a>.</p>


<p>Referenced by <a href="#a1c42298ffb49a95c87577d3e5de46aea">shouldBitcastLoadStoreType</a>.</p>

</div>
</div>

### isRegisterVectorType() {#af6ee8616537a0f758b8962b4e5076b35}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool isRegisterVectorType (<a href="/web-llvm/docs/api/classes/llvm/llt">LLT</a> Ty)</td>
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



<p>Definition at line 235 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/amdgpulegalizerinfo-cpp">AMDGPULegalizerInfo.cpp</a>.</p>


<p>Referenced by <a href="#a2ea867ab6af309ac37d89c0ac9242600">isRegisterType</a>.</p>

</div>
</div>

### isSmallOddVector() {#a0dbe048033c8b5adaf283b8fe7de3ba1}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">LegalityPredicate isSmallOddVector (unsigned TypeIdx)</td>
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
<dt>Returns</dt>
<dd><p>true if this is an odd sized vector which should widen by adding an additional element. This is mostly to handle &lt;3 x s16&gt; -&gt; &lt;4 x s16&gt;. This excludes s1 vectors, which should always be scalarized.</p></dd>
</dl>


<p>Definition at line 72 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/amdgpulegalizerinfo-cpp">AMDGPULegalizerInfo.cpp</a>.</p>


<p>Reference <a href="/web-llvm/docs/api/classes/llvm/llt/#a956ffd0de93798f523683b447646dd92">llvm::LLT::getSizeInBits</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/classes/llvm/amdgpulegalizerinfo/#a44a4d4c034685aa34a4e8f62b0976e6c">llvm::AMDGPULegalizerInfo::AMDGPULegalizerInfo</a>.</p>

</div>
</div>

### isWideScalarExtLoadTruncStore() {#ab92c68720091c48aa146f82db0f9ce88}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">LegalityPredicate isWideScalarExtLoadTruncStore (unsigned TypeIdx)</td>
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



<p>Definition at line 367 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/amdgpulegalizerinfo-cpp">AMDGPULegalizerInfo.cpp</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/classes/llvm/amdgpulegalizerinfo/#a44a4d4c034685aa34a4e8f62b0976e6c">llvm::AMDGPULegalizerInfo::AMDGPULegalizerInfo</a>.</p>

</div>
</div>

### isWideVec16() {#a3d552c29a563f3462800870d14e72b0f}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">LegalityPredicate isWideVec16 (unsigned TypeIdx)</td>
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



<p>Definition at line 93 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/amdgpulegalizerinfo-cpp">AMDGPULegalizerInfo.cpp</a>.</p>


<p>Reference <a href="/web-llvm/docs/api/classes/llvm/llt/#a956ffd0de93798f523683b447646dd92">llvm::LLT::getSizeInBits</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/classes/llvm/amdgpulegalizerinfo/#a44a4d4c034685aa34a4e8f62b0976e6c">llvm::AMDGPULegalizerInfo::AMDGPULegalizerInfo</a>.</p>

</div>
</div>

### loadStoreBitcastWorkaround() {#ac6f0c363a0260f50a2e3dae5b8c00d21}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool loadStoreBitcastWorkaround (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/llt">LLT</a> Ty)</td>
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



<p>Definition at line 492 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/amdgpulegalizerinfo-cpp">AMDGPULegalizerInfo.cpp</a>.</p>


<p>References <a href="#a051bcca9a10dfdb5c382173aa0d5a860">EnableNewLegality</a>, <a href="#abb71b9eb64250d4491336cf106be74eb">hasBufferRsrcWorkaround</a> and <a href="/web-llvm/docs/api/files/lib/lib/analysis/inlineorder-cpp/#a7ee6f0cb51c3b9056199e9a0001fe8c3a6f6cb72d544962fa333e2e34ce64f719">Size</a>.</p>


<p>Referenced by <a href="#ad2c8a875d4d2a4e73f7a48e64226b265">isLoadStoreLegal</a> and <a href="#a1c42298ffb49a95c87577d3e5de46aea">shouldBitcastLoadStoreType</a>.</p>

</div>
</div>

### maxSizeForAddrSpace() {#a807f9ab682878abe0a704736d1f9f298}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">unsigned maxSizeForAddrSpace (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/gcnsubtarget">GCNSubtarget</a> &amp; ST, unsigned AS, bool IsLoad, bool IsAtomic)</td>
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



<p>Definition at line 378 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/amdgpulegalizerinfo-cpp">AMDGPULegalizerInfo.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/namespaces/llvm/amdgpuas/#a899ad5bfccfc22965a6714929a3dfae1af3a547aa91b97183a165b876de8e24d8">llvm::AMDGPUAS::BUFFER_RESOURCE</a>, <a href="/web-llvm/docs/api/namespaces/llvm/amdgpuas/#a899ad5bfccfc22965a6714929a3dfae1aa6d3112da64eecbdbb50aacb5f8251e8">llvm::AMDGPUAS::CONSTANT_ADDRESS</a>, <a href="/web-llvm/docs/api/namespaces/llvm/amdgpuas/#a899ad5bfccfc22965a6714929a3dfae1a1caf1e287a5fe7250388d66ed72aa0c1">llvm::AMDGPUAS::CONSTANT_ADDRESS_32BIT</a>, <a href="/web-llvm/docs/api/namespaces/llvm/amdgpuas/#a899ad5bfccfc22965a6714929a3dfae1abf4559ef958a13c33f6ec7ed13fd44e5">llvm::AMDGPUAS::GLOBAL_ADDRESS</a>, <a href="/web-llvm/docs/api/namespaces/llvm/amdgpuas/#a899ad5bfccfc22965a6714929a3dfae1a77b1c964e2ff99057bf5e75140457abe">llvm::AMDGPUAS::LOCAL_ADDRESS</a> and <a href="/web-llvm/docs/api/namespaces/llvm/amdgpuas/#a899ad5bfccfc22965a6714929a3dfae1aec164f45437d8827346f2d8ec645479a">llvm::AMDGPUAS::PRIVATE_ADDRESS</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/classes/llvm/amdgpulegalizerinfo/#a44a4d4c034685aa34a4e8f62b0976e6c">llvm::AMDGPULegalizerInfo::AMDGPULegalizerInfo</a>, <a href="#a812ebabddd1ad2d8f8bbc6194346e2ed">isLoadStoreSizeLegal</a> and <a href="#a2d595a51e66614b8adb83efbc8114401">shouldWidenLoad</a>.</p>

</div>
</div>

### moreElementsToNextExistingRegClass() {#a4b2db808be70ea68e0f121c1942982a9}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">LegalizeMutation moreElementsToNextExistingRegClass (unsigned TypeIdx)</td>
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



<p>Definition at line 141 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/amdgpulegalizerinfo-cpp">AMDGPULegalizerInfo.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/silowercontrolflow-cpp/#a4868c5d81c5ccc98c47aeab6244346a0">assert</a>, <a href="/web-llvm/docs/api/classes/llvm/llt/#acd1eca3232b7b3072543294cd2377a37">llvm::LLT::fixed_vector</a>, <a href="/web-llvm/docs/api/classes/llvm/siregisterinfo/#a7d8aef424553a9b93de21ced693f0b09">llvm::SIRegisterInfo::getSGPRClassForBitWidth</a> and <a href="#aabec8e9bc89e3e905a71769f8be922c1">MaxRegisterSize</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/classes/llvm/amdgpulegalizerinfo/#a44a4d4c034685aa34a4e8f62b0976e6c">llvm::AMDGPULegalizerInfo::AMDGPULegalizerInfo</a>.</p>

</div>
</div>

### moreEltsToNext32Bit() {#ad64f039266036a2ac4d704000928d65b}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">LegalizeMutation moreEltsToNext32Bit (unsigned TypeIdx)</td>
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



<p>Definition at line 124 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/amdgpulegalizerinfo-cpp">AMDGPULegalizerInfo.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/silowercontrolflow-cpp/#a4868c5d81c5ccc98c47aeab6244346a0">assert</a>, <a href="/web-llvm/docs/api/classes/llvm/llt/#acd1eca3232b7b3072543294cd2377a37">llvm::LLT::fixed_vector</a>, <a href="/web-llvm/docs/api/classes/llvm/llt/#a956ffd0de93798f523683b447646dd92">llvm::LLT::getSizeInBits</a> and <a href="/web-llvm/docs/api/files/lib/lib/analysis/inlineorder-cpp/#a7ee6f0cb51c3b9056199e9a0001fe8c3a6f6cb72d544962fa333e2e34ce64f719">Size</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/classes/llvm/amdgpulegalizerinfo/#a44a4d4c034685aa34a4e8f62b0976e6c">llvm::AMDGPULegalizerInfo::AMDGPULegalizerInfo</a>.</p>

</div>
</div>

### needsDenormHandlingF32() {#a092571cd6865fc5f86e2a594265ff717}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool needsDenormHandlingF32 (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/machinefunction">MachineFunction</a> &amp; MF, <a href="/web-llvm/docs/api/classes/llvm/register">Register</a> Src, unsigned Flags)</td>
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



<p>Definition at line 3273 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/amdgpulegalizerinfo-cpp">AMDGPULegalizerInfo.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/classes/llvm/machinefunction/#a5f3f664c3c8fef0ffd2833ae21254117">llvm::MachineFunction::getDenormalMode</a>, <a href="/web-llvm/docs/api/classes/llvm/machinefunction/#a810234b6b3d223b7c74a4253fcc5ea5e">llvm::MachineFunction::getRegInfo</a>, <a href="/web-llvm/docs/api/structs/llvm/apfloatbase/#a0c5765e9acba977f6e462c2917276d8f">llvm::APFloatBase::IEEEsingle</a>, <a href="/web-llvm/docs/api/structs/llvm/denormalmode/#a1b79f1995991b0a757a4d04969c3717f">llvm::DenormalMode::Input</a>, <a href="/web-llvm/docs/api/structs/llvm/denormalmode/#a29b26e3ae30f3f6ec4106ff181282893a40bc80ae1d362a1461703637e946cbd8">llvm::DenormalMode::PreserveSign</a> and <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/amdgpuisellowering-cpp/#aab56a29f82c8c83fb88e5a2b01550f76">valueIsKnownNeverF32Denorm</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/classes/llvm/amdgpulegalizerinfo/#a6cccbc4ab2203366175f55aba0035679">llvm::AMDGPULegalizerInfo::getScaledLogInput</a>, <a href="/web-llvm/docs/api/classes/llvm/amdgpulegalizerinfo/#a3c2bbefdd60b95a56cf8eeab162ea2ae">llvm::AMDGPULegalizerInfo::legalizeFExp2</a>, <a href="/web-llvm/docs/api/classes/llvm/amdgpulegalizerinfo/#a79967954fb48056dab46d231e4aab954">llvm::AMDGPULegalizerInfo::legalizeFExpUnsafe</a> and <a href="/web-llvm/docs/api/classes/llvm/amdgpulegalizerinfo/#a20562025b5dd6e948bb3346d29417237">llvm::AMDGPULegalizerInfo::legalizeFSQRTF32</a>.</p>

</div>
</div>

### numElementsNotEven() {#a8e4a67e6620c2b437e4b7a7707ac0914}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">LegalityPredicate numElementsNotEven (unsigned TypeIdx)</td>
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



<p>Definition at line 219 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/amdgpulegalizerinfo-cpp">AMDGPULegalizerInfo.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/classes/llvm/llt/#a71181d67d0bf68c3b8a535ec20463f90">llvm::LLT::getNumElements</a> and <a href="/web-llvm/docs/api/classes/llvm/llt/#a7da5cc6e8aadd4d5fb6dd68f8ec12b7e">llvm::LLT::isVector</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/classes/llvm/amdgpulegalizerinfo/#a44a4d4c034685aa34a4e8f62b0976e6c">llvm::AMDGPULegalizerInfo::AMDGPULegalizerInfo</a>.</p>

</div>
</div>

### oneMoreElement() {#a0e3fd79bb281f248eefd08814023d8c8}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">LegalizeMutation oneMoreElement (unsigned TypeIdx)</td>
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



<p>Definition at line 101 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/amdgpulegalizerinfo-cpp">AMDGPULegalizerInfo.cpp</a>.</p>


<p>Reference <a href="/web-llvm/docs/api/classes/llvm/llt/#acd1eca3232b7b3072543294cd2377a37">llvm::LLT::fixed_vector</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/classes/llvm/amdgpulegalizerinfo/#a44a4d4c034685aa34a4e8f62b0976e6c">llvm::AMDGPULegalizerInfo::AMDGPULegalizerInfo</a>.</p>

</div>
</div>

### packImage16bitOpsToDwords() {#a0022aa73e6337684561159d1f7929966}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void packImage16bitOpsToDwords (<a href="/web-llvm/docs/api/classes/llvm/machineirbuilder">MachineIRBuilder</a> &amp; B, <a href="/web-llvm/docs/api/classes/llvm/machineinstr">MachineInstr</a> &amp; MI, <a href="/web-llvm/docs/api/classes/llvm/smallvectorimpl">SmallVectorImpl</a>&lt; <a href="/web-llvm/docs/api/classes/llvm/register">Register</a> &gt; &amp; PackedAddrs, unsigned ArgOffset, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/structs/llvm/amdgpu/imagedimintrinsicinfo">AMDGPU::ImageDimIntrinsicInfo</a> * Intr, bool IsA16, bool IsG16)</td>
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

<p>Turn a set of s16 typed registers in <span class="doxyComputerOutput">AddrRegs</span> into a dword sized vector with s16 typed elements.</p>

<p>Definition at line 6295 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/amdgpulegalizerinfo-cpp">AMDGPULegalizerInfo.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/silowercontrolflow-cpp/#a4868c5d81c5ccc98c47aeab6244346a0">assert</a>, <a href="/web-llvm/docs/api/files/lib/lib/ir/builtingcs-cpp/#ae76959fe811ba090de4cba69ac00f1da">B</a>, <a href="/web-llvm/docs/api/structs/llvm/amdgpu/imagedimintrinsicinfo/#a9c2123200d7aaa8788be3dc92100af4e">llvm::AMDGPU::ImageDimIntrinsicInfo::BiasIndex</a>, <a href="/web-llvm/docs/api/structs/llvm/amdgpu/imagedimintrinsicinfo/#ae03876722d50e94e3f7fea62d1a357f5">llvm::AMDGPU::ImageDimIntrinsicInfo::CoordStart</a>, <a href="/web-llvm/docs/api/classes/llvm/llt/#acd1eca3232b7b3072543294cd2377a37">llvm::LLT::fixed_vector</a>, <a href="/web-llvm/docs/api/classes/llvm/srcop/#ae229785d0c8a8ce25d34be18fe150a54">llvm::SrcOp::getReg</a>, <a href="/web-llvm/docs/api/structs/llvm/amdgpu/imagedimintrinsicinfo/#ac293c5b2a8dc63dc52c90978fd3f141b">llvm::AMDGPU::ImageDimIntrinsicInfo::GradientStart</a>, <a href="/web-llvm/docs/api/files/lib/lib/support/md5-cpp/#ac0eafdc9ee161b71e7af98af736952fd">I</a>, <a href="/web-llvm/docs/api/files/lib/lib/codegen/lib/codegen/globalisel/irtranslator-cpp/#abe44dfdea65b4f7e11e0a608ab708b76">MI</a>, <a href="/web-llvm/docs/api/structs/llvm/amdgpu/imagedimintrinsicinfo/#a91c53b6a1976c724071eafc0400873ff">llvm::AMDGPU::ImageDimIntrinsicInfo::NumBiasArgs</a>, <a href="/web-llvm/docs/api/structs/llvm/amdgpu/imagedimintrinsicinfo/#ad2823ce8b3af31f5775b2868e2773d77">llvm::AMDGPU::ImageDimIntrinsicInfo::NumGradients</a>, <a href="/web-llvm/docs/api/classes/llvm/smallvectortemplatebase/#af42bfbc067df27c19ee2fc859df58799">llvm::SmallVectorTemplateBase&lt; T, bool &gt;::push_back</a>, <a href="#acd57bd926bf1c8815e21e1291a54d151">S16</a>, <a href="/web-llvm/docs/api/classes/llvm/llt/#a67021459c7ef8f9a634b4eac7ffd0f96">llvm::LLT::scalar</a>, <a href="#a1a23ce3b10dc058d258a405a87e06a1a">V2S16</a>, <a href="/web-llvm/docs/api/structs/llvm/amdgpu/imagedimintrinsicinfo/#a30d38b0c21817d31cdda049b08e632e6">llvm::AMDGPU::ImageDimIntrinsicInfo::VAddrEnd</a> and <a href="/web-llvm/docs/api/structs/llvm/amdgpu/imagedimintrinsicinfo/#af38eeafc61d19839d3beafae2395776b">llvm::AMDGPU::ImageDimIntrinsicInfo::VAddrStart</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/classes/llvm/amdgpulegalizerinfo/#ad0be6e871a184d6f7b814515324eee1b">llvm::AMDGPULegalizerInfo::legalizeImageIntrinsic</a>.</p>

</div>
</div>

### replaceWithConstant() {#a79158bc80349e2c5ecd857cb098db65e}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool replaceWithConstant (<a href="/web-llvm/docs/api/classes/llvm/machineirbuilder">MachineIRBuilder</a> &amp; B, <a href="/web-llvm/docs/api/classes/llvm/machineinstr">MachineInstr</a> &amp; MI, int64_t C)</td>
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



<p>Definition at line 4382 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/amdgpulegalizerinfo-cpp">AMDGPULegalizerInfo.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/files/lib/lib/ir/builtingcs-cpp/#ae76959fe811ba090de4cba69ac00f1da">B</a>, <a href="/web-llvm/docs/api/namespaces/llvm/callingconv/#ac6aa1387c4375260e2468eb5a77fdb4cafd841a49aec1539bc88abc8ff9e170fb">llvm::CallingConv::C</a> and <a href="/web-llvm/docs/api/files/lib/lib/codegen/lib/codegen/globalisel/irtranslator-cpp/#abe44dfdea65b4f7e11e0a608ab708b76">MI</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/classes/anonymous-coroelide-cpp-/coroidelider/#ab170ffc9dea0395ef981c715778778a5">anonymous{CoroElide.cpp}::CoroIdElider::attemptElide</a> and <a href="/web-llvm/docs/api/classes/llvm/amdgpulegalizerinfo/#af7e4619611fab877c69f6ec0a1d57525">llvm::AMDGPULegalizerInfo::legalizeWorkitemIDIntrinsic</a>.</p>

</div>
</div>

### shouldBitcastLoadStoreType() {#a1c42298ffb49a95c87577d3e5de46aea}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool shouldBitcastLoadStoreType (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/gcnsubtarget">GCNSubtarget</a> &amp; ST, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/llt">LLT</a> Ty, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/llt">LLT</a> MemTy)</td>
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

<p>Return true if a load or store of the type should be lowered with a bitcast to a different type.</p>

<p>Definition at line 519 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/amdgpulegalizerinfo-cpp">AMDGPULegalizerInfo.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/classes/llvm/llt/#a956ffd0de93798f523683b447646dd92">llvm::LLT::getSizeInBits</a>, <a href="#a3986167503ccf79606f2249e660c9961">isRegisterSize</a>, <a href="#a2ea867ab6af309ac37d89c0ac9242600">isRegisterType</a>, <a href="#a31648fb7411d04ec274b46d8dd635564">isRegisterVectorElementType</a>, <a href="/web-llvm/docs/api/classes/llvm/llt/#a7da5cc6e8aadd4d5fb6dd68f8ec12b7e">llvm::LLT::isVector</a>, <a href="#ac6f0c363a0260f50a2e3dae5b8c00d21">loadStoreBitcastWorkaround</a> and <a href="/web-llvm/docs/api/files/lib/lib/analysis/inlineorder-cpp/#a7ee6f0cb51c3b9056199e9a0001fe8c3a6f6cb72d544962fa333e2e34ce64f719">Size</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/classes/llvm/amdgpulegalizerinfo/#a44a4d4c034685aa34a4e8f62b0976e6c">llvm::AMDGPULegalizerInfo::AMDGPULegalizerInfo</a>, <a href="/web-llvm/docs/api/classes/llvm/amdgpulegalizerinfo/#af3c20d55579ac56788b8134a4d3e724f">llvm::AMDGPULegalizerInfo::fixStoreSourceType</a>, <a href="/web-llvm/docs/api/classes/llvm/amdgpulegalizerinfo/#a89e5277b1b90b54ea21a51120f9a4206">llvm::AMDGPULegalizerInfo::legalizeBufferLoad</a> and <a href="/web-llvm/docs/api/classes/llvm/amdgpulegalizerinfo/#ae0d1532576a7c6e3bda2d8966700d27a">llvm::AMDGPULegalizerInfo::legalizeSBufferLoad</a>.</p>

</div>
</div>

### shouldWidenLoad() {#a2d595a51e66614b8adb83efbc8114401}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool shouldWidenLoad (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/gcnsubtarget">GCNSubtarget</a> &amp; ST, <a href="/web-llvm/docs/api/classes/llvm/llt">LLT</a> MemoryTy, uint64_t AlignInBits, unsigned AddrSpace, unsigned Opcode)</td>
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

<p>Return true if we should legalize a load by widening an odd sized memory access up to the alignment.</p>


<p>Note this case when the memory access itself changes, not the size of the result register.</p>


<p>Definition at line 538 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/amdgpulegalizerinfo-cpp">AMDGPULegalizerInfo.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/classes/llvm/sitargetlowering/#a21805127d5ae570ea5776ee098c951f1">llvm::SITargetLowering::allowsMisalignedMemoryAccessesImpl</a>, <a href="/web-llvm/docs/api/namespaces/llvm/callingconv/#ac6aa1387c4375260e2468eb5a77fdb4cabc8e2ee40a84687a9e12fd08784b87ba">llvm::CallingConv::Fast</a>, <a href="/web-llvm/docs/api/classes/llvm/llt/#a956ffd0de93798f523683b447646dd92">llvm::LLT::getSizeInBits</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a6dec2b5d3e04b47adf4d918d678e81c9">llvm::isPowerOf2_32</a>, <a href="#a807f9ab682878abe0a704736d1f9f298">maxSizeForAddrSpace</a>, <a href="/web-llvm/docs/api/classes/llvm/machinememoperand/#aaa2020e47e35179234b9ea27d555b2dda7d12be6206e5b0026c71bbcd5cb76494">llvm::MachineMemOperand::MOLoad</a> and <a href="/web-llvm/docs/api/namespaces/llvm/#afb65eef479f0473d0fe1666b80155237">llvm::NextPowerOf2</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/classes/llvm/amdgpulegalizerinfo/#a44a4d4c034685aa34a4e8f62b0976e6c">llvm::AMDGPULegalizerInfo::AMDGPULegalizerInfo</a>, <a href="/web-llvm/docs/api/classes/llvm/amdgpulegalizerinfo/#af13d2c38b3bf7586a8f07d511eda68e8">llvm::AMDGPULegalizerInfo::legalizeLoad</a> and <a href="#a9ae9993cc0e622c6d10e6e9a2aad0a05">shouldWidenLoad</a>.</p>

</div>
</div>

### shouldWidenLoad() {#a9ae9993cc0e622c6d10e6e9a2aad0a05}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool shouldWidenLoad (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/gcnsubtarget">GCNSubtarget</a> &amp; ST, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/structs/llvm/legalityquery">LegalityQuery</a> &amp; Query, unsigned Opcode)</td>
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



<p>Definition at line 572 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/amdgpulegalizerinfo-cpp">AMDGPULegalizerInfo.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/structs/llvm/legalityquery/#a9e26ab57991dfde2757e4790a626d6a3">llvm::LegalityQuery::MMODescrs</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a9bccbe67aaab722783ca4e7c504aaaa7a56a57d29a3f9dda8671b4d6490a94b08">llvm::NotAtomic</a>, <a href="#a2d595a51e66614b8adb83efbc8114401">shouldWidenLoad</a> and <a href="/web-llvm/docs/api/structs/llvm/legalityquery/#ab28fca6f8145be28b70ad89bb0c741b0">llvm::LegalityQuery::Types</a>.</p>

</div>
</div>

### sizeIsMultipleOf32() {#afa3cedfbe23049312e516145f0e46cbb}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">LegalityPredicate sizeIsMultipleOf32 (unsigned TypeIdx)</td>
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



<p>Definition at line 86 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/amdgpulegalizerinfo-cpp">AMDGPULegalizerInfo.cpp</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/classes/llvm/amdgpulegalizerinfo/#a44a4d4c034685aa34a4e8f62b0976e6c">llvm::AMDGPULegalizerInfo::AMDGPULegalizerInfo</a>.</p>

</div>
</div>

### stripAnySourceMods() {#a716801caf6a489a6af735be940932003}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">Register stripAnySourceMods (<a href="/web-llvm/docs/api/classes/llvm/register">Register</a> OrigSrc, <a href="/web-llvm/docs/api/classes/llvm/machineregisterinfo">MachineRegisterInfo</a> &amp; MRI)</td>
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



<p>Definition at line 3781 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/amdgpulegalizerinfo-cpp">AMDGPULegalizerInfo.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/namespaces/llvm/#a0edf31d256ecb3ac003bf2d81a576c9e">llvm::getOpcodeDef</a> and <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64advsimdscalarpass-cpp/#aacd2ab195054a3e6a74bfbb9d5d571c8">MRI</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/classes/llvm/amdgpulegalizerinfo/#a44186e632d4bab1d35012ed738a23870">llvm::AMDGPULegalizerInfo::legalizeFFloor</a>.</p>

</div>
</div>

### toggleSPDenormMode() {#abceca15aff80aa1ea3b5e7603981f878}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void toggleSPDenormMode (bool Enable, <a href="/web-llvm/docs/api/classes/llvm/machineirbuilder">MachineIRBuilder</a> &amp; B, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/gcnsubtarget">GCNSubtarget</a> &amp; ST, <a href="/web-llvm/docs/api/structs/llvm/simoderegisterdefaults">SIModeRegisterDefaults</a> Mode)</td>
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



<p>Definition at line 4955 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/amdgpulegalizerinfo-cpp">AMDGPULegalizerInfo.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/files/lib/lib/ir/builtingcs-cpp/#ae76959fe811ba090de4cba69ac00f1da">B</a>, <a href="/web-llvm/docs/api/files/lib/lib/codegen/lib/codegen/asmprinter/dwarfdebug-cpp/#aaf2a32c0f2738e57cac623b73b2c88aba80cb2080e90221d1f5b425387d9bd030">Enable</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/sidefines-h/#a794476833214d5191d905cb35da453a8">FP_DENORM_FLUSH_NONE</a>, <a href="/web-llvm/docs/api/files/lib/lib/codegen/regallocevictionadvisor-cpp/#aef71c4b21823f236e70cc6d62375adcd">Mode</a> and <a href="#a795662e773d2eda28caf873fa6eb70c4">SPDenormModeBitField</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/classes/llvm/amdgpulegalizerinfo/#a464ac3e6051fb78eb3ee985975d17cb2">llvm::AMDGPULegalizerInfo::legalizeFDIV32</a>.</p>

</div>
</div>

### valueIsKnownNeverF32Denorm() {#a344a4fa1e7c1a3a6f6ede4213058ad12}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool valueIsKnownNeverF32Denorm (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/machineregisterinfo">MachineRegisterInfo</a> &amp; MRI, <a href="/web-llvm/docs/api/classes/llvm/register">Register</a> Src)</td>
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

<p>Return true if it's known that <span class="doxyComputerOutput">Src</span> can never be an f32 denormal value.</p>

<p>Definition at line 3237 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/amdgpulegalizerinfo-cpp">AMDGPULegalizerInfo.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/namespaces/llvm/#ac4fc845f5ed92de63cd4474f128f5fc5">llvm::cast</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64expandpseudoinsts-cpp/#ad3ece0ac2421637044624c9b01c42466">DefMI</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64isellowering-cpp/#a62766c75f88612ffa652342472e755f6">getIntrinsicID</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64advsimdscalarpass-cpp/#aacd2ab195054a3e6a74bfbb9d5d571c8">MRI</a> and <a href="/web-llvm/docs/api/classes/llvm/llt/#a67021459c7ef8f9a634b4eac7ffd0f96">llvm::LLT::scalar</a>.</p>

</div>
</div>

### vectorSmallerThan() {#a144b2ed41ce4f22842225b0b1b117a58}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">LegalityPredicate vectorSmallerThan (unsigned TypeIdx, unsigned Size)</td>
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



<p>Definition at line 205 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/amdgpulegalizerinfo-cpp">AMDGPULegalizerInfo.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/classes/llvm/llt/#a956ffd0de93798f523683b447646dd92">llvm::LLT::getSizeInBits</a>, <a href="/web-llvm/docs/api/classes/llvm/llt/#a7da5cc6e8aadd4d5fb6dd68f8ec12b7e">llvm::LLT::isVector</a> and <a href="/web-llvm/docs/api/files/lib/lib/analysis/inlineorder-cpp/#a7ee6f0cb51c3b9056199e9a0001fe8c3a6f6cb72d544962fa333e2e34ce64f719">Size</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/classes/llvm/amdgpulegalizerinfo/#a44a4d4c034685aa34a4e8f62b0976e6c">llvm::AMDGPULegalizerInfo::AMDGPULegalizerInfo</a>.</p>

</div>
</div>

### vectorWiderThan() {#a2d0beabfcf00e6fd23c97eff8ee516a6}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">LegalityPredicate vectorWiderThan (unsigned TypeIdx, unsigned Size)</td>
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



<p>Definition at line 212 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/amdgpulegalizerinfo-cpp">AMDGPULegalizerInfo.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/classes/llvm/llt/#a956ffd0de93798f523683b447646dd92">llvm::LLT::getSizeInBits</a>, <a href="/web-llvm/docs/api/classes/llvm/llt/#a7da5cc6e8aadd4d5fb6dd68f8ec12b7e">llvm::LLT::isVector</a> and <a href="/web-llvm/docs/api/files/lib/lib/analysis/inlineorder-cpp/#a7ee6f0cb51c3b9056199e9a0001fe8c3a6f6cb72d544962fa333e2e34ce64f719">Size</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/classes/llvm/amdgpulegalizerinfo/#a44a4d4c034685aa34a4e8f62b0976e6c">llvm::AMDGPULegalizerInfo::AMDGPULegalizerInfo</a>.</p>

</div>
</div>

### verifyCFIntrinsic() {#a87e58e9d24983c7890c502fbe731f950}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">MachineInstr * verifyCFIntrinsic (<a href="/web-llvm/docs/api/classes/llvm/machineinstr">MachineInstr</a> &amp; MI, <a href="/web-llvm/docs/api/classes/llvm/machineregisterinfo">MachineRegisterInfo</a> &amp; MRI, <a href="/web-llvm/docs/api/classes/llvm/machineinstr">MachineInstr</a> *&amp; Br, <a href="/web-llvm/docs/api/classes/llvm/machinebasicblock">MachineBasicBlock</a> *&amp; UncondBrTarget, bool &amp; Negated)</td>
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



<p>Definition at line 4234 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/amdgpulegalizerinfo-cpp">AMDGPULegalizerInfo.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/classes/llvm/machinebasicblock/#acbc921830578e2741be6549db716c0ce">llvm::MachineBasicBlock::end</a>, <a href="/web-llvm/docs/api/classes/llvm/machinefunction/#a9d017af749f76484cb9aec9ff6e4330c">llvm::MachineFunction::end</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#abfbb7869d5e1d000bcca6867dd813178">llvm::eraseInstr</a>, <a href="/web-llvm/docs/api/classes/llvm/ilist-node-impl/#af719fc783be6589465137d997701a432">llvm::ilist_node_impl&lt; OptionsT &gt;::getIterator</a>, <a href="/web-llvm/docs/api/classes/llvm/machineoperand/#a57e64b633278df75c699e6b98ce15031">llvm::MachineOperand::getMBB</a>, <a href="/web-llvm/docs/api/classes/llvm/machineinstr/#ad67c9230577a0b640c52852c75c93939">llvm::MachineInstr::getOperand</a>, <a href="/web-llvm/docs/api/classes/llvm/machinebasicblock/#acf6442108e21e7e5379feb8962de65b7">llvm::MachineBasicBlock::getParent</a>, <a href="#accff22ec9fbd872b5976a4a2dc20ef56">isNot</a>, <a href="/web-llvm/docs/api/files/lib/lib/codegen/lib/codegen/globalisel/irtranslator-cpp/#abe44dfdea65b4f7e11e0a608ab708b76">MI</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64advsimdscalarpass-cpp/#aacd2ab195054a3e6a74bfbb9d5d571c8">MRI</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#ab13c360340346d082b959b8cd79f2c1a">llvm::Next</a> and <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64expandpseudoinsts-cpp/#a6cf2f8996b1e9aaf2d7a435aaa62382f">UseMI</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/classes/llvm/amdgpulegalizerinfo/#a5892da00df1f8fb432eab72498344583">llvm::AMDGPULegalizerInfo::legalizeIntrinsic</a>.</p>

</div>
</div>

### widenToNextPowerOf2() {#acbd3ab3957032feb181df036bb6a8d27}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">LLT widenToNextPowerOf2 (<a href="/web-llvm/docs/api/classes/llvm/llt">LLT</a> Ty)</td>
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



<p>Definition at line 3073 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/amdgpulegalizerinfo-cpp">AMDGPULegalizerInfo.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/classes/llvm/elementcount/#a584cb8dfa0090b33a969c4dda27337f6">llvm::ElementCount::getFixed</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a5542d44947f8d964b5ce3b20ea719b44">llvm::PowerOf2Ceil</a> and <a href="/web-llvm/docs/api/classes/llvm/llt/#a67021459c7ef8f9a634b4eac7ffd0f96">llvm::LLT::scalar</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/classes/llvm/amdgpulegalizerinfo/#af13d2c38b3bf7586a8f07d511eda68e8">llvm::AMDGPULegalizerInfo::legalizeLoad</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Variables

### AllS16Vectors {#a60fec3ee73a795e286972083bf85a68e}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">std::initializer_list&lt;LLT&gt; AllS16Vectors</td>
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
<div class="doxyVerbatim">{
    <a href="#a1a23ce3b10dc058d258a405a87e06a1a">V2S16</a>, <a href="#a52e4f67b333637f707e6fe59057c7348">V4S16</a>, <a href="#af54c894f1513d925a199547dec0ef2b2">V6S16</a>, <a href="#af904a5a62bedccf8107722036a8df0ce">V8S16</a>, <a href="#ace4e8d195c9498b419467f234000a72e">V10S16</a>, <a href="#a7a3fa97d0457d84638593bf3da5e21f6">V12S16</a>, <a href="#a09d7d8b975bcef9c12bd114d3b593b00">V16S16</a>, <a href="#ad61c521a33598d8ca5b07dd4e0f03087">V2S128</a>, <a href="#a9e404048aa9a1687a9ec6f9d9420bf39">V4S128</a>}
</div>
</dd>
</dl>

<p>Definition at line 340 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/amdgpulegalizerinfo-cpp">AMDGPULegalizerInfo.cpp</a>.</p>


<p>Referenced by <a href="#a8ac13bffc4ec5811abc67aaa4166e9a8">isRegisterClassType</a>.</p>

</div>
</div>

### AllS32Vectors {#a4b69b2b66bc8186c8b21b62fe41d444d}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">std::initializer_list&lt;LLT&gt; AllS32Vectors</td>
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
    <a href="#a0b000f228cb40bf4aee0a19815ce4d99">V2S32</a>, <a href="#a257279ea49c58180217364b89917c6c3">V3S32</a>,  <a href="#a0af4f63c268470ef2eac6477d33fdce4">V4S32</a>,  <a href="#a4d742b8db1d6a22581da42b9b758e2be">V5S32</a>,  <a href="#a495ae51584ec946579f24bda39b4fa84">V6S32</a>,  <a href="#a4c29a6c597e1cb2db05e41d65f76d338">V7S32</a>, <a href="#a1348f6cfe026c7a1dca9a61c8713ab07">V8S32</a>,
    <a href="#a7261ab9abe3b6583e7e094677e84b50d">V9S32</a>, <a href="#a73e961aa3509555c9944d502a52d1303">V10S32</a>, <a href="#a53954ac3898aff9426fc131d14a84f11">V11S32</a>, <a href="#a11d102c56b1f897e6886c283d8f16ce4">V12S32</a>, <a href="#a83756b36d1fca7fb0054ab52622cda67">V16S32</a>, <a href="#a61cf1ca010a7d653f1cf0ddefa7a8e6d">V32S32</a>}
</div>
</dd>
</dl>

<p>Definition at line 343 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/amdgpulegalizerinfo-cpp">AMDGPULegalizerInfo.cpp</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/classes/llvm/amdgpulegalizerinfo/#a44a4d4c034685aa34a4e8f62b0976e6c">llvm::AMDGPULegalizerInfo::AMDGPULegalizerInfo</a> and <a href="#a8ac13bffc4ec5811abc67aaa4166e9a8">isRegisterClassType</a>.</p>

</div>
</div>

### AllS64Vectors {#abf8037dd8ffb10bb4c5fe61c6d0c5c6c}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">std::initializer_list&lt;LLT&gt; AllS64Vectors</td>
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
<div class="doxyVerbatim">= {<a href="#acb4ecd614e176840d5b2360a176f1333">V2S64</a>, <a href="#a0900073ce203e689dc42c702ba6a5c98">V3S64</a>, <a href="#a214d79cea6eb493a2f95b0170886311a">V4S64</a>, <a href="#a8c4f0c5559c18078956303fa71b2a027">V5S64</a>,
                                                   <a href="#aa95cd588b298b4861271199e3afe971f">V6S64</a>, <a href="#a839fd594af5fb0c910f8c3fa13e154a9">V7S64</a>, <a href="#a0c9c5c4bf19122ed92afa6fe3e70b158">V8S64</a>, <a href="#a7af378812d0f59470e1ad5ff1ac40679">V16S64</a>}
</div>
</dd>
</dl>

<p>Definition at line 347 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/amdgpulegalizerinfo-cpp">AMDGPULegalizerInfo.cpp</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/classes/llvm/amdgpulegalizerinfo/#a44a4d4c034685aa34a4e8f62b0976e6c">llvm::AMDGPULegalizerInfo::AMDGPULegalizerInfo</a> and <a href="#a8ac13bffc4ec5811abc67aaa4166e9a8">isRegisterClassType</a>.</p>

</div>
</div>

### AllScalarTypes {#ada70cb9213ffddaebab099c55f886d19}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">std::initializer_list&lt;LLT&gt; AllScalarTypes</td>
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
    <a href="#a33c95d7d51d4b0b421aaf3d40796b859">S32</a>, <a href="#a2b96ee4926f7c19420d19ecaf7adc1a8">S64</a>, <a href="#ac721ed1f1b2048a37c89fa31e662cd3a">S96</a>, <a href="#a0a82f21bb2863eb65c5f28fb9d34a954">S128</a>, <a href="#a8d3731c41acd28da69f691b8ce22edd4">S160</a>, <a href="#a7654aba611cb44b8c9d4a43398099bf6">S192</a>, <a href="#af775f87ae257bdc6f0b5e5eac41ad51a">S224</a>, <a href="#ae61a7658a9585eba0ff27a47e0c8aea1">S256</a>, <a href="#a7fcbdd8fbd887c5c2c68588ab6179c64">S512</a>, <a href="#a482bcb2c405924538af22abc4c9e85fc">S1024</a>}
</div>
</dd>
</dl>

<p>Definition at line 337 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/amdgpulegalizerinfo-cpp">AMDGPULegalizerInfo.cpp</a>.</p>


<p>Referenced by <a href="#a8ac13bffc4ec5811abc67aaa4166e9a8">isRegisterClassType</a>.</p>

</div>
</div>

### EnableNewLegality {#a051bcca9a10dfdb5c382173aa0d5a860}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">cl::opt&lt; bool &gt; EnableNewLegality("amdgpu-global-isel-new-legality", cl::desc("Use GlobalISel desired legality, rather than try to use" "rules compatible with selection patterns"), cl::init(false), cl::ReallyHidden)</td>
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



<p>Definition at line 46 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/amdgpulegalizerinfo-cpp">AMDGPULegalizerInfo.cpp</a>.</p>


<p>Referenced by <a href="#ac6f0c363a0260f50a2e3dae5b8c00d21">loadStoreBitcastWorkaround</a>.</p>

</div>
</div>

### F32 {#affe0a8af32c1d4e53b07959b240641b4}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">const LLT F32 = LLT::float32()</td>
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



<p>Definition at line 286 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/amdgpulegalizerinfo-cpp">AMDGPULegalizerInfo.cpp</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/classes/llvm/amdgpulegalizerinfo/#a44a4d4c034685aa34a4e8f62b0976e6c">llvm::AMDGPULegalizerInfo::AMDGPULegalizerInfo</a>, <a href="/web-llvm/docs/api/structs/llvm/yaml/scalarenumerationtraits-1c3bd737691f36eaba9501ef794ab207/#a7c4b27f07e30d8d62344fc85ab9bb714">llvm::yaml::ScalarEnumerationTraits&lt; WasmYAML::ValueType &gt;::enumeration</a>, <a href="/web-llvm/docs/api/classes/llvm/amdgpulegalizerinfo/#a6cccbc4ab2203366175f55aba0035679">llvm::AMDGPULegalizerInfo::getScaledLogInput</a>, <a href="/web-llvm/docs/api/classes/llvm/amdgpulegalizerinfo/#a5552c2fa1505412508e493149af31543">llvm::AMDGPULegalizerInfo::legalizeFExp</a>, <a href="/web-llvm/docs/api/classes/llvm/amdgpulegalizerinfo/#a3c2bbefdd60b95a56cf8eeab162ea2ae">llvm::AMDGPULegalizerInfo::legalizeFExp2</a>, <a href="/web-llvm/docs/api/classes/llvm/amdgpulegalizerinfo/#a79967954fb48056dab46d231e4aab954">llvm::AMDGPULegalizerInfo::legalizeFExpUnsafe</a>, <a href="/web-llvm/docs/api/classes/llvm/amdgpulegalizerinfo/#afb13811bb447af9b35a1ae4257e37a36">llvm::AMDGPULegalizerInfo::legalizeFlog2</a>, <a href="/web-llvm/docs/api/classes/llvm/amdgpulegalizerinfo/#a39adc1637ddc1df880ec4ab13529879e">llvm::AMDGPULegalizerInfo::legalizeFlogCommon</a>, <a href="/web-llvm/docs/api/classes/llvm/amdgpulegalizerinfo/#abf712aff736a372430ea6ea027fe32e5">llvm::AMDGPULegalizerInfo::legalizeFPow</a>, <a href="/web-llvm/docs/api/classes/llvm/amdgpulegalizerinfo/#a07957999af426a9136774abb7a037286">llvm::AMDGPULegalizerInfo::legalizeFSQRTF16</a>, <a href="/web-llvm/docs/api/classes/llvm/amdgpulegalizerinfo/#a20562025b5dd6e948bb3346d29417237">llvm::AMDGPULegalizerInfo::legalizeFSQRTF32</a> and <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/nvptx/nvptxiseldagtodag-cpp/#a5f3c1ae4858b86cca14c693cb98af79b">pickOpcodeForVectorStParam</a>.</p>

</div>
</div>

### F64 {#a563bbae35885ba289017e47ec57235fa}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">const LLT F64 = LLT::float64()</td>
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



<p>Definition at line 288 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/amdgpulegalizerinfo-cpp">AMDGPULegalizerInfo.cpp</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/classes/llvm/amdgpulegalizerinfo/#a44a4d4c034685aa34a4e8f62b0976e6c">llvm::AMDGPULegalizerInfo::AMDGPULegalizerInfo</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/x86/x86isellowering-cpp/#a1bca5f0c0254fc2b2707fe8b6e5677d3">combineBitcast</a>, <a href="/web-llvm/docs/api/structs/llvm/yaml/scalarenumerationtraits-1c3bd737691f36eaba9501ef794ab207/#a7c4b27f07e30d8d62344fc85ab9bb714">llvm::yaml::ScalarEnumerationTraits&lt; WasmYAML::ValueType &gt;::enumeration</a>, <a href="/web-llvm/docs/api/classes/llvm/amdgpulegalizerinfo/#a44186e632d4bab1d35012ed738a23870">llvm::AMDGPULegalizerInfo::legalizeFFloor</a>, <a href="/web-llvm/docs/api/classes/llvm/amdgpulegalizerinfo/#ae6424442b4dd0280dd56bc1c577e68ed">llvm::AMDGPULegalizerInfo::legalizeFSQRTF64</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/arm/armisellowering-cpp/#a00afc372e6cccfa7fd2904fde074a757">PerformExtractEltToVMOVRRD</a> and <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/nvptx/nvptxiseldagtodag-cpp/#a5f3c1ae4858b86cca14c693cb98af79b">pickOpcodeForVectorStParam</a>.</p>

</div>
</div>

### FPEnvModeBitField {#a1fff431f58bc2af2caae5f611ba0791f}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">unsigned FPEnvModeBitField</td>
</tr>
</table>
</td>
<td class="doxyMemberLabelsRight">
<span class="doxyMemberLabels">
<span class="doxyMemberLabel constexpr">constexpr</span>
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
<div class="doxyVerbatim">=
    AMDGPU::Hwreg::HwregEncoding::encode(AMDGPU::Hwreg::ID_MODE, 0, 23)
</div>
</dd>
</dl>

<p>Definition at line 7198 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/amdgpulegalizerinfo-cpp">AMDGPULegalizerInfo.cpp</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/classes/llvm/amdgpulegalizerinfo/#ad6a43ba94ff9ee58996abe2df50464a3">llvm::AMDGPULegalizerInfo::legalizeGetFPEnv</a> and <a href="/web-llvm/docs/api/classes/llvm/amdgpulegalizerinfo/#af6341dd9dcba1872086b57731b9c096d">llvm::AMDGPULegalizerInfo::legalizeSetFPEnv</a>.</p>

</div>
</div>

### FPEnvTrapBitField {#aa0516ba249c5d556a3ee34bfd27737f3}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">unsigned FPEnvTrapBitField</td>
</tr>
</table>
</td>
<td class="doxyMemberLabelsRight">
<span class="doxyMemberLabels">
<span class="doxyMemberLabel constexpr">constexpr</span>
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
<div class="doxyVerbatim">=
    AMDGPU::Hwreg::HwregEncoding::encode(AMDGPU::Hwreg::ID_TRAPSTS, 0, 5)
</div>
</dd>
</dl>

<p>Definition at line 7201 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/amdgpulegalizerinfo-cpp">AMDGPULegalizerInfo.cpp</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/classes/llvm/amdgpulegalizerinfo/#ad6a43ba94ff9ee58996abe2df50464a3">llvm::AMDGPULegalizerInfo::legalizeGetFPEnv</a> and <a href="/web-llvm/docs/api/classes/llvm/amdgpulegalizerinfo/#af6341dd9dcba1872086b57731b9c096d">llvm::AMDGPULegalizerInfo::legalizeSetFPEnv</a>.</p>

</div>
</div>

### MaxRegisterSize {#aabec8e9bc89e3e905a71769f8be922c1}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">unsigned MaxRegisterSize = 1024</td>
</tr>
</table>
</td>
<td class="doxyMemberLabelsRight">
<span class="doxyMemberLabels">
<span class="doxyMemberLabel constexpr">constexpr</span>
<span class="doxyMemberLabel static">static</span>
</span>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 53 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/amdgpulegalizerinfo-cpp">AMDGPULegalizerInfo.cpp</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/classes/llvm/amdgpulegalizerinfo/#a44a4d4c034685aa34a4e8f62b0976e6c">llvm::AMDGPULegalizerInfo::AMDGPULegalizerInfo</a>, <a href="#a3986167503ccf79606f2249e660c9961">isRegisterSize</a> and <a href="#a4b2db808be70ea68e0f121c1942982a9">moreElementsToNextExistingRegClass</a>.</p>

</div>
</div>

### MaxScalar {#abb0782aaccc0907cc36fe566a642c71b}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">const LLT MaxScalar = LLT::scalar(<a href="#aabec8e9bc89e3e905a71769f8be922c1">MaxRegisterSize</a>)</td>
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



<p>Definition at line 297 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/amdgpulegalizerinfo-cpp">AMDGPULegalizerInfo.cpp</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/classes/llvm/amdgpulegalizerinfo/#a44a4d4c034685aa34a4e8f62b0976e6c">llvm::AMDGPULegalizerInfo::AMDGPULegalizerInfo</a>.</p>

</div>
</div>

### S1 {#a22eabd3566ae5f32cb6f594f4f343399}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">const LLT S1 = LLT::scalar(1)</td>
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



<p>Definition at line 282 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/amdgpulegalizerinfo-cpp">AMDGPULegalizerInfo.cpp</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/classes/llvm/amdgpulegalizerinfo/#a44a4d4c034685aa34a4e8f62b0976e6c">llvm::AMDGPULegalizerInfo::AMDGPULegalizerInfo</a>, <a href="/web-llvm/docs/api/structs/anonymous-settheory-cpp-/andop/#a2a95bd4196657729f481b17b7c457d6d">anonymous{SetTheory.cpp}::AndOp::apply</a>, <a href="/web-llvm/docs/api/structs/llvm/hexagonsubtarget/bankconflictmutation/#a336138bbbfacbbb4be8c56d41f08b0c2">llvm::HexagonSubtarget::BankConflictMutation::apply</a>, <a href="/web-llvm/docs/api/classes/llvm/amdgpuregisterbankinfo/#a59ce3aa458b07483cb7422b0303b589b">llvm::AMDGPURegisterBankInfo::applyMappingMAD_64_32</a>, <a href="/web-llvm/docs/api/classes/llvm/binaryoperator/#acee1035fe1c77f85d4b80655e4df150a">llvm::BinaryOperator::BinaryOperator</a>, <a href="/web-llvm/docs/api/classes/llvm/amdgpulegalizerinfo/#a01959fee9db67c3a625348ae39489c5e">llvm::AMDGPULegalizerInfo::buildMultiply</a>, <a href="/web-llvm/docs/api/classes/llvm/stringswitch/#ae160b30f330ff80aca770eccbd622bb0">llvm::StringSwitch&lt; T, R &gt;::Cases</a>, <a href="/web-llvm/docs/api/classes/llvm/stringswitch/#a931ede9419864a545b6b679c025b5bb1">llvm::StringSwitch&lt; T, R &gt;::Cases</a>, <a href="/web-llvm/docs/api/classes/llvm/stringswitch/#aa8aef18351d47bdceacdb1da1f7af2c7">llvm::StringSwitch&lt; T, R &gt;::Cases</a>, <a href="/web-llvm/docs/api/classes/llvm/stringswitch/#abb7b572d55d25ad0b700231ff2399d98">llvm::StringSwitch&lt; T, R &gt;::Cases</a>, <a href="/web-llvm/docs/api/classes/llvm/stringswitch/#a1dd17df30c3b52d1e0f5317faaef4e4e">llvm::StringSwitch&lt; T, R &gt;::Cases</a>, <a href="/web-llvm/docs/api/classes/llvm/stringswitch/#a491cb4cc33dcafc0c4ef8d15ed04c7f1">llvm::StringSwitch&lt; T, R &gt;::Cases</a>, <a href="/web-llvm/docs/api/classes/llvm/stringswitch/#aa3f39f2122c9d75055c8b37401e375cf">llvm::StringSwitch&lt; T, R &gt;::Cases</a>, <a href="/web-llvm/docs/api/classes/llvm/stringswitch/#abdc24b10120247d56ec645cb6191fc9a">llvm::StringSwitch&lt; T, R &gt;::Cases</a>, <a href="/web-llvm/docs/api/classes/llvm/stringswitch/#aa13f802513b39e1e2a7650011e5651d7">llvm::StringSwitch&lt; T, R &gt;::Cases</a>, <a href="/web-llvm/docs/api/classes/llvm/stringswitch/#a1a88c815228a7c3609d4ef20daaf8554">llvm::StringSwitch&lt; T, R &gt;::CasesLower</a>, <a href="/web-llvm/docs/api/classes/llvm/stringswitch/#a58074239a30b92c33aeba30b27edb376">llvm::StringSwitch&lt; T, R &gt;::CasesLower</a>, <a href="/web-llvm/docs/api/classes/llvm/stringswitch/#aefa06ebc7b4fbf480129276bb50d6811">llvm::StringSwitch&lt; T, R &gt;::CasesLower</a>, <a href="/web-llvm/docs/api/classes/llvm/stringswitch/#a4544df2c19074824906281761017ddfc">llvm::StringSwitch&lt; T, R &gt;::CasesLower</a>, <a href="/web-llvm/docs/api/namespaces/anonymous-constantfolding-cpp-/#aeae4a07f0fe95525d21343b3139276bd">anonymous{ConstantFolding.cpp}::ConstantFoldAMDGCNCubeIntrinsic</a>, <a href="/web-llvm/docs/api/classes/llvm/binaryoperator/#a8f385eda0f71b4e8199b296fbc8e0da9">llvm::BinaryOperator::Create</a>, <a href="/web-llvm/docs/api/classes/llvm/cmpinst/#a62e2cf3675b93f0e6c07a4a00852f7cd">llvm::CmpInst::Create</a>, <a href="/web-llvm/docs/api/classes/llvm/selectinst/#a09d8760fa31a7b8739acf71a4d2ac9d9">llvm::SelectInst::Create</a>, <a href="/web-llvm/docs/api/classes/llvm/sandboxir/cmpinst/#a80a29c6e8a935d440a3dc301f3a95dec">llvm::sandboxir::CmpInst::create</a>, <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/scalar/reassociate-cpp/#a4b946333b7fb96fec126f22534cf3794">CreateAdd</a>, <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/scalar/reassociate-cpp/#a3621b702ef72b987959cdd7242c13d47">CreateMul</a>, <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/scalar/reassociate-cpp/#abaecf6dabc1e9495c8ba0c899ba1565c">CreateNeg</a>, <a href="/web-llvm/docs/api/classes/llvm/cmpinst/#a6d0ee639690d0fa59e6c9e0af5adc5c2">llvm::CmpInst::CreateWithCopiedFlags</a>, <a href="/web-llvm/docs/api/classes/llvm/sandboxir/cmpinst/#a781d2ab0a52d398b5f6c1a76d8c979ae">llvm::sandboxir::CmpInst::createWithCopiedFlags</a>, <a href="/web-llvm/docs/api/classes/llvm/binaryoperator/#a527bd9ac4fece095b5979a7d30ed93af">llvm::BinaryOperator::DECLARE_TRANSPARENT_OPERAND_ACCESSORS</a>, <a href="/web-llvm/docs/api/classes/llvm/pmdatamanager/#aff93635e4ea28861beb90faece603b3d">llvm::PMDataManager::dumpPassInfo</a>, <a href="/web-llvm/docs/api/classes/llvm/amdgpuregisterbankinfo/#a533cd1035e03cdca3da433e98e77e430">llvm::AMDGPURegisterBankInfo::executeInWaterfallLoop</a>, <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/instcombine/instcombinevectorops-cpp/#aabcb01976dc50b78faed7491a6d43042">foldShuffleOfUnaryOps</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a8ee09fbd48d9a5effc6b0e98a00dc012">llvm::get_stable_name</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/amdgpuregbanklegalize-cpp/#a7d4da10beff712762d6e9ebbf51b339a">getAnySgprS1</a>, <a href="/web-llvm/docs/api/classes/anonymous-amdgpuglobaliseldivergencelowering-cpp-/divergenceloweringhelper/#ae8882b2a7fc8ce50e0ae8a34ffd802c1">anonymous{AMDGPUGlobalISelDivergenceLowering.cpp}::DivergenceLoweringHelper::getCandidatesForLowering</a>, <a href="/web-llvm/docs/api/classes/llvm/dilocation/#a78cc51c415c7e64b5efe2c8458fbd35a">llvm::DILocation::getMergedLocation</a>, <a href="/web-llvm/docs/api/files/lib/lib/debuginfo/lib/debuginfo/pdb/lib/debuginfo/pdb/native/gsistreambuilder-cpp/#ad8de58e5ee26f7e8a2a509355b0156f4">gsiRecordCmp</a>, <a href="/web-llvm/docs/api/structs/anonymous-memorysanitizer-cpp-/memorysanitizervisitor/#aa28fe1a3de7cc0e732f5d7ee1dc5adbd">anonymous{MemorySanitizer.cpp}::MemorySanitizerVisitor::handleDppIntrinsic</a>, <a href="/web-llvm/docs/api/structs/anonymous-memorysanitizer-cpp-/memorysanitizervisitor/#a04fa6c52e825a7d994a3a5eeb1cc4549">anonymous{MemorySanitizer.cpp}::MemorySanitizerVisitor::handleFunnelShift</a>, <a href="/web-llvm/docs/api/structs/anonymous-memorysanitizer-cpp-/memorysanitizervisitor/#ac689bdce81e76d215f170f7eb3821be3">anonymous{MemorySanitizer.cpp}::MemorySanitizerVisitor::handleRelationalComparisonExact</a>, <a href="/web-llvm/docs/api/structs/anonymous-memorysanitizer-cpp-/memorysanitizervisitor/#a220983874e8efc856fac602c19e9aa2b">anonymous{MemorySanitizer.cpp}::MemorySanitizerVisitor::handleShift</a>, <a href="/web-llvm/docs/api/structs/anonymous-memorysanitizer-cpp-/memorysanitizervisitor/#acaaee38930abb5a8c5d6ff71045eda30">anonymous{MemorySanitizer.cpp}::MemorySanitizerVisitor::handleVectorPackIntrinsic</a>, <a href="/web-llvm/docs/api/structs/anonymous-memorysanitizer-cpp-/memorysanitizervisitor/#af1c328e6af190112474f8c694ccb59dc">anonymous{MemorySanitizer.cpp}::MemorySanitizerVisitor::handleVectorShiftIntrinsic</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/hexagon/hexagonpeephole-cpp/#a75858997548ce7f9cc07ce26843356c6">INITIALIZE_PASS</a>, <a href="/web-llvm/docs/api/namespaces/anonymous-sampleprofileinference-cpp-/#a46dd2e73fdb4a5c9bf2af4a8fa968bd1">anonymous{SampleProfileInference.cpp}::initializeNetwork</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a0f0d66fa63bebb53ddd51f1cc4def0f8">llvm::isEqual</a>, <a href="/web-llvm/docs/api/classes/llvm/mipsccstate/#a3f63290aff1f6b522c80c818a9d025ab">llvm::MipsCCState::isF128SoftLibCall</a>, <a href="/web-llvm/docs/api/classes/llvm/mipsmcexpr/#ad68220d5cd03f3e38fd0949937c7e6ac">llvm::MipsMCExpr::isGpOff</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/hexagon/hexagoniseldagtodag-cpp/#abd648b9bbf53e1b89e8e7e2695034268">isMemOPCandidate</a>, <a href="/web-llvm/docs/api/classes/llvm/amdgpulegalizerinfo/#ae468aab9eee24365f029a78836e6435d">llvm::AMDGPULegalizerInfo::legalizeFceil</a>, <a href="/web-llvm/docs/api/classes/llvm/amdgpulegalizerinfo/#a464ac3e6051fb78eb3ee985975d17cb2">llvm::AMDGPULegalizerInfo::legalizeFDIV32</a>, <a href="/web-llvm/docs/api/classes/llvm/amdgpulegalizerinfo/#a30fc420ff83b1e2c4ab42e86d9071e34">llvm::AMDGPULegalizerInfo::legalizeFDIV64</a>, <a href="/web-llvm/docs/api/classes/llvm/amdgpulegalizerinfo/#a6f737d47e92bb08927c272b12fba32d8">llvm::AMDGPULegalizerInfo::legalizeFDIVFastIntrin</a>, <a href="/web-llvm/docs/api/classes/llvm/amdgpulegalizerinfo/#a44186e632d4bab1d35012ed738a23870">llvm::AMDGPULegalizerInfo::legalizeFFloor</a>, <a href="/web-llvm/docs/api/classes/llvm/amdgpulegalizerinfo/#a20562025b5dd6e948bb3346d29417237">llvm::AMDGPULegalizerInfo::legalizeFSQRTF32</a>, <a href="/web-llvm/docs/api/classes/llvm/amdgpulegalizerinfo/#ae6424442b4dd0280dd56bc1c577e68ed">llvm::AMDGPULegalizerInfo::legalizeFSQRTF64</a>, <a href="/web-llvm/docs/api/classes/llvm/amdgpulegalizerinfo/#a0e7378d479179ae1df0b61b83c637a4d">llvm::AMDGPULegalizerInfo::legalizeIntrinsicTrunc</a>, <a href="/web-llvm/docs/api/classes/llvm/amdgpulegalizerinfo/#a3db547888c8d2ed5323f320bb5763014">llvm::AMDGPULegalizerInfo::legalizeUnsignedDIV_REM32Impl</a>, <a href="/web-llvm/docs/api/classes/llvm/amdgpulegalizerinfo/#a93bbde2af63d129f752ef7c3a0f84c15">llvm::AMDGPULegalizerInfo::legalizeUnsignedDIV_REM64Impl</a>, <a href="/web-llvm/docs/api/structs/anonymous-memorysanitizer-cpp-/memorysanitizervisitor/#a174a52b2885896fbf86e1250573168dc">anonymous{MemorySanitizer.cpp}::MemorySanitizerVisitor::LowerElementShadowExtend</a>, <a href="/web-llvm/docs/api/classes/llvm/legalizerhelper/#ab99f92278021f1921be23b762056a9cc">llvm::LegalizerHelper::lowerFPTOSI</a>, <a href="/web-llvm/docs/api/classes/llvm/legalizerhelper/#a64f47636eb4667460ea08f358d6d39da">llvm::LegalizerHelper::lowerFPTOUI</a>, <a href="/web-llvm/docs/api/classes/llvm/legalizerhelper/#a04ee040b3b0253a0832ddb7915d55ae1">llvm::LegalizerHelper::lowerFPTRUNC_F64_TO_F16</a>, <a href="/web-llvm/docs/api/classes/llvm/legalizerhelper/#a0a4f859f973b7f797f2d510c369980ad">llvm::LegalizerHelper::lowerSITOFP</a>, <a href="/web-llvm/docs/api/classes/llvm/legalizerhelper/#a9b5ad9f5de612dc98a4f3232a98ab754">llvm::LegalizerHelper::lowerU64ToF32BitOps</a>, <a href="/web-llvm/docs/api/classes/llvm/legalizerhelper/#ac9599381b406afe38a263b028248e407">llvm::LegalizerHelper::lowerU64ToF32WithSITOFP</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/x86/x86isellowering-cpp/#a0a69bfc728391a45832d24dca6c93abc">matchBinaryPermuteShuffle</a>, <a href="/web-llvm/docs/api/classes/llvm/combinerhelper/#a0255cbf70d03b31784d719fb73637002">llvm::CombinerHelper::matchCommuteShift</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/amdgpuregbanklegalizerules-cpp/#ac2bfcc1d9b7f5effd45c65a5f973df13">matchUniformityAndLLT</a>, <a href="/web-llvm/docs/api/classes/llvm/armtargetlowering/#a35a55a457bfc044d33bdeb4811532531">llvm::ARMTargetLowering::PerformMVETruncCombine</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64isellowering-cpp/#a31cdc023846d0798543e1fd10937005a">performVectorExtCombine</a>, <a href="/web-llvm/docs/api/classes/llvm/ppclegalizerinfo/#ae83d1a82dbe98543ff9238ae236b5e20">llvm::PPCLegalizerInfo::PPCLegalizerInfo</a>, <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/scalar/instsimplifypass-cpp/#a49359723de1a046072e8cc931068d43f">runImpl</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#ab471ffb4e400f1f924442e9149ce1b87">llvm::set_difference</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a2162d123f222998300d308bdefdb38b9">llvm::set_intersect</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a930620843c7a80fee7260fe93f61773f">llvm::set_intersection</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#afd9ccce4f25a3c4b7e29f0d3f8caac70">llvm::set_intersection_impl</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a38740a7e3fde66312240ec2cbf003fc2">llvm::set_is_subset</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a3e1137200d6e86367be1d605fdc14e6c">llvm::set_subtract</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a2c94f8511b1e1d4645596a8a786ead94">llvm::set_subtract</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a8b4f88b1fadc8f51a643e5faaa13afa6">llvm::set_union</a>, <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/scalar/loopinstsimplify-cpp/#ac7156f23f48b5eb96ead0522896d7574">simplifyLoopInst</a>, <a href="/web-llvm/docs/api/classes/llvm/giselcseinfo/#ad59eed9a40a4f5cca48396538dcb9b13">llvm::GISelCSEInfo::verify</a>, <a href="/web-llvm/docs/api/structs/anonymous-memorysanitizer-cpp-/memorysanitizervisitor/#af4ed8c796cc564c14664505603f6aac1">anonymous{MemorySanitizer.cpp}::MemorySanitizerVisitor::visitAnd</a> and <a href="/web-llvm/docs/api/structs/anonymous-memorysanitizer-cpp-/memorysanitizervisitor/#a684df7f760d6dcbfea36c5bccb2cfccd">anonymous{MemorySanitizer.cpp}::MemorySanitizerVisitor::visitOr</a>.</p>

</div>
</div>

### S1024 {#a482bcb2c405924538af22abc4c9e85fc}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">const LLT S1024 = LLT::scalar(1024)</td>
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



<p>Definition at line 296 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/amdgpulegalizerinfo-cpp">AMDGPULegalizerInfo.cpp</a>.</p>

</div>
</div>

### S128 {#a0a82f21bb2863eb65c5f28fb9d34a954}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">const LLT S128 = LLT::scalar(128)</td>
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



<p>Definition at line 290 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/amdgpulegalizerinfo-cpp">AMDGPULegalizerInfo.cpp</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/classes/llvm/amdgpulegalizerinfo/#a44a4d4c034685aa34a4e8f62b0976e6c">llvm::AMDGPULegalizerInfo::AMDGPULegalizerInfo</a>.</p>

</div>
</div>

### S16 {#acd57bd926bf1c8815e21e1291a54d151}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">const LLT S16 = LLT::scalar(16)</td>
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



<p>Definition at line 284 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/amdgpulegalizerinfo-cpp">AMDGPULegalizerInfo.cpp</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/classes/llvm/amdgpulegalizerinfo/#a44a4d4c034685aa34a4e8f62b0976e6c">llvm::AMDGPULegalizerInfo::AMDGPULegalizerInfo</a>, <a href="/web-llvm/docs/api/classes/llvm/amdgpulegalizerinfo/#af3c20d55579ac56788b8134a4d3e724f">llvm::AMDGPULegalizerInfo::fixStoreSourceType</a>, <a href="/web-llvm/docs/api/classes/llvm/amdgpulegalizerinfo/#a3dcd2bcf223daced673ed18e4ad47efa">llvm::AMDGPULegalizerInfo::handleD16VData</a>, <a href="/web-llvm/docs/api/classes/llvm/amdgpuregisterbankinfo/#a5f5e4d60d30f6101d9aedbc3e0e13bc0">llvm::AMDGPURegisterBankInfo::handleD16VData</a>, <a href="/web-llvm/docs/api/classes/llvm/hexagonasmprinter/#aee072cd97eb6d078d122611833049aa6">llvm::HexagonAsmPrinter::HexagonProcessInstruction</a>, <a href="/web-llvm/docs/api/classes/llvm/amdgpulegalizerinfo/#a4117d1ecf36af9158c825fb376c4082e">llvm::AMDGPULegalizerInfo::legalizeBuildVector</a>, <a href="/web-llvm/docs/api/classes/llvm/amdgpulegalizerinfo/#a94974538095721fcce4cf479555bc25c">llvm::AMDGPULegalizerInfo::legalizeBVHIntrinsic</a>, <a href="/web-llvm/docs/api/classes/llvm/amdgpulegalizerinfo/#a4f3b6abeaf9c509c93062f2246a0f40b">llvm::AMDGPULegalizerInfo::legalizeFDIV</a>, <a href="/web-llvm/docs/api/classes/llvm/amdgpulegalizerinfo/#a6451bf061f754edbcd6043a20bfc663c">llvm::AMDGPULegalizerInfo::legalizeFDIV16</a>, <a href="/web-llvm/docs/api/classes/llvm/amdgpulegalizerinfo/#ad0be6e871a184d6f7b814515324eee1b">llvm::AMDGPULegalizerInfo::legalizeImageIntrinsic</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/amdgpuregbanklegalizerules-cpp/#ad2488daf071559b63411016a2bf09b95">LLTToId</a>, <a href="/web-llvm/docs/api/classes/llvm/legalizerhelper/#aaa03d66b30e1b6173c99b9a4266b7da9">llvm::LegalizerHelper::lowerFPTRUNC</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/amdgpuregbanklegalizerules-cpp/#ac2bfcc1d9b7f5effd45c65a5f973df13">matchUniformityAndLLT</a>, <a href="#a0022aa73e6337684561159d1f7929966">packImage16bitOpsToDwords</a> and <a href="/web-llvm/docs/api/classes/llvm/ppclegalizerinfo/#ae83d1a82dbe98543ff9238ae236b5e20">llvm::PPCLegalizerInfo::PPCLegalizerInfo</a>.</p>

</div>
</div>

### S160 {#a8d3731c41acd28da69f691b8ce22edd4}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">const LLT S160 = LLT::scalar(160)</td>
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



<p>Definition at line 291 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/amdgpulegalizerinfo-cpp">AMDGPULegalizerInfo.cpp</a>.</p>

</div>
</div>

### S192 {#a7654aba611cb44b8c9d4a43398099bf6}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">const LLT S192 = LLT::scalar(192)</td>
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



<p>Definition at line 292 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/amdgpulegalizerinfo-cpp">AMDGPULegalizerInfo.cpp</a>.</p>

</div>
</div>

### S224 {#af775f87ae257bdc6f0b5e5eac41ad51a}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">const LLT S224 = LLT::scalar(224)</td>
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



<p>Definition at line 293 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/amdgpulegalizerinfo-cpp">AMDGPULegalizerInfo.cpp</a>.</p>

</div>
</div>

### S256 {#ae61a7658a9585eba0ff27a47e0c8aea1}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">const LLT S256 = LLT::scalar(256)</td>
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



<p>Definition at line 294 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/amdgpulegalizerinfo-cpp">AMDGPULegalizerInfo.cpp</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/classes/llvm/amdgpulegalizerinfo/#a44a4d4c034685aa34a4e8f62b0976e6c">llvm::AMDGPULegalizerInfo::AMDGPULegalizerInfo</a>.</p>

</div>
</div>

### S32 {#a33c95d7d51d4b0b421aaf3d40796b859}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">const LLT S32 = LLT::scalar(32)</td>
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



<p>Definition at line 285 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/amdgpulegalizerinfo-cpp">AMDGPULegalizerInfo.cpp</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/classes/llvm/sitargetlowering/#add01b669c3b94782f5e3a2babaa12f50">llvm::SITargetLowering::allocateSpecialEntryInputVGPRs</a>, <a href="/web-llvm/docs/api/classes/llvm/amdgpulegalizerinfo/#a44a4d4c034685aa34a4e8f62b0976e6c">llvm::AMDGPULegalizerInfo::AMDGPULegalizerInfo</a>, <a href="/web-llvm/docs/api/classes/anonymous-amdgpuregisterbankinfo-cpp-/applyregbankmapping/#aeef19e805c256d7c5a9135ebe84362cc">anonymous{AMDGPURegisterBankInfo.cpp}::ApplyRegBankMapping::applyBank</a>, <a href="/web-llvm/docs/api/classes/llvm/amdgpuregisterbankinfo/#a67457fbc2d167a5a1a18124bd446278f">llvm::AMDGPURegisterBankInfo::applyMappingBFE</a>, <a href="/web-llvm/docs/api/classes/llvm/amdgpuregisterbankinfo/#a66655fdd73a951d10ad6fb804f0fac98">llvm::AMDGPURegisterBankInfo::applyMappingImpl</a>, <a href="/web-llvm/docs/api/classes/llvm/amdgpuregisterbankinfo/#a87ac3f636dddf683cf1f9b7f1a60b1ae">llvm::AMDGPURegisterBankInfo::applyMappingLoad</a>, <a href="/web-llvm/docs/api/classes/llvm/amdgpuregisterbankinfo/#a59ce3aa458b07483cb7422b0303b589b">llvm::AMDGPURegisterBankInfo::applyMappingMAD_64_32</a>, <a href="/web-llvm/docs/api/classes/llvm/amdgpuregisterbankinfo/#afb1a8a9ef7b460687963fb7968fb7626">llvm::AMDGPURegisterBankInfo::applyMappingSBufferLoad</a>, <a href="/web-llvm/docs/api/structs/anonymous-amdgpucalllowering-cpp-/amdgpuoutgoingvaluehandler/#a0d589439dcf785bc8f36eaf8f4b25a90">anonymous{AMDGPUCallLowering.cpp}::AMDGPUOutgoingValueHandler::assignValueToReg</a>, <a href="/web-llvm/docs/api/classes/llvm/amdgpulegalizerinfo/#ad5c38c10f947e4226f85aade1ebf57f1">llvm::AMDGPULegalizerInfo::buildAbsGlobalAddress</a>, <a href="/web-llvm/docs/api/classes/llvm/amdgpulegalizerinfo/#a01959fee9db67c3a625348ae39489c5e">llvm::AMDGPULegalizerInfo::buildMultiply</a>, <a href="/web-llvm/docs/api/classes/llvm/amdgpuregisterbankinfo/#af693d8401a06eab53b8b5b2d6df05243">llvm::AMDGPURegisterBankInfo::buildReadFirstLane</a>, <a href="#a78249707a06ea5161d8c6bbb442ea46c">castBufferRsrcFromV4I32</a>, <a href="#ad049a79d46df2c25561d90e9d80fb5e3">convertImageAddrToPacked</a>, <a href="#a62e3406e85438cd0a8d5e3de179ef6eb">emitReciprocalU64</a>, <a href="#a47ea7f32b98178dbcb9bf3d1ff00daa1">extractF64Exponent</a>, <a href="/web-llvm/docs/api/classes/llvm/amdgpulegalizerinfo/#a2fd97f50411bc650c7f9f6e3118147f4">llvm::AMDGPULegalizerInfo::getSegmentAperture</a>, <a href="/web-llvm/docs/api/structs/anonymous-amdgpucalllowering-cpp-/amdgpuoutgoingarghandler/#a6901759e2aab843e39497ccb23a0c3cd">anonymous{AMDGPUCallLowering.cpp}::AMDGPUOutgoingArgHandler::getStackAddress</a>, <a href="/web-llvm/docs/api/classes/llvm/amdgpulegalizerinfo/#a3dcd2bcf223daced673ed18e4ad47efa">llvm::AMDGPULegalizerInfo::handleD16VData</a>, <a href="/web-llvm/docs/api/classes/llvm/amdgpuregisterbankinfo/#a5f5e4d60d30f6101d9aedbc3e0e13bc0">llvm::AMDGPURegisterBankInfo::handleD16VData</a>, <a href="/web-llvm/docs/api/classes/llvm/amdgpulegalizerinfo/#a805950c6af7deaddb2d8fbcaf4ea011b">llvm::AMDGPULegalizerInfo::legalizeAddrSpaceCast</a>, <a href="/web-llvm/docs/api/classes/llvm/amdgpulegalizerinfo/#a89e5277b1b90b54ea21a51120f9a4206">llvm::AMDGPULegalizerInfo::legalizeBufferLoad</a>, <a href="/web-llvm/docs/api/classes/llvm/amdgpulegalizerinfo/#a2324ad614c957fc91b34a00f32e89d60">llvm::AMDGPULegalizerInfo::legalizeBufferStore</a>, <a href="/web-llvm/docs/api/classes/llvm/amdgpulegalizerinfo/#a4117d1ecf36af9158c825fb376c4082e">llvm::AMDGPULegalizerInfo::legalizeBuildVector</a>, <a href="/web-llvm/docs/api/classes/llvm/amdgpulegalizerinfo/#a94974538095721fcce4cf479555bc25c">llvm::AMDGPULegalizerInfo::legalizeBVHIntrinsic</a>, <a href="/web-llvm/docs/api/classes/llvm/amdgpulegalizerinfo/#af30d14208a085b7b3e39b25a10f55896">llvm::AMDGPULegalizerInfo::legalizeCTLZ_ZERO_UNDEF</a>, <a href="/web-llvm/docs/api/classes/llvm/amdgpulegalizerinfo/#a4f3b6abeaf9c509c93062f2246a0f40b">llvm::AMDGPULegalizerInfo::legalizeFDIV</a>, <a href="/web-llvm/docs/api/classes/llvm/amdgpulegalizerinfo/#a6451bf061f754edbcd6043a20bfc663c">llvm::AMDGPULegalizerInfo::legalizeFDIV16</a>, <a href="/web-llvm/docs/api/classes/llvm/amdgpulegalizerinfo/#a464ac3e6051fb78eb3ee985975d17cb2">llvm::AMDGPULegalizerInfo::legalizeFDIV32</a>, <a href="/web-llvm/docs/api/classes/llvm/amdgpulegalizerinfo/#a30fc420ff83b1e2c4ab42e86d9071e34">llvm::AMDGPULegalizerInfo::legalizeFDIV64</a>, <a href="/web-llvm/docs/api/classes/llvm/amdgpulegalizerinfo/#a6f737d47e92bb08927c272b12fba32d8">llvm::AMDGPULegalizerInfo::legalizeFDIVFastIntrin</a>, <a href="/web-llvm/docs/api/classes/llvm/amdgpulegalizerinfo/#ac6475a6b99e088697d90032ddab24447">llvm::AMDGPULegalizerInfo::legalizeFPTOI</a>, <a href="/web-llvm/docs/api/classes/llvm/amdgpulegalizerinfo/#ae6424442b4dd0280dd56bc1c577e68ed">llvm::AMDGPULegalizerInfo::legalizeFSQRTF64</a>, <a href="/web-llvm/docs/api/classes/llvm/amdgpulegalizerinfo/#ad6a43ba94ff9ee58996abe2df50464a3">llvm::AMDGPULegalizerInfo::legalizeGetFPEnv</a>, <a href="/web-llvm/docs/api/classes/llvm/amdgpulegalizerinfo/#a04975f118b224e8cd322d1aa86f2ceb2">llvm::AMDGPULegalizerInfo::legalizeGlobalValue</a>, <a href="/web-llvm/docs/api/classes/llvm/amdgpulegalizerinfo/#ad0be6e871a184d6f7b814515324eee1b">llvm::AMDGPULegalizerInfo::legalizeImageIntrinsic</a>, <a href="/web-llvm/docs/api/classes/llvm/amdgpulegalizerinfo/#a5892da00df1f8fb432eab72498344583">llvm::AMDGPULegalizerInfo::legalizeIntrinsic</a>, <a href="/web-llvm/docs/api/classes/llvm/amdgpulegalizerinfo/#a0e7378d479179ae1df0b61b83c637a4d">llvm::AMDGPULegalizerInfo::legalizeIntrinsicTrunc</a>, <a href="/web-llvm/docs/api/classes/llvm/amdgpulegalizerinfo/#abb023d557c720f8730e0c266c1cd0f9c">llvm::AMDGPULegalizerInfo::legalizeITOFP</a>, <a href="/web-llvm/docs/api/classes/llvm/amdgpulegalizerinfo/#af4667ecbc4447b41863430fb572d8f82">llvm::AMDGPULegalizerInfo::legalizeLaneOp</a>, <a href="/web-llvm/docs/api/classes/llvm/amdgpulegalizerinfo/#a2645b2c5fc9b404821322ad403c87810">llvm::AMDGPULegalizerInfo::legalizeMul</a>, <a href="/web-llvm/docs/api/classes/llvm/amdgpulegalizerinfo/#a376125f5ee6f0a21fdd6336557fa3913">llvm::AMDGPULegalizerInfo::legalizePointerAsRsrcIntrin</a>, <a href="/web-llvm/docs/api/classes/llvm/amdgpulegalizerinfo/#af6341dd9dcba1872086b57731b9c096d">llvm::AMDGPULegalizerInfo::legalizeSetFPEnv</a>, <a href="/web-llvm/docs/api/classes/llvm/amdgpulegalizerinfo/#aba263b2348b84c2d9a10adc0a42d9606">llvm::AMDGPULegalizerInfo::legalizeSignedDIV_REM</a>, <a href="/web-llvm/docs/api/classes/llvm/amdgpulegalizerinfo/#a1d0eafc5b0af4bf05b288d62caa72ac9">llvm::AMDGPULegalizerInfo::legalizeUnsignedDIV_REM</a>, <a href="/web-llvm/docs/api/classes/llvm/amdgpulegalizerinfo/#a3db547888c8d2ed5323f320bb5763014">llvm::AMDGPULegalizerInfo::legalizeUnsignedDIV_REM32Impl</a>, <a href="/web-llvm/docs/api/classes/llvm/amdgpulegalizerinfo/#a93bbde2af63d129f752ef7c3a0f84c15">llvm::AMDGPULegalizerInfo::legalizeUnsignedDIV_REM64Impl</a>, <a href="/web-llvm/docs/api/classes/llvm/amdgpulegalizerinfo/#ab0873d6f5bfe8490b5ef6be3a84dd805">llvm::AMDGPULegalizerInfo::legalizeWaveID</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/amdgpuregbanklegalizerules-cpp/#ad2488daf071559b63411016a2bf09b95">LLTToId</a>, <a href="/web-llvm/docs/api/classes/llvm/amdgpulegalizerinfo/#ae63198baedfab72494f0d79823e99b75">llvm::AMDGPULegalizerInfo::loadInputValue</a>, <a href="/web-llvm/docs/api/classes/llvm/legalizerhelper/#ab99f92278021f1921be23b762056a9cc">llvm::LegalizerHelper::lowerFPTOSI</a>, <a href="/web-llvm/docs/api/classes/llvm/legalizerhelper/#a64f47636eb4667460ea08f358d6d39da">llvm::LegalizerHelper::lowerFPTOUI</a>, <a href="/web-llvm/docs/api/classes/llvm/legalizerhelper/#a04ee040b3b0253a0832ddb7915d55ae1">llvm::LegalizerHelper::lowerFPTRUNC_F64_TO_F16</a>, <a href="/web-llvm/docs/api/classes/llvm/legalizerhelper/#a0a4f859f973b7f797f2d510c369980ad">llvm::LegalizerHelper::lowerSITOFP</a>, <a href="/web-llvm/docs/api/classes/llvm/legalizerhelper/#a9b5ad9f5de612dc98a4f3232a98ab754">llvm::LegalizerHelper::lowerU64ToF32BitOps</a>, <a href="/web-llvm/docs/api/classes/llvm/legalizerhelper/#ac9599381b406afe38a263b028248e407">llvm::LegalizerHelper::lowerU64ToF32WithSITOFP</a>, <a href="/web-llvm/docs/api/classes/llvm/legalizerhelper/#a13531e23193d32ac81bdefa1db2ad987">llvm::LegalizerHelper::lowerU64ToF64BitFloatOps</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/amdgpuregbanklegalizerules-cpp/#ac2bfcc1d9b7f5effd45c65a5f973df13">matchUniformityAndLLT</a>, <a href="/web-llvm/docs/api/classes/llvm/amdgpucalllowering/#ac9f5ed1e7ae99c336e8ae9b4ccf10b50">llvm::AMDGPUCallLowering::passSpecialInputs</a>, <a href="/web-llvm/docs/api/classes/llvm/ppclegalizerinfo/#ae83d1a82dbe98543ff9238ae236b5e20">llvm::PPCLegalizerInfo::PPCLegalizerInfo</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/amdgpuregisterbankinfo-cpp/#aeae677889401c02a8def9a0508e858c7">reinsertVectorIndexAdd</a>, <a href="/web-llvm/docs/api/classes/llvm/amdgpuregisterbankinfo/#a8532a373e31385aa7f7ff3c4d14eff4b">llvm::AMDGPURegisterBankInfo::setBufferOffsets</a>, <a href="/web-llvm/docs/api/classes/llvm/amdgpulegalizerinfo/#a14daf64c8f1ebcbe259a41854f49ad12">llvm::AMDGPULegalizerInfo::splitBufferOffsets</a>, <a href="/web-llvm/docs/api/classes/llvm/amdgpuregisterbankinfo/#a0924254734e306adcc8cdcd0e2a3544c">llvm::AMDGPURegisterBankInfo::splitBufferOffsets</a> and <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/amdgpuregisterbankinfo-cpp/#a5227e311d2ae980540efa4033943595e">unpackV2S16ToS32</a>.</p>

</div>
</div>

### S512 {#a7fcbdd8fbd887c5c2c68588ab6179c64}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">const LLT S512 = LLT::scalar(512)</td>
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



<p>Definition at line 295 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/amdgpulegalizerinfo-cpp">AMDGPULegalizerInfo.cpp</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/classes/llvm/amdgpulegalizerinfo/#a44a4d4c034685aa34a4e8f62b0976e6c">llvm::AMDGPULegalizerInfo::AMDGPULegalizerInfo</a>.</p>

</div>
</div>

### S64 {#a2b96ee4926f7c19420d19ecaf7adc1a8}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">const LLT S64 = LLT::scalar(64)</td>
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



<p>Definition at line 287 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/amdgpulegalizerinfo-cpp">AMDGPULegalizerInfo.cpp</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/classes/llvm/amdgpulegalizerinfo/#a44a4d4c034685aa34a4e8f62b0976e6c">llvm::AMDGPULegalizerInfo::AMDGPULegalizerInfo</a>, <a href="/web-llvm/docs/api/classes/llvm/amdgpuregisterbankinfo/#a67457fbc2d167a5a1a18124bd446278f">llvm::AMDGPURegisterBankInfo::applyMappingBFE</a>, <a href="/web-llvm/docs/api/classes/llvm/amdgpuregisterbankinfo/#a66655fdd73a951d10ad6fb804f0fac98">llvm::AMDGPURegisterBankInfo::applyMappingImpl</a>, <a href="/web-llvm/docs/api/classes/llvm/amdgpulegalizerinfo/#a01959fee9db67c3a625348ae39489c5e">llvm::AMDGPULegalizerInfo::buildMultiply</a>, <a href="/web-llvm/docs/api/classes/llvm/amdgpulegalizerinfo/#a2fd97f50411bc650c7f9f6e3118147f4">llvm::AMDGPULegalizerInfo::getSegmentAperture</a>, <a href="/web-llvm/docs/api/classes/llvm/amdgpulegalizerinfo/#ae468aab9eee24365f029a78836e6435d">llvm::AMDGPULegalizerInfo::legalizeFceil</a>, <a href="/web-llvm/docs/api/classes/llvm/amdgpulegalizerinfo/#a4f3b6abeaf9c509c93062f2246a0f40b">llvm::AMDGPULegalizerInfo::legalizeFDIV</a>, <a href="/web-llvm/docs/api/classes/llvm/amdgpulegalizerinfo/#a30fc420ff83b1e2c4ab42e86d9071e34">llvm::AMDGPULegalizerInfo::legalizeFDIV64</a>, <a href="/web-llvm/docs/api/classes/llvm/amdgpulegalizerinfo/#ac6475a6b99e088697d90032ddab24447">llvm::AMDGPULegalizerInfo::legalizeFPTOI</a>, <a href="/web-llvm/docs/api/classes/llvm/amdgpulegalizerinfo/#ad6a43ba94ff9ee58996abe2df50464a3">llvm::AMDGPULegalizerInfo::legalizeGetFPEnv</a>, <a href="/web-llvm/docs/api/classes/llvm/amdgpulegalizerinfo/#a0e7378d479179ae1df0b61b83c637a4d">llvm::AMDGPULegalizerInfo::legalizeIntrinsicTrunc</a>, <a href="/web-llvm/docs/api/classes/llvm/amdgpulegalizerinfo/#abb023d557c720f8730e0c266c1cd0f9c">llvm::AMDGPULegalizerInfo::legalizeITOFP</a>, <a href="/web-llvm/docs/api/classes/llvm/amdgpulegalizerinfo/#af6341dd9dcba1872086b57731b9c096d">llvm::AMDGPULegalizerInfo::legalizeSetFPEnv</a>, <a href="/web-llvm/docs/api/classes/llvm/amdgpulegalizerinfo/#aba263b2348b84c2d9a10adc0a42d9606">llvm::AMDGPULegalizerInfo::legalizeSignedDIV_REM</a>, <a href="/web-llvm/docs/api/classes/llvm/amdgpulegalizerinfo/#af9de933caeeaebd4387c7c62f02a3bbd">llvm::AMDGPULegalizerInfo::legalizeTrapHsaQueuePtr</a>, <a href="/web-llvm/docs/api/classes/llvm/amdgpulegalizerinfo/#a1d0eafc5b0af4bf05b288d62caa72ac9">llvm::AMDGPULegalizerInfo::legalizeUnsignedDIV_REM</a>, <a href="/web-llvm/docs/api/classes/llvm/amdgpulegalizerinfo/#a93bbde2af63d129f752ef7c3a0f84c15">llvm::AMDGPULegalizerInfo::legalizeUnsignedDIV_REM64Impl</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/amdgpuregbanklegalizerules-cpp/#ad2488daf071559b63411016a2bf09b95">LLTToId</a>, <a href="/web-llvm/docs/api/classes/llvm/legalizerhelper/#ab99f92278021f1921be23b762056a9cc">llvm::LegalizerHelper::lowerFPTOSI</a>, <a href="/web-llvm/docs/api/classes/llvm/legalizerhelper/#a64f47636eb4667460ea08f358d6d39da">llvm::LegalizerHelper::lowerFPTOUI</a>, <a href="/web-llvm/docs/api/classes/llvm/legalizerhelper/#aaa03d66b30e1b6173c99b9a4266b7da9">llvm::LegalizerHelper::lowerFPTRUNC</a>, <a href="/web-llvm/docs/api/classes/llvm/legalizerhelper/#a0a4f859f973b7f797f2d510c369980ad">llvm::LegalizerHelper::lowerSITOFP</a>, <a href="/web-llvm/docs/api/classes/llvm/legalizerhelper/#a9b5ad9f5de612dc98a4f3232a98ab754">llvm::LegalizerHelper::lowerU64ToF32BitOps</a>, <a href="/web-llvm/docs/api/classes/llvm/legalizerhelper/#ac9599381b406afe38a263b028248e407">llvm::LegalizerHelper::lowerU64ToF32WithSITOFP</a>, <a href="/web-llvm/docs/api/classes/llvm/legalizerhelper/#a13531e23193d32ac81bdefa1db2ad987">llvm::LegalizerHelper::lowerU64ToF64BitFloatOps</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/amdgpuregbanklegalizerules-cpp/#ac2bfcc1d9b7f5effd45c65a5f973df13">matchUniformityAndLLT</a> and <a href="/web-llvm/docs/api/classes/llvm/ppclegalizerinfo/#ae83d1a82dbe98543ff9238ae236b5e20">llvm::PPCLegalizerInfo::PPCLegalizerInfo</a>.</p>

</div>
</div>

### S8 {#af00ba7c018760702ba16a5009cec810c}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">const LLT S8 = LLT::scalar(8)</td>
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



<p>Definition at line 283 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/amdgpulegalizerinfo-cpp">AMDGPULegalizerInfo.cpp</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/classes/llvm/amdgpulegalizerinfo/#a44a4d4c034685aa34a4e8f62b0976e6c">llvm::AMDGPULegalizerInfo::AMDGPULegalizerInfo</a>, <a href="/web-llvm/docs/api/classes/llvm/stringswitch/#ae160b30f330ff80aca770eccbd622bb0">llvm::StringSwitch&lt; T, R &gt;::Cases</a>, <a href="/web-llvm/docs/api/classes/llvm/stringswitch/#a931ede9419864a545b6b679c025b5bb1">llvm::StringSwitch&lt; T, R &gt;::Cases</a> and <a href="/web-llvm/docs/api/classes/llvm/ppclegalizerinfo/#ae83d1a82dbe98543ff9238ae236b5e20">llvm::PPCLegalizerInfo::PPCLegalizerInfo</a>.</p>

</div>
</div>

### S96 {#ac721ed1f1b2048a37c89fa31e662cd3a}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">const LLT S96 = LLT::scalar(96)</td>
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



<p>Definition at line 289 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/amdgpulegalizerinfo-cpp">AMDGPULegalizerInfo.cpp</a>.</p>

</div>
</div>

### SPDenormModeBitField {#a795662e773d2eda28caf873fa6eb70c4}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">unsigned SPDenormModeBitField</td>
</tr>
</table>
</td>
<td class="doxyMemberLabelsRight">
<span class="doxyMemberLabels">
<span class="doxyMemberLabel constexpr">constexpr</span>
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
<div class="doxyVerbatim">=
    AMDGPU::Hwreg::HwregEncoding::encode(AMDGPU::Hwreg::ID_MODE, 4, 2)
</div>
</dd>
</dl>

<p>Definition at line 4950 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/amdgpulegalizerinfo-cpp">AMDGPULegalizerInfo.cpp</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/classes/llvm/amdgpulegalizerinfo/#a464ac3e6051fb78eb3ee985975d17cb2">llvm::AMDGPULegalizerInfo::legalizeFDIV32</a> and <a href="#abceca15aff80aa1ea3b5e7603981f878">toggleSPDenormMode</a>.</p>

</div>
</div>

### V10S16 {#ace4e8d195c9498b419467f234000a72e}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">const LLT V10S16 = LLT::fixed_vector(10, 16)</td>
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



<p>Definition at line 304 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/amdgpulegalizerinfo-cpp">AMDGPULegalizerInfo.cpp</a>.</p>

</div>
</div>

### V10S32 {#a73e961aa3509555c9944d502a52d1303}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">const LLT V10S32 = LLT::fixed_vector(10, 32)</td>
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



<p>Definition at line 319 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/amdgpulegalizerinfo-cpp">AMDGPULegalizerInfo.cpp</a>.</p>

</div>
</div>

### V11S32 {#a53954ac3898aff9426fc131d14a84f11}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">const LLT V11S32 = LLT::fixed_vector(11, 32)</td>
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



<p>Definition at line 320 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/amdgpulegalizerinfo-cpp">AMDGPULegalizerInfo.cpp</a>.</p>

</div>
</div>

### V12S16 {#a7a3fa97d0457d84638593bf3da5e21f6}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">const LLT V12S16 = LLT::fixed_vector(12, 16)</td>
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



<p>Definition at line 305 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/amdgpulegalizerinfo-cpp">AMDGPULegalizerInfo.cpp</a>.</p>

</div>
</div>

### V12S32 {#a11d102c56b1f897e6886c283d8f16ce4}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">const LLT V12S32 = LLT::fixed_vector(12, 32)</td>
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



<p>Definition at line 321 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/amdgpulegalizerinfo-cpp">AMDGPULegalizerInfo.cpp</a>.</p>

</div>
</div>

### V16S16 {#a09d7d8b975bcef9c12bd114d3b593b00}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">const LLT V16S16 = LLT::fixed_vector(16, 16)</td>
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



<p>Definition at line 306 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/amdgpulegalizerinfo-cpp">AMDGPULegalizerInfo.cpp</a>.</p>

</div>
</div>

### V16S32 {#a83756b36d1fca7fb0054ab52622cda67}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">const LLT V16S32 = LLT::fixed_vector(16, 32)</td>
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



<p>Definition at line 322 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/amdgpulegalizerinfo-cpp">AMDGPULegalizerInfo.cpp</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/classes/llvm/amdgpulegalizerinfo/#a44a4d4c034685aa34a4e8f62b0976e6c">llvm::AMDGPULegalizerInfo::AMDGPULegalizerInfo</a>.</p>

</div>
</div>

### V16S64 {#a7af378812d0f59470e1ad5ff1ac40679}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">const LLT V16S64 = LLT::fixed_vector(16, 64)</td>
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



<p>Definition at line 332 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/amdgpulegalizerinfo-cpp">AMDGPULegalizerInfo.cpp</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/classes/llvm/amdgpulegalizerinfo/#a44a4d4c034685aa34a4e8f62b0976e6c">llvm::AMDGPULegalizerInfo::AMDGPULegalizerInfo</a>.</p>

</div>
</div>

### V2BF16 {#aa6c31d3f7f1803b32735d9b3568e7f12}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">const LLT V2BF16 = <a href="#ade55769087ba2b628fd60dc76161764f">V2F16</a></td>
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



<p>Definition at line 309 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/amdgpulegalizerinfo-cpp">AMDGPULegalizerInfo.cpp</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/classes/llvm/amdgpulegalizerinfo/#a44a4d4c034685aa34a4e8f62b0976e6c">llvm::AMDGPULegalizerInfo::AMDGPULegalizerInfo</a>.</p>

</div>
</div>

### V2F16 {#ade55769087ba2b628fd60dc76161764f}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">const LLT V2F16 = LLT::fixed_vector(2, LLT::float16())</td>
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



<p>Definition at line 308 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/amdgpulegalizerinfo-cpp">AMDGPULegalizerInfo.cpp</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/classes/llvm/amdgpulegalizerinfo/#a44a4d4c034685aa34a4e8f62b0976e6c">llvm::AMDGPULegalizerInfo::AMDGPULegalizerInfo</a>.</p>

</div>
</div>

### V2S128 {#ad61c521a33598d8ca5b07dd4e0f03087}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">const LLT V2S128 = LLT::fixed_vector(2, 128)</td>
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



<p>Definition at line 334 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/amdgpulegalizerinfo-cpp">AMDGPULegalizerInfo.cpp</a>.</p>

</div>
</div>

### V2S16 {#a1a23ce3b10dc058d258a405a87e06a1a}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">const LLT V2S16 = LLT::fixed_vector(2, 16)</td>
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



<p>Definition at line 300 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/amdgpulegalizerinfo-cpp">AMDGPULegalizerInfo.cpp</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/classes/llvm/amdgpulegalizerinfo/#a44a4d4c034685aa34a4e8f62b0976e6c">llvm::AMDGPULegalizerInfo::AMDGPULegalizerInfo</a>, <a href="/web-llvm/docs/api/classes/llvm/amdgpulegalizerinfo/#a94974538095721fcce4cf479555bc25c">llvm::AMDGPULegalizerInfo::legalizeBVHIntrinsic</a>, <a href="/web-llvm/docs/api/classes/llvm/amdgpulegalizerinfo/#ad0be6e871a184d6f7b814515324eee1b">llvm::AMDGPULegalizerInfo::legalizeImageIntrinsic</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/amdgpuregbanklegalizerules-cpp/#ad2488daf071559b63411016a2bf09b95">LLTToId</a> and <a href="#a0022aa73e6337684561159d1f7929966">packImage16bitOpsToDwords</a>.</p>

</div>
</div>

### V2S32 {#a0b000f228cb40bf4aee0a19815ce4d99}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">const LLT V2S32 = LLT::fixed_vector(2, 32)</td>
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



<p>Definition at line 311 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/amdgpulegalizerinfo-cpp">AMDGPULegalizerInfo.cpp</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/classes/llvm/amdgpulegalizerinfo/#a44a4d4c034685aa34a4e8f62b0976e6c">llvm::AMDGPULegalizerInfo::AMDGPULegalizerInfo</a> and <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/amdgpuregbanklegalizerules-cpp/#ad2488daf071559b63411016a2bf09b95">LLTToId</a>.</p>

</div>
</div>

### V2S64 {#acb4ecd614e176840d5b2360a176f1333}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">const LLT V2S64 = LLT::fixed_vector(2, 64)</td>
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



<p>Definition at line 325 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/amdgpulegalizerinfo-cpp">AMDGPULegalizerInfo.cpp</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/classes/llvm/amdgpulegalizerinfo/#a44a4d4c034685aa34a4e8f62b0976e6c">llvm::AMDGPULegalizerInfo::AMDGPULegalizerInfo</a> and <a href="/web-llvm/docs/api/classes/llvm/ppclegalizerinfo/#ae83d1a82dbe98543ff9238ae236b5e20">llvm::PPCLegalizerInfo::PPCLegalizerInfo</a>.</p>

</div>
</div>

### V2S8 {#ab8e5c09740bb85eb6c2d25b534f91570}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">const LLT V2S8 = LLT::fixed_vector(2, 8)</td>
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



<p>Definition at line 299 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/amdgpulegalizerinfo-cpp">AMDGPULegalizerInfo.cpp</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/classes/llvm/amdgpulegalizerinfo/#a44a4d4c034685aa34a4e8f62b0976e6c">llvm::AMDGPULegalizerInfo::AMDGPULegalizerInfo</a>.</p>

</div>
</div>

### V32S32 {#a61cf1ca010a7d653f1cf0ddefa7a8e6d}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">const LLT V32S32 = LLT::fixed_vector(32, 32)</td>
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



<p>Definition at line 323 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/amdgpulegalizerinfo-cpp">AMDGPULegalizerInfo.cpp</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/classes/llvm/amdgpulegalizerinfo/#a44a4d4c034685aa34a4e8f62b0976e6c">llvm::AMDGPULegalizerInfo::AMDGPULegalizerInfo</a>.</p>

</div>
</div>

### V3S32 {#a257279ea49c58180217364b89917c6c3}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">const LLT V3S32 = LLT::fixed_vector(3, 32)</td>
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



<p>Definition at line 312 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/amdgpulegalizerinfo-cpp">AMDGPULegalizerInfo.cpp</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/classes/llvm/amdgpulegalizerinfo/#a94974538095721fcce4cf479555bc25c">llvm::AMDGPULegalizerInfo::legalizeBVHIntrinsic</a> and <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/amdgpuregbanklegalizerules-cpp/#ad2488daf071559b63411016a2bf09b95">LLTToId</a>.</p>

</div>
</div>

### V3S64 {#a0900073ce203e689dc42c702ba6a5c98}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">const LLT V3S64 = LLT::fixed_vector(3, 64)</td>
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



<p>Definition at line 326 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/amdgpulegalizerinfo-cpp">AMDGPULegalizerInfo.cpp</a>.</p>

</div>
</div>

### V4S128 {#a9e404048aa9a1687a9ec6f9d9420bf39}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">const LLT V4S128 = LLT::fixed_vector(4, 128)</td>
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



<p>Definition at line 335 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/amdgpulegalizerinfo-cpp">AMDGPULegalizerInfo.cpp</a>.</p>

</div>
</div>

### V4S16 {#a52e4f67b333637f707e6fe59057c7348}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">const LLT V4S16 = LLT::fixed_vector(4, 16)</td>
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



<p>Definition at line 301 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/amdgpulegalizerinfo-cpp">AMDGPULegalizerInfo.cpp</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/classes/llvm/amdgpulegalizerinfo/#a44a4d4c034685aa34a4e8f62b0976e6c">llvm::AMDGPULegalizerInfo::AMDGPULegalizerInfo</a> and <a href="/web-llvm/docs/api/classes/llvm/amdgpulegalizerinfo/#ad0be6e871a184d6f7b814515324eee1b">llvm::AMDGPULegalizerInfo::legalizeImageIntrinsic</a>.</p>

</div>
</div>

### V4S32 {#a0af4f63c268470ef2eac6477d33fdce4}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">const LLT V4S32 = LLT::fixed_vector(4, 32)</td>
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



<p>Definition at line 313 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/amdgpulegalizerinfo-cpp">AMDGPULegalizerInfo.cpp</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/classes/llvm/amdgpulegalizerinfo/#a44a4d4c034685aa34a4e8f62b0976e6c">llvm::AMDGPULegalizerInfo::AMDGPULegalizerInfo</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/amdgpuregbanklegalizerules-cpp/#ad2488daf071559b63411016a2bf09b95">LLTToId</a> and <a href="/web-llvm/docs/api/classes/llvm/ppclegalizerinfo/#ae83d1a82dbe98543ff9238ae236b5e20">llvm::PPCLegalizerInfo::PPCLegalizerInfo</a>.</p>

</div>
</div>

### V4S64 {#a214d79cea6eb493a2f95b0170886311a}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">const LLT V4S64 = LLT::fixed_vector(4, 64)</td>
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



<p>Definition at line 327 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/amdgpulegalizerinfo-cpp">AMDGPULegalizerInfo.cpp</a>.</p>

</div>
</div>

### V5S32 {#a4d742b8db1d6a22581da42b9b758e2be}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">const LLT V5S32 = LLT::fixed_vector(5, 32)</td>
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



<p>Definition at line 314 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/amdgpulegalizerinfo-cpp">AMDGPULegalizerInfo.cpp</a>.</p>

</div>
</div>

### V5S64 {#a8c4f0c5559c18078956303fa71b2a027}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">const LLT V5S64 = LLT::fixed_vector(5, 64)</td>
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



<p>Definition at line 328 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/amdgpulegalizerinfo-cpp">AMDGPULegalizerInfo.cpp</a>.</p>

</div>
</div>

### V6S16 {#af54c894f1513d925a199547dec0ef2b2}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">const LLT V6S16 = LLT::fixed_vector(6, 16)</td>
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



<p>Definition at line 302 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/amdgpulegalizerinfo-cpp">AMDGPULegalizerInfo.cpp</a>.</p>

</div>
</div>

### V6S32 {#a495ae51584ec946579f24bda39b4fa84}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">const LLT V6S32 = LLT::fixed_vector(6, 32)</td>
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



<p>Definition at line 315 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/amdgpulegalizerinfo-cpp">AMDGPULegalizerInfo.cpp</a>.</p>

</div>
</div>

### V6S64 {#aa95cd588b298b4861271199e3afe971f}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">const LLT V6S64 = LLT::fixed_vector(6, 64)</td>
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



<p>Definition at line 329 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/amdgpulegalizerinfo-cpp">AMDGPULegalizerInfo.cpp</a>.</p>

</div>
</div>

### V7S32 {#a4c29a6c597e1cb2db05e41d65f76d338}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">const LLT V7S32 = LLT::fixed_vector(7, 32)</td>
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



<p>Definition at line 316 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/amdgpulegalizerinfo-cpp">AMDGPULegalizerInfo.cpp</a>.</p>

</div>
</div>

### V7S64 {#a839fd594af5fb0c910f8c3fa13e154a9}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">const LLT V7S64 = LLT::fixed_vector(7, 64)</td>
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



<p>Definition at line 330 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/amdgpulegalizerinfo-cpp">AMDGPULegalizerInfo.cpp</a>.</p>

</div>
</div>

### V8S16 {#af904a5a62bedccf8107722036a8df0ce}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">const LLT V8S16 = LLT::fixed_vector(8, 16)</td>
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



<p>Definition at line 303 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/amdgpulegalizerinfo-cpp">AMDGPULegalizerInfo.cpp</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/classes/llvm/ppclegalizerinfo/#ae83d1a82dbe98543ff9238ae236b5e20">llvm::PPCLegalizerInfo::PPCLegalizerInfo</a>.</p>

</div>
</div>

### V8S32 {#a1348f6cfe026c7a1dca9a61c8713ab07}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">const LLT V8S32 = LLT::fixed_vector(8, 32)</td>
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



<p>Definition at line 317 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/amdgpulegalizerinfo-cpp">AMDGPULegalizerInfo.cpp</a>.</p>

</div>
</div>

### V8S64 {#a0c9c5c4bf19122ed92afa6fe3e70b158}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">const LLT V8S64 = LLT::fixed_vector(8, 64)</td>
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



<p>Definition at line 331 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/amdgpulegalizerinfo-cpp">AMDGPULegalizerInfo.cpp</a>.</p>

</div>
</div>

### V9S32 {#a7261ab9abe3b6583e7e094677e84b50d}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">const LLT V9S32 = LLT::fixed_vector(9, 32)</td>
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



<p>Definition at line 318 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/amdgpulegalizerinfo-cpp">AMDGPULegalizerInfo.cpp</a>.</p>

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
<td class="doxyMemberName">#define DEBUG_TYPE&nbsp;&nbsp;&nbsp;"amdgpu-legalinfo"</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 37 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/amdgpulegalizerinfo-cpp">AMDGPULegalizerInfo.cpp</a>.</p>

</div>
</div>

</div>

<hr/>

<p class="doxyGeneratedBy">Generated via <a href="https://github.com/xpack/doxygen2docusaurus">doxygen2docusaurus</a> by <a href="https://www.doxygen.nl">Doxygen</a> 1.14.0.</p>

</div>
