---

# DO NOT EDIT!
# Automatically generated via doxygen2docusaurus by Doxygen.

slug: /api/classes/llvm/ivusers
custom_edit_url: null
toc_max_heading_level: 4
keywords:
  - doxygen
  - reference
  - class

---

<div class="doxyPage">

# The `IVUsers` Class Reference



## Declaration

<div class="doxyDeclaration">
class llvm::IVUsers { ... }
</div>

## Included Headers

<div class="doxyIncludesList">#include "<a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/analysis/ivusers-h">llvm/Analysis/IVUsers.h</a>"
</div>

## Public Member Typedefs Index

<table class="doxyMembersIndex">

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">typedef</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="/web-llvm/docs/api/namespaces/llvm/#a62ea5abc9af8e7ee394912e2617cf30f">ilist</a>&lt; <a href="/web-llvm/docs/api/classes/llvm/ivstrideuse">IVStrideUse</a> &gt;::iterator <a href="#ac4ea8771137797e80c4f56a3111e2397">iterator</a></td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">typedef</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="/web-llvm/docs/api/namespaces/llvm/#a62ea5abc9af8e7ee394912e2617cf30f">ilist</a>&lt; <a href="/web-llvm/docs/api/classes/llvm/ivstrideuse">IVStrideUse</a> &gt;::const_iterator <a href="#a1ac1243c7bc2878be52de359bd652680">const_iterator</a></td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#aade51f7d2ade94165429460adda9e063">IVStrideUse</a></td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a37e4d7bb727910e7d12a2439a6c069ca">IVUsers</a> (Loop *L, AssumptionCache *AC, LoopInfo *LI, DominatorTree *DT, ScalarEvolution *SE)</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a84ff868b90dce94cf9c8c504ff53cfad">IVUsers</a> (IVUsers &amp;&amp;X)</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a5d6ec66fa25d2a95429ee13159b90249">IVUsers</a> (const IVUsers &amp;)=delete</td>
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

## Public Operators Index

<table class="doxyMembersIndex">

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/ivusers">IVUsers</a> &amp;</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a59650f700bbcb2ad8c5bf22e6b353fd2">operator=</a> (IVUsers &amp;&amp;)=delete</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/ivusers">IVUsers</a> &amp;</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#af280755c00e32b58a9186e6dce5df3ef">operator=</a> (const IVUsers &amp;)=delete</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/loop">Loop</a> *</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a4d82eec6f6363e4d31660c31b6a85b8d">getLoop</a> () const</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#aaae0691d9859142f6bcfb992862e44a9">AddUsersIfInteresting</a> (Instruction *I)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>AddUsersIfInteresting - Inspect the specified <a href="/web-llvm/docs/api/classes/llvm/instruction">Instruction</a>. <a href="#aaae0691d9859142f6bcfb992862e44a9">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/ivstrideuse">IVStrideUse</a> &amp;</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a2c38dcaaa58a80d2005b912b1273a872">AddUser</a> (Instruction *User, Value *Operand)</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/scev">SCEV</a> *</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a729d7a4c47511beaaec595f1b85f7889">getReplacementExpr</a> (const IVStrideUse &amp;IU) const</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>getReplacementExpr - Return a <a href="/web-llvm/docs/api/classes/llvm/scev">SCEV</a> expression which computes the value of the OperandValToReplace of the given <a href="/web-llvm/docs/api/classes/llvm/ivstrideuse">IVStrideUse</a>. <a href="#a729d7a4c47511beaaec595f1b85f7889">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/scev">SCEV</a> *</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#af19a630344b862c4b06bca0e51d978cc">getExpr</a> (const IVStrideUse &amp;IU) const</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>getExpr - Return the expression for the use. <a href="#af19a630344b862c4b06bca0e51d978cc">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/scev">SCEV</a> *</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a5d599af3e44171ef73b8427c855b492e">getStride</a> (const IVStrideUse &amp;IU, const Loop *L) const</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="#ac4ea8771137797e80c4f56a3111e2397">iterator</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#aa73e72d96213b699b7656cef4a41fff7">begin</a> ()</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="#ac4ea8771137797e80c4f56a3111e2397">iterator</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a2206acfe0bf8df3750ce14311cc4963f">end</a> ()</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="#a1ac1243c7bc2878be52de359bd652680">const_iterator</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ad5fbdc714637c698896fcefa24a0bbfb">begin</a> () const</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="#a1ac1243c7bc2878be52de359bd652680">const_iterator</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#abbb9d0fddb05d7365547ec4b08f59ca9">end</a> () const</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#aff447b803e32fdf3e16156e9f6fb4249">empty</a> () const</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a1eed18775305b30aa90308d24cd7921b">isIVUserOrOperand</a> (Instruction *Inst) const</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a3df6da0991021b17f9180fb55105b6e8">releaseMemory</a> ()</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#afd7ddc6bb1068961b39278e6cf3190c9">print</a> (raw_ostream &amp;OS, const Module *=nullptr) const</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a04b694028e4949a1f3be58fa2c561756">dump</a> () const</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>dump - This method is used for debugging. <a href="#a04b694028e4949a1f3be58fa2c561756">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

</table>

## Private Member Attributes Index

<table class="doxyMembersIndex">

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/loop">Loop</a> *</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a35ee673b838679a8acc7e9d48ed0314e">L</a></td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ad2210a9aeb3bed422d65264c549f8fdd">AC</a></td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a7e937dc4951be6264daefd2abdb587d7">LI</a></td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a689308f3665ee8c2bc49d966e5e9d0db">DT</a></td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/scalarevolution">ScalarEvolution</a> *</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a4182d8f73b789f2d9e0d3286227a3413">SE</a></td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/smallptrset">SmallPtrSet</a>&lt; <a href="/web-llvm/docs/api/classes/llvm/instruction">Instruction</a> *, 16 &gt;</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a593d6e70e914ebc5950fcec82c1f6651">Processed</a></td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/namespaces/llvm/#a62ea5abc9af8e7ee394912e2617cf30f">ilist</a>&lt; <a href="/web-llvm/docs/api/classes/llvm/ivstrideuse">IVStrideUse</a> &gt;</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#afe21f100c5308cd992db37d5f237d127">IVUses</a></td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>IVUses - A list of all tracked IV uses of induction variable expressions we are interested in. <a href="#afe21f100c5308cd992db37d5f237d127">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/smallptrset">SmallPtrSet</a>&lt; <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/value">Value</a> *, 32 &gt;</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#abc30110b0ec49794c9fc08bc6e612ddb">EphValues</a></td>
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


<p>Definition at line 91 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/analysis/ivusers-h">IVUsers.h</a>.</p>


<div class="doxySectionDef">

## Public Member Typedefs

### const\_iterator {#a1ac1243c7bc2878be52de359bd652680}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">typedef ilist&lt;IVStrideUse&gt;::const_iterator llvm::IVUsers::const_iterator</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 142 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/analysis/ivusers-h">IVUsers.h</a>.</p>

</div>
</div>

### iterator {#ac4ea8771137797e80c4f56a3111e2397}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">typedef ilist&lt;IVStrideUse&gt;::iterator llvm::IVUsers::iterator</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 141 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/analysis/ivusers-h">IVUsers.h</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Friends

### IVStrideUse {#aade51f7d2ade94165429460adda9e063}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">friend class <a href="/web-llvm/docs/api/classes/llvm/ivstrideuse">IVStrideUse</a></td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">


<p>Definition at line 92 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/analysis/ivusers-h">IVUsers.h</a>.</p>


<p>Reference <a href="#aade51f7d2ade94165429460adda9e063">IVStrideUse</a>.</p>


<p>Referenced by <a href="#a2c38dcaaa58a80d2005b912b1273a872">AddUser</a>, <a href="#aaae0691d9859142f6bcfb992862e44a9">AddUsersIfInteresting</a>, <a href="#af19a630344b862c4b06bca0e51d978cc">getExpr</a>, <a href="#a729d7a4c47511beaaec595f1b85f7889">getReplacementExpr</a>, <a href="#a5d599af3e44171ef73b8427c855b492e">getStride</a>, <a href="#aade51f7d2ade94165429460adda9e063">IVStrideUse</a>, <a href="#a84ff868b90dce94cf9c8c504ff53cfad">IVUsers</a> and <a href="#afd7ddc6bb1068961b39278e6cf3190c9">print</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Public Constructors

### IVUsers() {#a37e4d7bb727910e7d12a2439a6c069ca}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">IVUsers::IVUsers (<a href="/web-llvm/docs/api/classes/llvm/loop">Loop</a> * L, <a href="/web-llvm/docs/api/classes/llvm/assumptioncache">AssumptionCache</a> * AC, <a href="/web-llvm/docs/api/classes/llvm/loopinfo">LoopInfo</a> * LI, <a href="/web-llvm/docs/api/classes/llvm/dominatortree">DominatorTree</a> * DT, <a href="/web-llvm/docs/api/classes/llvm/scalarevolution">ScalarEvolution</a> * SE)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Declaration at line 108 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/analysis/ivusers-h">IVUsers.h</a>, definition at line 251 of file <a href="/web-llvm/docs/api/files/lib/lib/analysis/ivusers-cpp">IVUsers.cpp</a>.</p>


<p>References <a href="#aaae0691d9859142f6bcfb992862e44a9">AddUsersIfInteresting</a>, <a href="/web-llvm/docs/api/structs/llvm/codemetrics/#a7e174506b52ad46ea1f746a7f727d999">llvm::CodeMetrics::collectEphemeralValues</a>, <a href="/web-llvm/docs/api/files/lib/lib/support/md5-cpp/#ac0eafdc9ee161b71e7af98af736952fd">I</a> and <a href="/web-llvm/docs/api/namespaces/llvm/#a92ca992e52dddc420f4b069cae06dfbe">llvm::isa</a>.</p>


<p>Referenced by <a href="#a5d6ec66fa25d2a95429ee13159b90249">IVUsers</a>, <a href="#a84ff868b90dce94cf9c8c504ff53cfad">IVUsers</a>, <a href="#af280755c00e32b58a9186e6dce5df3ef">operator=</a> and <a href="#a59650f700bbcb2ad8c5bf22e6b353fd2">operator=</a>.</p>

</div>
</div>

### IVUsers() {#a84ff868b90dce94cf9c8c504ff53cfad}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">llvm::IVUsers::IVUsers (<a href="/web-llvm/docs/api/classes/llvm/ivusers">IVUsers</a> &amp;&amp; X)</td>
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



<p>Definition at line 111 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/analysis/ivusers-h">IVUsers.h</a>.</p>


<p>References <a href="#aade51f7d2ade94165429460adda9e063">IVStrideUse</a>, <a href="#a37e4d7bb727910e7d12a2439a6c069ca">IVUsers</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#abfc9c7ecf70f66901e439f7c04ef3dbb">llvm::move</a> and <a href="/web-llvm/docs/api/files/lib/lib/tablegen/tablegenbackendskeleton-cpp/#ab60f28d7a141ac46ccc200176a1bca8b">X</a>.</p>

</div>
</div>

### IVUsers() {#a5d6ec66fa25d2a95429ee13159b90249}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">llvm::IVUsers::IVUsers (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/ivusers">IVUsers</a> &amp;)</td>
</tr>
</table>
</td>
<td class="doxyMemberLabelsRight">
<span class="doxyMemberLabels">
<span class="doxyMemberLabel delete">delete</span>
</span>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 118 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/analysis/ivusers-h">IVUsers.h</a>.</p>


<p>Reference <a href="#a37e4d7bb727910e7d12a2439a6c069ca">IVUsers</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Public Operators

### operator=() {#a59650f700bbcb2ad8c5bf22e6b353fd2}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">IVUsers &amp; llvm::IVUsers::operator= (<a href="/web-llvm/docs/api/classes/llvm/ivusers">IVUsers</a> &amp;&amp;)</td>
</tr>
</table>
</td>
<td class="doxyMemberLabelsRight">
<span class="doxyMemberLabels">
<span class="doxyMemberLabel delete">delete</span>
</span>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 119 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/analysis/ivusers-h">IVUsers.h</a>.</p>


<p>Reference <a href="#a37e4d7bb727910e7d12a2439a6c069ca">IVUsers</a>.</p>

</div>
</div>

### operator=() {#af280755c00e32b58a9186e6dce5df3ef}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">IVUsers &amp; llvm::IVUsers::operator= (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/ivusers">IVUsers</a> &amp;)</td>
</tr>
</table>
</td>
<td class="doxyMemberLabelsRight">
<span class="doxyMemberLabels">
<span class="doxyMemberLabel delete">delete</span>
</span>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 120 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/analysis/ivusers-h">IVUsers.h</a>.</p>


<p>Reference <a href="#a37e4d7bb727910e7d12a2439a6c069ca">IVUsers</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Public Member Functions

### AddUser() {#a2c38dcaaa58a80d2005b912b1273a872}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">IVStrideUse &amp; IVUsers::AddUser (<a href="/web-llvm/docs/api/classes/llvm/instruction">Instruction</a> * User, <a href="/web-llvm/docs/api/classes/llvm/value">Value</a> * Operand)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Declaration at line 129 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/analysis/ivusers-h">IVUsers.h</a>, definition at line 246 of file <a href="/web-llvm/docs/api/files/lib/lib/analysis/ivusers-cpp">IVUsers.cpp</a>.</p>


<p>Reference <a href="#aade51f7d2ade94165429460adda9e063">IVStrideUse</a>.</p>


<p>Referenced by <a href="#aaae0691d9859142f6bcfb992862e44a9">AddUsersIfInteresting</a>.</p>

</div>
</div>

### AddUsersIfInteresting() {#aaae0691d9859142f6bcfb992862e44a9}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool IVUsers::AddUsersIfInteresting (<a href="/web-llvm/docs/api/classes/llvm/instruction">Instruction</a> * I)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>AddUsersIfInteresting - Inspect the specified <a href="/web-llvm/docs/api/classes/llvm/instruction">Instruction</a>.</p>


<p>Inspect the specified instruction.</p>


<p>If it is a reducible <a href="/web-llvm/docs/api/classes/llvm/scev">SCEV</a>, recursively add its users to the IVUsesByStride set and return true. Otherwise, return false.</p>


<p>Declaration at line 127 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/analysis/ivusers-h">IVUsers.h</a>, definition at line 136 of file <a href="/web-llvm/docs/api/files/lib/lib/analysis/ivusers-cpp">IVUsers.cpp</a>.</p>


<p>References <a href="#a2c38dcaaa58a80d2005b912b1273a872">AddUser</a>, <a href="#aaae0691d9859142f6bcfb992862e44a9">AddUsersIfInteresting</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#ac4fc845f5ed92de63cd4474f128f5fc5">llvm::cast</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a7c46c742c31be54870e2038048e6b391">llvm::dbgs</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a6fb1355b48afff4e97045b546b5f6415">llvm::denormalizeForPostIncUse</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/arm/armslshardening-cpp/#ad467c4ab9119043f9b7750ab986be61a">DL</a>, <a href="/web-llvm/docs/api/files/lib/lib/support/md5-cpp/#ac0eafdc9ee161b71e7af98af736952fd">I</a>, <a href="/web-llvm/docs/api/classes/llvm/smallptrsetimpl/#a9d834ae3da8c62c2b668dada51335eb0">llvm::SmallPtrSetImpl&lt; PtrType &gt;::insert</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a92ca992e52dddc420f4b069cae06dfbe">llvm::isa</a>, <a href="/web-llvm/docs/api/files/lib/lib/analysis/ivusers-cpp/#a5a81ec50ef587462736e1ba010fab186">isInteresting</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a8601ff0320b6e29a13a2194200853425">llvm::isSafeToSpeculativelyExecute</a>, <a href="#aade51f7d2ade94165429460adda9e063">IVStrideUse</a>, <a href="/web-llvm/docs/api/files/lib/lib/analysis/ivusers-cpp/#acd81badac05008b8ec9f327167344baa">IVUseShouldUsePostIncValue</a>, <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/support/debug-h/#a196897517069dda1bdb549e24468f7d7">LLVM_DEBUG</a> and <a href="/web-llvm/docs/api/namespaces/llvm/#adb2ce7b0fb87c632dac34aa98feabb82">llvm::normalizeForPostIncUseIf</a>.</p>


<p>Referenced by <a href="#aaae0691d9859142f6bcfb992862e44a9">AddUsersIfInteresting</a> and <a href="#a37e4d7bb727910e7d12a2439a6c069ca">IVUsers</a>.</p>

</div>
</div>

### begin() {#aa73e72d96213b699b7656cef4a41fff7}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">iterator llvm::IVUsers::begin ()</td>
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



<p>Definition at line 143 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/analysis/ivusers-h">IVUsers.h</a>.</p>

</div>
</div>

### begin() {#ad5fbdc714637c698896fcefa24a0bbfb}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">const_iterator llvm::IVUsers::begin ()</td>
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



<p>Definition at line 145 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/analysis/ivusers-h">IVUsers.h</a>.</p>

</div>
</div>

### dump() {#a04b694028e4949a1f3be58fa2c561756}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">LLVM_DUMP_METHOD void IVUsers::dump ()</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>dump - This method is used for debugging.</p>

<p>Declaration at line 158 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/analysis/ivusers-h">IVUsers.h</a>, definition at line 292 of file <a href="/web-llvm/docs/api/files/lib/lib/analysis/ivusers-cpp">IVUsers.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/namespaces/llvm/#a7c46c742c31be54870e2038048e6b391">llvm::dbgs</a>, <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/support/compiler-h/#aa863693eef567397d9c292da5bf22d34">LLVM_DUMP_METHOD</a> and <a href="#afd7ddc6bb1068961b39278e6cf3190c9">print</a>.</p>

</div>
</div>

### empty() {#aff447b803e32fdf3e16156e9f6fb4249}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool llvm::IVUsers::empty ()</td>
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



<p>Definition at line 147 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/analysis/ivusers-h">IVUsers.h</a>.</p>

</div>
</div>

### end() {#a2206acfe0bf8df3750ce14311cc4963f}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">iterator llvm::IVUsers::end ()</td>
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



<p>Definition at line 144 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/analysis/ivusers-h">IVUsers.h</a>.</p>

</div>
</div>

### end() {#abbb9d0fddb05d7365547ec4b08f59ca9}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">const_iterator llvm::IVUsers::end ()</td>
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



<p>Definition at line 146 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/analysis/ivusers-h">IVUsers.h</a>.</p>

</div>
</div>

### getExpr() {#af19a630344b862c4b06bca0e51d978cc}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">const SCEV * IVUsers::getExpr (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/ivstrideuse">IVStrideUse</a> &amp; IU)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>getExpr - Return the expression for the use.</p>


<p>Returns nullptr if the result is not invertible.</p>


<p>Declaration at line 137 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/analysis/ivusers-h">IVUsers.h</a>, definition at line 336 of file <a href="/web-llvm/docs/api/files/lib/lib/analysis/ivusers-cpp">IVUsers.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/classes/llvm/ivstrideuse/#a6475dcea1bb00ad07700b96492896c59">llvm::IVStrideUse::getPostIncLoops</a>, <a href="#a729d7a4c47511beaaec595f1b85f7889">getReplacementExpr</a>, <a href="#aade51f7d2ade94165429460adda9e063">IVStrideUse</a> and <a href="/web-llvm/docs/api/namespaces/llvm/#a99237ea99bf8618b7d29b5ca6185069b">llvm::normalizeForPostIncUse</a>.</p>


<p>Referenced by <a href="#a5d599af3e44171ef73b8427c855b492e">getStride</a>.</p>

</div>
</div>

### getLoop() {#a4d82eec6f6363e4d31660c31b6a85b8d}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">Loop * llvm::IVUsers::getLoop ()</td>
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



<p>Definition at line 122 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/analysis/ivusers-h">IVUsers.h</a>.</p>

</div>
</div>

### getReplacementExpr() {#a729d7a4c47511beaaec595f1b85f7889}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">const SCEV * IVUsers::getReplacementExpr (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/ivstrideuse">IVStrideUse</a> &amp; IU)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>getReplacementExpr - Return a <a href="/web-llvm/docs/api/classes/llvm/scev">SCEV</a> expression which computes the value of the OperandValToReplace of the given <a href="/web-llvm/docs/api/classes/llvm/ivstrideuse">IVStrideUse</a>.</p>


<p>getReplacementExpr - Return a <a href="/web-llvm/docs/api/classes/llvm/scev">SCEV</a> expression which computes the value of the OperandValToReplace.</p>


<p>Declaration at line 133 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/analysis/ivusers-h">IVUsers.h</a>, definition at line 331 of file <a href="/web-llvm/docs/api/files/lib/lib/analysis/ivusers-cpp">IVUsers.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/classes/llvm/ivstrideuse/#a850ce8990175a8dc4e5a641df3db14aa">llvm::IVStrideUse::getOperandValToReplace</a> and <a href="#aade51f7d2ade94165429460adda9e063">IVStrideUse</a>.</p>


<p>Referenced by <a href="#af19a630344b862c4b06bca0e51d978cc">getExpr</a> and <a href="#afd7ddc6bb1068961b39278e6cf3190c9">print</a>.</p>

</div>
</div>

### getStride() {#a5d599af3e44171ef73b8427c855b492e}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">const SCEV * IVUsers::getStride (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/ivstrideuse">IVStrideUse</a> &amp; IU, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/loop">Loop</a> * L)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Declaration at line 139 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/analysis/ivusers-h">IVUsers.h</a>, definition at line 358 of file <a href="/web-llvm/docs/api/files/lib/lib/analysis/ivusers-cpp">IVUsers.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/files/lib/lib/analysis/ivusers-cpp/#a0566a3442b9159ce7b3a199bbc68c445">findAddRecForLoop</a>, <a href="#af19a630344b862c4b06bca0e51d978cc">getExpr</a> and <a href="#aade51f7d2ade94165429460adda9e063">IVStrideUse</a>.</p>

</div>
</div>

### isIVUserOrOperand() {#a1eed18775305b30aa90308d24cd7921b}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool llvm::IVUsers::isIVUserOrOperand (<a href="/web-llvm/docs/api/classes/llvm/instruction">Instruction</a> * Inst)</td>
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



<p>Definition at line 149 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/analysis/ivusers-h">IVUsers.h</a>.</p>

</div>
</div>

### print() {#afd7ddc6bb1068961b39278e6cf3190c9}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void IVUsers::print (<a href="/web-llvm/docs/api/classes/llvm/raw-ostream">raw_ostream</a> &amp; OS, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/module">Module</a> * M=nullptr)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Declaration at line 155 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/analysis/ivusers-h">IVUsers.h</a>, definition at line 265 of file <a href="/web-llvm/docs/api/files/lib/lib/analysis/ivusers-cpp">IVUsers.cpp</a>.</p>


<p>References <a href="#a729d7a4c47511beaaec595f1b85f7889">getReplacementExpr</a> and <a href="#aade51f7d2ade94165429460adda9e063">IVStrideUse</a>.</p>


<p>Referenced by <a href="#a04b694028e4949a1f3be58fa2c561756">dump</a>.</p>

</div>
</div>

### releaseMemory() {#a3df6da0991021b17f9180fb55105b6e8}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void IVUsers::releaseMemory ()</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Declaration at line 153 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/analysis/ivusers-h">IVUsers.h</a>, definition at line 295 of file <a href="/web-llvm/docs/api/files/lib/lib/analysis/ivusers-cpp">IVUsers.cpp</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Private Member Attributes

### AC {#ad2210a9aeb3bed422d65264c549f8fdd}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">AssumptionCache* llvm::IVUsers::AC</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 94 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/analysis/ivusers-h">IVUsers.h</a>.</p>

</div>
</div>

### DT {#a689308f3665ee8c2bc49d966e5e9d0db}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">DominatorTree* llvm::IVUsers::DT</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 96 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/analysis/ivusers-h">IVUsers.h</a>.</p>

</div>
</div>

### EphValues {#abc30110b0ec49794c9fc08bc6e612ddb}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">SmallPtrSet&lt;const Value *, 32&gt; llvm::IVUsers::EphValues</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 105 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/analysis/ivusers-h">IVUsers.h</a>.</p>

</div>
</div>

### IVUses {#afe21f100c5308cd992db37d5f237d127}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">ilist&lt;IVStrideUse&gt; llvm::IVUsers::IVUses</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>IVUses - A list of all tracked IV uses of induction variable expressions we are interested in.</p>

<p>Definition at line 102 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/analysis/ivusers-h">IVUsers.h</a>.</p>

</div>
</div>

### L {#a35ee673b838679a8acc7e9d48ed0314e}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">Loop* llvm::IVUsers::L</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 93 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/analysis/ivusers-h">IVUsers.h</a>.</p>

</div>
</div>

### LI {#a7e937dc4951be6264daefd2abdb587d7}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">LoopInfo* llvm::IVUsers::LI</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 95 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/analysis/ivusers-h">IVUsers.h</a>.</p>

</div>
</div>

### Processed {#a593d6e70e914ebc5950fcec82c1f6651}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">SmallPtrSet&lt;Instruction*, 16&gt; llvm::IVUsers::Processed</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 98 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/analysis/ivusers-h">IVUsers.h</a>.</p>

</div>
</div>

### SE {#a4182d8f73b789f2d9e0d3286227a3413}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">ScalarEvolution* llvm::IVUsers::SE</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 97 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/analysis/ivusers-h">IVUsers.h</a>.</p>

</div>
</div>

</div>

<hr/>

The documentation for this class was generated from the following files:

<ul>
<li><a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/analysis/ivusers-h">IVUsers.h</a></li>
<li><a href="/web-llvm/docs/api/files/lib/lib/analysis/ivusers-cpp">IVUsers.cpp</a></li>
</ul>

<hr/>

<p class="doxyGeneratedBy">Generated via <a href="https://github.com/xpack/doxygen2docusaurus">doxygen2docusaurus</a> by <a href="https://www.doxygen.nl">Doxygen</a> 1.14.0.</p>

</div>
