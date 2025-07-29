---

# DO NOT EDIT!
# Automatically generated via doxygen2docusaurus by Doxygen.

slug: /api/structs/llvm/tileinfo
custom_edit_url: null
toc_max_heading_level: 4
keywords:
  - doxygen
  - reference
  - struct

---

<div class="doxyPage">

# `TileInfo` Struct

<p>A helper struct to create IR loop nests for tiling in IR of the following form: for ColumnLoop.Index = 0..NumColumns for RowLoop.Index = 0..NumRows for KLoop.Index = 0..NumInner. <a href="#details">More...</a></p>

## Declaration

<div class="doxyDeclaration">
struct llvm::TileInfo { ... }
</div>

## Included Headers

<div class="doxyIncludesList">#include "<a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/transforms/include/llvm/transforms/utils/matrixutils-h">llvm/Transforms/Utils/MatrixUtils.h</a>"
</div>

## Public Constructors Index

<table class="doxyMembersIndex">

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a9afab8d2da3126b5a96ad1ead181f32f">TileInfo</a> (unsigned NumRows, unsigned NumColumns, unsigned NumInner, unsigned TileSize)</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/basicblock">BasicBlock</a> *</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a8547d158fd9eb8e0cb27673ac3034a1c">CreateTiledLoops</a> (BasicBlock *Start, BasicBlock *End, IRBuilderBase &amp;B, DomTreeUpdater &amp;DTU, LoopInfo &amp;LI)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Creates an IR loop nests for tiling of the form below. <a href="#a8547d158fd9eb8e0cb27673ac3034a1c">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

</table>

## Public Member Attributes Index

<table class="doxyMembersIndex">

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">unsigned</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a4d7f66cf9378e5d805eb7487829c99fd">NumRows</a></td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Number of rows of the matrix. <a href="#a4d7f66cf9378e5d805eb7487829c99fd">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">unsigned</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a875ddebc5962ba98bd7e090f5951687e">NumColumns</a></td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Number of columns of the matrix. <a href="#a875ddebc5962ba98bd7e090f5951687e">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">unsigned</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a21b1735a7e34df5c9bb4f706fc6cfadc">NumInner</a></td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Number of columns of the first matrix of a multiply / number of rows of the second matrix of a multiply. <a href="#a21b1735a7e34df5c9bb4f706fc6cfadc">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">unsigned</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#abea2744097436ef6ca24ccb940193ad3">TileSize</a> = -1</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Number of rows/columns in a tile. <a href="#abea2744097436ef6ca24ccb940193ad3">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/structs/llvm/tileinfo/matrixloop">MatrixLoop</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a3e06087e90c0e4057bdc3fe3b0ec5904">RowLoop</a></td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>The loop iterating on the rows. <a href="#a3e06087e90c0e4057bdc3fe3b0ec5904">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/structs/llvm/tileinfo/matrixloop">MatrixLoop</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a3159a958f6b4f8b6d76d34964649237c">ColumnLoop</a></td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>The loop iterating on the columns. <a href="#a3159a958f6b4f8b6d76d34964649237c">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/structs/llvm/tileinfo/matrixloop">MatrixLoop</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#acf6bd724509861d665d98379be763344">KLoop</a></td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>The loop iterating on k (inner dimension). <a href="#acf6bd724509861d665d98379be763344">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

</table>

## Private Static Functions Index

<table class="doxyMembersIndex">

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">static <a href="/web-llvm/docs/api/classes/llvm/basicblock">BasicBlock</a> *</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a7f4198a66aa15f9f616af5b00d2dc1eb">CreateLoop</a> (BasicBlock *Preheader, BasicBlock *Exit, Value *Bound, Value *Step, StringRef Name, IRBuilderBase &amp;B, DomTreeUpdater &amp;DTU, Loop *L, LoopInfo &amp;LI)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Creates a new loop with header, body and latch blocks that iterates from [0, Bound). <a href="#a7f4198a66aa15f9f616af5b00d2dc1eb">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

</table>

## Description {#details}

<p>A helper struct to create IR loop nests for tiling in IR of the following form: for ColumnLoop.Index = 0..NumColumns for RowLoop.Index = 0..NumRows for KLoop.Index = 0..NumInner.</p>

<p>Definition at line 31 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/transforms/include/llvm/transforms/utils/matrixutils-h">MatrixUtils.h</a>.</p>


<div class="doxySectionDef">

## Public Constructors

### TileInfo() {#a9afab8d2da3126b5a96ad1ead181f32f}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">llvm::TileInfo::TileInfo (unsigned NumRows, unsigned NumColumns, unsigned NumInner, unsigned TileSize)</td>
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



<p>Definition at line 61 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/transforms/include/llvm/transforms/utils/matrixutils-h">MatrixUtils.h</a>.</p>


<p>References <a href="#a875ddebc5962ba98bd7e090f5951687e">NumColumns</a>, <a href="#a21b1735a7e34df5c9bb4f706fc6cfadc">NumInner</a>, <a href="#a4d7f66cf9378e5d805eb7487829c99fd">NumRows</a> and <a href="#abea2744097436ef6ca24ccb940193ad3">TileSize</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Public Member Functions

### CreateTiledLoops() {#a8547d158fd9eb8e0cb27673ac3034a1c}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">BasicBlock * TileInfo::CreateTiledLoops (<a href="/web-llvm/docs/api/classes/llvm/basicblock">BasicBlock</a> * Start, <a href="/web-llvm/docs/api/classes/llvm/basicblock">BasicBlock</a> * End, <a href="/web-llvm/docs/api/classes/llvm/irbuilderbase">IRBuilderBase</a> &amp; B, <a href="/web-llvm/docs/api/classes/llvm/domtreeupdater">DomTreeUpdater</a> &amp; DTU, <a href="/web-llvm/docs/api/classes/llvm/loopinfo">LoopInfo</a> &amp; LI)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Creates an IR loop nests for tiling of the form below.</p>


<p>Returns the block for the inner loop body and sets {Column,Row,Inner}LoopHeader/Latch fields.</p>


<p>for ColumnLoop.Index = 0..NumColumns for RowLoop.Index = 0..NumRows for InnerLoop.Index = 0..NumInner</p>


<p>Declaration at line 73 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/transforms/include/llvm/transforms/utils/matrixutils-h">MatrixUtils.h</a>, definition at line 70 of file <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/utils/matrixutils-cpp">MatrixUtils.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/classes/llvm/loopbase/#a990a86b0de7a84a9f489d2034878e330">llvm::LoopBase&lt; BlockT, LoopT &gt;::addChildLoop</a>, <a href="/web-llvm/docs/api/classes/llvm/loopinfobase/#a1e4ac7b073d744d43f3cb1a3660c03c3">llvm::LoopInfoBase&lt; BlockT, LoopT &gt;::addTopLevelLoop</a>, <a href="/web-llvm/docs/api/classes/llvm/loopinfobase/#a5a0ae49bf720341774a25029fd23bf59">llvm::LoopInfoBase&lt; BlockT, LoopT &gt;::AllocateLoop</a>, <a href="/web-llvm/docs/api/files/lib/lib/ir/builtingcs-cpp/#ae76959fe811ba090de4cba69ac00f1da">B</a>, <a href="#a3159a958f6b4f8b6d76d34964649237c">ColumnLoop</a>, <a href="/web-llvm/docs/api/classes/llvm/loopinfobase/#ad61bd84d4988c90bf6c5cd62d8e7fb00">llvm::LoopInfoBase&lt; BlockT, LoopT &gt;::getLoopFor</a>, <a href="/web-llvm/docs/api/classes/llvm/basicblock/#a59fb91d1691350f7d1b8e8a114e3f2a4">llvm::BasicBlock::getSinglePredecessor</a>, <a href="/web-llvm/docs/api/classes/llvm/basicblock/#a79c007dcf9fff57e1569e778d7885b5e">llvm::BasicBlock::getSingleSuccessor</a>, <a href="#acf6bd724509861d665d98379be763344">KLoop</a>, <a href="#a875ddebc5962ba98bd7e090f5951687e">NumColumns</a>, <a href="#a21b1735a7e34df5c9bb4f706fc6cfadc">NumInner</a>, <a href="#a4d7f66cf9378e5d805eb7487829c99fd">NumRows</a>, <a href="#a3e06087e90c0e4057bdc3fe3b0ec5904">RowLoop</a> and <a href="#abea2744097436ef6ca24ccb940193ad3">TileSize</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/classes/anonymous-lowermatrixintrinsics-cpp-/lowermatrixintrinsics/#a1fb67d47830d47e72144d7456dbb7fa0">anonymous{LowerMatrixIntrinsics.cpp}::LowerMatrixIntrinsics::createTiledLoops</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Public Member Attributes

### ColumnLoop {#a3159a958f6b4f8b6d76d34964649237c}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">MatrixLoop llvm::TileInfo::ColumnLoop</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>The loop iterating on the columns.</p>

<p>Definition at line 57 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/transforms/include/llvm/transforms/utils/matrixutils-h">MatrixUtils.h</a>.</p>


<p>Referenced by <a href="#a8547d158fd9eb8e0cb27673ac3034a1c">CreateTiledLoops</a> and <a href="/web-llvm/docs/api/classes/anonymous-lowermatrixintrinsics-cpp-/lowermatrixintrinsics/#a1fb67d47830d47e72144d7456dbb7fa0">anonymous{LowerMatrixIntrinsics.cpp}::LowerMatrixIntrinsics::createTiledLoops</a>.</p>

</div>
</div>

### KLoop {#acf6bd724509861d665d98379be763344}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">MatrixLoop llvm::TileInfo::KLoop</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>The loop iterating on k (inner dimension).</p>

<p>Definition at line 59 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/transforms/include/llvm/transforms/utils/matrixutils-h">MatrixUtils.h</a>.</p>


<p>Referenced by <a href="#a8547d158fd9eb8e0cb27673ac3034a1c">CreateTiledLoops</a> and <a href="/web-llvm/docs/api/classes/anonymous-lowermatrixintrinsics-cpp-/lowermatrixintrinsics/#a1fb67d47830d47e72144d7456dbb7fa0">anonymous{LowerMatrixIntrinsics.cpp}::LowerMatrixIntrinsics::createTiledLoops</a>.</p>

</div>
</div>

### NumColumns {#a875ddebc5962ba98bd7e090f5951687e}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">unsigned llvm::TileInfo::NumColumns</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Number of columns of the matrix.</p>

<p>Definition at line 36 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/transforms/include/llvm/transforms/utils/matrixutils-h">MatrixUtils.h</a>.</p>


<p>Referenced by <a href="#a8547d158fd9eb8e0cb27673ac3034a1c">CreateTiledLoops</a> and <a href="#a9afab8d2da3126b5a96ad1ead181f32f">TileInfo</a>.</p>

</div>
</div>

### NumInner {#a21b1735a7e34df5c9bb4f706fc6cfadc}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">unsigned llvm::TileInfo::NumInner</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Number of columns of the first matrix of a multiply / number of rows of the second matrix of a multiply.</p>

<p>Definition at line 40 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/transforms/include/llvm/transforms/utils/matrixutils-h">MatrixUtils.h</a>.</p>


<p>Referenced by <a href="#a8547d158fd9eb8e0cb27673ac3034a1c">CreateTiledLoops</a> and <a href="#a9afab8d2da3126b5a96ad1ead181f32f">TileInfo</a>.</p>

</div>
</div>

### NumRows {#a4d7f66cf9378e5d805eb7487829c99fd}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">unsigned llvm::TileInfo::NumRows</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Number of rows of the matrix.</p>

<p>Definition at line 33 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/transforms/include/llvm/transforms/utils/matrixutils-h">MatrixUtils.h</a>.</p>


<p>Referenced by <a href="#a8547d158fd9eb8e0cb27673ac3034a1c">CreateTiledLoops</a> and <a href="#a9afab8d2da3126b5a96ad1ead181f32f">TileInfo</a>.</p>

</div>
</div>

### RowLoop {#a3e06087e90c0e4057bdc3fe3b0ec5904}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">MatrixLoop llvm::TileInfo::RowLoop</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>The loop iterating on the rows.</p>

<p>Definition at line 55 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/transforms/include/llvm/transforms/utils/matrixutils-h">MatrixUtils.h</a>.</p>


<p>Referenced by <a href="#a8547d158fd9eb8e0cb27673ac3034a1c">CreateTiledLoops</a> and <a href="/web-llvm/docs/api/classes/anonymous-lowermatrixintrinsics-cpp-/lowermatrixintrinsics/#a1fb67d47830d47e72144d7456dbb7fa0">anonymous{LowerMatrixIntrinsics.cpp}::LowerMatrixIntrinsics::createTiledLoops</a>.</p>

</div>
</div>

### TileSize {#abea2744097436ef6ca24ccb940193ad3}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">unsigned llvm::TileInfo::TileSize = -1</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Number of rows/columns in a tile.</p>

<p>Definition at line 43 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/transforms/include/llvm/transforms/utils/matrixutils-h">MatrixUtils.h</a>.</p>


<p>Referenced by <a href="#a8547d158fd9eb8e0cb27673ac3034a1c">CreateTiledLoops</a> and <a href="#a9afab8d2da3126b5a96ad1ead181f32f">TileInfo</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Private Static Functions

### CreateLoop() {#a7f4198a66aa15f9f616af5b00d2dc1eb}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">BasicBlock * TileInfo::CreateLoop (<a href="/web-llvm/docs/api/classes/llvm/basicblock">BasicBlock</a> * Preheader, <a href="/web-llvm/docs/api/classes/llvm/basicblock">BasicBlock</a> * Exit, <a href="/web-llvm/docs/api/classes/llvm/value">Value</a> * Bound, <a href="/web-llvm/docs/api/classes/llvm/value">Value</a> * Step, <a href="/web-llvm/docs/api/classes/llvm/stringref">StringRef</a> Name, <a href="/web-llvm/docs/api/classes/llvm/irbuilderbase">IRBuilderBase</a> &amp; B, <a href="/web-llvm/docs/api/classes/llvm/domtreeupdater">DomTreeUpdater</a> &amp; DTU, <a href="/web-llvm/docs/api/classes/llvm/loop">Loop</a> * L, <a href="/web-llvm/docs/api/classes/llvm/loopinfo">LoopInfo</a> &amp; LI)</td>
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

<p>Creates a new loop with header, body and latch blocks that iterates from [0, Bound).</p>


<p>Updates <span class="doxyComputerOutput">Preheader</span> to branch to the new header and uses <span class="doxyComputerOutput">Exit</span> as exit block. Adds the new loop blocks to \L and applies dominator tree updates to <span class="doxyComputerOutput">DTU</span>.</p>


<p>Declaration at line 82 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/transforms/include/llvm/transforms/utils/matrixutils-h">MatrixUtils.h</a>, definition at line 23 of file <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/utils/matrixutils-cpp">MatrixUtils.cpp</a>.</p>

</div>
</div>

</div>

<hr/>

The documentation for this struct was generated from the following files:

<ul>
<li><a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/transforms/include/llvm/transforms/utils/matrixutils-h">MatrixUtils.h</a></li>
<li><a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/utils/matrixutils-cpp">MatrixUtils.cpp</a></li>
</ul>

<hr/>

<p class="doxyGeneratedBy">Generated via <a href="https://github.com/xpack/doxygen2docusaurus">doxygen2docusaurus</a> by <a href="https://www.doxygen.nl">Doxygen</a> 1.15.0.</p>

</div>
