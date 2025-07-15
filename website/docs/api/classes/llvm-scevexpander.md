---

# DO NOT EDIT!
# Automatically generated via doxygen2docusaurus by Doxygen.

slug: /api/classes/llvm/scevexpander
custom_edit_url: null
toc_max_heading_level: 4
keywords:
  - doxygen
  - reference
  - class

---

<div class="doxyPage">

# The `SCEVExpander` Class Reference

<p>This class uses information about analyze scalars to rewrite expressions in canonical form. <a href="#details">More...</a></p>

## Declaration

<div class="doxyDeclaration">
class llvm::SCEVExpander { ... }
</div>

## Included Headers

<div class="doxyIncludesList">#include "<a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/transforms/include/llvm/transforms/utils/scalarevolutionexpander-h">llvm/Transforms/Utils/ScalarEvolutionExpander.h</a>"
</div>

## Base class

<table class="doxyMembersIndex">

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">struct</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="/web-llvm/docs/api/structs/llvm/scevvisitor">SCEVVisitor&lt;SC, RetVal&gt;</a></td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>This class defines a simple visitor class that may be used for various <a href="/web-llvm/docs/api/classes/llvm/scev">SCEV</a> analysis purposes. <a href="/web-llvm/docs/api/structs/llvm/scevvisitor/#details">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

</table>

## Private Member Typedefs Index

<table class="doxyMembersIndex">

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">typedef</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/irbuilder">IRBuilder</a>&lt; <a href="/web-llvm/docs/api/classes/llvm/instsimplifyfolder">InstSimplifyFolder</a>, <a href="/web-llvm/docs/api/classes/llvm/irbuildercallbackinserter">IRBuilderCallbackInserter</a> &gt; <a href="#a6700c6176ca232bbbaa3dd7cf66ddf91">BuilderType</a></td>
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

## Friends Index

<table class="doxyMembersIndex">

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">class</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a332b64336604f3d94ee5dfcb9e73471a">SCEVExpanderCleaner</a></td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a3e6aa0e2571ba8a0f5f865a88eebac11">SCEVVisitor&lt; SCEVExpander, Value * &gt;</a></td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a86fc272b516cc390141710ff1b16b74b">SCEVExpander</a> (ScalarEvolution &amp;se, const DataLayout &amp;DL, const char *name, bool PreserveLCSSA=true)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Construct a <a href="/web-llvm/docs/api/classes/llvm/scevexpander">SCEVExpander</a> in "canonical" mode. <a href="#a86fc272b516cc390141710ff1b16b74b">More...</a></p>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a7026820c29a64c16747c3a4fb7eeae09">~SCEVExpander</a> ()</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#aa9bcc84c7b023d3b1321851509110dae">clear</a> ()</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Erase the contents of the InsertedExpressions map so that users trying to expand the same expression into multiple BasicBlocks or different places within the same <a href="/web-llvm/docs/api/classes/llvm/basicblock">BasicBlock</a> can do so. <a href="#aa9bcc84c7b023d3b1321851509110dae">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/scalarevolution">ScalarEvolution</a> *</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a6210fd650d8883005f3b59a97da555c0">getSE</a> ()</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/smallvectorimpl">SmallVectorImpl</a>&lt; <a href="/web-llvm/docs/api/classes/llvm/weakvh">WeakVH</a> &gt; &amp;</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ac1b3b1c5a4e00d4820109245f5bc41e2">getInsertedIVs</a> () const</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/smallvector">SmallVector</a>&lt; <a href="/web-llvm/docs/api/classes/llvm/instruction">Instruction</a> *, 32 &gt;</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a32b54b1dbb903f03b8050884cdecbe7e">getAllInsertedInstructions</a> () const</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Return a vector containing all instructions inserted during expansion. <a href="#a32b54b1dbb903f03b8050884cdecbe7e">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">bool</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a5a1f8f7e12808825560c7a10ec2f970b">isHighCostExpansion</a> (ArrayRef&lt; const SCEV * &gt; Exprs, Loop *L, unsigned Budget, const TargetTransformInfo *TTI, const Instruction *At)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Return true for expressions that can't be evaluated at runtime within given <b>Budget</b>. <a href="#a5a1f8f7e12808825560c7a10ec2f970b">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/instruction">Instruction</a> *</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#aece02adc8e4cc74296bfe410eabe287b">getIVIncOperand</a> (Instruction *IncV, Instruction *InsertPos, bool allowScale)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Return the induction variable increment's IV operand. <a href="#aece02adc8e4cc74296bfe410eabe287b">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">bool</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#aa3255071e8195c43058f7e265c54677f">hoistIVInc</a> (Instruction *IncV, Instruction *InsertPos, bool RecomputePoisonFlags=false)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Utility for hoisting <span class="doxyComputerOutput">IncV</span> (with all subexpressions requried for its computation) before <span class="doxyComputerOutput">InsertPos</span>. <a href="#aa3255071e8195c43058f7e265c54677f">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">unsigned</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a635463dc5e146744799163c2f820e51b">replaceCongruentIVs</a> (Loop *L, const DominatorTree *DT, SmallVectorImpl&lt; WeakTrackingVH &gt; &amp;DeadInsts, const TargetTransformInfo *TTI=nullptr)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>replace congruent phis with their most canonical representative. <a href="#a635463dc5e146744799163c2f820e51b">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">bool</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a3b8edb4179c8a762f5ab29e1dd613c3a">isSafeToExpand</a> (const SCEV *S) const</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Return true if the given expression is safe to expand in the sense that all materialized values are safe to speculate anywhere their operands are defined, and the expander is capable of expanding the expression. <a href="#a3b8edb4179c8a762f5ab29e1dd613c3a">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">bool</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a5c94af409fdce59362329aa65584482d">isSafeToExpandAt</a> (const SCEV *S, const Instruction *InsertionPoint) const</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Return true if the given expression is safe to expand in the sense that all materialized values are defined and safe to speculate at the specified location and their operands are defined at this location. <a href="#a5c94af409fdce59362329aa65584482d">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/value">Value</a> *</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ac711b5659270bd9e66b8f38ec481260c">expandCodeFor</a> (const SCEV *SH, Type *Ty, BasicBlock::iterator I)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Insert code to directly compute the specified <a href="/web-llvm/docs/api/classes/llvm/scev">SCEV</a> expression into the program. <a href="#ac711b5659270bd9e66b8f38ec481260c">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/value">Value</a> *</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ad34ae7fb2daf2fcf542d77e0e99a439e">expandCodeFor</a> (const SCEV *SH, Type *Ty, Instruction *I)</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#aac98cc9f91ac31468cb93febcd484e5b">expandCodeFor</a> (const SCEV *SH, Type *Ty=nullptr)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Insert code to directly compute the specified <a href="/web-llvm/docs/api/classes/llvm/scev">SCEV</a> expression into the program. <a href="#aac98cc9f91ac31468cb93febcd484e5b">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/value">Value</a> *</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#aab89200a9867fdf7476cf0c09e80ef78">expandCodeForPredicate</a> (const SCEVPredicate *Pred, Instruction *Loc)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Generates a code sequence that evaluates this predicate. <a href="#aab89200a9867fdf7476cf0c09e80ef78">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/value">Value</a> *</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ab9d2c872efeb61279eb6cbe774b117d4">expandComparePredicate</a> (const SCEVComparePredicate *Pred, Instruction *Loc)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>A specialized variant of expandCodeForPredicate, handling the case when we are expanding code for a <a href="/web-llvm/docs/api/classes/llvm/scevcomparepredicate">SCEVComparePredicate</a>. <a href="#ab9d2c872efeb61279eb6cbe774b117d4">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/value">Value</a> *</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a16e9052fd33aedf29b009262d35d59f8">generateOverflowCheck</a> (const SCEVAddRecExpr *AR, Instruction *Loc, bool Signed)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Generates code that evaluates if the <span class="doxyComputerOutput">AR</span> expression will overflow. <a href="#a16e9052fd33aedf29b009262d35d59f8">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/value">Value</a> *</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ad160f0c6b2de8059d92dbff54d093531">expandWrapPredicate</a> (const SCEVWrapPredicate *P, Instruction *Loc)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>A specialized variant of expandCodeForPredicate, handling the case when we are expanding code for a <a href="/web-llvm/docs/api/classes/llvm/scevwrappredicate">SCEVWrapPredicate</a>. <a href="#ad160f0c6b2de8059d92dbff54d093531">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/value">Value</a> *</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a88dfee6623475363a4e46966d8383c0f">expandUnionPredicate</a> (const SCEVUnionPredicate *Pred, Instruction *Loc)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>A specialized variant of expandCodeForPredicate, handling the case when we are expanding code for a <a href="/web-llvm/docs/api/classes/llvm/scevunionpredicate">SCEVUnionPredicate</a>. <a href="#a88dfee6623475363a4e46966d8383c0f">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">void</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#abb16499dadbe473c428b55f72850ef97">setIVIncInsertPos</a> (const Loop *L, Instruction *Pos)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Set the current IV increment loop and position. <a href="#abb16499dadbe473c428b55f72850ef97">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">void</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#aaca0b4b6c0a7f9a36f043b993177e03e">setPostInc</a> (const PostIncLoopSet &amp;L)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Enable post-inc expansion for addrecs referring to the given loops. <a href="#aaca0b4b6c0a7f9a36f043b993177e03e">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">void</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a767b257cc39ee9ea9e0edcee4220c00c">clearPostInc</a> ()</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Disable all post-inc expansion. <a href="#a767b257cc39ee9ea9e0edcee4220c00c">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">void</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#acfd53cb9ef34b9c9d9428fdaf08e0f0b">disableCanonicalMode</a> ()</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Disable the behavior of expanding expressions in canonical form rather than in a more literal form. <a href="#acfd53cb9ef34b9c9d9428fdaf08e0f0b">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">void</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a546c51290ce25125f40293fb4ebc1919">enableLSRMode</a> ()</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#afb583e40ce2835c2afa2e05e84fd5b87">setInsertPoint</a> (Instruction *IP)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Set the current insertion point. <a href="#afb583e40ce2835c2afa2e05e84fd5b87">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">void</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a55844f6b9919e935ae52085f77eff21f">setInsertPoint</a> (BasicBlock::iterator IP)</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a647982e2639d56e8f172122bb422aca1">clearInsertPoint</a> ()</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Clear the current insertion point. <a href="#a647982e2639d56e8f172122bb422aca1">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">void</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ab1ef4391900efc4cf934806ea7d43166">SetCurrentDebugLocation</a> (DebugLoc L)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Set location information used by debugging information. <a href="#ab1ef4391900efc4cf934806ea7d43166">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/debugloc">DebugLoc</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ab001af82df1eacb91579783e1d382875">getCurrentDebugLocation</a> () const</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Get location information used by debugging information. <a href="#ab001af82df1eacb91579783e1d382875">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">bool</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#aab1d5fe8452ef0d6995904efe86ef9ff">isInsertedInstruction</a> (Instruction *I) const</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Return true if the specified instruction was inserted by the code rewriter. <a href="#aab1d5fe8452ef0d6995904efe86ef9ff">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">void</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a346ef44d7050fbf42b5d871ba5006b80">setChainedPhi</a> (PHINode *PN)</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a19bc2d813d4dfa8408b259b197d1e34d">hasRelatedExistingExpansion</a> (const SCEV *S, const Instruction *At, Loop *L)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Determine whether there is an existing expansion of S that can be reused. <a href="#a19bc2d813d4dfa8408b259b197d1e34d">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/basicblock/#a98c0a84a5dfa8bce341c829709f171e5">BasicBlock::iterator</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#af99566d9ade6807a99ccf61cb126e1be">findInsertPointAfter</a> (Instruction *I, Instruction *MustDominate) const</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Returns a suitable insert point after <span class="doxyComputerOutput">I</span>, that dominates <span class="doxyComputerOutput">MustDominate</span>. <a href="#af99566d9ade6807a99ccf61cb126e1be">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

</table>

## Private Member Functions Index

<table class="doxyMembersIndex">

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/llvmcontext">LLVMContext</a> &amp;</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a2ea3589aabbc830e5906cb2b2ff673c2">getContext</a> () const</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a5beeb02a287212152542a26ff6db5d3d">isHighCostExpansionHelper</a> (const SCEVOperand &amp;WorkItem, Loop *L, const Instruction &amp;At, InstructionCost &amp;Cost, unsigned Budget, const TargetTransformInfo &amp;TTI, SmallPtrSetImpl&lt; const SCEV * &gt; &amp;Processed, SmallVectorImpl&lt; SCEVOperand &gt; &amp;Worklist)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Recursive helper function for isHighCostExpansion. <a href="#a5beeb02a287212152542a26ff6db5d3d">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/value">Value</a> *</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a8a8fe26d9e9ce5a24e045401e9ef1fba">InsertBinop</a> (Instruction::BinaryOps Opcode, Value *LHS, Value *RHS, SCEV::NoWrapFlags Flags, bool IsSafeToHoist)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Insert the specified binary operator, doing a small amount of work to avoid inserting an obviously redundant operation, and hoisting to an outer loop when the opportunity is there and it is safe. <a href="#a8a8fe26d9e9ce5a24e045401e9ef1fba">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/basicblock/#a98c0a84a5dfa8bce341c829709f171e5">BasicBlock::iterator</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a7dea7b651c5214c21829ba40ef3e15c5">GetOptimalInsertionPointForCastOf</a> (Value *V) const</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>We want to cast <span class="doxyComputerOutput">V</span>. What would be the best place for such a cast? <a href="#a7dea7b651c5214c21829ba40ef3e15c5">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/value">Value</a> *</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a00becc53359635fb5eaff2e972bc4de1">ReuseOrCreateCast</a> (Value *V, Type *Ty, Instruction::CastOps Op, BasicBlock::iterator IP)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Arrange for there to be a cast of V to Ty at IP, reusing an existing cast if a suitable one exists, moving an existing cast if a suitable one exists but isn't in the right place, or creating a new one. <a href="#a00becc53359635fb5eaff2e972bc4de1">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/value">Value</a> *</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a6546e8e825e04691c207c67f6bc6ea18">InsertNoopCastOfTo</a> (Value *V, Type *Ty)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Insert a cast of V to the specified type, which must be possible with a noop cast, doing what we can to share the casts. <a href="#a6546e8e825e04691c207c67f6bc6ea18">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/value">Value</a> *</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a567935fdae75b6acc865c1b66aa4311a">expandAddToGEP</a> (const SCEV *Op, Value *V, SCEV::NoWrapFlags Flags)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Expand a <a href="/web-llvm/docs/api/classes/llvm/scevaddexpr">SCEVAddExpr</a> with a pointer type into a GEP instead of using ptrtoint+arithmetic+inttoptr. <a href="#a567935fdae75b6acc865c1b66aa4311a">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/value">Value</a> *</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a467dca4de216e2f1beae85be93ec2141">FindValueInExprValueMap</a> (const SCEV *S, const Instruction *InsertPt, SmallVectorImpl&lt; Instruction * &gt; &amp;DropPoisonGeneratingInsts)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Find a previous <a href="/web-llvm/docs/api/classes/llvm/value">Value</a> in ExprValueMap for expand. <a href="#a467dca4de216e2f1beae85be93ec2141">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/value">Value</a> *</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a69efede7551620cf802005ca401b1bf0">expand</a> (const SCEV *S)</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a8916a99b2298f31251b3ddb4be82af23">expand</a> (const SCEV *S, BasicBlock::iterator I)</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#abefaa79a0a0cc0eccfde0a2c08f7244d">expand</a> (const SCEV *S, Instruction *I)</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/loop">Loop</a> *</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ac97e7b4527246d0d493542b6fc43d1ea">getRelevantLoop</a> (const SCEV *)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Determine the most "relevant" loop for the given <a href="/web-llvm/docs/api/classes/llvm/scev">SCEV</a>. <a href="#ac97e7b4527246d0d493542b6fc43d1ea">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/value">Value</a> *</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ad35d57cfffa31ac0df7ef469f2febe27">expandMinMaxExpr</a> (const SCEVNAryExpr *S, Intrinsic::ID IntrinID, Twine Name, bool IsSequential=false)</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a3509e77c195527afc04aa5c101055826">visitConstant</a> (const SCEVConstant *S)</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a0f314fdc34263b3b7fe45b9854101076">visitVScale</a> (const SCEVVScale *S)</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a915ebbc1983b769a69936da9e4d9a8dd">visitPtrToIntExpr</a> (const SCEVPtrToIntExpr *S)</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a2d18716a1b4bd0fb83cdac8e38f5094c">visitTruncateExpr</a> (const SCEVTruncateExpr *S)</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a25b413caf366ce2d1af3620b896516e6">visitZeroExtendExpr</a> (const SCEVZeroExtendExpr *S)</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a6eb5295d5b4300f2b8cd27e4de900bac">visitSignExtendExpr</a> (const SCEVSignExtendExpr *S)</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ab05c7beecf728417d5575f52c4363a5f">visitAddExpr</a> (const SCEVAddExpr *S)</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a4da0f47660e915dce9913e42ff5c5cad">visitMulExpr</a> (const SCEVMulExpr *S)</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a44f1be06c0bddaff604a737c2cc5c017">visitUDivExpr</a> (const SCEVUDivExpr *S)</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a6e67c29f8e93322975735619cc1db892">visitAddRecExpr</a> (const SCEVAddRecExpr *S)</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#af2ae2afd31b9f1743aa4431f9dd65f55">visitSMaxExpr</a> (const SCEVSMaxExpr *S)</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a398aa5a8fd378f41bc7149f27cc4f346">visitUMaxExpr</a> (const SCEVUMaxExpr *S)</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a76d351568dea2dea73b5831973553a02">visitSMinExpr</a> (const SCEVSMinExpr *S)</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a0c1068c29244f77a14d302b79056337e">visitUMinExpr</a> (const SCEVUMinExpr *S)</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ac44a236f94f64a6c44bfaf3bc8d752ae">visitSequentialUMinExpr</a> (const SCEVSequentialUMinExpr *S)</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a28a21749896dfc7b6c70b6b87e038d48">visitUnknown</a> (const SCEVUnknown *S)</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a6331d66bb0cafa41e3ae0efe90dbcf2f">rememberInstruction</a> (Value *I)</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#aa5f25e2fa644adb54fc9c90d6eebfd53">rememberFlags</a> (Instruction *I)</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a79250227f2ba8c48c6a4d6375235e4b4">isNormalAddRecExprPHI</a> (PHINode *PN, Instruction *IncV, const Loop *L)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Determine if this is a well-behaved chain of instructions leading back to the PHI. <a href="#a79250227f2ba8c48c6a4d6375235e4b4">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">bool</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a45c836c43811b79ea3963f5ac552836c">isExpandedAddRecExprPHI</a> (PHINode *PN, Instruction *IncV, const Loop *L)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Determine if this cyclic phi is in a form that would have been generated by LSR. <a href="#a45c836c43811b79ea3963f5ac552836c">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/value">Value</a> *</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a194469ade12ed18650764bea85aa3b70">expandAddRecExprLiterally</a> (const SCEVAddRecExpr *)</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/phinode">PHINode</a> *</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a304441fb9d5b724603ecf7dab9edfc4f">getAddRecExprPHILiterally</a> (const SCEVAddRecExpr *Normalized, const Loop *L, Type *&amp;TruncTy, bool &amp;InvertStep)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>getAddRecExprPHILiterally - Helper for expandAddRecExprLiterally. <a href="#a304441fb9d5b724603ecf7dab9edfc4f">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/value">Value</a> *</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ac9d886f8773a9b85d9a9cf760ed8fe85">expandIVInc</a> (PHINode *PN, Value *StepV, const Loop *L, bool useSubtract)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>expandIVInc - Expand an IV increment at Builder's current InsertPos. <a href="#ac9d886f8773a9b85d9a9cf760ed8fe85">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">void</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a64986ad1d7ce9af41f0d780e8c0d6e67">fixupInsertPoints</a> (Instruction *I)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>If the insert point of the current builder or any of the builders on the stack of saved builders has 'I' as its insert point, update it to point to the instruction after 'I'. <a href="#a64986ad1d7ce9af41f0d780e8c0d6e67">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/value">Value</a> *</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a234e6cfb2c2b3424edfe16fabc93fd42">fixupLCSSAFormFor</a> (Value *V)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Create LCSSA PHIs for <span class="doxyComputerOutput">V</span>, if it is required for uses at the Builder's current insertion point. <a href="#a234e6cfb2c2b3424edfe16fabc93fd42">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">void</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a249cad3acbfbd79f098428a00be02b27">replaceCongruentIVInc</a> (PHINode *&amp;Phi, PHINode *&amp;OrigPhi, Loop *L, const DominatorTree *DT, SmallVectorImpl&lt; WeakTrackingVH &gt; &amp;DeadInsts)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Replace congruent phi increments with their most canonical representative. <a href="#a249cad3acbfbd79f098428a00be02b27">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

</table>

## Private Member Attributes Index

<table class="doxyMembersIndex">

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/scalarevolution">ScalarEvolution</a> &amp;</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a4c360cc24c148a24284ef7e05ac57f46">SE</a></td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a2832d8d750888adfa930a40f4b775cfc">DL</a></td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> char *</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a13740ed2a75d6c4cdfa2977908f48ee8">IVName</a></td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a5610ec331defe47156f77671fa962cf9">PreserveLCSSA</a></td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Indicates whether LCSSA phis should be created for inserted values. <a href="#a5610ec331defe47156f77671fa962cf9">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/densemap">DenseMap</a>&lt; std::pair&lt; <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/scev">SCEV</a> *, <a href="/web-llvm/docs/api/classes/llvm/instruction">Instruction</a> * &gt;, <a href="/web-llvm/docs/api/classes/llvm/trackingvh">TrackingVH</a>&lt; <a href="/web-llvm/docs/api/classes/llvm/value">Value</a> &gt; &gt;</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a302a7e2c1398c2eb3c15bd1d10942e32">InsertedExpressions</a></td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/denseset">DenseSet</a>&lt; <a href="/web-llvm/docs/api/classes/llvm/assertingvh">AssertingVH</a>&lt; <a href="/web-llvm/docs/api/classes/llvm/value">Value</a> &gt; &gt;</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a9617c9357c65d9674eea0265f8da3873">InsertedValues</a></td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/denseset">DenseSet</a>&lt; <a href="/web-llvm/docs/api/classes/llvm/assertingvh">AssertingVH</a>&lt; <a href="/web-llvm/docs/api/classes/llvm/value">Value</a> &gt; &gt;</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a4a1a76d8b898087e1fb5c55992f0fbbc">InsertedPostIncValues</a></td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/smallptrset">SmallPtrSet</a>&lt; <a href="/web-llvm/docs/api/classes/llvm/value">Value</a> *, 16 &gt;</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a5a690e395170641aa3c09f7c66bad964">ReusedValues</a></td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Keep track of the existing IR values re-used during expansion. <a href="#a5a690e395170641aa3c09f7c66bad964">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/densemap">DenseMap</a>&lt; <a href="/web-llvm/docs/api/classes/llvm/poisoningvh">PoisoningVH</a>&lt; <a href="/web-llvm/docs/api/classes/llvm/instruction">Instruction</a> &gt;, <a href="/web-llvm/docs/api/structs/llvm/poisonflags">PoisonFlags</a> &gt;</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#abd1d4ea0467c3ce8222cd25561b12ffe">OrigFlags</a></td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Original flags of instructions for which they were modified. <a href="#abd1d4ea0467c3ce8222cd25561b12ffe">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/smallvector">SmallVector</a>&lt; <a href="/web-llvm/docs/api/classes/llvm/weakvh">WeakVH</a>, 2 &gt;</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a15c246fd830232a66b70e97ba4e15b9a">InsertedIVs</a></td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/densemap">DenseMap</a>&lt; <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/scev">SCEV</a> *, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/loop">Loop</a> * &gt;</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a6f46521c2c6d6f03d58c6e1ca1c0a36b">RelevantLoops</a></td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>A memoization of the "relevant" loop for a given <a href="/web-llvm/docs/api/classes/llvm/scev">SCEV</a>. <a href="#a6f46521c2c6d6f03d58c6e1ca1c0a36b">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/namespaces/llvm/#ac765465998d0f34ed6123631bda54fab">PostIncLoopSet</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a2cf670fa81b4a4fcec22a7a9ea79798b">PostIncLoops</a></td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Addrecs referring to any of the given loops are expanded in post-inc mode. <a href="#a2cf670fa81b4a4fcec22a7a9ea79798b">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/loop">Loop</a> *</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#aedd96ed7cabfbe35949d6728ecc366f2">IVIncInsertLoop</a></td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>When this is non-null, addrecs expanded in the loop it indicates should be inserted with increments at IVIncInsertPos. <a href="#aedd96ed7cabfbe35949d6728ecc366f2">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/instruction">Instruction</a> *</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#aab6603f1fe9f273708ae12dea838b750">IVIncInsertPos</a></td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>When expanding addrecs in the IVIncInsertLoop loop, insert the IV increment at this position. <a href="#aab6603f1fe9f273708ae12dea838b750">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/denseset">DenseSet</a>&lt; <a href="/web-llvm/docs/api/classes/llvm/assertingvh">AssertingVH</a>&lt; <a href="/web-llvm/docs/api/classes/llvm/phinode">PHINode</a> &gt; &gt;</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ab3bc6e83a36928fb09e9bdaa9f962108">ChainedPhis</a></td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Phis that complete an IV chain. Reuse. <a href="#ab3bc6e83a36928fb09e9bdaa9f962108">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">bool</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#af49abbf03c5d46468304e5166990598d">CanonicalMode</a></td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>When true, <a href="/web-llvm/docs/api/classes/llvm/scevexpander">SCEVExpander</a> tries to expand expressions in "canonical" form. <a href="#af49abbf03c5d46468304e5166990598d">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">bool</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a6c3ec10b8aa0d9f2e18bd287d27da800">LSRMode</a></td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>When invoked from LSR, the expander is in "strength reduction" mode. <a href="#a6c3ec10b8aa0d9f2e18bd287d27da800">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">bool</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a0d3639e3fea688663e85d1ff25a7720d">SafeUDivMode</a> = false</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>When true, rewrite any divisors of UDiv expressions that may be 0 to umax(Divisor, 1) to avoid introducing UB. <a href="#a0d3639e3fea688663e85d1ff25a7720d">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/irbuilder">BuilderType</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a39ca47578ad55b6c8bb653c64c3bf536">Builder</a></td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/smallvector">SmallVector</a>&lt; SCEVInsertPointGuard *, 8 &gt;</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a56d3a87956a2f3c48107d38538edd801">InsertPointGuards</a></td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Stack of pointers to saved insert points, used to keep insert points consistent when instructions are moved. <a href="#a56d3a87956a2f3c48107d38538edd801">More...</a></p>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#aad8311debca961aeee16791414f9efa1">canReuseFlagsFromOriginalIVInc</a> (PHINode *OrigPhi, PHINode *WidePhi, Instruction *OrigInc, Instruction *WideInc)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Return true if both increments directly increment the corresponding IV PHI nodes and have the same opcode. <a href="#aad8311debca961aeee16791414f9efa1">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

</table>

## Description {#details}

<p>This class uses information about analyze scalars to rewrite expressions in canonical form.</p>


<p>Clients should create an instance of this class when rewriting is needed, and destroy it when finished to allow the release of the associated memory.</p>


<p>Definition at line 63 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/transforms/include/llvm/transforms/utils/scalarevolutionexpander-h">ScalarEvolutionExpander.h</a>.</p>


<div class="doxySectionDef">

## Private Member Typedefs

### BuilderType {#a6700c6176ca232bbbaa3dd7cf66ddf91}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">typedef IRBuilder&lt;InstSimplifyFolder, IRBuilderCallbackInserter&gt; llvm::SCEVExpander::BuilderType</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 134 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/transforms/include/llvm/transforms/utils/scalarevolutionexpander-h">ScalarEvolutionExpander.h</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Friends

### SCEVExpanderCleaner {#a332b64336604f3d94ee5dfcb9e73471a}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">friend class <a href="/web-llvm/docs/api/classes/llvm/scevexpandercleaner">SCEVExpanderCleaner</a></td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">


<p>Definition at line 64 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/transforms/include/llvm/transforms/utils/scalarevolutionexpander-h">ScalarEvolutionExpander.h</a>.</p>


<p>References <a href="/web-llvm/docs/api/files/lib/lib/ir/builtingcs-cpp/#ae76959fe811ba090de4cba69ac00f1da">B</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a0e00fad9c34de40b1e31f3aa6f8e024cae1e4c8c9ccd9fc39c391da4bcd093fb2">llvm::Block</a>, <a href="#ab001af82df1eacb91579783e1d382875">getCurrentDebugLocation</a>, <a href="#a86fc272b516cc390141710ff1b16b74b">SCEVExpander</a> and <a href="#a332b64336604f3d94ee5dfcb9e73471a">SCEVExpanderCleaner</a>.</p>


<p>Referenced by <a href="#a332b64336604f3d94ee5dfcb9e73471a">SCEVExpanderCleaner</a>.</p>

</div>
</div>

### SCEVVisitor&lt; SCEVExpander, Value \* &gt; {#a3e6aa0e2571ba8a0f5f865a88eebac11}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">friend struct <a href="/web-llvm/docs/api/structs/llvm/scevvisitor">SCEVVisitor</a>&lt; <a href="/web-llvm/docs/api/classes/llvm/scevexpander">SCEVExpander</a>, <a href="/web-llvm/docs/api/classes/llvm/value">Value</a> * &gt;</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">


<p>Definition at line 175 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/transforms/include/llvm/transforms/utils/scalarevolutionexpander-h">ScalarEvolutionExpander.h</a>.</p>


<p>Reference <a href="#a86fc272b516cc390141710ff1b16b74b">SCEVExpander</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Public Constructors

### SCEVExpander() {#a86fc272b516cc390141710ff1b16b74b}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">llvm::SCEVExpander::SCEVExpander (<a href="/web-llvm/docs/api/classes/llvm/scalarevolution">ScalarEvolution</a> &amp; se, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/datalayout">DataLayout</a> &amp; DL, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> char * name, bool PreserveLCSSA=<a href="/web-llvm/docs/api/files/lib/lib/analysis/basicaliasanalysis-cpp/#af6d5cafbdfc5313e65d990120021a3ec">true</a>)</td>
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

<p>Construct a <a href="/web-llvm/docs/api/classes/llvm/scevexpander">SCEVExpander</a> in "canonical" mode.</p>

<p>Definition at line 185 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/transforms/include/llvm/transforms/utils/scalarevolutionexpander-h">ScalarEvolutionExpander.h</a>.</p>


<p>References <a href="/web-llvm/docs/api/files/lib/lib/support/md5-cpp/#ac0eafdc9ee161b71e7af98af736952fd">I</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/smeabipass-cpp/#a8f8f80d37794cde9472343e4487ba3eb">name</a> and <a href="/web-llvm/docs/api/files/lib/lib/analysis/basicaliasanalysis-cpp/#af6d5cafbdfc5313e65d990120021a3ec">true</a>.</p>


<p>Referenced by <a href="#a332b64336604f3d94ee5dfcb9e73471a">SCEVExpanderCleaner</a> and <a href="#a3e6aa0e2571ba8a0f5f865a88eebac11">SCEVVisitor&lt; SCEVExpander, Value * &gt;</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Public Destructor

### \~SCEVExpander() {#a7026820c29a64c16747c3a4fb7eeae09}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">llvm::SCEVExpander::~SCEVExpander ()</td>
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



<p>Definition at line 198 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/transforms/include/llvm/transforms/utils/scalarevolutionexpander-h">ScalarEvolutionExpander.h</a>.</p>


<p>Reference <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/silowercontrolflow-cpp/#a4868c5d81c5ccc98c47aeab6244346a0">assert</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Public Member Functions

### clear() {#aa9bcc84c7b023d3b1321851509110dae}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void llvm::SCEVExpander::clear ()</td>
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

<p>Erase the contents of the InsertedExpressions map so that users trying to expand the same expression into multiple BasicBlocks or different places within the same <a href="/web-llvm/docs/api/classes/llvm/basicblock">BasicBlock</a> can do so.</p>

<p>Definition at line 210 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/transforms/include/llvm/transforms/utils/scalarevolutionexpander-h">ScalarEvolutionExpander.h</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/scalar/looptermfold-cpp/#ae78c54dce6798892e47ca90660f9a8f6">RunTermFold</a>.</p>

</div>
</div>

### clearInsertPoint() {#a647982e2639d56e8f172122bb422aca1}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void llvm::SCEVExpander::clearInsertPoint ()</td>
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

<p>Clear the current insertion point.</p>


<p>This is useful if the instruction that had been serving as the insertion point may have been deleted.</p>


<p>Definition at line 392 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/transforms/include/llvm/transforms/utils/scalarevolutionexpander-h">ScalarEvolutionExpander.h</a>.</p>

</div>
</div>

### clearPostInc() {#a767b257cc39ee9ea9e0edcee4220c00c}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void llvm::SCEVExpander::clearPostInc ()</td>
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

<p>Disable all post-inc expansion.</p>

<p>Definition at line 362 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/transforms/include/llvm/transforms/utils/scalarevolutionexpander-h">ScalarEvolutionExpander.h</a>.</p>

</div>
</div>

### disableCanonicalMode() {#acfd53cb9ef34b9c9d9428fdaf08e0f0b}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void llvm::SCEVExpander::disableCanonicalMode ()</td>
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

<p>Disable the behavior of expanding expressions in canonical form rather than in a more literal form.</p>


<p>Non-canonical mode is useful for late optimization passes.</p>


<p>Definition at line 373 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/transforms/include/llvm/transforms/utils/scalarevolutionexpander-h">ScalarEvolutionExpander.h</a>.</p>

</div>
</div>

### enableLSRMode() {#a546c51290ce25125f40293fb4ebc1919}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void llvm::SCEVExpander::enableLSRMode ()</td>
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



<p>Definition at line 375 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/transforms/include/llvm/transforms/utils/scalarevolutionexpander-h">ScalarEvolutionExpander.h</a>.</p>

</div>
</div>

### expandCodeFor() {#ac711b5659270bd9e66b8f38ec481260c}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">Value * SCEVExpander::expandCodeFor (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/scev">SCEV</a> * SH, <a href="/web-llvm/docs/api/classes/llvm/type">Type</a> * Ty, <a href="/web-llvm/docs/api/classes/llvm/basicblock/#a98c0a84a5dfa8bce341c829709f171e5">BasicBlock::iterator</a> I)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Insert code to directly compute the specified <a href="/web-llvm/docs/api/classes/llvm/scev">SCEV</a> expression into the program.</p>


<p>The code is inserted into the specified block.</p>


<p>Declaration at line 312 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/transforms/include/llvm/transforms/utils/scalarevolutionexpander-h">ScalarEvolutionExpander.h</a>, definition at line 1443 of file <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/utils/scalarevolutionexpander-cpp">ScalarEvolutionExpander.cpp</a>.</p>


<p>References <a href="#ac711b5659270bd9e66b8f38ec481260c">expandCodeFor</a> and <a href="#afb583e40ce2835c2afa2e05e84fd5b87">setInsertPoint</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/namespaces/llvm/#ad4f572b4f4bf6aa2dbf10a0bd160280d">llvm::addDiffRuntimeChecks</a>, <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/vectorize/slpvectorizer-cpp/#a0a8a72a5038e4a261d35418751506868">calculateRtStride</a>, <a href="#ac711b5659270bd9e66b8f38ec481260c">expandCodeFor</a>, <a href="#ad34ae7fb2daf2fcf542d77e0e99a439e">expandCodeFor</a>, <a href="/web-llvm/docs/api/structs/llvm/loopstructure/#adc8650d6098e0949f6ecc6368c2ebb99">llvm::LoopStructure::parseLoopStructure</a>, <a href="/web-llvm/docs/api/classes/llvm/loopconstrainer/#af041772a16751b1c52d52ae08cd5046d">llvm::LoopConstrainer::run</a>, <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/scalar/looptermfold-cpp/#ae78c54dce6798892e47ca90660f9a8f6">RunTermFold</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a2776b4c8cd41fd60781f7b9e18af9edb">llvm::splitLoopBound</a> and <a href="/web-llvm/docs/api/namespaces/llvm/#acd628d451ca9d9b021876d59f46e670b">llvm::UnrollRuntimeLoopRemainder</a>.</p>

</div>
</div>

### expandCodeFor() {#ad34ae7fb2daf2fcf542d77e0e99a439e}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">Value * llvm::SCEVExpander::expandCodeFor (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/scev">SCEV</a> * SH, <a href="/web-llvm/docs/api/classes/llvm/type">Type</a> * Ty, <a href="/web-llvm/docs/api/classes/llvm/instruction">Instruction</a> * I)</td>
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



<p>Definition at line 313 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/transforms/include/llvm/transforms/utils/scalarevolutionexpander-h">ScalarEvolutionExpander.h</a>.</p>


<p>References <a href="#ac711b5659270bd9e66b8f38ec481260c">expandCodeFor</a> and <a href="/web-llvm/docs/api/files/lib/lib/support/md5-cpp/#ac0eafdc9ee161b71e7af98af736952fd">I</a>.</p>

</div>
</div>

### expandCodeFor() {#aac98cc9f91ac31468cb93febcd484e5b}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">Value * SCEVExpander::expandCodeFor (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/scev">SCEV</a> * SH, <a href="/web-llvm/docs/api/classes/llvm/type">Type</a> * Ty=nullptr)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Insert code to directly compute the specified <a href="/web-llvm/docs/api/classes/llvm/scev">SCEV</a> expression into the program.</p>


<p>The code is inserted into the <a href="/web-llvm/docs/api/classes/llvm/scevexpander">SCEVExpander</a>'s current insertion point. If a type is specified, the result will be expanded to have that type, with a cast if necessary.</p>


<p>Declaration at line 321 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/transforms/include/llvm/transforms/utils/scalarevolutionexpander-h">ScalarEvolutionExpander.h</a>, definition at line 1450 of file <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/utils/scalarevolutionexpander-cpp">ScalarEvolutionExpander.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/silowercontrolflow-cpp/#a4868c5d81c5ccc98c47aeab6244346a0">assert</a> and <a href="/web-llvm/docs/api/classes/llvm/scev/#aefeda9454a5e8dfcec3deb106964832a">llvm::SCEV::getType</a>.</p>

</div>
</div>

### expandCodeForPredicate() {#aab89200a9867fdf7476cf0c09e80ef78}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">Value * SCEVExpander::expandCodeForPredicate (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/scevpredicate">SCEVPredicate</a> * Pred, <a href="/web-llvm/docs/api/classes/llvm/instruction">Instruction</a> * Loc)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Generates a code sequence that evaluates this predicate.</p>


<p>The inserted instructions will be at position <span class="doxyComputerOutput"><a href="/web-llvm/docs/api/namespaces/llvm/loc">Loc</a></span>. The result will be of type i1 and will have a value of 0 when the predicate is false and 1 otherwise.</p>


<p>Declaration at line 326 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/transforms/include/llvm/transforms/utils/scalarevolutionexpander-h">ScalarEvolutionExpander.h</a>, definition at line 2067 of file <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/utils/scalarevolutionexpander-cpp">ScalarEvolutionExpander.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/silowercontrolflow-cpp/#a4868c5d81c5ccc98c47aeab6244346a0">assert</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#ac4fc845f5ed92de63cd4474f128f5fc5">llvm::cast</a>, <a href="#ab9d2c872efeb61279eb6cbe774b117d4">expandComparePredicate</a>, <a href="#a88dfee6623475363a4e46966d8383c0f">expandUnionPredicate</a>, <a href="#ad160f0c6b2de8059d92dbff54d093531">expandWrapPredicate</a>, <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/support/errorhandling-h/#ace243f5c25697a1107cce46626b3dc94">llvm_unreachable</a>, <a href="/web-llvm/docs/api/classes/llvm/scevpredicate/#a75f4943e861ac0b6d41439c7d5c07adba319b527f8f84903a6c37695faf0bc2c8">llvm::SCEVPredicate::P_Compare</a>, <a href="/web-llvm/docs/api/classes/llvm/scevpredicate/#a75f4943e861ac0b6d41439c7d5c07adba8905d2b2d2eed2135c4c6cc4af11e311">llvm::SCEVPredicate::P_Union</a> and <a href="/web-llvm/docs/api/classes/llvm/scevpredicate/#a75f4943e861ac0b6d41439c7d5c07adbaac3069eca0cb48a03eaa7d95fb84829c">llvm::SCEVPredicate::P_Wrap</a>.</p>


<p>Referenced by <a href="#a88dfee6623475363a4e46966d8383c0f">expandUnionPredicate</a>.</p>

</div>
</div>

### expandComparePredicate() {#ab9d2c872efeb61279eb6cbe774b117d4}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">Value * SCEVExpander::expandComparePredicate (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/scevcomparepredicate">SCEVComparePredicate</a> * Pred, <a href="/web-llvm/docs/api/classes/llvm/instruction">Instruction</a> * Loc)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>A specialized variant of expandCodeForPredicate, handling the case when we are expanding code for a <a href="/web-llvm/docs/api/classes/llvm/scevcomparepredicate">SCEVComparePredicate</a>.</p>

<p>Declaration at line 330 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/transforms/include/llvm/transforms/utils/scalarevolutionexpander-h">ScalarEvolutionExpander.h</a>, definition at line 2083 of file <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/utils/scalarevolutionexpander-cpp">ScalarEvolutionExpander.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/classes/llvm/cmpinst/#aa2a54b545d237ecfe450fd1292f7675e">llvm::CmpInst::getInversePredicate</a> and <a href="/web-llvm/docs/api/files/lib/lib/support/md5-cpp/#ac0eafdc9ee161b71e7af98af736952fd">I</a>.</p>


<p>Referenced by <a href="#aab89200a9867fdf7476cf0c09e80ef78">expandCodeForPredicate</a>.</p>

</div>
</div>

### expandUnionPredicate() {#a88dfee6623475363a4e46966d8383c0f}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">Value * SCEVExpander::expandUnionPredicate (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/scevunionpredicate">SCEVUnionPredicate</a> * Pred, <a href="/web-llvm/docs/api/classes/llvm/instruction">Instruction</a> * Loc)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>A specialized variant of expandCodeForPredicate, handling the case when we are expanding code for a <a href="/web-llvm/docs/api/classes/llvm/scevunionpredicate">SCEVUnionPredicate</a>.</p>

<p>Declaration at line 343 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/transforms/include/llvm/transforms/utils/scalarevolutionexpander-h">ScalarEvolutionExpander.h</a>, definition at line 2243 of file <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/utils/scalarevolutionexpander-cpp">ScalarEvolutionExpander.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/classes/llvm/smallvectortemplatecommon/#ad9a3c7bc26b130377bbafc170b5f88a2">llvm::SmallVectorTemplateCommon&lt; T, typename &gt;::empty</a>, <a href="#aab89200a9867fdf7476cf0c09e80ef78">expandCodeForPredicate</a>, <a href="/web-llvm/docs/api/classes/llvm/value/#ab3fc0225d8aaf8434026c3573f961f2c">llvm::Value::getContext</a>, <a href="/web-llvm/docs/api/classes/llvm/constantint/#aa7cce62ac5cc6df09cce0535874336b7">llvm::ConstantInt::getFalse</a> and <a href="/web-llvm/docs/api/classes/llvm/smallvectortemplatebase/#af42bfbc067df27c19ee2fc859df58799">llvm::SmallVectorTemplateBase&lt; T, bool &gt;::push_back</a>.</p>


<p>Referenced by <a href="#aab89200a9867fdf7476cf0c09e80ef78">expandCodeForPredicate</a>.</p>

</div>
</div>

### expandWrapPredicate() {#ad160f0c6b2de8059d92dbff54d093531}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">Value * SCEVExpander::expandWrapPredicate (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/scevwrappredicate">SCEVWrapPredicate</a> * P, <a href="/web-llvm/docs/api/classes/llvm/instruction">Instruction</a> * Loc)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>A specialized variant of expandCodeForPredicate, handling the case when we are expanding code for a <a href="/web-llvm/docs/api/classes/llvm/scevwrappredicate">SCEVWrapPredicate</a>.</p>

<p>Declaration at line 339 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/transforms/include/llvm/transforms/utils/scalarevolutionexpander-h">ScalarEvolutionExpander.h</a>, definition at line 2218 of file <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/utils/scalarevolutionexpander-cpp">ScalarEvolutionExpander.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/files/lib/lib/ir/builtingcs-cpp/#a2e38c85003a042421cde1647632d0b72">A</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#ac4fc845f5ed92de63cd4474f128f5fc5">llvm::cast</a>, <a href="#a16e9052fd33aedf29b009262d35d59f8">generateOverflowCheck</a>, <a href="/web-llvm/docs/api/classes/llvm/value/#ab3fc0225d8aaf8434026c3573f961f2c">llvm::Value::getContext</a>, <a href="/web-llvm/docs/api/classes/llvm/constantint/#aa7cce62ac5cc6df09cce0535874336b7">llvm::ConstantInt::getFalse</a>, <a href="/web-llvm/docs/api/classes/llvm/scevwrappredicate/#a0cfd938ff9c572d287e5e7923624db70aa4c321f736f542d50b81bb06351f7fce">llvm::SCEVWrapPredicate::IncrementNSSW</a> and <a href="/web-llvm/docs/api/classes/llvm/scevwrappredicate/#a0cfd938ff9c572d287e5e7923624db70a17e825823d4b6a92c1b221c4460c91a3">llvm::SCEVWrapPredicate::IncrementNUSW</a>.</p>


<p>Referenced by <a href="#aab89200a9867fdf7476cf0c09e80ef78">expandCodeForPredicate</a>.</p>

</div>
</div>

### findInsertPointAfter() {#af99566d9ade6807a99ccf61cb126e1be}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">BasicBlock::iterator SCEVExpander::findInsertPointAfter (<a href="/web-llvm/docs/api/classes/llvm/instruction">Instruction</a> * I, <a href="/web-llvm/docs/api/classes/llvm/instruction">Instruction</a> * MustDominate)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Returns a suitable insert point after <span class="doxyComputerOutput">I</span>, that dominates <span class="doxyComputerOutput">MustDominate</span>.</p>


<p>Skips instructions inserted by the expander.</p>


<p>Declaration at line 425 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/transforms/include/llvm/transforms/utils/scalarevolutionexpander-h">ScalarEvolutionExpander.h</a>, definition at line 148 of file <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/utils/scalarevolutionexpander-cpp">ScalarEvolutionExpander.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/silowercontrolflow-cpp/#a4868c5d81c5ccc98c47aeab6244346a0">assert</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a22eeee01734061ac1b31ccd994c49eef">llvm::dyn_cast</a>, <a href="/web-llvm/docs/api/classes/llvm/ilist-detail/node-parent-access/#a7e19e7508415378ad9523e0339b23e22">llvm::ilist_detail::node_parent_access&lt; NodeTy, ParentTy &gt;::getParent</a>, <a href="/web-llvm/docs/api/files/lib/lib/support/md5-cpp/#ac0eafdc9ee161b71e7af98af736952fd">I</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/nvptx/nvvmintrrange-cpp/#ac5804672fc0850438d63caec770647f8">II</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a92ca992e52dddc420f4b069cae06dfbe">llvm::isa</a> and <a href="#aab1d5fe8452ef0d6995904efe86ef9ff">isInsertedInstruction</a>.</p>

</div>
</div>

### generateOverflowCheck() {#a16e9052fd33aedf29b009262d35d59f8}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">Value * SCEVExpander::generateOverflowCheck (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/scevaddrecexpr">SCEVAddRecExpr</a> * AR, <a href="/web-llvm/docs/api/classes/llvm/instruction">Instruction</a> * Loc, bool Signed)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Generates code that evaluates if the <span class="doxyComputerOutput">AR</span> expression will overflow.</p>

<p>Declaration at line 334 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/transforms/include/llvm/transforms/utils/scalarevolutionexpander-h">ScalarEvolutionExpander.h</a>, definition at line 2094 of file <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/utils/scalarevolutionexpander-cpp">ScalarEvolutionExpander.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/namespaces/llvm/#aac36edd0f1ce976f0025c98e88d3830eaec211f7c20af43e742bf2570c3cb84f9">llvm::Add</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/silowercontrolflow-cpp/#a4868c5d81c5ccc98c47aeab6244346a0">assert</a>, <a href="/web-llvm/docs/api/classes/llvm/integertype/#a14f7b4f1aed38192fb6b7772eb506bdb">llvm::IntegerType::get</a>, <a href="/web-llvm/docs/api/classes/llvm/value/#ab3fc0225d8aaf8434026c3573f961f2c">llvm::Value::getContext</a>, <a href="/web-llvm/docs/api/classes/llvm/constantint/#aa7cce62ac5cc6df09cce0535874336b7">llvm::ConstantInt::getFalse</a>, <a href="/web-llvm/docs/api/classes/llvm/scevaddrecexpr/#a99ab4a82c6d7373e2e367986b9527bf0">llvm::SCEVAddRecExpr::getLoop</a>, <a href="/web-llvm/docs/api/classes/llvm/apint/#a331d69b5f93e47e7c596062b77dd5913">llvm::APInt::getMaxValue</a>, <a href="/web-llvm/docs/api/classes/llvm/scevaddrecexpr/#a19c13fe96d59c787e900b7bbf7173263">llvm::SCEVAddRecExpr::getStart</a>, <a href="/web-llvm/docs/api/classes/llvm/scevaddrecexpr/#a4049f7040a4628b15f182c3c9aaf802a">llvm::SCEVAddRecExpr::getStepRecurrence</a>, <a href="/web-llvm/docs/api/classes/llvm/scev/#aefeda9454a5e8dfcec3deb106964832a">llvm::SCEV::getType</a>, <a href="/web-llvm/docs/api/classes/llvm/scevaddrecexpr/#a1596600146d065022af8b9c4a1d0b427">llvm::SCEVAddRecExpr::getType</a>, <a href="/web-llvm/docs/api/classes/llvm/apint/#add4e37b60ea64faafbc9a5bf3e27280f">llvm::APInt::getZero</a>, <a href="/web-llvm/docs/api/classes/llvm/cmpinst/#a2be3583dac92a031fa1458d4d992c78bac17897ebf2f6a6986280fc3bdf28a30a">llvm::CmpInst::ICMP_NE</a>, <a href="/web-llvm/docs/api/classes/llvm/cmpinst/#a2be3583dac92a031fa1458d4d992c78ba720a42e85f7e981afd61e28473b0000a">llvm::CmpInst::ICMP_SGT</a>, <a href="/web-llvm/docs/api/classes/llvm/cmpinst/#a2be3583dac92a031fa1458d4d992c78ba15ae464950ac676919c2f0c7aafc706c">llvm::CmpInst::ICMP_SLT</a>, <a href="/web-llvm/docs/api/classes/llvm/cmpinst/#a2be3583dac92a031fa1458d4d992c78ba607cecdc5172814382033e001ed11fad">llvm::CmpInst::ICMP_UGT</a>, <a href="/web-llvm/docs/api/classes/llvm/cmpinst/#a2be3583dac92a031fa1458d4d992c78ba91d86a4753c8bd7624e01bf565d87f8e">llvm::CmpInst::ICMP_ULT</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a92ca992e52dddc420f4b069cae06dfbe">llvm::isa</a>, <a href="/web-llvm/docs/api/classes/llvm/scevaddrecexpr/#a54bb7394d874cbbef1d81e6bea89d4f3">llvm::SCEVAddRecExpr::isAffine</a>, <a href="/web-llvm/docs/api/classes/llvm/scev/#a1ecb726f4e7b445057b795ed500546a0">llvm::SCEV::isOne</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#aac36edd0f1ce976f0025c98e88d3830ea62b6d55816cf737bfc6f42e60df1a3f2">llvm::Mul</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/nvptx/nvptxisellowering-cpp/#ae1a90b5d85643644483b2ca70da4d13faed3fa7a5efe80dad3ea3d86cc14be246">Signed</a> and <a href="/web-llvm/docs/api/classes/llvm/apint/#a1dc76cc8bf703e6ada68bededcbb9573">llvm::APInt::zext</a>.</p>


<p>Referenced by <a href="#ad160f0c6b2de8059d92dbff54d093531">expandWrapPredicate</a>.</p>

</div>
</div>

### getAllInsertedInstructions() {#a32b54b1dbb903f03b8050884cdecbe7e}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">SmallVector&lt; Instruction *, 32 &gt; llvm::SCEVExpander::getAllInsertedInstructions ()</td>
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

<p>Return a vector containing all instructions inserted during expansion.</p>

<p>Definition at line 224 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/transforms/include/llvm/transforms/utils/scalarevolutionexpander-h">ScalarEvolutionExpander.h</a>.</p>


<p>Reference <a href="/web-llvm/docs/api/namespaces/llvm/#a22eeee01734061ac1b31ccd994c49eef">llvm::dyn_cast</a>.</p>

</div>
</div>

### getCurrentDebugLocation() {#ab001af82df1eacb91579783e1d382875}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">DebugLoc llvm::SCEVExpander::getCurrentDebugLocation ()</td>
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

<p>Get location information used by debugging information.</p>

<p>Definition at line 400 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/transforms/include/llvm/transforms/utils/scalarevolutionexpander-h">ScalarEvolutionExpander.h</a>.</p>


<p>Referenced by <a href="#a332b64336604f3d94ee5dfcb9e73471a">SCEVExpanderCleaner</a>.</p>

</div>
</div>

### getInsertedIVs() {#ac1b3b1c5a4e00d4820109245f5bc41e2}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">const SmallVectorImpl&lt; WeakVH &gt; &amp; llvm::SCEVExpander::getInsertedIVs ()</td>
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



<p>Definition at line 221 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/transforms/include/llvm/transforms/utils/scalarevolutionexpander-h">ScalarEvolutionExpander.h</a>.</p>

</div>
</div>

### getIVIncOperand() {#aece02adc8e4cc74296bfe410eabe287b}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">Instruction * SCEVExpander::getIVIncOperand (<a href="/web-llvm/docs/api/classes/llvm/instruction">Instruction</a> * IncV, <a href="/web-llvm/docs/api/classes/llvm/instruction">Instruction</a> * InsertPos, bool allowScale)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Return the induction variable increment's IV operand.</p>


<p>getIVIncOperand returns an induction variable increment's induction variable operand.</p>


<p>If allowScale is set, any type of GEP is allowed as long as the nonIV operands dominate InsertPos.</p>


<p>If allowScale is not set, ensure that a GEP increment conforms to one of the simple patterns generated by getAddRecExprPHILiterally and expandAddtoGEP. If the pattern isn't recognized, return NULL.</p>


<p>Declaration at line 274 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/transforms/include/llvm/transforms/utils/scalarevolutionexpander-h">ScalarEvolutionExpander.h</a>, definition at line 742 of file <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/utils/scalarevolutionexpander-cpp">ScalarEvolutionExpander.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/namespaces/llvm/#ac4fc845f5ed92de63cd4474f128f5fc5">llvm::cast</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a02981de53fb6ffd384d39addc4d25f37">llvm::drop_begin</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a22eeee01734061ac1b31ccd994c49eef">llvm::dyn_cast</a>, <a href="/web-llvm/docs/api/classes/llvm/instruction/#ab4e05d690df389b8b1477c90387b575f">llvm::Instruction::getOpcode</a>, <a href="/web-llvm/docs/api/classes/llvm/user/#aa0a2cb1582d1cec317bd205085469ca1">llvm::User::getOperand</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a92ca992e52dddc420f4b069cae06dfbe">llvm::isa</a> and <a href="/web-llvm/docs/api/classes/llvm/user/#a0b931781aa589c6ebe64a76c1447e5b2">llvm::User::operands</a>.</p>


<p>Referenced by <a href="#aa3255071e8195c43058f7e265c54677f">hoistIVInc</a>.</p>

</div>
</div>

### getSE() {#a6210fd650d8883005f3b59a97da555c0}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">ScalarEvolution * llvm::SCEVExpander::getSE ()</td>
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



<p>Definition at line 220 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/transforms/include/llvm/transforms/utils/scalarevolutionexpander-h">ScalarEvolutionExpander.h</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/namespaces/llvm/#ad4f572b4f4bf6aa2dbf10a0bd160280d">llvm::addDiffRuntimeChecks</a>.</p>

</div>
</div>

### hasRelatedExistingExpansion() {#a19bc2d813d4dfa8408b259b197d1e34d}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool SCEVExpander::hasRelatedExistingExpansion (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/scev">SCEV</a> * S, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/instruction">Instruction</a> * At, <a href="/web-llvm/docs/api/classes/llvm/loop">Loop</a> * L)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Determine whether there is an existing expansion of S that can be reused.</p>


<p>This is used to check whether S can be expanded cheaply.</p>


<p>L is a hint which tells in which loop to look for the suitable value.</p>


<p>Note that this function does not perform an exhaustive search. I.e if it didn't find any value it does not mean that there is no such value.</p>


<p>Declaration at line 420 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/transforms/include/llvm/transforms/utils/scalarevolutionexpander-h">ScalarEvolutionExpander.h</a>, definition at line 1809 of file <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/utils/scalarevolutionexpander-cpp">ScalarEvolutionExpander.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/namespaces/llvm/patternmatch/#ad856c036ca10c903c93082a4e784d4a6">llvm::PatternMatch::m_BasicBlock</a>, <a href="/web-llvm/docs/api/namespaces/llvm/patternmatch/#a811d001fa503a556ac2a48d64366500f">llvm::PatternMatch::m_Br</a>, <a href="/web-llvm/docs/api/namespaces/llvm/patternmatch/#ab86c85b47e09489dcda68fd91d082d77">llvm::PatternMatch::m_ICmp</a>, <a href="/web-llvm/docs/api/namespaces/llvm/patternmatch/#a2adca0e23c974dbb32019dccb22547bc">llvm::PatternMatch::m_Instruction</a> and <a href="/web-llvm/docs/api/namespaces/llvm/patternmatch/#a25d956d9e0beadd47ce4bc255dfa811d">llvm::PatternMatch::match</a>.</p>

</div>
</div>

### hoistIVInc() {#aa3255071e8195c43058f7e265c54677f}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool SCEVExpander::hoistIVInc (<a href="/web-llvm/docs/api/classes/llvm/instruction">Instruction</a> * IncV, <a href="/web-llvm/docs/api/classes/llvm/instruction">Instruction</a> * InsertPos, bool RecomputePoisonFlags=false)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Utility for hoisting <span class="doxyComputerOutput">IncV</span> (with all subexpressions requried for its computation) before <span class="doxyComputerOutput">InsertPos</span>.</p>


<p>hoistStep - Attempt to hoist a simple IV increment above InsertPos to make it available to other uses in this loop.</p>


<p>If <span class="doxyComputerOutput">RecomputePoisonFlags</span> is set, drops all poison-generating flags from instructions being hoisted and tries to re-infer them in the new location. It should be used when we are going to introduce a new use in the new position that didn't exist before, and may trigger new UB in case of poison.</p>


<p>Recursively hoist any operands, until we reach a value that dominates InsertPos.</p>


<p>Declaration at line 283 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/transforms/include/llvm/transforms/utils/scalarevolutionexpander-h">ScalarEvolutionExpander.h</a>, definition at line 802 of file <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/utils/scalarevolutionexpander-cpp">ScalarEvolutionExpander.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/namespaces/llvm/#ac4fc845f5ed92de63cd4474f128f5fc5">llvm::cast</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a22eeee01734061ac1b31ccd994c49eef">llvm::dyn_cast</a>, <a href="/web-llvm/docs/api/classes/llvm/scev/#af43000d4dcb7d6d63cb6e36933ed3f6fa2f7a8775a783f7ea3ad24b3f9cb5d949">llvm::SCEV::FlagNSW</a>, <a href="/web-llvm/docs/api/classes/llvm/scev/#af43000d4dcb7d6d63cb6e36933ed3f6faafb62cd6afdc004ef6e8a1f6288eb382">llvm::SCEV::FlagNUW</a>, <a href="/web-llvm/docs/api/classes/llvm/ilist-node-impl/#af719fc783be6589465137d997701a432">llvm::ilist_node_impl&lt; OptionsT &gt;::getIterator</a>, <a href="#aece02adc8e4cc74296bfe410eabe287b">getIVIncOperand</a>, <a href="/web-llvm/docs/api/classes/llvm/ilist-detail/node-parent-access/#a7e19e7508415378ad9523e0339b23e22">llvm::ilist_detail::node_parent_access&lt; NodeTy, ParentTy &gt;::getParent</a>, <a href="/web-llvm/docs/api/files/lib/lib/support/md5-cpp/#ac0eafdc9ee161b71e7af98af736952fd">I</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a92ca992e52dddc420f4b069cae06dfbe">llvm::isa</a>, <a href="/web-llvm/docs/api/classes/llvm/scalarevolution/#adfe987ba0fa56ab9ecdb606c2462b6b9">llvm::ScalarEvolution::maskFlags</a>, <a href="/web-llvm/docs/api/classes/llvm/smallvectortemplatebase/#af42bfbc067df27c19ee2fc859df58799">llvm::SmallVectorTemplateBase&lt; T, bool &gt;::push_back</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a6b0ac1fa4f05de76413c5e0ca6334035">llvm::reverse</a>, <a href="/web-llvm/docs/api/classes/llvm/instruction/#a4166b451a572b1e5d3fea7250af53653">llvm::Instruction::setHasNoSignedWrap</a> and <a href="/web-llvm/docs/api/classes/llvm/instruction/#a0c03b71c79206ec41270dc3788183e0d">llvm::Instruction::setHasNoUnsignedWrap</a>.</p>

</div>
</div>

### isHighCostExpansion() {#a5a1f8f7e12808825560c7a10ec2f970b}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool llvm::SCEVExpander::isHighCostExpansion (<a href="/web-llvm/docs/api/classes/llvm/arrayref">ArrayRef</a>&lt; <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/scev">SCEV</a> * &gt; Exprs, <a href="/web-llvm/docs/api/classes/llvm/loop">Loop</a> * L, unsigned Budget, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/targettransforminfo">TargetTransformInfo</a> * TTI, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/instruction">Instruction</a> * At)</td>
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

<p>Return true for expressions that can't be evaluated at runtime within given <b>Budget</b>.</p>


<p><span class="doxyComputerOutput">At</span> is a parameter which specifies point in code where user is going to expand these expressions. Sometimes this knowledge can lead to a less pessimistic cost estimation.</p>


<p>Definition at line 250 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/transforms/include/llvm/transforms/utils/scalarevolutionexpander-h">ScalarEvolutionExpander.h</a>.</p>


<p>References <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/silowercontrolflow-cpp/#a4868c5d81c5ccc98c47aeab6244346a0">assert</a>, <a href="/web-llvm/docs/api/classes/llvm/smallvectorimpl/#a396fcfee6914c76974b73c3d203da6a5">llvm::SmallVectorImpl&lt; T &gt;::emplace_back</a>, <a href="/web-llvm/docs/api/classes/llvm/smallvectortemplatecommon/#ad9a3c7bc26b130377bbafc170b5f88a2">llvm::SmallVectorTemplateCommon&lt; T, typename &gt;::empty</a>, <a href="/web-llvm/docs/api/classes/llvm/smallvectorimpl/#a0c8ffe664a36e30d49c84d0aded2fe08">llvm::SmallVectorImpl&lt; T &gt;::pop_back_val</a> and <a href="/web-llvm/docs/api/classes/llvm/targettransforminfo/#ac44f6b9fdbb5f9cc199f8329cb0b272cae46c9eecc49bd2dc253c607e78a0fb86">llvm::TargetTransformInfo::TCC_Basic</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/scalar/looptermfold-cpp/#a0e67dc55f94f7419d24a39fa5b79c42f">canFoldTermCondOfLoop</a> and <a href="/web-llvm/docs/api/namespaces/llvm/#acd628d451ca9d9b021876d59f46e670b">llvm::UnrollRuntimeLoopRemainder</a>.</p>

</div>
</div>

### isInsertedInstruction() {#aab1d5fe8452ef0d6995904efe86ef9ff}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool llvm::SCEVExpander::isInsertedInstruction (<a href="/web-llvm/docs/api/classes/llvm/instruction">Instruction</a> * I)</td>
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

<p>Return true if the specified instruction was inserted by the code rewriter.</p>


<p>If so, the client should not modify the instruction. Note that this also includes instructions re-used during expansion.</p>


<p>Definition at line 407 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/transforms/include/llvm/transforms/utils/scalarevolutionexpander-h">ScalarEvolutionExpander.h</a>.</p>


<p>Reference <a href="/web-llvm/docs/api/files/lib/lib/support/md5-cpp/#ac0eafdc9ee161b71e7af98af736952fd">I</a>.</p>


<p>Referenced by <a href="#af99566d9ade6807a99ccf61cb126e1be">findInsertPointAfter</a>.</p>

</div>
</div>

### isSafeToExpand() {#a3b8edb4179c8a762f5ab29e1dd613c3a}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool SCEVExpander::isSafeToExpand (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/scev">SCEV</a> * S)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Return true if the given expression is safe to expand in the sense that all materialized values are safe to speculate anywhere their operands are defined, and the expander is capable of expanding the expression.</p>

<p>Declaration at line 303 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/transforms/include/llvm/transforms/utils/scalarevolutionexpander-h">ScalarEvolutionExpander.h</a>, definition at line 2353 of file <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/utils/scalarevolutionexpander-cpp">ScalarEvolutionExpander.cpp</a>.</p>


<p>Reference <a href="/web-llvm/docs/api/namespaces/llvm/#a002c7b1beef8b58691fe7aa42ffa2fe7">llvm::visitAll</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/scalar/looptermfold-cpp/#a0e67dc55f94f7419d24a39fa5b79c42f">canFoldTermCondOfLoop</a>, <a href="#a5c94af409fdce59362329aa65584482d">isSafeToExpandAt</a> and <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/scalar/looptermfold-cpp/#ae78c54dce6798892e47ca90660f9a8f6">RunTermFold</a>.</p>

</div>
</div>

### isSafeToExpandAt() {#a5c94af409fdce59362329aa65584482d}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool SCEVExpander::isSafeToExpandAt (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/scev">SCEV</a> * S, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/instruction">Instruction</a> * InsertionPoint)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Return true if the given expression is safe to expand in the sense that all materialized values are defined and safe to speculate at the specified location and their operands are defined at this location.</p>

<p>Declaration at line 308 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/transforms/include/llvm/transforms/utils/scalarevolutionexpander-h">ScalarEvolutionExpander.h</a>, definition at line 2359 of file <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/utils/scalarevolutionexpander-cpp">ScalarEvolutionExpander.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/namespaces/llvm/#a22eeee01734061ac1b31ccd994c49eef">llvm::dyn_cast</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#acd1cd968cb420c82d70926920fcdc7d7">llvm::is_contained</a> and <a href="#a3b8edb4179c8a762f5ab29e1dd613c3a">isSafeToExpand</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/classes/llvm/loopconstrainer/#af041772a16751b1c52d52ae08cd5046d">llvm::LoopConstrainer::run</a>.</p>

</div>
</div>

### replaceCongruentIVs() {#a635463dc5e146744799163c2f820e51b}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">unsigned SCEVExpander::replaceCongruentIVs (<a href="/web-llvm/docs/api/classes/llvm/loop">Loop</a> * L, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/dominatortree">DominatorTree</a> * DT, <a href="/web-llvm/docs/api/classes/llvm/smallvectorimpl">SmallVectorImpl</a>&lt; <a href="/web-llvm/docs/api/classes/llvm/weaktrackingvh">WeakTrackingVH</a> &gt; &amp; DeadInsts, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/targettransforminfo">TargetTransformInfo</a> * TTI=nullptr)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>replace congruent phis with their most canonical representative.</p>


<p>replaceCongruentIVs - <a href="/web-llvm/docs/api/namespaces/llvm/check">Check</a> for congruent phis in this loop header and replace them with their most canonical representative.</p>


<p>Return the number of phis eliminated.</p>


<p>Return the number of phis eliminated.</p>


<p>This does not depend on any <a href="/web-llvm/docs/api/classes/llvm/scevexpander">SCEVExpander</a> state but should be used in the same context that <a href="/web-llvm/docs/api/classes/llvm/scevexpander">SCEVExpander</a> is used.</p>


<p>Declaration at line 296 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/transforms/include/llvm/transforms/utils/scalarevolutionexpander-h">ScalarEvolutionExpander.h</a>, definition at line 1711 of file <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/utils/scalarevolutionexpander-cpp">ScalarEvolutionExpander.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/classes/llvm/smallvectortemplatecommon/#acd9e771a3296c6b24146955754620557">llvm::SmallVectorTemplateCommon&lt; T, typename &gt;::back</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a7c46c742c31be54870e2038048e6b391">llvm::dbgs</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a22eeee01734061ac1b31ccd994c49eef">llvm::dyn_cast</a>, <a href="/web-llvm/docs/api/classes/llvm/smallvectorimpl/#a396fcfee6914c76974b73c3d203da6a5">llvm::SmallVectorImpl&lt; T &gt;::emplace_back</a>, <a href="/web-llvm/docs/api/classes/llvm/value/#a0344a49526443edf90cc0aef3abd3337">llvm::Value::getType</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a92ca992e52dddc420f4b069cae06dfbe">llvm::isa</a>, <a href="/web-llvm/docs/api/classes/llvm/type/#a3b996fbf8458aafffc86cb98a68d0a47">llvm::Type::isPointerTy</a>, <a href="/web-llvm/docs/api/classes/llvm/smallvectortemplatebase/#af42bfbc067df27c19ee2fc859df58799">llvm::SmallVectorTemplateBase&lt; T, bool &gt;::push_back</a>, <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/utils/scalarevolutionexpander-cpp/#ad36bc86b1f4a0066ce1e30ca08b09d33">SCEV_DEBUG_WITH_TYPE</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a57feb935aaafd1bd4bfbb8dc56ad2129">llvm::simplifyInstruction</a> and <a href="/web-llvm/docs/api/namespaces/llvm/#a076f93c387f454f0db13d4bc7d4e7f9c">llvm::stable_sort</a>.</p>

</div>
</div>

### setChainedPhi() {#a346ef44d7050fbf42b5d871ba5006b80}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void llvm::SCEVExpander::setChainedPhi (<a href="/web-llvm/docs/api/classes/llvm/phinode">PHINode</a> * PN)</td>
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



<p>Definition at line 411 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/transforms/include/llvm/transforms/utils/scalarevolutionexpander-h">ScalarEvolutionExpander.h</a>.</p>

</div>
</div>

### SetCurrentDebugLocation() {#ab1ef4391900efc4cf934806ea7d43166}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void llvm::SCEVExpander::SetCurrentDebugLocation (<a href="/web-llvm/docs/api/classes/llvm/debugloc">DebugLoc</a> L)</td>
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

<p>Set location information used by debugging information.</p>

<p>Definition at line 395 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/transforms/include/llvm/transforms/utils/scalarevolutionexpander-h">ScalarEvolutionExpander.h</a>.</p>

</div>
</div>

### setInsertPoint() {#afb583e40ce2835c2afa2e05e84fd5b87}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void llvm::SCEVExpander::setInsertPoint (<a href="/web-llvm/docs/api/classes/llvm/instruction">Instruction</a> * IP)</td>
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

<p>Set the current insertion point.</p>


<p>This is useful if multiple calls to <a href="#ac711b5659270bd9e66b8f38ec481260c">expandCodeFor()</a> are going to be made with the same insert point and the insert point may be moved during one of the expansions (e.g. if the insert point is not a block terminator).</p>


<p>Definition at line 381 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/transforms/include/llvm/transforms/utils/scalarevolutionexpander-h">ScalarEvolutionExpander.h</a>.</p>


<p>Reference <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/silowercontrolflow-cpp/#a4868c5d81c5ccc98c47aeab6244346a0">assert</a>.</p>


<p>Referenced by <a href="#ac711b5659270bd9e66b8f38ec481260c">expandCodeFor</a>.</p>

</div>
</div>

### setInsertPoint() {#a55844f6b9919e935ae52085f77eff21f}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void llvm::SCEVExpander::setInsertPoint (<a href="/web-llvm/docs/api/classes/llvm/basicblock/#a98c0a84a5dfa8bce341c829709f171e5">BasicBlock::iterator</a> IP)</td>
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



<p>Definition at line 386 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/transforms/include/llvm/transforms/utils/scalarevolutionexpander-h">ScalarEvolutionExpander.h</a>.</p>

</div>
</div>

### setIVIncInsertPos() {#abb16499dadbe473c428b55f72850ef97}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void llvm::SCEVExpander::setIVIncInsertPos (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/loop">Loop</a> * L, <a href="/web-llvm/docs/api/classes/llvm/instruction">Instruction</a> * Pos)</td>
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

<p>Set the current IV increment loop and position.</p>

<p>Definition at line 346 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/transforms/include/llvm/transforms/utils/scalarevolutionexpander-h">ScalarEvolutionExpander.h</a>.</p>


<p>Reference <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/silowercontrolflow-cpp/#a4868c5d81c5ccc98c47aeab6244346a0">assert</a>.</p>

</div>
</div>

### setPostInc() {#aaca0b4b6c0a7f9a36f043b993177e03e}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void llvm::SCEVExpander::setPostInc (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/namespaces/llvm/#ac765465998d0f34ed6123631bda54fab">PostIncLoopSet</a> &amp; L)</td>
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

<p>Enable post-inc expansion for addrecs referring to the given loops.</p>


<p>Post-inc expansion is only supported in non-canonical mode.</p>


<p>Definition at line 355 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/transforms/include/llvm/transforms/utils/scalarevolutionexpander-h">ScalarEvolutionExpander.h</a>.</p>


<p>Reference <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/silowercontrolflow-cpp/#a4868c5d81c5ccc98c47aeab6244346a0">assert</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Private Member Functions

### expand() {#a69efede7551620cf802005ca401b1bf0}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">Value * SCEVExpander::expand (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/scev">SCEV</a> * S)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Declaration at line 469 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/transforms/include/llvm/transforms/utils/scalarevolutionexpander-h">ScalarEvolutionExpander.h</a>, definition at line 1502 of file <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/utils/scalarevolutionexpander-cpp">ScalarEvolutionExpander.cpp</a>.</p>

</div>
</div>

### expand() {#a8916a99b2298f31251b3ddb4be82af23}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">Value * llvm::SCEVExpander::expand (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/scev">SCEV</a> * S, <a href="/web-llvm/docs/api/classes/llvm/basicblock/#a98c0a84a5dfa8bce341c829709f171e5">BasicBlock::iterator</a> I)</td>
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



<p>Definition at line 470 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/transforms/include/llvm/transforms/utils/scalarevolutionexpander-h">ScalarEvolutionExpander.h</a>.</p>

</div>
</div>

### expand() {#abefaa79a0a0cc0eccfde0a2c08f7244d}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">Value * llvm::SCEVExpander::expand (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/scev">SCEV</a> * S, <a href="/web-llvm/docs/api/classes/llvm/instruction">Instruction</a> * I)</td>
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



<p>Definition at line 474 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/transforms/include/llvm/transforms/utils/scalarevolutionexpander-h">ScalarEvolutionExpander.h</a>.</p>

</div>
</div>

### expandAddRecExprLiterally() {#a194469ade12ed18650764bea85aa3b70}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">Value * SCEVExpander::expandAddRecExprLiterally (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/scevaddrecexpr">SCEVAddRecExpr</a> * S)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Declaration at line 525 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/transforms/include/llvm/transforms/utils/scalarevolutionexpander-h">ScalarEvolutionExpander.h</a>, definition at line 1143 of file <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/utils/scalarevolutionexpander-cpp">ScalarEvolutionExpander.cpp</a>.</p>

</div>
</div>

### expandAddToGEP() {#a567935fdae75b6acc865c1b66aa4311a}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">Value * SCEVExpander::expandAddToGEP (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/scev">SCEV</a> * Offset, <a href="/web-llvm/docs/api/classes/llvm/value">Value</a> * V, <a href="/web-llvm/docs/api/classes/llvm/scev/#af43000d4dcb7d6d63cb6e36933ed3f6f">SCEV::NoWrapFlags</a> Flags)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Expand a <a href="/web-llvm/docs/api/classes/llvm/scevaddexpr">SCEVAddExpr</a> with a pointer type into a GEP instead of using ptrtoint+arithmetic+inttoptr.</p>


<p>expandAddToGEP - Expand an addition expression with a pointer type into a GEP instead of using ptrtoint+arithmetic+inttoptr.</p>


<p>This helps BasicAliasAnalysis and other passes analyze the result. See the rules for getelementptr vs. inttoptr in <a href="http://llvm.org/docs/LangRef.html#pointeraliasing">http://llvm.org/docs/LangRef.html#pointeraliasing</a> for details.</p>


<p>Design note: The correctness of using getelementptr here depends on <a href="/web-llvm/docs/api/classes/llvm/scalarevolution">ScalarEvolution</a> not recognizing inttoptr and ptrtoint operators, as they may introduce pointer arithmetic which may not be safely converted into getelementptr.</p>


<p>Design note: It might seem desirable for this function to be more loop-aware. If some of the indices are loop-invariant while others aren't, it might seem desirable to emit multiple GEPs, keeping the loop-invariant portions of the overall computation outside the loop. However, there are a few reasons this is not done here. Hoisting simple arithmetic is a low-level optimization that often isn't very important until late in the optimization process. In fact, passes like InstructionCombining will combine GEPs, even if it means pushing loop-invariant computation down into loops, so even if the GEPs were split here, the work would quickly be undone. The LoopStrengthReduction pass, which is usually run quite late (and after the last InstructionCombining pass), takes care of hoisting loop-invariant portions of expressions, after considering what can be folded using target addressing modes.</p>


<p>Declaration at line 460 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/transforms/include/llvm/transforms/utils/scalarevolutionexpander-h">ScalarEvolutionExpander.h</a>, definition at line 360 of file <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/utils/scalarevolutionexpander-cpp">ScalarEvolutionExpander.cpp</a>.</p>

</div>
</div>

### expandIVInc() {#ac9d886f8773a9b85d9a9cf760ed8fe85}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">Value * SCEVExpander::expandIVInc (<a href="/web-llvm/docs/api/classes/llvm/phinode">PHINode</a> * PN, <a href="/web-llvm/docs/api/classes/llvm/value">Value</a> * StepV, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/loop">Loop</a> * L, bool useSubtract)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>expandIVInc - Expand an IV increment at Builder's current InsertPos.</p>


<p>Typically this is the LatchBlock terminator or IVIncInsertPos, but we may need to materialize IV increments elsewhere to handle difficult situations.</p>


<p>Declaration at line 529 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/transforms/include/llvm/transforms/utils/scalarevolutionexpander-h">ScalarEvolutionExpander.h</a>, definition at line 883 of file <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/utils/scalarevolutionexpander-cpp">ScalarEvolutionExpander.cpp</a>.</p>

</div>
</div>

### expandMinMaxExpr() {#ad35d57cfffa31ac0df7ef469f2febe27}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">Value * SCEVExpander::expandMinMaxExpr (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/scevnaryexpr">SCEVNAryExpr</a> * S, <a href="/web-llvm/docs/api/namespaces/llvm/intrinsic/#a80add6b3b1cdaec560907995127adc16">Intrinsic::ID</a> IntrinID, <a href="/web-llvm/docs/api/classes/llvm/twine">Twine</a> Name, bool IsSequential=false)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Declaration at line 482 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/transforms/include/llvm/transforms/utils/scalarevolutionexpander-h">ScalarEvolutionExpander.h</a>, definition at line 1390 of file <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/utils/scalarevolutionexpander-cpp">ScalarEvolutionExpander.cpp</a>.</p>

</div>
</div>

### FindValueInExprValueMap() {#a467dca4de216e2f1beae85be93ec2141}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">Value * SCEVExpander::FindValueInExprValueMap (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/scev">SCEV</a> * S, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/instruction">Instruction</a> * InsertPt, <a href="/web-llvm/docs/api/classes/llvm/smallvectorimpl">SmallVectorImpl</a>&lt; <a href="/web-llvm/docs/api/classes/llvm/instruction">Instruction</a> * &gt; &amp; DropPoisonGeneratingInsts)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Find a previous <a href="/web-llvm/docs/api/classes/llvm/value">Value</a> in ExprValueMap for expand.</p>


<p>DropPoisonGeneratingInsts is populated with instructions for which poison-generating flags must be dropped if the value is reused.</p>


<p>Declaration at line 465 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/transforms/include/llvm/transforms/utils/scalarevolutionexpander-h">ScalarEvolutionExpander.h</a>, definition at line 1462 of file <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/utils/scalarevolutionexpander-cpp">ScalarEvolutionExpander.cpp</a>.</p>

</div>
</div>

### fixupInsertPoints() {#a64986ad1d7ce9af41f0d780e8c0d6e67}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void SCEVExpander::fixupInsertPoints (<a href="/web-llvm/docs/api/classes/llvm/instruction">Instruction</a> * I)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>If the insert point of the current builder or any of the builders on the stack of saved builders has 'I' as its insert point, update it to point to the instruction after 'I'.</p>


<p>This is intended to be used when the instruction 'I' is being moved. If this fixup is not done and 'I' is moved to a different block, the inconsistent insert point (with a mismatched <a href="/web-llvm/docs/api/classes/llvm/instruction">Instruction</a> and Block) can lead to an instruction being inserted in a block other than its parent.</p>


<p>Declaration at line 532 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/transforms/include/llvm/transforms/utils/scalarevolutionexpander-h">ScalarEvolutionExpander.h</a>, definition at line 789 of file <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/utils/scalarevolutionexpander-cpp">ScalarEvolutionExpander.cpp</a>.</p>

</div>
</div>

### fixupLCSSAFormFor() {#a234e6cfb2c2b3424edfe16fabc93fd42}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">Value * SCEVExpander::fixupLCSSAFormFor (<a href="/web-llvm/docs/api/classes/llvm/value">Value</a> * V)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Create LCSSA PHIs for <span class="doxyComputerOutput">V</span>, if it is required for uses at the Builder's current insertion point.</p>

<p>Declaration at line 536 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/transforms/include/llvm/transforms/utils/scalarevolutionexpander-h">ScalarEvolutionExpander.h</a>, definition at line 2257 of file <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/utils/scalarevolutionexpander-cpp">ScalarEvolutionExpander.cpp</a>.</p>

</div>
</div>

### getAddRecExprPHILiterally() {#a304441fb9d5b724603ecf7dab9edfc4f}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">PHINode * SCEVExpander::getAddRecExprPHILiterally (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/scevaddrecexpr">SCEVAddRecExpr</a> * Normalized, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/loop">Loop</a> * L, <a href="/web-llvm/docs/api/classes/llvm/type">Type</a> *&amp; TruncTy, bool &amp; InvertStep)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>getAddRecExprPHILiterally - Helper for expandAddRecExprLiterally.</p>


<p>Expand the base addrec, which is the addrec without any non-loop-dominating values, and return the PHI.</p>


<p>Declaration at line 526 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/transforms/include/llvm/transforms/utils/scalarevolutionexpander-h">ScalarEvolutionExpander.h</a>, definition at line 965 of file <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/utils/scalarevolutionexpander-cpp">ScalarEvolutionExpander.cpp</a>.</p>

</div>
</div>

### getContext() {#a2ea3589aabbc830e5906cb2b2ff673c2}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">LLVMContext &amp; llvm::SCEVExpander::getContext ()</td>
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



<p>Definition at line 429 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/transforms/include/llvm/transforms/utils/scalarevolutionexpander-h">ScalarEvolutionExpander.h</a>.</p>

</div>
</div>

### GetOptimalInsertionPointForCastOf() {#a7dea7b651c5214c21829ba40ef3e15c5}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">BasicBlock::iterator SCEVExpander::GetOptimalInsertionPointForCastOf (<a href="/web-llvm/docs/api/classes/llvm/value">Value</a> * V)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>We want to cast <span class="doxyComputerOutput">V</span>. What would be the best place for such a cast?</p>

<p>Declaration at line 446 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/transforms/include/llvm/transforms/utils/scalarevolutionexpander-h">ScalarEvolutionExpander.h</a>, definition at line 175 of file <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/utils/scalarevolutionexpander-cpp">ScalarEvolutionExpander.cpp</a>.</p>

</div>
</div>

### getRelevantLoop() {#ac97e7b4527246d0d493542b6fc43d1ea}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">const Loop * SCEVExpander::getRelevantLoop (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/scev">SCEV</a> * S)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Determine the most "relevant" loop for the given <a href="/web-llvm/docs/api/classes/llvm/scev">SCEV</a>.</p>


<p>getRelevantLoop - Get the most relevant loop associated with the given expression, according to PickMostRelevantLoop.</p>


<p>Declaration at line 480 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/transforms/include/llvm/transforms/utils/scalarevolutionexpander-h">ScalarEvolutionExpander.h</a>, definition at line 432 of file <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/utils/scalarevolutionexpander-cpp">ScalarEvolutionExpander.cpp</a>.</p>

</div>
</div>

### InsertBinop() {#a8a8fe26d9e9ce5a24e045401e9ef1fba}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">Value * SCEVExpander::InsertBinop (<a href="/web-llvm/docs/api/classes/llvm/instruction/#ac26154a24f393f523c87cc5f8239f36c">Instruction::BinaryOps</a> Opcode, <a href="/web-llvm/docs/api/classes/llvm/value">Value</a> * LHS, <a href="/web-llvm/docs/api/classes/llvm/value">Value</a> * RHS, <a href="/web-llvm/docs/api/classes/llvm/scev/#af43000d4dcb7d6d63cb6e36933ed3f6f">SCEV::NoWrapFlags</a> Flags, bool IsSafeToHoist)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Insert the specified binary operator, doing a small amount of work to avoid inserting an obviously redundant operation, and hoisting to an outer loop when the opportunity is there and it is safe.</p>


<p>InsertBinop - Insert the specified binary operator, doing a small amount of work to avoid inserting an obviously redundant operation, and hoisting to an outer loop when the opportunity is there and it is safe.</p>


<p>Declaration at line 442 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/transforms/include/llvm/transforms/utils/scalarevolutionexpander-h">ScalarEvolutionExpander.h</a>, definition at line 261 of file <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/utils/scalarevolutionexpander-cpp">ScalarEvolutionExpander.cpp</a>.</p>

</div>
</div>

### InsertNoopCastOfTo() {#a6546e8e825e04691c207c67f6bc6ea18}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">Value * SCEVExpander::InsertNoopCastOfTo (<a href="/web-llvm/docs/api/classes/llvm/value">Value</a> * V, <a href="/web-llvm/docs/api/classes/llvm/type">Type</a> * Ty)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Insert a cast of V to the specified type, which must be possible with a noop cast, doing what we can to share the casts.</p>


<p>InsertNoopCastOfTo - Insert a cast of V to the specified type, which must be possible with a noop cast, doing what we can to share the casts.</p>


<p>Declaration at line 456 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/transforms/include/llvm/transforms/utils/scalarevolutionexpander-h">ScalarEvolutionExpander.h</a>, definition at line 205 of file <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/utils/scalarevolutionexpander-cpp">ScalarEvolutionExpander.cpp</a>.</p>

</div>
</div>

### isExpandedAddRecExprPHI() {#a45c836c43811b79ea3963f5ac552836c}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool SCEVExpander::isExpandedAddRecExprPHI (<a href="/web-llvm/docs/api/classes/llvm/phinode">PHINode</a> * PN, <a href="/web-llvm/docs/api/classes/llvm/instruction">Instruction</a> * IncV, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/loop">Loop</a> * L)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Determine if this cyclic phi is in a form that would have been generated by LSR.</p>


<p>We don't care if the phi was actually expanded in this pass, as long as it is in a low-cost form, for example, no implied multiplication. This should match any patterns generated by getAddRecExprPHILiterally and expandAddtoGEP.</p>


<p>Declaration at line 523 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/transforms/include/llvm/transforms/utils/scalarevolutionexpander-h">ScalarEvolutionExpander.h</a>, definition at line 869 of file <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/utils/scalarevolutionexpander-cpp">ScalarEvolutionExpander.cpp</a>.</p>

</div>
</div>

### isHighCostExpansionHelper() {#a5beeb02a287212152542a26ff6db5d3d}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool SCEVExpander::isHighCostExpansionHelper (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/structs/llvm/scevoperand">SCEVOperand</a> &amp; WorkItem, <a href="/web-llvm/docs/api/classes/llvm/loop">Loop</a> * L, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/instruction">Instruction</a> &amp; At, <a href="/web-llvm/docs/api/classes/llvm/instructioncost">InstructionCost</a> &amp; Cost, unsigned Budget, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/targettransforminfo">TargetTransformInfo</a> &amp; TTI, <a href="/web-llvm/docs/api/classes/llvm/smallptrsetimpl">SmallPtrSetImpl</a>&lt; <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/scev">SCEV</a> * &gt; &amp; Processed, <a href="/web-llvm/docs/api/classes/llvm/smallvectorimpl">SmallVectorImpl</a>&lt; <a href="/web-llvm/docs/api/structs/llvm/scevoperand">SCEVOperand</a> &gt; &amp; Worklist)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Recursive helper function for isHighCostExpansion.</p>

<p>Declaration at line 432 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/transforms/include/llvm/transforms/utils/scalarevolutionexpander-h">ScalarEvolutionExpander.h</a>, definition at line 1976 of file <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/utils/scalarevolutionexpander-cpp">ScalarEvolutionExpander.cpp</a>.</p>

</div>
</div>

### isNormalAddRecExprPHI() {#a79250227f2ba8c48c6a4d6375235e4b4}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool SCEVExpander::isNormalAddRecExprPHI (<a href="/web-llvm/docs/api/classes/llvm/phinode">PHINode</a> * PN, <a href="/web-llvm/docs/api/classes/llvm/instruction">Instruction</a> * IncV, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/loop">Loop</a> * L)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Determine if this is a well-behaved chain of instructions leading back to the PHI.</p>


<p>If so, it may be reused by expanded expressions.</p>


<p>Declaration at line 521 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/transforms/include/llvm/transforms/utils/scalarevolutionexpander-h">ScalarEvolutionExpander.h</a>, definition at line 705 of file <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/utils/scalarevolutionexpander-cpp">ScalarEvolutionExpander.cpp</a>.</p>

</div>
</div>

### rememberFlags() {#aa5f25e2fa644adb54fc9c90d6eebfd53}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void SCEVExpander::rememberFlags (<a href="/web-llvm/docs/api/classes/llvm/instruction">Instruction</a> * I)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Declaration at line 519 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/transforms/include/llvm/transforms/utils/scalarevolutionexpander-h">ScalarEvolutionExpander.h</a>, definition at line 1611 of file <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/utils/scalarevolutionexpander-cpp">ScalarEvolutionExpander.cpp</a>.</p>

</div>
</div>

### rememberInstruction() {#a6331d66bb0cafa41e3ae0efe90dbcf2f}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void SCEVExpander::rememberInstruction (<a href="/web-llvm/docs/api/classes/llvm/value">Value</a> * I)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Declaration at line 517 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/transforms/include/llvm/transforms/utils/scalarevolutionexpander-h">ScalarEvolutionExpander.h</a>, definition at line 1601 of file <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/utils/scalarevolutionexpander-cpp">ScalarEvolutionExpander.cpp</a>.</p>

</div>
</div>

### replaceCongruentIVInc() {#a249cad3acbfbd79f098428a00be02b27}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void SCEVExpander::replaceCongruentIVInc (<a href="/web-llvm/docs/api/classes/llvm/phinode">PHINode</a> *&amp; Phi, <a href="/web-llvm/docs/api/classes/llvm/phinode">PHINode</a> *&amp; OrigPhi, <a href="/web-llvm/docs/api/classes/llvm/loop">Loop</a> * L, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/dominatortree">DominatorTree</a> * DT, <a href="/web-llvm/docs/api/classes/llvm/smallvectorimpl">SmallVectorImpl</a>&lt; <a href="/web-llvm/docs/api/classes/llvm/weaktrackingvh">WeakTrackingVH</a> &gt; &amp; DeadInsts)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Replace congruent phi increments with their most canonical representative.</p>


<p>May swap <span class="doxyComputerOutput">Phi</span> and <span class="doxyComputerOutput">OrigPhi</span>, if <span class="doxyComputerOutput">Phi</span> is more canonical, due to its increment.</p>


<p>Declaration at line 541 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/transforms/include/llvm/transforms/utils/scalarevolutionexpander-h">ScalarEvolutionExpander.h</a>, definition at line 1616 of file <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/utils/scalarevolutionexpander-cpp">ScalarEvolutionExpander.cpp</a>.</p>

</div>
</div>

### ReuseOrCreateCast() {#a00becc53359635fb5eaff2e972bc4de1}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">Value * SCEVExpander::ReuseOrCreateCast (<a href="/web-llvm/docs/api/classes/llvm/value">Value</a> * V, <a href="/web-llvm/docs/api/classes/llvm/type">Type</a> * Ty, <a href="/web-llvm/docs/api/classes/llvm/instruction/#afa0b2fa29ba074f2b6ec9ac11163f2d9">Instruction::CastOps</a> Op, <a href="/web-llvm/docs/api/classes/llvm/basicblock/#a98c0a84a5dfa8bce341c829709f171e5">BasicBlock::iterator</a> IP)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Arrange for there to be a cast of V to Ty at IP, reusing an existing cast if a suitable one exists, moving an existing cast if a suitable one exists but isn't in the right place, or creating a new one.</p>


<p>ReuseOrCreateCast - Arrange for there to be a cast of V to Ty at IP, reusing an existing cast if a suitable one (= dominating IP) exists, or creating a new one.</p>


<p>Declaration at line 451 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/transforms/include/llvm/transforms/utils/scalarevolutionexpander-h">ScalarEvolutionExpander.h</a>, definition at line 98 of file <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/utils/scalarevolutionexpander-cpp">ScalarEvolutionExpander.cpp</a>.</p>

</div>
</div>

### visitAddExpr() {#ab05c7beecf728417d5575f52c4363a5f}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">Value * SCEVExpander::visitAddExpr (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/scevaddexpr">SCEVAddExpr</a> * S)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Declaration at line 497 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/transforms/include/llvm/transforms/utils/scalarevolutionexpander-h">ScalarEvolutionExpander.h</a>, definition at line 510 of file <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/utils/scalarevolutionexpander-cpp">ScalarEvolutionExpander.cpp</a>.</p>

</div>
</div>

### visitAddRecExpr() {#a6e67c29f8e93322975735619cc1db892}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">Value * SCEVExpander::visitAddRecExpr (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/scevaddrecexpr">SCEVAddRecExpr</a> * S)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Declaration at line 503 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/transforms/include/llvm/transforms/utils/scalarevolutionexpander-h">ScalarEvolutionExpander.h</a>, definition at line 1233 of file <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/utils/scalarevolutionexpander-cpp">ScalarEvolutionExpander.cpp</a>.</p>

</div>
</div>

### visitConstant() {#a3509e77c195527afc04aa5c101055826}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">Value * llvm::SCEVExpander::visitConstant (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/scevconstant">SCEVConstant</a> * S)</td>
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



<p>Definition at line 485 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/transforms/include/llvm/transforms/utils/scalarevolutionexpander-h">ScalarEvolutionExpander.h</a>.</p>

</div>
</div>

### visitMulExpr() {#a4da0f47660e915dce9913e42ff5c5cad}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">Value * SCEVExpander::visitMulExpr (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/scevmulexpr">SCEVMulExpr</a> * S)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Declaration at line 499 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/transforms/include/llvm/transforms/utils/scalarevolutionexpander-h">ScalarEvolutionExpander.h</a>, definition at line 582 of file <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/utils/scalarevolutionexpander-cpp">ScalarEvolutionExpander.cpp</a>.</p>

</div>
</div>

### visitPtrToIntExpr() {#a915ebbc1983b769a69936da9e4d9a8dd}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">Value * SCEVExpander::visitPtrToIntExpr (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/scevptrtointexpr">SCEVPtrToIntExpr</a> * S)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Declaration at line 489 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/transforms/include/llvm/transforms/utils/scalarevolutionexpander-h">ScalarEvolutionExpander.h</a>, definition at line 1368 of file <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/utils/scalarevolutionexpander-cpp">ScalarEvolutionExpander.cpp</a>.</p>

</div>
</div>

### visitSequentialUMinExpr() {#ac44a236f94f64a6c44bfaf3bc8d752ae}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">Value * SCEVExpander::visitSequentialUMinExpr (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/scevsequentialuminexpr">SCEVSequentialUMinExpr</a> * S)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Declaration at line 513 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/transforms/include/llvm/transforms/utils/scalarevolutionexpander-h">ScalarEvolutionExpander.h</a>, definition at line 1435 of file <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/utils/scalarevolutionexpander-cpp">ScalarEvolutionExpander.cpp</a>.</p>

</div>
</div>

### visitSignExtendExpr() {#a6eb5295d5b4300f2b8cd27e4de900bac}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">Value * SCEVExpander::visitSignExtendExpr (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/scevsignextendexpr">SCEVSignExtendExpr</a> * S)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Declaration at line 495 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/transforms/include/llvm/transforms/utils/scalarevolutionexpander-h">ScalarEvolutionExpander.h</a>, definition at line 1385 of file <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/utils/scalarevolutionexpander-cpp">ScalarEvolutionExpander.cpp</a>.</p>

</div>
</div>

### visitSMaxExpr() {#af2ae2afd31b9f1743aa4431f9dd65f55}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">Value * SCEVExpander::visitSMaxExpr (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/scevsmaxexpr">SCEVSMaxExpr</a> * S)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Declaration at line 505 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/transforms/include/llvm/transforms/utils/scalarevolutionexpander-h">ScalarEvolutionExpander.h</a>, definition at line 1419 of file <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/utils/scalarevolutionexpander-cpp">ScalarEvolutionExpander.cpp</a>.</p>

</div>
</div>

### visitSMinExpr() {#a76d351568dea2dea73b5831973553a02}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">Value * SCEVExpander::visitSMinExpr (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/scevsminexpr">SCEVSMinExpr</a> * S)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Declaration at line 509 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/transforms/include/llvm/transforms/utils/scalarevolutionexpander-h">ScalarEvolutionExpander.h</a>, definition at line 1427 of file <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/utils/scalarevolutionexpander-cpp">ScalarEvolutionExpander.cpp</a>.</p>

</div>
</div>

### visitTruncateExpr() {#a2d18716a1b4bd0fb83cdac8e38f5094c}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">Value * SCEVExpander::visitTruncateExpr (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/scevtruncateexpr">SCEVTruncateExpr</a> * S)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Declaration at line 491 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/transforms/include/llvm/transforms/utils/scalarevolutionexpander-h">ScalarEvolutionExpander.h</a>, definition at line 1374 of file <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/utils/scalarevolutionexpander-cpp">ScalarEvolutionExpander.cpp</a>.</p>

</div>
</div>

### visitUDivExpr() {#a44f1be06c0bddaff604a737c2cc5c017}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">Value * SCEVExpander::visitUDivExpr (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/scevudivexpr">SCEVUDivExpr</a> * S)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Declaration at line 501 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/transforms/include/llvm/transforms/utils/scalarevolutionexpander-h">ScalarEvolutionExpander.h</a>, definition at line 674 of file <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/utils/scalarevolutionexpander-cpp">ScalarEvolutionExpander.cpp</a>.</p>

</div>
</div>

### visitUMaxExpr() {#a398aa5a8fd378f41bc7149f27cc4f346}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">Value * SCEVExpander::visitUMaxExpr (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/scevumaxexpr">SCEVUMaxExpr</a> * S)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Declaration at line 507 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/transforms/include/llvm/transforms/utils/scalarevolutionexpander-h">ScalarEvolutionExpander.h</a>, definition at line 1423 of file <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/utils/scalarevolutionexpander-cpp">ScalarEvolutionExpander.cpp</a>.</p>

</div>
</div>

### visitUMinExpr() {#a0c1068c29244f77a14d302b79056337e}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">Value * SCEVExpander::visitUMinExpr (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/scevuminexpr">SCEVUMinExpr</a> * S)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Declaration at line 511 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/transforms/include/llvm/transforms/utils/scalarevolutionexpander-h">ScalarEvolutionExpander.h</a>, definition at line 1431 of file <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/utils/scalarevolutionexpander-cpp">ScalarEvolutionExpander.cpp</a>.</p>

</div>
</div>

### visitUnknown() {#a28a21749896dfc7b6c70b6b87e038d48}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">Value * llvm::SCEVExpander::visitUnknown (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/scevunknown">SCEVUnknown</a> * S)</td>
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



<p>Definition at line 515 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/transforms/include/llvm/transforms/utils/scalarevolutionexpander-h">ScalarEvolutionExpander.h</a>.</p>

</div>
</div>

### visitVScale() {#a0f314fdc34263b3b7fe45b9854101076}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">Value * SCEVExpander::visitVScale (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/scevvscale">SCEVVScale</a> * S)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Declaration at line 487 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/transforms/include/llvm/transforms/utils/scalarevolutionexpander-h">ScalarEvolutionExpander.h</a>, definition at line 1439 of file <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/utils/scalarevolutionexpander-cpp">ScalarEvolutionExpander.cpp</a>.</p>

</div>
</div>

### visitZeroExtendExpr() {#a25b413caf366ce2d1af3620b896516e6}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">Value * SCEVExpander::visitZeroExtendExpr (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/scevzeroextendexpr">SCEVZeroExtendExpr</a> * S)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Declaration at line 493 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/transforms/include/llvm/transforms/utils/scalarevolutionexpander-h">ScalarEvolutionExpander.h</a>, definition at line 1379 of file <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/utils/scalarevolutionexpander-cpp">ScalarEvolutionExpander.cpp</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Private Member Attributes

### Builder {#a39ca47578ad55b6c8bb653c64c3bf536}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">BuilderType llvm::SCEVExpander::Builder</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 135 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/transforms/include/llvm/transforms/utils/scalarevolutionexpander-h">ScalarEvolutionExpander.h</a>.</p>

</div>
</div>

### CanonicalMode {#af49abbf03c5d46468304e5166990598d}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool llvm::SCEVExpander::CanonicalMode</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>When true, <a href="/web-llvm/docs/api/classes/llvm/scevexpander">SCEVExpander</a> tries to expand expressions in "canonical" form.</p>


<p>When false, expressions are expanded in a more literal form.</p>


<p>In "canonical" form addrecs are expanded as arithmetic based on a canonical induction variable. Note that CanonicalMode doesn't guarantee that all expressions are expanded in "canonical" form. For some expressions literal mode can be preferred.</p>


<p>Definition at line 122 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/transforms/include/llvm/transforms/utils/scalarevolutionexpander-h">ScalarEvolutionExpander.h</a>.</p>

</div>
</div>

### ChainedPhis {#ab3bc6e83a36928fb09e9bdaa9f962108}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">DenseSet&lt;AssertingVH&lt;PHINode&gt; &gt; llvm::SCEVExpander::ChainedPhis</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Phis that complete an IV chain. Reuse.</p>

<p>Definition at line 113 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/transforms/include/llvm/transforms/utils/scalarevolutionexpander-h">ScalarEvolutionExpander.h</a>.</p>

</div>
</div>

### DL {#a2832d8d750888adfa930a40f4b775cfc}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">const DataLayout&amp; llvm::SCEVExpander::DL</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 67 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/transforms/include/llvm/transforms/utils/scalarevolutionexpander-h">ScalarEvolutionExpander.h</a>.</p>

</div>
</div>

### InsertedExpressions {#a302a7e2c1398c2eb3c15bd1d10942e32}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">DenseMap&lt;std::pair&lt;const SCEV *, Instruction *&gt;, TrackingVH&lt;Value&gt; &gt; llvm::SCEVExpander::InsertedExpressions</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 77 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/transforms/include/llvm/transforms/utils/scalarevolutionexpander-h">ScalarEvolutionExpander.h</a>.</p>

</div>
</div>

### InsertedIVs {#a15c246fd830232a66b70e97ba4e15b9a}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">SmallVector&lt;WeakVH, 2&gt; llvm::SCEVExpander::InsertedIVs</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 93 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/transforms/include/llvm/transforms/utils/scalarevolutionexpander-h">ScalarEvolutionExpander.h</a>.</p>

</div>
</div>

### InsertedPostIncValues {#a4a1a76d8b898087e1fb5c55992f0fbbc}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">DenseSet&lt;AssertingVH&lt;Value&gt; &gt; llvm::SCEVExpander::InsertedPostIncValues</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 81 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/transforms/include/llvm/transforms/utils/scalarevolutionexpander-h">ScalarEvolutionExpander.h</a>.</p>

</div>
</div>

### InsertedValues {#a9617c9357c65d9674eea0265f8da3873}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">DenseSet&lt;AssertingVH&lt;Value&gt; &gt; llvm::SCEVExpander::InsertedValues</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 80 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/transforms/include/llvm/transforms/utils/scalarevolutionexpander-h">ScalarEvolutionExpander.h</a>.</p>

</div>
</div>

### InsertPointGuards {#a56d3a87956a2f3c48107d38538edd801}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">SmallVector&lt;SCEVInsertPointGuard *, 8&gt; llvm::SCEVExpander::InsertPointGuards</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Stack of pointers to saved insert points, used to keep insert points consistent when instructions are moved.</p>

<p>Definition at line 175 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/transforms/include/llvm/transforms/utils/scalarevolutionexpander-h">ScalarEvolutionExpander.h</a>.</p>

</div>
</div>

### IVIncInsertLoop {#aedd96ed7cabfbe35949d6728ecc366f2}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">const Loop* llvm::SCEVExpander::IVIncInsertLoop</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>When this is non-null, addrecs expanded in the loop it indicates should be inserted with increments at IVIncInsertPos.</p>

<p>Definition at line 106 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/transforms/include/llvm/transforms/utils/scalarevolutionexpander-h">ScalarEvolutionExpander.h</a>.</p>

</div>
</div>

### IVIncInsertPos {#aab6603f1fe9f273708ae12dea838b750}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">Instruction* llvm::SCEVExpander::IVIncInsertPos</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>When expanding addrecs in the IVIncInsertLoop loop, insert the IV increment at this position.</p>

<p>Definition at line 110 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/transforms/include/llvm/transforms/utils/scalarevolutionexpander-h">ScalarEvolutionExpander.h</a>.</p>

</div>
</div>

### IVName {#a13740ed2a75d6c4cdfa2977908f48ee8}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">const char* llvm::SCEVExpander::IVName</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 70 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/transforms/include/llvm/transforms/utils/scalarevolutionexpander-h">ScalarEvolutionExpander.h</a>.</p>

</div>
</div>

### LSRMode {#a6c3ec10b8aa0d9f2e18bd287d27da800}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool llvm::SCEVExpander::LSRMode</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>When invoked from LSR, the expander is in "strength reduction" mode.</p>


<p>The only difference is that phi's are only reused if they are already in "expanded" form.</p>


<p>Definition at line 127 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/transforms/include/llvm/transforms/utils/scalarevolutionexpander-h">ScalarEvolutionExpander.h</a>.</p>

</div>
</div>

### OrigFlags {#abd1d4ea0467c3ce8222cd25561b12ffe}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">DenseMap&lt;PoisoningVH&lt;Instruction&gt;, PoisonFlags&gt; llvm::SCEVExpander::OrigFlags</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Original flags of instructions for which they were modified.</p>


<p>Used by <a href="/web-llvm/docs/api/classes/llvm/scevexpandercleaner">SCEVExpanderCleaner</a> to undo changes.</p>


<p>Definition at line 90 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/transforms/include/llvm/transforms/utils/scalarevolutionexpander-h">ScalarEvolutionExpander.h</a>.</p>

</div>
</div>

### PostIncLoops {#a2cf670fa81b4a4fcec22a7a9ea79798b}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">PostIncLoopSet llvm::SCEVExpander::PostIncLoops</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Addrecs referring to any of the given loops are expanded in post-inc mode.</p>


<p>For example, expanding {1,+,1}&lt;L&gt; in post-inc mode returns the add instruction that adds one to the phi for {0,+,1}&lt;L&gt;, as opposed to a new phi starting at 1. This is only supported in non-canonical mode.</p>


<p>Definition at line 102 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/transforms/include/llvm/transforms/utils/scalarevolutionexpander-h">ScalarEvolutionExpander.h</a>.</p>

</div>
</div>

### PreserveLCSSA {#a5610ec331defe47156f77671fa962cf9}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool llvm::SCEVExpander::PreserveLCSSA</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Indicates whether LCSSA phis should be created for inserted values.</p>

<p>Definition at line 73 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/transforms/include/llvm/transforms/utils/scalarevolutionexpander-h">ScalarEvolutionExpander.h</a>.</p>

</div>
</div>

### RelevantLoops {#a6f46521c2c6d6f03d58c6e1ca1c0a36b}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">DenseMap&lt;const SCEV *, const Loop *&gt; llvm::SCEVExpander::RelevantLoops</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>A memoization of the "relevant" loop for a given <a href="/web-llvm/docs/api/classes/llvm/scev">SCEV</a>.</p>

<p>Definition at line 96 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/transforms/include/llvm/transforms/utils/scalarevolutionexpander-h">ScalarEvolutionExpander.h</a>.</p>

</div>
</div>

### ReusedValues {#a5a690e395170641aa3c09f7c66bad964}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">SmallPtrSet&lt;Value *, 16&gt; llvm::SCEVExpander::ReusedValues</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Keep track of the existing IR values re-used during expansion.</p>


<p>FIXME: Ideally re-used instructions would not be added to InsertedValues/InsertedPostIncValues.</p>


<p>Definition at line 86 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/transforms/include/llvm/transforms/utils/scalarevolutionexpander-h">ScalarEvolutionExpander.h</a>.</p>

</div>
</div>

### SafeUDivMode {#a0d3639e3fea688663e85d1ff25a7720d}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool llvm::SCEVExpander::SafeUDivMode = false</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>When true, rewrite any divisors of UDiv expressions that may be 0 to umax(Divisor, 1) to avoid introducing UB.</p>


<p>If the divisor may be poison, freeze it first.</p>


<p>Definition at line 132 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/transforms/include/llvm/transforms/utils/scalarevolutionexpander-h">ScalarEvolutionExpander.h</a>.</p>

</div>
</div>

### SE {#a4c360cc24c148a24284ef7e05ac57f46}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">ScalarEvolution&amp; llvm::SCEVExpander::SE</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 66 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/transforms/include/llvm/transforms/utils/scalarevolutionexpander-h">ScalarEvolutionExpander.h</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Public Static Functions

### canReuseFlagsFromOriginalIVInc() {#aad8311debca961aeee16791414f9efa1}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool SCEVExpander::canReuseFlagsFromOriginalIVInc (<a href="/web-llvm/docs/api/classes/llvm/phinode">PHINode</a> * OrigPhi, <a href="/web-llvm/docs/api/classes/llvm/phinode">PHINode</a> * WidePhi, <a href="/web-llvm/docs/api/classes/llvm/instruction">Instruction</a> * OrigInc, <a href="/web-llvm/docs/api/classes/llvm/instruction">Instruction</a> * WideInc)</td>
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

<p>Return true if both increments directly increment the corresponding IV PHI nodes and have the same opcode.</p>


<p>It is not safe to re-use the flags from the original increment, if it is more complex and <a href="/web-llvm/docs/api/classes/llvm/scev">SCEV</a> expansion may have yielded a more simplified wider increment.</p>


<p>Declaration at line 290 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/transforms/include/llvm/transforms/utils/scalarevolutionexpander-h">ScalarEvolutionExpander.h</a>, definition at line 855 of file <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/utils/scalarevolutionexpander-cpp">ScalarEvolutionExpander.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/classes/llvm/instruction/#ab4e05d690df389b8b1477c90387b575f">llvm::Instruction::getOpcode</a>, <a href="/web-llvm/docs/api/namespaces/llvm/patternmatch/#ab3021d22d00a294cb59bd5067bc5c4b2">llvm::PatternMatch::m_c_BinOp</a>, <a href="/web-llvm/docs/api/namespaces/llvm/patternmatch/#a2d9861feadd3a09792967a012559e7b2">llvm::PatternMatch::m_Specific</a>, <a href="/web-llvm/docs/api/namespaces/llvm/patternmatch/#aaf522908fe903018eb9b087dd6e49296">llvm::PatternMatch::m_Value</a> and <a href="/web-llvm/docs/api/namespaces/llvm/patternmatch/#a25d956d9e0beadd47ce4bc255dfa811d">llvm::PatternMatch::match</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/classes/anonymous-simplifyindvar-cpp-/wideniv/#a5586ec5eac8a93b87b095f949ea8daf3">anonymous{SimplifyIndVar.cpp}::WidenIV::createWideIV</a> and <a href="/web-llvm/docs/api/classes/anonymous-simplifyindvar-cpp-/wideniv/#a39eadf98e4773739cd4e7b4befee6fb5">anonymous{SimplifyIndVar.cpp}::WidenIV::widenIVUse</a>.</p>

</div>
</div>

</div>

<hr/>

The documentation for this class was generated from the following files:

<ul>
<li><a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/transforms/include/llvm/transforms/utils/scalarevolutionexpander-h">ScalarEvolutionExpander.h</a></li>
<li><a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/utils/scalarevolutionexpander-cpp">ScalarEvolutionExpander.cpp</a></li>
</ul>

<hr/>

<p class="doxyGeneratedBy">Generated via <a href="https://github.com/xpack/doxygen2docusaurus">doxygen2docusaurus</a> by <a href="https://www.doxygen.nl">Doxygen</a> 1.14.0.</p>

</div>
