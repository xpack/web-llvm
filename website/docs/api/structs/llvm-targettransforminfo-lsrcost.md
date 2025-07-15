---

# DO NOT EDIT!
# Automatically generated via doxygen2docusaurus by Doxygen.

slug: /api/structs/llvm/targettransforminfo/lsrcost
custom_edit_url: null
toc_max_heading_level: 4
keywords:
  - doxygen
  - reference
  - struct

---

<div class="doxyPage">

# The `LSRCost` Struct Reference



## Declaration

<div class="doxyDeclaration">
struct llvm::TargetTransformInfo::LSRCost { ... }
</div>

## Included Headers

<div class="doxyIncludesList">#include "<a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/analysis/targettransforminfo-h">llvm/Analysis/TargetTransformInfo.h</a>"
</div>

## Public Member Attributes Index

<table class="doxyMembersIndex">

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">unsigned</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a5b3b10333e5dcfbc64652b383025b77c">Insns</a></td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>TODO: Some of these could be merged. <a href="#a5b3b10333e5dcfbc64652b383025b77c">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">unsigned</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#acc4efcc7eb81341eb7b94387d7519fd7">NumRegs</a></td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a95eb887e84c6d2b102a6b0114276f8da">AddRecCost</a></td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a1cc611760ab739d87bf545a55dcea72b">NumIVMuls</a></td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ad56d6a45ed26384d00b88e431e6e9181">NumBaseAdds</a></td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a66e939ebf350e35ede6f1af76f243b65">ImmCost</a></td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#afa00c85b17f12a25f99f238eaf86ece7">SetupCost</a></td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a56c87ad7c1654d83b3f4d7984fc66d75">ScaleCost</a></td>
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


<p>Definition at line 522 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/analysis/targettransforminfo-h">TargetTransformInfo.h</a>.</p>


<div class="doxySectionDef">

## Public Member Attributes

### AddRecCost {#a95eb887e84c6d2b102a6b0114276f8da}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">unsigned llvm::TargetTransformInfo::LSRCost::AddRecCost</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 527 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/analysis/targettransforminfo-h">TargetTransformInfo.h</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/classes/llvm/aarch64ttiimpl/#a67ac59d3984e23f1758de82838789087">llvm::AArch64TTIImpl::isLSRCostLess</a>, <a href="/web-llvm/docs/api/classes/llvm/ppcttiimpl/#a2e2c6081215dcc909699433f341692f7">llvm::PPCTTIImpl::isLSRCostLess</a>, <a href="/web-llvm/docs/api/classes/llvm/riscvttiimpl/#a1feac9e51b46df47635415f398fde729">llvm::RISCVTTIImpl::isLSRCostLess</a>, <a href="/web-llvm/docs/api/classes/llvm/systemzttiimpl/#aa07ee4a285d3e3e144b27bdd1cb7529b">llvm::SystemZTTIImpl::isLSRCostLess</a>, <a href="/web-llvm/docs/api/classes/llvm/targettransforminfoimplbase/#a24dfd2b966967135b0dba8e680d313f0">llvm::TargetTransformInfoImplBase::isLSRCostLess</a> and <a href="/web-llvm/docs/api/classes/llvm/x86ttiimpl/#a9c585e96b54164c0102f42b9c808393b">llvm::X86TTIImpl::isLSRCostLess</a>.</p>

</div>
</div>

### ImmCost {#a66e939ebf350e35ede6f1af76f243b65}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">unsigned llvm::TargetTransformInfo::LSRCost::ImmCost</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 530 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/analysis/targettransforminfo-h">TargetTransformInfo.h</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/classes/llvm/aarch64ttiimpl/#a67ac59d3984e23f1758de82838789087">llvm::AArch64TTIImpl::isLSRCostLess</a>, <a href="/web-llvm/docs/api/classes/llvm/ppcttiimpl/#a2e2c6081215dcc909699433f341692f7">llvm::PPCTTIImpl::isLSRCostLess</a>, <a href="/web-llvm/docs/api/classes/llvm/riscvttiimpl/#a1feac9e51b46df47635415f398fde729">llvm::RISCVTTIImpl::isLSRCostLess</a>, <a href="/web-llvm/docs/api/classes/llvm/targettransforminfoimplbase/#a24dfd2b966967135b0dba8e680d313f0">llvm::TargetTransformInfoImplBase::isLSRCostLess</a> and <a href="/web-llvm/docs/api/classes/llvm/x86ttiimpl/#a9c585e96b54164c0102f42b9c808393b">llvm::X86TTIImpl::isLSRCostLess</a>.</p>

</div>
</div>

### Insns {#a5b3b10333e5dcfbc64652b383025b77c}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">unsigned llvm::TargetTransformInfo::LSRCost::Insns</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>TODO: Some of these could be merged.</p>


<p>Also, a lexical ordering isn't always optimal.</p>


<p>Definition at line 525 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/analysis/targettransforminfo-h">TargetTransformInfo.h</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/classes/llvm/aarch64ttiimpl/#a67ac59d3984e23f1758de82838789087">llvm::AArch64TTIImpl::isLSRCostLess</a>, <a href="/web-llvm/docs/api/classes/llvm/ppcttiimpl/#a2e2c6081215dcc909699433f341692f7">llvm::PPCTTIImpl::isLSRCostLess</a>, <a href="/web-llvm/docs/api/classes/llvm/riscvttiimpl/#a1feac9e51b46df47635415f398fde729">llvm::RISCVTTIImpl::isLSRCostLess</a>, <a href="/web-llvm/docs/api/classes/llvm/systemzttiimpl/#aa07ee4a285d3e3e144b27bdd1cb7529b">llvm::SystemZTTIImpl::isLSRCostLess</a> and <a href="/web-llvm/docs/api/classes/llvm/x86ttiimpl/#a9c585e96b54164c0102f42b9c808393b">llvm::X86TTIImpl::isLSRCostLess</a>.</p>

</div>
</div>

### NumBaseAdds {#ad56d6a45ed26384d00b88e431e6e9181}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">unsigned llvm::TargetTransformInfo::LSRCost::NumBaseAdds</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 529 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/analysis/targettransforminfo-h">TargetTransformInfo.h</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/classes/llvm/aarch64ttiimpl/#a67ac59d3984e23f1758de82838789087">llvm::AArch64TTIImpl::isLSRCostLess</a>, <a href="/web-llvm/docs/api/classes/llvm/ppcttiimpl/#a2e2c6081215dcc909699433f341692f7">llvm::PPCTTIImpl::isLSRCostLess</a>, <a href="/web-llvm/docs/api/classes/llvm/riscvttiimpl/#a1feac9e51b46df47635415f398fde729">llvm::RISCVTTIImpl::isLSRCostLess</a>, <a href="/web-llvm/docs/api/classes/llvm/systemzttiimpl/#aa07ee4a285d3e3e144b27bdd1cb7529b">llvm::SystemZTTIImpl::isLSRCostLess</a>, <a href="/web-llvm/docs/api/classes/llvm/targettransforminfoimplbase/#a24dfd2b966967135b0dba8e680d313f0">llvm::TargetTransformInfoImplBase::isLSRCostLess</a> and <a href="/web-llvm/docs/api/classes/llvm/x86ttiimpl/#a9c585e96b54164c0102f42b9c808393b">llvm::X86TTIImpl::isLSRCostLess</a>.</p>

</div>
</div>

### NumIVMuls {#a1cc611760ab739d87bf545a55dcea72b}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">unsigned llvm::TargetTransformInfo::LSRCost::NumIVMuls</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 528 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/analysis/targettransforminfo-h">TargetTransformInfo.h</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/classes/llvm/aarch64ttiimpl/#a67ac59d3984e23f1758de82838789087">llvm::AArch64TTIImpl::isLSRCostLess</a>, <a href="/web-llvm/docs/api/classes/llvm/ppcttiimpl/#a2e2c6081215dcc909699433f341692f7">llvm::PPCTTIImpl::isLSRCostLess</a>, <a href="/web-llvm/docs/api/classes/llvm/riscvttiimpl/#a1feac9e51b46df47635415f398fde729">llvm::RISCVTTIImpl::isLSRCostLess</a>, <a href="/web-llvm/docs/api/classes/llvm/systemzttiimpl/#aa07ee4a285d3e3e144b27bdd1cb7529b">llvm::SystemZTTIImpl::isLSRCostLess</a>, <a href="/web-llvm/docs/api/classes/llvm/targettransforminfoimplbase/#a24dfd2b966967135b0dba8e680d313f0">llvm::TargetTransformInfoImplBase::isLSRCostLess</a> and <a href="/web-llvm/docs/api/classes/llvm/x86ttiimpl/#a9c585e96b54164c0102f42b9c808393b">llvm::X86TTIImpl::isLSRCostLess</a>.</p>

</div>
</div>

### NumRegs {#acc4efcc7eb81341eb7b94387d7519fd7}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">unsigned llvm::TargetTransformInfo::LSRCost::NumRegs</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 526 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/analysis/targettransforminfo-h">TargetTransformInfo.h</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/classes/llvm/aarch64ttiimpl/#a67ac59d3984e23f1758de82838789087">llvm::AArch64TTIImpl::isLSRCostLess</a>, <a href="/web-llvm/docs/api/classes/llvm/ppcttiimpl/#a2e2c6081215dcc909699433f341692f7">llvm::PPCTTIImpl::isLSRCostLess</a>, <a href="/web-llvm/docs/api/classes/llvm/riscvttiimpl/#a1feac9e51b46df47635415f398fde729">llvm::RISCVTTIImpl::isLSRCostLess</a>, <a href="/web-llvm/docs/api/classes/llvm/systemzttiimpl/#aa07ee4a285d3e3e144b27bdd1cb7529b">llvm::SystemZTTIImpl::isLSRCostLess</a>, <a href="/web-llvm/docs/api/classes/llvm/targettransforminfoimplbase/#a24dfd2b966967135b0dba8e680d313f0">llvm::TargetTransformInfoImplBase::isLSRCostLess</a> and <a href="/web-llvm/docs/api/classes/llvm/x86ttiimpl/#a9c585e96b54164c0102f42b9c808393b">llvm::X86TTIImpl::isLSRCostLess</a>.</p>

</div>
</div>

### ScaleCost {#a56c87ad7c1654d83b3f4d7984fc66d75}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">unsigned llvm::TargetTransformInfo::LSRCost::ScaleCost</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 532 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/analysis/targettransforminfo-h">TargetTransformInfo.h</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/classes/llvm/aarch64ttiimpl/#a67ac59d3984e23f1758de82838789087">llvm::AArch64TTIImpl::isLSRCostLess</a>, <a href="/web-llvm/docs/api/classes/llvm/ppcttiimpl/#a2e2c6081215dcc909699433f341692f7">llvm::PPCTTIImpl::isLSRCostLess</a>, <a href="/web-llvm/docs/api/classes/llvm/riscvttiimpl/#a1feac9e51b46df47635415f398fde729">llvm::RISCVTTIImpl::isLSRCostLess</a>, <a href="/web-llvm/docs/api/classes/llvm/systemzttiimpl/#aa07ee4a285d3e3e144b27bdd1cb7529b">llvm::SystemZTTIImpl::isLSRCostLess</a>, <a href="/web-llvm/docs/api/classes/llvm/targettransforminfoimplbase/#a24dfd2b966967135b0dba8e680d313f0">llvm::TargetTransformInfoImplBase::isLSRCostLess</a> and <a href="/web-llvm/docs/api/classes/llvm/x86ttiimpl/#a9c585e96b54164c0102f42b9c808393b">llvm::X86TTIImpl::isLSRCostLess</a>.</p>

</div>
</div>

### SetupCost {#afa00c85b17f12a25f99f238eaf86ece7}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">unsigned llvm::TargetTransformInfo::LSRCost::SetupCost</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 531 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/analysis/targettransforminfo-h">TargetTransformInfo.h</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/classes/llvm/aarch64ttiimpl/#a67ac59d3984e23f1758de82838789087">llvm::AArch64TTIImpl::isLSRCostLess</a>, <a href="/web-llvm/docs/api/classes/llvm/ppcttiimpl/#a2e2c6081215dcc909699433f341692f7">llvm::PPCTTIImpl::isLSRCostLess</a>, <a href="/web-llvm/docs/api/classes/llvm/riscvttiimpl/#a1feac9e51b46df47635415f398fde729">llvm::RISCVTTIImpl::isLSRCostLess</a>, <a href="/web-llvm/docs/api/classes/llvm/systemzttiimpl/#aa07ee4a285d3e3e144b27bdd1cb7529b">llvm::SystemZTTIImpl::isLSRCostLess</a>, <a href="/web-llvm/docs/api/classes/llvm/targettransforminfoimplbase/#a24dfd2b966967135b0dba8e680d313f0">llvm::TargetTransformInfoImplBase::isLSRCostLess</a> and <a href="/web-llvm/docs/api/classes/llvm/x86ttiimpl/#a9c585e96b54164c0102f42b9c808393b">llvm::X86TTIImpl::isLSRCostLess</a>.</p>

</div>
</div>

</div>

<hr/>

The documentation for this struct was generated from the following file:

<ul>
<li><a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/analysis/targettransforminfo-h">TargetTransformInfo.h</a></li>
</ul>

<hr/>

<p class="doxyGeneratedBy">Generated via <a href="https://github.com/xpack/doxygen2docusaurus">doxygen2docusaurus</a> by <a href="https://www.doxygen.nl">Doxygen</a> 1.14.0.</p>

</div>
