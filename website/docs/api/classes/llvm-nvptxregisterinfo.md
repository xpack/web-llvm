---

# DO NOT EDIT!
# Automatically generated via doxygen2docusaurus by Doxygen.

slug: /api/classes/llvm/nvptxregisterinfo
custom_edit_url: null
toc_max_heading_level: 4
keywords:
  - doxygen
  - reference
  - class

---

<div class="doxyPage">

# `NVPTXRegisterInfo` Class



## Declaration

<div class="doxyDeclaration">
class llvm::NVPTXRegisterInfo { ... }
</div>

## Included Headers

<div class="doxyIncludesList">#include "<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/nvptx/nvptxregisterinfo-h">Target/NVPTX/NVPTXRegisterInfo.h</a>"
</div>

## Base class

<table class="doxyMembersIndex">

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">class</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="/web-llvm/docs/api/classes/nvptxgenregisterinfo">NVPTXGenRegisterInfo</a></td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#acb97b235299d7b9a39b77a5ecee32bff">NVPTXRegisterInfo</a> ()</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/namespaces/llvm/#aad72cfbb210808985a9dc19f4e5d8542">MCPhysReg</a> *</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a5490ca5d24638e92301b86bff5d6b239">getCalleeSavedRegs</a> (const MachineFunction *MF) const override</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p><a href="/web-llvm/docs/api/namespaces/llvm/nvptx">NVPTX</a> Callee Saved Registers. <a href="#a5490ca5d24638e92301b86bff5d6b239">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/bitvector">BitVector</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a9de87011bca72add5b7fc77d76459c15">getReservedRegs</a> (const MachineFunction &amp;MF) const override</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a682aaf1662c79a3be4911c51eebd8cdf">eliminateFrameIndex</a> (MachineBasicBlock::iterator MI, int SPAdj, unsigned FIOperandNum, RegScavenger *RS=nullptr) const override</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/register">Register</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ae2f5ece1b06cfd17affe66011423b306">getFrameRegister</a> (const MachineFunction &amp;MF) const override</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/register">Register</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a4eb67642b89e53f4413509a2d5a32915">getFrameLocalRegister</a> (const MachineFunction &amp;MF) const</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/uniquestringsaver">UniqueStringSaver</a> &amp;</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ac56b5cbfcdd8e93ae59c377e0fdb1435">getStrPool</a> () const</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> char *</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a11f68a471f467af9babb2ba236bcf1d9">getName</a> (unsigned RegNo) const</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a6b4972eff902518ef535018579cf0bb7">addToDebugRegisterMap</a> (uint64_t preEncodedVirtualRegister, std::string registerName) const</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a11ad79519e5b7b2729da9080d0c4c003">clearDebugRegisterMap</a> () const</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">int64_t</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ae271370eae878e78d2bad43aa2d68e1d">getDwarfRegNum</a> (MCRegister RegNum, bool isEH) const override</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/namespaces/llvm/#a8e612822d4ba7bb36c9c79582a567108">BumpPtrAllocator</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#afb414e1c2ae1975d704f3496d1d5dfed">StrAlloc</a></td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/uniquestringsaver">UniqueStringSaver</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a9bb61e4c4baab9c63efdb8d02e994e97">StrPool</a></td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/densemap">DenseMap</a>&lt; uint64_t, uint64_t &gt;</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#abdef4ae44d2bacdec33820493cc3af4c">debugRegisterMap</a></td>
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


<p>Definition at line 24 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/nvptx/nvptxregisterinfo-h">NVPTXRegisterInfo.h</a>.</p>


<div class="doxySectionDef">

## Public Constructors

### NVPTXRegisterInfo() {#acb97b235299d7b9a39b77a5ecee32bff}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">NVPTXRegisterInfo::NVPTXRegisterInfo ()</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Declaration at line 35 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/nvptx/nvptxregisterinfo-h">NVPTXRegisterInfo.h</a>, definition at line 86 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/nvptx/nvptxregisterinfo-cpp">NVPTXRegisterInfo.cpp</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Public Member Functions

### addToDebugRegisterMap() {#a6b4972eff902518ef535018579cf0bb7}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void NVPTXRegisterInfo::addToDebugRegisterMap (uint64_t preEncodedVirtualRegister, std::string registerName)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Declaration at line 71 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/nvptx/nvptxregisterinfo-h">NVPTXRegisterInfo.h</a>, definition at line 165 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/nvptx/nvptxregisterinfo-cpp">NVPTXRegisterInfo.cpp</a>.</p>


<p>Reference <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/nvptx/nvptxregisterinfo-cpp/#aab8b72686fab99a218789ee582f09c6b">encodeRegisterForDwarf</a>.</p>

</div>
</div>

### clearDebugRegisterMap() {#a11ad79519e5b7b2729da9080d0c4c003}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void NVPTXRegisterInfo::clearDebugRegisterMap ()</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Declaration at line 73 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/nvptx/nvptxregisterinfo-h">NVPTXRegisterInfo.h</a>, definition at line 143 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/nvptx/nvptxregisterinfo-cpp">NVPTXRegisterInfo.cpp</a>.</p>

</div>
</div>

### eliminateFrameIndex() {#a682aaf1662c79a3be4911c51eebd8cdf}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool NVPTXRegisterInfo::eliminateFrameIndex (<a href="/web-llvm/docs/api/classes/llvm/machinebasicblock/#ae34c996b58df9b9ce6695a0c8b70c533">MachineBasicBlock::iterator</a> MI, int SPAdj, unsigned FIOperandNum, <a href="/web-llvm/docs/api/classes/llvm/regscavenger">RegScavenger</a> * RS=nullptr)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Declaration at line 46 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/nvptx/nvptxregisterinfo-h">NVPTXRegisterInfo.h</a>, definition at line 112 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/nvptx/nvptxregisterinfo-cpp">NVPTXRegisterInfo.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/silowercontrolflow-cpp/#a4868c5d81c5ccc98c47aeab6244346a0">assert</a>, <a href="/web-llvm/docs/api/classes/llvm/machinefunction/#a54f334a9c8ca6d105eae383ae87e4524">llvm::MachineFunction::getFrameInfo</a>, <a href="#ae2f5ece1b06cfd17affe66011423b306">getFrameRegister</a>, <a href="/web-llvm/docs/api/classes/llvm/machineframeinfo/#adf98860d7f42290f873c82a981eb0ea6">llvm::MachineFrameInfo::getObjectOffset</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/nvptx/nvvmintrrange-cpp/#ac5804672fc0850438d63caec770647f8">II</a>, <a href="/web-llvm/docs/api/files/lib/lib/codegen/lib/codegen/globalisel/irtranslator-cpp/#abe44dfdea65b4f7e11e0a608ab708b76">MI</a> and <a href="/web-llvm/docs/api/namespaces/llvm/#a05f5b9a11bdcc5feba62899f95dcf878a3134224cba2545bc57954d3b072aebb4">llvm::Offset</a>.</p>

</div>
</div>

### getCalleeSavedRegs() {#a5490ca5d24638e92301b86bff5d6b239}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">const MCPhysReg * NVPTXRegisterInfo::getCalleeSavedRegs (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/machinefunction">MachineFunction</a> * MF)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p><a href="/web-llvm/docs/api/namespaces/llvm/nvptx">NVPTX</a> Callee Saved Registers.</p>

<p>Declaration at line 42 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/nvptx/nvptxregisterinfo-h">NVPTXRegisterInfo.h</a>, definition at line 94 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/nvptx/nvptxregisterinfo-cpp">NVPTXRegisterInfo.cpp</a>.</p>

</div>
</div>

### getDwarfRegNum() {#ae271370eae878e78d2bad43aa2d68e1d}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">int64_t NVPTXRegisterInfo::getDwarfRegNum (<a href="/web-llvm/docs/api/classes/llvm/mcregister">MCRegister</a> RegNum, bool isEH)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Declaration at line 74 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/nvptx/nvptxregisterinfo-h">NVPTXRegisterInfo.h</a>, definition at line 173 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/nvptx/nvptxregisterinfo-cpp">NVPTXRegisterInfo.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/nvptx/nvptxregisterinfo-cpp/#aab8b72686fab99a218789ee582f09c6b">encodeRegisterForDwarf</a>, <a href="/web-llvm/docs/api/classes/llvm/nvptxinstprinter/#aa021e0896ced10e79b81454e4186a7f2">llvm::NVPTXInstPrinter::getRegisterName</a>, <a href="/web-llvm/docs/api/classes/llvm/mcregister/#af8403cc977c65b910e618ebcb6a12c32">llvm::MCRegister::id</a>, <a href="/web-llvm/docs/api/classes/llvm/mcregister/#adab6a6e130a565c2cb11ef465fac90e7">llvm::MCRegister::isPhysical</a>, <a href="/web-llvm/docs/api/files/lib/lib/debuginfo/lib/debuginfo/gsym/inlineinfo-cpp/#a5db99f4b7f8744e0b1c8b50dba8ec5a2">lookup</a> and <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/smeabipass-cpp/#a8f8f80d37794cde9472343e4487ba3eb">name</a>.</p>

</div>
</div>

### getFrameLocalRegister() {#a4eb67642b89e53f4413509a2d5a32915}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">Register NVPTXRegisterInfo::getFrameLocalRegister (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/machinefunction">MachineFunction</a> &amp; MF)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Declaration at line 51 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/nvptx/nvptxregisterinfo-h">NVPTXRegisterInfo.h</a>, definition at line 137 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/nvptx/nvptxregisterinfo-cpp">NVPTXRegisterInfo.cpp</a>.</p>


<p>Reference <a href="/web-llvm/docs/api/classes/llvm/machinefunction/#af777ff93c9e07a6ff5ffe3226deb3e76">llvm::MachineFunction::getTarget</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/nvptx/nvptxpeephole-cpp/#ae48b9308a21e92c2301831dfc8d75ac9">CombineCVTAToLocal</a> and <a href="/web-llvm/docs/api/classes/llvm/nvptxframelowering/#aad707aff5fcbdc8180deb9e6695f0c32">llvm::NVPTXFrameLowering::emitPrologue</a>.</p>

</div>
</div>

### getFrameRegister() {#ae2f5ece1b06cfd17affe66011423b306}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">Register NVPTXRegisterInfo::getFrameRegister (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/machinefunction">MachineFunction</a> &amp; MF)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Declaration at line 50 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/nvptx/nvptxregisterinfo-h">NVPTXRegisterInfo.h</a>, definition at line 130 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/nvptx/nvptxregisterinfo-cpp">NVPTXRegisterInfo.cpp</a>.</p>


<p>Reference <a href="/web-llvm/docs/api/classes/llvm/machinefunction/#af777ff93c9e07a6ff5ffe3226deb3e76">llvm::MachineFunction::getTarget</a>.</p>


<p>Referenced by <a href="#a682aaf1662c79a3be4911c51eebd8cdf">eliminateFrameIndex</a>, <a href="/web-llvm/docs/api/classes/llvm/nvptxframelowering/#aad707aff5fcbdc8180deb9e6695f0c32">llvm::NVPTXFrameLowering::emitPrologue</a> and <a href="/web-llvm/docs/api/structs/anonymous-nvptxpeephole-cpp-/nvptxpeephole/#af04bad5ec6853f7eed479f1080ec99a3">anonymous{NVPTXPeephole.cpp}::NVPTXPeephole::runOnMachineFunction</a>.</p>

</div>
</div>

### getName() {#a11f68a471f467af9babb2ba236bcf1d9}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">const char * llvm::NVPTXRegisterInfo::getName (unsigned RegNo)</td>
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



<p>Definition at line 57 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/nvptx/nvptxregisterinfo-h">NVPTXRegisterInfo.h</a>.</p>


<p>References <a href="/web-llvm/docs/api/classes/llvm/stringref/#a7b0fa1a82461032cdf16b7f6c59f0a6a">llvm::StringRef::data</a>, <a href="#ac56b5cbfcdd8e93ae59c377e0fdb1435">getStrPool</a> and <a href="/web-llvm/docs/api/classes/llvm/uniquestringsaver/#aaa37b5fdb34477a1eb3361f7ee9717f3">llvm::UniqueStringSaver::save</a>.</p>

</div>
</div>

### getReservedRegs() {#a9de87011bca72add5b7fc77d76459c15}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">BitVector NVPTXRegisterInfo::getReservedRegs (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/machinefunction">MachineFunction</a> &amp; MF)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Declaration at line 44 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/nvptx/nvptxregisterinfo-h">NVPTXRegisterInfo.h</a>, definition at line 99 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/nvptx/nvptxregisterinfo-cpp">NVPTXRegisterInfo.cpp</a>.</p>


<p>Reference <a href="/web-llvm/docs/api/namespaces/llvm/#a8c9d5a3046b96979a032c218e858cd15a942d4e37dd5607ab68e54755540d4a47">llvm::Reserved</a>.</p>

</div>
</div>

### getStrPool() {#ac56b5cbfcdd8e93ae59c377e0fdb1435}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">UniqueStringSaver &amp; llvm::NVPTXRegisterInfo::getStrPool ()</td>
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



<p>Definition at line 53 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/nvptx/nvptxregisterinfo-h">NVPTXRegisterInfo.h</a>.</p>


<p>Referenced by <a href="#a11f68a471f467af9babb2ba236bcf1d9">getName</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Private Member Attributes

### debugRegisterMap {#abdef4ae44d2bacdec33820493cc3af4c}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">DenseMap&lt;uint64_t, uint64_t&gt; llvm::NVPTXRegisterInfo::debugRegisterMap</td>
</tr>
</table>
</td>
<td class="doxyMemberLabelsRight">
<span class="doxyMemberLabels">
<span class="doxyMemberLabel mutable">mutable</span>
</span>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 32 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/nvptx/nvptxregisterinfo-h">NVPTXRegisterInfo.h</a>.</p>

</div>
</div>

### StrAlloc {#afb414e1c2ae1975d704f3496d1d5dfed}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">BumpPtrAllocator llvm::NVPTXRegisterInfo::StrAlloc</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 27 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/nvptx/nvptxregisterinfo-h">NVPTXRegisterInfo.h</a>.</p>

</div>
</div>

### StrPool {#a9bb61e4c4baab9c63efdb8d02e994e97}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">UniqueStringSaver llvm::NVPTXRegisterInfo::StrPool</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 28 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/nvptx/nvptxregisterinfo-h">NVPTXRegisterInfo.h</a>.</p>

</div>
</div>

</div>

<hr/>

The documentation for this class was generated from the following files:

<ul>
<li><a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/nvptx/nvptxregisterinfo-cpp">NVPTXRegisterInfo.cpp</a></li>
<li><a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/nvptx/nvptxregisterinfo-h">NVPTXRegisterInfo.h</a></li>
</ul>

<hr/>

<p class="doxyGeneratedBy">Generated via <a href="https://github.com/xpack/doxygen2docusaurus">doxygen2docusaurus</a> by <a href="https://www.doxygen.nl">Doxygen</a> 1.15.0.</p>

</div>
