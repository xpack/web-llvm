---

# DO NOT EDIT!
# Automatically generated via doxygen2docusaurus by Doxygen.

slug: /api/namespaces/llvm/amdgpu/depctr
custom_edit_url: null
toc_max_heading_level: 4
keywords:
  - doxygen
  - reference
  - namespace

---

<div class="doxyPage">

# `DepCtr` Namespace



## Definition

<div class="doxyDefinition">
namespace llvm::AMDGPU::DepCtr { ... }
</div>

## Functions Index

<table class="doxyMembersIndex">

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">int</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#aed8a3720f645c7bbc2321b96e35d0db1">getDefaultDepCtrEncoding</a> (const MCSubtargetInfo &amp;STI)</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ac8e67eb826ed33ec20e1d0ed0ae7ea89">isSymbolicDepCtrEncoding</a> (unsigned Code, bool &amp;HasNonDefaultVal, const MCSubtargetInfo &amp;STI)</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a32e99aad99ecf2ce78c854ce632097f5">decodeDepCtr</a> (unsigned Code, int &amp;Id, StringRef &amp;Name, unsigned &amp;Val, bool &amp;IsDefault, const MCSubtargetInfo &amp;STI)</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">int</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#aa21c648940433a5a427e164a2c2c825c">encodeDepCtr</a> (const StringRef Name, int64_t Val, unsigned &amp;UsedOprMask, const MCSubtargetInfo &amp;STI)</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#af53128c62a54496ecc5959d2bdab8034">decodeFieldVmVsrc</a> (unsigned Encoded)</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ad0af1d007a5a69d0408b1ad698ffae04">decodeFieldVaVdst</a> (unsigned Encoded)</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a6ed2385750706d762e272bec591ce6c0">decodeFieldSaSdst</a> (unsigned Encoded)</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a9b14ed5636171541f2cdacb6f5c47394">encodeFieldVmVsrc</a> (unsigned Encoded, unsigned VmVsrc)</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#aa9c4ee6ae0c2ffbce2e43c174427ca9a">encodeFieldVmVsrc</a> (unsigned VmVsrc)</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a69c825f4b28e0cc125d650923c9a02da">encodeFieldVaVdst</a> (unsigned Encoded, unsigned VaVdst)</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a17a51a32718cef4f7bdde2933cf9a6fb">encodeFieldVaVdst</a> (unsigned VaVdst)</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#aa9b70486e0433ce7ad354709d973c40e">encodeFieldSaSdst</a> (unsigned Encoded, unsigned SaSdst)</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a66aff4d7761faf5fd11c054065a1599f">encodeFieldSaSdst</a> (unsigned SaSdst)</td>
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

## Variables Index

<table class="doxyMembersIndex">

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/structs/llvm/amdgpu/customoperandval">CustomOperandVal</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#abeef708757cf4d9dd37dbd53f1039ad9">DepCtrInfo</a>[] = ...</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> int</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#aa005c1844a1387f355c83eb2c322abe6">DEP_CTR_SIZE</a> = ...</td>
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

### decodeDepCtr() {#a32e99aad99ecf2ce78c854ce632097f5}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool llvm::AMDGPU::DepCtr::decodeDepCtr (unsigned Code, int &amp; Id, <a href="/web-llvm/docs/api/classes/llvm/stringref">StringRef</a> &amp; Name, unsigned &amp; Val, bool &amp; IsDefault, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/mcsubtargetinfo">MCSubtargetInfo</a> &amp; STI)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 1698 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/lib/target/amdgpu/utils/amdgpubaseinfo-cpp">AMDGPUBaseInfo.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/namespaces/llvm/amdgpu/#ab1d87d1571318f5e34f457d97c6b8375">llvm::AMDGPU::decodeCustomOperand</a>, <a href="#aa005c1844a1387f355c83eb2c322abe6">DEP_CTR_SIZE</a> and <a href="#abeef708757cf4d9dd37dbd53f1039ad9">DepCtrInfo</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/classes/llvm/amdgpuinstprinter/#a6895016d90c30dc6d1997e420a181f0e">llvm::AMDGPUInstPrinter::printDepCtr</a>.</p>

</div>
</div>

### decodeFieldSaSdst() {#a6ed2385750706d762e272bec591ce6c0}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">unsigned llvm::AMDGPU::DepCtr::decodeFieldSaSdst (unsigned Encoded)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">




<dl class="doxySectionUser">
<dt>Returns</dt>
<dd><p>Decoded SaSdst from given immediate <span class="doxyComputerOutput">Encoded</span>.</p></dd>
</dl>


<p>Definition at line 1718 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/lib/target/amdgpu/utils/amdgpubaseinfo-cpp">AMDGPUBaseInfo.cpp</a>.</p>

</div>
</div>

### decodeFieldVaVdst() {#ad0af1d007a5a69d0408b1ad698ffae04}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">unsigned llvm::AMDGPU::DepCtr::decodeFieldVaVdst (unsigned Encoded)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">




<dl class="doxySectionUser">
<dt>Returns</dt>
<dd><p>Decoded VaVdst from given immediate <span class="doxyComputerOutput">Encoded</span>.</p></dd>
</dl>


<p>Definition at line 1714 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/lib/target/amdgpu/utils/amdgpubaseinfo-cpp">AMDGPUBaseInfo.cpp</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/classes/anonymous-amdgpuinsertdelayalu-cpp-/amdgpuinsertdelayalu/#acd449b894bd3b36c645c143ca58240e4">anonymous{AMDGPUInsertDelayAlu.cpp}::AMDGPUInsertDelayAlu::instructionWaitsForVALU</a>.</p>

</div>
</div>

### decodeFieldVmVsrc() {#af53128c62a54496ecc5959d2bdab8034}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">unsigned llvm::AMDGPU::DepCtr::decodeFieldVmVsrc (unsigned Encoded)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">




<dl class="doxySectionUser">
<dt>Returns</dt>
<dd><p>Decoded VmVsrc from given immediate <span class="doxyComputerOutput">Encoded</span>.</p></dd>
</dl>


<p>Definition at line 1710 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/lib/target/amdgpu/utils/amdgpubaseinfo-cpp">AMDGPUBaseInfo.cpp</a>.</p>

</div>
</div>

### encodeDepCtr() {#aa21c648940433a5a427e164a2c2c825c}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">int llvm::AMDGPU::DepCtr::encodeDepCtr (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/stringref">StringRef</a> Name, int64_t Val, unsigned &amp; UsedOprMask, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/mcsubtargetinfo">MCSubtargetInfo</a> &amp; STI)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 1704 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/lib/target/amdgpu/utils/amdgpubaseinfo-cpp">AMDGPUBaseInfo.cpp</a>.</p>


<p>References <a href="#aa005c1844a1387f355c83eb2c322abe6">DEP_CTR_SIZE</a>, <a href="#abeef708757cf4d9dd37dbd53f1039ad9">DepCtrInfo</a> and <a href="/web-llvm/docs/api/namespaces/llvm/amdgpu/#adba46a37416d34246b94f46426282aba">llvm::AMDGPU::encodeCustomOperand</a>.</p>

</div>
</div>

### encodeFieldSaSdst() {#aa9b70486e0433ce7ad354709d973c40e}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">unsigned llvm::AMDGPU::DepCtr::encodeFieldSaSdst (unsigned Encoded, unsigned SaSdst)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">




<dl class="doxySectionUser">
<dt>Returns</dt>
<dd><p><span class="doxyComputerOutput">Encoded</span> combined with encoded <span class="doxyComputerOutput">SaSdst</span>.</p></dd>
</dl>


<p>Definition at line 1738 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/lib/target/amdgpu/utils/amdgpubaseinfo-cpp">AMDGPUBaseInfo.cpp</a>.</p>


<p>Referenced by <a href="#a66aff4d7761faf5fd11c054065a1599f">encodeFieldSaSdst</a> and <a href="/web-llvm/docs/api/classes/llvm/siinstrinfo/#aff3eb40a3be5c2fb6f804f1e5649fd57">llvm::SIInstrInfo::insertIndirectBranch</a>.</p>

</div>
</div>

### encodeFieldSaSdst() {#a66aff4d7761faf5fd11c054065a1599f}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">unsigned llvm::AMDGPU::DepCtr::encodeFieldSaSdst (unsigned SaSdst)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">




<dl class="doxySectionUser">
<dt>Returns</dt>
<dd><p><span class="doxyComputerOutput">SaSdst</span> as an encoded Depctr immediate.</p></dd>
</dl>


<p>Definition at line 1742 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/lib/target/amdgpu/utils/amdgpubaseinfo-cpp">AMDGPUBaseInfo.cpp</a>.</p>


<p>Reference <a href="#aa9b70486e0433ce7ad354709d973c40e">encodeFieldSaSdst</a>.</p>

</div>
</div>

### encodeFieldVaVdst() {#a69c825f4b28e0cc125d650923c9a02da}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">unsigned llvm::AMDGPU::DepCtr::encodeFieldVaVdst (unsigned Encoded, unsigned VaVdst)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">




<dl class="doxySectionUser">
<dt>Returns</dt>
<dd><p><span class="doxyComputerOutput">Encoded</span> combined with encoded <span class="doxyComputerOutput">VaVdst</span>.</p></dd>
</dl>


<p>Definition at line 1730 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/lib/target/amdgpu/utils/amdgpubaseinfo-cpp">AMDGPUBaseInfo.cpp</a>.</p>


<p>Referenced by <a href="#a17a51a32718cef4f7bdde2933cf9a6fb">encodeFieldVaVdst</a>.</p>

</div>
</div>

### encodeFieldVaVdst() {#a17a51a32718cef4f7bdde2933cf9a6fb}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">unsigned llvm::AMDGPU::DepCtr::encodeFieldVaVdst (unsigned VaVdst)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">




<dl class="doxySectionUser">
<dt>Returns</dt>
<dd><p><span class="doxyComputerOutput">VaVdst</span> as an encoded Depctr immediate.</p></dd>
</dl>


<p>Definition at line 1734 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/lib/target/amdgpu/utils/amdgpubaseinfo-cpp">AMDGPUBaseInfo.cpp</a>.</p>


<p>Reference <a href="#a69c825f4b28e0cc125d650923c9a02da">encodeFieldVaVdst</a>.</p>

</div>
</div>

### encodeFieldVmVsrc() {#a9b14ed5636171541f2cdacb6f5c47394}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">unsigned llvm::AMDGPU::DepCtr::encodeFieldVmVsrc (unsigned Encoded, unsigned VmVsrc)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">




<dl class="doxySectionUser">
<dt>Returns</dt>
<dd><p><span class="doxyComputerOutput">Encoded</span> combined with encoded <span class="doxyComputerOutput">VmVsrc</span>.</p></dd>
</dl>


<p>Definition at line 1722 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/lib/target/amdgpu/utils/amdgpubaseinfo-cpp">AMDGPUBaseInfo.cpp</a>.</p>


<p>Referenced by <a href="#aa9c4ee6ae0c2ffbce2e43c174427ca9a">encodeFieldVmVsrc</a>.</p>

</div>
</div>

### encodeFieldVmVsrc() {#aa9c4ee6ae0c2ffbce2e43c174427ca9a}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">unsigned llvm::AMDGPU::DepCtr::encodeFieldVmVsrc (unsigned VmVsrc)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">




<dl class="doxySectionUser">
<dt>Returns</dt>
<dd><p><span class="doxyComputerOutput">VmVsrc</span> as an encoded Depctr immediate.</p></dd>
</dl>


<p>Definition at line 1726 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/lib/target/amdgpu/utils/amdgpubaseinfo-cpp">AMDGPUBaseInfo.cpp</a>.</p>


<p>Reference <a href="#a9b14ed5636171541f2cdacb6f5c47394">encodeFieldVmVsrc</a>.</p>

</div>
</div>

### getDefaultDepCtrEncoding() {#aed8a3720f645c7bbc2321b96e35d0db1}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">int llvm::AMDGPU::DepCtr::getDefaultDepCtrEncoding (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/mcsubtargetinfo">MCSubtargetInfo</a> &amp; STI)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 1685 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/lib/target/amdgpu/utils/amdgpubaseinfo-cpp">AMDGPUBaseInfo.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/namespaces/llvm/#ae58c751054b01f206f9b9e34e461d25fa7a1920d61156abc05a60135aefe8bc67">llvm::Default</a>, <a href="#aa005c1844a1387f355c83eb2c322abe6">DEP_CTR_SIZE</a>, <a href="#abeef708757cf4d9dd37dbd53f1039ad9">DepCtrInfo</a> and <a href="/web-llvm/docs/api/namespaces/llvm/amdgpu/#aac0ac2247bcb96cc09003f9ad3209fe9">llvm::AMDGPU::getDefaultCustomOperandEncoding</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/classes/anonymous-amdgpuasmparser-cpp-/amdgpuasmparser/#aa54525f0109858da308fa32559539255">anonymous{AMDGPUAsmParser.cpp}::AMDGPUAsmParser::parseDepCtr</a>.</p>

</div>
</div>

### isSymbolicDepCtrEncoding() {#ac8e67eb826ed33ec20e1d0ed0ae7ea89}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool llvm::AMDGPU::DepCtr::isSymbolicDepCtrEncoding (unsigned Code, bool &amp; HasNonDefaultVal, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/mcsubtargetinfo">MCSubtargetInfo</a> &amp; STI)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 1692 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/lib/target/amdgpu/utils/amdgpubaseinfo-cpp">AMDGPUBaseInfo.cpp</a>.</p>


<p>References <a href="#aa005c1844a1387f355c83eb2c322abe6">DEP_CTR_SIZE</a>, <a href="#abeef708757cf4d9dd37dbd53f1039ad9">DepCtrInfo</a> and <a href="/web-llvm/docs/api/namespaces/llvm/amdgpu/#a1b3c3770530e74155f4aba13e19f1145">llvm::AMDGPU::isSymbolicCustomOperandEncoding</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/classes/llvm/amdgpuinstprinter/#a6895016d90c30dc6d1997e420a181f0e">llvm::AMDGPUInstPrinter::printDepCtr</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Variables

### DEP\_CTR\_SIZE {#aa005c1844a1387f355c83eb2c322abe6}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">const int llvm::AMDGPU::DepCtr::DEP_CTR_SIZE</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<dl class="doxySectionUser">
<dt>Initialiser</dt>
<dd>
<div class="doxyVerbatim">=
    static_cast&lt;int&gt;(sizeof(<a href="#abeef708757cf4d9dd37dbd53f1039ad9">DepCtrInfo</a>) / sizeof(<a href="/web-llvm/docs/api/structs/llvm/amdgpu/customoperandval">CustomOperandVal</a>))
</div>
</dd>
</dl>

<p>Definition at line 83 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/lib/target/amdgpu/utils/amdgpuasmutils-cpp">AMDGPUAsmUtils.cpp</a>.</p>


<p>Referenced by <a href="#a32e99aad99ecf2ce78c854ce632097f5">decodeDepCtr</a>, <a href="#aa21c648940433a5a427e164a2c2c825c">encodeDepCtr</a>, <a href="#aed8a3720f645c7bbc2321b96e35d0db1">getDefaultDepCtrEncoding</a> and <a href="#ac8e67eb826ed33ec20e1d0ed0ae7ea89">isSymbolicDepCtrEncoding</a>.</p>

</div>
</div>

### DepCtrInfo {#abeef708757cf4d9dd37dbd53f1039ad9}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">const CustomOperandVal llvm::AMDGPU::DepCtr::DepCtrInfo</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<dl class="doxySectionUser">
<dt>Initialiser</dt>
<dd>
<div class="doxyVerbatim">= {
  {{"depctr_hold_cnt"},  1,   1,    7,    1,   <a href="/web-llvm/docs/api/namespaces/llvm/amdgpu/#a03038e2ec3d91a361fbbb066e575de9a">isGFX10_BEncoding</a>},
  {{"depctr_sa_sdst"},   1,   1,    0,    1},
  {{"depctr_va_vdst"},  15,  15,   12,    4},
  {{"depctr_va_sdst"},   7,   7,    9,    3},
  {{"depctr_va_ssrc"},   1,   1,    8,    1},
  {{"depctr_va_vcc"},    1,   1,    1,    1},
  {{"depctr_vm_vsrc"},   7,   7,    2,    3},
}
</div>
</dd>
</dl>

<p>Definition at line 71 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/lib/target/amdgpu/utils/amdgpuasmutils-cpp">AMDGPUAsmUtils.cpp</a>.</p>


<p>Referenced by <a href="#a32e99aad99ecf2ce78c854ce632097f5">decodeDepCtr</a>, <a href="#aa21c648940433a5a427e164a2c2c825c">encodeDepCtr</a>, <a href="#aed8a3720f645c7bbc2321b96e35d0db1">getDefaultDepCtrEncoding</a> and <a href="#ac8e67eb826ed33ec20e1d0ed0ae7ea89">isSymbolicDepCtrEncoding</a>.</p>

</div>
</div>

</div>

<hr/>

The documentation for this namespace was generated from the following files:

<ul>
<li><a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/lib/target/amdgpu/utils/amdgpuasmutils-cpp">AMDGPUAsmUtils.cpp</a></li>
<li><a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/lib/target/amdgpu/utils/amdgpubaseinfo-cpp">AMDGPUBaseInfo.cpp</a></li>
</ul>

<hr/>

<p class="doxyGeneratedBy">Generated via <a href="https://github.com/xpack/doxygen2docusaurus">doxygen2docusaurus</a> by <a href="https://www.doxygen.nl">Doxygen</a> 1.15.0.</p>

</div>
