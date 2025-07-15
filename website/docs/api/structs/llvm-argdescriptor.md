---

# DO NOT EDIT!
# Automatically generated via doxygen2docusaurus by Doxygen.

slug: /api/structs/llvm/argdescriptor
custom_edit_url: null
toc_max_heading_level: 4
keywords:
  - doxygen
  - reference
  - struct

---

<div class="doxyPage">

# The `ArgDescriptor` Struct Reference



## Declaration

<div class="doxyDeclaration">
struct llvm::ArgDescriptor { ... }
</div>

## Included Headers

<div class="doxyIncludesList">#include "<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/amdgpuargumentusageinfo-h">Target/AMDGPU/AMDGPUArgumentUsageInfo.h</a>"
</div>

## Derived Structs

<table class="doxyMembersIndex">

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">struct</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="/web-llvm/docs/api/structs/llvm/kernargpreloaddescriptor">KernArgPreloadDescriptor</a></td>
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

## Friends Index

<table class="doxyMembersIndex">

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">struct</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a1fa30b3771a6fa6e61ee2ddef996c943">AMDGPUFunctionArgInfo</a></td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a9372aacf8826c6530439c62695398383">AMDGPUArgumentUsageInfo</a></td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#af8187cceb10a89808f79bbf15136df5d">ArgDescriptor</a> (unsigned Val=0, unsigned Mask=~0u, bool IsStack=false, bool IsSet=false)</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#affbc06542a43694e5f1b9395247aeb76">operator bool</a> () const</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">bool</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ab23237108d60cd63ae0772d377c6adf4">isSet</a> () const</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a523f3df17ae0b64f7d35d4caad3a54cc">isRegister</a> () const</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/mcregister">MCRegister</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a2ee87af66bd7eee85e5a7baabe20afe3">getRegister</a> () const</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">unsigned</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#abbadb717106b06e0a4bd9555e53663d4">getStackOffset</a> () const</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">unsigned</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#aca6660bcd84fca6d680694ff0c78893d">getMask</a> () const</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#aa9bfb4bb223ce3b720ec0ff7260bce95">isMasked</a> () const</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">void</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a96a608070d394c15c847e9a52e250c1c">print</a> (raw_ostream &amp;OS, const TargetRegisterInfo *TRI=nullptr) const</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/mcregister">MCRegister</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a54655386a49ce4e122c806d11156bf85">Reg</a></td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">unsigned</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ab3eea14feb0c5674b5d437c67284fc0b">StackOffset</a></td>
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

## Private Member Attributes Index

<table class="doxyMembersIndex">

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">union <a href="/web-llvm/docs/api/structs/llvm/argdescriptor">llvm::ArgDescriptor</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#abd33404bfb235a49049c9b93ea3838bd"></a></td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">unsigned</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#aa1dd94b8f91c4643ff313ef6e97dedb8">Mask</a></td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a0c9e2c6544bd1d8e6e029a533eeec9ff">IsStack</a></td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#aa289f3e631ee8a1f85a0cfd833cdf190">IsSet</a></td>
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

## Public Static Functions Index

<table class="doxyMembersIndex">

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">static <a href="/web-llvm/docs/api/structs/llvm/argdescriptor">ArgDescriptor</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ab80da72ac9122b5c4e4a0a2cfaa25d9e">createRegister</a> (Register Reg, unsigned Mask=~0u)</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">static <a href="/web-llvm/docs/api/structs/llvm/argdescriptor">ArgDescriptor</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a2b90780a92bdcaed0a47e50d86ec6e6b">createStack</a> (unsigned Offset, unsigned Mask=~0u)</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">static <a href="/web-llvm/docs/api/structs/llvm/argdescriptor">ArgDescriptor</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a5ba9ffd4c829c39d10d780ebd8c55ed9">createArg</a> (const ArgDescriptor &amp;Arg, unsigned Mask)</td>
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


<p>Definition at line 25 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/amdgpuargumentusageinfo-h">AMDGPUArgumentUsageInfo.h</a>.</p>


<div class="doxySectionDef">

## Friends

### AMDGPUArgumentUsageInfo {#a9372aacf8826c6530439c62695398383}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">friend class <a href="/web-llvm/docs/api/classes/llvm/amdgpuargumentusageinfo">AMDGPUArgumentUsageInfo</a></td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">


<p>Definition at line 28 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/amdgpuargumentusageinfo-h">AMDGPUArgumentUsageInfo.h</a>.</p>


<p>Reference <a href="#a9372aacf8826c6530439c62695398383">AMDGPUArgumentUsageInfo</a>.</p>


<p>Referenced by <a href="#a9372aacf8826c6530439c62695398383">AMDGPUArgumentUsageInfo</a>.</p>

</div>
</div>

### AMDGPUFunctionArgInfo {#a1fa30b3771a6fa6e61ee2ddef996c943}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">friend struct <a href="/web-llvm/docs/api/structs/llvm/amdgpufunctionarginfo">AMDGPUFunctionArgInfo</a></td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">


<p>Definition at line 27 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/amdgpuargumentusageinfo-h">AMDGPUArgumentUsageInfo.h</a>.</p>


<p>Reference <a href="#a1fa30b3771a6fa6e61ee2ddef996c943">AMDGPUFunctionArgInfo</a>.</p>


<p>Referenced by <a href="#a1fa30b3771a6fa6e61ee2ddef996c943">AMDGPUFunctionArgInfo</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Public Constructors

### ArgDescriptor() {#af8187cceb10a89808f79bbf15136df5d}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">llvm::ArgDescriptor::ArgDescriptor (unsigned Val=0, unsigned Mask=~0u, bool IsStack=false, bool IsSet=false)</td>
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



<p>Definition at line 42 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/amdgpuargumentusageinfo-h">AMDGPUArgumentUsageInfo.h</a>.</p>


<p>Reference <a href="#a54655386a49ce4e122c806d11156bf85">Reg</a>.</p>


<p>Referenced by <a href="#a5ba9ffd4c829c39d10d780ebd8c55ed9">createArg</a>, <a href="#ab80da72ac9122b5c4e4a0a2cfaa25d9e">createRegister</a> and <a href="#a2b90780a92bdcaed0a47e50d86ec6e6b">createStack</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Public Operators

### operator bool() {#affbc06542a43694e5f1b9395247aeb76}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">llvm::ArgDescriptor::operator bool ()</td>
</tr>
</table>
</td>
<td class="doxyMemberLabelsRight">
<span class="doxyMemberLabels">
<span class="doxyMemberLabel inline">inline</span>
<span class="doxyMemberLabel explicit">explicit</span>
</span>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 62 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/amdgpuargumentusageinfo-h">AMDGPUArgumentUsageInfo.h</a>.</p>


<p>Reference <a href="#ab23237108d60cd63ae0772d377c6adf4">isSet</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Public Member Functions

### getMask() {#aca6660bcd84fca6d680694ff0c78893d}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">unsigned llvm::ArgDescriptor::getMask ()</td>
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



<p>Definition at line 80 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/amdgpuargumentusageinfo-h">AMDGPUArgumentUsageInfo.h</a>.</p>


<p>Reference <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/silowercontrolflow-cpp/#a4868c5d81c5ccc98c47aeab6244346a0">assert</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/classes/llvm/amdgpulegalizerinfo/#ae63198baedfab72494f0d79823e99b75">llvm::AMDGPULegalizerInfo::loadInputValue</a> and <a href="/web-llvm/docs/api/classes/llvm/amdgputargetlowering/#a6e1294084507417fe6404d7b7b9c9471">llvm::AMDGPUTargetLowering::loadInputValue</a>.</p>

</div>
</div>

### getRegister() {#a2ee87af66bd7eee85e5a7baabe20afe3}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">MCRegister llvm::ArgDescriptor::getRegister ()</td>
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



<p>Definition at line 70 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/amdgpuargumentusageinfo-h">AMDGPUArgumentUsageInfo.h</a>.</p>


<p>References <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/silowercontrolflow-cpp/#a4868c5d81c5ccc98c47aeab6244346a0">assert</a> and <a href="#a54655386a49ce4e122c806d11156bf85">Reg</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/siisellowering-cpp/#aa6d8b3f60a0c329bf81effc71e8bb4b4">allocateSGPR32Input</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/siisellowering-cpp/#aff2b0bbccb50fa8a18787acab6f4feee">allocateSGPR64Input</a>, <a href="/web-llvm/docs/api/classes/llvm/amdgpulegalizerinfo/#ae63198baedfab72494f0d79823e99b75">llvm::AMDGPULegalizerInfo::loadInputValue</a>, <a href="/web-llvm/docs/api/classes/llvm/amdgputargetlowering/#a6e1294084507417fe6404d7b7b9c9471">llvm::AMDGPUTargetLowering::loadInputValue</a> and <a href="/web-llvm/docs/api/classes/llvm/amdgpucalllowering/#ac9f5ed1e7ae99c336e8ae9b4ccf10b50">llvm::AMDGPUCallLowering::passSpecialInputs</a>.</p>

</div>
</div>

### getStackOffset() {#abbadb717106b06e0a4bd9555e53663d4}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">unsigned llvm::ArgDescriptor::getStackOffset ()</td>
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



<p>Definition at line 75 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/amdgpuargumentusageinfo-h">AMDGPUArgumentUsageInfo.h</a>.</p>


<p>References <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/silowercontrolflow-cpp/#a4868c5d81c5ccc98c47aeab6244346a0">assert</a> and <a href="#ab3eea14feb0c5674b5d437c67284fc0b">StackOffset</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/classes/llvm/amdgputargetlowering/#a6e1294084507417fe6404d7b7b9c9471">llvm::AMDGPUTargetLowering::loadInputValue</a>.</p>

</div>
</div>

### isMasked() {#aa9bfb4bb223ce3b720ec0ff7260bce95}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool llvm::ArgDescriptor::isMasked ()</td>
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



<p>Definition at line 86 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/amdgpuargumentusageinfo-h">AMDGPUArgumentUsageInfo.h</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/classes/llvm/amdgpulegalizerinfo/#ae63198baedfab72494f0d79823e99b75">llvm::AMDGPULegalizerInfo::loadInputValue</a>, <a href="/web-llvm/docs/api/classes/llvm/amdgputargetlowering/#a6e1294084507417fe6404d7b7b9c9471">llvm::AMDGPUTargetLowering::loadInputValue</a>, <a href="/web-llvm/docs/api/classes/llvm/amdgpucalllowering/#ac9f5ed1e7ae99c336e8ae9b4ccf10b50">llvm::AMDGPUCallLowering::passSpecialInputs</a> and <a href="/web-llvm/docs/api/classes/llvm/sitargetlowering/#aae4a4706a2a2568c38bd04b1354eafb4">llvm::SITargetLowering::passSpecialInputs</a>.</p>

</div>
</div>

### isRegister() {#a523f3df17ae0b64f7d35d4caad3a54cc}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool llvm::ArgDescriptor::isRegister ()</td>
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



<p>Definition at line 66 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/amdgpuargumentusageinfo-h">AMDGPUArgumentUsageInfo.h</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/classes/llvm/amdgputargetlowering/#a6e1294084507417fe6404d7b7b9c9471">llvm::AMDGPUTargetLowering::loadInputValue</a> and <a href="/web-llvm/docs/api/classes/llvm/amdgpucalllowering/#ac9f5ed1e7ae99c336e8ae9b4ccf10b50">llvm::AMDGPUCallLowering::passSpecialInputs</a>.</p>

</div>
</div>

### isSet() {#ab23237108d60cd63ae0772d377c6adf4}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool llvm::ArgDescriptor::isSet ()</td>
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



<p>Definition at line 58 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/amdgpuargumentusageinfo-h">AMDGPUArgumentUsageInfo.h</a>.</p>


<p>Referenced by <a href="#affbc06542a43694e5f1b9395247aeb76">operator bool</a>.</p>

</div>
</div>

### print() {#a96a608070d394c15c847e9a52e250c1c}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void llvm::ArgDescriptor::print (<a href="/web-llvm/docs/api/classes/llvm/raw-ostream">raw_ostream</a> &amp; OS, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/targetregisterinfo">TargetRegisterInfo</a> * TRI=nullptr)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 90 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/amdgpuargumentusageinfo-h">AMDGPUArgumentUsageInfo.h</a>.</p>


<p>Reference <a href="/web-llvm/docs/api/files/lib/lib/codegen/machinesink-cpp/#a0f36ed1bc17fc1aa97fe291c439a0698">TRI</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/namespaces/llvm/#a0113f6e52bacdee4ca7645ac1baf3ab8">llvm::operator&lt;&lt;</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Public Member Attributes

### Reg {#a54655386a49ce4e122c806d11156bf85}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">MCRegister llvm::ArgDescriptor::Reg</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 31 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/amdgpuargumentusageinfo-h">AMDGPUArgumentUsageInfo.h</a>.</p>


<p>Referenced by <a href="#af8187cceb10a89808f79bbf15136df5d">ArgDescriptor</a>, <a href="#a5ba9ffd4c829c39d10d780ebd8c55ed9">createArg</a>, <a href="#ab80da72ac9122b5c4e4a0a2cfaa25d9e">createRegister</a> and <a href="#a2ee87af66bd7eee85e5a7baabe20afe3">getRegister</a>.</p>

</div>
</div>

### StackOffset {#ab3eea14feb0c5674b5d437c67284fc0b}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">unsigned llvm::ArgDescriptor::StackOffset</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 32 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/amdgpuargumentusageinfo-h">AMDGPUArgumentUsageInfo.h</a>.</p>


<p>Referenced by <a href="#abbadb717106b06e0a4bd9555e53663d4">getStackOffset</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Private Member Attributes

###  {#abd33404bfb235a49049c9b93ea3838bd}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">union llvm::ArgDescriptor llvm::ArgDescriptor</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 33 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/amdgpuargumentusageinfo-h">AMDGPUArgumentUsageInfo.h</a>.</p>

</div>
</div>

### IsSet {#aa289f3e631ee8a1f85a0cfd833cdf190}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool llvm::ArgDescriptor::IsSet</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 39 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/amdgpuargumentusageinfo-h">AMDGPUArgumentUsageInfo.h</a>.</p>

</div>
</div>

### IsStack {#a0c9e2c6544bd1d8e6e029a533eeec9ff}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool llvm::ArgDescriptor::IsStack</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 38 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/amdgpuargumentusageinfo-h">AMDGPUArgumentUsageInfo.h</a>.</p>

</div>
</div>

### Mask {#aa1dd94b8f91c4643ff313ef6e97dedb8}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">unsigned llvm::ArgDescriptor::Mask</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 36 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/amdgpuargumentusageinfo-h">AMDGPUArgumentUsageInfo.h</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Public Static Functions

### createArg() {#a5ba9ffd4c829c39d10d780ebd8c55ed9}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">ArgDescriptor llvm::ArgDescriptor::createArg (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/structs/llvm/argdescriptor">ArgDescriptor</a> &amp; Arg, unsigned Mask)</td>
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



<p>Definition at line 54 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/amdgpuargumentusageinfo-h">AMDGPUArgumentUsageInfo.h</a>.</p>


<p>References <a href="#af8187cceb10a89808f79bbf15136df5d">ArgDescriptor</a> and <a href="#a54655386a49ce4e122c806d11156bf85">Reg</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/siisellowering-cpp/#abcfc092d297e085e5b5390b5b1656236">allocateVGPR32Input</a>, <a href="/web-llvm/docs/api/classes/llvm/gcntargetmachine/#a546e4834a3dc92d96ef8b7598f552a45">llvm::GCNTargetMachine::parseMachineFunctionInfo</a>, <a href="/web-llvm/docs/api/classes/llvm/amdgpucalllowering/#ac9f5ed1e7ae99c336e8ae9b4ccf10b50">llvm::AMDGPUCallLowering::passSpecialInputs</a> and <a href="/web-llvm/docs/api/classes/llvm/sitargetlowering/#aae4a4706a2a2568c38bd04b1354eafb4">llvm::SITargetLowering::passSpecialInputs</a>.</p>

</div>
</div>

### createRegister() {#ab80da72ac9122b5c4e4a0a2cfaa25d9e}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">ArgDescriptor llvm::ArgDescriptor::createRegister (<a href="/web-llvm/docs/api/classes/llvm/register">Register</a> Reg, unsigned Mask=~0u)</td>
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



<p>Definition at line 46 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/amdgpuargumentusageinfo-h">AMDGPUArgumentUsageInfo.h</a>.</p>


<p>References <a href="#af8187cceb10a89808f79bbf15136df5d">ArgDescriptor</a> and <a href="#a54655386a49ce4e122c806d11156bf85">Reg</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/classes/llvm/simachinefunctioninfo/#a8f7e4c04e50a907758b386c72881aeab">llvm::SIMachineFunctionInfo::addDispatchID</a>, <a href="/web-llvm/docs/api/classes/llvm/simachinefunctioninfo/#a20d6ce13e4dd56524b3f12e9e0f4e486">llvm::SIMachineFunctionInfo::addDispatchPtr</a>, <a href="/web-llvm/docs/api/classes/llvm/simachinefunctioninfo/#a2d8c2f895782d369f697943a12afc842">llvm::SIMachineFunctionInfo::addFlatScratchInit</a>, <a href="/web-llvm/docs/api/classes/llvm/simachinefunctioninfo/#ad11ce964b5bd5fa132b60b747c6da45b">llvm::SIMachineFunctionInfo::addImplicitBufferPtr</a>, <a href="/web-llvm/docs/api/classes/llvm/simachinefunctioninfo/#a8e62f53d9286d3407be6644804a7629b">llvm::SIMachineFunctionInfo::addKernargSegmentPtr</a>, <a href="/web-llvm/docs/api/classes/llvm/simachinefunctioninfo/#a7df209bfd0caf887ea85b2f87deb1d23">llvm::SIMachineFunctionInfo::addLDSKernelId</a>, <a href="/web-llvm/docs/api/classes/llvm/simachinefunctioninfo/#abe9cb2c1e57e662992ae50574e1e0669">llvm::SIMachineFunctionInfo::addPrivateSegmentBuffer</a>, <a href="/web-llvm/docs/api/classes/llvm/simachinefunctioninfo/#a18a67353fc677817bcbf9ed74b104d8a">llvm::SIMachineFunctionInfo::addPrivateSegmentSize</a>, <a href="/web-llvm/docs/api/classes/llvm/simachinefunctioninfo/#a6f4dee20d1bcc5a830f54a929dd88272">llvm::SIMachineFunctionInfo::addPrivateSegmentWaveByteOffset</a>, <a href="/web-llvm/docs/api/classes/llvm/simachinefunctioninfo/#a3cbc6457d84c432dea9eb6d83ac711fa">llvm::SIMachineFunctionInfo::addQueuePtr</a>, <a href="/web-llvm/docs/api/classes/llvm/simachinefunctioninfo/#afec13b8987b54c5ba1b890a066f65b15">llvm::SIMachineFunctionInfo::addWorkGroupIDX</a>, <a href="/web-llvm/docs/api/classes/llvm/simachinefunctioninfo/#a59ab34975380ef0aeea0e19aee8b5066">llvm::SIMachineFunctionInfo::addWorkGroupIDY</a>, <a href="/web-llvm/docs/api/classes/llvm/simachinefunctioninfo/#ae859682da11fe274e285540154095291">llvm::SIMachineFunctionInfo::addWorkGroupIDZ</a>, <a href="/web-llvm/docs/api/classes/llvm/simachinefunctioninfo/#aea6797599702c93fb7858314715f4b2f">llvm::SIMachineFunctionInfo::addWorkGroupInfo</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/siisellowering-cpp/#a8688cc0d4d5620a54a1d45bd3087de1f">allocateSGPR32InputImpl</a>, <a href="/web-llvm/docs/api/classes/llvm/sitargetlowering/#add01b669c3b94782f5e3a2babaa12f50">llvm::SITargetLowering::allocateSpecialEntryInputVGPRs</a>, <a href="/web-llvm/docs/api/classes/llvm/sitargetlowering/#a7e8edb844e6cf1666a202039e9a21d01">llvm::SITargetLowering::allocateSpecialInputVGPRsFixed</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/siisellowering-cpp/#abcfc092d297e085e5b5390b5b1656236">allocateVGPR32Input</a>, <a href="/web-llvm/docs/api/structs/llvm/amdgpufunctionarginfo/#a69667e25bd46f756ca2b9efab35508eb">llvm::AMDGPUFunctionArgInfo::fixedABILayout</a>, <a href="/web-llvm/docs/api/classes/llvm/amdgpulegalizerinfo/#a724c83948fec4d3162f4620ec6f61a7a">llvm::AMDGPULegalizerInfo::loadInputValue</a>, <a href="/web-llvm/docs/api/classes/llvm/gcntargetmachine/#a546e4834a3dc92d96ef8b7598f552a45">llvm::GCNTargetMachine::parseMachineFunctionInfo</a>, <a href="/web-llvm/docs/api/classes/llvm/simachinefunctioninfo/#a84f2897437136a65a41de83cc7a962f6">llvm::SIMachineFunctionInfo::setPrivateSegmentWaveByteOffset</a> and <a href="/web-llvm/docs/api/classes/llvm/simachinefunctioninfo/#af63d1fba23bc323d27c9dc50313698eb">llvm::SIMachineFunctionInfo::SIMachineFunctionInfo</a>.</p>

</div>
</div>

### createStack() {#a2b90780a92bdcaed0a47e50d86ec6e6b}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">ArgDescriptor llvm::ArgDescriptor::createStack (unsigned Offset, unsigned Mask=~0u)</td>
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



<p>Definition at line 50 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/amdgpuargumentusageinfo-h">AMDGPUArgumentUsageInfo.h</a>.</p>


<p>References <a href="#af8187cceb10a89808f79bbf15136df5d">ArgDescriptor</a> and <a href="/web-llvm/docs/api/namespaces/llvm/#a05f5b9a11bdcc5feba62899f95dcf878a3134224cba2545bc57954d3b072aebb4">llvm::Offset</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/siisellowering-cpp/#abcfc092d297e085e5b5390b5b1656236">allocateVGPR32Input</a> and <a href="/web-llvm/docs/api/classes/llvm/gcntargetmachine/#a546e4834a3dc92d96ef8b7598f552a45">llvm::GCNTargetMachine::parseMachineFunctionInfo</a>.</p>

</div>
</div>

</div>

<hr/>

The documentation for this struct was generated from the following file:

<ul>
<li><a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/amdgpuargumentusageinfo-h">AMDGPUArgumentUsageInfo.h</a></li>
</ul>

<hr/>

<p class="doxyGeneratedBy">Generated via <a href="https://github.com/xpack/doxygen2docusaurus">doxygen2docusaurus</a> by <a href="https://www.doxygen.nl">Doxygen</a> 1.14.0.</p>

</div>
