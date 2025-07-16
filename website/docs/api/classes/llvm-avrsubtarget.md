---

# DO NOT EDIT!
# Automatically generated via doxygen2docusaurus by Doxygen.

slug: /api/classes/llvm/avrsubtarget
custom_edit_url: null
toc_max_heading_level: 4
keywords:
  - doxygen
  - reference
  - class

---

<div class="doxyPage">

# The `AVRSubtarget` Class Reference

<p>A specific <a href="/web-llvm/docs/api/namespaces/llvm/avr">AVR</a> target MCU. <a href="#details">More...</a></p>

## Declaration

<div class="doxyDeclaration">
class llvm::AVRSubtarget { ... }
</div>

## Included Headers

<div class="doxyIncludesList">#include "<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/avr/avrsubtarget-h">Target/AVR/AVRSubtarget.h</a>"
</div>

## Base class

<table class="doxyMembersIndex">

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">class</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="/web-llvm/docs/api/classes/avrgensubtargetinfo">AVRGenSubtargetInfo</a></td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ac466bcd3c4f3ff4bf4b100a8ee16ffdd">AVRSubtarget</a> (const Triple &amp;TT, const std::string &amp;CPU, const std::string &amp;FS, const AVRTargetMachine &amp;TM)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Creates an <a href="/web-llvm/docs/api/namespaces/llvm/avr">AVR</a> subtarget. <a href="#ac466bcd3c4f3ff4bf4b100a8ee16ffdd">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

</table>

## Public Member Functions Index

<table class="doxyMembersIndex">

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/avrinstrinfo">AVRInstrInfo</a> *</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a68197f257d323a42ac0143c2770e086d">getInstrInfo</a> () const override</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/targetframelowering">TargetFrameLowering</a> *</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a4d01ac0bdee1681bc7e2b977cf957af9">getFrameLowering</a> () const override</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/avrtargetlowering">AVRTargetLowering</a> *</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a9c8fd8b79bc0d2fad8e6e02473aa1a58">getTargetLowering</a> () const override</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/avrselectiondaginfo">AVRSelectionDAGInfo</a> *</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a863c1416df37ca7e5292a6b874f5da2d">getSelectionDAGInfo</a> () const override</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/avrregisterinfo">AVRRegisterInfo</a> *</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#afcfa7aba3fbf0b2fa321cecf07028e03">getRegisterInfo</a> () const override</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a832de1d5f542d96c1de19287a82e1329">ParseSubtargetFeatures</a> (StringRef CPU, StringRef TuneCPU, StringRef FS)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Parses a subtarget feature string, setting appropriate options. <a href="#a832de1d5f542d96c1de19287a82e1329">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/avrsubtarget">AVRSubtarget</a> &amp;</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ae69c346b74fe8a570faf35eb0be6fd79">initializeSubtargetDependencies</a> (StringRef CPU, StringRef FS, const TargetMachine &amp;TM)</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a0c423e38cffd1fd4979bc447c60b293f">getIORegisterOffset</a> () const</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a8a5a0198706bfc480c706209d64c9ff3">enableSubRegLiveness</a> () const override</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a154ae73cf1cb9914e5ab319fbf826e3a">getELFArch</a> () const</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Gets the <a href="/web-llvm/docs/api/namespaces/llvm/elf">ELF</a> architecture for the e_flags field of an <a href="/web-llvm/docs/api/namespaces/llvm/elf">ELF</a> object file. <a href="#a154ae73cf1cb9914e5ab319fbf826e3a">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">int</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a519a59b55a83f21b36a589a7eef6792a">getIORegRAMPZ</a> () const</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Get I/O register addresses. <a href="#a519a59b55a83f21b36a589a7eef6792a">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">int</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a7a6df9b893fb2dbba8a66206c1b7cb3c">getIORegEIND</a> () const</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a5d55520f73ade11f7ccbcbb286242e8d">getIORegSPL</a> () const</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#af9463e1f1a1aa687accd4e5c55a5c8e3">getIORegSPH</a> () const</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a6cc9be9e149d2abb36b36f32f1f54236">getIORegSREG</a> () const</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a5ef1dc63595d1d0b228bfa91faded9a2">getRegTmpIndex</a> () const</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Get GPR aliases. <a href="#a5ef1dc63595d1d0b228bfa91faded9a2">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">int</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a96bf006e836daf0b35679c6637801d09">getRegZeroIndex</a> () const</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a025f926b1640c8610bec3a052e58042a">getTmpRegister</a> () const</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a584960b0fd536f365fae55e2fa4f81a2">getZeroRegister</a> () const</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">unsigned</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a06a5c44febc83fbfe3a2a3dcf02ffaaa">ELFArch</a> = 0</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>The <a href="/web-llvm/docs/api/namespaces/llvm/elf">ELF</a> e_flags architecture. <a href="#a06a5c44febc83fbfe3a2a3dcf02ffaaa">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/avrinstrinfo">AVRInstrInfo</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ad79d94ac078fae504d964677fa469095">InstrInfo</a></td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/avrframelowering">AVRFrameLowering</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a923767d5d32d0186070e642cfb29e165">FrameLowering</a></td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/avrtargetlowering">AVRTargetLowering</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#acaa58201d13368f3b62b0ab0bc2d5be7">TLInfo</a></td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/avrselectiondaginfo">AVRSelectionDAGInfo</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a7aad7bd6b1ceaab48fc9e484f6cad907">TSInfo</a></td>
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

<p>A specific <a href="/web-llvm/docs/api/namespaces/llvm/avr">AVR</a> target MCU.</p>

<p>Definition at line 32 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/avr/avrsubtarget-h">AVRSubtarget.h</a>.</p>


<div class="doxySectionDef">

## Public Constructors

### AVRSubtarget() {#ac466bcd3c4f3ff4bf4b100a8ee16ffdd}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">llvm::AVRSubtarget::AVRSubtarget (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/triple">Triple</a> &amp; TT, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> std::string &amp; CPU, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> std::string &amp; FS, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/avrtargetmachine">AVRTargetMachine</a> &amp; TM)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Creates an <a href="/web-llvm/docs/api/namespaces/llvm/avr">AVR</a> subtarget.</p>


<dl class="doxyParamsList">
<dt class="doxyParamsTableTitle">Parameters</dt>
<dd>
<table class="doxyParamsTable">
<tr class="doxyParamItem">
<td class="doxyParamItemName">TT</td>
<td class="doxyParamItemDescription"><p>The target triple.</p></td>
</tr>
<tr class="doxyParamItem">
<td class="doxyParamItemName">CPU</td>
<td class="doxyParamItemDescription"><p>The CPU to target.</p></td>
</tr>
<tr class="doxyParamItem">
<td class="doxyParamItemName">FS</td>
<td class="doxyParamItemDescription"><p>The feature string.</p></td>
</tr>
<tr class="doxyParamItem">
<td class="doxyParamItemName">TM</td>
<td class="doxyParamItemDescription"><p>The target machine.</p></td>
</tr>
</table>
</dd>
</dl>

<p>Declaration at line 39 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/avr/avrsubtarget-h">AVRSubtarget.h</a>, definition at line 29 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/avr/avrsubtarget-cpp">AVRSubtarget.cpp</a>.</p>


<p>References <a href="#ae69c346b74fe8a570faf35eb0be6fd79">initializeSubtargetDependencies</a> and <a href="#a832de1d5f542d96c1de19287a82e1329">ParseSubtargetFeatures</a>.</p>


<p>Referenced by <a href="#a832de1d5f542d96c1de19287a82e1329">ParseSubtargetFeatures</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Public Member Functions

### enableSubRegLiveness() {#a8a5a0198706bfc480c706209d64c9ff3}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool llvm::AVRSubtarget::enableSubRegLiveness ()</td>
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



<p>Definition at line 70 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/avr/avrsubtarget-h">AVRSubtarget.h</a>.</p>

</div>
</div>

### getELFArch() {#a154ae73cf1cb9914e5ab319fbf826e3a}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">unsigned llvm::AVRSubtarget::getELFArch ()</td>
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

<p>Gets the <a href="/web-llvm/docs/api/namespaces/llvm/elf">ELF</a> architecture for the e_flags field of an <a href="/web-llvm/docs/api/namespaces/llvm/elf">ELF</a> object file.</p>

<p>Definition at line 74 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/avr/avrsubtarget-h">AVRSubtarget.h</a>.</p>


<p>Reference <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/silowercontrolflow-cpp/#a4868c5d81c5ccc98c47aeab6244346a0">assert</a>.</p>

</div>
</div>

### getFrameLowering() {#a4d01ac0bdee1681bc7e2b977cf957af9}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">const TargetFrameLowering * llvm::AVRSubtarget::getFrameLowering ()</td>
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



<p>Definition at line 43 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/avr/avrsubtarget-h">AVRSubtarget.h</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/namespaces/anonymous-avrexpandpseudoinsts-cpp-/#a7498bc4ad9bb17297a488ce7621b4e04">anonymous{AVRExpandPseudoInsts.cpp}::AVRExpandPseudo::expand&lt; AVR::STDSPQRr &gt;</a> and <a href="/web-llvm/docs/api/namespaces/anonymous-avrexpandpseudoinsts-cpp-/#ae050cc8421a02259268236bf0acca320">anonymous{AVRExpandPseudoInsts.cpp}::AVRExpandPseudo::expand&lt; AVR::STDWSPQRr &gt;</a>.</p>

</div>
</div>

### getInstrInfo() {#a68197f257d323a42ac0143c2770e086d}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">const AVRInstrInfo * llvm::AVRSubtarget::getInstrInfo ()</td>
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



<p>Definition at line 42 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/avr/avrsubtarget-h">AVRSubtarget.h</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/classes/llvm/avrframelowering/#a430f53d8e433993ae806a386a4870efc">llvm::AVRFrameLowering::eliminateCallFramePseudoInstr</a>, <a href="/web-llvm/docs/api/classes/llvm/avrframelowering/#a487d00503c99000990bb90458b08702c">llvm::AVRFrameLowering::emitEpilogue</a>, <a href="/web-llvm/docs/api/classes/llvm/avrframelowering/#a2b9b845d1b6461c8c99fbeed9984f757">llvm::AVRFrameLowering::emitPrologue</a>, <a href="/web-llvm/docs/api/classes/llvm/avrframelowering/#a8b418b49786b4eb1c06b0e407e346c01">llvm::AVRFrameLowering::restoreCalleeSavedRegisters</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#ab49c96f446ff54d9f4d51653b4542581">llvm::restoreStatusRegister</a>, <a href="/web-llvm/docs/api/classes/anonymous-avrexpandpseudoinsts-cpp-/avrexpandpseudo/#aba54307c769c172842accffb5c29e759">anonymous{AVRExpandPseudoInsts.cpp}::AVRExpandPseudo::runOnMachineFunction</a> and <a href="/web-llvm/docs/api/classes/llvm/avrframelowering/#af676cadcef1e3d4d159420f075a083da">llvm::AVRFrameLowering::spillCalleeSavedRegisters</a>.</p>

</div>
</div>

### getIORegEIND() {#a7a6df9b893fb2dbba8a66206c1b7cb3c}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">int llvm::AVRSubtarget::getIORegEIND ()</td>
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



<p>Definition at line 82 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/avr/avrsubtarget-h">AVRSubtarget.h</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/classes/llvm/avrasmprinter/#acd56f0ff4ca0b0bb54682c0e195c7589">llvm::AVRAsmPrinter::emitStartOfAsmFile</a>.</p>

</div>
</div>

### getIORegisterOffset() {#a0c423e38cffd1fd4979bc447c60b293f}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">uint8_t llvm::AVRSubtarget::getIORegisterOffset ()</td>
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



<p>Definition at line 68 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/avr/avrsubtarget-h">AVRSubtarget.h</a>.</p>

</div>
</div>

### getIORegRAMPZ() {#a519a59b55a83f21b36a589a7eef6792a}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">int llvm::AVRSubtarget::getIORegRAMPZ ()</td>
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

<p>Get I/O register addresses.</p>

<p>Definition at line 81 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/avr/avrsubtarget-h">AVRSubtarget.h</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/classes/llvm/avrasmprinter/#acd56f0ff4ca0b0bb54682c0e195c7589">llvm::AVRAsmPrinter::emitStartOfAsmFile</a>.</p>

</div>
</div>

### getIORegSPH() {#af9463e1f1a1aa687accd4e5c55a5c8e3}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">int llvm::AVRSubtarget::getIORegSPH ()</td>
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



<p>Definition at line 84 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/avr/avrsubtarget-h">AVRSubtarget.h</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/classes/llvm/avrasmprinter/#acd56f0ff4ca0b0bb54682c0e195c7589">llvm::AVRAsmPrinter::emitStartOfAsmFile</a>.</p>

</div>
</div>

### getIORegSPL() {#a5d55520f73ade11f7ccbcbb286242e8d}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">int llvm::AVRSubtarget::getIORegSPL ()</td>
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



<p>Definition at line 83 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/avr/avrsubtarget-h">AVRSubtarget.h</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/classes/llvm/avrasmprinter/#acd56f0ff4ca0b0bb54682c0e195c7589">llvm::AVRAsmPrinter::emitStartOfAsmFile</a>.</p>

</div>
</div>

### getIORegSREG() {#a6cc9be9e149d2abb36b36f32f1f54236}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">int llvm::AVRSubtarget::getIORegSREG ()</td>
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



<p>Definition at line 85 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/avr/avrsubtarget-h">AVRSubtarget.h</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/namespaces/anonymous-avrexpandpseudoinsts-cpp-/#a805f2e0106f53455754a4a20b7ec657e">anonymous{AVRExpandPseudoInsts.cpp}::AVRExpandPseudo::expand&lt; AVR::SPWRITE &gt;</a>, <a href="/web-llvm/docs/api/classes/llvm/avrregisterinfo/#a5846a629f1d7d7cc33ecf2a63319e14a">llvm::AVRRegisterInfo::eliminateFrameIndex</a>, <a href="/web-llvm/docs/api/classes/llvm/avrframelowering/#a2b9b845d1b6461c8c99fbeed9984f757">llvm::AVRFrameLowering::emitPrologue</a>, <a href="/web-llvm/docs/api/classes/llvm/avrasmprinter/#acd56f0ff4ca0b0bb54682c0e195c7589">llvm::AVRAsmPrinter::emitStartOfAsmFile</a> and <a href="/web-llvm/docs/api/namespaces/llvm/#ab49c96f446ff54d9f4d51653b4542581">llvm::restoreStatusRegister</a>.</p>

</div>
</div>

### getRegisterInfo() {#afcfa7aba3fbf0b2fa321cecf07028e03}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">const AVRRegisterInfo * llvm::AVRSubtarget::getRegisterInfo ()</td>
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



<p>Definition at line 52 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/avr/avrsubtarget-h">AVRSubtarget.h</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/classes/llvm/avrasmprinter/#abb1c33c814741adb78a9ff7f10ff3552">llvm::AVRAsmPrinter::PrintAsmOperand</a>, <a href="/web-llvm/docs/api/classes/anonymous-avrexpandpseudoinsts-cpp-/avrexpandpseudo/#aba54307c769c172842accffb5c29e759">anonymous{AVRExpandPseudoInsts.cpp}::AVRExpandPseudo::runOnMachineFunction</a> and <a href="/web-llvm/docs/api/classes/llvm/avrframelowering/#af676cadcef1e3d4d159420f075a083da">llvm::AVRFrameLowering::spillCalleeSavedRegisters</a>.</p>

</div>
</div>

### getRegTmpIndex() {#a5ef1dc63595d1d0b228bfa91faded9a2}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">int llvm::AVRSubtarget::getRegTmpIndex ()</td>
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

<p>Get GPR aliases.</p>

<p>Definition at line 88 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/avr/avrsubtarget-h">AVRSubtarget.h</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/classes/llvm/avrasmprinter/#acd56f0ff4ca0b0bb54682c0e195c7589">llvm::AVRAsmPrinter::emitStartOfAsmFile</a>.</p>

</div>
</div>

### getRegZeroIndex() {#a96bf006e836daf0b35679c6637801d09}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">int llvm::AVRSubtarget::getRegZeroIndex ()</td>
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



<p>Definition at line 89 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/avr/avrsubtarget-h">AVRSubtarget.h</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/classes/llvm/avrasmprinter/#acd56f0ff4ca0b0bb54682c0e195c7589">llvm::AVRAsmPrinter::emitStartOfAsmFile</a>.</p>

</div>
</div>

### getSelectionDAGInfo() {#a863c1416df37ca7e5292a6b874f5da2d}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">const AVRSelectionDAGInfo * llvm::AVRSubtarget::getSelectionDAGInfo ()</td>
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



<p>Definition at line 49 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/avr/avrsubtarget-h">AVRSubtarget.h</a>.</p>

</div>
</div>

### getTargetLowering() {#a9c8fd8b79bc0d2fad8e6e02473aa1a58}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">const AVRTargetLowering * llvm::AVRSubtarget::getTargetLowering ()</td>
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



<p>Definition at line 46 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/avr/avrsubtarget-h">AVRSubtarget.h</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/classes/anonymous-avriseldagtodag-cpp-/avrdagtodagisel/#af1389c2a1baf930223956103b615a838">anonymous{AVRISelDAGToDAG.cpp}::AVRDAGToDAGISel::SelectInlineAsmMemoryOperand</a>.</p>

</div>
</div>

### getTmpRegister() {#a025f926b1640c8610bec3a052e58042a}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">Register llvm::AVRSubtarget::getTmpRegister ()</td>
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



<p>Definition at line 91 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/avr/avrsubtarget-h">AVRSubtarget.h</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/namespaces/anonymous-avrexpandpseudoinsts-cpp-/#a805f2e0106f53455754a4a20b7ec657e">anonymous{AVRExpandPseudoInsts.cpp}::AVRExpandPseudo::expand&lt; AVR::SPWRITE &gt;</a>, <a href="/web-llvm/docs/api/classes/llvm/avrregisterinfo/#a5846a629f1d7d7cc33ecf2a63319e14a">llvm::AVRRegisterInfo::eliminateFrameIndex</a>, <a href="/web-llvm/docs/api/classes/llvm/avrframelowering/#a2b9b845d1b6461c8c99fbeed9984f757">llvm::AVRFrameLowering::emitPrologue</a> and <a href="/web-llvm/docs/api/namespaces/llvm/#ab49c96f446ff54d9f4d51653b4542581">llvm::restoreStatusRegister</a>.</p>

</div>
</div>

### getZeroRegister() {#a584960b0fd536f365fae55e2fa4f81a2}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">Register llvm::AVRSubtarget::getZeroRegister ()</td>
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



<p>Definition at line 94 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/avr/avrsubtarget-h">AVRSubtarget.h</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/classes/llvm/avrframelowering/#a2b9b845d1b6461c8c99fbeed9984f757">llvm::AVRFrameLowering::emitPrologue</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#ad64501a368789645f6f80afbce82da90">llvm::insertMultibyteShift</a> and <a href="/web-llvm/docs/api/namespaces/llvm/#ab49c96f446ff54d9f4d51653b4542581">llvm::restoreStatusRegister</a>.</p>

</div>
</div>

### initializeSubtargetDependencies() {#ae69c346b74fe8a570faf35eb0be6fd79}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">AVRSubtarget &amp; llvm::AVRSubtarget::initializeSubtargetDependencies (<a href="/web-llvm/docs/api/classes/llvm/stringref">StringRef</a> CPU, <a href="/web-llvm/docs/api/classes/llvm/stringref">StringRef</a> FS, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/targetmachine">TargetMachine</a> &amp; TM)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Declaration at line 60 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/avr/avrsubtarget-h">AVRSubtarget.h</a>, definition at line 38 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/avr/avrsubtarget-cpp">AVRSubtarget.cpp</a>.</p>


<p>Reference <a href="#a832de1d5f542d96c1de19287a82e1329">ParseSubtargetFeatures</a>.</p>


<p>Referenced by <a href="#ac466bcd3c4f3ff4bf4b100a8ee16ffdd">AVRSubtarget</a>.</p>

</div>
</div>

### ParseSubtargetFeatures() {#a832de1d5f542d96c1de19287a82e1329}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void llvm::AVRSubtarget::ParseSubtargetFeatures (<a href="/web-llvm/docs/api/classes/llvm/stringref">StringRef</a> CPU, <a href="/web-llvm/docs/api/classes/llvm/stringref">StringRef</a> TuneCPU, <a href="/web-llvm/docs/api/classes/llvm/stringref">StringRef</a> FS)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Parses a subtarget feature string, setting appropriate options.</p>



:::info
<p>Definition of function is auto generated by <span class="doxyComputerOutput">tblgen</span>.</p>
:::


<p>Definition at line 58 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/avr/avrsubtarget-h">AVRSubtarget.h</a>.</p>


<p>Reference <a href="#ac466bcd3c4f3ff4bf4b100a8ee16ffdd">AVRSubtarget</a>.</p>


<p>Referenced by <a href="#ac466bcd3c4f3ff4bf4b100a8ee16ffdd">AVRSubtarget</a> and <a href="#ae69c346b74fe8a570faf35eb0be6fd79">initializeSubtargetDependencies</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Private Member Attributes

### ELFArch {#a06a5c44febc83fbfe3a2a3dcf02ffaaa}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">unsigned llvm::AVRSubtarget::ELFArch = 0</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>The <a href="/web-llvm/docs/api/namespaces/llvm/elf">ELF</a> e_flags architecture.</p>

<p>Definition at line 100 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/avr/avrsubtarget-h">AVRSubtarget.h</a>.</p>

</div>
</div>

### FrameLowering {#a923767d5d32d0186070e642cfb29e165}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">AVRFrameLowering llvm::AVRSubtarget::FrameLowering</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 108 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/avr/avrsubtarget-h">AVRSubtarget.h</a>.</p>

</div>
</div>

### InstrInfo {#ad79d94ac078fae504d964677fa469095}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">AVRInstrInfo llvm::AVRSubtarget::InstrInfo</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 107 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/avr/avrsubtarget-h">AVRSubtarget.h</a>.</p>

</div>
</div>

### TLInfo {#acaa58201d13368f3b62b0ab0bc2d5be7}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">AVRTargetLowering llvm::AVRSubtarget::TLInfo</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 109 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/avr/avrsubtarget-h">AVRSubtarget.h</a>.</p>

</div>
</div>

### TSInfo {#a7aad7bd6b1ceaab48fc9e484f6cad907}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">AVRSelectionDAGInfo llvm::AVRSubtarget::TSInfo</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 110 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/avr/avrsubtarget-h">AVRSubtarget.h</a>.</p>

</div>
</div>

</div>

<hr/>

The documentation for this class was generated from the following files:

<ul>
<li><a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/avr/avrsubtarget-cpp">AVRSubtarget.cpp</a></li>
<li><a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/avr/avrsubtarget-h">AVRSubtarget.h</a></li>
</ul>

<hr/>

<p class="doxyGeneratedBy">Generated via <a href="https://github.com/xpack/doxygen2docusaurus">doxygen2docusaurus</a> by <a href="https://www.doxygen.nl">Doxygen</a> 1.15.0.</p>

</div>
