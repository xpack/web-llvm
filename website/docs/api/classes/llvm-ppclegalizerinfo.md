---

# DO NOT EDIT!
# Automatically generated via doxygen2docusaurus by Doxygen.

slug: /api/classes/llvm/ppclegalizerinfo
custom_edit_url: null
toc_max_heading_level: 4
keywords:
  - doxygen
  - reference
  - class

---

<div class="doxyPage">

# The `PPCLegalizerInfo` Class Reference

<p>This class provides the information for the PowerPC target legalizer for GlobalISel. <a href="#details">More...</a></p>

## Declaration

<div class="doxyDeclaration">
class llvm::PPCLegalizerInfo { ... }
</div>

## Included Headers

<div class="doxyIncludesList">#include "<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/powerpc/lib/target/powerpc/gisel/ppclegalizerinfo-h">Target/PowerPC/GISel/PPCLegalizerInfo.h</a>"
</div>

## Base class

<table class="doxyMembersIndex">

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">class</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/legalizerinfo">LegalizerInfo</a></td>
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

## Public Constructors Index

<table class="doxyMembersIndex">

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ae83d1a82dbe98543ff9238ae236b5e20">PPCLegalizerInfo</a> (const PPCSubtarget &amp;ST)</td>
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

<p>This class provides the information for the PowerPC target legalizer for GlobalISel.</p>

<p>Definition at line 23 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/powerpc/lib/target/powerpc/gisel/ppclegalizerinfo-h">PPCLegalizerInfo.h</a>.</p>


<div class="doxySectionDef">

## Public Constructors

### PPCLegalizerInfo() {#ae83d1a82dbe98543ff9238ae236b5e20}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">PPCLegalizerInfo::PPCLegalizerInfo (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/ppcsubtarget">PPCSubtarget</a> &amp; ST)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Declaration at line 25 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/powerpc/lib/target/powerpc/gisel/ppclegalizerinfo-h">PPCLegalizerInfo.h</a>, definition at line 39 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/powerpc/lib/target/powerpc/gisel/ppclegalizerinfo-cpp">PPCLegalizerInfo.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/namespaces/llvm/legalitypredicates/#ad7ac7032baa62cc00002886633b9f281">llvm::LegalityPredicates::all</a>, <a href="/web-llvm/docs/api/classes/llvm/legalizeruleset/#a3128e17013a7e7dd6a855d0b00ad60f9">llvm::LegalizeRuleSet::bitcastIf</a>, <a href="/web-llvm/docs/api/namespaces/llvm/legalizemutations/#acd331b959990c033f8d612adf7701b05">llvm::LegalizeMutations::changeTo</a>, <a href="/web-llvm/docs/api/classes/llvm/legacylegalizerinfo/#a6b586580f1e35e04ae0f3186fadd6594">llvm::LegacyLegalizerInfo::computeTables</a>, <a href="/web-llvm/docs/api/classes/llvm/llt/#acd1eca3232b7b3072543294cd2377a37">llvm::LLT::fixed_vector</a>, <a href="/web-llvm/docs/api/classes/llvm/legalizerinfo/#a32539827696dafee94ee79c3321b4245">llvm::LegalizerInfo::getActionDefinitionsBuilder</a>, <a href="/web-llvm/docs/api/classes/llvm/legalizerinfo/#a33b434e9218db992447f811551810394">llvm::LegalizerInfo::getLegacyLegalizerInfo</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/amdgpulegalizerinfo-cpp/#a2ea867ab6af309ac37d89c0ac9242600">isRegisterType</a>, <a href="/web-llvm/docs/api/classes/llvm/legalizeruleset/#a1c27c69ac65f9d4937858c10288a17f6">llvm::LegalizeRuleSet::legalFor</a>, <a href="/web-llvm/docs/api/classes/llvm/legalizeruleset/#ae4c02bcf9d3bfdee70f097d0b6aeb9f3">llvm::LegalizeRuleSet::legalForCartesianProduct</a>, <a href="/web-llvm/docs/api/classes/llvm/legalizeruleset/#af6dcfac5a30e4050e3ac204f27062fe6">llvm::LegalizeRuleSet::legalIf</a>, <a href="/web-llvm/docs/api/classes/llvm/legalizeruleset/#a6a836d4faf3f9f04f1f04cc5f6de3c03">llvm::LegalizeRuleSet::lower</a>, <a href="/web-llvm/docs/api/classes/llvm/legalizeruleset/#a6eec582df34bb1c63e8666b41ff561ec">llvm::LegalizeRuleSet::lowerFor</a>, <a href="/web-llvm/docs/api/classes/llvm/llt/#a7ff0361855acbbe71b15b8dc6003fbc5">llvm::LLT::pointer</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/amdgpulegalizerinfo-cpp/#a22eabd3566ae5f32cb6f594f4f343399">S1</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/amdgpulegalizerinfo-cpp/#acd57bd926bf1c8815e21e1291a54d151">S16</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/amdgpulegalizerinfo-cpp/#a33c95d7d51d4b0b421aaf3d40796b859">S32</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/amdgpulegalizerinfo-cpp/#a2b96ee4926f7c19420d19ecaf7adc1a8">S64</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/amdgpulegalizerinfo-cpp/#af00ba7c018760702ba16a5009cec810c">S8</a>, <a href="/web-llvm/docs/api/classes/llvm/llt/#a67021459c7ef8f9a634b4eac7ffd0f96">llvm::LLT::scalar</a>, <a href="/web-llvm/docs/api/namespaces/llvm/legalitypredicates/#ab82dcf447c1a6ace035cab178a049b39">llvm::LegalityPredicates::typeIsNot</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/amdgpulegalizerinfo-cpp/#acb4ecd614e176840d5b2360a176f1333">V2S64</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/amdgpulegalizerinfo-cpp/#a0af4f63c268470ef2eac6477d33fdce4">V4S32</a> and <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/amdgpulegalizerinfo-cpp/#af904a5a62bedccf8107722036a8df0ce">V8S16</a>.</p>

</div>
</div>

</div>

<hr/>

The documentation for this class was generated from the following files:

<ul>
<li><a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/powerpc/lib/target/powerpc/gisel/ppclegalizerinfo-cpp">PPCLegalizerInfo.cpp</a></li>
<li><a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/powerpc/lib/target/powerpc/gisel/ppclegalizerinfo-h">PPCLegalizerInfo.h</a></li>
</ul>

<hr/>

<p class="doxyGeneratedBy">Generated via <a href="https://github.com/xpack/doxygen2docusaurus">doxygen2docusaurus</a> by <a href="https://www.doxygen.nl">Doxygen</a> 1.14.0.</p>

</div>
