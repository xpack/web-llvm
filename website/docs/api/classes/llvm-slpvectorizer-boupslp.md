---

# DO NOT EDIT!
# Automatically generated via doxygen2docusaurus by Doxygen.

slug: /api/classes/llvm/slpvectorizer/boupslp
custom_edit_url: null
toc_max_heading_level: 4
keywords:
  - doxygen
  - reference
  - class

---

<div class="doxyPage">

# `BoUpSLP` Class

<p>Bottom Up SLP Vectorizer. <a href="#details">More...</a></p>

## Declaration

<div class="doxyDeclaration">
class llvm::slpvectorizer::BoUpSLP { ... }
</div>

## Public Member Typedefs Index

<table class="doxyMembersIndex">

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">using</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#acd60c5f9dd5f4fba7d7fd87f922d3dff">ValueList</a> = <a href="/web-llvm/docs/api/classes/llvm/smallvector">SmallVector</a>&lt; <a href="/web-llvm/docs/api/classes/llvm/value">Value</a> *, 8 &gt;</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">using</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a583379aade2a5a99809751051dbbb986">InstrList</a> = <a href="/web-llvm/docs/api/classes/llvm/smallvector">SmallVector</a>&lt; <a href="/web-llvm/docs/api/classes/llvm/instruction">Instruction</a> *, 16 &gt;</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">using</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a7d1ab05a47620f16e5d70d395b9541a0">ValueSet</a> = <a href="/web-llvm/docs/api/classes/llvm/smallptrset">SmallPtrSet</a>&lt; <a href="/web-llvm/docs/api/classes/llvm/value">Value</a> *, 16 &gt;</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">using</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a361126e112f3b523319d3cbc4bfc3814">StoreList</a> = <a href="/web-llvm/docs/api/classes/llvm/smallvector">SmallVector</a>&lt; <a href="/web-llvm/docs/api/classes/llvm/storeinst">StoreInst</a> *, 8 &gt;</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">using</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a8d0bc81039d5e2c5c855590d222c0fae">ExtraValueToDebugLocsMap</a> = <a href="/web-llvm/docs/api/classes/llvm/smalldenseset">SmallDenseSet</a>&lt; <a href="/web-llvm/docs/api/classes/llvm/value">Value</a> *, 4 &gt;</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">using</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a056d3cd46ef12f648e431fe9776451a1">OrdersType</a> = <a href="/web-llvm/docs/api/classes/llvm/smallvector">SmallVector</a>&lt; unsigned, 4 &gt;</td>
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

## Private Member Typedefs Index

<table class="doxyMembersIndex">

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">using</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a5319baf174815e75970f89ba7b04bbc2">ValueToGatherNodesMap</a> = <a href="/web-llvm/docs/api/classes/llvm/densemap">DenseMap</a>&lt; <a href="/web-llvm/docs/api/classes/llvm/value">Value</a> *, <a href="/web-llvm/docs/api/classes/llvm/smallptrset">SmallPtrSet</a>&lt; <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> TreeEntry *, 4 &gt; &gt;</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">using</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#adc30cafc2ad5556569c92eda7b8d1e29">UserList</a> = <a href="/web-llvm/docs/api/classes/llvm/smallvector">SmallVector</a>&lt; ExternalUser, 16 &gt;</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">using</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a3d2d659539432a9220d8a535771f232f">AliasCacheKey</a> = std::pair&lt; <a href="/web-llvm/docs/api/classes/llvm/instruction">Instruction</a> *, <a href="/web-llvm/docs/api/classes/llvm/instruction">Instruction</a> * &gt;</td>
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

## Enumerations Index

<table class="doxyMembersIndex">

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">enum class</td>
<td class="doxyMemberIndexItemName" align="left" valign="top">LoadsState { <a href="#a1897e235929f1961872707de9a400031">...</a> }</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Tracks the state we can represent the loads in the given sequence. <a href="#a1897e235929f1961872707de9a400031">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

</table>

## Friends Index

<table class="doxyMembersIndex">

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">struct</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a01ca80cf3ebaaf7a2923280b9ae1cfe8">GraphTraits&lt; BoUpSLP * &gt;</a></td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a00a020a143720f62cbf698f3da52aab8">DOTGraphTraits&lt; BoUpSLP * &gt;</a></td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/raw-ostream">raw_ostream</a> &amp;</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a1ad33e006f22925ac5a583abd6042512">operator&lt;&lt;</a></td>
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

## Public Constructors Index

<table class="doxyMembersIndex">

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a8f40b270f64be7a9b63bc9cfb3b2977a">BoUpSLP</a> (Function *Func, ScalarEvolution *Se, TargetTransformInfo *Tti, TargetLibraryInfo *TLi, AAResults *Aa, LoopInfo *Li, DominatorTree *Dt, AssumptionCache *AC, DemandedBits *DB, const DataLayout *DL, OptimizationRemarkEmitter *ORE)</td>
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

## Public Destructor Index

<table class="doxyMembersIndex">

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a3a4414a627935727a956fd992d951d41">~BoUpSLP</a> ()</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/value">Value</a> *</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#af30798297200e0134c0a54cfdfa6c6cd">vectorizeTree</a> ()</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Vectorize the tree that starts with the elements in <span class="doxyComputerOutput">VL</span>. <a href="#af30798297200e0134c0a54cfdfa6c6cd">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/value">Value</a> *</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a99b79343fdc586cce804ebabf3d419e2">vectorizeTree</a> (const ExtraValueToDebugLocsMap &amp;ExternallyUsedValues, Instruction *ReductionRoot=nullptr)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Vectorize the tree but with the list of externally used values <span class="doxyComputerOutput">ExternallyUsedValues</span>. <a href="#a99b79343fdc586cce804ebabf3d419e2">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/instructioncost">InstructionCost</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#aee3b49d7f15550d64c7db0e29a124c6d">getSpillCost</a> () const</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/instructioncost">InstructionCost</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a7800714c330f8f3952e8058b090e001b">getTreeCost</a> (ArrayRef&lt; Value * &gt; VectorizedVals={})</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ad022a5da5618f159f353f6faa4c902cb">buildTree</a> (ArrayRef&lt; Value * &gt; Roots, const SmallDenseSet&lt; Value * &gt; &amp;UserIgnoreLst)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Construct a vectorizable tree that starts at <span class="doxyComputerOutput">Roots</span>, ignoring users for the purpose of scheduling and extraction in the <span class="doxyComputerOutput">UserIgnoreLst</span>. <a href="#ad022a5da5618f159f353f6faa4c902cb">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">void</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a9a5d97b0aecbff971c950b2daae62509">buildTree</a> (ArrayRef&lt; Value * &gt; Roots)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Construct a vectorizable tree that starts at <span class="doxyComputerOutput">Roots</span>. <a href="#a9a5d97b0aecbff971c950b2daae62509">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">bool</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#abeef90aa6ca3783373fedb682df96b6e">doesRootHaveInTreeUses</a> () const</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Returns whether the root node has in-tree uses. <a href="#abeef90aa6ca3783373fedb682df96b6e">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/arrayref">ArrayRef</a>&lt; <a href="/web-llvm/docs/api/classes/llvm/value">Value</a> * &gt;</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a612d7463b1c5f28990f0f5e3593b7401">getRootNodeScalars</a> () const</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Return the scalars of the root node. <a href="#a612d7463b1c5f28990f0f5e3593b7401">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">std::optional&lt; std::pair&lt; <a href="/web-llvm/docs/api/classes/llvm/type">Type</a> *, bool &gt; &gt;</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a0b43ef7c72a8cb10a0cb09154a3b3b2d">getRootNodeTypeWithNoCast</a> () const</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Returns the type/is-signed info for the root node in the graph without casting. <a href="#a0b43ef7c72a8cb10a0cb09154a3b3b2d">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">bool</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a5c9be38d8bb16b6d645d2dfdb60f908d">isSignedMinBitwidthRootNode</a> () const</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Checks if the root graph node can be emitted with narrower bitwidth at codegen and returns it signedness, if so. <a href="#a5c9be38d8bb16b6d645d2dfdb60f908d">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/fixedvectortype">FixedVectorType</a> *</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#adac504434993ab1673128914746eef47">getReductionType</a> () const</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Returns reduction type after minbitdth analysis. <a href="#adac504434993ab1673128914746eef47">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">void</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a9a2e07f0b5ef19c59116913d4875a4e3">buildExternalUses</a> (const ExtraValueToDebugLocsMap &amp;ExternallyUsedValues={})</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Builds external uses of the vectorized scalars, i.e. <a href="#a9a2e07f0b5ef19c59116913d4875a4e3">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">void</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a91b0e07ff96232db2a91d6cfdf67a5e0">transformNodes</a> ()</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Transforms graph nodes to target specific representations, if profitable. <a href="#a91b0e07ff96232db2a91d6cfdf67a5e0">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">void</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a70aa6f9a0441a7a9449cb206bd77bad2">deleteTree</a> ()</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Clear the internal data structures that are created by 'buildTree'. <a href="#a70aa6f9a0441a7a9449cb206bd77bad2">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">unsigned</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a3a11daf8d89c135162dd6623f5bd164f">getTreeSize</a> () const</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">unsigned</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a45d4fa202493524e9b22c245f06ef855">getCanonicalGraphSize</a> () const</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Returns the base graph size, before any transformations. <a href="#a45d4fa202493524e9b22c245f06ef855">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">void</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#afd07d19c7174c06cd7c7415f63596839">optimizeGatherSequence</a> ()</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Perform LICM and CSE on the newly generated gather sequences. <a href="#afd07d19c7174c06cd7c7415f63596839">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">bool</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ae420d94473ac8cb96686184a551f6097">isIdentityOrder</a> (ArrayRef&lt; unsigned &gt; Order) const</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Does this non-empty order represent an identity order? <a href="#ae420d94473ac8cb96686184a551f6097">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">std::optional&lt; <a href="#a056d3cd46ef12f648e431fe9776451a1">OrdersType</a> &gt;</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#af8ac96c98d73833321b6d95a9c88b9d4">findReusedOrderedScalars</a> (const TreeEntry &amp;TE)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Checks if the specified gather tree entry <span class="doxyComputerOutput">TE</span> can be represented as a shuffled vector entry + (possibly) permutation with other gathers. <a href="#af8ac96c98d73833321b6d95a9c88b9d4">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">std::optional&lt; <a href="#a056d3cd46ef12f648e431fe9776451a1">OrdersType</a> &gt;</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a183245826b2f3e16c86e81e567db9b51">findPartiallyOrderedLoads</a> (const TreeEntry &amp;TE)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Sort loads into increasing pointers offsets to allow greater clustering. <a href="#a183245826b2f3e16c86e81e567db9b51">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">std::optional&lt; <a href="#a056d3cd46ef12f648e431fe9776451a1">OrdersType</a> &gt;</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ab2c5c3c0b3cd0db8b0692df8f66b6264">getReorderingData</a> (const TreeEntry &amp;TE, bool TopToBottom)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Gets reordering data for the given tree entry. <a href="#ab2c5c3c0b3cd0db8b0692df8f66b6264">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">void</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a1bc3cc02c0dc6dcb9ad315b7755475e7">reorderTopToBottom</a> ()</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Reorders the current graph to the most profitable order starting from the root node to the leaf nodes. <a href="#a1bc3cc02c0dc6dcb9ad315b7755475e7">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">void</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a2eb73a15ea2a5105bd2cec95863d7113">reorderBottomToTop</a> (bool IgnoreReorder=false)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Reorders the current graph to the most profitable order starting from leaves to the root. <a href="#a2eb73a15ea2a5105bd2cec95863d7113">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">unsigned</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a54f30c8bea3912d1d0f347626c395be6">getVectorElementSize</a> (Value *V)</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a7032e1ab44275cf7331a7898a3713aad">computeMinimumValueSizes</a> ()</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Compute the minimum type sizes required to represent the entries in a vectorizable tree. <a href="#a7032e1ab44275cf7331a7898a3713aad">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">unsigned</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#adc72e9ea7ec5e94d10e2a9a4fdaa3fc2">getMaxVecRegSize</a> () const</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">unsigned</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#aef776c88ca6591ad28a6f21f216f1ef7">getMinVecRegSize</a> () const</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">unsigned</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#aacc65a747c158a620f90f612a673a506">getMinVF</a> (unsigned Sz) const</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">unsigned</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a782cc6906561f01e563f30e50833235d">getMaximumVF</a> (unsigned ElemWidth, unsigned Opcode) const</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">unsigned</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#aac9cfeffe904936120849defcaa5afbc">canMapToVector</a> (Type *T) const</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p><a href="/web-llvm/docs/api/namespaces/llvm/check">Check</a> if homogeneous aggregate is isomorphic to some <a href="/web-llvm/docs/api/classes/llvm/vectortype">VectorType</a>. <a href="#aac9cfeffe904936120849defcaa5afbc">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">bool</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#aa054ca3a90996e96887be015cf288270">isTreeTinyAndNotFullyVectorizable</a> (bool ForReduction=false) const</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ad633712289394ee2c1d80b79432d11df">isTreeNotExtendable</a> () const</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Checks if the graph and all its subgraphs cannot be better vectorized. <a href="#ad633712289394ee2c1d80b79432d11df">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">bool</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a541f9da09ec4756f94ba8de97508ad80">isLoadCombineReductionCandidate</a> (RecurKind RdxKind) const</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Assume that a legal-sized 'or'-reduction of shifted/zexted loaded values can be load combined in the backend. <a href="#a541f9da09ec4756f94ba8de97508ad80">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">bool</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a49a7bbde7c622cc904ed4f8c1857cae6">isLoadCombineCandidate</a> (ArrayRef&lt; Value * &gt; Stores) const</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Assume that a vector of stores of bitwise-or/shifted/zexted loaded values can be load combined in the backend. <a href="#a49a7bbde7c622cc904ed4f8c1857cae6">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="#a1897e235929f1961872707de9a400031">LoadsState</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a496356f8335c794a9b365488ed263ead">canVectorizeLoads</a> (ArrayRef&lt; Value * &gt; VL, const Value *VL0, SmallVectorImpl&lt; unsigned &gt; &amp;Order, SmallVectorImpl&lt; Value * &gt; &amp;PointerOps, unsigned *BestVF=nullptr, bool TryRecursiveCheck=true) const</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Checks if the given array of loads can be represented as a vectorized, scatter or just simple gather. <a href="#a496356f8335c794a9b365488ed263ead">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexTemplate">
<td class="doxyMemberIndexTemplate" colspan="2"><div>template &lt;typename T&gt;</div></td>
</tr>
<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemTypeTemplate" align="left" valign="top">void</td>
<td class="doxyMemberIndexItemNameTemplate" align="left" valign="top"><a href="#a30c194a6bf543ebc57f18dd7840a1ecf">registerNonVectorizableLoads</a> (ArrayRef&lt; T * &gt; VL)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Registers non-vectorizable sequence of loads. <a href="#a30c194a6bf543ebc57f18dd7840a1ecf">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexTemplate">
<td class="doxyMemberIndexTemplate" colspan="2"><div>template &lt;typename T&gt;</div></td>
</tr>
<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemTypeTemplate" align="left" valign="top">bool</td>
<td class="doxyMemberIndexItemNameTemplate" align="left" valign="top"><a href="#a44ad06e18d7d3783f20435a9f159a763">areKnownNonVectorizableLoads</a> (ArrayRef&lt; T * &gt; VL) const</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Checks if the given loads sequence is known as not vectorizable. <a href="#a44ad06e18d7d3783f20435a9f159a763">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/optimizationremarkemitter">OptimizationRemarkEmitter</a> *</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ac8feff57671dce8f164846b3f0499bb5">getORE</a> ()</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">std::optional&lt; int &gt;</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#af3dd2dd5c72b919c173c6bc31d7c3ac3">findBestRootPair</a> (ArrayRef&lt; std::pair&lt; Value *, Value * &gt; &gt; Candidates, int Limit=LookAheadHeuristics::ScoreFail) const</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Evaluate each pair in <span class="doxyComputerOutput">Candidates</span> and return index into <span class="doxyComputerOutput">Candidates</span> for a pair which have highest score deemed to have best chance to form root of profitable tree to vectorize. <a href="#af3dd2dd5c72b919c173c6bc31d7c3ac3">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">bool</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a937e8e7cd2fb7c82d9512b69fc81b65b">isDeleted</a> (Instruction *I) const</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Checks if the instruction is marked for deletion. <a href="#a937e8e7cd2fb7c82d9512b69fc81b65b">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">void</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ab93aab6d000a610c36f69bb84137b2b8">eraseInstruction</a> (Instruction *I)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Removes an instruction from its block and eventually deletes it. <a href="#ab93aab6d000a610c36f69bb84137b2b8">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexTemplate">
<td class="doxyMemberIndexTemplate" colspan="2"><div>template &lt;typename T&gt;</div></td>
</tr>
<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemTypeTemplate" align="left" valign="top">void</td>
<td class="doxyMemberIndexItemNameTemplate" align="left" valign="top"><a href="#aa8ccbcf19b9150f2872f794ecdc53d3e">removeInstructionsAndOperands</a> (ArrayRef&lt; T * &gt; DeadVals)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Remove instructions from the parent function and clear the operands of <span class="doxyComputerOutput">DeadVals</span> instructions, marking for deletion trivially dead operands. <a href="#aa8ccbcf19b9150f2872f794ecdc53d3e">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">bool</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ab27b8e376a736c99b51c692c97a988fc">isAnalyzedReductionRoot</a> (Instruction *I) const</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Checks if the instruction was already analyzed for being possible reduction root. <a href="#ab27b8e376a736c99b51c692c97a988fc">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">void</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a5e8175cf734a1f96d3e5cda536407932">analyzedReductionRoot</a> (Instruction *I)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p><a href="/web-llvm/docs/api/classes/llvm/register">Register</a> given instruction as already analyzed for being possible reduction root. <a href="#a5e8175cf734a1f96d3e5cda536407932">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">bool</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a47fd84cb035443c529e17a54beae390f">areAnalyzedReductionVals</a> (ArrayRef&lt; Value * &gt; VL) const</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Checks if the provided list of reduced values was checked already for vectorization. <a href="#a47fd84cb035443c529e17a54beae390f">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">void</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a51b254a1b9cc02e8f8790cdd85b36a7f">analyzedReductionVals</a> (ArrayRef&lt; Value * &gt; VL)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Adds the list of reduced values to list of already checked values for the vectorization. <a href="#a51b254a1b9cc02e8f8790cdd85b36a7f">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">void</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#afaa748b2bfe8b9ddbd614dab3542411c">clearReductionData</a> ()</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Clear the list of the analyzed reduction root instructions. <a href="#afaa748b2bfe8b9ddbd614dab3542411c">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">bool</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#acc0cf2fab0dd3b42f500516296cb0bea">isAnyGathered</a> (const SmallDenseSet&lt; Value * &gt; &amp;Vals) const</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Checks if the given value is gathered in one of the nodes. <a href="#acc0cf2fab0dd3b42f500516296cb0bea">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">bool</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ae687ad0abfe8f68d8ca893dac9f1fa3a">isGathered</a> (const Value *V) const</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Checks if the given value is gathered in one of the nodes. <a href="#ae687ad0abfe8f68d8ca893dac9f1fa3a">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">bool</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a901abd1d0b7b05f2e37225606f095e7e">isNotScheduled</a> (const Value *V) const</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Checks if the specified value was not schedule. <a href="#a901abd1d0b7b05f2e37225606f095e7e">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">bool</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#adef9fad96a0d90c56a892520edbdb749">isVectorized</a> (Value *V) const</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p><a href="/web-llvm/docs/api/namespaces/llvm/check">Check</a> if the value is vectorized in the tree. <a href="#adef9fad96a0d90c56a892520edbdb749">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

</table>

## Private Member Functions Index

<table class="doxyMembersIndex">

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">bool</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a03b2575be4eac0913a5d94935a1728bb">collectValuesToDemote</a> (const TreeEntry &amp;E, bool IsProfitableToDemoteRoot, unsigned &amp;BitWidth, SmallVectorImpl&lt; unsigned &gt; &amp;ToDemote, DenseSet&lt; const TreeEntry * &gt; &amp;Visited, const SmallDenseSet&lt; unsigned, 8 &gt; &amp;NodesToKeepBWs, unsigned &amp;MaxDepthLevel, bool &amp;IsProfitableToDemote, bool IsTruncRoot) const</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Determine if a node <span class="doxyComputerOutput">E</span> in can be demoted to a smaller type with a truncation. <a href="#a03b2575be4eac0913a5d94935a1728bb">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">bool</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a9011f4a3aec07cbaa5c49e88399ea219">canReorderOperands</a> (TreeEntry *UserTE, SmallVectorImpl&lt; std::pair&lt; unsigned, TreeEntry * &gt; &gt; &amp;Edges, ArrayRef&lt; TreeEntry * &gt; ReorderableGathers, SmallVectorImpl&lt; TreeEntry * &gt; &amp;GatherOps)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p><a href="/web-llvm/docs/api/namespaces/llvm/check">Check</a> if the operands on the edges <span class="doxyComputerOutput">Edges</span> of the <span class="doxyComputerOutput">UserTE</span> allows reordering (i.e. <a href="#a9011f4a3aec07cbaa5c49e88399ea219">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">void</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a73a31d5bb7dcd22d8c81ee4a0169b142">reorderNodeWithReuses</a> (TreeEntry &amp;TE, ArrayRef&lt; int &gt; Mask) const</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Checks if the given <span class="doxyComputerOutput">TE</span> is a gather node with clustered reused scalars and reorders it per given <span class="doxyComputerOutput">Mask</span>. <a href="#a73a31d5bb7dcd22d8c81ee4a0169b142">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">TreeEntry *</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a082e45a1867ab3ea33d888c84ba6169c">getVectorizedOperand</a> (TreeEntry *UserTE, unsigned OpIdx)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Returns vectorized operand <span class="doxyComputerOutput">OpIdx</span> of the node <span class="doxyComputerOutput">UserTE</span> from the graph, if any. <a href="#a082e45a1867ab3ea33d888c84ba6169c">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> TreeEntry *</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#acf574bc8610c80c9059b61c1bd3b2b3d">getVectorizedOperand</a> (const TreeEntry *UserTE, unsigned OpIdx) const</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Returns vectorized operand <span class="doxyComputerOutput">OpIdx</span> of the node <span class="doxyComputerOutput">UserTE</span> from the graph, if any. <a href="#acf574bc8610c80c9059b61c1bd3b2b3d">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">bool</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a835c2380aa3fbc9ddeb4b919902e9838">areAllUsersVectorized</a> (Instruction *I, const SmallDenseSet&lt; Value * &gt; *VectorizedVals=nullptr) const</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Checks if all users of <span class="doxyComputerOutput">I</span> are the part of the vectorization tree. <a href="#a835c2380aa3fbc9ddeb4b919902e9838">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/structs/llvm/targettransforminfo/operandvalueinfo">TargetTransformInfo::OperandValueInfo</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#aafe4a9650de05d71c213add93b277db6">getOperandInfo</a> (ArrayRef&lt; Value * &gt; Ops)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Return information about the vector formed for the specified index of a vector of (the same) instruction. <a href="#aafe4a9650de05d71c213add93b277db6">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> TreeEntry *</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#aafe54b7b2bb2f0963b1f3fb48b23d075">getOperandEntry</a> (const TreeEntry *E, unsigned Idx) const</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>\ returns the graph entry for the <span class="doxyComputerOutput">Idx</span> operand of the <span class="doxyComputerOutput">E</span> entry. <a href="#aafe54b7b2bb2f0963b1f3fb48b23d075">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/instruction">Instruction</a> *</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#abc035709a419cdb3f324255cb01543f9">getRootEntryInstruction</a> (const TreeEntry &amp;Entry) const</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Gets the root instruction for the given node. <a href="#abc035709a419cdb3f324255cb01543f9">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/targettransforminfo/#af84cce349a77262269fd3f6756f37a64">TargetTransformInfo::CastContextHint</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#aa5214603d52de0ae6ac4cc2b0a001d81">getCastContextHint</a> (const TreeEntry &amp;TE) const</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/instructioncost">InstructionCost</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ad63e623a5637db5d71c45c9378a20138">getEntryCost</a> (const TreeEntry *E, ArrayRef&lt; Value * &gt; VectorizedVals, SmallPtrSetImpl&lt; Value * &gt; &amp;CheckedExtracts)</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a66f4bb98d9a5c179ff1e0e827713a120">buildTree_rec</a> (ArrayRef&lt; Value * &gt; Roots, unsigned Depth, const EdgeInfo &amp;EI, unsigned InterleaveFactor=0)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>This is the recursive part of buildTree. <a href="#a66f4bb98d9a5c179ff1e0e827713a120">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">bool</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ad442d7323a88e9bbb875e109448bf172">canReuseExtract</a> (ArrayRef&lt; Value * &gt; VL, SmallVectorImpl&lt; unsigned &gt; &amp;CurrentOrder, bool ResizeAllowed=false) const</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#adfafa535e8cc90f46f85c3b1423d6d67">vectorizeTree</a> (TreeEntry *E, bool PostponedPHIs)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Vectorize a single entry in the tree. <a href="#adfafa535e8cc90f46f85c3b1423d6d67">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">TreeEntry *</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a165c20e5f3127b4b43922eee3282050b">getMatchedVectorizedOperand</a> (const TreeEntry *E, unsigned NodeIdx)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Returns vectorized operand node, that matches the order of the scalars operand number <span class="doxyComputerOutput">NodeIdx</span> in entry <span class="doxyComputerOutput">E</span>. <a href="#a165c20e5f3127b4b43922eee3282050b">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> TreeEntry *</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a493d808fb43d8683f8d9429864f926c6">getMatchedVectorizedOperand</a> (const TreeEntry *E, unsigned NodeIdx) const</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#afab0ce28b491c2faba682ac8ae5396f5">vectorizeOperand</a> (TreeEntry *E, unsigned NodeIdx, bool PostponedPHIs)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Vectorize a single entry in the tree, the <span class="doxyComputerOutput">Idx-th</span> operand of the entry <span class="doxyComputerOutput">E</span>. <a href="#afab0ce28b491c2faba682ac8ae5396f5">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexTemplate">
<td class="doxyMemberIndexTemplate" colspan="2"><div>template &lt;typename BVTy, typename ResTy, typename... Args&gt;</div></td>
</tr>
<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemTypeTemplate" align="left" valign="top">ResTy</td>
<td class="doxyMemberIndexItemNameTemplate" align="left" valign="top"><a href="#acfe91867a2060578464be38b6977deaf">processBuildVector</a> (const TreeEntry *E, Type *ScalarTy, Args &amp;...Params)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Create a new vector from a list of scalar values. <a href="#acfe91867a2060578464be38b6977deaf">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/value">Value</a> *</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a7190a8565c844f810d43ed05d7ad6573">createBuildVector</a> (const TreeEntry *E, Type *ScalarTy, bool PostponedPHIs)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Create a new vector from a list of scalar values. <a href="#a7190a8565c844f810d43ed05d7ad6573">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/instruction">Instruction</a> &amp;</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ab7562b6e17ceb56fa8731af2117bf261">getLastInstructionInBundle</a> (const TreeEntry *E)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Returns the instruction in the bundle, which can be used as a base point for scheduling. <a href="#ab7562b6e17ceb56fa8731af2117bf261">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">std::optional&lt; <a href="/web-llvm/docs/api/classes/llvm/targettransforminfo/#af46433d0e36d3f80afc3a8c67b5c53ec">TargetTransformInfo::ShuffleKind</a> &gt;</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a19ef6f06ba0112253a3a767a28504aed">tryToGatherSingleRegisterExtractElements</a> (MutableArrayRef&lt; Value * &gt; VL, SmallVectorImpl&lt; int &gt; &amp;Mask) const</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Tries to find extractelement instructions with constant indices from fixed vector type and gather such instructions into a bunch, which highly likely might be detected as a shuffle of 1 or 2 input vectors. <a href="#a19ef6f06ba0112253a3a767a28504aed">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/smallvector">SmallVector</a>&lt; std::optional&lt; <a href="/web-llvm/docs/api/classes/llvm/targettransforminfo/#af46433d0e36d3f80afc3a8c67b5c53ec">TargetTransformInfo::ShuffleKind</a> &gt; &gt;</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a43820a91e3d701ddc34b2d72e0a65269">tryToGatherExtractElements</a> (SmallVectorImpl&lt; Value * &gt; &amp;VL, SmallVectorImpl&lt; int &gt; &amp;Mask, unsigned NumParts) const</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Tries to find extractelement instructions with constant indices from fixed vector type and gather such instructions into a bunch, which highly likely might be detected as a shuffle of 1 or 2 input vectors. <a href="#a43820a91e3d701ddc34b2d72e0a65269">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">std::optional&lt; <a href="/web-llvm/docs/api/classes/llvm/targettransforminfo/#af46433d0e36d3f80afc3a8c67b5c53ec">TargetTransformInfo::ShuffleKind</a> &gt;</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a6469daa232d7c7587d1256860e4a85cf">isGatherShuffledSingleRegisterEntry</a> (const TreeEntry *TE, ArrayRef&lt; Value * &gt; VL, MutableArrayRef&lt; int &gt; Mask, SmallVectorImpl&lt; const TreeEntry * &gt; &amp;Entries, unsigned Part, bool ForOrder)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Checks if the gathered <span class="doxyComputerOutput">VL</span> can be represented as a single register shuffle(s) of previous tree entries. <a href="#a6469daa232d7c7587d1256860e4a85cf">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/smallvector">SmallVector</a>&lt; std::optional&lt; <a href="/web-llvm/docs/api/classes/llvm/targettransforminfo/#af46433d0e36d3f80afc3a8c67b5c53ec">TargetTransformInfo::ShuffleKind</a> &gt; &gt;</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ab9bad2e690f2b2621c7632ff50a6852c">isGatherShuffledEntry</a> (const TreeEntry *TE, ArrayRef&lt; Value * &gt; VL, SmallVectorImpl&lt; int &gt; &amp;Mask, SmallVectorImpl&lt; SmallVector&lt; const TreeEntry * &gt; &gt; &amp;Entries, unsigned NumParts, bool ForOrder=false)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Checks if the gathered <span class="doxyComputerOutput">VL</span> can be represented as multi-register shuffle(s) of previous tree entries. <a href="#ab9bad2e690f2b2621c7632ff50a6852c">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/instructioncost">InstructionCost</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#acadcc40e851da294bfda85d1ea8e351c">getGatherCost</a> (ArrayRef&lt; Value * &gt; VL, bool ForPoisonSrc, Type *ScalarTy) const</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a61c5bdc9bb16637acfd0771792633153">setInsertPointAfterBundle</a> (const TreeEntry *E)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Set the Builder insert point to one after the last instruction in the bundle. <a href="#a61c5bdc9bb16637acfd0771792633153">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/value">Value</a> *</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ad85f77b2e5e94d0be46613351b0c6765">gather</a> (ArrayRef&lt; Value * &gt; VL, Value *Root, Type *ScalarTy, function_ref&lt; Value *(Value *, Value *, ArrayRef&lt; int &gt;)&gt; CreateShuffle)</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#aa82698e1e0686f629237d59e8ed8f944">isFullyVectorizableTinyTree</a> (bool ForReduction) const</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ace69c2cae8c7e231ac95bb7fc6816f1b">tryToVectorizeGatheredLoads</a> (const SmallMapVector&lt; std::tuple&lt; BasicBlock *, Value *, Type * &gt;, SmallVector&lt; SmallVector&lt; std::pair&lt; LoadInst *, int &gt; &gt; &gt;, 8 &gt; &amp;GatheredLoads)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Run through the list of all gathered loads in the graph and try to find vector loads/masked gathers instead of regular gathers. <a href="#ace69c2cae8c7e231ac95bb7fc6816f1b">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/smallvector">SmallVector</a>&lt; <a href="/web-llvm/docs/api/classes/llvm/smallvector">SmallVector</a>&lt; <a href="/web-llvm/docs/api/classes/llvm/storeinst">StoreInst</a> * &gt; &gt;</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ad078900b5c7804535baf9e40fda2881b">collectUserStores</a> (const BoUpSLP::TreeEntry *TE) const</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Helper for <span class="doxyComputerOutput">findExternalStoreUsersReorderIndices()</span>. <a href="#ad078900b5c7804535baf9e40fda2881b">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">bool</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#af11846ed705c63e33dfb2f214298bb0d">canFormVector</a> (ArrayRef&lt; StoreInst * &gt; StoresVec, OrdersType &amp;ReorderIndices) const</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Helper for <span class="doxyComputerOutput">findExternalStoreUsersReorderIndices()</span>. <a href="#af11846ed705c63e33dfb2f214298bb0d">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/smallvector">SmallVector</a>&lt; <a href="#a056d3cd46ef12f648e431fe9776451a1">OrdersType</a>, 1 &gt;</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a3561aceaf1691c808ab34d1609bcda8f">findExternalStoreUsersReorderIndices</a> (TreeEntry *TE) const</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Iterates through the users of <span class="doxyComputerOutput">TE</span>, looking for scalar stores that can be potentially vectorized in a future SLP-tree. <a href="#a3561aceaf1691c808ab34d1609bcda8f">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">void</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a75dec9db92f17ee8d74a398331c9bd5c">reorderGatherNode</a> (TreeEntry &amp;TE)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Tries to reorder the gathering node for better vectorization opportunities. <a href="#a75dec9db92f17ee8d74a398331c9bd5c">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">void</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a90a5dba433e854f5ada067fbab531dc6">dumpTreeCosts</a> (const TreeEntry *E, InstructionCost ReuseShuffleCost, InstructionCost VecCost, InstructionCost ScalarCost, StringRef Banner) const</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">TreeEntry *</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a8be06c3d1de5aefe60a9a8ec98bb216b">newTreeEntry</a> (ArrayRef&lt; Value * &gt; VL, std::optional&lt; ScheduleData * &gt; Bundle, const InstructionsState &amp;S, const EdgeInfo &amp;UserTreeIdx, ArrayRef&lt; int &gt; ReuseShuffleIndices={}, ArrayRef&lt; unsigned &gt; ReorderIndices={}, unsigned InterleaveFactor=0)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Create a new VectorizableTree entry. <a href="#a8be06c3d1de5aefe60a9a8ec98bb216b">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">TreeEntry *</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#aa028f2760a292569ae42e9219ed5af68">newTreeEntry</a> (ArrayRef&lt; Value * &gt; VL, TreeEntry::EntryState EntryState, std::optional&lt; ScheduleData * &gt; Bundle, const InstructionsState &amp;S, const EdgeInfo &amp;UserTreeIdx, ArrayRef&lt; int &gt; ReuseShuffleIndices={}, ArrayRef&lt; unsigned &gt; ReorderIndices={})</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/support/compiler-h/#aa863693eef567397d9c292da5bf22d34">LLVM_DUMP_METHOD</a> void</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a088274764ebab0b22a089cd9948e7d5b">dumpVectorizableTree</a> () const</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Debug printer. <a href="#a088274764ebab0b22a089cd9948e7d5b">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">TreeEntry *</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#abe7ba4656a84c9e5fb10267137ad335d">getTreeEntry</a> (Value *V)</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> TreeEntry *</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a45bc71b7cb7fdca2c0f70dff121664d3">getTreeEntry</a> (Value *V) const</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a91b5e45f639db019ee95a7dda7997920">areAltOperandsProfitable</a> (const InstructionsState &amp;S, ArrayRef&lt; Value * &gt; VL) const</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p><a href="/web-llvm/docs/api/namespaces/llvm/check">Check</a> that the operand node of alternate node does not generate buildvector sequence. <a href="#a91b5e45f639db019ee95a7dda7997920">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">TreeEntry::EntryState</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a43bc83ca6b3d717c12d9d5fcfc301998">getScalarsVectorizationState</a> (const InstructionsState &amp;S, ArrayRef&lt; Value * &gt; VL, bool IsScatterVectorizeUserTE, OrdersType &amp;CurrentOrder, SmallVectorImpl&lt; Value * &gt; &amp;PointerOps)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Checks if the specified list of the instructions/values can be vectorized and fills required data before actual scheduling of the instructions. <a href="#a43bc83ca6b3d717c12d9d5fcfc301998">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">bool</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a948082ce2f3a54a7f5c2f9c3336fccab">isAliased</a> (const MemoryLocation &amp;Loc1, Instruction *Inst1, Instruction *Inst2)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Checks if two instructions may access the same memory. <a href="#a948082ce2f3a54a7f5c2f9c3336fccab">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">void</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ac844a9ffc7b47fb80f3411c7ca6d9957">scheduleBlock</a> (BlockScheduling *BS)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Performs the "real" scheduling. <a href="#ac844a9ffc7b47fb80f3411c7ca6d9957">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

</table>

## Private Member Attributes Index

<table class="doxyMembersIndex">

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/smallvector">TreeEntry::VecTreeTy</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a7795c2fb3606392450da583eccfe2455">VectorizableTree</a></td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>– Vectorization State – Holds all of the tree entries. <a href="#a7795c2fb3606392450da583eccfe2455">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/smalldensemap">SmallDenseMap</a>&lt; <a href="/web-llvm/docs/api/classes/llvm/value">Value</a> *, TreeEntry * &gt;</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a0d459fe5dd29a392f49dd710d2f2c71b">ScalarToTreeEntry</a></td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Maps a specific scalar to its tree entry. <a href="#a0d459fe5dd29a392f49dd710d2f2c71b">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/smalldensemap">SmallDenseMap</a>&lt; <a href="/web-llvm/docs/api/classes/llvm/value">Value</a> *, <a href="/web-llvm/docs/api/classes/llvm/smallvector">SmallVector</a>&lt; TreeEntry * &gt; &gt;</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a0426828efa639b0c95cee44ecccc3398">MultiNodeScalars</a></td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>List of scalars, used in several vectorize nodes, and the list of the nodes. <a href="#a0426828efa639b0c95cee44ecccc3398">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/smalldensemap">SmallDenseMap</a>&lt; <a href="/web-llvm/docs/api/classes/llvm/value">Value</a> *, unsigned &gt;</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#aac428d1f1b708780715566924bb373c4">InstrElementSize</a></td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Maps a value to the proposed vectorizable size. <a href="#aac428d1f1b708780715566924bb373c4">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="#a7d1ab05a47620f16e5d70d395b9541a0">ValueSet</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a880b231f9052bd991c88bd1805d9ab62">MustGather</a></td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>A list of scalars that we found that we need to keep as scalars. <a href="#a880b231f9052bd991c88bd1805d9ab62">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="#a7d1ab05a47620f16e5d70d395b9541a0">ValueSet</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#aa48f882b8196ab0a8c5dec13ef77323d">NonScheduledFirst</a></td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>A set of first non-schedulable values. <a href="#aa48f882b8196ab0a8c5dec13ef77323d">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/densemap">DenseMap</a>&lt; <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> TreeEntry *, <a href="/web-llvm/docs/api/classes/llvm/instruction">Instruction</a> * &gt;</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ac2ec502416f5f101b36b509650ffb823">EntryToLastInstruction</a></td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>A map between the vectorized entries and the last instructions in the bundles. <a href="#ac2ec502416f5f101b36b509650ffb823">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/setvector">SetVector</a>&lt; <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> TreeEntry * &gt;</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a7a9dcf5bc2ba583e66567329dbfd1396">PostponedGathers</a></td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>List of gather nodes, depending on other gather/vector nodes, which should be emitted after the vector instruction emission process to correctly handle order of the vector instructions and shuffles. <a href="#a7a9dcf5bc2ba583e66567329dbfd1396">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/densemap">ValueToGatherNodesMap</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a6a07db700982ba8691a9c0439cd99b37">ValueToGatherNodes</a></td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/setvector">SetVector</a>&lt; unsigned &gt;</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a5b0954b60b8951313eefe78a2b147111">LoadEntriesToVectorize</a></td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>A list of the load entries (node indices), which can be vectorized using strided or masked gather approach, but attempted to be represented as contiguous loads. <a href="#a5b0954b60b8951313eefe78a2b147111">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">bool</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#afd3f8ca47800c55be221192689c8f7f4">IsGraphTransformMode</a> = false</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>true if graph nodes transforming mode is on. <a href="#afd3f8ca47800c55be221192689c8f7f4">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">std::optional&lt; unsigned &gt;</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a17c313765367cc79f5a76a3488cbd347">GatheredLoadsEntriesFirst</a></td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>The index of the first gathered load entry in the VectorizeTree. <a href="#a17c313765367cc79f5a76a3488cbd347">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/densemap">DenseMap</a>&lt; AliasCacheKey, bool &gt;</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a772e8ab1fc9c813525acf20b463c2044">AliasCache</a></td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Cache for alias results. <a href="#a772e8ab1fc9c813525acf20b463c2044">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/batchaaresults">BatchAAResults</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a277f844b254e2586007a5e8d8e379152">BatchAA</a></td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/denseset">DenseSet</a>&lt; <a href="/web-llvm/docs/api/classes/llvm/instruction">Instruction</a> * &gt;</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ac45648ffb65206927ce3f2074c3648b1">DeletedInstructions</a></td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Temporary store for deleted instructions. <a href="#ac45648ffb65206927ce3f2074c3648b1">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/smallptrset">SmallPtrSet</a>&lt; <a href="/web-llvm/docs/api/classes/llvm/instruction">Instruction</a> *, 16 &gt;</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ab8cb7770321ee9ce399b8c21ddae0b13">AnalyzedReductionsRoots</a></td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Set of the instruction, being analyzed already for reductions. <a href="#ab8cb7770321ee9ce399b8c21ddae0b13">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/denseset">DenseSet</a>&lt; size_t &gt;</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a65cc1a338cc136eb98e1287053986ef6">AnalyzedReductionVals</a></td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Set of hashes for the list of reduction values already being analyzed. <a href="#a65cc1a338cc136eb98e1287053986ef6">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/denseset">DenseSet</a>&lt; <a href="/web-llvm/docs/api/classes/llvm/value">Value</a> * &gt;</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ad24c04ce97610b8eb2f2a5d94e270c35">AnalyzedMinBWVals</a></td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Values, already been analyzed for mininmal bitwidth and found to be non-profitable. <a href="#ad24c04ce97610b8eb2f2a5d94e270c35">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/smallvector">UserList</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ac3e8695ea354c51527226b28948e055d">ExternalUses</a></td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>A list of values that need to extracted out of the tree. <a href="#ac3e8695ea354c51527226b28948e055d">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/smallptrset">SmallPtrSet</a>&lt; <a href="/web-llvm/docs/api/classes/llvm/value">Value</a> *, 4 &gt;</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a4c5eb71c0ee34534905b0ab6951d8dc4">ExternalUsesAsOriginalScalar</a></td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>A list of GEPs which can be reaplced by scalar GEPs instead of extractelement instructions. <a href="#a4c5eb71c0ee34534905b0ab6951d8dc4">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/smallptrset">SmallPtrSet</a>&lt; <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/value">Value</a> *, 32 &gt;</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a504a10433dad784129b4adf2fd3cb5d1">EphValues</a></td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Values used only by @llvm.assume calls. <a href="#a504a10433dad784129b4adf2fd3cb5d1">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/setvector">SetVector</a>&lt; <a href="/web-llvm/docs/api/classes/llvm/instruction">Instruction</a> * &gt;</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ae5b0c4e328eddea9cb8ddf84745ab391">GatherShuffleExtractSeq</a></td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Holds all of the instructions that we gathered, shuffle instructions and extractelements. <a href="#ae5b0c4e328eddea9cb8ddf84745ab391">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/denseset">DenseSet</a>&lt; <a href="/web-llvm/docs/api/classes/llvm/basicblock">BasicBlock</a> * &gt;</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ab57fdc3e32cc0ae8d6eb1fbaed3c77d0">CSEBlocks</a></td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>A list of blocks that we are going to CSE. <a href="#ab57fdc3e32cc0ae8d6eb1fbaed3c77d0">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/denseset">DenseSet</a>&lt; size_t &gt;</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ab93d7484ebdc203459a0bab5096a6e4e">ListOfKnonwnNonVectorizableLoads</a></td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>List of hashes of vector of loads, which are known to be non vectorizable. <a href="#ab93d7484ebdc203459a0bab5096a6e4e">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/mapvector">MapVector</a>&lt; <a href="/web-llvm/docs/api/classes/llvm/basicblock">BasicBlock</a> *, std::unique_ptr&lt; BlockScheduling &gt; &gt;</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a3f26a32453e8c86c84e186f2b27ac6eb">BlocksSchedules</a></td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Attaches the BlockScheduling structures to basic blocks. <a href="#a3f26a32453e8c86c84e186f2b27ac6eb">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/smalldenseset">SmallDenseSet</a>&lt; <a href="/web-llvm/docs/api/classes/llvm/value">Value</a> * &gt; *</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#abc56ef7b38f2fd4baed872ee29265ec8">UserIgnoreList</a> = nullptr</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>List of users to ignore during scheduling and that don't need extracting. <a href="#abc56ef7b38f2fd4baed872ee29265ec8">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/function">Function</a> *</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a96a28a1ec7e0f3568694ec52481add5b">F</a></td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/scalarevolution">ScalarEvolution</a> *</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a9f477ff68bc3e29ed2b26a8b9d072634">SE</a></td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/targettransforminfo">TargetTransformInfo</a> *</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ae5d74b8a6753eb90229afe818e3807aa">TTI</a></td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/targetlibraryinfo">TargetLibraryInfo</a> *</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#af6ffb2e92d674db7068b73c46d532c5b">TLI</a></td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/loopinfo">LoopInfo</a> *</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a25696ba9845aa178a6b3cdd70e86df35">LI</a></td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a94eb5749199afa148e48ecffe2f0b606">DT</a></td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/assumptioncache">AssumptionCache</a> *</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a5f8905cef85ca000a578442fd6965b4a">AC</a></td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/demandedbits">DemandedBits</a> *</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ae42fdd4f837a80b393a3b65d6e779226">DB</a></td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/datalayout">DataLayout</a> *</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a2ab2dc46997fa0aaa5c501588e35b095">DL</a></td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/optimizationremarkemitter">OptimizationRemarkEmitter</a> *</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a4900c0a59fd5c667796582d309fb5fc4">ORE</a></td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">unsigned</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#aa1a6e405b6b9407ae9ab78f1519b5617">MaxVecRegSize</a></td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">unsigned</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a9cb0c966edf73d76b32a5ec0fc9d33eb">MinVecRegSize</a></td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/irbuilder">IRBuilder</a>&lt; <a href="/web-llvm/docs/api/classes/llvm/targetfolder">TargetFolder</a> &gt;</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ab33f29aab2441e8e1cfcb837a856bafd">Builder</a></td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p><a href="/web-llvm/docs/api/classes/llvm/instruction">Instruction</a> builder to construct the vectorized tree. <a href="#ab33f29aab2441e8e1cfcb837a856bafd">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/densemap">DenseMap</a>&lt; <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> TreeEntry *, std::pair&lt; uint64_t, bool &gt; &gt;</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a7ace999cc9764c8972092693622137ed">MinBWs</a></td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>A map of scalar integer values to the smallest bit width with which they can legally be represented. <a href="#a7ace999cc9764c8972092693622137ed">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">unsigned</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ac8c4611dde12401c1a83394bc6e0f0d0">ReductionBitWidth</a> = 0</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Final size of the reduced vector, if the current graph represents the input for the reduction and it was possible to narrow the size of the reduction. <a href="#ac8c4611dde12401c1a83394bc6e0f0d0">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">unsigned</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a2e1826a912fcf88df608a66edfcd148a">BaseGraphSize</a> = 1</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Canonical graph size before the transformations. <a href="#a2e1826a912fcf88df608a66edfcd148a">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">std::optional&lt; std::pair&lt; unsigned, unsigned &gt; &gt;</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#aaf3c6ddeb70c587a6c6306c1edd7bafd">CastMaxMinBWSizes</a></td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>If the tree contains any zext/sext/trunc nodes, contains max-min pair of type sizes, used in the tree. <a href="#aaf3c6ddeb70c587a6c6306c1edd7bafd">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/denseset">DenseSet</a>&lt; unsigned &gt;</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a48fbdd3082f1a4ac3926ea985676fe9a">ExtraBitWidthNodes</a></td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Indices of the vectorized nodes, which supposed to be the roots of the new bitwidth analysis attempt, like trunc, IToFP or ICmp. <a href="#a48fbdd3082f1a4ac3926ea985676fe9a">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

</table>

## Description {#details}

<p>Bottom Up SLP Vectorizer.</p>

<p>Definition at line 1336 of file <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/vectorize/slpvectorizer-cpp">SLPVectorizer.cpp</a>.</p>


<div class="doxySectionDef">

## Public Member Typedefs

### ExtraValueToDebugLocsMap {#a8d0bc81039d5e2c5c855590d222c0fae}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">using llvm::slpvectorizer::BoUpSLP::ExtraValueToDebugLocsMap =  SmallDenseSet&lt;Value *, 4&gt;</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 1355 of file <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/vectorize/slpvectorizer-cpp">SLPVectorizer.cpp</a>.</p>

</div>
</div>

### InstrList {#a583379aade2a5a99809751051dbbb986}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">using llvm::slpvectorizer::BoUpSLP::InstrList =  SmallVector&lt;Instruction *, 16&gt;</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 1352 of file <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/vectorize/slpvectorizer-cpp">SLPVectorizer.cpp</a>.</p>

</div>
</div>

### OrdersType {#a056d3cd46ef12f648e431fe9776451a1}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">using llvm::slpvectorizer::BoUpSLP::OrdersType =  SmallVector&lt;unsigned, 4&gt;</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 1356 of file <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/vectorize/slpvectorizer-cpp">SLPVectorizer.cpp</a>.</p>

</div>
</div>

### StoreList {#a361126e112f3b523319d3cbc4bfc3814}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">using llvm::slpvectorizer::BoUpSLP::StoreList =  SmallVector&lt;StoreInst *, 8&gt;</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 1354 of file <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/vectorize/slpvectorizer-cpp">SLPVectorizer.cpp</a>.</p>

</div>
</div>

### ValueList {#acd60c5f9dd5f4fba7d7fd87f922d3dff}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">using llvm::slpvectorizer::BoUpSLP::ValueList =  SmallVector&lt;Value *, 8&gt;</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 1351 of file <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/vectorize/slpvectorizer-cpp">SLPVectorizer.cpp</a>.</p>

</div>
</div>

### ValueSet {#a7d1ab05a47620f16e5d70d395b9541a0}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">using llvm::slpvectorizer::BoUpSLP::ValueSet =  SmallPtrSet&lt;Value *, 16&gt;</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 1353 of file <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/vectorize/slpvectorizer-cpp">SLPVectorizer.cpp</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Private Member Typedefs

### AliasCacheKey {#a3d2d659539432a9220d8a535771f232f}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">using llvm::slpvectorizer::BoUpSLP::AliasCacheKey =  std::pair&lt;Instruction *, Instruction *&gt;</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 3835 of file <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/vectorize/slpvectorizer-cpp">SLPVectorizer.cpp</a>.</p>

</div>
</div>

### UserList {#adc30cafc2ad5556569c92eda7b8d1e29}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">using llvm::slpvectorizer::BoUpSLP::UserList =  SmallVector&lt;ExternalUser, 16&gt;</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 3813 of file <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/vectorize/slpvectorizer-cpp">SLPVectorizer.cpp</a>.</p>

</div>
</div>

### ValueToGatherNodesMap {#a5319baf174815e75970f89ba7b04bbc2}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">using llvm::slpvectorizer::BoUpSLP::ValueToGatherNodesMap = 
      DenseMap&lt;Value *, SmallPtrSet&lt;const TreeEntry *, 4&gt;&gt;</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 3784 of file <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/vectorize/slpvectorizer-cpp">SLPVectorizer.cpp</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Enumerations

### LoadsState {#a1897e235929f1961872707de9a400031}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">enum class llvm::slpvectorizer::BoUpSLP::LoadsState </td>
</tr>
</table>
</td>
<td class="doxyMemberLabelsRight">
<span class="doxyMemberLabels">
<span class="doxyMemberLabel strong">strong</span>
</span>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Tracks the state we can represent the loads in the given sequence.</p>

<dl class="doxyEnumList">
<dt class="doxyEnumTableTitle">Enumeration values</dt>
<dd>
<table class="doxyEnumTable">

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">Gather<a id="a1897e235929f1961872707de9a400031aad22c799930d644e8468fe44c0312d53"></a></td>
<td class="doxyEnumItemDescription"></td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">Vectorize<a id="a1897e235929f1961872707de9a400031ab8c3ff4276089f60a1f1820acc67bf60"></a></td>
<td class="doxyEnumItemDescription"></td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">ScatterVectorize<a id="a1897e235929f1961872707de9a400031a705aab2193971a020dd6e9b6bfc0a160"></a></td>
<td class="doxyEnumItemDescription"></td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">StridedVectorize<a id="a1897e235929f1961872707de9a400031ac1873549f5ed932486f6b91a280e118e"></a></td>
<td class="doxyEnumItemDescription"></td>
</tr>

</table>
</dd>
</dl>

<p>Definition at line 1344 of file <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/vectorize/slpvectorizer-cpp">SLPVectorizer.cpp</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Friends

### DOTGraphTraits&lt; BoUpSLP \* &gt; {#a00a020a143720f62cbf698f3da52aab8}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">friend struct <a href="/web-llvm/docs/api/structs/llvm/dotgraphtraits">DOTGraphTraits</a>&lt; <a href="/web-llvm/docs/api/classes/llvm/slpvectorizer/boupslp">BoUpSLP</a> * &gt;</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">


<p>Definition at line 4062 of file <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/vectorize/slpvectorizer-cpp">SLPVectorizer.cpp</a>.</p>

</div>
</div>

### GraphTraits&lt; BoUpSLP \* &gt; {#a01ca80cf3ebaaf7a2923280b9ae1cfe8}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">friend struct <a href="/web-llvm/docs/api/structs/llvm/graphtraits">GraphTraits</a>&lt; <a href="/web-llvm/docs/api/classes/llvm/slpvectorizer/boupslp">BoUpSLP</a> * &gt;</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">


<p>Definition at line 4062 of file <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/vectorize/slpvectorizer-cpp">SLPVectorizer.cpp</a>.</p>

</div>
</div>

### operator&lt;&lt; {#a1ad33e006f22925ac5a583abd6042512}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">friend <a href="/web-llvm/docs/api/classes/llvm/raw-ostream">raw_ostream</a> &amp; <a href="/web-llvm/docs/api/classes/llvm/raw-ostream">raw_ostream</a> &amp; os, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> BoUpSLP::ScheduleData &amp; SD</td>
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


<p>Definition at line 4062 of file <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/vectorize/slpvectorizer-cpp">SLPVectorizer.cpp</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Public Constructors

### BoUpSLP() {#a8f40b270f64be7a9b63bc9cfb3b2977a}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">llvm::slpvectorizer::BoUpSLP::BoUpSLP (<a href="/web-llvm/docs/api/classes/llvm/function">Function</a> * Func, <a href="/web-llvm/docs/api/classes/llvm/scalarevolution">ScalarEvolution</a> * Se, <a href="/web-llvm/docs/api/classes/llvm/targettransforminfo">TargetTransformInfo</a> * Tti, <a href="/web-llvm/docs/api/classes/llvm/targetlibraryinfo">TargetLibraryInfo</a> * TLi, <a href="/web-llvm/docs/api/classes/llvm/aaresults">AAResults</a> * Aa, <a href="/web-llvm/docs/api/classes/llvm/loopinfo">LoopInfo</a> * Li, <a href="/web-llvm/docs/api/classes/llvm/dominatortree">DominatorTree</a> * Dt, <a href="/web-llvm/docs/api/classes/llvm/assumptioncache">AssumptionCache</a> * AC, <a href="/web-llvm/docs/api/classes/llvm/demandedbits">DemandedBits</a> * DB, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/datalayout">DataLayout</a> * DL, <a href="/web-llvm/docs/api/classes/llvm/optimizationremarkemitter">OptimizationRemarkEmitter</a> * ORE)</td>
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



<p>Definition at line 1358 of file <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/vectorize/slpvectorizer-cpp">SLPVectorizer.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/structs/llvm/codemetrics/#a7e174506b52ad46ea1f746a7f727d999">llvm::CodeMetrics::collectEphemeralValues</a>, <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/vectorize/slpvectorizer-cpp/#a1ca809da394247bba762653f861875a1">MaxVectorRegSizeOption</a>, <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/vectorize/slpvectorizer-cpp/#ad4b62196a6175779b466b2e8f0e5cc12">MinVectorRegSizeOption</a> and <a href="/web-llvm/docs/api/classes/llvm/targettransforminfo/#a8bb3b1ccf19b8c85429b777dfa4a0166a183020fbea95c99db23f6d3594f4c4af">llvm::TargetTransformInfo::RGK_FixedWidthVector</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/classes/llvm/slpvectorizer/boupslp/lookaheadheuristics/#a8e14accdaa3da86f319cd54a73cf7e79">llvm::slpvectorizer::BoUpSLP::LookAheadHeuristics::LookAheadHeuristics</a>, <a href="/web-llvm/docs/api/classes/boupslp/shufflecostestimator/#a01132bd1988568a34c781bcc4631f6bd">llvm::slpvectorizer::BoUpSLP::ShuffleCostEstimator::ShuffleCostEstimator</a>, <a href="/web-llvm/docs/api/classes/boupslp/shuffleinstructionbuilder/#ab191e4dcc36fced04070c777d9787496">llvm::slpvectorizer::BoUpSLP::ShuffleInstructionBuilder::ShuffleInstructionBuilder</a> and <a href="/web-llvm/docs/api/classes/llvm/slpvectorizer/boupslp/vloperands/#a3c3378c4b4191797dc4125fc8d2b4029">llvm::slpvectorizer::BoUpSLP::VLOperands::VLOperands</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Public Destructor

### \~BoUpSLP() {#a3a4414a627935727a956fd992d951d41}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">BoUpSLP::~BoUpSLP ()</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 2966 of file <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/vectorize/slpvectorizer-cpp">SLPVectorizer.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/silowercontrolflow-cpp/#a4868c5d81c5ccc98c47aeab6244346a0">assert</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a7c46c742c31be54870e2038048e6b391">llvm::dbgs</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a22eeee01734061ac1b31ccd994c49eef">llvm::dyn_cast</a>, <a href="/web-llvm/docs/api/classes/llvm/smallvectorimpl/#a396fcfee6914c76974b73c3d203da6a5">llvm::SmallVectorImpl&lt; T &gt;::emplace_back</a>, <a href="/web-llvm/docs/api/files/lib/lib/support/md5-cpp/#ac0eafdc9ee161b71e7af98af736952fd">I</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a92ca992e52dddc420f4b069cae06dfbe">llvm::isa</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a1106b8a15061e8494873e10bb8a364e5">llvm::RecursivelyDeleteTriviallyDeadInstructions</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a26389c546573f058ad8ecbdc5c1933cf">llvm::verifyFunction</a> and <a href="/web-llvm/docs/api/namespaces/llvm/#a845142f96a84f067cb6bf639e37980d0">llvm::wouldInstructionBeTriviallyDead</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Public Member Functions

### analyzedReductionRoot() {#a5e8175cf734a1f96d3e5cda536407932}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void llvm::slpvectorizer::BoUpSLP::analyzedReductionRoot (<a href="/web-llvm/docs/api/classes/llvm/instruction">Instruction</a> * I)</td>
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

<p><a href="/web-llvm/docs/api/classes/llvm/register">Register</a> given instruction as already analyzed for being possible reduction root.</p>

<p>Definition at line 2931 of file <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/vectorize/slpvectorizer-cpp">SLPVectorizer.cpp</a>.</p>


<p>Reference <a href="/web-llvm/docs/api/files/lib/lib/support/md5-cpp/#ac0eafdc9ee161b71e7af98af736952fd">I</a>.</p>

</div>
</div>

### analyzedReductionVals() {#a51b254a1b9cc02e8f8790cdd85b36a7f}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void llvm::slpvectorizer::BoUpSLP::analyzedReductionVals (<a href="/web-llvm/docs/api/classes/llvm/arrayref">ArrayRef</a>&lt; <a href="/web-llvm/docs/api/classes/llvm/value">Value</a> * &gt; VL)</td>
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

<p>Adds the list of reduced values to list of already checked values for the vectorization.</p>

<p>Definition at line 2941 of file <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/vectorize/slpvectorizer-cpp">SLPVectorizer.cpp</a>.</p>


<p>Reference <a href="/web-llvm/docs/api/namespaces/llvm/#a0e2e479cf4860dc8a00614e36ee3d5e9">llvm::hash_value</a>.</p>


<p>Referenced by <a href="#a91b0e07ff96232db2a91d6cfdf67a5e0">transformNodes</a>.</p>

</div>
</div>

### areAnalyzedReductionVals() {#a47fd84cb035443c529e17a54beae390f}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool llvm::slpvectorizer::BoUpSLP::areAnalyzedReductionVals (<a href="/web-llvm/docs/api/classes/llvm/arrayref">ArrayRef</a>&lt; <a href="/web-llvm/docs/api/classes/llvm/value">Value</a> * &gt; VL)</td>
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

<p>Checks if the provided list of reduced values was checked already for vectorization.</p>

<p>Definition at line 2936 of file <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/vectorize/slpvectorizer-cpp">SLPVectorizer.cpp</a>.</p>


<p>Reference <a href="/web-llvm/docs/api/namespaces/llvm/#a0e2e479cf4860dc8a00614e36ee3d5e9">llvm::hash_value</a>.</p>

</div>
</div>

### areKnownNonVectorizableLoads() {#a44ad06e18d7d3783f20435a9f159a763}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<div class="doxyMemberTemplate">template &lt;typename T&gt;</div>
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool llvm::slpvectorizer::BoUpSLP::areKnownNonVectorizableLoads (<a href="/web-llvm/docs/api/classes/llvm/arrayref">ArrayRef</a>&lt; T * &gt; VL)</td>
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

<p>Checks if the given loads sequence is known as not vectorizable.</p>

<p>Definition at line 1650 of file <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/vectorize/slpvectorizer-cpp">SLPVectorizer.cpp</a>.</p>


<p>Reference <a href="/web-llvm/docs/api/namespaces/llvm/#a0e2e479cf4860dc8a00614e36ee3d5e9">llvm::hash_value</a>.</p>


<p>Referenced by <a href="#a496356f8335c794a9b365488ed263ead">canVectorizeLoads</a> and <a href="#a91b0e07ff96232db2a91d6cfdf67a5e0">transformNodes</a>.</p>

</div>
</div>

### buildExternalUses() {#a9a2e07f0b5ef19c59116913d4875a4e3}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void BoUpSLP::buildExternalUses (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="#a8d0bc81039d5e2c5c855590d222c0fae">ExtraValueToDebugLocsMap</a> &amp; ExternallyUsedValues={})</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Builds external uses of the vectorized scalars, i.e.</p>


<p>the list of vectorized scalars to be extracted, their lanes and their scalar users. <span class="doxyComputerOutput">ExternallyUsedValues</span> contains additional list of external uses to handle vectorization of reductions.</p>


<p>Definition at line 1471 of file <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/vectorize/slpvectorizer-cpp">SLPVectorizer.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/silowercontrolflow-cpp/#a4868c5d81c5ccc98c47aeab6244346a0">assert</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a7c46c742c31be54870e2038048e6b391">llvm::dbgs</a>, <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/vectorize/slpvectorizer-cpp/#a596e8b6e6b71f454b18f982f947e5e03">doesInTreeUserNeedToExtract</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a22eeee01734061ac1b31ccd994c49eef">llvm::dyn_cast</a>, <a href="/web-llvm/docs/api/classes/llvm/densemapbase/#a65520b9c67759099e313d0f4e7b5ff9e">llvm::DenseMapBase&lt; DerivedT, KeyT, ValueT, KeyInfoT, BucketT &gt;::end</a>, <a href="/web-llvm/docs/api/classes/llvm/detail/densesetimpl/#a8cd802dcaed35e1f28ea3cbe4af4eff5">llvm::detail::DenseSetImpl&lt; ValueT, MapTy, ValueInfoT &gt;::end</a>, <a href="/web-llvm/docs/api/classes/llvm/densemapbase/#a0c047f127ed4380a6f383d70bec4eb94">llvm::DenseMapBase&lt; DerivedT, KeyT, ValueT, KeyInfoT, BucketT &gt;::find</a>, <a href="/web-llvm/docs/api/classes/llvm/detail/densesetimpl/#a56034ec173ce8feff8568c0e29462094">llvm::detail::DenseSetImpl&lt; ValueT, MapTy, ValueInfoT &gt;::find</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a92ca992e52dddc420f4b069cae06dfbe">llvm::isa</a>, <a href="#a937e8e7cd2fb7c82d9512b69fc81b65b">isDeleted</a>, <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/support/debug-h/#a196897517069dda1bdb549e24468f7d7">LLVM_DEBUG</a>, <a href="/web-llvm/docs/api/classes/llvm/densemapbase/#a1a245b31aced1374f28f45d2b297f402">llvm::DenseMapBase&lt; DerivedT, KeyT, ValueT, KeyInfoT, BucketT &gt;::try_emplace</a> and <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/vectorize/slpvectorizer-cpp/#a75df5de932994d1472ad3cda6a88cf21">UsesLimit</a>.</p>

</div>
</div>

### buildTree() {#ad022a5da5618f159f353f6faa4c902cb}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void BoUpSLP::buildTree (<a href="/web-llvm/docs/api/classes/llvm/arrayref">ArrayRef</a>&lt; <a href="/web-llvm/docs/api/classes/llvm/value">Value</a> * &gt; Roots, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/smalldenseset">SmallDenseSet</a>&lt; <a href="/web-llvm/docs/api/classes/llvm/value">Value</a> * &gt; &amp; UserIgnoreLst)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Construct a vectorizable tree that starts at <span class="doxyComputerOutput">Roots</span>, ignoring users for the purpose of scheduling and extraction in the <span class="doxyComputerOutput">UserIgnoreLst</span>.</p>

<p>Definition at line 1406 of file <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/vectorize/slpvectorizer-cpp">SLPVectorizer.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/vectorize/slpvectorizer-cpp/#aabfbce373feafd33ca9e104d8b164ece">allSameType</a> and <a href="#a70aa6f9a0441a7a9449cb206bd77bad2">deleteTree</a>.</p>

</div>
</div>

### buildTree() {#a9a5d97b0aecbff971c950b2daae62509}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void BoUpSLP::buildTree (<a href="/web-llvm/docs/api/classes/llvm/arrayref">ArrayRef</a>&lt; <a href="/web-llvm/docs/api/classes/llvm/value">Value</a> * &gt; Roots)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Construct a vectorizable tree that starts at <span class="doxyComputerOutput">Roots</span>.</p>

<p>Definition at line 1410 of file <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/vectorize/slpvectorizer-cpp">SLPVectorizer.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/vectorize/slpvectorizer-cpp/#aabfbce373feafd33ca9e104d8b164ece">allSameType</a> and <a href="#a70aa6f9a0441a7a9449cb206bd77bad2">deleteTree</a>.</p>

</div>
</div>

### canMapToVector() {#aac9cfeffe904936120849defcaa5afbc}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">unsigned BoUpSLP::canMapToVector (<a href="/web-llvm/docs/api/classes/llvm/type">Type</a> * T)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p><a href="/web-llvm/docs/api/namespaces/llvm/check">Check</a> if homogeneous aggregate is isomorphic to some <a href="/web-llvm/docs/api/classes/llvm/vectortype">VectorType</a>.</p>


<p>Accepts homogeneous multidimensional aggregate of scalars/vectors like {[4 x i16], [4 x i16]}, { &lt;2 x float&gt;, &lt;2 x float&gt; }, {{{i16, i16}, {i16, i16}}, {{i16, i16}, {i16, i16}}} and so on.</p>


<dl class="doxySectionUser">
<dt>Returns</dt>
<dd><p>number of elements in vector if isomorphism exists, 0 otherwise.</p></dd>
</dl>


<p>Definition at line 1597 of file <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/vectorize/slpvectorizer-cpp">SLPVectorizer.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/namespaces/llvm/#ac4fc845f5ed92de63cd4474f128f5fc5">llvm::cast</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a22eeee01734061ac1b31ccd994c49eef">llvm::dyn_cast</a>, <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/vectorize/slpvectorizer-cpp/#a065bd87e0b855701cd8ca61aa05d4c50">getWidenedType</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a92ca992e52dddc420f4b069cae06dfbe">llvm::isa</a>, <a href="/web-llvm/docs/api/classes/llvm/type/#a0f5c23d3b941362c2fa195f4c0b99683">llvm::Type::isEmptyTy</a>, <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/vectorize/slpvectorizer-cpp/#aa3ea54a95743867473d32853d3c65603">isValidElementType</a>, <a href="/web-llvm/docs/api/files/lib/lib/support/regcomp-c/#a0240ac851181b84ac374872dc5434ee4">N</a> and <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/mips/mips16isellowering-cpp/#a0acb682b8260ab1c60b918599864e2e5">T</a>.</p>

</div>
</div>

### canVectorizeLoads() {#a496356f8335c794a9b365488ed263ead}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">BoUpSLP::LoadsState BoUpSLP::canVectorizeLoads (<a href="/web-llvm/docs/api/classes/llvm/arrayref">ArrayRef</a>&lt; <a href="/web-llvm/docs/api/classes/llvm/value">Value</a> * &gt; VL, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/value">Value</a> * VL0, <a href="/web-llvm/docs/api/classes/llvm/smallvectorimpl">SmallVectorImpl</a>&lt; unsigned &gt; &amp; Order, <a href="/web-llvm/docs/api/classes/llvm/smallvectorimpl">SmallVectorImpl</a>&lt; <a href="/web-llvm/docs/api/classes/llvm/value">Value</a> * &gt; &amp; PointerOps, unsigned * BestVF=nullptr, bool TryRecursiveCheck=<a href="/web-llvm/docs/api/files/lib/lib/analysis/basicaliasanalysis-cpp/#af6d5cafbdfc5313e65d990120021a3ec">true</a>)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Checks if the given array of loads can be represented as a vectorized, scatter or just simple gather.</p>


<dl class="doxyParamsList">
<dt class="doxyParamsTableTitle">Parameters</dt>
<dd>
<table class="doxyParamsTable">
<tr class="doxyParamItem">
<td class="doxyParamItemName">VL</td>
<td class="doxyParamItemDescription"><p>list of loads.</p></td>
</tr>
<tr class="doxyParamItem">
<td class="doxyParamItemName">VL0</td>
<td class="doxyParamItemDescription"><p>main load value.</p></td>
</tr>
<tr class="doxyParamItem">
<td class="doxyParamItemName">Order</td>
<td class="doxyParamItemDescription"><p>returned order of load instructions.</p></td>
</tr>
<tr class="doxyParamItem">
<td class="doxyParamItemName">PointerOps</td>
<td class="doxyParamItemDescription"><p>returned list of pointer operands.</p></td>
</tr>
<tr class="doxyParamItem">
<td class="doxyParamItemName">BestVF</td>
<td class="doxyParamItemDescription"><p>return best vector factor, if recursive check found better vectorization sequences rather than masked gather.</p></td>
</tr>
<tr class="doxyParamItem">
<td class="doxyParamItemName">TryRecursiveCheck</td>
<td class="doxyParamItemDescription"><p>used to check if long masked gather can be represented as a serie of loads/insert subvector, if profitable.</p></td>
</tr>
</table>
</dd>
</dl>

<p>Definition at line 1637 of file <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/vectorize/slpvectorizer-cpp">SLPVectorizer.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/namespaces/llvm/#a0d10fe510ced2849a8074fe81e5d04ce">llvm::all_of</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a61d13d6824ec46c31260a4fd0997eda0">llvm::any_of</a>, <a href="#a44ad06e18d7d3783f20435a9f159a763">areKnownNonVectorizableLoads</a>, <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/vectorize/slpvectorizer-cpp/#abf8c65a150fe96c228db5b19d6b09e3a">arePointersCompatible</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#ab9c6b351507d3c0730f4290919d43a12">llvm::ArrayRef</a>, <a href="/web-llvm/docs/api/classes/llvm/smallvectortemplatecommon/#acd9e771a3296c6b24146955754620557">llvm::SmallVectorTemplateCommon&lt; T, typename &gt;::back</a>, <a href="/web-llvm/docs/api/classes/llvm/arrayref/#aab36927882fbfdcbb860d87fd9c30da8">llvm::ArrayRef&lt; T &gt;::begin</a>, <a href="/web-llvm/docs/api/classes/llvm/smallvectortemplatecommon/#a8a045d250952c0867382a9840ee18fdf">llvm::SmallVectorTemplateCommon&lt; T, typename &gt;::begin</a>, <a href="/web-llvm/docs/api/namespaces/llvm/callingconv/#ac6aa1387c4375260e2468eb5a77fdb4cafd841a49aec1539bc88abc8ff9e170fb">llvm::CallingConv::C</a>, <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/vectorize/slpvectorizer-cpp/#a0a8a72a5038e4a261d35418751506868">calculateRtStride</a>, <a href="#a496356f8335c794a9b365488ed263ead">canVectorizeLoads</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#ac4fc845f5ed92de63cd4474f128f5fc5">llvm::cast</a>, <a href="/web-llvm/docs/api/classes/llvm/smallvectorimpl/#aac0ea55010b7b1a301e65a0baea057aa">llvm::SmallVectorImpl&lt; T &gt;::clear</a>, <a href="/web-llvm/docs/api/classes/llvm/apint/#a781bd5c20864a9c185018258af774ace">llvm::APInt::clearAllBits</a>, <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/vectorize/slpvectorizer-cpp/#ae06eb06e1d6ba6b5e8d319eef5d16280">computeCommonAlignment</a>, <a href="/web-llvm/docs/api/files/lib/lib/analysis/costmodel-cpp/#a162d8b2b3865594d1e14d828d2b8336a">CostKind</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#ac214df91cdc242f4710ea5a93939c678">llvm::count_if</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a05a7412bf10f2226fb69f2876b76e9cd">llvm::doesNotNeedToBeScheduled</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a22eeee01734061ac1b31ccd994c49eef">llvm::dyn_cast</a>, <a href="/web-llvm/docs/api/classes/llvm/smallvectortemplatecommon/#ad9a3c7bc26b130377bbafc170b5f88a2">llvm::SmallVectorTemplateCommon&lt; T, typename &gt;::empty</a>, <a href="/web-llvm/docs/api/classes/llvm/arrayref/#a7ca5197533a9c1fb8a2bd30587fcec6b">llvm::ArrayRef&lt; T &gt;::end</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a206e2134ddd2312c3488d0632d98f554">llvm::enumerate</a>, <a href="/web-llvm/docs/api/classes/llvm/arrayref/#a721fc555cb3d8dc2a1a680dcc2ce69b2">llvm::ArrayRef&lt; T &gt;::front</a>, <a href="/web-llvm/docs/api/classes/llvm/smallvectortemplatecommon/#a58dc840fc84420b7f0b773794b8101c1">llvm::SmallVectorTemplateCommon&lt; T, typename &gt;::front</a>, <a href="#a1897e235929f1961872707de9a400031aad22c799930d644e8468fe44c0312d53">Gather</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/hexagon/hexagoncommongep-cpp/#ad532e8710e50302e0a376b61c91fa91d">GEP</a>, <a href="/web-llvm/docs/api/classes/llvm/apint/#a071e8d814b2b30b02544fad964227b8e">llvm::APInt::getAllOnes</a>, <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/vectorize/slpvectorizer-cpp/#abd93b259f88f77258d2428448d9f8032">getFloorFullVectorNumberOfElements</a>, <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/vectorize/slpvectorizer-cpp/#ac10dff634cacc4be44046af5ee45f92a">getGEPCosts</a>, <a href="#aacc65a747c158a620f90f612a673a506">getMinVF</a>, <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/vectorize/slpvectorizer-cpp/#a2f1d58ac35de4475017aca6c5bda6d44">getNumElements</a>, <a href="/web-llvm/docs/api/classes/llvm/apint/#aec662ee6ab1490a4cabebf2812e5b9ca">llvm::APInt::getOneBitSet</a>, <a href="/web-llvm/docs/api/files/lib/lib/analysis/basicaliasanalysis-cpp/#a1b8850f1ed44c12bc3501175a71c251c">getParent</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a54b19432f9c7d4df0f2f2307175f73e4">llvm::getPointerOperand</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a034d66b8c0aeb72ea13fd26392083446">llvm::getPointersDiff</a>, <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/vectorize/slpvectorizer-cpp/#a3c4c7b26972597220296eab6450669b0">getShuffleCost</a>, <a href="/web-llvm/docs/api/classes/llvm/value/#a0344a49526443edf90cc0aef3abd3337">llvm::Value::getType</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a3b1c5788b85ffa254be0e834edf5cf8f">llvm::getUnderlyingObject</a>, <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/vectorize/slpvectorizer-cpp/#a065bd87e0b855701cd8ca61aa05d4c50">getWidenedType</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a617c1c04cfa1325ad04eb69339d92188">llvm::has_single_bit</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a7d6443d726d7d8cdb827119e6f8f7819">llvm::hasFullVectorsOrPowerOf2</a>, <a href="/web-llvm/docs/api/files/lib/lib/support/md5-cpp/#ac0eafdc9ee161b71e7af98af736952fd">I</a>, <a href="/web-llvm/docs/api/classes/llvm/smallset/#afcadfef2cf37c3e6dbdbc9cd7bea50a0">llvm::SmallSet&lt; T, N, C &gt;::insert</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a92ca992e52dddc420f4b069cae06dfbe">llvm::isa</a>, <a href="/web-llvm/docs/api/classes/llvm/apint/#a423e2c491de1408d54e35f0b47d076be">llvm::APInt::isAllOnes</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a445c0cf40cd4a28c8b53579dfab9a193">llvm::IsaPred</a>, <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/vectorize/slpvectorizer-cpp/#afa640d51b943ce0396e7131bf2352f8a">isReverseOrder</a>, <a href="/web-llvm/docs/api/classes/llvm/apint/#a49cd5939942c6665aba4cae8c220dff1">llvm::APInt::isZero</a>, <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/vectorize/slpvectorizer-cpp/#a1ffea6d979c6f85d480c0f4187207058">MaxProfitableLoadStride</a>, <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/vectorize/slpvectorizer-cpp/#a3d9350d9f87e91559fd54f4e66190255">MinProfitableStridedLoads</a>, <a href="/web-llvm/docs/api/files/lib/lib/option/option-cpp/#a04665169063c8ca1f2ea96c27fc7c2b2">P</a>, <a href="/web-llvm/docs/api/files/lib/lib/analysis/targetlibraryinfo-cpp/#aca185e6d0e9f423dbb24440206454872a11dbf501abf829b3ab7049c2d3a8a053">Ptr</a>, <a href="/web-llvm/docs/api/classes/llvm/smallvectortemplatebase/#af42bfbc067df27c19ee2fc859df58799">llvm::SmallVectorTemplateBase&lt; T, bool &gt;::push_back</a>, <a href="/web-llvm/docs/api/classes/llvm/smallvectorimpl/#ad0b3d8447f88377b62d9c019f3c4e118">llvm::SmallVectorImpl&lt; T &gt;::resize</a>, <a href="#a1897e235929f1961872707de9a400031a705aab2193971a020dd6e9b6bfc0a160">ScatterVectorize</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#adc4eb8be6f7a12ede962987fb9cabb47">llvm::seq</a>, <a href="/web-llvm/docs/api/classes/llvm/apint/#ab6fff8a97bcb55e50e9be0ecf0c99b63">llvm::APInt::setAllBits</a>, <a href="/web-llvm/docs/api/classes/llvm/apint/#acb95d5d8e87df053e1b53e2ec60de4b6">llvm::APInt::setBits</a>, <a href="/web-llvm/docs/api/classes/llvm/arrayref/#a85ffb6531d4cda988ea81f18d4e56fb7">llvm::ArrayRef&lt; T &gt;::size</a>, <a href="/web-llvm/docs/api/classes/llvm/smallset/#afd7c135e18f2d7253d4f8545cd7b1756">llvm::SmallSet&lt; T, N, C &gt;::size</a>, <a href="/web-llvm/docs/api/classes/llvm/smallvectortemplatecommon/#a1c479a8c434377c2b8cb056bdfdfc201">llvm::SmallVectorTemplateCommon&lt; T, typename &gt;::size</a>, <a href="/web-llvm/docs/api/classes/llvm/targettransforminfo/#af46433d0e36d3f80afc3a8c67b5c53ecab1ac8982cdb119f39a5fe74610a46796">llvm::TargetTransformInfo::SK_Broadcast</a>, <a href="/web-llvm/docs/api/classes/llvm/targettransforminfo/#af46433d0e36d3f80afc3a8c67b5c53eca466a4d581cf3a553414b9c2e889b944a">llvm::TargetTransformInfo::SK_InsertSubvector</a>, <a href="/web-llvm/docs/api/classes/llvm/arrayref/#aebf6ca7590d4f766b894044015a0fa31">llvm::ArrayRef&lt; T &gt;::slice</a>, <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/vectorize/slpvectorizer-cpp/#a704fbec676f53c0e32a778dcd57d21d9">SLPCostThreshold</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a8d9d7c33311a38eae588e12caf8985ce">llvm::sortPtrAccesses</a>, <a href="#a1897e235929f1961872707de9a400031ac1873549f5ed932486f6b91a280e118e">StridedVectorize</a>, <a href="/web-llvm/docs/api/classes/llvm/targettransforminfo/#a706f223f760b55668fbae74202b816bba59b32ea7b6f10564abd40ad90602ca5b">llvm::TargetTransformInfo::TCK_RecipThroughput</a> and <a href="#a1897e235929f1961872707de9a400031ab8c3ff4276089f60a1f1820acc67bf60">Vectorize</a>.</p>


<p>Referenced by <a href="#a496356f8335c794a9b365488ed263ead">canVectorizeLoads</a>, <a href="#ab2c5c3c0b3cd0db8b0692df8f66b6264">getReorderingData</a> and <a href="#a91b0e07ff96232db2a91d6cfdf67a5e0">transformNodes</a>.</p>

</div>
</div>

### clearReductionData() {#afaa748b2bfe8b9ddbd614dab3542411c}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void llvm::slpvectorizer::BoUpSLP::clearReductionData ()</td>
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

<p>Clear the list of the analyzed reduction root instructions.</p>

<p>Definition at line 2945 of file <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/vectorize/slpvectorizer-cpp">SLPVectorizer.cpp</a>.</p>

</div>
</div>

### computeMinimumValueSizes() {#a7032e1ab44275cf7331a7898a3713aad}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void BoUpSLP::computeMinimumValueSizes ()</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Compute the minimum type sizes required to represent the entries in a vectorizable tree.</p>

<p>Definition at line 1569 of file <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/vectorize/slpvectorizer-cpp">SLPVectorizer.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/namespaces/llvm/#a0d10fe510ced2849a8074fe81e5d04ce">llvm::all_of</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a61d13d6824ec46c31260a4fd0997eda0">llvm::any_of</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/silowercontrolflow-cpp/#a4868c5d81c5ccc98c47aeab6244346a0">assert</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a4cc11b26432f9343b3c532f06171ad04">llvm::bit_ceil</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#ac4fc845f5ed92de63cd4474f128f5fc5">llvm::cast</a>, <a href="/web-llvm/docs/api/classes/llvm/smallvectorimpl/#aac0ea55010b7b1a301e65a0baea057aa">llvm::SmallVectorImpl&lt; T &gt;::clear</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#ad46ed333b920b20e78d948610366254c">llvm::ComputeNumSignBits</a>, <a href="/web-llvm/docs/api/classes/llvm/detail/densesetimpl/#ad409c2de8502b94c8a0b1193307c63b6">llvm::detail::DenseSetImpl&lt; ValueT, MapTy, ValueInfoT &gt;::contains</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a22eeee01734061ac1b31ccd994c49eef">llvm::dyn_cast</a>, <a href="/web-llvm/docs/api/classes/llvm/integertype/#a14f7b4f1aed38192fb6b7772eb506bdb">llvm::IntegerType::get</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#ac2e6c50683f73779b6b83effaf07ca30">llvm::getNumberOfParts</a>, <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/vectorize/slpvectorizer-cpp/#a2f1d58ac35de4475017aca6c5bda6d44">getNumElements</a>, <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/vectorize/vplanslp-cpp/#a06b4f19004df11b338ccc7e73bf47ab4">getOpcode</a>, <a href="/web-llvm/docs/api/classes/llvm/type/#a7c742b32ebcd73d6dc851afac295b0f2">llvm::Type::getScalarType</a>, <a href="/web-llvm/docs/api/classes/llvm/value/#a0344a49526443edf90cc0aef3abd3337">llvm::Value::getType</a>, <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/vectorize/slpvectorizer-cpp/#a065bd87e0b855701cd8ca61aa05d4c50">getWidenedType</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a92ca992e52dddc420f4b069cae06dfbe">llvm::isa</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a523d5dedb074ebe223d5cf61142bc313">llvm::isGather</a>, <a href="/web-llvm/docs/api/classes/llvm/smallvectortemplatebase/#af42bfbc067df27c19ee2fc859df58799">llvm::SmallVectorTemplateBase&lt; T, bool &gt;::push_back</a> and <a href="/web-llvm/docs/api/structs/llvm/slpvectorizer/boupslp/edgeinfo/#ac3d3c4a713b6bbd7165cd4b872252b79">llvm::slpvectorizer::BoUpSLP::EdgeInfo::UserTE</a>.</p>

</div>
</div>

### deleteTree() {#a70aa6f9a0441a7a9449cb206bd77bad2}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void llvm::slpvectorizer::BoUpSLP::deleteTree ()</td>
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

<p>Clear the internal data structures that are created by 'buildTree'.</p>

<p>Definition at line 1477 of file <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/vectorize/slpvectorizer-cpp">SLPVectorizer.cpp</a>.</p>


<p>Referenced by <a href="#a9a5d97b0aecbff971c950b2daae62509">buildTree</a> and <a href="#ad022a5da5618f159f353f6faa4c902cb">buildTree</a>.</p>

</div>
</div>

### doesRootHaveInTreeUses() {#abeef90aa6ca3783373fedb682df96b6e}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool llvm::slpvectorizer::BoUpSLP::doesRootHaveInTreeUses ()</td>
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

<p>Returns whether the root node has in-tree uses.</p>

<p>Definition at line 1413 of file <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/vectorize/slpvectorizer-cpp">SLPVectorizer.cpp</a>.</p>

</div>
</div>

### eraseInstruction() {#ab93aab6d000a610c36f69bb84137b2b8}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void llvm::slpvectorizer::BoUpSLP::eraseInstruction (<a href="/web-llvm/docs/api/classes/llvm/instruction">Instruction</a> * I)</td>
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

<p>Removes an instruction from its block and eventually deletes it.</p>


<p>It's like <a href="/web-llvm/docs/api/classes/llvm/instruction/#a601ee49a4c4e0babf29bd1cf09036570">Instruction::eraseFromParent()</a> except that the actual deletion is delayed until <a href="/web-llvm/docs/api/classes/llvm/slpvectorizer/boupslp">BoUpSLP</a> is destructed.</p>


<p>Definition at line 2835 of file <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/vectorize/slpvectorizer-cpp">SLPVectorizer.cpp</a>.</p>


<p>Reference <a href="/web-llvm/docs/api/files/lib/lib/support/md5-cpp/#ac0eafdc9ee161b71e7af98af736952fd">I</a>.</p>


<p>Referenced by <a href="#afd07d19c7174c06cd7c7415f63596839">optimizeGatherSequence</a> and <a href="#a99b79343fdc586cce804ebabf3d419e2">vectorizeTree</a>.</p>

</div>
</div>

### findBestRootPair() {#af3dd2dd5c72b919c173c6bc31d7c3ac3}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">std::optional&lt; int &gt; llvm::slpvectorizer::BoUpSLP::findBestRootPair (<a href="/web-llvm/docs/api/classes/llvm/arrayref">ArrayRef</a>&lt; std::pair&lt; <a href="/web-llvm/docs/api/classes/llvm/value">Value</a> *, <a href="/web-llvm/docs/api/classes/llvm/value">Value</a> * &gt; &gt; Candidates, int Limit=<a href="/web-llvm/docs/api/classes/llvm/slpvectorizer/boupslp/lookaheadheuristics/#a653c21908b15629b676161353d43d719">LookAheadHeuristics::ScoreFail</a>)</td>
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

<p>Evaluate each pair in <span class="doxyComputerOutput">Candidates</span> and return index into <span class="doxyComputerOutput">Candidates</span> for a pair which have highest score deemed to have best chance to form root of profitable tree to vectorize.</p>


<p>Return std::nullopt if no candidate scored above the <a href="/web-llvm/docs/api/classes/llvm/slpvectorizer/boupslp/lookaheadheuristics/#a653c21908b15629b676161353d43d719">LookAheadHeuristics::ScoreFail</a>.</p>


<dl class="doxyParamsList">
<dt class="doxyParamsTableTitle">Parameters</dt>
<dd>
<table class="doxyParamsTable">
<tr class="doxyParamItem">
<td class="doxyParamItemName">Limit</td>
<td class="doxyParamItemDescription"><p>Lower limit of the cost, considered to be good enough score.</p></td>
</tr>
</table>
</dd>
</dl>

<p>Definition at line 2810 of file <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/vectorize/slpvectorizer-cpp">SLPVectorizer.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/classes/llvm/slpvectorizer/boupslp/lookaheadheuristics/#a54d9af6b4c656c782e017020406e8291">llvm::slpvectorizer::BoUpSLP::LookAheadHeuristics::getScoreAtLevelRec</a>, <a href="/web-llvm/docs/api/files/lib/lib/support/md5-cpp/#ac0eafdc9ee161b71e7af98af736952fd">I</a>, <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/vectorize/slpvectorizer-cpp/#a99e5e5bf957082c728b786a978a3b18a">RootLookAheadMaxDepth</a>, <a href="/web-llvm/docs/api/classes/llvm/slpvectorizer/boupslp/lookaheadheuristics/#a653c21908b15629b676161353d43d719">llvm::slpvectorizer::BoUpSLP::LookAheadHeuristics::ScoreFail</a> and <a href="/web-llvm/docs/api/namespaces/llvm/#adc4eb8be6f7a12ede962987fb9cabb47">llvm::seq</a>.</p>


<p>Referenced by <a href="#a91b0e07ff96232db2a91d6cfdf67a5e0">transformNodes</a>.</p>

</div>
</div>

### findPartiallyOrderedLoads() {#a183245826b2f3e16c86e81e567db9b51}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">std::optional&lt; BoUpSLP::OrdersType &gt; BoUpSLP::findPartiallyOrderedLoads (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> TreeEntry &amp; TE)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Sort loads into increasing pointers offsets to allow greater clustering.</p>

<p>Definition at line 1531 of file <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/vectorize/slpvectorizer-cpp">SLPVectorizer.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/silowercontrolflow-cpp/#a4868c5d81c5ccc98c47aeab6244346a0">assert</a>, <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/vectorize/slpvectorizer-cpp/#a2d26c707fd7389b46ad98970d56faf24">clusterSortPtrAccesses</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a22eeee01734061ac1b31ccd994c49eef">llvm::dyn_cast</a>, <a href="/web-llvm/docs/api/classes/llvm/smallvectortemplatebase/#af42bfbc067df27c19ee2fc859df58799">llvm::SmallVectorTemplateBase&lt; T, bool &gt;::push_back</a> and <a href="/web-llvm/docs/api/classes/llvm/smallvectorimpl/#a499ea32ca1b8d16cedfe01d1e5b08f29">llvm::SmallVectorImpl&lt; T &gt;::reserve</a>.</p>


<p>Referenced by <a href="#ab2c5c3c0b3cd0db8b0692df8f66b6264">getReorderingData</a>.</p>

</div>
</div>

### findReusedOrderedScalars() {#af8ac96c98d73833321b6d95a9c88b9d4}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">std::optional&lt; BoUpSLP::OrdersType &gt; BoUpSLP::findReusedOrderedScalars (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> TreeEntry &amp; TE)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Checks if the specified gather tree entry <span class="doxyComputerOutput">TE</span> can be represented as a shuffled vector entry + (possibly) permutation with other gathers.</p>


<p>It implements the checks only for possibly ordered scalars (Loads, ExtractElement, ExtractValue), which can be part of the graph.</p>


<p>Definition at line 1528 of file <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/vectorize/slpvectorizer-cpp">SLPVectorizer.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/classes/llvm/smallbitvector/#a8cfcd92a373cdd7deefb939dd76b83e3">llvm::SmallBitVector::all</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a0d10fe510ced2849a8074fe81e5d04ce">llvm::all_of</a>, <a href="/web-llvm/docs/api/classes/llvm/smallbitvector/#ab06e25d03b0091f03f2a25118933236b">llvm::SmallBitVector::any</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a61d13d6824ec46c31260a4fd0997eda0">llvm::any_of</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/silowercontrolflow-cpp/#a4868c5d81c5ccc98c47aeab6244346a0">assert</a>, <a href="/web-llvm/docs/api/classes/llvm/mutablearrayref/#aae2bf8b46988a2fc0589e95903930c19">llvm::MutableArrayRef&lt; T &gt;::begin</a>, <a href="/web-llvm/docs/api/classes/llvm/smallvectortemplatecommon/#a8a045d250952c0867382a9840ee18fdf">llvm::SmallVectorTemplateCommon&lt; T, typename &gt;::begin</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#ac4fc845f5ed92de63cd4474f128f5fc5">llvm::cast</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#ac214df91cdc242f4710ea5a93939c678">llvm::count_if</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a22eeee01734061ac1b31ccd994c49eef">llvm::dyn_cast</a>, <a href="/web-llvm/docs/api/classes/llvm/smallvectortemplatecommon/#ad9a3c7bc26b130377bbafc170b5f88a2">llvm::SmallVectorTemplateCommon&lt; T, typename &gt;::empty</a>, <a href="/web-llvm/docs/api/classes/llvm/mutablearrayref/#a9d959094f4544749c129c46034cbed67">llvm::MutableArrayRef&lt; T &gt;::end</a>, <a href="/web-llvm/docs/api/classes/llvm/smallvectortemplatecommon/#a075e34e98605d0e7c289763a104869ac">llvm::SmallVectorTemplateCommon&lt; T, typename &gt;::end</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a086e9fbdb06276db7753101a08a63adf">llvm::find</a>, <a href="/web-llvm/docs/api/classes/llvm/smallvectortemplatecommon/#a58dc840fc84420b7f0b773794b8101c1">llvm::SmallVectorTemplateCommon&lt; T, typename &gt;::front</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#ac2e6c50683f73779b6b83effaf07ca30">llvm::getNumberOfParts</a>, <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/vectorize/slpvectorizer-cpp/#a3b9e7c9e471d8a5babf5b80f50029b8f">getNumElems</a>, <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/vectorize/slpvectorizer-cpp/#a74addefa3085903bdce006cd86cb2a27">getPartNumElems</a>, <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/vectorize/slpvectorizer-cpp/#a065bd87e0b855701cd8ca61aa05d4c50">getWidenedType</a>, <a href="/web-llvm/docs/api/files/lib/lib/support/md5-cpp/#ac0eafdc9ee161b71e7af98af736952fd">I</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a92ca992e52dddc420f4b069cae06dfbe">llvm::isa</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/amdgpuinstructionselector-cpp/#a6dee2d9e1e2a288de903228075ac71de">isConstant</a>, <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/vectorize/slpvectorizer-cpp/#aa3ea54a95743867473d32853d3c65603">isValidElementType</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a9965a6249be879ba3d336a75a4f3efa7">llvm::PoisonMaskElem</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#adc4eb8be6f7a12ede962987fb9cabb47">llvm::seq</a>, <a href="/web-llvm/docs/api/classes/llvm/smallbitvector/#a18e2d7efe05987370dc6b5c54797fcf5">llvm::SmallBitVector::set</a>, <a href="/web-llvm/docs/api/classes/llvm/smallvectortemplatecommon/#a1c479a8c434377c2b8cb056bdfdfc201">llvm::SmallVectorTemplateCommon&lt; T, typename &gt;::size</a>, <a href="/web-llvm/docs/api/classes/llvm/targettransforminfo/#af46433d0e36d3f80afc3a8c67b5c53eca7beec9815d0197f2d31fac9968e9205b">llvm::TargetTransformInfo::SK_PermuteSingleSrc</a> and <a href="/web-llvm/docs/api/classes/llvm/smallbitvector/#a585f149dd8c344a40c53b1694d3161ed">llvm::SmallBitVector::test</a>.</p>


<p>Referenced by <a href="#ab2c5c3c0b3cd0db8b0692df8f66b6264">getReorderingData</a>.</p>

</div>
</div>

### getCanonicalGraphSize() {#a45d4fa202493524e9b22c245f06ef855}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">unsigned llvm::slpvectorizer::BoUpSLP::getCanonicalGraphSize ()</td>
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

<p>Returns the base graph size, before any transformations.</p>

<p>Definition at line 1507 of file <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/vectorize/slpvectorizer-cpp">SLPVectorizer.cpp</a>.</p>


<p>Referenced by <a href="#ad633712289394ee2c1d80b79432d11df">isTreeNotExtendable</a> and <a href="#a91b0e07ff96232db2a91d6cfdf67a5e0">transformNodes</a>.</p>

</div>
</div>

### getMaximumVF() {#a782cc6906561f01e563f30e50833235d}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">unsigned llvm::slpvectorizer::BoUpSLP::getMaximumVF (unsigned ElemWidth, unsigned Opcode)</td>
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



<p>Definition at line 1585 of file <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/vectorize/slpvectorizer-cpp">SLPVectorizer.cpp</a>.</p>


<p>Reference <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/vectorize/slpvectorizer-cpp/#a470e4a44fc1d069edcb7e3e0b6e7f014">MaxVFOption</a>.</p>

</div>
</div>

### getMaxVecRegSize() {#adc72e9ea7ec5e94d10e2a9a4fdaa3fc2}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">unsigned llvm::slpvectorizer::BoUpSLP::getMaxVecRegSize ()</td>
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



<p>Definition at line 1572 of file <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/vectorize/slpvectorizer-cpp">SLPVectorizer.cpp</a>.</p>

</div>
</div>

### getMinVecRegSize() {#aef776c88ca6591ad28a6f21f216f1ef7}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">unsigned llvm::slpvectorizer::BoUpSLP::getMinVecRegSize ()</td>
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



<p>Definition at line 1577 of file <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/vectorize/slpvectorizer-cpp">SLPVectorizer.cpp</a>.</p>


<p>Referenced by <a href="#aacc65a747c158a620f90f612a673a506">getMinVF</a>.</p>

</div>
</div>

### getMinVF() {#aacc65a747c158a620f90f612a673a506}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">unsigned llvm::slpvectorizer::BoUpSLP::getMinVF (unsigned Sz)</td>
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



<p>Definition at line 1581 of file <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/vectorize/slpvectorizer-cpp">SLPVectorizer.cpp</a>.</p>


<p>Reference <a href="#aef776c88ca6591ad28a6f21f216f1ef7">getMinVecRegSize</a>.</p>


<p>Referenced by <a href="#a496356f8335c794a9b365488ed263ead">canVectorizeLoads</a> and <a href="#a91b0e07ff96232db2a91d6cfdf67a5e0">transformNodes</a>.</p>

</div>
</div>

### getORE() {#ac8feff57671dce8f164846b3f0499bb5}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">OptimizationRemarkEmitter * llvm::slpvectorizer::BoUpSLP::getORE ()</td>
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



<p>Definition at line 1654 of file <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/vectorize/slpvectorizer-cpp">SLPVectorizer.cpp</a>.</p>

</div>
</div>

### getReductionType() {#adac504434993ab1673128914746eef47}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">FixedVectorType * llvm::slpvectorizer::BoUpSLP::getReductionType ()</td>
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

<p>Returns reduction type after minbitdth analysis.</p>

<p>Definition at line 1450 of file <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/vectorize/slpvectorizer-cpp">SLPVectorizer.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/classes/llvm/integertype/#a14f7b4f1aed38192fb6b7772eb506bdb">llvm::IntegerType::get</a> and <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/vectorize/slpvectorizer-cpp/#a065bd87e0b855701cd8ca61aa05d4c50">getWidenedType</a>.</p>

</div>
</div>

### getReorderingData() {#ab2c5c3c0b3cd0db8b0692df8f66b6264}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">std::optional&lt; BoUpSLP::OrdersType &gt; BoUpSLP::getReorderingData (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> TreeEntry &amp; TE, bool TopToBottom)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Gets reordering data for the given tree entry.</p>


<p>If the entry is vectorized</p>


<ul class="doxyList ">
<li>just return ReorderIndices, otherwise check if the scalars can be reordered and return the most optimal order.

<dl class="doxySectionUser">
<dt>Returns</dt>
<dd><p>std::nullopt if ordering is not important, empty order, if identity order is important, or the actual order.</p></dd>
</dl>


<dl class="doxyParamsList">
<dt class="doxyParamsTableTitle">Parameters</dt>
<dd>
<table class="doxyParamsTable">
<tr class="doxyParamItem">
<td class="doxyParamItemName">TopToBottom</td>
<td class="doxyParamItemDescription"><p>If true, include the order of vectorized stores and insertelement nodes, otherwise skip them.</p></td>
</tr>
</table>
</dd>
</dl></li>
</ul>

<p>Definition at line 1540 of file <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/vectorize/slpvectorizer-cpp">SLPVectorizer.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/vectorize/slpvectorizer-cpp/#ae122b7b9960cfd970b1d5c0d83f22039">addMask</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a0d10fe510ced2849a8074fe81e5d04ce">llvm::all_of</a>, <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/vectorize/slpvectorizer-cpp/#a7568c08b526dbf7f7b5402f3eb605b55">allConstant</a>, <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/vectorize/slpvectorizer-cpp/#aabfbce373feafd33ca9e104d8b164ece">allSameType</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a61d13d6824ec46c31260a4fd0997eda0">llvm::any_of</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#ab9c6b351507d3c0730f4290919d43a12">llvm::ArrayRef</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/silowercontrolflow-cpp/#a4868c5d81c5ccc98c47aeab6244346a0">assert</a>, <a href="/web-llvm/docs/api/classes/llvm/smallvectortemplatecommon/#a8a045d250952c0867382a9840ee18fdf">llvm::SmallVectorTemplateCommon&lt; T, typename &gt;::begin</a>, <a href="#a496356f8335c794a9b365488ed263ead">canVectorizeLoads</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#ac4fc845f5ed92de63cd4474f128f5fc5">llvm::cast</a>, <a href="/web-llvm/docs/api/classes/llvm/instruction/#a784097fca76abad9e815cf1692de79c4">llvm::Instruction::comesBefore</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#ac214df91cdc242f4710ea5a93939c678">llvm::count_if</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#aa20539e89704d20b98b97e9c3feac934">llvm::Data</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a9dda4472ee0b7ea92ab49eedf6e13d50">llvm::divideCeil</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a22eeee01734061ac1b31ccd994c49eef">llvm::dyn_cast</a>, <a href="/web-llvm/docs/api/classes/llvm/smallvectortemplatecommon/#ad9a3c7bc26b130377bbafc170b5f88a2">llvm::SmallVectorTemplateCommon&lt; T, typename &gt;::empty</a>, <a href="/web-llvm/docs/api/classes/llvm/smallvectortemplatecommon/#a075e34e98605d0e7c289763a104869ac">llvm::SmallVectorTemplateCommon&lt; T, typename &gt;::end</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a206e2134ddd2312c3488d0632d98f554">llvm::enumerate</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a086e9fbdb06276db7753101a08a63adf">llvm::find</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#ac78c09ae232b2ce188ff590d51e3c268">llvm::find_if</a>, <a href="#a183245826b2f3e16c86e81e567db9b51">findPartiallyOrderedLoads</a>, <a href="#af8ac96c98d73833321b6d95a9c88b9d4">findReusedOrderedScalars</a>, <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/vectorize/slpvectorizer-cpp/#ae203ebf95f0711b6d63e3672baeaf669">fixupOrderingIndices</a>, <a href="/web-llvm/docs/api/classes/llvm/smallvectortemplatecommon/#a58dc840fc84420b7f0b773794b8101c1">llvm::SmallVectorTemplateCommon&lt; T, typename &gt;::front</a>, <a href="/web-llvm/docs/api/classes/llvm/poisonvalue/#a1bf08613fb664a2e377a9a72c59a6b66">llvm::PoisonValue::get</a>, <a href="/web-llvm/docs/api/files/lib/lib/ir/datalayout-cpp/#a0626211048d3157a84aac054ba7e894a">getElementIndex</a>, <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/vectorize/slpvectorizer-cpp/#a992052c8e8463f5d055c79ca8abb9521">getExtractIndex</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#ac2e6c50683f73779b6b83effaf07ca30">llvm::getNumberOfParts</a>, <a href="/web-llvm/docs/api/classes/llvm/value/#aba0055050d741f60b6e0523507a2c79f">llvm::Value::getNumUses</a>, <a href="/web-llvm/docs/api/files/lib/lib/analysis/basicaliasanalysis-cpp/#a1b8850f1ed44c12bc3501175a71c251c">getParent</a>, <a href="/web-llvm/docs/api/classes/llvm/ilist-detail/node-parent-access/#a7e19e7508415378ad9523e0339b23e22">llvm::ilist_detail::node_parent_access&lt; NodeTy, ParentTy &gt;::getParent</a>, <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/vectorize/slpvectorizer-cpp/#a3c4c7b26972597220296eab6450669b0">getShuffleCost</a>, <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/vectorize/slpvectorizer-cpp/#a065bd87e0b855701cd8ca61aa05d4c50">getWidenedType</a>, <a href="/web-llvm/docs/api/files/lib/lib/support/md5-cpp/#ac0eafdc9ee161b71e7af98af736952fd">I</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/nvptx/nvvmintrrange-cpp/#ac5804672fc0850438d63caec770647f8">II</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a6f0917bf2ae18fac81fea6bf7e887115">llvm::inversePermutation</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a92ca992e52dddc420f4b069cae06dfbe">llvm::isa</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a445c0cf40cd4a28c8b53579dfab9a193">llvm::IsaPred</a>, <a href="#ae420d94473ac8cb96686184a551f6097">isIdentityOrder</a>, <a href="/web-llvm/docs/api/classes/llvm/shufflevectorinst/#a6659bba6a4be5e7102bdb10e5fc3658c">llvm::ShuffleVectorInst::isOneUseSingleSourceMask</a>, <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/vectorize/slpvectorizer-cpp/#afa640d51b943ce0396e7131bf2352f8a">isReverseOrder</a>, <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/scalar/lowermatrixintrinsics-cpp/#a6a2164e5aeea9c3e9a02eab3747efd8c">isSplat</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a9965a6249be879ba3d336a75a4f3efa7">llvm::PoisonMaskElem</a>, <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/vectorize/slpvectorizer-cpp/#a633db91afb11db086004de9e3eb37217">reorderOrder</a>, <a href="/web-llvm/docs/api/classes/llvm/smallbitvector/#a18e2d7efe05987370dc6b5c54797fcf5">llvm::SmallBitVector::set</a>, <a href="/web-llvm/docs/api/classes/llvm/smallvectortemplatecommon/#a1c479a8c434377c2b8cb056bdfdfc201">llvm::SmallVectorTemplateCommon&lt; T, typename &gt;::size</a>, <a href="/web-llvm/docs/api/classes/llvm/targettransforminfo/#af46433d0e36d3f80afc3a8c67b5c53eca7beec9815d0197f2d31fac9968e9205b">llvm::TargetTransformInfo::SK_PermuteSingleSrc</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a076f93c387f454f0db13d4bc7d4e7f9c">llvm::stable_sort</a>, <a href="#a1897e235929f1961872707de9a400031ac1873549f5ed932486f6b91a280e118e">StridedVectorize</a>, <a href="/web-llvm/docs/api/classes/llvm/targettransforminfo/#a706f223f760b55668fbae74202b816bba59b32ea7b6f10564abd40ad90602ca5b">llvm::TargetTransformInfo::TCK_RecipThroughput</a>, <a href="/web-llvm/docs/api/classes/llvm/smallbitvector/#a585f149dd8c344a40c53b1694d3161ed">llvm::SmallBitVector::test</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a615619b0b2879029152b9a20e96624bc">llvm::transform</a>, <a href="/web-llvm/docs/api/classes/llvm/value/#a158da2b6d3d938aaa15b6acd00150e2c">llvm::Value::user_begin</a>, <a href="#a1897e235929f1961872707de9a400031ab8c3ff4276089f60a1f1820acc67bf60">Vectorize</a>, <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/vectorize/slpvectorizer-cpp/#a617fa15d11df5807cbc0e7191ff649d3">VectorizeNonPowerOf2</a> and <a href="/web-llvm/docs/api/namespaces/llvm/#a06041e3bf4b0a9e8984809413ddd9506">llvm::zip</a>.</p>


<p>Referenced by <a href="#a2eb73a15ea2a5105bd2cec95863d7113">reorderBottomToTop</a> and <a href="#a1bc3cc02c0dc6dcb9ad315b7755475e7">reorderTopToBottom</a>.</p>

</div>
</div>

### getRootNodeScalars() {#a612d7463b1c5f28990f0f5e3593b7401}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">ArrayRef&lt; Value * &gt; llvm::slpvectorizer::BoUpSLP::getRootNodeScalars ()</td>
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

<p>Return the scalars of the root node.</p>

<p>Definition at line 1419 of file <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/vectorize/slpvectorizer-cpp">SLPVectorizer.cpp</a>.</p>


<p>Reference <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/silowercontrolflow-cpp/#a4868c5d81c5ccc98c47aeab6244346a0">assert</a>.</p>

</div>
</div>

### getRootNodeTypeWithNoCast() {#a0b43ef7c72a8cb10a0cb09154a3b3b2d}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">std::optional&lt; std::pair&lt; Type *, bool &gt; &gt; llvm::slpvectorizer::BoUpSLP::getRootNodeTypeWithNoCast ()</td>
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

<p>Returns the type/is-signed info for the root node in the graph without casting.</p>

<p>Definition at line 1426 of file <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/vectorize/slpvectorizer-cpp">SLPVectorizer.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/namespaces/llvm/#ac4fc845f5ed92de63cd4474f128f5fc5">llvm::cast</a>, <a href="/web-llvm/docs/api/classes/llvm/smallvectortemplatecommon/#a58dc840fc84420b7f0b773794b8101c1">llvm::SmallVectorTemplateCommon&lt; T, typename &gt;::front</a>, <a href="/web-llvm/docs/api/classes/llvm/integertype/#a14f7b4f1aed38192fb6b7772eb506bdb">llvm::IntegerType::get</a>, <a href="/web-llvm/docs/api/classes/llvm/value/#ab3fc0225d8aaf8434026c3573f961f2c">llvm::Value::getContext</a>, <a href="/web-llvm/docs/api/classes/llvm/value/#a0344a49526443edf90cc0aef3abd3337">llvm::Value::getType</a> and <a href="/web-llvm/docs/api/classes/llvm/type/#ac6d28a9b11139182134a9618028a0d07">llvm::Type::isIntegerTy</a>.</p>

</div>
</div>

### getSpillCost() {#aee3b49d7f15550d64c7db0e29a124c6d}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">InstructionCost BoUpSLP::getSpillCost ()</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">




<dl class="doxySectionUser">
<dt>Returns</dt>
<dd><p>the cost incurred by unwanted spills and fills, caused by holding live values over call sites.</p></dd>
</dl>


<p>Definition at line 1398 of file <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/vectorize/slpvectorizer-cpp">SLPVectorizer.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/files/lib/lib/ir/builtingcs-cpp/#a2e38c85003a042421cde1647632d0b72">A</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/silowercontrolflow-cpp/#a4868c5d81c5ccc98c47aeab6244346a0">assert</a>, <a href="/web-llvm/docs/api/files/lib/lib/ir/builtingcs-cpp/#ae76959fe811ba090de4cba69ac00f1da">B</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#ac4fc845f5ed92de63cd4474f128f5fc5">llvm::cast</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a7c46c742c31be54870e2038048e6b391">llvm::dbgs</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a22eeee01734061ac1b31ccd994c49eef">llvm::dyn_cast</a>, <a href="/web-llvm/docs/api/classes/llvm/smallptrsetimpl/#a11045c7973ab24a8d6315b61fa337d4e">llvm::SmallPtrSetImpl&lt; PtrType &gt;::erase</a>, <a href="/web-llvm/docs/api/classes/llvm/ilist-node-impl/#af719fc783be6589465137d997701a432">llvm::ilist_node_impl&lt; OptionsT &gt;::getIterator</a>, <a href="/web-llvm/docs/api/classes/llvm/ilist-detail/node-parent-access/#a7e19e7508415378ad9523e0339b23e22">llvm::ilist_detail::node_parent_access&lt; NodeTy, ParentTy &gt;::getParent</a>, <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/vectorize/slpvectorizer-cpp/#a065bd87e0b855701cd8ca61aa05d4c50">getWidenedType</a>, <a href="/web-llvm/docs/api/files/lib/lib/support/md5-cpp/#ac0eafdc9ee161b71e7af98af736952fd">I</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/nvptx/nvvmintrrange-cpp/#ac5804672fc0850438d63caec770647f8">II</a>, <a href="/web-llvm/docs/api/classes/llvm/smallptrsetimpl/#a9d834ae3da8c62c2b668dada51335eb0">llvm::SmallPtrSetImpl&lt; PtrType &gt;::insert</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a92ca992e52dddc420f4b069cae06dfbe">llvm::isa</a>, <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/support/debug-h/#a196897517069dda1bdb549e24468f7d7">LLVM_DEBUG</a>, <a href="/web-llvm/docs/api/classes/llvm/user/#a0b931781aa589c6ebe64a76c1447e5b2">llvm::User::operands</a>, <a href="/web-llvm/docs/api/classes/llvm/smallvectortemplatebase/#af42bfbc067df27c19ee2fc859df58799">llvm::SmallVectorTemplateBase&lt; T, bool &gt;::push_back</a>, <a href="/web-llvm/docs/api/classes/llvm/smallptrsetimplbase/#a0e1c3175b0ac22fe3853651c28e1ecb8">llvm::SmallPtrSetImplBase::size</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a74cdbd1e4f731e7d7cd83461b8b1de0b">llvm::sort</a>, <a href="/web-llvm/docs/api/classes/llvm/targettransforminfo/#a706f223f760b55668fbae74202b816bba59b32ea7b6f10564abd40ad90602ca5b">llvm::TargetTransformInfo::TCK_RecipThroughput</a> and <a href="/web-llvm/docs/api/files/lib/lib/tablegen/tablegenbackendskeleton-cpp/#ab60f28d7a141ac46ccc200176a1bca8b">X</a>.</p>

</div>
</div>

### getTreeCost() {#a7800714c330f8f3952e8058b090e001b}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">InstructionCost BoUpSLP::getTreeCost (<a href="/web-llvm/docs/api/classes/llvm/arrayref">ArrayRef</a>&lt; <a href="/web-llvm/docs/api/classes/llvm/value">Value</a> * &gt; VectorizedVals={})</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">




<dl class="doxySectionUser">
<dt>Returns</dt>
<dd><p>the vectorization cost of the subtree that starts at <span class="doxyComputerOutput">VL</span>. A negative number means that this is profitable.</p></dd>
</dl>


<p>Definition at line 1402 of file <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/vectorize/slpvectorizer-cpp">SLPVectorizer.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/namespaces/llvm/#a0d10fe510ced2849a8074fe81e5d04ce">llvm::all_of</a>, <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/vectorize/slpvectorizer-cpp/#abe6927d96b3815417479246b5afc732e">areTwoInsertFromSameBuildVector</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/silowercontrolflow-cpp/#a4868c5d81c5ccc98c47aeab6244346a0">assert</a>, <a href="/web-llvm/docs/api/classes/llvm/smallvectortemplatecommon/#a8a045d250952c0867382a9840ee18fdf">llvm::SmallVectorTemplateCommon&lt; T, typename &gt;::begin</a>, <a href="/web-llvm/docs/api/namespaces/llvm/callingconv/#ac6aa1387c4375260e2468eb5a77fdb4cafd841a49aec1539bc88abc8ff9e170fb">llvm::CallingConv::C</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#ac4fc845f5ed92de63cd4474f128f5fc5">llvm::cast</a>, <a href="/web-llvm/docs/api/files/lib/lib/analysis/costmodel-cpp/#a162d8b2b3865594d1e14d828d2b8336a">CostKind</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#ac214df91cdc242f4710ea5a93939c678">llvm::count_if</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#aa20539e89704d20b98b97e9c3feac934">llvm::Data</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a7c46c742c31be54870e2038048e6b391">llvm::dbgs</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a22eeee01734061ac1b31ccd994c49eef">llvm::dyn_cast</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a3377eac88526e806d9d887c4a0ba2a73">llvm::dyn_cast_if_present</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a5f6182886dc2f96c204299e92c1565d5">llvm::dyn_cast_or_null</a>, <a href="/web-llvm/docs/api/classes/llvm/smallvectorimpl/#a396fcfee6914c76974b73c3d203da6a5">llvm::SmallVectorImpl&lt; T &gt;::emplace_back</a>, <a href="/web-llvm/docs/api/classes/llvm/densemapbase/#a65520b9c67759099e313d0f4e7b5ff9e">llvm::DenseMapBase&lt; DerivedT, KeyT, ValueT, KeyInfoT, BucketT &gt;::end</a>, <a href="/web-llvm/docs/api/classes/llvm/smallvectortemplatecommon/#a075e34e98605d0e7c289763a104869ac">llvm::SmallVectorTemplateCommon&lt; T, typename &gt;::end</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a206e2134ddd2312c3488d0632d98f554">llvm::enumerate</a>, <a href="/web-llvm/docs/api/classes/llvm/densemapbase/#a0c047f127ed4380a6f383d70bec4eb94">llvm::DenseMapBase&lt; DerivedT, KeyT, ValueT, KeyInfoT, BucketT &gt;::find</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#ac78c09ae232b2ce188ff590d51e3c268">llvm::find_if</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a0b2a153b655ed78a07468297eb4c6256">llvm::for_each</a>, <a href="/web-llvm/docs/api/classes/llvm/integertype/#a14f7b4f1aed38192fb6b7772eb506bdb">llvm::IntegerType::get</a>, <a href="/web-llvm/docs/api/files/lib/lib/ir/datalayout-cpp/#a0626211048d3157a84aac054ba7e894a">getElementIndex</a>, <a href="/web-llvm/docs/api/classes/llvm/user/#aa0a2cb1582d1cec317bd205085469ca1">llvm::User::getOperand</a>, <a href="/web-llvm/docs/api/classes/llvm/insertelementinst/#a49230ece74a48a27fb2bb1a4928b6e29">llvm::InsertElementInst::getType</a>, <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/vectorize/slpvectorizer-cpp/#a065bd87e0b855701cd8ca61aa05d4c50">getWidenedType</a>, <a href="/web-llvm/docs/api/classes/llvm/apint/#add4e37b60ea64faafbc9a5bf3e27280f">llvm::APInt::getZero</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a617c1c04cfa1325ad04eb69339d92188">llvm::has_single_bit</a>, <a href="/web-llvm/docs/api/files/lib/lib/support/md5-cpp/#ac0eafdc9ee161b71e7af98af736952fd">I</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/nvptx/nvvmintrrange-cpp/#ac5804672fc0850438d63caec770647f8">II</a>, <a href="/web-llvm/docs/api/classes/llvm/detail/densesetimpl/#a1b0f3ebdced8fce4b22c6a63b25d9525">llvm::detail::DenseSetImpl&lt; ValueT, MapTy, ValueInfoT &gt;::insert</a>, <a href="/web-llvm/docs/api/classes/llvm/smallptrsetimpl/#a9d834ae3da8c62c2b668dada51335eb0">llvm::SmallPtrSetImpl&lt; PtrType &gt;::insert</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a92ca992e52dddc420f4b069cae06dfbe">llvm::isa</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a4956305191cdba7f9995569d011a5ab7">llvm::isa_and_nonnull</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a7c36204b4ae6bbd9edda208f271aa569">llvm::isa_and_present</a>, <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/vectorize/slpvectorizer-cpp/#a405ff61e8571b58fecaa716540af108f">isFirstInsertElement</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#ae7f4b5fbc0aa5c8204b9a4b06e070d75">llvm::isKnownNonNegative</a>, <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/support/debug-h/#a196897517069dda1bdb549e24468f7d7">LLVM_DEBUG</a>, <a href="/web-llvm/docs/api/classes/llvm/targettransforminfo/#af84cce349a77262269fd3f6756f37a64a6adf97f83acf6453d4a6a4b1070f3754">llvm::TargetTransformInfo::None</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a7dc3069afa2ce5ea62ac2eb183e51c00">llvm::none_of</a>, <a href="/web-llvm/docs/api/files/lib/lib/option/option-cpp/#a04665169063c8ca1f2ea96c27fc7c2b2">P</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a9965a6249be879ba3d336a75a4f3efa7">llvm::PoisonMaskElem</a>, <a href="/web-llvm/docs/api/classes/llvm/smallvectortemplatebase/#af42bfbc067df27c19ee2fc859df58799">llvm::SmallVectorTemplateBase&lt; T, bool &gt;::push_back</a>, <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/vectorize/slpvectorizer-cpp/#a9f3bcb74818214fe1e8df656c52ab206">shortBundleName</a>, <a href="/web-llvm/docs/api/classes/llvm/smallvectortemplatecommon/#a1c479a8c434377c2b8cb056bdfdfc201">llvm::SmallVectorTemplateCommon&lt; T, typename &gt;::size</a>, <a href="/web-llvm/docs/api/classes/llvm/targettransforminfo/#ac44f6b9fdbb5f9cc199f8329cb0b272cae46c9eecc49bd2dc253c607e78a0fb86">llvm::TargetTransformInfo::TCC_Basic</a>, <a href="/web-llvm/docs/api/classes/llvm/targettransforminfo/#ac44f6b9fdbb5f9cc199f8329cb0b272ca89f768b1267e3083b4eb05b4ab77e717">llvm::TargetTransformInfo::TCC_Free</a>, <a href="/web-llvm/docs/api/classes/llvm/targettransforminfo/#a706f223f760b55668fbae74202b816bba59b32ea7b6f10564abd40ad90602ca5b">llvm::TargetTransformInfo::TCK_RecipThroughput</a> and <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/vectorize/slpvectorizer-cpp/#a75df5de932994d1472ad3cda6a88cf21">UsesLimit</a>.</p>

</div>
</div>

### getTreeSize() {#a3a11daf8d89c135162dd6623f5bd164f}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">unsigned llvm::slpvectorizer::BoUpSLP::getTreeSize ()</td>
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



<p>Definition at line 1504 of file <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/vectorize/slpvectorizer-cpp">SLPVectorizer.cpp</a>.</p>


<p>Referenced by <a href="#ad633712289394ee2c1d80b79432d11df">isTreeNotExtendable</a> and <a href="#a91b0e07ff96232db2a91d6cfdf67a5e0">transformNodes</a>.</p>

</div>
</div>

### getVectorElementSize() {#a54f30c8bea3912d1d0f347626c395be6}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">unsigned BoUpSLP::getVectorElementSize (<a href="/web-llvm/docs/api/classes/llvm/value">Value</a> * V)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">




<dl class="doxySectionUser">
<dt>Returns</dt>
<dd><p>The vector element size in bits to use when vectorizing the expression tree ending at <span class="doxyComputerOutput">V</span>. If V is a store, the size is the width of the stored value. Otherwise, the size is the width of the largest loaded value reaching V. This method is used by the vectorizer to calculate vectorization factors.</p></dd>
</dl>


<p>Definition at line 1565 of file <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/vectorize/slpvectorizer-cpp">SLPVectorizer.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/namespaces/llvm/#a22eeee01734061ac1b31ccd994c49eef">llvm::dyn_cast</a>, <a href="/web-llvm/docs/api/classes/llvm/smallvectorimpl/#a396fcfee6914c76974b73c3d203da6a5">llvm::SmallVectorImpl&lt; T &gt;::emplace_back</a>, <a href="/web-llvm/docs/api/classes/llvm/smallvectortemplatecommon/#ad9a3c7bc26b130377bbafc170b5f88a2">llvm::SmallVectorTemplateCommon&lt; T, typename &gt;::empty</a>, <a href="/web-llvm/docs/api/classes/llvm/type/#aa75984a442f2379de0c66018201fa628">llvm::Type::getInt1Ty</a>, <a href="/web-llvm/docs/api/classes/llvm/value/#a0344a49526443edf90cc0aef3abd3337">llvm::Value::getType</a>, <a href="#a54f30c8bea3912d1d0f347626c395be6">getVectorElementSize</a>, <a href="/web-llvm/docs/api/files/lib/lib/support/md5-cpp/#ac0eafdc9ee161b71e7af98af736952fd">I</a>, <a href="/web-llvm/docs/api/classes/llvm/smallptrsetimpl/#a9d834ae3da8c62c2b668dada51335eb0">llvm::SmallPtrSetImpl&lt; PtrType &gt;::insert</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a92ca992e52dddc420f4b069cae06dfbe">llvm::isa</a>, <a href="/web-llvm/docs/api/classes/llvm/smallvectorimpl/#a0c8ffe664a36e30d49c84d0aded2fe08">llvm::SmallVectorImpl&lt; T &gt;::pop_back_val</a> and <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/vectorize/slpvectorizer-cpp/#adbff8697d64e4ee139aa777b68999872">RecursionMaxDepth</a>.</p>


<p>Referenced by <a href="#a54f30c8bea3912d1d0f347626c395be6">getVectorElementSize</a> and <a href="#a91b0e07ff96232db2a91d6cfdf67a5e0">transformNodes</a>.</p>

</div>
</div>

### isAnalyzedReductionRoot() {#ab27b8e376a736c99b51c692c97a988fc}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool llvm::slpvectorizer::BoUpSLP::isAnalyzedReductionRoot (<a href="/web-llvm/docs/api/classes/llvm/instruction">Instruction</a> * I)</td>
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

<p>Checks if the instruction was already analyzed for being possible reduction root.</p>

<p>Definition at line 2926 of file <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/vectorize/slpvectorizer-cpp">SLPVectorizer.cpp</a>.</p>


<p>Reference <a href="/web-llvm/docs/api/files/lib/lib/support/md5-cpp/#ac0eafdc9ee161b71e7af98af736952fd">I</a>.</p>

</div>
</div>

### isAnyGathered() {#acc0cf2fab0dd3b42f500516296cb0bea}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool llvm::slpvectorizer::BoUpSLP::isAnyGathered (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/smalldenseset">SmallDenseSet</a>&lt; <a href="/web-llvm/docs/api/classes/llvm/value">Value</a> * &gt; &amp; Vals)</td>
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

<p>Checks if the given value is gathered in one of the nodes.</p>

<p>Definition at line 2951 of file <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/vectorize/slpvectorizer-cpp">SLPVectorizer.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/namespaces/llvm/#a61d13d6824ec46c31260a4fd0997eda0">llvm::any_of</a> and <a href="/web-llvm/docs/api/classes/llvm/detail/densesetimpl/#ad409c2de8502b94c8a0b1193307c63b6">llvm::detail::DenseSetImpl&lt; ValueT, MapTy, ValueInfoT &gt;::contains</a>.</p>

</div>
</div>

### isDeleted() {#a937e8e7cd2fb7c82d9512b69fc81b65b}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool llvm::slpvectorizer::BoUpSLP::isDeleted (<a href="/web-llvm/docs/api/classes/llvm/instruction">Instruction</a> * I)</td>
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

<p>Checks if the instruction is marked for deletion.</p>

<p>Definition at line 2830 of file <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/vectorize/slpvectorizer-cpp">SLPVectorizer.cpp</a>.</p>


<p>Reference <a href="/web-llvm/docs/api/files/lib/lib/support/md5-cpp/#ac0eafdc9ee161b71e7af98af736952fd">I</a>.</p>


<p>Referenced by <a href="#a9a2e07f0b5ef19c59116913d4875a4e3">buildExternalUses</a>, <a href="#afd07d19c7174c06cd7c7415f63596839">optimizeGatherSequence</a> and <a href="#a91b0e07ff96232db2a91d6cfdf67a5e0">transformNodes</a>.</p>

</div>
</div>

### isGathered() {#ae687ad0abfe8f68d8ca893dac9f1fa3a}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool llvm::slpvectorizer::BoUpSLP::isGathered (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/value">Value</a> * V)</td>
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

<p>Checks if the given value is gathered in one of the nodes.</p>

<p>Definition at line 2955 of file <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/vectorize/slpvectorizer-cpp">SLPVectorizer.cpp</a>.</p>

</div>
</div>

### isIdentityOrder() {#ae420d94473ac8cb96686184a551f6097}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool llvm::slpvectorizer::BoUpSLP::isIdentityOrder (<a href="/web-llvm/docs/api/classes/llvm/arrayref">ArrayRef</a>&lt; unsigned &gt; Order)</td>
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

<p>Does this non-empty order represent an identity order?</p>


<p>Identity should be represented as an empty order, so this is used to decide if we can canonicalize a computed order. Undef elements (represented as size) are ignored.</p>


<p>Definition at line 1516 of file <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/vectorize/slpvectorizer-cpp">SLPVectorizer.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/namespaces/llvm/#a0d10fe510ced2849a8074fe81e5d04ce">llvm::all_of</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/silowercontrolflow-cpp/#a4868c5d81c5ccc98c47aeab6244346a0">assert</a>, <a href="/web-llvm/docs/api/classes/llvm/arrayref/#ac835b8735b1b2faec0efdca236e37d94">llvm::ArrayRef&lt; T &gt;::empty</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a206e2134ddd2312c3488d0632d98f554">llvm::enumerate</a>, <a href="/web-llvm/docs/api/files/lib/lib/option/option-cpp/#a04665169063c8ca1f2ea96c27fc7c2b2">P</a> and <a href="/web-llvm/docs/api/classes/llvm/arrayref/#a85ffb6531d4cda988ea81f18d4e56fb7">llvm::ArrayRef&lt; T &gt;::size</a>.</p>


<p>Referenced by <a href="#ab2c5c3c0b3cd0db8b0692df8f66b6264">getReorderingData</a>, <a href="#a2eb73a15ea2a5105bd2cec95863d7113">reorderBottomToTop</a> and <a href="#a1bc3cc02c0dc6dcb9ad315b7755475e7">reorderTopToBottom</a>.</p>

</div>
</div>

### isLoadCombineCandidate() {#a49a7bbde7c622cc904ed4f8c1857cae6}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool BoUpSLP::isLoadCombineCandidate (<a href="/web-llvm/docs/api/classes/llvm/arrayref">ArrayRef</a>&lt; <a href="/web-llvm/docs/api/classes/llvm/value">Value</a> * &gt; Stores)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Assume that a vector of stores of bitwise-or/shifted/zexted loaded values can be load combined in the backend.</p>


<p>Load combining may not be allowed in the IR optimizer, so we do not want to alter the pattern. For example, partially transforming a scalar bswap() pattern into vector code is effectively impossible for the backend to undo. TODO: If load combining is allowed in the IR optimizer, this analysis may not be necessary.</p>


<p>Definition at line 1625 of file <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/vectorize/slpvectorizer-cpp">SLPVectorizer.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/vectorize/slpvectorizer-cpp/#a0109582eb646d501101a7e6a059814fb">isLoadCombineCandidateImpl</a>, <a href="/web-llvm/docs/api/namespaces/llvm/patternmatch/#a00ad7932f192b7c4702d78902155536d">llvm::PatternMatch::m_Store</a>, <a href="/web-llvm/docs/api/namespaces/llvm/patternmatch/#aaf522908fe903018eb9b087dd6e49296">llvm::PatternMatch::m_Value</a>, <a href="/web-llvm/docs/api/namespaces/llvm/patternmatch/#a25d956d9e0beadd47ce4bc255dfa811d">llvm::PatternMatch::match</a>, <a href="/web-llvm/docs/api/classes/llvm/arrayref/#a85ffb6531d4cda988ea81f18d4e56fb7">llvm::ArrayRef&lt; T &gt;::size</a> and <a href="/web-llvm/docs/api/files/lib/lib/tablegen/tablegenbackendskeleton-cpp/#ab60f28d7a141ac46ccc200176a1bca8b">X</a>.</p>

</div>
</div>

### isLoadCombineReductionCandidate() {#a541f9da09ec4756f94ba8de97508ad80}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool BoUpSLP::isLoadCombineReductionCandidate (<a href="/web-llvm/docs/api/namespaces/llvm/#aac36edd0f1ce976f0025c98e88d3830e">RecurKind</a> RdxKind)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Assume that a legal-sized 'or'-reduction of shifted/zexted loaded values can be load combined in the backend.</p>


<p>Load combining may not be allowed in the IR optimizer, so we do not want to alter the pattern. For example, partially transforming a scalar bswap() pattern into vector code is effectively impossible for the backend to undo. TODO: If load combining is allowed in the IR optimizer, this analysis may not be necessary.</p>


<p>Definition at line 1616 of file <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/vectorize/slpvectorizer-cpp">SLPVectorizer.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/vectorize/slpvectorizer-cpp/#a0109582eb646d501101a7e6a059814fb">isLoadCombineCandidateImpl</a> and <a href="/web-llvm/docs/api/namespaces/llvm/#aac36edd0f1ce976f0025c98e88d3830ea3a2d5fe857d8f9541136a124c2edec6c">llvm::Or</a>.</p>

</div>
</div>

### isNotScheduled() {#a901abd1d0b7b05f2e37225606f095e7e}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool llvm::slpvectorizer::BoUpSLP::isNotScheduled (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/value">Value</a> * V)</td>
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

<p>Checks if the specified value was not schedule.</p>

<p>Definition at line 2959 of file <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/vectorize/slpvectorizer-cpp">SLPVectorizer.cpp</a>.</p>

</div>
</div>

### isSignedMinBitwidthRootNode() {#a5c9be38d8bb16b6d645d2dfdb60f908d}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool llvm::slpvectorizer::BoUpSLP::isSignedMinBitwidthRootNode ()</td>
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

<p>Checks if the root graph node can be emitted with narrower bitwidth at codegen and returns it signedness, if so.</p>

<p>Definition at line 1445 of file <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/vectorize/slpvectorizer-cpp">SLPVectorizer.cpp</a>.</p>

</div>
</div>

### isTreeNotExtendable() {#ad633712289394ee2c1d80b79432d11df}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool BoUpSLP::isTreeNotExtendable ()</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Checks if the graph and all its subgraphs cannot be better vectorized.</p>


<p>It may happen, if all gather nodes are loads and they cannot be "clusterized". In this case even subgraphs cannot be vectorized more effectively than the base graph.</p>


<p>Definition at line 1607 of file <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/vectorize/slpvectorizer-cpp">SLPVectorizer.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/vectorize/slpvectorizer-cpp/#a7568c08b526dbf7f7b5402f3eb605b55">allConstant</a>, <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/vectorize/slpvectorizer-cpp/#abd5114d6b451e9ca85a36fc3f19f76c4">allSameBlock</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#ab9c6b351507d3c0730f4290919d43a12">llvm::ArrayRef</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#ac214df91cdc242f4710ea5a93939c678">llvm::count_if</a>, <a href="#a45d4fa202493524e9b22c245f06ef855">getCanonicalGraphSize</a>, <a href="#a3a11daf8d89c135162dd6623f5bd164f">getTreeSize</a>, <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/scalar/lowermatrixintrinsics-cpp/#a6a2164e5aeea9c3e9a02eab3747efd8c">isSplat</a> and <a href="/web-llvm/docs/api/namespaces/llvm/#adc4eb8be6f7a12ede962987fb9cabb47">llvm::seq</a>.</p>

</div>
</div>

### isTreeTinyAndNotFullyVectorizable() {#aa054ca3a90996e96887be015cf288270}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool BoUpSLP::isTreeTinyAndNotFullyVectorizable (bool ForReduction=false)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">




<dl class="doxySectionUser">
<dt>Returns</dt>
<dd><p>True if the VectorizableTree is both tiny and not fully vectorizable. We do not vectorize such trees.</p></dd>
</dl>


<p>Definition at line 1601 of file <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/vectorize/slpvectorizer-cpp">SLPVectorizer.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/namespaces/llvm/#a0d10fe510ced2849a8074fe81e5d04ce">llvm::all_of</a>, <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/vectorize/slpvectorizer-cpp/#a7568c08b526dbf7f7b5402f3eb605b55">allConstant</a>, <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/vectorize/slpvectorizer-cpp/#abd5114d6b451e9ca85a36fc3f19f76c4">allSameBlock</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a61d13d6824ec46c31260a4fd0997eda0">llvm::any_of</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/silowercontrolflow-cpp/#a4868c5d81c5ccc98c47aeab6244346a0">assert</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#ac214df91cdc242f4710ea5a93939c678">llvm::count_if</a>, <a href="/web-llvm/docs/api/classes/llvm/apint/#a071e8d814b2b30b02544fad964227b8e">llvm::APInt::getAllOnes</a>, <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/vectorize/slpvectorizer-cpp/#a065bd87e0b855701cd8ca61aa05d4c50">getWidenedType</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a92ca992e52dddc420f4b069cae06dfbe">llvm::isa</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a445c0cf40cd4a28c8b53579dfab9a193">llvm::IsaPred</a>, <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/scalar/lowermatrixintrinsics-cpp/#a6a2164e5aeea9c3e9a02eab3747efd8c">isSplat</a>, <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/vectorize/slpvectorizer-cpp/#a630e10d123952904d5da8a02713d935a">MinTreeSize</a>, <a href="/web-llvm/docs/api/classes/llvm/debugcounter/#a5aace8653ce3726ef07194dcf6bce2bf">llvm::DebugCounter::shouldExecute</a>, <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/vectorize/slpvectorizer-cpp/#a704fbec676f53c0e32a778dcd57d21d9">SLPCostThreshold</a> and <a href="/web-llvm/docs/api/classes/llvm/targettransforminfo/#a706f223f760b55668fbae74202b816bba59b32ea7b6f10564abd40ad90602ca5b">llvm::TargetTransformInfo::TCK_RecipThroughput</a>.</p>

</div>
</div>

### isVectorized() {#adef9fad96a0d90c56a892520edbdb749}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool llvm::slpvectorizer::BoUpSLP::isVectorized (<a href="/web-llvm/docs/api/classes/llvm/value">Value</a> * V)</td>
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

<p><a href="/web-llvm/docs/api/namespaces/llvm/check">Check</a> if the value is vectorized in the tree.</p>

<p>Definition at line 2964 of file <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/vectorize/slpvectorizer-cpp">SLPVectorizer.cpp</a>.</p>


<p>Referenced by <a href="#a91b0e07ff96232db2a91d6cfdf67a5e0">transformNodes</a>.</p>

</div>
</div>

### optimizeGatherSequence() {#afd07d19c7174c06cd7c7415f63596839}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void BoUpSLP::optimizeGatherSequence ()</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Perform LICM and CSE on the newly generated gather sequences.</p>

<p>Definition at line 1510 of file <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/vectorize/slpvectorizer-cpp">SLPVectorizer.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/files/lib/lib/ir/builtingcs-cpp/#a2e38c85003a042421cde1647632d0b72">A</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a61d13d6824ec46c31260a4fd0997eda0">llvm::any_of</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/silowercontrolflow-cpp/#a4868c5d81c5ccc98c47aeab6244346a0">assert</a>, <a href="/web-llvm/docs/api/classes/llvm/smallvectorimpl/#a38c50aa8e3e9588f4f968c2e03a0cee0">llvm::SmallVectorImpl&lt; T &gt;::assign</a>, <a href="/web-llvm/docs/api/files/lib/lib/ir/builtingcs-cpp/#ae76959fe811ba090de4cba69ac00f1da">B</a>, <a href="/web-llvm/docs/api/classes/llvm/smallvectortemplatecommon/#a8a045d250952c0867382a9840ee18fdf">llvm::SmallVectorTemplateCommon&lt; T, typename &gt;::begin</a>, <a href="/web-llvm/docs/api/classes/llvm/smallptrsetimplbase/#a16413f1a88d8baca228d0a1b4cc0bfc6">llvm::SmallPtrSetImplBase::clear</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a7c46c742c31be54870e2038048e6b391">llvm::dbgs</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a22eeee01734061ac1b31ccd994c49eef">llvm::dyn_cast</a>, <a href="/web-llvm/docs/api/classes/llvm/smallvectortemplatecommon/#ad9a3c7bc26b130377bbafc170b5f88a2">llvm::SmallVectorTemplateCommon&lt; T, typename &gt;::empty</a>, <a href="/web-llvm/docs/api/classes/llvm/smallvectortemplatecommon/#a075e34e98605d0e7c289763a104869ac">llvm::SmallVectorTemplateCommon&lt; T, typename &gt;::end</a>, <a href="#ab93aab6d000a610c36f69bb84137b2b8">eraseInstruction</a>, <a href="/web-llvm/docs/api/classes/llvm/ilist-node-impl/#af719fc783be6589465137d997701a432">llvm::ilist_node_impl&lt; OptionsT &gt;::getIterator</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#ac2e6c50683f73779b6b83effaf07ca30">llvm::getNumberOfParts</a>, <a href="/web-llvm/docs/api/classes/llvm/basicblock/#acf3c3aa4880eb60d00963ba93082c298">llvm::BasicBlock::getTerminator</a>, <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/vectorize/slpvectorizer-cpp/#a065bd87e0b855701cd8ca61aa05d4c50">getWidenedType</a>, <a href="/web-llvm/docs/api/files/lib/lib/support/md5-cpp/#ac0eafdc9ee161b71e7af98af736952fd">I</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#acd1cd968cb420c82d70926920fcdc7d7">llvm::is_contained</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a92ca992e52dddc420f4b069cae06dfbe">llvm::isa</a>, <a href="#a937e8e7cd2fb7c82d9512b69fc81b65b">isDeleted</a>, <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/support/debug-h/#a196897517069dda1bdb549e24468f7d7">LLVM_DEBUG</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a3d2cdc4a0db233678e7141c9d6ea3419">llvm::make_early_inc_range</a>, <a href="/web-llvm/docs/api/files/lib/lib/support/regcomp-c/#a0240ac851181b84ac374872dc5434ee4">N</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a9965a6249be879ba3d336a75a4f3efa7">llvm::PoisonMaskElem</a>, <a href="/web-llvm/docs/api/classes/llvm/smallvectortemplatebase/#af42bfbc067df27c19ee2fc859df58799">llvm::SmallVectorTemplateBase&lt; T, bool &gt;::push_back</a>, <a href="/web-llvm/docs/api/classes/llvm/smallvectorimpl/#a499ea32ca1b8d16cedfe01d1e5b08f29">llvm::SmallVectorImpl&lt; T &gt;::reserve</a>, <a href="/web-llvm/docs/api/classes/llvm/arrayref/#a85ffb6531d4cda988ea81f18d4e56fb7">llvm::ArrayRef&lt; T &gt;::size</a>, <a href="/web-llvm/docs/api/classes/llvm/smallvectortemplatecommon/#a1c479a8c434377c2b8cb056bdfdfc201">llvm::SmallVectorTemplateCommon&lt; T, typename &gt;::size</a> and <a href="/web-llvm/docs/api/namespaces/llvm/#a74cdbd1e4f731e7d7cd83461b8b1de0b">llvm::sort</a>.</p>

</div>
</div>

### registerNonVectorizableLoads() {#a30c194a6bf543ebc57f18dd7840a1ecf}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<div class="doxyMemberTemplate">template &lt;typename T&gt;</div>
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void llvm::slpvectorizer::BoUpSLP::registerNonVectorizableLoads (<a href="/web-llvm/docs/api/classes/llvm/arrayref">ArrayRef</a>&lt; T * &gt; VL)</td>
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

<p>Registers non-vectorizable sequence of loads.</p>

<p>Definition at line 1644 of file <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/vectorize/slpvectorizer-cpp">SLPVectorizer.cpp</a>.</p>


<p>Reference <a href="/web-llvm/docs/api/namespaces/llvm/#a0e2e479cf4860dc8a00614e36ee3d5e9">llvm::hash_value</a>.</p>


<p>Referenced by <a href="#a91b0e07ff96232db2a91d6cfdf67a5e0">transformNodes</a>.</p>

</div>
</div>

### removeInstructionsAndOperands() {#aa8ccbcf19b9150f2872f794ecdc53d3e}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<div class="doxyMemberTemplate">template &lt;typename T&gt;</div>
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void llvm::slpvectorizer::BoUpSLP::removeInstructionsAndOperands (<a href="/web-llvm/docs/api/classes/llvm/arrayref">ArrayRef</a>&lt; T * &gt; DeadVals)</td>
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

<p>Remove instructions from the parent function and clear the operands of <span class="doxyComputerOutput">DeadVals</span> instructions, marking for deletion trivially dead operands.</p>

<p>Definition at line 2842 of file <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/vectorize/slpvectorizer-cpp">SLPVectorizer.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/namespaces/llvm/#a0d10fe510ced2849a8074fe81e5d04ce">llvm::all_of</a>, <a href="/web-llvm/docs/api/classes/llvm/smallvectorimpl/#a7efd1f0c1206d95e4fe01a9b49a57b82">llvm::SmallVectorImpl&lt; T &gt;::append</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/silowercontrolflow-cpp/#a4868c5d81c5ccc98c47aeab6244346a0">assert</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#ac4fc845f5ed92de63cd4474f128f5fc5">llvm::cast</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a3e627c32543ca70720c4270a8b11da3f">llvm::cast_or_null</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a22eeee01734061ac1b31ccd994c49eef">llvm::dyn_cast</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a3377eac88526e806d9d887c4a0ba2a73">llvm::dyn_cast_if_present</a>, <a href="/web-llvm/docs/api/classes/llvm/smallvectortemplatecommon/#ad9a3c7bc26b130377bbafc170b5f88a2">llvm::SmallVectorTemplateCommon&lt; T, typename &gt;::empty</a>, <a href="/web-llvm/docs/api/files/lib/lib/support/md5-cpp/#ac0eafdc9ee161b71e7af98af736952fd">I</a>, <a href="/web-llvm/docs/api/classes/llvm/detail/densesetimpl/#a1b0f3ebdced8fce4b22c6a63b25d9525">llvm::detail::DenseSetImpl&lt; ValueT, MapTy, ValueInfoT &gt;::insert</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a627b2f86ac433d829482d5a5a0f50668">llvm::isInstructionTriviallyDead</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a7dc3069afa2ce5ea62ac2eb183e51c00">llvm::none_of</a>, <a href="/web-llvm/docs/api/classes/llvm/smallvectorimpl/#a0c8ffe664a36e30d49c84d0aded2fe08">llvm::SmallVectorImpl&lt; T &gt;::pop_back_val</a>, <a href="/web-llvm/docs/api/classes/llvm/smallvectortemplatebase/#af42bfbc067df27c19ee2fc859df58799">llvm::SmallVectorTemplateBase&lt; T, bool &gt;::push_back</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a26be1141b23850a2b4eb78021d99e862">llvm::salvageDebugInfo</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/mips/mips16isellowering-cpp/#a0acb682b8260ab1c60b918599864e2e5">T</a>, <a href="/web-llvm/docs/api/classes/llvm/value/#a9d7de807ebdfe1819df3ff6cb0f16158">llvm::Value::use_empty</a> and <a href="/web-llvm/docs/api/namespaces/llvm/#a845142f96a84f067cb6bf639e37980d0">llvm::wouldInstructionBeTriviallyDead</a>.</p>

</div>
</div>

### reorderBottomToTop() {#a2eb73a15ea2a5105bd2cec95863d7113}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void BoUpSLP::reorderBottomToTop (bool IgnoreReorder=false)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Reorders the current graph to the most profitable order starting from leaves to the root.</p>


<p>It allows to rotate small subgraphs and reduce the number of reshuffles if the leaf nodes use the same order. In this case we can merge the orders and just shuffle user node instead of shuffling its operands. Plus, even the leaf nodes have different orders, it allows to sink reordering in the graph closer to the root node and merge it later during analysis.</p>


<p>Definition at line 1558 of file <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/vectorize/slpvectorizer-cpp">SLPVectorizer.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/demangle/itaniumdemangle-h/#a536e22898d28a9340a4204407a75ad5d">AbstractManglingParser&lt; Derived, Alloc &gt;::NumOps</a>, <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/demangle/itaniumdemangle-h/#a926d7ce2143863b7a2afda0fca4d2b65">AbstractManglingParser&lt; Derived, Alloc &gt;::Ops</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a0d10fe510ced2849a8074fe81e5d04ce">llvm::all_of</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/silowercontrolflow-cpp/#a4868c5d81c5ccc98c47aeab6244346a0">assert</a>, <a href="/web-llvm/docs/api/classes/llvm/smallvectortemplatecommon/#a8a045d250952c0867382a9840ee18fdf">llvm::SmallVectorTemplateCommon&lt; T, typename &gt;::begin</a>, <a href="/web-llvm/docs/api/classes/llvm/smallptrsetimplbase/#a16413f1a88d8baca228d0a1b4cc0bfc6">llvm::SmallPtrSetImplBase::clear</a>, <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/vectorize/slpvectorizer-cpp/#a4bbe053c13b73cf6ed1276f66b615fc7">combineOrders</a>, <a href="/web-llvm/docs/api/classes/llvm/detail/densesetimpl/#ad409c2de8502b94c8a0b1193307c63b6">llvm::detail::DenseSetImpl&lt; ValueT, MapTy, ValueInfoT &gt;::contains</a>, <a href="/web-llvm/docs/api/classes/llvm/detail/densesetimpl/#afe504aa31a6a354cec13f5b32d0b1d9d">llvm::detail::DenseSetImpl&lt; ValueT, MapTy, ValueInfoT &gt;::count</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#ac214df91cdc242f4710ea5a93939c678">llvm::count_if</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#aa20539e89704d20b98b97e9c3feac934">llvm::Data</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a02981de53fb6ffd384d39addc4d25f37">llvm::drop_begin</a>, <a href="/web-llvm/docs/api/structs/llvm/slpvectorizer/boupslp/edgeinfo/#a014a11a5b7363e38bdd5c5c04302c6b8">llvm::slpvectorizer::BoUpSLP::EdgeInfo::EdgeIdx</a>, <a href="/web-llvm/docs/api/classes/llvm/setvector/#ac178f4fc4e4a0642610c374256b9fb27">llvm::SetVector&lt; T, Vector, Set, N &gt;::empty</a>, <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/vectorize/slpvectorizer-cpp/#ae203ebf95f0711b6d63e3672baeaf669">fixupOrderingIndices</a>, <a href="#a1897e235929f1961872707de9a400031aad22c799930d644e8468fe44c0312d53">Gather</a>, <a href="#ab2c5c3c0b3cd0db8b0692df8f66b6264">getReorderingData</a>, <a href="/web-llvm/docs/api/files/lib/lib/support/md5-cpp/#ac0eafdc9ee161b71e7af98af736952fd">I</a>, <a href="/web-llvm/docs/api/classes/llvm/detail/densesetimpl/#a1b0f3ebdced8fce4b22c6a63b25d9525">llvm::detail::DenseSetImpl&lt; ValueT, MapTy, ValueInfoT &gt;::insert</a>, <a href="/web-llvm/docs/api/classes/llvm/setvector/#af34eb71cc483e84d2eca80575cb9ccde">llvm::SetVector&lt; T, Vector, Set, N &gt;::insert</a>, <a href="/web-llvm/docs/api/classes/llvm/smallptrsetimpl/#a9d834ae3da8c62c2b668dada51335eb0">llvm::SmallPtrSetImpl&lt; PtrType &gt;::insert</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a6f0917bf2ae18fac81fea6bf7e887115">llvm::inversePermutation</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a92ca992e52dddc420f4b069cae06dfbe">llvm::isa</a>, <a href="#ae420d94473ac8cb96686184a551f6097">isIdentityOrder</a>, <a href="/web-llvm/docs/api/files/lib/lib/option/option-cpp/#a04665169063c8ca1f2ea96c27fc7c2b2">P</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a9965a6249be879ba3d336a75a4f3efa7">llvm::PoisonMaskElem</a>, <a href="/web-llvm/docs/api/classes/llvm/smallvectortemplatebase/#af42bfbc067df27c19ee2fc859df58799">llvm::SmallVectorTemplateBase&lt; T, bool &gt;::push_back</a>, <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/vectorize/slpvectorizer-cpp/#a633db91afb11db086004de9e3eb37217">reorderOrder</a>, <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/vectorize/slpvectorizer-cpp/#a4a3e80130d3f25468190ba343064b37e">reorderReuses</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a14c12bda1f5a9beed612b00f3f98b888">llvm::reorderScalars</a>, <a href="/web-llvm/docs/api/classes/llvm/arrayref/#a85ffb6531d4cda988ea81f18d4e56fb7">llvm::ArrayRef&lt; T &gt;::size</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a74cdbd1e4f731e7d7cd83461b8b1de0b">llvm::sort</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a615619b0b2879029152b9a20e96624bc">llvm::transform</a>, <a href="/web-llvm/docs/api/files/lib/lib/analysis/ivusers-cpp/#a4e5b9edb51eec9dbca592075eb64dfcb">Users</a> and <a href="/web-llvm/docs/api/structs/llvm/slpvectorizer/boupslp/edgeinfo/#ac3d3c4a713b6bbd7165cd4b872252b79">llvm::slpvectorizer::BoUpSLP::EdgeInfo::UserTE</a>.</p>

</div>
</div>

### reorderTopToBottom() {#a1bc3cc02c0dc6dcb9ad315b7755475e7}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void BoUpSLP::reorderTopToBottom ()</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Reorders the current graph to the most profitable order starting from the root node to the leaf nodes.</p>


<p>The best order is chosen only from the nodes of the same size (vectorization factor). Smaller nodes are considered parts of subgraph with smaller VF and they are reordered independently. We can make it because we still need to extend smaller nodes to the wider VF and we can merge reordering shuffles with the widening shuffles.</p>


<p>Definition at line 1549 of file <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/vectorize/slpvectorizer-cpp">SLPVectorizer.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/vectorize/slpvectorizer-cpp/#ae122b7b9960cfd970b1d5c0d83f22039">addMask</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a0d10fe510ced2849a8074fe81e5d04ce">llvm::all_of</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/silowercontrolflow-cpp/#a4868c5d81c5ccc98c47aeab6244346a0">assert</a>, <a href="/web-llvm/docs/api/classes/llvm/smallvectortemplatecommon/#a8a045d250952c0867382a9840ee18fdf">llvm::SmallVectorTemplateCommon&lt; T, typename &gt;::begin</a>, <a href="/web-llvm/docs/api/files/lib/lib/debuginfod/httpclient-cpp/#a0b91b2b50d54e38aa1e8e31e56c31357">Cleanup</a>, <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/vectorize/slpvectorizer-cpp/#a4bbe053c13b73cf6ed1276f66b615fc7">combineOrders</a>, <a href="/web-llvm/docs/api/classes/llvm/densemapbase/#a53408c95a7bfb5443b43fb2134c3eb23">llvm::DenseMapBase&lt; DerivedT, KeyT, ValueT, KeyInfoT, BucketT &gt;::count</a>, <a href="/web-llvm/docs/api/classes/llvm/arrayref/#ac835b8735b1b2faec0efdca236e37d94">llvm::ArrayRef&lt; T &gt;::empty</a>, <a href="/web-llvm/docs/api/classes/llvm/densemapbase/#a49c487a9395a6c384be8544cfb2cfccf">llvm::DenseMapBase&lt; DerivedT, KeyT, ValueT, KeyInfoT, BucketT &gt;::empty</a>, <a href="/web-llvm/docs/api/classes/llvm/smallvectortemplatecommon/#ad9a3c7bc26b130377bbafc170b5f88a2">llvm::SmallVectorTemplateCommon&lt; T, typename &gt;::empty</a>, <a href="/web-llvm/docs/api/classes/llvm/densemapbase/#a65520b9c67759099e313d0f4e7b5ff9e">llvm::DenseMapBase&lt; DerivedT, KeyT, ValueT, KeyInfoT, BucketT &gt;::end</a>, <a href="/web-llvm/docs/api/classes/llvm/densemapbase/#a1eb8504bab5f794778d82db6ac829923">llvm::DenseMapBase&lt; DerivedT, KeyT, ValueT, KeyInfoT, BucketT &gt;::erase</a>, <a href="/web-llvm/docs/api/classes/llvm/densemapbase/#a0c047f127ed4380a6f383d70bec4eb94">llvm::DenseMapBase&lt; DerivedT, KeyT, ValueT, KeyInfoT, BucketT &gt;::find</a>, <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/vectorize/slpvectorizer-cpp/#ae203ebf95f0711b6d63e3672baeaf669">fixupOrderingIndices</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a0b2a153b655ed78a07468297eb4c6256">llvm::for_each</a>, <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/vectorize/slpvectorizer-cpp/#a4617b6f7b2916249d12f30bc81a17855">getAltInstrMask</a>, <a href="#ab2c5c3c0b3cd0db8b0692df8f66b6264">getReorderingData</a>, <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/vectorize/slpvectorizer-cpp/#a065bd87e0b855701cd8ca61aa05d4c50">getWidenedType</a>, <a href="/web-llvm/docs/api/files/lib/lib/support/md5-cpp/#ac0eafdc9ee161b71e7af98af736952fd">I</a>, <a href="/web-llvm/docs/api/classes/llvm/densemapbase/#adb33f3ede2f5bfc9b3ee658aaf648492">llvm::DenseMapBase&lt; DerivedT, KeyT, ValueT, KeyInfoT, BucketT &gt;::insert</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a6f0917bf2ae18fac81fea6bf7e887115">llvm::inversePermutation</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a92ca992e52dddc420f4b069cae06dfbe">llvm::isa</a>, <a href="#ae420d94473ac8cb96686184a551f6097">isIdentityOrder</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a1af45c4dc83c083c5ae914d96fd3ce96">llvm::make_scope_exit</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a7dc3069afa2ce5ea62ac2eb183e51c00">llvm::none_of</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a9965a6249be879ba3d336a75a4f3efa7">llvm::PoisonMaskElem</a>, <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/vectorize/slpvectorizer-cpp/#adbff8697d64e4ee139aa777b68999872">RecursionMaxDepth</a>, <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/vectorize/slpvectorizer-cpp/#a633db91afb11db086004de9e3eb37217">reorderOrder</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a14c12bda1f5a9beed612b00f3f98b888">llvm::reorderScalars</a>, <a href="/web-llvm/docs/api/classes/llvm/arrayref/#a85ffb6531d4cda988ea81f18d4e56fb7">llvm::ArrayRef&lt; T &gt;::size</a>, <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/vectorize/slpvectorizer-cpp/#a8b6f16f98498a168902dd2d5cd8f9462">SLPReVec</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a615619b0b2879029152b9a20e96624bc">llvm::transform</a> and <a href="/web-llvm/docs/api/classes/llvm/densemapbase/#a1a245b31aced1374f28f45d2b297f402">llvm::DenseMapBase&lt; DerivedT, KeyT, ValueT, KeyInfoT, BucketT &gt;::try_emplace</a>.</p>

</div>
</div>

### transformNodes() {#a91b0e07ff96232db2a91d6cfdf67a5e0}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void BoUpSLP::transformNodes ()</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Transforms graph nodes to target specific representations, if profitable.</p>

<p>Definition at line 1474 of file <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/vectorize/slpvectorizer-cpp">SLPVectorizer.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/namespaces/llvm/#a0d10fe510ced2849a8074fe81e5d04ce">llvm::all_of</a>, <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/vectorize/slpvectorizer-cpp/#a7568c08b526dbf7f7b5402f3eb605b55">allConstant</a>, <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/vectorize/slpvectorizer-cpp/#abd5114d6b451e9ca85a36fc3f19f76c4">allSameBlock</a>, <a href="#a51b254a1b9cc02e8f8790cdd85b36a7f">analyzedReductionVals</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a61d13d6824ec46c31260a4fd0997eda0">llvm::any_of</a>, <a href="#a44ad06e18d7d3783f20435a9f159a763">areKnownNonVectorizableLoads</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#ab9c6b351507d3c0730f4290919d43a12">llvm::ArrayRef</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/silowercontrolflow-cpp/#a4868c5d81c5ccc98c47aeab6244346a0">assert</a>, <a href="/web-llvm/docs/api/classes/llvm/arrayref/#a291ac49156942529f159a9ec003cc25f">llvm::ArrayRef&lt; T &gt;::back</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a323137971325611ddc1b899b00b8aaa0">llvm::canConvertToMinOrMaxIntrinsic</a>, <a href="#a496356f8335c794a9b365488ed263ead">canVectorizeLoads</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#ac4fc845f5ed92de63cd4474f128f5fc5">llvm::cast</a>, <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/vectorize/slpvectorizer-cpp/#ae06eb06e1d6ba6b5e8d319eef5d16280">computeCommonAlignment</a>, <a href="/web-llvm/docs/api/files/lib/lib/analysis/costmodel-cpp/#a162d8b2b3865594d1e14d828d2b8336a">CostKind</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#ab1772fd431decccb7926d484ea223db7">llvm::count</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#ac214df91cdc242f4710ea5a93939c678">llvm::count_if</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a22eeee01734061ac1b31ccd994c49eef">llvm::dyn_cast</a>, <a href="/web-llvm/docs/api/classes/llvm/smallvectorimpl/#a396fcfee6914c76974b73c3d203da6a5">llvm::SmallVectorImpl&lt; T &gt;::emplace_back</a>, <a href="/web-llvm/docs/api/classes/llvm/mapvector/#a8da97c44f514ad1ae9ccf4518b0f88aa">llvm::MapVector&lt; KeyT, ValueT, MapType, VectorType &gt;::empty</a>, <a href="/web-llvm/docs/api/classes/llvm/smallvectortemplatecommon/#ad9a3c7bc26b130377bbafc170b5f88a2">llvm::SmallVectorTemplateCommon&lt; T, typename &gt;::empty</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#ac78c09ae232b2ce188ff590d51e3c268">llvm::find_if</a>, <a href="#af3dd2dd5c72b919c173c6bc31d7c3ac3">findBestRootPair</a>, <a href="/web-llvm/docs/api/classes/llvm/arrayref/#a721fc555cb3d8dc2a1a680dcc2ce69b2">llvm::ArrayRef&lt; T &gt;::front</a>, <a href="#a1897e235929f1961872707de9a400031aad22c799930d644e8468fe44c0312d53">Gather</a>, <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/vectorize/slpvectorizer-cpp/#a9e4f7b81913ac2176cac1eaa2b66a0b7">gatherPossiblyVectorizableLoads</a>, <a href="#a45d4fa202493524e9b22c245f06ef855">getCanonicalGraphSize</a>, <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/vectorize/slpvectorizer-cpp/#abd93b259f88f77258d2428448d9f8032">getFloorFullVectorNumberOfElements</a>, <a href="#aacc65a747c158a620f90f612a673a506">getMinVF</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#ac2e6c50683f73779b6b83effaf07ca30">llvm::getNumberOfParts</a>, <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/vectorize/slpvectorizer-cpp/#acb2c6a8dafac1cdf8927e67b28baab1c">getSameOpcode</a>, <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/vectorize/slpvectorizer-cpp/#a3c4c7b26972597220296eab6450669b0">getShuffleCost</a>, <a href="#a3a11daf8d89c135162dd6623f5bd164f">getTreeSize</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a3b1c5788b85ffa254be0e834edf5cf8f">llvm::getUnderlyingObject</a>, <a href="#a54f30c8bea3912d1d0f347626c395be6">getVectorElementSize</a>, <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/vectorize/slpvectorizer-cpp/#a065bd87e0b855701cd8ca61aa05d4c50">getWidenedType</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a7d6443d726d7d8cdb827119e6f8f7819">llvm::hasFullVectorsOrPowerOf2</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a6f0917bf2ae18fac81fea6bf7e887115">llvm::inversePermutation</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a92ca992e52dddc420f4b069cae06dfbe">llvm::isa</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a445c0cf40cd4a28c8b53579dfab9a193">llvm::IsaPred</a>, <a href="#a937e8e7cd2fb7c82d9512b69fc81b65b">isDeleted</a>, <a href="/web-llvm/docs/api/classes/llvm/shufflevectorinst/#af9582c096b5d287b663ec8ca4550aa72">llvm::ShuffleVectorInst::isInterleaveMask</a>, <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/vectorize/slpvectorizer-cpp/#afa640d51b943ce0396e7131bf2352f8a">isReverseOrder</a>, <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/scalar/lowermatrixintrinsics-cpp/#a6a2164e5aeea9c3e9a02eab3747efd8c">isSplat</a>, <a href="#adef9fad96a0d90c56a892520edbdb749">isVectorized</a>, <a href="/web-llvm/docs/api/namespaces/llvm/intrinsic/#a35fedf4db6d756bd82501607f93c1e79aab5fb650050f184fa7c19c26abde5226">llvm::Intrinsic::not_intrinsic</a>, <a href="/web-llvm/docs/api/files/lib/lib/option/option-cpp/#a04665169063c8ca1f2ea96c27fc7c2b2">P</a>, <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/vectorize/slpvectorizer-cpp/#adbff8697d64e4ee139aa777b68999872">RecursionMaxDepth</a>, <a href="#a30c194a6bf543ebc57f18dd7840a1ecf">registerNonVectorizableLoads</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a14c12bda1f5a9beed612b00f3f98b888">llvm::reorderScalars</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a6b0ac1fa4f05de76413c5e0ca6334035">llvm::reverse</a>, <a href="#a1897e235929f1961872707de9a400031a705aab2193971a020dd6e9b6bfc0a160">ScatterVectorize</a>, <a href="/web-llvm/docs/api/classes/llvm/slpvectorizer/boupslp/lookaheadheuristics/#a9bcb4a0dcff036fbe065d2d3fc070e0a">llvm::slpvectorizer::BoUpSLP::LookAheadHeuristics::ScoreSplatLoads</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#adc4eb8be6f7a12ede962987fb9cabb47">llvm::seq</a>, <a href="/web-llvm/docs/api/classes/llvm/arrayref/#a85ffb6531d4cda988ea81f18d4e56fb7">llvm::ArrayRef&lt; T &gt;::size</a>, <a href="/web-llvm/docs/api/classes/llvm/targettransforminfo/#af46433d0e36d3f80afc3a8c67b5c53ecaea788d98147161f25d5adc3ec6ce7e1f">llvm::TargetTransformInfo::SK_Reverse</a>, <a href="/web-llvm/docs/api/classes/llvm/arrayref/#aebf6ca7590d4f766b894044015a0fa31">llvm::ArrayRef&lt; T &gt;::slice</a>, <a href="/web-llvm/docs/api/classes/llvm/targettransforminfo/#ac44f6b9fdbb5f9cc199f8329cb0b272ca022565d444ccf496c0414bccefbcd9c8">llvm::TargetTransformInfo::TCC_Expensive</a> and <a href="/web-llvm/docs/api/classes/llvm/targettransforminfo/#a706f223f760b55668fbae74202b816bba59b32ea7b6f10564abd40ad90602ca5b">llvm::TargetTransformInfo::TCK_RecipThroughput</a>.</p>

</div>
</div>

### vectorizeTree() {#af30798297200e0134c0a54cfdfa6c6cd}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">Value * BoUpSLP::vectorizeTree ()</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Vectorize the tree that starts with the elements in <span class="doxyComputerOutput">VL</span>.</p>


<p>Returns the vectorized root.</p>


<p>Definition at line 1387 of file <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/vectorize/slpvectorizer-cpp">SLPVectorizer.cpp</a>.</p>


<p>Reference <a href="#af30798297200e0134c0a54cfdfa6c6cd">vectorizeTree</a>.</p>


<p>Referenced by <a href="#af30798297200e0134c0a54cfdfa6c6cd">vectorizeTree</a> and <a href="#a99b79343fdc586cce804ebabf3d419e2">vectorizeTree</a>.</p>

</div>
</div>

### vectorizeTree() {#a99b79343fdc586cce804ebabf3d419e2}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">Value * BoUpSLP::vectorizeTree (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="#a8d0bc81039d5e2c5c855590d222c0fae">ExtraValueToDebugLocsMap</a> &amp; ExternallyUsedValues, <a href="/web-llvm/docs/api/classes/llvm/instruction">Instruction</a> * ReductionRoot=nullptr)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Vectorize the tree but with the list of externally used values <span class="doxyComputerOutput">ExternallyUsedValues</span>.</p>


<p>Values in this <a href="/web-llvm/docs/api/classes/llvm/mapvector">MapVector</a> can be replaced but the generated extractvalue instructions.</p>


<p>Definition at line 1393 of file <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/vectorize/slpvectorizer-cpp">SLPVectorizer.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/classes/boupslp/shuffleinstructionbuilder/#ac9d11e9f66eb3617827801cb7f0f6619">llvm::slpvectorizer::BoUpSLP::ShuffleInstructionBuilder::add</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a61d13d6824ec46c31260a4fd0997eda0">llvm::any_of</a>, <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/vectorize/slpvectorizer-cpp/#abe6927d96b3815417479246b5afc732e">areTwoInsertFromSameBuildVector</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/silowercontrolflow-cpp/#a4868c5d81c5ccc98c47aeab6244346a0">assert</a>, <a href="/web-llvm/docs/api/classes/llvm/arrayref/#a291ac49156942529f159a9ec003cc25f">llvm::ArrayRef&lt; T &gt;::back</a>, <a href="/web-llvm/docs/api/classes/llvm/smallvectortemplatecommon/#acd9e771a3296c6b24146955754620557">llvm::SmallVectorTemplateCommon&lt; T, typename &gt;::back</a>, <a href="/web-llvm/docs/api/classes/llvm/smallvectortemplatecommon/#a8a045d250952c0867382a9840ee18fdf">llvm::SmallVectorTemplateCommon&lt; T, typename &gt;::begin</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#ac4fc845f5ed92de63cd4474f128f5fc5">llvm::cast</a>, <a href="/web-llvm/docs/api/classes/llvm/detail/densesetimpl/#ad409c2de8502b94c8a0b1193307c63b6">llvm::detail::DenseSetImpl&lt; ValueT, MapTy, ValueInfoT &gt;::contains</a>, <a href="/web-llvm/docs/api/classes/llvm/detail/densesetimpl/#afe504aa31a6a354cec13f5b32d0b1d9d">llvm::detail::DenseSetImpl&lt; ValueT, MapTy, ValueInfoT &gt;::count</a>, <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/vectorize/slpvectorizer-cpp/#ae3a4c284255a153d29ddcbd05bcf5345">createExtractVector</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#aa20539e89704d20b98b97e9c3feac934">llvm::Data</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a7c46c742c31be54870e2038048e6b391">llvm::dbgs</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a22eeee01734061ac1b31ccd994c49eef">llvm::dyn_cast</a>, <a href="/web-llvm/docs/api/classes/llvm/smallvectorimpl/#a396fcfee6914c76974b73c3d203da6a5">llvm::SmallVectorImpl&lt; T &gt;::emplace_back</a>, <a href="/web-llvm/docs/api/classes/llvm/densemapbase/#a65520b9c67759099e313d0f4e7b5ff9e">llvm::DenseMapBase&lt; DerivedT, KeyT, ValueT, KeyInfoT, BucketT &gt;::end</a>, <a href="/web-llvm/docs/api/classes/llvm/smallvectortemplatecommon/#a075e34e98605d0e7c289763a104869ac">llvm::SmallVectorTemplateCommon&lt; T, typename &gt;::end</a>, <a href="#ab93aab6d000a610c36f69bb84137b2b8">eraseInstruction</a>, <a href="/web-llvm/docs/api/classes/boupslp/shuffleinstructionbuilder/#adedeebdfb49d04e53d9c73abfa8a429f">llvm::slpvectorizer::BoUpSLP::ShuffleInstructionBuilder::finalize</a>, <a href="/web-llvm/docs/api/classes/llvm/densemapbase/#a0c047f127ed4380a6f383d70bec4eb94">llvm::DenseMapBase&lt; DerivedT, KeyT, ValueT, KeyInfoT, BucketT &gt;::find</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#ac78c09ae232b2ce188ff590d51e3c268">llvm::find_if</a>, <a href="/web-llvm/docs/api/classes/llvm/arrayref/#a721fc555cb3d8dc2a1a680dcc2ce69b2">llvm::ArrayRef&lt; T &gt;::front</a>, <a href="/web-llvm/docs/api/classes/llvm/smallvectortemplatecommon/#a58dc840fc84420b7f0b773794b8101c1">llvm::SmallVectorTemplateCommon&lt; T, typename &gt;::front</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a73257f51950d9ea50955e3fb9c724a25">llvm::get</a>, <a href="/web-llvm/docs/api/classes/llvm/poisonvalue/#a1bf08613fb664a2e377a9a72c59a6b66">llvm::PoisonValue::get</a>, <a href="/web-llvm/docs/api/files/lib/lib/ir/datalayout-cpp/#a0626211048d3157a84aac054ba7e894a">getElementIndex</a>, <a href="/web-llvm/docs/api/classes/llvm/ilist-node-impl/#af719fc783be6589465137d997701a432">llvm::ilist_node_impl&lt; OptionsT &gt;::getIterator</a>, <a href="/web-llvm/docs/api/classes/llvm/user/#aa0a2cb1582d1cec317bd205085469ca1">llvm::User::getOperand</a>, <a href="/web-llvm/docs/api/classes/llvm/ilist-detail/node-parent-access/#a7e19e7508415378ad9523e0339b23e22">llvm::ilist_detail::node_parent_access&lt; NodeTy, ParentTy &gt;::getParent</a>, <a href="/web-llvm/docs/api/classes/llvm/insertelementinst/#a49230ece74a48a27fb2bb1a4928b6e29">llvm::InsertElementInst::getType</a>, <a href="/web-llvm/docs/api/classes/llvm/value/#a0344a49526443edf90cc0aef3abd3337">llvm::Value::getType</a>, <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/vectorize/slpvectorizer-cpp/#a065bd87e0b855701cd8ca61aa05d4c50">getWidenedType</a>, <a href="/web-llvm/docs/api/files/lib/lib/support/md5-cpp/#ac0eafdc9ee161b71e7af98af736952fd">I</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/nvptx/nvvmintrrange-cpp/#ac5804672fc0850438d63caec770647f8">II</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a98c6256d0644613c6b5b3e2ef06ef5ce">llvm::InnerAnalysisManagerProxy&lt; AnalysisManagerT, IRUnitT, ExtraArgTs... &gt;::Key</a>, <a href="/web-llvm/docs/api/classes/llvm/detail/densesetimpl/#a1b0f3ebdced8fce4b22c6a63b25d9525">llvm::detail::DenseSetImpl&lt; ValueT, MapTy, ValueInfoT &gt;::insert</a>, <a href="/web-llvm/docs/api/classes/llvm/smallvectorimpl/#a94d23373106467003722f7d6c17b1528">llvm::SmallVectorImpl&lt; T &gt;::insert</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#acd1cd968cb420c82d70926920fcdc7d7">llvm::is_contained</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a92ca992e52dddc420f4b069cae06dfbe">llvm::isa</a>, <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/vectorize/slpvectorizer-cpp/#a405ff61e8571b58fecaa716540af108f">isFirstInsertElement</a>, <a href="/web-llvm/docs/api/classes/llvm/type/#a34ee40bb2f4f5ece47ef19e5f1f57e3c">llvm::Type::isIntOrIntVectorTy</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#ae7f4b5fbc0aa5c8204b9a4b06e070d75">llvm::isKnownNonNegative</a>, <a href="/web-llvm/docs/api/files/lib/lib/support/lib/support/blake3/blake3-impl-h/#a78823051d1dad34b9b3d8120112e674d">IV</a>, <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/support/debug-h/#a196897517069dda1bdb549e24468f7d7">LLVM_DEBUG</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#aea9b36512640e798bb1a7ac08dc2124d">llvm::mayHaveNonDefUseDependency</a>, <a href="/web-llvm/docs/api/classes/llvm/instruction/#a54507f01d7d06127068ee0663233511d">llvm::Instruction::moveAfter</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a99416758c13252bef45320a6ba6aa09c">llvm::MutableArrayRef</a>, <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/vectorize/slpvectorizer-cpp/#a67399cd92cbad7bcf7d0fbe417f779ec">performExtractsShuffleAction</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/amdgpurewriteundefforphi-cpp/#a2e83cb1bc3f5e8986cbd14575755a134">PHI</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a9965a6249be879ba3d336a75a4f3efa7">llvm::PoisonMaskElem</a>, <a href="/web-llvm/docs/api/classes/llvm/smallvectortemplatebase/#af42bfbc067df27c19ee2fc859df58799">llvm::SmallVectorTemplateBase&lt; T, bool &gt;::push_back</a>, <a href="/web-llvm/docs/api/classes/llvm/smallvectortemplatecommon/#a23aab542398091e1fcfd46b6006d64ac">llvm::SmallVectorTemplateCommon&lt; T, typename &gt;::rbegin</a>, <a href="/web-llvm/docs/api/classes/llvm/smallvectortemplatecommon/#ad696953257cf1c4e5bd12d02146e7287">llvm::SmallVectorTemplateCommon&lt; T, typename &gt;::rend</a>, <a href="/web-llvm/docs/api/classes/llvm/user/#a1600c7959045cb6b6a5f5a1d427ec67e">llvm::User::replaceUsesOfWith</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a6b0ac1fa4f05de76413c5e0ca6334035">llvm::reverse</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#adc4eb8be6f7a12ede962987fb9cabb47">llvm::seq</a>, <a href="/web-llvm/docs/api/classes/llvm/smallvectortemplatecommon/#a1c479a8c434377c2b8cb056bdfdfc201">llvm::SmallVectorTemplateCommon&lt; T, typename &gt;::size</a>, <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/vectorize/slpvectorizer-cpp/#a8b6f16f98498a168902dd2d5cd8f9462">SLPReVec</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a74cdbd1e4f731e7d7cd83461b8b1de0b">llvm::sort</a>, <a href="/web-llvm/docs/api/classes/llvm/densemapbase/#a1a245b31aced1374f28f45d2b297f402">llvm::DenseMapBase&lt; DerivedT, KeyT, ValueT, KeyInfoT, BucketT &gt;::try_emplace</a>, <a href="/web-llvm/docs/api/classes/llvm/user/#a282fa3e9586425313e0a954c18deee15">llvm::User::User</a>, <a href="/web-llvm/docs/api/classes/llvm/value/#a411cf3e3932f209ce3374cb31adc1da6">llvm::Value::users</a>, <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/vectorize/slpvectorizer-cpp/#a75df5de932994d1472ad3cda6a88cf21">UsesLimit</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#add480f2ed87faa59c16d4c01ffb4bf39a57dea6f5039281b7fee517fc43bf3110">llvm::Vector</a> and <a href="#af30798297200e0134c0a54cfdfa6c6cd">vectorizeTree</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Private Member Functions

### areAllUsersVectorized() {#a835c2380aa3fbc9ddeb4b919902e9838}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool BoUpSLP::areAllUsersVectorized (<a href="/web-llvm/docs/api/classes/llvm/instruction">Instruction</a> * I, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/smalldenseset">SmallDenseSet</a>&lt; <a href="/web-llvm/docs/api/classes/llvm/value">Value</a> * &gt; * VectorizedVals=nullptr)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Checks if all users of <span class="doxyComputerOutput">I</span> are the part of the vectorization tree.</p>

<p>Definition at line 3032 of file <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/vectorize/slpvectorizer-cpp">SLPVectorizer.cpp</a>.</p>

</div>
</div>

### areAltOperandsProfitable() {#a91b5e45f639db019ee95a7dda7997920}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool BoUpSLP::areAltOperandsProfitable (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> InstructionsState &amp; S, <a href="/web-llvm/docs/api/classes/llvm/arrayref">ArrayRef</a>&lt; <a href="/web-llvm/docs/api/classes/llvm/value">Value</a> * &gt; VL)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p><a href="/web-llvm/docs/api/namespaces/llvm/check">Check</a> that the operand node of alternate node does not generate buildvector sequence.</p>


<p>If it is, then probably not worth it to build alternate shuffle, if number of buildvector operands + alternate instruction &gt; than the number of buildvector instructions.</p>


<dl class="doxyParamsList">
<dt class="doxyParamsTableTitle">Parameters</dt>
<dd>
<table class="doxyParamsTable">
<tr class="doxyParamItem">
<td class="doxyParamItemName">S</td>
<td class="doxyParamItemDescription"><p>the instructions state of the analyzed values.</p></td>
</tr>
<tr class="doxyParamItem">
<td class="doxyParamItemName">VL</td>
<td class="doxyParamItemDescription"><p>list of the instructions with alternate opcodes.</p></td>
</tr>
</table>
</dd>
</dl>

<p>Definition at line 3744 of file <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/vectorize/slpvectorizer-cpp">SLPVectorizer.cpp</a>.</p>

</div>
</div>

### buildTree\_rec() {#a66f4bb98d9a5c179ff1e0e827713a120}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void BoUpSLP::buildTree_rec (<a href="/web-llvm/docs/api/classes/llvm/arrayref">ArrayRef</a>&lt; <a href="/web-llvm/docs/api/classes/llvm/value">Value</a> * &gt; Roots, unsigned Depth, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/structs/llvm/slpvectorizer/boupslp/edgeinfo">EdgeInfo</a> &amp; EI, unsigned InterleaveFactor=0)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>This is the recursive part of buildTree.</p>

<p>Definition at line 3058 of file <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/vectorize/slpvectorizer-cpp">SLPVectorizer.cpp</a>.</p>

</div>
</div>

### canFormVector() {#af11846ed705c63e33dfb2f214298bb0d}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool BoUpSLP::canFormVector (<a href="/web-llvm/docs/api/classes/llvm/arrayref">ArrayRef</a>&lt; <a href="/web-llvm/docs/api/classes/llvm/storeinst">StoreInst</a> * &gt; StoresVec, <a href="#a056d3cd46ef12f648e431fe9776451a1">OrdersType</a> &amp; ReorderIndices)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Helper for <span class="doxyComputerOutput">findExternalStoreUsersReorderIndices()</span>.</p>


<p>It checks if the stores in <span class="doxyComputerOutput">StoresVec</span> can form a vector instruction. If so it returns true and populates <span class="doxyComputerOutput">ReorderIndices</span> with the shuffle indices of the stores when compared to the sorted vector.</p>


<p>Definition at line 3199 of file <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/vectorize/slpvectorizer-cpp">SLPVectorizer.cpp</a>.</p>

</div>
</div>

### canReorderOperands() {#a9011f4a3aec07cbaa5c49e88399ea219}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool BoUpSLP::canReorderOperands (TreeEntry * UserTE, <a href="/web-llvm/docs/api/classes/llvm/smallvectorimpl">SmallVectorImpl</a>&lt; std::pair&lt; unsigned, TreeEntry * &gt; &gt; &amp; Edges, <a href="/web-llvm/docs/api/classes/llvm/arrayref">ArrayRef</a>&lt; TreeEntry * &gt; ReorderableGathers, <a href="/web-llvm/docs/api/classes/llvm/smallvectorimpl">SmallVectorImpl</a>&lt; TreeEntry * &gt; &amp; GatherOps)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p><a href="/web-llvm/docs/api/namespaces/llvm/check">Check</a> if the operands on the edges <span class="doxyComputerOutput">Edges</span> of the <span class="doxyComputerOutput">UserTE</span> allows reordering (i.e.</p>


<p>the operands can be reordered because they have only one user and reordarable).</p>


<dl class="doxyParamsList">
<dt class="doxyParamsTableTitle">Parameters</dt>
<dd>
<table class="doxyParamsTable">
<tr class="doxyParamItem">
<td class="doxyParamItemName">ReorderableGathers</td>
<td class="doxyParamItemDescription"><p>List of all gather nodes that require reordering (e.g., gather of extractlements or partially vectorizable loads).</p></td>
</tr>
<tr class="doxyParamItem">
<td class="doxyParamItemName">GatherOps</td>
<td class="doxyParamItemDescription"><p>List of gather operand nodes for <span class="doxyComputerOutput">UserTE</span> that require reordering, subset of <span class="doxyComputerOutput">NonVectorized</span>.</p></td>
</tr>
</table>
</dd>
</dl>

<p>Definition at line 2987 of file <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/vectorize/slpvectorizer-cpp">SLPVectorizer.cpp</a>.</p>

</div>
</div>

### canReuseExtract() {#ad442d7323a88e9bbb875e109448bf172}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool BoUpSLP::canReuseExtract (<a href="/web-llvm/docs/api/classes/llvm/arrayref">ArrayRef</a>&lt; <a href="/web-llvm/docs/api/classes/llvm/value">Value</a> * &gt; VL, <a href="/web-llvm/docs/api/classes/llvm/smallvectorimpl">SmallVectorImpl</a>&lt; unsigned &gt; &amp; CurrentOrder, bool ResizeAllowed=false)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">




<dl class="doxySectionUser">
<dt>Returns</dt>
<dd><p>true if the ExtractElement/ExtractValue instructions in <span class="doxyComputerOutput">VL</span> can be vectorized to use the original vector (or aggregate "bitcast" to a vector) and sets <span class="doxyComputerOutput">CurrentOrder</span> to the identity permutation; otherwise returns false, setting <span class="doxyComputerOutput">CurrentOrder</span> to either an empty vector or a non-identity permutation that allows to reuse extract instructions.</p></dd>
</dl>


<dl class="doxyParamsList">
<dt class="doxyParamsTableTitle">Parameters</dt>
<dd>
<table class="doxyParamsTable">
<tr class="doxyParamItem">
<td class="doxyParamItemName">ResizeAllowed</td>
<td class="doxyParamItemDescription"><p>indicates whether it is allowed to handle subvector extract order.</p></td>
</tr>
</table>
</dd>
</dl>

<p>Definition at line 3068 of file <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/vectorize/slpvectorizer-cpp">SLPVectorizer.cpp</a>.</p>

</div>
</div>

### collectUserStores() {#ad078900b5c7804535baf9e40fda2881b}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">SmallVector&lt; SmallVector&lt; StoreInst * &gt; &gt; BoUpSLP::collectUserStores (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> BoUpSLP::TreeEntry * TE)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Helper for <span class="doxyComputerOutput">findExternalStoreUsersReorderIndices()</span>.</p>


<p>It iterates over the users of <span class="doxyComputerOutput">TE</span> and collects the stores. It returns the map from the store pointers to the collected stores.</p>


<p>Definition at line 3193 of file <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/vectorize/slpvectorizer-cpp">SLPVectorizer.cpp</a>.</p>

</div>
</div>

### collectValuesToDemote() {#a03b2575be4eac0913a5d94935a1728bb}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool BoUpSLP::collectValuesToDemote (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> TreeEntry &amp; E, bool IsProfitableToDemoteRoot, unsigned &amp; BitWidth, <a href="/web-llvm/docs/api/classes/llvm/smallvectorimpl">SmallVectorImpl</a>&lt; unsigned &gt; &amp; ToDemote, <a href="/web-llvm/docs/api/classes/llvm/denseset">DenseSet</a>&lt; <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> TreeEntry * &gt; &amp; Visited, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/smalldenseset">SmallDenseSet</a>&lt; unsigned, 8 &gt; &amp; NodesToKeepBWs, unsigned &amp; MaxDepthLevel, bool &amp; IsProfitableToDemote, bool IsTruncRoot)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Determine if a node <span class="doxyComputerOutput">E</span> in can be demoted to a smaller type with a truncation.</p>


<p>We collect the entries that will be demoted in ToDemote.</p>


<dl class="doxyParamsList">
<dt class="doxyParamsTableTitle">Parameters</dt>
<dd>
<table class="doxyParamsTable">
<tr class="doxyParamItem">
<td class="doxyParamItemName">E</td>
<td class="doxyParamItemDescription"><p><a href="/web-llvm/docs/api/classes/node">Node</a> for analysis</p></td>
</tr>
<tr class="doxyParamItem">
<td class="doxyParamItemName">ToDemote</td>
<td class="doxyParamItemDescription"><p>indices of the nodes to be demoted.</p></td>
</tr>
</table>
</dd>
</dl>

<p>Definition at line 2973 of file <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/vectorize/slpvectorizer-cpp">SLPVectorizer.cpp</a>.</p>

</div>
</div>

### createBuildVector() {#a7190a8565c844f810d43ed05d7ad6573}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">Value * BoUpSLP::createBuildVector (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> TreeEntry * E, <a href="/web-llvm/docs/api/classes/llvm/type">Type</a> * ScalarTy, bool PostponedPHIs)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Create a new vector from a list of scalar values.</p>


<p>Produces a sequence which exploits values reused across lanes, and arranges the inserts for ease of later optimization.</p>


<p>Definition at line 3100 of file <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/vectorize/slpvectorizer-cpp">SLPVectorizer.cpp</a>.</p>

</div>
</div>

### dumpTreeCosts() {#a90a5dba433e854f5ada067fbab531dc6}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void llvm::slpvectorizer::BoUpSLP::dumpTreeCosts (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> TreeEntry * E, <a href="/web-llvm/docs/api/classes/llvm/instructioncost">InstructionCost</a> ReuseShuffleCost, <a href="/web-llvm/docs/api/classes/llvm/instructioncost">InstructionCost</a> VecCost, <a href="/web-llvm/docs/api/classes/llvm/instructioncost">InstructionCost</a> ScalarCost, <a href="/web-llvm/docs/api/classes/llvm/stringref">StringRef</a> Banner)</td>
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



<p>Definition at line 3584 of file <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/vectorize/slpvectorizer-cpp">SLPVectorizer.cpp</a>.</p>

</div>
</div>

### dumpVectorizableTree() {#a088274764ebab0b22a089cd9948e7d5b}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">LLVM_DUMP_METHOD void llvm::slpvectorizer::BoUpSLP::dumpVectorizableTree ()</td>
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

<p>Debug printer.</p>

<p>Definition at line 3720 of file <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/vectorize/slpvectorizer-cpp">SLPVectorizer.cpp</a>.</p>

</div>
</div>

### findExternalStoreUsersReorderIndices() {#a3561aceaf1691c808ab34d1609bcda8f}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">SmallVector&lt; BoUpSLP::OrdersType, 1 &gt; BoUpSLP::findExternalStoreUsersReorderIndices (TreeEntry * TE)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Iterates through the users of <span class="doxyComputerOutput">TE</span>, looking for scalar stores that can be potentially vectorized in a future SLP-tree.</p>


<p>If found, it keeps track of their order and builds an order index vector for each store bundle. It returns all these order vectors found. We run this after the tree has formed, otherwise we may come across user instructions that are not yet in the tree.</p>


<p>Definition at line 3209 of file <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/vectorize/slpvectorizer-cpp">SLPVectorizer.cpp</a>.</p>

</div>
</div>

### gather() {#ad85f77b2e5e94d0be46613351b0c6765}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">Value * BoUpSLP::gather (<a href="/web-llvm/docs/api/classes/llvm/arrayref">ArrayRef</a>&lt; <a href="/web-llvm/docs/api/classes/llvm/value">Value</a> * &gt; VL, <a href="/web-llvm/docs/api/classes/llvm/value">Value</a> * Root, <a href="/web-llvm/docs/api/classes/llvm/type">Type</a> * ScalarTy, <a href="/web-llvm/docs/api/classes/llvm/function-ref">function_ref</a>&lt; <a href="/web-llvm/docs/api/classes/llvm/value">Value</a> *(<a href="/web-llvm/docs/api/classes/llvm/value">Value</a> *, <a href="/web-llvm/docs/api/classes/llvm/value">Value</a> *, <a href="/web-llvm/docs/api/classes/llvm/arrayref">ArrayRef</a>&lt; int &gt;)&gt; CreateShuffle)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">




<dl class="doxySectionUser">
<dt>Returns</dt>
<dd><p>a vector from a collection of scalars in <span class="doxyComputerOutput">VL</span>. if <span class="doxyComputerOutput">Root</span> is not specified, the starting vector value is poison.</p></dd>
</dl>


<p>Definition at line 3174 of file <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/vectorize/slpvectorizer-cpp">SLPVectorizer.cpp</a>.</p>

</div>
</div>

### getCastContextHint() {#aa5214603d52de0ae6ac4cc2b0a001d81}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">TTI::CastContextHint BoUpSLP::getCastContextHint (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> TreeEntry &amp; TE)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">




<dl class="doxySectionUser">
<dt>Returns</dt>
<dd><p>Cast context for the given graph node.</p></dd>
</dl>


<p>Definition at line 3050 of file <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/vectorize/slpvectorizer-cpp">SLPVectorizer.cpp</a>.</p>

</div>
</div>

### getEntryCost() {#ad63e623a5637db5d71c45c9378a20138}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">InstructionCost BoUpSLP::getEntryCost (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> TreeEntry * E, <a href="/web-llvm/docs/api/classes/llvm/arrayref">ArrayRef</a>&lt; <a href="/web-llvm/docs/api/classes/llvm/value">Value</a> * &gt; VectorizedVals, <a href="/web-llvm/docs/api/classes/llvm/smallptrsetimpl">SmallPtrSetImpl</a>&lt; <a href="/web-llvm/docs/api/classes/llvm/value">Value</a> * &gt; &amp; CheckedExtracts)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">




<dl class="doxySectionUser">
<dt>Returns</dt>
<dd><p>the cost of the vectorizable entry.</p></dd>
</dl>


<p>Definition at line 3053 of file <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/vectorize/slpvectorizer-cpp">SLPVectorizer.cpp</a>.</p>

</div>
</div>

### getGatherCost() {#acadcc40e851da294bfda85d1ea8e351c}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">InstructionCost BoUpSLP::getGatherCost (<a href="/web-llvm/docs/api/classes/llvm/arrayref">ArrayRef</a>&lt; <a href="/web-llvm/docs/api/classes/llvm/value">Value</a> * &gt; VL, bool ForPoisonSrc, <a href="/web-llvm/docs/api/classes/llvm/type">Type</a> * ScalarTy)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">




<dl class="doxySectionUser">
<dt>Returns</dt>
<dd><p>the cost of gathering (inserting) the values in <span class="doxyComputerOutput">VL</span> into a vector.</p></dd>
</dl>


<dl class="doxyParamsList">
<dt class="doxyParamsTableTitle">Parameters</dt>
<dd>
<table class="doxyParamsTable">
<tr class="doxyParamItem">
<td class="doxyParamItemName">ForPoisonSrc</td>
<td class="doxyParamItemDescription"><p>true if initial vector is poison, false otherwise.</p></td>
</tr>
</table>
</dd>
</dl>

<p>Definition at line 3164 of file <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/vectorize/slpvectorizer-cpp">SLPVectorizer.cpp</a>.</p>

</div>
</div>

### getLastInstructionInBundle() {#ab7562b6e17ceb56fa8731af2117bf261}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">Instruction &amp; BoUpSLP::getLastInstructionInBundle (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> TreeEntry * E)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Returns the instruction in the bundle, which can be used as a base point for scheduling.</p>


<p>Usually it is the last instruction in the bundle, except for the case when all operands are external (in this case, it is the first instruction in the list).</p>


<p>Definition at line 3107 of file <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/vectorize/slpvectorizer-cpp">SLPVectorizer.cpp</a>.</p>

</div>
</div>

### getMatchedVectorizedOperand() {#a165c20e5f3127b4b43922eee3282050b}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">BoUpSLP::TreeEntry * BoUpSLP::getMatchedVectorizedOperand (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> TreeEntry * E, unsigned NodeIdx)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Returns vectorized operand node, that matches the order of the scalars operand number <span class="doxyComputerOutput">NodeIdx</span> in entry <span class="doxyComputerOutput">E</span>.</p>

<p>Definition at line 3079 of file <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/vectorize/slpvectorizer-cpp">SLPVectorizer.cpp</a>.</p>

</div>
</div>

### getMatchedVectorizedOperand() {#a493d808fb43d8683f8d9429864f926c6}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">const TreeEntry * llvm::slpvectorizer::BoUpSLP::getMatchedVectorizedOperand (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> TreeEntry * E, unsigned NodeIdx)</td>
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



<p>Definition at line 3080 of file <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/vectorize/slpvectorizer-cpp">SLPVectorizer.cpp</a>.</p>

</div>
</div>

### getOperandEntry() {#aafe54b7b2bb2f0963b1f3fb48b23d075}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">const BoUpSLP::TreeEntry * BoUpSLP::getOperandEntry (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> TreeEntry * E, unsigned Idx)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>\ returns the graph entry for the <span class="doxyComputerOutput">Idx</span> operand of the <span class="doxyComputerOutput">E</span> entry.</p>

<p>Definition at line 3041 of file <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/vectorize/slpvectorizer-cpp">SLPVectorizer.cpp</a>.</p>

</div>
</div>

### getOperandInfo() {#aafe4a9650de05d71c213add93b277db6}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">TTI::OperandValueInfo BoUpSLP::getOperandInfo (<a href="/web-llvm/docs/api/classes/llvm/arrayref">ArrayRef</a>&lt; <a href="/web-llvm/docs/api/classes/llvm/value">Value</a> * &gt; Ops)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Return information about the vector formed for the specified index of a vector of (the same) instruction.</p>

<p>Definition at line 3038 of file <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/vectorize/slpvectorizer-cpp">SLPVectorizer.cpp</a>.</p>

</div>
</div>

### getRootEntryInstruction() {#abc035709a419cdb3f324255cb01543f9}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">Instruction * BoUpSLP::getRootEntryInstruction (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> TreeEntry &amp; Entry)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Gets the root instruction for the given node.</p>


<p>If the node is a strided load/store node with the reverse order, the root instruction is the last one.</p>


<p>Definition at line 3046 of file <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/vectorize/slpvectorizer-cpp">SLPVectorizer.cpp</a>.</p>

</div>
</div>

### getScalarsVectorizationState() {#a43bc83ca6b3d717c12d9d5fcfc301998}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">BoUpSLP::TreeEntry::EntryState BoUpSLP::getScalarsVectorizationState (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> InstructionsState &amp; S, <a href="/web-llvm/docs/api/classes/llvm/arrayref">ArrayRef</a>&lt; <a href="/web-llvm/docs/api/classes/llvm/value">Value</a> * &gt; VL, bool IsScatterVectorizeUserTE, <a href="#a056d3cd46ef12f648e431fe9776451a1">OrdersType</a> &amp; CurrentOrder, <a href="/web-llvm/docs/api/classes/llvm/smallvectorimpl">SmallVectorImpl</a>&lt; <a href="/web-llvm/docs/api/classes/llvm/value">Value</a> * &gt; &amp; PointerOps)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Checks if the specified list of the instructions/values can be vectorized and fills required data before actual scheduling of the instructions.</p>

<p>Definition at line 3750 of file <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/vectorize/slpvectorizer-cpp">SLPVectorizer.cpp</a>.</p>

</div>
</div>

### getTreeEntry() {#abe7ba4656a84c9e5fb10267137ad335d}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">TreeEntry * llvm::slpvectorizer::BoUpSLP::getTreeEntry (<a href="/web-llvm/docs/api/classes/llvm/value">Value</a> * V)</td>
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



<p>Definition at line 3728 of file <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/vectorize/slpvectorizer-cpp">SLPVectorizer.cpp</a>.</p>

</div>
</div>

### getTreeEntry() {#a45bc71b7cb7fdca2c0f70dff121664d3}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">const TreeEntry * llvm::slpvectorizer::BoUpSLP::getTreeEntry (<a href="/web-llvm/docs/api/classes/llvm/value">Value</a> * V)</td>
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



<p>Definition at line 3733 of file <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/vectorize/slpvectorizer-cpp">SLPVectorizer.cpp</a>.</p>

</div>
</div>

### getVectorizedOperand() {#a082e45a1867ab3ea33d888c84ba6169c}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">TreeEntry * llvm::slpvectorizer::BoUpSLP::getVectorizedOperand (TreeEntry * UserTE, unsigned OpIdx)</td>
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

<p>Returns vectorized operand <span class="doxyComputerOutput">OpIdx</span> of the node <span class="doxyComputerOutput">UserTE</span> from the graph, if any.</p>


<p>If it is not vectorized (gather node), returns nullptr.</p>


<p>Definition at line 2998 of file <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/vectorize/slpvectorizer-cpp">SLPVectorizer.cpp</a>.</p>

</div>
</div>

### getVectorizedOperand() {#acf574bc8610c80c9059b61c1bd3b2b3d}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">const TreeEntry * llvm::slpvectorizer::BoUpSLP::getVectorizedOperand (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> TreeEntry * UserTE, unsigned OpIdx)</td>
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

<p>Returns vectorized operand <span class="doxyComputerOutput">OpIdx</span> of the node <span class="doxyComputerOutput">UserTE</span> from the graph, if any.</p>


<p>If it is not vectorized (gather node), returns nullptr.</p>


<p>Definition at line 3025 of file <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/vectorize/slpvectorizer-cpp">SLPVectorizer.cpp</a>.</p>

</div>
</div>

### isAliased() {#a948082ce2f3a54a7f5c2f9c3336fccab}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool llvm::slpvectorizer::BoUpSLP::isAliased (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/memorylocation">MemoryLocation</a> &amp; Loc1, <a href="/web-llvm/docs/api/classes/llvm/instruction">Instruction</a> * Inst1, <a href="/web-llvm/docs/api/classes/llvm/instruction">Instruction</a> * Inst2)</td>
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

<p>Checks if two instructions may access the same memory.</p>


<p><span class="doxyComputerOutput">Loc1</span> is the location of <span class="doxyComputerOutput">Inst1</span>. It is passed explicitly because it is invariant in the calling loop.</p>


<p>Definition at line 3819 of file <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/vectorize/slpvectorizer-cpp">SLPVectorizer.cpp</a>.</p>

</div>
</div>

### isFullyVectorizableTinyTree() {#aa82698e1e0686f629237d59e8ed8f944}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool BoUpSLP::isFullyVectorizableTinyTree (bool ForReduction)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">




<dl class="doxySectionUser">
<dt>Returns</dt>
<dd><p>whether the VectorizableTree is fully vectorizable and will be beneficial even the tree height is tiny.</p></dd>
</dl>


<p>Definition at line 3179 of file <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/vectorize/slpvectorizer-cpp">SLPVectorizer.cpp</a>.</p>

</div>
</div>

### isGatherShuffledEntry() {#ab9bad2e690f2b2621c7632ff50a6852c}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">SmallVector&lt; std::optional&lt; TargetTransformInfo::ShuffleKind &gt; &gt; BoUpSLP::isGatherShuffledEntry (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> TreeEntry * TE, <a href="/web-llvm/docs/api/classes/llvm/arrayref">ArrayRef</a>&lt; <a href="/web-llvm/docs/api/classes/llvm/value">Value</a> * &gt; VL, <a href="/web-llvm/docs/api/classes/llvm/smallvectorimpl">SmallVectorImpl</a>&lt; int &gt; &amp; Mask, <a href="/web-llvm/docs/api/classes/llvm/smallvectorimpl">SmallVectorImpl</a>&lt; <a href="/web-llvm/docs/api/classes/llvm/smallvector">SmallVector</a>&lt; <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> TreeEntry * &gt; &gt; &amp; Entries, unsigned NumParts, bool ForOrder=false)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Checks if the gathered <span class="doxyComputerOutput">VL</span> can be represented as multi-register shuffle(s) of previous tree entries.</p>


<dl class="doxyParamsList">
<dt class="doxyParamsTableTitle">Parameters</dt>
<dd>
<table class="doxyParamsTable">
<tr class="doxyParamItem">
<td class="doxyParamItemName">TE</td>
<td class="doxyParamItemDescription"><p>Tree entry checked for permutation.</p></td>
</tr>
<tr class="doxyParamItem">
<td class="doxyParamItemName">VL</td>
<td class="doxyParamItemDescription"><p>List of scalars (a subset of the TE scalar), checked for permutations.</p></td>
</tr>
<tr class="doxyParamItem">
<td class="doxyParamItemName">ForOrder</td>
<td class="doxyParamItemDescription"><p>Tries to fetch the best candidates for ordering info. Also commands to build the mask using the original vector value, without relying on the potential reordering.</p></td>
</tr>
</table>
</dd>
</dl>

<dl class="doxySectionUser">
<dt>Returns</dt>
<dd><p>per-register series of ShuffleKind, if gathered values can be represented as shuffles of previous tree entries. <span class="doxyComputerOutput">Mask</span> is filled with the shuffle mask (also on per-register base).</p></dd>
</dl>


<p>Definition at line 3156 of file <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/vectorize/slpvectorizer-cpp">SLPVectorizer.cpp</a>.</p>

</div>
</div>

### isGatherShuffledSingleRegisterEntry() {#a6469daa232d7c7587d1256860e4a85cf}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">std::optional&lt; TargetTransformInfo::ShuffleKind &gt; BoUpSLP::isGatherShuffledSingleRegisterEntry (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> TreeEntry * TE, <a href="/web-llvm/docs/api/classes/llvm/arrayref">ArrayRef</a>&lt; <a href="/web-llvm/docs/api/classes/llvm/value">Value</a> * &gt; VL, <a href="/web-llvm/docs/api/classes/llvm/mutablearrayref">MutableArrayRef</a>&lt; int &gt; Mask, <a href="/web-llvm/docs/api/classes/llvm/smallvectorimpl">SmallVectorImpl</a>&lt; <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> TreeEntry * &gt; &amp; Entries, unsigned Part, bool ForOrder)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Checks if the gathered <span class="doxyComputerOutput">VL</span> can be represented as a single register shuffle(s) of previous tree entries.</p>


<dl class="doxyParamsList">
<dt class="doxyParamsTableTitle">Parameters</dt>
<dd>
<table class="doxyParamsTable">
<tr class="doxyParamItem">
<td class="doxyParamItemName">TE</td>
<td class="doxyParamItemDescription"><p>Tree entry checked for permutation.</p></td>
</tr>
<tr class="doxyParamItem">
<td class="doxyParamItemName">VL</td>
<td class="doxyParamItemDescription"><p>List of scalars (a subset of the TE scalar), checked for permutations. Must form single-register vector.</p></td>
</tr>
<tr class="doxyParamItem">
<td class="doxyParamItemName">ForOrder</td>
<td class="doxyParamItemDescription"><p>Tries to fetch the best candidates for ordering info. Also commands to build the mask using the original vector value, without relying on the potential reordering.</p></td>
</tr>
</table>
</dd>
</dl>

<dl class="doxySectionUser">
<dt>Returns</dt>
<dd><p>ShuffleKind, if gathered values can be represented as shuffles of previous tree entries. <span class="doxyComputerOutput">Part</span> of <span class="doxyComputerOutput">Mask</span> is filled with the shuffle mask.</p></dd>
</dl>


<p>Definition at line 3139 of file <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/vectorize/slpvectorizer-cpp">SLPVectorizer.cpp</a>.</p>

</div>
</div>

### newTreeEntry() {#a8be06c3d1de5aefe60a9a8ec98bb216b}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">TreeEntry * llvm::slpvectorizer::BoUpSLP::newTreeEntry (<a href="/web-llvm/docs/api/classes/llvm/arrayref">ArrayRef</a>&lt; <a href="/web-llvm/docs/api/classes/llvm/value">Value</a> * &gt; VL, std::optional&lt; ScheduleData * &gt; Bundle, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> InstructionsState &amp; S, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/structs/llvm/slpvectorizer/boupslp/edgeinfo">EdgeInfo</a> &amp; UserTreeIdx, <a href="/web-llvm/docs/api/classes/llvm/arrayref">ArrayRef</a>&lt; int &gt; ReuseShuffleIndices={}, <a href="/web-llvm/docs/api/classes/llvm/arrayref">ArrayRef</a>&lt; unsigned &gt; ReorderIndices={}, unsigned InterleaveFactor=0)</td>
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

<p>Create a new VectorizableTree entry.</p>

<p>Definition at line 3599 of file <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/vectorize/slpvectorizer-cpp">SLPVectorizer.cpp</a>.</p>

</div>
</div>

### newTreeEntry() {#aa028f2760a292569ae42e9219ed5af68}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">TreeEntry * llvm::slpvectorizer::BoUpSLP::newTreeEntry (<a href="/web-llvm/docs/api/classes/llvm/arrayref">ArrayRef</a>&lt; <a href="/web-llvm/docs/api/classes/llvm/value">Value</a> * &gt; VL, TreeEntry::EntryState EntryState, std::optional&lt; ScheduleData * &gt; Bundle, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> InstructionsState &amp; S, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/structs/llvm/slpvectorizer/boupslp/edgeinfo">EdgeInfo</a> &amp; UserTreeIdx, <a href="/web-llvm/docs/api/classes/llvm/arrayref">ArrayRef</a>&lt; int &gt; ReuseShuffleIndices={}, <a href="/web-llvm/docs/api/classes/llvm/arrayref">ArrayRef</a>&lt; unsigned &gt; ReorderIndices={})</td>
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



<p>Definition at line 3615 of file <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/vectorize/slpvectorizer-cpp">SLPVectorizer.cpp</a>.</p>

</div>
</div>

### processBuildVector() {#acfe91867a2060578464be38b6977deaf}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<div class="doxyMemberTemplate">template &lt;typename BVTy, typename ResTy, typename... Args&gt;</div>
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">ResTy BoUpSLP::processBuildVector (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> TreeEntry * E, <a href="/web-llvm/docs/api/classes/llvm/type">Type</a> * ScalarTy, Args &amp;... Params)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Create a new vector from a list of scalar values.</p>


<p>Produces a sequence which exploits values reused across lanes, and arranges the inserts for ease of later optimization.</p>


<p>Definition at line 3095 of file <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/vectorize/slpvectorizer-cpp">SLPVectorizer.cpp</a>.</p>

</div>
</div>

### reorderGatherNode() {#a75dec9db92f17ee8d74a398331c9bd5c}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void BoUpSLP::reorderGatherNode (TreeEntry &amp; TE)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Tries to reorder the gathering node for better vectorization opportunities.</p>

<p>Definition at line 3213 of file <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/vectorize/slpvectorizer-cpp">SLPVectorizer.cpp</a>.</p>

</div>
</div>

### reorderNodeWithReuses() {#a73a31d5bb7dcd22d8c81ee4a0169b142}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void BoUpSLP::reorderNodeWithReuses (TreeEntry &amp; TE, <a href="/web-llvm/docs/api/classes/llvm/arrayref">ArrayRef</a>&lt; int &gt; Mask)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Checks if the given <span class="doxyComputerOutput">TE</span> is a gather node with clustered reused scalars and reorders it per given <span class="doxyComputerOutput">Mask</span>.</p>

<p>Definition at line 2994 of file <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/vectorize/slpvectorizer-cpp">SLPVectorizer.cpp</a>.</p>

</div>
</div>

### scheduleBlock() {#ac844a9ffc7b47fb80f3411c7ca6d9957}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void BoUpSLP::scheduleBlock (BlockScheduling * BS)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Performs the "real" scheduling.</p>


<p>Done before vectorization is actually performed in a basic block.</p>


<p>Definition at line 4358 of file <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/vectorize/slpvectorizer-cpp">SLPVectorizer.cpp</a>.</p>

</div>
</div>

### setInsertPointAfterBundle() {#a61c5bdc9bb16637acfd0771792633153}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void BoUpSLP::setInsertPointAfterBundle (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> TreeEntry * E)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Set the Builder insert point to one after the last instruction in the bundle.</p>

<p>Definition at line 3169 of file <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/vectorize/slpvectorizer-cpp">SLPVectorizer.cpp</a>.</p>

</div>
</div>

### tryToGatherExtractElements() {#a43820a91e3d701ddc34b2d72e0a65269}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">SmallVector&lt; std::optional&lt; TTI::ShuffleKind &gt; &gt; BoUpSLP::tryToGatherExtractElements (<a href="/web-llvm/docs/api/classes/llvm/smallvectorimpl">SmallVectorImpl</a>&lt; <a href="/web-llvm/docs/api/classes/llvm/value">Value</a> * &gt; &amp; VL, <a href="/web-llvm/docs/api/classes/llvm/smallvectorimpl">SmallVectorImpl</a>&lt; int &gt; &amp; Mask, unsigned NumParts)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Tries to find extractelement instructions with constant indices from fixed vector type and gather such instructions into a bunch, which highly likely might be detected as a shuffle of 1 or 2 input vectors.</p>


<p>If this attempt was successful, the matched scalars are replaced by poison values in <span class="doxyComputerOutput">VL</span> for future analysis.</p>


<p>Definition at line 3124 of file <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/vectorize/slpvectorizer-cpp">SLPVectorizer.cpp</a>.</p>

</div>
</div>

### tryToGatherSingleRegisterExtractElements() {#a19ef6f06ba0112253a3a767a28504aed}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">std::optional&lt; TTI::ShuffleKind &gt; BoUpSLP::tryToGatherSingleRegisterExtractElements (<a href="/web-llvm/docs/api/classes/llvm/mutablearrayref">MutableArrayRef</a>&lt; <a href="/web-llvm/docs/api/classes/llvm/value">Value</a> * &gt; VL, <a href="/web-llvm/docs/api/classes/llvm/smallvectorimpl">SmallVectorImpl</a>&lt; int &gt; &amp; Mask)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Tries to find extractelement instructions with constant indices from fixed vector type and gather such instructions into a bunch, which highly likely might be detected as a shuffle of 1 or 2 input vectors.</p>


<p>If this attempt was successful, the matched scalars are replaced by poison values in <span class="doxyComputerOutput">VL</span> for future analysis.</p>


<p>Definition at line 3115 of file <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/vectorize/slpvectorizer-cpp">SLPVectorizer.cpp</a>.</p>

</div>
</div>

### tryToVectorizeGatheredLoads() {#ace69c2cae8c7e231ac95bb7fc6816f1b}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void BoUpSLP::tryToVectorizeGatheredLoads (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/structs/llvm/smallmapvector">SmallMapVector</a>&lt; std::tuple&lt; <a href="/web-llvm/docs/api/classes/llvm/basicblock">BasicBlock</a> *, <a href="/web-llvm/docs/api/classes/llvm/value">Value</a> *, <a href="/web-llvm/docs/api/classes/llvm/type">Type</a> * &gt;, <a href="/web-llvm/docs/api/classes/llvm/smallvector">SmallVector</a>&lt; <a href="/web-llvm/docs/api/classes/llvm/smallvector">SmallVector</a>&lt; std::pair&lt; <a href="/web-llvm/docs/api/classes/llvm/loadinst">LoadInst</a> *, int &gt; &gt; &gt;, 8 &gt; &amp; GatheredLoads)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Run through the list of all gathered loads in the graph and try to find vector loads/masked gathers instead of regular gathers.</p>


<p>Later these loads are reshufled to build final gathered nodes.</p>


<p>Definition at line 3184 of file <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/vectorize/slpvectorizer-cpp">SLPVectorizer.cpp</a>.</p>

</div>
</div>

### vectorizeOperand() {#afab0ce28b491c2faba682ac8ae5396f5}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">Value * BoUpSLP::vectorizeOperand (TreeEntry * E, unsigned NodeIdx, bool PostponedPHIs)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Vectorize a single entry in the tree, the <span class="doxyComputerOutput">Idx-th</span> operand of the entry <span class="doxyComputerOutput">E</span>.</p>


<dl class="doxyParamsList">
<dt class="doxyParamsTableTitle">Parameters</dt>
<dd>
<table class="doxyParamsTable">
<tr class="doxyParamItem">
<td class="doxyParamItemName">PostponedPHIs</td>
<td class="doxyParamItemDescription"><p>true, if need to postpone emission of phi nodes to avoid issues with def-use order.</p></td>
</tr>
</table>
</dd>
</dl>

<p>Definition at line 3089 of file <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/vectorize/slpvectorizer-cpp">SLPVectorizer.cpp</a>.</p>

</div>
</div>

### vectorizeTree() {#adfafa535e8cc90f46f85c3b1423d6d67}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">Value * BoUpSLP::vectorizeTree (TreeEntry * E, bool PostponedPHIs)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Vectorize a single entry in the tree.</p>


<dl class="doxyParamsList">
<dt class="doxyParamsTableTitle">Parameters</dt>
<dd>
<table class="doxyParamsTable">
<tr class="doxyParamItem">
<td class="doxyParamItemName">PostponedPHIs</td>
<td class="doxyParamItemDescription"><p>true, if need to postpone emission of phi nodes to avoid issues with def-use order.</p></td>
</tr>
</table>
</dd>
</dl>

<p>Definition at line 3075 of file <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/vectorize/slpvectorizer-cpp">SLPVectorizer.cpp</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Private Member Attributes

### AC {#a5f8905cef85ca000a578442fd6965b4a}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">AssumptionCache* llvm::slpvectorizer::BoUpSLP::AC</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 4394 of file <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/vectorize/slpvectorizer-cpp">SLPVectorizer.cpp</a>.</p>

</div>
</div>

### AliasCache {#a772e8ab1fc9c813525acf20b463c2044}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">DenseMap&lt;AliasCacheKey, bool&gt; llvm::slpvectorizer::BoUpSLP::AliasCache</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Cache for alias results.</p>


<p>TODO: consider moving this to the <a href="/web-llvm/docs/api/namespaces/llvm/#ae457f1cf451ed893666c4a384e58f8e5">AliasAnalysis</a> itself.</p>


<p>Definition at line 3839 of file <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/vectorize/slpvectorizer-cpp">SLPVectorizer.cpp</a>.</p>

</div>
</div>

### AnalyzedMinBWVals {#ad24c04ce97610b8eb2f2a5d94e270c35}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">DenseSet&lt;Value *&gt; llvm::slpvectorizer::BoUpSLP::AnalyzedMinBWVals</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Values, already been analyzed for mininmal bitwidth and found to be non-profitable.</p>

<p>Definition at line 3861 of file <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/vectorize/slpvectorizer-cpp">SLPVectorizer.cpp</a>.</p>

</div>
</div>

### AnalyzedReductionsRoots {#ab8cb7770321ee9ce399b8c21ddae0b13}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">SmallPtrSet&lt;Instruction *, 16&gt; llvm::slpvectorizer::BoUpSLP::AnalyzedReductionsRoots</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Set of the instruction, being analyzed already for reductions.</p>

<p>Definition at line 3854 of file <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/vectorize/slpvectorizer-cpp">SLPVectorizer.cpp</a>.</p>

</div>
</div>

### AnalyzedReductionVals {#a65cc1a338cc136eb98e1287053986ef6}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">DenseSet&lt;size_t&gt; llvm::slpvectorizer::BoUpSLP::AnalyzedReductionVals</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Set of hashes for the list of reduction values already being analyzed.</p>

<p>Definition at line 3857 of file <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/vectorize/slpvectorizer-cpp">SLPVectorizer.cpp</a>.</p>

</div>
</div>

### BaseGraphSize {#a2e1826a912fcf88df608a66edfcd148a}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">unsigned llvm::slpvectorizer::BoUpSLP::BaseGraphSize = 1</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Canonical graph size before the transformations.</p>

<p>Definition at line 4418 of file <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/vectorize/slpvectorizer-cpp">SLPVectorizer.cpp</a>.</p>

</div>
</div>

### BatchAA {#a277f844b254e2586007a5e8d8e379152}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">BatchAAResults llvm::slpvectorizer::BoUpSLP::BatchAA</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 3844 of file <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/vectorize/slpvectorizer-cpp">SLPVectorizer.cpp</a>.</p>

</div>
</div>

### BlocksSchedules {#a3f26a32453e8c86c84e186f2b27ac6eb}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">MapVector&lt;BasicBlock *, std::unique_ptr&lt;BlockScheduling&gt; &gt; llvm::slpvectorizer::BoUpSLP::BlocksSchedules</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Attaches the BlockScheduling structures to basic blocks.</p>

<p>Definition at line 4354 of file <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/vectorize/slpvectorizer-cpp">SLPVectorizer.cpp</a>.</p>

</div>
</div>

### Builder {#ab33f29aab2441e8e1cfcb837a856bafd}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">IRBuilder&lt;TargetFolder&gt; llvm::slpvectorizer::BoUpSLP::Builder</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p><a href="/web-llvm/docs/api/classes/llvm/instruction">Instruction</a> builder to construct the vectorized tree.</p>

<p>Definition at line 4403 of file <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/vectorize/slpvectorizer-cpp">SLPVectorizer.cpp</a>.</p>

</div>
</div>

### CastMaxMinBWSizes {#aaf3c6ddeb70c587a6c6306c1edd7bafd}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">std::optional&lt;std::pair&lt;unsigned, unsigned&gt; &gt; llvm::slpvectorizer::BoUpSLP::CastMaxMinBWSizes</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>If the tree contains any zext/sext/trunc nodes, contains max-min pair of type sizes, used in the tree.</p>

<p>Definition at line 4422 of file <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/vectorize/slpvectorizer-cpp">SLPVectorizer.cpp</a>.</p>

</div>
</div>

### CSEBlocks {#ab57fdc3e32cc0ae8d6eb1fbaed3c77d0}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">DenseSet&lt;BasicBlock *&gt; llvm::slpvectorizer::BoUpSLP::CSEBlocks</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>A list of blocks that we are going to CSE.</p>

<p>Definition at line 3881 of file <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/vectorize/slpvectorizer-cpp">SLPVectorizer.cpp</a>.</p>

</div>
</div>

### DB {#ae42fdd4f837a80b393a3b65d6e779226}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">DemandedBits* llvm::slpvectorizer::BoUpSLP::DB</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 4395 of file <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/vectorize/slpvectorizer-cpp">SLPVectorizer.cpp</a>.</p>

</div>
</div>

### DeletedInstructions {#ac45648ffb65206927ce3f2074c3648b1}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">DenseSet&lt;Instruction *&gt; llvm::slpvectorizer::BoUpSLP::DeletedInstructions</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Temporary store for deleted instructions.</p>


<p>Instructions will be deleted eventually when the <a href="/web-llvm/docs/api/classes/llvm/slpvectorizer/boupslp">BoUpSLP</a> is destructed. The deferral is required to ensure that there are no incorrect collisions in the AliasCache, which can happen if a new instruction is allocated at the same address as a previously deleted instruction.</p>


<p>Definition at line 3851 of file <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/vectorize/slpvectorizer-cpp">SLPVectorizer.cpp</a>.</p>

</div>
</div>

### DL {#a2ab2dc46997fa0aaa5c501588e35b095}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">const DataLayout* llvm::slpvectorizer::BoUpSLP::DL</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 4396 of file <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/vectorize/slpvectorizer-cpp">SLPVectorizer.cpp</a>.</p>

</div>
</div>

### DT {#a94eb5749199afa148e48ecffe2f0b606}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">DominatorTree* llvm::slpvectorizer::BoUpSLP::DT</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 4393 of file <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/vectorize/slpvectorizer-cpp">SLPVectorizer.cpp</a>.</p>

</div>
</div>

### EntryToLastInstruction {#ac2ec502416f5f101b36b509650ffb823}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">DenseMap&lt;const TreeEntry *, Instruction *&gt; llvm::slpvectorizer::BoUpSLP::EntryToLastInstruction</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>A map between the vectorized entries and the last instructions in the bundles.</p>


<p>The bundles are built in use order, not in the def order of the instructions. So, we cannot rely directly on the last instruction in the bundle being the last instruction in the program order during vectorization process since the basic blocks are affected, need to pre-gather them before.</p>


<p>Definition at line 3777 of file <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/vectorize/slpvectorizer-cpp">SLPVectorizer.cpp</a>.</p>

</div>
</div>

### EphValues {#a504a10433dad784129b4adf2fd3cb5d1}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">SmallPtrSet&lt;const Value *, 32&gt; llvm::slpvectorizer::BoUpSLP::EphValues</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Values used only by @llvm.assume calls.</p>

<p>Definition at line 3874 of file <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/vectorize/slpvectorizer-cpp">SLPVectorizer.cpp</a>.</p>

</div>
</div>

### ExternalUses {#ac3e8695ea354c51527226b28948e055d}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">UserList llvm::slpvectorizer::BoUpSLP::ExternalUses</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>A list of values that need to extracted out of the tree.</p>


<p>This list holds pairs of (Internal Scalar : External <a href="/web-llvm/docs/api/classes/llvm/user">User</a>). External <a href="/web-llvm/docs/api/classes/llvm/user">User</a> can be nullptr, it means that this Internal Scalar will be used later, after vectorization.</p>


<p>Definition at line 3867 of file <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/vectorize/slpvectorizer-cpp">SLPVectorizer.cpp</a>.</p>

</div>
</div>

### ExternalUsesAsOriginalScalar {#a4c5eb71c0ee34534905b0ab6951d8dc4}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">SmallPtrSet&lt;Value *, 4&gt; llvm::slpvectorizer::BoUpSLP::ExternalUsesAsOriginalScalar</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>A list of GEPs which can be reaplced by scalar GEPs instead of extractelement instructions.</p>

<p>Definition at line 3871 of file <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/vectorize/slpvectorizer-cpp">SLPVectorizer.cpp</a>.</p>

</div>
</div>

### ExtraBitWidthNodes {#a48fbdd3082f1a4ac3926ea985676fe9a}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">DenseSet&lt;unsigned&gt; llvm::slpvectorizer::BoUpSLP::ExtraBitWidthNodes</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Indices of the vectorized nodes, which supposed to be the roots of the new bitwidth analysis attempt, like trunc, IToFP or ICmp.</p>

<p>Definition at line 4426 of file <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/vectorize/slpvectorizer-cpp">SLPVectorizer.cpp</a>.</p>

</div>
</div>

### F {#a96a28a1ec7e0f3568694ec52481add5b}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">Function* llvm::slpvectorizer::BoUpSLP::F</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 4388 of file <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/vectorize/slpvectorizer-cpp">SLPVectorizer.cpp</a>.</p>

</div>
</div>

### GatheredLoadsEntriesFirst {#a17c313765367cc79f5a76a3488cbd347}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">std::optional&lt;unsigned&gt; llvm::slpvectorizer::BoUpSLP::GatheredLoadsEntriesFirst</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>The index of the first gathered load entry in the VectorizeTree.</p>

<p>Definition at line 3797 of file <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/vectorize/slpvectorizer-cpp">SLPVectorizer.cpp</a>.</p>

</div>
</div>

### GatherShuffleExtractSeq {#ae5b0c4e328eddea9cb8ddf84745ab391}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">SetVector&lt;Instruction *&gt; llvm::slpvectorizer::BoUpSLP::GatherShuffleExtractSeq</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Holds all of the instructions that we gathered, shuffle instructions and extractelements.</p>

<p>Definition at line 3878 of file <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/vectorize/slpvectorizer-cpp">SLPVectorizer.cpp</a>.</p>

</div>
</div>

### InstrElementSize {#aac428d1f1b708780715566924bb373c4}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">SmallDenseMap&lt;Value *, unsigned&gt; llvm::slpvectorizer::BoUpSLP::InstrElementSize</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Maps a value to the proposed vectorizable size.</p>

<p>Definition at line 3763 of file <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/vectorize/slpvectorizer-cpp">SLPVectorizer.cpp</a>.</p>

</div>
</div>

### IsGraphTransformMode {#afd3f8ca47800c55be221192689c8f7f4}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool llvm::slpvectorizer::BoUpSLP::IsGraphTransformMode = false</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>true if graph nodes transforming mode is on.</p>

<p>Definition at line 3794 of file <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/vectorize/slpvectorizer-cpp">SLPVectorizer.cpp</a>.</p>

</div>
</div>

### LI {#a25696ba9845aa178a6b3cdd70e86df35}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">LoopInfo* llvm::slpvectorizer::BoUpSLP::LI</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 4392 of file <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/vectorize/slpvectorizer-cpp">SLPVectorizer.cpp</a>.</p>

</div>
</div>

### ListOfKnonwnNonVectorizableLoads {#ab93d7484ebdc203459a0bab5096a6e4e}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">DenseSet&lt;size_t&gt; llvm::slpvectorizer::BoUpSLP::ListOfKnonwnNonVectorizableLoads</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>List of hashes of vector of loads, which are known to be non vectorizable.</p>

<p>Definition at line 3884 of file <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/vectorize/slpvectorizer-cpp">SLPVectorizer.cpp</a>.</p>

</div>
</div>

### LoadEntriesToVectorize {#a5b0954b60b8951313eefe78a2b147111}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">SetVector&lt;unsigned&gt; llvm::slpvectorizer::BoUpSLP::LoadEntriesToVectorize</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>A list of the load entries (node indices), which can be vectorized using strided or masked gather approach, but attempted to be represented as contiguous loads.</p>

<p>Definition at line 3791 of file <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/vectorize/slpvectorizer-cpp">SLPVectorizer.cpp</a>.</p>

</div>
</div>

### MaxVecRegSize {#aa1a6e405b6b9407ae9ab78f1519b5617}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">unsigned llvm::slpvectorizer::BoUpSLP::MaxVecRegSize</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 4399 of file <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/vectorize/slpvectorizer-cpp">SLPVectorizer.cpp</a>.</p>

</div>
</div>

### MinBWs {#a7ace999cc9764c8972092693622137ed}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">DenseMap&lt;const TreeEntry *, std::pair&lt;uint64_t, bool&gt; &gt; llvm::slpvectorizer::BoUpSLP::MinBWs</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>A map of scalar integer values to the smallest bit width with which they can legally be represented.</p>


<p>The values map to (width, signed) pairs, where "width" indicates the minimum bit width and "signed" is True if the value must be signed-extended, rather than zero-extended, back to its original width.</p>


<p>Definition at line 4410 of file <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/vectorize/slpvectorizer-cpp">SLPVectorizer.cpp</a>.</p>

</div>
</div>

### MinVecRegSize {#a9cb0c966edf73d76b32a5ec0fc9d33eb}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">unsigned llvm::slpvectorizer::BoUpSLP::MinVecRegSize</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 4400 of file <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/vectorize/slpvectorizer-cpp">SLPVectorizer.cpp</a>.</p>

</div>
</div>

### MultiNodeScalars {#a0426828efa639b0c95cee44ecccc3398}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">SmallDenseMap&lt;Value *, SmallVector&lt;TreeEntry *&gt; &gt; llvm::slpvectorizer::BoUpSLP::MultiNodeScalars</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>List of scalars, used in several vectorize nodes, and the list of the nodes.</p>

<p>Definition at line 3760 of file <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/vectorize/slpvectorizer-cpp">SLPVectorizer.cpp</a>.</p>

</div>
</div>

### MustGather {#a880b231f9052bd991c88bd1805d9ab62}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">ValueSet llvm::slpvectorizer::BoUpSLP::MustGather</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>A list of scalars that we found that we need to keep as scalars.</p>

<p>Definition at line 3766 of file <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/vectorize/slpvectorizer-cpp">SLPVectorizer.cpp</a>.</p>

</div>
</div>

### NonScheduledFirst {#aa48f882b8196ab0a8c5dec13ef77323d}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">ValueSet llvm::slpvectorizer::BoUpSLP::NonScheduledFirst</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>A set of first non-schedulable values.</p>

<p>Definition at line 3769 of file <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/vectorize/slpvectorizer-cpp">SLPVectorizer.cpp</a>.</p>

</div>
</div>

### ORE {#a4900c0a59fd5c667796582d309fb5fc4}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">OptimizationRemarkEmitter* llvm::slpvectorizer::BoUpSLP::ORE</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 4397 of file <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/vectorize/slpvectorizer-cpp">SLPVectorizer.cpp</a>.</p>

</div>
</div>

### PostponedGathers {#a7a9dcf5bc2ba583e66567329dbfd1396}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">SetVector&lt;const TreeEntry *&gt; llvm::slpvectorizer::BoUpSLP::PostponedGathers</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>List of gather nodes, depending on other gather/vector nodes, which should be emitted after the vector instruction emission process to correctly handle order of the vector instructions and shuffles.</p>

<p>Definition at line 3782 of file <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/vectorize/slpvectorizer-cpp">SLPVectorizer.cpp</a>.</p>

</div>
</div>

### ReductionBitWidth {#ac8c4611dde12401c1a83394bc6e0f0d0}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">unsigned llvm::slpvectorizer::BoUpSLP::ReductionBitWidth = 0</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Final size of the reduced vector, if the current graph represents the input for the reduction and it was possible to narrow the size of the reduction.</p>

<p>Definition at line 4415 of file <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/vectorize/slpvectorizer-cpp">SLPVectorizer.cpp</a>.</p>

</div>
</div>

### ScalarToTreeEntry {#a0d459fe5dd29a392f49dd710d2f2c71b}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">SmallDenseMap&lt;Value *, TreeEntry *&gt; llvm::slpvectorizer::BoUpSLP::ScalarToTreeEntry</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Maps a specific scalar to its tree entry.</p>

<p>Definition at line 3756 of file <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/vectorize/slpvectorizer-cpp">SLPVectorizer.cpp</a>.</p>

</div>
</div>

### SE {#a9f477ff68bc3e29ed2b26a8b9d072634}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">ScalarEvolution* llvm::slpvectorizer::BoUpSLP::SE</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 4389 of file <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/vectorize/slpvectorizer-cpp">SLPVectorizer.cpp</a>.</p>

</div>
</div>

### TLI {#af6ffb2e92d674db7068b73c46d532c5b}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">TargetLibraryInfo* llvm::slpvectorizer::BoUpSLP::TLI</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 4391 of file <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/vectorize/slpvectorizer-cpp">SLPVectorizer.cpp</a>.</p>

</div>
</div>

### TTI {#ae5d74b8a6753eb90229afe818e3807aa}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">TargetTransformInfo* llvm::slpvectorizer::BoUpSLP::TTI</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 4390 of file <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/vectorize/slpvectorizer-cpp">SLPVectorizer.cpp</a>.</p>

</div>
</div>

### UserIgnoreList {#abc56ef7b38f2fd4baed872ee29265ec8}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">const SmallDenseSet&lt;Value *&gt;* llvm::slpvectorizer::BoUpSLP::UserIgnoreList = nullptr</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>List of users to ignore during scheduling and that don't need extracting.</p>

<p>Definition at line 4361 of file <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/vectorize/slpvectorizer-cpp">SLPVectorizer.cpp</a>.</p>

</div>
</div>

### ValueToGatherNodes {#a6a07db700982ba8691a9c0439cd99b37}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">ValueToGatherNodesMap llvm::slpvectorizer::BoUpSLP::ValueToGatherNodes</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 3786 of file <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/vectorize/slpvectorizer-cpp">SLPVectorizer.cpp</a>.</p>

</div>
</div>

### VectorizableTree {#a7795c2fb3606392450da583eccfe2455}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">TreeEntry::VecTreeTy llvm::slpvectorizer::BoUpSLP::VectorizableTree</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>– Vectorization State – Holds all of the tree entries.</p>

<p>Definition at line 3716 of file <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/vectorize/slpvectorizer-cpp">SLPVectorizer.cpp</a>.</p>

</div>
</div>

</div>

<hr/>

The documentation for this class was generated from the following file:

<ul>
<li><a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/vectorize/slpvectorizer-cpp">SLPVectorizer.cpp</a></li>
</ul>

<hr/>

<p class="doxyGeneratedBy">Generated via <a href="https://github.com/xpack/doxygen2docusaurus">doxygen2docusaurus</a> by <a href="https://www.doxygen.nl">Doxygen</a> 1.15.0.</p>

</div>
