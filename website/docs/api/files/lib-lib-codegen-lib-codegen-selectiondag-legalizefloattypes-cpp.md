---

# DO NOT EDIT!
# Automatically generated via doxygen2docusaurus by Doxygen.

slug: /api/files/lib/lib/codegen/lib/codegen/selectiondag/legalizefloattypes-cpp
custom_edit_url: null
toc_max_heading_level: 4
keywords:
  - doxygen
  - reference
  - file

---

<div class="doxyPage">

# `LegalizeFloatTypes.cpp` File



## Included Headers

<div class="doxyIncludesList">#include "<a href="/web-llvm/docs/api/files/lib/lib/codegen/lib/codegen/selectiondag/legalizetypes-h">LegalizeTypes.h</a>"
#include "<a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/analysis/targetlibraryinfo-h">llvm/Analysis/TargetLibraryInfo.h</a>"
#include "<a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/support/errorhandling-h">llvm/Support/ErrorHandling.h</a>"
#include "<a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/support/raw-ostream-h">llvm/Support/raw_ostream.h</a>"
</div>

## Functions Index

<table class="doxyMembersIndex">

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">static <a href="/web-llvm/docs/api/namespaces/llvm/rtlib/#a50a0bab21f1d14a86a1483ec283e4447">RTLIB::Libcall</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a58492714a9e09dae62ec55add9f1ec42">GetFPLibCall</a> (EVT VT, RTLIB::Libcall Call_F32, RTLIB::Libcall Call_F64, RTLIB::Libcall Call_F80, RTLIB::Libcall Call_F128, RTLIB::Libcall Call_PPCF128)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>GetFPLibCall - Return the right libcall for the given floating point type. <a href="#a58492714a9e09dae62ec55add9f1ec42">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">static <a href="/web-llvm/docs/api/namespaces/llvm/rtlib/#a50a0bab21f1d14a86a1483ec283e4447">RTLIB::Libcall</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a219666604b8d066914b87cdf21db4e21">findFPToIntLibcall</a> (EVT SrcVT, EVT RetVT, EVT &amp;Promoted, bool Signed)</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">static <a href="/web-llvm/docs/api/namespaces/llvm/isd/#a22ea9cec080dd5f4f47ba234c2f59110">ISD::NodeType</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a97ab080c0626f319bd2237326f1ebd19">GetPromotionOpcode</a> (EVT OpVT, EVT RetVT)</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">static <a href="/web-llvm/docs/api/namespaces/llvm/isd/#a22ea9cec080dd5f4f47ba234c2f59110">ISD::NodeType</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#abb4ca7a3f237c82c7dc9361d844c014d">GetPromotionOpcodeStrict</a> (EVT OpVT, EVT RetVT)</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ad78e062f62e0d6e453941fb4ca843e4d">DEBUG_TYPE</a>&nbsp;&nbsp;&nbsp;"legalize-types"</td>
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

### findFPToIntLibcall() {#a219666604b8d066914b87cdf21db4e21}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">RTLIB::Libcall findFPToIntLibcall (<a href="/web-llvm/docs/api/structs/llvm/evt">EVT</a> SrcVT, <a href="/web-llvm/docs/api/structs/llvm/evt">EVT</a> RetVT, <a href="/web-llvm/docs/api/structs/llvm/evt">EVT</a> &amp; Promoted, bool Signed)</td>
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



<p>Definition at line 1206 of file <a href="/web-llvm/docs/api/files/lib/lib/codegen/lib/codegen/selectiondag/legalizefloattypes-cpp">LegalizeFloatTypes.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/structs/llvm/evt/#aa994416d7190670c5fc0e295ebe6f6b0">llvm::EVT::bitsGE</a>, <a href="/web-llvm/docs/api/namespaces/llvm/rtlib/#aa70a6cd6c880ca47e604870efe33eba4">llvm::RTLIB::getFPTOSINT</a>, <a href="/web-llvm/docs/api/namespaces/llvm/rtlib/#a80e747e8b302cf5ad8e1d5ecade1937c">llvm::RTLIB::getFPTOUINT</a> and <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/nvptx/nvptxisellowering-cpp/#ae1a90b5d85643644483b2ca70da4d13faed3fa7a5efe80dad3ea3d86cc14be246">Signed</a>.</p>

</div>
</div>

### GetFPLibCall() {#a58492714a9e09dae62ec55add9f1ec42}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">RTLIB::Libcall GetFPLibCall (<a href="/web-llvm/docs/api/structs/llvm/evt">EVT</a> VT, <a href="/web-llvm/docs/api/namespaces/llvm/rtlib/#a50a0bab21f1d14a86a1483ec283e4447">RTLIB::Libcall</a> Call_F32, <a href="/web-llvm/docs/api/namespaces/llvm/rtlib/#a50a0bab21f1d14a86a1483ec283e4447">RTLIB::Libcall</a> Call_F64, <a href="/web-llvm/docs/api/namespaces/llvm/rtlib/#a50a0bab21f1d14a86a1483ec283e4447">RTLIB::Libcall</a> Call_F80, <a href="/web-llvm/docs/api/namespaces/llvm/rtlib/#a50a0bab21f1d14a86a1483ec283e4447">RTLIB::Libcall</a> Call_F128, <a href="/web-llvm/docs/api/namespaces/llvm/rtlib/#a50a0bab21f1d14a86a1483ec283e4447">RTLIB::Libcall</a> Call_PPCF128)</td>
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

<p>GetFPLibCall - Return the right libcall for the given floating point type.</p>


<p>FIXME: This is a local version of <a href="/web-llvm/docs/api/namespaces/llvm/rtlib/#aea94ed67dbfe2a4e0aa7121da40b0e94">RTLIB::getFPLibCall</a> that should be refactored away (see <a href="/web-llvm/docs/api/namespaces/llvm/rtlib/#a0616dff37f5666b8c8ab44b6a0e6c5b8">RTLIB::getPOWI</a> for an example).</p>


<p>Definition at line 32 of file <a href="/web-llvm/docs/api/files/lib/lib/codegen/lib/codegen/selectiondag/legalizefloattypes-cpp">LegalizeFloatTypes.cpp</a>.</p>

</div>
</div>

### GetPromotionOpcode() {#a97ab080c0626f319bd2237326f1ebd19}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">ISD::NodeType GetPromotionOpcode (<a href="/web-llvm/docs/api/structs/llvm/evt">EVT</a> OpVT, <a href="/web-llvm/docs/api/structs/llvm/evt">EVT</a> RetVT)</td>
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



<p>Definition at line 2469 of file <a href="/web-llvm/docs/api/files/lib/lib/codegen/lib/codegen/selectiondag/legalizefloattypes-cpp">LegalizeFloatTypes.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/namespaces/llvm/isd/#a22ea9cec080dd5f4f47ba234c2f59110abdae7178e801a788f47e55ad3db3ee6a">llvm::ISD::BF16_TO_FP</a>, <a href="/web-llvm/docs/api/namespaces/llvm/isd/#a22ea9cec080dd5f4f47ba234c2f59110a3e12fcc9960ef3bf0ae5876382d4c66f">llvm::ISD::FP16_TO_FP</a>, <a href="/web-llvm/docs/api/namespaces/llvm/isd/#a22ea9cec080dd5f4f47ba234c2f59110a0bb173b5a879225092abdeaba1394839">llvm::ISD::FP_TO_BF16</a>, <a href="/web-llvm/docs/api/namespaces/llvm/isd/#a22ea9cec080dd5f4f47ba234c2f59110a38f379e4fddf750c36f1323a04d12171">llvm::ISD::FP_TO_FP16</a> and <a href="/web-llvm/docs/api/namespaces/llvm/#a7f2a3d4dcfee70225988aec53ff1e173">llvm::report_fatal_error</a>.</p>

</div>
</div>

### GetPromotionOpcodeStrict() {#abb4ca7a3f237c82c7dc9361d844c014d}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">ISD::NodeType GetPromotionOpcodeStrict (<a href="/web-llvm/docs/api/structs/llvm/evt">EVT</a> OpVT, <a href="/web-llvm/docs/api/structs/llvm/evt">EVT</a> RetVT)</td>
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



<p>Definition at line 2481 of file <a href="/web-llvm/docs/api/files/lib/lib/codegen/lib/codegen/selectiondag/legalizefloattypes-cpp">LegalizeFloatTypes.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/namespaces/llvm/#a7f2a3d4dcfee70225988aec53ff1e173">llvm::report_fatal_error</a>, <a href="/web-llvm/docs/api/namespaces/llvm/isd/#a22ea9cec080dd5f4f47ba234c2f59110ab60b57f9ecb68fa5f4445ec18e835a64">llvm::ISD::STRICT_BF16_TO_FP</a>, <a href="/web-llvm/docs/api/namespaces/llvm/isd/#a22ea9cec080dd5f4f47ba234c2f59110a8be8417e323644ecd854ce67c362a850">llvm::ISD::STRICT_FP16_TO_FP</a>, <a href="/web-llvm/docs/api/namespaces/llvm/isd/#a22ea9cec080dd5f4f47ba234c2f59110ac98e3abb765d6786634ba0656ae83e17">llvm::ISD::STRICT_FP_TO_BF16</a> and <a href="/web-llvm/docs/api/namespaces/llvm/isd/#a22ea9cec080dd5f4f47ba234c2f59110a8a54f717e10fab9c9821196fc882cc11">llvm::ISD::STRICT_FP_TO_FP16</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Macro Definitions

### DEBUG\_TYPE {#ad78e062f62e0d6e453941fb4ca843e4d}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">#define DEBUG_TYPE&nbsp;&nbsp;&nbsp;"legalize-types"</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 27 of file <a href="/web-llvm/docs/api/files/lib/lib/codegen/lib/codegen/selectiondag/legalizefloattypes-cpp">LegalizeFloatTypes.cpp</a>.</p>

</div>
</div>

</div>

<hr/>

<p class="doxyGeneratedBy">Generated via <a href="https://github.com/xpack/doxygen2docusaurus">doxygen2docusaurus</a> by <a href="https://www.doxygen.nl">Doxygen</a> 1.15.0.</p>

</div>
