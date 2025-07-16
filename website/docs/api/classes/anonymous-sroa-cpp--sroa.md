---

# DO NOT EDIT!
# Automatically generated via doxygen2docusaurus by Doxygen.

slug: /api/classes/anonymous-sroa-cpp-/sroa
custom_edit_url: null
toc_max_heading_level: 4
keywords:
  - doxygen
  - reference
  - class

---

<div class="doxyPage">

# The `SROA` Class Reference

<p>An optimization pass providing Scalar Replacement of Aggregates. <a href="#details">More...</a></p>

## Declaration

<div class="doxyDeclaration">
class anonymous{SROA.cpp}::SROA { ... }
</div>

## Friends Index

<table class="doxyMembersIndex">

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">class</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a79522441dc59c0a101a4e208abdf855a">AllocaSliceRewriter</a></td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#afc5246d29111911b196d9a1c69aa812c">SROA</a> (LLVMContext *C, DomTreeUpdater *DTU, AssumptionCache *AC, SROAOptions PreserveCFG_)</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">std::pair&lt; bool, bool &gt;</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a8317779540f30fe6a5dda2359f023675">runSROA</a> (Function &amp;F)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Main run method used by both the <a href="/web-llvm/docs/api/classes/llvm/sroapass">SROAPass</a> and by the legacy pass. <a href="#a8317779540f30fe6a5dda2359f023675">More...</a></p>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#aacab3841a3ef28ce5d8eff4d06d0d081">presplitLoadsAndStores</a> (AllocaInst &amp;AI, AllocaSlices &amp;AS)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Pre-split loads and stores to simplify rewriting. <a href="#aacab3841a3ef28ce5d8eff4d06d0d081">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/allocainst">AllocaInst</a> *</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ae7365e0ad8b217267d8d669c030ba017">rewritePartition</a> (AllocaInst &amp;AI, AllocaSlices &amp;AS, Partition &amp;P)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Rewrite an alloca partition's users. <a href="#ae7365e0ad8b217267d8d669c030ba017">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">bool</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a71221c0b1a573a3bb9f5033cc8e5ab0d">splitAlloca</a> (AllocaInst &amp;AI, AllocaSlices &amp;AS)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Walks the slices of an alloca and form partitions based on them, rewriting each of their uses. <a href="#a71221c0b1a573a3bb9f5033cc8e5ab0d">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">bool</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#aca72f24d9848af8803ebfd85c4a2a9e9">propagateStoredValuesToLoads</a> (AllocaInst &amp;AI, AllocaSlices &amp;AS)</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">std::pair&lt; bool, bool &gt;</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ab7bd34f2cdc4fee8bd2dc6c96903aa82">runOnAlloca</a> (AllocaInst &amp;AI)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Analyze an alloca for <a href="/web-llvm/docs/api/classes/anonymous-sroa-cpp-/sroa">SROA</a>. <a href="#ab7bd34f2cdc4fee8bd2dc6c96903aa82">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">void</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#af4a4af2e04be471234631eed6ab8c168">clobberUse</a> (Use &amp;U)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Clobber a use with poison, deleting the used value if it becomes dead. <a href="#af4a4af2e04be471234631eed6ab8c168">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">bool</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a408e9739b91e3bbe158e8e21fc66b1b1">deleteDeadInstructions</a> (SmallPtrSetImpl&lt; AllocaInst * &gt; &amp;DeletedAllocas)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Delete the dead instructions accumulated in this run. <a href="#a408e9739b91e3bbe158e8e21fc66b1b1">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">bool</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ad580cb5b1c27faec5ac5818bd4b0370a">promoteAllocas</a> (Function &amp;F)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Promote the allocas, using the best available technique. <a href="#ad580cb5b1c27faec5ac5818bd4b0370a">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

</table>

## Private Member Attributes Index

<table class="doxyMembersIndex">

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/llvmcontext">LLVMContext</a> *<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#aab5db29f7fde580ba52164284ecb94ef">C</a></td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/domtreeupdater">DomTreeUpdater</a> *<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#aee619933430dce87db6d46cac853c3ad">DTU</a></td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/assumptioncache">AssumptionCache</a> *<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#af6caf54d2b4c70b9dbd28541e685c21b">AC</a></td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> bool</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a004ffa57ff51b76e8e11099a5854e618">PreserveCFG</a></td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/smallsetvector">SmallSetVector</a>&lt; <a href="/web-llvm/docs/api/classes/llvm/allocainst">AllocaInst</a> *, 16 &gt;</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a9bb8b741e320d9f12e63e955c1367430">Worklist</a></td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Worklist of alloca instructions to simplify. <a href="#a9bb8b741e320d9f12e63e955c1367430">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/smallvector">SmallVector</a>&lt; <a href="/web-llvm/docs/api/classes/llvm/weakvh">WeakVH</a>, 8 &gt;</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a730c9770522327bebf0f87bef1ab71b6">DeadInsts</a></td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>A collection of instructions to delete. <a href="#a730c9770522327bebf0f87bef1ab71b6">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/smallsetvector">SmallSetVector</a>&lt; <a href="/web-llvm/docs/api/classes/llvm/allocainst">AllocaInst</a> *, 16 &gt;</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a1aae3849009fdcd89acb4c5bd60f7a64">PostPromotionWorklist</a></td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Post-promotion worklist. <a href="#a1aae3849009fdcd89acb4c5bd60f7a64">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/setvector">SetVector</a>&lt; <a href="/web-llvm/docs/api/classes/llvm/allocainst">AllocaInst</a> *, <a href="/web-llvm/docs/api/classes/llvm/smallvector">SmallVector</a>&lt; <a href="/web-llvm/docs/api/classes/llvm/allocainst">AllocaInst</a> * &gt;, <a href="/web-llvm/docs/api/classes/llvm/smallptrset">SmallPtrSet</a>&lt; <a href="/web-llvm/docs/api/classes/llvm/allocainst">AllocaInst</a> *, 16 &gt;, 16 &gt;</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a38a5d453f1c9b0e5b1f56a1470a838b1">PromotableAllocas</a></td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>A collection of alloca instructions we can directly promote. <a href="#a38a5d453f1c9b0e5b1f56a1470a838b1">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/smallsetvector">SmallSetVector</a>&lt; <a href="/web-llvm/docs/api/classes/llvm/phinode">PHINode</a> *, 8 &gt;</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a864c9ba1b56309fefc0eda114e71aa10">SpeculatablePHIs</a></td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>A worklist of PHIs to speculate prior to promoting allocas. <a href="#a864c9ba1b56309fefc0eda114e71aa10">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/structs/llvm/smallmapvector">SmallMapVector</a>&lt; <a href="/web-llvm/docs/api/classes/llvm/selectinst">SelectInst</a> *, <a href="/web-llvm/docs/api/namespaces/anonymous-sroa-cpp-/#a0bd6174f8bb3840fa3e80f8c870023fd">RewriteableMemOps</a>, 8 &gt;</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a105c431155e6b5c340f3630c981fae3e">SelectsToRewrite</a></td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>A worklist of select instructions to rewrite prior to promoting allocas. <a href="#a105c431155e6b5c340f3630c981fae3e">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

</table>

## Private Static Functions Index

<table class="doxyMembersIndex">

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">static std::optional&lt; <a href="/web-llvm/docs/api/namespaces/anonymous-sroa-cpp-/#a0bd6174f8bb3840fa3e80f8c870023fd">RewriteableMemOps</a> &gt;</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a1d9e8c850d077a5426394ffbcb4224c7">isSafeSelectToSpeculate</a> (SelectInst &amp;SI, bool PreserveCFG)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Select instructions that use an alloca and are subsequently loaded can be rewritten to load both input pointers and then select between the result, allowing the load of the alloca to be promoted. <a href="#a1d9e8c850d077a5426394ffbcb4224c7">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

</table>

## Description {#details}

<p>An optimization pass providing Scalar Replacement of Aggregates.</p>


<p>This pass takes allocations which can be completely analyzed (that is, they don't escape) and tries to turn them into scalar SSA values. There are a few steps to this process.</p>


<p>1) It takes allocations of aggregates and analyzes the ways in which they are used to try to split them into smaller allocations, ideally of a single scalar data type. It will split up memcpy and memset accesses as necessary and try to isolate individual scalar accesses. 2) It will transform accesses into forms which are suitable for SSA value promotion. This can be replacing a memset with a scalar store of an integer value, or it can involve speculating operations on a PHI or select to be a PHI or select of the results. 3) Finally, this will try to detect a pattern of accesses which map cleanly onto insert and extract operations on a vector value, and convert them to this form. By doing so, it will enable promotion of vector aggregates to SSA vector values.</p>


<p>Definition at line 171 of file <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/scalar/sroa-cpp">SROA.cpp</a>.</p>


<div class="doxySectionDef">

## Friends

### AllocaSliceRewriter {#a79522441dc59c0a101a4e208abdf855a}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">friend class <a href="/web-llvm/docs/api/classes/anonymous-sroa-cpp-/allocaslicerewriter">AllocaSliceRewriter</a></td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">


<p>Definition at line 246 of file <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/scalar/sroa-cpp">SROA.cpp</a>.</p>


<p>References <a href="#a79522441dc59c0a101a4e208abdf855a">AllocaSliceRewriter</a>, <a href="/web-llvm/docs/api/files/lib/lib/support/md5-cpp/#a96d73bbd7af15cb1fc38c3f4a3bd82e9">F</a> and <a href="/web-llvm/docs/api/files/lib/lib/option/option-cpp/#a04665169063c8ca1f2ea96c27fc7c2b2">P</a>.</p>


<p>Referenced by <a href="#a79522441dc59c0a101a4e208abdf855a">AllocaSliceRewriter</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Public Constructors

### SROA() {#afc5246d29111911b196d9a1c69aa812c}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">anonymous{SROA.cpp}::SROA::SROA (<a href="/web-llvm/docs/api/classes/llvm/llvmcontext">LLVMContext</a> * C, <a href="/web-llvm/docs/api/classes/llvm/domtreeupdater">DomTreeUpdater</a> * DTU, <a href="/web-llvm/docs/api/classes/llvm/assumptioncache">AssumptionCache</a> * AC, <a href="/web-llvm/docs/api/namespaces/llvm/#af4e437674a39417056e3028415053139">SROAOptions</a> PreserveCFG_)</td>
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



<p>Definition at line 237 of file <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/scalar/sroa-cpp">SROA.cpp</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Public Member Functions

### runSROA() {#a8317779540f30fe6a5dda2359f023675}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">std::pair&lt; bool, bool &gt; SROA::runSROA (<a href="/web-llvm/docs/api/classes/llvm/function">Function</a> &amp; F)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Main run method used by both the <a href="/web-llvm/docs/api/classes/llvm/sroapass">SROAPass</a> and by the legacy pass.</p>

<p>Definition at line 243 of file <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/scalar/sroa-cpp">SROA.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/silowercontrolflow-cpp/#a4868c5d81c5ccc98c47aeab6244346a0">assert</a>, <a href="/web-llvm/docs/api/classes/llvm/basicblock/#a0ed5f3ab3c2e4196ee0cffffa080c062">llvm::BasicBlock::begin</a>, <a href="/web-llvm/docs/api/classes/llvm/smallptrsetimplbase/#a16413f1a88d8baca228d0a1b4cc0bfc6">llvm::SmallPtrSetImplBase::clear</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a7c46c742c31be54870e2038048e6b391">llvm::dbgs</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/arm/armslshardening-cpp/#ad467c4ab9119043f9b7750ab986be61a">DL</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a22eeee01734061ac1b31ccd994c49eef">llvm::dyn_cast</a>, <a href="/web-llvm/docs/api/classes/llvm/smallptrsetimplbase/#af8a50544090e81ac83601aff8f4b0142">llvm::SmallPtrSetImplBase::empty</a>, <a href="/web-llvm/docs/api/classes/llvm/basicblock/#a0b4e7bee9b8575cc7db73329f1a561bd">llvm::BasicBlock::end</a>, <a href="/web-llvm/docs/api/files/lib/lib/support/md5-cpp/#a96d73bbd7af15cb1fc38c3f4a3bd82e9">F</a>, <a href="/web-llvm/docs/api/classes/llvm/allocainst/#a9b5ec84ea363eca9e35ddca20a5313af">llvm::AllocaInst::getAllocatedType</a>, <a href="/web-llvm/docs/api/files/lib/lib/support/md5-cpp/#ac0eafdc9ee161b71e7af98af736952fd">I</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a5023b360abc7a5d1612061fba30003a6">llvm::isAllocaPromotable</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#aa9ef2dbd1b7ce921093f7d4a7bd4cc5c">llvm::isAssignmentTrackingEnabled</a>, <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/support/debug-h/#a196897517069dda1bdb549e24468f7d7">LLVM_DEBUG</a> and <a href="/web-llvm/docs/api/namespaces/llvm/#a08f3f942afc0ee9115a8f9fa87e9191d">llvm::RemoveRedundantDbgInstrs</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/classes/anonymous-sroa-cpp-/sroalegacypass/#a8e87a8ac1e3d62aaa253240fc597f797">anonymous{SROA.cpp}::SROALegacyPass::runOnFunction</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Private Member Functions

### clobberUse() {#af4a4af2e04be471234631eed6ab8c168}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void SROA::clobberUse (<a href="/web-llvm/docs/api/classes/llvm/use">Use</a> &amp; U)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Clobber a use with poison, deleting the used value if it becomes dead.</p>

<p>Definition at line 253 of file <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/scalar/sroa-cpp">SROA.cpp</a>.</p>

</div>
</div>

### deleteDeadInstructions() {#a408e9739b91e3bbe158e8e21fc66b1b1}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool SROA::deleteDeadInstructions (<a href="/web-llvm/docs/api/classes/llvm/smallptrsetimpl">SmallPtrSetImpl</a>&lt; <a href="/web-llvm/docs/api/classes/llvm/allocainst">AllocaInst</a> * &gt; &amp; DeletedAllocas)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Delete the dead instructions accumulated in this run.</p>


<p>Recursively deletes the dead instructions we've accumulated. This is done at the very end to maximize locality of the recursive delete and to minimize the problems of invalidated instruction pointers as such pointers are used heavily in the intermediate stages of the algorithm.</p>


<p>We also record the alloca instructions deleted here so that they aren't subsequently handed to mem2reg to promote.</p>


<p>Definition at line 254 of file <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/scalar/sroa-cpp">SROA.cpp</a>.</p>

</div>
</div>

### presplitLoadsAndStores() {#aacab3841a3ef28ce5d8eff4d06d0d081}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool SROA::presplitLoadsAndStores (<a href="/web-llvm/docs/api/classes/llvm/allocainst">AllocaInst</a> &amp; AI, <a href="/web-llvm/docs/api/classes/anonymous-sroa-cpp-/allocaslices">AllocaSlices</a> &amp; AS)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Pre-split loads and stores to simplify rewriting.</p>


<p>We want to break up the splittable load+store pairs as much as possible. This is important to do as a preprocessing step, as once we start rewriting the accesses to partitions of the alloca we lose the necessary information to correctly split apart paired loads and stores which both point into this alloca. The case to consider is something like the following:</p>


<p>a = alloca [12 x i8] gep1 = getelementptr i8, ptr a, i32 0 gep2 = getelementptr i8, ptr a, i32 4 gep3 = getelementptr i8, ptr a, i32 8 store float 0.0, ptr gep1 store float 1.0, ptr gep2 v = load i64, ptr gep1 store i64 v, ptr gep2 f1 = load float, ptr gep2 f2 = load float, ptr gep3</p>


<p>Here we want to form 3 partitions of the alloca, each 4 bytes large, and promote everything so we recover the 2 SSA values that should have been there all along.</p>


<dl class="doxySectionUser">
<dt>Returns</dt>
<dd><p>true if any changes are made.</p></dd>
</dl>


<p>Definition at line 248 of file <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/scalar/sroa-cpp">SROA.cpp</a>.</p>

</div>
</div>

### promoteAllocas() {#ad580cb5b1c27faec5ac5818bd4b0370a}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool SROA::promoteAllocas (<a href="/web-llvm/docs/api/classes/llvm/function">Function</a> &amp; F)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Promote the allocas, using the best available technique.</p>


<p>This attempts to promote whatever allocas have been identified as viable in the PromotableAllocas list. If that list is empty, there is nothing to do. This function returns whether any promotion occurred.</p>


<p>Definition at line 255 of file <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/scalar/sroa-cpp">SROA.cpp</a>.</p>

</div>
</div>

### propagateStoredValuesToLoads() {#aca72f24d9848af8803ebfd85c4a2a9e9}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool SROA::propagateStoredValuesToLoads (<a href="/web-llvm/docs/api/classes/llvm/allocainst">AllocaInst</a> &amp; AI, <a href="/web-llvm/docs/api/classes/anonymous-sroa-cpp-/allocaslices">AllocaSlices</a> &amp; AS)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 251 of file <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/scalar/sroa-cpp">SROA.cpp</a>.</p>

</div>
</div>

### rewritePartition() {#ae7365e0ad8b217267d8d669c030ba017}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">AllocaInst * SROA::rewritePartition (<a href="/web-llvm/docs/api/classes/llvm/allocainst">AllocaInst</a> &amp; AI, <a href="/web-llvm/docs/api/classes/anonymous-sroa-cpp-/allocaslices">AllocaSlices</a> &amp; AS, <a href="/web-llvm/docs/api/classes/anonymous-sroa-cpp-/partition">Partition</a> &amp; P)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Rewrite an alloca partition's users.</p>


<p>This routine drives both of the rewriting goals of the <a href="/web-llvm/docs/api/classes/anonymous-sroa-cpp-/sroa">SROA</a> pass. It tries to rewrite uses of an alloca partition to be conducive for SSA value promotion. If the partition needs a new, more refined alloca, this will build that new alloca, preserving as much type information as possible, and rewrite the uses of the old alloca to point at the new one and have the appropriate new offsets. It also evaluates how successful the rewrite was at enabling promotion and if it was successful queues the alloca to be promoted.</p>


<p>Definition at line 249 of file <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/scalar/sroa-cpp">SROA.cpp</a>.</p>

</div>
</div>

### runOnAlloca() {#ab7bd34f2cdc4fee8bd2dc6c96903aa82}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">std::pair&lt; bool, bool &gt; SROA::runOnAlloca (<a href="/web-llvm/docs/api/classes/llvm/allocainst">AllocaInst</a> &amp; AI)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Analyze an alloca for <a href="/web-llvm/docs/api/classes/anonymous-sroa-cpp-/sroa">SROA</a>.</p>


<p>This analyzes the alloca to ensure we can reason about it, builds the slices of the alloca, and then hands it off to be split and rewritten as needed.</p>


<p>Definition at line 252 of file <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/scalar/sroa-cpp">SROA.cpp</a>.</p>

</div>
</div>

### splitAlloca() {#a71221c0b1a573a3bb9f5033cc8e5ab0d}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool SROA::splitAlloca (<a href="/web-llvm/docs/api/classes/llvm/allocainst">AllocaInst</a> &amp; AI, <a href="/web-llvm/docs/api/classes/anonymous-sroa-cpp-/allocaslices">AllocaSlices</a> &amp; AS)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Walks the slices of an alloca and form partitions based on them, rewriting each of their uses.</p>

<p>Definition at line 250 of file <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/scalar/sroa-cpp">SROA.cpp</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Private Member Attributes

### AC {#af6caf54d2b4c70b9dbd28541e685c21b}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">AssumptionCache* const anonymous{SROA.cpp}::SROA::AC</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 174 of file <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/scalar/sroa-cpp">SROA.cpp</a>.</p>

</div>
</div>

### C {#aab5db29f7fde580ba52164284ecb94ef}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">LLVMContext* const anonymous{SROA.cpp}::SROA::C</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 172 of file <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/scalar/sroa-cpp">SROA.cpp</a>.</p>

</div>
</div>

### DeadInsts {#a730c9770522327bebf0f87bef1ab71b6}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">SmallVector&lt;WeakVH, 8&gt; anonymous{SROA.cpp}::SROA::DeadInsts</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>A collection of instructions to delete.</p>


<p>We try to batch deletions to simplify code and make things a bit more efficient. We also make sure there is no dangling pointers.</p>


<p>Definition at line 189 of file <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/scalar/sroa-cpp">SROA.cpp</a>.</p>

</div>
</div>

### DTU {#aee619933430dce87db6d46cac853c3ad}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">DomTreeUpdater* const anonymous{SROA.cpp}::SROA::DTU</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 173 of file <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/scalar/sroa-cpp">SROA.cpp</a>.</p>

</div>
</div>

### PostPromotionWorklist {#a1aae3849009fdcd89acb4c5bd60f7a64}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">SmallSetVector&lt;AllocaInst *, 16&gt; anonymous{SROA.cpp}::SROA::PostPromotionWorklist</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Post-promotion worklist.</p>


<p>Sometimes we discover an alloca which has a high probability of becoming viable for <a href="/web-llvm/docs/api/classes/anonymous-sroa-cpp-/sroa">SROA</a> after a round of promotion takes place. In those cases, the alloca is enqueued here for re-processing.</p>


<p>Note that we have to be very careful to clear allocas out of this list in the event they are deleted.</p>


<p>Definition at line 199 of file <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/scalar/sroa-cpp">SROA.cpp</a>.</p>

</div>
</div>

### PreserveCFG {#a004ffa57ff51b76e8e11099a5854e618}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">const bool anonymous{SROA.cpp}::SROA::PreserveCFG</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 175 of file <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/scalar/sroa-cpp">SROA.cpp</a>.</p>

</div>
</div>

### PromotableAllocas {#a38a5d453f1c9b0e5b1f56a1470a838b1}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">SetVector&lt;AllocaInst *, SmallVector&lt;AllocaInst *&gt;, SmallPtrSet&lt;AllocaInst *, 16&gt;, 16&gt; anonymous{SROA.cpp}::SROA::PromotableAllocas</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>A collection of alloca instructions we can directly promote.</p>

<p>Definition at line 204 of file <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/scalar/sroa-cpp">SROA.cpp</a>.</p>

</div>
</div>

### SelectsToRewrite {#a105c431155e6b5c340f3630c981fae3e}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">SmallMapVector&lt;SelectInst *, RewriteableMemOps, 8&gt; anonymous{SROA.cpp}::SROA::SelectsToRewrite</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>A worklist of select instructions to rewrite prior to promoting allocas.</p>

<p>Definition at line 215 of file <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/scalar/sroa-cpp">SROA.cpp</a>.</p>

</div>
</div>

### SpeculatablePHIs {#a864c9ba1b56309fefc0eda114e71aa10}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">SmallSetVector&lt;PHINode *, 8&gt; anonymous{SROA.cpp}::SROA::SpeculatablePHIs</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>A worklist of PHIs to speculate prior to promoting allocas.</p>


<p>All of these PHIs have been checked for the safety of speculation and by being speculated will allow promoting allocas currently in the promotable queue.</p>


<p>Definition at line 211 of file <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/scalar/sroa-cpp">SROA.cpp</a>.</p>

</div>
</div>

### Worklist {#a9bb8b741e320d9f12e63e955c1367430}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">SmallSetVector&lt;AllocaInst *, 16&gt; anonymous{SROA.cpp}::SROA::Worklist</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Worklist of alloca instructions to simplify.</p>


<p>Each alloca in the function is added to this. Each new alloca formed gets added to it as well to recursively simplify unless that alloca can be directly promoted. Finally, each time we rewrite a use of an alloca other the one being actively rewritten, we add it back onto the list if not already present to ensure it is re-visited.</p>


<p>Definition at line 184 of file <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/scalar/sroa-cpp">SROA.cpp</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Private Static Functions

### isSafeSelectToSpeculate() {#a1d9e8c850d077a5426394ffbcb4224c7}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">std::optional&lt; RewriteableMemOps &gt; SROA::isSafeSelectToSpeculate (<a href="/web-llvm/docs/api/classes/llvm/selectinst">SelectInst</a> &amp; SI, bool PreserveCFG)</td>
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

<p>Select instructions that use an alloca and are subsequently loaded can be rewritten to load both input pointers and then select between the result, allowing the load of the alloca to be promoted.</p>


<p>From this: P2 = select i1 cond, ptr Alloca, ptr Other V = load &lt;type&gt;, ptr P2 to: V1 = load &lt;type&gt;, ptr Alloca -&gt; will be mem2reg'd V2 = load &lt;type&gt;, ptr Other V = select i1 cond, &lt;type&gt; V1, &lt;type&gt; V2</p>


<p>We can do this to a select if its only uses are loads and if either the operand to the select can be loaded unconditionally, or if we are allowed to perform CFG modifications. If found an intervening bitcast with a single use of the load, allow the promotion.</p>


<p>Definition at line 234 of file <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/scalar/sroa-cpp">SROA.cpp</a>.</p>

</div>
</div>

</div>

<hr/>

The documentation for this class was generated from the following file:

<ul>
<li><a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/scalar/sroa-cpp">SROA.cpp</a></li>
</ul>

<hr/>

<p class="doxyGeneratedBy">Generated via <a href="https://github.com/xpack/doxygen2docusaurus">doxygen2docusaurus</a> by <a href="https://www.doxygen.nl">Doxygen</a> 1.15.0.</p>

</div>
