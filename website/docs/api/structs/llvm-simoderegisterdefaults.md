---

# DO NOT EDIT!
# Automatically generated via doxygen2docusaurus by Doxygen.

slug: /api/structs/llvm/simoderegisterdefaults
custom_edit_url: null
toc_max_heading_level: 4
keywords:
  - doxygen
  - reference
  - struct

---

<div class="doxyPage">

# `SIModeRegisterDefaults` Struct



## Declaration

<div class="doxyDeclaration">
struct llvm::SIModeRegisterDefaults { ... }
</div>

## Included Headers

<div class="doxyIncludesList">#include "<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/simoderegisterdefaults-h">Target/AMDGPU/SIModeRegisterDefaults.h</a>"
</div>

## Public Constructors Index

<table class="doxyMembersIndex">

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a5c51e7c717aeeb4ea130f6a95f8d7d6a">SIModeRegisterDefaults</a> ()</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ad34c639c525fbb1dc22558683559f46d">SIModeRegisterDefaults</a> (const Function &amp;F, const GCNSubtarget &amp;ST)</td>
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

## Public Operators Index

<table class="doxyMembersIndex">

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">bool</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ada223cd35c40f958ac1f70c1d0fd60ef">operator==</a> (const SIModeRegisterDefaults Other) const</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">uint32_t</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a6590b6137a9fe659ad1ba3b2387b4cbd">fpDenormModeSPValue</a> () const</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Get the encoding value for the FP_DENORM bits of the mode register for the FP32 denormal mode. <a href="#a6590b6137a9fe659ad1ba3b2387b4cbd">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">uint32_t</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a98055d81c972ca478d57d2b1a871ecd9">fpDenormModeDPValue</a> () const</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Get the encoding value for the FP_DENORM bits of the mode register for the FP64/FP16 denormal mode. <a href="#a98055d81c972ca478d57d2b1a871ecd9">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">bool</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#abdddc79ec28eda713a19458d04d46fd6">isInlineCompatible</a> (SIModeRegisterDefaults CalleeMode) const</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">bool</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a7238526aeceaef9a0db1ab0c21a0cf0e">IEEE</a></td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Floating point opcodes that support exception flag gathering quiet and propagate signaling NaN inputs per IEEE 754-2008. <a href="#a7238526aeceaef9a0db1ab0c21a0cf0e">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">bool</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a5eff9b4ca99cdc0544e946f36ba98458">DX10Clamp</a></td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Used by the vector ALU to force DX10-style treatment of NaNs: when set, clamp NaN to zero; otherwise, pass NaN through. <a href="#a5eff9b4ca99cdc0544e946f36ba98458">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/structs/llvm/denormalmode">DenormalMode</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#af1d0653d028bac2c78f7eec72f32472e">FP32Denormals</a></td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>If this is set, neither input or output denormals are flushed for most f32 instructions. <a href="#af1d0653d028bac2c78f7eec72f32472e">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/structs/llvm/denormalmode">DenormalMode</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a69743300b37bda17c4cf7690f2dc2fac">FP64FP16Denormals</a></td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>If this is set, neither input or output denormals are flushed for both f64 and f16/v2f16 instructions. <a href="#a69743300b37bda17c4cf7690f2dc2fac">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

</table>

## Public Static Functions Index

<table class="doxyMembersIndex">

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">static <a href="/web-llvm/docs/api/structs/llvm/simoderegisterdefaults">SIModeRegisterDefaults</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a785285b13b67a380426876b52ae4d811">getDefaultForCallingConv</a> (CallingConv::ID CC)</td>
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


<p>Definition at line 20 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/simoderegisterdefaults-h">SIModeRegisterDefaults.h</a>.</p>


<div class="doxySectionDef">

## Public Constructors

### SIModeRegisterDefaults() {#a5c51e7c717aeeb4ea130f6a95f8d7d6a}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">llvm::SIModeRegisterDefaults::SIModeRegisterDefaults ()</td>
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



<p>Definition at line 39 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/simoderegisterdefaults-h">SIModeRegisterDefaults.h</a>.</p>


<p>References <a href="#a5eff9b4ca99cdc0544e946f36ba98458">DX10Clamp</a>, <a href="#af1d0653d028bac2c78f7eec72f32472e">FP32Denormals</a>, <a href="#a69743300b37bda17c4cf7690f2dc2fac">FP64FP16Denormals</a>, <a href="#a7238526aeceaef9a0db1ab0c21a0cf0e">IEEE</a> and <a href="/web-llvm/docs/api/files/lib/lib/analysis/basicaliasanalysis-cpp/#af6d5cafbdfc5313e65d990120021a3ec">true</a>.</p>


<p>Referenced by <a href="#a785285b13b67a380426876b52ae4d811">getDefaultForCallingConv</a>, <a href="#abdddc79ec28eda713a19458d04d46fd6">isInlineCompatible</a> and <a href="#ada223cd35c40f958ac1f70c1d0fd60ef">operator==</a>.</p>

</div>
</div>

### SIModeRegisterDefaults() {#ad34c639c525fbb1dc22558683559f46d}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">SIModeRegisterDefaults::SIModeRegisterDefaults (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/function">Function</a> &amp; F, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/gcnsubtarget">GCNSubtarget</a> &amp; ST)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Declaration at line 45 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/simoderegisterdefaults-h">SIModeRegisterDefaults.h</a>, definition at line 14 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/simoderegisterdefaults-cpp">SIModeRegisterDefaults.cpp</a>.</p>


<p>References <a href="#a5eff9b4ca99cdc0544e946f36ba98458">DX10Clamp</a>, <a href="/web-llvm/docs/api/classes/llvm/stringref/#a2dc80c585ad5882da8cae7b5968f7e74">llvm::StringRef::empty</a>, <a href="/web-llvm/docs/api/files/lib/lib/support/md5-cpp/#a96d73bbd7af15cb1fc38c3f4a3bd82e9">F</a>, <a href="#af1d0653d028bac2c78f7eec72f32472e">FP32Denormals</a>, <a href="#a69743300b37bda17c4cf7690f2dc2fac">FP64FP16Denormals</a>, <a href="#a785285b13b67a380426876b52ae4d811">getDefaultForCallingConv</a>, <a href="#a7238526aeceaef9a0db1ab0c21a0cf0e">IEEE</a> and <a href="/web-llvm/docs/api/namespaces/llvm/#ac3b7e007d72635d0f8c320a122f71947">llvm::parseDenormalFPAttribute</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Public Operators

### operator==() {#ada223cd35c40f958ac1f70c1d0fd60ef}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool llvm::SIModeRegisterDefaults::operator== (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/structs/llvm/simoderegisterdefaults">SIModeRegisterDefaults</a> Other)</td>
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



<p>Definition at line 53 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/simoderegisterdefaults-h">SIModeRegisterDefaults.h</a>.</p>


<p>References <a href="#a5eff9b4ca99cdc0544e946f36ba98458">DX10Clamp</a>, <a href="#af1d0653d028bac2c78f7eec72f32472e">FP32Denormals</a>, <a href="#a69743300b37bda17c4cf7690f2dc2fac">FP64FP16Denormals</a>, <a href="#a7238526aeceaef9a0db1ab0c21a0cf0e">IEEE</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a9eb4f5b98b70ee4fab9614ed58282c1fa6311ae17c1ee52b36e68aaf4ad066387">llvm::Other</a> and <a href="#a5c51e7c717aeeb4ea130f6a95f8d7d6a">SIModeRegisterDefaults</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Public Member Functions

### fpDenormModeDPValue() {#a98055d81c972ca478d57d2b1a871ecd9}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">uint32_t llvm::SIModeRegisterDefaults::fpDenormModeDPValue ()</td>
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

<p>Get the encoding value for the FP_DENORM bits of the mode register for the FP64/FP16 denormal mode.</p>

<p>Definition at line 73 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/simoderegisterdefaults-h">SIModeRegisterDefaults.h</a>.</p>


<p>References <a href="#a69743300b37bda17c4cf7690f2dc2fac">FP64FP16Denormals</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/sidefines-h/#ab15f612878863c5bd138b803fa1c1419">FP_DENORM_FLUSH_IN</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/sidefines-h/#a97400ab52a53a0ee0adbaff0ae0f63e5">FP_DENORM_FLUSH_IN_FLUSH_OUT</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/sidefines-h/#a794476833214d5191d905cb35da453a8">FP_DENORM_FLUSH_NONE</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/sidefines-h/#a0fac6d4c330d9dff100bc9b62ba9f2a5">FP_DENORM_FLUSH_OUT</a>, <a href="/web-llvm/docs/api/structs/llvm/denormalmode/#a8b25a485fab5c4ade966d2ad73bc2ccf">llvm::DenormalMode::getPreserveSign</a> and <a href="/web-llvm/docs/api/structs/llvm/denormalmode/#a29b26e3ae30f3f6ec4106ff181282893a40bc80ae1d362a1461703637e946cbd8">llvm::DenormalMode::PreserveSign</a>.</p>

</div>
</div>

### fpDenormModeSPValue() {#a6590b6137a9fe659ad1ba3b2387b4cbd}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">uint32_t llvm::SIModeRegisterDefaults::fpDenormModeSPValue ()</td>
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

<p>Get the encoding value for the FP_DENORM bits of the mode register for the FP32 denormal mode.</p>

<p>Definition at line 61 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/simoderegisterdefaults-h">SIModeRegisterDefaults.h</a>.</p>


<p>References <a href="#af1d0653d028bac2c78f7eec72f32472e">FP32Denormals</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/sidefines-h/#ab15f612878863c5bd138b803fa1c1419">FP_DENORM_FLUSH_IN</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/sidefines-h/#a97400ab52a53a0ee0adbaff0ae0f63e5">FP_DENORM_FLUSH_IN_FLUSH_OUT</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/sidefines-h/#a794476833214d5191d905cb35da453a8">FP_DENORM_FLUSH_NONE</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/sidefines-h/#a0fac6d4c330d9dff100bc9b62ba9f2a5">FP_DENORM_FLUSH_OUT</a>, <a href="/web-llvm/docs/api/structs/llvm/denormalmode/#a8b25a485fab5c4ade966d2ad73bc2ccf">llvm::DenormalMode::getPreserveSign</a> and <a href="/web-llvm/docs/api/structs/llvm/denormalmode/#a29b26e3ae30f3f6ec4106ff181282893a40bc80ae1d362a1461703637e946cbd8">llvm::DenormalMode::PreserveSign</a>.</p>

</div>
</div>

### isInlineCompatible() {#abdddc79ec28eda713a19458d04d46fd6}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool llvm::SIModeRegisterDefaults::isInlineCompatible (<a href="/web-llvm/docs/api/structs/llvm/simoderegisterdefaults">SIModeRegisterDefaults</a> CalleeMode)</td>
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



<p>Definition at line 85 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/simoderegisterdefaults-h">SIModeRegisterDefaults.h</a>.</p>


<p>References <a href="#a5eff9b4ca99cdc0544e946f36ba98458">DX10Clamp</a>, <a href="#a7238526aeceaef9a0db1ab0c21a0cf0e">IEEE</a> and <a href="#a5c51e7c717aeeb4ea130f6a95f8d7d6a">SIModeRegisterDefaults</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/classes/llvm/gcnttiimpl/#ab22e771266e47d5314bdf2eb148bac1f">llvm::GCNTTIImpl::areInlineCompatible</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Public Member Attributes

### DX10Clamp {#a5eff9b4ca99cdc0544e946f36ba98458}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool llvm::SIModeRegisterDefaults::DX10Clamp</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Used by the vector ALU to force DX10-style treatment of NaNs: when set, clamp NaN to zero; otherwise, pass NaN through.</p>

<p>Definition at line 29 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/simoderegisterdefaults-h">SIModeRegisterDefaults.h</a>.</p>


<p>Referenced by <a href="#abdddc79ec28eda713a19458d04d46fd6">isInlineCompatible</a>, <a href="#ada223cd35c40f958ac1f70c1d0fd60ef">operator==</a>, <a href="/web-llvm/docs/api/classes/llvm/gcntargetmachine/#a546e4834a3dc92d96ef8b7598f552a45">llvm::GCNTargetMachine::parseMachineFunctionInfo</a>, <a href="#a5c51e7c717aeeb4ea130f6a95f8d7d6a">SIModeRegisterDefaults</a> and <a href="#ad34c639c525fbb1dc22558683559f46d">SIModeRegisterDefaults</a>.</p>

</div>
</div>

### FP32Denormals {#af1d0653d028bac2c78f7eec72f32472e}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">DenormalMode llvm::SIModeRegisterDefaults::FP32Denormals</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>If this is set, neither input or output denormals are flushed for most f32 instructions.</p>

<p>Definition at line 33 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/simoderegisterdefaults-h">SIModeRegisterDefaults.h</a>.</p>


<p>Referenced by <a href="#a6590b6137a9fe659ad1ba3b2387b4cbd">fpDenormModeSPValue</a>, <a href="/web-llvm/docs/api/classes/llvm/amdgpulegalizerinfo/#a4774d239d20e55380840e775aed66efc">llvm::AMDGPULegalizerInfo::legalizeFMad</a>, <a href="/web-llvm/docs/api/classes/llvm/amdgputargetlowering/#a6f30e11353716cf175b1fb59b11cb6f4">llvm::AMDGPUTargetLowering::LowerDIVREM24</a>, <a href="/web-llvm/docs/api/classes/llvm/amdgputargetlowering/#aec76b73c15365e949f7322e371e6471b">llvm::AMDGPUTargetLowering::LowerUDIVREM64</a>, <a href="#ada223cd35c40f958ac1f70c1d0fd60ef">operator==</a>, <a href="/web-llvm/docs/api/classes/llvm/gcntargetmachine/#a546e4834a3dc92d96ef8b7598f552a45">llvm::GCNTargetMachine::parseMachineFunctionInfo</a>, <a href="#a5c51e7c717aeeb4ea130f6a95f8d7d6a">SIModeRegisterDefaults</a> and <a href="#ad34c639c525fbb1dc22558683559f46d">SIModeRegisterDefaults</a>.</p>

</div>
</div>

### FP64FP16Denormals {#a69743300b37bda17c4cf7690f2dc2fac}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">DenormalMode llvm::SIModeRegisterDefaults::FP64FP16Denormals</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>If this is set, neither input or output denormals are flushed for both f64 and f16/v2f16 instructions.</p>

<p>Definition at line 37 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/simoderegisterdefaults-h">SIModeRegisterDefaults.h</a>.</p>


<p>Referenced by <a href="#a98055d81c972ca478d57d2b1a871ecd9">fpDenormModeDPValue</a>, <a href="/web-llvm/docs/api/classes/llvm/amdgpulegalizerinfo/#a4774d239d20e55380840e775aed66efc">llvm::AMDGPULegalizerInfo::legalizeFMad</a>, <a href="#ada223cd35c40f958ac1f70c1d0fd60ef">operator==</a>, <a href="/web-llvm/docs/api/classes/llvm/gcntargetmachine/#a546e4834a3dc92d96ef8b7598f552a45">llvm::GCNTargetMachine::parseMachineFunctionInfo</a>, <a href="#a5c51e7c717aeeb4ea130f6a95f8d7d6a">SIModeRegisterDefaults</a> and <a href="#ad34c639c525fbb1dc22558683559f46d">SIModeRegisterDefaults</a>.</p>

</div>
</div>

### IEEE {#a7238526aeceaef9a0db1ab0c21a0cf0e}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool llvm::SIModeRegisterDefaults::IEEE</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Floating point opcodes that support exception flag gathering quiet and propagate signaling NaN inputs per IEEE 754-2008.</p>


<p>Min_dx10 and max_dx10 become IEEE 754- 2008 compliant due to signaling NaN propagation and quieting.</p>


<p>Definition at line 25 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/simoderegisterdefaults-h">SIModeRegisterDefaults.h</a>.</p>


<p>Referenced by <a href="#abdddc79ec28eda713a19458d04d46fd6">isInlineCompatible</a>, <a href="/web-llvm/docs/api/classes/llvm/amdgpulegalizerinfo/#a44186e632d4bab1d35012ed738a23870">llvm::AMDGPULegalizerInfo::legalizeFFloor</a>, <a href="/web-llvm/docs/api/classes/llvm/amdgpulegalizerinfo/#a91b85787aa32d7f1f0d38d59a77cee68">llvm::AMDGPULegalizerInfo::legalizeMinNumMaxNum</a>, <a href="/web-llvm/docs/api/classes/llvm/amdgpulegalizerinfo/#a68b29f4aff8a6db0040bc8e00a520116">llvm::AMDGPULegalizerInfo::legalizeRsqClampIntrinsic</a>, <a href="#ada223cd35c40f958ac1f70c1d0fd60ef">operator==</a>, <a href="/web-llvm/docs/api/classes/llvm/gcntargetmachine/#a546e4834a3dc92d96ef8b7598f552a45">llvm::GCNTargetMachine::parseMachineFunctionInfo</a>, <a href="#a5c51e7c717aeeb4ea130f6a95f8d7d6a">SIModeRegisterDefaults</a> and <a href="#ad34c639c525fbb1dc22558683559f46d">SIModeRegisterDefaults</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Public Static Functions

### getDefaultForCallingConv() {#a785285b13b67a380426876b52ae4d811}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">SIModeRegisterDefaults llvm::SIModeRegisterDefaults::getDefaultForCallingConv (<a href="/web-llvm/docs/api/namespaces/llvm/callingconv/#abdf8cf606905c10634e831390981b0ed">CallingConv::ID</a> CC)</td>
</tr>
</table>
</td>
<td class="doxyMemberLabelsRight">
<span class="doxyMemberLabels">
<span class="doxyMemberLabel inline">inline</span>
<span class="doxyMemberLabel static">static</span>
</span>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 47 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/simoderegisterdefaults-h">SIModeRegisterDefaults.h</a>.</p>


<p>References <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/riscv/riscvredundantcopyelimination-cpp/#a77c69067ae8279bc00ab8757731e90d7">CC</a>, <a href="/web-llvm/docs/api/namespaces/llvm/amdgpu/#aa813940c0ad88b3c4419f65af3e89e5e">llvm::AMDGPU::isShader</a>, <a href="/web-llvm/docs/api/files/lib/lib/codegen/regallocevictionadvisor-cpp/#aef71c4b21823f236e70cc6d62375adcd">Mode</a> and <a href="#a5c51e7c717aeeb4ea130f6a95f8d7d6a">SIModeRegisterDefaults</a>.</p>


<p>Referenced by <a href="#ad34c639c525fbb1dc22558683559f46d">SIModeRegisterDefaults</a>.</p>

</div>
</div>

</div>

<hr/>

The documentation for this struct was generated from the following files:

<ul>
<li><a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/simoderegisterdefaults-cpp">SIModeRegisterDefaults.cpp</a></li>
<li><a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/simoderegisterdefaults-h">SIModeRegisterDefaults.h</a></li>
</ul>

<hr/>

<p class="doxyGeneratedBy">Generated via <a href="https://github.com/xpack/doxygen2docusaurus">doxygen2docusaurus</a> by <a href="https://www.doxygen.nl">Doxygen</a> 1.15.0.</p>

</div>
