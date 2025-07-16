---

# DO NOT EDIT!
# Automatically generated via doxygen2docusaurus by Doxygen.

slug: /api/files/lib/lib/target/lib/target/arm/lib/target/arm/mctargetdesc/armtargetstreamer-cpp
custom_edit_url: null
toc_max_heading_level: 4
keywords:
  - doxygen
  - reference
  - file

---

<div class="doxyPage">

# The `ARMTargetStreamer.cpp` File Reference



## Included Headers

<div class="doxyIncludesList">#include "<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/arm/lib/target/arm/mctargetdesc/armmctargetdesc-h">MCTargetDesc/ARMMCTargetDesc.h</a>"
#include "<a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/mc/constantpools-h">llvm/MC/ConstantPools.h</a>"
#include "<a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/mc/mcasminfo-h">llvm/MC/MCAsmInfo.h</a>"
#include "<a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/mc/mccontext-h">llvm/MC/MCContext.h</a>"
#include "<a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/mc/mcexpr-h">llvm/MC/MCExpr.h</a>"
#include "<a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/mc/mcstreamer-h">llvm/MC/MCStreamer.h</a>"
#include "<a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/mc/mcsubtargetinfo-h">llvm/MC/MCSubtargetInfo.h</a>"
#include "<a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/support/armbuildattributes-h">llvm/Support/ARMBuildAttributes.h</a>"
</div>

## Functions Index

<table class="doxyMembersIndex">

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">static <a href="/web-llvm/docs/api/namespaces/llvm/armbuildattrs/#a6f3569befc20dac7d092acbfc2ecbf04">ARMBuildAttrs::CPUArch</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#aaf6e4a38fe1be7aab9c4e702d9dbb396">getArchForCPU</a> (const MCSubtargetInfo &amp;STI)</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a482a1a87ca8a29083e5c88eac796ed62">isV8M</a> (const MCSubtargetInfo &amp;STI)</td>
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

### getArchForCPU() {#aaf6e4a38fe1be7aab9c4e702d9dbb396}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">ARMBuildAttrs::CPUArch getArchForCPU (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/mcsubtargetinfo">MCSubtargetInfo</a> &amp; STI)</td>
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



<p>Definition at line 131 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/arm/lib/target/arm/mctargetdesc/armtargetstreamer-cpp">ARMTargetStreamer.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/classes/llvm/mcsubtargetinfo/#a5d5452528429597f223826cbc63ca867">llvm::MCSubtargetInfo::getCPU</a>, <a href="/web-llvm/docs/api/classes/llvm/mcsubtargetinfo/#a0ad14e9a81239b54fd64089b3290bfde">llvm::MCSubtargetInfo::hasFeature</a>, <a href="/web-llvm/docs/api/namespaces/llvm/armbuildattrs/#a6f3569befc20dac7d092acbfc2ecbf04aba09d4835b95fc1a37b8883bbbbddbd1">llvm::ARMBuildAttrs::v4</a>, <a href="/web-llvm/docs/api/namespaces/llvm/armbuildattrs/#a6f3569befc20dac7d092acbfc2ecbf04a2519f8fd19963254840edfa09c21a565">llvm::ARMBuildAttrs::v4T</a>, <a href="/web-llvm/docs/api/namespaces/llvm/armbuildattrs/#a6f3569befc20dac7d092acbfc2ecbf04acf263340a2ed14be933a5369f5094447">llvm::ARMBuildAttrs::v5T</a>, <a href="/web-llvm/docs/api/namespaces/llvm/armbuildattrs/#a6f3569befc20dac7d092acbfc2ecbf04a5593c6c42fb67cb1f5f62845693a28fa">llvm::ARMBuildAttrs::v5TE</a>, <a href="/web-llvm/docs/api/namespaces/llvm/armbuildattrs/#a6f3569befc20dac7d092acbfc2ecbf04acd8b908686196c4123cdb4251b5661d0">llvm::ARMBuildAttrs::v5TEJ</a>, <a href="/web-llvm/docs/api/namespaces/llvm/armbuildattrs/#a6f3569befc20dac7d092acbfc2ecbf04a08b94165165355a8b5da8663f656b783">llvm::ARMBuildAttrs::v6</a>, <a href="/web-llvm/docs/api/namespaces/llvm/armbuildattrs/#a6f3569befc20dac7d092acbfc2ecbf04a4a4933da5591cff473164615859f9558">llvm::ARMBuildAttrs::v6S_M</a>, <a href="/web-llvm/docs/api/namespaces/llvm/armbuildattrs/#a6f3569befc20dac7d092acbfc2ecbf04ace4bdfa827c96c98399ec299deb3e6d1">llvm::ARMBuildAttrs::v6T2</a>, <a href="/web-llvm/docs/api/namespaces/llvm/armbuildattrs/#a6f3569befc20dac7d092acbfc2ecbf04a3cf0cd428f021cea15953922332619e7">llvm::ARMBuildAttrs::v7</a>, <a href="/web-llvm/docs/api/namespaces/llvm/armbuildattrs/#a6f3569befc20dac7d092acbfc2ecbf04a49b5daf5353b4da268f64fef514a443f">llvm::ARMBuildAttrs::v7E_M</a>, <a href="/web-llvm/docs/api/namespaces/llvm/armbuildattrs/#a6f3569befc20dac7d092acbfc2ecbf04a33780b53b2b0f05453df0d9fdaa4b04f">llvm::ARMBuildAttrs::v8_1_M_Main</a>, <a href="/web-llvm/docs/api/namespaces/llvm/armbuildattrs/#a6f3569befc20dac7d092acbfc2ecbf04ae939f53cb580663a92ac0b5ea2a203f6">llvm::ARMBuildAttrs::v8_A</a>, <a href="/web-llvm/docs/api/namespaces/llvm/armbuildattrs/#a6f3569befc20dac7d092acbfc2ecbf04a20ea6e94be6a97156977fe988078462a">llvm::ARMBuildAttrs::v8_M_Base</a>, <a href="/web-llvm/docs/api/namespaces/llvm/armbuildattrs/#a6f3569befc20dac7d092acbfc2ecbf04a518a8feea596bb0014fd3d0bca83c844">llvm::ARMBuildAttrs::v8_M_Main</a>, <a href="/web-llvm/docs/api/namespaces/llvm/armbuildattrs/#a6f3569befc20dac7d092acbfc2ecbf04a97beaa983d40bf4220e8c224f68e4578">llvm::ARMBuildAttrs::v8_R</a> and <a href="/web-llvm/docs/api/namespaces/llvm/armbuildattrs/#a6f3569befc20dac7d092acbfc2ecbf04a1188f7dc8364dbce20bfa37134594cdf">llvm::ARMBuildAttrs::v9_A</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/classes/llvm/armtargetstreamer/#a17b7b6be8c77b055cf79259a4af7ff0c">llvm::ARMTargetStreamer::emitTargetAttributes</a>.</p>

</div>
</div>

### isV8M() {#a482a1a87ca8a29083e5c88eac796ed62}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool isV8M (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/mcsubtargetinfo">MCSubtargetInfo</a> &amp; STI)</td>
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



<p>Definition at line 167 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/arm/lib/target/arm/mctargetdesc/armtargetstreamer-cpp">ARMTargetStreamer.cpp</a>.</p>


<p>Reference <a href="/web-llvm/docs/api/classes/llvm/mcsubtargetinfo/#a0ad14e9a81239b54fd64089b3290bfde">llvm::MCSubtargetInfo::hasFeature</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/classes/llvm/armtargetstreamer/#a17b7b6be8c77b055cf79259a4af7ff0c">llvm::ARMTargetStreamer::emitTargetAttributes</a>.</p>

</div>
</div>

</div>

<hr/>

<p class="doxyGeneratedBy">Generated via <a href="https://github.com/xpack/doxygen2docusaurus">doxygen2docusaurus</a> by <a href="https://www.doxygen.nl">Doxygen</a> 1.15.0.</p>

</div>
