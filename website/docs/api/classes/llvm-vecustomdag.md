---

# DO NOT EDIT!
# Automatically generated via doxygen2docusaurus by Doxygen.

slug: /api/classes/llvm/vecustomdag
custom_edit_url: null
toc_max_heading_level: 4
keywords:
  - doxygen
  - reference
  - class

---

<div class="doxyPage">

# `VECustomDAG` Class



## Declaration

<div class="doxyDeclaration">
class llvm::VECustomDAG { ... }
</div>

## Included Headers

<div class="doxyIncludesList">#include "<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/ve/vecustomdag-h">Target/VE/VECustomDAG.h</a>"
</div>

## Public Constructors Index

<table class="doxyMembersIndex">

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a4e7da125d660f42ac931e4bdd4031393">VECustomDAG</a> (SelectionDAG &amp;DAG, SDLoc DL)</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a262f8afb6282cb142427c78c028fcd8d">VECustomDAG</a> (SelectionDAG &amp;DAG, SDValue WhereOp)</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a709b4f84b841c9e1b875b592b8343a1b">VECustomDAG</a> (SelectionDAG &amp;DAG, const SDNode *WhereN)</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/selectiondag">SelectionDAG</a> *</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a9882ec513cb04a263c4cbce0f8529ecd">getDAG</a> () const</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a6bc77ff0f140f382784b468fb1b8f65e">getNode</a> (unsigned OC, SDVTList VTL, ArrayRef&lt; SDValue &gt; OpV, std::optional&lt; SDNodeFlags &gt; Flags=std::nullopt) const</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>getNode { <a href="#a6bc77ff0f140f382784b468fb1b8f65e">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/sdvalue">SDValue</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a24f2724c3180118c51af9b3fe77328f2">getNode</a> (unsigned OC, ArrayRef&lt; EVT &gt; ResVT, ArrayRef&lt; SDValue &gt; OpV, std::optional&lt; SDNodeFlags &gt; Flags=std::nullopt) const</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#afd07a519f6f716dfb3649c99c3bf8fc2">getNode</a> (unsigned OC, EVT ResVT, ArrayRef&lt; SDValue &gt; OpV, std::optional&lt; SDNodeFlags &gt; Flags=std::nullopt) const</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a8b43494409db5f4c462bb8dcd4a10379">getUNDEF</a> (EVT VT) const</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a5dcd3bf98753b88499149fbe53d4f913">getLegalReductionOpVVP</a> (unsigned VVPOpcode, EVT ResVT, SDValue StartV, SDValue VectorV, SDValue Mask, SDValue AVL, SDNodeFlags Flags) const</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>} getNode <a href="#a5dcd3bf98753b88499149fbe53d4f913">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/sdvalue">SDValue</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a871da559dbbc4dd972b1fd4308fdacef">getUnpack</a> (EVT DestVT, SDValue Vec, PackElem Part, SDValue AVL) const</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>} Legalizing getNode <a href="#a871da559dbbc4dd972b1fd4308fdacef">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/sdvalue">SDValue</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#aac3d4c9bf1c3f241d05e2b6ff1da908c">getPack</a> (EVT DestVT, SDValue LoVec, SDValue HiVec, SDValue AVL) const</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a2a7d147364709982a559ec4186fa5d1e">getMergeValues</a> (ArrayRef&lt; SDValue &gt; Values) const</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>} <a href="/web-llvm/docs/api/namespaces/llvm/#a6405223942a3a52775bb99d512dca2ad">Packing</a> <a href="#a2a7d147364709982a559ec4186fa5d1e">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/sdvalue">SDValue</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#adb789b9db13d7d57909fe893bf5b8ec7">getConstant</a> (uint64_t Val, EVT VT, bool IsTarget=false, bool IsOpaque=false) const</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a4d94a477b234a43ddcf817c49c59d575">getConstantMask</a> (Packing Packing, bool AllTrue) const</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a5cbffc44ad31b145185f0cf56289c7d3">getMaskBroadcast</a> (EVT ResultVT, SDValue Scalar, SDValue AVL) const</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a33828d2d1154bc3142d35300e0460959">getBroadcast</a> (EVT ResultVT, SDValue Scalar, SDValue AVL) const</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a7f0d42ec138cbda5ad9f106de9c63c7c">annotateLegalAVL</a> (SDValue AVL) const</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/structs/llvm/vetargetmasks">VETargetMasks</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ae417bd7b6316086f84e03b50c2bf8915">getTargetSplitMask</a> (SDValue RawMask, SDValue RawAVL, PackElem Part) const</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a05fa62cfcf9c4e5947236b7c8631c772">getSplitPtrOffset</a> (SDValue Ptr, SDValue ByteStride, PackElem Part) const</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#adb85958a25173ec157b8244230f8d83f">getSplitPtrStride</a> (SDValue PackStride) const</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a51a84e2a653d37da834d4e3f7eb662c8">getGatherScatterAddress</a> (SDValue BasePtr, SDValue Scale, SDValue Index, SDValue Mask, SDValue AVL) const</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/structs/llvm/evt">EVT</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ada28169376dccd18b7bf89215c83adc5">getVectorVT</a> (EVT ElemVT, unsigned NumElems) const</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a296bd0523713054145b12423233db6ef">DAG</a></td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/sdloc">SDLoc</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ab84813bb43cd974380e91af99129d7d9">DL</a></td>
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


<p>Definition at line 142 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/ve/vecustomdag-h">VECustomDAG.h</a>.</p>


<div class="doxySectionDef">

## Public Constructors

### VECustomDAG() {#a4e7da125d660f42ac931e4bdd4031393}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">llvm::VECustomDAG::VECustomDAG (<a href="/web-llvm/docs/api/classes/llvm/selectiondag">SelectionDAG</a> &amp; DAG, <a href="/web-llvm/docs/api/classes/llvm/sdloc">SDLoc</a> DL)</td>
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



<p>Definition at line 149 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/ve/vecustomdag-h">VECustomDAG.h</a>.</p>

</div>
</div>

### VECustomDAG() {#a262f8afb6282cb142427c78c028fcd8d}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">llvm::VECustomDAG::VECustomDAG (<a href="/web-llvm/docs/api/classes/llvm/selectiondag">SelectionDAG</a> &amp; DAG, <a href="/web-llvm/docs/api/classes/llvm/sdvalue">SDValue</a> WhereOp)</td>
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



<p>Definition at line 151 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/ve/vecustomdag-h">VECustomDAG.h</a>.</p>

</div>
</div>

### VECustomDAG() {#a709b4f84b841c9e1b875b592b8343a1b}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">llvm::VECustomDAG::VECustomDAG (<a href="/web-llvm/docs/api/classes/llvm/selectiondag">SelectionDAG</a> &amp; DAG, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/sdnode">SDNode</a> * WhereN)</td>
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



<p>Definition at line 153 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/ve/vecustomdag-h">VECustomDAG.h</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Public Member Functions

### annotateLegalAVL() {#a7f0d42ec138cbda5ad9f106de9c63c7c}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">SDValue llvm::VECustomDAG::annotateLegalAVL (<a href="/web-llvm/docs/api/classes/llvm/sdvalue">SDValue</a> AVL)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Declaration at line 206 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/ve/vecustomdag-h">VECustomDAG.h</a>, definition at line 474 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/ve/vecustomdag-cpp">VECustomDAG.cpp</a>.</p>


<p>References <a href="#a6bc77ff0f140f382784b468fb1b8f65e">getNode</a>, <a href="/web-llvm/docs/api/classes/llvm/sdvalue/#a6b2b8ca5b0fdf6484247d5ae74deb9ff">llvm::SDValue::getValueType</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a84e306a52da2372d1d398fb5a3c75c81">llvm::isLegalAVL</a> and <a href="/web-llvm/docs/api/namespaces/llvm/veisd/#a49f380eab7f36fdf783b97376cf8065eacac7b6d14e0495f8ca948adab88191cf">llvm::VEISD::LEGALAVL</a>.</p>


<p>Referenced by <a href="#ae417bd7b6316086f84e03b50c2bf8915">getTargetSplitMask</a> and <a href="/web-llvm/docs/api/classes/llvm/vetargetlowering/#a5b511edb819f787e3913f2c3bd6bab00">llvm::VETargetLowering::legalizePackedAVL</a>.</p>

</div>
</div>

### getBroadcast() {#a33828d2d1154bc3142d35300e0460959}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">SDValue llvm::VECustomDAG::getBroadcast (<a href="/web-llvm/docs/api/structs/llvm/evt">EVT</a> ResultVT, <a href="/web-llvm/docs/api/classes/llvm/sdvalue">SDValue</a> Scalar, <a href="/web-llvm/docs/api/classes/llvm/sdvalue">SDValue</a> AVL)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Declaration at line 203 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/ve/vecustomdag-h">VECustomDAG.h</a>, definition at line 451 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/ve/vecustomdag-cpp">VECustomDAG.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/silowercontrolflow-cpp/#a4868c5d81c5ccc98c47aeab6244346a0">assert</a>, <a href="#a5cbffc44ad31b145185f0cf56289c7d3">getMaskBroadcast</a>, <a href="#a6bc77ff0f140f382784b468fb1b8f65e">getNode</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a7c242ac8227e53a677e25cac39aaad82">llvm::isMaskType</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a0346da3fb8d131cf057b3f5c1757400b">llvm::isPackedVectorType</a>, <a href="/web-llvm/docs/api/structs/llvm/evt/#aa54976197fff266f4143beb44fc9764c">llvm::EVT::isVector</a>, <a href="/web-llvm/docs/api/namespaces/llvm/veisd/#a49f380eab7f36fdf783b97376cf8065ea284dc8f7016c3d93c4a1dc5b1a2c7803">llvm::VEISD::REPL_F32</a>, <a href="/web-llvm/docs/api/namespaces/llvm/veisd/#a49f380eab7f36fdf783b97376cf8065ea2f01ed5327e84e9058da4c5bad91fe44">llvm::VEISD::REPL_I32</a> and <a href="/web-llvm/docs/api/namespaces/llvm/veisd/#a49f380eab7f36fdf783b97376cf8065eaff28a96ed40cf064a55fd76a6aa58989">llvm::VEISD::VEC_BROADCAST</a>.</p>


<p>Referenced by <a href="#a51a84e2a653d37da834d4e3f7eb662c8">getGatherScatterAddress</a>, <a href="#a5cbffc44ad31b145185f0cf56289c7d3">getMaskBroadcast</a> and <a href="/web-llvm/docs/api/classes/llvm/vetargetlowering/#aaf4437cbbdf47747d1297e4e66c977cc">llvm::VETargetLowering::lowerBUILD_VECTOR</a>.</p>

</div>
</div>

### getConstant() {#adb789b9db13d7d57909fe893bf5b8ec7}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">SDValue llvm::VECustomDAG::getConstant (uint64_t Val, <a href="/web-llvm/docs/api/structs/llvm/evt">EVT</a> VT, bool IsTarget=false, bool IsOpaque=false)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Declaration at line 198 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/ve/vecustomdag-h">VECustomDAG.h</a>, definition at line 404 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/ve/vecustomdag-cpp">VECustomDAG.cpp</a>.</p>


<p>Referenced by <a href="#a4d94a477b234a43ddcf817c49c59d575">getConstantMask</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#aedd8585aefa5e46401807f2f581d42c3">llvm::getLoadStoreStride</a>, <a href="#adb85958a25173ec157b8244230f8d83f">getSplitPtrStride</a>, <a href="#ae417bd7b6316086f84e03b50c2bf8915">getTargetSplitMask</a>, <a href="/web-llvm/docs/api/classes/llvm/vetargetlowering/#a5b511edb819f787e3913f2c3bd6bab00">llvm::VETargetLowering::legalizePackedAVL</a>, <a href="/web-llvm/docs/api/classes/llvm/vetargetlowering/#aaf4437cbbdf47747d1297e4e66c977cc">llvm::VETargetLowering::lowerBUILD_VECTOR</a>, <a href="/web-llvm/docs/api/classes/llvm/vetargetlowering/#a144a947122d0dd71ef58276fef8dfbb3">llvm::VETargetLowering::lowerToVVP</a>, <a href="/web-llvm/docs/api/classes/llvm/vetargetlowering/#a087a79677b0a36af63d2122ea6e1ee29">llvm::VETargetLowering::lowerVVP_GATHER_SCATTER</a>, <a href="/web-llvm/docs/api/classes/llvm/vetargetlowering/#a2f8e0ad32ef05ffb3966db924f5ae9ee">llvm::VETargetLowering::lowerVVP_LOAD_STORE</a> and <a href="/web-llvm/docs/api/classes/llvm/vetargetlowering/#a01ecd83dddd47ee7cb952356a66f776c">llvm::VETargetLowering::splitMaskArithmetic</a>.</p>

</div>
</div>

### getConstantMask() {#a4d94a477b234a43ddcf817c49c59d575}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">SDValue llvm::VECustomDAG::getConstantMask (<a href="/web-llvm/docs/api/namespaces/llvm/#a6405223942a3a52775bb99d512dca2ad">Packing</a> Packing, bool AllTrue)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Declaration at line 201 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/ve/vecustomdag-h">VECustomDAG.h</a>, definition at line 409 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/ve/vecustomdag-cpp">VECustomDAG.cpp</a>.</p>


<p>References <a href="#adb789b9db13d7d57909fe893bf5b8ec7">getConstant</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#aaea80b81575ab69196851372b8c5bc2a">llvm::getLegalVectorType</a>, <a href="#a6bc77ff0f140f382784b468fb1b8f65e">getNode</a> and <a href="/web-llvm/docs/api/namespaces/llvm/veisd/#a49f380eab7f36fdf783b97376cf8065eaff28a96ed40cf064a55fd76a6aa58989">llvm::VEISD::VEC_BROADCAST</a>.</p>


<p>Referenced by <a href="#a5cbffc44ad31b145185f0cf56289c7d3">getMaskBroadcast</a>, <a href="#ae417bd7b6316086f84e03b50c2bf8915">getTargetSplitMask</a>, <a href="/web-llvm/docs/api/classes/llvm/vetargetlowering/#a144a947122d0dd71ef58276fef8dfbb3">llvm::VETargetLowering::lowerToVVP</a>, <a href="/web-llvm/docs/api/classes/llvm/vetargetlowering/#a087a79677b0a36af63d2122ea6e1ee29">llvm::VETargetLowering::lowerVVP_GATHER_SCATTER</a> and <a href="/web-llvm/docs/api/classes/llvm/vetargetlowering/#a2f8e0ad32ef05ffb3966db924f5ae9ee">llvm::VETargetLowering::lowerVVP_LOAD_STORE</a>.</p>

</div>
</div>

### getDAG() {#a9882ec513cb04a263c4cbce0f8529ecd}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">SelectionDAG * llvm::VECustomDAG::getDAG ()</td>
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



<p>Definition at line 147 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/ve/vecustomdag-h">VECustomDAG.h</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/classes/llvm/vetargetlowering/#a2f8e0ad32ef05ffb3966db924f5ae9ee">llvm::VETargetLowering::lowerVVP_LOAD_STORE</a>.</p>

</div>
</div>

### getGatherScatterAddress() {#a51a84e2a653d37da834d4e3f7eb662c8}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">SDValue llvm::VECustomDAG::getGatherScatterAddress (<a href="/web-llvm/docs/api/classes/llvm/sdvalue">SDValue</a> BasePtr, <a href="/web-llvm/docs/api/classes/llvm/sdvalue">SDValue</a> Scale, <a href="/web-llvm/docs/api/classes/llvm/sdvalue">SDValue</a> Index, <a href="/web-llvm/docs/api/classes/llvm/sdvalue">SDValue</a> Mask, <a href="/web-llvm/docs/api/classes/llvm/sdvalue">SDValue</a> AVL)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Declaration at line 214 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/ve/vecustomdag-h">VECustomDAG.h</a>, definition at line 536 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/ve/vecustomdag-cpp">VECustomDAG.cpp</a>.</p>


<p>References <a href="#a33828d2d1154bc3142d35300e0460959">getBroadcast</a>, <a href="#a6bc77ff0f140f382784b468fb1b8f65e">getNode</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a1a86775f3d85d98a31b2751e1eb348ea">llvm::isNullConstant</a> and <a href="/web-llvm/docs/api/namespaces/llvm/#ac926ae0b6871c2207db3e787f6dbcb80">llvm::isOneConstant</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/classes/llvm/vetargetlowering/#a087a79677b0a36af63d2122ea6e1ee29">llvm::VETargetLowering::lowerVVP_GATHER_SCATTER</a>.</p>

</div>
</div>

### getLegalReductionOpVVP() {#a5dcd3bf98753b88499149fbe53d4f913}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">SDValue llvm::VECustomDAG::getLegalReductionOpVVP (unsigned VVPOpcode, <a href="/web-llvm/docs/api/structs/llvm/evt">EVT</a> ResVT, <a href="/web-llvm/docs/api/classes/llvm/sdvalue">SDValue</a> StartV, <a href="/web-llvm/docs/api/classes/llvm/sdvalue">SDValue</a> VectorV, <a href="/web-llvm/docs/api/classes/llvm/sdvalue">SDValue</a> Mask, <a href="/web-llvm/docs/api/classes/llvm/sdvalue">SDValue</a> AVL, <a href="/web-llvm/docs/api/structs/llvm/sdnodeflags">SDNodeFlags</a> Flags)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>} getNode</p>


<p>Legalizing getNode {</p>


<p>Declaration at line 184 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/ve/vecustomdag-h">VECustomDAG.h</a>, definition at line 562 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/ve/vecustomdag-cpp">VECustomDAG.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/silowercontrolflow-cpp/#a4868c5d81c5ccc98c47aeab6244346a0">assert</a>, <a href="#a6bc77ff0f140f382784b468fb1b8f65e">getNode</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#ad49951af9f5b144c4a9b80041ca3a630">llvm::getScalarReductionOpcode</a>, <a href="/web-llvm/docs/api/classes/llvm/sdvalue/#a6b2b8ca5b0fdf6484247d5ae74deb9ff">llvm::SDValue::getValueType</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#ac9aa93c5c44060d8bb0620dca40fd2cc">llvm::hasReductionStartParam</a> and <a href="/web-llvm/docs/api/namespaces/llvm/#a7c242ac8227e53a677e25cac39aaad82">llvm::isMaskType</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/classes/llvm/vetargetlowering/#a144a947122d0dd71ef58276fef8dfbb3">llvm::VETargetLowering::lowerToVVP</a>.</p>

</div>
</div>

### getMaskBroadcast() {#a5cbffc44ad31b145185f0cf56289c7d3}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">SDValue llvm::VECustomDAG::getMaskBroadcast (<a href="/web-llvm/docs/api/structs/llvm/evt">EVT</a> ResultVT, <a href="/web-llvm/docs/api/classes/llvm/sdvalue">SDValue</a> Scalar, <a href="/web-llvm/docs/api/classes/llvm/sdvalue">SDValue</a> AVL)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Declaration at line 202 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/ve/vecustomdag-h">VECustomDAG.h</a>, definition at line 422 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/ve/vecustomdag-cpp">VECustomDAG.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/silowercontrolflow-cpp/#a4868c5d81c5ccc98c47aeab6244346a0">assert</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a22eeee01734061ac1b31ccd994c49eef">llvm::dyn_cast</a>, <a href="#a33828d2d1154bc3142d35300e0460959">getBroadcast</a>, <a href="#a4d94a477b234a43ddcf817c49c59d575">getConstantMask</a>, <a href="/web-llvm/docs/api/classes/llvm/sdvalue/#a2b08aa629a6326d1a0444ee6d477c39d">llvm::SDValue::getNode</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#ad1b6d700f803718300ba21413283f7eb">llvm::getTypePacking</a>, <a href="/web-llvm/docs/api/structs/llvm/evt/#ae245d70802e4ebe1cae2b6122c62a22a">llvm::EVT::getVectorNumElements</a>, <a href="/web-llvm/docs/api/classes/llvm/mvt/#abf8d0055af4879a302268d3f834b2be5">llvm::MVT::getVectorVT</a>, <a href="/web-llvm/docs/api/namespaces/llvm/isd/#ac3c3cf58d6d631af6a172457304d3d07a2887cc8b39915a25180f4bca0026a15e">llvm::ISD::SETNE</a> and <a href="/web-llvm/docs/api/namespaces/llvm/veisd/#a49f380eab7f36fdf783b97376cf8065eaff28a96ed40cf064a55fd76a6aa58989">llvm::VEISD::VEC_BROADCAST</a>.</p>


<p>Referenced by <a href="#a33828d2d1154bc3142d35300e0460959">getBroadcast</a>.</p>

</div>
</div>

### getMergeValues() {#a2a7d147364709982a559ec4186fa5d1e}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">SDValue llvm::VECustomDAG::getMergeValues (<a href="/web-llvm/docs/api/classes/llvm/arrayref">ArrayRef</a>&lt; <a href="/web-llvm/docs/api/classes/llvm/sdvalue">SDValue</a> &gt; Values)</td>
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

<p>} <a href="/web-llvm/docs/api/namespaces/llvm/#a6405223942a3a52775bb99d512dca2ad">Packing</a></p>

<p>Definition at line 194 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/ve/vecustomdag-h">VECustomDAG.h</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/classes/llvm/vetargetlowering/#a087a79677b0a36af63d2122ea6e1ee29">llvm::VETargetLowering::lowerVVP_GATHER_SCATTER</a>, <a href="/web-llvm/docs/api/classes/llvm/vetargetlowering/#a2f8e0ad32ef05ffb3966db924f5ae9ee">llvm::VETargetLowering::lowerVVP_LOAD_STORE</a> and <a href="/web-llvm/docs/api/classes/llvm/vetargetlowering/#aaa24ed1e70b01f73a7f60f6c3d6c83a4">llvm::VETargetLowering::splitPackedLoadStore</a>.</p>

</div>
</div>

### getNode() {#a6bc77ff0f140f382784b468fb1b8f65e}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">SDValue llvm::VECustomDAG::getNode (unsigned OC, <a href="/web-llvm/docs/api/structs/llvm/sdvtlist">SDVTList</a> VTL, <a href="/web-llvm/docs/api/classes/llvm/arrayref">ArrayRef</a>&lt; <a href="/web-llvm/docs/api/classes/llvm/sdvalue">SDValue</a> &gt; OpV, std::optional&lt; <a href="/web-llvm/docs/api/structs/llvm/sdnodeflags">SDNodeFlags</a> &gt; Flags=std::nullopt)</td>
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

<p>getNode {</p>

<p>Definition at line 156 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/ve/vecustomdag-h">VECustomDAG.h</a>.</p>


<p>Reference <a href="/web-llvm/docs/api/files/lib/lib/support/regcomp-c/#a0240ac851181b84ac374872dc5434ee4">N</a>.</p>


<p>Referenced by <a href="#a7f0d42ec138cbda5ad9f106de9c63c7c">annotateLegalAVL</a>, <a href="#a33828d2d1154bc3142d35300e0460959">getBroadcast</a>, <a href="#a4d94a477b234a43ddcf817c49c59d575">getConstantMask</a>, <a href="#a51a84e2a653d37da834d4e3f7eb662c8">getGatherScatterAddress</a>, <a href="#a5dcd3bf98753b88499149fbe53d4f913">getLegalReductionOpVVP</a>, <a href="#a05fa62cfcf9c4e5947236b7c8631c772">getSplitPtrOffset</a>, <a href="#adb85958a25173ec157b8244230f8d83f">getSplitPtrStride</a>, <a href="#ae417bd7b6316086f84e03b50c2bf8915">getTargetSplitMask</a>, <a href="/web-llvm/docs/api/classes/llvm/vetargetlowering/#a5b511edb819f787e3913f2c3bd6bab00">llvm::VETargetLowering::legalizePackedAVL</a>, <a href="/web-llvm/docs/api/classes/llvm/vetargetlowering/#aaf4437cbbdf47747d1297e4e66c977cc">llvm::VETargetLowering::lowerBUILD_VECTOR</a>, <a href="/web-llvm/docs/api/classes/llvm/vetargetlowering/#a144a947122d0dd71ef58276fef8dfbb3">llvm::VETargetLowering::lowerToVVP</a>, <a href="/web-llvm/docs/api/classes/llvm/vetargetlowering/#a087a79677b0a36af63d2122ea6e1ee29">llvm::VETargetLowering::lowerVVP_GATHER_SCATTER</a>, <a href="/web-llvm/docs/api/classes/llvm/vetargetlowering/#a2f8e0ad32ef05ffb3966db924f5ae9ee">llvm::VETargetLowering::lowerVVP_LOAD_STORE</a>, <a href="/web-llvm/docs/api/classes/llvm/vetargetlowering/#a01ecd83dddd47ee7cb952356a66f776c">llvm::VETargetLowering::splitMaskArithmetic</a>, <a href="/web-llvm/docs/api/classes/llvm/vetargetlowering/#aaa24ed1e70b01f73a7f60f6c3d6c83a4">llvm::VETargetLowering::splitPackedLoadStore</a> and <a href="/web-llvm/docs/api/classes/llvm/vetargetlowering/#ac796b9abfdee3add2549c94b5f3ddf11">llvm::VETargetLowering::splitVectorOp</a>.</p>

</div>
</div>

### getNode() {#a24f2724c3180118c51af9b3fe77328f2}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">SDValue llvm::VECustomDAG::getNode (unsigned OC, <a href="/web-llvm/docs/api/classes/llvm/arrayref">ArrayRef</a>&lt; <a href="/web-llvm/docs/api/structs/llvm/evt">EVT</a> &gt; ResVT, <a href="/web-llvm/docs/api/classes/llvm/arrayref">ArrayRef</a>&lt; <a href="/web-llvm/docs/api/classes/llvm/sdvalue">SDValue</a> &gt; OpV, std::optional&lt; <a href="/web-llvm/docs/api/structs/llvm/sdnodeflags">SDNodeFlags</a> &gt; Flags=std::nullopt)</td>
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



<p>Definition at line 164 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/ve/vecustomdag-h">VECustomDAG.h</a>.</p>


<p>Reference <a href="/web-llvm/docs/api/files/lib/lib/support/regcomp-c/#a0240ac851181b84ac374872dc5434ee4">N</a>.</p>

</div>
</div>

### getNode() {#afd07a519f6f716dfb3649c99c3bf8fc2}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">SDValue llvm::VECustomDAG::getNode (unsigned OC, <a href="/web-llvm/docs/api/structs/llvm/evt">EVT</a> ResVT, <a href="/web-llvm/docs/api/classes/llvm/arrayref">ArrayRef</a>&lt; <a href="/web-llvm/docs/api/classes/llvm/sdvalue">SDValue</a> &gt; OpV, std::optional&lt; <a href="/web-llvm/docs/api/structs/llvm/sdnodeflags">SDNodeFlags</a> &gt; Flags=std::nullopt)</td>
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



<p>Definition at line 172 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/ve/vecustomdag-h">VECustomDAG.h</a>.</p>


<p>Reference <a href="/web-llvm/docs/api/files/lib/lib/support/regcomp-c/#a0240ac851181b84ac374872dc5434ee4">N</a>.</p>

</div>
</div>

### getPack() {#aac3d4c9bf1c3f241d05e2b6ff1da908c}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">SDValue llvm::VECustomDAG::getPack (<a href="/web-llvm/docs/api/structs/llvm/evt">EVT</a> DestVT, <a href="/web-llvm/docs/api/classes/llvm/sdvalue">SDValue</a> LoVec, <a href="/web-llvm/docs/api/classes/llvm/sdvalue">SDValue</a> HiVec, <a href="/web-llvm/docs/api/classes/llvm/sdvalue">SDValue</a> AVL)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Declaration at line 191 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/ve/vecustomdag-h">VECustomDAG.h</a>, definition at line 490 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/ve/vecustomdag-cpp">VECustomDAG.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/silowercontrolflow-cpp/#a4868c5d81c5ccc98c47aeab6244346a0">assert</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#ab36c9d24e2e9bf7f23e297e087acb8ce">llvm::getAnnotatedNodeAVL</a> and <a href="/web-llvm/docs/api/namespaces/llvm/veisd/#a49f380eab7f36fdf783b97376cf8065ea4da0e8711a1f646b6712352e97076461">llvm::VEISD::VEC_PACK</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/classes/llvm/vetargetlowering/#a01ecd83dddd47ee7cb952356a66f776c">llvm::VETargetLowering::splitMaskArithmetic</a>, <a href="/web-llvm/docs/api/classes/llvm/vetargetlowering/#aaa24ed1e70b01f73a7f60f6c3d6c83a4">llvm::VETargetLowering::splitPackedLoadStore</a> and <a href="/web-llvm/docs/api/classes/llvm/vetargetlowering/#ac796b9abfdee3add2549c94b5f3ddf11">llvm::VETargetLowering::splitVectorOp</a>.</p>

</div>
</div>

### getSplitPtrOffset() {#a05fa62cfcf9c4e5947236b7c8631c772}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">SDValue llvm::VECustomDAG::getSplitPtrOffset (<a href="/web-llvm/docs/api/classes/llvm/sdvalue">SDValue</a> Ptr, <a href="/web-llvm/docs/api/classes/llvm/sdvalue">SDValue</a> ByteStride, <a href="/web-llvm/docs/api/namespaces/llvm/#a9ac8e4e13ad96a39c3f8db9ed633ad2b">PackElem</a> Part)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Declaration at line 211 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/ve/vecustomdag-h">VECustomDAG.h</a>, definition at line 521 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/ve/vecustomdag-cpp">VECustomDAG.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/namespaces/llvm/isd/#a22ea9cec080dd5f4f47ba234c2f59110a269996b43a1f3e1d1f84a70fd4387535">llvm::ISD::ADD</a>, <a href="#a6bc77ff0f140f382784b468fb1b8f65e">getNode</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a9ac8e4e13ad96a39c3f8db9ed633ad2bac1a5298f939e87e8f962a5edfc206918">llvm::Hi</a> and <a href="/web-llvm/docs/api/files/lib/lib/analysis/targetlibraryinfo-cpp/#aca185e6d0e9f423dbb24440206454872a11dbf501abf829b3ab7049c2d3a8a053">Ptr</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/classes/llvm/vetargetlowering/#aaa24ed1e70b01f73a7f60f6c3d6c83a4">llvm::VETargetLowering::splitPackedLoadStore</a>.</p>

</div>
</div>

### getSplitPtrStride() {#adb85958a25173ec157b8244230f8d83f}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">SDValue llvm::VECustomDAG::getSplitPtrStride (<a href="/web-llvm/docs/api/classes/llvm/sdvalue">SDValue</a> PackStride)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Declaration at line 213 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/ve/vecustomdag-h">VECustomDAG.h</a>, definition at line 530 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/ve/vecustomdag-cpp">VECustomDAG.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/namespaces/llvm/#a22eeee01734061ac1b31ccd994c49eef">llvm::dyn_cast</a>, <a href="#adb789b9db13d7d57909fe893bf5b8ec7">getConstant</a>, <a href="#a6bc77ff0f140f382784b468fb1b8f65e">getNode</a> and <a href="/web-llvm/docs/api/namespaces/llvm/isd/#a22ea9cec080dd5f4f47ba234c2f59110a8cc94e03dea594863073a02f5bb94997">llvm::ISD::SHL</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/classes/llvm/vetargetlowering/#aaa24ed1e70b01f73a7f60f6c3d6c83a4">llvm::VETargetLowering::splitPackedLoadStore</a>.</p>

</div>
</div>

### getTargetSplitMask() {#ae417bd7b6316086f84e03b50c2bf8915}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">VETargetMasks llvm::VECustomDAG::getTargetSplitMask (<a href="/web-llvm/docs/api/classes/llvm/sdvalue">SDValue</a> RawMask, <a href="/web-llvm/docs/api/classes/llvm/sdvalue">SDValue</a> RawAVL, <a href="/web-llvm/docs/api/namespaces/llvm/#a9ac8e4e13ad96a39c3f8db9ed633ad2b">PackElem</a> Part)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Declaration at line 207 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/ve/vecustomdag-h">VECustomDAG.h</a>, definition at line 498 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/ve/vecustomdag-cpp">VECustomDAG.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/namespaces/llvm/isd/#a22ea9cec080dd5f4f47ba234c2f59110a269996b43a1f3e1d1f84a70fd4387535">llvm::ISD::ADD</a>, <a href="#a7f0d42ec138cbda5ad9f106de9c63c7c">annotateLegalAVL</a>, <a href="#adb789b9db13d7d57909fe893bf5b8ec7">getConstant</a>, <a href="#a4d94a477b234a43ddcf817c49c59d575">getConstantMask</a>, <a href="#a6bc77ff0f140f382784b468fb1b8f65e">getNode</a>, <a href="#a871da559dbbc4dd972b1fd4308fdacef">getUnpack</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a9ac8e4e13ad96a39c3f8db9ed633ad2bac1a5298f939e87e8f962a5edfc206918">llvm::Hi</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a6405223942a3a52775bb99d512dca2ada960b44c579bc2f6818d2daaf9e4c16f0">llvm::Normal</a> and <a href="/web-llvm/docs/api/namespaces/llvm/isd/#a22ea9cec080dd5f4f47ba234c2f59110a3c6553c8acebe1b57c211ee45e2d8f98">llvm::ISD::SRL</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/classes/llvm/vetargetlowering/#aaa24ed1e70b01f73a7f60f6c3d6c83a4">llvm::VETargetLowering::splitPackedLoadStore</a> and <a href="/web-llvm/docs/api/classes/llvm/vetargetlowering/#ac796b9abfdee3add2549c94b5f3ddf11">llvm::VETargetLowering::splitVectorOp</a>.</p>

</div>
</div>

### getUNDEF() {#a8b43494409db5f4c462bb8dcd4a10379}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">SDValue llvm::VECustomDAG::getUNDEF (<a href="/web-llvm/docs/api/structs/llvm/evt">EVT</a> VT)</td>
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



<p>Definition at line 180 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/ve/vecustomdag-h">VECustomDAG.h</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/classes/llvm/vetargetlowering/#aaf4437cbbdf47747d1297e4e66c977cc">llvm::VETargetLowering::lowerBUILD_VECTOR</a>.</p>

</div>
</div>

### getUnpack() {#a871da559dbbc4dd972b1fd4308fdacef}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">SDValue llvm::VECustomDAG::getUnpack (<a href="/web-llvm/docs/api/structs/llvm/evt">EVT</a> DestVT, <a href="/web-llvm/docs/api/classes/llvm/sdvalue">SDValue</a> Vec, <a href="/web-llvm/docs/api/namespaces/llvm/#a9ac8e4e13ad96a39c3f8db9ed633ad2b">PackElem</a> Part, <a href="/web-llvm/docs/api/classes/llvm/sdvalue">SDValue</a> AVL)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>} Legalizing getNode</p>


<p><a href="/web-llvm/docs/api/namespaces/llvm/#a6405223942a3a52775bb99d512dca2ad">Packing</a> {</p>


<p>Declaration at line 190 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/ve/vecustomdag-h">VECustomDAG.h</a>, definition at line 480 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/ve/vecustomdag-cpp">VECustomDAG.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/silowercontrolflow-cpp/#a4868c5d81c5ccc98c47aeab6244346a0">assert</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#ab36c9d24e2e9bf7f23e297e087acb8ce">llvm::getAnnotatedNodeAVL</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a9ac8e4e13ad96a39c3f8db9ed633ad2baff50b4aa1c9cc2197ef898436641c911">llvm::Lo</a>, <a href="/web-llvm/docs/api/namespaces/llvm/veisd/#a49f380eab7f36fdf783b97376cf8065eac2e8495bbe1525a5a532a8843cfa4b7f">llvm::VEISD::VEC_UNPACK_HI</a> and <a href="/web-llvm/docs/api/namespaces/llvm/veisd/#a49f380eab7f36fdf783b97376cf8065eaf662c0fb94f348a70a3091ae4b56b3bb">llvm::VEISD::VEC_UNPACK_LO</a>.</p>


<p>Referenced by <a href="#ae417bd7b6316086f84e03b50c2bf8915">getTargetSplitMask</a>, <a href="/web-llvm/docs/api/classes/llvm/vetargetlowering/#a01ecd83dddd47ee7cb952356a66f776c">llvm::VETargetLowering::splitMaskArithmetic</a>, <a href="/web-llvm/docs/api/classes/llvm/vetargetlowering/#aaa24ed1e70b01f73a7f60f6c3d6c83a4">llvm::VETargetLowering::splitPackedLoadStore</a> and <a href="/web-llvm/docs/api/classes/llvm/vetargetlowering/#ac796b9abfdee3add2549c94b5f3ddf11">llvm::VETargetLowering::splitVectorOp</a>.</p>

</div>
</div>

### getVectorVT() {#ada28169376dccd18b7bf89215c83adc5}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">EVT llvm::VECustomDAG::getVectorVT (<a href="/web-llvm/docs/api/structs/llvm/evt">EVT</a> ElemVT, unsigned NumElems)</td>
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



<p>Definition at line 216 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/ve/vecustomdag-h">VECustomDAG.h</a>.</p>


<p>Reference <a href="/web-llvm/docs/api/structs/llvm/evt/#a210ba6b43ba451b698857dd9de71bd15">llvm::EVT::getVectorVT</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Private Member Attributes

### DAG {#a296bd0523713054145b12423233db6ef}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">SelectionDAG&amp; llvm::VECustomDAG::DAG</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 143 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/ve/vecustomdag-h">VECustomDAG.h</a>.</p>

</div>
</div>

### DL {#ab84813bb43cd974380e91af99129d7d9}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">SDLoc llvm::VECustomDAG::DL</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 144 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/ve/vecustomdag-h">VECustomDAG.h</a>.</p>

</div>
</div>

</div>

<hr/>

The documentation for this class was generated from the following files:

<ul>
<li><a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/ve/vecustomdag-cpp">VECustomDAG.cpp</a></li>
<li><a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/ve/vecustomdag-h">VECustomDAG.h</a></li>
</ul>

<hr/>

<p class="doxyGeneratedBy">Generated via <a href="https://github.com/xpack/doxygen2docusaurus">doxygen2docusaurus</a> by <a href="https://www.doxygen.nl">Doxygen</a> 1.15.0.</p>

</div>
