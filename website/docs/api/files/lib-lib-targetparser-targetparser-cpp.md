---

# DO NOT EDIT!
# Automatically generated via doxygen2docusaurus by Doxygen.

slug: /api/files/lib/lib/targetparser/targetparser-cpp
custom_edit_url: null
toc_max_heading_level: 4
keywords:
  - doxygen
  - reference
  - file

---

<div class="doxyPage">

# The `TargetParser.cpp` File Reference



## Included Headers

<div class="doxyIncludesList">#include "<a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/targetparser/targetparser-h">llvm/TargetParser/TargetParser.h</a>"
#include "<a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/adt/arrayref-h">llvm/ADT/ArrayRef.h</a>"
#include "<a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/targetparser/triple-h">llvm/TargetParser/Triple.h</a>"
</div>

## Namespaces Index

<table class="doxyMembersIndex">

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">namespace</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="/web-llvm/docs/api/namespaces/anonymous-targetparser-cpp-">anonymous{TargetParser.cpp}</a></td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="/web-llvm/docs/api/structs/anonymous-targetparser-cpp-/gpuinfo">GPUInfo</a></td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">static bool</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a5088972ea77dc548385d0c903f56683b">isWave32Capable</a> (StringRef GPU, const Triple &amp;T)</td>
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

### isWave32Capable() {#a5088972ea77dc548385d0c903f56683b}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool isWave32Capable (<a href="/web-llvm/docs/api/classes/llvm/stringref">StringRef</a> GPU, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/triple">Triple</a> &amp; T)</td>
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



<p>Definition at line 630 of file <a href="/web-llvm/docs/api/files/lib/lib/targetparser/targetparser-cpp">TargetParser.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/namespaces/llvm/amdgpu/#a13e9112ff7e4f43ca57811e8315558c0ad91847f0315557cbaa80e134f41b126b">llvm::AMDGPU::GK_GFX1010</a>, <a href="/web-llvm/docs/api/namespaces/llvm/amdgpu/#a13e9112ff7e4f43ca57811e8315558c0af52d637bc791e67bcad28549446ef2f5">llvm::AMDGPU::GK_GFX1011</a>, <a href="/web-llvm/docs/api/namespaces/llvm/amdgpu/#a13e9112ff7e4f43ca57811e8315558c0abcd4e53544524c77b26e75b3324e6e2d">llvm::AMDGPU::GK_GFX1012</a>, <a href="/web-llvm/docs/api/namespaces/llvm/amdgpu/#a13e9112ff7e4f43ca57811e8315558c0a1666585da5fa94f8ffc4ef239e35d402">llvm::AMDGPU::GK_GFX1013</a>, <a href="/web-llvm/docs/api/namespaces/llvm/amdgpu/#a13e9112ff7e4f43ca57811e8315558c0a0af7c4fa5f04c90c04af24b475146443">llvm::AMDGPU::GK_GFX1030</a>, <a href="/web-llvm/docs/api/namespaces/llvm/amdgpu/#a13e9112ff7e4f43ca57811e8315558c0a4890850c6802640e28da0127a4028628">llvm::AMDGPU::GK_GFX1031</a>, <a href="/web-llvm/docs/api/namespaces/llvm/amdgpu/#a13e9112ff7e4f43ca57811e8315558c0af839fd11ff6ef14278ce5ab2909ecacc">llvm::AMDGPU::GK_GFX1032</a>, <a href="/web-llvm/docs/api/namespaces/llvm/amdgpu/#a13e9112ff7e4f43ca57811e8315558c0a1cf86d1b367f32d4dcce6b1263851727">llvm::AMDGPU::GK_GFX1033</a>, <a href="/web-llvm/docs/api/namespaces/llvm/amdgpu/#a13e9112ff7e4f43ca57811e8315558c0ad86d9c309318d0e898c11b962f2689ae">llvm::AMDGPU::GK_GFX1034</a>, <a href="/web-llvm/docs/api/namespaces/llvm/amdgpu/#a13e9112ff7e4f43ca57811e8315558c0a72c46554b31a1af487670cb1b482e071">llvm::AMDGPU::GK_GFX1035</a>, <a href="/web-llvm/docs/api/namespaces/llvm/amdgpu/#a13e9112ff7e4f43ca57811e8315558c0ae40a66d6dde5d1afbf7c88bea752f8d2">llvm::AMDGPU::GK_GFX1036</a>, <a href="/web-llvm/docs/api/namespaces/llvm/amdgpu/#a13e9112ff7e4f43ca57811e8315558c0aa99086974c656449b0a768a397077871">llvm::AMDGPU::GK_GFX10_1_GENERIC</a>, <a href="/web-llvm/docs/api/namespaces/llvm/amdgpu/#a13e9112ff7e4f43ca57811e8315558c0a34226d524b27afc332b8d49a773e6386">llvm::AMDGPU::GK_GFX10_3_GENERIC</a>, <a href="/web-llvm/docs/api/namespaces/llvm/amdgpu/#a13e9112ff7e4f43ca57811e8315558c0a95657bf48aa53bd9069caf9a4cf4a85b">llvm::AMDGPU::GK_GFX1100</a>, <a href="/web-llvm/docs/api/namespaces/llvm/amdgpu/#a13e9112ff7e4f43ca57811e8315558c0a69eee5a82feaeecf8a11c1537d0be7f9">llvm::AMDGPU::GK_GFX1101</a>, <a href="/web-llvm/docs/api/namespaces/llvm/amdgpu/#a13e9112ff7e4f43ca57811e8315558c0a56bc624c035fcd4f0cb0dcc8fa69ac44">llvm::AMDGPU::GK_GFX1102</a>, <a href="/web-llvm/docs/api/namespaces/llvm/amdgpu/#a13e9112ff7e4f43ca57811e8315558c0adb1513c858da01a82dd680c31847fdf8">llvm::AMDGPU::GK_GFX1103</a>, <a href="/web-llvm/docs/api/namespaces/llvm/amdgpu/#a13e9112ff7e4f43ca57811e8315558c0a8e887e52f2ac42f801debc4beeb39088">llvm::AMDGPU::GK_GFX1150</a>, <a href="/web-llvm/docs/api/namespaces/llvm/amdgpu/#a13e9112ff7e4f43ca57811e8315558c0aa70ba858a11343b6a2f2a07a570f071f">llvm::AMDGPU::GK_GFX1151</a>, <a href="/web-llvm/docs/api/namespaces/llvm/amdgpu/#a13e9112ff7e4f43ca57811e8315558c0ad484cc41ee4e53f7ff2a31d82fb7fd05">llvm::AMDGPU::GK_GFX1152</a>, <a href="/web-llvm/docs/api/namespaces/llvm/amdgpu/#a13e9112ff7e4f43ca57811e8315558c0ab050d267cac9447dce920a24d0868330">llvm::AMDGPU::GK_GFX1153</a>, <a href="/web-llvm/docs/api/namespaces/llvm/amdgpu/#a13e9112ff7e4f43ca57811e8315558c0aea7938fa858839b99bc77596636e6a33">llvm::AMDGPU::GK_GFX11_GENERIC</a>, <a href="/web-llvm/docs/api/namespaces/llvm/amdgpu/#a13e9112ff7e4f43ca57811e8315558c0a85bdff80fea1923cfef4be6d72a0deb9">llvm::AMDGPU::GK_GFX1200</a>, <a href="/web-llvm/docs/api/namespaces/llvm/amdgpu/#a13e9112ff7e4f43ca57811e8315558c0ad97e690142b36bc08a093a9ec302cc51">llvm::AMDGPU::GK_GFX1201</a>, <a href="/web-llvm/docs/api/namespaces/llvm/amdgpu/#a13e9112ff7e4f43ca57811e8315558c0a7d26ffeeb2d981fbfc571f04e6a0b591">llvm::AMDGPU::GK_GFX12_GENERIC</a>, <a href="/web-llvm/docs/api/namespaces/llvm/amdgpu/#a98ac623b540c21285a2307f08fe7d237">llvm::AMDGPU::parseArchAMDGCN</a> and <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/mips/mips16isellowering-cpp/#a0acb682b8260ab1c60b918599864e2e5">T</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/namespaces/llvm/amdgpu/#a62ffd7301f2325401902cda2f544da0a">llvm::AMDGPU::insertWaveSizeFeature</a>.</p>

</div>
</div>

</div>

<hr/>

<p class="doxyGeneratedBy">Generated via <a href="https://github.com/xpack/doxygen2docusaurus">doxygen2docusaurus</a> by <a href="https://www.doxygen.nl">Doxygen</a> 1.14.0.</p>

</div>
