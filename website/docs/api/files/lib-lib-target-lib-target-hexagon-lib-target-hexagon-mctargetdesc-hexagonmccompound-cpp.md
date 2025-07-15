---

# DO NOT EDIT!
# Automatically generated via doxygen2docusaurus by Doxygen.

slug: /api/files/lib/lib/target/lib/target/hexagon/lib/target/hexagon/mctargetdesc/hexagonmccompound-cpp
custom_edit_url: null
toc_max_heading_level: 4
keywords:
  - doxygen
  - reference
  - file

---

<div class="doxyPage">

# The `HexagonMCCompound.cpp` File Reference



## Included Headers

<div class="doxyIncludesList">#include "<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/hexagon/lib/target/hexagon/mctargetdesc/hexagonbaseinfo-h">MCTargetDesc/HexagonBaseInfo.h</a>"
#include "<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/hexagon/lib/target/hexagon/mctargetdesc/hexagonmcinstrinfo-h">MCTargetDesc/HexagonMCInstrInfo.h</a>"
#include "<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/hexagon/lib/target/hexagon/mctargetdesc/hexagonmcshuffler-h">MCTargetDesc/HexagonMCShuffler.h</a>"
#include "<a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/mc/mccontext-h">llvm/MC/MCContext.h</a>"
#include "<a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/mc/mcexpr-h">llvm/MC/MCExpr.h</a>"
#include "<a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/mc/mcinst-h">llvm/MC/MCInst.h</a>"
#include "<a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/support/debug-h">llvm/Support/Debug.h</a>"
#include "<a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/support/errorhandling-h">llvm/Support/ErrorHandling.h</a>"
#include "<a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/support/raw-ostream-h">llvm/Support/raw_ostream.h</a>"
#include &lt;cassert&gt;
#include &lt;cstdint&gt;
</div>

## Enumerations Index

<table class="doxyMembersIndex">

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">enum</td>
<td class="doxyMemberIndexItemName" align="left" valign="top">OpcodeIndex { <a href="#aac4e485cee645621dcac1e8a6e56fc9e">...</a> }</td>
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

## Functions Index

<table class="doxyMembersIndex">

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">static unsigned</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a1c0379352edde54a80bacc7540aee0c7">getCompoundCandidateGroup</a> (MCInst const &amp;MI, bool IsExtended)</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">static unsigned</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a81470ca50ca4d5d5888f72c1dc2c9993">getCompoundOp</a> (MCInst const &amp;HMCI)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>getCompoundOp - Return the index from 0-7 into the above opcode lists. <a href="#a81470ca50ca4d5d5888f72c1dc2c9993">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">static <a href="/web-llvm/docs/api/classes/llvm/mcinst">MCInst</a> *</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ad635fb338c113f5de9924ceeeb507dca">getCompoundInsn</a> (MCContext &amp;Context, MCInst const &amp;L, MCInst const &amp;R)</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#aaaf1263d3963abf3556875a37c3df8f8">isOrderedCompoundPair</a> (MCInst const &amp;MIa, bool IsExtendedA, MCInst const &amp;MIb, bool IsExtendedB)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Non-Symmetrical. See if these two instructions are fit for compound pair. <a href="#aaaf1263d3963abf3556875a37c3df8f8">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">static bool</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a060f0d1989564164d0cf3fad101666f4">lookForCompound</a> (MCInstrInfo const &amp;MCII, MCContext &amp;Context, MCInst &amp;MCI)</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">static <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> unsigned</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#af18b782a7e06d4575e08be82466b0124">tstBitOpcode</a>[8] = ...</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">static <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> unsigned</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ab157172bce0b50fc2d71ed39cfe10489">cmpeqBitOpcode</a>[8] = ...</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">static <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> unsigned</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a0e9614dcf3ff3e956c283df0238ed91a">cmpgtBitOpcode</a>[8] = ...</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">static <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> unsigned</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a33a80bda89258df41b27225ae290ea12">cmpgtuBitOpcode</a>[8] = ...</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">static <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> unsigned</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a1dea8b980ed8ceba5968e04e01df38fd">cmpeqiBitOpcode</a>[8] = ...</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">static <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> unsigned</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#acfbadb3bb028c41c79e53f726f26e293">cmpgtiBitOpcode</a>[8] = ...</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">static <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> unsigned</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a8bc14009b0e273b596d5ce21f7b59b6c">cmpgtuiBitOpcode</a>[8] = ...</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">static <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> unsigned</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a4b9dc2f1efcfbacbff48c2b08dfb31c9">cmpeqn1BitOpcode</a>[8] = ...</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">static <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> unsigned</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a55b9c4b330d4f4e5f747a81cc9ea33ce">cmpgtn1BitOpcode</a>[8] = ...</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ad78e062f62e0d6e453941fb4ca843e4d">DEBUG_TYPE</a>&nbsp;&nbsp;&nbsp;"hexagon-mccompound"</td>
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

## Enumerations

### OpcodeIndex {#aac4e485cee645621dcac1e8a6e56fc9e}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">enum OpcodeIndex </td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">


<dl class="doxyEnumList">
<dt class="doxyEnumTableTitle">Enumeration values</dt>
<dd>
<table class="doxyEnumTable">

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">fp0_jump_nt<a id="aac4e485cee645621dcac1e8a6e56fc9ea1f123e1bdd63de7c18889234a8fe2130"></a></td>
<td class="doxyEnumItemDescription"> (= 0)</td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">fp0_jump_t<a id="aac4e485cee645621dcac1e8a6e56fc9ea5de1207537d013d71aef408a3e819ae2"></a></td>
<td class="doxyEnumItemDescription"></td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">fp1_jump_nt<a id="aac4e485cee645621dcac1e8a6e56fc9ea75ae5ee8a1df0fc02316f18608dcf0ed"></a></td>
<td class="doxyEnumItemDescription"></td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">fp1_jump_t<a id="aac4e485cee645621dcac1e8a6e56fc9ea6003c65836cbe108b5cb7ba3699fcc04"></a></td>
<td class="doxyEnumItemDescription"></td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">tp0_jump_nt<a id="aac4e485cee645621dcac1e8a6e56fc9eaba11a8a75f5cf98fa0b84a340e221b66"></a></td>
<td class="doxyEnumItemDescription"></td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">tp0_jump_t<a id="aac4e485cee645621dcac1e8a6e56fc9eae44321a0fc3b030edb2176b8ec822400"></a></td>
<td class="doxyEnumItemDescription"></td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">tp1_jump_nt<a id="aac4e485cee645621dcac1e8a6e56fc9ea02b0bc723911c4a90aba13b8485c49d2"></a></td>
<td class="doxyEnumItemDescription"></td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">tp1_jump_t<a id="aac4e485cee645621dcac1e8a6e56fc9ea5f9fb5b0565b9af6fc76ec74842c04f6"></a></td>
<td class="doxyEnumItemDescription"></td>
</tr>

</table>
</dd>
</dl>

<p>Definition at line 30 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/hexagon/lib/target/hexagon/mctargetdesc/hexagonmccompound-cpp">HexagonMCCompound.cpp</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Functions

### getCompoundCandidateGroup() {#a1c0379352edde54a80bacc7540aee0c7}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">unsigned getCompoundCandidateGroup (<a href="/web-llvm/docs/api/classes/llvm/mcinst">MCInst</a> <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> &amp; MI, bool IsExtended)</td>
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



<p>Definition at line 80 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/hexagon/lib/target/hexagon/mctargetdesc/hexagonmccompound-cpp">HexagonMCCompound.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/namespaces/llvm/hexagonii/#a8c5fc47618410395f043e1a8510c8d4aab944953b48ea80dee9c9c1b8386474fc">llvm::HexagonII::HCG_A</a>, <a href="/web-llvm/docs/api/namespaces/llvm/hexagonii/#a8c5fc47618410395f043e1a8510c8d4aa1181d3826dc35a48b242827157300b9c">llvm::HexagonII::HCG_B</a>, <a href="/web-llvm/docs/api/namespaces/llvm/hexagonii/#a8c5fc47618410395f043e1a8510c8d4aa0dc0bcc38a2d0221ce1f7f79838e7ae5">llvm::HexagonII::HCG_C</a>, <a href="/web-llvm/docs/api/namespaces/llvm/hexagonii/#a8c5fc47618410395f043e1a8510c8d4aaffbac8b5898a3bd64b0f283e4f3ee93c">llvm::HexagonII::HCG_None</a>, <a href="/web-llvm/docs/api/namespaces/llvm/hexagonmcinstrinfo/#a174e266390355aa15c8ab81345640235">llvm::HexagonMCInstrInfo::inRange</a>, <a href="/web-llvm/docs/api/namespaces/llvm/hexagonmcinstrinfo/#a90252d582ff57d9749eb7dc3aac57816">llvm::HexagonMCInstrInfo::isIntRegForSubInst</a>, <a href="/web-llvm/docs/api/files/lib/lib/codegen/lib/codegen/globalisel/irtranslator-cpp/#abe44dfdea65b4f7e11e0a608ab708b76">MI</a> and <a href="/web-llvm/docs/api/namespaces/llvm/hexagonmcinstrinfo/#a6ca1ea5b42b7c51b90376ec8262db074">llvm::HexagonMCInstrInfo::minConstant</a>.</p>


<p>Referenced by <a href="#aaaf1263d3963abf3556875a37c3df8f8">isOrderedCompoundPair</a>.</p>

</div>
</div>

### getCompoundInsn() {#ad635fb338c113f5de9924ceeeb507dca}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">MCInst * getCompoundInsn (<a href="/web-llvm/docs/api/classes/llvm/mccontext">MCContext</a> &amp; Context, <a href="/web-llvm/docs/api/classes/llvm/mcinst">MCInst</a> <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> &amp; L, <a href="/web-llvm/docs/api/classes/llvm/mcinst">MCInst</a> <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> &amp; R)</td>
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



<p>Definition at line 197 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/hexagon/lib/target/hexagon/mctargetdesc/hexagonmccompound-cpp">HexagonMCCompound.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/classes/llvm/mcinst/#ad5a79c04398dc86a3acfe7f8713216eb">llvm::MCInst::addOperand</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/silowercontrolflow-cpp/#a4868c5d81c5ccc98c47aeab6244346a0">assert</a>, <a href="#ab157172bce0b50fc2d71ed39cfe10489">cmpeqBitOpcode</a>, <a href="#a1dea8b980ed8ceba5968e04e01df38fd">cmpeqiBitOpcode</a>, <a href="#a4b9dc2f1efcfbacbff48c2b08dfb31c9">cmpeqn1BitOpcode</a>, <a href="#a0e9614dcf3ff3e956c283df0238ed91a">cmpgtBitOpcode</a>, <a href="#acfbadb3bb028c41c79e53f726f26e293">cmpgtiBitOpcode</a>, <a href="#a55b9c4b330d4f4e5f747a81cc9ea33ce">cmpgtn1BitOpcode</a>, <a href="#a33a80bda89258df41b27225ae290ea12">cmpgtuBitOpcode</a>, <a href="#a8bc14009b0e273b596d5ce21f7b59b6c">cmpgtuiBitOpcode</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a7c46c742c31be54870e2038048e6b391">llvm::dbgs</a>, <a href="#a81470ca50ca4d5d5888f72c1dc2c9993">getCompoundOp</a>, <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/support/debug-h/#a196897517069dda1bdb549e24468f7d7">LLVM_DEBUG</a>, <a href="/web-llvm/docs/api/classes/llvm/mcinst/#ae844d6ff99f067e6672e004ed7613c24">llvm::MCInst::setOpcode</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/lib/target/aarch64/disassembler/aarch64disassembler-cpp/#abdb086b34295fb7aa09493c62d798465">Success</a> and <a href="#af18b782a7e06d4575e08be82466b0124">tstBitOpcode</a>.</p>


<p>Referenced by <a href="#a060f0d1989564164d0cf3fad101666f4">lookForCompound</a>.</p>

</div>
</div>

### getCompoundOp() {#a81470ca50ca4d5d5888f72c1dc2c9993}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">unsigned getCompoundOp (<a href="/web-llvm/docs/api/classes/llvm/mcinst">MCInst</a> <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> &amp; HMCI)</td>
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

<p>getCompoundOp - Return the index from 0-7 into the above opcode lists.</p>

<p>Definition at line 175 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/hexagon/lib/target/hexagon/mctargetdesc/hexagonmccompound-cpp">HexagonMCCompound.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/silowercontrolflow-cpp/#a4868c5d81c5ccc98c47aeab6244346a0">assert</a>, <a href="#aac4e485cee645621dcac1e8a6e56fc9ea1f123e1bdd63de7c18889234a8fe2130">fp0_jump_nt</a>, <a href="#aac4e485cee645621dcac1e8a6e56fc9ea5de1207537d013d71aef408a3e819ae2">fp0_jump_t</a>, <a href="#aac4e485cee645621dcac1e8a6e56fc9ea75ae5ee8a1df0fc02316f18608dcf0ed">fp1_jump_nt</a>, <a href="#aac4e485cee645621dcac1e8a6e56fc9ea6003c65836cbe108b5cb7ba3699fcc04">fp1_jump_t</a>, <a href="/web-llvm/docs/api/classes/llvm/mcinst/#a5c26b1db954c27889986dba3b310a8e4">llvm::MCInst::getOpcode</a>, <a href="/web-llvm/docs/api/classes/llvm/mcinst/#aef5de3ac30fe221c5b4e702574ab46a9">llvm::MCInst::getOperand</a>, <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/support/errorhandling-h/#ace243f5c25697a1107cce46626b3dc94">llvm_unreachable</a>, <a href="#aac4e485cee645621dcac1e8a6e56fc9eaba11a8a75f5cf98fa0b84a340e221b66">tp0_jump_nt</a>, <a href="#aac4e485cee645621dcac1e8a6e56fc9eae44321a0fc3b030edb2176b8ec822400">tp0_jump_t</a>, <a href="#aac4e485cee645621dcac1e8a6e56fc9ea02b0bc723911c4a90aba13b8485c49d2">tp1_jump_nt</a> and <a href="#aac4e485cee645621dcac1e8a6e56fc9ea5f9fb5b0565b9af6fc76ec74842c04f6">tp1_jump_t</a>.</p>


<p>Referenced by <a href="#ad635fb338c113f5de9924ceeeb507dca">getCompoundInsn</a>.</p>

</div>
</div>

### isOrderedCompoundPair() {#aaaf1263d3963abf3556875a37c3df8f8}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool isOrderedCompoundPair (<a href="/web-llvm/docs/api/classes/llvm/mcinst">MCInst</a> <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> &amp; MIa, bool IsExtendedA, <a href="/web-llvm/docs/api/classes/llvm/mcinst">MCInst</a> <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> &amp; MIb, bool IsExtendedB)</td>
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

<p>Non-Symmetrical. See if these two instructions are fit for compound pair.</p>

<p>Definition at line 335 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/hexagon/lib/target/hexagon/mctargetdesc/hexagonmccompound-cpp">HexagonMCCompound.cpp</a>.</p>


<p>References <a href="#a1c0379352edde54a80bacc7540aee0c7">getCompoundCandidateGroup</a>, <a href="/web-llvm/docs/api/classes/llvm/mcinst/#a5c26b1db954c27889986dba3b310a8e4">llvm::MCInst::getOpcode</a>, <a href="/web-llvm/docs/api/classes/llvm/mcinst/#aef5de3ac30fe221c5b4e702574ab46a9">llvm::MCInst::getOperand</a>, <a href="/web-llvm/docs/api/classes/llvm/mcoperand/#a94abf618eb8001b802910ab872a7d1d9">llvm::MCOperand::getReg</a>, <a href="/web-llvm/docs/api/namespaces/llvm/hexagonii/#a8c5fc47618410395f043e1a8510c8d4aab944953b48ea80dee9c9c1b8386474fc">llvm::HexagonII::HCG_A</a>, <a href="/web-llvm/docs/api/namespaces/llvm/hexagonii/#a8c5fc47618410395f043e1a8510c8d4aa1181d3826dc35a48b242827157300b9c">llvm::HexagonII::HCG_B</a> and <a href="/web-llvm/docs/api/namespaces/llvm/hexagonii/#a8c5fc47618410395f043e1a8510c8d4aa0dc0bcc38a2d0221ce1f7f79838e7ae5">llvm::HexagonII::HCG_C</a>.</p>


<p>Referenced by <a href="#a060f0d1989564164d0cf3fad101666f4">lookForCompound</a>.</p>

</div>
</div>

### lookForCompound() {#a060f0d1989564164d0cf3fad101666f4}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool lookForCompound (<a href="/web-llvm/docs/api/classes/llvm/mcinstrinfo">MCInstrInfo</a> <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> &amp; MCII, <a href="/web-llvm/docs/api/classes/llvm/mccontext">MCContext</a> &amp; Context, <a href="/web-llvm/docs/api/classes/llvm/mcinst">MCInst</a> &amp; MCI)</td>
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



<p>Definition at line 349 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/hexagon/lib/target/hexagon/mctargetdesc/hexagonmccompound-cpp">HexagonMCCompound.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/silowercontrolflow-cpp/#a4868c5d81c5ccc98c47aeab6244346a0">assert</a>, <a href="/web-llvm/docs/api/files/lib/lib/ir/builtingcs-cpp/#ae76959fe811ba090de4cba69ac00f1da">B</a>, <a href="/web-llvm/docs/api/classes/llvm/mcinst/#ad7df02a018c3a01d74738d5ba3a09e93">llvm::MCInst::begin</a>, <a href="/web-llvm/docs/api/namespaces/llvm/hexagonmcinstrinfo/#aa004a7b4f04de8ed59326f54873f7422">llvm::HexagonMCInstrInfo::bundleInstructionsOffset</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a7c46c742c31be54870e2038048e6b391">llvm::dbgs</a>, <a href="/web-llvm/docs/api/classes/llvm/mcinst/#ad815f3f5c7e6106ca7ba4926d143c2cf">llvm::MCInst::end</a>, <a href="/web-llvm/docs/api/classes/llvm/mcinst/#a392c263d0b0a47be4702000f9bca7f16">llvm::MCInst::erase</a>, <a href="#ad635fb338c113f5de9924ceeeb507dca">getCompoundInsn</a>, <a href="/web-llvm/docs/api/classes/llvm/mcinst/#a5c26b1db954c27889986dba3b310a8e4">llvm::MCInst::getOpcode</a>, <a href="/web-llvm/docs/api/namespaces/llvm/hexagonmcinstrinfo/#a94f0ca29631596dfaa69418dd1dd6cbd">llvm::HexagonMCInstrInfo::getType</a>, <a href="/web-llvm/docs/api/namespaces/llvm/hexagonmcinstrinfo/#a69d33e060c5b0bbfe0f8a2cbeb71f598">llvm::HexagonMCInstrInfo::isBundle</a>, <a href="/web-llvm/docs/api/namespaces/llvm/hexagonmcinstrinfo/#a95c527167756007a3fb2ab49ec4b2c6d">llvm::HexagonMCInstrInfo::isImmext</a>, <a href="#aaaf1263d3963abf3556875a37c3df8f8">isOrderedCompoundPair</a>, <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/support/debug-h/#a196897517069dda1bdb549e24468f7d7">LLVM_DEBUG</a> and <a href="/web-llvm/docs/api/namespaces/llvm/hexagonii/#a9bebdf970b4f51041ed3dee5d558a807a9ef44633e8b88d5296c9251b1c9dcb88">llvm::HexagonII::TypeJ</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/namespaces/llvm/hexagonmcinstrinfo/#a65fdd614c206400e24b2676a71daac1c">llvm::HexagonMCInstrInfo::tryCompound</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Variables

### cmpeqBitOpcode {#ab157172bce0b50fc2d71ed39cfe10489}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">const unsigned cmpeqBitOpcode[8]</td>
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



<dl class="doxySectionUser">
<dt>Initialiser</dt>
<dd>
<div class="doxyVerbatim">= {
    J4_cmpeq_fp0_jump_nt, J4_cmpeq_fp0_jump_t,  J4_cmpeq_fp1_jump_nt,
    J4_cmpeq_fp1_jump_t,  J4_cmpeq_tp0_jump_nt, J4_cmpeq_tp0_jump_t,
    J4_cmpeq_tp1_jump_nt, J4_cmpeq_tp1_jump_t}
</div>
</dd>
</dl>

<p>Definition at line 45 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/hexagon/lib/target/hexagon/mctargetdesc/hexagonmccompound-cpp">HexagonMCCompound.cpp</a>.</p>


<p>Referenced by <a href="#ad635fb338c113f5de9924ceeeb507dca">getCompoundInsn</a>.</p>

</div>
</div>

### cmpeqiBitOpcode {#a1dea8b980ed8ceba5968e04e01df38fd}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">const unsigned cmpeqiBitOpcode[8]</td>
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



<dl class="doxySectionUser">
<dt>Initialiser</dt>
<dd>
<div class="doxyVerbatim">= {
    J4_cmpeqi_fp0_jump_nt, J4_cmpeqi_fp0_jump_t,  J4_cmpeqi_fp1_jump_nt,
    J4_cmpeqi_fp1_jump_t,  J4_cmpeqi_tp0_jump_nt, J4_cmpeqi_tp0_jump_t,
    J4_cmpeqi_tp1_jump_nt, J4_cmpeqi_tp1_jump_t}
</div>
</dd>
</dl>

<p>Definition at line 57 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/hexagon/lib/target/hexagon/mctargetdesc/hexagonmccompound-cpp">HexagonMCCompound.cpp</a>.</p>


<p>Referenced by <a href="#ad635fb338c113f5de9924ceeeb507dca">getCompoundInsn</a>.</p>

</div>
</div>

### cmpeqn1BitOpcode {#a4b9dc2f1efcfbacbff48c2b08dfb31c9}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">const unsigned cmpeqn1BitOpcode[8]</td>
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



<dl class="doxySectionUser">
<dt>Initialiser</dt>
<dd>
<div class="doxyVerbatim">= {
    J4_cmpeqn1_fp0_jump_nt, J4_cmpeqn1_fp0_jump_t,  J4_cmpeqn1_fp1_jump_nt,
    J4_cmpeqn1_fp1_jump_t,  J4_cmpeqn1_tp0_jump_nt, J4_cmpeqn1_tp0_jump_t,
    J4_cmpeqn1_tp1_jump_nt, J4_cmpeqn1_tp1_jump_t}
</div>
</dd>
</dl>

<p>Definition at line 69 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/hexagon/lib/target/hexagon/mctargetdesc/hexagonmccompound-cpp">HexagonMCCompound.cpp</a>.</p>


<p>Referenced by <a href="#ad635fb338c113f5de9924ceeeb507dca">getCompoundInsn</a>.</p>

</div>
</div>

### cmpgtBitOpcode {#a0e9614dcf3ff3e956c283df0238ed91a}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">const unsigned cmpgtBitOpcode[8]</td>
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



<dl class="doxySectionUser">
<dt>Initialiser</dt>
<dd>
<div class="doxyVerbatim">= {
    J4_cmpgt_fp0_jump_nt, J4_cmpgt_fp0_jump_t,  J4_cmpgt_fp1_jump_nt,
    J4_cmpgt_fp1_jump_t,  J4_cmpgt_tp0_jump_nt, J4_cmpgt_tp0_jump_t,
    J4_cmpgt_tp1_jump_nt, J4_cmpgt_tp1_jump_t}
</div>
</dd>
</dl>

<p>Definition at line 49 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/hexagon/lib/target/hexagon/mctargetdesc/hexagonmccompound-cpp">HexagonMCCompound.cpp</a>.</p>


<p>Referenced by <a href="#ad635fb338c113f5de9924ceeeb507dca">getCompoundInsn</a>.</p>

</div>
</div>

### cmpgtiBitOpcode {#acfbadb3bb028c41c79e53f726f26e293}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">const unsigned cmpgtiBitOpcode[8]</td>
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



<dl class="doxySectionUser">
<dt>Initialiser</dt>
<dd>
<div class="doxyVerbatim">= {
    J4_cmpgti_fp0_jump_nt, J4_cmpgti_fp0_jump_t,  J4_cmpgti_fp1_jump_nt,
    J4_cmpgti_fp1_jump_t,  J4_cmpgti_tp0_jump_nt, J4_cmpgti_tp0_jump_t,
    J4_cmpgti_tp1_jump_nt, J4_cmpgti_tp1_jump_t}
</div>
</dd>
</dl>

<p>Definition at line 61 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/hexagon/lib/target/hexagon/mctargetdesc/hexagonmccompound-cpp">HexagonMCCompound.cpp</a>.</p>


<p>Referenced by <a href="#ad635fb338c113f5de9924ceeeb507dca">getCompoundInsn</a>.</p>

</div>
</div>

### cmpgtn1BitOpcode {#a55b9c4b330d4f4e5f747a81cc9ea33ce}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">const unsigned cmpgtn1BitOpcode[8]</td>
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



<dl class="doxySectionUser">
<dt>Initialiser</dt>
<dd>
<div class="doxyVerbatim">= {
    J4_cmpgtn1_fp0_jump_nt, J4_cmpgtn1_fp0_jump_t,  J4_cmpgtn1_fp1_jump_nt,
    J4_cmpgtn1_fp1_jump_t,  J4_cmpgtn1_tp0_jump_nt, J4_cmpgtn1_tp0_jump_t,
    J4_cmpgtn1_tp1_jump_nt, J4_cmpgtn1_tp1_jump_t,
}
</div>
</dd>
</dl>

<p>Definition at line 73 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/hexagon/lib/target/hexagon/mctargetdesc/hexagonmccompound-cpp">HexagonMCCompound.cpp</a>.</p>


<p>Referenced by <a href="#ad635fb338c113f5de9924ceeeb507dca">getCompoundInsn</a>.</p>

</div>
</div>

### cmpgtuBitOpcode {#a33a80bda89258df41b27225ae290ea12}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">const unsigned cmpgtuBitOpcode[8]</td>
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



<dl class="doxySectionUser">
<dt>Initialiser</dt>
<dd>
<div class="doxyVerbatim">= {
    J4_cmpgtu_fp0_jump_nt, J4_cmpgtu_fp0_jump_t,  J4_cmpgtu_fp1_jump_nt,
    J4_cmpgtu_fp1_jump_t,  J4_cmpgtu_tp0_jump_nt, J4_cmpgtu_tp0_jump_t,
    J4_cmpgtu_tp1_jump_nt, J4_cmpgtu_tp1_jump_t}
</div>
</dd>
</dl>

<p>Definition at line 53 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/hexagon/lib/target/hexagon/mctargetdesc/hexagonmccompound-cpp">HexagonMCCompound.cpp</a>.</p>


<p>Referenced by <a href="#ad635fb338c113f5de9924ceeeb507dca">getCompoundInsn</a>.</p>

</div>
</div>

### cmpgtuiBitOpcode {#a8bc14009b0e273b596d5ce21f7b59b6c}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">const unsigned cmpgtuiBitOpcode[8]</td>
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



<dl class="doxySectionUser">
<dt>Initialiser</dt>
<dd>
<div class="doxyVerbatim">= {
    J4_cmpgtui_fp0_jump_nt, J4_cmpgtui_fp0_jump_t,  J4_cmpgtui_fp1_jump_nt,
    J4_cmpgtui_fp1_jump_t,  J4_cmpgtui_tp0_jump_nt, J4_cmpgtui_tp0_jump_t,
    J4_cmpgtui_tp1_jump_nt, J4_cmpgtui_tp1_jump_t}
</div>
</dd>
</dl>

<p>Definition at line 65 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/hexagon/lib/target/hexagon/mctargetdesc/hexagonmccompound-cpp">HexagonMCCompound.cpp</a>.</p>


<p>Referenced by <a href="#ad635fb338c113f5de9924ceeeb507dca">getCompoundInsn</a>.</p>

</div>
</div>

### tstBitOpcode {#af18b782a7e06d4575e08be82466b0124}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">const unsigned tstBitOpcode[8]</td>
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



<dl class="doxySectionUser">
<dt>Initialiser</dt>
<dd>
<div class="doxyVerbatim">= {
    J4_tstbit0_fp0_jump_nt, J4_tstbit0_fp0_jump_t,  J4_tstbit0_fp1_jump_nt,
    J4_tstbit0_fp1_jump_t,  J4_tstbit0_tp0_jump_nt, J4_tstbit0_tp0_jump_t,
    J4_tstbit0_tp1_jump_nt, J4_tstbit0_tp1_jump_t}
</div>
</dd>
</dl>

<p>Definition at line 41 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/hexagon/lib/target/hexagon/mctargetdesc/hexagonmccompound-cpp">HexagonMCCompound.cpp</a>.</p>


<p>Referenced by <a href="#ad635fb338c113f5de9924ceeeb507dca">getCompoundInsn</a>.</p>

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
<td class="doxyMemberName">#define DEBUG_TYPE&nbsp;&nbsp;&nbsp;"hexagon-mccompound"</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 28 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/hexagon/lib/target/hexagon/mctargetdesc/hexagonmccompound-cpp">HexagonMCCompound.cpp</a>.</p>

</div>
</div>

</div>

<hr/>

<p class="doxyGeneratedBy">Generated via <a href="https://github.com/xpack/doxygen2docusaurus">doxygen2docusaurus</a> by <a href="https://www.doxygen.nl">Doxygen</a> 1.14.0.</p>

</div>
