---

# DO NOT EDIT!
# Automatically generated via doxygen2docusaurus by Doxygen.

slug: /api/classes/llvm/canonicalloopinfo
custom_edit_url: null
toc_max_heading_level: 4
keywords:
  - doxygen
  - reference
  - class

---

<div class="doxyPage">

# `CanonicalLoopInfo` Class

<p>Class to represented the control flow structure of an OpenMP canonical loop. <a href="#details">More...</a></p>

## Declaration

<div class="doxyDeclaration">
class llvm::CanonicalLoopInfo { ... }
</div>

## Included Headers

<div class="doxyIncludesList">#include "<a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/frontend/include/llvm/frontend/openmp/ompirbuilder-h">llvm/Frontend/OpenMP/OMPIRBuilder.h</a>"
</div>

## Friends Index

<table class="doxyMembersIndex">

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">class</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a1ce8ab76394bc6773081e7634cd20625">OpenMPIRBuilder</a></td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a4b2b7074e300c251f7cb8913620b1d80">isValid</a> () const</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Returns whether this object currently represents the IR of a loop. <a href="#a4b2b7074e300c251f7cb8913620b1d80">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/basicblock">BasicBlock</a> *</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ad50eb30e70ff2a9ea7f220547e2b6f6d">getPreheader</a> () const</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>The preheader ensures that there is only a single edge entering the loop. <a href="#ad50eb30e70ff2a9ea7f220547e2b6f6d">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/basicblock">BasicBlock</a> *</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a01c4471afa921c4962d7138cfcef4942">getHeader</a> () const</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>The header is the entry for each iteration. <a href="#a01c4471afa921c4962d7138cfcef4942">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/basicblock">BasicBlock</a> *</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#acb5b5b136597312e0d5df6b746a7e6db">getCond</a> () const</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>The condition block computes whether there is another loop iteration. <a href="#acb5b5b136597312e0d5df6b746a7e6db">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/basicblock">BasicBlock</a> *</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a47521ec347ef7b522745bf89e2e2d19a">getBody</a> () const</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>The body block is the single entry for a loop iteration and not controlled by <a href="/web-llvm/docs/api/classes/llvm/canonicalloopinfo">CanonicalLoopInfo</a>. <a href="#a47521ec347ef7b522745bf89e2e2d19a">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/basicblock">BasicBlock</a> *</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ac37a6cf77f6f82b6bb28af4d9c8626d0">getLatch</a> () const</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Reaching the latch indicates the end of the loop body code. <a href="#ac37a6cf77f6f82b6bb28af4d9c8626d0">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/basicblock">BasicBlock</a> *</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ad3bf46daef8ce8176a68bcec0320dfd3">getExit</a> () const</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Reaching the exit indicates no more iterations are being executed. <a href="#ad3bf46daef8ce8176a68bcec0320dfd3">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/basicblock">BasicBlock</a> *</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a92d8bce979891dc43b6573e8cca2e58c">getAfter</a> () const</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>The after block is intended for clean-up code such as lifetime end markers. <a href="#a92d8bce979891dc43b6573e8cca2e58c">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/value">Value</a> *</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a01560f4a4ff7bfc8a96bd406b6f17ea2">getTripCount</a> () const</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Returns the <a href="/web-llvm/docs/api/classes/llvm/value">llvm::Value</a> containing the number of loop iterations. <a href="#a01560f4a4ff7bfc8a96bd406b6f17ea2">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/instruction">Instruction</a> *</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#af4131f5f461f1138483addfd7cd7f579">getIndVar</a> () const</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Returns the instruction representing the current logical induction variable. <a href="#af4131f5f461f1138483addfd7cd7f579">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/type">Type</a> *</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a46b5cd2a0881c8be5183d70a32eef90d">getIndVarType</a> () const</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Return the type of the induction variable (and the trip count). <a href="#a46b5cd2a0881c8be5183d70a32eef90d">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/openmpirbuilder/#aafc1886793b898052f87edd7e9fdbaa3">OpenMPIRBuilder::InsertPointTy</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ac72ebc430ef7dcf1791c66080ddedd9d">getPreheaderIP</a> () const</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Return the insertion point for user code before the loop. <a href="#ac72ebc430ef7dcf1791c66080ddedd9d">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/openmpirbuilder/#aafc1886793b898052f87edd7e9fdbaa3">OpenMPIRBuilder::InsertPointTy</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a8031442528bff99473596a0de4aa0422">getBodyIP</a> () const</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Return the insertion point for user code in the body. <a href="#a8031442528bff99473596a0de4aa0422">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/openmpirbuilder/#aafc1886793b898052f87edd7e9fdbaa3">OpenMPIRBuilder::InsertPointTy</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a578dd7d619d0ccfc6ace07aa380022cc">getAfterIP</a> () const</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Return the insertion point for user code after the loop. <a href="#a578dd7d619d0ccfc6ace07aa380022cc">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/function">Function</a> *</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a9592feb460b27d417f42a41aabfe253a">getFunction</a> () const</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a32ff799dcb39887a8d21322020f305ba">assertOK</a> () const</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Consistency self-check. <a href="#a32ff799dcb39887a8d21322020f305ba">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">void</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a9ce55b05f8ad85126fc92eeeb35457c7">invalidate</a> ()</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Invalidate this loop. <a href="#a9ce55b05f8ad85126fc92eeeb35457c7">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

</table>

## Private Member Functions Index

<table class="doxyMembersIndex">

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">void</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#acc965de7b820b3a86dae34b15b4eae02">collectControlBlocks</a> (SmallVectorImpl&lt; BasicBlock * &gt; &amp;BBs)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Add the control blocks of this loop to <span class="doxyComputerOutput">BBs</span>. <a href="#acc965de7b820b3a86dae34b15b4eae02">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">void</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a588e5d2b299d0090847ce7f3df2749ba">setTripCount</a> (Value *TripCount)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Sets the number of loop iterations to the given value. <a href="#a588e5d2b299d0090847ce7f3df2749ba">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">void</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#acd8accd2da5cd306a89efb53c1e0f7bc">mapIndVar</a> (llvm::function_ref&lt; Value *(Instruction *)&gt; Updater)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Replace all uses of the canonical induction variable in the loop body with a new one. <a href="#acd8accd2da5cd306a89efb53c1e0f7bc">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

</table>

## Private Member Attributes Index

<table class="doxyMembersIndex">

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/basicblock">BasicBlock</a> *</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a7a071723c44daf28c5226d0e270a9734">Header</a> = nullptr</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/basicblock">BasicBlock</a> *</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#add606e5b781dc64d0ba4820809e8d88a">Cond</a> = nullptr</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/basicblock">BasicBlock</a> *</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a8ae42f9b63c65fda9fc05a85c37d470b">Latch</a> = nullptr</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/basicblock">BasicBlock</a> *</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a2c2f33e4aac8c213794cb9fac93f8a6d">Exit</a> = nullptr</td>
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

<p>Class to represented the control flow structure of an OpenMP canonical loop.</p>


<p>The control-flow structure is standardized for easy consumption by directives associated with loops. For instance, the worksharing-loop construct may change this control flow such that each loop iteration is executed on only one thread. The constraints of a canonical loop in brief are:</p>


<ul class="doxyList ">
<li>The number of loop iterations must have been computed before entering the loop.</li>
<li>Has an (unsigned) logical induction variable that starts at zero and increments by one.</li>
<li>The loop's CFG itself has no side-effects. The OpenMP specification itself allows side-effects, but the order in which they happen, including how often or whether at all, is unspecified. We expect that the frontend will emit those side-effect instructions somewhere (e.g. before the loop) such that the <a href="/web-llvm/docs/api/classes/llvm/canonicalloopinfo">CanonicalLoopInfo</a> itself can be side-effect free.</li>
</ul>

<p>Keep in mind that <a href="/web-llvm/docs/api/classes/llvm/canonicalloopinfo">CanonicalLoopInfo</a> is meant to only describe a repeated execution of a loop body that satifies these constraints. It does NOT represent arbitrary SESE regions that happen to contain a loop. Do not use <a href="/web-llvm/docs/api/classes/llvm/canonicalloopinfo">CanonicalLoopInfo</a> for such purposes.</p>


<p>The control flow can be described as follows:</p>



<pre><code>Preheader
   |
</code></pre>


<p>/-&gt; Header | | | Cond—\ | | | | Body | | | | | | &lt;...&gt; | | | | | --Latch | | Exit | After</p>


<p>The loop is thought to start at PreheaderIP (at the Preheader's terminator, including) and end at AfterIP (at the After's first instruction, excluding). That is, instructions in the Preheader and After blocks (except the Preheader's terminator) are out of <a href="/web-llvm/docs/api/classes/llvm/canonicalloopinfo">CanonicalLoopInfo</a>'s control and may have side-effects. Typically, the Preheader is used to compute the loop's trip count. The instructions from BodyIP (at the Body block's first instruction, excluding) until the Latch are also considered outside <a href="/web-llvm/docs/api/classes/llvm/canonicalloopinfo">CanonicalLoopInfo</a>'s control and thus can have side-effects. The body block is the single entry point into the loop body, which may contain arbitrary control flow as long as all control paths eventually branch to the Latch block.</p>


<p>TODO: Consider adding another standardized <a href="/web-llvm/docs/api/classes/llvm/basicblock">BasicBlock</a> between Body CFG and Latch to guarantee that there is only a single edge to the latch. It would make loop transformations easier to not needing to consider multiple predecessors of the latch (See redirectAllPredecessorsTo) and would give us an equivalant to PreheaderIP, AfterIP and BodyIP for inserting code that executes after each body iteration.</p>


<p>There must be no loop-carried dependencies through llvm::Values. This is equivalant to that the Latch has no <a href="/web-llvm/docs/api/classes/llvm/phinode">PHINode</a> and the Header's only <a href="/web-llvm/docs/api/classes/llvm/phinode">PHINode</a> is for the induction variable.</p>


<p>All code in Header, Cond, Latch and Exit (plus the terminator of the Preheader) are <a href="/web-llvm/docs/api/classes/llvm/canonicalloopinfo">CanonicalLoopInfo</a>'s responsibility and their build-up checked by <a href="#a32ff799dcb39887a8d21322020f305ba">assertOK()</a>. They are expected to not be modified unless explicitly modifying the <a href="/web-llvm/docs/api/classes/llvm/canonicalloopinfo">CanonicalLoopInfo</a> through a methods that applies a OpenMP loop-associated construct such as applyWorkshareLoop, tileLoops, unrollLoop, etc. These methods usually invalidate the <a href="/web-llvm/docs/api/classes/llvm/canonicalloopinfo">CanonicalLoopInfo</a> and re-use its basic blocks. After invalidation, the <a href="/web-llvm/docs/api/classes/llvm/canonicalloopinfo">CanonicalLoopInfo</a> must not be used anymore as its underlying control flow may not exist anymore. Loop-transformation methods such as tileLoops, collapseLoops and unrollLoop may also return a new <a href="/web-llvm/docs/api/classes/llvm/canonicalloopinfo">CanonicalLoopInfo</a> that can be passed to other loop-associated construct implementing methods. These loop-transforming methods may either create a new <a href="/web-llvm/docs/api/classes/llvm/canonicalloopinfo">CanonicalLoopInfo</a> usually using createLoopSkeleton and invalidate the input <a href="/web-llvm/docs/api/classes/llvm/canonicalloopinfo">CanonicalLoopInfo</a>, or reuse and modify one of the input <a href="/web-llvm/docs/api/classes/llvm/canonicalloopinfo">CanonicalLoopInfo</a> and return it as representing the modified loop. What is done is an implementation detail of transformation-implementing method and callers should always assume that the <a href="/web-llvm/docs/api/classes/llvm/canonicalloopinfo">CanonicalLoopInfo</a> passed to it is invalidated and a new object is returned. Returned <a href="/web-llvm/docs/api/classes/llvm/canonicalloopinfo">CanonicalLoopInfo</a> have the same structure and guarantees as the one created by createCanonicalLoop, such that transforming methods do not have to special case where the <a href="/web-llvm/docs/api/classes/llvm/canonicalloopinfo">CanonicalLoopInfo</a> originated from.</p>


<p>Generally, methods consuming <a href="/web-llvm/docs/api/classes/llvm/canonicalloopinfo">CanonicalLoopInfo</a> do not need an <a href="/web-llvm/docs/api/classes/llvm/openmpirbuilder/#aafc1886793b898052f87edd7e9fdbaa3">OpenMPIRBuilder::InsertPointTy</a> as argument, but use the locations of the <a href="/web-llvm/docs/api/classes/llvm/canonicalloopinfo">CanonicalLoopInfo</a> to insert new or modify existing instructions. Unless documented otherwise, methods consuming <a href="/web-llvm/docs/api/classes/llvm/canonicalloopinfo">CanonicalLoopInfo</a> do not invalidate any <a href="/web-llvm/docs/api/classes/llvm/irbuilder">InsertPoint</a> that is outside <a href="/web-llvm/docs/api/classes/llvm/canonicalloopinfo">CanonicalLoopInfo</a>'s control. Specifically, any <a href="/web-llvm/docs/api/classes/llvm/irbuilder">InsertPoint</a> in the Preheader, After or Block can still be used after calling such a method.</p>


<p>TODO: Provide mechanisms for exception handling and cancellation points.</p>


<p>Defined outside <a href="/web-llvm/docs/api/classes/llvm/openmpirbuilder">OpenMPIRBuilder</a> because nested classes cannot be forward-declared, e.g. to avoid having to include the entire <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/frontend/include/llvm/frontend/openmp/ompirbuilder-h">OMPIRBuilder.h</a>.</p>


<p>Definition at line 3512 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/frontend/include/llvm/frontend/openmp/ompirbuilder-h">OMPIRBuilder.h</a>.</p>


<div class="doxySectionDef">

## Friends

### OpenMPIRBuilder {#a1ce8ab76394bc6773081e7634cd20625}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">friend class <a href="/web-llvm/docs/api/classes/llvm/openmpirbuilder">OpenMPIRBuilder</a></td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">


<p>Definition at line 3513 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/frontend/include/llvm/frontend/openmp/ompirbuilder-h">OMPIRBuilder.h</a>.</p>


<p>Reference <a href="#a1ce8ab76394bc6773081e7634cd20625">OpenMPIRBuilder</a>.</p>


<p>Referenced by <a href="#a1ce8ab76394bc6773081e7634cd20625">OpenMPIRBuilder</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Public Member Functions

### assertOK() {#a32ff799dcb39887a8d21322020f305ba}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void CanonicalLoopInfo::assertOK ()</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Consistency self-check.</p>

<p>Declaration at line 3662 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/frontend/include/llvm/frontend/openmp/ompirbuilder-h">OMPIRBuilder.h</a>, definition at line 9892 of file <a href="/web-llvm/docs/api/files/lib/lib/frontend/lib/frontend/openmp/ompirbuilder-cpp">OMPIRBuilder.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/files/lib/lib/passes/standardinstrumentations-cpp/#a6f1bbcae7288f05872dcfe811d0388baa7bfcadb5535fe8aad5032762b7bfe159">After</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/silowercontrolflow-cpp/#a4868c5d81c5ccc98c47aeab6244346a0">assert</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#ac4fc845f5ed92de63cd4474f128f5fc5">llvm::cast</a>, <a href="/web-llvm/docs/api/classes/llvm/basicblock/#a4848d1a141ddc7cf0068460fba53ba37">llvm::BasicBlock::front</a>, <a href="#a92d8bce979891dc43b6573e8cca2e58c">getAfter</a>, <a href="#a47521ec347ef7b522745bf89e2e2d19a">getBody</a>, <a href="#af4131f5f461f1138483addfd7cd7f579">getIndVar</a>, <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/vectorize/vplanslp-cpp/#a06b4f19004df11b338ccc7e73bf47ab4">getOpcode</a>, <a href="/web-llvm/docs/api/classes/llvm/user/#aa0a2cb1582d1cec317bd205085469ca1">llvm::User::getOperand</a>, <a href="/web-llvm/docs/api/files/lib/lib/analysis/basicaliasanalysis-cpp/#a1b8850f1ed44c12bc3501175a71c251c">getParent</a>, <a href="#ad50eb30e70ff2a9ea7f220547e2b6f6d">getPreheader</a>, <a href="/web-llvm/docs/api/classes/llvm/basicblock/#a59fb91d1691350f7d1b8e8a114e3f2a4">llvm::BasicBlock::getSinglePredecessor</a>, <a href="/web-llvm/docs/api/classes/llvm/basicblock/#a79c007dcf9fff57e1569e778d7885b5e">llvm::BasicBlock::getSingleSuccessor</a>, <a href="/web-llvm/docs/api/classes/llvm/basicblock/#acf3c3aa4880eb60d00963ba93082c298">llvm::BasicBlock::getTerminator</a>, <a href="#a01560f4a4ff7bfc8a96bd406b6f17ea2">getTripCount</a>, <a href="/web-llvm/docs/api/classes/llvm/value/#a0344a49526443edf90cc0aef3abd3337">llvm::Value::getType</a>, <a href="/web-llvm/docs/api/classes/llvm/cmpinst/#a2be3583dac92a031fa1458d4d992c78ba91d86a4753c8bd7624e01bf565d87f8e">llvm::CmpInst::ICMP_ULT</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a92ca992e52dddc420f4b069cae06dfbe">llvm::isa</a>, <a href="/web-llvm/docs/api/files/lib/lib/demangle/rustdemangle-cpp/#a103d8cfe62c1651cd70e181746f8a840">isValid</a>, <a href="/web-llvm/docs/api/files/lib/lib/analysis/lint-cpp/#a45005634b54e2126cb3e6ec0dbc9ade4">isZero</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/nvptx/nvvmreflect-cpp/#ac934769d93af95250952646a3829df4c">size</a> and <a href="/web-llvm/docs/api/namespaces/llvm/#a26e2a938b431eaa6eca2beaa96410c9d">llvm::successors</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/classes/llvm/openmpirbuilder/#ae0287686a5ffe03bc264972c862726ea">llvm::OpenMPIRBuilder::createCanonicalLoop</a> and <a href="/web-llvm/docs/api/classes/llvm/openmpirbuilder/#a445fa52d77040bccb16bfea111234a2e">llvm::OpenMPIRBuilder::createLoopSkeleton</a>.</p>

</div>
</div>

### getAfter() {#a92d8bce979891dc43b6573e8cca2e58c}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">BasicBlock * llvm::CanonicalLoopInfo::getAfter ()</td>
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

<p>The after block is intended for clean-up code such as lifetime end markers.</p>


<p>It is separate from the exit block to ensure, analogous to the preheader, it having just a single entry edge and being free from PHI nodes should there be multiple loop exits (such as from break statements/cancellations).</p>


<p>Definition at line 3605 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/frontend/include/llvm/frontend/openmp/ompirbuilder-h">OMPIRBuilder.h</a>.</p>


<p>References <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/silowercontrolflow-cpp/#a4868c5d81c5ccc98c47aeab6244346a0">assert</a> and <a href="#a4b2b7074e300c251f7cb8913620b1d80">isValid</a>.</p>


<p>Referenced by <a href="#a32ff799dcb39887a8d21322020f305ba">assertOK</a>, <a href="/web-llvm/docs/api/classes/llvm/openmpirbuilder/#a08610118e213de1b759470f0eafb9b18">llvm::OpenMPIRBuilder::collapseLoops</a>, <a href="/web-llvm/docs/api/classes/llvm/openmpirbuilder/#ae0287686a5ffe03bc264972c862726ea">llvm::OpenMPIRBuilder::createCanonicalLoop</a>, <a href="#a578dd7d619d0ccfc6ace07aa380022cc">getAfterIP</a> and <a href="/web-llvm/docs/api/classes/llvm/openmpirbuilder/#a76e12ec076e7af4be7b8b77a5d53d3fc">llvm::OpenMPIRBuilder::tileLoops</a>.</p>

</div>
</div>

### getAfterIP() {#a578dd7d619d0ccfc6ace07aa380022cc}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">OpenMPIRBuilder::InsertPointTy llvm::CanonicalLoopInfo::getAfterIP ()</td>
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

<p>Return the insertion point for user code after the loop.</p>

<p>Definition at line 3650 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/frontend/include/llvm/frontend/openmp/ompirbuilder-h">OMPIRBuilder.h</a>.</p>


<p>References <a href="/web-llvm/docs/api/files/lib/lib/passes/standardinstrumentations-cpp/#a6f1bbcae7288f05872dcfe811d0388baa7bfcadb5535fe8aad5032762b7bfe159">After</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/silowercontrolflow-cpp/#a4868c5d81c5ccc98c47aeab6244346a0">assert</a>, <a href="#a92d8bce979891dc43b6573e8cca2e58c">getAfter</a> and <a href="#a4b2b7074e300c251f7cb8913620b1d80">isValid</a>.</p>

</div>
</div>

### getBody() {#a47521ec347ef7b522745bf89e2e2d19a}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">BasicBlock * llvm::CanonicalLoopInfo::getBody ()</td>
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

<p>The body block is the single entry for a loop iteration and not controlled by <a href="/web-llvm/docs/api/classes/llvm/canonicalloopinfo">CanonicalLoopInfo</a>.</p>


<p>It can contain arbitrary control flow but must eventually branch to the <span class="doxyComputerOutput">Latch</span> block.</p>


<p>Definition at line 3581 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/frontend/include/llvm/frontend/openmp/ompirbuilder-h">OMPIRBuilder.h</a>.</p>


<p>References <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/silowercontrolflow-cpp/#a4868c5d81c5ccc98c47aeab6244346a0">assert</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#ac4fc845f5ed92de63cd4474f128f5fc5">llvm::cast</a> and <a href="#a4b2b7074e300c251f7cb8913620b1d80">isValid</a>.</p>


<p>Referenced by <a href="#a32ff799dcb39887a8d21322020f305ba">assertOK</a>, <a href="/web-llvm/docs/api/classes/llvm/openmpirbuilder/#a08610118e213de1b759470f0eafb9b18">llvm::OpenMPIRBuilder::collapseLoops</a>, <a href="#a8031442528bff99473596a0de4aa0422">getBodyIP</a>, <a href="/web-llvm/docs/api/classes/llvm/openmpirbuilder/#a76e12ec076e7af4be7b8b77a5d53d3fc">llvm::OpenMPIRBuilder::tileLoops</a> and <a href="/web-llvm/docs/api/files/lib/lib/frontend/lib/frontend/openmp/ompirbuilder-cpp/#aa2a5199bf39360e25f40b93cd5f9468a">workshareLoopTargetCallback</a>.</p>

</div>
</div>

### getBodyIP() {#a8031442528bff99473596a0de4aa0422}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">OpenMPIRBuilder::InsertPointTy llvm::CanonicalLoopInfo::getBodyIP ()</td>
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

<p>Return the insertion point for user code in the body.</p>

<p>Definition at line 3643 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/frontend/include/llvm/frontend/openmp/ompirbuilder-h">OMPIRBuilder.h</a>.</p>


<p>References <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/silowercontrolflow-cpp/#a4868c5d81c5ccc98c47aeab6244346a0">assert</a>, <a href="/web-llvm/docs/api/classes/llvm/basicblock/#a0ed5f3ab3c2e4196ee0cffffa080c062">llvm::BasicBlock::begin</a>, <a href="#a47521ec347ef7b522745bf89e2e2d19a">getBody</a> and <a href="#a4b2b7074e300c251f7cb8913620b1d80">isValid</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/classes/llvm/openmpirbuilder/#ae0287686a5ffe03bc264972c862726ea">llvm::OpenMPIRBuilder::createCanonicalLoop</a>.</p>

</div>
</div>

### getCond() {#acb5b5b136597312e0d5df6b746a7e6db}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">BasicBlock * llvm::CanonicalLoopInfo::getCond ()</td>
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

<p>The condition block computes whether there is another loop iteration.</p>


<p>If yes, branches to the body; otherwise to the exit block.</p>


<p>Definition at line 3573 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/frontend/include/llvm/frontend/openmp/ompirbuilder-h">OMPIRBuilder.h</a>.</p>


<p>References <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/silowercontrolflow-cpp/#a4868c5d81c5ccc98c47aeab6244346a0">assert</a> and <a href="#a4b2b7074e300c251f7cb8913620b1d80">isValid</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/classes/llvm/openmpirbuilder/#acd1fbb2df257f945afda92919be322f3">llvm::OpenMPIRBuilder::applySimd</a>.</p>

</div>
</div>

### getExit() {#ad3bf46daef8ce8176a68bcec0320dfd3}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">BasicBlock * llvm::CanonicalLoopInfo::getExit ()</td>
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

<p>Reaching the exit indicates no more iterations are being executed.</p>

<p>Definition at line 3595 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/frontend/include/llvm/frontend/openmp/ompirbuilder-h">OMPIRBuilder.h</a>.</p>


<p>References <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/silowercontrolflow-cpp/#a4868c5d81c5ccc98c47aeab6244346a0">assert</a> and <a href="#a4b2b7074e300c251f7cb8913620b1d80">isValid</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/classes/llvm/openmpirbuilder/#a76e12ec076e7af4be7b8b77a5d53d3fc">llvm::OpenMPIRBuilder::tileLoops</a> and <a href="/web-llvm/docs/api/files/lib/lib/frontend/lib/frontend/openmp/ompirbuilder-cpp/#aa2a5199bf39360e25f40b93cd5f9468a">workshareLoopTargetCallback</a>.</p>

</div>
</div>

### getFunction() {#a9592feb460b27d417f42a41aabfe253a}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">Function * llvm::CanonicalLoopInfo::getFunction ()</td>
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



<p>Definition at line 3656 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/frontend/include/llvm/frontend/openmp/ompirbuilder-h">OMPIRBuilder.h</a>.</p>


<p>References <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/silowercontrolflow-cpp/#a4868c5d81c5ccc98c47aeab6244346a0">assert</a> and <a href="#a4b2b7074e300c251f7cb8913620b1d80">isValid</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/classes/llvm/openmpirbuilder/#acd1fbb2df257f945afda92919be322f3">llvm::OpenMPIRBuilder::applySimd</a> and <a href="/web-llvm/docs/api/files/lib/lib/frontend/lib/frontend/openmp/ompirbuilder-cpp/#a946282957319b8c23ab9f169abb504c4">computeHeuristicUnrollFactor</a>.</p>

</div>
</div>

### getHeader() {#a01c4471afa921c4962d7138cfcef4942}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">BasicBlock * llvm::CanonicalLoopInfo::getHeader ()</td>
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

<p>The header is the entry for each iteration.</p>


<p>In the canonical control flow, it only contains the <a href="/web-llvm/docs/api/classes/llvm/phinode">PHINode</a> for the induction variable.</p>


<p>Definition at line 3566 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/frontend/include/llvm/frontend/openmp/ompirbuilder-h">OMPIRBuilder.h</a>.</p>


<p>References <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/silowercontrolflow-cpp/#a4868c5d81c5ccc98c47aeab6244346a0">assert</a> and <a href="#a4b2b7074e300c251f7cb8913620b1d80">isValid</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/classes/llvm/openmpirbuilder/#acd1fbb2df257f945afda92919be322f3">llvm::OpenMPIRBuilder::applySimd</a>, <a href="/web-llvm/docs/api/files/lib/lib/frontend/lib/frontend/openmp/ompirbuilder-cpp/#a946282957319b8c23ab9f169abb504c4">computeHeuristicUnrollFactor</a> and <a href="/web-llvm/docs/api/files/lib/lib/frontend/lib/frontend/openmp/ompirbuilder-cpp/#aa2a5199bf39360e25f40b93cd5f9468a">workshareLoopTargetCallback</a>.</p>

</div>
</div>

### getIndVar() {#af4131f5f461f1138483addfd7cd7f579}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">Instruction * llvm::CanonicalLoopInfo::getIndVar ()</td>
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

<p>Returns the instruction representing the current logical induction variable.</p>


<p>Always unsigned, always starting at 0 with an increment of one.</p>


<p>Definition at line 3622 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/frontend/include/llvm/frontend/openmp/ompirbuilder-h">OMPIRBuilder.h</a>.</p>


<p>References <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/silowercontrolflow-cpp/#a4868c5d81c5ccc98c47aeab6244346a0">assert</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a92ca992e52dddc420f4b069cae06dfbe">llvm::isa</a> and <a href="#a4b2b7074e300c251f7cb8913620b1d80">isValid</a>.</p>


<p>Referenced by <a href="#a32ff799dcb39887a8d21322020f305ba">assertOK</a>, <a href="/web-llvm/docs/api/classes/llvm/openmpirbuilder/#ae0287686a5ffe03bc264972c862726ea">llvm::OpenMPIRBuilder::createCanonicalLoop</a>, <a href="#a46b5cd2a0881c8be5183d70a32eef90d">getIndVarType</a> and <a href="/web-llvm/docs/api/classes/llvm/openmpirbuilder/#a76e12ec076e7af4be7b8b77a5d53d3fc">llvm::OpenMPIRBuilder::tileLoops</a>.</p>

</div>
</div>

### getIndVarType() {#a46b5cd2a0881c8be5183d70a32eef90d}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">Type * llvm::CanonicalLoopInfo::getIndVarType ()</td>
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

<p>Return the type of the induction variable (and the trip count).</p>

<p>Definition at line 3630 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/frontend/include/llvm/frontend/openmp/ompirbuilder-h">OMPIRBuilder.h</a>.</p>


<p>References <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/silowercontrolflow-cpp/#a4868c5d81c5ccc98c47aeab6244346a0">assert</a>, <a href="#af4131f5f461f1138483addfd7cd7f579">getIndVar</a>, <a href="/web-llvm/docs/api/classes/llvm/value/#a0344a49526443edf90cc0aef3abd3337">llvm::Value::getType</a> and <a href="#a4b2b7074e300c251f7cb8913620b1d80">isValid</a>.</p>

</div>
</div>

### getLatch() {#ac37a6cf77f6f82b6bb28af4d9c8626d0}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">BasicBlock * llvm::CanonicalLoopInfo::getLatch ()</td>
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

<p>Reaching the latch indicates the end of the loop body code.</p>


<p>In the canonical control flow, it only contains the increment of the induction variable.</p>


<p>Definition at line 3589 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/frontend/include/llvm/frontend/openmp/ompirbuilder-h">OMPIRBuilder.h</a>.</p>


<p>References <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/silowercontrolflow-cpp/#a4868c5d81c5ccc98c47aeab6244346a0">assert</a> and <a href="#a4b2b7074e300c251f7cb8913620b1d80">isValid</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/classes/llvm/openmpirbuilder/#acd1fbb2df257f945afda92919be322f3">llvm::OpenMPIRBuilder::applySimd</a>, <a href="/web-llvm/docs/api/classes/llvm/openmpirbuilder/#a08610118e213de1b759470f0eafb9b18">llvm::OpenMPIRBuilder::collapseLoops</a> and <a href="/web-llvm/docs/api/classes/llvm/openmpirbuilder/#a76e12ec076e7af4be7b8b77a5d53d3fc">llvm::OpenMPIRBuilder::tileLoops</a>.</p>

</div>
</div>

### getPreheader() {#ad50eb30e70ff2a9ea7f220547e2b6f6d}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">BasicBlock * CanonicalLoopInfo::getPreheader ()</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>The preheader ensures that there is only a single edge entering the loop.</p>


<p>Code that must be execute before any loop iteration can be emitted here, such as computing the loop trip count and begin lifetime markers. Code in the preheader is not considered part of the canonical loop.</p>


<p>Declaration at line 3562 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/frontend/include/llvm/frontend/openmp/ompirbuilder-h">OMPIRBuilder.h</a>, definition at line 9838 of file <a href="/web-llvm/docs/api/files/lib/lib/frontend/lib/frontend/openmp/ompirbuilder-cpp">OMPIRBuilder.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/silowercontrolflow-cpp/#a4868c5d81c5ccc98c47aeab6244346a0">assert</a>, <a href="/web-llvm/docs/api/files/lib/lib/demangle/rustdemangle-cpp/#a103d8cfe62c1651cd70e181746f8a840">isValid</a>, <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/support/errorhandling-h/#ace243f5c25697a1107cce46626b3dc94">llvm_unreachable</a> and <a href="/web-llvm/docs/api/namespaces/llvm/#acb22fb04083152eee862457e42e8dc31">llvm::predecessors</a>.</p>


<p>Referenced by <a href="#a32ff799dcb39887a8d21322020f305ba">assertOK</a>, <a href="/web-llvm/docs/api/classes/llvm/openmpirbuilder/#a08610118e213de1b759470f0eafb9b18">llvm::OpenMPIRBuilder::collapseLoops</a>, <a href="/web-llvm/docs/api/classes/llvm/openmpirbuilder/#ae0287686a5ffe03bc264972c862726ea">llvm::OpenMPIRBuilder::createCanonicalLoop</a>, <a href="#ac72ebc430ef7dcf1791c66080ddedd9d">getPreheaderIP</a>, <a href="/web-llvm/docs/api/classes/llvm/openmpirbuilder/#a76e12ec076e7af4be7b8b77a5d53d3fc">llvm::OpenMPIRBuilder::tileLoops</a> and <a href="/web-llvm/docs/api/files/lib/lib/frontend/lib/frontend/openmp/ompirbuilder-cpp/#aa2a5199bf39360e25f40b93cd5f9468a">workshareLoopTargetCallback</a>.</p>

</div>
</div>

### getPreheaderIP() {#ac72ebc430ef7dcf1791c66080ddedd9d}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">OpenMPIRBuilder::InsertPointTy llvm::CanonicalLoopInfo::getPreheaderIP ()</td>
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

<p>Return the insertion point for user code before the loop.</p>

<p>Definition at line 3636 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/frontend/include/llvm/frontend/openmp/ompirbuilder-h">OMPIRBuilder.h</a>.</p>


<p>References <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/silowercontrolflow-cpp/#a4868c5d81c5ccc98c47aeab6244346a0">assert</a>, <a href="/web-llvm/docs/api/classes/llvm/basicblock/#a0b4e7bee9b8575cc7db73329f1a561bd">llvm::BasicBlock::end</a>, <a href="#ad50eb30e70ff2a9ea7f220547e2b6f6d">getPreheader</a> and <a href="#a4b2b7074e300c251f7cb8913620b1d80">isValid</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/classes/llvm/openmpirbuilder/#a08610118e213de1b759470f0eafb9b18">llvm::OpenMPIRBuilder::collapseLoops</a> and <a href="/web-llvm/docs/api/classes/llvm/openmpirbuilder/#a76e12ec076e7af4be7b8b77a5d53d3fc">llvm::OpenMPIRBuilder::tileLoops</a>.</p>

</div>
</div>

### getTripCount() {#a01560f4a4ff7bfc8a96bd406b6f17ea2}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">Value * llvm::CanonicalLoopInfo::getTripCount ()</td>
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

<p>Returns the <a href="/web-llvm/docs/api/classes/llvm/value">llvm::Value</a> containing the number of loop iterations.</p>


<p>It must be valid in the preheader and always interpreted as an unsigned integer of any bit-width.</p>


<p>Definition at line 3613 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/frontend/include/llvm/frontend/openmp/ompirbuilder-h">OMPIRBuilder.h</a>.</p>


<p>References <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/silowercontrolflow-cpp/#a4868c5d81c5ccc98c47aeab6244346a0">assert</a>, <a href="/web-llvm/docs/api/classes/llvm/user/#aa0a2cb1582d1cec317bd205085469ca1">llvm::User::getOperand</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a92ca992e52dddc420f4b069cae06dfbe">llvm::isa</a> and <a href="#a4b2b7074e300c251f7cb8913620b1d80">isValid</a>.</p>


<p>Referenced by <a href="#a32ff799dcb39887a8d21322020f305ba">assertOK</a> and <a href="/web-llvm/docs/api/files/lib/lib/frontend/lib/frontend/openmp/ompirbuilder-cpp/#aa2a5199bf39360e25f40b93cd5f9468a">workshareLoopTargetCallback</a>.</p>

</div>
</div>

### invalidate() {#a9ce55b05f8ad85126fc92eeeb35457c7}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void CanonicalLoopInfo::invalidate ()</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Invalidate this loop.</p>


<p>That is, the underlying IR does not fulfill the requirements of an OpenMP canonical loop anymore.</p>


<p>Declaration at line 3666 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/frontend/include/llvm/frontend/openmp/ompirbuilder-h">OMPIRBuilder.h</a>, definition at line 9986 of file <a href="/web-llvm/docs/api/files/lib/lib/frontend/lib/frontend/openmp/ompirbuilder-cpp">OMPIRBuilder.cpp</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/files/lib/lib/frontend/lib/frontend/openmp/ompirbuilder-cpp/#aa2a5199bf39360e25f40b93cd5f9468a">workshareLoopTargetCallback</a>.</p>

</div>
</div>

### isValid() {#a4b2b7074e300c251f7cb8913620b1d80}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool llvm::CanonicalLoopInfo::isValid ()</td>
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

<p>Returns whether this object currently represents the IR of a loop.</p>


<p>If returning false, it may have been consumed by a loop transformation or not been intialized. Do not use in this case;</p>


<p>Definition at line 3556 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/frontend/include/llvm/frontend/openmp/ompirbuilder-h">OMPIRBuilder.h</a>.</p>


<p>Referenced by <a href="#a92d8bce979891dc43b6573e8cca2e58c">getAfter</a>, <a href="#a578dd7d619d0ccfc6ace07aa380022cc">getAfterIP</a>, <a href="#a47521ec347ef7b522745bf89e2e2d19a">getBody</a>, <a href="#a8031442528bff99473596a0de4aa0422">getBodyIP</a>, <a href="#acb5b5b136597312e0d5df6b746a7e6db">getCond</a>, <a href="#ad3bf46daef8ce8176a68bcec0320dfd3">getExit</a>, <a href="#a9592feb460b27d417f42a41aabfe253a">getFunction</a>, <a href="#a01c4471afa921c4962d7138cfcef4942">getHeader</a>, <a href="#af4131f5f461f1138483addfd7cd7f579">getIndVar</a>, <a href="#a46b5cd2a0881c8be5183d70a32eef90d">getIndVarType</a>, <a href="#ac37a6cf77f6f82b6bb28af4d9c8626d0">getLatch</a>, <a href="#ac72ebc430ef7dcf1791c66080ddedd9d">getPreheaderIP</a> and <a href="#a01560f4a4ff7bfc8a96bd406b6f17ea2">getTripCount</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Private Member Functions

### collectControlBlocks() {#acc965de7b820b3a86dae34b15b4eae02}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void CanonicalLoopInfo::collectControlBlocks (<a href="/web-llvm/docs/api/classes/llvm/smallvectorimpl">SmallVectorImpl</a>&lt; <a href="/web-llvm/docs/api/classes/llvm/basicblock">BasicBlock</a> * &gt; &amp; BBs)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Add the control blocks of this loop to <span class="doxyComputerOutput">BBs</span>.</p>


<p>This does not include any block from the body, including the one returned by <a href="#a47521ec347ef7b522745bf89e2e2d19a">getBody()</a>.</p>


<p>FIXME: This currently includes the Preheader and After blocks even though their content is (mostly) not under <a href="/web-llvm/docs/api/classes/llvm/canonicalloopinfo">CanonicalLoopInfo</a>'s control. Re-evaluated whether this makes sense.</p>


<p>Declaration at line 3529 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/frontend/include/llvm/frontend/openmp/ompirbuilder-h">OMPIRBuilder.h</a>, definition at line 9828 of file <a href="/web-llvm/docs/api/files/lib/lib/frontend/lib/frontend/openmp/ompirbuilder-cpp">OMPIRBuilder.cpp</a>.</p>

</div>
</div>

### mapIndVar() {#acd8accd2da5cd306a89efb53c1e0f7bc}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void CanonicalLoopInfo::mapIndVar (<a href="/web-llvm/docs/api/classes/llvm/function-ref">llvm::function_ref</a>&lt; <a href="/web-llvm/docs/api/classes/llvm/value">Value</a> *(<a href="/web-llvm/docs/api/classes/llvm/instruction">Instruction</a> *)&gt; Updater)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Replace all uses of the canonical induction variable in the loop body with a new one.</p>


<p>The intended use case is to update the induction variable for an updated iteration space such that it can stay normalized in the 0...tripcount-1 range.</p>


<p>The <span class="doxyComputerOutput">Updater</span> is called with the (presumable updated) current normalized induction variable and is expected to return the value that uses of the pre-updated induction values should use instead, typically dependent on the new induction variable. This is a lambda (instead of e.g. just passing the new value) to be able to distinguish the uses of the pre-updated induction variable and uses of the induction varible to compute the updated induction variable value.</p>


<p>Declaration at line 3550 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/frontend/include/llvm/frontend/openmp/ompirbuilder-h">OMPIRBuilder.h</a>, definition at line 9859 of file <a href="/web-llvm/docs/api/files/lib/lib/frontend/lib/frontend/openmp/ompirbuilder-cpp">OMPIRBuilder.cpp</a>.</p>

</div>
</div>

### setTripCount() {#a588e5d2b299d0090847ce7f3df2749ba}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void CanonicalLoopInfo::setTripCount (<a href="/web-llvm/docs/api/classes/llvm/value">Value</a> * TripCount)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Sets the number of loop iterations to the given value.</p>


<p>This value must be valid in the condition block (i.e., defined in the preheader) and is interpreted as an unsigned integer.</p>


<p>Declaration at line 3534 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/frontend/include/llvm/frontend/openmp/ompirbuilder-h">OMPIRBuilder.h</a>, definition at line 9847 of file <a href="/web-llvm/docs/api/files/lib/lib/frontend/lib/frontend/openmp/ompirbuilder-cpp">OMPIRBuilder.cpp</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Private Member Attributes

### Cond {#add606e5b781dc64d0ba4820809e8d88a}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">BasicBlock* llvm::CanonicalLoopInfo::Cond = nullptr</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 3517 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/frontend/include/llvm/frontend/openmp/ompirbuilder-h">OMPIRBuilder.h</a>.</p>

</div>
</div>

### Exit {#a2c2f33e4aac8c213794cb9fac93f8a6d}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">BasicBlock* llvm::CanonicalLoopInfo::Exit = nullptr</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 3519 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/frontend/include/llvm/frontend/openmp/ompirbuilder-h">OMPIRBuilder.h</a>.</p>

</div>
</div>

### Header {#a7a071723c44daf28c5226d0e270a9734}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">BasicBlock* llvm::CanonicalLoopInfo::Header = nullptr</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 3516 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/frontend/include/llvm/frontend/openmp/ompirbuilder-h">OMPIRBuilder.h</a>.</p>

</div>
</div>

### Latch {#a8ae42f9b63c65fda9fc05a85c37d470b}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">BasicBlock* llvm::CanonicalLoopInfo::Latch = nullptr</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 3518 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/frontend/include/llvm/frontend/openmp/ompirbuilder-h">OMPIRBuilder.h</a>.</p>

</div>
</div>

</div>

<hr/>

The documentation for this class was generated from the following files:

<ul>
<li><a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/frontend/include/llvm/frontend/openmp/ompirbuilder-h">OMPIRBuilder.h</a></li>
<li><a href="/web-llvm/docs/api/files/lib/lib/frontend/lib/frontend/openmp/ompirbuilder-cpp">OMPIRBuilder.cpp</a></li>
</ul>

<hr/>

<p class="doxyGeneratedBy">Generated via <a href="https://github.com/xpack/doxygen2docusaurus">doxygen2docusaurus</a> by <a href="https://www.doxygen.nl">Doxygen</a> 1.15.0.</p>

</div>
