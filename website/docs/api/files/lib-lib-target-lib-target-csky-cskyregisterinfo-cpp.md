---

# DO NOT EDIT!
# Automatically generated via doxygen2docusaurus by Doxygen.

slug: /api/files/lib/lib/target/lib/target/csky/cskyregisterinfo-cpp
custom_edit_url: null
toc_max_heading_level: 4
keywords:
  - doxygen
  - reference
  - file

---

<div class="doxyPage">

# The `CSKYRegisterInfo.cpp` File Reference



## Included Headers

<div class="doxyIncludesList">#include "<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/csky/cskyregisterinfo-h">CSKYRegisterInfo.h</a>"
#include "<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/csky/csky-h">CSKY.h</a>"
#include "<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/csky/cskysubtarget-h">CSKYSubtarget.h</a>"
#include "<a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/codegen/machineframeinfo-h">llvm/CodeGen/MachineFrameInfo.h</a>"
#include "<a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/codegen/machinefunction-h">llvm/CodeGen/MachineFunction.h</a>"
#include "<a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/codegen/registerscavenging-h">llvm/CodeGen/RegisterScavenging.h</a>"
#include "<a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/mc/mccontext-h">llvm/MC/MCContext.h</a>"
#include "CSKYGenRegisterInfo.inc"
</div>

## Functions Index

<table class="doxyMembersIndex">

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">static bool</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a76ab554cc4cdb60abb9d68fbd36dc2e6">IsLegalOffset</a> (const CSKYInstrInfo *TII, MachineInstr *MI, int &amp;Offset)</td>
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

## Macro Definitions Index

<table class="doxyMembersIndex">

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">#define</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a13b7359d3501128c4c130fd13756facc">GET_REGINFO_TARGET_DESC</a></td>
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

### IsLegalOffset() {#a76ab554cc4cdb60abb9d68fbd36dc2e6}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool IsLegalOffset (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/cskyinstrinfo">CSKYInstrInfo</a> * TII, <a href="/web-llvm/docs/api/classes/llvm/machineinstr">MachineInstr</a> * MI, int &amp; Offset)</td>
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



<p>Definition at line 108 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/csky/cskyregisterinfo-cpp">CSKYRegisterInfo.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/namespaces/llvm/cskyii/#a7c885c9b4b58e218f08493cac4b063a1a99f1a027f5463baeb6715f093d442211">llvm::CSKYII::AddrMode16B</a>, <a href="/web-llvm/docs/api/namespaces/llvm/cskyii/#a7c885c9b4b58e218f08493cac4b063a1ae00ccd16c4c437f2c7bce7514f64837b">llvm::CSKYII::AddrMode16H</a>, <a href="/web-llvm/docs/api/namespaces/llvm/cskyii/#a7c885c9b4b58e218f08493cac4b063a1a6c20caf417983da3a5f04afbb180e843">llvm::CSKYII::AddrMode16W</a>, <a href="/web-llvm/docs/api/namespaces/llvm/cskyii/#a7c885c9b4b58e218f08493cac4b063a1ab4a82e98c86e8b40c10a62fe46373df6">llvm::CSKYII::AddrMode32B</a>, <a href="/web-llvm/docs/api/namespaces/llvm/cskyii/#a7c885c9b4b58e218f08493cac4b063a1a22a48ca582683625d3909c733334838a">llvm::CSKYII::AddrMode32H</a>, <a href="/web-llvm/docs/api/namespaces/llvm/cskyii/#a7c885c9b4b58e218f08493cac4b063a1a3c0f8f5233f23065df1ab94ad78c5166">llvm::CSKYII::AddrMode32SDF</a>, <a href="/web-llvm/docs/api/namespaces/llvm/cskyii/#a7c885c9b4b58e218f08493cac4b063a1a11b19e3ae1624051aacf087d499fe247">llvm::CSKYII::AddrMode32WD</a>, <a href="/web-llvm/docs/api/namespaces/llvm/cskyii/#a292743075275955fa2fffa48be6c1c9dad09a641fcc2ffe8ed85f133acd924705">llvm::CSKYII::AddrModeMask</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/silowercontrolflow-cpp/#a4868c5d81c5ccc98c47aeab6244346a0">assert</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a87e65296f2a6d9570117a852af342764">llvm::isUInt</a>, <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/support/errorhandling-h/#ace243f5c25697a1107cce46626b3dc94">llvm_unreachable</a>, <a href="/web-llvm/docs/api/files/lib/lib/codegen/lib/codegen/globalisel/irtranslator-cpp/#abe44dfdea65b4f7e11e0a608ab708b76">MI</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a05f5b9a11bdcc5feba62899f95dcf878a3134224cba2545bc57954d3b072aebb4">llvm::Offset</a> and <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/hexagon/hexagoncopytocombine-cpp/#a1d40004718218dbdf06b496766299101">TII</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/classes/llvm/cskyregisterinfo/#ac8db545cfaf863844d25944e00814ba1">llvm::CSKYRegisterInfo::eliminateFrameIndex</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Macro Definitions

### GET\_REGINFO\_TARGET\_DESC {#a13b7359d3501128c4c130fd13756facc}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">#define GET_REGINFO_TARGET_DESC</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 21 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/csky/cskyregisterinfo-cpp">CSKYRegisterInfo.cpp</a>.</p>

</div>
</div>

</div>

<hr/>

<p class="doxyGeneratedBy">Generated via <a href="https://github.com/xpack/doxygen2docusaurus">doxygen2docusaurus</a> by <a href="https://www.doxygen.nl">Doxygen</a> 1.15.0.</p>

</div>
