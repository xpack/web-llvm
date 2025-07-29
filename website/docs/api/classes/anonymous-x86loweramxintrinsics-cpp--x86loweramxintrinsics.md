---

# DO NOT EDIT!
# Automatically generated via doxygen2docusaurus by Doxygen.

slug: /api/classes/anonymous-x86loweramxintrinsics-cpp-/x86loweramxintrinsics
custom_edit_url: null
toc_max_heading_level: 4
keywords:
  - doxygen
  - reference
  - class

---

<div class="doxyPage">

# `X86LowerAMXIntrinsics` Class



## Declaration

<div class="doxyDeclaration">
class anonymous{X86LowerAMXIntrinsics.cpp}::X86LowerAMXIntrinsics { ... }
</div>

## Public Constructors Index

<table class="doxyMembersIndex">

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a14d37bda314974c5ebe60c602e68bfa3">X86LowerAMXIntrinsics</a> (Function &amp;F, DomTreeUpdater &amp;DomTU, LoopInfo *LoopI)</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#afd8404fba4a01a50928ea2d51954afb7">visit</a> ()</td>
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
<td class="doxyMemberIndexTemplate" colspan="2"><div>template &lt;bool IsTileLoad&gt;</div></td>
</tr>
<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemTypeTemplate" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/value">Value</a> *</td>
<td class="doxyMemberIndexItemNameTemplate" align="left" valign="top"><a href="#a991aa40e1236f6093ee0c3d93628319c">createTileLoadStoreLoops</a> (BasicBlock *Start, BasicBlock *End, IRBuilderBase &amp;B, Value *Row, Value *Col, Value *Ptr, Value *Stride, Value *Tile)</td>
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
<td class="doxyMemberIndexTemplate" colspan="2"><div>template &lt;Intrinsic::ID IntrID&gt;</div></td>
</tr>
<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemTypeTemplate" align="left" valign="top">auto </td>
<td class="doxyMemberIndexItemNameTemplate" align="left" valign="top"><a href="#a5f7b74afe2d1d4f3cc3373cd8af2e6ad">createTileDPLoops</a> (BasicBlock *Start, BasicBlock *End, IRBuilderBase &amp;B, Value *Row, Value *Col, Value *K, Value *Acc, Value *LHS, Value *RHS) -&gt; std::enable_if_t&lt; IntrID==Intrinsic::x86_tdpbssd_internal||IntrID==Intrinsic::x86_tdpbsud_internal||IntrID==Intrinsic::x86_tdpbusd_internal||IntrID==Intrinsic::x86_tdpbuud_internal||IntrID==Intrinsic::x86_tdpbf16ps_internal, <a href="/web-llvm/docs/api/classes/llvm/value">Value</a> * &gt;</td>
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
<td class="doxyMemberIndexTemplate" colspan="2"><div>template &lt;Intrinsic::ID IntrID&gt;</div></td>
</tr>
<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemTypeTemplate" align="left" valign="top">auto </td>
<td class="doxyMemberIndexItemNameTemplate" align="left" valign="top"><a href="#a79f47e97963f500c113eb9bfee2e5b47">lowerTileDP</a> (Instruction *TileDP) -&gt; std::enable_if_t&lt; IntrID==Intrinsic::x86_tdpbssd_internal||IntrID==Intrinsic::x86_tdpbsud_internal||IntrID==Intrinsic::x86_tdpbusd_internal||IntrID==Intrinsic::x86_tdpbuud_internal||IntrID==Intrinsic::x86_tdpbf16ps_internal, bool &gt;</td>
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
<td class="doxyMemberIndexTemplate" colspan="2"><div>template &lt;bool IsTileLoad&gt;</div></td>
</tr>
<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemTypeTemplate" align="left" valign="top">bool</td>
<td class="doxyMemberIndexItemNameTemplate" align="left" valign="top"><a href="#aabc37fb487455e5268d389333bc5c890">lowerTileLoadStore</a> (Instruction *TileLoadStore)</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/basicblock">BasicBlock</a> *</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#afbbbb5228107fd52d04b975fd15e1fb9">createLoop</a> (BasicBlock *Preheader, BasicBlock *Exit, Value *Bound, Value *Step, StringRef Name, IRBuilderBase &amp;B, Loop *L)</td>
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
<td class="doxyMemberIndexTemplate" colspan="2"><div>template &lt;bool IsTileLoad&gt;</div></td>
</tr>
<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemTypeTemplate" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/value">Value</a> *</td>
<td class="doxyMemberIndexItemNameTemplate" align="left" valign="top"><a href="#a991aa40e1236f6093ee0c3d93628319c">createTileLoadStoreLoops</a> (BasicBlock *Start, BasicBlock *End, IRBuilderBase &amp;B, Value *Row, Value *Col, Value *Ptr, Value *Stride, Value *Tile)</td>
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
<td class="doxyMemberIndexTemplate" colspan="2"><div>template &lt;Intrinsic::ID IntrID&gt;</div></td>
</tr>
<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemTypeTemplate" align="left" valign="top">auto </td>
<td class="doxyMemberIndexItemNameTemplate" align="left" valign="top"><a href="#a5f7b74afe2d1d4f3cc3373cd8af2e6ad">createTileDPLoops</a> (BasicBlock *Start, BasicBlock *End, IRBuilderBase &amp;B, Value *Row, Value *Col, Value *K, Value *Acc, Value *LHS, Value *RHS) -&gt; std::enable_if_t&lt; IntrID==Intrinsic::x86_tdpbssd_internal||IntrID==Intrinsic::x86_tdpbsud_internal||IntrID==Intrinsic::x86_tdpbusd_internal||IntrID==Intrinsic::x86_tdpbuud_internal||IntrID==Intrinsic::x86_tdpbf16ps_internal, <a href="/web-llvm/docs/api/classes/llvm/value">Value</a> * &gt;</td>
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
<td class="doxyMemberIndexTemplate" colspan="2"><div>template &lt;bool IsTileLoad&gt;</div></td>
</tr>
<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemTypeTemplate" align="left" valign="top">bool</td>
<td class="doxyMemberIndexItemNameTemplate" align="left" valign="top"><a href="#aabc37fb487455e5268d389333bc5c890">lowerTileLoadStore</a> (Instruction *TileLoadStore)</td>
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
<td class="doxyMemberIndexTemplate" colspan="2"><div>template &lt;Intrinsic::ID IntrID&gt;</div></td>
</tr>
<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemTypeTemplate" align="left" valign="top">auto </td>
<td class="doxyMemberIndexItemNameTemplate" align="left" valign="top"><a href="#a79f47e97963f500c113eb9bfee2e5b47">lowerTileDP</a> (Instruction *TileDP) -&gt; std::enable_if_t&lt; IntrID==Intrinsic::x86_tdpbssd_internal||IntrID==Intrinsic::x86_tdpbsud_internal||IntrID==Intrinsic::x86_tdpbusd_internal||IntrID==Intrinsic::x86_tdpbuud_internal||IntrID==Intrinsic::x86_tdpbf16ps_internal, bool &gt;</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ae5c84017c7546f3d878b7b195e0a476d">lowerTileZero</a> (Instruction *TileZero)</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/function">Function</a> &amp;</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a7bb626df8440038b0ea43cf68d9ebd18">Func</a></td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/domtreeupdater">DomTreeUpdater</a> &amp;</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ae40977978a58148b8827ca2380f94666">DTU</a></td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a3f4244257c72a5745da3d256808201a7">LI</a></td>
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


<p>Definition at line 59 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/x86/x86loweramxintrinsics-cpp">X86LowerAMXIntrinsics.cpp</a>.</p>


<div class="doxySectionDef">

## Public Constructors

### X86LowerAMXIntrinsics() {#a14d37bda314974c5ebe60c602e68bfa3}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">anonymous{X86LowerAMXIntrinsics.cpp}::X86LowerAMXIntrinsics::X86LowerAMXIntrinsics (<a href="/web-llvm/docs/api/classes/llvm/function">Function</a> &amp; F, <a href="/web-llvm/docs/api/classes/llvm/domtreeupdater">DomTreeUpdater</a> &amp; DomTU, <a href="/web-llvm/docs/api/classes/llvm/loopinfo">LoopInfo</a> * LoopI)</td>
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



<p>Definition at line 63 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/x86/x86loweramxintrinsics-cpp">X86LowerAMXIntrinsics.cpp</a>.</p>


<p>Reference <a href="/web-llvm/docs/api/files/lib/lib/support/md5-cpp/#a96d73bbd7af15cb1fc38c3f4a3bd82e9">F</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Public Member Functions

### createTileDPLoops() {#a5f7b74afe2d1d4f3cc3373cd8af2e6ad}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<div class="doxyMemberTemplate">template &lt;Intrinsic::ID IntrID&gt;</div>
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">std::enable_if_t&lt; IntrID==Intrinsic::x86_tdpbssd_internal||IntrID==Intrinsic::x86_tdpbsud_internal||IntrID==Intrinsic::x86_tdpbusd_internal||IntrID==Intrinsic::x86_tdpbuud_internal||IntrID==Intrinsic::x86_tdpbf16ps_internal, Value * &gt; anonymous{X86LowerAMXIntrinsics.cpp}::X86LowerAMXIntrinsics::createTileDPLoops (<a href="/web-llvm/docs/api/classes/llvm/basicblock">BasicBlock</a> * Start, <a href="/web-llvm/docs/api/classes/llvm/basicblock">BasicBlock</a> * End, <a href="/web-llvm/docs/api/classes/llvm/irbuilderbase">IRBuilderBase</a> &amp; B, <a href="/web-llvm/docs/api/classes/llvm/value">Value</a> * Row, <a href="/web-llvm/docs/api/classes/llvm/value">Value</a> * Col, <a href="/web-llvm/docs/api/classes/llvm/value">Value</a> * K, <a href="/web-llvm/docs/api/classes/llvm/value">Value</a> * Acc, <a href="/web-llvm/docs/api/classes/llvm/value">Value</a> * LHS, <a href="/web-llvm/docs/api/classes/llvm/value">Value</a> * RHS)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 239 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/x86/x86loweramxintrinsics-cpp">X86LowerAMXIntrinsics.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/classes/llvm/loopbase/#a990a86b0de7a84a9f489d2034878e330">llvm::LoopBase&lt; BlockT, LoopT &gt;::addChildLoop</a>, <a href="/web-llvm/docs/api/classes/llvm/phinode/#a089cccb6f231efee72abc76d0f9c695f">llvm::PHINode::addIncoming</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#ab9c6b351507d3c0730f4290919d43a12">llvm::ArrayRef</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/silowercontrolflow-cpp/#a4868c5d81c5ccc98c47aeab6244346a0">assert</a>, <a href="/web-llvm/docs/api/files/lib/lib/ir/builtingcs-cpp/#ae76959fe811ba090de4cba69ac00f1da">B</a>, <a href="/web-llvm/docs/api/classes/llvm/basicblock/#a0ed5f3ab3c2e4196ee0cffffa080c062">llvm::BasicBlock::begin</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#ac4fc845f5ed92de63cd4474f128f5fc5">llvm::cast</a>, <a href="/web-llvm/docs/api/classes/llvm/fixedvectortype/#af9a870d5df50fe0133a410b7c9114c80">llvm::FixedVectorType::get</a>, <a href="/web-llvm/docs/api/classes/llvm/constant/#aa6574d526b3e38a28f688a7bb4325c2c">llvm::Constant::getNullValue</a>, <a href="/web-llvm/docs/api/classes/llvm/basicblock/#a59fb91d1691350f7d1b8e8a114e3f2a4">llvm::BasicBlock::getSinglePredecessor</a>, <a href="/web-llvm/docs/api/classes/llvm/basicblock/#a79c007dcf9fff57e1569e778d7885b5e">llvm::BasicBlock::getSingleSuccessor</a>, <a href="/web-llvm/docs/api/classes/llvm/basicblock/#acf3c3aa4880eb60d00963ba93082c298">llvm::BasicBlock::getTerminator</a>, <a href="/web-llvm/docs/api/classes/llvm/value/#a0344a49526443edf90cc0aef3abd3337">llvm::Value::getType</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/x86/x86loweramxintrinsics-cpp/#ac5c08ee0c063916d061cf1d064a2e97f">isV256I32Ty</a> and <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/support/errorhandling-h/#ace243f5c25697a1107cce46626b3dc94">llvm_unreachable</a>.</p>

</div>
</div>

### createTileLoadStoreLoops() {#a991aa40e1236f6093ee0c3d93628319c}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<div class="doxyMemberTemplate">template &lt;bool IsTileLoad&gt;</div>
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">Value * anonymous{X86LowerAMXIntrinsics.cpp}::X86LowerAMXIntrinsics::createTileLoadStoreLoops (<a href="/web-llvm/docs/api/classes/llvm/basicblock">BasicBlock</a> * Start, <a href="/web-llvm/docs/api/classes/llvm/basicblock">BasicBlock</a> * End, <a href="/web-llvm/docs/api/classes/llvm/irbuilderbase">IRBuilderBase</a> &amp; B, <a href="/web-llvm/docs/api/classes/llvm/value">Value</a> * Row, <a href="/web-llvm/docs/api/classes/llvm/value">Value</a> * Col, <a href="/web-llvm/docs/api/classes/llvm/value">Value</a> * Ptr, <a href="/web-llvm/docs/api/classes/llvm/value">Value</a> * Stride, <a href="/web-llvm/docs/api/classes/llvm/value">Value</a> * Tile)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 146 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/x86/x86loweramxintrinsics-cpp">X86LowerAMXIntrinsics.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/classes/llvm/loopbase/#a990a86b0de7a84a9f489d2034878e330">llvm::LoopBase&lt; BlockT, LoopT &gt;::addChildLoop</a>, <a href="/web-llvm/docs/api/classes/llvm/phinode/#a089cccb6f231efee72abc76d0f9c695f">llvm::PHINode::addIncoming</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/silowercontrolflow-cpp/#a4868c5d81c5ccc98c47aeab6244346a0">assert</a>, <a href="/web-llvm/docs/api/files/lib/lib/ir/builtingcs-cpp/#ae76959fe811ba090de4cba69ac00f1da">B</a>, <a href="/web-llvm/docs/api/classes/llvm/basicblock/#a0ed5f3ab3c2e4196ee0cffffa080c062">llvm::BasicBlock::begin</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#ac4fc845f5ed92de63cd4474f128f5fc5">llvm::cast</a>, <a href="/web-llvm/docs/api/classes/llvm/fixedvectortype/#af9a870d5df50fe0133a410b7c9114c80">llvm::FixedVectorType::get</a>, <a href="/web-llvm/docs/api/classes/llvm/constant/#aa6574d526b3e38a28f688a7bb4325c2c">llvm::Constant::getNullValue</a>, <a href="/web-llvm/docs/api/classes/llvm/basicblock/#a59fb91d1691350f7d1b8e8a114e3f2a4">llvm::BasicBlock::getSinglePredecessor</a>, <a href="/web-llvm/docs/api/classes/llvm/basicblock/#a79c007dcf9fff57e1569e778d7885b5e">llvm::BasicBlock::getSingleSuccessor</a>, <a href="/web-llvm/docs/api/classes/llvm/basicblock/#acf3c3aa4880eb60d00963ba93082c298">llvm::BasicBlock::getTerminator</a>, <a href="/web-llvm/docs/api/classes/llvm/value/#a0344a49526443edf90cc0aef3abd3337">llvm::Value::getType</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/x86/x86loweramxintrinsics-cpp/#ac5c08ee0c063916d061cf1d064a2e97f">isV256I32Ty</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a05f5b9a11bdcc5feba62899f95dcf878a3134224cba2545bc57954d3b072aebb4">llvm::Offset</a> and <a href="/web-llvm/docs/api/files/lib/lib/analysis/targetlibraryinfo-cpp/#aca185e6d0e9f423dbb24440206454872a11dbf501abf829b3ab7049c2d3a8a053">Ptr</a>.</p>

</div>
</div>

### lowerTileDP() {#a79f47e97963f500c113eb9bfee2e5b47}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<div class="doxyMemberTemplate">template &lt;Intrinsic::ID IntrID&gt;</div>
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">std::enable_if_t&lt; IntrID==Intrinsic::x86_tdpbssd_internal||IntrID==Intrinsic::x86_tdpbsud_internal||IntrID==Intrinsic::x86_tdpbusd_internal||IntrID==Intrinsic::x86_tdpbuud_internal||IntrID==Intrinsic::x86_tdpbf16ps_internal, bool &gt; anonymous{X86LowerAMXIntrinsics.cpp}::X86LowerAMXIntrinsics::lowerTileDP (<a href="/web-llvm/docs/api/classes/llvm/instruction">Instruction</a> * TileDP)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 473 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/x86/x86loweramxintrinsics-cpp">X86LowerAMXIntrinsics.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/files/lib/lib/ir/builtingcs-cpp/#a2e38c85003a042421cde1647632d0b72">A</a>, <a href="/web-llvm/docs/api/files/lib/lib/ir/builtingcs-cpp/#ae76959fe811ba090de4cba69ac00f1da">B</a>, <a href="/web-llvm/docs/api/namespaces/llvm/callingconv/#ac6aa1387c4375260e2468eb5a77fdb4cafd841a49aec1539bc88abc8ff9e170fb">llvm::CallingConv::C</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#ac4fc845f5ed92de63cd4474f128f5fc5">llvm::cast</a>, <a href="/web-llvm/docs/api/classes/llvm/irbuilderbase/#a932f08e32ea37a7019902ee467beb268">llvm::IRBuilderBase::CreateBitCast</a>, <a href="/web-llvm/docs/api/classes/llvm/irbuilderbase/#a5849d19e500f8c6713ec44889058f424">llvm::IRBuilderBase::CreateLShr</a>, <a href="/web-llvm/docs/api/classes/llvm/instruction/#a601ee49a4c4e0babf29bd1cf09036570">llvm::Instruction::eraseFromParent</a>, <a href="/web-llvm/docs/api/classes/llvm/irbuilderbase/#aa2ed385be8984b4306762990278eb13d">llvm::IRBuilderBase::getContext</a>, <a href="/web-llvm/docs/api/classes/llvm/basicblock/#a362b5e6097732cbc0d2fb555a1f73400">llvm::BasicBlock::getFirstNonPHIIt</a>, <a href="/web-llvm/docs/api/classes/llvm/irbuilderbase/#ac33b7f085ea15691aa45a61ef207d603">llvm::IRBuilderBase::getInt16</a>, <a href="/web-llvm/docs/api/classes/llvm/ilist-detail/node-parent-access/#a7e19e7508415378ad9523e0339b23e22">llvm::ilist_detail::node_parent_access&lt; NodeTy, ParentTy &gt;::getParent</a>, <a href="/web-llvm/docs/api/classes/llvm/type/#a08ceb864464bce07aed4387d665f6565">llvm::Type::getX86_AMXTy</a>, <a href="/web-llvm/docs/api/files/lib/lib/support/md5-cpp/#ac0eafdc9ee161b71e7af98af736952fd">I</a>, <a href="/web-llvm/docs/api/namespaces/llvm/patternmatch/#a99d8e67ed2343ad6717d7a8fdd3e7c7a">llvm::PatternMatch::m_BitCast</a>, <a href="/web-llvm/docs/api/namespaces/llvm/patternmatch/#a3c0adc1054838f4498e0e860b637a22b">llvm::PatternMatch::m_Intrinsic</a>, <a href="/web-llvm/docs/api/namespaces/llvm/patternmatch/#aaf522908fe903018eb9b087dd6e49296">llvm::PatternMatch::m_Value</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a3d2cdc4a0db233678e7141c9d6ea3419">llvm::make_early_inc_range</a>, <a href="/web-llvm/docs/api/namespaces/llvm/patternmatch/#a25d956d9e0beadd47ce4bc255dfa811d">llvm::PatternMatch::match</a>, <a href="/web-llvm/docs/api/files/lib/lib/support/regcomp-c/#a0240ac851181b84ac374872dc5434ee4">N</a>, <a href="/web-llvm/docs/api/classes/llvm/value/#a3ab5fc45117b450e8bb04e564cb6e5f2">llvm::Value::replaceAllUsesWith</a>, <a href="/web-llvm/docs/api/classes/llvm/irbuilderbase/#ace45cae6925c65e9d6916e09dd5b17cc">llvm::IRBuilderBase::SetInsertPoint</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#ac6c9ffe7979754415f4ca0d677174bc2">llvm::SplitBlock</a> and <a href="/web-llvm/docs/api/classes/llvm/value/#abf855b7cd63a0cd7f73759e396f280c9">llvm::Value::uses</a>.</p>

</div>
</div>

### lowerTileLoadStore() {#aabc37fb487455e5268d389333bc5c890}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<div class="doxyMemberTemplate">template &lt;bool IsTileLoad&gt;</div>
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool anonymous{X86LowerAMXIntrinsics.cpp}::X86LowerAMXIntrinsics::lowerTileLoadStore (<a href="/web-llvm/docs/api/classes/llvm/instruction">Instruction</a> * TileLoadStore)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 511 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/x86/x86loweramxintrinsics-cpp">X86LowerAMXIntrinsics.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/namespaces/llvm/#ac4fc845f5ed92de63cd4474f128f5fc5">llvm::cast</a>, <a href="/web-llvm/docs/api/classes/llvm/irbuilderbase/#a932f08e32ea37a7019902ee467beb268">llvm::IRBuilderBase::CreateBitCast</a>, <a href="/web-llvm/docs/api/classes/llvm/irbuilderbase/#a5849d19e500f8c6713ec44889058f424">llvm::IRBuilderBase::CreateLShr</a>, <a href="/web-llvm/docs/api/classes/llvm/instruction/#a601ee49a4c4e0babf29bd1cf09036570">llvm::Instruction::eraseFromParent</a>, <a href="/web-llvm/docs/api/classes/llvm/irbuilderbase/#aa2ed385be8984b4306762990278eb13d">llvm::IRBuilderBase::getContext</a>, <a href="/web-llvm/docs/api/classes/llvm/basicblock/#a362b5e6097732cbc0d2fb555a1f73400">llvm::BasicBlock::getFirstNonPHIIt</a>, <a href="/web-llvm/docs/api/classes/llvm/irbuilderbase/#ac33b7f085ea15691aa45a61ef207d603">llvm::IRBuilderBase::getInt16</a>, <a href="/web-llvm/docs/api/classes/llvm/irbuilderbase/#a73f286a780fbb8c82c0a8574540719ea">llvm::IRBuilderBase::getInt64</a>, <a href="/web-llvm/docs/api/classes/llvm/ilist-detail/node-parent-access/#a7e19e7508415378ad9523e0339b23e22">llvm::ilist_detail::node_parent_access&lt; NodeTy, ParentTy &gt;::getParent</a>, <a href="/web-llvm/docs/api/classes/llvm/type/#a08ceb864464bce07aed4387d665f6565">llvm::Type::getX86_AMXTy</a>, <a href="/web-llvm/docs/api/files/lib/lib/support/md5-cpp/#ac0eafdc9ee161b71e7af98af736952fd">I</a>, <a href="/web-llvm/docs/api/namespaces/llvm/patternmatch/#a99d8e67ed2343ad6717d7a8fdd3e7c7a">llvm::PatternMatch::m_BitCast</a>, <a href="/web-llvm/docs/api/namespaces/llvm/patternmatch/#a3c0adc1054838f4498e0e860b637a22b">llvm::PatternMatch::m_Intrinsic</a>, <a href="/web-llvm/docs/api/namespaces/llvm/patternmatch/#aaf522908fe903018eb9b087dd6e49296">llvm::PatternMatch::m_Value</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a3d2cdc4a0db233678e7141c9d6ea3419">llvm::make_early_inc_range</a>, <a href="/web-llvm/docs/api/namespaces/llvm/patternmatch/#a25d956d9e0beadd47ce4bc255dfa811d">llvm::PatternMatch::match</a>, <a href="/web-llvm/docs/api/files/lib/lib/support/regcomp-c/#a0240ac851181b84ac374872dc5434ee4">N</a>, <a href="/web-llvm/docs/api/files/lib/lib/analysis/targetlibraryinfo-cpp/#aca185e6d0e9f423dbb24440206454872a11dbf501abf829b3ab7049c2d3a8a053">Ptr</a>, <a href="/web-llvm/docs/api/classes/llvm/value/#a3ab5fc45117b450e8bb04e564cb6e5f2">llvm::Value::replaceAllUsesWith</a>, <a href="/web-llvm/docs/api/classes/llvm/irbuilderbase/#ace45cae6925c65e9d6916e09dd5b17cc">llvm::IRBuilderBase::SetInsertPoint</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#ac6c9ffe7979754415f4ca0d677174bc2">llvm::SplitBlock</a> and <a href="/web-llvm/docs/api/classes/llvm/value/#abf855b7cd63a0cd7f73759e396f280c9">llvm::Value::uses</a>.</p>

</div>
</div>

### visit() {#afd8404fba4a01a50928ea2d51954afb7}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool X86LowerAMXIntrinsics::visit ()</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 65 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/x86/x86loweramxintrinsics-cpp">X86LowerAMXIntrinsics.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/namespaces/llvm/callingconv/#ac6aa1387c4375260e2468eb5a77fdb4cafd841a49aec1539bc88abc8ff9e170fb">llvm::CallingConv::C</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#ad6e19a09aeed4c56617c284e099c81de">llvm::depth_first</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a22eeee01734061ac1b31ccd994c49eef">llvm::dyn_cast</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/nvptx/nvvmintrrange-cpp/#ac5804672fc0850438d63caec770647f8">II</a>, <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/support/errorhandling-h/#ace243f5c25697a1107cce46626b3dc94">llvm_unreachable</a> and <a href="/web-llvm/docs/api/classes/llvm/smallvectortemplatebase/#af42bfbc067df27c19ee2fc859df58799">llvm::SmallVectorTemplateBase&lt; T, bool &gt;::push_back</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/classes/anonymous-x86loweramxintrinsics-cpp-/x86loweramxintrinsicslegacypass/#a3676b694f0f141994877ccf4564027ef">anonymous{X86LowerAMXIntrinsics.cpp}::X86LowerAMXIntrinsicsLegacyPass::runOnFunction</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Private Member Functions

### createLoop() {#afbbbb5228107fd52d04b975fd15e1fb9}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">BasicBlock * X86LowerAMXIntrinsics::createLoop (<a href="/web-llvm/docs/api/classes/llvm/basicblock">BasicBlock</a> * Preheader, <a href="/web-llvm/docs/api/classes/llvm/basicblock">BasicBlock</a> * Exit, <a href="/web-llvm/docs/api/classes/llvm/value">Value</a> * Bound, <a href="/web-llvm/docs/api/classes/llvm/value">Value</a> * Step, <a href="/web-llvm/docs/api/classes/llvm/stringref">StringRef</a> Name, <a href="/web-llvm/docs/api/classes/llvm/irbuilderbase">IRBuilderBase</a> &amp; B, <a href="/web-llvm/docs/api/classes/llvm/loop">Loop</a> * L)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 70 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/x86/x86loweramxintrinsics-cpp">X86LowerAMXIntrinsics.cpp</a>.</p>

</div>
</div>

### createTileDPLoops() {#a5f7b74afe2d1d4f3cc3373cd8af2e6ad}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<div class="doxyMemberTemplate">template &lt;Intrinsic::ID IntrID&gt;</div>
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">std::enable_if_t&lt; IntrID==Intrinsic::x86_tdpbssd_internal||IntrID==Intrinsic::x86_tdpbsud_internal||IntrID==Intrinsic::x86_tdpbusd_internal||IntrID==Intrinsic::x86_tdpbuud_internal||IntrID==Intrinsic::x86_tdpbf16ps_internal, Value * &gt; anonymous{X86LowerAMXIntrinsics.cpp}::X86LowerAMXIntrinsics::createTileDPLoops (<a href="/web-llvm/docs/api/classes/llvm/basicblock">BasicBlock</a> * Start, <a href="/web-llvm/docs/api/classes/llvm/basicblock">BasicBlock</a> * End, <a href="/web-llvm/docs/api/classes/llvm/irbuilderbase">IRBuilderBase</a> &amp; B, <a href="/web-llvm/docs/api/classes/llvm/value">Value</a> * Row, <a href="/web-llvm/docs/api/classes/llvm/value">Value</a> * Col, <a href="/web-llvm/docs/api/classes/llvm/value">Value</a> * K, <a href="/web-llvm/docs/api/classes/llvm/value">Value</a> * Acc, <a href="/web-llvm/docs/api/classes/llvm/value">Value</a> * LHS, <a href="/web-llvm/docs/api/classes/llvm/value">Value</a> * RHS)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 84 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/x86/x86loweramxintrinsics-cpp">X86LowerAMXIntrinsics.cpp</a>.</p>

</div>
</div>

### createTileLoadStoreLoops() {#a991aa40e1236f6093ee0c3d93628319c}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<div class="doxyMemberTemplate">template &lt;bool IsTileLoad&gt;</div>
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">Value * anonymous{X86LowerAMXIntrinsics.cpp}::X86LowerAMXIntrinsics::createTileLoadStoreLoops (<a href="/web-llvm/docs/api/classes/llvm/basicblock">BasicBlock</a> * Start, <a href="/web-llvm/docs/api/classes/llvm/basicblock">BasicBlock</a> * End, <a href="/web-llvm/docs/api/classes/llvm/irbuilderbase">IRBuilderBase</a> &amp; B, <a href="/web-llvm/docs/api/classes/llvm/value">Value</a> * Row, <a href="/web-llvm/docs/api/classes/llvm/value">Value</a> * Col, <a href="/web-llvm/docs/api/classes/llvm/value">Value</a> * Ptr, <a href="/web-llvm/docs/api/classes/llvm/value">Value</a> * Stride, <a href="/web-llvm/docs/api/classes/llvm/value">Value</a> * Tile)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 74 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/x86/x86loweramxintrinsics-cpp">X86LowerAMXIntrinsics.cpp</a>.</p>

</div>
</div>

### lowerTileDP() {#a79f47e97963f500c113eb9bfee2e5b47}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<div class="doxyMemberTemplate">template &lt;Intrinsic::ID IntrID&gt;</div>
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">std::enable_if_t&lt; IntrID==Intrinsic::x86_tdpbssd_internal||IntrID==Intrinsic::x86_tdpbsud_internal||IntrID==Intrinsic::x86_tdpbusd_internal||IntrID==Intrinsic::x86_tdpbuud_internal||IntrID==Intrinsic::x86_tdpbf16ps_internal, bool &gt; anonymous{X86LowerAMXIntrinsics.cpp}::X86LowerAMXIntrinsics::lowerTileDP (<a href="/web-llvm/docs/api/classes/llvm/instruction">Instruction</a> * TileDP)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 96 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/x86/x86loweramxintrinsics-cpp">X86LowerAMXIntrinsics.cpp</a>.</p>

</div>
</div>

### lowerTileLoadStore() {#aabc37fb487455e5268d389333bc5c890}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<div class="doxyMemberTemplate">template &lt;bool IsTileLoad&gt;</div>
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool anonymous{X86LowerAMXIntrinsics.cpp}::X86LowerAMXIntrinsics::lowerTileLoadStore (<a href="/web-llvm/docs/api/classes/llvm/instruction">Instruction</a> * TileLoadStore)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 88 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/x86/x86loweramxintrinsics-cpp">X86LowerAMXIntrinsics.cpp</a>.</p>

</div>
</div>

### lowerTileZero() {#ae5c84017c7546f3d878b7b195e0a476d}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool X86LowerAMXIntrinsics::lowerTileZero (<a href="/web-llvm/docs/api/classes/llvm/instruction">Instruction</a> * TileZero)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 97 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/x86/x86loweramxintrinsics-cpp">X86LowerAMXIntrinsics.cpp</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Private Member Attributes

### DTU {#ae40977978a58148b8827ca2380f94666}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">DomTreeUpdater&amp; anonymous{X86LowerAMXIntrinsics.cpp}::X86LowerAMXIntrinsics::DTU</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 68 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/x86/x86loweramxintrinsics-cpp">X86LowerAMXIntrinsics.cpp</a>.</p>

</div>
</div>

### Func {#a7bb626df8440038b0ea43cf68d9ebd18}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">Function&amp; anonymous{X86LowerAMXIntrinsics.cpp}::X86LowerAMXIntrinsics::Func</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 60 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/x86/x86loweramxintrinsics-cpp">X86LowerAMXIntrinsics.cpp</a>.</p>

</div>
</div>

### LI {#a3f4244257c72a5745da3d256808201a7}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">LoopInfo* anonymous{X86LowerAMXIntrinsics.cpp}::X86LowerAMXIntrinsics::LI</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 69 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/x86/x86loweramxintrinsics-cpp">X86LowerAMXIntrinsics.cpp</a>.</p>

</div>
</div>

</div>

<hr/>

The documentation for this class was generated from the following file:

<ul>
<li><a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/x86/x86loweramxintrinsics-cpp">X86LowerAMXIntrinsics.cpp</a></li>
</ul>

<hr/>

<p class="doxyGeneratedBy">Generated via <a href="https://github.com/xpack/doxygen2docusaurus">doxygen2docusaurus</a> by <a href="https://www.doxygen.nl">Doxygen</a> 1.15.0.</p>

</div>
