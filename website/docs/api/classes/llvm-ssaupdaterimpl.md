---

# DO NOT EDIT!
# Automatically generated via doxygen2docusaurus by Doxygen.

slug: /api/classes/llvm/ssaupdaterimpl
custom_edit_url: null
toc_max_heading_level: 4
keywords:
  - doxygen
  - reference
  - class

---

<div class="doxyPage">

# The `SSAUpdaterImpl` Class Template Reference



## Declaration

<div class="doxyDeclaration">
template &lt;typename UpdaterT&gt;
class llvm::SSAUpdaterImpl&lt;UpdaterT&gt; { ... }
</div>

## Included Headers

<div class="doxyIncludesList">#include "<a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/transforms/include/llvm/transforms/utils/ssaupdaterimpl-h">llvm/Transforms/Utils/SSAUpdaterImpl.h</a>"
</div>

## Private Member Typedefs Index

<table class="doxyMembersIndex">

<tr class="doxyMemberIndexTemplate">
<td class="doxyMemberIndexTemplate" colspan="2"><div>template &lt;typename UpdaterT&gt;</div></td>
</tr>
<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemTypeTemplate" align="left" valign="top">using</td>
<td class="doxyMemberIndexItemNameTemplate" align="left" valign="top"><a href="#a5c02d9afff1fb1b35cd113bf2a9ba908">Traits</a> = <a href="/web-llvm/docs/api/classes/llvm/ssaupdatertraits">SSAUpdaterTraits</a>&lt; UpdaterT &gt;</td>
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
<td class="doxyMemberIndexTemplate" colspan="2"><div>template &lt;typename UpdaterT&gt;</div></td>
</tr>
<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemTypeTemplate" align="left" valign="top">using</td>
<td class="doxyMemberIndexItemNameTemplate" align="left" valign="top"><a href="#a2ea9f05f9ff6796eb824ece16eb60708">BlkT</a> = typename Traits::BlkT</td>
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
<td class="doxyMemberIndexTemplate" colspan="2"><div>template &lt;typename UpdaterT&gt;</div></td>
</tr>
<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemTypeTemplate" align="left" valign="top">using</td>
<td class="doxyMemberIndexItemNameTemplate" align="left" valign="top"><a href="#a490100ebb370235ce8d04a6b4afa16c5">ValT</a> = typename Traits::ValT</td>
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
<td class="doxyMemberIndexTemplate" colspan="2"><div>template &lt;typename UpdaterT&gt;</div></td>
</tr>
<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemTypeTemplate" align="left" valign="top">using</td>
<td class="doxyMemberIndexItemNameTemplate" align="left" valign="top"><a href="#a20e90f8e9ad4744b4d77b9534a4d9dec">PhiT</a> = typename Traits::PhiT</td>
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
<td class="doxyMemberIndexTemplate" colspan="2"><div>template &lt;typename UpdaterT&gt;</div></td>
</tr>
<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemTypeTemplate" align="left" valign="top">using</td>
<td class="doxyMemberIndexItemNameTemplate" align="left" valign="top"><a href="#aef0766f16cb5480636bbd6a6087a75b4">AvailableValsTy</a> = <a href="/web-llvm/docs/api/classes/llvm/densemap">DenseMap</a>&lt; BlkT *, ValT &gt;</td>
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
<td class="doxyMemberIndexTemplate" colspan="2"><div>template &lt;typename UpdaterT&gt;</div></td>
</tr>
<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemTypeTemplate" align="left" valign="top">using</td>
<td class="doxyMemberIndexItemNameTemplate" align="left" valign="top"><a href="#a8e2fa5790ddd0984480af9f42d00f2d0">BlockListTy</a> = <a href="/web-llvm/docs/api/classes/llvm/smallvectorimpl">SmallVectorImpl</a>&lt; BBInfo * &gt;</td>
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
<td class="doxyMemberIndexTemplate" colspan="2"><div>template &lt;typename UpdaterT&gt;</div></td>
</tr>
<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemTypeTemplate" align="left" valign="top">using</td>
<td class="doxyMemberIndexItemNameTemplate" align="left" valign="top"><a href="#aba873fefc1e81e5db13366acab06fa47">BBMapTy</a> = <a href="/web-llvm/docs/api/classes/llvm/densemap">DenseMap</a>&lt; BlkT *, BBInfo * &gt;</td>
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

<tr class="doxyMemberIndexTemplate">
<td class="doxyMemberIndexTemplate" colspan="2"><div>template &lt;typename UpdaterT&gt;</div></td>
</tr>
<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemNoTypeNameTemplate" colspan="2" align="left" valign="top"><a href="#a5f421457a35ee1520ac43e4f7def256d">SSAUpdaterImpl</a> (UpdaterT *U, AvailableValsTy *A, SmallVectorImpl&lt; PhiT * &gt; *Ins)</td>
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

<tr class="doxyMemberIndexTemplate">
<td class="doxyMemberIndexTemplate" colspan="2"><div>template &lt;typename UpdaterT&gt;</div></td>
</tr>
<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemTypeTemplate" align="left" valign="top">ValT</td>
<td class="doxyMemberIndexItemNameTemplate" align="left" valign="top"><a href="#a4f6c8ac18caa1b4beaf0d4d88b82cef9">GetValue</a> (BlkT *BB)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>GetValue - <a href="/web-llvm/docs/api/namespaces/llvm/check">Check</a> to see if AvailableVals has an entry for the specified BB and if so, return it. <a href="#a4f6c8ac18caa1b4beaf0d4d88b82cef9">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexTemplate">
<td class="doxyMemberIndexTemplate" colspan="2"><div>template &lt;typename UpdaterT&gt;</div></td>
</tr>
<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemTypeTemplate" align="left" valign="top">BBInfo *</td>
<td class="doxyMemberIndexItemNameTemplate" align="left" valign="top"><a href="#a85cbdd891f1cd43d6c79f7d68a2caf46">BuildBlockList</a> (BlkT *BB, BlockListTy *BlockList)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>BuildBlockList - Starting from the specified basic block, traverse back through its predecessors until reaching blocks with known values. <a href="#a85cbdd891f1cd43d6c79f7d68a2caf46">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexTemplate">
<td class="doxyMemberIndexTemplate" colspan="2"><div>template &lt;typename UpdaterT&gt;</div></td>
</tr>
<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemTypeTemplate" align="left" valign="top">BBInfo *</td>
<td class="doxyMemberIndexItemNameTemplate" align="left" valign="top"><a href="#ad25fe079e293e33582cbb5f3bf494bf5">IntersectDominators</a> (BBInfo *Blk1, BBInfo *Blk2)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>IntersectDominators - This is the dataflow lattice "meet" operation for finding dominators. <a href="#ad25fe079e293e33582cbb5f3bf494bf5">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexTemplate">
<td class="doxyMemberIndexTemplate" colspan="2"><div>template &lt;typename UpdaterT&gt;</div></td>
</tr>
<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemTypeTemplate" align="left" valign="top">void</td>
<td class="doxyMemberIndexItemNameTemplate" align="left" valign="top"><a href="#a0ab1c1435c29eea38d7a8dd64f064b84">FindDominators</a> (BlockListTy *BlockList, BBInfo *PseudoEntry)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>FindDominators - Calculate the dominator tree for the subset of the CFG corresponding to the basic blocks on the BlockList. <a href="#a0ab1c1435c29eea38d7a8dd64f064b84">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexTemplate">
<td class="doxyMemberIndexTemplate" colspan="2"><div>template &lt;typename UpdaterT&gt;</div></td>
</tr>
<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemTypeTemplate" align="left" valign="top">bool</td>
<td class="doxyMemberIndexItemNameTemplate" align="left" valign="top"><a href="#a42e6b449c6b8fe1fa8d10f2f300f7e9b">IsDefInDomFrontier</a> (const BBInfo *Pred, const BBInfo *IDom)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>IsDefInDomFrontier - Search up the dominator tree from Pred to IDom for any blocks containing definitions of the value. <a href="#a42e6b449c6b8fe1fa8d10f2f300f7e9b">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexTemplate">
<td class="doxyMemberIndexTemplate" colspan="2"><div>template &lt;typename UpdaterT&gt;</div></td>
</tr>
<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemTypeTemplate" align="left" valign="top">void</td>
<td class="doxyMemberIndexItemNameTemplate" align="left" valign="top"><a href="#aad5016c6fea77df1d3f4af224e1472db">FindPHIPlacement</a> (BlockListTy *BlockList)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>FindPHIPlacement - PHIs are needed in the iterated dominance frontiers of the known definitions. <a href="#aad5016c6fea77df1d3f4af224e1472db">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexTemplate">
<td class="doxyMemberIndexTemplate" colspan="2"><div>template &lt;typename UpdaterT&gt;</div></td>
</tr>
<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemTypeTemplate" align="left" valign="top">bool</td>
<td class="doxyMemberIndexItemNameTemplate" align="left" valign="top"><a href="#aa2056655c5376accdc268fe15b0683c3">FindSingularVal</a> (BBInfo *Info)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p><a href="/web-llvm/docs/api/namespaces/llvm/check">Check</a> all predecessors and if all of them have the same AvailableVal use it as value for block represented by Info. <a href="#aa2056655c5376accdc268fe15b0683c3">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexTemplate">
<td class="doxyMemberIndexTemplate" colspan="2"><div>template &lt;typename UpdaterT&gt;</div></td>
</tr>
<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemTypeTemplate" align="left" valign="top">void</td>
<td class="doxyMemberIndexItemNameTemplate" align="left" valign="top"><a href="#a3d50f3f3bb104fb854ac8de326c5bb64">FindAvailableVals</a> (BlockListTy *BlockList)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>FindAvailableVal - If this block requires a PHI, first check if an existing PHI matches the PHI placement and reaching definitions computed earlier, and if not, create a new PHI. <a href="#a3d50f3f3bb104fb854ac8de326c5bb64">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexTemplate">
<td class="doxyMemberIndexTemplate" colspan="2"><div>template &lt;typename UpdaterT&gt;</div></td>
</tr>
<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemTypeTemplate" align="left" valign="top">void</td>
<td class="doxyMemberIndexItemNameTemplate" align="left" valign="top"><a href="#a8c85661eda0e37ef407c2620c78a4186">FindExistingPHI</a> (BlkT *BB, BlockListTy *BlockList)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>FindExistingPHI - Look through the PHI nodes in a block to see if any of them match what is needed. <a href="#a8c85661eda0e37ef407c2620c78a4186">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexTemplate">
<td class="doxyMemberIndexTemplate" colspan="2"><div>template &lt;typename UpdaterT&gt;</div></td>
</tr>
<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemTypeTemplate" align="left" valign="top">bool</td>
<td class="doxyMemberIndexItemNameTemplate" align="left" valign="top"><a href="#a361f4564a774bbb16b4a27667256c5ad">CheckIfPHIMatches</a> (PhiT *PHI, SmallVectorImpl&lt; BBInfo * &gt; &amp;TaggedBlocks)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>CheckIfPHIMatches - <a href="/web-llvm/docs/api/namespaces/llvm/check">Check</a> if a PHI node matches the placement and values in the BBMap. <a href="#a361f4564a774bbb16b4a27667256c5ad">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexTemplate">
<td class="doxyMemberIndexTemplate" colspan="2"><div>template &lt;typename UpdaterT&gt;</div></td>
</tr>
<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemTypeTemplate" align="left" valign="top">void</td>
<td class="doxyMemberIndexItemNameTemplate" align="left" valign="top"><a href="#a15993d541998ac409f0fe09abfef6fe8">RecordMatchingPHIs</a> (BlockListTy *BlockList)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>RecordMatchingPHIs - For each PHI node that matches, record it in both the BBMap and the AvailableVals mapping. <a href="#a15993d541998ac409f0fe09abfef6fe8">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

</table>

## Private Member Attributes Index

<table class="doxyMembersIndex">

<tr class="doxyMemberIndexTemplate">
<td class="doxyMemberIndexTemplate" colspan="2"><div>template &lt;typename UpdaterT&gt;</div></td>
</tr>
<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemTypeTemplate" align="left" valign="top">UpdaterT *</td>
<td class="doxyMemberIndexItemNameTemplate" align="left" valign="top"><a href="#add38d53c84dc3df0119ec856ab2051bc">Updater</a></td>
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
<td class="doxyMemberIndexTemplate" colspan="2"><div>template &lt;typename UpdaterT&gt;</div></td>
</tr>
<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemTypeTemplate" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/densemap">AvailableValsTy</a> *</td>
<td class="doxyMemberIndexItemNameTemplate" align="left" valign="top"><a href="#a1c336acd8a51ac8367ed5716e9b5959c">AvailableVals</a></td>
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
<td class="doxyMemberIndexTemplate" colspan="2"><div>template &lt;typename UpdaterT&gt;</div></td>
</tr>
<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemTypeTemplate" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/smallvectorimpl">SmallVectorImpl</a>&lt; PhiT * &gt; *</td>
<td class="doxyMemberIndexItemNameTemplate" align="left" valign="top"><a href="#a70e48f9d3b9167dc97edd893b3a3c5a8">InsertedPHIs</a></td>
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
<td class="doxyMemberIndexTemplate" colspan="2"><div>template &lt;typename UpdaterT&gt;</div></td>
</tr>
<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemTypeTemplate" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/densemap">BBMapTy</a></td>
<td class="doxyMemberIndexItemNameTemplate" align="left" valign="top"><a href="#a46bd0cf95a415ac35a359555ebc8deb8">BBMap</a></td>
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
<td class="doxyMemberIndexTemplate" colspan="2"><div>template &lt;typename UpdaterT&gt;</div></td>
</tr>
<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemTypeTemplate" align="left" valign="top"><a href="/web-llvm/docs/api/namespaces/llvm/#a8e612822d4ba7bb36c9c79582a567108">BumpPtrAllocator</a></td>
<td class="doxyMemberIndexItemNameTemplate" align="left" valign="top"><a href="#a59dc15a0c906fab271863a88f8c86a43">Allocator</a></td>
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


<p>Definition at line 31 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/transforms/include/llvm/transforms/utils/ssaupdaterimpl-h">SSAUpdaterImpl.h</a>.</p>


<div class="doxySectionDef">

## Private Member Typedefs

### AvailableValsTy {#aef0766f16cb5480636bbd6a6087a75b4}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<div class="doxyMemberTemplate">template &lt;typename UpdaterT&gt;</div>
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">using llvm::SSAUpdaterImpl&lt; UpdaterT &gt;::AvailableValsTy =  DenseMap&lt;BlkT *, ValT&gt;</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 73 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/transforms/include/llvm/transforms/utils/ssaupdaterimpl-h">SSAUpdaterImpl.h</a>.</p>

</div>
</div>

### BBMapTy {#aba873fefc1e81e5db13366acab06fa47}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<div class="doxyMemberTemplate">template &lt;typename UpdaterT&gt;</div>
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">using llvm::SSAUpdaterImpl&lt; UpdaterT &gt;::BBMapTy =  DenseMap&lt;BlkT *, BBInfo *&gt;</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 80 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/transforms/include/llvm/transforms/utils/ssaupdaterimpl-h">SSAUpdaterImpl.h</a>.</p>

</div>
</div>

### BlkT {#a2ea9f05f9ff6796eb824ece16eb60708}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<div class="doxyMemberTemplate">template &lt;typename UpdaterT&gt;</div>
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">using llvm::SSAUpdaterImpl&lt; UpdaterT &gt;::BlkT =  typename Traits::BlkT</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 36 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/transforms/include/llvm/transforms/utils/ssaupdaterimpl-h">SSAUpdaterImpl.h</a>.</p>

</div>
</div>

### BlockListTy {#a8e2fa5790ddd0984480af9f42d00f2d0}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<div class="doxyMemberTemplate">template &lt;typename UpdaterT&gt;</div>
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">using llvm::SSAUpdaterImpl&lt; UpdaterT &gt;::BlockListTy =  SmallVectorImpl&lt;BBInfo *&gt;</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 79 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/transforms/include/llvm/transforms/utils/ssaupdaterimpl-h">SSAUpdaterImpl.h</a>.</p>

</div>
</div>

### PhiT {#a20e90f8e9ad4744b4d77b9534a4d9dec}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<div class="doxyMemberTemplate">template &lt;typename UpdaterT&gt;</div>
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">using llvm::SSAUpdaterImpl&lt; UpdaterT &gt;::PhiT =  typename Traits::PhiT</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 38 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/transforms/include/llvm/transforms/utils/ssaupdaterimpl-h">SSAUpdaterImpl.h</a>.</p>

</div>
</div>

### Traits {#a5c02d9afff1fb1b35cd113bf2a9ba908}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<div class="doxyMemberTemplate">template &lt;typename UpdaterT&gt;</div>
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">using llvm::SSAUpdaterImpl&lt; UpdaterT &gt;::Traits =  SSAUpdaterTraits&lt;UpdaterT&gt;</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 35 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/transforms/include/llvm/transforms/utils/ssaupdaterimpl-h">SSAUpdaterImpl.h</a>.</p>

</div>
</div>

### ValT {#a490100ebb370235ce8d04a6b4afa16c5}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<div class="doxyMemberTemplate">template &lt;typename UpdaterT&gt;</div>
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">using llvm::SSAUpdaterImpl&lt; UpdaterT &gt;::ValT =  typename Traits::ValT</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 37 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/transforms/include/llvm/transforms/utils/ssaupdaterimpl-h">SSAUpdaterImpl.h</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Public Constructors

### SSAUpdaterImpl() {#a5f421457a35ee1520ac43e4f7def256d}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<div class="doxyMemberTemplate">template &lt;typename UpdaterT&gt;</div>
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">llvm::SSAUpdaterImpl&lt; UpdaterT &gt;::SSAUpdaterImpl (UpdaterT * U, <a href="/web-llvm/docs/api/classes/llvm/densemap">AvailableValsTy</a> * A, <a href="/web-llvm/docs/api/classes/llvm/smallvectorimpl">SmallVectorImpl</a>&lt; PhiT * &gt; * Ins)</td>
</tr>
</table>
</td>
<td class="doxyMemberLabelsRight">
<span class="doxyMemberLabels">
<span class="doxyMemberLabel inline">inline</span>
<span class="doxyMemberLabel explicit">explicit</span>
</span>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 86 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/transforms/include/llvm/transforms/utils/ssaupdaterimpl-h">SSAUpdaterImpl.h</a>.</p>


<p>Reference <a href="/web-llvm/docs/api/files/lib/lib/ir/builtingcs-cpp/#a2e38c85003a042421cde1647632d0b72">A</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Public Member Functions

### BuildBlockList() {#a85cbdd891f1cd43d6c79f7d68a2caf46}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<div class="doxyMemberTemplate">template &lt;typename UpdaterT&gt;</div>
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">BBInfo * llvm::SSAUpdaterImpl&lt; UpdaterT &gt;::BuildBlockList (BlkT * BB, <a href="/web-llvm/docs/api/classes/llvm/smallvectorimpl">BlockListTy</a> * BlockList)</td>
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

<p>BuildBlockList - Starting from the specified basic block, traverse back through its predecessors until reaching blocks with known values.</p>


<p>Create BBInfo structures for the blocks and append them to the block list.</p>


<p>Definition at line 116 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/transforms/include/llvm/transforms/utils/ssaupdaterimpl-h">SSAUpdaterImpl.h</a>.</p>


<p>References <a href="/web-llvm/docs/api/classes/llvm/smallvectortemplatecommon/#acd9e771a3296c6b24146955754620557">llvm::SmallVectorTemplateCommon&lt; T, typename &gt;::back</a>, <a href="/web-llvm/docs/api/classes/llvm/smallvectorimpl/#aac0ea55010b7b1a301e65a0baea057aa">llvm::SmallVectorImpl&lt; T &gt;::clear</a>, <a href="/web-llvm/docs/api/files/lib/lib/ir/builtingcs-cpp/#abb2b3a60ccc38a28239e19a1646e0c8a">E</a>, <a href="/web-llvm/docs/api/classes/llvm/smallvectortemplatecommon/#ad9a3c7bc26b130377bbafc170b5f88a2">llvm::SmallVectorTemplateCommon&lt; T, typename &gt;::empty</a>, <a href="/web-llvm/docs/api/files/lib/lib/codegen/lib/codegen/globalisel/cseinfo-cpp/#a75f8a8519c2c9b30e7c06dc5e256fffa">Info</a>, <a href="/web-llvm/docs/api/classes/llvm/smallvectortemplatebase/#ad97688dfe9cd802e2a0691cbe620218a">llvm::SmallVectorTemplateBase&lt; T, bool &gt;::pop_back</a>, <a href="/web-llvm/docs/api/classes/llvm/smallvectorimpl/#a0c8ffe664a36e30d49c84d0aded2fe08">llvm::SmallVectorImpl&lt; T &gt;::pop_back_val</a>, <a href="/web-llvm/docs/api/classes/llvm/smallvectortemplatebase/#af42bfbc067df27c19ee2fc859df58799">llvm::SmallVectorTemplateBase&lt; T, bool &gt;::push_back</a> and <a href="/web-llvm/docs/api/classes/llvm/smallvectortemplatecommon/#a1c479a8c434377c2b8cb056bdfdfc201">llvm::SmallVectorTemplateCommon&lt; T, typename &gt;::size</a>.</p>


<p>Referenced by <a href="#a4f6c8ac18caa1b4beaf0d4d88b82cef9">llvm::SSAUpdaterImpl&lt; UpdaterT &gt;::GetValue</a>.</p>

</div>
</div>

### CheckIfPHIMatches() {#a361f4564a774bbb16b4a27667256c5ad}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<div class="doxyMemberTemplate">template &lt;typename UpdaterT&gt;</div>
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool llvm::SSAUpdaterImpl&lt; UpdaterT &gt;::CheckIfPHIMatches (PhiT * PHI, <a href="/web-llvm/docs/api/classes/llvm/smallvectorimpl">SmallVectorImpl</a>&lt; BBInfo * &gt; &amp; TaggedBlocks)</td>
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

<p>CheckIfPHIMatches - <a href="/web-llvm/docs/api/namespaces/llvm/check">Check</a> if a PHI node matches the placement and values in the BBMap.</p>

<p>Definition at line 427 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/transforms/include/llvm/transforms/utils/ssaupdaterimpl-h">SSAUpdaterImpl.h</a>.</p>


<p>References <a href="/web-llvm/docs/api/files/lib/lib/debuginfod/httpclient-cpp/#a0b91b2b50d54e38aa1e8e31e56c31357">Cleanup</a>, <a href="/web-llvm/docs/api/files/lib/lib/ir/builtingcs-cpp/#abb2b3a60ccc38a28239e19a1646e0c8a">E</a>, <a href="/web-llvm/docs/api/files/lib/lib/support/md5-cpp/#ac0eafdc9ee161b71e7af98af736952fd">I</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a1af45c4dc83c083c5ae914d96fd3ce96">llvm::make_scope_exit</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/amdgpurewriteundefforphi-cpp/#a2e83cb1bc3f5e8986cbd14575755a134">PHI</a> and <a href="/web-llvm/docs/api/classes/llvm/smallvectortemplatebase/#af42bfbc067df27c19ee2fc859df58799">llvm::SmallVectorTemplateBase&lt; T, bool &gt;::push_back</a>.</p>


<p>Referenced by <a href="#a8c85661eda0e37ef407c2620c78a4186">llvm::SSAUpdaterImpl&lt; UpdaterT &gt;::FindExistingPHI</a>.</p>

</div>
</div>

### FindAvailableVals() {#a3d50f3f3bb104fb854ac8de326c5bb64}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<div class="doxyMemberTemplate">template &lt;typename UpdaterT&gt;</div>
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void llvm::SSAUpdaterImpl&lt; UpdaterT &gt;::FindAvailableVals (<a href="/web-llvm/docs/api/classes/llvm/smallvectorimpl">BlockListTy</a> * BlockList)</td>
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

<p>FindAvailableVal - If this block requires a PHI, first check if an existing PHI matches the PHI placement and reaching definitions computed earlier, and if not, create a new PHI.</p>


<p>Visit all the block's predecessors to calculate the available value for each one and fill in the incoming values for a new PHI.</p>


<p>Definition at line 353 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/transforms/include/llvm/transforms/utils/ssaupdaterimpl-h">SSAUpdaterImpl.h</a>.</p>


<p>References <a href="/web-llvm/docs/api/classes/llvm/smallvectortemplatecommon/#a8a045d250952c0867382a9840ee18fdf">llvm::SmallVectorTemplateCommon&lt; T, typename &gt;::begin</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a7c46c742c31be54870e2038048e6b391">llvm::dbgs</a>, <a href="/web-llvm/docs/api/files/lib/lib/ir/builtingcs-cpp/#abb2b3a60ccc38a28239e19a1646e0c8a">E</a>, <a href="/web-llvm/docs/api/classes/llvm/smallvectortemplatecommon/#a075e34e98605d0e7c289763a104869ac">llvm::SmallVectorTemplateCommon&lt; T, typename &gt;::end</a>, <a href="#a8c85661eda0e37ef407c2620c78a4186">llvm::SSAUpdaterImpl&lt; UpdaterT &gt;::FindExistingPHI</a>, <a href="#aa2056655c5376accdc268fe15b0683c3">llvm::SSAUpdaterImpl&lt; UpdaterT &gt;::FindSingularVal</a>, <a href="/web-llvm/docs/api/files/lib/lib/support/md5-cpp/#ac0eafdc9ee161b71e7af98af736952fd">I</a>, <a href="/web-llvm/docs/api/files/lib/lib/codegen/lib/codegen/globalisel/cseinfo-cpp/#a75f8a8519c2c9b30e7c06dc5e256fffa">Info</a>, <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/support/debug-h/#a196897517069dda1bdb549e24468f7d7">LLVM_DEBUG</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/amdgpurewriteundefforphi-cpp/#a2e83cb1bc3f5e8986cbd14575755a134">PHI</a>, <a href="/web-llvm/docs/api/classes/llvm/smallvectortemplatecommon/#a23aab542398091e1fcfd46b6006d64ac">llvm::SmallVectorTemplateCommon&lt; T, typename &gt;::rbegin</a> and <a href="/web-llvm/docs/api/classes/llvm/smallvectortemplatecommon/#ad696953257cf1c4e5bd12d02146e7287">llvm::SmallVectorTemplateCommon&lt; T, typename &gt;::rend</a>.</p>


<p>Referenced by <a href="#a4f6c8ac18caa1b4beaf0d4d88b82cef9">llvm::SSAUpdaterImpl&lt; UpdaterT &gt;::GetValue</a>.</p>

</div>
</div>

### FindDominators() {#a0ab1c1435c29eea38d7a8dd64f064b84}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<div class="doxyMemberTemplate">template &lt;typename UpdaterT&gt;</div>
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void llvm::SSAUpdaterImpl&lt; UpdaterT &gt;::FindDominators (<a href="/web-llvm/docs/api/classes/llvm/smallvectorimpl">BlockListTy</a> * BlockList, BBInfo * PseudoEntry)</td>
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

<p>FindDominators - Calculate the dominator tree for the subset of the CFG corresponding to the basic blocks on the BlockList.</p>


<p>This uses the algorithm from: "A Simple, Fast Dominance Algorithm" by Cooper, Harvey and Kennedy, published in Software–Practice and Experience, 2001, 4:1-10. Because the CFG subset does not include any edges leading into blocks that define the value, the results are not the usual dominator tree. The CFG subset has a single pseudo-entry node with edges to a set of root nodes for blocks that define the value. The dominators for this subset CFG are not the standard dominators but they are adequate for placing PHIs within the subset CFG.</p>


<p>Definition at line 240 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/transforms/include/llvm/transforms/utils/ssaupdaterimpl-h">SSAUpdaterImpl.h</a>.</p>


<p>References <a href="/web-llvm/docs/api/files/lib/lib/ir/builtingcs-cpp/#abb2b3a60ccc38a28239e19a1646e0c8a">E</a>, <a href="/web-llvm/docs/api/files/lib/lib/support/md5-cpp/#ac0eafdc9ee161b71e7af98af736952fd">I</a>, <a href="/web-llvm/docs/api/files/lib/lib/codegen/lib/codegen/globalisel/cseinfo-cpp/#a75f8a8519c2c9b30e7c06dc5e256fffa">Info</a>, <a href="#ad25fe079e293e33582cbb5f3bf494bf5">llvm::SSAUpdaterImpl&lt; UpdaterT &gt;::IntersectDominators</a>, <a href="/web-llvm/docs/api/classes/llvm/smallvectortemplatecommon/#a23aab542398091e1fcfd46b6006d64ac">llvm::SmallVectorTemplateCommon&lt; T, typename &gt;::rbegin</a> and <a href="/web-llvm/docs/api/classes/llvm/smallvectortemplatecommon/#ad696953257cf1c4e5bd12d02146e7287">llvm::SmallVectorTemplateCommon&lt; T, typename &gt;::rend</a>.</p>


<p>Referenced by <a href="#a4f6c8ac18caa1b4beaf0d4d88b82cef9">llvm::SSAUpdaterImpl&lt; UpdaterT &gt;::GetValue</a>.</p>

</div>
</div>

### FindExistingPHI() {#a8c85661eda0e37ef407c2620c78a4186}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<div class="doxyMemberTemplate">template &lt;typename UpdaterT&gt;</div>
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void llvm::SSAUpdaterImpl&lt; UpdaterT &gt;::FindExistingPHI (BlkT * BB, <a href="/web-llvm/docs/api/classes/llvm/smallvectorimpl">BlockListTy</a> * BlockList)</td>
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

<p>FindExistingPHI - Look through the PHI nodes in a block to see if any of them match what is needed.</p>

<p>Definition at line 415 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/transforms/include/llvm/transforms/utils/ssaupdaterimpl-h">SSAUpdaterImpl.h</a>.</p>


<p>References <a href="#a361f4564a774bbb16b4a27667256c5ad">llvm::SSAUpdaterImpl&lt; UpdaterT &gt;::CheckIfPHIMatches</a> and <a href="#a15993d541998ac409f0fe09abfef6fe8">llvm::SSAUpdaterImpl&lt; UpdaterT &gt;::RecordMatchingPHIs</a>.</p>


<p>Referenced by <a href="#a3d50f3f3bb104fb854ac8de326c5bb64">llvm::SSAUpdaterImpl&lt; UpdaterT &gt;::FindAvailableVals</a>.</p>

</div>
</div>

### FindPHIPlacement() {#aad5016c6fea77df1d3f4af224e1472db}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<div class="doxyMemberTemplate">template &lt;typename UpdaterT&gt;</div>
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void llvm::SSAUpdaterImpl&lt; UpdaterT &gt;::FindPHIPlacement (<a href="/web-llvm/docs/api/classes/llvm/smallvectorimpl">BlockListTy</a> * BlockList)</td>
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

<p>FindPHIPlacement - PHIs are needed in the iterated dominance frontiers of the known definitions.</p>


<p>Iteratively add PHIs in the dom frontiers until nothing changes. Along the way, keep track of the nearest dominating definitions for non-PHI blocks.</p>


<p>Definition at line 294 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/transforms/include/llvm/transforms/utils/ssaupdaterimpl-h">SSAUpdaterImpl.h</a>.</p>


<p>References <a href="/web-llvm/docs/api/files/lib/lib/ir/builtingcs-cpp/#abb2b3a60ccc38a28239e19a1646e0c8a">E</a>, <a href="/web-llvm/docs/api/files/lib/lib/support/md5-cpp/#ac0eafdc9ee161b71e7af98af736952fd">I</a>, <a href="/web-llvm/docs/api/files/lib/lib/codegen/lib/codegen/globalisel/cseinfo-cpp/#a75f8a8519c2c9b30e7c06dc5e256fffa">Info</a>, <a href="#a42e6b449c6b8fe1fa8d10f2f300f7e9b">llvm::SSAUpdaterImpl&lt; UpdaterT &gt;::IsDefInDomFrontier</a>, <a href="/web-llvm/docs/api/classes/llvm/smallvectortemplatecommon/#a23aab542398091e1fcfd46b6006d64ac">llvm::SmallVectorTemplateCommon&lt; T, typename &gt;::rbegin</a> and <a href="/web-llvm/docs/api/classes/llvm/smallvectortemplatecommon/#ad696953257cf1c4e5bd12d02146e7287">llvm::SmallVectorTemplateCommon&lt; T, typename &gt;::rend</a>.</p>


<p>Referenced by <a href="#a4f6c8ac18caa1b4beaf0d4d88b82cef9">llvm::SSAUpdaterImpl&lt; UpdaterT &gt;::GetValue</a>.</p>

</div>
</div>

### FindSingularVal() {#aa2056655c5376accdc268fe15b0683c3}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<div class="doxyMemberTemplate">template &lt;typename UpdaterT&gt;</div>
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool llvm::SSAUpdaterImpl&lt; UpdaterT &gt;::FindSingularVal (BBInfo * Info)</td>
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

<p><a href="/web-llvm/docs/api/namespaces/llvm/check">Check</a> all predecessors and if all of them have the same AvailableVal use it as value for block represented by Info.</p>


<p>Return true if singluar value is found.</p>


<p>Definition at line 329 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/transforms/include/llvm/transforms/utils/ssaupdaterimpl-h">SSAUpdaterImpl.h</a>.</p>


<p>References <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/silowercontrolflow-cpp/#a4868c5d81c5ccc98c47aeab6244346a0">assert</a> and <a href="/web-llvm/docs/api/files/lib/lib/codegen/lib/codegen/globalisel/cseinfo-cpp/#a75f8a8519c2c9b30e7c06dc5e256fffa">Info</a>.</p>


<p>Referenced by <a href="#a3d50f3f3bb104fb854ac8de326c5bb64">llvm::SSAUpdaterImpl&lt; UpdaterT &gt;::FindAvailableVals</a>.</p>

</div>
</div>

### GetValue() {#a4f6c8ac18caa1b4beaf0d4d88b82cef9}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<div class="doxyMemberTemplate">template &lt;typename UpdaterT&gt;</div>
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">ValT llvm::SSAUpdaterImpl&lt; UpdaterT &gt;::GetValue (BlkT * BB)</td>
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

<p>GetValue - <a href="/web-llvm/docs/api/namespaces/llvm/check">Check</a> to see if AvailableVals has an entry for the specified BB and if so, return it.</p>


<p>If not, construct SSA form by first calculating the required placement of PHIs and then inserting new PHIs where needed.</p>


<p>Definition at line 94 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/transforms/include/llvm/transforms/utils/ssaupdaterimpl-h">SSAUpdaterImpl.h</a>.</p>


<p>References <a href="#a85cbdd891f1cd43d6c79f7d68a2caf46">llvm::SSAUpdaterImpl&lt; UpdaterT &gt;::BuildBlockList</a>, <a href="#a3d50f3f3bb104fb854ac8de326c5bb64">llvm::SSAUpdaterImpl&lt; UpdaterT &gt;::FindAvailableVals</a>, <a href="#a0ab1c1435c29eea38d7a8dd64f064b84">llvm::SSAUpdaterImpl&lt; UpdaterT &gt;::FindDominators</a>, <a href="#aad5016c6fea77df1d3f4af224e1472db">llvm::SSAUpdaterImpl&lt; UpdaterT &gt;::FindPHIPlacement</a> and <a href="/web-llvm/docs/api/classes/llvm/smallvectortemplatecommon/#a1c479a8c434377c2b8cb056bdfdfc201">llvm::SmallVectorTemplateCommon&lt; T, typename &gt;::size</a>.</p>

</div>
</div>

### IntersectDominators() {#ad25fe079e293e33582cbb5f3bf494bf5}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<div class="doxyMemberTemplate">template &lt;typename UpdaterT&gt;</div>
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">BBInfo * llvm::SSAUpdaterImpl&lt; UpdaterT &gt;::IntersectDominators (BBInfo * Blk1, BBInfo * Blk2)</td>
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

<p>IntersectDominators - This is the dataflow lattice "meet" operation for finding dominators.</p>


<p>Given two basic blocks, it walks up the dominator tree until it finds a common dominator of both. It uses the postorder number of the blocks to determine how to do that.</p>


<p>Definition at line 214 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/transforms/include/llvm/transforms/utils/ssaupdaterimpl-h">SSAUpdaterImpl.h</a>.</p>


<p>Referenced by <a href="#a0ab1c1435c29eea38d7a8dd64f064b84">llvm::SSAUpdaterImpl&lt; UpdaterT &gt;::FindDominators</a>.</p>

</div>
</div>

### IsDefInDomFrontier() {#a42e6b449c6b8fe1fa8d10f2f300f7e9b}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<div class="doxyMemberTemplate">template &lt;typename UpdaterT&gt;</div>
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool llvm::SSAUpdaterImpl&lt; UpdaterT &gt;::IsDefInDomFrontier (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> BBInfo * Pred, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> BBInfo * IDom)</td>
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

<p>IsDefInDomFrontier - Search up the dominator tree from Pred to IDom for any blocks containing definitions of the value.</p>


<p>If one is found, then the successor of Pred is in the dominance frontier for the definition, and this function returns true.</p>


<p>Definition at line 282 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/transforms/include/llvm/transforms/utils/ssaupdaterimpl-h">SSAUpdaterImpl.h</a>.</p>


<p>Referenced by <a href="#aad5016c6fea77df1d3f4af224e1472db">llvm::SSAUpdaterImpl&lt; UpdaterT &gt;::FindPHIPlacement</a>.</p>

</div>
</div>

### RecordMatchingPHIs() {#a15993d541998ac409f0fe09abfef6fe8}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<div class="doxyMemberTemplate">template &lt;typename UpdaterT&gt;</div>
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void llvm::SSAUpdaterImpl&lt; UpdaterT &gt;::RecordMatchingPHIs (<a href="/web-llvm/docs/api/classes/llvm/smallvectorimpl">BlockListTy</a> * BlockList)</td>
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

<p>RecordMatchingPHIs - For each PHI node that matches, record it in both the BBMap and the AvailableVals mapping.</p>

<p>Definition at line 487 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/transforms/include/llvm/transforms/utils/ssaupdaterimpl-h">SSAUpdaterImpl.h</a>.</p>


<p>References <a href="/web-llvm/docs/api/classes/llvm/smallvectortemplatecommon/#a8a045d250952c0867382a9840ee18fdf">llvm::SmallVectorTemplateCommon&lt; T, typename &gt;::begin</a>, <a href="/web-llvm/docs/api/files/lib/lib/ir/builtingcs-cpp/#abb2b3a60ccc38a28239e19a1646e0c8a">E</a>, <a href="/web-llvm/docs/api/classes/llvm/smallvectortemplatecommon/#a075e34e98605d0e7c289763a104869ac">llvm::SmallVectorTemplateCommon&lt; T, typename &gt;::end</a>, <a href="/web-llvm/docs/api/files/lib/lib/support/md5-cpp/#ac0eafdc9ee161b71e7af98af736952fd">I</a> and <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/amdgpurewriteundefforphi-cpp/#a2e83cb1bc3f5e8986cbd14575755a134">PHI</a>.</p>


<p>Referenced by <a href="#a8c85661eda0e37ef407c2620c78a4186">llvm::SSAUpdaterImpl&lt; UpdaterT &gt;::FindExistingPHI</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Private Member Attributes

### Allocator {#a59dc15a0c906fab271863a88f8c86a43}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<div class="doxyMemberTemplate">template &lt;typename UpdaterT&gt;</div>
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">BumpPtrAllocator llvm::SSAUpdaterImpl&lt; UpdaterT &gt;::Allocator</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 83 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/transforms/include/llvm/transforms/utils/ssaupdaterimpl-h">SSAUpdaterImpl.h</a>.</p>

</div>
</div>

### AvailableVals {#a1c336acd8a51ac8367ed5716e9b5959c}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<div class="doxyMemberTemplate">template &lt;typename UpdaterT&gt;</div>
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">AvailableValsTy* llvm::SSAUpdaterImpl&lt; UpdaterT &gt;::AvailableVals</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 75 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/transforms/include/llvm/transforms/utils/ssaupdaterimpl-h">SSAUpdaterImpl.h</a>.</p>

</div>
</div>

### BBMap {#a46bd0cf95a415ac35a359555ebc8deb8}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<div class="doxyMemberTemplate">template &lt;typename UpdaterT&gt;</div>
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">BBMapTy llvm::SSAUpdaterImpl&lt; UpdaterT &gt;::BBMap</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 82 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/transforms/include/llvm/transforms/utils/ssaupdaterimpl-h">SSAUpdaterImpl.h</a>.</p>

</div>
</div>

### InsertedPHIs {#a70e48f9d3b9167dc97edd893b3a3c5a8}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<div class="doxyMemberTemplate">template &lt;typename UpdaterT&gt;</div>
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">SmallVectorImpl&lt;PhiT *&gt;* llvm::SSAUpdaterImpl&lt; UpdaterT &gt;::InsertedPHIs</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 77 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/transforms/include/llvm/transforms/utils/ssaupdaterimpl-h">SSAUpdaterImpl.h</a>.</p>

</div>
</div>

### Updater {#add38d53c84dc3df0119ec856ab2051bc}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<div class="doxyMemberTemplate">template &lt;typename UpdaterT&gt;</div>
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">UpdaterT* llvm::SSAUpdaterImpl&lt; UpdaterT &gt;::Updater</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 33 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/transforms/include/llvm/transforms/utils/ssaupdaterimpl-h">SSAUpdaterImpl.h</a>.</p>

</div>
</div>

</div>

<hr/>

The documentation for this class was generated from the following file:

<ul>
<li><a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/transforms/include/llvm/transforms/utils/ssaupdaterimpl-h">SSAUpdaterImpl.h</a></li>
</ul>

<hr/>

<p class="doxyGeneratedBy">Generated via <a href="https://github.com/xpack/doxygen2docusaurus">doxygen2docusaurus</a> by <a href="https://www.doxygen.nl">Doxygen</a> 1.15.0.</p>

</div>
