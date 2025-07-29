---

# DO NOT EDIT!
# Automatically generated via doxygen2docusaurus by Doxygen.

slug: /api/classes/llvm/memcpyoptpass
custom_edit_url: null
toc_max_heading_level: 4
keywords:
  - doxygen
  - reference
  - class

---

<div class="doxyPage">

# `MemCpyOptPass` Class



## Declaration

<div class="doxyDeclaration">
class llvm::MemCpyOptPass { ... }
</div>

## Included Headers

<div class="doxyIncludesList">#include "<a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/transforms/include/llvm/transforms/scalar/memcpyoptimizer-h">llvm/Transforms/Scalar/MemCpyOptimizer.h</a>"
</div>

## Base class

<table class="doxyMembersIndex">

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">struct</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="/web-llvm/docs/api/structs/llvm/passinfomixin">PassInfoMixin&lt;DerivedT&gt;</a></td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>A CRTP mix-in to automatically provide informational APIs needed for passes. <a href="/web-llvm/docs/api/structs/llvm/passinfomixin/#details">More...</a></p>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a637b931c7ffc01cd1a9bef1ce9ec2c89">MemCpyOptPass</a> ()=default</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">PreservedAnalyses</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a07c3f5129a977e2f949212878c3042ae">run</a> (Function &amp;F, FunctionAnalysisManager &amp;AM)</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a18e40505cff07b625ae84a227804a9f4">runImpl</a> (Function &amp;F, TargetLibraryInfo *TLI, AAResults *AA, AssumptionCache *AC, DominatorTree *DT, PostDominatorTree *PDT, MemorySSA *MSSA)</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">bool</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a28a5bc7abd6f755d21e910f6449e3303">processStore</a> (StoreInst *SI, BasicBlock::iterator &amp;BBI)</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a9c8c1bbdef677429e07a9aa7424dc72c">processStoreOfLoad</a> (StoreInst *SI, LoadInst *LI, const DataLayout &amp;DL, BasicBlock::iterator &amp;BBI)</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a4a1a54da3fd032393e36cd134d0c004d">processMemSet</a> (MemSetInst *SI, BasicBlock::iterator &amp;BBI)</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a57f66b9650506719d68c7ac48e493419">processMemCpy</a> (MemCpyInst *M, BasicBlock::iterator &amp;BBI)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Perform simplification of memcpy's. <a href="#a57f66b9650506719d68c7ac48e493419">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">bool</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a4c784aa7cdee016822ff12c6a7c7b8cd">processMemMove</a> (MemMoveInst *M, BasicBlock::iterator &amp;BBI)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Transforms memmove calls to memcpy calls when the src/dst are guaranteed not to alias. <a href="#a4c784aa7cdee016822ff12c6a7c7b8cd">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">bool</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a0911b8f99c4833c2760e5e0f2672a2d7">performCallSlotOptzn</a> (Instruction *cpyLoad, Instruction *cpyStore, Value *cpyDst, Value *cpySrc, TypeSize cpyLen, Align cpyAlign, BatchAAResults &amp;BAA, std::function&lt; CallInst *()&gt; GetC)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Takes a memcpy and a call that it depends on, and checks for the possibility of a call slot optimization by having the call write its result directly into the destination of the memcpy. <a href="#a0911b8f99c4833c2760e5e0f2672a2d7">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">bool</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#aacd1e7e2aadfe46851e9e3de0ba871dc">processMemCpyMemCpyDependence</a> (MemCpyInst *M, MemCpyInst *MDep, BatchAAResults &amp;BAA)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>We've found that the (upward scanning) memory dependence of memcpy 'M' is the memcpy 'MDep'. <a href="#aacd1e7e2aadfe46851e9e3de0ba871dc">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">bool</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a73be05c583396ef6fd0be3ecf2f2d089">processMemSetMemCpyDependence</a> (MemCpyInst *MemCpy, MemSetInst *MemSet, BatchAAResults &amp;BAA)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>We've found that the (upward scanning) memory dependence of <span class="doxyComputerOutput">MemCpy</span> is <span class="doxyComputerOutput">MemSet</span>. <a href="#a73be05c583396ef6fd0be3ecf2f2d089">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">bool</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a6a42125d8ee5f5911ce95909b19c4b72">performMemCpyToMemSetOptzn</a> (MemCpyInst *MemCpy, MemSetInst *MemSet, BatchAAResults &amp;BAA)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Transform memcpy to memset when its source was just memset. <a href="#a6a42125d8ee5f5911ce95909b19c4b72">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">bool</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#acbc80c28a43766809fe19793606d91f9">processByValArgument</a> (CallBase &amp;CB, unsigned ArgNo)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>This is called on every byval argument in call sites. <a href="#acbc80c28a43766809fe19793606d91f9">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">bool</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#aebf01621ed83283f192fd201010415d1">processImmutArgument</a> (CallBase &amp;CB, unsigned ArgNo)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>This is called on memcpy dest pointer arguments attributed as immutable during call. <a href="#aebf01621ed83283f192fd201010415d1">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/instruction">Instruction</a> *</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ae6144d8d036202f4e6c4034c7f3d7fb3">tryMergingIntoMemset</a> (Instruction *I, Value *StartPtr, Value *ByteVal)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>When scanning forward over instructions, we look for some other patterns to fold away. <a href="#ae6144d8d036202f4e6c4034c7f3d7fb3">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">bool</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a6857fd7ecf20f3bb86be775c48ff8be0">moveUp</a> (StoreInst *SI, Instruction *P, const LoadInst *LI)</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ab19c55b9b71afdd4b0f773d9496bcb9c">performStackMoveOptzn</a> (Instruction *Load, Instruction *Store, AllocaInst *DestAlloca, AllocaInst *SrcAlloca, TypeSize Size, BatchAAResults &amp;BAA)</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a5fb52c0478bfa2334039fa14c51d6707">isMemMoveMemSetDependency</a> (MemMoveInst *M)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Memmove calls with overlapping src/dest buffers that come after a memset may be removed. <a href="#a5fb52c0478bfa2334039fa14c51d6707">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">void</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a478ed71b0d9199ee72f385b6001f5f6b">eraseInstruction</a> (Instruction *I)</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a5663ca56c2796cdc34d00d82949d1e27">iterateOnFunction</a> (Function &amp;F)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Executes one iteration of <a href="/web-llvm/docs/api/classes/llvm/memcpyoptpass">MemCpyOptPass</a>. <a href="#a5663ca56c2796cdc34d00d82949d1e27">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

</table>

## Private Member Attributes Index

<table class="doxyMembersIndex">

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/targetlibraryinfo">TargetLibraryInfo</a> *</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#aa33bf6884a533653a7fec69f0725ec57">TLI</a> = nullptr</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/aaresults">AAResults</a> *</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a1942f604436459d0d79e5f094f0f3167">AA</a> = nullptr</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#af86c77bf27ff17616328af5abac0766c">AC</a> = nullptr</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ac237bb61ccfc540e7fecb97a19503c5c">DT</a> = nullptr</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/postdominatortree">PostDominatorTree</a> *</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a97b580492ad3a29e86d853e4632ed3c8">PDT</a> = nullptr</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/memoryssa">MemorySSA</a> *</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#af6217dcdf9861c3d22b7728d98ca63e4">MSSA</a> = nullptr</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/memoryssaupdater">MemorySSAUpdater</a> *</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#acbc62c464977178f914b1e8088a80724">MSSAU</a> = nullptr</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/earliestescapeanalysis">EarliestEscapeAnalysis</a> *</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a9e22dabe946d2420130bbf0c5a2ce42a">EEA</a> = nullptr</td>
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


<p>Definition at line 44 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/transforms/include/llvm/transforms/scalar/memcpyoptimizer-h">MemCpyOptimizer.h</a>.</p>


<div class="doxySectionDef">

## Public Constructors

### MemCpyOptPass() {#a637b931c7ffc01cd1a9bef1ce9ec2c89}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">llvm::MemCpyOptPass::MemCpyOptPass ()</td>
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



<p>Definition at line 55 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/transforms/include/llvm/transforms/scalar/memcpyoptimizer-h">MemCpyOptimizer.h</a>.</p>


<p>References <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/arm/armslshardening-cpp/#ad467c4ab9119043f9b7750ab986be61a">DL</a>, <a href="/web-llvm/docs/api/files/lib/lib/support/md5-cpp/#a96d73bbd7af15cb1fc38c3f4a3bd82e9">F</a>, <a href="/web-llvm/docs/api/files/lib/lib/support/md5-cpp/#ac0eafdc9ee161b71e7af98af736952fd">I</a>, <a href="/web-llvm/docs/api/files/lib/lib/option/option-cpp/#a04665169063c8ca1f2ea96c27fc7c2b2">P</a> and <a href="/web-llvm/docs/api/files/lib/lib/analysis/inlineorder-cpp/#a7ee6f0cb51c3b9056199e9a0001fe8c3a6f6cb72d544962fa333e2e34ce64f719">Size</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Public Member Functions

### run() {#a07c3f5129a977e2f949212878c3042ae}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">PreservedAnalyses MemCpyOptPass::run (<a href="/web-llvm/docs/api/classes/llvm/function">Function</a> &amp; F, <a href="/web-llvm/docs/api/namespaces/llvm/#adce09a5a0de0e3177eb00e932734af2f">FunctionAnalysisManager</a> &amp; AM)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Declaration at line 57 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/transforms/include/llvm/transforms/scalar/memcpyoptimizer-h">MemCpyOptimizer.h</a>, definition at line 2153 of file <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/scalar/memcpyoptimizer-cpp">MemCpyOptimizer.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/files/lib/lib/support/md5-cpp/#a96d73bbd7af15cb1fc38c3f4a3bd82e9">F</a>, <a href="/web-llvm/docs/api/classes/llvm/analysismanager/#aaab1fad63e4f3b8679469720a873fedd">llvm::AnalysisManager&lt; IRUnitT, ExtraArgTs &gt;::getResult</a> and <a href="#a18e40505cff07b625ae84a227804a9f4">runImpl</a>.</p>

</div>
</div>

### runImpl() {#a18e40505cff07b625ae84a227804a9f4}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool MemCpyOptPass::runImpl (<a href="/web-llvm/docs/api/classes/llvm/function">Function</a> &amp; F, <a href="/web-llvm/docs/api/classes/llvm/targetlibraryinfo">TargetLibraryInfo</a> * TLI, <a href="/web-llvm/docs/api/classes/llvm/aaresults">AAResults</a> * AA, <a href="/web-llvm/docs/api/classes/llvm/assumptioncache">AssumptionCache</a> * AC, <a href="/web-llvm/docs/api/classes/llvm/dominatortree">DominatorTree</a> * DT, <a href="/web-llvm/docs/api/classes/llvm/postdominatortree">PostDominatorTree</a> * PDT, <a href="/web-llvm/docs/api/classes/llvm/memoryssa">MemorySSA</a> * MSSA)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Declaration at line 60 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/transforms/include/llvm/transforms/scalar/memcpyoptimizer-h">MemCpyOptimizer.h</a>, definition at line 2171 of file <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/scalar/memcpyoptimizer-cpp">MemCpyOptimizer.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/files/lib/lib/support/md5-cpp/#a96d73bbd7af15cb1fc38c3f4a3bd82e9">F</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#aa29fe161c408879ada30c90ebbf55dcf">llvm::VerifyMemorySSA</a> and <a href="/web-llvm/docs/api/classes/llvm/memoryssa/#a88b10d37f671e58cf138ac84a8257c17">llvm::MemorySSA::verifyMemorySSA</a>.</p>


<p>Referenced by <a href="#a07c3f5129a977e2f949212878c3042ae">run</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Private Member Functions

### eraseInstruction() {#a478ed71b0d9199ee72f385b6001f5f6b}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void MemCpyOptPass::eraseInstruction (<a href="/web-llvm/docs/api/classes/llvm/instruction">Instruction</a> * I)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Declaration at line 92 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/transforms/include/llvm/transforms/scalar/memcpyoptimizer-h">MemCpyOptimizer.h</a>, definition at line 285 of file <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/scalar/memcpyoptimizer-cpp">MemCpyOptimizer.cpp</a>.</p>

</div>
</div>

### isMemMoveMemSetDependency() {#a5fb52c0478bfa2334039fa14c51d6707}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool MemCpyOptPass::isMemMoveMemSetDependency (<a href="/web-llvm/docs/api/classes/llvm/memmoveinst">MemMoveInst</a> * M)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Memmove calls with overlapping src/dest buffers that come after a memset may be removed.</p>

<p>Declaration at line 90 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/transforms/include/llvm/transforms/scalar/memcpyoptimizer-h">MemCpyOptimizer.h</a>, definition at line 1847 of file <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/scalar/memcpyoptimizer-cpp">MemCpyOptimizer.cpp</a>.</p>

</div>
</div>

### iterateOnFunction() {#a5663ca56c2796cdc34d00d82949d1e27}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool MemCpyOptPass::iterateOnFunction (<a href="/web-llvm/docs/api/classes/llvm/function">Function</a> &amp; F)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Executes one iteration of <a href="/web-llvm/docs/api/classes/llvm/memcpyoptpass">MemCpyOptPass</a>.</p>

<p>Declaration at line 93 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/transforms/include/llvm/transforms/scalar/memcpyoptimizer-h">MemCpyOptimizer.h</a>, definition at line 2106 of file <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/scalar/memcpyoptimizer-cpp">MemCpyOptimizer.cpp</a>.</p>

</div>
</div>

### moveUp() {#a6857fd7ecf20f3bb86be775c48ff8be0}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool MemCpyOptPass::moveUp (<a href="/web-llvm/docs/api/classes/llvm/storeinst">StoreInst</a> * SI, <a href="/web-llvm/docs/api/classes/llvm/instruction">Instruction</a> * P, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/loadinst">LoadInst</a> * LI)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Declaration at line 86 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/transforms/include/llvm/transforms/scalar/memcpyoptimizer-h">MemCpyOptimizer.h</a>, definition at line 501 of file <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/scalar/memcpyoptimizer-cpp">MemCpyOptimizer.cpp</a>.</p>

</div>
</div>

### performCallSlotOptzn() {#a0911b8f99c4833c2760e5e0f2672a2d7}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool MemCpyOptPass::performCallSlotOptzn (<a href="/web-llvm/docs/api/classes/llvm/instruction">Instruction</a> * cpyLoad, <a href="/web-llvm/docs/api/classes/llvm/instruction">Instruction</a> * cpyStore, <a href="/web-llvm/docs/api/classes/llvm/value">Value</a> * cpyDst, <a href="/web-llvm/docs/api/classes/llvm/value">Value</a> * cpySrc, <a href="/web-llvm/docs/api/classes/llvm/typesize">TypeSize</a> cpyLen, <a href="/web-llvm/docs/api/structs/llvm/align">Align</a> cpyAlign, <a href="/web-llvm/docs/api/classes/llvm/batchaaresults">BatchAAResults</a> &amp; BAA, std::function&lt; <a href="/web-llvm/docs/api/classes/llvm/callinst">CallInst</a> *()&gt; GetC)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Takes a memcpy and a call that it depends on, and checks for the possibility of a call slot optimization by having the call write its result directly into the destination of the memcpy.</p>

<p>Declaration at line 72 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/transforms/include/llvm/transforms/scalar/memcpyoptimizer-h">MemCpyOptimizer.h</a>, definition at line 839 of file <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/scalar/memcpyoptimizer-cpp">MemCpyOptimizer.cpp</a>.</p>

</div>
</div>

### performMemCpyToMemSetOptzn() {#a6a42125d8ee5f5911ce95909b19c4b72}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool MemCpyOptPass::performMemCpyToMemSetOptzn (<a href="/web-llvm/docs/api/classes/llvm/memcpyinst">MemCpyInst</a> * MemCpy, <a href="/web-llvm/docs/api/classes/llvm/memsetinst">MemSetInst</a> * MemSet, <a href="/web-llvm/docs/api/classes/llvm/batchaaresults">BatchAAResults</a> &amp; BAA)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Transform memcpy to memset when its source was just memset.</p>


<p>In other words, turn:</p>


<div class="doxyProgramListing">

<div class="doxyCodeLine"><span class="doxyNoLineNumber">&nbsp;</span><span class="doxyLineContent"><span class="doxyHighlight">memset(dst1, c, dst1_size);</span></span></div>
<div class="doxyCodeLine"><span class="doxyNoLineNumber">&nbsp;</span><span class="doxyLineContent"><span class="doxyHighlight">memcpy(dst2, dst1, dst2_size);</span></span></div>

</div>


<p>into:</p>


<div class="doxyProgramListing">

<div class="doxyCodeLine"><span class="doxyNoLineNumber">&nbsp;</span><span class="doxyLineContent"><span class="doxyHighlight">memset(dst1, c, dst1_size);</span></span></div>
<div class="doxyCodeLine"><span class="doxyNoLineNumber">&nbsp;</span><span class="doxyLineContent"><span class="doxyHighlight">memset(dst2, c, dst2_size);</span></span></div>

</div>


<p>When dst2_size &lt;= dst1_size.</p>


<p>Declaration at line 80 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/transforms/include/llvm/transforms/scalar/memcpyoptimizer-h">MemCpyOptimizer.h</a>, definition at line 1419 of file <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/scalar/memcpyoptimizer-cpp">MemCpyOptimizer.cpp</a>.</p>

</div>
</div>

### performStackMoveOptzn() {#ab19c55b9b71afdd4b0f773d9496bcb9c}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool MemCpyOptPass::performStackMoveOptzn (<a href="/web-llvm/docs/api/classes/llvm/instruction">Instruction</a> * Load, <a href="/web-llvm/docs/api/classes/llvm/instruction">Instruction</a> * Store, <a href="/web-llvm/docs/api/classes/llvm/allocainst">AllocaInst</a> * DestAlloca, <a href="/web-llvm/docs/api/classes/llvm/allocainst">AllocaInst</a> * SrcAlloca, <a href="/web-llvm/docs/api/classes/llvm/typesize">TypeSize</a> Size, <a href="/web-llvm/docs/api/classes/llvm/batchaaresults">BatchAAResults</a> &amp; BAA)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Declaration at line 87 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/transforms/include/llvm/transforms/scalar/memcpyoptimizer-h">MemCpyOptimizer.h</a>, definition at line 1486 of file <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/scalar/memcpyoptimizer-cpp">MemCpyOptimizer.cpp</a>.</p>

</div>
</div>

### processByValArgument() {#acbc80c28a43766809fe19793606d91f9}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool MemCpyOptPass::processByValArgument (<a href="/web-llvm/docs/api/classes/llvm/callbase">CallBase</a> &amp; CB, unsigned ArgNo)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>This is called on every byval argument in call sites.</p>

<p>Declaration at line 82 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/transforms/include/llvm/transforms/scalar/memcpyoptimizer-h">MemCpyOptimizer.h</a>, definition at line 1932 of file <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/scalar/memcpyoptimizer-cpp">MemCpyOptimizer.cpp</a>.</p>

</div>
</div>

### processImmutArgument() {#aebf01621ed83283f192fd201010415d1}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool MemCpyOptPass::processImmutArgument (<a href="/web-llvm/docs/api/classes/llvm/callbase">CallBase</a> &amp; CB, unsigned ArgNo)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>This is called on memcpy dest pointer arguments attributed as immutable during call.</p>


<p>Try to use memcpy source directly if all of the following conditions are satisfied.</p>


<ol class="doxyList" type="1">
<li>The memcpy dst is neither modified during the call nor captured by the call.</li>
<li>The memcpy dst is an alloca with known alignment &amp; size. 2-1. The memcpy length == the alloca size which ensures that the new pointer is dereferenceable for the required range 2-2. The src pointer has alignment &gt;= the alloca alignment or can be enforced so.</li>
<li>The memcpy dst and src is not modified between the memcpy and the call. (if MSSA clobber check is safe.)</li>
<li>The memcpy src is not modified during the call. (ModRef check shows no Mod.)</li>
</ol>

<p>Declaration at line 83 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/transforms/include/llvm/transforms/scalar/memcpyoptimizer-h">MemCpyOptimizer.h</a>, definition at line 2015 of file <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/scalar/memcpyoptimizer-cpp">MemCpyOptimizer.cpp</a>.</p>

</div>
</div>

### processMemCpy() {#a57f66b9650506719d68c7ac48e493419}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool MemCpyOptPass::processMemCpy (<a href="/web-llvm/docs/api/classes/llvm/memcpyinst">MemCpyInst</a> * M, <a href="/web-llvm/docs/api/classes/llvm/basicblock/#a98c0a84a5dfa8bce341c829709f171e5">BasicBlock::iterator</a> &amp; BBI)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Perform simplification of memcpy's.</p>


<p>If we have memcpy A which copies X to Y, and memcpy B which copies Y to Z, then we can rewrite B to be a memcpy from X to Z (or potentially a memmove, depending on circumstances). This allows later passes to remove the first memcpy altogether.</p>


<p>Declaration at line 70 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/transforms/include/llvm/transforms/scalar/memcpyoptimizer-h">MemCpyOptimizer.h</a>, definition at line 1713 of file <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/scalar/memcpyoptimizer-cpp">MemCpyOptimizer.cpp</a>.</p>

</div>
</div>

### processMemCpyMemCpyDependence() {#aacd1e7e2aadfe46851e9e3de0ba871dc}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool MemCpyOptPass::processMemCpyMemCpyDependence (<a href="/web-llvm/docs/api/classes/llvm/memcpyinst">MemCpyInst</a> * M, <a href="/web-llvm/docs/api/classes/llvm/memcpyinst">MemCpyInst</a> * MDep, <a href="/web-llvm/docs/api/classes/llvm/batchaaresults">BatchAAResults</a> &amp; BAA)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>We've found that the (upward scanning) memory dependence of memcpy 'M' is the memcpy 'MDep'.</p>


<p>Try to simplify M to copy from MDep's input if we can.</p>


<p>Declaration at line 76 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/transforms/include/llvm/transforms/scalar/memcpyoptimizer-h">MemCpyOptimizer.h</a>, definition at line 1106 of file <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/scalar/memcpyoptimizer-cpp">MemCpyOptimizer.cpp</a>.</p>

</div>
</div>

### processMemMove() {#a4c784aa7cdee016822ff12c6a7c7b8cd}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool MemCpyOptPass::processMemMove (<a href="/web-llvm/docs/api/classes/llvm/memmoveinst">MemMoveInst</a> * M, <a href="/web-llvm/docs/api/classes/llvm/basicblock/#a98c0a84a5dfa8bce341c829709f171e5">BasicBlock::iterator</a> &amp; BBI)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Transforms memmove calls to memcpy calls when the src/dst are guaranteed not to alias.</p>

<p>Declaration at line 71 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/transforms/include/llvm/transforms/scalar/memcpyoptimizer-h">MemCpyOptimizer.h</a>, definition at line 1900 of file <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/scalar/memcpyoptimizer-cpp">MemCpyOptimizer.cpp</a>.</p>

</div>
</div>

### processMemSet() {#a4a1a54da3fd032393e36cd134d0c004d}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool MemCpyOptPass::processMemSet (<a href="/web-llvm/docs/api/classes/llvm/memsetinst">MemSetInst</a> * SI, <a href="/web-llvm/docs/api/classes/llvm/basicblock/#a98c0a84a5dfa8bce341c829709f171e5">BasicBlock::iterator</a> &amp; BBI)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Declaration at line 69 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/transforms/include/llvm/transforms/scalar/memcpyoptimizer-h">MemCpyOptimizer.h</a>, definition at line 824 of file <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/scalar/memcpyoptimizer-cpp">MemCpyOptimizer.cpp</a>.</p>

</div>
</div>

### processMemSetMemCpyDependence() {#a73be05c583396ef6fd0be3ecf2f2d089}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool MemCpyOptPass::processMemSetMemCpyDependence (<a href="/web-llvm/docs/api/classes/llvm/memcpyinst">MemCpyInst</a> * MemCpy, <a href="/web-llvm/docs/api/classes/llvm/memsetinst">MemSetInst</a> * MemSet, <a href="/web-llvm/docs/api/classes/llvm/batchaaresults">BatchAAResults</a> &amp; BAA)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>We've found that the (upward scanning) memory dependence of <span class="doxyComputerOutput">MemCpy</span> is <span class="doxyComputerOutput">MemSet</span>.</p>


<p>Try to simplify <span class="doxyComputerOutput">MemSet</span> to only set the trailing bytes that weren't copied over by <span class="doxyComputerOutput">MemCpy</span>.</p>


<p>In other words, transform:</p>


<div class="doxyProgramListing">

<div class="doxyCodeLine"><span class="doxyNoLineNumber">&nbsp;</span><span class="doxyLineContent"><span class="doxyHighlight">memset(dst, c, dst_size);</span></span></div>
<div class="doxyCodeLine"><span class="doxyNoLineNumber">&nbsp;</span><span class="doxyLineContent"><span class="doxyHighlight">...</span></span></div>
<div class="doxyCodeLine"><span class="doxyNoLineNumber">&nbsp;</span><span class="doxyLineContent"><span class="doxyHighlight">memcpy(dst, src, src_size);</span></span></div>

</div>


<p>into:</p>


<div class="doxyProgramListing">

<div class="doxyCodeLine"><span class="doxyNoLineNumber">&nbsp;</span><span class="doxyLineContent"><span class="doxyHighlight">...</span></span></div>
<div class="doxyCodeLine"><span class="doxyNoLineNumber">&nbsp;</span><span class="doxyLineContent"><span class="doxyHighlight">memset(dst + src_size, c, dst_size &lt;= src_size ? 0 : dst_size - src_size);</span></span></div>
<div class="doxyCodeLine"><span class="doxyNoLineNumber">&nbsp;</span><span class="doxyLineContent"><span class="doxyHighlight">memcpy(dst, src, src_size);</span></span></div>

</div>


<p>The memset is sunk to just before the memcpy to ensure that src_size is present when emitting the simplified memset.</p>


<p>Declaration at line 78 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/transforms/include/llvm/transforms/scalar/memcpyoptimizer-h">MemCpyOptimizer.h</a>, definition at line 1277 of file <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/scalar/memcpyoptimizer-cpp">MemCpyOptimizer.cpp</a>.</p>

</div>
</div>

### processStore() {#a28a5bc7abd6f755d21e910f6449e3303}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool MemCpyOptPass::processStore (<a href="/web-llvm/docs/api/classes/llvm/storeinst">StoreInst</a> * SI, <a href="/web-llvm/docs/api/classes/llvm/basicblock/#a98c0a84a5dfa8bce341c829709f171e5">BasicBlock::iterator</a> &amp; BBI)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Declaration at line 66 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/transforms/include/llvm/transforms/scalar/memcpyoptimizer-h">MemCpyOptimizer.h</a>, definition at line 742 of file <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/scalar/memcpyoptimizer-cpp">MemCpyOptimizer.cpp</a>.</p>

</div>
</div>

### processStoreOfLoad() {#a9c8c1bbdef677429e07a9aa7424dc72c}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool MemCpyOptPass::processStoreOfLoad (<a href="/web-llvm/docs/api/classes/llvm/storeinst">StoreInst</a> * SI, <a href="/web-llvm/docs/api/classes/llvm/loadinst">LoadInst</a> * LI, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/datalayout">DataLayout</a> &amp; DL, <a href="/web-llvm/docs/api/classes/llvm/basicblock/#a98c0a84a5dfa8bce341c829709f171e5">BasicBlock::iterator</a> &amp; BBI)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Declaration at line 67 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/transforms/include/llvm/transforms/scalar/memcpyoptimizer-h">MemCpyOptimizer.h</a>, definition at line 625 of file <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/scalar/memcpyoptimizer-cpp">MemCpyOptimizer.cpp</a>.</p>

</div>
</div>

### tryMergingIntoMemset() {#ae6144d8d036202f4e6c4034c7f3d7fb3}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">Instruction * MemCpyOptPass::tryMergingIntoMemset (<a href="/web-llvm/docs/api/classes/llvm/instruction">Instruction</a> * StartInst, <a href="/web-llvm/docs/api/classes/llvm/value">Value</a> * StartPtr, <a href="/web-llvm/docs/api/classes/llvm/value">Value</a> * ByteVal)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>When scanning forward over instructions, we look for some other patterns to fold away.</p>


<p>In particular, this looks for stores to neighboring locations of memory. If it sees enough consecutive ones, it attempts to merge them together into a memcpy/memset.</p>


<p>Declaration at line 84 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/transforms/include/llvm/transforms/scalar/memcpyoptimizer-h">MemCpyOptimizer.h</a>, definition at line 348 of file <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/scalar/memcpyoptimizer-cpp">MemCpyOptimizer.cpp</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Private Member Attributes

### AA {#a1942f604436459d0d79e5f094f0f3167}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">AAResults* llvm::MemCpyOptPass::AA = nullptr</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 46 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/transforms/include/llvm/transforms/scalar/memcpyoptimizer-h">MemCpyOptimizer.h</a>.</p>

</div>
</div>

### AC {#af86c77bf27ff17616328af5abac0766c}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">AssumptionCache* llvm::MemCpyOptPass::AC = nullptr</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 47 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/transforms/include/llvm/transforms/scalar/memcpyoptimizer-h">MemCpyOptimizer.h</a>.</p>

</div>
</div>

### DT {#ac237bb61ccfc540e7fecb97a19503c5c}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">DominatorTree* llvm::MemCpyOptPass::DT = nullptr</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 48 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/transforms/include/llvm/transforms/scalar/memcpyoptimizer-h">MemCpyOptimizer.h</a>.</p>

</div>
</div>

### EEA {#a9e22dabe946d2420130bbf0c5a2ce42a}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">EarliestEscapeAnalysis* llvm::MemCpyOptPass::EEA = nullptr</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 52 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/transforms/include/llvm/transforms/scalar/memcpyoptimizer-h">MemCpyOptimizer.h</a>.</p>

</div>
</div>

### MSSA {#af6217dcdf9861c3d22b7728d98ca63e4}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">MemorySSA* llvm::MemCpyOptPass::MSSA = nullptr</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 50 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/transforms/include/llvm/transforms/scalar/memcpyoptimizer-h">MemCpyOptimizer.h</a>.</p>

</div>
</div>

### MSSAU {#acbc62c464977178f914b1e8088a80724}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">MemorySSAUpdater* llvm::MemCpyOptPass::MSSAU = nullptr</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 51 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/transforms/include/llvm/transforms/scalar/memcpyoptimizer-h">MemCpyOptimizer.h</a>.</p>

</div>
</div>

### PDT {#a97b580492ad3a29e86d853e4632ed3c8}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">PostDominatorTree* llvm::MemCpyOptPass::PDT = nullptr</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 49 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/transforms/include/llvm/transforms/scalar/memcpyoptimizer-h">MemCpyOptimizer.h</a>.</p>

</div>
</div>

### TLI {#aa33bf6884a533653a7fec69f0725ec57}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">TargetLibraryInfo* llvm::MemCpyOptPass::TLI = nullptr</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 45 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/transforms/include/llvm/transforms/scalar/memcpyoptimizer-h">MemCpyOptimizer.h</a>.</p>

</div>
</div>

</div>

<hr/>

The documentation for this class was generated from the following files:

<ul>
<li><a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/transforms/include/llvm/transforms/scalar/memcpyoptimizer-h">MemCpyOptimizer.h</a></li>
<li><a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/scalar/memcpyoptimizer-cpp">MemCpyOptimizer.cpp</a></li>
</ul>

<hr/>

<p class="doxyGeneratedBy">Generated via <a href="https://github.com/xpack/doxygen2docusaurus">doxygen2docusaurus</a> by <a href="https://www.doxygen.nl">Doxygen</a> 1.15.0.</p>

</div>
