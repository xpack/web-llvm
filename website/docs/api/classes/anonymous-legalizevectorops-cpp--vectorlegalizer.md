---

# DO NOT EDIT!
# Automatically generated via doxygen2docusaurus by Doxygen.

slug: /api/classes/anonymous-legalizevectorops-cpp-/vectorlegalizer
custom_edit_url: null
toc_max_heading_level: 4
keywords:
  - doxygen
  - reference
  - class

---

<div class="doxyPage">

# `VectorLegalizer` Class



## Declaration

<div class="doxyDeclaration">
class anonymous{LegalizeVectorOps.cpp}::VectorLegalizer { ... }
</div>

## Public Constructors Index

<table class="doxyMembersIndex">

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ab3ce50c3e069741fd2cdb0216f66069b">VectorLegalizer</a> (SelectionDAG &amp;dag)</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">bool</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a45819d3524983de52fd325c7ebf6b801">Run</a> ()</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Begin legalizer the vector operations in the DAG. <a href="#a45819d3524983de52fd325c7ebf6b801">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

</table>

## Private Member Functions Index

<table class="doxyMembersIndex">

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">void</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ab3bd711fb198612b3f217a854c6987c9">AddLegalizedOperand</a> (SDValue From, SDValue To)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Adds a node to the translation cache. <a href="#ab3bd711fb198612b3f217a854c6987c9">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/sdvalue">SDValue</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a75ee7b55ead91f4b061d055b61a133a7">LegalizeOp</a> (SDValue Op)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Legalizes the given node. <a href="#a75ee7b55ead91f4b061d055b61a133a7">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/sdvalue">SDValue</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ad9f7ba7bd51759afc9616783918a4774">TranslateLegalizeResults</a> (SDValue Op, SDNode *Result)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Assuming the node is legal, "legalize" the results. <a href="#ad9f7ba7bd51759afc9616783918a4774">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/sdvalue">SDValue</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a0aa964dbf1d8e1f545d8abbf957f4890">RecursivelyLegalizeResults</a> (SDValue Op, MutableArrayRef&lt; SDValue &gt; Results)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Make sure Results are legal and update the translation cache. <a href="#a0aa964dbf1d8e1f545d8abbf957f4890">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">bool</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ab0bfaa11692f703bbe7db577d57c0c86">LowerOperationWrapper</a> (SDNode *N, SmallVectorImpl&lt; SDValue &gt; &amp;Results)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Wrapper to interface LowerOperation with a vector of Results. <a href="#ab0bfaa11692f703bbe7db577d57c0c86">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/sdvalue">SDValue</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ae7e249d47be4ecc4b6d7b903c2253122">UnrollVSETCC</a> (SDNode *Node)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Implements unrolling a VSETCC. <a href="#ae7e249d47be4ecc4b6d7b903c2253122">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">void</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ab68ff3284bb0cb541c0a5a50c7c88cac">Expand</a> (SDNode *Node, SmallVectorImpl&lt; SDValue &gt; &amp;Results)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Implement expand-based legalization of vector operations. <a href="#ab68ff3284bb0cb541c0a5a50c7c88cac">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">void</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#aa16dbedad3f5c864ac633aebef24d38d">ExpandFP_TO_UINT</a> (SDNode *Node, SmallVectorImpl&lt; SDValue &gt; &amp;Results)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Implements expansion for FP_TO_UINT; falls back to UnrollVectorOp if FP_TO_SINT isn't legal. <a href="#aa16dbedad3f5c864ac633aebef24d38d">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">void</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#aae7c2c883dfa2673e8bd68e3169cd8f2">ExpandUINT_TO_FLOAT</a> (SDNode *Node, SmallVectorImpl&lt; SDValue &gt; &amp;Results)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Implements expansion for UINT_TO_FLOAT; falls back to UnrollVectorOp if SINT_TO_FLOAT and SHR on vectors isn't legal. <a href="#aae7c2c883dfa2673e8bd68e3169cd8f2">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/sdvalue">SDValue</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a1e87b1a7e949a39e858471d18f0fbd57">ExpandSEXTINREG</a> (SDNode *Node)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Implement expansion for SIGN_EXTEND_INREG using SRL and SRA. <a href="#a1e87b1a7e949a39e858471d18f0fbd57">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/sdvalue">SDValue</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ab977dc1c87120397c5b35b6336463bc2">ExpandANY_EXTEND_VECTOR_INREG</a> (SDNode *Node)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Implement expansion for ANY_EXTEND_VECTOR_INREG. <a href="#ab977dc1c87120397c5b35b6336463bc2">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/sdvalue">SDValue</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a48474513ea98bdc42a6ad90bb7944876">ExpandSIGN_EXTEND_VECTOR_INREG</a> (SDNode *Node)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Implement expansion for SIGN_EXTEND_VECTOR_INREG. <a href="#a48474513ea98bdc42a6ad90bb7944876">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/sdvalue">SDValue</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a10fe9d6157bf8560eaff0cce1ba45643">ExpandZERO_EXTEND_VECTOR_INREG</a> (SDNode *Node)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Implement expansion for ZERO_EXTEND_VECTOR_INREG. <a href="#a10fe9d6157bf8560eaff0cce1ba45643">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/sdvalue">SDValue</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a5a9f95e687e0fd5a1a411c3b7d11ea2c">ExpandBSWAP</a> (SDNode *Node)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Expand bswap of vectors into a shuffle if legal. <a href="#a5a9f95e687e0fd5a1a411c3b7d11ea2c">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/sdvalue">SDValue</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a7c8de8c388f23f0984591711265c6661">ExpandVSELECT</a> (SDNode *Node)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Implement vselect in terms of XOR, AND, OR when blend is not supported by the target. <a href="#a7c8de8c388f23f0984591711265c6661">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/sdvalue">SDValue</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a2f0a29e9cd457dc354f5ed9002e8c12c">ExpandVP_SELECT</a> (SDNode *Node)</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/sdvalue">SDValue</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a56933cb802fc9c9a82fe4f6a34d5bf4c">ExpandVP_MERGE</a> (SDNode *Node)</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/sdvalue">SDValue</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a5dc57d630bee525742cafe3189fa97dd">ExpandVP_REM</a> (SDNode *Node)</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/sdvalue">SDValue</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a603881b7f6240338bacb603661218f8c">ExpandVP_FNEG</a> (SDNode *Node)</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/sdvalue">SDValue</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a2008980527f65e9ee79e816f3975222e">ExpandVP_FABS</a> (SDNode *Node)</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/sdvalue">SDValue</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a93a74f2e3f0afcd20f32fc2b28d39489">ExpandVP_FCOPYSIGN</a> (SDNode *Node)</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/sdvalue">SDValue</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#aeb71ae780493f849f41a662928ba9fe9">ExpandSELECT</a> (SDNode *Node)</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">std::pair&lt; <a href="/web-llvm/docs/api/classes/llvm/sdvalue">SDValue</a>, <a href="/web-llvm/docs/api/classes/llvm/sdvalue">SDValue</a> &gt;</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a57b016b84f4ca1635f9a0d4004fcd04b">ExpandLoad</a> (SDNode *N)</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/sdvalue">SDValue</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a7750e58756ec8f6deb6fd8b2c4d6ce2f">ExpandStore</a> (SDNode *N)</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/sdvalue">SDValue</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a8bc5ffe6e111eb328b3a16fca246a612">ExpandFNEG</a> (SDNode *Node)</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/sdvalue">SDValue</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a53f8ed9425685f8d4ac9d24a928f5431">ExpandFABS</a> (SDNode *Node)</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/sdvalue">SDValue</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a2d2e02e5f672027c3519ce3190259d8e">ExpandFCOPYSIGN</a> (SDNode *Node)</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#aa5cf67c7ba9b8b974bab99f69ed9af47">ExpandFSUB</a> (SDNode *Node, SmallVectorImpl&lt; SDValue &gt; &amp;Results)</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a5628a73bfa1ff873d26be45ed0ff3d36">ExpandSETCC</a> (SDNode *Node, SmallVectorImpl&lt; SDValue &gt; &amp;Results)</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/sdvalue">SDValue</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#aed97efdc3e83b6865d0a031d4451e22c">ExpandBITREVERSE</a> (SDNode *Node)</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ad7454d05a8bcba674c67932faede7dc1">ExpandUADDSUBO</a> (SDNode *Node, SmallVectorImpl&lt; SDValue &gt; &amp;Results)</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#aa78df95355579f753b3fe4b4f1ee75bd">ExpandSADDSUBO</a> (SDNode *Node, SmallVectorImpl&lt; SDValue &gt; &amp;Results)</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#aab7341704b6bf9655c8fda40caae4418">ExpandMULO</a> (SDNode *Node, SmallVectorImpl&lt; SDValue &gt; &amp;Results)</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a700799d00eaeb4448bc05be78ad735dc">ExpandFixedPointDiv</a> (SDNode *Node, SmallVectorImpl&lt; SDValue &gt; &amp;Results)</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#af1d0015036027f4542631404798228dd">ExpandStrictFPOp</a> (SDNode *Node, SmallVectorImpl&lt; SDValue &gt; &amp;Results)</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a0cd9d03983e6b0704dfcfd1b873c0113">ExpandREM</a> (SDNode *Node, SmallVectorImpl&lt; SDValue &gt; &amp;Results)</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#aa0b09e597a51406ce0d0d5ebd1a5f73f">tryExpandVecMathCall</a> (SDNode *Node, RTLIB::Libcall LC, SmallVectorImpl&lt; SDValue &gt; &amp;Results)</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ae219a8cfaf5c87dba823f685fc2cf718">tryExpandVecMathCall</a> (SDNode *Node, RTLIB::Libcall Call_F32, RTLIB::Libcall Call_F64, RTLIB::Libcall Call_F80, RTLIB::Libcall Call_F128, RTLIB::Libcall Call_PPCF128, SmallVectorImpl&lt; SDValue &gt; &amp;Results)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Try to expand the node to a vector libcall based on the result type. <a href="#ae219a8cfaf5c87dba823f685fc2cf718">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">void</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a14dcb4c9e8f36f1cc107d4ef3537be90">UnrollStrictFPOp</a> (SDNode *Node, SmallVectorImpl&lt; SDValue &gt; &amp;Results)</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a48132e71fc426c43814ed69230f4f27b">Promote</a> (SDNode *Node, SmallVectorImpl&lt; SDValue &gt; &amp;Results)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Implements vector promotion. <a href="#a48132e71fc426c43814ed69230f4f27b">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">void</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a7dc89e1332ff1ede7be0aa46260d10e0">PromoteINT_TO_FP</a> (SDNode *Node, SmallVectorImpl&lt; SDValue &gt; &amp;Results)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Implements [SU]INT_TO_FP vector promotion. <a href="#a7dc89e1332ff1ede7be0aa46260d10e0">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">void</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a3b07c6aca979c7a6b79acdf60732d0f1">PromoteFP_TO_INT</a> (SDNode *Node, SmallVectorImpl&lt; SDValue &gt; &amp;Results)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Implements FP_TO_[SU]INT vector promotion of the result type. <a href="#a3b07c6aca979c7a6b79acdf60732d0f1">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">void</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ad3d774d322a2f0e30d6aef1ff496c827">PromoteSETCC</a> (SDNode *Node, SmallVectorImpl&lt; SDValue &gt; &amp;Results)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Implements vector setcc operation promotion. <a href="#ad3d774d322a2f0e30d6aef1ff496c827">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">void</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a2934f64eb8b687aeca2405a9446d9305">PromoteSTRICT</a> (SDNode *Node, SmallVectorImpl&lt; SDValue &gt; &amp;Results)</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/selectiondag">SelectionDAG</a> &amp;</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a6def0c84146c2e22e6fbe0b057f8cdd4">DAG</a></td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/targetlowering">TargetLowering</a> &amp;</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a375c9a458397bb0e51b11cdfafdf1204">TLI</a></td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a3933c2293491a131dcbbf6dce51b0f8d">Changed</a> = false</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/smalldensemap">SmallDenseMap</a>&lt; <a href="/web-llvm/docs/api/classes/llvm/sdvalue">SDValue</a>, <a href="/web-llvm/docs/api/classes/llvm/sdvalue">SDValue</a>, 64 &gt;</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ac63f747ee8475b2702ceb0771cb8d133">LegalizedNodes</a></td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>For nodes that are of legal width, and that have more than one use, this map indicates what regularized operand to use. <a href="#ac63f747ee8475b2702ceb0771cb8d133">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

</table>


<p>Definition at line 55 of file <a href="/web-llvm/docs/api/files/lib/lib/codegen/lib/codegen/selectiondag/legalizevectorops-cpp">LegalizeVectorOps.cpp</a>.</p>


<div class="doxySectionDef">

## Public Constructors

### VectorLegalizer() {#ab3ce50c3e069741fd2cdb0216f66069b}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">anonymous{LegalizeVectorOps.cpp}::VectorLegalizer::VectorLegalizer (<a href="/web-llvm/docs/api/classes/llvm/selectiondag">SelectionDAG</a> &amp; dag)</td>
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



<p>Definition at line 193 of file <a href="/web-llvm/docs/api/files/lib/lib/codegen/lib/codegen/selectiondag/legalizevectorops-cpp">LegalizeVectorOps.cpp</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Public Member Functions

### Run() {#a45819d3524983de52fd325c7ebf6b801}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool VectorLegalizer::Run ()</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Begin legalizer the vector operations in the DAG.</p>

<p>Definition at line 197 of file <a href="/web-llvm/docs/api/files/lib/lib/codegen/lib/codegen/selectiondag/legalizevectorops-cpp">LegalizeVectorOps.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/namespaces/llvm/#a61d13d6824ec46c31260a4fd0997eda0">llvm::any_of</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/silowercontrolflow-cpp/#a4868c5d81c5ccc98c47aeab6244346a0">assert</a> and <a href="/web-llvm/docs/api/files/lib/lib/support/md5-cpp/#ac0eafdc9ee161b71e7af98af736952fd">I</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Private Member Functions

### AddLegalizedOperand() {#ab3bd711fb198612b3f217a854c6987c9}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void anonymous{LegalizeVectorOps.cpp}::VectorLegalizer::AddLegalizedOperand (<a href="/web-llvm/docs/api/classes/llvm/sdvalue">SDValue</a> From, <a href="/web-llvm/docs/api/classes/llvm/sdvalue">SDValue</a> To)</td>
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

<p>Adds a node to the translation cache.</p>

<p>Definition at line 66 of file <a href="/web-llvm/docs/api/files/lib/lib/codegen/lib/codegen/selectiondag/legalizevectorops-cpp">LegalizeVectorOps.cpp</a>.</p>

</div>
</div>

### Expand() {#ab68ff3284bb0cb541c0a5a50c7c88cac}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void VectorLegalizer::Expand (<a href="/web-llvm/docs/api/classes/llvm/sdnode">SDNode</a> * Node, <a href="/web-llvm/docs/api/classes/llvm/smallvectorimpl">SmallVectorImpl</a>&lt; <a href="/web-llvm/docs/api/classes/llvm/sdvalue">SDValue</a> &gt; &amp; Results)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Implement expand-based legalization of vector operations.</p>


<p>This is just a high-level routine to dispatch to specific code paths for operations to legalize them.</p>


<p>Definition at line 96 of file <a href="/web-llvm/docs/api/files/lib/lib/codegen/lib/codegen/selectiondag/legalizevectorops-cpp">LegalizeVectorOps.cpp</a>.</p>

</div>
</div>

### ExpandANY\_EXTEND\_VECTOR\_INREG() {#ab977dc1c87120397c5b35b6336463bc2}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">SDValue VectorLegalizer::ExpandANY_EXTEND_VECTOR_INREG (<a href="/web-llvm/docs/api/classes/llvm/sdnode">SDNode</a> * Node)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Implement expansion for ANY_EXTEND_VECTOR_INREG.</p>


<p>Shuffles the low lanes of the operand into place and bitcasts to the proper type. The contents of the bits in the extended part of each element are undef.</p>


<p>Definition at line 114 of file <a href="/web-llvm/docs/api/files/lib/lib/codegen/lib/codegen/selectiondag/legalizevectorops-cpp">LegalizeVectorOps.cpp</a>.</p>

</div>
</div>

### ExpandBITREVERSE() {#aed97efdc3e83b6865d0a031d4451e22c}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">SDValue VectorLegalizer::ExpandBITREVERSE (<a href="/web-llvm/docs/api/classes/llvm/sdnode">SDNode</a> * Node)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 149 of file <a href="/web-llvm/docs/api/files/lib/lib/codegen/lib/codegen/selectiondag/legalizevectorops-cpp">LegalizeVectorOps.cpp</a>.</p>

</div>
</div>

### ExpandBSWAP() {#a5a9f95e687e0fd5a1a411c3b7d11ea2c}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">SDValue VectorLegalizer::ExpandBSWAP (<a href="/web-llvm/docs/api/classes/llvm/sdnode">SDNode</a> * Node)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Expand bswap of vectors into a shuffle if legal.</p>

<p>Definition at line 130 of file <a href="/web-llvm/docs/api/files/lib/lib/codegen/lib/codegen/selectiondag/legalizevectorops-cpp">LegalizeVectorOps.cpp</a>.</p>

</div>
</div>

### ExpandFABS() {#a53f8ed9425685f8d4ac9d24a928f5431}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">SDValue VectorLegalizer::ExpandFABS (<a href="/web-llvm/docs/api/classes/llvm/sdnode">SDNode</a> * Node)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 145 of file <a href="/web-llvm/docs/api/files/lib/lib/codegen/lib/codegen/selectiondag/legalizevectorops-cpp">LegalizeVectorOps.cpp</a>.</p>

</div>
</div>

### ExpandFCOPYSIGN() {#a2d2e02e5f672027c3519ce3190259d8e}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">SDValue VectorLegalizer::ExpandFCOPYSIGN (<a href="/web-llvm/docs/api/classes/llvm/sdnode">SDNode</a> * Node)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 146 of file <a href="/web-llvm/docs/api/files/lib/lib/codegen/lib/codegen/selectiondag/legalizevectorops-cpp">LegalizeVectorOps.cpp</a>.</p>

</div>
</div>

### ExpandFixedPointDiv() {#a700799d00eaeb4448bc05be78ad735dc}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void VectorLegalizer::ExpandFixedPointDiv (<a href="/web-llvm/docs/api/classes/llvm/sdnode">SDNode</a> * Node, <a href="/web-llvm/docs/api/classes/llvm/smallvectorimpl">SmallVectorImpl</a>&lt; <a href="/web-llvm/docs/api/classes/llvm/sdvalue">SDValue</a> &gt; &amp; Results)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 153 of file <a href="/web-llvm/docs/api/files/lib/lib/codegen/lib/codegen/selectiondag/legalizevectorops-cpp">LegalizeVectorOps.cpp</a>.</p>

</div>
</div>

### ExpandFNEG() {#a8bc5ffe6e111eb328b3a16fca246a612}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">SDValue VectorLegalizer::ExpandFNEG (<a href="/web-llvm/docs/api/classes/llvm/sdnode">SDNode</a> * Node)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 144 of file <a href="/web-llvm/docs/api/files/lib/lib/codegen/lib/codegen/selectiondag/legalizevectorops-cpp">LegalizeVectorOps.cpp</a>.</p>

</div>
</div>

### ExpandFP\_TO\_UINT() {#aa16dbedad3f5c864ac633aebef24d38d}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void VectorLegalizer::ExpandFP_TO_UINT (<a href="/web-llvm/docs/api/classes/llvm/sdnode">SDNode</a> * Node, <a href="/web-llvm/docs/api/classes/llvm/smallvectorimpl">SmallVectorImpl</a>&lt; <a href="/web-llvm/docs/api/classes/llvm/sdvalue">SDValue</a> &gt; &amp; Results)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Implements expansion for FP_TO_UINT; falls back to UnrollVectorOp if FP_TO_SINT isn't legal.</p>

<p>Definition at line 100 of file <a href="/web-llvm/docs/api/files/lib/lib/codegen/lib/codegen/selectiondag/legalizevectorops-cpp">LegalizeVectorOps.cpp</a>.</p>

</div>
</div>

### ExpandFSUB() {#aa5cf67c7ba9b8b974bab99f69ed9af47}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void VectorLegalizer::ExpandFSUB (<a href="/web-llvm/docs/api/classes/llvm/sdnode">SDNode</a> * Node, <a href="/web-llvm/docs/api/classes/llvm/smallvectorimpl">SmallVectorImpl</a>&lt; <a href="/web-llvm/docs/api/classes/llvm/sdvalue">SDValue</a> &gt; &amp; Results)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 147 of file <a href="/web-llvm/docs/api/files/lib/lib/codegen/lib/codegen/selectiondag/legalizevectorops-cpp">LegalizeVectorOps.cpp</a>.</p>

</div>
</div>

### ExpandLoad() {#a57b016b84f4ca1635f9a0d4004fcd04b}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">std::pair&lt; SDValue, SDValue &gt; VectorLegalizer::ExpandLoad (<a href="/web-llvm/docs/api/classes/llvm/sdnode">SDNode</a> * N)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 142 of file <a href="/web-llvm/docs/api/files/lib/lib/codegen/lib/codegen/selectiondag/legalizevectorops-cpp">LegalizeVectorOps.cpp</a>.</p>

</div>
</div>

### ExpandMULO() {#aab7341704b6bf9655c8fda40caae4418}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void VectorLegalizer::ExpandMULO (<a href="/web-llvm/docs/api/classes/llvm/sdnode">SDNode</a> * Node, <a href="/web-llvm/docs/api/classes/llvm/smallvectorimpl">SmallVectorImpl</a>&lt; <a href="/web-llvm/docs/api/classes/llvm/sdvalue">SDValue</a> &gt; &amp; Results)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 152 of file <a href="/web-llvm/docs/api/files/lib/lib/codegen/lib/codegen/selectiondag/legalizevectorops-cpp">LegalizeVectorOps.cpp</a>.</p>

</div>
</div>

### ExpandREM() {#a0cd9d03983e6b0704dfcfd1b873c0113}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void VectorLegalizer::ExpandREM (<a href="/web-llvm/docs/api/classes/llvm/sdnode">SDNode</a> * Node, <a href="/web-llvm/docs/api/classes/llvm/smallvectorimpl">SmallVectorImpl</a>&lt; <a href="/web-llvm/docs/api/classes/llvm/sdvalue">SDValue</a> &gt; &amp; Results)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 155 of file <a href="/web-llvm/docs/api/files/lib/lib/codegen/lib/codegen/selectiondag/legalizevectorops-cpp">LegalizeVectorOps.cpp</a>.</p>

</div>
</div>

### ExpandSADDSUBO() {#aa78df95355579f753b3fe4b4f1ee75bd}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void VectorLegalizer::ExpandSADDSUBO (<a href="/web-llvm/docs/api/classes/llvm/sdnode">SDNode</a> * Node, <a href="/web-llvm/docs/api/classes/llvm/smallvectorimpl">SmallVectorImpl</a>&lt; <a href="/web-llvm/docs/api/classes/llvm/sdvalue">SDValue</a> &gt; &amp; Results)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 151 of file <a href="/web-llvm/docs/api/files/lib/lib/codegen/lib/codegen/selectiondag/legalizevectorops-cpp">LegalizeVectorOps.cpp</a>.</p>

</div>
</div>

### ExpandSELECT() {#aeb71ae780493f849f41a662928ba9fe9}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">SDValue VectorLegalizer::ExpandSELECT (<a href="/web-llvm/docs/api/classes/llvm/sdnode">SDNode</a> * Node)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 141 of file <a href="/web-llvm/docs/api/files/lib/lib/codegen/lib/codegen/selectiondag/legalizevectorops-cpp">LegalizeVectorOps.cpp</a>.</p>

</div>
</div>

### ExpandSETCC() {#a5628a73bfa1ff873d26be45ed0ff3d36}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void VectorLegalizer::ExpandSETCC (<a href="/web-llvm/docs/api/classes/llvm/sdnode">SDNode</a> * Node, <a href="/web-llvm/docs/api/classes/llvm/smallvectorimpl">SmallVectorImpl</a>&lt; <a href="/web-llvm/docs/api/classes/llvm/sdvalue">SDValue</a> &gt; &amp; Results)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 148 of file <a href="/web-llvm/docs/api/files/lib/lib/codegen/lib/codegen/selectiondag/legalizevectorops-cpp">LegalizeVectorOps.cpp</a>.</p>

</div>
</div>

### ExpandSEXTINREG() {#a1e87b1a7e949a39e858471d18f0fbd57}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">SDValue VectorLegalizer::ExpandSEXTINREG (<a href="/web-llvm/docs/api/classes/llvm/sdnode">SDNode</a> * Node)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Implement expansion for SIGN_EXTEND_INREG using SRL and SRA.</p>

<p>Definition at line 107 of file <a href="/web-llvm/docs/api/files/lib/lib/codegen/lib/codegen/selectiondag/legalizevectorops-cpp">LegalizeVectorOps.cpp</a>.</p>

</div>
</div>

### ExpandSIGN\_EXTEND\_VECTOR\_INREG() {#a48474513ea98bdc42a6ad90bb7944876}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">SDValue VectorLegalizer::ExpandSIGN_EXTEND_VECTOR_INREG (<a href="/web-llvm/docs/api/classes/llvm/sdnode">SDNode</a> * Node)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Implement expansion for SIGN_EXTEND_VECTOR_INREG.</p>


<p>Shuffles the low lanes of the operand into place, bitcasts to the proper type, then shifts left and arithmetic shifts right to introduce a sign extension.</p>


<p>Definition at line 121 of file <a href="/web-llvm/docs/api/files/lib/lib/codegen/lib/codegen/selectiondag/legalizevectorops-cpp">LegalizeVectorOps.cpp</a>.</p>

</div>
</div>

### ExpandStore() {#a7750e58756ec8f6deb6fd8b2c4d6ce2f}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">SDValue VectorLegalizer::ExpandStore (<a href="/web-llvm/docs/api/classes/llvm/sdnode">SDNode</a> * N)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 143 of file <a href="/web-llvm/docs/api/files/lib/lib/codegen/lib/codegen/selectiondag/legalizevectorops-cpp">LegalizeVectorOps.cpp</a>.</p>

</div>
</div>

### ExpandStrictFPOp() {#af1d0015036027f4542631404798228dd}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void VectorLegalizer::ExpandStrictFPOp (<a href="/web-llvm/docs/api/classes/llvm/sdnode">SDNode</a> * Node, <a href="/web-llvm/docs/api/classes/llvm/smallvectorimpl">SmallVectorImpl</a>&lt; <a href="/web-llvm/docs/api/classes/llvm/sdvalue">SDValue</a> &gt; &amp; Results)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 154 of file <a href="/web-llvm/docs/api/files/lib/lib/codegen/lib/codegen/selectiondag/legalizevectorops-cpp">LegalizeVectorOps.cpp</a>.</p>

</div>
</div>

### ExpandUADDSUBO() {#ad7454d05a8bcba674c67932faede7dc1}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void VectorLegalizer::ExpandUADDSUBO (<a href="/web-llvm/docs/api/classes/llvm/sdnode">SDNode</a> * Node, <a href="/web-llvm/docs/api/classes/llvm/smallvectorimpl">SmallVectorImpl</a>&lt; <a href="/web-llvm/docs/api/classes/llvm/sdvalue">SDValue</a> &gt; &amp; Results)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 150 of file <a href="/web-llvm/docs/api/files/lib/lib/codegen/lib/codegen/selectiondag/legalizevectorops-cpp">LegalizeVectorOps.cpp</a>.</p>

</div>
</div>

### ExpandUINT\_TO\_FLOAT() {#aae7c2c883dfa2673e8bd68e3169cd8f2}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void VectorLegalizer::ExpandUINT_TO_FLOAT (<a href="/web-llvm/docs/api/classes/llvm/sdnode">SDNode</a> * Node, <a href="/web-llvm/docs/api/classes/llvm/smallvectorimpl">SmallVectorImpl</a>&lt; <a href="/web-llvm/docs/api/classes/llvm/sdvalue">SDValue</a> &gt; &amp; Results)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Implements expansion for UINT_TO_FLOAT; falls back to UnrollVectorOp if SINT_TO_FLOAT and SHR on vectors isn't legal.</p>

<p>Definition at line 104 of file <a href="/web-llvm/docs/api/files/lib/lib/codegen/lib/codegen/selectiondag/legalizevectorops-cpp">LegalizeVectorOps.cpp</a>.</p>

</div>
</div>

### ExpandVP\_FABS() {#a2008980527f65e9ee79e816f3975222e}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">SDValue VectorLegalizer::ExpandVP_FABS (<a href="/web-llvm/docs/api/classes/llvm/sdnode">SDNode</a> * Node)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 139 of file <a href="/web-llvm/docs/api/files/lib/lib/codegen/lib/codegen/selectiondag/legalizevectorops-cpp">LegalizeVectorOps.cpp</a>.</p>

</div>
</div>

### ExpandVP\_FCOPYSIGN() {#a93a74f2e3f0afcd20f32fc2b28d39489}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">SDValue VectorLegalizer::ExpandVP_FCOPYSIGN (<a href="/web-llvm/docs/api/classes/llvm/sdnode">SDNode</a> * Node)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 140 of file <a href="/web-llvm/docs/api/files/lib/lib/codegen/lib/codegen/selectiondag/legalizevectorops-cpp">LegalizeVectorOps.cpp</a>.</p>

</div>
</div>

### ExpandVP\_FNEG() {#a603881b7f6240338bacb603661218f8c}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">SDValue VectorLegalizer::ExpandVP_FNEG (<a href="/web-llvm/docs/api/classes/llvm/sdnode">SDNode</a> * Node)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 138 of file <a href="/web-llvm/docs/api/files/lib/lib/codegen/lib/codegen/selectiondag/legalizevectorops-cpp">LegalizeVectorOps.cpp</a>.</p>

</div>
</div>

### ExpandVP\_MERGE() {#a56933cb802fc9c9a82fe4f6a34d5bf4c}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">SDValue VectorLegalizer::ExpandVP_MERGE (<a href="/web-llvm/docs/api/classes/llvm/sdnode">SDNode</a> * Node)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 136 of file <a href="/web-llvm/docs/api/files/lib/lib/codegen/lib/codegen/selectiondag/legalizevectorops-cpp">LegalizeVectorOps.cpp</a>.</p>

</div>
</div>

### ExpandVP\_REM() {#a5dc57d630bee525742cafe3189fa97dd}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">SDValue VectorLegalizer::ExpandVP_REM (<a href="/web-llvm/docs/api/classes/llvm/sdnode">SDNode</a> * Node)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 137 of file <a href="/web-llvm/docs/api/files/lib/lib/codegen/lib/codegen/selectiondag/legalizevectorops-cpp">LegalizeVectorOps.cpp</a>.</p>

</div>
</div>

### ExpandVP\_SELECT() {#a2f0a29e9cd457dc354f5ed9002e8c12c}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">SDValue VectorLegalizer::ExpandVP_SELECT (<a href="/web-llvm/docs/api/classes/llvm/sdnode">SDNode</a> * Node)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 135 of file <a href="/web-llvm/docs/api/files/lib/lib/codegen/lib/codegen/selectiondag/legalizevectorops-cpp">LegalizeVectorOps.cpp</a>.</p>

</div>
</div>

### ExpandVSELECT() {#a7c8de8c388f23f0984591711265c6661}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">SDValue VectorLegalizer::ExpandVSELECT (<a href="/web-llvm/docs/api/classes/llvm/sdnode">SDNode</a> * Node)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Implement vselect in terms of XOR, AND, OR when blend is not supported by the target.</p>

<p>Definition at line 134 of file <a href="/web-llvm/docs/api/files/lib/lib/codegen/lib/codegen/selectiondag/legalizevectorops-cpp">LegalizeVectorOps.cpp</a>.</p>

</div>
</div>

### ExpandZERO\_EXTEND\_VECTOR\_INREG() {#a10fe9d6157bf8560eaff0cce1ba45643}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">SDValue VectorLegalizer::ExpandZERO_EXTEND_VECTOR_INREG (<a href="/web-llvm/docs/api/classes/llvm/sdnode">SDNode</a> * Node)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Implement expansion for ZERO_EXTEND_VECTOR_INREG.</p>


<p>Shuffles the low lanes of the operand into place and blends zeros into the remaining lanes, finally bitcasting to the proper type.</p>


<p>Definition at line 127 of file <a href="/web-llvm/docs/api/files/lib/lib/codegen/lib/codegen/selectiondag/legalizevectorops-cpp">LegalizeVectorOps.cpp</a>.</p>

</div>
</div>

### LegalizeOp() {#a75ee7b55ead91f4b061d055b61a133a7}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">SDValue VectorLegalizer::LegalizeOp (<a href="/web-llvm/docs/api/classes/llvm/sdvalue">SDValue</a> Op)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Legalizes the given node.</p>

<p>Definition at line 74 of file <a href="/web-llvm/docs/api/files/lib/lib/codegen/lib/codegen/selectiondag/legalizevectorops-cpp">LegalizeVectorOps.cpp</a>.</p>

</div>
</div>

### LowerOperationWrapper() {#ab0bfaa11692f703bbe7db577d57c0c86}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool VectorLegalizer::LowerOperationWrapper (<a href="/web-llvm/docs/api/classes/llvm/sdnode">SDNode</a> * N, <a href="/web-llvm/docs/api/classes/llvm/smallvectorimpl">SmallVectorImpl</a>&lt; <a href="/web-llvm/docs/api/classes/llvm/sdvalue">SDValue</a> &gt; &amp; Results)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Wrapper to interface LowerOperation with a vector of Results.</p>


<p>Returns false if the target wants to use default expansion. Otherwise returns true. If return is true and the Results are empty, then the target wants to keep the input node as is.</p>


<p>Definition at line 87 of file <a href="/web-llvm/docs/api/files/lib/lib/codegen/lib/codegen/selectiondag/legalizevectorops-cpp">LegalizeVectorOps.cpp</a>.</p>

</div>
</div>

### Promote() {#a48132e71fc426c43814ed69230f4f27b}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void VectorLegalizer::Promote (<a href="/web-llvm/docs/api/classes/llvm/sdnode">SDNode</a> * Node, <a href="/web-llvm/docs/api/classes/llvm/smallvectorimpl">SmallVectorImpl</a>&lt; <a href="/web-llvm/docs/api/classes/llvm/sdvalue">SDValue</a> &gt; &amp; Results)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Implements vector promotion.</p>


<p>This is essentially just bitcasting the operands to a different type and bitcasting the result back to the original type.</p>


<p>Definition at line 171 of file <a href="/web-llvm/docs/api/files/lib/lib/codegen/lib/codegen/selectiondag/legalizevectorops-cpp">LegalizeVectorOps.cpp</a>.</p>

</div>
</div>

### PromoteFP\_TO\_INT() {#a3b07c6aca979c7a6b79acdf60732d0f1}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void VectorLegalizer::PromoteFP_TO_INT (<a href="/web-llvm/docs/api/classes/llvm/sdnode">SDNode</a> * Node, <a href="/web-llvm/docs/api/classes/llvm/smallvectorimpl">SmallVectorImpl</a>&lt; <a href="/web-llvm/docs/api/classes/llvm/sdvalue">SDValue</a> &gt; &amp; Results)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Implements FP_TO_[SU]INT vector promotion of the result type.</p>


<p>It is promoted to a larger integer type. The result is then truncated back to the original type.</p>


<p>Definition at line 182 of file <a href="/web-llvm/docs/api/files/lib/lib/codegen/lib/codegen/selectiondag/legalizevectorops-cpp">LegalizeVectorOps.cpp</a>.</p>

</div>
</div>

### PromoteINT\_TO\_FP() {#a7dc89e1332ff1ede7be0aa46260d10e0}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void VectorLegalizer::PromoteINT_TO_FP (<a href="/web-llvm/docs/api/classes/llvm/sdnode">SDNode</a> * Node, <a href="/web-llvm/docs/api/classes/llvm/smallvectorimpl">SmallVectorImpl</a>&lt; <a href="/web-llvm/docs/api/classes/llvm/sdvalue">SDValue</a> &gt; &amp; Results)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Implements [SU]INT_TO_FP vector promotion.</p>


<p>This is a [zs]ext of the input operand to a larger integer type.</p>


<p>Definition at line 176 of file <a href="/web-llvm/docs/api/files/lib/lib/codegen/lib/codegen/selectiondag/legalizevectorops-cpp">LegalizeVectorOps.cpp</a>.</p>

</div>
</div>

### PromoteSETCC() {#ad3d774d322a2f0e30d6aef1ff496c827}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void VectorLegalizer::PromoteSETCC (<a href="/web-llvm/docs/api/classes/llvm/sdnode">SDNode</a> * Node, <a href="/web-llvm/docs/api/classes/llvm/smallvectorimpl">SmallVectorImpl</a>&lt; <a href="/web-llvm/docs/api/classes/llvm/sdvalue">SDValue</a> &gt; &amp; Results)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Implements vector setcc operation promotion.</p>


<p>All vector operands are promoted to a vector type with larger element type.</p>


<p>Definition at line 188 of file <a href="/web-llvm/docs/api/files/lib/lib/codegen/lib/codegen/selectiondag/legalizevectorops-cpp">LegalizeVectorOps.cpp</a>.</p>

</div>
</div>

### PromoteSTRICT() {#a2934f64eb8b687aeca2405a9446d9305}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void VectorLegalizer::PromoteSTRICT (<a href="/web-llvm/docs/api/classes/llvm/sdnode">SDNode</a> * Node, <a href="/web-llvm/docs/api/classes/llvm/smallvectorimpl">SmallVectorImpl</a>&lt; <a href="/web-llvm/docs/api/classes/llvm/sdvalue">SDValue</a> &gt; &amp; Results)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 190 of file <a href="/web-llvm/docs/api/files/lib/lib/codegen/lib/codegen/selectiondag/legalizevectorops-cpp">LegalizeVectorOps.cpp</a>.</p>

</div>
</div>

### RecursivelyLegalizeResults() {#a0aa964dbf1d8e1f545d8abbf957f4890}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">SDValue VectorLegalizer::RecursivelyLegalizeResults (<a href="/web-llvm/docs/api/classes/llvm/sdvalue">SDValue</a> Op, <a href="/web-llvm/docs/api/classes/llvm/mutablearrayref">MutableArrayRef</a>&lt; <a href="/web-llvm/docs/api/classes/llvm/sdvalue">SDValue</a> &gt; Results)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Make sure Results are legal and update the translation cache.</p>

<p>Definition at line 80 of file <a href="/web-llvm/docs/api/files/lib/lib/codegen/lib/codegen/selectiondag/legalizevectorops-cpp">LegalizeVectorOps.cpp</a>.</p>

</div>
</div>

### TranslateLegalizeResults() {#ad9f7ba7bd51759afc9616783918a4774}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">SDValue VectorLegalizer::TranslateLegalizeResults (<a href="/web-llvm/docs/api/classes/llvm/sdvalue">SDValue</a> Op, <a href="/web-llvm/docs/api/classes/llvm/sdnode">SDNode</a> * Result)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Assuming the node is legal, "legalize" the results.</p>

<p>Definition at line 77 of file <a href="/web-llvm/docs/api/files/lib/lib/codegen/lib/codegen/selectiondag/legalizevectorops-cpp">LegalizeVectorOps.cpp</a>.</p>

</div>
</div>

### tryExpandVecMathCall() {#aa0b09e597a51406ce0d0d5ebd1a5f73f}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool VectorLegalizer::tryExpandVecMathCall (<a href="/web-llvm/docs/api/classes/llvm/sdnode">SDNode</a> * Node, <a href="/web-llvm/docs/api/namespaces/llvm/rtlib/#a50a0bab21f1d14a86a1483ec283e4447">RTLIB::Libcall</a> LC, <a href="/web-llvm/docs/api/classes/llvm/smallvectorimpl">SmallVectorImpl</a>&lt; <a href="/web-llvm/docs/api/classes/llvm/sdvalue">SDValue</a> &gt; &amp; Results)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 157 of file <a href="/web-llvm/docs/api/files/lib/lib/codegen/lib/codegen/selectiondag/legalizevectorops-cpp">LegalizeVectorOps.cpp</a>.</p>

</div>
</div>

### tryExpandVecMathCall() {#ae219a8cfaf5c87dba823f685fc2cf718}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool VectorLegalizer::tryExpandVecMathCall (<a href="/web-llvm/docs/api/classes/llvm/sdnode">SDNode</a> * Node, <a href="/web-llvm/docs/api/namespaces/llvm/rtlib/#a50a0bab21f1d14a86a1483ec283e4447">RTLIB::Libcall</a> Call_F32, <a href="/web-llvm/docs/api/namespaces/llvm/rtlib/#a50a0bab21f1d14a86a1483ec283e4447">RTLIB::Libcall</a> Call_F64, <a href="/web-llvm/docs/api/namespaces/llvm/rtlib/#a50a0bab21f1d14a86a1483ec283e4447">RTLIB::Libcall</a> Call_F80, <a href="/web-llvm/docs/api/namespaces/llvm/rtlib/#a50a0bab21f1d14a86a1483ec283e4447">RTLIB::Libcall</a> Call_F128, <a href="/web-llvm/docs/api/namespaces/llvm/rtlib/#a50a0bab21f1d14a86a1483ec283e4447">RTLIB::Libcall</a> Call_PPCF128, <a href="/web-llvm/docs/api/classes/llvm/smallvectorimpl">SmallVectorImpl</a>&lt; <a href="/web-llvm/docs/api/classes/llvm/sdvalue">SDValue</a> &gt; &amp; Results)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Try to expand the node to a vector libcall based on the result type.</p>

<p>Definition at line 159 of file <a href="/web-llvm/docs/api/files/lib/lib/codegen/lib/codegen/selectiondag/legalizevectorops-cpp">LegalizeVectorOps.cpp</a>.</p>

</div>
</div>

### UnrollStrictFPOp() {#a14dcb4c9e8f36f1cc107d4ef3537be90}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void VectorLegalizer::UnrollStrictFPOp (<a href="/web-llvm/docs/api/classes/llvm/sdnode">SDNode</a> * Node, <a href="/web-llvm/docs/api/classes/llvm/smallvectorimpl">SmallVectorImpl</a>&lt; <a href="/web-llvm/docs/api/classes/llvm/sdvalue">SDValue</a> &gt; &amp; Results)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 165 of file <a href="/web-llvm/docs/api/files/lib/lib/codegen/lib/codegen/selectiondag/legalizevectorops-cpp">LegalizeVectorOps.cpp</a>.</p>

</div>
</div>

### UnrollVSETCC() {#ae7e249d47be4ecc4b6d7b903c2253122}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">SDValue VectorLegalizer::UnrollVSETCC (<a href="/web-llvm/docs/api/classes/llvm/sdnode">SDNode</a> * Node)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Implements unrolling a VSETCC.</p>

<p>Definition at line 90 of file <a href="/web-llvm/docs/api/files/lib/lib/codegen/lib/codegen/selectiondag/legalizevectorops-cpp">LegalizeVectorOps.cpp</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Private Member Attributes

### Changed {#a3933c2293491a131dcbbf6dce51b0f8d}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool anonymous{LegalizeVectorOps.cpp}::VectorLegalizer::Changed = false</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 58 of file <a href="/web-llvm/docs/api/files/lib/lib/codegen/lib/codegen/selectiondag/legalizevectorops-cpp">LegalizeVectorOps.cpp</a>.</p>

</div>
</div>

### DAG {#a6def0c84146c2e22e6fbe0b057f8cdd4}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">SelectionDAG&amp; anonymous{LegalizeVectorOps.cpp}::VectorLegalizer::DAG</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 56 of file <a href="/web-llvm/docs/api/files/lib/lib/codegen/lib/codegen/selectiondag/legalizevectorops-cpp">LegalizeVectorOps.cpp</a>.</p>

</div>
</div>

### LegalizedNodes {#ac63f747ee8475b2702ceb0771cb8d133}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">SmallDenseMap&lt;SDValue, SDValue, 64&gt; anonymous{LegalizeVectorOps.cpp}::VectorLegalizer::LegalizedNodes</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>For nodes that are of legal width, and that have more than one use, this map indicates what regularized operand to use.</p>


<p>This allows us to avoid legalizing the same thing more than once.</p>


<p>Definition at line 63 of file <a href="/web-llvm/docs/api/files/lib/lib/codegen/lib/codegen/selectiondag/legalizevectorops-cpp">LegalizeVectorOps.cpp</a>.</p>

</div>
</div>

### TLI {#a375c9a458397bb0e51b11cdfafdf1204}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">const TargetLowering&amp; anonymous{LegalizeVectorOps.cpp}::VectorLegalizer::TLI</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 57 of file <a href="/web-llvm/docs/api/files/lib/lib/codegen/lib/codegen/selectiondag/legalizevectorops-cpp">LegalizeVectorOps.cpp</a>.</p>

</div>
</div>

</div>

<hr/>

The documentation for this class was generated from the following file:

<ul>
<li><a href="/web-llvm/docs/api/files/lib/lib/codegen/lib/codegen/selectiondag/legalizevectorops-cpp">LegalizeVectorOps.cpp</a></li>
</ul>

<hr/>

<p class="doxyGeneratedBy">Generated via <a href="https://github.com/xpack/doxygen2docusaurus">doxygen2docusaurus</a> by <a href="https://www.doxygen.nl">Doxygen</a> 1.15.0.</p>

</div>
