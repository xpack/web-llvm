---

# DO NOT EDIT!
# Automatically generated via doxygen2docusaurus by Doxygen.

slug: /api/classes/llvm/arm/wineh/runtimefunctionarm64
custom_edit_url: null
toc_max_heading_level: 4
keywords:
  - doxygen
  - reference
  - class

---

<div class="doxyPage">

# The `RuntimeFunctionARM64` Class Reference

<p><a href="/web-llvm/docs/api/classes/llvm/arm/wineh/runtimefunctionarm64">RuntimeFunctionARM64</a> - An entry in the table of procedure data (.pdata) <a href="#details">More...</a></p>

## Declaration

<div class="doxyDeclaration">
class llvm::ARM::WinEH::RuntimeFunctionARM64 { ... }
</div>

## Included Headers

<div class="doxyIncludesList">#include "<a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/support/armwineh-h">llvm/Support/ARMWinEH.h</a>"
</div>

## Public Constructors Index

<table class="doxyMembersIndex">

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a0dc094bdfb506dc8ee0dd934834f569f">RuntimeFunctionARM64</a> (const support::ulittle32_t *Data)</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a4673cc53656da8df66cdad97dd8648c0">RuntimeFunctionARM64</a> (const support::ulittle32_t BeginAddress, const support::ulittle32_t UnwindData)</td>
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

## Public Member Functions Index

<table class="doxyMembersIndex">

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/namespaces/llvm/arm/wineh/#a42eec988a426045927f9b40043dad476">RuntimeFunctionFlag</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ad1f3a592c7416aae13ed4b680f83cd13">Flag</a> () const</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">uint32_t</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a7bd7b8b4c0172b2019f66ba3dd346d66">ExceptionInformationRVA</a> () const</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">uint32_t</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a237ce46af95d080421995cb4ddf02fef">PackedUnwindData</a> () const</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">uint32_t</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a5ef74e462393cd85864949453f4612ff">FunctionLength</a> () const</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">uint8_t</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a8cd6a25da092fd8df2a10ee85ad9a205">RegF</a> () const</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">uint8_t</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a5ddacd1c8f5c8801661645993a93d86e">RegI</a> () const</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">bool</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a9a1120221dcf9499e5955c51723d234d">H</a> () const</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">uint8_t</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#aca7df18b795124b3650184ed28b70e73">CR</a> () const</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">uint16_t</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#acbb19bbf197b52835ec97eb53c05de20">FrameSize</a> () const</td>
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

## Public Member Attributes Index

<table class="doxyMembersIndex">

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/namespaces/llvm/support/#a206b37274fa3e908017da357d12724d1">support::ulittle32_t</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a70385f8825067ba3525ae385b9406cb8">BeginAddress</a></td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/namespaces/llvm/support/#a206b37274fa3e908017da357d12724d1">support::ulittle32_t</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ac0b03cf027cd06833ae7467bbd8b5f29">UnwindData</a></td>
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

<p><a href="/web-llvm/docs/api/classes/llvm/arm/wineh/runtimefunctionarm64">RuntimeFunctionARM64</a> - An entry in the table of procedure data (.pdata)</p>


<p>3 3 2 2 2 2 2 2 2 2 2 2 1 1 1 1 1 1 1 1 1 1 0 0 0 0 0 0 0 0 0 0 1 0 9 8 7 6 5 4 3 2 1 0 9 8 7 6 5 4 3 2 1 0 9 8 7 6 5 4 3 2 1 0 +------------------------------------------------------------—+ | <a href="/web-llvm/docs/api/classes/llvm/function">Function</a> Start RVA | +--------------—+—+-+----—+--—+------------------—+—+ | Frame Size |CR |H| RegI |RegF | <a href="/web-llvm/docs/api/classes/llvm/function">Function</a> Length |Flg| +--------------—+—+-+----—+--—+------------------—+—+</p>


<p>See <a href="https://docs.microsoft.com/en-us/cpp/build/arm64-exception-handling">https://docs.microsoft.com/en-us/cpp/build/arm64-exception-handling</a> for the full reference for this struct.</p>


<p>Definition at line 224 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/support/armwineh-h">ARMWinEH.h</a>.</p>


<div class="doxySectionDef">

## Public Constructors

### RuntimeFunctionARM64() {#a0dc094bdfb506dc8ee0dd934834f569f}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">llvm::ARM::WinEH::RuntimeFunctionARM64::RuntimeFunctionARM64 (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/namespaces/llvm/support/#a206b37274fa3e908017da357d12724d1">support::ulittle32_t</a> * Data)</td>
</tr>
</table>
</td>
<td class="doxyMemberLabelsRight">
<span class="doxyMemberLabels">
<span class="doxyMemberLabel inline">inline</span>
</span>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 229 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/support/armwineh-h">ARMWinEH.h</a>.</p>


<p>References <a href="#a70385f8825067ba3525ae385b9406cb8">BeginAddress</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#aa20539e89704d20b98b97e9c3feac934">llvm::Data</a> and <a href="#ac0b03cf027cd06833ae7467bbd8b5f29">UnwindData</a>.</p>

</div>
</div>

### RuntimeFunctionARM64() {#a4673cc53656da8df66cdad97dd8648c0}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">llvm::ARM::WinEH::RuntimeFunctionARM64::RuntimeFunctionARM64 (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/namespaces/llvm/support/#a206b37274fa3e908017da357d12724d1">support::ulittle32_t</a> BeginAddress, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/namespaces/llvm/support/#a206b37274fa3e908017da357d12724d1">support::ulittle32_t</a> UnwindData)</td>
</tr>
</table>
</td>
<td class="doxyMemberLabelsRight">
<span class="doxyMemberLabels">
<span class="doxyMemberLabel inline">inline</span>
</span>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 232 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/support/armwineh-h">ARMWinEH.h</a>.</p>


<p>References <a href="#a70385f8825067ba3525ae385b9406cb8">BeginAddress</a> and <a href="#ac0b03cf027cd06833ae7467bbd8b5f29">UnwindData</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Public Member Functions

### CR() {#aca7df18b795124b3650184ed28b70e73}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">uint8_t llvm::ARM::WinEH::RuntimeFunctionARM64::CR ()</td>
</tr>
</table>
</td>
<td class="doxyMemberLabelsRight">
<span class="doxyMemberLabels">
<span class="doxyMemberLabel inline">inline</span>
</span>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 276 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/support/armwineh-h">ARMWinEH.h</a>.</p>


<p>References <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/silowercontrolflow-cpp/#a4868c5d81c5ccc98c47aeab6244346a0">assert</a>, <a href="#ad1f3a592c7416aae13ed4b680f83cd13">Flag</a>, <a href="/web-llvm/docs/api/namespaces/llvm/arm/wineh/#a42eec988a426045927f9b40043dad476aed0bc398a2fccf46725c2636f9f875ee">llvm::ARM::WinEH::RFF_Packed</a>, <a href="/web-llvm/docs/api/namespaces/llvm/arm/wineh/#a42eec988a426045927f9b40043dad476afbbe066bebad303d6ba46102bc525a6b">llvm::ARM::WinEH::RFF_PackedFragment</a> and <a href="#ac0b03cf027cd06833ae7467bbd8b5f29">UnwindData</a>.</p>

</div>
</div>

### ExceptionInformationRVA() {#a7bd7b8b4c0172b2019f66ba3dd346d66}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">uint32_t llvm::ARM::WinEH::RuntimeFunctionARM64::ExceptionInformationRVA ()</td>
</tr>
</table>
</td>
<td class="doxyMemberLabelsRight">
<span class="doxyMemberLabels">
<span class="doxyMemberLabel inline">inline</span>
</span>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 240 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/support/armwineh-h">ARMWinEH.h</a>.</p>


<p>References <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/silowercontrolflow-cpp/#a4868c5d81c5ccc98c47aeab6244346a0">assert</a>, <a href="#ad1f3a592c7416aae13ed4b680f83cd13">Flag</a>, <a href="/web-llvm/docs/api/namespaces/llvm/arm/wineh/#a42eec988a426045927f9b40043dad476af5a03e381d3bd0eabef74975876a2670">llvm::ARM::WinEH::RFF_Unpacked</a> and <a href="#ac0b03cf027cd06833ae7467bbd8b5f29">UnwindData</a>.</p>

</div>
</div>

### Flag() {#ad1f3a592c7416aae13ed4b680f83cd13}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">RuntimeFunctionFlag llvm::ARM::WinEH::RuntimeFunctionARM64::Flag ()</td>
</tr>
</table>
</td>
<td class="doxyMemberLabelsRight">
<span class="doxyMemberLabels">
<span class="doxyMemberLabel inline">inline</span>
</span>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 236 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/support/armwineh-h">ARMWinEH.h</a>.</p>


<p>Reference <a href="#ac0b03cf027cd06833ae7467bbd8b5f29">UnwindData</a>.</p>


<p>Referenced by <a href="#aca7df18b795124b3650184ed28b70e73">CR</a>, <a href="#a7bd7b8b4c0172b2019f66ba3dd346d66">ExceptionInformationRVA</a>, <a href="#acbb19bbf197b52835ec97eb53c05de20">FrameSize</a>, <a href="#a5ef74e462393cd85864949453f4612ff">FunctionLength</a>, <a href="#a9a1120221dcf9499e5955c51723d234d">H</a>, <a href="#a237ce46af95d080421995cb4ddf02fef">PackedUnwindData</a>, <a href="#a8cd6a25da092fd8df2a10ee85ad9a205">RegF</a> and <a href="#a5ddacd1c8f5c8801661645993a93d86e">RegI</a>.</p>

</div>
</div>

### FrameSize() {#acbb19bbf197b52835ec97eb53c05de20}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">uint16_t llvm::ARM::WinEH::RuntimeFunctionARM64::FrameSize ()</td>
</tr>
</table>
</td>
<td class="doxyMemberLabelsRight">
<span class="doxyMemberLabels">
<span class="doxyMemberLabel inline">inline</span>
</span>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 282 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/support/armwineh-h">ARMWinEH.h</a>.</p>


<p>References <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/silowercontrolflow-cpp/#a4868c5d81c5ccc98c47aeab6244346a0">assert</a>, <a href="#ad1f3a592c7416aae13ed4b680f83cd13">Flag</a>, <a href="/web-llvm/docs/api/namespaces/llvm/arm/wineh/#a42eec988a426045927f9b40043dad476aed0bc398a2fccf46725c2636f9f875ee">llvm::ARM::WinEH::RFF_Packed</a>, <a href="/web-llvm/docs/api/namespaces/llvm/arm/wineh/#a42eec988a426045927f9b40043dad476afbbe066bebad303d6ba46102bc525a6b">llvm::ARM::WinEH::RFF_PackedFragment</a> and <a href="#ac0b03cf027cd06833ae7467bbd8b5f29">UnwindData</a>.</p>

</div>
</div>

### FunctionLength() {#a5ef74e462393cd85864949453f4612ff}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">uint32_t llvm::ARM::WinEH::RuntimeFunctionARM64::FunctionLength ()</td>
</tr>
</table>
</td>
<td class="doxyMemberLabelsRight">
<span class="doxyMemberLabels">
<span class="doxyMemberLabel inline">inline</span>
</span>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 252 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/support/armwineh-h">ARMWinEH.h</a>.</p>


<p>References <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/silowercontrolflow-cpp/#a4868c5d81c5ccc98c47aeab6244346a0">assert</a>, <a href="#ad1f3a592c7416aae13ed4b680f83cd13">Flag</a>, <a href="/web-llvm/docs/api/namespaces/llvm/arm/wineh/#a42eec988a426045927f9b40043dad476aed0bc398a2fccf46725c2636f9f875ee">llvm::ARM::WinEH::RFF_Packed</a>, <a href="/web-llvm/docs/api/namespaces/llvm/arm/wineh/#a42eec988a426045927f9b40043dad476afbbe066bebad303d6ba46102bc525a6b">llvm::ARM::WinEH::RFF_PackedFragment</a> and <a href="#ac0b03cf027cd06833ae7467bbd8b5f29">UnwindData</a>.</p>

</div>
</div>

### H() {#a9a1120221dcf9499e5955c51723d234d}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool llvm::ARM::WinEH::RuntimeFunctionARM64::H ()</td>
</tr>
</table>
</td>
<td class="doxyMemberLabelsRight">
<span class="doxyMemberLabels">
<span class="doxyMemberLabel inline">inline</span>
</span>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 270 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/support/armwineh-h">ARMWinEH.h</a>.</p>


<p>References <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/silowercontrolflow-cpp/#a4868c5d81c5ccc98c47aeab6244346a0">assert</a>, <a href="#ad1f3a592c7416aae13ed4b680f83cd13">Flag</a>, <a href="/web-llvm/docs/api/namespaces/llvm/arm/wineh/#a42eec988a426045927f9b40043dad476aed0bc398a2fccf46725c2636f9f875ee">llvm::ARM::WinEH::RFF_Packed</a>, <a href="/web-llvm/docs/api/namespaces/llvm/arm/wineh/#a42eec988a426045927f9b40043dad476afbbe066bebad303d6ba46102bc525a6b">llvm::ARM::WinEH::RFF_PackedFragment</a> and <a href="#ac0b03cf027cd06833ae7467bbd8b5f29">UnwindData</a>.</p>

</div>
</div>

### PackedUnwindData() {#a237ce46af95d080421995cb4ddf02fef}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">uint32_t llvm::ARM::WinEH::RuntimeFunctionARM64::PackedUnwindData ()</td>
</tr>
</table>
</td>
<td class="doxyMemberLabelsRight">
<span class="doxyMemberLabels">
<span class="doxyMemberLabel inline">inline</span>
</span>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 246 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/support/armwineh-h">ARMWinEH.h</a>.</p>


<p>References <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/silowercontrolflow-cpp/#a4868c5d81c5ccc98c47aeab6244346a0">assert</a>, <a href="#ad1f3a592c7416aae13ed4b680f83cd13">Flag</a>, <a href="/web-llvm/docs/api/namespaces/llvm/arm/wineh/#a42eec988a426045927f9b40043dad476aed0bc398a2fccf46725c2636f9f875ee">llvm::ARM::WinEH::RFF_Packed</a>, <a href="/web-llvm/docs/api/namespaces/llvm/arm/wineh/#a42eec988a426045927f9b40043dad476afbbe066bebad303d6ba46102bc525a6b">llvm::ARM::WinEH::RFF_PackedFragment</a> and <a href="#ac0b03cf027cd06833ae7467bbd8b5f29">UnwindData</a>.</p>

</div>
</div>

### RegF() {#a8cd6a25da092fd8df2a10ee85ad9a205}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">uint8_t llvm::ARM::WinEH::RuntimeFunctionARM64::RegF ()</td>
</tr>
</table>
</td>
<td class="doxyMemberLabelsRight">
<span class="doxyMemberLabels">
<span class="doxyMemberLabel inline">inline</span>
</span>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 258 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/support/armwineh-h">ARMWinEH.h</a>.</p>


<p>References <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/silowercontrolflow-cpp/#a4868c5d81c5ccc98c47aeab6244346a0">assert</a>, <a href="#ad1f3a592c7416aae13ed4b680f83cd13">Flag</a>, <a href="/web-llvm/docs/api/namespaces/llvm/arm/wineh/#a42eec988a426045927f9b40043dad476aed0bc398a2fccf46725c2636f9f875ee">llvm::ARM::WinEH::RFF_Packed</a>, <a href="/web-llvm/docs/api/namespaces/llvm/arm/wineh/#a42eec988a426045927f9b40043dad476afbbe066bebad303d6ba46102bc525a6b">llvm::ARM::WinEH::RFF_PackedFragment</a> and <a href="#ac0b03cf027cd06833ae7467bbd8b5f29">UnwindData</a>.</p>

</div>
</div>

### RegI() {#a5ddacd1c8f5c8801661645993a93d86e}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">uint8_t llvm::ARM::WinEH::RuntimeFunctionARM64::RegI ()</td>
</tr>
</table>
</td>
<td class="doxyMemberLabelsRight">
<span class="doxyMemberLabels">
<span class="doxyMemberLabel inline">inline</span>
</span>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 264 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/support/armwineh-h">ARMWinEH.h</a>.</p>


<p>References <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/silowercontrolflow-cpp/#a4868c5d81c5ccc98c47aeab6244346a0">assert</a>, <a href="#ad1f3a592c7416aae13ed4b680f83cd13">Flag</a>, <a href="/web-llvm/docs/api/namespaces/llvm/arm/wineh/#a42eec988a426045927f9b40043dad476aed0bc398a2fccf46725c2636f9f875ee">llvm::ARM::WinEH::RFF_Packed</a>, <a href="/web-llvm/docs/api/namespaces/llvm/arm/wineh/#a42eec988a426045927f9b40043dad476afbbe066bebad303d6ba46102bc525a6b">llvm::ARM::WinEH::RFF_PackedFragment</a> and <a href="#ac0b03cf027cd06833ae7467bbd8b5f29">UnwindData</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Public Member Attributes

### BeginAddress {#a70385f8825067ba3525ae385b9406cb8}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">const support::ulittle32_t llvm::ARM::WinEH::RuntimeFunctionARM64::BeginAddress</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 226 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/support/armwineh-h">ARMWinEH.h</a>.</p>


<p>Referenced by <a href="#a0dc094bdfb506dc8ee0dd934834f569f">RuntimeFunctionARM64</a> and <a href="#a4673cc53656da8df66cdad97dd8648c0">RuntimeFunctionARM64</a>.</p>

</div>
</div>

### UnwindData {#ac0b03cf027cd06833ae7467bbd8b5f29}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">const support::ulittle32_t llvm::ARM::WinEH::RuntimeFunctionARM64::UnwindData</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 227 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/support/armwineh-h">ARMWinEH.h</a>.</p>


<p>Referenced by <a href="#aca7df18b795124b3650184ed28b70e73">CR</a>, <a href="#a7bd7b8b4c0172b2019f66ba3dd346d66">ExceptionInformationRVA</a>, <a href="#ad1f3a592c7416aae13ed4b680f83cd13">Flag</a>, <a href="#acbb19bbf197b52835ec97eb53c05de20">FrameSize</a>, <a href="#a5ef74e462393cd85864949453f4612ff">FunctionLength</a>, <a href="#a9a1120221dcf9499e5955c51723d234d">H</a>, <a href="#a237ce46af95d080421995cb4ddf02fef">PackedUnwindData</a>, <a href="#a8cd6a25da092fd8df2a10ee85ad9a205">RegF</a>, <a href="#a5ddacd1c8f5c8801661645993a93d86e">RegI</a>, <a href="#a0dc094bdfb506dc8ee0dd934834f569f">RuntimeFunctionARM64</a> and <a href="#a4673cc53656da8df66cdad97dd8648c0">RuntimeFunctionARM64</a>.</p>

</div>
</div>

</div>

<hr/>

The documentation for this class was generated from the following file:

<ul>
<li><a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/support/armwineh-h">ARMWinEH.h</a></li>
</ul>

<hr/>

<p class="doxyGeneratedBy">Generated via <a href="https://github.com/xpack/doxygen2docusaurus">doxygen2docusaurus</a> by <a href="https://www.doxygen.nl">Doxygen</a> 1.15.0.</p>

</div>
