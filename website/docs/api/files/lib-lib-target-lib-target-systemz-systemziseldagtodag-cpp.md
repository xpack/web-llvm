---

# DO NOT EDIT!
# Automatically generated via doxygen2docusaurus by Doxygen.

slug: /api/files/lib/lib/target/lib/target/systemz/systemziseldagtodag-cpp
custom_edit_url: null
toc_max_heading_level: 4
keywords:
  - doxygen
  - reference
  - file

---

<div class="doxyPage">

# `SystemZISelDAGToDAG.cpp` File



## Included Headers

<div class="doxyIncludesList">#include "<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/systemz/systemztargetmachine-h">SystemZTargetMachine.h</a>"
#include "<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/systemz/systemzisellowering-h">SystemZISelLowering.h</a>"
#include "<a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/analysis/aliasanalysis-h">llvm/Analysis/AliasAnalysis.h</a>"
#include "<a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/codegen/selectiondagisel-h">llvm/CodeGen/SelectionDAGISel.h</a>"
#include "<a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/support/debug-h">llvm/Support/Debug.h</a>"
#include "<a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/support/knownbits-h">llvm/Support/KnownBits.h</a>"
#include "<a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/support/raw-ostream-h">llvm/Support/raw_ostream.h</a>"
#include "SystemZGenDAGISel.inc"
</div>

## Namespaces Index

<table class="doxyMembersIndex">

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">namespace</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="/web-llvm/docs/api/namespaces/anonymous-systemziseldagtodag-cpp-">anonymous{SystemZISelDAGToDAG.cpp}</a></td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">struct</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="/web-llvm/docs/api/structs/anonymous-systemziseldagtodag-cpp-/systemzaddressingmode">SystemZAddressingMode</a></td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">struct</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="/web-llvm/docs/api/structs/anonymous-systemziseldagtodag-cpp-/rxsbgoperands">RxSBGOperands</a></td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">class</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="/web-llvm/docs/api/classes/anonymous-systemziseldagtodag-cpp-/systemzdagtodagisel">SystemZDAGToDAGISel</a></td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">class</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="/web-llvm/docs/api/classes/anonymous-systemziseldagtodag-cpp-/systemzdagtodagisellegacy">SystemZDAGToDAGISelLegacy</a></td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">struct</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="/web-llvm/docs/api/structs/anonymous-systemziseldagtodag-cpp-/ipmconversion">IPMConversion</a></td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">static bool</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a2fa6af6bfd047fb63d886637fe12e498">selectDisp</a> (SystemZAddressingMode::DispRange DR, int64_t Val)</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">static void</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a0524144f93dd6479626daa0354221241">changeComponent</a> (SystemZAddressingMode &amp;AM, bool IsBase, SDValue Value)</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a4fb6befd188d4185b174e86dedab8015">expandAdjDynAlloc</a> (SystemZAddressingMode &amp;AM, bool IsBase, SDValue Value)</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a76209ff948be2ad224249f3e5a00dd44">expandIndex</a> (SystemZAddressingMode &amp;AM, SDValue Base, SDValue Index)</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a8054b3854a083e947e97f07f6a5fd396">expandDisp</a> (SystemZAddressingMode &amp;AM, bool IsBase, SDValue Op0, uint64_t Op1)</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a585775891613ee08dcba83bd7c407162">isValidDisp</a> (SystemZAddressingMode::DispRange DR, int64_t Val)</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ab40a430aafd22186cbdbd94ec923b02b">shouldUseLA</a> (SDNode *Base, int64_t Disp, SDNode *Index)</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">static void</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ae61c505ef5dc38733d7b12b91e545a44">insertDAGNode</a> (SelectionDAG *DAG, SDNode *Pos, SDValue N)</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a7cc7fca619b4ff2c891081311105af67">maskMatters</a> (RxSBGOperands &amp;RxSBG, uint64_t Mask)</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a50de01231a46d2b82c41aebd0c413690">isFusableLoadOpStorePattern</a> (StoreSDNode *StoreNode, SDValue StoredVal, SelectionDAG *CurDAG, LoadSDNode *&amp;LoadNode, SDValue &amp;InputChain)</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">static IPMConversion</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a28e0a0edbf89edb6e77b86a94974848d">getIPMConversion</a> (unsigned CCValid, unsigned CCMask)</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ad78e062f62e0d6e453941fb4ca843e4d">DEBUG_TYPE</a>&nbsp;&nbsp;&nbsp;"systemz-isel"</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#acf9235cddac26ff3f81e8c56849bcaac">PASS_NAME</a>&nbsp;&nbsp;&nbsp;"SystemZ DAG-&gt;DAG <a href="/web-llvm/docs/api/classes/llvm/pattern">Pattern</a> <a href="/web-llvm/docs/api/classes/llvm/instruction">Instruction</a> Selection"</td>
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

### changeComponent() {#a0524144f93dd6479626daa0354221241}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void changeComponent (SystemZAddressingMode &amp; AM, bool IsBase, <a href="/web-llvm/docs/api/classes/llvm/sdvalue">SDValue</a> Value)</td>
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



<p>Definition at line 429 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/systemz/systemziseldagtodag-cpp">SystemZISelDAGToDAG.cpp</a>.</p>


<p>Referenced by <a href="#a4fb6befd188d4185b174e86dedab8015">expandAdjDynAlloc</a> and <a href="#a8054b3854a083e947e97f07f6a5fd396">expandDisp</a>.</p>

</div>
</div>

### expandAdjDynAlloc() {#a4fb6befd188d4185b174e86dedab8015}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool expandAdjDynAlloc (SystemZAddressingMode &amp; AM, bool IsBase, <a href="/web-llvm/docs/api/classes/llvm/sdvalue">SDValue</a> Value)</td>
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



<p>Definition at line 440 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/systemz/systemziseldagtodag-cpp">SystemZISelDAGToDAG.cpp</a>.</p>


<p>Reference <a href="#a0524144f93dd6479626daa0354221241">changeComponent</a>.</p>

</div>
</div>

### expandDisp() {#a8054b3854a083e947e97f07f6a5fd396}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool expandDisp (SystemZAddressingMode &amp; AM, bool IsBase, <a href="/web-llvm/docs/api/classes/llvm/sdvalue">SDValue</a> Op0, uint64_t Op1)</td>
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



<p>Definition at line 464 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/systemz/systemziseldagtodag-cpp">SystemZISelDAGToDAG.cpp</a>.</p>


<p>References <a href="#a0524144f93dd6479626daa0354221241">changeComponent</a> and <a href="#a2fa6af6bfd047fb63d886637fe12e498">selectDisp</a>.</p>

</div>
</div>

### expandIndex() {#a76209ff948be2ad224249f3e5a00dd44}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool expandIndex (SystemZAddressingMode &amp; AM, <a href="/web-llvm/docs/api/classes/llvm/sdvalue">SDValue</a> Base, <a href="/web-llvm/docs/api/classes/llvm/sdvalue">SDValue</a> Index)</td>
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



<p>Definition at line 452 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/systemz/systemziseldagtodag-cpp">SystemZISelDAGToDAG.cpp</a>.</p>


<p>Reference <a href="/web-llvm/docs/api/namespaces/llvm/sampleprof/#a702f69807459cc25db5754a5f179d3fcaf6fbeb8fa9f451468611536b00878d41">llvm::sampleprof::Base</a>.</p>

</div>
</div>

### getIPMConversion() {#a28e0a0edbf89edb6e77b86a94974848d}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">IPMConversion getIPMConversion (unsigned CCValid, unsigned CCMask)</td>
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



<p>Definition at line 1946 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/systemz/systemziseldagtodag-cpp">SystemZISelDAGToDAG.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/namespaces/llvm/systemz/#a14b31497ae4b898370352164acc3b5f8">llvm::SystemZ::CCMASK_0</a>, <a href="/web-llvm/docs/api/namespaces/llvm/systemz/#a3e4f7a3f70ff22719bebc0dedfa6f5d4">llvm::SystemZ::CCMASK_1</a>, <a href="/web-llvm/docs/api/namespaces/llvm/systemz/#aedfe0ac9b427e32574e7eafa44518c95">llvm::SystemZ::CCMASK_2</a>, <a href="/web-llvm/docs/api/namespaces/llvm/systemz/#abfe77bb849cf01dbc4b6fc10e091395e">llvm::SystemZ::CCMASK_3</a>, <a href="/web-llvm/docs/api/namespaces/llvm/systemz/#a739201f9c14177326c5b3dd889dc51a5">llvm::SystemZ::IPM_CC</a>, <a href="/web-llvm/docs/api/structs/anonymous-systemziseldagtodag-cpp-/ipmconversion/#ac9b8b45ddc556a9fa8375d7b8695fcd5">anonymous{SystemZISelDAGToDAG.cpp}::IPMConversion::IPMConversion</a> and <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/support/errorhandling-h/#ace243f5c25697a1107cce46626b3dc94">llvm_unreachable</a>.</p>

</div>
</div>

### insertDAGNode() {#ae61c505ef5dc38733d7b12b91e545a44}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void insertDAGNode (<a href="/web-llvm/docs/api/classes/llvm/selectiondag">SelectionDAG</a> * DAG, <a href="/web-llvm/docs/api/classes/llvm/sdnode">SDNode</a> * Pos, <a href="/web-llvm/docs/api/classes/llvm/sdvalue">SDValue</a> N)</td>
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



<p>Definition at line 638 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/systemz/systemziseldagtodag-cpp">SystemZISelDAGToDAG.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/classes/llvm/ilist-node-impl/#af719fc783be6589465137d997701a432">llvm::ilist_node_impl&lt; OptionsT &gt;::getIterator</a>, <a href="/web-llvm/docs/api/classes/llvm/sdnode/#a1bdddc5f08b7b8b77e2518296dd4d84f">llvm::SDNode::getNodeId</a>, <a href="/web-llvm/docs/api/classes/llvm/selectiondagisel/#a483127dd84f9da223f9fe5d20a0367a8">llvm::SelectionDAGISel::getUninvalidatedNodeId</a>, <a href="/web-llvm/docs/api/classes/llvm/selectiondagisel/#af26c0de7ef8200c67d515229ac1f5453">llvm::SelectionDAGISel::InvalidateNodeId</a>, <a href="/web-llvm/docs/api/files/lib/lib/support/regcomp-c/#a0240ac851181b84ac374872dc5434ee4">N</a> and <a href="/web-llvm/docs/api/classes/llvm/selectiondag/#aed6667e93ace54abed8e4432b7b88927">llvm::SelectionDAG::RepositionNode</a>.</p>

</div>
</div>

### isFusableLoadOpStorePattern() {#a50de01231a46d2b82c41aebd0c413690}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool isFusableLoadOpStorePattern (<a href="/web-llvm/docs/api/classes/llvm/storesdnode">StoreSDNode</a> * StoreNode, <a href="/web-llvm/docs/api/classes/llvm/sdvalue">SDValue</a> StoredVal, <a href="/web-llvm/docs/api/classes/llvm/selectiondag">SelectionDAG</a> * CurDAG, <a href="/web-llvm/docs/api/classes/llvm/loadsdnode">LoadSDNode</a> *&amp; LoadNode, <a href="/web-llvm/docs/api/classes/llvm/sdvalue">SDValue</a> &amp; InputChain)</td>
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



<p>Definition at line 1313 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/systemz/systemziseldagtodag-cpp">SystemZISelDAGToDAG.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/namespaces/llvm/#ac4fc845f5ed92de63cd4474f128f5fc5">llvm::cast</a>, <a href="/web-llvm/docs/api/classes/llvm/loadsdnode/#a20fd5ba47db6a4cc8ad9d197fc1bbbee">llvm::LoadSDNode::getBasePtr</a>, <a href="/web-llvm/docs/api/classes/llvm/storesdnode/#a46c9e231f45e8c83b88089c0b013b87b">llvm::StoreSDNode::getBasePtr</a>, <a href="/web-llvm/docs/api/classes/llvm/memsdnode/#ab858661e16a61c4fc6b27b6b26aac17b">llvm::MemSDNode::getChain</a>, <a href="/web-llvm/docs/api/classes/llvm/sdvalue/#a2b08aa629a6326d1a0444ee6d477c39d">llvm::SDValue::getNode</a>, <a href="/web-llvm/docs/api/classes/llvm/selectiondag/#abad5b17501ce8972fb04a149611e7177">llvm::SelectionDAG::getNode</a>, <a href="/web-llvm/docs/api/classes/llvm/loadsdnode/#a71689ed396153740b31ac1a182364651">llvm::LoadSDNode::getOffset</a>, <a href="/web-llvm/docs/api/classes/llvm/storesdnode/#a51de544d610ce7e2c69bc1b34fbeb18e">llvm::StoreSDNode::getOffset</a>, <a href="/web-llvm/docs/api/classes/llvm/sdnode/#a8388f666d6e735f35837ad03ed1f7a7a">llvm::SDNode::getOperand</a>, <a href="/web-llvm/docs/api/classes/llvm/sdvalue/#ac476ca9c302b9ba8d47ea7b02f6149f5">llvm::SDValue::getResNo</a>, <a href="/web-llvm/docs/api/classes/llvm/sdnode/#ad82ad170343d0b4fe88a5551ec43659d">llvm::SDNode::hasNUsesOfValue</a>, <a href="/web-llvm/docs/api/classes/llvm/sdnode/#a7c6beebf86835d6582b0550cd7731ee9">llvm::SDNode::hasPredecessorHelper</a>, <a href="/web-llvm/docs/api/classes/llvm/memsdnode/#aba37cfe8576deaf53760781cffe425fe">llvm::MemSDNode::isNonTemporal</a>, <a href="/web-llvm/docs/api/namespaces/llvm/isd/#afaaeadcd82b42fc0d385a6247bf7bb52">llvm::ISD::isNormalLoad</a>, <a href="/web-llvm/docs/api/namespaces/llvm/isd/#a308088c2d65f8f3955f5fb0f6aca7ccc">llvm::ISD::isNormalStore</a>, <a href="/web-llvm/docs/api/classes/llvm/sdnode/#a0cdd5176dc41b96586448ecc59770250">llvm::SDNode::ops</a>, <a href="/web-llvm/docs/api/classes/llvm/smallvectortemplatebase/#af42bfbc067df27c19ee2fc859df58799">llvm::SmallVectorTemplateBase&lt; T, bool &gt;::push_back</a> and <a href="/web-llvm/docs/api/namespaces/llvm/isd/#a22ea9cec080dd5f4f47ba234c2f59110ad469508535ce2082a1ab1f0e429187b8">llvm::ISD::TokenFactor</a>.</p>

</div>
</div>

### isValidDisp() {#a585775891613ee08dcba83bd7c407162}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool isValidDisp (<a href="/web-llvm/docs/api/structs/anonymous-systemziseldagtodag-cpp-/systemzaddressingmode/#a0acf891b270d205d852a48b857c42987">SystemZAddressingMode::DispRange</a> DR, int64_t Val)</td>
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



<p>Definition at line 523 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/systemz/systemziseldagtodag-cpp">SystemZISelDAGToDAG.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/silowercontrolflow-cpp/#a4868c5d81c5ccc98c47aeab6244346a0">assert</a>, <a href="/web-llvm/docs/api/structs/anonymous-systemziseldagtodag-cpp-/systemzaddressingmode/#a0acf891b270d205d852a48b857c42987a47ed8d3fd4a1725cc46294ce9c6db90a">anonymous{SystemZISelDAGToDAG.cpp}::SystemZAddressingMode::Disp12Only</a>, <a href="/web-llvm/docs/api/structs/anonymous-systemziseldagtodag-cpp-/systemzaddressingmode/#a0acf891b270d205d852a48b857c42987a4a4e2c60e2bea977601e746cfb0144fe">anonymous{SystemZISelDAGToDAG.cpp}::SystemZAddressingMode::Disp12Pair</a>, <a href="/web-llvm/docs/api/structs/anonymous-systemziseldagtodag-cpp-/systemzaddressingmode/#a0acf891b270d205d852a48b857c42987a5e5fd31d017ba7df42c11b3d68a8a4af">anonymous{SystemZISelDAGToDAG.cpp}::SystemZAddressingMode::Disp20Only</a>, <a href="/web-llvm/docs/api/structs/anonymous-systemziseldagtodag-cpp-/systemzaddressingmode/#a0acf891b270d205d852a48b857c42987a34dc3b55235a2c79a0ba5c762f05c004">anonymous{SystemZISelDAGToDAG.cpp}::SystemZAddressingMode::Disp20Only128</a>, <a href="/web-llvm/docs/api/structs/anonymous-systemziseldagtodag-cpp-/systemzaddressingmode/#a0acf891b270d205d852a48b857c42987af37bf1237d492caabde564e81fc14d1b">anonymous{SystemZISelDAGToDAG.cpp}::SystemZAddressingMode::Disp20Pair</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a87e65296f2a6d9570117a852af342764">llvm::isUInt</a>, <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/support/errorhandling-h/#ace243f5c25697a1107cce46626b3dc94">llvm_unreachable</a> and <a href="#a2fa6af6bfd047fb63d886637fe12e498">selectDisp</a>.</p>

</div>
</div>

### maskMatters() {#a7cc7fca619b4ff2c891081311105af67}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool maskMatters (RxSBGOperands &amp; RxSBG, uint64_t Mask)</td>
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



<p>Definition at line 791 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/systemz/systemziseldagtodag-cpp">SystemZISelDAGToDAG.cpp</a>.</p>

</div>
</div>

### selectDisp() {#a2fa6af6bfd047fb63d886637fe12e498}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool selectDisp (<a href="/web-llvm/docs/api/structs/anonymous-systemziseldagtodag-cpp-/systemzaddressingmode/#a0acf891b270d205d852a48b857c42987">SystemZAddressingMode::DispRange</a> DR, int64_t Val)</td>
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



<p>Definition at line 411 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/systemz/systemziseldagtodag-cpp">SystemZISelDAGToDAG.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/structs/anonymous-systemziseldagtodag-cpp-/systemzaddressingmode/#a0acf891b270d205d852a48b857c42987a47ed8d3fd4a1725cc46294ce9c6db90a">anonymous{SystemZISelDAGToDAG.cpp}::SystemZAddressingMode::Disp12Only</a>, <a href="/web-llvm/docs/api/structs/anonymous-systemziseldagtodag-cpp-/systemzaddressingmode/#a0acf891b270d205d852a48b857c42987a4a4e2c60e2bea977601e746cfb0144fe">anonymous{SystemZISelDAGToDAG.cpp}::SystemZAddressingMode::Disp12Pair</a>, <a href="/web-llvm/docs/api/structs/anonymous-systemziseldagtodag-cpp-/systemzaddressingmode/#a0acf891b270d205d852a48b857c42987a5e5fd31d017ba7df42c11b3d68a8a4af">anonymous{SystemZISelDAGToDAG.cpp}::SystemZAddressingMode::Disp20Only</a>, <a href="/web-llvm/docs/api/structs/anonymous-systemziseldagtodag-cpp-/systemzaddressingmode/#a0acf891b270d205d852a48b857c42987a34dc3b55235a2c79a0ba5c762f05c004">anonymous{SystemZISelDAGToDAG.cpp}::SystemZAddressingMode::Disp20Only128</a>, <a href="/web-llvm/docs/api/structs/anonymous-systemziseldagtodag-cpp-/systemzaddressingmode/#a0acf891b270d205d852a48b857c42987af37bf1237d492caabde564e81fc14d1b">anonymous{SystemZISelDAGToDAG.cpp}::SystemZAddressingMode::Disp20Pair</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a1a1e51a5952c3afa00875df90e7ae6f8">llvm::isInt</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a87e65296f2a6d9570117a852af342764">llvm::isUInt</a> and <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/support/errorhandling-h/#ace243f5c25697a1107cce46626b3dc94">llvm_unreachable</a>.</p>


<p>Referenced by <a href="#a8054b3854a083e947e97f07f6a5fd396">expandDisp</a> and <a href="#a585775891613ee08dcba83bd7c407162">isValidDisp</a>.</p>

</div>
</div>

### shouldUseLA() {#ab40a430aafd22186cbdbd94ec923b02b}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool shouldUseLA (<a href="/web-llvm/docs/api/classes/llvm/sdnode">SDNode</a> * Base, int64_t Disp, <a href="/web-llvm/docs/api/classes/llvm/sdnode">SDNode</a> * Index)</td>
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



<p>Definition at line 543 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/systemz/systemziseldagtodag-cpp">SystemZISelDAGToDAG.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/namespaces/llvm/sampleprof/#a702f69807459cc25db5754a5f179d3fcaf6fbeb8fa9f451468611536b00878d41">llvm::sampleprof::Base</a>, <a href="/web-llvm/docs/api/namespaces/llvm/isd/#a22ea9cec080dd5f4f47ba234c2f59110a4b437632fd9b97dd36010d85eb363efe">llvm::ISD::FrameIndex</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a1a1e51a5952c3afa00875df90e7ae6f8">llvm::isInt</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a87e65296f2a6d9570117a852af342764">llvm::isUInt</a>, <a href="/web-llvm/docs/api/namespaces/llvm/isd/#a22ea9cec080dd5f4f47ba234c2f59110a5183f3d72924bc7c77ba8d3f5de9f602">llvm::ISD::SIGN_EXTEND</a> and <a href="/web-llvm/docs/api/namespaces/llvm/isd/#a22ea9cec080dd5f4f47ba234c2f59110aaa59dd5ec37f21905436b354c0292d9e">llvm::ISD::SIGN_EXTEND_INREG</a>.</p>

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
<td class="doxyMemberName">#define DEBUG_TYPE&nbsp;&nbsp;&nbsp;"systemz-isel"</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 23 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/systemz/systemziseldagtodag-cpp">SystemZISelDAGToDAG.cpp</a>.</p>

</div>
</div>

### PASS\_NAME {#acf9235cddac26ff3f81e8c56849bcaac}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">#define PASS_NAME&nbsp;&nbsp;&nbsp;"SystemZ DAG-&gt;DAG <a href="/web-llvm/docs/api/classes/llvm/pattern">Pattern</a> <a href="/web-llvm/docs/api/classes/llvm/instruction">Instruction</a> Selection"</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 24 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/systemz/systemziseldagtodag-cpp">SystemZISelDAGToDAG.cpp</a>.</p>

</div>
</div>

</div>

<hr/>

<p class="doxyGeneratedBy">Generated via <a href="https://xpack.github.io/doxygen2docusaurus">doxygen2docusaurus</a> 2.0.0 by <a href="https://www.doxygen.nl">Doxygen</a> 1.15.0.</p>

</div>
