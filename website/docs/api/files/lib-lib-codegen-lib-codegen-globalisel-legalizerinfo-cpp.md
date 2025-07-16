---

# DO NOT EDIT!
# Automatically generated via doxygen2docusaurus by Doxygen.

slug: /api/files/lib/lib/codegen/lib/codegen/globalisel/legalizerinfo-cpp
custom_edit_url: null
toc_max_heading_level: 4
keywords:
  - doxygen
  - reference
  - file

---

<div class="doxyPage">

# The `LegalizerInfo.cpp` File Reference



## Included Headers

<div class="doxyIncludesList">#include "<a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/codegen/include/llvm/codegen/globalisel/legalizerinfo-h">llvm/CodeGen/GlobalISel/LegalizerInfo.h</a>"
#include "<a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/adt/smallbitvector-h">llvm/ADT/SmallBitVector.h</a>"
#include "<a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/codegen/machineinstr-h">llvm/CodeGen/MachineInstr.h</a>"
#include "<a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/codegen/machineoperand-h">llvm/CodeGen/MachineOperand.h</a>"
#include "<a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/codegen/machineregisterinfo-h">llvm/CodeGen/MachineRegisterInfo.h</a>"
#include "<a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/codegen/targetopcodes-h">llvm/CodeGen/TargetOpcodes.h</a>"
#include "<a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/codegentypes/lowleveltype-h">llvm/CodeGenTypes/LowLevelType.h</a>"
#include "<a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/mc/mcinstrdesc-h">llvm/MC/MCInstrDesc.h</a>"
#include "<a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/mc/mcinstrinfo-h">llvm/MC/MCInstrInfo.h</a>"
#include "<a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/support/debug-h">llvm/Support/Debug.h</a>"
#include "<a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/support/errorhandling-h">llvm/Support/ErrorHandling.h</a>"
#include &lt;algorithm&gt;
</div>

## Functions Index

<table class="doxyMembersIndex">

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">static bool</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a629547dc68b8b25d374ecd455b155fbc">hasNoSimpleLoops</a> (const LegalizeRule &amp;Rule, const LegalityQuery &amp;Q, const std::pair&lt; unsigned, LLT &gt; &amp;Mutation)</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ace2b635ecd7fc6de3eb1f8a95530d08d">mutationIsSane</a> (const LegalizeRule &amp;Rule, const LegalityQuery &amp;Q, std::pair&lt; unsigned, LLT &gt; Mutation)</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">static <a href="/web-llvm/docs/api/classes/llvm/llt">LLT</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a8e84947680117194867a596a56a354bd">getTypeFromTypeIdx</a> (const MachineInstr &amp;MI, const MachineRegisterInfo &amp;MRI, unsigned OpIdx, unsigned TypeIdx)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Helper function to get <a href="/web-llvm/docs/api/classes/llvm/llt">LLT</a> for the given type index. <a href="#a8e84947680117194867a596a56a354bd">More...</a></p>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ad78e062f62e0d6e453941fb4ca843e4d">DEBUG_TYPE</a>&nbsp;&nbsp;&nbsp;"legalizer-info"</td>
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

### getTypeFromTypeIdx() {#a8e84947680117194867a596a56a354bd}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">LLT getTypeFromTypeIdx (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/machineinstr">MachineInstr</a> &amp; MI, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/machineregisterinfo">MachineRegisterInfo</a> &amp; MRI, unsigned OpIdx, unsigned TypeIdx)</td>
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

<p>Helper function to get <a href="/web-llvm/docs/api/classes/llvm/llt">LLT</a> for the given type index.</p>

<p>Definition at line 257 of file <a href="/web-llvm/docs/api/files/lib/lib/codegen/lib/codegen/globalisel/legalizerinfo-cpp">LegalizerInfo.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/silowercontrolflow-cpp/#a4868c5d81c5ccc98c47aeab6244346a0">assert</a>, <a href="/web-llvm/docs/api/files/lib/lib/codegen/lib/codegen/globalisel/irtranslator-cpp/#abe44dfdea65b4f7e11e0a608ab708b76">MI</a> and <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64advsimdscalarpass-cpp/#aacd2ab195054a3e6a74bfbb9d5d571c8">MRI</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/classes/llvm/legalizerinfo/#a373eb03c4fdd576998906436ebe07001">llvm::LegalizerInfo::getAction</a>.</p>

</div>
</div>

### hasNoSimpleLoops() {#a629547dc68b8b25d374ecd455b155fbc}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool hasNoSimpleLoops (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/legalizerule">LegalizeRule</a> &amp; Rule, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/structs/llvm/legalityquery">LegalityQuery</a> &amp; Q, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> std::pair&lt; unsigned, <a href="/web-llvm/docs/api/classes/llvm/llt">LLT</a> &gt; &amp; Mutation)</td>
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



<p>Definition at line 95 of file <a href="/web-llvm/docs/api/files/lib/lib/codegen/lib/codegen/globalisel/legalizerinfo-cpp">LegalizerInfo.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/namespaces/llvm/legalizeactions/#a834a0e3032e20fe88a0c931e8f246654adbc4d3a46a3d7a515b5458a671394536">llvm::LegalizeActions::Custom</a>, <a href="/web-llvm/docs/api/namespaces/llvm/legalizeactions/#a834a0e3032e20fe88a0c931e8f246654a123b973f813232425a88cae2ef685a5a">llvm::LegalizeActions::FewerElements</a>, <a href="/web-llvm/docs/api/classes/llvm/legalizerule/#a842fdd54c667972d369854a4fa346755">llvm::LegalizeRule::getAction</a>, <a href="/web-llvm/docs/api/namespaces/llvm/irsimilarity/#af46430106334db52bfa7a4107e53a0bda8f7357506e00d8cd0694f948f909865d">llvm::IRSimilarity::Legal</a>, <a href="/web-llvm/docs/api/namespaces/llvm/legalizeactions/#a834a0e3032e20fe88a0c931e8f246654a1e5ed9cc15d3744694855efcdf0b948e">llvm::LegalizeActions::Libcall</a>, <a href="/web-llvm/docs/api/namespaces/llvm/legalizeactions/#a834a0e3032e20fe88a0c931e8f246654a5ff0dbefe0555c538e207b9ee20e26cf">llvm::LegalizeActions::Lower</a>, <a href="/web-llvm/docs/api/namespaces/llvm/legalizeactions/#a834a0e3032e20fe88a0c931e8f246654af7c712e88ef2300e4bc43089d1cdf3e5">llvm::LegalizeActions::MoreElements</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/powerpc/ppcvsxfmamutate-cpp/#a11cb5628e531251532f100309802a146">Mutation</a> and <a href="/web-llvm/docs/api/structs/llvm/legalityquery/#ab28fca6f8145be28b70ad89bb0c741b0">llvm::LegalityQuery::Types</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/classes/llvm/legalizeruleset/#af5b725eb16175a6ebbd75e53d6bc0d2c">llvm::LegalizeRuleSet::apply</a>.</p>

</div>
</div>

### mutationIsSane() {#ace2b635ecd7fc6de3eb1f8a95530d08d}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool mutationIsSane (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/legalizerule">LegalizeRule</a> &amp; Rule, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/structs/llvm/legalityquery">LegalityQuery</a> &amp; Q, std::pair&lt; unsigned, <a href="/web-llvm/docs/api/classes/llvm/llt">LLT</a> &gt; Mutation)</td>
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



<p>Definition at line 112 of file <a href="/web-llvm/docs/api/files/lib/lib/codegen/lib/codegen/globalisel/legalizerinfo-cpp">LegalizerInfo.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/namespaces/llvm/legalizeactions/#a834a0e3032e20fe88a0c931e8f246654ac37bb600575f12795f12c117b2d86740">llvm::LegalizeActions::Bitcast</a>, <a href="/web-llvm/docs/api/namespaces/llvm/legalizeactions/#a834a0e3032e20fe88a0c931e8f246654adbc4d3a46a3d7a515b5458a671394536">llvm::LegalizeActions::Custom</a>, <a href="/web-llvm/docs/api/namespaces/llvm/legalizeactions/#a834a0e3032e20fe88a0c931e8f246654a123b973f813232425a88cae2ef685a5a">llvm::LegalizeActions::FewerElements</a>, <a href="/web-llvm/docs/api/classes/llvm/legalizerule/#a842fdd54c667972d369854a4fa346755">llvm::LegalizeRule::getAction</a>, <a href="/web-llvm/docs/api/classes/llvm/llt/#aa911a7e9e51b7ed20810fc819efe6a26">llvm::LLT::getElementCount</a>, <a href="/web-llvm/docs/api/classes/llvm/elementcount/#a584cb8dfa0090b33a969c4dda27337f6">llvm::ElementCount::getFixed</a>, <a href="/web-llvm/docs/api/classes/llvm/llt/#a32472b5afd0ae6edb4a233a25056a6aa">llvm::LLT::getScalarSizeInBits</a>, <a href="/web-llvm/docs/api/classes/llvm/llt/#ae4165ca7bcbee300d5e9c065adcc1415">llvm::LLT::getScalarType</a>, <a href="/web-llvm/docs/api/classes/llvm/llt/#a956ffd0de93798f523683b447646dd92">llvm::LLT::getSizeInBits</a>, <a href="/web-llvm/docs/api/classes/llvm/details/fixedorscalablequantity/#afb486f9022a26e1cc53ff189710dbde5">llvm::details::FixedOrScalableQuantity&lt; ElementCount, unsigned &gt;::isKnownGE</a>, <a href="/web-llvm/docs/api/classes/llvm/details/fixedorscalablequantity/#a338ba7ca7a526243ab1853d07d90fe38">llvm::details::FixedOrScalableQuantity&lt; ElementCount, unsigned &gt;::isKnownLE</a>, <a href="/web-llvm/docs/api/classes/llvm/llt/#a7da5cc6e8aadd4d5fb6dd68f8ec12b7e">llvm::LLT::isVector</a>, <a href="/web-llvm/docs/api/namespaces/llvm/irsimilarity/#af46430106334db52bfa7a4107e53a0bda8f7357506e00d8cd0694f948f909865d">llvm::IRSimilarity::Legal</a>, <a href="/web-llvm/docs/api/namespaces/llvm/legalizeactions/#a834a0e3032e20fe88a0c931e8f246654af7c712e88ef2300e4bc43089d1cdf3e5">llvm::LegalizeActions::MoreElements</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/powerpc/ppcvsxfmamutate-cpp/#a11cb5628e531251532f100309802a146">Mutation</a>, <a href="/web-llvm/docs/api/namespaces/llvm/legalizeactions/#a834a0e3032e20fe88a0c931e8f246654ad0868c394d6503253b0d29c7e383e78b">llvm::LegalizeActions::NarrowScalar</a>, <a href="/web-llvm/docs/api/structs/llvm/legalityquery/#ab28fca6f8145be28b70ad89bb0c741b0">llvm::LegalityQuery::Types</a> and <a href="/web-llvm/docs/api/namespaces/llvm/legalizeactions/#a834a0e3032e20fe88a0c931e8f246654aad899913ed8431ad4b1c81f717f7a909">llvm::LegalizeActions::WidenScalar</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/classes/llvm/legalizeruleset/#af5b725eb16175a6ebbd75e53d6bc0d2c">llvm::LegalizeRuleSet::apply</a>.</p>

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
<td class="doxyMemberName">#define DEBUG_TYPE&nbsp;&nbsp;&nbsp;"legalizer-info"</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 30 of file <a href="/web-llvm/docs/api/files/lib/lib/codegen/lib/codegen/globalisel/legalizerinfo-cpp">LegalizerInfo.cpp</a>.</p>

</div>
</div>

</div>

<hr/>

<p class="doxyGeneratedBy">Generated via <a href="https://github.com/xpack/doxygen2docusaurus">doxygen2docusaurus</a> by <a href="https://www.doxygen.nl">Doxygen</a> 1.15.0.</p>

</div>
