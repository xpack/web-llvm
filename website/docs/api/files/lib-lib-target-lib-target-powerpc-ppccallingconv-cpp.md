---

# DO NOT EDIT!
# Automatically generated via doxygen2docusaurus by Doxygen.

slug: /api/files/lib/lib/target/lib/target/powerpc/ppccallingconv-cpp
custom_edit_url: null
toc_max_heading_level: 4
keywords:
  - doxygen
  - reference
  - file

---

<div class="doxyPage">

# The `PPCCallingConv.cpp` File Reference



## Included Headers

<div class="doxyIncludesList">#include "<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/powerpc/ppccallingconv-h">PPCCallingConv.h</a>"
#include "<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/powerpc/ppcsubtarget-h">PPCSubtarget.h</a>"
#include "<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/powerpc/ppcccstate-h">PPCCCState.h</a>"
#include "PPCGenCallingConv.inc"
</div>

## Functions Index

<table class="doxyMembersIndex">

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">bool</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a671f96b9ff2ab136b28355da12359a4a">CC_PPC_AnyReg_Error</a> (unsigned &amp;, MVT &amp;, MVT &amp;, CCValAssign::LocInfo &amp;, ISD::ArgFlagsTy &amp;, CCState &amp;)</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a21db8f9e0318e72f5b8aa856aa52d8b7">CC_PPC64_ELF_Shadow_GPR_Regs</a> (unsigned &amp;ValNo, MVT &amp;ValVT, MVT &amp;LocVT, CCValAssign::LocInfo &amp;LocInfo, ISD::ArgFlagsTy &amp;ArgFlags, CCState &amp;State)</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#afdaa3d0bfed7c804a0acc4c3563ab0ae">CC_PPC32_SVR4_Custom_Dummy</a> (unsigned &amp;ValNo, MVT &amp;ValVT, MVT &amp;LocVT, CCValAssign::LocInfo &amp;LocInfo, ISD::ArgFlagsTy &amp;ArgFlags, CCState &amp;State)</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a248c0ef85aa77ccc7b334368cdfdcd1c">CC_PPC32_SVR4_Custom_AlignArgRegs</a> (unsigned &amp;ValNo, MVT &amp;ValVT, MVT &amp;LocVT, CCValAssign::LocInfo &amp;LocInfo, ISD::ArgFlagsTy &amp;ArgFlags, CCState &amp;State)</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a456c0f0e7d096d3ce2776259dc92eb4d">CC_PPC32_SVR4_Custom_SkipLastArgRegsPPCF128</a> (unsigned &amp;ValNo, MVT &amp;ValVT, MVT &amp;LocVT, CCValAssign::LocInfo &amp;LocInfo, ISD::ArgFlagsTy &amp;ArgFlags, CCState &amp;State)</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#adeb8a5810db34abafbc7292378d15255">CC_PPC32_SVR4_Custom_AlignFPArgRegs</a> (unsigned &amp;ValNo, MVT &amp;ValVT, MVT &amp;LocVT, CCValAssign::LocInfo &amp;LocInfo, ISD::ArgFlagsTy &amp;ArgFlags, CCState &amp;State)</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#aa881d2e727e6a14013435af6691a598e">CC_PPC32_SPE_CustomSplitFP64</a> (unsigned &amp;ValNo, MVT &amp;ValVT, MVT &amp;LocVT, CCValAssign::LocInfo &amp;LocInfo, ISD::ArgFlagsTy &amp;ArgFlags, CCState &amp;State)</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a7a5fa20ecc7b5d7b962f4591ed563c17">CC_PPC32_SPE_RetF64</a> (unsigned &amp;ValNo, MVT &amp;ValVT, MVT &amp;LocVT, CCValAssign::LocInfo &amp;LocInfo, ISD::ArgFlagsTy &amp;ArgFlags, CCState &amp;State)</td>
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

### CC\_PPC\_AnyReg\_Error() {#a671f96b9ff2ab136b28355da12359a4a}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool CC_PPC_AnyReg_Error (unsigned &amp;, <a href="/web-llvm/docs/api/classes/llvm/mvt">MVT</a> &amp;, <a href="/web-llvm/docs/api/classes/llvm/mvt">MVT</a> &amp;, <a href="/web-llvm/docs/api/classes/llvm/ccvalassign/#a2b78fd53da0b5df7bc4eacf7df556a45">CCValAssign::LocInfo</a> &amp;, <a href="/web-llvm/docs/api/structs/llvm/isd/argflagsty">ISD::ArgFlagsTy</a> &amp;, <a href="/web-llvm/docs/api/classes/llvm/ccstate">CCState</a> &amp;)</td>
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



<p>Definition at line 14 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/powerpc/ppccallingconv-cpp">PPCCallingConv.cpp</a>.</p>


<p>Reference <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/support/errorhandling-h/#ace243f5c25697a1107cce46626b3dc94">llvm_unreachable</a>.</p>

</div>
</div>

### CC\_PPC32\_SPE\_CustomSplitFP64() {#aa881d2e727e6a14013435af6691a598e}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool CC_PPC32_SPE_CustomSplitFP64 (unsigned &amp; ValNo, <a href="/web-llvm/docs/api/classes/llvm/mvt">MVT</a> &amp; ValVT, <a href="/web-llvm/docs/api/classes/llvm/mvt">MVT</a> &amp; LocVT, <a href="/web-llvm/docs/api/classes/llvm/ccvalassign/#a2b78fd53da0b5df7bc4eacf7df556a45">CCValAssign::LocInfo</a> &amp; LocInfo, <a href="/web-llvm/docs/api/structs/llvm/isd/argflagsty">ISD::ArgFlagsTy</a> &amp; ArgFlags, <a href="/web-llvm/docs/api/classes/llvm/ccstate">CCState</a> &amp; State)</td>
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



<p>Definition at line 144 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/powerpc/ppccallingconv-cpp">PPCCallingConv.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/silowercontrolflow-cpp/#a4868c5d81c5ccc98c47aeab6244346a0">assert</a>, <a href="/web-llvm/docs/api/classes/llvm/ccvalassign/#a3213a94802bb4f87a3e388af6cdd9d7f">llvm::CCValAssign::getCustomReg</a>, <a href="/web-llvm/docs/api/files/lib/lib/codegen/machinesink-cpp/#a359e1ff26f6d466d927a61aae45b05c3">Reg</a> and <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/mips/mips16isellowering-cpp/#a0acb682b8260ab1c60b918599864e2e5">T</a>.</p>

</div>
</div>

### CC\_PPC32\_SPE\_RetF64() {#a7a5fa20ecc7b5d7b962f4591ed563c17}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool CC_PPC32_SPE_RetF64 (unsigned &amp; ValNo, <a href="/web-llvm/docs/api/classes/llvm/mvt">MVT</a> &amp; ValVT, <a href="/web-llvm/docs/api/classes/llvm/mvt">MVT</a> &amp; LocVT, <a href="/web-llvm/docs/api/classes/llvm/ccvalassign/#a2b78fd53da0b5df7bc4eacf7df556a45">CCValAssign::LocInfo</a> &amp; LocInfo, <a href="/web-llvm/docs/api/structs/llvm/isd/argflagsty">ISD::ArgFlagsTy</a> &amp; ArgFlags, <a href="/web-llvm/docs/api/classes/llvm/ccstate">CCState</a> &amp; State)</td>
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



<p>Definition at line 173 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/powerpc/ppccallingconv-cpp">PPCCallingConv.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/classes/llvm/ccvalassign/#a3213a94802bb4f87a3e388af6cdd9d7f">llvm::CCValAssign::getCustomReg</a> and <a href="/web-llvm/docs/api/files/lib/lib/codegen/machinesink-cpp/#a359e1ff26f6d466d927a61aae45b05c3">Reg</a>.</p>

</div>
</div>

### CC\_PPC32\_SVR4\_Custom\_AlignArgRegs() {#a248c0ef85aa77ccc7b334368cdfdcd1c}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool CC_PPC32_SVR4_Custom_AlignArgRegs (unsigned &amp; ValNo, <a href="/web-llvm/docs/api/classes/llvm/mvt">MVT</a> &amp; ValVT, <a href="/web-llvm/docs/api/classes/llvm/mvt">MVT</a> &amp; LocVT, <a href="/web-llvm/docs/api/classes/llvm/ccvalassign/#a2b78fd53da0b5df7bc4eacf7df556a45">CCValAssign::LocInfo</a> &amp; LocInfo, <a href="/web-llvm/docs/api/structs/llvm/isd/argflagsty">ISD::ArgFlagsTy</a> &amp; ArgFlags, <a href="/web-llvm/docs/api/classes/llvm/ccstate">CCState</a> &amp; State)</td>
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



<p>Definition at line 66 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/powerpc/ppccallingconv-cpp">PPCCallingConv.cpp</a>.</p>

</div>
</div>

### CC\_PPC32\_SVR4\_Custom\_AlignFPArgRegs() {#adeb8a5810db34abafbc7292378d15255}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool CC_PPC32_SVR4_Custom_AlignFPArgRegs (unsigned &amp; ValNo, <a href="/web-llvm/docs/api/classes/llvm/mvt">MVT</a> &amp; ValVT, <a href="/web-llvm/docs/api/classes/llvm/mvt">MVT</a> &amp; LocVT, <a href="/web-llvm/docs/api/classes/llvm/ccvalassign/#a2b78fd53da0b5df7bc4eacf7df556a45">CCValAssign::LocInfo</a> &amp; LocInfo, <a href="/web-llvm/docs/api/structs/llvm/isd/argflagsty">ISD::ArgFlagsTy</a> &amp; ArgFlags, <a href="/web-llvm/docs/api/classes/llvm/ccstate">CCState</a> &amp; State)</td>
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



<p>Definition at line 116 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/powerpc/ppccallingconv-cpp">PPCCallingConv.cpp</a>.</p>

</div>
</div>

### CC\_PPC32\_SVR4\_Custom\_Dummy() {#afdaa3d0bfed7c804a0acc4c3563ab0ae}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool CC_PPC32_SVR4_Custom_Dummy (unsigned &amp; ValNo, <a href="/web-llvm/docs/api/classes/llvm/mvt">MVT</a> &amp; ValVT, <a href="/web-llvm/docs/api/classes/llvm/mvt">MVT</a> &amp; LocVT, <a href="/web-llvm/docs/api/classes/llvm/ccvalassign/#a2b78fd53da0b5df7bc4eacf7df556a45">CCValAssign::LocInfo</a> &amp; LocInfo, <a href="/web-llvm/docs/api/structs/llvm/isd/argflagsty">ISD::ArgFlagsTy</a> &amp; ArgFlags, <a href="/web-llvm/docs/api/classes/llvm/ccstate">CCState</a> &amp; State)</td>
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



<p>Definition at line 59 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/powerpc/ppccallingconv-cpp">PPCCallingConv.cpp</a>.</p>

</div>
</div>

### CC\_PPC32\_SVR4\_Custom\_SkipLastArgRegsPPCF128() {#a456c0f0e7d096d3ce2776259dc92eb4d}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool CC_PPC32_SVR4_Custom_SkipLastArgRegsPPCF128 (unsigned &amp; ValNo, <a href="/web-llvm/docs/api/classes/llvm/mvt">MVT</a> &amp; ValVT, <a href="/web-llvm/docs/api/classes/llvm/mvt">MVT</a> &amp; LocVT, <a href="/web-llvm/docs/api/classes/llvm/ccvalassign/#a2b78fd53da0b5df7bc4eacf7df556a45">CCValAssign::LocInfo</a> &amp; LocInfo, <a href="/web-llvm/docs/api/structs/llvm/isd/argflagsty">ISD::ArgFlagsTy</a> &amp; ArgFlags, <a href="/web-llvm/docs/api/classes/llvm/ccstate">CCState</a> &amp; State)</td>
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



<p>Definition at line 93 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/powerpc/ppccallingconv-cpp">PPCCallingConv.cpp</a>.</p>

</div>
</div>

### CC\_PPC64\_ELF\_Shadow\_GPR\_Regs() {#a21db8f9e0318e72f5b8aa856aa52d8b7}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool CC_PPC64_ELF_Shadow_GPR_Regs (unsigned &amp; ValNo, <a href="/web-llvm/docs/api/classes/llvm/mvt">MVT</a> &amp; ValVT, <a href="/web-llvm/docs/api/classes/llvm/mvt">MVT</a> &amp; LocVT, <a href="/web-llvm/docs/api/classes/llvm/ccvalassign/#a2b78fd53da0b5df7bc4eacf7df556a45">CCValAssign::LocInfo</a> &amp; LocInfo, <a href="/web-llvm/docs/api/structs/llvm/isd/argflagsty">ISD::ArgFlagsTy</a> &amp; ArgFlags, <a href="/web-llvm/docs/api/classes/llvm/ccstate">CCState</a> &amp; State)</td>
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



<p>Definition at line 26 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/powerpc/ppccallingconv-cpp">PPCCallingConv.cpp</a>.</p>


<p>Reference <a href="/web-llvm/docs/api/classes/llvm/mvt/#a0c1ae89f2c2765a979f999ecdc11304c">llvm::MVT::is128BitVector</a>.</p>

</div>
</div>

</div>

<hr/>

<p class="doxyGeneratedBy">Generated via <a href="https://github.com/xpack/doxygen2docusaurus">doxygen2docusaurus</a> by <a href="https://www.doxygen.nl">Doxygen</a> 1.15.0.</p>

</div>
