---

# DO NOT EDIT!
# Automatically generated via doxygen2docusaurus by Doxygen.

slug: /api/files/lib/lib/codegen/lib/codegen/selectiondag/legalizevectorops-cpp
custom_edit_url: null
toc_max_heading_level: 4
keywords:
  - doxygen
  - reference
  - file

---

<div class="doxyPage">

# The `LegalizeVectorOps.cpp` File Reference



## Included Headers

<div class="doxyIncludesList">#include "<a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/adt/densemap-h">llvm/ADT/DenseMap.h</a>"
#include "<a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/adt/smallvector-h">llvm/ADT/SmallVector.h</a>"
#include "<a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/analysis/targetlibraryinfo-h">llvm/Analysis/TargetLibraryInfo.h</a>"
#include "<a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/analysis/vectorutils-h">llvm/Analysis/VectorUtils.h</a>"
#include "<a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/codegen/isdopcodes-h">llvm/CodeGen/ISDOpcodes.h</a>"
#include "<a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/codegen/selectiondag-h">llvm/CodeGen/SelectionDAG.h</a>"
#include "<a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/codegen/selectiondagnodes-h">llvm/CodeGen/SelectionDAGNodes.h</a>"
#include "<a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/codegen/targetlowering-h">llvm/CodeGen/TargetLowering.h</a>"
#include "<a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/codegen/valuetypes-h">llvm/CodeGen/ValueTypes.h</a>"
#include "<a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/codegentypes/machinevaluetype-h">llvm/CodeGenTypes/MachineValueType.h</a>"
#include "<a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/ir/datalayout-h">llvm/IR/DataLayout.h</a>"
#include "<a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/support/casting-h">llvm/Support/Casting.h</a>"
#include "<a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/support/compiler-h">llvm/Support/Compiler.h</a>"
#include "<a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/support/debug-h">llvm/Support/Debug.h</a>"
#include "<a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/support/errorhandling-h">llvm/Support/ErrorHandling.h</a>"
#include &lt;cassert&gt;
#include &lt;cstdint&gt;
#include &lt;iterator&gt;
#include &lt;utility&gt;
#include "llvm/IR/ConstrainedOps.def"
#include "llvm/IR/VPIntrinsics.def"
</div>

## Namespaces Index

<table class="doxyMembersIndex">

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">namespace</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="/web-llvm/docs/api/namespaces/anonymous-legalizevectorops-cpp-">anonymous{LegalizeVectorOps.cpp}</a></td>
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

## Classes Index

<table class="doxyMembersIndex">

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">class</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="/web-llvm/docs/api/classes/anonymous-legalizevectorops-cpp-/vectorlegalizer">VectorLegalizer</a></td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">static void</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ad378536508f0c71b730daf4da2026076">createBSWAPShuffleMask</a> (EVT VT, SmallVectorImpl&lt; int &gt; &amp;ShuffleMask)</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ad78e062f62e0d6e453941fb4ca843e4d">DEBUG_TYPE</a>&nbsp;&nbsp;&nbsp;"legalizevectorops"</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">#define</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#abf72c4cc7b3c53cbf1f02dd1f6c3c46b">DAG_INSTRUCTION</a>(NAME, NARG, ROUND_MODE, INTRINSIC, DAGN)&nbsp;&nbsp;&nbsp;  case ISD::STRICT_##DAGN:</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">#define</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ab147009f90cee109f49012b2a721d00e">BEGIN_REGISTER_VP_SDNODE</a>(VPID, LEGALPOS, ...)&nbsp;&nbsp;&nbsp;...</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">#define</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#abf72c4cc7b3c53cbf1f02dd1f6c3c46b">DAG_INSTRUCTION</a>(NAME, NARG, ROUND_MODE, INTRINSIC, DAGN)&nbsp;&nbsp;&nbsp;  case ISD::STRICT_##DAGN:</td>
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

### createBSWAPShuffleMask() {#ad378536508f0c71b730daf4da2026076}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void createBSWAPShuffleMask (<a href="/web-llvm/docs/api/structs/llvm/evt">EVT</a> VT, <a href="/web-llvm/docs/api/classes/llvm/smallvectorimpl">SmallVectorImpl</a>&lt; int &gt; &amp; ShuffleMask)</td>
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



<p>Definition at line 1439 of file <a href="/web-llvm/docs/api/files/lib/lib/codegen/lib/codegen/selectiondag/legalizevectorops-cpp">LegalizeVectorOps.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/files/lib/lib/ir/builtingcs-cpp/#abb2b3a60ccc38a28239e19a1646e0c8a">E</a>, <a href="/web-llvm/docs/api/structs/llvm/evt/#a547a88964f1673c84410baa7a2a83f4d">llvm::EVT::getScalarSizeInBits</a>, <a href="/web-llvm/docs/api/structs/llvm/evt/#ae245d70802e4ebe1cae2b6122c62a22a">llvm::EVT::getVectorNumElements</a>, <a href="/web-llvm/docs/api/files/lib/lib/support/md5-cpp/#ac0eafdc9ee161b71e7af98af736952fd">I</a> and <a href="/web-llvm/docs/api/classes/llvm/smallvectortemplatebase/#af42bfbc067df27c19ee2fc859df58799">llvm::SmallVectorTemplateBase&lt; T, bool &gt;::push_back</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Macro Definitions

### BEGIN\_REGISTER\_VP\_SDNODE {#ab147009f90cee109f49012b2a721d00e}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">#define BEGIN_REGISTER_VP_SDNODE(VPID, LEGALPOS, ...)&nbsp;&nbsp;&nbsp;...</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<dl class="doxySectionUser">
<dt>Value</dt>
<dd>
<div class="doxyVerbatim">  case ISD::VPID: {                                                            \
    EVT LegalizeVT = LEGALPOS &lt; 0 ? <a href="/web-llvm/docs/api/classes/node">Node</a>-&gt;<a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/vectorize/slpvectorizer-cpp/#a9df55d50aee24118cfdc34ecb32db484">getValueType</a>(-(1 + LEGALPOS))        \
                                  : <a href="/web-llvm/docs/api/classes/node">Node</a>-&gt;getOperand(LEGALPOS).<a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/vectorize/slpvectorizer-cpp/#a9df55d50aee24118cfdc34ecb32db484">getValueType</a>(); \
    <a href="/web-llvm/docs/api/files/lib/lib/passes/passbuilderbindings-cpp/#acdfbcf188e2d4a80837e89de2ccdffab">if</a> (ISD::VPID == ISD::VP_SETCC) {                                          \
      ISD::CondCode CCCode = cast&lt;CondCodeSDNode&gt;(<a href="/web-llvm/docs/api/classes/node">Node</a>-&gt;getOperand(2))-&gt;get(); \
      Action = TLI.getCondCodeAction(CCCode, <a href="/web-llvm/docs/api/files/lib/lib/codegen/lib/codegen/selectiondag/selectiondagisel-cpp/#a4ee68bef4d94f4873f75267990914ac6">LegalizeVT.getSimpleVT</a>());        \
      <a href="/web-llvm/docs/api/files/lib/lib/passes/passbuilderbindings-cpp/#acdfbcf188e2d4a80837e89de2ccdffab">if</a> (Action != TargetLowering::Legal)                                     \
        <a href="/web-llvm/docs/api/files/lib/lib/codegen/lib/codegen/asmprinter/ehstreamer-cpp/#a91cf6fbebedd86150a36e5ac3d5d3bfc">break</a>;                                                                 \
    }                                                                          \
    /* Defer non-<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/amdgpupromotealloca-cpp/#ac760e37eba1d852d0a28011a1a0ce05f">vector</a> results to LegalizeDAG. */                             \
    <a href="/web-llvm/docs/api/files/lib/lib/passes/passbuilderbindings-cpp/#acdfbcf188e2d4a80837e89de2ccdffab">if</a> (!<a href="/web-llvm/docs/api/classes/node">Node</a>-&gt;<a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/vectorize/slpvectorizer-cpp/#a9df55d50aee24118cfdc34ecb32db484">getValueType</a>(0).isVector() &amp;&amp;                                   \
        <a href="/web-llvm/docs/api/classes/node">Node</a>-&gt;<a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/vectorize/slpvectorizer-cpp/#a9df55d50aee24118cfdc34ecb32db484">getValueType</a>(0) != MVT::Other) {                                 \
      Action = TargetLowering::Legal;                                          \
      <a href="/web-llvm/docs/api/files/lib/lib/codegen/lib/codegen/asmprinter/ehstreamer-cpp/#a91cf6fbebedd86150a36e5ac3d5d3bfc">break</a>;                                                                   \
    }                                                                          \
    Action = TLI.getOperationAction(<a href="/web-llvm/docs/api/classes/node">Node</a>-&gt;<a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/vectorize/vplanslp-cpp/#a06b4f19004df11b338ccc7e73bf47ab4">getOpcode</a>(), LegalizeVT);            \
  } <a href="/web-llvm/docs/api/files/lib/lib/codegen/lib/codegen/asmprinter/ehstreamer-cpp/#a91cf6fbebedd86150a36e5ac3d5d3bfc">break</a>;
</div>
</dd>
</dl>

<p>Definition at line 524 of file <a href="/web-llvm/docs/api/files/lib/lib/codegen/lib/codegen/selectiondag/legalizevectorops-cpp">LegalizeVectorOps.cpp</a>.</p>

</div>
</div>

### DAG\_INSTRUCTION {#abf72c4cc7b3c53cbf1f02dd1f6c3c46b}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">#define DAG_INSTRUCTION(NAME, NARG, ROUND_MODE, INTRINSIC, DAGN)&nbsp;&nbsp;&nbsp;  case ISD::STRICT_##DAGN:</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 315 of file <a href="/web-llvm/docs/api/files/lib/lib/codegen/lib/codegen/selectiondag/legalizevectorops-cpp">LegalizeVectorOps.cpp</a>.</p>

</div>
</div>

### DAG\_INSTRUCTION {#abf72c4cc7b3c53cbf1f02dd1f6c3c46b}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">#define DAG_INSTRUCTION(NAME, NARG, ROUND_MODE, INTRINSIC, DAGN)&nbsp;&nbsp;&nbsp;  case ISD::STRICT_##DAGN:</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 1176 of file <a href="/web-llvm/docs/api/files/lib/lib/codegen/lib/codegen/selectiondag/legalizevectorops-cpp">LegalizeVectorOps.cpp</a>.</p>

</div>
</div>

### DEBUG\_TYPE {#ad78e062f62e0d6e453941fb4ca843e4d}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">#define DEBUG_TYPE&nbsp;&nbsp;&nbsp;"legalizevectorops"</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 51 of file <a href="/web-llvm/docs/api/files/lib/lib/codegen/lib/codegen/selectiondag/legalizevectorops-cpp">LegalizeVectorOps.cpp</a>.</p>

</div>
</div>

</div>

<hr/>

<p class="doxyGeneratedBy">Generated via <a href="https://github.com/xpack/doxygen2docusaurus">doxygen2docusaurus</a> by <a href="https://www.doxygen.nl">Doxygen</a> 1.14.0.</p>

</div>
