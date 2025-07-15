---

# DO NOT EDIT!
# Automatically generated via doxygen2docusaurus by Doxygen.

slug: /api/classes/anonymous-structurizecfg-cpp-/structurizecfg
custom_edit_url: null
toc_max_heading_level: 4
keywords:
  - doxygen
  - reference
  - class

---

<div class="doxyPage">

# The `StructurizeCFG` Class Reference

<p>Transforms the control flow graph on one single entry/exit region at a time. <a href="#details">More...</a></p>

## Declaration

<div class="doxyDeclaration">
class anonymous{StructurizeCFG.cpp}::StructurizeCFG { ... }
</div>

## Public Member Functions Index

<table class="doxyMembersIndex">

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">void</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a88fa969de8279bbac9d3718775723b50">init</a> (Region *R)</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#aa5aa23c5169a9bc1cf14f6ed750717e8">run</a> (Region *R, DominatorTree *DT)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Run the transformation for each region found. <a href="#aa5aa23c5169a9bc1cf14f6ed750717e8">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">bool</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#aa2ebb8b48e7c632966b1cda5d79a257a">makeUniformRegion</a> (Region *R, UniformityInfo &amp;UA)</td>
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

## Private Member Functions Index

<table class="doxyMembersIndex">

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">void</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#aef1c7818820b7a812ed566e3138b8f2f">orderNodes</a> ()</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Build up the general order of nodes, by performing a topological sort of the parent region's nodes, while ensuring that there is no outer cycle node between any two inner cycle nodes. <a href="#aef1c7818820b7a812ed566e3138b8f2f">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">void</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#aee92775a299a48cb187aacd4103157a9">analyzeLoops</a> (RegionNode *N)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Determine the end of the loops. <a href="#aee92775a299a48cb187aacd4103157a9">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/structs/anonymous-structurizecfg-cpp-/predinfo">PredInfo</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a928aacf4c183a36d589b7fa07b375327">buildCondition</a> (BranchInst *Term, unsigned Idx, bool Invert)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Build the condition for one edge. <a href="#a928aacf4c183a36d589b7fa07b375327">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">void</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a92b91e1d9e09e4fd936d45a41264a8b0">gatherPredicates</a> (RegionNode *N)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Analyze the predecessors of each block and build up predicates. <a href="#a92b91e1d9e09e4fd936d45a41264a8b0">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">void</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a2fcbbd61aa3db40465f43ddbdec25bba">collectInfos</a> ()</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Collect various loop and predicate infos. <a href="#a2fcbbd61aa3db40465f43ddbdec25bba">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">void</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#aee911748e1a076d7ffbfba17624db048">insertConditions</a> (bool Loops)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Insert the missing branch conditions. <a href="#aee911748e1a076d7ffbfba17624db048">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">void</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#af2b5a4b160e6f710414e26ea858b5b06">simplifyConditions</a> ()</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Simplify any inverted conditions that were built by buildConditions. <a href="#af2b5a4b160e6f710414e26ea858b5b06">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">void</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#aa41c40c6f0ed03894d0be962cc72aef3">delPhiValues</a> (BasicBlock *From, BasicBlock *To)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Remove all PHI values coming from "From" into "To" and remember them in DeletedPhis. <a href="#aa41c40c6f0ed03894d0be962cc72aef3">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">void</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ae25f27044904030bee35785c261c9199">addPhiValues</a> (BasicBlock *From, BasicBlock *To)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Add a dummy PHI value as soon as we knew the new predecessor. <a href="#ae25f27044904030bee35785c261c9199">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">void</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ac25e4b6a874225141f3f5211c089d59e">findUndefBlocks</a> (BasicBlock *PHIBlock, const SmallSet&lt; BasicBlock *, 8 &gt; &amp;Incomings, SmallVector&lt; BasicBlock * &gt; &amp;UndefBlks) const</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>When we are reconstructing a PHI inside <span class="doxyComputerOutput">PHIBlock</span> with incoming values from predecessors <span class="doxyComputerOutput">Incomings</span>, we have a chance to mark the available value from some blocks as undefined. <a href="#ac25e4b6a874225141f3f5211c089d59e">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">void</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a57ad96c38a241b7165ecc7196cba5dad">mergeIfCompatible</a> (EquivalenceClasses&lt; PHINode * &gt; &amp;PhiClasses, PHINode *A, PHINode *B)</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a0a6f59a135f6035d25132a27d6462aa3">setPhiValues</a> ()</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Add the real PHI value as soon as everything is set up. <a href="#a0a6f59a135f6035d25132a27d6462aa3">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">void</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a7dc28ad086da9f645a89c3648a717526">simplifyAffectedPhis</a> ()</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a08cfca281f6c3c311ae5775e98b8048a">killTerminator</a> (BasicBlock *BB)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Remove phi values from all successors and then remove the terminator. <a href="#a08cfca281f6c3c311ae5775e98b8048a">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">void</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a096c890de40fb6ccec2b09c4dcf2a0f8">changeExit</a> (RegionNode *Node, BasicBlock *NewExit, bool IncludeDominator)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Let node exit(s) point to NewExit. <a href="#a096c890de40fb6ccec2b09c4dcf2a0f8">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/basicblock">BasicBlock</a> *</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ab5254f3d747320eea6029c29daee0738">getNextFlow</a> (BasicBlock *Dominator)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Create a new flow node and update dominator tree and region info. <a href="#ab5254f3d747320eea6029c29daee0738">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/basicblock">BasicBlock</a> *</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a2e3df36a4673db21c8aeebc34b7c14f9">needPrefix</a> (bool NeedEmpty)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Create a new or reuse the previous node as flow node. <a href="#a2e3df36a4673db21c8aeebc34b7c14f9">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/basicblock">BasicBlock</a> *</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a16311b3afbb74f04fbf5857fdcdb6f6d">needPostfix</a> (BasicBlock *Flow, bool ExitUseAllowed)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Returns the region exit if possible, otherwise just a new flow node. <a href="#a16311b3afbb74f04fbf5857fdcdb6f6d">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">void</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a891573bb97c83d66139c13dbe27955b1">setPrevNode</a> (BasicBlock *BB)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Set the previous node. <a href="#a891573bb97c83d66139c13dbe27955b1">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">bool</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a121b2d5ed83fbe08cbddd36a32629442">dominatesPredicates</a> (BasicBlock *BB, RegionNode *Node)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Does BB dominate all the predicates of <a href="/web-llvm/docs/api/classes/node">Node</a>? <a href="#a121b2d5ed83fbe08cbddd36a32629442">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">bool</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a53af414aa569c00cdb1d5b2e117d00c6">isPredictableTrue</a> (RegionNode *Node)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Can we predict that this node will always be called? <a href="#a53af414aa569c00cdb1d5b2e117d00c6">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">void</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a1f7ca0920099c8bf623a903167268f70">wireFlow</a> (bool ExitUseAllowed, BasicBlock *LoopEnd)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Take one node from the order vector and wire it up. <a href="#a1f7ca0920099c8bf623a903167268f70">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">void</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a7dde8574cab7b012dcee1369c8a4a514">handleLoops</a> (bool ExitUseAllowed, BasicBlock *LoopEnd)</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a8c259b307e89399ce241ff06c4609622">createFlow</a> ()</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>After this function control flow looks like it should be, but branches and PHI nodes only have undefined conditions. <a href="#a8c259b307e89399ce241ff06c4609622">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">void</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ab7da1981276acd2b1ff543fd2bdbea59">rebuildSSA</a> ()</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Handle a rare case where the disintegrated nodes instructions no longer dominate all their uses. <a href="#ab7da1981276acd2b1ff543fd2bdbea59">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

</table>

## Private Member Attributes Index

<table class="doxyMembersIndex">

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/type">Type</a> *</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a1bc1d94c9059399f62e2625e53e319f7">Boolean</a></td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/constantint">ConstantInt</a> *</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ab945f305cb5fdaf98922f5a1cc1b050d">BoolTrue</a></td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/constantint">ConstantInt</a> *</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a02d252557efb96f853e8421540d87b25">BoolFalse</a></td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/value">Value</a> *</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a15292c0c2a173a898b95e54212de9a8a">BoolPoison</a></td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/function">Function</a> *</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a5c21a10fe692b7f4ebd62c6909006e24">Func</a></td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/region">Region</a> *</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a2c4ad44b0b1c80ef2147ffbe661e7a1b">ParentRegion</a></td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/namespaces/llvm/#a00a2f5a62b5d5d5b6b0e143c4d30041f">UniformityInfo</a> *</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a935e3206aa0b27a037fbfbd4d0ebb995">UA</a> = nullptr</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/dominatortree">DominatorTree</a> *</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ac80643c98e782543c05a224429156465">DT</a></td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/smallvector">SmallVector</a>&lt; <a href="/web-llvm/docs/api/classes/llvm/regionnode">RegionNode</a> *, 8 &gt;</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a01f0b20d4d8147cb89ccc98305c1086e">Order</a></td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/namespaces/anonymous-structurizecfg-cpp-/#a68d8ef4336337d48e93d2695078eaa8a">BBSet</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#aac0ba3cd36810347423cf9bcf67c1135">Visited</a></td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/namespaces/anonymous-structurizecfg-cpp-/#a68d8ef4336337d48e93d2695078eaa8a">BBSet</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#abedae77480970e8675b780d81334dce2">FlowSet</a></td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/smallvector">SmallVector</a>&lt; <a href="/web-llvm/docs/api/classes/llvm/weakvh">WeakVH</a>, 8 &gt;</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a46df5e278e6bbf85903583fb4da0349e">AffectedPhis</a></td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/namespaces/anonymous-structurizecfg-cpp-/#a4b3f51cb0e962615906c19d321a36c3d">BBPhiMap</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a81062d3fe06123e31ec788d9f8fcb2a2">DeletedPhis</a></td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/namespaces/anonymous-structurizecfg-cpp-/#a0bc6097d22abc3599d59cc4e54125ae5">BB2BBVecMap</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#aa2e4ea5fec0ed514e2bc48c38595bd6d">AddedPhis</a></td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/namespaces/anonymous-structurizecfg-cpp-/#ac091dfcf8842b843957ec9df17789989">PredMap</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a1e874a729bde72d7ad1765303d3457ae">Predicates</a></td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/namespaces/anonymous-structurizecfg-cpp-/#ab8635f13889d2429aa82bfc3e6264651">BranchVector</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a61f560ccf3847fe07a262855241ee39b">Conditions</a></td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/namespaces/anonymous-structurizecfg-cpp-/#a0cb8bfe08f3ef40d7c34b57c07ddee60">BB2BBMap</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#aeca8628b6b9131d35ad2642f7d8e8d85">Loops</a></td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/namespaces/anonymous-structurizecfg-cpp-/#ac091dfcf8842b843957ec9df17789989">PredMap</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ad12f4d9c07fe18c51e3dff65e65a3aa5">LoopPreds</a></td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/namespaces/anonymous-structurizecfg-cpp-/#ab8635f13889d2429aa82bfc3e6264651">BranchVector</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a284483a62e3d131817da95467c2842a8">LoopConds</a></td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/namespaces/anonymous-structurizecfg-cpp-/#a3ba1b4064479d872e2fae5f5aa35e9ac">BranchDebugLocMap</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#aee47765f2b6471ca36aff60d8e98ccbf">TermDL</a></td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/regionnode">RegionNode</a> *</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a80dfc9f631eb73f21ae7d72d731f5b04">PrevNode</a></td>
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

<p>Transforms the control flow graph on one single entry/exit region at a time.</p>


<p>After the transform all "If"/"Then"/"Else" style control flow looks like this:</p>



<pre><code>/// 1
/// ||
/// | |
/// 2 |
/// | /
/// |/
/// 3
/// ||   Where:
/// | |  1 = "If" block, calculates the condition
/// 4 |  2 = "Then" subregion, runs if the condition is true
/// | /  3 = "Flow" blocks, newly inserted flow blocks, rejoins the flow
/// |/   4 = "Else" optional subregion, runs if the condition is false
/// 5    5 = "End" block, also rejoins the control flow
///
</code></pre>


<p>Control flow is expressed as a branch where the true exit goes into the "Then"/"Else" region, while the false exit skips the region The condition for the optional "Else" region is expressed as a PHI node. The incoming values of the PHI node are true for the "If" edge and false for the "Then" edge.</p>


<p>Additionally to that even complicated loops look like this:</p>



<pre><code>/// 1
/// ||
/// | |
/// 2 ^  Where:
/// | /  1 = "Entry" block
/// |/   2 = "Loop" optional subregion, with all exits at "Flow" block
/// 3    3 = "Flow" block, with back edge to entry block
/// |
///
</code></pre>


<p>The back edge of the "Flow" block is always on the false side of the branch while the true side continues the general flow. So the loop condition consist of a network of PHI nodes where the true incoming values expresses breaks and the false values expresses continue states.</p>


<p>Definition at line 279 of file <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/scalar/structurizecfg-cpp">StructurizeCFG.cpp</a>.</p>


<div class="doxySectionDef">

## Public Member Functions

### init() {#a88fa969de8279bbac9d3718775723b50}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void StructurizeCFG::init (<a href="/web-llvm/docs/api/classes/llvm/region">Region</a> * R)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 365 of file <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/scalar/structurizecfg-cpp">StructurizeCFG.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/classes/llvm/poisonvalue/#a1bf08613fb664a2e377a9a72c59a6b66">llvm::PoisonValue::get</a>, <a href="/web-llvm/docs/api/classes/llvm/constantint/#aa7cce62ac5cc6df09cce0535874336b7">llvm::ConstantInt::getFalse</a>, <a href="/web-llvm/docs/api/classes/llvm/type/#aa75984a442f2379de0c66018201fa628">llvm::Type::getInt1Ty</a> and <a href="/web-llvm/docs/api/classes/llvm/constantint/#a82dbbd8e3688b0bc1eedb338864d0d0c">llvm::ConstantInt::getTrue</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/classes/anonymous-structurizecfg-cpp-/structurizecfglegacypass/#aecbd421c713f3803e5d34d14db2b4409">anonymous{StructurizeCFG.cpp}::StructurizeCFGLegacyPass::runOnRegion</a>.</p>

</div>
</div>

### makeUniformRegion() {#aa2ebb8b48e7c632966b1cda5d79a257a}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool StructurizeCFG::makeUniformRegion (<a href="/web-llvm/docs/api/classes/llvm/region">Region</a> * R, <a href="/web-llvm/docs/api/namespaces/llvm/#a00a2f5a62b5d5d5b6b0e143c4d30041f">UniformityInfo</a> &amp; UA)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 367 of file <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/scalar/structurizecfg-cpp">StructurizeCFG.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/namespaces/llvm/#a7c46c742c31be54870e2038048e6b391">llvm::dbgs</a>, <a href="/web-llvm/docs/api/classes/llvm/mdnode/#a7d10a7b9b7f40b04d27ed97c38ea1950">llvm::MDNode::get</a>, <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/scalar/structurizecfg-cpp/#ad1d9e6fe4974ee0754beaf3d7756bf20">hasOnlyUniformBranches</a> and <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/support/debug-h/#a196897517069dda1bdb549e24468f7d7">LLVM_DEBUG</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/classes/anonymous-structurizecfg-cpp-/structurizecfglegacypass/#aecbd421c713f3803e5d34d14db2b4409">anonymous{StructurizeCFG.cpp}::StructurizeCFGLegacyPass::runOnRegion</a>.</p>

</div>
</div>

### run() {#aa5aa23c5169a9bc1cf14f6ed750717e8}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool StructurizeCFG::run (<a href="/web-llvm/docs/api/classes/llvm/region">Region</a> * R, <a href="/web-llvm/docs/api/classes/llvm/dominatortree">DominatorTree</a> * DT)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Run the transformation for each region found.</p>

<p>Definition at line 366 of file <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/scalar/structurizecfg-cpp">StructurizeCFG.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/silowercontrolflow-cpp/#a4868c5d81c5ccc98c47aeab6244346a0">assert</a> and <a href="/web-llvm/docs/api/namespaces/llvm/#a2436f015662138f27cf2be735ad740e3">llvm::hasOnlySimpleTerminator</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/classes/anonymous-structurizecfg-cpp-/structurizecfglegacypass/#aecbd421c713f3803e5d34d14db2b4409">anonymous{StructurizeCFG.cpp}::StructurizeCFGLegacyPass::runOnRegion</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Private Member Functions

### addPhiValues() {#ae25f27044904030bee35785c261c9199}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void StructurizeCFG::addPhiValues (<a href="/web-llvm/docs/api/classes/llvm/basicblock">BasicBlock</a> * From, <a href="/web-llvm/docs/api/classes/llvm/basicblock">BasicBlock</a> * To)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Add a dummy PHI value as soon as we knew the new predecessor.</p>

<p>Definition at line 326 of file <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/scalar/structurizecfg-cpp">StructurizeCFG.cpp</a>.</p>

</div>
</div>

### analyzeLoops() {#aee92775a299a48cb187aacd4103157a9}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void StructurizeCFG::analyzeLoops (<a href="/web-llvm/docs/api/classes/llvm/regionnode">RegionNode</a> * N)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Determine the end of the loops.</p>

<p>Definition at line 312 of file <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/scalar/structurizecfg-cpp">StructurizeCFG.cpp</a>.</p>

</div>
</div>

### buildCondition() {#a928aacf4c183a36d589b7fa07b375327}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">PredInfo StructurizeCFG::buildCondition (<a href="/web-llvm/docs/api/classes/llvm/branchinst">BranchInst</a> * Term, unsigned Idx, bool Invert)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Build the condition for one edge.</p>

<p>Definition at line 314 of file <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/scalar/structurizecfg-cpp">StructurizeCFG.cpp</a>.</p>

</div>
</div>

### changeExit() {#a096c890de40fb6ccec2b09c4dcf2a0f8}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void StructurizeCFG::changeExit (<a href="/web-llvm/docs/api/classes/llvm/regionnode">RegionNode</a> * Node, <a href="/web-llvm/docs/api/classes/llvm/basicblock">BasicBlock</a> * NewExit, bool IncludeDominator)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Let node exit(s) point to NewExit.</p>

<p>Definition at line 341 of file <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/scalar/structurizecfg-cpp">StructurizeCFG.cpp</a>.</p>

</div>
</div>

### collectInfos() {#a2fcbbd61aa3db40465f43ddbdec25bba}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void StructurizeCFG::collectInfos ()</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Collect various loop and predicate infos.</p>

<p>Definition at line 318 of file <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/scalar/structurizecfg-cpp">StructurizeCFG.cpp</a>.</p>

</div>
</div>

### createFlow() {#a8c259b307e89399ce241ff06c4609622}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void StructurizeCFG::createFlow ()</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>After this function control flow looks like it should be, but branches and PHI nodes only have undefined conditions.</p>

<p>Definition at line 360 of file <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/scalar/structurizecfg-cpp">StructurizeCFG.cpp</a>.</p>

</div>
</div>

### delPhiValues() {#aa41c40c6f0ed03894d0be962cc72aef3}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void StructurizeCFG::delPhiValues (<a href="/web-llvm/docs/api/classes/llvm/basicblock">BasicBlock</a> * From, <a href="/web-llvm/docs/api/classes/llvm/basicblock">BasicBlock</a> * To)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Remove all PHI values coming from "From" into "To" and remember them in DeletedPhis.</p>

<p>Definition at line 324 of file <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/scalar/structurizecfg-cpp">StructurizeCFG.cpp</a>.</p>

</div>
</div>

### dominatesPredicates() {#a121b2d5ed83fbe08cbddd36a32629442}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool StructurizeCFG::dominatesPredicates (<a href="/web-llvm/docs/api/classes/llvm/basicblock">BasicBlock</a> * BB, <a href="/web-llvm/docs/api/classes/llvm/regionnode">RegionNode</a> * Node)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Does BB dominate all the predicates of <a href="/web-llvm/docs/api/classes/node">Node</a>?</p>

<p>Definition at line 352 of file <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/scalar/structurizecfg-cpp">StructurizeCFG.cpp</a>.</p>

</div>
</div>

### findUndefBlocks() {#ac25e4b6a874225141f3f5211c089d59e}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void StructurizeCFG::findUndefBlocks (<a href="/web-llvm/docs/api/classes/llvm/basicblock">BasicBlock</a> * PHIBlock, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/smallset">SmallSet</a>&lt; <a href="/web-llvm/docs/api/classes/llvm/basicblock">BasicBlock</a> *, 8 &gt; &amp; Incomings, <a href="/web-llvm/docs/api/classes/llvm/smallvector">SmallVector</a>&lt; <a href="/web-llvm/docs/api/classes/llvm/basicblock">BasicBlock</a> * &gt; &amp; UndefBlks)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>When we are reconstructing a PHI inside <span class="doxyComputerOutput">PHIBlock</span> with incoming values from predecessors <span class="doxyComputerOutput">Incomings</span>, we have a chance to mark the available value from some blocks as undefined.</p>


<p>The function will find out all such blocks and return in <span class="doxyComputerOutput">UndefBlks</span>.</p>


<p>Definition at line 328 of file <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/scalar/structurizecfg-cpp">StructurizeCFG.cpp</a>.</p>

</div>
</div>

### gatherPredicates() {#a92b91e1d9e09e4fd936d45a41264a8b0}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void StructurizeCFG::gatherPredicates (<a href="/web-llvm/docs/api/classes/llvm/regionnode">RegionNode</a> * N)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Analyze the predecessors of each block and build up predicates.</p>

<p>Definition at line 316 of file <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/scalar/structurizecfg-cpp">StructurizeCFG.cpp</a>.</p>

</div>
</div>

### getNextFlow() {#ab5254f3d747320eea6029c29daee0738}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">BasicBlock * StructurizeCFG::getNextFlow (<a href="/web-llvm/docs/api/classes/llvm/basicblock">BasicBlock</a> * Dominator)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Create a new flow node and update dominator tree and region info.</p>

<p>Definition at line 344 of file <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/scalar/structurizecfg-cpp">StructurizeCFG.cpp</a>.</p>

</div>
</div>

### handleLoops() {#a7dde8574cab7b012dcee1369c8a4a514}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void StructurizeCFG::handleLoops (bool ExitUseAllowed, <a href="/web-llvm/docs/api/classes/llvm/basicblock">BasicBlock</a> * LoopEnd)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 358 of file <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/scalar/structurizecfg-cpp">StructurizeCFG.cpp</a>.</p>

</div>
</div>

### insertConditions() {#aee911748e1a076d7ffbfba17624db048}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void StructurizeCFG::insertConditions (bool Loops)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Insert the missing branch conditions.</p>

<p>Definition at line 320 of file <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/scalar/structurizecfg-cpp">StructurizeCFG.cpp</a>.</p>

</div>
</div>

### isPredictableTrue() {#a53af414aa569c00cdb1d5b2e117d00c6}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool StructurizeCFG::isPredictableTrue (<a href="/web-llvm/docs/api/classes/llvm/regionnode">RegionNode</a> * Node)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Can we predict that this node will always be called?</p>

<p>Definition at line 354 of file <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/scalar/structurizecfg-cpp">StructurizeCFG.cpp</a>.</p>

</div>
</div>

### killTerminator() {#a08cfca281f6c3c311ae5775e98b8048a}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void StructurizeCFG::killTerminator (<a href="/web-llvm/docs/api/classes/llvm/basicblock">BasicBlock</a> * BB)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Remove phi values from all successors and then remove the terminator.</p>

<p>Definition at line 339 of file <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/scalar/structurizecfg-cpp">StructurizeCFG.cpp</a>.</p>

</div>
</div>

### mergeIfCompatible() {#a57ad96c38a241b7165ecc7196cba5dad}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void StructurizeCFG::mergeIfCompatible (<a href="/web-llvm/docs/api/classes/llvm/equivalenceclasses">EquivalenceClasses</a>&lt; <a href="/web-llvm/docs/api/classes/llvm/phinode">PHINode</a> * &gt; &amp; PhiClasses, <a href="/web-llvm/docs/api/classes/llvm/phinode">PHINode</a> * A, <a href="/web-llvm/docs/api/classes/llvm/phinode">PHINode</a> * B)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 332 of file <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/scalar/structurizecfg-cpp">StructurizeCFG.cpp</a>.</p>

</div>
</div>

### needPostfix() {#a16311b3afbb74f04fbf5857fdcdb6f6d}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">BasicBlock * StructurizeCFG::needPostfix (<a href="/web-llvm/docs/api/classes/llvm/basicblock">BasicBlock</a> * Flow, bool ExitUseAllowed)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Returns the region exit if possible, otherwise just a new flow node.</p>

<p>Definition at line 348 of file <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/scalar/structurizecfg-cpp">StructurizeCFG.cpp</a>.</p>

</div>
</div>

### needPrefix() {#a2e3df36a4673db21c8aeebc34b7c14f9}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">BasicBlock * StructurizeCFG::needPrefix (bool NeedEmpty)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Create a new or reuse the previous node as flow node.</p>

<p>Definition at line 346 of file <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/scalar/structurizecfg-cpp">StructurizeCFG.cpp</a>.</p>

</div>
</div>

### orderNodes() {#aef1c7818820b7a812ed566e3138b8f2f}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">Structurize the false void StructurizeCFG::orderNodes ()</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Build up the general order of nodes, by performing a topological sort of the parent region's nodes, while ensuring that there is no outer cycle node between any two inner cycle nodes.</p>

<p>Definition at line 310 of file <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/scalar/structurizecfg-cpp">StructurizeCFG.cpp</a>.</p>

</div>
</div>

### rebuildSSA() {#ab7da1981276acd2b1ff543fd2bdbea59}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void StructurizeCFG::rebuildSSA ()</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Handle a rare case where the disintegrated nodes instructions no longer dominate all their uses.</p>


<p>Not sure if this is really necessary</p>


<p>Definition at line 362 of file <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/scalar/structurizecfg-cpp">StructurizeCFG.cpp</a>.</p>

</div>
</div>

### setPhiValues() {#a0a6f59a135f6035d25132a27d6462aa3}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void StructurizeCFG::setPhiValues ()</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Add the real PHI value as soon as everything is set up.</p>

<p>Definition at line 335 of file <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/scalar/structurizecfg-cpp">StructurizeCFG.cpp</a>.</p>

</div>
</div>

### setPrevNode() {#a891573bb97c83d66139c13dbe27955b1}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void StructurizeCFG::setPrevNode (<a href="/web-llvm/docs/api/classes/llvm/basicblock">BasicBlock</a> * BB)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Set the previous node.</p>

<p>Definition at line 350 of file <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/scalar/structurizecfg-cpp">StructurizeCFG.cpp</a>.</p>

</div>
</div>

### simplifyAffectedPhis() {#a7dc28ad086da9f645a89c3648a717526}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void StructurizeCFG::simplifyAffectedPhis ()</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 337 of file <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/scalar/structurizecfg-cpp">StructurizeCFG.cpp</a>.</p>

</div>
</div>

### simplifyConditions() {#af2b5a4b160e6f710414e26ea858b5b06}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void StructurizeCFG::simplifyConditions ()</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Simplify any inverted conditions that were built by buildConditions.</p>

<p>Definition at line 322 of file <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/scalar/structurizecfg-cpp">StructurizeCFG.cpp</a>.</p>

</div>
</div>

### wireFlow() {#a1f7ca0920099c8bf623a903167268f70}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void StructurizeCFG::wireFlow (bool ExitUseAllowed, <a href="/web-llvm/docs/api/classes/llvm/basicblock">BasicBlock</a> * LoopEnd)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Take one node from the order vector and wire it up.</p>

<p>Definition at line 356 of file <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/scalar/structurizecfg-cpp">StructurizeCFG.cpp</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Private Member Attributes

### AddedPhis {#aa2e4ea5fec0ed514e2bc48c38595bd6d}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">BB2BBVecMap anonymous{StructurizeCFG.cpp}::StructurizeCFG::AddedPhis</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 297 of file <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/scalar/structurizecfg-cpp">StructurizeCFG.cpp</a>.</p>

</div>
</div>

### AffectedPhis {#a46df5e278e6bbf85903583fb4da0349e}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">SmallVector&lt;WeakVH, 8&gt; anonymous{StructurizeCFG.cpp}::StructurizeCFG::AffectedPhis</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 295 of file <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/scalar/structurizecfg-cpp">StructurizeCFG.cpp</a>.</p>

</div>
</div>

### Boolean {#a1bc1d94c9059399f62e2625e53e319f7}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">Type* anonymous{StructurizeCFG.cpp}::StructurizeCFG::Boolean</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 280 of file <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/scalar/structurizecfg-cpp">StructurizeCFG.cpp</a>.</p>

</div>
</div>

### BoolFalse {#a02d252557efb96f853e8421540d87b25}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">ConstantInt* anonymous{StructurizeCFG.cpp}::StructurizeCFG::BoolFalse</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 282 of file <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/scalar/structurizecfg-cpp">StructurizeCFG.cpp</a>.</p>

</div>
</div>

### BoolPoison {#a15292c0c2a173a898b95e54212de9a8a}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">Value* anonymous{StructurizeCFG.cpp}::StructurizeCFG::BoolPoison</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 283 of file <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/scalar/structurizecfg-cpp">StructurizeCFG.cpp</a>.</p>

</div>
</div>

### BoolTrue {#ab945f305cb5fdaf98922f5a1cc1b050d}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">ConstantInt* anonymous{StructurizeCFG.cpp}::StructurizeCFG::BoolTrue</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 281 of file <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/scalar/structurizecfg-cpp">StructurizeCFG.cpp</a>.</p>

</div>
</div>

### Conditions {#a61f560ccf3847fe07a262855241ee39b}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">BranchVector anonymous{StructurizeCFG.cpp}::StructurizeCFG::Conditions</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 300 of file <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/scalar/structurizecfg-cpp">StructurizeCFG.cpp</a>.</p>

</div>
</div>

### DeletedPhis {#a81062d3fe06123e31ec788d9f8fcb2a2}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">BBPhiMap anonymous{StructurizeCFG.cpp}::StructurizeCFG::DeletedPhis</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 296 of file <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/scalar/structurizecfg-cpp">StructurizeCFG.cpp</a>.</p>

</div>
</div>

### DT {#ac80643c98e782543c05a224429156465}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">DominatorTree* anonymous{StructurizeCFG.cpp}::StructurizeCFG::DT</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 289 of file <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/scalar/structurizecfg-cpp">StructurizeCFG.cpp</a>.</p>

</div>
</div>

### FlowSet {#abedae77480970e8675b780d81334dce2}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">BBSet anonymous{StructurizeCFG.cpp}::StructurizeCFG::FlowSet</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 293 of file <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/scalar/structurizecfg-cpp">StructurizeCFG.cpp</a>.</p>

</div>
</div>

### Func {#a5c21a10fe692b7f4ebd62c6909006e24}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">Function* anonymous{StructurizeCFG.cpp}::StructurizeCFG::Func</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 285 of file <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/scalar/structurizecfg-cpp">StructurizeCFG.cpp</a>.</p>

</div>
</div>

### LoopConds {#a284483a62e3d131817da95467c2842a8}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">BranchVector anonymous{StructurizeCFG.cpp}::StructurizeCFG::LoopConds</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 304 of file <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/scalar/structurizecfg-cpp">StructurizeCFG.cpp</a>.</p>

</div>
</div>

### LoopPreds {#ad12f4d9c07fe18c51e3dff65e65a3aa5}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">PredMap anonymous{StructurizeCFG.cpp}::StructurizeCFG::LoopPreds</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 303 of file <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/scalar/structurizecfg-cpp">StructurizeCFG.cpp</a>.</p>

</div>
</div>

### Loops {#aeca8628b6b9131d35ad2642f7d8e8d85}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">BB2BBMap anonymous{StructurizeCFG.cpp}::StructurizeCFG::Loops</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 302 of file <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/scalar/structurizecfg-cpp">StructurizeCFG.cpp</a>.</p>

</div>
</div>

### Order {#a01f0b20d4d8147cb89ccc98305c1086e}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">SmallVector&lt;RegionNode *, 8&gt; anonymous{StructurizeCFG.cpp}::StructurizeCFG::Order</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 291 of file <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/scalar/structurizecfg-cpp">StructurizeCFG.cpp</a>.</p>

</div>
</div>

### ParentRegion {#a2c4ad44b0b1c80ef2147ffbe661e7a1b}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">Region* anonymous{StructurizeCFG.cpp}::StructurizeCFG::ParentRegion</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 286 of file <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/scalar/structurizecfg-cpp">StructurizeCFG.cpp</a>.</p>

</div>
</div>

### Predicates {#a1e874a729bde72d7ad1765303d3457ae}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">PredMap anonymous{StructurizeCFG.cpp}::StructurizeCFG::Predicates</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 299 of file <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/scalar/structurizecfg-cpp">StructurizeCFG.cpp</a>.</p>

</div>
</div>

### PrevNode {#a80dfc9f631eb73f21ae7d72d731f5b04}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">RegionNode* anonymous{StructurizeCFG.cpp}::StructurizeCFG::PrevNode</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 308 of file <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/scalar/structurizecfg-cpp">StructurizeCFG.cpp</a>.</p>

</div>
</div>

### TermDL {#aee47765f2b6471ca36aff60d8e98ccbf}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">BranchDebugLocMap anonymous{StructurizeCFG.cpp}::StructurizeCFG::TermDL</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 306 of file <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/scalar/structurizecfg-cpp">StructurizeCFG.cpp</a>.</p>

</div>
</div>

### UA {#a935e3206aa0b27a037fbfbd4d0ebb995}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">UniformityInfo* anonymous{StructurizeCFG.cpp}::StructurizeCFG::UA = nullptr</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 288 of file <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/scalar/structurizecfg-cpp">StructurizeCFG.cpp</a>.</p>

</div>
</div>

### Visited {#aac0ba3cd36810347423cf9bcf67c1135}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">BBSet anonymous{StructurizeCFG.cpp}::StructurizeCFG::Visited</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 292 of file <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/scalar/structurizecfg-cpp">StructurizeCFG.cpp</a>.</p>

</div>
</div>

</div>

<hr/>

The documentation for this class was generated from the following file:

<ul>
<li><a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/scalar/structurizecfg-cpp">StructurizeCFG.cpp</a></li>
</ul>

<hr/>

<p class="doxyGeneratedBy">Generated via <a href="https://github.com/xpack/doxygen2docusaurus">doxygen2docusaurus</a> by <a href="https://www.doxygen.nl">Doxygen</a> 1.14.0.</p>

</div>
