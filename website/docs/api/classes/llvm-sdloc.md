---

# DO NOT EDIT!
# Automatically generated via doxygen2docusaurus by Doxygen.

slug: /api/classes/llvm/sdloc
custom_edit_url: null
toc_max_heading_level: 4
keywords:
  - doxygen
  - reference
  - class

---

<div class="doxyPage">

# `SDLoc` Class

<p>Wrapper class for IR location info (IR ordering and <a href="/web-llvm/docs/api/classes/llvm/debugloc">DebugLoc</a>) to be passed into <a href="/web-llvm/docs/api/classes/llvm/sdnode">SDNode</a> creation functions. <a href="#details">More...</a></p>

## Declaration

<div class="doxyDeclaration">
class llvm::SDLoc { ... }
</div>

## Included Headers

<div class="doxyIncludesList">#include "<a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/codegen/selectiondagnodes-h">llvm/CodeGen/SelectionDAGNodes.h</a>"
</div>

## Public Constructors Index

<table class="doxyMembersIndex">

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a7bda78db91f3b9a955338f08258ec630">SDLoc</a> ()=default</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ab547baa9b958a27de005b90f74c5ffda">SDLoc</a> (const SDNode *N)</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a535048fa70ac1c49d6a6d8a23e92f25a">SDLoc</a> (const SDValue V)</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#af51eb66f94729c8f983431082ca475fe">SDLoc</a> (const Instruction *I, int Order)</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">unsigned</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a37934a8cf612bfc68a163352faf23e2b">getIROrder</a> () const</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/debugloc">DebugLoc</a> &amp;</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a2f7e1a05a6d21e25bcc3c5ea275b252b">getDebugLoc</a> () const</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/debugloc">DebugLoc</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ae0f70b0eee7f25a30e8f1e31476f9cc9">DL</a></td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ae8f9b51332372e0c45022d6c4c0d4938">IROrder</a> = 0</td>
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

<p>Wrapper class for IR location info (IR ordering and <a href="/web-llvm/docs/api/classes/llvm/debugloc">DebugLoc</a>) to be passed into <a href="/web-llvm/docs/api/classes/llvm/sdnode">SDNode</a> creation functions.</p>


<p>When an <a href="/web-llvm/docs/api/classes/llvm/sdnode">SDNode</a> is created from the DAGBuilder, the <a href="/web-llvm/docs/api/classes/llvm/debugloc">DebugLoc</a> is extracted from the original <a href="/web-llvm/docs/api/classes/llvm/instruction">Instruction</a>, and IROrder is the ordinal position of the instruction. When an <a href="/web-llvm/docs/api/classes/llvm/sdnode">SDNode</a> is created after the DAG is being built, both <a href="/web-llvm/docs/api/classes/llvm/debugloc">DebugLoc</a> and the IROrder are propagated from the original <a href="/web-llvm/docs/api/classes/llvm/sdnode">SDNode</a>. So <a href="/web-llvm/docs/api/classes/llvm/sdloc">SDLoc</a> class provides two constructors besides the default one, one to be used by the DAGBuilder, the other to be used by others.</p>


<p>Definition at line 1182 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/codegen/selectiondagnodes-h">SelectionDAGNodes.h</a>.</p>


<div class="doxySectionDef">

## Public Constructors

### SDLoc() {#a7bda78db91f3b9a955338f08258ec630}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">llvm::SDLoc::SDLoc ()</td>
</tr>
</table>
</td>
<td class="doxyMemberLabelsRight">
<span class="doxyMemberLabels">
<span class="doxyMemberLabel default">default</span>
</span>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 1188 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/codegen/selectiondagnodes-h">SelectionDAGNodes.h</a>.</p>


<p>Referenced by <a href="#a535048fa70ac1c49d6a6d8a23e92f25a">SDLoc</a>.</p>

</div>
</div>

### SDLoc() {#ab547baa9b958a27de005b90f74c5ffda}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">llvm::SDLoc::SDLoc (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/sdnode">SDNode</a> * N)</td>
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



<p>Definition at line 1189 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/codegen/selectiondagnodes-h">SelectionDAGNodes.h</a>.</p>


<p>References <a href="#a2f7e1a05a6d21e25bcc3c5ea275b252b">getDebugLoc</a>, <a href="#a37934a8cf612bfc68a163352faf23e2b">getIROrder</a> and <a href="/web-llvm/docs/api/files/lib/lib/support/regcomp-c/#a0240ac851181b84ac374872dc5434ee4">N</a>.</p>

</div>
</div>

### SDLoc() {#a535048fa70ac1c49d6a6d8a23e92f25a}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">llvm::SDLoc::SDLoc (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/sdvalue">SDValue</a> V)</td>
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



<p>Definition at line 1190 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/codegen/selectiondagnodes-h">SelectionDAGNodes.h</a>.</p>


<p>References <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/lib/target/amdgpu/utils/amdgpudelayedmcexpr-cpp/#a3b9e43a5529fa7d4adb2bad70198c9bd">getNode</a> and <a href="#a7bda78db91f3b9a955338f08258ec630">SDLoc</a>.</p>

</div>
</div>

### SDLoc() {#af51eb66f94729c8f983431082ca475fe}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">llvm::SDLoc::SDLoc (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/instruction">Instruction</a> * I, int Order)</td>
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



<p>Definition at line 1191 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/codegen/selectiondagnodes-h">SelectionDAGNodes.h</a>.</p>


<p>References <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/silowercontrolflow-cpp/#a4868c5d81c5ccc98c47aeab6244346a0">assert</a> and <a href="/web-llvm/docs/api/files/lib/lib/support/md5-cpp/#ac0eafdc9ee161b71e7af98af736952fd">I</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Public Member Functions

### getDebugLoc() {#a2f7e1a05a6d21e25bcc3c5ea275b252b}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">const DebugLoc &amp; llvm::SDLoc::getDebugLoc ()</td>
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



<p>Definition at line 1198 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/codegen/selectiondagnodes-h">SelectionDAGNodes.h</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/x86/x86iselloweringcall-cpp/#a9df9cc3269d03373740e69dcb005d729">errorUnsupported</a>, <a href="/web-llvm/docs/api/classes/llvm/selectiondag/#a0ebd1bad63f0443b8329ac6a0c2a0ea6">llvm::SelectionDAG::getAddrSpaceCast</a>, <a href="/web-llvm/docs/api/classes/llvm/selectiondag/#a1a1f2f01c1eb849390f448f90643c6ff">llvm::SelectionDAG::getAtomic</a>, <a href="/web-llvm/docs/api/classes/llvm/selectiondag/#a5bd5e426c197fd66ec0ac6f088d51185">llvm::SelectionDAG::getGatherVP</a>, <a href="/web-llvm/docs/api/classes/llvm/selectiondag/#a3af6334751e0a4eaf2b2a253f545a861">llvm::SelectionDAG::getGetFPEnv</a>, <a href="/web-llvm/docs/api/classes/llvm/selectiondag/#aa4f17f756eb1cb25b572523363d9ddce">llvm::SelectionDAG::getIndexedStore</a>, <a href="/web-llvm/docs/api/classes/llvm/selectiondag/#aa34a22977f06d68f99eabea788b8d4fa">llvm::SelectionDAG::getIndexedStoreVP</a>, <a href="/web-llvm/docs/api/classes/llvm/selectiondag/#a099ce58f978968532bb5de54ed2a4a8b">llvm::SelectionDAG::getLabelNode</a>, <a href="/web-llvm/docs/api/classes/llvm/selectiondag/#ad4283d9a650f42aafcff8b6cefc332a2">llvm::SelectionDAG::getLifetimeNode</a>, <a href="/web-llvm/docs/api/classes/llvm/selectiondag/#ab280576b46181ebb3a3716370169c287">llvm::SelectionDAG::getLoad</a>, <a href="/web-llvm/docs/api/classes/llvm/selectiondag/#ab517db4292565daf5cea12e127f9db87">llvm::SelectionDAG::getLoadVP</a>, <a href="/web-llvm/docs/api/classes/llvm/selectiondag/#a0bc0f0450beae61b3c7c3f110d3b7c5c">llvm::SelectionDAG::getMaskedGather</a>, <a href="/web-llvm/docs/api/classes/llvm/selectiondag/#a77eef56a45fec10f706e25be688f3beb">llvm::SelectionDAG::getMaskedHistogram</a>, <a href="/web-llvm/docs/api/classes/llvm/selectiondag/#af2a48350a921ca25a0939a82228555f4">llvm::SelectionDAG::getMaskedLoad</a>, <a href="/web-llvm/docs/api/classes/llvm/selectiondag/#aff2202a13bbfad20f9b5156fd930cf01">llvm::SelectionDAG::getMaskedScatter</a>, <a href="/web-llvm/docs/api/classes/llvm/selectiondag/#aa83e0455dcd3f0feb08e08ebb0a18db0">llvm::SelectionDAG::getMaskedStore</a>, <a href="/web-llvm/docs/api/classes/llvm/selectiondag/#a6fc57a7458164a2086dfee32a82530db">llvm::SelectionDAG::getMemIntrinsicNode</a>, <a href="/web-llvm/docs/api/classes/llvm/selectiondag/#a1e99e576dd285dc69aa7ae6de70c05b1">llvm::SelectionDAG::getPseudoProbeNode</a>, <a href="/web-llvm/docs/api/classes/llvm/selectiondag/#ab8b2b591dc9b054d04368b7d069fb76c">llvm::SelectionDAG::getScatterVP</a>, <a href="/web-llvm/docs/api/classes/llvm/selectiondag/#aa7cfce69eeecdf585f55b39efbdff6ba">llvm::SelectionDAG::getSetFPEnv</a>, <a href="/web-llvm/docs/api/classes/llvm/selectiondag/#a211f6d3863ce35b5a5893032fe0449cc">llvm::SelectionDAG::getStore</a>, <a href="/web-llvm/docs/api/classes/llvm/selectiondag/#a7bebd21fcb08b6b7288fee3de1246c52">llvm::SelectionDAG::getStoreVP</a>, <a href="/web-llvm/docs/api/classes/llvm/selectiondag/#a8c2603648fb228b097b421cfd6c577e2">llvm::SelectionDAG::getTruncStore</a>, <a href="/web-llvm/docs/api/classes/llvm/selectiondag/#a2b70646a1a7d39196c9e405e6e765b98">llvm::SelectionDAG::getTruncStoreVP</a>, <a href="/web-llvm/docs/api/classes/llvm/selectiondag/#afa7e233051b9ed8ebc0191f42698cb14">llvm::SelectionDAG::getVectorShuffle</a>, <a href="/web-llvm/docs/api/classes/llvm/amdgputargetlowering/#a2b01b00892f78bc1a75f271e3b9042f5">llvm::AMDGPUTargetLowering::lowerUnhandledCall</a> and <a href="#ab547baa9b958a27de005b90f74c5ffda">SDLoc</a>.</p>

</div>
</div>

### getIROrder() {#a37934a8cf612bfc68a163352faf23e2b}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">unsigned llvm::SDLoc::getIROrder ()</td>
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



<p>Definition at line 1197 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/codegen/selectiondagnodes-h">SelectionDAGNodes.h</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/classes/llvm/selectiondag/#a0ebd1bad63f0443b8329ac6a0c2a0ea6">llvm::SelectionDAG::getAddrSpaceCast</a>, <a href="/web-llvm/docs/api/classes/llvm/selectiondag/#a1a1f2f01c1eb849390f448f90643c6ff">llvm::SelectionDAG::getAtomic</a>, <a href="/web-llvm/docs/api/classes/llvm/selectiondag/#a5bd5e426c197fd66ec0ac6f088d51185">llvm::SelectionDAG::getGatherVP</a>, <a href="/web-llvm/docs/api/classes/llvm/selectiondag/#a3af6334751e0a4eaf2b2a253f545a861">llvm::SelectionDAG::getGetFPEnv</a>, <a href="/web-llvm/docs/api/classes/llvm/selectiondag/#aa4f17f756eb1cb25b572523363d9ddce">llvm::SelectionDAG::getIndexedStore</a>, <a href="/web-llvm/docs/api/classes/llvm/selectiondag/#aa34a22977f06d68f99eabea788b8d4fa">llvm::SelectionDAG::getIndexedStoreVP</a>, <a href="/web-llvm/docs/api/classes/llvm/selectiondag/#a099ce58f978968532bb5de54ed2a4a8b">llvm::SelectionDAG::getLabelNode</a>, <a href="/web-llvm/docs/api/classes/llvm/selectiondag/#ad4283d9a650f42aafcff8b6cefc332a2">llvm::SelectionDAG::getLifetimeNode</a>, <a href="/web-llvm/docs/api/classes/llvm/selectiondag/#ab280576b46181ebb3a3716370169c287">llvm::SelectionDAG::getLoad</a>, <a href="/web-llvm/docs/api/classes/llvm/selectiondag/#ab517db4292565daf5cea12e127f9db87">llvm::SelectionDAG::getLoadVP</a>, <a href="/web-llvm/docs/api/classes/llvm/selectiondag/#a0bc0f0450beae61b3c7c3f110d3b7c5c">llvm::SelectionDAG::getMaskedGather</a>, <a href="/web-llvm/docs/api/classes/llvm/selectiondag/#a77eef56a45fec10f706e25be688f3beb">llvm::SelectionDAG::getMaskedHistogram</a>, <a href="/web-llvm/docs/api/classes/llvm/selectiondag/#af2a48350a921ca25a0939a82228555f4">llvm::SelectionDAG::getMaskedLoad</a>, <a href="/web-llvm/docs/api/classes/llvm/selectiondag/#aff2202a13bbfad20f9b5156fd930cf01">llvm::SelectionDAG::getMaskedScatter</a>, <a href="/web-llvm/docs/api/classes/llvm/selectiondag/#aa83e0455dcd3f0feb08e08ebb0a18db0">llvm::SelectionDAG::getMaskedStore</a>, <a href="/web-llvm/docs/api/classes/llvm/selectiondag/#a6fc57a7458164a2086dfee32a82530db">llvm::SelectionDAG::getMemIntrinsicNode</a>, <a href="/web-llvm/docs/api/classes/llvm/selectiondag/#a1e99e576dd285dc69aa7ae6de70c05b1">llvm::SelectionDAG::getPseudoProbeNode</a>, <a href="/web-llvm/docs/api/classes/llvm/selectiondag/#ab8b2b591dc9b054d04368b7d069fb76c">llvm::SelectionDAG::getScatterVP</a>, <a href="/web-llvm/docs/api/classes/llvm/selectiondag/#aa7cfce69eeecdf585f55b39efbdff6ba">llvm::SelectionDAG::getSetFPEnv</a>, <a href="/web-llvm/docs/api/classes/llvm/selectiondag/#a211f6d3863ce35b5a5893032fe0449cc">llvm::SelectionDAG::getStore</a>, <a href="/web-llvm/docs/api/classes/llvm/selectiondag/#a7bebd21fcb08b6b7288fee3de1246c52">llvm::SelectionDAG::getStoreVP</a>, <a href="/web-llvm/docs/api/classes/llvm/selectiondag/#a8c2603648fb228b097b421cfd6c577e2">llvm::SelectionDAG::getTruncStore</a>, <a href="/web-llvm/docs/api/classes/llvm/selectiondag/#a2b70646a1a7d39196c9e405e6e765b98">llvm::SelectionDAG::getTruncStoreVP</a>, <a href="/web-llvm/docs/api/classes/llvm/selectiondag/#afa7e233051b9ed8ebc0191f42698cb14">llvm::SelectionDAG::getVectorShuffle</a> and <a href="#ab547baa9b958a27de005b90f74c5ffda">SDLoc</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Private Member Attributes

### DL {#ae0f70b0eee7f25a30e8f1e31476f9cc9}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">DebugLoc llvm::SDLoc::DL</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 1184 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/codegen/selectiondagnodes-h">SelectionDAGNodes.h</a>.</p>

</div>
</div>

### IROrder {#ae8f9b51332372e0c45022d6c4c0d4938}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">int llvm::SDLoc::IROrder = 0</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 1185 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/codegen/selectiondagnodes-h">SelectionDAGNodes.h</a>.</p>

</div>
</div>

</div>

<hr/>

The documentation for this class was generated from the following file:

<ul>
<li><a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/codegen/selectiondagnodes-h">SelectionDAGNodes.h</a></li>
</ul>

<hr/>

<p class="doxyGeneratedBy">Generated via <a href="https://github.com/xpack/doxygen2docusaurus">doxygen2docusaurus</a> by <a href="https://www.doxygen.nl">Doxygen</a> 1.15.0.</p>

</div>
