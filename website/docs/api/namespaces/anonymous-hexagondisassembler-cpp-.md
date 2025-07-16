---

# DO NOT EDIT!
# Automatically generated via doxygen2docusaurus by Doxygen.

slug: /api/namespaces/anonymous-hexagondisassembler-cpp-
custom_edit_url: null
toc_max_heading_level: 4
keywords:
  - doxygen
  - reference
  - namespace

---

<div class="doxyPage">

# The `anonymous{HexagonDisassembler.cpp}` Namespace Reference



## Definition

<div class="doxyDefinition">
namespace anonymous{HexagonDisassembler.cpp} { ... }
</div>

## Classes Index

<table class="doxyMembersIndex">

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">class</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="/web-llvm/docs/api/classes/anonymous-hexagondisassembler-cpp-/hexagondisassembler">HexagonDisassembler</a></td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p><a href="/web-llvm/docs/api/namespaces/llvm/hexagon">Hexagon</a> disassembler for all <a href="/web-llvm/docs/api/namespaces/llvm/hexagon">Hexagon</a> platforms. <a href="/web-llvm/docs/api/classes/anonymous-hexagondisassembler-cpp-/hexagondisassembler/#details">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

</table>

## Functions Index

<table class="doxyMembersIndex">

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">static uint64_t</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a2e0e4ab18e7fb56c7dbd46fe864243e6">fullValue</a> (HexagonDisassembler const &amp;Disassembler, MCInst &amp;MI, int64_t Value)</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">static <a href="/web-llvm/docs/api/classes/anonymous-hexagondisassembler-cpp-/hexagondisassembler">HexagonDisassembler</a> <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> &amp;</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a286150b949c366f38d99bcf292053cf0">disassembler</a> (const MCDisassembler *Decoder)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexTemplate">
<td class="doxyMemberIndexTemplate" colspan="2"><div>template &lt;size_t T&gt;</div></td>
</tr>
<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemTypeTemplate" align="left" valign="top">static void</td>
<td class="doxyMemberIndexItemNameTemplate" align="left" valign="top"><a href="#a924259105b9cc65caf1525588ae6ca8c">signedDecoder</a> (MCInst &amp;MI, unsigned tmp, const MCDisassembler *Decoder)</td>
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

### disassembler() {#a286150b949c366f38d99bcf292053cf0}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">HexagonDisassembler const  &amp; anonymous{HexagonDisassembler.cpp}::disassembler (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/mcdisassembler">MCDisassembler</a> * Decoder)</td>
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



<p>Definition at line 80 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/hexagon/lib/target/hexagon/disassembler/hexagondisassembler-cpp">HexagonDisassembler.cpp</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/hexagon/lib/target/hexagon/disassembler/hexagondisassembler-cpp/#a20a8e4705041b6319c008c1e981eee45">brtargetDecoder</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/hexagon/lib/target/hexagon/disassembler/hexagondisassembler-cpp/#a2a753b4c73b07ef8f90dcada88f6ef4d">s32_0ImmDecoder</a>, <a href="#a924259105b9cc65caf1525588ae6ca8c">signedDecoder</a> and <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/hexagon/lib/target/hexagon/disassembler/hexagondisassembler-cpp/#a42a94b0bc3b45d5b82f8cf8d26dc8449">unsignedImmDecoder</a>.</p>

</div>
</div>

### fullValue() {#a2e0e4ab18e7fb56c7dbd46fe864243e6}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">uint64_t anonymous{HexagonDisassembler.cpp}::fullValue (<a href="/web-llvm/docs/api/classes/anonymous-hexagondisassembler-cpp-/hexagondisassembler">HexagonDisassembler</a> <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> &amp; Disassembler, <a href="/web-llvm/docs/api/classes/llvm/mcinst">MCInst</a> &amp; MI, int64_t Value)</td>
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



<p>Definition at line 62 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/hexagon/lib/target/hexagon/disassembler/hexagondisassembler-cpp">HexagonDisassembler.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/silowercontrolflow-cpp/#a4868c5d81c5ccc98c47aeab6244346a0">assert</a>, <a href="/web-llvm/docs/api/classes/anonymous-hexagondisassembler-cpp-/hexagondisassembler/#a34045a679c93f10aa18b84f8fc653a98">anonymous{HexagonDisassembler.cpp}::HexagonDisassembler::CurrentExtender</a>, <a href="/web-llvm/docs/api/classes/llvm/mcoperand/#ac9408fbc60922d24b01c1efcbd4ba52b">llvm::MCOperand::getExpr</a>, <a href="/web-llvm/docs/api/namespaces/llvm/hexagonmcinstrinfo/#a5115f4f0f0213e99431e82c167be0b98">llvm::HexagonMCInstrInfo::getExtendableOp</a>, <a href="/web-llvm/docs/api/namespaces/llvm/hexagonmcinstrinfo/#ac728d542c58e2a7c3a56cc67b0da9044">llvm::HexagonMCInstrInfo::getExtentAlignment</a>, <a href="/web-llvm/docs/api/classes/llvm/mcinst/#aef5de3ac30fe221c5b4e702574ab46a9">llvm::MCInst::getOperand</a>, <a href="/web-llvm/docs/api/classes/anonymous-hexagondisassembler-cpp-/hexagondisassembler/#ac29f61978d19ce197dc2ff89cf4b3750">anonymous{HexagonDisassembler.cpp}::HexagonDisassembler::MCII</a>, <a href="/web-llvm/docs/api/files/lib/lib/codegen/lib/codegen/globalisel/irtranslator-cpp/#abe44dfdea65b4f7e11e0a608ab708b76">MI</a> and <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/lib/target/aarch64/disassembler/aarch64disassembler-cpp/#abdb086b34295fb7aa09493c62d798465">Success</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/hexagon/lib/target/hexagon/disassembler/hexagondisassembler-cpp/#a20a8e4705041b6319c008c1e981eee45">brtargetDecoder</a>, <a href="#a924259105b9cc65caf1525588ae6ca8c">signedDecoder</a> and <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/hexagon/lib/target/hexagon/disassembler/hexagondisassembler-cpp/#a42a94b0bc3b45d5b82f8cf8d26dc8449">unsignedImmDecoder</a>.</p>

</div>
</div>

### signedDecoder() {#a924259105b9cc65caf1525588ae6ca8c}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<div class="doxyMemberTemplate">template &lt;size_t T&gt;</div>
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void anonymous{HexagonDisassembler.cpp}::signedDecoder (<a href="/web-llvm/docs/api/classes/llvm/mcinst">MCInst</a> &amp; MI, unsigned tmp, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/mcdisassembler">MCDisassembler</a> * Decoder)</td>
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



<p>Definition at line 84 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/hexagon/lib/target/hexagon/disassembler/hexagondisassembler-cpp">HexagonDisassembler.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/namespaces/llvm/hexagonmcinstrinfo/#a10e72ca32e8206bcc1a9ec642a797e44">llvm::HexagonMCInstrInfo::addConstant</a>, <a href="#a286150b949c366f38d99bcf292053cf0">disassembler</a>, <a href="#a2e0e4ab18e7fb56c7dbd46fe864243e6">fullValue</a>, <a href="/web-llvm/docs/api/classes/llvm/mcdisassembler/#a3faa10cafd0be721018fc1b9bc2c5488">llvm::MCDisassembler::getContext</a>, <a href="/web-llvm/docs/api/files/lib/lib/codegen/lib/codegen/globalisel/irtranslator-cpp/#abe44dfdea65b4f7e11e0a608ab708b76">MI</a> and <a href="/web-llvm/docs/api/namespaces/llvm/#ad12a58d7f81a304e0c568ad2210bc4fe">llvm::SignExtend64</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/hexagon/lib/target/hexagon/disassembler/hexagondisassembler-cpp/#a2a753b4c73b07ef8f90dcada88f6ef4d">s32_0ImmDecoder</a>.</p>

</div>
</div>

</div>

<hr/>

The documentation for this namespace was generated from the following file:

<ul>
<li><a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/hexagon/lib/target/hexagon/disassembler/hexagondisassembler-cpp">HexagonDisassembler.cpp</a></li>
</ul>

<hr/>

<p class="doxyGeneratedBy">Generated via <a href="https://github.com/xpack/doxygen2docusaurus">doxygen2docusaurus</a> by <a href="https://www.doxygen.nl">Doxygen</a> 1.15.0.</p>

</div>
