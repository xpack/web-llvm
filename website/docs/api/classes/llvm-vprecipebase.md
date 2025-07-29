---

# DO NOT EDIT!
# Automatically generated via doxygen2docusaurus by Doxygen.

slug: /api/classes/llvm/vprecipebase
custom_edit_url: null
toc_max_heading_level: 4
keywords:
  - doxygen
  - reference
  - class

---

<div class="doxyPage">

# `VPRecipeBase` Class

<p><a href="/web-llvm/docs/api/classes/llvm/vprecipebase">VPRecipeBase</a> is a base class modeling a sequence of one or more output IR instructions. <a href="#details">More...</a></p>

## Declaration

<div class="doxyDeclaration">
class llvm::VPRecipeBase { ... }
</div>

## Included Headers

<div class="doxyIncludesList">#include "<a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/vectorize/vplan-h">Transforms/Vectorize/VPlan.h</a>"
</div>

## Base classes

<table class="doxyMembersIndex">

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">class</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/ilist-node-with-parent">ilist_node_with_parent&lt;NodeTy, ParentTy, Options&gt;</a></td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>An ilist node that can access its parent list. <a href="/web-llvm/docs/api/classes/llvm/ilist-node-with-parent/#details">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">class</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/vpdef">VPDef</a></td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>This class augments a recipe with a set of VPValues defined by the recipe. <a href="/web-llvm/docs/api/classes/llvm/vpdef/#details">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">class</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/vpuser">VPUser</a></td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>This class augments <a href="/web-llvm/docs/api/classes/llvm/vpvalue">VPValue</a> with operands which provide the inverse def-use edges from <a href="/web-llvm/docs/api/classes/llvm/vpvalue">VPValue</a>'s users to their defs. <a href="/web-llvm/docs/api/classes/llvm/vpuser/#details">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

</table>

## Derived Classes

<table class="doxyMembersIndex">

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">class</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/vpbranchonmaskrecipe">VPBranchOnMaskRecipe</a></td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>A recipe for generating conditional branches on the bits of a mask. <a href="/web-llvm/docs/api/classes/llvm/vpbranchonmaskrecipe/#details">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">class</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/vphistogramrecipe">VPHistogramRecipe</a></td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>A recipe representing a sequence of load -&gt; update -&gt; store as part of a histogram operation. <a href="/web-llvm/docs/api/classes/llvm/vphistogramrecipe/#details">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">class</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/vpirinstruction">VPIRInstruction</a></td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>A recipe to wrap on original IR instruction not to be modified during execution, execept for PHIs. <a href="/web-llvm/docs/api/classes/llvm/vpirinstruction/#details">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">class</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/vpinterleaverecipe">VPInterleaveRecipe</a></td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p><a href="/web-llvm/docs/api/classes/llvm/vpinterleaverecipe">VPInterleaveRecipe</a> is a recipe for transforming an interleave group of load or stores into one wide load/store and shuffles. <a href="/web-llvm/docs/api/classes/llvm/vpinterleaverecipe/#details">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">class</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/vpsingledefrecipe">VPSingleDefRecipe</a></td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>VPSingleDef is a base class for recipes for modeling a sequence of one or more output IR that define a single result <a href="/web-llvm/docs/api/classes/llvm/vpvalue">VPValue</a>. <a href="/web-llvm/docs/api/classes/llvm/vpsingledefrecipe/#details">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">class</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/vpwidenmemoryrecipe">VPWidenMemoryRecipe</a></td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>A common base class for widening memory operations. <a href="/web-llvm/docs/api/classes/llvm/vpwidenmemoryrecipe/#details">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

</table>

## Friends Index

<table class="doxyMembersIndex">

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">class</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ac053f64c43882b2047a6e3327c37cea7">VPBlockUtils</a></td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#aaf68139c582775191f8535403942e5f2">VPRecipeBase</a> (const unsigned char SC, ArrayRef&lt; VPValue * &gt; Operands, DebugLoc DL={})</td>
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
<td class="doxyMemberIndexTemplate" colspan="2"><div>template &lt;typename IterT&gt;</div></td>
</tr>
<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemNoTypeNameTemplate" colspan="2" align="left" valign="top"><a href="#ae03424ec05766df1594f3cf201886dd3">VPRecipeBase</a> (const unsigned char SC, iterator_range&lt; IterT &gt; Operands, DebugLoc DL={})</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a692fa28b621540ea6603a8505bc881fa">~VPRecipeBase</a> ()=default</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/vprecipebase">VPRecipeBase</a> *</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ab24e14192fc0bd2cecdca8c3bddf4916">clone</a> ()=0</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Clone the current recipe. <a href="#ab24e14192fc0bd2cecdca8c3bddf4916">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/vpbasicblock">VPBasicBlock</a> *</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a6c88376daf23b16ad26b7ac6c224d21e">getParent</a> ()</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/vpbasicblock">VPBasicBlock</a> *</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ac190cfce960895f8a9a1f963da0614a9">getParent</a> () const</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a81954e9fa447937fb744fda95cf8f946">execute</a> (VPTransformState &amp;State)=0</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>The method which generates the output IR instructions that correspond to this VPRecipe, thereby "executing" the <a href="/web-llvm/docs/api/classes/llvm/vplan">VPlan</a>. <a href="#a81954e9fa447937fb744fda95cf8f946">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/instructioncost">InstructionCost</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ac84a2bc6b484c5d3a03e80ce40f0a14c">cost</a> (ElementCount VF, VPCostContext &amp;Ctx)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Return the cost of this recipe, taking into account if the cost computation should be skipped and the ForceTargetInstructionCost flag. <a href="#ac84a2bc6b484c5d3a03e80ce40f0a14c">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">void</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a8859e5e8cad5653b278964f47414fd84">insertBefore</a> (VPRecipeBase *InsertPos)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Insert an unlinked recipe into a basic block immediately before the specified recipe. <a href="#a8859e5e8cad5653b278964f47414fd84">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">void</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a15bed4c9d22574f9ac4c01f92c6f37b6">insertBefore</a> (VPBasicBlock &amp;BB, iplist&lt; VPRecipeBase &gt;::iterator IP)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Insert an unlinked recipe into <span class="doxyComputerOutput">BB</span> immediately before the insertion point <span class="doxyComputerOutput">IP</span>;. <a href="#a15bed4c9d22574f9ac4c01f92c6f37b6">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">void</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a8c02e0ea8aec7fa58b24b6d22f0e3e8e">insertAfter</a> (VPRecipeBase *InsertPos)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Insert an unlinked Recipe into a basic block immediately after the specified Recipe. <a href="#a8c02e0ea8aec7fa58b24b6d22f0e3e8e">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">void</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#af48299a4811bd1572ef5cdf597930edf">moveAfter</a> (VPRecipeBase *MovePos)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Unlink this recipe from its current <a href="/web-llvm/docs/api/classes/llvm/vpbasicblock">VPBasicBlock</a> and insert it into the <a href="/web-llvm/docs/api/classes/llvm/vpbasicblock">VPBasicBlock</a> that MovePos lives in, right after MovePos. <a href="#af48299a4811bd1572ef5cdf597930edf">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">void</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a83c9341e2d36f67d5cad25ba91e862e1">moveBefore</a> (VPBasicBlock &amp;BB, iplist&lt; VPRecipeBase &gt;::iterator I)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Unlink this recipe and insert into BB before I. <a href="#a83c9341e2d36f67d5cad25ba91e862e1">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">void</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ae4b7881e0e91ff340908b161a10e69b6">removeFromParent</a> ()</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>This method unlinks 'this' from the containing basic block, but does not delete it. <a href="#ae4b7881e0e91ff340908b161a10e69b6">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/iplist">iplist</a>&lt; <a href="/web-llvm/docs/api/classes/llvm/vprecipebase">VPRecipeBase</a> &gt;<a href="/web-llvm/docs/api/classes/llvm/iplist">::iterator</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#aac9dfb61b37082dca00de284bb3309e8">eraseFromParent</a> ()</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>This method unlinks 'this' from the containing basic block and deletes it. <a href="#aac9dfb61b37082dca00de284bb3309e8">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">bool</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a2408a88276528d80adefefa00995705a">mayHaveSideEffects</a> () const</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Returns true if the recipe may have side-effects. <a href="#a2408a88276528d80adefefa00995705a">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">bool</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#af1fd3c4a51ec7fed4584ced33acc368d">isPhi</a> () const</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Returns true for PHI-like recipes. <a href="#af1fd3c4a51ec7fed4584ced33acc368d">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">bool</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a00bc7da040562d501bcc0e0635a2b53c">mayReadFromMemory</a> () const</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Returns true if the recipe may read from memory. <a href="#a00bc7da040562d501bcc0e0635a2b53c">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">bool</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a5fcebe7c77877e7f65c88e61c0fe1149">mayWriteToMemory</a> () const</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Returns true if the recipe may write to memory. <a href="#a5fcebe7c77877e7f65c88e61c0fe1149">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">bool</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a15ab200cb0259f0c13b4e068acfd7fc6">mayReadOrWriteMemory</a> () const</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Returns true if the recipe may read from or write to memory. <a href="#a15ab200cb0259f0c13b4e068acfd7fc6">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/debugloc">DebugLoc</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a733c4c530159a8b86223376c0696430e">getDebugLoc</a> () const</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Returns the debug location of the recipe. <a href="#a733c4c530159a8b86223376c0696430e">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

</table>

## Protected Member Functions Index

<table class="doxyMembersIndex">

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/instructioncost">InstructionCost</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a677e548bbdd91cb3de30c3de2b40049a">computeCost</a> (ElementCount VF, VPCostContext &amp;Ctx) const</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Compute the cost of this recipe either using a recipe's specialized implementation or using the legacy cost model and the underlying instructions. <a href="#a677e548bbdd91cb3de30c3de2b40049a">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

</table>

## Private Member Attributes Index

<table class="doxyMembersIndex">

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">friend</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a352a9464a359d84e0221affad65246dc">VPBasicBlock</a></td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/vpbasicblock">VPBasicBlock</a> *</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a80c68de8f5a578929c5a42a7ae452b1d">Parent</a> = nullptr</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Each VPRecipe belongs to a single <a href="/web-llvm/docs/api/classes/llvm/vpbasicblock">VPBasicBlock</a>. <a href="#a80c68de8f5a578929c5a42a7ae452b1d">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/debugloc">DebugLoc</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a2a12270e9d725d90bdcd522db8a5c6ac">DL</a></td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>The debug location for the recipe. <a href="#a2a12270e9d725d90bdcd522db8a5c6ac">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

</table>

## Public Static Functions Index

<table class="doxyMembersIndex">

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">static bool</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a94599a3a939b7cf678cc58c8827c4d21">classof</a> (const VPDef *D)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Method to support type inquiry through isa, cast, and dyn_cast. <a href="#a94599a3a939b7cf678cc58c8827c4d21">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">static bool</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#adc8662faed8d6e19081308d8f3d418a2">classof</a> (const VPUser *U)</td>
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

<p><a href="/web-llvm/docs/api/classes/llvm/vprecipebase">VPRecipeBase</a> is a base class modeling a sequence of one or more output IR instructions.</p>


<p><a href="/web-llvm/docs/api/classes/llvm/vprecipebase">VPRecipeBase</a> owns the VPValues it defines through <a href="/web-llvm/docs/api/classes/llvm/vpdef">VPDef</a> and is responsible for deleting its defined values. Single-value recipes must inherit from VPSingleDef instead of inheriting from both <a href="/web-llvm/docs/api/classes/llvm/vprecipebase">VPRecipeBase</a> and <a href="/web-llvm/docs/api/classes/llvm/vpvalue">VPValue</a> separately.</p>


<p>Definition at line 709 of file <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/vectorize/vplan-h">VPlan.h</a>.</p>


<div class="doxySectionDef">

## Friends

### VPBlockUtils {#ac053f64c43882b2047a6e3327c37cea7}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">friend class <a href="/web-llvm/docs/api/classes/llvm/vpblockutils">VPBlockUtils</a></td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">


<p>Definition at line 713 of file <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/vectorize/vplan-h">VPlan.h</a>.</p>


<p>Reference <a href="#ac053f64c43882b2047a6e3327c37cea7">VPBlockUtils</a>.</p>


<p>Referenced by <a href="#ac053f64c43882b2047a6e3327c37cea7">VPBlockUtils</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Public Constructors

### VPRecipeBase() {#aaf68139c582775191f8535403942e5f2}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">llvm::VPRecipeBase::VPRecipeBase (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> unsigned char SC, <a href="/web-llvm/docs/api/classes/llvm/arrayref">ArrayRef</a>&lt; <a href="/web-llvm/docs/api/classes/llvm/vpvalue">VPValue</a> * &gt; Operands, <a href="/web-llvm/docs/api/classes/llvm/debugloc">DebugLoc</a> DL={})</td>
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



<p>Definition at line 722 of file <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/vectorize/vplan-h">VPlan.h</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/classes/llvm/vpwidenmemoryrecipe/#a63f38beaba4e25370544f46d3d0b26fd">llvm::VPWidenMemoryRecipe::classof</a>, <a href="#ab24e14192fc0bd2cecdca8c3bddf4916">clone</a>, <a href="#a81954e9fa447937fb744fda95cf8f946">execute</a>, <a href="#a8c02e0ea8aec7fa58b24b6d22f0e3e8e">insertAfter</a>, <a href="#a8859e5e8cad5653b278964f47414fd84">insertBefore</a>, <a href="#af48299a4811bd1572ef5cdf597930edf">moveAfter</a>, <a href="/web-llvm/docs/api/classes/llvm/vpbranchonmaskrecipe/#a471279ec446aa8abb3363cb7b26745ea">llvm::VPBranchOnMaskRecipe::VPBranchOnMaskRecipe</a>, <a href="/web-llvm/docs/api/classes/llvm/vpinterleaverecipe/#a847d088f08911b99220a45e38b97030c">llvm::VPInterleaveRecipe::VPInterleaveRecipe</a>, <a href="/web-llvm/docs/api/classes/llvm/vpirinstruction/#af7ca8755f07a6e9ebff954ae595944c3">llvm::VPIRInstruction::VPIRInstruction</a> and <a href="/web-llvm/docs/api/classes/llvm/vpwidenmemoryrecipe/#a683571dc9876623d7cffc7e6f0fd67f7">llvm::VPWidenMemoryRecipe::VPWidenMemoryRecipe</a>.</p>

</div>
</div>

### VPRecipeBase() {#ae03424ec05766df1594f3cf201886dd3}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<div class="doxyMemberTemplate">template &lt;typename IterT&gt;</div>
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">llvm::VPRecipeBase::VPRecipeBase (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> unsigned char SC, <a href="/web-llvm/docs/api/classes/llvm/iterator-range">iterator_range</a>&lt; IterT &gt; Operands, <a href="/web-llvm/docs/api/classes/llvm/debugloc">DebugLoc</a> DL={})</td>
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



<p>Definition at line 727 of file <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/vectorize/vplan-h">VPlan.h</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Public Destructor

### \~VPRecipeBase() {#a692fa28b621540ea6603a8505bc881fa}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">virtual llvm::VPRecipeBase::~VPRecipeBase ()</td>
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



<p>Definition at line 730 of file <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/vectorize/vplan-h">VPlan.h</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Public Member Functions

### clone() {#ab24e14192fc0bd2cecdca8c3bddf4916}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">virtual VPRecipeBase * llvm::VPRecipeBase::clone ()</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Clone the current recipe.</p>

<p>Definition at line 733 of file <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/vectorize/vplan-h">VPlan.h</a>.</p>


<p>Reference <a href="#aaf68139c582775191f8535403942e5f2">VPRecipeBase</a>.</p>

</div>
</div>

### cost() {#ac84a2bc6b484c5d3a03e80ce40f0a14c}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">InstructionCost VPRecipeBase::cost (<a href="/web-llvm/docs/api/classes/llvm/elementcount">ElementCount</a> VF, <a href="/web-llvm/docs/api/structs/llvm/vpcostcontext">VPCostContext</a> &amp; Ctx)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Return the cost of this recipe, taking into account if the cost computation should be skipped and the ForceTargetInstructionCost flag.</p>


<p>Also takes care of printing the cost for debugging.</p>


<p>Declaration at line 746 of file <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/vectorize/vplan-h">VPlan.h</a>, definition at line 246 of file <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/vectorize/vplanrecipes-cpp">VPlanRecipes.cpp</a>.</p>


<p>References <a href="#a677e548bbdd91cb3de30c3de2b40049a">computeCost</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a7c46c742c31be54870e2038048e6b391">llvm::dbgs</a>, <a href="/web-llvm/docs/api/classes/llvm/vpdef/#a223467b284dc610de3b6c21d0e03f111">llvm::VPDef::dump</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a22eeee01734061ac1b31ccd994c49eef">llvm::dyn_cast</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a5f6182886dc2f96c204299e92c1565d5">llvm::dyn_cast_or_null</a>, <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/vectorize/loopvectorize-cpp/#a5eae6074e6a1bb62e365ef65f3e26196">ForceTargetInstructionCost</a>, <a href="/web-llvm/docs/api/classes/llvm/instructioncost/#ae01c5ced9fe2fe50f421ae121483ef04">llvm::InstructionCost::isValid</a>, <a href="/web-llvm/docs/api/classes/llvm/elementcount/#a098a514da47d00e1176aa2e16eacfb70">llvm::ElementCount::isVector</a> and <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/support/debug-h/#a196897517069dda1bdb549e24468f7d7">LLVM_DEBUG</a>.</p>

</div>
</div>

### eraseFromParent() {#aac9dfb61b37082dca00de284bb3309e8}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">iplist&lt; VPRecipeBase &gt;::iterator VPRecipeBase::eraseFromParent ()</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>This method unlinks 'this' from the containing basic block and deletes it.</p>


<dl class="doxySectionUser">
<dt>Returns</dt>
<dd><p>an iterator pointing to the element after the erased one</p></dd>
</dl>


<p>Declaration at line 775 of file <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/vectorize/vplan-h">VPlan.h</a>, definition at line 230 of file <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/vectorize/vplanrecipes-cpp">VPlanRecipes.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/silowercontrolflow-cpp/#a4868c5d81c5ccc98c47aeab6244346a0">assert</a>, <a href="/web-llvm/docs/api/classes/llvm/iplist-impl/#a95277287fd3ae24d127c0992c7af888f">llvm::iplist_impl&lt; IntrusiveListT, TraitsT &gt;::erase</a>, <a href="/web-llvm/docs/api/classes/llvm/ilist-node-impl/#af719fc783be6589465137d997701a432">llvm::ilist_node_impl&lt; ilist_detail::compute_node_options&lt; VPRecipeBase, Options... &gt;::type &gt;::getIterator</a>, <a href="#a6c88376daf23b16ad26b7ac6c224d21e">getParent</a> and <a href="/web-llvm/docs/api/classes/llvm/vpbasicblock/#a355ec03c80ff2b96d14a01df0fa35844">llvm::VPBasicBlock::getRecipeList</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/vectorize/vplantransforms-cpp/#a5a9cb34d61fa4930ff585649d1d5b2ed">addVPLaneMaskPhiAndUpdateExitBranch</a>, <a href="/web-llvm/docs/api/structs/llvm/vplantransforms/#aa88371693bc18186386b04e8c45a30e4">llvm::VPlanTransforms::createInterleaveGroups</a>, <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/vectorize/vplantransforms-cpp/#ac967ad551e77554a15e20cac14877ac7">createReplicateRegion</a>, <a href="/web-llvm/docs/api/structs/llvm/vplantransforms/#ac2fcd61c17c94d7e9d10b24b718c812e">llvm::VPlanTransforms::handleUncountableEarlyExit</a>, <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/vectorize/loopvectorize-cpp/#a13368acf4fbb5816c3d82099b11519b1">preparePlanForMainVectorLoop</a> and <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/vectorize/vplantransforms-cpp/#aefd03ef5fc77c520e27fe794e8ec93e9">removeRedundantCanonicalIVs</a>.</p>

</div>
</div>

### execute() {#a81954e9fa447937fb744fda95cf8f946}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">virtual void llvm::VPRecipeBase::execute (<a href="/web-llvm/docs/api/structs/llvm/vptransformstate">VPTransformState</a> &amp; State)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>The method which generates the output IR instructions that correspond to this VPRecipe, thereby "executing" the <a href="/web-llvm/docs/api/classes/llvm/vplan">VPlan</a>.</p>

<p>Definition at line 741 of file <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/vectorize/vplan-h">VPlan.h</a>.</p>


<p>References <a href="/web-llvm/docs/api/files/lib/lib/support/md5-cpp/#ac0eafdc9ee161b71e7af98af736952fd">I</a> and <a href="#aaf68139c582775191f8535403942e5f2">VPRecipeBase</a>.</p>

</div>
</div>

### getDebugLoc() {#a733c4c530159a8b86223376c0696430e}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">DebugLoc llvm::VPRecipeBase::getDebugLoc ()</td>
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

<p>Returns the debug location of the recipe.</p>

<p>Definition at line 805 of file <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/vectorize/vplan-h">VPlan.h</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/vectorize/loopvectorize-cpp/#a20c2e870e2c105fbf0945df09a9a5c4d">addResumePhiRecipeForInduction</a>, <a href="/web-llvm/docs/api/classes/llvm/vpactivelanemaskphirecipe/#a0f37ded87f1369ecdfb1a2584e12e1a4">llvm::VPActiveLaneMaskPHIRecipe::clone</a>, <a href="/web-llvm/docs/api/classes/llvm/vpcanonicalivphirecipe/#a79f07fcd4bfc94aa84346e34ad963f4e">llvm::VPCanonicalIVPHIRecipe::clone</a>, <a href="/web-llvm/docs/api/classes/llvm/vphistogramrecipe/#a4c02a215b23361553e82137c023b5556">llvm::VPHistogramRecipe::clone</a>, <a href="/web-llvm/docs/api/classes/llvm/vpinstruction/#a4a5678fa8d469e9dd49b7e389c22d5c7">llvm::VPInstruction::clone</a>, <a href="/web-llvm/docs/api/classes/llvm/vppredinstphirecipe/#a9819963ec9063787a1face68ae70a3ed">llvm::VPPredInstPHIRecipe::clone</a>, <a href="/web-llvm/docs/api/classes/llvm/vpreductionrecipe/#ab2fe55432b8e2d065d25a3cb0e10332d">llvm::VPReductionRecipe::clone</a>, <a href="/web-llvm/docs/api/classes/llvm/vpreversevectorpointerrecipe/#a35baec6b7c56d47b6b7e002a92b0621f">llvm::VPReverseVectorPointerRecipe::clone</a>, <a href="/web-llvm/docs/api/classes/llvm/vpscalarcastrecipe/#a7b5806a160a44f78155a4efc60ff0cdb">llvm::VPScalarCastRecipe::clone</a>, <a href="/web-llvm/docs/api/classes/llvm/vpvectorpointerrecipe/#af0756969ccfa0f31807a67c9b0caf92f">llvm::VPVectorPointerRecipe::clone</a>, <a href="/web-llvm/docs/api/classes/llvm/vpwidencallrecipe/#a23c6cd965aca4e811f1d5b0e5b7eb204">llvm::VPWidenCallRecipe::clone</a>, <a href="/web-llvm/docs/api/classes/llvm/vpwidenintorfpinductionrecipe/#a53a0f613b760cdb5f775c434e3c61af3">llvm::VPWidenIntOrFpInductionRecipe::clone</a>, <a href="/web-llvm/docs/api/classes/llvm/vpwidenintrinsicrecipe/#a5eac4b4a3d8c1941d57b6c10750e72d7">llvm::VPWidenIntrinsicRecipe::clone</a>, <a href="/web-llvm/docs/api/structs/llvm/vpwidenloadrecipe/#a8cd41c107c1039e2a5550d777076db35">llvm::VPWidenLoadRecipe::clone</a>, <a href="/web-llvm/docs/api/classes/llvm/vpwidenpointerinductionrecipe/#a04e6730b77aac431d36f2cdba6a873ee">llvm::VPWidenPointerInductionRecipe::clone</a>, <a href="/web-llvm/docs/api/structs/llvm/vpwidenstorerecipe/#a97c6d18aca1810dbc2ae1efede7331ee">llvm::VPWidenStoreRecipe::clone</a>, <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/vectorize/vplantransforms-cpp/#ad0faf4b8ff1cf3306958d056dcb2fde2">createEVLRecipe</a>, <a href="/web-llvm/docs/api/classes/llvm/vpactivelanemaskphirecipe/#a0b6f2c0e5bec17e3b7fddc78e12cd5d1">llvm::VPActiveLaneMaskPHIRecipe::execute</a>, <a href="/web-llvm/docs/api/classes/llvm/vpblendrecipe/#af1d96b296e589e5d8318e526b5d2ff92">llvm::VPBlendRecipe::execute</a>, <a href="/web-llvm/docs/api/classes/llvm/vphistogramrecipe/#a19aa4af9c02f8e3571cc82c0634a25f6">llvm::VPHistogramRecipe::execute</a>, <a href="/web-llvm/docs/api/classes/llvm/vpinstruction/#af2ef259f4a63359fe35f05b8b67a911b">llvm::VPInstruction::execute</a>, <a href="/web-llvm/docs/api/classes/llvm/vppartialreductionrecipe/#a29641e0ae49abc7a19221cc882c08da6">llvm::VPPartialReductionRecipe::execute</a>, <a href="/web-llvm/docs/api/classes/llvm/vppredinstphirecipe/#a3e63796e123d5ba9cbfa023983328c37">llvm::VPPredInstPHIRecipe::execute</a>, <a href="/web-llvm/docs/api/classes/llvm/vpreductionrecipe/#ac66885d3ce04a263a03746461eac12b1">llvm::VPReductionRecipe::execute</a>, <a href="/web-llvm/docs/api/classes/llvm/vpreversevectorpointerrecipe/#ab76c8b759635aabfadc49dc1292aec2c">llvm::VPReverseVectorPointerRecipe::execute</a>, <a href="/web-llvm/docs/api/classes/llvm/vpscalarphirecipe/#ab94cd5f70a441ccaad6de9c85f583741">llvm::VPScalarPHIRecipe::execute</a>, <a href="/web-llvm/docs/api/classes/llvm/vpvectorpointerrecipe/#a82d57109b0437debe570e7dae895f3e3">llvm::VPVectorPointerRecipe::execute</a>, <a href="/web-llvm/docs/api/classes/llvm/vpwidencallrecipe/#acd93ffe413319e78d7c62688cc86eb6c">llvm::VPWidenCallRecipe::execute</a>, <a href="/web-llvm/docs/api/classes/llvm/vpwidencastrecipe/#a9b432a2a53b6ec71e9290e6f9d7582ea">llvm::VPWidenCastRecipe::execute</a>, <a href="/web-llvm/docs/api/classes/llvm/vpwidenevlrecipe/#a703a08e4f8a8f64b8be733d194070cd1">llvm::VPWidenEVLRecipe::execute</a>, <a href="/web-llvm/docs/api/classes/llvm/vpwidenintorfpinductionrecipe/#a98d8cca54a99e8b64eb406f898565323">llvm::VPWidenIntOrFpInductionRecipe::execute</a>, <a href="/web-llvm/docs/api/classes/llvm/vpwidenintrinsicrecipe/#ad6ab589f9da183bfc7227344c30aab78">llvm::VPWidenIntrinsicRecipe::execute</a>, <a href="/web-llvm/docs/api/structs/llvm/vpwidenloadevlrecipe/#a16471f19bad1ca5212ccbd52c21b8b54">llvm::VPWidenLoadEVLRecipe::execute</a>, <a href="/web-llvm/docs/api/structs/llvm/vpwidenloadrecipe/#a7c2b787dbd70d3fbd4f3699342eec925">llvm::VPWidenLoadRecipe::execute</a>, <a href="/web-llvm/docs/api/classes/llvm/vpwidenphirecipe/#afd60b87e0eaaccd0f8c122208ac1049d">llvm::VPWidenPHIRecipe::execute</a>, <a href="/web-llvm/docs/api/classes/llvm/vpwidenpointerinductionrecipe/#ac53a5d033ba641288b6e15344d880186">llvm::VPWidenPointerInductionRecipe::execute</a>, <a href="/web-llvm/docs/api/classes/llvm/vpwidenrecipe/#a1217df326ed753111e60d3eaef272ded">llvm::VPWidenRecipe::execute</a>, <a href="/web-llvm/docs/api/structs/llvm/vpwidenselectrecipe/#a8ab6a201a32f4db51d8f030c5d3ba5c6">llvm::VPWidenSelectRecipe::execute</a>, <a href="/web-llvm/docs/api/structs/llvm/vpwidenstoreevlrecipe/#a1c719942d2fa4ca51fe66c92b9ab834c">llvm::VPWidenStoreEVLRecipe::execute</a>, <a href="/web-llvm/docs/api/structs/llvm/vpwidenstorerecipe/#a0fd82e391d2d015065516e32f62870c1">llvm::VPWidenStoreRecipe::execute</a>, <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/vectorize/vplantransforms-cpp/#a6bc9d4e47e8a41e60f4bedae712f0c03">legalizeAndOptimizeInductions</a>, <a href="/web-llvm/docs/api/classes/llvm/vpinstruction/#aca839409ad4f4fb66241f6b97da6674f">llvm::VPInstruction::print</a>, <a href="/web-llvm/docs/api/structs/llvm/vplantransforms/#ad16bff9364e25351de81704fe81fd229">llvm::VPlanTransforms::tryAddExplicitVectorLength</a>, <a href="/web-llvm/docs/api/classes/llvm/vpblendrecipe/#a06a43099cff6ce62ba54dbdb91b394c2">llvm::VPBlendRecipe::VPBlendRecipe</a> and <a href="/web-llvm/docs/api/classes/llvm/vprecipewithirflags/#a76fb233396e6e9451f58b35eb03681da">llvm::VPRecipeWithIRFlags::VPRecipeWithIRFlags</a>.</p>

</div>
</div>

### getParent() {#a6c88376daf23b16ad26b7ac6c224d21e}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">VPBasicBlock * llvm::VPRecipeBase::getParent ()</td>
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




<dl class="doxySectionUser">
<dt>Returns</dt>
<dd><p>the <a href="/web-llvm/docs/api/classes/llvm/vpbasicblock">VPBasicBlock</a> which this VPRecipe belongs to.</p></dd>
</dl>


<p>Definition at line 736 of file <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/vectorize/vplan-h">VPlan.h</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/structs/llvm/vplantransforms/#ae64d6953a1334207d9e7d9cd2587ee9f">llvm::VPlanTransforms::adjustFixedOrderRecurrences</a>, <a href="/web-llvm/docs/api/classes/llvm/vpinstruction/#a824509de893dd23a9dde948791384889">llvm::VPInstruction::dump</a>, <a href="#aac9dfb61b37082dca00de284bb3309e8">eraseFromParent</a>, <a href="/web-llvm/docs/api/classes/llvm/vpderivedivrecipe/#a0f37fe11b57d14686c7ca5e7a3846174">llvm::VPDerivedIVRecipe::execute</a>, <a href="/web-llvm/docs/api/classes/llvm/vpexpandscevrecipe/#a940f7bf15c2f5bb339729b6eef075fb5">llvm::VPExpandSCEVRecipe::execute</a>, <a href="/web-llvm/docs/api/classes/llvm/vpirinstruction/#a82c7920e0c53dc071f1ac55f91a2895f">llvm::VPIRInstruction::execute</a>, <a href="/web-llvm/docs/api/classes/llvm/vpwidenpointerinductionrecipe/#ac53a5d033ba641288b6e15344d880186">llvm::VPWidenPointerInductionRecipe::execute</a>, <a href="/web-llvm/docs/api/classes/llvm/vpirinstruction/#ad326bf7574f239b4177d077e513403aa">llvm::VPIRInstruction::extractLastLaneOfOperand</a>, <a href="/web-llvm/docs/api/classes/llvm/vpslottracker/#a5a7e7a1fc5386a94fa15cc6e157d7b79">llvm::VPSlotTracker::getOrCreateName</a>, <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/vectorize/vplantransforms-cpp/#a9396319801f74828cfbd94177f38eabc">hoistPreviousBeforeFORUsers</a>, <a href="#a8c02e0ea8aec7fa58b24b6d22f0e3e8e">insertAfter</a>, <a href="#a8859e5e8cad5653b278964f47414fd84">insertBefore</a>, <a href="/web-llvm/docs/api/classes/llvm/vpwidenintorfpinductionrecipe/#aebed30683f6b89d62f06d2a10786c2e3">llvm::VPWidenIntOrFpInductionRecipe::isCanonical</a>, <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/vectorize/vplan-cpp/#a50b9bc5e656f43fdb704a6847d679973">isDefinedInsideLoopRegions</a>, <a href="/web-llvm/docs/api/classes/llvm/vpirinstruction/#ada5844051cef5e6e1fc7a5158c8047b7">llvm::VPIRInstruction::print</a>, <a href="#ae4b7881e0e91ff340908b161a10e69b6">removeFromParent</a>, <a href="/web-llvm/docs/api/classes/llvm/innerloopvectorizer/#a4690286163882c35068b1908f4d752fd">llvm::InnerLoopVectorizer::scalarizeInstruction</a>, <a href="/web-llvm/docs/api/classes/llvm/vpbuilder/#a16c5883e0be30cbd188280eec8941f6e">llvm::VPBuilder::setInsertPoint</a> and <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/vectorize/vplantransforms-cpp/#a1536feae2abb3570ac032768a53ddd00">sinkScalarOperands</a>.</p>

</div>
</div>

### getParent() {#ac190cfce960895f8a9a1f963da0614a9}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">const VPBasicBlock * llvm::VPRecipeBase::getParent ()</td>
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



<p>Definition at line 737 of file <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/vectorize/vplan-h">VPlan.h</a>.</p>

</div>
</div>

### insertAfter() {#a8c02e0ea8aec7fa58b24b6d22f0e3e8e}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void VPRecipeBase::insertAfter (<a href="/web-llvm/docs/api/classes/llvm/vprecipebase">VPRecipeBase</a> * InsertPos)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Insert an unlinked Recipe into a basic block immediately after the specified Recipe.</p>

<p>Declaration at line 757 of file <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/vectorize/vplan-h">VPlan.h</a>, definition at line 217 of file <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/vectorize/vplanrecipes-cpp">VPlanRecipes.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/silowercontrolflow-cpp/#a4868c5d81c5ccc98c47aeab6244346a0">assert</a>, <a href="/web-llvm/docs/api/classes/llvm/ilist-node-impl/#af719fc783be6589465137d997701a432">llvm::ilist_node_impl&lt; OptionsT &gt;::getIterator</a>, <a href="#a6c88376daf23b16ad26b7ac6c224d21e">getParent</a>, <a href="/web-llvm/docs/api/classes/llvm/vpbasicblock/#adfdd504b078cce3b90e7c5cf1f5164db">llvm::VPBasicBlock::insert</a> and <a href="#aaf68139c582775191f8535403942e5f2">VPRecipeBase</a>.</p>


<p>Referenced by <a href="#af48299a4811bd1572ef5cdf597930edf">moveAfter</a>.</p>

</div>
</div>

### insertBefore() {#a8859e5e8cad5653b278964f47414fd84}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void VPRecipeBase::insertBefore (<a href="/web-llvm/docs/api/classes/llvm/vprecipebase">VPRecipeBase</a> * InsertPos)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Insert an unlinked recipe into a basic block immediately before the specified recipe.</p>

<p>Declaration at line 750 of file <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/vectorize/vplan-h">VPlan.h</a>, definition at line 203 of file <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/vectorize/vplanrecipes-cpp">VPlanRecipes.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/silowercontrolflow-cpp/#a4868c5d81c5ccc98c47aeab6244346a0">assert</a>, <a href="/web-llvm/docs/api/classes/llvm/ilist-node-impl/#af719fc783be6589465137d997701a432">llvm::ilist_node_impl&lt; OptionsT &gt;::getIterator</a>, <a href="#a6c88376daf23b16ad26b7ac6c224d21e">getParent</a>, <a href="/web-llvm/docs/api/classes/llvm/vpbasicblock/#adfdd504b078cce3b90e7c5cf1f5164db">llvm::VPBasicBlock::insert</a> and <a href="#aaf68139c582775191f8535403942e5f2">VPRecipeBase</a>.</p>


<p>Referenced by <a href="#a83c9341e2d36f67d5cad25ba91e862e1">moveBefore</a>, <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/vectorize/vplantransforms-cpp/#a5f39858b5d6d72b92c138916c64c90ba">transformRecipestoEVLRecipes</a>, <a href="/web-llvm/docs/api/structs/llvm/vplantransforms/#ae61793492431f138869f097a5f31bd32">llvm::VPlanTransforms::truncateToMinimalBitwidths</a>, <a href="/web-llvm/docs/api/structs/llvm/vplantransforms/#ad16bff9364e25351de81704fe81fd229">llvm::VPlanTransforms::tryAddExplicitVectorLength</a> and <a href="/web-llvm/docs/api/structs/llvm/vplantransforms/#ad210afaefb4884ac5008dd5fbaf1cbf8">llvm::VPlanTransforms::VPInstructionsToVPRecipes</a>.</p>

</div>
</div>

### insertBefore() {#a15bed4c9d22574f9ac4c01f92c6f37b6}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void VPRecipeBase::insertBefore (<a href="/web-llvm/docs/api/classes/llvm/vpbasicblock">VPBasicBlock</a> &amp; BB, <a href="/web-llvm/docs/api/classes/llvm/iplist">iplist</a>&lt; <a href="/web-llvm/docs/api/classes/llvm/vprecipebase">VPRecipeBase</a> &gt;<a href="/web-llvm/docs/api/classes/llvm/iplist">::iterator</a> IP)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Insert an unlinked recipe into <span class="doxyComputerOutput">BB</span> immediately before the insertion point <span class="doxyComputerOutput">IP</span>;.</p>

<p>Declaration at line 753 of file <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/vectorize/vplan-h">VPlan.h</a>, definition at line 210 of file <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/vectorize/vplanrecipes-cpp">VPlanRecipes.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/silowercontrolflow-cpp/#a4868c5d81c5ccc98c47aeab6244346a0">assert</a>, <a href="/web-llvm/docs/api/classes/llvm/vpbasicblock/#a4a7f4b8433e9a788149ffd94a0a07051">llvm::VPBasicBlock::end</a>, <a href="/web-llvm/docs/api/files/lib/lib/support/md5-cpp/#ac0eafdc9ee161b71e7af98af736952fd">I</a> and <a href="/web-llvm/docs/api/classes/llvm/vpbasicblock/#adfdd504b078cce3b90e7c5cf1f5164db">llvm::VPBasicBlock::insert</a>.</p>

</div>
</div>

### isPhi() {#af1fd3c4a51ec7fed4584ced33acc368d}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool llvm::VPRecipeBase::isPhi ()</td>
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

<p>Returns true for PHI-like recipes.</p>

<p>Definition at line 789 of file <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/vectorize/vplan-h">VPlan.h</a>.</p>


<p>Reference <a href="/web-llvm/docs/api/classes/llvm/vpdef/#ad537baa7adabb231da7e1b79a1e1696b">llvm::VPDef::getVPDefID</a>.</p>

</div>
</div>

### mayHaveSideEffects() {#a2408a88276528d80adefefa00995705a}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool VPRecipeBase::mayHaveSideEffects ()</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Returns true if the recipe may have side-effects.</p>

<p>Declaration at line 786 of file <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/vectorize/vplan-h">VPlan.h</a>, definition at line 146 of file <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/vectorize/vplanrecipes-cpp">VPlanRecipes.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/silowercontrolflow-cpp/#a4868c5d81c5ccc98c47aeab6244346a0">assert</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#ac4fc845f5ed92de63cd4474f128f5fc5">llvm::cast</a>, <a href="/web-llvm/docs/api/classes/llvm/function/#a81f38aca859ffeda166f8c385f7d55a5">llvm::Function::doesNotThrow</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a5f6182886dc2f96c204299e92c1565d5">llvm::dyn_cast_or_null</a>, <a href="/web-llvm/docs/api/classes/llvm/vpdef/#ad537baa7adabb231da7e1b79a1e1696b">llvm::VPDef::getVPDefID</a>, <a href="/web-llvm/docs/api/classes/llvm/vpdef/#a76a983b694720483a3dd9fe57314e39b">llvm::VPDef::getVPSingleValue</a>, <a href="/web-llvm/docs/api/files/lib/lib/support/md5-cpp/#ac0eafdc9ee161b71e7af98af736952fd">I</a>, <a href="#a2408a88276528d80adefefa00995705a">mayHaveSideEffects</a>, <a href="#a5fcebe7c77877e7f65c88e61c0fe1149">mayWriteToMemory</a> and <a href="/web-llvm/docs/api/classes/llvm/function/#a48e10a01350fafd3df5828061787a97e">llvm::Function::willReturn</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/vectorize/vplantransforms-cpp/#a9396319801f74828cfbd94177f38eabc">hoistPreviousBeforeFORUsers</a>, <a href="#a2408a88276528d80adefefa00995705a">mayHaveSideEffects</a> and <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/vectorize/vplantransforms-cpp/#a1536feae2abb3570ac032768a53ddd00">sinkScalarOperands</a>.</p>

</div>
</div>

### mayReadFromMemory() {#a00bc7da040562d501bcc0e0635a2b53c}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool VPRecipeBase::mayReadFromMemory ()</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Returns true if the recipe may read from memory.</p>

<p>Declaration at line 794 of file <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/vectorize/vplan-h">VPlan.h</a>, definition at line 100 of file <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/vectorize/vplanrecipes-cpp">VPlanRecipes.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/silowercontrolflow-cpp/#a4868c5d81c5ccc98c47aeab6244346a0">assert</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#ac4fc845f5ed92de63cd4474f128f5fc5">llvm::cast</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a5f6182886dc2f96c204299e92c1565d5">llvm::dyn_cast_or_null</a>, <a href="/web-llvm/docs/api/classes/llvm/vpdef/#ad537baa7adabb231da7e1b79a1e1696b">llvm::VPDef::getVPDefID</a>, <a href="/web-llvm/docs/api/classes/llvm/vpdef/#a76a983b694720483a3dd9fe57314e39b">llvm::VPDef::getVPSingleValue</a> and <a href="/web-llvm/docs/api/files/lib/lib/support/md5-cpp/#ac0eafdc9ee161b71e7af98af736952fd">I</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/vectorize/vplantransforms-cpp/#a9396319801f74828cfbd94177f38eabc">hoistPreviousBeforeFORUsers</a> and <a href="#a15ab200cb0259f0c13b4e068acfd7fc6">mayReadOrWriteMemory</a>.</p>

</div>
</div>

### mayReadOrWriteMemory() {#a15ab200cb0259f0c13b4e068acfd7fc6}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool llvm::VPRecipeBase::mayReadOrWriteMemory ()</td>
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

<p>Returns true if the recipe may read from or write to memory.</p>

<p>Definition at line 800 of file <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/vectorize/vplan-h">VPlan.h</a>.</p>


<p>References <a href="#a00bc7da040562d501bcc0e0635a2b53c">mayReadFromMemory</a> and <a href="#a5fcebe7c77877e7f65c88e61c0fe1149">mayWriteToMemory</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/vectorize/vplantransforms-cpp/#a1536feae2abb3570ac032768a53ddd00">sinkScalarOperands</a>.</p>

</div>
</div>

### mayWriteToMemory() {#a5fcebe7c77877e7f65c88e61c0fe1149}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool VPRecipeBase::mayWriteToMemory ()</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Returns true if the recipe may write to memory.</p>

<p>Declaration at line 797 of file <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/vectorize/vplan-h">VPlan.h</a>, definition at line 52 of file <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/vectorize/vplanrecipes-cpp">VPlanRecipes.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/silowercontrolflow-cpp/#a4868c5d81c5ccc98c47aeab6244346a0">assert</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#ac4fc845f5ed92de63cd4474f128f5fc5">llvm::cast</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a5f6182886dc2f96c204299e92c1565d5">llvm::dyn_cast_or_null</a>, <a href="/web-llvm/docs/api/classes/llvm/vpdef/#ad537baa7adabb231da7e1b79a1e1696b">llvm::VPDef::getVPDefID</a>, <a href="/web-llvm/docs/api/classes/llvm/vpdef/#a76a983b694720483a3dd9fe57314e39b">llvm::VPDef::getVPSingleValue</a> and <a href="/web-llvm/docs/api/files/lib/lib/support/md5-cpp/#ac0eafdc9ee161b71e7af98af736952fd">I</a>.</p>


<p>Referenced by <a href="#a2408a88276528d80adefefa00995705a">mayHaveSideEffects</a> and <a href="#a15ab200cb0259f0c13b4e068acfd7fc6">mayReadOrWriteMemory</a>.</p>

</div>
</div>

### moveAfter() {#af48299a4811bd1572ef5cdf597930edf}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void VPRecipeBase::moveAfter (<a href="/web-llvm/docs/api/classes/llvm/vprecipebase">VPRecipeBase</a> * MovePos)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Unlink this recipe from its current <a href="/web-llvm/docs/api/classes/llvm/vpbasicblock">VPBasicBlock</a> and insert it into the <a href="/web-llvm/docs/api/classes/llvm/vpbasicblock">VPBasicBlock</a> that MovePos lives in, right after MovePos.</p>

<p>Declaration at line 761 of file <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/vectorize/vplan-h">VPlan.h</a>, definition at line 235 of file <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/vectorize/vplanrecipes-cpp">VPlanRecipes.cpp</a>.</p>


<p>References <a href="#a8c02e0ea8aec7fa58b24b6d22f0e3e8e">insertAfter</a>, <a href="#ae4b7881e0e91ff340908b161a10e69b6">removeFromParent</a> and <a href="#aaf68139c582775191f8535403942e5f2">VPRecipeBase</a>.</p>

</div>
</div>

### moveBefore() {#a83c9341e2d36f67d5cad25ba91e862e1}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void VPRecipeBase::moveBefore (<a href="/web-llvm/docs/api/classes/llvm/vpbasicblock">VPBasicBlock</a> &amp; BB, <a href="/web-llvm/docs/api/classes/llvm/iplist">iplist</a>&lt; <a href="/web-llvm/docs/api/classes/llvm/vprecipebase">VPRecipeBase</a> &gt;<a href="/web-llvm/docs/api/classes/llvm/iplist">::iterator</a> I)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Unlink this recipe and insert into BB before I.</p>


<dl class="doxySectionUser">
<dt>Precondition</dt>
<dd><p>I is a valid iterator into BB.</p></dd>
</dl>


<p>Declaration at line 766 of file <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/vectorize/vplan-h">VPlan.h</a>, definition at line 240 of file <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/vectorize/vplanrecipes-cpp">VPlanRecipes.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/files/lib/lib/support/md5-cpp/#ac0eafdc9ee161b71e7af98af736952fd">I</a>, <a href="#a8859e5e8cad5653b278964f47414fd84">insertBefore</a> and <a href="#ae4b7881e0e91ff340908b161a10e69b6">removeFromParent</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/vectorize/vplantransforms-cpp/#a1536feae2abb3570ac032768a53ddd00">sinkScalarOperands</a>.</p>

</div>
</div>

### removeFromParent() {#ae4b7881e0e91ff340908b161a10e69b6}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void VPRecipeBase::removeFromParent ()</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>This method unlinks 'this' from the containing basic block, but does not delete it.</p>

<p>Declaration at line 770 of file <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/vectorize/vplan-h">VPlan.h</a>, definition at line 224 of file <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/vectorize/vplanrecipes-cpp">VPlanRecipes.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/silowercontrolflow-cpp/#a4868c5d81c5ccc98c47aeab6244346a0">assert</a>, <a href="/web-llvm/docs/api/classes/llvm/ilist-node-impl/#af719fc783be6589465137d997701a432">llvm::ilist_node_impl&lt; ilist_detail::compute_node_options&lt; VPRecipeBase, Options... &gt;::type &gt;::getIterator</a>, <a href="#a6c88376daf23b16ad26b7ac6c224d21e">getParent</a>, <a href="/web-llvm/docs/api/classes/llvm/vpbasicblock/#a355ec03c80ff2b96d14a01df0fa35844">llvm::VPBasicBlock::getRecipeList</a> and <a href="/web-llvm/docs/api/classes/llvm/iplist-impl/#a99db7b74235ded8f74e4e2a5cc6f6209">llvm::iplist_impl&lt; IntrusiveListT, TraitsT &gt;::remove</a>.</p>


<p>Referenced by <a href="#af48299a4811bd1572ef5cdf597930edf">moveAfter</a> and <a href="#a83c9341e2d36f67d5cad25ba91e862e1">moveBefore</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Protected Member Functions

### computeCost() {#a677e548bbdd91cb3de30c3de2b40049a}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">InstructionCost VPRecipeBase::computeCost (<a href="/web-llvm/docs/api/classes/llvm/elementcount">ElementCount</a> VF, <a href="/web-llvm/docs/api/structs/llvm/vpcostcontext">VPCostContext</a> &amp; Ctx)</td>
</tr>
</table>
</td>
<td class="doxyMemberLabelsRight">
<span class="doxyMemberLabels">
<span class="doxyMemberLabel protected">protected</span>
<span class="doxyMemberLabel virtual">virtual</span>
</span>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Compute the cost of this recipe either using a recipe's specialized implementation or using the legacy cost model and the underlying instructions.</p>

<p>Declaration at line 811 of file <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/vectorize/vplan-h">VPlan.h</a>, definition at line 276 of file <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/vectorize/vplanrecipes-cpp">VPlanRecipes.cpp</a>.</p>


<p>Reference <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/support/errorhandling-h/#ace243f5c25697a1107cce46626b3dc94">llvm_unreachable</a>.</p>


<p>Referenced by <a href="#ac84a2bc6b484c5d3a03e80ce40f0a14c">cost</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Private Member Attributes

### DL {#a2a12270e9d725d90bdcd522db8a5c6ac}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">DebugLoc llvm::VPRecipeBase::DL</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>The debug location for the recipe.</p>

<p>Definition at line 719 of file <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/vectorize/vplan-h">VPlan.h</a>.</p>

</div>
</div>

### Parent {#a80c68de8f5a578929c5a42a7ae452b1d}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">VPBasicBlock* llvm::VPRecipeBase::Parent = nullptr</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Each VPRecipe belongs to a single <a href="/web-llvm/docs/api/classes/llvm/vpbasicblock">VPBasicBlock</a>.</p>

<p>Definition at line 716 of file <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/vectorize/vplan-h">VPlan.h</a>.</p>

</div>
</div>

### VPBasicBlock {#a352a9464a359d84e0221affad65246dc}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">friend llvm::VPRecipeBase::VPBasicBlock</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 712 of file <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/vectorize/vplan-h">VPlan.h</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Public Static Functions

### classof() {#a94599a3a939b7cf678cc58c8827c4d21}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool llvm::VPRecipeBase::classof (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/vpdef">VPDef</a> * D)</td>
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

<p>Method to support type inquiry through isa, cast, and dyn_cast.</p>

<p>Definition at line 778 of file <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/vectorize/vplan-h">VPlan.h</a>.</p>


<p>References <a href="/web-llvm/docs/api/files/lib/lib/ir/builtingcs-cpp/#a6a9f043784cf87001c84980afa76da82">D</a> and <a href="/web-llvm/docs/api/classes/llvm/vpdef/#ae5915b6b9efc4889c4ff4bfa01bf5903">llvm::VPDef::VPDef</a>.</p>

</div>
</div>

### classof() {#adc8662faed8d6e19081308d8f3d418a2}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool llvm::VPRecipeBase::classof (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/vpuser">VPUser</a> * U)</td>
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



<p>Definition at line 783 of file <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/vectorize/vplan-h">VPlan.h</a>.</p>


<p>Reference <a href="/web-llvm/docs/api/classes/llvm/vpuser/#a76244ee883849bc5ec7c6091697ecaa2">llvm::VPUser::VPUser</a>.</p>

</div>
</div>

</div>

<hr/>

The documentation for this class was generated from the following files:

<ul>
<li><a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/vectorize/vplan-h">VPlan.h</a></li>
<li><a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/vectorize/vplanrecipes-cpp">VPlanRecipes.cpp</a></li>
</ul>

<hr/>

<p class="doxyGeneratedBy">Generated via <a href="https://github.com/xpack/doxygen2docusaurus">doxygen2docusaurus</a> by <a href="https://www.doxygen.nl">Doxygen</a> 1.15.0.</p>

</div>
