---

# DO NOT EDIT!
# Automatically generated via doxygen2docusaurus by Doxygen.

slug: /api/files/lib/lib/target/lib/target/amdgpu/amdgpuregbanklegalizerules-cpp
custom_edit_url: null
toc_max_heading_level: 4
keywords:
  - doxygen
  - reference
  - file

---

<div class="doxyPage">

# `AMDGPURegBankLegalizeRules.cpp` File



## Included Headers

<div class="doxyIncludesList">#include "<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/amdgpuregbanklegalizerules-h">AMDGPURegBankLegalizeRules.h</a>"
#include "<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/amdgpuinstrinfo-h">AMDGPUInstrInfo.h</a>"
#include "<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/gcnsubtarget-h">GCNSubtarget.h</a>"
#include "<a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/codegen/include/llvm/codegen/globalisel/genericmachineinstrs-h">llvm/CodeGen/GlobalISel/GenericMachineInstrs.h</a>"
#include "<a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/codegen/machineuniformityanalysis-h">llvm/CodeGen/MachineUniformityAnalysis.h</a>"
#include "llvm/IR/IntrinsicsAMDGPU.h"
#include "<a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/support/amdgpuaddrspace-h">llvm/Support/AMDGPUAddrSpace.h</a>"
</div>

## Classes Index

<table class="doxyMembersIndex">

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">class</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="/web-llvm/docs/api/classes/predicate">Predicate</a></td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">struct</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="/web-llvm/docs/api/structs/predicate/elt">Elt</a></td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">bool</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ac2bfcc1d9b7f5effd45c65a5f973df13">matchUniformityAndLLT</a> (Register Reg, UniformityLLTOpPredicateID UniID, const MachineUniformityInfo &amp;MUI, const MachineRegisterInfo &amp;MRI)</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/namespaces/llvm/amdgpu/#a76e181dec221dc54600e40d350953420">UniformityLLTOpPredicateID</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ad2488daf071559b63411016a2bf09b95">LLTToId</a> (LLT Ty)</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/namespaces/llvm/amdgpu/#a76e181dec221dc54600e40d350953420">UniformityLLTOpPredicateID</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a5430de9bfca0f2700d4afb0121e156fe">LLTToBId</a> (LLT Ty)</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ad78e062f62e0d6e453941fb4ca843e4d">DEBUG_TYPE</a>&nbsp;&nbsp;&nbsp;"amdgpu-regbanklegalize"</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Definitions of RegBankLegalize Rules for all opcodes. <a href="#ad78e062f62e0d6e453941fb4ca843e4d">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

</table>


<div class="doxySectionDef">

## Functions

### LLTToBId() {#a5430de9bfca0f2700d4afb0121e156fe}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">UniformityLLTOpPredicateID LLTToBId (<a href="/web-llvm/docs/api/classes/llvm/llt">LLT</a> Ty)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 184 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/amdgpuregbanklegalizerules-cpp">AMDGPURegBankLegalizeRules.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/hexagon/lib/target/hexagon/mctargetdesc/hexagonmccodeemitter-cpp/#ae4dfd7b0d66121016d6466d2ff10e8ba">_</a>, <a href="/web-llvm/docs/api/namespaces/llvm/amdgpu/#a76e181dec221dc54600e40d350953420a8e33d0d9c111a50cb39e6060f712acc8">llvm::AMDGPU::B128</a>, <a href="/web-llvm/docs/api/namespaces/llvm/amdgpu/#a76e181dec221dc54600e40d350953420aa6f2e5339ef0a03a1aac1a2ded70ee88">llvm::AMDGPU::B32</a>, <a href="/web-llvm/docs/api/namespaces/llvm/amdgpu/#a76e181dec221dc54600e40d350953420a6177319f039156724113f1ef7ed40b0c">llvm::AMDGPU::B64</a>, <a href="/web-llvm/docs/api/namespaces/llvm/amdgpu/#a76e181dec221dc54600e40d350953420adf9dfb559cf5a7298951ba8d91c6d360">llvm::AMDGPU::B96</a>, <a href="/web-llvm/docs/api/classes/llvm/llt/#acd1eca3232b7b3072543294cd2377a37">llvm::LLT::fixed_vector</a>, <a href="/web-llvm/docs/api/classes/llvm/llt/#a7ff0361855acbbe71b15b8dc6003fbc5">llvm::LLT::pointer</a> and <a href="/web-llvm/docs/api/classes/llvm/llt/#a67021459c7ef8f9a634b4eac7ffd0f96">llvm::LLT::scalar</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/classes/llvm/amdgpu/setofrulesforopcode/#a8af003ad0cddc27f1ea6484eb93e06ac">llvm::AMDGPU::SetOfRulesForOpcode::findMappingForMI</a>.</p>

</div>
</div>

### LLTToId() {#ad2488daf071559b63411016a2bf09b95}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">UniformityLLTOpPredicateID LLTToId (<a href="/web-llvm/docs/api/classes/llvm/llt">LLT</a> Ty)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 166 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/amdgpuregbanklegalizerules-cpp">AMDGPURegBankLegalizeRules.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/hexagon/lib/target/hexagon/mctargetdesc/hexagonmccodeemitter-cpp/#ae4dfd7b0d66121016d6466d2ff10e8ba">_</a>, <a href="/web-llvm/docs/api/classes/llvm/llt/#acd1eca3232b7b3072543294cd2377a37">llvm::LLT::fixed_vector</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/amdgpulegalizerinfo-cpp/#acd57bd926bf1c8815e21e1291a54d151">S16</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/amdgpulegalizerinfo-cpp/#a33c95d7d51d4b0b421aaf3d40796b859">S32</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/amdgpulegalizerinfo-cpp/#a2b96ee4926f7c19420d19ecaf7adc1a8">S64</a>, <a href="/web-llvm/docs/api/classes/llvm/llt/#a67021459c7ef8f9a634b4eac7ffd0f96">llvm::LLT::scalar</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/amdgpulegalizerinfo-cpp/#a1a23ce3b10dc058d258a405a87e06a1a">V2S16</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/amdgpulegalizerinfo-cpp/#a0b000f228cb40bf4aee0a19815ce4d99">V2S32</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/amdgpulegalizerinfo-cpp/#a257279ea49c58180217364b89917c6c3">V3S32</a> and <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/amdgpulegalizerinfo-cpp/#a0af4f63c268470ef2eac6477d33fdce4">V4S32</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/classes/llvm/amdgpu/setofrulesforopcode/#a8af003ad0cddc27f1ea6484eb93e06ac">llvm::AMDGPU::SetOfRulesForOpcode::findMappingForMI</a>.</p>

</div>
</div>

### matchUniformityAndLLT() {#ac2bfcc1d9b7f5effd45c65a5f973df13}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool matchUniformityAndLLT (<a href="/web-llvm/docs/api/classes/llvm/register">Register</a> Reg, <a href="/web-llvm/docs/api/namespaces/llvm/amdgpu/#a76e181dec221dc54600e40d350953420">UniformityLLTOpPredicateID</a> UniID, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/namespaces/llvm/#a02b9df38cfd95dfb86cb5b81234df892">MachineUniformityInfo</a> &amp; MUI, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/machineregisterinfo">MachineRegisterInfo</a> &amp; MRI)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 41 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/amdgpuregbanklegalizerules-cpp">AMDGPURegBankLegalizeRules.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/hexagon/lib/target/hexagon/mctargetdesc/hexagonmccodeemitter-cpp/#ae4dfd7b0d66121016d6466d2ff10e8ba">_</a>, <a href="/web-llvm/docs/api/namespaces/llvm/amdgpu/#a76e181dec221dc54600e40d350953420a8e33d0d9c111a50cb39e6060f712acc8">llvm::AMDGPU::B128</a>, <a href="/web-llvm/docs/api/namespaces/llvm/amdgpu/#a76e181dec221dc54600e40d350953420ab48ec0d2d92413d06583513e710645fb">llvm::AMDGPU::B256</a>, <a href="/web-llvm/docs/api/namespaces/llvm/amdgpu/#a76e181dec221dc54600e40d350953420aa6f2e5339ef0a03a1aac1a2ded70ee88">llvm::AMDGPU::B32</a>, <a href="/web-llvm/docs/api/namespaces/llvm/amdgpu/#a76e181dec221dc54600e40d350953420a2df244739d83957ac71aebd10f256231">llvm::AMDGPU::B512</a>, <a href="/web-llvm/docs/api/namespaces/llvm/amdgpu/#a76e181dec221dc54600e40d350953420a6177319f039156724113f1ef7ed40b0c">llvm::AMDGPU::B64</a>, <a href="/web-llvm/docs/api/namespaces/llvm/amdgpu/#a76e181dec221dc54600e40d350953420adf9dfb559cf5a7298951ba8d91c6d360">llvm::AMDGPU::B96</a>, <a href="/web-llvm/docs/api/namespaces/llvm/amdgpu/#a76e181dec221dc54600e40d350953420a1200c596b10f6b45bd8bb059219c4f12">llvm::AMDGPU::DivB128</a>, <a href="/web-llvm/docs/api/namespaces/llvm/amdgpu/#a76e181dec221dc54600e40d350953420acd02fd0cdd6fbc43d3761d3bbcae7f7a">llvm::AMDGPU::DivB256</a>, <a href="/web-llvm/docs/api/namespaces/llvm/amdgpu/#a76e181dec221dc54600e40d350953420a9add2fdc05b41903b41ec3336a2fddd1">llvm::AMDGPU::DivB32</a>, <a href="/web-llvm/docs/api/namespaces/llvm/amdgpu/#a76e181dec221dc54600e40d350953420a3af22f245908c1446994d885848f46af">llvm::AMDGPU::DivB512</a>, <a href="/web-llvm/docs/api/namespaces/llvm/amdgpu/#a76e181dec221dc54600e40d350953420a74dc7cae50483b84b9d95948079daf40">llvm::AMDGPU::DivB64</a>, <a href="/web-llvm/docs/api/namespaces/llvm/amdgpu/#a76e181dec221dc54600e40d350953420af6171405c4a2d6d5045aa9ee504b651e">llvm::AMDGPU::DivB96</a>, <a href="/web-llvm/docs/api/namespaces/llvm/amdgpu/#a76e181dec221dc54600e40d350953420a2c1df13b184923afc2cb79b16c766f57">llvm::AMDGPU::DivP1</a>, <a href="/web-llvm/docs/api/namespaces/llvm/amdgpu/#a76e181dec221dc54600e40d350953420a0c598d889a1443817f7ef6dd2f87ea29">llvm::AMDGPU::DivP3</a>, <a href="/web-llvm/docs/api/namespaces/llvm/amdgpu/#a76e181dec221dc54600e40d350953420ac6b534a26350aaeb0d0217c420def52b">llvm::AMDGPU::DivP4</a>, <a href="/web-llvm/docs/api/namespaces/llvm/amdgpu/#a76e181dec221dc54600e40d350953420ae0af493134959f369c3c548209ce4e64">llvm::AMDGPU::DivP5</a>, <a href="/web-llvm/docs/api/namespaces/llvm/amdgpu/#a76e181dec221dc54600e40d350953420afb78a782d068759a523da387da91d882">llvm::AMDGPU::DivS1</a>, <a href="/web-llvm/docs/api/namespaces/llvm/amdgpu/#a76e181dec221dc54600e40d350953420a9b162f0022f1653589cf67c3b072f9cb">llvm::AMDGPU::DivS32</a>, <a href="/web-llvm/docs/api/namespaces/llvm/amdgpu/#a76e181dec221dc54600e40d350953420a4403259502320119000750de688b1afb">llvm::AMDGPU::DivS64</a>, <a href="/web-llvm/docs/api/classes/llvm/genericuniformityinfo/#a346e760e49252b524cf93d2bc874174e">llvm::GenericUniformityInfo&lt; ContextT &gt;::isDivergent</a>, <a href="/web-llvm/docs/api/classes/llvm/genericuniformityinfo/#a48249434dfd225344cb47d4982c9d5cc">llvm::GenericUniformityInfo&lt; ContextT &gt;::isUniform</a>, <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/support/errorhandling-h/#ace243f5c25697a1107cce46626b3dc94">llvm_unreachable</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64advsimdscalarpass-cpp/#aacd2ab195054a3e6a74bfbb9d5d571c8">MRI</a>, <a href="/web-llvm/docs/api/namespaces/llvm/amdgpu/#a76e181dec221dc54600e40d350953420a16c3a14a4de3fbf61469a9c80a01a9ed">llvm::AMDGPU::P1</a>, <a href="/web-llvm/docs/api/namespaces/llvm/amdgpu/#a76e181dec221dc54600e40d350953420af92b6003daf929bf36028443a9790150">llvm::AMDGPU::P3</a>, <a href="/web-llvm/docs/api/namespaces/llvm/amdgpu/#a76e181dec221dc54600e40d350953420a7f414452d83a1489f791f7164971019a">llvm::AMDGPU::P4</a>, <a href="/web-llvm/docs/api/namespaces/llvm/amdgpu/#a76e181dec221dc54600e40d350953420a42cbb5784c00f3dd0212fc7bfeebbe90">llvm::AMDGPU::P5</a>, <a href="/web-llvm/docs/api/classes/llvm/llt/#a7ff0361855acbbe71b15b8dc6003fbc5">llvm::LLT::pointer</a>, <a href="/web-llvm/docs/api/files/lib/lib/codegen/machinesink-cpp/#a359e1ff26f6d466d927a61aae45b05c3">Reg</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/amdgpulegalizerinfo-cpp/#a22eabd3566ae5f32cb6f594f4f343399">S1</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/amdgpulegalizerinfo-cpp/#acd57bd926bf1c8815e21e1291a54d151">S16</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/amdgpulegalizerinfo-cpp/#a33c95d7d51d4b0b421aaf3d40796b859">S32</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/amdgpulegalizerinfo-cpp/#a2b96ee4926f7c19420d19ecaf7adc1a8">S64</a>, <a href="/web-llvm/docs/api/classes/llvm/llt/#a67021459c7ef8f9a634b4eac7ffd0f96">llvm::LLT::scalar</a>, <a href="/web-llvm/docs/api/namespaces/llvm/amdgpu/#a76e181dec221dc54600e40d350953420a5010d1330cc47e215b31568774f805cd">llvm::AMDGPU::UniB128</a>, <a href="/web-llvm/docs/api/namespaces/llvm/amdgpu/#a76e181dec221dc54600e40d350953420af6e9d4a12a2dcf16f084720a1ef87941">llvm::AMDGPU::UniB256</a>, <a href="/web-llvm/docs/api/namespaces/llvm/amdgpu/#a76e181dec221dc54600e40d350953420a4f7512b2db0c88a026ac6b312a2e20ef">llvm::AMDGPU::UniB32</a>, <a href="/web-llvm/docs/api/namespaces/llvm/amdgpu/#a76e181dec221dc54600e40d350953420a3a4a82361555b80d3c6297236c83b7e2">llvm::AMDGPU::UniB512</a>, <a href="/web-llvm/docs/api/namespaces/llvm/amdgpu/#a76e181dec221dc54600e40d350953420a439c9b575e412dbb0ac9f8e6179b4728">llvm::AMDGPU::UniB64</a>, <a href="/web-llvm/docs/api/namespaces/llvm/amdgpu/#a76e181dec221dc54600e40d350953420a9bb212a131349c1db3f88ca6ee67434b">llvm::AMDGPU::UniB96</a>, <a href="/web-llvm/docs/api/namespaces/llvm/amdgpu/#a76e181dec221dc54600e40d350953420a988754bd8189f1fe50f0c35fcd4fe89a">llvm::AMDGPU::UniP1</a>, <a href="/web-llvm/docs/api/namespaces/llvm/amdgpu/#a76e181dec221dc54600e40d350953420ae746790acf7e929808a4600690d1b58d">llvm::AMDGPU::UniP3</a>, <a href="/web-llvm/docs/api/namespaces/llvm/amdgpu/#a76e181dec221dc54600e40d350953420ae7d7ff3ebc4c6919fe11d44e42e2ffdd">llvm::AMDGPU::UniP4</a>, <a href="/web-llvm/docs/api/namespaces/llvm/amdgpu/#a76e181dec221dc54600e40d350953420adbc949905d6ae3277cf6bc15a3306437">llvm::AMDGPU::UniP5</a>, <a href="/web-llvm/docs/api/namespaces/llvm/amdgpu/#a76e181dec221dc54600e40d350953420a7a410554c7d5aec017fb84e95b95ffff">llvm::AMDGPU::UniS1</a>, <a href="/web-llvm/docs/api/namespaces/llvm/amdgpu/#a76e181dec221dc54600e40d350953420add4a306f664c8209ecf726d99b5704fd">llvm::AMDGPU::UniS16</a>, <a href="/web-llvm/docs/api/namespaces/llvm/amdgpu/#a76e181dec221dc54600e40d350953420a26f1c53b64b980b589c64fd9f61ec50f">llvm::AMDGPU::UniS32</a> and <a href="/web-llvm/docs/api/namespaces/llvm/amdgpu/#a76e181dec221dc54600e40d350953420a4a917415d28aa004b6b5390d58c36401">llvm::AMDGPU::UniS64</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/structs/llvm/amdgpu/predicatemapping/#a8566d56fd1d655d436f77922e14a14ee">llvm::AMDGPU::PredicateMapping::match</a>.</p>

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
<td class="doxyMemberName">#define DEBUG_TYPE&nbsp;&nbsp;&nbsp;"amdgpu-regbanklegalize"</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Definitions of RegBankLegalize Rules for all opcodes.</p>


<p>Implementation of container for all the Rules and search. Fast search for most common case when Rule.Predicate checks <a href="/web-llvm/docs/api/classes/llvm/llt">LLT</a> and uniformity of register in operand 0.</p>


<p>Definition at line 24 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/amdgpuregbanklegalizerules-cpp">AMDGPURegBankLegalizeRules.cpp</a>.</p>

</div>
</div>

</div>

<hr/>

<p class="doxyGeneratedBy">Generated via <a href="https://xpack.github.io/doxygen2docusaurus">doxygen2docusaurus</a> 2.0.0 by <a href="https://www.doxygen.nl">Doxygen</a> 1.15.0.</p>

</div>
