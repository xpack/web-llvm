---

# DO NOT EDIT!
# Automatically generated via doxygen2docusaurus by Doxygen.

slug: /api/classes/anonymous-codegenprepare-cpp-/codegenprepare
custom_edit_url: null
toc_max_heading_level: 4
keywords:
  - doxygen
  - reference
  - class

---

<div class="doxyPage">

# `CodeGenPrepare` Class



## Declaration

<div class="doxyDeclaration">
class anonymous{CodeGenPrepare.cpp}::CodeGenPrepare { ... }
</div>

## Friends Index

<table class="doxyMembersIndex">

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">class</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#add05b1dba7a9938b30736abfceee94bf">CodeGenPrepareLegacyPass</a></td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a88c47869c3d6832ba11c5480ba78aa04">CodeGenPrepare</a> ()</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a2fab09a0564f5203372a75e51f20b526">CodeGenPrepare</a> (const TargetMachine *TM)</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">void</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a603cbf2855141608521f6709cdfb126f">releaseMemory</a> ()</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#aa963097f89a02195cba904f74c5e0f71">run</a> (Function &amp;F, FunctionAnalysisManager &amp;AM)</td>
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

<tr class="doxyMemberIndexTemplate">
<td class="doxyMemberIndexTemplate" colspan="2"><div>template &lt;typename F&gt;</div></td>
</tr>
<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemTypeTemplate" align="left" valign="top">void</td>
<td class="doxyMemberIndexItemNameTemplate" align="left" valign="top"><a href="#aebe65440aaacc621de5f01476c4cdbf8">resetIteratorIfInvalidatedWhileCalling</a> (BasicBlock *BB, F f)</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a4c148ccce69d6cc369ffd4f1af74db3c">getDT</a> (Function &amp;F)</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a58c195830f33ef6f11aee9e08c3cfb2f">removeAllAssertingVHReferences</a> (Value *V)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>An instruction is about to be deleted, so remove all references to it in our GEP-tracking data strcutures. <a href="#a58c195830f33ef6f11aee9e08c3cfb2f">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">bool</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a3dcd746570792e10cf6a0d674e0bcfc1">eliminateAssumptions</a> (Function &amp;F)</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ac52c20dcc2816650d2391094a7130e19">eliminateFallThrough</a> (Function &amp;F, DominatorTree *DT=nullptr)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Merge basic blocks which are connected by a single edge, where one of the basic blocks has a single successor pointing to the other basic block, which has a single predecessor. <a href="#ac52c20dcc2816650d2391094a7130e19">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">bool</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a8a98f2fc2e044e5c49e08dc512e9766d">eliminateMostlyEmptyBlocks</a> (Function &amp;F)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Eliminate blocks that contain only PHI nodes, debug info directives, and an unconditional branch. <a href="#a8a98f2fc2e044e5c49e08dc512e9766d">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/basicblock">BasicBlock</a> *</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ae885a922e6c608baa4b10f4c344ff8f9">findDestBlockOfMergeableEmptyBlock</a> (BasicBlock *BB)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Find a destination block from BB if BB is mergeable empty block. <a href="#ae885a922e6c608baa4b10f4c344ff8f9">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">bool</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#adae1a5b888e2f1cae3a8e27539b57a96">canMergeBlocks</a> (const BasicBlock *BB, const BasicBlock *DestBB) const</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Return true if we can merge BB into DestBB if there is a single unconditional branch between them, and BB contains no other non-phi instructions. <a href="#adae1a5b888e2f1cae3a8e27539b57a96">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">void</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a7cde84775859537191b0ef8ff50a6a64">eliminateMostlyEmptyBlock</a> (BasicBlock *BB)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Eliminate a basic block that has only phi's and an unconditional branch in it. <a href="#a7cde84775859537191b0ef8ff50a6a64">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">bool</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a78ca6c4dfaa10c937e5498a8e89c3e5f">isMergingEmptyBlockProfitable</a> (BasicBlock *BB, BasicBlock *DestBB, bool isPreheader)</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a88540618571df605c6a8afcc1dda31b2">makeBitReverse</a> (Instruction &amp;I)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Given an OR instruction, check to see if this is a bitreverse idiom. <a href="#a88540618571df605c6a8afcc1dda31b2">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">bool</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a76f689d898c02e67ec20b7f989f3d9cc">optimizeBlock</a> (BasicBlock &amp;BB, ModifyDT &amp;ModifiedDT)</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a8c882a84c5e053c5357f20e964cb931f">optimizeInst</a> (Instruction *I, ModifyDT &amp;ModifiedDT)</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#afd8b9969b84a5af5e0cb3bfb01396efe">optimizeMemoryInst</a> (Instruction *MemoryInst, Value *Addr, Type *AccessTy, unsigned AddrSpace)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Sink addressing mode computation immediate before MemoryInst if doing so can be done without increasing register pressure. <a href="#afd8b9969b84a5af5e0cb3bfb01396efe">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">bool</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ae01c9a10c8ff78ab53ad052a3ba0da3d">optimizeGatherScatterInst</a> (Instruction *MemoryInst, Value *Ptr)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Rewrite GEP input to gather/scatter to enable <a href="/web-llvm/docs/api/classes/llvm/selectiondagbuilder">SelectionDAGBuilder</a> to find a uniform base to use for <a href="/web-llvm/docs/api/namespaces/llvm/isd/#a22ea9cec080dd5f4f47ba234c2f59110ab4685260a7e506fe51f17d9b600349c8">ISD::MGATHER</a>/MSCATTER. <a href="#ae01c9a10c8ff78ab53ad052a3ba0da3d">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">bool</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#acdc7dab18d5d084b8575d1b74ee3a148">optimizeInlineAsmInst</a> (CallInst *CS)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>If there are any memory operands, use OptimizeMemoryInst to sink their address computing into the block when possible / profitable. <a href="#acdc7dab18d5d084b8575d1b74ee3a148">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">bool</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a5e71ce5490f551bc23302493c0085350">optimizeCallInst</a> (CallInst *CI, ModifyDT &amp;ModifiedDT)</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a6df2c21c695e9f4b2daffadc78315161">optimizeExt</a> (Instruction *&amp;I)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Move a zext or sext fed by a load into the same basic block as the load, unless conditions are unfavorable. <a href="#a6df2c21c695e9f4b2daffadc78315161">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">bool</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a0120cd06c7eb8a6da3bbc5ce8c21b246">optimizeExtUses</a> (Instruction *I)</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a391adeee5b39aa16cf62049001ca645f">optimizeLoadExt</a> (LoadInst *Load)</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a8b3c1b5ac856dcbab367e6f861bd7fc6">optimizeShiftInst</a> (BinaryOperator *BO)</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ad631003806d9185e7996c19bc641a759">optimizeFunnelShift</a> (IntrinsicInst *Fsh)</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#acfd60d0907cc0c992181890a76c01fb5">optimizeSelectInst</a> (SelectInst *SI)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>If we have a <a href="/web-llvm/docs/api/classes/llvm/selectinst">SelectInst</a> that will likely profit from branch prediction, turn it into a branch. <a href="#acfd60d0907cc0c992181890a76c01fb5">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">bool</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a57be619ad0dcc9b77665d4fb62a81003">optimizeShuffleVectorInst</a> (ShuffleVectorInst *SVI)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Some targets only accept certain types for splat inputs. <a href="#a57be619ad0dcc9b77665d4fb62a81003">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">bool</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#aadedf13a700b332f76fb1e3b2c3dbcc8">optimizeSwitchType</a> (SwitchInst *SI)</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a7baeeb27daa2e0e307aac0c6778486b0">optimizeSwitchPhiConstants</a> (SwitchInst *SI)</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a12f2bc1d5d97f6f3f257b3a2de7b0290">optimizeSwitchInst</a> (SwitchInst *SI)</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a2b04fd8d828ff9353eadb53454feaa12">optimizeExtractElementInst</a> (Instruction *Inst)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Some targets can do store(extractelement) with one instruction. <a href="#a2b04fd8d828ff9353eadb53454feaa12">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">bool</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a29a32e999bef6e6fd8876e11332fc8a8">dupRetToEnableTailCallOpts</a> (BasicBlock *BB, ModifyDT &amp;ModifiedDT)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Look for opportunities to duplicate return instructions to the predecessor to enable tail call optimizations. <a href="#a29a32e999bef6e6fd8876e11332fc8a8">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">bool</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ae9b9cffc69c81998e5349bb85ab4886e">fixupDbgValue</a> (Instruction *I)</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ad513cf759e58690876c6d228372c0727">fixupDbgVariableRecord</a> (DbgVariableRecord &amp;I)</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a09fac3ed84c79268f38c699d988fccb2">fixupDbgVariableRecordsOnInst</a> (Instruction &amp;I)</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#aa94082d9cc8875835efa79034bfaf7a7">placeDbgValues</a> (Function &amp;F)</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#aa678397f87a02f641d55b093ee4b494b">placePseudoProbes</a> (Function &amp;F)</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ac987df3baf35a23470af099afda7a901">canFormExtLd</a> (const SmallVectorImpl&lt; Instruction * &gt; &amp;MovedExts, LoadInst *&amp;LI, Instruction *&amp;Inst, bool HasPromoted)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Return true, if an ext(load) can be formed from an extension in <span class="doxyComputerOutput">MovedExts</span>. <a href="#ac987df3baf35a23470af099afda7a901">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">bool</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a9a02e3d0ad1ea144575f64ba9a95634e">tryToPromoteExts</a> (TypePromotionTransaction &amp;TPT, const SmallVectorImpl&lt; Instruction * &gt; &amp;Exts, SmallVectorImpl&lt; Instruction * &gt; &amp;ProfitablyMovedExts, unsigned CreatedInstsCost=0)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Try to speculatively promote extensions in <span class="doxyComputerOutput">Exts</span> and continue promoting through newly promoted operands recursively as far as doing so is profitable. <a href="#a9a02e3d0ad1ea144575f64ba9a95634e">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">bool</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#af45b1c3fab319bf39030078cd22f6a1a">mergeSExts</a> (Function &amp;F)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Merging redundant sexts when one is dominating the other. <a href="#af45b1c3fab319bf39030078cd22f6a1a">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">bool</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a5980d7c3f3f9b39d852be2cee498acbc">splitLargeGEPOffsets</a> ()</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#af93bf2e7385e69ef9a5537d32b53467c">optimizePhiType</a> (PHINode *Inst, SmallPtrSetImpl&lt; PHINode * &gt; &amp;Visited, SmallPtrSetImpl&lt; Instruction * &gt; &amp;DeletedInstrs)</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a3776577e3bf79df620ee34ce567983a4">optimizePhiTypes</a> (Function &amp;F)</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a1ef6f0046c6311f5f7f2e376f1b4c4f0">performAddressTypePromotion</a> (Instruction *&amp;Inst, bool AllowPromotionWithoutCommonHeader, bool HasPromoted, TypePromotionTransaction &amp;TPT, SmallVectorImpl&lt; Instruction * &gt; &amp;SpeculativelyMovedExts)</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a012eb45f151fde970456d622d79becef">splitBranchCondition</a> (Function &amp;F, ModifyDT &amp;ModifiedDT)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Some targets prefer to split a conditional branch like: <a href="#a012eb45f151fde970456d622d79becef">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">bool</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a895cf8e0468cfd0f5d7a65d127ab2657">simplifyOffsetableRelocate</a> (GCStatepointInst &amp;I)</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#aa4f770d38985ae435db295e10d4ecbe7">tryToSinkFreeOperands</a> (Instruction *I)</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#aedea0e9c1be04102aad0dbfa2560488e">replaceMathCmpWithIntrinsic</a> (BinaryOperator *BO, Value *Arg0, Value *Arg1, CmpInst *Cmp, Intrinsic::ID IID)</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#aa44248d0b8f996cfaabb3fd9df71ad8a">optimizeCmp</a> (CmpInst *Cmp, ModifyDT &amp;ModifiedDT)</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#abfea0186c56640ad5d10657fe279471c">optimizeURem</a> (Instruction *Rem)</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a169836c1a9e8a2827a2d44acf15fc9db">combineToUSubWithOverflow</a> (CmpInst *Cmp, ModifyDT &amp;ModifiedDT)</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a2f1965e8c691f0c73dd7e16bf1433953">combineToUAddWithOverflow</a> (CmpInst *Cmp, ModifyDT &amp;ModifiedDT)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Try to combine the compare into a call to the llvm.uadd.with.overflow intrinsic. <a href="#a2f1965e8c691f0c73dd7e16bf1433953">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">void</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ada74b9df95b7bd64a3b6479cc06ba590">verifyBFIUpdates</a> (Function &amp;F)</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a5a1636536a963c0bec635a22aabae0b1">_run</a> (Function &amp;F)</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">bool</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#aaf22dc443fa1ce5fcf175fcf27dd50fa">IsHugeFunc</a> = false</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>If encounter huge function, we need to limit the build time. <a href="#aaf22dc443fa1ce5fcf175fcf27dd50fa">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/smallset">SmallSet</a>&lt; <a href="/web-llvm/docs/api/classes/llvm/basicblock">BasicBlock</a> *, 32 &gt;</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a3976bdb67704d416ca52fd8a1ead845a">FreshBBs</a></td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>FreshBBs is like worklist, it collected the updated BBs which need to be optimized again. <a href="#a3976bdb67704d416ca52fd8a1ead845a">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

</table>

## Private Member Attributes Index

<table class="doxyMembersIndex">

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/targetmachine">TargetMachine</a> *</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ac7ab22ca458c148de65fb8b943deea58">TM</a> = nullptr</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/targetsubtargetinfo">TargetSubtargetInfo</a> *</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ad2c4a5860836d9d24581cefe71fe1fa7">SubtargetInfo</a> = nullptr</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/targetlowering">TargetLowering</a> *</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a36a9e61fcf4b40e4e9eb953cd5006007">TLI</a> = nullptr</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/targetregisterinfo">TargetRegisterInfo</a> *</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#af4dc1e36f37c37682621e513ae5aab71">TRI</a> = nullptr</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/targettransforminfo">TargetTransformInfo</a> *</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#aa5ca8813f077b3f8c1373ec6a507f1fc">TTI</a> = nullptr</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/basicblocksectionsprofilereader">BasicBlockSectionsProfileReader</a> *</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#aced9c3ba002870c8135a88069ac78804">BBSectionsProfileReader</a> = nullptr</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/targetlibraryinfo">TargetLibraryInfo</a> *</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a434e1e371c4318830b31e68f705ad7b6">TLInfo</a> = nullptr</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a85fed8ffc853b7f46a978e17fe2fe4c4">LI</a> = nullptr</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">std::unique_ptr&lt; <a href="/web-llvm/docs/api/classes/llvm/blockfrequencyinfo">BlockFrequencyInfo</a> &gt;</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#aba2fab722c3b0b47cbc10159ac698921">BFI</a></td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">std::unique_ptr&lt; <a href="/web-llvm/docs/api/classes/llvm/branchprobabilityinfo">BranchProbabilityInfo</a> &gt;</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ac862d0e4372ae2d548f8e50e5bdd1342">BPI</a></td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a6562baca501311590056bce906fbe710">PSI</a> = nullptr</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/basicblock/#a98c0a84a5dfa8bce341c829709f171e5">BasicBlock::iterator</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a0a61253b305c28fc0fc02ac0dfeba7ab">CurInstIterator</a></td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>As we scan instructions optimizing them, this is the next instruction to optimize. <a href="#a0a61253b305c28fc0fc02ac0dfeba7ab">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/valuemap">ValueMap</a>&lt; <a href="/web-llvm/docs/api/classes/llvm/value">Value</a> *, <a href="/web-llvm/docs/api/classes/llvm/weaktrackingvh">WeakTrackingVH</a> &gt;</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a3bb34eab6528acd9f39f7f4d60170140">SunkAddrs</a></td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Keeps track of non-local addresses that have been sunk into a block. <a href="#a3bb34eab6528acd9f39f7f4d60170140">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/namespaces/anonymous-codegenprepare-cpp-/#af2dad33e47a12a0b01b11d97d390f7ee">SetOfInstrs</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a31a6cd022d80e3aae7963285905fb9eb">InsertedInsts</a></td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Keeps track of all instructions inserted for the current function. <a href="#a31a6cd022d80e3aae7963285905fb9eb">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/namespaces/anonymous-codegenprepare-cpp-/#a71622f7f81af67784beaf8b1420aa76d">InstrToOrigTy</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a2c914af3632b09022dca056b80f9285a">PromotedInsts</a></td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Keeps track of the type of the related instruction before their promotion for the current function. <a href="#a2c914af3632b09022dca056b80f9285a">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/namespaces/anonymous-codegenprepare-cpp-/#af2dad33e47a12a0b01b11d97d390f7ee">SetOfInstrs</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#abbdd32f1a7a9e787e8d310f1bcbefe42">RemovedInsts</a></td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Keep track of instructions removed during promotion. <a href="#abbdd32f1a7a9e787e8d310f1bcbefe42">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/densemap">DenseMap</a>&lt; <a href="/web-llvm/docs/api/classes/llvm/value">Value</a> *, <a href="/web-llvm/docs/api/classes/llvm/instruction">Instruction</a> * &gt;</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a77dbd9b78cdf8a35774f3fa2a31c2c3b">SeenChainsForSExt</a></td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Keep track of sext chains based on their initial value. <a href="#a77dbd9b78cdf8a35774f3fa2a31c2c3b">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/mapvector">MapVector</a>&lt; <a href="/web-llvm/docs/api/classes/llvm/assertingvh">AssertingVH</a>&lt; <a href="/web-llvm/docs/api/classes/llvm/value">Value</a> &gt;, <a href="/web-llvm/docs/api/classes/llvm/smallvector">SmallVector</a>&lt; std::pair&lt; <a href="/web-llvm/docs/api/classes/llvm/assertingvh">AssertingVH</a>&lt; <a href="/web-llvm/docs/api/classes/llvm/getelementptrinst">GetElementPtrInst</a> &gt;, int64_t &gt;, 32 &gt; &gt;</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a54b9e60f911bbd107957ec0aabed205a">LargeOffsetGEPMap</a></td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Keep track of GEPs accessing the same data structures such as structs or arrays that are candidates to be split later because of their large size. <a href="#a54b9e60f911bbd107957ec0aabed205a">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/smallset">SmallSet</a>&lt; <a href="/web-llvm/docs/api/classes/llvm/assertingvh">AssertingVH</a>&lt; <a href="/web-llvm/docs/api/classes/llvm/value">Value</a> &gt;, 2 &gt;</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#aeb66fcc600b9528a52cdcf071b47030b">NewGEPBases</a></td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Keep track of new GEP base after splitting the GEPs having large offset. <a href="#aeb66fcc600b9528a52cdcf071b47030b">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/densemap">DenseMap</a>&lt; <a href="/web-llvm/docs/api/classes/llvm/assertingvh">AssertingVH</a>&lt; <a href="/web-llvm/docs/api/classes/llvm/getelementptrinst">GetElementPtrInst</a> &gt;, int &gt;</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ab69d1616b0fc0edf604ca57895b7d048">LargeOffsetGEPID</a></td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Map serial numbers to Large offset GEPs. <a href="#ab69d1616b0fc0edf604ca57895b7d048">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/namespaces/anonymous-codegenprepare-cpp-/#a882043c34b485e559cd3e42b1a4274b2">ValueToSExts</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#addbd90927b3cef37941b6959884c9706">ValToSExtendedUses</a></td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Keep track of SExt promoted. <a href="#addbd90927b3cef37941b6959884c9706">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">bool</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a2fc44d6d2a92b3d69d6095590234057e">OptSize</a></td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>True if the function has the OptSize attribute. <a href="#a2fc44d6d2a92b3d69d6095590234057e">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/datalayout">DataLayout</a> *</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a3df9aef490f35a91696c218f58b6c017">DL</a> = nullptr</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p><a href="/web-llvm/docs/api/classes/llvm/datalayout">DataLayout</a> for the <a href="/web-llvm/docs/api/classes/llvm/function">Function</a> being processed. <a href="#a3df9aef490f35a91696c218f58b6c017">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">std::unique_ptr&lt; <a href="/web-llvm/docs/api/classes/llvm/dominatortree">DominatorTree</a> &gt;</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#aae09e473eac423426f55bb40c6624e62">DT</a></td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Building the dominator tree can be expensive, so we only build it lazily and update it when required. <a href="#aae09e473eac423426f55bb40c6624e62">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

</table>


<p>Definition at line 305 of file <a href="/web-llvm/docs/api/files/lib/lib/codegen/codegenprepare-cpp">CodeGenPrepare.cpp</a>.</p>


<div class="doxySectionDef">

## Friends

### CodeGenPrepareLegacyPass {#add05b1dba7a9938b30736abfceee94bf}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">friend class <a href="/web-llvm/docs/api/classes/anonymous-codegenprepare-cpp-/codegenpreparelegacypass">CodeGenPrepareLegacyPass</a></td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">


<p>Definition at line 306 of file <a href="/web-llvm/docs/api/files/lib/lib/codegen/codegenprepare-cpp">CodeGenPrepare.cpp</a>.</p>


<p>Reference <a href="#add05b1dba7a9938b30736abfceee94bf">CodeGenPrepareLegacyPass</a>.</p>


<p>Referenced by <a href="#add05b1dba7a9938b30736abfceee94bf">CodeGenPrepareLegacyPass</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Public Constructors

### CodeGenPrepare() {#a88c47869c3d6832ba11c5480ba78aa04}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">anonymous{CodeGenPrepare.cpp}::CodeGenPrepare::CodeGenPrepare ()</td>
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



<p>Definition at line 370 of file <a href="/web-llvm/docs/api/files/lib/lib/codegen/codegenprepare-cpp">CodeGenPrepare.cpp</a>.</p>

</div>
</div>

### CodeGenPrepare() {#a2fab09a0564f5203372a75e51f20b526}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">anonymous{CodeGenPrepare.cpp}::CodeGenPrepare::CodeGenPrepare (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/targetmachine">TargetMachine</a> * TM)</td>
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



<p>Definition at line 371 of file <a href="/web-llvm/docs/api/files/lib/lib/codegen/codegenprepare-cpp">CodeGenPrepare.cpp</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Public Member Functions

### releaseMemory() {#a603cbf2855141608521f6709cdfb126f}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void anonymous{CodeGenPrepare.cpp}::CodeGenPrepare::releaseMemory ()</td>
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



<p>Definition at line 381 of file <a href="/web-llvm/docs/api/files/lib/lib/codegen/codegenprepare-cpp">CodeGenPrepare.cpp</a>.</p>


<p>Reference <a href="#a3976bdb67704d416ca52fd8a1ead845a">FreshBBs</a>.</p>

</div>
</div>

### run() {#aa963097f89a02195cba904f74c5e0f71}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool CodeGenPrepare::run (<a href="/web-llvm/docs/api/classes/llvm/function">Function</a> &amp; F, <a href="/web-llvm/docs/api/namespaces/llvm/#adce09a5a0de0e3177eb00e932734af2f">FunctionAnalysisManager</a> &amp; AM)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 390 of file <a href="/web-llvm/docs/api/files/lib/lib/codegen/codegenprepare-cpp">CodeGenPrepare.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/files/lib/lib/support/md5-cpp/#a96d73bbd7af15cb1fc38c3f4a3bd82e9">F</a>, <a href="/web-llvm/docs/api/classes/llvm/analysismanager/#a828ff8185f881fca9e3d534781244041">llvm::AnalysisManager&lt; IRUnitT, ExtraArgTs &gt;::getCachedResult</a> and <a href="/web-llvm/docs/api/classes/llvm/analysismanager/#aaab1fad63e4f3b8679469720a873fedd">llvm::AnalysisManager&lt; IRUnitT, ExtraArgTs &gt;::getResult</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Private Member Functions

### \_run() {#a5a1636536a963c0bec635a22aabae0b1}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool CodeGenPrepare::_run (<a href="/web-llvm/docs/api/classes/llvm/function">Function</a> &amp; F)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 478 of file <a href="/web-llvm/docs/api/files/lib/lib/codegen/codegenprepare-cpp">CodeGenPrepare.cpp</a>.</p>

</div>
</div>

### canFormExtLd() {#ac987df3baf35a23470af099afda7a901}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool CodeGenPrepare::canFormExtLd (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/smallvectorimpl">SmallVectorImpl</a>&lt; <a href="/web-llvm/docs/api/classes/llvm/instruction">Instruction</a> * &gt; &amp; MovedExts, <a href="/web-llvm/docs/api/classes/llvm/loadinst">LoadInst</a> *&amp; LI, <a href="/web-llvm/docs/api/classes/llvm/instruction">Instruction</a> *&amp; Inst, bool HasPromoted)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Return true, if an ext(load) can be formed from an extension in <span class="doxyComputerOutput">MovedExts</span>.</p>

<p>Definition at line 452 of file <a href="/web-llvm/docs/api/files/lib/lib/codegen/codegenprepare-cpp">CodeGenPrepare.cpp</a>.</p>

</div>
</div>

### canMergeBlocks() {#adae1a5b888e2f1cae3a8e27539b57a96}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool CodeGenPrepare::canMergeBlocks (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/basicblock">BasicBlock</a> * BB, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/basicblock">BasicBlock</a> * DestBB)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Return true if we can merge BB into DestBB if there is a single unconditional branch between them, and BB contains no other non-phi instructions.</p>

<p>Definition at line 423 of file <a href="/web-llvm/docs/api/files/lib/lib/codegen/codegenprepare-cpp">CodeGenPrepare.cpp</a>.</p>

</div>
</div>

### combineToUAddWithOverflow() {#a2f1965e8c691f0c73dd7e16bf1433953}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool CodeGenPrepare::combineToUAddWithOverflow (<a href="/web-llvm/docs/api/classes/llvm/cmpinst">CmpInst</a> * Cmp, <a href="/web-llvm/docs/api/namespaces/anonymous-codegenprepare-cpp-/#af5758ce8e1ea07d0c154e97556db4379">ModifyDT</a> &amp; ModifiedDT)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Try to combine the compare into a call to the llvm.uadd.with.overflow intrinsic.</p>


<p>Return true if any changes were made.</p>


<p>Definition at line 476 of file <a href="/web-llvm/docs/api/files/lib/lib/codegen/codegenprepare-cpp">CodeGenPrepare.cpp</a>.</p>

</div>
</div>

### combineToUSubWithOverflow() {#a169836c1a9e8a2827a2d44acf15fc9db}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool CodeGenPrepare::combineToUSubWithOverflow (<a href="/web-llvm/docs/api/classes/llvm/cmpinst">CmpInst</a> * Cmp, <a href="/web-llvm/docs/api/namespaces/anonymous-codegenprepare-cpp-/#af5758ce8e1ea07d0c154e97556db4379">ModifyDT</a> &amp; ModifiedDT)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 475 of file <a href="/web-llvm/docs/api/files/lib/lib/codegen/codegenprepare-cpp">CodeGenPrepare.cpp</a>.</p>

</div>
</div>

### dupRetToEnableTailCallOpts() {#a29a32e999bef6e6fd8876e11332fc8a8}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool CodeGenPrepare::dupRetToEnableTailCallOpts (<a href="/web-llvm/docs/api/classes/llvm/basicblock">BasicBlock</a> * BB, <a href="/web-llvm/docs/api/namespaces/anonymous-codegenprepare-cpp-/#af5758ce8e1ea07d0c154e97556db4379">ModifyDT</a> &amp; ModifiedDT)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Look for opportunities to duplicate return instructions to the predecessor to enable tail call optimizations.</p>


<p>The case it is currently looking for is the following one. Known intrinsics or library function that may be tail called are taken into account as well.</p>


<div class="doxyProgramListing">

<div class="doxyCodeLine"><span class="doxyNoLineNumber">&nbsp;</span><span class="doxyLineContent"><span class="doxyHighlight">bb0:</span></span></div>
<div class="doxyCodeLine"><span class="doxyNoLineNumber">&nbsp;</span><span class="doxyLineContent"><span class="doxyHighlight">  %tmp0 = tail call i32 @f0()</span></span></div>
<div class="doxyCodeLine"><span class="doxyNoLineNumber">&nbsp;</span><span class="doxyLineContent"><span class="doxyHighlight">  br label %return</span></span></div>
<div class="doxyCodeLine"><span class="doxyNoLineNumber">&nbsp;</span><span class="doxyLineContent"><span class="doxyHighlight">bb1:</span></span></div>
<div class="doxyCodeLine"><span class="doxyNoLineNumber">&nbsp;</span><span class="doxyLineContent"><span class="doxyHighlight">  %tmp1 = tail call i32 @f1()</span></span></div>
<div class="doxyCodeLine"><span class="doxyNoLineNumber">&nbsp;</span><span class="doxyLineContent"><span class="doxyHighlight">  br label %return</span></span></div>
<div class="doxyCodeLine"><span class="doxyNoLineNumber">&nbsp;</span><span class="doxyLineContent"><span class="doxyHighlight">bb2:</span></span></div>
<div class="doxyCodeLine"><span class="doxyNoLineNumber">&nbsp;</span><span class="doxyLineContent"><span class="doxyHighlight">  %tmp2 = tail call i32 @f2()</span></span></div>
<div class="doxyCodeLine"><span class="doxyNoLineNumber">&nbsp;</span><span class="doxyLineContent"><span class="doxyHighlight">  br label %return</span></span></div>
<div class="doxyCodeLine"><span class="doxyNoLineNumber">&nbsp;</span><span class="doxyLineContent"><span class="doxyHighlight">return:</span></span></div>
<div class="doxyCodeLine"><span class="doxyNoLineNumber">&nbsp;</span><span class="doxyLineContent"><span class="doxyHighlight">  %retval = phi i32 [ %tmp0, %bb0 ], [ %tmp1, %bb1 ], [ %tmp2, %bb2 ]</span></span></div>
<div class="doxyCodeLine"><span class="doxyNoLineNumber">&nbsp;</span><span class="doxyLineContent"><span class="doxyHighlight">  ret i32 %retval</span></span></div>

</div>


<p>=&gt;</p>


<div class="doxyProgramListing">

<div class="doxyCodeLine"><span class="doxyNoLineNumber">&nbsp;</span><span class="doxyLineContent"><span class="doxyHighlight">bb0:</span></span></div>
<div class="doxyCodeLine"><span class="doxyNoLineNumber">&nbsp;</span><span class="doxyLineContent"><span class="doxyHighlight">  %tmp0 = tail call i32 @f0()</span></span></div>
<div class="doxyCodeLine"><span class="doxyNoLineNumber">&nbsp;</span><span class="doxyLineContent"><span class="doxyHighlight">  ret i32 %tmp0</span></span></div>
<div class="doxyCodeLine"><span class="doxyNoLineNumber">&nbsp;</span><span class="doxyLineContent"><span class="doxyHighlight">bb1:</span></span></div>
<div class="doxyCodeLine"><span class="doxyNoLineNumber">&nbsp;</span><span class="doxyLineContent"><span class="doxyHighlight">  %tmp1 = tail call i32 @f1()</span></span></div>
<div class="doxyCodeLine"><span class="doxyNoLineNumber">&nbsp;</span><span class="doxyLineContent"><span class="doxyHighlight">  ret i32 %tmp1</span></span></div>
<div class="doxyCodeLine"><span class="doxyNoLineNumber">&nbsp;</span><span class="doxyLineContent"><span class="doxyHighlight">bb2:</span></span></div>
<div class="doxyCodeLine"><span class="doxyNoLineNumber">&nbsp;</span><span class="doxyLineContent"><span class="doxyHighlight">  %tmp2 = tail call i32 @f2()</span></span></div>
<div class="doxyCodeLine"><span class="doxyNoLineNumber">&nbsp;</span><span class="doxyLineContent"><span class="doxyHighlight">  ret i32 %tmp2</span></span></div>

</div>


<p>Definition at line 446 of file <a href="/web-llvm/docs/api/files/lib/lib/codegen/codegenprepare-cpp">CodeGenPrepare.cpp</a>.</p>

</div>
</div>

### eliminateAssumptions() {#a3dcd746570792e10cf6a0d674e0bcfc1}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool CodeGenPrepare::eliminateAssumptions (<a href="/web-llvm/docs/api/classes/llvm/function">Function</a> &amp; F)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 419 of file <a href="/web-llvm/docs/api/files/lib/lib/codegen/codegenprepare-cpp">CodeGenPrepare.cpp</a>.</p>

</div>
</div>

### eliminateFallThrough() {#ac52c20dcc2816650d2391094a7130e19}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool CodeGenPrepare::eliminateFallThrough (<a href="/web-llvm/docs/api/classes/llvm/function">Function</a> &amp; F, <a href="/web-llvm/docs/api/classes/llvm/dominatortree">DominatorTree</a> * DT=nullptr)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Merge basic blocks which are connected by a single edge, where one of the basic blocks has a single successor pointing to the other basic block, which has a single predecessor.</p>

<p>Definition at line 420 of file <a href="/web-llvm/docs/api/files/lib/lib/codegen/codegenprepare-cpp">CodeGenPrepare.cpp</a>.</p>

</div>
</div>

### eliminateMostlyEmptyBlock() {#a7cde84775859537191b0ef8ff50a6a64}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void CodeGenPrepare::eliminateMostlyEmptyBlock (<a href="/web-llvm/docs/api/classes/llvm/basicblock">BasicBlock</a> * BB)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Eliminate a basic block that has only phi's and an unconditional branch in it.</p>

<p>Definition at line 424 of file <a href="/web-llvm/docs/api/files/lib/lib/codegen/codegenprepare-cpp">CodeGenPrepare.cpp</a>.</p>

</div>
</div>

### eliminateMostlyEmptyBlocks() {#a8a98f2fc2e044e5c49e08dc512e9766d}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool CodeGenPrepare::eliminateMostlyEmptyBlocks (<a href="/web-llvm/docs/api/classes/llvm/function">Function</a> &amp; F)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Eliminate blocks that contain only PHI nodes, debug info directives, and an unconditional branch.</p>


<p>Passes before isel (e.g. LSR/loopsimplify) often split edges in ways that are non-optimal for isel. Start by eliminating these blocks so we can split them the way we want them.</p>


<p>Definition at line 421 of file <a href="/web-llvm/docs/api/files/lib/lib/codegen/codegenprepare-cpp">CodeGenPrepare.cpp</a>.</p>

</div>
</div>

### findDestBlockOfMergeableEmptyBlock() {#ae885a922e6c608baa4b10f4c344ff8f9}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">BasicBlock * CodeGenPrepare::findDestBlockOfMergeableEmptyBlock (<a href="/web-llvm/docs/api/classes/llvm/basicblock">BasicBlock</a> * BB)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Find a destination block from BB if BB is mergeable empty block.</p>

<p>Definition at line 422 of file <a href="/web-llvm/docs/api/files/lib/lib/codegen/codegenprepare-cpp">CodeGenPrepare.cpp</a>.</p>

</div>
</div>

### fixupDbgValue() {#ae9b9cffc69c81998e5349bb85ab4886e}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool CodeGenPrepare::fixupDbgValue (<a href="/web-llvm/docs/api/classes/llvm/instruction">Instruction</a> * I)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 447 of file <a href="/web-llvm/docs/api/files/lib/lib/codegen/codegenprepare-cpp">CodeGenPrepare.cpp</a>.</p>

</div>
</div>

### fixupDbgVariableRecord() {#ad513cf759e58690876c6d228372c0727}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool CodeGenPrepare::fixupDbgVariableRecord (<a href="/web-llvm/docs/api/classes/llvm/dbgvariablerecord">DbgVariableRecord</a> &amp; I)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 448 of file <a href="/web-llvm/docs/api/files/lib/lib/codegen/codegenprepare-cpp">CodeGenPrepare.cpp</a>.</p>

</div>
</div>

### fixupDbgVariableRecordsOnInst() {#a09fac3ed84c79268f38c699d988fccb2}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool CodeGenPrepare::fixupDbgVariableRecordsOnInst (<a href="/web-llvm/docs/api/classes/llvm/instruction">Instruction</a> &amp; I)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 449 of file <a href="/web-llvm/docs/api/files/lib/lib/codegen/codegenprepare-cpp">CodeGenPrepare.cpp</a>.</p>

</div>
</div>

### getDT() {#a4c148ccce69d6cc369ffd4f1af74db3c}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">DominatorTree &amp; anonymous{CodeGenPrepare.cpp}::CodeGenPrepare::getDT (<a href="/web-llvm/docs/api/classes/llvm/function">Function</a> &amp; F)</td>
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



<p>Definition at line 412 of file <a href="/web-llvm/docs/api/files/lib/lib/codegen/codegenprepare-cpp">CodeGenPrepare.cpp</a>.</p>

</div>
</div>

### isMergingEmptyBlockProfitable() {#a78ca6c4dfaa10c937e5498a8e89c3e5f}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool CodeGenPrepare::isMergingEmptyBlockProfitable (<a href="/web-llvm/docs/api/classes/llvm/basicblock">BasicBlock</a> * BB, <a href="/web-llvm/docs/api/classes/llvm/basicblock">BasicBlock</a> * DestBB, bool isPreheader)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 425 of file <a href="/web-llvm/docs/api/files/lib/lib/codegen/codegenprepare-cpp">CodeGenPrepare.cpp</a>.</p>

</div>
</div>

### makeBitReverse() {#a88540618571df605c6a8afcc1dda31b2}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool CodeGenPrepare::makeBitReverse (<a href="/web-llvm/docs/api/classes/llvm/instruction">Instruction</a> &amp; I)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Given an OR instruction, check to see if this is a bitreverse idiom.</p>


<p>If so, insert the new intrinsic and return true.</p>


<p>Definition at line 427 of file <a href="/web-llvm/docs/api/files/lib/lib/codegen/codegenprepare-cpp">CodeGenPrepare.cpp</a>.</p>

</div>
</div>

### mergeSExts() {#af45b1c3fab319bf39030078cd22f6a1a}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool CodeGenPrepare::mergeSExts (<a href="/web-llvm/docs/api/classes/llvm/function">Function</a> &amp; F)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Merging redundant sexts when one is dominating the other.</p>

<p>Definition at line 458 of file <a href="/web-llvm/docs/api/files/lib/lib/codegen/codegenprepare-cpp">CodeGenPrepare.cpp</a>.</p>

</div>
</div>

### optimizeBlock() {#a76f689d898c02e67ec20b7f989f3d9cc}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool CodeGenPrepare::optimizeBlock (<a href="/web-llvm/docs/api/classes/llvm/basicblock">BasicBlock</a> &amp; BB, <a href="/web-llvm/docs/api/namespaces/anonymous-codegenprepare-cpp-/#af5758ce8e1ea07d0c154e97556db4379">ModifyDT</a> &amp; ModifiedDT)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 428 of file <a href="/web-llvm/docs/api/files/lib/lib/codegen/codegenprepare-cpp">CodeGenPrepare.cpp</a>.</p>

</div>
</div>

### optimizeCallInst() {#a5e71ce5490f551bc23302493c0085350}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool CodeGenPrepare::optimizeCallInst (<a href="/web-llvm/docs/api/classes/llvm/callinst">CallInst</a> * CI, <a href="/web-llvm/docs/api/namespaces/anonymous-codegenprepare-cpp-/#af5758ce8e1ea07d0c154e97556db4379">ModifyDT</a> &amp; ModifiedDT)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 434 of file <a href="/web-llvm/docs/api/files/lib/lib/codegen/codegenprepare-cpp">CodeGenPrepare.cpp</a>.</p>

</div>
</div>

### optimizeCmp() {#aa44248d0b8f996cfaabb3fd9df71ad8a}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool CodeGenPrepare::optimizeCmp (<a href="/web-llvm/docs/api/classes/llvm/cmpinst">CmpInst</a> * Cmp, <a href="/web-llvm/docs/api/namespaces/anonymous-codegenprepare-cpp-/#af5758ce8e1ea07d0c154e97556db4379">ModifyDT</a> &amp; ModifiedDT)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 473 of file <a href="/web-llvm/docs/api/files/lib/lib/codegen/codegenprepare-cpp">CodeGenPrepare.cpp</a>.</p>

</div>
</div>

### optimizeExt() {#a6df2c21c695e9f4b2daffadc78315161}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool CodeGenPrepare::optimizeExt (<a href="/web-llvm/docs/api/classes/llvm/instruction">Instruction</a> *&amp; Inst)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Move a zext or sext fed by a load into the same basic block as the load, unless conditions are unfavorable.</p>


<p>This allows <a href="/web-llvm/docs/api/classes/llvm/selectiondag">SelectionDAG</a> to fold the extend into the load.</p>


<p>E.g.,</p>


<div class="doxyProgramListing">

<div class="doxyCodeLine"><span class="doxyNoLineNumber">&nbsp;</span><span class="doxyLineContent"><span class="doxyHighlight">%ld = <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/amdgpumarklastscratchload-cpp/#a8a3fe89940744b94ffe5dacd6704c2be">load</a> i32* %addr</span></span></div>
<div class="doxyCodeLine"><span class="doxyNoLineNumber">&nbsp;</span><span class="doxyLineContent"><span class="doxyHighlight">%<a href="/web-llvm/docs/api/namespaces/llvm/arm-am/#a5d0557608eaebed12bc00812724ba2cdae6bcee28992dab735eaa43f5dfa48a09">add</a> = <a href="/web-llvm/docs/api/namespaces/llvm/arm-am/#a5d0557608eaebed12bc00812724ba2cdae6bcee28992dab735eaa43f5dfa48a09">add</a> nuw i32 %ld, 4</span></span></div>
<div class="doxyCodeLine"><span class="doxyNoLineNumber">&nbsp;</span><span class="doxyLineContent"><span class="doxyHighlight">%zext = zext i32 %<a href="/web-llvm/docs/api/namespaces/llvm/arm-am/#a5d0557608eaebed12bc00812724ba2cdae6bcee28992dab735eaa43f5dfa48a09">add</a> to i64 */</span></span></div>

</div>


<p>/** =&gt;</p>


<div class="doxyProgramListing">

<div class="doxyCodeLine"><span class="doxyNoLineNumber">&nbsp;</span><span class="doxyLineContent"><span class="doxyHighlight">%ld = <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/amdgpumarklastscratchload-cpp/#a8a3fe89940744b94ffe5dacd6704c2be">load</a> i32* %addr</span></span></div>
<div class="doxyCodeLine"><span class="doxyNoLineNumber">&nbsp;</span><span class="doxyLineContent"><span class="doxyHighlight">%zext = zext i32 %ld to i64</span></span></div>
<div class="doxyCodeLine"><span class="doxyNoLineNumber">&nbsp;</span><span class="doxyLineContent"><span class="doxyHighlight">%<a href="/web-llvm/docs/api/namespaces/llvm/arm-am/#a5d0557608eaebed12bc00812724ba2cdae6bcee28992dab735eaa43f5dfa48a09">add</a> = <a href="/web-llvm/docs/api/namespaces/llvm/arm-am/#a5d0557608eaebed12bc00812724ba2cdae6bcee28992dab735eaa43f5dfa48a09">add</a> nuw i64 %zext, 4</span></span></div>
<div class="doxyCodeLine"><span class="doxyNoLineNumber">&nbsp;</span><span class="doxyLineContent"><span class="doxyHighlight">\<a href="/web-llvm/docs/api/namespaces/llvm/#a15ce86953ef9122361a5be3aba654272">encode</a></span></span></div>
<div class="doxyCodeLine"><span class="doxyNoLineNumber">&nbsp;</span><span class="doxyLineContent"><span class="doxyHighlight"><a href="/web-llvm/docs/api/namespaces/llvm/#ac226f3d2b9ca090171a8e0a8cb92c343a3b0649c72650c313a357338dcdfb64ec">Note</a> that the promotion in %<a href="/web-llvm/docs/api/namespaces/llvm/arm-am/#a5d0557608eaebed12bc00812724ba2cdae6bcee28992dab735eaa43f5dfa48a09">add</a> to i64 is done in tryToPromoteExts(), which</span></span></div>
<div class="doxyCodeLine"><span class="doxyNoLineNumber">&nbsp;</span><span class="doxyLineContent"><span class="doxyHighlight">allow us to <a href="/web-llvm/docs/api/namespaces/llvm/scevpatternmatch/#ac7955a91d3f8f0d5caff3879f0778e82">match</a> zext(<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/amdgpumarklastscratchload-cpp/#a8a3fe89940744b94ffe5dacd6704c2be">load</a> i32*) to i64.</span></span></div>
<div class="doxyCodeLine"><span class="doxyNoLineNumber">&nbsp;</span></div>
<div class="doxyCodeLine"><span class="doxyNoLineNumber">&nbsp;</span><span class="doxyLineContent"><span class="doxyHighlight">Also, </span><span class="doxyHighlightKeywordFlow">try</span><span class="doxyHighlight"> to promote the computations used to obtain a sign extended</span></span></div>
<div class="doxyCodeLine"><span class="doxyNoLineNumber">&nbsp;</span><span class="doxyLineContent"><span class="doxyHighlight">value used into memory accesses.</span></span></div>
<div class="doxyCodeLine"><span class="doxyNoLineNumber">&nbsp;</span><span class="doxyLineContent"><span class="doxyHighlight">E.g.,</span></span></div>
<div class="doxyCodeLine"><span class="doxyNoLineNumber">&nbsp;</span><span class="doxyLineContent"><span class="doxyHighlight">\code</span></span></div>
<div class="doxyCodeLine"><span class="doxyNoLineNumber">&nbsp;</span><span class="doxyLineContent"><span class="doxyHighlight">a = <a href="/web-llvm/docs/api/namespaces/llvm/arm-am/#a5d0557608eaebed12bc00812724ba2cdae6bcee28992dab735eaa43f5dfa48a09">add</a> nsw i32 <a href="/web-llvm/docs/api/namespaces/llvm/m68k/#ab3a288f2953d8eca3e363959fc2cf38ea92eb5ffee6ae2fec3ad71c777531578f">b</a>, 3</span></span></div>
<div class="doxyCodeLine"><span class="doxyNoLineNumber">&nbsp;</span><span class="doxyLineContent"><span class="doxyHighlight">d = sext i32 a to i64</span></span></div>
<div class="doxyCodeLine"><span class="doxyNoLineNumber">&nbsp;</span><span class="doxyLineContent"><span class="doxyHighlight"><a href="/web-llvm/docs/api/namespaces/llvm/numbers/#a92f4283d4e0e2ea1776894b3ae93640f">e</a> = getelementptr ..., i64 d</span></span></div>

</div>


<p>=&gt;</p>


<div class="doxyProgramListing">

<div class="doxyCodeLine"><span class="doxyNoLineNumber">&nbsp;</span><span class="doxyLineContent"><span class="doxyHighlight"><a href="/web-llvm/docs/api/namespaces/llvm/m68k/#ab3a288f2953d8eca3e363959fc2cf38ea8fa14cdd754f91cc6554c9e71929cce7">f</a> = sext i32 <a href="/web-llvm/docs/api/namespaces/llvm/m68k/#ab3a288f2953d8eca3e363959fc2cf38ea92eb5ffee6ae2fec3ad71c777531578f">b</a> to i64</span></span></div>
<div class="doxyCodeLine"><span class="doxyNoLineNumber">&nbsp;</span><span class="doxyLineContent"><span class="doxyHighlight">a = <a href="/web-llvm/docs/api/namespaces/llvm/arm-am/#a5d0557608eaebed12bc00812724ba2cdae6bcee28992dab735eaa43f5dfa48a09">add</a> nsw i64 <a href="/web-llvm/docs/api/namespaces/llvm/m68k/#ab3a288f2953d8eca3e363959fc2cf38ea8fa14cdd754f91cc6554c9e71929cce7">f</a>, 3</span></span></div>
<div class="doxyCodeLine"><span class="doxyNoLineNumber">&nbsp;</span><span class="doxyLineContent"><span class="doxyHighlight"><a href="/web-llvm/docs/api/namespaces/llvm/numbers/#a92f4283d4e0e2ea1776894b3ae93640f">e</a> = getelementptr ..., i64 a</span></span></div>

</div>


<p><span class="doxyComputerOutput">Inst</span>[in/out] the extension may be modified during the process if some promotions apply.</p>


<p>Definition at line 435 of file <a href="/web-llvm/docs/api/files/lib/lib/codegen/codegenprepare-cpp">CodeGenPrepare.cpp</a>.</p>

</div>
</div>

### optimizeExtractElementInst() {#a2b04fd8d828ff9353eadb53454feaa12}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool CodeGenPrepare::optimizeExtractElementInst (<a href="/web-llvm/docs/api/classes/llvm/instruction">Instruction</a> * Inst)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Some targets can do store(extractelement) with one instruction.</p>


<p>Try to push the extractelement towards the stores when the target has this feature and this is profitable.</p>


<p>Definition at line 445 of file <a href="/web-llvm/docs/api/files/lib/lib/codegen/codegenprepare-cpp">CodeGenPrepare.cpp</a>.</p>

</div>
</div>

### optimizeExtUses() {#a0120cd06c7eb8a6da3bbc5ce8c21b246}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool CodeGenPrepare::optimizeExtUses (<a href="/web-llvm/docs/api/classes/llvm/instruction">Instruction</a> * I)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 436 of file <a href="/web-llvm/docs/api/files/lib/lib/codegen/codegenprepare-cpp">CodeGenPrepare.cpp</a>.</p>

</div>
</div>

### optimizeFunnelShift() {#ad631003806d9185e7996c19bc641a759}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool CodeGenPrepare::optimizeFunnelShift (<a href="/web-llvm/docs/api/classes/llvm/intrinsicinst">IntrinsicInst</a> * Fsh)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 439 of file <a href="/web-llvm/docs/api/files/lib/lib/codegen/codegenprepare-cpp">CodeGenPrepare.cpp</a>.</p>

</div>
</div>

### optimizeGatherScatterInst() {#ae01c9a10c8ff78ab53ad052a3ba0da3d}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool CodeGenPrepare::optimizeGatherScatterInst (<a href="/web-llvm/docs/api/classes/llvm/instruction">Instruction</a> * MemoryInst, <a href="/web-llvm/docs/api/classes/llvm/value">Value</a> * Ptr)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Rewrite GEP input to gather/scatter to enable <a href="/web-llvm/docs/api/classes/llvm/selectiondagbuilder">SelectionDAGBuilder</a> to find a uniform base to use for <a href="/web-llvm/docs/api/namespaces/llvm/isd/#a22ea9cec080dd5f4f47ba234c2f59110ab4685260a7e506fe51f17d9b600349c8">ISD::MGATHER</a>/MSCATTER.</p>


<p><a href="/web-llvm/docs/api/classes/llvm/selectiondagbuilder">SelectionDAGBuilder</a> can only handle a 2 operand GEP in the same basic block or a splat constant vector. The 2 operands to the GEP must have a scalar pointer and a vector index.</p>


<p>If the existing GEP has a vector base pointer that is splat, we can look through the splat to find the scalar pointer. If we can't find a scalar pointer there's nothing we can do.</p>


<p>If we have a GEP with more than 2 indices where the middle indices are all zeroes, we can replace it with 2 GEPs where the second has 2 operands.</p>


<p>If the final index isn't a vector or is a splat, we can emit a scalar GEP followed by a GEP with an all zeroes vector index. This will enable <a href="/web-llvm/docs/api/classes/llvm/selectiondagbuilder">SelectionDAGBuilder</a> to use the scalar GEP as the uniform base and have a zero index.</p>


<p>Definition at line 432 of file <a href="/web-llvm/docs/api/files/lib/lib/codegen/codegenprepare-cpp">CodeGenPrepare.cpp</a>.</p>

</div>
</div>

### optimizeInlineAsmInst() {#acdc7dab18d5d084b8575d1b74ee3a148}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool CodeGenPrepare::optimizeInlineAsmInst (<a href="/web-llvm/docs/api/classes/llvm/callinst">CallInst</a> * CS)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>If there are any memory operands, use OptimizeMemoryInst to sink their address computing into the block when possible / profitable.</p>

<p>Definition at line 433 of file <a href="/web-llvm/docs/api/files/lib/lib/codegen/codegenprepare-cpp">CodeGenPrepare.cpp</a>.</p>

</div>
</div>

### optimizeInst() {#a8c882a84c5e053c5357f20e964cb931f}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool CodeGenPrepare::optimizeInst (<a href="/web-llvm/docs/api/classes/llvm/instruction">Instruction</a> * I, <a href="/web-llvm/docs/api/namespaces/anonymous-codegenprepare-cpp-/#af5758ce8e1ea07d0c154e97556db4379">ModifyDT</a> &amp; ModifiedDT)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 429 of file <a href="/web-llvm/docs/api/files/lib/lib/codegen/codegenprepare-cpp">CodeGenPrepare.cpp</a>.</p>

</div>
</div>

### optimizeLoadExt() {#a391adeee5b39aa16cf62049001ca645f}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool CodeGenPrepare::optimizeLoadExt (<a href="/web-llvm/docs/api/classes/llvm/loadinst">LoadInst</a> * Load)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 437 of file <a href="/web-llvm/docs/api/files/lib/lib/codegen/codegenprepare-cpp">CodeGenPrepare.cpp</a>.</p>

</div>
</div>

### optimizeMemoryInst() {#afd8b9969b84a5af5e0cb3bfb01396efe}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool CodeGenPrepare::optimizeMemoryInst (<a href="/web-llvm/docs/api/classes/llvm/instruction">Instruction</a> * MemoryInst, <a href="/web-llvm/docs/api/classes/llvm/value">Value</a> * Addr, <a href="/web-llvm/docs/api/classes/llvm/type">Type</a> * AccessTy, unsigned AddrSpace)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Sink addressing mode computation immediate before MemoryInst if doing so can be done without increasing register pressure.</p>


<p>The need for the register pressure constraint means this can end up being an all or nothing decision for all uses of the same addressing computation.</p>


<p>Load and Store Instructions often have addressing modes that can do significant amounts of computation. As such, instruction selection will try to get the load or store to do as much computation as possible for the program. The problem is that isel can only see within a single block. As such, we sink as much legal addressing mode work into the block as possible.</p>


<p>This method is used to optimize both load/store and inline asms with memory operands. It's also used to sink addressing computations feeding into cold call sites into their (cold) basic block.</p>


<p>The motivation for handling sinking into cold blocks is that doing so can both enable other address mode sinking (by satisfying the register pressure constraint above), and reduce register pressure globally (by removing the addressing mode computation from the fast path entirely.).</p>


<p>Definition at line 430 of file <a href="/web-llvm/docs/api/files/lib/lib/codegen/codegenprepare-cpp">CodeGenPrepare.cpp</a>.</p>

</div>
</div>

### optimizePhiType() {#af93bf2e7385e69ef9a5537d32b53467c}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool CodeGenPrepare::optimizePhiType (<a href="/web-llvm/docs/api/classes/llvm/phinode">PHINode</a> * Inst, <a href="/web-llvm/docs/api/classes/llvm/smallptrsetimpl">SmallPtrSetImpl</a>&lt; <a href="/web-llvm/docs/api/classes/llvm/phinode">PHINode</a> * &gt; &amp; Visited, <a href="/web-llvm/docs/api/classes/llvm/smallptrsetimpl">SmallPtrSetImpl</a>&lt; <a href="/web-llvm/docs/api/classes/llvm/instruction">Instruction</a> * &gt; &amp; DeletedInstrs)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 460 of file <a href="/web-llvm/docs/api/files/lib/lib/codegen/codegenprepare-cpp">CodeGenPrepare.cpp</a>.</p>

</div>
</div>

### optimizePhiTypes() {#a3776577e3bf79df620ee34ce567983a4}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool CodeGenPrepare::optimizePhiTypes (<a href="/web-llvm/docs/api/classes/llvm/function">Function</a> &amp; F)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 462 of file <a href="/web-llvm/docs/api/files/lib/lib/codegen/codegenprepare-cpp">CodeGenPrepare.cpp</a>.</p>

</div>
</div>

### optimizeSelectInst() {#acfd60d0907cc0c992181890a76c01fb5}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool CodeGenPrepare::optimizeSelectInst (<a href="/web-llvm/docs/api/classes/llvm/selectinst">SelectInst</a> * SI)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>If we have a <a href="/web-llvm/docs/api/classes/llvm/selectinst">SelectInst</a> that will likely profit from branch prediction, turn it into a branch.</p>

<p>Definition at line 440 of file <a href="/web-llvm/docs/api/files/lib/lib/codegen/codegenprepare-cpp">CodeGenPrepare.cpp</a>.</p>

</div>
</div>

### optimizeShiftInst() {#a8b3c1b5ac856dcbab367e6f861bd7fc6}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool CodeGenPrepare::optimizeShiftInst (<a href="/web-llvm/docs/api/classes/llvm/binaryoperator">BinaryOperator</a> * BO)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 438 of file <a href="/web-llvm/docs/api/files/lib/lib/codegen/codegenprepare-cpp">CodeGenPrepare.cpp</a>.</p>

</div>
</div>

### optimizeShuffleVectorInst() {#a57be619ad0dcc9b77665d4fb62a81003}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool CodeGenPrepare::optimizeShuffleVectorInst (<a href="/web-llvm/docs/api/classes/llvm/shufflevectorinst">ShuffleVectorInst</a> * SVI)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Some targets only accept certain types for splat inputs.</p>


<p>For example a VDUP in MVE takes a GPR (integer) register, and the instruction that incorporate a VDUP (such as a VADD qd, qm, rm) also require a gpr register.</p>


<p>Definition at line 441 of file <a href="/web-llvm/docs/api/files/lib/lib/codegen/codegenprepare-cpp">CodeGenPrepare.cpp</a>.</p>

</div>
</div>

### optimizeSwitchInst() {#a12f2bc1d5d97f6f3f257b3a2de7b0290}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool CodeGenPrepare::optimizeSwitchInst (<a href="/web-llvm/docs/api/classes/llvm/switchinst">SwitchInst</a> * SI)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 444 of file <a href="/web-llvm/docs/api/files/lib/lib/codegen/codegenprepare-cpp">CodeGenPrepare.cpp</a>.</p>

</div>
</div>

### optimizeSwitchPhiConstants() {#a7baeeb27daa2e0e307aac0c6778486b0}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool CodeGenPrepare::optimizeSwitchPhiConstants (<a href="/web-llvm/docs/api/classes/llvm/switchinst">SwitchInst</a> * SI)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 443 of file <a href="/web-llvm/docs/api/files/lib/lib/codegen/codegenprepare-cpp">CodeGenPrepare.cpp</a>.</p>

</div>
</div>

### optimizeSwitchType() {#aadedf13a700b332f76fb1e3b2c3dbcc8}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool CodeGenPrepare::optimizeSwitchType (<a href="/web-llvm/docs/api/classes/llvm/switchinst">SwitchInst</a> * SI)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 442 of file <a href="/web-llvm/docs/api/files/lib/lib/codegen/codegenprepare-cpp">CodeGenPrepare.cpp</a>.</p>

</div>
</div>

### optimizeURem() {#abfea0186c56640ad5d10657fe279471c}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool CodeGenPrepare::optimizeURem (<a href="/web-llvm/docs/api/classes/llvm/instruction">Instruction</a> * Rem)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 474 of file <a href="/web-llvm/docs/api/files/lib/lib/codegen/codegenprepare-cpp">CodeGenPrepare.cpp</a>.</p>

</div>
</div>

### performAddressTypePromotion() {#a1ef6f0046c6311f5f7f2e376f1b4c4f0}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool CodeGenPrepare::performAddressTypePromotion (<a href="/web-llvm/docs/api/classes/llvm/instruction">Instruction</a> *&amp; Inst, bool AllowPromotionWithoutCommonHeader, bool HasPromoted, <a href="/web-llvm/docs/api/classes/anonymous-codegenprepare-cpp-/typepromotiontransaction">TypePromotionTransaction</a> &amp; TPT, <a href="/web-llvm/docs/api/classes/llvm/smallvectorimpl">SmallVectorImpl</a>&lt; <a href="/web-llvm/docs/api/classes/llvm/instruction">Instruction</a> * &gt; &amp; SpeculativelyMovedExts)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 463 of file <a href="/web-llvm/docs/api/files/lib/lib/codegen/codegenprepare-cpp">CodeGenPrepare.cpp</a>.</p>

</div>
</div>

### placeDbgValues() {#aa94082d9cc8875835efa79034bfaf7a7}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool CodeGenPrepare::placeDbgValues (<a href="/web-llvm/docs/api/classes/llvm/function">Function</a> &amp; F)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 450 of file <a href="/web-llvm/docs/api/files/lib/lib/codegen/codegenprepare-cpp">CodeGenPrepare.cpp</a>.</p>

</div>
</div>

### placePseudoProbes() {#aa678397f87a02f641d55b093ee4b494b}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool CodeGenPrepare::placePseudoProbes (<a href="/web-llvm/docs/api/classes/llvm/function">Function</a> &amp; F)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 451 of file <a href="/web-llvm/docs/api/files/lib/lib/codegen/codegenprepare-cpp">CodeGenPrepare.cpp</a>.</p>

</div>
</div>

### removeAllAssertingVHReferences() {#a58c195830f33ef6f11aee9e08c3cfb2f}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void CodeGenPrepare::removeAllAssertingVHReferences (<a href="/web-llvm/docs/api/classes/llvm/value">Value</a> * V)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>An instruction is about to be deleted, so remove all references to it in our GEP-tracking data strcutures.</p>

<p>Definition at line 418 of file <a href="/web-llvm/docs/api/files/lib/lib/codegen/codegenprepare-cpp">CodeGenPrepare.cpp</a>.</p>

</div>
</div>

### replaceMathCmpWithIntrinsic() {#aedea0e9c1be04102aad0dbfa2560488e}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool CodeGenPrepare::replaceMathCmpWithIntrinsic (<a href="/web-llvm/docs/api/classes/llvm/binaryoperator">BinaryOperator</a> * BO, <a href="/web-llvm/docs/api/classes/llvm/value">Value</a> * Arg0, <a href="/web-llvm/docs/api/classes/llvm/value">Value</a> * Arg1, <a href="/web-llvm/docs/api/classes/llvm/cmpinst">CmpInst</a> * Cmp, <a href="/web-llvm/docs/api/namespaces/llvm/intrinsic/#a80add6b3b1cdaec560907995127adc16">Intrinsic::ID</a> IID)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 471 of file <a href="/web-llvm/docs/api/files/lib/lib/codegen/codegenprepare-cpp">CodeGenPrepare.cpp</a>.</p>

</div>
</div>

### resetIteratorIfInvalidatedWhileCalling() {#aebe65440aaacc621de5f01476c4cdbf8}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<div class="doxyMemberTemplate">template &lt;typename F&gt;</div>
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void anonymous{CodeGenPrepare.cpp}::CodeGenPrepare::resetIteratorIfInvalidatedWhileCalling (<a href="/web-llvm/docs/api/classes/llvm/basicblock">BasicBlock</a> * BB, <a href="/web-llvm/docs/api/files/lib/lib/support/md5-cpp/#a96d73bbd7af15cb1fc38c3f4a3bd82e9">F</a> f)</td>
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



<p>Definition at line 394 of file <a href="/web-llvm/docs/api/files/lib/lib/codegen/codegenprepare-cpp">CodeGenPrepare.cpp</a>.</p>

</div>
</div>

### simplifyOffsetableRelocate() {#a895cf8e0468cfd0f5d7a65d127ab2657}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool CodeGenPrepare::simplifyOffsetableRelocate (<a href="/web-llvm/docs/api/classes/llvm/gcstatepointinst">GCStatepointInst</a> &amp; I)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 468 of file <a href="/web-llvm/docs/api/files/lib/lib/codegen/codegenprepare-cpp">CodeGenPrepare.cpp</a>.</p>

</div>
</div>

### splitBranchCondition() {#a012eb45f151fde970456d622d79becef}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool CodeGenPrepare::splitBranchCondition (<a href="/web-llvm/docs/api/classes/llvm/function">Function</a> &amp; F, <a href="/web-llvm/docs/api/namespaces/anonymous-codegenprepare-cpp-/#af5758ce8e1ea07d0c154e97556db4379">ModifyDT</a> &amp; ModifiedDT)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Some targets prefer to split a conditional branch like:</p>


<div class="doxyProgramListing">

<div class="doxyCodeLine"><span class="doxyNoLineNumber">&nbsp;</span><span class="doxyLineContent"><span class="doxyHighlight">%0 = icmp ne i32 %a, 0</span></span></div>
<div class="doxyCodeLine"><span class="doxyNoLineNumber">&nbsp;</span><span class="doxyLineContent"><span class="doxyHighlight">%1 = icmp ne i32 %<a href="/web-llvm/docs/api/namespaces/llvm/m68k/#ab3a288f2953d8eca3e363959fc2cf38ea92eb5ffee6ae2fec3ad71c777531578f">b</a>, 0</span></span></div>
<div class="doxyCodeLine"><span class="doxyNoLineNumber">&nbsp;</span><span class="doxyLineContent"><span class="doxyHighlight">%or.cond = or i1 %0, %1</span></span></div>
<div class="doxyCodeLine"><span class="doxyNoLineNumber">&nbsp;</span><span class="doxyLineContent"><span class="doxyHighlight">br i1 %or.cond, label %TrueBB, label %FalseBB</span></span></div>

</div>


<p>into multiple branch instructions like:</p>


<div class="doxyProgramListing">

<div class="doxyCodeLine"><span class="doxyNoLineNumber">&nbsp;</span><span class="doxyLineContent"><span class="doxyHighlight">bb1:</span></span></div>
<div class="doxyCodeLine"><span class="doxyNoLineNumber">&nbsp;</span><span class="doxyLineContent"><span class="doxyHighlight">  %0 = icmp ne i32 %a, 0</span></span></div>
<div class="doxyCodeLine"><span class="doxyNoLineNumber">&nbsp;</span><span class="doxyLineContent"><span class="doxyHighlight">  br i1 %0, label %TrueBB, label %bb2</span></span></div>
<div class="doxyCodeLine"><span class="doxyNoLineNumber">&nbsp;</span><span class="doxyLineContent"><span class="doxyHighlight">bb2:</span></span></div>
<div class="doxyCodeLine"><span class="doxyNoLineNumber">&nbsp;</span><span class="doxyLineContent"><span class="doxyHighlight">  %1 = icmp ne i32 %<a href="/web-llvm/docs/api/namespaces/llvm/m68k/#ab3a288f2953d8eca3e363959fc2cf38ea92eb5ffee6ae2fec3ad71c777531578f">b</a>, 0</span></span></div>
<div class="doxyCodeLine"><span class="doxyNoLineNumber">&nbsp;</span><span class="doxyLineContent"><span class="doxyHighlight">  br i1 %1, label %TrueBB, label %FalseBB</span></span></div>

</div>


<p>This usually allows instruction selection to do even further optimizations and combine the compare with the branch instruction. Currently this is applied for targets which have "cheap" jump instructions.</p>


<p>FIXME: Remove the (equivalent?) implementation in <a href="/web-llvm/docs/api/classes/llvm/selectiondag">SelectionDAG</a>.</p>


<p>Definition at line 467 of file <a href="/web-llvm/docs/api/files/lib/lib/codegen/codegenprepare-cpp">CodeGenPrepare.cpp</a>.</p>

</div>
</div>

### splitLargeGEPOffsets() {#a5980d7c3f3f9b39d852be2cee498acbc}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool CodeGenPrepare::splitLargeGEPOffsets ()</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 459 of file <a href="/web-llvm/docs/api/files/lib/lib/codegen/codegenprepare-cpp">CodeGenPrepare.cpp</a>.</p>

</div>
</div>

### tryToPromoteExts() {#a9a02e3d0ad1ea144575f64ba9a95634e}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool CodeGenPrepare::tryToPromoteExts (<a href="/web-llvm/docs/api/classes/anonymous-codegenprepare-cpp-/typepromotiontransaction">TypePromotionTransaction</a> &amp; TPT, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/smallvectorimpl">SmallVectorImpl</a>&lt; <a href="/web-llvm/docs/api/classes/llvm/instruction">Instruction</a> * &gt; &amp; Exts, <a href="/web-llvm/docs/api/classes/llvm/smallvectorimpl">SmallVectorImpl</a>&lt; <a href="/web-llvm/docs/api/classes/llvm/instruction">Instruction</a> * &gt; &amp; ProfitablyMovedExts, unsigned CreatedInstsCost=0)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Try to speculatively promote extensions in <span class="doxyComputerOutput">Exts</span> and continue promoting through newly promoted operands recursively as far as doing so is profitable.</p>


<p>Save extensions profitably moved up, in <span class="doxyComputerOutput">ProfitablyMovedExts</span>. When some promotion happened, <span class="doxyComputerOutput">TPT</span> contains the proper state to revert them.</p>


<dl class="doxySectionUser">
<dt>Returns</dt>
<dd><p>true if some promotion happened, false otherwise.</p></dd>
</dl>


<p>Definition at line 454 of file <a href="/web-llvm/docs/api/files/lib/lib/codegen/codegenprepare-cpp">CodeGenPrepare.cpp</a>.</p>

</div>
</div>

### tryToSinkFreeOperands() {#aa4f770d38985ae435db295e10d4ecbe7}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool CodeGenPrepare::tryToSinkFreeOperands (<a href="/web-llvm/docs/api/classes/llvm/instruction">Instruction</a> * I)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 470 of file <a href="/web-llvm/docs/api/files/lib/lib/codegen/codegenprepare-cpp">CodeGenPrepare.cpp</a>.</p>

</div>
</div>

### verifyBFIUpdates() {#ada74b9df95b7bd64a3b6479cc06ba590}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void LLVM_ATTRIBUTE_UNUSED CodeGenPrepare::verifyBFIUpdates (<a href="/web-llvm/docs/api/classes/llvm/function">Function</a> &amp; F)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 477 of file <a href="/web-llvm/docs/api/files/lib/lib/codegen/codegenprepare-cpp">CodeGenPrepare.cpp</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Public Member Attributes

### FreshBBs {#a3976bdb67704d416ca52fd8a1ead845a}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">SmallSet&lt;BasicBlock *, 32&gt; anonymous{CodeGenPrepare.cpp}::CodeGenPrepare::FreshBBs</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>FreshBBs is like worklist, it collected the updated BBs which need to be optimized again.</p>


<p>Note: Consider building time in this pass, when a BB updated, we need to insert such BB into FreshBBs for huge function.</p>


<p>Definition at line 379 of file <a href="/web-llvm/docs/api/files/lib/lib/codegen/codegenprepare-cpp">CodeGenPrepare.cpp</a>.</p>


<p>Referenced by <a href="#a603cbf2855141608521f6709cdfb126f">releaseMemory</a>.</p>

</div>
</div>

### IsHugeFunc {#aaf22dc443fa1ce5fcf175fcf27dd50fa}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool anonymous{CodeGenPrepare.cpp}::CodeGenPrepare::IsHugeFunc = false</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>If encounter huge function, we need to limit the build time.</p>

<p>Definition at line 373 of file <a href="/web-llvm/docs/api/files/lib/lib/codegen/codegenprepare-cpp">CodeGenPrepare.cpp</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Private Member Attributes

### BBSectionsProfileReader {#aced9c3ba002870c8135a88069ac78804}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">const BasicBlockSectionsProfileReader* anonymous{CodeGenPrepare.cpp}::CodeGenPrepare::BBSectionsProfileReader = nullptr</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 312 of file <a href="/web-llvm/docs/api/files/lib/lib/codegen/codegenprepare-cpp">CodeGenPrepare.cpp</a>.</p>

</div>
</div>

### BFI {#aba2fab722c3b0b47cbc10159ac698921}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">std::unique_ptr&lt;BlockFrequencyInfo&gt; anonymous{CodeGenPrepare.cpp}::CodeGenPrepare::BFI</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 315 of file <a href="/web-llvm/docs/api/files/lib/lib/codegen/codegenprepare-cpp">CodeGenPrepare.cpp</a>.</p>

</div>
</div>

### BPI {#ac862d0e4372ae2d548f8e50e5bdd1342}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">std::unique_ptr&lt;BranchProbabilityInfo&gt; anonymous{CodeGenPrepare.cpp}::CodeGenPrepare::BPI</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 316 of file <a href="/web-llvm/docs/api/files/lib/lib/codegen/codegenprepare-cpp">CodeGenPrepare.cpp</a>.</p>

</div>
</div>

### CurInstIterator {#a0a61253b305c28fc0fc02ac0dfeba7ab}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">BasicBlock::iterator anonymous{CodeGenPrepare.cpp}::CodeGenPrepare::CurInstIterator</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>As we scan instructions optimizing them, this is the next instruction to optimize.</p>


<p>Transforms that can invalidate this should update it.</p>


<p>Definition at line 321 of file <a href="/web-llvm/docs/api/files/lib/lib/codegen/codegenprepare-cpp">CodeGenPrepare.cpp</a>.</p>

</div>
</div>

### DL {#a3df9aef490f35a91696c218f58b6c017}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">const DataLayout* anonymous{CodeGenPrepare.cpp}::CodeGenPrepare::DL = nullptr</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p><a href="/web-llvm/docs/api/classes/llvm/datalayout">DataLayout</a> for the <a href="/web-llvm/docs/api/classes/llvm/function">Function</a> being processed.</p>

<p>Definition at line 363 of file <a href="/web-llvm/docs/api/files/lib/lib/codegen/codegenprepare-cpp">CodeGenPrepare.cpp</a>.</p>

</div>
</div>

### DT {#aae09e473eac423426f55bb40c6624e62}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">std::unique_ptr&lt;DominatorTree&gt; anonymous{CodeGenPrepare.cpp}::CodeGenPrepare::DT</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Building the dominator tree can be expensive, so we only build it lazily and update it when required.</p>

<p>Definition at line 367 of file <a href="/web-llvm/docs/api/files/lib/lib/codegen/codegenprepare-cpp">CodeGenPrepare.cpp</a>.</p>

</div>
</div>

### InsertedInsts {#a31a6cd022d80e3aae7963285905fb9eb}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">SetOfInstrs anonymous{CodeGenPrepare.cpp}::CodeGenPrepare::InsertedInsts</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Keeps track of all instructions inserted for the current function.</p>

<p>Definition at line 331 of file <a href="/web-llvm/docs/api/files/lib/lib/codegen/codegenprepare-cpp">CodeGenPrepare.cpp</a>.</p>

</div>
</div>

### LargeOffsetGEPID {#ab69d1616b0fc0edf604ca57895b7d048}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">DenseMap&lt;AssertingVH&lt;GetElementPtrInst&gt;, int&gt; anonymous{CodeGenPrepare.cpp}::CodeGenPrepare::LargeOffsetGEPID</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Map serial numbers to Large offset GEPs.</p>

<p>Definition at line 354 of file <a href="/web-llvm/docs/api/files/lib/lib/codegen/codegenprepare-cpp">CodeGenPrepare.cpp</a>.</p>

</div>
</div>

### LargeOffsetGEPMap {#a54b9e60f911bbd107957ec0aabed205a}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">MapVector&lt;AssertingVH&lt;Value&gt;, SmallVector&lt;std::pair&lt;AssertingVH&lt;GetElementPtrInst&gt;, int64_t&gt;, 32&gt; &gt; anonymous{CodeGenPrepare.cpp}::CodeGenPrepare::LargeOffsetGEPMap</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Keep track of GEPs accessing the same data structures such as structs or arrays that are candidates to be split later because of their large size.</p>

<p>Definition at line 348 of file <a href="/web-llvm/docs/api/files/lib/lib/codegen/codegenprepare-cpp">CodeGenPrepare.cpp</a>.</p>

</div>
</div>

### LI {#a85fed8ffc853b7f46a978e17fe2fe4c4}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">LoopInfo* anonymous{CodeGenPrepare.cpp}::CodeGenPrepare::LI = nullptr</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 314 of file <a href="/web-llvm/docs/api/files/lib/lib/codegen/codegenprepare-cpp">CodeGenPrepare.cpp</a>.</p>

</div>
</div>

### NewGEPBases {#aeb66fcc600b9528a52cdcf071b47030b}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">SmallSet&lt;AssertingVH&lt;Value&gt;, 2&gt; anonymous{CodeGenPrepare.cpp}::CodeGenPrepare::NewGEPBases</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Keep track of new GEP base after splitting the GEPs having large offset.</p>

<p>Definition at line 351 of file <a href="/web-llvm/docs/api/files/lib/lib/codegen/codegenprepare-cpp">CodeGenPrepare.cpp</a>.</p>

</div>
</div>

### OptSize {#a2fc44d6d2a92b3d69d6095590234057e}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool anonymous{CodeGenPrepare.cpp}::CodeGenPrepare::OptSize</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>True if the function has the OptSize attribute.</p>

<p>Definition at line 360 of file <a href="/web-llvm/docs/api/files/lib/lib/codegen/codegenprepare-cpp">CodeGenPrepare.cpp</a>.</p>

</div>
</div>

### PromotedInsts {#a2c914af3632b09022dca056b80f9285a}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">InstrToOrigTy anonymous{CodeGenPrepare.cpp}::CodeGenPrepare::PromotedInsts</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Keeps track of the type of the related instruction before their promotion for the current function.</p>

<p>Definition at line 335 of file <a href="/web-llvm/docs/api/files/lib/lib/codegen/codegenprepare-cpp">CodeGenPrepare.cpp</a>.</p>

</div>
</div>

### PSI {#a6562baca501311590056bce906fbe710}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">ProfileSummaryInfo* anonymous{CodeGenPrepare.cpp}::CodeGenPrepare::PSI = nullptr</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 317 of file <a href="/web-llvm/docs/api/files/lib/lib/codegen/codegenprepare-cpp">CodeGenPrepare.cpp</a>.</p>

</div>
</div>

### RemovedInsts {#abbdd32f1a7a9e787e8d310f1bcbefe42}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">SetOfInstrs anonymous{CodeGenPrepare.cpp}::CodeGenPrepare::RemovedInsts</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Keep track of instructions removed during promotion.</p>

<p>Definition at line 338 of file <a href="/web-llvm/docs/api/files/lib/lib/codegen/codegenprepare-cpp">CodeGenPrepare.cpp</a>.</p>

</div>
</div>

### SeenChainsForSExt {#a77dbd9b78cdf8a35774f3fa2a31c2c3b}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">DenseMap&lt;Value *, Instruction *&gt; anonymous{CodeGenPrepare.cpp}::CodeGenPrepare::SeenChainsForSExt</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Keep track of sext chains based on their initial value.</p>

<p>Definition at line 341 of file <a href="/web-llvm/docs/api/files/lib/lib/codegen/codegenprepare-cpp">CodeGenPrepare.cpp</a>.</p>

</div>
</div>

### SubtargetInfo {#ad2c4a5860836d9d24581cefe71fe1fa7}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">const TargetSubtargetInfo* anonymous{CodeGenPrepare.cpp}::CodeGenPrepare::SubtargetInfo = nullptr</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 308 of file <a href="/web-llvm/docs/api/files/lib/lib/codegen/codegenprepare-cpp">CodeGenPrepare.cpp</a>.</p>

</div>
</div>

### SunkAddrs {#a3bb34eab6528acd9f39f7f4d60170140}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">ValueMap&lt;Value *, WeakTrackingVH&gt; anonymous{CodeGenPrepare.cpp}::CodeGenPrepare::SunkAddrs</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Keeps track of non-local addresses that have been sunk into a block.</p>


<p>This allows us to avoid inserting duplicate code for blocks with multiple load/stores of the same address. The usage of <a href="/web-llvm/docs/api/classes/llvm/weaktrackingvh">WeakTrackingVH</a> enables SunkAddrs to be treated as a cache whose entries can be invalidated if a sunken address computation has been erased.</p>


<p>Definition at line 328 of file <a href="/web-llvm/docs/api/files/lib/lib/codegen/codegenprepare-cpp">CodeGenPrepare.cpp</a>.</p>

</div>
</div>

### TLI {#a36a9e61fcf4b40e4e9eb953cd5006007}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">const TargetLowering* anonymous{CodeGenPrepare.cpp}::CodeGenPrepare::TLI = nullptr</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 309 of file <a href="/web-llvm/docs/api/files/lib/lib/codegen/codegenprepare-cpp">CodeGenPrepare.cpp</a>.</p>

</div>
</div>

### TLInfo {#a434e1e371c4318830b31e68f705ad7b6}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">const TargetLibraryInfo* anonymous{CodeGenPrepare.cpp}::CodeGenPrepare::TLInfo = nullptr</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 313 of file <a href="/web-llvm/docs/api/files/lib/lib/codegen/codegenprepare-cpp">CodeGenPrepare.cpp</a>.</p>

</div>
</div>

### TM {#ac7ab22ca458c148de65fb8b943deea58}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">const TargetMachine* anonymous{CodeGenPrepare.cpp}::CodeGenPrepare::TM = nullptr</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 307 of file <a href="/web-llvm/docs/api/files/lib/lib/codegen/codegenprepare-cpp">CodeGenPrepare.cpp</a>.</p>

</div>
</div>

### TRI {#af4dc1e36f37c37682621e513ae5aab71}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">const TargetRegisterInfo* anonymous{CodeGenPrepare.cpp}::CodeGenPrepare::TRI = nullptr</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 310 of file <a href="/web-llvm/docs/api/files/lib/lib/codegen/codegenprepare-cpp">CodeGenPrepare.cpp</a>.</p>

</div>
</div>

### TTI {#aa5ca8813f077b3f8c1373ec6a507f1fc}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">const TargetTransformInfo* anonymous{CodeGenPrepare.cpp}::CodeGenPrepare::TTI = nullptr</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 311 of file <a href="/web-llvm/docs/api/files/lib/lib/codegen/codegenprepare-cpp">CodeGenPrepare.cpp</a>.</p>

</div>
</div>

### ValToSExtendedUses {#addbd90927b3cef37941b6959884c9706}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">ValueToSExts anonymous{CodeGenPrepare.cpp}::CodeGenPrepare::ValToSExtendedUses</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Keep track of SExt promoted.</p>

<p>Definition at line 357 of file <a href="/web-llvm/docs/api/files/lib/lib/codegen/codegenprepare-cpp">CodeGenPrepare.cpp</a>.</p>

</div>
</div>

</div>

<hr/>

The documentation for this class was generated from the following file:

<ul>
<li><a href="/web-llvm/docs/api/files/lib/lib/codegen/codegenprepare-cpp">CodeGenPrepare.cpp</a></li>
</ul>

<hr/>

<p class="doxyGeneratedBy">Generated via <a href="https://github.com/xpack/doxygen2docusaurus">doxygen2docusaurus</a> by <a href="https://www.doxygen.nl">Doxygen</a> 1.15.0.</p>

</div>
