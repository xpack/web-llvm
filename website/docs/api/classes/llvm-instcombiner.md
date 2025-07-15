---

# DO NOT EDIT!
# Automatically generated via doxygen2docusaurus by Doxygen.

slug: /api/classes/llvm/instcombiner
custom_edit_url: null
toc_max_heading_level: 4
keywords:
  - doxygen
  - reference
  - class

---

<div class="doxyPage">

# The `InstCombiner` Class Reference

<p>The core instruction combiner logic. <a href="#details">More...</a></p>

## Declaration

<div class="doxyDeclaration">
class llvm::InstCombiner { ... }
</div>

## Included Headers

<div class="doxyIncludesList">#include "<a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/transforms/include/llvm/transforms/instcombine/instcombiner-h">llvm/Transforms/InstCombine/InstCombiner.h</a>"
</div>

## Derived Classes

<table class="doxyMembersIndex">

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">class</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/instcombinerimpl">InstCombinerImpl</a></td>
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

## Public Member Typedefs Index

<table class="doxyMembersIndex">

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">using</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a19c4df37b96c2a73991556b696924584">BuilderTy</a> = <a href="/web-llvm/docs/api/classes/llvm/irbuilder">IRBuilder</a>&lt; <a href="/web-llvm/docs/api/classes/llvm/targetfolder">TargetFolder</a>, <a href="/web-llvm/docs/api/classes/llvm/irbuildercallbackinserter">IRBuilderCallbackInserter</a> &gt;</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>An <a href="/web-llvm/docs/api/classes/llvm/irbuilder">IRBuilder</a> that automatically inserts new instructions into the worklist. <a href="#a19c4df37b96c2a73991556b696924584">More...</a></p>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#af70e33de5e351fc22288a3130b0428b6">InstCombiner</a> (InstructionWorklist &amp;Worklist, BuilderTy &amp;Builder, bool MinimizeSize, AAResults *AA, AssumptionCache &amp;AC, TargetLibraryInfo &amp;TLI, TargetTransformInfo &amp;TTI, DominatorTree &amp;DT, OptimizationRemarkEmitter &amp;ORE, BlockFrequencyInfo *BFI, BranchProbabilityInfo *BPI, ProfileSummaryInfo *PSI, const DataLayout &amp;DL, ReversePostOrderTraversal&lt; BasicBlock * &gt; &amp;RPOT)</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a239b9fd8ca2ce771713c69e4fca765af">~InstCombiner</a> ()=default</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ab98cb2aaf6e757aac9c471f85f113a50">getFreelyInvertedImpl</a> (Value *V, bool WillInvertAllUses, BuilderTy *Builder, bool &amp;DoesConsume, unsigned Depth)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Return nonnull value if V is free to invert under the condition of WillInvertAllUses. <a href="#ab98cb2aaf6e757aac9c471f85f113a50">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/value">Value</a> *</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#af11b32adde24fea55878e66dd7139362">getFreelyInverted</a> (Value *V, bool WillInvertAllUses, BuilderTy *Builder, bool &amp;DoesConsume)</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ab1dfd539be512820814cce9f06adb250">getFreelyInverted</a> (Value *V, bool WillInvertAllUses, BuilderTy *Builder)</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a1f819cdc746560fd28977b1175030cff">isFreeToInvert</a> (Value *V, bool WillInvertAllUses, bool &amp;DoesConsume)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Return true if the specified value is free to invert (apply ~ to). <a href="#a1f819cdc746560fd28977b1175030cff">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">bool</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a18727b52ba4b34ed267df9b3cfa6c407">isFreeToInvert</a> (Value *V, bool WillInvertAllUses)</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ab0cf90f56e055b09227ab0f84acc4083">canFreelyInvertAllUsersOf</a> (Instruction *V, Value *IgnoredUser)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Given i1 V, can every user of V be freely adapted if V is changed to !V ? <a href="#ab0cf90f56e055b09227ab0f84acc4083">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">void</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ab86d58ae73173328360a32cbbb0d5b14">addToWorklist</a> (Instruction *I)</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/assumptioncache">AssumptionCache</a> &amp;</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ae2eddfa57a32ec610ce9685720d591b7">getAssumptionCache</a> () const</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/targetlibraryinfo">TargetLibraryInfo</a> &amp;</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a3cf623e18c507f6a12ba24ee04320625">getTargetLibraryInfo</a> () const</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/dominatortree">DominatorTree</a> &amp;</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a209240824927e66a0caa50636623e79a">getDominatorTree</a> () const</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/datalayout">DataLayout</a> &amp;</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a16262e69f9cdf5d2c9d5623c3b06af43">getDataLayout</a> () const</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/structs/llvm/simplifyquery">SimplifyQuery</a> &amp;</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#af56f7a148b00922368e55ab9c4948724">getSimplifyQuery</a> () const</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/optimizationremarkemitter">OptimizationRemarkEmitter</a> &amp;</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ad266f62eb13926ec63289681c04564fb">getOptimizationRemarkEmitter</a> () const</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/blockfrequencyinfo">BlockFrequencyInfo</a> *</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a441e8056feed591b0e0fd1b2a6ac81c0">getBlockFrequencyInfo</a> () const</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/profilesummaryinfo">ProfileSummaryInfo</a> *</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ad08bc4ef198e2c99b48b26cdd7c118b0">getProfileSummaryInfo</a> () const</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">std::optional&lt; <a href="/web-llvm/docs/api/classes/llvm/instruction">Instruction</a> * &gt;</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#aaeec6d7b5f74d07ed6e0e15fc652e327">targetInstCombineIntrinsic</a> (IntrinsicInst &amp;II)</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">std::optional&lt; <a href="/web-llvm/docs/api/classes/llvm/value">Value</a> * &gt;</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#adccadc34e77a7a0982a0832ce2419a00">targetSimplifyDemandedUseBitsIntrinsic</a> (IntrinsicInst &amp;II, APInt DemandedMask, KnownBits &amp;Known, bool &amp;KnownBitsComputed)</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">std::optional&lt; <a href="/web-llvm/docs/api/classes/llvm/value">Value</a> * &gt;</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ac1539f8fc8167c5be0eb439a4c5187fc">targetSimplifyDemandedVectorEltsIntrinsic</a> (IntrinsicInst &amp;II, APInt DemandedElts, APInt &amp;UndefElts, APInt &amp;UndefElts2, APInt &amp;UndefElts3, std::function&lt; void(Instruction *, unsigned, APInt, APInt &amp;)&gt; SimplifyAndSetOp)</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ac17fa2d851e729e9c308df593b098fc1">computeBackEdges</a> ()</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#af5a8feb3d194df1e72e6a32cc746bc97">isBackEdge</a> (const BasicBlock *From, const BasicBlock *To)</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/instruction">Instruction</a> *</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a46f1e493b5d0822af6344aa294f93fdb">InsertNewInstBefore</a> (Instruction *New, BasicBlock::iterator Old)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Inserts an instruction <span class="doxyComputerOutput">New</span> before instruction <span class="doxyComputerOutput">Old</span>. <a href="#a46f1e493b5d0822af6344aa294f93fdb">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/instruction">Instruction</a> *</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a7ce29ca36c91b8c790b0f8b2560c3033">InsertNewInstWith</a> (Instruction *New, BasicBlock::iterator Old)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Same as InsertNewInstBefore, but also sets the debug loc. <a href="#a7ce29ca36c91b8c790b0f8b2560c3033">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/instruction">Instruction</a> *</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a49f1bd0bdf0ef741bdd714cc1188d7c5">replaceInstUsesWith</a> (Instruction &amp;I, Value *V)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>A combiner-aware RAUW-like routine. <a href="#a49f1bd0bdf0ef741bdd714cc1188d7c5">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/instruction">Instruction</a> *</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ac2a56636a6f3742f5e495f67e67b6b36">replaceOperand</a> (Instruction &amp;I, unsigned OpNum, Value *V)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Replace operand of instruction and add old operand to the worklist. <a href="#ac2a56636a6f3742f5e495f67e67b6b36">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">void</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a6c1f812e984c68bc39c22b63a117e1eb">replaceUse</a> (Use &amp;U, Value *NewValue)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Replace use and add the previously used value to the worklist. <a href="#a6c1f812e984c68bc39c22b63a117e1eb">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/instruction">Instruction</a> *</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a190073d8a0e9a2eeb56f0cb96816d7ef">eraseInstFromFunction</a> (Instruction &amp;I)=0</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p><a href="/web-llvm/docs/api/classes/llvm/combiner">Combiner</a> aware instruction erasure. <a href="#a190073d8a0e9a2eeb56f0cb96816d7ef">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">void</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ae099c6fa4a0b06306ece7dd372e8d02a">computeKnownBits</a> (const Value *V, KnownBits &amp;Known, unsigned Depth, const Instruction *CxtI) const</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/structs/llvm/knownbits">KnownBits</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a6c1e1b56ee28b4d21a3950d48175e284">computeKnownBits</a> (const Value *V, unsigned Depth, const Instruction *CxtI) const</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a46e6cc426055f50cdb04009adb4c2f94">isKnownToBeAPowerOfTwo</a> (const Value *V, bool OrZero=false, unsigned Depth=0, const Instruction *CxtI=nullptr)</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ae506e7be0a7aaf9001e31d5fca5f2fbc">MaskedValueIsZero</a> (const Value *V, const APInt &amp;Mask, unsigned Depth=0, const Instruction *CxtI=nullptr) const</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a879221accd38e1327b8dcf596650b031">ComputeNumSignBits</a> (const Value *Op, unsigned Depth=0, const Instruction *CxtI=nullptr) const</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#afe741651c79e1ff35939d1c04a3a191b">ComputeMaxSignificantBits</a> (const Value *Op, unsigned Depth=0, const Instruction *CxtI=nullptr) const</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/namespaces/llvm/#a06c60fef11885eadbda4026c83ae9a13">OverflowResult</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a20be54dc5cf0b5f4d1a53adee1215d96">computeOverflowForUnsignedMul</a> (const Value *LHS, const Value *RHS, const Instruction *CxtI, bool IsNSW=false) const</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/namespaces/llvm/#a06c60fef11885eadbda4026c83ae9a13">OverflowResult</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#acfd758f11fb745755ce05f4763dea3c4">computeOverflowForSignedMul</a> (const Value *LHS, const Value *RHS, const Instruction *CxtI) const</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/namespaces/llvm/#a06c60fef11885eadbda4026c83ae9a13">OverflowResult</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#aeea35a035c67331d0d1383bf392b1d6e">computeOverflowForUnsignedAdd</a> (const WithCache&lt; const Value * &gt; &amp;LHS, const WithCache&lt; const Value * &gt; &amp;RHS, const Instruction *CxtI) const</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/namespaces/llvm/#a06c60fef11885eadbda4026c83ae9a13">OverflowResult</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a5ab19cff71a6dcbd4d061468d868de48">computeOverflowForSignedAdd</a> (const WithCache&lt; const Value * &gt; &amp;LHS, const WithCache&lt; const Value * &gt; &amp;RHS, const Instruction *CxtI) const</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/namespaces/llvm/#a06c60fef11885eadbda4026c83ae9a13">OverflowResult</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a6e3d062a96f0592c80d7a2e829be2aa3">computeOverflowForUnsignedSub</a> (const Value *LHS, const Value *RHS, const Instruction *CxtI) const</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/namespaces/llvm/#a06c60fef11885eadbda4026c83ae9a13">OverflowResult</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a0056e5666f4dff4b171f6817deb601c6">computeOverflowForSignedSub</a> (const Value *LHS, const Value *RHS, const Instruction *CxtI) const</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a95d0ee42ca35b04f96e22c6ae954e2f7">SimplifyDemandedBits</a> (Instruction *I, unsigned OpNo, const APInt &amp;DemandedMask, KnownBits &amp;Known, unsigned Depth, const SimplifyQuery &amp;Q)=0</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a7ff4e7685008dfb8e6a970b9130a1015">SimplifyDemandedBits</a> (Instruction *I, unsigned OpNo, const APInt &amp;DemandedMask, KnownBits &amp;Known)</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a98434f092f1b1a571d9e53226ab75a06">SimplifyDemandedVectorElts</a> (Value *V, APInt DemandedElts, APInt &amp;UndefElts, unsigned Depth=0, bool AllowMultipleUsers=false)=0</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#aed7a042bbe624a8dcfdfb66c8bf39777">isValidAddrSpaceCast</a> (unsigned FromAS, unsigned ToAS) const</td>
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

## Public Member Attributes Index

<table class="doxyMembersIndex">

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">uint64_t</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a4bc1fafcc9582581002518df62792214">MaxArraySizeForCombine</a> = 0</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Maximum size of array considered when transforming. <a href="#a4bc1fafcc9582581002518df62792214">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="#a19c4df37b96c2a73991556b696924584">BuilderTy</a> &amp;</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ae1d331bc844ecb92bdeb0b706ae04396">Builder</a></td>
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

## Protected Member Attributes Index

<table class="doxyMembersIndex">

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/instructionworklist">InstructionWorklist</a> &amp;</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a7b93340fbcab35a38a04bf49aa3113a0">Worklist</a></td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>A worklist of the instructions that need to be simplified. <a href="#a7b93340fbcab35a38a04bf49aa3113a0">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> bool</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a8d57399452f30fb78195887945ae507c">MinimizeSize</a></td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a4764870a6b87dce34acb4e5eaef32e42">AA</a></td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/assumptioncache">AssumptionCache</a> &amp;</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ab63bb17a04c3e86b58219750716899a9">AC</a></td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/targetlibraryinfo">TargetLibraryInfo</a> &amp;</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a3ccb79ce550ca98c6f524c1c6bdd06a1">TLI</a></td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/dominatortree">DominatorTree</a> &amp;</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ac881b40b83c0bd8934689bdc8c306cf5">DT</a></td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/datalayout">DataLayout</a> &amp;</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a878e8128a9a4e5626df91dcd91cba337">DL</a></td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/structs/llvm/simplifyquery">SimplifyQuery</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a067e49eb19f14e50f84cf4b4e7f6acde">SQ</a></td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/optimizationremarkemitter">OptimizationRemarkEmitter</a> &amp;</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#aeae5f7d492700a5221d5252b72e8466a">ORE</a></td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/blockfrequencyinfo">BlockFrequencyInfo</a> *</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a25e411550ff000d1660e2376e3ae2ef8">BFI</a></td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/branchprobabilityinfo">BranchProbabilityInfo</a> *</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a7f74e84c9b2bc2441706161c2ed9cc5a">BPI</a></td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/profilesummaryinfo">ProfileSummaryInfo</a> *</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ad2f83bae44783989a87e7200ae678c76">PSI</a></td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/domconditioncache">DomConditionCache</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a888ebf4b0f794a1c13741d38f0c4aa61">DC</a></td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/reversepostordertraversal">ReversePostOrderTraversal</a>&lt; <a href="/web-llvm/docs/api/classes/llvm/basicblock">BasicBlock</a> * &gt; &amp;</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a8768d7bd3a905c9cd89c3738d4873a0d">RPOT</a></td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ae03c488dcba2bb63f265b62001cc361e">MadeIRChange</a> = false</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/smalldenseset">SmallDenseSet</a>&lt; std::pair&lt; <a href="/web-llvm/docs/api/classes/llvm/basicblock">BasicBlock</a> *, <a href="/web-llvm/docs/api/classes/llvm/basicblock">BasicBlock</a> * &gt;, 8 &gt;</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ad9606d00d0f1d7488ee416b25857f223">DeadEdges</a></td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Edges that are known to never be taken. <a href="#ad9606d00d0f1d7488ee416b25857f223">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/smalldensemap">SmallDenseMap</a>&lt; <a href="/web-llvm/docs/api/classes/llvm/basicblock">BasicBlock</a> *, <a href="/web-llvm/docs/api/classes/llvm/smallvector">SmallVector</a>&lt; <a href="/web-llvm/docs/api/classes/llvm/basicblock">BasicBlock</a> * &gt;, 8 &gt;</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a3b7ae785888d5e91d84157171db3876c">PredOrder</a></td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Order of predecessors to canonicalize phi nodes towards. <a href="#a3b7ae785888d5e91d84157171db3876c">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/smalldenseset">SmallDenseSet</a>&lt; std::pair&lt; <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/basicblock">BasicBlock</a> *, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/basicblock">BasicBlock</a> * &gt;, 8 &gt;</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#abca480cb3ed0ecf3fe3bde76bdf4b230">BackEdges</a></td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Backedges, used to avoid pushing instructions across backedges in cases where this may result in infinite combine loops. <a href="#abca480cb3ed0ecf3fe3bde76bdf4b230">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">bool</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a577df1f2641fe6bf067c364d94154cf1">ComputedBackEdges</a> = false</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/targettransforminfo">TargetTransformInfo</a> &amp;</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a5696bc370733423fa09de368b102e92c">TTIForTargetIntrinsicsOnly</a></td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Only used to call target specific intrinsic combining. <a href="#a5696bc370733423fa09de368b102e92c">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

</table>

## Public Static Functions Index

<table class="doxyMembersIndex">

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">static <a href="/web-llvm/docs/api/classes/llvm/value">Value</a> *</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#aa1eeea37af7eeec30772c649d25cd1ba">peekThroughBitcast</a> (Value *V, bool OneUseOnly=false)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Return the source operand of a potentially bitcasted value while optionally checking if it has one use. <a href="#aa1eeea37af7eeec30772c649d25cd1ba">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">static unsigned</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a2f79a062519c0854b4b97bbceac77997">getComplexity</a> (Value *V)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Assign a complexity or rank value to LLVM Values. <a href="#a2f79a062519c0854b4b97bbceac77997">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">static bool</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a7245fe59c5c3470907144f999fbb258a">isCanonicalPredicate</a> (CmpPredicate Pred)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p><a href="/web-llvm/docs/api/classes/predicate">Predicate</a> canonicalization reduces the number of patterns that need to be matched by other transforms. <a href="#a7245fe59c5c3470907144f999fbb258a">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">static <a href="/web-llvm/docs/api/classes/llvm/constant">Constant</a> *</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#afe2dc21e0303f087635f70178f4a17ea">AddOne</a> (Constant *C)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Add one to a <a href="/web-llvm/docs/api/classes/llvm/constant">Constant</a>. <a href="#afe2dc21e0303f087635f70178f4a17ea">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">static <a href="/web-llvm/docs/api/classes/llvm/constant">Constant</a> *</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a5c9e100d07432e392331760d46053089">SubOne</a> (Constant *C)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Subtract one from a <a href="/web-llvm/docs/api/classes/llvm/constant">Constant</a>. <a href="#a5c9e100d07432e392331760d46053089">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">static bool</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a4ffe5454cf09255ace0804d9c8044004">shouldAvoidAbsorbingNotIntoSelect</a> (const SelectInst &amp;SI)</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">static <a href="/web-llvm/docs/api/classes/llvm/constant">Constant</a> *</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#acf9cbfcb493b0042022c94230e9350e2">getSafeVectorConstantForBinop</a> (BinaryOperator::BinaryOps Opcode, Constant *In, bool IsRHSConstant)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Some binary operators require special handling to avoid poison and undefined behavior. <a href="#acf9cbfcb493b0042022c94230e9350e2">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

</table>

## Description {#details}

<p>The core instruction combiner logic.</p>


<p>This class provides both the logic to recursively visit instructions and combine them.</p>


<p>Definition at line 48 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/transforms/include/llvm/transforms/instcombine/instcombiner-h">InstCombiner.h</a>.</p>


<div class="doxySectionDef">

## Public Member Typedefs

### BuilderTy {#a19c4df37b96c2a73991556b696924584}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">using llvm::InstCombiner::BuilderTy =  IRBuilder&lt;TargetFolder, IRBuilderCallbackInserter&gt;</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>An <a href="/web-llvm/docs/api/classes/llvm/irbuilder">IRBuilder</a> that automatically inserts new instructions into the worklist.</p>

<p>Definition at line 60 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/transforms/include/llvm/transforms/instcombine/instcombiner-h">InstCombiner.h</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Public Constructors

### InstCombiner() {#af70e33de5e351fc22288a3130b0428b6}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">llvm::InstCombiner::InstCombiner (<a href="/web-llvm/docs/api/classes/llvm/instructionworklist">InstructionWorklist</a> &amp; Worklist, <a href="#a19c4df37b96c2a73991556b696924584">BuilderTy</a> &amp; Builder, bool MinimizeSize, <a href="/web-llvm/docs/api/classes/llvm/aaresults">AAResults</a> * AA, <a href="/web-llvm/docs/api/classes/llvm/assumptioncache">AssumptionCache</a> &amp; AC, <a href="/web-llvm/docs/api/classes/llvm/targetlibraryinfo">TargetLibraryInfo</a> &amp; TLI, <a href="/web-llvm/docs/api/classes/llvm/targettransforminfo">TargetTransformInfo</a> &amp; TTI, <a href="/web-llvm/docs/api/classes/llvm/dominatortree">DominatorTree</a> &amp; DT, <a href="/web-llvm/docs/api/classes/llvm/optimizationremarkemitter">OptimizationRemarkEmitter</a> &amp; ORE, <a href="/web-llvm/docs/api/classes/llvm/blockfrequencyinfo">BlockFrequencyInfo</a> * BFI, <a href="/web-llvm/docs/api/classes/llvm/branchprobabilityinfo">BranchProbabilityInfo</a> * BPI, <a href="/web-llvm/docs/api/classes/llvm/profilesummaryinfo">ProfileSummaryInfo</a> * PSI, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/datalayout">DataLayout</a> &amp; DL, <a href="/web-llvm/docs/api/classes/llvm/reversepostordertraversal">ReversePostOrderTraversal</a>&lt; <a href="/web-llvm/docs/api/classes/llvm/basicblock">BasicBlock</a> * &gt; &amp; RPOT)</td>
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



<p>Definition at line 101 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/transforms/include/llvm/transforms/instcombine/instcombiner-h">InstCombiner.h</a>.</p>


<p>References <a href="#a4764870a6b87dce34acb4e5eaef32e42">AA</a>, <a href="#ab63bb17a04c3e86b58219750716899a9">AC</a>, <a href="#a25e411550ff000d1660e2376e3ae2ef8">BFI</a>, <a href="#a7f74e84c9b2bc2441706161c2ed9cc5a">BPI</a>, <a href="#ae1d331bc844ecb92bdeb0b706ae04396">Builder</a>, <a href="#a888ebf4b0f794a1c13741d38f0c4aa61">DC</a>, <a href="#a878e8128a9a4e5626df91dcd91cba337">DL</a>, <a href="#ac881b40b83c0bd8934689bdc8c306cf5">DT</a>, <a href="#a8d57399452f30fb78195887945ae507c">MinimizeSize</a>, <a href="#aeae5f7d492700a5221d5252b72e8466a">ORE</a>, <a href="#ad2f83bae44783989a87e7200ae678c76">PSI</a>, <a href="#a8768d7bd3a905c9cd89c3738d4873a0d">RPOT</a>, <a href="#a067e49eb19f14e50f84cf4b4e7f6acde">SQ</a>, <a href="#a3ccb79ce550ca98c6f524c1c6bdd06a1">TLI</a>, <a href="/web-llvm/docs/api/files/lib/lib/analysis/basicaliasanalysis-cpp/#af6d5cafbdfc5313e65d990120021a3ec">true</a> and <a href="#a7b93340fbcab35a38a04bf49aa3113a0">Worklist</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/classes/llvm/instcombinerimpl/#a3192aaa795b73ba7009f98fdad625080">llvm::InstCombinerImpl::InstCombinerImpl</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Public Destructor

### \~InstCombiner() {#a239b9fd8ca2ce771713c69e4fca765af}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">virtual llvm::InstCombiner::~InstCombiner ()</td>
</tr>
</table>
</td>
<td class="doxyMemberLabelsRight">
<span class="doxyMemberLabels">
<span class="doxyMemberLabel virtual">virtual</span>
<span class="doxyMemberLabel default">default</span>
</span>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 114 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/transforms/include/llvm/transforms/instcombine/instcombiner-h">InstCombiner.h</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Public Member Functions

### addToWorklist() {#ab86d58ae73173328360a32cbbb0d5b14}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void llvm::InstCombiner::addToWorklist (<a href="/web-llvm/docs/api/classes/llvm/instruction">Instruction</a> * I)</td>
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



<p>Definition at line 332 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/transforms/include/llvm/transforms/instcombine/instcombiner-h">InstCombiner.h</a>.</p>


<p>References <a href="/web-llvm/docs/api/files/lib/lib/support/md5-cpp/#ac0eafdc9ee161b71e7af98af736952fd">I</a> and <a href="#a7b93340fbcab35a38a04bf49aa3113a0">Worklist</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/classes/llvm/instcombinerimpl/#ad6aa61c7462784d1c9641ee501486375">llvm::InstCombinerImpl::addDeadEdge</a>, <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/instcombine/instcombineandorxor-cpp/#a22b32bcfbb9aec8a8fcb9826f40a3955">foldIsPowerOf2</a>, <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/instcombine/instcombineandorxor-cpp/#a034d63ecfce76136f23c28e698d7a720">foldIsPowerOf2OrZero</a>, <a href="/web-llvm/docs/api/classes/llvm/instcombinerimpl/#af8c1d39848b445bea8e307b53f81c481">llvm::InstCombinerImpl::freelyInvertAllUsersOf</a>, <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/instcombine/instcombineshifts-cpp/#ab2d3d519ed327a47cba69f5523785d2d">getShiftedValue</a>, <a href="/web-llvm/docs/api/classes/llvm/instcombinerimpl/#a352cde174c12aa24afbb7e61c22853e2">llvm::InstCombinerImpl::handleUnreachableFrom</a>, <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/instcombine/instcombinecompares-cpp/#a67cafe6badc04395d797929d9d4e8efe">processUMulZExtIdiom</a>, <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/instcombine/instcombinevectorops-cpp/#a801d960feba2403acf8dbd07ee3f34b6">replaceExtractElements</a>, <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/instcombine/instcombinecompares-cpp/#a0aa7c68d8c3095ffc271ecceab16c86e">rewriteGEPAsOffset</a>, <a href="/web-llvm/docs/api/classes/llvm/x86ttiimpl/#afd63c73f7201b4ed318ed3a3c56b6cad">llvm::X86TTIImpl::simplifyDemandedVectorEltsIntrinsic</a> and <a href="/web-llvm/docs/api/classes/llvm/instcombinerimpl/#aea9ba5a362fb88bd97349a302133dd03">llvm::InstCombinerImpl::visitBranchInst</a>.</p>

</div>
</div>

### canFreelyInvertAllUsersOf() {#ab0cf90f56e055b09227ab0f84acc4083}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool llvm::InstCombiner::canFreelyInvertAllUsersOf (<a href="/web-llvm/docs/api/classes/llvm/instruction">Instruction</a> * V, <a href="/web-llvm/docs/api/classes/llvm/value">Value</a> * IgnoredUser)</td>
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

<p>Given i1 V, can every user of V be freely adapted if V is changed to !V ?</p>


<p>InstCombine's freelyInvertAllUsersOf() must be kept in sync with this fn. NOTE: for Instructions only!</p>


<p>See also: <a href="#a1f819cdc746560fd28977b1175030cff">isFreeToInvert()</a></p>


<p>Definition at line 244 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/transforms/include/llvm/transforms/instcombine/instcombiner-h">InstCombiner.h</a>.</p>


<p>References <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/silowercontrolflow-cpp/#a4868c5d81c5ccc98c47aeab6244346a0">assert</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#ac4fc845f5ed92de63cd4474f128f5fc5">llvm::cast</a>, <a href="/web-llvm/docs/api/files/lib/lib/support/md5-cpp/#ac0eafdc9ee161b71e7af98af736952fd">I</a>, <a href="/web-llvm/docs/api/namespaces/llvm/patternmatch/#ae28f9cbf5b5e3fbeb69d1414285c1760">llvm::PatternMatch::m_Not</a>, <a href="/web-llvm/docs/api/namespaces/llvm/patternmatch/#aaf522908fe903018eb9b087dd6e49296">llvm::PatternMatch::m_Value</a>, <a href="/web-llvm/docs/api/namespaces/llvm/patternmatch/#a25d956d9e0beadd47ce4bc255dfa811d">llvm::PatternMatch::match</a>, <a href="#a4ffe5454cf09255ace0804d9c8044004">shouldAvoidAbsorbingNotIntoSelect</a> and <a href="/web-llvm/docs/api/classes/llvm/value/#abf855b7cd63a0cd7f73759e396f280c9">llvm::Value::uses</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/instcombine/instcombineandorxor-cpp/#a4fda26317fcc1b226ecc5a9a28bf68fc">canFreelyInvert</a>, <a href="/web-llvm/docs/api/classes/llvm/instcombinerimpl/#a6f392d7a34855ef605496d0afcb913cd">llvm::InstCombinerImpl::canonicalizeICmpPredicate</a>, <a href="/web-llvm/docs/api/classes/llvm/instcombinerimpl/#a4e2dd07eceeed7496e6c3df4d364c91e">llvm::InstCombinerImpl::sinkNotIntoLogicalOp</a> and <a href="/web-llvm/docs/api/classes/llvm/instcombinerimpl/#a8d44c548f74b3d233a248672402b5dd1">llvm::InstCombinerImpl::sinkNotIntoOtherHandOfLogicalOp</a>.</p>

</div>
</div>

### computeBackEdges() {#ac17fa2d851e729e9c308df593b098fc1}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void InstCombiner::computeBackEdges ()</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Declaration at line 357 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/transforms/include/llvm/transforms/instcombine/instcombiner-h">InstCombiner.h</a>, definition at line 5496 of file <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/instcombine/instructioncombining-cpp">InstructionCombining.cpp</a>.</p>


<p>References <a href="#abca480cb3ed0ecf3fe3bde76bdf4b230">BackEdges</a>, <a href="#a577df1f2641fe6bf067c364d94154cf1">ComputedBackEdges</a>, <a href="/web-llvm/docs/api/classes/llvm/smallptrsetimpl/#af74676a3c7447be34bd2c1da76ec0c48">llvm::SmallPtrSetImpl&lt; PtrType &gt;::contains</a>, <a href="/web-llvm/docs/api/classes/llvm/smallptrsetimpl/#a9d834ae3da8c62c2b668dada51335eb0">llvm::SmallPtrSetImpl&lt; PtrType &gt;::insert</a>, <a href="#a8768d7bd3a905c9cd89c3738d4873a0d">RPOT</a> and <a href="/web-llvm/docs/api/namespaces/llvm/#a26e2a938b431eaa6eca2beaa96410c9d">llvm::successors</a>.</p>


<p>Referenced by <a href="#af5a8feb3d194df1e72e6a32cc746bc97">isBackEdge</a>.</p>

</div>
</div>

### computeKnownBits() {#ae099c6fa4a0b06306ece7dd372e8d02a}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void llvm::InstCombiner::computeKnownBits (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/value">Value</a> * V, <a href="/web-llvm/docs/api/structs/llvm/knownbits">KnownBits</a> &amp; Known, unsigned Depth, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/instruction">Instruction</a> * CxtI)</td>
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



<p>Definition at line 433 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/transforms/include/llvm/transforms/instcombine/instcombiner-h">InstCombiner.h</a>.</p>


<p>References <a href="/web-llvm/docs/api/namespaces/llvm/#ab2c2c51743fb4a1b17c59563909f3f24">llvm::computeKnownBits</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a1eb5609345b906d024fbf9e4bc1adc06afe578efb7ca235af77fb0eef7edcf639">llvm::Depth</a> and <a href="#a067e49eb19f14e50f84cf4b4e7f6acde">SQ</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/instcombine/instcombineloadstorealloca-cpp/#a4380ad0de0940297354df2effeb021ad">canReplaceGEPIdxWithZero</a>, <a href="/web-llvm/docs/api/classes/llvm/instcombinerimpl/#a52d249cc9856fb556e92d5a1b03e5e80">llvm::InstCombinerImpl::convertOrOfShiftsToFunnelShift</a>, <a href="/web-llvm/docs/api/classes/llvm/instcombinerimpl/#ac38a3c2794db0ecc70c9bb7106f1e1bf">llvm::InstCombinerImpl::foldAddWithConstant</a>, <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/instcombine/instcombinecalls-cpp/#abd2a207499b6fef021080fbe87fa61d6">foldCtpop</a>, <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/instcombine/instcombinecalls-cpp/#ac6169fee4cf2c33a0c3abb46628bfefc">foldCttzCtlz</a>, <a href="/web-llvm/docs/api/classes/llvm/instcombinerimpl/#afa5f2de80c23c28bd1a3320e8369aab2">llvm::InstCombinerImpl::foldICmpAndConstConst</a>, <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/instcombine/instcombinecompares-cpp/#a25119a0e5bcc1f71c61c4acc02e3ff2b">foldICmpAndXX</a>, <a href="/web-llvm/docs/api/classes/llvm/instcombinerimpl/#a36ef4128d8b08242e337bcbed0dce3c8">llvm::InstCombinerImpl::foldICmpBinOp</a>, <a href="/web-llvm/docs/api/classes/llvm/instcombinerimpl/#a9bbadd565d3ba2855a90a04101d8d4cf">llvm::InstCombinerImpl::foldICmpTruncConstant</a>, <a href="/web-llvm/docs/api/classes/llvm/instcombinerimpl/#a6fccc5a9bafccfbd5927bb72eb035635">llvm::InstCombinerImpl::foldICmpWithZero</a>, <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/instcombine/instcombinecasts-cpp/#aac5576a66149a9259706758d613ba555">isKnownExactCastIntToFP</a>, <a href="/web-llvm/docs/api/classes/llvm/instcombinerimpl/#a4bb2cbb88b57c9a126549efe2134d1cb">llvm::InstCombinerImpl::SimplifyDemandedUseBits</a>, <a href="/web-llvm/docs/api/classes/llvm/instcombinerimpl/#aa4100f52d21246ec944e97fe1b64b124">llvm::InstCombinerImpl::simplifyRangeCheck</a>, <a href="/web-llvm/docs/api/classes/llvm/instcombinerimpl/#a648710a93ceb0bbddf0a2ae7a8bb2ca5">llvm::InstCombinerImpl::visitAnd</a>, <a href="/web-llvm/docs/api/classes/llvm/instcombinerimpl/#afa2581e2e1ac6959cd02e28062a7c1d5">llvm::InstCombinerImpl::visitCallInst</a>, <a href="/web-llvm/docs/api/classes/llvm/instcombinerimpl/#a197424adbab353be4587e6dfaee445e3">llvm::InstCombinerImpl::visitLShr</a>, <a href="/web-llvm/docs/api/classes/llvm/instcombinerimpl/#a1e893463cbb4b5e2e3830b2e4c28cbdb">llvm::InstCombinerImpl::visitOr</a>, <a href="/web-llvm/docs/api/classes/llvm/instcombinerimpl/#af12904244ec179b265540ed1fb8c6615">llvm::InstCombinerImpl::visitSDiv</a> and <a href="/web-llvm/docs/api/classes/llvm/instcombinerimpl/#a91100900b6eb1ae18127f1e1f8f8a40e">llvm::InstCombinerImpl::visitSwitchInst</a>.</p>

</div>
</div>

### computeKnownBits() {#a6c1e1b56ee28b4d21a3950d48175e284}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">KnownBits llvm::InstCombiner::computeKnownBits (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/value">Value</a> * V, unsigned Depth, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/instruction">Instruction</a> * CxtI)</td>
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



<p>Definition at line 438 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/transforms/include/llvm/transforms/instcombine/instcombiner-h">InstCombiner.h</a>.</p>


<p>References <a href="/web-llvm/docs/api/namespaces/llvm/#ab2c2c51743fb4a1b17c59563909f3f24">llvm::computeKnownBits</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a1eb5609345b906d024fbf9e4bc1adc06afe578efb7ca235af77fb0eef7edcf639">llvm::Depth</a> and <a href="#a067e49eb19f14e50f84cf4b4e7f6acde">SQ</a>.</p>

</div>
</div>

### ComputeMaxSignificantBits() {#afe741651c79e1ff35939d1c04a3a191b}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">unsigned llvm::InstCombiner::ComputeMaxSignificantBits (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/value">Value</a> * Op, unsigned Depth=0, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/instruction">Instruction</a> * CxtI=nullptr)</td>
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



<p>Definition at line 460 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/transforms/include/llvm/transforms/instcombine/instcombiner-h">InstCombiner.h</a>.</p>


<p>References <a href="#ab63bb17a04c3e86b58219750716899a9">AC</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#ae95177e7337984f5bc961723ecf67169">llvm::ComputeMaxSignificantBits</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a1eb5609345b906d024fbf9e4bc1adc06afe578efb7ca235af77fb0eef7edcf639">llvm::Depth</a>, <a href="#a878e8128a9a4e5626df91dcd91cba337">DL</a> and <a href="#ac881b40b83c0bd8934689bdc8c306cf5">DT</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/instcombine/instcombinecompares-cpp/#aae87c326017fc14f5ba90a036e45438a">processUGT_ADDCST_ADD</a> and <a href="/web-llvm/docs/api/classes/llvm/instcombinerimpl/#a43a1d060dacb05eb645cf91ea86d7bd3">llvm::InstCombinerImpl::visitTrunc</a>.</p>

</div>
</div>

### ComputeNumSignBits() {#a879221accd38e1327b8dcf596650b031}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">unsigned llvm::InstCombiner::ComputeNumSignBits (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/value">Value</a> * Op, unsigned Depth=0, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/instruction">Instruction</a> * CxtI=nullptr)</td>
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



<p>Definition at line 455 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/transforms/include/llvm/transforms/instcombine/instcombiner-h">InstCombiner.h</a>.</p>


<p>References <a href="#ab63bb17a04c3e86b58219750716899a9">AC</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#ad46ed333b920b20e78d948610366254c">llvm::ComputeNumSignBits</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a1eb5609345b906d024fbf9e4bc1adc06afe578efb7ca235af77fb0eef7edcf639">llvm::Depth</a>, <a href="#a878e8128a9a4e5626df91dcd91cba337">DL</a> and <a href="#ac881b40b83c0bd8934689bdc8c306cf5">DT</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/instcombine/instcombinecasts-cpp/#aefd6331c5fd6ec51f6a9e5558f885f28">canEvaluateTruncated</a>, <a href="/web-llvm/docs/api/classes/llvm/instcombinerimpl/#a4bb2cbb88b57c9a126549efe2134d1cb">llvm::InstCombinerImpl::SimplifyDemandedUseBits</a>, <a href="/web-llvm/docs/api/classes/llvm/instcombinerimpl/#a0a89a6b25b8a92fb896a994a36b74241">llvm::InstCombinerImpl::visitAdd</a> and <a href="/web-llvm/docs/api/classes/llvm/instcombinerimpl/#a2a5120238e6845643a37d5a4675a5342">llvm::InstCombinerImpl::visitSExt</a>.</p>

</div>
</div>

### computeOverflowForSignedAdd() {#a5ab19cff71a6dcbd4d061468d868de48}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">OverflowResult llvm::InstCombiner::computeOverflowForSignedAdd (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/withcache">WithCache</a>&lt; <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/value">Value</a> * &gt; &amp; LHS, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/withcache">WithCache</a>&lt; <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/value">Value</a> * &gt; &amp; RHS, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/instruction">Instruction</a> * CxtI)</td>
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



<p>Definition at line 488 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/transforms/include/llvm/transforms/instcombine/instcombiner-h">InstCombiner.h</a>.</p>


<p>References <a href="/web-llvm/docs/api/namespaces/llvm/#aa7790033a75bbc8568fcf887ada7ae05">llvm::computeOverflowForSignedAdd</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/x86/x86partialreduction-cpp/#a9e1483f7215664a2315c53c3558d9a8d">LHS</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/x86/x86partialreduction-cpp/#a87b8bfbbe9d8f7146d7f20a5fb42efd0">RHS</a> and <a href="#a067e49eb19f14e50f84cf4b4e7f6acde">SQ</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/classes/llvm/instcombinerimpl/#aefea2d173494ecda5fae066b6b04eca4">llvm::InstCombinerImpl::computeOverflow</a>.</p>

</div>
</div>

### computeOverflowForSignedMul() {#acfd758f11fb745755ce05f4763dea3c4}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">OverflowResult llvm::InstCombiner::computeOverflowForSignedMul (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/value">Value</a> * LHS, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/value">Value</a> * RHS, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/instruction">Instruction</a> * CxtI)</td>
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



<p>Definition at line 473 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/transforms/include/llvm/transforms/instcombine/instcombiner-h">InstCombiner.h</a>.</p>


<p>References <a href="/web-llvm/docs/api/namespaces/llvm/#a874815cd838916d66cd1408438e0cb51">llvm::computeOverflowForSignedMul</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/x86/x86partialreduction-cpp/#a9e1483f7215664a2315c53c3558d9a8d">LHS</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/x86/x86partialreduction-cpp/#a87b8bfbbe9d8f7146d7f20a5fb42efd0">RHS</a> and <a href="#a067e49eb19f14e50f84cf4b4e7f6acde">SQ</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/classes/llvm/instcombinerimpl/#aefea2d173494ecda5fae066b6b04eca4">llvm::InstCombinerImpl::computeOverflow</a>.</p>

</div>
</div>

### computeOverflowForSignedSub() {#a0056e5666f4dff4b171f6817deb601c6}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">OverflowResult llvm::InstCombiner::computeOverflowForSignedSub (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/value">Value</a> * LHS, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/value">Value</a> * RHS, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/instruction">Instruction</a> * CxtI)</td>
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



<p>Definition at line 502 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/transforms/include/llvm/transforms/instcombine/instcombiner-h">InstCombiner.h</a>.</p>


<p>References <a href="/web-llvm/docs/api/namespaces/llvm/#a6b72ea7b10ac690e8f1bcdf144c7e5d4">llvm::computeOverflowForSignedSub</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/x86/x86partialreduction-cpp/#a9e1483f7215664a2315c53c3558d9a8d">LHS</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/x86/x86partialreduction-cpp/#a87b8bfbbe9d8f7146d7f20a5fb42efd0">RHS</a> and <a href="#a067e49eb19f14e50f84cf4b4e7f6acde">SQ</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/classes/llvm/instcombinerimpl/#aefea2d173494ecda5fae066b6b04eca4">llvm::InstCombinerImpl::computeOverflow</a>.</p>

</div>
</div>

### computeOverflowForUnsignedAdd() {#aeea35a035c67331d0d1383bf392b1d6e}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">OverflowResult llvm::InstCombiner::computeOverflowForUnsignedAdd (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/withcache">WithCache</a>&lt; <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/value">Value</a> * &gt; &amp; LHS, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/withcache">WithCache</a>&lt; <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/value">Value</a> * &gt; &amp; RHS, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/instruction">Instruction</a> * CxtI)</td>
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



<p>Definition at line 480 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/transforms/include/llvm/transforms/instcombine/instcombiner-h">InstCombiner.h</a>.</p>


<p>References <a href="/web-llvm/docs/api/namespaces/llvm/#ad7fabe65a8d4b9b26a17c87317461c58">llvm::computeOverflowForUnsignedAdd</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/x86/x86partialreduction-cpp/#a9e1483f7215664a2315c53c3558d9a8d">LHS</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/x86/x86partialreduction-cpp/#a87b8bfbbe9d8f7146d7f20a5fb42efd0">RHS</a> and <a href="#a067e49eb19f14e50f84cf4b4e7f6acde">SQ</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/classes/llvm/instcombinerimpl/#aefea2d173494ecda5fae066b6b04eca4">llvm::InstCombinerImpl::computeOverflow</a>.</p>

</div>
</div>

### computeOverflowForUnsignedMul() {#a20be54dc5cf0b5f4d1a53adee1215d96}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">OverflowResult llvm::InstCombiner::computeOverflowForUnsignedMul (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/value">Value</a> * LHS, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/value">Value</a> * RHS, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/instruction">Instruction</a> * CxtI, bool IsNSW=false)</td>
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



<p>Definition at line 465 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/transforms/include/llvm/transforms/instcombine/instcombiner-h">InstCombiner.h</a>.</p>


<p>References <a href="/web-llvm/docs/api/namespaces/llvm/#a62fdc50378ed0e117f3c4e829f9d68a8">llvm::computeOverflowForUnsignedMul</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/x86/x86partialreduction-cpp/#a9e1483f7215664a2315c53c3558d9a8d">LHS</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/x86/x86partialreduction-cpp/#a87b8bfbbe9d8f7146d7f20a5fb42efd0">RHS</a> and <a href="#a067e49eb19f14e50f84cf4b4e7f6acde">SQ</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/classes/llvm/instcombinerimpl/#aefea2d173494ecda5fae066b6b04eca4">llvm::InstCombinerImpl::computeOverflow</a>.</p>

</div>
</div>

### computeOverflowForUnsignedSub() {#a6e3d062a96f0592c80d7a2e829be2aa3}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">OverflowResult llvm::InstCombiner::computeOverflowForUnsignedSub (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/value">Value</a> * LHS, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/value">Value</a> * RHS, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/instruction">Instruction</a> * CxtI)</td>
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



<p>Definition at line 495 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/transforms/include/llvm/transforms/instcombine/instcombiner-h">InstCombiner.h</a>.</p>


<p>References <a href="/web-llvm/docs/api/namespaces/llvm/#abfdf10a69ac9839f2ae92515b969b77e">llvm::computeOverflowForUnsignedSub</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/x86/x86partialreduction-cpp/#a9e1483f7215664a2315c53c3558d9a8d">LHS</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/x86/x86partialreduction-cpp/#a87b8bfbbe9d8f7146d7f20a5fb42efd0">RHS</a> and <a href="#a067e49eb19f14e50f84cf4b4e7f6acde">SQ</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/classes/llvm/instcombinerimpl/#aefea2d173494ecda5fae066b6b04eca4">llvm::InstCombinerImpl::computeOverflow</a>.</p>

</div>
</div>

### eraseInstFromFunction() {#a190073d8a0e9a2eeb56f0cb96816d7ef}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">virtual Instruction * llvm::InstCombiner::eraseInstFromFunction (<a href="/web-llvm/docs/api/classes/llvm/instruction">Instruction</a> &amp; I)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p><a href="/web-llvm/docs/api/classes/llvm/combiner">Combiner</a> aware instruction erasure.</p>


<p>When dealing with an instruction that has side effects or produces a void value, we can't rely on DCE to delete the instruction. Instead, visit methods should return the value returned by this function.</p>


<p>Definition at line 431 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/transforms/include/llvm/transforms/instcombine/instcombiner-h">InstCombiner.h</a>.</p>


<p>Reference <a href="/web-llvm/docs/api/files/lib/lib/support/md5-cpp/#ac0eafdc9ee161b71e7af98af736952fd">I</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64targettransforminfo-cpp/#a7a1fca604182e2700a44c3d0a707a953">instCombineDMB</a>, <a href="/web-llvm/docs/api/classes/llvm/armttiimpl/#a5c10997d5aed59d126fc726249d8b561">llvm::ARMTTIImpl::instCombineIntrinsic</a>, <a href="/web-llvm/docs/api/classes/llvm/gcnttiimpl/#ae3d1835a72f8f0ba85ace9e2c0fbfc96">llvm::GCNTTIImpl::instCombineIntrinsic</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64targettransforminfo-cpp/#a5f64e951a3840e09ae4d21552754ec13">instCombineST1ScatterIndex</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64targettransforminfo-cpp/#acbcb2b20c6532c73d9c0c74e9e2c9c13">instCombineSVENoActiveReplace</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64targettransforminfo-cpp/#a54b85817791d12ddcec17af86ffb1487">instCombineSVENoActiveUnaryErase</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64targettransforminfo-cpp/#a73170211689546daae2d8b0676c6d676">instCombineSVENoActiveZero</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64targettransforminfo-cpp/#a6139b54e783a57871c92c1ac67e4be6e">instCombineSVEST1</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/amdgpuinstcombineintrinsic-cpp/#a8a43e48d75ff4289fc2674097dab5d50">modifyIntrinsicCall</a> and <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/x86/x86instcombineintrinsic-cpp/#a708996b12b1b5e6ac2555880bdaeda64">simplifyX86MaskedStore</a>.</p>

</div>
</div>

### getAssumptionCache() {#ae2eddfa57a32ec610ce9685720d591b7}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">AssumptionCache &amp; llvm::InstCombiner::getAssumptionCache ()</td>
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



<p>Definition at line 334 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/transforms/include/llvm/transforms/instcombine/instcombiner-h">InstCombiner.h</a>.</p>


<p>Reference <a href="#ab63bb17a04c3e86b58219750716899a9">AC</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/classes/llvm/armttiimpl/#a5c10997d5aed59d126fc726249d8b561">llvm::ARMTTIImpl::instCombineIntrinsic</a>, <a href="/web-llvm/docs/api/classes/llvm/ppcttiimpl/#a04dad23556e58f793c9a508a1a2d9aa5">llvm::PPCTTIImpl::instCombineIntrinsic</a> and <a href="/web-llvm/docs/api/classes/llvm/instcombinerimpl/#afa2581e2e1ac6959cd02e28062a7c1d5">llvm::InstCombinerImpl::visitCallInst</a>.</p>

</div>
</div>

### getBlockFrequencyInfo() {#a441e8056feed591b0e0fd1b2a6ac81c0}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">BlockFrequencyInfo * llvm::InstCombiner::getBlockFrequencyInfo ()</td>
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



<p>Definition at line 342 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/transforms/include/llvm/transforms/instcombine/instcombiner-h">InstCombiner.h</a>.</p>


<p>Reference <a href="#a25e411550ff000d1660e2376e3ae2ef8">BFI</a>.</p>

</div>
</div>

### getDataLayout() {#a16262e69f9cdf5d2c9d5623c3b06af43}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">const DataLayout &amp; llvm::InstCombiner::getDataLayout ()</td>
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



<p>Definition at line 337 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/transforms/include/llvm/transforms/instcombine/instcombiner-h">InstCombiner.h</a>.</p>


<p>Reference <a href="#a878e8128a9a4e5626df91dcd91cba337">DL</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/instcombine/instcombinecasts-cpp/#aefd6331c5fd6ec51f6a9e5558f885f28">canEvaluateTruncated</a>, <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/instcombine/instructioncombining-cpp/#a856d46e90d7159a88c175ceff667f40c">canonicalizeGEPOfConstGEPI8</a>, <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/instcombine/instcombineloadstorealloca-cpp/#a4380ad0de0940297354df2effeb021ad">canReplaceGEPIdxWithZero</a>, <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/instcombine/instcombineloadstorealloca-cpp/#a20fc81c83f56078eb06e2db21611f58f">combineLoadToOperationType</a>, <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/instcombine/instcombinecasts-cpp/#aa1c33c4fbbe149ca5deb130bca410ef2">foldVecExtTruncToExtElt</a>, <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/instcombine/instcombinecasts-cpp/#aee3e98b16f1c8d8d8b30b9a459a6a602">foldVecTruncToExtElt</a>, <a href="/web-llvm/docs/api/classes/llvm/armttiimpl/#a5c10997d5aed59d126fc726249d8b561">llvm::ARMTTIImpl::instCombineIntrinsic</a>, <a href="/web-llvm/docs/api/classes/llvm/ppcttiimpl/#a04dad23556e58f793c9a508a1a2d9aa5">llvm::PPCTTIImpl::instCombineIntrinsic</a>, <a href="/web-llvm/docs/api/classes/llvm/x86ttiimpl/#a47cb7185e35282131b486036ff7c45df">llvm::X86TTIImpl::instCombineIntrinsic</a>, <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/instcombine/instcombineloadstorealloca-cpp/#ad32864e83b171a9c8c05bb7da05ceffd">likeBitCastFromVector</a>, <a href="/web-llvm/docs/api/classes/llvm/negator/#a2abe5e7f029b63c7b1bd29ac231ef7fa">llvm::Negator::Negate</a>, <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/instcombine/instcombinecasts-cpp/#a8f948dd0c375dfeb4cdf99bc33905e66">optimizeIntegerToVectorInsertions</a>, <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/instcombine/instcombinecasts-cpp/#a75e6b6bf03adf614aaf100a9afdcd612">optimizeVectorResizeWithIntegerBitCasts</a>, <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/instcombine/instcombineloadstorealloca-cpp/#a25ea6e038ccdef52ab01b0ee3da9ee52">simplifyAllocaArraySize</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/amdgpuinstcombineintrinsic-cpp/#aae1a4eb9b437e719a333c79f74c9a1b2">simplifyAMDGCNMemoryIntrinsicDemanded</a>, <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/instcombine/instructioncombining-cpp/#a41c00c458f7416c93927bc2f332b3898">simplifyAssocCastAssoc</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/x86/x86instcombineintrinsic-cpp/#a06d646994f54f30c64dcb09a8c6d91f3">simplifyX86MaskedLoad</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/x86/x86instcombineintrinsic-cpp/#a708996b12b1b5e6ac2555880bdaeda64">simplifyX86MaskedStore</a>, <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/instcombine/instcombineloadstorealloca-cpp/#aa0014a4c2da32289f871b8d5a1aa538b">unpackLoadToAggregate</a> and <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/instcombine/instcombineloadstorealloca-cpp/#acce887569ed105b612c33053a3264608">unpackStoreToAggregate</a>.</p>

</div>
</div>

### getDominatorTree() {#a209240824927e66a0caa50636623e79a}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">DominatorTree &amp; llvm::InstCombiner::getDominatorTree ()</td>
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



<p>Definition at line 336 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/transforms/include/llvm/transforms/instcombine/instcombiner-h">InstCombiner.h</a>.</p>


<p>Reference <a href="#ac881b40b83c0bd8934689bdc8c306cf5">DT</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/classes/llvm/armttiimpl/#a5c10997d5aed59d126fc726249d8b561">llvm::ARMTTIImpl::instCombineIntrinsic</a>, <a href="/web-llvm/docs/api/classes/llvm/ppcttiimpl/#a04dad23556e58f793c9a508a1a2d9aa5">llvm::PPCTTIImpl::instCombineIntrinsic</a>, <a href="/web-llvm/docs/api/classes/llvm/negator/#a2abe5e7f029b63c7b1bd29ac231ef7fa">llvm::Negator::Negate</a> and <a href="/web-llvm/docs/api/classes/llvm/instcombinerimpl/#afa2581e2e1ac6959cd02e28062a7c1d5">llvm::InstCombinerImpl::visitCallInst</a>.</p>

</div>
</div>

### getFreelyInverted() {#af11b32adde24fea55878e66dd7139362}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">Value * llvm::InstCombiner::getFreelyInverted (<a href="/web-llvm/docs/api/classes/llvm/value">Value</a> * V, bool WillInvertAllUses, <a href="#a19c4df37b96c2a73991556b696924584">BuilderTy</a> * Builder, bool &amp; DoesConsume)</td>
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



<p>Definition at line 209 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/transforms/include/llvm/transforms/instcombine/instcombiner-h">InstCombiner.h</a>.</p>


<p>References <a href="#ae1d331bc844ecb92bdeb0b706ae04396">Builder</a> and <a href="#ab98cb2aaf6e757aac9c471f85f113a50">getFreelyInvertedImpl</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/instcombine/instcombinecompares-cpp/#a25119a0e5bcc1f71c61c4acc02e3ff2b">foldICmpAndXX</a>, <a href="/web-llvm/docs/api/classes/llvm/instcombinerimpl/#afbfe964338488078570fe14e7deb0551">llvm::InstCombinerImpl::foldICmpBitCast</a>, <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/instcombine/instcombinecompares-cpp/#afb20557855b41f2b32ebd166b4d4b10f">foldICmpOrXX</a>, <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/instcombine/instcombinecompares-cpp/#a566049e9c903d4e0067b8557d49c7d62">foldICmpWithLowBitMaskedVal</a>, <a href="#ab1dfd539be512820814cce9f06adb250">getFreelyInverted</a>, <a href="#a1f819cdc746560fd28977b1175030cff">isFreeToInvert</a>, <a href="/web-llvm/docs/api/classes/llvm/instcombinerimpl/#aa4cf868b89270f2f699fdee46cb572a4">llvm::InstCombinerImpl::tryFoldInstWithCtpopWithNot</a>, <a href="/web-llvm/docs/api/classes/llvm/instcombinerimpl/#a0a89a6b25b8a92fb896a994a36b74241">llvm::InstCombinerImpl::visitAdd</a>, <a href="/web-llvm/docs/api/classes/llvm/instcombinerimpl/#a648710a93ceb0bbddf0a2ae7a8bb2ca5">llvm::InstCombinerImpl::visitAnd</a>, <a href="/web-llvm/docs/api/classes/llvm/instcombinerimpl/#afa2581e2e1ac6959cd02e28062a7c1d5">llvm::InstCombinerImpl::visitCallInst</a>, <a href="/web-llvm/docs/api/classes/llvm/instcombinerimpl/#ae31c50e938b95587c87aed0f133b1346">llvm::InstCombinerImpl::visitICmpInst</a> and <a href="/web-llvm/docs/api/classes/llvm/instcombinerimpl/#a606601489498c1ba41f25e77eb2dd0cf">llvm::InstCombinerImpl::visitSub</a>.</p>

</div>
</div>

### getFreelyInverted() {#ab1dfd539be512820814cce9f06adb250}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">Value * llvm::InstCombiner::getFreelyInverted (<a href="/web-llvm/docs/api/classes/llvm/value">Value</a> * V, bool WillInvertAllUses, <a href="#a19c4df37b96c2a73991556b696924584">BuilderTy</a> * Builder)</td>
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



<p>Definition at line 216 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/transforms/include/llvm/transforms/instcombine/instcombiner-h">InstCombiner.h</a>.</p>


<p>References <a href="#ae1d331bc844ecb92bdeb0b706ae04396">Builder</a> and <a href="#af11b32adde24fea55878e66dd7139362">getFreelyInverted</a>.</p>

</div>
</div>

### getFreelyInvertedImpl() {#ab98cb2aaf6e757aac9c471f85f113a50}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">Value * InstCombiner::getFreelyInvertedImpl (<a href="/web-llvm/docs/api/classes/llvm/value">Value</a> * V, bool WillInvertAllUses, <a href="#a19c4df37b96c2a73991556b696924584">BuilderTy</a> * Builder, bool &amp; DoesConsume, unsigned Depth)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Return nonnull value if V is free to invert under the condition of WillInvertAllUses.</p>


<p>If Builder is nonnull, it will return a simplified ~V. If Builder is null, it will return an arbitrary nonnull value (not dereferenceable). If the inversion will consume instructions, <span class="doxyComputerOutput">DoesConsume</span> will be set to true. Otherwise it will be false.</p>


<p>Declaration at line 205 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/transforms/include/llvm/transforms/instcombine/instcombiner-h">InstCombiner.h</a>, definition at line 2573 of file <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/instcombine/instructioncombining-cpp">InstructionCombining.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/files/lib/lib/ir/builtingcs-cpp/#a2e38c85003a042421cde1647632d0b72">A</a>, <a href="/web-llvm/docs/api/classes/llvm/phinode/#a089cccb6f231efee72abc76d0f9c695f">llvm::PHINode::addIncoming</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/silowercontrolflow-cpp/#a4868c5d81c5ccc98c47aeab6244346a0">assert</a>, <a href="/web-llvm/docs/api/files/lib/lib/ir/builtingcs-cpp/#ae76959fe811ba090de4cba69ac00f1da">B</a>, <a href="#ae1d331bc844ecb92bdeb0b706ae04396">Builder</a>, <a href="/web-llvm/docs/api/namespaces/llvm/callingconv/#ac6aa1387c4375260e2468eb5a77fdb4cafd841a49aec1539bc88abc8ff9e170fb">llvm::CallingConv::C</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#ac4fc845f5ed92de63cd4474f128f5fc5">llvm::cast</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/riscv/riscvredundantcopyelimination-cpp/#a193847098793cdbab306803186676899">Cond</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a1eb5609345b906d024fbf9e4bc1adc06afe578efb7ca235af77fb0eef7edcf639">llvm::Depth</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a22eeee01734061ac1b31ccd994c49eef">llvm::dyn_cast</a>, <a href="/web-llvm/docs/api/classes/llvm/smallvectorimpl/#a396fcfee6914c76974b73c3d203da6a5">llvm::SmallVectorImpl&lt; T &gt;::emplace_back</a>, <a href="#ab98cb2aaf6e757aac9c471f85f113a50">getFreelyInvertedImpl</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a0434306df3aa5ec48fcf19d0958d7c01">llvm::getInverseMinMaxIntrinsic</a>, <a href="/web-llvm/docs/api/classes/llvm/constantexpr/#a5b43a866f0fca605556f0f69f70c522a">llvm::ConstantExpr::getNot</a>, <a href="/web-llvm/docs/api/files/lib/lib/support/md5-cpp/#ac0eafdc9ee161b71e7af98af736952fd">I</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/nvptx/nvvmintrrange-cpp/#ac5804672fc0850438d63caec770647f8">II</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/powerpc/ppcisellowering-cpp/#a5e8a1ef711294cc52d6e2c41279f4c0f">IsSelect</a>, <a href="/web-llvm/docs/api/namespaces/llvm/patternmatch/#a062ccd76a126632721e9aa09775d6c0e">llvm::PatternMatch::m_Add</a>, <a href="/web-llvm/docs/api/namespaces/llvm/patternmatch/#a014d851989a66ce781c4f89dfffb26b5">llvm::PatternMatch::m_And</a>, <a href="/web-llvm/docs/api/namespaces/llvm/patternmatch/#a0c94f3ca4234f78cf22840e79087f3f2">llvm::PatternMatch::m_AShr</a>, <a href="/web-llvm/docs/api/namespaces/llvm/patternmatch/#a5f6c38f6f64c2118341c829f97e26396">llvm::PatternMatch::m_ImmConstant</a>, <a href="/web-llvm/docs/api/namespaces/llvm/patternmatch/#acf8c16eed89e5ee1a10b6dfc08a33b3a">llvm::PatternMatch::m_LogicalAnd</a>, <a href="/web-llvm/docs/api/namespaces/llvm/patternmatch/#a5cce7a41c7581ff15a23ab90eb3b403a">llvm::PatternMatch::m_LogicalOr</a>, <a href="/web-llvm/docs/api/namespaces/llvm/patternmatch/#ad1e2bbf1a8ae559791b42b649d06bbd0">llvm::PatternMatch::m_MaxOrMin</a>, <a href="/web-llvm/docs/api/namespaces/llvm/patternmatch/#ae28f9cbf5b5e3fbeb69d1414285c1760">llvm::PatternMatch::m_Not</a>, <a href="/web-llvm/docs/api/namespaces/llvm/patternmatch/#ae44af1eeb2e5f7a1973a4ab78963a503">llvm::PatternMatch::m_Or</a>, <a href="/web-llvm/docs/api/namespaces/llvm/patternmatch/#a3ccd94f6a7507492b47c7351e3fb78c6">llvm::PatternMatch::m_Select</a>, <a href="/web-llvm/docs/api/namespaces/llvm/patternmatch/#a9ffe83e2db4b833b819ee721595c04dc">llvm::PatternMatch::m_SExtLike</a>, <a href="/web-llvm/docs/api/namespaces/llvm/patternmatch/#af5c293ba602295963ee06dd6f22e6335">llvm::PatternMatch::m_Sub</a>, <a href="/web-llvm/docs/api/namespaces/llvm/patternmatch/#a1b8442c10c9ed6e0e07160b54541450e">llvm::PatternMatch::m_Trunc</a>, <a href="/web-llvm/docs/api/namespaces/llvm/patternmatch/#aaf522908fe903018eb9b087dd6e49296">llvm::PatternMatch::m_Value</a>, <a href="/web-llvm/docs/api/namespaces/llvm/patternmatch/#a1cacb72e897c55bdfd5c726d13d69af1">llvm::PatternMatch::m_Xor</a>, <a href="/web-llvm/docs/api/namespaces/llvm/patternmatch/#a25d956d9e0beadd47ce4bc255dfa811d">llvm::PatternMatch::match</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a67b491833e9e37c0ff08f1d4cd1bd4f4">llvm::MaxAnalysisRecursionDepth</a> and <a href="#a4ffe5454cf09255ace0804d9c8044004">shouldAvoidAbsorbingNotIntoSelect</a>.</p>


<p>Referenced by <a href="#af11b32adde24fea55878e66dd7139362">getFreelyInverted</a> and <a href="#ab98cb2aaf6e757aac9c471f85f113a50">getFreelyInvertedImpl</a>.</p>

</div>
</div>

### getOptimizationRemarkEmitter() {#ad266f62eb13926ec63289681c04564fb}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">OptimizationRemarkEmitter &amp; llvm::InstCombiner::getOptimizationRemarkEmitter ()</td>
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



<p>Definition at line 339 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/transforms/include/llvm/transforms/instcombine/instcombiner-h">InstCombiner.h</a>.</p>


<p>Reference <a href="#aeae5f7d492700a5221d5252b72e8466a">ORE</a>.</p>

</div>
</div>

### getProfileSummaryInfo() {#ad08bc4ef198e2c99b48b26cdd7c118b0}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">ProfileSummaryInfo * llvm::InstCombiner::getProfileSummaryInfo ()</td>
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



<p>Definition at line 343 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/transforms/include/llvm/transforms/instcombine/instcombiner-h">InstCombiner.h</a>.</p>


<p>Reference <a href="#ad2f83bae44783989a87e7200ae678c76">PSI</a>.</p>

</div>
</div>

### getSimplifyQuery() {#af56f7a148b00922368e55ab9c4948724}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">const SimplifyQuery &amp; llvm::InstCombiner::getSimplifyQuery ()</td>
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



<p>Definition at line 338 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/transforms/include/llvm/transforms/instcombine/instcombiner-h">InstCombiner.h</a>.</p>


<p>Reference <a href="#a067e49eb19f14e50f84cf4b4e7f6acde">SQ</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/classes/llvm/gcnttiimpl/#ae5be25044bcd47e6c80f68c90159891f">llvm::GCNTTIImpl::canSimplifyLegacyMulToMul</a>, <a href="/web-llvm/docs/api/classes/llvm/instcombinerimpl/#a17e63ceed2274abf926d0a1b99cded18">llvm::InstCombinerImpl::computeKnownFPClass</a>, <a href="/web-llvm/docs/api/classes/llvm/instcombinerimpl/#aa67f7a0760efe078730620092a23a7fb">llvm::InstCombinerImpl::computeKnownFPClass</a>, <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/instcombine/instcombinecalls-cpp/#abd2a207499b6fef021080fbe87fa61d6">foldCtpop</a>, <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/instcombine/instcombinecalls-cpp/#ac6169fee4cf2c33a0c3abb46628bfefc">foldCttzCtlz</a>, <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/instcombine/instcombinecompares-cpp/#a48239fe2dd570dc10b58a6a89ce6dd72">foldFCmpFSubIntoFCmp</a>, <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/instcombine/instcombinecasts-cpp/#a568e85197421e091a259bf80e19c6765">foldFPtoI</a>, <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/instcombine/instcombinecompares-cpp/#a25119a0e5bcc1f71c61c4acc02e3ff2b">foldICmpAndXX</a>, <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/instcombine/instcombineselect-cpp/#a917f93b85c9b8cfe9ad68ba6d49966ba">foldSelectBinOpIdentity</a>, <a href="/web-llvm/docs/api/classes/llvm/instcombinerimpl/#a3b73df3a995af9ca26c9d024c957c45a">llvm::InstCombinerImpl::foldSelectShuffle</a>, <a href="/web-llvm/docs/api/classes/llvm/gcnttiimpl/#ae3d1835a72f8f0ba85ace9e2c0fbfc96">llvm::GCNTTIImpl::instCombineIntrinsic</a>, <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/instcombine/instcombineandorxor-cpp/#a2a50775521fbb289313bb39964dabae3">simplifyAndOrWithOpReplaced</a>, <a href="/web-llvm/docs/api/classes/llvm/instcombinerimpl/#afa2581e2e1ac6959cd02e28062a7c1d5">llvm::InstCombinerImpl::visitCallInst</a>, <a href="/web-llvm/docs/api/classes/llvm/instcombinerimpl/#a86b0437dceb8e39c8185dc7def325011">llvm::InstCombinerImpl::visitFCmpInst</a>, <a href="/web-llvm/docs/api/classes/llvm/instcombinerimpl/#af616ac59efde7c61f6e8ff8bd80d2027">llvm::InstCombinerImpl::visitFNeg</a>, <a href="/web-llvm/docs/api/classes/llvm/instcombinerimpl/#afa72f4f7fc2ee2bf6cd3b64bd07c37e8">llvm::InstCombinerImpl::visitFSub</a> and <a href="/web-llvm/docs/api/classes/llvm/instcombinerimpl/#a752efe4724ac3a97d07ee81d5f779c92">llvm::InstCombinerImpl::visitPHINode</a>.</p>

</div>
</div>

### getTargetLibraryInfo() {#a3cf623e18c507f6a12ba24ee04320625}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">TargetLibraryInfo &amp; llvm::InstCombiner::getTargetLibraryInfo ()</td>
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



<p>Definition at line 335 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/transforms/include/llvm/transforms/instcombine/instcombiner-h">InstCombiner.h</a>.</p>


<p>Reference <a href="#a3ccb79ce550ca98c6f524c1c6bdd06a1">TLI</a>.</p>

</div>
</div>

### InsertNewInstBefore() {#a46f1e493b5d0822af6344aa294f93fdb}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">Instruction * llvm::InstCombiner::InsertNewInstBefore (<a href="/web-llvm/docs/api/classes/llvm/instruction">Instruction</a> * New, <a href="/web-llvm/docs/api/classes/llvm/basicblock/#a98c0a84a5dfa8bce341c829709f171e5">BasicBlock::iterator</a> Old)</td>
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

<p>Inserts an instruction <span class="doxyComputerOutput">New</span> before instruction <span class="doxyComputerOutput">Old</span>.</p>


<p>Also adds the new instruction to the worklist and returns <span class="doxyComputerOutput">New</span> so that it is suitable for use as the return from the visitation patterns.</p>


<p>Definition at line 368 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/transforms/include/llvm/transforms/instcombine/instcombiner-h">InstCombiner.h</a>.</p>


<p>References <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/silowercontrolflow-cpp/#a4868c5d81c5ccc98c47aeab6244346a0">assert</a> and <a href="#a7b93340fbcab35a38a04bf49aa3113a0">Worklist</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/classes/llvm/instcombinerimpl/#aab1473644ffe7926032a4e01ed4bad78">llvm::InstCombinerImpl::foldIntegerTypedPHI</a>, <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/instcombine/instructioncombining-cpp/#a7b9a62f04a493cc8b8dadc64100578f8">foldOperationIntoSelectOperand</a>, <a href="/web-llvm/docs/api/classes/llvm/instcombinerimpl/#a2fc50d227d302eb98914f04bcc6634e1">llvm::InstCombinerImpl::foldOpIntoPhi</a>, <a href="/web-llvm/docs/api/classes/llvm/instcombinerimpl/#a4df124d92129ffa8748086388a420b73">llvm::InstCombinerImpl::foldPHIArgBinOpIntoPHI</a>, <a href="/web-llvm/docs/api/classes/llvm/instcombinerimpl/#af4dbcb044eda11161781dfbf3f007f04">llvm::InstCombinerImpl::foldPHIArgExtractValueInstructionIntoPHI</a>, <a href="/web-llvm/docs/api/classes/llvm/instcombinerimpl/#acc9feb478a72bb822133b6eec00bef9f">llvm::InstCombinerImpl::foldPHIArgGEPIntoPHI</a>, <a href="/web-llvm/docs/api/classes/llvm/instcombinerimpl/#a29028fb86efd0ff0ea01f243f47684fc">llvm::InstCombinerImpl::foldPHIArgInsertValueInstructionIntoPHI</a>, <a href="/web-llvm/docs/api/classes/llvm/instcombinerimpl/#aa8a186c50cdf60ac11ae1d0b884d468d">llvm::InstCombinerImpl::foldPHIArgLoadIntoPHI</a>, <a href="/web-llvm/docs/api/classes/llvm/instcombinerimpl/#a7a3e32edb65b5b1c216d4454f14df21c">llvm::InstCombinerImpl::foldPHIArgOpIntoPHI</a>, <a href="/web-llvm/docs/api/classes/llvm/instcombinerimpl/#a84318f31145b081677697de64401238a">llvm::InstCombinerImpl::foldPHIArgZextsIntoPHI</a>, <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/instcombine/instcombineselect-cpp/#a550ee33b5be6c859c443739649308721">foldSelectZeroOrMul</a>, <a href="#a7ce29ca36c91b8c790b0f8b2560c3033">InsertNewInstWith</a>, <a href="/web-llvm/docs/api/classes/llvm/instcombinerimpl/#a9d9df487d54cc5567b4e0b1c8e0120a8">llvm::InstCombinerImpl::mergeStoreIntoSuccessor</a> and <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/instcombine/instcombineloadstorealloca-cpp/#a23239d94380595765d9caf8bae661d7a">replaceGEPIdxWithZero</a>.</p>

</div>
</div>

### InsertNewInstWith() {#a7ce29ca36c91b8c790b0f8b2560c3033}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">Instruction * llvm::InstCombiner::InsertNewInstWith (<a href="/web-llvm/docs/api/classes/llvm/instruction">Instruction</a> * New, <a href="/web-llvm/docs/api/classes/llvm/basicblock/#a98c0a84a5dfa8bce341c829709f171e5">BasicBlock::iterator</a> Old)</td>
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

<p>Same as InsertNewInstBefore, but also sets the debug loc.</p>

<p>Definition at line 377 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/transforms/include/llvm/transforms/instcombine/instcombiner-h">InstCombiner.h</a>.</p>


<p>Reference <a href="#a46f1e493b5d0822af6344aa294f93fdb">InsertNewInstBefore</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/classes/llvm/instcombinerimpl/#ab464550d233a70bf18d772d204549342">llvm::InstCombinerImpl::CreateNonTerminatorUnreachable</a>, <a href="/web-llvm/docs/api/classes/llvm/instcombinerimpl/#ab05ba39ce6e678149dabd939c9ad4c3e">llvm::InstCombinerImpl::EvaluateInDifferentType</a>, <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/instcombine/instcombineshifts-cpp/#ab2d3d519ed327a47cba69f5523785d2d">getShiftedValue</a>, <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/instcombine/instcombinevectorops-cpp/#a801d960feba2403acf8dbd07ee3f34b6">replaceExtractElements</a>, <a href="/web-llvm/docs/api/classes/llvm/instcombinerimpl/#a225d5b1dcc0015e743f1dbbf348a9c36">llvm::InstCombinerImpl::SimplifyAssociativeOrCommutative</a>, <a href="/web-llvm/docs/api/classes/llvm/instcombinerimpl/#a4bb2cbb88b57c9a126549efe2134d1cb">llvm::InstCombinerImpl::SimplifyDemandedUseBits</a>, <a href="/web-llvm/docs/api/classes/llvm/instcombinerimpl/#a37cce7aa1875173688e5971c5d6fa9e0">llvm::InstCombinerImpl::SimplifyDemandedVectorElts</a> and <a href="/web-llvm/docs/api/classes/llvm/instcombinerimpl/#a93a6fd2ea0b1d80347d4d5eff6462428">llvm::InstCombinerImpl::simplifyShrShlDemandedBits</a>.</p>

</div>
</div>

### isBackEdge() {#af5a8feb3d194df1e72e6a32cc746bc97}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool llvm::InstCombiner::isBackEdge (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/basicblock">BasicBlock</a> * From, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/basicblock">BasicBlock</a> * To)</td>
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



<p>Definition at line 358 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/transforms/include/llvm/transforms/instcombine/instcombiner-h">InstCombiner.h</a>.</p>


<p>References <a href="#abca480cb3ed0ecf3fe3bde76bdf4b230">BackEdges</a>, <a href="#ac17fa2d851e729e9c308df593b098fc1">computeBackEdges</a> and <a href="#a577df1f2641fe6bf067c364d94154cf1">ComputedBackEdges</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/classes/llvm/instcombinerimpl/#a2fc50d227d302eb98914f04bcc6634e1">llvm::InstCombinerImpl::foldOpIntoPhi</a>.</p>

</div>
</div>

### isFreeToInvert() {#a1f819cdc746560fd28977b1175030cff}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool llvm::InstCombiner::isFreeToInvert (<a href="/web-llvm/docs/api/classes/llvm/value">Value</a> * V, bool WillInvertAllUses, bool &amp; DoesConsume)</td>
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

<p>Return true if the specified value is free to invert (apply ~ to).</p>


<p>This happens in cases where the ~ can be eliminated. If WillInvertAllUses is true, work under the assumption that the caller intends to remove all uses of V and only keep uses of ~V.</p>


<p>See also: <a href="#ab0cf90f56e055b09227ab0f84acc4083">canFreelyInvertAllUsersOf()</a></p>


<p>Definition at line 228 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/transforms/include/llvm/transforms/instcombine/instcombiner-h">InstCombiner.h</a>.</p>


<p>Reference <a href="#af11b32adde24fea55878e66dd7139362">getFreelyInverted</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/instcombine/instcombineandorxor-cpp/#a4fda26317fcc1b226ecc5a9a28bf68fc">canFreelyInvert</a>, <a href="#a18727b52ba4b34ed267df9b3cfa6c407">isFreeToInvert</a>, <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/instcombine/instcombineandorxor-cpp/#a2d3ce43f7795a8f4f6925bffbcc90279">matchDeMorgansLaws</a>, <a href="/web-llvm/docs/api/classes/llvm/instcombinerimpl/#aa4cf868b89270f2f699fdee46cb572a4">llvm::InstCombinerImpl::tryFoldInstWithCtpopWithNot</a>, <a href="/web-llvm/docs/api/classes/llvm/instcombinerimpl/#a0a89a6b25b8a92fb896a994a36b74241">llvm::InstCombinerImpl::visitAdd</a>, <a href="/web-llvm/docs/api/classes/llvm/instcombinerimpl/#afa2581e2e1ac6959cd02e28062a7c1d5">llvm::InstCombinerImpl::visitCallInst</a>, <a href="/web-llvm/docs/api/classes/llvm/instcombinerimpl/#ae31c50e938b95587c87aed0f133b1346">llvm::InstCombinerImpl::visitICmpInst</a> and <a href="/web-llvm/docs/api/classes/llvm/instcombinerimpl/#a606601489498c1ba41f25e77eb2dd0cf">llvm::InstCombinerImpl::visitSub</a>.</p>

</div>
</div>

### isFreeToInvert() {#a18727b52ba4b34ed267df9b3cfa6c407}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool llvm::InstCombiner::isFreeToInvert (<a href="/web-llvm/docs/api/classes/llvm/value">Value</a> * V, bool WillInvertAllUses)</td>
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



<p>Definition at line 234 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/transforms/include/llvm/transforms/instcombine/instcombiner-h">InstCombiner.h</a>.</p>


<p>Reference <a href="#a1f819cdc746560fd28977b1175030cff">isFreeToInvert</a>.</p>

</div>
</div>

### isKnownToBeAPowerOfTwo() {#a46e6cc426055f50cdb04009adb4c2f94}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool llvm::InstCombiner::isKnownToBeAPowerOfTwo (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/value">Value</a> * V, bool OrZero=false, unsigned Depth=0, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/instruction">Instruction</a> * CxtI=nullptr)</td>
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



<p>Definition at line 443 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/transforms/include/llvm/transforms/instcombine/instcombiner-h">InstCombiner.h</a>.</p>


<p>References <a href="/web-llvm/docs/api/namespaces/llvm/#a1eb5609345b906d024fbf9e4bc1adc06afe578efb7ca235af77fb0eef7edcf639">llvm::Depth</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a4036c3c75bcee1206cd199548b87f9ae">llvm::isKnownToBeAPowerOfTwo</a> and <a href="#a067e49eb19f14e50f84cf4b4e7f6acde">SQ</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/instcombine/instcombinecalls-cpp/#abd2a207499b6fef021080fbe87fa61d6">foldCtpop</a>, <a href="/web-llvm/docs/api/classes/llvm/instcombinerimpl/#acb575761ffbc75842def91257cc5168d">llvm::InstCombinerImpl::foldICmpEquality</a>, <a href="/web-llvm/docs/api/classes/llvm/instcombinerimpl/#a90148636c6d38a9475471b8b43e93b04">llvm::InstCombinerImpl::foldIRemByPowerOfTwoToBitTest</a>, <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/instcombine/instcombinemuldivrem-cpp/#a2057625407debe603c4fb211d1cdc571">simplifyValueKnownNonZero</a>, <a href="/web-llvm/docs/api/classes/llvm/instcombinerimpl/#a648710a93ceb0bbddf0a2ae7a8bb2ca5">llvm::InstCombinerImpl::visitAnd</a>, <a href="/web-llvm/docs/api/classes/llvm/instcombinerimpl/#afa2581e2e1ac6959cd02e28062a7c1d5">llvm::InstCombinerImpl::visitCallInst</a>, <a href="/web-llvm/docs/api/classes/llvm/instcombinerimpl/#ae31c50e938b95587c87aed0f133b1346">llvm::InstCombinerImpl::visitICmpInst</a>, <a href="/web-llvm/docs/api/classes/llvm/instcombinerimpl/#af12904244ec179b265540ed1fb8c6615">llvm::InstCombinerImpl::visitSDiv</a>, <a href="/web-llvm/docs/api/classes/llvm/instcombinerimpl/#a1cdbee2aa0ed532c8d9e91a00cc91f37">llvm::InstCombinerImpl::visitUDiv</a>, <a href="/web-llvm/docs/api/classes/llvm/instcombinerimpl/#a2f39b95e8efb44737439c323b18a55d7">llvm::InstCombinerImpl::visitURem</a> and <a href="/web-llvm/docs/api/classes/llvm/instcombinerimpl/#aaf7b6cd7c3ceb4af17b610cba09648c9">llvm::InstCombinerImpl::visitXor</a>.</p>

</div>
</div>

### isValidAddrSpaceCast() {#aed7a042bbe624a8dcfdfb66c8bf39777}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool InstCombiner::isValidAddrSpaceCast (unsigned FromAS, unsigned ToAS)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Declaration at line 523 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/transforms/include/llvm/transforms/instcombine/instcombiner-h">InstCombiner.h</a>, definition at line 189 of file <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/instcombine/instructioncombining-cpp">InstructionCombining.cpp</a>.</p>


<p>Referenced by <a href="#a98434f092f1b1a571d9e53226ab75a06">SimplifyDemandedVectorElts</a>.</p>

</div>
</div>

### MaskedValueIsZero() {#ae506e7be0a7aaf9001e31d5fca5f2fbc}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool llvm::InstCombiner::MaskedValueIsZero (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/value">Value</a> * V, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/apint">APInt</a> &amp; Mask, unsigned Depth=0, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/instruction">Instruction</a> * CxtI=nullptr)</td>
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



<p>Definition at line 450 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/transforms/include/llvm/transforms/instcombine/instcombiner-h">InstCombiner.h</a>.</p>


<p>References <a href="/web-llvm/docs/api/namespaces/llvm/#a1eb5609345b906d024fbf9e4bc1adc06afe578efb7ca235af77fb0eef7edcf639">llvm::Depth</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a5738f911a81d4a66c8778d86be098dde">llvm::MaskedValueIsZero</a> and <a href="#a067e49eb19f14e50f84cf4b4e7f6acde">SQ</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/instcombine/instcombineshifts-cpp/#aaba35705ce5c614a4b4d1a6ed6e8bb57">canEvaluateShiftedShift</a>, <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/instcombine/instcombinecasts-cpp/#aefd6331c5fd6ec51f6a9e5558f885f28">canEvaluateTruncated</a>, <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/instcombine/instcombinecasts-cpp/#a3d3ed8206aabad62293aeddd444bab9f">canEvaluateZExtd</a>, <a href="/web-llvm/docs/api/classes/llvm/instcombinerimpl/#ac38a3c2794db0ecc70c9bb7106f1e1bf">llvm::InstCombinerImpl::foldAddWithConstant</a>, <a href="/web-llvm/docs/api/classes/llvm/instcombinerimpl/#a648710a93ceb0bbddf0a2ae7a8bb2ca5">llvm::InstCombinerImpl::visitAnd</a>, <a href="/web-llvm/docs/api/classes/llvm/instcombinerimpl/#a612d91fe0858006abe73d7b62821da0c">llvm::InstCombinerImpl::visitAShr</a>, <a href="/web-llvm/docs/api/classes/llvm/instcombinerimpl/#afa2581e2e1ac6959cd02e28062a7c1d5">llvm::InstCombinerImpl::visitCallInst</a>, <a href="/web-llvm/docs/api/classes/llvm/instcombinerimpl/#a1e893463cbb4b5e2e3830b2e4c28cbdb">llvm::InstCombinerImpl::visitOr</a>, <a href="/web-llvm/docs/api/classes/llvm/instcombinerimpl/#a90fcdfa591c9bd0cf511f2803198b355">llvm::InstCombinerImpl::visitShl</a>, <a href="/web-llvm/docs/api/classes/llvm/instcombinerimpl/#a411aa95504f966614c8f5d5aeeef1f04">llvm::InstCombinerImpl::visitSRem</a>, <a href="/web-llvm/docs/api/classes/llvm/instcombinerimpl/#a43a1d060dacb05eb645cf91ea86d7bd3">llvm::InstCombinerImpl::visitTrunc</a>, <a href="/web-llvm/docs/api/classes/llvm/instcombinerimpl/#aaf7b6cd7c3ceb4af17b610cba09648c9">llvm::InstCombinerImpl::visitXor</a> and <a href="/web-llvm/docs/api/classes/llvm/instcombinerimpl/#a2175862566372c3684fe4f7bf62e3143">llvm::InstCombinerImpl::visitZExt</a>.</p>

</div>
</div>

### replaceInstUsesWith() {#a49f1bd0bdf0ef741bdd714cc1188d7c5}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">Instruction * llvm::InstCombiner::replaceInstUsesWith (<a href="/web-llvm/docs/api/classes/llvm/instruction">Instruction</a> &amp; I, <a href="/web-llvm/docs/api/classes/llvm/value">Value</a> * V)</td>
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

<p>A combiner-aware RAUW-like routine.</p>


<p>This method is to be used when an instruction is found to be dead, replaceable with another preexisting expression. Here we add all uses of I to the worklist, replace all uses of I with the new value, then return I, so that the inst combiner will know that I was modified.</p>


<p>Definition at line 388 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/transforms/include/llvm/transforms/instcombine/instcombiner-h">InstCombiner.h</a>.</p>


<p>References <a href="/web-llvm/docs/api/namespaces/llvm/#a7c46c742c31be54870e2038048e6b391">llvm::dbgs</a>, <a href="/web-llvm/docs/api/classes/llvm/poisonvalue/#a1bf08613fb664a2e377a9a72c59a6b66">llvm::PoisonValue::get</a>, <a href="/web-llvm/docs/api/files/lib/lib/support/md5-cpp/#ac0eafdc9ee161b71e7af98af736952fd">I</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a92ca992e52dddc420f4b069cae06dfbe">llvm::isa</a>, <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/support/debug-h/#a196897517069dda1bdb549e24468f7d7">LLVM_DEBUG</a> and <a href="#a7b93340fbcab35a38a04bf49aa3113a0">Worklist</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/classes/llvm/instcombinerimpl/#a6adc65f05e61f4929966c0e4429c6fc7">llvm::InstCombinerImpl::commonCastTransforms</a>, <a href="/web-llvm/docs/api/classes/llvm/instcombinerimpl/#a739e3cd7494ba55179722c33498e8462">llvm::InstCombinerImpl::commonIDivRemTransforms</a>, <a href="/web-llvm/docs/api/classes/llvm/instcombinerimpl/#a8d5176ac30d2d151700b01a9f3451131">llvm::InstCombinerImpl::commonIDivTransforms</a>, <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/instcombine/instcombinemuldivrem-cpp/#a0adb0a856adef09fd017379f4644ba4e">convertFSqrtDivIntoFMul</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/nvptx/nvptxtargettransforminfo-cpp/#a2efdcd5db2fb392d8ef38eca4bc0f570">convertNvvmIntrinsicToLlvm</a>, <a href="/web-llvm/docs/api/classes/llvm/instcombinerimpl/#ac38a3c2794db0ecc70c9bb7106f1e1bf">llvm::InstCombinerImpl::foldAddWithConstant</a>, <a href="/web-llvm/docs/api/classes/llvm/instcombinerimpl/#acad657182350311f85bc33387733e506">llvm::InstCombinerImpl::foldAggregateConstructionIntoAggregateReuse</a>, <a href="/web-llvm/docs/api/classes/llvm/instcombinerimpl/#ad4fde4387244f67f320e62602af17b68">llvm::InstCombinerImpl::foldAllocaCmp</a>, <a href="/web-llvm/docs/api/classes/llvm/instcombinerimpl/#a866883cec7ed781fcf1e9cda18b24f5b">llvm::InstCombinerImpl::foldCmpLoadFromIndexedGlobal</a>, <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/instcombine/instcombinecalls-cpp/#abd2a207499b6fef021080fbe87fa61d6">foldCtpop</a>, <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/instcombine/instcombinecalls-cpp/#ac6169fee4cf2c33a0c3abb46628bfefc">foldCttzCtlz</a>, <a href="/web-llvm/docs/api/classes/llvm/instcombinerimpl/#aabb5edbf6f79b04ce152f73869c1a4aa">llvm::InstCombinerImpl::foldDeadPhiWeb</a>, <a href="/web-llvm/docs/api/classes/llvm/instcombinerimpl/#a901cc1fd9cbb0ec57e3d7f53a70ecd09">llvm::InstCombinerImpl::foldFCmpIntToFPConst</a>, <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/instcombine/instcombinecompares-cpp/#a64f9db21c2ec2a4bd69aeea38e48b3a4">foldFCmpWithFloorAndCeil</a>, <a href="/web-llvm/docs/api/classes/llvm/instcombinerimpl/#ac633a4c4d399457c76640f7dea5ebcd7">llvm::InstCombinerImpl::foldFMulReassoc</a>, <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/instcombine/instcombinecasts-cpp/#a568e85197421e091a259bf80e19c6765">foldFPtoI</a>, <a href="/web-llvm/docs/api/classes/llvm/instcombinerimpl/#aef28063eb280fec69a391dd35c51666e">llvm::InstCombinerImpl::foldFreezeIntoRecurrence</a>, <a href="/web-llvm/docs/api/classes/llvm/instcombinerimpl/#afc78cb7aeb92b0fc9223239dd827f7e3">llvm::InstCombinerImpl::foldGEPICmp</a>, <a href="/web-llvm/docs/api/classes/llvm/instcombinerimpl/#aa148a41463d0d36003033ac988b2c28d">llvm::InstCombinerImpl::foldICmpAddConstant</a>, <a href="/web-llvm/docs/api/classes/llvm/instcombinerimpl/#ac457b78bde79027e427b9d2ca79bb2f1">llvm::InstCombinerImpl::foldICmpAndConstant</a>, <a href="/web-llvm/docs/api/classes/llvm/instcombinerimpl/#afa5f2de80c23c28bd1a3320e8369aab2">llvm::InstCombinerImpl::foldICmpAndConstConst</a>, <a href="/web-llvm/docs/api/classes/llvm/instcombinerimpl/#ab60c98e34bf6a4b6b599ab93a3f12b06">llvm::InstCombinerImpl::foldICmpAndShift</a>, <a href="/web-llvm/docs/api/classes/llvm/instcombinerimpl/#a36ef4128d8b08242e337bcbed0dce3c8">llvm::InstCombinerImpl::foldICmpBinOp</a>, <a href="/web-llvm/docs/api/classes/llvm/instcombinerimpl/#afbfe964338488078570fe14e7deb0551">llvm::InstCombinerImpl::foldICmpBitCast</a>, <a href="/web-llvm/docs/api/classes/llvm/instcombinerimpl/#a78688f28e25e6d68d3f06ddf6e7aac0f">llvm::InstCombinerImpl::foldICmpCommutative</a>, <a href="/web-llvm/docs/api/classes/llvm/instcombinerimpl/#a8efbb860a56c4deccffeca4d2963fb70">llvm::InstCombinerImpl::foldICmpDivConstant</a>, <a href="/web-llvm/docs/api/classes/llvm/instcombinerimpl/#a1140591a375ac3efde57977192880eb0">llvm::InstCombinerImpl::foldICmpOrConstant</a>, <a href="/web-llvm/docs/api/classes/llvm/instcombinerimpl/#a0550f165f22c1b1372bf6428191f0a9e">llvm::InstCombinerImpl::foldICmpSelectConstant</a>, <a href="/web-llvm/docs/api/classes/llvm/instcombinerimpl/#a47a83bda096455c177d40a2fbae13de1">llvm::InstCombinerImpl::foldICmpShlConstConst</a>, <a href="/web-llvm/docs/api/classes/llvm/instcombinerimpl/#af57017eaefdf5b514ffd801e9923bbca">llvm::InstCombinerImpl::foldICmpShrConstConst</a>, <a href="/web-llvm/docs/api/classes/llvm/instcombinerimpl/#a7c9fd9f2dba79c2289639f72457fcea1">llvm::InstCombinerImpl::foldICmpUsingBoolRange</a>, <a href="/web-llvm/docs/api/classes/llvm/instcombinerimpl/#a8de411243dcb508d9d512006edaba1ec">llvm::InstCombinerImpl::foldICmpUsingKnownBits</a>, <a href="/web-llvm/docs/api/classes/llvm/instcombinerimpl/#a6c028a26ae2c72e9018e5a80713ba819">llvm::InstCombinerImpl::foldICmpWithConstant</a>, <a href="/web-llvm/docs/api/classes/llvm/instcombinerimpl/#af24dc3f2a89de0b400a681002927217d">llvm::InstCombinerImpl::foldICmpWithDominatingICmp</a>, <a href="/web-llvm/docs/api/classes/llvm/instcombinerimpl/#acff3d4c4feb8a1f71844fa1facae5670">llvm::InstCombinerImpl::foldICmpWithMinMax</a>, <a href="/web-llvm/docs/api/classes/llvm/instcombinerimpl/#aab1473644ffe7926032a4e01ed4bad78">llvm::InstCombinerImpl::foldIntegerTypedPHI</a>, <a href="/web-llvm/docs/api/classes/llvm/instcombinerimpl/#a78d5bb4c6437373debabeb3f816645cb">llvm::InstCombinerImpl::foldItoFPtoI</a>, <a href="/web-llvm/docs/api/classes/llvm/instcombinerimpl/#a657815d57170937e7e75bee5ecf235ce">llvm::InstCombinerImpl::foldMultiplicationOverflowCheck</a>, <a href="/web-llvm/docs/api/classes/llvm/instcombinerimpl/#a2fc50d227d302eb98914f04bcc6634e1">llvm::InstCombinerImpl::foldOpIntoPhi</a>, <a href="/web-llvm/docs/api/classes/llvm/instcombinerimpl/#aed2c2c5e2a07649e02d6647d9a5c8852">llvm::InstCombinerImpl::foldPowiReassoc</a>, <a href="/web-llvm/docs/api/classes/llvm/instcombinerimpl/#a4bd29d381405675f36964e4a5382dae4">llvm::InstCombinerImpl::foldSelectOpOp</a>, <a href="/web-llvm/docs/api/classes/llvm/instcombinerimpl/#a3b73df3a995af9ca26c9d024c957c45a">llvm::InstCombinerImpl::foldSelectShuffle</a>, <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/instcombine/instcombineselect-cpp/#a550ee33b5be6c859c443739649308721">foldSelectZeroOrMul</a>, <a href="/web-llvm/docs/api/classes/llvm/instcombinerimpl/#ad3f7f3eaea6d34ab9ade1af54174f5a2">llvm::InstCombinerImpl::FoldShiftByConstant</a>, <a href="/web-llvm/docs/api/classes/llvm/instcombinerimpl/#aa72b51b8f455c8a622bb6f8cc9c14860">llvm::InstCombinerImpl::foldVariableSignZeroExtensionOfVariableHighBitExtract</a>, <a href="/web-llvm/docs/api/classes/llvm/instcombinerimpl/#af8c1d39848b445bea8e307b53f81c481">llvm::InstCombinerImpl::freelyInvertAllUsersOf</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/nvptx/nvptxtargettransforminfo-cpp/#a047890dfe94355c41e98c0b8561b9f14">handleSpaceCheckIntrinsics</a>, <a href="/web-llvm/docs/api/classes/llvm/instcombinerimpl/#a352cde174c12aa24afbb7e61c22853e2">llvm::InstCombinerImpl::handleUnreachableFrom</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64targettransforminfo-cpp/#aa75e387193fd10b9055d76076288f1ad">instCombineConvertFromSVBool</a>, <a href="/web-llvm/docs/api/classes/llvm/armttiimpl/#a5c10997d5aed59d126fc726249d8b561">llvm::ARMTTIImpl::instCombineIntrinsic</a>, <a href="/web-llvm/docs/api/classes/llvm/gcnttiimpl/#ae3d1835a72f8f0ba85ace9e2c0fbfc96">llvm::GCNTTIImpl::instCombineIntrinsic</a>, <a href="/web-llvm/docs/api/classes/llvm/x86ttiimpl/#a47cb7185e35282131b486036ff7c45df">llvm::X86TTIImpl::instCombineIntrinsic</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64targettransforminfo-cpp/#a4e5c7b6a107ed8c6fa33ce4b8a6f97c2">instCombineLD1GatherIndex</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64targettransforminfo-cpp/#a853cb930011d541f0c0d5ec55cdba398">instCombineMaxMinNM</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64targettransforminfo-cpp/#a7fcf73aaa1b218db266c0f9d4020ab3f">instCombineRDFFR</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64targettransforminfo-cpp/#a2cdcdfa49d958739255ca4c594a794c1">instCombineSVEAllOrNoActive</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64targettransforminfo-cpp/#a7915bab3089583402f61b46f7baea356">instCombineSVECmpNE</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64targettransforminfo-cpp/#aed4b32e0e8ed6a18607dde66ca4a433e">instCombineSVECntElts</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64targettransforminfo-cpp/#a965b006c5624011322112bb1f1325f8e">instCombineSVECondLast</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64targettransforminfo-cpp/#aa6ab3fab9efb1a05c605f74d579db034">instCombineSVEDup</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64targettransforminfo-cpp/#afdcb3be103dc32527286d0352eeacdd6">instCombineSVEDupqLane</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64targettransforminfo-cpp/#a777bb183e9f322303a06538caf0696b2">instCombineSVEDupX</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64targettransforminfo-cpp/#a55db09d477edd12f49b553e2bff37a46">instCombineSVEInsr</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64targettransforminfo-cpp/#ae2f9543c1954e97e2887aab7c33e18b4">instCombineSVELast</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64targettransforminfo-cpp/#ac80824cf7bdae0e18c7032eb8ce5214c">instCombineSVELD1</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64targettransforminfo-cpp/#acbcb2b20c6532c73d9c0c74e9e2c9c13">instCombineSVENoActiveReplace</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64targettransforminfo-cpp/#a73170211689546daae2d8b0676c6d676">instCombineSVENoActiveZero</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64targettransforminfo-cpp/#a9946a89352eee5ab78f0f3fc4fc18941">instCombineSVEPTest</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64targettransforminfo-cpp/#a6059af97420634905c86d144d23dab4e">instCombineSVESDIV</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64targettransforminfo-cpp/#a122aba3e4ce982c894eee6da09b1c234">instCombineSVESel</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64targettransforminfo-cpp/#accf1e11b7d8fcba73d2fe80110555e48">instCombineSVESrshl</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64targettransforminfo-cpp/#aba5cce04083b467217c8829a13e5b981">instCombineSVETBL</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64targettransforminfo-cpp/#a194bc0e605101ffd7f8249fcf88e45ca">instCombineSVEUnpack</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64targettransforminfo-cpp/#aac6aaf36d8c34dfd27b90fc04ea3c08f">instCombineSVEUzp1</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64targettransforminfo-cpp/#ab6151efab78587b3732ad634505a4dd0">instCombineSVEVectorBinOp</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64targettransforminfo-cpp/#a052318a71439e8ffd109c713d19b5926">instCombineSVEVectorFuseMulAddSub</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64targettransforminfo-cpp/#a02ae4cbb6cd5032e168971d651d7285b">instCombineSVEVectorMul</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64targettransforminfo-cpp/#aa11ad9ec9e8586b319ba9e5c9fb6443e">instCombineSVEZip</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/amdgpuinstcombineintrinsic-cpp/#a8a43e48d75ff4289fc2674097dab5d50">modifyIntrinsicCall</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64targettransforminfo-cpp/#a53ef6f5be8cd25a33229fe16aca9d537">processPhiNode</a>, <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/instcombine/instcombinecompares-cpp/#aae87c326017fc14f5ba90a036e45438a">processUGT_ADDCST_ADD</a>, <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/instcombine/instcombinecompares-cpp/#a67cafe6badc04395d797929d9d4e8efe">processUMulZExtIdiom</a>, <a href="/web-llvm/docs/api/classes/llvm/instcombinerimpl/#acc169700a214095e0dca03c99ba3a9eb">llvm::InstCombinerImpl::removeInstructionsBeforeUnreachable</a>, <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/instcombine/instcombinevectorops-cpp/#a801d960feba2403acf8dbd07ee3f34b6">replaceExtractElements</a>, <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/instcombine/instcombinecompares-cpp/#a0aa7c68d8c3095ffc271ecceab16c86e">rewriteGEPAsOffset</a>, <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/instcombine/instcombineloadstorealloca-cpp/#a25ea6e038ccdef52ab01b0ee3da9ee52">simplifyAllocaArraySize</a>, <a href="/web-llvm/docs/api/classes/llvm/instcombinerimpl/#afcc877a26419c2aef195256bc0aa01e3">llvm::InstCombinerImpl::SimplifyDemandedInstructionBits</a>, <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/instcombine/instcombinemuldivrem-cpp/#a177f4d30b9356e0bc4a5dc176e825cb2">simplifyIRemMulShl</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/x86/x86instcombineintrinsic-cpp/#a06d646994f54f30c64dcb09a8c6d91f3">simplifyX86MaskedLoad</a>, <a href="/web-llvm/docs/api/classes/llvm/instcombinerimpl/#a4e2dd07eceeed7496e6c3df4d364c91e">llvm::InstCombinerImpl::sinkNotIntoLogicalOp</a>, <a href="/web-llvm/docs/api/classes/llvm/instcombinerimpl/#a8d44c548f74b3d233a248672402b5dd1">llvm::InstCombinerImpl::sinkNotIntoOtherHandOfLogicalOp</a>, <a href="/web-llvm/docs/api/classes/llvm/instcombinerimpl/#ac8cb4401526dd424f15566e4501792f7">llvm::InstCombinerImpl::SliceUpIllegalIntegerPHI</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64targettransforminfo-cpp/#a16774c131664a3e4cbc7ebc236f49c9e">tryCombineFromSVBoolBinOp</a>, <a href="/web-llvm/docs/api/classes/llvm/instcombinerimpl/#aa4cf868b89270f2f699fdee46cb572a4">llvm::InstCombinerImpl::tryFoldInstWithCtpopWithNot</a>, <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/instcombine/instcombineloadstorealloca-cpp/#aa0014a4c2da32289f871b8d5a1aa538b">unpackLoadToAggregate</a>, <a href="/web-llvm/docs/api/classes/llvm/instcombinerimpl/#a0a89a6b25b8a92fb896a994a36b74241">llvm::InstCombinerImpl::visitAdd</a>, <a href="/web-llvm/docs/api/classes/llvm/instcombinerimpl/#af99540103c8717d41b490fc2a1acad5c">llvm::InstCombinerImpl::visitAllocaInst</a>, <a href="/web-llvm/docs/api/classes/llvm/instcombinerimpl/#ae289e620828eabb1dfe34c9ad322a81d">llvm::InstCombinerImpl::visitAllocSite</a>, <a href="/web-llvm/docs/api/classes/llvm/instcombinerimpl/#a648710a93ceb0bbddf0a2ae7a8bb2ca5">llvm::InstCombinerImpl::visitAnd</a>, <a href="/web-llvm/docs/api/classes/llvm/instcombinerimpl/#a612d91fe0858006abe73d7b62821da0c">llvm::InstCombinerImpl::visitAShr</a>, <a href="/web-llvm/docs/api/classes/llvm/instcombinerimpl/#a89ab5eaec7693029761c8d0b3ded3b00">llvm::InstCombinerImpl::visitBitCast</a>, <a href="/web-llvm/docs/api/classes/llvm/instcombinerimpl/#afa2581e2e1ac6959cd02e28062a7c1d5">llvm::InstCombinerImpl::visitCallInst</a>, <a href="/web-llvm/docs/api/classes/llvm/instcombinerimpl/#a71ef354bd1ea9e02d70146d7218a7d39">llvm::InstCombinerImpl::visitExtractElementInst</a>, <a href="/web-llvm/docs/api/classes/llvm/instcombinerimpl/#a679f36556ace611ccc56580cb497973a">llvm::InstCombinerImpl::visitExtractValueInst</a>, <a href="/web-llvm/docs/api/classes/llvm/instcombinerimpl/#a92fdf04445f26ef88ea0e134408b30fe">llvm::InstCombinerImpl::visitFAdd</a>, <a href="/web-llvm/docs/api/classes/llvm/instcombinerimpl/#a86b0437dceb8e39c8185dc7def325011">llvm::InstCombinerImpl::visitFCmpInst</a>, <a href="/web-llvm/docs/api/classes/llvm/instcombinerimpl/#a5457b45fe74cf2f411f5824d32fd389d">llvm::InstCombinerImpl::visitFDiv</a>, <a href="/web-llvm/docs/api/classes/llvm/instcombinerimpl/#abf257c2c6dadfee6ee83fabb6ea77c4f">llvm::InstCombinerImpl::visitFMul</a>, <a href="/web-llvm/docs/api/classes/llvm/instcombinerimpl/#af616ac59efde7c61f6e8ff8bd80d2027">llvm::InstCombinerImpl::visitFNeg</a>, <a href="/web-llvm/docs/api/classes/llvm/instcombinerimpl/#a7eb1707b3b9ea994955ac9d230535261">llvm::InstCombinerImpl::visitFPTrunc</a>, <a href="/web-llvm/docs/api/classes/llvm/instcombinerimpl/#a629e02c312173d0da1b62288bc8fbd48">llvm::InstCombinerImpl::visitFree</a>, <a href="/web-llvm/docs/api/classes/llvm/instcombinerimpl/#a397caaa6fe7aad6bb3d482f9fe157e71">llvm::InstCombinerImpl::visitFreeze</a>, <a href="/web-llvm/docs/api/classes/llvm/instcombinerimpl/#aa86b3c1abcd345da14cfe5dd65165b86">llvm::InstCombinerImpl::visitFRem</a>, <a href="/web-llvm/docs/api/classes/llvm/instcombinerimpl/#afa72f4f7fc2ee2bf6cd3b64bd07c37e8">llvm::InstCombinerImpl::visitFSub</a>, <a href="/web-llvm/docs/api/classes/llvm/instcombinerimpl/#a22bc54f319e33d248b169116b757a143">llvm::InstCombinerImpl::visitGEPOfGEP</a>, <a href="/web-llvm/docs/api/classes/llvm/instcombinerimpl/#ae755d569b6e5c69a8abbc6de50cf3f6b">llvm::InstCombinerImpl::visitGetElementPtrInst</a>, <a href="/web-llvm/docs/api/classes/llvm/instcombinerimpl/#ae31c50e938b95587c87aed0f133b1346">llvm::InstCombinerImpl::visitICmpInst</a>, <a href="/web-llvm/docs/api/classes/llvm/instcombinerimpl/#a687fa4390149f0cb751d8ad89dca6a3c">llvm::InstCombinerImpl::visitInsertElementInst</a>, <a href="/web-llvm/docs/api/classes/llvm/instcombinerimpl/#a643f8d7ef849e1312c83906b4b27b4aa">llvm::InstCombinerImpl::visitInsertValueInst</a>, <a href="/web-llvm/docs/api/classes/llvm/instcombinerimpl/#a3ba96a0d49ec5f1a062b075f54536a3c">llvm::InstCombinerImpl::visitLoadInst</a>, <a href="/web-llvm/docs/api/classes/llvm/instcombinerimpl/#a197424adbab353be4587e6dfaee445e3">llvm::InstCombinerImpl::visitLShr</a>, <a href="/web-llvm/docs/api/classes/llvm/instcombinerimpl/#a01ed915fb2acf9fd660ca752edeec0db">llvm::InstCombinerImpl::visitMul</a>, <a href="/web-llvm/docs/api/classes/llvm/instcombinerimpl/#a1e893463cbb4b5e2e3830b2e4c28cbdb">llvm::InstCombinerImpl::visitOr</a>, <a href="/web-llvm/docs/api/classes/llvm/instcombinerimpl/#a752efe4724ac3a97d07ee81d5f779c92">llvm::InstCombinerImpl::visitPHINode</a>, <a href="/web-llvm/docs/api/classes/llvm/instcombinerimpl/#a50b0daca4f05a8d2af14aec07f64f3cc">llvm::InstCombinerImpl::visitPtrToInt</a>, <a href="/web-llvm/docs/api/classes/llvm/instcombinerimpl/#af12904244ec179b265540ed1fb8c6615">llvm::InstCombinerImpl::visitSDiv</a>, <a href="/web-llvm/docs/api/classes/llvm/instcombinerimpl/#a2a5120238e6845643a37d5a4675a5342">llvm::InstCombinerImpl::visitSExt</a>, <a href="/web-llvm/docs/api/classes/llvm/instcombinerimpl/#a90fcdfa591c9bd0cf511f2803198b355">llvm::InstCombinerImpl::visitShl</a>, <a href="/web-llvm/docs/api/classes/llvm/instcombinerimpl/#ad31108b4f7156db7565eadba1285c93a">llvm::InstCombinerImpl::visitShuffleVectorInst</a>, <a href="/web-llvm/docs/api/classes/llvm/instcombinerimpl/#a411aa95504f966614c8f5d5aeeef1f04">llvm::InstCombinerImpl::visitSRem</a>, <a href="/web-llvm/docs/api/classes/llvm/instcombinerimpl/#a606601489498c1ba41f25e77eb2dd0cf">llvm::InstCombinerImpl::visitSub</a>, <a href="/web-llvm/docs/api/classes/llvm/instcombinerimpl/#a43a1d060dacb05eb645cf91ea86d7bd3">llvm::InstCombinerImpl::visitTrunc</a>, <a href="/web-llvm/docs/api/classes/llvm/instcombinerimpl/#a1cdbee2aa0ed532c8d9e91a00cc91f37">llvm::InstCombinerImpl::visitUDiv</a>, <a href="/web-llvm/docs/api/classes/llvm/instcombinerimpl/#a2f39b95e8efb44737439c323b18a55d7">llvm::InstCombinerImpl::visitURem</a>, <a href="/web-llvm/docs/api/classes/llvm/instcombinerimpl/#aaf7b6cd7c3ceb4af17b610cba09648c9">llvm::InstCombinerImpl::visitXor</a> and <a href="/web-llvm/docs/api/classes/llvm/instcombinerimpl/#a2175862566372c3684fe4f7bf62e3143">llvm::InstCombinerImpl::visitZExt</a>.</p>

</div>
</div>

### replaceOperand() {#ac2a56636a6f3742f5e495f67e67b6b36}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">Instruction * llvm::InstCombiner::replaceOperand (<a href="/web-llvm/docs/api/classes/llvm/instruction">Instruction</a> &amp; I, unsigned OpNum, <a href="/web-llvm/docs/api/classes/llvm/value">Value</a> * V)</td>
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

<p>Replace operand of instruction and add old operand to the worklist.</p>

<p>Definition at line 412 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/transforms/include/llvm/transforms/instcombine/instcombiner-h">InstCombiner.h</a>.</p>


<p>References <a href="/web-llvm/docs/api/files/lib/lib/support/md5-cpp/#ac0eafdc9ee161b71e7af98af736952fd">I</a> and <a href="#a7b93340fbcab35a38a04bf49aa3113a0">Worklist</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/classes/llvm/instcombinerimpl/#a739e3cd7494ba55179722c33498e8462">llvm::InstCombinerImpl::commonIDivRemTransforms</a>, <a href="/web-llvm/docs/api/classes/llvm/instcombinerimpl/#a8d5176ac30d2d151700b01a9f3451131">llvm::InstCombinerImpl::commonIDivTransforms</a>, <a href="/web-llvm/docs/api/classes/llvm/instcombinerimpl/#aa831d259fa5719e16927b5f4877988db">llvm::InstCombinerImpl::commonShiftTransforms</a>, <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/instcombine/instcombinecalls-cpp/#abd2a207499b6fef021080fbe87fa61d6">foldCtpop</a>, <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/instcombine/instcombinecalls-cpp/#ac6169fee4cf2c33a0c3abb46628bfefc">foldCttzCtlz</a>, <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/instcombine/instcombinecompares-cpp/#a093153573aa0758fa34bf50a930fb27f">foldFabsWithFcmpZero</a>, <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/instcombine/instcombinecompares-cpp/#a48239fe2dd570dc10b58a6a89ce6dd72">foldFCmpFSubIntoFCmp</a>, <a href="/web-llvm/docs/api/classes/llvm/instcombinerimpl/#aa8f0b6273a443e7a98755fcb08d97f22">llvm::InstCombinerImpl::foldICmpXorConstant</a>, <a href="/web-llvm/docs/api/classes/llvm/instcombinerimpl/#abd122b6678d6a8f14b6ab6bc18863b27">llvm::InstCombinerImpl::foldPHIArgIntToPtrToPHI</a>, <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/instcombine/instcombineselect-cpp/#a917f93b85c9b8cfe9ad68ba6d49966ba">foldSelectBinOpIdentity</a>, <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/instcombine/instcombineselect-cpp/#a550ee33b5be6c859c443739649308721">foldSelectZeroOrMul</a>, <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/instcombine/instcombinevectorops-cpp/#a661440047dc1b2af077911d9cf92236a">foldShuffleWithInsert</a>, <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/instcombine/instcombinecompares-cpp/#a72de2035f3a6a9668b5de9e3c2624e46">foldSqrtWithFcmpZero</a>, <a href="/web-llvm/docs/api/classes/llvm/armttiimpl/#a5c10997d5aed59d126fc726249d8b561">llvm::ARMTTIImpl::instCombineIntrinsic</a>, <a href="/web-llvm/docs/api/classes/llvm/gcnttiimpl/#ae3d1835a72f8f0ba85ace9e2c0fbfc96">llvm::GCNTTIImpl::instCombineIntrinsic</a>, <a href="/web-llvm/docs/api/classes/llvm/x86ttiimpl/#a47cb7185e35282131b486036ff7c45df">llvm::X86TTIImpl::instCombineIntrinsic</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64targettransforminfo-cpp/#ac798b3bd7ffd81421fe4b75b8af36c7c">instCombineSVEAllOrNoActiveUnary</a>, <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/instcombine/instcombineloadstorealloca-cpp/#a25ea6e038ccdef52ab01b0ee3da9ee52">simplifyAllocaArraySize</a>, <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/instcombine/instructioncombining-cpp/#a41c00c458f7416c93927bc2f332b3898">simplifyAssocCastAssoc</a>, <a href="/web-llvm/docs/api/classes/llvm/instcombinerimpl/#a225d5b1dcc0015e743f1dbbf348a9c36">llvm::InstCombinerImpl::SimplifyAssociativeOrCommutative</a>, <a href="/web-llvm/docs/api/classes/llvm/instcombinerimpl/#a4bb2cbb88b57c9a126549efe2134d1cb">llvm::InstCombinerImpl::SimplifyDemandedUseBits</a>, <a href="/web-llvm/docs/api/classes/llvm/instcombinerimpl/#a37cce7aa1875173688e5971c5d6fa9e0">llvm::InstCombinerImpl::SimplifyDemandedVectorElts</a>, <a href="/web-llvm/docs/api/classes/llvm/instcombinerimpl/#a558144ce515858cbab3df5c7005a5a50">llvm::InstCombinerImpl::simplifyDivRemOfSelectWithZeroOp</a>, <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/instcombine/instcombinemuldivrem-cpp/#a2057625407debe603c4fb211d1cdc571">simplifyValueKnownNonZero</a>, <a href="/web-llvm/docs/api/classes/llvm/instcombinerimpl/#a0a89a6b25b8a92fb896a994a36b74241">llvm::InstCombinerImpl::visitAdd</a>, <a href="/web-llvm/docs/api/classes/llvm/instcombinerimpl/#af99540103c8717d41b490fc2a1acad5c">llvm::InstCombinerImpl::visitAllocaInst</a>, <a href="/web-llvm/docs/api/classes/llvm/instcombinerimpl/#a3d5d32552609554018891c30a532f1d6">llvm::InstCombinerImpl::visitAtomicRMWInst</a>, <a href="/web-llvm/docs/api/classes/llvm/instcombinerimpl/#aea9ba5a362fb88bd97349a302133dd03">llvm::InstCombinerImpl::visitBranchInst</a>, <a href="/web-llvm/docs/api/classes/llvm/instcombinerimpl/#afa2581e2e1ac6959cd02e28062a7c1d5">llvm::InstCombinerImpl::visitCallInst</a>, <a href="/web-llvm/docs/api/classes/llvm/instcombinerimpl/#a71ef354bd1ea9e02d70146d7218a7d39">llvm::InstCombinerImpl::visitExtractElementInst</a>, <a href="/web-llvm/docs/api/classes/llvm/instcombinerimpl/#a86b0437dceb8e39c8185dc7def325011">llvm::InstCombinerImpl::visitFCmpInst</a>, <a href="/web-llvm/docs/api/classes/llvm/instcombinerimpl/#a5457b45fe74cf2f411f5824d32fd389d">llvm::InstCombinerImpl::visitFDiv</a>, <a href="/web-llvm/docs/api/classes/llvm/instcombinerimpl/#ae755d569b6e5c69a8abbc6de50cf3f6b">llvm::InstCombinerImpl::visitGetElementPtrInst</a>, <a href="/web-llvm/docs/api/classes/llvm/instcombinerimpl/#ae31c50e938b95587c87aed0f133b1346">llvm::InstCombinerImpl::visitICmpInst</a>, <a href="/web-llvm/docs/api/classes/llvm/instcombinerimpl/#a687fa4390149f0cb751d8ad89dca6a3c">llvm::InstCombinerImpl::visitInsertElementInst</a>, <a href="/web-llvm/docs/api/classes/llvm/instcombinerimpl/#a3ba96a0d49ec5f1a062b075f54536a3c">llvm::InstCombinerImpl::visitLoadInst</a>, <a href="/web-llvm/docs/api/classes/llvm/instcombinerimpl/#a752efe4724ac3a97d07ee81d5f779c92">llvm::InstCombinerImpl::visitPHINode</a>, <a href="/web-llvm/docs/api/classes/llvm/instcombinerimpl/#ad31108b4f7156db7565eadba1285c93a">llvm::InstCombinerImpl::visitShuffleVectorInst</a>, <a href="/web-llvm/docs/api/classes/llvm/instcombinerimpl/#a411aa95504f966614c8f5d5aeeef1f04">llvm::InstCombinerImpl::visitSRem</a>, <a href="/web-llvm/docs/api/classes/llvm/instcombinerimpl/#a8042dd4cb7e9772368f2808b8db577be">llvm::InstCombinerImpl::visitStoreInst</a> and <a href="/web-llvm/docs/api/classes/llvm/instcombinerimpl/#a91100900b6eb1ae18127f1e1f8f8a40e">llvm::InstCombinerImpl::visitSwitchInst</a>.</p>

</div>
</div>

### replaceUse() {#a6c1f812e984c68bc39c22b63a117e1eb}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void llvm::InstCombiner::replaceUse (<a href="/web-llvm/docs/api/classes/llvm/use">Use</a> &amp; U, <a href="/web-llvm/docs/api/classes/llvm/value">Value</a> * NewValue)</td>
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

<p>Replace use and add the previously used value to the worklist.</p>

<p>Definition at line 420 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/transforms/include/llvm/transforms/instcombine/instcombiner-h">InstCombiner.h</a>.</p>


<p>Reference <a href="#a7b93340fbcab35a38a04bf49aa3113a0">Worklist</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/classes/llvm/instcombinerimpl/#ad6aa61c7462784d1c9641ee501486375">llvm::InstCombinerImpl::addDeadEdge</a>, <a href="/web-llvm/docs/api/classes/llvm/instcombinerimpl/#aef28063eb280fec69a391dd35c51666e">llvm::InstCombinerImpl::foldFreezeIntoRecurrence</a>, <a href="/web-llvm/docs/api/classes/llvm/instcombinerimpl/#ab7805c1d4f86c20199da1dd1fab589f0">llvm::InstCombinerImpl::pushFreezeToPreventPoisonFromPropagating</a>, <a href="/web-llvm/docs/api/classes/llvm/instcombinerimpl/#a7e500d9f027b07d62374f0cee5d56724">llvm::InstCombinerImpl::SimplifyDemandedBits</a>, <a href="/web-llvm/docs/api/classes/llvm/instcombinerimpl/#aaeccf80524731a932f8e9eef3f576bf5">llvm::InstCombinerImpl::SimplifyDemandedFPClass</a>, <a href="/web-llvm/docs/api/classes/llvm/instcombinerimpl/#a558144ce515858cbab3df5c7005a5a50">llvm::InstCombinerImpl::simplifyDivRemOfSelectWithZeroOp</a>, <a href="/web-llvm/docs/api/classes/llvm/instcombinerimpl/#aea9ba5a362fb88bd97349a302133dd03">llvm::InstCombinerImpl::visitBranchInst</a> and <a href="/web-llvm/docs/api/classes/llvm/instcombinerimpl/#afa2581e2e1ac6959cd02e28062a7c1d5">llvm::InstCombinerImpl::visitCallInst</a>.</p>

</div>
</div>

### SimplifyDemandedBits() {#a95d0ee42ca35b04f96e22c6ae954e2f7}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">virtual bool llvm::InstCombiner::SimplifyDemandedBits (<a href="/web-llvm/docs/api/classes/llvm/instruction">Instruction</a> * I, unsigned OpNo, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/apint">APInt</a> &amp; DemandedMask, <a href="/web-llvm/docs/api/structs/llvm/knownbits">KnownBits</a> &amp; Known, unsigned Depth, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/structs/llvm/simplifyquery">SimplifyQuery</a> &amp; Q)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 508 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/transforms/include/llvm/transforms/instcombine/instcombiner-h">InstCombiner.h</a>.</p>


<p>References <a href="/web-llvm/docs/api/namespaces/llvm/#a1eb5609345b906d024fbf9e4bc1adc06afe578efb7ca235af77fb0eef7edcf639">llvm::Depth</a> and <a href="/web-llvm/docs/api/files/lib/lib/support/md5-cpp/#ac0eafdc9ee161b71e7af98af736952fd">I</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/classes/llvm/armttiimpl/#a5c10997d5aed59d126fc726249d8b561">llvm::ARMTTIImpl::instCombineIntrinsic</a>, <a href="/web-llvm/docs/api/classes/llvm/x86ttiimpl/#a47cb7185e35282131b486036ff7c45df">llvm::X86TTIImpl::instCombineIntrinsic</a>, <a href="#a7ff4e7685008dfb8e6a970b9130a1015">SimplifyDemandedBits</a>, <a href="/web-llvm/docs/api/classes/llvm/gcnttiimpl/#a1747fa66edae41ea9492c338ef853e12">llvm::GCNTTIImpl::simplifyDemandedLaneMaskArg</a> and <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/x86/x86instcombineintrinsic-cpp/#ad67049bfa2bb6a438fc450e018cd0dd0">simplifyX86VPERMMask</a>.</p>

</div>
</div>

### SimplifyDemandedBits() {#a7ff4e7685008dfb8e6a970b9130a1015}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool llvm::InstCombiner::SimplifyDemandedBits (<a href="/web-llvm/docs/api/classes/llvm/instruction">Instruction</a> * I, unsigned OpNo, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/apint">APInt</a> &amp; DemandedMask, <a href="/web-llvm/docs/api/structs/llvm/knownbits">KnownBits</a> &amp; Known)</td>
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



<p>Definition at line 512 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/transforms/include/llvm/transforms/instcombine/instcombiner-h">InstCombiner.h</a>.</p>


<p>References <a href="/web-llvm/docs/api/files/lib/lib/support/md5-cpp/#ac0eafdc9ee161b71e7af98af736952fd">I</a>, <a href="#a95d0ee42ca35b04f96e22c6ae954e2f7">SimplifyDemandedBits</a> and <a href="#a067e49eb19f14e50f84cf4b4e7f6acde">SQ</a>.</p>

</div>
</div>

### SimplifyDemandedVectorElts() {#a98434f092f1b1a571d9e53226ab75a06}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">virtual Value * llvm::InstCombiner::SimplifyDemandedVectorElts (<a href="/web-llvm/docs/api/classes/llvm/value">Value</a> * V, <a href="/web-llvm/docs/api/classes/llvm/apint">APInt</a> DemandedElts, <a href="/web-llvm/docs/api/classes/llvm/apint">APInt</a> &amp; UndefElts, unsigned Depth=0, bool AllowMultipleUsers=false)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 519 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/transforms/include/llvm/transforms/instcombine/instcombiner-h">InstCombiner.h</a>.</p>


<p>References <a href="/web-llvm/docs/api/namespaces/llvm/#a1eb5609345b906d024fbf9e4bc1adc06afe578efb7ca235af77fb0eef7edcf639">llvm::Depth</a> and <a href="#aed7a042bbe624a8dcfdfb66c8bf39777">isValidAddrSpaceCast</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/classes/llvm/x86ttiimpl/#a47cb7185e35282131b486036ff7c45df">llvm::X86TTIImpl::instCombineIntrinsic</a>.</p>

</div>
</div>

### targetInstCombineIntrinsic() {#aaeec6d7b5f74d07ed6e0e15fc652e327}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">std::optional&lt; Instruction * &gt; InstCombiner::targetInstCombineIntrinsic (<a href="/web-llvm/docs/api/classes/llvm/intrinsicinst">IntrinsicInst</a> &amp; II)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Declaration at line 346 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/transforms/include/llvm/transforms/instcombine/instcombiner-h">InstCombiner.h</a>, definition at line 156 of file <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/instcombine/instructioncombining-cpp">InstructionCombining.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/nvptx/nvvmintrrange-cpp/#ac5804672fc0850438d63caec770647f8">II</a> and <a href="#aaeec6d7b5f74d07ed6e0e15fc652e327">targetInstCombineIntrinsic</a>.</p>


<p>Referenced by <a href="#aaeec6d7b5f74d07ed6e0e15fc652e327">targetInstCombineIntrinsic</a> and <a href="/web-llvm/docs/api/classes/llvm/instcombinerimpl/#afa2581e2e1ac6959cd02e28062a7c1d5">llvm::InstCombinerImpl::visitCallInst</a>.</p>

</div>
</div>

### targetSimplifyDemandedUseBitsIntrinsic() {#adccadc34e77a7a0982a0832ce2419a00}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">std::optional&lt; Value * &gt; InstCombiner::targetSimplifyDemandedUseBitsIntrinsic (<a href="/web-llvm/docs/api/classes/llvm/intrinsicinst">IntrinsicInst</a> &amp; II, <a href="/web-llvm/docs/api/classes/llvm/apint">APInt</a> DemandedMask, <a href="/web-llvm/docs/api/structs/llvm/knownbits">KnownBits</a> &amp; Known, bool &amp; KnownBitsComputed)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Declaration at line 348 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/transforms/include/llvm/transforms/instcombine/instcombiner-h">InstCombiner.h</a>, definition at line 164 of file <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/instcombine/instructioncombining-cpp">InstructionCombining.cpp</a>.</p>


<p>Reference <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/nvptx/nvvmintrrange-cpp/#ac5804672fc0850438d63caec770647f8">II</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/classes/llvm/instcombinerimpl/#a4bb2cbb88b57c9a126549efe2134d1cb">llvm::InstCombinerImpl::SimplifyDemandedUseBits</a>.</p>

</div>
</div>

### targetSimplifyDemandedVectorEltsIntrinsic() {#ac1539f8fc8167c5be0eb439a4c5187fc}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">std::optional&lt; Value * &gt; InstCombiner::targetSimplifyDemandedVectorEltsIntrinsic (<a href="/web-llvm/docs/api/classes/llvm/intrinsicinst">IntrinsicInst</a> &amp; II, <a href="/web-llvm/docs/api/classes/llvm/apint">APInt</a> DemandedElts, <a href="/web-llvm/docs/api/classes/llvm/apint">APInt</a> &amp; UndefElts, <a href="/web-llvm/docs/api/classes/llvm/apint">APInt</a> &amp; UndefElts2, <a href="/web-llvm/docs/api/classes/llvm/apint">APInt</a> &amp; UndefElts3, std::function&lt; void(<a href="/web-llvm/docs/api/classes/llvm/instruction">Instruction</a> *, unsigned, <a href="/web-llvm/docs/api/classes/llvm/apint">APInt</a>, <a href="/web-llvm/docs/api/classes/llvm/apint">APInt</a> &amp;)&gt; SimplifyAndSetOp)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Declaration at line 351 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/transforms/include/llvm/transforms/instcombine/instcombiner-h">InstCombiner.h</a>, definition at line 175 of file <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/instcombine/instructioncombining-cpp">InstructionCombining.cpp</a>.</p>


<p>Reference <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/nvptx/nvvmintrrange-cpp/#ac5804672fc0850438d63caec770647f8">II</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/classes/llvm/instcombinerimpl/#a37cce7aa1875173688e5971c5d6fa9e0">llvm::InstCombinerImpl::SimplifyDemandedVectorElts</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Public Member Attributes

### Builder {#ae1d331bc844ecb92bdeb0b706ae04396}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">BuilderTy&amp; llvm::InstCombiner::Builder</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 61 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/transforms/include/llvm/transforms/instcombine/instcombiner-h">InstCombiner.h</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/instcombine/instcombinecasts-cpp/#a3e2793cc62829d80622b78cc681b25c2">canonicalizeBitCastExtElt</a>, <a href="/web-llvm/docs/api/classes/llvm/instcombinerimpl/#a1347d52f024418efd43a77e0fcb57355">llvm::InstCombinerImpl::canonicalizeCondSignextOfHighBitExtractToSignextHighBitExtract</a>, <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/instcombine/instructioncombining-cpp/#a856d46e90d7159a88c175ceff667f40c">canonicalizeGEPOfConstGEPI8</a>, <a href="/web-llvm/docs/api/classes/llvm/instcombinerimpl/#ad7586c4efa39c8f9162c7608ff9a57cf">llvm::InstCombinerImpl::combineLoadToNewType</a>, <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/instcombine/instcombineloadstorealloca-cpp/#a00d35e1397cf2210fd30e1993c1eaab9">combineStoreToNewValue</a>, <a href="/web-llvm/docs/api/classes/llvm/instcombinerimpl/#a6adc65f05e61f4929966c0e4429c6fc7">llvm::InstCombinerImpl::commonCastTransforms</a>, <a href="/web-llvm/docs/api/classes/llvm/instcombinerimpl/#a8d5176ac30d2d151700b01a9f3451131">llvm::InstCombinerImpl::commonIDivTransforms</a>, <a href="/web-llvm/docs/api/classes/llvm/instcombinerimpl/#aa831d259fa5719e16927b5f4877988db">llvm::InstCombinerImpl::commonShiftTransforms</a>, <a href="/web-llvm/docs/api/classes/llvm/instcombinerimpl/#ac38a3c2794db0ecc70c9bb7106f1e1bf">llvm::InstCombinerImpl::foldAddWithConstant</a>, <a href="/web-llvm/docs/api/classes/llvm/instcombinerimpl/#acad657182350311f85bc33387733e506">llvm::InstCombinerImpl::foldAggregateConstructionIntoAggregateReuse</a>, <a href="/web-llvm/docs/api/classes/llvm/instcombinerimpl/#a069cade7de51978d60286551f6ff71e1">llvm::InstCombinerImpl::foldBinOpOfSelectAndCastOfSelectCondition</a>, <a href="/web-llvm/docs/api/classes/llvm/instcombinerimpl/#a295de4cfe04f8cf0dee3bc16c78e5f13">llvm::InstCombinerImpl::foldBinOpShiftWithShift</a>, <a href="/web-llvm/docs/api/classes/llvm/instcombinerimpl/#a9317f2efaf85a4afc7cde58a2c0d734b">llvm::InstCombinerImpl::foldBinopWithPhiOperands</a>, <a href="/web-llvm/docs/api/classes/llvm/instcombinerimpl/#a866883cec7ed781fcf1e9cda18b24f5b">llvm::InstCombinerImpl::foldCmpLoadFromIndexedGlobal</a>, <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/instcombine/instcombinecalls-cpp/#abd2a207499b6fef021080fbe87fa61d6">foldCtpop</a>, <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/instcombine/instcombinecalls-cpp/#ac6169fee4cf2c33a0c3abb46628bfefc">foldCttzCtlz</a>, <a href="/web-llvm/docs/api/classes/llvm/instcombinerimpl/#ac633a4c4d399457c76640f7dea5ebcd7">llvm::InstCombinerImpl::foldFMulReassoc</a>, <a href="/web-llvm/docs/api/classes/llvm/instcombinerimpl/#aef28063eb280fec69a391dd35c51666e">llvm::InstCombinerImpl::foldFreezeIntoRecurrence</a>, <a href="/web-llvm/docs/api/classes/llvm/instcombinerimpl/#afc78cb7aeb92b0fc9223239dd827f7e3">llvm::InstCombinerImpl::foldGEPICmp</a>, <a href="/web-llvm/docs/api/classes/llvm/instcombinerimpl/#aa148a41463d0d36003033ac988b2c28d">llvm::InstCombinerImpl::foldICmpAddConstant</a>, <a href="/web-llvm/docs/api/classes/llvm/instcombinerimpl/#ac457b78bde79027e427b9d2ca79bb2f1">llvm::InstCombinerImpl::foldICmpAndConstant</a>, <a href="/web-llvm/docs/api/classes/llvm/instcombinerimpl/#afa5f2de80c23c28bd1a3320e8369aab2">llvm::InstCombinerImpl::foldICmpAndConstConst</a>, <a href="/web-llvm/docs/api/classes/llvm/instcombinerimpl/#ab60c98e34bf6a4b6b599ab93a3f12b06">llvm::InstCombinerImpl::foldICmpAndShift</a>, <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/instcombine/instcombinecompares-cpp/#a25119a0e5bcc1f71c61c4acc02e3ff2b">foldICmpAndXX</a>, <a href="/web-llvm/docs/api/classes/llvm/instcombinerimpl/#a36ef4128d8b08242e337bcbed0dce3c8">llvm::InstCombinerImpl::foldICmpBinOp</a>, <a href="/web-llvm/docs/api/classes/llvm/instcombinerimpl/#a78aa741a7874614a21b66826ffe6e5ce">llvm::InstCombinerImpl::foldICmpBinOpEqualityWithConstant</a>, <a href="/web-llvm/docs/api/classes/llvm/instcombinerimpl/#afbfe964338488078570fe14e7deb0551">llvm::InstCombinerImpl::foldICmpBitCast</a>, <a href="/web-llvm/docs/api/classes/llvm/instcombinerimpl/#a78688f28e25e6d68d3f06ddf6e7aac0f">llvm::InstCombinerImpl::foldICmpCommutative</a>, <a href="/web-llvm/docs/api/classes/llvm/instcombinerimpl/#a8efbb860a56c4deccffeca4d2963fb70">llvm::InstCombinerImpl::foldICmpDivConstant</a>, <a href="/web-llvm/docs/api/classes/llvm/instcombinerimpl/#a4f55d7706c3a7a5983907b84d98ddbad">llvm::InstCombinerImpl::foldICmpEqIntrinsicWithConstant</a>, <a href="/web-llvm/docs/api/classes/llvm/instcombinerimpl/#acb575761ffbc75842def91257cc5168d">llvm::InstCombinerImpl::foldICmpEquality</a>, <a href="/web-llvm/docs/api/classes/llvm/instcombinerimpl/#a7df35aaa0732f4b23e5458034a2c29d1">llvm::InstCombinerImpl::foldICmpIntrinsicWithConstant</a>, <a href="/web-llvm/docs/api/classes/llvm/instcombinerimpl/#a1140591a375ac3efde57977192880eb0">llvm::InstCombinerImpl::foldICmpOrConstant</a>, <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/instcombine/instcombinecompares-cpp/#afb20557855b41f2b32ebd166b4d4b10f">foldICmpOrXX</a>, <a href="/web-llvm/docs/api/classes/llvm/instcombinerimpl/#a0550f165f22c1b1372bf6428191f0a9e">llvm::InstCombinerImpl::foldICmpSelectConstant</a>, <a href="/web-llvm/docs/api/classes/llvm/instcombinerimpl/#abe15d83fb0501730bbfe840143cedc08">llvm::InstCombinerImpl::foldICmpShlConstant</a>, <a href="/web-llvm/docs/api/classes/llvm/instcombinerimpl/#a037006a1d44974a6840403beb4febd30">llvm::InstCombinerImpl::foldICmpShrConstant</a>, <a href="/web-llvm/docs/api/classes/llvm/instcombinerimpl/#a06131a96d98381fd2b73c4ef401d416c">llvm::InstCombinerImpl::foldICmpSRemConstant</a>, <a href="/web-llvm/docs/api/classes/llvm/instcombinerimpl/#a39e315cb89b7144083895c083cc958e0">llvm::InstCombinerImpl::foldICmpSubConstant</a>, <a href="/web-llvm/docs/api/classes/llvm/instcombinerimpl/#a9bbadd565d3ba2855a90a04101d8d4cf">llvm::InstCombinerImpl::foldICmpTruncConstant</a>, <a href="/web-llvm/docs/api/classes/llvm/instcombinerimpl/#a157d508026592d1fdb9c78a3c3d34a06">llvm::InstCombinerImpl::foldICmpTruncWithTruncOrExt</a>, <a href="/web-llvm/docs/api/classes/llvm/instcombinerimpl/#a7c9fd9f2dba79c2289639f72457fcea1">llvm::InstCombinerImpl::foldICmpUsingBoolRange</a>, <a href="/web-llvm/docs/api/classes/llvm/instcombinerimpl/#a6c028a26ae2c72e9018e5a80713ba819">llvm::InstCombinerImpl::foldICmpWithConstant</a>, <a href="/web-llvm/docs/api/classes/llvm/instcombinerimpl/#af24dc3f2a89de0b400a681002927217d">llvm::InstCombinerImpl::foldICmpWithDominatingICmp</a>, <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/instcombine/instcombinecompares-cpp/#a566049e9c903d4e0067b8557d49c7d62">foldICmpWithLowBitMaskedVal</a>, <a href="/web-llvm/docs/api/classes/llvm/instcombinerimpl/#a7caf9cd5dff4734b8af500d6f0f07437">llvm::InstCombinerImpl::foldICmpWithTrunc</a>, <a href="/web-llvm/docs/api/classes/llvm/instcombinerimpl/#a04d40b2885dcf7e80feed09ba6209e54">llvm::InstCombinerImpl::foldICmpWithZextOrSext</a>, <a href="/web-llvm/docs/api/classes/llvm/instcombinerimpl/#abb66b7fb706f49e1966d64fa3ebeabfb">llvm::InstCombinerImpl::foldICmpXorShiftConst</a>, <a href="/web-llvm/docs/api/classes/llvm/instcombinerimpl/#a90148636c6d38a9475471b8b43e93b04">llvm::InstCombinerImpl::foldIRemByPowerOfTwoToBitTest</a>, <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/instcombine/instcombineandorxor-cpp/#a45705c727d8388c014471504b4ab0c4e">foldLogicCastConstant</a>, <a href="/web-llvm/docs/api/classes/llvm/instcombinerimpl/#a657815d57170937e7e75bee5ecf235ce">llvm::InstCombinerImpl::foldMultiplicationOverflowCheck</a>, <a href="/web-llvm/docs/api/classes/llvm/instcombinerimpl/#aed2c2c5e2a07649e02d6647d9a5c8852">llvm::InstCombinerImpl::foldPowiReassoc</a>, <a href="/web-llvm/docs/api/classes/llvm/instcombinerimpl/#aaa55d4e19334af5b17eb03205a1bece3">llvm::InstCombinerImpl::foldSelectICmp</a>, <a href="/web-llvm/docs/api/classes/llvm/instcombinerimpl/#a9eeb1caaa920e692849cb94d64b7d66f">llvm::InstCombinerImpl::foldSelectIntoOp</a>, <a href="/web-llvm/docs/api/classes/llvm/instcombinerimpl/#a4bd29d381405675f36964e4a5382dae4">llvm::InstCombinerImpl::foldSelectOpOp</a>, <a href="/web-llvm/docs/api/classes/llvm/instcombinerimpl/#a3b73df3a995af9ca26c9d024c957c45a">llvm::InstCombinerImpl::foldSelectShuffle</a>, <a href="/web-llvm/docs/api/classes/llvm/instcombinerimpl/#ad3f7f3eaea6d34ab9ade1af54174f5a2">llvm::InstCombinerImpl::FoldShiftByConstant</a>, <a href="/web-llvm/docs/api/classes/llvm/instcombinerimpl/#a4a128160ac46052a6accc9ba3e84ae08">llvm::InstCombinerImpl::foldSquareSumFP</a>, <a href="/web-llvm/docs/api/classes/llvm/instcombinerimpl/#a2f7fbcaeeb7e6d76fa71bf5abebcae45">llvm::InstCombinerImpl::foldSquareSumInt</a>, <a href="/web-llvm/docs/api/classes/llvm/instcombinerimpl/#a2511e442d198696042ad2a39cad89059">llvm::InstCombinerImpl::foldUsingDistributiveLaws</a>, <a href="/web-llvm/docs/api/classes/llvm/instcombinerimpl/#aa72b51b8f455c8a622bb6f8cc9c14860">llvm::InstCombinerImpl::foldVariableSignZeroExtensionOfVariableHighBitExtract</a>, <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/instcombine/instcombinecasts-cpp/#aa1c33c4fbbe149ca5deb130bca410ef2">foldVecExtTruncToExtElt</a>, <a href="/web-llvm/docs/api/classes/llvm/instcombinerimpl/#acbf4c17d9f1b9f6729602a3c2a6c5b9d">llvm::InstCombinerImpl::foldVectorBinop</a>, <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/instcombine/instcombinecasts-cpp/#aee3e98b16f1c8d8d8b30b9a459a6a602">foldVecTruncToExtElt</a>, <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/instcombine/instcombineandorxor-cpp/#a6bf246a84f7e8596777a0231fa7d7bc9">freelyInvert</a>, <a href="#ab1dfd539be512820814cce9f06adb250">getFreelyInverted</a>, <a href="#af11b32adde24fea55878e66dd7139362">getFreelyInverted</a>, <a href="#ab98cb2aaf6e757aac9c471f85f113a50">getFreelyInvertedImpl</a>, <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/instcombine/instcombineshifts-cpp/#ab2d3d519ed327a47cba69f5523785d2d">getShiftedValue</a>, <a href="/web-llvm/docs/api/classes/llvm/instcombinerimpl/#a33c929139a72254b75f7ebb9593af9a9">llvm::InstCombinerImpl::insertRangeTest</a>, <a href="/web-llvm/docs/api/classes/llvm/armttiimpl/#a5c10997d5aed59d126fc726249d8b561">llvm::ARMTTIImpl::instCombineIntrinsic</a>, <a href="/web-llvm/docs/api/classes/llvm/gcnttiimpl/#ae3d1835a72f8f0ba85ace9e2c0fbfc96">llvm::GCNTTIImpl::instCombineIntrinsic</a>, <a href="/web-llvm/docs/api/classes/llvm/ppcttiimpl/#a04dad23556e58f793c9a508a1a2d9aa5">llvm::PPCTTIImpl::instCombineIntrinsic</a>, <a href="/web-llvm/docs/api/classes/llvm/x86ttiimpl/#a47cb7185e35282131b486036ff7c45df">llvm::X86TTIImpl::instCombineIntrinsic</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64targettransforminfo-cpp/#a4e5c7b6a107ed8c6fa33ce4b8a6f97c2">instCombineLD1GatherIndex</a>, <a href="#af70e33de5e351fc22288a3130b0428b6">InstCombiner</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64targettransforminfo-cpp/#a7fcf73aaa1b218db266c0f9d4020ab3f">instCombineRDFFR</a>, <a href="/web-llvm/docs/api/classes/llvm/instcombinerimpl/#a3192aaa795b73ba7009f98fdad625080">llvm::InstCombinerImpl::InstCombinerImpl</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64targettransforminfo-cpp/#a5f64e951a3840e09ae4d21552754ec13">instCombineST1ScatterIndex</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64targettransforminfo-cpp/#a7915bab3089583402f61b46f7baea356">instCombineSVECmpNE</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64targettransforminfo-cpp/#aed4b32e0e8ed6a18607dde66ca4a433e">instCombineSVECntElts</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64targettransforminfo-cpp/#a965b006c5624011322112bb1f1325f8e">instCombineSVECondLast</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64targettransforminfo-cpp/#afdcb3be103dc32527286d0352eeacdd6">instCombineSVEDupqLane</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64targettransforminfo-cpp/#a777bb183e9f322303a06538caf0696b2">instCombineSVEDupX</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64targettransforminfo-cpp/#ae2f9543c1954e97e2887aab7c33e18b4">instCombineSVELast</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64targettransforminfo-cpp/#ac80824cf7bdae0e18c7032eb8ce5214c">instCombineSVELD1</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64targettransforminfo-cpp/#a9946a89352eee5ab78f0f3fc4fc18941">instCombineSVEPTest</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64targettransforminfo-cpp/#a6059af97420634905c86d144d23dab4e">instCombineSVESDIV</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64targettransforminfo-cpp/#a122aba3e4ce982c894eee6da09b1c234">instCombineSVESel</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64targettransforminfo-cpp/#accf1e11b7d8fcba73d2fe80110555e48">instCombineSVESrshl</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64targettransforminfo-cpp/#a6139b54e783a57871c92c1ac67e4be6e">instCombineSVEST1</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64targettransforminfo-cpp/#aba5cce04083b467217c8829a13e5b981">instCombineSVETBL</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64targettransforminfo-cpp/#a194bc0e605101ffd7f8249fcf88e45ca">instCombineSVEUnpack</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64targettransforminfo-cpp/#aac6aaf36d8c34dfd27b90fc04ea3c08f">instCombineSVEUzp1</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64targettransforminfo-cpp/#ab6151efab78587b3732ad634505a4dd0">instCombineSVEVectorBinOp</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64targettransforminfo-cpp/#a052318a71439e8ffd109c713d19b5926">instCombineSVEVectorFuseMulAddSub</a>, <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/instcombine/instcombineandorxor-cpp/#a2d3ce43f7795a8f4f6925bffbcc90279">matchDeMorgansLaws</a>, <a href="/web-llvm/docs/api/classes/llvm/instcombinerimpl/#a9d9df487d54cc5567b4e0b1c8e0120a8">llvm::InstCombinerImpl::mergeStoreIntoSuccessor</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/amdgpuinstcombineintrinsic-cpp/#a8a43e48d75ff4289fc2674097dab5d50">modifyIntrinsicCall</a>, <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/instcombine/instcombinemuldivrem-cpp/#a1d14a70b8f7a753dacc88586d6954900">narrowUDivURem</a>, <a href="/web-llvm/docs/api/classes/llvm/negator/#a2abe5e7f029b63c7b1bd29ac231ef7fa">llvm::Negator::Negate</a>, <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/instcombine/instcombinecasts-cpp/#a8f948dd0c375dfeb4cdf99bc33905e66">optimizeIntegerToVectorInsertions</a>, <a href="/web-llvm/docs/api/classes/llvm/instcombinerimpl/#a884253dce055eb76863ec81c061aef33">llvm::InstCombinerImpl::OptimizePointerDifference</a>, <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/instcombine/instcombinecasts-cpp/#a75e6b6bf03adf614aaf100a9afdcd612">optimizeVectorResizeWithIntegerBitCasts</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64targettransforminfo-cpp/#a53ef6f5be8cd25a33229fe16aca9d537">processPhiNode</a>, <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/instcombine/instcombinecompares-cpp/#aae87c326017fc14f5ba90a036e45438a">processUGT_ADDCST_ADD</a>, <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/instcombine/instcombinecompares-cpp/#a67cafe6badc04395d797929d9d4e8efe">processUMulZExtIdiom</a>, <a href="/web-llvm/docs/api/classes/llvm/instcombinerimpl/#ab7805c1d4f86c20199da1dd1fab589f0">llvm::InstCombinerImpl::pushFreezeToPreventPoisonFromPropagating</a>, <a href="/web-llvm/docs/api/classes/llvm/instcombinerimpl/#a4b2e9167fd714396a473ee5493c1350b">llvm::InstCombinerImpl::reassociateShiftAmtsOfTwoSameDirectionShifts</a>, <a href="/web-llvm/docs/api/classes/llvm/instcombinerimpl/#ac5d3cfa0755b34bcbd3f2298e9fa28ed">llvm::InstCombinerImpl::run</a>, <a href="/web-llvm/docs/api/classes/llvm/instcombinerimpl/#aa9bbead3db102aa9d3eaeb47e695db1a">llvm::InstCombinerImpl::SimplifyAddWithRemainder</a>, <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/instcombine/instcombineloadstorealloca-cpp/#a25ea6e038ccdef52ab01b0ee3da9ee52">simplifyAllocaArraySize</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/amdgpuinstcombineintrinsic-cpp/#aae1a4eb9b437e719a333c79f74c9a1b2">simplifyAMDGCNMemoryIntrinsicDemanded</a>, <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/instcombine/instcombineandorxor-cpp/#a2a50775521fbb289313bb39964dabae3">simplifyAndOrWithOpReplaced</a>, <a href="/web-llvm/docs/api/classes/llvm/instcombinerimpl/#a557f3c41bf651bbd713f9220c59f0b1a">llvm::InstCombinerImpl::SimplifyAnyMemSet</a>, <a href="/web-llvm/docs/api/classes/llvm/instcombinerimpl/#ae3e39244e3fac45ac81d2096353f2b38">llvm::InstCombinerImpl::SimplifyAnyMemTransfer</a>, <a href="/web-llvm/docs/api/classes/llvm/instcombinerimpl/#ab18666f9305cc63df7009c9e4ec0e35a">llvm::InstCombinerImpl::simplifyBinOpSplats</a>, <a href="/web-llvm/docs/api/classes/llvm/instcombinerimpl/#a4bb2cbb88b57c9a126549efe2134d1cb">llvm::InstCombinerImpl::SimplifyDemandedUseBits</a>, <a href="/web-llvm/docs/api/classes/llvm/x86ttiimpl/#afd63c73f7201b4ed318ed3a3c56b6cad">llvm::X86TTIImpl::simplifyDemandedVectorEltsIntrinsic</a>, <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/instcombine/instcombinecalls-cpp/#a5d184e552e67beabd9484eb437df86cb">simplifyInvariantGroupIntrinsic</a>, <a href="/web-llvm/docs/api/classes/llvm/instcombinerimpl/#aa4100f52d21246ec944e97fe1b64b124">llvm::InstCombinerImpl::simplifyRangeCheck</a>, <a href="/web-llvm/docs/api/classes/llvm/instcombinerimpl/#ad36c0bc30660bad4f2b79be90608ea60">llvm::InstCombinerImpl::SimplifySelectsFeedingBinaryOp</a>, <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/instcombine/instcombinephi-cpp/#a86ed982844e004af01652f203eda23c0">simplifyUsingControlFlow</a>, <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/instcombine/instcombinemuldivrem-cpp/#a2057625407debe603c4fb211d1cdc571">simplifyValueKnownNonZero</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/x86/x86instcombineintrinsic-cpp/#a06d646994f54f30c64dcb09a8c6d91f3">simplifyX86MaskedLoad</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/x86/x86instcombineintrinsic-cpp/#a708996b12b1b5e6ac2555880bdaeda64">simplifyX86MaskedStore</a>, <a href="/web-llvm/docs/api/classes/llvm/instcombinerimpl/#a4e2dd07eceeed7496e6c3df4d364c91e">llvm::InstCombinerImpl::sinkNotIntoLogicalOp</a>, <a href="/web-llvm/docs/api/classes/llvm/instcombinerimpl/#a8d44c548f74b3d233a248672402b5dd1">llvm::InstCombinerImpl::sinkNotIntoOtherHandOfLogicalOp</a>, <a href="/web-llvm/docs/api/classes/llvm/instcombinerimpl/#ac8cb4401526dd424f15566e4501792f7">llvm::InstCombinerImpl::SliceUpIllegalIntegerPHI</a>, <a href="/web-llvm/docs/api/classes/llvm/instcombinerimpl/#a3bc72a9347951e36bc3a991d6bfc44ea">llvm::InstCombinerImpl::takeLog2</a>, <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/instcombine/instcombinecompares-cpp/#abce78109fa7acac1ae7aa1b4ee1ce07f">transformToIndexedCompare</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64targettransforminfo-cpp/#a16774c131664a3e4cbc7ebc236f49c9e">tryCombineFromSVBoolBinOp</a>, <a href="/web-llvm/docs/api/classes/llvm/instcombinerimpl/#aebf722c3ce9439ef88175255d8669080">llvm::InstCombinerImpl::tryFactorizationFolds</a>, <a href="/web-llvm/docs/api/classes/llvm/instcombinerimpl/#aa4cf868b89270f2f699fdee46cb572a4">llvm::InstCombinerImpl::tryFoldInstWithCtpopWithNot</a>, <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/instcombine/instcombineloadstorealloca-cpp/#aa0014a4c2da32289f871b8d5a1aa538b">unpackLoadToAggregate</a>, <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/instcombine/instcombineloadstorealloca-cpp/#acce887569ed105b612c33053a3264608">unpackStoreToAggregate</a>, <a href="/web-llvm/docs/api/classes/llvm/instcombinerimpl/#a0a89a6b25b8a92fb896a994a36b74241">llvm::InstCombinerImpl::visitAdd</a>, <a href="/web-llvm/docs/api/classes/llvm/instcombinerimpl/#a648710a93ceb0bbddf0a2ae7a8bb2ca5">llvm::InstCombinerImpl::visitAnd</a>, <a href="/web-llvm/docs/api/classes/llvm/instcombinerimpl/#a612d91fe0858006abe73d7b62821da0c">llvm::InstCombinerImpl::visitAShr</a>, <a href="/web-llvm/docs/api/classes/llvm/instcombinerimpl/#a89ab5eaec7693029761c8d0b3ded3b00">llvm::InstCombinerImpl::visitBitCast</a>, <a href="/web-llvm/docs/api/classes/llvm/instcombinerimpl/#aea9ba5a362fb88bd97349a302133dd03">llvm::InstCombinerImpl::visitBranchInst</a>, <a href="/web-llvm/docs/api/classes/llvm/instcombinerimpl/#afa2581e2e1ac6959cd02e28062a7c1d5">llvm::InstCombinerImpl::visitCallInst</a>, <a href="/web-llvm/docs/api/classes/llvm/instcombinerimpl/#a71ef354bd1ea9e02d70146d7218a7d39">llvm::InstCombinerImpl::visitExtractElementInst</a>, <a href="/web-llvm/docs/api/classes/llvm/instcombinerimpl/#a679f36556ace611ccc56580cb497973a">llvm::InstCombinerImpl::visitExtractValueInst</a>, <a href="/web-llvm/docs/api/classes/llvm/instcombinerimpl/#a92fdf04445f26ef88ea0e134408b30fe">llvm::InstCombinerImpl::visitFAdd</a>, <a href="/web-llvm/docs/api/classes/llvm/instcombinerimpl/#a86b0437dceb8e39c8185dc7def325011">llvm::InstCombinerImpl::visitFCmpInst</a>, <a href="/web-llvm/docs/api/classes/llvm/instcombinerimpl/#a5457b45fe74cf2f411f5824d32fd389d">llvm::InstCombinerImpl::visitFDiv</a>, <a href="/web-llvm/docs/api/classes/llvm/instcombinerimpl/#abf257c2c6dadfee6ee83fabb6ea77c4f">llvm::InstCombinerImpl::visitFMul</a>, <a href="/web-llvm/docs/api/classes/llvm/instcombinerimpl/#af616ac59efde7c61f6e8ff8bd80d2027">llvm::InstCombinerImpl::visitFNeg</a>, <a href="/web-llvm/docs/api/classes/llvm/instcombinerimpl/#a7eb1707b3b9ea994955ac9d230535261">llvm::InstCombinerImpl::visitFPTrunc</a>, <a href="/web-llvm/docs/api/classes/llvm/instcombinerimpl/#afa72f4f7fc2ee2bf6cd3b64bd07c37e8">llvm::InstCombinerImpl::visitFSub</a>, <a href="/web-llvm/docs/api/classes/llvm/instcombinerimpl/#a22bc54f319e33d248b169116b757a143">llvm::InstCombinerImpl::visitGEPOfGEP</a>, <a href="/web-llvm/docs/api/classes/llvm/instcombinerimpl/#ae755d569b6e5c69a8abbc6de50cf3f6b">llvm::InstCombinerImpl::visitGetElementPtrInst</a>, <a href="/web-llvm/docs/api/classes/llvm/instcombinerimpl/#ae31c50e938b95587c87aed0f133b1346">llvm::InstCombinerImpl::visitICmpInst</a>, <a href="/web-llvm/docs/api/classes/llvm/instcombinerimpl/#a687fa4390149f0cb751d8ad89dca6a3c">llvm::InstCombinerImpl::visitInsertElementInst</a>, <a href="/web-llvm/docs/api/classes/llvm/instcombinerimpl/#a9567d315d63f844326900f461f5b3d7a">llvm::InstCombinerImpl::visitIntToPtr</a>, <a href="/web-llvm/docs/api/classes/llvm/instcombinerimpl/#a3ba96a0d49ec5f1a062b075f54536a3c">llvm::InstCombinerImpl::visitLoadInst</a>, <a href="/web-llvm/docs/api/classes/llvm/instcombinerimpl/#a197424adbab353be4587e6dfaee445e3">llvm::InstCombinerImpl::visitLShr</a>, <a href="/web-llvm/docs/api/classes/llvm/instcombinerimpl/#a01ed915fb2acf9fd660ca752edeec0db">llvm::InstCombinerImpl::visitMul</a>, <a href="/web-llvm/docs/api/classes/llvm/instcombinerimpl/#a1e893463cbb4b5e2e3830b2e4c28cbdb">llvm::InstCombinerImpl::visitOr</a>, <a href="/web-llvm/docs/api/classes/llvm/instcombinerimpl/#a50b0daca4f05a8d2af14aec07f64f3cc">llvm::InstCombinerImpl::visitPtrToInt</a>, <a href="/web-llvm/docs/api/classes/llvm/instcombinerimpl/#af12904244ec179b265540ed1fb8c6615">llvm::InstCombinerImpl::visitSDiv</a>, <a href="/web-llvm/docs/api/classes/llvm/instcombinerimpl/#a2a5120238e6845643a37d5a4675a5342">llvm::InstCombinerImpl::visitSExt</a>, <a href="/web-llvm/docs/api/classes/llvm/instcombinerimpl/#a90fcdfa591c9bd0cf511f2803198b355">llvm::InstCombinerImpl::visitShl</a>, <a href="/web-llvm/docs/api/classes/llvm/instcombinerimpl/#ad31108b4f7156db7565eadba1285c93a">llvm::InstCombinerImpl::visitShuffleVectorInst</a>, <a href="/web-llvm/docs/api/classes/llvm/instcombinerimpl/#a411aa95504f966614c8f5d5aeeef1f04">llvm::InstCombinerImpl::visitSRem</a>, <a href="/web-llvm/docs/api/classes/llvm/instcombinerimpl/#a606601489498c1ba41f25e77eb2dd0cf">llvm::InstCombinerImpl::visitSub</a>, <a href="/web-llvm/docs/api/classes/llvm/instcombinerimpl/#a91100900b6eb1ae18127f1e1f8f8a40e">llvm::InstCombinerImpl::visitSwitchInst</a>, <a href="/web-llvm/docs/api/classes/llvm/instcombinerimpl/#a43a1d060dacb05eb645cf91ea86d7bd3">llvm::InstCombinerImpl::visitTrunc</a>, <a href="/web-llvm/docs/api/classes/llvm/instcombinerimpl/#a1cdbee2aa0ed532c8d9e91a00cc91f37">llvm::InstCombinerImpl::visitUDiv</a>, <a href="/web-llvm/docs/api/classes/llvm/instcombinerimpl/#a2f39b95e8efb44737439c323b18a55d7">llvm::InstCombinerImpl::visitURem</a>, <a href="/web-llvm/docs/api/classes/llvm/instcombinerimpl/#aaf7b6cd7c3ceb4af17b610cba09648c9">llvm::InstCombinerImpl::visitXor</a> and <a href="/web-llvm/docs/api/classes/llvm/instcombinerimpl/#a2175862566372c3684fe4f7bf62e3143">llvm::InstCombinerImpl::visitZExt</a>.</p>

</div>
</div>

### MaxArraySizeForCombine {#a4bc1fafcc9582581002518df62792214}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">uint64_t llvm::InstCombiner::MaxArraySizeForCombine = 0</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Maximum size of array considered when transforming.</p>

<p>Definition at line 56 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/transforms/include/llvm/transforms/instcombine/instcombiner-h">InstCombiner.h</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/instcombine/instructioncombining-cpp/#a45a945c85468ec7d17b48b0d4f612b7e">combineInstructionsOverFunction</a>, <a href="/web-llvm/docs/api/classes/llvm/instcombinerimpl/#a866883cec7ed781fcf1e9cda18b24f5b">llvm::InstCombinerImpl::foldCmpLoadFromIndexedGlobal</a>, <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/instcombine/instcombineloadstorealloca-cpp/#aa0014a4c2da32289f871b8d5a1aa538b">unpackLoadToAggregate</a> and <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/instcombine/instcombineloadstorealloca-cpp/#acce887569ed105b612c33053a3264608">unpackStoreToAggregate</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Protected Member Attributes

### AA {#a4764870a6b87dce34acb4e5eaef32e42}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">AAResults* llvm::InstCombiner::AA</td>
</tr>
</table>
</td>
<td class="doxyMemberLabelsRight">
<span class="doxyMemberLabels">
<span class="doxyMemberLabel protected">protected</span>
</span>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 70 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/transforms/include/llvm/transforms/instcombine/instcombiner-h">InstCombiner.h</a>.</p>


<p>Referenced by <a href="#af70e33de5e351fc22288a3130b0428b6">InstCombiner</a>, <a href="/web-llvm/docs/api/classes/llvm/instcombinerimpl/#a3192aaa795b73ba7009f98fdad625080">llvm::InstCombinerImpl::InstCombinerImpl</a>, <a href="/web-llvm/docs/api/classes/llvm/instcombinerimpl/#a557f3c41bf651bbd713f9220c59f0b1a">llvm::InstCombinerImpl::SimplifyAnyMemSet</a>, <a href="/web-llvm/docs/api/classes/llvm/instcombinerimpl/#ae3e39244e3fac45ac81d2096353f2b38">llvm::InstCombinerImpl::SimplifyAnyMemTransfer</a>, <a href="/web-llvm/docs/api/classes/llvm/instcombinerimpl/#af99540103c8717d41b490fc2a1acad5c">llvm::InstCombinerImpl::visitAllocaInst</a>, <a href="/web-llvm/docs/api/classes/llvm/instcombinerimpl/#ae289e620828eabb1dfe34c9ad322a81d">llvm::InstCombinerImpl::visitAllocSite</a>, <a href="/web-llvm/docs/api/classes/llvm/instcombinerimpl/#afa2581e2e1ac6959cd02e28062a7c1d5">llvm::InstCombinerImpl::visitCallInst</a>, <a href="/web-llvm/docs/api/classes/llvm/instcombinerimpl/#a3ba96a0d49ec5f1a062b075f54536a3c">llvm::InstCombinerImpl::visitLoadInst</a> and <a href="/web-llvm/docs/api/classes/llvm/instcombinerimpl/#a8042dd4cb7e9772368f2808b8db577be">llvm::InstCombinerImpl::visitStoreInst</a>.</p>

</div>
</div>

### AC {#ab63bb17a04c3e86b58219750716899a9}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">AssumptionCache&amp; llvm::InstCombiner::AC</td>
</tr>
</table>
</td>
<td class="doxyMemberLabelsRight">
<span class="doxyMemberLabels">
<span class="doxyMemberLabel protected">protected</span>
</span>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 73 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/transforms/include/llvm/transforms/instcombine/instcombiner-h">InstCombiner.h</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/classes/llvm/instcombinerimpl/#aa831d259fa5719e16927b5f4877988db">llvm::InstCombinerImpl::commonShiftTransforms</a>, <a href="#afe741651c79e1ff35939d1c04a3a191b">ComputeMaxSignificantBits</a>, <a href="#a879221accd38e1327b8dcf596650b031">ComputeNumSignBits</a>, <a href="/web-llvm/docs/api/classes/llvm/instcombinerimpl/#a36ef4128d8b08242e337bcbed0dce3c8">llvm::InstCombinerImpl::foldICmpBinOp</a>, <a href="#ae2eddfa57a32ec610ce9685720d591b7">getAssumptionCache</a>, <a href="#af70e33de5e351fc22288a3130b0428b6">InstCombiner</a>, <a href="/web-llvm/docs/api/classes/llvm/instcombinerimpl/#a3192aaa795b73ba7009f98fdad625080">llvm::InstCombinerImpl::InstCombinerImpl</a>, <a href="/web-llvm/docs/api/classes/llvm/instcombinerimpl/#aa9bbead3db102aa9d3eaeb47e695db1a">llvm::InstCombinerImpl::SimplifyAddWithRemainder</a>, <a href="/web-llvm/docs/api/classes/llvm/instcombinerimpl/#a557f3c41bf651bbd713f9220c59f0b1a">llvm::InstCombinerImpl::SimplifyAnyMemSet</a>, <a href="/web-llvm/docs/api/classes/llvm/instcombinerimpl/#ae3e39244e3fac45ac81d2096353f2b38">llvm::InstCombinerImpl::SimplifyAnyMemTransfer</a>, <a href="/web-llvm/docs/api/classes/llvm/instcombinerimpl/#af99540103c8717d41b490fc2a1acad5c">llvm::InstCombinerImpl::visitAllocaInst</a> and <a href="/web-llvm/docs/api/classes/llvm/instcombinerimpl/#afa2581e2e1ac6959cd02e28062a7c1d5">llvm::InstCombinerImpl::visitCallInst</a>.</p>

</div>
</div>

### BackEdges {#abca480cb3ed0ecf3fe3bde76bdf4b230}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">SmallDenseSet&lt;std::pair&lt;const BasicBlock *, const BasicBlock *&gt;, 8&gt; llvm::InstCombiner::BackEdges</td>
</tr>
</table>
</td>
<td class="doxyMemberLabelsRight">
<span class="doxyMemberLabels">
<span class="doxyMemberLabel protected">protected</span>
</span>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Backedges, used to avoid pushing instructions across backedges in cases where this may result in infinite combine loops.</p>


<p>For irreducible loops this picks an arbitrary backedge.</p>


<p>Definition at line 97 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/transforms/include/llvm/transforms/instcombine/instcombiner-h">InstCombiner.h</a>.</p>


<p>Referenced by <a href="#ac17fa2d851e729e9c308df593b098fc1">computeBackEdges</a> and <a href="#af5a8feb3d194df1e72e6a32cc746bc97">isBackEdge</a>.</p>

</div>
</div>

### BFI {#a25e411550ff000d1660e2376e3ae2ef8}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">BlockFrequencyInfo* llvm::InstCombiner::BFI</td>
</tr>
</table>
</td>
<td class="doxyMemberLabelsRight">
<span class="doxyMemberLabels">
<span class="doxyMemberLabel protected">protected</span>
</span>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 79 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/transforms/include/llvm/transforms/instcombine/instcombiner-h">InstCombiner.h</a>.</p>


<p>Referenced by <a href="#a441e8056feed591b0e0fd1b2a6ac81c0">getBlockFrequencyInfo</a>, <a href="#af70e33de5e351fc22288a3130b0428b6">InstCombiner</a> and <a href="/web-llvm/docs/api/classes/llvm/instcombinerimpl/#a3192aaa795b73ba7009f98fdad625080">llvm::InstCombinerImpl::InstCombinerImpl</a>.</p>

</div>
</div>

### BPI {#a7f74e84c9b2bc2441706161c2ed9cc5a}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">BranchProbabilityInfo* llvm::InstCombiner::BPI</td>
</tr>
</table>
</td>
<td class="doxyMemberLabelsRight">
<span class="doxyMemberLabels">
<span class="doxyMemberLabel protected">protected</span>
</span>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 80 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/transforms/include/llvm/transforms/instcombine/instcombiner-h">InstCombiner.h</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/classes/llvm/instcombinerimpl/#af8c1d39848b445bea8e307b53f81c481">llvm::InstCombinerImpl::freelyInvertAllUsersOf</a>, <a href="#af70e33de5e351fc22288a3130b0428b6">InstCombiner</a>, <a href="/web-llvm/docs/api/classes/llvm/instcombinerimpl/#a3192aaa795b73ba7009f98fdad625080">llvm::InstCombinerImpl::InstCombinerImpl</a> and <a href="/web-llvm/docs/api/classes/llvm/instcombinerimpl/#aea9ba5a362fb88bd97349a302133dd03">llvm::InstCombinerImpl::visitBranchInst</a>.</p>

</div>
</div>

### ComputedBackEdges {#a577df1f2641fe6bf067c364d94154cf1}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool llvm::InstCombiner::ComputedBackEdges = false</td>
</tr>
</table>
</td>
<td class="doxyMemberLabelsRight">
<span class="doxyMemberLabels">
<span class="doxyMemberLabel protected">protected</span>
</span>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 98 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/transforms/include/llvm/transforms/instcombine/instcombiner-h">InstCombiner.h</a>.</p>


<p>Referenced by <a href="#ac17fa2d851e729e9c308df593b098fc1">computeBackEdges</a> and <a href="#af5a8feb3d194df1e72e6a32cc746bc97">isBackEdge</a>.</p>

</div>
</div>

### DC {#a888ebf4b0f794a1c13741d38f0c4aa61}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">DomConditionCache llvm::InstCombiner::DC</td>
</tr>
</table>
</td>
<td class="doxyMemberLabelsRight">
<span class="doxyMemberLabels">
<span class="doxyMemberLabel protected">protected</span>
</span>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 82 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/transforms/include/llvm/transforms/instcombine/instcombiner-h">InstCombiner.h</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/classes/llvm/instcombinerimpl/#a6fc7cb23fbdc2e353fdf2f3aa5212e92">llvm::InstCombinerImpl::eraseInstFromFunction</a>, <a href="/web-llvm/docs/api/classes/llvm/instcombinerimpl/#af24dc3f2a89de0b400a681002927217d">llvm::InstCombinerImpl::foldICmpWithDominatingICmp</a>, <a href="#af70e33de5e351fc22288a3130b0428b6">InstCombiner</a> and <a href="/web-llvm/docs/api/classes/llvm/instcombinerimpl/#aea9ba5a362fb88bd97349a302133dd03">llvm::InstCombinerImpl::visitBranchInst</a>.</p>

</div>
</div>

### DeadEdges {#ad9606d00d0f1d7488ee416b25857f223}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">SmallDenseSet&lt;std::pair&lt;BasicBlock *, BasicBlock *&gt;, 8&gt; llvm::InstCombiner::DeadEdges</td>
</tr>
</table>
</td>
<td class="doxyMemberLabelsRight">
<span class="doxyMemberLabels">
<span class="doxyMemberLabel protected">protected</span>
</span>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Edges that are known to never be taken.</p>

<p>Definition at line 89 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/transforms/include/llvm/transforms/instcombine/instcombiner-h">InstCombiner.h</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/classes/llvm/instcombinerimpl/#ad6aa61c7462784d1c9641ee501486375">llvm::InstCombinerImpl::addDeadEdge</a>, <a href="/web-llvm/docs/api/classes/llvm/instcombinerimpl/#a4e25c5f8a8a770362e0ab9dcaa167dab">llvm::InstCombinerImpl::handlePotentiallyDeadBlocks</a> and <a href="/web-llvm/docs/api/classes/llvm/instcombinerimpl/#a51dffbda74e47e34a64858d09d456108">llvm::InstCombinerImpl::prepareWorklist</a>.</p>

</div>
</div>

### DL {#a878e8128a9a4e5626df91dcd91cba337}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">const DataLayout&amp; llvm::InstCombiner::DL</td>
</tr>
</table>
</td>
<td class="doxyMemberLabelsRight">
<span class="doxyMemberLabels">
<span class="doxyMemberLabel protected">protected</span>
</span>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 76 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/transforms/include/llvm/transforms/instcombine/instcombiner-h">InstCombiner.h</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/classes/llvm/instcombinerimpl/#a6adc65f05e61f4929966c0e4429c6fc7">llvm::InstCombinerImpl::commonCastTransforms</a>, <a href="#afe741651c79e1ff35939d1c04a3a191b">ComputeMaxSignificantBits</a>, <a href="#a879221accd38e1327b8dcf596650b031">ComputeNumSignBits</a>, <a href="/web-llvm/docs/api/classes/llvm/instcombinerimpl/#ab05ba39ce6e678149dabd939c9ad4c3e">llvm::InstCombinerImpl::EvaluateInDifferentType</a>, <a href="/web-llvm/docs/api/classes/llvm/instcombinerimpl/#a295de4cfe04f8cf0dee3bc16c78e5f13">llvm::InstCombinerImpl::foldBinOpShiftWithShift</a>, <a href="/web-llvm/docs/api/classes/llvm/instcombinerimpl/#a9317f2efaf85a4afc7cde58a2c0d734b">llvm::InstCombinerImpl::foldBinopWithPhiOperands</a>, <a href="/web-llvm/docs/api/classes/llvm/instcombinerimpl/#a866883cec7ed781fcf1e9cda18b24f5b">llvm::InstCombinerImpl::foldCmpLoadFromIndexedGlobal</a>, <a href="/web-llvm/docs/api/classes/llvm/instcombinerimpl/#ac633a4c4d399457c76640f7dea5ebcd7">llvm::InstCombinerImpl::foldFMulReassoc</a>, <a href="/web-llvm/docs/api/classes/llvm/instcombinerimpl/#afc78cb7aeb92b0fc9223239dd827f7e3">llvm::InstCombinerImpl::foldGEPICmp</a>, <a href="/web-llvm/docs/api/classes/llvm/instcombinerimpl/#a36ef4128d8b08242e337bcbed0dce3c8">llvm::InstCombinerImpl::foldICmpBinOp</a>, <a href="/web-llvm/docs/api/classes/llvm/instcombinerimpl/#a3d58c11c9787c2764e5f11bb127ced00">llvm::InstCombinerImpl::foldICmpInstWithConstantNotInt</a>, <a href="/web-llvm/docs/api/classes/llvm/instcombinerimpl/#a8de411243dcb508d9d512006edaba1ec">llvm::InstCombinerImpl::foldICmpUsingKnownBits</a>, <a href="/web-llvm/docs/api/classes/llvm/instcombinerimpl/#a9ab27a13577b53506529f28d41aa0672">llvm::InstCombinerImpl::foldICmpWithCastOp</a>, <a href="/web-llvm/docs/api/classes/llvm/instcombinerimpl/#a6c028a26ae2c72e9018e5a80713ba819">llvm::InstCombinerImpl::foldICmpWithConstant</a>, <a href="/web-llvm/docs/api/classes/llvm/instcombinerimpl/#aab1473644ffe7926032a4e01ed4bad78">llvm::InstCombinerImpl::foldIntegerTypedPHI</a>, <a href="/web-llvm/docs/api/classes/llvm/instcombinerimpl/#a2fc50d227d302eb98914f04bcc6634e1">llvm::InstCombinerImpl::foldOpIntoPhi</a>, <a href="/web-llvm/docs/api/classes/llvm/instcombinerimpl/#aaa55d4e19334af5b17eb03205a1bece3">llvm::InstCombinerImpl::foldSelectICmp</a>, <a href="/web-llvm/docs/api/classes/llvm/instcombinerimpl/#a3b73df3a995af9ca26c9d024c957c45a">llvm::InstCombinerImpl::foldSelectShuffle</a>, <a href="/web-llvm/docs/api/classes/llvm/instcombinerimpl/#ad3f7f3eaea6d34ab9ade1af54174f5a2">llvm::InstCombinerImpl::FoldShiftByConstant</a>, <a href="/web-llvm/docs/api/classes/llvm/instcombinerimpl/#acbf4c17d9f1b9f6729602a3c2a6c5b9d">llvm::InstCombinerImpl::foldVectorBinop</a>, <a href="#a16262e69f9cdf5d2c9d5623c3b06af43">getDataLayout</a>, <a href="/web-llvm/docs/api/classes/llvm/instcombinerimpl/#a97d3f5c1aaad9cd86d8f6e9596473891">llvm::InstCombinerImpl::getLosslessTrunc</a>, <a href="#af70e33de5e351fc22288a3130b0428b6">InstCombiner</a>, <a href="/web-llvm/docs/api/classes/llvm/instcombinerimpl/#a3192aaa795b73ba7009f98fdad625080">llvm::InstCombinerImpl::InstCombinerImpl</a>, <a href="/web-llvm/docs/api/classes/llvm/instcombinerimpl/#a9d9df487d54cc5567b4e0b1c8e0120a8">llvm::InstCombinerImpl::mergeStoreIntoSuccessor</a>, <a href="/web-llvm/docs/api/classes/llvm/instcombinerimpl/#a51dffbda74e47e34a64858d09d456108">llvm::InstCombinerImpl::prepareWorklist</a>, <a href="/web-llvm/docs/api/classes/llvm/instcombinerimpl/#a557f3c41bf651bbd713f9220c59f0b1a">llvm::InstCombinerImpl::SimplifyAnyMemSet</a>, <a href="/web-llvm/docs/api/classes/llvm/instcombinerimpl/#ae3e39244e3fac45ac81d2096353f2b38">llvm::InstCombinerImpl::SimplifyAnyMemTransfer</a>, <a href="/web-llvm/docs/api/classes/llvm/instcombinerimpl/#a225d5b1dcc0015e743f1dbbf348a9c36">llvm::InstCombinerImpl::SimplifyAssociativeOrCommutative</a>, <a href="/web-llvm/docs/api/classes/llvm/instcombinerimpl/#ab133fcc8ac42264ff3425cea7b6642bc">llvm::InstCombinerImpl::SimplifyDemandedInstructionBits</a>, <a href="/web-llvm/docs/api/classes/llvm/instcombinerimpl/#a4bb2cbb88b57c9a126549efe2134d1cb">llvm::InstCombinerImpl::SimplifyDemandedUseBits</a>, <a href="/web-llvm/docs/api/classes/llvm/instcombinerimpl/#aa4cf868b89270f2f699fdee46cb572a4">llvm::InstCombinerImpl::tryFoldInstWithCtpopWithNot</a>, <a href="/web-llvm/docs/api/classes/llvm/instcombinerimpl/#af99540103c8717d41b490fc2a1acad5c">llvm::InstCombinerImpl::visitAllocaInst</a>, <a href="/web-llvm/docs/api/classes/llvm/instcombinerimpl/#ae289e620828eabb1dfe34c9ad322a81d">llvm::InstCombinerImpl::visitAllocSite</a>, <a href="/web-llvm/docs/api/classes/llvm/instcombinerimpl/#a648710a93ceb0bbddf0a2ae7a8bb2ca5">llvm::InstCombinerImpl::visitAnd</a>, <a href="/web-llvm/docs/api/classes/llvm/instcombinerimpl/#a89ab5eaec7693029761c8d0b3ded3b00">llvm::InstCombinerImpl::visitBitCast</a>, <a href="/web-llvm/docs/api/classes/llvm/instcombinerimpl/#afa2581e2e1ac6959cd02e28062a7c1d5">llvm::InstCombinerImpl::visitCallInst</a>, <a href="/web-llvm/docs/api/classes/llvm/instcombinerimpl/#a92fdf04445f26ef88ea0e134408b30fe">llvm::InstCombinerImpl::visitFAdd</a>, <a href="/web-llvm/docs/api/classes/llvm/instcombinerimpl/#a86b0437dceb8e39c8185dc7def325011">llvm::InstCombinerImpl::visitFCmpInst</a>, <a href="/web-llvm/docs/api/classes/llvm/instcombinerimpl/#abf257c2c6dadfee6ee83fabb6ea77c4f">llvm::InstCombinerImpl::visitFMul</a>, <a href="/web-llvm/docs/api/classes/llvm/instcombinerimpl/#af616ac59efde7c61f6e8ff8bd80d2027">llvm::InstCombinerImpl::visitFNeg</a>, <a href="/web-llvm/docs/api/classes/llvm/instcombinerimpl/#a629e02c312173d0da1b62288bc8fbd48">llvm::InstCombinerImpl::visitFree</a>, <a href="/web-llvm/docs/api/classes/llvm/instcombinerimpl/#afa72f4f7fc2ee2bf6cd3b64bd07c37e8">llvm::InstCombinerImpl::visitFSub</a>, <a href="/web-llvm/docs/api/classes/llvm/instcombinerimpl/#a22bc54f319e33d248b169116b757a143">llvm::InstCombinerImpl::visitGEPOfGEP</a>, <a href="/web-llvm/docs/api/classes/llvm/instcombinerimpl/#ae755d569b6e5c69a8abbc6de50cf3f6b">llvm::InstCombinerImpl::visitGetElementPtrInst</a>, <a href="/web-llvm/docs/api/classes/llvm/instcombinerimpl/#ae31c50e938b95587c87aed0f133b1346">llvm::InstCombinerImpl::visitICmpInst</a>, <a href="/web-llvm/docs/api/classes/llvm/instcombinerimpl/#a687fa4390149f0cb751d8ad89dca6a3c">llvm::InstCombinerImpl::visitInsertElementInst</a>, <a href="/web-llvm/docs/api/classes/llvm/instcombinerimpl/#a9567d315d63f844326900f461f5b3d7a">llvm::InstCombinerImpl::visitIntToPtr</a>, <a href="/web-llvm/docs/api/classes/llvm/instcombinerimpl/#a3ba96a0d49ec5f1a062b075f54536a3c">llvm::InstCombinerImpl::visitLoadInst</a>, <a href="/web-llvm/docs/api/classes/llvm/instcombinerimpl/#a01ed915fb2acf9fd660ca752edeec0db">llvm::InstCombinerImpl::visitMul</a>, <a href="/web-llvm/docs/api/classes/llvm/instcombinerimpl/#a50b0daca4f05a8d2af14aec07f64f3cc">llvm::InstCombinerImpl::visitPtrToInt</a>, <a href="/web-llvm/docs/api/classes/llvm/instcombinerimpl/#a2a5120238e6845643a37d5a4675a5342">llvm::InstCombinerImpl::visitSExt</a>, <a href="/web-llvm/docs/api/classes/llvm/instcombinerimpl/#ad31108b4f7156db7565eadba1285c93a">llvm::InstCombinerImpl::visitShuffleVectorInst</a>, <a href="/web-llvm/docs/api/classes/llvm/instcombinerimpl/#a606601489498c1ba41f25e77eb2dd0cf">llvm::InstCombinerImpl::visitSub</a> and <a href="/web-llvm/docs/api/classes/llvm/instcombinerimpl/#a43a1d060dacb05eb645cf91ea86d7bd3">llvm::InstCombinerImpl::visitTrunc</a>.</p>

</div>
</div>

### DT {#ac881b40b83c0bd8934689bdc8c306cf5}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">DominatorTree&amp; llvm::InstCombiner::DT</td>
</tr>
</table>
</td>
<td class="doxyMemberLabelsRight">
<span class="doxyMemberLabels">
<span class="doxyMemberLabel protected">protected</span>
</span>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 75 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/transforms/include/llvm/transforms/instcombine/instcombiner-h">InstCombiner.h</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/classes/llvm/instcombinerimpl/#a6adc65f05e61f4929966c0e4429c6fc7">llvm::InstCombinerImpl::commonCastTransforms</a>, <a href="#afe741651c79e1ff35939d1c04a3a191b">ComputeMaxSignificantBits</a>, <a href="#a879221accd38e1327b8dcf596650b031">ComputeNumSignBits</a>, <a href="/web-llvm/docs/api/classes/llvm/instcombinerimpl/#a52d249cc9856fb556e92d5a1b03e5e80">llvm::InstCombinerImpl::convertOrOfShiftsToFunnelShift</a>, <a href="/web-llvm/docs/api/classes/llvm/instcombinerimpl/#ad3f2b185fd3e7dd4d0e694e773792fb8">llvm::InstCombinerImpl::dominatesAllUses</a>, <a href="/web-llvm/docs/api/classes/llvm/instcombinerimpl/#a9317f2efaf85a4afc7cde58a2c0d734b">llvm::InstCombinerImpl::foldBinopWithPhiOperands</a>, <a href="/web-llvm/docs/api/classes/llvm/instcombinerimpl/#aef28063eb280fec69a391dd35c51666e">llvm::InstCombinerImpl::foldFreezeIntoRecurrence</a>, <a href="/web-llvm/docs/api/classes/llvm/instcombinerimpl/#a36ef4128d8b08242e337bcbed0dce3c8">llvm::InstCombinerImpl::foldICmpBinOp</a>, <a href="/web-llvm/docs/api/classes/llvm/instcombinerimpl/#af24dc3f2a89de0b400a681002927217d">llvm::InstCombinerImpl::foldICmpWithDominatingICmp</a>, <a href="/web-llvm/docs/api/classes/llvm/instcombinerimpl/#aab1473644ffe7926032a4e01ed4bad78">llvm::InstCombinerImpl::foldIntegerTypedPHI</a>, <a href="/web-llvm/docs/api/classes/llvm/instcombinerimpl/#a2fc50d227d302eb98914f04bcc6634e1">llvm::InstCombinerImpl::foldOpIntoPhi</a>, <a href="/web-llvm/docs/api/classes/llvm/instcombinerimpl/#af59c587eddc75748a1e201369cd3dbac">llvm::InstCombinerImpl::freezeOtherUses</a>, <a href="#a209240824927e66a0caa50636623e79a">getDominatorTree</a>, <a href="/web-llvm/docs/api/classes/llvm/instcombinerimpl/#a4e25c5f8a8a770362e0ab9dcaa167dab">llvm::InstCombinerImpl::handlePotentiallyDeadBlocks</a>, <a href="#af70e33de5e351fc22288a3130b0428b6">InstCombiner</a>, <a href="/web-llvm/docs/api/classes/llvm/instcombinerimpl/#a3192aaa795b73ba7009f98fdad625080">llvm::InstCombinerImpl::InstCombinerImpl</a>, <a href="/web-llvm/docs/api/classes/llvm/instcombinerimpl/#a51dffbda74e47e34a64858d09d456108">llvm::InstCombinerImpl::prepareWorklist</a>, <a href="/web-llvm/docs/api/classes/llvm/instcombinerimpl/#ac5d3cfa0755b34bcbd3f2298e9fa28ed">llvm::InstCombinerImpl::run</a>, <a href="/web-llvm/docs/api/classes/llvm/instcombinerimpl/#aa9bbead3db102aa9d3eaeb47e695db1a">llvm::InstCombinerImpl::SimplifyAddWithRemainder</a>, <a href="/web-llvm/docs/api/classes/llvm/instcombinerimpl/#a557f3c41bf651bbd713f9220c59f0b1a">llvm::InstCombinerImpl::SimplifyAnyMemSet</a>, <a href="/web-llvm/docs/api/classes/llvm/instcombinerimpl/#ae3e39244e3fac45ac81d2096353f2b38">llvm::InstCombinerImpl::SimplifyAnyMemTransfer</a>, <a href="/web-llvm/docs/api/classes/llvm/instcombinerimpl/#a37cce7aa1875173688e5971c5d6fa9e0">llvm::InstCombinerImpl::SimplifyDemandedVectorElts</a>, <a href="/web-llvm/docs/api/classes/llvm/instcombinerimpl/#af99540103c8717d41b490fc2a1acad5c">llvm::InstCombinerImpl::visitAllocaInst</a>, <a href="/web-llvm/docs/api/classes/llvm/instcombinerimpl/#a648710a93ceb0bbddf0a2ae7a8bb2ca5">llvm::InstCombinerImpl::visitAnd</a>, <a href="/web-llvm/docs/api/classes/llvm/instcombinerimpl/#aea9ba5a362fb88bd97349a302133dd03">llvm::InstCombinerImpl::visitBranchInst</a>, <a href="/web-llvm/docs/api/classes/llvm/instcombinerimpl/#afa2581e2e1ac6959cd02e28062a7c1d5">llvm::InstCombinerImpl::visitCallInst</a>, <a href="/web-llvm/docs/api/classes/llvm/instcombinerimpl/#a1e893463cbb4b5e2e3830b2e4c28cbdb">llvm::InstCombinerImpl::visitOr</a> and <a href="/web-llvm/docs/api/classes/llvm/instcombinerimpl/#a2175862566372c3684fe4f7bf62e3143">llvm::InstCombinerImpl::visitZExt</a>.</p>

</div>
</div>

### MadeIRChange {#ae03c488dcba2bb63f265b62001cc361e}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool llvm::InstCombiner::MadeIRChange = false</td>
</tr>
</table>
</td>
<td class="doxyMemberLabelsRight">
<span class="doxyMemberLabels">
<span class="doxyMemberLabel protected">protected</span>
</span>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 86 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/transforms/include/llvm/transforms/instcombine/instcombiner-h">InstCombiner.h</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/classes/llvm/instcombinerimpl/#ad6aa61c7462784d1c9641ee501486375">llvm::InstCombinerImpl::addDeadEdge</a>, <a href="/web-llvm/docs/api/classes/llvm/instcombinerimpl/#a6fc7cb23fbdc2e353fdf2f3aa5212e92">llvm::InstCombinerImpl::eraseInstFromFunction</a>, <a href="/web-llvm/docs/api/classes/llvm/instcombinerimpl/#a352cde174c12aa24afbb7e61c22853e2">llvm::InstCombinerImpl::handleUnreachableFrom</a>, <a href="/web-llvm/docs/api/classes/llvm/instcombinerimpl/#a51dffbda74e47e34a64858d09d456108">llvm::InstCombinerImpl::prepareWorklist</a> and <a href="/web-llvm/docs/api/classes/llvm/instcombinerimpl/#ac5d3cfa0755b34bcbd3f2298e9fa28ed">llvm::InstCombinerImpl::run</a>.</p>

</div>
</div>

### MinimizeSize {#a8d57399452f30fb78195887945ae507c}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">const bool llvm::InstCombiner::MinimizeSize</td>
</tr>
</table>
</td>
<td class="doxyMemberLabelsRight">
<span class="doxyMemberLabels">
<span class="doxyMemberLabel protected">protected</span>
</span>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 68 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/transforms/include/llvm/transforms/instcombine/instcombiner-h">InstCombiner.h</a>.</p>


<p>Referenced by <a href="#af70e33de5e351fc22288a3130b0428b6">InstCombiner</a>, <a href="/web-llvm/docs/api/classes/llvm/instcombinerimpl/#a3192aaa795b73ba7009f98fdad625080">llvm::InstCombinerImpl::InstCombinerImpl</a> and <a href="/web-llvm/docs/api/classes/llvm/instcombinerimpl/#a629e02c312173d0da1b62288bc8fbd48">llvm::InstCombinerImpl::visitFree</a>.</p>

</div>
</div>

### ORE {#aeae5f7d492700a5221d5252b72e8466a}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">OptimizationRemarkEmitter&amp; llvm::InstCombiner::ORE</td>
</tr>
</table>
</td>
<td class="doxyMemberLabelsRight">
<span class="doxyMemberLabels">
<span class="doxyMemberLabel protected">protected</span>
</span>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 78 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/transforms/include/llvm/transforms/instcombine/instcombiner-h">InstCombiner.h</a>.</p>


<p>Referenced by <a href="#ad266f62eb13926ec63289681c04564fb">getOptimizationRemarkEmitter</a>, <a href="#af70e33de5e351fc22288a3130b0428b6">InstCombiner</a> and <a href="/web-llvm/docs/api/classes/llvm/instcombinerimpl/#a3192aaa795b73ba7009f98fdad625080">llvm::InstCombinerImpl::InstCombinerImpl</a>.</p>

</div>
</div>

### PredOrder {#a3b7ae785888d5e91d84157171db3876c}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">SmallDenseMap&lt;BasicBlock *, SmallVector&lt;BasicBlock *&gt;, 8&gt; llvm::InstCombiner::PredOrder</td>
</tr>
</table>
</td>
<td class="doxyMemberLabelsRight">
<span class="doxyMemberLabels">
<span class="doxyMemberLabel protected">protected</span>
</span>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Order of predecessors to canonicalize phi nodes towards.</p>

<p>Definition at line 92 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/transforms/include/llvm/transforms/instcombine/instcombiner-h">InstCombiner.h</a>.</p>

</div>
</div>

### PSI {#ad2f83bae44783989a87e7200ae678c76}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">ProfileSummaryInfo* llvm::InstCombiner::PSI</td>
</tr>
</table>
</td>
<td class="doxyMemberLabelsRight">
<span class="doxyMemberLabels">
<span class="doxyMemberLabel protected">protected</span>
</span>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 81 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/transforms/include/llvm/transforms/instcombine/instcombiner-h">InstCombiner.h</a>.</p>


<p>Referenced by <a href="#ad08bc4ef198e2c99b48b26cdd7c118b0">getProfileSummaryInfo</a>, <a href="#af70e33de5e351fc22288a3130b0428b6">InstCombiner</a> and <a href="/web-llvm/docs/api/classes/llvm/instcombinerimpl/#a3192aaa795b73ba7009f98fdad625080">llvm::InstCombinerImpl::InstCombinerImpl</a>.</p>

</div>
</div>

### RPOT {#a8768d7bd3a905c9cd89c3738d4873a0d}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">ReversePostOrderTraversal&lt;BasicBlock *&gt;&amp; llvm::InstCombiner::RPOT</td>
</tr>
</table>
</td>
<td class="doxyMemberLabelsRight">
<span class="doxyMemberLabels">
<span class="doxyMemberLabel protected">protected</span>
</span>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 84 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/transforms/include/llvm/transforms/instcombine/instcombiner-h">InstCombiner.h</a>.</p>


<p>Referenced by <a href="#ac17fa2d851e729e9c308df593b098fc1">computeBackEdges</a>, <a href="#af70e33de5e351fc22288a3130b0428b6">InstCombiner</a>, <a href="/web-llvm/docs/api/classes/llvm/instcombinerimpl/#a3192aaa795b73ba7009f98fdad625080">llvm::InstCombinerImpl::InstCombinerImpl</a> and <a href="/web-llvm/docs/api/classes/llvm/instcombinerimpl/#a51dffbda74e47e34a64858d09d456108">llvm::InstCombinerImpl::prepareWorklist</a>.</p>

</div>
</div>

### SQ {#a067e49eb19f14e50f84cf4b4e7f6acde}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">SimplifyQuery llvm::InstCombiner::SQ</td>
</tr>
</table>
</td>
<td class="doxyMemberLabelsRight">
<span class="doxyMemberLabels">
<span class="doxyMemberLabel protected">protected</span>
</span>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 77 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/transforms/include/llvm/transforms/instcombine/instcombiner-h">InstCombiner.h</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/classes/llvm/instcombinerimpl/#aa831d259fa5719e16927b5f4877988db">llvm::InstCombinerImpl::commonShiftTransforms</a>, <a href="#ae099c6fa4a0b06306ece7dd372e8d02a">computeKnownBits</a>, <a href="#a6c1e1b56ee28b4d21a3950d48175e284">computeKnownBits</a>, <a href="#a5ab19cff71a6dcbd4d061468d868de48">computeOverflowForSignedAdd</a>, <a href="#acfd758f11fb745755ce05f4763dea3c4">computeOverflowForSignedMul</a>, <a href="#a0056e5666f4dff4b171f6817deb601c6">computeOverflowForSignedSub</a>, <a href="#aeea35a035c67331d0d1383bf392b1d6e">computeOverflowForUnsignedAdd</a>, <a href="#a20be54dc5cf0b5f4d1a53adee1215d96">computeOverflowForUnsignedMul</a>, <a href="#a6e3d062a96f0592c80d7a2e829be2aa3">computeOverflowForUnsignedSub</a>, <a href="/web-llvm/docs/api/classes/llvm/instcombinerimpl/#ac38a3c2794db0ecc70c9bb7106f1e1bf">llvm::InstCombinerImpl::foldAddWithConstant</a>, <a href="/web-llvm/docs/api/classes/llvm/instcombinerimpl/#aa148a41463d0d36003033ac988b2c28d">llvm::InstCombinerImpl::foldICmpAddConstant</a>, <a href="/web-llvm/docs/api/classes/llvm/instcombinerimpl/#a36ef4128d8b08242e337bcbed0dce3c8">llvm::InstCombinerImpl::foldICmpBinOp</a>, <a href="/web-llvm/docs/api/classes/llvm/instcombinerimpl/#a78aa741a7874614a21b66826ffe6e5ce">llvm::InstCombinerImpl::foldICmpBinOpEqualityWithConstant</a>, <a href="/web-llvm/docs/api/classes/llvm/instcombinerimpl/#a78688f28e25e6d68d3f06ddf6e7aac0f">llvm::InstCombinerImpl::foldICmpCommutative</a>, <a href="/web-llvm/docs/api/classes/llvm/instcombinerimpl/#a7df35aaa0732f4b23e5458034a2c29d1">llvm::InstCombinerImpl::foldICmpIntrinsicWithConstant</a>, <a href="/web-llvm/docs/api/classes/llvm/instcombinerimpl/#a8de411243dcb508d9d512006edaba1ec">llvm::InstCombinerImpl::foldICmpUsingKnownBits</a>, <a href="/web-llvm/docs/api/classes/llvm/instcombinerimpl/#acff3d4c4feb8a1f71844fa1facae5670">llvm::InstCombinerImpl::foldICmpWithMinMax</a>, <a href="/web-llvm/docs/api/classes/llvm/instcombinerimpl/#a6fccc5a9bafccfbd5927bb72eb035635">llvm::InstCombinerImpl::foldICmpWithZero</a>, <a href="/web-llvm/docs/api/classes/llvm/instcombinerimpl/#a2fc50d227d302eb98914f04bcc6634e1">llvm::InstCombinerImpl::foldOpIntoPhi</a>, <a href="/web-llvm/docs/api/classes/llvm/instcombinerimpl/#aaa55d4e19334af5b17eb03205a1bece3">llvm::InstCombinerImpl::foldSelectICmp</a>, <a href="/web-llvm/docs/api/classes/llvm/instcombinerimpl/#a1f737dab05d29dca38561bc99b9ef5b5">llvm::InstCombinerImpl::foldSignBitTest</a>, <a href="/web-llvm/docs/api/classes/llvm/instcombinerimpl/#a2511e442d198696042ad2a39cad89059">llvm::InstCombinerImpl::foldUsingDistributiveLaws</a>, <a href="/web-llvm/docs/api/classes/llvm/instcombinerimpl/#a37917731b931aee3150190267d3dd2b5">llvm::InstCombinerImpl::foldVectorSelect</a>, <a href="#af56f7a148b00922368e55ab9c4948724">getSimplifyQuery</a>, <a href="#af70e33de5e351fc22288a3130b0428b6">InstCombiner</a>, <a href="#a46e6cc426055f50cdb04009adb4c2f94">isKnownToBeAPowerOfTwo</a>, <a href="#ae506e7be0a7aaf9001e31d5fca5f2fbc">MaskedValueIsZero</a>, <a href="/web-llvm/docs/api/classes/llvm/instcombinerimpl/#a4b2e9167fd714396a473ee5493c1350b">llvm::InstCombinerImpl::reassociateShiftAmtsOfTwoSameDirectionShifts</a>, <a href="/web-llvm/docs/api/classes/llvm/instcombinerimpl/#a225d5b1dcc0015e743f1dbbf348a9c36">llvm::InstCombinerImpl::SimplifyAssociativeOrCommutative</a>, <a href="#a7ff4e7685008dfb8e6a970b9130a1015">SimplifyDemandedBits</a>, <a href="/web-llvm/docs/api/classes/llvm/instcombinerimpl/#afcc877a26419c2aef195256bc0aa01e3">llvm::InstCombinerImpl::SimplifyDemandedInstructionBits</a>, <a href="/web-llvm/docs/api/classes/llvm/instcombinerimpl/#ad36c0bc30660bad4f2b79be90608ea60">llvm::InstCombinerImpl::SimplifySelectsFeedingBinaryOp</a>, <a href="/web-llvm/docs/api/classes/llvm/instcombinerimpl/#aebf722c3ce9439ef88175255d8669080">llvm::InstCombinerImpl::tryFactorizationFolds</a>, <a href="/web-llvm/docs/api/classes/llvm/instcombinerimpl/#a0a89a6b25b8a92fb896a994a36b74241">llvm::InstCombinerImpl::visitAdd</a>, <a href="/web-llvm/docs/api/classes/llvm/instcombinerimpl/#a648710a93ceb0bbddf0a2ae7a8bb2ca5">llvm::InstCombinerImpl::visitAnd</a>, <a href="/web-llvm/docs/api/classes/llvm/instcombinerimpl/#a612d91fe0858006abe73d7b62821da0c">llvm::InstCombinerImpl::visitAShr</a>, <a href="/web-llvm/docs/api/classes/llvm/instcombinerimpl/#a89ab5eaec7693029761c8d0b3ded3b00">llvm::InstCombinerImpl::visitBitCast</a>, <a href="/web-llvm/docs/api/classes/llvm/instcombinerimpl/#afa2581e2e1ac6959cd02e28062a7c1d5">llvm::InstCombinerImpl::visitCallInst</a>, <a href="/web-llvm/docs/api/classes/llvm/instcombinerimpl/#a71ef354bd1ea9e02d70146d7218a7d39">llvm::InstCombinerImpl::visitExtractElementInst</a>, <a href="/web-llvm/docs/api/classes/llvm/instcombinerimpl/#a679f36556ace611ccc56580cb497973a">llvm::InstCombinerImpl::visitExtractValueInst</a>, <a href="/web-llvm/docs/api/classes/llvm/instcombinerimpl/#a92fdf04445f26ef88ea0e134408b30fe">llvm::InstCombinerImpl::visitFAdd</a>, <a href="/web-llvm/docs/api/classes/llvm/instcombinerimpl/#a86b0437dceb8e39c8185dc7def325011">llvm::InstCombinerImpl::visitFCmpInst</a>, <a href="/web-llvm/docs/api/classes/llvm/instcombinerimpl/#a5457b45fe74cf2f411f5824d32fd389d">llvm::InstCombinerImpl::visitFDiv</a>, <a href="/web-llvm/docs/api/classes/llvm/instcombinerimpl/#abf257c2c6dadfee6ee83fabb6ea77c4f">llvm::InstCombinerImpl::visitFMul</a>, <a href="/web-llvm/docs/api/classes/llvm/instcombinerimpl/#a397caaa6fe7aad6bb3d482f9fe157e71">llvm::InstCombinerImpl::visitFreeze</a>, <a href="/web-llvm/docs/api/classes/llvm/instcombinerimpl/#aa86b3c1abcd345da14cfe5dd65165b86">llvm::InstCombinerImpl::visitFRem</a>, <a href="/web-llvm/docs/api/classes/llvm/instcombinerimpl/#a22bc54f319e33d248b169116b757a143">llvm::InstCombinerImpl::visitGEPOfGEP</a>, <a href="/web-llvm/docs/api/classes/llvm/instcombinerimpl/#ae755d569b6e5c69a8abbc6de50cf3f6b">llvm::InstCombinerImpl::visitGetElementPtrInst</a>, <a href="/web-llvm/docs/api/classes/llvm/instcombinerimpl/#ae31c50e938b95587c87aed0f133b1346">llvm::InstCombinerImpl::visitICmpInst</a>, <a href="/web-llvm/docs/api/classes/llvm/instcombinerimpl/#a687fa4390149f0cb751d8ad89dca6a3c">llvm::InstCombinerImpl::visitInsertElementInst</a>, <a href="/web-llvm/docs/api/classes/llvm/instcombinerimpl/#a643f8d7ef849e1312c83906b4b27b4aa">llvm::InstCombinerImpl::visitInsertValueInst</a>, <a href="/web-llvm/docs/api/classes/llvm/instcombinerimpl/#a3ba96a0d49ec5f1a062b075f54536a3c">llvm::InstCombinerImpl::visitLoadInst</a>, <a href="/web-llvm/docs/api/classes/llvm/instcombinerimpl/#a197424adbab353be4587e6dfaee445e3">llvm::InstCombinerImpl::visitLShr</a>, <a href="/web-llvm/docs/api/classes/llvm/instcombinerimpl/#a01ed915fb2acf9fd660ca752edeec0db">llvm::InstCombinerImpl::visitMul</a>, <a href="/web-llvm/docs/api/classes/llvm/instcombinerimpl/#a1e893463cbb4b5e2e3830b2e4c28cbdb">llvm::InstCombinerImpl::visitOr</a>, <a href="/web-llvm/docs/api/classes/llvm/instcombinerimpl/#a752efe4724ac3a97d07ee81d5f779c92">llvm::InstCombinerImpl::visitPHINode</a>, <a href="/web-llvm/docs/api/classes/llvm/instcombinerimpl/#af12904244ec179b265540ed1fb8c6615">llvm::InstCombinerImpl::visitSDiv</a>, <a href="/web-llvm/docs/api/classes/llvm/instcombinerimpl/#a2a5120238e6845643a37d5a4675a5342">llvm::InstCombinerImpl::visitSExt</a>, <a href="/web-llvm/docs/api/classes/llvm/instcombinerimpl/#a90fcdfa591c9bd0cf511f2803198b355">llvm::InstCombinerImpl::visitShl</a>, <a href="/web-llvm/docs/api/classes/llvm/instcombinerimpl/#ad31108b4f7156db7565eadba1285c93a">llvm::InstCombinerImpl::visitShuffleVectorInst</a>, <a href="/web-llvm/docs/api/classes/llvm/instcombinerimpl/#a5c5efa376b5dcc0c0b0628d89882a498">llvm::InstCombinerImpl::visitSIToFP</a>, <a href="/web-llvm/docs/api/classes/llvm/instcombinerimpl/#a411aa95504f966614c8f5d5aeeef1f04">llvm::InstCombinerImpl::visitSRem</a>, <a href="/web-llvm/docs/api/classes/llvm/instcombinerimpl/#a606601489498c1ba41f25e77eb2dd0cf">llvm::InstCombinerImpl::visitSub</a>, <a href="/web-llvm/docs/api/classes/llvm/instcombinerimpl/#a43a1d060dacb05eb645cf91ea86d7bd3">llvm::InstCombinerImpl::visitTrunc</a>, <a href="/web-llvm/docs/api/classes/llvm/instcombinerimpl/#a1cdbee2aa0ed532c8d9e91a00cc91f37">llvm::InstCombinerImpl::visitUDiv</a>, <a href="/web-llvm/docs/api/classes/llvm/instcombinerimpl/#a4d45f96f90c7ddd805c6bae2949077de">llvm::InstCombinerImpl::visitUIToFP</a>, <a href="/web-llvm/docs/api/classes/llvm/instcombinerimpl/#a2f39b95e8efb44737439c323b18a55d7">llvm::InstCombinerImpl::visitURem</a>, <a href="/web-llvm/docs/api/classes/llvm/instcombinerimpl/#aaf7b6cd7c3ceb4af17b610cba09648c9">llvm::InstCombinerImpl::visitXor</a>, <a href="/web-llvm/docs/api/classes/llvm/instcombinerimpl/#a2175862566372c3684fe4f7bf62e3143">llvm::InstCombinerImpl::visitZExt</a> and <a href="/web-llvm/docs/api/classes/llvm/instcombinerimpl/#a14d35a77d4b1f7036fd49cee4d138f21">llvm::InstCombinerImpl::~InstCombinerImpl</a>.</p>

</div>
</div>

### TLI {#a3ccb79ce550ca98c6f524c1c6bdd06a1}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">TargetLibraryInfo&amp; llvm::InstCombiner::TLI</td>
</tr>
</table>
</td>
<td class="doxyMemberLabelsRight">
<span class="doxyMemberLabels">
<span class="doxyMemberLabel protected">protected</span>
</span>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 74 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/transforms/include/llvm/transforms/instcombine/instcombiner-h">InstCombiner.h</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/classes/llvm/instcombinerimpl/#a866883cec7ed781fcf1e9cda18b24f5b">llvm::InstCombinerImpl::foldCmpLoadFromIndexedGlobal</a>, <a href="#a3cf623e18c507f6a12ba24ee04320625">getTargetLibraryInfo</a>, <a href="#af70e33de5e351fc22288a3130b0428b6">InstCombiner</a>, <a href="/web-llvm/docs/api/classes/llvm/instcombinerimpl/#a3192aaa795b73ba7009f98fdad625080">llvm::InstCombinerImpl::InstCombinerImpl</a>, <a href="/web-llvm/docs/api/classes/llvm/instcombinerimpl/#a51dffbda74e47e34a64858d09d456108">llvm::InstCombinerImpl::prepareWorklist</a>, <a href="/web-llvm/docs/api/classes/llvm/instcombinerimpl/#ac5d3cfa0755b34bcbd3f2298e9fa28ed">llvm::InstCombinerImpl::run</a>, <a href="/web-llvm/docs/api/classes/llvm/instcombinerimpl/#af4b167ac2fde7b3d71172817650150a6">llvm::InstCombinerImpl::tryToSinkInstruction</a>, <a href="/web-llvm/docs/api/classes/llvm/instcombinerimpl/#ae289e620828eabb1dfe34c9ad322a81d">llvm::InstCombinerImpl::visitAllocSite</a>, <a href="/web-llvm/docs/api/classes/llvm/instcombinerimpl/#afa2581e2e1ac6959cd02e28062a7c1d5">llvm::InstCombinerImpl::visitCallInst</a>, <a href="/web-llvm/docs/api/classes/llvm/instcombinerimpl/#a5457b45fe74cf2f411f5824d32fd389d">llvm::InstCombinerImpl::visitFDiv</a> and <a href="/web-llvm/docs/api/classes/llvm/instcombinerimpl/#a629e02c312173d0da1b62288bc8fbd48">llvm::InstCombinerImpl::visitFree</a>.</p>

</div>
</div>

### Worklist {#a7b93340fbcab35a38a04bf49aa3113a0}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">InstructionWorklist&amp; llvm::InstCombiner::Worklist</td>
</tr>
</table>
</td>
<td class="doxyMemberLabelsRight">
<span class="doxyMemberLabels">
<span class="doxyMemberLabel protected">protected</span>
</span>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>A worklist of the instructions that need to be simplified.</p>

<p>Definition at line 65 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/transforms/include/llvm/transforms/instcombine/instcombiner-h">InstCombiner.h</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/classes/llvm/instcombinerimpl/#ad6aa61c7462784d1c9641ee501486375">llvm::InstCombinerImpl::addDeadEdge</a>, <a href="#ab86d58ae73173328360a32cbbb0d5b14">addToWorklist</a>, <a href="/web-llvm/docs/api/classes/llvm/instcombinerimpl/#a6fc7cb23fbdc2e353fdf2f3aa5212e92">llvm::InstCombinerImpl::eraseInstFromFunction</a>, <a href="/web-llvm/docs/api/classes/llvm/instcombinerimpl/#aef28063eb280fec69a391dd35c51666e">llvm::InstCombinerImpl::foldFreezeIntoRecurrence</a>, <a href="/web-llvm/docs/api/classes/llvm/instcombinerimpl/#a4e25c5f8a8a770362e0ab9dcaa167dab">llvm::InstCombinerImpl::handlePotentiallyDeadBlocks</a>, <a href="/web-llvm/docs/api/classes/llvm/instcombinerimpl/#a68e1b07361fa3158d2c11c1af3d7ab1b">llvm::InstCombinerImpl::handlePotentiallyDeadSuccessors</a>, <a href="/web-llvm/docs/api/classes/llvm/instcombinerimpl/#a352cde174c12aa24afbb7e61c22853e2">llvm::InstCombinerImpl::handleUnreachableFrom</a>, <a href="#a46f1e493b5d0822af6344aa294f93fdb">InsertNewInstBefore</a>, <a href="#af70e33de5e351fc22288a3130b0428b6">InstCombiner</a>, <a href="/web-llvm/docs/api/classes/llvm/instcombinerimpl/#a3192aaa795b73ba7009f98fdad625080">llvm::InstCombinerImpl::InstCombinerImpl</a>, <a href="/web-llvm/docs/api/classes/llvm/instcombinerimpl/#adf0b3634500370e379ded8d75a72e791">llvm::InstCombinerImpl::matchBSwapOrBitReverse</a>, <a href="/web-llvm/docs/api/classes/llvm/instcombinerimpl/#a51dffbda74e47e34a64858d09d456108">llvm::InstCombinerImpl::prepareWorklist</a>, <a href="/web-llvm/docs/api/classes/llvm/instcombinerimpl/#a61a7d6f4ff5c687b725de3d5612d25dd">llvm::InstCombinerImpl::replaceInInstruction</a>, <a href="#a49f1bd0bdf0ef741bdd714cc1188d7c5">replaceInstUsesWith</a>, <a href="#ac2a56636a6f3742f5e495f67e67b6b36">replaceOperand</a>, <a href="#a6c1f812e984c68bc39c22b63a117e1eb">replaceUse</a>, <a href="/web-llvm/docs/api/classes/llvm/instcombinerimpl/#ac5d3cfa0755b34bcbd3f2298e9fa28ed">llvm::InstCombinerImpl::run</a>, <a href="/web-llvm/docs/api/classes/llvm/instcombinerimpl/#a37cce7aa1875173688e5971c5d6fa9e0">llvm::InstCombinerImpl::SimplifyDemandedVectorElts</a>, <a href="/web-llvm/docs/api/classes/llvm/instcombinerimpl/#a558144ce515858cbab3df5c7005a5a50">llvm::InstCombinerImpl::simplifyDivRemOfSelectWithZeroOp</a>, <a href="/web-llvm/docs/api/classes/llvm/instcombinerimpl/#af4b167ac2fde7b3d71172817650150a6">llvm::InstCombinerImpl::tryToSinkInstruction</a>, <a href="/web-llvm/docs/api/classes/llvm/instcombinerimpl/#a0a89a6b25b8a92fb896a994a36b74241">llvm::InstCombinerImpl::visitAdd</a>, <a href="/web-llvm/docs/api/classes/llvm/instcombinerimpl/#ae289e620828eabb1dfe34c9ad322a81d">llvm::InstCombinerImpl::visitAllocSite</a>, <a href="/web-llvm/docs/api/classes/llvm/instcombinerimpl/#aea9ba5a362fb88bd97349a302133dd03">llvm::InstCombinerImpl::visitBranchInst</a>, <a href="/web-llvm/docs/api/classes/llvm/instcombinerimpl/#afa2581e2e1ac6959cd02e28062a7c1d5">llvm::InstCombinerImpl::visitCallInst</a>, <a href="/web-llvm/docs/api/classes/llvm/instcombinerimpl/#a71ef354bd1ea9e02d70146d7218a7d39">llvm::InstCombinerImpl::visitExtractElementInst</a> and <a href="/web-llvm/docs/api/classes/llvm/instcombinerimpl/#a8042dd4cb7e9772368f2808b8db577be">llvm::InstCombinerImpl::visitStoreInst</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Private Member Attributes

### TTIForTargetIntrinsicsOnly {#a5696bc370733423fa09de368b102e92c}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">TargetTransformInfo&amp; llvm::InstCombiner::TTIForTargetIntrinsicsOnly</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Only used to call target specific intrinsic combining.</p>


<p>It must <b>NOT</b> be used for any other purpose, as InstCombine is a target-independent canonicalization transform.</p>


<p>Definition at line 52 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/transforms/include/llvm/transforms/instcombine/instcombiner-h">InstCombiner.h</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Public Static Functions

### AddOne() {#afe2dc21e0303f087635f70178f4a17ea}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">Constant * llvm::InstCombiner::AddOne (<a href="/web-llvm/docs/api/classes/llvm/constant">Constant</a> * C)</td>
</tr>
</table>
</td>
<td class="doxyMemberLabelsRight">
<span class="doxyMemberLabels">
<span class="doxyMemberLabel inline">inline</span>
<span class="doxyMemberLabel static">static</span>
</span>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Add one to a <a href="/web-llvm/docs/api/classes/llvm/constant">Constant</a>.</p>

<p>Definition at line 178 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/transforms/include/llvm/transforms/instcombine/instcombiner-h">InstCombiner.h</a>.</p>


<p>References <a href="/web-llvm/docs/api/namespaces/llvm/callingconv/#ac6aa1387c4375260e2468eb5a77fdb4cafd841a49aec1539bc88abc8ff9e170fb">llvm::CallingConv::C</a> and <a href="/web-llvm/docs/api/classes/llvm/constantexpr/#ae6f1c15034bc5515033874630a8ecce6">llvm::ConstantExpr::getAdd</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/classes/llvm/instcombinerimpl/#ac38a3c2794db0ecc70c9bb7106f1e1bf">llvm::InstCombinerImpl::foldAddWithConstant</a>, <a href="/web-llvm/docs/api/classes/llvm/instcombinerimpl/#a0a89a6b25b8a92fb896a994a36b74241">llvm::InstCombinerImpl::visitAdd</a> and <a href="/web-llvm/docs/api/classes/llvm/instcombinerimpl/#a606601489498c1ba41f25e77eb2dd0cf">llvm::InstCombinerImpl::visitSub</a>.</p>

</div>
</div>

### getComplexity() {#a2f79a062519c0854b4b97bbceac77997}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">unsigned llvm::InstCombiner::getComplexity (<a href="/web-llvm/docs/api/classes/llvm/value">Value</a> * V)</td>
</tr>
</table>
</td>
<td class="doxyMemberLabelsRight">
<span class="doxyMemberLabels">
<span class="doxyMemberLabel inline">inline</span>
<span class="doxyMemberLabel static">static</span>
</span>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Assign a complexity or rank value to LLVM Values.</p>


<p>This is used to reduce the amount of pattern matching needed for compares and commutative instructions. For example, if we have: icmp ugt X, <a href="/web-llvm/docs/api/classes/llvm/constant">Constant</a> or xor (add X, <a href="/web-llvm/docs/api/classes/llvm/constant">Constant</a>), cast Z</p>


<p>We do not have to consider the commuted variants of these patterns because canonicalization based on complexity guarantees the above ordering.</p>


<p>This routine maps IR values to various complexity ranks: 0 -&gt; undef 1 -&gt; Constants 2 -&gt; Cast and (f)neg/not instructions 3 -&gt; Other instructions and arguments</p>


<p>Definition at line 143 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/transforms/include/llvm/transforms/instcombine/instcombiner-h">InstCombiner.h</a>.</p>


<p>References <a href="/web-llvm/docs/api/namespaces/llvm/#a92ca992e52dddc420f4b069cae06dfbe">llvm::isa</a>, <a href="/web-llvm/docs/api/namespaces/llvm/patternmatch/#aba7473bfa862dd9eadf04a6fefc6aa69">llvm::PatternMatch::m_FNeg</a>, <a href="/web-llvm/docs/api/namespaces/llvm/patternmatch/#a5d295dcffba83c3c5a17d2fb3273b434">llvm::PatternMatch::m_Neg</a>, <a href="/web-llvm/docs/api/namespaces/llvm/patternmatch/#ae28f9cbf5b5e3fbeb69d1414285c1760">llvm::PatternMatch::m_Not</a>, <a href="/web-llvm/docs/api/namespaces/llvm/patternmatch/#aaf522908fe903018eb9b087dd6e49296">llvm::PatternMatch::m_Value</a> and <a href="/web-llvm/docs/api/namespaces/llvm/patternmatch/#a25d956d9e0beadd47ce4bc255dfa811d">llvm::PatternMatch::match</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/classes/llvm/instcombinerimpl/#a225d5b1dcc0015e743f1dbbf348a9c36">llvm::InstCombinerImpl::SimplifyAssociativeOrCommutative</a>, <a href="/web-llvm/docs/api/classes/llvm/instcombinerimpl/#a86b0437dceb8e39c8185dc7def325011">llvm::InstCombinerImpl::visitFCmpInst</a> and <a href="/web-llvm/docs/api/classes/llvm/instcombinerimpl/#ae31c50e938b95587c87aed0f133b1346">llvm::InstCombinerImpl::visitICmpInst</a>.</p>

</div>
</div>

### getSafeVectorConstantForBinop() {#acf9cbfcb493b0042022c94230e9350e2}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">Constant * llvm::InstCombiner::getSafeVectorConstantForBinop (<a href="/web-llvm/docs/api/classes/llvm/instruction/#ac26154a24f393f523c87cc5f8239f36c">BinaryOperator::BinaryOps</a> Opcode, <a href="/web-llvm/docs/api/classes/llvm/constant">Constant</a> * In, bool IsRHSConstant)</td>
</tr>
</table>
</td>
<td class="doxyMemberLabelsRight">
<span class="doxyMemberLabels">
<span class="doxyMemberLabel inline">inline</span>
<span class="doxyMemberLabel static">static</span>
</span>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Some binary operators require special handling to avoid poison and undefined behavior.</p>


<p>If a constant vector has undef elements, replace those undefs with identity constants if possible because those are always safe to execute. If no identity constant exists, replace undef with some other safe constant.</p>


<p>Definition at line 280 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/transforms/include/llvm/transforms/instcombine/instcombiner-h">InstCombiner.h</a>.</p>


<p>References <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/silowercontrolflow-cpp/#a4868c5d81c5ccc98c47aeab6244346a0">assert</a>, <a href="/web-llvm/docs/api/namespaces/llvm/callingconv/#ac6aa1387c4375260e2468eb5a77fdb4cafd841a49aec1539bc88abc8ff9e170fb">llvm::CallingConv::C</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#ac4fc845f5ed92de63cd4474f128f5fc5">llvm::cast</a>, <a href="/web-llvm/docs/api/classes/llvm/constantvector/#ade9fa017ca3aa82f7694a47090547bc1">llvm::ConstantVector::get</a>, <a href="/web-llvm/docs/api/classes/llvm/constantexpr/#ae9c2f00a962cb8e0316cf3548a5d8029">llvm::ConstantExpr::getBinOpIdentity</a>, <a href="/web-llvm/docs/api/classes/llvm/constant/#aa6574d526b3e38a28f688a7bb4325c2c">llvm::Constant::getNullValue</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a92ca992e52dddc420f4b069cae06dfbe">llvm::isa</a> and <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/support/errorhandling-h/#ace243f5c25697a1107cce46626b3dc94">llvm_unreachable</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/classes/llvm/instcombinerimpl/#a3b73df3a995af9ca26c9d024c957c45a">llvm::InstCombinerImpl::foldSelectShuffle</a>, <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/instcombine/instcombinevectorops-cpp/#a2c05df65ce7ce7ec1d78348be2452e8d">foldSelectShuffleWith1Binop</a> and <a href="/web-llvm/docs/api/classes/llvm/instcombinerimpl/#acbf4c17d9f1b9f6729602a3c2a6c5b9d">llvm::InstCombinerImpl::foldVectorBinop</a>.</p>

</div>
</div>

### isCanonicalPredicate() {#a7245fe59c5c3470907144f999fbb258a}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool llvm::InstCombiner::isCanonicalPredicate (<a href="/web-llvm/docs/api/classes/llvm/cmppredicate">CmpPredicate</a> Pred)</td>
</tr>
</table>
</td>
<td class="doxyMemberLabelsRight">
<span class="doxyMemberLabels">
<span class="doxyMemberLabel inline">inline</span>
<span class="doxyMemberLabel static">static</span>
</span>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p><a href="/web-llvm/docs/api/classes/predicate">Predicate</a> canonicalization reduces the number of patterns that need to be matched by other transforms.</p>


<p>For example, we may swap the operands of a conditional branch or select to create a compare with a canonical (inverted) predicate which is then more likely to be matched with other values.</p>


<p>Definition at line 160 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/transforms/include/llvm/transforms/instcombine/instcombiner-h">InstCombiner.h</a>.</p>


<p>References <a href="/web-llvm/docs/api/classes/llvm/cmpinst/#a2be3583dac92a031fa1458d4d992c78ba541533f34077bbbcfb703a90f6d2da9b">llvm::CmpInst::FCMP_OGE</a>, <a href="/web-llvm/docs/api/classes/llvm/cmpinst/#a2be3583dac92a031fa1458d4d992c78ba9835cfe02fb5027680bd7203b024f77a">llvm::CmpInst::FCMP_OLE</a>, <a href="/web-llvm/docs/api/classes/llvm/cmpinst/#a2be3583dac92a031fa1458d4d992c78ba8a80b27ca29fe2076b9bbdee02c65464">llvm::CmpInst::FCMP_ONE</a>, <a href="/web-llvm/docs/api/classes/llvm/cmpinst/#a2be3583dac92a031fa1458d4d992c78bac17897ebf2f6a6986280fc3bdf28a30a">llvm::CmpInst::ICMP_NE</a>, <a href="/web-llvm/docs/api/classes/llvm/cmpinst/#a2be3583dac92a031fa1458d4d992c78bac1aa7b798ba11d2e497d5cce6ce6d3dc">llvm::CmpInst::ICMP_SGE</a>, <a href="/web-llvm/docs/api/classes/llvm/cmpinst/#a2be3583dac92a031fa1458d4d992c78ba2751d6136a2819749dcef65dc19a4246">llvm::CmpInst::ICMP_SLE</a>, <a href="/web-llvm/docs/api/classes/llvm/cmpinst/#a2be3583dac92a031fa1458d4d992c78ba573bcd571c938fce863525330bbfc4b8">llvm::CmpInst::ICMP_UGE</a> and <a href="/web-llvm/docs/api/classes/llvm/cmpinst/#a2be3583dac92a031fa1458d4d992c78bad92f160316221fd4090520bb2b3cefc5">llvm::CmpInst::ICMP_ULE</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/instcombine/instcombinecompares-cpp/#a8bd7da2c6b76da474423e160c63fdc68">canonicalizeCmpWithConstant</a>, <a href="/web-llvm/docs/api/classes/llvm/instcombinerimpl/#a6f392d7a34855ef605496d0afcb913cd">llvm::InstCombinerImpl::canonicalizeICmpPredicate</a> and <a href="/web-llvm/docs/api/classes/llvm/instcombinerimpl/#aea9ba5a362fb88bd97349a302133dd03">llvm::InstCombinerImpl::visitBranchInst</a>.</p>

</div>
</div>

### peekThroughBitcast() {#aa1eeea37af7eeec30772c649d25cd1ba}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">Value * llvm::InstCombiner::peekThroughBitcast (<a href="/web-llvm/docs/api/classes/llvm/value">Value</a> * V, bool OneUseOnly=false)</td>
</tr>
</table>
</td>
<td class="doxyMemberLabelsRight">
<span class="doxyMemberLabels">
<span class="doxyMemberLabel inline">inline</span>
<span class="doxyMemberLabel static">static</span>
</span>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Return the source operand of a potentially bitcasted value while optionally checking if it has one use.</p>


<p>If there is no bitcast or the one use check is not met, return the input value itself.</p>


<p>Definition at line 119 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/transforms/include/llvm/transforms/instcombine/instcombiner-h">InstCombiner.h</a>.</p>


<p>Reference <a href="/web-llvm/docs/api/namespaces/llvm/#a22eeee01734061ac1b31ccd994c49eef">llvm::dyn_cast</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/classes/llvm/x86ttiimpl/#a47cb7185e35282131b486036ff7c45df">llvm::X86TTIImpl::instCombineIntrinsic</a>.</p>

</div>
</div>

### shouldAvoidAbsorbingNotIntoSelect() {#a4ffe5454cf09255ace0804d9c8044004}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool llvm::InstCombiner::shouldAvoidAbsorbingNotIntoSelect (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/selectinst">SelectInst</a> &amp; SI)</td>
</tr>
</table>
</td>
<td class="doxyMemberLabelsRight">
<span class="doxyMemberLabels">
<span class="doxyMemberLabel inline">inline</span>
<span class="doxyMemberLabel static">static</span>
</span>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 187 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/transforms/include/llvm/transforms/instcombine/instcombiner-h">InstCombiner.h</a>.</p>


<p>References <a href="/web-llvm/docs/api/namespaces/llvm/patternmatch/#a2276d81e0e6e31d0a69c4352a066ef73">llvm::PatternMatch::m_LogicalAnd</a>, <a href="/web-llvm/docs/api/namespaces/llvm/patternmatch/#ad4d070a596ae37b8e01f15e4f759fc07">llvm::PatternMatch::m_LogicalOr</a>, <a href="/web-llvm/docs/api/namespaces/llvm/patternmatch/#aaf522908fe903018eb9b087dd6e49296">llvm::PatternMatch::m_Value</a> and <a href="/web-llvm/docs/api/namespaces/llvm/patternmatch/#a25d956d9e0beadd47ce4bc255dfa811d">llvm::PatternMatch::match</a>.</p>


<p>Referenced by <a href="#ab0cf90f56e055b09227ab0f84acc4083">canFreelyInvertAllUsersOf</a> and <a href="#ab98cb2aaf6e757aac9c471f85f113a50">getFreelyInvertedImpl</a>.</p>

</div>
</div>

### SubOne() {#a5c9e100d07432e392331760d46053089}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">Constant * llvm::InstCombiner::SubOne (<a href="/web-llvm/docs/api/classes/llvm/constant">Constant</a> * C)</td>
</tr>
</table>
</td>
<td class="doxyMemberLabelsRight">
<span class="doxyMemberLabels">
<span class="doxyMemberLabel inline">inline</span>
<span class="doxyMemberLabel static">static</span>
</span>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Subtract one from a <a href="/web-llvm/docs/api/classes/llvm/constant">Constant</a>.</p>

<p>Definition at line 183 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/transforms/include/llvm/transforms/instcombine/instcombiner-h">InstCombiner.h</a>.</p>


<p>References <a href="/web-llvm/docs/api/namespaces/llvm/callingconv/#ac6aa1387c4375260e2468eb5a77fdb4cafd841a49aec1539bc88abc8ff9e170fb">llvm::CallingConv::C</a> and <a href="/web-llvm/docs/api/classes/llvm/constantexpr/#a554ab77949b0a16670a83ec3307501eb">llvm::ConstantExpr::getSub</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/classes/llvm/instcombinerimpl/#ac38a3c2794db0ecc70c9bb7106f1e1bf">llvm::InstCombinerImpl::foldAddWithConstant</a>, <a href="/web-llvm/docs/api/classes/llvm/instcombinerimpl/#ac457b78bde79027e427b9d2ca79bb2f1">llvm::InstCombinerImpl::foldICmpAndConstant</a>, <a href="/web-llvm/docs/api/classes/llvm/instcombinerimpl/#a0a89a6b25b8a92fb896a994a36b74241">llvm::InstCombinerImpl::visitAdd</a> and <a href="/web-llvm/docs/api/classes/llvm/instcombinerimpl/#a606601489498c1ba41f25e77eb2dd0cf">llvm::InstCombinerImpl::visitSub</a>.</p>

</div>
</div>

</div>

<hr/>

The documentation for this class was generated from the following files:

<ul>
<li><a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/transforms/include/llvm/transforms/instcombine/instcombiner-h">InstCombiner.h</a></li>
<li><a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/instcombine/instructioncombining-cpp">InstructionCombining.cpp</a></li>
</ul>

<hr/>

<p class="doxyGeneratedBy">Generated via <a href="https://github.com/xpack/doxygen2docusaurus">doxygen2docusaurus</a> by <a href="https://www.doxygen.nl">Doxygen</a> 1.14.0.</p>

</div>
