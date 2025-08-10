---

# DO NOT EDIT!
# Automatically generated via doxygen2docusaurus by Doxygen.

slug: /api/structs/llvm/registerbankinfo/partialmapping
custom_edit_url: null
toc_max_heading_level: 4
keywords:
  - doxygen
  - reference
  - struct

---

<div class="doxyPage">

# `PartialMapping` Struct

<p>Helper struct that represents how a value is partially mapped into a register. <a href="#details">More...</a></p>

## Declaration

<div class="doxyDeclaration">
struct llvm::RegisterBankInfo::PartialMapping { ... }
</div>

## Included Headers

<div class="doxyIncludesList">#include "<a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/codegen/registerbankinfo-h">llvm/CodeGen/RegisterBankInfo.h</a>"
</div>

## Public Constructors Index

<table class="doxyMembersIndex">

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a5e777b5830144bec3ba5750f0f33f5bc">PartialMapping</a> ()=default</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">constexpr</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a048ada9430cf3309d4a1db1a7261420c">PartialMapping</a> (unsigned StartIdx, unsigned Length, const RegisterBank &amp;RegBank)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Provide a shortcut for quickly building <a href="/web-llvm/docs/api/structs/llvm/registerbankinfo/partialmapping">PartialMapping</a>. <a href="#a048ada9430cf3309d4a1db1a7261420c">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

</table>

## Public Member Functions Index

<table class="doxyMembersIndex">

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">unsigned</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a6de81ad6fdab369c1e85c901b7f2e8d4">getHighBitIdx</a> () const</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ad6adb61747f6498e03e8169e79c4365f">dump</a> () const</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Print this partial mapping on <a href="/web-llvm/docs/api/namespaces/llvm/#a7c46c742c31be54870e2038048e6b391">dbgs()</a> stream. <a href="#ad6adb61747f6498e03e8169e79c4365f">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">void</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a047cd07201d30259f344dc3e0f94e040">print</a> (raw_ostream &amp;OS) const</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Print this partial mapping on <span class="doxyComputerOutput">OS</span>;. <a href="#a047cd07201d30259f344dc3e0f94e040">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">bool</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#aaee9b30ca4238627080ab0cb45ac28e6">verify</a> (const RegisterBankInfo &amp;RBI) const</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p><a href="/web-llvm/docs/api/namespaces/llvm/check">Check</a> that the Mask is compatible with the RegBank. <a href="#aaee9b30ca4238627080ab0cb45ac28e6">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

</table>

## Public Member Attributes Index

<table class="doxyMembersIndex">

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">unsigned</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a0c55804243f2f158a9afa64f0f764c35">StartIdx</a></td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Number of bits at which this partial mapping starts in the original value. <a href="#a0c55804243f2f158a9afa64f0f764c35">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">unsigned</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#afac28dfebeb6f31c2c87dd1acdcd038f">Length</a></td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Length of this mapping in bits. <a href="#afac28dfebeb6f31c2c87dd1acdcd038f">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/registerbank">RegisterBank</a> *</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ae78f517f813c1983db970736287379e1">RegBank</a></td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p><a href="/web-llvm/docs/api/classes/llvm/register">Register</a> bank where the partial value lives. <a href="#ae78f517f813c1983db970736287379e1">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

</table>

## Description {#details}

<p>Helper struct that represents how a value is partially mapped into a register.</p>


<p>The StartIdx and Length represent what region of the orginal value this partial mapping covers. This can be represented as a Mask of contiguous bit starting at StartIdx bit and spanning Length bits. StartIdx is the number of bits from the less significant bits.</p>


<p>Definition at line 49 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/codegen/registerbankinfo-h">RegisterBankInfo.h</a>.</p>


<div class="doxySectionDef">

## Public Constructors

### PartialMapping() {#a5e777b5830144bec3ba5750f0f33f5bc}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">llvm::RegisterBankInfo::PartialMapping::PartialMapping ()</td>
</tr>
</table>
</td>
<td class="doxyMemberLabelsRight">
<span class="doxyMemberLabels">
<span class="doxyMemberLabel default">default</span>
</span>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 63 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/codegen/registerbankinfo-h">RegisterBankInfo.h</a>.</p>

</div>
</div>

### PartialMapping() {#a048ada9430cf3309d4a1db1a7261420c}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">llvm::RegisterBankInfo::PartialMapping::PartialMapping (unsigned StartIdx, unsigned Length, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/registerbank">RegisterBank</a> &amp; RegBank)</td>
</tr>
</table>
</td>
<td class="doxyMemberLabelsRight">
<span class="doxyMemberLabels">
<span class="doxyMemberLabel inline">inline</span>
<span class="doxyMemberLabel constexpr">constexpr</span>
</span>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Provide a shortcut for quickly building <a href="/web-llvm/docs/api/structs/llvm/registerbankinfo/partialmapping">PartialMapping</a>.</p>

<p>Definition at line 66 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/codegen/registerbankinfo-h">RegisterBankInfo.h</a>.</p>


<p>References <a href="#afac28dfebeb6f31c2c87dd1acdcd038f">Length</a>, <a href="#ae78f517f813c1983db970736287379e1">RegBank</a> and <a href="#a0c55804243f2f158a9afa64f0f764c35">StartIdx</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Public Member Functions

### dump() {#ad6adb61747f6498e03e8169e79c4365f}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">LLVM_DUMP_METHOD void RegisterBankInfo::PartialMapping::dump ()</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Print this partial mapping on <a href="/web-llvm/docs/api/namespaces/llvm/#a7c46c742c31be54870e2038048e6b391">dbgs()</a> stream.</p>

<p>Declaration at line 75 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/codegen/registerbankinfo-h">RegisterBankInfo.h</a>, definition at line 517 of file <a href="/web-llvm/docs/api/files/lib/lib/codegen/registerbankinfo-cpp">RegisterBankInfo.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/namespaces/llvm/#a7c46c742c31be54870e2038048e6b391">llvm::dbgs</a>, <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/support/compiler-h/#aa863693eef567397d9c292da5bf22d34">LLVM_DUMP_METHOD</a> and <a href="#a047cd07201d30259f344dc3e0f94e040">print</a>.</p>

</div>
</div>

### getHighBitIdx() {#a6de81ad6fdab369c1e85c901b7f2e8d4}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">unsigned llvm::RegisterBankInfo::PartialMapping::getHighBitIdx ()</td>
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




<dl class="doxySectionUser">
<dt>Returns</dt>
<dd><p>the index of in the original value of the most significant bit that this partial mapping covers.</p></dd>
</dl>


<p>Definition at line 72 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/codegen/registerbankinfo-h">RegisterBankInfo.h</a>.</p>


<p>References <a href="#afac28dfebeb6f31c2c87dd1acdcd038f">Length</a> and <a href="#a0c55804243f2f158a9afa64f0f764c35">StartIdx</a>.</p>


<p>Referenced by <a href="#a047cd07201d30259f344dc3e0f94e040">print</a>, <a href="#aaee9b30ca4238627080ab0cb45ac28e6">verify</a> and <a href="/web-llvm/docs/api/structs/llvm/registerbankinfo/valuemapping/#a6778093ec4b236fadf3c13e2fe1e2ee9">llvm::RegisterBankInfo::ValueMapping::verify</a>.</p>

</div>
</div>

### print() {#a047cd07201d30259f344dc3e0f94e040}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void RegisterBankInfo::PartialMapping::print (<a href="/web-llvm/docs/api/classes/llvm/raw-ostream">raw_ostream</a> &amp; OS)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Print this partial mapping on <span class="doxyComputerOutput">OS</span>;.</p>

<p>Declaration at line 78 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/codegen/registerbankinfo-h">RegisterBankInfo.h</a>, definition at line 534 of file <a href="/web-llvm/docs/api/files/lib/lib/codegen/registerbankinfo-cpp">RegisterBankInfo.cpp</a>.</p>


<p>References <a href="#a6de81ad6fdab369c1e85c901b7f2e8d4">getHighBitIdx</a>, <a href="#ae78f517f813c1983db970736287379e1">RegBank</a> and <a href="#a0c55804243f2f158a9afa64f0f764c35">StartIdx</a>.</p>


<p>Referenced by <a href="#ad6adb61747f6498e03e8169e79c4365f">dump</a> and <a href="/web-llvm/docs/api/namespaces/llvm/#ab4cb97e6e305fd71bc5e8aa32add69d3">llvm::operator&lt;&lt;</a>.</p>

</div>
</div>

### verify() {#aaee9b30ca4238627080ab0cb45ac28e6}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool RegisterBankInfo::PartialMapping::verify (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/registerbankinfo">RegisterBankInfo</a> &amp; RBI)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p><a href="/web-llvm/docs/api/namespaces/llvm/check">Check</a> that the Mask is compatible with the RegBank.</p>


<p>Indeed, if the RegBank cannot accomadate the "active bits" of the mask, there is no way this mapping is valid.</p>



:::info
<p>This method does not check anything when assertions are disabled.</p>
:::


<dl class="doxySectionUser">
<dt>Returns</dt>
<dd><p>True is the check was successful.</p></dd>
</dl>


<p>Declaration at line 87 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/codegen/registerbankinfo-h">RegisterBankInfo.h</a>, definition at line 523 of file <a href="/web-llvm/docs/api/files/lib/lib/codegen/registerbankinfo-cpp">RegisterBankInfo.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/silowercontrolflow-cpp/#a4868c5d81c5ccc98c47aeab6244346a0">assert</a>, <a href="#a6de81ad6fdab369c1e85c901b7f2e8d4">getHighBitIdx</a>, <a href="/web-llvm/docs/api/classes/llvm/registerbankinfo/#a86c7cb8b065aaa7ceace9c9218ace573">llvm::RegisterBankInfo::getMaximumSize</a>, <a href="#afac28dfebeb6f31c2c87dd1acdcd038f">Length</a>, <a href="#ae78f517f813c1983db970736287379e1">RegBank</a>, <a href="/web-llvm/docs/api/classes/llvm/registerbankinfo/#aa9467bf23c0dfb8176a54358477962fa">llvm::RegisterBankInfo::RegisterBankInfo</a> and <a href="#a0c55804243f2f158a9afa64f0f764c35">StartIdx</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/structs/llvm/registerbankinfo/valuemapping/#a6778093ec4b236fadf3c13e2fe1e2ee9">llvm::RegisterBankInfo::ValueMapping::verify</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Public Member Attributes

### Length {#afac28dfebeb6f31c2c87dd1acdcd038f}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">unsigned llvm::RegisterBankInfo::PartialMapping::Length</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Length of this mapping in bits.</p>


<p>This is how many bits this partial mapping covers in the original value: from StartIdx to StartIdx + Length -1.</p>


<p>Definition at line 58 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/codegen/registerbankinfo-h">RegisterBankInfo.h</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/namespaces/llvm/arm/#ae9dd1e8c6c91a85d71bf41a59985d586">llvm::ARM::checkPartMapping</a>, <a href="/web-llvm/docs/api/classes/llvm/registerbankinfo/operandsmapper/#a6817453b853abea76fab37803ade6ef4">llvm::RegisterBankInfo::OperandsMapper::createVRegs</a>, <a href="/web-llvm/docs/api/classes/llvm/amdgpuregisterbankinfo/#ac390939d904c03a62f806bac6ae2626c">llvm::AMDGPURegisterBankInfo::getBreakDownCost</a>, <a href="#a6de81ad6fdab369c1e85c901b7f2e8d4">getHighBitIdx</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#ab214387d08c2431d183770f2599a347d">llvm::hash_value</a>, <a href="#a048ada9430cf3309d4a1db1a7261420c">PartialMapping</a>, <a href="/web-llvm/docs/api/classes/llvm/regbankselect/#ac8d8bb4999d968e0efc9555c2b178a83">llvm::RegBankSelect::repairReg</a> and <a href="#aaee9b30ca4238627080ab0cb45ac28e6">verify</a>.</p>

</div>
</div>

### RegBank {#ae78f517f813c1983db970736287379e1}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">const RegisterBank* llvm::RegisterBankInfo::PartialMapping::RegBank</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p><a href="/web-llvm/docs/api/classes/llvm/register">Register</a> bank where the partial value lives.</p>

<p>Definition at line 61 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/codegen/registerbankinfo-h">RegisterBankInfo.h</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/classes/llvm/regbankselect/#afc5c7be6a4fbeb70b07dde19d8ebc2fd">llvm::RegBankSelect::applyMapping</a>, <a href="/web-llvm/docs/api/classes/llvm/amdgpuregisterbankinfo/#a67457fbc2d167a5a1a18124bd446278f">llvm::AMDGPURegisterBankInfo::applyMappingBFE</a>, <a href="/web-llvm/docs/api/classes/llvm/amdgpuregisterbankinfo/#a66655fdd73a951d10ad6fb804f0fac98">llvm::AMDGPURegisterBankInfo::applyMappingImpl</a>, <a href="/web-llvm/docs/api/classes/llvm/amdgpuregisterbankinfo/#a87ac3f636dddf683cf1f9b7f1a60b1ae">llvm::AMDGPURegisterBankInfo::applyMappingLoad</a>, <a href="/web-llvm/docs/api/classes/llvm/amdgpuregisterbankinfo/#afb1a8a9ef7b460687963fb7968fb7626">llvm::AMDGPURegisterBankInfo::applyMappingSBufferLoad</a>, <a href="/web-llvm/docs/api/classes/llvm/regbankselect/#ac00dc73d1e42ba9d0e4f906e8b4edfd8">llvm::RegBankSelect::assignmentMatch</a>, <a href="/web-llvm/docs/api/namespaces/llvm/arm/#ae9dd1e8c6c91a85d71bf41a59985d586">llvm::ARM::checkPartMapping</a>, <a href="/web-llvm/docs/api/classes/llvm/registerbankinfo/operandsmapper/#a6817453b853abea76fab37803ade6ef4">llvm::RegisterBankInfo::OperandsMapper::createVRegs</a>, <a href="/web-llvm/docs/api/classes/llvm/amdgpuregisterbankinfo/#ac390939d904c03a62f806bac6ae2626c">llvm::AMDGPURegisterBankInfo::getBreakDownCost</a>, <a href="/web-llvm/docs/api/classes/llvm/regbankselect/#ac3cfa17f907e7258d898433ddfeb3fbf">llvm::RegBankSelect::getRepairCost</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#ab214387d08c2431d183770f2599a347d">llvm::hash_value</a>, <a href="#a048ada9430cf3309d4a1db1a7261420c">PartialMapping</a>, <a href="#a047cd07201d30259f344dc3e0f94e040">print</a> and <a href="#aaee9b30ca4238627080ab0cb45ac28e6">verify</a>.</p>

</div>
</div>

### StartIdx {#a0c55804243f2f158a9afa64f0f764c35}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">unsigned llvm::RegisterBankInfo::PartialMapping::StartIdx</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Number of bits at which this partial mapping starts in the original value.</p>


<p>The bits are counted from less significant bits to most significant bits.</p>


<p>Definition at line 53 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/codegen/registerbankinfo-h">RegisterBankInfo.h</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/namespaces/llvm/arm/#ae9dd1e8c6c91a85d71bf41a59985d586">llvm::ARM::checkPartMapping</a>, <a href="/web-llvm/docs/api/classes/llvm/amdgpuregisterbankinfo/#ac390939d904c03a62f806bac6ae2626c">llvm::AMDGPURegisterBankInfo::getBreakDownCost</a>, <a href="#a6de81ad6fdab369c1e85c901b7f2e8d4">getHighBitIdx</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#ab214387d08c2431d183770f2599a347d">llvm::hash_value</a>, <a href="#a048ada9430cf3309d4a1db1a7261420c">PartialMapping</a>, <a href="#a047cd07201d30259f344dc3e0f94e040">print</a>, <a href="#aaee9b30ca4238627080ab0cb45ac28e6">verify</a> and <a href="/web-llvm/docs/api/structs/llvm/registerbankinfo/valuemapping/#a6778093ec4b236fadf3c13e2fe1e2ee9">llvm::RegisterBankInfo::ValueMapping::verify</a>.</p>

</div>
</div>

</div>

<hr/>

The documentation for this struct was generated from the following files:

<ul>
<li><a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/codegen/registerbankinfo-h">RegisterBankInfo.h</a></li>
<li><a href="/web-llvm/docs/api/files/lib/lib/codegen/registerbankinfo-cpp">RegisterBankInfo.cpp</a></li>
</ul>

<hr/>

<p class="doxyGeneratedBy">Generated via <a href="https://xpack.github.io/doxygen2docusaurus">doxygen2docusaurus</a> 2.0.0 by <a href="https://www.doxygen.nl">Doxygen</a> 1.15.0.</p>

</div>
